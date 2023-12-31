
# OpenHarmony社区版本发布计划：

| **迭代计划** | **版本号**            |**API版本号**| **版本构建** | **版本转测试** | **版本测试完成** |
| ------------ | --------------------- | --------- | ------------ | -------------- | ---------------- |
| IT1          | OpenHarmony 2.2 Beta2  | 6         | 2021/7/21    | 2021/7/21      | **2021/7/30**    |
| IT2          | OpenHarmony 3.0 LTS   | 7         | 2021/9/22    | 2021/9/22      | **2021/9/28**    |
| IT3          | OpenHarmony 3.1 Beta | 8         | 2021/12/22   | 2021/12/22     | **2021/12/30**   |
| IT4          | OpenHarmony 3.1 Release | 8         | 2022/3/9    | 2022/3/9      | **2022/3/30**    |
| IT5          | OpenHarmony 3.2 Beta1 | 9         | 2022/5/25    | 2022/5/26      | **2022/5/30**    |
| IT6          | OpenHarmony 3.2 Beta2 | 9         | 2022/7/20    | 2022/7/21      | **2022/7/30**    |
| IT7          | OpenHarmony 3.2 Beta3 | 9         | 2022/9/21    | 2022/9/22      | **2022/9/30**    |
| IT8          | OpenHarmony 3.2 Beta4 | 9         | 2022/11/21    | 2022/11/22      | **2022/11/30**    |
| IT9          | OpenHarmony 3.2 Beta5 | 9         | 2023/1/23    | 2023/1/24      | **2023/1/30**    |
| IT10         | OpenHarmony 3.2 Release | 9       | 2023/2/25    | 2023/2/26      | **2023/3/30**    |
| IT11         | OpenHarmony 4.0 Beta1 | 10        | 2023/5/24    | 2023/5/25      | **2023/5/31**    |
| IT12         | OpenHarmony 4.0 Beta2 | 10        | 2023/7/26    | 2023/7/27      | **2023/7/31**    |
| IT13         | OpenHarmony 4.0 Release | 10      | 2023/10/19    | 2023/10/20      | **2023/10/25**    |
| IT14         | OpenHarmony 4.1 Beta1 | 11        | 2023/12/27    | 2023/12/28      | **2023/12/31**    |



## 版本类型说明
| 版本名称 | 介绍   | 说明                                       |
| -------- | ------ | ------------------------------------------ |
| alpha    | 内测版 | 内部测试版本                               |
| beta     | 公测版 | Beta阶段会一直加入新的功能                 |
| Release  | 正式版 | 稳定版本                                   |
| LTS      | 正式版 | 长期支持版本                                   |

## OpenHarmony 3.1 Release Roadmap Overview:

**申明：** OpenHarmony 路标每半年发布一次，实际支持特性以最终发布的版本为准。

## 1、ArkUI

- 对于 **极简声明式开发范式** ，提供更为丰富的组件能力和动画效果，并支持Canvas绘制能力；
- 支持更多交互输入方式：触摸、键盘、鼠标。

## 2、系统应用

- 系统应用构建，包含系统桌面、SystemUI、系统设置、相机、图库、通话、联系人、信息、文件选择器、输入法。

## 3、应用框架

- 提供 **元能力相关能力** ：提供卡片能力，支持开发者为元能力配套开发卡片；提供FA和Stage两种开发模型，支持单实例和多实例的组件开发方式；
- 提供 **包管理相关** 能力 **：** 完善多HAP包安装/卸载；支持获取跨设备应用信息；并对包结构进行优化。

## 4、分布式

- 提供更多 **分布式软总线** 能力，提升设备互联体验：新增支持蓝牙连接、组网和传输；新增p2p连接和组网，并提供文件传输、流传输；
- 支持 **硬件互助** ，资源共享：支持镜像和扩展投屏；支持分布式相机。
- 支持更多 **分布式特性：** 支持分布式任务管理，原子化服务和应用进行跨设备迁移、跨设备流转；支持分布式文件系统；分布式数据库；分布式数据对象。

## 5、图形显示 &amp; 窗口

- 为开发者提供基于EGL/GLES Native SDK的3D图形绘制能力。
- 为开发者提供基于WebGL SDK的3D图形绘制能力。
- 推出全新的 **UI**** 动效框架**，提升界面动效体验：支持动画线程与UI线程分离，提供新的UI动画计算逻辑，优化动画过程中UI测量布局绘制逻辑。
- 支持 **分屏和多窗口** 显示，支持窗口内容跨窗口拖拽。

## 6、媒体

对于standard设备，新增如下能力：

- 支持本地基础音视频播放和录制能力，支持视频硬编解码，支持主流音视频codec与封装格式，并易于生态厂商扩展；
- 支持相机基础预览、拍摄、录像能力，及分布式相机预览、拍摄能力。

## 7、通信互联

- 提供基础 **电话** 和 **蜂窝数据** 能力：SIM卡、搜网、通话、短信、蜂窝数据；
- **提供更多短距通信** 能力：支持Wi-Fi STA/AP/P2P能力，支持NFC有源标签的读写能力，支持传统蓝牙的基本管理能力和低功耗蓝牙的基本能力；

## 8、安全

- 提供统一的 **秘钥管理服务** ，为系统应用和上层业务提供本地秘钥全生命周期的管理；
- 提供统一的用户 **身份认证框架** ，可以为如PIN码等提供对外统一的认证服务；
- 提供基于Access Token的权限管理、隔离与访问控制架构。

## 9、ArkCompiler

- 提供 **TS/JS**** 编译器和运行时的相关能力：**新增支持eTS，TypeScript 4.13，EcmaScript modules；新增支持CMS(Concurrent Marking &amp; Sweep) GC、Moving GC；新增支持轻量化Actor / Worker。

- **提供调试调优相关功能** ：支持CPU Profiler，行列号、断点、异常调试，Attach调试

## 10、内核

- **文件系统** 性能和安全增强：支持闪存友好的文件系统（F2FS），提供了更灵活的空间分配策略和底层空间回收策略；支持F2FS/EXT4的文件级数据加密。
- 优化 **资源调度** ：支持进程智能分组，支持调频，支持延迟任务调度。

## 11、IDE &amp; 工具

- 支持基于 **声明式范式** UI框架极简开发；
- **提供卡片开发相关能力** ：新增低代码模板，支持服务卡片零代码开发；
- 应用一键式自动化签名；
- **提供跨设备应用开发** 相关能力：支持根据设备能力集进行API联想，支持根据开发者使用的API自动生成应用RPCID；
- 优化开发 **调测能力** ：提供日志功能增强和事件处理、查询、订阅能力；提供崩溃、卡死无响应、内核重启定位信息；

- 提供兼容性 **测试工具和测试套件** ，含PCS3.1，ACTS3.1，DCTS3.1，HATS3.1，兼容性认证平台；
- 提供UI随机注入自动化测试工具 **Wukong** ，性能能效测试工具 **SmartPerf** ；
- 提供 **测试框架** ：JavaScript单元测试框架，UI测试框架，分布式测试框架。


# 各版本特性交付清单：


## OpenHarmony_release 2.2(beta1)版本特性清单：

状态说明：discussion(方案讨论，需求未接受)，Reject(未纳入版本)，developing(开发中)，Testing(测试中)，Accepted(已验收)

| no   | issue                                                        | feture description                                  | status     | sig                | owner                                         |
| :--- | ------------------------------------------------------------ | :-------------------------------------------------- | :--------- | :----------------- | :-------------------------------------------- |
| 1    | I3HX0V | 【HiLog】L1系统HiLog功能增强                 | 轻量系统 | SIG_BscSoftSrv | [@shenchenkai](https://gitee.com/shenchenkai) |
| 2    | I3INEZ | 【AI子系统】AI引擎支持基于共享内存的数据传输 | 轻量系统 | SIG_AI         | [@armylee0](https://gitee.com/armylee0)       |
| 3    | I3ICFO | 【分布式数据管理】提供数据库内容的删除能力          | 轻量系统 | SIG_DataManagement   | [@widecode](https://gitee.com/widecode) |
| 4    | I3ICH0 | 【分布式数据管理】提供统一的HAL文件系统操作函数实现 | 轻量系统 | SIG_DataManagement   | [@widecode](https://gitee.com/widecode) |
| 5    | I3ICG4 | 【分布式数据管理】提供相关数据存储的原子操作能力    | 轻量系统 | SIG_DataManagement   | [@widecode](https://gitee.com/widecode) |
| 6    | I3ICGH | 【分布式数据管理】提供二进制Value的写入读取能力     | 轻量系统 | SIG_DataManagement   | [@widecode](https://gitee.com/widecode) |
| 7    | I3NSPB) | 【轻量级图形】UIKit组件支持margin/padding           | 轻量系统 | SIG_GraphicsandMedia | [@niulihua](https://gitee.com/niulihua) |
| 8    | I3NSZH) | 【轻量级图形】圆形/胶囊按钮支持缩放和白色蒙层动效   | 轻量系统 | SIG_GraphicsandMedia | [@niulihua](https://gitee.com/niulihua) |


## OpenHarmony_release 2.2(beta2)版本特性清单：

状态说明：discussion(方案讨论，需求未接受)，Reject(未纳入版本)，developing(开发中)，Testing(测试中)，Accepted(已验收)

| no   | issue                                                        | feture description                                           | platform     | sig                  | owner                                               |
| :--- | ------------------------------------------------------------ | :----------------------------------------------------------- | :--------- | :------------------- | :-------------------------------------------------- |
| 1    | I3NCKH | 【轻内核子系统】L0上支持基于NOR Flash的littlefs文件系统      | 轻量系统 | SIG_Kernel           | [@kkup180](https://gitee.com/kkup180)               |
| 2    | I3NCTE | 【轻内核子系统】L0上对外提供统一的文件系统操作接口           | 轻量系统 | SIG_Kernel           | [@kkup180](https://gitee.com/kkup180)               |
| 3    | I3NCX2 | 【轻内核子系统】L0 补充120个POSIX接口                        | 轻量系统 | SIG_Kernel           | [@kkup180](https://gitee.com/kkup180)               |
| 4    | I3NT2C | 【轻内核子系统】移植mksh命令解析器                           | 轻量系统 | SIG_Kernel           | [@kkup180](https://gitee.com/kkup180)               |
| 5    | I3NT2K | 【轻内核子系统】shell交互友好性提升                          | 轻量系统 | SIG_Kernel           | [@kkup180](https://gitee.com/kkup180)               |
| 6    | I3NT2V | 【轻内核子系统】移植toybox命令集                             | 轻量系统 | SIG_Kernel           | [@kkup180](https://gitee.com/kkup180)               |
| 7    | I3NT4N | 【轻内核子系统】Namecache模块                                | 轻量系统 | SIG_Kernel           | [@kkup180](https://gitee.com/kkup180)               |
| 8    | I3NT58 | 【轻内核子系统】Vnode管理                                    | 轻量系统 | SIG_Kernel           | [@kkup180](https://gitee.com/kkup180)               |
| 9    | I3NT5Q | 【轻内核子系统】Lookup模块                                   | 轻量系统 | SIG_Kernel           | [@kkup180](https://gitee.com/kkup180)               |
| 10   | I3NT6H | 【轻内核子系统】文件系统维测增强                             | 轻量系统 | SIG_Kernel           | [@kkup180](https://gitee.com/kkup180)               |
| 11   | I3NT6U | 【轻内核子系统】liteos-a內核模块可配置                       | 轻量系统 | SIG_Kernel           | [@kkup180](https://gitee.com/kkup180)               |
| 12   | I3NT78 | 【轻内核子系统】liteos-a小系统三方芯片适配                   | 轻量系统 | SIG_Kernel           | [@kkup180](https://gitee.com/kkup180)               |
| 13   | I3SNIP | 【轻内核子系统】L0支持三方组件Mbedtls编译                    | 轻量系统 | SIG_Kernel           | [@kkup180](https://gitee.com/kkup180)               |
| 14   | I3SNKK | 【轻内核子系统】L0支持三方组件curl编译                       | 轻量系统 | SIG_Kernel           | [@kkup180](https://gitee.com/kkup180)               |
| 15   | I3NIME | 【启动恢复子系统】支持恢复出厂设置                           | 轻量系统 | SIG_BscSoftSrv       | [@handyohos](https://gitee.com/handyohos)           |
| 16   | I3NTBC | 【启动恢复子系统】L0/L1/L2接口优化                           | 轻量系统 | SIG_BscSoftSrv       | [@handyohos](https://gitee.com/handyohos)           |
| 17   | I3NN4H  | 【DFX子系统】【HiLog】L0系统HiLog功能增强                    | 轻量系统 | SIG_BscSoftSrv       | [@shenchenkai](https://gitee.com/shenchenkai)       |
| 18   | I3NN53  | 【DFX子系统】【HiEvent】L0系统HiEvent功能增强                | 轻量系统 | SIG_BscSoftSrv       | [@shenchenkai](https://gitee.com/shenchenkai)       |
| 19   | I3ID9Q  | 【分布式调度】建立轻量设备DMS与富设备DMS通信通道             | 轻量系统 | SIG_AppFramework     | [@lijiarun](https://gitee.com/lijiarun)             |
| 20   | I3ID9V  | 【分布式调度】轻量设备启动富设备上的Ability                  | 轻量系统 | SIG_AppFramework     | [@lijiarun](https://gitee.com/lijiarun)             |
| 21   | I3I1V8          | 【全球化子系统】构建应用资源解析和加载机制                   | 轻量系统 | SIG_AppFramework     | [@zhengbin5](https://gitee.com/zhengbin5)           |
| 22   | I3I1VJ  | 【全球化子系统】构建资源回溯机制                             | 轻量系统 | SIG_AppFramework     | [@zhengbin5](https://gitee.com/zhengbin5)           |
| 23   | I3QE85 | 【驱动子系统】L0支持HDF框架                                  | 轻量系统 | SIG_DriverFramework  | [@zianed](https://gitee.com/zianed)                 |
| 24   | I3NSVQ  | 【轻量级图形】DFX维测能力：UIKit支持显示控件轮廓             | 轻量系统 | SIG_GraphicsandMedia | [@niulihua](https://gitee.com/niulihua)             |
| 25   | I3NSWY  | 【轻量级图形】ScrollView/List支持通过弧形进度条展示滑动进度  | 轻量系统 | SIG_GraphicsandMedia | [@niulihua](https://gitee.com/niulihua)             |
| 26   | I3NSZZ  | 【轻量级图形】支持开关按钮/复选框/单选按钮动效               | 轻量系统 | SIG_GraphicsandMedia | [@niulihua](https://gitee.com/niulihua)             |
| 27   | I3NSQ6  | 【轻量级图形】UIKit支持点阵字体产品化解耦                    | 轻量系统 | SIG_GraphicsandMedia | [@niulihua](https://gitee.com/niulihua)             |
| 28   | I3NSZ1  | 【轻量级图形】UI框架提供统一多后端框架支持多芯片平台         | 轻量系统 | SIG_GraphicsandMedia | [@niulihua](https://gitee.com/niulihua)             |           |
| 29   | I3NCB9 | 【L1 Linux开源】编译器替换后的内核代码适配                   | 轻量系统 | SIG_Kernel           | [@zzzuo](https://gitee.com/zzzuo)                 |
| 30   | I3NBVI  | 【L1 Linux开源】clang替换                                    | 轻量系统 | SIG_CompileRuntime   | [@zhuoli72](https://gitee.com/zhuoli72)           |
| 31   | I3NC8H  | 【L1 Linux开源】musl库替换                                   | 轻量系统 | SIG_CompileRuntime   | [@zhuoli72](https://gitee.com/zhuoli72)           |
| 32   | I3NCEF  | 【L1 Linux开源】工具集替换                                   | 轻量系统 | SIG_CompileRuntime   | [@taiyipei](https://gitee.com/taiyipei)           |
| 33   | I3NCF7  | 【L1 Linux开源】rootfs替换                                   | 轻量系统 | SIG_CompileRuntime   | [@taiyipei](https://gitee.com/taiyipei)           |
| 34   | I3NCG0  | 【L1 Linux开源】镜像制作工具替换                             | 轻量系统 | SIG_CompileRuntime   | [@taiyipei](https://gitee.com/taiyipei)           |
| 35   | I3NCGM  | 【L1 Linux开源】开源编译构建                                 | 轻量系统 | SIG_CompileRuntime   | [@taiyipei](https://gitee.com/taiyipei)           |
| 36   | I3NCCT  | 【L1 Linux开源】编译器替换后的HDF适配                        | 轻量系统 | SIG_DriverFramework  | [@zianed](https://gitee.com/zianed)               |
| 37   | I3N0LP  | 【全球化子系统】构建自定义数据编译能力                       | 轻量系统 | SIG_AppFramework     | [@zhengbin5](https://gitee.com/zhengbin5)         |
| 38   | I3N0OP  | 【全球化子系统】构建星期、单复数、数字开关国际化能力         | 轻量系统 | SIG_AppFramework     | [@zhengbin5](https://gitee.com/zhengbin5)         |
| 39   | I3NSY0  | 【轻量级图形】支持A4\A8、LUT8、TSC图片格式作为输入           | 轻量系统 | SIG_GraphicsandMedia | [@niulihua](https://gitee.com/niulihua)           |
| 40   | I3NT0R  | 【轻量级图形】支持多语言字体对齐                             | 轻量系统 | SIG_GraphicsandMedia | [@niulihua](https://gitee.com/niulihua)           |
| 41   | I3SNGO  | 【编译子系统】build_lite支持开源软件的通用patch框架          | 轻量系统 | SIG_CompileRuntime   | [@taiyipei](https://gitee.com/taiyipei)           |
| 42 | I3ZDIF  | RQ-[Demo&应用子系统][JSUI]【通用】JS动画（动画样式、渐变样式、转场样式、自定义字体样式） | 标准系统 | SIG_Samples | [@illybyy](https://gitee.com/illybyy) |
| 43 | I3ZDIG  | RQ-[Demo&应用子系统][JSUI]【通用】原子布局 | 标准系统 | SIG_Samples | [@illybyy](https://gitee.com/illybyy) |
| 44 | I3ZDIH  | RQ-[Demo&应用子系统][JSUI]【容器组件】新事件提醒（badge） | 标准系统 | SIG_Samples | [@illybyy](https://gitee.com/illybyy) |
| 45 | I3ZDII  | RQ-[Demo&应用子系统][JAVA UI]【HarmonyOS】自定义组件（CustomComponent） | 标准系统 | SIG_Samples | [@illybyy](https://gitee.com/illybyy) |
| 46 | I3ZDIJ  | RQ-[Demo&应用子系统][JAVA UI]【HarmonyOS】自定义布局（CustomLayout） | 标准系统 | SIG_Samples | [@illybyy](https://gitee.com/illybyy) |
| 47 | I3ZDIK  | RQ-[Demo&应用子系统][JS UI]【HarmonyOS】FA卡片（JsFACard） | 标准系统 | SIG_Samples | [@illybyy](https://gitee.com/illybyy) |
| 48 | I3ZDIL  | RQ-[Demo&应用子系统][多模]【HarmonyOS】多模输入（MultiModeInput） | 标准系统 | SIG_Samples | [@illybyy](https://gitee.com/illybyy) |
| 49 | I3ZDIM  | RQ-[Demo&应用子系统][多模]【HarmonyOS】多模输入事件标准化（MultimodalEvent） | 标准系统 | SIG_Samples | [@illybyy](https://gitee.com/illybyy) |
| 50 | I3ZDIN  | RQ-[Demo&应用子系统][JAVA UI]【HarmonyOS】Fraction | 标准系统 | SIG_Samples | [@illybyy](https://gitee.com/illybyy) |
| 51 | I3ZDIO  | RQ-[Demo&应用子系统][ServiceAbility]【HarmonyOS】前台服务（ForegroundService） | 标准系统 | SIG_Samples | [@illybyy](https://gitee.com/illybyy) |
| 52 | I3ZDIP  | RQ-[Demo&应用子系统][Ability测试]【HarmonyOS】Ability的自动化测试（Delegator） | 标准系统 | SIG_Samples | [@illybyy](https://gitee.com/illybyy) |
| 53 | I3ZDIQ  | RQ-[Demo&应用子系统][无障碍]【HarmonyOS】accessibility | 标准系统 | SIG_Samples | [@illybyy](https://gitee.com/illybyy) |
| 54 | I3ZDIR  | RQ-[Demo&应用子系统][JAVA UI]【HarmonyOS】AbilityForm | 标准系统 | SIG_Samples | [@illybyy](https://gitee.com/illybyy) |
| 55 | I3ZDIS  | RQ-[Demo&应用子系统][AI]【HarmonyOS】AI | 标准系统 | SIG_Samples | [@illybyy](https://gitee.com/illybyy) |
| 56 | I3ZDIT  | RQ-[Demo&应用子系统][媒体]【HarmonyOS】Audio | 标准系统 | SIG_Samples | [@illybyy](https://gitee.com/illybyy) |
| 57 | I3ZDIU  | RQ-[Demo&应用子系统][媒体]【HarmonyOS】AudioPlayer | 标准系统 | SIG_Samples | [@illybyy](https://gitee.com/illybyy) |
| 58 | I3ZDIW  | RQ-[Demo&应用子系统][设备]【HarmonyOS】BatteryInfo | 标准系统 | SIG_Samples | [@illybyy](https://gitee.com/illybyy) |
| 59 | I3ZDIX  | RQ-[Demo&应用子系统][设备]【HarmonyOS】指南针Compass | 标准系统 | SIG_Samples | [@illybyy](https://gitee.com/illybyy) |
| 60 | I3ZDIY  | RQ-[Demo&应用子系统][安全]【HarmonyOS】DataSecurity | 标准系统 | SIG_Samples | [@illybyy](https://gitee.com/illybyy) |
| 61 | I3ZDIZ  | RQ-[Demo&应用子系统][网络]【HarmonyOS】DistributedAbility | 标准系统 | SIG_Samples | [@illybyy](https://gitee.com/illybyy) |
| 62 | I3ZDJ0  | RQ-[Demo&应用子系统][通用]【HarmonyOS】DistributedCommonEvent | 标准系统 | SIG_Samples | [@illybyy](https://gitee.com/illybyy) |
| 63 | I3ZDJ1  | RQ-[Demo&应用子系统][数据]【HarmonyOS】DistributedPictures | 标准系统 | SIG_Samples | [@illybyy](https://gitee.com/illybyy) |
| 64 | I3ZDJ3  | RQ-[Demo&应用子系统][安全]【HarmonyOS】FaceRecognition | 标准系统 | SIG_Samples | [@illybyy](https://gitee.com/illybyy) |
| 65 | I3ZDJ4  | RQ-[Demo&应用子系统][设备]【HarmonyOS】NFC | 标准系统 | SIG_Samples | [@illybyy](https://gitee.com/illybyy) |
| 66 | I3ZDJ5  | RQ-[Demo&应用子系统][数据]【HarmonyOS】关系型数据库 | 标准系统 | SIG_Samples | [@illybyy](https://gitee.com/illybyy) |
| 67 | I3ZDJ6  | RQ-[Demo&应用子系统][数据]【HarmonyOS】对象关系映射数据库 | 标准系统 | SIG_Samples | [@illybyy](https://gitee.com/illybyy) |
| 68 | I3ZRBA  | 提供系统电源状态机管理能力 | 标准系统 | SIG_DistributedHardwareManagement | [@hhh2](https://gitee.com/hhh2) |
| 69 | I3ZRBV  | 提供休眠运行锁（RunningLock）管理能力 | 标准系统 | SIG_DistributedHardwareManagement | [@hhh2](https://gitee.com/hhh2) |
| 70 | I3ZRCV  | 提供休眠、唤醒流程管理及实现 | 标准系统 | SIG_DistributedHardwareManagement | [@hhh2](https://gitee.com/hhh2) |
| 71 | I3ZMUM  | 【分布式数据管理子系统】【本地数据库】 轻量级数据库JS API交付，对标开源+小程序 | 标准系统 | SIG_DataManagement | [@widecode](https://gitee.com/widecode) |
| 72 | I3ZMW4  | 【分布式数据管理子系统】【本地数据库】提供RDB和PREFERENCES的能力 | 标准系统 | SIG_DataManagement | [@widecode](https://gitee.com/widecode) |
| 73 | I3ZMX5  | 【分布式数据管理子系统】【本地数据库】 支持ResultSet滑动窗口能力 | 标准系统 | SIG_DataManagement | [@widecode](https://gitee.com/widecode) |
| 74 | I3YC8O  | 【分布式数据管理】【分布式数据库】支持JS接口创建分布式数据库 | 标准系统 | SIG_DataManagement | [@widecode](https://gitee.com/widecode) |
| 75 | I3WHJS  | 基于HDF驱动框架提供马达驱动程序适配 | 标准系统 | SIG_DriverFramework | [@chenfeng469](https://gitee.com/chenfeng469) |
| 76 | I3ZRA7  | 基于HDF驱动框架提供加速度传感器驱动程序适配 | 标准系统 | SIG_DriverFramework | [@chenfeng469](https://gitee.com/chenfeng469) |
| 77   | I3NN88 | 【DFX子系统】【HiDumper】LiteOS_M系统信息dump工具 | 轻量系统 | SIG_BscSoftSrv | [@kkup180](https://gitee.com/kkup180) |
| 78   | I3NN7D | 【DFX子系统】【HiDumper】LiteOS_A系统信息dump工具 | 轻量系统 | SIG_BscSoftSrv | [@kkup180](https://gitee.com/kkup180) |
| 79   | I3NT48| 【轻内核子系统】proc文件系统增强                             | 轻量系统 | SIG_Kernel           | [@kkup180](https://gitee.com/kkup180)             |
| 80   | I3WLDI| 【轻内核子系统】L0支持轻量级shell框架和常用调测命令           | 轻量系统 | SIG_Kernel           | [@kkup180](https://gitee.com/kkup180)             |
| 81   | I3WLCN| 【轻内核子系统】L0 LiteOS-M支持ARM9架构                     | 轻量系统 | SIG_Kernel           | [@kkup180](https://gitee.com/kkup180)             |
| 82   | I3NE8P  | 【电源管理】充放电状态查询接口                               | 轻量系统 | SIG_HardwareMng      | [@zianed](https://gitee.com/zianed)               |
| 83   | I3NIEJ  | 【电源管理】电量查询接口                                     | 轻量系统 | SIG_HardwareMng      | [@zianed](https://gitee.com/zianed)               |
| 84   | I3NIFG  | 【电源管理】实现并提供低功耗模式                             | 轻量系统 | SIG_HardwareMng      | [@zianed](https://gitee.com/zianed)               |
| 85   | I3NIFR | 【电源管理】提供低功耗模式统一API                            | 轻量系统 | SIG_HardwareMng      | [@zianed](https://gitee.com/zianed)               |
| 86   | I3NN7V  | 【DFX子系统】【BBoxDetector】LiteOS_A死机重启维测框架        | 轻量系统 | SIG_BscSoftSrv       | [@kkup180](https://gitee.com/kkup180)             |
| 87   | I3NN9B | 【DFX子系统】【BBoxDetector】LiteOS_M死机重启维测框架        | 轻量系统 | SIG_BscSoftSrv       | [@kkup180](https://gitee.com/kkup180)             |
| 88 | I3ZN3M | 【分布式数据管理】鸿蒙单框架L2分布式数据管理开源 | 标准系统 | SIG_DataManagement | [@widecode](https://gitee.com/widecode) |
| 89 | I40K12 | 【Samples】【JSUI】【容器组件】JS气泡（popup） | 标准系统 | SIG_Samples | [@illybyy](https://gitee.com/illybyy) |
| 90 | I40K1P | 【Samples】【JSUI】【容器组件】下拉刷新容器（refresh） | 标准系统 | SIG_Samples | [@illybyy](https://gitee.com/illybyy) |
| 91 | I40K2A | 【Samples】【数据】【HarmonyOS】轻量级偏好数据库 | 标准系统 | SIG_Samples | [@illybyy](https://gitee.com/illybyy) |
| 92 | I40NBW | 【应用子系统】鸿蒙单框架L2系统应用-设置开源-WLAN | 标准系统 | SIG_SysApplication | [@nicolaswang](https://gitee.com/nicolaswang) |
| 93 | I41LYF | 导航栏支持显示BACK、HOME、RECENT菜单 | 标准系统 | SIG_SysApplication | [@liuzhenyu2021](https://gitee.com/liuzhenyu2021) |
| 94 | I41LSC | 【SystemUI】SystemUI权限系统弹窗能力 | 标准系统 | SIG_SysApplication | [@liuzhenyu2021](https://gitee.com/liuzhenyu2021) |
| 95 | I3XY72 | c++与 js时间\日期和数字国际化能力构建 | 标准系统 | SIG_ApplicationFramework | [@meaty-bag-and-wangwang-meat](https://gitee.com/meaty-bag-and-wangwang-meat) |
|96  |I3XLZR |AudioService音频服务|标准系统|SIG_GraphicsandMedia|[@magekkkk](https://gitee.com/magekkkk)|
|97  |I3XM04 |Audio音频管理模块及API|标准系统|SIG_GraphicsandMedia|[@magekkkk](https://gitee.com/magekkkk)|
|98  |I3XM2C |CameraService 相机服务|标准系统|SIG_GraphicsandMedia|[@magekkkk](https://gitee.com/magekkkk)|
|99  |I3XM1U |Camera相机处理模块及API|标准系统|SIG_GraphicsandMedia|[@magekkkk](https://gitee.com/magekkkk)|
|100| I3XM34 |MediaService播放录制服务|标准系统|SIG_GraphicsandMedia|[@magekkkk](https://gitee.com/magekkkk)|
|101| I3XM2V |Media媒体处理模块及API|标准系统|SIG_GraphicsandMedia|[@magekkkk](https://gitee.com/magekkkk)|
|102| I41GOS |【分布式文件子系统】（需求）基于JS语言实现system.file接口|标准系统|SIG_DataManagement|[@panqinxu](https://gitee.com/panqinxu)|
|103| I426IN |【组网】自组网管理|标准系统|SIG_SoftBus|[@maerlii](https://gitee.com/maerlii)|
|104| I40NBW |WLAN设置项|标准系统|SIG_SystemApplication|[@xiongshiyi](https://gitee.com/xiongshiyi)|
|105| I400ZM |【应用子系统】【Launcher】桌面设置界面UX优化，Grid布局桌面支持图标拖动|标准系统|SIG_SystemApplication|[@xiongshiyi](https://gitee.com/xiongshiyi)|
|106| I41J7Q |支持Video组件|标准系统|SIG_ApplicationFramework|[@zhanghaibo0](https://gitee.com/zhanghaibo0)|
|107| I41JBF |支持Camera组件|标准系统|SIG_ApplicationFramework|[@zhanghaibo0](https://gitee.com/zhanghaibo0)|
|108| I41JG4 |支持JS与NAPI混合开发接口|标准系统|SIG_ApplicationFramework|[@zhanghaibo0](https://gitee.com/zhanghaibo0)|
|109| I3ZRBA |提供系统电源状态机管理能力|标准系统|SIG_DistributedHardwareManagement|[@zianed](https://gitee.com/zianed)|
|110| I3ZRBV |提供休眠运行锁（RunningLock）管理能力|标准系统|SIG_DistributedHardwareManagement|[@zianed](https://gitee.com/zianed)|
|111| I3ZRCV |提供休眠、唤醒流程管理及实现|标准系统|SIG_DistributedHardwareManagement|[@zianed](https://gitee.com/zianed)|
|112| I3WHJS |基于HDF驱动框架提供马达驱动程序适配|标准系统|SIG_DriverFramework|[@zianed](https://gitee.com/zianed)|
|113| I3ZRA7 |基于HDF驱动框架提供加速度传感器驱动程序适配|标准系统|SIG_DriverFramework|[@zianed](https://gitee.com/zianed)|
|114| I41HBJ |【驱动子系统】提供Audio HDI接口实现|标准系统|SIG_DriverFramework|[@zianed](https://gitee.com/zianed)|
|115| I41HBK |【驱动子系统】Audio 驱动框架用户态接口库|标准系统|SIG_DriverFramework|[@zianed](https://gitee.com/zianed)|
|116| I41HBM |【驱动子系统】提供支持MPI接口的用户态接口库|标准系统|SIG_DriverFramework|[@zianed](https://gitee.com/zianed)|
|117| I41HBN |【驱动子系统】HDI接口支持跨进程通信|标准系统|SIG_DriverFramework|[@zianed](https://gitee.com/zianed)|
|118| I41HBH |【驱动子系统】基于HDF驱动框架提供WIFI支持HDI接口能力|标准系统|SIG_DriverFramework|[@zianed](https://gitee.com/zianed)|
|119| I41HBG |【驱动子系统】基于HDF驱动框架提供WIFI支持P2P驱动能力|标准系统|SIG_DriverFramework|[@zianed](https://gitee.com/zianed)|
|120| I41HBI |【驱动子系统】提供Audio Driver Model驱动模型框架|标准系统|SIG_DriverFramework|[@zianed](https://gitee.com/zianed)|
|121| I41HBA |【驱动子系统】基于HDF驱动框架提供keyboard驱动能力|标准系统|SIG_DriverFramework|[@zianed](https://gitee.com/zianed)|
|122| I41HBZ |【驱动子系统】基于HDF框架提供USB device DDK|标准系统|SIG_DriverFramework|[@zianed](https://gitee.com/zianed)|
|123| I41HBU |【驱动子系统】基于HDF驱动框架提供Camera设备驱动模型框架层BufferManager|标准系统|SIG_DriverFramework|[@zianed](https://gitee.com/zianed)|
|124| I41HBV |【驱动子系统】基于HDF驱动框架提供Camera设备驱动模型框架层utils通用组件(thread、event、watchdog)r|标准系统|SIG_DriverFramework|[@zianed](https://gitee.com/zianed)|
|125| I41HBX |【驱动子系统】基于HDF驱动框架提供Camera驱动多平台扩展平台适配|标准系统|SIG_DriverFramework|[@zianed](https://gitee.com/zianed)|
|126| I41HBY |【驱动子系统】基于HDF框架提供USB host DDK|标准系统|SIG_DriverFramework|[@zianed](https://gitee.com/zianed)|
|127| I41HBP |【驱动子系统】基于HDF驱动框架提供相机标准南向接口Camera设备控制（CameraDevice）|标准系统|SIG_DriverFramework|[@zianed](https://gitee.com/zianed)|
|128| I41HBQ |【驱动子系统】基于HDF驱动框架提供相机标准南向接口Image流控制（StreamOperator）|标准系统|SIG_DriverFramework|[@zianed](https://gitee.com/zianed)|
|129| I41HBR |【驱动子系统】基于HDF驱动框架提供相机标准南向接口Camera HDI接口|标准系统|SIG_DriverFramework|[@zianed](https://gitee.com/zianed)|
|130| I41HBS |【驱动子系统】基于HDF驱动框架提供Pipeline管理 |标准系统|SIG_DriverFramework|[@zianed](https://gitee.com/zianed)|
|131| I41HBT |【驱动子系统】基于HDF驱动框架提供Camera设备驱动模型框架层设备管理DeviceManager|标准系统|SIG_DriverFramework|[@zianed](https://gitee.com/zianed)|
|132| I41HBO |【驱动子系统】基于HDF驱动框架提供相机标准南向接口Camera设备管理（CameraHost）|标准系统|SIG_DriverFramework|[@zianed](https://gitee.com/zianed)|
|133| I3ZVIO |Hi3516DV300开发板上，提供账号无关的设备认证能力|标准系统|SIG_DistributedHardwareManagement|[@locheng7](https://gitee.com/locheng7)|
|134| I40PB8 |应用侧取消本地所有通知|标准系统|SIG_SystemApplication|[@autumn330](https://gitee.com/autumn330)|
|135| I40PB0 |应用侧发布本地多行类型通知|标准系统|SIG_SystemApplication|[@autumn330](https://gitee.com/autumn330)|
|136| I40PB1 |应用侧发布本地长文本通知|标准系统|SIG_SystemApplication|[@autumn330](https://gitee.com/autumn330)|
|137| I40PB2 |应用侧发布本地内容资讯类型的普通文本通知|标准系统|SIG_SystemApplication|[@autumn330](https://gitee.com/autumn330)|
|138| I40PB3 |应用侧发布本地其他类型的普通文本通知|标准系统|SIG_SystemApplication|[@autumn330](https://gitee.com/autumn330)|
|139| I40PB4 |应用侧发布本地服务提醒类型的普通文本通知|标准系统|SIG_SystemApplication|[@autumn330](https://gitee.com/autumn330)|
|140| I40PB5 |应用侧发布本地社交通讯类型的普通文本通知|标准系统|SIG_SystemApplication|[@autumn330](https://gitee.com/autumn330)|
|141| I3XY72 |c++与 js时间\日期和数字国际化能力构建|标准系统|SIG_ApplicationFramework|[@meaty-bag-and-wangwang-meat](https://gitee.com/meaty-bag-and-wangwang-meat)|
|142| I42IMT |RQ-[Demo&应用子系统][分布式]OpenHarmony版本分布式计算器|标准系统|SIG_SystemApplication|[@purple-ding-gags](https://gitee.com/purple-ding-gags)|
|143| I42IKN |RQ-[Demo&应用子系统][分布式]OpenHarmony版本分布式音乐播放器|标准系统|SIG_SystemApplication|[@purple-ding-gags](https://gitee.com/purple-ding-gags)|
|144| I41JB1 |【应用子系统】【图库】图库基础功能-大图浏览|标准系统|SIG_SystemApplication|[@sunjunxiong](https://gitee.com/sunjunxiong)|
|145| I41J2Y |【应用子系统】【图库】图库基础功能-相册管理|标准系统|SIG_SystemApplication|[@sunjunxiong](https://gitee.com/sunjunxiong)|
|146| I41JBB |【应用子系统】【图库】图库基础功能-Toolbar操作|标准系统|SIG_SystemApplication|[@sunjunxiong](https://gitee.com/sunjunxiong)|


## OpenHarmony_release 3.0(LTS)版本特性清单：

状态说明：discussion(方案讨论，需求未接受)，Reject(未纳入版本)，developing(开发中)，Testing(测试中)，Accepted(已验收)

| no   | issue                                                        | feture description                                           | platform     | sig                  | owner                                             |
| :--- | ------------------------------------------------------------ | :----------------------------------------------------------- | :--------- | :------------------- | :------------------------------------------------ |
| 1  | I40PAV | 发布开启一个有页面的Ability的WantAgent通知 | 标准系统 | SIG_ApplicationFramework | [@autumn330](https://gitee.com/autumn330) |
| 2  | I40PAW | 通知删除接口 | 标准系统 | SIG_ApplicationFramework | [@autumn330](https://gitee.com/autumn330) |
| 3  | I40PAX | 查看Active通知内容和Active通知个数的接口 | 标准系统 | SIG_ApplicationFramework | [@autumn330](https://gitee.com/autumn330) |
| 4  | I40PAY | 通知取消订阅 | 标准系统 | SIG_ApplicationFramework | [@autumn330](https://gitee.com/autumn330) |
| 5  | I40PAZ | 通知订阅 | 标准系统 | SIG_ApplicationFramework | [@autumn330](https://gitee.com/autumn330) |
| 6  | I426IT | 【组网】组网单框架FWK | 标准系统 | SIG_SoftBus | [@maerlii](https://gitee.com/maerlii) |
| 7  | I426IM | 【组网】组网框架构建：安全 | 标准系统 | SIG_SoftBus | [@maerlii](https://gitee.com/maerlii) |
| 8  | I426IQ | 【组网】节点信息管理 | 标准系统 | SIG_SoftBus | [@maerlii](https://gitee.com/maerlii) |
| 9  | I3NIMY | 【连接】BR/EDR模块管理 | 标准系统 | SIG_SoftBus | [@tianmeimimi](https://gitee.com/tianmeimimi) |
| 10 | I426J0 | 【传输】通道管理 | 标准系统 | SIG_SoftBus | [@maerlii](https://gitee.com/maerlii) |
| 11 | I3NIZD | 【连接】连接策略的定义与管理 | 标准系统 | SIG_SoftBus | [@tianmeimimi](https://gitee.com/tianmeimimi) |
| 12 | I426IW | 【连接】连接状态机功能实现 | 标准系统 | SIG_SoftBus | [@maerlii](https://gitee.com/maerlii) |
| 13 | I42UO1 | RQ-[Demo&应用子系统][JSUI][容器组件]JS堆叠容器（stack） | 标准系统 | SIG_SystemApplication | [@adslk](https://gitee.com/adslk) |
| 14 | I42X0C | RQ-[Demo&应用子系统][JSUI][容器组件]JS步骤导航器（stepper） | 标准系统 | SIG_SystemApplication | [@gaohui100](https://gitee.com/gaohui100) |
| 15 | I42WY6 | RQ-[Demo&应用子系统][JSUI][容器组件]JS滑动容器（swiper） | 标准系统 | SIG_SystemApplication | [@gaohui100](https://gitee.com/gaohui100) |
| 16 | I42UNK | RQ-[Demo&应用子系统][JSUI][容器组件]JS页签容器（tabs） | 标准系统 | SIG_SystemApplication | [@adslk](https://gitee.com/adslk) |
| 17 | I42S96 | RQ-[Demo&应用子系统][数据][HarmonyOS]融合搜索 | 标准系统 | SIG_SystemApplication | [@guojin26](https://gitee.com/guojin26) |
| 18 | I40PB6 | 应用侧增加slot | 标准系统 | SIG_ApplicationFramework | [@autumn330](https://gitee.com/autumn330) |
| 19 | I40PB7 | 应用侧删除slot | 标准系统 | SIG_ApplicationFramework | [@autumn330](https://gitee.com/autumn330) |
| 20 | I42WA2 | L2 提供 OHOS LLVM编译 | 标准系统 | SIG_CompileRuntime | [@zhuoli72](https://gitee.com/zhuoli72) |
| 21 | I3U4DP | musl侵入式修改分离 | 标准系统 | SIG_CompileRuntime | [@caoruihong](https://gitee.com/caoruihong) |
| 22 | I42WDD | L2 musl c库支持 | 标准系统 | SIG_CompileRuntime | [@zhuoli72](https://gitee.com/zhuoli72) |
| 23 | I4014F | 【帐号子系统】JS API交付，开源+小程序 | 标准系统 | SIG_BasicSoftwareService | [@verystone](https://gitee.com/verystone) |
| 24 | I436VH | 创建串行任务分发器，使用串行任务分发器执行任务 | 标准系统 | SIG_ApplicationFramework | [@autumn330](https://gitee.com/autumn330) |
| 25 | I436VI | 创建专有任务分发器，使用专有任务分发器执行任务 | 标准系统 | SIG_ApplicationFramework | [@autumn330](https://gitee.com/autumn330) |
| 26 | I436VJ | 创建全局并发任务分发器，使用全局并发任务分发器执行任务 | 标准系统 | SIG_ApplicationFramework | [@autumn330](https://gitee.com/autumn330) |
| 27 | I436VK | 创建并发任务分发器，使用并发任务分发器执行任务 | 标准系统 | SIG_ApplicationFramework | [@autumn330](https://gitee.com/autumn330) |
| 28 | I436VL | ces部件化改造 | 标准系统 | SIG_ApplicationFramework | [@autumn330](https://gitee.com/autumn330) |
| 29 | I436VM | ans部件化改造 | 标准系统 | SIG_ApplicationFramework | [@autumn330](https://gitee.com/autumn330) |
| 30 | I436VX | 提供分布式的回调Native接口 | 标准系统 | SIG_ApplicationFramework | [@autumn330](https://gitee.com/autumn330) |
| 31 | I436N0 | 支持应用包信息分布式存储能力 | 标准系统 | SIG_ApplicationFramework | [@fuzhangHW](https://gitee.com/fuzhangHW) |
| 32 | I4312I | 支持全新开发范式 | 标准系统 | SIG_ApplicationFramework | [@zhanghaibo0](https://gitee.com/zhanghaibo0) |
| 33 | I4313W | 【分布式文件子系统】（需求）ext4&f2fs拍包工具 | 标准系统 | SIG_DataManagement | [@panqinxu](https://gitee.com/panqinxu) |
| 34 | I41H57 | 【驱动子系统】基于HDF驱动框架提供ADC平台总线驱动 | 标准系统 | SIG_DriverFramework | [@zianed](https://gitee.com/zianed) |
| 35 | I3QEVG | 【分布式调度】轻设备获取调用者APP的APPID并传输到富设备      | 轻量系统 | SIG_AppFramework     | [@lijiarun](https://gitee.com/lijiarun)            |
|36  | I43W4L |RQ-[Demo&应用子系统][JSUI][基础组件]JS基础组件|标准系统|SIG_SystemApplication|[@guojin26](https://gitee.com/guojin26)|
|37  | I43XA7 |RQ-[Demo&应用子系统][JSUI][图表组件]chart|标准系统|SIG_SystemApplication|[@adslk](https://gitee.com/adslk)|
|38  | I43W8L |RQ-[Demo&应用子系统][JSUI][滑动选择器组件] picker|标准系统|SIG_SystemApplication|[@gaohui100](https://gitee.com/gaohui100)|
|39  | I41HBB |【驱动子系统】基于HDF驱动框架提供mouse驱动能力|标准系统|SIG_DriverFramework|[@zianed](https://gitee.com/zianed)|
| 40 | I3XCB5 | 【应用程序框架】按照应用粒度的存储资源使用统计       | 轻量系统 | SIG_AppFramework     | [@autumn](https://gitee.com/autumn330)            |
| 41 | I3NK7D | 【多媒体子系统】适配新南向接口                               | 轻量系统 | SIG_GraphicsAndMedia | [@zhu-mingliang](https://gitee.com/zhu-mingliang)   |
| 42 | I3NM60 | 【多媒体子系统】相机metadata管理及相机静态能力查询           | 轻量系统 | SIG_GraphicsAndMedia | [@zhu-mingliang](https://gitee.com/zhu-mingliang)   |
| 43 | I3NM6F | 【多媒体子系统】相机设备管理                                 | 轻量系统 | SIG_GraphicsAndMedia | [@zhu-mingliang](https://gitee.com/zhu-mingliang)   |
| 44 | I3NM73 | 【多媒体子系统】相机图像帧管理                               | 轻量系统 | SIG_GraphicsAndMedia | [@zhu-mingliang](https://gitee.com/zhu-mingliang)   |
| 45 | I3NM8J | 【多媒体子系统】本地mp3播放支持                              | 轻量系统 | SIG_GraphicsAndMedia | [@zhu-mingliang](https://gitee.com/zhu-mingliang)   |
| 46 | I3NMMU | 【多媒体子系统】编码视频流和音频流处理支持                   | 轻量系统 | SIG_GraphicsAndMedia | [@zhu-mingliang](https://gitee.com/zhu-mingliang)   |
|47  | I43G6T |WM Client架构演进|标准系统|SIG_GraphicsandMedia|[@lz-230](https://gitee.com/lz-230)|
|48  | I43HMM |WM Server架构演进|标准系统|SIG_GraphicsandMedia|[@lz-230](https://gitee.com/lz-230)|
|49  | I43I3O |RQ-[图形子系统][vsync模块][vsync]vsync架构演进|标准系统|SIG_GraphicsandMedia|[@lz-230](https://gitee.com/lz-230)|
|50  | I44TNC |RQ-[Demo&应用子系统][JSUI][Menu/Option]JSMenu|标准系统|SIG_SystemApplication|[@guojin26](https://gitee.com/guojin26)|
|51  | I452UD |RQ-[Demo&应用子系统][JSUI]【OpenHarmony】工具栏|标准系统|SIG_SystemApplication|[@adslk](https://gitee.com/adslk)|
|52  | I44TN0 |RQ-[Demo&应用子系统][JSUI][滑动条] slider|标准系统|SIG_SystemApplication|[@gaohui100](https://gitee.com/gaohui100)|
|53  | I41HC0 |【驱动子系统】基于HDF驱动框架提供Display HDI的服务化|标准系统|SIG_DriverFramework|[@zianed](https://gitee.com/zianed)|
|54  | I41LWL |【SystemUI】状态栏最大最小化|标准系统|SIG_SystemApplication|[@liuzhenyu2021](https://gitee.com/liuzhenyu2021)|
|55  | I3NIOF |【传输】传输SDK|轻量系统|SIG_SoftBus|[@jiangkuaixue](https://gitee.com/jiangkuaixue)|
|56  | I3XHVJ |支持全量升级包升级|标准系统|SIG_BasicSoftwareService|[@ailorna](https://gitee.com/ailorna)|
|57  | I3XHVP |支持差分升级包升级|标准系统|SIG_BasicSoftwareService|[@ailorna](https://gitee.com/ailorna)|
|58  | I436VT |安装读取shortcut信息|标准系统|SIG_ApplicationFramework|[@autumn330](https://gitee.com/autumn330)|
|59  | I3NN1Z | 【应用程序框架】轻量级实现弹窗授权动态授权机制               | 轻量系统 | SIG_AppFramework     | [@autumn](https://gitee.com/autumn330)              |
|60  | I3NTAZ | 【安全】轻量级实现弹窗授权动态授权机制                       | 轻量系统 | SIG_Security         | [@scuteehuangjun](https://gitee.com/scuteehuangjun) |
|61  | I45ZKP |RQ-[Demo&应用子系统][JSUI][画布组件] JsCanvas|标准系统|SIG_SystemApplication|[@gaohui100](https://gitee.com/gaohui100)|
|62  | I466KX |RQ-[Demo&应用子系统][JSUI]【OpenHarmony】 栅格布局|标准系统|SIG_SystemApplication|[@adslk](https://gitee.com/adslk)|
|63  | I45YM2 |RQ-[Demo&应用子系统][JS UI]【OpenHarmony】JS自定义组件（JSUICustomComponent）|标准系统|SIG_SystemApplication|[@guojin26](https://gitee.com/guojin26)|
|64  | I44Y4J |RQ-[Demo&应用子系统][JS UI]【HarmonyOS】自适应卡片（AdaptiveServiceWidget）|标准系统|SIG_SystemApplication|[@caopan_com](https://gitee.com/caopan_com)|
|65  | I44Y0N |RQ-[Demo&应用子系统][JS UI]【HarmonyOS】自适应页面（AdaptivePortalPage）|标准系统|SIG_SystemApplication|[@wangli325](https://gitee.com/wangli325)|
|66  | I44Y15 |RQ-[Demo&应用子系统][JS UI]【HarmonyOS】自适应效率型首页（AdaptivePortalList）|标准系统|SIG_SystemApplication|[@wangli325](https://gitee.com/wangli325)|
|67  | I46ZCN |RQ-[Demo&应用子系统][JAVA UI]【HarmonyOS】添加NativeLayer示例|标准系统|SIG_SystemApplication|[@guojin26](https://gitee.com/guojin26)|
|68  | I3ZVTJ |【分布式任务调度子系统】接收远端拉起FA请求，跨设备拉起远端FA|标准系统|SIG_DataManagement|[@zjucx](https://gitee.com/zjucx)|
|69  | I3ZVTT |【分布式任务调度子系统】鸿蒙单框架L2分布式能力建设-SAMGR模块构建|标准系统|SIG_DataManagement|[@zjucx](https://gitee.com/zjucx)|
|70  | I3ZMY9 |【分布式数据管理子系统】【本地数据库】 XTS测试用例|标准系统|SIG_DataManagement|[@widecode](https://gitee.com/widecode)|
|71  | I41H55 |【驱动子系统】基于HDF驱动框架提供I2S/PCM平台总线驱动|标准系统|SIG_DistributedHardwareManagement|[@zianed](https://gitee.com/zianed)|
|72  | I41HBF |【驱动子系统】基于HDF驱动框架提供Display驱动模型兼容DRM显示框架|标准系统|SIG_DistributedHardwareManagement|[@zianed](https://gitee.com/zianed)|
|73  | I46J19 |add jsapi in compileruntime|标准系统|SIG_CompileRuntime|[@xliu-huanwei](https://gitee.com/xliu-huanwei)|
|74  | I46N37 |升级quickjs使用worker|标准系统|SIG_CompileRuntime|[@wpyhuawei](https://gitee.com/wpyhuawei)|
|75  | I40PBC |应用侧发布本地分组的普通通知|标准系统|SIG_ApplicationFramework|[@autumn330](https://gitee.com/autumn330)|
|76  | I40PBF |在免打扰模式下发布通知|标准系统|SIG_ApplicationFramework|[@autumn330](https://gitee.com/autumn330)|
|77  | I40PBG |发布开启一个无页面的Ability的wantAgent|标准系统|SIG_ApplicationFramework|[@autumn330](https://gitee.com/autumn330)|
|78  | I40PBH |取消WantAgent的实例|标准系统|SIG_ApplicationFramework|[@autumn330](https://gitee.com/autumn330)|
|79  | I40PBI |发布公共事件的WantAgent通知|标准系统|SIG_ApplicationFramework|[@autumn330](https://gitee.com/autumn330)|
|80  | I40PBM |应用侧取消本地通知|标准系统|SIG_ApplicationFramework|[@autumn330](https://gitee.com/autumn330)|
|81  | I40PBN |应用侧发布声音通知|标准系统|SIG_ApplicationFramework|[@autumn330](https://gitee.com/autumn330)|
|82  | I40PBO |应用侧发布振动通知|标准系统|SIG_ApplicationFramework|[@autumn330](https://gitee.com/autumn330)|
|83  | I40PBP |应用侧发布本地有输入框的通知（NotificationUserInput）|标准系统|SIG_ApplicationFramework|[@autumn330](https://gitee.com/autumn330)|
|84  | I46W6Q | 【全球化】新增31种语言支持              | 轻量系统 | SIG_AppFramework     | [@zhiweilai](https://gitee.com/zhiweilai)              |
|85  | I47B4N |RQ-[Demo&应用子系统][JSUI]【OpenHarmony】页面路由|标准系统|SIG_SystemApplication|[@gaohui100](https://gitee.com/gaohui100)|
|86  | I479L2 |RQ-[Demo&应用子系统][JSUI]【OpenHarmony】 系统时间与定时器|标准系统|SIG_SystemApplication|[@adslk](https://gitee.com/adslk)|
|87  | I48CJ3 |RQ-[Demo&应用子系统][JSUI]【OpenHarmony】设备信息|标准系统|SIG_SystemApplication|[@caopan_com](https://gitee.com/caopan_com)|
|88  | I48VL4 |RQ-[Demo&应用子系统][JSUI]【OpenHarmony】设置屏幕亮度|标准系统|SIG_SystemApplication|[@caopan_com](https://gitee.com/caopan_com)|
|89  | I49B4X |RQ-[Demo&应用子系统][JSUI]【OpenHarmony】国际化|标准系统|SIG_SystemApplication|[@gaohui100](https://gitee.com/gaohui100)|
|90  | I3ZXZF |【Kernel升级适配】OpenHarmony L2内核版本升级至5.10|标准系统|SIG_Kernel|[@z-jax](https://gitee.com/z-jax)|
|91  | I41HC1 |【驱动子系统】基于HDF驱动框架提供Codec HDI的服务化|标准系统|SIG_DriverFramework|[@zianed](https://gitee.com/zianed)|
|92  | I41HB1 |【驱动子系统】基于HDF驱动框架提供陀螺仪Sensor驱动能力|标准系统|SIG_DriverFramework|[@zianed](https://gitee.com/zianed)|
|93  | I41HBE |【驱动子系统】基于HDF驱动框架提供backlight驱动能力|标准系统|SIG_DriverFramework|[@zianed](https://gitee.com/zianed)|
|94  | I41HB5 |【驱动子系统】基于HDF驱动框架提供压力Sensor驱动能力|标准系统|SIG_DriverFramework|[@zianed](https://gitee.com/zianed)|
|95  | I41HB4 |【驱动子系统】基于HDF驱动框架提供霍尔Sensor驱动能力|标准系统|SIG_DriverFramework|[@zianed](https://gitee.com/zianed)|
|96  | I41H50 |【驱动子系统】驱动hdi-gen开发工具|标准系统|SIG_DriverFramework|[@zianed](https://gitee.com/zianed)|
|97  | I41HBD |【驱动子系统】基于HDF驱动框架提供Encoder驱动能力|标准系统|SIG_DriverFramework|[@zianed](https://gitee.com/zianed)|
|98  | I3NJ0R |【发现】发现调度模块功能实现|标准系统|SIG_SoftBus|[@tianmeimimi](https://gitee.com/tianmeimimi)|
|99  | I3NIPH |【传输】消息传输|标准系统|SIG_SoftBus|[@tianmeimimi](https://gitee.com/tianmeimimi)|
|100 | I3NIPO |【传输】Byte传输|标准系统|SIG_SoftBus|[@tianmeimimi](https://gitee.com/tianmeimimi)|
|101 | I3NIOF |【传输】传输SDK|标准系统|SIG_SoftBus|[@tianmeimimi](https://gitee.com/tianmeimimi)|
|102 | I3NINO |【传输】会话协商|标准系统|SIG_SoftBus|[@tianmeimimi](https://gitee.com/tianmeimimi)|
|103 | I40PBD |2个不同的slot，加入到同一个Slot组里面|标准系统|SIG_ApplicationFramework|[@autumn330](https://gitee.com/autumn330)|
|104 | I40PBJ |提供管理角标显示/隐藏的接口|标准系统|SIG_ApplicationFramework|[@autumn330](https://gitee.com/autumn330)|
|105 | I40PBK |提供管理通知许可的接口（设置和查询）|标准系统|SIG_ApplicationFramework|[@autumn330](https://gitee.com/autumn330)|
|106 | I40PBL |应用删除SlotGroup|标准系统|SIG_ApplicationFramework|[@autumn330](https://gitee.com/autumn330)|
|107 | I40PBQ |发布带ActionButton的本地通知|标准系统|SIG_ApplicationFramework|[@autumn330](https://gitee.com/autumn330)|
|108 | I40PBR |通知流控处理|标准系统|SIG_ApplicationFramework|[@autumn330](https://gitee.com/autumn330)|
|109 | I40PBT |死亡监听|标准系统|SIG_ApplicationFramework|[@autumn330](https://gitee.com/autumn330)|
|110 | I40PBU |通知shell命令|标准系统|SIG_ApplicationFramework|[@autumn330](https://gitee.com/autumn330)|
|111 | I49HOX |工具链提供维测能力|标准系统|SIG_CompileRuntime|[@dhy308](https://gitee.com/dhy308)|
|112 | I40OPG |【定时服务】非功能性需求|标准系统|SIG_ApplicationFramework|[@autumn330](https://gitee.com/autumn330)|
|113 | I40OPH |【定时服务】时间时区同步|标准系统|SIG_ApplicationFramework|[@autumn330](https://gitee.com/autumn330)|
|114 | I40OPI |【定时服务】定时器功能|标准系统|SIG_ApplicationFramework|[@autumn330](https://gitee.com/autumn330)|
|115 | I40OPJ |【定时服务】时间时区管理|标准系统|SIG_ApplicationFramework|[@autumn330](https://gitee.com/autumn330)|
|116 | I3ZQED |【帐号子系统】添加分布式帐号登录状态IPC消息权限检查|标准系统|SIG_BasicSoftwareService|[@verystone](https://gitee.com/verystone)|
|117 | I40MWK |构建语言和地区配置和区域显示能力|标准系统|SIG_ApplicationFramework|[@mengjingzhimo](https://gitee.com/mengjingzhimo)|
|118 | I40OWT |【搜网】Radio状态管理|标准系统|SIG_SoftBus|[@zhang-hai-feng](https://gitee.com/zhang-hai-feng)|
|119 | I40OWU |【搜网】搜网注册|标准系统|SIG_SoftBus|[@zhang-hai-feng](https://gitee.com/zhang-hai-feng)|
|120 | I40OWN |【SIM卡】卡状态处理|标准系统|SIG_SoftBus|[@zhang-hai-feng](https://gitee.com/zhang-hai-feng)|
|121 | I40OWO |【SIM卡】解锁卡pin、puk|标准系统|SIG_SoftBus|[@zhang-hai-feng](https://gitee.com/zhang-hai-feng)|
|122 | I40OWM |【SIM卡】卡账户处理|标准系统|SIG_SoftBus|[@zhang-hai-feng](https://gitee.com/zhang-hai-feng)|
|123 | I40OX3 |【短彩信】提供小区广播的能力|标准系统|SIG_SoftBus|[@zhang-hai-feng](https://gitee.com/zhang-hai-feng)|
|124 | I40OX6 |【短彩信】提供短信基本配置功能|标准系统|SIG_SoftBus|[@zhang-hai-feng](https://gitee.com/zhang-hai-feng)|
|125 | I40OSY |【SIM卡】提供拷贝、删除、更新、获取卡短信的能力供电话子系统内部使用|标准系统|SIG_SoftBus|[@zhang-hai-feng](https://gitee.com/zhang-hai-feng)|
|126 | I40OTN |【通话管理】CS域发送MMI命令|标准系统|SIG_SoftBus|[@zhang-hai-feng](https://gitee.com/zhang-hai-feng)|
|127 | I40OTS |【通话管理】CS域DTMF功能|标准系统|SIG_SoftBus|[@zhang-hai-feng](https://gitee.com/zhang-hai-feng)|
|128 | I40OTW |【通话管理】CS通话基础功能|标准系统|SIG_SoftBus|[@zhang-hai-feng](https://gitee.com/zhang-hai-feng)|
|129 | I40OTX |【通话管理】CS通话扩展功能|标准系统|SIG_SoftBus|[@zhang-hai-feng](https://gitee.com/zhang-hai-feng)|
|130 | I40OTY |【SIM卡】G/U卡文件信息获取、保存|标准系统|SIG_SoftBus|[@zhang-hai-feng](https://gitee.com/zhang-hai-feng)|
|131 | I40OU3 |【搜网】驻网信息(运营商信息及SPN广播GSM）|标准系统|SIG_SoftBus|[@zhang-hai-feng](https://gitee.com/zhang-hai-feng)|
|132 | I40OU5 |【搜网】网络状态(漫游、GSM/LTE/WCDMA接入技术）|标准系统|SIG_SoftBus|[@zhang-hai-feng](https://gitee.com/zhang-hai-feng)|
|133 | I40OU7 |【搜网】信号强度(WCDMA/GSM/LTE)|标准系统|SIG_SoftBus|[@zhang-hai-feng](https://gitee.com/zhang-hai-feng)|
|134 | I40OUC |【短彩信】提供发送短信功能|标准系统|SIG_SoftBus|[@zhang-hai-feng](https://gitee.com/zhang-hai-feng)|
|135 | I40OUF |【短彩信】提供接收短信功能|标准系统|SIG_SoftBus|[@zhang-hai-feng](https://gitee.com/zhang-hai-feng)|
|136 | I40OTT |【通话管理】CS域呼叫等待功能|标准系统|SIG_SoftBus|[@zhang-hai-feng](https://gitee.com/zhang-hai-feng)|
|137 | I49HPE |独立发布SDK能力支持|标准系统|SIG_ApplicationFramework|[@zhanghaibo0](https://gitee.com/zhanghaibo0)|
|138 | I49CTN |【hdc_std】支持openharmony sdk独立发布|标准系统|SIG_R&DToolChain|[@chuxuezhe111](https://gitee.com/chuxuezhe111)|
|139 | I49HLR |【Build】OpenHarmony SDK的打包和编译|标准系统|SIG_CompileRuntime|[@weichaox](https://gitee.com/weichaox)|
|140 | I40OWF |【SIM卡】随卡功能实现，包括获取当前运营商配置等|标准系统|SIG_SoftBus|[@zhang-hai-feng](https://gitee.com/zhang-hai-feng)|
|141 | I3NT3F | 【轻内核子系统】内核支持trace功能                            | 轻量系统 | SIG_Kernel           | [@kkup180](https://gitee.com/kkup180)               |
|142 | I3NT63 | 【轻内核子系统】pagecache功能完善                            | 轻量系统 | SIG_Kernel           | [@kkup180](https://gitee.com/kkup180)               |
|143 | I49V7K |test code static check|标准系统|SIG_BasicSoftwareService|[@skyblackleon](https://gitee.com/skyblackleon)|
|144 | I49XVK |AA/APPEXE/IPC合入master|标准系统|SIG_ApplicationFramework|[@fuzhangHW](https://gitee.com/fuzhangHW)|
|145 | I43UU4 |JS应用生命周期补充支持|标准系统|SIG_ApplicationFramework|[@zhanghaibo0](https://gitee.com/zhanghaibo0)|
|146 | I43V4W |支持使用JS开发service ability|标准系统|SIG_ApplicationFramework|[@zhanghaibo0](https://gitee.com/zhanghaibo0)|
|147 | I43V73 |支持使用JS开发data ability|标准系统|SIG_ApplicationFramework|[@zhanghaibo0](https://gitee.com/zhanghaibo0)|
|148 | I43UZ0 |支持系统服务弹窗|标准系统|SIG_ApplicationFramework|[@zhanghaibo0](https://gitee.com/zhanghaibo0)|
|149 | I3ZVIO |Hi3516DV300开发板上，提供账号无关的设备认证能力|标准系统|SIG_DistributedHardwareManagement|[@locheng7](https://gitee.com/locheng7)|
|150 | I3ZVUD |L2系统上为系统服务（应用）提供kit接口（JS）|标准系统|SIG_DistributedHardwareManagement|[@locheng7](https://gitee.com/locheng7)|
|151 | I4A3YY |ACE2.0方舟对接|标准系统|SIG_CompileRuntime|[@guobingbing3](https://gitee.com/guobingbing3)|
|152 | I40SQU |【工具链】提供hdc java lib|标准系统|SIG_R&DToolChain|[@chuxuezhe111](https://gitee.com/chuxuezhe111)|
|153 | I474ZZ |【分布式数据管理】【JS API接口】增加关系型数据库JS API|标准系统|SIG_DataManagement|[@mangtsang](https://gitee.com/mangtsang)|
|154 | I40PBE |应用侧发布本地带应用ICON的普通通知|标准系统|SIG_ApplicationFramework|[@autumn330](https://gitee.com/autumn330)|
|155 | I43UU4 |JS应用生命周期补充支持|标准系统|SIG_ApplicationFramework|[@zhanghaibo0](https://gitee.com/zhanghaibo0)|
|156 | I43UU4 |JS应用生命周期补充支持|标准系统|SIG_ApplicationFramework|[@zhanghaibo0](https://gitee.com/zhanghaibo0)|
|157 | I43V4W |支持使用JS开发service ability|标准系统|SIG_ApplicationFramework|[@zhanghaibo0](https://gitee.com/zhanghaibo0)|
|158 | I43V73 |支持使用JS开发data ability|标准系统|SIG_ApplicationFramework|[@zhanghaibo0](https://gitee.com/zhanghaibo0)|
|159 | I43UZ0 |支持系统服务弹窗|标准系统|SIG_ApplicationFramework|[@zhanghaibo0](https://gitee.com/zhanghaibo0)|
|160 | I42TIB |RQ-[媒体子系统][Media][媒体录制器]音视频录制及API|标准系统|SIG_GraphicsandMedia|[@magekkkk](https://gitee.com/magekkkk)|
|161 | I42TMC |RQ-[媒体子系统][Camera][相机框架管理]相机录像功能|标准系统|SIG_GraphicsandMedia|[@magekkkk](https://gitee.com/magekkkk)|
|162 | I3ZVT4 |【分布式任务调度子系统】鸿蒙单框架L2分布式能力建设-跨设备绑定元能力|标准系统|SIG_DataManagement|[@zjucx](https://gitee.com/zjucx)|
|163 | I49HB0 |【分布式任务调度子系统】启动、绑定能力添加组件visible权限校验|标准系统|SIG_DataManagement|[@zmxlye](https://gitee.com/zmxlye)|
|164 | I40121 |【Kernel升级适配】HDF适配OpenHarmony 5.10内核|标准系统|SIG_DriverFramework|[@yuanbogit](https://gitee.com/yuanbogit)|
|165 | I3ZY55 |【Kernel升级适配】Hi3516DV300开发板适配OpenHarmony 5.10内核|标准系统|SIG_Kernel|[@z-jax](https://gitee.com/z-jax)|
|166 | I441K6 |L2构建分布式权限管理主体标识转换能力|标准系统|SIG_Security|[@xuwenfang](https://gitee.com/xuwenfang)|
|167 | I4446U |L2构建分布式权限同步能力|标准系统|SIG_Security|[@xuwenfang](https://gitee.com/xuwenfang)|
|168 | I4447R |L2构建分布式权限管理能力|标准系统|SIG_Security|[@xuwenfang](https://gitee.com/xuwenfang)|
|169 | I3NIQX |【连接】BLE模块管理|标准系统|SIG_SoftBus|[@tianmeimimi](https://gitee.com/tianmeimimi)|
|170 | I426J6 |【传输】文件传输|标准系统|SIG_SoftBus|[@maerlii](https://gitee.com/maerlii)|
|171 | I426J3 |【传输】TCP通道复用打开和关闭|标准系统|SIG_SoftBus|[@maerlii](https://gitee.com/maerlii)|
|172 | I40PBB |应用侧发布本地图片类型通知|标准系统|SIG_ApplicationFramework|[@autumn330](https://gitee.com/autumn330)|
|173 | I40PBS |通知图片大小限制|标准系统|SIG_ApplicationFramework|[@autumn330](https://gitee.com/autumn330)|
|174 | I4BE9N |modify dataabilityDB for LTS branch|标准系统|SIG_BasicSoftwareService|[@skyblackleon](https://gitee.com/skyblackleon)|
|175 | I48DFB |【分布式任务调度子系统】分布式调度支持元能力迁移管理能力|标准系统|SIG_DataManagement|[@wangdd__zju](https://gitee.com/wangdd__zju)|
|176 | I48BOB |【分布式文件子系统】（需求）JS 存储框架开发|标准系统|SIG_DataManagement|[@gudehe](https://gitee.com/gudehe)|
|177 | I4A3LY |【分布式文件子系统】（需求）JS 存储框架挂载能力 - FS manager|标准系统|SIG_DataManagement|[@zhangzhiwi](https://gitee.com/zhangzhiwi)|
|178 | I4BXPQ |【DFX】libhicollie支持OpenHarmony standard|标准系统|SIG_BasicSoftwareService|[@stesen](https://gitee.com/stesen)|
|179 | I4BXMM |【DFX】libhitrace支持OpenHarmony standard|标准系统|SIG_BasicSoftwareService|[@stesen](https://gitee.com/stesen)|
|180 | I4BY0R |【DFX】鸿蒙应用事件打点接口与鸿蒙应用事件管理（JS）|标准系统|SIG_BasicSoftwareService|[@lyj](https://gitee.com/lyj_love_code)|

## OpenHarmony_release 3.1(Beta)版本特性清单：
状态说明：discussion(方案讨论，需求未接受)，Reject(未纳入版本)，developing(开发中)，Testing(测试中)，Accepted(已验收)

| no   | issue                                                        | feture description                                           | platform     | sig                  | owner                                             |
| :--- | ------------------------------------------------------------ | :----------------------------------------------------------- | :--------- | :------------------- | :------------------------------------------------ |
| 1   | I3XGJH | init基础环境构建                             | 轻量系统 | SIG_BscSoftSrv| [@handyohos](https://gitee.com/handyohos) |
| 2   | I3XGKV | sytemparameter管理                            | 轻量系统 | SIG_BscSoftSrv| [@handyohos](https://gitee.com/handyohos) |
| 3   | I3XGLN | init 脚本管理                            | 轻量系统 | SIG_BscSoftSrv| [@handyohos](https://gitee.com/handyohos) |
| 4   | I3XGM3 | init 服务管理                            | 轻量系统 | SIG_BscSoftSrv| [@handyohos](https://gitee.com/handyohos) |
| 5   | I3XGMQ | 基础权限管理                             | 轻量系统 | SIG_BscSoftSrv| [@handyohos](https://gitee.com/handyohos) |
| 6   | I3XGN8 | bootimage构建和加载                             | 轻量系统 | SIG_BscSoftSrv| [@handyohos](https://gitee.com/handyohos) |
| 7   | I3XGO7 | uevent 管理                            | 轻量系统 | SIG_BscSoftSrv| [@handyohos](https://gitee.com/handyohos) |
| 8   | I4BX5Z | 【需求】HiStreamer支持音频播放和控制             | 轻量系统 | SIG_GraphicsandMedia         | [@guodongchen](https://gitee.com/guodongchen) |
| 9   | I4BX8A | 【需求】HiStreamer支持常见音频格式mp3/wav的播放   | 轻量系统 | SIG_GraphicsandMedia         | [@guodongchen](https://gitee.com/guodongchen) |
| 10  | I4BX9E | 【需求】HiStreamer播放引擎框架需求               | 轻量系统 | SIG_GraphicsandMedia         | [@guodongchen](https://gitee.com/guodongchen) |
| 11  | I3XGNM | 烧写模式支持                           | 轻量系统 | SIG_BscSoftSrv           | [@handyohos](https://gitee.com/handyohos) |
| 12  | I4FL3F | 3516开发板多模输入触屏和Back适配验证                          | 标准系统 | SIG_HardwareMgr           | [@hhh2](https://gitee.com/hhh2) |
| 13  | I4DK89 | 【需求】HiStreamer插件框架需求                              | 轻量系统 | SIG_GraphicsandMedia | [@guodongchen](https://gitee.com/guodongchen) |
| 14  | I4DK8D | 【需求】HiStreamer性能和DFX需求                             | 轻量系统 | SIG_GraphicsandMedia | [@guodongchen](https://gitee.com/guodongchen) |
| 15  | I3ND6Y | 【性能】OS内核&驱动启动优化                           | 轻量系统 | SIG_Kernel           | [@kkup180](https://gitee.com/kkup180)             |
| 16  | I3NTCT | 【启动恢复子系统】Linux版本init支持热插拔                    | 轻量系统 | SIG_BscSoftSrv       | [@handyohos](https://gitee.com/handyohos)         |
| 17  | I3O2G8 | 【应用程序框架】轻量级应用实现entity标签                     | 轻量系统 | SIG_AppFramework     | [@autumn](https://gitee.com/autumn330)|
| 18  | I3NTDP | 【电话服务】支持轻量级mbed TLS协议栈                      | 轻量系统 | SIG_SoftBus          | [@rain_myf](https://gitee.com/rain_myf) |
|19   | I4M8FW|【新增特性】支持应用账号基础信息管理|标准系统|SIG_BasicSoftwareService|[@verystone](https://gitee.com/verystone)|
|20   | I4MBQE|新增特性：时间时区管理|标准系统|SIG_BasicSoftwareService|[@autumn330](https://gitee.com/autumn330)|
|21   | I4MBQF|【增强特性】【事件通知子系统】线程间EventHandler支持HiTrace能力|标准系统|SIG_BasicSoftwareService|[@autumn330](https://gitee.com/autumn330)|
|22   | I4MBQG|【资料】hisysevent部件资料需求|标准系统|SIG_BasicSoftwareService|[@yaomanhai](https://gitee.com/yaomanhai)|
|23   | I4MBQH|【新增特性】支持鸿蒙HiSysEvent部件提供查询接口|标准系统|SIG_BasicSoftwareService|[@yaomanhai](https://gitee.com/yaomanhai)|
|24   | I4MBQI|【新增特性】提供工具查询或者订阅系统事件|标准系统|SIG_BasicSoftwareService|[@yaomanhai](https://gitee.com/yaomanhai)|
|25   | I4MBQJ|【新增特性】支持鸿蒙HiSysEvent部件提供订阅接口|标准系统|SIG_BasicSoftwareService|[@yaomanhai](https://gitee.com/yaomanhai)|
|26   | I4MBQK|【资料】hiappevent部件资料需求|标准系统|SIG_BasicSoftwareService|[@yaomanhai](https://gitee.com/yaomanhai)|
|27   | I4MBQL|【新增特性】支持鸿蒙hiappevent部件的C接口|标准系统|SIG_BasicSoftwareService|[@yaomanhai](https://gitee.com/yaomanhai)|
|28   | I4MBQM|【新增规格】L0-L2支持统一的部件配置|标准系统|SIG_CompileRuntime|[@wangxing-hw](https://gitee.com/wangxing-hw)|
|29   | I4MBQN|【新增规格】L0-L2支持使用统一的编译命令进行编译|标准系统|SIG_CompileRuntime|[@wangxing-hw](https://gitee.com/wangxing-hw)|
|30   | I4MBQO|【新增规格】L0-L2支持使用统一的编译流程|标准系统|SIG_CompileRuntime|[@wangxing-hw](https://gitee.com/wangxing-hw)|
|31   | I4MBQP|【新增规格】L0-L2支持使用统一的gn模板|标准系统|SIG_CompileRuntime|[@wangxing-hw](https://gitee.com/wangxing-hw)|
|32   | I4MBQQ|【新增规格】L0-L2支持统一的产品配置|标准系统|SIG_CompileRuntime|[@wangxing-hw](https://gitee.com/wangxing-hw)|
|33   | I4MBQR|【资料】制定gn编码规范和最佳实践指导|标准系统|SIG_CompileRuntime|[@wangxing-hw](https://gitee.com/wangxing-hw)|
|34   | I4MBQS|【新增特性】支持应用账号信息查询|标准系统|SIG_BasicSoftwareService|[@verystone](https://gitee.com/verystone)|
|35   | I4MBQT|【新增特性】支持应用账号功能设置与内容修改|标准系统|SIG_BasicSoftwareService|[@verystone](https://gitee.com/verystone)|
|36   | I4MBQU|【新增特性】支持应用账号订阅及取消订阅|标准系统|SIG_BasicSoftwareService|[@verystone](https://gitee.com/verystone)|
|37   | I4MBQV|【DFX】应用账号基础信息约束|标准系统|SIG_BasicSoftwareService|[@verystone](https://gitee.com/verystone)|
|38   | I4MBQW|【新增特性】支持应用账号的新增和删除|标准系统|SIG_BasicSoftwareService|[@verystone](https://gitee.com/verystone)|
|39   | I4MBQX|【增强特性】定制框架基础能力|标准系统|SIG_ApplicationFramework|[@zhengbin5](https://gitee.com/zhengbin5)|
|40   | I4MBQY|【新增特性】资源编译工具支持增量编译|标准系统|SIG_ApplicationFramework|[@mengjingzhimo](https://gitee.com/mengjingzhimo)|
|41   | I4MBQZ|【增强特性】时间段格式化|标准系统|SIG_ApplicationFramework|[@mengjingzhimo](https://gitee.com/mengjingzhimo)|
|42   | I4MBR0|【增强特性】区域表示和属性|标准系统|SIG_ApplicationFramework|[@mengjingzhimo](https://gitee.com/mengjingzhimo)|
|43   | I4MBR1|【增强特性】单复数支持|标准系统|SIG_ApplicationFramework|[@mengjingzhimo](https://gitee.com/mengjingzhimo)|
|44   | I4MBR2|【增强特性】字符串排序|标准系统|SIG_ApplicationFramework|[@mengjingzhimo](https://gitee.com/mengjingzhimo)|
|45   | I4MBR3|【增强特性】电话号码处理|标准系统|SIG_ApplicationFramework|[@mengjingzhimo](https://gitee.com/mengjingzhimo)|
|46   | I4MBR4|【新增特性】字母表检索|标准系统|SIG_ApplicationFramework|[@mengjingzhimo](https://gitee.com/mengjingzhimo)|
|47   | I4MBR5|【新增特性】度量衡体系和格式化|标准系统|SIG_ApplicationFramework|[@mengjingzhimo](https://gitee.com/mengjingzhimo)|
|48   | I4MBR7|【新增特性】日历&本地历法|标准系统|SIG_ApplicationFramework|[@mengjingzhimo](https://gitee.com/mengjingzhimo)|
|49   | I4MBR8|【增强特性】unicode字符属性|标准系统|SIG_ApplicationFramework|[@mengjingzhimo](https://gitee.com/mengjingzhimo)|
|50   | I4MBR9|【增强特性】断词断行|标准系统|SIG_ApplicationFramework|[@mengjingzhimo](https://gitee.com/mengjingzhimo)|
|51   | I4MBRA|【新增特性】系统资源管理|标准系统|SIG_ApplicationFramework|[@jameshw](https://gitee.com/jameshw)|
|52   | I4MBRB|【新增特性】rawfile资源管理|标准系统|SIG_ApplicationFramework|[@mengjingzhimo](https://gitee.com/mengjingzhimo)|
|53   | I4MBRC|【hiperf部件】采样数据展示|标准系统|SIG_R&DToolChain|[@wangzaishang](https://gitee.com/wangzaishang)|
|54   | I4MBRD|【hiperf部件】性能数据采样记录|标准系统|SIG_R&DToolChain|[@wangzaishang](https://gitee.com/wangzaishang)|
|55   | I4MBRE|【hiperf部件】性能数据计数统计|标准系统|SIG_R&DToolChain|[@wangzaishang](https://gitee.com/wangzaishang)|
|56   | I4MBRF|【新增特性】支持STA基础特性的JS API接口|标准系统|SIG_SoftBus|[@cheng_guohong](https://gitee.com/cheng_guohong)|
|57   | I4MBRG|【新增特性】支持STA基础特性JS API资料文档|标准系统|SIG_SoftBus|[@cheng_guohong](https://gitee.com/cheng_guohong)|
|58   | I4MBRH|【新增特性】支持STA基础特性|标准系统|SIG_SoftBus|[@cheng_guohong](https://gitee.com/cheng_guohong)|
|59   | I4MBRI|【新增特性】支持SoftAP基础特性|标准系统|SIG_SoftBus|[@cheng_guohong](https://gitee.com/cheng_guohong)|
|60   | I4MBRJ|【新增特性】提供WiFi模块的维测能力|标准系统|SIG_SoftBus|[@cheng_guohong](https://gitee.com/cheng_guohong)|
|61   | I4MBRK|【新增特性】USB服务JS接口实现|标准系统|SIG_DistributedHardwareManagement|[@hhh2](https://gitee.com/hhh2)|
|62   | I4MBRP|【泛Sensor】地磁场偏角和倾角|标准系统|SIG_DistributedHardwareManagement|[@hhh2](https://gitee.com/hhh2)|
|63   | I4MBRQ|【泛Sensor】地磁场偏角和倾角|标准系统|SIG_DistributedHardwareManagement|[@hhh2](https://gitee.com/hhh2)|
|64   | I4MBRR|【资料】distributed_kv_store分布式数据库支持按谓词查询条件进行数据库记录的跨设备同步和订阅|标准系统|SIG_DataManagement|[@widecode](https://gitee.com/widecode)|
|65   | I4MBRS|【distributed_kv_store】分布式数据库支持按谓词查询条件进行数据库记录的跨设备同步和订阅|标准系统|SIG_DataManagement|[@widecode](https://gitee.com/widecode)|
|66   | I4MBRT|【资料】RDB提供数据库级安全加密|标准系统|SIG_DataManagement|[@mangtsang](https://gitee.com/mangtsang)|
|67   | I4MBRU|【RDB】支持数据库加密|标准系统|SIG_DataManagement|[@mangtsang](https://gitee.com/mangtsang)|
|68   | I4MBRV|【samgr】系统服务状态监控|标准系统|SIG_BasicSoftwareService|[@lijiarun](https://gitee.com/lijiarun)|
|69   | I4MBRW|【samgr】服务进程内的SA名单管控|标准系统|SIG_BasicSoftwareService|[@lijiarun](https://gitee.com/lijiarun)|
|70   | I4MBRX|【samgr】加载指定系统服务|标准系统|SIG_BasicSoftwareService|[@lijiarun](https://gitee.com/lijiarun)|
|71   | I4MBRY|【samgr】系统服务进程管理|标准系统|SIG_BasicSoftwareService|[@lijiarun](https://gitee.com/lijiarun)|
|72   | I4MBRZ|【samgr】全量服务列表初始化|标准系统|SIG_BasicSoftwareService|[@lijiarun](https://gitee.com/lijiarun)|
|73   | I4MBS0|【新增特性】【组网】软总线支持网络切换组网|标准系统|SIG_SoftBus|[@bigpumpkin](https://gitee.com/bigpumpkin)|
|74   | I4MBS1|【新增特性】【传输】软总线提供传输ExtAPI接口|标准系统|SIG_SoftBus|[@bigpumpkin](https://gitee.com/bigpumpkin)|
|75   | I4MBS2|【新增特性】支持statfs API能力需求|标准系统|SIG_DataManagement|[@zhangzhiwi](https://gitee.com/zhangzhiwi)|
|76   | I4MBS3|【新增特性】支持长时任务通知|标准系统|SIG_BasicSoftwareService|[@autumn330](https://gitee.com/autumn330)|
|77   | I4MBS4|【新增特性】通知系统API支持权限管理|标准系统|SIG_BasicSoftwareService|[@autumn330](https://gitee.com/autumn330)|
|78   | I4MBS5|【新增特性】支持设置通知振动|标准系统|SIG_BasicSoftwareService|[@autumn330](https://gitee.com/autumn330)|
|79   | I4MBS6|【新增特性】支持通知声音设置和查询|标准系统|SIG_BasicSoftwareService|[@autumn330](https://gitee.com/autumn330)|
|80   | I4MBS7|【新增特性】通知支持免打扰|标准系统|SIG_BasicSoftwareService|[@autumn330](https://gitee.com/autumn330)|
|81   | I4MBS8|【新增特性】支持会话类通知|标准系统|SIG_BasicSoftwareService|[@autumn330](https://gitee.com/autumn330)|
|82   | I4MBS9|【新增特性】EventHandler支持hitrace|标准系统|SIG_BasicSoftwareService|[@autumn330](https://gitee.com/autumn330)|
|83   | I4MBSA|【新增特性】支持系统公共事件管理特性|标准系统|SIG_BasicSoftwareService|[@autumn330](https://gitee.com/autumn330)|
|84   | I4MBSB|【新增特性】支持eventEmitter|标准系统|SIG_BasicSoftwareService|[@autumn330](https://gitee.com/autumn330)|
|85   | I4MBSC|【增强特性】支持Module和Ability的srcPath字段|标准系统|SIG_ApplicationFramework|[@gwang2008](https://gitee.com/gwang2008)|
|86   | I4MBSD|【新增特性】支持多hap包安装|标准系统|SIG_ApplicationFramework|[@gwang2008](https://gitee.com/gwang2008)|
|87   | I4MBSE|【新增特性】提供桌面包管理客户端|标准系统|SIG_ApplicationFramework|[@gwang2008](https://gitee.com/gwang2008)|
|88   | I4MBSF|【新增特性】提供清除缓存数据js api|标准系统|SIG_ApplicationFramework|[@gwang2008](https://gitee.com/gwang2008)|
|89   | I4MBSG|【增强特性】安装包信息查询|标准系统|SIG_ApplicationFramework|[@gwang2008](https://gitee.com/gwang2008)|
|90   | I4MBSH|【新增特性】多hap安装时的签名校验|标准系统|SIG_ApplicationFramework|[@gwang2008](https://gitee.com/gwang2008)|
|91   | I4MBSI|【新增特性】ZIDL工具自动生成Extension C++服务端及客户端接口文件|标准系统|SIG_ApplicationFramework|[@gwang2008](https://gitee.com/gwang2008)|
|92   | I4MBT4|【增强特性】支持常驻进程开机启动|标准系统|SIG_ApplicationFramework|[@gwang2008](https://gitee.com/gwang2008)|
|93   | I4MBTN|【新增特性】支持CMA复用特性|标准系统|SIG_Kernel|[@liuyoufang](https://gitee.com/liuyoufang)|
|94   | I4MBTO|【新增特性】支持内存占用分类查询|标准系统|SIG_CompileRuntime|[@huanghuijin](https://gitee.com/huanghuijin)|
|95   | I4MBTP|【增强特性】传感器驱动模型能力增强|标准系统|SIG_DriverFramework|[@zianed](https://gitee.com/zianed)|
|96   | I4MBTQ|【增强特性】传感器器件驱动能力增强|标准系统|SIG_DriverFramework|[@zianed](https://gitee.com/zianed)|
|97   | I4MBTR|【新增特性】Display-Layer HDI接口针对L2的参考实现；  Display-Gralloc HDI接口针对L2的参考实现；  Display-Device  HDI接口针对L2的参考实现；|标准系统|SIG_DriverFramework|[@zianed](https://gitee.com/zianed)|
|98   | I4MBTS|【增强特性】 HDF-Input设备能力丰富|标准系统|SIG_DriverFramework|[@zianed](https://gitee.com/zianed)|
|99   | I4MBTT|【新增特性】支持Linux/Liteos-a内核系统级休眠唤醒|标准系统|SIG_DriverFramework|[@zianed](https://gitee.com/zianed)|
|100 | I4MBTU|【新增特性】支持同步/异步电源管理调用|标准系统|SIG_DriverFramework|[@zianed](https://gitee.com/zianed)|
|101 | I4MBTV|【新增特性】提供hcs宏式解析接口|标准系统|SIG_DriverFramework|[@zianed](https://gitee.com/zianed)|
|102 | I4MBU1|【设置公共数据存储】Settings数据管理API|标准系统|SIG_SystemApplication|[@lv-zhongwei](https://gitee.com/lv-zhongwei)|
|103 | I4MBU3|【设置】系统-时间设置|标准系统|SIG_SystemApplication|[@lv-zhongwei](https://gitee.com/lv-zhongwei)|
|104 | I4MBU5|【设置】声音管理|标准系统|SIG_SystemApplication|[@lv-zhongwei](https://gitee.com/lv-zhongwei)|
|105 | I4MBU6|【设置】基础能力-数据管理|标准系统|SIG_SystemApplication|[@lv-zhongwei](https://gitee.com/lv-zhongwei)|
|106 | I4MBU7|【设置】基础能力-默认值管理|标准系统|SIG_SystemApplication|[@lv-zhongwei](https://gitee.com/lv-zhongwei)|
|107 | I4MBU8|【设置】基础能力-多设备形态差异化构建|标准系统|SIG_SystemApplication|[@lv-zhongwei](https://gitee.com/lv-zhongwei)|
|108 | I4MBU9|【SystemUI】【通知】通知组件化|标准系统|SIG_SystemApplication|[@lv-zhongwei](https://gitee.com/lv-zhongwei)|
|109 | I4MBUB|【新增特性】提供windows/MacOS/Linux的前端编译工具链|标准系统|SIG_CompileRuntime|[@godmiaozi](https://gitee.com/godmiaozi)|
|110 | I4MBUC|【新增特性】Openharmony jsapi替换为ark版本|标准系统|SIG_CompileRuntime|[@wuzhefengh](https://gitee.com/wuzhefengh)|
|111 | I4MBUD|【新增规格】内存管理分配回收功能/Concurrent mark算法以及Concurrent Sweep实现|标准系统|SIG_CompileRuntime|[@wuzhefengh](https://gitee.com/wuzhefengh)|
|112 | I4MBUE|【新增特性】OpenharmonyOS上默认内置应用替换为ark版本|标准系统|SIG_CompileRuntime|[@wuzhefengh](https://gitee.com/wuzhefengh)|
|113 | I4MBUF|【增强特性】Inline Cache功能|标准系统|SIG_CompileRuntime|[@wuzhefengh](https://gitee.com/wuzhefengh)|
|114 | I4MBUG|【增强特性】支持解释器call指令优化|标准系统|SIG_CompileRuntime|[@wuzhefengh](https://gitee.com/wuzhefengh)|
|115 | I4MBUH|【新增规格】CPU Profiler运行时实现|标准系统|SIG_CompileRuntime|[@wuzhefengh](https://gitee.com/wuzhefengh)|
|116 | I4MBUI|【新增规格】内存管理分配回收功能/ 支持Old Space的Partial GC|标准系统|SIG_CompileRuntime|[@wuzhefengh](https://gitee.com/wuzhefengh)|
|117 | I4MBUJ|【新增特性】OpenHarmony应用工程编译构建能力  【描述】  1、在正常构建场景下，能够将开发者程序代码编译成方舟字节码  2、在编译出现错误时，输出准确编译错误提示信息|标准系统|SIG_CompileRuntime|[@godmiaozi](https://gitee.com/godmiaozi)|
|118 | I4MBUK|【新增规格】JS运行时支持预览器|标准系统|SIG_CompileRuntime|[@wuzhefengh](https://gitee.com/wuzhefengh)|
|119 | I4MBUL|【新增规格】方舟支持调试并且支持attach模式|标准系统|SIG_CompileRuntime|[@wuzhefengh](https://gitee.com/wuzhefengh)|
|120 | I4MBUM|【新增规格】提供libc，c++，clang基础测试框架|标准系统|SIG_CompileRuntime|[@wuzhefengh](https://gitee.com/wuzhefengh)|
|121 | I4MBUN|【新增规格】支持utils特性  /提供process接口规格|标准系统|SIG_CompileRuntime|[@wuzhefengh](https://gitee.com/wuzhefengh)|
|122 | I4MBUO|【新增规格】支持utils特性  /提供提供Scope接口规格|标准系统|SIG_CompileRuntime|[@wuzhefengh](https://gitee.com/wuzhefengh)|
|123 | I4MBUP|【新增规格】支持utils特性  /提供提供Base64接口规格|标准系统|SIG_CompileRuntime|[@wuzhefengh](https://gitee.com/wuzhefengh)|
|124 | I4MBUQ|【新增规格】支持utils特性  /提供提供RationalNumber接口规格|标准系统|SIG_CompileRuntime|[@wuzhefengh](https://gitee.com/wuzhefengh)|
|125 | I4MBUR|【新增规格】支持语言增强特性/提供JS Typeof 接口规格|标准系统|SIG_CompileRuntime|[@wuzhefengh](https://gitee.com/wuzhefengh)|
|126 | I4MBUS|【新增规格】支持URI特性 /提供 URI解析接口规格|标准系统|SIG_CompileRuntime|[@wuzhefengh](https://gitee.com/wuzhefengh)|
|127 | I4MBUT|【新增规格】支持utils特性提供LRUBuffer接口规格|标准系统|SIG_CompileRuntime|[@wuzhefengh](https://gitee.com/wuzhefengh)|
|128 | I4MBUU|【新增规格】支持XML特性/提供XmlPullParser 接口规格|标准系统|SIG_CompileRuntime|[@wuzhefengh](https://gitee.com/wuzhefengh)|
|129 | I4MBUV|【新增规格】支持XML特性/提供xmlSerializer 接口规格|标准系统|SIG_CompileRuntime|[@wuzhefengh](https://gitee.com/wuzhefengh)|
|130 | I4MBUW|【新增规格】支持XML特性/提供xml2JSObject 接口规格|标准系统|SIG_CompileRuntime|[@wuzhefengh](https://gitee.com/wuzhefengh)|
|131 | I4MBUX|【新增规格】资源管理特性对接全球化规格|标准系统|SIG_ApplicationFramework|[@davidwulanxi](https://gitee.com/davidwulanxi)|
|132 | I4MBUY|【新增规格】事件中增加Target获取尺寸|标准系统|SIG_ApplicationFramework|[@davidwulanxi](https://gitee.com/davidwulanxi)|
|133 | I4MBUZ|【新增规格】Swiper组件支持设置缓存cache|标准系统|SIG_ApplicationFramework|[@davidwulanxi](https://gitee.com/davidwulanxi)|
|134 | I4MBV1|【新增规格】Image组件支持同步、异步渲染设置|标准系统|SIG_ApplicationFramework|[@davidwulanxi](https://gitee.com/davidwulanxi)|
|135 | I4MBV3|【新增规格】样式设置特性增加组件多态样式设置规格|标准系统|SIG_ApplicationFramework|[@davidwulanxi](https://gitee.com/davidwulanxi)|
|136 | I4MBV5|【新增规格】字母索引条组件增加提示菜单内容扩展规格|标准系统|SIG_ApplicationFramework|[@davidwulanxi](https://gitee.com/davidwulanxi)|
|137 | I4MBV6|【新增规格】组件自定义特性增加自定义容器组件规格|标准系统|SIG_ApplicationFramework|[@davidwulanxi](https://gitee.com/davidwulanxi)|
|138 | I4MBV7|【新增规格】滚动条样式自定义能力|标准系统|SIG_ApplicationFramework|[@davidwulanxi](https://gitee.com/davidwulanxi)|
|139 | I4MBV8|【新增规格】Swiper组件新增切换禁用规格|标准系统|SIG_ApplicationFramework|[@davidwulanxi](https://gitee.com/davidwulanxi)|
|140 | I4MBV9|【新增规格】Tabs组件新增TabBar内容自定义规格|标准系统|SIG_ApplicationFramework|[@davidwulanxi](https://gitee.com/davidwulanxi)|
|141 | I4MBVA|【新增规格】Navigation组件新增标题栏设置规格|标准系统|SIG_ApplicationFramework|[@davidwulanxi](https://gitee.com/davidwulanxi)|
|142 | I4MBVB|【新增规格】工具栏组件增加工具栏显隐控制规格|标准系统|SIG_ApplicationFramework|[@davidwulanxi](https://gitee.com/davidwulanxi)|
|143 | I4MBVC|【新增规格】工具栏组件增加内容自定义能力规格|标准系统|SIG_ApplicationFramework|[@davidwulanxi](https://gitee.com/davidwulanxi)|
|144 | I4MBVD|【新增特性】新增SysCap声明编译特性|标准系统|SIG_ApplicationFramework|[@karl-z](https://gitee.com/karl-z)|
|145 | I4MBVE|【新增特性】新增JS SDK编译特性|标准系统|SIG_ApplicationFramework|[@lihong67](https://gitee.com/lihong67)|
|146 | I4MBVF|【新增特性】新增Config.json编译特性|标准系统|SIG_ApplicationFramework|[@lihong67](https://gitee.com/lihong67)|
|147 | I4MBVG|【新增规格】新增断点调试特性支持单实例调试|标准系统|SIG_ApplicationFramework|[@lihong67](https://gitee.com/lihong67)|
|148 | I4MBVH|【新增规格】新增attach调试特性支持单实例调试|标准系统|SIG_ApplicationFramework|[@lihong67](https://gitee.com/lihong67)|
|149 | I4MBVI|【新增规格】新增声明式范式编译特性支持编译和校验规格|标准系统|SIG_ApplicationFramework|[@lihong67](https://gitee.com/lihong67)|
|150 | I4MBVJ|【新增特性】新增JS模块共享编译特性|标准系统|SIG_ApplicationFramework|[@lihong67](https://gitee.com/lihong67)|
|151 | I4MBVK|【新增特性】新增HAR引用和编译特性|标准系统|SIG_ApplicationFramework|[@lihong67](https://gitee.com/lihong67)|
|152 | I4MBVL|【新增特性】新增NPM引用和编译特性|标准系统|SIG_ApplicationFramework|[@lihong67](https://gitee.com/lihong67)|
|153 | I4MBVM|【资料】ace_engine_standard部件IT2版本资料录入需求|标准系统|SIG_Docs|[@neeen](https://gitee.com/neeen)|
|154 | I4MBVN|【新增特性】纵向显示滑动条组件特性|标准系统|SIG_ApplicationFramework|[@davidwulanxi](https://gitee.com/davidwulanxi)|
|155 | I4MBVO|【新增特性】Popup组件增加内容自定义规格|标准系统|SIG_ApplicationFramework|[@davidwulanxi](https://gitee.com/davidwulanxi)|
|156 | I4MBVP|【新增特性】Canvas绘制能力支持|标准系统|SIG_ApplicationFramework|[@davidwulanxi](https://gitee.com/davidwulanxi)|
|157 | I4MBVQ|【新增规格】Canvas能力增强|标准系统|SIG_ApplicationFramework|[@davidwulanxi](https://gitee.com/davidwulanxi)|
|158 | I4MBVR|【新增特性】触摸响应热区设置|标准系统|SIG_ApplicationFramework|[@davidwulanxi](https://gitee.com/davidwulanxi)|
|159 | I4MBVS|【新增特性】Lottie动画支持|标准系统|SIG_ApplicationFramework|[@davidwulanxi](https://gitee.com/davidwulanxi)|
|160 | I4MBVT|【新增特性】组件尺寸获取特性|标准系统|SIG_ApplicationFramework|[@davidwulanxi](https://gitee.com/davidwulanxi)|
|161 | I4MBVU|【新增特性】Menu组件增加内容自定义规格|标准系统|SIG_ApplicationFramework|[@davidwulanxi](https://gitee.com/davidwulanxi)|
|162 | I4MBVV|【新增特性】Swipe手势特性|标准系统|SIG_ApplicationFramework|[@davidwulanxi](https://gitee.com/davidwulanxi)|
|163 | I4MBVW|【新增特性】UI预览支持Inspector能力|标准系统|SIG_ApplicationFramework|[@lihong67](https://gitee.com/lihong67)|
|164 | I4MBVX|【新增特性】新增非路由文件预览特性|标准系统|SIG_ApplicationFramework|[@lihong67](https://gitee.com/lihong67)|
|165 | I4MBVY|【新增特性】新增NAPI预览特性|标准系统|SIG_ApplicationFramework|[@lihong67](https://gitee.com/lihong67)|
|166 | I4MBVZ|【新增规格】新增声明式范式预览特性支持基础预览规格|标准系统|SIG_ApplicationFramework|[@lihong67](https://gitee.com/lihong67)|
|167 | I4MBW2|【新增规格】新增声明式范式热加载特性支持已有节点修改规格|标准系统|SIG_ApplicationFramework|[@lihong67](https://gitee.com/lihong67)|
|168 | I4MBW3|【新增规格】新增声明式范式热加载特性支持新增节点规格|标准系统|SIG_ApplicationFramework|[@lihong67](https://gitee.com/lihong67)|
|169 | I4MBW4|【新增规格】新增声明式范式热加载特性支持删除节点规格|标准系统|SIG_ApplicationFramework|[@lihong67](https://gitee.com/lihong67)|
|170 | I4MBW5|【新增规格】新增组件预览特性支持页面组件预览规格|标准系统|SIG_ApplicationFramework|[@lihong67](https://gitee.com/lihong67)|
|171 | I4NY1T|【device_profile】订阅profile信息变化|标准系统|SIG_BasicSoftwareService|[@lijiarun](https://gitee.com/lijiarun)|
|172 | I4NY1U|【device_profile】订阅同步通知|标准系统|SIG_BasicSoftwareService|[@lijiarun](https://gitee.com/lijiarun)|
|173 | I4NY1V|【device_profile】CS采集OS特征信息|标准系统|SIG_BasicSoftwareService|[@lijiarun](https://gitee.com/lijiarun)|
|174 | I4NY1W|【device_profile】向业务端提供同步profile能力|标准系统|SIG_BasicSoftwareService|[@lijiarun](https://gitee.com/lijiarun)|
|175 | I4NY1X|【device_profile】提供查询远程设备profile记录功能|标准系统|SIG_BasicSoftwareService|[@lijiarun](https://gitee.com/lijiarun)|
|176 | I4NY1Z|【device_profile】profile上线同步（wifi组网下）|标准系统|SIG_BasicSoftwareService|[@lijiarun](https://gitee.com/lijiarun)|
|177 | I4NY21|【device_profile】提供删除本地profile记录功能|标准系统|SIG_BasicSoftwareService|[@lijiarun](https://gitee.com/lijiarun)|
|178 | I4NY22|【device_profile】提供查询本地profile记录功能|标准系统|SIG_BasicSoftwareService|[@lijiarun](https://gitee.com/lijiarun)|
|179 | I4NY23|【device_profile】提供写入profile记录功能|标准系统|SIG_BasicSoftwareService|[@lijiarun](https://gitee.com/lijiarun)|

## OpenHarmony_release 3.1(Release)版本特性清单：
状态说明：discussion(方案讨论，需求未接受)，Reject(未纳入版本)，developing(开发中)，Testing(测试中)，Accepted(已验收)
| issue                                                        | feture description                                           | platform     | sig                  | owner                                             |
| ------------------------------------------------------------ | :----------------------------------------------------------- | :--------- | :------------------- | :------------------------------------------------ |
| I410YD | 【充放电&Battery服务】 支持关机充电特性                      | 标准系统       | SIG_HardwareMgr          | [@aqxyjay](https://gitee.com/aqxyjay)                 |
| I410Y1 | 【充放电&Battery服务】 电池温度异常关机保护                  | 标准系统       | SIG_HardwareMgr          | [@aqxyjay](https://gitee.com/aqxyjay)                 |
| I4OGD2 | 【资料】跨设备组件调用新增/增强特性资料说明                  | 标准系统       | SIG_BasicSoftwareService | [@cangegegege](https://gitee.com/cangegegege)         |
| I4PDB8 | 【新增特性】提供设备PnP事件监听接口                          | 标准系统       | SIG_HardwareMgr          | [@yuanbogit](https://gitee.com/yuanbogit)             |
| I4PDAV | 【联系人】通话记录 - 基本内容（名字、号码、时间、来电次数等） | 标准系统       | SIG_SystemApplication    | [@lv-zhongwei](https://gitee.com/lv-zhongwei)         |
| I4PDAW | 【联系人】通话记录 - 通话记录列表显示（TAB/列表展示）        | 标准系统       | SIG_SystemApplication    | [@lv-zhongwei](https://gitee.com/lv-zhongwei)         |
| I4PDAX | 【设置】显示管理                                             | 标准系统       | SIG_SystemApplication    | [@lv-zhongwei](https://gitee.com/lv-zhongwei)         |
| I4PDAY | 【SystemUI】【状态栏】提示胶囊                               | 标准系统       | SIG_SystemApplication    | [@lv-zhongwei](https://gitee.com/lv-zhongwei)         |
| I4PCX8 | 【RPC】进程间IPC、设备间RPC支持HiTrace能力                   | 标准系统       | SIG_SoftBus              | [@Xi_Yuhao](https://gitee.com/Xi_Yuhao)               |
| I4PD3K | 进程退出后的回收处理策略配置能力增强                         | 标准系统       | SIG_BscSoftSrv           | [@xionglei16](https://gitee.com/xionglei16)           |
| I4PD3C | 支持SA类进程按需启动                                         | 标准系统       | SIG_BscSoftSrv           | [@xionglei16](https://gitee.com/xionglei16)           |
| I4NZVP | 【distributed_kv_store】提供分布式数据库JS API               | 标准系统       | SIG_DataManagement       | [@widecode](https://gitee.com/widecode)               |
| I4WVMH | 【新增规格】系统的应用权限初始化预置定义    | 标准系统 | SIG_Security | [@jiang-xiaofeng](https://gitee.com/jiang-xiaofeng)       |
| I4WVO9 | 【新增规格】应用权限申请列表查询    | 标准系统 | SIG_Security | [@jiang-xiaofeng](https://gitee.com/jiang-xiaofeng)       |
| I4WVPV | 【新增规格】本地权限校验接口和机制    | 标准系统 | SIG_Security | [@jiang-xiaofeng](https://gitee.com/jiang-xiaofeng)       |
| I4WVR3 | 【新增规格】应用权限的设置接口和机制    | 标准系统 | SIG_Security | [@jiang-xiaofeng](https://gitee.com/jiang-xiaofeng)       |
| I4WVRG | 【新增规格】AT管理服务基本框架    | 标准系统 | SIG_Security | [@jiang-xiaofeng](https://gitee.com/jiang-xiaofeng)       |
| I4WVRR | 【新增规格】Hap应用token查询接口     | 标准系统 | SIG_Security | [@jiang-xiaofeng](https://gitee.com/jiang-xiaofeng)       |
| I4WVS6 | 【新增规格】Hap应用的Token信息删除机制    | 标准系统 | SIG_Security | [@jiang-xiaofeng](https://gitee.com/jiang-xiaofeng)       |
| I4WVSI | 【新增规格】Hap应用的Token创建和更新机制   | 标准系统 | SIG_Security | [@jiang-xiaofeng](https://gitee.com/jiang-xiaofeng)       |
| I4WVTM | 【新增特性】支持SELinux策略文件编译生成conf文件的编译框架    | 标准系统 | SIG_Security | [@jiang-xiaofeng](https://gitee.com/jiang-xiaofeng)       |
| I4WVYE | 【新增特性】支持SELinux conf文件策略生成二进制策略编译的编译框架    | 标准系统 | SIG_Security | [@jiang-xiaofeng](https://gitee.com/jiang-xiaofeng)       |
| I4WTQI | 【新增特性】图案密码组件特性支持                          | 标准系统|SIG_ArkUI|[@qieqiewl](https://gitee.com/qieqiewl) |
| I4WTQI | 【新增规格】FormComponent组件支持直接读取config文件获取配置信息                         | 标准系统|SIG_ArkUI|[@qieqiewl](https://gitee.com/qieqiewl) |
| I4WTQI | 【新增规格】输入组件支持设置光标位置                          | 标准系统|SIG_ArkUI|[@qieqiewl](https://gitee.com/qieqiewl) |
| I4WTQI | 【新增规格】拖拽能力增加鼠标拖拽规格                          | 标准系统|SIG_ArkUI|[@qieqiewl](https://gitee.com/qieqiewl) |
| I4WTQL | 【新增规格】支持系统应用弹窗功能                          | 标准系统|SIG_ArkUI|[@qieqiewl](https://gitee.com/qieqiewl) |
| I4WWTB | 【泛sensor】支持通用的算法接口 | 标准系统 | SIG_DistributedHardwareManagement | 标准系统 | SIG_DistributedHardwareManagement | [@hhh2](https://gitee.com/hhh2) |
| I4WWT6 | 【多模】触摸板输入事件注入功能 | 标准系统 | SIG_DistributedHardwareManagement | [@hhh2](https://gitee.com/hhh2) |
| I4WWSN | 【多模】订阅单系统按键输入事件 | 标准系统 | SIG_DistributedHardwareManagement | [@hhh2](https://gitee.com/hhh2) |
| I4RKSM | 【backstore部件】提供Buffer Queue机制 | 标准系统 | SIG-Graphics | [@lz-230](https://gitee.com/lz-230) |
| I4R9PC | 【backstore部件】surface管理 | 标准系统 | SIG-Graphics | [@lz-230](https://gitee.com/lz-230) |
| I4R9PD | 【backstore部件】平台窗口管理 | 标准系统 | SIG-Graphics | [@lz-230](https://gitee.com/lz-230) |
| I4R9P4 | 【window_manager】窗口能力重构 增强特性：提供应用窗口创建管理能力 | 标准系统 | SIG-Graphics | [@lz-230](https://gitee.com/lz-230) |
| I4R301 | 【window_manager】【新增特性】提供接口指导输入事件分发 | 标准系统 | SIG-Graphics | [@lz-230](https://gitee.com/lz-230) |
| I4QGKM | 【部件化专项】battery_manage部件标准化 | 标准系统       | SIG_HardwareMgr          | [@aqxyjay](https://gitee.com/aqxyjay)                 |
| I412F4 | 【省电模式】 支持省电模式                                    | 标准系统       | SIG_HardwareMgr          | [@aqxyjay](https://gitee.com/aqxyjay)                 |
| I4GYBV | 【新增特性】提供温升监控接口                                 | 标准系统       | SIG_HardwareMgr          | [@aqxyjay](https://gitee.com/aqxyjay)                 |
| I4P7FC | [标准系统]提供NDK所需的musl版本的libc基础库以及相应头文件 | 标准系统       | SIG_CompileRuntime       | [@huanghuijin](https://gitee.com/huanghuijin)         |
| I4P7F9 | [标准系统]提供NDK所需的libc++库以及相应头文件    | 标准系统       | SIG_CompileRuntime       | [@huanghuijin](https://gitee.com/huanghuijin)         |
| I4OGCN | 【增强特性】【DMS】根据指定设备发起迁移能力，接收迁移结果    | 标准系统       | SIG_BasicSoftwareService | [@cangegegege](https://gitee.com/cangegegege)         |
| I4OGCM | 【新增特性】【任务管理】提供获取实时任务接口  | 标准系统       | SIG_BasicSoftwareService | [@cangegegege](https://gitee.com/cangegegege)         |
| I4PBOK | 【新增特性】通知支持多用户                                   | 标准系统 | SIG_ApplicationFramework | [@xzz_0810](https://gitee.com/xzz_0810)               |
| I4PCM4 | 【新增特性】上下文提供应用/Hap包/组件信息查询能力            | 标准系统   | SIG_ApplicationFramework | [@silent-dye](https://gitee.com/silent-dye)           |
| I4PCM8 | 【新增特性】应用启动/组件切换流程trace                       | 标准系统   | SIG_ApplicationFramework | [@silent-dye](https://gitee.com/silent-dye)           |
| I4PCNZ | 【新增特性】服务组件泄漏检测                                 | 标准系统   | SIG_ApplicationFramework | [@xuezhongzhu](https://gitee.com/xuezhongzhu)         |
| I4PCPP | 【新增特性】上下文适配多用户                                 | 标准系统   | SIG_ApplicationFramework | [@xuezhongzhu](https://gitee.com/xuezhongzhu)         |
| I4PCPR | 【新增特性】非并发模式下，禁止非当前用户的应用通过其他方式自启 | 标准系统   | SIG_ApplicationFramework | [@xuezhongzhu](https://gitee.com/xuezhongzhu)         |
| I4PCPV | 【新增特性】提供指定用户启动组件的系统接口                   | 标准系统   | SIG_ApplicationFramework | [@xuezhongzhu](https://gitee.com/xuezhongzhu)         |
| I4PCQ1 | 【新增特性】提供指定用户管理应用的系统接口                   | 标准系统   | SIG_ApplicationFramework | [@xuezhongzhu](https://gitee.com/xuezhongzhu)         |
| I4PCQJ | 【新增特性】对外接口适配多用户                               | 标准系统   | SIG_ApplicationFramework | [@xuezhongzhu0810](https://gitee.com/xuezhongzhu0810) |
| I4PCQP | 【新增特性】支持singleuser的运行模式                         | 标准系统   | SIG_ApplicationFramework | [@xuezhongzhu0810](https://gitee.com/xuezhongzhu0810) |
| I4PCQU | 【新增特性】启动初始化默认用户                               | 标准系统   | SIG_ApplicationFramework | [@xuezhongzhu0810](https://gitee.com/xuezhongzhu0810) |
| I4PCQW | 【新增特性】启动用户                                         | 标准系统   | SIG_ApplicationFramework | [@xuezhongzhu0810](https://gitee.com/xuezhongzhu0810) |
| I4PCQY | 【新增特性】切换用户                                         | 标准系统   | SIG_ApplicationFramework | [@xuezhongzhu0810](https://gitee.com/xuezhongzhu0810) |
| I4PCR2 | 【新增特性】停止用户                                         | 标准系统   | SIG_ApplicationFramework | [@xuezhongzhu0810](https://gitee.com/xuezhongzhu0810) |
| I4PBP7 |【新增特性】支持应用发送模板通知（调试能力）|标准系统|SIG_ApplicationFramework|[@xzz_0810](https://gitee.com/xzz_0810)|
| I4PBPE |【新增特性】支持进度条通知|标准系统|SIG_ApplicationFramework|[@xzz_0810](https://gitee.com/xzz_0810)|
| I4PCGY |【增强特性】新增卡片开发基类|标准系统|SIG_ApplicationFramework|[@lsq1474521181](https://gitee.com/lsq1474521181)|
| I4PCH9 |【增强特性】通过配置文件配置服务卡片|标准系统|SIG_ApplicationFramework|[@lsq1474521181](https://gitee.com/lsq1474521181)|
| I4PCLL |【新增特性】JS提供的应用级别上下文|标准系统|SIG_ApplicationFramework|[@silent-dye](https://gitee.com/silent-dye)|
| I4PCLN |【新增特性】Abilty的状态恢复|标准系统|SIG_ApplicationFramework|[@silent-dye](https://gitee.com/silent-dye)|
| I4PCM6 |【新增特性】提供应用或组件状态监听/查询能力|标准系统|SIG_ApplicationFramework|[@silent-dye](https://gitee.com/silent-dye)|
| I4PCP1 |【新增特性】应用运行信息查询|标准系统|SIG_ApplicationFramework|[@xuezhongzhu](https://gitee.com/xuezhongzhu)|
| I4PCPG |【增强特性】支持系统环境变化通知|标准系统|SIG_ApplicationFramework|[@xuezhongzhu](https://gitee.com/xuezhongzhu)|
| I4PCR8 |【增强特性】支持常驻进程开机启动|标准系统|SIG_ApplicationFramework|[@xuezhongzhu0810](https://gitee.com/xuezhongzhu0810)|
| I4PCSB |【新增特性】强制停止进程|标准系统|SIG_ApplicationFramework|[@xuezhongzhu0810](https://gitee.com/xuezhongzhu0810)|
| I4PCV4 |【新增特性】支持任务切换|标准系统|SIG_ApplicationFramework|[@sheilei](https://gitee.com/sheilei)|
| I4PCV9 |【新增特性】多任务管理|标准系统|SIG_ApplicationFramework|[@sheilei](https://gitee.com/sheilei)|
| I4PCVA |【新增特性】支持任务锁|标准系统|SIG_ApplicationFramework|[@sheilei](https://gitee.com/sheilei)|
| I4PCVF |【新增特性】支持任务清除|标准系统|SIG_ApplicationFramework|[@sheilei](https://gitee.com/sheilei)|
| I4PCVZ |【新增特性】支持指定displayId启动Ability|标准系统|SIG_ApplicationFramework|[@sheilei](https://gitee.com/sheilei)|
| I4PCW3 |【增强特性】pendingwant机制支持跨设备启动通用组件|标准系统|SIG_ApplicationFramework|[@sheilei](https://gitee.com/sheilei)|
| I4PKYL | 【新增特性】支持查询指定用户下的应用信息                     | 标准系统   | SIG_ApplicationFramework | [@shuaytao](https://gitee.com/shuaytao)               |
| I4PKYM | 【新增特性】支持多用户创建                                   | 标准系统   | SIG_ApplicationFramework | [@shuaytao](https://gitee.com/shuaytao)               |
| I4PKYN | 【新增特性】支持多用户删除                                   | 标准系统   | SIG_ApplicationFramework | [@shuaytao](https://gitee.com/shuaytao)               |
| I4PKYO | 【新增特性】支持安装应用到指定用户                           | 标准系统   | SIG_ApplicationFramework | [@shuaytao](https://gitee.com/shuaytao)               |
| I4PKYP | 【新增特性】支持卸载指定用户下的应用                         | 标准系统   | SIG_ApplicationFramework | [@shuaytao](https://gitee.com/shuaytao)               |
| I4PKY8 | 【新增特性】installd 提供应用空间统计、cache统计             | 标准系统   | SIG_ApplicationFramework | [@shuaytao](https://gitee.com/shuaytao)               |
| I4PC12 | 支持基本文件异步操作API需求                                  | 标准系统       | SIG_Kernel               | [@panqinxu](https://gitee.com/panqinxu)               |
| I4PXMP | [编译构建子系统]【增强特性】统一编译入口，轻量级和标准系统使用hb可编译 | 标准系统 | SIG_CompileRuntime | [@weichaox](https://gitee.com/weichaox)       |
| I4PXNS | [编译构建子系统]【新增特性】提供NDK的编译模板               | 标准系统 | SIG_CompileRuntime | [@weichaox](https://gitee.com/weichaox)       |
| I4PXNZ | [编译构建子系统]【新增特性】 Native-SDK中提供cmake toolchain文件               | 标准系统 | SIG_CompileRuntime | [@weichaox](https://gitee.com/weichaox)       |
| I4PXRD | [编译构建子系统]【新增特性】归一的部件定义和编译               | 标准系统 | SIG_CompileRuntime | [@weichaox](https://gitee.com/weichaox)       |
| I4JBFF | [账号子系统]【新增特性】支持本地多用户信息查询               | 标准系统 | SIG_BscSoftSrv | [@jiang-xiaofeng](https://gitee.com/jiang-xiaofeng)       |
| I4IU2T | [账号子系统]【新增特性】支持本地多用户订阅及取消订阅          | 标准系统 | SIG_BscSoftSrv | [@jiang-xiaofeng](https://gitee.com/jiang-xiaofeng)       |
| I4IU3B | [账号子系统]【新增特性】支持本地多用户启动、停止、切换动作     | 标准系统 | SIG_BscSoftSrv | [@jiang-xiaofeng](https://gitee.com/jiang-xiaofeng)       |
| I4Q9QZ | [内核子系统]【增强特性】支持南向接口融合    | 标准系统 | SIG_Kernel | [@leonchan5](https://gitee.com/leonchan5)       |
| I4Q8F8 | [标准系统]【新增特性】提供Standard人脸识别框架     | 标准系统 | SIG_Security | [@wangxu](https://gitee.com/wangxu43)       |
| I4Q8F5 | [标准系统]【新增特性】提供Standard人脸录入控件     | 标准系统 | SIG_Security | [@wangxu](https://gitee.com/wangxu43)       |
| I4Q8F3 | [标准系统]【新增特性】提供Standard统一身份认证JS接口     | 标准系统 | SIG_Security | [@wangxu](https://gitee.com/wangxu43)       |
| I4LKQ0 | [内核子系统]【新增特性】cpuset与cpu热插拔解耦     | 标准系统 | SIG_Kernel | [@liuyoufang](https://gitee.com/liuyoufang)       |
| I4HAMI | 【data_share_ability】支持跨应用订阅数据库的变化    | 标准系统 | SIG_DataManagement | [@verystone](https://gitee.com/verystone)      |
| I4Q6AS |【新增特性】FreezeDetector|标准系统|SIG_BasicSoftwareService|[@guochuanqi](https://gitee.com/guochuanqi)|
| I4Q6AV |【新增特性】在Openharmony上hiview插件管理平台代理加载特性|标准系统|SIG_BasicSoftwareService|[@guochuanqi](https://gitee.com/guochuanqi)|
| I4Q6AT |【新增特性】在Openharmony上FaultLogger添加js api|标准系统|SIG_BasicSoftwareService|[@guochuanqi](https://gitee.com/guochuanqi)|
| I4Q6B3 |【新增特性】支持内核日志的读取和落盘|标准系统|SIG_BasicSoftwareService|[@guochuanqi](https://gitee.com/guochuanqi)|
| I4Q6B1 |【增强特性】将hilogd NDK库加入到OpenHarmony NDK包|标准系统|SIG_BasicSoftwareService|[@guochuanqi](https://gitee.com/guochuanqi)|
| I4Q8ZL |【增强特性】日志管理|标准系统|SIG_BasicSoftwareService|[@guochuanqi](https://gitee.com/guochuanqi)|
| I4Q8ZK |【增强特性】进程异常信号处理|标准系统|SIG_BasicSoftwareService|[@guochuanqi](https://gitee.com/guochuanqi)|
| I4Q8ZJ |【增强特性】抓取调用栈工具|标准系统|SIG_BasicSoftwareService|[@guochuanqi](https://gitee.com/guochuanqi)|
| I4Q8ZI |【新增特性】抓取调用栈基础库|标准系统|SIG_BasicSoftwareService|[@guochuanqi](https://gitee.com/guochuanqi)|
| I4QEKH | 【新增特性】提供共享内存相关HDI能力                          | 标准系统 | SIG_Driver         | [@xie0812](https://gitee.com/xie0812)           |
| I4QEKI | 【新增特性】驱动开发工具支持标准系统驱动开发                           | 标准系统 | SIG_Driver         | [@xie0812](https://gitee.com/xie0812)           |
| I4QEKJ |【新增特性】HDI接口适配linux-input驱动                           | 标准系统 | SIG_Driver         | [@xie0812](https://gitee.com/xie0812)           |
| I4QEKM | 【新增特性】提供power HDI接口能力                           | 标准系统 | SIG_Driver         | [@xie0812](https://gitee.com/xie0812)           |
| I4QEKK | 【新增特性】基于HDF驱动框架提供硬件TIMER驱动                          | 标准系统 | SIG_Driver         | [@xie0812](https://gitee.com/xie0812)           |
| I4QEKL | 【新增特性】基于HDF驱动框架构建统一的平台驱动对象模型                           | 标准系统 | SIG_Driver         | [@xie0812](https://gitee.com/xie0812)           |
| I4QEKN | 【新增特性】USB Device功能实现                           | 标准系统 | SIG_Driver         | [@xie0812](https://gitee.com/xie0812)           |
| I4QEKO | 【新增特性】USB Host功能实现                          | 标准系统 | SIG_Driver         | [@xie0812](https://gitee.com/xie0812)           |
| I4QEPQ |【资料】【RDB】支持QuerySql返回结果集，进一步支持更广泛的查询方式|标准系统|SIG_DataManagement|[@mangtsang](https://gitee.com/mangtsang)|
| I4NZP6 |【RDB】增加多表查询能力|标准系统|SIG_DataManagement|[@mangtsang](https://gitee.com/mangtsang)|
| I4FZ6B |【RDB】提供事务能力|标准系统|SIG_DataManagement|[@mangtsang](https://gitee.com/mangtsang)|
| I4HAMI |【data_share_ability】支持跨应用订阅数据库的变化|标准系统|SIG_DataManagement|[@mangtsang](https://gitee.com/mangtsang)|
| I4QC4U |【新增特性】PC预览资源管理特性对接全球化规格|标准系统|SIG_ArkUI|[@qieqiewl](https://gitee.com/qieqiewl)|
| I4QC4S |【新增规格】文本计时器组件支持|标准系统|SIG_ArkUI|[@qieqiewl](https://gitee.com/qieqiewl)|
| I4QC4R |【新增规格】进度条组件能力增强|标准系统|SIG_ArkUI|[@qieqiewl](https://gitee.com/qieqiewl)|
| I4QC4P |【新增规格】文字时钟组件支持|标准系统|SIG_ArkUI|[@qieqiewl](https://gitee.com/qieqiewl)|
| I4QC4N |【新增规格】TextInput组件能力增强|标准系统|SIG_ArkUI|[@qieqiewl](https://gitee.com/qieqiewl)|
| I4QC4O |【新增规格】Select组件支持|标准系统|SIG_ArkUI|[@qieqiewl](https://gitee.com/qieqiewl)|
| I4QC4K |【新增规格】TextArea组件能力增强|标准系统|SIG_ArkUI|[@qieqiewl](https://gitee.com/qieqiewl)|
| I4QGHF | 【部件化专项】power_manage部件标准化 | 标准系统       | SIG_HardwareMgr          | [@aqxyjay](https://gitee.com/aqxyjay)                 |
| I4QKLO |【联系人】联系人列表 - 列表元素显示（姓名、工作单位、头像等）| 标准系统    | SIG_SystemApplication   |[@sunjunxiong](https://gitee.com/sunjunxiong)|
| I4QKLM |【联系人】联系人列表 - 新建/编辑联系人 | 标准系统    | SIG_SystemApplication   |[@sunjunxiong](https://gitee.com/sunjunxiong)|
| I4IEJW |【新增特性】【RPC】RPC支持本设备收发及死亡通知 | 标准系统    | SIG_SoftBus   |[@liubb940516](https://gitee.com/liubb940516)|
| I4IEJE |【新增特性】【RPC】RPC支持统一管理框架 | 标准系统    | SIG_SoftBus   |[@liubb940516](https://gitee.com/liubb940516)|
| I4PXNS |【新增特性】 提供NDK的编译模板  | 标准系统 | SIG_CompileRuntime | [@anguanglin](https://gitee.com/anguanglin)
| I4PW9P |【新增特性】 提供图形配置界面，通过界面操作选择部件列表  | 标准系统 | SIG_CompileRuntime | [@anguanglin](https://gitee.com/anguanglin)
| I4PWA3 |【新增特性】支持利用Kconfig输出生成支持编译产品配置   | 标准系统 | SIG_CompileRuntime | [@anguanglin](https://gitee.com/anguanglin)
| I4PWAB |【新增特性】提供Kconfig的使用指导   | 标准系统 | SIG_CompileRuntime | [@anguanglin](https://gitee.com/anguanglin)
| I4WTQM | 【新增特性】支持三方应用发起分享页面呈现                           | 标准系统|SIG_ArkUI|[@qieqiewl](https://gitee.com/qieqiewl) |
| I4WTPK | 【新增规格】DatePicker组件能力增强                           | 标准系统|SIG_ArkUI|[@qieqiewl](https://gitee.com/qieqiewl) |
| I4WTPO | 【新增规格】TextPicker组件能力增强                           | 标准系统|SIG_ArkUI|[@qieqiewl](https://gitee.com/qieqiewl) |
| I4WTPY | 【新增规格】文本组件支持鼠标拖拽选择文字规格                           | 标准系统|SIG_ArkUI|[@qieqiewl](https://gitee.com/qieqiewl) |
| I4WTR6 | 【新增特性】XComponent组件特性支持声明式范式规格                           | 标准系统|SIG_ArkUI|[@qieqiewl](https://gitee.com/qieqiewl) |
| I4WTR7 | 【新增特性】XComponent组件特性支持获取Surface规格                           | 标准系统|SIG_ArkUI|[@qieqiewl](https://gitee.com/qieqiewl) |
| I4WTRA | 【新增特性】鼠标按键、滚轮事件支持                          | 标准系统|SIG_ArkUI|[@qieqiewl](https://gitee.com/qieqiewl) |
| I4WTQI | 【新增规格】拖拽能力增加鼠标拖拽规格                          | 标准系统|SIG_ArkUI|[@qieqiewl](https://gitee.com/qieqiewl) |
| I4WWRX | 【多模】带键盘类按键状态的鼠标事件 | 标准系统 | SIG_DistributedHardwareManagement | [@hhh2](https://gitee.com/hhh2) |
| I4WWRY | 【多模】鼠标连续滚动事件增加开始和结束 | 标准系统 | SIG_DistributedHardwareManagement | [@hhh2](https://gitee.com/hhh2) |
| I4WWSY | 【多模】触摸板水平轴&垂直轴同时滑动 | 标准系统 | SIG_DistributedHardwareManagement | [@hhh2](https://gitee.com/hhh2) |
| I4WWT3 | 【多模】触摸板输入事件监听功能 | 标准系统 | SIG_DistributedHardwareManagement | [@hhh2](https://gitee.com/hhh2) |
| I4WWT4 | 【多模】触摸板输入事件拦截功能 | 标准系统 | SIG_DistributedHardwareManagement | [@hhh2](https://gitee.com/hhh2) |
| I4WWS4 | 【多模】鼠标图标显示 | 标准系统 | SIG_DistributedHardwareManagement | [@hhh2](https://gitee.com/hhh2) |
| I4GYCD | 【新增特性】支持软件耗电统计                                 | 标准系统       | SIG_HardwareMgr          | [@aqxyjay](https://gitee.com/aqxyjay)                 |
| I4GYCN | 【新增特性】支持硬件耗电统计                                 | 标准系统       | SIG_HardwareMgr          | [@aqxyjay](https://gitee.com/aqxyjay)                 |
| I4GYDQ | 【新增特性】支持耗电详情记录                                 | 标准系统       | SIG_HardwareMgr          | [@aqxyjay](https://gitee.com/aqxyjay)                 |
| I4GY9U | 【新增特性】支持内核温控服务                                 | 标准系统       | SIG_HardwareMgr          | [@aqxyjay](https://gitee.com/aqxyjay)                 |
| I4GYAF | 【新增特性】支持用户层和服务温控服务                         | 标准系统       | SIG_HardwareMgr          | [@aqxyjay](https://gitee.com/aqxyjay)                 |
| I4P7FB | [标准系统]提供NDK中HOS与OHOS两种target，ABI的clang/llvm编译工具链 提供NDK中调试工具链，支持lldb，asan等功能 | 标准系统       | SIG_CompileRuntime       | [@huanghuijin](https://gitee.com/huanghuijin)         |
| I4P7F2 | [标准系统]支持基于lldb的断点调试                 | 标准系统       | SIG_CompileRuntime       | [@huanghuijin](https://gitee.com/huanghuijin)         |
| I4P7F3 | [标准系统]支持C/C++应用调试栈/变量的查看能力     | 标准系统       | SIG_CompileRuntime       | [@huanghuijin](https://gitee.com/huanghuijin)         |
| I4P7EQ | [标准系统]ts类型信息提取                         | 标准系统       | SIG_CompileRuntime       | [@huanghuijin](https://gitee.com/huanghuijin)         |
| I4P7ER | [标准系统]Ts2abc中的类型信息增强                 | 标准系统       | SIG_CompileRuntime       | [@huanghuijin](https://gitee.com/huanghuijin)         |
| I4P7ET | [标准系统]Panda file中的类型系统存储             | 标准系统       | SIG_CompileRuntime       | [@huanghuijin](https://gitee.com/huanghuijin)         |
| I4P7EU | [标准系统]abc支持列号信息                        | 标准系统       | SIG_CompileRuntime       | [@huanghuijin](https://gitee.com/huanghuijin)         |
| I4P7FY | [标准系统]container特性/LightWeightMap接口规格   | 标准系统       | SIG_CompileRuntime       | [@huanghuijin](https://gitee.com/huanghuijin)         |
| I4P7FX | [标准系统]container特性/Deque接口规格            | 标准系统       | SIG_CompileRuntime       | [@huanghuijin](https://gitee.com/huanghuijin)         |
| I4P7FV | [标准系统]container特性/HashSet接口规格          | 标准系统       | SIG_CompileRuntime       | [@huanghuijin](https://gitee.com/huanghuijin)         |
| I4P7FT | [标准系统]container特性/TreeSet接口规格          | 标准系统       | SIG_CompileRuntime       | [@huanghuijin](https://gitee.com/huanghuijin)         |
| I4P7FR | [标准系统]container特性/TreeMap接口规格          | 标准系统       | SIG_CompileRuntime       | [@huanghuijin](https://gitee.com/huanghuijin)         |
| I4P7FP | [标准系统]container特性/Queue接口规格            | 标准系统       | SIG_CompileRuntime       | [@huanghuijin](https://gitee.com/huanghuijin)         |
| I4P7FO | [标准系统]container特性/Vector接口规格           | 标准系统       | SIG_CompileRuntime       | [@huanghuijin](https://gitee.com/huanghuijin)         |
| I4P7FM | [标准系统]container特性/PlainArray接口规格       | 标准系统       | SIG_CompileRuntime       | [@huanghuijin](https://gitee.com/huanghuijin)         |
| I4P7FL | [标准系统]container特性/ArrayList接口规格        | 标准系统       | SIG_CompileRuntime       | [@huanghuijin](https://gitee.com/huanghuijin)         |
| I4P7FK | [标准系统]container特性/LightWeightSet接口规格   | 标准系统       | SIG_CompileRuntime       | [@huanghuijin](https://gitee.com/huanghuijin)         |
| I4P7FH | [标准系统]container特性/HashMap接口规格          | 标准系统       | SIG_CompileRuntime       | [@huanghuijin](https://gitee.com/huanghuijin)         |
| I4P7FF | [标准系统]container特性/List接口规格             | 标准系统       | SIG_CompileRuntime       | [@huanghuijin](https://gitee.com/huanghuijin)         |
| I4P7FE | [标准系统]container特性/Stack接口规格            | 标准系统       | SIG_CompileRuntime       | [@huanghuijin](https://gitee.com/huanghuijin)         |
| I4OGCO | 【新增特性】【DMS】提供跨设备迁移接口                        | 标准系统       | SIG_BasicSoftwareService | [@cangegegege](https://gitee.com/cangegegege)         |
| I4OGCL | 【增强特性】【框架】迁移数据保存                             | 标准系统       | SIG_BasicSoftwareService | [@cangegegege](https://gitee.com/cangegegege)         |
| I4OH9B | 【samgr】动态加载未启动的本地系统服务                        | 标准系统       | SIG_BasicSoftwareService | [@cangegegege](https://gitee.com/cangegegege)         |
| I4OH9A | 【samgr】系统服务启动性能跟踪                                | 标准系统       | SIG_BasicSoftwareService | [@cangegegege](https://gitee.com/cangegegege)         |
| I4OH98 | 【samgr】SAMGR异常恢复                                       | 标准系统       | SIG_BasicSoftwareService | [@cangegegege](https://gitee.com/cangegegege)         |
| I4OH94 | 【device_profile】校验DP客户端访问profile记录的权限          | 标准系统       | SIG_BasicSoftwareService | [@cangegegege](https://gitee.com/cangegegege)         |
| I4OGD6 | 【部件化专项】分布式DeviceProfile子系统部件标准化            | 标准系统       | SIG_BasicSoftwareService | [@cangegegege](https://gitee.com/cangegegege)         |
| I4PBJF | 【部件化专项】distributed_notification_service部件标准化     | 标准系统 | SIG_ApplicationFramework | [@xzz_0810](https://gitee.com/xzz_0810)               |
| I4PBNF | 【部件化专项】common_event部件标准化                         | 标准系统 | SIG_ApplicationFramework | [@xzz_0810](https://gitee.com/xzz_0810)               |
| I4PBO1 | 【资料】通知能力开发者材料                                   | 标准系统 | SIG_ApplicationFramework | [@xzz_0810](https://gitee.com/xzz_0810)               |
| I4PBPM | 【增强特性】分布式通知支持流控                               | 标准系统 | SIG_ApplicationFramework | [@xzz_0810](https://gitee.com/xzz_0810)               |
| I4PBRM | 【新增特性】支持其他设备的通知点击后在本设备跳转             | 标准系统 | SIG_ApplicationFramework | [@xzz_0810](https://gitee.com/xzz_0810)               |
| I4PBRW | 【新增特性】支持设备级的分布式通知使能控制                   | 标准系统 | SIG_ApplicationFramework | [@xzz_0810](https://gitee.com/xzz_0810)               |
| I4PBSE | 【新增特性】支持通知管理应用设置和查询应用级的分布式通知使能 | 标准系统 | SIG_ApplicationFramework | [@xzz_0810](https://gitee.com/xzz_0810)               |
| I4PBSP | 【新增特性】支持应用设置分布式通知能力是否使能               | 标准系统 | SIG_ApplicationFramework | [@xzz_0810](https://gitee.com/xzz_0810)               |
| I4PBT7 | 【新增特性】分布式通知同步                                   | 标准系统 | SIG_ApplicationFramework | [@xzz_0810](https://gitee.com/xzz_0810)               |
| I4PBU3 | 【新增特性】分布式通知联动取消                               | 标准系统 | SIG_ApplicationFramework | [@xzz_0810](https://gitee.com/xzz_0810)               |
| I4PBUU | 【新增规格】 支持通过config.json静态配置公共事件，支持通过wokscheduler静态拉起订阅者 | 标准系统 | SIG_ApplicationFramework | [@xzz_0810](https://gitee.com/xzz_0810)               |
| I4PBV9 | 【新增规格】 支持静态订阅者管控                              | 标准系统 | SIG_ApplicationFramework | [@xzz_0810](https://gitee.com/xzz_0810)               |
| I4PCH4 | 【新增特性】卡片支持多用户                                   | 标准系统   | SIG_ApplicationFramework | [@lsq1474521181](https://gitee.com/lsq1474521181)     |
| I4PCHC | 【元能力-运行管理部件化】基于SysCap的平台代码解耦和部件化改造 | 标准系统   | SIG_ApplicationFramework | [@lsq1474521181](https://gitee.com/lsq1474521181)     |
| I4PCHF | 【元能力-卡片管理部件化】基于SysCap的平台代码解耦和部件化改造 | 标准系统   | SIG_ApplicationFramework | [@lsq1474521181](https://gitee.com/lsq1474521181)     |
| I4PPVU | 【新增特性】进程多实例                                       | 标准系统   | SIG_ApplicationFramework | [@sheilei](https://gitee.com/sheilei)                 |
| I4PPW2 | 【资料】提供测试框架新增/增强特性资料说明                    | 标准系统   | SIG_ApplicationFramework | [@sheilei](https://gitee.com/sheilei)                 |
| I4PCLO | 【增强特性】Ability多实例                                    | 标准系统   | SIG_ApplicationFramework | [@silent-dye](https://gitee.com/silent-dye)           |
| I4PCLR | 【新增特性】动态加载多Hap包                                  | 标准系统   | SIG_ApplicationFramework | [@silent-dye](https://gitee.com/silent-dye)           |
| I4PCM1 | 【新增特性】提供ce/de级上下文                                | 标准系统   | SIG_ApplicationFramework | [@silent-dye](https://gitee.com/silent-dye)           |
| I4PCOQ | 【新增特性】应用管理                                         | 标准系统   | SIG_ApplicationFramework | [@xuezhongzhu](https://gitee.com/xuezhongzhu)         |
| I4PCS2 | 【资料】提供测试工具新增/增强特性资料说明                    | 标准系统   | SIG_ApplicationFramework | [@xuezhongzhu0810](https://gitee.com/xuezhongzhu0810) |
| I4PCVN | 【新增特性】支持任务快照获取和更新                           | 标准系统   | SIG_ApplicationFramework | [@sheilei](https://gitee.com/sheilei)                 |
| I4PCWF | 【资料】提供服务组件新增/增强特性资料说明                    | 标准系统   | SIG_ApplicationFramework | [@sheilei](https://gitee.com/sheilei)                 |
| I4PPW6 | 【增强特性】指定窗口模式启动组件                             | 标准系统|SIG_ApplicationFramework|[@sheilei](https://gitee.com/sheilei)|
| I4PPWA | 【增强特性】Ability框架适配配置文件变更                      | 标准系统|SIG_ApplicationFramework|[@sheilei](https://gitee.com/sheilei)|
| I4PPWD | 【增强特性】Extension框架适配配置文件变更                    | 标准系统|SIG_ApplicationFramework|[@sheilei](https://gitee.com/sheilei)|
| I4PPWI | 【新增特性】快速设置扩展                                     | 标准系统|SIG_ApplicationFramework|[@sheilei](https://gitee.com/sheilei)|
| I4PKY3 | 【部件化专项】bundle_manager部件标准化                       | 标准系统   | SIG_ApplicationFramework | [@shuaytao](https://gitee.com/shuaytao)               |
| I4PKYB | 【增强特性】schema适配配置文件重构                           | 标准系统   | SIG_ApplicationFramework | [@shuaytao](https://gitee.com/shuaytao)               |
| I4PKYD | 【新增特性】安装能力适配config.json调整                      | 标准系统   | SIG_ApplicationFramework | [@shuaytao](https://gitee.com/shuaytao)               |
| I4PKYF | 【新增特性】支持查询指定Metadata资源profile配置文件的信息    | 标准系统   | SIG_ApplicationFramework | [@shuaytao](https://gitee.com/shuaytao)               |
| I4PKYH | 【新增特性】支持对Extension的查询                            | 标准系统   | SIG_ApplicationFramework | [@shuaytao](https://gitee.com/shuaytao)               |
| I4PKYI | 【新增特性】提供清除数据的能力                               | 标准系统   | SIG_ApplicationFramework | [@shuaytao](https://gitee.com/shuaytao)               |
| I4PKYR | 【新增特性】系统定义权限的初始化                             | 标准系统   | SIG_ApplicationFramework | [@shuaytao](https://gitee.com/shuaytao)               |
| I4PKYU | 【新增特性】支持对应用权限信息的查询                         | 标准系统   | SIG_ApplicationFramework | [@shuaytao](https://gitee.com/shuaytao)               |
| I4PXN0 | [编译构建子系统]【增强特性】编译构建日志优化，日志按级别显示               | 标准系统 | SIG_CompileRuntime | [@weichaox](https://gitee.com/weichaox)       |
| I4PXND | [编译构建子系统]【增强特性】hb命令安装、集成及扩展支持               | 标准系统 | SIG_CompileRuntime | [@weichaox](https://gitee.com/weichaox)       |
| I4PKY7 | 【新增特性】跨设备信息同步 | 标准系统 | SIG_ApplicationFramework | [@shuaytao](https://gitee.com/shuaytao) |
| I4PKY8 | 【新增特性】跨设备信息查询 | 标准系统 | SIG_ApplicationFramework | [@shuaytao](https://gitee.com/shuaytao) |
| I4PKYE | 【新增特性】支持查询禁用的组件信息和应用信息 | 标准系统 | SIG_ApplicationFramework | [@shuaytao](https://gitee.com/shuaytao) |
| I4QA2V | 【部件化专项】bundle_tool部件标准化 | 标准系统 | SIG_ApplicationFramework | [@shuaytao](https://gitee.com/shuaytao) |
| I4Q9RC)| [内核子系统]【增强特性】支持指令集融合    | 标准系统 | SIG_Kernel | [@leonchan5](https://gitee.com/leonchan5) |
| I4PZE7 | 【增强特性】支持周边不可信设备的发现    | 标准系统 | SIG_DistributedHardwareManagement | [@renguang1116](https://gitee.com/renguang1116)   |
| I4PZE4 | 【增强特性】支持JSAPI接口    | 标准系统 | SIG_DistributedHardwareManagement | [@renguang1116](https://gitee.com/renguang1116)  |
| I4PZE2 | 【新增特性】支持多用户切换    | 标准系统 | SIG_DistributedHardwareManagement | [@renguang1116](https://gitee.com/renguang1116) |
| I4PZDZ | 【增强特性】支持账号无关设备的PIN码认证    | 标准系统 | SIG_DistributedHardwareManagement | [@renguang1116](https://gitee.com/renguang1116) |
| I4PZDY | 【增强特性】支持可信设备列表查询    | 标准系统 | SIG_DistributedHardwareManagement | [@renguang1116](https://gitee.com/renguang1116) |
| I4PZDT | 【增强特性】支持可信设备的上下线监听    | 标准系统 | SIG_DistributedHardwareManagement | [@renguang1116](https://gitee.com/renguang1116) |
| I4PZDR | 【增强特性】分布式设备管理部件资料    | 标准系统 | SIG_DistributedHardwareManagement | [@renguang1116](https://gitee.com/renguang1116) |
| I4PZC9 | 【新增特性】支持分布式设备管理接口授权控制    | 标准系统 | SIG_DistributedHardwareManagement | [@renguang1116](https://gitee.com/renguang1116) |
| I4PZC7 | 【新增特性】支持设备被发现开关控制    | 标准系统 | SIG_DistributedHardwareManagement | [@renguang1116](https://gitee.com/renguang1116)   |
| I4QESH | 【新增特性】设备Id的查询和转换    | 标准系统 | SIG_DistributedHardwareManagement | [@renguang1116](https://gitee.com/renguang1116)|
| I4QEKP | 【新增特性】基于HDF驱动框架提供light驱动能力                          | 标准系统 | SIG_Driver         | [@xie0812](https://gitee.com/xie0812)           |
| I4QEKR | 【新增特性】Display-Layer、Display-Gralloc、Display-Gfx针对轻量系统的增强参考实现                          | 轻量系统 | SIG_Driver         | [@xie0812](https://gitee.com/xie0812)           |
| I4QEKV | 【新增特性】USB服务 HDI接口实现                          | 标准系统 | SIG_Driver         | [@xie0812](https://gitee.com/xie0812)           |
| I4OEOZ | 【新增特性】监控输入亮屏输入事件，并根据输入事件进行亮、灭屏   | 标准系统       | SIG_HardwareMgr          | [@aqxyjay](https://gitee.com/aqxyjay)                 |
| I4MBRM | 【新增特性】支持接近光控制锁，通话时通过接近光控制亮灭屏的特性   | 标准系统       | SIG_HardwareMgr          | [@aqxyjay](https://gitee.com/aqxyjay)                 |
| I4MBRL | 【新增特性】支持显示相关的能耗调节    | 标准系统       | SIG_HardwareMgr          | [@aqxyjay](https://gitee.com/aqxyjay)                 |
| I4QGI0 | 【新增特性】长按power Key弹出关机界面    | 标准系统       | SIG_HardwareMgr          | [@aqxyjay](https://gitee.com/aqxyjay)                 |
| I4QGJH | 【部件化专项】thermal_manager部件标准化    | 标准系统       | SIG_HardwareMgr          | [@aqxyjay](https://gitee.com/aqxyjay)                 |
| I4QGLI | 【部件化专项】battery_statistics部件标准化    | 标准系统       | SIG_HardwareMgr          | [@aqxyjay](https://gitee.com/aqxyjay)                 |
| I4QT3R | 【部件化专项】标准系统部件标准化 | 标准系统 | SIG_BasicSoftwareService           | [@wangwenli_wolf](https://gitee.com/wangwenli_wolf)                  |
| I4QT3Y | 【新增特性】支持系统进程统一代理三方提醒 | 标准系统 | SIG_BasicSoftwareService           | [@wangwenli_wolf](https://gitee.com/wangwenli_wolf)                  |
| I4QT40 | 【新增特性】提醒后台代理计时能力 | 标准系统 | SIG_BasicSoftwareService           | [@wangwenli_wolf](https://gitee.com/wangwenli_wolf)                  |
| I4QT41 | 【新增特性】提醒代理管理 | 标准系统 | SIG_BasicSoftwareService           | [@wangwenli_wolf](https://gitee.com/wangwenli_wolf)                  |
| I4QT42 | 【新增特性】提醒代理相关资料文档 | 标准系统 | SIG_BasicSoftwareService           | [@wangwenli_wolf](https://gitee.com/wangwenli_wolf)                  |
| I4QT43 | 【新增特性】全局资源调度框架 | 标准系统 | SIG_BasicSoftwareService           | [@wangwenli_wolf](https://gitee.com/wangwenli_wolf)                  |
| I4QU0N | 【新增特性】支持Soc调频 | 标准系统 | SIG_BasicSoftwareService           | [@wangwenli_wolf](https://gitee.com/wangwenli_wolf)                  |
| I4QU0V | 【新增特性】支持短时任务申请/注销/查询 | 标准系统 | SIG_BasicSoftwareService           | [@wangwenli_wolf](https://gitee.com/wangwenli_wolf)                  |
| I4QU0W | 【新增特性】短时任务后台管理 | 标准系统 | SIG_BasicSoftwareService           | [@wangwenli_wolf](https://gitee.com/wangwenli_wolf)                  |
| I4QU0X | 【新增特性】短时任务可维可测 | 标准系统 | SIG_BasicSoftwareService           | [@wangwenli_wolf](https://gitee.com/wangwenli_wolf)                  |
| I4QU0Z | 【新增特性】短时任务相关资料文档 | 标准系统 | SIG_BasicSoftwareService           | [@wangwenli_wolf](https://gitee.com/wangwenli_wolf)                  |
| I4R2MH | 【新增特性】时区数据更新                         | 标准系统 | SIG_ApplicationFramework          | [@mengjingzhimo](https://gitee.com/mengjingzhimo) |
| I4R2M3 | 【新增特性】时区数据部署                         | 标准系统 | SIG_ApplicationFramework          | [@mengjingzhimo](https://gitee.com/mengjingzhimo) |
| I4R2C2 | 【新增特性】多偏好语言                         | 标准系统 | SIG_ApplicationFramework          | [@mengjingzhimo](https://gitee.com/mengjingzhimo) |
| I4R2YF | 【增强特性】ResourceManager适配hap包结构和配置清单文件调整                                     | 标准系统 | SIG_ApplicationFramework          | [@jameshw](https://gitee.com/jameshw)         |
| I4R3DO | 【增强特性】restool工具适配配置清单文件调整                                   | 标准系统 | SIG_ApplicationFramework          | [@jameshw](https://gitee.com/jameshw)         |
| I4OWTZ | [内核子系统]【外部依赖】内核实现进程的tokenID设置     | 标准系统 | SIG_Kernel | [@liuyoufang](https://gitee.com/liuyoufang)       |
| I4QE9K | [内核子系统]【新增特性】提供内核态驱动与用户态之间、用户态与用户态之间的内核共享能力     | 标准系统 | SIG_Kernel | [@liuyoufang](https://gitee.com/liuyoufang)       |
| I4QM8F | [内核子系统]【部件化专项】Linux内核部件标准化     | 标准系统 | SIG_Kernel | [@liuyoufang](https://gitee.com/liuyoufang)       |
| I4Q79P | 【新增特性】【RPC】RPC支持跨设备收发及死亡通知 | 标准系统 | SIG_SoftBus | [@pilipala195](https://gitee.com/pilipala195)       |
| I4Q79C | 【新增特性】【RPC】RPC支持跨设备服务管理 | 标准系统 | SIG_SoftBus | [@pilipala195](https://gitee.com/pilipala195)       |
| I4IIRC | 【新增特性】【RPC】IPC实现tokenid的传递和查询 | 标准系统 | SIG_SoftBus | [@Xi_Yuhao](https://gitee.com/Xi_Yuhao)       |
| I4RCE2 | 【部件化专项】【selinux部件】部件标准化     | 标准系统 | SIG_Security | [@jiang-xiaofeng](https://gitee.com/jiang-xiaofeng)       |
| I4RCDU | 【新增规格】支持只读镜像的文件的标签设置     | 标准系统 | SIG_Security | [@jiang-xiaofeng](https://gitee.com/jiang-xiaofeng)       |
| I4RCDS | 【新增规格】支持native进程标签设置     | 标准系统 | SIG_Security | [@jiang-xiaofeng](https://gitee.com/jiang-xiaofeng)       |
| I4RCD9 | 【新增规格】支持SELinux虚拟文件标签设置     | 标准系统 | SIG_Security | [@jiang-xiaofeng](https://gitee.com/jiang-xiaofeng)       |
| I4RCD6 | 【新增规格】支持SELinux文件标签设置     | 标准系统 | SIG_Security | [@jiang-xiaofeng](https://gitee.com/jiang-xiaofeng)       |
| I4RCD0 | 【新增特性】支持SELinux策略加载和使能     | 标准系统 | SIG_Security | [@jiang-xiaofeng](https://gitee.com/jiang-xiaofeng)       |
| I4RCBT | 【新增规格】提供hap应用selinux domain设置接口库    | 标准系统 | SIG_Security | [@jiang-xiaofeng](https://gitee.com/jiang-xiaofeng)       |
| I4RCB7 | 【新增规格】提供hap应用数据目录的selinux标签设置接口库    | 标准系统 | SIG_Security | [@jiang-xiaofeng](https://gitee.com/jiang-xiaofeng)       |
| I4RCAA | 【新增特性】实现文件系统二级目录的selinux标签设置    | 标准系统 | SIG_Security | [@jiang-xiaofeng](https://gitee.com/jiang-xiaofeng)       |
| I4JBEK | [帐号子系统]支持分布式组网账号ID的派生    | 标准系统 | SIG_BscSoftSrv | [@jiang-xiaofeng](https://gitee.com/jiang-xiaofeng)       |
| I4JBFB | [账号子系统]支持分布式组网账号状态管理    | 标准系统 | SIG_BscSoftSrv | [@jiang-xiaofeng](https://gitee.com/jiang-xiaofeng)       |
| I4IU33 | [帐号子系统]支持本地多用户功能设置与内容修改    | 标准系统 | SIG_BscSoftSrv | [@jiang-xiaofeng](https://gitee.com/jiang-xiaofeng)       |
| I4JBFI | [账号子系统]支持本地多用户分布式信息查询    | 标准系统 | SIG_BscSoftSrv | [@jiang-xiaofeng](https://gitee.com/jiang-xiaofeng)       |
| I4IU3V | [帐号子系统]支持域账户和本地用户关联    | 标准系统 | SIG_BscSoftSrv | [@jiang-xiaofeng](https://gitee.com/jiang-xiaofeng)       |
| I4IU6A | [帐号子系统]支持本地用户约束条件配置    | 标准系统 | SIG_BscSoftSrv | [@jiang-xiaofeng](https://gitee.com/jiang-xiaofeng)       |
| I4IU6N | [帐号子系统]支持本地多用户基础信息管理    | 标准系统 | SIG_BscSoftSrv | [@jiang-xiaofeng](https://gitee.com/jiang-xiaofeng)       |
| I4IU74 | [帐号子系统]支持本地用户的创建和删除    | 标准系统 | SIG_BscSoftSrv | [@jiang-xiaofeng](https://gitee.com/jiang-xiaofeng)       |
| I4RCGG | [帐号子系统]支持用户信息查询    | 标准系统 | SIG_BscSoftSrv | [@jiang-xiaofeng](https://gitee.com/jiang-xiaofeng)       |
| I4QJVZ | 【新增特性】HUKS CORE 算法能力模块Ability化    | 标准系统 | SIG_Security | [@chaos-liang](https://gitee.com/Chaos-Liang)       |
| I4RCRT | [驱动子系统]SR000GNFHL：【新增特性】USB服务 部件标准化                          | 标准系统 | SIG_Driver         | [@wu-chengwen](https://gitee.com/wu-chengwen)           |
| I4RBA4 | [新增特性]PKI应用签名工具支持生成签名密钥 | 标准系统       | SIG_Security | [@zhiwei-liu](https://gitee.com/zhiwei-liu)      |
| I4RBEN | [新增特性]PKI应用签名工具支持生成证书签名请求（CSR）| 标准系统      | SIG_Security | [@zhiwei-liu](https://gitee.com/zhiwei-liu)      |
| I4RBEA | [新增特性]PKI应用签名工具支持生成CA密钥和证书 | 标准系统      | SIG_Security | [@zhiwei-liu](https://gitee.com/zhiwei-liu)       |
| I4RFJP | [部件化专项]【PKISignCentre部件】PKISignCentre部件标准化 | 标准系统      | SIG_Security | [@zhiwei-liu](https://gitee.com/zhiwei-liu)       |
| I4PNX7 |【分布式RDB】数据存储需求|标准系统|SIG_DataManagement|[@widecode](https://gitee.com/widecode)|
| I4R6T4 |【部件化专项】【native_appdatamgr部件】native_appdatamgr部件标准化|标准系统|SIG_DataManagement|[@mangtsang](https://gitee.com/mangtsang)|
| I4RFYC |【部件化专项】【objectstore部件】分布式数据对象部件标准化|标准系统|SIG_DataManagement|[@widecode](https://gitee.com/widecode)|
| I4H3LS |分布式数据对象提供JS接口|标准系统|SIG_DataManagement|[@widecode](https://gitee.com/widecode)|
| I4NUD5 |方舟C++ FFI支持继承关系|标准系统|SIG_CompileRuntime|[@weng-changcheng](https://gitee.com/weng-changcheng)|
| I4P86T |支持Worker中可以再创建Worker，子Worker可以跟父Worker通信|标准系统|SIG_CompileRuntime|[@weng-changcheng](https://gitee.com/weng-changcheng)|
| I4P7FN |【新增规格】container特性/LinkedList接口规格|标准系统|SIG_CompileRuntime|[@gongjunsong](https://gitee.com/gongjunsong)|
| I4RG4R | 【DFX】用户IAM框架DFX需求 | 标准系统      | SIG_Security | [@wangxu](https://gitee.com/wangxu43)       |
| I4RG4X | 【user_idm】支持用户本地人脸的删除 | 标准系统      | SIG_Security | [@wangxu](https://gitee.com/wangxu43)       |
| I4RG55 | 【user_idm】支持用户本地认证凭据信息查询 | 标准系统      | SIG_Security | [@wangxu](https://gitee.com/wangxu43)       |
| I4RG59 | 【user_idm】支持用户本地口令的录入 | 标准系统      | SIG_Security | [@wangxu](https://gitee.com/wangxu43)       |
| I4RG5G | 【user_idm】支持用户本地口令的删除 | 标准系统      | SIG_Security | [@wangxu](https://gitee.com/wangxu43)       |
| I4RG5M | 【user_idm】支持用户本地人脸的录入 | 标准系统      | SIG_Security | [@wangxu](https://gitee.com/wangxu43)       |
| I4RG5R | 【user_idm】支持删除用户时，删除该用户的身份认证凭据 | 标准系统      | SIG_Security | [@wangxu](https://gitee.com/wangxu43)       |
| I4RGMX | 【部件化专项】【user_idm部件】部件标准化 | 标准系统      | SIG_Security | [@wangxu](https://gitee.com/wangxu43)       |
| I4RGMD | 【部件化专项】【face_auth部件】部件标准化 | 标准系统      | SIG_Security | [@wangxu](https://gitee.com/wangxu43)       |
| I4RGND | 【部件化专项】【user_auth部件】部件标准化 | 标准系统      | SIG_Security | [@wangxu](https://gitee.com/wangxu43)       |
| I4RG8D | 【user_auth】支持用户本地口令认证 | 标准系统      | SIG_Security | [@wangxu](https://gitee.com/wangxu43)       |
| I4RG7W | 【user_auth】支持用户本地人脸认证 | 标准系统      | SIG_Security | [@wangxu](https://gitee.com/wangxu43)       |
| I4RGNO | 【部件化专项】【pin_auth部件】部件标准化 | 标准系统      | SIG_Security | [@wangxu](https://gitee.com/wangxu43)       |
| I4RG9E | 【DFX】口令认证框架DFX需求 | 标准系统      | SIG_Security | [@wangxu](https://gitee.com/wangxu43)       |
| I4RG91 | 【pin_auth】支持用户本地口令认证 | 标准系统      | SIG_Security | [@wangxu](https://gitee.com/wangxu43)       |
| I4RG8W | 【pin_auth】支持用户本地口令录入 | 标准系统      | SIG_Security | [@wangxu](https://gitee.com/wangxu43)       |
| I4RGO7 | 【部件化专项】【auth_executor_mgr部件】部件标准化| 标准系统      | SIG_Security | [@wangxu](https://gitee.com/wangxu43)       |
| I4RGU3 | 【pin_auth】提供软实现| 标准系统      | SIG_Security | [@wangxu](https://gitee.com/wangxu43)       |
| I4RGUM | 【useriam】提供软实现| 标准系统      | SIG_Security | [@wangxu](https://gitee.com/wangxu43)       |
| I4RGWU | 【pin_auth】支持用户本地口令删除| 标准系统      | SIG_Security | [@wangxu](https://gitee.com/wangxu43)       |
| I4RCRM |【IDE工具支持】交互事件回调耗时打印|标准系统|SIG_ArkUI|[@qieqiewl](https://gitee.com/qieqiewl)|
| I4RCRL |【IDE工具支持】渲染流水线耗时打印|标准系统|SIG_ArkUI|[@qieqiewl](https://gitee.com/qieqiewl)|
| I4RCRK |【DFX】ACE框架超时检测机制|标准系统|SIG_ArkUI|[@qieqiewl](https://gitee.com/qieqiewl)|
| I4RCRI |【新增规格】卡片支持鼠标悬停事件|标准系统|SIG_ArkUI|[@qieqiewl](https://gitee.com/qieqiewl)|
| I4RCRH |【新增特性】自定义builder|标准系统|SIG_ArkUI|[@qieqiewl](https://gitee.com/qieqiewl)|
| I4RCRG |【新增特性】$$双向绑定编译转换支持|标准系统|SIG_ArkUI|[@qieqiewl](https://gitee.com/qieqiewl)||
| I4RCRF |【新增特性】新增自定义组件支持访问子组件数据|标准系统|SIG_ArkUI|[@qieqiewl](https://gitee.com/qieqiewl)|
| I4RCRE |【新增特性】新增NAPI继承机制|标准系统|SIG_ArkUI|[@qieqiewl](https://gitee.com/qieqiewl)|
| I4RCRD |【新增规格】新增OffscreenCanvas支持抗锯齿特性|标准系统|SIG_ArkUI|[@qieqiewl](https://gitee.com/qieqiewl)|
| I4RCRC |【新增特性】样式状态编译转换支持|标准系统|SIG_ArkUI|[@qieqiewl](https://gitee.com/qieqiewl)|
| I4RCRA |【新增特性】ArkUI对接窗口新架构|标准系统|SIG_ArkUI|[@qieqiewl](https://gitee.com/qieqiewl)|
| I4Q8ZH |【跟踪】【hiappevent部件】应用事件功能增强|标准系统|SIG_BasicSoftwareService|[@guochuanqi](https://gitee.com/guochuanqi)|
| I4RCR0 |【跟踪】【hilog部件】流水日志功能增强|标准系统|SIG_BasicSoftwareService|[@guochuanqi](https://gitee.com/guochuanqi)|
| I4Q6AS |【资料】faultloggerd部件 南北向文档需求|标准系统|SIG_BasicSoftwareService|[@guochuanqi](https://gitee.com/guochuanqi)|
| I4NJTS |[轻量级图形子系统]支持通用touch事件、list组件支持scrollbottom/scrolltop事件|轻量系统|SIG_AppFramework|[@piggyguy](https://gitee.com/piggyguy)|
| I4NJTD |[轻量级图形子系统]list组件支持scrollbottom/scrolltop事件|轻量系统|SIG_AppFramework|[@piggyguy](https://gitee.com/piggyguy)|
| I4RFBD |【新增特性】【local_file_system】支持fat/exfat/ntfs等可插拔文件系统能力|标准系统|SIG_Kernel|[@panqinxu](https://gitee.com/panqinxu)|
| I4RDNG |【新增特性】【local_file_system】支持ext4/f2fs等用户态工具的能力|标准系统|SIG_Kernel|[@panqinxu](https://gitee.com/panqinxu)|
| I4RE2G |【新增特性】【local_file_system】支持ext4/f2fs格式镜像打包能力|标准系统|SIG_Kernel|[@panqinxu](https://gitee.com/panqinxu)|
| I4RENG |【新增特性】【local_file_system】支持ext4/f2fs文件系统开机resize和fsck|标准系统|SIG_Kernel|[@panqinxu](https://gitee.com/panqinxu)|
| I4RF6Z |【新增特性】【local_file_system】支持fat/exfat/ntfs等可插拔文件系统能力|标准系统|SIG_Kernel|[@panqinxu](https://gitee.com/panqinxu)|
| I4RFEQ |【新增特性】【storage_service部件】支持密钥存储管理|标准系统|SIG_Kernel|[@panqinxu](https://gitee.com/panqinxu)|
| I4RG9F |【新增特性】【storage_service】CE/DE文件软加密策略管理|标准系统|SIG_Kernel|[@panqinxu](https://gitee.com/panqinxu)|
| I4PW8P |【新增特性】支持生成部件列表和部件依赖关系|标准系统|SIG_CompileRuntime|@烈烈(https://gitee.com/xiaolielie)|
| I4ROL2 |【通话】-通话中支持DTMF键盘 | 标准系统    | SIG_SystemApplication   |[@sunjunxiong](https://gitee.com/sunjunxiong)|
| I4ROL0 |【通话】-通话中显示状态及计时 | 标准系统    | SIG_SystemApplication   |[@sunjunxiong](https://gitee.com/sunjunxiong)|
| I4ROKZ |【通话】-来电支持通话页面拉起| 标准系统    | SIG_SystemApplication   |[@sunjunxiong](https://gitee.com/sunjunxiong)|
| I4ROKY |【通话】-通话中显示联系人号码和姓名 | 标准系统    | SIG_SystemApplication   |[@sunjunxiong](https://gitee.com/sunjunxiong)|
| I4ROLD |【通话】-来电显示通知 | 标准系统    | SIG_SystemApplication   |[@sunjunxiong](https://gitee.com/sunjunxiong)|
| I4ROLG |【短信】- 短信 - 短信接收 | 标准系统    | SIG_SystemApplication   |[@sunjunxiong](https://gitee.com/sunjunxiong)|
| I4ROKU |【短信】- 短信 - 短信接收 | 标准系统    | SIG_SystemApplication   |[@sunjunxiong](https://gitee.com/sunjunxiong)|
| I4QKLL |【短信】- 短信 - 短信单发（单卡）| 标准系统    | SIG_SystemApplication   |[@sunjunxiong](https://gitee.com/sunjunxiong)|
| I4QKLK |【短信】- 短信 - 短信送达报告 | 标准系统    | SIG_SystemApplication   |[@sunjunxiong](https://gitee.com/sunjunxiong)|
| I4WTGK |【新增特性】支持模板通知注册、查询和发送 | 标准系统 | SIG_ApplicationFramework |[@xzz_0810](https://gitee.com/xzz_0810)|
| I4WTJA |【增强特性】新增字段的Schema校验 | 标准系统 | SIG_ApplicationFramework |[@xzz_0810](https://gitee.com/xzz_0810)|
| I4WTJV |【新增特性】支持查询包含metadata的组件信息和应用信息 | 标准系统 | SIG_ApplicationFramework |[@xzz_0810](https://gitee.com/xzz_0810)|
| I4WTM0 |【增强特性】数据目录创建 | 标准系统 | SIG_ApplicationFramework |[@xzz_0810](https://gitee.com/xzz_0810)|
| I4WTM9 |【增强特性】支持安装包信息新增字段查询 | 标准系统 | SIG_ApplicationFramework |[@xzz_0810](https://gitee.com/xzz_0810)|
| I4WU7S |【增强特性】支持可卸载预置鸿蒙应用的卸载 | 标准系统 | SIG_ApplicationFramework |[@xzz_0810](https://gitee.com/xzz_0810)|
| I4WU8F |【增强特性】支持可卸载预置应用的升级 | 标准系统 | SIG_ApplicationFramework |[@xzz_0810](https://gitee.com/xzz_0810)|
| I4WU8Z |【新增特性】支持可卸载预置应用卸载后的恢复 | 标准系统 | SIG_ApplicationFramework |[@xzz_0810](https://gitee.com/xzz_0810)|
| I4WU9N |【增强特性】支持hap包中config文件新增字段的解析和存储 | 标准系统 | SIG_ApplicationFramework |[@xzz_0810](https://gitee.com/xzz_0810)|
| I4WUA1 |【新增特性】禁用/使能APP、组件 | 标准系统 | SIG_ApplicationFramework |[@xzz_0810](https://gitee.com/xzz_0810)|
| I4WUAL |【新增特性】支持查询仅系统应用的组件信息 | 标准系统 | SIG_ApplicationFramework |[@xzz_0810](https://gitee.com/xzz_0810)|
| I4PKZ3 |【新增特性】应用AccessToken的初始化及删除 | 标准系统 | SIG_ApplicationFramework |[@shuaytao](https://gitee.com/shuaytao)|
| I4WV7N |【新增特性】【任务管理】查询任务列表 | 标准系统 | SIG_ApplicationFramework |[@xzz_0810](https://gitee.com/xzz_0810)|
| I4WV8I |【新增特性】【任务管理】同步任务列表 | 标准系统 | SIG_ApplicationFramework |[@xzz_0810](https://gitee.com/xzz_0810)|
| I4WV8Y |【资料】跨设备启动组件新增/增强特性资料说明 | 标准系统 | SIG_ApplicationFramework |[@xzz_0810](https://gitee.com/xzz_0810)|
| I4WV9L |【增强特性】【DMS】跨设备组件调用验收demo | 标准系统 | SIG_ApplicationFramework |[@xzz_0810](https://gitee.com/xzz_0810)|
| I4WVA1 |【增强特性】【DMS】跨设备启动组件验收demo | 标准系统 | SIG_ApplicationFramework |[@xzz_0810](https://gitee.com/xzz_0810)|
| I4WVAG |【增强特性】【框架】支持跨设备任务迁移 | 标准系统 | SIG_ApplicationFramework |[@xzz_0810](https://gitee.com/xzz_0810)|
| I4WVBL |【增强特性】【AMS】支持跨设备任务迁移 | 标准系统 | SIG_ApplicationFramework |[@xzz_0810](https://gitee.com/xzz_0810)|
| I4WVC4 |【增强特性】【AMS】支持迁移结果通知客户端 | 标准系统 | SIG_ApplicationFramework |[@xzz_0810](https://gitee.com/xzz_0810)|
| I4WVCI |【增强特性】【DMS】支持跨设备任务迁移 | 标准系统 | SIG_ApplicationFramework |[@xzz_0810](https://gitee.com/xzz_0810)|
| I4WVCW |【增强特性】【DMS】支持跨设备组件调用 | 标准系统 | SIG_ApplicationFramework |[@xzz_0810](https://gitee.com/xzz_0810)|
| I4WVDI |【增强特性】【AMS】支持跨设备组件调用 | 标准系统 | SIG_ApplicationFramework |[@xzz_0810](https://gitee.com/xzz_0810)|
| I4WVEG |【增强特性】【框架】支持跨设备组件调用 | 标准系统 | SIG_ApplicationFramework |[@xzz_0810](https://gitee.com/xzz_0810)|
| I4WVGL |【增强特性】【AMS】支持跨设备启动组件 | 标准系统 | SIG_ApplicationFramework |[@xzz_0810](https://gitee.com/xzz_0810)|
| I4WVH1 |【增强特性】【框架】支持跨设备启动组件 | 标准系统 | SIG_ApplicationFramework |[@xzz_0810](https://gitee.com/xzz_0810)|
| I4WVHL |【增强特性】【DMS】支持跨设备启动组件 | 标准系统 | SIG_ApplicationFramework |[@xzz_0810](https://gitee.com/xzz_0810)|
| I4WVI9 |【增强特性】上下文提供获取应用不同路径接口 | 标准系统 | SIG_ApplicationFramework |[@xzz_0810](https://gitee.com/xzz_0810)|
| I4MBT0 |【增强特性】上下文提供获取资源管理器接口 | 标准系统 | SIG_ApplicationFramework |[@dongjinguang](https://gitee.com/dongjinguang)|
| I4MBT1 |【增强特性】提供创建指定应用上下文的能力 | 标准系统 | SIG_ApplicationFramework |[@dongjinguang](https://gitee.com/dongjinguang)|
| I4WVJJ |【增强特性】系统环境变化通知AbilityStage和Extension | 标准系统 | SIG_ApplicationFramework |[@xzz_0810](https://gitee.com/xzz_0810)|
| I4WVJY |【增强特性】系统环境变化通知支持深浅色模式 | 标准系统 | SIG_ApplicationFramework |[@xzz_0810](https://gitee.com/xzz_0810)|
| I4WVKB |【增强特性】系统环境变化通知支持字体大小变化 | 标准系统 | SIG_ApplicationFramework |[@xzz_0810](https://gitee.com/xzz_0810)|
| I4WVKN |【增强特性】系统环境变化通知支持转屏 | 标准系统 | SIG_ApplicationFramework |[@xzz_0810](https://gitee.com/xzz_0810)|
| I4WVL2 |【增强特性】系统环境变化通知支持displayid | 标准系统 | SIG_ApplicationFramework |[@xzz_0810](https://gitee.com/xzz_0810)|
| I4WVLM |【增强特性】系统环境变化通知支持densitydpi | 标准系统 | SIG_ApplicationFramework |[@xzz_0810](https://gitee.com/xzz_0810)|
| I4MBT5 |【新增特性】启动拉起调试引擎 | 标准系统 | SIG_ApplicationFramework |[@dongjinguang](https://gitee.com/dongjinguang)|
| I4MBT6 |【新增特性】支持分享图片、视频、文件等到其他应用 | 标准系统 | SIG_ApplicationFramework |[@dongjinguang](https://gitee.com/dongjinguang)|
| I4MBT8 |【新增特性】通用组件启动过程联调 | 标准系统 | SIG_ApplicationFramework |[@dongjinguang](https://gitee.com/dongjinguang)|
| I4MBT9 |【新增特性】通用组件从前台调度到后台的过程联调 | 标准系统 | SIG_ApplicationFramework |[@dongjinguang](https://gitee.com/dongjinguang)|
| I4MBTA |【新增特性】结束通用组件 | 标准系统 | SIG_ApplicationFramework |[@dongjinguang](https://gitee.com/dongjinguang)|
| I4MBTB |【新增特性】通用组件支持带返回值调用 | 标准系统 | SIG_ApplicationFramework |[@dongjinguang](https://gitee.com/dongjinguang)|
| I4MBTD |【新增特性】支持Ability的可见性配置 | 标准系统 | SIG_ApplicationFramework |[@dongjinguang](https://gitee.com/dongjinguang)|
| I4MBTE |【新增特性】支持从系统服务启动Ability | 标准系统 | SIG_ApplicationFramework |[@dongjinguang](https://gitee.com/dongjinguang)|
| I4MBTF |【新增特性】提供Ability和上下文 | 标准系统 | SIG_ApplicationFramework |[@dongjinguang](https://gitee.com/dongjinguang)|
| I4MBTG |【新增特性】创建通用组件 | 标准系统 | SIG_ApplicationFramework |[@dongjinguang](https://gitee.com/dongjinguang)|
| I4MBTH |【新增特性】启动通用组件 | 标准系统 | SIG_ApplicationFramework |[@dongjinguang](https://gitee.com/dongjinguang)|
| I4MBTI |【新增特性】调度通用组件从前台到后台 | 标准系统 | SIG_ApplicationFramework |[@dongjinguang](https://gitee.com/dongjinguang)|
| I4MBTJ |【新增特性】获取Scene对象 | 标准系统 | SIG_ApplicationFramework |[@dongjinguang](https://gitee.com/dongjinguang)|
| I4WVO4 |【增强特性】PA对接方舟引擎 | 标准系统 | SIG_ApplicationFramework |[@xzz_0810](https://gitee.com/xzz_0810)|
| I4MBTK |【新增特性】提供Service和上下文 | 标准系统 | SIG_ApplicationFramework |[@dongjinguang](https://gitee.com/dongjinguang)|
| I4MBTL |【增强特性】服务组件生命周期 | 标准系统 | SIG_ApplicationFramework |[@dongjinguang](https://gitee.com/dongjinguang)|
| I4MBTM |【增强特性】服务组件启动/调用 | 标准系统 | SIG_ApplicationFramework |[@dongjinguang](https://gitee.com/dongjinguang)|
| I4QZVB  | 【部件化专项】【Access Token部件】部件标准化     | 标准系统 | SIG_Security | [@jiang-xiaofeng](https://gitee.com/jiang-xiaofeng)       |
| I4WVPH  | 【新增规格】AT同步服务基本框架     | 标准系统 | SIG_Security | [@jiang-xiaofeng](https://gitee.com/jiang-xiaofeng)       |
| I4WVQT  | 【新增规格】native的Token创建和更新机制      | 标准系统 | SIG_Security | [@jiang-xiaofeng](https://gitee.com/jiang-xiaofeng)       |
| I4WTQ5 | 【新增规格】ACE打包工具适配包结构和配置文件变化                          | 标准系统|SIG_ArkUI|[@qieqiewl](https://gitee.com/qieqiewl) |
| I4WTPI | 【新增规格】video组件重新对接窗口新架构                          | 标准系统|SIG_ArkUI|[@qieqiewl](https://gitee.com/qieqiewl) |
| I4WTPR | 【新增规格】Swiper组件动画自定义能力支持                           | 标准系统|SIG_ArkUI|[@qieqiewl](https://gitee.com/qieqiewl) |
| I4WTQ7 | 【新增规格】低代码编译支持                           | 标准系统|SIG_ArkUI|[@qieqiewl](https://gitee.com/qieqiewl) |
| I4WTR8 | 【新增特性】Web组件能力支持                          | 标准系统|SIG_ArkUI|[@qieqiewl](https://gitee.com/qieqiewl) |
| I4WTRB | 【新增特性】路由信息分布式迁移支持                           | 标准系统|SIG_ArkUI|[@qieqiewl](https://gitee.com/qieqiewl) |
| I4WTQJ | 【新增规格】输入组件键盘快捷键支持                           | 标准系统|SIG_ArkUI|[@qieqiewl](https://gitee.com/qieqiewl) |
| I4WTR5 | 【新增特性】XComponent组件特性支持基础渲染规格                           | 标准系统|SIG_ArkUI|[@qieqiewl](https://gitee.com/qieqiewl) |
| I4WTR2 | 【新增规格】XComponent组件支持Workder特性支持多级Worker规格和调试                           | 标准系统|SIG_ArkUI|[@qieqiewl](https://gitee.com/qieqiewl) |
| I4WTQV | 【新增特性】增加场景数据存储特性                           | 标准系统|SIG_ArkUI|[@qieqiewl](https://gitee.com/qieqiewl) |
| I4WTPS | 【新增规格】新增Touch事件支持多点触控信息                           | 标准系统|SIG_ArkUI|[@qieqiewl](https://gitee.com/qieqiewl) |
| I4WWTB | 【泛sensor】系统部件标准化 | 标准系统 | SIG_DistributedHardwareManagement | 标准系统 | SIG_DistributedHardwareManagement | [@hhh2](https://gitee.com/hhh2) |
| I4WWRO | 【msdp】device_status部件标准化 | 标准系统 | SIG_DistributedHardwareManagement | 标准系统 | SIG_DistributedHardwareManagement | [@hhh2](https://gitee.com/hhh2) |
| I4WWRP | 【多模】input部件标准化 | 标准系统 | SIG_DistributedHardwareManagement | [@hhh2](https://gitee.com/hhh2) |
| I4R304 | 【可测试性】提供命令行截图能力 | 标准系统 | SIG-Graphics | [@lz-230](https://gitee.com/lz-230) |
| I4R9OU | 【window_manager】【新增特性】提供沉浸式能力 | 标准系统 | SIG-Graphics | [@lz-230](https://gitee.com/lz-230) |
| I4R306 | 【window_manager】【新增特性】快照能力 | 标准系统 | SIG-Graphics | [@lz-230](https://gitee.com/lz-230) |
| I4R307 | 【window_manager】【新增特性】快照能力 | 标准系统 | SIG-Graphics | [@lz-230](https://gitee.com/lz-230) |
| I4R30C | 【window_manager】【新增特性】应用主窗口支持分屏显示 | 标准系统 | SIG-Graphics | [@lz-230](https://gitee.com/lz-230) |
| I4R2ZY | 【window_manager】【增强特性】：提供输入法窗口 重构特性 | 标准系统 | SIG-Graphics | [@lz-230](https://gitee.com/lz-230) |
| I4R300 | 【window_manager】【增强特性】提供输入法窗口 新增特性 | 标准系统 | SIG-Graphics | [@lz-230](https://gitee.com/lz-230) |
| I4R9OW | 【window_manager】【新增规格】系统窗口创建和管理能力 | 标准系统 | SIG-Graphics | [@lz-230](https://gitee.com/lz-230) |
| I4R9OX | 【window_manager】【新增规格】系统窗口创建和管理能力 | 标准系统 | SIG-Graphics | [@lz-230](https://gitee.com/lz-230) |
| I4RKT8 | 【render_service部件】【新增规格】新增ACE1.0控件接入RenderService渲染后端规格 | 标准系统 | SIG-Graphics | [@lz-230](https://gitee.com/lz-230) |
| I4RKT6 | 【render_service部件】【新增特性】新增RenderService支持多屏绘制特性 | 标准系统 | SIG-Graphics | [@lz-230](https://gitee.com/lz-230) |
| I4RKT4 | 【render_service部件】【新增特性】新增RenderService支持窗口绘制特性 | 标准系统 | SIG-Graphics | [@lz-230](https://gitee.com/lz-230) |
| I4R9PB | 【composer部件】【新增特性 显示设备管理】显示设备管理 | 标准系统 | SIG-Graphics | [@lz-230](https://gitee.com/lz-230) |
| I4RKSY | 【2d_engine部件】 skia及其依赖库开源引入 | 标准系统 | SIG-Graphics | [@lz-230](https://gitee.com/lz-230) |
| I4RKSW | 【drawing部件】提供3D 图形能力支持NDK能力 | 标准系统 | SIG-Graphics | [@lz-230](https://gitee.com/lz-230) |
| I4RKSV | 【drawing部件】提供webgl 图形能力 | 标准系统 | SIG-Graphics | [@lz-230](https://gitee.com/lz-230) |
| I4ZEKH | 【window_manager】【新增特性】支持亮屏灭屏流程 | 标准系统 | SIG-Graphics | [@lz-230](https://gitee.com/lz-230) |
| I4P7F1 | [标准系统]方舟支持列号显示       | 标准系统       | SIG_CompileRuntime       | [@huanghuijin](https://gitee.com/huanghuijin)     |
| I4PC3R | 【新增特性】提供卡片开发基础能力             | 标准系统   | SIG_ApplicationFramework | [@lsq1474521181](https://gitee.com/lsq1474521181) |
| I4PCGJ | 【资料】提供卡片框架新增/增强特性资料说明    | 标准系统   | SIG_ApplicationFramework | [@lsq1474521181](https://gitee.com/lsq1474521181) |
| I4PCO3 | 【新增特性】主线程EventRunner耗时检测        | 标准系统   | SIG_ApplicationFramework | [@xuezhongzhu](https://gitee.com/xuezhongzhu)     |
| I4PPZF | 【增强特性】卡片框架适配配置文件变更         | 标准系统   | SIG_ApplicationFramework | [@sheilei](https://gitee.com/sheilei)             |
| I4PQ0I | 【增强特性】获取启动参数                     | 标准系统   | SIG_ApplicationFramework | [@sheilei](https://gitee.com/sheilei)             |
| I4PQ0K | 【增强特性】扩展Extension独立进程运行        | 标准系统   | SIG_ApplicationFramework | [@sheilei](https://gitee.com/sheilei)             |
| I4PQ0M | 【增强特性】上下文提供消息发送和监听能力     | 标准系统   | SIG_ApplicationFramework | [@sheilei](https://gitee.com/sheilei)             |
| I4PQ0Z | 【新增特性】支持导出客户端应用信息           | 标准系统   | SIG_ApplicationFramework | [@sheilei](https://gitee.com/sheilei)             |
| I4PQ12 | 【新增特性】支持导出AMS信息                  | 标准系统   | SIG_ApplicationFramework | [@sheilei](https://gitee.com/sheilei)             |
| I4PQ13 | 【增强特性】上下文提供权限校验及权限申请接口 | 标准系统   | SIG_ApplicationFramework | [@sheilei](https://gitee.com/sheilei)             |
| I4PQ19 | 【新增特性】支持桌面进程异常恢复             | 标准系统   | SIG_ApplicationFramework | [@sheilei](https://gitee.com/sheilei)             |
| I4PQ1E | 【增强特性】支持常驻进程异常恢复             | 标准系统   | SIG_ApplicationFramework | [@sheilei](https://gitee.com/sheilei)             |
| I4PQ1O | 【新增特性】支持NewWant                      | 标准系统   | SIG_ApplicationFramework | [@xzz_0810](https://gitee.com/xzz_0810)           |
| I4PKYG | 【新增特性】支持关键流程hitrace              | 标准系统   | SIG_ApplicationFramework | [@shuaytao](https://gitee.com/shuaytao)           |
| I4PKYK | 【增强特性】启动扫描                         | 标准系统   | SIG_ApplicationFramework | [@shuaytao](https://gitee.com/shuaytao)           |
| I4SIH9 | 【新增特性】应用申请权限管理                 | 标准系统   | SIG_ApplicationFramework | [@shuaytao](https://gitee.com/shuaytao)           |
| I4PBSZ | 【新增特性】根据设备状态决策通知是否提醒     | 标准系统 | SIG_ApplicationFramework | [@xzz_0810](https://gitee.com/xzz_0810)           |
| I4QESE | 【新增特性】PIN码认证过程中的界面实现    | 标准系统 | SIG_DistributedHardwareManagement | [@renguang1116](https://gitee.com/renguang1116)
| I4QESK | 【部件化专项】【device_manager部件】device_manager部件标准化   | 标准系统 | SIG_DistributedHardwareManagement | [@renguang1116](https://gitee.com/renguang1116)
| I4QEKW | 【新增特性】提供codec设备驱动模型，支持codec类型设备                          | 标准系统 | SIG_Driver         | [@xie0812](https://gitee.com/xie0812)           |
| I4QEKX | 【特性增强】pipeline模块能力增强                          | 标准系统 | SIG_Driver         | [@xie0812](https://gitee.com/xie0812)           |
| I4QT44 | 【新增特性】短时任务相关资料文档 | 标准系统 | SIG_BasicSoftwareService           | [@wangwenli_wolf](https://gitee.com/wangwenli_wolf)                  |
| I4R2CV | 【增强特性】大小写转换                         | 标准系统 | SIG_ApplicationFramework          | [@mengjingzhimo](https://gitee.com/mengjingzhimo) |
| I4R2X9 | 【部件化专项】全球化子系统部件标准化                                     | 标准系统 | SIG_ApplicationFramework          | [@jameshw](https://gitee.com/jameshw)         |
| I4R3CG | 【新增特性】资源预览优化                                     | 标准系统 | SIG_ApplicationFramework          | [@jameshw](https://gitee.com/jameshw)         |
| I4OH95 | 【部件化专项】系统服务管理子系统部件标准化                   | 标准系统       | SIG_BasicSoftwareService | [@cangegegege](https://gitee.com/cangegegege)         |
| I4RD2M | 【部件化专项】LiteOS-M内核部件标准化                  | 轻量系统       | SIG_Kernel | [@leonchan5](https://gitee.com/leonchan5)
| I4RD2U | 【部件化专项】LiteOS-A内核部件标准化                  | 轻量系统       | SIG_Kernel | [@leonchan5](https://gitee.com/leonchan5)
| I4R6SK |【部件化专项】【key_value_store部件】key_value_store部件标准化|标准系统|SIG_DataManagement|[@widecode](https://gitee.com/widecode)|
| I4QEKQ | 【新增特性】Display的Gralllo、Gfx和Device的HDI接口实现服务                          | 标准系统 | SIG_Driver         | [@xie0812](https://gitee.com/xie0812)           |
| I4QEKS | 【新增特性】platform_driver部件标准化                          | 标准系统 | SIG_Driver         | [@xie0812](https://gitee.com/xie0812)           |
| I4QEKT | 【新增特性】peripheral_driver部件标准化                          | 标准系统 | SIG_Driver         | [@xie0812](https://gitee.com/xie0812)           |
| I4QEKU | 【新增特性】driver_framework部件标准化                          | 标准系统 | SIG_Driver         | [@xie0812](https://gitee.com/xie0812)           |
| I4RTX4 | 【部件化专项】设备安全等级管理（DSLM）部件标准             | 标准系统        | SIG_Security                      | [@zhirenx](https://gitee.com/zhirenx)                    |
| I4P7EX | [标准系统]DFX维测支持运行时支持DFX/在异常时需要hook机制以及栈列信息特性 | 标准系统       | SIG_CompileRuntime       | [@huanghuijin](https://gitee.com/huanghuijin)         |
| I4RFWF | 【部件化专项】【deviceauth部件】deviceauth部件标准化 | 标准系统       | SIG_Security       | [@lvyuanmin](https://gitee.com/lvyuanmin)         |
| I4S36A | [标准系统]【部件化专项】ts_js_common_api部件标准化 | 标准系统     | SIG_CompileRuntime       | [@huanghuijin](https://gitee.com/huanghuijin)         |
| I4S36C | [标准系统]【部件化专项】cpp_compiler_toolchain部件标准化 | 标准系统     | SIG_CompileRuntime       | [@huanghuijin](https://gitee.com/huanghuijin)         |
| I4S36D | [标准系统]【部件化专项】ark_ide_support部件标准化 | 标准系统     | SIG_CompileRuntime       | [@huanghuijin](https://gitee.com/huanghuijin)         |
| I4S36F | [标准系统]【部件化专项】ark_frontend_compiler部件标准化 | 标准系统     | SIG_CompileRuntime       | [@huanghuijin](https://gitee.com/huanghuijin)         |
| I4S36G | [标准系统]【部件化专项】ark_runtime部件标准化 | 标准系统     | SIG_CompileRuntime       | [@huanghuijin](https://gitee.com/huanghuijin)         |
| I4RXK2 | 【新增特性】支持为进程代持fd                      | 标准系统 | SIG_BscSoftSrv       | [@handyohos](https://gitee.com/handyohos)     |
| I4RXJM | 【新增特性】支持进程根据热插拔事件按需启动                                | 标准系统 | SIG_BscSoftSrv       | [@handyohos](https://gitee.com/handyohos)     |
| I4RXJ9 | 【新增特性】支持socket类进程按需启动                               | 标准系统 | SIG_BscSoftSrv       | [@handyohos](https://gitee.com/handyohos)     |
| I4RXJ2 | 【新增规格】统一init维护命令                                | 标准系统 | SIG_BscSoftSrv       | [@handyohos](https://gitee.com/handyohos)     |
| I4S6QC | 【资料】标准系统介绍资料需求                                | 标准系统 | SIG_Security       | [@wangxu](https://gitee.com/wangxu43)     |
| I4LRGQ | [内核子系统]【新增特性】OpenHarmony内核基线使能     | 标准系统 | SIG_Kernel | [@liuyoufang](https://gitee.com/liuyoufang)       |
| I4RU58 | 【部件化专项】【data_transit_mgr_lib部件】data_transit_mgr_lib部件标准化  | 标准系统   | SIG_Security  | [@wangyongzhong2](https://gitee.com/wangyongzhong2)  |
| I4SEZD | 【新增规格】动态权限弹窗界面实现    | 标准系统 | SIG_Security | [@jiang-xiaofeng](https://gitee.com/jiang-xiaofeng)       |
| I4SEZ7 | 【动态权限设置】实现动态权限授权机制    | 标准系统 | SIG_Security | [@jiang-xiaofeng](https://gitee.com/jiang-xiaofeng)       |
| I4ITYY | [帐号子系统]支持应用账号基础鉴权功能    | 标准系统 | SIG_BscSoftSrv | [@jiang-xiaofeng](https://gitee.com/jiang-xiaofeng)       |
| I4SHYL | 【资料】app_account_standard部件应用账号管理需求    | 标准系统 | SIG_BscSoftSrv | [@jiang-xiaofeng](https://gitee.com/jiang-xiaofeng)       |
| I4QT4W | [账号子系统]【部件化专项】【os_account部件】部件标准化    | 标准系统 | SIG_BscSoftSrv | [@jiang-xiaofeng](https://gitee.com/jiang-xiaofeng)       |
| I4WV31 | 【部件化专项】启动子系统部件标准化       | 标准系统 | SIG_BscSoftSrv       | [@handyohos](https://gitee.com/handyohos)     |
| I4WTQK | 【新增特性】鼠标双击选字                           | 标准系统|SIG_ArkUI|[@qieqiewl](https://gitee.com/qieqiewl) |
| I4WTPE | 【新增规格】动画能力增强                          | 标准系统|SIG_ArkUI|[@qieqiewl](https://gitee.com/qieqiewl) |
| I4WTPG | 【新增规格】基础动画参数配置增强                           | 标准系统|SIG_ArkUI|[@qieqiewl](https://gitee.com/qieqiewl) |
| I4WTPH | 【新增规格】row 和column 容器的孩子节点支持  flex属性                           | 标准系统|SIG_ArkUI|[@qieqiewl](https://gitee.com/qieqiewl) |
| I4WTP2 | 【测试框架】HiTrace能力对接                          | 标准系统|SIG_ArkUI|[@qieqiewl](https://gitee.com/qieqiewl) |
| I4WTR9 | 【新增特性】焦点设置支持                           | 标准系统|SIG_ArkUI|[@qieqiewl](https://gitee.com/qieqiewl) |
| I4WTPC | 【部件化专项】ACE开发框架子系统部件标准化                           | 标准系统|SIG_ArkUI|[@qieqiewl](https://gitee.com/qieqiewl) |
| I4X0Z3 | 【部件化专项】【distributed_hardware_fwk部件】distributed_hardware_fwk部件标准化       | 标准系统 | SIG_DistributedHardwareManagement       | [@hwzhangchuang](https://gitee.com/hwzhangchuang)     |
| I4X0WN | 【部件专项化】【distributed_camera部件】distributed_camera部件标准化       | 标准系统 | SIG_DistributedHardwareManagement       | [@hwzhangchuang](https://gitee.com/hwzhangchuang)     |
| I4WXHW | 【部件化专项】升级服务子系统部件标准化       | 标准系统 | SIG_BscSoftSrv       | [@hughes802](https://gitee.com/hughes802)     |
| I4R9OS | 【window_manager】【新增特性】支持窗口装饰 | 标准系统 | SIG-Graphics | [@lz-230](https://gitee.com/lz-230) |
| I4R309 | 【window_manager】【新增规格】增强特性 | 标准系统 | SIG-Graphics | [@lz-230](https://gitee.com/lz-230) |
| I4R30G | 【window_manager】【新增特性】应用主窗口支持自由窗口显示 | 标准系统 | SIG-Graphics | [@lz-230](https://gitee.com/lz-230) |
| I4ZCG4 | 【部件化专项】图形图像子系统部件标准化 | 标准系统 | SIG-Graphics | [@lz-230](https://gitee.com/lz-230) |
| I4XXHF | 【SysCap】图形子系统支持SysCap机制 | 标准系统 | SIG-Graphics | [@lz-230](https://gitee.com/lz-230) |
| I4ZELE | 【部件化专项】窗口管理子系统部件标准化口管理子系统部件标准化 | 标准系统 | SIG-Graphics | [@lz-230](https://gitee.com/lz-230) |
| I4NJTS | [轻量级图形子系统]支持通用touch事件、list组件支持scrollbottom/scrolltop事件 | 轻量系统       | SIG_AppFramework         | [@piggyguy](https://gitee.com/piggyguy)               |
| I4NJTD | [轻量级图形子系统]list组件支持scrollbottom/scrolltop事件     | 轻量系统       | SIG_AppFramework         | [@piggyguy](https://gitee.com/piggyguy)               |
| I4OGF0 | 【资料】thermal_manager部件类资料需求                        | 标准系统       | SIG_HardwareMgr          | [@aqxyjay](https://gitee.com/aqxyjay)                 |
| I4OEQT | 【集成验证】不亮屏检测                                       | 标准系统       | SIG_HardwareMgr          | [@aqxyjay](https://gitee.com/aqxyjay)                 |
| I4P7EY | [标准系统]支持TS Runtime                         | 标准系统       | SIG_CompileRuntime       | [@huanghuijin](https://gitee.com/huanghuijin)         |
| I4P7F5 | [标准系统]支持LLDB命令窗口                       | 标准系统       | SIG_CompileRuntime       | [@huanghuijin](https://gitee.com/huanghuijin)         |
| I4P7EV | [标准系统]支持ts/js模块化编译                    | 标准系统       | SIG_CompileRuntime       | [@huanghuijin](https://gitee.com/huanghuijin)         |
| I4OGD1 | 【新增特性】【DMS】支持组件间跨设备的onCall调用              | 标准系统       | SIG_BasicSoftwareService | [@cangegegege](https://gitee.com/cangegegege)         |
| I4OGCY | 【新增特性】【AMS/框架】支持组件间跨设备的onCall调用         | 标准系统       | SIG_BasicSoftwareService | [@cangegegege](https://gitee.com/cangegegege)         |
| I4OGCX | 【新增特性】【任务管理】快照变化更新                         | 标准系统       | SIG_BasicSoftwareService | [@cangegegege](https://gitee.com/cangegegege)         |
| I4OGCW | 【新增特性】【任务管理】任务变化更新                         | 标准系统       | SIG_BasicSoftwareService | [@cangegegege](https://gitee.com/cangegegege)         |
| I4OGCV | 【新增特性】【任务管理】同步任务快照                         | 标准系统       | SIG_BasicSoftwareService | [@cangegegege](https://gitee.com/cangegegege)         |
| I4OGCU | 【新增特性】【任务管理】结束任务同步                         | 标准系统       | SIG_BasicSoftwareService | [@cangegegege](https://gitee.com/cangegegege)         |
| I4OGCT | 【新增特性】【任务管理】发起任务同步                         | 标准系统       | SIG_BasicSoftwareService | [@cangegegege](https://gitee.com/cangegegege)         |
| I4OGCS | 【新增特性】【任务管理】查询任务快照                         | 标准系统       | SIG_BasicSoftwareService | [@cangegegege](https://gitee.com/cangegegege)         |
| I4OGCP | 【新增特性】【DMS】跨设备组件权限校验                        | 标准系统       | SIG_BasicSoftwareService | [@cangegegege](https://gitee.com/cangegegege)         |
| I4OGCK | 【增强特性】框架等待分布式对象同步完成后返回迁移结果         | 标准系统       | SIG_BasicSoftwareService | [@cangegegege](https://gitee.com/cangegegege)         |
| I4OH99 | 【samgr】注册/查询本地系统服务权限控制                       | 标准系统       | SIG_BasicSoftwareService | [@cangegegege](https://gitee.com/cangegegege)         |
| I4TS0Z | 【新增】轻量系统samgr支持远程服务管理                            | 轻量系统      | SIG_BasicSoftwareService | [@cangegegege](https://gitee.com/cangegegege)         |
| I4OH96 | 【samgr】samgr资料                                           | 标准系统       | SIG_BasicSoftwareService | [@cangegegege](https://gitee.com/cangegegege)         |
| I4OH93 | 【device_profile】同步功能适配可信群组                       | 标准系统       | SIG_BasicSoftwareService | [@cangegegege](https://gitee.com/cangegegege)         |
| I4OGD7 | 【device_profile】deviceProfile资料                          | 标准系统       | SIG_BasicSoftwareService | [@cangegegege](https://gitee.com/cangegegege)         |
| I4PBBV | 【新增特性】事件耗时调用                                     | 标准系统 | SIG_ApplicationFramework | [@xzz_0810](https://gitee.com/xzz_0810)               |
| I4PD0O | 【特性增强】通知发送使能能力增强                             | 标准系统 | SIG_ApplicationFramework | [@sheilei](https://gitee.com/sheilei)                 |
| I4PBQ1 | 【增强特性】分布式通知能力支持dump命令                       | 标准系统 | SIG_ApplicationFramework | [@xzz_0810](https://gitee.com/xzz_0810)               |
| I4PBR0 | 【新增特性】支持其他设备的通知点击后在跨设备跳转             | 标准系统 | SIG_ApplicationFramework | [@xzz_0810](https://gitee.com/xzz_0810)               |
| I4PC2S | 【新增特性】公共事件支持多用户特性                           | 标准系统 | SIG_ApplicationFramework | [@lsq1474521181](https://gitee.com/lsq1474521181)     |
| I4PCHK | 【新增特性】C++/JS 客户端与服务端互通                        | 标准系统   | SIG_ApplicationFramework | [@lsq1474521181](https://gitee.com/lsq1474521181)     |
| I4PCS0 | 【新增特性】提供Ability启动停止方法                          | 标准系统   | SIG_ApplicationFramework | [@xuezhongzhu0810](https://gitee.com/xuezhongzhu0810) |
| I4PQ5F | 【资料】提供ZIDL部件新增/增强特性资料说明                    | 标准系统   | SIG_ApplicationFramework | [@xzz_0810](https://gitee.com/xzz_0810)               |
| I4PQ5N | 【增强特性】支持IAbilityController                           | 标准系统   | SIG_ApplicationFramework | [@xzz_0810](https://gitee.com/xzz_0810)               |
| I4PCNK | 【资料】提供运行管理新增/增强特性资料说明                    | 标准系统   | SIG_ApplicationFramework | [@xuezhongzhu](https://gitee.com/xuezhongzhu)         |
| I4PCPA | 【资料】提供环境变化新增/增强特性资料说明                    | 标准系统   | SIG_ApplicationFramework | [@xuezhongzhu](https://gitee.com/xuezhongzhu)         |
| I4PCV0 | 【资料】提供通用组件新增/增强特性资料说明                    | 标准系统   | SIG_ApplicationFramework | [@sheilei](https://gitee.com/sheilei)                 |
| I4PQ5X | 【增强特性】Extension接口整改                                | 标准系统   | SIG_ApplicationFramework | [@xzz_0810](https://gitee.com/xzz_0810)               |
| I4PCLY |【新增特性】对外接口权限校验验收|标准系统|SIG_ApplicationFramework|[@silent-dye](https://gitee.com/silent-dye)|
| I4PCPI |【增强特性】支持系统环境查询|标准系统|SIG_ApplicationFramework|[@xuezhongzhu](https://gitee.com/xuezhongzhu)|
| I4PCRG |【新增特性】提供Ability监听器|标准系统|SIG_ApplicationFramework|[@xuezhongzhu0810](https://gitee.com/xuezhongzhu0810)|
| I4PCRL |【新增特性】测试框架整体功能|标准系统|SIG_ApplicationFramework|[@xuezhongzhu0810](https://gitee.com/xuezhongzhu0810)|
| I4PCRO |【新增特性】测试框架需要提供如下查询相关的功能|标准系统|SIG_ApplicationFramework|[@xuezhongzhu0810](https://gitee.com/xuezhongzhu0810)|
| I4PCRQ |【新增特性】提供调度组件生命周期相关的功能|标准系统|SIG_ApplicationFramework|[@xuezhongzhu0810](https://gitee.com/xuezhongzhu0810)|
| I4PCRX |【新增特性】测试框架提供可以执行shell命令能力|标准系统|SIG_ApplicationFramework|[@xuezhongzhu0810](https://gitee.com/xuezhongzhu0810)|
| I4PCS6 |【新增特性】AA适配测试框架|标准系统|SIG_ApplicationFramework|[@xuezhongzhu0810](https://gitee.com/xuezhongzhu0810)|
| I4PCVU |【新增特性】通用组件call调用|标准系统|SIG_ApplicationFramework|[@sheilei](https://gitee.com/sheilei)|
| I4PKYA | 【新增特性】包命令行工具                                     | 标准系统   | SIG_ApplicationFramework | [@shuaytao](https://gitee.com/shuaytao)               |
| I4PKYS | 【新增特性】支持现有js查询接口的权限管控                     | 标准系统   | SIG_ApplicationFramework | [@shuaytao](https://gitee.com/shuaytao)               |
| I4PKYW | 【新增特性】支持现有js监听安装、卸载、更新状态变化接口的权限管控 | 标准系统   | SIG_ApplicationFramework | [@shuaytao](https://gitee.com/shuaytao)               |
| I4PKYX | 【新增特性】支持现有js清理缓存接口的权限管控                 | 标准系统   | SIG_ApplicationFramework | [@shuaytao](https://gitee.com/shuaytao)               |
| I4PKYY | 【新增特性】支持现有js使能/禁用应用/组件接口的权限管控       | 标准系统   | SIG_ApplicationFramework | [@shuaytao](https://gitee.com/shuaytao)               |
| I4PKYZ | 【新增特性】返回应用类型                                     | 标准系统   | SIG_ApplicationFramework | [@shuaytao](https://gitee.com/shuaytao)               |
| I4PKZ1 | 【新增特性】应用数据目标标签设置                             | 标准系统   | SIG_ApplicationFramework | [@shuaytao](https://gitee.com/shuaytao)               |
| I4PKYT | 【新增特性】支持现有js安装接口的权限管控 | 标准系统 | SIG_ApplicationFramework | [@shuaytao](https://gitee.com/shuaytao) |
| I4QA3D | 【增强特性】新增zlib解压、压缩数据native接口 | 标准系统 | SIG_ApplicationFramework | [@shuaytao](https://gitee.com/shuaytao) |
| I4SY5T | 【SysCap】标准系统支持SysCap机制 | 标准系统   | SIG_ApplicationFramework | [@shuaytao](https://gitee.com/shuaytao)               |
| I4Q9S6 | [内核子系统]【增强特性】支持内核接口融合    | 轻量系统 | SIG_Kernel | [@leonchan5](https://gitee.com/leonchan5)       |
| I4QESV | 【新增特性】设备可用状态上报性能跟踪   | 标准系统 | SIG_DistributedHardwareManagement | [@renguang1116](https://gitee.com/renguang1116)           |
| I4QEKZ | 【新增特性】支持用户态平台驱动接口                          | 标准系统 | SIG_Driver         | [@xie0812](https://gitee.com/xie0812)           |
| I4QEL1 | 【新增特性】【新增特性】支持基于FB显示架构的基础功能                          | 标准系统 | SIG_Driver         | [@xie0812](https://gitee.com/xie0812)           |
| I4QEL2 | 【增强特性】马达驱动模型能力增强                          | 标准系统 | SIG_Driver         | [@xie0812](https://gitee.com/xie0812)           |
| I4QT3S | 【新增特性】长时任务管理 | 标准系统 | SIG_BasicSoftwareService           | [@wangwenli_wolf](https://gitee.com/wangwenli_wolf)                  |
| I4QT3T | 【新增特性】长时任务规范 | 标准系统 | SIG_BasicSoftwareService           | [@wangwenli_wolf](https://gitee.com/wangwenli_wolf)                  |
| I4QT3U | 【新增特性】长时任务可维可测 | 标准系统 | SIG_BasicSoftwareService           | [@wangwenli_wolf](https://gitee.com/wangwenli_wolf)                  |
| I4QT3V | 【新增特性】长时任务相关资料文档 | 标准系统 | SIG_BasicSoftwareService           | [@wangwenli_wolf](https://gitee.com/wangwenli_wolf)                  |
| I4QT3W | 【新增特性】长时任务申请/注销 | 标准系统 | SIG_BasicSoftwareService           | [@wangwenli_wolf](https://gitee.com/wangwenli_wolf)                  |
| I4QU0O | 【新增特性】设备和系统相关状态检测 | 标准系统 | SIG_BasicSoftwareService           | [@wangwenli_wolf](https://gitee.com/wangwenli_wolf)                  |
| I4QU0P | 【新增特性】延迟任务调度 | 标准系统 | SIG_BasicSoftwareService           | [@wangwenli_wolf](https://gitee.com/wangwenli_wolf)                  |
| I4QU0R | 【新增特性】延迟任务后台管理 | 标准系统 | SIG_BasicSoftwareService           | [@wangwenli_wolf](https://gitee.com/wangwenli_wolf)                  |
| I4QU0S | 【新增特性】延迟任务可维可测 | 标准系统 | SIG_BasicSoftwareService           | [@wangwenli_wolf](https://gitee.com/wangwenli_wolf)                  |
| I4QU0T | 【新增特性】延迟任务适配PC多账户 | 标准系统 | SIG_BasicSoftwareService           | [@wangwenli_wolf](https://gitee.com/wangwenli_wolf)                  |
| I4U076 | 【SysCap】标准系统支持SysCap机制 | 标准系统 | SIG_BasicSoftwareService           | [@wangwenli_wolf](https://gitee.com/wangwenli_wolf)                  |
| I4R2Y1 | 【增强特性】提供定制框架js接口                               | 标准系统 | SIG_ApplicationFramework          | [@zhengbin5](https://gitee.com/zhengbin5)         |
| I4R2Y8 | 【新增特性】支持颜色模式限定词                                     | 标准系统 | SIG_ApplicationFramework          | [@jameshw](https://gitee.com/jameshw)         |
| I4R2YA | 【新增特性】新增资源管理NDK接口                                     | 标准系统 | SIG_ApplicationFramework          | [@jameshw](https://gitee.com/jameshw)         |
| I4R2YC | 【新增特性】资源overlay                                     | 标准系统 | SIG_ApplicationFramework          | [@jameshw](https://gitee.com/jameshw)         |
| I4R2MP | 【新增特性】时区数据编译                         | 标准系统 | SIG_ApplicationFramework          | [@mengjingzhimo](https://gitee.com/mengjingzhimo) |
| I4R2LF | 【新增特性】时区数据解析                         | 标准系统 | SIG_ApplicationFramework          | [@mengjingzhimo](https://gitee.com/mengjingzhimo) |
| I4R3FR | 【资料】全球化新增API资料更新                       | 标准系统 | SIG_ApplicationFramework          | [@mengjingzhimo](https://gitee.com/mengjingzhimo) |
| I4RD3H | 【liteos_m部件】增加支持POSIX接口                  | 轻量系统       | SIG_Kernel | [@leonchan5](https://gitee.com/leonchan5) |
| I4QEKY | 【新增特性】Audio支持模拟耳机设备                          | 标准系统 | SIG_Driver         | [@xie0812](https://gitee.com/xie0812)           |
| I4RTYX | 【新增特性】【接口】提供查询本机或者组网内其它设备的设备安全等级信息的接口 | 标准系统 | SIG_Security | [@zhirenx](https://gitee.com/zhirenx) |
| I4RTYW | 【新增特性】【服务】支持获取自己或者组网内其它设备的设备安全等级信息 | 标准系统 | SIG_Security | [@zhirenx](https://gitee.com/zhirenx) |
| I4RTYU | 【新增特性】【服务】支持被组网内其它设备查询自己的设备安全等级信息 | 标准系统 | SIG_Security | [@zhirenx](https://gitee.com/zhirenx) |
| I4RTYN | 【新增特性】【南向】支持OEM厂家接入设备安全等级模块 | 标准系统 | SIG_Security | [@zhirenx](https://gitee.com/zhirenx) |
| I4SY5E | 【packing_tool部件】支持打包工具将syscap二进制文件打包到hap包中 | 标准系统 | SIG_ApplicationFramework | [@shuaytao](https://gitee.com/shuaytao) |
| I4SY5G | 【bundle_manager部件】支持基于SysCap的应用安装 | 标准系统 | SIG_ApplicationFramework | [@shuaytao](https://gitee.com/shuaytao) |
| I4TNBV | 【新增规格】进程启动配置能力增强                                | 标准系统 | SIG_BscSoftSrv       | [@handyohos](https://gitee.com/handyohos)     |
| I4TNBL | 【新增特性】支持UHDF类进程按需启动                                | 标准系统 | SIG_BscSoftSrv       | [@handyohos](https://gitee.com/handyohos)     |
| I4TNBQ | 【SysCap】启动恢复子系统支持SysCap机制                                | 标准系统 | SIG_BscSoftSrv       | [@handyohos](https://gitee.com/handyohos)     |
| I4HAMD | 【data_share_ability】支持对数据访问方式的控制                    | 标准系统   | SIG_DataManagement | [@verystone](https://gitee.com/verystone)         |
| I4TJFZ | 【增强特性】DeviceAuth部件支持设备间互信关系认证的多用户隔离，使用指定系统用户下管理的互信关系进行认证                   | 标准系统   | SIG_Security | [@lvyuanmin](https://gitee.com/lvyuanmin)         |
| I4TJG1 | 【增强特性】DeviceAuth部件实现互信群组数据多实例，支持指定用户的数据查询                    | 标准系统   | SIG_Security | [@lvyuanmin](https://gitee.com/lvyuanmin)         |
| I4TSJE |  【新增规格】【face_auth】支持用户本地人脸录入   | 标准系统   | SIG_Security      | [@tianshi_liu](https://gitee.com/tianshi_liu)     |
| I4TSJY |  【新增规格】【face_auth】支持用户本地人脸认证   | 标准系统   | SIG_Security      | [@tianshi_liu](https://gitee.com/tianshi_liu)     |
| I4TSK7 |  【新增规格】【face_auth】支持用户本地人脸删除   | 标准系统   | SIG_Security      | [@tianshi_liu](https://gitee.com/tianshi_liu)     |
| I4TSKP |  【需求描述】独立需求跟踪人脸认证框架DFX相关需求   | 标准系统   | SIG_Security      | [@tianshi_liu](https://gitee.com/tianshi_liu)     |
| I4SAI0 |  【新增特性】提供DataTransitMgrLib部件，支持数据跨设备流转时的管控策略   | 标准系统   | SIG_Security      | [@wangyongzhong2](https://gitee.com/wangyongzhong2)     |
| I4H4FH |【distributed_kv_store】分布式数据库支持分类分级|标准系统|SIG_DataManagement|[@widecode](https://gitee.com/widecode)|
| I4H3M8 |【新增特性】分布式数据对象支持复杂类型|标准系统|SIG_DataManagement|[@widecode](https://gitee.com/widecode)|
| I4HAMD |【data_share_ability】支持对数据访问方式的控制|标准系统|SIG_DataManagement|[@mangtsang](https://gitee.com/mangtsang)|
| I4PO00 |【分布式RDB】数据同步需求|标准系统|SIG_DataManagement|[@mangtsang](https://gitee.com/mangtsang)|
| I4OTW6 |【distributed_kv_store】分布式数据库Query支持InKeys谓词|标准系统|SIG_DataManagement|[@widecode](https://gitee.com/widecode)|
| I4TXSP |【SysCap】分布式数据管理子系统支持SysCap机制|标准系统|SIG_DataManagement|[@widecode](https://gitee.com/widecode)|
| I4TTK5 |【新增特性】支持磁盘管理查询的特性|标准系统|SIG_Kernel|[@panqinxu](https://gitee.com/panqinxu)|
| I4TTJV |【新增特性】支持卷信息查询和管理特性|标准系统|SIG_Kernel|[@panqinxu](https://gitee.com/panqinxu)|
| I4TTJN |【新增特性】支持外卡设备相关事件分发特性|标准系统|SIG_Kernel|[@panqinxu](https://gitee.com/panqinxu)|
| I4TTJJ |【资料】storage_manag   er部件资料需求|标准系统|SIG_Kernel|[@panqinxu](https://gitee.com/panqinxu)|
| I4TTHQ |【新增特性】支持外部存储访问需求|标准系统|SIG_Kernel|[@panqinxu](https://gitee.com/panqinxu)|
| I4TTHF |【新增特性】支持外卡上下线管理特性|标准系统|SIG_Kernel|[@panqinxu](https://gitee.com/panqinxu)|
| I4TTGR |【新增特性】【storage_manager部件】文件加密特性使能|标准系统|SIG_Kernel|[@panqinxu](https://gitee.com/panqinxu)|
| I4TTH9 |【新增特性】【storage_manager部件】CE密钥生命周期管理|标准系统|SIG_Kernel|[@panqinxu](https://gitee.com/panqinxu)|
| I4TT7Y |【新增特性】【storage_manager部件】文件加密特性对外接口|标准系统|SIG_Kernel|[@panqinxu](https://gitee.com/panqinxu)|
| I4SNSU |【新增特性】支持应用沙箱隔离能力|标准系统|SIG_Kernel|[@panqinxu](https://gitee.com/panqinxu)|
| I4TTM7 |【新增特性】支持设备间的sendfile能力|标准系统|SIG_Kernel|[@panqinxu](https://gitee.com/panqinxu)|
| I4TTOU |【新增特性】支持提供用户态跨设备分享接口能力规格|标准系统|SIG_Kernel|[@panqinxu](https://gitee.com/panqinxu)|
| I4TTOP |【新增特性】支持建立本地文件与分布式文件的映射规格|标准系统|SIG_Kernel|[@panqinxu](https://gitee.com/panqinxu)|
| I4TTOJ |【新增特性】为数据标签访问提供应用接口|标准系统|SIG_Kernel|[@panqinxu](https://gitee.com/panqinxu)|
| I4TTOF |【新增特性】支持异账号能力规格|标准系统|SIG_Kernel|[@panqinxu](https://gitee.com/panqinxu)|
| I4TTNG |【新增特性】支持数据分类设备分级，控制数据流转规格|标准系统|SIG_Kernel|[@panqinxu](https://gitee.com/panqinxu)|
| I4TTN8 |【新增特性】支持分布式文件系统的基础功能|标准系统|SIG_Kernel|[@panqinxu](https://gitee.com/panqinxu)|
| I4TTMN |【新增特性】支持应用包名级权限配置|标准系统|SIG_Kernel|[@panqinxu](https://gitee.com/panqinxu)|
| I4TT8L |【新增规格】HUKS提供三段式密钥管理接口|标准系统|SIG_Security|[@chaos-liang](https://gitee.com/Chaos-Liang)|
| I4TT8P |【新增规格】HUKS 架构优化，提供抽象统一的HAL层。|标准系统|SIG_Security|[@chaos-liang](https://gitee.com/Chaos-Liang)|
| I4TT8Z |【新增规格】HUKS支持多用户隔离|标准系统|SIG_Security|[@chaos-liang](https://gitee.com/Chaos-Liang)|
| I4S5RB |【新增特性】PKI应用签名工具支持生成Profile签名调试/发布证书|标准系统| SIG_Security | [@zhiwei-liu](https://gitee.com/zhiwei-liu)|
| I4S5R7 |【新增特性】PKI应用签名工具支持生成应用调试/发布证书|标准系统| SIG_Security | [@zhiwei-liu](https://gitee.com/zhiwei-liu)|
| I4S5RC |【新增特性】PKI应用签名工具支持Profile文件签名|标准系统| SIG_Security | [@zhiwei-liu](https://gitee.com/zhiwei-liu)|
| I4S5QZ |【新增特性】PKI应用签名工具支持Hap包签名|标准系统| SIG_Security | [@zhiwei-liu](https://gitee.com/zhiwei-liu)|
| I4U08D | [语言编译运行时]【SysCap】语言编译器运行时子系统支持SysCap  | 标准系统 | SIG_CompileRuntime       | [@huanghuijin]()         |
| I4P7F7 | [语言编译运行时，图形图像，DRF]NDK整体集成 | 标准系统 | SIG_CompileRuntime       | [@huanghuijin]()         |
| I4QQ1E | [语言编译运行时]【新增规格】Pandafile模块中zlib替换miniz | 标准系统 | SIG_CompileRuntime       | [@huanghuijin]()         |
| I4TMTO | [语言编译运行时]【c_cpp_runtime部件】动态库卸载 | 标准系统 | SIG_CompileRuntime       | [@huanghuijin]()         |
| I4U73N |【SysCap】标准系统支持SysCap机制|标准系统|SIG_Kernel|[@panqinxu](https://gitee.com/panqinxu)|
| I4Q6AQ |【【新增特性】Watchdog机制标准系统|标准系统|SIG_BasicSoftwareService|[@guochuanqi](https://gitee.com/guochuanqi)|
| I4Q6AP |【新增特性】支持JS app性能分析信息调试调优能力|标准系统|SIG_BasicSoftwareService|[@guochuanqi](https://gitee.com/guochuanqi)|
| I4Q6AN |【新增特性】：命令行调试通道|标准系统|SIG_BasicSoftwareService|[@guochuanqi](https://gitee.com/guochuanqi)|
| I4PJE6 |【【新增特性】支持JS app内存信息调试调优能力|标准系统|SIG_BasicSoftwareService|[@guochuanqi](https://gitee.com/guochuanqi)|
| I4PJE5 |【新增特性】支持JS app native内存信息调试调优能力|标准系统|SIG_BasicSoftwareService|[@guochuanqi](https://gitee.com/guochuanqi)|
| I4PJDO |【新增特性】hungtask卡死-内核hungtask监控D状态进程|标准系统|SIG_BasicSoftwareService|[@guochuanqi](https://gitee.com/guochuanqi)|
| I4PJDN |【新增特性】SCREEN ON卡死-不亮屏故障卡死|标准系统|SIG_BasicSoftwareService|[@guochuanqi](https://gitee.com/guochuanqi)|
| I4PJDP |【新增特性】Power按键-长按、短按Power按键事件上报|标准系统|SIG_BasicSoftwareService|[@guochuanqi](https://gitee.com/guochuanqi)|
| I4PJDM |【新增特性】INIT卡死-init长时间不执行|标准系统|SIG_BasicSoftwareService|[@guochuanqi](https://gitee.com/guochuanqi)|
| I4Q6AR |【新增特性】鸿蒙芯片维测框架|标准系统|SIG_BasicSoftwareService|[@guochuanqi](https://gitee.com/guochuanqi)|
| I4Q6AZ |【资料】hilog部件的js api需求，kmsg支持需求，init日志支持需求|标准系统|SIG_BasicSoftwareService|[@guochuanqi](https://gitee.com/guochuanqi)|
| I4Q6B2 |【新增特性】hilog支持开机阶段的日志打印和保存|标准系统|SIG_BasicSoftwareService|[@guochuanqi](https://gitee.com/guochuanqi)|
| I4Q6B4 |【新增特性】hilog支持js接口|标准系统|SIG_BasicSoftwareService|[@guochuanqi](https://gitee.com/guochuanqi)|
| I4Q6BA |【增强特性】支持HiLog关联traceid|标准系统|SIG_BasicSoftwareService|[@guochuanqi](https://gitee.com/guochuanqi)|
| I4Q6B9 |【增强特性】支持HiSysEvent关联traceid|标准系统|SIG_BasicSoftwareService|[@guochuanqi](https://gitee.com/guochuanqi)|
| I4Q6B7 |【增强特性】支持HiAppEvent关联traceid|标准系统|SIG_BasicSoftwareService|[@guochuanqi](https://gitee.com/guochuanqi)|
| I4Q6B6 |【增强特性】支持HiTrace JS接口|标准系统|SIG_BasicSoftwareService|[@guochuanqi](https://gitee.com/guochuanqi)|
| I4U0JZ |【新增特性】供鸿蒙hisysevent系统事件管理|标准系统|SIG_BasicSoftwareService|[@guochuanqi](https://gitee.com/guochuanqi)|
| I4PUKP |【新增特性】hisysevent订阅接口支持TAG方式订阅事件|标准系统|SIG_BasicSoftwareService|[@guochuanqi](https://gitee.com/guochuanqi)|
| I4U0KL |【SysCap】DFX子系统支持SysCap机制|标准系统|SIG_BasicSoftwareService|[@guochuanqi](https://gitee.com/guochuanqi)|
| I4U0KP |【profiler部件】cpu profiler功能|标准系统|SIG_BasicSoftwareService|[@guochuanqi](https://gitee.com/guochuanqi)|
| I4U89V |【新增】驱动/输入驱动XTS用例|轻量系统|compatibility|[@jiyong](https://gitee.com/jiyong)|
| I4U8I3 |【新增】智能开关面板样例|轻量系统|SIG_Kernel|[@kkup180](https://gitee.com/kkup180)|
| I4U8KB |【新增】驱动/显示驱动适配|轻量系统|SIG_Driver|[@zianed](https://gitee.com/zianed)|
| I4U8LZ |【新增】驱动/显示驱动XTS用例|轻量系统|compatibility|[@jiyong](https://gitee.com/jiyong)|
| I4U8N4 |【新增】驱动/输入驱动适配|轻量系统|SIG_Driver|[@zianed](https://gitee.com/zianed)|
| I4U8O1 |【新增】芯片架构SoC与Board解耦端到端联调|轻量系统|SIG_Kernel|[@kkup180](https://gitee.com/kkup180)|
| I4U8VP |【新增】编译构建/Module rules 编译构建流程适配SoC与Board分离机制|轻量系统|SIG_Kernel|[@kkup180](https://gitee.com/kkup180)|
| I4U8WL |【新增】硬件芯片/hisilico跟随SoC与Board分离机制进行调整|轻量系统|SIG_DevBoard|[@northking-super](https://gitee.com/northking-super)|
| I4S878 |【新增】用户程序框架/轻设备包管理 XTS用例|轻量系统|compatibility|[@jiyong](https://gitee.com/jiyong)|
| I4TY9D |【新增】 轻量系统图形/UI组件和图形基础组件 XTS用例|轻量系统|compatibility|[@jiyong](https://gitee.com/jiyong)|
| I4TFTB |【关联】轻量系统新增HCS宏式解析接口|轻量系统|SIG_Driver|[@fx_zhang](https://gitee.com/fx_zhang)|
| I4T1JA |【新增】轻量系统分布式软总线/分布式软总线 XTS用例|轻量系统|compatibility|[@jiyong](https://gitee.com/jiyong)|
| I4TS0Z |【新增】轻量系统samgr支持远程服务管理|轻量系统|SIG_DistributedSchedule|[@zjucx](https://gitee.com/zjucx)|
| I4RXQ3 | [内核子系统]【新增特性】内存管理基础特性     | 标准系统 | SIG_Kernel | [@liuyoufang](https://gitee.com/liuyoufang)       |
| I4TEGS | [内核子系统]【新增特性】F2FS末端性能优化     | 标准系统 | SIG_Kernel | [@liuyoufang](https://gitee.com/liuyoufang)       |
| I4SRVK | [内核子系统]【新增特性】支持CPU轻量级隔离特性     | 标准系统 | SIG_Kernel | [@liuyoufang](https://gitee.com/liuyoufang)       |
| I4SE2N | [内核子系统]【新增特性】支持按照用户维度进行内存资源管控的能力     | 标准系统 | SIG_Kernel | [@liuyoufang](https://gitee.com/liuyoufang)       |
| I4T402 | SR000GRI6M: 【SysCap】标准系统支持SysCap机制 | 标准系统 | SIG_ApplicationFramework | [@zero-cyc](https://gitee.com/zero-cyc) |
| I4TEF8 | aafwk模块添加syscap字段信息 | 标准系统 | SIG_ApplicationFramework | @[guyuanzhang](https://gitee.com/guyuanzhang) |
| I4STSP | 支持灭屏、解锁场景应用生命周期变化 | 标准系统 | SIG_ApplicationFramework | @[jiangwensai](https://gitee.com/jiangwensai) |
| I4T8CK | 常驻进程启动默认组件 | 标准系统 | SIG_ApplicationFramework | @[zhoujun62](https://gitee.com/zhoujun62) |
| I4RV2A | extension读写权限配置 | 标准系统 | SIG_ApplicationFramework | @[zhoujun62](https://gitee.com/zhoujun62) |
| I4S8X4 | Uri权限动态授权 | 标准系统 | SIG_ApplicationFramework | @[altay](https://gitee.com/altay) |
| I4U457 | Uri权限校验接口 | 标准系统 | SIG_ApplicationFramework | @[altay](https://gitee.com/altay) |
| I4UI3X | Uri权限生命周期管理 | 标准系统 | SIG_ApplicationFramework | @[xzz_0810](https://gitee.com/xzz_0810) |
| I4TYDO | 【新增规格】设备下线时的token信息删除    | 标准系统 | SIG_Security | [@jiang-xiaofeng](https://gitee.com/jiang-xiaofeng)       |
| I4TYCK | 【新增规格】分布式权限校验接口和机制    | 标准系统 | SIG_Security | [@jiang-xiaofeng](https://gitee.com/jiang-xiaofeng)       |
| I4TYE7 | 【SysCap】标准系统支持SysCap机制    | 标准系统 | SIG_Security | [@jiang-xiaofeng](https://gitee.com/jiang-xiaofeng)       |
| I4IU5G | [帐号子系统]支持本地多用户辅助管理工具    | 标准系统 | SIG_BscSoftSrv | [@jiang-xiaofeng](https://gitee.com/jiang-xiaofeng)       |
| I4IU51 | [帐号子系统]本地多用户基础信息约束    | 标准系统 | SIG_BscSoftSrv | [@jiang-xiaofeng](https://gitee.com/jiang-xiaofeng)       |
| I4IU4D | [帐号子系统]支持本地多用户接口权限检查及服务访问约束    | 标准系统 | SIG_BscSoftSrv | [@jiang-xiaofeng](https://gitee.com/jiang-xiaofeng)       |
| I4TXW3 | 【SysCap】账号子系统支持SysCap机制    | 标准系统 | SIG_BscSoftSrv | [@jiang-xiaofeng](https://gitee.com/jiang-xiaofeng)       |
| I4TYET | 【新增规格】提供parameter的selinux标签设置接口库    | 标准系统 | SIG_Security | [@jiang-xiaofeng](https://gitee.com/jiang-xiaofeng)       |
| I4TIWQ | 【SysCap】USB服务子系统支持SysCap机制    | 标准系统 | SIG_Driver         | [@xie0812](https://gitee.com/xie0812)           |
| I4TJG3 | 【增强特性】DeviceAuth部件支持帐号无关点对点信任关系建立、解除的多用户数据隔离                  | 标准系统   | SIG_Security | [@lvyuanmin](https://gitee.com/lvyuanmin)         |
| I4QELC | 【新增特性】【HDF框架】支持UHDF类进程按需启动                          | 标准系统 | SIG_Driver         | [@xie0812](https://gitee.com/xie0812)           |
| I4QEL5 | 【DFX】USB DFX实现                          | 标准系统 | SIG_Driver         | [@xie0812](https://gitee.com/xie0812)           |
| I4QEL6 | 【新增特性】USB Port功能实现                          | 标准系统 | SIG_Driver         | [@xie0812](https://gitee.com/xie0812)           |
| I4U5WZ | 【测试框架】控件树dump能力特性增强                           | 标准系统               | SIG_ApplicationFramework          | [@zcdqs](https://gitee.com/zcdqs) |
| I4U5XM | 【新增规格】ACE Loader支持JS文件条件编译能力                 | 标准系统               | SIG_ApplicationFramework          | [@qieqiewl](https://gitee.com/qieqiewl) |
| I4U0L8 | 【SysCap】分布式标准系统支持SysCap机制                   | 标准系统               | SIG_SoftBus                       | [@Xi_Yuhao](https://gitee.com/Xi_Yuhao) |
| I4WVOC | 【新增特性】分布式硬件使能/去使能                   | 标准系统               | SIG_DistributedHardwareManagement                       | [@hwzhangchuang](https://gitee.com/hwzhangchuang) |
| I4WVO0 | 【新增特性】分布式硬件部件配置和动态加载                   | 标准系统               | SIG_DistributedHardwareManagement                       | [@hwzhangchuang](https://gitee.com/hwzhangchuang) |
| I4WVNF | 【新增特性】分布式硬件上下线管理                   | 标准系统               | SIG_DistributedHardwareManagement                       | [@hwzhangchuang](https://gitee.com/hwzhangchuang) |
| I4WVMX | 【新增特性】分布式硬件接入管理                   | 标准系统               | SIG_DistributedHardwareManagement                       | [@hwzhangchuang](https://gitee.com/hwzhangchuang) |
| I4WVLU | 【新增特性】分布式硬件版本管理                   | 标准系统               | SIG_DistributedHardwareManagement                       | [@hwzhangchuang](https://gitee.com/hwzhangchuang) |
| I4WTQN | 【新增特性】新增RichText标签                           | 标准系统|SIG_ArkUI|[@qieqiewl](https://gitee.com/qieqiewl) |
| I4WTPV | 【新增规格】Image组件新增分布式图片路径加载能力                          | 标准系统|SIG_ArkUI|[@qieqiewl](https://gitee.com/qieqiewl) |
| I4WTQP | 【新增特性】拖拽手势支持跨窗口拖拽特性                           | 标准系统|SIG_ArkUI|[@qieqiewl](https://gitee.com/qieqiewl) |
| I4WTR3 | 【新增特性】富文本组件支持                           | 标准系统|SIG_ArkUI|[@qieqiewl](https://gitee.com/qieqiewl) |
| I4WTR4 | 【新增特性】分布式状态管理特性                           | 标准系统|SIG_ArkUI|[@qieqiewl](https://gitee.com/qieqiewl) |
| I4WTRC | 【新增特性】组件状态数据分布式迁移支持                           | 标准系统|SIG_ArkUI|[@qieqiewl](https://gitee.com/qieqiewl) |
| I4WWRN | 【msdp】支持设备皮套开合事件订阅    | 标准系统 | SIG_DistributedHardwareManagement | [@mayunteng_1](https://gitee.com/mayunteng_1)       |
| I4WWRR | 【多模】JS API性能 | 标准系统 | SIG_DistributedHardwareManagement | [@hhh2](https://gitee.com/hhh2) |
| I4WWRT | 【多模】注入工具 | 标准系统 | SIG_DistributedHardwareManagement | [@hhh2](https://gitee.com/hhh2) |
| I4WWRV | 【多模】ANR检测 | 标准系统 | SIG_DistributedHardwareManagement | [@hhh2](https://gitee.com/hhh2) |
| I4WWTB | 【泛sensor】Sensor支持周边依赖 | 标准系统 | SIG_DistributedHardwareManagement | 标准系统 | SIG_DistributedHardwareManagement | [@hhh2](https://gitee.com/hhh2) |
| I4WWTB | 【泛sensor】Miscdevice支持周边依赖 | 标准系统 | SIG_DistributedHardwareManagement | 标准系统 | SIG_DistributedHardwareManagement | [@hhh2](https://gitee.com/hhh2) |
| I4X49M | 【新增特性】设备管理应用开发框架 | 标准系统 | SIG_ApplicationFramework          | [@jameshw](https://gitee.com/jameshw)         |
| I4X49T | 【新增特性】企业设备管理服务基本能力 | 标准系统 | SIG_ApplicationFramework          | [@jameshw](https://gitee.com/jameshw)         |
| I4X49Z | 【新增特性】设置系统时间 | 标准系统 | SIG_ApplicationFramework          | [@jameshw](https://gitee.com/jameshw)         |
| I4X4A5 | 【资料】EDM API资料 | 标准系统 | SIG_ApplicationFramework          | [@jameshw](https://gitee.com/jameshw)         |
| I4X4AF | 【新增特性】DA业务发放能力 | 标准系统 | SIG_ApplicationFramework          | [@jameshw](https://gitee.com/jameshw)         |
| I4XGLQ | 【新增特性】UI随机压测工具 | 标准系统 | SIG_WuKong          | [@dwq](https://gitee.com/currydavids)         |
| I4R30D | 【window_manager】【新增特性】应用主窗口支持自由窗口显示 | 标准系统 | SIG-Graphics | [@lz-230](https://gitee.com/lz-230) |
| I4R30F | 【window_manager】【新增特性】应用主窗口支持自由窗口显示 | 标准系统 | SIG-Graphics | [@lz-230](https://gitee.com/lz-230) |
| I4R9OT | 【window_manager】【新增特性】支持窗口装饰 | 标准系统 | SIG-Graphics | [@lz-230](https://gitee.com/lz-230) |
| I4R9OZ | 【window_manager】【新增规格】增强特性 | 标准系统 | SIG-Graphics | [@lz-230](https://gitee.com/lz-230) |
| I4R9P0 | 【window_manager】【新增规格】增强特性：提供Display管理能力 | 标准系统 | SIG-Graphics | [@lz-230](https://gitee.com/lz-230) |
| I4R9P2 | 【window_manager】【新增规格】增强特性：提供Display管理能力 | 标准系统 | SIG-Graphics | [@lz-230](https://gitee.com/lz-230) |
| I4R302 | 【window_manager】【新增特性】支持窗口效果 | 标准系统 | SIG-Graphics | [@lz-230](https://gitee.com/lz-230) |
| I4R303 | 【window_manager】【新增特性】支持窗口动画 | 标准系统 | SIG-Graphics | [@lz-230](https://gitee.com/lz-230) |
| I4R308 | 【window_manager】【新增规格】增强特性：提供应用窗口创建管理能力 | 标准系统 | SIG-Graphics | [@lz-230](https://gitee.com/lz-230) |
| I4R30B | 【window_manager】【新增规格】增强特性：提供应用窗口创建管理能力 | 标准系统 | SIG-Graphics | [@lz-230](https://gitee.com/lz-230) |
| I4R30H | 【window_manager】【新增特性】应用主窗口支持自由窗口显示 | 标准系统 | SIG-Graphics | [@lz-230](https://gitee.com/lz-230) |
| I4RKT5 | 【render_service部件】【新增特性】新增RenderService支持自绘制通路特性 | 标准系统 | SIG-Graphics | [@lz-230](https://gitee.com/lz-230) |
| I4ZEL9 | 【window_manager】【新增规格】增强特性：提供Display管理能力 | 标准系统 | SIG-Graphics | [@lz-230](https://gitee.com/lz-230) |
| I4ZEIW | 【window_manager】【新增特性】支持亮屏灭屏流程 | 标准系统 | SIG-Graphics | [@lz-230](https://gitee.com/lz-230) |
| I4R9P9 | 【animation部件】支持窗口动画 | 标准系统 | SIG-Graphics | [@lz-230](https://gitee.com/lz-230) |
| I4RKT3 | 【composer部件】提供合成和送显的能力 | 标准系统 | SIG-Graphics | [@lz-230](https://gitee.com/lz-230) |
| I4R9PA | 【composer部件】【新增特性 显示设备管理】vsync管理 | 标准系统 | SIG-Graphics | [@lz-230](https://gitee.com/lz-230) |
| I4RKSP | 【effect部件】【新增特性 Render Effect】提供窗口级非实时模糊特效 | 标准系统 | SIG-Graphics | [@lz-230](https://gitee.com/lz-230) |
| I4RKSN | 【effect部件】【新增特性 Image Effect】提供饱和度，对比度，亮度算法组件 | 标准系统 | SIG-Graphics | [@lz-230](https://gitee.com/lz-230) |
| I4RKSO | 【effect部件】【新增特性Image Effect】提供图片效果处理框架 | 标准系统 | SIG-Graphics | [@lz-230](https://gitee.com/lz-230) |
| I4OGLE | 【资料】batterystatistic部件资料需求         | 标准系统     | SIG_HardwareMgr          | [@aqxyjay](https://gitee.com/aqxyjay)                 |
| I40IRO | 【系统电源管理服务】 支持休眠和混合睡眠模式  | 标准系统     | SIG_HardwareMgr          | [@aqxyjay](https://gitee.com/aqxyjay)                 |
| I4OGD4 | 【资料】跨设备任务迁移新增/增强特性资料说明  | 标准系统     | SIG_BasicSoftwareService | [@cangegegege](https://gitee.com/cangegegege)         |
| I4OGCZ | 【资料】跨设备组件oncall调用新增特性资料说明 | 标准系统     | SIG_BasicSoftwareService | [@cangegegege](https://gitee.com/cangegegege)         |
| I4PCLE |【新增特性】应用环境创建和管理优化|标准系统|SIG_ApplicationFramework|[@silent-dye](https://gitee.com/silent-dye)|
| I4PCLJ |【新增特性】应用启动功耗优化|标准系统|SIG_ApplicationFramework|[@silent-dye](https://gitee.com/silent-dye)|
| I4PCLU |【新增特性】对外接口性能验收|标准系统|SIG_ApplicationFramework|[@silent-dye](https://gitee.com/silent-dye)|
| I4PCMC |【新增特性】应用启动性能优化|标准系统|SIG_ApplicationFramework|[@silent-dye](https://gitee.com/silent-dye)|
| I4PKY4 | 【showcase特性】DBMS启动与退出               | 标准系统 | SIG_ApplicationFramework | [@shuaytao](https://gitee.com/shuaytao)               |
| I4PKY5 | 【showcase特性】DBMS异常退出的恢复           | 标准系统 | SIG_ApplicationFramework | [@shuaytao](https://gitee.com/shuaytao)               |
| I4PKY6 | 【showcase特性】跨设备获取icon和label        | 标准系统 | SIG_ApplicationFramework | [@shuaytao](https://gitee.com/shuaytao)               |
| I4PKY9 | 【资料】包命令行工具资料说明                 | 标准系统 | SIG_ApplicationFramework | [@shuaytao](https://gitee.com/shuaytao)               |
| I4PKYC | 【资料】config.json配置文件字段说明          | 标准系统 | SIG_ApplicationFramework | [@shuaytao](https://gitee.com/shuaytao)               |
| I4PKYJ | 【资料】提供包管理服基本功能的资料说明       | 标准系统 | SIG_ApplicationFramework | [@shuaytao](https://gitee.com/shuaytao)               |
| I4Q9SU | [内核子系统]【增强特性】支持北向接口融合   | 标准系统 | SIG_Kernel | [@leonchan5](https://gitee.com/leonchan5)       |
| I4QEL3 | 【资料】驱动子系统资料刷新                          | 标准系统 | SIG_Driver         | [@xie0812](https://gitee.com/xie0812)           |
| I4QEL4 | 【资料】USB子系统文档资料                          | 标准系统 | SIG_Driver         | [@xie0812](https://gitee.com/xie0812)           |
| I4QT3X | 【新增特性】支持日历类及延迟提醒功能 | 标准系统 | SIG_BasicSoftwareService           | [@wangwenli_wolf](https://gitee.com/wangwenli_wolf)                  |
| I4RTYQ |【资料】DSLM部件设备安全等级凭据格式开放和交换协议开放需求| 标准系统 | SIG_Security | [@zhirenx](https://gitee.com/zhirenx) |
| I4RGFY | 【DataShare】基于ExtensionAbility新框架重构并提供单设备上跨应用数据共享能力                    | 标准系统   | SIG_DataManagement | [@verystone](https://gitee.com/verystone)         |
| I4QU0U | 【新增特性】延迟任务相关资料文档 | 标准系统 | SIG_BasicSoftwareService           | [@wangwenli_wolf](https://gitee.com/wangwenli_wolf)                  |
| I4T9KH |【资料】PKI应用签名工具资料需求|标准系统| SIG_Security | [@zhiwei-liu](https://gitee.com/zhiwei-liu)|
| I4UTCF | 【新增特性】进程分组及并行启动基础框架   | 标准系统 | SIG_BscSoftSrv| [@handyohos](https://gitee.com/handyohos) |
| I4UTCM | 【新增规格】【新增特性】进程分组启动支持整机不同的启动功能   | 标准系统 | SIG_BscSoftSrv| [@handyohos](https://gitee.com/handyohos) |
| I4UUUU | 【新增规格】DEMO测试，提供密钥管理全能力集的测试DEMO | 标准系统 | SIG_Security | [@chaos-liang](https://gitee.com/Chaos-Liang) |
| I4TYFR | 【新增规格】HUKS在删除应用的情况下，HUKS需要删除相关的密钥数据 | 标准系统 | SIG_Security | [@chaos-liang](https://gitee.com/Chaos-Liang) |
| I4TYFI | 【新增规格】HUKS在删除子用户情况下，需要删除相关的密钥数据 | 标准系统 | SIG_Security | [@chaos-liang](https://gitee.com/Chaos-Liang) |
| I4TYFA | 【新增规格】HUKS支持密钥应用基于APP UID的访问隔离 | 标准系统 | SIG_Security | [@chaos-liang](https://gitee.com/Chaos-Liang) |
| I4TYF1 | 【新增规格】HUKS支持key attestation和id attestation. | 标准系统 | SIG_Security | [@chaos-liang](https://gitee.com/Chaos-Liang) |
| I4TYEM | 【新增规格】HUKS支持安全等级凭据的导入签发及验证 | 标准系统 | SIG_Security | [@chaos-liang](https://gitee.com/Chaos-Liang) |
| I4H4FR |【distributed_kv_store】支持多用户数据隔离和共享|标准系统|SIG_DataManagement|[@widecode](https://gitee.com/widecode)|
| I4RGFY |【DataShare】基于ExtensionAbility新框架重构并提供单设备上跨应用数据共享能力|标准系统|SIG_DataManagement|[@widecode](https://gitee.com/widecode)|
| I4UZJ6 |【资料】提供分布式数据对象能力资料跟踪需求|标准系统|SIG_DataManagement|[@widecode](https://gitee.com/widecode)|
| I4UZK0 |【资料】RDB提供分布式关系型数据库|标准系统|SIG_DataManagement|[@mangtsang](https://gitee.com/mangtsang)|
| I4UZL4 |【资料】data_share提供对数据访问方式的控制|标准系统|SIG_DataManagement|[@mangtsang](https://gitee.com/mangtsang)|
| I4V038 | 【新增规格】实现通过应用权限管理界面设置应用权限    | 标准系统 | SIG_Security | [@jiang-xiaofeng](https://gitee.com/jiang-xiaofeng)       |
| I4V032 | 【新增规格】应用权限权限管理界面实现    | 标准系统 | SIG_Security | [@jiang-xiaofeng](https://gitee.com/jiang-xiaofeng)       |
| I4V02Y | 【新增规格】主体设备上应用卸载时同步    | 标准系统 | SIG_Security | [@jiang-xiaofeng](https://gitee.com/jiang-xiaofeng)       |
| I4V02P | 【DFX】Token信息的dump机制    | 标准系统 | SIG_Security | [@jiang-xiaofeng](https://gitee.com/jiang-xiaofeng)       |
| I4V02K | 【新增规格】主体设备上应用授权状态更新同步    | 标准系统 | SIG_Security | [@jiang-xiaofeng](https://gitee.com/jiang-xiaofeng)       |
| I4TYDA | 【新增规格】token信息跨设备同步    | 标准系统 | SIG_Security | [@jiang-xiaofeng](https://gitee.com/jiang-xiaofeng)       |
| I4TYCV | 【新增规格】设备上线时的native进程的token信息同步    | 标准系统 | SIG_Security | [@jiang-xiaofeng](https://gitee.com/jiang-xiaofeng)       |
| I4V03D | 【新增特性】支持SELinux开关的dump机制    | 标准系统 | SIG_Security | [@jiang-xiaofeng](https://gitee.com/jiang-xiaofeng)       |
| I4JBF2 | [账号子系统]os_account_standard部件分布式组网账号管理需求    | 标准系统 | SIG_BscSoftSrv | [@jiang-xiaofeng](https://gitee.com/jiang-xiaofeng)       |
| I4IU5W | [帐号子系统]os_account_standard部件本地多用户生命周期管理需求    | 标准系统 | SIG_BscSoftSrv | [@jiang-xiaofeng](https://gitee.com/jiang-xiaofeng)       |
| I4V74F | 【新增特性】【组网】拓扑管理    | 标准系统 | SIG_SoftBus | [@fanxiaoyu321](https://gitee.com/fanxiaoyu321)       |
| I4Q6B5 |【SR000GIILK:【资料】hitrace部件的js api需求|标准系统|SIG_BasicSoftwareService|[@guochuanqi](https://gitee.com/guochuanqi)|
| I4PJE4 |【SR000GI6P9:【资料】hiprofiler部件资料需求|标准系统|SIG_BasicSoftwareService|[@guochuanqi](https://gitee.com/guochuanqi)|
| I4WW3H | 【新增特性】支持分布式Camera使能和去使能 | 标准系统 | SIG_DistributedHardwareManagement | [@hwzhangchuang](https://gitee.com/hwzhangchuang) |
| I4WVZS | 【新增特性】支持通过分布式相机进行图像预览 | 标准系统 | SIG_DistributedHardwareManagement | [@hwzhangchuang](https://gitee.com/hwzhangchuang) |
| I4WVXW | 【新增特性】支持基于HDF实现分布式相机驱动 | 标准系统 | SIG_DistributedHardwareManagement | [@hwzhangchuang](https://gitee.com/hwzhangchuang) |
| I4WVW9 | 【新增特性】主控端相机控制参数支持传递到被控端生效 | 标准系统 | SIG_DistributedHardwareManagement | [@hwzhangchuang](https://gitee.com/hwzhangchuang) |
| I4WVVK | 【新增特性】支持通过分布式相机进行拍照 | 标准系统 | SIG_DistributedHardwareManagement | [@hwzhangchuang](https://gitee.com/hwzhangchuang) |
| I4WWS6 | 【多模】trace功能 | 标准系统 | SIG_DistributedHardwareManagement | [@hhh2](https://gitee.com/hhh2) |
| I4WWTB | 【资料】JS API资料 | 标准系统 | SIG_DistributedHardwareManagement | 标准系统 | SIG_DistributedHardwareManagement | [@hhh2](https://gitee.com/hhh2) |
| I4WWS7 | 【多模】inputMonitor JS API资料 | 标准系统 | SIG_DistributedHardwareManagement | [@hhh2](https://gitee.com/hhh2) |
| I4WWS8 | 【多模】inputDevice JS API资料 | 标准系统 | SIG_DistributedHardwareManagement | [@hhh2](https://gitee.com/hhh2) |
| I4WVOX | 【新增特性】分布式硬件管理资料                   | 标准系统               | SIG_DistributedHardwareManagement                       | [@hwzhangchuang](https://gitee.com/hwzhangchuang) |
| I4ZCG0 | 【backstore部件】提供SurfaceID以及工具类 | 标准系统 | SIG-Graphics | [@lz-230](https://gitee.com/lz-230) |
| I4ZCGG | 【drawing部件】提供图形NDK能力 | 标准系统 | SIG-Graphics | [@lz-230](https://gitee.com/lz-230) |
| I4ZCGC | 【广色域】【新增特性 图形支持广色域】提供图层，窗口的色彩管理 | 标准系统 | SIG-Graphics | [@lz-230](https://gitee.com/lz-230) |
| I4R9P6 | 【广色域】【新增特性 图形支持广色域】渲染支持色彩管理 | 标准系统 | SIG-Graphics | [@lz-230](https://gitee.com/lz-230) |
| I4R9P7 | 【广色域】【新增特性 图形支持广色域】投屏,合成支持色彩管理 | 标准系统 | SIG-Graphics | [@lz-230](https://gitee.com/lz-230) |
| I4R9P8 | 【广色域】【新增特性 图形支持广色域】提供色域描述，定义和单点色域转换工具类 | 标准系统 | SIG-Graphics | [@lz-230](https://gitee.com/lz-230) |
| I4P7F7 | [标准系统]提供Windows，linux，Mac多平台NDK | 标准系统 | SIG_CompileRuntime | [@huanghuijin](https://gitee.com/huanghuijin) |
| I4Q9F2 | [内核子系统]【新增特性】支持native动态加载机制   | 标准系统 | SIG_Kernel | [@leonchan5](https://gitee.com/leonchan5)       |
| I4Q9OQ | [内核子系统]【新增特性】支持Cortex-M55  | 标准系统 | SIG_Kernel | [@leonchan5](https://gitee.com/leonchan5)       |
| I4QEL7 | 【新增特性】EDP、HDMI屏幕支持；支持显示设备热插拔事件上报；支持查询显示设备相关信息；支持修改显示分辨率                          | 标准系统 | SIG_Driver         | [@xie0812](https://gitee.com/xie0812)           |
| I4QEL8 | 【新增特性】Audio支持录音缓存阈值上报、设备加载成功后事件上报                          | 标准系统 | SIG_Driver         | [@xie0812](https://gitee.com/xie0812)           |
| I4U76A | 【新增特性】基于HDF驱动框架提供计步器Sensor驱动能力                          | 标准系统 | SIG_Driver         | [@xie0812](https://gitee.com/xie0812)           |
| I4QT45 | 【新增特性】查询指定时间范围内的应用使用历史统计数据 | 标准系统 | SIG_BasicSoftwareService           | [@wangwenli_wolf](https://gitee.com/wangwenli_wolf)                  |
| I4QT46 | 【新增特性】查询指定时间范围内的应用事件集合 | 标准系统 | SIG_BasicSoftwareService           | [@wangwenli_wolf](https://gitee.com/wangwenli_wolf)                  |
| I4QU0G | 【新增特性】查询应用程序当前是否不常用应用 | 标准系统 | SIG_BasicSoftwareService           | [@wangwenli_wolf](https://gitee.com/wangwenli_wolf)                  |
| I4QU0I | 【新增特性】采集数据处理 | 标准系统 | SIG_BasicSoftwareService           | [@wangwenli_wolf](https://gitee.com/wangwenli_wolf)                  |
| I4QU0K | 【新增特性】配置信息变更更新 | 标准系统 | SIG_BasicSoftwareService           | [@wangwenli_wolf](https://gitee.com/wangwenli_wolf)                  |
| I4QU0M |  资料专项 | 标准系统 | SIG_BasicSoftwareService           | [@wangwenli_wolf](https://gitee.com/wangwenli_wolf)                  |
| I4UTC6 | 【新增规格】系统进程运行环境沙盒构建   | 标准系统 | SIG_BscSoftSrv| [@handyohos](https://gitee.com/handyohos) |
| I4UTCO | 【增强特性】支持app进程孵化能力增强   | 标准系统 | SIG_BscSoftSrv| [@handyohos](https://gitee.com/handyohos) |
| I4UTCY | 【增强特性】appspawn支持孵化的应用进程回收   | 标准系统 | SIG_BscSoftSrv| [@handyohos](https://gitee.com/handyohos) |
| I4UTD0 | 【资料】init部件南向文档需求   | 标准系统 | SIG_BscSoftSrv| [@handyohos](https://gitee.com/handyohos) |
| I4U27N | 【新增特性】提供获取RawFileDescriptor的js接口                                     | 标准系统 | SIG_ApplicationFramework          | [@jameshw](https://gitee.com/jameshw)         |
| I4VMGZ | [内核子系统]【新增特性】支持基础FPS智能感知调度功能     | 标准系统 | SIG_Kernel | [@liuyoufang](https://gitee.com/liuyoufang)       |
| I4U089 | [内核子系统]【新增特性】内核调度支持绘帧线程优先供给机制     | 标准系统 | SIG_Kernel | [@liuyoufang](https://gitee.com/liuyoufang)       |
| I4V226 | 【资料】HUKS密钥管理开发指南和API接口说明 | 标准系统 | SIG_Security | [@chaos-liang](https://gitee.com/Chaos-Liang) |
| I4W1E4 | 【性能】AccessToken性能需求    | 标准系统 | SIG_Security | [@jiang-xiaofeng](https://gitee.com/jiang-xiaofeng)       |
| I4W1E0 | 【资料】AccessToken资料需求    | 标准系统 | SIG_Security | [@jiang-xiaofeng](https://gitee.com/jiang-xiaofeng)       |
| I4W7ZO | [语言编译器运行时]【新增特性】Runtime性能调优 | 标准系统 | SIG_CompileRuntime | [@huanghuijin](https://gitee.com/huanghuijin) |
| I4W7ZR | [语言编译器运行时]【新增规格】内存管理分配回收功能/HPP GC性能调优 | 标准系统 | SIG_CompileRuntime | [@huanghuijin](https://gitee.com/huanghuijin) |
| I4WWDA | [语言编译器运行时]【资料】语言编译器运行时资料刷新 | 标准系统 | SIG_CompileRuntime | [@huanghuijin](https://gitee.com/huanghuijin) |
| I4WWHD | [语言编译器运行时]【新增特性】TS benchmark 的设计与实现 | 标准系统 | SIG_CompileRuntime | [@huanghuijin](https://gitee.com/huanghuijin) |
| I4WWKK | [语言编译器运行时]【增强特性】Actor轻量化1.0 | 标准系统 | SIG_CompileRuntime | [@huanghuijin](https://gitee.com/huanghuijin) |
| I4WWMK | [语言编译器运行时]【资料】TS/JS语言基础库资料刷新 | 标准系统 | SIG_CompileRuntime | [@huanghuijin](https://gitee.com/huanghuijin) |
| I4WW76 | 【新增特性】支持分布式Screen的使能和去使能 | 标准系统 | SIG_DistributedHardwareManagement | [@hwzhangchuang](https://gitee.com/hwzhangchuang) |
| I4WW6U | 【新增特性】支持分布式Screen的镜像/扩展显示 | 标准系统 | SIG_DistributedHardwareManagement | [@hwzhangchuang](https://gitee.com/hwzhangchuang) |
| I4WW60 | 【新增特性】支持分布式Screen在被控端的显示 | 标准系统 | SIG_DistributedHardwareManagement | [@hwzhangchuang](https://gitee.com/hwzhangchuang) |
| I4X2EL | 【部件化专项】无障碍软件服务子系统部件标准化    | 标准系统 | SIG_BasicSoftwareService | [@dubingjian](https://gitee.com/bj1010) |
| I4X2EM | 【新增特性 信息交换机制】按键拦截               | 标准系统 | SIG_BasicSoftwareService | [@dubingjian](https://gitee.com/bj1010) |
| I4X2EN | 【新增特性 信息交换机制】支持上报窗口节点信息   | 标准系统 | SIG_BasicSoftwareService | [@dubingjian](https://gitee.com/bj1010) |
| I4X2EO | 【新增特性 无障碍服务管理】目标应用连接         | 标准系统 | SIG_BasicSoftwareService | [@dubingjian](https://gitee.com/bj1010) |
| I4X2EP | 【新增特性 无障碍服务管理】辅助应用连接         | 标准系统 | SIG_BasicSoftwareService | [@dubingjian](https://gitee.com/bj1010) |
| I4X2ER | 【新增特性 无障碍服务管理】辅助应用更新         | 标准系统 | SIG_BasicSoftwareService | [@dubingjian](https://gitee.com/bj1010) |
| I4X2ES | 【新增特性 无障碍服务管理】无障碍字幕配置       | 标准系统 | SIG_BasicSoftwareService | [@dubingjian](https://gitee.com/bj1010) |
| I4X2ET | 【新增特性 信息交换机制】支持控件节点信息上报   | 标准系统 | SIG_BasicSoftwareService | [@dubingjian](https://gitee.com/bj1010) |
| I4X2EV | 【新增特性 信息交换机制】焦点查询               | 标准系统 | SIG_BasicSoftwareService | [@dubingjian](https://gitee.com/bj1010) |
| I4X2EY | 【新增特性 信息交换机制】无障碍事件列表         | 标准系统 | SIG_BasicSoftwareService | [@dubingjian](https://gitee.com/bj1010) |
| I4X2EZ | 【新增特性 信息交换机制】无障碍事件信息         | 标准系统 | SIG_BasicSoftwareService | [@dubingjian](https://gitee.com/bj1010) |
| I4X2F0 | 【新增特性 信息交换机制】无障碍动作发起         | 标准系统 | SIG_BasicSoftwareService | [@dubingjian](https://gitee.com/bj1010) |
| I4X2F1 | 【新增特性 信息交换机制】辅助应用列表查询       | 标准系统 | SIG_BasicSoftwareService | [@dubingjian](https://gitee.com/bj1010) |
| I4X2F2 | 【新增特性 信息交换机制】辅助应用状态查询与监听 | 标准系统 | SIG_BasicSoftwareService | [@dubingjian](https://gitee.com/bj1010) |
| I4X2F3 | 【新增特性 信息交换机制】手势模拟               | 标准系统 | SIG_BasicSoftwareService | [@dubingjian](https://gitee.com/bj1010) |
| I4X2F4 | 【新增特性 信息交换机制】触摸拦截               | 标准系统 | SIG_BasicSoftwareService | [@dubingjian](https://gitee.com/bj1010) |
| I4X2F6 | 【SysCap】无障碍软件服务子系统支持SysCap机制    | 标准系统 | SIG_BasicSoftwareService | [@dubingjian](https://gitee.com/bj1010) |
| I4XXCD |【新增规格】Image组件支持同步、异步渲染设置|标准系统|SIG_BasicSoftwareService|[@handyohos](https://gitee.com/handyohos)|
| I4XXCE |【部件化专项】Web子系统部件标准化|标准系统|SIG_ApplicationFramework|[@bigpumpkin](https://gitee.com/bigpumpkin)|
| I4XXCG |【资料】Web子系统JS接口说明|标准系统|SIG_ApplicationFramework|[@bigpumpkin](https://gitee.com/bigpumpkin)|
| I4XXCH |【新增特性】应用内支持Web页面的加载和显示|标准系统|SIG_ApplicationFramework|[@bigpumpkin](https://gitee.com/bigpumpkin)|
| I4XXCI |【新增特性】应用可设置Web页面状态的监听和回调|标准系统|SIG_ApplicationFramework|[@bigpumpkin](https://gitee.com/bigpumpkin)|
| I4XXCJ |【新增特性】应用可配置Web引擎的工作参数|标准系统|SIG_ApplicationFramework|[@bigpumpkin](https://gitee.com/bigpumpkin)|
| I4XXCK|【syscap_codec部件】SysCap编解码工具|标准系统|SIG_CompileRuntime|[@wangxing-hw](https://gitee.com/wangxing-hw)|
| I4XXCM|【测试工具】需要扩展对三方N设备的支持|标准系统|SIG_Test|[@buranfanchen](https://gitee.com/buranfanchen)|
| I4XXCN|【测试工具】开关机压力测试工具|标准系统|SIG_Test|[@buranfanchen](https://gitee.com/buranfanchen)|
| I4XXCO|【测试工具】休眠唤醒压力测试工具|标准系统|SIG_Test|[@buranfanchen](https://gitee.com/buranfanchen)|
| I4XXCQ|【测试框架】UI测试框架测试资料|标准系统|SIG_Test|[@buranfanchen](https://gitee.com/buranfanchen)|
| I4XXCR|【测试框架】界面自动化测试|标准系统|SIG_Test|[@buranfanchen](https://gitee.com/buranfanchen)|
| I4XXCS|【测试框架】开发者测试框架资料|标准系统|SIG_Test|[@buranfanchen](https://gitee.com/buranfanchen)|
| I4XXCV|【测试框架】TS开发者测试框架|标准系统|SIG_Test|[@buranfanchen](https://gitee.com/buranfanchen)|
| I4XXCW|【测试框架】JS应用开发者测试框架|标准系统|SIG_Test|[@buranfanchen](https://gitee.com/buranfanchen)|
| I4XXCX|【测试框架】测试流水线测试套执行报表|标准系统|SIG_Test|[@buranfanchen](https://gitee.com/buranfanchen)|
| I4XXCY|【测试框架】执行测试用例|标准系统|SIG_Test|[@buranfanchen](https://gitee.com/buranfanchen)|
| I4XXCZ|【测试框架】用例配置管理|标准系统|SIG_Test|[@buranfanchen](https://gitee.com/buranfanchen)|
| I4XXD0|【测试框架】执行器设备管理|标准系统|SIG_Test|[@buranfanchen](https://gitee.com/buranfanchen)|
| I4XXD1|【测试框架】分布式测试框架资料|标准系统|SIG_Test|[@buranfanchen](https://gitee.com/buranfanchen)|
| I4XXD2|【测试框架】TS/JS 分布式测试框架|标准系统|SIG_Test|[@buranfanchen](https://gitee.com/buranfanchen)|
| I4XXD3|【测试框架】C++分布式接口测试|标准系统|SIG_Test|[@buranfanchen](https://gitee.com/buranfanchen)|
| I4XXD4|【CERTMGR】支持以OH凭据到OH认证云进行端云验证|标准系统|SIG_Test|[@buranfanchen](https://gitee.com/buranfanchen)|
| I4XXD6|【认证测试】HATS3.1 HDF&HDI兼容性测试套件|标准系统|SIG_Test|[@buranfanchen](https://gitee.com/buranfanchen)|
| I4XXD7|【认证测试】DCTS3.1分布式兼容性测试套件|标准系统|SIG_Test|[@buranfanchen](https://gitee.com/buranfanchen)|
| I4XXD8|【cert_mgr_platform】资源管理|标准系统|SIG_Test|[@buranfanchen](https://gitee.com/buranfanchen)|
| I4XXDA|【cert_mgr_platform】字典管理|标准系统|SIG_Test|[@buranfanchen](https://gitee.com/buranfanchen)|
| I4XXDB|【cert_mgr_platform】发证管理|标准系统|SIG_Test|[@buranfanchen](https://gitee.com/buranfanchen)|
| I4XXDD|【cert_mgr_platform】公示管理|标准系统|SIG_Test|[@buranfanchen](https://gitee.com/buranfanchen)|
| I4XXDE|【cert_mgr_platform】认证度量|标准系统|SIG_Test|[@buranfanchen](https://gitee.com/buranfanchen)|
| I4XXDF|【cert_mgr_platform】Token申请与Token管理|标准系统|SIG_Test|[@buranfanchen](https://gitee.com/buranfanchen)|
| I4XXDH|【cert_mgr_platform】企业空间管理|标准系统|SIG_Test|[@buranfanchen](https://gitee.com/buranfanchen)|
| I4XXDI|【cert_mgr_platform】认证提交|标准系统|SIG_Test|[@buranfanchen](https://gitee.com/buranfanchen)|
| I4XXDJ|【cert_mgr_platform】认证进度和认证结果查询|标准系统|SIG_Test|[@buranfanchen](https://gitee.com/buranfanchen)|
| I4XXDL|【cert_mgr_platform】问题反馈&问题处理|标准系统|SIG_Test|[@buranfanchen](https://gitee.com/buranfanchen)|
| I4XXDM|【cert_mgr_platform】认证审核|标准系统|SIG_Test|[@buranfanchen](https://gitee.com/buranfanchen)|
| I4XXDN|【cert_mgr_platform】OHCA协议签署与OHCA协议管理|标准系统|SIG_Test|[@buranfanchen](https://gitee.com/buranfanchen)|
| I4XXDO|【cert_mgr_platform】企业用户信息维护|标准系统|SIG_Test|[@buranfanchen](https://gitee.com/buranfanchen)|
| I4XXDP|【cert_mgr_platform】用户权限配置|标准系统|SIG_Test|[@buranfanchen](https://gitee.com/buranfanchen)|
| I4XXDR|【cert_mgr_platform】用户登陆|标准系统|SIG_Test|[@buranfanchen](https://gitee.com/buranfanchen)|
| I4XXDS|【cert_mgr_platform】OpenHarmony官网统一帐号支持兼容性认证账号登录和认证管理|标准系统|SIG_Test|[@buranfanchen](https://gitee.com/buranfanchen)|
| I4XXDU|【cert_mgr_platform】OpenHarmony官网兼容性认证结果公示和宣传专区|标准系统|SIG_Test|[@buranfanchen](https://gitee.com/buranfanchen)|
| I4XXDV|【cert_mgr_platform】OpenHarmony官网PCS规范/XTS套件/认证指导/授标规范发布和管理专区|标准系统|SIG_Test|[@buranfanchen](https://gitee.com/buranfanchen)|
| I4XXDX|【认证测试】XTS执行框架支持组件化配置(xdevice)|标准系统|SIG_Test|[@buranfanchen](https://gitee.com/buranfanchen)|
| I4XXDY|【认证测试】xts测试套件支持按部件构建挑选|标准系统|SIG_Test|[@buranfanchen](https://gitee.com/buranfanchen)|
| I4XXDZ|【认证测试】测试框架支持部件化编译|标准系统|SIG_Test|[@buranfanchen](https://gitee.com/buranfanchen)|
| I4XXE1|【pcs】新增分布式文件兼容性规范|标准系统|SIG_Test|[@buranfanchen](https://gitee.com/buranfanchen)|
| I4XXE2|【pcs】新增分布式通知兼容性规范|标准系统|SIG_Test|[@buranfanchen](https://gitee.com/buranfanchen)|
| I4XXE4|【pcs】更新应用包结构兼容性规范|标准系统|SIG_Test|[@buranfanchen](https://gitee.com/buranfanchen)|
| I4XXE5|【pcs】更新兼容性测试规范|标准系统|SIG_Test|[@buranfanchen](https://gitee.com/buranfanchen)|
| I4XXE6|【pcs】新增SysCap和PCID兼容性规范|标准系统|SIG_Test|[@buranfanchen](https://gitee.com/buranfanchen)|
| I4XXE8|【pcs】更新mini/small/standard基础系统类型API最小集|标准系统|SIG_Test|[@buranfanchen](https://gitee.com/buranfanchen)|
| I4XXEA|【部件化专项】分布式标准系统部件标准化|标准系统|SIG_SoftBus|[@bigpumpkin](https://gitee.com/bigpumpkin)|
| I4RKT7|【DFX】增加图形栈基础维测能力，看护图形系统性能指标|标准系统|SIG-Graphics|[@lz-230](https://gitee.com/lz-230)|
| I4XXED|【RPC】RPC支持基础数据类型序列化/反序列化|标准系统|SIG_SoftBus|[@bigpumpkin](https://gitee.com/bigpumpkin)|
| I4XXEF|【RPC】支持RPC对象跨进程序列化|标准系统|SIG_SoftBus|[@bigpumpkin](https://gitee.com/bigpumpkin)|
| I4XXEL|【增强特性】软总线支持蓝牙|标准系统|SIG_SoftBus|[@bigpumpkin](https://gitee.com/bigpumpkin)|
| I4XXEN|【新增特性】【组网】软总线组网支持P2P连接|标准系统|SIG_SoftBus|[@bigpumpkin](https://gitee.com/bigpumpkin)|
| I4XXEO|【增强特性】【传输】文件传输增强（NSTACK组件能力）|标准系统|SIG_SoftBus|[@bigpumpkin](https://gitee.com/bigpumpkin)|
| I4XXEP|【新增特性】【连接】软总线支持P2P连接|标准系统|SIG_SoftBus|[@bigpumpkin](https://gitee.com/bigpumpkin)|
| I4IEDX|【RPC】RPC支持基础数据类型序列化/反序列化SR000GJUUQ|标准系统|SIG_SoftBus|[@bigpumpkin](https://gitee.com/bigpumpkin)|
| I4XXER|【新增特性】【组网】软总线提供组网ExtAPI接口|标准系统|SIG_SoftBus|[@bigpumpkin](https://gitee.com/bigpumpkin)|
| I4XXES|【新增特性】【传输】软总线支持P2P文件传输|标准系统|SIG_SoftBus|[@bigpumpkin](https://gitee.com/bigpumpkin)|
| I4XXET|【新增特性】【传输】软总线支持P2P流传输|标准系统|SIG_SoftBus|[@bigpumpkin](https://gitee.com/bigpumpkin)|
| I4XXEV|【新增特性】【传输】流传输增强（NSTACK组件能力增强）|标准系统|SIG_SoftBus|[@bigpumpkin](https://gitee.com/bigpumpkin)|
| I4XXEX|【传输】文件传输（蓝牙)|标准系统|SIG_SoftBus|[@bigpumpkin](https://gitee.com/bigpumpkin)|
| I4XXEY|【增强特性】软总线支持获取设备名称|标准系统|SIG_SoftBus|[@bigpumpkin](https://gitee.com/bigpumpkin)|
| I3NIN8|【RPC】支持RPC对象跨进程序列化SR000FLG|标准系统|SIG_SoftBus|[@bigpumpkin](https://gitee.com/bigpumpkin)|
| I4XXF0|【部件化专项】分布式软总线(基础通信)子系统WIFI部件标准化|标准系统|SIG_SoftBus|[@cheng_guohong](https://gitee.com/cheng_guohong)|
| I4XXF3|【部件化专项】分布式软总线(基础通信)子系统NFC部件标准化|标准系统|SIG_SoftBus|[@cheng_guohong](https://gitee.com/cheng_guohong)|
| I4XXF4|【部件化专项】分布式软总线(基础通信)子系统蓝牙部件标准化|标准系统|SIG_SoftBus|[@cheng_guohong](https://gitee.com/cheng_guohong)|
| I4XXF5|【bluetooth_standard】提供蓝牙功耗统计以及功耗优化能力|标准系统|SIG_SoftBus|[@cheng_guohong](https://gitee.com/cheng_guohong)|
| I4XXF6|【新增特性】支持STA基础特性的复杂加密方式|标准系统|SIG_SoftBus|[@cheng_guohong](https://gitee.com/cheng_guohong)|
| I4XXF7|【新增特性】支持SoftAP 5G及信道自动选择|标准系统|SIG_SoftBus|[@cheng_guohong](https://gitee.com/cheng_guohong)|
| I4XXF8|【新增特性】支持SoftAP基础特性的JS API接口|标准系统|SIG_SoftBus|[@cheng_guohong](https://gitee.com/cheng_guohong)|
| I4XXF9|【新增特性】支持SoftAP基础特性的JS API接口资料文档|标准系统|SIG_SoftBus|[@cheng_guohong](https://gitee.com/cheng_guohong)|
| I4XXFB|【新增特性】支持P2P magiclink连接特性|标准系统|SIG_SoftBus|[@cheng_guohong](https://gitee.com/cheng_guohong)|
| I4XXFC|【新增特性】支持P2P 基础特性能力的JS API接口|标准系统|SIG_SoftBus|[@cheng_guohong](https://gitee.com/cheng_guohong)|
| I4XXFE|【新增特性】支持P2P 基础特性能力的JS API接口文档|标准系统|SIG_SoftBus|[@cheng_guohong](https://gitee.com/cheng_guohong)|
| I4XXFF|【新增特性】提供WiFi P2P基本能力|标准系统|SIG_SoftBus|[@cheng_guohong](https://gitee.com/cheng_guohong)|
| I4XXFG|【新增特性】支持WiFi功耗统计以及功耗优化能力|标准系统|SIG_SoftBus|[@cheng_guohong](https://gitee.com/cheng_guohong)|
| I4XXFH|【新增特性】支持WiFi架构与WPA的HDI能力|标准系统|SIG_SoftBus|[@cheng_guohong](https://gitee.com/cheng_guohong)|
| I4XXFK|【新增特性】支持WiFi架构与驱动的HDI能力|标准系统|SIG_SoftBus|[@cheng_guohong](https://gitee.com/cheng_guohong)|
| I4XXFL|【bluetooth_standard】支持蓝牙SPP能力，提供BR的数据传输能力|标准系统|SIG_SoftBus|[@cheng_guohong](https://gitee.com/cheng_guohong)|
| I4XXFM|【bluetooth_standard】提供蓝牙SPP功能的开发指导手册、API说明文档的资料文档|标准系统|SIG_SoftBus|[@cheng_guohong](https://gitee.com/cheng_guohong)|
| I4XXFN|【bluetooth_standard】支持蓝牙BLE相关的基本能力|标准系统|SIG_SoftBus|[@cheng_guohong](https://gitee.com/cheng_guohong)|
| I4XXFP|【bluetooth_standard】支持蓝牙BLE相关的基本能力|标准系统|SIG_SoftBus|[@cheng_guohong](https://gitee.com/cheng_guohong)|
| I4XXFQ|【bluetooth_standard】提供HFP profile能力以及相关API|标准系统|SIG_SoftBus|[@cheng_guohong](https://gitee.com/cheng_guohong)|
| I4XXFS|【bluetooth_standard】提供HFP profile能力以及相关API|标准系统|SIG_SoftBus|[@cheng_guohong](https://gitee.com/cheng_guohong)|
| I4XXFT|【bluetooth_standard】提供A2DP profile相关能力以及JS API|标准系统|SIG_SoftBus|[@cheng_guohong](https://gitee.com/cheng_guohong)|
| I4XXFV|【bluetooth_standard】提供A2DP profile相关能力以及JS API|标准系统|SIG_SoftBus|[@cheng_guohong](https://gitee.com/cheng_guohong)|
| I4XXFW|【bluetooth_standard】提供AVRCP profile相关能力以及JS API|标准系统|SIG_SoftBus|[@cheng_guohong](https://gitee.com/cheng_guohong)|
| I4XXFY|【bluetooth_standard】提供AVRCP profile相关能力以及JS API|标准系统|SIG_SoftBus|[@cheng_guohong](https://gitee.com/cheng_guohong)|
| I4XXFZ|【bluetooth_standard】蓝牙PAN特性，支持通过蓝牙进行网络共享；|标准系统|SIG_SoftBus|[@cheng_guohong](https://gitee.com/cheng_guohong)|
| I4XXG0|【bluetooth_standard】蓝牙PAN特性，支持通过蓝牙进行网络共享；|标准系统|SIG_SoftBus|[@cheng_guohong](https://gitee.com/cheng_guohong)|
| I4XXG1|【bluetooth_standard】提供蓝牙DFX相关能力以及JS API|标准系统|SIG_SoftBus|[@cheng_guohong](https://gitee.com/cheng_guohong)|
| I4XXG4|【新增特性】提供NFC NDEF 有源标签的读写能力|标准系统|SIG_SoftBus|[@cheng_guohong](https://gitee.com/cheng_guohong)|
| I4XXG5|【资料】有源标签读取JS接口的资料开发|标准系统|SIG_SoftBus|[@cheng_guohong](https://gitee.com/cheng_guohong)|
| I4XXG6|【bluetooth_standard】提供蓝牙文件传输能力|标准系统|SIG_SoftBus|[@cheng_guohong](https://gitee.com/cheng_guohong)|
| I4XXG7|【bluetooth_standard】提供蓝牙文件传输能力|标准系统|SIG_SoftBus|[@cheng_guohong](https://gitee.com/cheng_guohong)|
| I4XXG8|【bluetooth_standard】支持人机接口设备接入能力，如蓝牙键盘、鼠标、游戏手柄等|标准系统|SIG_SoftBus|[@cheng_guohong](https://gitee.com/cheng_guohong)|
| I4XXG9|【bluetooth_standard】支持人机接口设备接入能力，如蓝牙键盘、鼠标、游戏手柄等|标准系统|SIG_SoftBus|[@cheng_guohong](https://gitee.com/cheng_guohong)|
| I4XXGB|【bluetooth_standard】支持蓝牙BR/EDR的基本能力|标准系统|SIG_SoftBus|[@cheng_guohong](https://gitee.com/cheng_guohong)|
| I4XXGC|【bluetooth_standard】支持蓝牙BR/EDR的基本能力|标准系统|SIG_SoftBus|[@cheng_guohong](https://gitee.com/cheng_guohong)|
| I4XXGD|【SysCap】分布式标准系统（基础通信）支持SysCap机制|标准系统|SIG_SoftBus|[@cheng_guohong](https://gitee.com/cheng_guohong)|
| I4XXGF|【request部件】文件上传功能|标准系统|SIG_DataManagement|[@mangtsang](https://gitee.com/mangtsang)|
| I4XXGG|【部件化专项】【preference部件】preference部件标准化|标准系统|SIG_DataManagement|[@mangtsang](https://gitee.com/mangtsang)|
| I4XXGH|【部件化专项】【data_share_ability部件】data_share_ability部件标准化|标准系统|SIG_DataManagement|[@mangtsang](https://gitee.com/mangtsang)|
| I4XXGI|【部件化专项】【relational_store部件】relational_store部件标准化|标准系统|SIG_DataManagement|[@mangtsang](https://gitee.com/mangtsang)|
| I4XXGK|【SysCap】分布式数据管理子系统支持SysCap机制|标准系统|SIG_DataManagement|[@mangtsang](https://gitee.com/mangtsang)|
| I4XXGN|【SysCap】分布式硬件管理子系统支持SysCap机制|标准系统|SIG_DistributedHardwareManagement|[@hwzhangchuang](https://gitee.com/hwzhangchuang)|
| I4XXGO|【资料】提供场景化视频播放JS接口说明|标准系统|SIG_Media|[@zhu-mingliang](https://gitee.com/zhu-mingliang)|
| I4XXGP|【资料】提供场景化视频录制JS接口说明|标准系统|SIG_Media|[@zhu-mingliang](https://gitee.com/zhu-mingliang)|
| I4XXGQ|【新增特性】图片位图，解码框架接口对齐API7|标准系统|SIG_Media|[@zhu-mingliang](https://gitee.com/zhu-mingliang)|
| I4XXGR|【SysCap】媒体子系统支持SysCap机制|标准系统|SIG_Media|[@zhu-mingliang](https://gitee.com/zhu-mingliang)|
| I4XXGS|【外部依赖】【内核子系统】内核实现进程的tokenID设置|标准系统|SIG_Kernel|[@liuyoufang](https://gitee.com/liuyoufang)|
| I4XXGT|【新增】编译构建/Module rules 编译构建流程适配SoC与Board分离机制。|标准系统|SIG_Kernel|[@leonchan5](https://gitee.com/leonchan5)|
| I4XXGU|【新增】硬件芯片/hisilico跟随SoC与Board分离机制进行调整。|标准系统|SIG_Kernel|[@leonchan5](https://gitee.com/leonchan5)|
| I4XXGV|【增强特性】appspawn归一|标准系统|SIG_BasicSoftwareService|[@handyohos](https://gitee.com/handyohos)|
| I4XXGW|【部件化专项】启动子系统提供SystemCapability API|标准系统|SIG_BasicSoftwareService|[@handyohos](https://gitee.com/handyohos)|
| I4XXGX|【SysCap】启动恢复子系统支持SysCap机制|标准系统|SIG_BasicSoftwareService|[@handyohos](https://gitee.com/handyohos)|
| I4XXGZ|【新增特性】基于HDF驱动框架提供计步器Sensor驱动能力|标准系统|SIG_DriverFramework|[@zianed](https://gitee.com/zianed)|
| I4XXH2|【SysCap】全球化子系统支持SysCap机制|标准系统|SIG_ApplicationFramework|[@mengjingzhimo](https://gitee.com/mengjingzhimo)|
| I4XXH6|【SysCap】升级服务子系统支持SysCap机制|标准系统|SIG_BasicSoftwareService|[@ailorna](https://gitee.com/ailorna)|
| I4XXH7|【SysCap】标准系统支持SysCap机制|标准系统|SIG_BasicSoftwareService|[@autumn330](https://gitee.com/autumn330)|
| I4XXH8|【部件化专项】inputmethod部件标准化|标准系统|SIG_BasicSoftwareService|[@zhouyongfei](https://gitee.com/zhouyongfei)|
| I4XXH9|【inputmethod部件】inputmethod JS API接口开放|标准系统|SIG_BasicSoftwareService|[@zhouyongfei](https://gitee.com/zhouyongfei)|
| I4XXHA|【新增规格】输入法管理服务|标准系统|SIG_BasicSoftwareService|[@zhouyongfei](https://gitee.com/zhouyongfei)|
| I4XXHB|【新增规格】输入法开发框架监听系统事件、输入框事件|标准系统|SIG_BasicSoftwareService|[@zhouyongfei](https://gitee.com/zhouyongfei)|
| I4XXHC|【新增规格】输入法开发框架支持输入法应用的文本输入|标准系统|SIG_BasicSoftwareService|[@zhouyongfei](https://gitee.com/zhouyongfei)|
| I4XXHE|【新增规格】输入法管理服务资料|标准系统|SIG_BasicSoftwareService|[@zhouyongfei](https://gitee.com/zhouyongfei)|
| I4XXHF|【SysCap】图形子系统支持SysCap机制|标准系统|SIG_GraphicsandMedia|[@lz-230](https://gitee.com/lz-230)|
| I4XXHG|【wpa_supplicant】提供magiclink能力|标准系统|SIG-Telephony|[@clevercong](https://gitee.com/clevercong)|
| I4XXHH|【wpa_supplicant】提供基于NL80211的wpa、p2p能力。|标准系统|SIG-Telephony|[@clevercong](https://gitee.com/clevercong)|
| I4XXHJ|【部件化专项】netmanager_base部件标准化|标准系统|SIG-Telephony|[@clevercong](https://gitee.com/clevercong)|
| I4XXHK|【部件化专项】netstack部件标准化|标准系统|SIG-Telephony|[@clevercong](https://gitee.com/clevercong)|
| I4XXHL|【增强特性】提供基础网络连接管理相关native和JS API接口|标准系统|SIG-Telephony|[@clevercong](https://gitee.com/clevercong)|
| I4XXHM|【资料】网络管理子系统资料新增|标准系统|SIG-Telephony|[@clevercong](https://gitee.com/clevercong)|
| I4XXHN|【增强特性】支持网络连接状态查询和网络连接状态变化通知|标准系统|SIG-Telephony|[@clevercong](https://gitee.com/clevercong)|
| I4XXHP|【增强特性】支持DNS解析和配置|标准系统|SIG-Telephony|[@clevercong](https://gitee.com/clevercong)|
| I4XXHR|【资料】基础网络连接管理部件资料新增|标准系统|SIG-Telephony|[@clevercong](https://gitee.com/clevercong)|
| I4XXHS|【增强特性】支持对WIFI/蜂窝网络连接的管理和切换|标准系统|SIG-Telephony|[@clevercong](https://gitee.com/clevercong)|
| I4XXHT|【增强特性】支持http 1.1/https/http2|标准系统|SIG-Telephony|[@clevercong](https://gitee.com/clevercong)|
| I4XXHU|【增强特性】支持TCP/UDP Socket|标准系统|SIG-Telephony|[@clevercong](https://gitee.com/clevercong)|
| I4XXHV|【部件化专项】位置服务子系统部件标准化|标准系统|SIG_SoftBus|[@cheng_guohong](https://gitee.com/cheng_guohong)|
| I4XXHW|【location_gnss】支持GNSS辅助协议|标准系统|SIG_SoftBus|[@cheng_guohong](https://gitee.com/cheng_guohong)|
| I4XXHY|【location_network】支持网络定位的mock demo能力|标准系统|SIG_SoftBus|[@cheng_guohong](https://gitee.com/cheng_guohong)|
| I4XXHZ|【location_network】支持网络定位能力|标准系统|SIG_SoftBus|[@cheng_guohong](https://gitee.com/cheng_guohong)|
| I4XXI0|【location_geocode】支持经纬度和地址互相转换|标准系统|SIG_SoftBus|[@cheng_guohong](https://gitee.com/cheng_guohong)|
| I4XXI1|【资料】geocode JS接口的资料开发|标准系统|SIG_SoftBus|[@cheng_guohong](https://gitee.com/cheng_guohong)|
| I4XXI2|【资料】地理围栏JS接口的资料开发|标准系统|SIG_SoftBus|[@cheng_guohong](https://gitee.com/cheng_guohong)|
| I4XXI3|【location_geofence】支持GNSS芯片相关的地理围栏功能|标准系统|SIG_SoftBus|[@cheng_guohong](https://gitee.com/cheng_guohong)|
| I4XXI4|【location_locator】支持位置服务定位管理功能|标准系统|SIG_SoftBus|[@cheng_guohong](https://gitee.com/cheng_guohong)|
| I4XXI5|【location_locator】支持管理多个定位请求，支持多应用同时请求定位|标准系统|SIG_SoftBus|[@cheng_guohong](https://gitee.com/cheng_guohong)|
| I4XXI6|【资料】位置服务定位管理JS接口的资料开发|标准系统|SIG_SoftBus|[@cheng_guohong](https://gitee.com/cheng_guohong)|
| I4XXI7|【location_locator】提供位置服务隐私的安全保障能力|标准系统|SIG_SoftBus|[@cheng_guohong](https://gitee.com/cheng_guohong)|
| I4XXI8|【location_locator】支持位置服务的安全管理能力|标准系统|SIG_SoftBus|[@cheng_guohong](https://gitee.com/cheng_guohong)|
| I4XXI9|【location_locator】提供位置服务DFX能力|标准系统|SIG_SoftBus|[@cheng_guohong](https://gitee.com/cheng_guohong)|
| I4XXIA|【资料】位置服务dump JS接口的资料开发|标准系统|SIG_SoftBus|[@cheng_guohong](https://gitee.com/cheng_guohong)|
| I4XXIB|【location_gnss】支持GNSS参数设置和信息上报功能|标准系统|SIG_SoftBus|[@cheng_guohong](https://gitee.com/cheng_guohong)|
| I4XXIC|【location_gnss】提供GNSS Batching的能力|标准系统|SIG_SoftBus|[@cheng_guohong](https://gitee.com/cheng_guohong)|
| I4XXIE|【资料】GNSS基本定位能力JS接口的资料开发|标准系统|SIG_SoftBus|[@cheng_guohong](https://gitee.com/cheng_guohong)|
| I4XXIF|【location_gnss】提供GNSS基本定位功能|标准系统|SIG_SoftBus|[@cheng_guohong](https://gitee.com/cheng_guohong)|
| I4XXIG|【location_gnss】提供GNSS硬件功耗统计以及功耗优化能力|标准系统|SIG_SoftBus|[@cheng_guohong](https://gitee.com/cheng_guohong)|
| I4XXIH|【location_gnss】供GNSS性能提升的相关辅助信息请求和注入能力|标准系统|SIG_SoftBus|[@cheng_guohong](https://gitee.com/cheng_guohong)|
| I4XXII|【资料】GNSS辅助信息请求和注入JS接口的资料开发|标准系统|SIG_SoftBus|[@cheng_guohong](https://gitee.com/cheng_guohong)|
| I4XXIJ|【SysCap】位置服务子系统支持SysCap机制|标准系统|SIG_SoftBus|[@cheng_guohong](https://gitee.com/cheng_guohong)|
| I4XXIL|【部件化专项】文件存储子系统部件标准化|标准系统|SIG_Kernel|[@panqinxu](https://gitee.com/panqinxu)|
| I4XXIM|【新增特性】【storage_manager部件】CE/DE 文件软加密策略管理|标准系统|SIG_Kernel|[@panqinxu](https://gitee.com/panqinxu)|
| I4XXIN|【新增特性】【storage_manager部件】支持秘钥存储管理|标准系统|SIG_Kernel|[@panqinxu](https://gitee.com/panqinxu)|
| I4XXIO|【新增特性】【local_file_system部件】支持ext4/f2fs等用户态工具能力|标准系统|SIG_Kernel|[@panqinxu](https://gitee.com/panqinxu)|
| I4XXIP|【新增特性】响应多用户创建删除，进行用户目录创建和删除|标准系统|SIG_Kernel|[@panqinxu](https://gitee.com/panqinxu)|
| I4XXIQ|【资料】【file_api部件】文件系统增强接口文档|标准系统|SIG_Kernel|[@panqinxu](https://gitee.com/panqinxu)|
| I4XXIR|【新增特性】支持目录环境能力需求|标准系统|SIG_Kernel|[@panqinxu](https://gitee.com/panqinxu)|
| I4XXIT|【新增特性】支持应用文件分享能力|标准系统|SIG_Kernel|[@panqinxu](https://gitee.com/panqinxu)|
| I4XXIU|【资料】【user_file_manager部件】file picker需要的JS API文件接口文档|标准系统|SIG_Kernel|[@panqinxu](https://gitee.com/panqinxu)|
| I4XXIW|【新增特性】支持File Manager Service文件操作实现需求|标准系统|SIG_Kernel|[@panqinxu](https://gitee.com/panqinxu)|
| I4XXIX|【新增特性】支持file picker需要的JS API文件接口需求|标准系统|SIG_Kernel|[@panqinxu](https://gitee.com/panqinxu)|
| I4XXIY|【新增特性】支持应用占用空间统计特性|标准系统|SIG_Kernel|[@panqinxu](https://gitee.com/panqinxu)|
| I4XXIZ|【新增特性】支持应用cache统计特性|标准系统|SIG_Kernel|[@panqinxu](https://gitee.com/panqinxu)|
| I4XXJ2|【SysCap】标准系统支持SysCap机制|标准系统|SIG_Kernel|[@panqinxu](https://gitee.com/panqinxu)|
| I4XXJ4|【SysCap】无障碍软件服务子系统支持SysCap机制|标准系统|SIG_BasicSoftwareService|[@bj1010](https://gitee.com/bj1010)|
| I4XXJ5|【wukong部件】UI随机压测工具|标准系统|SIG_R&DToolChain|[@wangzaishang](https://gitee.com/wangzaishang)|
| I4XXJ6|【hiperf部件】开发者使用资料开发|标准系统|SIG_R&DToolChain|[@wangzaishang](https://gitee.com/wangzaishang)|
| I4XXJA|【部件化专项】【coauth部件】部件标准化|标准系统|SIG_Security|[@wangxu43](https://gitee.com/wangxu43)|
| I4XXJB|【增强特性】Builtin Stub功能汇编化|标准系统|SIG_CompileRuntime|[@wangxing-hw](https://gitee.com/wangxing-hw)|
| I4XXJC|【SysCap】语言编译器运行时子系统支持SysCap机制|标准系统|SIG_CompileRuntime|[@wangxing-hw](https://gitee.com/wangxing-hw)|
| I4XXJD|【新增特性】 [JS-Runtime]BigInt数据类型支持|标准系统|SIG_CompileRuntime|[@wangxing-hw](https://gitee.com/wangxing-hw)|
| I4XXJE|【增强特性】运行管理API补齐|标准系统|SIG_ApplicationFramework|[@gwang2008](https://gitee.com/gwang2008)|
| I4XXJF|【增强特性】ParticleAbility能力补齐|标准系统|SIG_ApplicationFramework|[@gwang2008](https://gitee.com/gwang2008)|
| I4XXJG|【增强特性】DataAbilityHelper能力补齐|标准系统|SIG_ApplicationFramework|[@gwang2008](https://gitee.com/gwang2008)|
| I4XXJH|【增强特性】上下文能力补齐|标准系统|SIG_ApplicationFramework|[@gwang2008](https://gitee.com/gwang2008)|
| I4XXJI|【SysCap】标准系统支持SysCap机制|标准系统|SIG_ApplicationFramework|[@gwang2008](https://gitee.com/gwang2008)|
| I4XXJJ|【SysCap】账号子系统支持SysCap机制|标准系统|SIG_BasicSoftwareService|[@jiang-xiaofeng](https://gitee.com/jiang-xiaofeng)|
| I4XXJL|【短信】资料|标准系统|SIG_SystemApplication|[@starr666](https://gitee.com/starr666)|
| I4XXJM|【短信】信息管理 - 信息删除|标准系统|SIG_SystemApplication|[@starr666](https://gitee.com/starr666)|
| I4XXJO|【短信】DFX - 日志|标准系统|SIG_SystemApplication|[@starr666](https://gitee.com/starr666)|
| I4XXJP|【短信】全球化 - 全球化，多语言支持|标准系统|SIG_SystemApplication|[@starr666](https://gitee.com/starr666)|
| I4XXJQ|【短信】信息管理 - 信息查看|标准系统|SIG_SystemApplication|[@starr666](https://gitee.com/starr666)|
| I4XXJR|【图库】大图浏览-收藏操作|标准系统|SIG_SystemApplication|[@sunjunxiong](https://gitee.com/sunjunxiong)|
| I4XXJT|【图库】资料需求|标准系统|SIG_SystemApplication|[@sunjunxiong](https://gitee.com/sunjunxiong)|
| I4XXJU|【图库】全局菜单|标准系统|SIG_SystemApplication|[@sunjunxiong](https://gitee.com/sunjunxiong)|
| I4XXJV|【图库】沉浸式特性|标准系统|SIG_SystemApplication|[@sunjunxiong](https://gitee.com/sunjunxiong)|
| I4XXJW|【图库】相册特性-相册显示|标准系统|SIG_SystemApplication|[@sunjunxiong](https://gitee.com/sunjunxiong)|
| I4XXJY|【图库】相册特性-基础管理|标准系统|SIG_SystemApplication|[@sunjunxiong](https://gitee.com/sunjunxiong)|
| I4XXJZ|【图库】相册特性-最近删除相册|标准系统|SIG_SystemApplication|[@sunjunxiong](https://gitee.com/sunjunxiong)|
| I4XXK1|【图库】大图浏览-基础浏览&操作|标准系统|SIG_SystemApplication|[@sunjunxiong](https://gitee.com/sunjunxiong)|
| I4XXK2|【图库】大图浏览-视频播放|标准系统|SIG_SystemApplication|[@sunjunxiong](https://gitee.com/sunjunxiong)|
| I4XXK3|【图库】大图浏览-其他操作|标准系统|SIG_SystemApplication|[@sunjunxiong](https://gitee.com/sunjunxiong)|
| I4XXK4|【图库】分布式特性|标准系统|SIG_SystemApplication|[@sunjunxiong](https://gitee.com/sunjunxiong)|
| I4XXK5|【图库】外部交互特性|标准系统|SIG_SystemApplication|[@sunjunxiong](https://gitee.com/sunjunxiong)|
| I4XXK6|【图库】照片特性|标准系统|SIG_SystemApplication|[@sunjunxiong](https://gitee.com/sunjunxiong)|
| I4XXK9|【图库】宫格特性-基础操作|标准系统|SIG_SystemApplication|[@sunjunxiong](https://gitee.com/sunjunxiong)|
| I4XXKA|【图库】宫格特性-其他操作|标准系统|SIG_SystemApplication|[@sunjunxiong](https://gitee.com/sunjunxiong)|
| I4XXKB|【图库】快速滑动|标准系统|SIG_SystemApplication|[@sunjunxiong](https://gitee.com/sunjunxiong)|
| I4XXKD|【笔记】支持鼠标左右键|标准系统|SIG_SystemApplication|[@lv-zhongwei](https://gitee.com/lv-zhongwei)|
| I4XXKE|【笔记】支持文本编辑|标准系统|SIG_SystemApplication|[@lv-zhongwei](https://gitee.com/lv-zhongwei)|
| I4XXKF|【笔记】基础功能DFX|标准系统|SIG_SystemApplication|[@lv-zhongwei](https://gitee.com/lv-zhongwei)|
| I4XXKG|【笔记】笔记支持分栏|标准系统|SIG_SystemApplication|[@lv-zhongwei](https://gitee.com/lv-zhongwei)|
| I4XXKH|【笔记】笔记搜索能力|标准系统|SIG_SystemApplication|[@lv-zhongwei](https://gitee.com/lv-zhongwei)|
| I4XXKI|【笔记】笔记支持收藏|标准系统|SIG_SystemApplication|[@lv-zhongwei](https://gitee.com/lv-zhongwei)|
| I4XXKJ|【笔记】移动到其他文件夹|标准系统|SIG_SystemApplication|[@lv-zhongwei](https://gitee.com/lv-zhongwei)|
| I4XXKK|【笔记】笔记支持置顶|标准系统|SIG_SystemApplication|[@lv-zhongwei](https://gitee.com/lv-zhongwei)|
| I4XXKL|【笔记】笔记支持删除|标准系统|SIG_SystemApplication|[@lv-zhongwei](https://gitee.com/lv-zhongwei)|
| I4XXKM|【笔记】笔记列表显示|标准系统|SIG_SystemApplication|[@lv-zhongwei](https://gitee.com/lv-zhongwei)|
| I4XXKO|【笔记】支持分类显示|标准系统|SIG_SystemApplication|[@lv-zhongwei](https://gitee.com/lv-zhongwei)|
| I4XXKQ|【笔记】支持文件夹管理|标准系统|SIG_SystemApplication|[@lv-zhongwei](https://gitee.com/lv-zhongwei)|
| I4XXKR|【新增特性】输入法资料|标准系统|SIG_BasicSoftwareService|[@zhouyongfei](https://gitee.com/zhouyongfei)|
| I4XXKS|【新增特性】输入法实现成service|标准系统|SIG_BasicSoftwareService|[@zhouyongfei](https://gitee.com/zhouyongfei)|
| I4XXKU|【新增特性】【输入法】文本输入|标准系统|SIG_BasicSoftwareService|[@zhouyongfei](https://gitee.com/zhouyongfei)|
| I4XXKW|【新增特性】【输入法】支持物理键盘|标准系统|SIG_BasicSoftwareService|[@zhouyongfei](https://gitee.com/zhouyongfei)|
| I4XXKX|【新增特性】【输入法】横屏下布局显示|标准系统|SIG_BasicSoftwareService|[@zhouyongfei](https://gitee.com/zhouyongfei)|
| I4XXKZ|【设置公共数据存储】Settings数据管理API-兼容HarmonyOS API7|标准系统|SIG_BasicSoftwareService|[@zhouyongfei](https://gitee.com/zhouyongfei)|
| I4XXL0|【资料】文件选择器-指导资料|标准系统|SIG_SystemApplication|[@lv-zhongwei](https://gitee.com/lv-zhongwei)|
| I4XXL2|【DFX】性能、功耗、打点等DFX特性|标准系统|SIG_SystemApplication|[@lv-zhongwei](https://gitee.com/lv-zhongwei)|
| I4XXL3|【文件保存路径】文件选择器-提供文件保存至选择路径的能力|标准系统|SIG_SystemApplication|[@lv-zhongwei](https://gitee.com/lv-zhongwei)|
| I4XXL4|【文件选择】文件选择器-提供文件选择能力|标准系统|SIG_SystemApplication|[@lv-zhongwei](https://gitee.com/lv-zhongwei)|
| I4XXL7|【通话】应用界面ACE2.0适配|标准系统|SIG_SystemApplication|[@jyh926](https://gitee.com/jyh926)|
| I4XXL8|【资料】应用子系统通话应用需求|标准系统|SIG_SystemApplication|[@jyh926](https://gitee.com/jyh926)|
| I4XXLA|基础功能适配支持DFX|标准系统|SIG_SystemApplication|[@jyh926](https://gitee.com/jyh926)|
| I4XXLD|移动数据设置基础功能|标准系统|SIG_SystemApplication|[@jyh926](https://gitee.com/jyh926)|
| I4XXLE|基础功能适配支持全球化|标准系统|SIG_SystemApplication|[@jyh926](https://gitee.com/jyh926)|
| I4XXLG|来电支持接听拒接基本操作|标准系统|SIG_SystemApplication|[@jyh926](https://gitee.com/jyh926)|
| I4XXLH|【相机】资料需求|标准系统|SIG_SystemApplication|[@blancwu](https://gitee.com/blancwu)|
| I4XXLJ|【相机】基础架构-DFX|标准系统|SIG_SystemApplication|[@blancwu](https://gitee.com/blancwu)|
| I4XXLM|【相机】基础架构-动效|标准系统|SIG_SystemApplication|[@blancwu](https://gitee.com/blancwu)|
| I4XXLP|【相机】基础架构-统一架构|标准系统|SIG_SystemApplication|[@blancwu](https://gitee.com/blancwu)|
| I4XXLQ|【相机】基础架构-屏幕形态适配|标准系统|SIG_SystemApplication|[@blancwu](https://gitee.com/blancwu)|
| I4XXLR|【相机】基础架构-多语言适配|标准系统|SIG_SystemApplication|[@blancwu](https://gitee.com/blancwu)|
| I4XXLS|【相机】缩略图显示和跳转|标准系统|SIG_SystemApplication|[@blancwu](https://gitee.com/blancwu)|
| I4XXLT|【相机】三方调用|标准系统|SIG_SystemApplication|[@blancwu](https://gitee.com/blancwu)|
| I4XXLX|【相机】后置普通拍照|标准系统|SIG_SystemApplication|[@blancwu](https://gitee.com/blancwu)|
| I4XXLY|【相机】后置普通录像|标准系统|SIG_SystemApplication|[@blancwu](https://gitee.com/blancwu)|
| I4XXM0|【联系人】DFX - 日志|标准系统|SIG_SystemApplication|[@starr666](https://gitee.com/starr666)|
| I4XXM1|【联系人】资料|标准系统|SIG_SystemApplication|[@starr666](https://gitee.com/starr666)|
| I4XXM2|【联系人】拨号盘 - 号码格式化显示（空格区分等）|标准系统|SIG_SystemApplication|[@starr666](https://gitee.com/starr666)|
| I4XXM3|【联系人】拨号盘 - 按键音|标准系统|SIG_SystemApplication|[@starr666](https://gitee.com/starr666)|
| I4XXM4|【设置】显示管理-分辨率设置|标准系统|SIG_SystemApplication|[@lv-zhongwei](https://gitee.com/lv-zhongwei)|
| I4XXM5|【设置】外部入口-权限管理|标准系统|SIG_SystemApplication|[@lv-zhongwei](https://gitee.com/lv-zhongwei)|
| I4XXM6|【设置】资料需求|标准系统|SIG_SystemApplication|[@lv-zhongwei](https://gitee.com/lv-zhongwei)|
| I4XXM8|【设置】系统-语言设置|标准系统|SIG_SystemApplication|[@lv-zhongwei](https://gitee.com/lv-zhongwei)|
| I4XXM9|【设置】开发者模式|标准系统|SIG_SystemApplication|[@lv-zhongwei](https://gitee.com/lv-zhongwei)|
| I4XXMB|【设置】WIFI管理|标准系统|SIG_SystemApplication|[@lv-zhongwei](https://gitee.com/lv-zhongwei)|
| I4XXMC|【设置】蓝牙管理|标准系统|SIG_SystemApplication|[@lv-zhongwei](https://gitee.com/lv-zhongwei)|
| I4XXMD|【设置】密码管理|标准系统|SIG_SystemApplication|[@lv-zhongwei](https://gitee.com/lv-zhongwei)|
| I4XXMG|【设置】应用管理|标准系统|SIG_SystemApplication|[@lv-zhongwei](https://gitee.com/lv-zhongwei)|
| I4XXMH|【设置】存储空间信息|标准系统|SIG_SystemApplication|[@lv-zhongwei](https://gitee.com/lv-zhongwei)|
| I4XXMI|【设置】定位服务开关|标准系统|SIG_SystemApplication|[@lv-zhongwei](https://gitee.com/lv-zhongwei)|
| I4XXMJ|【设置】用户管理|标准系统|SIG_SystemApplication|[@lv-zhongwei](https://gitee.com/lv-zhongwei)|
| I4XXMK|【设置】系统-恢复出厂|标准系统|SIG_SystemApplication|[@lv-zhongwei](https://gitee.com/lv-zhongwei)|
| I4XXML|【设置】基础能力-搜索|标准系统|SIG_SystemApplication|[@lv-zhongwei](https://gitee.com/lv-zhongwei)|
| I4XXMM|【资料】【SystemUI】支持子系统应用资料类需求|标准系统|SIG_SystemApplication|[@lv-zhongwei](https://gitee.com/lv-zhongwei)|
| I4XXMO|【SystemUI】【状态-控制开关】支持控制开关-蓝牙|标准系统|SIG_SystemApplication|[@lv-zhongwei](https://gitee.com/lv-zhongwei)|
| I4XXMQ|【SystemUI】【状态-控制开关】支持控制开关-响铃|标准系统|SIG_SystemApplication|[@lv-zhongwei](https://gitee.com/lv-zhongwei)|
| I4XXMR|【SystemUI】【状态栏】支持状态栏图标-时间|标准系统|SIG_SystemApplication|[@lv-zhongwei](https://gitee.com/lv-zhongwei)|
| I4XXMS|【SystemUI】【状态-控制开关】支持控制开关-位置信息|标准系统|SIG_SystemApplication|[@lv-zhongwei](https://gitee.com/lv-zhongwei)|
| I4XXMT|【SystemUI】【通知】分布式通知|标准系统|SIG_SystemApplication|[@lv-zhongwei](https://gitee.com/lv-zhongwei)|
| I4XXMU|【SystemUI】【通知管理】通知管理设置|标准系统|SIG_SystemApplication|[@lv-zhongwei](https://gitee.com/lv-zhongwei)|
| I4XXMV|【SystemUI】【状态栏】状态栏-可配置接入|标准系统|SIG_SystemApplication|[@lv-zhongwei](https://gitee.com/lv-zhongwei)|
| I4XXMX|【SystemUI】【状态-控制开关】支持控制开关-Wifi|标准系统|SIG_SystemApplication|[@lv-zhongwei](https://gitee.com/lv-zhongwei)|
| I4XXMY|【SystemUI】【状态栏图标】沉浸式|标准系统|SIG_SystemApplication|[@lv-zhongwei](https://gitee.com/lv-zhongwei)|
| I4XXMZ|【SystemUI】【控制开关】控制中心面板及交互|标准系统|SIG_SystemApplication|[@lv-zhongwei](https://gitee.com/lv-zhongwei)|
| I4XXN0|【SystemUI】支持多用户|标准系统|SIG_SystemApplication|[@lv-zhongwei](https://gitee.com/lv-zhongwei)|
| I4XXN1|【SystemUI】支持键鼠操作|标准系统|SIG_SystemApplication|[@lv-zhongwei](https://gitee.com/lv-zhongwei)|
| I4XXN2|【SystemUI】【通知】通知图标/属性处理|标准系统|SIG_SystemApplication|[@lv-zhongwei](https://gitee.com/lv-zhongwei)|
| I4XXN3|【SystemUI】【通知】通知发送权限管理|标准系统|SIG_SystemApplication|[@lv-zhongwei](https://gitee.com/lv-zhongwei)|
| I4XXN5|【SystemUI】【通知】通知支持扩展模板|标准系统|SIG_SystemApplication|[@lv-zhongwei](https://gitee.com/lv-zhongwei)|
| I4XXN6|【SystemUI】【基础框架】SystemUI状态栏/导航栏窗属性可配置|标准系统|SIG_SystemApplication|[@lv-zhongwei](https://gitee.com/lv-zhongwei)|
| I4XXN7|【SystemUI】【控制开关】截屏功能|标准系统|SIG_SystemApplication|[@lv-zhongwei](https://gitee.com/lv-zhongwei)|
| I4XXN9|【SystemUI】【控制开关】亮度调节|标准系统|SIG_SystemApplication|[@lv-zhongwei](https://gitee.com/lv-zhongwei)|
| I4XXNA|【SystemUI】支持音量面板|标准系统|SIG_SystemApplication|[@lv-zhongwei](https://gitee.com/lv-zhongwei)|
| I4XXNB|【SystemUI】支持通知样式适配|标准系统|SIG_SystemApplication|[@lv-zhongwei](https://gitee.com/lv-zhongwei)|
| I4XXNC|【SystemUI】【基础框架】SystemUI启动与显示|标准系统|SIG_SystemApplication|[@lv-zhongwei](https://gitee.com/lv-zhongwei)|
| I4XXND|【DFX】性能、功耗、日志等DFX特性|标准系统|SIG_SystemApplication|[@lv-zhongwei](https://gitee.com/lv-zhongwei)|
| I4XXNT|【资料】应用子系统桌面应用需求|标准系统|SIG_SystemApplication|[@lv-zhongwei](https://gitee.com/lv-zhongwei)|
| I4XXNV|【DFX】性能、功耗、安全、兼容性设计|标准系统|SIG_SystemApplication|[@lv-zhongwei](https://gitee.com/lv-zhongwei)|
| I4XXNW|【鼠标适配】【动效】鼠标操作相关动效|标准系统|SIG_SystemApplication|[@lv-zhongwei](https://gitee.com/lv-zhongwei)|
| I4XXNY|【鼠标适配】鼠标适配|标准系统|SIG_SystemApplication|[@lv-zhongwei](https://gitee.com/lv-zhongwei)|
| I4XXNZ|【手势导航】支持全局手势导航|标准系统|SIG_SystemApplication|[@lv-zhongwei](https://gitee.com/lv-zhongwei)|
| I4XXO0|【桌面设置】桌面设置基础功能|标准系统|SIG_SystemApplication|[@lv-zhongwei](https://gitee.com/lv-zhongwei)|
| I4XXO2|【Dock栏】【动效】Dock栏动效|标准系统|SIG_SystemApplication|[@lv-zhongwei](https://gitee.com/lv-zhongwei)|
| I4XXO3|【Dock栏】Dock栏基础能力|标准系统|SIG_SystemApplication|[@lv-zhongwei](https://gitee.com/lv-zhongwei)|
| I4XXO4|【布局管理】多设备布局自适应、横竖屏切换管理等布局管理能力|标准系统|SIG_SystemApplication|[@lv-zhongwei](https://gitee.com/lv-zhongwei)|
| I4XXO5|【未读数字角标】【2D】未读数字角标管理|标准系统|SIG_SystemApplication|[@lv-zhongwei](https://gitee.com/lv-zhongwei)|
| I4XXO6|【快捷方式Shortcut】Shortcut PopWindow显示等基础功能|标准系统|SIG_SystemApplication|[@lv-zhongwei](https://gitee.com/lv-zhongwei)|
| I4XXO8|【应用图标】应用图标显示和点击图标触发应用启动|标准系统|SIG_SystemApplication|[@lv-zhongwei](https://gitee.com/lv-zhongwei)|
| I4XXOA|【应用中心】【动效】全量应用列表基础功能|标准系统|SIG_SystemApplication|[@lv-zhongwei](https://gitee.com/lv-zhongwei)|
| I4XXOD|【应用中心】全量应用列表基础功能|标准系统|SIG_SystemApplication|[@lv-zhongwei](https://gitee.com/lv-zhongwei)|
| I4XXOE|【普通多任务】多任务卡片列表|标准系统|SIG_SystemApplication|[@lv-zhongwei](https://gitee.com/lv-zhongwei)|
| I4XXOF|【普通多任务】【动效】多任务动效|标准系统|SIG_SystemApplication|[@lv-zhongwei](https://gitee.com/lv-zhongwei)|
| I4XXOG|【智能文件夹】【动效】智能文件夹相关动效|标准系统|SIG_SystemApplication|[@lv-zhongwei](https://gitee.com/lv-zhongwei)|
| I4XXOI|【智能文件夹】智能文件夹显示、合并等基础功能|标准系统|SIG_SystemApplication|[@lv-zhongwei](https://gitee.com/lv-zhongwei)|
| I4XXOJ|【万能卡片基本功能】【动效】卡片相关动效|标准系统|SIG_SystemApplication|[@lv-zhongwei](https://gitee.com/lv-zhongwei)|
| I4XXOK|【万能卡片基本功能】卡片的呼出、关闭、固定、编辑等基础能力|标准系统|SIG_SystemApplication|[@lv-zhongwei](https://gitee.com/lv-zhongwei)|
| I4XXOL|【设置】系统-设备名称|标准系统|SIG_SystemApplication|[@lv-zhongwei](https://gitee.com/lv-zhongwei)|
| I4Y0ZI|【新增特性】分布式相机性能规格|标准系统|SIG_DistributedHardwareManagement|[@hwzhangchuang](https://gitee.com/hwzhangchuang)|
| I4YLKY|【三四方库】JSON处理|标准系统|SIG_ApplicationFramework|[@andyhm10000](https://gitee.com/andyhm10000)|
| I4YLKZ|【三四方库】xmlgraphics-batik|标准系统|SIG_ApplicationFramework|[@andyhm10000](https://gitee.com/andyhm10000)|
| I4YLL0|【三四方库】aws-sdk|标准系统|SIG_ApplicationFramework|[@andyhm10000](https://gitee.com/andyhm10000)|
| I4YLL1|【三四方库】commons-codec|标准系统|SIG_ApplicationFramework|[@andyhm10000](https://gitee.com/andyhm10000)|
| I4YLL2|【三四方库】arouter-api-onActivitResult|标准系统|SIG_ApplicationFramework|[@andyhm10000](https://gitee.com/andyhm10000)|
| I4YLL3|【三四方库】MMKV|标准系统|SIG_ApplicationFramework|[@andyhm10000](https://gitee.com/andyhm10000)|
| I4YLL4|【三四方库】ireader/sdk|标准系统|SIG_ApplicationFramework|[@andyhm10000](https://gitee.com/andyhm10000)|
| I4YLL5|【三四方库】firebase|标准系统|SIG_ApplicationFramework|[@andyhm10000](https://gitee.com/andyhm10000)|
| I4YLL6|【三四方库】eventbus|标准系统|SIG_ApplicationFramework|[@andyhm10000](https://gitee.com/andyhm10000)|
| I4YLL7|【三四方库】压缩/解压缩|标准系统|SIG_ApplicationFramework|[@andyhm10000](https://gitee.com/andyhm10000)|
| I4YLL8|【三四方库】扫描/解析二维码|标准系统|SIG_ApplicationFramework|[@andyhm10000](https://gitee.com/andyhm10000)|
| I4YLL9|【三四方库】网络请求|标准系统|SIG_ApplicationFramework|[@andyhm10000](https://gitee.com/andyhm10000)|
| I4YLLA|【三四方库】Vcard|标准系统|SIG_ApplicationFramework|[@andyhm10000](https://gitee.com/andyhm10000)|
| I4YLLC|【三四方库】图片处理|标准系统|SIG_ApplicationFramework|[@andyhm10000](https://gitee.com/andyhm10000)|
| I4YLLD|【三四方库】动画处理|标准系统|SIG_ApplicationFramework|[@andyhm10000](https://gitee.com/andyhm10000)|
| I4YLLE|【三四方库】RxJS|标准系统|SIG_ApplicationFramework|[@andyhm10000](https://gitee.com/andyhm10000)|
| I4YLLF|【三四方库】Lucene|标准系统|SIG_ApplicationFramework|[@andyhm10000](https://gitee.com/andyhm10000)|
| I4YLLG|【三四方库】LibphoneNumber|标准系统|SIG_ApplicationFramework|[@andyhm10000](https://gitee.com/andyhm10000)|
| I4YLLH|【三四方库】拼音处理|标准系统|SIG_ApplicationFramework|[@andyhm10000](https://gitee.com/andyhm10000)|
| I4YLLI|【三四方库】其他TOP200应用依赖的三方库|标准系统|SIG_ApplicationFramework|[@andyhm10000](https://gitee.com/andyhm10000)|
| I4YLLJ|【三四方库】Rocket.Chat.ohos|标准系统|SIG_ApplicationFramework|[@andyhm10000](https://gitee.com/andyhm10000)|
| I4YLLK|【三四方库】rebound|标准系统|SIG_ApplicationFramework|[@andyhm10000](https://gitee.com/andyhm10000)|
| I4YLLL|【三四方库】thrift|标准系统|SIG_ApplicationFramework|[@andyhm10000](https://gitee.com/andyhm10000)|
| I4YLLM|【三四方库】LargeImage|标准系统|SIG_ApplicationFramework|[@andyhm10000](https://gitee.com/andyhm10000)|
| I4YLLN|【三四方库】mixpanel-ohos|标准系统|SIG_ApplicationFramework|[@andyhm10000](https://gitee.com/andyhm10000)|
| I4YLLP|【三四方库】realm|标准系统|SIG_ApplicationFramework|[@andyhm10000](https://gitee.com/andyhm10000)|
| I4R2ZX| 【window_manager】【新增特性】支持跨窗口拖拽框架 | 标准系统 | SIG-Graphics | [@lz-230](https://gitee.com/lz-230) |
| I4R9OY| 【window_manager】【新增规格】增强特性：提供虚拟屏幕 | 标准系统 | SIG-Graphics | [@lz-230](https://gitee.com/lz-230) |
| I4R9P3| 【DFX】窗口绘制超时检测/窗口焦点故障检测 | 标准系统 | SIG-Graphics | [@lz-230](https://gitee.com/lz-230) |
| I4R30E| 【资料】提供窗口管理子系统资料说明 | 标准系统 | SIG-Graphics | [@lz-230](https://gitee.com/lz-230) |
| I4RKSS| 【drawing部件】提供二次绘制能力 | 标准系统 | SIG-Graphics | [@lz-230](https://gitee.com/lz-230) |
| I4RKSU| 【资料】提供图形drawing部件、composer部件、backstore部件的相关资料 | 标准系统 | SIG-Graphics | [@lz-230](https://gitee.com/lz-230) |

## OpenHarmony 3.2(Beta1)版本特性清单：
状态说明：discussion(方案讨论，需求未接受)，Reject(未纳入版本)，developing(开发中)，Testing(测试中)，Accepted(已验收)
| issue                                                        | feture description                                           | platform     | sig                  | owner                                             |
| ------------------------------------------------------------ | :----------------------------------------------------------- | :--------- | :------------------- | :------------------------------------------------ |
| I50DBH| 【新增特性】卡片数据支持携带图片           | 标准系统 | SIG_ApplicationFramework | [@xzz_0810](https://gitee.com/xzz_0810) |
| I50DBT| 【新增特性】FA卡片能力补齐-formManager重构 | 标准系统 | SIG_ApplicationFramework | [@xzz_0810](https://gitee.com/xzz_0810) |
| I524TT| 【新增特性】支持对测试框架的配置                       | 标准系统 | SIG_ApplicationFramework | [@shuaytao](https://gitee.com/shuaytao)       |
| I524WG| 【新增特性】支持系统应用不允许清除的能力               | 标准系统 | SIG_ApplicationFramework | [@shuaytao](https://gitee.com/shuaytao)       |
| I524WP| 【增强特性】查询指定应用是否安装                       | 标准系统 | SIG_ApplicationFramework | [@shuaytao](https://gitee.com/shuaytao)       |
| I52G5Q| 【分布式组件管理】【MR】【DMS】添加群组校验机制        | 标准系统     | SIG_BasicSoftwareService | [@cangegegege](https://gitee.com/cangegegege) |
| I526UP| 【MR】【新增特性】支持@system.battery 电池信息查询接口 | 标准系统     | SIG_HardwareMgr          | [@aqxyjay](https://gitee.com/aqxyjay)         |
| I50DAQ| 【特性增强】卡片使用记录上报 | 标准系统 | SIG_ApplicationFramework | [@xzz_0810](https://gitee.com/xzz_0810) |
| I50DOL| 【增强特性】Stage模型支持Worker机制                    | 标准系统 | SIG_ApplicationFramework | [@xzz_0810](https://gitee.com/xzz_0810) |
| I524UF| 【新增特性】支持系统feature的升级（已安装entry的情况下） | 标准系统 | SIG_ApplicationFramework | [@shuaytao](https://gitee.com/shuaytao) |
| I524VP| 【新增特性】支持隐式查询的优先级                         | 标准系统 | SIG_ApplicationFramework | [@shuaytao](https://gitee.com/shuaytao) |
| I526V9| 【增强特性】支持三方等设备的休眠接口                 | 标准系统     | SIG_HardwareMgr          | [@aqxyjay](https://gitee.com/aqxyjay)   |
| I526VG| 【MR】【新增特性】支持@system.brightness亮度调节接口     | 标准系统     | SIG_HardwareMgr          | [@aqxyjay](https://gitee.com/aqxyjay)   |
| I526VC| 【MR】【增强特性】支持应用通过窗口可以设置自己系统亮度   | 标准系统     | SIG_HardwareMgr          | [@aqxyjay](https://gitee.com/aqxyjay)   |
| I526V1| 【增强特性】提供读取瞬时电压、电流和电量的接口     | 标准系统     | SIG_HardwareMgr          | [@aqxyjay](https://gitee.com/aqxyjay)   |
| I4UD9W| 【增强特性】支持内核态动态驱动加载机制，提高设备驱动开发、调试效率 | 标准系统     | SIG_DriverFramework          | [@ji-fengfei](https://gitee.com/ji-fengfei)         |
| I531ST| 支持卡片卸载时，删除对应的卡片使用记录 | 标准系统     | SIG_BasicSoftwareService          | [@wangwenli_wolf](https://gitee.com/wangwenli_wolf)         |
| I531SU| 支持查询获取卡片使用记录 | 标准系统     | SIG_BasicSoftwareService          | [@wangwenli_wolf](https://gitee.com/wangwenli_wolf)         |
| I531SV| 支持记录卡片的使用计数以及使用时间 | 标准系统     | SIG_BasicSoftwareService          | [@wangwenli_wolf](https://gitee.com/wangwenli_wolf)         |
| I53CJX| 【MR】【新增特性】支持兼容system.network | 标准系统 | SIG_Telephony | [@zhang-hai-feng](https://gitee.com/zhang-hai-feng) |
| I53CKH| 【MR】【新增规格】支持兼容system.fetch | 标准系统 | SIG_Telephony | [@zhang-hai-feng](https://gitee.com/zhang-hai-feng) |
| I53CKT| 【MR】【新增特性】支持WebSocket | 标准系统 | SIG_Telephony | [@zhang-hai-feng](https://gitee.com/zhang-hai-feng) |
| I53FCL| 【新增特性】【MR】兼容支持stage新模型HAP包随版本编译 | 标准系统 | SIG_CompileRuntime  | [@anguanglin](https://gitee.com/anguanglin) |
| I4XLKK|【新增特性】【MR】支持API6 System.storage接口|标准系统|SIG_DataManagement|[@widecode](https://gitee.com/widecode)|
| I4XLKL|【资料】【MR】提供API6 System.storage的API文档|标准系统|SIG_DataManagement|[@widecode](https://gitee.com/widecode)|
| I53J82|【request部件】【upload】支持@system.request接口|标准系统|SIG-Basicsoftwareservice|[@litao33](https://gitee.com/litao33)|
| I582RO|【MR】【增强特性】通知发送和取消API7接口补齐|标准系统|SIG_ApplicationFramework|[@xzz_0810](https://gitee.com/xzz_0810)|
| I530U7|【input部件】三方件json版本升级|标准系统|SIG-basicsoftwareservice|[@hhh2](https://gitee.com/hhh2)|
| I530UH|【新增特性】启动优化|标准系统|SIG-Basicsoftwareservice|[@hhh2](https://gitee.com/hhh2)|
| I530UU|【新增特性】支持裁剪鼠标光标显示特性|标准系统|SIG-Basicsoftwareservice|[@hhh2](https://gitee.com/hhh2)|
| I530UW|【MR】【增强特性】通知发送和取消API7接口补齐|标准系统|SIG-Basicsoftwareservice|[@hhh2](https://gitee.com/hhh2)|
| I58ZUU|【新增规格】测试调度框架支持部件化|标准系统|SIG-Test|[@inter515](https://gitee.com/inter515)|
| I54566| 【增强特性】相机服务和HDI循环依赖整改 | 标准系统 | SIG_DriverFramework | [@ji-fengfei](https://gitee.com/ji-fengfei) |
| I56W2U| 【新增特性】【BackupExtension】包管理支持BackupExtension类型          | 标准系统 | SIG_ApplicationFramework | [@shuaytao](https://gitee.com/shuaytao)       |
| I56W3Z| 【新增特性】完善部分命令          | 标准系统 | SIG_ApplicationFramework | [@shuaytao](https://gitee.com/shuaytao)       |
| I56W68| 【新增特性】将pack.info打到hap包中          | 标准系统 | SIG_ApplicationFramework | [@shuaytao](https://gitee.com/shuaytao)       |
| I56W6W| 【新增特性】支持将新旧hap包打包到同一个app包中         | 标准系统 | SIG_ApplicationFramework | [@shuaytao](https://gitee.com/shuaytao)       |
| I582UZ| 【部件化】事件部件化 | 标准系统 | SIG_ApplicationFramework | [@xzz_0810](https://gitee.com/xzz_0810) |
| I58ZUK| 【新增规格】UI测试框架能力增强:API接口补充增强 | 标准系统 | SIG_Test | [@inter515](https://gitee.com/inter515) |
| I58ZUJ| 【新增规格】用例执行筛选能力 | 标准系统 | SIG_Test | [@inter515](https://gitee.com/inter515) |
| I56A90| 【新增规格】系统支持64位 | 标准系统 | SIG_DriverFramework | [@ji-fengfei](https://gitee.com/ji-fengfei) |
| I50I6S| 【新增特性】Audio新增IPC模式与直调模式接口调用统一 | 标准系统 | SIG_DriverFramework | [@ji-fengfei](https://gitee.com/ji-fengfei) |
| I54FQG| 【新增特性】提供codec设备驱动模型，支持codec类型设备 | 标准系统 | SIG_DriverFramework | [@ji-fengfei](https://gitee.com/ji-fengfei) |
| I550OL| 【新增特性】提供DFX跟踪定位，获取信息能力 | 标准系统 | SIG_DriverFramework | [@ji-fengfei](https://gitee.com/ji-fengfei) |
| I544XP| 【新增特性】支持HDF服务SELinux权限检查| 标准系统 | SIG_DriverFramework | [@ji-fengfei](https://gitee.com/ji-fengfei) |
| I4UL98| 【新增特性】ADC适配Linux内核IIO框架 | 标准系统 | SIG_DriverFramework | [@ji-fengfei](https://gitee.com/ji-fengfei) |
| I56H9L| 【增强特性】支持申请亮屏锁的时候，同时点亮屏 | 标准系统 | SIG_HardwareMgr | [@aqxyjay](https://gitee.com/aqxyjay) |
| I56H9W| 【增强特性】支持窗口单独设置自己的超时灭屏的时长 | 标准系统 | SIG_HardwareMgr | [@aqxyjay](https://gitee.com/aqxyjay) |
| I56HB8| 【增强特性】支持应用在在一定时间内保持屏幕最大亮度       | 标准系统 | SIG_HardwareMgr | [@aqxyjay](https://gitee.com/aqxyjay) |
| I55HGU| 【增强特性】支持setting查询最小、最大、默认亮度值        | 标准系统 | SIG_HardwareMgr | [@aqxyjay](https://gitee.com/aqxyjay) |
| I56HBI| 【增强特性】按键检测优化                                 | 标准系统 | SIG_HardwareMgr | [@aqxyjay](https://gitee.com/aqxyjay) |
| I56HCK| 【增强特性】【powermgr_lite】powermgr_lite支持L1 IPC切换 | 轻量系统 | SIG_HardwareMgr | [@aqxyjay](https://gitee.com/aqxyjay) |
| I55E9Y| 【增强特性】【battery_lite】battery_lite支持L1 IPC切换   | 轻量系统 | SIG_HardwareMgr | [@aqxyjay](https://gitee.com/aqxyjay) |
| I577AK| 【新增特性】支持OpenHarmony内存维测增强特性 | 标准系统 | SIG_Kernel | [@liuyoufang](https://gitee.com/liuyoufang) |
| I56W4O| 【新增特性】拆包工具将hap包中的rpcid文件提出               | 标准系统 | SIG_ApplicationFramework | [@shuaytao](https://gitee.com/shuaytao)       |
| I56W59| 【新增特性】拆包工具对stage模型包的解析               | 标准系统 | SIG_ApplicationFramework | [@shuaytao](https://gitee.com/shuaytao)       |
| I56W7H| 【新增特性】bms扫描完成后，发送扫描完成事件               | 标准系统 | SIG_ApplicationFramework | [@shuaytao](https://gitee.com/shuaytao)       |
| I56WIG| 【新增特性】包管理模块对外提供沙箱应用的安装能力               | 标准系统 | SIG_ApplicationFramework | [@shuaytao](https://gitee.com/shuaytao)       |
| I56WIS| 【新增特性】包管理模块提供对外沙箱应用的卸载能力               | 标准系统 | SIG_ApplicationFramework | [@shuaytao](https://gitee.com/shuaytao)       |
| I56WJ7| 【新增特性】包管理模块提供沙箱应用的包信息的查询能力               | 标准系统 | SIG_ApplicationFramework | [@shuaytao](https://gitee.com/shuaytao)       |
| I582UB| 【新增规格】支持代理通知 | 标准系统 | SIG_ApplicationFramework | [@xzz_0810](https://gitee.com/xzz_0810) |
| I530UL|【新增特性】支持不可触摸窗口|标准系统|SIG-Basicsoftwareservice|[@hhh2](https://gitee.com/hhh2)|
| I530W3|【新增特性】支持通过JS API监听手写笔输入设备的热插拔|标准系统|SIG-Basicsoftwareservice|[@hhh2](https://gitee.com/hhh2)|
| I530W5|【新增特性】支持通过JS API监听遥控器输入设备的热插拔|标准系统|SIG-Basicsoftwareservice|[@hhh2](https://gitee.com/hhh2)|
| I530W9|【新增特性】支持通过JS API监听鼠标输入设备的热插拔|标准系统|SIG-Basicsoftwareservice|[@hhh2](https://gitee.com/hhh2)|
| I530WB|【新增特性】支持通过JS API查看触摸板输入设备扩展信息|标准系统|SIG-Basicsoftwareservice|[@hhh2](https://gitee.com/hhh2)|
| I530WF|【新增特性】支持通过JS API监听键盘输入设备的热插拔|标准系统|SIG-Basicsoftwareservice|[@hhh2](https://gitee.com/hhh2)|
| I530WG|【新增特性】支持识别Linux Input手写笔输入设备的热插拔|标准系统|SIG-Basicsoftwareservice|[@hhh2](https://gitee.com/hhh2)|
| I530XV|【新增特性】支持Linux Input手写笔按下、移动、抬起输入事件接收并分发|标准系统|SIG-Basicsoftwareservice|[@hhh2](https://gitee.com/hhh2)|
| I58ZN5|测试子系统支持64位|标准系统|SIG_Test|[@inter515](https://gitee.com/inter515)|
| I56QF9| 【新增规格】UserAuth通用DFX需求（IAM部件合一、南向部件分离） | 标准系统 | SIG_ApplicationFramework | [@wangxu43](https://gitee.com/wangxu43) |
| I5875X| 【新增规格】用户IAM子系统UserAuth南向资料 | 标准系统 | SIG_ApplicationFramework | [@wangxu43](https://gitee.com/wangxu43) |
| I58ZUM| 【新增规格】UI测试框架能力增强: UI-dump功能开发 | 标准系统 | SIG_Test | [@inter515](https://gitee.com/inter515) |
| I58ZUR| 【新增规格】UI测试框架能力增强:自定义UI操作参数支持 | 标准系统 | SIG_Test | [@inter515](https://gitee.com/inter515) |
| I58ZUS| 【新增规格】测试调度框架支持配置 | 标准系统 | SIG_Test | [@inter515](https://gitee.com/inter515) |
| I58ZUW| 【增强特性】wukong稳定性工具支持控件注入 | 标准系统 | SIG_Test | [@inter515](https://gitee.com/inter515) |
| I58ZUV| 【增强特性】wukong支持稳定性报告解析、生成与展示 | 标准系统 | SIG_Test | [@inter515](https://gitee.com/inter515) |

## OpenHarmony 3.2(Beta2)版本特性清单：
状态说明：discussion(方案讨论，需求未接受)，Reject(未纳入版本)，developing(开发中)，Testing(测试中)，Accepted(已验收)
| issue                                                        | feture description                                           | platform     | sig                  | owner                                             |
| ------------------------------------------------------------ | :----------------------------------------------------------- | :--------- | :------------------- | :------------------------------------------------ |
|I57ZSO| 【增强特性】AMS 关键trace补齐                                | 标准系统   | SIG_ApplicationFramework | [@xzz_0810](https://gitee.com/xzz_0810) |
|I57ZQ2| 【新增特性】支持动态卡片的信息持久化                         | 标准系统   | SIG_ApplicationFramework | [@xzz_0810](https://gitee.com/xzz_0810) |
|I57ZPF| 支持提供方添加动态卡片                                       | 标准系统   | SIG_ApplicationFramework | [@xzz_0810](https://gitee.com/xzz_0810) |
|I57ZO2| 【特性增强】AMS内部锁优化                                    | 标准系统   | SIG_ApplicationFramework | [@xzz_0810](https://gitee.com/xzz_0810) |
|I57ZL8| 【增强特性】Want支持moduleName                               | 标准系统   | SIG_ApplicationFramework | [@xzz_0810](https://gitee.com/xzz_0810) |
|I57ZJC| 【增强特性】Extension进程管理机制优化                        | 标准系统   | SIG_ApplicationFramework | [@xzz_0810](https://gitee.com/xzz_0810) |
|I58411| 【eventhandler】部件名、仓名和目录整改                       | 标准系统 | SIG_ApplicationFramework | [@xzz_0810](https://gitee.com/xzz_0810) |
|I582OG| 【distributed_notification_service部件】部件名、仓名和目录整改 | 标准系统 | SIG_ApplicationFramework | [@xzz_0810](https://gitee.com/xzz_0810) |
|I582OW| 【common_event_service部件】部件名、仓名和目录整改           | 标准系统 | SIG_ApplicationFramework | [@xzz_0810](https://gitee.com/xzz_0810) |
|I5A6H6| 【增强特性】增强显示设备管理,支持多屏显示能力          | 标准系统 | SIG_DriverFramework | [@ji-fengfei](https://gitee.com/ji-fengfei) |
|I536FN| 【新增特性】支持HDI passthrougt模式           | 标准系统 | SIG_DriverFramework | [@ji-fengfei](https://gitee.com/ji-fengfei) |
|I56V2N| 【新增特性】HDF WLAN DAL HDI功率模式相关接口的定义与开发           | 标准系统 | SIG_DriverFramework | [@ji-fengfei](https://gitee.com/ji-fengfei) |
|I5936I| 【增强特性】增强Camera设备管理，补齐能力短板           | 标准系统 | SIG_DriverFramework | [@ji-fengfei](https://gitee.com/ji-fengfei) |
|I56W5H| 【新增特性】拆包工具提供解析资源的接口               | 标准系统 | SIG_ApplicationFramework | [@shuaytao](https://gitee.com/shuaytao)       |
|I56W5T| 【新增特性】配置依赖关系               | 标准系统 | SIG_ApplicationFramework | [@shuaytao](https://gitee.com/shuaytao)       |
|I56WF6| 【新增特性】支持查询包依赖关系               | 标准系统 | SIG_ApplicationFramework | [@shuaytao](https://gitee.com/shuaytao)       |
|I56W26| 【bundle_framework部件】部件名、仓名和目录整改               | 标准系统 | SIG_ApplicationFramework | [@shuaytao](https://gitee.com/shuaytao)       |
|I56W1V| 【distributed_bundle_framework部件】部件名、仓名和目录整改               | 标准系统 | SIG_ApplicationFramework | [@shuaytao](https://gitee.com/shuaytao)       |
|I56W7B| 【新增特性】增加基于ModuleName的查询接口               | 标准系统 | SIG_ApplicationFramework | [@shuaytao](https://gitee.com/shuaytao)       |
|I56WAB| 【新增特性】预授权机制               | 标准系统 | SIG_ApplicationFramework | [@shuaytao](https://gitee.com/shuaytao)       |
|I56W1C| 【bundle_tool部件】部件名、仓名和目录整改               | 标准系统 | SIG_ApplicationFramework | [@shuaytao](https://gitee.com/shuaytao)       |
|I56W0L| 【zlib部件】zlib三方开源软件独立为部件               | 标准系统 | SIG_ApplicationFramework | [@shuaytao](https://gitee.com/shuaytao)       |
|I56WCC| 【新增特性】包管理DFX               | 标准系统 | SIG_ApplicationFramework | [@shuaytao](https://gitee.com/shuaytao)       |
|I56WJB| 【DFX打点】【包管理子系统】提供系统事件、SA dump打点               | 标准系统 | SIG_ApplicationFramework | [@shuaytao](https://gitee.com/shuaytao)       |
|I54CZR| 新框架与元能力解耦DataShare代码迁移至数据管理子系统          | 标准系统 | SIG_DataManagement | [@srr101](https://gitee.com/srr101) |
|I54CWP| 新框架与元能力解耦DataShare 独立部件交付          | 标准系统 | SIG_DataManagement | [@srr101](https://gitee.com/srr101) |
|I54D25| 【新增特性】DataShare支持多种数据储存类型           | 标准系统 | SIG_DataManagement | [@srr101](https://gitee.com/srr101) |
|I530XH| 【新增特性】支持系统按键通过配置文件配置按键映射规则	|标准系统|SIG-Basicsoftwareservice|[@hhh2](https://gitee.com/hhh2)|
|I530XN| 【新增特性】支持键盘按键自动重复	|标准系统|SIG-Basicsoftwareservice|[@hhh2](https://gitee.com/hhh2)|
|I530XX| 【新增特性】支持触摸点压力属性	|标准系统|SIG-Basicsoftwareservice|[@hhh2](https://gitee.com/hhh2)|
|I530Y1| 【新增特性】支持触摸点工具区域属性	|标准系统|SIG-Basicsoftwareservice|[@hhh2](https://gitee.com/hhh2)|
|I530Y2| 【新增特性】支持触摸点工具类型属性	|标准系统|SIG-Basicsoftwareservice|[@hhh2](https://gitee.com/hhh2)|
|I530XZ| 【新增特性】支持触摸点触摸区域属性	|标准系统|SIG-Basicsoftwareservice|[@hhh2](https://gitee.com/hhh2)|
|I57ZUI| 【新增特性】支持无UI应用开发的设备-graphics模块解耦 | 标准系统   | SIG_ApplicationFramework | [@xzz_0810](https://gitee.com/xzz_0810) |
|I57ZVC| 【新增特性】支持无UI应用开发的设备-power模块解耦    | 标准系统   | SIG_ApplicationFramework | [@xzz_0810](https://gitee.com/xzz_0810) |
|I57ZW3| 【新增特性】支持提供方添加静态卡片(配置文件配置)     | 标准系统   | SIG_ApplicationFramework | [@xzz_0810](https://gitee.com/xzz_0810) |
|I57ZWM| 【新增特性】支持查询动态卡片信息                     | 标准系统   | SIG_ApplicationFramework | [@xzz_0810](https://gitee.com/xzz_0810) |
|I57ZXK| 【新增特性】提供方查询静态卡片                       | 标准系统   | SIG_ApplicationFramework | [@xzz_0810](https://gitee.com/xzz_0810) |
|I57ZXS| 【新增特性】Extention接口整改                        | 标准系统   | SIG_ApplicationFramework | [@xzz_0810](https://gitee.com/xzz_0810) |
|I57ZYQ| 【新增特性】组件提供销毁状态查询接口                 | 标准系统   | SIG_ApplicationFramework | [@xzz_0810](https://gitee.com/xzz_0810) |
|I57ZZH| 【新增特性】提供创建不同Hap包上下文能力              | 标准系统   | SIG_ApplicationFramework | [@xzz_0810](https://gitee.com/xzz_0810) |
|I57ZZZ| 【新增特性】【MR】组件本地启动支持免安装             | 标准系统   | SIG_ApplicationFramework | [@xzz_0810](https://gitee.com/xzz_0810) |
|I5800S| 【增强特性】 支持ability销毁后移除任务               | 标准系统   | SIG_ApplicationFramework | [@xzz_0810](https://gitee.com/xzz_0810) |
|I5801E| 【新增特性】测试框架支持应用abilityStage层级测试     | 标准系统   | SIG_ApplicationFramework | [@xzz_0810](https://gitee.com/xzz_0810) |
|I5801V| 【新增特性】【MR】支持获取当前top FA信息             | 标准系统   | SIG_ApplicationFramework | [@xzz_0810](https://gitee.com/xzz_0810) |
|I58025| 【新增特性】支持系统SA启动和访问组件                 | 标准系统   | SIG_ApplicationFramework | [@xzz_0810](https://gitee.com/xzz_0810) |
|I5802M| 【新增特性】支持系统SA查询和监听系统环境变化         | 标准系统   | SIG_ApplicationFramework | [@xzz_0810](https://gitee.com/xzz_0810) |
|I58034| 【增强特性】使用libuv统一JS Looper机制               | 标准系统   | SIG_ApplicationFramework | [@xzz_0810](https://gitee.com/xzz_0810) |
|I5803R| 应用程序框架需要具备接受heapdump信号的能力           | 标准系统   | SIG_ApplicationFramework | [@xzz_0810](https://gitee.com/xzz_0810) |
|I58047| 【元能力】支持单实例Ability迁移                      | 标准系统   | SIG_ApplicationFramework | [@xzz_0810](https://gitee.com/xzz_0810) |
|I5841H| 【内存基线】事件通知内存基线                         | 标准系统 | SIG_ApplicationFramework | [@xzz_0810](https://gitee.com/xzz_0810) |
|I582QQ| 【新增规格】通知发送支持设置未读角标                 | 标准系统 | SIG_ApplicationFramework | [@xzz_0810](https://gitee.com/xzz_0810) |
|I56W39| 【新增特性】支持原子化服务老化卸载               | 标准系统 | SIG_ApplicationFramework | [@shuaytao](https://gitee.com/shuaytao)       |
|I524R7| 【新增特性】支持原子化服务免安装基本能力               | 标准系统 | SIG_ApplicationFramework | [@shuaytao](https://gitee.com/shuaytao)       |
|I56W50| 【新增特性】打包同一应用的app包检查其中的hap包的moduleName要唯一               | 标准系统 | SIG_ApplicationFramework | [@shuaytao](https://gitee.com/shuaytao)       |
|I56W6P| 【新增特性】增加启动页的配置字段               | 标准系统 | SIG_ApplicationFramework | [@shuaytao](https://gitee.com/shuaytao)       |
|I5AWKX| 【新增特性】包管理支持获取包的指纹信息               | 标准系统 | SIG_ApplicationFramework | [@shuaytao](https://gitee.com/shuaytao)       |
|I56OQI| 【新增特性】包管理支持存取hap包的sha256哈希值               | 标准系统 | SIG_ApplicationFramework | [@shuaytao](https://gitee.com/shuaytao)       |
|I5AWNC| 【新增特性】打包工具支持多工程打包               | 标准系统 | SIG_ApplicationFramework | [@shuaytao](https://gitee.com/shuaytao)       |
|I53JX4| 【新增特性】跨设备查询指定语言的Label               | 标准系统 | SIG_ApplicationFramework | [@shuaytao](https://gitee.com/shuaytao)       |
|I5B0AB| 【新增规格】【电源管理服务子系统】电源管理子系统的SELinux策略配置 | 标准系统 | SIG_HardwareMgr | [@aqxyjay](https://gitee.com/aqxyjay) |
|I5B084| 【增强特性】Power HDI 接口补齐 | 标准系统 | SIG_HardwareMgr | [@aqxyjay](https://gitee.com/aqxyjay) |
|I5B09M| 【增强特性】充放电和电池HDI接口补齐 | 标准系统 | SIG_HardwareMgr | [@aqxyjay](https://gitee.com/aqxyjay) |
|I5B9DJ| 【DFX打点】【电源服务子系统】提供系统事件、SA dump、trace打点 | 标准系统 | SIG_HardwareMgr | [@aqxyjay](https://gitee.com/aqxyjay) |
|I5AOM8| 【新增特性】增加Action Hub功能 | 标准系统 | SIG_HardwareMgr | [@aqxyjay](https://gitee.com/aqxyjay) |
|I5AJW1| 【新增特性】支持Linux libALSA音频接口兼容           | 标准系统 | SIG_DriverFramework | [@ji-fengfei](https://gitee.com/ji-fengfei) |
|I41H53| 【新增特性】基于HDF框架及平台驱模型实现CANBUS总线框架           | 标准系统 | SIG_DriverFramework | [@ji-fengfei](https://gitee.com/ji-fengfei) |
|I5A2BJ| 【新增特性】用户态中断支持           | 标准系统 | SIG_DriverFramework | [@ji-fengfei](https://gitee.com/ji-fengfei) |
|I5B0C5| 【新增特性】camera支持实现Mate类型的流           | 标准系统 | SIG_DriverFramework | [@ji-fengfei](https://gitee.com/ji-fengfei) |
|I5B0BR| 【新增特性】录像模式自拍镜像功能           | 标准系统 | SIG_DriverFramework | [@ji-fengfei](https://gitee.com/ji-fengfei) |
|I59MYK| 【新增特性】USB服务广播消息           | 标准系统 | SIG_UsbManager | [@ji-fengfei](https://gitee.com/ji-fengfei) |
|I5AR8N| 【新增规格】【USB服务子系统】USB服务子系统的SELinux策略配置           | 标准系统 | SIG_UsbManager | [@ji-fengfei](https://gitee.com/ji-fengfei) |
|I530WD| 【新增特性】支持通过JS API查看触摸屏输入设备扩展信息	|标准系统|SIG-Basicsoftwareservice|[@hhh2](https://gitee.com/hhh2)|
|I530W0| 【新增特性】支持通过JS API 查看鼠标输入设备扩展信息	|标准系统|SIG-Basicsoftwareservice|[@hhh2](https://gitee.com/hhh2)|
|I530XT| 【新增特性】支持通过C++ API按照相对坐标调整鼠标位置	|标准系统|SIG-Basicsoftwareservice|[@hhh2](https://gitee.com/hhh2)|
|I530XM| 【新增特性】支持键盘通过配置文件配置按键映射规则	|标准系统|SIG-Basicsoftwareservice|[@hhh2](https://gitee.com/hhh2)|
|I530XK| 【新增特性】支持键盘类型识别	|标准系统|SIG-Basicsoftwareservice|[@hhh2](https://gitee.com/hhh2)|
|I530WP| 【新增特性】支持触摸点工具类型属性	|标准系统|SIG-Basicsoftwareservice|[@hhh2](https://gitee.com/hhh2)|
|I530WM| 【新增特性】支持触摸点触摸区域属性	|标准系统|SIG-Basicsoftwareservice|[@hhh2](https://gitee.com/hhh2)|
|I530XL| 【新增特性】支持按键能力识别	|标准系统|SIG-Basicsoftwareservice|[@hhh2](https://gitee.com/hhh2)|
|I530WI| 【新增特性】支持Linux Input手写笔压感合成	|标准系统|SIG-Basicsoftwareservice|[@hhh2](https://gitee.com/hhh2)|
|I530WJ| 【新增特性】支持Linux Input手写笔倾角	|标准系统|SIG-Basicsoftwareservice|[@hhh2](https://gitee.com/hhh2)|
|I530WH| 【新增特性】支持Linux Input手写笔功能按键输入事件接收并分发	|标准系统|SIG-Basicsoftwareservice|[@hhh2](https://gitee.com/hhh2)|
|I50MMB| 【增强特性】MMC现有驱动框架及适配驱动优化           | 标准系统 | SIG_DriverFramework | [@ji-fengfei](https://gitee.com/ji-fengfei) |
|I5805B| 【增强特性】AMS ANR功能优化                                  | 标准系统   | SIG_ApplicationFramework | [@xzz_0810](https://gitee.com/xzz_0810) |
|I580B2| 【新增特性】查询系统是否支持卡片使用方添加卡片到桌           | 标准系统   | SIG_ApplicationFramework | [@xzz_0810](https://gitee.com/xzz_0810) |
|I580GE| 【新增特性】FA卡片提供方升级卸载管理                         | 标准系统   | SIG_ApplicationFramework | [@xzz_0810](https://gitee.com/xzz_0810) |
|I580IF| 【新增特性】应用启动支持跳转应用市场下载页面                 | 标准系统   | SIG_ApplicationFramework | [@xzz_0810](https://gitee.com/xzz_0810) |
|I580IQ| 【ability_runtime部件】部件名仓名和目录整改                  | 标准系统   | SIG_ApplicationFramework | [@xzz_0810](https://gitee.com/xzz_0810) |
|I580JB| 【新增特性】上报adj模块系统应用被杀后是否能够正常恢复        | 标准系统   | SIG_ApplicationFramework | [@xzz_0810](https://gitee.com/xzz_0810) |
|I580JM| 【新增特性】支持系统应用ability不在最新任务列表显示          | 标准系统   | SIG_ApplicationFramework | [@xzz_0810](https://gitee.com/xzz_0810) |
|I580JW| 【增强特性】部件依赖整改                                     | 标准系统   | SIG_ApplicationFramework | [@xzz_0810](https://gitee.com/xzz_0810) |
|I580KA| 【增强特性】支持获任务取低分辨率snapshot                     | 标准系统   | SIG_ApplicationFramework | [@xzz_0810](https://gitee.com/xzz_0810) |
|I580KL| 【新增规格】【元能力子系统】元能力子系统的SELinux策略配置    | 标准系统   | SIG_ApplicationFramework | [@xzz_0810](https://gitee.com/xzz_0810) |
|I580LF| 【新增规格】运行时按需加载ABC模块                            | 标准系统   | SIG_ApplicationFramework | [@xzz_0810](https://gitee.com/xzz_0810) |
|I58418| 【新增规格】【事件通知子系统】事件通知子系统的SELinux策略配置 | 标准系统 | SIG_ApplicationFramework | [@xzz_0810](https://gitee.com/xzz_0810) |
|I582ST| 【新增规格】支持配置通知清理事件                             | 标准系统 | SIG_ApplicationFramework | [@xzz_0810](https://gitee.com/xzz_0810) |
|I582TF| 【增强特性】通知渠道信息设置和查询增强                       | 标准系统 | SIG_ApplicationFramework | [@xzz_0810](https://gitee.com/xzz_0810) |
|I582UL| 【增强特性】分布式通知同步增强                               | 标准系统 | SIG_ApplicationFramework | [@xzz_0810](https://gitee.com/xzz_0810) |
|I582Y4| 【DFX打点】【事件通知子系统】提供系统事件、SA dump、trace打点 | 标准系统 | SIG_ApplicationFramework | [@xzz_0810](https://gitee.com/xzz_0810) |
|I5DC5E| 【增强特性】Camera耗电统计 | 标准系统 | SIG_HardwareMgr | [@aqxyjay](https://gitee.com/aqxyjay) |
|I5DC7M| 【增强特性】Audio耗电统计 | 标准系统 | SIG_HardwareMgr | [@aqxyjay](https://gitee.com/aqxyjay) |
|I5DC8L| 【增强特性】Timer功耗DFX | 标准系统 | SIG_HardwareMgr | [@aqxyjay](https://gitee.com/aqxyjay) |
|I5DOI3| 【增强特性】power_manager及display_power_manager的重启恢复机制 | 标准系统 | SIG_HardwareMgr | [@aqxyjay](https://gitee.com/aqxyjay) |
|I5DOIE| 【增强特性】battery_manager的重启恢复机制 | 标准系统 | SIG_HardwareMgr | [@aqxyjay](https://gitee.com/aqxyjay) |
|I5B070| 【增强特性】电源管理服务内存基线 | 标准系统 | SIG_HardwareMgr | [@aqxyjay](https://gitee.com/aqxyjay) |
|I56WD7| 【新增特性】支持查询默认应用               | 标准系统 | SIG_ApplicationFramework | [@shuaytao](https://gitee.com/shuaytao)       |
|I56WDJ| 【新增特性】支持更改默认应用               | 标准系统 | SIG_ApplicationFramework | [@shuaytao](https://gitee.com/shuaytao)       |
|I56WDR| 【新增特性】支持恢复系统默认应用               | 标准系统 | SIG_ApplicationFramework | [@shuaytao](https://gitee.com/shuaytao)       |
|I56W2E| 【新增规格】【包管理子系统】包管理子系统的SELinux策略配置               | 标准系统 | SIG_ApplicationFramework | [@shuaytao](https://gitee.com/shuaytao)       |
|I56W2N| 【packing_tool部件】支持应用窗口的属性字段               | 标准系统 | SIG_ApplicationFramework | [@shuaytao](https://gitee.com/shuaytao)       |
|I56WFD| 【新增特性】提供查询metadata resource的js接口               | 标准系统 | SIG_ApplicationFramework | [@shuaytao](https://gitee.com/shuaytao)       |
|I56WEK| 【新增特性】支持按文件类型设置默认应用               | 标准系统 | SIG_ApplicationFramework | [@shuaytao](https://gitee.com/shuaytao)       |
|I56WDY| 【新增特性】支持三方应用把自己设置为默认应用               | 标准系统 | SIG_ApplicationFramework | [@shuaytao](https://gitee.com/shuaytao)       |
|I5ERJT| 【新增规格】用户IAM子系统SELinux策略配置 | 标准系统 | SIG_ApplicationFramework | [@wangxu43](https://gitee.com/wangxu43) |
|I5EPCD| 支持完成指定用户的指纹录入【框架】 | 标准系统 | SIG_Security |  [@wangxu](https://gitee.com/wangxu43) |
|I5EPCM| 支持完成指定用户的指纹认证和指纹识别【框架】| 标准系统 | SIG_Security |  [@wangxu](https://gitee.com/wangxu43)  |
|I5EPCU| 支持完成指定用户的指纹认证删除【框架】| 标准系统 | SIG_Security |  [@wangxu](https://gitee.com/wangxu43)  |
|I5D6CQ| 【新增规格】【驱动子系统】驱动子系统SELinux策略配置            | 标准系统 | SIG_DriverFramework | [@ji-fengfei](https://gitee.com/ji-fengfei) |
|I5DVBW| 【新增特性】新增音频音效控制           | 标准系统 | SIG_DriverFramework | [@ji-fengfei](https://gitee.com/ji-fengfei) |
|I5CXAB| 【增强特性】支持红外设备输入           | 标准系统 | SIG_DriverFramework | [@ji-fengfei](https://gitee.com/ji-fengfei) |
|I571EI| 【新增特性】基于HDF驱动框架提供心率计Sensor驱动能力           | 标准系统 | SIG_DriverFramework | [@ji-fengfei](https://gitee.com/ji-fengfei) |
|I5E3IQ| 【增强特性】增强USB设备模式，兼容Linux原生接口           | 标准系统 | SIG_UsbManager | [@ji-fengfei](https://gitee.com/ji-fengfei) |
|I5ESLP| 【增强特性】增强显示设备管理及硬件合成接口能力，并扩展色彩配置能力           | 标准系统 | SIG_DriverFramework | [@ji-fengfei](https://gitee.com/ji-fengfei) |
|I5DUOW| 【新增特性】增强HDF WLAN DAL的能力           | 标准系统 | SIG_DriverFramework | [@ji-fengfei](https://gitee.com/ji-fengfei) |
|I530XJ| 【新增特性】支持系统按键自动重复	|标准系统|SIG-Basicsoftwareservice|[@hhh2](https://gitee.com/hhh2)|
|I530X8| 【新增特性】支持通过配置文件配置按键映射规则	|标准系统|SIG-Basicsoftwareservice|[@hhh2](https://gitee.com/hhh2)|
|I530WO| 【新增特性】支持触摸点工具区域属性	|标准系统|SIG-Basicsoftwareservice|[@hhh2](https://gitee.com/hhh2)|
|I530UN| 【新增特性】窗口多热区分发机制	|标准系统|SIG-Basicsoftwareservice|[@hhh2](https://gitee.com/hhh2)|
|I530YF| 【新增规格】【多模输入】【input】SELinux策略配置	|标准系统|SIG-Basicsoftwareservice|[@hhh2](https://gitee.com/hhh2)|
|I580MY| 【新增特性】fms支持dump                      | 标准系统   | SIG_ApplicationFramework | [@xzz_0810](https://gitee.com/xzz_0810) |
|I580NR| 【新增特性】数据库文件切换路径               | 标准系统   | SIG_ApplicationFramework | [@xzz_0810](https://gitee.com/xzz_0810) |
|I580OA| 【新增特性】stage模型卡片能力补齐            | 标准系统   | SIG_ApplicationFramework | [@xzz_0810](https://gitee.com/xzz_0810) |
|I581GX| 【新增特性】AMS支持打开沙箱应用              | 标准系统   | SIG_ApplicationFramework | [@xzz_0810](https://gitee.com/xzz_0810) |
|I581HE| 【新增特性】FA模型支持windows平台轻量模拟    | 标准系统   | SIG_ApplicationFramework | [@xzz_0810](https://gitee.com/xzz_0810) |
|I581JD| 【新增特性】Stage模型支持windows平台轻量模拟 | 标准系统   | SIG_ApplicationFramework | [@xzz_0810](https://gitee.com/xzz_0810) |
|I581JY| 【增强特性】常驻进程白名单                   | 标准系统   | SIG_ApplicationFramework | [@xzz_0810](https://gitee.com/xzz_0810) |
|I581KD| 【增强特性】dataAbility兼容                  | 标准系统   | SIG_ApplicationFramework | [@xzz_0810](https://gitee.com/xzz_0810) |
|I581KO| 【增强特性】运行管理服务新增线程             | 标准系统   | SIG_ApplicationFramework | [@xzz_0810](https://gitee.com/xzz_0810) |
|I581L0| 【新增特性】应用上下文支持监听系统状态       | 标准系统   | SIG_ApplicationFramework | [@xzz_0810](https://gitee.com/xzz_0810) |
|I581LC| 【新增特性】清理整个应用后，发送公共事件     | 标准系统   | SIG_ApplicationFramework | [@xzz_0810](https://gitee.com/xzz_0810) |
|I581LR| 【增强特性】清理任务时，清理整个应用         | 标准系统   | SIG_ApplicationFramework | [@xzz_0810](https://gitee.com/xzz_0810) |
|I581M3| 【新增特性】应用选择框                       | 标准系统   | SIG_ApplicationFramework | [@xzz_0810](https://gitee.com/xzz_0810) |
|I581MR| 【新增特性】ACE 声明式框架适配新的JS runtime | 标准系统   | SIG_ApplicationFramework | [@xzz_0810](https://gitee.com/xzz_0810) |
|I581ND| 【新增特性】Stage模型适配新的JS runtime      | 标准系统   | SIG_ApplicationFramework | [@xzz_0810](https://gitee.com/xzz_0810) |
|I581PY| 【新增特性】JS runtime支持日志打印           | 标准系统   | SIG_ApplicationFramework | [@xzz_0810](https://gitee.com/xzz_0810) |
|I581QJ| 【新增特性】抽取JS runtime对接vm             | 标准系统   | SIG_ApplicationFramework | [@xzz_0810](https://gitee.com/xzz_0810) |
|I582SD| 【DFX】【增强特性】通知DFX能力增强           | 标准系统 | SIG_ApplicationFramework | [@xzz_0810](https://gitee.com/xzz_0810) |
|I582V2| 【新增规格】支持点对点发送事件               | 标准系统 | SIG_ApplicationFramework | [@xzz_0810](https://gitee.com/xzz_0810) |
|I582XB| 【新增规格】工具适配多用户                   | 标准系统 | SIG_ApplicationFramework | [@xzz_0810](https://gitee.com/xzz_0810) |
|I5DOLA| 【新增特性】适配SOC资源管控框架 | 标准系统 | SIG_HardwareMgr | [@aqxyjay](https://gitee.com/aqxyjay) |
|I5DC9H| 【增强特性】分布式任务调度功耗DFX | 标准系统 | SIG_HardwareMgr | [@aqxyjay](https://gitee.com/aqxyjay) |
|I5DONL| 【新增特性】充电资源管控框架 | 标准系统 | SIG_HardwareMgr | [@aqxyjay](https://gitee.com/aqxyjay) |
|I5DOP4| 【新增特性】热维测DFX | 标准系统 | SIG_HardwareMgr | [@aqxyjay](https://gitee.com/aqxyjay) |
|I56W7P| 【新增特性】包管理服务内存基线               | 标准系统 | SIG_ApplicationFramework | [@shuaytao](https://gitee.com/shuaytao)       |
|I56WCV| 【新增特性】支持查询指定应用的PackInfo信息               | 标准系统 | SIG_ApplicationFramework | [@shuaytao](https://gitee.com/shuaytao)       |
|I56W83| 【新增特性】支持组件的迁移前检查               | 标准系统 | SIG_ApplicationFramework | [@shuaytao](https://gitee.com/shuaytao)       |
|I59ZMR| 【新增特性】包管理支持众测应用               | 标准系统 | SIG_ApplicationFramework | [@shuaytao](https://gitee.com/shuaytao)       |
|I56W26| 【bundle_framework部件】部件名、仓名和目录整改               | 标准系统 | SIG_ApplicationFramework | [@shuaytao](https://gitee.com/shuaytao)       |
|I5A7OV| 【新增特性】包管理提供NDK接口，获取当前包的包名和证书指纹信息               | 标准系统 | SIG_ApplicationFramework | [@shuaytao](https://gitee.com/shuaytao)       |
|I5ACYA| 【新增特性】app图标支持模块化得方式获取               | 标准系统 | SIG_ApplicationFramework | [@shuaytao](https://gitee.com/shuaytao)       |
|I5214K| 【新增特性】Audio usb插拔识别及事件上报            | 标准系统 | SIG_DriverFramework | [@ji-fengfei](https://gitee.com/ji-fengfei) |
|I5F411| 【增强特性】马达效果能力增强           | 标准系统 | SIG_DriverFramework | [@ji-fengfei](https://gitee.com/ji-fengfei) |
|I528DG| 【新增特性】支持Codec 2.0参考实现，简化适配难度           | 标准系统 | SIG_DriverFramework | [@ji-fengfei](https://gitee.com/ji-fengfei) |
|I5ETTJ| 【新增特性】MMC适配Liteos_m内核           | 标准系统 | SIG_DriverFramework | [@ji-fengfei](https://gitee.com/ji-fengfei) |
|I5DJE5| 【增强特性】兼容Linux uevent事件上报机制，增强设备即插即用功能           | 标准系统 | SIG_DriverFramework | [@ji-fengfei](https://gitee.com/ji-fengfei) |
|I5FK6J| 【增强特性】提供软件Vsync机制，保障图形合成渲染同步           | 标准系统 | SIG_DriverFramework | [@ji-fengfei](https://gitee.com/ji-fengfei) |
|I5EHGF| 【资料】DataShare跨应用数据管理           | 标准系统 |SIG_DataManagement | [@srr101](https://gitee.com/srr101) |
|I5FWVI| 【新增规格】用户IAM子系统DFX | 标准系统 | SIG_ApplicationFramework | [@wangxu43](https://gitee.com/wangxu43) |
|I530WK| 【新增特性】支持触摸点压力属性	|标准系统|SIG-Basicsoftwareservice|[@hhh2](https://gitee.com/hhh2)|
|I530UT| 【新增特性】JS API Mock	|标准系统|SIG-Basicsoftwareservice|[@hhh2](https://gitee.com/hhh2)|
|I530YB| 【DFX打点】【多模输入子系统】提供系统事件、SA dump、trace打点	|标准系统|SIG-Basicsoftwareservice|[@hhh2](https://gitee.com/hhh2)|
|I5HMBS| 【input部件】键鼠自适应布局适配	|标准系统|SIG-Basicsoftwareservice|[@hhh2](https://gitee.com/hhh2)|
|I5NU4L| 【新增特性】【hilog部件】系统domain白名单管理    | 标准系统 | SIG_BasicSoftwareService  | [@stone2050](https://gitee.com/stone2050) |
|I5NU71| 【新增特性】【hilog部件】日志统计功能    | 标准系统 | SIG_BasicSoftwareService  | [@stone2050](https://gitee.com/stone2050) |
|I5NU7F| 【新增特性】【hilog部件】日志服务权限管理   | 标准系统 | SIG_BasicSoftwareService  | [@stone2050](https://gitee.com/stone2050) |
|I5KDIG| 【新增规格】【DFX子系统】【hisysevent部件】订阅功能提供应对系统事件风暴能力    | 标准系统 | SIG_BasicSoftwareService  | [@stone2050](https://gitee.com/stone2050) |
|I5L2RV| 【新增规格】【DFX子系统】【hisysevent部件】查询功能提供应对系统事件风暴能力    | 标准系统 | SIG_BasicSoftwareService  | [@stone2050](https://gitee.com/stone2050) |
|I5LFCZ| 【新增规格】【DFX子系统】【hisysevent部件】系统事件存储处理提供应用系统事件风暴能力    | 标准系统 | SIG_BasicSoftwareService  | [@stone2050](https://gitee.com/stone2050) |
|I5FNPQ| 【新增规格】【DFX子系统】【hisysevent部件】系统事件打点接口提供应对事件风暴能力   | 标准系统 | SIG_BasicSoftwareService  | [@stone2050](https://gitee.com/stone2050) |
|I5NTOS| 【新增规格】【DFX子系统】【hiappevent部件】hiappevent的事件清理能力    | 标准系统 | SIG_BasicSoftwareService  | [@stone2050](https://gitee.com/stone2050) |
|I5NTOD| 【新增规格】【DFX子系统】【hiappevent部件】hiappevent的事件查询能力    | 标准系统 | SIG_BasicSoftwareService  | [@stone2050](https://gitee.com/stone2050) |
|I5LB4N| 【新增规格】【DFX子系统】【hiappevent部件】hiappevent的事件订阅能力    | 标准系统 | SIG_BasicSoftwareService  | [@stone2050](https://gitee.com/stone2050) |
|I5KYYI| 【新增规格】【DFX子系统】【hiappevent部件】hiappevent的事件分发能力    | 标准系统 | SIG_BasicSoftwareService  | [@stone2050](https://gitee.com/stone2050) |
|I5K0X6| 【新增规格】【DFX子系统】【hiappevent部件】hiappevent的事件管理能力    | 标准系统 | SIG_BasicSoftwareService  | [@stone2050](https://gitee.com/stone2050) |
|I5NULM| 【新增规格】【DFX子系统】【hiview部件】提供读取内核事件处理能力    | 标准系统 | SIG_BasicSoftwareService  | [@stone2050](https://gitee.com/stone2050) |
|I5NXHX| 【新增特性】支持CPU调优垂直整合JS napi和native栈关联    | 标准系统 | SIG_BasicSoftwareService  | [@stone2050](https://gitee.com/stone2050) |
|I5NX04| 【新增特性】调用MEMTRACK hidl接口，支持获取GPU等设备占用的内存    | 标准系统 | SIG_BasicSoftwareService  | [@stone2050](https://gitee.com/stone2050) |
|I5GXTG| 【新增特性】hidumper权限隐私优化    | 标准系统 | SIG_BasicSoftwareService  | [@stone2050](https://gitee.com/stone2050) |
|5NWZQ | 【新增特性】对进程SMAPS进一步进行分类，在hidumper信息导出时候展示更加细致的分类信息    | 标准系统 | SIG_BasicSoftwareService  | [@stone2050](https://gitee.com/stone2050) |
|I581R1| 【新增特性】JS runtime支持timer | 标准系统 | SIG_ApplicationFramework | [@xzz_0810](https://gitee.com/xzz_0810) |


###### 以上计划由OpenHarmony社区版本发布SIG组织发布
