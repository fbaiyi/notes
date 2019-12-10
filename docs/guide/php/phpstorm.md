# 激活

[帮助](https://zhile.io/2018/08/19/jetbrains-license-server-crack.html)

> 使用方法

 1. 先下载压缩包解压后得到jetbrains-agent.jar，把它放到你认为合适的文件夹内。  
    下载页面：https://zhile.io/2018/08/17/jetbrains-license-server-crack.html
 2. 启动你的IDE，如果上来就需要注册，选择：试用（Evaluate for free）进入IDE
 3. 点击你要注册的IDE菜单："Configure" 或 "Help" -> "Edit Custom VM Options ..."如果提示是否要创建文件，请点"Yes"。  
    参考文章：https://intellij-support.jetbrains.com/hc/en-us/articles/206544869
 4. 在打开的vmoptions编辑窗口末行添加：-javaagent:/absolute/path/to/jetbrains-agent.jar  
    一定要自己确认好路径(不要使用中文路径)，填错会导致IDE打不开！！！最好使用绝对路径。  
	一个vmoptions内只能有一个-javaagent参数。  
    示例:
      - mac:      -javaagent:/Users/neo/jetbrains-agent.jar
      - linux:    -javaagent:/home/neo/jetbrains-agent.jar
      - windows:  -javaagent:C:\Users\neo\jetbrains-agent.jar  
        如果还是填错了，参考这篇文章编辑vmoptions补救：https://intellij-support.jetbrains.com/hc/en-us/articles/206544519
 5. 重启你的IDE。
 6. 点击IDE菜单 "Help" -> "Register..." 或 "Configure" -> "Manage License..."  
    支持两种注册方式：License server 和 Activation code:
    - 选择License server方式，地址填入：http://jetbrains-license-server （应该会自动填上）
      或者点击按钮："Discover Server"来自动填充地址。
    - 选择Activation code方式离线激活，请使用：ACTIVATION_CODE.txt 内的注册码激活  
      如果激活窗口一直弹出（error 1653219），请去hosts文件里移除jetbrains相关的项目  
      如果你需要自定义License name，请访问：https://zhile.io/custom-license.html  