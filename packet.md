# Web3 钱包安全使用指南



TARESKY
Part-Time Geeker, Full-Time Dreamer.
Subscribe
   
Search...
MAR 26, 2022
Web3 钱包安全使用指南
安全和方便很多时候是矛盾的，在自己能够长期保持的使用方式里，选择最安全的那个
IMG_0313.png
每个人对”麻烦“的耐性不同。为了让这篇文章“有用”，我尽量由简单到复杂地介绍自己管理钱包的方式，同时注明这些措施的必要性，以及替代方案。但不会涉及“钱包是什么”这类更基础的问题，请自行 Google 或阅读《白话：区块链“稳定币挖矿”是什么》 中相关内容。

Table of Contents
别着急，暂时放在交易所
使用 Chrome 钱包插件之前，先重装系统
【必须】重装系统
【必须】不用来源不明软件
【必须】不从搜索引擎下载钱包
【推荐】新手尽量使用 macOS
【推荐】善用 Chrome 的多用户功能
【必须】开启 Chrome 自动更新功能
【必须】手动输入助记词、私钥
【推荐】使用原生或开源输入法
难免使用手机钱包
【推荐】新手尽量使用 iOS
【必须】手动输入助记词、私钥
保存助记词的几种方式
【推荐】二次加工后保存
【推荐】拆分后保存
其他措施
【推荐】一矿一地址依旧重要
【推荐】大部分资金应放在硬件钱包
【推荐】使用 Passphrase 钓鱼
【推荐】使用复杂的派生路径
个人使用举例
热钱包仅分配少量资金
主力使用硬件钱包
别着急，暂时放在交易所
大部分人的第一笔 Crypto 来自中心化交易所。在你对 Web3 钱包有一定概念之前，把钱放在交互和安全机制都更熟悉的交易所中，才是最稳妥的。

使用 Chrome 钱包插件之前，先重装系统
由于目前 Web3 项目的开发水平参差不齐，使用桌面端浏览器能获得最好的兼容性，大部分人在使用 Chrome 钱包插件。

【必须】重装系统
个人电脑，很哪回忆起使用过的全部软件。公司电脑不推荐使用，更无法确定是否预安装了其他监控软件。
操作系统在底层，这里的隐患如果没有先行排除，在上层做再多的防护都是舍本逐末。所以重装操作系统是必须项。
【必须】不用来源不明软件
破解软件一直是病毒的重灾区。Crypto 用户的特征非常明显，如果你是黑客，你会优先对付那些拥有加密货币的用户，还是普通用户？
实际上，你使用任何一款软件都应该考虑它的风险。只用你认可的软件，只从官方渠道下载，都是降低风险的办法。
【必须】不从搜索引擎下载钱包
搜索引擎的前排结果是假钱包的风险已经出现过多次。如果你不知道准确的官网 URL，从社交媒体（Twitter）比对粉丝数和活跃度，来找官方账号是比较稳妥的。
【推荐】新手尽量使用 macOS
我不了解 Linux。常用的 macOS 和 Windows 相比，权限控制更容易。用户可以知道哪些软件有监听键盘输入权限、监听麦克风权限、屏幕录制权限，并且考虑其中的风险。
【推荐】善用 Chrome 的多用户功能
不要将钱包插件安装在你的 Google 默认用户下，因为这里有你的常用插件，很难判断这些插件会不会作恶。
当你在使用多个硬件钱包，或者单个硬件钱包 + 多个 Passphrase（类似双重密码）时，把它们分配在不同的 Chrome 账户 —— 不同的钱包插件中，可以有效避免调用钱包时相互冲突。
【必须】开启 Chrome 自动更新功能
你会看到很多 Crypto KOL 提醒你更新 Chrome 内核，往往是因为发现了紧急的安全漏洞。在 Chrome-设置-关于 Chrome 更新部分的下方，开启自动更新，举手之劳以免错过相关消息。
【必须】手动输入助记词、私钥
复制粘贴始终是高危操作，手动输入搭配输入框自动掩码，至少可以应对剪切板和屏幕被监控的情况。
助记词输入不会花很多时间，别偷懒。如果一定要复制私钥，建议分段复制，中间插入复制一些无关信息，拼成完整的私钥。
【推荐】使用原生或开源输入法
输入法是权限大户，我个人仅使用 Apple 的原生输入法。如果是 Windows 平台，开源且热门的输入法会优于商业大厂输入法。
难免使用手机钱包
如果你没有随身携带电脑的习惯，难免需要使用手机钱包完成一些紧急操作，同样有需要注意的地方。

