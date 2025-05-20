# Function: <code>pid_task</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct task_struct *pid_task(struct pid *pid, enum pid_type type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff8109db60)
Location: kernel/pid.c:435
Inline: True
Inline callers:
  - kernel/pid.c:get_pid_task
  - kernel/pid.c:find_task_by_vpid
Direct callers:
  - kernel/signal.c:kill_pid_info_as_cred
  - kernel/signal.c:kill_pid_info
  - kernel/sys.c:SyS_setpgid
  - kernel/sys.c:sys_setsid
  - kernel/time/posix-timers.c:posix_timer_event
  - kernel/pid_namespace.c:zap_pid_ns_processes
  - fs/proc/base.c:proc_loginuid_write
  - fs/proc/base.c:pid_getattr
  - fs/proc/base.c:next_tgid
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/array.c:get_children_pid
  - fs/proc/array.c:get_children_pid
  - fs/proc/fd.c:proc_fd_permission
  - fs/proc/proc_net.c:get_proc_task_net
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
```
**Symbols:**

```
ffffffff8109db60-ffffffff8109db92: pid_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct task_struct *pid_task(struct pid *pid, enum pid_type type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810a1236)
Location: kernel/pid.c:435
Inline: True
Inline callers:
  - kernel/pid.c:get_pid_task
  - kernel/pid.c:find_task_by_vpid
Direct callers:
  - kernel/signal.c:kill_pid_info_as_cred
  - kernel/signal.c:kill_pid_info
  - kernel/sys.c:sys_setsid
  - kernel/sys.c:SyS_setpgid
  - kernel/time/posix-timers.c:posix_timer_event
  - kernel/pid_namespace.c:zap_pid_ns_processes
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:next_tgid
  - fs/proc/base.c:pid_getattr
  - fs/proc/base.c:proc_loginuid_write
  - fs/proc/array.c:get_children_pid
  - fs/proc/array.c:get_children_pid
  - fs/proc/fd.c:proc_fd_permission
  - fs/proc/proc_net.c:get_proc_task_net
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
```
**Symbols:**

```
ffffffff810a11c0-ffffffff810a11f2: pid_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct task_struct *pid_task(struct pid *pid, enum pid_type type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810a62f6)
Location: kernel/pid.c:435
Inline: True
Inline callers:
  - kernel/pid.c:get_pid_task
  - kernel/pid.c:find_task_by_vpid
Direct callers:
  - kernel/signal.c:kill_pid_info_as_cred
  - kernel/signal.c:kill_pid_info
  - kernel/sys.c:sys_setsid
  - kernel/sys.c:SyS_setpgid
  - kernel/time/posix-timers.c:posix_timer_event
  - kernel/pid_namespace.c:zap_pid_ns_processes
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:next_tgid
  - fs/proc/base.c:pid_getattr
  - fs/proc/base.c:proc_loginuid_write
  - fs/proc/array.c:get_children_pid
  - fs/proc/array.c:get_children_pid
  - fs/proc/fd.c:proc_fd_permission
  - fs/proc/proc_net.c:get_proc_task_net
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
```
**Symbols:**

```
ffffffff810a6280-ffffffff810a62b2: pid_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct task_struct *pid_task(struct pid *pid, enum pid_type type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810a32d6)
Location: kernel/pid.c:436
Inline: True
Inline callers:
  - kernel/pid.c:get_pid_task
  - kernel/pid.c:find_task_by_vpid
Direct callers:
  - kernel/signal.c:kill_pid_info_as_cred
  - kernel/signal.c:kill_pid_info
  - kernel/sys.c:sys_setsid
  - kernel/sys.c:SyS_setpgid
  - kernel/time/posix-timers.c:posix_timer_event
  - kernel/pid_namespace.c:zap_pid_ns_processes
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:next_tgid
  - fs/proc/base.c:pid_getattr
  - fs/proc/base.c:proc_loginuid_write
  - fs/proc/array.c:get_children_pid
  - fs/proc/array.c:get_children_pid
  - fs/proc/fd.c:proc_fd_permission
  - fs/proc/proc_net.c:get_proc_task_net
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
```
**Symbols:**

```
ffffffff810a3260-ffffffff810a3292: pid_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct task_struct *pid_task(struct pid *pid, enum pid_type type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810a9b35)
Location: kernel/pid.c:305
Inline: True
Inline callers:
  - kernel/pid.c:get_pid_task
  - kernel/pid.c:find_task_by_vpid
