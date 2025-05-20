# Function: <code>jiffies_to_timespec64</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void jiffies_to_timespec64(const long unsigned int jiffies, struct timespec *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff810eada0)
Location: kernel/time/time.c:575
Inline: False
Direct callers:
  - kernel/sched/core.c:SyS_sched_rr_get_interval
  - kernel/time/itimer.c:set_cpu_itimer
  - kernel/time/itimer.c:set_cpu_itimer
  - kernel/time/posix-cpu-timers.c:sample_to_timespec
  - drivers/ata/libata-transport.c:ata_show_ering
```
**Symbols:**

```
ffffffff810eada0-ffffffff810eaddb: jiffies_to_timespec64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void jiffies_to_timespec64(const long unsigned int jiffies, struct timespec *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff810f1a40)
Location: kernel/time/time.c:582
Inline: False
Direct callers:
  - kernel/sched/core.c:SyS_sched_rr_get_interval
  - kernel/time/itimer.c:set_cpu_itimer
  - kernel/time/itimer.c:set_cpu_itimer
  - kernel/time/posix-cpu-timers.c:sample_to_timespec
```
**Symbols:**

```
ffffffff810f1a40-ffffffff810f1a7e: jiffies_to_timespec64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void jiffies_to_timespec64(const long unsigned int jiffies, struct timespec *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff810f8bc0)
Location: kernel/time/time.c:582
Inline: False
Direct callers:
  - kernel/sched/core.c:SyS_sched_rr_get_interval
  - kernel/time/posix-cpu-timers.c:sample_to_timespec
  - kernel/time/itimer.c:set_cpu_itimer
  - kernel/time/itimer.c:set_cpu_itimer
```
**Symbols:**

```
ffffffff810f8bc0-ffffffff810f8bfe: jiffies_to_timespec64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void jiffies_to_timespec64(const long unsigned int jiffies, struct timespec *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff810fabe0)
Location: kernel/time/time.c:672
Inline: False
Direct callers:
  - kernel/sched/core.c:SyS_sched_rr_get_interval
