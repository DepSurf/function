# Function: <code>task_rlimit</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mmap.c (ffffffff8106f71e)
Location: include/linux/sched.h:3173
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:arch_pick_mmap_layout
  - arch/x86/mm/mmap.c:arch_pick_mmap_layout
```
```
In kernel/fork.c (ffffffff8107e90a)
Location: include/linux/sched.h:3173
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/signal.c (ffffffff8108cd95)
Location: include/linux/sched.h:3173
Inline: True
Inline callers:
  - kernel/signal.c:__sigqueue_alloc
```
```
In kernel/sys.c (ffffffff81092f02)
Location: include/linux/sched.h:3173
Inline: True
```
```
In kernel/sched/core.c (ffffffff810a99d4)
Location: include/linux/sched.h:3173
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:SyS_nice
```
```
In kernel/sched/rt.c (ffffffff810c01e7)
Location: include/linux/sched.h:3173
Inline: True
Inline callers:
  - kernel/sched/rt.c:task_tick_rt
```
```
In kernel/bpf/syscall.c (ffffffff811730ec)
Location: include/linux/sched.h:3173
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:SyS_bpf
```
```
In kernel/events/core.c (ffffffff8118144b)
Location: include/linux/sched.h:3173
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
```
```
In mm/filemap.c (ffffffff8118d739)
Location: include/linux/sched.h:3173
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_write_iter
```
```
In mm/mlock.c (ffffffff811c2c5e)
Location: include/linux/sched.h:3173
Inline: True
Inline callers:
  - mm/mlock.c:do_mlock
  - mm/mlock.c:do_mlock
  - mm/mlock.c:SyS_mlockall
  - mm/mlock.c:SyS_mlockall
  - mm/mlock.c:user_shm_lock
```
```
In mm/mmap.c (ffffffff811c614e)
Location: include/linux/sched.h:3173
Inline: True
Inline callers:
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:do_brk
  - mm/mmap.c:do_brk
  - mm/mmap.c:SyS_brk
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
  - mm/mmap.c:do_mmap
```
```
In mm/mremap.c (ffffffff811c9214)
Location: include/linux/sched.h:3173
Inline: True
Inline callers:
  - mm/mremap.c:vma_to_resize
```
```
In fs/exec.c (ffffffff81212546)
Location: include/linux/sched.h:3173
Inline: True
Inline callers:
  - fs/exec.c:setup_arg_pages
```
```
In fs/select.c (ffffffff81221e9c)
Location: include/linux/sched.h:3173
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
```
```
In fs/attr.c (ffffffff81229304)
Location: include/linux/sched.h:3173
Inline: True
```
```
In fs/file.c (ffffffff8122a893)
Location: include/linux/sched.h:3173
Inline: True
Inline callers:
  - fs/file.c:get_unused_fd_flags
  - fs/file.c:replace_fd
  - fs/file.c:SyS_dup2
  - fs/file.c:f_dupfd
  - fs/file.c:f_dupfd
```
```
In fs/coredump.c (ffffffff8126f07c)
Location: include/linux/sched.h:3173
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
```
```
In fs/proc/array.c (ffffffff81280ff0)
Location: include/linux/sched.h:3173
Inline: True
Inline callers:
  - fs/proc/array.c:proc_pid_status
```
```
In ipc/shm.c (ffffffff8132b2a6)
Location: include/linux/sched.h:3173
Inline: True
Inline callers:
  - ipc/shm.c:SyS_shmctl
```
```
In ipc/mqueue.c (ffffffff8132c71b)
Location: include/linux/sched.h:3173
Inline: True
Inline callers:
  - ipc/mqueue.c:mqueue_get_inode
```
```
In security/selinux/hooks.c (ffffffff81346b7a)
Location: include/linux/sched.h:3173
Inline: True
```
```
In net/unix/af_unix.c (ffffffff817be667)
Location: include/linux/sched.h:3173
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_scm_to_skb
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mmap.c (ffffffff8106f47e)
Location: include/linux/sched.h:3450
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:arch_pick_mmap_layout
  - arch/x86/mm/mmap.c:arch_pick_mmap_layout
```
```
In kernel/fork.c (ffffffff81080578)
Location: include/linux/sched.h:3450
Inline: True
```
```
In kernel/signal.c (ffffffff8108ff65)
Location: include/linux/sched.h:3450
Inline: True
Inline callers:
  - kernel/signal.c:__sigqueue_alloc
```
```
In kernel/sys.c (ffffffff81096092)
Location: include/linux/sched.h:3450
Inline: True
```
```
In kernel/sched/core.c (ffffffff810acb8d)
Location: include/linux/sched.h:3450
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:SyS_nice
```
```
In kernel/sched/rt.c (ffffffff810c3c17)
Location: include/linux/sched.h:3450
Inline: True
Inline callers:
  - kernel/sched/rt.c:task_tick_rt
```
```
In kernel/bpf/syscall.c (ffffffff81181aa4)
Location: include/linux/sched.h:3450
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_map_precharge_memlock
```
```
In kernel/events/core.c (ffffffff81193220)
Location: include/linux/sched.h:3450
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
```
```
In mm/filemap.c (ffffffff811a29f0)
Location: include/linux/sched.h:3450
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_write_iter
```
```
In mm/mlock.c (ffffffff811dfbe7)
Location: include/linux/sched.h:3450
Inline: True
Inline callers:
  - mm/mlock.c:user_shm_lock
  - mm/mlock.c:SyS_mlockall
  - mm/mlock.c:SyS_mlockall
  - mm/mlock.c:do_mlock
  - mm/mlock.c:do_mlock
```
```
In mm/mmap.c (ffffffff811e2fa3)
Location: include/linux/sched.h:3450
Inline: True
Inline callers:
  - mm/mmap.c:do_brk
  - mm/mmap.c:do_mmap
  - mm/mmap.c:SyS_brk
```
```
In mm/mremap.c (ffffffff811e55f2)
Location: include/linux/sched.h:3450
Inline: True
Inline callers:
  - mm/mremap.c:vma_to_resize
```
```
In fs/exec.c (ffffffff81239021)
Location: include/linux/sched.h:3450
Inline: True
Inline callers:
  - fs/exec.c:setup_arg_pages
```
```
In fs/select.c (ffffffff81249b6d)
Location: include/linux/sched.h:3450
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
```
```
In fs/attr.c (ffffffff81251a34)
Location: include/linux/sched.h:3450
Inline: True
```
```
In fs/file.c (ffffffff81253771)
Location: include/linux/sched.h:3450
Inline: True
Inline callers:
  - fs/file.c:f_dupfd
  - fs/file.c:f_dupfd
  - fs/file.c:SyS_dup2
  - fs/file.c:replace_fd
  - fs/file.c:get_unused_fd_flags
```
```
In fs/coredump.c (ffffffff8129a863)
Location: include/linux/sched.h:3450
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
```
```
In fs/proc/array.c (ffffffff812ae096)
Location: include/linux/sched.h:3450
Inline: True
Inline callers:
  - fs/proc/array.c:proc_pid_status
```
```
In ipc/shm.c (ffffffff8135fefa)
Location: include/linux/sched.h:3450
Inline: True
Inline callers:
  - ipc/shm.c:SyS_shmctl
```
```
In ipc/mqueue.c (ffffffff8136137f)
Location: include/linux/sched.h:3450
Inline: True
Inline callers:
  - ipc/mqueue.c:mqueue_get_inode
```
```
In security/selinux/hooks.c (ffffffff8137c345)
Location: include/linux/sched.h:3450
Inline: True
```
```
In net/unix/af_unix.c (ffffffff8182b607)
Location: include/linux/sched.h:3450
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_scm_to_skb
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mmap.c (ffffffff810730d2)
Location: include/linux/sched.h:3635
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:arch_pick_mmap_layout
  - arch/x86/mm/mmap.c:arch_pick_mmap_layout
```
```
In kernel/fork.c (ffffffff81084ebe)
Location: include/linux/sched.h:3635
Inline: True
```
```
In kernel/signal.c (ffffffff81094ee5)
Location: include/linux/sched.h:3635
Inline: True
Inline callers:
  - kernel/signal.c:__sigqueue_alloc
```
```
In kernel/sys.c (ffffffff8109b062)
Location: include/linux/sched.h:3635
Inline: True
```
```
In kernel/sched/core.c (ffffffff810b2c2b)
Location: include/linux/sched.h:3635
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:SyS_nice
```
```
In kernel/sched/rt.c (ffffffff810c9c87)
Location: include/linux/sched.h:3635
Inline: True
Inline callers:
  - kernel/sched/rt.c:task_tick_rt
```
```
In kernel/bpf/syscall.c (ffffffff8118dccb)
Location: include/linux/sched.h:3635
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:__bpf_prog_charge
  - kernel/bpf/syscall.c:bpf_map_precharge_memlock
```
```
In kernel/events/core.c (ffffffff811a2a01)
Location: include/linux/sched.h:3635
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
```
```
In mm/filemap.c (ffffffff811b2830)
Location: include/linux/sched.h:3635
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_write_iter
```
```
In mm/mlock.c (ffffffff811efb37)
Location: include/linux/sched.h:3635
Inline: True
Inline callers:
  - mm/mlock.c:user_shm_lock
  - mm/mlock.c:SyS_mlockall
  - mm/mlock.c:SyS_mlockall
  - mm/mlock.c:do_mlock
  - mm/mlock.c:do_mlock
```
```
In mm/mmap.c (ffffffff811f2f83)
Location: include/linux/sched.h:3635
Inline: True
Inline callers:
  - mm/mmap.c:do_brk
  - mm/mmap.c:do_mmap
  - mm/mmap.c:SyS_brk
```
```
In mm/mremap.c (ffffffff811f5812)
Location: include/linux/sched.h:3635
Inline: True
Inline callers:
  - mm/mremap.c:vma_to_resize
```
```
In fs/exec.c (ffffffff8124bcd1)
Location: include/linux/sched.h:3635
Inline: True
Inline callers:
  - fs/exec.c:setup_arg_pages
```
```
In fs/select.c (ffffffff8125cb3d)
Location: include/linux/sched.h:3635
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
```
```
In fs/attr.c (ffffffff81264c04)
Location: include/linux/sched.h:3635
Inline: True
```
```
In fs/file.c (ffffffff812669c1)
Location: include/linux/sched.h:3635
Inline: True
Inline callers:
  - fs/file.c:f_dupfd
  - fs/file.c:f_dupfd
  - fs/file.c:SyS_dup2
  - fs/file.c:replace_fd
  - fs/file.c:get_unused_fd_flags
```
```
In fs/coredump.c (ffffffff812af3f3)
Location: include/linux/sched.h:3635
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
```
```
In fs/proc/array.c (ffffffff812c3a21)
Location: include/linux/sched.h:3635
Inline: True
Inline callers:
  - fs/proc/array.c:proc_pid_status
```
```
In ipc/shm.c (ffffffff813766fa)
Location: include/linux/sched.h:3635
Inline: True
Inline callers:
  - ipc/shm.c:SyS_shmctl
```
```
In ipc/mqueue.c (ffffffff81377b7a)
Location: include/linux/sched.h:3635
Inline: True
Inline callers:
  - ipc/mqueue.c:mqueue_get_inode
```
```
In security/selinux/hooks.c (ffffffff81392e01)
Location: include/linux/sched.h:3635
Inline: True
```
```
In net/unix/af_unix.c (ffffffff8185d027)
Location: include/linux/sched.h:3635
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_scm_to_skb
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mmap.c (ffffffff81072581)
Location: include/linux/sched/signal.h:590
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:arch_pick_mmap_base
```
```
In kernel/fork.c (ffffffff81081db1)
Location: include/linux/sched/signal.h:590
Inline: True
```
```
In kernel/signal.c (ffffffff81091f75)
Location: include/linux/sched/signal.h:590
Inline: True
Inline callers:
  - kernel/signal.c:__sigqueue_alloc
```
```
In kernel/sys.c (ffffffff81097e62)
Location: include/linux/sched/signal.h:590
Inline: True
```
```
In kernel/sched/core.c (ffffffff810aea90)
Location: include/linux/sched/signal.h:590
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:SyS_nice
```
```
In kernel/sched/rt.c (ffffffff810c4997)
Location: include/linux/sched/signal.h:590
Inline: True
Inline callers:
  - kernel/sched/rt.c:task_tick_rt
```
```
In kernel/bpf/syscall.c (ffffffff81192ab2)
Location: include/linux/sched/signal.h:590
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:__bpf_prog_charge
  - kernel/bpf/syscall.c:bpf_map_precharge_memlock
```
```
In kernel/events/core.c (ffffffff811aa06e)
Location: include/linux/sched/signal.h:590
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
```
```
In mm/filemap.c (ffffffff811b94a0)
Location: include/linux/sched/signal.h:590
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_write_iter
```
```
In mm/mlock.c (ffffffff811faa57)
Location: include/linux/sched/signal.h:590
Inline: True
Inline callers:
  - mm/mlock.c:user_shm_lock
  - mm/mlock.c:SyS_mlockall
  - mm/mlock.c:SyS_mlockall
  - mm/mlock.c:do_mlock
  - mm/mlock.c:do_mlock
```
```
In mm/mmap.c (ffffffff811fdec7)
Location: include/linux/sched/signal.h:590
Inline: True
Inline callers:
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:do_mmap
  - mm/mmap.c:SyS_brk
```
```
In mm/mremap.c (ffffffff812005fb)
Location: include/linux/sched/signal.h:590
Inline: True
Inline callers:
  - mm/mremap.c:vma_to_resize
