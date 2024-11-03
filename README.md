## 文件架构

```
motion_and_presence_sensor/        # 工作区
├── 1. Hardware/                   # PCB制版文件
│   ├── presence_basic/            # 基础圆版
│   ├── presence_basic/            # 基础圆版
│   └── presence_robot/            # V2 机器人版
├── 2. Friware/                    # 源代码目录
│   ├── ESPHome/                   # ESPHome相关配置和bin文件
│   └── Tasmota/                   # 仅bin文件
├── 3. Software/                   # empty
├── 4. CAD-Model/                  # 3D打印设计稿
│   ├── presence_basic/            # 基础圆版
│   └── presence_robot/            # V2 机器人版
├── 5. Docs/                       # 参考资料文件夹
├── 6. Test/                       # empty
├── 7. Images/                     # 参考图片资料
├── README.md                      # readme_cn
└── README_en.md                   # readme_en
```

## 风险提示
本项目涉及220V强电，使用过程中存在严重的用电风险。
请确保您具备专业的电工技能或寻求专业电工的支持来进行安装和操作。
对于用电风险需自行承担责任，我们不对因使用本项目而导致的任何损失或损害承担责任。
## 项目背景
这个产品挺简单的，就开源分享给大家了~  
感谢嘉立创的支持~
如果对硬件感兴趣，可以加我的QQ交流群：580259245

## 成品展示
<center>
	<img 
	align="absmiddle" src="https://www.buda8888.com:30006/images/ReZ-TI/Product/SmartHome/Sensor/motion_and_presence_sensor/jlc/2.png" 
	style="max-width:100%" />
	<br>
	<br>
	<img 
	align="absmiddle" src="https://www.buda8888.com:30006/images/ReZ-TI/Product/SmartHome/Sensor/motion_and_presence_sensor/jlc/3.png" 
	style="max-width:100%" />
	<br>
	<br>
	<img 
	align="absmiddle" src="https://www.buda8888.com:30006/images/ReZ-TI/Product/SmartHome/Sensor/motion_and_presence_sensor/jlc/4.png" 
	style="max-width:100%" />
	<br>
	<br>
	<img 
	align="absmiddle" src="https://www.buda8888.com:30006/images/ReZ-TI/Product/SmartHome/Sensor/motion_and_presence_sensor/jlc/demo2.gif" 
	style="max-width:100%" />
	<br>
	<br>
	<img 
	align="absmiddle" src="https://www.buda8888.com:30006/images/ReZ-TI/Product/SmartHome/Sensor/motion_and_presence_sensor/jlc/6.png" 
	style="max-width:100%" />
	<br>
	<br>
</center>

### 自动化效果展示
<center>
	<img 
	align="absmiddle" src="https://www.buda8888.com:30006/images/ReZ-TI/Product/SmartHome/Sensor/motion_and_presence_sensor/general/雷鹰01：餐厅厨房自动化演示/雷鹰01：餐厅厨房自动化演示.gif" 
	style="max-width:100%" />
	<br>
	<br>
	<img 
	align="absmiddle" src="https://www.buda8888.com:30006/images/ReZ-TI/Product/SmartHome/Sensor/motion_and_presence_sensor/general/雷鹰01：近距离控制展示/雷鹰01：近距离控制展示.gif" 
	style="max-width:100%" />
	<br>
	<br>
	<img 
	align="absmiddle" src="https://www.buda8888.com:30006/images/ReZ-TI/Product/SmartHome/Sensor/motion_and_presence_sensor/general/雷鹰01：电视机暂停互动/雷鹰01：电视机暂停互动.gif" 
	style="max-width:100%" />
	<br>
	<br>
	<img 
	align="absmiddle" src="https://www.buda8888.com:30006/images/ReZ-TI/Product/SmartHome/Sensor/motion_and_presence_sensor/general/雷鹰01：卫生间顶装效果演示/雷鹰01：卫生间顶装效果演示.gif" 
	style="max-width:100%" />
