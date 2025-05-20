# Function: <code>rlimit</code>

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
Location: include/linux/sched.h:3185
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:arch_pick_mmap_layout
  - arch/x86/mm/mmap.c:arch_pick_mmap_layout
```
```
In kernel/sys.c (ffffffff81092ef9)
Location: include/linux/sched.h:3185
Inline: True
```
```
In kernel/bpf/syscall.c (ffffffff811730ec)
Location: include/linux/sched.h:3185
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:SyS_bpf
```
```
In kernel/events/core.c (ffffffff81181442)
Location: include/linux/sched.h:3185
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
```
```
In mm/filemap.c (ffffffff8118d730)
Location: include/linux/sched.h:3185
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_write_iter
```
```
In mm/mlock.c (ffffffff811c2c55)
Location: include/linux/sched.h:3185
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
Location: include/linux/sched.h:3185
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
Location: include/linux/sched.h:3185
Inline: True
Inline callers:
  - mm/mremap.c:vma_to_resize
```
```
In fs/exec.c (ffffffff8121253d)
Location: include/linux/sched.h:3185
Inline: True
Inline callers:
  - fs/exec.c:setup_arg_pages
```
```
In fs/select.c (ffffffff81221e93)
Location: include/linux/sched.h:3185
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
```
```
In fs/attr.c (ffffffff812292fb)
Location: include/linux/sched.h:3185
Inline: True
```
```
In fs/file.c (ffffffff8122a88a)
Location: include/linux/sched.h:3185
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
Location: include/linux/sched.h:3185
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
```
```
In ipc/shm.c (ffffffff8132b29d)
Location: include/linux/sched.h:3185
Inline: True
Inline callers:
  - ipc/shm.c:SyS_shmctl
```
```
In ipc/mqueue.c (ffffffff8132c712)
Location: include/linux/sched.h:3185
Inline: True
Inline callers:
  - ipc/mqueue.c:mqueue_get_inode
```
```
In security/selinux/hooks.c (ffffffff81346b7a)
Location: include/linux/sched.h:3185
Inline: True
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
Location: include/linux/sched.h:3462
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:arch_pick_mmap_layout
  - arch/x86/mm/mmap.c:arch_pick_mmap_layout
```
```
In kernel/sys.c (ffffffff81096089)
Location: include/linux/sched.h:3462
Inline: True
```
```
In kernel/bpf/syscall.c (ffffffff81181aa4)
Location: include/linux/sched.h:3462
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_map_precharge_memlock
```
```
In kernel/events/core.c (ffffffff81193213)
Location: include/linux/sched.h:3462
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
```
```
In mm/filemap.c (ffffffff811a29e2)
Location: include/linux/sched.h:3462
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_write_iter
```
```
In mm/mlock.c (ffffffff811dfbd6)
Location: include/linux/sched.h:3462
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
Location: include/linux/sched.h:3462
Inline: True
Inline callers:
  - mm/mmap.c:do_brk
  - mm/mmap.c:do_mmap
  - mm/mmap.c:SyS_brk
```
```
In mm/mremap.c (ffffffff811e55f2)
Location: include/linux/sched.h:3462
Inline: True
Inline callers:
  - mm/mremap.c:vma_to_resize
```
```
In fs/exec.c (ffffffff81239018)
Location: include/linux/sched.h:3462
Inline: True
Inline callers:
  - fs/exec.c:setup_arg_pages
```
```
In fs/select.c (ffffffff81249b64)
Location: include/linux/sched.h:3462
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
```
```
In fs/attr.c (ffffffff81251a2b)
Location: include/linux/sched.h:3462
Inline: True
```
```
In fs/file.c (ffffffff81253764)
Location: include/linux/sched.h:3462
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
Location: include/linux/sched.h:3462
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
```
```
In ipc/shm.c (ffffffff8135fef1)
Location: include/linux/sched.h:3462
Inline: True
Inline callers:
  - ipc/shm.c:SyS_shmctl
```
```
In ipc/mqueue.c (ffffffff81361376)
Location: include/linux/sched.h:3462
Inline: True
Inline callers:
  - ipc/mqueue.c:mqueue_get_inode
```
```
In security/selinux/hooks.c (ffffffff8137c345)
Location: include/linux/sched.h:3462
Inline: True
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
Location: include/linux/sched.h:3647
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:arch_pick_mmap_layout
  - arch/x86/mm/mmap.c:arch_pick_mmap_layout
```
```
In kernel/sys.c (ffffffff8109b059)
Location: include/linux/sched.h:3647
Inline: True
```
```
In kernel/bpf/syscall.c (ffffffff8118dccb)
Location: include/linux/sched.h:3647
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:__bpf_prog_charge
  - kernel/bpf/syscall.c:bpf_map_precharge_memlock
```
```
In kernel/events/core.c (ffffffff811a29f4)
Location: include/linux/sched.h:3647
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
```
```
In mm/filemap.c (ffffffff811b2822)
Location: include/linux/sched.h:3647
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_write_iter
```
```
In mm/mlock.c (ffffffff811efb26)
Location: include/linux/sched.h:3647
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
Location: include/linux/sched.h:3647
Inline: True
Inline callers:
  - mm/mmap.c:do_brk
  - mm/mmap.c:do_mmap
  - mm/mmap.c:SyS_brk
```
```
In mm/mremap.c (ffffffff811f5812)
Location: include/linux/sched.h:3647
Inline: True
Inline callers:
  - mm/mremap.c:vma_to_resize
```
```
In fs/exec.c (ffffffff8124bcc8)
Location: include/linux/sched.h:3647
Inline: True
Inline callers:
  - fs/exec.c:setup_arg_pages
```
```
In fs/select.c (ffffffff8125cb34)
Location: include/linux/sched.h:3647
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
```
```
In fs/attr.c (ffffffff81264bfb)
Location: include/linux/sched.h:3647
Inline: True
```
```
In fs/file.c (ffffffff812669b4)
Location: include/linux/sched.h:3647
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
Location: include/linux/sched.h:3647
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
```
```
In ipc/shm.c (ffffffff813766f1)
Location: include/linux/sched.h:3647
Inline: True
Inline callers:
  - ipc/shm.c:SyS_shmctl
```
```
In ipc/mqueue.c (ffffffff81377b71)
Location: include/linux/sched.h:3647
Inline: True
Inline callers:
  - ipc/mqueue.c:mqueue_get_inode
```
```
In security/selinux/hooks.c (ffffffff81392e01)
Location: include/linux/sched.h:3647
Inline: True
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
Location: include/linux/sched/signal.h:602
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:arch_pick_mmap_base
```
```
In kernel/sys.c (ffffffff81097e59)
Location: include/linux/sched/signal.h:602
Inline: True
```
```
In kernel/bpf/syscall.c (ffffffff81192ab2)
Location: include/linux/sched/signal.h:602
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:__bpf_prog_charge
  - kernel/bpf/syscall.c:bpf_map_precharge_memlock
```
```
In kernel/events/core.c (ffffffff811aa065)
Location: include/linux/sched/signal.h:602
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
```
```
In mm/filemap.c (ffffffff811b9492)
Location: include/linux/sched/signal.h:602
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_write_iter
```
```
In mm/mlock.c (ffffffff811faa46)
Location: include/linux/sched/signal.h:602
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
Location: include/linux/sched/signal.h:602
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
Location: include/linux/sched/signal.h:602
Inline: True
Inline callers:
  - mm/mremap.c:vma_to_resize
```
```
In fs/exec.c (ffffffff81257de5)
Location: include/linux/sched/signal.h:602
Inline: True
Inline callers:
  - fs/exec.c:setup_arg_pages
```
```
In fs/select.c (ffffffff812696f7)
Location: include/linux/sched/signal.h:602
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
```
```
In fs/attr.c (ffffffff8127242b)
Location: include/linux/sched/signal.h:602
Inline: True
```
```
In fs/file.c (ffffffff812741af)
Location: include/linux/sched/signal.h:602
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
Location: include/linux/sched/signal.h:602
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
```
```
In ipc/shm.c (ffffffff8138a2f1)
Location: include/linux/sched/signal.h:602
Inline: True
Inline callers:
  - ipc/shm.c:SyS_shmctl
```
```
In ipc/mqueue.c (ffffffff8138b6fc)
Location: include/linux/sched/signal.h:602
Inline: True
Inline callers:
  - ipc/mqueue.c:mqueue_get_inode
