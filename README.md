# lazydog-release
## 通过蓝牙连接车位感应器进行数据采集步骤
#### 下载文件
- 下载 en.stsw-link004.zip， 安装STM32 ST-LINK Utility
- 下载 lzboot-b1.hex 和 lzdog-0.5.hex

#### 刷 bootloader （只需要刷一次）
- 打开 ST-LINK Utility
- 选 File，Open，选 lzboot-b1.hex
- 选 Target，Program & Verify

#### 刷 应用程序
- 在 ST-LINK Utility里选 File，Open，选 lzdog-0.5.hex (第一版是0.5，以后会陆续更新）
- 选 Target，Program & Verify

#### 安装安卓APP
- 在安卓手机上下载并安装 app-ota-v3.0.1.apk （第一版是3.0.1，以后会陆续更新）

#### 安卓上运行 OTA APP
##### OTA功能
把OTA的.bin文件放在手机以下路径：Android\data\com.innotek.android.lazydog\files，APP就可以找到该文件，打开OTA开关就可以开始了
##### 数据采集
数据采集以后会储存在手机里的CSV文件，以下路径：Android\data\com.innotek.android.lazydog\files

![BLE scan](/images/ota0.jpg)
![OTA](/images/ota1.jpg)
