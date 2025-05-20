# Function: <code>timespec64_add_ns</code>

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
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff8110c918)
Location: include/linux/time64.h:137
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:getrawmonotonic64
  - kernel/time/timekeeping.c:ktime_get_ts64
  - kernel/time/timekeeping.c:__getnstimeofday64
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81117098)
Location: include/linux/time64.h:138
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:ktime_get_raw_ts64
  - kernel/time/timekeeping.c:ktime_get_ts64
  - kernel/time/timekeeping.c:ktime_get_real_ts64
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff811226d8)
Location: include/linux/time64.h:139
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:ktime_get_raw_ts64
  - kernel/time/timekeeping.c:ktime_get_ts64
  - kernel/time/timekeeping.c:ktime_get_real_ts64
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff8112d4d5)
Location: include/linux/time64.h:152
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:ktime_get_raw_ts64
  - kernel/time/timekeeping.c:ktime_get_ts64
  - kernel/time/timekeeping.c:ktime_get_real_ts64
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81139375)
Location: include/linux/time64.h:154
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:ktime_get_raw_ts64
  - kernel/time/timekeeping.c:ktime_get_ts64
  - kernel/time/timekeeping.c:ktime_get_real_ts64
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81148017)
Location: include/linux/time64.h:146
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:ktime_get_raw_ts64
  - kernel/time/timekeeping.c:ktime_get_ts64
  - kernel/time/timekeeping.c:ktime_get_real_ts64
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff8114445d)
Location: include/linux/time64.h:150
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:ktime_get_raw_ts64
  - kernel/time/timekeeping.c:ktime_get_ts64
  - kernel/time/timekeeping.c:ktime_get_real_ts64
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff811455dd)
Location: include/linux/time64.h:150
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:ktime_get_raw_ts64
  - kernel/time/timekeeping.c:ktime_get_ts64
  - kernel/time/timekeeping.c:ktime_get_real_ts64
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff8116985d)
Location: include/linux/time64.h:155
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:ktime_get_raw_ts64
  - kernel/time/timekeeping.c:ktime_get_ts64
  - kernel/time/timekeeping.c:ktime_get_real_ts64
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff8119de42)
Location: include/linux/time64.h:155
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:ktime_get_raw_ts64
  - kernel/time/timekeeping.c:ktime_get_ts64
  - kernel/time/timekeeping.c:ktime_get_real_ts64
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff811dc062)
Location: include/linux/time64.h:158
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:ktime_get_raw_ts64
  - kernel/time/timekeeping.c:ktime_get_ts64
  - kernel/time/timekeeping.c:ktime_get_real_ts64
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff811f0f02)
Location: include/linux/time64.h:158
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:ktime_get_raw_ts64
  - kernel/time/timekeeping.c:ktime_get_ts64
  - kernel/time/timekeeping.c:ktime_get_real_ts64
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81207042)
Location: include/linux/time64.h:158
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:ktime_get_raw_ts64
  - kernel/time/timekeeping.c:ktime_get_ts64
  - kernel/time/timekeeping.c:ktime_get_real_ts64
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffff8000101a3108)
Location: include/linux/time64.h:154
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:ktime_get_raw_ts64
  - kernel/time/timekeeping.c:ktime_get_ts64
  - kernel/time/timekeeping.c:ktime_get_real_ts64
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
In arch/arm/plat-omap/counter_32k.c (c034f7d0)
Location: include/linux/time64.h:154
Inline: True
Inline callers:
  - arch/arm/plat-omap/counter_32k.c:omap_read_persistent_clock64
```
```
In kernel/time/timekeeping.c (c03ed138)
Location: include/linux/time64.h:154
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:ktime_get_raw_ts64
  - kernel/time/timekeeping.c:ktime_get_ts64
  - kernel/time/timekeeping.c:ktime_get_real_ts64
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (c0000000002049d0)
Location: include/linux/time64.h:154
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:ktime_get_raw_ts64
  - kernel/time/timekeeping.c:ktime_get_ts64
  - kernel/time/timekeeping.c:ktime_get_real_ts64
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffe00012fa66)
Location: include/linux/time64.h:154
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:ktime_get_raw_ts64
  - kernel/time/timekeeping.c:ktime_get_ts64
  - kernel/time/timekeeping.c:ktime_get_real_ts64
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81131b25)
Location: include/linux/time64.h:154
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:ktime_get_raw_ts64
  - kernel/time/timekeeping.c:ktime_get_ts64
  - kernel/time/timekeeping.c:ktime_get_real_ts64
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81124585)
Location: include/linux/time64.h:154
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:ktime_get_raw_ts64
  - kernel/time/timekeeping.c:ktime_get_ts64
  - kernel/time/timekeeping.c:ktime_get_real_ts64
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff8112f845)
Location: include/linux/time64.h:154
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:ktime_get_raw_ts64
  - kernel/time/timekeeping.c:ktime_get_ts64
  - kernel/time/timekeeping.c:ktime_get_real_ts64
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff8113c265)
Location: include/linux/time64.h:154
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:ktime_get_raw_ts64
  - kernel/time/timekeeping.c:ktime_get_ts64
  - kernel/time/timekeeping.c:ktime_get_real_ts64
```
</details>
</li>
</ul>

## Differences
