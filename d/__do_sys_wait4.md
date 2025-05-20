# Function: <code>__do_sys_wait4</code>

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
In <code>4.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long int __do_sys_wait4(pid_t upid, int *stat_addr, int options, struct rusage *ru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810940a0)
Location: kernel/exit.c:1673
Inline: False
Direct callers:
  - kernel/exit.c:__ia32_sys_wait4
  - kernel/exit.c:__x64_sys_wait4
```
**Symbols:**

```
ffffffff810940a0-ffffffff8109412d: __do_sys_wait4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int __do_sys_wait4(pid_t upid, int *stat_addr, int options, struct rusage *ru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff8109c440)
Location: kernel/exit.c:1675
Inline: False
Direct callers:
  - kernel/exit.c:__ia32_sys_wait4
  - kernel/exit.c:__x64_sys_wait4
```
**Symbols:**

```
ffffffff8109c440-ffffffff8109c4cd: __do_sys_wait4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long int __do_sys_wait4(pid_t upid, int *stat_addr, int options, struct rusage *ru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810a0a60)
Location: kernel/exit.c:1679
Inline: False
Direct callers:
  - kernel/exit.c:__ia32_sys_wait4
  - kernel/exit.c:__x64_sys_wait4
```
**Symbols:**

```
ffffffff810a0a60-ffffffff810a0aef: __do_sys_wait4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int __do_sys_wait4(pid_t upid, int *stat_addr, int options, struct rusage *ru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810a7040)
Location: kernel/exit.c:1625
Inline: False
Direct callers:
  - kernel/exit.c:__ia32_sys_wait4
  - kernel/exit.c:__x64_sys_wait4
```
**Symbols:**

```
ffffffff810a7040-ffffffff810a70cf: __do_sys_wait4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int __do_sys_wait4(pid_t upid, int *stat_addr, int options, struct rusage *ru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810ae790)
Location: kernel/exit.c:1629
Inline: False
Direct callers:
  - kernel/exit.c:__ia32_sys_wait4
  - kernel/exit.c:__x64_sys_wait4
```
**Symbols:**

```
ffffffff810ae790-ffffffff810ae81e: __do_sys_wait4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int __do_sys_wait4(pid_t upid, int *stat_addr, int options, struct rusage *ru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810a9de0)
Location: kernel/exit.c:1654
Inline: False
Direct callers:
  - kernel/exit.c:__ia32_sys_wait4
  - kernel/exit.c:__x64_sys_wait4
```
**Symbols:**

```
ffffffff810a9de0-ffffffff810a9e6e: __do_sys_wait4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int __do_sys_wait4(pid_t upid, int *stat_addr, int options, struct rusage *ru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810aae10)
Location: kernel/exit.c:1701
Inline: False
Direct callers:
  - kernel/exit.c:__ia32_sys_wait4
  - kernel/exit.c:__x64_sys_wait4
```
**Symbols:**

```
ffffffff810aae10-ffffffff810aae9f: __do_sys_wait4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int __do_sys_wait4(pid_t upid, int *stat_addr, int options, struct rusage *ru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810bc930)
Location: kernel/exit.c:1701
Inline: False
Direct callers:
  - kernel/exit.c:__ia32_sys_wait4
  - kernel/exit.c:__x64_sys_wait4
```
**Symbols:**

```
ffffffff810bc930-ffffffff810bc9bf: __do_sys_wait4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int __do_sys_wait4(pid_t upid, int *stat_addr, int options, struct rusage *ru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810d36e0)
Location: kernel/exit.c:1705
Inline: False
Direct callers:
  - kernel/exit.c:__ia32_sys_wait4
  - kernel/exit.c:__x64_sys_wait4
```
**Symbols:**

```
ffffffff810d36e0-ffffffff810d3797: __do_sys_wait4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int __do_sys_wait4(pid_t upid, int *stat_addr, int options, struct rusage *ru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810f2390)
Location: kernel/exit.c:1799
Inline: False
Direct callers:
  - kernel/exit.c:__ia32_sys_wait4
  - kernel/exit.c:__x64_sys_wait4
