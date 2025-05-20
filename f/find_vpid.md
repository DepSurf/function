# Function: <code>find_vpid</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct pid *find_vpid(int nr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff8109db20)
Location: kernel/pid.c:380
Inline: True
Inline callers:
  - kernel/pid.c:find_get_pid
Direct callers:
  - kernel/signal.c:SYSC_kill
  - kernel/signal.c:SYSC_kill
  - kernel/signal.c:do_rt_sigqueueinfo
  - kernel/sys.c:SyS_setpriority
  - kernel/sys.c:SyS_getpriority
  - kernel/sys.c:SyS_setpgid
  - kernel/pid_namespace.c:zap_pid_ns_processes
  - fs/fcntl.c:f_setown
  - fs/fcntl.c:SyS_fcntl
  - block/ioprio.c:SyS_ioprio_set
  - block/ioprio.c:SyS_ioprio_get
  - drivers/tty/tty_io.c:tty_ioctl
```
**Symbols:**

```
ffffffff8109db20-ffffffff8109db5a: find_vpid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct pid *find_vpid(int nr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810a1276)
Location: kernel/pid.c:380
Inline: True
Inline callers:
  - kernel/pid.c:find_get_pid
Direct callers:
  - kernel/signal.c:do_rt_sigqueueinfo
  - kernel/signal.c:SYSC_kill
  - kernel/signal.c:SYSC_kill
  - kernel/sys.c:SyS_setpgid
  - kernel/sys.c:SyS_getpriority
  - kernel/sys.c:SyS_setpriority
  - kernel/pid_namespace.c:zap_pid_ns_processes
  - fs/fcntl.c:SyS_fcntl
  - fs/fcntl.c:f_setown
  - block/ioprio.c:SyS_ioprio_get
  - block/ioprio.c:SyS_ioprio_set
  - drivers/tty/tty_io.c:tty_ioctl
```
**Symbols:**

```
ffffffff810a1180-ffffffff810a11ba: find_vpid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct pid *find_vpid(int nr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810a6336)
Location: kernel/pid.c:380
Inline: True
Inline callers:
  - kernel/pid.c:find_get_pid
Direct callers:
  - kernel/signal.c:do_rt_sigqueueinfo
  - kernel/signal.c:SYSC_kill
  - kernel/signal.c:SYSC_kill
  - kernel/sys.c:SyS_setpgid
  - kernel/sys.c:SyS_getpriority
  - kernel/sys.c:SyS_setpriority
  - kernel/pid_namespace.c:zap_pid_ns_processes
  - fs/fcntl.c:SyS_fcntl
  - fs/fcntl.c:f_setown
  - block/ioprio.c:SyS_ioprio_get
  - block/ioprio.c:SyS_ioprio_set
  - drivers/tty/tty_io.c:tty_ioctl
```
**Symbols:**

```
ffffffff810a6240-ffffffff810a627a: find_vpid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct pid *find_vpid(int nr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810a3318)
Location: kernel/pid.c:381
Inline: True
Inline callers:
  - kernel/pid.c:find_get_pid
Direct callers:
  - kernel/signal.c:do_rt_sigqueueinfo
  - kernel/signal.c:SYSC_kill
  - kernel/signal.c:SYSC_kill
  - kernel/sys.c:SyS_setpgid
  - kernel/sys.c:SyS_getpriority
  - kernel/sys.c:SyS_setpriority
  - kernel/pid_namespace.c:zap_pid_ns_processes
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:f_setown
  - block/ioprio.c:SyS_ioprio_get
  - block/ioprio.c:SyS_ioprio_set
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
```
**Symbols:**

```
ffffffff810a3220-ffffffff810a3253: find_vpid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct pid *find_vpid(int nr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810a9df5)
Location: kernel/pid.c:250
Inline: True
Inline callers:
  - kernel/pid.c:find_get_pid
