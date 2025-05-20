# Function: <code>clocksource_cyc2ns</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (0)
Location: include/linux/clocksource.h:176
Inline: True
```
```
In kernel/time/clocksource.c (ffffffff810f7d4b)
Location: include/linux/clocksource.h:176
Inline: True
Inline callers:
  - kernel/time/clocksource.c:__clocksource_update_freq_scale
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff810fc102)
Location: include/linux/clocksource.h:176
Inline: True
```
```
In kernel/time/clocksource.c (ffffffff810fee65)
Location: include/linux/clocksource.h:176
Inline: True
Inline callers:
  - kernel/time/clocksource.c:__clocksource_update_freq_scale
  - kernel/time/clocksource.c:clocksource_watchdog
  - kernel/time/clocksource.c:clocksource_watchdog
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff810ff002)
Location: include/linux/clocksource.h:179
Inline: True
```
```
In kernel/time/clocksource.c (ffffffff81101cd5)
Location: include/linux/clocksource.h:179
Inline: True
Inline callers:
  - kernel/time/clocksource.c:__clocksource_update_freq_scale
  - kernel/time/clocksource.c:clocksource_watchdog
  - kernel/time/clocksource.c:clocksource_watchdog
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
In kernel/time/clocksource.c (ffffffff81103e29)
Location: include/linux/clocksource.h:183
Inline: True
Inline callers:
  - kernel/time/clocksource.c:__clocksource_update_freq_scale
  - kernel/time/clocksource.c:clocksource_watchdog
  - kernel/time/clocksource.c:clocksource_watchdog
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/clocksource.c (ffffffff8110eeb9)
Location: include/linux/clocksource.h:184
Inline: True
Inline callers:
  - kernel/time/clocksource.c:__clocksource_update_freq_scale
  - kernel/time/clocksource.c:clocksource_watchdog
  - kernel/time/clocksource.c:clocksource_watchdog
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
In kernel/time/clocksource.c (ffffffff8111a923)
Location: include/linux/clocksource.h:184
Inline: True
Inline callers:
  - kernel/time/clocksource.c:__clocksource_update_freq_scale
  - kernel/time/clocksource.c:clocksource_watchdog
  - kernel/time/clocksource.c:clocksource_watchdog
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
In kernel/time/clocksource.c (ffffffff81125dc4)
Location: include/linux/clocksource.h:184
Inline: True
Inline callers:
  - kernel/time/clocksource.c:__clocksource_update_freq_scale
  - kernel/time/clocksource.c:clocksource_watchdog
  - kernel/time/clocksource.c:clocksource_watchdog
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
In kernel/time/clocksource.c (ffffffff81131962)
Location: include/linux/clocksource.h:184
Inline: True
Inline callers:
  - kernel/time/clocksource.c:__clocksource_update_freq_scale
  - kernel/time/clocksource.c:clocksource_watchdog
  - kernel/time/clocksource.c:clocksource_watchdog
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
In kernel/time/clocksource.c (ffffffff8113d8b2)
Location: include/linux/clocksource.h:184
Inline: True
Inline callers:
  - kernel/time/clocksource.c:__clocksource_update_freq_scale
  - kernel/time/clocksource.c:clocksource_watchdog
  - kernel/time/clocksource.c:clocksource_watchdog
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
In kernel/time/clocksource.c (ffffffff8114cab6)
Location: include/linux/clocksource.h:195
Inline: True
Inline callers:
  - kernel/time/clocksource.c:__clocksource_update_freq_scale
  - kernel/time/clocksource.c:clocksource_watchdog
  - kernel/time/clocksource.c:clocksource_watchdog
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
In kernel/time/clocksource.c (ffffffff81be39ed)
Location: include/linux/clocksource.h:195
Inline: True
Inline callers:
  - kernel/time/clocksource.c:__clocksource_update_freq_scale
  - kernel/time/clocksource.c:clocksource_watchdog
  - kernel/time/clocksource.c:clocksource_watchdog
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
In kernel/time/clocksource.c (ffffffff81149c08)
Location: include/linux/clocksource.h:201
Inline: True
Inline callers:
  - kernel/time/clocksource.c:__clocksource_update_freq_scale
  - kernel/time/clocksource.c:clocksource_watchdog
  - kernel/time/clocksource.c:clocksource_watchdog
  - kernel/time/clocksource.c:clocksource_verify_percpu
  - kernel/time/clocksource.c:cs_watchdog_read
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
In kernel/time/clocksource.c (ffffffff81cb179f)
Location: include/linux/clocksource.h:204
Inline: True
Inline callers:
  - kernel/time/clocksource.c:__clocksource_update_freq_scale
  - kernel/time/clocksource.c:clocksource_watchdog
  - kernel/time/clocksource.c:clocksource_watchdog
  - kernel/time/clocksource.c:cs_watchdog_read
  - kernel/time/clocksource.c:cs_watchdog_read
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
In kernel/time/clocksource.c (ffffffff811a15d8)
Location: include/linux/clocksource.h:204
Inline: True
Inline callers:
  - kernel/time/clocksource.c:__clocksource_update_freq_scale
  - kernel/time/clocksource.c:clocksource_watchdog
  - kernel/time/clocksource.c:clocksource_watchdog
  - kernel/time/clocksource.c:cs_watchdog_read
  - kernel/time/clocksource.c:cs_watchdog_read
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
In kernel/time/clocksource.c (ffffffff811dfdd9)
Location: include/linux/clocksource.h:204
Inline: True
Inline callers:
  - kernel/time/clocksource.c:__clocksource_update_freq_scale
  - kernel/time/clocksource.c:clocksource_watchdog
  - kernel/time/clocksource.c:clocksource_watchdog
  - kernel/time/clocksource.c:cs_watchdog_read
  - kernel/time/clocksource.c:cs_watchdog_read
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
In kernel/time/clocksource.c (ffffffff811f4307)
Location: include/linux/clocksource.h:204
Inline: True
Inline callers:
  - kernel/time/clocksource.c:__clocksource_update_freq_scale
  - kernel/time/clocksource.c:clocksource_watchdog
  - kernel/time/clocksource.c:clocksource_watchdog
  - kernel/time/clocksource.c:cs_watchdog_read
  - kernel/time/clocksource.c:cs_watchdog_read
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
In kernel/time/clocksource.c (ffffffff8120a447)
Location: include/linux/clocksource.h:204
Inline: True
Inline callers:
  - kernel/time/clocksource.c:__clocksource_update_freq_scale
  - kernel/time/clocksource.c:clocksource_watchdog
  - kernel/time/clocksource.c:clocksource_watchdog
  - kernel/time/clocksource.c:cs_watchdog_read
  - kernel/time/clocksource.c:cs_watchdog_read
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
In kernel/time/clocksource.c (ffff8000101a6988)
Location: include/linux/clocksource.h:184
Inline: True
Inline callers:
  - kernel/time/clocksource.c:__clocksource_update_freq_scale
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
Location: include/linux/clocksource.h:184
Inline: True
Inline callers:
  - arch/arm/plat-omap/counter_32k.c:omap_read_persistent_clock64