```
```
In security/selinux/hooks.c (ffffffff813a8fdd)
Location: include/linux/sched/signal.h:602
Inline: True
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
Location: include/linux/sched/signal.h:603
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:arch_pick_mmap_base
```
```
In kernel/sys.c (ffffffff8109eb49)
Location: include/linux/sched/signal.h:603
Inline: True
```
```
In kernel/bpf/syscall.c (ffffffff811a0d6e)
Location: include/linux/sched/signal.h:603
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:__bpf_prog_charge
  - kernel/bpf/syscall.c:bpf_map_precharge_memlock
```
```
In kernel/events/core.c (ffffffff811bd958)
Location: include/linux/sched/signal.h:603
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
```
```
In mm/filemap.c (ffffffff811cf912)
Location: include/linux/sched/signal.h:603
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_write_iter
```
```
In mm/mlock.c (ffffffff81212f56)
Location: include/linux/sched/signal.h:603
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
Location: include/linux/sched/signal.h:603
Inline: True
Inline callers:
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:do_mmap
  - mm/mmap.c:SyS_brk
```
```
In mm/mremap.c (ffffffff81218dc8)
Location: include/linux/sched/signal.h:603
Inline: True
Inline callers:
  - mm/mremap.c:vma_to_resize
```
```
In fs/exec.c (ffffffff8127a0b5)
Location: include/linux/sched/signal.h:603
Inline: True
Inline callers:
  - fs/exec.c:setup_arg_pages
```
```
In fs/select.c (ffffffff8128bfa7)
Location: include/linux/sched/signal.h:603
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
```
```
In fs/attr.c (ffffffff81294d4c)
Location: include/linux/sched/signal.h:603
Inline: True
```
```
In fs/file.c (ffffffff81296aaf)
Location: include/linux/sched/signal.h:603
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
Location: include/linux/sched/signal.h:603
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
```
```
In ipc/shm.c (ffffffff813ae4aa)
Location: include/linux/sched/signal.h:603
Inline: True
Inline callers:
  - ipc/shm.c:shmctl_do_lock
```
```
In ipc/mqueue.c (ffffffff813b0a8c)
Location: include/linux/sched/signal.h:603
Inline: True
Inline callers:
  - ipc/mqueue.c:mqueue_get_inode
```
```
In security/selinux/hooks.c (ffffffff813cef14)
Location: include/linux/sched/signal.h:603
Inline: True
```
```
In net/core/skbuff.c (ffffffff8183115a)
Location: include/linux/sched/signal.h:603
Inline: True
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
In kernel/sys.c (ffffffff810a4440)
Location: include/linux/sched/signal.h:631
Inline: True
```
```
In kernel/bpf/syscall.c (ffffffff811b5a75)
Location: include/linux/sched/signal.h:631
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_prog_charge
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:bpf_map_precharge_memlock
```
```
In kernel/events/core.c (ffffffff811ddbc3)
Location: include/linux/sched/signal.h:631
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
```
```
In mm/filemap.c (ffffffff811f0a42)
Location: include/linux/sched/signal.h:631
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_write_iter
```
```
In mm/mlock.c (ffffffff81233f13)
Location: include/linux/sched/signal.h:631
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
Location: include/linux/sched/signal.h:631
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
Location: include/linux/sched/signal.h:631
Inline: True
Inline callers:
  - mm/mremap.c:vma_to_resize
```
```
In fs/exec.c (ffffffff812a2967)
Location: include/linux/sched/signal.h:631
Inline: True
```
```
In fs/select.c (ffffffff812b2792)
Location: include/linux/sched/signal.h:631
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
```
```
In fs/attr.c (ffffffff812baf0b)
Location: include/linux/sched/signal.h:631
Inline: True
```
```
In fs/file.c (ffffffff812bcc45)
Location: include/linux/sched/signal.h:631
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
Location: include/linux/sched/signal.h:631
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
```
```
In ipc/shm.c (ffffffff813dea1d)
Location: include/linux/sched/signal.h:631
Inline: True
Inline callers:
  - ipc/shm.c:shmctl_do_lock
```
```
In ipc/mqueue.c (ffffffff813e315a)
Location: include/linux/sched/signal.h:631
Inline: True
Inline callers:
  - ipc/mqueue.c:mqueue_get_inode
```
```
In security/selinux/hooks.c (ffffffff81402547)
Location: include/linux/sched/signal.h:631
Inline: True
```
```
In net/core/skbuff.c (ffffffff8187b60d)
Location: include/linux/sched/signal.h:631
Inline: True
```
```
In net/xdp/xdp_umem.c (ffffffff819cd109)
Location: include/linux/sched/signal.h:631
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
In kernel/sys.c (ffffffff810ad2a0)
Location: include/linux/sched/signal.h:673
Inline: True
```
```
In kernel/bpf/syscall.c (ffffffff811c3695)
Location: include/linux/sched/signal.h:673
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_prog_charge
  - kernel/bpf/syscall.c:bpf_charge_memlock
  - kernel/bpf/syscall.c:bpf_map_precharge_memlock
```
```
In kernel/events/core.c (ffffffff811edfc3)
Location: include/linux/sched/signal.h:673
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
```
```
In mm/filemap.c (ffffffff811fc585)
Location: include/linux/sched/signal.h:673
Inline: True
```
```
In mm/mlock.c (ffffffff812476c3)
Location: include/linux/sched/signal.h:673
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
Location: include/linux/sched/signal.h:673
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
Location: include/linux/sched/signal.h:673
Inline: True
Inline callers:
  - mm/mremap.c:vma_to_resize
```
```
In fs/exec.c (ffffffff812b77d6)
Location: include/linux/sched/signal.h:673
Inline: True
```
```
In fs/select.c (ffffffff812c78a2)
Location: include/linux/sched/signal.h:673
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
```
```
In fs/attr.c (ffffffff812d00fb)
Location: include/linux/sched/signal.h:673
Inline: True
```
```
In fs/file.c (ffffffff812d1f05)
Location: include/linux/sched/signal.h:673
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
Location: include/linux/sched/signal.h:673
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
```
```
In ipc/shm.c (ffffffff813f911d)
Location: include/linux/sched/signal.h:673
Inline: True
Inline callers:
  - ipc/shm.c:shmctl_do_lock
```
```
In ipc/mqueue.c (ffffffff813fd93a)
Location: include/linux/sched/signal.h:673
Inline: True
Inline callers:
  - ipc/mqueue.c:mqueue_get_inode
```
```
In security/selinux/hooks.c (ffffffff8141adc2)
Location: include/linux/sched/signal.h:673
Inline: True
```
```
In net/core/skbuff.c (ffffffff8189c44d)
Location: include/linux/sched/signal.h:673
Inline: True
```
```
In net/xdp/xdp_umem.c (ffffffff81a06464)
Location: include/linux/sched/signal.h:673
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
In kernel/sys.c (ffffffff810b2ae0)
Location: include/linux/sched/signal.h:704
Inline: True
```
```
In kernel/bpf/syscall.c (ffffffff811d4de5)
Location: include/linux/sched/signal.h:704
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_prog_charge
  - kernel/bpf/syscall.c:bpf_charge_memlock
```
```
In kernel/events/core.c (ffffffff812059f8)
Location: include/linux/sched/signal.h:704
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
```
```
In mm/filemap.c (ffffffff81213cf7)
Location: include/linux/sched/signal.h:704
Inline: True
```
```
In mm/mlock.c (ffffffff812598d3)
Location: include/linux/sched/signal.h:704
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
Location: include/linux/sched/signal.h:704
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
Location: include/linux/sched/signal.h:704
Inline: True
Inline callers:
  - mm/mremap.c:vma_to_resize
```
```
In fs/exec.c (ffffffff812d3e57)
Location: include/linux/sched/signal.h:704
Inline: True
```
```
In fs/select.c (ffffffff812e4432)
Location: include/linux/sched/signal.h:704
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
```
```
In fs/attr.c (ffffffff812ed11b)
Location: include/linux/sched/signal.h:704
Inline: True
```
```
In fs/file.c (ffffffff812eef45)
Location: include/linux/sched/signal.h:704
Inline: True
Inline callers:
  - fs/file.c:f_dupfd
  - fs/file.c:f_dupfd
  - fs/file.c:ksys_dup3
  - fs/file.c:replace_fd
  - fs/file.c:get_unused_fd_flags
```
```
In fs/io_uring.c (ffffffff81330ed4)
Location: include/linux/sched/signal.h:704
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_sqe_buffer_register
```
```
In fs/coredump.c (ffffffff813499d4)
Location: include/linux/sched/signal.h:704
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In ipc/shm.c (ffffffff8142569d)
Location: include/linux/sched/signal.h:704
Inline: True
Inline callers:
  - ipc/shm.c:shmctl_do_lock
