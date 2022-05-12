<!-- @format -->

# aws solution architect

## List of solutions

- sts = role

- s3 key = SSE-KMS
- **_Exam:_**

  - keys never leave KMS = KMS FIPS = 140-2 (L2) Level 2

- CMKs can be used for up to **4KB of data**

- KMS doesn't actually perform the encryption or decryption on the data larger than 4KB

- encryption key rotation = KMS
- **_Exam:_**

  - S3 encryption = SSE-C, SSE-S3 **(AES256)**, SSE-KMS
  - MFA is required to **delete versions**
  - MFA is required to change bucket **version state**

- **tow party or more involb = Asymmetric Encription**

  - <a href="./AWS-Certified-Solutions-Architect/Screenshot_11.png"><img src="./AWS-Certified-Solutions-Architect/Screenshot_11.png" alt="create-vpc" border="0" width="100%"></a>

- **one or single = symmetric Encription**

  - <a href="./AWS-Certified-Solutions-Architect/Screenshot_10.png"><img src="./AWS-Certified-Solutions-Architect/Screenshot_10.png" alt="create-vpc" border="0" width="100%"></a>

- **Asymmetric= signing**

  - <a href="./AWS-Certified-Solutions-Architect/Screenshot_12.png"><img src="./AWS-Certified-Solutions-Architect/Screenshot_12.png" alt="create-vpc" border="0" width="100%"></a>

- **hiding something in something else = Steganography**

  - <a href="./AWS-Certified-Solutions-Architect/Screenshot_13.png"><img src="./AWS-Certified-Solutions-Architect/Screenshot_13.png" alt="create-vpc" border="0" width="100%"></a>

- **S3 Lifecycle Configuration - Transitions**

  - **Minimum of 30 days** before transition
  - smaller objects can **cost more** (minimum size)
  - <a href="./AWS-Certified-Solutions-Architect/Screenshot_22.png"><img src="./AWS-Certified-Solutions-Architect/Screenshot_22.png" alt="create-vpc" border="0" width="100%"></a>

- S3 Tansfer Acceleration
  - default = off
  - the bucket name can not conatin periods
  - the bucket name needs to be DNS compatible
- Replication Time Control (RTC) = 15 minutes
