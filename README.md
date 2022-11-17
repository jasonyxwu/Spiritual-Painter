# Spiritual-Painter

## Introduction

Spiritual-Painter(SP) is a platform game that consists of 4 levels in total.
The game is greatly inspired by Splatoon, a phenomenous multiplayer game released by Nintendo. Plus, the game difficulty is supper challenging, so get yourself prepared before starting to play it!!

## Platform

Framework: Unreal Engine
Version: 4.27.2

## Coding Style

- The first letter of each word in a name (such as type name or variable name) is capitalized, and there is usually no underscore between words. For example, `Health` and `UPrimitiveComponent` are correct, but not `lastMouseCoordinates` or `delta_coordinates`.
- Type names are prefixed with an additional upper-case letter to distinguish them from variable names. For example, `FSkin` is a type name, and `Skin` is an instance of a `FSkin`.
  - Template classes are prefixed by T.
  - Classes that inherit from `UObject` are prefixed by U.
  - Classes that inherit from `AActor` are prefixed by A.
  - Classes that inherit from `SWidget` are prefixed by S.
  - Classes that are abstract interfaces are prefixed by I.
  - Enums are prefixed by E.
  - Boolean variables must be prefixed by b (for example, `bPendingDestruction`, or `bHasFadedIn`).
  - Most other classes are prefixed by F, though some subsystems use other letters.







reference：https://docs.unrealengine.com/4.27/en-US/ProductionPipelines/DevelopmentSetup/CodingStandard/

11. 16

Daily Todo

ALL

- [ ] 
- [ ] 写可发射敌方墨水的敌人
- [ ] 研究一下boss





之后的task

- [ ] 寻找铁丝网素材（unpaintable / 潜墨可穿透）
- [ ]  给地图添加光源



胡

- [x] 写paintable/unpaintable基类

- [ ] 重构地图

- [x] 写敌方墨水球BP

- [ ] 写一个boss掉落的能力碎片bp

- [x] 在全局变量里添加布尔数组 存储boss的击败状态

  
  
  

吴

- [ ] 人物转向
- [ ] 

冯

- [ ] 写可移动平台

刘

- [ ] 可交互开关 / 控制大门打开
- [ ] 完善enemy





## To-dos

### 1. Character



#### 1.1 Basics

- [ ] **normal attack**：向前/后/上/下挥动笔刷，喷洒出剑气形状墨水，对途经敌人造成伤害（不可穿透），墨水在与可涂物体（墙壁、地板）接触后会产生溅射效果并附着。

- [x] Movement
- [x] dash
- [x] jump

#### 1.2 special ability （通过地图探索（或击败boss）后可获得的能力）

- [ ] 能力1  **潜墨**（变成其他形态在墨水中游动），通过该能力可以前往被铁丝网阻挡的区域
- [ ] 能力2  **喷射背包**（向下喷射出高压的墨水**） ：**可以在跳跃后打开喷射背包再跳一次（即二段跳）
- [ ] 能力3  **砸地** ：范围攻击 消耗法术值能力 可以在空中释放



- [ ] Inking System
- [ ] 
- [ ] Level interaction

### 2. Maps

#### interactive object

- [ ] switcher
- [ ] elevator controlled by switcher
- [ ] checkpoint
- [ ] Breakable objects （like hidden walls、shortcuts）
- [ ] 生命碎片（n个可以合成一个 增加生命上限）
- [ ] 墨水瓶碎片（n个可以合成一个 增加墨水槽上限）

#### 场景物

- [ ] 地图背景图 （可以从ai画图网站生成

### 3. UI

- [ ] 找一些好看的英文字体

- [ ] 主菜单
- [ ] Protagonist UI 
- [ ] 背包系统
- [ ] 整体地图以及区域地图绘制
- [ ] 小地图制作 实时显示在右上角
- [ ] npc对话系统

### 4. enemy

#### 4.1 boss

- [ ] 1 新手村boss设计

#### 4.2 normal enemy （respawned after interacting with checkpoints）

#### 4.3 elite enemy   (精英怪）

### 5. Music

#### 5.1 sound effect

## Contributors

<a href="https://github.com/jasonyxwu/Spiritual-Painter/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=jasonyxwu/Spiritual-Painter" />
</a>