【推荐】新手尽量使用 iOS
我使用过很长一段时间的 Android，始终无法掌握手机的各种权限控制，相比之下 iOS 会好很多。例如 App 下载渠道控制、剪切板被使用时会有明确提示。
另一个见仁见智的问题是后门，我很难相信在可以轻松植入后门的地方，权力机关会选择不植入，点到即止。
【必须】手动输入助记词、私钥
和桌面平台一样，复制粘贴助记词是高危操作。尤其如果你使用 iOS 设备，即使断网的情况下（断开 Wi-Fi、打开蓝牙），复制动作也会被通用剪贴板功能同步到附近的 Mac 设备，而此时 Mac 的很多应用可能拥有剪切板权限。
保存助记词的几种方式
助记词需要离线保存是常识，对我来说有点难以完全执行，我会担心它在现实环境中的安全性：备份多了会不会泄漏、备份少了会不会丢失、记在脑子里会不会忘。

【推荐】二次加工后保存
交换顺序：最简单的是按你牢记的规则交换顺序，这能防普通人，防不了专业人士。
更改单词：多次循环生成新的助记词，直到出现对你有特殊意义的词，替换它。
【推荐】拆分后保存
简单版：把助记词分成 2 份，分开保存。好处降低泄漏的风险，坏处增加丢失的风险。
复杂版：假设 12 位助记词，分成 1～9、4～12、7～3 这样三份，此时如果丢失了其中一份，可以通过剩余的两份拼出完整的。
科学版：对上一种方式做了数学升级，在 Trezor 硬件钱包中它被叫做 Shamir share backup —— 你可以选择创建 10 份助记词，且拥有其中任意 6 份可以恢复真正的助记词。这对小团队来说非常重要。
其他措施
【推荐】一矿一地址依旧重要
智能合约的授权风险是老生常谈，相比于每次挖完矿记得去取消授权，我也选择一矿一地址这种“笨拙”的方式隔离风险。
【推荐】大部分资金应放在硬件钱包
硬件钱包无法原始防范助记词丢失的风险、无法防范合约授权滥用的风险，但理论上可以屏蔽大部分使用环境带来的风险。外加现在硬件钱包搭配浏览器插件还算好用，多按几下按钮或触屏而已，没有理由将大部分资金置于险境。
硬件钱包的 PIN 码，必须设置成非常用密码。盗取你硬件的人，可以从常见的社工库里查到你的常用数字密码，所以硬件钱包的密码必须和常用密码不同。
【推荐】使用 Passphrase 钓鱼
大部分硬件钱包会支持 Passphrase 功能，可以简单理解成双重密码。同一个硬件钱包，当使用不同的 Passphrase 会生成出不同的公私钥组。因此你可以在默认（不开启 Passphrase）的钱包放一些钱钓鱼，且不在任何其他地方使用它，排除其他风险的可能性，如果这个钱包被盗，直接说明助记词被盗了。
【推荐】使用复杂的派生路径
设置不同的助记词派生路径，可以导出不同的公私钥。不过由于常用软件对这个功能支持的不好，并且其他措施对我来说够用了，就没有实际使用它。
个人使用举例
热钱包仅分配少量资金
助记词在 iOS 手机钱包生成
更改单词和顺序后，抄写在纸上随包携带（离线）
更改单词和顺序后，分成两份，分别拍照和存于密码库（在线）
从 iOS 设备只导出私钥，不导出助记词
手输私钥导入电脑 Metamask
默认派生地址为钓鱼地址，帮助出现风险时排查问题
部分私钥需要上传服务器，只能少放钱
主力使用硬件钱包
助记词通过硬件钱包离线生成
更改单词和顺序后，抄写在纸上随包携带（离线）
更改单词和顺序后，分成两份，分别拍照和存于密码库（在线）
第一时间使用校验助记词功能再做一次验证
未开启 Passphrase 的地址为钓鱼地址
根据需要设置不同的 Passphrase，记忆 Passphrase，并在不关联的地方保存它
根据不同 Passphrase 使用不同的 Chrome 账户
最后，如果你问我有必要吗，我觉得有，也不妨碍其他人觉得没有。另外一点过往经验是：正因为我觉得有必要，并且即使钱很少的时候也有必要，才会有更多可能性。

欢迎讨论、欢迎纠错、欢迎分享。

taresky
 