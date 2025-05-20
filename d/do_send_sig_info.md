# Function: <code>do_send_sig_info</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int do_send_sig_info(int sig, struct siginfo *info, struct task_struct *p, bool group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8108f230)
Location: kernel/signal.c:1134
Inline: False
Direct callers:
  - kernel/signal.c:send_sig
  - kernel/signal.c:do_send_specific
  - kernel/signal.c:kdb_send_sig_info
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:oom_kill_process
  - fs/fcntl.c:send_sigio_to_task
  - fs/fcntl.c:send_sigio_to_task
  - fs/fcntl.c:send_sigurg
  - drivers/tty/sysrq.c:send_sig_all
```
**Symbols:**

```
ffffffff8108f230-ffffffff8108f2c8: do_send_sig_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int do_send_sig_info(int sig, struct siginfo *info, struct task_struct *p, bool group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810922a0)
Location: kernel/signal.c:1134
Inline: False
Direct callers:
  - kernel/signal.c:kdb_send_sig_info
  - kernel/signal.c:do_send_specific
  - kernel/signal.c:send_sig
  - fs/fcntl.c:send_sigurg
  - fs/fcntl.c:send_sigio_to_task
  - fs/fcntl.c:send_sigio_to_task
  - drivers/tty/sysrq.c:send_sig_all
```
**Symbols:**

```
ffffffff810922a0-ffffffff81092338: do_send_sig_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int do_send_sig_info(int sig, struct siginfo *info, struct task_struct *p, bool group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81097230)
Location: kernel/signal.c:1140
Inline: False
Direct callers:
  - kernel/signal.c:kdb_send_sig_info
  - kernel/signal.c:do_send_specific
  - kernel/signal.c:send_sig
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:oom_kill_process
  - fs/fcntl.c:send_sigurg
  - fs/fcntl.c:send_sigio_to_task
  - fs/fcntl.c:send_sigio_to_task
  - drivers/tty/sysrq.c:send_sig_all
```
**Symbols:**

```
ffffffff81097230-ffffffff810972c8: do_send_sig_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int do_send_sig_info(int sig, struct siginfo *info, struct task_struct *p, bool group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81094530)
Location: kernel/signal.c:1154
Inline: False
Direct callers:
  - kernel/signal.c:kdb_send_sig_info
  - kernel/signal.c:do_send_specific
  - kernel/signal.c:send_sig
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:oom_kill_process
  - fs/fcntl.c:send_sigurg
  - fs/fcntl.c:send_sigio_to_task
  - fs/fcntl.c:send_sigio_to_task
  - drivers/tty/sysrq.c:send_sig_all
```
**Symbols:**

```
ffffffff81094530-ffffffff810945c8: do_send_sig_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int do_send_sig_info(int sig, struct siginfo *info, struct task_struct *p, bool group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8109b3d0)
Location: kernel/signal.c:1155
Inline: False
Direct callers:
  - kernel/signal.c:kdb_send_sig_info
  - kernel/signal.c:do_send_specific
  - kernel/signal.c:send_sig
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:oom_kill_process
  - fs/fcntl.c:send_sigurg
  - fs/fcntl.c:send_sigio_to_task
  - fs/fcntl.c:send_sigio_to_task
  - drivers/tty/sysrq.c:send_sig_all
```
**Symbols:**

```
ffffffff8109b3d0-ffffffff8109b468: do_send_sig_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int do_send_sig_info(int sig, struct siginfo *info, struct task_struct *p, bool group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8109f320)
Location: kernel/signal.c:1163
Inline: False
Direct callers:
  - kernel/signal.c:do_send_specific
  - kernel/signal.c:send_sig_mceerr
  - kernel/signal.c:send_sig_fault
  - kernel/signal.c:send_sig
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:oom_kill_process
  - fs/fcntl.c:send_sigurg
  - fs/fcntl.c:send_sigio_to_task
  - fs/fcntl.c:send_sigio_to_task
  - drivers/tty/sysrq.c:send_sig_all
