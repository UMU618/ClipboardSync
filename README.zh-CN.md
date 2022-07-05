# 剪贴板同步

## 用户故事

很久很久以前，老板问稣：“为什么我在公司的电脑按 CTRL+C，回家后在自己的电脑按 CTRL+V，结果我想复制的内容却没过来？”

稣淡定地回答：“您肯定没有使用鎏光云桌面的剪贴板同步工具。”

老板问：“哦？那是什么神器？”

稣：“您看，这个剪贴板同步工具是从鎏光云桌面（RegameDesk）抽取出来，专门满足您这个需求的。它是个绿色软件，而且同时集成客户端和服务端。也就是说，客户端和服务端都是同一个软件，这样您不必下载两套程序，用起来更方便。您只要在家里电脑运行它的服务端模式，然后在公司的电脑上用客户端模式连接家里的服务端，就可以实现两台电脑的剪贴板同步。”

老板又问：“走网络的，数据安全吗？”

稣：“SSL 加密，和 HTTPS 一样安全！”

老板高兴地说：“HTTPS！这个我懂，那我就放心使用了。”

# 下载

[百度网盘](https://pan.baidu.com/s/1oFOBhidFp8NJ75SRU41gnQ?pwd=7dfu)

## 用法

参数 --help 可以显示帮助，看不懂算稣输！

## 限制

1. 目前 SSL 证书是内置的，所以理论上存在安全问题……后面把证书弄成可配置的，就更安全了。

2. 目前用户认证是内置的，就是著名的 UMU/123456，后面把这块弄成可配置的，就更更安全了。

3. 文件同步还没做，目前仅支持文本。

4. 还没开源，审核挺麻烦的……