```
```
In ipc/mqueue.c (ffffffff81429f8d)
Location: include/linux/sched/signal.h:704
Inline: True
Inline callers:
  - ipc/mqueue.c:mqueue_get_inode
```
```
In security/selinux/hooks.c (ffffffff814488ab)
Location: include/linux/sched/signal.h:704
Inline: True
```
```
In net/core/skbuff.c (ffffffff818e6ccd)
Location: include/linux/sched/signal.h:704
Inline: True
```
```
In net/xdp/xdp_umem.c (ffffffff81a75d88)
Location: include/linux/sched/signal.h:704
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
In kernel/sys.c (ffffffff810b90d0)
Location: include/linux/sched/signal.h:696
Inline: True
```
```
In kernel/bpf/syscall.c (ffffffff811e14f5)
Location: include/linux/sched/signal.h:696
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_prog_charge
  - kernel/bpf/syscall.c:bpf_charge_memlock
```
```
In kernel/events/core.c (ffffffff81212d8c)
Location: include/linux/sched/signal.h:696
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
```
```
In mm/filemap.c (ffffffff812214f7)
Location: include/linux/sched/signal.h:696
Inline: True
```
```
In mm/mlock.c (ffffffff81267da3)
Location: include/linux/sched/signal.h:696
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
Location: include/linux/sched/signal.h:696
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
Location: include/linux/sched/signal.h:696
Inline: True
Inline callers:
  - mm/mremap.c:vma_to_resize
```
```
In fs/exec.c (ffffffff812e59e7)
Location: include/linux/sched/signal.h:696
Inline: True
```
```
In fs/select.c (ffffffff812f5e72)
Location: include/linux/sched/signal.h:696
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
```
```
In fs/attr.c (ffffffff812feb7b)
Location: include/linux/sched/signal.h:696
Inline: True
```
```
In fs/file.c (ffffffff81300a05)
Location: include/linux/sched/signal.h:696
Inline: True
Inline callers:
  - fs/file.c:f_dupfd
  - fs/file.c:f_dupfd
  - fs/file.c:ksys_dup3
  - fs/file.c:replace_fd
  - fs/file.c:get_unused_fd_flags
```
```
In fs/io_uring.c (ffffffff81344f6a)
Location: include/linux/sched/signal.h:696
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_sqe_buffer_register
```
```
In fs/coredump.c (ffffffff81361c74)
Location: include/linux/sched/signal.h:696
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In ipc/shm.c (ffffffff8143f3ed)
Location: include/linux/sched/signal.h:696
Inline: True
Inline callers:
  - ipc/shm.c:shmctl_do_lock
```
```
In ipc/mqueue.c (ffffffff81443cbd)
Location: include/linux/sched/signal.h:696
Inline: True
Inline callers:
  - ipc/mqueue.c:mqueue_get_inode
```
```
In security/selinux/hooks.c (ffffffff8146243b)
Location: include/linux/sched/signal.h:696
Inline: True
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff817d5175)
Location: include/linux/sched/signal.h:696
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_map
```
```
In net/core/skbuff.c (ffffffff819190ad)
Location: include/linux/sched/signal.h:696
Inline: True
```
```
In net/xdp/xdp_umem.c (ffffffff81aacaeb)
Location: include/linux/sched/signal.h:696
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
In kernel/sys.c (ffffffff810c0e4f)
Location: include/linux/sched/signal.h:708
Inline: True
Inline callers:
  - kernel/sys.c:validate_prctl_map_addr
  - kernel/sys.c:set_user
```
```
In kernel/bpf/syscall.c (ffffffff811ffc55)
Location: include/linux/sched/signal.h:708
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_prog_charge
  - kernel/bpf/syscall.c:bpf_map_charge_memlock
```
```
In kernel/events/core.c (ffffffff8123ee00)
Location: include/linux/sched/signal.h:708
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
```
```
In mm/filemap.c (ffffffff8124e18e)
Location: include/linux/sched/signal.h:708
Inline: True
Inline callers:
  - mm/filemap.c:generic_write_check_limits
```
```
In mm/mlock.c (ffffffff81297db3)
Location: include/linux/sched/signal.h:708
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
Location: include/linux/sched/signal.h:708
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
Location: include/linux/sched/signal.h:708
Inline: True
Inline callers:
  - mm/mremap.c:vma_to_resize
```
```
In fs/exec.c (ffffffff8131d4d5)
Location: include/linux/sched/signal.h:708
Inline: True
Inline callers:
  - fs/exec.c:__do_execve_file
```
```
In fs/select.c (ffffffff8132ef89)
Location: include/linux/sched/signal.h:708
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
```
```
In fs/attr.c (ffffffff81337c7b)
Location: include/linux/sched/signal.h:708
Inline: True
```
```
In fs/file.c (ffffffff81339c45)
Location: include/linux/sched/signal.h:708
Inline: True
Inline callers:
  - fs/file.c:f_dupfd
  - fs/file.c:f_dupfd
  - fs/file.c:ksys_dup
  - fs/file.c:ksys_dup3
  - fs/file.c:replace_fd
```
```
In fs/io_uring.c (ffffffff813857e4)
Location: include/linux/sched/signal.h:708
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_issue_sqe
  - fs/io_uring.c:io_accept_prep
  - fs/io_uring.c:__io_openat_prep
```
```
In fs/coredump.c (ffffffff813a7f03)
Location: include/linux/sched/signal.h:708
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
  - fs/coredump.c:format_corename
```
```
In ipc/shm.c (ffffffff8148ff5d)
Location: include/linux/sched/signal.h:708
Inline: True
Inline callers:
  - ipc/shm.c:shmctl_do_lock
```
```
In ipc/mqueue.c (ffffffff81494991)
Location: include/linux/sched/signal.h:708
Inline: True
Inline callers:
  - ipc/mqueue.c:mqueue_get_inode
```
```
In security/selinux/hooks.c (ffffffff814b637b)
Location: include/linux/sched/signal.h:708
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committing_creds
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff8189fe49)
Location: include/linux/sched/signal.h:708
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_replay
  - drivers/vfio/vfio_iommu_type1.c:vfio_pin_map_dma
```
```
In net/socket.c (ffffffff819e1263)
Location: include/linux/sched/signal.h:708
Inline: True
Inline callers:
  - net/socket.c:__sys_accept4
```
```
In net/core/skbuff.c (ffffffff819ecd11)
Location: include/linux/sched/signal.h:708
Inline: True
```
```
In net/xdp/xdp_umem.c (ffffffff81ba851f)
Location: include/linux/sched/signal.h:708
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
In kernel/sys.c (ffffffff810bbfaf)
Location: include/linux/sched/signal.h:723
Inline: True
Inline callers:
  - kernel/sys.c:validate_prctl_map_addr
  - kernel/sys.c:set_user
```
```
In kernel/events/core.c (ffffffff812491f0)
Location: include/linux/sched/signal.h:723
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
```
```
In mm/mlock.c (ffffffff812a2f03)
Location: include/linux/sched/signal.h:723
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
Location: include/linux/sched/signal.h:723
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
Location: include/linux/sched/signal.h:723
Inline: True
Inline callers:
  - mm/mremap.c:vma_to_resize
```
```
In fs/read_write.c (ffffffff813205ae)
Location: include/linux/sched/signal.h:723
Inline: True
Inline callers:
  - fs/read_write.c:generic_write_check_limits
```
```
In fs/exec.c (ffffffff81328c5b)
Location: include/linux/sched/signal.h:723
Inline: True
Inline callers:
  - fs/exec.c:do_execveat_common
```
```
In fs/select.c (ffffffff8133a869)
Location: include/linux/sched/signal.h:723
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
```
```
In fs/attr.c (ffffffff813435db)
Location: include/linux/sched/signal.h:723
Inline: True
```
```
In fs/file.c (ffffffff813459a5)
Location: include/linux/sched/signal.h:723
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
In fs/io_uring.c (ffffffff81396818)
Location: include/linux/sched/signal.h:723
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
In fs/coredump.c (ffffffff813b8f83)
Location: include/linux/sched/signal.h:723
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
  - fs/coredump.c:format_corename
```
```
In ipc/shm.c (ffffffff814ad677)
Location: include/linux/sched/signal.h:723
Inline: True
Inline callers:
  - ipc/shm.c:shmctl_do_lock
```
```
In ipc/mqueue.c (ffffffff814b22f1)
Location: include/linux/sched/signal.h:723
Inline: True
Inline callers:
  - ipc/mqueue.c:mqueue_get_inode