Direct callers:
  - kernel/signal.c:kill_pid_info_as_cred
  - kernel/signal.c:kill_pid_info
  - kernel/sys.c:sys_setsid
  - kernel/sys.c:SyS_setpgid
  - kernel/time/posix-timers.c:posix_timer_event
  - kernel/pid_namespace.c:zap_pid_ns_processes
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:next_tgid
  - fs/proc/base.c:pid_getattr
  - fs/proc/base.c:proc_loginuid_write
  - fs/proc/array.c:get_children_pid
  - fs/proc/array.c:get_children_pid
  - fs/proc/fd.c:proc_fd_permission
  - fs/proc/proc_net.c:get_proc_task_net
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
```
**Symbols:**

```
ffffffff810a9ab0-ffffffff810a9ae2: pid_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct task_struct *pid_task(struct pid *pid, enum pid_type type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810b0745)
Location: kernel/pid.c:317
Inline: True
Inline callers:
  - kernel/pid.c:get_pid_task
  - kernel/pid.c:find_task_by_vpid
Direct callers:
  - kernel/signal.c:kill_pid_info_as_cred
  - kernel/signal.c:kill_pid_info
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__ia32_sys_setpgid
  - kernel/sys.c:__x64_sys_setpgid
  - kernel/time/posix-timers.c:posix_timer_event
  - kernel/pid_namespace.c:zap_pid_ns_processes
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:next_tgid
  - fs/proc/base.c:pid_getattr
  - fs/proc/base.c:proc_loginuid_write
  - fs/proc/array.c:get_children_pid
  - fs/proc/array.c:get_children_pid
  - fs/proc/fd.c:proc_fd_permission
  - fs/proc/proc_net.c:get_proc_task_net
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
```
**Symbols:**

```
ffffffff810b06d0-ffffffff810b0704: pid_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct task_struct *pid_task(struct pid *pid, enum pid_type type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810b9885)
Location: kernel/pid.c:326
Inline: True
Inline callers:
  - kernel/pid.c:get_pid_task
  - kernel/pid.c:find_task_by_vpid
Direct callers:
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:kill_pid_info_as_cred
  - kernel/signal.c:kill_pid_info
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__ia32_sys_setpgid
  - kernel/sys.c:__x64_sys_setpgid
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/pid_namespace.c:zap_pid_ns_processes
  - fs/fcntl.c:send_sigurg
  - fs/fcntl.c:send_sigio
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:next_tgid
  - fs/proc/base.c:proc_pid_attr_write
  - fs/proc/base.c:pid_getattr
  - fs/proc/base.c:proc_loginuid_write
  - fs/proc/array.c:get_children_pid
  - fs/proc/array.c:get_children_pid
  - fs/proc/fd.c:proc_fd_permission
  - fs/proc/proc_net.c:get_proc_task_net
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
```
**Symbols:**

```
ffffffff810b9810-ffffffff810b9840: pid_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct task_struct *pid_task(struct pid *pid, enum pid_type type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810bf96c)
Location: kernel/pid.c:329
Inline: True
Inline callers:
  - kernel/pid.c:__ia32_sys_pidfd_open
  - kernel/pid.c:__x64_sys_pidfd_open
  - kernel/pid.c:get_pid_task
  - kernel/pid.c:find_task_by_vpid
