# Microduck 复刻 · SolidWorks 三维图纸与装配说明书

> **可编辑的 SolidWorks 源文件**（不是 STL），外加一份 21 页的装配安装说明书。**两个版本**：
> **v2.0 飞特 HD-1910 版**（2026-09-12，已装出实物）和 **v1.1 原版 XL330 版**（2026-09-15，踝 / 小腿 / 脚同步改了）。
> 配套主仓：[**fanhao375/microduck-replica**](https://github.com/fanhao375/microduck-replica) —— 整机复刻、电路板与逆向分析都在那边。

> 📦 **压缩包在 [Releases 页](../../releases)（页面右边栏），不在上面的文件列表里。** 374 MB 的 SolidWorks 不适合塞进 git。
> 🖨️ **只想打印、不想看图** → [拓竹 MakerWorld · microduck 飞特版](https://makerworld.com.cn/zh/models/2963569-microduck#profileId-3478428)，一键切片（机械行者Robo 上传，就是这套飞特版）。

<div align="center">
  <img src="assets/飞特版装机-正面.jpg" alt="飞特 HD-1910 版装机实物" width="360">
  <br><sub>2026-09-13 · 飞特 HD-1910 版装出来了，15 颗全在位</sub>
</div>

<div align="center">
  <img src="组件图/00-microduck装配体.png" alt="microduck 装配体" width="300">
  <img src="组件图/00-microduck装配体爆炸图3.png" alt="microduck 爆炸图" width="360">
</div>

---

## 两个版本，选一个下

| | 原版 · XL330 · **v1.1** | 飞特 · HD-1910 · **v2.0** |
|---|---|---|
| **舵机** | Dynamixel XL330-M288 | 飞特 HD-1910-C001 |
| **文件** | 57 个 SolidWorks，无后缀 | 62 个 SolidWorks + 9 个 STEP，`-FT` 后缀 |
| **差别** | — | **舵盘凸出**，8 个配合件改了（[改了什么](#飞特-hd-1910-版改了什么)） |
| **打印** | 主仓 [`print/`](https://github.com/fanhao375/microduck-replica/tree/master/print) 上游 STL | [`打印/` 3mf](打印/) · [拓竹一键打印](https://makerworld.com.cn/zh/models/2963569-microduck#profileId-3478428) |
| **实物** | — | 已装出（上图） |
| **下载** | [`SolidWorks-XL330-v1.1.zip`](https://github.com/fanhao375/microduck-replica-cad/releases/download/v1.1/SolidWorks-XL330-v1.1.zip) 333 MB | [`SolidWorks-FT.zip`](https://github.com/fanhao375/microduck-replica-cad/releases/latest/download/SolidWorks-FT.zip) 373 MB |

两版的踝 / 小腿 / 脚在 2026-09-15 同步成了一套设计；装配说明书和组件图两版通用。

---

## 图纸作者：机械行者Robo

**这套三维图纸和安装说明书，全部由「机械行者Robo」建模、整理、编写。**

他还在做装配视频，有装配上的问题去他那儿留言最快：

<table>
<tr>
<td align="center" width="50%">
  <img src="assets/小红书-机械行者Robo.jpg" alt="小红书 机械行者Robo" width="230"><br>
  <b>小红书 · 机械行者Robo</b><br>
  <sub>小红书号 270594280</sub>
</td>
<td align="center" width="50%">
  <img src="assets/抖音-机械行者Robo.jpg" alt="抖音 机械行者Robo" width="230"><br>
  <b>抖音 · 机械行者Robo</b><br>
  <sub>抖音号 1852366168 —— 「人人可做机器人」</sub>
</td>
</tr>
</table>

> 觉得图纸有用的话，去关注一下他 —— 这套东西建模和整理的工作量不小，而且是免费放出来的。

---

## 下载

| 要什么 | 在哪 |
|---|---|
| **飞特 HD-1910 版源文件**（v2.0 · 62 个 SolidWorks + 9 个 STEP，解压 435 MB） | 👉 [**下载 `SolidWorks-FT.zip`**](https://github.com/fanhao375/microduck-replica-cad/releases/latest/download/SolidWorks-FT.zip) |
| **只要改动件的 STEP**（v2.0 · 9 个，15 MB） | 👉 [**下载 `STEP-changed-parts-FT.zip`**](https://github.com/fanhao375/microduck-replica-cad/releases/latest/download/STEP-changed-parts-FT.zip) —— 不用 SolidWorks 也能开 |
| **原版 XL330 版源文件**（v1.1 · 57 个 SolidWorks，解压 348 MB） | 👉 [**下载 `SolidWorks-XL330-v1.1.zip`**](https://github.com/fanhao375/microduck-replica-cad/releases/download/v1.1/SolidWorks-XL330-v1.1.zip)（[v1.0 旧版](../../releases/tag/v1.0) 仍可下） |
| **装配 BOM**（机械行者Robo 整理，35 个打印件 + 16 个外购件，含材料、数量，**2026-09-16 起带轴承和螺丝的采购链接**） | [`BOM/装配BOM-机械行者Robo-2026-09-16-带采购链接.xlsx`](BOM/装配BOM-机械行者Robo-2026-09-16-带采购链接.xlsx)，下面有校对过的表 |
| **装配安装说明书**（21 页 PDF） | [`安装说明书/microduck装配安装说明书.pdf`](安装说明书/microduck装配安装说明书.pdf) |
| **组件图 / 爆炸图**（23 张） | [`组件图/`](组件图/) |
| 🖨️ **打印工程文件**（Bambu Studio `.3mf`，4.9 MB，2026-09-15 版） | [`打印/microduck-飞特版-BambuStudio.3mf`](打印/microduck-飞特版-BambuStudio.3mf) —— **就在仓库里，直接下**。5 个盘、52 个件、P2S / PLA / 0.2 层高，跟拓竹上那个是同一份 |
| 🖨️ **拓竹一键打印** | [MakerWorld · microduck 飞特版](https://makerworld.com.cn/zh/models/2963569-microduck#profileId-3478428) —— 有拓竹打印机的直接云切片 |

> **为什么源文件放 Releases 不放 git**：SolidWorks 是二进制格式，git 存它既不能 diff 也不能合并，
> 只会一版版往历史里堆 —— 改三次图仓库就上 1 GB，而且**历史删不掉**。
> 放 Release 附件则不计入仓库体积，更新时发新版即可，clone 这个仓库始终只有几 MB。

---

## 飞特 HD-1910 版改了什么

原版用 Dynamixel XL330，本仓库主仓走飞特 HD-1910（更便宜、力矩大 2.5 倍、电压额定匹配 —— 见[主仓执行器选型](https://github.com/fanhao375/microduck-replica/blob/master/docs/执行器选型.md)）。
**两款舵机外形接近但舵盘不一样：HD-1910 的舵盘是凸出来的，XL330 是凹进去的。** 所有跟舵盘配合的件都得改：

| 改动件 | 为什么 |
|---|---|
| `left_upper_leg` / `right_upper_leg` 左右上腿 | 髋 pitch 和膝的舵盘位 |
| `leg` 小腿 | 膝和踝的舵盘位 |
| `trunk_base` 躯干底座 | 髋 yaw 舵机安装位 |
| `yaw2roll` 偏航转横滚 | 髋 yaw 舵盘 → 髋 roll 舵机 |
| `bearing_roll` 轴承滚轮 | 髋 roll 轴承座 |
| `01-upper_leg_rigidity_plate` 上腿加固板 | 跟上腿一起改 |
| `99-yaw_roll_motion` 偏航横滚运动 | 头部 yaw/roll，`-F` 和 `-FT` 两个变体 |

**文件命名**：所有件带 `-FT` 后缀（FT = 飞特）。没改的件也带 `-FT`，是为了整套装配体引用一致 —— 27 个件跟 v1.0 内容一样，只是改了名。

**多出来的**：`HD-1910-c001-dan / -shuang`（单盘 / 双盘舵机模型）、`舵机比较.SLDASM`（两款舵机并排对比）、`飞特电机资料1/`（飞特给的 STEP / DWG / 规格图）。

⚠️ 装配说明书 PDF 和组件图**还是 v1.0 的**，装配顺序和步骤不变，只是舵机换了。

---

## XL330 原版 v1.1 改了什么（2026-09-15）

飞特版改踝、小腿、脚那一片时顺手把原版也改了，两版这一区域现在是同一套设计：

```
改了   05_左小腿 · 06_左踝脚 · 14_右小腿 · 15_右踝脚 · 10_头部总成
       ankle_left 脚踝左 · foot_left 左脚 · leg 腿部
新增   deep groove ball bearings gb（轴承模型）
改名   00-microduck装配体 → 00-microduck装配体 XL330-288舵机版本
       ankle_right_脚踝右 → ankle_right脚踝右
```

46 个件跟 v1.0 一样。

---

## 装配 BOM

[`BOM/装配BOM-机械行者Robo-2026-09-16-带采购链接.xlsx`](BOM/装配BOM-机械行者Robo-2026-09-16-带采购链接.xlsx) 是机械行者Robo 按装配体整理的，2026-09-16 版给轴承和螺丝加了他实际下单的淘宝 / 天猫链接（小白照着买就行）。
表里电子件的型号和数量 2026-09-17 由 fanhao375 按主仓查证过的事实校过一遍（电池 NP-F550、舵机 15、`imu_to_dxl` 1、舵机线 17），下面这张表照它排。只有一处跟表不同：

| 表里 | 这里 | 依据 |
|---|---|---|
| 轮辋 / 轮胎 / 滚轮叶片 | 标为**轮滑变体，走路不用** | 上游 `变体-轮滑/`，只有做轮滑功能才打 |

### 一、3D 打印件（35 项）

| # | 零件 | 文件 | 材料 | 数量 | 备注 |
|---|---|---|---|---|---|
| 1 | 头部上壳 | `top_head_shell` | PLA | 1 | |
| 2 | 头部下壳 | `bottom_head_shell` | PLA | 1 | |
| 3 | 面部零件 | `face_part` | PLA | 1 | |
| 4 | 下巴 | `jaw` | PLA | 1 | |
| 5 | 软下巴 | `jaw_soft` | **TPU** | 1 | 软性件 |
| 6 | 软嘴顶部 | `soft_mouth_top` | **TPU** | 1 | 软性件 |
| 7 | 眼睛 | `noenoeil` | PLA | 1 | |
| 8 | 颈部 | `neck` | PLA | 2 | 可换铝合金增强 |
| 9 | 颈部俯仰 | `neck_pitch` | PLA | 1 | |
| 10 | 躯干底座 | `trunk_base` | PLA | 1 | 可换铝合金增强 |
| 11 | 左壳 | `left_shell` | PLA | 1 | |
| 12 | 右壳 | `right_shell` | PLA | 1 | |
| 13 | 髋部左 | `hip_l` | PLA | 2 | |
| 14 | 偏航转横滚 | `yaw2roll` | PLA | 1 | |
| 15 | 偏航横滚运动 | `yaw_roll_motion` | PLA | 1 | |
| 16 | 腿部 | `leg` | PLA | 2 | |
| 17 | 左上腿 | `left_upper_leg` | PLA | 1 | |
| 18 | 右上腿 | `right_upper_leg` | PLA | 1 | |
| 19 | 上腿加固板 | `upper_leg_rigidity_plate` | PLA | 2 | 可换铝合金增强 |
| 20 | 左脚 | `foot_left` | PLA | 1 | |
| 21 | 右脚 | `foot_right` | PLA | 1 | |
| 22 | 左脚底 | `sole_left` | PLA | 1 | |
| 23 | 右脚底 | `sole_right` | PLA | 1 | |
| 24 | 脚踝左 | `ankle_left` | PLA | 1 | |
| 25 | 脚踝右 | `ankle_right` | PLA | 1 | |
| 26 | 脚踝左 V1 | `ankle_l_v1` | PLA | 1 | 备选，与 24 二选一 |
| 27 | 脚踝右 V1 | `ankle_r_v1` | PLA | 1 | 备选，与 25 二选一 |
| 28 | 轮辋 | `rim` | PLA | 4 | **轮滑变体，走路不用** |
| 29 | 轮胎 | `tire` | TPU | 4 | **轮滑变体，走路不用** |
| 30 | 滚轮叶片 | `roller_blade` | PLA | 2 | **轮滑变体，走路不用** |
| 31 | M12 镜头座 | `m12_lens_holder` | PLA | 1 | |
| 32 | 电机支架 | `motor_support` | PLA | 1 | |
| 33 | 电源支架 | `power_support` | PLA | 1 | |
| 34 | 香蕉形 PCB 锁扣 | `banana_pcb_locker` | PLA | 1 | |
| 35 | 轴承滚轮 | `bearing_roll` | PLA | 2 | 可换铝合金增强 |

### 二、外购件（16 项 + 螺纹胶）

| # | 件 | 数量 | 备注 |
|---|---|---|---|
| 36 | Radxa Zero 3W 主控 | 1 | [主仓电控采购清单](https://github.com/fanhao375/microduck-replica/blob/master/docs/电控采购清单.md) |
| 37 | RPI Robot HAT 电路板 | 1 | 官方开源，嘉立创打样；或[不打 HAT 飞线](https://github.com/fanhao375/microduck-replica/blob/master/docs/不打HAT.md) |
| 38 | imu_to_dxl 电路板 | **1** | 主仓自绘，[hardware/imu_to_dxl](https://github.com/fanhao375/microduck-replica/tree/master/hardware/imu_to_dxl) |
| 39 | 舵机 | **15** | XL330-M288 或飞特 **HD-1910-C001** 二选一；13 单盘 + 2 双盘 |
| 40 | 舵机线缆 | 17 | 舵机自带一根，调试和总线分支要另买；飞特 2.0 mm、Dynamixel 2.5 mm |
| 41 | 电池 | 1 | **NP-F550**，2S |
| 42 | 电池座 | 1 | NP-F 电池仓 + 取电扣板 |
| 43 | IMX219 摄像头 | 1 | |
| 44 | 扬声器 | 1 | 走 HAT 音频才要 |
| 45 | 轴承 10×15×3 | 3 | 机械行者Robo 买的：[淘宝 963037239628](https://item.taobao.com/item.htm?id=963037239628&skuId=6069280211062)（选 10×15×3 那个 SKU） |
| 46 | 轴承 16×22×4 | 11 | 机械行者Robo 买的：[天猫 978199812185](https://detail.tmall.com/item.htm?id=978199812185&skuId=6245616343131) |
| 47 | 轴承 6×12×3 | 2 | 轮滑变体用，走路不用买。同一家：[淘宝 963037239628](https://item.taobao.com/item.htm?id=963037239628&skuId=6068333830994)（选 6×12×3） |
| 48 | 螺丝 M2×5 | 若干 | 机械行者Robo 买的：[天猫 637524754721](https://detail.tmall.com/item.htm?id=637524754721&skuId=5802482233046)；每种多少颗见[主仓紧固件反推](https://github.com/fanhao375/microduck-replica/blob/master/docs/紧固件反推.md) |
| 49 | 螺丝 M2×6 | 若干 | 同一家：[天猫 637524754721](https://detail.tmall.com/item.htm?id=637524754721&skuId=5802482233047) |
| 50 | 螺丝 M2.5×6 | 若干 | 同一家：[天猫 637524754721](https://detail.tmall.com/item.htm?id=637524754721&skuId=61808188996) |
| 51 | 螺纹胶 | 1 | 乐泰 243，原表没列，装配说明书要求 |

---

## 打印

**[`打印/microduck-飞特版-BambuStudio.3mf`](打印/microduck-飞特版-BambuStudio.3mf)** —— 机械行者Robo 排好盘的 Bambu Studio 工程，跟[拓竹 MakerWorld](https://makerworld.com.cn/zh/models/2963569-microduck#profileId-3478428) 上传的是同一份。

| 项 | 值 |
|---|---|
| 打印机 | Bambu Lab **P2S**，0.4 喷嘴 |
| 耗材 | PLA Basic |
| 层高 | 0.2 mm |
| 盘数 | **5 盘**，52 个对象 —— 飞特版全部打印件 |

<table>
<tr>
<td align="center"><img src="打印/盘1.png" width="180"><br><sub>盘 1</sub></td>
<td align="center"><img src="打印/盘2.png" width="180"><br><sub>盘 2</sub></td>
<td align="center"><img src="打印/盘3.png" width="180"><br><sub>盘 3</sub></td>
<td align="center"><img src="打印/盘4.png" width="180"><br><sub>盘 4</sub></td>
<td align="center"><img src="打印/盘5.png" width="180"><br><sub>盘 5</sub></td>
</tr>
</table>

**怎么用**：Bambu Studio 打开 → 切片 → 打印，五盘依次来。**不是拓竹打印机**也能用：任何切片软件都能导入 `.3mf` 拿到模型和排盘，只是打印参数要按自己的机器重设。

耗材、螺丝、热熔螺母的采购在[主仓机械采购清单](https://github.com/fanhao375/microduck-replica/blob/master/docs/机械采购清单.md)。

---

## 组件清单（15 个）

| 序号 | 组件 | 英文 | 位置 / 功能 |
|---|---|---|---|
| 01 | 躯干主体 | Torso | 机身主体，**全部组件的装配基准件**，承载左/右腿、颈部与控制器 |
| 02 | 左髋 | Left Hip | 左腿根部髋关节（Pitch），腿部前后摆动 |
| 03 | 左髋 Roll | Left Hip Roll | 左腿髋部横滚关节，腿部侧向摆动 |
| 04 | 左大腿 | Left Thigh | 连接髋关节与小腿 |
| 05 | 左小腿 | Left Calf | 连接大腿与踝关节 |
| 06 | 左踝脚 | Left Ankle & Foot | 踝关节及脚部，足部转动与支撑 |
| 07 | 颈根 | Neck Base | 颈部与机身连接处的旋转底座（Yaw） |
| 08 | 颈俯仰 | Neck Pitch | 颈部俯仰摆动关节 |
| 09 | 头 Yaw / Roll | Head Yaw / Roll | 头部水平摆动与横滚关节 |
| 10 | 头部总成 | Head Assembly | 头部完整组件，含外壳、摄像头等 |
| 11 | 右髋 | Right Hip | 与 02 镜像对称 |
| 12 | 右髋 Roll | Right Hip Roll | 与 03 镜像对称 |
| 13 | 右大腿 | Right Thigh | 与 04 镜像对称 |
| 14 | 右小腿 | Right Calf | 与 05 镜像对称 |
| 15 | 右踝脚 | Right Ankle & Foot | 与 06 镜像对称 |

## 装配顺序

**按编号 01 → 15 依次装，就是推荐的整机装配顺序：**

```
1.  01           躯干主体 —— 作为整机基准先行固定
2.  02 → 06      左腿   左髋 → 左髋Roll → 左大腿 → 左小腿 → 左踝脚
3.  07 → 10      颈头   颈根 → 颈俯仰 → 头Yaw/Roll → 头部总成
4.  11 → 15      右腿   右髋 → 右髋Roll → 右大腿 → 右小腿 → 右踝脚
```

**每一步的详细步骤、配图和注意事项，见** [装配安装说明书 PDF](安装说明书/microduck装配安装说明书.pdf)。

---

## 组件图

<table>
<tr>
<td align="center"><img src="组件图/01-躯干主体.png" width="200"><br><sub><b>01</b> 躯干主体</sub></td>
<td align="center"><img src="组件图/02-左髋.png" width="200"><br><sub><b>02</b> 左髋</sub></td>
<td align="center"><img src="组件图/03-左髋roll.png" width="200"><br><sub><b>03</b> 左髋 Roll</sub></td>
<td align="center"><img src="组件图/04-左大腿.png" width="200"><br><sub><b>04</b> 左大腿</sub></td>
</tr>
<tr>
<td align="center"><img src="组件图/05-左小腿.png" width="200"><br><sub><b>05</b> 左小腿</sub></td>
<td align="center"><img src="组件图/06-左踝脚.png" width="200"><br><sub><b>06</b> 左踝脚</sub></td>
<td align="center"><img src="组件图/07-颈根.png" width="200"><br><sub><b>07</b> 颈根</sub></td>
<td align="center"><img src="组件图/08-颈俯仰.png" width="200"><br><sub><b>08</b> 颈俯仰</sub></td>
</tr>
<tr>
<td align="center"><img src="组件图/09-头yawroll.png" width="200"><br><sub><b>09</b> 头 Yaw/Roll</sub></td>
<td align="center"><img src="组件图/10-头部总成.png" width="200"><br><sub><b>10</b> 头部总成</sub></td>
<td align="center"><img src="组件图/11-右髋.png" width="200"><br><sub><b>11</b> 右髋</sub></td>
<td align="center"><img src="组件图/12-右髋.png" width="200"><br><sub><b>12</b> 右髋 Roll</sub></td>
</tr>
<tr>
<td align="center"><img src="组件图/13-右大腿.png" width="200"><br><sub><b>13</b> 右大腿</sub></td>
<td align="center"><img src="组件图/14-右小腿.png" width="200"><br><sub><b>14</b> 右小腿</sub></td>
<td align="center"><img src="组件图/15-右踝脚.png" width="200"><br><sub><b>15</b> 右踝脚</sub></td>
<td align="center"><img src="组件图/10-头部总成爆炸2.png" width="200"><br><sub>头部总成（爆炸）</sub></td>
</tr>
</table>

<div align="center">
  <img src="组件图/零件明预览.png" alt="零件总览" width="820"><br>
  <sub>全部零件总览</sub>
</div>

---

## 文件清单

### 装配体（16 个 `.SLDASM`）

`00-microduck装配体` 是总装，下面 15 个是分组件：

```
00-microduck装配体      70.3 MB      08_颈俯仰               0.3 MB
01_躯干主体             20.5 MB      09_头yaw-roll          0.7 MB
02_左髋yaw-roll         2.5 MB      10_头部总成             22.2 MB
03_左髋roll             3.8 MB      11_右髋yaw-roll         2.5 MB
04_左大腿               1.9 MB      12_右髋roll             3.8 MB
05_左小腿               1.9 MB      13_右大腿               2.0 MB
06_左踝脚               9.3 MB      14_右小腿               1.8 MB
07_颈根                 0.1 MB      15_右踝脚               9.3 MB
```

### 零件（40 个 `.SLDPRT`）

| 类别 | 零件 |
|---|---|
| **躯干 / 外壳** | `trunk_base_躯干底座` · `left_shell_左壳` · `right_shell_右壳` · `power_support_电源支架` · `banana_pcb_locker_香蕉形PCB锁扣` |
| **腿** | `leg_腿部` · `left_upper_leg_左上腿` · `right_upper_leg_右上腿` · `hip_l_髋部左` · `yaw2roll_偏航转横滚` · `yaw_roll_motion_偏航横滚运动` · `01-upper_leg_rigidity_plate_上腿加固板` |
| **踝 / 脚** | `ankle_left_脚踝左` · `ankle_right_脚踝右` · `foot_left_左脚` · `foot_right_右脚` · `sole_left_左脚底` · `sole_right_右脚底` |
| **颈 / 头** | `neck_颈部` · `neck_pitch_颈部俯仰` · `top_head_shell_头部上壳` · `bottom_head_shell_头部下壳` · `face_part_面部零件` · `jaw_下巴` · `jaw_soft_软下巴` · `soft_mouth_top_软嘴顶部` · `noenoeil_眼睛` |
| **摄像头** | `m12_lens_holder_M12镜头座` · `lens_镜头` |
| **电路板** | `3D_PCB1_2026-09-08`（imu_to_dxl，2026-09-08 版）· `elec_rpi_robot_hat_pcb_树莓派机器人HAT电路板` · `pcb__raspberry_pi_zero_2_w_树莓派Zero2W电路板` |
| **标准件 / 外购** | `舵机xl330-288` · `xl330-m288-t1` · `xl330-m288-t2` · `轴承16×22×4` · `bearing_roll_轴承滚轮` · `M2铜柱` · `motor_support_电机支架` · `np_f970_NPF970电池` |

### 两处命名要留意

- **`np_f970_NPF970电池`** —— 文件名沿用了上游的 `np_f970`，但**实物是 NP-F550**。
  主仓实测上游网格包围盒为 **70.8 × 38.6 × 20.6 mm**，正是 F550/F570 的尺寸；真 NP-F970 厚约 60 mm，
  **买错装不进去，而且 300 g 会吃掉整机预算的三分之一**。详见
  [主仓 BOM 的电池型号勘误](https://github.com/fanhao375/microduck-replica/blob/master/BOM.md)。
- **`pcb__raspberry_pi_zero_2_w`** —— 同样是上游的占位命名，**实机主控是 Radxa Zero 3W**（RK3566），
  只是外形同为 Pi Zero。见[主仓的硬件方案逆向](https://github.com/fanhao375/microduck-replica/blob/master/docs/硬件方案逆向.md)。

---

## 通用注意事项（摘自说明书）

- 装配前对照 BOM 清点零件数量与规格，确认 **M2 / M2.5** 螺丝与紧固件齐全
- **舵机类关节件：装配前先通电归中位再锁紧**，避免行程偏移
- 螺丝**对角分步预紧**，避免单边受力导致零件变形；塑料件切勿过度锁紧
- **左右对称件（髋 / 大腿 / 小腿 / 踝脚）务必区分左右**，切勿装反
- 线缆统一固定、预留关节活动余量，严禁压线、夹线、缠绕
- 每完成一个活动关节，转动测试一次，检查是否干涉、卡滞、异响
- 首次通电前检查所有电气连接、绝缘与极性

**推荐工具**：十字/内六角螺丝刀 · 镊子 · 螺纹胶 · 舵机中位调试工具或控制板。

---

## 声明与许可

> ⚠️ **这是第三方复刻件，不是官方设计。** 与 Pollen Robotics 无隶属关系，未获其背书。

本套图纸依据 [`pollen-robotics/microduck_rl`](https://github.com/pollen-robotics/microduck_rl) 公开发布的
STL 网格重建为可编辑的 SolidWorks 参数模型。上游 3D 模型许可为 **CC BY-NC-SA**，
因此本仓库的图纸作为衍生作品同样以 **[CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/deed.zh)** 发布：
**署名 · 非商业性使用 · 相同方式共享**。

- **图纸与说明书著作权归「机械行者Robo」**，转载与二次分发请保留署名
- 文档文字部分同样按 CC BY-NC-SA 4.0 发布
- Microduck 是 Pollen Robotics 的商业产品，本仓库不提供任何官方支持

**发现问题**请开 [issue](../../issues)，或到上面两个账号留言。
