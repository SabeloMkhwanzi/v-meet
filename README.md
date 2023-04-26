**Huddle01 x FVM - Video Jam**

V-Meet: Virtual Meeting Room is a decentralized application (dApp) that enables users to create and host virtual meetings on the blockchain. Participants can join scheduled meetings using their unique digital identities and interact in real-time through video, audio, and chat functionalities. The dApp utilizes web3 technologies, such as smart contracts and blockchain, to provide a secure and transparent platform for hosting online meetings.

1. V-meet is a platform that enables users to purchase or subscribe to content (such as music, books, and videos) directly from content creators as NFTs (Non-Fungible Tokens).

2. Users can buy content NFTs or subscribe with Subscription NFTs, with the fees going directly to the creators. Notifications are sent to users when new content is created, and subscribers can schedule calls with creators.

3. V-meet empowers creators to sell their content directly to users without intermediaries. Users gain ownership of the content with NFT access, and the content is stored on IPFS/Filecoin for secure and decentralized distribution.

_How its Made_

- Filecoin Hyperspace Network: to deploy content NFTs (ERC1155), and subscription NFTs (ERC721)

- Lighthouse SDK: For encryption and token-gated access of content by users/subscribers.

- Huddle01 SDK: For video calling with content creators

- Push Protocol SDK: For sending notifications to users on creation of new content by the creators

## Getting Started

First, run the development server:

```bash
git clone https://github.com/SabeloMkhwanzi/v-meet

npm run dev
# or
yarn dev
# or
pnpm dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.