Direct callers:
  - kernel/fork.c:pidfd_poll
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:kill_pid_usb_asyncio
  - kernel/signal.c:kill_pid_info
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__ia32_sys_setpgid
  - kernel/sys.c:__x64_sys_setpgid
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/pid_namespace.c:zap_pid_ns_processes
  - fs/fcntl.c:send_sigurg
  - fs/fcntl.c:send_sigio
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:next_tgid
  - fs/proc/base.c:proc_pid_attr_write
  - fs/proc/base.c:pid_getattr
  - fs/proc/base.c:proc_loginuid_write
  - fs/proc/array.c:get_children_pid
  - fs/proc/array.c:get_children_pid
  - fs/proc/fd.c:proc_fd_permission
  - fs/proc/proc_net.c:get_proc_task_net
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
```
**Symbols:**

```
ffffffff810bf590-ffffffff810bf5c1: pid_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct task_struct *pid_task(struct pid *pid, enum pid_type type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810c5d3c)
Location: kernel/pid.c:329
Inline: True
Inline callers:
  - kernel/pid.c:__ia32_sys_pidfd_open
  - kernel/pid.c:__x64_sys_pidfd_open
  - kernel/pid.c:get_pid_task
  - kernel/pid.c:find_task_by_vpid
Direct callers:
  - kernel/fork.c:pidfd_poll
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:kill_pid_usb_asyncio
  - kernel/signal.c:kill_pid_info
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__ia32_sys_setpgid
  - kernel/sys.c:__x64_sys_setpgid
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/pid_namespace.c:zap_pid_ns_processes
  - fs/fcntl.c:send_sigurg
  - fs/fcntl.c:send_sigio
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:next_tgid
  - fs/proc/base.c:proc_pid_attr_write
  - fs/proc/base.c:pid_getattr
  - fs/proc/base.c:proc_loginuid_write
  - fs/proc/array.c:get_children_pid
  - fs/proc/array.c:get_children_pid
  - fs/proc/fd.c:proc_fd_permission
  - fs/proc/proc_net.c:get_proc_task_net
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
```
**Symbols:**

```
ffffffff810c5970-ffffffff810c59a0: pid_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct task_struct *pid_task(struct pid *pid, enum pid_type type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810cd8b2)
Location: kernel/pid.c:395
Inline: True
Inline callers:
  - kernel/pid.c:pidfd_getfd
  - kernel/pid.c:find_get_task_by_vpid
Direct callers:
  - kernel/fork.c:pidfd_poll
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:kill_pid
  - kernel/signal.c:kill_pid_usb_asyncio
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__do_sys_setpgid
  - kernel/nsproxy.c:validate_nsset
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_get
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_del
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_get
  - kernel/time/posix-cpu-timers.c:pid_for_clock
  - kernel/pid_namespace.c:zap_pid_ns_processes
  - fs/fcntl.c:send_sigurg
  - fs/fcntl.c:send_sigio
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:next_tgid
  - fs/proc/base.c:proc_pid_attr_write
  - fs/proc/base.c:pid_getattr
  - fs/proc/base.c:proc_loginuid_write
  - fs/proc/array.c:get_children_pid
  - fs/proc/array.c:get_children_pid
  - fs/proc/fd.c:proc_fd_permission
  - fs/proc/proc_net.c:get_proc_task_net
  - ipc/mqueue.c:__do_notify
  - drivers/tty/tty_jobctrl.c:tiocspgrp
  - drivers/tty/tty_jobctrl.c:tiocspgrp
```
**Symbols:**

```
ffffffff810cd2d0-ffffffff810cd301: pid_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct task_struct *pid_task(struct pid *pid, enum pid_type type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810c83d2)
Location: kernel/pid.c:396
Inline: True
Inline callers:
  - kernel/pid.c:pidfd_getfd
  - kernel/pid.c:find_get_task_by_vpid