```
```
In fs/exec.c (ffffffff81257dee)
Location: include/linux/sched/signal.h:590
Inline: True
Inline callers:
  - fs/exec.c:setup_arg_pages
```
```
In fs/select.c (ffffffff81269700)
Location: include/linux/sched/signal.h:590
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
```
```
In fs/attr.c (ffffffff81272434)
Location: include/linux/sched/signal.h:590
Inline: True
```
```
In fs/file.c (ffffffff812741bc)
Location: include/linux/sched/signal.h:590
Inline: True
Inline callers:
  - fs/file.c:f_dupfd
  - fs/file.c:f_dupfd
  - fs/file.c:SyS_dup2
  - fs/file.c:replace_fd
  - fs/file.c:get_unused_fd_flags
```
```
In fs/coredump.c (ffffffff812bc80b)
Location: include/linux/sched/signal.h:590
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
```
```
In fs/proc/array.c (ffffffff812d0ca9)
Location: include/linux/sched/signal.h:590
Inline: True
Inline callers:
  - fs/proc/array.c:proc_pid_status
```
```
In ipc/shm.c (ffffffff8138a2fa)
Location: include/linux/sched/signal.h:590
Inline: True
Inline callers:
  - ipc/shm.c:SyS_shmctl
```
```
In ipc/mqueue.c (ffffffff8138b705)
Location: include/linux/sched/signal.h:590
Inline: True
Inline callers:
  - ipc/mqueue.c:mqueue_get_inode
```
```
In security/selinux/hooks.c (ffffffff813a8fdd)
Location: include/linux/sched/signal.h:590
Inline: True
```
```
In net/unix/af_unix.c (ffffffff81881841)
Location: include/linux/sched/signal.h:590
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_scm_to_skb
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mmap.c (ffffffff81077e01)
Location: include/linux/sched/signal.h:591
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:arch_pick_mmap_base
```
```
In kernel/fork.c (ffffffff81088667)
Location: include/linux/sched/signal.h:591
Inline: True
```
```
In kernel/signal.c (ffffffff81098e05)
Location: include/linux/sched/signal.h:591
Inline: True
Inline callers:
  - kernel/signal.c:__sigqueue_alloc
```
```
In kernel/sys.c (ffffffff8109eb52)
Location: include/linux/sched/signal.h:591
Inline: True
```
```
In kernel/sched/core.c (ffffffff810b5ce1)
Location: include/linux/sched/signal.h:591
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:SyS_nice
```
```
In kernel/sched/rt.c (ffffffff810cc047)
Location: include/linux/sched/signal.h:591
Inline: True
Inline callers:
  - kernel/sched/rt.c:task_tick_rt
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811159b5)
Location: include/linux/sched/signal.h:591
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
```
```
In kernel/bpf/syscall.c (ffffffff811a0d6e)
Location: include/linux/sched/signal.h:591
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:__bpf_prog_charge
  - kernel/bpf/syscall.c:bpf_map_precharge_memlock
```
```
In kernel/events/core.c (ffffffff811bd961)
Location: include/linux/sched/signal.h:591
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
```
```
In mm/filemap.c (ffffffff811cf920)
Location: include/linux/sched/signal.h:591
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_write_iter
```
```
In mm/mlock.c (ffffffff81212f67)
Location: include/linux/sched/signal.h:591
Inline: True
Inline callers:
  - mm/mlock.c:user_shm_lock
  - mm/mlock.c:SyS_mlockall
  - mm/mlock.c:SyS_mlockall
  - mm/mlock.c:do_mlock
  - mm/mlock.c:do_mlock
```
```
In mm/mmap.c (ffffffff81216477)
Location: include/linux/sched/signal.h:591
Inline: True
Inline callers:
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:do_mmap
  - mm/mmap.c:SyS_brk
```
```
In mm/mremap.c (ffffffff81218dd1)
Location: include/linux/sched/signal.h:591
Inline: True
Inline callers:
  - mm/mremap.c:vma_to_resize
```
```
In fs/exec.c (ffffffff8127a0be)
Location: include/linux/sched/signal.h:591
Inline: True
Inline callers:
  - fs/exec.c:setup_arg_pages
```
```
In fs/select.c (ffffffff8128bfb0)
Location: include/linux/sched/signal.h:591
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
```
```
In fs/attr.c (ffffffff81294d55)
Location: include/linux/sched/signal.h:591
Inline: True
```
```
In fs/file.c (ffffffff81296abc)
Location: include/linux/sched/signal.h:591
Inline: True
Inline callers:
  - fs/file.c:f_dupfd
  - fs/file.c:f_dupfd
  - fs/file.c:SyS_dup2
  - fs/file.c:replace_fd
  - fs/file.c:get_unused_fd_flags
```
```
In fs/coredump.c (ffffffff812e010d)
Location: include/linux/sched/signal.h:591
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
```
```
In fs/proc/array.c (ffffffff812f5502)
Location: include/linux/sched/signal.h:591
Inline: True
Inline callers:
  - fs/proc/array.c:proc_pid_status
```
```
In ipc/shm.c (ffffffff813ae4b3)
Location: include/linux/sched/signal.h:591
Inline: True
Inline callers:
  - ipc/shm.c:shmctl_do_lock
```
```
In ipc/mqueue.c (ffffffff813b0a95)
Location: include/linux/sched/signal.h:591
Inline: True
Inline callers:
  - ipc/mqueue.c:mqueue_get_inode
```
```
In security/selinux/hooks.c (ffffffff813cef14)
Location: include/linux/sched/signal.h:591
Inline: True
```
```
In net/core/skbuff.c (ffffffff81831163)
Location: include/linux/sched/signal.h:591
Inline: True
```
```
In net/unix/af_unix.c (ffffffff819029dd)
Location: include/linux/sched/signal.h:591
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_scm_to_skb
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
In kernel/fork.c (ffffffff8108c3d7)
Location: include/linux/sched/signal.h:619
Inline: True
```
```
In kernel/signal.c (ffffffff8109c600)
Location: include/linux/sched/signal.h:619
Inline: True
Inline callers:
  - kernel/signal.c:__sigqueue_alloc
```
```
In kernel/sys.c (ffffffff810a4440)
Location: include/linux/sched/signal.h:619
Inline: True
```
```
In kernel/sched/core.c (ffffffff810bd986)
Location: include/linux/sched/signal.h:619
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__ia32_sys_nice
  - kernel/sched/core.c:__x64_sys_nice
```
```
In kernel/sched/rt.c (ffffffff810d36d7)
Location: include/linux/sched/signal.h:619
Inline: True
Inline callers:
  - kernel/sched/rt.c:task_tick_rt
```
```
In kernel/time/posix-cpu-timers.c (ffffffff81122186)
Location: include/linux/sched/signal.h:619
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
```
```
In kernel/bpf/syscall.c (ffffffff811b5a7f)
Location: include/linux/sched/signal.h:619
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_prog_charge
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:bpf_map_precharge_memlock
```
```
In kernel/events/core.c (ffffffff811ddbd3)
Location: include/linux/sched/signal.h:619
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
```
```
In mm/filemap.c (ffffffff811f0a4b)
Location: include/linux/sched/signal.h:619
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_write_iter
```
```
In mm/mlock.c (ffffffff81233f13)
Location: include/linux/sched/signal.h:619
Inline: True
Inline callers:
  - mm/mlock.c:user_shm_lock
  - mm/mlock.c:__ia32_sys_mlockall
  - mm/mlock.c:__ia32_sys_mlockall
  - mm/mlock.c:__x64_sys_mlockall
  - mm/mlock.c:__x64_sys_mlockall
  - mm/mlock.c:do_mlock
  - mm/mlock.c:do_mlock
```
```
In mm/mmap.c (ffffffff8123723e)
Location: include/linux/sched/signal.h:619
Inline: True
Inline callers:
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:do_mmap
  - mm/mmap.c:__ia32_sys_brk
  - mm/mmap.c:__x64_sys_brk
```
```
In mm/mremap.c (ffffffff8123a735)
Location: include/linux/sched/signal.h:619
Inline: True
Inline callers:
  - mm/mremap.c:vma_to_resize
```
```
In fs/exec.c (ffffffff812a2967)
Location: include/linux/sched/signal.h:619
Inline: True
```
```
In fs/select.c (ffffffff812b279b)
Location: include/linux/sched/signal.h:619
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
```
```
In fs/attr.c (ffffffff812baf15)
Location: include/linux/sched/signal.h:619
Inline: True
```
```
In fs/file.c (ffffffff812bcc58)
Location: include/linux/sched/signal.h:619
Inline: True
Inline callers:
  - fs/file.c:f_dupfd
  - fs/file.c:f_dupfd
  - fs/file.c:ksys_dup3
  - fs/file.c:replace_fd
  - fs/file.c:get_unused_fd_flags
```
```
In fs/coredump.c (ffffffff8130c33e)
Location: include/linux/sched/signal.h:619
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
```
```
In fs/proc/array.c (ffffffff8132288d)
Location: include/linux/sched/signal.h:619
Inline: True
Inline callers:
  - fs/proc/array.c:proc_pid_status
```
```
In ipc/shm.c (ffffffff813dea26)
Location: include/linux/sched/signal.h:619
Inline: True
Inline callers:
  - ipc/shm.c:shmctl_do_lock
```
```
In ipc/mqueue.c (ffffffff813e3163)
Location: include/linux/sched/signal.h:619
Inline: True
Inline callers:
  - ipc/mqueue.c:mqueue_get_inode
```
```
In security/selinux/hooks.c (ffffffff81402547)
Location: include/linux/sched/signal.h:619
Inline: True
```
```
In net/core/skbuff.c (ffffffff8187b60d)
Location: include/linux/sched/signal.h:619
Inline: True
```
```
In net/unix/af_unix.c (ffffffff81958e4d)
Location: include/linux/sched/signal.h:619
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_scm_to_skb
```
```
In net/xdp/xdp_umem.c (ffffffff819cd109)
Location: include/linux/sched/signal.h:619
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_create
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
In kernel/fork.c (ffffffff81093e0b)
Location: include/linux/sched/signal.h:661
Inline: True
```
```
In kernel/signal.c (ffffffff810a4868)
Location: include/linux/sched/signal.h:661
Inline: True
Inline callers:
  - kernel/signal.c:__sigqueue_alloc
```
```
In kernel/sys.c (ffffffff810ad2a0)
Location: include/linux/sched/signal.h:661
Inline: True
```
```
In kernel/sched/core.c (ffffffff810c6b4d)
Location: include/linux/sched/signal.h:661
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__ia32_sys_nice
  - kernel/sched/core.c:__x64_sys_nice
```
```
In kernel/sched/rt.c (ffffffff810dca8b)
Location: include/linux/sched/signal.h:661
Inline: True
Inline callers:
  - kernel/sched/rt.c:task_tick_rt
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8112d8a4)
Location: include/linux/sched/signal.h:661
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
```
```
In kernel/bpf/syscall.c (ffffffff811c369f)
Location: include/linux/sched/signal.h:661
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_prog_charge
  - kernel/bpf/syscall.c:bpf_charge_memlock
  - kernel/bpf/syscall.c:bpf_map_precharge_memlock
```
```
In kernel/events/core.c (ffffffff811edfd3)
Location: include/linux/sched/signal.h:661
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
```
```
In mm/filemap.c (ffffffff811fc58f)
Location: include/linux/sched/signal.h:661
Inline: True
```
```
In mm/mlock.c (ffffffff812476c3)
Location: include/linux/sched/signal.h:661
Inline: True
Inline callers:
  - mm/mlock.c:user_shm_lock
  - mm/mlock.c:__ia32_sys_mlockall
  - mm/mlock.c:__ia32_sys_mlockall
  - mm/mlock.c:__x64_sys_mlockall
  - mm/mlock.c:__x64_sys_mlockall
  - mm/mlock.c:do_mlock
  - mm/mlock.c:do_mlock
```
```
In mm/mmap.c (ffffffff8124aaf5)
Location: include/linux/sched/signal.h:661
Inline: True
Inline callers:
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:do_mmap
  - mm/mmap.c:__ia32_sys_brk
  - mm/mmap.c:__x64_sys_brk
```
```
In mm/mremap.c (ffffffff8124e8a5)
Location: include/linux/sched/signal.h:661
Inline: True
Inline callers:
  - mm/mremap.c:vma_to_resize
```
```
In fs/exec.c (ffffffff812b77d6)
Location: include/linux/sched/signal.h:661
Inline: True
```
```
In fs/select.c (ffffffff812c78ab)
Location: include/linux/sched/signal.h:661
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
```
```
In fs/attr.c (ffffffff812d0105)
Location: include/linux/sched/signal.h:661
Inline: True
```
```
In fs/file.c (ffffffff812d1f18)
Location: include/linux/sched/signal.h:661
Inline: True
Inline callers:
  - fs/file.c:f_dupfd
  - fs/file.c:f_dupfd
  - fs/file.c:ksys_dup3
  - fs/file.c:replace_fd
  - fs/file.c:get_unused_fd_flags
```
```
In fs/coredump.c (ffffffff81321b9e)
Location: include/linux/sched/signal.h:661
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
```
```
In fs/proc/array.c (ffffffff813399c2)
Location: include/linux/sched/signal.h:661
Inline: True
Inline callers:
  - fs/proc/array.c:proc_pid_status
```
```
In ipc/shm.c (ffffffff813f9126)
Location: include/linux/sched/signal.h:661
Inline: True
Inline callers:
  - ipc/shm.c:shmctl_do_lock
```
```
In ipc/mqueue.c (ffffffff813fd943)
Location: include/linux/sched/signal.h:661
Inline: True
Inline callers:
  - ipc/mqueue.c:mqueue_get_inode
