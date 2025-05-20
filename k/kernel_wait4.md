# Function: <code>kernel_wait4</code>

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
long int kernel_wait4(pid_t upid, int *stat_addr, int options, struct rusage *ru);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff81089720)
Location: kernel/exit.c:1633
Inline: False
Direct callers:
  - kernel/exit.c:C_SYSC_wait4
  - kernel/exit.c:C_SYSC_wait4
  - kernel/exit.c:SYSC_wait4
  - kernel/exit.c:SYSC_wait4
```
**Symbols:**

```
ffffffff81089720-ffffffff8108984d: kernel_wait4 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long int kernel_wait4(pid_t upid, int *stat_addr, int options, struct rusage *ru);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810904a0)
Location: kernel/exit.c:1630
Inline: False
Direct callers:
  - kernel/exit.c:C_SYSC_wait4
  - kernel/exit.c:C_SYSC_wait4
  - kernel/exit.c:SYSC_wait4
  - kernel/exit.c:SYSC_wait4
```
**Symbols:**

```
ffffffff810904a0-ffffffff810905cd: kernel_wait4 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long int kernel_wait4(pid_t upid, int *stat_addr, int options, struct rusage *ru);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff81093f70)
Location: kernel/exit.c:1630
Inline: False
Direct callers:
  - kernel/exit.c:__do_compat_sys_wait4
  - kernel/exit.c:__do_compat_sys_wait4
  - kernel/exit.c:__ia32_sys_waitpid
  - kernel/exit.c:__x64_sys_waitpid
  - kernel/exit.c:__do_sys_wait4
  - kernel/exit.c:__do_sys_wait4
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
**Symbols:**

```
ffffffff81093f70-ffffffff8109409e: kernel_wait4 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int kernel_wait4(pid_t upid, int *stat_addr, int options, struct rusage *ru);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff8109c2f0)
Location: kernel/exit.c:1632
Inline: False
Direct callers:
  - kernel/exit.c:__do_compat_sys_wait4
  - kernel/exit.c:__do_compat_sys_wait4
  - kernel/exit.c:__ia32_sys_waitpid
  - kernel/exit.c:__x64_sys_waitpid
  - kernel/exit.c:__do_sys_wait4
  - kernel/exit.c:__do_sys_wait4
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
**Symbols:**

```
ffffffff8109c2f0-ffffffff8109c434: kernel_wait4 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long int kernel_wait4(pid_t upid, int *stat_addr, int options, struct rusage *ru);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810a0910)
Location: kernel/exit.c:1636
Inline: False
Direct callers:
  - kernel/exit.c:__do_compat_sys_wait4
  - kernel/exit.c:__do_compat_sys_wait4
  - kernel/exit.c:__ia32_sys_waitpid
  - kernel/exit.c:__x64_sys_waitpid
  - kernel/exit.c:__do_sys_wait4
  - kernel/exit.c:__do_sys_wait4
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
**Symbols:**

```
ffffffff810a0910-ffffffff810a0a54: kernel_wait4 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int kernel_wait4(pid_t upid, int *stat_addr, int options, struct rusage *ru);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810a6ef0)
Location: kernel/exit.c:1582
Inline: False
Direct callers:
  - kernel/exit.c:__do_compat_sys_wait4
  - kernel/exit.c:__do_compat_sys_wait4
  - kernel/exit.c:__ia32_sys_waitpid
  - kernel/exit.c:__x64_sys_waitpid
  - kernel/exit.c:__do_sys_wait4
  - kernel/exit.c:__do_sys_wait4
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
**Symbols:**

```
ffffffff810a6ef0-ffffffff810a7034: kernel_wait4 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int kernel_wait4(pid_t upid, int *stat_addr, int options, struct rusage *ru);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810ae640)
Location: kernel/exit.c:1586
Inline: False
Direct callers:
  - kernel/exit.c:__do_compat_sys_wait4
  - kernel/exit.c:__do_compat_sys_wait4
  - kernel/exit.c:__ia32_sys_waitpid
  - kernel/exit.c:__x64_sys_waitpid
  - kernel/exit.c:__do_sys_wait4
  - kernel/exit.c:__do_sys_wait4
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
**Symbols:**

