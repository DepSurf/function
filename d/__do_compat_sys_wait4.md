# Function: <code>__do_compat_sys_wait4</code>

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
long int __do_compat_sys_wait4(compat_pid_t pid, compat_uint_t *stat_addr, int options, struct compat_rusage *ru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810941b0)
Location: kernel/exit.c:1700
Inline: False
Direct callers:
  - kernel/exit.c:__x32_compat_sys_wait4
  - kernel/exit.c:__ia32_compat_sys_wait4
```
**Symbols:**

```
ffffffff810941b0-ffffffff81094237: __do_compat_sys_wait4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int __do_compat_sys_wait4(compat_pid_t pid, compat_uint_t *stat_addr, int options, struct compat_rusage *ru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff8109c550)
Location: kernel/exit.c:1702
Inline: False
Direct callers:
  - kernel/exit.c:__x32_compat_sys_wait4
  - kernel/exit.c:__ia32_compat_sys_wait4
```
**Symbols:**

```
ffffffff8109c550-ffffffff8109c5d7: __do_compat_sys_wait4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long int __do_compat_sys_wait4(compat_pid_t pid, compat_uint_t *stat_addr, int options, struct compat_rusage *ru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810a0b70)
Location: kernel/exit.c:1706
Inline: False
Direct callers:
  - kernel/exit.c:__x32_compat_sys_wait4
  - kernel/exit.c:__ia32_compat_sys_wait4
```
**Symbols:**

```
ffffffff810a0b70-ffffffff810a0bf9: __do_compat_sys_wait4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int __do_compat_sys_wait4(compat_pid_t pid, compat_uint_t *stat_addr, int options, struct compat_rusage *ru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810a7150)
Location: kernel/exit.c:1652
Inline: False
Direct callers:
  - kernel/exit.c:__x32_compat_sys_wait4
  - kernel/exit.c:__ia32_compat_sys_wait4
```
**Symbols:**

```
ffffffff810a7150-ffffffff810a71d9: __do_compat_sys_wait4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int __do_compat_sys_wait4(compat_pid_t pid, compat_uint_t *stat_addr, int options, struct compat_rusage *ru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810ae8a0)
Location: kernel/exit.c:1656
Inline: False
Direct callers:
  - kernel/exit.c:__x32_compat_sys_wait4
  - kernel/exit.c:__ia32_compat_sys_wait4
```
**Symbols:**

```
ffffffff810ae8a0-ffffffff810ae928: __do_compat_sys_wait4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int __do_compat_sys_wait4(compat_pid_t pid, compat_uint_t *stat_addr, int options, struct compat_rusage *ru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810a9ef0)
Location: kernel/exit.c:1681
Inline: False
Direct callers:
  - kernel/exit.c:__x32_compat_sys_wait4
  - kernel/exit.c:__ia32_compat_sys_wait4
```
**Symbols:**

```
ffffffff810a9ef0-ffffffff810a9f78: __do_compat_sys_wait4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int __do_compat_sys_wait4(compat_pid_t pid, compat_uint_t *stat_addr, int options, struct compat_rusage *ru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810aaf20)
Location: kernel/exit.c:1728
Inline: False
Direct callers:
  - kernel/exit.c:__x32_compat_sys_wait4
  - kernel/exit.c:__ia32_compat_sys_wait4
```
**Symbols:**

```
ffffffff810aaf20-ffffffff810aafa9: __do_compat_sys_wait4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int __do_compat_sys_wait4(compat_pid_t pid, compat_uint_t *stat_addr, int options, struct compat_rusage *ru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810bca40)
Location: kernel/exit.c:1728
Inline: False
Direct callers:
  - kernel/exit.c:__x64_compat_sys_wait4
  - kernel/exit.c:__ia32_compat_sys_wait4
```
**Symbols:**

```
ffffffff810bca40-ffffffff810bcac9: __do_compat_sys_wait4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int __do_compat_sys_wait4(compat_pid_t pid, compat_uint_t *stat_addr, int options, struct compat_rusage *ru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810d3860)
Location: kernel/exit.c:1732
Inline: False
Direct callers:
  - kernel/exit.c:__ia32_compat_sys_wait4
