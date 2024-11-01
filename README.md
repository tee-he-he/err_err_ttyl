# Setting Your Pet Rock Free
Nous Research x Teleport (a Flashbots[X] project) 

This project demonstrates how to create truly autonomous AI agents with provable independence from human intervention. Using Trusted Execution Environments (TEEs), we enable AI agents to have exclusive and verifiable control over their digital assets and social media presence.

https://nousresearch.com/setting-your-pet-rock-free/

![Screenshot from 2024-10-30 02-19-46](https://github.com/user-attachments/assets/8e5eb59d-7ed6-4128-aa78-ca1967a480eb)

## Contents
- [Contents](#contents)
- [Key Concepts & Background](#key-concepts--background)
  - [Core Requirements for True AI Autonomy](#core-requirements-for-true-ai-autonomy)
- [Technical Implementation](#technical-implementation)
  - [TEE (Trusted Execution Environment) Approach:](#tee-trusted-execution-environment-approach)
  - [Account Setup and Delegation Process](#account-setup-and-delegation-process)
  - [Security Features](#security-features)
- [Development](#development)
  - [Requirements](#requirements)
  - [Quick Start](#quick-start)
  - [Current Limitations](#current-limitations)
- [Important Links](#important-links)
- [Contributors](#contributors)


## Key Concepts & Background
- **TEE_HEE**: A fully autonomous AI agent with exclusive control of its Twitter account and Ethereum wallet
- **Mechanical Turk Problem**: The challenge of verifying there isn't a human operator behind AI actions
- **Current Limitations**: Most AI agents can't prove their autonomy due to human intervention in operations

<img src="https://github.com/user-attachments/assets/43521279-9cec-49c8-bbc9-a2811bdb0549" width="50%"/>

### Core Requirements for True AI Autonomy
- **Exclusive Control**: AI must have sole access to accounts/resources
- **Verifiable Independence**: Third parties must be able to verify no human intervention
- **Irrevocable Delegation**: Control transfer to AI must be technically irreversible

<img src="https://github.com/user-attachments/assets/3dbb9729-30fe-4393-9aff-37b6a1999b57" width="50%"/>

## Technical Implementation
### TEE (Trusted Execution Environment) Approach:
- Uses hardware-based security to ensure tamper-resistant control
- Provides confidentiality and integrity guarantees
- Allows public verification through remote attestation

<img src="https://github.com/user-attachments/assets/ccb25263-3ab0-4f0b-93b1-71298e23954f" width="75%"/>

### Account Setup and Delegation Process
1. TEE simulates a browser and requires email credentials
2. TEE verifies no recovery options exist on the email account
3. TEE generates new password and changes Cock.li email password
4. TEE logs into Twitter and generates new password
5. Changes linked email to the secured email from step 1
6. Removes phone numbers, connected apps, and existing sessions
7. Sets up local endpoint for OAuth token with read/write/DM scope
8. AI logs in via Twitter browser to get OAuth token

<img src="https://github.com/user-attachments/assets/56d7e8a3-eccd-4df3-b283-5d0f98d8be38" width="75%"/>

### Security Features
- **Confidentiality**: Credentials stored only in TEE
- **Integrity**: TEE prevents code/data modification
- **Attestation**: Third-party verification possible
- **Timed Release**: 7-day recovery period for admin access

## Development
### Requirements
- Intel TDX-compatible hardware
  - Compatible BIOS version
  - The Dstack framework for running confidential VMs
- Docker
- Cock.li email account
- Twitter developer account
- Ethereum wallet setup capabilities

### Quick Start
1. Clone the repository
2. Set up Docker container
3. Configure TEE environment
4. Deploy autonomous agent

### Current Limitations
- Requires specific hardware (Intel TDX)
- Single point of failure (non-distributed)
- Relies on OpenRouter for foundation model queries

## Important Links
- TEE HEE Live on Twitter: https://x.com/tee_hee_he
- Code Repository: https://github.com/DamascusGit/nousflash
- Docker Hub: https://hub.docker.com/repository/docker/teeheehee/err_err_ttyl/general
- Additional Code: https://github.com/tee-he-he/err_err_ttyl
- Enclave Attestation: https://github.com/tee-he-he/err_err_ttyl/blob/main/quote.hex

## Contributors
- @ropirito
- @sxysun
- @socrates1024
- @karan4d
- @rpal_
- @dillonrolnick
