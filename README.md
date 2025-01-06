
#  Transocean

## Project Overview

This project aims to create a decentralized platform for identifying and tracking the ports visited by ships during their journeys. By utilizing blockchain technology, the platform ensures transparency and immutability of data, providing a reliable and verifiable record of the ship's journey. Upon launching, each ship is registered with a unique identifier, and its journey details are recorded as it visits various ports, allowing easy traceability and accountability.

## Features

- **Ship Identification**: Each ship is registered with a unique identifier upon launch.
- **Port Tracking**: Records the ports a ship visits along its journey.
- **Blockchain Integration**: Data is stored securely on the blockchain, ensuring transparency and immutability.
- **Decentralized Platform**: No central authority controlling the platform, enabling trustless interactions.
- **Public Accessibility**: Anyone can view the journey and port history of a ship.

## Deployment

Transocean platform is now live and accessible at:

**Deployment Link**: ([Transocean - Blockchain-Based Ship Tracking Platform](https://transocean.vercel.app/))

Explore the platform to register ships, track their journeys, and access a transparent, immutable record of every port visited. All data is securely stored on the blockchain, ensuring full traceability and trust in the system.


## Getting Started

### Prerequisites

Before you start, ensure you have the following installed on your machine:

- Node.js (v16 or later)
- npm or yarn
- Blockchain wallet (e.g., MetaMask)

### Installation

1. **Clone the repository**:
    ```bash
    git clone https://github.com/WeTranscend-labs/FE-PortTrack.git
    cd FE-PortTrack
    ```

2. **Install Node.js dependencies**:
    ```bash
    npm install
    ```
3. Configure environment variables:
   - Create a `.env` file in the root directory.
   - Add the following variables:
     ```env
     NEXT_PUBLIC_APP_NAME=YourAppName
	 NEXT_PUBLIC_WALLET_CONNECT_PROJECT_ID=your-wallet-connect-project-id
	 NEXT_PUBLIC_CONTRACT_ADDRESS=your-contract-address
     ```

5. **Start the platform**:
    ```bash
    npm run dev
    ```

## Technologies Used

- **Frontend**: Next.js, TypeScript, Tailwind CSS
- **Smart Contracts Language**: Solidity
- **Blockchain Interaction**: Ethers.js, Wagmi, Viem
- **Text Editor**: TinyMCE React
- **Others**: React Hook Form, React Query, Zod

## Contributing

We welcome contributions! If you have an idea to improve the platform, feel free to fork the repository, create a branch, and submit a pull request. Please follow these steps:

1. Fork the project.
2. Create a new branch for your feature or bug fix.
3. Commit your changes.
4. Push your changes to your fork.
5. Open a pull request to the main repository.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.


