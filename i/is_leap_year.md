# Function: <code>is_leap_year</code>

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
In drivers/rtc/rtc-lib.c (ffffffff81672f68)
Location: include/linux/rtc.h:213
Inline: True
Inline callers:
  - drivers/rtc/rtc-lib.c:rtc_year_days
  - drivers/rtc/rtc-lib.c:rtc_time64_to_tm
  - drivers/rtc/rtc-lib.c:rtc_time64_to_tm
  - drivers/rtc/rtc-lib.c:rtc_valid_tm
```
```
In drivers/rtc/interface.c (ffffffff81674d6e)
Location: include/linux/rtc.h:213
Inline: True
Inline callers:
  - drivers/rtc/interface.c:__rtc_read_alarm
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
In drivers/rtc/rtc-lib.c (ffffffff816d3a3b)
Location: include/linux/rtc.h:217
Inline: True
Inline callers:
  - drivers/rtc/rtc-lib.c:rtc_valid_tm
  - drivers/rtc/rtc-lib.c:rtc_time64_to_tm
  - drivers/rtc/rtc-lib.c:rtc_time64_to_tm
  - drivers/rtc/rtc-lib.c:rtc_year_days
```
```
In drivers/rtc/interface.c (ffffffff816d5622)
Location: include/linux/rtc.h:217
Inline: True
Inline callers:
  - drivers/rtc/interface.c:__rtc_read_alarm
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
In drivers/rtc/rtc-lib.c (ffffffff8170371b)
Location: include/linux/rtc.h:217
Inline: True
Inline callers:
  - drivers/rtc/rtc-lib.c:rtc_valid_tm
  - drivers/rtc/rtc-lib.c:rtc_time64_to_tm
  - drivers/rtc/rtc-lib.c:rtc_time64_to_tm
  - drivers/rtc/rtc-lib.c:rtc_year_days
```
```
In drivers/rtc/interface.c (ffffffff81705302)
Location: include/linux/rtc.h:217
Inline: True
Inline callers:
  - drivers/rtc/interface.c:__rtc_read_alarm
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/rtc/rtc-lib.c (ffffffff81718efe)
Location: include/linux/rtc.h:221
Inline: True
Inline callers:
  - drivers/rtc/rtc-lib.c:rtc_valid_tm
  - drivers/rtc/rtc-lib.c:rtc_time64_to_tm
  - drivers/rtc/rtc-lib.c:rtc_time64_to_tm
  - drivers/rtc/rtc-lib.c:rtc_year_days
```
```
In drivers/rtc/interface.c (ffffffff8171ad4b)
Location: include/linux/rtc.h:221
Inline: True
Inline callers:
  - drivers/rtc/interface.c:__rtc_read_alarm
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
In drivers/rtc/rtc-lib.c (ffffffff8178a0de)
Location: include/linux/rtc.h:228
Inline: True
Inline callers:
  - drivers/rtc/rtc-lib.c:rtc_valid_tm
  - drivers/rtc/rtc-lib.c:rtc_time64_to_tm
  - drivers/rtc/rtc-lib.c:rtc_time64_to_tm
  - drivers/rtc/rtc-lib.c:rtc_year_days
```
```
In drivers/rtc/interface.c (ffffffff8178bff1)
Location: include/linux/rtc.h:228
Inline: True
Inline callers:
  - drivers/rtc/interface.c:__rtc_read_alarm
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
In drivers/rtc/rtc-lib.c (ffffffff817cb1f2)
Location: include/linux/rtc.h:233
Inline: True
Inline callers:
  - drivers/rtc/rtc-lib.c:rtc_valid_tm
  - drivers/rtc/rtc-lib.c:rtc_time64_to_tm
  - drivers/rtc/rtc-lib.c:rtc_time64_to_tm
  - drivers/rtc/rtc-lib.c:rtc_year_days
