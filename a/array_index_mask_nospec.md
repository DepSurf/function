# Function: <code>array_index_mask_nospec</code>

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
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/entry/common.c (ffffffff81003d56)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - arch/x86/entry/common.c:do_fast_syscall_32
  - arch/x86/entry/common.c:do_int80_syscall_32
  - arch/x86/entry/common.c:do_syscall_64
```
```
In kernel/kcmp.c (ffffffff811041fe)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - kernel/kcmp.c:SyS_kcmp
  - kernel/kcmp.c:get_file_raw_ptr
```
```
In kernel/time/posix-timers.c (ffffffff81112e2e)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
```
```
In fs/file.c (ffffffff8129696c)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - fs/file.c:SyS_dup2
  - fs/file.c:SyS_dup2
  - fs/file.c:__fget
```
```
In fs/notify/dnotify/dnotify.c (ffffffff812bdc20)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
```
```
In fs/locks.c (ffffffff812d6663)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - fs/locks.c:fcntl_setlk
```
```
In fs/proc/fd.c (ffffffff812f5c65)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_readfd_common
  - fs/proc/fd.c:proc_fd_link
  - fs/proc/fd.c:tid_fd_revalidate
  - fs/proc/fd.c:seq_show
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/entry/common.c (ffffffff810044fd)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - arch/x86/entry/common.c:do_fast_syscall_32
  - arch/x86/entry/common.c:do_int80_syscall_32
  - arch/x86/entry/common.c:do_syscall_64
```
```
In arch/x86/events/core.c (ffffffff81006c84)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_setup_perfctr
  - arch/x86/events/core.c:x86_setup_perfctr
  - arch/x86/events/core.c:x86_setup_perfctr
  - arch/x86/events/core.c:x86_setup_perfctr
```
```
In arch/x86/events/msr.c (ffffffff8100af6a)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_event_init
```
```
In kernel/sys.c (ffffffff810a4ccf)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - kernel/sys.c:__x32_compat_sys_old_getrlimit
  - kernel/sys.c:__ia32_compat_sys_old_getrlimit
  - kernel/sys.c:__ia32_sys_old_getrlimit
  - kernel/sys.c:__x64_sys_old_getrlimit
```
```
In kernel/sched/core.c (ffffffff810ba953)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_weight_nice_write_s64
```
```
In kernel/sched/autogroup.c (ffffffff810dd6e5)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
```
```
In kernel/kcmp.c (ffffffff8110e9d1)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - kernel/kcmp.c:kcmp_epoll_target
  - kernel/kcmp.c:get_file_raw_ptr
```
```
In kernel/time/posix-timers.c (ffffffff81120606)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__x32_compat_sys_clock_nanosleep
  - kernel/time/posix-timers.c:__ia32_compat_sys_clock_nanosleep
  - kernel/time/posix-timers.c:__ia32_sys_clock_nanosleep
  - kernel/time/posix-timers.c:__x64_sys_clock_nanosleep
  - kernel/time/posix-timers.c:__x32_compat_sys_clock_getres
  - kernel/time/posix-timers.c:__ia32_compat_sys_clock_getres
  - kernel/time/posix-timers.c:__do_compat_sys_clock_adjtime
  - kernel/time/posix-timers.c:__x32_compat_sys_clock_gettime
  - kernel/time/posix-timers.c:__ia32_compat_sys_clock_gettime
  - kernel/time/posix-timers.c:__x32_compat_sys_clock_settime
  - kernel/time/posix-timers.c:__ia32_compat_sys_clock_settime
  - kernel/time/posix-timers.c:__ia32_sys_clock_getres
  - kernel/time/posix-timers.c:__x64_sys_clock_getres
  - kernel/time/posix-timers.c:__do_sys_clock_adjtime
  - kernel/time/posix-timers.c:__ia32_sys_clock_gettime
  - kernel/time/posix-timers.c:__x64_sys_clock_gettime
  - kernel/time/posix-timers.c:__ia32_sys_clock_settime
  - kernel/time/posix-timers.c:__x64_sys_clock_settime
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/bpf/syscall.c (ffffffff811b38f0)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_task_fd_query
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:map_create
```
```
In kernel/events/ring_buffer.c (ffffffff811e331c)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_to_page
```
```
In fs/file.c (ffffffff812bc111)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - fs/file.c:__ia32_sys_dup2
  - fs/file.c:__x64_sys_dup2
  - fs/file.c:ksys_dup3
  - fs/file.c:__fget
```
```
In fs/notify/dnotify/dnotify.c (ffffffff812e68b8)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
```
```
In fs/locks.c (ffffffff81301217)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - fs/locks.c:fcntl_setlk
```
```
In fs/quota/quota.c (ffffffff81315bbe)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - fs/quota/quota.c:kernel_quotactl
```
```
In fs/proc/fd.c (ffffffff813234de)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_readfd_common
  - fs/proc/fd.c:proc_fd_link
  - fs/proc/fd.c:tid_fd_mode
  - fs/proc/fd.c:seq_show
```
```
In fs/ext4/mballoc.c (ffffffff813624d2)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
```
```
In ipc/sem.c (ffffffff813dc751)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:perform_atomic_semop
  - ipc/sem.c:perform_atomic_semop
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff8161ef9e)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
```
```
In net/socket.c (ffffffff81873f17)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
```
```
In net/core/sock_diag.c (ffffffff818b8d64)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff818da415)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_create
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
In arch/x86/entry/common.c (ffffffff8100452d)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - arch/x86/entry/common.c:do_fast_syscall_32
  - arch/x86/entry/common.c:do_int80_syscall_32
  - arch/x86/entry/common.c:do_syscall_64
```
```
In arch/x86/events/core.c (ffffffff81006bbe)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_setup_perfctr
  - arch/x86/events/core.c:x86_setup_perfctr
  - arch/x86/events/core.c:x86_setup_perfctr
  - arch/x86/events/core.c:x86_setup_perfctr
```
```
In arch/x86/events/msr.c (ffffffff8100ae9a)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_event_init
```
```
In kernel/sys.c (ffffffff810ad97f)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - kernel/sys.c:__x32_compat_sys_old_getrlimit
  - kernel/sys.c:__ia32_compat_sys_old_getrlimit
  - kernel/sys.c:__ia32_sys_old_getrlimit
  - kernel/sys.c:__x64_sys_old_getrlimit
```
```
In kernel/sched/core.c (ffffffff810c3b23)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_weight_nice_write_s64
```
```
In kernel/sched/autogroup.c (ffffffff810e7e55)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
```
```
In kernel/kcmp.c (ffffffff81119f51)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - kernel/kcmp.c:kcmp_epoll_target
  - kernel/kcmp.c:get_file_raw_ptr
```
```
In kernel/time/posix-timers.c (ffffffff8112bde6)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__x32_compat_sys_clock_nanosleep
  - kernel/time/posix-timers.c:__ia32_compat_sys_clock_nanosleep
  - kernel/time/posix-timers.c:__ia32_sys_clock_nanosleep
  - kernel/time/posix-timers.c:__x64_sys_clock_nanosleep
  - kernel/time/posix-timers.c:__x32_compat_sys_clock_getres
  - kernel/time/posix-timers.c:__ia32_compat_sys_clock_getres
  - kernel/time/posix-timers.c:__do_compat_sys_clock_adjtime
  - kernel/time/posix-timers.c:__x32_compat_sys_clock_gettime
  - kernel/time/posix-timers.c:__ia32_compat_sys_clock_gettime
  - kernel/time/posix-timers.c:__x32_compat_sys_clock_settime
  - kernel/time/posix-timers.c:__ia32_compat_sys_clock_settime
  - kernel/time/posix-timers.c:__ia32_sys_clock_getres
  - kernel/time/posix-timers.c:__x64_sys_clock_getres
  - kernel/time/posix-timers.c:__do_sys_clock_adjtime
  - kernel/time/posix-timers.c:__ia32_sys_clock_gettime
  - kernel/time/posix-timers.c:__x64_sys_clock_gettime
  - kernel/time/posix-timers.c:__ia32_sys_clock_settime
  - kernel/time/posix-timers.c:__x64_sys_clock_settime
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/bpf/syscall.c (ffffffff811c4162)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:bpf_prog_load
```
```
In kernel/events/ring_buffer.c (ffffffff811f37dc)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_to_page
```
```
In fs/file.c (ffffffff812d1301)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - fs/file.c:__ia32_sys_dup2
  - fs/file.c:__x64_sys_dup2
  - fs/file.c:ksys_dup3
  - fs/file.c:__fget
```
```
In fs/notify/dnotify/dnotify.c (ffffffff812fb44b)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
```
```
In fs/aio.c (ffffffff813069d8)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - fs/aio.c:lookup_ioctx
```
```
In fs/locks.c (ffffffff81316d05)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - fs/locks.c:fcntl_setlk
```
```
In fs/quota/quota.c (ffffffff8132cb50)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - fs/quota/quota.c:kernel_quotactl
```
```
In fs/proc/fd.c (ffffffff8133a3fe)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_readfd_common
  - fs/proc/fd.c:proc_fd_link
  - fs/proc/fd.c:tid_fd_mode
  - fs/proc/fd.c:seq_show
```
```
In fs/ext4/mballoc.c (ffffffff8137a6e2)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
```
```
In ipc/sem.c (ffffffff813f6d80)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:perform_atomic_semop
  - ipc/sem.c:perform_atomic_semop
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff8163c1fe)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
```
```
In drivers/ptp/ptp_chardev.c (ffffffff8180af10)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
```
```
In net/socket.c (ffffffff81894687)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
```
```
In net/core/sock_diag.c (ffffffff818df9b4)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81906f15)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_create
```
```
In net/ipv4/ipmr.c (ffffffff81973a62)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_compat_ioctl
  - net/ipv4/ipmr.c:ipmr_ioctl
```
```
In net/ipv6/ip6mr.c (ffffffff819d7205)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_compat_ioctl
  - net/ipv6/ip6mr.c:ip6mr_ioctl
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
In arch/x86/entry/common.c (ffffffff8100474f)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - arch/x86/entry/common.c:do_fast_syscall_32
  - arch/x86/entry/common.c:do_int80_syscall_32
  - arch/x86/entry/common.c:do_syscall_64
```
```
In arch/x86/events/core.c (ffffffff81006dd2)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_setup_perfctr
  - arch/x86/events/core.c:x86_setup_perfctr
  - arch/x86/events/core.c:x86_setup_perfctr
  - arch/x86/events/core.c:x86_setup_perfctr
```
```
In arch/x86/events/msr.c (ffffffff8100b382)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_event_init
```
```
In arch/x86/kernel/ptrace.c (ffffffff81041065)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
```
```
In arch/x86/kernel/tls.c (ffffffff81042c3e)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:do_get_thread_area
```
```
In kernel/sys.c (ffffffff810b37cf)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - kernel/sys.c:__x32_compat_sys_old_getrlimit
  - kernel/sys.c:__ia32_compat_sys_old_getrlimit
  - kernel/sys.c:__ia32_sys_old_getrlimit
  - kernel/sys.c:__x64_sys_old_getrlimit
```
```
In kernel/sched/core.c (ffffffff810c9c13)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_weight_nice_write_s64
```
```
In kernel/sched/autogroup.c (ffffffff810eedcd)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
```
```
In kernel/kcmp.c (ffffffff81124bd3)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/kcmp.c:get_file_raw_ptr
```
```
In kernel/time/posix-timers.c (ffffffff81135085)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__ia32_sys_clock_nanosleep_time32
  - kernel/time/posix-timers.c:__x64_sys_clock_nanosleep_time32
  - kernel/time/posix-timers.c:__ia32_sys_clock_nanosleep
  - kernel/time/posix-timers.c:__x64_sys_clock_nanosleep
  - kernel/time/posix-timers.c:__ia32_sys_clock_getres_time32
  - kernel/time/posix-timers.c:__x64_sys_clock_getres_time32
  - kernel/time/posix-timers.c:__ia32_sys_clock_gettime32
  - kernel/time/posix-timers.c:__x64_sys_clock_gettime32
  - kernel/time/posix-timers.c:__ia32_sys_clock_settime32
  - kernel/time/posix-timers.c:__x64_sys_clock_settime32
  - kernel/time/posix-timers.c:__ia32_sys_clock_getres
  - kernel/time/posix-timers.c:__x64_sys_clock_getres
  - kernel/time/posix-timers.c:do_clock_adjtime
  - kernel/time/posix-timers.c:__ia32_sys_clock_gettime
  - kernel/time/posix-timers.c:__x64_sys_clock_gettime
  - kernel/time/posix-timers.c:__ia32_sys_clock_settime
  - kernel/time/posix-timers.c:__x64_sys_clock_settime
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/bpf/syscall.c (ffffffff811d60d2)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:map_create
```
```
In kernel/events/ring_buffer.c (ffffffff8120b4d1)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_to_page
```
```
In fs/file.c (ffffffff812ee321)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - fs/file.c:__ia32_sys_dup2
  - fs/file.c:__x64_sys_dup2
  - fs/file.c:ksys_dup3
  - fs/file.c:__fget
```
```
In fs/notify/dnotify/dnotify.c (ffffffff8131bd32)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
```
```
In fs/aio.c (ffffffff81327fc8)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - fs/aio.c:lookup_ioctx
```
```
In fs/io_uring.c (ffffffff8132d945)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
```
```
In fs/locks.c (ffffffff8133e59a)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - fs/locks.c:fcntl_setlk
```
```
In fs/quota/quota.c (ffffffff8135469f)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - fs/quota/quota.c:do_quotactl
```
```
In fs/proc/fd.c (ffffffff8136259e)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_readfd_common
  - fs/proc/fd.c:proc_fd_link
  - fs/proc/fd.c:tid_fd_mode
  - fs/proc/fd.c:seq_show
```
```
In fs/ext4/mballoc.c (ffffffff813a41cb)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
```
```
In ipc/sem.c (ffffffff81422df8)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:perform_atomic_semop
  - ipc/sem.c:perform_atomic_semop
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff8166f9a0)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
```
```
In drivers/ptp/ptp_chardev.c (ffffffff8184cb57)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
```
```
In net/socket.c (ffffffff818dea47)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
```
```
In net/core/sock_diag.c (ffffffff8192e000)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff819681c2)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_create
```
```
In net/ipv4/ipmr.c (ffffffff819dd575)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_compat_ioctl
  - net/ipv4/ipmr.c:ipmr_ioctl
```
```
In net/ipv6/ip6mr.c (ffffffff81a462e2)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_compat_ioctl
  - net/ipv6/ip6mr.c:ip6mr_ioctl
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
In arch/x86/entry/common.c (ffffffff810047af)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - arch/x86/entry/common.c:do_fast_syscall_32
  - arch/x86/entry/common.c:do_int80_syscall_32
  - arch/x86/entry/common.c:do_syscall_64
  - arch/x86/entry/common.c:do_syscall_64
```
```
In arch/x86/events/core.c (ffffffff81006e52)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_setup_perfctr
  - arch/x86/events/core.c:x86_setup_perfctr
  - arch/x86/events/core.c:x86_setup_perfctr
  - arch/x86/events/core.c:x86_setup_perfctr
