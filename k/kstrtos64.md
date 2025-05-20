# Function: <code>kstrtos64</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-sysfs.c (ffffffff8141a033)
Location: include/linux/kernel.h:349
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_wb_lat_store
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-sysfs.c (ffffffff81427fa3)
Location: include/linux/kernel.h:362
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_wb_lat_store
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-sysfs.c (ffffffff81453063)
Location: include/linux/kernel.h:399
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_wb_lat_store
```
```
In drivers/rtc/rtc-sysfs.c (ffffffff8178d875)
Location: include/linux/kernel.h:399
Inline: True
Inline callers:
  - drivers/rtc/rtc-sysfs.c:wakealarm_store
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-sysfs.c (ffffffff81486505)
Location: include/linux/kernel.h:415
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_wb_lat_store
```
```
In drivers/rtc/rtc-sysfs.c (ffffffff817cfe95)
Location: include/linux/kernel.h:415
Inline: True
Inline callers:
  - drivers/rtc/rtc-sysfs.c:wakealarm_store
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/ntp.c (ffffffff828afa80)
Location: include/linux/kernel.h:448
Inline: True
Inline callers:
  - kernel/time/ntp.c:ntp_tick_adj_setup
```
```
In block/blk-sysfs.c (ffffffff814a07d3)
Location: include/linux/kernel.h:448
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_wb_lat_store
```
```
In drivers/rtc/sysfs.c (ffffffff817f6e25)
Location: include/linux/kernel.h:448
Inline: True
Inline callers:
  - drivers/rtc/sysfs.c:wakealarm_store
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/ntp.c (ffffffff828c8613)
Location: include/linux/kernel.h:407
Inline: True
Inline callers:
  - kernel/time/ntp.c:ntp_tick_adj_setup
```
```
In block/blk-sysfs.c (ffffffff814cedc5)
Location: include/linux/kernel.h:407
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_wb_lat_store
```
```
In drivers/rtc/sysfs.c (ffffffff81837b2f)
Location: include/linux/kernel.h:407
Inline: True
Inline callers:
  - drivers/rtc/sysfs.c:wakealarm_store
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/ntp.c (ffffffff828d0bf1)
Location: include/linux/kernel.h:411
Inline: True
Inline callers:
  - kernel/time/ntp.c:ntp_tick_adj_setup
```
```
In block/blk-sysfs.c (ffffffff814e8135)
Location: include/linux/kernel.h:411
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_wb_lat_store
```
```
In drivers/rtc/sysfs.c (ffffffff8186949f)
Location: include/linux/kernel.h:411
Inline: True
Inline callers:
  - drivers/rtc/sysfs.c:wakealarm_store
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/ntp.c (ffffffff82cf1b33)
Location: include/linux/kernel.h:400
Inline: True
Inline callers:
  - kernel/time/ntp.c:ntp_tick_adj_setup
```
```
In block/blk-sysfs.c (ffffffff81547045)
Location: include/linux/kernel.h:400
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_wb_lat_store
```
```
In drivers/rtc/sysfs.c (ffffffff8193d0ff)
Location: include/linux/kernel.h:400
Inline: True
Inline callers:
  - drivers/rtc/sysfs.c:wakealarm_store
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/ntp.c (ffffffff82fde5ce)
Location: include/linux/kernel.h:252
Inline: True
Inline callers:
  - kernel/time/ntp.c:ntp_tick_adj_setup
```
```
In block/blk-sysfs.c (ffffffff81562d35)
Location: include/linux/kernel.h:252
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_wb_lat_store
```
```
In drivers/rtc/sysfs.c (ffffffff8194310f)
Location: include/linux/kernel.h:252
Inline: True
Inline callers:
  - drivers/rtc/sysfs.c:wakealarm_store
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/ntp.c (ffffffff831e90f8)
Location: include/linux/kernel.h:262
Inline: True
Inline callers:
  - kernel/time/ntp.c:ntp_tick_adj_setup
```
```
In block/blk-sysfs.c (ffffffff8156b4e5)
Location: include/linux/kernel.h:262
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_wb_lat_store
```
```
In drivers/rtc/sysfs.c (ffffffff8192692f)
Location: include/linux/kernel.h:262
Inline: True
Inline callers:
  - drivers/rtc/sysfs.c:wakealarm_store
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/ntp.c (ffffffff832cd6a5)
Location: include/linux/kstrtox.h:79
Inline: True
Inline callers:
  - kernel/time/ntp.c:ntp_tick_adj_setup
```
```
In block/blk-sysfs.c (ffffffff815cf765)
Location: include/linux/kstrtox.h:79
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_wb_lat_store
```
```
In drivers/rtc/sysfs.c (ffffffff819c986f)
Location: include/linux/kstrtox.h:79
Inline: True
Inline callers:
  - drivers/rtc/sysfs.c:wakealarm_store
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/ntp.c (ffffffff834812ad)
Location: include/linux/kstrtox.h:79
Inline: True
Inline callers:
  - kernel/time/ntp.c:ntp_tick_adj_setup
```
```
In block/blk-sysfs.c (ffffffff8167adcb)
Location: include/linux/kstrtox.h:79
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_wb_lat_store
```
```
In drivers/rtc/sysfs.c (ffffffff81b2aca2)
Location: include/linux/kstrtox.h:79
Inline: True
Inline callers:
  - drivers/rtc/sysfs.c:wakealarm_store
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/ntp.c (ffffffff83eae185)
Location: include/linux/kstrtox.h:79
Inline: True
Inline callers:
  - kernel/time/ntp.c:ntp_tick_adj_setup
