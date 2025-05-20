# Function: <code>kill_pid_info</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int kill_pid_info(int sig, struct siginfo *info, struct pid *pid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8108f870)
Location: kernel/signal.c:1288
Inline: False
Direct callers:
  - kernel/signal.c:kill_pid
  - kernel/signal.c:SYSC_kill
  - kernel/signal.c:do_rt_sigqueueinfo
  - kernel/time/itimer.c:it_real_fn
  - ipc/mqueue.c:__do_notify
```
**Symbols:**

```
ffffffff8108f870-ffffffff8108f8bc: kill_pid_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int kill_pid_info(int sig, struct siginfo *info, struct pid *pid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810928f0)
Location: kernel/signal.c:1288
Inline: False
Direct callers:
  - kernel/signal.c:do_rt_sigqueueinfo
  - kernel/signal.c:SYSC_kill
  - kernel/signal.c:kill_pid
  - kernel/time/itimer.c:it_real_fn
  - ipc/mqueue.c:__do_notify
```
**Symbols:**

```
ffffffff810928f0-ffffffff8109293c: kill_pid_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int kill_pid_info(int sig, struct siginfo *info, struct pid *pid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81097880)
Location: kernel/signal.c:1294
Inline: False
Direct callers:
  - kernel/signal.c:do_rt_sigqueueinfo
  - kernel/signal.c:SYSC_kill
  - kernel/signal.c:kill_pid
  - kernel/time/itimer.c:it_real_fn
  - ipc/mqueue.c:__do_notify
```
**Symbols:**

```
ffffffff81097880-ffffffff810978cc: kill_pid_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int kill_pid_info(int sig, struct siginfo *info, struct pid *pid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81094bb0)
Location: kernel/signal.c:1312
Inline: False
Direct callers:
  - kernel/signal.c:do_rt_sigqueueinfo
  - kernel/signal.c:SYSC_kill
  - kernel/signal.c:kill_pid
  - kernel/time/itimer.c:it_real_fn
  - ipc/mqueue.c:__do_notify
```
**Symbols:**

```
ffffffff81094bb0-ffffffff81094bfc: kill_pid_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int kill_pid_info(int sig, struct siginfo *info, struct pid *pid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8109ba50)
Location: kernel/signal.c:1313
Inline: False
Direct callers:
  - kernel/signal.c:do_rt_sigqueueinfo
  - kernel/signal.c:SYSC_kill
  - kernel/signal.c:kill_pid
  - kernel/time/itimer.c:it_real_fn
  - ipc/mqueue.c:__do_notify
```
**Symbols:**

```
ffffffff8109ba50-ffffffff8109ba9c: kill_pid_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int kill_pid_info(int sig, struct siginfo *info, struct pid *pid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8109fab0)
Location: kernel/signal.c:1311
Inline: False
Direct callers:
  - kernel/signal.c:do_rt_sigqueueinfo
  - kernel/signal.c:__do_sys_kill
  - kernel/signal.c:kill_pid
  - kernel/time/itimer.c:it_real_fn
  - ipc/mqueue.c:__do_notify
```
**Symbols:**

```
ffffffff8109fab0-ffffffff8109fafc: kill_pid_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int kill_pid_info(int sig, struct kernel_siginfo *info, struct pid *pid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810a7d60)
Location: kernel/signal.c:1395
Inline: False
Direct callers:
  - kernel/signal.c:do_rt_sigqueueinfo
  - kernel/signal.c:kill_pid
  - kernel/signal.c:kill_something_info
  - kernel/time/itimer.c:it_real_fn
  - ipc/mqueue.c:__do_notify
```
**Symbols:**

```
ffffffff810a7d60-ffffffff810a7db1: kill_pid_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int kill_pid_info(int sig, struct kernel_siginfo *info, struct pid *pid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810ad8d0)
Location: kernel/signal.c:1433
Inline: False
Direct callers:
  - kernel/signal.c:do_rt_sigqueueinfo
  - kernel/signal.c:__ia32_sys_pidfd_send_signal
  - kernel/signal.c:__ia32_sys_pidfd_send_signal
  - kernel/signal.c:__x64_sys_pidfd_send_signal
  - kernel/signal.c:__x64_sys_pidfd_send_signal
  - kernel/signal.c:kill_pid
  - kernel/signal.c:kill_something_info
  - kernel/time/itimer.c:it_real_fn
  - ipc/mqueue.c:__do_notify
