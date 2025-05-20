# Function: <code>do_rt_tgsigqueueinfo</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int do_rt_tgsigqueueinfo(pid_t tgid, pid_t pid, int sig, siginfo_t *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8108f4a0)
Location: kernel/signal.c:2982
Inline: False
Direct callers:
  - kernel/signal.c:SYSC_rt_tgsigqueueinfo
  - kernel/signal.c:C_SYSC_rt_tgsigqueueinfo
```
**Symbols:**

```
ffffffff8108f4a0-ffffffff8108f50e: do_rt_tgsigqueueinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int do_rt_tgsigqueueinfo(pid_t tgid, pid_t pid, int sig, siginfo_t *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81092510)
Location: kernel/signal.c:2982
Inline: False
Direct callers:
  - kernel/signal.c:C_SYSC_rt_tgsigqueueinfo
  - kernel/signal.c:SYSC_rt_tgsigqueueinfo
```
**Symbols:**

```
ffffffff81092510-ffffffff81092584: do_rt_tgsigqueueinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int do_rt_tgsigqueueinfo(pid_t tgid, pid_t pid, int sig, siginfo_t *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810974a0)
Location: kernel/signal.c:2995
Inline: False
Direct callers:
  - kernel/signal.c:C_SYSC_rt_tgsigqueueinfo
  - kernel/signal.c:SYSC_rt_tgsigqueueinfo
```
**Symbols:**

```
ffffffff810974a0-ffffffff81097514: do_rt_tgsigqueueinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int do_rt_tgsigqueueinfo(pid_t tgid, pid_t pid, int sig, siginfo_t *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810947b0)
Location: kernel/signal.c:3050
Inline: False
Direct callers:
  - kernel/signal.c:C_SYSC_rt_tgsigqueueinfo
  - kernel/signal.c:SYSC_rt_tgsigqueueinfo
```
**Symbols:**

```
ffffffff810947b0-ffffffff81094824: do_rt_tgsigqueueinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int do_rt_tgsigqueueinfo(pid_t tgid, pid_t pid, int sig, siginfo_t *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8109b650)
Location: kernel/signal.c:3071
Inline: False
Direct callers:
  - kernel/signal.c:C_SYSC_rt_tgsigqueueinfo
  - kernel/signal.c:SYSC_rt_tgsigqueueinfo
```
**Symbols:**

```
ffffffff8109b650-ffffffff8109b6c4: do_rt_tgsigqueueinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int do_rt_tgsigqueueinfo(pid_t tgid, pid_t pid, int sig, siginfo_t *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8109f700)
Location: kernel/signal.c:3304
Inline: False
Direct callers:
  - kernel/signal.c:__do_compat_sys_rt_tgsigqueueinfo
  - kernel/signal.c:__do_sys_rt_tgsigqueueinfo
```
**Symbols:**

```
ffffffff8109f700-ffffffff8109f771: do_rt_tgsigqueueinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int do_rt_tgsigqueueinfo(pid_t tgid, pid_t pid, int sig, kernel_siginfo_t *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810a7990)
Location: kernel/signal.c:3631
Inline: False
Direct callers:
  - kernel/signal.c:__x32_compat_sys_rt_tgsigqueueinfo
  - kernel/signal.c:__ia32_compat_sys_rt_tgsigqueueinfo
  - kernel/signal.c:__ia32_sys_rt_tgsigqueueinfo
  - kernel/signal.c:__x64_sys_rt_tgsigqueueinfo
```
**Symbols:**

```
ffffffff810a7990-ffffffff810a79fb: do_rt_tgsigqueueinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int do_rt_tgsigqueueinfo(pid_t tgid, pid_t pid, int sig, kernel_siginfo_t *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810ae140)
Location: kernel/signal.c:3879
Inline: False
Direct callers:
  - kernel/signal.c:__x32_compat_sys_rt_tgsigqueueinfo
  - kernel/signal.c:__ia32_compat_sys_rt_tgsigqueueinfo
  - kernel/signal.c:__ia32_sys_rt_tgsigqueueinfo
  - kernel/signal.c:__x64_sys_rt_tgsigqueueinfo
```
**Symbols:**

```
ffffffff810ae140-ffffffff810ae1b7: do_rt_tgsigqueueinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int do_rt_tgsigqueueinfo(pid_t tgid, pid_t pid, int sig, kernel_siginfo_t *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b4750)
Location: kernel/signal.c:3887
Inline: False
Direct callers:
  - kernel/signal.c:__x32_compat_sys_rt_tgsigqueueinfo
  - kernel/signal.c:__ia32_compat_sys_rt_tgsigqueueinfo
  - kernel/signal.c:__ia32_sys_rt_tgsigqueueinfo
  - kernel/signal.c:__x64_sys_rt_tgsigqueueinfo