```
**Symbols:**

```
ffffffff8109f320-ffffffff8109f3b8: do_send_sig_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int do_send_sig_info(int sig, struct kernel_siginfo *info, struct task_struct *p, enum pid_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810a75e0)
Location: kernel/signal.c:1246
Inline: False
Direct callers:
  - kernel/signal.c:do_send_specific
  - kernel/signal.c:send_sig_mceerr
  - kernel/signal.c:send_sig_fault
  - kernel/signal.c:send_sig
  - kernel/signal.c:group_send_sig_info
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/memory-failure.c:kill_procs
  - fs/fcntl.c:send_sigurg
  - fs/fcntl.c:send_sigurg
  - fs/fcntl.c:send_sigio_to_task
  - fs/fcntl.c:send_sigio_to_task
  - drivers/tty/sysrq.c:send_sig_all
```
**Symbols:**

```
ffffffff810a75e0-ffffffff810a7677: do_send_sig_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int do_send_sig_info(int sig, struct kernel_siginfo *info, struct task_struct *p, enum pid_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810ad710)
Location: kernel/signal.c:1278
Inline: False
Direct callers:
  - kernel/signal.c:do_send_specific
  - kernel/signal.c:send_sig_mceerr
  - kernel/signal.c:send_sig_fault
  - kernel/signal.c:send_sig
  - kernel/signal.c:group_send_sig_info
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/memory-failure.c:kill_procs
  - fs/fcntl.c:send_sigurg
  - fs/fcntl.c:send_sigurg
  - fs/fcntl.c:send_sigio_to_task
  - fs/fcntl.c:send_sigio_to_task
  - drivers/tty/sysrq.c:send_sig_all
```
**Symbols:**

```
ffffffff810ad710-ffffffff810ad7a0: do_send_sig_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int do_send_sig_info(int sig, struct kernel_siginfo *info, struct task_struct *p, enum pid_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b3d30)
Location: kernel/signal.c:1283
Inline: False
Direct callers:
  - kernel/signal.c:do_send_specific
  - kernel/signal.c:send_sig_mceerr
  - kernel/signal.c:send_sig_fault
  - kernel/signal.c:send_sig
  - kernel/signal.c:group_send_sig_info
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/memory-failure.c:kill_procs
  - fs/fcntl.c:send_sigurg
  - fs/fcntl.c:send_sigurg
  - fs/fcntl.c:send_sigio_to_task
  - fs/fcntl.c:send_sigio_to_task
  - drivers/tty/sysrq.c:send_sig_all
```
**Symbols:**

```
ffffffff810b3d30-ffffffff810b3dc0: do_send_sig_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int do_send_sig_info(int sig, struct kernel_siginfo *info, struct task_struct *p, enum pid_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810bc7e0)
Location: kernel/signal.c:1283
Inline: False
Direct callers:
  - kernel/signal.c:do_send_specific
  - kernel/signal.c:kill_pid
  - kernel/signal.c:send_sig_mceerr
  - kernel/signal.c:send_sig_fault
  - kernel/signal.c:send_sig
  - kernel/signal.c:kill_something_info
  - kernel/signal.c:__kill_pgrp_info
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/memory-failure.c:kill_procs
  - fs/fcntl.c:send_sigurg
  - fs/fcntl.c:send_sigurg
  - fs/fcntl.c:send_sigio_to_task
  - fs/fcntl.c:send_sigio_to_task
  - ipc/mqueue.c:__do_notify
  - drivers/tty/sysrq.c:send_sig_all
```
**Symbols:**

```
ffffffff810bc7e0-ffffffff810bc894: do_send_sig_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int do_send_sig_info(int sig, struct kernel_siginfo *info, struct task_struct *p, enum pid_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b7ad0)
Location: kernel/signal.c:1284
Inline: False
Direct callers:
  - kernel/signal.c:do_send_specific
  - kernel/signal.c:send_sig_mceerr
  - kernel/signal.c:send_sig_fault
  - kernel/signal.c:send_sig
  - kernel/signal.c:kill_something_info
  - kernel/signal.c:kill_pid_info
  - kernel/signal.c:__kill_pgrp_info
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/memory-failure.c:kill_procs
  - fs/fcntl.c:send_sigurg
  - fs/fcntl.c:send_sigurg
  - fs/fcntl.c:send_sigio_to_task
  - fs/fcntl.c:send_sigio_to_task
  - ipc/mqueue.c:__do_notify
  - drivers/tty/sysrq.c:send_sig_all