```
```
In arch/x86/events/msr.c (ffffffff8100b792)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_event_init
```
```
In arch/x86/kernel/ptrace.c (ffffffff810417f5)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
```
```
In arch/x86/kernel/tls.c (ffffffff810433ae)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:do_get_thread_area
```
```
In kernel/sys.c (ffffffff810b9dbf)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - kernel/sys.c:__x32_compat_sys_old_getrlimit
  - kernel/sys.c:__ia32_compat_sys_old_getrlimit
  - kernel/sys.c:__ia32_sys_old_getrlimit
  - kernel/sys.c:__x64_sys_old_getrlimit
```
```
In kernel/sched/core.c (ffffffff810d2ed3)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_weight_nice_write_s64
```
```
In kernel/sched/autogroup.c (ffffffff810faa31)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
```
```
In kernel/kcmp.c (ffffffff81130b93)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/kcmp.c:get_file_raw_ptr
```
```
In kernel/time/posix-timers.c (ffffffff811410a5)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__ia32_sys_clock_nanosleep_time32
  - kernel/time/posix-timers.c:__x64_sys_clock_nanosleep_time32
  - kernel/time/posix-timers.c:__ia32_sys_clock_nanosleep
  - kernel/time/posix-timers.c:__x64_sys_clock_nanosleep
  - kernel/time/posix-timers.c:__ia32_sys_clock_getres_time32
  - kernel/time/posix-timers.c:__x64_sys_clock_getres_time32
  - kernel/time/posix-timers.c:__ia32_sys_clock_gettime32
  - kernel/time/posix-timers.c:__x64_sys_clock_gettime32
  - kernel/time/posix-timers.c:__ia32_sys_clock_settime32
  - kernel/time/posix-timers.c:__x64_sys_clock_settime32
  - kernel/time/posix-timers.c:__ia32_sys_clock_getres
  - kernel/time/posix-timers.c:__x64_sys_clock_getres
  - kernel/time/posix-timers.c:do_clock_adjtime
  - kernel/time/posix-timers.c:__ia32_sys_clock_gettime
  - kernel/time/posix-timers.c:__x64_sys_clock_gettime
  - kernel/time/posix-timers.c:__ia32_sys_clock_settime
  - kernel/time/posix-timers.c:__x64_sys_clock_settime
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/bpf/syscall.c (ffffffff811e2078)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:map_create
```
```
In kernel/events/ring_buffer.c (ffffffff812187b1)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_to_page
```
```
In fs/file.c (ffffffff812ffde1)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - fs/file.c:__ia32_sys_dup2
  - fs/file.c:__x64_sys_dup2
  - fs/file.c:ksys_dup3
  - fs/file.c:__fget
```
```
In fs/notify/dnotify/dnotify.c (ffffffff8132eb1b)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
```
```
In fs/aio.c (ffffffff8133ad68)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - fs/aio.c:lookup_ioctx
```
```
In fs/io_uring.c (ffffffff81340978)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
```
```
In fs/locks.c (ffffffff81356b8a)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - fs/locks.c:fcntl_setlk
```
```
In fs/quota/quota.c (ffffffff8136ca0f)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - fs/quota/quota.c:do_quotactl
```
```
In fs/proc/fd.c (ffffffff8137a7fe)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_readfd_common
  - fs/proc/fd.c:proc_fd_link
  - fs/proc/fd.c:tid_fd_mode
  - fs/proc/fd.c:seq_show
```
```
In fs/ext4/mballoc.c (ffffffff813bd03b)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
```
```
In ipc/sem.c (ffffffff8143cb9c)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:perform_atomic_semop
  - ipc/sem.c:perform_atomic_semop
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff81691fa1)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff817d6fe0)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
```
```
In drivers/ptp/ptp_chardev.c (ffffffff8187e79f)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
```
```
In net/socket.c (ffffffff81910c17)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
```
```
In net/core/sock_diag.c (ffffffff81960290)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff8199ec62)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_create
```
```
In net/ipv4/ipmr.c (ffffffff81a146ad)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_compat_ioctl
  - net/ipv4/ipmr.c:ipmr_ioctl
```
```
In net/ipv6/ip6mr.c (ffffffff81a7ced2)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_compat_ioctl
  - net/ipv6/ip6mr.c:ip6mr_ioctl
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
In arch/x86/entry/common.c (ffffffff8100561c)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - arch/x86/entry/common.c:do_syscall_32_irqs_on
  - arch/x86/entry/common.c:do_syscall_64
  - arch/x86/entry/common.c:do_syscall_64
```
```
In arch/x86/events/core.c (ffffffff81007eb2)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_setup_perfctr
  - arch/x86/events/core.c:x86_setup_perfctr
  - arch/x86/events/core.c:x86_setup_perfctr
  - arch/x86/events/core.c:x86_setup_perfctr
```
```
In arch/x86/events/msr.c (ffffffff8100ca82)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_event_init
```
```
In arch/x86/kernel/ptrace.c (ffffffff81045c03)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:x32_arch_ptrace
  - arch/x86/kernel/ptrace.c:getreg32
  - arch/x86/kernel/ptrace.c:arch_ptrace
```
```
In arch/x86/kernel/tls.c (ffffffff81046874)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:__ia32_sys_get_thread_area
  - arch/x86/kernel/tls.c:__x64_sys_get_thread_area
```
```
In kernel/sys.c (ffffffff810c1ccf)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - kernel/sys.c:__x32_compat_sys_old_getrlimit
  - kernel/sys.c:__ia32_compat_sys_old_getrlimit
  - kernel/sys.c:__ia32_sys_old_getrlimit
  - kernel/sys.c:__x64_sys_old_getrlimit
```
```
In kernel/sched/core.c (ffffffff810dcac3)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_weight_nice_write_s64
```
```
In kernel/sched/autogroup.c (ffffffff81104ea5)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
```
```
In kernel/kcmp.c (ffffffff8113fc20)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - kernel/kcmp.c:kcmp_epoll_target
  - kernel/kcmp.c:get_file_raw_ptr
```
```
In kernel/time/posix-timers.c (ffffffff811520b5)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__ia32_sys_clock_nanosleep_time32
  - kernel/time/posix-timers.c:__x64_sys_clock_nanosleep_time32
  - kernel/time/posix-timers.c:__ia32_sys_clock_nanosleep
  - kernel/time/posix-timers.c:__x64_sys_clock_nanosleep
  - kernel/time/posix-timers.c:__ia32_sys_clock_getres_time32
  - kernel/time/posix-timers.c:__x64_sys_clock_getres_time32
  - kernel/time/posix-timers.c:__do_sys_clock_adjtime32
  - kernel/time/posix-timers.c:__ia32_sys_clock_gettime32
  - kernel/time/posix-timers.c:__x64_sys_clock_gettime32
  - kernel/time/posix-timers.c:__ia32_sys_clock_settime32
  - kernel/time/posix-timers.c:__x64_sys_clock_settime32
  - kernel/time/posix-timers.c:__ia32_sys_clock_getres
  - kernel/time/posix-timers.c:__x64_sys_clock_getres
  - kernel/time/posix-timers.c:__do_sys_clock_adjtime
  - kernel/time/posix-timers.c:__ia32_sys_clock_gettime
  - kernel/time/posix-timers.c:__x64_sys_clock_gettime
  - kernel/time/posix-timers.c:__ia32_sys_clock_settime
  - kernel/time/posix-timers.c:__x64_sys_clock_settime
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/bpf/syscall.c (ffffffff811fc765)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_task_fd_query
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:map_create
```
```
In kernel/bpf/task_iter.c (ffffffff812166d2)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - kernel/bpf/task_iter.c:task_file_seq_get_next
```
```
In kernel/events/ring_buffer.c (ffffffff81244411)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_to_page
```
```
In fs/file.c (ffffffff81338f21)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - fs/file.c:__ia32_sys_dup2
  - fs/file.c:__x64_sys_dup2
  - fs/file.c:ksys_dup3
  - fs/file.c:__fget_files
```
```
In fs/notify/dnotify/dnotify.c (ffffffff813689eb)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
```
```
In fs/aio.c (ffffffff81374e68)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - fs/aio.c:lookup_ioctx
```
```
In fs/io_uring.c (ffffffff81380606)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - fs/io_uring.c:__io_sqe_files_update
  - fs/io_uring.c:io_grab_files
  - fs/io_uring.c:io_file_get
  - fs/io_uring.c:io_import_fixed
```
```
In fs/locks.c (ffffffff8139df46)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - fs/locks.c:fcntl_setlk
```
```
In fs/quota/quota.c (ffffffff813b48a9)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - fs/quota/quota.c:do_quotactl
```
```
In fs/proc/fd.c (ffffffff813c3c02)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_readfd_common
  - fs/proc/fd.c:proc_fd_link
  - fs/proc/fd.c:tid_fd_mode
  - fs/proc/fd.c:seq_show
```
```
In fs/ext4/mballoc.c (ffffffff81408ee7)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
```
```
In ipc/sem.c (ffffffff8148d258)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:perform_atomic_semop
  - ipc/sem.c:perform_atomic_semop_slow
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff81744881)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff818a471c)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
```
```
In drivers/ptp/ptp_chardev.c (ffffffff8194cc96)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
```
```
In net/socket.c (ffffffff819e2e3c)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - net/socket.c:__do_sys_socketcall
```
```
In net/core/sock_diag.c (ffffffff81a33680)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81a77812)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_create
```
```
In net/ipv4/ipmr.c (ffffffff81b0562f)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_compat_ioctl
  - net/ipv4/ipmr.c:ipmr_ioctl
```
```
In net/ipv6/ip6mr.c (ffffffff81b7788d)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_compat_ioctl
  - net/ipv6/ip6mr.c:ip6mr_ioctl
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
In arch/x86/entry/common.c (ffffffff81c34ca7)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - arch/x86/entry/common.c:__do_fast_syscall_32
  - arch/x86/entry/common.c:do_int80_syscall_32
  - arch/x86/entry/common.c:do_syscall_64
  - arch/x86/entry/common.c:do_syscall_64
```
```
In arch/x86/events/core.c (ffffffff81006f62)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_setup_perfctr
  - arch/x86/events/core.c:x86_setup_perfctr
  - arch/x86/events/core.c:x86_setup_perfctr
  - arch/x86/events/core.c:x86_setup_perfctr
```
```
In arch/x86/events/msr.c (ffffffff8100b9d2)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_event_init
```
```
In arch/x86/kernel/ptrace.c (ffffffff81045670)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:x32_arch_ptrace
  - arch/x86/kernel/ptrace.c:getreg32
  - arch/x86/kernel/ptrace.c:arch_ptrace
```
```
In arch/x86/kernel/tls.c (ffffffff810462f9)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:do_get_thread_area
```
```
In kernel/sys.c (ffffffff810bcfbf)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - kernel/sys.c:__x32_compat_sys_old_getrlimit
  - kernel/sys.c:__ia32_compat_sys_old_getrlimit
  - kernel/sys.c:__ia32_sys_old_getrlimit
  - kernel/sys.c:__x64_sys_old_getrlimit
```
```
In kernel/sched/core.c (ffffffff810d9333)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_weight_nice_write_s64
```
```
In kernel/sched/autogroup.c (ffffffff81103525)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
```
```
In kernel/time/posix-timers.c (ffffffff8114e335)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__ia32_sys_clock_nanosleep_time32
  - kernel/time/posix-timers.c:__x64_sys_clock_nanosleep_time32
  - kernel/time/posix-timers.c:__ia32_sys_clock_nanosleep
  - kernel/time/posix-timers.c:__x64_sys_clock_nanosleep
  - kernel/time/posix-timers.c:__ia32_sys_clock_getres_time32
  - kernel/time/posix-timers.c:__x64_sys_clock_getres_time32
  - kernel/time/posix-timers.c:__do_sys_clock_adjtime32
  - kernel/time/posix-timers.c:__ia32_sys_clock_gettime32
  - kernel/time/posix-timers.c:__x64_sys_clock_gettime32
  - kernel/time/posix-timers.c:__ia32_sys_clock_settime32
  - kernel/time/posix-timers.c:__x64_sys_clock_settime32
  - kernel/time/posix-timers.c:__ia32_sys_clock_getres
  - kernel/time/posix-timers.c:__x64_sys_clock_getres
  - kernel/time/posix-timers.c:__do_sys_clock_adjtime
  - kernel/time/posix-timers.c:__ia32_sys_clock_gettime
  - kernel/time/posix-timers.c:__x64_sys_clock_gettime
  - kernel/time/posix-timers.c:__ia32_sys_clock_settime
  - kernel/time/posix-timers.c:__x64_sys_clock_settime
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/seccomp.c (ffffffff811a38ea)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_run_filters
```
```
In kernel/bpf/syscall.c (ffffffff811ff704)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:map_create
```
```
In kernel/events/ring_buffer.c (ffffffff8124eac1)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_to_page
```
```
In fs/file.c (ffffffff81344b35)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - fs/file.c:__ia32_sys_dup2
  - fs/file.c:__x64_sys_dup2
  - fs/file.c:ksys_dup3
  - fs/file.c:task_lookup_next_fd_rcu
  - fs/file.c:task_lookup_fd_rcu
  - fs/file.c:__fget_files
```
```
In fs/notify/dnotify/dnotify.c (ffffffff81375d10)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
```
```
In fs/aio.c (ffffffff81382deb)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - fs/aio.c:lookup_ioctx
```
```
In fs/io_uring.c (ffffffff8138eed0)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - fs/io_uring.c:__io_sqe_files_update
  - fs/io_uring.c:io_file_get
  - fs/io_uring.c:io_import_fixed
```
```
In fs/locks.c (ffffffff813af8ea)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - fs/locks.c:fcntl_setlk
```
```
In fs/quota/quota.c (ffffffff813c62c9)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - fs/quota/quota.c:do_quotactl
```
```
In fs/proc/fd.c (ffffffff813d5bdf)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - fs/proc/fd.c:seq_show
```
```
In fs/ext4/mballoc.c (ffffffff8141c7fc)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
```
```
In ipc/sem.c (ffffffff814aa96c)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:perform_atomic_semop
  - ipc/sem.c:perform_atomic_semop_slow
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff8176020a)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_setactivate
```
```
In drivers/tty/vt/keyboard.c (ffffffff8176612a)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff818b37c3)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
```
```
In drivers/ptp/ptp_chardev.c (ffffffff819521b7)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
```
```
In net/socket.c (ffffffff819e2abc)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - net/socket.c:__do_sys_socketcall
```
```
In net/core/sock_diag.c (ffffffff81a359f0)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81a806e2)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_create
```
```
In net/ipv4/ipmr.c (ffffffff81b13854)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_compat_ioctl
  - net/ipv4/ipmr.c:ipmr_ioctl
