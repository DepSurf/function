# Function: <code>do_rt_sigqueueinfo</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int do_rt_sigqueueinfo(pid_t pid, int sig, siginfo_t *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8108fa90)
Location: kernel/signal.c:2938
Inline: False
Direct callers:
  - kernel/signal.c:SYSC_rt_sigqueueinfo
  - kernel/signal.c:C_SYSC_rt_sigqueueinfo
```
**Symbols:**

```
ffffffff8108fa90-ffffffff8108faf1: do_rt_sigqueueinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int do_rt_sigqueueinfo(pid_t pid, int sig, siginfo_t *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81092b10)
Location: kernel/signal.c:2938
Inline: False
Direct callers:
  - kernel/signal.c:C_SYSC_rt_sigqueueinfo
  - kernel/signal.c:SYSC_rt_sigqueueinfo
```
**Symbols:**

```
ffffffff81092b10-ffffffff81092b71: do_rt_sigqueueinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int do_rt_sigqueueinfo(pid_t pid, int sig, siginfo_t *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81097aa0)
Location: kernel/signal.c:2951
Inline: False
Direct callers:
  - kernel/signal.c:C_SYSC_rt_sigqueueinfo
  - kernel/signal.c:SYSC_rt_sigqueueinfo
```
**Symbols:**

```
ffffffff81097aa0-ffffffff81097b01: do_rt_sigqueueinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int do_rt_sigqueueinfo(pid_t pid, int sig, siginfo_t *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81094de0)
Location: kernel/signal.c:3006
Inline: False
Direct callers:
  - kernel/signal.c:C_SYSC_rt_sigqueueinfo
  - kernel/signal.c:SYSC_rt_sigqueueinfo
```
**Symbols:**

```
ffffffff81094de0-ffffffff81094e41: do_rt_sigqueueinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int do_rt_sigqueueinfo(pid_t pid, int sig, siginfo_t *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8109bc80)
Location: kernel/signal.c:3027
Inline: False
Direct callers:
  - kernel/signal.c:C_SYSC_rt_sigqueueinfo
  - kernel/signal.c:SYSC_rt_sigqueueinfo
```
**Symbols:**

```
ffffffff8109bc80-ffffffff8109bce1: do_rt_sigqueueinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int do_rt_sigqueueinfo(pid_t pid, int sig, siginfo_t *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8109fd30)
Location: kernel/signal.c:3260
Inline: False
Direct callers:
  - kernel/signal.c:__do_compat_sys_rt_sigqueueinfo
  - kernel/signal.c:__do_sys_rt_sigqueueinfo
```
**Symbols:**

```
ffffffff8109fd30-ffffffff8109fd91: do_rt_sigqueueinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int do_rt_sigqueueinfo(pid_t pid, int sig, kernel_siginfo_t *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810a8090)
Location: kernel/signal.c:3588
Inline: False
Direct callers:
  - kernel/signal.c:__x32_compat_sys_rt_sigqueueinfo
  - kernel/signal.c:__ia32_compat_sys_rt_sigqueueinfo
  - kernel/signal.c:__ia32_sys_rt_sigqueueinfo
  - kernel/signal.c:__x64_sys_rt_sigqueueinfo
```
**Symbols:**

```
ffffffff810a8090-ffffffff810a80ee: do_rt_sigqueueinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int do_rt_sigqueueinfo(pid_t pid, int sig, kernel_siginfo_t *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810ad950)
Location: kernel/signal.c:3836
Inline: False
Direct callers:
  - kernel/signal.c:__x32_compat_sys_rt_sigqueueinfo
  - kernel/signal.c:__ia32_compat_sys_rt_sigqueueinfo
  - kernel/signal.c:__ia32_sys_rt_sigqueueinfo
  - kernel/signal.c:__x64_sys_rt_sigqueueinfo
```
**Symbols:**

```
ffffffff810ad950-ffffffff810ad9b0: do_rt_sigqueueinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int do_rt_sigqueueinfo(pid_t pid, int sig, kernel_siginfo_t *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b3f70)
Location: kernel/signal.c:3844
Inline: False
Direct callers:
  - kernel/signal.c:__x32_compat_sys_rt_sigqueueinfo
  - kernel/signal.c:__ia32_compat_sys_rt_sigqueueinfo
  - kernel/signal.c:__ia32_sys_rt_sigqueueinfo
  - kernel/signal.c:__x64_sys_rt_sigqueueinfo