```
```
In security/selinux/hooks.c (ffffffff814d405b)
Location: include/linux/sched/signal.h:723
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committing_creds
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff818af7d9)
Location: include/linux/sched/signal.h:723
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_replay
  - drivers/vfio/vfio_iommu_type1.c:vfio_pin_map_dma
```
```
In net/socket.c (ffffffff819e0ab0)
Location: include/linux/sched/signal.h:723
Inline: True
Inline callers:
  - net/socket.c:__sys_accept4
```
```
In net/core/skbuff.c (ffffffff819ec9d1)
Location: include/linux/sched/signal.h:723
Inline: True
```
```
In net/xdp/xdp_umem.c (ffffffff81bb8283)
Location: include/linux/sched/signal.h:723
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
In kernel/sys.c (ffffffff810bd855)
Location: include/linux/sched/signal.h:729
Inline: True
Inline callers:
  - kernel/sys.c:validate_prctl_map_addr
  - kernel/sys.c:set_user
```
```
In kernel/events/core.c (ffffffff8124d3c0)
Location: include/linux/sched/signal.h:729
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
```
```
In mm/mlock.c (ffffffff812a8763)
Location: include/linux/sched/signal.h:729
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
Location: include/linux/sched/signal.h:729
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
Location: include/linux/sched/signal.h:729
Inline: True
Inline callers:
  - mm/mremap.c:vma_to_resize
```
```
In fs/read_write.c (ffffffff813266e4)
Location: include/linux/sched/signal.h:729
Inline: True
Inline callers:
  - fs/read_write.c:generic_write_check_limits
```
```
In fs/exec.c (ffffffff8132eaa6)
Location: include/linux/sched/signal.h:729
Inline: True
```
```
In fs/select.c (ffffffff81340d6d)
Location: include/linux/sched/signal.h:729
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
```
```
In fs/attr.c (ffffffff813498db)
Location: include/linux/sched/signal.h:729
Inline: True
```
```
In fs/file.c (ffffffff8134bd65)
Location: include/linux/sched/signal.h:729
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
In fs/io_uring.c (ffffffff8139181d)
Location: include/linux/sched/signal.h:729
Inline: True
Inline callers:
  - fs/io_uring.c:io_buffer_account_pin
  - fs/io_uring.c:io_req_prep
  - fs/io_uring.c:__io_openat_prep
```
```
In fs/coredump.c (ffffffff813bfee4)
Location: include/linux/sched/signal.h:729
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In ipc/shm.c (ffffffff814b34f7)
Location: include/linux/sched/signal.h:729
Inline: True
Inline callers:
  - ipc/shm.c:shmctl_do_lock
```
```
In ipc/mqueue.c (ffffffff814b8163)
Location: include/linux/sched/signal.h:729
Inline: True
Inline callers:
  - ipc/mqueue.c:mqueue_get_inode
```
```
In security/selinux/hooks.c (ffffffff814da607)
Location: include/linux/sched/signal.h:729
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committing_creds
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff818921d2)
Location: include/linux/sched/signal.h:729
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_replay
  - drivers/vfio/vfio_iommu_type1.c:vfio_pin_map_dma
```
```
In net/socket.c (ffffffff819c6b00)
Location: include/linux/sched/signal.h:729
Inline: True
Inline callers:
  - net/socket.c:__sys_accept4
```
```
In net/core/skbuff.c (ffffffff819d2eb1)
Location: include/linux/sched/signal.h:729
Inline: True
```
```
In net/xdp/xdp_umem.c (ffffffff81ba7445)
Location: include/linux/sched/signal.h:729
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
In kernel/fork.c (ffffffff810b3edd)
Location: include/linux/sched/signal.h:733
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/sys.c (ffffffff810d0262)
Location: include/linux/sched/signal.h:733
Inline: True
Inline callers:
  - kernel/sys.c:validate_prctl_map_addr
  - kernel/sys.c:flag_nproc_exceeded
```
```
In kernel/acct.c (ffffffff8118c128)
Location: include/linux/sched/signal.h:733
Inline: True
Inline callers:
  - kernel/acct.c:do_acct_process
```
```
In kernel/user_namespace.c (ffffffff811aaa2d)
Location: include/linux/sched/signal.h:733
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
  - kernel/user_namespace.c:create_user_ns
  - kernel/user_namespace.c:create_user_ns
  - kernel/user_namespace.c:create_user_ns
```
```
In kernel/events/core.c (ffffffff81286fd0)
Location: include/linux/sched/signal.h:733
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
```
```
In mm/mlock.c (ffffffff812e9d65)
Location: include/linux/sched/signal.h:733
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
Location: include/linux/sched/signal.h:733
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
Location: include/linux/sched/signal.h:733
Inline: True
Inline callers:
  - mm/mremap.c:vma_to_resize
```
```
In fs/read_write.c (ffffffff81373c84)
Location: include/linux/sched/signal.h:733
Inline: True
Inline callers:
  - fs/read_write.c:generic_write_check_limits
```
```
In fs/exec.c (ffffffff8137c3c5)
Location: include/linux/sched/signal.h:733
Inline: True
```
```
In fs/select.c (ffffffff8138e72d)
Location: include/linux/sched/signal.h:733
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
```
```
In fs/attr.c (ffffffff8139762b)
Location: include/linux/sched/signal.h:733
Inline: True
```
```
In fs/file.c (ffffffff81399ba5)
Location: include/linux/sched/signal.h:733
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
In fs/io_uring.c (ffffffff813df726)
Location: include/linux/sched/signal.h:733
Inline: True
Inline callers:
  - fs/io_uring.c:io_buffer_account_pin
  - fs/io_uring.c:io_sqe_files_register
  - fs/io_uring.c:io_req_prep
```
```
In fs/coredump.c (ffffffff8140fd14)
Location: include/linux/sched/signal.h:733
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In ipc/shm.c (ffffffff8150bb75)
Location: include/linux/sched/signal.h:733
Inline: True
Inline callers:
  - ipc/shm.c:shmctl_do_lock
```
```
In ipc/mqueue.c (ffffffff815109a2)
Location: include/linux/sched/signal.h:733
Inline: True
Inline callers:
  - ipc/mqueue.c:mqueue_get_inode
```
```
In security/selinux/hooks.c (ffffffff81533507)
Location: include/linux/sched/signal.h:733
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committing_creds
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff81926692)
Location: include/linux/sched/signal.h:733
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_replay
  - drivers/vfio/vfio_iommu_type1.c:vfio_pin_map_dma
```
```
In net/socket.c (ffffffff81a75e50)
Location: include/linux/sched/signal.h:733
Inline: True
Inline callers:
  - net/socket.c:__sys_accept4
```
```
In net/core/skbuff.c (ffffffff81a82b91)
Location: include/linux/sched/signal.h:733
Inline: True
```
```
In net/xdp/xdp_umem.c (ffffffff81c7505f)
Location: include/linux/sched/signal.h:733
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
In kernel/fork.c (ffffffff810ca1ea)
Location: include/linux/sched/signal.h:773
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/sys.c (ffffffff810e6c59)
Location: include/linux/sched/signal.h:773
Inline: True
Inline callers:
  - kernel/sys.c:validate_prctl_map_addr
  - kernel/sys.c:flag_nproc_exceeded
```
```
In kernel/acct.c (ffffffff811bb507)
Location: include/linux/sched/signal.h:773
Inline: True
Inline callers:
  - kernel/acct.c:do_acct_process
```
```
In kernel/user_namespace.c (ffffffff811dc081)
Location: include/linux/sched/signal.h:773
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
  - kernel/user_namespace.c:create_user_ns
  - kernel/user_namespace.c:create_user_ns
  - kernel/user_namespace.c:create_user_ns
```
```
In kernel/events/core.c (ffffffff812db8d0)
Location: include/linux/sched/signal.h:773
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
```
```
In mm/mlock.c (ffffffff8134c8e3)
Location: include/linux/sched/signal.h:773
Inline: True
Inline callers:
  - mm/mlock.c:user_shm_lock
  - mm/mlock.c:__do_sys_mlockall
  - mm/mlock.c:__do_sys_mlockall
  - mm/mlock.c:do_mlock
  - mm/mlock.c:do_mlock
```
```
In mm/mmap.c (ffffffff81e6e4a8)
Location: include/linux/sched/signal.h:773
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
Location: include/linux/sched/signal.h:773
Inline: True
Inline callers:
  - fs/read_write.c:generic_write_check_limits