```
```
In drivers/rtc/interface.c (ffffffff817ce423)
Location: include/linux/rtc.h:233
Inline: True
Inline callers:
  - drivers/rtc/interface.c:__rtc_read_alarm
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
In drivers/rtc/lib.c (ffffffff817f28a2)
Location: include/linux/rtc.h:214
Inline: True
Inline callers:
  - drivers/rtc/lib.c:rtc_valid_tm
  - drivers/rtc/lib.c:rtc_time64_to_tm
  - drivers/rtc/lib.c:rtc_time64_to_tm
  - drivers/rtc/lib.c:rtc_year_days
```
```
In drivers/rtc/interface.c (ffffffff817f5460)
Location: include/linux/rtc.h:214
Inline: True
Inline callers:
  - drivers/rtc/interface.c:__rtc_read_alarm
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
In drivers/rtc/lib.c (ffffffff81833599)
Location: include/linux/rtc.h:213
Inline: True
Inline callers:
  - drivers/rtc/lib.c:rtc_valid_tm
  - drivers/rtc/lib.c:rtc_time64_to_tm
  - drivers/rtc/lib.c:rtc_time64_to_tm
  - drivers/rtc/lib.c:rtc_year_days
```
```
In drivers/rtc/interface.c (ffffffff81836095)
Location: include/linux/rtc.h:213
Inline: True
Inline callers:
  - drivers/rtc/interface.c:__rtc_read_alarm
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
In drivers/rtc/lib.c (ffffffff81864ed9)
Location: include/linux/rtc.h:213
Inline: True
Inline callers:
  - drivers/rtc/lib.c:rtc_valid_tm
  - drivers/rtc/lib.c:rtc_time64_to_tm
  - drivers/rtc/lib.c:rtc_time64_to_tm
  - drivers/rtc/lib.c:rtc_year_days
```
```
In drivers/rtc/interface.c (ffffffff81867a05)
Location: include/linux/rtc.h:213
Inline: True
Inline callers:
  - drivers/rtc/interface.c:__rtc_read_alarm
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
In drivers/rtc/lib.c (ffffffff81938829)
Location: include/linux/rtc.h:207
Inline: True
Inline callers:
  - drivers/rtc/lib.c:rtc_valid_tm
  - drivers/rtc/lib.c:rtc_time64_to_tm
  - drivers/rtc/lib.c:rtc_time64_to_tm
  - drivers/rtc/lib.c:rtc_year_days
```
```
In drivers/rtc/interface.c (ffffffff8193b415)
Location: include/linux/rtc.h:207
Inline: True
Inline callers:
  - drivers/rtc/interface.c:__rtc_read_alarm
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
In drivers/rtc/lib.c (ffffffff8193eb59)
Location: include/linux/rtc.h:219
Inline: True
Inline callers:
  - drivers/rtc/lib.c:rtc_valid_tm
  - drivers/rtc/lib.c:rtc_time64_to_tm
  - drivers/rtc/lib.c:rtc_time64_to_tm
  - drivers/rtc/lib.c:rtc_year_days
```
```
In drivers/rtc/interface.c (ffffffff8194177f)
Location: include/linux/rtc.h:219
Inline: True
Inline callers:
  - drivers/rtc/interface.c:__rtc_read_alarm
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
In drivers/rtc/lib.c (ffffffff81922349)
Location: include/linux/rtc.h:221
Inline: True
Inline callers:
  - drivers/rtc/lib.c:rtc_valid_tm
  - drivers/rtc/lib.c:rtc_time64_to_tm
  - drivers/rtc/lib.c:rtc_time64_to_tm
  - drivers/rtc/lib.c:rtc_year_days
```
```
In drivers/rtc/interface.c (ffffffff81924f0c)
Location: include/linux/rtc.h:221
Inline: True
Inline callers:
  - drivers/rtc/interface.c:__rtc_read_alarm
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
In drivers/rtc/lib.c (ffffffff819c52d0)
Location: include/linux/rtc.h:221
Inline: True
Inline callers:
  - drivers/rtc/lib.c:rtc_valid_tm
  - drivers/rtc/lib.c:rtc_year_days
