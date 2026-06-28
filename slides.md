---
theme: apple-basic
background: https://source.unsplash.com/collection/94734566/1920x1080
title: 志愿者培训
info: |
  ## 志愿者培训
  WCA 魔方比赛志愿者操作指南
class: text-center
drawings:
  persist: false
transition: slide-left
mdc: true
duration: 30min
---

## WCA 魔方比赛

<div class="text-8xl font-bold my-10">
  志愿者培训
</div>

<div class="pt-8">
  <span @click="$slidev.nav.next" class="px-2 py-1 rounded cursor-pointer" hover="bg-white bg-opacity-10">
    GO <carbon:arrow-right />
  </span>
</div>

<div class="opacity-80 text-lg pt-8">
  作者：泉州魔方赛事组
</div>

---
transition: fade-out
layout: two-cols
---

# 目录

<div class="text-sm space-y-2">

**一：选手落座**

- 检查证件与成绩条
- 计时器使用教学

**二：打乱**

- 监督打乱员签名
- 保持遮挡盒关闭

**三：还原开始前**

- 计时器检查
- 观察阶段计时

**四：还原过程中**

- 观察违规行为
- 及格线与还原时限

</div>

::right::

<div class="text-sm space-y-2">

**五：还原结束**

- 成绩记录与签字

**判罚说明**

- 还原开始前判罚（①-④）
- 还原结束后判罚（⑤-⑧）

**特殊项目**

- 盲拧规则
- 单手规则
- 魔表规则
- 长项目规则

**其他情况**

- 录像设备
- 时间记录

</div>

---
layout: two-cols
---

# 一：选手落座

## 检查要点

- 确认选手参赛证件与成绩条信息一致
- 确认成绩条上是否印有十位 WCA ID
- WCA ID 格式：`2016WUJI01`（4 位数字 + 4 位字母 + 2 位数字）

<img src="./assets/scordcard.png" class="rounded-lg" alt="成绩条示例" />

::right::

## 需要检查的内容

1. **项目与轮次**是否与当前轮次一致
2. **选手姓名与编号**是否与参赛证件一致

## 特殊情况处理

若成绩条上**没有 WCA ID**，请先询问选手是否会使用计时器。

若选手不会使用，可用以下话术引导：

> 「双手手指放在计时器感应区；待红绿灯均亮起后松手开始计时；还原结束后，双手再次触碰感应区停止计时。」

---

# 一：选手落座

## 准备工作

- 若选手携带**多个魔方**，请询问本次使用哪一个，并将其带至打乱区
- 在成绩条**右下角**标注桌号
- 将成绩条夹在夹板上，与选手魔方、遮挡盒一并带至打乱区

<v-clicks>

- ✓ 检查证件
- ✓ 确认魔方
- ✓ 标记桌号
- ✓ 带到打乱区

</v-clicks>

---
layout: two-cols
---

# 二：打乱

## 打乱流程

- 请务必监督打乱员完成签名
- 请时刻留意对应打乱员，避免拿错成绩条或魔方

## 重要提醒

打乱后请保持**遮挡盒始终盖在魔方上**，不要打开，随后将其带回赛台。

<div class="mt-4 p-3 bg-yellow-100 dark:bg-yellow-900 rounded-lg text-sm leading-snug">
  ⚠️ 回到赛台后，请将遮挡盒连同内部魔方从夹板「滑」至选手面前，<strong class="text-red-600">切勿提前打开遮挡盒</strong>。
</div>

::right::

<div class="flex items-center justify-center h-full">

<img src="./assets/遮罩.png" class="max-w-full max-h-96 rounded-lg" alt="遮挡盒使用方法" />

</div>

---

# 三：还原开始前

## 计时器检查

检查计时器是否已开机并清零（应为 **2-PAD 模式**）

<img src="./assets/timer.png" class="h-40 mx-auto mt-4" alt="计时器按键说明" />

### 按键说明

- **开关键**：若显示屏未亮起，按此键开机
- **清零键**：每次还原开始前确认计时器已归零；若未归零，按此键清零（4-PAD 模式下需长按复位）

---

# 三：还原开始前

