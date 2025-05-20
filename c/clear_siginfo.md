# Function: <code>clear_siginfo</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/entry/common.c (ffffffff81003dd5)
Location: include/linux/signal.h:19
Inline: True
Inline callers:
  - arch/x86/entry/common.c:tracehook_report_syscall_exit
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff81005081)
Location: include/linux/signal.h:19
Inline: True
```
```
In arch/x86/kernel/traps.c (ffffffff8102e491)
Location: include/linux/signal.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:math_error
  - arch/x86/kernel/traps.c:do_error_trap
```
```
In arch/x86/kernel/ptrace.c (ffffffff8103e9ed)
Location: include/linux/signal.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:send_sigtrap
```
```
In arch/x86/kernel/umip.c (ffffffff8106fe31)
Location: include/linux/signal.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/umip.c:force_sig_info_umip_fault
```
```
In arch/x86/mm/fault.c (ffffffff81074cc3)
Location: include/linux/signal.h:19
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:force_sig_info_fault
```
```
In kernel/signal.c (ffffffff8109f5a8)
Location: include/linux/signal.h:19
Inline: True
Inline callers:
  - kernel/signal.c:do_tkill
  - kernel/signal.c:__do_sys_kill
  - kernel/signal.c:copy_siginfo_from_user32
  - kernel/signal.c:get_signal
  - kernel/signal.c:ptrace_do_notify
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
  - kernel/signal.c:force_sig_ptrace_errno_trap
  - kernel/signal.c:force_sig_pkuerr
  - kernel/signal.c:force_sig_bnderr
  - kernel/signal.c:send_sig_mceerr
  - kernel/signal.c:force_sig_mceerr
  - kernel/signal.c:send_sig_fault
  - kernel/signal.c:force_sig_fault
  - kernel/signal.c:__send_signal
  - kernel/signal.c:__send_signal
  - kernel/signal.c:__dequeue_signal
```
```
In kernel/time/posix-timers.c (ffffffff8111f825)
Location: include/linux/signal.h:19
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/seccomp.c (ffffffff8116abc5)
Location: include/linux/signal.h:19
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_init_siginfo
```
```
In fs/fcntl.c (ffffffff812ae3e9)
Location: include/linux/signal.h:19
Inline: True
Inline callers:
  - fs/fcntl.c:send_sigio_to_task
```
```
In ipc/mqueue.c (ffffffff813e04c9)
Location: include/linux/signal.h:19
Inline: True
Inline callers:
  - ipc/mqueue.c:__do_notify
```
```
In drivers/usb/core/devio.c (ffffffff817678e3)
Location: include/linux/signal.h:19
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_remove
  - drivers/usb/core/devio.c:async_completed
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810a7852)
Location: include/linux/signal.h:20
Inline: True
Inline callers:
  - kernel/signal.c:do_tkill
  - kernel/signal.c:__ia32_sys_kill
  - kernel/signal.c:__x64_sys_kill
  - kernel/signal.c:post_copy_siginfo_from_user32
  - kernel/signal.c:get_signal
  - kernel/signal.c:ptrace_do_notify
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
  - kernel/signal.c:force_sig_ptrace_errno_trap
  - kernel/signal.c:force_sig_pkuerr
  - kernel/signal.c:force_sig_bnderr
  - kernel/signal.c:send_sig_mceerr
  - kernel/signal.c:force_sig_mceerr
  - kernel/signal.c:send_sig_fault
  - kernel/signal.c:force_sig_fault
  - kernel/signal.c:__send_signal
  - kernel/signal.c:__send_signal
  - kernel/signal.c:__dequeue_signal
```
```
In kernel/time/posix-timers.c (ffffffff8112aff5)
Location: include/linux/signal.h:20
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/seccomp.c (ffffffff81177d05)
Location: include/linux/signal.h:20
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_init_siginfo
```
```
In fs/fcntl.c (ffffffff812c350f)
Location: include/linux/signal.h:20
Inline: True
Inline callers:
  - fs/fcntl.c:send_sigio_to_task
```
```
In ipc/mqueue.c (ffffffff813facd3)
Location: include/linux/signal.h:20
Inline: True
Inline callers:
  - ipc/mqueue.c:__do_notify