```
**Symbols:**

```
ffffffff810b3f70-ffffffff810b3fd0: do_rt_sigqueueinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int do_rt_sigqueueinfo(pid_t pid, int sig, kernel_siginfo_t *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810bd0f0)
Location: kernel/signal.c:3862
Inline: False
Direct callers:
  - kernel/signal.c:__x32_compat_sys_rt_sigqueueinfo
  - kernel/signal.c:__ia32_compat_sys_rt_sigqueueinfo
  - kernel/signal.c:__ia32_sys_rt_sigqueueinfo
  - kernel/signal.c:__x64_sys_rt_sigqueueinfo
```
**Symbols:**

```
ffffffff810bd0f0-ffffffff810bd150: do_rt_sigqueueinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int do_rt_sigqueueinfo(pid_t pid, int sig, kernel_siginfo_t *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b8460)
Location: kernel/signal.c:3883
Inline: False
Direct callers:
  - kernel/signal.c:__x32_compat_sys_rt_sigqueueinfo
  - kernel/signal.c:__ia32_compat_sys_rt_sigqueueinfo
  - kernel/signal.c:__ia32_sys_rt_sigqueueinfo
  - kernel/signal.c:__x64_sys_rt_sigqueueinfo
```
**Symbols:**

```
ffffffff810b8460-ffffffff810b84cc: do_rt_sigqueueinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int do_rt_sigqueueinfo(pid_t pid, int sig, kernel_siginfo_t *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b99e0)
Location: kernel/signal.c:3905
Inline: False
Direct callers:
  - kernel/signal.c:__x32_compat_sys_rt_sigqueueinfo
  - kernel/signal.c:__ia32_compat_sys_rt_sigqueueinfo
  - kernel/signal.c:__ia32_sys_rt_sigqueueinfo
  - kernel/signal.c:__x64_sys_rt_sigqueueinfo
```
**Symbols:**

```
ffffffff810b99e0-ffffffff810b9a4c: do_rt_sigqueueinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int do_rt_sigqueueinfo(pid_t pid, int sig, kernel_siginfo_t *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810cbff0)
Location: kernel/signal.c:3993
Inline: False
Direct callers:
  - kernel/signal.c:__x64_compat_sys_rt_sigqueueinfo
  - kernel/signal.c:__ia32_compat_sys_rt_sigqueueinfo
  - kernel/signal.c:__ia32_sys_rt_sigqueueinfo
  - kernel/signal.c:__x64_sys_rt_sigqueueinfo
```
**Symbols:**

```
ffffffff810cbff0-ffffffff810cc05c: do_rt_sigqueueinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int do_rt_sigqueueinfo(pid_t pid, int sig, kernel_siginfo_t *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810e30f0)
Location: kernel/signal.c:3976
Inline: False
Direct callers:
  - kernel/signal.c:__ia32_compat_sys_rt_sigqueueinfo
  - kernel/signal.c:__ia32_sys_rt_sigqueueinfo
  - kernel/signal.c:__x64_sys_rt_sigqueueinfo
```
**Symbols:**

```
ffffffff810e30f0-ffffffff810e3166: do_rt_sigqueueinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int do_rt_sigqueueinfo(pid_t pid, int sig, kernel_siginfo_t *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81103610)
Location: kernel/signal.c:3978
Inline: False
Direct callers:
  - kernel/signal.c:__ia32_compat_sys_rt_sigqueueinfo
  - kernel/signal.c:__ia32_sys_rt_sigqueueinfo
  - kernel/signal.c:__x64_sys_rt_sigqueueinfo
```
**Symbols:**

```
ffffffff81103610-ffffffff81103686: do_rt_sigqueueinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int do_rt_sigqueueinfo(pid_t pid, int sig, kernel_siginfo_t *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8110f850)
Location: kernel/signal.c:4002
Inline: False
Direct callers:
  - kernel/signal.c:__ia32_compat_sys_rt_sigqueueinfo
  - kernel/signal.c:__ia32_sys_rt_sigqueueinfo
  - kernel/signal.c:__x64_sys_rt_sigqueueinfo
