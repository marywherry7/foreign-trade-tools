# 如何创建及设置 OKX API Key

本指南将引导您如何设置 OKX API Key，以便与 Bitsgap 平台实现连接。OKX 提供两种 API 调用方式：**OKX 快速 API** 和 **手动连接**。请选择最适合您需求的方法，以便顺利完成配置。关键词：OKX、API Key、快速 API、手动连接、Bitsgap。

🚀 与 OKX 一起开启您的加密货币之旅！零手续费交易，使用最先进的 Web3 功能，加入数百万全球交易者的行列。新用户可获得高达 100 USDT 的独家欢迎奖金！今天就与世界领先的数字资产平台一起开始您的交易冒险吧。

👉 OKX 新人限时优惠，最高可领取 100 USDT 奖励 ： [OKX活动页面](https://bit.ly/OKXe) | [国内镜像地址（免翻墙）](https://bit.ly/okX)

---

## OKX 快速 API

**OKX 快速 API** 使用 OAuth 2.0 进行快速且安全的集成，确保您与 Bitsgap 平台的无缝连接。

1. 打开 **交易 > 期货** 页面，并点击设置图标。
2. 确保 **账户模式** 设置为“单一币种保证金”，**持仓模式** 设置为“一向持仓”。
3. 为期货交易，我们建议采用 **逐仓保证金模式** 以降低风险。
4. **选择 OKX 和快速连接**  
   - 从列表中选择 OKX，然后点击 **快速连接** 后的 [Connect]（纯文本提示）。
5. **授权权限**  
   - 在 OKX 网站上输入您的账户信息并登录，随后授权 Bitsgap 请求的交易权限（不涉及个人数据）。
6. **连接校验**  
   - 授权完成后，系统将自动返回 Bitsgap 平台，您将在 **My Exchanges** 中看到 OKX（纯文本显示为“已连接”状态）及您的交易余额。

![设置步骤图1](https://i.bitsgap.com/hc/article_attachments/18009112892700)
![设置步骤图2](https://i.bitsgap.com/hc/article_attachments/18009112893212)
![设置步骤图3](https://i.bitsgap.com/hc/article_attachments/18009117562780)
![设置步骤图4](https://i.bitsgap.com/hc/article_attachments/18009112893980)
![设置步骤图5](https://i.bitsgap.com/hc/article_attachments/18009117566364)
![设置步骤图6](https://i.bitsgap.com/hc/article_attachments/18009117567900)
![权限授权图](https://i.bitsgap.com/hc/article_attachments/18009117568284)
![授权完成图](https://i.bitsgap.com/hc/article_attachments/18009117569180)
![连接校验图](https://i.bitsgap.com/hc/article_attachments/18009117569308)

---

## 手动连接

若您更倾向于手动配置，请参照以下步骤操作：

1. （可选）**配置期货账户**  
   - 为期货交易，请按照 **快速 API** 中的步骤进行账户配置。
2. **前往 API 管理页面**  
   - 在账户设置中进入 **API 管理** 页面。
3. **创建 V5 API Key**  
   - 点击 [Create V5 API Key] 按钮，并选择 **关联第三方应用**，在列表中选择 **Bitsgap**。
4. **命名并配置 API 权限**  
   - 为 API key 命名，创建一个安全的 **Passphrase** 并妥善保存。  
   - 启用以下权限：  
     - **读取**：开启  
     - **交易**：开启  
   - 完成安全验证并确认设置。
5. **复制 API 和 Secret Keys**  
   - 将生成的 API key 和 Secret key 妥善保存。
6. **连接到 Bitsgap**  
   - 选择 OKX，输入 API key、Secret key 与 Passphrase，然后点击 [Connect]（纯文本提示）。
7. **最终连接校验**  
   - 检查 OKX 是否以 **已连接** 状态显示在 **My Exchanges** 中，并确认交易余额信息无误。

![手动连接图1](https://i.bitsgap.com/hc/article_attachments/18009117570204)
![手动连接图2](https://i.bitsgap.com/hc/article_attachments/18009117570844)
![手动连接图3](https://i.bitsgap.com/hc/article_attachments/18009117571484)
![手动连接图4](https://i.bitsgap.com/hc/article_attachments/18009117571868)
![手动连接图5](https://i.bitsgap.com/hc/article_attachments/18009112900636)
![手动连接图6](https://i.bitsgap.com/hc/article_attachments/18009112901020)
![手动连接图7](https://i.bitsgap.com/hc/article_attachments/18009112901404)
![手动连接图8](https://i.bitsgap.com/hc/article_attachments/18009117573148)
![手动连接图9](https://i.bitsgap.com/hc/article_attachments/18009117573788)

---

## 需要帮助？

如果在配置过程中遇到任何问题，请查阅相关帮助文档或联系平台客服获取支持。

**关键要点：**  
- 本文介绍了通过 OKX 快速 API 和手动连接两种方式设置 API key 的步骤。  
- 详细指导包括账户及权限设置、连接校验等关键操作。  
- 文章同时融合增强的广告信息，助您开启安全便捷的加密货币交易体验。