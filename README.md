# Data Privacy Enhancement RPA with Power Automate Desktop

## Introduction

Welcome to the Data Privacy Enhancement RPA project with Power Automate Desktop. This repository houses an RPA workflow designed to bolster data privacy by encrypting sensitive information, such as names and NRIC, before securely transferring it. This solution is particularly valuable for professionals in data analytics, data management, and AML KYC (Anti-Money Laundering and Know Your Customer) domains where data privacy is of utmost importance.

## Background

In the realms of data analytics, data management, and AML KYC, discussions about data privacy are commonplace. Data management professionals prioritize customer privacy and argue against accessing or querying personally identifiable information (PII) without proper authorization. AML KYC experts, however, primarily focus on name screening, which occasionally results in RFIs (Requests for Information) for wire transfers being blocked due to data privacy laws.

## Features

- **Encryption**: Utilizes the AES encryption method to encrypt each row of content, safeguarding sensitive information.

- **Secure Transfer**: Facilitates secure transfer of encrypted data between sender and recipient, often packaged within Excel files.

- **Decryption**: Empowers recipients to decrypt data using the provided decryption method.

## How It Works

1. **Encryption**: The RPA workflow employs AES encryption to secure sensitive data, such as names and NRIC.

2. **Secure Transfer**: Encrypted data can be safely transferred between sender and recipient, often within Excel files.

3. **Decryption**: To access the original data, the recipient can utilize the decryption method outlined in the accompanying documentation.

Compared to traditional methods like zipping and unzipping data using software like Winzip, this RPA workflow provides an additional layer of security and privacy for sensitive information.

## Getting Started

### Prerequisites

- Ensure you have [Power Automate Desktop](https://powerautomate.microsoft.com/en-us/robotic-process-automation/) installed on your machine.

