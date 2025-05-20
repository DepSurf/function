# Function: <code>schedule_hrtimeout_range_clock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int schedule_hrtimeout_range_clock(ktime_t *expires, long unsigned int delta, const enum hrtimer_mode mode, int clock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81823820)
Location: kernel/time/hrtimer.c:1727
Inline: True
Direct callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout
```
**Symbols:**

```
ffffffff81823820-ffffffff818239c2: schedule_hrtimeout_range_clock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int schedule_hrtimeout_range_clock(ktime_t *expires, u64 delta, const enum hrtimer_mode mode, int clock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff8189e4a0)
Location: kernel/time/hrtimer.c:1687
Inline: True
Direct callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout
```
**Symbols:**

```
ffffffff8189e4a0-ffffffff8189e64e: schedule_hrtimeout_range_clock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int schedule_hrtimeout_range_clock(ktime_t *expires, u64 delta, const enum hrtimer_mode mode, int clock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff818d3340)
Location: kernel/time/hrtimer.c:1687
Inline: True
Direct callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout
```
**Symbols:**

```
ffffffff818d3340-ffffffff818d34f0: schedule_hrtimeout_range_clock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int schedule_hrtimeout_range_clock(ktime_t *expires, u64 delta, const enum hrtimer_mode mode, int clock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff8190a4f0)
Location: kernel/time/hrtimer.c:1678
Inline: True
Direct callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout
```
**Symbols:**

```
ffffffff8190a4f0-ffffffff8190a67d: schedule_hrtimeout_range_clock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int schedule_hrtimeout_range_clock(ktime_t *expires, u64 delta, const enum hrtimer_mode mode, int clock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81994850)
Location: kernel/time/hrtimer.c:1684
Inline: True
Direct callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout
```
**Symbols:**

```
ffffffff81994850-ffffffff819949e0: schedule_hrtimeout_range_clock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int schedule_hrtimeout_range_clock(ktime_t *expires, u64 delta, const enum hrtimer_mode mode, clockid_t clock_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff819f0de0)
Location: kernel/time/hrtimer.c:1918
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout
```
**Symbols:**

```
ffffffff819f0de0-ffffffff819f0f80: schedule_hrtimeout_range_clock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int schedule_hrtimeout_range_clock(ktime_t *expires, u64 delta, const enum hrtimer_mode mode, clockid_t clock_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81a2c160)
Location: kernel/time/hrtimer.c:1908
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout
```
**Symbols:**

```
ffffffff81a2c160-ffffffff81a2c300: schedule_hrtimeout_range_clock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int schedule_hrtimeout_range_clock(ktime_t *expires, u64 delta, const enum hrtimer_mode mode, clockid_t clock_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81a9c300)
Location: kernel/time/hrtimer.c:1908
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout
```
**Symbols:**

```
ffffffff81a9c300-ffffffff81a9c498: schedule_hrtimeout_range_clock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int schedule_hrtimeout_range_clock(ktime_t *expires, u64 delta, const enum hrtimer_mode mode, clockid_t clock_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81ad3be0)
Location: kernel/time/hrtimer.c:2103
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout
```
**Symbols:**

```
ffffffff81ad3be0-ffffffff81ad3ce5: schedule_hrtimeout_range_clock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int schedule_hrtimeout_range_clock(ktime_t *expires, u64 delta, const enum hrtimer_mode mode, clockid_t clock_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81bcbbf0)
Location: kernel/time/hrtimer.c:2110
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout
  - ipc/mqueue.c:wq_sleep
```
**Symbols:**

```
ffffffff81bcbbf0-ffffffff81bcbd10: schedule_hrtimeout_range_clock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int schedule_hrtimeout_range_clock(ktime_t *expires, u64 delta, const enum hrtimer_mode mode, clockid_t clock_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81c44a10)
Location: kernel/time/hrtimer.c:2130
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout
  - ipc/mqueue.c:wq_sleep
```
**Symbols:**

```
ffffffff81c44a10-ffffffff81c44b30: schedule_hrtimeout_range_clock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int schedule_hrtimeout_range_clock(ktime_t *expires, u64 delta, const enum hrtimer_mode mode, clockid_t clock_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81c37c80)
Location: kernel/time/hrtimer.c:2130
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout
  - ipc/mqueue.c:wq_sleep
```
**Symbols:**

```
ffffffff81c37c80-ffffffff81c37d9d: schedule_hrtimeout_range_clock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int schedule_hrtimeout_range_clock(ktime_t *expires, u64 delta, const enum hrtimer_mode mode, clockid_t clock_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81d56540)
Location: kernel/time/hrtimer.c:2278
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout
  - ipc/mqueue.c:wq_sleep