```
```
In fs/exec.c (ffffffff813fc738)
Location: include/linux/sched/signal.h:773
Inline: True
```
```
In fs/select.c (ffffffff8140fa0d)
Location: include/linux/sched/signal.h:773
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
```
```
In fs/attr.c (ffffffff81419820)
Location: include/linux/sched/signal.h:773
Inline: True
```
```
In fs/file.c (ffffffff8141c655)
Location: include/linux/sched/signal.h:773
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
Location: include/linux/sched/signal.h:773
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In ipc/shm.c (ffffffff8159d1ad)
Location: include/linux/sched/signal.h:773
Inline: True
Inline callers:
  - ipc/shm.c:shmctl_do_lock
```
```
In ipc/mqueue.c (ffffffff8159fc1d)
Location: include/linux/sched/signal.h:773
Inline: True
Inline callers:
  - ipc/mqueue.c:mqueue_get_inode
```
```
In security/selinux/hooks.c (ffffffff815c4daf)
Location: include/linux/sched/signal.h:773
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committing_creds
```
```
In io_uring/io_uring.c (ffffffff816cd3ae)
Location: include/linux/sched/signal.h:773
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_buffer_account_pin
  - io_uring/io_uring.c:io_sqe_files_register
  - io_uring/io_uring.c:io_socket_prep
  - io_uring/io_uring.c:io_accept_prep
  - io_uring/io_uring.c:__io_openat_prep
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff81a7b9ce)
Location: include/linux/sched/signal.h:773
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_replay
  - drivers/vfio/vfio_iommu_type1.c:vfio_pin_map_dma
```
```
In net/socket.c (ffffffff81be8e88)
Location: include/linux/sched/signal.h:773
Inline: True
Inline callers:
  - net/socket.c:__sys_accept4
```
```
In net/core/skbuff.c (ffffffff81bf78b3)
Location: include/linux/sched/signal.h:773
Inline: True
Inline callers:
  - net/core/skbuff.c:mm_account_pinned_pages
```
```
In net/xdp/xdp_umem.c (ffffffff81e19203)
Location: include/linux/sched/signal.h:773
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
In kernel/fork.c (ffffffff810e784b)
Location: include/linux/sched/signal.h:774
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/sys.c (ffffffff8110aac9)
Location: include/linux/sched/signal.h:774
Inline: True
Inline callers:
  - kernel/sys.c:validate_prctl_map_addr
  - kernel/sys.c:flag_nproc_exceeded
```
```
In kernel/acct.c (ffffffff811fd327)
Location: include/linux/sched/signal.h:774
Inline: True
Inline callers:
  - kernel/acct.c:do_acct_process
```
```
In kernel/user_namespace.c (ffffffff812218e9)
Location: include/linux/sched/signal.h:774
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
  - kernel/user_namespace.c:create_user_ns
  - kernel/user_namespace.c:create_user_ns
  - kernel/user_namespace.c:create_user_ns
```
```
In kernel/events/core.c (ffffffff81343b97)
Location: include/linux/sched/signal.h:774
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
```
```
In mm/mlock.c (ffffffff813c5453)
Location: include/linux/sched/signal.h:774
Inline: True
Inline callers:
  - mm/mlock.c:user_shm_lock
  - mm/mlock.c:__do_sys_mlockall
  - mm/mlock.c:__do_sys_mlockall
  - mm/mlock.c:do_mlock
  - mm/mlock.c:do_mlock
```
```
In mm/mmap.c (ffffffff813ca6fb)
Location: include/linux/sched/signal.h:774
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
Location: include/linux/sched/signal.h:774
Inline: True
Inline callers:
  - fs/read_write.c:generic_write_check_limits
```
```
In fs/exec.c (ffffffff814861e8)
Location: include/linux/sched/signal.h:774
Inline: True
```
```
In fs/select.c (ffffffff8149a64d)
Location: include/linux/sched/signal.h:774
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
```
```
In fs/attr.c (ffffffff814a52f0)
Location: include/linux/sched/signal.h:774
Inline: True
```
```
In fs/file.c (ffffffff814a8765)
Location: include/linux/sched/signal.h:774
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
Location: include/linux/sched/signal.h:774
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In ipc/shm.c (ffffffff8164669d)
Location: include/linux/sched/signal.h:774
Inline: True
Inline callers:
  - ipc/shm.c:shmctl_do_lock
```
```
In ipc/mqueue.c (ffffffff816494bd)
Location: include/linux/sched/signal.h:774
Inline: True
Inline callers:
  - ipc/mqueue.c:mqueue_get_inode
```
```
In security/selinux/hooks.c (ffffffff816718af)
Location: include/linux/sched/signal.h:774
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committing_creds
```
```
In io_uring/openclose.c (ffffffff81794548)
Location: include/linux/sched/signal.h:774
Inline: True
Inline callers:
  - io_uring/openclose.c:__io_openat_prep
```
```
In io_uring/net.c (ffffffff81798230)
Location: include/linux/sched/signal.h:774
Inline: True
Inline callers:
  - io_uring/net.c:io_socket_prep
  - io_uring/net.c:io_accept_prep
```
```
In io_uring/rsrc.c (ffffffff817a1d5a)
Location: include/linux/sched/signal.h:774
Inline: True
Inline callers:
  - io_uring/rsrc.c:io_sqe_files_register
  - io_uring/rsrc.c:__io_account_mem
```
```
In net/core/skbuff.c (ffffffff81da6623)
Location: include/linux/sched/signal.h:774
Inline: True
Inline callers:
  - net/core/skbuff.c:mm_account_pinned_pages
```
```
In net/xdp/xdp_umem.c (ffffffff81ff0459)
Location: include/linux/sched/signal.h:774
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
In kernel/fork.c (ffffffff810f33fc)
Location: include/linux/sched/signal.h:774
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/sys.c (ffffffff81116c89)
Location: include/linux/sched/signal.h:774
Inline: True
Inline callers:
  - kernel/sys.c:validate_prctl_map_addr
  - kernel/sys.c:flag_nproc_exceeded
```
```
In kernel/acct.c (ffffffff812124b7)
Location: include/linux/sched/signal.h:774
Inline: True
Inline callers:
  - kernel/acct.c:do_acct_process
```
```
In kernel/user_namespace.c (ffffffff81237d9e)
Location: include/linux/sched/signal.h:774
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
  - kernel/user_namespace.c:create_user_ns
  - kernel/user_namespace.c:create_user_ns
  - kernel/user_namespace.c:create_user_ns
```
```
In kernel/events/core.c (ffffffff81374c1d)
Location: include/linux/sched/signal.h:774
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
```
```
In mm/mlock.c (ffffffff813f9823)
Location: include/linux/sched/signal.h:774
Inline: True
Inline callers:
  - mm/mlock.c:user_shm_lock
  - mm/mlock.c:__do_sys_mlockall
  - mm/mlock.c:__do_sys_mlockall
  - mm/mlock.c:do_mlock
  - mm/mlock.c:do_mlock
```
```
In mm/mmap.c (ffffffff813feccb)
Location: include/linux/sched/signal.h:774
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
Location: include/linux/sched/signal.h:774
Inline: True
Inline callers:
  - fs/read_write.c:generic_write_check_limits
```
```
In fs/exec.c (ffffffff814bad53)
Location: include/linux/sched/signal.h:774
Inline: True
```
```
In fs/select.c (ffffffff814cf6fd)
Location: include/linux/sched/signal.h:774
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
```
```
In fs/attr.c (ffffffff814da720)
Location: include/linux/sched/signal.h:774
Inline: True
```
```
In fs/file.c (ffffffff814dd755)
Location: include/linux/sched/signal.h:774
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
Location: include/linux/sched/signal.h:774
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In ipc/shm.c (ffffffff8167ebb3)
Location: include/linux/sched/signal.h:774
Inline: True
Inline callers:
  - ipc/shm.c:shmctl_do_lock
```
```
In ipc/mqueue.c (ffffffff81681a1d)
Location: include/linux/sched/signal.h:774
Inline: True
Inline callers:
  - ipc/mqueue.c:mqueue_get_inode
```
```
In security/selinux/hooks.c (ffffffff816aa08b)
Location: include/linux/sched/signal.h:774
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committing_creds
```
```
In io_uring/openclose.c (ffffffff817d5200)
Location: include/linux/sched/signal.h:774
Inline: True
Inline callers:
  - io_uring/openclose.c:__io_openat_prep
```
```
In io_uring/net.c (ffffffff817d8fb0)
Location: include/linux/sched/signal.h:774
Inline: True
Inline callers:
  - io_uring/net.c:io_socket_prep
  - io_uring/net.c:io_accept_prep
```
```
In io_uring/rsrc.c (ffffffff817e2ebb)
Location: include/linux/sched/signal.h:774
Inline: True
Inline callers:
  - io_uring/rsrc.c:io_sqe_files_register
  - io_uring/rsrc.c:__io_account_mem