```
```
In net/ipv6/ip6mr.c (ffffffff81b86802)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_compat_ioctl
  - net/ipv6/ip6mr.c:ip6mr_ioctl
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
In arch/x86/entry/common.c (ffffffff81c270c0)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - arch/x86/entry/common.c:__do_fast_syscall_32
  - arch/x86/entry/common.c:do_int80_syscall_32
  - arch/x86/entry/common.c:do_syscall_64
  - arch/x86/entry/common.c:do_syscall_64
```
```
In arch/x86/events/core.c (ffffffff8100768a)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_setup_perfctr
  - arch/x86/events/core.c:x86_setup_perfctr
  - arch/x86/events/core.c:x86_setup_perfctr
  - arch/x86/events/core.c:x86_setup_perfctr
```
```
In arch/x86/events/msr.c (ffffffff8100c372)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_event_init
```
```
In arch/x86/kernel/ptrace.c (ffffffff810471e1)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:x32_arch_ptrace
  - arch/x86/kernel/ptrace.c:getreg32
  - arch/x86/kernel/ptrace.c:arch_ptrace
```
```
In arch/x86/kernel/tls.c (ffffffff81047d1c)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:do_get_thread_area
```
```
In kernel/sys.c (ffffffff810bf16f)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - kernel/sys.c:__x32_compat_sys_old_getrlimit
  - kernel/sys.c:__ia32_compat_sys_old_getrlimit
  - kernel/sys.c:__ia32_sys_old_getrlimit
  - kernel/sys.c:__x64_sys_old_getrlimit
```
```
In kernel/sched/core.c (ffffffff810dacc3)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_weight_nice_write_s64
```
```
In kernel/sched/autogroup.c (ffffffff81105831)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
```
```
In kernel/time/posix-timers.c (ffffffff8114ee26)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__ia32_sys_clock_nanosleep_time32
  - kernel/time/posix-timers.c:__x64_sys_clock_nanosleep_time32
  - kernel/time/posix-timers.c:__ia32_sys_clock_nanosleep
  - kernel/time/posix-timers.c:__x64_sys_clock_nanosleep
  - kernel/time/posix-timers.c:__ia32_sys_clock_getres_time32
  - kernel/time/posix-timers.c:__x64_sys_clock_getres_time32
  - kernel/time/posix-timers.c:__do_sys_clock_adjtime32
  - kernel/time/posix-timers.c:__ia32_sys_clock_gettime32
  - kernel/time/posix-timers.c:__x64_sys_clock_gettime32
  - kernel/time/posix-timers.c:__ia32_sys_clock_settime32
  - kernel/time/posix-timers.c:__x64_sys_clock_settime32
  - kernel/time/posix-timers.c:__ia32_sys_clock_getres
  - kernel/time/posix-timers.c:__x64_sys_clock_getres
  - kernel/time/posix-timers.c:__do_sys_clock_adjtime
  - kernel/time/posix-timers.c:__ia32_sys_clock_gettime
  - kernel/time/posix-timers.c:__x64_sys_clock_gettime
  - kernel/time/posix-timers.c:__ia32_sys_clock_settime
  - kernel/time/posix-timers.c:__x64_sys_clock_settime
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/seccomp.c (ffffffff811a450a)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_run_filters
```
```
In kernel/bpf/syscall.c (ffffffff812000af)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:map_create
```
```
In kernel/events/ring_buffer.c (ffffffff812533d4)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_to_page
```
```
In fs/file.c (ffffffff8134b0e9)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - fs/file.c:__ia32_sys_dup2
  - fs/file.c:__x64_sys_dup2
  - fs/file.c:ksys_dup3
  - fs/file.c:task_lookup_next_fd_rcu
  - fs/file.c:task_lookup_fd_rcu
  - fs/file.c:__fget_files
```
```
In fs/notify/dnotify/dnotify.c (ffffffff8137c6ae)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
```
```
In fs/aio.c (ffffffff81389e5e)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - fs/aio.c:lookup_ioctx
```
```
In fs/io_uring.c (ffffffff8139e37d)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:__io_sqe_buffers_update
  - fs/io_uring.c:__io_sqe_files_update
  - fs/io_uring.c:io_file_get
  - fs/io_uring.c:io_import_iovec
```
```
In fs/locks.c (ffffffff813b6b80)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - fs/locks.c:fcntl_setlk
```
```
In fs/quota/quota.c (ffffffff813ccfbc)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - fs/quota/quota.c:do_quotactl
```
```
In fs/proc/fd.c (ffffffff813dcbef)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - fs/proc/fd.c:seq_show
```
```
In fs/ext4/mballoc.c (ffffffff81422b03)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
```
```
In ipc/sem.c (ffffffff814b11c7)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:perform_atomic_semop
  - ipc/sem.c:perform_atomic_semop_slow
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff81744b8d)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
```
```
In drivers/tty/vt/keyboard.c (ffffffff81749d7a)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff8189699c)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
```
```
In drivers/ptp/ptp_chardev.c (ffffffff8193603b)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
```
```
In net/socket.c (ffffffff819c8adc)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - net/socket.c:__do_sys_socketcall
```
```
In net/core/sock_diag.c (ffffffff81a1cb40)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81a69d72)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_create
```
```
In net/ipv4/ipmr.c (ffffffff81b01694)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_compat_ioctl
  - net/ipv4/ipmr.c:ipmr_ioctl
```
```
In net/ipv6/ip6mr.c (ffffffff81b754c9)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_compat_ioctl
  - net/ipv6/ip6mr.c:ip6mr_ioctl
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
In arch/x86/entry/common.c (ffffffff81d450ee)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - arch/x86/entry/common.c:__do_fast_syscall_32
  - arch/x86/entry/common.c:do_int80_syscall_32
  - arch/x86/entry/common.c:do_syscall_64
  - arch/x86/entry/common.c:do_syscall_64
```
```
In arch/x86/events/core.c (ffffffff81007f61)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_setup_perfctr
  - arch/x86/events/core.c:x86_setup_perfctr
  - arch/x86/events/core.c:x86_setup_perfctr
  - arch/x86/events/core.c:x86_setup_perfctr
```
```
In arch/x86/events/msr.c (ffffffff8100c88a)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_event_init
```
```
In arch/x86/kernel/ptrace.c (ffffffff8104d648)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:x32_arch_ptrace
  - arch/x86/kernel/ptrace.c:getreg32
  - arch/x86/kernel/ptrace.c:arch_ptrace
```
```
In arch/x86/kernel/tls.c (ffffffff8104e5bf)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:do_get_thread_area
```
```
In kernel/sys.c (ffffffff810d1b13)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - kernel/sys.c:__x64_compat_sys_old_getrlimit
  - kernel/sys.c:__ia32_compat_sys_old_getrlimit
  - kernel/sys.c:__ia32_sys_old_getrlimit
  - kernel/sys.c:__x64_sys_old_getrlimit
```
```
In kernel/sched/core.c (ffffffff810ee8be)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_weight_nice_write_s64
```
```
In kernel/sched/autogroup.c (ffffffff811234a1)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
```
```
In kernel/time/posix-timers.c (ffffffff81172f89)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__ia32_sys_clock_nanosleep_time32
  - kernel/time/posix-timers.c:__x64_sys_clock_nanosleep_time32
  - kernel/time/posix-timers.c:__ia32_sys_clock_nanosleep
  - kernel/time/posix-timers.c:__x64_sys_clock_nanosleep
  - kernel/time/posix-timers.c:__ia32_sys_clock_getres_time32
  - kernel/time/posix-timers.c:__x64_sys_clock_getres_time32
  - kernel/time/posix-timers.c:__do_sys_clock_adjtime32
  - kernel/time/posix-timers.c:__ia32_sys_clock_gettime32
  - kernel/time/posix-timers.c:__x64_sys_clock_gettime32
  - kernel/time/posix-timers.c:__ia32_sys_clock_settime32
  - kernel/time/posix-timers.c:__x64_sys_clock_settime32
  - kernel/time/posix-timers.c:__ia32_sys_clock_getres
  - kernel/time/posix-timers.c:__x64_sys_clock_getres
  - kernel/time/posix-timers.c:__do_sys_clock_adjtime
  - kernel/time/posix-timers.c:__ia32_sys_clock_gettime
  - kernel/time/posix-timers.c:__x64_sys_clock_gettime
  - kernel/time/posix-timers.c:__ia32_sys_clock_settime
  - kernel/time/posix-timers.c:__x64_sys_clock_settime
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/seccomp.c (ffffffff811cdd5a)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_run_filters
```
```
In kernel/bpf/syscall.c (ffffffff81231db6)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:map_create
```
```
In kernel/events/ring_buffer.c (ffffffff8128ecf4)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_to_page
```
```
In fs/file.c (ffffffff81398ec9)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - fs/file.c:__ia32_sys_dup2
  - fs/file.c:__x64_sys_dup2
  - fs/file.c:ksys_dup3
  - fs/file.c:task_lookup_next_fd_rcu
  - fs/file.c:task_lookup_fd_rcu
  - fs/file.c:__fget_files
```
```
In fs/notify/dnotify/dnotify.c (ffffffff813c9537)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
```
```
In fs/aio.c (ffffffff813d713e)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - fs/aio.c:lookup_ioctx
```
```
In fs/io_uring.c (ffffffff813ee429)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:__io_sqe_buffers_update
  - fs/io_uring.c:__io_sqe_files_update
  - fs/io_uring.c:io_init_req
  - fs/io_uring.c:io_close
  - fs/io_uring.c:__io_splice_prep
  - fs/io_uring.c:io_import_iovec
```
```
In fs/locks.c (ffffffff8140687d)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - fs/locks.c:fcntl_setlk
```
```
In fs/quota/quota.c (ffffffff8141e27c)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - fs/quota/quota.c:do_quotactl
```
```
In fs/proc/fd.c (ffffffff8142e2cf)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - fs/proc/fd.c:seq_show
```
```
In fs/ext4/mballoc.c (ffffffff81476284)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
```
```
In ipc/sem.c (ffffffff815096ad)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - ipc/sem.c:__do_semtimedop
  - ipc/sem.c:__do_semtimedop
  - ipc/sem.c:__do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:perform_atomic_semop
  - ipc/sem.c:perform_atomic_semop_slow
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff817c5f0d)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
```
```
In drivers/tty/vt/keyboard.c (ffffffff817cb3bd)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl
```
```
In drivers/dma-buf/dma-heap.c (ffffffff818a7b85)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - drivers/dma-buf/dma-heap.c:dma_heap_ioctl
```
```
In drivers/vfio/pci/vfio_pci_core.c (ffffffff8192a929)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_ioctl
```
```
In drivers/ptp/ptp_chardev.c (ffffffff819d973e)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
```
```
In net/socket.c (ffffffff81a77e31)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - net/socket.c:__do_sys_socketcall
```
```
In net/core/sock_diag.c (ffffffff81ad0362)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81b23362)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_create
```
```
In net/ipv4/ipmr.c (ffffffff81bc33ce)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_compat_ioctl
  - net/ipv4/ipmr.c:ipmr_ioctl
```
```
In net/ipv6/ip6mr.c (ffffffff81c3fe2b)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_compat_ioctl
  - net/ipv6/ip6mr.c:ip6mr_ioctl
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
In arch/x86/entry/common.c (ffffffff81f1308a)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - arch/x86/entry/common.c:__do_fast_syscall_32
  - arch/x86/entry/common.c:do_int80_syscall_32
  - arch/x86/entry/common.c:do_syscall_64
```
```
In arch/x86/events/core.c (ffffffff810074e3)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_setup_perfctr
  - arch/x86/events/core.c:x86_setup_perfctr
  - arch/x86/events/core.c:x86_setup_perfctr
  - arch/x86/events/core.c:x86_setup_perfctr
```
```
In arch/x86/events/msr.c (ffffffff8100d5ca)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_event_init
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff81057207)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:fpu_xstate_prctl
```
```
In arch/x86/kernel/ptrace.c (ffffffff81058316)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:getreg32
  - arch/x86/kernel/ptrace.c:arch_ptrace
```
```
In arch/x86/kernel/tls.c (ffffffff8105974f)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:do_get_thread_area
```
```
In kernel/sys.c (ffffffff810e7743)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_compat_sys_old_getrlimit
  - kernel/sys.c:__ia32_sys_old_getrlimit
  - kernel/sys.c:__x64_sys_old_getrlimit
```
```
In kernel/sched/core.c (ffffffff8110af5d)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_weight_nice_write_s64
```
```
In kernel/sched/build_utility.c (ffffffff8114d071)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:proc_sched_autogroup_set_nice
```
```
In kernel/time/posix-timers.c (ffffffff811a84e9)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__ia32_sys_clock_nanosleep_time32
  - kernel/time/posix-timers.c:__x64_sys_clock_nanosleep_time32
  - kernel/time/posix-timers.c:__ia32_sys_clock_nanosleep
  - kernel/time/posix-timers.c:__x64_sys_clock_nanosleep
  - kernel/time/posix-timers.c:__ia32_sys_clock_getres_time32
  - kernel/time/posix-timers.c:__x64_sys_clock_getres_time32
  - kernel/time/posix-timers.c:__do_sys_clock_adjtime32
  - kernel/time/posix-timers.c:__ia32_sys_clock_gettime32
  - kernel/time/posix-timers.c:__x64_sys_clock_gettime32
  - kernel/time/posix-timers.c:__ia32_sys_clock_settime32
  - kernel/time/posix-timers.c:__x64_sys_clock_settime32
  - kernel/time/posix-timers.c:__ia32_sys_clock_getres
  - kernel/time/posix-timers.c:__x64_sys_clock_getres
  - kernel/time/posix-timers.c:__do_sys_clock_adjtime
  - kernel/time/posix-timers.c:__ia32_sys_clock_gettime
  - kernel/time/posix-timers.c:__x64_sys_clock_gettime
  - kernel/time/posix-timers.c:__ia32_sys_clock_settime
  - kernel/time/posix-timers.c:__x64_sys_clock_settime
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/seccomp.c (ffffffff81201c7a)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_run_filters
```
```
In kernel/bpf/syscall.c (ffffffff812750a6)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:map_create
```
```
In kernel/events/ring_buffer.c (ffffffff812e3bfc)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_to_page
```
```
In mm/hugetlb.c (ffffffff834904c3)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - mm/hugetlb.c:hugepages_setup
```
```
In fs/file.c (ffffffff8141b79a)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - fs/file.c:__ia32_sys_dup2
  - fs/file.c:__x64_sys_dup2
  - fs/file.c:ksys_dup3
  - fs/file.c:__fget_light
  - fs/file.c:__fget_light
  - fs/file.c:task_lookup_next_fd_rcu
  - fs/file.c:task_lookup_fd_rcu
  - fs/file.c:fget_task
  - fs/file.c:fget_raw
  - fs/file.c:fget
