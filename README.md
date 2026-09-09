# Microduck 复刻 · SolidWorks 三维图纸与装配说明书

> **可编辑的 SolidWorks 源文件**（不是 STL），56 个零件与装配体，外加一份 21 页的装配安装说明书。
> 配套主仓：[**fanhao375/microduck-replica**](https://github.com/fanhao375/microduck-replica) —— 整机复刻、电路板与逆向分析都在那边。

<div align="center">
  <img src="组件图/00-microduck装配体.png" alt="microduck 装配体" width="300">
  <img src="组件图/00-microduck装配体爆炸图3.png" alt="microduck 爆炸图" width="360">
</div>

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
| **SolidWorks 源文件**（56 个，解压后 340 MB） | 👉 [**下载 `SolidWorks.zip`**](https://github.com/fanhao375/microduck-replica-cad/releases/latest/download/SolidWorks.zip)（341 MB，或到 [Releases](../../releases) 页） |
| **装配安装说明书**（21 页 PDF） | [`安装说明书/microduck装配安装说明书.pdf`](安装说明书/microduck装配安装说明书.pdf) |
| **组件图 / 爆炸图**（23 张） | [`组件图/`](组件图/) |

> **为什么源文件放 Releases 不放 git**：SolidWorks 是二进制格式，git 存它既不能 diff 也不能合并，
> 只会一版版往历史里堆 —— 改三次图仓库就上 1 GB，而且**历史删不掉**。
> 放 Release 附件则不计入仓库体积，更新时发新版即可，clone 这个仓库始终只有几 MB。

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