```
```
In kernel/time/clocksource.c (c03f230c)
Location: include/linux/clocksource.h:184
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocks_calc_max_nsecs
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
In kernel/time/clocksource.c (c000000000209034)
Location: include/linux/clocksource.h:184
Inline: True
Inline callers:
  - kernel/time/clocksource.c:__clocksource_update_freq_scale
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
In kernel/time/clocksource.c (ffffffe000132ac2)
Location: include/linux/clocksource.h:184
Inline: True
Inline callers:
  - kernel/time/clocksource.c:__clocksource_update_freq_scale
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
In kernel/time/clocksource.c (ffffffff81136062)
Location: include/linux/clocksource.h:184
Inline: True
Inline callers:
  - kernel/time/clocksource.c:__clocksource_update_freq_scale
  - kernel/time/clocksource.c:clocksource_watchdog
  - kernel/time/clocksource.c:clocksource_watchdog
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
In kernel/time/clocksource.c (ffffffff81128ab2)
Location: include/linux/clocksource.h:184
Inline: True
Inline callers:
  - kernel/time/clocksource.c:__clocksource_update_freq_scale
  - kernel/time/clocksource.c:clocksource_watchdog
  - kernel/time/clocksource.c:clocksource_watchdog
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
In kernel/time/clocksource.c (ffffffff81133d82)
Location: include/linux/clocksource.h:184
Inline: True
Inline callers:
  - kernel/time/clocksource.c:__clocksource_update_freq_scale
  - kernel/time/clocksource.c:clocksource_watchdog
  - kernel/time/clocksource.c:clocksource_watchdog
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
In kernel/time/clocksource.c (ffffffff811407a2)
Location: include/linux/clocksource.h:184
Inline: True
Inline callers:
  - kernel/time/clocksource.c:__clocksource_update_freq_scale
  - kernel/time/clocksource.c:clocksource_watchdog
  - kernel/time/clocksource.c:clocksource_watchdog
```
</details>
</li>
</ul>

## Differences