```
**Symbols:**

```
ffffffff810b7ad0-ffffffff810b7b82: do_send_sig_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int do_send_sig_info(int sig, struct kernel_siginfo *info, struct task_struct *p, enum pid_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b9030)
Location: kernel/signal.c:1286
Inline: False
Direct callers:
  - kernel/signal.c:do_send_specific
  - kernel/signal.c:send_sig_mceerr
  - kernel/signal.c:send_sig_fault
  - kernel/signal.c:send_sig
  - kernel/signal.c:kill_something_info
  - kernel/signal.c:kill_pid_info
  - kernel/signal.c:__kill_pgrp_info
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/memory-failure.c:kill_procs
  - fs/fcntl.c:send_sigurg
  - fs/fcntl.c:send_sigurg
  - fs/fcntl.c:send_sigio_to_task
  - fs/fcntl.c:send_sigio_to_task
  - ipc/mqueue.c:__do_notify
  - drivers/tty/sysrq.c:send_sig_all
```
**Symbols:**

```
ffffffff810b9030-ffffffff810b90e2: do_send_sig_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int do_send_sig_info(int sig, struct kernel_siginfo *info, struct task_struct *p, enum pid_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810cb5c0)
Location: kernel/signal.c:1287
Inline: False
Direct callers:
  - kernel/signal.c:do_send_specific
  - kernel/signal.c:send_sig_fault_trapno
  - kernel/signal.c:send_sig_mceerr
  - kernel/signal.c:send_sig_fault
  - kernel/signal.c:send_sig
  - kernel/signal.c:kill_something_info
  - kernel/signal.c:kill_pid_info
  - kernel/signal.c:__kill_pgrp_info
  - kernel/cgroup/cgroup.c:cgroup_post_fork
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/memory-failure.c:kill_procs
  - fs/fcntl.c:send_sigurg
  - fs/fcntl.c:send_sigurg
  - fs/fcntl.c:send_sigio_to_task
  - fs/fcntl.c:send_sigio_to_task
  - ipc/mqueue.c:__do_notify
  - drivers/tty/sysrq.c:send_sig_all
```
**Symbols:**

```
ffffffff810cb5c0-ffffffff810cb672: do_send_sig_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int do_send_sig_info(int sig, struct kernel_siginfo *info, struct task_struct *p, enum pid_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810e2520)
Location: kernel/signal.c:1288
Inline: False
Direct callers:
  - kernel/signal.c:do_send_specific
  - kernel/signal.c:kill_pid
  - kernel/signal.c:send_sig_fault_trapno
  - kernel/signal.c:send_sig_perf
  - kernel/signal.c:send_sig_mceerr
  - kernel/signal.c:send_sig_fault
  - kernel/signal.c:send_sig
  - kernel/signal.c:kill_something_info
  - kernel/signal.c:__kill_pgrp_info
  - kernel/cgroup/cgroup.c:cgroup_post_fork
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/memory-failure.c:kill_procs
  - fs/fcntl.c:send_sigurg
  - fs/fcntl.c:send_sigurg
  - fs/fcntl.c:send_sigio_to_task
  - fs/fcntl.c:send_sigio_to_task
  - ipc/mqueue.c:__do_notify
  - drivers/tty/sysrq.c:send_sig_all
```
**Symbols:**

```
ffffffff810e2520-ffffffff810e25d4: do_send_sig_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int do_send_sig_info(int sig, struct kernel_siginfo *info, struct task_struct *p, enum pid_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff811028f0)
Location: kernel/signal.c:1289
Inline: False
Direct callers:
  - kernel/signal.c:do_send_specific
  - kernel/signal.c:kill_pid
  - kernel/signal.c:send_sig_fault_trapno
  - kernel/signal.c:send_sig_perf
  - kernel/signal.c:send_sig_mceerr
  - kernel/signal.c:send_sig_fault
  - kernel/signal.c:send_sig
  - kernel/signal.c:kill_something_info
  - kernel/signal.c:__kill_pgrp_info
  - kernel/cgroup/cgroup.c:cgroup_post_fork
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/memory-failure.c:kill_procs
  - fs/fcntl.c:send_sigurg
  - fs/fcntl.c:send_sigurg
  - fs/fcntl.c:send_sigio_to_task
  - fs/fcntl.c:send_sigio_to_task
  - ipc/mqueue.c:__do_notify
  - drivers/tty/sysrq.c:send_sig_all