```
```
In drivers/usb/core/devio.c (ffffffff8178d472)
Location: include/linux/signal.h:20
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_notify
  - drivers/usb/core/devio.c:async_completed
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810adfed)
Location: include/linux/signal.h:20
Inline: True
Inline callers:
  - kernel/signal.c:do_tkill
  - kernel/signal.c:__ia32_sys_pidfd_send_signal
  - kernel/signal.c:__x64_sys_pidfd_send_signal
  - kernel/signal.c:__ia32_sys_kill
  - kernel/signal.c:__x64_sys_kill
  - kernel/signal.c:post_copy_siginfo_from_user32
  - kernel/signal.c:get_signal
  - kernel/signal.c:ptrace_do_notify
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
  - kernel/signal.c:force_sig_ptrace_errno_trap
  - kernel/signal.c:force_sig_pkuerr
  - kernel/signal.c:force_sig_bnderr
  - kernel/signal.c:send_sig_mceerr
  - kernel/signal.c:force_sig_mceerr
  - kernel/signal.c:send_sig_fault
  - kernel/signal.c:force_sig_fault
  - kernel/signal.c:force_sig
  - kernel/signal.c:kill_pid_usb_asyncio
  - kernel/signal.c:__send_signal
  - kernel/signal.c:__send_signal
  - kernel/signal.c:__dequeue_signal
```
```
In kernel/time/posix-timers.c (ffffffff81136068)
Location: include/linux/signal.h:20
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/seccomp.c (ffffffff81184aa5)
Location: include/linux/signal.h:20
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_init_siginfo
```
```
In fs/fcntl.c (ffffffff812dff21)
Location: include/linux/signal.h:20
Inline: True
Inline callers:
  - fs/fcntl.c:send_sigio_to_task
```
```
In ipc/mqueue.c (ffffffff814270f0)
Location: include/linux/signal.h:20
Inline: True
Inline callers:
  - ipc/mqueue.c:__do_notify
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b45fd)
Location: include/linux/signal.h:20
Inline: True
Inline callers:
  - kernel/signal.c:do_tkill
  - kernel/signal.c:__ia32_sys_pidfd_send_signal
  - kernel/signal.c:__x64_sys_pidfd_send_signal
  - kernel/signal.c:__ia32_sys_kill
  - kernel/signal.c:__x64_sys_kill
  - kernel/signal.c:post_copy_siginfo_from_user32
  - kernel/signal.c:get_signal
  - kernel/signal.c:ptrace_do_notify
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
  - kernel/signal.c:force_sig_ptrace_errno_trap
  - kernel/signal.c:force_sig_pkuerr
  - kernel/signal.c:force_sig_bnderr
  - kernel/signal.c:send_sig_mceerr
  - kernel/signal.c:force_sig_mceerr
  - kernel/signal.c:send_sig_fault
  - kernel/signal.c:force_sig_fault
  - kernel/signal.c:force_sig
  - kernel/signal.c:kill_pid_usb_asyncio
  - kernel/signal.c:__send_signal
  - kernel/signal.c:__send_signal
  - kernel/signal.c:__dequeue_signal
```
```
In kernel/time/posix-timers.c (ffffffff81142108)
Location: include/linux/signal.h:20
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/seccomp.c (ffffffff81190925)
Location: include/linux/signal.h:20
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_init_siginfo
```
```
In fs/fcntl.c (ffffffff812f19c1)
Location: include/linux/signal.h:20
Inline: True
Inline callers:
  - fs/fcntl.c:send_sigio_to_task
```
```
In ipc/mqueue.c (ffffffff81440e30)
Location: include/linux/signal.h:20
Inline: True
Inline callers:
  - ipc/mqueue.c:__do_notify
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810bcb38)
Location: include/linux/signal.h:20
Inline: True
Inline callers:
  - kernel/signal.c:do_tkill
  - kernel/signal.c:__do_sys_pidfd_send_signal
  - kernel/signal.c:__ia32_sys_kill
  - kernel/signal.c:__x64_sys_kill
  - kernel/signal.c:post_copy_siginfo_from_user32
  - kernel/signal.c:ptrace_signal
  - kernel/signal.c:ptrace_do_notify
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
  - kernel/signal.c:force_sig_ptrace_errno_trap
  - kernel/signal.c:force_sig_pkuerr
  - kernel/signal.c:force_sig_bnderr
  - kernel/signal.c:send_sig_mceerr
  - kernel/signal.c:force_sig_mceerr
  - kernel/signal.c:send_sig_fault
  - kernel/signal.c:force_sig_fault
  - kernel/signal.c:force_sigsegv
  - kernel/signal.c:kill_pid_usb_asyncio
  - kernel/signal.c:__send_signal
  - kernel/signal.c:__send_signal
  - kernel/signal.c:collect_signal
```
```
In kernel/time/posix-timers.c (ffffffff81150a68)
Location: include/linux/signal.h:20
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/seccomp.c (ffffffff811a67c4)
Location: include/linux/signal.h:20
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
```
```
In fs/fcntl.c (ffffffff81329b61)
Location: include/linux/signal.h:20
Inline: True
Inline callers:
  - fs/fcntl.c:send_sigio_to_task
