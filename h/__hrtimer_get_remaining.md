# Function: <code>__hrtimer_get_remaining</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
ktime_t __hrtimer_get_remaining(const struct hrtimer *timer, bool adjust);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff810eee40)
Location: kernel/time/hrtimer.c:1086
Inline: False
Direct callers:
  - kernel/time/itimer.c:itimer_get_remtime
```
**Symbols:**

```
ffffffff810eee40-ffffffff810eeead: __hrtimer_get_remaining (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
ktime_t __hrtimer_get_remaining(const struct hrtimer *timer, bool adjust);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff810f5f00)
Location: kernel/time/hrtimer.c:1076
Inline: False
Direct callers:
  - kernel/time/itimer.c:itimer_get_remtime
```
**Symbols:**

```
ffffffff810f5f00-ffffffff810f5f6d: __hrtimer_get_remaining (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
ktime_t __hrtimer_get_remaining(const struct hrtimer *timer, bool adjust);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff810fd030)
Location: kernel/time/hrtimer.c:1076
Inline: False
Direct callers:
  - kernel/time/itimer.c:itimer_get_remtime
```
**Symbols:**

```
ffffffff810fd030-ffffffff810fd09d: __hrtimer_get_remaining (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
ktime_t __hrtimer_get_remaining(const struct hrtimer *timer, bool adjust);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff810ff3c0)
Location: kernel/time/hrtimer.c:1046
Inline: False
Direct callers:
  - kernel/time/itimer.c:itimer_get_remtime
```
**Symbols:**

```
ffffffff810ff3c0-ffffffff810ff42d: __hrtimer_get_remaining (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
ktime_t __hrtimer_get_remaining(const struct hrtimer *timer, bool adjust);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff8110a1b0)
Location: kernel/time/hrtimer.c:1046
Inline: False
Direct callers:
  - kernel/time/itimer.c:itimer_get_remtime
```
**Symbols:**

```
ffffffff8110a1b0-ffffffff8110a223: __hrtimer_get_remaining (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
ktime_t __hrtimer_get_remaining(const struct hrtimer *timer, bool adjust);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff811159a0)
Location: kernel/time/hrtimer.c:1184
Inline: False
Direct callers:
  - kernel/time/itimer.c:itimer_get_remtime
```
**Symbols:**

```
ffffffff811159a0-ffffffff81115a13: __hrtimer_get_remaining (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
ktime_t __hrtimer_get_remaining(const struct hrtimer *timer, bool adjust);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81121070)
Location: kernel/time/hrtimer.c:1175
Inline: False
Direct callers:
  - kernel/time/itimer.c:itimer_get_remtime
  - kernel/events/core.c:cpu_clock_event_stop
```
**Symbols:**

```
ffffffff81121070-ffffffff811210e3: __hrtimer_get_remaining (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
ktime_t __hrtimer_get_remaining(const struct hrtimer *timer, bool adjust);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff8112b890)
Location: kernel/time/hrtimer.c:1175
Inline: False
Direct callers:
  - kernel/time/itimer.c:itimer_get_remtime
```
**Symbols:**

```
ffffffff8112b890-ffffffff8112b903: __hrtimer_get_remaining (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
ktime_t __hrtimer_get_remaining(const struct hrtimer *timer, bool adjust);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff811372b0)
Location: kernel/time/hrtimer.c:1292
Inline: False
Direct callers:
  - kernel/time/itimer.c:itimer_get_remtime
```
**Symbols:**

```
ffffffff811372b0-ffffffff8113731f: __hrtimer_get_remaining (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
ktime_t __hrtimer_get_remaining(const struct hrtimer *timer, bool adjust);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81146500)
Location: kernel/time/hrtimer.c:1292
Inline: False
Direct callers:
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/itimer.c:do_getitimer
  - kernel/events/core.c:task_clock_event_del
  - kernel/events/core.c:cpu_clock_event_del
```
**Symbols:**

```
ffffffff81146500-ffffffff8114656e: __hrtimer_get_remaining (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ktime_t __hrtimer_get_remaining(const struct hrtimer *timer, bool adjust);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81142b20)
Location: kernel/time/hrtimer.c:1309
Inline: False
Direct callers:
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/itimer.c:do_getitimer
  - kernel/events/core.c:task_clock_event_del
  - kernel/events/core.c:cpu_clock_event_del
```
**Symbols:**

```
ffffffff81142b20-ffffffff81142b8e: __hrtimer_get_remaining (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ktime_t __hrtimer_get_remaining(const struct hrtimer *timer, bool adjust);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81144050)
Location: kernel/time/hrtimer.c:1309
Inline: False
Direct callers:
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/itimer.c:do_getitimer
  - kernel/events/core.c:task_clock_event_del
  - kernel/events/core.c:cpu_clock_event_del
```
**Symbols:**

```
ffffffff81144050-ffffffff811440be: __hrtimer_get_remaining (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
ktime_t __hrtimer_get_remaining(const struct hrtimer *timer, bool adjust);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81167600)
Location: kernel/time/hrtimer.c:1457
Inline: False
Direct callers:
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/itimer.c:do_getitimer
  - kernel/events/core.c:task_clock_event_del
  - kernel/events/core.c:cpu_clock_event_del