```
**Symbols:**

```
ffffffff811028f0-ffffffff811029a4: do_send_sig_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int do_send_sig_info(int sig, struct kernel_siginfo *info, struct task_struct *p, enum pid_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8110eb30)
Location: kernel/signal.c:1293
Inline: False
Direct callers:
  - kernel/signal.c:do_send_specific
  - kernel/signal.c:kill_pid
  - kernel/signal.c:send_sig_fault_trapno
  - kernel/signal.c:send_sig_perf
  - kernel/signal.c:send_sig_mceerr
  - kernel/signal.c:send_sig_fault
  - kernel/signal.c:send_sig
  - kernel/signal.c:kill_something_info
  - kernel/signal.c:__kill_pgrp_info
  - kernel/cgroup/cgroup.c:cgroup_post_fork
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/memory-failure.c:kill_procs
  - fs/fcntl.c:send_sigurg
  - fs/fcntl.c:send_sigurg
  - fs/fcntl.c:send_sigio_to_task
  - fs/fcntl.c:send_sigio_to_task
  - ipc/mqueue.c:__do_notify
  - drivers/tty/sysrq.c:send_sig_all
```
**Symbols:**

```
ffffffff8110eb30-ffffffff8110ebe4: do_send_sig_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int do_send_sig_info(int sig, struct kernel_siginfo *info, struct task_struct *p, enum pid_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff811184b0)
Location: kernel/signal.c:1293
Inline: False
Direct callers:
  - kernel/signal.c:do_send_specific
  - kernel/signal.c:kill_pid
  - kernel/signal.c:send_sig_fault_trapno
  - kernel/signal.c:send_sig_perf
  - kernel/signal.c:send_sig_mceerr
  - kernel/signal.c:send_sig_fault
  - kernel/signal.c:send_sig
  - kernel/signal.c:kill_something_info
  - kernel/signal.c:__kill_pgrp_info
  - kernel/cgroup/cgroup.c:cgroup_post_fork
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/memory-failure.c:kill_procs
  - fs/fcntl.c:send_sigurg
  - fs/fcntl.c:send_sigurg
  - fs/fcntl.c:send_sigio_to_task
  - fs/fcntl.c:send_sigio_to_task
  - ipc/mqueue.c:__do_notify
  - drivers/tty/sysrq.c:send_sig_all
```
**Symbols:**

```
ffffffff811184b0-ffffffff81118564: do_send_sig_info (STB_GLOBAL)
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
int do_send_sig_info(int sig, struct kernel_siginfo *info, struct task_struct *p, enum pid_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffff80001010fd38)
Location: kernel/signal.c:1283
Inline: False
Direct callers:
  - kernel/signal.c:do_send_specific
  - kernel/signal.c:send_sig_mceerr
  - kernel/signal.c:send_sig_fault
  - kernel/signal.c:send_sig
  - kernel/signal.c:group_send_sig_info
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - fs/fcntl.c:send_sigurg
  - fs/fcntl.c:send_sigurg
  - fs/fcntl.c:send_sigio_to_task
  - fs/fcntl.c:send_sigio_to_task
  - drivers/tty/sysrq.c:send_sig_all
```
**Symbols:**

```
ffff80001010fd38-ffff80001010fde4: do_send_sig_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int do_send_sig_info(int sig, struct kernel_siginfo *info, struct task_struct *p, enum pid_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c0367b24)
Location: kernel/signal.c:1283
Inline: False
Direct callers:
  - kernel/signal.c:do_send_specific
  - kernel/signal.c:send_sig_mceerr
  - kernel/signal.c:send_sig_fault
  - kernel/signal.c:send_sig
  - kernel/signal.c:group_send_sig_info
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - fs/fcntl.c:send_sigurg
  - fs/fcntl.c:send_sigurg
  - fs/fcntl.c:send_sigio_to_task
  - fs/fcntl.c:send_sigio_to_task
  - drivers/tty/sysrq.c:send_sig_all
```
**Symbols:**

```
c0367b24-c0367bc8: do_send_sig_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int do_send_sig_info(int sig, struct kernel_siginfo *info, struct task_struct *p, enum pid_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c0000000001573f0)
Location: kernel/signal.c:1283
Inline: False
Direct callers:
  - kernel/signal.c:do_send_specific
  - kernel/signal.c:send_sig_mceerr
  - kernel/signal.c:send_sig_fault
  - kernel/signal.c:send_sig
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/memory-failure.c:kill_procs
  - fs/fcntl.c:send_sigurg
  - fs/fcntl.c:send_sigurg
  - fs/fcntl.c:send_sigio_to_task
  - fs/fcntl.c:send_sigio_to_task
  - fs/fcntl.c:send_sigio_to_task
  - drivers/tty/sysrq.c:send_sig_all