```
```
In net/core/skbuff.c (ffffffff81e15707)
Location: include/linux/sched/signal.h:774
Inline: True
Inline callers:
  - net/core/skbuff.c:mm_account_pinned_pages
```
```
In net/xdp/xdp_umem.c (ffffffff8206c607)
Location: include/linux/sched/signal.h:774
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
Location: include/linux/sched/signal.h:777
Inline: True
Inline callers:
  - arch/x86/kernel/shstk.c:shstk_alloc_thread_stack
  - arch/x86/kernel/shstk.c:shstk_setup
```
```
In kernel/fork.c (ffffffff810fc7ac)
Location: include/linux/sched/signal.h:777
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/sys.c (ffffffff81120679)
Location: include/linux/sched/signal.h:777
Inline: True
Inline callers:
  - kernel/sys.c:validate_prctl_map_addr
  - kernel/sys.c:flag_nproc_exceeded
```
```
In kernel/acct.c (ffffffff81229b37)
Location: include/linux/sched/signal.h:777
Inline: True
Inline callers:
  - kernel/acct.c:do_acct_process
```
```
In kernel/user_namespace.c (ffffffff8125189e)
Location: include/linux/sched/signal.h:777
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
  - kernel/user_namespace.c:create_user_ns
  - kernel/user_namespace.c:create_user_ns
  - kernel/user_namespace.c:create_user_ns
```
```
In kernel/events/core.c (ffffffff8139df4d)
Location: include/linux/sched/signal.h:777
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
```
```
In mm/mlock.c (ffffffff814255e3)
Location: include/linux/sched/signal.h:777
Inline: True
Inline callers:
  - mm/mlock.c:user_shm_lock
  - mm/mlock.c:__do_sys_mlockall
  - mm/mlock.c:__do_sys_mlockall
  - mm/mlock.c:do_mlock
  - mm/mlock.c:do_mlock
```
```
In mm/mmap.c (ffffffff8142b13b)
Location: include/linux/sched/signal.h:777
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
Location: include/linux/sched/signal.h:777
Inline: True
Inline callers:
  - fs/read_write.c:generic_write_check_limits
```
```
In fs/exec.c (ffffffff814ed2c7)
Location: include/linux/sched/signal.h:777
Inline: True
```
```
In fs/select.c (ffffffff8150203d)
Location: include/linux/sched/signal.h:777
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
```
```
In fs/attr.c (ffffffff8150ccc0)
Location: include/linux/sched/signal.h:777
Inline: True
```
```
In fs/file.c (ffffffff815101a5)
Location: include/linux/sched/signal.h:777
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
Location: include/linux/sched/signal.h:777
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In ipc/shm.c (ffffffff816bafa3)
Location: include/linux/sched/signal.h:777
Inline: True
Inline callers:
  - ipc/shm.c:shmctl_do_lock
```
```
In ipc/mqueue.c (ffffffff816bddfe)
Location: include/linux/sched/signal.h:777
Inline: True
Inline callers:
  - ipc/mqueue.c:mqueue_get_inode
```
```
In security/selinux/hooks.c (ffffffff816e689e)
Location: include/linux/sched/signal.h:777
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committing_creds
```
```
In io_uring/openclose.c (ffffffff81819050)
Location: include/linux/sched/signal.h:777
Inline: True
Inline callers:
  - io_uring/openclose.c:__io_openat_prep
```
```
In io_uring/net.c (ffffffff8181d2c0)
Location: include/linux/sched/signal.h:777
Inline: True
Inline callers:
  - io_uring/net.c:io_socket_prep
  - io_uring/net.c:io_accept_prep
```
```
In io_uring/rsrc.c (ffffffff81826f94)
Location: include/linux/sched/signal.h:777
Inline: True
Inline callers:
  - io_uring/rsrc.c:io_sqe_files_register
  - io_uring/rsrc.c:__io_account_mem
```
```
In net/core/skbuff.c (ffffffff81ed2aa7)
Location: include/linux/sched/signal.h:777
Inline: True
Inline callers:
  - net/core/skbuff.c:mm_account_pinned_pages
```
```
In net/xdp/xdp_umem.c (ffffffff82140405)
Location: include/linux/sched/signal.h:777
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
In kernel/sys.c (ffff8000101146ac)
Location: include/linux/sched/signal.h:696
Inline: True
```
```
In kernel/bpf/syscall.c (ffff80001026410c)
Location: include/linux/sched/signal.h:696
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_prog_charge
  - kernel/bpf/syscall.c:bpf_charge_memlock
```
```
In kernel/events/core.c (ffff80001029d0e8)
Location: include/linux/sched/signal.h:696
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
```
```
In mm/filemap.c (ffff8000102ae078)
Location: include/linux/sched/signal.h:696
Inline: True
```
```
In mm/mlock.c (ffff8000102fed30)
Location: include/linux/sched/signal.h:696
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
Location: include/linux/sched/signal.h:696
Inline: True
Inline callers:
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:do_mmap
  - mm/mmap.c:__arm64_sys_brk
```
```
In mm/mremap.c (ffff800010305cf4)
Location: include/linux/sched/signal.h:696
Inline: True
Inline callers:
  - mm/mremap.c:vma_to_resize
```
```
In fs/exec.c (ffff80001038dd78)
Location: include/linux/sched/signal.h:696
Inline: True
```
```
In fs/select.c (ffff8000103a2f88)
Location: include/linux/sched/signal.h:696
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
```
```
In fs/attr.c (ffff8000103b0068)
Location: include/linux/sched/signal.h:696
Inline: True
```
```
In fs/file.c (ffff8000103b29ac)
Location: include/linux/sched/signal.h:696
Inline: True
Inline callers:
  - fs/file.c:f_dupfd
  - fs/file.c:f_dupfd
  - fs/file.c:ksys_dup3
  - fs/file.c:replace_fd
  - fs/file.c:get_unused_fd_flags
```
```
In fs/io_uring.c (ffff800010401084)
Location: include/linux/sched/signal.h:696
Inline: True
Inline callers:
  - fs/io_uring.c:io_account_mem
```
```
In fs/coredump.c (ffff800010428374)
Location: include/linux/sched/signal.h:696
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In ipc/shm.c (ffff800010527824)
Location: include/linux/sched/signal.h:696
Inline: True
Inline callers:
  - ipc/shm.c:shmctl_do_lock
```
```
In ipc/mqueue.c (ffff800010529c38)
Location: include/linux/sched/signal.h:696
Inline: True
Inline callers:
  - ipc/mqueue.c:mqueue_get_inode
```
```
In security/selinux/hooks.c (ffff800010550170)
Location: include/linux/sched/signal.h:696
Inline: True
```
```
In net/core/skbuff.c (ffff800010bb2d30)
Location: include/linux/sched/signal.h:696
Inline: True
```
```
In net/xdp/xdp_umem.c (ffff800010d81364)
Location: include/linux/sched/signal.h:696
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
In kernel/sys.c (c036ac5c)
Location: include/linux/sched/signal.h:696
Inline: True
Inline callers:
  - kernel/sys.c:set_user
```
```
In kernel/bpf/syscall.c (c0496700)
Location: include/linux/sched/signal.h:696
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_prog_charge
  - kernel/bpf/syscall.c:bpf_charge_memlock
```
```
In kernel/events/core.c (c04cc8c4)
Location: include/linux/sched/signal.h:696
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
```
```
In mm/filemap.c (c04db4c8)
Location: include/linux/sched/signal.h:696
Inline: True
Inline callers:
  - mm/filemap.c:generic_write_check_limits
```
```
In mm/mlock.c (c051dd7c)
Location: include/linux/sched/signal.h:696
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
Location: include/linux/sched/signal.h:696
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
Location: include/linux/sched/signal.h:696
Inline: True
Inline callers:
  - mm/mremap.c:vma_to_resize
```
```
In fs/exec.c (c05756a0)
Location: include/linux/sched/signal.h:696
Inline: True
Inline callers:
  - fs/exec.c:__do_execve_file
```
```
In fs/select.c (c0585870)
Location: include/linux/sched/signal.h:696
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
```
```
In fs/attr.c (c058f894)
Location: include/linux/sched/signal.h:696
Inline: True
```
```
In fs/file.c (c0591c78)
Location: include/linux/sched/signal.h:696
Inline: True
Inline callers:
  - fs/file.c:f_dupfd
  - fs/file.c:f_dupfd
  - fs/file.c:ksys_dup3
  - fs/file.c:replace_fd
  - fs/file.c:get_unused_fd_flags