```
```
In fs/notify/dnotify/dnotify.c (ffffffff81450ee9)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
```
```
In fs/aio.c (ffffffff81460cc7)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - fs/aio.c:lookup_ioctx
```
```
In fs/locks.c (ffffffff8147b395)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - fs/locks.c:fcntl_setlk
```
```
In fs/quota/quota.c (ffffffff81495f6c)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - fs/quota/quota.c:do_quotactl
```
```
In fs/proc/fd.c (ffffffff814a79f4)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - fs/proc/fd.c:seq_show
```
```
In fs/ext4/mballoc.c (ffffffff814f8015)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
```
```
In ipc/sem.c (ffffffff8159b2b3)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - ipc/sem.c:__do_semtimedop
  - ipc/sem.c:__do_semtimedop
  - ipc/sem.c:__do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:perform_atomic_semop
  - ipc/sem.c:perform_atomic_semop_slow
```
```
In io_uring/io_uring.c (ffffffff816d8436)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - io_uring/io_uring.c:__io_uring_register
  - io_uring/io_uring.c:__io_uring_register
  - io_uring/io_uring.c:__do_sys_io_uring_enter
  - io_uring/io_uring.c:io_ringfd_register
  - io_uring/io_uring.c:__io_sqe_buffers_update
  - io_uring/io_uring.c:__io_sqe_files_update
  - io_uring/io_uring.c:io_wq_submit_work
  - io_uring/io_uring.c:io_issue_sqe
  - io_uring/io_uring.c:io_async_cancel
  - io_uring/io_uring.c:io_fixed_fd_install
  - io_uring/io_uring.c:io_splice
  - io_uring/io_uring.c:io_tee
  - io_uring/io_uring.c:io_prep_rw
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff81902bda)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
```
```
In drivers/tty/vt/keyboard.c (ffffffff81908b5e)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl
```
```
In drivers/dma-buf/dma-heap.c (ffffffff819f190a)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - drivers/dma-buf/dma-heap.c:dma_heap_ioctl
```
```
In drivers/vfio/pci/vfio_pci_core.c (ffffffff81a81c9f)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_ioctl
```
```
In drivers/ptp/ptp_chardev.c (ffffffff81b3d218)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
```
```
In drivers/md/dm-ioctl.c (ffffffff81b79cad)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:ctl_ioctl
```
```
In net/socket.c (ffffffff81beb371)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - net/socket.c:__do_sys_socketcall
```
```
In net/core/sock_diag.c (ffffffff81c4dbf1)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81cabd11)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_create
```
```
In net/ipv4/ipmr.c (ffffffff81d581f0)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_compat_ioctl
  - net/ipv4/ipmr.c:ipmr_ioctl
```
```
In net/ipv6/ip6mr.c (ffffffff81dde425)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_compat_ioctl
  - net/ipv6/ip6mr.c:ip6mr_ioctl
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
In arch/x86/entry/common.c (ffffffff820ba0aa)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - arch/x86/entry/common.c:__do_fast_syscall_32
  - arch/x86/entry/common.c:do_int80_syscall_32
  - arch/x86/entry/common.c:do_syscall_64
```
```
In arch/x86/events/core.c (ffffffff81005cdb)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_get_hw_event_config
  - arch/x86/events/core.c:x86_setup_perfctr
  - arch/x86/events/core.c:x86_setup_perfctr
  - arch/x86/events/core.c:x86_setup_perfctr
  - arch/x86/events/core.c:x86_setup_perfctr
```
```
In arch/x86/events/msr.c (ffffffff810107aa)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_event_init
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff81064967)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:fpu_xstate_prctl
```
```
In arch/x86/kernel/ptrace.c (ffffffff81065b95)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:getreg32
  - arch/x86/kernel/ptrace.c:arch_ptrace
```
```
In arch/x86/kernel/tls.c (ffffffff810670af)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:do_get_thread_area
```
```
In kernel/sys.c (ffffffff811083d3)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_compat_sys_old_getrlimit
  - kernel/sys.c:__ia32_sys_old_getrlimit
  - kernel/sys.c:__x64_sys_old_getrlimit
  - kernel/sys.c:__ia32_compat_sys_getrlimit
  - kernel/sys.c:__ia32_sys_getrlimit
  - kernel/sys.c:__x64_sys_getrlimit
```
```
In kernel/sched/core.c (ffffffff8112fdbd)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_weight_nice_write_s64
```
```
In kernel/sched/build_utility.c (ffffffff8117c101)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:proc_sched_autogroup_set_nice
```
```
In kernel/time/posix-timers.c (ffffffff811e8279)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__ia32_sys_clock_nanosleep_time32
  - kernel/time/posix-timers.c:__x64_sys_clock_nanosleep_time32
  - kernel/time/posix-timers.c:__ia32_sys_clock_nanosleep
  - kernel/time/posix-timers.c:__x64_sys_clock_nanosleep
  - kernel/time/posix-timers.c:__ia32_sys_clock_getres_time32
  - kernel/time/posix-timers.c:__x64_sys_clock_getres_time32
  - kernel/time/posix-timers.c:__do_sys_clock_adjtime32
  - kernel/time/posix-timers.c:__ia32_sys_clock_gettime32
  - kernel/time/posix-timers.c:__x64_sys_clock_gettime32
  - kernel/time/posix-timers.c:__ia32_sys_clock_settime32
  - kernel/time/posix-timers.c:__x64_sys_clock_settime32
  - kernel/time/posix-timers.c:__ia32_sys_clock_getres
  - kernel/time/posix-timers.c:__x64_sys_clock_getres
  - kernel/time/posix-timers.c:__do_sys_clock_adjtime
  - kernel/time/posix-timers.c:__ia32_sys_clock_gettime
  - kernel/time/posix-timers.c:__x64_sys_clock_gettime
  - kernel/time/posix-timers.c:__ia32_sys_clock_settime
  - kernel/time/posix-timers.c:__x64_sys_clock_settime
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/seccomp.c (ffffffff81249f9c)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
```
```
In kernel/bpf/syscall.c (ffffffff812ca573)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:map_create
```
```
In kernel/events/ring_buffer.c (ffffffff8134c2cc)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_to_page
```
```
In mm/hugetlb.c (ffffffff83ec3647)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - mm/hugetlb.c:hugepages_setup
```
```
In fs/file.c (ffffffff814a797a)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - fs/file.c:__ia32_sys_dup2
  - fs/file.c:__x64_sys_dup2
  - fs/file.c:ksys_dup3
  - fs/file.c:__fget_light
  - fs/file.c:__fget_light
  - fs/file.c:task_lookup_next_fd_rcu
  - fs/file.c:task_lookup_fd_rcu
  - fs/file.c:fget_task
  - fs/file.c:fget_raw
  - fs/file.c:fget
```
```
In fs/notify/dnotify/dnotify.c (ffffffff814df959)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
```
```
In fs/aio.c (ffffffff814f0c77)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - fs/aio.c:lookup_ioctx
```
```
In fs/locks.c (ffffffff8150df15)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - fs/locks.c:fcntl_setlk
```
```
In fs/quota/quota.c (ffffffff81529ecc)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - fs/quota/quota.c:do_quotactl
```
```
In fs/proc/fd.c (ffffffff8153d3f4)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - fs/proc/fd.c:seq_show
```
```
In fs/ext4/mballoc.c (ffffffff81592611)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
```
```
In ipc/sem.c (ffffffff81644603)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - ipc/sem.c:__do_semtimedop
  - ipc/sem.c:__do_semtimedop
  - ipc/sem.c:__do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:perform_atomic_semop
  - ipc/sem.c:perform_atomic_semop_slow
```
```
In io_uring/io_uring.c (ffffffff8178c466)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - io_uring/io_uring.c:__io_uring_register
  - io_uring/io_uring.c:__do_sys_io_uring_enter
  - io_uring/io_uring.c:io_wq_submit_work
  - io_uring/io_uring.c:io_issue_sqe
```
```
In io_uring/filetable.c (ffffffff8179433b)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - io_uring/filetable.c:io_fixed_fd_remove
  - io_uring/filetable.c:io_install_fixed_file
```
```
In io_uring/uring_cmd.c (ffffffff81794ef7)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - io_uring/uring_cmd.c:io_uring_cmd_prep
```
```
In io_uring/net.c (ffffffff817976f3)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - io_uring/net.c:io_send_zc_prep
```
```
In io_uring/msg_ring.c (ffffffff81798bc8)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - io_uring/msg_ring.c:io_msg_ring
```
```
In io_uring/tctx.c (ffffffff8179c427)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - io_uring/tctx.c:io_ringfd_unregister
  - io_uring/tctx.c:io_ringfd_register
```
```
In io_uring/cancel.c (ffffffff8179e583)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - io_uring/cancel.c:__io_sync_cancel
```
```
In io_uring/rsrc.c (ffffffff817a26be)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - io_uring/rsrc.c:__io_sqe_buffers_update
  - io_uring/rsrc.c:__io_sqe_files_update
```
```
In io_uring/rw.c (ffffffff817a4011)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - io_uring/rw.c:io_prep_rw
```
```
In lib/nlattr.c (ffffffff81890c41)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - lib/nlattr.c:__nla_validate_parse
  - lib/nlattr.c:validate_nla
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff81a5cbaa)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
```
```
In drivers/tty/vt/keyboard.c (ffffffff81a63131)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl
```
```
In drivers/dma-buf/dma-heap.c (ffffffff81b6f5ca)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - drivers/dma-buf/dma-heap.c:dma_heap_ioctl
```
```
In drivers/ptp/ptp_chardev.c (ffffffff81cd3248)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
```
```
In drivers/md/dm-ioctl.c (ffffffff81d1810b)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:ctl_ioctl
```
```
In net/socket.c (ffffffff81d97d01)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - net/socket.c:__do_sys_socketcall
```
```
In net/core/sock_diag.c (ffffffff81e02bd1)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81e69201)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_create
```
```
In net/ipv4/fib_semantics.c (ffffffff81f02407)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_metrics_match
```
```
In net/ipv4/metrics.c (ffffffff81f107e5)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - net/ipv4/metrics.c:ip_metrics_convert
```
```
In net/ipv4/ipmr.c (ffffffff81f226c0)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_compat_ioctl
  - net/ipv4/ipmr.c:ipmr_ioctl
```
```
In net/ipv6/ip6mr.c (ffffffff81fb06a5)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_compat_ioctl
  - net/ipv6/ip6mr.c:ip6mr_ioctl
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
In arch/x86/entry/common.c (ffffffff821398ba)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - arch/x86/entry/common.c:__do_fast_syscall_32
  - arch/x86/entry/common.c:do_int80_syscall_32
  - arch/x86/entry/common.c:do_syscall_64
```
```
In arch/x86/events/core.c (ffffffff8100548b)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_get_hw_event_config
  - arch/x86/events/core.c:x86_setup_perfctr
  - arch/x86/events/core.c:x86_setup_perfctr
  - arch/x86/events/core.c:x86_setup_perfctr
  - arch/x86/events/core.c:x86_setup_perfctr
```
```
In arch/x86/events/msr.c (ffffffff8100fe6a)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_event_init
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff8106625f)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:fpu_xstate_prctl
```
```
In arch/x86/kernel/ptrace.c (ffffffff81067417)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:getreg32
  - arch/x86/kernel/ptrace.c:arch_ptrace
```
```
In arch/x86/kernel/tls.c (ffffffff810687d4)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:__ia32_sys_get_thread_area
  - arch/x86/kernel/tls.c:__x64_sys_get_thread_area
```
```
In kernel/sys.c (ffffffff811146e3)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_compat_sys_old_getrlimit
  - kernel/sys.c:__ia32_sys_old_getrlimit
  - kernel/sys.c:__x64_sys_old_getrlimit
  - kernel/sys.c:__ia32_compat_sys_getrlimit
  - kernel/sys.c:__ia32_sys_getrlimit
  - kernel/sys.c:__x64_sys_getrlimit
```
```
In kernel/sched/core.c (ffffffff8113d82d)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_weight_nice_write_s64
```
```
In kernel/sched/build_utility.c (ffffffff8118cdc1)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:proc_sched_autogroup_set_nice
```
```
In kernel/time/posix-timers.c (ffffffff811fc869)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__ia32_sys_clock_nanosleep_time32
  - kernel/time/posix-timers.c:__x64_sys_clock_nanosleep_time32
  - kernel/time/posix-timers.c:__ia32_sys_clock_nanosleep
  - kernel/time/posix-timers.c:__x64_sys_clock_nanosleep
  - kernel/time/posix-timers.c:__ia32_sys_clock_getres_time32
  - kernel/time/posix-timers.c:__x64_sys_clock_getres_time32
  - kernel/time/posix-timers.c:__do_sys_clock_adjtime32
  - kernel/time/posix-timers.c:__ia32_sys_clock_gettime32
  - kernel/time/posix-timers.c:__x64_sys_clock_gettime32
  - kernel/time/posix-timers.c:__ia32_sys_clock_settime32
  - kernel/time/posix-timers.c:__x64_sys_clock_settime32
  - kernel/time/posix-timers.c:__ia32_sys_clock_getres
  - kernel/time/posix-timers.c:__x64_sys_clock_getres
  - kernel/time/posix-timers.c:__do_sys_clock_adjtime
  - kernel/time/posix-timers.c:__ia32_sys_clock_gettime
  - kernel/time/posix-timers.c:__x64_sys_clock_gettime
  - kernel/time/posix-timers.c:__ia32_sys_clock_settime
  - kernel/time/posix-timers.c:__x64_sys_clock_settime
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/seccomp.c (ffffffff8126128d)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
```
```
In kernel/bpf/syscall.c (ffffffff812f1f2c)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:map_create
```
```
In kernel/events/ring_buffer.c (ffffffff8137d31c)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_to_page
```
```
In mm/hugetlb.c (ffffffff836e8727)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - mm/hugetlb.c:hugepages_setup
```
```
In fs/file.c (ffffffff814dc89a)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - fs/file.c:__ia32_sys_dup2
  - fs/file.c:__x64_sys_dup2
  - fs/file.c:ksys_dup3
  - fs/file.c:__fget_light
  - fs/file.c:__fget_light
  - fs/file.c:task_lookup_next_fd_rcu
  - fs/file.c:task_lookup_fd_rcu
  - fs/file.c:fget_task
  - fs/file.c:fget_raw
  - fs/file.c:fget
  - fs/file.c:pick_file
```
```
In fs/notify/dnotify/dnotify.c (ffffffff815161e4)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
```
```
In fs/aio.c (ffffffff81527a17)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - fs/aio.c:lookup_ioctx
```
```
In fs/locks.c (ffffffff815456e9)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - fs/locks.c:fcntl_setlk
```
```
In fs/quota/quota.c (ffffffff8156229b)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - fs/quota/quota.c:do_quotactl
```
```
In fs/proc/fd.c (ffffffff815756d4)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - fs/proc/fd.c:seq_show
```
```
In fs/ext4/mballoc.c (ffffffff815c9b30)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
```
```
In ipc/sem.c (ffffffff8167cb2b)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - ipc/sem.c:__do_semtimedop
  - ipc/sem.c:__do_semtimedop
  - ipc/sem.c:__do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:perform_atomic_semop
  - ipc/sem.c:perform_atomic_semop_slow
```
```
In io_uring/io_uring.c (ffffffff817cd9a6)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - io_uring/io_uring.c:__do_sys_io_uring_register
  - io_uring/io_uring.c:__io_uring_register
  - io_uring/io_uring.c:__do_sys_io_uring_enter
  - io_uring/io_uring.c:io_wq_submit_work
  - io_uring/io_uring.c:io_issue_sqe
