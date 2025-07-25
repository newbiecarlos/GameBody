# GameBody

Gamebody体感编程播放器
Gamebody Interactive player

一、介绍
我们制作了一款名为Gamebody的体感编程播放器，一种交互式DIY程序APP。它是用体感动态控制音频、视频的播放器。用户可以对交互逻辑进行编程、自定义上传交互内容。是一种相当开放的架构方式。

我们的创作初衷是为了使用健身运动器械的时候，能根据你的动作节奏、数量，为你加油打气的智能播放器程序。现在，你似乎可以把它与任何东西相结合——哑铃、玩具娃娃、或者其他什么东西。玩的开心。

【核心功能】通过手机/平板传感器(陀螺仪、加速度计、地磁仪)的传感器，实现运动器械进行运动、触摸、语音等多维度AI交互互动。
【适配性】兼容安卓(支持本地DIY)及苹果系统（待开发），覆盖主流手机/平板设备。
【技术优势】:AI内容生成工具+传感器数据融合，让运动器械“活”起来。


二、使用方法：
1、下载APP：

中国地区下载：地址（待上传）

国际网盘下载:  地址（待上传）

由于我们是一款用户可以自己线下（离线）更新素材和交互逻辑内容的APP，所以安卓系统会比较好的支持这种用户线下更新，苹果IOS系统相对封闭，不支持，所以目前暂时只支持安卓系统。

2、安装

连接手机和电脑：使用准备好的数据线，一端插入手机数据接口，另一端插入电脑 USB 接口。手机连接电脑后，可能会弹出提示，如询问是否允许 USB 调试、选择连接方式（如充电、传输文件（MTP）、传输照片（PTP）等），选择 “传输文件（MTP）” 模式。​如果没有提示，需要开启手机 “USB 调试” 功能：进入手机 “设置” 选项，因手机品牌和系统版本差异，“USB 调试” 位置可能不同。一般在 “设置” - “关于手机” 中，连续点击 “版本号” 多次，即可开启 “开发者选项”。然后在 “开发者选项” 中找到 “USB 调试” 并开启。例如华为手机，路径大致为 “设置” - “系统” - “关于手机” - 多次点击 “版本号” 激活开发者选项 - 返回 “系统” 找到 “开发者选项” - 开启 “USB 调试”。

打开电脑上的文件管理工具：在 Windows 系统中，可通过 “此电脑” 进入；在苹果 Mac 系统中，可通过 “访达” 进入。找到已下载好的 APP 安装包（APK 文件）所在文件夹。​
复制 APK 文件到手机存储：选中 APK 文件，通过复制（快捷键 Ctrl + C 或 Command + C）和粘贴（快捷键 Ctrl + V 或 Command + V）操作，将 APK 文件粘贴到手机存储设备中。一般可选择粘贴到手机的 “内部存储” 或 “SD 卡” 的根目录下，也可新建一个专门文件夹存放，方便查找。例如新建名为 “APK 安装包” 的文件夹，将 APK 文件粘贴进去。​

在手机上安装 APP：断开手机与电脑的连接，打开手机的 “文件管理” 应用，找到刚刚复制到手机的 APK 文件。点击 APK 文件，手机会弹出安装提示，如提示应用的来源、所需权限等信息，确认无误后，点击 “安装” 按钮。安装过程可能需要等待一段时间，安装完成后，即可在手机桌面找到并打开该 APP。

3、打开APP
打开APP之后点击待机界面任意位置
![图片1](https://github.com/newbiecarlos/GameBody/blob/main/%E5%9B%BE%E7%89%871.png)
进入菜单页面，选择右上角的
![图片2](https://github.com/newbiecarlos/GameBody/blob/main/%E5%9B%BE%E7%89%872.png)
选择菜单内容，开始体验

4、APP界面
（待更新）

5、APP自定义内容说明
![图片3](https://github.com/newbiecarlos/GameBody/blob/main/%E5%9B%BE%E7%89%873.png)
编程方式：通过excel进行交互逻辑\素材设置。整个编程逻辑是：通过【触发器】监听 > 进行【逻辑条件】判断 > 加载播放等各种【动作】效果。
具体教程详见视频和说明文档：视频地址
如果要想修改/自己制作MOD，轻具备一定的EXCEL基础，规则设置相对简单，并不复杂，至少比程序员编程简单。

素材说明：
1)完成DB.xlsx文件的编辑，以及对应素材后
2)导入到打包程序，会生成一个自定义名称的XXX.data文件
3)将生成好的素材包XXX.data文件考入Android/data/com.gamebody.app/files/assets/temp/目录下
4)开机享受游戏