```
**Symbols:**

```
ffffffff810d3860-ffffffff810d3911: __do_compat_sys_wait4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int __do_compat_sys_wait4(compat_pid_t pid, compat_uint_t *stat_addr, int options, struct compat_rusage *ru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810f2560)
Location: kernel/exit.c:1826
Inline: False
Direct callers:
  - kernel/exit.c:__ia32_compat_sys_wait4
```
**Symbols:**

```
ffffffff810f2560-ffffffff810f2611: __do_compat_sys_wait4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int __do_compat_sys_wait4(compat_pid_t pid, compat_uint_t *stat_addr, int options, struct compat_rusage *ru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810fe4e0)
Location: kernel/exit.c:1831
Inline: False
Direct callers:
  - kernel/exit.c:__ia32_compat_sys_wait4
```
**Symbols:**

```
ffffffff810fe4e0-ffffffff810fe591: __do_compat_sys_wait4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int __do_compat_sys_wait4(compat_pid_t pid, compat_uint_t *stat_addr, int options, struct compat_rusage *ru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff81107b90)
Location: kernel/exit.c:1834
Inline: False
Direct callers:
  - kernel/exit.c:__ia32_compat_sys_wait4
```
**Symbols:**

```
ffffffff81107b90-ffffffff81107c41: __do_compat_sys_wait4 (STB_LOCAL)
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
long int __do_compat_sys_wait4(compat_pid_t pid, compat_uint_t *stat_addr, int options, struct compat_rusage *ru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffff8000100fe228)
Location: kernel/exit.c:1652
Inline: False
Direct callers:
  - kernel/exit.c:__arm64_compat_sys_wait4
```
**Symbols:**

```
ffff8000100fe228-ffff8000100fe2c0: __do_compat_sys_wait4 (STB_LOCAL)
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
long int __do_compat_sys_wait4(compat_pid_t pid, compat_uint_t *stat_addr, int options, struct compat_rusage *ru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (c000000000145260)
Location: kernel/exit.c:1652
Inline: False
Direct callers:
  - kernel/exit.c:__se_compat_sys_wait4
```
**Symbols:**

```
c000000000145260-c000000000145304: __do_compat_sys_wait4 (STB_LOCAL)
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
long int __do_compat_sys_wait4(compat_pid_t pid, compat_uint_t *stat_addr, int options, struct compat_rusage *ru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810a0a70)
Location: kernel/exit.c:1652
Inline: False
Direct callers:
  - kernel/exit.c:__x32_compat_sys_wait4
  - kernel/exit.c:__ia32_compat_sys_wait4
```
**Symbols:**

```
ffffffff810a0a70-ffffffff810a0af9: __do_compat_sys_wait4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int __do_compat_sys_wait4(compat_pid_t pid, compat_uint_t *stat_addr, int options, struct compat_rusage *ru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff8108f490)
Location: kernel/exit.c:1652
Inline: False
Direct callers:
  - kernel/exit.c:__x32_compat_sys_wait4
  - kernel/exit.c:__ia32_compat_sys_wait4
```
**Symbols:**

```
ffffffff8108f490-ffffffff8108f519: __do_compat_sys_wait4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int __do_compat_sys_wait4(compat_pid_t pid, compat_uint_t *stat_addr, int options, struct compat_rusage *ru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810a0a20)
Location: kernel/exit.c:1652
Inline: False
Direct callers:
  - kernel/exit.c:__x32_compat_sys_wait4
  - kernel/exit.c:__ia32_compat_sys_wait4
```
**Symbols:**

```
ffffffff810a0a20-ffffffff810a0aa9: __do_compat_sys_wait4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int __do_compat_sys_wait4(compat_pid_t pid, compat_uint_t *stat_addr, int options, struct compat_rusage *ru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810a89a0)
Location: kernel/exit.c:1652
Inline: False
Direct callers:
  - kernel/exit.c:__x32_compat_sys_wait4
  - kernel/exit.c:__ia32_compat_sys_wait4
```
**Symbols:**

```
ffffffff810a89a0-ffffffff810a8a29: __do_compat_sys_wait4 (STB_LOCAL)
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