```
```
In io_uring/filetable.c (ffffffff817d5021)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - io_uring/filetable.c:io_fixed_fd_remove
  - io_uring/filetable.c:io_install_fixed_file
```
```
In io_uring/uring_cmd.c (ffffffff817d5bf9)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - io_uring/uring_cmd.c:io_uring_cmd_prep
```
```
In io_uring/net.c (ffffffff817d8453)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - io_uring/net.c:io_send_zc_prep
```
```
In io_uring/msg_ring.c (ffffffff817d996d)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - io_uring/msg_ring.c:io_msg_send_fd
```
```
In io_uring/tctx.c (ffffffff817dd63a)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - io_uring/tctx.c:io_ringfd_unregister
  - io_uring/tctx.c:io_ringfd_register
```
```
In io_uring/cancel.c (ffffffff817df771)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - io_uring/cancel.c:__io_sync_cancel
```
```
In io_uring/rsrc.c (ffffffff817e381d)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - io_uring/rsrc.c:__io_sqe_buffers_update
  - io_uring/rsrc.c:__io_sqe_files_update
```
```
In io_uring/rw.c (ffffffff817e5071)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - io_uring/rw.c:io_prep_rw
```
```
In lib/nlattr.c (ffffffff818d305a)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - lib/nlattr.c:__nla_validate_parse
  - lib/nlattr.c:validate_nla
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff81aa70f1)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
```
```
In drivers/tty/vt/keyboard.c (ffffffff81aad7fe)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl
```
```
In drivers/dma-buf/dma-heap.c (ffffffff81bc2e8a)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - drivers/dma-buf/dma-heap.c:dma_heap_ioctl
```
```
In drivers/ptp/ptp_chardev.c (ffffffff81d3a8ce)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
```
```
In drivers/md/dm-ioctl.c (ffffffff81d813d5)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:ctl_ioctl
```
```
In net/socket.c (ffffffff81e06371)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - net/socket.c:__do_sys_socketcall
```
```
In net/core/sock_diag.c (ffffffff81e75141)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81ec50b1)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_create
```
```
In net/ipv4/fib_semantics.c (ffffffff81f61e67)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_metrics_match
```
```
In net/ipv4/metrics.c (ffffffff81f704d5)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - net/ipv4/metrics.c:ip_metrics_convert
```
```
In net/ipv4/ipmr.c (ffffffff81f821f0)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_compat_ioctl
  - net/ipv4/ipmr.c:ipmr_ioctl
```
```
In net/ipv6/ip6mr.c (ffffffff82010d55)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_compat_ioctl
  - net/ipv6/ip6mr.c:ip6mr_ioctl
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
In arch/x86/entry/common.c (ffffffff8221b66a)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - arch/x86/entry/common.c:__do_fast_syscall_32
  - arch/x86/entry/common.c:do_int80_emulation
  - arch/x86/entry/common.c:do_syscall_64
```
```
In arch/x86/events/core.c (ffffffff8100ab8b)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_get_hw_event_config
  - arch/x86/events/core.c:x86_setup_perfctr
  - arch/x86/events/core.c:x86_setup_perfctr
  - arch/x86/events/core.c:x86_setup_perfctr
  - arch/x86/events/core.c:x86_setup_perfctr
```
```
In arch/x86/events/msr.c (ffffffff810155aa)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_event_init
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff8106d6df)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:fpu_xstate_prctl
```
```
In arch/x86/kernel/ptrace.c (ffffffff8106e897)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:getreg32
  - arch/x86/kernel/ptrace.c:arch_ptrace
```
```
In arch/x86/kernel/tls.c (ffffffff8106fc54)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:__ia32_sys_get_thread_area
  - arch/x86/kernel/tls.c:__x64_sys_get_thread_area
```
```
In kernel/sys.c (ffffffff8111e0d3)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_compat_sys_old_getrlimit
  - kernel/sys.c:__ia32_sys_old_getrlimit
  - kernel/sys.c:__x64_sys_old_getrlimit
  - kernel/sys.c:__ia32_compat_sys_getrlimit
  - kernel/sys.c:__ia32_sys_getrlimit
  - kernel/sys.c:__x64_sys_getrlimit
```
```
In kernel/sched/core.c (ffffffff8114898d)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_weight_nice_write_s64
```
```
In kernel/sched/build_utility.c (ffffffff8119b771)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:proc_sched_autogroup_set_nice
```
```
In kernel/time/posix-timers.c (ffffffff81212a59)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__ia32_sys_clock_nanosleep_time32
  - kernel/time/posix-timers.c:__x64_sys_clock_nanosleep_time32
  - kernel/time/posix-timers.c:__ia32_sys_clock_nanosleep
  - kernel/time/posix-timers.c:__x64_sys_clock_nanosleep
  - kernel/time/posix-timers.c:__ia32_sys_clock_getres_time32
  - kernel/time/posix-timers.c:__x64_sys_clock_getres_time32
  - kernel/time/posix-timers.c:__do_sys_clock_adjtime32
  - kernel/time/posix-timers.c:__ia32_sys_clock_gettime32
  - kernel/time/posix-timers.c:__x64_sys_clock_gettime32
  - kernel/time/posix-timers.c:__ia32_sys_clock_settime32
  - kernel/time/posix-timers.c:__x64_sys_clock_settime32
  - kernel/time/posix-timers.c:__ia32_sys_clock_getres
  - kernel/time/posix-timers.c:__x64_sys_clock_getres
  - kernel/time/posix-timers.c:__do_sys_clock_adjtime
  - kernel/time/posix-timers.c:__ia32_sys_clock_gettime
  - kernel/time/posix-timers.c:__x64_sys_clock_gettime
  - kernel/time/posix-timers.c:__ia32_sys_clock_settime
  - kernel/time/posix-timers.c:__x64_sys_clock_settime
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/seccomp.c (ffffffff8127b48d)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
```
```
In kernel/bpf/syscall.c (ffffffff81310da2)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:map_create
```
```
In kernel/events/ring_buffer.c (ffffffff813a657c)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_to_page
```
```
In mm/hugetlb.c (ffffffff8391bcb7)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - mm/hugetlb.c:hugepages_setup
```
```
In fs/file.c (ffffffff8150edbe)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - fs/file.c:__ia32_sys_dup
  - fs/file.c:__x64_sys_dup
  - fs/file.c:__ia32_sys_dup2
  - fs/file.c:__x64_sys_dup2
  - fs/file.c:ksys_dup3
  - fs/file.c:__fdget_pos
  - fs/file.c:__fdget_pos
  - fs/file.c:__fdget_raw
  - fs/file.c:__fdget_raw
  - fs/file.c:task_lookup_next_fdget_rcu
  - fs/file.c:task_lookup_fdget_rcu
  - fs/file.c:lookup_fdget_rcu
  - fs/file.c:fget_task
  - fs/file.c:fget
  - fs/file.c:file_close_fd_locked
```
```
In fs/aio.c (ffffffff8155c7a7)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - fs/aio.c:lookup_ioctx
```
```
In fs/locks.c (ffffffff8157ac3e)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - fs/locks.c:fcntl_setlk
```
```
In fs/quota/quota.c (ffffffff8159898b)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - fs/quota/quota.c:do_quotactl
```
```
In fs/proc/fd.c (ffffffff815ae028)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - fs/proc/fd.c:seq_show
```
```
In fs/ext4/mballoc.c (ffffffff81602944)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
```
```
In ipc/sem.c (ffffffff816b8efb)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - ipc/sem.c:__do_semtimedop
  - ipc/sem.c:__do_semtimedop
  - ipc/sem.c:__do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:perform_atomic_semop
  - ipc/sem.c:perform_atomic_semop
```
```
In io_uring/io_uring.c (ffffffff81815f89)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - io_uring/io_uring.c:__do_sys_io_uring_enter
  - io_uring/io_uring.c:io_wq_submit_work
  - io_uring/io_uring.c:io_issue_sqe
```
```
In io_uring/filetable.c (ffffffff81818e71)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - io_uring/filetable.c:io_fixed_fd_remove
  - io_uring/filetable.c:io_install_fixed_file
```
```
In io_uring/openclose.c (ffffffff81819639)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - io_uring/openclose.c:io_close
```
```
In io_uring/uring_cmd.c (ffffffff81819e69)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - io_uring/uring_cmd.c:io_uring_cmd_prep
```
```
In io_uring/net.c (ffffffff8181c763)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - io_uring/net.c:io_send_zc_prep
```
```
In io_uring/msg_ring.c (ffffffff8181dc8d)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - io_uring/msg_ring.c:io_msg_send_fd
```
```
In io_uring/tctx.c (ffffffff8182198a)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - io_uring/tctx.c:io_ringfd_unregister
  - io_uring/tctx.c:io_ringfd_register
```
```
In io_uring/cancel.c (ffffffff81823bd1)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - io_uring/cancel.c:__io_sync_cancel
```
```
In io_uring/rsrc.c (ffffffff818278cd)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - io_uring/rsrc.c:__io_sqe_buffers_update
  - io_uring/rsrc.c:__io_sqe_files_update
```
```
In io_uring/rw.c (ffffffff8182965e)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - io_uring/rw.c:io_prep_rw_fixed
```
```
In io_uring/register.c (ffffffff8182bec7)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - io_uring/register.c:__do_sys_io_uring_register
  - io_uring/register.c:__io_uring_register
```
```
In lib/nlattr.c (ffffffff8192513a)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - lib/nlattr.c:__nla_validate_parse
  - lib/nlattr.c:validate_nla
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff81af9b81)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
```
```
In drivers/tty/vt/keyboard.c (ffffffff81b0041a)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl
```
```
In drivers/dma-buf/dma-heap.c (ffffffff81c1761e)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - drivers/dma-buf/dma-heap.c:dma_heap_ioctl
```
```
In drivers/gpu/drm/drm_ioctl.c (ffffffff81c9eab3)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_ioctl.c:drm_ioctl
  - drivers/gpu/drm/drm_ioctl.c:drm_ioctl
```
```
In drivers/ptp/ptp_chardev.c (ffffffff81df10c1)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
```
```
In drivers/md/dm-ioctl.c (ffffffff81e38a45)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:ctl_ioctl
```
```
In net/socket.c (ffffffff81ec2c31)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - net/socket.c:__do_sys_socketcall
```
```
In net/core/sock_diag.c (ffffffff81f349e1)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81f88491)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_create
```
```
In net/ipv4/fib_semantics.c (ffffffff82028437)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_metrics_match
```
```
In net/ipv4/metrics.c (ffffffff82036c05)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - net/ipv4/metrics.c:ip_metrics_convert
```
```
In net/ipv4/ipmr.c (ffffffff82048870)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_compat_ioctl
  - net/ipv4/ipmr.c:ipmr_ioctl
```
```
In net/ipv6/ip6mr.c (ffffffff820dfce5)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_compat_ioctl
  - net/ipv6/ip6mr.c:ip6mr_ioctl
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/arm64/kernel/ptrace.c (ffff800010089ec0)
Location: arch/arm64/include/asm/barrier.h:44
Inline: True
Inline callers:
  - arch/arm64/kernel/ptrace.c:ptrace_hbp_create
  - arch/arm64/kernel/ptrace.c:ptrace_hbp_create
```
```
In arch/arm64/kernel/syscall.c (ffff80001009d9bc)
Location: arch/arm64/include/asm/barrier.h:44
Inline: True
```
```
In virt/kvm/kvm_main.c (ffff8000100b51e0)
Location: arch/arm64/include/asm/barrier.h:44
Inline: True
Inline callers:
  - virt/kvm/kvm_main.c:vcpu_stat_get_per_vm
  - virt/kvm/kvm_main.c:kvm_vm_ioctl
  - virt/kvm/kvm_main.c:kvm_vm_ioctl
  - virt/kvm/kvm_main.c:kvm_vm_ioctl
  - virt/kvm/kvm_main.c:kvm_vcpu_on_spin
  - virt/kvm/kvm_main.c:kvm_vcpu_mark_page_dirty
  - virt/kvm/kvm_main.c:mark_page_dirty
  - virt/kvm/kvm_main.c:kvm_read_guest_cached
  - virt/kvm/kvm_main.c:kvm_write_guest_offset_cached
  - virt/kvm/kvm_main.c:kvm_gfn_to_hva_cache_init
  - virt/kvm/kvm_main.c:kvm_vcpu_write_guest_page
  - virt/kvm/kvm_main.c:kvm_write_guest_page
  - virt/kvm/kvm_main.c:kvm_vcpu_read_guest_atomic
  - virt/kvm/kvm_main.c:kvm_read_guest_atomic
  - virt/kvm/kvm_main.c:kvm_vcpu_read_guest_page
  - virt/kvm/kvm_main.c:kvm_read_guest_page
  - virt/kvm/kvm_main.c:kvm_vcpu_unmap
  - virt/kvm/kvm_main.c:kvm_unmap_gfn
  - virt/kvm/kvm_main.c:kvm_vcpu_map
  - virt/kvm/kvm_main.c:kvm_map_gfn
  - virt/kvm/kvm_main.c:kvm_vcpu_gfn_to_pfn
  - virt/kvm/kvm_main.c:gfn_to_pfn
  - virt/kvm/kvm_main.c:kvm_vcpu_gfn_to_pfn_atomic
  - virt/kvm/kvm_main.c:gfn_to_pfn_atomic
  - virt/kvm/kvm_main.c:gfn_to_pfn_prot
  - virt/kvm/kvm_main.c:kvm_vcpu_gfn_to_hva_prot
  - virt/kvm/kvm_main.c:gfn_to_hva_prot
  - virt/kvm/kvm_main.c:kvm_vcpu_gfn_to_hva
  - virt/kvm/kvm_main.c:gfn_to_hva
  - virt/kvm/kvm_main.c:kvm_is_visible_gfn
  - virt/kvm/kvm_main.c:kvm_clear_dirty_log_protect
  - virt/kvm/kvm_main.c:kvm_get_dirty_log_protect
  - virt/kvm/kvm_main.c:kvm_get_dirty_log
  - virt/kvm/kvm_main.c:__kvm_set_memory_region
  - virt/kvm/kvm_main.c:__kvm_set_memory_region
  - virt/kvm/kvm_main.c:__kvm_set_memory_region
  - virt/kvm/kvm_main.c:__kvm_set_memory_region
  - virt/kvm/kvm_main.c:kvm_put_kvm
  - virt/kvm/kvm_main.c:kvm_create_vm
  - virt/kvm/kvm_main.c:kvm_make_vcpus_request_mask
```
```
In virt/kvm/arm/arm.c (ffff8000100c7cf4)
Location: arch/arm64/include/asm/barrier.h:44
Inline: True
Inline callers:
  - virt/kvm/arm/arm.c:kvm_mpidr_to_vcpu
  - virt/kvm/arm/arm.c:kvm_vm_ioctl_irq_line
  - virt/kvm/arm/arm.c:kvm_vm_ioctl_irq_line
  - virt/kvm/arm/arm.c:kvm_arm_resume_guest
  - virt/kvm/arm/arm.c:kvm_arm_halt_guest