6、其他说明
关于广告：目前APP是免费使用。请点击广告让我们有一些收入。如果您能请我们喝杯咖啡或者赞助我们，我们很乐意提供VIP版/去广告激活工作：发送捐助截图及CDKEY到 cssn99@gmail.com邮箱， 72小时内我们将邮件回复接活码，复制粘贴到对应的框内点击激活即可。


Gamebody Interactive player
I. Introduction
We have developed an interactive DIY program app called Gamebody, which is a player that controls audio and video through motion sensing. Users can program interactive logic and upload custom interactive content. It features a highly open architecture.

Our original intention was to create an intelligent player program that can cheer you on based on your movement rhythm and quantity when using fitness equipment. Now, you can combine it with almost anything - dumbbells, dolls, or other objects. Enjoy playing!

Core Functions: Realize multi-dimensional AI interaction such as movement, touch, and voice for sports equipment through mobile phone/tablet sensors (gyroscope, accelerometer, magnetometer).

Compatibility: Compatible with Android (supports local DIY) and iOS (under development), covering mainstream mobile phones and tablet devices.

Technical Advantages: AI content generation tools + sensor data fusion make sports equipment "come alive".

II. Usage Method
1. Download the APP
Download in China: Link (to be uploaded)

International cloud disk download: Link (to be uploaded)

Since ours is an APP that allows users to update materials and interactive logic offline, the Android system will better support such offline updates. The Apple iOS system is relatively closed and does not support it, so currently only the Android system is supported.

2. Installation
Connect your phone to the computer: Use a prepared data cable, insert one end into the phone's data interface, and the other end into the computer's USB interface. After connecting the phone to the computer, a prompt may pop up, such as asking whether to allow USB debugging, or to select a connection mode (such as charging, file transfer (MTP), photo transfer (PTP), etc.). Select the "File Transfer (MTP)" mode. If there is no prompt, you need to enable the "USB Debugging" function on your phone: Enter the "Settings" option. Due to differences in phone brands and system versions, the location of "USB Debugging" may vary. Generally, in "Settings" - "About Phone", click "Version Number" multiple times in a row to enable "Developer Options". Then find "USB Debugging" in "Developer Options" and enable it. For example, for Huawei phones, the path is roughly "Settings" - "System" - "About Phone" - click "Version Number" multiple times to activate Developer Options - return to "System" to find "Developer Options" - enable "USB Debugging".

Open the file management tool on the computer: In Windows system, you can enter through "This PC"; in Apple Mac system, you can enter through "Finder". Find the folder where the downloaded APP installation package (APK file) is located.

Copy the APK file to the phone storage: Select the APK file, and copy (shortcut key Ctrl + C or Command + C) and paste (shortcut key Ctrl + V or Command + V) to paste the APK file into the phone storage device. Generally, you can choose to paste it into the root directory of the phone's "Internal Storage" or "SD Card", or create a special folder for storage for easy 查找。For example, create a folder named "APK Installation Packages" and paste the APK file into it.

Install the APP on the phone: Disconnect the phone from the computer, open the "File Management" app on the phone, and find the APK file just copied to the phone. Click the APK file, and the phone will pop up an installation prompt, such as prompting the source of the app and the required permissions. After confirming, click the "Install" button. The installation process may take some time. After installation, you can find and open the app on the phone's home screen.

3. Open the APP
After opening the APP, click anywhere on the standby interface

Enter the menu page and select the one in the upper right corner

Select menu content and start experiencing

4. APP Interface
(To be updated)

5. Instructions for Customizing APP Content

Programming method: Set interactive logic and materials through Excel. The entire programming logic is: Monitor through [Trigger] > Judge [Logical Conditions] > Load and play various [Action] effects.

For specific tutorials, please refer to the video and instruction document: Video address

If you want to modify or create your own MOD, you need to have a certain Excel foundation. The rule settings are relatively simple, not complicated, at least simpler than programmer programming.

Material description:

Complete the editing of the DB.xlsx file and corresponding materials
Import into the packaging program, and a custom-named XXX.data file will be generated
Copy the generated material package XXX.data file into the Android/data/com.gamebody.app/files/assets/temp/ directory
Turn on the device and enjoy the game

6. Other Instructions
Regarding advertisements: The APP is currently free to use. Please click on the advertisements to help us generate some income. If you can buy us a cup of coffee or sponsor us, we will be happy to provide VIP version/ad-free activation: Send the donation screenshot and CDKEY to cssn99@gmail.com, and we will reply with the activation code via email within 72 hours. Copy and paste it into the corresponding box and click activate.
