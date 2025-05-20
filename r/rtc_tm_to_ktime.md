# Function: <code>rtc_tm_to_ktime</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
ktime_t rtc_tm_to_ktime(struct rtc_time tm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/rtc-lib.c (ffffffff816732f0)
Location: drivers/rtc/rtc-lib.c:129
Inline: False
Direct callers:
  - kernel/time/alarmtimer.c:alarmtimer_suspend
  - drivers/rtc/interface.c:rtc_timer_enqueue
  - drivers/rtc/interface.c:rtc_update_irq_enable
  - drivers/rtc/interface.c:rtc_timer_do_work
```
**Symbols:**

```
ffffffff816732f0-ffffffff81673326: rtc_tm_to_ktime (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
ktime_t rtc_tm_to_ktime(struct rtc_time tm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/rtc-lib.c (ffffffff816d3ae0)
Location: drivers/rtc/rtc-lib.c:129
Inline: False
Direct callers:
  - kernel/time/alarmtimer.c:alarmtimer_suspend
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_enqueue
  - drivers/rtc/interface.c:rtc_update_irq_enable
```
**Symbols:**

```
ffffffff816d3ae0-ffffffff816d3b16: rtc_tm_to_ktime (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
ktime_t rtc_tm_to_ktime(struct rtc_time tm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/rtc-lib.c (ffffffff817037c0)
Location: drivers/rtc/rtc-lib.c:129
Inline: False
Direct callers:
  - kernel/time/alarmtimer.c:alarmtimer_suspend
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_enqueue
  - drivers/rtc/interface.c:rtc_update_irq_enable
```
**Symbols:**

```
ffffffff817037c0-ffffffff817037f6: rtc_tm_to_ktime (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
ktime_t rtc_tm_to_ktime(struct rtc_time tm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/rtc-lib.c (ffffffff81718fa0)
Location: drivers/rtc/rtc-lib.c:129
Inline: False
Direct callers:
  - kernel/time/alarmtimer.c:alarmtimer_suspend
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_enqueue
  - drivers/rtc/interface.c:rtc_update_irq_enable
```
**Symbols:**

```
ffffffff81718fa0-ffffffff81718fd6: rtc_tm_to_ktime (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
ktime_t rtc_tm_to_ktime(struct rtc_time tm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/rtc-lib.c (ffffffff8178a180)
Location: drivers/rtc/rtc-lib.c:129
Inline: False
Direct callers:
  - kernel/time/alarmtimer.c:alarmtimer_suspend
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_enqueue
  - drivers/rtc/interface.c:rtc_update_irq_enable
```
**Symbols:**

```
ffffffff8178a180-ffffffff8178a1b6: rtc_tm_to_ktime (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
ktime_t rtc_tm_to_ktime(struct rtc_time tm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/rtc-lib.c (ffffffff817cb290)
Location: drivers/rtc/rtc-lib.c:127
Inline: False
Direct callers:
  - kernel/time/alarmtimer.c:alarmtimer_suspend
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_enqueue
  - drivers/rtc/interface.c:rtc_update_irq_enable
```
**Symbols:**

```
ffffffff817cb290-ffffffff817cb2c6: rtc_tm_to_ktime (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
ktime_t rtc_tm_to_ktime(struct rtc_time tm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/lib.c (ffffffff817f2940)
Location: drivers/rtc/lib.c:127
Inline: False
Direct callers:
  - kernel/time/alarmtimer.c:alarmtimer_suspend
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_enqueue
  - drivers/rtc/interface.c:rtc_update_irq_enable
```
**Symbols:**

```
ffffffff817f2940-ffffffff817f2976: rtc_tm_to_ktime (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
ktime_t rtc_tm_to_ktime(struct rtc_time tm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/lib.c (ffffffff81833620)
Location: drivers/rtc/lib.c:125
Inline: False
Direct callers:
  - kernel/time/alarmtimer.c:alarmtimer_suspend
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_enqueue
  - drivers/rtc/interface.c:rtc_update_irq_enable
```
**Symbols:**

```
ffffffff81833620-ffffffff81833657: rtc_tm_to_ktime (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
ktime_t rtc_tm_to_ktime(struct rtc_time tm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/lib.c (ffffffff81864f60)
Location: drivers/rtc/lib.c:125
Inline: False
Direct callers:
  - kernel/time/alarmtimer.c:alarmtimer_suspend
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_enqueue
  - drivers/rtc/interface.c:rtc_update_irq_enable
```
**Symbols:**

```
ffffffff81864f60-ffffffff81864f97: rtc_tm_to_ktime (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
ktime_t rtc_tm_to_ktime(struct rtc_time tm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/lib.c (ffffffff81938510)
Location: drivers/rtc/lib.c:125
Inline: False
Direct callers:
  - kernel/time/alarmtimer.c:alarmtimer_suspend
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_enqueue
  - drivers/rtc/interface.c:rtc_update_irq_enable
  - drivers/rtc/interface.c:rtc_set_alarm
```
**Symbols:**

```
ffffffff81938510-ffffffff81938560: rtc_tm_to_ktime (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ktime_t rtc_tm_to_ktime(struct rtc_time tm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/lib.c (ffffffff8193e840)
Location: drivers/rtc/lib.c:125
Inline: False
Direct callers:
  - kernel/time/alarmtimer.c:alarmtimer_suspend
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_enqueue
  - drivers/rtc/interface.c:rtc_update_irq_enable
  - drivers/rtc/interface.c:rtc_set_alarm
```
**Symbols:**

```
ffffffff8193e840-ffffffff8193e890: rtc_tm_to_ktime (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ktime_t rtc_tm_to_ktime(struct rtc_time tm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/lib.c (ffffffff81922040)
Location: drivers/rtc/lib.c:125
Inline: False
Direct callers:
  - kernel/time/alarmtimer.c:alarmtimer_suspend
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_enqueue
  - drivers/rtc/interface.c:rtc_update_irq_enable
  - drivers/rtc/interface.c:rtc_set_alarm
```
**Symbols:**

```
ffffffff81922040-ffffffff81922090: rtc_tm_to_ktime (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
ktime_t rtc_tm_to_ktime(struct rtc_time tm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/lib.c (ffffffff819c5230)
Location: drivers/rtc/lib.c:178
Inline: False
Direct callers:
  - kernel/time/alarmtimer.c:alarmtimer_suspend
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_enqueue
  - drivers/rtc/interface.c:rtc_update_irq_enable
  - drivers/rtc/interface.c:rtc_set_alarm
```
**Symbols:**

```
ffffffff819c5230-ffffffff819c5280: rtc_tm_to_ktime (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
ktime_t rtc_tm_to_ktime(struct rtc_time tm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/lib.c (ffffffff81b25810)
Location: drivers/rtc/lib.c:178
Inline: False
Direct callers:
  - kernel/time/alarmtimer.c:alarmtimer_suspend
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_enqueue
  - drivers/rtc/interface.c:rtc_update_irq_enable
  - drivers/rtc/interface.c:rtc_initialize_alarm
  - drivers/rtc/interface.c:rtc_initialize_alarm
```
**Symbols:**

```
ffffffff81b25810-ffffffff81b25872: rtc_tm_to_ktime (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ktime_t rtc_tm_to_ktime(struct rtc_time tm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/lib.c (ffffffff81cb8dc0)
Location: drivers/rtc/lib.c:178
Inline: False
Direct callers:
  - kernel/time/alarmtimer.c:alarmtimer_suspend
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_enqueue
  - drivers/rtc/interface.c:rtc_update_irq_enable
  - drivers/rtc/interface.c:rtc_initialize_alarm
  - drivers/rtc/interface.c:rtc_initialize_alarm
  - drivers/rtc/interface.c:rtc_set_alarm
```
**Symbols:**

```
ffffffff81cb8dc0-ffffffff81cb8e22: rtc_tm_to_ktime (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ktime_t rtc_tm_to_ktime(struct rtc_time tm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/lib.c (ffffffff81d204f0)
Location: drivers/rtc/lib.c:178
Inline: False
Direct callers:
  - kernel/time/alarmtimer.c:alarmtimer_suspend
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_enqueue
  - drivers/rtc/interface.c:rtc_update_irq_enable
  - drivers/rtc/interface.c:rtc_initialize_alarm
  - drivers/rtc/interface.c:rtc_initialize_alarm
  - drivers/rtc/interface.c:rtc_set_alarm
```
**Symbols:**

```
ffffffff81d204f0-ffffffff81d20552: rtc_tm_to_ktime (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ktime_t rtc_tm_to_ktime(struct rtc_time tm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/lib.c (ffffffff81dd6220)
Location: drivers/rtc/lib.c:178
Inline: False
Direct callers:
  - kernel/time/alarmtimer.c:alarmtimer_suspend
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_enqueue
  - drivers/rtc/interface.c:rtc_update_irq_enable
  - drivers/rtc/interface.c:rtc_initialize_alarm
  - drivers/rtc/interface.c:rtc_initialize_alarm
  - drivers/rtc/interface.c:rtc_set_alarm
```
**Symbols:**

```
ffffffff81dd6220-ffffffff81dd6282: rtc_tm_to_ktime (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
ktime_t rtc_tm_to_ktime(struct rtc_time tm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/lib.c (ffff800010aa67a8)
Location: drivers/rtc/lib.c:125
Inline: False
Direct callers:
  - kernel/time/alarmtimer.c:alarmtimer_suspend
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_enqueue
  - drivers/rtc/interface.c:rtc_update_irq_enable
```
**Symbols:**

```
ffff800010aa67a8-ffff800010aa6804: rtc_tm_to_ktime (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
ktime_t rtc_tm_to_ktime(struct rtc_time tm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/lib.c (c0b85270)
Location: drivers/rtc/lib.c:125
Inline: False
Direct callers:
  - kernel/time/alarmtimer.c:alarmtimer_suspend
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_enqueue
  - drivers/rtc/interface.c:rtc_update_irq_enable
```
**Symbols:**

```
c0b85270-c0b852d8: rtc_tm_to_ktime (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
ktime_t rtc_tm_to_ktime(struct rtc_time tm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/lib.c (c000000000b87360)
Location: drivers/rtc/lib.c:125
Inline: False
Direct callers:
  - kernel/time/alarmtimer.c:alarmtimer_suspend
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_enqueue
  - drivers/rtc/interface.c:rtc_update_irq_enable
```
**Symbols:**

```
c000000000b87360-c000000000b873e8: rtc_tm_to_ktime (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
ktime_t rtc_tm_to_ktime(struct rtc_time tm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/lib.c (ffffffe0006b2af6)
Location: drivers/rtc/lib.c:125
Inline: False
Direct callers:
  - kernel/time/alarmtimer.c:alarmtimer_suspend
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_enqueue
  - drivers/rtc/interface.c:rtc_update_irq_enable
```
**Symbols:**

```
ffffffe0006b2af6-ffffffe0006b2b48: rtc_tm_to_ktime (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
ktime_t rtc_tm_to_ktime(struct rtc_time tm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/lib.c (ffffffff81817c10)
Location: drivers/rtc/lib.c:125
Inline: False
Direct callers:
  - kernel/time/alarmtimer.c:alarmtimer_suspend
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_enqueue
  - drivers/rtc/interface.c:rtc_update_irq_enable
```
**Symbols:**

```
ffffffff81817c10-ffffffff81817c47: rtc_tm_to_ktime (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
ktime_t rtc_tm_to_ktime(struct rtc_time tm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/lib.c (ffffffff817df300)
Location: drivers/rtc/lib.c:125
Inline: False
Direct callers:
  - kernel/time/alarmtimer.c:alarmtimer_suspend
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_enqueue
  - drivers/rtc/interface.c:rtc_update_irq_enable
```
**Symbols:**

```
ffffffff817df300-ffffffff817df337: rtc_tm_to_ktime (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
ktime_t rtc_tm_to_ktime(struct rtc_time tm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/lib.c (ffffffff818590f0)
Location: drivers/rtc/lib.c:125
Inline: False
Direct callers:
  - kernel/time/alarmtimer.c:alarmtimer_suspend
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_enqueue
  - drivers/rtc/interface.c:rtc_update_irq_enable
```
**Symbols:**

```
ffffffff818590f0-ffffffff81859127: rtc_tm_to_ktime (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
ktime_t rtc_tm_to_ktime(struct rtc_time tm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/lib.c (ffffffff818741d0)
Location: drivers/rtc/lib.c:125
Inline: False
Direct callers:
  - kernel/time/alarmtimer.c:alarmtimer_suspend
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_enqueue
  - drivers/rtc/interface.c:rtc_update_irq_enable
```
**Symbols:**

```
ffffffff818741d0-ffffffff81874207: rtc_tm_to_ktime (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
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
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