Direct callers:
  - kernel/exit.c:thread_group_exited
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:kill_pid_usb_asyncio
  - kernel/signal.c:kill_pid_info
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__do_sys_setpgid
  - kernel/nsproxy.c:validate_nsset
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_get
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_del
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_get
  - kernel/time/posix-cpu-timers.c:pid_for_clock
  - kernel/pid_namespace.c:zap_pid_ns_processes
  - kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_delete_elem
  - kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_update_elem
  - kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_lookup_elem
  - fs/fcntl.c:send_sigurg
  - fs/fcntl.c:send_sigio
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:next_tgid
  - fs/proc/base.c:proc_pid_attr_write
  - fs/proc/base.c:pid_getattr
  - fs/proc/base.c:proc_loginuid_write
  - fs/proc/array.c:get_children_pid
  - fs/proc/array.c:get_children_pid
  - fs/proc/fd.c:proc_fd_permission
  - fs/proc/proc_net.c:get_proc_task_net
  - ipc/mqueue.c:__do_notify
```
**Symbols:**

```
ffffffff810c7df0-ffffffff810c7e20: pid_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct task_struct *pid_task(struct pid *pid, enum pid_type type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810c9e82)
Location: kernel/pid.c:396
Inline: True
Inline callers:
  - kernel/pid.c:pidfd_getfd
  - kernel/pid.c:find_get_task_by_vpid
Direct callers:
  - kernel/exit.c:thread_group_exited
  - kernel/exit.c:do_wait
  - kernel/exit.c:do_wait
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:kill_pid_usb_asyncio
  - kernel/signal.c:kill_pid_info
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__do_sys_setpgid
  - kernel/nsproxy.c:validate_nsset
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_get
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_del
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_get
  - kernel/time/posix-cpu-timers.c:pid_for_clock
  - kernel/pid_namespace.c:zap_pid_ns_processes
  - kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_delete_elem
  - kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_update_elem
  - kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_lookup_elem
  - fs/fcntl.c:send_sigurg
  - fs/fcntl.c:send_sigio
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:f_getown
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:next_tgid
  - fs/proc/base.c:proc_pid_attr_write
  - fs/proc/base.c:pid_getattr
  - fs/proc/base.c:proc_loginuid_write
  - fs/proc/array.c:get_children_pid
  - fs/proc/array.c:get_children_pid
  - fs/proc/fd.c:proc_fd_permission
  - fs/proc/proc_net.c:get_proc_task_net
  - ipc/mqueue.c:__do_notify
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
```
**Symbols:**

```
ffffffff810c9880-ffffffff810c98b1: pid_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct task_struct *pid_task(struct pid *pid, enum pid_type type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810dcc72)
Location: kernel/pid.c:396
Inline: True
Inline callers:
  - kernel/pid.c:pidfd_getfd
  - kernel/pid.c:find_get_task_by_vpid
Direct callers:
  - kernel/exit.c:thread_group_exited
  - kernel/exit.c:do_wait
  - kernel/exit.c:do_wait
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:kill_pid_usb_asyncio
  - kernel/signal.c:kill_pid_info
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__do_sys_setpgid
  - kernel/nsproxy.c:validate_nsset
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_get
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_del
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_get
  - kernel/time/posix-cpu-timers.c:pid_for_clock
  - kernel/pid_namespace.c:zap_pid_ns_processes
  - kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_delete_elem
  - kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_update_elem
  - kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_lookup_elem
  - fs/fcntl.c:send_sigurg
  - fs/fcntl.c:send_sigio
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:f_getown
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:next_tgid
  - fs/proc/base.c:proc_pid_attr_write
  - fs/proc/base.c:pid_getattr
  - fs/proc/base.c:proc_loginuid_write
  - fs/proc/array.c:get_children_pid
  - fs/proc/array.c:get_children_pid
  - fs/proc/fd.c:proc_fd_permission
  - fs/proc/proc_net.c:get_proc_task_net
  - ipc/mqueue.c:__do_notify
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
```
**Symbols:**

```
ffffffff810dc7c0-ffffffff810dc816: pid_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct task_struct *pid_task(struct pid *pid, enum pid_type type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810f64ed)
Location: kernel/pid.c:396
Inline: True
Inline callers:
  - kernel/pid.c:pidfd_getfd
  - kernel/pid.c:pidfd_get_task
  - kernel/pid.c:find_get_task_by_vpid