```
**Symbols:**

```
ffffffff810ad8d0-ffffffff810ad92f: kill_pid_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int kill_pid_info(int sig, struct kernel_siginfo *info, struct pid *pid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b3ef0)
Location: kernel/signal.c:1438
Inline: False
Direct callers:
  - kernel/signal.c:do_rt_sigqueueinfo
  - kernel/signal.c:__ia32_sys_pidfd_send_signal
  - kernel/signal.c:__ia32_sys_pidfd_send_signal
  - kernel/signal.c:__x64_sys_pidfd_send_signal
  - kernel/signal.c:__x64_sys_pidfd_send_signal
  - kernel/signal.c:kill_pid
  - kernel/signal.c:kill_something_info
  - kernel/time/itimer.c:it_real_fn
  - ipc/mqueue.c:__do_notify
```
**Symbols:**

```
ffffffff810b3ef0-ffffffff810b3f4f: kill_pid_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int kill_pid_info(int sig, struct kernel_siginfo *info, struct pid *pid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810bd326)
Location: kernel/signal.c:1438
Inline: True
Inline callers:
  - kernel/signal.c:kill_pid
Direct callers:
  - kernel/signal.c:do_rt_sigqueueinfo
  - kernel/signal.c:__do_sys_pidfd_send_signal
  - kernel/signal.c:__do_sys_pidfd_send_signal
  - kernel/signal.c:kill_something_info
  - kernel/time/itimer.c:it_real_fn
```
**Symbols:**

```
ffffffff810bd070-ffffffff810bd0e8: kill_pid_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int kill_pid_info(int sig, struct kernel_siginfo *info, struct pid *pid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b83a0)
Location: kernel/signal.c:1439
Inline: False
Direct callers:
  - kernel/signal.c:do_rt_sigqueueinfo
  - kernel/signal.c:__do_sys_pidfd_send_signal
  - kernel/signal.c:__do_sys_pidfd_send_signal
  - kernel/signal.c:kill_pid
  - kernel/signal.c:kill_something_info
  - kernel/time/itimer.c:it_real_fn
```
**Symbols:**

```
ffffffff810b83a0-ffffffff810b843f: kill_pid_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int kill_pid_info(int sig, struct kernel_siginfo *info, struct pid *pid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b9920)
Location: kernel/signal.c:1441
Inline: False
Direct callers:
  - kernel/signal.c:do_rt_sigqueueinfo
  - kernel/signal.c:__do_sys_pidfd_send_signal
  - kernel/signal.c:__do_sys_pidfd_send_signal
  - kernel/signal.c:kill_pid
  - kernel/signal.c:kill_something_info
  - kernel/time/itimer.c:it_real_fn
```
**Symbols:**

```
ffffffff810b9920-ffffffff810b99bf: kill_pid_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int kill_pid_info(int sig, struct kernel_siginfo *info, struct pid *pid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810cbf30)
Location: kernel/signal.c:1467
Inline: False
Direct callers:
  - kernel/signal.c:do_rt_sigqueueinfo
  - kernel/signal.c:__do_sys_pidfd_send_signal
  - kernel/signal.c:__do_sys_pidfd_send_signal
  - kernel/signal.c:kill_pid
  - kernel/signal.c:kill_something_info
  - kernel/time/itimer.c:it_real_fn
```
**Symbols:**

```
ffffffff810cbf30-ffffffff810cbfcf: kill_pid_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int kill_pid_info(int sig, struct kernel_siginfo *info, struct pid *pid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810e33a0)
Location: kernel/signal.c:1468
Inline: True
Inline callers:
  - kernel/signal.c:kill_pid