Direct callers:
  - kernel/signal.c:do_rt_sigqueueinfo
  - kernel/signal.c:SYSC_kill
  - kernel/signal.c:SYSC_kill
  - kernel/sys.c:SyS_setpgid
  - kernel/sys.c:SyS_getpriority
  - kernel/sys.c:SyS_setpriority
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:f_setown
  - block/ioprio.c:SyS_ioprio_get
  - block/ioprio.c:SyS_ioprio_set
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
```
**Symbols:**

```
ffffffff810a9db0-ffffffff810a9dee: find_vpid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct pid *find_vpid(int nr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810b0a15)
Location: kernel/pid.c:262
Inline: True
Inline callers:
  - kernel/pid.c:find_get_pid
Direct callers:
  - kernel/signal.c:do_rt_sigqueueinfo
  - kernel/signal.c:__do_sys_kill
  - kernel/signal.c:__do_sys_kill
  - kernel/sys.c:__ia32_sys_setpgid
  - kernel/sys.c:__x64_sys_setpgid
  - kernel/sys.c:__ia32_sys_getpriority
  - kernel/sys.c:__x64_sys_getpriority
  - kernel/sys.c:__ia32_sys_setpriority
  - kernel/sys.c:__x64_sys_setpriority
  - kernel/bpf/syscall.c:bpf_task_fd_query
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:f_setown
  - block/ioprio.c:__ia32_sys_ioprio_get
  - block/ioprio.c:__x64_sys_ioprio_get
  - block/ioprio.c:__ia32_sys_ioprio_set
  - block/ioprio.c:__x64_sys_ioprio_set
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
```
**Symbols:**

```
ffffffff810b09c0-ffffffff810b0a0c: find_vpid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct pid *find_vpid(int nr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810b9ae5)
Location: kernel/pid.c:264
Inline: True
Inline callers:
  - kernel/pid.c:find_get_pid
Direct callers:
  - kernel/signal.c:do_rt_sigqueueinfo
  - kernel/signal.c:kill_something_info
  - kernel/signal.c:kill_something_info
  - kernel/sys.c:__ia32_sys_setpgid
  - kernel/sys.c:__x64_sys_setpgid
  - kernel/sys.c:__ia32_sys_getpriority
  - kernel/sys.c:__x64_sys_getpriority
  - kernel/sys.c:__ia32_sys_setpriority
  - kernel/sys.c:__x64_sys_setpriority
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/bpf/syscall.c:__do_sys_bpf
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:f_setown
  - block/ioprio.c:__ia32_sys_ioprio_get
  - block/ioprio.c:__x64_sys_ioprio_get
  - block/ioprio.c:__ia32_sys_ioprio_set
  - block/ioprio.c:__x64_sys_ioprio_set
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
```
**Symbols:**

```
ffffffff810b9aa0-ffffffff810b9adc: find_vpid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct pid *find_vpid(int nr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810bf859)
Location: kernel/pid.c:267
Inline: True
Inline callers:
  - kernel/pid.c:find_get_pid
Direct callers:
  - kernel/signal.c:do_rt_sigqueueinfo
  - kernel/signal.c:kill_something_info
  - kernel/signal.c:kill_something_info
  - kernel/sys.c:__ia32_sys_setpgid
  - kernel/sys.c:__x64_sys_setpgid
  - kernel/sys.c:__ia32_sys_getpriority
  - kernel/sys.c:__x64_sys_getpriority
  - kernel/sys.c:__ia32_sys_setpriority
  - kernel/sys.c:__x64_sys_setpriority
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/bpf/syscall.c:__do_sys_bpf
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:f_setown
  - block/ioprio.c:__ia32_sys_ioprio_get
  - block/ioprio.c:__x64_sys_ioprio_get
  - block/ioprio.c:__ia32_sys_ioprio_set
  - block/ioprio.c:__x64_sys_ioprio_set
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
```
**Symbols:**

```
ffffffff810bf810-ffffffff810bf848: find_vpid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct pid *find_vpid(int nr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810c5c29)
Location: kernel/pid.c:267
Inline: True
Inline callers:
  - kernel/pid.c:find_get_pid