## 标准流程

<div class="grid grid-cols-2 gap-8">

<div>

### 1. 准备阶段

将带有遮挡盒的魔方置于选手面前，询问：

> **「准备好了吗？」**

选手确认准备就绪后，打开遮挡盒，并启动秒表开始观察计时。

</div>

<div>

### 2. 计时器操作

选手启动计时器（而非仅将手放上感应区）时，同步停止秒表。

### 秒表使用

- 左键：清零
- 右键：开始 / 暂停

<img src="./assets/stopwatch.jpg" class="h-32 mx-auto mt-4 rounded" alt="秒表" />

</div>

</div>

---

# 三：还原开始前

## 观察与计时

同时观察选手与秒表。注意：观察阶段选手**不得转动魔方**。

### 时间提示

<div class="grid grid-cols-3 gap-4 mt-6">

<div class="p-4 bg-blue-100 dark:bg-blue-900 rounded-lg text-center">

**8 秒**
<br>
提示「8 秒」

</div>

<div class="p-4 bg-blue-100 dark:bg-blue-900 rounded-lg text-center">

**12 秒**
<br>
提示「12 秒」

</div>

<div class="p-4 bg-orange-100 dark:bg-orange-900 rounded-lg text-center">

**≥ 17 秒**
<br>
记为 DNF（未完成）

</div>

</div>

<div class="mt-6 p-4 bg-green-100 dark:bg-green-900 rounded-lg">
  💡 观察时间在 15 至 17 秒之间时，**切勿提前归零秒表**。
</div>

<div class="mt-6 p-4 bg-green-100 dark:bg-green-900 rounded-lg">
  💡 提示时须读完整，如「8 秒」「12 秒」。
</div>

---

# 四：还原过程中

## 志愿者职责

<div class="text-xl my-8">

- 📵 **全程观察**选手是否有违规行为，<span class="text-red-600 font-bold">请勿使用手机！</span>
- 🤫 **请勿干扰**选手比赛
- 🙅 还原过程中若出现问题，请选手**自行处理**

</div>

<div class="grid grid-cols-2 gap-6 mt-8">

<div class="text-center">

**散架示例（普通项目）**

<img src="./assets/pop.png" class="h-40 mx-auto rounded-lg" alt="散架示例" />

</div>

<div class="text-center">

**散架示例（盲拧）**

<img src="./assets/pop-bld.png" class="h-40 mx-auto rounded-lg" alt="盲拧散架示例" />

</div>

</div>

---

# 四：还原过程中

## 重要概念

<div class="grid grid-cols-2 gap-8">

<div class="p-6 bg-blue-100 dark:bg-blue-900 rounded-lg">

### 及格线

选手须在该轮次截止前，至少有一次成绩优于（短于）及格线，方可继续参赛。

及格线标注在成绩条<strong>中间</strong>。
</div>

<div class="p-6 bg-purple-100 dark:bg-purple-900 rounded-lg">

### 还原时限

单次还原的最长时限；超时可直接叫停，并记为 DNF。

还原时限标注在成绩条<strong>最下方</strong>。
</div>

</div>

<div class="mt-6 text-center">

<img src="./assets/scordcard.png" class="h-48 mx-auto rounded" alt="成绩条示例" />

</div>

---

# 五：还原结束

## 成绩记录

还原结束后，如实抄录计时器上的**显示时间**及**判罚编号**。

### 计算公式

<div class="my-6 p-6 bg-green-100 dark:bg-green-900 rounded-lg text-center text-2xl font-bold">

最终时间 = 显示时间 + 判罚个数 × 2 秒

</div>

若还原未完成，或其他 DNF 情况，最终时间记为 **DNF**。

---
layout: default
---

# 五：还原结束

## 签字规则

<div class="grid grid-cols-2 gap-8">

<div>

### 裁判签字与选手签字

- **第一次还原**：须签 / 盖全名 ✓
- **所有有判罚的还原**：须签 / 盖全名 ✓
- **其余还原**：可签缩略名

</div>

<div>

