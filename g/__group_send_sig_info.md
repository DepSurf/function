# Function: <code>__group_send_sig_info</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int __group_send_sig_info(int sig, struct siginfo *info, struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8108e9e6)
Location: kernel/signal.c:1123
Inline: True
Inline callers:
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
Direct callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - drivers/tty/tty_io.c:__tty_hangup
  - drivers/tty/tty_io.c:__tty_hangup
```
**Symbols:**

```
ffffffff8108f000-ffffffff8108f015: __group_send_sig_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int __group_send_sig_info(int sig, struct siginfo *info, struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81091a66)
Location: kernel/signal.c:1123
Inline: True
Inline callers:
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
Direct callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - drivers/tty/tty_io.c:__tty_hangup
  - drivers/tty/tty_io.c:__tty_hangup
```
**Symbols:**

```
ffffffff81092070-ffffffff81092085: __group_send_sig_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int __group_send_sig_info(int sig, struct siginfo *info, struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810969f6)
Location: kernel/signal.c:1129
Inline: True
Inline callers:
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
Direct callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - drivers/tty/tty_io.c:__tty_hangup
  - drivers/tty/tty_io.c:__tty_hangup
```
**Symbols:**

```
ffffffff81097000-ffffffff81097015: __group_send_sig_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int __group_send_sig_info(int sig, struct siginfo *info, struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81093d08)
Location: kernel/signal.c:1143
Inline: True
Inline callers:
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
Direct callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
```
**Symbols:**

```
ffffffff81094300-ffffffff81094315: __group_send_sig_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int __group_send_sig_info(int sig, struct siginfo *info, struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8109abef)
Location: kernel/signal.c:1144
Inline: True
Inline callers:
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
Direct callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
```
**Symbols:**

```
ffffffff8109b1a0-ffffffff8109b1b5: __group_send_sig_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int __group_send_sig_info(int sig, struct siginfo *info, struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8109eb82)
Location: kernel/signal.c:1152
Inline: True
Inline callers:
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
Direct callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
```
**Symbols:**

```
ffffffff8109f110-ffffffff8109f125: __group_send_sig_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int __group_send_sig_info(int sig, struct kernel_siginfo *info, struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810a6e68)
Location: kernel/signal.c:1241
Inline: True
Inline callers:
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
Direct callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
```
**Symbols:**

```
ffffffff810a73d0-ffffffff810a73e5: __group_send_sig_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int __group_send_sig_info(int sig, struct kernel_siginfo *info, struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810acf1c)
Location: kernel/signal.c:1273
Inline: True
Inline callers:
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
Direct callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
```
**Symbols:**

```
ffffffff810acb00-ffffffff810acb15: __group_send_sig_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int __group_send_sig_info(int sig, struct kernel_siginfo *info, struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b353c)
Location: kernel/signal.c:1278
Inline: True
Inline callers:
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
Direct callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
```
**Symbols:**

```
ffffffff810b3110-ffffffff810b3125: __group_send_sig_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int __group_send_sig_info(int sig, struct kernel_siginfo *info, struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810bbf64)
Location: kernel/signal.c:1278
Inline: True
Inline callers:
  - kernel/signal.c:do_notify_parent_cldstop
Direct callers:
  - kernel/time/posix-cpu-timers.c:check_process_timers
  - kernel/time/posix-cpu-timers.c:check_process_timers
  - kernel/time/posix-cpu-timers.c:check_cpu_itimer
  - kernel/time/posix-cpu-timers.c:check_thread_timers
  - kernel/time/posix-cpu-timers.c:check_thread_timers
  - kernel/time/posix-cpu-timers.c:check_thread_timers
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
```
**Symbols:**

```
ffffffff810bbde0-ffffffff810bbdf5: __group_send_sig_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int __group_send_sig_info(int sig, struct kernel_siginfo *info, struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b724c)
Location: kernel/signal.c:1279
Inline: True
Inline callers:
  - kernel/signal.c:do_notify_parent_cldstop
