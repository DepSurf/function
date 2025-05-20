# Function: <code>clock_was_set</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void clock_was_set();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff810eeb36)
Location: kernel/time/hrtimer.c:753
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:clock_was_set_work
Direct callers:
  - kernel/time/timekeeping.c:timekeeping_inject_offset
  - kernel/time/timekeeping.c:do_settimeofday64
  - kernel/time/timekeeping.c:timekeeping_set_tai_offset
  - kernel/time/timekeeping.c:timekeeping_inject_sleeptime64
  - kernel/time/timekeeping.c:do_adjtimex
```
**Symbols:**

```
ffffffff810ef830-ffffffff810ef853: clock_was_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void clock_was_set();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff810f5b76)
Location: kernel/time/hrtimer.c:743
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:clock_was_set_work
Direct callers:
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:timekeeping_inject_sleeptime64
  - kernel/time/timekeeping.c:timekeeping_set_tai_offset
  - kernel/time/timekeeping.c:timekeeping_inject_offset
  - kernel/time/timekeeping.c:do_settimeofday64
```
**Symbols:**

```
ffffffff810f68b0-ffffffff810f68d3: clock_was_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void clock_was_set();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff810fcb36)
Location: kernel/time/hrtimer.c:743
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:clock_was_set_work
Direct callers:
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:timekeeping_inject_sleeptime64
  - kernel/time/timekeeping.c:timekeeping_set_tai_offset
  - kernel/time/timekeeping.c:timekeeping_inject_offset
  - kernel/time/timekeeping.c:do_settimeofday64
```
**Symbols:**

```
ffffffff810fd8d0-ffffffff810fd8f3: clock_was_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void clock_was_set();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff810ff076)
Location: kernel/time/hrtimer.c:744
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:clock_was_set_work
Direct callers:
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:timekeeping_inject_sleeptime64
  - kernel/time/timekeeping.c:timekeeping_inject_offset
  - kernel/time/timekeeping.c:do_settimeofday64
```
**Symbols:**

```
ffffffff810ffb60-ffffffff810ffb83: clock_was_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void clock_was_set();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81109e56)
Location: kernel/time/hrtimer.c:746
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:clock_was_set_work
Direct callers:
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:timekeeping_inject_sleeptime64
  - kernel/time/timekeeping.c:timekeeping_inject_offset
  - kernel/time/timekeeping.c:do_settimeofday64
```
**Symbols:**

```
ffffffff8110a980-ffffffff8110a9a3: clock_was_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void clock_was_set();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81115835)
Location: kernel/time/hrtimer.c:857
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:clock_was_set_work
Direct callers:
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:timekeeping_inject_sleeptime64
  - kernel/time/timekeeping.c:timekeeping_inject_offset
```
**Symbols:**

```
ffffffff81116270-ffffffff81116293: clock_was_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void clock_was_set();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81120f05)
Location: kernel/time/hrtimer.c:848
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:clock_was_set_work
Direct callers:
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:timekeeping_inject_sleeptime64
  - kernel/time/timekeeping.c:timekeeping_inject_offset
```
**Symbols:**

```
ffffffff811218b0-ffffffff811218d3: clock_was_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void clock_was_set();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff8112b685)
Location: kernel/time/hrtimer.c:847
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:clock_was_set_work
Direct callers:
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:timekeeping_inject_sleeptime64
  - kernel/time/timekeeping.c:timekeeping_inject_offset
```
**Symbols:**

```
ffffffff8112c1c0-ffffffff8112c1e3: clock_was_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void clock_was_set();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81137805)
Location: kernel/time/hrtimer.c:868
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:clock_was_set_work
Direct callers:
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:timekeeping_inject_sleeptime64
  - kernel/time/timekeeping.c:timekeeping_inject_offset
```
**Symbols:**

```
ffffffff811381e0-ffffffff81138203: clock_was_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void clock_was_set();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81146335)
Location: kernel/time/hrtimer.c:868
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:clock_was_set_work
Direct callers:
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:timekeeping_inject_sleeptime64
  - kernel/time/timekeeping.c:timekeeping_inject_offset
```
**Symbols:**

```
ffffffff81146ff0-ffffffff81147013: clock_was_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void clock_was_set();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81142855)
Location: kernel/time/hrtimer.c:885
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:clock_was_set_work
Direct callers:
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:timekeeping_inject_sleeptime64
  - kernel/time/timekeeping.c:timekeeping_inject_offset
```
**Symbols:**

```
ffffffff81143490-ffffffff811434b3: clock_was_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void clock_was_set();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81143aa5)
Location: kernel/time/hrtimer.c:885
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:clock_was_set_work
Direct callers:
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:timekeeping_inject_sleeptime64
  - kernel/time/timekeeping.c:timekeeping_inject_offset
```
**Symbols:**

```
ffffffff81144640-ffffffff8114466c: clock_was_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void clock_was_set(unsigned int bases);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/hrtimer.c (0)
Location: kernel/time/hrtimer.c:945
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:clock_was_set_work
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:timekeeping_inject_sleeptime64
  - kernel/time/timekeeping.c:timekeeping_inject_offset