Direct callers:
  - kernel/exit.c:thread_group_exited
  - kernel/exit.c:do_wait
  - kernel/exit.c:do_wait
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:kill_pid
  - kernel/signal.c:kill_pid_usb_asyncio
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__do_sys_setpgid
  - kernel/nsproxy.c:validate_nsset
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_get
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_del
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_get
  - kernel/time/posix-cpu-timers.c:pid_for_clock
  - kernel/pid_namespace.c:zap_pid_ns_processes
  - kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_delete_elem
  - kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_update_elem
  - kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_lookup_elem
  - fs/fcntl.c:send_sigurg
  - fs/fcntl.c:send_sigio
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:f_getown
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:next_tgid
  - fs/proc/base.c:proc_pid_attr_write
  - fs/proc/base.c:pid_revalidate
  - fs/proc/base.c:pid_getattr
  - fs/proc/base.c:proc_loginuid_write
  - fs/proc/array.c:get_children_pid
  - fs/proc/array.c:get_children_pid
  - fs/proc/fd.c:proc_fd_permission
  - fs/proc/proc_net.c:get_proc_task_net
  - ipc/mqueue.c:__do_notify
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
```
**Symbols:**

```
ffffffff810f5f50-ffffffff810f5fbe: pid_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct task_struct *pid_task(struct pid *pid, enum pid_type type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff81118b7d)
Location: kernel/pid.c:396
Inline: True
Inline callers:
  - kernel/pid.c:pidfd_getfd
  - kernel/pid.c:pidfd_get_task
  - kernel/pid.c:find_get_task_by_vpid
Direct callers:
  - kernel/exit.c:thread_group_exited
  - kernel/exit.c:do_wait
  - kernel/exit.c:do_wait
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:kill_pid
  - kernel/signal.c:kill_pid_usb_asyncio
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__do_sys_setpgid
  - kernel/nsproxy.c:validate_nsset
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_get
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_del
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_get
  - kernel/time/posix-cpu-timers.c:pid_for_clock
  - kernel/pid_namespace.c:zap_pid_ns_processes
  - kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_delete_elem
  - kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_update_elem
  - kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_lookup_elem
  - fs/fcntl.c:send_sigurg
  - fs/fcntl.c:send_sigio
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:f_getown
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:next_tgid
  - fs/proc/base.c:proc_pid_attr_write
  - fs/proc/base.c:pid_revalidate
  - fs/proc/base.c:pid_getattr
  - fs/proc/base.c:proc_loginuid_write
  - fs/proc/array.c:get_children_pid
  - fs/proc/array.c:get_children_pid
  - fs/proc/fd.c:proc_fd_permission
  - fs/proc/proc_net.c:get_proc_task_net
  - ipc/mqueue.c:__do_notify
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
```
**Symbols:**

```
ffffffff811184a0-ffffffff8111850f: pid_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct task_struct *pid_task(struct pid *pid, enum pid_type type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff8112603d)
Location: kernel/pid.c:399
Inline: True
Inline callers:
  - kernel/pid.c:pidfd_getfd
  - kernel/pid.c:pidfd_get_task
  - kernel/pid.c:find_get_task_by_vpid
