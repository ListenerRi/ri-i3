# ri-i3
ri-i3是一份包含了大多数功能的i3wm配置文件
主要有两个配置文件:config和config_i3status
- config是i3的主要配置,包含了按键映射,主要变量等
- config_i3status是i3status的配置文件,用来在i3bar上显示一些系统信息(包括网速)

# 截图
桌面:
![start](/screenshots/start.png)
平铺:
![split-window](/screenshots/split-window.png)
窗口透明:
![transparent](/screenshots/transparent.png)
浮动与窗口阴影:
![float-shadow](/screenshots/float-shadow.png)

# 主要按键

## 特殊键解释
- $mod:Alt
- Mod4:Windows
- Return:回车
- Up,Down,Left,Right:上下左右
- Print:打印键
- button1:鼠标左键
- button2:鼠标中建
- button3:鼠标右键
- button4:鼠标向上滚轮
- button5:鼠标向下滚轮

## 一般按键
**按下此类按键后直接执行对应功能**

|按键                            |功能                                       |
|:----:                          |:----:                                     |
|$mod+Return                     |打开terminal                               |
|Print                           |进入截图模式                               |
|Ctrl+Print                      |截取当前窗口                               |
|$mod+q                          |关闭当前窗口                               |
|$mod+d                          |运行dmenu                                  |
|$mod+h / $mod+Left              |切换到左边的窗口                           |
|$mod+j / $mod+Down              |切换到下边的窗口                           |
|$mod+k / $mod+Up                |切换到上边的窗口                           |
|$mod+l / $mod+Right             |切换到右边的窗口                           |
|$mod+Shift+h / $mod+Shift+Left  |向左移动窗口                               |
|$mod+Shift+j / $mod+Shift+Down  |向下移动窗口                               |
|$mod+Shift+k / $mod+Shift+Up    |向上移动窗口                               |
|$mod+Shift+l / $mod+Shift+Right |向右移动窗口                               |
|$mod+v                          |切换一下个窗口水平或者垂直出现             |
|$mod+f                          |切换当前窗口全屏模式                       |
|$mod+s                          |切换到堆叠模式                             |
|$mod+t                          |切换到标签模式                             |
|$mod+w                          |切换当前窗口的水平或垂直模式               |
|$mod+Shift+space                |切换当前窗口浮动模式                       |
|$mod+space                      |在浮动窗口和平铺窗口之间切换焦点           |
|$mod+p                          |选中父容器                                 |
|$mod+c                          |选中子窗口                                 |
|$mod+?                          |'?'为数字,切换到对应工作区                 |
|$mod+Shift+?                    |'?'为数字,将当前窗口移动到对应工作区       |
|$mod+Shift+c                    |重启加载i3配置文件                         |
|$mod+Shift+r                    |重启i3(不注销当前会话)                     |
|$mod+button2                    |关闭点击的窗口                             |
|button2                         |点击窗口标题后关闭对应窗口                 |
|button3                         |点击窗口标题后切换对应窗口的浮动与平铺模式 |
|$mod+button4                    |向左移动窗口                               |
|$mod+button5                    |向右移动窗口                               |
|$mod+Shift+button4              |向上移动窗口                               |
|$mod+Shift+button5              |向下移动窗口                               |
|button4                         |在窗口标题上向上滚动窗口不透明             |
|button5                         |在窗口标题上向下滚动使窗口透明             |

## 模式按键
**按下此类按键后进入特殊模式,等待下一个按键以执行对应功能**
**工作区旁边会提示等待哪些按键以及对应的功能**

|按键                |模式     |
|:----:              |:----:    |
|$mod+a              |运行软件 |
|$mod+r              |窗口大小 |
|control+$mod+Delete |关机重启 |
|$mod+Shift+v        |音量调节 |
|$mod+Shift+b        |亮度调节 |
