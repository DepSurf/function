# Function: <code>do_send_specific</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int do_send_specific(pid_t tgid, pid_t pid, int sig, struct siginfo *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8108f340)
Location: kernel/signal.c:2861
Inline: False
Direct callers:
  - kernel/signal.c:do_tkill
  - kernel/signal.c:do_rt_tgsigqueueinfo
```
**Symbols:**

```
ffffffff8108f340-ffffffff8108f3c7: do_send_specific (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int do_send_specific(pid_t tgid, pid_t pid, int sig, struct siginfo *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810923b0)
Location: kernel/signal.c:2861
Inline: False
Direct callers:
  - kernel/signal.c:do_rt_tgsigqueueinfo
  - kernel/signal.c:do_tkill
```
**Symbols:**

```
ffffffff810923b0-ffffffff81092437: do_send_specific (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int do_send_specific(pid_t tgid, pid_t pid, int sig, struct siginfo *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81097340)
Location: kernel/signal.c:2874
Inline: False
Direct callers:
  - kernel/signal.c:do_rt_tgsigqueueinfo
  - kernel/signal.c:do_tkill
```
**Symbols:**

```
ffffffff81097340-ffffffff810973c7: do_send_specific (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int do_send_specific(pid_t tgid, pid_t pid, int sig, struct siginfo *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81094640)
Location: kernel/signal.c:2929
Inline: False
Direct callers:
  - kernel/signal.c:do_rt_tgsigqueueinfo
  - kernel/signal.c:do_tkill
```
**Symbols:**

```
ffffffff81094640-ffffffff810946c3: do_send_specific (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int do_send_specific(pid_t tgid, pid_t pid, int sig, struct siginfo *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8109b4e0)
Location: kernel/signal.c:2950
Inline: False
Direct callers:
  - kernel/signal.c:do_rt_tgsigqueueinfo
  - kernel/signal.c:do_tkill
```
**Symbols:**

```
ffffffff8109b4e0-ffffffff8109b563: do_send_specific (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int do_send_specific(pid_t tgid, pid_t pid, int sig, struct siginfo *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8109f4d0)
Location: kernel/signal.c:3182
Inline: False
Direct callers:
  - kernel/signal.c:do_rt_tgsigqueueinfo
  - kernel/signal.c:do_tkill
```
**Symbols:**

```
ffffffff8109f4d0-ffffffff8109f55c: do_send_specific (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int do_send_specific(pid_t tgid, pid_t pid, int sig, struct kernel_siginfo *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810a7780)
Location: kernel/signal.c:3510
Inline: False
Direct callers:
  - kernel/signal.c:do_rt_tgsigqueueinfo
  - kernel/signal.c:do_tkill
```
**Symbols:**

```
ffffffff810a7780-ffffffff810a780c: do_send_specific (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int do_send_specific(pid_t tgid, pid_t pid, int sig, struct kernel_siginfo *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810adf20)
Location: kernel/signal.c:3758
Inline: False
Direct callers:
  - kernel/signal.c:do_rt_tgsigqueueinfo
  - kernel/signal.c:do_tkill
```
**Symbols:**

```
ffffffff810adf20-ffffffff810adfa9: do_send_specific (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int do_send_specific(pid_t tgid, pid_t pid, int sig, struct kernel_siginfo *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b4530)
Location: kernel/signal.c:3766
Inline: False
Direct callers:
  - kernel/signal.c:do_rt_tgsigqueueinfo
  - kernel/signal.c:do_tkill
```
**Symbols:**

```
ffffffff810b4530-ffffffff810b45b9: do_send_specific (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int do_send_specific(pid_t tgid, pid_t pid, int sig, struct kernel_siginfo *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810bca60)
Location: kernel/signal.c:3784
Inline: False
Direct callers:
  - kernel/signal.c:__x32_compat_sys_rt_tgsigqueueinfo
  - kernel/signal.c:__x64_sys_rt_tgsigqueueinfo
  - kernel/signal.c:do_tkill
```
**Symbols:**

```
ffffffff810bca60-ffffffff810bcae9: do_send_specific (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int do_send_specific(pid_t tgid, pid_t pid, int sig, struct kernel_siginfo *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b7d70)
Location: kernel/signal.c:3805
Inline: False
Direct callers:
  - kernel/signal.c:__x32_compat_sys_rt_tgsigqueueinfo
  - kernel/signal.c:__x64_sys_rt_tgsigqueueinfo
  - kernel/signal.c:do_tkill
```
**Symbols:**

```
ffffffff810b7d70-ffffffff810b7e07: do_send_specific (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int do_send_specific(pid_t tgid, pid_t pid, int sig, struct kernel_siginfo *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b92d0)
Location: kernel/signal.c:3827
Inline: False
Direct callers:
  - kernel/signal.c:__x32_compat_sys_rt_tgsigqueueinfo
  - kernel/signal.c:__x64_sys_rt_tgsigqueueinfo
  - kernel/signal.c:do_tkill
```
**Symbols:**

```
ffffffff810b92d0-ffffffff810b9365: do_send_specific (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int do_send_specific(pid_t tgid, pid_t pid, int sig, struct kernel_siginfo *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810cb8e0)
Location: kernel/signal.c:3915
Inline: False
Direct callers:
  - kernel/signal.c:__x64_compat_sys_rt_tgsigqueueinfo
  - kernel/signal.c:__x64_sys_rt_tgsigqueueinfo
  - kernel/signal.c:do_tkill
```
**Symbols:**

```
ffffffff810cb8e0-ffffffff810cb975: do_send_specific (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int do_send_specific(pid_t tgid, pid_t pid, int sig, struct kernel_siginfo *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810e2990)
Location: kernel/signal.c:3898
Inline: False
Direct callers:
  - kernel/signal.c:do_rt_tgsigqueueinfo
  - kernel/signal.c:do_tkill
```
**Symbols:**

```
ffffffff810e2990-ffffffff810e2a4d: do_send_specific (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int do_send_specific(pid_t tgid, pid_t pid, int sig, struct kernel_siginfo *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81102de0)
Location: kernel/signal.c:3900
Inline: False
Direct callers:
  - kernel/signal.c:do_rt_tgsigqueueinfo
  - kernel/signal.c:do_tkill
```
**Symbols:**

```
ffffffff81102de0-ffffffff81102e9d: do_send_specific (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int do_send_specific(pid_t tgid, pid_t pid, int sig, struct kernel_siginfo *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8110f020)
Location: kernel/signal.c:3924
Inline: False
Direct callers:
  - kernel/signal.c:do_rt_tgsigqueueinfo
  - kernel/signal.c:do_tkill
```
**Symbols:**

```
ffffffff8110f020-ffffffff8110f0dd: do_send_specific (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int do_send_specific(pid_t tgid, pid_t pid, int sig, struct kernel_siginfo *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff811189a0)
Location: kernel/signal.c:3935
Inline: False
Direct callers:
  - kernel/signal.c:do_rt_tgsigqueueinfo
  - kernel/signal.c:do_tkill
```
**Symbols:**

```
ffffffff811189a0-ffffffff81118a5d: do_send_specific (STB_LOCAL)
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
int do_send_specific(pid_t tgid, pid_t pid, int sig, struct kernel_siginfo *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffff8000101105e0)
Location: kernel/signal.c:3766
Inline: False
Direct callers:
  - kernel/signal.c:do_rt_tgsigqueueinfo
  - kernel/signal.c:do_tkill
```
**Symbols:**

```
ffff8000101105e0-ffff800010110694: do_send_specific (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int do_send_specific(pid_t tgid, pid_t pid, int sig, struct kernel_siginfo *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c0367f94)
Location: kernel/signal.c:3766
Inline: False
Direct callers:
  - kernel/signal.c:__se_sys_rt_tgsigqueueinfo
  - kernel/signal.c:do_tkill
```
**Symbols:**

```
c0367f94-c0368034: do_send_specific (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int do_send_specific(pid_t tgid, pid_t pid, int sig, struct kernel_siginfo *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c000000000157d40)
Location: kernel/signal.c:3766
Inline: False
Direct callers:
  - kernel/signal.c:do_rt_tgsigqueueinfo
  - kernel/signal.c:do_rt_tgsigqueueinfo
  - kernel/signal.c:do_tkill
```
**Symbols:**

```
c000000000157d40-c000000000157e48: do_send_specific (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int do_send_specific(pid_t tgid, pid_t pid, int sig, struct kernel_siginfo *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffe0000d047a)
Location: kernel/signal.c:3766
Inline: False
Direct callers:
  - kernel/signal.c:__se_sys_rt_tgsigqueueinfo
  - kernel/signal.c:do_tkill
```
**Symbols:**

```
ffffffe0000d047a-ffffffe0000d0504: do_send_specific (STB_LOCAL)
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
int do_send_specific(pid_t tgid, pid_t pid, int sig, struct kernel_siginfo *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810ae8a0)
Location: kernel/signal.c:3766
Inline: False
Direct callers:
  - kernel/signal.c:do_rt_tgsigqueueinfo
  - kernel/signal.c:do_tkill
```
**Symbols:**

```
ffffffff810ae8a0-ffffffff810ae929: do_send_specific (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int do_send_specific(pid_t tgid, pid_t pid, int sig, struct kernel_siginfo *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8109d1f0)
Location: kernel/signal.c:3766
Inline: False
Direct callers:
  - kernel/signal.c:do_rt_tgsigqueueinfo
  - kernel/signal.c:do_tkill
```
**Symbols:**

```
ffffffff8109d1f0-ffffffff8109d279: do_send_specific (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int do_send_specific(pid_t tgid, pid_t pid, int sig, struct kernel_siginfo *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810ade00)
Location: kernel/signal.c:3766
Inline: False
Direct callers:
  - kernel/signal.c:do_rt_tgsigqueueinfo
  - kernel/signal.c:do_tkill
```
**Symbols:**

```
ffffffff810ade00-ffffffff810ade89: do_send_specific (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int do_send_specific(pid_t tgid, pid_t pid, int sig, struct kernel_siginfo *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b6060)
Location: kernel/signal.c:3766
Inline: False
Direct callers:
  - kernel/signal.c:do_rt_tgsigqueueinfo
  - kernel/signal.c:do_tkill
```
**Symbols:**

```
ffffffff810b6060-ffffffff810b6100: do_send_specific (STB_LOCAL)
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
<code>struct siginfo *info</code> ➡️ <code>struct kernel_siginfo *info</code>
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
