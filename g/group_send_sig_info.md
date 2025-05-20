# Function: <code>group_send_sig_info</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int group_send_sig_info(int sig, struct siginfo *info, struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8108f760)
Location: kernel/signal.c:1254
Inline: True
Direct callers:
  - kernel/exit.c:do_exit
  - kernel/signal.c:__kill_pgrp_info
  - kernel/signal.c:kill_pid_info
  - kernel/signal.c:SYSC_kill
```
**Symbols:**

```
ffffffff8108f760-ffffffff8108f79c: group_send_sig_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int group_send_sig_info(int sig, struct siginfo *info, struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810927e0)
Location: kernel/signal.c:1254
Inline: True
Direct callers:
  - kernel/exit.c:do_exit
  - kernel/signal.c:SYSC_kill
  - kernel/signal.c:kill_pid_info
  - kernel/signal.c:__kill_pgrp_info
```
**Symbols:**

```
ffffffff810927e0-ffffffff8109281c: group_send_sig_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int group_send_sig_info(int sig, struct siginfo *info, struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81097770)
Location: kernel/signal.c:1260
Inline: True
Direct callers:
  - kernel/exit.c:do_exit
  - kernel/signal.c:SYSC_kill
  - kernel/signal.c:kill_pid_info
  - kernel/signal.c:__kill_pgrp_info
```
**Symbols:**

```
ffffffff81097770-ffffffff810977ac: group_send_sig_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int group_send_sig_info(int sig, struct siginfo *info, struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81094a90)
Location: kernel/signal.c:1278
Inline: True
Direct callers:
  - kernel/exit.c:do_exit
  - kernel/signal.c:SYSC_kill
  - kernel/signal.c:kill_pid_info
  - kernel/signal.c:__kill_pgrp_info
```
**Symbols:**

```
ffffffff81094a90-ffffffff81094acc: group_send_sig_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int group_send_sig_info(int sig, struct siginfo *info, struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8109b930)
Location: kernel/signal.c:1279
Inline: True
Direct callers:
  - kernel/exit.c:do_exit
  - kernel/signal.c:SYSC_kill
  - kernel/signal.c:kill_pid_info
  - kernel/signal.c:__kill_pgrp_info
```
**Symbols:**

```
ffffffff8109b930-ffffffff8109b96c: group_send_sig_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int group_send_sig_info(int sig, struct siginfo *info, struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8109f980)
Location: kernel/signal.c:1277
Inline: True
Direct callers:
  - kernel/exit.c:do_exit
  - kernel/signal.c:__do_sys_kill
  - kernel/signal.c:kill_pid_info
  - kernel/signal.c:__kill_pgrp_info
```
**Symbols:**

```
ffffffff8109f980-ffffffff8109f9c3: group_send_sig_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int group_send_sig_info(int sig, struct kernel_siginfo *info, struct task_struct *p, enum pid_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810a7c30)
Location: kernel/signal.c:1360
Inline: False
Direct callers:
  - kernel/exit.c:do_exit
  - kernel/signal.c:kill_something_info
  - kernel/signal.c:kill_pid_info
  - kernel/signal.c:__kill_pgrp_info
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
**Symbols:**

```
ffffffff810a7c30-ffffffff810a7c7a: group_send_sig_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int group_send_sig_info(int sig, struct kernel_siginfo *info, struct task_struct *p, enum pid_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810ad7a0)
Location: kernel/signal.c:1398
Inline: False
Direct callers:
  - kernel/exit.c:do_exit
  - kernel/signal.c:kill_something_info
  - kernel/signal.c:kill_pid_info
  - kernel/signal.c:__kill_pgrp_info
  - kernel/pid_namespace.c:zap_pid_ns_processes
  - kernel/trace/bpf_trace.c:bpf_send_signal
  - kernel/trace/bpf_trace.c:do_bpf_send_signal
```
**Symbols:**