```
ffffffff810ae640-ffffffff810ae784: kernel_wait4 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int kernel_wait4(pid_t upid, int *stat_addr, int options, struct rusage *ru);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810a9c90)
Location: kernel/exit.c:1595
Inline: False
Direct callers:
  - kernel/exit.c:__do_compat_sys_wait4
  - kernel/exit.c:__do_compat_sys_wait4
  - kernel/exit.c:__ia32_sys_waitpid
  - kernel/exit.c:__x64_sys_waitpid
  - kernel/exit.c:__do_sys_wait4
  - kernel/exit.c:__do_sys_wait4
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
**Symbols:**

```
ffffffff810a9c90-ffffffff810a9dd4: kernel_wait4 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int kernel_wait4(pid_t upid, int *stat_addr, int options, struct rusage *ru);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810aacc0)
Location: kernel/exit.c:1642
Inline: False
Direct callers:
  - kernel/exit.c:__do_compat_sys_wait4
  - kernel/exit.c:__do_compat_sys_wait4
  - kernel/exit.c:__ia32_sys_waitpid
  - kernel/exit.c:__x64_sys_waitpid
  - kernel/exit.c:__do_sys_wait4
  - kernel/exit.c:__do_sys_wait4
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
**Symbols:**

```
ffffffff810aacc0-ffffffff810aae04: kernel_wait4 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int kernel_wait4(pid_t upid, int *stat_addr, int options, struct rusage *ru);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810bc7e0)
Location: kernel/exit.c:1642
Inline: False
Direct callers:
  - kernel/exit.c:__do_compat_sys_wait4
  - kernel/exit.c:__do_compat_sys_wait4
  - kernel/exit.c:__ia32_sys_waitpid
  - kernel/exit.c:__x64_sys_waitpid
  - kernel/exit.c:__do_sys_wait4
  - kernel/exit.c:__do_sys_wait4
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
**Symbols:**

```
ffffffff810bc7e0-ffffffff810bc924: kernel_wait4 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int kernel_wait4(pid_t upid, int *stat_addr, int options, struct rusage *ru);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810d3570)
Location: kernel/exit.c:1646
Inline: False
Direct callers:
  - kernel/exit.c:__do_compat_sys_wait4
  - kernel/exit.c:__do_compat_sys_wait4
  - kernel/exit.c:__ia32_sys_waitpid
  - kernel/exit.c:__x64_sys_waitpid
  - kernel/exit.c:__do_sys_wait4
  - kernel/exit.c:__do_sys_wait4
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
**Symbols:**

```
ffffffff810d3570-ffffffff810d36d7: kernel_wait4 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int kernel_wait4(pid_t upid, int *stat_addr, int options, struct rusage *ru);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810f2210)
Location: kernel/exit.c:1740
Inline: False
Direct callers:
  - kernel/exit.c:__do_compat_sys_wait4
  - kernel/exit.c:__do_compat_sys_wait4
  - kernel/exit.c:__ia32_sys_waitpid
  - kernel/exit.c:__x64_sys_waitpid
  - kernel/exit.c:__do_sys_wait4
  - kernel/exit.c:__do_sys_wait4
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
**Symbols:**

```
ffffffff810f2210-ffffffff810f2377: kernel_wait4 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int kernel_wait4(pid_t upid, int *stat_addr, int options, struct rusage *ru);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810fe190)
Location: kernel/exit.c:1745
Inline: False
Direct callers:
  - kernel/exit.c:__do_compat_sys_wait4
  - kernel/exit.c:__do_compat_sys_wait4
  - kernel/exit.c:__ia32_sys_waitpid
  - kernel/exit.c:__x64_sys_waitpid
  - kernel/exit.c:__do_sys_wait4
  - kernel/exit.c:__do_sys_wait4
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
**Symbols:**

```
ffffffff810fe190-ffffffff810fe2f7: kernel_wait4 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int kernel_wait4(pid_t upid, int *stat_addr, int options, struct rusage *ru);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff81107840)
Location: kernel/exit.c:1748
Inline: False
Direct callers:
  - kernel/exit.c:__do_compat_sys_wait4
  - kernel/exit.c:__do_compat_sys_wait4
  - kernel/exit.c:__ia32_sys_waitpid
  - kernel/exit.c:__x64_sys_waitpid
  - kernel/exit.c:__do_sys_wait4
  - kernel/exit.c:__do_sys_wait4
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
**Symbols:**

```
ffffffff81107840-ffffffff811079a7: kernel_wait4 (STB_GLOBAL)
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
long int kernel_wait4(pid_t upid, int *stat_addr, int options, struct rusage *ru);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffff8000100fddd8)
Location: kernel/exit.c:1582
Inline: False
Direct callers:
  - kernel/exit.c:__do_compat_sys_wait4
  - kernel/exit.c:__do_compat_sys_wait4
  - kernel/exit.c:__do_sys_wait4
  - kernel/exit.c:__do_sys_wait4
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
**Symbols:**

