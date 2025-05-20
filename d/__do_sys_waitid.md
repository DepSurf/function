# Function: <code>__do_sys_waitid</code>

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
long int __do_sys_waitid(int which, pid_t upid, struct siginfo *infop, int options, struct rusage *ru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff81092d30)
Location: kernel/exit.c:1596
Inline: False
Direct callers:
  - kernel/exit.c:__ia32_sys_waitid
  - kernel/exit.c:__x64_sys_waitid
```
**Symbols:**

```
ffffffff81092d30-ffffffff81092e58: __do_sys_waitid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int __do_sys_waitid(int which, pid_t upid, struct siginfo *infop, int options, struct rusage *ru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff8109b020)
Location: kernel/exit.c:1599
Inline: False
Direct callers:
  - kernel/exit.c:__ia32_sys_waitid
  - kernel/exit.c:__x64_sys_waitid
```
**Symbols:**

```
ffffffff8109b020-ffffffff8109b12d: __do_sys_waitid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long int __do_sys_waitid(int which, pid_t upid, struct siginfo *infop, int options, struct rusage *ru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff8109f680)
Location: kernel/exit.c:1603
Inline: False
Direct callers:
  - kernel/exit.c:__ia32_sys_waitid
  - kernel/exit.c:__x64_sys_waitid
```
**Symbols:**

```
ffffffff8109f680-ffffffff8109f78d: __do_sys_waitid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int __do_sys_waitid(int which, pid_t upid, struct siginfo *infop, int options, struct rusage *ru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810a5d00)
Location: kernel/exit.c:1549
Inline: False
Direct callers:
  - kernel/exit.c:__ia32_sys_waitid
  - kernel/exit.c:__x64_sys_waitid
```
**Symbols:**

```
ffffffff810a5d00-ffffffff810a5e0d: __do_sys_waitid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int __do_sys_waitid(int which, pid_t upid, struct siginfo *infop, int options, struct rusage *ru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810ad890)
Location: kernel/exit.c:1553
Inline: False
Direct callers:
  - kernel/exit.c:__ia32_sys_waitid
  - kernel/exit.c:__x64_sys_waitid
```
**Symbols:**

```
ffffffff810ad890-ffffffff810ad9ae: __do_sys_waitid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int __do_sys_waitid(int which, pid_t upid, struct siginfo *infop, int options, struct rusage *ru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810a8ef0)
Location: kernel/exit.c:1562
Inline: False
Direct callers:
  - kernel/exit.c:__ia32_sys_waitid
  - kernel/exit.c:__x64_sys_waitid
```
**Symbols:**

```
ffffffff810a8ef0-ffffffff810a9025: __do_sys_waitid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int __do_sys_waitid(int which, pid_t upid, struct siginfo *infop, int options, struct rusage *ru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810a9fb0)
Location: kernel/exit.c:1609
Inline: False
Direct callers:
  - kernel/exit.c:__ia32_sys_waitid
  - kernel/exit.c:__x64_sys_waitid
```
**Symbols:**

```
ffffffff810a9fb0-ffffffff810aa0b7: __do_sys_waitid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int __do_sys_waitid(int which, pid_t upid, struct siginfo *infop, int options, struct rusage *ru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810bbaf0)
Location: kernel/exit.c:1609
Inline: False
Direct callers:
  - kernel/exit.c:__ia32_sys_waitid
  - kernel/exit.c:__x64_sys_waitid
```
**Symbols:**

```
ffffffff810bbaf0-ffffffff810bbbf7: __do_sys_waitid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int __do_sys_waitid(int which, pid_t upid, struct siginfo *infop, int options, struct rusage *ru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810d25b0)
Location: kernel/exit.c:1613
Inline: False
Direct callers:
  - kernel/exit.c:__ia32_sys_waitid
  - kernel/exit.c:__x64_sys_waitid
```
**Symbols:**

```
ffffffff810d25b0-ffffffff810d26f3: __do_sys_waitid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int __do_sys_waitid(int which, pid_t upid, struct siginfo *infop, int options, struct rusage *ru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810f1040)
Location: kernel/exit.c:1707
Inline: False
Direct callers:
  - kernel/exit.c:__ia32_sys_waitid
  - kernel/exit.c:__x64_sys_waitid
