# Function: <code>sched_rr_get_interval</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int sched_rr_get_interval(pid_t pid, struct timespec *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b5370)
Location: kernel/sched/core.c:5101
Inline: False
Direct callers:
  - kernel/sched/core.c:compat_SyS_sched_rr_get_interval
  - kernel/sched/core.c:SyS_sched_rr_get_interval
```
**Symbols:**

```
ffffffff810b5370-ffffffff810b5484: sched_rr_get_interval (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int sched_rr_get_interval(pid_t pid, struct timespec64 *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810bcd60)
Location: kernel/sched/core.c:5226
Inline: False
Direct callers:
  - kernel/sched/core.c:__x32_compat_sys_sched_rr_get_interval
  - kernel/sched/core.c:__ia32_compat_sys_sched_rr_get_interval
  - kernel/sched/core.c:__ia32_sys_sched_rr_get_interval
  - kernel/sched/core.c:__x64_sys_sched_rr_get_interval
```
**Symbols:**

```
ffffffff810bcd60-ffffffff810bce6f: sched_rr_get_interval (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int sched_rr_get_interval(pid_t pid, struct timespec64 *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810c5f80)
Location: kernel/sched/core.c:5209
Inline: False
Direct callers:
  - kernel/sched/core.c:__x32_compat_sys_sched_rr_get_interval
  - kernel/sched/core.c:__ia32_compat_sys_sched_rr_get_interval
  - kernel/sched/core.c:__ia32_sys_sched_rr_get_interval
  - kernel/sched/core.c:__x64_sys_sched_rr_get_interval
```
**Symbols:**

```
ffffffff810c5f80-ffffffff810c608f: sched_rr_get_interval (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int sched_rr_get_interval(pid_t pid, struct timespec64 *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810cbb80)
Location: kernel/sched/core.c:5662
Inline: False
Direct callers:
  - kernel/sched/core.c:__ia32_sys_sched_rr_get_interval_time32
  - kernel/sched/core.c:__x64_sys_sched_rr_get_interval_time32
  - kernel/sched/core.c:__ia32_sys_sched_rr_get_interval
  - kernel/sched/core.c:__x64_sys_sched_rr_get_interval
```
**Symbols:**

```
ffffffff810cbb80-ffffffff810cbc95: sched_rr_get_interval (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int sched_rr_get_interval(pid_t pid, struct timespec64 *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d56e0)
Location: kernel/sched/core.c:5853
Inline: False
Direct callers:
  - kernel/sched/core.c:__ia32_sys_sched_rr_get_interval_time32
  - kernel/sched/core.c:__x64_sys_sched_rr_get_interval_time32
  - kernel/sched/core.c:__ia32_sys_sched_rr_get_interval
  - kernel/sched/core.c:__x64_sys_sched_rr_get_interval
```
**Symbols:**

```
ffffffff810d56e0-ffffffff810d57f5: sched_rr_get_interval (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int sched_rr_get_interval(pid_t pid, struct timespec64 *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810dfcb0)
Location: kernel/sched/core.c:6086
Inline: False
Direct callers:
  - kernel/sched/core.c:__ia32_sys_sched_rr_get_interval_time32
  - kernel/sched/core.c:__x64_sys_sched_rr_get_interval_time32
  - kernel/sched/core.c:__ia32_sys_sched_rr_get_interval
  - kernel/sched/core.c:__x64_sys_sched_rr_get_interval
```
**Symbols:**

```
ffffffff810dfcb0-ffffffff810dfdc5: sched_rr_get_interval (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int sched_rr_get_interval(pid_t pid, struct timespec64 *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810dcfa0)
Location: kernel/sched/core.c:6906
Inline: False
Direct callers:
  - kernel/sched/core.c:__ia32_sys_sched_rr_get_interval_time32
  - kernel/sched/core.c:__x64_sys_sched_rr_get_interval_time32
  - kernel/sched/core.c:__ia32_sys_sched_rr_get_interval
  - kernel/sched/core.c:__x64_sys_sched_rr_get_interval
```
**Symbols:**

```
ffffffff810dcfa0-ffffffff810dd0c2: sched_rr_get_interval (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int sched_rr_get_interval(pid_t pid, struct timespec64 *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810deb70)
Location: kernel/sched/core.c:7257
Inline: False
Direct callers:
  - kernel/sched/core.c:__ia32_sys_sched_rr_get_interval_time32
  - kernel/sched/core.c:__x64_sys_sched_rr_get_interval_time32
  - kernel/sched/core.c:__ia32_sys_sched_rr_get_interval
  - kernel/sched/core.c:__x64_sys_sched_rr_get_interval
```
**Symbols:**

```
ffffffff810deb70-ffffffff810dec92: sched_rr_get_interval (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int sched_rr_get_interval(pid_t pid, struct timespec64 *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810f3aa0)
Location: kernel/sched/core.c:8455
Inline: False
Direct callers:
  - kernel/sched/core.c:__ia32_sys_sched_rr_get_interval_time32
  - kernel/sched/core.c:__x64_sys_sched_rr_get_interval_time32
  - kernel/sched/core.c:__ia32_sys_sched_rr_get_interval
  - kernel/sched/core.c:__x64_sys_sched_rr_get_interval
```
**Symbols:**

```
ffffffff810f3aa0-ffffffff810f3bc0: sched_rr_get_interval (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int sched_rr_get_interval(pid_t pid, struct timespec64 *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff8110fb20)
Location: kernel/sched/core.c:8746
Inline: False
Direct callers:
  - kernel/sched/core.c:__ia32_sys_sched_rr_get_interval_time32
  - kernel/sched/core.c:__x64_sys_sched_rr_get_interval_time32
  - kernel/sched/core.c:__ia32_sys_sched_rr_get_interval
  - kernel/sched/core.c:__x64_sys_sched_rr_get_interval
```
**Symbols:**

```
ffffffff8110fb20-ffffffff8110fc50: sched_rr_get_interval (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int sched_rr_get_interval(pid_t pid, struct timespec64 *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff811369d0)
Location: kernel/sched/core.c:8930
Inline: False
Direct callers:
  - kernel/sched/core.c:__ia32_sys_sched_rr_get_interval_time32
  - kernel/sched/core.c:__x64_sys_sched_rr_get_interval_time32
  - kernel/sched/core.c:__ia32_sys_sched_rr_get_interval
  - kernel/sched/core.c:__x64_sys_sched_rr_get_interval
```
**Symbols:**

```
ffffffff811369d0-ffffffff81136b00: sched_rr_get_interval (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int sched_rr_get_interval(pid_t pid, struct timespec64 *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81145a10)
Location: kernel/sched/core.c:9087
Inline: False
Direct callers:
  - kernel/sched/core.c:__ia32_sys_sched_rr_get_interval_time32
  - kernel/sched/core.c:__x64_sys_sched_rr_get_interval_time32
  - kernel/sched/core.c:__ia32_sys_sched_rr_get_interval
  - kernel/sched/core.c:__x64_sys_sched_rr_get_interval
```
**Symbols:**

```
ffffffff81145a10-ffffffff81145b56: sched_rr_get_interval (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (ffffffff811514a7)
Location: kernel/sched/core.c:9082
Inline: True
Inline callers:
  - kernel/sched/core.c:__ia32_sys_sched_rr_get_interval_time32
  - kernel/sched/core.c:__x64_sys_sched_rr_get_interval_time32
  - kernel/sched/core.c:__ia32_sys_sched_rr_get_interval
  - kernel/sched/core.c:__x64_sys_sched_rr_get_interval
Direct callers:
  - kernel/sched/core.c:__ia32_sys_sched_rr_get_interval_time32
  - kernel/sched/core.c:__x64_sys_sched_rr_get_interval_time32
  - kernel/sched/core.c:__ia32_sys_sched_rr_get_interval
  - kernel/sched/core.c:__x64_sys_sched_rr_get_interval
```
**Symbols:**

```
ffffffff81151310-ffffffff81151456: sched_rr_get_interval.part.0 (STB_LOCAL)
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
int sched_rr_get_interval(pid_t pid, struct timespec64 *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffff800010136220)
Location: kernel/sched/core.c:5853
Inline: False
Direct callers:
  - kernel/sched/core.c:__arm64_sys_sched_rr_get_interval_time32
  - kernel/sched/core.c:__arm64_sys_sched_rr_get_interval
```
**Symbols:**

```
ffff800010136220-ffff800010136334: sched_rr_get_interval (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int sched_rr_get_interval(pid_t pid, struct timespec64 *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c038516c)
Location: kernel/sched/core.c:5853
Inline: False
Direct callers:
  - kernel/sched/core.c:__se_sys_sched_rr_get_interval_time32
  - kernel/sched/core.c:__se_sys_sched_rr_get_interval
```
**Symbols:**

```
c038516c-c0385288: sched_rr_get_interval (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int sched_rr_get_interval(pid_t pid, struct timespec64 *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c000000000181330)
Location: kernel/sched/core.c:5853
Inline: False
Direct callers:
  - kernel/sched/core.c:__se_sys_sched_rr_get_interval_time32
  - kernel/sched/core.c:__se_sys_sched_rr_get_interval
```
**Symbols:**

```
c000000000181330-c0000000001814e8: sched_rr_get_interval (STB_LOCAL)
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
In kernel/sched/core.c (ffffffe0000ec224)
Location: kernel/sched/core.c:5853
Inline: True
Inline callers:
  - kernel/sched/core.c:__se_sys_sched_rr_get_interval
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
int sched_rr_get_interval(pid_t pid, struct timespec64 *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810cf9e0)
Location: kernel/sched/core.c:5853
Inline: False
Direct callers:
  - kernel/sched/core.c:__ia32_sys_sched_rr_get_interval_time32
  - kernel/sched/core.c:__x64_sys_sched_rr_get_interval_time32
  - kernel/sched/core.c:__ia32_sys_sched_rr_get_interval
  - kernel/sched/core.c:__x64_sys_sched_rr_get_interval
```
**Symbols:**

```
ffffffff810cf9e0-ffffffff810cfaf5: sched_rr_get_interval (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int sched_rr_get_interval(pid_t pid, struct timespec64 *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810be2a0)
Location: kernel/sched/core.c:5853
Inline: False
Direct callers:
  - kernel/sched/core.c:__ia32_sys_sched_rr_get_interval_time32
  - kernel/sched/core.c:__x64_sys_sched_rr_get_interval_time32
  - kernel/sched/core.c:__ia32_sys_sched_rr_get_interval
  - kernel/sched/core.c:__x64_sys_sched_rr_get_interval
```
**Symbols:**

```
ffffffff810be2a0-ffffffff810be3b5: sched_rr_get_interval (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int sched_rr_get_interval(pid_t pid, struct timespec64 *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810ce570)
Location: kernel/sched/core.c:5853
Inline: False
Direct callers:
  - kernel/sched/core.c:__ia32_sys_sched_rr_get_interval_time32
  - kernel/sched/core.c:__x64_sys_sched_rr_get_interval_time32
  - kernel/sched/core.c:__ia32_sys_sched_rr_get_interval
  - kernel/sched/core.c:__x64_sys_sched_rr_get_interval
```
**Symbols:**

```
ffffffff810ce570-ffffffff810ce685: sched_rr_get_interval (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int sched_rr_get_interval(pid_t pid, struct timespec64 *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d7540)
Location: kernel/sched/core.c:5853
Inline: False
Direct callers:
  - kernel/sched/core.c:__ia32_sys_sched_rr_get_interval_time32
  - kernel/sched/core.c:__x64_sys_sched_rr_get_interval_time32
  - kernel/sched/core.c:__ia32_sys_sched_rr_get_interval
  - kernel/sched/core.c:__x64_sys_sched_rr_get_interval
```
**Symbols:**

```
ffffffff810d7540-ffffffff810d7669: sched_rr_get_interval (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct timespec *t</code> ➡️ <code>struct timespec64 *t</code>
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