Direct callers:
  - kernel/time/posix-cpu-timers.c:check_process_timers
  - kernel/time/posix-cpu-timers.c:check_process_timers
  - kernel/time/posix-cpu-timers.c:check_cpu_itimer
  - kernel/time/posix-cpu-timers.c:check_thread_timers
  - kernel/time/posix-cpu-timers.c:check_thread_timers
  - kernel/time/posix-cpu-timers.c:check_thread_timers
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
```
**Symbols:**

```
ffffffff810b70b0-ffffffff810b70c5: __group_send_sig_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int __group_send_sig_info(int sig, struct kernel_siginfo *info, struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b8847)
Location: kernel/signal.c:1281
Inline: True
Inline callers:
  - kernel/signal.c:do_notify_parent_cldstop
Direct callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timers_work
  - kernel/time/posix-cpu-timers.c:posix_cpu_timers_work
  - kernel/time/posix-cpu-timers.c:posix_cpu_timers_work
  - kernel/time/posix-cpu-timers.c:check_process_timers
  - kernel/time/posix-cpu-timers.c:check_process_timers
  - kernel/time/posix-cpu-timers.c:check_cpu_itimer
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
```
**Symbols:**

```
ffffffff810b86b0-ffffffff810b86c5: __group_send_sig_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int __group_send_sig_info(int sig, struct kernel_siginfo *info, struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810cad37)
Location: kernel/signal.c:1282
Inline: True
Inline callers:
  - kernel/signal.c:do_notify_parent_cldstop
Direct callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timers_work
  - kernel/time/posix-cpu-timers.c:posix_cpu_timers_work
  - kernel/time/posix-cpu-timers.c:posix_cpu_timers_work
  - kernel/time/posix-cpu-timers.c:check_process_timers
  - kernel/time/posix-cpu-timers.c:check_process_timers
  - kernel/time/posix-cpu-timers.c:check_cpu_itimer
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
```
**Symbols:**

```
ffffffff810caba0-ffffffff810cabb5: __group_send_sig_info (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int __group_send_sig_info(int sig, struct kernel_siginfo *info, struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffff80001010f3b8)
Location: kernel/signal.c:1278
Inline: True
Inline callers:
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
Direct callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
```
**Symbols:**

```
ffff80001010ef60-ffff80001010efa8: __group_send_sig_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int __group_send_sig_info(int sig, struct kernel_siginfo *info, struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c03670b0)
Location: kernel/signal.c:1278
Inline: True
Inline callers:
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
Direct callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
```
**Symbols:**

```
c0366cac-c0366ccc: __group_send_sig_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int __group_send_sig_info(int sig, struct kernel_siginfo *info, struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c0000000001568b0)
Location: kernel/signal.c:1278
Inline: True
Inline callers:
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
Direct callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
```
**Symbols:**

```
c000000000156400-c000000000156418: __group_send_sig_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int __group_send_sig_info(int sig, struct kernel_siginfo *info, struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffe0000cf8e0)
Location: kernel/signal.c:1278
Inline: True
Inline callers:
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
Direct callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
```
**Symbols:**

```
ffffffe0000cf5b0-ffffffe0000cf5ec: __group_send_sig_info (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int __group_send_sig_info(int sig, struct kernel_siginfo *info, struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810ad8ac)
Location: kernel/signal.c:1278
Inline: True
Inline callers:
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
Direct callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
```
**Symbols:**

```
ffffffff810ad480-ffffffff810ad495: __group_send_sig_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int __group_send_sig_info(int sig, struct kernel_siginfo *info, struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8109c231)
Location: kernel/signal.c:1278
Inline: True
Inline callers:
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
Direct callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
```
**Symbols:**

```
ffffffff8109be00-ffffffff8109be15: __group_send_sig_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int __group_send_sig_info(int sig, struct kernel_siginfo *info, struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810ace0c)
Location: kernel/signal.c:1278
Inline: True
Inline callers:
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
Direct callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
```
**Symbols:**

```
ffffffff810ac9e0-ffffffff810ac9f5: __group_send_sig_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int __group_send_sig_info(int sig, struct kernel_siginfo *info, struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b4fe1)
Location: kernel/signal.c:1278
Inline: True
Inline callers:
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
Direct callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
```
**Symbols:**

```
ffffffff810b4b70-ffffffff810b4b85: __group_send_sig_info (STB_GLOBAL)
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