```
```
In fs/io_uring.c (c05d1e6c)
Location: include/linux/sched/signal.h:696
Inline: True
Inline callers:
  - fs/io_uring.c:io_account_mem
```
```
In fs/binfmt_flat.c (c05ec8b8)
Location: include/linux/sched/signal.h:696
Inline: True
Inline callers:
  - fs/binfmt_flat.c:load_flat_file
```
```
In fs/coredump.c (c05f0ffc)
Location: include/linux/sched/signal.h:696
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
  - fs/coredump.c:format_corename
```
```
In ipc/shm.c (c06e1618)
Location: include/linux/sched/signal.h:696
Inline: True
Inline callers:
  - ipc/shm.c:ksys_shmctl
```
```
In ipc/mqueue.c (c06e2900)
Location: include/linux/sched/signal.h:696
Inline: True
Inline callers:
  - ipc/mqueue.c:mqueue_get_inode
```
```
In security/selinux/hooks.c (c0706150)
Location: include/linux/sched/signal.h:696
Inline: True
```
```
In net/core/skbuff.c (c0ccf8c8)
Location: include/linux/sched/signal.h:696
Inline: True
```
```
In net/xdp/xdp_umem.c (c0e7b914)
Location: include/linux/sched/signal.h:696
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
In kernel/sys.c (c00000000015d418)
Location: include/linux/sched/signal.h:696
Inline: True
```
```
In kernel/bpf/syscall.c (c000000000308ff8)
Location: include/linux/sched/signal.h:696
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_prog_charge
  - kernel/bpf/syscall.c:bpf_map_charge_memlock
  - kernel/bpf/syscall.c:bpf_map_charge_init
```
```
In kernel/events/core.c (c00000000034da54)
Location: include/linux/sched/signal.h:696
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
```
```
In mm/filemap.c (c0000000003634c0)
Location: include/linux/sched/signal.h:696
Inline: True
```
```
In mm/mlock.c (c0000000003caa04)
Location: include/linux/sched/signal.h:696
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
Location: include/linux/sched/signal.h:696
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
Location: include/linux/sched/signal.h:696
Inline: True
Inline callers:
  - mm/mremap.c:vma_to_resize
```
```
In fs/exec.c (c000000000485fac)
Location: include/linux/sched/signal.h:696
Inline: True
```
```
In fs/select.c (c00000000049ccc0)
Location: include/linux/sched/signal.h:696
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
```
```
In fs/attr.c (c0000000004ab72c)
Location: include/linux/sched/signal.h:696
Inline: True
```
```
In fs/file.c (c0000000004ae8fc)
Location: include/linux/sched/signal.h:696
Inline: True
Inline callers:
  - fs/file.c:f_dupfd
  - fs/file.c:f_dupfd
  - fs/file.c:ksys_dup3
  - fs/file.c:replace_fd
  - fs/file.c:get_unused_fd_flags
```
```
In fs/io_uring.c (c0000000005094d8)
Location: include/linux/sched/signal.h:696
Inline: True
Inline callers:
  - fs/io_uring.c:io_account_mem
```
```
In fs/coredump.c (c000000000538508)
Location: include/linux/sched/signal.h:696
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In ipc/shm.c (c000000000672248)
Location: include/linux/sched/signal.h:696
Inline: True
Inline callers:
  - ipc/shm.c:shmctl_do_lock
```
```
In ipc/mqueue.c (c000000000674cfc)
Location: include/linux/sched/signal.h:696
Inline: True
Inline callers:
  - ipc/mqueue.c:mqueue_get_inode
```
```
In security/selinux/hooks.c (c0000000006aadf4)
Location: include/linux/sched/signal.h:696
Inline: True
```
```
In net/core/skbuff.c (c000000000c89bbc)
Location: include/linux/sched/signal.h:696
Inline: True
```
```
In net/xdp/xdp_umem.c (c000000000ec12bc)
Location: include/linux/sched/signal.h:696
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
In kernel/sys.c (ffffffe0000d233e)
Location: include/linux/sched/signal.h:696
Inline: True
```
```
In kernel/bpf/syscall.c (ffffffe0001a052c)
Location: include/linux/sched/signal.h:696
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_map_charge_memlock
  - kernel/bpf/syscall.c:bpf_map_charge_init
```
```
In kernel/events/core.c (ffffffe0001ce0d8)
Location: include/linux/sched/signal.h:696
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
```
```
In mm/filemap.c (ffffffe0001d4d1a)
Location: include/linux/sched/signal.h:696
Inline: True
```
```
In mm/mlock.c (ffffffe00020cf98)
Location: include/linux/sched/signal.h:696
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
Location: include/linux/sched/signal.h:696
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
Location: include/linux/sched/signal.h:696
Inline: True
Inline callers:
  - mm/mremap.c:vma_to_resize
```
```
In fs/exec.c (ffffffe00025e8c0)
Location: include/linux/sched/signal.h:696
Inline: True
Inline callers:
  - fs/exec.c:__do_execve_file
```
```
In fs/select.c (ffffffe00026b074)
Location: include/linux/sched/signal.h:696
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
```
```
In fs/attr.c (ffffffe0002744c4)
Location: include/linux/sched/signal.h:696
Inline: True
```
```
In fs/file.c (ffffffe0002769ec)
Location: include/linux/sched/signal.h:696
Inline: True
Inline callers:
  - fs/file.c:f_dupfd
  - fs/file.c:f_dupfd
  - fs/file.c:ksys_dup3
  - fs/file.c:replace_fd
  - fs/file.c:get_unused_fd_flags
```
```
In fs/io_uring.c (ffffffe0002b06b4)
Location: include/linux/sched/signal.h:696
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_sqe_buffer_register
```
```
In fs/binfmt_flat.c (ffffffe0002c2e56)
Location: include/linux/sched/signal.h:696
Inline: True
Inline callers:
  - fs/binfmt_flat.c:load_flat_file
```
```
In fs/coredump.c (ffffffe0002c65ba)
Location: include/linux/sched/signal.h:696
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In ipc/shm.c (ffffffe00038b746)
Location: include/linux/sched/signal.h:696
Inline: True
```
```
In ipc/mqueue.c (ffffffe00038d572)
Location: include/linux/sched/signal.h:696
Inline: True
Inline callers:
  - ipc/mqueue.c:mqueue_get_inode
```
```
In security/selinux/hooks.c (ffffffe0003a8a2e)
Location: include/linux/sched/signal.h:696
Inline: True
```
```
In net/core/skbuff.c (ffffffe000743826)
Location: include/linux/sched/signal.h:696
Inline: True
```
```
In net/xdp/xdp_umem.c (ffffffe0008ad832)
Location: include/linux/sched/signal.h:696
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
In kernel/sys.c (ffffffff810b3440)
Location: include/linux/sched/signal.h:696
Inline: True
```
```
In kernel/bpf/syscall.c (ffffffff811d9b15)
Location: include/linux/sched/signal.h:696
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_prog_charge
  - kernel/bpf/syscall.c:bpf_charge_memlock
```
```
In kernel/events/core.c (ffffffff8120b3dc)
Location: include/linux/sched/signal.h:696
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
```
```
In mm/filemap.c (ffffffff81219b47)
Location: include/linux/sched/signal.h:696
Inline: True
```
```
In mm/mlock.c (ffffffff812603f3)
Location: include/linux/sched/signal.h:696
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
Location: include/linux/sched/signal.h:696
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
Location: include/linux/sched/signal.h:696
Inline: True
Inline callers:
  - mm/mremap.c:vma_to_resize
```
```
In fs/exec.c (ffffffff812ddfc7)
Location: include/linux/sched/signal.h:696
Inline: True
```
```
In fs/select.c (ffffffff812ee452)
Location: include/linux/sched/signal.h:696
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
```
```
In fs/attr.c (ffffffff812f715b)
Location: include/linux/sched/signal.h:696
Inline: True
```
```
In fs/file.c (ffffffff812f8fe5)
Location: include/linux/sched/signal.h:696
Inline: True
Inline callers:
  - fs/file.c:f_dupfd
  - fs/file.c:f_dupfd
  - fs/file.c:ksys_dup3
  - fs/file.c:replace_fd
  - fs/file.c:get_unused_fd_flags
```
```
In fs/io_uring.c (ffffffff8133d54a)
Location: include/linux/sched/signal.h:696
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_sqe_buffer_register
```
```
In fs/coredump.c (ffffffff8135a254)
Location: include/linux/sched/signal.h:696
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In ipc/shm.c (ffffffff814379cd)
Location: include/linux/sched/signal.h:696
Inline: True
Inline callers:
  - ipc/shm.c:shmctl_do_lock