```
**Symbols:**

```
ffffffff81cb099f-ffffffff81cb09c6: clock_was_set.cold (STB_LOCAL)
ffffffff81167cb0-ffffffff81167eeb: clock_was_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void clock_was_set(unsigned int bases);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/hrtimer.c (0)
Location: kernel/time/hrtimer.c:945
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:clock_was_set_work
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:timekeeping_inject_sleeptime64
  - kernel/time/timekeeping.c:timekeeping_inject_offset
  - kernel/time/timekeeping.c:do_settimeofday64
```
**Symbols:**

```
ffffffff81e61f2a-ffffffff81e61f5c: clock_was_set.cold (STB_LOCAL)
ffffffff8119b670-ffffffff8119b8d6: clock_was_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void clock_was_set(unsigned int bases);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/hrtimer.c (0)
Location: kernel/time/hrtimer.c:945
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:clock_was_set_work
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:timekeeping_inject_sleeptime64
  - kernel/time/timekeeping.c:timekeeping_inject_offset
  - kernel/time/timekeeping.c:do_settimeofday64
```
**Symbols:**

```
ffffffff8205adfc-ffffffff8205ae28: clock_was_set.cold (STB_LOCAL)
ffffffff811d9f10-ffffffff811da184: clock_was_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void clock_was_set(unsigned int bases);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/hrtimer.c (0)
Location: kernel/time/hrtimer.c:947
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:clock_was_set_work
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:timekeeping_inject_sleeptime64
  - kernel/time/timekeeping.c:timekeeping_inject_offset
  - kernel/time/timekeeping.c:do_settimeofday64
```
**Symbols:**

```
ffffffff820d96ab-ffffffff820d96dc: clock_was_set.cold (STB_LOCAL)
ffffffff811ee400-ffffffff811ee6bc: clock_was_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void clock_was_set(unsigned int bases);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/hrtimer.c (0)
Location: kernel/time/hrtimer.c:947
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:clock_was_set_work
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:timekeeping_inject_sleeptime64
  - kernel/time/timekeeping.c:timekeeping_inject_offset
  - kernel/time/timekeeping.c:do_settimeofday64
```
**Symbols:**

```
ffffffff821b4faa-ffffffff821b4fdb: clock_was_set.cold (STB_LOCAL)
ffffffff81204580-ffffffff8120483c: clock_was_set (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void clock_was_set();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffff8000101a0b38)
Location: kernel/time/hrtimer.c:868
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:clock_was_set_work
Direct callers:
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:timekeeping_inject_sleeptime64
  - kernel/time/timekeeping.c:timekeeping_inject_offset
```
**Symbols:**

```
ffff8000101a1c80-ffff8000101a1cb0: clock_was_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void clock_was_set();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (c03ea92c)
Location: kernel/time/hrtimer.c:868
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:clock_was_set_work
Direct callers:
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:timekeeping_inject_sleeptime64
  - kernel/time/timekeeping.c:timekeeping_inject_offset
```
**Symbols:**

```
c03eba80-c03ebab0: clock_was_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void clock_was_set();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (c000000000201f9c)
Location: kernel/time/hrtimer.c:868
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:clock_was_set_work
Direct callers:
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:timekeeping_inject_sleeptime64
  - kernel/time/timekeeping.c:timekeeping_inject_offset
```
**Symbols:**

```
c000000000203090-c0000000002030dc: clock_was_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void clock_was_set();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffe00012e468)
Location: kernel/time/hrtimer.c:868
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:clock_was_set_work
Direct callers:
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:timekeeping_inject_offset
```
**Symbols:**

```
ffffffe00012efac-ffffffe00012efe2: clock_was_set (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void clock_was_set();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff8112ffb5)
Location: kernel/time/hrtimer.c:868
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:clock_was_set_work
Direct callers:
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:timekeeping_inject_sleeptime64
  - kernel/time/timekeeping.c:timekeeping_inject_offset
```
**Symbols:**

```
ffffffff81130990-ffffffff811309b3: clock_was_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void clock_was_set();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81122a25)
Location: kernel/time/hrtimer.c:868
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:clock_was_set_work
Direct callers:
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:timekeeping_inject_sleeptime64
  - kernel/time/timekeeping.c:timekeeping_inject_offset
```
**Symbols:**

```
ffffffff81123400-ffffffff81123423: clock_was_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void clock_was_set();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff8112dcd5)
Location: kernel/time/hrtimer.c:868
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:clock_was_set_work
Direct callers:
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:timekeeping_inject_sleeptime64
  - kernel/time/timekeeping.c:timekeeping_inject_offset
```
**Symbols:**

```
ffffffff8112e6b0-ffffffff8112e6d3: clock_was_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void clock_was_set();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff8113a625)
Location: kernel/time/hrtimer.c:868
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:clock_was_set_work
Direct callers:
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:timekeeping_inject_sleeptime64
  - kernel/time/timekeeping.c:timekeeping_inject_offset
```
**Symbols:**

```
ffffffff8113b0b0-ffffffff8113b0d3: clock_was_set (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int bases</code>
</li>
</ul>
</details>
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