Direct callers:
  - kernel/signal.c:do_rt_sigqueueinfo
  - kernel/signal.c:kill_something_info
  - kernel/signal.c:kill_something_info
  - kernel/sys.c:__ia32_sys_setpgid
  - kernel/sys.c:__x64_sys_setpgid
  - kernel/sys.c:__ia32_sys_getpriority
  - kernel/sys.c:__x64_sys_getpriority
  - kernel/sys.c:__ia32_sys_setpriority
  - kernel/sys.c:__x64_sys_setpriority
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/bpf/syscall.c:__do_sys_bpf
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:f_setown
  - block/ioprio.c:__ia32_sys_ioprio_get
  - block/ioprio.c:__x64_sys_ioprio_get
  - block/ioprio.c:__ia32_sys_ioprio_set
  - block/ioprio.c:__x64_sys_ioprio_set
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
```
**Symbols:**

```
ffffffff810c5be0-ffffffff810c5c18: find_vpid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct pid *find_vpid(int nr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810cd600)
Location: kernel/pid.c:314
Inline: True
Inline callers:
  - kernel/pid.c:find_get_pid
Direct callers:
  - kernel/signal.c:do_rt_sigqueueinfo
  - kernel/signal.c:kill_something_info
  - kernel/signal.c:kill_something_info
  - kernel/sys.c:__do_sys_setpgid
  - kernel/sys.c:__do_sys_getpriority
  - kernel/sys.c:__do_sys_setpriority
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/bpf/syscall.c:bpf_task_fd_query
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:f_setown
  - block/ioprio.c:__do_sys_ioprio_get
  - block/ioprio.c:__do_sys_ioprio_set
  - drivers/tty/tty_jobctrl.c:tiocspgrp
```
**Symbols:**

```
ffffffff810cd480-ffffffff810cd4b8: find_vpid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct pid *find_vpid(int nr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810c81cb)
Location: kernel/pid.c:315
Inline: True
Inline callers:
  - kernel/pid.c:find_get_pid
Direct callers:
  - kernel/signal.c:do_rt_sigqueueinfo
  - kernel/signal.c:kill_something_info
  - kernel/signal.c:kill_something_info
  - kernel/sys.c:__do_sys_setpgid
  - kernel/sys.c:__do_sys_getpriority
  - kernel/sys.c:__do_sys_setpriority
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/bpf/syscall.c:bpf_task_fd_query
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:f_setown
  - block/ioprio.c:__do_sys_ioprio_get
  - block/ioprio.c:__do_sys_ioprio_set
```
**Symbols:**

```
ffffffff810c7f10-ffffffff810c7f48: find_vpid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct pid *find_vpid(int nr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810c9ceb)
Location: kernel/pid.c:315
Inline: True
Inline callers:
  - kernel/pid.c:find_get_pid
Direct callers:
  - kernel/signal.c:do_rt_sigqueueinfo
  - kernel/signal.c:kill_something_info
  - kernel/signal.c:kill_something_info
  - kernel/sys.c:__do_sys_setpgid
  - kernel/sys.c:__do_sys_getpriority
  - kernel/sys.c:__do_sys_setpriority
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/bpf/syscall.c:bpf_task_fd_query
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:f_setown
  - block/ioprio.c:__do_sys_ioprio_get
  - block/ioprio.c:__do_sys_ioprio_set
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
```
**Symbols:**

```
ffffffff810c99b0-ffffffff810c99e8: find_vpid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct pid *find_vpid(int nr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810dcbdb)
Location: kernel/pid.c:315
Inline: True
Inline callers:
  - kernel/pid.c:find_get_pid