<div class="mt-4 p-3 bg-yellow-100 dark:bg-yellow-900 rounded-lg text-sm">
  💡 年龄较小、尚未学会签名的选手，以及少数民族或外国友人姓名较长者，可不强制签署全名。
</div>

<div class="mt-4 p-3 bg-yellow-100 dark:bg-yellow-900 rounded-lg text-sm">
  💡 计时器显示多少，就抄写多少。
</div>

</div>

</div>

<div class="mt-6 flex justify-center">

<img src="./assets/scordcard.png" class="w-3/5 mx-auto rounded-lg" alt="签字示例" />

</div>

---
layout: two-cols
layoutClass: gap-8
---

# 说明一：判罚

## 还原开始前判罚（①-④）

<div class="space-y-3">

<div class="flex items-center gap-2">

<div class="text-2xl font-bold shrink-0">①</div>

<img src="./assets/plus-1.png" class="h-14 rounded" alt="判罚1" />

<div class="flex-1 text-sm leading-tight">

**未将魔方放置在垫子上**

选手开始前未将魔方放置在垫子上

</div>

</div>

<div class="flex items-center gap-2">

<div class="text-2xl font-bold shrink-0">②</div>

<img src="./assets/plus-2.png" class="h-14 rounded" alt="判罚2" />

<div class="flex-1 text-sm leading-tight">

**未用手指启动计时器**

选手开始时未用手指启动计时器

</div>

</div>

<div class="flex items-center gap-2">

<div class="text-2xl font-bold shrink-0">③</div>

<img src="./assets/plus-3.png" class="h-14 rounded" alt="判罚3" />

<div class="flex-1 text-sm leading-tight">

**启动时手接触魔方**

选手启动计时器时，手接触了魔方

</div>

</div>

<div class="flex items-center gap-2">

<div class="text-2xl font-bold shrink-0">④</div>

<img src="./assets/plus-4.png" class="h-14 rounded" alt="判罚4" />

<div class="flex-1 text-sm leading-tight">

**观察时间超时**

选手观察时间超过 15 秒且未满 17 秒

</div>

</div>

</div>

::right::

## 还原结束后判罚（⑤-⑧）

<div class="space-y-3">

<div class="flex items-center gap-2">

<div class="text-2xl font-bold shrink-0">⑤</div>

<img src="./assets/plus-5.png" class="h-14 rounded" alt="判罚5" />

<div class="flex-1 text-sm leading-tight">

**停止时手接触魔方**

还原结束、停止计时器时，手接触了魔方

</div>

</div>

<div class="flex items-center gap-2">

<div class="text-2xl font-bold shrink-0">⑥</div>

<img src="./assets/plus-6.png" class="h-14 rounded" alt="判罚6" />

<div class="flex-1 text-sm leading-tight">

**未正确停止计时器**

还原结束后，选手未以双手、手心向下平放的方式停止计时器

</div>

</div>

<div class="flex items-center gap-2">

<div class="text-2xl font-bold shrink-0">⑦</div>

<img src="./assets/plus-7.png" class="h-14 rounded" alt="判罚7" />

<div class="flex-1 text-sm leading-tight">

**停止后触碰魔方**

停止计时器后，选手触碰了魔方

<div class="text-xs text-red-600 mt-1">
⚠️ 若选手随后进行了转动，直接记为 DNF
</div>

</div>

</div>

<div class="flex items-center gap-2">

<div class="text-2xl font-bold shrink-0">⑧</div>

<img src="./assets/plus-8.png" class="h-14 rounded" alt="判罚8" />

<div class="flex-1 text-sm leading-tight">

**差一步未还原**

魔方差一步未还原（「一步」指外层转动）

</div>

</div>

</div>

---

# 关于「一步」的认定

魔方各层块转动超过临界角，即计为「一步」：
<div class="mt-6 text-center">

<img src="./assets/plus2.png" class="h-64 mx-auto rounded" alt="+2判罚图示" />

</div>

<div class="mt-6 space-y-2">

- 📅 **魔表**无需判断步数，只要未还原即记为 DNF
- ❓ 若无法判断，请举手联系现场代表或主办团队协助

</div>

---
transition: fade-out
---

# 说明二：盲拧

