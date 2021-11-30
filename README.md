# qiapiao
另一个QQ飞车卡漂项目
~~开发初衷仅是不想看[STY大佬的爱情故事弹窗](https://github.com/StyGame/kapiao) 他的讽刺只会让我更加坚定于开发这个项目!~~

你好!对于某人那些让部分玩家反感的爱情弹窗,所计划制作的重新开发,直到他允许选择不弹出也表示弹窗写的不是人名.好了已经够了!我也被当作恶心人,现在是时候 Say goodbye 了!
详细了解: <https://github.com/StyGame/kapiao/issues/1>

你也可以继续使用直到特征码搜索失效将不再提供新版本.
之后你也可以使用他的版本: <https://github.com/StyGame/kapiao>

## 使用方法
下载此文件 [QUSEREX.dll](https://github.com/qiabug/qiapiao/raw/main/QUSEREX.dll) 并保存到 QQ飞车 的 Releasephysx27 目录.

----
Download this file [QUSEREX.dll](https://github.com/qiabug/qiapiao/raw/main/QUSEREX.dll) and save to the Releasephysx27 directory of QQSpeed.

## 更新
### 2021.11.27
>  2021.10.30的版本依然可以使用 本次更新仅尝试解决封号问题

1.DLL以无模块加载 以免被检测到本模块加载导致封号

2.不替换游戏自带文件 以免文件校验导致封号
>  如果你之前替换了 EventReport.dll 请使用QQ飞车修复工具

3.清除PE头 解决游戏扫描内存导致数据异常问题

### 2021.10.30
1.适配游戏更新

2.去掉卡漂开启提示

3.跟随游戏更换开发工具到 Visual Studio 2019

4.取消代码混淆,文件更小了

5.更换劫持DLL文件,由于ExternalControlLOC.dll不调用DllMain函数.

### 2021.3.26
1.修复失效

2.优化代码

### 2020.5.23
1.采用特征码搜索 理论不用跟着游戏更新 除非代码变化

2.解除卡漂限制 不需要一直刷新 使卡漂更流畅

3.不替换游戏自带文件
