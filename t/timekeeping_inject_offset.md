# Function: <code>timekeeping_inject_offset</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int timekeeping_inject_offset(struct timespec *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff810f4f90)
Location: kernel/time/timekeeping.c:1203
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:do_adjtimex
```
**Symbols:**

```
ffffffff810f4f90-ffffffff810f513e: timekeeping_inject_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int timekeeping_inject_offset(struct timespec *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff810fc150)
Location: kernel/time/timekeeping.c:1208
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:do_adjtimex
```
**Symbols:**

```
ffffffff810fc150-ffffffff810fc2fe: timekeeping_inject_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int timekeeping_inject_offset(struct timespec *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff810ff050)
Location: kernel/time/timekeeping.c:1237
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:do_adjtimex
```
**Symbols:**

```
ffffffff810ff050-ffffffff810ff1fe: timekeeping_inject_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int timekeeping_inject_offset(struct timespec *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff811016e0)
Location: kernel/time/timekeeping.c:1267
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:do_adjtimex
```
**Symbols:**

```
ffffffff811016e0-ffffffff81101847: timekeeping_inject_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int timekeeping_inject_offset(struct timespec *ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff8110c520)
Location: kernel/time/timekeeping.c:1271
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:timekeeping_warp_clock
```
**Symbols:**

```
ffffffff8110c520-ffffffff8110c67c: timekeeping_inject_offset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int timekeeping_inject_offset(struct timespec64 *ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81117f30)
Location: kernel/time/timekeeping.c:1272
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:timekeeping_warp_clock
```
**Symbols:**

```
ffffffff81117f30-ffffffff8111808b: timekeeping_inject_offset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int timekeeping_inject_offset(const struct timespec64 *ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81123550)
Location: kernel/time/timekeeping.c:1263
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:timekeeping_warp_clock
```
**Symbols:**

```
ffffffff81123550-ffffffff811236ab: timekeeping_inject_offset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int timekeeping_inject_offset(const struct timespec64 *ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff8112dc90)
Location: kernel/time/timekeeping.c:1273
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:timekeeping_warp_clock
```
**Symbols:**

```
ffffffff8112dc90-ffffffff8112ddec: timekeeping_inject_offset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int timekeeping_inject_offset(const struct timespec64 *ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81139c40)
Location: kernel/time/timekeeping.c:1273
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:timekeeping_warp_clock
```
**Symbols:**

```
ffffffff81139c40-ffffffff81139d9c: timekeeping_inject_offset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int timekeeping_inject_offset(const struct timespec64 *ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81148d50)
Location: kernel/time/timekeeping.c:1272
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:timekeeping_warp_clock
```
**Symbols:**

```
ffffffff81148d50-ffffffff81148f3c: timekeeping_inject_offset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int timekeeping_inject_offset(const struct timespec64 *ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff811451c0)
Location: kernel/time/timekeeping.c:1341
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:timekeeping_warp_clock
```
**Symbols:**

```
ffffffff811451c0-ffffffff811453ac: timekeeping_inject_offset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int timekeeping_inject_offset(const struct timespec64 *ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81146280)
Location: kernel/time/timekeeping.c:1342
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:timekeeping_warp_clock
```
**Symbols:**

```
ffffffff81146280-ffffffff8114646c: timekeeping_inject_offset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int timekeeping_inject_offset(const struct timespec64 *ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/timekeeping.c (0)
Location: kernel/time/timekeeping.c:1341
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:timekeeping_warp_clock
```
**Symbols:**

```
ffffffff8116a500-ffffffff8116a70e: timekeeping_inject_offset (STB_LOCAL)
ffffffff81cb0f99-ffffffff81cb1096: timekeeping_inject_offset.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int timekeeping_inject_offset(const struct timespec64 *ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/timekeeping.c (0)
Location: kernel/time/timekeeping.c:1362
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:timekeeping_warp_clock
```
**Symbols:**

```
ffffffff8119e090-ffffffff8119e2c8: timekeeping_inject_offset (STB_LOCAL)
ffffffff81e624eb-ffffffff81e625e8: timekeeping_inject_offset.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int timekeeping_inject_offset(const struct timespec64 *ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/timekeeping.c (0)
Location: kernel/time/timekeeping.c:1362
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:timekeeping_warp_clock
```
**Symbols:**

```
ffffffff811dcc60-ffffffff811dce98: timekeeping_inject_offset (STB_LOCAL)
ffffffff8205b338-ffffffff8205b435: timekeeping_inject_offset.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int timekeeping_inject_offset(const struct timespec64 *ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/timekeeping.c (0)
Location: kernel/time/timekeeping.c:1362
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:timekeeping_warp_clock
```
**Symbols:**

```
ffffffff811f1180-ffffffff811f13b0: timekeeping_inject_offset (STB_LOCAL)
ffffffff820d9be7-ffffffff820d9cfe: timekeeping_inject_offset.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int timekeeping_inject_offset(const struct timespec64 *ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/timekeeping.c (0)
Location: kernel/time/timekeeping.c:1362
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:timekeeping_warp_clock
```
**Symbols:**

```
ffffffff812072c0-ffffffff812074f0: timekeeping_inject_offset (STB_LOCAL)
ffffffff821b54e6-ffffffff821b55fd: timekeeping_inject_offset.cold (STB_LOCAL)
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
int timekeeping_inject_offset(const struct timespec64 *ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffff8000101a4328)
Location: kernel/time/timekeeping.c:1273
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:timekeeping_warp_clock
```
**Symbols:**

```
ffff8000101a4328-ffff8000101a4514: timekeeping_inject_offset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int timekeeping_inject_offset(const struct timespec64 *ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (c03ee1dc)
Location: kernel/time/timekeeping.c:1273
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:timekeeping_warp_clock
```
**Symbols:**

```
c03ee1dc-c03ee52c: timekeeping_inject_offset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int timekeeping_inject_offset(const struct timespec64 *ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (c000000000205850)
Location: kernel/time/timekeeping.c:1273
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:timekeeping_warp_clock
```
**Symbols:**

```
c000000000205850-c000000000205a78: timekeeping_inject_offset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int timekeeping_inject_offset(const struct timespec64 *ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffe00013072c)
Location: kernel/time/timekeeping.c:1273
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:timekeeping_warp_clock
```
**Symbols:**

```
ffffffe00013072c-ffffffe000130872: timekeeping_inject_offset (STB_LOCAL)
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
int timekeeping_inject_offset(const struct timespec64 *ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff811323f0)
Location: kernel/time/timekeeping.c:1273
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:timekeeping_warp_clock
```
**Symbols:**

```
ffffffff811323f0-ffffffff8113254c: timekeeping_inject_offset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int timekeeping_inject_offset(const struct timespec64 *ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81124e50)
Location: kernel/time/timekeeping.c:1273
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:timekeeping_warp_clock
```
**Symbols:**

```
ffffffff81124e50-ffffffff81124fac: timekeeping_inject_offset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int timekeeping_inject_offset(const struct timespec64 *ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81130110)
Location: kernel/time/timekeeping.c:1273
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:timekeeping_warp_clock
```
**Symbols:**

```
ffffffff81130110-ffffffff8113026c: timekeeping_inject_offset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int timekeeping_inject_offset(const struct timespec64 *ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff8113cb30)
Location: kernel/time/timekeeping.c:1273
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:timekeeping_warp_clock
```
**Symbols:**

```
ffffffff8113cb30-ffffffff8113cc8c: timekeeping_inject_offset (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct timespec *ts</code> ➡️ <code>struct timespec64 *ts</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct timespec64 *ts</code> ➡️ <code>const struct timespec64 *ts</code>
</li>
</ul>
</details>
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