```
```
In ipc/mqueue.c (ffffffff81491bfe)
Location: include/linux/signal.h:20
Inline: True
Inline callers:
  - ipc/mqueue.c:__do_notify
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b7e58)
Location: include/linux/signal.h:20
Inline: True
Inline callers:
  - kernel/signal.c:do_tkill
  - kernel/signal.c:__do_sys_pidfd_send_signal
  - kernel/signal.c:__ia32_sys_kill
  - kernel/signal.c:__x64_sys_kill
  - kernel/signal.c:post_copy_siginfo_from_user32
  - kernel/signal.c:ptrace_signal
  - kernel/signal.c:ptrace_do_notify
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
  - kernel/signal.c:force_sig_ptrace_errno_trap
  - kernel/signal.c:force_sig_pkuerr
  - kernel/signal.c:force_sig_bnderr
  - kernel/signal.c:send_sig_mceerr
  - kernel/signal.c:force_sig_mceerr
  - kernel/signal.c:send_sig_fault
  - kernel/signal.c:force_sig_fault
  - kernel/signal.c:force_sigsegv
  - kernel/signal.c:kill_pid_usb_asyncio
  - kernel/signal.c:__send_signal
  - kernel/signal.c:__send_signal
  - kernel/signal.c:collect_signal
```
```
In kernel/entry/syscall_user_dispatch.c (ffffffff8113bcaf)
Location: include/linux/signal.h:20
Inline: True
Inline callers:
  - kernel/entry/syscall_user_dispatch.c:syscall_user_dispatch
```
```
In kernel/time/posix-timers.c (ffffffff8114cce8)
Location: include/linux/signal.h:20
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/seccomp.c (ffffffff811a3dd4)
Location: include/linux/signal.h:20
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
```
```
In fs/fcntl.c (ffffffff813350cb)
Location: include/linux/signal.h:20
Inline: True
Inline callers:
  - fs/fcntl.c:send_sigio_to_task
```
```
In ipc/mqueue.c (ffffffff814af930)
Location: include/linux/signal.h:20
Inline: True
Inline callers:
  - ipc/mqueue.c:__do_notify
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b93b8)
Location: include/linux/signal.h:20
Inline: True
Inline callers:
  - kernel/signal.c:do_tkill
  - kernel/signal.c:__do_sys_pidfd_send_signal
  - kernel/signal.c:__ia32_sys_kill
  - kernel/signal.c:__x64_sys_kill
  - kernel/signal.c:post_copy_siginfo_from_user32
  - kernel/signal.c:get_signal
  - kernel/signal.c:ptrace_do_notify
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
  - kernel/signal.c:force_sig_ptrace_errno_trap
  - kernel/signal.c:force_sig_perf
  - kernel/signal.c:force_sig_pkuerr
  - kernel/signal.c:force_sig_bnderr
  - kernel/signal.c:send_sig_mceerr
  - kernel/signal.c:force_sig_mceerr
  - kernel/signal.c:send_sig_fault
  - kernel/signal.c:force_sig_fault
  - kernel/signal.c:force_sigsegv
  - kernel/signal.c:kill_pid_usb_asyncio
  - kernel/signal.c:__send_signal
  - kernel/signal.c:__send_signal
  - kernel/signal.c:collect_signal
```
```
In kernel/entry/syscall_user_dispatch.c (ffffffff8113cf9f)
Location: include/linux/signal.h:20
Inline: True
Inline callers:
  - kernel/entry/syscall_user_dispatch.c:syscall_user_dispatch
```
```
In kernel/time/posix-timers.c (ffffffff8114f0f5)
Location: include/linux/signal.h:20
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/seccomp.c (ffffffff811a47a1)
Location: include/linux/signal.h:20
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
```
```
In fs/fcntl.c (ffffffff8133b25b)
Location: include/linux/signal.h:20
Inline: True
Inline callers:
  - fs/fcntl.c:send_sigio_to_task
```
```
In ipc/mqueue.c (ffffffff814b5770)
Location: include/linux/signal.h:20
Inline: True
Inline callers:
  - ipc/mqueue.c:__do_notify
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810cb9c8)
Location: include/linux/signal.h:20
Inline: True
Inline callers:
  - kernel/signal.c:do_tkill
  - kernel/signal.c:__do_sys_pidfd_send_signal
  - kernel/signal.c:__ia32_sys_kill
  - kernel/signal.c:__x64_sys_kill
  - kernel/signal.c:post_copy_siginfo_from_user32
  - kernel/signal.c:signal_setup_done
  - kernel/signal.c:get_signal
  - kernel/signal.c:ptrace_do_notify
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
  - kernel/signal.c:send_sig_fault_trapno
  - kernel/signal.c:force_sig_fault_trapno
  - kernel/signal.c:force_sig_ptrace_errno_trap
  - kernel/signal.c:force_sig_seccomp
  - kernel/signal.c:force_sig_perf
  - kernel/signal.c:force_sig_pkuerr
  - kernel/signal.c:force_sig_bnderr
  - kernel/signal.c:send_sig_mceerr
  - kernel/signal.c:force_sig_mceerr
  - kernel/signal.c:send_sig_fault
  - kernel/signal.c:force_sig_fault
  - kernel/signal.c:force_exit_sig
  - kernel/signal.c:kill_pid_usb_asyncio
  - kernel/signal.c:__send_signal
  - kernel/signal.c:__send_signal
  - kernel/signal.c:collect_signal