```
ffffffff810ad7a0-ffffffff810ad7f0: group_send_sig_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int group_send_sig_info(int sig, struct kernel_siginfo *info, struct task_struct *p, enum pid_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b3dc0)
Location: kernel/signal.c:1403
Inline: False
Direct callers:
  - kernel/exit.c:do_exit
  - kernel/signal.c:kill_something_info
  - kernel/signal.c:kill_pid_info
  - kernel/signal.c:__kill_pgrp_info
  - kernel/pid_namespace.c:zap_pid_ns_processes
  - kernel/trace/bpf_trace.c:bpf_send_signal
  - kernel/trace/bpf_trace.c:do_bpf_send_signal
```
**Symbols:**

```
ffffffff810b3dc0-ffffffff810b3e10: group_send_sig_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int group_send_sig_info(int sig, struct kernel_siginfo *info, struct task_struct *p, enum pid_type type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810bd341)
Location: kernel/signal.c:1403
Inline: True
Inline callers:
  - kernel/signal.c:kill_pid
  - kernel/signal.c:kill_something_info
  - kernel/signal.c:__kill_pgrp_info
Direct callers:
  - kernel/exit.c:forget_original_parent
  - kernel/pid_namespace.c:zap_pid_ns_processes
  - kernel/trace/bpf_trace.c:bpf_send_signal_common
  - kernel/trace/bpf_trace.c:do_bpf_send_signal
```
**Symbols:**

```
ffffffff810bc8a0-ffffffff810bc8f0: group_send_sig_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int group_send_sig_info(int sig, struct kernel_siginfo *info, struct task_struct *p, enum pid_type type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b8779)
Location: kernel/signal.c:1404
Inline: True
Inline callers:
  - kernel/signal.c:kill_something_info
  - kernel/signal.c:kill_pid_info
  - kernel/signal.c:__kill_pgrp_info
Direct callers:
  - kernel/exit.c:forget_original_parent
  - kernel/pid_namespace.c:zap_pid_ns_processes
  - kernel/trace/bpf_trace.c:bpf_send_signal_common
  - kernel/trace/bpf_trace.c:do_bpf_send_signal
```
**Symbols:**

```
ffffffff810b7b90-ffffffff810b7bf5: group_send_sig_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int group_send_sig_info(int sig, struct kernel_siginfo *info, struct task_struct *p, enum pid_type type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b9cf9)
Location: kernel/signal.c:1406
Inline: True
Inline callers:
  - kernel/signal.c:kill_something_info
  - kernel/signal.c:kill_pid_info
  - kernel/signal.c:__kill_pgrp_info
Direct callers:
  - kernel/exit.c:forget_original_parent
  - kernel/pid_namespace.c:zap_pid_ns_processes
  - kernel/trace/bpf_trace.c:bpf_send_signal_common
  - kernel/trace/bpf_trace.c:do_bpf_send_signal
```
**Symbols:**

```
ffffffff810b90f0-ffffffff810b9155: group_send_sig_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int group_send_sig_info(int sig, struct kernel_siginfo *info, struct task_struct *p, enum pid_type type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810cc309)
Location: kernel/signal.c:1432
Inline: True
Inline callers:
  - kernel/signal.c:kill_something_info
  - kernel/signal.c:kill_pid_info
  - kernel/signal.c:__kill_pgrp_info
Direct callers:
  - kernel/exit.c:forget_original_parent
  - kernel/pid_namespace.c:zap_pid_ns_processes
  - kernel/trace/bpf_trace.c:bpf_send_signal_common
  - kernel/trace/bpf_trace.c:do_bpf_send_signal
```
**Symbols:**

```
ffffffff810cb680-ffffffff810cb6e5: group_send_sig_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int group_send_sig_info(int sig, struct kernel_siginfo *info, struct task_struct *p, enum pid_type type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810e33b8)
Location: kernel/signal.c:1433
Inline: True
Inline callers:
  - kernel/signal.c:kill_pid
  - kernel/signal.c:kill_something_info
  - kernel/signal.c:__kill_pgrp_info
Direct callers:
  - kernel/exit.c:forget_original_parent
  - kernel/pid_namespace.c:zap_pid_ns_processes
  - kernel/trace/bpf_trace.c:bpf_send_signal_common
  - kernel/trace/bpf_trace.c:do_bpf_send_signal
  - drivers/tty/tty_io.c:__do_SAK
  - drivers/tty/tty_io.c:__do_SAK
  - drivers/tty/tty_io.c:__do_SAK
```
**Symbols:**