盲拧项目除以下要点外，其余流程与一般项目相同：

## 特殊流程

<div class="space-y-6">

<div class="p-6 bg-blue-100 dark:bg-blue-900 rounded-lg">

**① 自行开盖**：打乱后将魔方带回赛台，志愿者无需开盖；由选手启动计时器后自行开盖并开始计时

</div>

<div class="p-6 bg-purple-100 dark:bg-purple-900 rounded-lg">

**② 视线遮挡**：选手戴上眼罩并开始转动魔方后（戴眼罩前可继续记忆），使用挡板遮挡选手视线与魔方

</div>

</div>

<div class="mt-6 p-4 bg-yellow-100 dark:bg-yellow-900 rounded-lg">
  💡 多盲项目同时适用本说明与长项目说明中的相关要求。
</div>

---
transition: fade-out
---

# 说明三：单手

单手项目除以下要点外，其余流程与一般项目相同：

## 规则要点

<div class="space-y-6">

<div class="p-6 bg-blue-100 dark:bg-blue-900 rounded-lg">

**① 观察时可以使用双手**

</div>

<div class="p-6 bg-red-100 dark:bg-red-900 rounded-lg">

**② 只可使用同一只手**：启动计时器后，只能使用同一只手操作魔方；**中途不得换手**，否则记为 DNF

</div>

<div class="p-6 bg-green-100 dark:bg-green-900 rounded-lg">

**③ 掉落处理**：还原过程中若魔方掉落或散架，只允许用**一只手**捡回或恢复魔方

</div>

</div>

---
transition: fade-out
layout: two-cols
layoutClass: gap-12
---

# 说明四：魔表

魔表项目除以下要点外，其余流程与一般项目相同：

## 特殊规则

<div class="space-y-2 leading-tight">

<div class="p-3 bg-red-100 dark:bg-red-900 rounded-lg text-sm leading-snug">

**① 无编号 ⑧ 判罚**：魔表不设编号 ⑧ 判罚，只要未还原即记为 DNF

</div>

<div class="p-3 bg-blue-100 dark:bg-blue-900 rounded-lg text-sm leading-snug">

**② 允许操作立柱**：观察阶段允许选手操作立柱

</div>

<div class="p-3 bg-purple-100 dark:bg-purple-900 rounded-lg text-sm leading-snug">

**③ 检查背面**：还原完成后检查时，须一并检查背面

</div>

<div class="p-2 bg-yellow-100 dark:bg-yellow-900 rounded-lg text-center text-xs leading-snug">
  ⚠️ 检查时勿将指向 6 点的表针误判为已还原
</div>

</div>

::right::

<div class="flex flex-col gap-4 h-full justify-center items-center">

<div class="text-center">
<img src="./assets/clock-1.png" class="rounded max-h-44 mx-auto object-contain" alt="魔表" />
</div>

<div class="text-center">
<img src="./assets/clock-2.png" class="rounded max-h-44 mx-auto object-contain" alt="魔表" />
</div>

</div>

---
transition: fade-out
---

# 说明五：长项目

预计用时超过 10 分钟的项目，不使用计时器计时（计时器上限为 10 分钟），请使用手持秒表辅助计时。

## 计时方式

<div class="grid grid-cols-2 gap-8">

<div class="p-6 bg-green-100 dark:bg-green-900 rounded-lg">

**开始计时**

选手双手手心向下放在桌面，离开桌面时开始计时

</div>

<div class="p-6 bg-red-100 dark:bg-red-900 rounded-lg">

**停止计时**

选手双手手心向下拍在桌面时停止计时

</div>

</div>

---

# 说明五：长项目

## 记录格式

秒表的毫秒显示只有两位，抄写为 **「XX:XX.XX」** 格式即可。

<div class="p-6 bg-yellow-100 dark:bg-yellow-900 rounded-lg my-6">

例如：一小时应记为 `60:00.00`，而非 `1:00:00.00`。

</div>

---
layout: two-cols
layoutClass: gap-8
---

# 说明五：长项目

## 多盲项目

<div class="space-y-3">