```
```
In virt/kvm/arm/mmu.c (ffff8000100c82fc)
Location: arch/arm64/include/asm/barrier.h:44
Inline: True
Inline callers:
  - virt/kvm/arm/mmu.c:handle_hva_to_gpa
  - virt/kvm/arm/mmu.c:kvm_mmu_wp_memory_region
  - virt/kvm/arm/mmu.c:stage2_unmap_vm
  - virt/kvm/arm/mmu.c:stage2_flush_vm
```
```
In virt/kvm/arm/psci.c (ffff8000100ce398)
Location: arch/arm64/include/asm/barrier.h:44
Inline: True
Inline callers:
  - virt/kvm/arm/psci.c:kvm_psci_0_2_call
```
```
In arch/arm64/kvm/guest.c (ffff8000100d1ff8)
Location: arch/arm64/include/asm/barrier.h:44
Inline: True
```
```
In virt/kvm/arm/vgic/vgic.c (ffff8000100dd4b8)
Location: arch/arm64/include/asm/barrier.h:44
Inline: True
Inline callers:
  - virt/kvm/arm/vgic/vgic.c:vgic_kick_vcpus
  - virt/kvm/arm/vgic/vgic.c:kvm_vgic_inject_irq
```
```
In virt/kvm/arm/vgic/vgic-init.c (ffff8000100dd9f0)
Location: arch/arm64/include/asm/barrier.h:44
Inline: True
Inline callers:
  - virt/kvm/arm/vgic/vgic-init.c:__kvm_vgic_destroy
  - virt/kvm/arm/vgic/vgic-init.c:kvm_vgic_create
  - virt/kvm/arm/vgic/vgic-init.c:kvm_vgic_create
  - virt/kvm/arm/vgic/vgic-init.c:kvm_vgic_create
```
```
In virt/kvm/arm/vgic/vgic-v3.c (ffff8000100e0088)
Location: arch/arm64/include/asm/barrier.h:44
Inline: True
Inline callers:
  - virt/kvm/arm/vgic/vgic-v3.c:vgic_v3_map_resources
```
```
In virt/kvm/arm/vgic/vgic-v4.c (ffff8000100e083c)
Location: arch/arm64/include/asm/barrier.h:44
Inline: True
Inline callers:
  - virt/kvm/arm/vgic/vgic-v4.c:vgic_v4_teardown
  - virt/kvm/arm/vgic/vgic-v4.c:vgic_v4_init
  - virt/kvm/arm/vgic/vgic-v4.c:vgic_v4_init
```
```
In virt/kvm/arm/vgic/vgic-mmio-v2.c (ffff8000100e2ed4)
Location: arch/arm64/include/asm/barrier.h:44
Inline: True
Inline callers:
  - virt/kvm/arm/vgic/vgic-mmio-v2.c:vgic_mmio_write_apr
  - virt/kvm/arm/vgic/vgic-mmio-v2.c:vgic_mmio_read_apr
  - virt/kvm/arm/vgic/vgic-mmio-v2.c:vgic_mmio_write_target
  - virt/kvm/arm/vgic/vgic-mmio-v2.c:vgic_mmio_write_sgir
```
```
In virt/kvm/arm/vgic/vgic-mmio-v3.c (ffff8000100e4e3c)
Location: arch/arm64/include/asm/barrier.h:44
Inline: True
Inline callers:
  - virt/kvm/arm/vgic/vgic-mmio-v3.c:vgic_v3_dispatch_sgi
  - virt/kvm/arm/vgic/vgic-mmio-v3.c:vgic_v3_set_redist_base
  - virt/kvm/arm/vgic/vgic-mmio-v3.c:vgic_v3_set_redist_base
```
```
In virt/kvm/arm/vgic/vgic-kvm-device.c (ffff8000100e6558)
Location: arch/arm64/include/asm/barrier.h:44
Inline: True
Inline callers:
  - virt/kvm/arm/vgic/vgic-kvm-device.c:vgic_v3_parse_attr
  - virt/kvm/arm/vgic/vgic-kvm-device.c:lock_all_vcpus
  - virt/kvm/arm/vgic/vgic-kvm-device.c:unlock_vcpus
```
```
In virt/kvm/arm/vgic/vgic-its.c (ffff8000100e8d1c)
Location: arch/arm64/include/asm/barrier.h:44
Inline: True
Inline callers:
  - virt/kvm/arm/vgic/vgic-its.c:vgic_its_restore_ite
  - virt/kvm/arm/vgic/vgic-its.c:vgic_its_cmd_handle_mapi
  - virt/kvm/arm/vgic/vgic-its.c:vgic_its_resolve_lpi
```
```
In virt/kvm/arm/vgic/vgic-debug.c (ffff8000100eb658)
Location: arch/arm64/include/asm/barrier.h:44
Inline: True
Inline callers:
  - virt/kvm/arm/vgic/vgic-debug.c:vgic_debug_show
```
```
In virt/kvm/irqchip.c (ffff8000100ebf84)
Location: arch/arm64/include/asm/barrier.h:44
Inline: True
Inline callers:
  - virt/kvm/irqchip.c:kvm_set_irq_routing
```
```
In virt/kvm/arm/arch_timer.c (ffff8000100ee03c)
Location: arch/arm64/include/asm/barrier.h:44
Inline: True
Inline callers:
  - virt/kvm/arm/arch_timer.c:kvm_arm_timer_set_attr
  - virt/kvm/arm/arch_timer.c:kvm_arm_timer_set_attr
  - virt/kvm/arm/arch_timer.c:kvm_timer_enable
```
```
In virt/kvm/arm/pmu.c (ffff8000100ef5b0)
Location: arch/arm64/include/asm/barrier.h:44
Inline: True
Inline callers:
  - virt/kvm/arm/pmu.c:kvm_arm_pmu_v3_set_attr
```
```
In kernel/sched/core.c (ffff800010133234)
Location: arch/arm64/include/asm/barrier.h:44
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_weight_nice_write_s64
```
```
In kernel/sched/autogroup.c (ffff80001015f480)
Location: arch/arm64/include/asm/barrier.h:44
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
```
```
In kernel/kcmp.c (ffff800010197ad8)
Location: arch/arm64/include/asm/barrier.h:44
Inline: True
Inline callers:
  - kernel/kcmp.c:kcmp_epoll_target
  - kernel/kcmp.c:get_file_raw_ptr
```
```
In kernel/time/posix-timers.c (ffff8000101ab24c)
Location: arch/arm64/include/asm/barrier.h:44
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__arm64_sys_clock_nanosleep_time32
  - kernel/time/posix-timers.c:__arm64_sys_clock_nanosleep
  - kernel/time/posix-timers.c:__arm64_sys_clock_getres_time32
  - kernel/time/posix-timers.c:__arm64_sys_clock_gettime32
  - kernel/time/posix-timers.c:__arm64_sys_clock_settime32
  - kernel/time/posix-timers.c:__arm64_sys_clock_getres
  - kernel/time/posix-timers.c:do_clock_adjtime
  - kernel/time/posix-timers.c:__arm64_sys_clock_gettime
  - kernel/time/posix-timers.c:__arm64_sys_clock_settime
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/bpf/syscall.c (ffff8000102657ac)
Location: arch/arm64/include/asm/barrier.h:44
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:map_create
```
```
In kernel/events/ring_buffer.c (ffff8000102a32c8)
Location: arch/arm64/include/asm/barrier.h:44
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_to_page
```
```
In fs/file.c (ffff8000103b196c)
Location: arch/arm64/include/asm/barrier.h:44
Inline: True
Inline callers:
  - fs/file.c:__arm64_sys_dup2
  - fs/file.c:ksys_dup3
  - fs/file.c:__fget
```
```
In fs/notify/dnotify/dnotify.c (ffff8000103eb530)
Location: arch/arm64/include/asm/barrier.h:44
Inline: True
Inline callers:
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
```
```
In fs/aio.c (ffff8000103fbf2c)
Location: arch/arm64/include/asm/barrier.h:44
Inline: True
Inline callers:
  - fs/aio.c:lookup_ioctx
```
```
In fs/io_uring.c (ffff800010400930)
Location: arch/arm64/include/asm/barrier.h:44
Inline: True
```
```
In fs/locks.c (ffff80001041969c)
Location: arch/arm64/include/asm/barrier.h:44
Inline: True
Inline callers:
  - fs/locks.c:fcntl_setlk
```
```
In fs/quota/quota.c (ffff8000104368f8)
Location: arch/arm64/include/asm/barrier.h:44
Inline: True
Inline callers:
  - fs/quota/quota.c:do_quotactl
```
```
In fs/proc/fd.c (ffff800010446ad0)
Location: arch/arm64/include/asm/barrier.h:44
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_readfd_common
  - fs/proc/fd.c:proc_fd_link
  - fs/proc/fd.c:tid_fd_mode
  - fs/proc/fd.c:seq_show
```
```
In fs/ext4/mballoc.c (ffff800010493d88)
Location: arch/arm64/include/asm/barrier.h:44
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
```
```
In ipc/sem.c (ffff8000105248ec)
Location: arch/arm64/include/asm/barrier.h:44
Inline: True
Inline callers:
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:perform_atomic_semop
  - ipc/sem.c:perform_atomic_semop
```
```
In drivers/tty/vt/vt_ioctl.c (ffff800010865f28)
Location: arch/arm64/include/asm/barrier.h:44
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
```
```
In drivers/ata/libahci.c (ffff8000109b8ad0)
Location: arch/arm64/include/asm/barrier.h:44
Inline: True
Inline callers:
  - drivers/ata/libahci.c:ahci_led_store
```
```
In drivers/ptp/ptp_chardev.c (ffff800010ac8430)
Location: arch/arm64/include/asm/barrier.h:44
Inline: True
Inline callers:
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
```
```
In net/core/sock_diag.c (ffff800010c03b0c)
Location: arch/arm64/include/asm/barrier.h:44
Inline: True
```
```
In net/netlink/af_netlink.c (ffff800010c4c648)
Location: arch/arm64/include/asm/barrier.h:44
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_create
```
```
In net/ipv4/ipmr.c (ffff800010ccf7f8)
Location: arch/arm64/include/asm/barrier.h:44
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_compat_ioctl
  - net/ipv4/ipmr.c:ipmr_ioctl
```
```
In net/ipv6/ip6mr.c (ffff800010d478d4)
Location: arch/arm64/include/asm/barrier.h:44
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_compat_ioctl
  - net/ipv6/ip6mr.c:ip6mr_ioctl
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
In kernel/sched/core.c (c03828b4)
Location: arch/arm/include/asm/barrier.h:82
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_weight_nice_write_s64
```
```
In kernel/sched/autogroup.c (c03abcf4)
Location: arch/arm/include/asm/barrier.h:82
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
```
```
In kernel/kcmp.c (c03e2df8)
Location: arch/arm/include/asm/barrier.h:82
Inline: True
Inline callers:
  - kernel/kcmp.c:__se_sys_kcmp
  - kernel/kcmp.c:get_file_raw_ptr
```
```
In kernel/time/posix-timers.c (c03f7b78)
Location: arch/arm/include/asm/barrier.h:82
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__se_sys_clock_nanosleep_time32
  - kernel/time/posix-timers.c:__se_sys_clock_nanosleep
  - kernel/time/posix-timers.c:__se_sys_clock_getres_time32
  - kernel/time/posix-timers.c:__se_sys_clock_gettime32
  - kernel/time/posix-timers.c:__se_sys_clock_settime32
  - kernel/time/posix-timers.c:__se_sys_clock_getres
  - kernel/time/posix-timers.c:do_clock_adjtime
  - kernel/time/posix-timers.c:__se_sys_clock_gettime
  - kernel/time/posix-timers.c:__se_sys_clock_settime
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/bpf/syscall.c (c0493994)
Location: arch/arm/include/asm/barrier.h:82
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_task_fd_query
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:map_create
```
```
In kernel/events/ring_buffer.c (c04d2cfc)
Location: arch/arm/include/asm/barrier.h:82
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_to_page
```
```
In fs/file.c (c0591ba8)
Location: arch/arm/include/asm/barrier.h:82
Inline: True
Inline callers:
  - fs/file.c:__se_sys_dup2
  - fs/file.c:ksys_dup3
  - fs/file.c:__fget
```
```
In fs/notify/dnotify/dnotify.c (c05c253c)
Location: arch/arm/include/asm/barrier.h:82
Inline: True
Inline callers:
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
```
```
In fs/aio.c (c05ced30)
Location: arch/arm/include/asm/barrier.h:82
Inline: True
Inline callers:
  - fs/aio.c:lookup_ioctx
```
```
In fs/io_uring.c (c05d23a0)
Location: arch/arm/include/asm/barrier.h:82
Inline: True
Inline callers:
  - fs/io_uring.c:io_import_iovec
```
```
In fs/locks.c (c05e5ba4)
Location: arch/arm/include/asm/barrier.h:82
Inline: True
Inline callers:
  - fs/locks.c:fcntl_setlk64
  - fs/locks.c:fcntl_setlk
```
```
In fs/quota/quota.c (c05fe514)
Location: arch/arm/include/asm/barrier.h:82
Inline: True
Inline callers:
  - fs/quota/quota.c:do_quotactl
```
```
In fs/proc/fd.c (c060bca8)
Location: arch/arm/include/asm/barrier.h:82
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_readfd_common
  - fs/proc/fd.c:proc_fd_link
  - fs/proc/fd.c:tid_fd_mode
  - fs/proc/fd.c:seq_show
```
```
In fs/ext4/mballoc.c (c065530c)
Location: arch/arm/include/asm/barrier.h:82
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
```
```
In ipc/sem.c (c06df64c)
Location: arch/arm/include/asm/barrier.h:82
Inline: True
Inline callers:
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:ksys_semctl
  - ipc/sem.c:semctl_main
  - ipc/sem.c:perform_atomic_semop
  - ipc/sem.c:perform_atomic_semop
```
```
In drivers/tty/vt/vt_ioctl.c (c096c6ec)
Location: arch/arm/include/asm/barrier.h:82
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
```
```
In drivers/ata/libahci.c (c0a848fc)
Location: arch/arm/include/asm/barrier.h:82
Inline: True
Inline callers:
  - drivers/ata/libahci.c:ahci_led_store