```
```
In security/selinux/hooks.c (ffffffff8141adc2)
Location: include/linux/sched/signal.h:661
Inline: True
```
```
In net/core/skbuff.c (ffffffff8189c44d)
Location: include/linux/sched/signal.h:661
Inline: True
```
```
In net/unix/af_unix.c (ffffffff8198da0d)
Location: include/linux/sched/signal.h:661
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_scm_to_skb
```
```
In net/xdp/xdp_umem.c (ffffffff81a06464)
Location: include/linux/sched/signal.h:661
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_create
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
In kernel/fork.c (ffffffff8109856a)
Location: include/linux/sched/signal.h:692
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/signal.c (ffffffff810a94ee)
Location: include/linux/sched/signal.h:692
Inline: True
Inline callers:
  - kernel/signal.c:__sigqueue_alloc
```
```
In kernel/sys.c (ffffffff810b2ae0)
Location: include/linux/sched/signal.h:692
Inline: True
```
```
In kernel/sched/core.c (ffffffff810ccfcf)
Location: include/linux/sched/signal.h:692
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__ia32_sys_nice
  - kernel/sched/core.c:__x64_sys_nice
```
```
In kernel/sched/rt.c (ffffffff810e3a33)
Location: include/linux/sched/signal.h:692
Inline: True
Inline callers:
  - kernel/sched/rt.c:task_tick_rt
```
```
In kernel/time/posix-cpu-timers.c (ffffffff81138292)
Location: include/linux/sched/signal.h:692
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
```
```
In kernel/bpf/syscall.c (ffffffff811d4def)
Location: include/linux/sched/signal.h:692
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_prog_charge
  - kernel/bpf/syscall.c:bpf_charge_memlock
```
```
In kernel/events/core.c (ffffffff81205a01)
Location: include/linux/sched/signal.h:692
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
```
```
In mm/filemap.c (ffffffff81213cf7)
Location: include/linux/sched/signal.h:692
Inline: True
```
```
In mm/util.c (ffffffff81236f49)
Location: include/linux/sched/signal.h:692
Inline: True
Inline callers:
  - mm/util.c:__account_locked_vm
  - mm/util.c:__account_locked_vm
```
```
In mm/mlock.c (ffffffff812598d3)
Location: include/linux/sched/signal.h:692
Inline: True
Inline callers:
  - mm/mlock.c:user_shm_lock
  - mm/mlock.c:__ia32_sys_mlockall
  - mm/mlock.c:__ia32_sys_mlockall
  - mm/mlock.c:__x64_sys_mlockall
  - mm/mlock.c:__x64_sys_mlockall
  - mm/mlock.c:do_mlock
  - mm/mlock.c:do_mlock
```
```
In mm/mmap.c (ffffffff8125ce64)
Location: include/linux/sched/signal.h:692
Inline: True
Inline callers:
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:do_mmap
  - mm/mmap.c:__ia32_sys_brk
  - mm/mmap.c:__x64_sys_brk
```
```
In mm/mremap.c (ffffffff81260bef)
Location: include/linux/sched/signal.h:692
Inline: True
Inline callers:
  - mm/mremap.c:vma_to_resize
```
```
In fs/exec.c (ffffffff812d3e57)
Location: include/linux/sched/signal.h:692
Inline: True
```
```
In fs/select.c (ffffffff812e443b)
Location: include/linux/sched/signal.h:692
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
```
```
In fs/attr.c (ffffffff812ed124)
Location: include/linux/sched/signal.h:692
Inline: True
```
```
In fs/file.c (ffffffff812eef5c)
Location: include/linux/sched/signal.h:692
Inline: True
Inline callers:
  - fs/file.c:f_dupfd
  - fs/file.c:f_dupfd
  - fs/file.c:ksys_dup3
  - fs/file.c:replace_fd
  - fs/file.c:get_unused_fd_flags
```
```
In fs/io_uring.c (ffffffff81331fe9)
Location: include/linux/sched/signal.h:692
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_sqe_buffer_register
```
```
In fs/coredump.c (ffffffff813499d4)
Location: include/linux/sched/signal.h:692
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/array.c (ffffffff81361b90)
Location: include/linux/sched/signal.h:692
Inline: True
Inline callers:
  - fs/proc/array.c:proc_pid_status
```
```
In ipc/shm.c (ffffffff814256a6)
Location: include/linux/sched/signal.h:692
Inline: True
Inline callers:
  - ipc/shm.c:shmctl_do_lock
```
```
In ipc/mqueue.c (ffffffff81429f96)
Location: include/linux/sched/signal.h:692
Inline: True
Inline callers:
  - ipc/mqueue.c:mqueue_get_inode
```
```
In security/selinux/hooks.c (ffffffff814488ab)
Location: include/linux/sched/signal.h:692
Inline: True
```
```
In net/core/skbuff.c (ffffffff818e6ccd)
Location: include/linux/sched/signal.h:692
Inline: True
```
```
In net/unix/scm.c (ffffffff819fdf4f)
Location: include/linux/sched/signal.h:692
Inline: True
Inline callers:
  - net/unix/scm.c:unix_attach_fds
```
```
In net/xdp/xdp_umem.c (ffffffff81a75d91)
Location: include/linux/sched/signal.h:692
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_create
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
In kernel/fork.c (ffffffff8109eb54)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/signal.c (ffffffff810afabc)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - kernel/signal.c:__sigqueue_alloc
```
```
In kernel/sys.c (ffffffff810b90d0)
Location: include/linux/sched/signal.h:684
Inline: True
```
```
In kernel/sched/core.c (ffffffff810d68b9)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__ia32_sys_nice
  - kernel/sched/core.c:__x64_sys_nice
```
```
In kernel/sched/rt.c (ffffffff810ef573)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - kernel/sched/rt.c:task_tick_rt
```
```
In kernel/time/posix-cpu-timers.c (ffffffff81144226)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
```
```
In kernel/bpf/syscall.c (ffffffff811e14ff)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_prog_charge
  - kernel/bpf/syscall.c:bpf_charge_memlock
```
```
In kernel/events/core.c (ffffffff81212d95)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
```
```
In mm/filemap.c (ffffffff812214f7)
Location: include/linux/sched/signal.h:684
Inline: True
```
```
In mm/util.c (ffffffff81245119)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - mm/util.c:__account_locked_vm
  - mm/util.c:__account_locked_vm
```
```
In mm/mlock.c (ffffffff81267da3)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - mm/mlock.c:user_shm_lock
  - mm/mlock.c:__ia32_sys_mlockall
  - mm/mlock.c:__ia32_sys_mlockall
  - mm/mlock.c:__x64_sys_mlockall
  - mm/mlock.c:__x64_sys_mlockall
  - mm/mlock.c:do_mlock
  - mm/mlock.c:do_mlock
```
```
In mm/mmap.c (ffffffff8126b634)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:do_mmap
  - mm/mmap.c:__ia32_sys_brk
  - mm/mmap.c:__x64_sys_brk
```
```
In mm/mremap.c (ffffffff8126f37f)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - mm/mremap.c:vma_to_resize
```
```
In fs/exec.c (ffffffff812e59e7)
Location: include/linux/sched/signal.h:684
Inline: True
```
```
In fs/select.c (ffffffff812f5e7b)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
```
```
In fs/attr.c (ffffffff812feb84)
Location: include/linux/sched/signal.h:684
Inline: True
```
```
In fs/file.c (ffffffff81300a1c)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - fs/file.c:f_dupfd
  - fs/file.c:f_dupfd
  - fs/file.c:ksys_dup3
  - fs/file.c:replace_fd
  - fs/file.c:get_unused_fd_flags
```
```
In fs/io_uring.c (ffffffff81345ba9)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_sqe_buffer_register
```
```
In fs/coredump.c (ffffffff81361c74)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/array.c (ffffffff81379df0)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - fs/proc/array.c:proc_pid_status
```
```
In ipc/shm.c (ffffffff8143f3f6)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - ipc/shm.c:shmctl_do_lock
```
```
In ipc/mqueue.c (ffffffff81443cc6)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - ipc/mqueue.c:mqueue_get_inode
```
```
In security/selinux/hooks.c (ffffffff8146243b)
Location: include/linux/sched/signal.h:684
Inline: True
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff817d517e)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_map
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages
```
```
In net/core/skbuff.c (ffffffff819190ad)
Location: include/linux/sched/signal.h:684
Inline: True
```
```
In net/unix/scm.c (ffffffff81a34b3f)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - net/unix/scm.c:unix_attach_fds
```
```
In net/xdp/xdp_umem.c (ffffffff81aacaf4)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_create
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
In kernel/fork.c (ffffffff810a605f)
Location: include/linux/sched/signal.h:696
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/signal.c (ffffffff810b7910)
Location: include/linux/sched/signal.h:696
Inline: True
Inline callers:
  - kernel/signal.c:__sigqueue_alloc
```
```
In kernel/sys.c (ffffffff810c0e58)
Location: include/linux/sched/signal.h:696
Inline: True
Inline callers:
  - kernel/sys.c:validate_prctl_map_addr
  - kernel/sys.c:set_user
```
```
In kernel/sched/core.c (ffffffff810e0fba)
Location: include/linux/sched/signal.h:696
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__ia32_sys_nice
  - kernel/sched/core.c:__x64_sys_nice
```
```
In kernel/sched/rt.c (ffffffff810f8e71)
Location: include/linux/sched/signal.h:696
Inline: True
Inline callers:
  - kernel/sched/rt.c:task_tick_rt
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8115357d)
Location: include/linux/sched/signal.h:696
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:check_process_timers
  - kernel/time/posix-cpu-timers.c:check_thread_timers
```
```
In kernel/bpf/syscall.c (ffffffff811ffc5f)
Location: include/linux/sched/signal.h:696
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_prog_charge
  - kernel/bpf/syscall.c:bpf_map_charge_memlock
```
```
In kernel/events/core.c (ffffffff8123ee09)
Location: include/linux/sched/signal.h:696
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
```
```
In kernel/watch_queue.c (ffffffff8124c839)
Location: include/linux/sched/signal.h:696
Inline: True
Inline callers:
  - kernel/watch_queue.c:add_watch_to_object
```
```
In mm/filemap.c (ffffffff8124e18e)
Location: include/linux/sched/signal.h:696
Inline: True
Inline callers:
  - mm/filemap.c:generic_write_check_limits
```
```
In mm/util.c (ffffffff81272d29)
Location: include/linux/sched/signal.h:696
Inline: True
Inline callers:
  - mm/util.c:__account_locked_vm
  - mm/util.c:__account_locked_vm
```
```
In mm/mlock.c (ffffffff81297db3)
Location: include/linux/sched/signal.h:696
Inline: True
Inline callers:
  - mm/mlock.c:user_shm_lock
  - mm/mlock.c:__do_sys_mlockall
  - mm/mlock.c:__do_sys_mlockall
  - mm/mlock.c:do_mlock
  - mm/mlock.c:do_mlock
```
```
In mm/mmap.c (ffffffff8129b5e9)
Location: include/linux/sched/signal.h:696
Inline: True
Inline callers:
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
  - mm/mmap.c:do_mmap
  - mm/mmap.c:__do_sys_brk
```
```
In mm/mremap.c (ffffffff8129f924)
Location: include/linux/sched/signal.h:696
Inline: True
Inline callers:
  - mm/mremap.c:vma_to_resize
```
```
In fs/exec.c (ffffffff8131d4d5)
Location: include/linux/sched/signal.h:696
Inline: True
Inline callers:
  - fs/exec.c:__do_execve_file
```
```
In fs/select.c (ffffffff8132ef92)
Location: include/linux/sched/signal.h:696
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
```
```
In fs/attr.c (ffffffff81337c84)
Location: include/linux/sched/signal.h:696
Inline: True
```
```
In fs/file.c (ffffffff81339c5c)
Location: include/linux/sched/signal.h:696
Inline: True
Inline callers:
  - fs/file.c:f_dupfd
  - fs/file.c:f_dupfd
  - fs/file.c:ksys_dup
  - fs/file.c:ksys_dup3
  - fs/file.c:replace_fd
```
```
In fs/io_uring.c (ffffffff813857ed)
Location: include/linux/sched/signal.h:696
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_issue_sqe
  - fs/io_uring.c:io_accept_prep
  - fs/io_uring.c:__io_openat_prep
```
```
In fs/io-wq.c (ffffffff8138b51c)
Location: include/linux/sched/signal.h:696
Inline: True
Inline callers:
  - fs/io-wq.c:io_wq_create
```
```
In fs/coredump.c (ffffffff813a7f03)
Location: include/linux/sched/signal.h:696
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
  - fs/coredump.c:format_corename
```
```
In fs/proc/array.c (ffffffff813c2eb0)
Location: include/linux/sched/signal.h:696
Inline: True
Inline callers:
  - fs/proc/array.c:proc_pid_status
```
```
In ipc/shm.c (ffffffff8148ff66)
Location: include/linux/sched/signal.h:696
Inline: True
Inline callers:
  - ipc/shm.c:shmctl_do_lock
```
```
In ipc/mqueue.c (ffffffff8149499a)
Location: include/linux/sched/signal.h:696
Inline: True
Inline callers:
  - ipc/mqueue.c:mqueue_get_inode
```
```
In security/selinux/hooks.c (ffffffff814b637b)
Location: include/linux/sched/signal.h:696
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committing_creds
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff8189fe5a)
Location: include/linux/sched/signal.h:696
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_replay
  - drivers/vfio/vfio_iommu_type1.c:vfio_pin_map_dma
  - drivers/vfio/vfio_iommu_type1.c:vfio_pin_page_external