```
```
In kernel/entry/syscall_user_dispatch.c (ffffffff811600bf)
Location: include/linux/signal.h:20
Inline: True
Inline callers:
  - kernel/entry/syscall_user_dispatch.c:syscall_user_dispatch
```
```
In kernel/time/posix-timers.c (ffffffff811732b2)
Location: include/linux/signal.h:20
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:do_timer_create
```
```
In fs/fcntl.c (ffffffff81388e7b)
Location: include/linux/signal.h:20
Inline: True
Inline callers:
  - fs/fcntl.c:send_sigio_to_task
```
```
In ipc/mqueue.c (ffffffff8150de60)
Location: include/linux/signal.h:20
Inline: True
Inline callers:
  - ipc/mqueue.c:__do_notify
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810e2a92)
Location: include/linux/signal.h:20
Inline: True
Inline callers:
  - kernel/signal.c:do_tkill
  - kernel/signal.c:__do_sys_pidfd_send_signal
  - kernel/signal.c:__ia32_sys_kill
  - kernel/signal.c:__x64_sys_kill
  - kernel/signal.c:post_copy_siginfo_from_user32
  - kernel/signal.c:signal_setup_done
  - kernel/signal.c:signal_setup_done
  - kernel/signal.c:ptrace_signal
  - kernel/signal.c:ptrace_do_notify
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
  - kernel/signal.c:send_sig_fault_trapno
  - kernel/signal.c:force_sig_fault_trapno
  - kernel/signal.c:force_sig_ptrace_errno_trap
  - kernel/signal.c:force_sig_seccomp
  - kernel/signal.c:send_sig_perf
  - kernel/signal.c:force_sig_pkuerr
  - kernel/signal.c:force_sig_bnderr
  - kernel/signal.c:send_sig_mceerr
  - kernel/signal.c:force_sig_mceerr
  - kernel/signal.c:send_sig_fault
  - kernel/signal.c:force_sig_fault
  - kernel/signal.c:force_exit_sig
  - kernel/signal.c:kill_pid_usb_asyncio
  - kernel/signal.c:__send_signal_locked
  - kernel/signal.c:__send_signal_locked
  - kernel/signal.c:collect_signal
```
```
In kernel/entry/syscall_user_dispatch.c (ffffffff8118a595)
Location: include/linux/signal.h:20
Inline: True
Inline callers:
  - kernel/entry/syscall_user_dispatch.c:syscall_user_dispatch
```
```
In kernel/time/posix-timers.c (ffffffff811a65d9)
Location: include/linux/signal.h:20
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:do_timer_create
```
```
In fs/fcntl.c (ffffffff8140a10a)
Location: include/linux/signal.h:20
Inline: True
Inline callers:
  - fs/fcntl.c:send_sigio_to_task
```
```
In ipc/mqueue.c (ffffffff815a0925)
Location: include/linux/signal.h:20
Inline: True
Inline callers:
  - ipc/mqueue.c:__do_notify
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81102ef2)
Location: include/linux/signal.h:20
Inline: True
Inline callers:
  - kernel/signal.c:do_tkill
  - kernel/signal.c:__do_sys_pidfd_send_signal
  - kernel/signal.c:__ia32_sys_kill
  - kernel/signal.c:__x64_sys_kill
  - kernel/signal.c:post_copy_siginfo_from_user32
  - kernel/signal.c:signal_setup_done
  - kernel/signal.c:signal_setup_done
  - kernel/signal.c:get_signal
  - kernel/signal.c:ptrace_signal
  - kernel/signal.c:ptrace_do_notify
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
  - kernel/signal.c:send_sig_fault_trapno
  - kernel/signal.c:force_sig_fault_trapno
  - kernel/signal.c:force_sig_ptrace_errno_trap
  - kernel/signal.c:force_sig_seccomp
  - kernel/signal.c:send_sig_perf
  - kernel/signal.c:force_sig_pkuerr
  - kernel/signal.c:force_sig_bnderr
  - kernel/signal.c:send_sig_mceerr
  - kernel/signal.c:force_sig_mceerr
  - kernel/signal.c:send_sig_fault
  - kernel/signal.c:force_sig_fault
  - kernel/signal.c:force_exit_sig
  - kernel/signal.c:kill_pid_usb_asyncio
  - kernel/signal.c:__send_signal_locked
  - kernel/signal.c:__send_signal_locked
  - kernel/signal.c:collect_signal