```
```
In drivers/ptp/ptp_chardev.c (c0ba7dcc)
Location: arch/arm/include/asm/barrier.h:82
Inline: True
Inline callers:
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
```
```
In sound/core/control.c (c0c879a0)
Location: arch/arm/include/asm/barrier.h:82
Inline: True
Inline callers:
  - sound/core/control.c:snd_ctl_ioctl
  - sound/core/control.c:snd_ctl_ioctl
  - sound/core/control.c:snd_ctl_ioctl
  - sound/core/control.c:snd_ctl_ioctl
  - sound/core/control.c:snd_ctl_ioctl
  - sound/core/control.c:snd_ctl_ioctl
  - sound/core/control.c:snd_ctl_tlv_ioctl
  - sound/core/control.c:snd_ctl_tlv_ioctl
  - sound/core/control.c:snd_ctl_tlv_ioctl
  - sound/core/control.c:snd_ctl_elem_add_user
  - sound/core/control.c:snd_ctl_elem_add_user
  - sound/core/control.c:snd_ctl_elem_user_put
  - sound/core/control.c:snd_ctl_elem_user_put
  - sound/core/control.c:snd_ctl_elem_user_get
  - sound/core/control.c:snd_ctl_elem_user_enum_info
  - sound/core/control.c:snd_ctl_elem_user_info
  - sound/core/control.c:snd_ctl_elem_info_user
  - sound/core/control.c:snd_ctl_activate_id
```
```
In sound/core/pcm.c (c0c90658)
Location: arch/arm/include/asm/barrier.h:82
Inline: True
Inline callers:
  - sound/core/pcm.c:snd_pcm_control_ioctl
```
```
In sound/core/pcm_lib.c (c0c98f50)
Location: arch/arm/include/asm/barrier.h:82
Inline: True
Inline callers:
  - sound/core/pcm_lib.c:pcm_chmap_ctl_get
```
```
In net/core/sock_diag.c (c0d1ce78)
Location: arch/arm/include/asm/barrier.h:82
Inline: True
```
```
In net/netlink/af_netlink.c (c0d5d464)
Location: arch/arm/include/asm/barrier.h:82
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_create
```
```
In net/ipv4/ipmr.c (c0dd9ea0)
Location: arch/arm/include/asm/barrier.h:82
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_ioctl
```
```
In net/ipv6/ip6mr.c (c0e4955c)
Location: arch/arm/include/asm/barrier.h:82
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_ioctl
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
In arch/powerpc/kernel/ptrace.c (c000000000018838)
Location: include/linux/nospec.h:22
Inline: True
Inline callers:
  - arch/powerpc/kernel/ptrace.c:ptrace_put_reg
  - arch/powerpc/kernel/ptrace.c:ptrace_get_reg
```
```
In arch/powerpc/kvm/book3s_hv_rm_xics.c (c0000000001237a0)
Location: include/linux/nospec.h:22
Inline: True
Inline callers:
  - arch/powerpc/kvm/book3s_hv_rm_xics.c:xics_rm_h_ipi
  - arch/powerpc/kvm/book3s_hv_rm_xics.c:icp_rm_deliver_irq
```
```
In arch/powerpc/kvm/book3s_hv_rm_xive.c (c000000000124ee0)
Location: include/linux/nospec.h:22
Inline: True
Inline callers:
  - arch/powerpc/kvm/book3s_hv_rm_xive.c:xive_rm_h_ipi
  - arch/powerpc/kvm/book3s_hv_rm_xive.c:xive_rm_h_ipoll
```
```
In kernel/sys.c (c00000000015dc30)
Location: include/linux/nospec.h:22
Inline: True
Inline callers:
  - kernel/sys.c:__se_compat_sys_old_getrlimit
  - kernel/sys.c:__se_sys_old_getrlimit
```
```
In kernel/sched/core.c (c00000000017e0f4)
Location: include/linux/nospec.h:22
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_weight_nice_write_s64
```
```
In kernel/sched/autogroup.c (c0000000001b4978)
Location: include/linux/nospec.h:22
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
```
```
In kernel/kcmp.c (c0000000001f7cd8)
Location: include/linux/nospec.h:22
Inline: True
Inline callers:
  - kernel/kcmp.c:__se_sys_kcmp
  - kernel/kcmp.c:get_file_raw_ptr
```
```
In kernel/time/posix-timers.c (c00000000020f668)
Location: include/linux/nospec.h:22
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__se_sys_clock_nanosleep_time32
  - kernel/time/posix-timers.c:__se_sys_clock_nanosleep
  - kernel/time/posix-timers.c:__se_sys_clock_getres_time32
  - kernel/time/posix-timers.c:__se_sys_clock_gettime32
  - kernel/time/posix-timers.c:__se_sys_clock_settime32
  - kernel/time/posix-timers.c:__se_sys_clock_getres
  - kernel/time/posix-timers.c:do_clock_adjtime
  - kernel/time/posix-timers.c:__se_sys_clock_gettime
  - kernel/time/posix-timers.c:__se_sys_clock_settime
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/bpf/syscall.c (c00000000030a2cc)
Location: include/linux/nospec.h:22
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:map_create
```
```
In kernel/events/ring_buffer.c (c000000000355794)
Location: include/linux/nospec.h:22
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_to_page
```
```
In fs/file.c (c0000000004ad030)
Location: include/linux/nospec.h:22
Inline: True
Inline callers:
  - fs/file.c:__se_sys_dup2
  - fs/file.c:ksys_dup3
  - fs/file.c:__fget
```
```
In fs/notify/dnotify/dnotify.c (c0000000004f288c)
Location: include/linux/nospec.h:22
Inline: True
Inline callers:
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
```
```
In fs/aio.c (c000000000503f94)
Location: include/linux/nospec.h:22
Inline: True
Inline callers:
  - fs/aio.c:lookup_ioctx
```
```
In fs/io_uring.c (c00000000050a2b8)
Location: include/linux/nospec.h:22
Inline: True
```
```
In fs/locks.c (c00000000052919c)
Location: include/linux/nospec.h:22
Inline: True
Inline callers:
  - fs/locks.c:fcntl_setlk
```
```
In fs/quota/quota.c (c000000000548af0)
Location: include/linux/nospec.h:22
Inline: True
Inline callers:
  - fs/quota/quota.c:do_quotactl
```
```
In fs/proc/fd.c (c00000000055cb70)
Location: include/linux/nospec.h:22
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_readfd_common
  - fs/proc/fd.c:proc_fd_link
  - fs/proc/fd.c:tid_fd_mode
  - fs/proc/fd.c:seq_show
```
```
In fs/ext4/mballoc.c (c0000000005bcc1c)
Location: include/linux/nospec.h:22
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
```
```
In ipc/sem.c (c00000000066f050)
Location: include/linux/nospec.h:22
Inline: True
Inline callers:
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:perform_atomic_semop
  - ipc/sem.c:perform_atomic_semop
```
```
In drivers/tty/vt/vt_ioctl.c (c000000000905f88)
Location: include/linux/nospec.h:22
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
```
```
In drivers/vfio/pci/vfio_pci.c (c000000000ab6220)
Location: include/linux/nospec.h:22
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
```
```
In drivers/ptp/ptp_chardev.c (c000000000ba9bb0)
Location: include/linux/nospec.h:22
Inline: True
Inline callers:
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
```
```
In net/socket.c (c000000000c7d6ec)
Location: include/linux/nospec.h:22
Inline: True
Inline callers:
  - net/socket.c:__se_sys_socketcall
```
```
In net/core/sock_diag.c (c000000000ced414)
Location: include/linux/nospec.h:22
Inline: True
```
```
In net/netlink/af_netlink.c (c000000000d4b040)
Location: include/linux/nospec.h:22
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_create
```
```
In net/ipv4/ipmr.c (c000000000ded994)
Location: include/linux/nospec.h:22
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_compat_ioctl
  - net/ipv4/ipmr.c:ipmr_ioctl
```
```
In net/ipv6/ip6mr.c (c000000000e7cf14)
Location: include/linux/nospec.h:22
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_compat_ioctl
  - net/ipv6/ip6mr.c:ip6mr_ioctl
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
In kernel/sched/core.c (ffffffe0000e5c9c)
Location: include/linux/nospec.h:22
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_weight_nice_write_s64
```
```
In kernel/sched/autogroup.c (ffffffe000103740)
Location: include/linux/nospec.h:22
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
```
```
In kernel/kcmp.c (ffffffe000128cac)
Location: include/linux/nospec.h:22
Inline: True
Inline callers:
  - kernel/kcmp.c:__se_sys_kcmp
  - kernel/kcmp.c:get_file_raw_ptr
```
```
In kernel/time/posix-timers.c (ffffffe000136d96)
Location: include/linux/nospec.h:22
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__se_sys_clock_nanosleep
  - kernel/time/posix-timers.c:__se_sys_clock_getres
  - kernel/time/posix-timers.c:do_clock_adjtime
  - kernel/time/posix-timers.c:__se_sys_clock_gettime
  - kernel/time/posix-timers.c:__se_sys_clock_settime
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/bpf/syscall.c (ffffffe0001a1066)
Location: include/linux/nospec.h:22
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:map_create
```
```
In kernel/events/ring_buffer.c (ffffffe0001d1b04)
Location: include/linux/nospec.h:22
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_to_page
```
```
In fs/file.c (ffffffe0002768f4)
Location: include/linux/nospec.h:22
Inline: True
Inline callers:
  - fs/file.c:__se_sys_dup2
  - fs/file.c:ksys_dup3
  - fs/file.c:__fget
```
```
In fs/notify/dnotify/dnotify.c (ffffffe00029f920)
Location: include/linux/nospec.h:22
Inline: True
Inline callers:
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
```
```
In fs/aio.c (ffffffe0002a9284)
Location: include/linux/nospec.h:22
Inline: True
Inline callers:
  - fs/aio.c:lookup_ioctx
```
```
In fs/io_uring.c (ffffffe0002acfd6)
Location: include/linux/nospec.h:22
Inline: True
```
```
In fs/locks.c (ffffffe0002bfe26)
Location: include/linux/nospec.h:22
Inline: True
Inline callers:
  - fs/locks.c:fcntl_setlk
```
```
In fs/quota/quota.c (ffffffe0002d0ec2)
Location: include/linux/nospec.h:22
Inline: True
Inline callers:
  - fs/quota/quota.c:do_quotactl
```
```
In fs/proc/fd.c (ffffffe0002dca16)
Location: include/linux/nospec.h:22
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_readfd_common
  - fs/proc/fd.c:proc_fd_link
  - fs/proc/fd.c:tid_fd_mode
  - fs/proc/fd.c:seq_show
```
```
In fs/ext4/mballoc.c (ffffffe000318844)
Location: include/linux/nospec.h:22
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
```
```
In ipc/sem.c (ffffffe0003896bc)
Location: include/linux/nospec.h:22
Inline: True
Inline callers:
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:__se_sys_semctl
  - ipc/sem.c:semctl_main
  - ipc/sem.c:perform_atomic_semop
  - ipc/sem.c:perform_atomic_semop
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffe00053c20a)
Location: include/linux/nospec.h:22
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
```
```
In drivers/ptp/ptp_chardev.c (ffffffe0006c64b8)
Location: include/linux/nospec.h:22
Inline: True
Inline callers:
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
```
```
In net/core/sock_diag.c (ffffffe000782b14)
Location: include/linux/nospec.h:22
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffe0007b9a4c)
Location: include/linux/nospec.h:22
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_create
```
```
In net/ipv4/ipmr.c (ffffffe000821abc)
Location: include/linux/nospec.h:22
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_ioctl
```
```
In net/ipv6/ip6mr.c (ffffffe0008817e2)
Location: include/linux/nospec.h:22
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_ioctl
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
In arch/x86/entry/common.c (ffffffff810047af)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - arch/x86/entry/common.c:do_fast_syscall_32
  - arch/x86/entry/common.c:do_int80_syscall_32
  - arch/x86/entry/common.c:do_syscall_64
  - arch/x86/entry/common.c:do_syscall_64
```
```
In arch/x86/events/core.c (ffffffff81006e52)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_setup_perfctr
  - arch/x86/events/core.c:x86_setup_perfctr
  - arch/x86/events/core.c:x86_setup_perfctr
  - arch/x86/events/core.c:x86_setup_perfctr
```
```
In arch/x86/events/msr.c (ffffffff8100b792)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_event_init
```
```
In arch/x86/kernel/ptrace.c (ffffffff81041975)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
```
```
In arch/x86/kernel/tls.c (ffffffff8104352e)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:do_get_thread_area
```
```
In kernel/sys.c (ffffffff810b412f)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - kernel/sys.c:__x32_compat_sys_old_getrlimit
  - kernel/sys.c:__ia32_compat_sys_old_getrlimit
  - kernel/sys.c:__ia32_sys_old_getrlimit
  - kernel/sys.c:__x64_sys_old_getrlimit
```
```
In kernel/sched/core.c (ffffffff810cd1f3)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_weight_nice_write_s64
```
```
In kernel/sched/autogroup.c (ffffffff810f3dad)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
```
```
In kernel/kcmp.c (ffffffff81129343)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/kcmp.c:get_file_raw_ptr
```
```
In kernel/time/posix-timers.c (ffffffff81139855)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__ia32_sys_clock_nanosleep_time32
  - kernel/time/posix-timers.c:__x64_sys_clock_nanosleep_time32
  - kernel/time/posix-timers.c:__ia32_sys_clock_nanosleep
  - kernel/time/posix-timers.c:__x64_sys_clock_nanosleep
  - kernel/time/posix-timers.c:__ia32_sys_clock_getres_time32
  - kernel/time/posix-timers.c:__x64_sys_clock_getres_time32
  - kernel/time/posix-timers.c:__ia32_sys_clock_gettime32
  - kernel/time/posix-timers.c:__x64_sys_clock_gettime32
  - kernel/time/posix-timers.c:__ia32_sys_clock_settime32
  - kernel/time/posix-timers.c:__x64_sys_clock_settime32
  - kernel/time/posix-timers.c:__ia32_sys_clock_getres
  - kernel/time/posix-timers.c:__x64_sys_clock_getres
  - kernel/time/posix-timers.c:do_clock_adjtime
  - kernel/time/posix-timers.c:__ia32_sys_clock_gettime
  - kernel/time/posix-timers.c:__x64_sys_clock_gettime
  - kernel/time/posix-timers.c:__ia32_sys_clock_settime
  - kernel/time/posix-timers.c:__x64_sys_clock_settime
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/bpf/syscall.c (ffffffff811da698)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:map_create
```
```
In kernel/events/ring_buffer.c (ffffffff81210e01)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_to_page
```
```
In fs/file.c (ffffffff812f83c1)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - fs/file.c:__ia32_sys_dup2
  - fs/file.c:__x64_sys_dup2
  - fs/file.c:ksys_dup3
  - fs/file.c:__fget
```
```
In fs/notify/dnotify/dnotify.c (ffffffff813270fb)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
```
```
In fs/aio.c (ffffffff81333348)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - fs/aio.c:lookup_ioctx
```
```
In fs/io_uring.c (ffffffff81338f58)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
```
```
In fs/locks.c (ffffffff8134f16a)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - fs/locks.c:fcntl_setlk
```
```
In fs/quota/quota.c (ffffffff81364fef)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - fs/quota/quota.c:do_quotactl
```
```
In fs/proc/fd.c (ffffffff81372dde)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_readfd_common
  - fs/proc/fd.c:proc_fd_link
  - fs/proc/fd.c:tid_fd_mode
  - fs/proc/fd.c:seq_show
