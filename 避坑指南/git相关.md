配置vscode项目和git交互
    1.去https://git-scm.com/download/win 下载git
    2.vs装git blame插件，在插件配置中进入json文件，"git.path": "D:\\Git\\bin\\git.exe", 增加一行
    3.如果需要输入user name和user email，在项目文件夹右键，运行git bash在终端窗口运行命令：
        git config user.name "设置你的名字"
        git config user.email "这里面设置你的邮箱地址"

设置gitBash后无法测试游戏？
    设置默认配置文件为：powerShell

PR提交更改：
    改了代码后，源代码管理-提交-确认-同步，网页git-在自己fork的库pull requests-new pll-create pull

PULL同步远程库：
    源代码管理-更多操作-拉取/推送-拉取自-上流