Direct callers:
  - kernel/signal.c:do_rt_sigqueueinfo
  - kernel/signal.c:kill_something_info
  - kernel/signal.c:kill_something_info
  - kernel/sys.c:__do_sys_setpgid
  - kernel/sys.c:__do_sys_getpriority
  - kernel/sys.c:__do_sys_setpriority
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/bpf/syscall.c:bpf_task_fd_query
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:f_setown
  - block/ioprio.c:__do_sys_ioprio_get
  - block/ioprio.c:__do_sys_ioprio_set
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
```
**Symbols:**

```
ffffffff810dc910-ffffffff810dc948: find_vpid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct pid *find_vpid(int nr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810f754f)
Location: kernel/pid.c:315
Inline: True
Inline callers:
  - kernel/pid.c:__ia32_sys_pidfd_open
  - kernel/pid.c:__x64_sys_pidfd_open
Direct callers:
  - kernel/signal.c:do_rt_sigqueueinfo
  - kernel/signal.c:kill_something_info
  - kernel/signal.c:kill_something_info
  - kernel/sys.c:__do_sys_setpgid
  - kernel/sys.c:__do_sys_getpriority
  - kernel/sys.c:__do_sys_setpriority
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/bpf/syscall.c:bpf_task_fd_query
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:f_setown
  - block/ioprio.c:__do_sys_ioprio_get
  - block/ioprio.c:__do_sys_ioprio_set
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
```
**Symbols:**

```
ffffffff810f60d0-ffffffff810f6111: find_vpid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct pid *find_vpid(int nr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff81119ccf)
Location: kernel/pid.c:315
Inline: True
Inline callers:
  - kernel/pid.c:__ia32_sys_pidfd_open
  - kernel/pid.c:__x64_sys_pidfd_open
Direct callers:
  - kernel/signal.c:do_rt_sigqueueinfo
  - kernel/signal.c:kill_something_info
  - kernel/signal.c:kill_something_info
  - kernel/sys.c:__do_sys_setpgid
  - kernel/sys.c:__do_sys_getpriority
  - kernel/sys.c:__do_sys_setpriority
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/bpf/syscall.c:bpf_task_fd_query
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:f_setown
  - block/ioprio.c:__do_sys_ioprio_get
  - block/ioprio.c:__do_sys_ioprio_set
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
```
**Symbols:**

```
ffffffff81118670-ffffffff811186b1: find_vpid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct pid *find_vpid(int nr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff81125de0)
Location: kernel/pid.c:318
Inline: True
Inline callers:
  - kernel/pid.c:__ia32_sys_pidfd_open
  - kernel/pid.c:__x64_sys_pidfd_open
Direct callers:
  - kernel/signal.c:do_rt_sigqueueinfo
  - kernel/signal.c:kill_something_info
  - kernel/signal.c:kill_something_info
  - kernel/sys.c:__do_sys_setpgid
  - kernel/sys.c:__do_sys_getpriority
  - kernel/sys.c:__do_sys_setpriority
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/bpf/syscall.c:bpf_task_fd_query
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:f_setown
  - block/ioprio.c:__do_sys_ioprio_get
  - block/ioprio.c:__do_sys_ioprio_set
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
```
**Symbols:**

```
ffffffff811258b0-ffffffff811258f1: find_vpid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct pid *find_vpid(int nr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff811303e0)
Location: kernel/pid.c:318
Inline: True
Inline callers:
  - kernel/pid.c:__ia32_sys_pidfd_open
  - kernel/pid.c:__x64_sys_pidfd_open