```
```
In kernel/entry/syscall_user_dispatch.c (ffffffff811c6b35)
Location: include/linux/signal.h:20
Inline: True
Inline callers:
  - kernel/entry/syscall_user_dispatch.c:syscall_user_dispatch
```
```
In kernel/time/posix-timers.c (ffffffff811e6179)
Location: include/linux/signal.h:20
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:do_timer_create
```
```
In fs/fcntl.c (ffffffff81494a2a)
Location: include/linux/signal.h:20
Inline: True
Inline callers:
  - fs/fcntl.c:send_sigio_to_task
```
```
In ipc/mqueue.c (ffffffff8164a2b5)
Location: include/linux/signal.h:20
Inline: True
Inline callers:
  - ipc/mqueue.c:__do_notify
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8110f132)
Location: include/linux/signal.h:20
Inline: True
Inline callers:
  - kernel/signal.c:do_tkill
  - kernel/signal.c:__do_sys_pidfd_send_signal
  - kernel/signal.c:__ia32_sys_kill
  - kernel/signal.c:__x64_sys_kill
  - kernel/signal.c:post_copy_siginfo_from_user32
  - kernel/signal.c:signal_setup_done
  - kernel/signal.c:signal_setup_done
  - kernel/signal.c:get_signal
  - kernel/signal.c:ptrace_signal
  - kernel/signal.c:ptrace_do_notify
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
  - kernel/signal.c:send_sig_fault_trapno
  - kernel/signal.c:force_sig_fault_trapno
  - kernel/signal.c:force_sig_ptrace_errno_trap
  - kernel/signal.c:force_sig_seccomp
  - kernel/signal.c:send_sig_perf
  - kernel/signal.c:force_sig_pkuerr
  - kernel/signal.c:force_sig_bnderr
  - kernel/signal.c:send_sig_mceerr
  - kernel/signal.c:force_sig_mceerr
  - kernel/signal.c:send_sig_fault
  - kernel/signal.c:force_sig_fault
  - kernel/signal.c:force_exit_sig
  - kernel/signal.c:kill_pid_usb_asyncio
  - kernel/signal.c:__send_signal_locked
  - kernel/signal.c:__send_signal_locked
  - kernel/signal.c:collect_signal
```
```
In kernel/entry/syscall_user_dispatch.c (ffffffff811d9855)
Location: include/linux/signal.h:20
Inline: True
Inline callers:
  - kernel/entry/syscall_user_dispatch.c:syscall_user_dispatch
```
```
In kernel/time/posix-timers.c (ffffffff811fa7b8)
Location: include/linux/signal.h:20
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:do_timer_create
```
```
In fs/fcntl.c (ffffffff814c9a8a)
Location: include/linux/signal.h:20
Inline: True
Inline callers:
  - fs/fcntl.c:send_sigio_to_task
```
```
In ipc/mqueue.c (ffffffff816827fc)
Location: include/linux/signal.h:20
Inline: True
Inline callers:
  - ipc/mqueue.c:__do_notify
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81118ab2)
Location: include/linux/signal.h:21
Inline: True
Inline callers:
  - kernel/signal.c:do_tkill
  - kernel/signal.c:__do_sys_pidfd_send_signal
  - kernel/signal.c:__ia32_sys_kill
  - kernel/signal.c:__x64_sys_kill
  - kernel/signal.c:post_copy_siginfo_from_user32
  - kernel/signal.c:signal_setup_done
  - kernel/signal.c:signal_setup_done
  - kernel/signal.c:get_signal
  - kernel/signal.c:ptrace_signal
  - kernel/signal.c:ptrace_do_notify
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
  - kernel/signal.c:send_sig_fault_trapno
  - kernel/signal.c:force_sig_fault_trapno
  - kernel/signal.c:force_sig_ptrace_errno_trap
  - kernel/signal.c:force_sig_seccomp
  - kernel/signal.c:send_sig_perf
  - kernel/signal.c:force_sig_pkuerr
  - kernel/signal.c:force_sig_bnderr
  - kernel/signal.c:send_sig_mceerr
  - kernel/signal.c:force_sig_mceerr
  - kernel/signal.c:send_sig_fault
  - kernel/signal.c:force_sig_fault
  - kernel/signal.c:force_exit_sig
  - kernel/signal.c:kill_pid_usb_asyncio
  - kernel/signal.c:__send_signal_locked
  - kernel/signal.c:__send_signal_locked
  - kernel/signal.c:collect_signal
```
```
In kernel/entry/syscall_user_dispatch.c (ffffffff811ef505)
Location: include/linux/signal.h:21
Inline: True
Inline callers:
  - kernel/entry/syscall_user_dispatch.c:syscall_user_dispatch
