# Function: <code>kernel_waitid</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long int kernel_waitid(int which, pid_t upid, struct waitid_info *infop, int options, struct rusage *ru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810883c0)
Location: kernel/exit.c:1551
Inline: False
Direct callers:
  - kernel/exit.c:C_SYSC_waitid
  - kernel/exit.c:C_SYSC_waitid
  - kernel/exit.c:SYSC_waitid
  - kernel/exit.c:SYSC_waitid
```
**Symbols:**

```
ffffffff810883c0-ffffffff8108848d: kernel_waitid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long int kernel_waitid(int which, pid_t upid, struct waitid_info *infop, int options, struct rusage *ru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff8108f140)
Location: kernel/exit.c:1550
Inline: False
Direct callers:
  - kernel/exit.c:C_SYSC_waitid
  - kernel/exit.c:C_SYSC_waitid
  - kernel/exit.c:SYSC_waitid
  - kernel/exit.c:SYSC_waitid
```
**Symbols:**

```
ffffffff8108f140-ffffffff8108f20d: kernel_waitid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long int kernel_waitid(int which, pid_t upid, struct waitid_info *infop, int options, struct rusage *ru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff81092c50)
Location: kernel/exit.c:1550
Inline: False
Direct callers:
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_sys_waitid
  - kernel/exit.c:__do_sys_waitid
```
**Symbols:**

```
ffffffff81092c50-ffffffff81092d23: kernel_waitid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int kernel_waitid(int which, pid_t upid, struct waitid_info *infop, int options, struct rusage *ru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff8109af40)
Location: kernel/exit.c:1553
Inline: False
Direct callers:
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_sys_waitid
  - kernel/exit.c:__do_sys_waitid
```
**Symbols:**

```
ffffffff8109af40-ffffffff8109b014: kernel_waitid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long int kernel_waitid(int which, pid_t upid, struct waitid_info *infop, int options, struct rusage *ru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff8109f5a0)
Location: kernel/exit.c:1557
Inline: False
Direct callers:
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_sys_waitid
  - kernel/exit.c:__do_sys_waitid
```
**Symbols:**

```
ffffffff8109f5a0-ffffffff8109f674: kernel_waitid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int kernel_waitid(int which, pid_t upid, struct waitid_info *infop, int options, struct rusage *ru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810a5b30)
Location: kernel/exit.c:1490
Inline: False
Direct callers:
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_sys_waitid
  - kernel/exit.c:__do_sys_waitid
```
**Symbols:**

```
ffffffff810a5b30-ffffffff810a5cfb: kernel_waitid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int kernel_waitid(int which, pid_t upid, struct waitid_info *infop, int options, struct rusage *ru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810ad650)
Location: kernel/exit.c:1494
Inline: False
Direct callers:
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_sys_waitid
  - kernel/exit.c:__do_sys_waitid
```
**Symbols:**

```
ffffffff810ad650-ffffffff810ad88f: kernel_waitid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int kernel_waitid(int which, pid_t upid, struct waitid_info *infop, int options, struct rusage *ru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810a8d20)
Location: kernel/exit.c:1496
Inline: False
Direct callers:
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_sys_waitid
  - kernel/exit.c:__do_sys_waitid
```
**Symbols:**

```
ffffffff810a8d20-ffffffff810a8ee6: kernel_waitid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int kernel_waitid(int which, pid_t upid, struct waitid_info *infop, int options, struct rusage *ru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810a9df0)
Location: kernel/exit.c:1543
Inline: False
Direct callers:
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_sys_waitid
  - kernel/exit.c:__do_sys_waitid
```
**Symbols:**

```
ffffffff810a9df0-ffffffff810a9fb0: kernel_waitid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int kernel_waitid(int which, pid_t upid, struct waitid_info *infop, int options, struct rusage *ru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810bb930)
Location: kernel/exit.c:1543
Inline: False
Direct callers:
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_sys_waitid
  - kernel/exit.c:__do_sys_waitid
```
**Symbols:**

```
ffffffff810bb930-ffffffff810bbaf0: kernel_waitid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int kernel_waitid(int which, pid_t upid, struct waitid_info *infop, int options, struct rusage *ru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810d2390)
Location: kernel/exit.c:1547
Inline: False
Direct callers:
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_sys_waitid
  - kernel/exit.c:__do_sys_waitid