```
ffffffff810e25e0-ffffffff810e2666: group_send_sig_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int group_send_sig_info(int sig, struct kernel_siginfo *info, struct task_struct *p, enum pid_type type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81103918)
Location: kernel/signal.c:1434
Inline: True
Inline callers:
  - kernel/signal.c:kill_pid
  - kernel/signal.c:kill_something_info
  - kernel/signal.c:__kill_pgrp_info
Direct callers:
  - kernel/exit.c:forget_original_parent
  - kernel/pid_namespace.c:zap_pid_ns_processes
  - kernel/trace/bpf_trace.c:bpf_send_signal_common
  - kernel/trace/bpf_trace.c:do_bpf_send_signal
  - drivers/tty/tty_io.c:__do_SAK
  - drivers/tty/tty_io.c:__do_SAK
  - drivers/tty/tty_io.c:__do_SAK
```
**Symbols:**

```
ffffffff811029c0-ffffffff81102a46: group_send_sig_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int group_send_sig_info(int sig, struct kernel_siginfo *info, struct task_struct *p, enum pid_type type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8110fb58)
Location: kernel/signal.c:1440
Inline: True
Inline callers:
  - kernel/signal.c:kill_pid
  - kernel/signal.c:kill_something_info
  - kernel/signal.c:__kill_pgrp_info
Direct callers:
  - kernel/exit.c:forget_original_parent
  - kernel/pid_namespace.c:zap_pid_ns_processes
  - kernel/trace/bpf_trace.c:bpf_send_signal_common
  - kernel/trace/bpf_trace.c:do_bpf_send_signal
  - drivers/tty/tty_io.c:__do_SAK
  - drivers/tty/tty_io.c:__do_SAK
  - drivers/tty/tty_io.c:__do_SAK
```
**Symbols:**

```
ffffffff8110ec00-ffffffff8110ec86: group_send_sig_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int group_send_sig_info(int sig, struct kernel_siginfo *info, struct task_struct *p, enum pid_type type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff811194c8)
Location: kernel/signal.c:1441
Inline: True
Inline callers:
  - kernel/signal.c:kill_pid
  - kernel/signal.c:kill_something_info
  - kernel/signal.c:__kill_pgrp_info
Direct callers:
  - kernel/exit.c:forget_original_parent
  - kernel/pid_namespace.c:zap_pid_ns_processes
  - kernel/trace/bpf_trace.c:bpf_send_signal_common
  - kernel/trace/bpf_trace.c:do_bpf_send_signal
  - drivers/tty/tty_io.c:__do_SAK
  - drivers/tty/tty_io.c:__do_SAK
  - drivers/tty/tty_io.c:__do_SAK
```
**Symbols:**

```
ffffffff81118580-ffffffff81118606: group_send_sig_info (STB_GLOBAL)
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
int group_send_sig_info(int sig, struct kernel_siginfo *info, struct task_struct *p, enum pid_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffff80001010fde8)
Location: kernel/signal.c:1403
Inline: False
Direct callers:
  - kernel/exit.c:do_exit
  - kernel/signal.c:__arm64_sys_kill
  - kernel/signal.c:kill_pid_info
  - kernel/signal.c:__kill_pgrp_info
  - kernel/pid_namespace.c:zap_pid_ns_processes
  - kernel/trace/bpf_trace.c:do_bpf_send_signal
```
**Symbols:**

```
ffff80001010fde8-ffff80001010fe60: group_send_sig_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int group_send_sig_info(int sig, struct kernel_siginfo *info, struct task_struct *p, enum pid_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c0367bc8)
Location: kernel/signal.c:1403
Inline: False
Direct callers:
  - kernel/exit.c:do_exit
  - kernel/signal.c:__se_sys_kill
  - kernel/signal.c:kill_pid_info
  - kernel/signal.c:__kill_pgrp_info
  - kernel/pid_namespace.c:zap_pid_ns_processes
  - kernel/trace/bpf_trace.c:bpf_send_signal
  - kernel/trace/bpf_trace.c:do_bpf_send_signal
```
**Symbols:**

