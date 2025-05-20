# Function: <code>posix_cpu_clock_get</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int posix_cpu_clock_get(const clockid_t which_clock, struct timespec *tp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff810f2a80)
Location: kernel/time/posix-cpu-timers.c:309
Inline: True
Direct callers:
  - kernel/time/posix-cpu-timers.c:thread_cpu_clock_get
  - kernel/time/posix-cpu-timers.c:process_cpu_clock_get
```
**Symbols:**

```
ffffffff810f2a80-ffffffff810f2ad4: posix_cpu_clock_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int posix_cpu_clock_get(const clockid_t which_clock, struct timespec *tp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff810f9b90)
Location: kernel/time/posix-cpu-timers.c:309
Inline: True
Direct callers:
  - kernel/time/posix-cpu-timers.c:thread_cpu_clock_get
  - kernel/time/posix-cpu-timers.c:process_cpu_clock_get
```
**Symbols:**

```
ffffffff810f9b90-ffffffff810f9be4: posix_cpu_clock_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int posix_cpu_clock_get(const clockid_t which_clock, struct timespec *tp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff81107520)
Location: kernel/time/posix-cpu-timers.c:308
Inline: True
Direct callers:
  - kernel/time/posix-cpu-timers.c:thread_cpu_clock_get
  - kernel/time/posix-cpu-timers.c:process_cpu_clock_get
```
**Symbols:**

```
ffffffff81107520-ffffffff81107574: posix_cpu_clock_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int posix_cpu_clock_get(const clockid_t which_clock, struct timespec *tp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff811098b0)
Location: kernel/time/posix-cpu-timers.c:289
Inline: True
Direct callers:
  - kernel/time/posix-cpu-timers.c:thread_cpu_clock_get
  - kernel/time/posix-cpu-timers.c:process_cpu_clock_get
```
**Symbols:**

```
ffffffff811098b0-ffffffff81109904: posix_cpu_clock_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int posix_cpu_clock_get(const clockid_t which_clock, struct timespec *tp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff81114a90)
Location: kernel/time/posix-cpu-timers.c:290
Inline: True
Direct callers:
  - kernel/time/posix-cpu-timers.c:thread_cpu_clock_get
  - kernel/time/posix-cpu-timers.c:process_cpu_clock_get
```
**Symbols:**

```
ffffffff81114a90-ffffffff81114ae4: posix_cpu_clock_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int posix_cpu_clock_get(const clockid_t which_clock, struct timespec64 *tp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff81121230)
Location: kernel/time/posix-cpu-timers.c:291
Inline: True
Direct callers:
  - kernel/time/posix-cpu-timers.c:thread_cpu_clock_get
  - kernel/time/posix-cpu-timers.c:process_cpu_clock_get
```
**Symbols:**

```
ffffffff81121230-ffffffff81121284: posix_cpu_clock_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int posix_cpu_clock_get(const clockid_t which_clock, struct timespec64 *tp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff8112c950)
Location: kernel/time/posix-cpu-timers.c:291
Inline: True
Direct callers:
  - kernel/time/posix-cpu-timers.c:thread_cpu_clock_get
  - kernel/time/posix-cpu-timers.c:process_cpu_clock_get
```
**Symbols:**

```
ffffffff8112c950-ffffffff8112c9a4: posix_cpu_clock_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int posix_cpu_clock_get(const clockid_t which_clock, struct timespec64 *tp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff81137320)
Location: kernel/time/posix-cpu-timers.c:291
Inline: True
Direct callers:
  - kernel/time/posix-cpu-timers.c:thread_cpu_clock_get
  - kernel/time/posix-cpu-timers.c:process_cpu_clock_get
```
**Symbols:**

```
ffffffff81137320-ffffffff81137378: posix_cpu_clock_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int posix_cpu_clock_get(const clockid_t clock, struct timespec64 *tp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff81143b70)
Location: kernel/time/posix-cpu-timers.c:362
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:thread_cpu_clock_get
  - kernel/time/posix-cpu-timers.c:process_cpu_clock_get
```
**Symbols:**

```
ffffffff81143b70-ffffffff81143c00: posix_cpu_clock_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int posix_cpu_clock_get(const clockid_t clock, struct timespec64 *tp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff81153270)
Location: kernel/time/posix-cpu-timers.c:350
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:thread_cpu_clock_get
  - kernel/time/posix-cpu-timers.c:process_cpu_clock_get
```
**Symbols:**

```
ffffffff81153270-ffffffff811532ed: posix_cpu_clock_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int posix_cpu_clock_get(const clockid_t clock, struct timespec64 *tp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff8114f520)
Location: kernel/time/posix-cpu-timers.c:350
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:thread_cpu_clock_get
  - kernel/time/posix-cpu-timers.c:process_cpu_clock_get
```
**Symbols:**

```
ffffffff8114f520-ffffffff8114f5aa: posix_cpu_clock_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int posix_cpu_clock_get(const clockid_t clock, struct timespec64 *tp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff811509b0)
Location: kernel/time/posix-cpu-timers.c:350
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:thread_cpu_clock_get
  - kernel/time/posix-cpu-timers.c:process_cpu_clock_get