```
```
In block/blk-sysfs.c (ffffffff8173744b)
Location: include/linux/kstrtox.h:79
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_wb_lat_store
```
```
In drivers/rtc/sysfs.c (ffffffff81cbe952)
Location: include/linux/kstrtox.h:79
Inline: True
Inline callers:
  - drivers/rtc/sysfs.c:wakealarm_store
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/ntp.c (ffffffff836d31b5)
Location: include/linux/kstrtox.h:79
Inline: True
Inline callers:
  - kernel/time/ntp.c:ntp_tick_adj_setup
```
```
In block/blk-sysfs.c (ffffffff81772e4b)
Location: include/linux/kstrtox.h:79
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_wb_lat_store
```
```
In drivers/rtc/sysfs.c (ffffffff81d26262)
Location: include/linux/kstrtox.h:79
Inline: True
Inline callers:
  - drivers/rtc/sysfs.c:wakealarm_store
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/ntp.c (ffffffff83904f75)
Location: include/linux/kstrtox.h:79
Inline: True
Inline callers:
  - kernel/time/ntp.c:ntp_tick_adj_setup
```
```
In block/blk-sysfs.c (ffffffff817b518b)
Location: include/linux/kstrtox.h:79
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_wb_lat_store
```
```
In drivers/rtc/sysfs.c (ffffffff81ddbfd2)
Location: include/linux/kstrtox.h:79
Inline: True
Inline callers:
  - drivers/rtc/sysfs.c:wakealarm_store
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/ntp.c (ffff800011448b4c)
Location: include/linux/kernel.h:411
Inline: True
Inline callers:
  - kernel/time/ntp.c:ntp_tick_adj_setup
```
```
In block/blk-sysfs.c (ffff8000105e5f30)
Location: include/linux/kernel.h:411
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_wb_lat_store
```
```
In drivers/rtc/sysfs.c (ffff800010aabd60)
Location: include/linux/kernel.h:411
Inline: True
Inline callers:
  - drivers/rtc/sysfs.c:wakealarm_store
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/ntp.c (c1522c1c)
Location: include/linux/kernel.h:411
Inline: True
Inline callers:
  - kernel/time/ntp.c:ntp_tick_adj_setup
```
```
In block/blk-sysfs.c (c0792ca0)
Location: include/linux/kernel.h:411
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_wb_lat_store
```
```
In drivers/rtc/sysfs.c (c0b8a308)
Location: include/linux/kernel.h:411
Inline: True
Inline callers:
  - drivers/rtc/sysfs.c:wakealarm_store
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/ntp.c (c00000000136dd80)
Location: include/linux/kernel.h:411
Inline: True
Inline callers:
  - kernel/time/ntp.c:ntp_tick_adj_setup
```
```
In block/blk-sysfs.c (c00000000077a244)
Location: include/linux/kernel.h:411
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_wb_lat_store
```
```
In drivers/rtc/sysfs.c (c000000000b8de8c)
Location: include/linux/kernel.h:411
Inline: True
Inline callers:
  - drivers/rtc/sysfs.c:wakealarm_store
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/ntp.c (ffffffe00000a0a6)
Location: include/linux/kernel.h:411
Inline: True
Inline callers:
  - kernel/time/ntp.c:ntp_tick_adj_setup
```
```
In block/blk-sysfs.c (ffffffe000427172)
Location: include/linux/kernel.h:411
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_wb_lat_store
```
```
In drivers/rtc/sysfs.c (ffffffe0006b66ce)
Location: include/linux/kernel.h:411
Inline: True
Inline callers:
  - drivers/rtc/sysfs.c:wakealarm_store
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/ntp.c (ffffffff828b9aa2)
Location: include/linux/kernel.h:411
Inline: True
Inline callers:
  - kernel/time/ntp.c:ntp_tick_adj_setup
```
```
In block/blk-sysfs.c (ffffffff814e0715)
Location: include/linux/kernel.h:411
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_wb_lat_store
```
```
In drivers/rtc/sysfs.c (ffffffff8181c14f)
Location: include/linux/kernel.h:411
Inline: True
Inline callers:
  - drivers/rtc/sysfs.c:wakealarm_store
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/ntp.c (ffffffff828b1ff3)
Location: include/linux/kernel.h:411
Inline: True
Inline callers:
  - kernel/time/ntp.c:ntp_tick_adj_setup
```
```
In block/blk-sysfs.c (ffffffff814d10b5)
Location: include/linux/kernel.h:411
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_wb_lat_store
```
```
In drivers/rtc/sysfs.c (ffffffff817e383f)
Location: include/linux/kernel.h:411
Inline: True
Inline callers:
  - drivers/rtc/sysfs.c:wakealarm_store
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/ntp.c (ffffffff828cc825)
Location: include/linux/kernel.h:411
Inline: True
Inline callers:
  - kernel/time/ntp.c:ntp_tick_adj_setup
```
```
In block/blk-sysfs.c (ffffffff814dc7a5)
Location: include/linux/kernel.h:411
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_wb_lat_store
```
```
In drivers/rtc/sysfs.c (ffffffff8185d62f)
Location: include/linux/kernel.h:411
Inline: True
Inline callers:
  - drivers/rtc/sysfs.c:wakealarm_store
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/ntp.c (ffffffff828d1c1f)
Location: include/linux/kernel.h:411
Inline: True
Inline callers:
  - kernel/time/ntp.c:ntp_tick_adj_setup
```
```
In block/blk-sysfs.c (ffffffff814f5615)
Location: include/linux/kernel.h:411
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_wb_lat_store
```
```
In drivers/rtc/sysfs.c (ffffffff8187889f)
Location: include/linux/kernel.h:411
Inline: True
Inline callers:
  - drivers/rtc/sysfs.c:wakealarm_store
```
</details>
</li>
</ul>

## Differences
