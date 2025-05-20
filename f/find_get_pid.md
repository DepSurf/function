# Function: <code>find_get_pid</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct pid *find_get_pid(pid_t nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff8109dc10)
Location: kernel/pid.c:488
Inline: False
Direct callers:
  - kernel/exit.c:SyS_waitid
  - kernel/exit.c:SyS_waitpid
  - kernel/exit.c:SyS_waitpid
  - kernel/sysctl.c:proc_do_cad_pid
  - kernel/trace/ftrace.c:ftrace_pid_write
  - net/core/scm.c:__scm_send
```
**Symbols:**

```
ffffffff8109dc10-ffffffff8109dc4d: find_get_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct pid *find_get_pid(pid_t nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810a1270)
Location: kernel/pid.c:488
Inline: False
Direct callers:
  - kernel/exit.c:SyS_waitpid
  - kernel/exit.c:SyS_waitpid
  - kernel/exit.c:SyS_waitid
  - kernel/sysctl.c:proc_do_cad_pid
  - net/core/scm.c:__scm_send
```
**Symbols:**

```
ffffffff810a1270-ffffffff810a12ad: find_get_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct pid *find_get_pid(pid_t nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810a6330)
Location: kernel/pid.c:488
Inline: False
Direct callers:
  - kernel/exit.c:SyS_waitpid
  - kernel/exit.c:SyS_waitpid
  - kernel/exit.c:SyS_waitid
  - kernel/sysctl.c:proc_do_cad_pid
  - net/core/scm.c:__scm_send
```
**Symbols:**

```
ffffffff810a6330-ffffffff810a636d: find_get_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct pid *find_get_pid(pid_t nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810a3310)
Location: kernel/pid.c:489
Inline: False
Direct callers:
  - kernel/exit.c:kernel_wait4
  - kernel/exit.c:kernel_wait4
  - kernel/exit.c:kernel_waitid
  - kernel/sysctl.c:proc_do_cad_pid
  - net/core/scm.c:__scm_send
```
**Symbols:**

```
ffffffff810a3310-ffffffff810a334b: find_get_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct pid *find_get_pid(pid_t nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810a9df0)
Location: kernel/pid.c:358
Inline: False
Direct callers:
  - kernel/exit.c:kernel_wait4
  - kernel/exit.c:kernel_wait4
  - kernel/exit.c:kernel_waitid
  - kernel/sysctl.c:proc_do_cad_pid
  - net/core/scm.c:__scm_send
```
**Symbols:**

```
ffffffff810a9df0-ffffffff810a9e36: find_get_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct pid *find_get_pid(pid_t nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810b0a10)
Location: kernel/pid.c:383
Inline: False
Direct callers:
  - kernel/exit.c:kernel_wait4
  - kernel/exit.c:kernel_wait4
  - kernel/exit.c:kernel_waitid
  - kernel/sysctl.c:proc_do_cad_pid
  - net/core/scm.c:__scm_send
```
**Symbols:**

```
ffffffff810b0a10-ffffffff810b0a58: find_get_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct pid *find_get_pid(pid_t nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810b9ae0)
Location: kernel/pid.c:390
Inline: False
Direct callers:
  - kernel/exit.c:kernel_wait4
  - kernel/exit.c:kernel_wait4
  - kernel/exit.c:kernel_waitid
  - kernel/sysctl.c:proc_do_cad_pid
  - net/core/scm.c:__scm_send
```
**Symbols:**

```
ffffffff810b9ae0-ffffffff810b9b24: find_get_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct pid *find_get_pid(pid_t nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810bf850)
Location: kernel/pid.c:393
Inline: False
Direct callers:
  - kernel/exit.c:kernel_wait4
  - kernel/exit.c:kernel_wait4
  - kernel/exit.c:kernel_waitid
  - kernel/sysctl.c:proc_do_cad_pid
  - kernel/pid.c:__ia32_sys_pidfd_open
  - kernel/pid.c:__x64_sys_pidfd_open
  - net/core/scm.c:__scm_send
```
**Symbols:**

```
ffffffff810bf850-ffffffff810bf896: find_get_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct pid *find_get_pid(pid_t nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810c5c20)
Location: kernel/pid.c:393
Inline: False
Direct callers:
  - kernel/exit.c:kernel_wait4
  - kernel/exit.c:kernel_wait4
  - kernel/exit.c:kernel_waitid
  - kernel/exit.c:kernel_waitid
  - kernel/sysctl.c:proc_do_cad_pid
  - kernel/pid.c:__ia32_sys_pidfd_open
  - kernel/pid.c:__x64_sys_pidfd_open
  - net/core/scm.c:__scm_send
```
**Symbols:**

```
ffffffff810c5c20-ffffffff810c5c66: find_get_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct pid *find_get_pid(pid_t nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810cd5f0)
Location: kernel/pid.c:459
Inline: False
Direct callers:
  - kernel/exit.c:kernel_wait4
  - kernel/exit.c:kernel_wait4
  - kernel/exit.c:kernel_waitid
  - kernel/exit.c:kernel_waitid
  - kernel/sysctl.c:proc_do_cad_pid
  - kernel/pid.c:__ia32_sys_pidfd_open
  - kernel/pid.c:__x64_sys_pidfd_open
  - net/core/scm.c:__scm_send