```
ffff8000100fddd8-ffff8000100fe038: kernel_wait4 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long int kernel_wait4(pid_t upid, int *stat_addr, int options, struct rusage *ru);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (c035b064)
Location: kernel/exit.c:1582
Inline: False
Direct callers:
  - kernel/exit.c:__se_sys_wait4
  - kernel/exit.c:__se_sys_wait4
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
**Symbols:**

```
c035b064-c035b1c8: kernel_wait4 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int kernel_wait4(pid_t upid, int *stat_addr, int options, struct rusage *ru);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (c000000000144f50)
Location: kernel/exit.c:1582
Inline: False
Direct callers:
  - kernel/exit.c:__do_compat_sys_wait4
  - kernel/exit.c:__do_compat_sys_wait4
  - kernel/exit.c:__se_sys_waitpid
  - kernel/exit.c:__do_sys_wait4
  - kernel/exit.c:__do_sys_wait4
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
**Symbols:**

```
c000000000144f50-c00000000014515c: kernel_wait4 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long int kernel_wait4(pid_t upid, int *stat_addr, int options, struct rusage *ru);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffe0000c658e)
Location: kernel/exit.c:1582
Inline: False
Direct callers:
  - kernel/exit.c:__do_sys_wait4
  - kernel/exit.c:__do_sys_wait4
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
**Symbols:**

```
ffffffe0000c658e-ffffffe0000c668e: kernel_wait4 (STB_GLOBAL)
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
long int kernel_wait4(pid_t upid, int *stat_addr, int options, struct rusage *ru);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810a0810)
Location: kernel/exit.c:1582
Inline: False
Direct callers:
  - kernel/exit.c:__do_compat_sys_wait4
  - kernel/exit.c:__do_compat_sys_wait4
  - kernel/exit.c:__ia32_sys_waitpid
  - kernel/exit.c:__x64_sys_waitpid
  - kernel/exit.c:__do_sys_wait4
  - kernel/exit.c:__do_sys_wait4
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
**Symbols:**

```
ffffffff810a0810-ffffffff810a0954: kernel_wait4 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int kernel_wait4(pid_t upid, int *stat_addr, int options, struct rusage *ru);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff8108f230)
Location: kernel/exit.c:1582
Inline: False
Direct callers:
  - kernel/exit.c:__do_compat_sys_wait4
  - kernel/exit.c:__do_compat_sys_wait4
  - kernel/exit.c:__ia32_sys_waitpid
  - kernel/exit.c:__x64_sys_waitpid
  - kernel/exit.c:__do_sys_wait4
  - kernel/exit.c:__do_sys_wait4
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
**Symbols:**

```
ffffffff8108f230-ffffffff8108f374: kernel_wait4 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int kernel_wait4(pid_t upid, int *stat_addr, int options, struct rusage *ru);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810a07c0)
Location: kernel/exit.c:1582
Inline: False
Direct callers:
  - kernel/exit.c:__do_compat_sys_wait4
  - kernel/exit.c:__do_compat_sys_wait4
  - kernel/exit.c:__ia32_sys_waitpid
  - kernel/exit.c:__x64_sys_waitpid
  - kernel/exit.c:__do_sys_wait4
  - kernel/exit.c:__do_sys_wait4
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
**Symbols:**

```
ffffffff810a07c0-ffffffff810a0904: kernel_wait4 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int kernel_wait4(pid_t upid, int *stat_addr, int options, struct rusage *ru);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810a8740)
Location: kernel/exit.c:1582
Inline: False
Direct callers:
  - kernel/exit.c:__do_compat_sys_wait4
  - kernel/exit.c:__do_compat_sys_wait4
  - kernel/exit.c:__ia32_sys_waitpid
  - kernel/exit.c:__x64_sys_waitpid
  - kernel/exit.c:__do_sys_wait4
  - kernel/exit.c:__do_sys_wait4
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
**Symbols:**

```
ffffffff810a8740-ffffffff810a8884: kernel_wait4 (STB_GLOBAL)
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