Direct callers:
  - kernel/signal.c:do_rt_sigqueueinfo
  - kernel/signal.c:kill_something_info
  - kernel/signal.c:kill_something_info
  - kernel/sys.c:__do_sys_setpgid
  - kernel/sys.c:__do_sys_getpriority
  - kernel/sys.c:__do_sys_setpriority
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/trace/bpf_trace.c:bpf_uprobe_multi_link_attach
  - kernel/bpf/syscall.c:bpf_task_fd_query
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:f_setown
  - block/ioprio.c:__do_sys_ioprio_get
  - block/ioprio.c:__do_sys_ioprio_set
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
```
**Symbols:**

```
ffffffff8112feb0-ffffffff8112fef1: find_vpid (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
struct pid *find_vpid(int nr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffff800010124248)
Location: kernel/pid.c:267
Inline: True
Inline callers:
  - kernel/pid.c:find_get_pid
Direct callers:
  - kernel/signal.c:do_rt_sigqueueinfo
  - kernel/signal.c:__arm64_sys_kill
  - kernel/signal.c:__arm64_sys_kill
  - kernel/sys.c:__arm64_sys_setpgid
  - kernel/sys.c:__arm64_sys_getpriority
  - kernel/sys.c:__arm64_sys_setpriority
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/bpf/syscall.c:__do_sys_bpf
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:f_setown
  - block/ioprio.c:__arm64_sys_ioprio_get
  - block/ioprio.c:__arm64_sys_ioprio_set
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
```
**Symbols:**

```
ffff8000101241e8-ffff800010124230: find_vpid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct pid *find_vpid(int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (c03774e0)
Location: kernel/pid.c:267
Inline: False
Direct callers:
  - kernel/signal.c:__se_sys_rt_sigqueueinfo
  - kernel/signal.c:__se_sys_kill
  - kernel/signal.c:__se_sys_kill
  - kernel/sys.c:__se_sys_setpgid
  - kernel/sys.c:__se_sys_getpriority
  - kernel/sys.c:__se_sys_setpriority
  - kernel/pid.c:find_get_pid
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/bpf/syscall.c:bpf_task_fd_query
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:f_setown
  - block/ioprio.c:__se_sys_ioprio_get
  - block/ioprio.c:__se_sys_ioprio_set
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
```
**Symbols:**

```
c03774e0-c0377528: find_vpid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct pid *find_vpid(int nr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (c00000000016df10)
Location: kernel/pid.c:267
Inline: True
Inline callers:
  - kernel/pid.c:find_get_pid
Direct callers:
  - kernel/signal.c:do_rt_sigqueueinfo
  - kernel/signal.c:__se_sys_kill
  - kernel/signal.c:__se_sys_kill
  - kernel/sys.c:__se_sys_setpgid
  - kernel/sys.c:__se_sys_getpriority
  - kernel/sys.c:__se_sys_setpriority
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/bpf/syscall.c:__do_sys_bpf
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:f_setown
  - block/ioprio.c:__se_sys_ioprio_get
  - block/ioprio.c:__se_sys_ioprio_set
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
```
**Symbols:**

```
c00000000016de90-c00000000016def0: find_vpid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct pid *find_vpid(int nr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffe0000dc494)
Location: kernel/pid.c:267
Inline: True
Inline callers:
  - kernel/pid.c:find_get_pid
Direct callers:
  - kernel/signal.c:__se_sys_rt_sigqueueinfo
  - kernel/signal.c:__se_sys_kill
  - kernel/signal.c:__se_sys_kill
  - kernel/sys.c:__se_sys_setpgid
  - kernel/sys.c:__se_sys_getpriority
  - kernel/sys.c:__se_sys_setpriority
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/bpf/syscall.c:__do_sys_bpf
  - fs/fcntl.c:__se_sys_fcntl
  - fs/fcntl.c:f_setown
  - block/ioprio.c:__se_sys_ioprio_get
  - block/ioprio.c:__se_sys_ioprio_set
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
```
**Symbols:**

```
ffffffe0000dc43e-ffffffe0000dc47e: find_vpid (STB_GLOBAL)
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
struct pid *find_vpid(int nr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810bffa9)
Location: kernel/pid.c:267
Inline: True
Inline callers:
  - kernel/pid.c:find_get_pid
Direct callers:
  - kernel/signal.c:do_rt_sigqueueinfo
  - kernel/signal.c:kill_something_info
  - kernel/signal.c:kill_something_info
  - kernel/sys.c:__ia32_sys_setpgid
  - kernel/sys.c:__x64_sys_setpgid
  - kernel/sys.c:__ia32_sys_getpriority
  - kernel/sys.c:__x64_sys_getpriority
  - kernel/sys.c:__ia32_sys_setpriority
  - kernel/sys.c:__x64_sys_setpriority
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/bpf/syscall.c:__do_sys_bpf
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:f_setown
  - block/ioprio.c:__ia32_sys_ioprio_get
  - block/ioprio.c:__x64_sys_ioprio_get
  - block/ioprio.c:__ia32_sys_ioprio_set
  - block/ioprio.c:__x64_sys_ioprio_set
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
```
**Symbols:**

```
ffffffff810bff60-ffffffff810bff98: find_vpid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct pid *find_vpid(int nr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810ae7b9)
Location: kernel/pid.c:267
Inline: True
Inline callers:
  - kernel/pid.c:find_get_pid
Direct callers:
  - kernel/signal.c:do_rt_sigqueueinfo
  - kernel/signal.c:kill_something_info
  - kernel/signal.c:kill_something_info
  - kernel/sys.c:__ia32_sys_setpgid
  - kernel/sys.c:__x64_sys_setpgid
  - kernel/sys.c:__ia32_sys_getpriority
  - kernel/sys.c:__x64_sys_getpriority
  - kernel/sys.c:__ia32_sys_setpriority
  - kernel/sys.c:__x64_sys_setpriority
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/bpf/syscall.c:__do_sys_bpf
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:f_setown
  - block/ioprio.c:__ia32_sys_ioprio_get
  - block/ioprio.c:__x64_sys_ioprio_get
  - block/ioprio.c:__ia32_sys_ioprio_set
  - block/ioprio.c:__x64_sys_ioprio_set
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
```
**Symbols:**

```
ffffffff810ae770-ffffffff810ae7a8: find_vpid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct pid *find_vpid(int nr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810bf4f9)
Location: kernel/pid.c:267
Inline: True
Inline callers:
  - kernel/pid.c:find_get_pid
Direct callers:
  - kernel/signal.c:do_rt_sigqueueinfo
  - kernel/signal.c:kill_something_info
  - kernel/signal.c:kill_something_info
  - kernel/sys.c:__ia32_sys_setpgid
  - kernel/sys.c:__x64_sys_setpgid
  - kernel/sys.c:__ia32_sys_getpriority
  - kernel/sys.c:__x64_sys_getpriority
  - kernel/sys.c:__ia32_sys_setpriority
  - kernel/sys.c:__x64_sys_setpriority
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/bpf/syscall.c:__do_sys_bpf
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:f_setown
  - block/ioprio.c:__ia32_sys_ioprio_get
  - block/ioprio.c:__x64_sys_ioprio_get
  - block/ioprio.c:__ia32_sys_ioprio_set
  - block/ioprio.c:__x64_sys_ioprio_set
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
```
**Symbols:**

```
ffffffff810bf4b0-ffffffff810bf4e8: find_vpid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct pid *find_vpid(int nr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810c7803)
Location: kernel/pid.c:267
Inline: True
Inline callers:
  - kernel/pid.c:find_get_pid
Direct callers:
  - kernel/signal.c:do_rt_sigqueueinfo
  - kernel/signal.c:kill_something_info
  - kernel/signal.c:kill_something_info
  - kernel/sys.c:__ia32_sys_setpgid
  - kernel/sys.c:__x64_sys_setpgid
  - kernel/sys.c:__ia32_sys_getpriority
  - kernel/sys.c:__x64_sys_getpriority
  - kernel/sys.c:__ia32_sys_setpriority
  - kernel/sys.c:__x64_sys_setpriority
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/bpf/syscall.c:__do_sys_bpf
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:f_setown
  - block/ioprio.c:__ia32_sys_ioprio_get
  - block/ioprio.c:__x64_sys_ioprio_get
  - block/ioprio.c:__ia32_sys_ioprio_set
  - block/ioprio.c:__x64_sys_ioprio_set
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
```
**Symbols:**

```
ffffffff810c7740-ffffffff810c7778: find_vpid (STB_GLOBAL)
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
