
# Linsg — Secure Messaging on Linera

## Description

Linsg is a Web3 application that provides a secure, decentralized messaging platform. It allows users to communicate directly while maintaining data privacy, confidentiality, and ownership of messages using the Linera Protocol.

## Inspiration

With the advancement of Web3, there is a growing need for communication systems that maintain data privacy and enable direct, decentralized communication. Linsg leverages Linera and microchains to make this vision a reality, ensuring secure and private communication without centralization.

## What it does

Linsg replicates the functionality of popular messaging apps like WhatsApp or Telegram, but on a decentralized Web3 platform. Users can send and receive text messages directly, with the assurance that their data is private and fully owned by them.

## How we built it

Linsg was built using the Linera microchains framework, with the core functionality implemented in Rust. The development and testing were carried out in a cloud environment on an Ubuntu Server hosted on Azure. This setup ensured scalability and robustness during the development phase.

## Challenges we ran into

- Iterating multiple times to deploy Linera on the server, facing challenges with disk space and memory constraints.
- Overcoming the learning curve associated with Rust and the Linera SDK, especially with no prior experience in Rust.

## Accomplishments that we're proud of

- Successfully creating a functional demo in a short period despite initial challenges and lack of experience with Rust.
- Demonstrating the potential of Linera microchains for secure, decentralized messaging.

## What we learned

- Gained in-depth knowledge of the Linera framework and the advantages of microchains for decentralized applications.
- Acquired proficiency in Rust, understanding its benefits and challenges in building Web3 applications.

## What's next for Linsg

- Developing a user-friendly interface for both web and mobile platforms to enhance accessibility and user experience.
- Expanding Linsg into a comprehensive product with additional features and improvements.
- Exploring the possibility of transforming Linsg into a startup to bring decentralized messaging to a broader audience.

## Deployment

### Prerequisites

- Install Rust
- Install Linera
- Install Node.js

### Steps

1. **Start Local Network**
   Initialize local variables `LINERA_WALLET` and `LINERA_STORAGE`:
   ```bash
   linera net up
   ```

2. **Clone the Repository**
   Clone this repository to your local machine:
   ```bash
   git clone <repository-url>
   ```

3. **Run Deployment Script**
   Navigate to the working directory and execute the deployment script:
   ```bash
   ./scripts/simple.sh <working directory>
   ```
   Example:
   ```bash
   ./scripts/simple.sh /tmp/.tmpguVRWj
   ```

4. **Start Frontend**
   Navigate to the frontend directory, install dependencies, and start the development server:
   ```bash
   cd frontend
   npm install
   npm run dev
   ```

5. **Enjoy**
   Open your browser and enjoy the application.

## About

Linsg — secure messaging system on Linera