Direct callers:
  - kernel/exit.c:thread_group_exited
  - kernel/exit.c:do_wait
  - kernel/exit.c:do_wait
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:kill_pid
  - kernel/signal.c:kill_pid_usb_asyncio
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__do_sys_setpgid
  - kernel/nsproxy.c:validate_nsset
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_get
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_del
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_get
  - kernel/time/posix-cpu-timers.c:pid_for_clock
  - kernel/pid_namespace.c:zap_pid_ns_processes
  - kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_delete_elem
  - kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_update_elem
  - kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_lookup_elem
  - fs/fcntl.c:send_sigurg
  - fs/fcntl.c:send_sigio
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:f_getown
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:next_tgid
  - fs/proc/base.c:proc_pid_attr_write
  - fs/proc/base.c:pid_revalidate
  - fs/proc/base.c:pid_getattr
  - fs/proc/base.c:proc_loginuid_write
  - fs/proc/array.c:get_children_pid
  - fs/proc/array.c:get_children_pid
  - fs/proc/fd.c:proc_fd_permission
  - fs/proc/proc_net.c:get_proc_task_net
  - ipc/mqueue.c:__do_notify
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
```
**Symbols:**

```
ffffffff811256e0-ffffffff8112574f: pid_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct task_struct *pid_task(struct pid *pid, enum pid_type type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff8113063d)
Location: kernel/pid.c:399
Inline: True
Inline callers:
  - kernel/pid.c:pidfd_getfd
  - kernel/pid.c:pidfd_get_task
  - kernel/pid.c:find_get_task_by_vpid
Direct callers:
  - kernel/exit.c:thread_group_exited
  - kernel/exit.c:__do_wait
  - kernel/exit.c:__do_wait
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:kill_pid
  - kernel/signal.c:kill_pid_usb_asyncio
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__do_sys_setpgid
  - kernel/nsproxy.c:validate_nsset
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_get
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_del
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_get
  - kernel/time/posix-cpu-timers.c:pid_for_clock
  - kernel/pid_namespace.c:zap_pid_ns_processes
  - kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_delete_elem
  - kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_update_elem
  - kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_lookup_elem
  - fs/fcntl.c:send_sigurg
  - fs/fcntl.c:send_sigio
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:f_getown
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:next_tgid
  - fs/proc/base.c:proc_pid_attr_write
  - fs/proc/base.c:pid_revalidate
  - fs/proc/base.c:pid_getattr
  - fs/proc/base.c:proc_loginuid_write
  - fs/proc/array.c:get_children_pid
  - fs/proc/array.c:get_children_pid
  - fs/proc/fd.c:proc_fd_permission
  - fs/proc/proc_net.c:get_proc_task_net
  - ipc/mqueue.c:__do_notify
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/gpu/drm/drm_debugfs.c:drm_clients_info
```
**Symbols:**

```
ffffffff8112fce0-ffffffff8112fd4e: pid_task (STB_GLOBAL)
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
struct task_struct *pid_task(struct pid *pid, enum pid_type type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffff80001012437c)
Location: kernel/pid.c:329
Inline: True
Inline callers:
  - kernel/pid.c:__arm64_sys_pidfd_open
  - kernel/pid.c:get_pid_task
  - kernel/pid.c:find_task_by_vpid
