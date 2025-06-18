# Casa Monarca – Secure Data Protection with Cryptography

A project to implement a **secure web application** for managing sensitive questionnaires and personal data, using advanced encryption to protect the information of migrants and vulnerable individuals. The solution was developed for the NGO [Casa Monarca](https://www.casamigrante.org/).

## Main Features

- **Encryption of sensitive data** using AES (Advanced Encryption Standard).
- **Hierarchical user and access management** (roles with different permissions).
- **Secure cloud storage** (AWS Redshift) and encrypted JSON format.
- **Administration panel** for aggregate dashboards and individual technical reports.
- **Compliance with privacy regulations** (GDPR and Mexican Federal Law on Personal Data Protection).
- **Incident response plan** and continuous security recommendations.

## Technologies Used

- **Python**
- **Streamlit** (web frontend)
- **PyCrypto** (AES encryption)
- **SQL** (database management)
- **AWS Redshift** (cloud storage)
- **Pandas** (data processing)
- **Plotly Express** (data visualization)

## System Overview

1. **Data collection:** Digital questionnaires gather sensitive information from migrants.
2. **Data transformation & encryption:** Data is processed and encrypted with AES before storage.
3. **Secure storage:** Encrypted data is saved in JSON format in the cloud.
4. **Access management:** Login system with role-based control (user, supervisor, admin).
5. **Visualization:** Dashboards for quantitative monitoring and individual technical reports.
6. **Decryption:** Only authorized users with the private key can access the original data.