```
**Symbols:**

```
ffffffff81167600-ffffffff8116766e: __hrtimer_get_remaining (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
ktime_t __hrtimer_get_remaining(const struct hrtimer *timer, bool adjust);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff8119b1b0)
Location: kernel/time/hrtimer.c:1457
Inline: False
Direct callers:
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/itimer.c:do_getitimer
  - kernel/events/core.c:task_clock_event_del
  - kernel/events/core.c:cpu_clock_event_del
```
**Symbols:**

```
ffffffff8119b1b0-ffffffff8119b226: __hrtimer_get_remaining (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ktime_t __hrtimer_get_remaining(const struct hrtimer *timer, bool adjust);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff811d9a10)
Location: kernel/time/hrtimer.c:1457
Inline: False
Direct callers:
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/itimer.c:do_getitimer
  - kernel/events/core.c:task_clock_event_del
  - kernel/events/core.c:cpu_clock_event_del
```
**Symbols:**

```
ffffffff811d9a10-ffffffff811d9a86: __hrtimer_get_remaining (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ktime_t __hrtimer_get_remaining(const struct hrtimer *timer, bool adjust);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff811ee1c0)
Location: kernel/time/hrtimer.c:1460
Inline: False
Direct callers:
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/itimer.c:do_getitimer
  - kernel/events/core.c:task_clock_event_del
  - kernel/events/core.c:cpu_clock_event_del
```
**Symbols:**

```
ffffffff811ee1c0-ffffffff811ee236: __hrtimer_get_remaining (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ktime_t __hrtimer_get_remaining(const struct hrtimer *timer, bool adjust);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81203860)
Location: kernel/time/hrtimer.c:1461
Inline: False
Direct callers:
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/itimer.c:do_getitimer
  - kernel/events/core.c:task_clock_event_del
  - kernel/events/core.c:cpu_clock_event_del
```
**Symbols:**

```
ffffffff81203860-ffffffff812038d6: __hrtimer_get_remaining (STB_GLOBAL)
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
ktime_t __hrtimer_get_remaining(const struct hrtimer *timer, bool adjust);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffff8000101a1400)
Location: kernel/time/hrtimer.c:1292
Inline: False
Direct callers:
  - kernel/time/itimer.c:itimer_get_remtime
  - kernel/events/core.c:task_clock_event_stop
```
**Symbols:**

```
ffff8000101a1400-ffff8000101a1490: __hrtimer_get_remaining (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
ktime_t __hrtimer_get_remaining(const struct hrtimer *timer, bool adjust);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (c03ea23c)
Location: kernel/time/hrtimer.c:1292
Inline: False
Direct callers:
  - kernel/time/itimer.c:itimer_get_remtime
```
**Symbols:**

```
c03ea23c-c03ea2d0: __hrtimer_get_remaining (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
ktime_t __hrtimer_get_remaining(const struct hrtimer *timer, bool adjust);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (c0000000002015d0)
Location: kernel/time/hrtimer.c:1292
Inline: False
Direct callers:
  - kernel/time/itimer.c:itimer_get_remtime
```
**Symbols:**

```
c0000000002015d0-c000000000201678: __hrtimer_get_remaining (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
ktime_t __hrtimer_get_remaining(const struct hrtimer *timer, bool adjust);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffe00012e050)
Location: kernel/time/hrtimer.c:1292
Inline: False
Direct callers:
  - kernel/time/itimer.c:itimer_get_remtime
  - kernel/events/core.c:cpu_clock_event_stop
```
**Symbols:**

```
ffffffe00012e050-ffffffe00012e0a2: __hrtimer_get_remaining (STB_GLOBAL)
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
ktime_t __hrtimer_get_remaining(const struct hrtimer *timer, bool adjust);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff8112fa60)
Location: kernel/time/hrtimer.c:1292
Inline: False
Direct callers:
  - kernel/time/itimer.c:itimer_get_remtime
```
**Symbols:**

```
ffffffff8112fa60-ffffffff8112facf: __hrtimer_get_remaining (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
ktime_t __hrtimer_get_remaining(const struct hrtimer *timer, bool adjust);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff811224d0)
Location: kernel/time/hrtimer.c:1292
Inline: False
Direct callers:
  - kernel/time/itimer.c:itimer_get_remtime
```
**Symbols:**

```
ffffffff811224d0-ffffffff8112253f: __hrtimer_get_remaining (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
ktime_t __hrtimer_get_remaining(const struct hrtimer *timer, bool adjust);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff8112d780)
Location: kernel/time/hrtimer.c:1292
Inline: False
Direct callers:
  - kernel/time/itimer.c:itimer_get_remtime
```
**Symbols:**

```
ffffffff8112d780-ffffffff8112d7ef: __hrtimer_get_remaining (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
ktime_t __hrtimer_get_remaining(const struct hrtimer *timer, bool adjust);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff8113a0b0)
Location: kernel/time/hrtimer.c:1292
Inline: False
Direct callers:
  - kernel/time/itimer.c:itimer_get_remtime
```
**Symbols:**

```
ffffffff8113a0b0-ffffffff8113a11f: __hrtimer_get_remaining (STB_GLOBAL)
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