```
```
In net/socket.c (ffffffff819e1274)
Location: include/linux/sched/signal.h:696
Inline: True
Inline callers:
  - net/socket.c:__sys_accept4
```
```
In net/core/skbuff.c (ffffffff819ecd11)
Location: include/linux/sched/signal.h:696
Inline: True
```
```
In net/unix/scm.c (ffffffff81b2997f)
Location: include/linux/sched/signal.h:696
Inline: True
Inline callers:
  - net/unix/scm.c:unix_attach_fds
```
```
In net/xdp/xdp_umem.c (ffffffff81ba8528)
Location: include/linux/sched/signal.h:696
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_reg
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
In kernel/fork.c (ffffffff810a1a4c)
Location: include/linux/sched/signal.h:711
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/signal.c (ffffffff810b2bac)
Location: include/linux/sched/signal.h:711
Inline: True
Inline callers:
  - kernel/signal.c:__sigqueue_alloc
```
```
In kernel/sys.c (ffffffff810bbfb8)
Location: include/linux/sched/signal.h:711
Inline: True
Inline callers:
  - kernel/sys.c:validate_prctl_map_addr
  - kernel/sys.c:set_user
```
```
In kernel/sched/core.c (ffffffff810de3e7)
Location: include/linux/sched/signal.h:711
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__ia32_sys_nice
  - kernel/sched/core.c:__x64_sys_nice
```
```
In kernel/sched/rt.c (ffffffff810f7061)
Location: include/linux/sched/signal.h:711
Inline: True
Inline callers:
  - kernel/sched/rt.c:task_tick_rt
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8114f83d)
Location: include/linux/sched/signal.h:711
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:check_process_timers
  - kernel/time/posix-cpu-timers.c:check_thread_timers
```
```
In kernel/events/core.c (ffffffff812491f9)
Location: include/linux/sched/signal.h:711
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
```
```
In kernel/watch_queue.c (ffffffff81256c79)
Location: include/linux/sched/signal.h:711
Inline: True
Inline callers:
  - kernel/watch_queue.c:add_watch_to_object
```
```
In mm/util.c (ffffffff8127d409)
Location: include/linux/sched/signal.h:711
Inline: True
Inline callers:
  - mm/util.c:__account_locked_vm
  - mm/util.c:__account_locked_vm
```
```
In mm/mlock.c (ffffffff812a2f03)
Location: include/linux/sched/signal.h:711
Inline: True
Inline callers:
  - mm/mlock.c:user_shm_lock
  - mm/mlock.c:__do_sys_mlockall
  - mm/mlock.c:__do_sys_mlockall
  - mm/mlock.c:do_mlock
  - mm/mlock.c:do_mlock
```
```
In mm/mmap.c (ffffffff812a678e)
Location: include/linux/sched/signal.h:711
Inline: True
Inline callers:
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
  - mm/mmap.c:do_mmap
  - mm/mmap.c:__do_sys_brk
```
```
In mm/mremap.c (ffffffff812aad94)
Location: include/linux/sched/signal.h:711
Inline: True
Inline callers:
  - mm/mremap.c:vma_to_resize
```
```
In fs/read_write.c (ffffffff813205ae)
Location: include/linux/sched/signal.h:711
Inline: True
Inline callers:
  - fs/read_write.c:generic_write_check_limits
```
```
In fs/exec.c (ffffffff81328c5b)
Location: include/linux/sched/signal.h:711
Inline: True
Inline callers:
  - fs/exec.c:do_execveat_common
```
```
In fs/select.c (ffffffff8133a872)
Location: include/linux/sched/signal.h:711
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
```
```
In fs/attr.c (ffffffff813435e4)
Location: include/linux/sched/signal.h:711
Inline: True
```
```
In fs/file.c (ffffffff813459af)
Location: include/linux/sched/signal.h:711
Inline: True
Inline callers:
  - fs/file.c:f_dupfd
  - fs/file.c:__ia32_sys_dup
  - fs/file.c:__x64_sys_dup
  - fs/file.c:ksys_dup3
  - fs/file.c:__receive_fd
  - fs/file.c:replace_fd
```
```
In fs/io_uring.c (ffffffff81396821)
Location: include/linux/sched/signal.h:711
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_buffer_account_pin
  - fs/io_uring.c:io_req_prep
  - fs/io_uring.c:__io_openat_prep
  - fs/io_uring.c:io_grab_identity
  - fs/io_uring.c:io_init_identity
```
```
In fs/io-wq.c (ffffffff8139c702)
Location: include/linux/sched/signal.h:711
Inline: True
Inline callers:
  - fs/io-wq.c:io_wq_create
```
```
In fs/coredump.c (ffffffff813b8f83)
Location: include/linux/sched/signal.h:711
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
  - fs/coredump.c:format_corename
```
```
In fs/proc/array.c (ffffffff813d5045)
Location: include/linux/sched/signal.h:711
Inline: True
Inline callers:
  - fs/proc/array.c:proc_pid_status
```
```
In ipc/shm.c (ffffffff814ad680)
Location: include/linux/sched/signal.h:711
Inline: True
Inline callers:
  - ipc/shm.c:shmctl_do_lock
```
```
In ipc/mqueue.c (ffffffff814b22fa)
Location: include/linux/sched/signal.h:711
Inline: True
Inline callers:
  - ipc/mqueue.c:mqueue_get_inode
```
```
In security/selinux/hooks.c (ffffffff814d405b)
Location: include/linux/sched/signal.h:711
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committing_creds
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff818af7ea)
Location: include/linux/sched/signal.h:711
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_replay
  - drivers/vfio/vfio_iommu_type1.c:vfio_pin_map_dma
  - drivers/vfio/vfio_iommu_type1.c:vfio_pin_page_external
```
```
In net/socket.c (ffffffff819e0ac1)
Location: include/linux/sched/signal.h:711
Inline: True
Inline callers:
  - net/socket.c:__sys_accept4
```
```
In net/core/skbuff.c (ffffffff819ec9d1)
Location: include/linux/sched/signal.h:711
Inline: True
```
```
In net/unix/scm.c (ffffffff81b382af)
Location: include/linux/sched/signal.h:711
Inline: True
Inline callers:
  - net/unix/scm.c:unix_attach_fds
```
```
In net/xdp/xdp_umem.c (ffffffff81bb828c)
Location: include/linux/sched/signal.h:711
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_reg
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
In kernel/fork.c (ffffffff810a27e9)
Location: include/linux/sched/signal.h:717
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/signal.c (ffffffff810b41f0)
Location: include/linux/sched/signal.h:717
Inline: True
Inline callers:
  - kernel/signal.c:__sigqueue_alloc
```
```
In kernel/sys.c (ffffffff810bd85e)
Location: include/linux/sched/signal.h:717
Inline: True
Inline callers:
  - kernel/sys.c:validate_prctl_map_addr
  - kernel/sys.c:set_user
```
```
In kernel/sched/core.c (ffffffff810dffde)
Location: include/linux/sched/signal.h:717
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__ia32_sys_nice
  - kernel/sched/core.c:__x64_sys_nice
```
```
In kernel/sched/rt.c (ffffffff810f91b1)
Location: include/linux/sched/signal.h:717
Inline: True
Inline callers:
  - kernel/sched/rt.c:task_tick_rt
```
```
In kernel/time/posix-cpu-timers.c (ffffffff81150d17)
Location: include/linux/sched/signal.h:717
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timers_work
  - kernel/time/posix-cpu-timers.c:check_process_timers
```
```
In kernel/events/core.c (ffffffff8124d3c9)
Location: include/linux/sched/signal.h:717
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
```
```
In kernel/watch_queue.c (ffffffff8125b119)
Location: include/linux/sched/signal.h:717
Inline: True
Inline callers:
  - kernel/watch_queue.c:add_watch_to_object
```
```
In mm/util.c (ffffffff812825a0)
Location: include/linux/sched/signal.h:717
Inline: True
Inline callers:
  - mm/util.c:__account_locked_vm
  - mm/util.c:__account_locked_vm
```
```
In mm/mlock.c (ffffffff812a8763)
Location: include/linux/sched/signal.h:717
Inline: True
Inline callers:
  - mm/mlock.c:user_shm_lock
  - mm/mlock.c:__do_sys_mlockall
  - mm/mlock.c:__do_sys_mlockall
  - mm/mlock.c:do_mlock
  - mm/mlock.c:do_mlock
```
```
In mm/mmap.c (ffffffff812ac753)
Location: include/linux/sched/signal.h:717
Inline: True
Inline callers:
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:do_mmap
  - mm/mmap.c:__do_sys_brk
```
```
In mm/mremap.c (ffffffff812b01e5)
Location: include/linux/sched/signal.h:717
Inline: True
Inline callers:
  - mm/mremap.c:vma_to_resize
```
```
In fs/read_write.c (ffffffff813266e4)
Location: include/linux/sched/signal.h:717
Inline: True
Inline callers:
  - fs/read_write.c:generic_write_check_limits
```
```
In fs/exec.c (ffffffff8132eaa6)
Location: include/linux/sched/signal.h:717
Inline: True
```
```
In fs/select.c (ffffffff81340d76)
Location: include/linux/sched/signal.h:717
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
```
```
In fs/attr.c (ffffffff813498e4)
Location: include/linux/sched/signal.h:717
Inline: True
```
```
In fs/file.c (ffffffff8134bd6f)
Location: include/linux/sched/signal.h:717
Inline: True
Inline callers:
  - fs/file.c:f_dupfd
  - fs/file.c:__ia32_sys_dup
  - fs/file.c:__x64_sys_dup
  - fs/file.c:ksys_dup3
  - fs/file.c:__receive_fd
  - fs/file.c:replace_fd
```
```
In fs/io_uring.c (ffffffff81391826)
Location: include/linux/sched/signal.h:717
Inline: True
Inline callers:
  - fs/io_uring.c:io_buffer_account_pin
  - fs/io_uring.c:io_req_prep
  - fs/io_uring.c:__io_openat_prep
```
```
In fs/io-wq.c (ffffffff813a37b7)
Location: include/linux/sched/signal.h:717
Inline: True
Inline callers:
  - fs/io-wq.c:io_wq_create
```
```
In fs/coredump.c (ffffffff813bfee4)
Location: include/linux/sched/signal.h:717
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/array.c (ffffffff813dbe9c)
Location: include/linux/sched/signal.h:717
Inline: True
Inline callers:
  - fs/proc/array.c:proc_pid_status
```
```
In ipc/shm.c (ffffffff814b3500)
Location: include/linux/sched/signal.h:717
Inline: True
Inline callers:
  - ipc/shm.c:shmctl_do_lock
```
```
In ipc/mqueue.c (ffffffff814b816c)
Location: include/linux/sched/signal.h:717
Inline: True
Inline callers:
  - ipc/mqueue.c:mqueue_get_inode
```
```
In security/selinux/hooks.c (ffffffff814da607)
Location: include/linux/sched/signal.h:717
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committing_creds
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff818921db)
Location: include/linux/sched/signal.h:717
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_replay
  - drivers/vfio/vfio_iommu_type1.c:vfio_pin_map_dma
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages
```
```
In net/socket.c (ffffffff819c6b11)
Location: include/linux/sched/signal.h:717
Inline: True
Inline callers:
  - net/socket.c:__sys_accept4
```
```
In net/core/skbuff.c (ffffffff819d2eb1)
Location: include/linux/sched/signal.h:717
Inline: True
```
```
In net/unix/scm.c (ffffffff81b25f4f)
Location: include/linux/sched/signal.h:717
Inline: True
Inline callers:
  - net/unix/scm.c:unix_attach_fds
```
```
In net/xdp/xdp_umem.c (ffffffff81ba744e)
Location: include/linux/sched/signal.h:717
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_reg
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
In kernel/fork.c (ffffffff810b3ee6)
Location: include/linux/sched/signal.h:721
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/signal.c (ffffffff810c62c8)
Location: include/linux/sched/signal.h:721
Inline: True
Inline callers:
  - kernel/signal.c:__sigqueue_alloc
```
```
In kernel/sys.c (ffffffff810d026b)
Location: include/linux/sched/signal.h:721
Inline: True
Inline callers:
  - kernel/sys.c:validate_prctl_map_addr
  - kernel/sys.c:flag_nproc_exceeded
```
```
In kernel/sched/core.c (ffffffff810f5118)
Location: include/linux/sched/signal.h:721
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__ia32_sys_nice
  - kernel/sched/core.c:__x64_sys_nice
```
```
In kernel/sched/rt.c (ffffffff81114782)
Location: include/linux/sched/signal.h:721
Inline: True
Inline callers:
  - kernel/sched/rt.c:task_tick_rt
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811750e7)
Location: include/linux/sched/signal.h:721
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timers_work
  - kernel/time/posix-cpu-timers.c:check_process_timers
```
```
In kernel/acct.c (ffffffff8118c128)
Location: include/linux/sched/signal.h:721
Inline: True
Inline callers:
  - kernel/acct.c:do_acct_process
```
```
In kernel/user_namespace.c (ffffffff811aaa36)
Location: include/linux/sched/signal.h:721
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
  - kernel/user_namespace.c:create_user_ns
  - kernel/user_namespace.c:create_user_ns
  - kernel/user_namespace.c:create_user_ns
```
```
In kernel/events/core.c (ffffffff81286fd9)
Location: include/linux/sched/signal.h:721
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
```
```
In kernel/watch_queue.c (ffffffff81296f19)
Location: include/linux/sched/signal.h:721
Inline: True
Inline callers:
  - kernel/watch_queue.c:add_watch_to_object
```
```
In mm/util.c (ffffffff812c06b2)
Location: include/linux/sched/signal.h:721
Inline: True
Inline callers:
  - mm/util.c:__account_locked_vm
  - mm/util.c:__account_locked_vm
