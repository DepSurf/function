# Function: <code>refcount_add</code>

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
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff817b4a61)
Location: include/linux/refcount.h:61
Inline: True
```
```
In net/core/skbuff.c (ffffffff817b7f69)
Location: include/linux/refcount.h:61
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_append_datato_frags
```
```
In net/core/datagram.c (ffffffff817bffff)
Location: include/linux/refcount.h:61
Inline: True
```
```
In net/ipv4/ip_output.c (ffffffff8181b010)
Location: include/linux/refcount.h:61
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp_output.c (ffffffff81833731)
Location: include/linux/refcount.h:61
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_transmit_skb
```
```
In net/ipv4/tcp_offload.c (ffffffff81842613)
Location: include/linux/refcount.h:61
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/unix/af_unix.c (ffffffff8188283c)
Location: include/linux/refcount.h:61
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_sendpage
```
```
In net/ipv6/ip6_output.c (ffffffff81888109)
Location: include/linux/refcount.h:61
Inline: True
```
```
In net/packet/af_packet.c (ffffffff818d2bb6)
Location: include/linux/refcount.h:61
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_snd
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
In net/core/sock.c (ffffffff8182cc98)
Location: arch/x86/include/asm/refcount.h:41
Inline: True
Inline callers:
  - net/core/sock.c:skb_set_owner_w
```
```
In net/core/skbuff.c (ffffffff818306cc)
Location: arch/x86/include/asm/refcount.h:41
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_append_datato_frags
```
```
In net/core/datagram.c (ffffffff81839381)
Location: arch/x86/include/asm/refcount.h:41
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
```
```
In net/ipv4/ip_output.c (ffffffff81899fb3)
Location: arch/x86/include/asm/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp_output.c (ffffffff818b2abc)
Location: arch/x86/include/asm/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_transmit_skb
```
```
In net/ipv4/tcp_offload.c (ffffffff818c1f37)
Location: arch/x86/include/asm/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/unix/af_unix.c (ffffffff819038dc)
Location: arch/x86/include/asm/refcount.h:41
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_sendpage
```
```
In net/ipv6/ip6_output.c (ffffffff8190a550)
Location: arch/x86/include/asm/refcount.h:41
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81957ae7)
Location: arch/x86/include/asm/refcount.h:41
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_snd
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
In net/core/sock.c (ffffffff81876a84)
Location: arch/x86/include/asm/refcount.h:41
Inline: True
Inline callers:
  - net/core/sock.c:skb_set_owner_w
```
```
In net/core/skbuff.c (ffffffff8187ab86)
Location: arch/x86/include/asm/refcount.h:41
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_append_datato_frags
```
```
In net/core/datagram.c (ffffffff81883aaf)
Location: arch/x86/include/asm/refcount.h:41
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
```
```
In net/ipv4/ip_output.c (ffffffff818ee458)
Location: arch/x86/include/asm/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp_output.c (ffffffff81907fb5)
Location: arch/x86/include/asm/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_offload.c (ffffffff81917bbb)
Location: arch/x86/include/asm/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp_offload.c (ffffffff81920f66)
Location: arch/x86/include/asm/refcount.h:41
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
```
```
In net/unix/af_unix.c (ffffffff8195b9e9)
Location: arch/x86/include/asm/refcount.h:41
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_sendpage
```
```
In net/ipv6/ip6_output.c (ffffffff8196192f)
Location: arch/x86/include/asm/refcount.h:41
Inline: True
```
```
In net/packet/af_packet.c (ffffffff819af78a)
Location: arch/x86/include/asm/refcount.h:41
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_snd
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
In mm/memcontrol.c (ffffffff81292df5)
Location: arch/x86/include/asm/refcount.h:42
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_id_get_many
```
```
In net/core/sock.c (ffffffff81897254)
Location: arch/x86/include/asm/refcount.h:42
Inline: True
Inline callers:
  - net/core/sock.c:skb_set_owner_w
```
```
In net/core/datagram.c (ffffffff818a4449)
Location: arch/x86/include/asm/refcount.h:42
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
```
```
In net/ipv4/ip_output.c (ffffffff8191bc1c)
Location: arch/x86/include/asm/refcount.h:42
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp_output.c (ffffffff819362a2)
Location: arch/x86/include/asm/refcount.h:42
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_offload.c (ffffffff819462e9)
Location: arch/x86/include/asm/refcount.h:42
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp_offload.c (ffffffff8194fad0)
Location: arch/x86/include/asm/refcount.h:42
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
```
```
In net/unix/af_unix.c (ffffffff8199020d)
Location: arch/x86/include/asm/refcount.h:42
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_sendpage
```
```
In net/ipv6/ip6_output.c (ffffffff81996280)
Location: arch/x86/include/asm/refcount.h:42
Inline: True
```
```
In net/packet/af_packet.c (ffffffff819e6cdf)
Location: arch/x86/include/asm/refcount.h:42
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_snd
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
In mm/memcontrol.c (ffffffff812ad765)
Location: arch/x86/include/asm/refcount.h:42
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_id_get_many
```
```
In fs/io_uring.c (ffffffff813320ca)
Location: arch/x86/include/asm/refcount.h:42
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_register
```
```
In net/core/sock.c (ffffffff818e16a4)
Location: arch/x86/include/asm/refcount.h:42
Inline: True
Inline callers:
  - net/core/sock.c:skb_set_owner_w
```
```
In net/core/datagram.c (ffffffff818efa9b)
Location: arch/x86/include/asm/refcount.h:42
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
```
```
In net/ipv4/ip_output.c (ffffffff8197df06)
Location: arch/x86/include/asm/refcount.h:42
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp_output.c (ffffffff8199a65f)
Location: arch/x86/include/asm/refcount.h:42
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_offload.c (ffffffff819aa922)
Location: arch/x86/include/asm/refcount.h:42
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp_offload.c (ffffffff819b4355)
Location: arch/x86/include/asm/refcount.h:42
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
```
```
In net/unix/af_unix.c (ffffffff819fb8fc)
Location: arch/x86/include/asm/refcount.h:42
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_sendpage
```
```
In net/ipv6/ip6_output.c (ffffffff81a026ef)
Location: arch/x86/include/asm/refcount.h:42
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81a56236)
Location: arch/x86/include/asm/refcount.h:42
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_snd
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
In mm/memcontrol.c (ffffffff812bf2b5)
Location: arch/x86/include/asm/refcount.h:42
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_id_get_many
```
```
In fs/io_uring.c (ffffffff81345c8a)
Location: arch/x86/include/asm/refcount.h:42
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_register
```
```
In net/core/sock.c (ffffffff81913894)
Location: arch/x86/include/asm/refcount.h:42
Inline: True
Inline callers:
  - net/core/sock.c:skb_set_owner_w
```
```
In net/core/datagram.c (ffffffff81921abb)
Location: arch/x86/include/asm/refcount.h:42
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
```
```
In net/ipv4/ip_output.c (ffffffff819b48b3)
Location: arch/x86/include/asm/refcount.h:42
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp_output.c (ffffffff819d10a9)
Location: arch/x86/include/asm/refcount.h:42
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_offload.c (ffffffff819e15c1)
Location: arch/x86/include/asm/refcount.h:42
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp_offload.c (ffffffff819eb085)
Location: arch/x86/include/asm/refcount.h:42
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
```
```
In net/unix/af_unix.c (ffffffff81a3258c)
Location: arch/x86/include/asm/refcount.h:42
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_sendpage
```
```
In net/ipv6/ip6_output.c (ffffffff81a392c7)
Location: arch/x86/include/asm/refcount.h:42
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81a8d716)
Location: arch/x86/include/asm/refcount.h:42
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_snd
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/ioport.c (ffffffff810370e0)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:io_bitmap_share
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81056644)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:threshold_create_bank
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81061b6b)
Location: include/linux/refcount.h:199
Inline: True
```
```
In kernel/fork.c (ffffffff810a742d)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
  - kernel/fork.c:copy_sighand
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/exit.c (ffffffff810ad746)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - kernel/exit.c:kernel_waitid
  - kernel/exit.c:wait_task_continued
  - kernel/exit.c:wait_task_stopped
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:mm_update_next_owner
  - kernel/exit.c:release_task