Direct callers:
  - kernel/signal.c:do_rt_sigqueueinfo
  - kernel/signal.c:__do_sys_pidfd_send_signal
  - kernel/signal.c:kill_something_info
  - kernel/time/itimer.c:it_real_fn
```
**Symbols:**

```
ffffffff810e3020-ffffffff810e30e8: kill_pid_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int kill_pid_info(int sig, struct kernel_siginfo *info, struct pid *pid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81103900)
Location: kernel/signal.c:1469
Inline: True
Inline callers:
  - kernel/signal.c:kill_pid
Direct callers:
  - kernel/signal.c:do_rt_sigqueueinfo
  - kernel/signal.c:__do_sys_pidfd_send_signal
  - kernel/signal.c:kill_something_info
  - kernel/time/itimer.c:it_real_fn
```
**Symbols:**

```
ffffffff81103530-ffffffff811035f8: kill_pid_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int kill_pid_info(int sig, struct kernel_siginfo *info, struct pid *pid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8110fb40)
Location: kernel/signal.c:1475
Inline: True
Inline callers:
  - kernel/signal.c:kill_pid
Direct callers:
  - kernel/signal.c:do_rt_sigqueueinfo
  - kernel/signal.c:__do_sys_pidfd_send_signal
  - kernel/signal.c:kill_something_info
  - kernel/time/itimer.c:it_real_fn
```
**Symbols:**

```
ffffffff8110f770-ffffffff8110f838: kill_pid_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int kill_pid_info(int sig, struct kernel_siginfo *info, struct pid *pid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff811194b0)
Location: kernel/signal.c:1481
Inline: True
Inline callers:
  - kernel/signal.c:kill_pid
Direct callers:
  - kernel/signal.c:do_rt_sigqueueinfo
  - kernel/signal.c:__do_sys_pidfd_send_signal
  - kernel/signal.c:kill_something_info
  - kernel/time/itimer.c:it_real_fn
```
**Symbols:**

```
ffffffff811190e0-ffffffff811191a8: kill_pid_info (STB_GLOBAL)
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
int kill_pid_info(int sig, struct kernel_siginfo *info, struct pid *pid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffff80001010ffb8)
Location: kernel/signal.c:1438
Inline: False
Direct callers:
  - kernel/signal.c:do_rt_sigqueueinfo
  - kernel/signal.c:__arm64_sys_pidfd_send_signal
  - kernel/signal.c:__arm64_sys_pidfd_send_signal
  - kernel/signal.c:__arm64_sys_kill
  - kernel/signal.c:kill_pid
  - kernel/time/itimer.c:it_real_fn
  - kernel/time/itimer.c:it_real_fn
  - ipc/mqueue.c:__do_notify
```
**Symbols:**

```
ffff80001010ffb8-ffff800010110038: kill_pid_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int kill_pid_info(int sig, struct kernel_siginfo *info, struct pid *pid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c0367d24)
Location: kernel/signal.c:1438
Inline: False
Direct callers:
  - kernel/signal.c:__se_sys_rt_sigqueueinfo
  - kernel/signal.c:__se_sys_pidfd_send_signal
  - kernel/signal.c:__se_sys_kill
  - kernel/signal.c:kill_pid
  - kernel/time/itimer.c:it_real_fn
  - ipc/mqueue.c:do_mq_timedsend
```
**Symbols:**

```
c0367d24-c0367d9c: kill_pid_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int kill_pid_info(int sig, struct kernel_siginfo *info, struct pid *pid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c0000000001576d0)
Location: kernel/signal.c:1438
Inline: False
Direct callers:
  - kernel/signal.c:do_rt_sigqueueinfo
  - kernel/signal.c:__se_sys_pidfd_send_signal
  - kernel/signal.c:__se_sys_pidfd_send_signal
  - kernel/signal.c:__se_sys_kill
  - kernel/signal.c:kill_pid
  - kernel/time/itimer.c:it_real_fn
  - kernel/time/itimer.c:it_real_fn
  - ipc/mqueue.c:__do_notify