```
**Symbols:**

```
c0000000001573f0-c0000000001574c0: do_send_sig_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int do_send_sig_info(int sig, struct kernel_siginfo *info, struct task_struct *p, enum pid_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffe0000d00ba)
Location: kernel/signal.c:1283
Inline: False
Direct callers:
  - kernel/signal.c:do_send_specific
  - kernel/signal.c:send_sig_mceerr
  - kernel/signal.c:send_sig_fault
  - kernel/signal.c:send_sig
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - fs/fcntl.c:send_sigurg
  - fs/fcntl.c:send_sigurg
  - fs/fcntl.c:send_sigio_to_task
  - fs/fcntl.c:send_sigio_to_task
  - drivers/tty/sysrq.c:send_sig_all
```
**Symbols:**

```
ffffffe0000d00ba-ffffffe0000d0126: do_send_sig_info (STB_GLOBAL)
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
int do_send_sig_info(int sig, struct kernel_siginfo *info, struct task_struct *p, enum pid_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810ae0a0)
Location: kernel/signal.c:1283
Inline: False
Direct callers:
  - kernel/signal.c:do_send_specific
  - kernel/signal.c:send_sig_mceerr
  - kernel/signal.c:send_sig_fault
  - kernel/signal.c:send_sig
  - kernel/signal.c:group_send_sig_info
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/memory-failure.c:kill_procs
  - fs/fcntl.c:send_sigurg
  - fs/fcntl.c:send_sigurg
  - fs/fcntl.c:send_sigio_to_task
  - fs/fcntl.c:send_sigio_to_task
  - drivers/tty/sysrq.c:send_sig_all
```
**Symbols:**

```
ffffffff810ae0a0-ffffffff810ae130: do_send_sig_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int do_send_sig_info(int sig, struct kernel_siginfo *info, struct task_struct *p, enum pid_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8109c9f0)
Location: kernel/signal.c:1283
Inline: False
Direct callers:
  - kernel/signal.c:do_send_specific
  - kernel/signal.c:send_sig_mceerr
  - kernel/signal.c:send_sig_fault
  - kernel/signal.c:send_sig
  - kernel/signal.c:group_send_sig_info
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/memory-failure.c:kill_procs
  - fs/fcntl.c:send_sigurg
  - fs/fcntl.c:send_sigurg
  - fs/fcntl.c:send_sigio_to_task
  - fs/fcntl.c:send_sigio_to_task
  - drivers/tty/sysrq.c:send_sig_all
```
**Symbols:**

```
ffffffff8109c9f0-ffffffff8109ca80: do_send_sig_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int do_send_sig_info(int sig, struct kernel_siginfo *info, struct task_struct *p, enum pid_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810ad600)
Location: kernel/signal.c:1283
Inline: False
Direct callers:
  - kernel/signal.c:do_send_specific
  - kernel/signal.c:send_sig_mceerr
  - kernel/signal.c:send_sig_fault
  - kernel/signal.c:send_sig
  - kernel/signal.c:group_send_sig_info
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/memory-failure.c:kill_procs
  - fs/fcntl.c:send_sigurg
  - fs/fcntl.c:send_sigurg
  - fs/fcntl.c:send_sigio_to_task
  - fs/fcntl.c:send_sigio_to_task
  - drivers/tty/sysrq.c:send_sig_all
```
**Symbols:**

```
ffffffff810ad600-ffffffff810ad690: do_send_sig_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int do_send_sig_info(int sig, struct kernel_siginfo *info, struct task_struct *p, enum pid_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b57f0)
Location: kernel/signal.c:1283
Inline: False
Direct callers:
  - kernel/signal.c:do_send_specific
  - kernel/signal.c:send_sig_mceerr
  - kernel/signal.c:send_sig_fault
  - kernel/signal.c:send_sig
  - kernel/signal.c:group_send_sig_info
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/memory-failure.c:kill_procs
  - fs/fcntl.c:send_sigurg
  - fs/fcntl.c:send_sigurg
  - fs/fcntl.c:send_sigio_to_task
  - fs/fcntl.c:send_sigio_to_task
  - drivers/tty/sysrq.c:send_sig_all
```
**Symbols:**

```
ffffffff810b57f0-ffffffff810b5880: do_send_sig_info (STB_GLOBAL)
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
<b>Param removed. </b>
<code>bool group</code>
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