```
```
In kernel/user.c (ffffffff810b6f3b)
Location: include/linux/refcount.h:199
Inline: True
```
```
In kernel/signal.c (ffffffff810b7958)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - kernel/signal.c:__sigqueue_alloc
```
```
In kernel/sys.c (ffffffff810c3feb)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - kernel/sys.c:__do_sys_prlimit64
```
```
In kernel/pid.c (ffffffff810cd8e2)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - kernel/pid.c:pidfd_getfd
  - kernel/pid.c:__ia32_sys_pidfd_open
  - kernel/pid.c:__x64_sys_pidfd_open
  - kernel/pid.c:find_get_pid
  - kernel/pid.c:get_task_pid
  - kernel/pid.c:find_get_task_by_vpid
  - kernel/pid.c:alloc_pid
```
```
In kernel/kthread.c (ffffffff810d0a3d)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_stop
```
```
In kernel/nsproxy.c (ffffffff810d6205)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - kernel/nsproxy.c:validate_nsset
  - kernel/nsproxy.c:create_new_namespaces
```
```
In kernel/cred.c (ffffffff810d7ba0)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
```
```
In kernel/smpboot.c (ffffffff810d92c6)
Location: include/linux/refcount.h:199
Inline: True
```
```
In kernel/sched/core.c (ffffffff810e5586)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__ia32_sys_sched_setattr
  - kernel/sched/core.c:__x64_sys_sched_setattr
  - kernel/sched/core.c:do_sched_setscheduler
  - kernel/sched/core.c:wake_q_add
```
```
In kernel/sched/fair.c (ffffffff810eb9f9)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_assign
```
```
In kernel/sched/rt.c (ffffffff810f92dd)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - kernel/sched/rt.c:push_rt_task
```
```
In kernel/sched/deadline.c (ffffffff810fa749)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - kernel/sched/deadline.c:start_dl_timer
  - kernel/sched/deadline.c:task_non_contending
```
```
In kernel/sched/autogroup.c (ffffffff81105062)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:proc_sched_autogroup_show_task
  - kernel/sched/autogroup.c:proc_sched_autogroup_show_task
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
  - kernel/sched/autogroup.c:sched_autogroup_fork
  - kernel/sched/autogroup.c:sched_autogroup_fork
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
  - kernel/sched/autogroup.c:autogroup_move_group
```
```
In kernel/sched/psi.c (ffffffff8110d457)
Location: include/linux/refcount.h:199
Inline: True
```
```
In kernel/locking/rwsem.c (ffffffff8110e618)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_mark_wake
```
```
In kernel/locking/percpu-rwsem.c (ffffffff8110f4f5)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:percpu_rwsem_wake_function
```
```
In kernel/locking/rtmutex.c (ffffffff81110dec)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_adjust_pi
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:task_blocks_on_rt_mutex
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
```
```
In kernel/irq/manage.c (ffffffff81122e62)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - kernel/irq/manage.c:setup_irq_thread
  - kernel/irq/manage.c:irq_set_affinity_locked
```
```
In kernel/rcu/update.c (ffffffff81130a97)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_trace_postgp
```
```
In kernel/kcmp.c (ffffffff8113fd3b)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/kcmp.c:__do_sys_kcmp
```
```
In kernel/time/posix-timers.c (ffffffff81150b11)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811528c4)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_create
```
```
In kernel/time/namespace.c (ffffffff8115a28f)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - kernel/time/namespace.c:timens_on_fork
  - kernel/time/namespace.c:timens_install
  - kernel/time/namespace.c:timens_install
  - kernel/time/namespace.c:timens_for_children_get
  - kernel/time/namespace.c:timens_get
  - kernel/time/namespace.c:copy_time_ns
```
```
In kernel/futex.c (ffffffff8115adc5)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - kernel/futex.c:mark_wake_futex
```
```
In kernel/cgroup/cgroup.c (ffffffff81177895)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_post_fork
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:css_task_iter_next
  - kernel/cgroup/cgroup.c:css_task_iter_advance_css_set
  - kernel/cgroup/cgroup.c:css_task_iter_advance_css_set
  - kernel/cgroup/cgroup.c:cgroup_procs_write_start
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:cgroup_init_fs_context
  - kernel/cgroup/cgroup.c:find_css_set