```
**Symbols:**

```
ffffffff81d56540-ffffffff81d5665b: schedule_hrtimeout_range_clock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int schedule_hrtimeout_range_clock(ktime_t *expires, u64 delta, const enum hrtimer_mode mode, clockid_t clock_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81f28360)
Location: kernel/time/hrtimer.c:2278
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout
  - ipc/mqueue.c:wq_sleep
```
**Symbols:**

```
ffffffff81f28360-ffffffff81f28483: schedule_hrtimeout_range_clock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int schedule_hrtimeout_range_clock(ktime_t *expires, u64 delta, const enum hrtimer_mode mode, clockid_t clock_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff820d3fb0)
Location: kernel/time/hrtimer.c:2280
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout
  - ipc/mqueue.c:wq_sleep
```
**Symbols:**

```
ffffffff820d3fb0-ffffffff820d40d3: schedule_hrtimeout_range_clock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int schedule_hrtimeout_range_clock(ktime_t *expires, u64 delta, const enum hrtimer_mode mode, clockid_t clock_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff82158230)
Location: kernel/time/hrtimer.c:2283
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout
  - ipc/mqueue.c:wq_sleep
```
**Symbols:**

```
ffffffff82158230-ffffffff82158376: schedule_hrtimeout_range_clock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int schedule_hrtimeout_range_clock(ktime_t *expires, u64 delta, const enum hrtimer_mode mode, clockid_t clock_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff8223b0a0)
Location: kernel/time/hrtimer.c:2277
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout
  - ipc/mqueue.c:wq_sleep
```
**Symbols:**

```
ffffffff8223b0a0-ffffffff8223b1e6: schedule_hrtimeout_range_clock (STB_GLOBAL)
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
int schedule_hrtimeout_range_clock(ktime_t *expires, u64 delta, const enum hrtimer_mode mode, clockid_t clock_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffff800010da6780)
Location: kernel/time/hrtimer.c:2103
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout
```
**Symbols:**

```
ffff800010da6780-ffff800010da6890: schedule_hrtimeout_range_clock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int schedule_hrtimeout_range_clock(ktime_t *expires, u64 delta, const enum hrtimer_mode mode, clockid_t clock_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (c0e9e568)
Location: kernel/time/hrtimer.c:2103
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout
```
**Symbols:**

```
c0e9e568-c0e9e6bc: schedule_hrtimeout_range_clock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int schedule_hrtimeout_range_clock(ktime_t *expires, u64 delta, const enum hrtimer_mode mode, clockid_t clock_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (c000000000ee8fc0)
Location: kernel/time/hrtimer.c:2103
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout
```
**Symbols:**

```
c000000000ee8fc0-c000000000ee9110: schedule_hrtimeout_range_clock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int schedule_hrtimeout_range_clock(ktime_t *expires, u64 delta, const enum hrtimer_mode mode, clockid_t clock_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffe0008c8b56)
Location: kernel/time/hrtimer.c:2103
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout
```
**Symbols:**

```
ffffffe0008c8b56-ffffffe0008c8c24: schedule_hrtimeout_range_clock (STB_GLOBAL)
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
int schedule_hrtimeout_range_clock(ktime_t *expires, u64 delta, const enum hrtimer_mode mode, clockid_t clock_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81a72a50)
Location: kernel/time/hrtimer.c:2103
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout
```
**Symbols:**

```
ffffffff81a72a50-ffffffff81a72b55: schedule_hrtimeout_range_clock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int schedule_hrtimeout_range_clock(ktime_t *expires, u64 delta, const enum hrtimer_mode mode, clockid_t clock_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81a2ee20)
Location: kernel/time/hrtimer.c:2103
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout
```
**Symbols:**

```
ffffffff81a2ee20-ffffffff81a2ef25: schedule_hrtimeout_range_clock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int schedule_hrtimeout_range_clock(ktime_t *expires, u64 delta, const enum hrtimer_mode mode, clockid_t clock_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81adee60)
Location: kernel/time/hrtimer.c:2103
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout
```
**Symbols:**

```
ffffffff81adee60-ffffffff81adef65: schedule_hrtimeout_range_clock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int schedule_hrtimeout_range_clock(ktime_t *expires, u64 delta, const enum hrtimer_mode mode, clockid_t clock_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81aeb2f0)
Location: kernel/time/hrtimer.c:2103
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout
```
**Symbols:**

```
ffffffff81aeb2f0-ffffffff81aeb3f5: schedule_hrtimeout_range_clock (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>long unsigned int delta</code> ➡️ <code>u64 delta</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>clockid_t clock_id</code>
</li>
<li>
<b>Param removed. </b>
<code>int clock</code>
</li>
</ul>
</details>
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