```
```
In kernel/time/posix-timers.c (ffffffff812109a8)
Location: include/linux/signal.h:21
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:do_timer_create
```
```
In fs/fcntl.c (ffffffff814fc34a)
Location: include/linux/signal.h:21
Inline: True
Inline callers:
  - fs/fcntl.c:send_sigio_to_task
```
```
In ipc/mqueue.c (ffffffff816bebfc)
Location: include/linux/signal.h:21
Inline: True
Inline callers:
  - ipc/mqueue.c:__do_notify
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void clear_siginfo(kernel_siginfo_t *info);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/arm64/kernel/ptrace.c (0)
Location: include/linux/signal.h:20
Inline: False
```
```
In kernel/signal.c (ffff8000101106d8)
Location: include/linux/signal.h:20
Inline: True
Inline callers:
  - kernel/signal.c:do_tkill
  - kernel/signal.c:__arm64_sys_pidfd_send_signal
  - kernel/signal.c:__arm64_sys_kill
  - kernel/signal.c:post_copy_siginfo_from_user32
  - kernel/signal.c:get_signal
  - kernel/signal.c:ptrace_do_notify
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
  - kernel/signal.c:force_sig_ptrace_errno_trap
  - kernel/signal.c:force_sig_pkuerr
  - kernel/signal.c:force_sig_bnderr
  - kernel/signal.c:send_sig_mceerr
  - kernel/signal.c:force_sig_mceerr
  - kernel/signal.c:send_sig_fault
  - kernel/signal.c:force_sig_fault
  - kernel/signal.c:force_sig
  - kernel/signal.c:kill_pid_usb_asyncio
  - kernel/signal.c:__send_signal
  - kernel/signal.c:collect_signal
Direct callers:
  - kernel/signal.c:__send_signal
```
```
In kernel/time/posix-timers.c (ffff8000101ac21c)
Location: include/linux/signal.h:20
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/seccomp.c (ffff800010207ff4)
Location: include/linux/signal.h:20
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_init_siginfo
```
```
In fs/fcntl.c (ffff80001039b370)
Location: include/linux/signal.h:20
Inline: True
Inline callers:
  - fs/fcntl.c:send_sigio_to_task
```
```
In ipc/mqueue.c (ffff80001052992c)
Location: include/linux/signal.h:20
Inline: True
Inline callers:
  - ipc/mqueue.c:__do_notify
```
**Symbols:**

```
ffff80001010aa60-ffff80001010aa70: clear_siginfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/arm/kernel/ptrace.c (0)
Location: include/linux/signal.h:20
Inline: False
```
```
In kernel/signal.c (c03680a0)
Location: include/linux/signal.h:20
Inline: True
Inline callers:
  - kernel/signal.c:do_tkill
  - kernel/signal.c:__se_sys_pidfd_send_signal
  - kernel/signal.c:__se_sys_kill
  - kernel/signal.c:get_signal
  - kernel/signal.c:ptrace_do_notify
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
  - kernel/signal.c:force_sig_ptrace_errno_trap
  - kernel/signal.c:force_sig_pkuerr
  - kernel/signal.c:force_sig_bnderr
  - kernel/signal.c:send_sig_mceerr
  - kernel/signal.c:force_sig_mceerr
  - kernel/signal.c:send_sig_fault
  - kernel/signal.c:force_sig_fault
  - kernel/signal.c:force_sig
  - kernel/signal.c:kill_pid_usb_asyncio
  - kernel/signal.c:__send_signal
  - kernel/signal.c:__send_signal
  - kernel/signal.c:collect_signal
```
```
In kernel/time/posix-timers.c (c03f65cc)
Location: include/linux/signal.h:20
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/seccomp.c (c04482a8)
Location: include/linux/signal.h:20
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
```
```
In fs/fcntl.c (c05818f8)
Location: include/linux/signal.h:20
Inline: True
Inline callers:
  - fs/fcntl.c:send_sigio_to_task
```
```
In ipc/mqueue.c (c06e3bac)
Location: include/linux/signal.h:20
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_timedsend
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c000000000157eb0)
Location: include/linux/signal.h:20
Inline: True
Inline callers:
  - kernel/signal.c:do_tkill
  - kernel/signal.c:__se_sys_pidfd_send_signal
  - kernel/signal.c:__se_sys_kill
  - kernel/signal.c:post_copy_siginfo_from_user32
  - kernel/signal.c:get_signal
  - kernel/signal.c:ptrace_do_notify
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
  - kernel/signal.c:force_sig_ptrace_errno_trap
  - kernel/signal.c:force_sig_pkuerr
  - kernel/signal.c:force_sig_bnderr
  - kernel/signal.c:send_sig_mceerr
  - kernel/signal.c:force_sig_mceerr
  - kernel/signal.c:send_sig_fault
  - kernel/signal.c:force_sig_fault
  - kernel/signal.c:force_sig
  - kernel/signal.c:kill_pid_usb_asyncio
  - kernel/signal.c:__send_signal
  - kernel/signal.c:__send_signal
  - kernel/signal.c:collect_signal
