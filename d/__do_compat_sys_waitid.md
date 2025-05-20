# Function: <code>__do_compat_sys_waitid</code>

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
long int __do_compat_sys_waitid(int which, compat_pid_t pid, struct compat_siginfo *infop, int options, struct compat_rusage *uru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff81092ec0)
Location: kernel/exit.c:1715
Inline: False
Direct callers:
  - kernel/exit.c:__x32_compat_sys_waitid
  - kernel/exit.c:__ia32_compat_sys_waitid
```
**Symbols:**

```
ffffffff81092ec0-ffffffff81093015: __do_compat_sys_waitid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int __do_compat_sys_waitid(int which, compat_pid_t pid, struct compat_siginfo *infop, int options, struct compat_rusage *uru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff8109b190)
Location: kernel/exit.c:1717
Inline: False
Direct callers:
  - kernel/exit.c:__x32_compat_sys_waitid
  - kernel/exit.c:__ia32_compat_sys_waitid
```
**Symbols:**

```
ffffffff8109b190-ffffffff8109b2c7: __do_compat_sys_waitid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long int __do_compat_sys_waitid(int which, compat_pid_t pid, struct compat_siginfo *infop, int options, struct compat_rusage *uru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff8109f7f0)
Location: kernel/exit.c:1721
Inline: False
Direct callers:
  - kernel/exit.c:__x32_compat_sys_waitid
  - kernel/exit.c:__ia32_compat_sys_waitid
```
**Symbols:**

```
ffffffff8109f7f0-ffffffff8109f927: __do_compat_sys_waitid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int __do_compat_sys_waitid(int which, compat_pid_t pid, struct compat_siginfo *infop, int options, struct compat_rusage *uru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810a5e70)
Location: kernel/exit.c:1667
Inline: False
Direct callers:
  - kernel/exit.c:__x32_compat_sys_waitid
  - kernel/exit.c:__ia32_compat_sys_waitid
```
**Symbols:**

```
ffffffff810a5e70-ffffffff810a5fa7: __do_compat_sys_waitid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int __do_compat_sys_waitid(int which, compat_pid_t pid, struct compat_siginfo *infop, int options, struct compat_rusage *uru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810ada10)
Location: kernel/exit.c:1671
Inline: False
Direct callers:
  - kernel/exit.c:__x32_compat_sys_waitid
  - kernel/exit.c:__ia32_compat_sys_waitid
```
**Symbols:**

```
ffffffff810ada10-ffffffff810adb65: __do_compat_sys_waitid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int __do_compat_sys_waitid(int which, compat_pid_t pid, struct compat_siginfo *infop, int options, struct compat_rusage *uru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810a9090)
Location: kernel/exit.c:1696
Inline: False
Direct callers:
  - kernel/exit.c:__x32_compat_sys_waitid
  - kernel/exit.c:__ia32_compat_sys_waitid
```
**Symbols:**

```
ffffffff810a9090-ffffffff810a91f6: __do_compat_sys_waitid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int __do_compat_sys_waitid(int which, compat_pid_t pid, struct compat_siginfo *infop, int options, struct compat_rusage *uru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810aa110)
Location: kernel/exit.c:1743
Inline: False
Direct callers:
  - kernel/exit.c:__x32_compat_sys_waitid
  - kernel/exit.c:__ia32_compat_sys_waitid
```
**Symbols:**

```
ffffffff810aa110-ffffffff810aa241: __do_compat_sys_waitid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int __do_compat_sys_waitid(int which, compat_pid_t pid, struct compat_siginfo *infop, int options, struct compat_rusage *uru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810bbc50)
Location: kernel/exit.c:1743
Inline: False
Direct callers:
  - kernel/exit.c:__x64_compat_sys_waitid
  - kernel/exit.c:__ia32_compat_sys_waitid
```
**Symbols:**

```
ffffffff810bbc50-ffffffff810bbd81: __do_compat_sys_waitid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int __do_compat_sys_waitid(int which, compat_pid_t pid, struct compat_siginfo *infop, int options, struct compat_rusage *uru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810d2760)
Location: kernel/exit.c:1747
Inline: False
Direct callers:
  - kernel/exit.c:__ia32_compat_sys_waitid