```
**Symbols:**

```
c0000000001576d0-c000000000157780: kill_pid_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int kill_pid_info(int sig, struct kernel_siginfo *info, struct pid *pid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffe0000d0262)
Location: kernel/signal.c:1438
Inline: False
Direct callers:
  - kernel/signal.c:__se_sys_rt_sigqueueinfo
  - kernel/signal.c:__se_sys_pidfd_send_signal
  - kernel/signal.c:__se_sys_pidfd_send_signal
  - kernel/signal.c:__se_sys_kill
  - kernel/signal.c:kill_pid
  - kernel/time/itimer.c:it_real_fn
  - ipc/mqueue.c:__do_notify
```
**Symbols:**

```
ffffffe0000d0262-ffffffe0000d02c8: kill_pid_info (STB_GLOBAL)
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
int kill_pid_info(int sig, struct kernel_siginfo *info, struct pid *pid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810ae260)
Location: kernel/signal.c:1438
Inline: False
Direct callers:
  - kernel/signal.c:do_rt_sigqueueinfo
  - kernel/signal.c:__ia32_sys_pidfd_send_signal
  - kernel/signal.c:__ia32_sys_pidfd_send_signal
  - kernel/signal.c:__x64_sys_pidfd_send_signal
  - kernel/signal.c:__x64_sys_pidfd_send_signal
  - kernel/signal.c:kill_pid
  - kernel/signal.c:kill_something_info
  - kernel/time/itimer.c:it_real_fn
  - ipc/mqueue.c:__do_notify
```
**Symbols:**

```
ffffffff810ae260-ffffffff810ae2bf: kill_pid_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int kill_pid_info(int sig, struct kernel_siginfo *info, struct pid *pid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8109cbb0)
Location: kernel/signal.c:1438
Inline: False
Direct callers:
  - kernel/signal.c:do_rt_sigqueueinfo
  - kernel/signal.c:__ia32_sys_pidfd_send_signal
  - kernel/signal.c:__ia32_sys_pidfd_send_signal
  - kernel/signal.c:__x64_sys_pidfd_send_signal
  - kernel/signal.c:__x64_sys_pidfd_send_signal
  - kernel/signal.c:kill_pid
  - kernel/signal.c:kill_something_info
  - kernel/time/itimer.c:it_real_fn
  - ipc/mqueue.c:__do_notify
```
**Symbols:**

```
ffffffff8109cbb0-ffffffff8109cc0f: kill_pid_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int kill_pid_info(int sig, struct kernel_siginfo *info, struct pid *pid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810ad7c0)
Location: kernel/signal.c:1438
Inline: False
Direct callers:
  - kernel/signal.c:do_rt_sigqueueinfo
  - kernel/signal.c:__ia32_sys_pidfd_send_signal
  - kernel/signal.c:__ia32_sys_pidfd_send_signal
  - kernel/signal.c:__x64_sys_pidfd_send_signal
  - kernel/signal.c:__x64_sys_pidfd_send_signal
  - kernel/signal.c:kill_pid
  - kernel/signal.c:kill_something_info
  - kernel/time/itimer.c:it_real_fn
  - ipc/mqueue.c:__do_notify
```
**Symbols:**

```
ffffffff810ad7c0-ffffffff810ad81f: kill_pid_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int kill_pid_info(int sig, struct kernel_siginfo *info, struct pid *pid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b59d0)
Location: kernel/signal.c:1438
Inline: False
Direct callers:
  - kernel/signal.c:do_rt_sigqueueinfo
  - kernel/signal.c:__ia32_sys_pidfd_send_signal
  - kernel/signal.c:__ia32_sys_pidfd_send_signal
  - kernel/signal.c:__x64_sys_pidfd_send_signal
  - kernel/signal.c:__x64_sys_pidfd_send_signal
  - kernel/signal.c:kill_pid
  - kernel/signal.c:kill_something_info
  - kernel/time/itimer.c:it_real_fn
  - ipc/mqueue.c:__do_notify
```
**Symbols:**

```
ffffffff810b59d0-ffffffff810b5a41: kill_pid_info (STB_GLOBAL)
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
