# Function: <code>rtc_alarm_disable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff8167457d)
Location: drivers/rtc/interface.c:785
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_timer_do_work
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff816d5927)
Location: drivers/rtc/interface.c:793
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_timer_do_work
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff8170560a)
Location: drivers/rtc/interface.c:793
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_timer_do_work
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
In drivers/rtc/interface.c (ffffffff8171b0b2)
Location: drivers/rtc/interface.c:800
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_timer_do_work
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
In drivers/rtc/interface.c (ffffffff8178c355)
Location: drivers/rtc/interface.c:800
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_timer_do_work
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/rtc/interface.c (ffffffff817cd280)
Location: drivers/rtc/interface.c:904
Inline: True
Direct callers:
  - drivers/rtc/interface.c:rtc_timer_do_work
```
**Symbols:**

```
ffffffff817cd280-ffffffff817cd2e6: rtc_alarm_disable.isra.12 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/rtc/interface.c (ffffffff817f4680)
Location: drivers/rtc/interface.c:830
Inline: True
Direct callers:
  - drivers/rtc/interface.c:rtc_timer_do_work
```
**Symbols:**

```
ffffffff817f4680-ffffffff817f46e6: rtc_alarm_disable.isra.13 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/rtc/interface.c (ffffffff81835340)
Location: drivers/rtc/interface.c:822
Inline: True
Direct callers:
  - drivers/rtc/interface.c:rtc_timer_do_work
```
**Symbols:**

```
ffffffff81835340-ffffffff818353a6: rtc_alarm_disable.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/rtc/interface.c (ffffffff81866b10)
Location: drivers/rtc/interface.c:830
Inline: True
Direct callers:
  - drivers/rtc/interface.c:rtc_timer_do_work
```
**Symbols:**

```
ffffffff81866b10-ffffffff81866b76: rtc_alarm_disable.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/rtc/interface.c (ffffffff8193a380)
Location: drivers/rtc/interface.c:844
Inline: True
Direct callers:
  - drivers/rtc/interface.c:rtc_timer_do_work
```
**Symbols:**

```
ffffffff8193a380-ffffffff8193a3ec: rtc_alarm_disable.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/rtc/interface.c (ffffffff819407c0)
Location: drivers/rtc/interface.c:844
Inline: True
Direct callers:
  - drivers/rtc/interface.c:rtc_timer_do_work
```
**Symbols:**

```
ffffffff819407c0-ffffffff81940814: rtc_alarm_disable.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void rtc_alarm_disable(struct rtc_device *rtc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff81923d30)
Location: drivers/rtc/interface.c:830
Inline: False
Direct callers:
  - drivers/rtc/interface.c:rtc_timer_do_work
```
**Symbols:**

```
ffffffff81923d30-ffffffff81923d9b: rtc_alarm_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void rtc_alarm_disable(struct rtc_device *rtc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff819c6d60)
Location: drivers/rtc/interface.c:830
Inline: False
Direct callers:
  - drivers/rtc/interface.c:rtc_timer_do_work
```
**Symbols:**

```
ffffffff819c6d60-ffffffff819c6dc8: rtc_alarm_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void rtc_alarm_disable(struct rtc_device *rtc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff81b27ea0)
Location: drivers/rtc/interface.c:844
Inline: False
Direct callers:
  - drivers/rtc/interface.c:rtc_timer_do_work
```
**Symbols:**

```
ffffffff81b27ea0-ffffffff81b27f45: rtc_alarm_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void rtc_alarm_disable(struct rtc_device *rtc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff81cbb770)
Location: drivers/rtc/interface.c:844
Inline: False
Direct callers:
  - drivers/rtc/interface.c:rtc_timer_do_work
```
**Symbols:**

```
ffffffff81cbb770-ffffffff81cbb815: rtc_alarm_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void rtc_alarm_disable(struct rtc_device *rtc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff81d22ef0)
Location: drivers/rtc/interface.c:844
Inline: False
Direct callers:
  - drivers/rtc/interface.c:rtc_timer_do_work
```
**Symbols:**

```
ffffffff81d22ef0-ffffffff81d22f95: rtc_alarm_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void rtc_alarm_disable(struct rtc_device *rtc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff81dd8c50)
Location: drivers/rtc/interface.c:844
Inline: False
Direct callers:
  - drivers/rtc/interface.c:rtc_timer_do_work
```
**Symbols:**

```
ffffffff81dd8c50-ffffffff81dd8cf5: rtc_alarm_disable (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/rtc/interface.c (ffff800010aa84c8)
Location: drivers/rtc/interface.c:830
Inline: True
Direct callers:
  - drivers/rtc/interface.c:rtc_timer_do_work
```
**Symbols:**

```
ffff800010aa84c8-ffff800010aa857c: rtc_alarm_disable.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void rtc_alarm_disable(struct rtc_device *rtc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (c0b872b4)
Location: drivers/rtc/interface.c:830
Inline: False
Direct callers:
  - drivers/rtc/interface.c:rtc_timer_do_work
```
**Symbols:**

```
c0b872b4-c0b8736c: rtc_alarm_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void rtc_alarm_disable(struct rtc_device *rtc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (c000000000b8a090)
Location: drivers/rtc/interface.c:830
Inline: False
Direct callers:
  - drivers/rtc/interface.c:rtc_timer_do_work
```
**Symbols:**

```
c000000000b8a090-c000000000b8a16c: rtc_alarm_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void rtc_alarm_disable(struct rtc_device *rtc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffe0006b3fae)
Location: drivers/rtc/interface.c:830
Inline: False
Direct callers:
  - drivers/rtc/interface.c:rtc_timer_do_work
```
**Symbols:**

```
ffffffe0006b3fae-ffffffe0006b402e: rtc_alarm_disable (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/rtc/interface.c (ffffffff818197c0)
Location: drivers/rtc/interface.c:830
Inline: True
Direct callers:
  - drivers/rtc/interface.c:rtc_timer_do_work
```
**Symbols:**

```
ffffffff818197c0-ffffffff81819826: rtc_alarm_disable.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/rtc/interface.c (ffffffff817e0eb0)
Location: drivers/rtc/interface.c:830
Inline: True
Direct callers:
  - drivers/rtc/interface.c:rtc_timer_do_work
```
**Symbols:**

```
ffffffff817e0eb0-ffffffff817e0f16: rtc_alarm_disable.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/rtc/interface.c (ffffffff8185aca0)
Location: drivers/rtc/interface.c:830
Inline: True
Direct callers:
  - drivers/rtc/interface.c:rtc_timer_do_work
```
**Symbols:**

```
ffffffff8185aca0-ffffffff8185ad06: rtc_alarm_disable.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/rtc/interface.c (ffffffff81875de0)
Location: drivers/rtc/interface.c:830
Inline: True
Direct callers:
  - drivers/rtc/interface.c:rtc_timer_do_work
```
**Symbols:**

```
ffffffff81875de0-ffffffff81875e5a: rtc_alarm_disable.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
</ul>