```
**Symbols:**

```
ffffffff811509b0-ffffffff81150a3a: posix_cpu_clock_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int posix_cpu_clock_get(const clockid_t clock, struct timespec64 *tp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff81174690)
Location: kernel/time/posix-cpu-timers.c:352
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:thread_cpu_clock_get
  - kernel/time/posix-cpu-timers.c:process_cpu_clock_get
```
**Symbols:**

```
ffffffff81174690-ffffffff81174742: posix_cpu_clock_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int posix_cpu_clock_get(const clockid_t clock, struct timespec64 *tp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff811a94a0)
Location: kernel/time/posix-cpu-timers.c:359
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:thread_cpu_clock_get
  - kernel/time/posix-cpu-timers.c:process_cpu_clock_get
```
**Symbols:**

```
ffffffff811a94a0-ffffffff811a956a: posix_cpu_clock_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int posix_cpu_clock_get(const clockid_t clock, struct timespec64 *tp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff811e93a0)
Location: kernel/time/posix-cpu-timers.c:359
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:thread_cpu_clock_get
  - kernel/time/posix-cpu-timers.c:process_cpu_clock_get
```
**Symbols:**

```
ffffffff811e93a0-ffffffff811e946a: posix_cpu_clock_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int posix_cpu_clock_get(const clockid_t clock, struct timespec64 *tp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff811fda90)
Location: kernel/time/posix-cpu-timers.c:358
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:thread_cpu_clock_get
  - kernel/time/posix-cpu-timers.c:process_cpu_clock_get
```
**Symbols:**

```
ffffffff811fda90-ffffffff811fdb5a: posix_cpu_clock_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int posix_cpu_clock_get(const clockid_t clock, struct timespec64 *tp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff81213ea0)
Location: kernel/time/posix-cpu-timers.c:358
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:thread_cpu_clock_get
  - kernel/time/posix-cpu-timers.c:process_cpu_clock_get
```
**Symbols:**

```
ffffffff81213ea0-ffffffff81213f43: posix_cpu_clock_get (STB_LOCAL)
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
int posix_cpu_clock_get(const clockid_t clock, struct timespec64 *tp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffff8000101ad918)
Location: kernel/time/posix-cpu-timers.c:362
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:thread_cpu_clock_get
  - kernel/time/posix-cpu-timers.c:process_cpu_clock_get
```
**Symbols:**

```
ffff8000101ad918-ffff8000101ad9d4: posix_cpu_clock_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int posix_cpu_clock_get(const clockid_t clock, struct timespec64 *tp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (c03f93e8)
Location: kernel/time/posix-cpu-timers.c:362
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:thread_cpu_clock_get
  - kernel/time/posix-cpu-timers.c:process_cpu_clock_get
```
**Symbols:**

```
c03f93e8-c03f94d4: posix_cpu_clock_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int posix_cpu_clock_get(const clockid_t clock, struct timespec64 *tp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (c0000000002123b0)
Location: kernel/time/posix-cpu-timers.c:362
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:thread_cpu_clock_get
  - kernel/time/posix-cpu-timers.c:process_cpu_clock_get
```
**Symbols:**

```
c0000000002123b0-c0000000002124bc: posix_cpu_clock_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int posix_cpu_clock_get(const clockid_t clock, struct timespec64 *tp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffe00013787c)
Location: kernel/time/posix-cpu-timers.c:362
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:thread_cpu_clock_get
  - kernel/time/posix-cpu-timers.c:process_cpu_clock_get
```
**Symbols:**

```
ffffffe00013787c-ffffffe000137926: posix_cpu_clock_get (STB_LOCAL)
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
int posix_cpu_clock_get(const clockid_t clock, struct timespec64 *tp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff8113c320)
Location: kernel/time/posix-cpu-timers.c:362
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:thread_cpu_clock_get
  - kernel/time/posix-cpu-timers.c:process_cpu_clock_get
```
**Symbols:**

```
ffffffff8113c320-ffffffff8113c3b0: posix_cpu_clock_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int posix_cpu_clock_get(const clockid_t clock, struct timespec64 *tp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff8112ede0)
Location: kernel/time/posix-cpu-timers.c:362
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:thread_cpu_clock_get
  - kernel/time/posix-cpu-timers.c:process_cpu_clock_get
```
**Symbols:**

```
ffffffff8112ede0-ffffffff8112ee70: posix_cpu_clock_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int posix_cpu_clock_get(const clockid_t clock, struct timespec64 *tp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff8113a040)
Location: kernel/time/posix-cpu-timers.c:362
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:thread_cpu_clock_get
  - kernel/time/posix-cpu-timers.c:process_cpu_clock_get
```
**Symbols:**

```
ffffffff8113a040-ffffffff8113a0d0: posix_cpu_clock_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int posix_cpu_clock_get(const clockid_t clock, struct timespec64 *tp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff81146e70)
Location: kernel/time/posix-cpu-timers.c:362
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:thread_cpu_clock_get
  - kernel/time/posix-cpu-timers.c:process_cpu_clock_get
```
**Symbols:**

```
ffffffff81146e70-ffffffff81146f00: posix_cpu_clock_get (STB_LOCAL)
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
<code>struct timespec *tp</code> ➡️ <code>struct timespec64 *tp</code>
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
<details>
<summary>Changed between <code>5.3</code> and <code>5.4</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const clockid_t clock</code>
</li>
<li>
<b>Param removed. </b>
<code>const clockid_t which_clock</code>
</li>
</ul>
</details>
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