```
**Symbols:**

```
ffffffff810d2390-ffffffff810d25a4: kernel_waitid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int kernel_waitid(int which, pid_t upid, struct waitid_info *infop, int options, struct rusage *ru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810f0e10)
Location: kernel/exit.c:1641
Inline: False
Direct callers:
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_sys_waitid
  - kernel/exit.c:__do_sys_waitid
```
**Symbols:**

```
ffffffff810f0e10-ffffffff810f1024: kernel_waitid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int kernel_waitid(int which, pid_t upid, struct waitid_info *infop, int options, struct rusage *ru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810fcdc0)
Location: kernel/exit.c:1646
Inline: False
Direct callers:
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_sys_waitid
  - kernel/exit.c:__do_sys_waitid
```
**Symbols:**

```
ffffffff810fcdc0-ffffffff810fcfba: kernel_waitid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int kernel_waitid(int which, pid_t upid, struct waitid_info *infop, int options, struct rusage *ru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff81107440)
Location: kernel/exit.c:1697
Inline: False
Direct callers:
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_sys_waitid
  - kernel/exit.c:__do_sys_waitid
```
**Symbols:**

```
ffffffff81107440-ffffffff811074fb: kernel_waitid (STB_LOCAL)
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
long int kernel_waitid(int which, pid_t upid, struct waitid_info *infop, int options, struct rusage *ru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffff8000100fbbd8)
Location: kernel/exit.c:1490
Inline: False
Direct callers:
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_sys_waitid
  - kernel/exit.c:__do_sys_waitid
```
**Symbols:**

```
ffff8000100fbbd8-ffff8000100fbd68: kernel_waitid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long int kernel_waitid(int which, pid_t upid, struct waitid_info *infop, int options, struct rusage *ru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (c0359b90)
Location: kernel/exit.c:1490
Inline: False
Direct callers:
  - kernel/exit.c:__do_sys_waitid
  - kernel/exit.c:__do_sys_waitid
```
**Symbols:**

```
c0359b90-c0359d38: kernel_waitid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int kernel_waitid(int which, pid_t upid, struct waitid_info *infop, int options, struct rusage *ru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (c000000000143200)
Location: kernel/exit.c:1490
Inline: False
Direct callers:
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_sys_waitid
  - kernel/exit.c:__do_sys_waitid
```
**Symbols:**

```
c000000000143200-c000000000143490: kernel_waitid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long int kernel_waitid(int which, pid_t upid, struct waitid_info *infop, int options, struct rusage *ru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffe0000c5652)
Location: kernel/exit.c:1490
Inline: False
Direct callers:
  - kernel/exit.c:__do_sys_waitid
  - kernel/exit.c:__do_sys_waitid
```
**Symbols:**

```
ffffffe0000c5652-ffffffe0000c578e: kernel_waitid (STB_LOCAL)
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
long int kernel_waitid(int which, pid_t upid, struct waitid_info *infop, int options, struct rusage *ru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff8109f450)
Location: kernel/exit.c:1490
Inline: False
Direct callers:
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_sys_waitid
  - kernel/exit.c:__do_sys_waitid
```
**Symbols:**

```
ffffffff8109f450-ffffffff8109f61b: kernel_waitid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int kernel_waitid(int which, pid_t upid, struct waitid_info *infop, int options, struct rusage *ru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff8108de80)
Location: kernel/exit.c:1490
Inline: False
Direct callers:
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_sys_waitid
  - kernel/exit.c:__do_sys_waitid
```
**Symbols:**

```
ffffffff8108de80-ffffffff8108e04b: kernel_waitid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int kernel_waitid(int which, pid_t upid, struct waitid_info *infop, int options, struct rusage *ru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff8109f400)
Location: kernel/exit.c:1490
Inline: False
Direct callers:
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_sys_waitid
  - kernel/exit.c:__do_sys_waitid
```
**Symbols:**

```
ffffffff8109f400-ffffffff8109f5cb: kernel_waitid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int kernel_waitid(int which, pid_t upid, struct waitid_info *infop, int options, struct rusage *ru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810a7360)
Location: kernel/exit.c:1490
Inline: False
Direct callers:
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_sys_waitid
  - kernel/exit.c:__do_sys_waitid
```
**Symbols:**

```
ffffffff810a7360-ffffffff810a752b: kernel_waitid (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