```
```
In mm/mlock.c (ffffffff812e9d6f)
Location: include/linux/sched/signal.h:721
Inline: True
Inline callers:
  - mm/mlock.c:user_shm_lock
  - mm/mlock.c:__do_sys_mlockall
  - mm/mlock.c:__do_sys_mlockall
  - mm/mlock.c:do_mlock
  - mm/mlock.c:do_mlock
```
```
In mm/mmap.c (ffffffff812edea3)
Location: include/linux/sched/signal.h:721
Inline: True
Inline callers:
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:do_mmap
  - mm/mmap.c:__do_sys_brk
```
```
In mm/mremap.c (ffffffff812f1a5f)
Location: include/linux/sched/signal.h:721
Inline: True
Inline callers:
  - mm/mremap.c:vma_to_resize
```
```
In fs/read_write.c (ffffffff81373c84)
Location: include/linux/sched/signal.h:721
Inline: True
Inline callers:
  - fs/read_write.c:generic_write_check_limits
```
```
In fs/exec.c (ffffffff8137c3c5)
Location: include/linux/sched/signal.h:721
Inline: True
```
```
In fs/select.c (ffffffff8138e736)
Location: include/linux/sched/signal.h:721
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
```
```
In fs/attr.c (ffffffff81397634)
Location: include/linux/sched/signal.h:721
Inline: True
```
```
In fs/file.c (ffffffff81399baf)
Location: include/linux/sched/signal.h:721
Inline: True
Inline callers:
  - fs/file.c:f_dupfd
  - fs/file.c:__ia32_sys_dup
  - fs/file.c:__x64_sys_dup
  - fs/file.c:ksys_dup3
  - fs/file.c:receive_fd
  - fs/file.c:replace_fd
```
```
In fs/io_uring.c (ffffffff813df72f)
Location: include/linux/sched/signal.h:721
Inline: True
Inline callers:
  - fs/io_uring.c:io_buffer_account_pin
  - fs/io_uring.c:io_sqe_files_register
  - fs/io_uring.c:io_req_prep
```
```
In fs/io-wq.c (ffffffff813f331f)
Location: include/linux/sched/signal.h:721
Inline: True
Inline callers:
  - fs/io-wq.c:io_wq_max_workers
  - fs/io-wq.c:io_wq_max_workers
  - fs/io-wq.c:io_wq_create
```
```
In fs/coredump.c (ffffffff8140fd14)
Location: include/linux/sched/signal.h:721
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/array.c (ffffffff8142d4df)
Location: include/linux/sched/signal.h:721
Inline: True
Inline callers:
  - fs/proc/array.c:proc_pid_status
```
```
In ipc/shm.c (ffffffff8150bb7e)
Location: include/linux/sched/signal.h:721
Inline: True
Inline callers:
  - ipc/shm.c:shmctl_do_lock
```
```
In ipc/mqueue.c (ffffffff815109a2)
Location: include/linux/sched/signal.h:721
Inline: True
Inline callers:
  - ipc/mqueue.c:mqueue_get_inode
```
```
In security/selinux/hooks.c (ffffffff81533507)
Location: include/linux/sched/signal.h:721
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committing_creds
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff8192669b)
Location: include/linux/sched/signal.h:721
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_replay
  - drivers/vfio/vfio_iommu_type1.c:vfio_pin_map_dma
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages
```
```
In net/socket.c (ffffffff81a75e61)
Location: include/linux/sched/signal.h:721
Inline: True
Inline callers:
  - net/socket.c:__sys_accept4
```
```
In net/core/skbuff.c (ffffffff81a82b91)
Location: include/linux/sched/signal.h:721
Inline: True
```
```
In net/unix/scm.c (ffffffff81bebbaf)
Location: include/linux/sched/signal.h:721
Inline: True
Inline callers:
  - net/unix/scm.c:unix_attach_fds
```
```
In net/xdp/xdp_umem.c (ffffffff81c75068)
Location: include/linux/sched/signal.h:721
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_reg
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
In kernel/fork.c (ffffffff810ca1f3)
Location: include/linux/sched/signal.h:761
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/signal.c (ffffffff810ddad1)
Location: include/linux/sched/signal.h:761
Inline: True
Inline callers:
  - kernel/signal.c:__sigqueue_alloc
```
```
In kernel/sys.c (ffffffff810e6c62)
Location: include/linux/sched/signal.h:761
Inline: True
Inline callers:
  - kernel/sys.c:validate_prctl_map_addr
  - kernel/sys.c:flag_nproc_exceeded
```
```
In kernel/sched/core.c (ffffffff81111c29)
Location: include/linux/sched/signal.h:761
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__ia32_sys_nice
  - kernel/sched/core.c:__x64_sys_nice
```
```
In kernel/sched/build_policy.c (ffffffff81137f65)
Location: include/linux/sched/signal.h:761
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:task_tick_rt
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811aa3b7)
Location: include/linux/sched/signal.h:761
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timers_work
  - kernel/time/posix-cpu-timers.c:check_process_timers
```
```
In kernel/acct.c (ffffffff811bb507)
Location: include/linux/sched/signal.h:761
Inline: True
Inline callers:
  - kernel/acct.c:do_acct_process
```
```
In kernel/user_namespace.c (ffffffff811dc08a)
Location: include/linux/sched/signal.h:761
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
  - kernel/user_namespace.c:create_user_ns
  - kernel/user_namespace.c:create_user_ns
  - kernel/user_namespace.c:create_user_ns
```
```
In kernel/events/core.c (ffffffff812db8d9)
Location: include/linux/sched/signal.h:761
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
```
```
In kernel/watch_queue.c (ffffffff812ed531)
Location: include/linux/sched/signal.h:761
Inline: True
Inline callers:
  - kernel/watch_queue.c:add_watch_to_object
```
```
In mm/util.c (ffffffff8131d15f)
Location: include/linux/sched/signal.h:761
Inline: True
Inline callers:
  - mm/util.c:__account_locked_vm
  - mm/util.c:__account_locked_vm
```
```
In mm/mlock.c (ffffffff8134c8e3)
Location: include/linux/sched/signal.h:761
Inline: True
Inline callers:
  - mm/mlock.c:user_shm_lock
  - mm/mlock.c:__do_sys_mlockall
  - mm/mlock.c:__do_sys_mlockall
  - mm/mlock.c:do_mlock
  - mm/mlock.c:do_mlock
```
```
In mm/mmap.c (ffffffff81e6e4b9)
Location: include/linux/sched/signal.h:761
Inline: True
Inline callers:
  - mm/mmap.c:may_expand_vm
  - mm/mmap.c:may_expand_vm
  - mm/mmap.c:may_expand_vm
  - mm/mmap.c:may_expand_vm
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:do_mmap
  - mm/mmap.c:__do_sys_brk
```
```
In fs/read_write.c (ffffffff813f2a74)
Location: include/linux/sched/signal.h:761
Inline: True
Inline callers:
  - fs/read_write.c:generic_write_check_limits
```
```
In fs/exec.c (ffffffff813fc738)
Location: include/linux/sched/signal.h:761
Inline: True
```
```
In fs/select.c (ffffffff8140fa16)
Location: include/linux/sched/signal.h:761
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
```
```
In fs/attr.c (ffffffff81419829)
Location: include/linux/sched/signal.h:761
Inline: True
```
```
In fs/file.c (ffffffff8141c65f)
Location: include/linux/sched/signal.h:761
Inline: True
Inline callers:
  - fs/file.c:f_dupfd
  - fs/file.c:__ia32_sys_dup
  - fs/file.c:__x64_sys_dup
  - fs/file.c:ksys_dup3
  - fs/file.c:receive_fd
  - fs/file.c:replace_fd
```
```
In fs/coredump.c (ffffffff814856d4)
Location: include/linux/sched/signal.h:761
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/array.c (ffffffff814a6e2b)
Location: include/linux/sched/signal.h:761
Inline: True
Inline callers:
  - fs/proc/array.c:proc_pid_status
```
```
In ipc/shm.c (ffffffff8159d1b6)
Location: include/linux/sched/signal.h:761
Inline: True
Inline callers:
  - ipc/shm.c:shmctl_do_lock
```
```
In ipc/mqueue.c (ffffffff8159fc1d)
Location: include/linux/sched/signal.h:761
Inline: True
Inline callers:
  - ipc/mqueue.c:mqueue_get_inode
```
```
In security/selinux/hooks.c (ffffffff815c4daf)
Location: include/linux/sched/signal.h:761
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committing_creds
```
```
In io_uring/io_uring.c (ffffffff816cd3b7)
Location: include/linux/sched/signal.h:761
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_buffer_account_pin
  - io_uring/io_uring.c:io_sqe_files_register
  - io_uring/io_uring.c:io_socket_prep
  - io_uring/io_uring.c:io_accept_prep
  - io_uring/io_uring.c:__io_openat_prep
```
```
In io_uring/io-wq.c (ffffffff816dbebf)
Location: include/linux/sched/signal.h:761
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_wq_max_workers
  - io_uring/io-wq.c:io_wq_max_workers
  - io_uring/io-wq.c:io_wq_create
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff81a7b9ce)
Location: include/linux/sched/signal.h:761
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_replay
  - drivers/vfio/vfio_iommu_type1.c:vfio_pin_map_dma
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages
```
```
In net/socket.c (ffffffff81be8e99)
Location: include/linux/sched/signal.h:761
Inline: True
Inline callers:
  - net/socket.c:__sys_accept4
```
```
In net/core/skbuff.c (ffffffff81bf78b3)
Location: include/linux/sched/signal.h:761
Inline: True
Inline callers:
  - net/core/skbuff.c:mm_account_pinned_pages
```
```
In net/unix/scm.c (ffffffff81d8408f)
Location: include/linux/sched/signal.h:761
Inline: True
Inline callers:
  - net/unix/scm.c:unix_attach_fds
```
```
In net/xdp/xdp_umem.c (ffffffff81e1920c)
Location: include/linux/sched/signal.h:761
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_reg
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
In kernel/fork.c (ffffffff810e7854)
Location: include/linux/sched/signal.h:762
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/signal.c (ffffffff810fdc01)
Location: include/linux/sched/signal.h:762
Inline: True
Inline callers:
  - kernel/signal.c:__sigqueue_alloc
```
```
In kernel/sys.c (ffffffff8110aad2)
Location: include/linux/sched/signal.h:762
Inline: True
Inline callers:
  - kernel/sys.c:validate_prctl_map_addr
  - kernel/sys.c:flag_nproc_exceeded
```
```
In kernel/sched/core.c (ffffffff81138be9)
Location: include/linux/sched/signal.h:762
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__ia32_sys_nice
  - kernel/sched/core.c:__x64_sys_nice
```
```
In kernel/sched/build_policy.c (ffffffff81162625)
Location: include/linux/sched/signal.h:762
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:task_tick_rt
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811ea3d7)
Location: include/linux/sched/signal.h:762
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timers_work
  - kernel/time/posix-cpu-timers.c:check_process_timers
```
```
In kernel/acct.c (ffffffff811fd327)
Location: include/linux/sched/signal.h:762
Inline: True
Inline callers:
  - kernel/acct.c:do_acct_process
```
```
In kernel/user_namespace.c (ffffffff812218f2)
Location: include/linux/sched/signal.h:762
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
  - kernel/user_namespace.c:create_user_ns
  - kernel/user_namespace.c:create_user_ns
  - kernel/user_namespace.c:create_user_ns
```
```
In kernel/events/core.c (ffffffff81343ba0)
Location: include/linux/sched/signal.h:762
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
```
```
In kernel/watch_queue.c (ffffffff81357901)
Location: include/linux/sched/signal.h:762
Inline: True
Inline callers:
  - kernel/watch_queue.c:add_watch_to_object
```
```
In mm/util.c (ffffffff81390ab7)
Location: include/linux/sched/signal.h:762
Inline: True
Inline callers:
  - mm/util.c:__account_locked_vm
  - mm/util.c:__account_locked_vm
```
```
In mm/mlock.c (ffffffff813c5453)
Location: include/linux/sched/signal.h:762
Inline: True
Inline callers:
  - mm/mlock.c:user_shm_lock
  - mm/mlock.c:__do_sys_mlockall
  - mm/mlock.c:__do_sys_mlockall
  - mm/mlock.c:do_mlock
  - mm/mlock.c:do_mlock
```
```
In mm/mmap.c (ffffffff813ca70c)
Location: include/linux/sched/signal.h:762
Inline: True
Inline callers:
  - mm/mmap.c:may_expand_vm
  - mm/mmap.c:may_expand_vm
  - mm/mmap.c:may_expand_vm
  - mm/mmap.c:may_expand_vm
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:do_mmap
  - mm/mmap.c:__do_sys_brk
  - mm/mmap.c:check_brk_limits
```
```
In fs/read_write.c (ffffffff8147b6c4)
Location: include/linux/sched/signal.h:762
Inline: True
Inline callers:
  - fs/read_write.c:generic_write_check_limits
```
```
In fs/exec.c (ffffffff814861e8)
Location: include/linux/sched/signal.h:762
Inline: True
```
```
In fs/select.c (ffffffff8149a656)
Location: include/linux/sched/signal.h:762
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
```
```
In fs/attr.c (ffffffff814a52f9)
Location: include/linux/sched/signal.h:762
Inline: True
```
```
In fs/file.c (ffffffff814a876f)
Location: include/linux/sched/signal.h:762
Inline: True
Inline callers:
  - fs/file.c:f_dupfd
  - fs/file.c:__ia32_sys_dup
  - fs/file.c:__x64_sys_dup
  - fs/file.c:ksys_dup3
  - fs/file.c:receive_fd
  - fs/file.c:replace_fd