```
c0367bc8-c0367c20: group_send_sig_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int group_send_sig_info(int sig, struct kernel_siginfo *info, struct task_struct *p, enum pid_type type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c0000000001574c0)
Location: kernel/signal.c:1403
Inline: True
Direct callers:
  - kernel/exit.c:do_exit
  - kernel/signal.c:__se_sys_kill
  - kernel/signal.c:kill_pid_info
  - kernel/signal.c:__kill_pgrp_info
  - kernel/pid_namespace.c:zap_pid_ns_processes
  - kernel/trace/bpf_trace.c:do_bpf_send_signal
```
**Symbols:**

```
c0000000001574c0-c000000000157560: group_send_sig_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int group_send_sig_info(int sig, struct kernel_siginfo *info, struct task_struct *p, enum pid_type type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffe0000d0126)
Location: kernel/signal.c:1403
Inline: True
Direct callers:
  - kernel/exit.c:do_exit
  - kernel/signal.c:__se_sys_kill
  - kernel/signal.c:kill_pid_info
  - kernel/signal.c:__kill_pgrp_info
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
**Symbols:**

```
ffffffe0000d0126-ffffffe0000d018a: group_send_sig_info (STB_GLOBAL)
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
int group_send_sig_info(int sig, struct kernel_siginfo *info, struct task_struct *p, enum pid_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810ae130)
Location: kernel/signal.c:1403
Inline: False
Direct callers:
  - kernel/exit.c:do_exit
  - kernel/signal.c:kill_something_info
  - kernel/signal.c:kill_pid_info
  - kernel/signal.c:__kill_pgrp_info
  - kernel/pid_namespace.c:zap_pid_ns_processes
  - kernel/trace/bpf_trace.c:bpf_send_signal
  - kernel/trace/bpf_trace.c:do_bpf_send_signal
```
**Symbols:**

```
ffffffff810ae130-ffffffff810ae180: group_send_sig_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int group_send_sig_info(int sig, struct kernel_siginfo *info, struct task_struct *p, enum pid_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8109ca80)
Location: kernel/signal.c:1403
Inline: False
Direct callers:
  - kernel/exit.c:do_exit
  - kernel/signal.c:kill_something_info
  - kernel/signal.c:kill_pid_info
  - kernel/signal.c:__kill_pgrp_info
  - kernel/pid_namespace.c:zap_pid_ns_processes
  - kernel/trace/bpf_trace.c:bpf_send_signal
  - kernel/trace/bpf_trace.c:do_bpf_send_signal
```
**Symbols:**

```
ffffffff8109ca80-ffffffff8109cad0: group_send_sig_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int group_send_sig_info(int sig, struct kernel_siginfo *info, struct task_struct *p, enum pid_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810ad690)
Location: kernel/signal.c:1403
Inline: False
Direct callers:
  - kernel/exit.c:do_exit
  - kernel/signal.c:kill_something_info
  - kernel/signal.c:kill_pid_info
  - kernel/signal.c:__kill_pgrp_info
  - kernel/pid_namespace.c:zap_pid_ns_processes
  - kernel/trace/bpf_trace.c:bpf_send_signal
  - kernel/trace/bpf_trace.c:do_bpf_send_signal
```
**Symbols:**

```
ffffffff810ad690-ffffffff810ad6e0: group_send_sig_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int group_send_sig_info(int sig, struct kernel_siginfo *info, struct task_struct *p, enum pid_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b5880)
Location: kernel/signal.c:1403
Inline: False
Direct callers:
  - kernel/exit.c:do_exit
  - kernel/signal.c:kill_something_info
  - kernel/signal.c:kill_pid_info
  - kernel/signal.c:__kill_pgrp_info
  - kernel/pid_namespace.c:zap_pid_ns_processes
  - kernel/trace/bpf_trace.c:bpf_send_signal
  - kernel/trace/bpf_trace.c:do_bpf_send_signal
```
**Symbols:**

```
ffffffff810b5880-ffffffff810b58ef: group_send_sig_info (STB_GLOBAL)
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
<b>Param added. </b>
<code>enum pid_type type</code>
</li>
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