```
**Symbols:**

```
ffffffff810f2390-ffffffff810f2447: __do_sys_wait4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int __do_sys_wait4(pid_t upid, int *stat_addr, int options, struct rusage *ru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810fe310)
Location: kernel/exit.c:1804
Inline: False
Direct callers:
  - kernel/exit.c:__ia32_sys_wait4
  - kernel/exit.c:__x64_sys_wait4
```
**Symbols:**

```
ffffffff810fe310-ffffffff810fe3c7: __do_sys_wait4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int __do_sys_wait4(pid_t upid, int *stat_addr, int options, struct rusage *ru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff811079c0)
Location: kernel/exit.c:1807
Inline: False
Direct callers:
  - kernel/exit.c:__ia32_sys_wait4
  - kernel/exit.c:__x64_sys_wait4
```
**Symbols:**

```
ffffffff811079c0-ffffffff81107a77: __do_sys_wait4 (STB_LOCAL)
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
long int __do_sys_wait4(pid_t upid, int *stat_addr, int options, struct rusage *ru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffff8000100fe038)
Location: kernel/exit.c:1625
Inline: False
Direct callers:
  - kernel/exit.c:__arm64_sys_wait4
```
**Symbols:**

```
ffff8000100fe038-ffff8000100fe1f0: __do_sys_wait4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/exit.c (c035b1f8)
Location: kernel/exit.c:1625
Inline: True
Inline callers:
  - kernel/exit.c:__se_sys_wait4
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int __do_sys_wait4(pid_t upid, int *stat_addr, int options, struct rusage *ru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (c000000000145160)
Location: kernel/exit.c:1625
Inline: False
Direct callers:
  - kernel/exit.c:__se_sys_wait4
```
**Symbols:**

```
c000000000145160-c000000000145214: __do_sys_wait4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long int __do_sys_wait4(pid_t upid, int *stat_addr, int options, struct rusage *ru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffe0000c668e)
Location: kernel/exit.c:1625
Inline: False
Direct callers:
  - kernel/exit.c:__se_sys_wait4
```
**Symbols:**

```
ffffffe0000c668e-ffffffe0000c66ee: __do_sys_wait4 (STB_LOCAL)
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
long int __do_sys_wait4(pid_t upid, int *stat_addr, int options, struct rusage *ru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810a0960)
Location: kernel/exit.c:1625
Inline: False
Direct callers:
  - kernel/exit.c:__ia32_sys_wait4
  - kernel/exit.c:__x64_sys_wait4
```
**Symbols:**

```
ffffffff810a0960-ffffffff810a09ef: __do_sys_wait4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int __do_sys_wait4(pid_t upid, int *stat_addr, int options, struct rusage *ru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff8108f380)
Location: kernel/exit.c:1625
Inline: False
Direct callers:
  - kernel/exit.c:__ia32_sys_wait4
  - kernel/exit.c:__x64_sys_wait4
```
**Symbols:**

```
ffffffff8108f380-ffffffff8108f40f: __do_sys_wait4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int __do_sys_wait4(pid_t upid, int *stat_addr, int options, struct rusage *ru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810a0910)
Location: kernel/exit.c:1625
Inline: False
Direct callers:
  - kernel/exit.c:__ia32_sys_wait4
  - kernel/exit.c:__x64_sys_wait4
```
**Symbols:**

```
ffffffff810a0910-ffffffff810a099f: __do_sys_wait4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int __do_sys_wait4(pid_t upid, int *stat_addr, int options, struct rusage *ru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810a8890)
Location: kernel/exit.c:1625
Inline: False
Direct callers:
  - kernel/exit.c:__ia32_sys_wait4
  - kernel/exit.c:__x64_sys_wait4
```
**Symbols:**

```
ffffffff810a8890-ffffffff810a891f: __do_sys_wait4 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