```
```
In kernel/cgroup/namespace.c (ffffffff811791a6)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:cgroupns_get
  - kernel/cgroup/namespace.c:cgroupns_install
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/cgroup/namespace.c:copy_cgroup_ns
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81179ad8)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_find_create
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
```
In kernel/utsname.c (ffffffff81183620)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - kernel/utsname.c:utsns_install
  - kernel/utsname.c:utsns_get
  - kernel/utsname.c:copy_utsname
```
```
In kernel/pid_namespace.c (ffffffff81185405)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_get_parent
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pidns_for_children_get
  - kernel/pid_namespace.c:pidns_get
  - kernel/pid_namespace.c:copy_pid_ns
  - kernel/pid_namespace.c:create_pid_namespace
```
```
In kernel/audit.c (ffffffff81188595)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - kernel/audit.c:audit_get_tty
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_send_queue
```
```
In kernel/auditfilter.c (ffffffff8118bfcb)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_list_rules_send
```
```
In kernel/audit_watch.c (ffffffff81191ff2)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_add_to_parent
  - kernel/audit_watch.c:audit_add_to_parent
  - kernel/audit_watch.c:audit_update_watch
```
```
In kernel/audit_tree.c (ffffffff811944ff)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_trim_trees
  - kernel/audit_tree.c:tag_chunk
  - kernel/audit_tree.c:create_chunk
  - kernel/audit_tree.c:replace_chunk
```
```
In kernel/hung_task.c (ffffffff811a42b7)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - kernel/hung_task.c:check_hung_uninterruptible_tasks
  - kernel/hung_task.c:check_hung_uninterruptible_tasks
```
```
In kernel/seccomp.c (ffffffff811a6660)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - kernel/seccomp.c:init_listener
  - kernel/seccomp.c:seccomp_attach_filter
```
```
In kernel/relay.c (ffffffff811a8a74)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - kernel/relay.c:relay_file_open
  - kernel/relay.c:relay_create_buf
```
```
In kernel/trace/trace.c (ffffffff811bb58b)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - kernel/trace/trace.c:buffer_pipe_buf_get
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811cb022)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In kernel/bpf/syscall.c (ffffffff8120018a)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_map_charge_init
```
```
In kernel/bpf/task_iter.c (ffffffff81216328)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - kernel/bpf/task_iter.c:init_seq_pidns
```
```
In kernel/bpf/trampoline.c (ffffffff8121eeca)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_lookup
```
```
In kernel/bpf/btf.c (ffffffff81225f05)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_get_by_fd
```
```
In kernel/bpf/dispatcher.c (ffffffff812262ea)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - kernel/bpf/dispatcher.c:bpf_dispatcher_change_prog
```
```
In kernel/bpf/offload.c (ffffffff81229189)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_map_offload_info_fill_ns
  - kernel/bpf/offload.c:bpf_prog_offload_info_fill_ns
```
```
In kernel/events/core.c (ffffffff8123e163)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init_context
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:find_get_context
  - kernel/events/core.c:find_get_context
  - kernel/events/core.c:alloc_perf_context
Direct callers:
  - kernel/events/core.c:__do_sys_perf_event_open
```
```
In kernel/events/uprobes.c (ffffffff81248af2)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - kernel/events/uprobes.c:prepare_uretprobe
  - kernel/events/uprobes.c:dup_utask
  - kernel/events/uprobes.c:build_probe_list
  - kernel/events/uprobes.c:build_probe_list
  - kernel/events/uprobes.c:alloc_uprobe
  - kernel/events/uprobes.c:__find_uprobe
```
```
In kernel/watch_queue.c (ffffffff8124c676)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - kernel/watch_queue.c:get_watch_queue
  - kernel/watch_queue.c:add_watch_to_object
  - kernel/watch_queue.c:add_watch_to_object
```
```
In mm/oom_kill.c (ffffffff81255680)
Location: include/linux/refcount.h:199
Inline: True
Direct callers:
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/backing-dev.c (ffffffff812777a6)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_get_by_id
  - mm/backing-dev.c:cgwb_create
  - mm/backing-dev.c:wb_congested_get_create
  - mm/backing-dev.c:wb_init
```
```
In mm/mlock.c (ffffffff81297dd5)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - mm/mlock.c:user_shm_lock
```
```
In mm/page_io.c (ffffffff812b877b)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
```
```
In mm/hugetlb.c (ffffffff812c3ecf)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_vm_op_open
```
```
In mm/mempolicy.c (ffffffff812cd193)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_migrate_pages
```
```
In mm/migrate.c (ffffffff812e73db)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - mm/migrate.c:kernel_move_pages
```
```
In mm/memcontrol.c (ffffffff812fde74)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
```
```
In mm/memory-failure.c (ffffffff813009cd)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - mm/memory-failure.c:add_to_kill
```
```
In fs/super.c (ffffffff81316770)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - fs/super.c:set_bdev_super_fc
```
```
In fs/pipe.c (ffffffff8131fa97)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - fs/pipe.c:alloc_pipe_info
```
```
In fs/fcntl.c (ffffffff81329d11)
Location: include/linux/refcount.h:199
Inline: True
```
```
In fs/fs_context.c (ffffffff813576f0)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - fs/fs_context.c:vfs_dup_fs_context
  - fs/fs_context.c:vfs_dup_fs_context
  - fs/fs_context.c:alloc_fs_context
```
```
In fs/block_dev.c (ffffffff81360c6e)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_get
```
```
In fs/notify/group.c (ffffffff81366d6a)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_get_group
```
```
In fs/notify/mark.c (ffffffff81367974)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_get_mark
```
```
In fs/notify/fanotify/fanotify.c (ffffffff8136aa74)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff8136b125)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:__do_sys_fanotify_init
```
```
In fs/eventpoll.c (ffffffff8136cfe8)
Location: include/linux/refcount.h:199
Inline: True
```
```
In fs/eventfd.c (ffffffff81371928)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_ctx_fdget
```
```
In fs/userfaultfd.c (ffffffff81373fe6)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ctx_read
  - fs/userfaultfd.c:userfaultfd_unmap_prep
  - fs/userfaultfd.c:userfaultfd_remove
  - fs/userfaultfd.c:mremap_userfaultfd_prep
  - fs/userfaultfd.c:dup_userfaultfd
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/io_uring.c (ffffffff8138579f)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:__io_sqe_files_scm
  - fs/io_uring.c:__io_sqe_files_scm
  - fs/io_uring.c:io_poll_add_prep
  - fs/io_uring.c:io_poll_queue_proc
  - fs/io_uring.c:io_arm_poll_handler
  - fs/io_uring.c:io_async_queue_proc
  - fs/io_uring.c:io_iopoll_complete
  - fs/io_uring.c:__io_cqring_fill_event
```
```
In fs/crypto/keysetup.c (ffffffff81393cce)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
```
```
In fs/crypto/keysetup_v1.c (ffffffff813943e7)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:find_or_insert_direct_key
```
```
In fs/posix_acl.c (ffffffff813a5fde)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - fs/posix_acl.c:set_cached_acl
```
```
In fs/proc/root.c (ffffffff813ba83c)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - fs/proc/root.c:proc_init_fs_context
  - fs/proc/root.c:proc_fill_super
  - fs/proc/root.c:proc_fill_super
```
```
In fs/proc/base.c (ffffffff813bf802)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_lookup
  - fs/proc/base.c:next_tgid
  - fs/proc/base.c:proc_pid_lookup
```
```
In fs/proc/generic.c (ffffffff813c0883)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_lookup_de
```
```
In fs/proc/array.c (ffffffff813c1cdf)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - fs/proc/array.c:get_children_pid
```
```
In fs/proc/proc_net.c (ffffffff813c9a0b)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - fs/proc/proc_net.c:get_proc_task_net
  - fs/proc/proc_net.c:bpf_iter_init_seq_net
```
```
In fs/configfs/item.c (ffffffff813d7889)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - fs/configfs/item.c:config_group_find_item
```
```
In fs/ecryptfs/keystore.c (ffffffff8146640e)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig
```
```
In fs/fuse/dev.c (ffffffff8146efea)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_abort_conn
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_do_read
  - fs/fuse/dev.c:fuse_simple_request
```
```
In fs/fuse/file.c (ffffffff8147a55f)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_writepages_send
  - fs/fuse/file.c:fuse_write_inode
  - fs/fuse/file.c:fuse_writepage_end
  - fs/fuse/file.c:fuse_send_readpages
  - fs/fuse/file.c:fuse_async_req_send
```
```
In fs/fuse/inode.c (ffffffff8147e0da)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_fill_super_common
  - fs/fuse/inode.c:fuse_conn_init
```
```
In ipc/util.c (ffffffff814867b4)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - ipc/util.c:sysvipc_proc_open
  - ipc/util.c:sysvipc_proc_open
```
```
In ipc/msg.c (ffffffff81489834)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:expunge_all
```
```
In ipc/sem.c (ffffffff8148e6fa)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:copy_semundo
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:freeary
  - ipc/sem.c:freeary
  - ipc/sem.c:freeary
  - ipc/sem.c:freeary
  - ipc/sem.c:update_queue
  - ipc/sem.c:wake_const_ops
  - ipc/sem.c:perform_atomic_semop
  - ipc/sem.c:perform_atomic_semop_slow
```
```
In ipc/shm.c (ffffffff81490d6d)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_close
```
```
In ipc/mqueue.c (ffffffff81494cec)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - ipc/mqueue.c:mq_init_ns
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
  - ipc/mqueue.c:mqueue_create_attr
  - ipc/mqueue.c:mqueue_evict_inode
  - ipc/mqueue.c:mqueue_init_fs_context
  - ipc/mqueue.c:mqueue_get_inode
```
```
In ipc/namespace.c (ffffffff814952cd)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - ipc/namespace.c:ipcns_install
  - ipc/namespace.c:ipcns_get
  - ipc/namespace.c:get_ipc_ns_exported
  - ipc/namespace.c:copy_ipcs
```
```
In security/keys/key.c (ffffffff81496e1c)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_user_lookup
```
```
In security/keys/keyring.c (ffffffff8149860a)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_gc_select_iterator
  - security/keys/keyring.c:__key_link
  - security/keys/keyring.c:find_key_to_update
  - security/keys/keyring.c:keyring_search_rcu
```
```
In security/keys/keyctl.c (ffffffff81499816)
Location: include/linux/refcount.h:199
Inline: True
```
```
In security/keys/process_keys.c (ffffffff8149d290)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:install_session_keyring_to_cred
```
```
In security/keys/request_key.c (ffffffff8149d91b)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - security/keys/request_key.c:request_key_rcu
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:cache_requested_key
```
```
In security/keys/request_key_auth.c (ffffffff8149e782)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/request_key_auth.c:request_key_auth_new
```
```
In security/apparmor/apparmorfs.c (ffffffff814ed532)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:create_profile_file
  - security/apparmor/apparmorfs.c:__aa_fs_create_rawdata
  - security/apparmor/apparmorfs.c:seq_profile_hash_open
  - security/apparmor/apparmorfs.c:seq_profile_attach_open
  - security/apparmor/apparmorfs.c:seq_profile_mode_open
  - security/apparmor/apparmorfs.c:seq_profile_name_open
  - security/apparmor/apparmorfs.c:multi_transaction_read
  - security/apparmor/apparmorfs.c:ns_revision_open
  - security/apparmor/apparmorfs.c:ns_revision_open
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_load
```
```
In security/apparmor/capability.c (ffffffff814f0bfa)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - security/apparmor/capability.c:audit_caps
```
```
In security/apparmor/task.c (ffffffff814f1521)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_set_current_onexec
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/task.c:aa_get_task_label
```
```
In security/apparmor/domain.c (ffffffff814f904b)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:find_attach
  - security/apparmor/domain.c:find_attach
```
```
In security/apparmor/policy.c (ffffffff814fc2d7)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:update_to_newest_parent
  - security/apparmor/policy.c:update_to_newest_parent
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_alloc_profile
  - security/apparmor/policy.c:__add_profile
```
```
In security/apparmor/policy_unpack.c (ffffffff814fd2a1)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:do_loaddata_free
Direct callers:
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
```
```
In security/apparmor/procattr.c (ffffffff814ff1ea)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff81501401)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_sock_graft
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_sk_clone_security
  - security/apparmor/lsm.c:apparmor_sk_clone_security
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_sb_pivotroot
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_capable
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/lsm.c:apparmor_task_alloc
  - security/apparmor/lsm.c:apparmor_task_alloc
  - security/apparmor/lsm.c:apparmor_task_alloc
  - security/apparmor/lsm.c:apparmor_cred_transfer
  - security/apparmor/lsm.c:apparmor_cred_prepare
Direct callers:
  - security/apparmor/lsm.c:apparmor_init
```
```
In security/apparmor/resource.c (ffffffff815057c6)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - security/apparmor/resource.c:aa_task_setrlimit
```
```
In security/apparmor/file.c (ffffffff8150734c)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_inherit_files
  - security/apparmor/file.c:aa_file_perm
```
```
In security/apparmor/policy_ns.c (ffffffff81507fcf)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:aa_prepare_ns
  - security/apparmor/policy_ns.c:__aa_find_or_create_ns
  - security/apparmor/policy_ns.c:__aa_create_ns
  - security/apparmor/policy_ns.c:__aa_create_ns
  - security/apparmor/policy_ns.c:aa_lookupn_ns
  - security/apparmor/policy_ns.c:aa_find_ns
  - security/apparmor/policy_ns.c:alloc_ns
  - security/apparmor/policy_ns.c:alloc_ns
```
```
In security/apparmor/label.c (ffffffff8150a3b5)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:label_merge_insert
  - security/apparmor/label.c:label_merge_insert
  - security/apparmor/label.c:label_merge_insert
  - security/apparmor/label.c:label_merge_insert
  - security/apparmor/label.c:label_merge_insert
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - security/apparmor/label.c:__label_insert
  - security/apparmor/label.c:__label_insert
  - security/apparmor/label.c:__label_insert
  - security/apparmor/label.c:aa_label_alloc
  - security/apparmor/label.c:aa_alloc_proxy
```
```
In security/apparmor/mount.c (ffffffff8150e7dc)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:build_pivotroot
```
```
In security/apparmor/net.c (0)
Location: include/linux/refcount.h:199
Inline: True
```
```
In security/apparmor/af_unix.c (ffffffff81511375)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_file_perm
```
```
In security/yama/yama_lsm.c (ffffffff81511fb3)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_task_prctl
  - security/yama/yama_lsm.c:report_access
  - security/yama/yama_lsm.c:report_access
```
```
In crypto/api.c (ffffffff8151e7d4)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - crypto/api.c:crypto_mod_get
```
```
In crypto/algapi.c (ffffffff8152020a)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_stats_get
  - crypto/algapi.c:crypto_spawn_alg
```
```
In crypto/algboss.c (ffffffff81528e1e)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - crypto/algboss.c:cryptomgr_schedule_probe
```
```
In crypto/asymmetric_keys/restrict.c (ffffffff815389ed)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
```
```
In block/bsg.c (ffffffff81568df9)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - block/bsg.c:bsg_open
```
```
In block/blk-cgroup.c (ffffffff8156a329)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_css_online
```
```
In lib/cpu_rmap.c (ffffffff815df675)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - lib/cpu_rmap.c:irq_cpu_rmap_add
```
```
In lib/klist.c (ffffffff815ea6eb)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - lib/klist.c:klist_next
  - lib/klist.c:klist_prev
```
```
In lib/kobject.c (ffffffff815eaa69)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - lib/kobject.c:kobject_get
```
```
In lib/kobject_uevent.c (ffffffff815ec2b0)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - lib/kobject_uevent.c:uevent_net_broadcast_untagged
```
```
In drivers/pinctrl/core.c (ffffffff81603606)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:pinctrl_get
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff81652cf2)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/hotplug/acpiphp_glue.c:hotplug_event
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_grab_context
```
```
In drivers/acpi/ec.c (ffffffff81690ca5)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_query
```
```
In drivers/clk/clk.c (ffffffff81702600)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_hw_create_clk
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff81720246)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
```
```
In drivers/reset/core.c (ffffffff817328b3)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - drivers/reset/core.c:__reset_control_get_internal
```
```
In drivers/tty/tty_io.c (ffffffff81736f9d)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_fasync
  - drivers/tty/tty_io.c:tty_open_by_driver
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/tty_io.c:tty_find_polling_driver
```
```
In drivers/tty/tty_port.c (ffffffff8173fa66)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_tty_get
```
```
In drivers/tty/tty_mutex.c (ffffffff81740324)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - drivers/tty/tty_mutex.c:tty_lock_interruptible
  - drivers/tty/tty_mutex.c:tty_lock
```
```
In drivers/tty/tty_ldsem.c (ffffffff81bcbe84)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:down_read_failed
```
```
In drivers/tty/tty_jobctrl.c (ffffffff8174187f)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tiocspgrp
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:get_current_tty
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
```
```
In drivers/tty/pty.c (ffffffff817424ba)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - drivers/tty/pty.c:pty_common_install
  - drivers/tty/pty.c:pty_common_install
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff81744a37)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
```
```
In drivers/char/virtio_console.c (ffffffff817748bb)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:find_port_by_devt
```
```
In drivers/char/hw_random/core.c (ffffffff81779ebf)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:hwrng_unregister
  - drivers/char/hw_random/core.c:hwrng_register
  - drivers/char/hw_random/core.c:hwrng_fillfn
  - drivers/char/hw_random/core.c:hwrng_attr_current_show
  - drivers/char/hw_random/core.c:hwrng_attr_current_store
  - drivers/char/hw_random/core.c:rng_dev_read
```
```
In drivers/connector/connector.c (ffffffff817ad1cd)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_call_callback
```
```
In drivers/lightnvm/core.c (ffffffff817b0381)
Location: include/linux/refcount.h:199
Inline: True
```
```
In drivers/base/core.c (ffffffff817b5547)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/power/runtime.c (ffffffff817c9f21)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_get_suppliers
  - drivers/base/power/runtime.c:rpm_get_suppliers
```
```
In drivers/base/firmware_loader/main.c (ffffffff817d5dba)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:assign_fw
```
```
In drivers/nvdimm/core.c (ffffffff8180ee6f)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff818126ba)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:get_ndd
```
```
In drivers/dax/bus.c (ffffffff81824580)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - drivers/dax/bus.c:__devm_create_dev_dax
  - drivers/dax/bus.c:alloc_dax_region
```
```
In drivers/dma-buf/dma-fence.c (ffffffff818270ed)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_get_stub
```
```
In drivers/dma-buf/dma-fence-array.c (ffffffff81827731)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffff81827e62)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
```
```
In drivers/dma-buf/dma-resv.c (ffffffff81828f32)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_add_excl_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_add_shared_fence
```
```
In drivers/dma-buf/sync_file.c (ffffffff8182ad3d)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_get_fence
  - drivers/dma-buf/sync_file.c:sync_file_create
```
```
In drivers/dma-buf/sw_sync.c (ffffffff8182bdee)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_pt_create
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff8183d7de)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
```
```
In drivers/scsi/sr.c (ffffffff8184ab4a)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_block_revalidate_disk
  - drivers/scsi/sr.c:sr_block_check_events
  - drivers/scsi/sr.c:sr_block_open
```
```
In drivers/scsi/sg.c (ffffffff8184ee08)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_add_sfp
  - drivers/scsi/sg.c:sg_open
```
```
In drivers/ata/libata-core.c (ffffffff81858dba)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_get
```
```
In drivers/net/phy/phy_device.c (ffffffff818848a3)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_package_join
```
```
In drivers/net/phy/sfp-bus.c (ffffffff81888995)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_bus_get
```
```
In drivers/net/tun.c (ffffffff8188f433)
Location: include/linux/refcount.h:199
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81892950)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_connect_channel
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_init
```
```
In drivers/net/xen-netfront.c (ffffffff81898515)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_make_one_txreq
```
```
In drivers/vfio/vfio.c (ffffffff8189ceb4)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_get_external_user
  - drivers/vfio/vfio.c:vfio_group_fops_open
  - drivers/vfio/vfio.c:vfio_group_set_container
  - drivers/vfio/vfio.c:vfio_del_group_dev
  - drivers/vfio/vfio.c:vfio_device_get_from_name
  - drivers/vfio/vfio.c:vfio_device_get_from_name
  - drivers/vfio/vfio.c:vfio_add_group_dev
  - drivers/vfio/vfio.c:vfio_iommu_group_notifier
  - drivers/vfio/vfio.c:vfio_group_get_device
  - drivers/vfio/vfio.c:vfio_group_get_device
  - drivers/vfio/vfio.c:vfio_group_get_from_iommu
  - drivers/vfio/vfio.c:vfio_create_group
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff818a0637)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_map
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff818a3585)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_reflck_find
```
```
In drivers/usb/core/hub.c (ffffffff818b47f2)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_activate
```
```
In drivers/usb/core/hcd.c (ffffffff818bbfc5)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_get_hcd
```
```
In drivers/usb/core/urb.c (ffffffff818c0969)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_get_from_anchor
  - drivers/usb/core/urb.c:usb_poison_anchored_urbs
  - drivers/usb/core/urb.c:usb_kill_anchored_urbs
  - drivers/usb/core/urb.c:usb_anchor_urb
```
```
In drivers/usb/core/message.c (ffffffff818c3117)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_set_configuration
```
```
In drivers/usb/core/file.c (ffffffff818c8487)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - drivers/usb/core/file.c:init_usb_class
```
```
In drivers/usb/core/devio.c (ffffffff818ccd5a)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:async_completed
```
```
In drivers/md/dm.c (ffffffff819775c4)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_get_table_device
```
```
In drivers/md/dm-table.c (ffffffff8197c83b)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_get_device
```
```
In drivers/opp/core.c (ffffffff81990f9f)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_adjust_voltage
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:dev_pm_opp_find_freq_ceil_by_volt
  - drivers/opp/core.c:dev_pm_opp_find_freq_floor
  - drivers/opp/core.c:_find_freq_ceil
  - drivers/opp/core.c:dev_pm_opp_find_level_exact
  - drivers/opp/core.c:dev_pm_opp_find_freq_exact
  - drivers/opp/core.c:_find_opp_table_unlocked
```
```
In drivers/remoteproc/remoteproc_virtio.c (ffffffff819cd480)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_virtio.c:rproc_add_virtio_dev
```
```
In drivers/nvmem/core.c (ffffffff819da4fa)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - drivers/nvmem/core.c:__nvmem_device_get
```
```
In net/socket.c (ffffffff819dee97)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - net/socket.c:get_net_ns
```
```
In net/core/sock.c (ffffffff819e61b9)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - net/core/sock.c:sk_reset_timer
  - net/core/sock.c:skb_set_owner_w
  - net/core/sock.c:skb_set_owner_w
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_alloc
```
```
In net/core/skbuff.c (ffffffff819f4387)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_ext_add
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/skbuff.c:sock_zerocopy_realloc
  - net/core/skbuff.c:sock_zerocopy_alloc
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/core/datagram.c (ffffffff819f53a3)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
  - net/core/datagram.c:__skb_try_recv_from_queue
```
```
In net/core/scm.c (ffffffff819f7215)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - net/core/scm.c:scm_fp_dup
  - net/core/scm.c:__scm_send
```
```
In net/core/net_namespace.c (ffffffff819f8d21)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - net/core/net_namespace.c:netns_install
  - net/core/net_namespace.c:netns_get
  - net/core/net_namespace.c:get_net_ns_by_pid
  - net/core/net_namespace.c:get_net_ns_by_fd
  - net/core/net_namespace.c:copy_net_ns
```
```
In net/core/dev.c (ffffffff81a0969d)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:dev_queue_xmit_nit
```
```
In net/core/neighbour.c (ffffffff81a15be0)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:neigh_alloc
```
```
In net/core/rtnetlink.c (ffffffff81a2181e)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnetlink_send
```
```
In net/core/flow_offload.c (ffffffff81a36d2a)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - net/core/flow_offload.c:flow_indr_dev_register
```
```
In net/core/net-sysfs.c (ffffffff81a37cde)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - net/core/net-sysfs.c:net_grab_current_ns
```
```
In net/core/page_pool.c (ffffffff81a3b2ae)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_use_xdp_mem
```
```
In net/core/skmsg.c (ffffffff81a3bf27)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_msg_verdict
  - net/core/skmsg.c:sk_psock_init
```
```
In net/core/netpoll.c (ffffffff81a3e167)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - net/core/netpoll.c:__netpoll_setup
```
```
In net/core/sock_map.c (ffffffff81a4e577)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_free
```
```
In net/core/devlink.c (ffffffff81a5320b)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_health_reporter_get_from_attrs
```
```
In net/sched/sch_generic.c (ffffffff81a66250)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - net/sched/sch_generic.c:attach_default_qdiscs
  - net/sched/sch_generic.c:attach_default_qdiscs
```
```
In net/sched/sch_api.c (ffffffff81a6b271)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
```
```
In net/sched/cls_api.c (ffffffff81a6cd40)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_chain_tp_find
  - net/sched/cls_api.c:tcf_chain_tp_insert_unique
  - net/sched/cls_api.c:__tcf_block_find
  - net/sched/cls_api.c:__tcf_get_next_proto
```
```
In net/sched/act_api.c (ffffffff81a727ca)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_idr_check_alloc
  - net/sched/act_api.c:tcf_idr_search
```
```
In net/netlink/af_netlink.c (ffffffff81a7b267)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:nlmsg_notify
  - net/netlink/af_netlink.c:__netlink_dump_start
  - net/netlink/af_netlink.c:__netlink_dump_start
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:do_one_broadcast
  - net/netlink/af_netlink.c:do_one_broadcast
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:netlink_getsockbyfilp
  - net/netlink/af_netlink.c:netlink_insert
```
```
In net/netfilter/nf_queue.c (ffffffff81a8f733)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
```
```
In net/ipv4/route.c (ffffffff81a937c6)
Location: include/linux/refcount.h:199
Inline: True
```
```
In net/ipv4/ip_fragment.c (ffffffff81a98ee0)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_reinit
```
```
In net/ipv4/ip_output.c (ffffffff81a9ea6d)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/ip_sockglue.c (ffffffff81aa0f5e)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_ra_control
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81aa647e)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
```
```
In net/ipv4/tcp.c (ffffffff81aae074)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/tcp_input.c (ffffffff81ab1854)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
```
```
In net/ipv4/tcp_output.c (ffffffff81abec31)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_tsq_handler
```
```
In net/ipv4/tcp_timer.c (ffffffff81ac225c)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_compressed_ack_kick
  - net/ipv4/tcp_timer.c:tcp_write_timer
  - net/ipv4/tcp_timer.c:tcp_delack_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ac8c69)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
```
```
In net/ipv4/tcp_offload.c (ffffffff81acec33)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/raw.c (ffffffff81ad02b0)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_hash_sk
```
```
In net/ipv4/udp.c (ffffffff81ad6e60)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/udp_offload.c (ffffffff81ad8d22)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
```
```
In net/ipv4/arp.c (ffffffff81adb366)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_constructor
```
```
In net/ipv4/devinet.c (ffffffff81ae199c)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:rtm_to_ifaddr
```
```
In net/ipv4/igmp.c (ffffffff81ae77c0)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - net/ipv4/igmp.c:____ip_mc_inc_group
  - net/ipv4/igmp.c:igmpv3_add_delrec
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_ifc_event
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_start_timer
```
```
In net/ipv4/fib_trie.c (ffffffff81af3cec)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_lookup
```
```
In net/ipv4/inet_fragment.c (ffffffff81af57f8)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:fqdir_init
```
```
In net/ipv4/ping.c (ffffffff81af7c46)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_get_port
```
```
In net/ipv4/nexthop.c (ffffffff81afb0ee)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:__remove_nexthop_fib
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81b0ad83)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_add
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_check
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b11b18)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:clone_policy
  - net/xfrm/xfrm_policy.c:xfrm_sk_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
```
```
In net/xfrm/xfrm_state.c (ffffffff81b1b20b)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:xfrm_state_lookup_byspi
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_dev_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_flush
```
```
In net/xfrm/xfrm_output.c (ffffffff81b20366)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
```
```
In net/unix/af_unix.c (ffffffff81b24a7a)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_shutdown
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:maybe_init_creds
  - net/unix/af_unix.c:unix_getname
  - net/unix/af_unix.c:unix_getname
  - net/unix/af_unix.c:unix_socketpair
  - net/unix/af_unix.c:unix_socketpair
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_find_other
  - net/unix/af_unix.c:unix_find_other
  - net/unix/af_unix.c:unix_autobind
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:copy_peercred
  - net/unix/af_unix.c:init_peercred
```
```
In net/ipv6/anycast.c (ffffffff81b2b733)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
```
```
In net/ipv6/ip6_output.c (ffffffff81b2dd7e)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/addrconf.c (ffffffff81b3e8c9)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_set_iftoken
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_begin
  - net/ipv6/addrconf.c:addrconf_dad_kick
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/addrconf.c:addrconf_add_linklocal
  - net/ipv6/addrconf.c:inet6_addr_del
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_stop
  - net/ipv6/addrconf.c:ipv6_get_ifaddr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
```
```
In net/ipv6/route.c (ffffffff81b44144)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:ip6_route_check_nh
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:ip6_blackhole_route
  - net/ipv6/route.c:ip6_rt_copy_init
  - net/ipv6/route.c:ip6_rt_copy_init
  - net/ipv6/route.c:ip6_dst_ifdown
```
```
In net/ipv6/ip6_fib.c (ffffffff81b4ee16)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_purge_rt
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81b50908)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:ip6_ra_control
```
```
In net/ipv6/ndisc.c (ffffffff81b54507)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_ifinfo_sysctl_change
  - net/ipv6/ndisc.c:ndisc_netdev_event
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_send_unsol_na
  - net/ipv6/ndisc.c:ndisc_constructor
  - net/ipv6/ndisc.c:ndisc_constructor
```
```
In net/ipv6/mcast.c (ffffffff81b62f99)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_dad_timer_expire
  - net/ipv6/mcast.c:ipv6_mc_dad_complete
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/mcast.c:mld_add_delrec
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b6a834)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_req
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81b781dd)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
```
```
In net/ipv6/syncookies.c (ffffffff81b7bbea)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/calipso.c (ffffffff81b7c5be)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_cache_check
```
```
In net/packet/af_packet.c (ffffffff81b891c7)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_create
  - net/packet/af_packet.c:tpacket_fill_skb
  - net/packet/af_packet.c:tpacket_rcv
```
```
In net/ncsi/ncsi-cmd.c (ffffffff81b9ed4a)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81ba55a8)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
  - net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
```
```
In net/xdp/xsk.c (ffffffff81ba6fdf)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_create
```
```
In net/xdp/xdp_umem.c (ffffffff81ba854d)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_reg
  - net/xdp/xdp_umem.c:xdp_get_umem
```
```
In net/mptcp/protocol.c (ffffffff81babe96)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_stream_accept
  - net/mptcp/protocol.c:mptcp_accept
  - net/mptcp/protocol.c:mptcp_retransmit_timer
  - net/mptcp/protocol.c:mptcp_subflow_eof
  - net/mptcp/protocol.c:mptcp_data_acked
  - net/mptcp/protocol.c:mptcp_data_ready
```
```
In net/mptcp/subflow.c (ffffffff81bafbc0)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
```
```
In net/mptcp/token.c (ffffffff81bb1cb0)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - net/mptcp/token.c:mptcp_token_get_sock
```
```
In net/mptcp/pm.c (ffffffff81bb22e8)
Location: include/linux/refcount.h:199
Inline: True
Inline callers:
  - net/mptcp/pm.c:mptcp_pm_schedule_work
```
**Symbols:**