```
**Symbols:**

```
ffffffff810cd5f0-ffffffff810cd673: find_get_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct pid *find_get_pid(pid_t nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810c81c0)
Location: kernel/pid.c:460
Inline: False
Direct callers:
  - kernel/exit.c:kernel_wait
  - kernel/exit.c:kernel_wait4
  - kernel/exit.c:kernel_wait4
  - kernel/exit.c:kernel_waitid
  - kernel/exit.c:kernel_waitid
  - kernel/sysctl.c:proc_do_cad_pid
  - kernel/pid.c:__ia32_sys_pidfd_open
  - kernel/pid.c:__x64_sys_pidfd_open
  - net/core/scm.c:__scm_send
```
**Symbols:**

```
ffffffff810c81c0-ffffffff810c8242: find_get_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct pid *find_get_pid(pid_t nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810c9ce0)
Location: kernel/pid.c:460
Inline: False
Direct callers:
  - kernel/exit.c:kernel_wait
  - kernel/exit.c:kernel_wait4
  - kernel/exit.c:kernel_wait4
  - kernel/exit.c:kernel_waitid
  - kernel/exit.c:kernel_waitid
  - kernel/sysctl.c:proc_do_cad_pid
  - kernel/pid.c:__ia32_sys_pidfd_open
  - kernel/pid.c:__x64_sys_pidfd_open
  - net/core/scm.c:__scm_send
```
**Symbols:**

```
ffffffff810c9ce0-ffffffff810c9d62: find_get_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct pid *find_get_pid(pid_t nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810dcbd0)
Location: kernel/pid.c:460
Inline: False
Direct callers:
  - kernel/exit.c:kernel_wait
  - kernel/exit.c:kernel_wait4
  - kernel/exit.c:kernel_wait4
  - kernel/exit.c:kernel_waitid
  - kernel/exit.c:kernel_waitid
  - kernel/sysctl.c:proc_do_cad_pid
  - kernel/pid.c:__ia32_sys_pidfd_open
  - kernel/pid.c:__x64_sys_pidfd_open
  - net/core/scm.c:__scm_send
```
**Symbols:**

```
ffffffff810dcbd0-ffffffff810dcc52: find_get_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct pid *find_get_pid(pid_t nr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810f754a)
Location: kernel/pid.c:460
Inline: True
Inline callers:
  - kernel/pid.c:__ia32_sys_pidfd_open
  - kernel/pid.c:__x64_sys_pidfd_open
Direct callers:
  - kernel/exit.c:kernel_wait
  - kernel/exit.c:kernel_wait4
  - kernel/exit.c:kernel_wait4
  - kernel/exit.c:kernel_waitid
  - kernel/exit.c:kernel_waitid
  - kernel/sysctl.c:proc_do_cad_pid
  - net/core/scm.c:__scm_send
```
**Symbols:**

```
ffffffff810f6440-ffffffff810f64cc: find_get_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct pid *find_get_pid(pid_t nr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff81119cca)
Location: kernel/pid.c:460
Inline: True
Inline callers:
  - kernel/pid.c:__ia32_sys_pidfd_open
  - kernel/pid.c:__x64_sys_pidfd_open
Direct callers:
  - kernel/exit.c:kernel_wait
  - kernel/exit.c:kernel_wait4
  - kernel/exit.c:kernel_wait4
  - kernel/exit.c:kernel_waitid
  - kernel/exit.c:kernel_waitid
  - kernel/sysctl.c:proc_do_cad_pid
  - net/core/scm.c:__scm_send
```
**Symbols:**

```
ffffffff81118ac0-ffffffff81118b4c: find_get_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct pid *find_get_pid(pid_t nr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff81125ddb)
Location: kernel/pid.c:463
Inline: True
Inline callers:
  - kernel/pid.c:__ia32_sys_pidfd_open
  - kernel/pid.c:__x64_sys_pidfd_open
Direct callers:
  - kernel/exit.c:kernel_wait
  - kernel/exit.c:kernel_wait4
  - kernel/exit.c:kernel_wait4
  - kernel/exit.c:kernel_waitid
  - kernel/exit.c:kernel_waitid
  - kernel/sysctl.c:proc_do_cad_pid
  - net/core/scm.c:__scm_send
```
**Symbols:**

```
ffffffff81125d00-ffffffff81125d8c: find_get_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct pid *find_get_pid(pid_t nr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff811303db)
Location: kernel/pid.c:463
Inline: True
Inline callers:
  - kernel/pid.c:__ia32_sys_pidfd_open
  - kernel/pid.c:__x64_sys_pidfd_open
Direct callers:
  - kernel/exit.c:kernel_wait
  - kernel/exit.c:kernel_wait4
  - kernel/exit.c:kernel_wait4
  - kernel/exit.c:kernel_waitid_prepare
  - kernel/exit.c:kernel_waitid_prepare
  - kernel/sysctl.c:proc_do_cad_pid
  - net/core/scm.c:__scm_send