```
**Symbols:**

```
ffffffff8110f850-ffffffff8110f8c6: do_rt_sigqueueinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int do_rt_sigqueueinfo(pid_t pid, int sig, kernel_siginfo_t *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff811191c0)
Location: kernel/signal.c:4013
Inline: False
Direct callers:
  - kernel/signal.c:__ia32_compat_sys_rt_sigqueueinfo
  - kernel/signal.c:__ia32_sys_rt_sigqueueinfo
  - kernel/signal.c:__x64_sys_rt_sigqueueinfo
```
**Symbols:**

```
ffffffff811191c0-ffffffff81119236: do_rt_sigqueueinfo (STB_LOCAL)
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
int do_rt_sigqueueinfo(pid_t pid, int sig, kernel_siginfo_t *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffff800010110080)
Location: kernel/signal.c:3844
Inline: False
Direct callers:
  - kernel/signal.c:__arm64_compat_sys_rt_sigqueueinfo
  - kernel/signal.c:__arm64_sys_rt_sigqueueinfo
```
**Symbols:**

```
ffff800010110080-ffff8000101100fc: do_rt_sigqueueinfo (STB_LOCAL)
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
In kernel/signal.c (c0369a18)
Location: kernel/signal.c:3844
Inline: True
Inline callers:
  - kernel/signal.c:__se_sys_rt_sigqueueinfo
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int do_rt_sigqueueinfo(pid_t pid, int sig, kernel_siginfo_t *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c0000000001577b0)
Location: kernel/signal.c:3844
Inline: False
Direct callers:
  - kernel/signal.c:__se_compat_sys_rt_sigqueueinfo
  - kernel/signal.c:__se_sys_rt_sigqueueinfo
```
**Symbols:**

```
c0000000001577b0-c000000000157854: do_rt_sigqueueinfo (STB_LOCAL)
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
In kernel/signal.c (ffffffe0000d194a)
Location: kernel/signal.c:3844
Inline: True
Inline callers:
  - kernel/signal.c:__se_sys_rt_sigqueueinfo
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
int do_rt_sigqueueinfo(pid_t pid, int sig, kernel_siginfo_t *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810ae2e0)
Location: kernel/signal.c:3844
Inline: False
Direct callers:
  - kernel/signal.c:__x32_compat_sys_rt_sigqueueinfo
  - kernel/signal.c:__ia32_compat_sys_rt_sigqueueinfo
  - kernel/signal.c:__ia32_sys_rt_sigqueueinfo
  - kernel/signal.c:__x64_sys_rt_sigqueueinfo
```
**Symbols:**

```
ffffffff810ae2e0-ffffffff810ae340: do_rt_sigqueueinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int do_rt_sigqueueinfo(pid_t pid, int sig, kernel_siginfo_t *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8109cc30)
Location: kernel/signal.c:3844
Inline: False
Direct callers:
  - kernel/signal.c:__x32_compat_sys_rt_sigqueueinfo
  - kernel/signal.c:__ia32_compat_sys_rt_sigqueueinfo
  - kernel/signal.c:__ia32_sys_rt_sigqueueinfo
  - kernel/signal.c:__x64_sys_rt_sigqueueinfo
```
**Symbols:**

```
ffffffff8109cc30-ffffffff8109cc90: do_rt_sigqueueinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int do_rt_sigqueueinfo(pid_t pid, int sig, kernel_siginfo_t *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810ad840)
Location: kernel/signal.c:3844
Inline: False
Direct callers:
  - kernel/signal.c:__x32_compat_sys_rt_sigqueueinfo
  - kernel/signal.c:__ia32_compat_sys_rt_sigqueueinfo
  - kernel/signal.c:__ia32_sys_rt_sigqueueinfo
  - kernel/signal.c:__x64_sys_rt_sigqueueinfo
```
**Symbols:**

```
ffffffff810ad840-ffffffff810ad8a0: do_rt_sigqueueinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int do_rt_sigqueueinfo(pid_t pid, int sig, kernel_siginfo_t *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b5a70)
Location: kernel/signal.c:3844
Inline: False
Direct callers:
  - kernel/signal.c:__x32_compat_sys_rt_sigqueueinfo
  - kernel/signal.c:__ia32_compat_sys_rt_sigqueueinfo
  - kernel/signal.c:__ia32_sys_rt_sigqueueinfo
  - kernel/signal.c:__x64_sys_rt_sigqueueinfo
```
**Symbols:**

```
ffffffff810b5a70-ffffffff810b5ae1: do_rt_sigqueueinfo (STB_LOCAL)
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
