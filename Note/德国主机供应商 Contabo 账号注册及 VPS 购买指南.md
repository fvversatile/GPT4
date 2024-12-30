# 德国主机供应商 Contabo 账号注册及 VPS 购买指南

Contabo 是一家成立于2003年的德国老牌服务器提供商，拥有超过17年的运营经验。公司主要提供 VPS、专用服务器和域名服务，在欧洲设有两个自建数据中心，并于今年新增了位于美国密苏里州圣路易斯的数据中心。Contabo 的 VPS 以高性价比、高配置和高稳定性著称，深受资深用户的喜爱。

![Contabo 服务器](https://www.daniao.org/wp-content/uploads/2020/11/contabao-eu-8.png)

Contabo 一贯秉承德国严谨的工作风格，付款后 VPS 开通通常需要1-3天，期间可能会进行身份验证。因此，建议购买时避免使用代理，填写真实信息。此外，网站界面较为简朴，类似上世纪90年代的风格，不支持支付宝和信用卡付款，但产品性价比极高。最便宜的4核8G 200G SSD方案月付仅需4.99欧元。德国数据中心适合欧洲用户，美国数据中心则适合国内用户延迟较低的需求。

## 官网访问

首先，访问 Contabo 的官方网站：[Contabo 官网](https://www.contabo.com)

## VPS 购买步骤

### 1. 选择 VPS 方案

进入 Contabo 官网后，您将看到 VPS 价格页面。Contabo 提供两种类型的 VPS 套餐：

- **SSD + HDD 混合方案**：硬盘容量大，价格实惠，起价3.99欧元/月。
- **纯 SSD 方案**：硬盘容量稍小，价格稍高，起价4.99欧元/月。

对于对硬盘读写速度有较高要求的用户，建议选择纯 SSD 方案；而对于需要大容量存储的用户，可以选择 SSD + HDD 混合方案。本文选择购买4.99欧元的纯 SSD VPS 方案，点击“Customize & ORDER”按钮开始配置 VPS。

![VPS 价格页](https://www.daniao.org/wp-content/uploads/2020/11/contabao-eu-1.png)

### 2. 自定义 VPS 配置

自定义 VPS 主要有以下三个关注点：

- **操作系统选择**：Windows 系统需要额外收费。
  
  ![操作系统选择](https://www.daniao.org/wp-content/uploads/2020/11/contabao-eu-2.png)

- **数据中心位置**：美国数据中心的价格略高于德国数据中心。
  
  ![数据中心位置](https://www.daniao.org/wp-content/uploads/2020/11/contabao-eu-3.png)

- **预付周期选择**：选择购买几个月的服务（例如月付、季度付或年付）。月付需支付4.99欧元的初装费（仅一次性收取），季度付可减免1.25欧元，年付则免除初装费。
  
  ![预付周期选择](https://www.daniao.org/wp-content/uploads/2020/11/contabao-eu-4.png)

### 3. 确认订单

配置完成后，点击“Order now”确认配置，系统将跳转到账号注册资料填写页面。

![确认订单](https://www.daniao.org/wp-content/uploads/2020/11/contabao-eu-5.png)

### 4. 填写付款信息

填写您的付款 Paypal 账号，并选择是否开启自动续费功能。

![付款信息](https://www.daniao.org/wp-content/uploads/2020/11/contabao-eu-6.png)

### 5. 添加自定义请求

由于 Contabo 默认随机分配 Intel E5-2630 或 AMD EPYC 7282 处理器，建议添加自定义请求以选择 AMD 处理器，以提升性能。

![自定义请求](https://www.daniao.org/wp-content/uploads/2020/11/contabao-eu-7.png)

### 6. 完成订单

支付完成后，您将获得订单号。Contabo 会在确认付款后，通过邮件发送账号登录信息和 VPS 详情。此时，您可以登录后台进行操作。

**注意事项：**

审核通过后，您将收到邮件“Your login data!”，其中包含服务器 IP、root 密码、默认端口22（用于 SSH 连接）以及 VNC IP 和端口（用于 VNC 登录）。

## Contabo 注册注意事项

1. **真实信息注册**：避免使用代理工具，使用真实 IP 注册，确保 IP 地址与填写的国家和城市匹配。姓名应与 Paypal 账户一致，以便顺利通过审核。
2. **付款后处理**：付款后几小时或1天内会收到 VPS 开通邮件。
3. **身份验证**：如使用虚假信息注册，可能需要提供身份证明文件，如身份证、护照或驾照。
4. **客服联系方式**：客服邮箱为 [support@contabo.com](mailto:support@contabo.com)，可通过此邮箱联系。
5. **工作时间**：北京时间下午3点至次日凌晨3点。

**续费提醒**：Contabo 会提前一周发送续费提醒邮件，逾期未续费将产生5~20欧元的罚款。建议按时续费或选择 Paypal 自动续费功能。

## IP 测试

### 数据中心位置

- **美国**：密苏里州
- **欧洲**：德国

### 测试 IP 列表

- 慕尼黑测试 IP：193.164.131.192
- 纽伦堡测试 IP：144.91.105.10X
- 纽伦堡测试 IP：62.171.168.X
- 美国测试 IP：209.126.15.91

### 配置详情

1. **税率**：欧美用户需缴税，国内用户注册无需税费。
2. **操作系统**：Linux 系统免费，选择 Windows 系统需每月支付4.99欧元。
3. **CPU**：随机分配 Intel E5-2630v4 或 AMD EPYC 7282 处理器。
4. **硬盘类型**：HDD 硬盘仅限德国数据中心，适合 PT 用户；SSD 硬盘提供 snapshot 快照备份功能。
5. **带宽**：VPS 配置带宽为200Mbps，超过限制会被强制降速。
6. **IP 购买**：额外支付3欧元/月。
7. **性能**：部分 SSD VPS 使用 AMD EPYC 7282 CPU，性能显著提升，UnixBench 单核评分1300+，四核3300+。
8. **优惠信息**：Contabo 优惠码较少，偶有免初装费活动，仅支持 Paypal 和信用卡付款。

## 推荐工具

在选择 VPS 服务时，除了 Contabo，您还可以考虑其他优质供应商以满足不同需求。选择合适的 VPS 服务商，将为您的项目提供稳定可靠的支持。

## WildCard 推荐

WildCard | 一分钟注册，轻松订阅海外线上服务：[https://bit.ly/bewildcard](https://bit.ly/bewildcard) 使用门槛极低，支持微信支付宝开通。支持开通各类海外平台，如 ChatGPT、Claude、Google Play、Apple Store、OpenAI、Twitter、Patreon、MidJourney、Amazon、POE、Microsoft、Facebook、GitHub、Telegram、PayPal 等海淘订阅平台。使用邀请码：ACCPAY，立享消费0手续费，减免开卡费用。

## 总结

Contabo 以其高性价比和稳定性在众多 VPS 提供商中脱颖而出。通过本文的注册和购买指南，您可以轻松上手，快速部署您的服务器。记得遵循注册注意事项，确保顺利开通服务，并合理选择数据中心和配置，以满足您的具体需求。