```
ffffffff810a4450-ffffffff810a4482: refcount_add.constprop.0 (STB_LOCAL)
ffffffff81231a00-ffffffff81231a32: refcount_add.constprop.0 (STB_LOCAL)
ffffffff81255680-ffffffff812556b2: refcount_add.constprop.0 (STB_LOCAL)
ffffffff814fcda0-ffffffff814fcdd2: refcount_add.constprop.0 (STB_LOCAL)
ffffffff81500090-ffffffff815000c2: refcount_add.constprop.0 (STB_LOCAL)
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
In mm/memcontrol.c (ffffffff8130a380)
Location: include/linux/refcount.h:220
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
```
```
In fs/io_uring.c (ffffffff8138e1a0)
Location: include/linux/refcount.h:220
Inline: True
Inline callers:
  - fs/io_uring.c:__io_sqe_files_scm
  - fs/io_uring.c:io_submit_sqes
```
```
In net/core/sock.c (ffffffff819e5335)
Location: include/linux/refcount.h:220
Inline: True
Inline callers:
  - net/core/sock.c:skb_set_owner_w
```
```
In net/core/datagram.c (ffffffff819f4dd0)
Location: include/linux/refcount.h:220
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
```
```
In net/ipv4/ip_output.c (ffffffff81aa89b7)
Location: include/linux/refcount.h:220
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp_output.c (ffffffff81ac9a10)
Location: include/linux/refcount.h:220
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_offload.c (ffffffff81adac53)
Location: include/linux/refcount.h:220
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp_offload.c (ffffffff81ae5232)
Location: include/linux/refcount.h:220
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
```
```
In net/unix/af_unix.c (ffffffff81b3597b)
Location: include/linux/refcount.h:220
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_sendpage
```
```
In net/ipv6/ip6_output.c (ffffffff81b3d541)
Location: include/linux/refcount.h:220
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81b977e6)
Location: include/linux/refcount.h:220
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_fill_skb
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
In mm/memcontrol.c (ffffffff81310c0a)
Location: include/linux/refcount.h:220
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
```
```
In fs/io_uring.c (ffffffff81394127)
Location: include/linux/refcount.h:220
Inline: True
Inline callers:
  - fs/io_uring.c:__io_sqe_files_scm
  - fs/io_uring.c:io_submit_sqes
```
```
In net/core/sock.c (ffffffff819cb365)
Location: include/linux/refcount.h:220
Inline: True
Inline callers:
  - net/core/sock.c:skb_set_owner_w
```
```
In net/core/datagram.c (ffffffff819daf60)
Location: include/linux/refcount.h:220
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
```
```
In net/ipv4/ip_output.c (ffffffff81a93ad7)
Location: include/linux/refcount.h:220
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp_output.c (ffffffff81ab489c)
Location: include/linux/refcount.h:220
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_offload.c (ffffffff81ac5c93)
Location: include/linux/refcount.h:220
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp_offload.c (ffffffff81ad0484)
Location: include/linux/refcount.h:220
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
```
```
In net/unix/af_unix.c (ffffffff81b23565)
Location: include/linux/refcount.h:220
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_sendpage
```
```
In net/ipv6/ip6_output.c (ffffffff81b2a9d8)
Location: include/linux/refcount.h:220
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81b867e8)
Location: include/linux/refcount.h:220
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_fill_skb
```
```
In net/xdp/xsk.c (ffffffff81ba5382)
Location: include/linux/refcount.h:220
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_build_skb_zerocopy
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
In mm/memcontrol.c (ffffffff8135be73)
Location: include/linux/refcount.h:220
Inline: True
Inline callers:
  - mm/memcontrol.c:__mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
```
```
In fs/io_uring.c (ffffffff813e1be8)
Location: include/linux/refcount.h:220
Inline: True
Inline callers:
  - fs/io_uring.c:__io_sqe_files_scm
  - fs/io_uring.c:io_submit_sqes
```
```
In net/core/sock.c (ffffffff81a7a9e6)
Location: include/linux/refcount.h:220
Inline: True
Inline callers:
  - net/core/sock.c:skb_set_owner_w
```
```
In net/core/skbuff.c (ffffffff81a863cd)
Location: include/linux/refcount.h:220
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_expand_head
```
```
In net/core/datagram.c (ffffffff81a8b5ff)
Location: include/linux/refcount.h:220
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
```
```
In net/ipv4/ip_output.c (ffffffff81b4ef17)
Location: include/linux/refcount.h:220
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp_output.c (ffffffff81b7185c)
Location: include/linux/refcount.h:220
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_offload.c (ffffffff81b84471)
Location: include/linux/refcount.h:220
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp_offload.c (ffffffff81b8eea2)
Location: include/linux/refcount.h:220
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
```
```
In net/unix/af_unix.c (ffffffff81be79f5)
Location: include/linux/refcount.h:220
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_sendpage
```
```
In net/ipv6/ip6_output.c (ffffffff81bf0a7d)
Location: include/linux/refcount.h:220
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81c52ba8)
Location: include/linux/refcount.h:220
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_fill_skb
```
```
In net/xdp/xsk.c (ffffffff81c72f0a)
Location: include/linux/refcount.h:220
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_build_skb_zerocopy
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
In mm/memcontrol.c (ffffffff813d58a0)
Location: include/linux/refcount.h:220
Inline: True
Inline callers:
  - mm/memcontrol.c:__mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
```
```
In io_uring/io_uring.c (ffffffff816d6530)
Location: include/linux/refcount.h:220
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_submit_sqes
```
```
In net/core/sock.c (ffffffff81bee8c6)
Location: include/linux/refcount.h:220
Inline: True
```
```
In net/core/skbuff.c (ffffffff81bfb63b)
Location: include/linux/refcount.h:220
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_expand_head
```
```
In net/core/datagram.c (ffffffff81c00c1f)
Location: include/linux/refcount.h:220
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
```
```
In net/ipv4/ip_output.c (ffffffff81cdc85d)
Location: include/linux/refcount.h:220
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp_output.c (ffffffff81d00fbf)
Location: include/linux/refcount.h:220
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_offload.c (ffffffff81d14c3f)
Location: include/linux/refcount.h:220
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp_offload.c (ffffffff81d1fb0b)
Location: include/linux/refcount.h:220
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
```
```
In net/unix/af_unix.c (ffffffff81d80948)
Location: include/linux/refcount.h:220
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_sendpage
```
```
In net/ipv6/ip6_output.c (ffffffff81d8918f)
Location: include/linux/refcount.h:220
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81df67d7)
Location: include/linux/refcount.h:220
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_fill_skb
```
```
In net/xdp/xsk.c (ffffffff81e17d55)
Location: include/linux/refcount.h:220
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_build_skb_zerocopy
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
In mm/memcontrol.c (ffffffff8145b2f3)
Location: include/linux/refcount.h:220
Inline: True
Inline callers:
  - mm/memcontrol.c:__mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
```
```
In io_uring/io_uring.c (ffffffff8178d34d)
Location: include/linux/refcount.h:220
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_task_refs_refill
```
```
In io_uring/net.c (ffffffff81795d11)
Location: include/linux/refcount.h:220
Inline: True
Inline callers:
  - io_uring/net.c:io_sg_from_iter
```
```
In io_uring/rsrc.c (ffffffff817a1567)
Location: include/linux/refcount.h:220
Inline: True
Inline callers:
  - io_uring/rsrc.c:__io_scm_file_account
```
```
In net/core/sock.c (ffffffff81d9aef6)
Location: include/linux/refcount.h:220
Inline: True
```
```
In net/core/skbuff.c (ffffffff81daa7cb)
Location: include/linux/refcount.h:220
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_expand_head
```
```
In net/core/datagram.c (ffffffff81db0090)
Location: include/linux/refcount.h:220
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
```
```
In net/ipv4/ip_output.c (ffffffff81e9d2bd)
Location: include/linux/refcount.h:220
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp_output.c (ffffffff81ec611f)
Location: include/linux/refcount.h:220
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_offload.c (ffffffff81edad7f)
Location: include/linux/refcount.h:220
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp_offload.c (ffffffff81ee6cfb)
Location: include/linux/refcount.h:220
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
```
```
In net/unix/af_unix.c (ffffffff81f4e4a8)
Location: include/linux/refcount.h:220
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_sendpage
```
```
In net/ipv6/ip6_output.c (ffffffff81f56f65)
Location: include/linux/refcount.h:220
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81fcad96)
Location: include/linux/refcount.h:220
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_fill_skb
```
```
In net/xdp/xsk.c (ffffffff81feeef5)
Location: include/linux/refcount.h:220
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_build_skb_zerocopy
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
In mm/memcontrol.c (ffffffff81490f63)
Location: include/linux/refcount.h:220
Inline: True
Inline callers:
  - mm/memcontrol.c:__mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
```
```
In io_uring/io_uring.c (ffffffff817ce72d)
Location: include/linux/refcount.h:220
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_task_refs_refill
```
```
In io_uring/net.c (ffffffff817d699e)
Location: include/linux/refcount.h:220
Inline: True
Inline callers:
  - io_uring/net.c:io_sg_from_iter
```
```
In io_uring/rsrc.c (ffffffff817e275f)
Location: include/linux/refcount.h:220
Inline: True
Inline callers:
  - io_uring/rsrc.c:__io_scm_file_account
```
```
In net/core/sock.c (ffffffff81e0a0ff)
Location: include/linux/refcount.h:220
Inline: True
```
```
In net/core/skbuff.c (ffffffff81e1a21b)
Location: include/linux/refcount.h:220
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_expand_head
```
```
In net/core/datagram.c (ffffffff81e202d9)
Location: include/linux/refcount.h:220
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
```
```
In net/ipv4/ip_output.c (ffffffff81efa2a8)
Location: include/linux/refcount.h:220
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp_output.c (ffffffff81f24864)
Location: include/linux/refcount.h:220
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_offload.c (ffffffff81f39e5a)
Location: include/linux/refcount.h:220
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp_offload.c (ffffffff81f4659a)
Location: include/linux/refcount.h:220
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
```
```
In net/unix/af_unix.c (ffffffff81faddd5)
Location: include/linux/refcount.h:220
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_sendmsg
```
```
In net/ipv6/ip6_output.c (ffffffff81fb6b2b)
Location: include/linux/refcount.h:220
Inline: True
```
```
In net/packet/af_packet.c (ffffffff8202c015)
Location: include/linux/refcount.h:220
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_fill_skb
```
```
In net/xdp/xsk.c (ffffffff8206ae8e)
Location: include/linux/refcount.h:220
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_build_skb_zerocopy
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
In mm/memcontrol.c (ffffffff814c08d0)
Location: include/linux/refcount.h:209
Inline: True
Inline callers:
  - mm/memcontrol.c:__mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
```
```
In io_uring/io_uring.c (ffffffff818119dd)
Location: include/linux/refcount.h:209
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_task_refs_refill
```
```
In io_uring/net.c (ffffffff8181ab6e)
Location: include/linux/refcount.h:209
Inline: True
Inline callers:
  - io_uring/net.c:io_sg_from_iter
```
```
In net/core/sock.c (ffffffff81ec6aef)
Location: include/linux/refcount.h:209
Inline: True
```
```
In net/core/skbuff.c (ffffffff81ed77db)
Location: include/linux/refcount.h:209
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_expand_head
```
```
In net/core/datagram.c (ffffffff81ede1b9)
Location: include/linux/refcount.h:209
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
```
```
In net/ipv4/ip_output.c (ffffffff81fbe1d6)
Location: include/linux/refcount.h:209
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp_output.c (ffffffff81fe9049)
Location: include/linux/refcount.h:209
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_offload.c (ffffffff81ffff4a)
Location: include/linux/refcount.h:209
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp_offload.c (ffffffff8200c6da)
Location: include/linux/refcount.h:209
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
```
```
In net/unix/af_unix.c (ffffffff8207a6a5)
Location: include/linux/refcount.h:209
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_sendmsg
```
```
In net/ipv6/ip6_output.c (ffffffff820842b0)
Location: include/linux/refcount.h:209
Inline: True
```
```
In net/packet/af_packet.c (ffffffff820fbac5)
Location: include/linux/refcount.h:209
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_fill_skb
```
```
In net/xdp/xsk.c (ffffffff8213eb8e)
Location: include/linux/refcount.h:209
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_build_skb
  - net/xdp/xsk.c:xsk_build_skb_zerocopy
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (c00000000045aec0)
Location: include/linux/refcount.h:79
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:__mem_cgroup_clear_mc
```
```
In fs/io_uring.c (c000000000510b5c)
Location: include/linux/refcount.h:79
Inline: True
Inline callers:
  - fs/io_uring.c:__se_sys_io_uring_register
```
```
In net/core/sock.c (c000000000c81ac0)
Location: include/linux/refcount.h:79
Inline: True
```
```
In net/core/datagram.c (c000000000c95300)
Location: include/linux/refcount.h:79
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
```
```
In net/ipv4/ip_output.c (c000000000d693f0)
Location: include/linux/refcount.h:79
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp_output.c (c000000000d8f6c4)
Location: include/linux/refcount.h:79
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_offload.c (c000000000da6668)
Location: include/linux/refcount.h:79
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp_offload.c (c000000000db36b4)
Location: include/linux/refcount.h:79
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
```
```
In net/unix/af_unix.c (c000000000e167c8)
Location: include/linux/refcount.h:79
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_sendpage
```
```
In net/ipv6/ip6_output.c (c000000000e20ea8)
Location: include/linux/refcount.h:79
Inline: True
```
```
In net/packet/af_packet.c (c000000000e94de0)
Location: include/linux/refcount.h:79
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_snd
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
In mm/memcontrol.c (ffffffe000244686)
Location: include/linux/refcount.h:79
Inline: True
Inline callers:
  - mm/memcontrol.c:__mem_cgroup_clear_mc
```
```
In fs/io_uring.c (ffffffe0002b1384)
Location: include/linux/refcount.h:79
Inline: True
Inline callers:
  - fs/io_uring.c:__se_sys_io_uring_register
```
```
In net/core/sock.c (ffffffe00073ec40)
Location: include/linux/refcount.h:79
Inline: True
Inline callers:
  - net/core/sock.c:skb_set_owner_w
```
```
In net/core/datagram.c (ffffffe00074aece)
Location: include/linux/refcount.h:79
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
```
```
In net/ipv4/ip_output.c (ffffffe0007cc914)
Location: include/linux/refcount.h:79
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp_output.c (ffffffe0007e57f8)
Location: include/linux/refcount.h:79
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_offload.c (ffffffe0007f4868)
Location: include/linux/refcount.h:79
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp_offload.c (ffffffe0007fd27e)
Location: include/linux/refcount.h:79
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
```
```
In net/unix/af_unix.c (ffffffe00083e4d0)
Location: include/linux/refcount.h:79
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_sendpage
```
```
In net/ipv6/ip6_output.c (ffffffe0008450b8)
Location: include/linux/refcount.h:79
Inline: True
```
```
In net/packet/af_packet.c (ffffffe000891504)
Location: include/linux/refcount.h:79
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_snd
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
In mm/memcontrol.c (ffffffff812b7895)
Location: arch/x86/include/asm/refcount.h:42
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_id_get_many
```
```
In fs/io_uring.c (ffffffff8133e26a)
Location: arch/x86/include/asm/refcount.h:42
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_register
```
```
In net/core/sock.c (ffffffff818b3894)
Location: arch/x86/include/asm/refcount.h:42
Inline: True
Inline callers:
  - net/core/sock.c:skb_set_owner_w
```
```
In net/core/datagram.c (ffffffff818c1abb)
Location: arch/x86/include/asm/refcount.h:42
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
```
```
In net/ipv4/ip_output.c (ffffffff81954723)
Location: arch/x86/include/asm/refcount.h:42
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp_output.c (ffffffff81970f19)
Location: arch/x86/include/asm/refcount.h:42
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_offload.c (ffffffff81981431)
Location: arch/x86/include/asm/refcount.h:42
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp_offload.c (ffffffff8198aef5)
Location: arch/x86/include/asm/refcount.h:42
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
```
```
In net/unix/af_unix.c (ffffffff819d1c1c)
Location: arch/x86/include/asm/refcount.h:42
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_sendpage
```
```
In net/ipv6/ip6_output.c (ffffffff819d8957)
Location: arch/x86/include/asm/refcount.h:42
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81a2cda6)
Location: arch/x86/include/asm/refcount.h:42
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_snd
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
In mm/memcontrol.c (ffffffff812a8a65)
Location: arch/x86/include/asm/refcount.h:42
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_id_get_many
```
```
In fs/io_uring.c (ffffffff8132ef2a)
Location: arch/x86/include/asm/refcount.h:42
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_register
```
```
In net/core/sock.c (ffffffff8186d7e4)
Location: arch/x86/include/asm/refcount.h:42
Inline: True
Inline callers:
  - net/core/sock.c:skb_set_owner_w
```
```
In net/core/datagram.c (ffffffff8187b9fb)
Location: arch/x86/include/asm/refcount.h:42
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
```
```
In net/ipv4/ip_output.c (ffffffff8190e213)
Location: arch/x86/include/asm/refcount.h:42
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp_output.c (ffffffff8192a9e9)
Location: arch/x86/include/asm/refcount.h:42
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_offload.c (ffffffff8193aef1)
Location: arch/x86/include/asm/refcount.h:42
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp_offload.c (ffffffff819449b5)
Location: arch/x86/include/asm/refcount.h:42
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
```
```
In net/unix/af_unix.c (ffffffff8198e9dc)
Location: arch/x86/include/asm/refcount.h:42
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_sendpage
```
```
In net/ipv6/ip6_output.c (ffffffff81995717)
Location: arch/x86/include/asm/refcount.h:42
Inline: True
```
```
In net/packet/af_packet.c (ffffffff819e9f96)
Location: arch/x86/include/asm/refcount.h:42
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_snd
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
In mm/memcontrol.c (ffffffff812b56a5)
Location: arch/x86/include/asm/refcount.h:42
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_id_get_many
```
```
In fs/io_uring.c (ffffffff8133bd3a)
Location: arch/x86/include/asm/refcount.h:42
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_register
```
```
In net/core/sock.c (ffffffff81904894)
Location: arch/x86/include/asm/refcount.h:42
Inline: True
Inline callers:
  - net/core/sock.c:skb_set_owner_w
```
```
In net/core/datagram.c (ffffffff81912abb)
Location: arch/x86/include/asm/refcount.h:42
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
```
```
In net/netfilter/nf_conntrack_expect.c (ffffffff819a28dd)
Location: arch/x86/include/asm/refcount.h:42
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_expect.c:nf_ct_expect_related_report
```
```
In net/ipv4/ip_output.c (ffffffff819beef3)
Location: arch/x86/include/asm/refcount.h:42
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp_output.c (ffffffff819db6e9)
Location: arch/x86/include/asm/refcount.h:42
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_offload.c (ffffffff819ebc01)
Location: arch/x86/include/asm/refcount.h:42
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp_offload.c (ffffffff819f56c5)
Location: arch/x86/include/asm/refcount.h:42
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
```
```
In net/unix/af_unix.c (ffffffff81a3c69c)
Location: arch/x86/include/asm/refcount.h:42
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_sendpage
```
```
In net/ipv6/ip6_output.c (ffffffff81a433d7)
Location: arch/x86/include/asm/refcount.h:42
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81a98956)
Location: arch/x86/include/asm/refcount.h:42
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_snd
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
In mm/memcontrol.c (ffffffff812c5bc5)
Location: arch/x86/include/asm/refcount.h:42
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_id_get_many
```
```
In fs/io_uring.c (ffffffff8134eeea)
Location: arch/x86/include/asm/refcount.h:42
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_register
```
```
In net/core/sock.c (ffffffff81925934)
Location: arch/x86/include/asm/refcount.h:42
Inline: True
Inline callers:
  - net/core/sock.c:skb_set_owner_w
```
```
In net/core/datagram.c (ffffffff81933c3b)
Location: arch/x86/include/asm/refcount.h:42
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
```
```
In net/ipv4/ip_output.c (ffffffff819c8875)
Location: arch/x86/include/asm/refcount.h:42
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/tcp_output.c (ffffffff819e5369)
Location: arch/x86/include/asm/refcount.h:42
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_offload.c (ffffffff819f5ab1)
Location: arch/x86/include/asm/refcount.h:42
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp_offload.c (ffffffff819ff8c5)
Location: arch/x86/include/asm/refcount.h:42
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
```
```
In net/unix/af_unix.c (ffffffff81a47327)
Location: arch/x86/include/asm/refcount.h:42
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_sendpage
```
```
In net/ipv6/ip6_output.c (ffffffff81a4f077)
Location: arch/x86/include/asm/refcount.h:42
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81aa4ff0)
Location: arch/x86/include/asm/refcount.h:42
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_snd
```
</details>
</li>
</ul>

## Differences
