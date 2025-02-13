<div align="center" style="font-size: 42px; font-weight:bold;">戴森球计划Mod</div>
---

### 一、戴森球计划Mod

​	适配《戴森球计划·黑雾崛起》大版本更新，每个dll都是1个单独的功能，尽可能最小化修改。



### 二、单一功能dll

- ZhuQtool.dll

  ​	修改于[xxoolm‘s QTools](https://github.com/xxoolm/QTools)项目，实验功能，简单的内置量化，按~键(ESC下方)打开界面，可以正向计算和统计生产黄糖需要多少原材料，也可以查看铁块可以生产哪些物品，反向计算，则需要选定目标产物才会计算及更新显示。不支持更换高等级制造设备和增产剂计算。




- Zhu背包物品堆叠倍数.dll

​		背包的物品堆叠倍数为10倍。不影响储物箱等物流系统。



- Zhu超级能量枢纽.dll

  ​	能量枢纽，充放电功率315MW，能量10.26GJ。

  

- Zhu超级蓄电池.dll

  ​	蓄电池放置在地上成为建筑时，蓄电池功率315MW，能量10.26GJ。

  

- Zhu轨道采集器立即建造.dll

  ​	需要背包有物品，传送带、高速传送带、急速传送带、轨道采集器4种建筑能立即建造，

  ​	其他建筑建造不受影响，减少初期传送带、轨道采集器等建设时间耗时过久，只能等小飞机慢吞吞飞完的痛点。小飞机起飞后，由于已经建造，会转向飞回背包，有少量耗电。

  

- Zhu黑雾不登录初始星系.dll

  ​	新建游戏时，将初始星系的黑雾数量设置为零，初始星系无黑雾生成。

  ​	拦截前往初始星系新建新的太空巢穴，黑雾前往其他星系新建巢穴不受影响。

  ​	初始星系成为系统安全区域，使先熟悉流水线，再前往其他星系开启战线的玩法，成为可能，而不是现在一上来就要面对黑雾。



- Zhu黑雾不登录海洋星.dll

  ​	黑雾中继器生成时，若登录位置在海洋星，则不生成。黑雾中继器返回母巢停留后，重新搜索登录星球时，会跳过海洋星。

  

- Zhu荒漠星添加石油.dll

  ​	全星系的海洋星删除所有基础矿物，奇珍矿物则不受影响。在全星系的荒漠星添加煤炭和石油矿物。每个荒漠星添加煤矿量在200个矿脉左右，石油则是100/s左右。

  ​	初始星系若存在冻土星，会在冻土星添加煤炭和石油。主要是靠近太阳，黑雾地面基地更多，冻土星黑雾基地少些，加之荒漠星可能没有钛矿，所以初始星系冻土星加上煤矿及石油。

  

- Zhu机甲数据修改.dll

  ​	默认卸载项目不生成dll。机甲功率200GJ，护盾充能功率100GJ，护盾量1TJ。沙盒模式近距离观察黑雾母巢用，可以不用在手动点击几百次的白糖科技升级。

  

- Zhu继承物品.dll

  ​	开局继承物品。

  ​	点击电磁学，点击立即研究，少量研究立刻完成和背包获得物品，同时游戏不会弹出作弊提示。这些科技大部分是物品科技，不是糖类科技，主要用于新手教学，对于多周目玩家，可以选择跳过物品科技。

  ​	解锁科技：

  ​	宇宙探索1级、机甲核心1级、机械骨骼1级、机舱容量1级、批量建造1级、能量回路1级、驱动引擎1级

  ​	电磁学、基础物流系统、自动化冶金、电磁矩阵、基础制造

  ​	获得物品：

  ​	采矿机3、风力涡轮机3，电弧熔炉3、制造台Mk.I 5，

  ​	传送带100、

  ​	小型储物仓40、物流配送器20、配送运输机200。

  

- Zhu矿机采矿留根.dll

  ​	当矿簇里的矿脉小于100个时，则跳转到其他矿脉采矿。这样矿脉不会采空而被清除，矿机采矿速度也不会下降。当所有的矿脉都小于100时，矿机不在采矿，但功率不会减少。此时矿机正常耗电，但矿物产出为零。只有采矿科技升级到157级时，矿机才会重新产矿。

  ​	

- Zhu清除黑雾不涂地基.dll

  ​	清除黑雾的行星基地时，游戏本体会将地面涂层地基的金属色。本dll在填坑黑雾地面基地时，不涂色保留星球原本贴图。但建设建筑时被拍平的凹凸起伏地形无法恢复。期待以后游戏更新，能建设跟随地形起伏而有点变化或者凌乱的建筑风格。

  

- Zhu取物范围.dll

  ​	可以操作全球设备，打开全球储物箱，不会遇到建筑太远，无法操作的提示。

  

- Zhu物流配送机起送量.dll

  ​	当前游戏的物流配送机是1个物品也会起飞送货，dll修改物流配送机起送量为100，但前期产量低，小飞机过来每次也只能取到少量货物，取不满100。

  ​	在升级第1次配送范围科技时，会将配送机的运送量修改至100~120，配送范围修改至全球。未升级科技前，只有起送量100起作用，运送量和配送范围未改变

  

- Zhu小矿机采集整个矿簇.dll

  ​	小采矿机覆盖到矿簇里的任何一个矿脉，会自动将整个矿簇里的所有矿脉纳入采集范围。

  ​	代码编制期间，遇到代码正常，数据是public的，通过控制台打印也确认数据也确实修改了，但就是不起作用，后面推测可能是多线程的线程被守护了，导致我这边修改后，又被其他线程改回去了。后面想了很多办法，最终通过统一矿机的矿脉列表长度方式解决的。原来是有多少矿脉，就生成对应的矿脉列表。现在把采矿机的矿脉列表都统一到32个矿脉，一般的矿脉也就28个以内，32长度的矿脉列表也够用了。

  

- Zhu小矿机增加采矿距离.dll

  ​	修改小采矿机与矿物的判定距离，由10修改到18，大约增加一倍距离，配合 Zhu小矿机采集整个矿簇.dll 大概可以做到小矿机规整排布。

  

- Zhu矿机采矿留根.dll

  ​	当矿簇里的矿脉小于100个时，则跳转到其他矿脉采矿。这样矿脉不会采空而被清除，矿机采矿速度也不会下降。当所有的矿脉都小于100时，矿机不在采矿，但功率不会减少。此时矿机正常耗电，但矿物产出为零。只有采矿科技升级到157级时，矿机才会重新产矿。

  ​	

- Zhu清除黑雾不涂地基.dll

  ​	清除黑雾的行星基地时，游戏本体会将地面涂层地基的金属色。本dll在填坑黑雾地面基地时，不涂色保留星球原本贴图。但建设建筑时被拍平的凹凸起伏地形无法恢复。期待以后游戏更新，能建设跟随地形起伏而有点变化或者凌乱的建筑风格。

  

- Zhu星系内快速移动.dll

  ​	在同星系内星球之间快速移动，在不同星系的星球之间快速移动，抵达其他星系的星球需要解锁对应的宇宙探索等级。不支持在星球的全球视图内快速移动；不支持在星团视图内不同星系之间移动（停留在太阳旁边）。

  

- Zhu星系数量.dll

  ​	新建游戏时，游戏默认的星系数量是32~64个。

  ​	本dll修改创建游戏时，星系的数量可选为7~128个。（星系数量， < 7个  或者 > 247 时会开始报错，由于新建256星系数量报错，所以将上限限制为128，虽然新建240个左右星系能正常新建不报错 ... ... ）

  

  

  


### 三、编译相关

1、游戏本体安装BepInEx 5.4.23.2Mod框架，再把Directory.Build.props里面的0Harmony.dll和BepInEx.dll的路径地址修改成你电脑里的路径地址就行。win10/win11桌面右键菜单有 复制文件地址 ，可以直接复制dll的文件路径。

2、把github网站上的源码下载下来，正常编译一遍，会报错，然后在Visual Studia 项目依赖里的netstandard2.0.0条目上鼠标右键，打开文件夹位置，进入到存dll的文件夹，把里面的dll都删除，再把戴森球计划游戏本体的安装文件夹里面的Dyson Sphere Program\DSPGAME_Data\Managed文件夹里面的dll全部复制进去，再重新编译一遍就行了。

3、编译环境。

Community Visual Studia 2022

Unity2018.4.12f1

[Message:   BepInEx] BepInEx 5.4.23.2 - DSPGAME (2024/7/25 19:52:32)

[Info   :   BepInEx] Running under Unity v2018.4.12.5889476

[Info   :   BepInEx] CLR runtime version: 4.0.30319.42000

[Info   :   BepInEx] Supports SRE: True

[Info   :   BepInEx] System platform: Bits64, Windows



### 四、参考

​	项目代码主要参考了[Windows10CE](https://github.com/Windows10CE/DSPPlugins)’s  [DSPPlugins](https://github.com/Windows10CE/DSPPlugins)项目、[mattsemar](https://github.com/mattsemar)’s  [dsp-long-arm](https://github.com/mattsemar/dsp-long-arm)项目、[hetima](https://github.com/hetima)'s  [DSP_FastTravelEnabler](https://github.com/hetima/DSP_FastTravelEnabler)项目、[hetima](https://github.com/hetima)'s [DSP_ExpandTouchableRange](https://github.com/hetima/DSP_ExpandTouchableRange)项目，和[是小庄庄鸭](https://space.bilibili.com/26024327)’s  戴森球计划Mod制作教学教程（[[戴森球计划Mod制作教学]1.手把手安装需要用到的软件](https://www.bilibili.com/video/BV1pK4y1n7FF)，[[戴森球计划Mod制作教学]2.新建项目及HelloWrold](https://www.bilibili.com/video/BV1UA411T7Jv)，[[戴森球计划Mod制作教学]1.评论区答疑](https://www.bilibili.com/video/BV1dy4y1a747)，[[戴森球计划Mod制作教学]3.代码分析及Mod制作思路](https://www.bilibili.com/video/BV1Gt4y1z7JS)，[[戴森球计划Mod制作教学]采矿机倍率修改(采矿更快)](https://www.bilibili.com/video/BV1At4y1z7vp)）


​	轨道采集器立即建造： [Windows10CE](https://github.com/Windows10CE/DSPPlugins)’s  [DSPPlugins](https://github.com/Windows10CE/DSPPlugins)项目

​	继承物品：  [Windows10CE](https://github.com/Windows10CE/DSPPlugins)’s  [DSPPlugins](https://github.com/Windows10CE/DSPPlugins)项目

​	取物范围： [hetima](https://github.com/hetima)'s [DSP_ExpandTouchableRange](https://github.com/hetima/DSP_ExpandTouchableRange)项目

​	快速移动：[hetima](https://github.com/hetima)'s  [DSP_FastTravelEnabler](https://github.com/hetima/DSP_FastTravelEnabler)项目

​	小矿机采集整个矿簇： [是小庄庄鸭](https://space.bilibili.com/26024327)’s  戴森球计划Mod制作教学教程（[[戴森球计划Mod制作教学]1.手把手安装需要用到的软件](https://www.bilibili.com/video/BV1pK4y1n7FF)，[[戴森球计划Mod制作教学]2.新建项目及HelloWrold](https://www.bilibili.com/video/BV1UA411T7Jv)，[[戴森球计划Mod制作教学]1.评论区答疑](https://www.bilibili.com/video/BV1dy4y1a747)，[[戴森球计划Mod制作教学]3.代码分析及Mod制作思路](https://www.bilibili.com/video/BV1Gt4y1z7JS)，[[戴森球计划Mod制作教学]采矿机倍率修改(采矿更快)](https://www.bilibili.com/video/BV1At4y1z7vp)）