```
**Symbols:**

```
ffffffff810b4750-ffffffff810b47c7: do_rt_tgsigqueueinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int do_rt_tgsigqueueinfo(pid_t tgid, pid_t pid, int sig, kernel_siginfo_t *info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810bcee0)
Location: kernel/signal.c:3905
Inline: True
Inline callers:
  - kernel/signal.c:__x32_compat_sys_rt_tgsigqueueinfo
  - kernel/signal.c:__x64_sys_rt_tgsigqueueinfo
Direct callers:
  - kernel/signal.c:__ia32_compat_sys_rt_tgsigqueueinfo
  - kernel/signal.c:__ia32_sys_rt_tgsigqueueinfo
```
**Symbols:**

```
ffffffff810bcc60-ffffffff810bccd7: do_rt_tgsigqueueinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int do_rt_tgsigqueueinfo(pid_t tgid, pid_t pid, int sig, kernel_siginfo_t *info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b8140)
Location: kernel/signal.c:3926
Inline: True
Inline callers:
  - kernel/signal.c:__x32_compat_sys_rt_tgsigqueueinfo
  - kernel/signal.c:__x64_sys_rt_tgsigqueueinfo
Direct callers:
  - kernel/signal.c:__ia32_compat_sys_rt_tgsigqueueinfo
  - kernel/signal.c:__ia32_sys_rt_tgsigqueueinfo
```
**Symbols:**

```
ffffffff810b7f80-ffffffff810b7ff7: do_rt_tgsigqueueinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int do_rt_tgsigqueueinfo(pid_t tgid, pid_t pid, int sig, kernel_siginfo_t *info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b96c5)
Location: kernel/signal.c:3948
Inline: True
Inline callers:
  - kernel/signal.c:__x32_compat_sys_rt_tgsigqueueinfo
  - kernel/signal.c:__x64_sys_rt_tgsigqueueinfo
Direct callers:
  - kernel/signal.c:__ia32_compat_sys_rt_tgsigqueueinfo
  - kernel/signal.c:__ia32_sys_rt_tgsigqueueinfo
```
**Symbols:**

```
ffffffff810b9500-ffffffff810b9577: do_rt_tgsigqueueinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int do_rt_tgsigqueueinfo(pid_t tgid, pid_t pid, int sig, kernel_siginfo_t *info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810cbcd5)
Location: kernel/signal.c:4036
Inline: True
Inline callers:
  - kernel/signal.c:__x64_compat_sys_rt_tgsigqueueinfo
  - kernel/signal.c:__x64_sys_rt_tgsigqueueinfo
Direct callers:
  - kernel/signal.c:__ia32_compat_sys_rt_tgsigqueueinfo
  - kernel/signal.c:__ia32_sys_rt_tgsigqueueinfo
```
**Symbols:**

```
ffffffff810cbb10-ffffffff810cbb87: do_rt_tgsigqueueinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int do_rt_tgsigqueueinfo(pid_t tgid, pid_t pid, int sig, kernel_siginfo_t *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810e2c40)
Location: kernel/signal.c:4019
Inline: False
Direct callers:
  - kernel/signal.c:__ia32_compat_sys_rt_tgsigqueueinfo
  - kernel/signal.c:__ia32_sys_rt_tgsigqueueinfo
  - kernel/signal.c:__x64_sys_rt_tgsigqueueinfo
```
**Symbols:**

```
ffffffff810e2c40-ffffffff810e2cca: do_rt_tgsigqueueinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int do_rt_tgsigqueueinfo(pid_t tgid, pid_t pid, int sig, kernel_siginfo_t *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff811030f0)
Location: kernel/signal.c:4021
Inline: False
Direct callers:
  - kernel/signal.c:__ia32_compat_sys_rt_tgsigqueueinfo
  - kernel/signal.c:__ia32_sys_rt_tgsigqueueinfo
  - kernel/signal.c:__x64_sys_rt_tgsigqueueinfo
```
**Symbols:**

```
ffffffff811030f0-ffffffff8110317a: do_rt_tgsigqueueinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int do_rt_tgsigqueueinfo(pid_t tgid, pid_t pid, int sig, kernel_siginfo_t *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8110f330)
Location: kernel/signal.c:4045
Inline: False
Direct callers:
  - kernel/signal.c:__ia32_compat_sys_rt_tgsigqueueinfo
  - kernel/signal.c:__ia32_sys_rt_tgsigqueueinfo
  - kernel/signal.c:__x64_sys_rt_tgsigqueueinfo