```
**Symbols:**

```
ffffffff810f1040-ffffffff810f1183: __do_sys_waitid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int __do_sys_waitid(int which, pid_t upid, struct siginfo *infop, int options, struct rusage *ru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810fcfd0)
Location: kernel/exit.c:1712
Inline: False
Direct callers:
  - kernel/exit.c:__ia32_sys_waitid
  - kernel/exit.c:__x64_sys_waitid
```
**Symbols:**

```
ffffffff810fcfd0-ffffffff810fd0f7: __do_sys_waitid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int __do_sys_waitid(int which, pid_t upid, struct siginfo *infop, int options, struct rusage *ru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff81107510)
Location: kernel/exit.c:1715
Inline: False
Direct callers:
  - kernel/exit.c:__ia32_sys_waitid
  - kernel/exit.c:__x64_sys_waitid
```
**Symbols:**

```
ffffffff81107510-ffffffff81107637: __do_sys_waitid (STB_LOCAL)
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
long int __do_sys_waitid(int which, pid_t upid, struct siginfo *infop, int options, struct rusage *ru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffff8000100fbd68)
Location: kernel/exit.c:1549
Inline: False
Direct callers:
  - kernel/exit.c:__arm64_sys_waitid
```
**Symbols:**

```
ffff8000100fbd68-ffff8000100fc644: __do_sys_waitid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long int __do_sys_waitid(int which, pid_t upid, struct siginfo *infop, int options, struct rusage *ru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (c0359d38)
Location: kernel/exit.c:1549
Inline: False
Direct callers:
  - kernel/exit.c:__se_sys_waitid
```
**Symbols:**

```
c0359d38-c0359ff0: __do_sys_waitid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int __do_sys_waitid(int which, pid_t upid, struct siginfo *infop, int options, struct rusage *ru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (c000000000143490)
Location: kernel/exit.c:1549
Inline: False
Direct callers:
  - kernel/exit.c:__se_sys_waitid
```
**Symbols:**

```
c000000000143490-c00000000014385c: __do_sys_waitid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long int __do_sys_waitid(int which, pid_t upid, struct siginfo *infop, int options, struct rusage *ru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffe0000c578e)
Location: kernel/exit.c:1549
Inline: False
Direct callers:
  - kernel/exit.c:__se_sys_waitid
```
**Symbols:**

```
ffffffe0000c578e-ffffffe0000c587c: __do_sys_waitid (STB_LOCAL)
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
long int __do_sys_waitid(int which, pid_t upid, struct siginfo *infop, int options, struct rusage *ru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff8109f620)
Location: kernel/exit.c:1549
Inline: False
Direct callers:
  - kernel/exit.c:__ia32_sys_waitid
  - kernel/exit.c:__x64_sys_waitid
```
**Symbols:**

```
ffffffff8109f620-ffffffff8109f72d: __do_sys_waitid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int __do_sys_waitid(int which, pid_t upid, struct siginfo *infop, int options, struct rusage *ru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff8108e050)
Location: kernel/exit.c:1549
Inline: False
Direct callers:
  - kernel/exit.c:__ia32_sys_waitid
  - kernel/exit.c:__x64_sys_waitid
```
**Symbols:**

```
ffffffff8108e050-ffffffff8108e15d: __do_sys_waitid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int __do_sys_waitid(int which, pid_t upid, struct siginfo *infop, int options, struct rusage *ru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff8109f5d0)
Location: kernel/exit.c:1549
Inline: False
Direct callers:
  - kernel/exit.c:__ia32_sys_waitid
  - kernel/exit.c:__x64_sys_waitid
```
**Symbols:**

```
ffffffff8109f5d0-ffffffff8109f6dd: __do_sys_waitid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int __do_sys_waitid(int which, pid_t upid, struct siginfo *infop, int options, struct rusage *ru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810a7530)
Location: kernel/exit.c:1549
Inline: False
Direct callers:
  - kernel/exit.c:__ia32_sys_waitid
  - kernel/exit.c:__x64_sys_waitid
```
**Symbols:**

```
ffffffff810a7530-ffffffff810a763d: __do_sys_waitid (STB_LOCAL)
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