```
```
In drivers/rtc/interface.c (ffffffff819c7e9c)
Location: include/linux/rtc.h:221
Inline: True
Inline callers:
  - drivers/rtc/interface.c:__rtc_read_alarm
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
In drivers/rtc/lib.c (ffffffff81b258dc)
Location: include/linux/rtc.h:222
Inline: True
Inline callers:
  - drivers/rtc/lib.c:rtc_valid_tm
  - drivers/rtc/lib.c:rtc_year_days
```
```
In drivers/rtc/interface.c (ffffffff81b28c67)
Location: include/linux/rtc.h:222
Inline: True
Inline callers:
  - drivers/rtc/interface.c:__rtc_read_alarm
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
In drivers/rtc/lib.c (ffffffff81cb8e9c)
Location: include/linux/rtc.h:222
Inline: True
Inline callers:
  - drivers/rtc/lib.c:rtc_valid_tm
  - drivers/rtc/lib.c:rtc_year_days
```
```
In drivers/rtc/interface.c (ffffffff81cbc813)
Location: include/linux/rtc.h:222
Inline: True
Inline callers:
  - drivers/rtc/interface.c:__rtc_read_alarm
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
In drivers/rtc/lib.c (ffffffff81d205cc)
Location: include/linux/rtc.h:222
Inline: True
Inline callers:
  - drivers/rtc/lib.c:rtc_valid_tm
  - drivers/rtc/lib.c:rtc_year_days
```
```
In drivers/rtc/interface.c (ffffffff81d24123)
Location: include/linux/rtc.h:222
Inline: True
Inline callers:
  - drivers/rtc/interface.c:__rtc_read_alarm
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
In drivers/rtc/lib.c (ffffffff81dd62fc)
Location: include/linux/rtc.h:223
Inline: True
Inline callers:
  - drivers/rtc/lib.c:rtc_valid_tm
  - drivers/rtc/lib.c:rtc_year_days
```
```
In drivers/rtc/interface.c (ffffffff81dd9e8e)
Location: include/linux/rtc.h:223
Inline: True
Inline callers:
  - drivers/rtc/interface.c:__rtc_read_alarm
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
In drivers/rtc/lib.c (ffff800010aa66d4)
Location: include/linux/rtc.h:213
Inline: True
Inline callers:
  - drivers/rtc/lib.c:rtc_valid_tm
  - drivers/rtc/lib.c:rtc_time64_to_tm
  - drivers/rtc/lib.c:rtc_time64_to_tm
  - drivers/rtc/lib.c:rtc_year_days
```
```
In drivers/rtc/interface.c (ffff800010aa95b8)
Location: include/linux/rtc.h:213
Inline: True
Inline callers:
  - drivers/rtc/interface.c:__rtc_read_alarm
```
```
In drivers/rtc/rtc-rtd119x.c (ffff800010aacf78)
Location: include/linux/rtc.h:213
Inline: True
Inline callers:
  - drivers/rtc/rtc-rtd119x.c:rtd119x_rtc_set_time
  - drivers/rtc/rtc-rtd119x.c:rtd119x_rtc_read_time
  - drivers/rtc/rtc-rtd119x.c:rtd119x_rtc_read_time
```
```
In drivers/rtc/rtc-sun6i.c (ffff800010aad534)
Location: include/linux/rtc.h:213
Inline: True
Inline callers:
  - drivers/rtc/rtc-sun6i.c:sun6i_rtc_settime
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
In drivers/rtc/lib.c (c0b84f6c)
Location: include/linux/rtc.h:213
Inline: True
Inline callers:
  - drivers/rtc/lib.c:rtc_valid_tm
  - drivers/rtc/lib.c:rtc_time64_to_tm
  - drivers/rtc/lib.c:rtc_time64_to_tm
  - drivers/rtc/lib.c:rtc_year_days
