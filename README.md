# PLAZA FINANCE BOT
![BANNER PLAZA FINANCE](image/image-1.png)

Plaza 是一个基于 Base 的链上债券和杠杆平台。

Plaza 是一个由一组 Solidity 智能合约构建的可编程衍生品平台，运行在 Base 上。它提供了两个核心产品：bondETH 和 levETH，分别是 ETH 流动质押衍生品（LSTs）和流动再质押衍生品（LRTs）池的可编程衍生品，如 wstETH。用户可以存入像 wstETH 这样的底层池资产，并获得相应的 levETH 或 bondETH，这些代币以 ERC20 代币的形式表示。这些代币可以与 DEX、借贷市场、再质押平台等协议进行组合使用。

![banner](image/image.png)

- 网站：[https://testnet.plaza.finance/](https://testnet.plaza.finance/rewards/JL4590xVLSix)
- Twitter：[@plaza_finance](https://x.com/plaza_finance)

## 功能

- **自动每日交易**
- **自动领取水龙头奖励**
- **自动生成新钱包**
- **向现有地址发送资金**
- **所有钱包信息保存在 wallets.json 中**

## 必要条件

- **Node.js**：确保已安装 Node.js。
- **npm**：确保已安装 npm。
- **钱包必须在 eth/base/arb 主网上至少有 $1 才能获取水龙头奖励**
- **使用“自动发送”功能将资金发送到现有钱包**：每个地址发送 `0.0003` ETH

## 安装步骤

1. 克隆代码仓库：
   ```bash
   git clone https://github.com/Zlkcyber/plazafintot.git
   cd plazafintot
   ```

2. 安装依赖：
   ```bash
   npm install
   ```

3. 设置：创建新钱包
   ```bash
   npm run create
   ```

4. 附加功能： 

- 向现有地址发送资金
    ```bash
    npm run autosend
    ```

- 使用代理（可选）：在 `proxy.txt` 文件中粘贴代理，每行一个代理。
    ```bash
    nano proxy.txt
    ```
    格式：`http://user:password@ip:port`

5. 运行脚本：
   ```bash
   npm run start
   ```

## ![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)

该项目采用 [MIT 许可协议](LICENSE)。
