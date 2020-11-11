# lazydog-release
## 通过蓝牙连接车位感应器进行数据采集步骤
#### 下载文件
- 下载 en.stsw-link004.zip， 安装STM32 ST-LINK Utility
- 下载 lzboot-b1.hex 和 lzdog-0.5.hex

#### 刷 bootloader
- 打开 ST-LINK Utility
- 选 File，Open，选 lzboot-b1.hex
- 选 Target，Program & Verify

#### 刷 App
- 在 ST-LINK Utility里选 File，Open，选 lzdog-0.5.hex
- 选 Target，Program & Verify

#### 安装安卓APP
- 在安卓手机上下载并安装 app-ota-v3.0.1.apk

#### 安卓上运行 OTA APP
![BLE scan](/images/ota0.png)
![OTA](/images/ota1.png)