```
```
In fs/ext4/mballoc.c (ffffffff813b561b)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
```
```
In ipc/sem.c (ffffffff8143517c)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:perform_atomic_semop
  - ipc/sem.c:perform_atomic_semop
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff81657a21)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
```
```
In drivers/ptp/ptp_chardev.c (ffffffff81826d0f)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
```
```
In net/socket.c (ffffffff818b0c17)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
```
```
In net/core/sock_diag.c (ffffffff81900260)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff8193ead2)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_create
```
```
In net/ipv4/ipmr.c (ffffffff819b3d65)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_compat_ioctl
  - net/ipv4/ipmr.c:ipmr_ioctl
```
```
In net/ipv6/ip6mr.c (ffffffff81a1c562)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_compat_ioctl
  - net/ipv6/ip6mr.c:ip6mr_ioctl
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
In arch/x86/entry/common.c (ffffffff81002dfe)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - arch/x86/entry/common.c:do_fast_syscall_32
  - arch/x86/entry/common.c:do_int80_syscall_32
  - arch/x86/entry/common.c:do_syscall_64
  - arch/x86/entry/common.c:do_syscall_64
```
```
In arch/x86/events/core.c (ffffffff81005572)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_setup_perfctr
  - arch/x86/events/core.c:x86_setup_perfctr
  - arch/x86/events/core.c:x86_setup_perfctr
  - arch/x86/events/core.c:x86_setup_perfctr
```
```
In arch/x86/events/msr.c (ffffffff8100a122)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_event_init
```
```
In arch/x86/kernel/ptrace.c (ffffffff81031035)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
```
```
In arch/x86/kernel/tls.c (ffffffff81032b4e)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:do_get_thread_area
```
```
In kernel/sys.c (ffffffff810a2a5f)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - kernel/sys.c:__x32_compat_sys_old_getrlimit
  - kernel/sys.c:__ia32_compat_sys_old_getrlimit
  - kernel/sys.c:__ia32_sys_old_getrlimit
  - kernel/sys.c:__x64_sys_old_getrlimit
```
```
In kernel/sched/core.c (ffffffff810bba53)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_weight_nice_write_s64
```
```
In kernel/sched/autogroup.c (ffffffff810e3f41)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
```
```
In kernel/kcmp.c (ffffffff8111bbd3)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/kcmp.c:get_file_raw_ptr
```
```
In kernel/time/posix-timers.c (ffffffff8112c2a5)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__ia32_sys_clock_nanosleep_time32
  - kernel/time/posix-timers.c:__x64_sys_clock_nanosleep_time32
  - kernel/time/posix-timers.c:__ia32_sys_clock_nanosleep
  - kernel/time/posix-timers.c:__x64_sys_clock_nanosleep
  - kernel/time/posix-timers.c:__ia32_sys_clock_getres_time32
  - kernel/time/posix-timers.c:__x64_sys_clock_getres_time32
  - kernel/time/posix-timers.c:__ia32_sys_clock_gettime32
  - kernel/time/posix-timers.c:__x64_sys_clock_gettime32
  - kernel/time/posix-timers.c:__ia32_sys_clock_settime32
  - kernel/time/posix-timers.c:__x64_sys_clock_settime32
  - kernel/time/posix-timers.c:__ia32_sys_clock_getres
  - kernel/time/posix-timers.c:__x64_sys_clock_getres
  - kernel/time/posix-timers.c:do_clock_adjtime
  - kernel/time/posix-timers.c:__ia32_sys_clock_gettime
  - kernel/time/posix-timers.c:__x64_sys_clock_gettime
  - kernel/time/posix-timers.c:__ia32_sys_clock_settime
  - kernel/time/posix-timers.c:__x64_sys_clock_settime
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/bpf/syscall.c (ffffffff811cd458)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:map_create
```
```
In kernel/events/ring_buffer.c (ffffffff81203b91)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_to_page
```
```
In fs/file.c (ffffffff812e8fe1)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - fs/file.c:__ia32_sys_dup2
  - fs/file.c:__x64_sys_dup2
  - fs/file.c:ksys_dup3
  - fs/file.c:__fget
```
```
In fs/notify/dnotify/dnotify.c (ffffffff81317c9b)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
```
```
In fs/aio.c (ffffffff81323fb8)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - fs/aio.c:lookup_ioctx
```
```
In fs/io_uring.c (ffffffff81329c88)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
```
```
In fs/locks.c (ffffffff8133fe4a)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - fs/locks.c:fcntl_setlk
```
```
In fs/quota/quota.c (ffffffff81355c8f)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - fs/quota/quota.c:do_quotactl
```
```
In fs/proc/fd.c (ffffffff813638ae)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_readfd_common
  - fs/proc/fd.c:proc_fd_link
  - fs/proc/fd.c:tid_fd_mode
  - fs/proc/fd.c:seq_show
```
```
In fs/ext4/mballoc.c (ffffffff813a60ab)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
```
```
In ipc/sem.c (ffffffff81425bfc)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:perform_atomic_semop
  - ipc/sem.c:perform_atomic_semop
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff81637db1)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff81781090)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
```
```
In drivers/ptp/ptp_chardev.c (ffffffff817ee39f)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
```
```
In net/socket.c (ffffffff8186ab67)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
```
```
In net/core/sock_diag.c (ffffffff818ba090)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff818f85d2)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_create
```
```
In net/ipv4/ipmr.c (ffffffff81970395)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_compat_ioctl
  - net/ipv4/ipmr.c:ipmr_ioctl
```
```
In net/ipv6/ip6mr.c (ffffffff819d9322)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_compat_ioctl
  - net/ipv6/ip6mr.c:ip6mr_ioctl
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
In arch/x86/entry/common.c (ffffffff8100476f)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - arch/x86/entry/common.c:do_fast_syscall_32
  - arch/x86/entry/common.c:do_int80_syscall_32
  - arch/x86/entry/common.c:do_syscall_64
  - arch/x86/entry/common.c:do_syscall_64
```
```
In arch/x86/events/core.c (ffffffff81006e12)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_setup_perfctr
  - arch/x86/events/core.c:x86_setup_perfctr
  - arch/x86/events/core.c:x86_setup_perfctr
  - arch/x86/events/core.c:x86_setup_perfctr
```
```
In arch/x86/events/msr.c (ffffffff8100b752)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_event_init
```
```
In arch/x86/kernel/ptrace.c (ffffffff810417b5)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
```
```
In arch/x86/kernel/tls.c (ffffffff8104336e)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:do_get_thread_area
```
```
In kernel/sys.c (ffffffff810b368f)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - kernel/sys.c:__x32_compat_sys_old_getrlimit
  - kernel/sys.c:__ia32_compat_sys_old_getrlimit
  - kernel/sys.c:__ia32_sys_old_getrlimit
  - kernel/sys.c:__x64_sys_old_getrlimit
```
```
In kernel/sched/core.c (ffffffff810cc623)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_weight_nice_write_s64
```
```
In kernel/sched/autogroup.c (ffffffff810f0f61)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
```
```
In kernel/kcmp.c (ffffffff81127063)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/kcmp.c:get_file_raw_ptr
```
```
In kernel/time/posix-timers.c (ffffffff81137575)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__ia32_sys_clock_nanosleep_time32
  - kernel/time/posix-timers.c:__x64_sys_clock_nanosleep_time32
  - kernel/time/posix-timers.c:__ia32_sys_clock_nanosleep
  - kernel/time/posix-timers.c:__x64_sys_clock_nanosleep
  - kernel/time/posix-timers.c:__ia32_sys_clock_getres_time32
  - kernel/time/posix-timers.c:__x64_sys_clock_getres_time32
  - kernel/time/posix-timers.c:__ia32_sys_clock_gettime32
  - kernel/time/posix-timers.c:__x64_sys_clock_gettime32
  - kernel/time/posix-timers.c:__ia32_sys_clock_settime32
  - kernel/time/posix-timers.c:__x64_sys_clock_settime32
  - kernel/time/posix-timers.c:__ia32_sys_clock_getres
  - kernel/time/posix-timers.c:__x64_sys_clock_getres
  - kernel/time/posix-timers.c:do_clock_adjtime
  - kernel/time/posix-timers.c:__ia32_sys_clock_gettime
  - kernel/time/posix-timers.c:__x64_sys_clock_gettime
  - kernel/time/posix-timers.c:__ia32_sys_clock_settime
  - kernel/time/posix-timers.c:__x64_sys_clock_settime
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/bpf/syscall.c (ffffffff811d8468)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:map_create
```
```
In kernel/events/ring_buffer.c (ffffffff8120eba1)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_to_page
```
```
In fs/file.c (ffffffff812f61d1)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - fs/file.c:__ia32_sys_dup2
  - fs/file.c:__x64_sys_dup2
  - fs/file.c:ksys_dup3
  - fs/file.c:__fget
```
```
In fs/notify/dnotify/dnotify.c (ffffffff81324bcb)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
```
```
In fs/aio.c (ffffffff81330e18)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - fs/aio.c:lookup_ioctx
```
```
In fs/io_uring.c (ffffffff81336a28)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
```
```
In fs/locks.c (ffffffff8134cc3a)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - fs/locks.c:fcntl_setlk
```
```
In fs/quota/quota.c (ffffffff81362abf)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - fs/quota/quota.c:do_quotactl
```
```
In fs/proc/fd.c (ffffffff813708ae)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_readfd_common
  - fs/proc/fd.c:proc_fd_link
  - fs/proc/fd.c:tid_fd_mode
  - fs/proc/fd.c:seq_show
```
```
In fs/ext4/mballoc.c (ffffffff813b2e7b)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
```
```
In ipc/sem.c (ffffffff8143131c)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:perform_atomic_semop
  - ipc/sem.c:perform_atomic_semop
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff81685de1)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff817cbe60)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
```
```
In drivers/ptp/ptp_chardev.c (ffffffff81873c4f)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
```
```
In net/socket.c (ffffffff81901c17)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
```
```
In net/core/sock_diag.c (ffffffff81951290)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff8198fc62)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_create
```
```
In net/ipv4/ipmr.c (ffffffff81a1e605)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_compat_ioctl
  - net/ipv4/ipmr.c:ipmr_ioctl
```
```
In net/ipv6/ip6mr.c (ffffffff81a86fe2)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_compat_ioctl
  - net/ipv6/ip6mr.c:ip6mr_ioctl
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
In arch/x86/entry/common.c (ffffffff810048af)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - arch/x86/entry/common.c:do_fast_syscall_32
  - arch/x86/entry/common.c:do_int80_syscall_32
  - arch/x86/entry/common.c:do_syscall_64
  - arch/x86/entry/common.c:do_syscall_64
```
```
In arch/x86/events/core.c (ffffffff81006f72)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_setup_perfctr
  - arch/x86/events/core.c:x86_setup_perfctr
  - arch/x86/events/core.c:x86_setup_perfctr
  - arch/x86/events/core.c:x86_setup_perfctr
```
```
In arch/x86/events/msr.c (ffffffff8100b932)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_event_init
```
```
In arch/x86/kernel/ptrace.c (ffffffff81042b95)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
```
```
In arch/x86/kernel/tls.c (ffffffff8104476e)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:do_get_thread_area
```
```
In kernel/sys.c (ffffffff810bbfc1)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - kernel/sys.c:__x32_compat_sys_old_getrlimit
  - kernel/sys.c:__ia32_compat_sys_old_getrlimit
  - kernel/sys.c:__ia32_sys_old_getrlimit
  - kernel/sys.c:__x64_sys_old_getrlimit
```
```
In kernel/sched/core.c (ffffffff810d4fc3)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_weight_nice_write_s64
```
```
In kernel/sched/autogroup.c (ffffffff810fbf8d)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
```
```
In kernel/kcmp.c (ffffffff811336aa)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/kcmp.c:get_file_raw_ptr
```
```
In kernel/time/posix-timers.c (ffffffff81144005)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__ia32_sys_clock_nanosleep_time32
  - kernel/time/posix-timers.c:__x64_sys_clock_nanosleep_time32
  - kernel/time/posix-timers.c:__ia32_sys_clock_nanosleep
  - kernel/time/posix-timers.c:__x64_sys_clock_nanosleep
  - kernel/time/posix-timers.c:__ia32_sys_clock_getres_time32
  - kernel/time/posix-timers.c:__x64_sys_clock_getres_time32
  - kernel/time/posix-timers.c:__ia32_sys_clock_gettime32
  - kernel/time/posix-timers.c:__x64_sys_clock_gettime32
  - kernel/time/posix-timers.c:__ia32_sys_clock_settime32
  - kernel/time/posix-timers.c:__x64_sys_clock_settime32
  - kernel/time/posix-timers.c:__ia32_sys_clock_getres
  - kernel/time/posix-timers.c:__x64_sys_clock_getres
  - kernel/time/posix-timers.c:do_clock_adjtime
  - kernel/time/posix-timers.c:__ia32_sys_clock_gettime
  - kernel/time/posix-timers.c:__x64_sys_clock_gettime
  - kernel/time/posix-timers.c:__ia32_sys_clock_settime
  - kernel/time/posix-timers.c:__x64_sys_clock_settime
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/bpf/syscall.c (ffffffff811e67f9)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:map_create
```
```
In kernel/events/ring_buffer.c (ffffffff8121dab1)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_to_page
```
```
In fs/file.c (ffffffff813073ec)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - fs/file.c:__ia32_sys_dup2
  - fs/file.c:__x64_sys_dup2
  - fs/file.c:ksys_dup3
  - fs/file.c:__fget
```
```
In fs/notify/dnotify/dnotify.c (ffffffff81336946)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
```
```
In fs/aio.c (ffffffff813439e9)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - fs/aio.c:lookup_ioctx
```
```
In fs/io_uring.c (ffffffff81349af8)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
```
```
In fs/locks.c (ffffffff8136017a)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - fs/locks.c:fcntl_setlk
```
```
In fs/quota/quota.c (ffffffff8137616f)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - fs/quota/quota.c:do_quotactl
```
```
In fs/proc/fd.c (ffffffff8138428d)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_readfd_common
  - fs/proc/fd.c:proc_fd_link
  - fs/proc/fd.c:tid_fd_mode
  - fs/proc/fd.c:seq_show
```
```
In fs/ext4/mballoc.c (ffffffff813c79d5)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
```
```
In ipc/sem.c (ffffffff814479ed)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:perform_atomic_semop
  - ipc/sem.c:perform_atomic_semop
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff816a03e1)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff817e6100)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
```
```
In drivers/ptp/ptp_chardev.c (ffffffff8188f5ff)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
```
```
In net/socket.c (ffffffff81922bb7)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
```
```
In net/core/sock_diag.c (ffffffff81972c80)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff819b2542)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_create
```
```
In net/ipv4/ipmr.c (ffffffff81a299a7)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_compat_ioctl
  - net/ipv4/ipmr.c:ipmr_ioctl
```
```
In net/ipv6/ip6mr.c (ffffffff81a93bac)
Location: arch/x86/include/asm/barrier.h:36
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_compat_ioctl
  - net/ipv6/ip6mr.c:ip6mr_ioctl
```
</details>
</li>
</ul>

## Differences