```
```
In kernel/time/posix-timers.c (c00000000020fe70)
Location: include/linux/signal.h:20
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/seccomp.c (c000000000284bc8)
Location: include/linux/signal.h:20
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_init_siginfo
```
```
In fs/fcntl.c (c000000000496748)
Location: include/linux/signal.h:20
Inline: True
Inline callers:
  - fs/fcntl.c:send_sigio_to_task
```
```
In ipc/mqueue.c (c000000000675400)
Location: include/linux/signal.h:20
Inline: True
Inline callers:
  - ipc/mqueue.c:__do_notify
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/riscv/kernel/ptrace.c (0)
Location: include/linux/signal.h:20
Inline: True
```
```
In kernel/signal.c (ffffffe0000d0522)
Location: include/linux/signal.h:20
Inline: True
Inline callers:
  - kernel/signal.c:do_tkill
  - kernel/signal.c:__se_sys_pidfd_send_signal
  - kernel/signal.c:__se_sys_kill
  - kernel/signal.c:get_signal
  - kernel/signal.c:ptrace_do_notify
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
  - kernel/signal.c:force_sig_ptrace_errno_trap
  - kernel/signal.c:force_sig_pkuerr
  - kernel/signal.c:force_sig_bnderr
  - kernel/signal.c:send_sig_mceerr
  - kernel/signal.c:force_sig_mceerr
  - kernel/signal.c:send_sig_fault
  - kernel/signal.c:force_sig_fault_to_task
  - kernel/signal.c:force_sig
  - kernel/signal.c:kill_pid_usb_asyncio
  - kernel/signal.c:__send_signal
  - kernel/signal.c:__send_signal
  - kernel/signal.c:collect_signal
```
```
In kernel/time/posix-timers.c (ffffffe000136170)
Location: include/linux/signal.h:20
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/seccomp.c (ffffffe00016b58c)
Location: include/linux/signal.h:20
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
```
```
In fs/fcntl.c (ffffffe0002687b2)
Location: include/linux/signal.h:20
Inline: True
Inline callers:
  - fs/fcntl.c:send_sigio_to_task
```
```
In ipc/mqueue.c (ffffffe00038c804)
Location: include/linux/signal.h:20
Inline: True
Inline callers:
  - ipc/mqueue.c:__do_notify
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810ae96d)
Location: include/linux/signal.h:20
Inline: True
Inline callers:
  - kernel/signal.c:do_tkill
  - kernel/signal.c:__ia32_sys_pidfd_send_signal
  - kernel/signal.c:__x64_sys_pidfd_send_signal
  - kernel/signal.c:__ia32_sys_kill
  - kernel/signal.c:__x64_sys_kill
  - kernel/signal.c:post_copy_siginfo_from_user32
  - kernel/signal.c:get_signal
  - kernel/signal.c:ptrace_do_notify
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
  - kernel/signal.c:force_sig_ptrace_errno_trap
  - kernel/signal.c:force_sig_pkuerr
  - kernel/signal.c:force_sig_bnderr
  - kernel/signal.c:send_sig_mceerr
  - kernel/signal.c:force_sig_mceerr
  - kernel/signal.c:send_sig_fault
  - kernel/signal.c:force_sig_fault
  - kernel/signal.c:force_sig
  - kernel/signal.c:kill_pid_usb_asyncio
  - kernel/signal.c:__send_signal
  - kernel/signal.c:__send_signal
  - kernel/signal.c:__dequeue_signal
```
```
In kernel/time/posix-timers.c (ffffffff8113a8b8)
Location: include/linux/signal.h:20
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/seccomp.c (ffffffff81188f45)
Location: include/linux/signal.h:20
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_init_siginfo
```
```
In fs/fcntl.c (ffffffff812e9fa1)
Location: include/linux/signal.h:20
Inline: True
Inline callers:
  - fs/fcntl.c:send_sigio_to_task
```
```
In ipc/mqueue.c (ffffffff81439410)
Location: include/linux/signal.h:20
Inline: True
Inline callers:
  - ipc/mqueue.c:__do_notify
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8109d2bd)
Location: include/linux/signal.h:20
Inline: True
Inline callers:
  - kernel/signal.c:do_tkill
  - kernel/signal.c:__ia32_sys_pidfd_send_signal
  - kernel/signal.c:__x64_sys_pidfd_send_signal
  - kernel/signal.c:__ia32_sys_kill
  - kernel/signal.c:__x64_sys_kill
  - kernel/signal.c:post_copy_siginfo_from_user32
  - kernel/signal.c:get_signal
  - kernel/signal.c:ptrace_do_notify
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
  - kernel/signal.c:force_sig_ptrace_errno_trap
  - kernel/signal.c:force_sig_pkuerr
  - kernel/signal.c:force_sig_bnderr
  - kernel/signal.c:send_sig_mceerr
  - kernel/signal.c:force_sig_mceerr
  - kernel/signal.c:send_sig_fault
  - kernel/signal.c:force_sig_fault
  - kernel/signal.c:force_sig
  - kernel/signal.c:kill_pid_usb_asyncio
  - kernel/signal.c:__send_signal
  - kernel/signal.c:__send_signal
  - kernel/signal.c:__dequeue_signal