```
**Symbols:**

```
ffffffff810d2760-ffffffff810d289d: __do_compat_sys_waitid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int __do_compat_sys_waitid(int which, compat_pid_t pid, struct compat_siginfo *infop, int options, struct compat_rusage *uru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810f1220)
Location: kernel/exit.c:1841
Inline: False
Direct callers:
  - kernel/exit.c:__ia32_compat_sys_waitid
```
**Symbols:**

```
ffffffff810f1220-ffffffff810f135d: __do_compat_sys_waitid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int __do_compat_sys_waitid(int which, compat_pid_t pid, struct compat_siginfo *infop, int options, struct compat_rusage *uru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810fd190)
Location: kernel/exit.c:1846
Inline: False
Direct callers:
  - kernel/exit.c:__ia32_compat_sys_waitid
```
**Symbols:**

```
ffffffff810fd190-ffffffff810fd2ae: __do_compat_sys_waitid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int __do_compat_sys_waitid(int which, compat_pid_t pid, struct compat_siginfo *infop, int options, struct compat_rusage *uru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff811076d0)
Location: kernel/exit.c:1849
Inline: False
Direct callers:
  - kernel/exit.c:__ia32_compat_sys_waitid
```
**Symbols:**

```
ffffffff811076d0-ffffffff811077ee: __do_compat_sys_waitid (STB_LOCAL)
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
long int __do_compat_sys_waitid(int which, compat_pid_t pid, struct compat_siginfo *infop, int options, struct compat_rusage *uru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffff8000100fc688)
Location: kernel/exit.c:1667
Inline: False
Direct callers:
  - kernel/exit.c:__arm64_compat_sys_waitid
```
**Symbols:**

```
ffff8000100fc688-ffff8000100fce9c: __do_compat_sys_waitid (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int __do_compat_sys_waitid(int which, compat_pid_t pid, struct compat_siginfo *infop, int options, struct compat_rusage *uru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (c000000000143880)
Location: kernel/exit.c:1667
Inline: False
Direct callers:
  - kernel/exit.c:__se_compat_sys_waitid
```
**Symbols:**

```
c000000000143880-c000000000143c4c: __do_compat_sys_waitid (STB_LOCAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
long int __do_compat_sys_waitid(int which, compat_pid_t pid, struct compat_siginfo *infop, int options, struct compat_rusage *uru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff8109f790)
Location: kernel/exit.c:1667
Inline: False
Direct callers:
  - kernel/exit.c:__x32_compat_sys_waitid
  - kernel/exit.c:__ia32_compat_sys_waitid
```
**Symbols:**

```
ffffffff8109f790-ffffffff8109f8c7: __do_compat_sys_waitid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int __do_compat_sys_waitid(int which, compat_pid_t pid, struct compat_siginfo *infop, int options, struct compat_rusage *uru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff8108e1c0)
Location: kernel/exit.c:1667
Inline: False
Direct callers:
  - kernel/exit.c:__x32_compat_sys_waitid
  - kernel/exit.c:__ia32_compat_sys_waitid
```
**Symbols:**

```
ffffffff8108e1c0-ffffffff8108e2f7: __do_compat_sys_waitid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int __do_compat_sys_waitid(int which, compat_pid_t pid, struct compat_siginfo *infop, int options, struct compat_rusage *uru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff8109f740)
Location: kernel/exit.c:1667
Inline: False
Direct callers:
  - kernel/exit.c:__x32_compat_sys_waitid
  - kernel/exit.c:__ia32_compat_sys_waitid
```
**Symbols:**

```
ffffffff8109f740-ffffffff8109f877: __do_compat_sys_waitid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int __do_compat_sys_waitid(int which, compat_pid_t pid, struct compat_siginfo *infop, int options, struct compat_rusage *uru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810a76a0)
Location: kernel/exit.c:1667
Inline: False
Direct callers:
  - kernel/exit.c:__x32_compat_sys_waitid
  - kernel/exit.c:__ia32_compat_sys_waitid
```
**Symbols:**

```
ffffffff810a76a0-ffffffff810a77d7: __do_compat_sys_waitid (STB_LOCAL)
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
