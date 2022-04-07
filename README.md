# Public smart contracts

Even though all public contracts' source code will be published
on Bscscan, this repository acts as a centralized place
for people to read and review those contracts more easily.

This repository also contains official addresses of OasisDAO's contracts.

*Note: Some contract logics are not fully decentralized as of now.
After the development is done, all those logics will be locked
so no changes can be made and full decentralization would be achieved.*

### OAS(Oasis) contract

This contracts holds OasisDAO's OAS data and is ERC-20/BEP-20 compliant.

* Source code: [Token_Gold_v3.sol](contracts/oas/Token_Gold_v3.sol)
* MainNet address: <a href="https://bscscan.com/address/0x10c3137762816b4f9bba18d8ace66edb20aba544" target="_blank">0x10c3137762816b4f9bba18d8ace66edb20aba544</a>

### OG(Oasis Gold) contract

This contracts holds OasisDAO's OG data and is ERC-20/BEP-20 compliant.

* Source code: [Token_Silver_v3.sol](contracts/og/Token_Silver_v3.sol)
* MainNet address: <a href="https://bscscan.com/address/0x11118681b271694e3d1730f4f29e63af05cf2180" target="_blank">0x11118681b271694e3d1730f4f29e63af05cf2180</a>

### OG claim contract

The contract allows players to use the authorization information provided by the OasisDAO system to complete the transfer of OG assets under their own accounts in the OasisDAO system to the Binance Smart Chain, which is based on EIP712 (Sign-Typed-Data-v4) to achieve offline signature and online verification..

* Source code: [Token_Silver_Claim_v1.sol](contracts/og/Token_Silver_Claim_v1.sol)
* MainNet address: <a href="https://bscscan.com/address/0x1563fa3436aecd9b8481bbe2960b59e269a1ed86" target="_blank">0x1563fa3436aecd9b8481bbe2960b59e269a1ed86</a>

### OC(Oasis City) contract

This contracts holds OasisDAO's OC data and is ERC-721/BEP-721 compliant.

* Source code: [Token_NFT_v2.sol](contracts/nft/Token_NFT_v2.sol)
* MainNet address: <a href="https://bscscan.com/address/0xce49df8f1c55ac7a796748aa8dd20c1a9048cc80" target="_blank">0xce49df8f1c55ac7a796748aa8dd20c1a9048cc80</a>

### OC mint contract

This The contract allows players to use the authorized signature provided by the OasisDAO system to mint OC assets on the Binance Smart Chain, which is based on EIP712 (Sign-Typed-Data-v4) to achieve offline signature and online verification.

* Source code: [AxieCore.sol](contracts/nft/Token_NFT_Mint_v1.sol)
* MainNet address: <a href="https://bscscan.com/address/0x5c14ce272a488673815a1b5aacab9e560c34e493" target="_blank">0x5c14ce272a488673815a1b5aacab9e560c34e493</a>

### OC trade contract

The contract allows players to use the authorized signatures provided by the OasisDAO system to buy OC assets listed for sale by other players using BNB on the Binance Smartchain, which is based on EIP712 (Sign-Typed-Data-v4) for offline signature and online verification.

* Source code: [Token_NFT_Trade_v1.sol](contracts/nft/Token_NFT_Trade_v1.sol)
* MainNet address: <a href="https://bscscan.com/address/0xffe01afd96af9dbd8acdeb8ac064c9876db455c3" target="_blank">0xffe01afd96af9dbd8acdeb8ac064c9876db455c3</a>