Direct callers:
  - kernel/fork.c:pidfd_poll
  - kernel/fork.c:pidfd_poll
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:kill_pid_usb_asyncio
  - kernel/signal.c:kill_pid_info
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__arm64_sys_setpgid
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/pid_namespace.c:zap_pid_ns_processes
  - fs/fcntl.c:send_sigurg
  - fs/fcntl.c:send_sigio
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:next_tgid
  - fs/proc/base.c:proc_pid_attr_write
  - fs/proc/base.c:pid_getattr
  - fs/proc/base.c:proc_loginuid_write
  - fs/proc/array.c:get_children_pid
  - fs/proc/array.c:get_children_pid
  - fs/proc/fd.c:proc_fd_permission
  - fs/proc/proc_net.c:get_proc_task_net
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
```
**Symbols:**

```
ffff800010123ea8-ffff800010123f04: pid_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct task_struct *pid_task(struct pid *pid, enum pid_type type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (c0377d1c)
Location: kernel/pid.c:329
Inline: True
Inline callers:
  - kernel/pid.c:__se_sys_pidfd_open
  - kernel/pid.c:get_pid_task
  - kernel/pid.c:find_task_by_vpid
Direct callers:
  - kernel/fork.c:pidfd_poll
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:kill_pid_usb_asyncio
  - kernel/signal.c:kill_pid_info
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__se_sys_setpgid
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/pid_namespace.c:zap_pid_ns_processes
  - fs/fcntl.c:send_sigurg
  - fs/fcntl.c:send_sigio
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:next_tgid
  - fs/proc/base.c:proc_pid_attr_write
  - fs/proc/base.c:pid_getattr
  - fs/proc/base.c:proc_loginuid_write
  - fs/proc/array.c:get_children_pid
  - fs/proc/array.c:get_children_pid
  - fs/proc/fd.c:proc_fd_permission
  - fs/proc/proc_net.c:get_proc_task_net
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
```
**Symbols:**

```
c037724c-c0377288: pid_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct task_struct *pid_task(struct pid *pid, enum pid_type type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (c00000000016dfb4)
Location: kernel/pid.c:329
Inline: True
Inline callers:
  - kernel/pid.c:__se_sys_pidfd_open
  - kernel/pid.c:get_pid_task
  - kernel/pid.c:find_task_by_vpid
Direct callers:
  - kernel/fork.c:pidfd_poll
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:kill_pid_usb_asyncio
  - kernel/signal.c:kill_pid_info
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__se_sys_setpgid
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/pid_namespace.c:zap_pid_ns_processes
  - fs/fcntl.c:send_sigurg
  - fs/fcntl.c:send_sigio
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:next_tgid
  - fs/proc/base.c:proc_pid_attr_write
  - fs/proc/base.c:pid_getattr
  - fs/proc/base.c:proc_loginuid_write
  - fs/proc/array.c:get_children_pid
  - fs/proc/array.c:get_children_pid
  - fs/proc/fd.c:proc_fd_permission
  - fs/proc/proc_net.c:get_proc_task_net
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
```
**Symbols:**

```
c00000000016dab0-c00000000016daf8: pid_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct task_struct *pid_task(struct pid *pid, enum pid_type type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffe0000dcd10)
Location: kernel/pid.c:329
Inline: True
Inline callers:
  - kernel/pid.c:__se_sys_pidfd_open
  - kernel/pid.c:get_pid_task
  - kernel/pid.c:find_task_by_vpid
Direct callers:
  - kernel/fork.c:pidfd_poll
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:kill_pid_usb_asyncio
  - kernel/signal.c:kill_pid_info
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__se_sys_setpgid
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/pid_namespace.c:zap_pid_ns_processes
  - fs/fcntl.c:send_sigurg
  - fs/fcntl.c:send_sigio
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:next_tgid
  - fs/proc/base.c:proc_pid_attr_write
  - fs/proc/base.c:pid_getattr
  - fs/proc/base.c:proc_loginuid_write
  - fs/proc/array.c:get_children_pid
  - fs/proc/array.c:get_children_pid
  - fs/proc/fd.c:proc_fd_permission
  - fs/proc/proc_net.c:get_proc_task_net
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
```
**Symbols:**

```
ffffffe0000dc102-ffffffe0000dc156: pid_task (STB_GLOBAL)
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
struct task_struct *pid_task(struct pid *pid, enum pid_type type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810c00bc)
Location: kernel/pid.c:329
Inline: True
Inline callers:
  - kernel/pid.c:__ia32_sys_pidfd_open
  - kernel/pid.c:__x64_sys_pidfd_open
  - kernel/pid.c:get_pid_task
  - kernel/pid.c:find_task_by_vpid
Direct callers:
  - kernel/fork.c:pidfd_poll
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:kill_pid_usb_asyncio
  - kernel/signal.c:kill_pid_info
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__ia32_sys_setpgid
  - kernel/sys.c:__x64_sys_setpgid
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/pid_namespace.c:zap_pid_ns_processes
  - fs/fcntl.c:send_sigurg
  - fs/fcntl.c:send_sigio
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:next_tgid
  - fs/proc/base.c:proc_pid_attr_write
  - fs/proc/base.c:pid_getattr
  - fs/proc/base.c:proc_loginuid_write
  - fs/proc/array.c:get_children_pid
  - fs/proc/array.c:get_children_pid
  - fs/proc/fd.c:proc_fd_permission
  - fs/proc/proc_net.c:get_proc_task_net
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
```
**Symbols:**

```
ffffffff810bfce0-ffffffff810bfd11: pid_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct task_struct *pid_task(struct pid *pid, enum pid_type type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810ae8cc)
Location: kernel/pid.c:329
Inline: True
Inline callers:
  - kernel/pid.c:__ia32_sys_pidfd_open
  - kernel/pid.c:__x64_sys_pidfd_open
  - kernel/pid.c:get_pid_task
  - kernel/pid.c:find_task_by_vpid
Direct callers:
  - kernel/fork.c:pidfd_poll
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:kill_pid_usb_asyncio
  - kernel/signal.c:kill_pid_info
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__ia32_sys_setpgid
  - kernel/sys.c:__x64_sys_setpgid
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/pid_namespace.c:zap_pid_ns_processes
  - fs/fcntl.c:send_sigurg
  - fs/fcntl.c:send_sigio
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:next_tgid
  - fs/proc/base.c:proc_pid_attr_write
  - fs/proc/base.c:pid_getattr
  - fs/proc/base.c:proc_loginuid_write
  - fs/proc/array.c:get_children_pid
  - fs/proc/array.c:get_children_pid
  - fs/proc/fd.c:proc_fd_permission
  - fs/proc/proc_net.c:get_proc_task_net
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
```
**Symbols:**

```
ffffffff810ae500-ffffffff810ae530: pid_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct task_struct *pid_task(struct pid *pid, enum pid_type type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810bf60c)
Location: kernel/pid.c:329
Inline: True
Inline callers:
  - kernel/pid.c:__ia32_sys_pidfd_open
  - kernel/pid.c:__x64_sys_pidfd_open
  - kernel/pid.c:get_pid_task
  - kernel/pid.c:find_task_by_vpid
Direct callers:
  - kernel/fork.c:pidfd_poll
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:kill_pid_usb_asyncio
  - kernel/signal.c:kill_pid_info
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__ia32_sys_setpgid
  - kernel/sys.c:__x64_sys_setpgid
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/pid_namespace.c:zap_pid_ns_processes
  - fs/fcntl.c:send_sigurg
  - fs/fcntl.c:send_sigio
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:next_tgid
  - fs/proc/base.c:proc_pid_attr_write
  - fs/proc/base.c:pid_getattr
  - fs/proc/base.c:proc_loginuid_write
  - fs/proc/array.c:get_children_pid
  - fs/proc/array.c:get_children_pid
  - fs/proc/fd.c:proc_fd_permission
  - fs/proc/proc_net.c:get_proc_task_net
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
```
**Symbols:**

```
ffffffff810bf240-ffffffff810bf270: pid_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct task_struct *pid_task(struct pid *pid, enum pid_type type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810c7a01)
Location: kernel/pid.c:329
Inline: True
Inline callers:
  - kernel/pid.c:__ia32_sys_pidfd_open
  - kernel/pid.c:__x64_sys_pidfd_open
  - kernel/pid.c:get_pid_task
  - kernel/pid.c:find_task_by_vpid
Direct callers:
  - kernel/fork.c:pidfd_poll
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:kill_pid_usb_asyncio
  - kernel/signal.c:kill_pid_info
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__ia32_sys_setpgid
  - kernel/sys.c:__x64_sys_setpgid
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/pid_namespace.c:zap_pid_ns_processes
  - fs/fcntl.c:send_sigurg
  - fs/fcntl.c:send_sigio
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:next_tgid
  - fs/proc/base.c:proc_pid_attr_write
  - fs/proc/base.c:pid_getattr
  - fs/proc/base.c:proc_loginuid_write
  - fs/proc/array.c:get_children_pid
  - fs/proc/array.c:get_children_pid
  - fs/proc/fd.c:proc_fd_permission
  - fs/proc/proc_net.c:get_proc_task_net
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
```
**Symbols:**

```
ffffffff810c75a0-ffffffff810c75d1: pid_task (STB_GLOBAL)
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