```
```
In ipc/mqueue.c (ffffffff8143c29d)
Location: include/linux/sched/signal.h:696
Inline: True
Inline callers:
  - ipc/mqueue.c:mqueue_get_inode
```
```
In security/selinux/hooks.c (ffffffff8145aa1b)
Location: include/linux/sched/signal.h:696
Inline: True
```
```
In net/core/skbuff.c (ffffffff818b90ad)
Location: include/linux/sched/signal.h:696
Inline: True
```
```
In net/xdp/xdp_umem.c (ffffffff81a4be7b)
Location: include/linux/sched/signal.h:696
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
In kernel/sys.c (ffffffff810a1d70)
Location: include/linux/sched/signal.h:696
Inline: True
```
```
In kernel/bpf/syscall.c (ffffffff811cc8d5)
Location: include/linux/sched/signal.h:696
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_prog_charge
  - kernel/bpf/syscall.c:bpf_charge_memlock
```
```
In kernel/events/core.c (ffffffff811fe1ac)
Location: include/linux/sched/signal.h:696
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
```
```
In mm/filemap.c (ffffffff8120cd57)
Location: include/linux/sched/signal.h:696
Inline: True
```
```
In mm/mlock.c (ffffffff81252813)
Location: include/linux/sched/signal.h:696
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
Location: include/linux/sched/signal.h:696
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
Location: include/linux/sched/signal.h:696
Inline: True
Inline callers:
  - mm/mremap.c:vma_to_resize
```
```
In fs/exec.c (ffffffff812cf2f7)
Location: include/linux/sched/signal.h:696
Inline: True
```
```
In fs/select.c (ffffffff812df082)
Location: include/linux/sched/signal.h:696
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
```
```
In fs/attr.c (ffffffff812e7d7b)
Location: include/linux/sched/signal.h:696
Inline: True
```
```
In fs/file.c (ffffffff812e9c05)
Location: include/linux/sched/signal.h:696
Inline: True
Inline callers:
  - fs/file.c:f_dupfd
  - fs/file.c:f_dupfd
  - fs/file.c:ksys_dup3
  - fs/file.c:replace_fd
  - fs/file.c:get_unused_fd_flags
```
```
In fs/io_uring.c (ffffffff8132e20a)
Location: include/linux/sched/signal.h:696
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_sqe_buffer_register
```
```
In fs/coredump.c (ffffffff8134af04)
Location: include/linux/sched/signal.h:696
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In ipc/shm.c (ffffffff8142843d)
Location: include/linux/sched/signal.h:696
Inline: True
Inline callers:
  - ipc/shm.c:shmctl_do_lock
```
```
In ipc/mqueue.c (ffffffff8142cd0d)
Location: include/linux/sched/signal.h:696
Inline: True
Inline callers:
  - ipc/mqueue.c:mqueue_get_inode
```
```
In security/selinux/hooks.c (ffffffff8144b44b)
Location: include/linux/sched/signal.h:696
Inline: True
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff8177f225)
Location: include/linux/sched/signal.h:696
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_map
```
```
In net/core/skbuff.c (ffffffff81872ffd)
Location: include/linux/sched/signal.h:696
Inline: True
```
```
In net/xdp/xdp_umem.c (ffffffff81a08a6b)
Location: include/linux/sched/signal.h:696
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
In kernel/sys.c (ffffffff810b29a0)
Location: include/linux/sched/signal.h:696
Inline: True
```
```
In kernel/bpf/syscall.c (ffffffff811d78e5)
Location: include/linux/sched/signal.h:696
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_prog_charge
  - kernel/bpf/syscall.c:bpf_charge_memlock
```
```
In kernel/events/core.c (ffffffff8120917c)
Location: include/linux/sched/signal.h:696
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
```
```
In mm/filemap.c (ffffffff812178e7)
Location: include/linux/sched/signal.h:696
Inline: True
```
```
In mm/mlock.c (ffffffff8125e193)
Location: include/linux/sched/signal.h:696
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
Location: include/linux/sched/signal.h:696
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
Location: include/linux/sched/signal.h:696
Inline: True
Inline callers:
  - mm/mremap.c:vma_to_resize
```
```
In fs/exec.c (ffffffff812dbdd7)
Location: include/linux/sched/signal.h:696
Inline: True
```
```
In fs/select.c (ffffffff812ec262)
Location: include/linux/sched/signal.h:696
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
```
```
In fs/attr.c (ffffffff812f4f6b)
Location: include/linux/sched/signal.h:696
Inline: True
```
```
In fs/file.c (ffffffff812f6df5)
Location: include/linux/sched/signal.h:696
Inline: True
Inline callers:
  - fs/file.c:f_dupfd
  - fs/file.c:f_dupfd
  - fs/file.c:ksys_dup3
  - fs/file.c:replace_fd
  - fs/file.c:get_unused_fd_flags
```
```
In fs/io_uring.c (ffffffff8133b01a)
Location: include/linux/sched/signal.h:696
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_sqe_buffer_register
```
```
In fs/coredump.c (ffffffff81357d24)
Location: include/linux/sched/signal.h:696
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In ipc/shm.c (ffffffff81433b6d)
Location: include/linux/sched/signal.h:696
Inline: True
Inline callers:
  - ipc/shm.c:shmctl_do_lock
```
```
In ipc/mqueue.c (ffffffff8143843d)
Location: include/linux/sched/signal.h:696
Inline: True
Inline callers:
  - ipc/mqueue.c:mqueue_get_inode
```
```
In security/selinux/hooks.c (ffffffff81456abb)
Location: include/linux/sched/signal.h:696
Inline: True
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff817c9ff5)
Location: include/linux/sched/signal.h:696
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_map
```
```
In net/core/skbuff.c (ffffffff8190a0ad)
Location: include/linux/sched/signal.h:696
Inline: True
```
```
In net/xdp/xdp_umem.c (ffffffff81ab7d2b)
Location: include/linux/sched/signal.h:696
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
In kernel/sys.c (ffffffff810bafa0)
Location: include/linux/sched/signal.h:696
Inline: True
```
```
In kernel/bpf/syscall.c (ffffffff811e5c85)
Location: include/linux/sched/signal.h:696
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_prog_charge
  - kernel/bpf/syscall.c:bpf_charge_memlock
```
```
In kernel/events/core.c (ffffffff81217f0c)
Location: include/linux/sched/signal.h:696
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
```
```
In mm/filemap.c (ffffffff812269a7)
Location: include/linux/sched/signal.h:696
Inline: True
```
```
In mm/mlock.c (ffffffff8126db73)
Location: include/linux/sched/signal.h:696
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
Location: include/linux/sched/signal.h:696
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
Location: include/linux/sched/signal.h:696
Inline: True
Inline callers:
  - mm/mremap.c:vma_to_resize
```
```
In fs/exec.c (ffffffff812ecb57)
Location: include/linux/sched/signal.h:696
Inline: True
```
```
In fs/select.c (ffffffff812fd262)
Location: include/linux/sched/signal.h:696
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
```
```
In fs/attr.c (ffffffff813060fb)
Location: include/linux/sched/signal.h:696
Inline: True
```
```
In fs/file.c (ffffffff81308065)
Location: include/linux/sched/signal.h:696
Inline: True
Inline callers:
  - fs/file.c:f_dupfd
  - fs/file.c:f_dupfd
  - fs/file.c:ksys_dup3
  - fs/file.c:replace_fd
  - fs/file.c:get_unused_fd_flags
```
```
In fs/io_uring.c (ffffffff8134e1ca)
Location: include/linux/sched/signal.h:696
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_sqe_buffer_register
```
```
In fs/coredump.c (ffffffff8136b404)
Location: include/linux/sched/signal.h:696
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In ipc/shm.c (ffffffff8144a2ce)
Location: include/linux/sched/signal.h:696
Inline: True
Inline callers:
  - ipc/shm.c:shmctl_do_lock
```
```
In ipc/mqueue.c (ffffffff8144c966)
Location: include/linux/sched/signal.h:696
Inline: True
Inline callers:
  - ipc/mqueue.c:mqueue_get_inode
```
```
In security/selinux/hooks.c (ffffffff8146ea7c)
Location: include/linux/sched/signal.h:696
Inline: True
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff817e4295)
Location: include/linux/sched/signal.h:696
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_map
```
```
In net/core/skbuff.c (ffffffff8192b1ad)
Location: include/linux/sched/signal.h:696
Inline: True
```
```
In net/xdp/xdp_umem.c (ffffffff81ac414b)
Location: include/linux/sched/signal.h:696
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_create
```
</details>
</li>
</ul>

## Differences
