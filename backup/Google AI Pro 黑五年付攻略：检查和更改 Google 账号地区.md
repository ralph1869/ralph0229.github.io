## 检查、更改 Google 账号地区

1. 打开 [Google 账号地区申请表](https://policies.google.com/country-association-form)。如果已经是可用地区，就不用改了。
2. 地区按实际情况填。如果在美国，就选美国和所在州；台湾等支持地区也可以。
3. 理由就写：自己要用 Antigravity 做开发。

有申请约 2 个小时就收到了修改成功的邮件，具体以 Google 通知为准。

![Google AI 黑五优惠时间表](https://github.com/user-attachments/assets/272c9c9d-a5e0-485e-98b4-56538ec53d47)

![Google AI Pro 黑五年付攻略原图](https://github.com/user-attachments/assets/b846b66b-7a26-46eb-a6e3-d7f50b43a99b)

**图中链接（按截图顺序）**

1. Google 账号的「删除服务」页面（仅查价可直接看下面两项）　<https://myaccount.google.com/deleteservices>
2. Google AI 套餐和价格　<https://one.google.com/about/google-ai-plans/>
3. Google One 升级或更改套餐　<https://one.google.com/settings?expand=upgrade>

## 土区实测：两种月付转年付

我和朋友的土区账号都叠加到了首年优惠，走的是两种方式。金额都是土耳其里拉（TRY）。

- 我原来用的是 Google AI Pro 月付，切到 Pro 年付，这次花了 **219.99 + 3,599.99 TRY**。
- 朋友原来用的是 Google AI Plus 月付，每月 19.99 TRY，切到 Pro 年付，这次约是 **20 + 3,599.99 TRY**。

下图是从 Plus 升级时看到的价格。Pro 含 5 TB，**首年 3,599.99 TRY，之后 8,699.99 TRY/年**。

**其他地区也能叠加吗？** 我们只试过土区。其他区我在网上看到的讨论很少，目前还没法确认能不能叠加同样的首年优惠。

![土区 Google One 从 AI Plus 月付切换到 AI Pro 年付的报价](https://github.com/user-attachments/assets/2ab0139d-d456-4d10-825e-f0e7f0ba66e6)

## 几句使用感受

仅分享信息，不构成购买推荐。我们走的是 Google 正规订阅渠道，我个人不太担心封号，但账号能否一直正常使用，谁也没法保证。Gemini 有个外号叫“VPN 质检机”，我用下来，感觉它对网络环境的要求可能比 Codex 略高一点。

客户端里，Gemini 类似 ChatGPT App，Antigravity IDE 类似 Cursor，`agy` 是在终端里用的 Antigravity CLI。就我平时写代码的体验，Codex 的功能更合我用。`agy` 内置的 Browser Use（`/browser`）能操作 Chrome，本身没有可以操控其他桌面软件的通用 Computer Use。如果想让 `agy` 操作浏览器以外的软件，可以试试通过 MCP 接入第三方项目 `open-computer-use`。项目展示的是 Gemini CLI 的用法，`agy` 的接入效果还待验证。[Browser Use 文档](https://antigravity.google/docs/browser) · [open-computer-use 项目](https://github.com/iFurySt/open-computer-use)

最后附两张当时的榜单截图。Gemini 4 Neon（xHigh）在编程榜排第 4，综合榜排第 3，两项都标了初步结果（Preliminary）。

![编程榜截图，Gemini 4 Neon 排第 4](https://github.com/user-attachments/assets/70fa3aa3-7a71-4047-97e4-5cfe5713094c)

![综合榜截图，Gemini 4 Neon 排第 3](https://github.com/user-attachments/assets/76c09fdd-523d-4e46-81b7-8c4e7af07549)