```
```
In fs/coredump.c (ffffffff81518d21)
Location: include/linux/sched/signal.h:762
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/array.c (ffffffff8153c48b)
Location: include/linux/sched/signal.h:762
Inline: True
Inline callers:
  - fs/proc/array.c:proc_pid_status
```
```
In ipc/shm.c (ffffffff816466a6)
Location: include/linux/sched/signal.h:762
Inline: True
Inline callers:
  - ipc/shm.c:shmctl_do_lock
```
```
In ipc/mqueue.c (ffffffff816494bd)
Location: include/linux/sched/signal.h:762
Inline: True
Inline callers:
  - ipc/mqueue.c:mqueue_get_inode
```
```
In security/selinux/hooks.c (ffffffff816718af)
Location: include/linux/sched/signal.h:762
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committing_creds
```
```
In io_uring/openclose.c (ffffffff81794551)
Location: include/linux/sched/signal.h:762
Inline: True
Inline callers:
  - io_uring/openclose.c:__io_openat_prep
```
```
In io_uring/net.c (ffffffff81798230)
Location: include/linux/sched/signal.h:762
Inline: True
Inline callers:
  - io_uring/net.c:io_socket_prep
  - io_uring/net.c:io_accept_prep
```
```
In io_uring/rsrc.c (ffffffff817a1d5a)
Location: include/linux/sched/signal.h:762
Inline: True
Inline callers:
  - io_uring/rsrc.c:io_sqe_files_register
  - io_uring/rsrc.c:__io_account_mem
```
```
In io_uring/io-wq.c (ffffffff817a7fcf)
Location: include/linux/sched/signal.h:762
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_wq_max_workers
  - io_uring/io-wq.c:io_wq_max_workers
  - io_uring/io-wq.c:io_wq_create
```
```
In net/core/skbuff.c (ffffffff81da6623)
Location: include/linux/sched/signal.h:762
Inline: True
Inline callers:
  - net/core/skbuff.c:mm_account_pinned_pages
```
```
In net/unix/scm.c (ffffffff81f5191f)
Location: include/linux/sched/signal.h:762
Inline: True
Inline callers:
  - net/unix/scm.c:unix_attach_fds
```
```
In net/xdp/xdp_umem.c (ffffffff81ff0462)
Location: include/linux/sched/signal.h:762
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_reg
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
In kernel/fork.c (ffffffff810f3405)
Location: include/linux/sched/signal.h:762
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/signal.c (ffffffff81109c71)
Location: include/linux/sched/signal.h:762
Inline: True
Inline callers:
  - kernel/signal.c:__sigqueue_alloc
```
```
In kernel/sys.c (ffffffff81116c92)
Location: include/linux/sched/signal.h:762
Inline: True
Inline callers:
  - kernel/sys.c:validate_prctl_map_addr
  - kernel/sys.c:flag_nproc_exceeded
```
```
In kernel/sched/core.c (ffffffff81147a4e)
Location: include/linux/sched/signal.h:762
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__ia32_sys_nice
  - kernel/sched/core.c:__x64_sys_nice
```
```
In kernel/sched/build_policy.c (ffffffff81172da5)
Location: include/linux/sched/signal.h:762
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:task_tick_rt
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811feaf7)
Location: include/linux/sched/signal.h:762
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timers_work
  - kernel/time/posix-cpu-timers.c:check_process_timers
```
```
In kernel/acct.c (ffffffff812124b7)
Location: include/linux/sched/signal.h:762
Inline: True
Inline callers:
  - kernel/acct.c:do_acct_process
```
```
In kernel/user_namespace.c (ffffffff81237da7)
Location: include/linux/sched/signal.h:762
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
  - kernel/user_namespace.c:create_user_ns
  - kernel/user_namespace.c:create_user_ns
  - kernel/user_namespace.c:create_user_ns
```
```
In kernel/events/core.c (ffffffff81374c26)
Location: include/linux/sched/signal.h:762
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
```
```
In kernel/watch_queue.c (ffffffff81389163)
Location: include/linux/sched/signal.h:762
Inline: True
Inline callers:
  - kernel/watch_queue.c:add_watch_to_object
```
```
In mm/util.c (ffffffff813c33bd)
Location: include/linux/sched/signal.h:762
Inline: True
Inline callers:
  - mm/util.c:__account_locked_vm
  - mm/util.c:__account_locked_vm
```
```
In mm/mlock.c (ffffffff813f9823)
Location: include/linux/sched/signal.h:762
Inline: True
Inline callers:
  - mm/mlock.c:user_shm_lock
  - mm/mlock.c:__do_sys_mlockall
  - mm/mlock.c:__do_sys_mlockall
  - mm/mlock.c:do_mlock
  - mm/mlock.c:do_mlock
```
```
In mm/mmap.c (ffffffff813fecdc)
Location: include/linux/sched/signal.h:762
Inline: True
Inline callers:
  - mm/mmap.c:may_expand_vm
  - mm/mmap.c:may_expand_vm
  - mm/mmap.c:may_expand_vm
  - mm/mmap.c:may_expand_vm
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:do_mmap
  - mm/mmap.c:__do_sys_brk
  - mm/mmap.c:check_brk_limits
```
```
In fs/read_write.c (ffffffff814b0254)
Location: include/linux/sched/signal.h:762
Inline: True
Inline callers:
  - fs/read_write.c:generic_write_check_limits
```
```
In fs/exec.c (ffffffff814bad53)
Location: include/linux/sched/signal.h:762
Inline: True
```
```
In fs/select.c (ffffffff814cf706)
Location: include/linux/sched/signal.h:762
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
```
```
In fs/attr.c (ffffffff814da729)
Location: include/linux/sched/signal.h:762
Inline: True
```
```
In fs/file.c (ffffffff814dd75f)
Location: include/linux/sched/signal.h:762
Inline: True
Inline callers:
  - fs/file.c:f_dupfd
  - fs/file.c:__ia32_sys_dup
  - fs/file.c:__x64_sys_dup
  - fs/file.c:ksys_dup3
  - fs/file.c:receive_fd
  - fs/file.c:replace_fd
```
```
In fs/coredump.c (ffffffff81550621)
Location: include/linux/sched/signal.h:762
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/array.c (ffffffff815747cc)
Location: include/linux/sched/signal.h:762
Inline: True
Inline callers:
  - fs/proc/array.c:proc_pid_status
```
```
In ipc/shm.c (ffffffff8167ebbc)
Location: include/linux/sched/signal.h:762
Inline: True
Inline callers:
  - ipc/shm.c:shmctl_do_lock
```
```
In ipc/mqueue.c (ffffffff81681a1d)
Location: include/linux/sched/signal.h:762
Inline: True
Inline callers:
  - ipc/mqueue.c:mqueue_get_inode
```
```
In security/selinux/hooks.c (ffffffff816aa08b)
Location: include/linux/sched/signal.h:762
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committing_creds
```
```
In io_uring/openclose.c (ffffffff817d5209)
Location: include/linux/sched/signal.h:762
Inline: True
Inline callers:
  - io_uring/openclose.c:__io_openat_prep
```
```
In io_uring/net.c (ffffffff817d8fb0)
Location: include/linux/sched/signal.h:762
Inline: True
Inline callers:
  - io_uring/net.c:io_socket_prep
  - io_uring/net.c:io_accept_prep
```
```
In io_uring/rsrc.c (ffffffff817e2ebb)
Location: include/linux/sched/signal.h:762
Inline: True
Inline callers:
  - io_uring/rsrc.c:io_sqe_files_register
  - io_uring/rsrc.c:__io_account_mem
```
```
In io_uring/io-wq.c (ffffffff817e8e92)
Location: include/linux/sched/signal.h:762
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_wq_max_workers
  - io_uring/io-wq.c:io_wq_max_workers
  - io_uring/io-wq.c:io_wq_create
```
```
In net/core/skbuff.c (ffffffff81e15710)
Location: include/linux/sched/signal.h:762
Inline: True
Inline callers:
  - net/core/skbuff.c:mm_account_pinned_pages
```
```
In net/unix/scm.c (ffffffff81fb12af)
Location: include/linux/sched/signal.h:762
Inline: True
Inline callers:
  - net/unix/scm.c:unix_attach_fds
```
```
In net/xdp/xdp_umem.c (ffffffff8206c610)
Location: include/linux/sched/signal.h:762
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_reg
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
In arch/x86/kernel/shstk.c (ffffffff810ca8e0)
Location: include/linux/sched/signal.h:765
Inline: True
Inline callers:
  - arch/x86/kernel/shstk.c:shstk_alloc_thread_stack
  - arch/x86/kernel/shstk.c:shstk_setup
```
```
In kernel/fork.c (ffffffff810fc7b5)
Location: include/linux/sched/signal.h:765
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/signal.c (ffffffff81113611)
Location: include/linux/sched/signal.h:765
Inline: True
Inline callers:
  - kernel/signal.c:__sigqueue_alloc
```
```
In kernel/sys.c (ffffffff81120682)
Location: include/linux/sched/signal.h:765
Inline: True
Inline callers:
  - kernel/sys.c:validate_prctl_map_addr
  - kernel/sys.c:flag_nproc_exceeded
```
```
In kernel/sched/core.c (ffffffff8115327e)
Location: include/linux/sched/signal.h:765
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__ia32_sys_nice
  - kernel/sched/core.c:__x64_sys_nice
```
```
In kernel/sched/build_policy.c (ffffffff811806b5)
Location: include/linux/sched/signal.h:765
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:task_tick_rt
```
```
In kernel/time/posix-cpu-timers.c (ffffffff81214d7c)
Location: include/linux/sched/signal.h:765
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:check_process_timers
  - kernel/time/posix-cpu-timers.c:check_thread_timers
```
```
In kernel/acct.c (ffffffff81229b37)
Location: include/linux/sched/signal.h:765
Inline: True
Inline callers:
  - kernel/acct.c:do_acct_process
```
```
In kernel/user_namespace.c (ffffffff812518a7)
Location: include/linux/sched/signal.h:765
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
  - kernel/user_namespace.c:create_user_ns
  - kernel/user_namespace.c:create_user_ns
  - kernel/user_namespace.c:create_user_ns
```
```
In kernel/events/core.c (ffffffff8139df56)
Location: include/linux/sched/signal.h:765
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
```
```
In kernel/watch_queue.c (ffffffff813b2bb3)
Location: include/linux/sched/signal.h:765
Inline: True
Inline callers:
  - kernel/watch_queue.c:add_watch_to_object
```
```
In mm/util.c (ffffffff813ededd)
Location: include/linux/sched/signal.h:765
Inline: True
Inline callers:
  - mm/util.c:__account_locked_vm
  - mm/util.c:__account_locked_vm
```
```
In mm/mlock.c (ffffffff814255e3)
Location: include/linux/sched/signal.h:765
Inline: True
Inline callers:
  - mm/mlock.c:user_shm_lock
  - mm/mlock.c:__do_sys_mlockall
  - mm/mlock.c:__do_sys_mlockall
  - mm/mlock.c:do_mlock
  - mm/mlock.c:do_mlock
```
```
In mm/mmap.c (ffffffff8142b14c)
Location: include/linux/sched/signal.h:765
Inline: True
Inline callers:
  - mm/mmap.c:may_expand_vm
  - mm/mmap.c:may_expand_vm
  - mm/mmap.c:may_expand_vm
  - mm/mmap.c:may_expand_vm
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:do_mmap
  - mm/mmap.c:__do_sys_brk
  - mm/mmap.c:check_brk_limits
```
```
In fs/read_write.c (ffffffff814e1a14)
Location: include/linux/sched/signal.h:765
Inline: True
Inline callers:
  - fs/read_write.c:generic_write_check_limits
```
```
In fs/exec.c (ffffffff814ed2c7)
Location: include/linux/sched/signal.h:765
Inline: True
```
```
In fs/select.c (ffffffff81502046)
Location: include/linux/sched/signal.h:765
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
```
```
In fs/attr.c (ffffffff8150ccc9)
Location: include/linux/sched/signal.h:765
Inline: True
```
```
In fs/file.c (ffffffff815101af)
Location: include/linux/sched/signal.h:765
Inline: True
Inline callers:
  - fs/file.c:f_dupfd
  - fs/file.c:__ia32_sys_dup
  - fs/file.c:__x64_sys_dup
  - fs/file.c:ksys_dup3
  - fs/file.c:replace_fd
```
```
In fs/coredump.c (ffffffff815864b1)
Location: include/linux/sched/signal.h:765
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/array.c (ffffffff815ad19c)
Location: include/linux/sched/signal.h:765
Inline: True
Inline callers:
  - fs/proc/array.c:proc_pid_status
```
```
In ipc/shm.c (ffffffff816bafac)
Location: include/linux/sched/signal.h:765
Inline: True
Inline callers:
  - ipc/shm.c:shmctl_do_lock
```
```
In ipc/mqueue.c (ffffffff816bddfe)
Location: include/linux/sched/signal.h:765
Inline: True
Inline callers:
  - ipc/mqueue.c:mqueue_get_inode
```
```
In security/selinux/hooks.c (ffffffff816e689e)
Location: include/linux/sched/signal.h:765
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committing_creds
```
```
In io_uring/openclose.c (ffffffff81819059)
Location: include/linux/sched/signal.h:765
Inline: True
Inline callers:
  - io_uring/openclose.c:__io_openat_prep
```
```
In io_uring/net.c (ffffffff8181d2c0)
Location: include/linux/sched/signal.h:765
Inline: True
Inline callers:
  - io_uring/net.c:io_socket_prep
  - io_uring/net.c:io_accept_prep