</center>

## 成本预估及购买建议
### 成本预估：
- 如果usb版，加上嘉立创免费打板，40元以内可以搞定；
- 顶装的话40出头把
### 购买渠道

| 配件名称         | 参考价格 | 购买渠道                | 链接                                         |
| ------------ | ---- | ------------------- | ------------------------------------------ |
| PCB电路板1块     | /    | 嘉立创                 | /                                          |
| ESP32C3-mini | 12.2 | 淘宝（Saint Geffen企业店） | [点击跳转](https://s.click.taobao.com/i0JbsJt) |
| LD2410B      | 16.9 | 淘宝（hilink旗舰店）       | [点击跳转](https://s.click.taobao.com/pmBbsJt) |
| 其他电容电阻等辅料    | 1    | 淘宝（推荐深圳优信电子）        | 进店搜索                                       |
| 3D打印外壳       | /    | 自行打印                | [打印文件](https://makerworld.com/zh/models/750315#profileId-683903)                                   |
| AC-DC电源模块    | 3.9  | 淘宝（深圳优信电子）          | 进店搜索                                       |
| 射灯卡扣         | 0.24 | 淘宝                  | [点击跳转](https://s.click.taobao.com/8XB5qJt) |

1. 上面的价格都不含运费
2. 如果嫌淘宝麻烦的，可以在嘉立创一键下单（除了ACDC电源），我已经把元器件都匹配了立创商城；
3. usb插头推荐买以前苹果那种正方形的，加最短的typec线，这样可以最小化体积
4. AC-DC模块、220v电源直插口和射灯卡扣只有顶装版需要，按需购买
5. 外壳的3D打印，如果自己没有打印机可以来我的淘宝小店支持一下~~

| 配件名称        | 参考价格   | 本店链接 |
| ----------- | ------ | ---- |
| 人在传感器3D打印外壳 | ==xx== | 链接1  |
|             |        |      |

## 硬件设计
<center>
	<img 
	align="absmiddle" src="https://www.buda8888.com:30006/images/ReZ-TI/Product/SmartHome/Sensor/motion_and_presence_sensor/jlc/7.png" 
	style="max-width:100%" />
	<br>
	<br>
	<img 
	align="absmiddle" src="https://www.buda8888.com:30006/images/ReZ-TI/Product/SmartHome/Sensor/motion_and_presence_sensor/jlc/8.png" 
	style="max-width:100%" />
</center>

### 焊接注意事项：
ESP32C3和typeC对于新手焊接可能不大友好，有条件的可以上钢网
其他都简单

## 软件设计 / 代码参考

### ESPHome：
配置文件见附件，推荐用ESPHome烧录

### Tasmota
如果想直接接matter必须要用tasmota固件，但是要注意，Tasmota在线版本不支持LD2410固件，需要自行clone项目，然后烧录固件，附件我上传了bin文件，大家可以通过tasmota的在线工具进行烧录

tasmota配置步骤：
1. 设备插电，通过连接wifi（烧录后也可以在电脑端连接），配置wifi配网信息
2. 在路由器查找设备ip，登陆设备ip
3. configuration里面配置gpio，如图；保存后会自动重启
4. 配置mqtt（我忘记tasmota跟ha连接是不是一定要配置mqtt了，大家看情况配置吧）
5. matter（如图），开启matter，等待重启
6. 在重启后的界面，用iphone打开家庭，扫描页面上的二维码（如果超过10分钟没有配置，二维码会消失，进入第五步里面有重新出现二维码的按钮）
7. 手机正常配置，配置完就可以愉快的玩耍了
<center>
	<img 
	align="absmiddle" src="https://www.buda8888.com:30006/images/ReZ-TI/Product/SmartHome/Sensor/motion_and_presence_sensor/jlc/9.png" 
	style="max-width:100%" />
</center>