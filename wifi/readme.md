
WIFI_AP:

    Step 1: Search for a hotspot named "m5Psram_cam" and connect.

    step 2: open the 192.168.4.1 web page

    第一步：搜索名为 "M5Psram_Cam" 热点，并连接。

    第二步：打开192.168.4.1网页端即可

WIFI_STA:
  
    Step 1: Modify the wireless network hotspot name and password to be connected to the program.

    step 2: Open the IP page obtained by the camera.

    第一步：修改程序要连接的wifi热点名称以及密码

    第二步：打开摄像头获取到的ip网页端即可


## 一些操作步骤（windows）


打开快捷方式： ESP-IDF Command Prompt (cmd.exe)

打开对应的目录：cd F:\git\m5stack-cam-psram\wifi\wifi_sta

编译: idf.py build

查看串口: idf.py -p COM7 monitor