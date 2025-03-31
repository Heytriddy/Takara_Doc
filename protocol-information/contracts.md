---
description: Takara智能合约地址 Takara Smart Contract Addresses
---

# 📜 合约信息

<figure><img src="../.gitbook/assets/1224 1h.png" alt=""><figcaption></figcaption></figure>

### **核心协议合约 Core Protocol Contracts**

| 名称                   | 合约地址                                     |描述                                              |
| ---------------------- | -------------------------------------------- | ------------------------------------------------- |
| **Comptroller**        | `0x56A171Acb1bBa46D4fdF21AfBE89377574B8D9BD` | Takara Lend 的风险管理与治理                      |
| **Unitroller**         | `0x71034bf5eC0FAd7aEE81a213403c8892F3d8CAeE` | Comptroller 合约的代理             |
| **MarketState**        | `0x323917A279B209754B32Ab57a817c64ECfE2AF40` | 借贷市场当前状态跟踪   |
| **MRD Proxy**          | `0x68A92Be349d48766128C0Ae893Fc391859F9BC11` | 管理市场交互的主代理合约 |
| **MRD Implementation** | `0x059798f39461e17047B6D2AD6AAE4d3a0dd9Dc82` | MRD 代理合约的逻辑实现               |
| **MRD Proxy Admin**    | `0x8DF1265bFb778fFD08341c63e7C67367c0a60288` | 管理协议升级的管理员合约        |

***

### **预言机 Oracles**

| 名称                  | 合约地址                                      | 描述                                          |
| --------------------- | -------------------------------------------- | ---------------------------------------------------- |
| **Price Feed Oracle** | `0xD6a275072dceC8a319c0C7178951A0CF9DCC0447` | 为协议风险管理提供资产定价  |

***

### **利率模型 Interest Rate Models**

| 名称                          | 合约地址                                     | 描述                              |
| ----------------------------- | -------------------------------------------- | ---------------------------------------- |
| **Jump Rate Model (USDC)**    | `0xED908ab644212969249bc7B167e3A2DF30709E1e` | USDC 出借的利率模型    |
| **Jump Rate Model (USDT)**    | `0x692D0bF5112B221AB14C5DC8C2159DDD87FF196B` | USDT 出借的利率模型    |
| **Jump Rate Model (WSEI)**    | `0x52196Ff255aA200552B5d24d56A725B0e206a26b` | WSEI 出借的利率模型   |
| **Jump Rate Model (fastUSD)** | `0xc6c06859d6caEF79a6E750EBc43Dd2dF63291aA2` | fastUSD 出借的利率模型 |
| **Jump Rate Model (iSEI)**    | `0xa282a20B9baB553D434faEC7D473C08B2e8D88FE` | iSEI 出借的利率模型 |

***

### **借贷市场合约（tTokens） Lending Market Contracts (tTokens)**

| 名称         | 合约地址                                     | 描述                                  |
| ------------ | -------------------------------------------- | -------------------------------------------- |
| **tSEI**     | `0xA26b9BFe606d29F16B5Aecf30F9233934452c4E2` | SEI 存款的计息代币     |
| **tUSDC**    | `0xC3c9e322F4aAe352ace79D0E62ADe3563fB86e87` | USDC 存款的计息代币    |
| **tUSDT**    | `0xc68351B9B3638A6f4A3Ae100Bd251e227BbD7479` | USDT 存款的计息代币   |
| **tfastUSD** | `0x92e51466482146E71b692ced2265284968E8B3d6` | fastUSD 存款的计息代币|
| **tiSEI**    | `0xda642A7821E91eD285262fead162E5fd17200429` | iSEI 存款的计息代币  |

***

### **基础资产 Underlying Assets**

| 名称        | 合约地址                                      | 描述                     |
| ----------- | -------------------------------------------- | -------------------------------- |
| **USDC**    | `0x3894085Ef7Ff0f0aeDf52E2A2704928d1Ec074F1` | Circle’s USD 稳定币       |
| **USDT**    | `0xB75D0B03c06A926e488e2659DF1A861F860bD3d1` | Tether’s USD 稳定币      |
| **WSEI**    | `0xE30feDd158A2e3b13e9badaeABaFc5516e95e8C7` | Wrapped SEI                     |
| **fastUSD** | `0x37a4dD9CED2b19Cfe8FAC251cd727b5787E45269` | Synthetic USD-pegged 稳定币 |
| **iSEI**    | `0x5Cf6826140C1C56Ff49C808A1A75407Cd1DF9423` | SEI 计息资产      |