```
```
In io_uring/rsrc.c (ffffffff81826f94)
Location: include/linux/sched/signal.h:765
Inline: True
Inline callers:
  - io_uring/rsrc.c:io_sqe_files_register
  - io_uring/rsrc.c:__io_account_mem
```
```
In io_uring/io-wq.c (ffffffff8182ec42)
Location: include/linux/sched/signal.h:765
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_wq_max_workers
  - io_uring/io-wq.c:io_wq_max_workers
  - io_uring/io-wq.c:io_wq_create
```
```
In net/core/skbuff.c (ffffffff81ed2ab0)
Location: include/linux/sched/signal.h:765
Inline: True
Inline callers:
  - net/core/skbuff.c:mm_account_pinned_pages
```
```
In net/unix/scm.c (ffffffff8207e9f8)
Location: include/linux/sched/signal.h:765
Inline: True
Inline callers:
  - net/unix/scm.c:unix_attach_fds
```
```
In net/xdp/xdp_umem.c (ffffffff8214040e)
Location: include/linux/sched/signal.h:765
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_reg
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
In kernel/fork.c (ffff8000100f3758)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/signal.c (ffff80001010b480)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - kernel/signal.c:__sigqueue_alloc
```
```
In kernel/sys.c (ffff8000101146b0)
Location: include/linux/sched/signal.h:684
Inline: True
```
```
In kernel/sched/core.c (ffff80001013715c)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__arm64_sys_nice
```
```
In kernel/sched/rt.c (ffff8000101507d4)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - kernel/sched/rt.c:task_tick_rt
```
```
In kernel/time/posix-cpu-timers.c (ffff8000101ae7a0)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
```
```
In kernel/bpf/syscall.c (ffff800010264110)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_prog_charge
  - kernel/bpf/syscall.c:bpf_charge_memlock
```
```
In kernel/events/core.c (ffff80001029d0ec)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
```
```
In mm/filemap.c (ffff8000102ae078)
Location: include/linux/sched/signal.h:684
Inline: True
```
```
In mm/util.c (ffff8000102d80c8)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - mm/util.c:__account_locked_vm
  - mm/util.c:__account_locked_vm
```
```
In mm/mlock.c (ffff8000102fed30)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - mm/mlock.c:user_shm_lock
  - mm/mlock.c:__arm64_sys_mlockall
  - mm/mlock.c:__arm64_sys_mlockall
  - mm/mlock.c:do_mlock
  - mm/mlock.c:do_mlock
```
```
In mm/mmap.c (ffff800010302e04)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:do_mmap
  - mm/mmap.c:__arm64_sys_brk
```
```
In mm/mremap.c (ffff800010305cf8)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - mm/mremap.c:vma_to_resize
```
```
In fs/exec.c (ffff80001038dd78)
Location: include/linux/sched/signal.h:684
Inline: True
```
```
In fs/select.c (ffff8000103a2f88)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
```
```
In fs/attr.c (ffff8000103b006c)
Location: include/linux/sched/signal.h:684
Inline: True
```
```
In fs/file.c (ffff8000103b29b0)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - fs/file.c:f_dupfd
  - fs/file.c:f_dupfd
  - fs/file.c:ksys_dup3
  - fs/file.c:replace_fd
  - fs/file.c:get_unused_fd_flags
```
```
In fs/io_uring.c (ffff800010403bbc)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - fs/io_uring.c:__arm64_sys_io_uring_register
  - fs/io_uring.c:io_account_mem
```
```
In fs/coredump.c (ffff800010428374)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/array.c (ffff800010445fbc)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - fs/proc/array.c:proc_pid_status
```
```
In ipc/shm.c (ffff800010527828)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - ipc/shm.c:shmctl_do_lock
```
```
In ipc/mqueue.c (ffff800010529c3c)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - ipc/mqueue.c:mqueue_get_inode
```
```
In security/selinux/hooks.c (ffff800010550170)
Location: include/linux/sched/signal.h:684
Inline: True
```
```
In net/core/skbuff.c (ffff800010bb2d30)
Location: include/linux/sched/signal.h:684
Inline: True
```
```
In net/unix/scm.c (ffff800010cf5378)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - net/unix/scm.c:unix_attach_fds
```
```
In net/xdp/xdp_umem.c (ffff800010d81368)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_create
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
In kernel/fork.c (c0351e94)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/signal.c (c0363d60)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - kernel/signal.c:__sigqueue_alloc
```
```
In kernel/sys.c (c036ac68)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - kernel/sys.c:set_user
```
```
In kernel/sched/core.c (c0385ea0)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__se_sys_nice
```
```
In kernel/sched/rt.c (c039e498)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - kernel/sched/rt.c:task_tick_rt
```
```
In kernel/time/posix-cpu-timers.c (c03f9880)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
```
```
In kernel/bpf/syscall.c (c0496700)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_prog_charge
  - kernel/bpf/syscall.c:bpf_charge_memlock
```
```
In kernel/events/core.c (c04cc8c4)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
```
```
In mm/filemap.c (c04db4c8)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - mm/filemap.c:generic_write_check_limits
```
```
In mm/util.c (c04ff560)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - mm/util.c:__account_locked_vm
  - mm/util.c:__account_locked_vm
```
```
In mm/mlock.c (c051dd7c)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - mm/mlock.c:user_shm_lock
  - mm/mlock.c:__se_sys_mlockall
  - mm/mlock.c:__se_sys_mlockall
  - mm/mlock.c:do_mlock
  - mm/mlock.c:do_mlock
```
```
In mm/mmap.c (c0520f84)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - mm/mmap.c:may_expand_vm
  - mm/mmap.c:may_expand_vm
  - mm/mmap.c:may_expand_vm
  - mm/mmap.c:may_expand_vm
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:do_mmap
  - mm/mmap.c:__se_sys_brk
```
```
In mm/mremap.c (c0523c28)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - mm/mremap.c:vma_to_resize
```
```
In fs/exec.c (c05756a0)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - fs/exec.c:__do_execve_file
```
```
In fs/select.c (c0585870)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
```
```
In fs/attr.c (c058f8ac)
Location: include/linux/sched/signal.h:684
Inline: True
```
```
In fs/file.c (c0591c90)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - fs/file.c:f_dupfd
  - fs/file.c:f_dupfd
  - fs/file.c:ksys_dup3
  - fs/file.c:replace_fd
  - fs/file.c:get_unused_fd_flags
```
```
In fs/io_uring.c (c05d7a84)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - fs/io_uring.c:__se_sys_io_uring_register
  - fs/io_uring.c:io_account_mem
```
```
In fs/binfmt_flat.c (c05ec8b8)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - fs/binfmt_flat.c:load_flat_file
```
```
In fs/coredump.c (c05f0ffc)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
  - fs/coredump.c:format_corename
```
```
In fs/proc/array.c (c060b148)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - fs/proc/array.c:proc_pid_status
```
```
In ipc/shm.c (c06e1618)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - ipc/shm.c:ksys_shmctl
```
```
In ipc/mqueue.c (c06e2900)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - ipc/mqueue.c:mqueue_get_inode
```
```
In security/selinux/hooks.c (c0706150)
Location: include/linux/sched/signal.h:684
Inline: True
```
```
In net/core/skbuff.c (c0ccf8c8)
Location: include/linux/sched/signal.h:684
Inline: True
```
```
In net/unix/scm.c (c0dfbe74)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - net/unix/scm.c:unix_attach_fds
```
```
In net/xdp/xdp_umem.c (c0e7b924)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_create
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
In kernel/fork.c (c0000000001394d0)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/signal.c (c000000000151fb4)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - kernel/signal.c:__sigqueue_alloc
```
```
In kernel/sys.c (c00000000015d41c)
Location: include/linux/sched/signal.h:684
Inline: True
```
```
In kernel/sched/core.c (c000000000182650)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__se_sys_nice
```
```
In kernel/sched/rt.c (c0000000001a4898)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - kernel/sched/rt.c:task_tick_rt
```
```
In kernel/time/posix-cpu-timers.c (c000000000212d54)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
```
```
In kernel/bpf/syscall.c (c000000000308ffc)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_prog_charge
  - kernel/bpf/syscall.c:bpf_map_charge_memlock
  - kernel/bpf/syscall.c:bpf_map_charge_init
```
```
In kernel/events/core.c (c00000000034da58)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
```
```
In mm/filemap.c (c0000000003634c0)
Location: include/linux/sched/signal.h:684
Inline: True
```
```
In mm/util.c (c000000000397d78)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - mm/util.c:__account_locked_vm
  - mm/util.c:__account_locked_vm
```
```
In mm/mlock.c (c0000000003caa04)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - mm/mlock.c:user_shm_lock
  - mm/mlock.c:__se_sys_mlockall
  - mm/mlock.c:__se_sys_mlockall
  - mm/mlock.c:do_mlock
  - mm/mlock.c:do_mlock
```
```
In mm/mmap.c (c0000000003cf648)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:do_mmap
  - mm/mmap.c:__se_sys_brk
```
```
In mm/mremap.c (c0000000003d33e0)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - mm/mremap.c:vma_to_resize
```
```
In fs/exec.c (c000000000485fac)
Location: include/linux/sched/signal.h:684
Inline: True
```
```
In fs/select.c (c00000000049ccc4)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
```
```
In fs/attr.c (c0000000004ab730)
Location: include/linux/sched/signal.h:684
Inline: True
```
```
In fs/file.c (c0000000004ae900)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - fs/file.c:f_dupfd
  - fs/file.c:f_dupfd
  - fs/file.c:ksys_dup3
  - fs/file.c:replace_fd
  - fs/file.c:get_unused_fd_flags
```
```
In fs/io_uring.c (c000000000510a68)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - fs/io_uring.c:__se_sys_io_uring_register
  - fs/io_uring.c:io_account_mem
```
```
In fs/coredump.c (c000000000538508)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/array.c (c00000000055bbf4)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - fs/proc/array.c:proc_pid_status
```
```
In ipc/shm.c (c00000000067224c)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - ipc/shm.c:shmctl_do_lock
```
```
In ipc/mqueue.c (c000000000674d00)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - ipc/mqueue.c:mqueue_get_inode
```
```
In security/selinux/hooks.c (c0000000006aadf4)
Location: include/linux/sched/signal.h:684
Inline: True
```
```
In net/core/skbuff.c (c000000000c89bbc)
Location: include/linux/sched/signal.h:684
Inline: True
```
```
In net/unix/scm.c (c000000000e1b4b8)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - net/unix/scm.c:unix_attach_fds
```
```
In net/xdp/xdp_umem.c (c000000000ec12c0)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_create
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
In kernel/fork.c (ffffffe0000bfe8e)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/signal.c (ffffffe0000cd4de)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - kernel/signal.c:__sigqueue_alloc
```
```
In kernel/sys.c (ffffffe0000d233e)
Location: include/linux/sched/signal.h:684
Inline: True
```
```
In kernel/sched/core.c (ffffffe0000e7992)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
```
```
In kernel/sched/rt.c (ffffffe0000f8eaa)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - kernel/sched/rt.c:task_tick_rt
```
```
In kernel/time/posix-cpu-timers.c (ffffffe00013822a)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
```
```
In kernel/bpf/syscall.c (ffffffe0001a052c)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_map_charge_memlock
  - kernel/bpf/syscall.c:bpf_map_charge_init
```
```
In kernel/events/core.c (ffffffe0001ce0d8)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
```
```
In mm/filemap.c (ffffffe0001d4d1a)
Location: include/linux/sched/signal.h:684
Inline: True
```
```
In mm/util.c (ffffffe0001f2a3a)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - mm/util.c:__account_locked_vm
  - mm/util.c:__account_locked_vm
```
```
In mm/mlock.c (ffffffe00020cf98)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - mm/mlock.c:user_shm_lock
  - mm/mlock.c:__se_sys_mlockall
  - mm/mlock.c:__se_sys_mlockall
  - mm/mlock.c:do_mlock
  - mm/mlock.c:do_mlock
```
```
In mm/mmap.c (ffffffe00020fb12)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:do_mmap
  - mm/mmap.c:__se_sys_brk
```
```
In mm/mremap.c (ffffffe00021197a)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - mm/mremap.c:vma_to_resize
```
```
In fs/exec.c (ffffffe00025e8c0)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - fs/exec.c:__do_execve_file
```
```
In fs/select.c (ffffffe00026b074)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
```
```
In fs/attr.c (ffffffe0002744c4)
Location: include/linux/sched/signal.h:684
Inline: True
```
```
In fs/file.c (ffffffe0002769ec)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - fs/file.c:f_dupfd
  - fs/file.c:f_dupfd
  - fs/file.c:ksys_dup3
  - fs/file.c:replace_fd
  - fs/file.c:get_unused_fd_flags
```
```
In fs/io_uring.c (ffffffe0002b12d0)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - fs/io_uring.c:__se_sys_io_uring_register
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_sqe_buffer_register
```
```
In fs/binfmt_flat.c (ffffffe0002c2e56)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - fs/binfmt_flat.c:load_flat_file
```
```
In fs/coredump.c (ffffffe0002c65ba)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/array.c (ffffffe0002dbfca)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - fs/proc/array.c:proc_pid_status
```
```
In ipc/shm.c (ffffffe00038b746)
Location: include/linux/sched/signal.h:684
Inline: True
```
```
In ipc/mqueue.c (ffffffe00038d572)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - ipc/mqueue.c:mqueue_get_inode
```
```
In security/selinux/hooks.c (ffffffe0003a8a2e)
Location: include/linux/sched/signal.h:684
Inline: True
```
```
In net/core/skbuff.c (ffffffe000743826)
Location: include/linux/sched/signal.h:684
Inline: True
```
```
In net/unix/scm.c (ffffffe000840e9a)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - net/unix/scm.c:unix_attach_fds
```
```
In net/xdp/xdp_umem.c (ffffffe0008ad832)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_create
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
In kernel/fork.c (ffffffff81098474)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/signal.c (ffffffff810a9e2c)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - kernel/signal.c:__sigqueue_alloc
```
```
In kernel/sys.c (ffffffff810b3440)
Location: include/linux/sched/signal.h:684
Inline: True
```
```
In kernel/sched/core.c (ffffffff810d0e7e)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__ia32_sys_nice
  - kernel/sched/core.c:__x64_sys_nice