```
**Symbols:**

```
ffffffff8110f330-ffffffff8110f3ba: do_rt_tgsigqueueinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int do_rt_tgsigqueueinfo(pid_t tgid, pid_t pid, int sig, kernel_siginfo_t *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81118cb0)
Location: kernel/signal.c:4056
Inline: False
Direct callers:
  - kernel/signal.c:__ia32_compat_sys_rt_tgsigqueueinfo
  - kernel/signal.c:__ia32_sys_rt_tgsigqueueinfo
  - kernel/signal.c:__x64_sys_rt_tgsigqueueinfo
```
**Symbols:**

```
ffffffff81118cb0-ffffffff81118d3a: do_rt_tgsigqueueinfo (STB_LOCAL)
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
int do_rt_tgsigqueueinfo(pid_t tgid, pid_t pid, int sig, kernel_siginfo_t *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffff8000101107f0)
Location: kernel/signal.c:3887
Inline: False
Direct callers:
  - kernel/signal.c:__arm64_compat_sys_rt_tgsigqueueinfo
  - kernel/signal.c:__arm64_sys_rt_tgsigqueueinfo
```
**Symbols:**

```
ffff8000101107f0-ffff800010110880: do_rt_tgsigqueueinfo (STB_LOCAL)
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
In kernel/signal.c (c0369ae0)
Location: kernel/signal.c:3887
Inline: True
Inline callers:
  - kernel/signal.c:__se_sys_rt_tgsigqueueinfo
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int do_rt_tgsigqueueinfo(pid_t tgid, pid_t pid, int sig, kernel_siginfo_t *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c000000000158010)
Location: kernel/signal.c:3887
Inline: False
Direct callers:
  - kernel/signal.c:__se_compat_sys_rt_tgsigqueueinfo
  - kernel/signal.c:__se_sys_rt_tgsigqueueinfo
```
**Symbols:**

```
c000000000158010-c000000000158110: do_rt_tgsigqueueinfo (STB_LOCAL)
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
In kernel/signal.c (ffffffe0000d19d0)
Location: kernel/signal.c:3887
Inline: True
Inline callers:
  - kernel/signal.c:__se_sys_rt_tgsigqueueinfo
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
int do_rt_tgsigqueueinfo(pid_t tgid, pid_t pid, int sig, kernel_siginfo_t *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810aeac0)
Location: kernel/signal.c:3887
Inline: False
Direct callers:
  - kernel/signal.c:__x32_compat_sys_rt_tgsigqueueinfo
  - kernel/signal.c:__ia32_compat_sys_rt_tgsigqueueinfo
  - kernel/signal.c:__ia32_sys_rt_tgsigqueueinfo
  - kernel/signal.c:__x64_sys_rt_tgsigqueueinfo
```
**Symbols:**

```
ffffffff810aeac0-ffffffff810aeb37: do_rt_tgsigqueueinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int do_rt_tgsigqueueinfo(pid_t tgid, pid_t pid, int sig, kernel_siginfo_t *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8109d410)
Location: kernel/signal.c:3887
Inline: False
Direct callers:
  - kernel/signal.c:__x32_compat_sys_rt_tgsigqueueinfo
  - kernel/signal.c:__ia32_compat_sys_rt_tgsigqueueinfo
  - kernel/signal.c:__ia32_sys_rt_tgsigqueueinfo
  - kernel/signal.c:__x64_sys_rt_tgsigqueueinfo
```
**Symbols:**

```
ffffffff8109d410-ffffffff8109d487: do_rt_tgsigqueueinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int do_rt_tgsigqueueinfo(pid_t tgid, pid_t pid, int sig, kernel_siginfo_t *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810ae020)
Location: kernel/signal.c:3887
Inline: False
Direct callers:
  - kernel/signal.c:__x32_compat_sys_rt_tgsigqueueinfo
  - kernel/signal.c:__ia32_compat_sys_rt_tgsigqueueinfo
  - kernel/signal.c:__ia32_sys_rt_tgsigqueueinfo
  - kernel/signal.c:__x64_sys_rt_tgsigqueueinfo
```
**Symbols:**

```
ffffffff810ae020-ffffffff810ae097: do_rt_tgsigqueueinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int do_rt_tgsigqueueinfo(pid_t tgid, pid_t pid, int sig, kernel_siginfo_t *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b6290)
Location: kernel/signal.c:3887
Inline: False
Direct callers:
  - kernel/signal.c:__x32_compat_sys_rt_tgsigqueueinfo
  - kernel/signal.c:__ia32_compat_sys_rt_tgsigqueueinfo
  - kernel/signal.c:__ia32_sys_rt_tgsigqueueinfo
  - kernel/signal.c:__x64_sys_rt_tgsigqueueinfo
```
**Symbols:**

```
ffffffff810b6290-ffffffff810b6307: do_rt_tgsigqueueinfo (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>siginfo_t *info</code> ➡️ <code>kernel_siginfo_t *info</code>
</li>
</ul>
</details>
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