<div class="p-3 bg-blue-100 dark:bg-blue-900 rounded-lg text-sm leading-snug">

**务必在选手确认开始时启动计时**（若使用秒表计时）。

</div>

<div class="p-3 bg-purple-100 dark:bg-purple-900 rounded-lg text-sm leading-snug">

**DNF 判断标准**

- ① 还原 1 个，尝试 2 个
- ② 还原 − (尝试 − 还原) < 0

</div>

</div>

::right::

<div class="flex flex-col justify-between h-full space-y-3">

<div class="flex-1 flex items-center justify-center">

<img src="./assets/image-20260225160322321.png" class="max-w-full h-auto rounded-lg object-contain" alt="多盲成绩单" />

</div>

<div class="space-y-3">

<div class="p-3 bg-green-100 dark:bg-green-900 rounded-lg text-sm leading-snug">

**还原时限**

- ① 尝试 > 5：60 min
- ② 尝试 ≤ 5：尝试 × 10 min

</div>

<div class="p-2 bg-yellow-100 dark:bg-yellow-900 rounded-lg text-xs leading-snug">
  💡 若选手选择使用计时器，成绩仍写三位小数；考虑到用时可能超过 10 分钟，建议同步启动秒表。
</div>

</div>

</div>

---
transition: fade-out
---

# 说明六：其他情况

## 录像设备

<div class="space-y-4">

<div class="p-4 bg-blue-100 dark:bg-blue-900 rounded-lg">

若选手使用相机、手机或其他录影设备，须确保选手**无法看到屏幕**（可将屏幕背对选手，或直接遮挡屏幕）。

</div>

<div class="p-4 bg-purple-100 dark:bg-purple-900 rounded-lg">

若手机不用于录像，须**摄像头朝上**放置在垫子外。

</div>

<div class="p-4 bg-red-100 dark:bg-red-900 rounded-lg">

选手全程**禁止佩戴耳机**（请注意区分耳罩与头戴式耳机，耳罩可佩戴）。

</div>

</div>

---

# 说明六：其他情况

## 时间记录

<div class="p-6 bg-yellow-100 dark:bg-yellow-900 rounded-lg my-6">

抄写时间时，请务必抄录**计时器屏幕显示的时间**，而非计时器背面的时间，并按 **「分钟:秒钟.毫秒」** 格式记录，例如：`12:34.56`。

</div>

## 下次尝试处理

若选手未还原（DNF / DNS / 备用打乱等）且需进行下一次尝试，请让选手**自行还原魔方**后，再带至打乱区重新打乱。

<div class="mt-6 p-4 bg-orange-100 dark:bg-orange-900 rounded-lg">
  💡 若监督代表给出备用打乱，建议在打乱时提醒打乱员使用备打 1 / 备打 2。
</div>

---
layout: center
class: text-center
---

# 重要提醒

<div class="text-xl my-12">

遇到无法自行处理的情况，请**保护好现场**，举手示意代表或主办团队介入处理。

</div>

<div class="text-4xl">
  🙋‍♂️
</div>

---
layout: center
class: text-center
---

# 谢谢

## 感谢各位志愿者

<div class="mt-12 text-lg opacity-75">

如有疑问，请及时联系主办团队或代表。

</div>

---
layout: center
---

# 引用

<div class="text-left text-sm max-w-xl mx-auto space-y-4 mt-8 opacity-90">

<div>

**WCA 官方规则（Regulations）**

[https://www.worldcubeassociation.org/regulations/](https://www.worldcubeassociation.org/regulations/)

</div>

<div>

**WCA 官方规则（中文版）**

[https://www.worldcubeassociation.org/regulations/translations/chinese/](https://www.worldcubeassociation.org/regulations/translations/chinese/)

</div>


<div class="opacity-75 pt-2">

本培训内容依据 WCA 官方规则整理，具体执裁以现场代表或主办团队指示为准。

</div>

<div class="pt-4 space-y-2">

感谢 **北京魔方赛事组委会** 与 **泉州魔方赛事组** 对本培训材料的支持。

如有问题，请联系：吴嘉顺 jwu@worldcubeassociation.org

</div>

</div>