```
```
In kernel/sched/rt.c (ffffffff810e8df3)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - kernel/sched/rt.c:task_tick_rt
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8113c9d6)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
```
```
In kernel/bpf/syscall.c (ffffffff811d9b1f)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_prog_charge
  - kernel/bpf/syscall.c:bpf_charge_memlock
```
```
In kernel/events/core.c (ffffffff8120b3e5)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
```
```
In mm/filemap.c (ffffffff81219b47)
Location: include/linux/sched/signal.h:684
Inline: True
```
```
In mm/util.c (ffffffff8123d769)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - mm/util.c:__account_locked_vm
  - mm/util.c:__account_locked_vm
```
```
In mm/mlock.c (ffffffff812603f3)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - mm/mlock.c:user_shm_lock
  - mm/mlock.c:__ia32_sys_mlockall
  - mm/mlock.c:__ia32_sys_mlockall
  - mm/mlock.c:__x64_sys_mlockall
  - mm/mlock.c:__x64_sys_mlockall
  - mm/mlock.c:do_mlock
  - mm/mlock.c:do_mlock
```
```
In mm/mmap.c (ffffffff81263c84)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:do_mmap
  - mm/mmap.c:__ia32_sys_brk
  - mm/mmap.c:__x64_sys_brk
```
```
In mm/mremap.c (ffffffff812679cf)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - mm/mremap.c:vma_to_resize
```
```
In fs/exec.c (ffffffff812ddfc7)
Location: include/linux/sched/signal.h:684
Inline: True
```
```
In fs/select.c (ffffffff812ee45b)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
```
```
In fs/attr.c (ffffffff812f7164)
Location: include/linux/sched/signal.h:684
Inline: True
```
```
In fs/file.c (ffffffff812f8ffc)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - fs/file.c:f_dupfd
  - fs/file.c:f_dupfd
  - fs/file.c:ksys_dup3
  - fs/file.c:replace_fd
  - fs/file.c:get_unused_fd_flags
```
```
In fs/io_uring.c (ffffffff8133e189)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_sqe_buffer_register
```
```
In fs/coredump.c (ffffffff8135a254)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/array.c (ffffffff813723d0)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - fs/proc/array.c:proc_pid_status
```
```
In ipc/shm.c (ffffffff814379d6)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - ipc/shm.c:shmctl_do_lock
```
```
In ipc/mqueue.c (ffffffff8143c2a6)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - ipc/mqueue.c:mqueue_get_inode
```
```
In security/selinux/hooks.c (ffffffff8145aa1b)
Location: include/linux/sched/signal.h:684
Inline: True
```
```
In net/core/skbuff.c (ffffffff818b90ad)
Location: include/linux/sched/signal.h:684
Inline: True
```
```
In net/unix/scm.c (ffffffff819d41cf)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - net/unix/scm.c:unix_attach_fds
```
```
In net/xdp/xdp_umem.c (ffffffff81a4be84)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_create
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
In kernel/fork.c (ffffffff81086eba)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/signal.c (ffffffff810987dc)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - kernel/signal.c:__sigqueue_alloc
```
```
In kernel/sys.c (ffffffff810a1d70)
Location: include/linux/sched/signal.h:684
Inline: True
```
```
In kernel/sched/core.c (ffffffff810bf07d)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__ia32_sys_nice
  - kernel/sched/core.c:__x64_sys_nice
```
```
In kernel/sched/rt.c (ffffffff810d8933)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - kernel/sched/rt.c:task_tick_rt
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8112f450)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
```
```
In kernel/bpf/syscall.c (ffffffff811cc8df)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_prog_charge
  - kernel/bpf/syscall.c:bpf_charge_memlock
```
```
In kernel/events/core.c (ffffffff811fe1b5)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
```
```
In mm/filemap.c (ffffffff8120cd57)
Location: include/linux/sched/signal.h:684
Inline: True
```
```
In mm/util.c (ffffffff81230769)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - mm/util.c:__account_locked_vm
  - mm/util.c:__account_locked_vm
```
```
In mm/mlock.c (ffffffff81252813)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - mm/mlock.c:user_shm_lock
  - mm/mlock.c:__ia32_sys_mlockall
  - mm/mlock.c:__ia32_sys_mlockall
  - mm/mlock.c:__x64_sys_mlockall
  - mm/mlock.c:__x64_sys_mlockall
  - mm/mlock.c:do_mlock
  - mm/mlock.c:do_mlock
```
```
In mm/mmap.c (ffffffff812560a4)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:do_mmap
  - mm/mmap.c:__ia32_sys_brk
  - mm/mmap.c:__x64_sys_brk
```
```
In mm/mremap.c (ffffffff81259d1f)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - mm/mremap.c:vma_to_resize
```
```
In fs/exec.c (ffffffff812cf2f7)
Location: include/linux/sched/signal.h:684
Inline: True
```
```
In fs/select.c (ffffffff812df08b)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
```
```
In fs/attr.c (ffffffff812e7d84)
Location: include/linux/sched/signal.h:684
Inline: True
```
```
In fs/file.c (ffffffff812e9c1c)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - fs/file.c:f_dupfd
  - fs/file.c:f_dupfd
  - fs/file.c:ksys_dup3
  - fs/file.c:replace_fd
  - fs/file.c:get_unused_fd_flags
```
```
In fs/io_uring.c (ffffffff8132ee49)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_sqe_buffer_register
```
```
In fs/coredump.c (ffffffff8134af04)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/array.c (ffffffff81362ea0)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - fs/proc/array.c:proc_pid_status
```
```
In ipc/shm.c (ffffffff81428446)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - ipc/shm.c:shmctl_do_lock
```
```
In ipc/mqueue.c (ffffffff8142cd16)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - ipc/mqueue.c:mqueue_get_inode
```
```
In security/selinux/hooks.c (ffffffff8144b44b)
Location: include/linux/sched/signal.h:684
Inline: True
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff8177f22e)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_map
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages
```
```
In net/core/skbuff.c (ffffffff81872ffd)
Location: include/linux/sched/signal.h:684
Inline: True
```
```
In net/unix/scm.c (ffffffff81990f8f)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - net/unix/scm.c:unix_attach_fds
```
```
In net/xdp/xdp_umem.c (ffffffff81a08a74)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_create
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
In kernel/fork.c (ffffffff81098424)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/signal.c (ffffffff810a938c)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - kernel/signal.c:__sigqueue_alloc
```
```
In kernel/sys.c (ffffffff810b29a0)
Location: include/linux/sched/signal.h:684
Inline: True
```
```
In kernel/sched/core.c (ffffffff810ceff0)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__ia32_sys_nice
  - kernel/sched/core.c:__x64_sys_nice
```
```
In kernel/sched/rt.c (ffffffff810e5aa3)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - kernel/sched/rt.c:task_tick_rt
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8113a6f6)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
```
```
In kernel/bpf/syscall.c (ffffffff811d78ef)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_prog_charge
  - kernel/bpf/syscall.c:bpf_charge_memlock
```
```
In kernel/events/core.c (ffffffff81209185)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
```
```
In mm/filemap.c (ffffffff812178e7)
Location: include/linux/sched/signal.h:684
Inline: True
```
```
In mm/util.c (ffffffff8123b509)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - mm/util.c:__account_locked_vm
  - mm/util.c:__account_locked_vm
```
```
In mm/mlock.c (ffffffff8125e193)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - mm/mlock.c:user_shm_lock
  - mm/mlock.c:__ia32_sys_mlockall
  - mm/mlock.c:__ia32_sys_mlockall
  - mm/mlock.c:__x64_sys_mlockall
  - mm/mlock.c:__x64_sys_mlockall
  - mm/mlock.c:do_mlock
  - mm/mlock.c:do_mlock
```
```
In mm/mmap.c (ffffffff81261a24)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:do_mmap
  - mm/mmap.c:__ia32_sys_brk
  - mm/mmap.c:__x64_sys_brk
```
```
In mm/mremap.c (ffffffff8126576f)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - mm/mremap.c:vma_to_resize
```
```
In fs/exec.c (ffffffff812dbdd7)
Location: include/linux/sched/signal.h:684
Inline: True
```
```
In fs/select.c (ffffffff812ec26b)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
```
```
In fs/attr.c (ffffffff812f4f74)
Location: include/linux/sched/signal.h:684
Inline: True
```
```
In fs/file.c (ffffffff812f6e0c)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - fs/file.c:f_dupfd
  - fs/file.c:f_dupfd
  - fs/file.c:ksys_dup3
  - fs/file.c:replace_fd
  - fs/file.c:get_unused_fd_flags
```
```
In fs/io_uring.c (ffffffff8133bc59)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_sqe_buffer_register
```
```
In fs/coredump.c (ffffffff81357d24)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/array.c (ffffffff8136fea0)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - fs/proc/array.c:proc_pid_status
```
```
In ipc/shm.c (ffffffff81433b76)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - ipc/shm.c:shmctl_do_lock
```
```
In ipc/mqueue.c (ffffffff81438446)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - ipc/mqueue.c:mqueue_get_inode
```
```
In security/selinux/hooks.c (ffffffff81456abb)
Location: include/linux/sched/signal.h:684
Inline: True
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff817c9ffe)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_map
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages
```
```
In net/core/skbuff.c (ffffffff8190a0ad)
Location: include/linux/sched/signal.h:684
Inline: True
```
```
In net/unix/scm.c (ffffffff81a3ec4f)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - net/unix/scm.c:unix_attach_fds
```
```
In net/xdp/xdp_umem.c (ffffffff81ab7d34)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_create
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
In kernel/fork.c (ffffffff810a001b)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/signal.c (ffffffff810b15b2)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - kernel/signal.c:__sigqueue_alloc
```
```
In kernel/sys.c (ffffffff810bafa0)
Location: include/linux/sched/signal.h:684
Inline: True
```
```
In kernel/sched/core.c (ffffffff810d83ff)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__ia32_sys_nice
  - kernel/sched/core.c:__x64_sys_nice
```
```
In kernel/sched/rt.c (ffffffff810f0983)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - kernel/sched/rt.c:task_tick_rt
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811471b6)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
```
```
In kernel/bpf/syscall.c (ffffffff811e5c8f)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_prog_charge
  - kernel/bpf/syscall.c:bpf_charge_memlock
```
```
In kernel/events/core.c (ffffffff81217f15)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
```
```
In mm/filemap.c (ffffffff812269a7)
Location: include/linux/sched/signal.h:684
Inline: True
```
```
In mm/util.c (ffffffff8124ac19)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - mm/util.c:__account_locked_vm
  - mm/util.c:__account_locked_vm
```
```
In mm/mlock.c (ffffffff8126db73)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - mm/mlock.c:user_shm_lock
  - mm/mlock.c:__ia32_sys_mlockall
  - mm/mlock.c:__ia32_sys_mlockall
  - mm/mlock.c:__x64_sys_mlockall
  - mm/mlock.c:__x64_sys_mlockall
  - mm/mlock.c:do_mlock
  - mm/mlock.c:do_mlock
```
```
In mm/mmap.c (ffffffff812713e4)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:do_mmap
  - mm/mmap.c:__ia32_sys_brk
  - mm/mmap.c:__x64_sys_brk
```
```
In mm/mremap.c (ffffffff8127511f)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - mm/mremap.c:vma_to_resize
```
```
In fs/exec.c (ffffffff812ecb57)
Location: include/linux/sched/signal.h:684
Inline: True
```
```
In fs/select.c (ffffffff812fd26b)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
```
```
In fs/attr.c (ffffffff81306104)
Location: include/linux/sched/signal.h:684
Inline: True
```
```
In fs/file.c (ffffffff8130807c)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - fs/file.c:f_dupfd
  - fs/file.c:f_dupfd
  - fs/file.c:ksys_dup3
  - fs/file.c:replace_fd
  - fs/file.c:get_unused_fd_flags
```
```
In fs/io_uring.c (ffffffff8134ee09)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_sqe_buffer_register
```
```
In fs/coredump.c (ffffffff8136b404)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/array.c (ffffffff8138383a)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - fs/proc/array.c:proc_pid_status
```
```
In ipc/shm.c (ffffffff8144a2d7)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - ipc/shm.c:shmctl_do_lock
```
```
In ipc/mqueue.c (ffffffff8144c96f)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - ipc/mqueue.c:mqueue_get_inode
```
```
In security/selinux/hooks.c (ffffffff8146ea7c)
Location: include/linux/sched/signal.h:684
Inline: True
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff817e429e)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_map
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages
```
```
In net/core/skbuff.c (ffffffff8192b1ad)
Location: include/linux/sched/signal.h:684
Inline: True
```
```
In net/unix/scm.c (ffffffff81a4a70f)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - net/unix/scm.c:unix_attach_fds
```
```
In net/xdp/xdp_umem.c (ffffffff81ac4154)
Location: include/linux/sched/signal.h:684
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_create
```
</details>
</li>
</ul>

## Differences
