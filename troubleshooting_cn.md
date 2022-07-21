# 故障排除


## 一般错误

 - 重置应用程序（单击您的个人资料图片 > 故障排除 > “重置应用程序”）。

## Not Loading（未加载）

![not-loading](https://user-images.githubusercontent.com/39476406/180140698-81db6a42-c625-4037-944b-17e8dd8cd2d7.png)

-重置应用程序（单击您的个人资料图片 > 故障排除 > “重置应用程序”）。

## Transaction Aborted（交易终止）

![transaction-aborted](https://user-images.githubusercontent.com/39476406/180141186-64d117a2-227b-4777-a957-734e46cabbc2.png)

-进入设置（单击个人资料图片）并选择“使用交易批准”选项

## Connection Error（连接错误）

![connection-error](https://user-images.githubusercontent.com/39476406/180144230-f1c0faec-0b71-42a0-aec2-142e68712e7b.png)

-首先请确保您已连接到受支持的网络（ETH/Arbitrum）。

-如果您不是使用Metamask，请使用 WalletConnect。

## Remaining Debt will be Below Dust Levels（剩余债务将低于尘埃水平）。

在撰写本文时，金库中允许的最低债务为 5000 美元等值（ETH网）或 100 美元等值（Arbitrum网）。如果您试图偿还的金额会使您的债务低于该水平，那么合同不会让您这样做。

![dust](https://user-images.githubusercontent.com/39476406/180144910-797f1d28-c245-428b-9e07-5230f1ec2333.png)

-在剩余债务大于尘埃的情况下，尝试将钱款数额增大1美元等值的USDC/DAI（实际上不会扣掉这么多），并确保您钱包里有足够的代币

## Liquidated（清算）

我们通过在 Discord 上授予他们“Protocol Hero”角色来纪念已被清算的用户。

如果您已被清算，我们需要验证您是否拥有清算保险库：

转到https://www.myetherwallet.com/wallet/sign

连接拥有清算保险库的钱包

签署包含任何文本的消息

将结果发布到 Discord中你所开立的 ticket-xxx 频道。

## 也许这是一个BUG

如果存在与您发现的问题相匹配的BUG，请检查 [bug tracker](https://github.com/yieldprotocol/bugs/issues) 。如果有，您可以考虑等待，或 [轻推](https://discord.com/channels/752978124614008945/764135581704781864)我们，以便我们优先处理。

## 如果其他一切都失败了

如果您无法按照此处的说明解决您的问题，请在我们的 Discord #create-ticket频道中打开支持票。出于对您钱包地址的安考虑因，我们不会在公共频道上提供支持。

告诉我们你想要达到的目标是什么。

告诉我们你是如何解决这个问题的。

告诉我们你的地址。

如果有任何调试信息（一长串无意义的十六进制数据），请将其复制并粘贴到工单中。

请注意，某些级别的支持仅在欧洲或美国工作时间提供。
[Edit this page](https://github.com/yieldprotocol/docs-v2/edit/main/troubleshooting_cn.md)