```
```
In kernel/time/posix-timers.c (ffffffff8112d308)
Location: include/linux/signal.h:20
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/seccomp.c (ffffffff8117c085)
Location: include/linux/signal.h:20
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_init_siginfo
```
```
In fs/fcntl.c (ffffffff812dad41)
Location: include/linux/signal.h:20
Inline: True
Inline callers:
  - fs/fcntl.c:send_sigio_to_task
```
```
In ipc/mqueue.c (ffffffff81429e80)
Location: include/linux/signal.h:20
Inline: True
Inline callers:
  - ipc/mqueue.c:__do_notify
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810adecd)
Location: include/linux/signal.h:20
Inline: True
Inline callers:
  - kernel/signal.c:do_tkill
  - kernel/signal.c:__ia32_sys_pidfd_send_signal
  - kernel/signal.c:__x64_sys_pidfd_send_signal
  - kernel/signal.c:__ia32_sys_kill
  - kernel/signal.c:__x64_sys_kill
  - kernel/signal.c:post_copy_siginfo_from_user32
  - kernel/signal.c:get_signal
  - kernel/signal.c:ptrace_do_notify
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
  - kernel/signal.c:force_sig_ptrace_errno_trap
  - kernel/signal.c:force_sig_pkuerr
  - kernel/signal.c:force_sig_bnderr
  - kernel/signal.c:send_sig_mceerr
  - kernel/signal.c:force_sig_mceerr
  - kernel/signal.c:send_sig_fault
  - kernel/signal.c:force_sig_fault
  - kernel/signal.c:force_sig
  - kernel/signal.c:kill_pid_usb_asyncio
  - kernel/signal.c:__send_signal
  - kernel/signal.c:__send_signal
  - kernel/signal.c:__dequeue_signal
```
```
In kernel/time/posix-timers.c (ffffffff811385d8)
Location: include/linux/signal.h:20
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/seccomp.c (ffffffff81186d15)
Location: include/linux/signal.h:20
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_init_siginfo
```
```
In fs/fcntl.c (ffffffff812e7db1)
Location: include/linux/signal.h:20
Inline: True
Inline callers:
  - fs/fcntl.c:send_sigio_to_task
```
```
In ipc/mqueue.c (ffffffff814355b0)
Location: include/linux/signal.h:20
Inline: True
Inline callers:
  - ipc/mqueue.c:__do_notify
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b613d)
Location: include/linux/signal.h:20
Inline: True
Inline callers:
  - kernel/signal.c:do_tkill
  - kernel/signal.c:__ia32_sys_pidfd_send_signal
  - kernel/signal.c:__x64_sys_pidfd_send_signal
  - kernel/signal.c:__ia32_sys_kill
  - kernel/signal.c:__x64_sys_kill
  - kernel/signal.c:post_copy_siginfo_from_user32
  - kernel/signal.c:get_signal
  - kernel/signal.c:ptrace_do_notify
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
  - kernel/signal.c:force_sig_ptrace_errno_trap
  - kernel/signal.c:force_sig_pkuerr
  - kernel/signal.c:force_sig_bnderr
  - kernel/signal.c:send_sig_mceerr
  - kernel/signal.c:force_sig_mceerr
  - kernel/signal.c:send_sig_fault
  - kernel/signal.c:force_sig_fault
  - kernel/signal.c:force_sig
  - kernel/signal.c:kill_pid_usb_asyncio
  - kernel/signal.c:__send_signal
  - kernel/signal.c:__send_signal
  - kernel/signal.c:__dequeue_signal
```
```
In kernel/time/posix-timers.c (ffffffff8114518a)
Location: include/linux/signal.h:20
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/seccomp.c (ffffffff81194665)
Location: include/linux/signal.h:20
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_init_siginfo
```
```
In fs/fcntl.c (ffffffff812f9029)
Location: include/linux/signal.h:20
Inline: True
Inline callers:
  - fs/fcntl.c:send_sigio_to_task
```
```
In ipc/mqueue.c (ffffffff8144cc50)
Location: include/linux/signal.h:20
Inline: True
Inline callers:
  - ipc/mqueue.c:__do_notify
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