```
```
In drivers/rtc/interface.c (c0b88414)
Location: include/linux/rtc.h:213
Inline: True
Inline callers:
  - drivers/rtc/interface.c:__rtc_read_alarm
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
In drivers/rtc/lib.c (c000000000b87258)
Location: include/linux/rtc.h:213
Inline: True
Inline callers:
  - drivers/rtc/lib.c:rtc_valid_tm
  - drivers/rtc/lib.c:rtc_time64_to_tm
  - drivers/rtc/lib.c:rtc_time64_to_tm
  - drivers/rtc/lib.c:rtc_year_days
```
```
In drivers/rtc/interface.c (c000000000b8b650)
Location: include/linux/rtc.h:213
Inline: True
Inline callers:
  - drivers/rtc/interface.c:__rtc_read_alarm
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
In drivers/rtc/lib.c (ffffffe0006b2a64)
Location: include/linux/rtc.h:213
Inline: True
Inline callers:
  - drivers/rtc/lib.c:rtc_valid_tm
  - drivers/rtc/lib.c:rtc_time64_to_tm
  - drivers/rtc/lib.c:rtc_time64_to_tm
  - drivers/rtc/lib.c:rtc_year_days
```
```
In drivers/rtc/interface.c (ffffffe0006b4d18)
Location: include/linux/rtc.h:213
Inline: True
Inline callers:
  - drivers/rtc/interface.c:__rtc_read_alarm
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
In drivers/rtc/lib.c (ffffffff81817b89)
Location: include/linux/rtc.h:213
Inline: True
Inline callers:
  - drivers/rtc/lib.c:rtc_valid_tm
  - drivers/rtc/lib.c:rtc_time64_to_tm
  - drivers/rtc/lib.c:rtc_time64_to_tm
  - drivers/rtc/lib.c:rtc_year_days
```
```
In drivers/rtc/interface.c (ffffffff8181a6b5)
Location: include/linux/rtc.h:213
Inline: True
Inline callers:
  - drivers/rtc/interface.c:__rtc_read_alarm
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
In drivers/rtc/lib.c (ffffffff817df279)
Location: include/linux/rtc.h:213
Inline: True
Inline callers:
  - drivers/rtc/lib.c:rtc_valid_tm
  - drivers/rtc/lib.c:rtc_time64_to_tm
  - drivers/rtc/lib.c:rtc_time64_to_tm
  - drivers/rtc/lib.c:rtc_year_days
```
```
In drivers/rtc/interface.c (ffffffff817e1da5)
Location: include/linux/rtc.h:213
Inline: True
Inline callers:
  - drivers/rtc/interface.c:__rtc_read_alarm
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
In drivers/rtc/lib.c (ffffffff81859069)
Location: include/linux/rtc.h:213
Inline: True
Inline callers:
  - drivers/rtc/lib.c:rtc_valid_tm
  - drivers/rtc/lib.c:rtc_time64_to_tm
  - drivers/rtc/lib.c:rtc_time64_to_tm
  - drivers/rtc/lib.c:rtc_year_days
```
```
In drivers/rtc/interface.c (ffffffff8185bb95)
Location: include/linux/rtc.h:213
Inline: True
Inline callers:
  - drivers/rtc/interface.c:__rtc_read_alarm
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
In drivers/rtc/lib.c (ffffffff81874149)
Location: include/linux/rtc.h:213
Inline: True
Inline callers:
  - drivers/rtc/lib.c:rtc_valid_tm
  - drivers/rtc/lib.c:rtc_time64_to_tm
  - drivers/rtc/lib.c:rtc_time64_to_tm
  - drivers/rtc/lib.c:rtc_year_days
```
```
In drivers/rtc/interface.c (ffffffff81876d7e)
Location: include/linux/rtc.h:213
Inline: True
Inline callers:
  - drivers/rtc/interface.c:__rtc_read_alarm
```
</details>
</li>
</ul>

## Differences
