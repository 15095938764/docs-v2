Please add content here.
故障排除
如果您无法通过此处的说明解决您的问题，请在Discord中询问我们。

出于对您的安全考虑，我们无法在公告频道上提供支持，请在:Discord的#create-ticket频道中打开一张支持票证。
1：告诉我们你想要达到的目标是什么。
2：告诉我们你是如何解决这个问题的。
3：告诉我们你的钱包地址。
4：如果有任何调试信息（一长串无意义的十六进制数据），请将其复制并粘贴到工单中。
请注意，某些级别的支持仅在欧洲或美国工作时间提供。

一般故障：
重置应用程序（单击您的个人资料图片 > 故障排除 > “重置应用程序”）。

页面未响应（Not Loading）：
![not-loading](https://user-images.githubusercontent.com/39476406/171218383-afd002a4-672b-4a25-aed6-561bb14bf490.png)
重置应用程序（单击您的个人资料图片 > 故障排除 > “重置应用程序”）。

交易中止（Transaction Aborted）：
![image](https://user-images.githubusercontent.com/39476406/171218831-db6dfdce-77a3-4b3b-bbb2-3ea24f13d5bc.png)
进入设置（单击个人资料图片）并选择“使用交易批准”选项

连接错误（Connection Error）：
![image](https://user-images.githubusercontent.com/39476406/171218974-8717b83c-f528-4565-ab35-f71fdf6d1b7c.png)
1：请确保您已连接到受支持的网络（以太坊/仲裁）。
2：如果您使用的是不是MetaMask（或者您使用的是ledger），请使用 WalletConnect 作为连接方式。

剩余债务将低于尘埃水平：
（Remaining Debt will be Below Dust Levels）
![image](https://user-images.githubusercontent.com/39476406/171219866-8a11254e-ac38-4fc3-b7c7-91d1806a94b6.png)
在撰写本文时，金库中允许的最低债务为 5000 美元（主网）等值或 100 美元等值（Arbitrum网）。如果您试图偿还的金额会使您剩余的债务低于该水平，那么合同不会让您这样做。
此外，尝试输入大于当前债务1美元左右的一个数值进行偿还，并确保您的钱包中有足够的资金来偿还全部债务。

被清算（Liquidated）
我们通过在 Discord 上授予他们“协议英雄”角色来识别已被清算的用户。
如果您已被清算，我们需要验证您是否拥有清算保险库：
转到https://www.myetherwallet.com/wallet/sign
连接拥有清算保险库的钱包
签署包含任何文本的消息
在Discord 的 #create-ticket 频道中开一张票据，然后发送你的消息。
[Edit this page](https://github.com/yieldprotocol/docs-v2/edit/main/troubleshooting_cn.md)