```
**Symbols:**

```
ffffffff810fabe0-ffffffff810fac1e: jiffies_to_timespec64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void jiffies_to_timespec64(const long unsigned int jiffies, struct timespec *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81105570)
Location: kernel/time/time.c:639
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_rr_get_interval
```
**Symbols:**

```
ffffffff81105570-ffffffff811055ae: jiffies_to_timespec64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void jiffies_to_timespec64(const long unsigned int jiffies, struct timespec64 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff811103d0)
Location: kernel/time/time.c:651
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_rr_get_interval
```
**Symbols:**

```
ffffffff811103d0-ffffffff8111040e: jiffies_to_timespec64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void jiffies_to_timespec64(const long unsigned int jiffies, struct timespec64 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff8111b9c0)
Location: kernel/time/time.c:589
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_rr_get_interval
```
**Symbols:**

```
ffffffff8111b9c0-ffffffff8111b9fe: jiffies_to_timespec64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void jiffies_to_timespec64(const long unsigned int jiffies, struct timespec64 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff811263e0)
Location: kernel/time/time.c:657
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_rr_get_interval
```
**Symbols:**

```
ffffffff811263e0-ffffffff8112641e: jiffies_to_timespec64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void jiffies_to_timespec64(const long unsigned int jiffies, struct timespec64 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81132380)
Location: kernel/time/time.c:657
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_rr_get_interval
```
**Symbols:**

```
ffffffff81132380-ffffffff811323be: jiffies_to_timespec64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void jiffies_to_timespec64(const long unsigned int jiffies, struct timespec64 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff811417e0)
Location: kernel/time/time.c:605
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_rr_get_interval
```
**Symbols:**

```
ffffffff811417e0-ffffffff8114181e: jiffies_to_timespec64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void jiffies_to_timespec64(const long unsigned int jiffies, struct timespec64 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff8113d9f0)
Location: kernel/time/time.c:605
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_rr_get_interval
```
**Symbols:**

```
ffffffff8113d9f0-ffffffff8113da2e: jiffies_to_timespec64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void jiffies_to_timespec64(const long unsigned int jiffies, struct timespec64 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff8113ec40)
Location: kernel/time/time.c:605
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_rr_get_interval
```
**Symbols:**

```
ffffffff8113ec40-ffffffff8113ec7e: jiffies_to_timespec64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void jiffies_to_timespec64(const long unsigned int jiffies, struct timespec64 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff811620d0)
Location: kernel/time/time.c:605
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_rr_get_interval
```
**Symbols:**

```
ffffffff811620d0-ffffffff8116210e: jiffies_to_timespec64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void jiffies_to_timespec64(const long unsigned int jiffies, struct timespec64 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81195030)
Location: kernel/time/time.c:605
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_rr_get_interval
```
**Symbols:**

```
ffffffff81195030-ffffffff81195079: jiffies_to_timespec64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void jiffies_to_timespec64(const long unsigned int jiffies, struct timespec64 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff811d2dc0)
Location: kernel/time/time.c:605
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_rr_get_interval
```
**Symbols:**

```
ffffffff811d2dc0-ffffffff811d2e09: jiffies_to_timespec64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void jiffies_to_timespec64(const long unsigned int jiffies, struct timespec64 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff811e70b0)
Location: kernel/time/time.c:605
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_rr_get_interval
```
**Symbols:**

```
ffffffff811e70b0-ffffffff811e70f9: jiffies_to_timespec64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void jiffies_to_timespec64(const long unsigned int jiffies, struct timespec64 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff811fce00)
Location: kernel/time/time.c:639
Inline: False
```
**Symbols:**

```
ffffffff811fce00-ffffffff811fce49: jiffies_to_timespec64 (STB_GLOBAL)
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
void jiffies_to_timespec64(const long unsigned int jiffies, struct timespec64 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffff800010199df8)
Location: kernel/time/time.c:657
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_rr_get_interval
```
**Symbols:**

```
ffff800010199df8-ffff800010199e5c: jiffies_to_timespec64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void jiffies_to_timespec64(const long unsigned int jiffies, struct timespec64 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (c03e54c0)
Location: kernel/time/time.c:657
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_rr_get_interval
```
**Symbols:**

```
c03e54c0-c03e5548: jiffies_to_timespec64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void jiffies_to_timespec64(const long unsigned int jiffies, struct timespec64 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (c0000000001fa0b0)
Location: kernel/time/time.c:657
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_rr_get_interval
```
**Symbols:**

```
c0000000001fa0b0-c0000000001fa100: jiffies_to_timespec64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void jiffies_to_timespec64(const long unsigned int jiffies, struct timespec64 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffe00012a2e6)
Location: kernel/time/time.c:657
Inline: False
Direct callers:
  - kernel/sched/core.c:__se_sys_sched_rr_get_interval
```
**Symbols:**

```
ffffffe00012a2e6-ffffffe00012a330: jiffies_to_timespec64 (STB_GLOBAL)
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
void jiffies_to_timespec64(const long unsigned int jiffies, struct timespec64 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff8112ab30)
Location: kernel/time/time.c:657
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_rr_get_interval
```
**Symbols:**

```
ffffffff8112ab30-ffffffff8112ab6e: jiffies_to_timespec64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void jiffies_to_timespec64(const long unsigned int jiffies, struct timespec64 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff8111d3a0)
Location: kernel/time/time.c:657
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_rr_get_interval
```
**Symbols:**

```
ffffffff8111d3a0-ffffffff8111d3de: jiffies_to_timespec64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void jiffies_to_timespec64(const long unsigned int jiffies, struct timespec64 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81128850)
Location: kernel/time/time.c:657
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_rr_get_interval
```
**Symbols:**

```
ffffffff81128850-ffffffff8112888e: jiffies_to_timespec64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void jiffies_to_timespec64(const long unsigned int jiffies, struct timespec64 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81134ed0)
Location: kernel/time/time.c:657
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_rr_get_interval
```
**Symbols:**

```
ffffffff81134ed0-ffffffff81134f0e: jiffies_to_timespec64 (STB_GLOBAL)
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
<code>struct timespec *value</code> ➡️ <code>struct timespec64 *value</code>
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