```
**Symbols:**

```
ffffffff81130300-ffffffff8113038c: find_get_pid (STB_GLOBAL)
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
struct pid *find_get_pid(pid_t nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffff800010124230)
Location: kernel/pid.c:393
Inline: False
Direct callers:
  - kernel/exit.c:kernel_wait4
  - kernel/exit.c:kernel_wait4
  - kernel/exit.c:kernel_waitid
  - kernel/exit.c:kernel_waitid
  - kernel/sysctl.c:proc_do_cad_pid
  - kernel/pid.c:__arm64_sys_pidfd_open
  - net/core/scm.c:__scm_send
```
**Symbols:**

```
ffff800010124230-ffff800010124288: find_get_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct pid *find_get_pid(pid_t nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (c0377528)
Location: kernel/pid.c:393
Inline: False
Direct callers:
  - kernel/exit.c:kernel_wait4
  - kernel/exit.c:kernel_wait4
  - kernel/exit.c:kernel_waitid
  - kernel/exit.c:kernel_waitid
  - kernel/sysctl.c:proc_do_cad_pid
  - kernel/pid.c:__se_sys_pidfd_open
  - net/core/scm.c:__scm_send
```
**Symbols:**

```
c0377528-c0377554: find_get_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct pid *find_get_pid(pid_t nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (c00000000016def0)
Location: kernel/pid.c:393
Inline: False
Direct callers:
  - kernel/exit.c:kernel_wait4
  - kernel/exit.c:kernel_wait4
  - kernel/exit.c:kernel_waitid
  - kernel/exit.c:kernel_waitid
  - kernel/sysctl.c:proc_do_cad_pid
  - kernel/pid.c:__se_sys_pidfd_open
  - net/core/scm.c:__scm_send
```
**Symbols:**

```
c00000000016def0-c00000000016df68: find_get_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct pid *find_get_pid(pid_t nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffe0000dc47e)
Location: kernel/pid.c:393
Inline: False
Direct callers:
  - kernel/exit.c:kernel_wait4
  - kernel/exit.c:kernel_wait4
  - kernel/exit.c:kernel_waitid
  - kernel/exit.c:kernel_waitid
  - kernel/sysctl.c:proc_do_cad_pid
  - kernel/pid.c:__se_sys_pidfd_open
  - net/core/scm.c:__scm_send
```
**Symbols:**

```
ffffffe0000dc47e-ffffffe0000dc4c6: find_get_pid (STB_GLOBAL)
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
struct pid *find_get_pid(pid_t nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810bffa0)
Location: kernel/pid.c:393
Inline: False
Direct callers:
  - kernel/exit.c:kernel_wait4
  - kernel/exit.c:kernel_wait4
  - kernel/exit.c:kernel_waitid
  - kernel/exit.c:kernel_waitid
  - kernel/sysctl.c:proc_do_cad_pid
  - kernel/pid.c:__ia32_sys_pidfd_open
  - kernel/pid.c:__x64_sys_pidfd_open
  - net/core/scm.c:__scm_send
```
**Symbols:**

```
ffffffff810bffa0-ffffffff810bffe6: find_get_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct pid *find_get_pid(pid_t nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810ae7b0)
Location: kernel/pid.c:393
Inline: False
Direct callers:
  - kernel/exit.c:kernel_wait4
  - kernel/exit.c:kernel_wait4
  - kernel/exit.c:kernel_waitid
  - kernel/exit.c:kernel_waitid
  - kernel/sysctl.c:proc_do_cad_pid
  - kernel/pid.c:__ia32_sys_pidfd_open
  - kernel/pid.c:__x64_sys_pidfd_open
  - net/core/scm.c:__scm_send
```
**Symbols:**

```
ffffffff810ae7b0-ffffffff810ae7f6: find_get_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct pid *find_get_pid(pid_t nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810bf4f0)
Location: kernel/pid.c:393
Inline: False
Direct callers:
  - kernel/exit.c:kernel_wait4
  - kernel/exit.c:kernel_wait4
  - kernel/exit.c:kernel_waitid
  - kernel/exit.c:kernel_waitid
  - kernel/sysctl.c:proc_do_cad_pid
  - kernel/pid.c:__ia32_sys_pidfd_open
  - kernel/pid.c:__x64_sys_pidfd_open
  - net/core/scm.c:__scm_send
```
**Symbols:**

```
ffffffff810bf4f0-ffffffff810bf536: find_get_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct pid *find_get_pid(pid_t nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810c77f0)
Location: kernel/pid.c:393
Inline: False
Direct callers:
  - kernel/exit.c:kernel_wait4
  - kernel/exit.c:kernel_wait4
  - kernel/exit.c:kernel_waitid
  - kernel/exit.c:kernel_waitid
  - kernel/sysctl.c:proc_do_cad_pid
  - kernel/pid.c:__ia32_sys_pidfd_open
  - kernel/pid.c:__x64_sys_pidfd_open
  - net/core/scm.c:__scm_send
```
**Symbols:**

```
ffffffff810c77f0-ffffffff810c784d: find_get_pid (STB_GLOBAL)
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
