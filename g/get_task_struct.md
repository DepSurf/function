# Function: <code>get_task_struct</code>

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
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
struct task_struct *get_task_struct(struct task_struct *t);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105ca1e)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
```
```
In kernel/fork.c (ffffffff810a0559)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
```
```
In kernel/exit.c (ffffffff810a5747)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:mm_update_next_owner
```
```
In kernel/sys.c (ffffffff810bc6a1)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_prlimit64
  - kernel/sys.c:__x64_sys_prlimit64
```
```
In kernel/pid.c (ffffffff810c59cc)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/pid.c:get_pid_task
  - kernel/pid.c:find_get_task_by_vpid
```
```
In kernel/kthread.c (ffffffff810c8e26)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_stop
```
```
In kernel/smpboot.c (ffffffff810cf44d)
Location: include/linux/sched/task.h:108
Inline: True
```
```
In kernel/sched/core.c (ffffffff810dca00)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__ia32_sys_sched_setattr
  - kernel/sched/core.c:__x64_sys_sched_setattr
  - kernel/sched/core.c:do_sched_setscheduler
  - kernel/sched/core.c:wake_q_add
```
```
In kernel/sched/fair.c (ffffffff810e3c16)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_find_cpu
```
```
In kernel/sched/rt.c (ffffffff810ef85c)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/sched/rt.c:push_rt_task
```
```
In kernel/sched/deadline.c (ffffffff810f12d8)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/sched/deadline.c:start_dl_timer
  - kernel/sched/deadline.c:task_non_contending
```
```
In kernel/locking/rwsem.c (ffffffff81103ab2)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_mark_wake
```
```
In kernel/locking/rtmutex.c (ffffffff81105e97)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_adjust_pi
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:task_blocks_on_rt_mutex
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
```
```
In kernel/irq/manage.c (ffffffff8111723e)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/irq/manage.c:setup_irq_thread
```
```
In kernel/rcu/update.c (ffffffff81123aad)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/kcmp.c (ffffffff81130922)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/kcmp.c:__do_sys_kcmp
```
```
In kernel/time/posix-cpu-timers.c (ffffffff81143182)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:__get_task_for_clock
```
```
In kernel/futex.c (ffffffff8114a1cb)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/futex.c:mark_wake_futex
```
```
In kernel/cgroup/cgroup.c (ffffffff81165f40)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_task_iter_next
  - kernel/cgroup/cgroup.c:cgroup_procs_write_start
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81168abb)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
```
In kernel/hung_task.c (ffffffff8118f79f)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/hung_task.c:watchdog
  - kernel/hung_task.c:watchdog
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811b2b25)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In kernel/events/core.c (ffffffff81213716)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:alloc_perf_context
```
```
In mm/oom_kill.c (ffffffff81227fd0)
Location: include/linux/sched/task.h:108
Inline: True
Direct callers:
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/page_io.c (ffffffff812864aa)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
```
```
In mm/mempolicy.c (ffffffff8129903f)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_migrate_pages
```
```
In mm/migrate.c (ffffffff812b1ee7)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - mm/migrate.c:kernel_move_pages
```
```
In mm/memory-failure.c (ffffffff812cab76)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - mm/memory-failure.c:add_to_kill
```
```
In fs/proc/base.c (ffffffff81376b39)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_lookup
  - fs/proc/base.c:next_tgid
  - fs/proc/base.c:proc_pid_lookup
```
```
In security/yama/yama_lsm.c (ffffffff814b2bc9)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_task_prctl
  - security/yama/yama_lsm.c:report_access
  - security/yama/yama_lsm.c:report_access
```
```
In drivers/tty/tty_ldsem.c (ffffffff81ad3e9f)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_read
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff817d565a)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_map
```
**Symbols:**

```
ffffffff81227fd0-ffffffff81227fde: get_task_struct (STB_LOCAL)
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81061b66)
Location: include/linux/sched/task.h:115
Inline: True
```
```
In kernel/fork.c (ffffffff810a7428)
Location: include/linux/sched/task.h:115
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
```
```
In kernel/exit.c (ffffffff810ac46b)
Location: include/linux/sched/task.h:115
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_continued
  - kernel/exit.c:wait_task_stopped
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:mm_update_next_owner
```
```
In kernel/sys.c (ffffffff810c3fe7)
Location: include/linux/sched/task.h:115
Inline: True
Inline callers:
  - kernel/sys.c:__do_sys_prlimit64
```
```
In kernel/pid.c (ffffffff810cd8db)
Location: include/linux/sched/task.h:115
Inline: True
Inline callers:
  - kernel/pid.c:pidfd_getfd
  - kernel/pid.c:find_get_task_by_vpid
```
```
In kernel/kthread.c (ffffffff810d0a38)
Location: include/linux/sched/task.h:115
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_stop
```
```
In kernel/smpboot.c (ffffffff810d92c1)
Location: include/linux/sched/task.h:115
Inline: True
```
```
In kernel/sched/core.c (ffffffff810e5581)
Location: include/linux/sched/task.h:115
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__ia32_sys_sched_setattr
  - kernel/sched/core.c:__x64_sys_sched_setattr
  - kernel/sched/core.c:do_sched_setscheduler
  - kernel/sched/core.c:wake_q_add
```
```
In kernel/sched/fair.c (ffffffff810eb9f5)
Location: include/linux/sched/task.h:115
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_assign
```
```
In kernel/sched/rt.c (ffffffff810f92d8)
Location: include/linux/sched/task.h:115
Inline: True
Inline callers:
  - kernel/sched/rt.c:push_rt_task
```
```
In kernel/sched/deadline.c (ffffffff810fa745)
Location: include/linux/sched/task.h:115
Inline: True
Inline callers:
  - kernel/sched/deadline.c:start_dl_timer
  - kernel/sched/deadline.c:task_non_contending
```
```
In kernel/locking/rwsem.c (ffffffff8110e60e)
Location: include/linux/sched/task.h:115
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_mark_wake
```
```
In kernel/locking/percpu-rwsem.c (ffffffff8110f4eb)
Location: include/linux/sched/task.h:115
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:percpu_rwsem_wake_function
```
```
In kernel/locking/rtmutex.c (ffffffff81110de7)
Location: include/linux/sched/task.h:115
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_adjust_pi
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:task_blocks_on_rt_mutex
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
```
```
In kernel/irq/manage.c (ffffffff81122e5e)
Location: include/linux/sched/task.h:115
Inline: True
Inline callers:
  - kernel/irq/manage.c:setup_irq_thread
```
```
In kernel/rcu/update.c (ffffffff81130a92)
Location: include/linux/sched/task.h:115
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_trace_postgp
```
```
In kernel/kcmp.c (ffffffff8113fd33)
Location: include/linux/sched/task.h:115
Inline: True
Inline callers:
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/kcmp.c:__do_sys_kcmp
```
```
In kernel/futex.c (ffffffff8115adbb)
Location: include/linux/sched/task.h:115
Inline: True
Inline callers:
  - kernel/futex.c:mark_wake_futex
```
```
In kernel/cgroup/cgroup.c (ffffffff8117707a)
Location: include/linux/sched/task.h:115
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_task_iter_next
  - kernel/cgroup/cgroup.c:cgroup_procs_write_start
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8117a7fd)
Location: include/linux/sched/task.h:115
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
```
In kernel/hung_task.c (ffffffff811a42b0)
Location: include/linux/sched/task.h:115
Inline: True
Inline callers:
  - kernel/hung_task.c:check_hung_uninterruptible_tasks
  - kernel/hung_task.c:check_hung_uninterruptible_tasks
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811cb022)
Location: include/linux/sched/task.h:115
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In kernel/events/core.c (ffffffff8123f6d9)
Location: include/linux/sched/task.h:115
Inline: True
Inline callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:alloc_perf_context
```
```
In mm/oom_kill.c (ffffffff81256865)
Location: include/linux/sched/task.h:115
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/page_io.c (ffffffff812b8777)
Location: include/linux/sched/task.h:115
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
```
```
In mm/mempolicy.c (ffffffff812cd18f)
Location: include/linux/sched/task.h:115
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_migrate_pages
```
```
In mm/migrate.c (ffffffff812e73d7)
Location: include/linux/sched/task.h:115
Inline: True
Inline callers:
  - mm/migrate.c:kernel_move_pages
```
```
In mm/memory-failure.c (ffffffff813009c9)
Location: include/linux/sched/task.h:115
Inline: True
Inline callers:
  - mm/memory-failure.c:add_to_kill
```
```
In fs/io_uring.c (ffffffff8137db7d)
Location: include/linux/sched/task.h:115
Inline: True
Inline callers:
  - fs/io_uring.c:io_poll_add_prep
  - fs/io_uring.c:io_arm_poll_handler
```
```
In fs/proc/base.c (ffffffff813bf7fd)
Location: include/linux/sched/task.h:115
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_lookup
  - fs/proc/base.c:next_tgid
  - fs/proc/base.c:proc_pid_lookup
```
```
In ipc/msg.c (ffffffff814881d3)
Location: include/linux/sched/task.h:115
Inline: True
Inline callers:
  - ipc/msg.c:expunge_all
```
```
In ipc/sem.c (ffffffff8148b2c0)
Location: include/linux/sched/task.h:115
Inline: True
Inline callers:
  - ipc/sem.c:freeary
  - ipc/sem.c:freeary
  - ipc/sem.c:freeary
  - ipc/sem.c:freeary
  - ipc/sem.c:update_queue
  - ipc/sem.c:wake_const_ops
```
```
In ipc/mqueue.c (ffffffff81494127)
Location: include/linux/sched/task.h:115
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
```
```
In security/yama/yama_lsm.c (ffffffff81511fae)
Location: include/linux/sched/task.h:115
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_task_prctl
  - security/yama/yama_lsm.c:report_access
  - security/yama/yama_lsm.c:report_access
```
```
In drivers/tty/tty_ldsem.c (ffffffff81bcbe84)
Location: include/linux/sched/task.h:115
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:down_read_failed
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff818a0627)
Location: include/linux/sched/task.h:115
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_map
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105ff76)
Location: include/linux/sched/task.h:100
Inline: True
```
```
In kernel/fork.c (ffffffff810a3105)
Location: include/linux/sched/task.h:100
Inline: True
Inline callers:
  - kernel/fork.c:kernel_clone
```
```
In kernel/exit.c (ffffffff810a7b24)
Location: include/linux/sched/task.h:100
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_continued
  - kernel/exit.c:wait_task_stopped
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:mm_update_next_owner
```
```
In kernel/sys.c (ffffffff810bf3ba)
Location: include/linux/sched/task.h:100
Inline: True
Inline callers:
  - kernel/sys.c:__do_sys_prlimit64
```
```
In kernel/pid.c (ffffffff810c83fb)
Location: include/linux/sched/task.h:100
Inline: True
Inline callers:
  - kernel/pid.c:pidfd_getfd
  - kernel/pid.c:find_get_task_by_vpid
```
```
In kernel/kthread.c (ffffffff810cb2b8)
Location: include/linux/sched/task.h:100
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_stop
```
```
In kernel/smpboot.c (ffffffff810d446c)
Location: include/linux/sched/task.h:100
Inline: True
```
```
In kernel/sched/core.c (ffffffff810dc82d)
Location: include/linux/sched/task.h:100
Inline: True
Inline callers:
  - kernel/sched/core.c:balance_push
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__ia32_sys_sched_setattr
  - kernel/sched/core.c:__x64_sys_sched_setattr
  - kernel/sched/core.c:do_sched_setscheduler
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/core.c:wake_q_add
```
```
In kernel/sched/fair.c (ffffffff810e9818)
Location: include/linux/sched/task.h:100
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_assign
```
```
In kernel/sched/rt.c (ffffffff810f7967)
Location: include/linux/sched/task.h:100
Inline: True
Inline callers:
  - kernel/sched/rt.c:pull_rt_task
```
```
In kernel/sched/deadline.c (ffffffff810fb8d9)
Location: include/linux/sched/task.h:100
Inline: True
Inline callers:
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:start_dl_timer
  - kernel/sched/deadline.c:task_non_contending
```
```
In kernel/locking/rwsem.c (ffffffff8110b88f)
Location: include/linux/sched/task.h:100
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_mark_wake
```
```
In kernel/locking/percpu-rwsem.c (ffffffff8110c6ab)
Location: include/linux/sched/task.h:100
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:percpu_rwsem_wake_function
```
```
In kernel/locking/rtmutex.c (ffffffff8110df97)
Location: include/linux/sched/task.h:100
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_adjust_pi
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:task_blocks_on_rt_mutex
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
```
```
In kernel/irq/manage.c (ffffffff8111eccf)
Location: include/linux/sched/task.h:100
Inline: True
Inline callers:
  - kernel/irq/manage.c:setup_irq_thread
```
```
In kernel/rcu/update.c (ffffffff8112c7a2)
Location: include/linux/sched/task.h:100
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_trace_postgp
```
```
In kernel/kcmp.c (ffffffff8113c073)
Location: include/linux/sched/task.h:100
Inline: True
Inline callers:
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/kcmp.c:__do_sys_kcmp
```
```
In kernel/futex.c (ffffffff81156ebb)
Location: include/linux/sched/task.h:100
Inline: True
Inline callers:
  - kernel/futex.c:mark_wake_futex
```
```
In kernel/cgroup/cgroup.c (ffffffff81173d5a)
Location: include/linux/sched/task.h:100
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_task_iter_next
  - kernel/cgroup/cgroup.c:cgroup_procs_write_start
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff811775f0)
Location: include/linux/sched/task.h:100
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
```
In kernel/hung_task.c (ffffffff811a1400)
Location: include/linux/sched/task.h:100
Inline: True
Inline callers:
  - kernel/hung_task.c:check_hung_uninterruptible_tasks
  - kernel/hung_task.c:check_hung_uninterruptible_tasks
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811c8702)
Location: include/linux/sched/task.h:100
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In kernel/events/core.c (ffffffff81249a14)
Location: include/linux/sched/task.h:100
Inline: True
Inline callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:alloc_perf_context
```
```
In mm/oom_kill.c (ffffffff812613ca)
Location: include/linux/sched/task.h:100
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/page_io.c (ffffffff812c3e75)
Location: include/linux/sched/task.h:100
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
```
```
In mm/mempolicy.c (ffffffff812d9a1f)
Location: include/linux/sched/task.h:100
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_migrate_pages
```
```
In mm/migrate.c (ffffffff812ed058)
Location: include/linux/sched/task.h:100
Inline: True
Inline callers:
  - mm/migrate.c:find_mm_struct
```
```
In mm/memory-failure.c (ffffffff8130cb69)
Location: include/linux/sched/task.h:100
Inline: True
Inline callers:
  - mm/memory-failure.c:add_to_kill
```
```
In fs/io_uring.c (ffffffff81396935)
Location: include/linux/sched/task.h:100
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
```
```
In fs/proc/base.c (ffffffff813d167d)
Location: include/linux/sched/task.h:100
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_lookup
  - fs/proc/base.c:next_tgid
  - fs/proc/base.c:proc_pid_lookup
```
```
In ipc/msg.c (ffffffff814a57f3)
Location: include/linux/sched/task.h:100
Inline: True
Inline callers:
  - ipc/msg.c:expunge_all
```
```
In ipc/sem.c (ffffffff814a88e0)
Location: include/linux/sched/task.h:100
Inline: True
Inline callers:
  - ipc/sem.c:freeary
  - ipc/sem.c:freeary
  - ipc/sem.c:freeary
  - ipc/sem.c:freeary
  - ipc/sem.c:update_queue
  - ipc/sem.c:wake_const_ops
```
```
In ipc/mqueue.c (ffffffff814b1a87)
Location: include/linux/sched/task.h:100
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
```
```
In security/yama/yama_lsm.c (ffffffff8152ed4e)
Location: include/linux/sched/task.h:100
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_task_prctl
  - security/yama/yama_lsm.c:report_access
  - security/yama/yama_lsm.c:report_access
```
```
In drivers/tty/tty_ldsem.c (ffffffff81c44ca4)
Location: include/linux/sched/task.h:100
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:down_read_failed
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff818af5c7)
Location: include/linux/sched/task.h:100
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_map
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff810610fa)
Location: include/linux/sched/task.h:102
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
```
```
In kernel/fork.c (ffffffff810a3c83)
Location: include/linux/sched/task.h:102
Inline: True
Inline callers:
  - kernel/fork.c:kernel_clone
```
```
In kernel/exit.c (ffffffff810a9968)
Location: include/linux/sched/task.h:102
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_task_stopped
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:mm_update_next_owner
```
```
In kernel/sys.c (ffffffff810c0d95)
Location: include/linux/sched/task.h:102
Inline: True
Inline callers:
  - kernel/sys.c:__do_sys_prlimit64
```
```
In kernel/pid.c (ffffffff810c9eab)
Location: include/linux/sched/task.h:102
Inline: True
Inline callers:
  - kernel/pid.c:pidfd_getfd
  - kernel/pid.c:find_get_task_by_vpid
```
```
In kernel/kthread.c (ffffffff810ccce8)
Location: include/linux/sched/task.h:102
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_stop
```
```
In kernel/smpboot.c (ffffffff810d60ac)
Location: include/linux/sched/task.h:102
Inline: True
```
```
In kernel/sched/core.c (ffffffff810de414)
Location: include/linux/sched/task.h:102
Inline: True
Inline callers:
  - kernel/sched/core.c:balance_push
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__ia32_sys_sched_setattr
  - kernel/sched/core.c:__x64_sys_sched_setattr
  - kernel/sched/core.c:do_sched_setscheduler
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/core.c:wake_q_add
```
```
In kernel/sched/fair.c (ffffffff810ea0e9)
Location: include/linux/sched/task.h:102
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_assign
```
```
In kernel/sched/rt.c (ffffffff810f9727)
Location: include/linux/sched/task.h:102
Inline: True
Inline callers:
  - kernel/sched/rt.c:pull_rt_task
```
```
In kernel/sched/deadline.c (ffffffff810fdc09)
Location: include/linux/sched/task.h:102
Inline: True
Inline callers:
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:start_dl_timer
  - kernel/sched/deadline.c:task_non_contending
```
```
In kernel/locking/rwsem.c (ffffffff8110d6af)
Location: include/linux/sched/task.h:102
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_mark_wake
```
```
In kernel/locking/percpu-rwsem.c (ffffffff8110e4db)
Location: include/linux/sched/task.h:102
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:percpu_rwsem_wake_function
```
```
In kernel/locking/rtmutex.c (ffffffff81c3731f)
Location: include/linux/sched/task.h:102
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_adjust_pi
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:task_blocks_on_rt_mutex
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
```
```
In kernel/irq/manage.c (ffffffff8111ef4f)
Location: include/linux/sched/task.h:102
Inline: True
Inline callers:
  - kernel/irq/manage.c:setup_irq_thread
```
```
In kernel/rcu/update.c (ffffffff8112cd02)
Location: include/linux/sched/task.h:102
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_trace_postgp
```
```
In kernel/kcmp.c (ffffffff8113d222)
Location: include/linux/sched/task.h:102
Inline: True
Inline callers:
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/kcmp.c:__do_sys_kcmp
```
```
In kernel/futex.c (ffffffff811582cb)
Location: include/linux/sched/task.h:102
Inline: True
Inline callers:
  - kernel/futex.c:mark_wake_futex
```
```
In kernel/cgroup/cgroup.c (ffffffff8117492a)
Location: include/linux/sched/task.h:102
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_task_iter_next
  - kernel/cgroup/cgroup.c:cgroup_procs_write_start
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81178174)
Location: include/linux/sched/task.h:102
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
```
In kernel/hung_task.c (ffffffff811a2060)
Location: include/linux/sched/task.h:102
Inline: True
Inline callers:
  - kernel/hung_task.c:check_hung_uninterruptible_tasks
  - kernel/hung_task.c:check_hung_uninterruptible_tasks
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811c99b7)
Location: include/linux/sched/task.h:102
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In kernel/events/core.c (ffffffff8124dbe3)
Location: include/linux/sched/task.h:102
Inline: True
Inline callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_remove_from_owner
  - kernel/events/core.c:alloc_perf_context
```
```
In mm/oom_kill.c (ffffffff81265c0a)
Location: include/linux/sched/task.h:102
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/page_io.c (ffffffff812cac75)
Location: include/linux/sched/task.h:102
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
```
```
In mm/mempolicy.c (ffffffff812e129f)
Location: include/linux/sched/task.h:102
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_migrate_pages
```
```
In mm/migrate.c (ffffffff812f33f8)
Location: include/linux/sched/task.h:102
Inline: True
Inline callers:
  - mm/migrate.c:find_mm_struct
```
```
In mm/huge_memory.c (ffffffff8130058e)
Location: include/linux/sched/task.h:102
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_pid
```
```
In mm/memory-failure.c (ffffffff813132c6)
Location: include/linux/sched/task.h:102
Inline: True
Inline callers:
  - mm/memory-failure.c:add_to_kill
```
```
In fs/io-wq.c (ffffffff813a391b)
Location: include/linux/sched/task.h:102
Inline: True
Inline callers:
  - fs/io-wq.c:io_wq_create
```
```
In fs/proc/base.c (ffffffff813d8577)
Location: include/linux/sched/task.h:102
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_lookup
  - fs/proc/base.c:next_tgid
  - fs/proc/base.c:proc_pid_lookup
```
```
In ipc/msg.c (ffffffff814ab7ab)
Location: include/linux/sched/task.h:102
Inline: True
Inline callers:
  - ipc/msg.c:expunge_all
```
```
In ipc/sem.c (ffffffff814ae81b)
Location: include/linux/sched/task.h:102
Inline: True
Inline callers:
  - ipc/sem.c:freeary
  - ipc/sem.c:freeary
  - ipc/sem.c:freeary
  - ipc/sem.c:freeary
  - ipc/sem.c:update_queue
  - ipc/sem.c:wake_const_ops
```
```
In ipc/mqueue.c (ffffffff814b7907)
Location: include/linux/sched/task.h:102
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
```
```
In security/yama/yama_lsm.c (ffffffff815354ee)
Location: include/linux/sched/task.h:102
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_task_prctl
  - security/yama/yama_lsm.c:report_access
  - security/yama/yama_lsm.c:report_access
```
```
In drivers/tty/tty_ldsem.c (ffffffff81c37f19)
Location: include/linux/sched/task.h:102
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:down_read_failed
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff81893d95)
Location: include/linux/sched/task.h:102
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_map
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8106adba)
Location: include/linux/sched/task.h:103
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
```
```
In kernel/fork.c (ffffffff810b54a0)
Location: include/linux/sched/task.h:103
Inline: True
Inline callers:
  - kernel/fork.c:kernel_clone
```
```
In kernel/exit.c (ffffffff810bb474)
Location: include/linux/sched/task.h:103
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_task_stopped
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:mm_update_next_owner
```
```
In kernel/sys.c (ffffffff810d3885)
Location: include/linux/sched/task.h:103
Inline: True
Inline callers:
  - kernel/sys.c:__do_sys_prlimit64
```
```
In kernel/pid.c (ffffffff810dcc9b)
Location: include/linux/sched/task.h:103
Inline: True
Inline callers:
  - kernel/pid.c:pidfd_getfd
  - kernel/pid.c:find_get_task_by_vpid
```
```
In kernel/kthread.c (ffffffff810dfe28)
Location: include/linux/sched/task.h:103
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_stop
```
```
In kernel/smpboot.c (ffffffff810e92fc)
Location: include/linux/sched/task.h:103
Inline: True
```
```
In kernel/sched/core.c (ffffffff810f2813)
Location: include/linux/sched/task.h:103
Inline: True
Inline callers:
  - kernel/sched/core.c:balance_push
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__do_sys_sched_setattr
  - kernel/sched/core.c:do_sched_setscheduler
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/core.c:wake_q_add
```
```
In kernel/sched/fair.c (ffffffff81101870)
Location: include/linux/sched/task.h:103
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_assign
```
```
In kernel/sched/rt.c (ffffffff81112f17)
Location: include/linux/sched/task.h:103
Inline: True
Inline callers:
  - kernel/sched/rt.c:pull_rt_task
```
```
In kernel/sched/deadline.c (ffffffff8111611e)
Location: include/linux/sched/task.h:103
Inline: True
Inline callers:
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:start_dl_timer
  - kernel/sched/deadline.c:task_non_contending
```
```
In kernel/sched/core_sched.c (ffffffff8112c445)
Location: include/linux/sched/task.h:103
Inline: True
Inline callers:
  - kernel/sched/core_sched.c:sched_core_share_pid
```
```
In kernel/locking/rwsem.c (ffffffff8112cf02)
Location: include/linux/sched/task.h:103
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_mark_wake
```
```
In kernel/locking/percpu-rwsem.c (ffffffff8112dc3b)
Location: include/linux/sched/task.h:103
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:percpu_rwsem_wake_function
```
```
In kernel/locking/rtmutex_api.c (ffffffff81d55fef)
Location: include/linux/sched/task.h:103
Inline: True
Inline callers:
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_pi
  - kernel/locking/rtmutex_api.c:remove_waiter
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
```
```
In kernel/irq/manage.c (ffffffff8113f20f)
Location: include/linux/sched/task.h:103
Inline: True
Inline callers:
  - kernel/irq/manage.c:setup_irq_thread
```
```
In kernel/rcu/update.c (ffffffff8114da02)
Location: include/linux/sched/task.h:103
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_trace_postgp
```
```
In kernel/kcmp.c (ffffffff811603a2)
Location: include/linux/sched/task.h:103
Inline: True
Inline callers:
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/kcmp.c:__do_sys_kcmp
```
```
In kernel/futex.c (ffffffff8117d1db)
Location: include/linux/sched/task.h:103
Inline: True
Inline callers:
  - kernel/futex.c:mark_wake_futex
```
```
In kernel/cgroup/cgroup.c (ffffffff8119b9fa)
Location: include/linux/sched/task.h:103
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_task_iter_next
  - kernel/cgroup/cgroup.c:cgroup_procs_write_start
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8119fae4)
Location: include/linux/sched/task.h:103
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
```
In kernel/hung_task.c (ffffffff811cb815)
Location: include/linux/sched/task.h:103
Inline: True
Inline callers:
  - kernel/hung_task.c:check_hung_uninterruptible_tasks
  - kernel/hung_task.c:check_hung_uninterruptible_tasks
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811f5495)
Location: include/linux/sched/task.h:103
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In kernel/events/core.c (ffffffff81288932)
Location: include/linux/sched/task.h:103
Inline: True
Inline callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_remove_from_owner
  - kernel/events/core.c:alloc_perf_context
```
```
In mm/oom_kill.c (ffffffff812a377c)
Location: include/linux/sched/task.h:103
Inline: True
Inline callers:
  - mm/oom_kill.c:out_of_memory
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/page_io.c (ffffffff8130fc7a)
Location: include/linux/sched/task.h:103
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
```
```
In mm/mempolicy.c (ffffffff8132856f)
Location: include/linux/sched/task.h:103
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_migrate_pages
```
```
In mm/migrate.c (ffffffff8133d868)
Location: include/linux/sched/task.h:103
Inline: True
Inline callers:
  - mm/migrate.c:find_mm_struct
```
```
In mm/huge_memory.c (ffffffff8134a22e)
Location: include/linux/sched/task.h:103
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_pid
```
```
In mm/memory-failure.c (ffffffff8135fd86)
Location: include/linux/sched/task.h:103
Inline: True
Inline callers:
  - mm/memory-failure.c:add_to_kill
```
```
In fs/io-wq.c (ffffffff813f2e7d)
Location: include/linux/sched/task.h:103
Inline: True
Inline callers:
  - fs/io-wq.c:io_wq_create
```
```
In fs/proc/base.c (ffffffff81429ca7)
Location: include/linux/sched/task.h:103
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_lookup
  - fs/proc/base.c:next_tgid
  - fs/proc/base.c:proc_pid_lookup
```
```
In ipc/msg.c (ffffffff81503c6b)
Location: include/linux/sched/task.h:103
Inline: True
Inline callers:
  - ipc/msg.c:expunge_all
```
```
In ipc/sem.c (ffffffff81506cab)
Location: include/linux/sched/task.h:103
Inline: True
Inline callers:
  - ipc/sem.c:freeary
  - ipc/sem.c:freeary
  - ipc/sem.c:freeary
  - ipc/sem.c:freeary
  - ipc/sem.c:update_queue
  - ipc/sem.c:wake_const_ops
```
```
In ipc/mqueue.c (ffffffff8151020f)
Location: include/linux/sched/task.h:103
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
```
```
In security/yama/yama_lsm.c (ffffffff81593abe)
Location: include/linux/sched/task.h:103
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_task_prctl
  - security/yama/yama_lsm.c:report_access
  - security/yama/yama_lsm.c:report_access
```
```
In drivers/tty/tty_ldsem.c (ffffffff81d567f3)
Location: include/linux/sched/task.h:103
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:down_read_failed
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff81927965)
Location: include/linux/sched/task.h:103
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_map
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff810780a7)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
```
```
In kernel/fork.c (ffffffff810cb815)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/fork.c:kernel_clone
```
```
In kernel/exit.c (ffffffff810d1e43)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_task_stopped
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:mm_update_next_owner
```
```
In kernel/sys.c (ffffffff810e9a08)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/sys.c:__do_sys_prlimit64
```
```
In kernel/pid.c (ffffffff810f6513)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/pid.c:pidfd_getfd
  - kernel/pid.c:pidfd_get_task
  - kernel/pid.c:find_get_task_by_vpid
```
```
In kernel/kthread.c (ffffffff810fa926)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_stop
```
```
In kernel/smpboot.c (ffffffff811040c4)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/smpboot.c:__smpboot_create_thread
```
```
In kernel/sched/core.c (ffffffff8110e740)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/sched/core.c:balance_push
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__do_sys_sched_setattr
  - kernel/sched/core.c:do_sched_setscheduler
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/core.c:wake_q_add
```
```
In kernel/sched/fair.c (ffffffff8111bd90)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_assign
```
```
In kernel/sched/build_policy.c (ffffffff8112fd73)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:pull_dl_task
  - kernel/sched/build_policy.c:push_dl_task
  - kernel/sched/build_policy.c:start_dl_timer
  - kernel/sched/build_policy.c:task_non_contending
  - kernel/sched/build_policy.c:pull_rt_task
  - kernel/sched/build_policy.c:push_rt_task
  - kernel/sched/build_policy.c:push_rt_task
```
```
In kernel/sched/build_utility.c (ffffffff8114b68e)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sched_core_share_pid
```
```
In kernel/locking/rwsem.c (ffffffff8114e1d3)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_mark_wake
```
```
In kernel/locking/percpu-rwsem.c (ffffffff8114ea0f)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:percpu_rwsem_wake_function
```
```
In kernel/locking/rtmutex_api.c (ffffffff81f27f8b)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_pi
  - kernel/locking/rtmutex_api.c:remove_waiter
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
```
```
In kernel/irq/manage.c (ffffffff81162ca7)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/irq/manage.c:setup_irq_thread
```
```
In kernel/rcu/update.c (ffffffff81174785)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_trace_postgp
```
```
In kernel/rcu/tree.c (ffffffff81e5f4a0)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_print_task_stall
```
```
In kernel/kcmp.c (ffffffff811930fc)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/kcmp.c:__do_sys_kcmp
```
```
In kernel/futex/waitwake.c (ffffffff811b6c57)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/futex/waitwake.c:futex_wake_mark
```
```
In kernel/cgroup/cgroup.c (ffffffff811cbc4a)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_task_iter_next
  - kernel/cgroup/cgroup.c:cgroup_procs_write_start
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff811d00f7)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
```
In kernel/hung_task.c (ffffffff811ff5d6)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/hung_task.c:check_hung_uninterruptible_tasks
  - kernel/hung_task.c:check_hung_uninterruptible_tasks
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff8122ecf2)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In kernel/events/core.c (ffffffff812ddc3f)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_remove_from_owner
  - kernel/events/core.c:alloc_perf_context
```
```
In mm/oom_kill.c (ffffffff812fb6c5)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - mm/oom_kill.c:out_of_memory
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:oom_evaluate_task
```
```
In mm/page_io.c (ffffffff8137a6c3)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
```
```
In mm/mempolicy.c (ffffffff813977d7)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_migrate_pages
```
```
In mm/migrate.c (ffffffff813b0b23)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - mm/migrate.c:find_mm_struct
```
```
In mm/huge_memory.c (ffffffff813c0dd6)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_pid
```
```
In mm/memory-failure.c (ffffffff813da9e8)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - mm/memory-failure.c:add_to_kill
```
```
In fs/proc/base.c (ffffffff814a3123)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_lookup
  - fs/proc/base.c:next_tgid
  - fs/proc/base.c:proc_pid_lookup
```
```
In ipc/msg.c (ffffffff81595622)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - ipc/msg.c:expunge_all
```
```
In ipc/sem.c (ffffffff81598fa6)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - ipc/sem.c:freeary
  - ipc/sem.c:freeary
  - ipc/sem.c:freeary
  - ipc/sem.c:freeary
  - ipc/sem.c:update_queue
  - ipc/sem.c:wake_const_ops
```
```
In ipc/mqueue.c (ffffffff815a23ee)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
```
```
In security/yama/yama_lsm.c (ffffffff8163558e)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_task_prctl
  - security/yama/yama_lsm.c:report_access
  - security/yama/yama_lsm.c:report_access
```
```
In io_uring/io-wq.c (ffffffff816db9dd)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_wq_create
```
```
In drivers/tty/tty_ldsem.c (ffffffff81f2899d)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:down_read_failed
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff81a7ccaa)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_map
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81088cb7)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
```
```
In kernel/fork.c (ffffffff810e8ddd)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/fork.c:kernel_clone
```
```
In kernel/exit.c (ffffffff810f08a3)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_task_stopped
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:mm_update_next_owner
```
```
In kernel/sys.c (ffffffff8110b6a8)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/sys.c:__do_sys_prlimit64
```
```
In kernel/pid.c (ffffffff81118ba3)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/pid.c:pidfd_getfd
  - kernel/pid.c:pidfd_get_task
  - kernel/pid.c:find_get_task_by_vpid
```
```
In kernel/kthread.c (ffffffff8111d776)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_stop
```
```
In kernel/smpboot.c (ffffffff81129874)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/smpboot.c:__smpboot_create_thread
```
```
In kernel/sched/core.c (ffffffff811354e0)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/sched/core.c:balance_push
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__do_sys_sched_setattr
  - kernel/sched/core.c:do_sched_setscheduler
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/core.c:wake_q_add
```
```
In kernel/sched/fair.c (ffffffff811452a2)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_assign
```
```
In kernel/sched/build_policy.c (ffffffff81159e37)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:pull_dl_task
  - kernel/sched/build_policy.c:push_dl_task
  - kernel/sched/build_policy.c:start_dl_timer
  - kernel/sched/build_policy.c:task_non_contending
  - kernel/sched/build_policy.c:pull_rt_task
  - kernel/sched/build_policy.c:push_rt_task
  - kernel/sched/build_policy.c:push_rt_task
```
```
In kernel/sched/build_utility.c (ffffffff8117a11e)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sched_core_share_pid
```
```
In kernel/locking/rwsem.c (ffffffff8117d153)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_mark_wake
```
```
In kernel/locking/percpu-rwsem.c (ffffffff8117dbaf)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:percpu_rwsem_wake_function
```
```
In kernel/locking/rtmutex_api.c (ffffffff820d3b3b)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_pi
  - kernel/locking/rtmutex_api.c:remove_waiter
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
```
```
In kernel/irq/manage.c (ffffffff81196877)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/irq/manage.c:setup_irq_thread
```
```
In kernel/rcu/update.c (ffffffff811aba39)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_trace_pregp_step
  - kernel/rcu/update.c:trc_inspect_reader
```
```
In kernel/rcu/tree.c (ffffffff811b1398)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_print_task_stall
```
```
In kernel/kcmp.c (ffffffff811d093c)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/kcmp.c:__do_sys_kcmp
```
```
In kernel/futex/waitwake.c (ffffffff811f7dc7)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/futex/waitwake.c:futex_wake_mark
```
```
In kernel/cgroup/cgroup.c (ffffffff8120f0fa)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_task_iter_next
  - kernel/cgroup/cgroup.c:cgroup_procs_write_start
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81213b57)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
```
In kernel/hung_task.c (ffffffff81246feb)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/hung_task.c:check_hung_uninterruptible_tasks
  - kernel/hung_task.c:check_hung_uninterruptible_tasks
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff8127ad14)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In kernel/trace/bpf_trace.c (ffffffff812a6c65)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_send_signal_common
```
```
In kernel/bpf/helpers.c (ffffffff812f4537)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_task_from_pid
```
```
In kernel/bpf/task_iter.c (ffffffff812f7000)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/bpf/task_iter.c:task_group_seq_get_next
```
```
In kernel/events/core.c (ffffffff8134605c)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_remove_from_owner
  - kernel/events/core.c:alloc_perf_context
```
```
In mm/oom_kill.c (ffffffff813657b6)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - mm/oom_kill.c:out_of_memory
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:oom_evaluate_task
```
```
In mm/page_io.c (ffffffff813f81b1)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
```
```
In mm/mempolicy.c (ffffffff814173b7)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_migrate_pages
```
```
In mm/migrate.c (ffffffff81431673)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - mm/migrate.c:find_mm_struct
```
```
In mm/huge_memory.c (ffffffff81442ca6)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_pid
```
```
In mm/memory-failure.c (ffffffff81460be5)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - mm/memory-failure.c:add_to_kill
```
```
In fs/proc/base.c (ffffffff815383a3)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_lookup
  - fs/proc/base.c:next_tgid
  - fs/proc/base.c:proc_pid_lookup
```
```
In ipc/msg.c (ffffffff8163e5a2)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - ipc/msg.c:expunge_all
```
```
In ipc/sem.c (ffffffff81642206)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - ipc/sem.c:freeary
  - ipc/sem.c:freeary
  - ipc/sem.c:freeary
  - ipc/sem.c:freeary
  - ipc/sem.c:update_queue
  - ipc/sem.c:wake_const_ops
```
```
In ipc/mqueue.c (ffffffff8164bebe)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
```
```
In security/apparmor/file.c (ffffffff816dbc34)
Location: include/linux/sched/task.h:108
Inline: True
```
```
In security/yama/yama_lsm.c (ffffffff816ec26e)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_task_prctl
  - security/yama/yama_lsm.c:report_access
  - security/yama/yama_lsm.c:report_access
```
```
In io_uring/io_uring.c (ffffffff8178c69c)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - io_uring/io_uring.c:__io_uring_register
  - io_uring/io_uring.c:io_uring_create
```
```
In io_uring/io-wq.c (ffffffff817a7aba)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_wq_create
```
```
In drivers/tty/tty_ldsem.c (ffffffff820d45fd)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:down_read_failed
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8108bbb7)
Location: include/linux/sched/task.h:114
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
```
```
In kernel/fork.c (ffffffff810f49e6)
Location: include/linux/sched/task.h:114
Inline: True
Inline callers:
  - kernel/fork.c:kernel_clone
```
```
In kernel/exit.c (ffffffff810fc860)
Location: include/linux/sched/task.h:114
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_task_stopped
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:mm_update_next_owner
```
```
In kernel/sys.c (ffffffff81117a38)
Location: include/linux/sched/task.h:114
Inline: True
Inline callers:
  - kernel/sys.c:__do_sys_prlimit64
```
```
In kernel/pid.c (ffffffff81126063)
Location: include/linux/sched/task.h:114
Inline: True
Inline callers:
  - kernel/pid.c:pidfd_getfd
  - kernel/pid.c:pidfd_get_task
  - kernel/pid.c:find_get_task_by_vpid
```
```
In kernel/kthread.c (ffffffff8112a966)
Location: include/linux/sched/task.h:114
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_stop
```
```
In kernel/smpboot.c (ffffffff81136d14)
Location: include/linux/sched/task.h:114
Inline: True
Inline callers:
  - kernel/smpboot.c:__smpboot_create_thread
```
```
In kernel/sched/core.c (ffffffff81144660)
Location: include/linux/sched/task.h:114
Inline: True
Inline callers:
  - kernel/sched/core.c:balance_push
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__do_sys_sched_setattr
  - kernel/sched/core.c:do_sched_setscheduler
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/core.c:wake_q_add
```
```
In kernel/sched/fair.c (ffffffff811557b2)
Location: include/linux/sched/task.h:114
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_assign
```
```
In kernel/sched/build_policy.c (ffffffff8116a047)
Location: include/linux/sched/task.h:114
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:pull_dl_task
  - kernel/sched/build_policy.c:push_dl_task
  - kernel/sched/build_policy.c:start_dl_timer
  - kernel/sched/build_policy.c:task_non_contending
  - kernel/sched/build_policy.c:pull_rt_task
  - kernel/sched/build_policy.c:push_rt_task
  - kernel/sched/build_policy.c:push_rt_task
```
```
In kernel/sched/build_utility.c (ffffffff8118ac7e)
Location: include/linux/sched/task.h:114
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sched_core_share_pid
```
```
In kernel/locking/rwsem.c (ffffffff8118de03)
Location: include/linux/sched/task.h:114
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_mark_wake
```
```
In kernel/locking/percpu-rwsem.c (ffffffff8118e84f)
Location: include/linux/sched/task.h:114
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:percpu_rwsem_wake_function
```
```
In kernel/locking/rtmutex_api.c (ffffffff82157dbb)
Location: include/linux/sched/task.h:114
Inline: True
Inline callers:
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_pi
  - kernel/locking/rtmutex_api.c:remove_waiter
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
```
```
In kernel/irq/manage.c (ffffffff811a8237)
Location: include/linux/sched/task.h:114
Inline: True
Inline callers:
  - kernel/irq/manage.c:setup_irq_thread
```
```
In kernel/rcu/update.c (ffffffff811bd959)
Location: include/linux/sched/task.h:114
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_trace_pregp_step
  - kernel/rcu/update.c:trc_inspect_reader
```
```
In kernel/rcu/tree.c (ffffffff811c3077)
Location: include/linux/sched/task.h:114
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_print_task_stall
```
```
In kernel/kcmp.c (ffffffff811e4bbc)
Location: include/linux/sched/task.h:114
Inline: True
Inline callers:
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/kcmp.c:__do_sys_kcmp
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811fd32a)
Location: include/linux/sched/task.h:114
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_wait_running
```
```
In kernel/futex/waitwake.c (ffffffff8120c567)
Location: include/linux/sched/task.h:114
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffffffff81224b0a)
Location: include/linux/sched/task.h:114
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_task_iter_next
  - kernel/cgroup/cgroup.c:cgroup_procs_write_start
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81229493)
Location: include/linux/sched/task.h:114
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
```
In kernel/hung_task.c (ffffffff8125e07b)
Location: include/linux/sched/task.h:114
Inline: True
Inline callers:
  - kernel/hung_task.c:check_hung_uninterruptible_tasks
  - kernel/hung_task.c:check_hung_uninterruptible_tasks
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff81292834)
Location: include/linux/sched/task.h:114
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In kernel/trace/trace_osnoise.c (ffffffff812967df)
Location: include/linux/sched/task.h:114
Inline: True
Inline callers:
  - kernel/trace/trace_osnoise.c:timerlat_fd_open
```
```
In kernel/trace/bpf_trace.c (ffffffff812c8d25)
Location: include/linux/sched/task.h:114
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_send_signal_common
```
```
In kernel/bpf/task_iter.c (ffffffff81324ec0)
Location: include/linux/sched/task.h:114
Inline: True
Inline callers:
  - kernel/bpf/task_iter.c:task_group_seq_get_next
```
```
In kernel/events/core.c (ffffffff8137712a)
Location: include/linux/sched/task.h:114
Inline: True
Inline callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_remove_from_owner
  - kernel/events/core.c:alloc_perf_context
```
```
In mm/oom_kill.c (ffffffff81397c59)
Location: include/linux/sched/task.h:114
Inline: True
Inline callers:
  - mm/oom_kill.c:out_of_memory
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:oom_evaluate_task
```
```
In mm/page_io.c (ffffffff8142a289)
Location: include/linux/sched/task.h:114
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage_bdev_sync
```
```
In mm/mempolicy.c (ffffffff8144a947)
Location: include/linux/sched/task.h:114
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_migrate_pages
```
```
In mm/migrate.c (ffffffff814670b3)
Location: include/linux/sched/task.h:114
Inline: True
Inline callers:
  - mm/migrate.c:find_mm_struct
```
```
In mm/huge_memory.c (ffffffff81478566)
Location: include/linux/sched/task.h:114
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_pid
```
```
In mm/memory-failure.c (ffffffff81495fe0)
Location: include/linux/sched/task.h:114
Inline: True
Inline callers:
  - mm/memory-failure.c:__add_to_kill
```
```
In fs/proc/base.c (ffffffff815705e6)
Location: include/linux/sched/task.h:114
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_lookup
  - fs/proc/base.c:next_tgid
  - fs/proc/base.c:proc_pid_lookup
```
```
In ipc/msg.c (ffffffff81676a92)
Location: include/linux/sched/task.h:114
Inline: True
Inline callers:
  - ipc/msg.c:expunge_all
```
```
In ipc/sem.c (ffffffff8167a782)
Location: include/linux/sched/task.h:114
Inline: True
Inline callers:
  - ipc/sem.c:freeary
  - ipc/sem.c:freeary
  - ipc/sem.c:freeary
  - ipc/sem.c:freeary
  - ipc/sem.c:update_queue
  - ipc/sem.c:wake_const_ops
```
```
In ipc/mqueue.c (ffffffff816845f8)
Location: include/linux/sched/task.h:114
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
```
```
In security/apparmor/file.c (ffffffff81715288)
Location: include/linux/sched/task.h:114
Inline: True
```
```
In security/yama/yama_lsm.c (ffffffff8172669e)
Location: include/linux/sched/task.h:114
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_task_prctl
  - security/yama/yama_lsm.c:report_access
  - security/yama/yama_lsm.c:report_access
```
```
In io_uring/io_uring.c (ffffffff817cd8bf)
Location: include/linux/sched/task.h:114
Inline: True
Inline callers:
  - io_uring/io_uring.c:__io_uring_register
  - io_uring/io_uring.c:io_uring_create
```
```
In io_uring/io-wq.c (ffffffff817e8978)
Location: include/linux/sched/task.h:114
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_wq_create
```
```
In rust/helpers.c (ffffffff81805c75)
Location: include/linux/sched/task.h:114
Inline: True
Inline callers:
  - rust/helpers.c:rust_helper_get_task_struct
```
```
In drivers/tty/tty_ldsem.c (ffffffff8215880d)
Location: include/linux/sched/task.h:114
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:down_read_failed
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff810938a6)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
```
```
In kernel/fork.c (ffffffff810fdd86)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/fork.c:kernel_clone
```
```
In kernel/exit.c (ffffffff81105f60)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_task_stopped
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:mm_update_next_owner
```
```
In kernel/sys.c (ffffffff81121428)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/sys.c:__do_sys_prlimit64
```
```
In kernel/pid.c (ffffffff81130663)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/pid.c:pidfd_getfd
  - kernel/pid.c:pidfd_get_task
  - kernel/pid.c:find_get_task_by_vpid
```
```
In kernel/kthread.c (ffffffff81134ff6)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_stop
```
```
In kernel/smpboot.c (ffffffff81141db5)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/smpboot.c:__smpboot_create_thread
```
```
In kernel/sched/core.c (ffffffff8114fb84)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/sched/core.c:balance_push
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:do_sched_setscheduler
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/core.c:wake_q_add
```
```
In kernel/sched/fair.c (ffffffff81163402)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_assign
```
```
In kernel/sched/build_policy.c (ffffffff811776ff)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:pull_dl_task
  - kernel/sched/build_policy.c:push_dl_task
  - kernel/sched/build_policy.c:start_dl_timer
  - kernel/sched/build_policy.c:task_non_contending
  - kernel/sched/build_policy.c:pull_rt_task
  - kernel/sched/build_policy.c:push_rt_task
  - kernel/sched/build_policy.c:push_rt_task
```
```
In kernel/sched/build_utility.c (ffffffff8119958e)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sched_core_share_pid
```
```
In kernel/locking/rwsem.c (ffffffff8119c7b3)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_mark_wake
```
```
In kernel/locking/percpu-rwsem.c (ffffffff8119d1ff)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:percpu_rwsem_wake_function
```
```
In kernel/locking/rtmutex_api.c (ffffffff8223ac2b)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_pi
  - kernel/locking/rtmutex_api.c:remove_waiter
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
```
```
In kernel/irq/manage.c (ffffffff811b7cb7)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/irq/manage.c:setup_irq_thread
```
```
In kernel/rcu/update.c (ffffffff811cde79)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_trace_pregp_step
  - kernel/rcu/update.c:trc_inspect_reader
```
```
In kernel/rcu/tree.c (ffffffff811d32b7)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_print_task_stall
```
```
In kernel/kcmp.c (ffffffff811fa90c)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/kcmp.c:__do_sys_kcmp
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8121352a)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_wait_running
```
```
In kernel/futex/waitwake.c (ffffffff812238af)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/futex/waitwake.c:futex_wake_mark
```
```
In kernel/cgroup/cgroup.c (ffffffff8123c7ff)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_task_iter_next
  - kernel/cgroup/cgroup.c:cgroup_procs_write_start
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff812412e3)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
```
In kernel/hung_task.c (ffffffff81277fbb)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/hung_task.c:check_hung_uninterruptible_tasks
  - kernel/hung_task.c:check_hung_uninterruptible_tasks
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff812adf1a)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In kernel/trace/trace_osnoise.c (ffffffff812b1ddf)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/trace/trace_osnoise.c:timerlat_fd_open
```
```
In kernel/trace/bpf_trace.c (ffffffff812e5cf5)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_send_signal_common
```
```
In kernel/bpf/task_iter.c (ffffffff8134977a)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/bpf/task_iter.c:bpf_iter_task_vma_new
  - kernel/bpf/task_iter.c:task_seq_get_next
```
```
In kernel/events/core.c (ffffffff813a03a1)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_remove_from_owner
  - kernel/events/core.c:alloc_perf_context
```
```
In mm/oom_kill.c (ffffffff813c1a85)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - mm/oom_kill.c:out_of_memory
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:oom_evaluate_task
```
```
In mm/page_io.c (ffffffff8146364f)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - mm/page_io.c:swap_read_folio_bdev_sync
```
```
In mm/mempolicy.c (ffffffff81484386)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_migrate_pages
```
```
In mm/migrate.c (ffffffff814962f3)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - mm/migrate.c:find_mm_struct
```
```
In mm/huge_memory.c (ffffffff814a7c96)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_pid
```
```
In mm/memory-failure.c (ffffffff814c568c)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - mm/memory-failure.c:__add_to_kill
```
```
In fs/proc/base.c (ffffffff815a90a8)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_lookup
  - fs/proc/base.c:next_tgid
  - fs/proc/base.c:proc_pid_lookup
```
```
In ipc/msg.c (ffffffff816b2e52)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - ipc/msg.c:expunge_all
```
```
In ipc/sem.c (ffffffff816b6b22)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - ipc/sem.c:freeary
  - ipc/sem.c:freeary
  - ipc/sem.c:freeary
  - ipc/sem.c:freeary
  - ipc/sem.c:update_queue
  - ipc/sem.c:wake_const_ops
```
```
In ipc/mqueue.c (ffffffff816c0a2e)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
```
```
In security/apparmor/file.c (ffffffff81753faa)
Location: include/linux/sched/task.h:116
Inline: True
```
```
In security/yama/yama_lsm.c (ffffffff817678be)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_task_prctl
  - security/yama/yama_lsm.c:report_access
  - security/yama/yama_lsm.c:report_access
```
```
In io_uring/io_uring.c (ffffffff81816c09)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_uring_create
```
```
In io_uring/register.c (ffffffff8182bde0)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - io_uring/register.c:__io_uring_register
```
```
In io_uring/io-wq.c (ffffffff8182e75a)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_wq_create
```
```
In rust/helpers.c (ffffffff818429e5)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - rust/helpers.c:rust_helper_get_task_struct
```
```
In drivers/tty/tty_ldsem.c (ffffffff8223c08d)
Location: include/linux/sched/task.h:116
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:down_read_failed
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
In kernel/fork.c (ffff8000100f4e38)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
```
```
In kernel/exit.c (ffff8000100fb680)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:mm_update_next_owner
```
```
In kernel/sys.c (ffff800010119514)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/sys.c:__arm64_sys_prlimit64
```
```
In kernel/pid.c (ffff800010124128)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/pid.c:get_pid_task
  - kernel/pid.c:find_get_task_by_vpid
```
```
In kernel/kthread.c (ffff800010128548)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_stop
```
```
In kernel/smpboot.c (ffff80001012f278)
Location: include/linux/sched/task.h:108
Inline: True
```
```
In kernel/sched/core.c (ffff80001013c5a8)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__arm64_sys_sched_setattr
  - kernel/sched/core.c:do_sched_setscheduler
  - kernel/sched/core.c:wake_q_add
```
```
In kernel/sched/fair.c (ffff800010143d08)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_find_cpu
```
```
In kernel/sched/rt.c (ffff800010150af4)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/sched/rt.c:push_rt_task
```
```
In kernel/sched/deadline.c (ffff800010153edc)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/sched/deadline.c:start_dl_timer
  - kernel/sched/deadline.c:task_non_contending
```
```
In kernel/locking/rwsem.c (ffff8000101693b4)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_mark_wake
```
```
In kernel/locking/rtmutex.c (ffff80001016c018)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_adjust_pi
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:task_blocks_on_rt_mutex
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
```
```
In kernel/irq/manage.c (ffff80001017b538)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
```
```
In kernel/rcu/update.c (ffff800010188d58)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/kcmp.c (ffff800010197c70)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/kcmp.c:__arm64_sys_kcmp
  - kernel/kcmp.c:__arm64_sys_kcmp
```
```
In kernel/time/posix-cpu-timers.c (ffff8000101ad294)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:__get_task_for_clock
```
```
In kernel/futex.c (ffff8000101b6bec)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/futex.c:mark_wake_futex
```
```
In kernel/cgroup/cgroup.c (ffff8000101d7b00)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_task_iter_next
  - kernel/cgroup/cgroup.c:cgroup_procs_write_start
```
```
In kernel/cgroup/cgroup-v1.c (ffff8000101dba70)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
```
In kernel/hung_task.c (ffff800010206e7c)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/hung_task.c:watchdog
  - kernel/hung_task.c:watchdog
```
```
In kernel/trace/trace_sched_wakeup.c (ffff80001023078c)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In kernel/events/core.c (ffff80001029d7fc)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:alloc_perf_context
```
```
In mm/oom_kill.c (ffff8000102b77c4)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/page_io.c (ffff800010320b28)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
```
```
In mm/mempolicy.c (ffff800010337cb4)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_migrate_pages
```
```
In mm/migrate.c (ffff800010352628)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - mm/migrate.c:kernel_move_pages
```
```
In mm/memory-failure.c (ffff80001036db68)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - mm/memory-failure.c:add_to_kill
```
```
In fs/proc/base.c (ffff8000104422e8)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_lookup
  - fs/proc/base.c:next_tgid
  - fs/proc/base.c:proc_pid_lookup
```
```
In security/yama/yama_lsm.c (ffff8000105aabb8)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_task_prctl
  - security/yama/yama_lsm.c:report_access
  - security/yama/yama_lsm.c:report_access
```
```
In drivers/tty/tty_ldsem.c (ffff800010da6ae8)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_read
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
In kernel/fork.c (c0353578)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
```
```
In kernel/exit.c (c035958c)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:mm_update_next_owner
```
```
In kernel/sys.c (c036db80)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/sys.c:__se_sys_prlimit64
```
```
In kernel/pid.c (c0377454)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/pid.c:get_pid_task
  - kernel/pid.c:find_get_task_by_vpid
```
```
In kernel/kthread.c (c037aa78)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_stop
```
```
In kernel/smpboot.c (c037f1e4)
Location: include/linux/sched/task.h:108
Inline: True
```
```
In kernel/sched/core.c (c038c950)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__se_sys_sched_setattr
  - kernel/sched/core.c:do_sched_setscheduler
  - kernel/sched/core.c:wake_q_add
```
```
In kernel/sched/rt.c (c039becc)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/sched/rt.c:push_rt_task
```
```
In kernel/sched/deadline.c (c03a0a94)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/sched/deadline.c:start_dl_timer
  - kernel/sched/deadline.c:task_non_contending
```
```
In kernel/locking/rwsem.c (c03b54cc)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_mark_wake
```
```
In kernel/locking/rtmutex.c (c03b7980)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_adjust_pi
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:task_blocks_on_rt_mutex
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
```
```
In kernel/irq/manage.c (c03cc910)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
```
```
In kernel/rcu/update.c (c03d75c4)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/kcmp.c (c03e2bc0)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/kcmp.c:__se_sys_kcmp
  - kernel/kcmp.c:__se_sys_kcmp
```
```
In kernel/time/posix-cpu-timers.c (c03f8234)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:__get_task_for_clock
```
```
In kernel/futex.c (c04003f8)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/futex.c:mark_wake_futex
```
```
In kernel/cgroup/cgroup.c (c041a7f4)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_task_iter_next
  - kernel/cgroup/cgroup.c:cgroup_procs_write_start
```
```
In kernel/cgroup/cgroup-v1.c (c041ddcc)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
```
In kernel/hung_task.c (c0445c54)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/hung_task.c:watchdog
  - kernel/hung_task.c:watchdog
```
```
In kernel/trace/trace_sched_wakeup.c (c046c818)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In kernel/events/core.c (c04ccf9c)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:alloc_perf_context
```
```
In mm/oom_kill.c (c04e43fc)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/page_io.c (c053951c)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
```
```
In fs/proc/base.c (c06079cc)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_lookup
  - fs/proc/base.c:next_tgid
  - fs/proc/base.c:proc_pid_lookup
```
```
In security/yama/yama_lsm.c (c075a400)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_task_prctl
  - security/yama/yama_lsm.c:report_access
  - security/yama/yama_lsm.c:report_access
```
```
In drivers/tty/tty_ldsem.c (c0e9e8e8)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_read
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
In kernel/fork.c (c00000000013af00)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
```
```
In kernel/exit.c (c000000000142c64)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:mm_update_next_owner
```
```
In kernel/sys.c (c000000000160e28)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/sys.c:__se_sys_prlimit64
```
```
In kernel/pid.c (c00000000016db94)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/pid.c:get_pid_task
  - kernel/pid.c:find_get_task_by_vpid
```
```
In kernel/kthread.c (c0000000001731a4)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_stop
```
```
In kernel/smpboot.c (c000000000178a28)
Location: include/linux/sched/task.h:108
Inline: True
```
```
In kernel/sched/core.c (c00000000018abec)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__se_sys_sched_setattr
  - kernel/sched/core.c:do_sched_setscheduler
  - kernel/sched/core.c:wake_q_add
```
```
In kernel/sched/fair.c (c0000000001933c8)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_find_cpu
```
```
In kernel/sched/rt.c (c0000000001a23a4)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/sched/rt.c:push_rt_task
```
```
In kernel/sched/deadline.c (c0000000001a7570)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/sched/deadline.c:start_dl_timer
  - kernel/sched/deadline.c:task_non_contending
```
```
In kernel/locking/rwsem.c (c0000000001c0d74)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_mark_wake
```
```
In kernel/locking/rtmutex.c (c0000000001c3b8c)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_adjust_pi
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:task_blocks_on_rt_mutex
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
```
```
In kernel/irq/manage.c (c0000000001d5fc8)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
```
```
In kernel/rcu/update.c (c0000000001e2ff0)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/kcmp.c (c0000000001f78ac)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/kcmp.c:__se_sys_kcmp
  - kernel/kcmp.c:__se_sys_kcmp
```
```
In kernel/time/posix-cpu-timers.c (c00000000021149c)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:__get_task_for_clock
```
```
In kernel/futex.c (c00000000021bf24)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/futex.c:mark_wake_futex
```
```
In kernel/cgroup/cgroup.c (c0000000002448c4)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_task_iter_next
  - kernel/cgroup/cgroup.c:cgroup_procs_write_start
```
```
In kernel/cgroup/cgroup-v1.c (c000000000249070)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
```
In kernel/hung_task.c (c0000000002833e4)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/hung_task.c:watchdog
  - kernel/hung_task.c:watchdog
```
```
In kernel/trace/trace_sched_wakeup.c (c0000000002bae8c)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In kernel/events/core.c (c00000000034e414)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:alloc_perf_context
```
```
In mm/oom_kill.c (c00000000036f5b8)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/page_io.c (c0000000003f5e8c)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
```
```
In mm/mempolicy.c (c000000000412abc)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_migrate_pages
```
```
In mm/migrate.c (c000000000438fa4)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - mm/migrate.c:kernel_move_pages
```
```
In mm/memory-failure.c (c00000000045e8ec)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - mm/memory-failure.c:add_to_kill
```
```
In fs/proc/base.c (c0000000005578dc)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_lookup
  - fs/proc/base.c:next_tgid
  - fs/proc/base.c:proc_pid_lookup
```
```
In security/yama/yama_lsm.c (c00000000072812c)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_task_prctl
  - security/yama/yama_lsm.c:report_access
  - security/yama/yama_lsm.c:report_access
```
```
In drivers/tty/tty_ldsem.c (c000000000ee9360)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_read
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
In kernel/fork.c (ffffffe0000c14c4)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
```
```
In kernel/exit.c (ffffffe0000c52f2)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:mm_update_next_owner
```
```
In kernel/sys.c (ffffffe0000d44a8)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/sys.c:__se_sys_prlimit64
```
```
In kernel/pid.c (ffffffe0000dc1de)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/pid.c:get_pid_task
  - kernel/pid.c:find_get_task_by_vpid
```
```
In kernel/kthread.c (ffffffe0000df370)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_stop
```
```
In kernel/smpboot.c (ffffffe0000e2f80)
Location: include/linux/sched/task.h:108
Inline: True
```
```
In kernel/sched/core.c (ffffffe0000ebdcc)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__se_sys_sched_setattr
  - kernel/sched/core.c:do_sched_setscheduler
  - kernel/sched/core.c:wake_q_add
```
```
In kernel/sched/rt.c (ffffffe0000f91c2)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/sched/rt.c:push_rt_task
```
```
In kernel/sched/deadline.c (ffffffe0000fb742)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/sched/deadline.c:start_dl_timer
  - kernel/sched/deadline.c:task_non_contending
```
```
In kernel/locking/rwsem.c (ffffffe00010a9c0)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_mark_wake
```
```
In kernel/locking/rtmutex.c (ffffffe00010c276)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_adjust_pi
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:task_blocks_on_rt_mutex
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
```
```
In kernel/irq/manage.c (ffffffe0001151ca)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
```
```
In kernel/rcu/update.c (ffffffe00011e006)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/kcmp.c (ffffffe000128a1a)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/kcmp.c:__se_sys_kcmp
  - kernel/kcmp.c:__se_sys_kcmp
```
```
In kernel/time/posix-cpu-timers.c (ffffffe0001372b2)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:__get_task_for_clock
```
```
In kernel/futex.c (ffffffe00013c44c)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/futex.c:mark_wake_futex
```
```
In kernel/cgroup/cgroup.c (ffffffe000150ba2)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_task_iter_next
  - kernel/cgroup/cgroup.c:cgroup_procs_write_start
```
```
In kernel/cgroup/cgroup-v1.c (ffffffe000153c0c)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
```
In kernel/hung_task.c (ffffffe0001696aa)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/hung_task.c:watchdog
  - kernel/hung_task.c:watchdog
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffe000189110)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In kernel/events/core.c (ffffffe0001cb82e)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:alloc_perf_context
```
```
In mm/oom_kill.c (ffffffe0001dbab8)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/page_io.c (ffffffe0002220fc)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
```
```
In fs/proc/base.c (ffffffe0002d8f5e)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_lookup
  - fs/proc/base.c:next_tgid
  - fs/proc/base.c:proc_pid_lookup
```
```
In security/yama/yama_lsm.c (ffffffe0003f3644)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_task_prctl
  - security/yama/yama_lsm.c:report_access
  - security/yama/yama_lsm.c:report_access
```
```
In drivers/tty/tty_ldsem.c (ffffffe0008c8db2)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_read
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Selective Inline ⚠️</summary>

```c
struct task_struct *get_task_struct(struct task_struct *t);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105c59e)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
```
```
In kernel/fork.c (ffffffff81099e79)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
```
```
In kernel/exit.c (ffffffff8109f067)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:mm_update_next_owner
```
```
In kernel/sys.c (ffffffff810b6a11)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_prlimit64
  - kernel/sys.c:__x64_sys_prlimit64
```
```
In kernel/pid.c (ffffffff810bfd4d)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/pid.c:get_pid_task
  - kernel/pid.c:find_get_task_by_vpid
```
```
In kernel/kthread.c (ffffffff810c31a6)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_stop
```
```
In kernel/smpboot.c (ffffffff810c97cd)
Location: include/linux/sched/task.h:108
Inline: True
```
```
In kernel/sched/core.c (ffffffff810d6c10)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__ia32_sys_sched_setattr
  - kernel/sched/core.c:__x64_sys_sched_setattr
  - kernel/sched/core.c:do_sched_setscheduler
  - kernel/sched/core.c:wake_q_add
```
```
In kernel/sched/fair.c (ffffffff810dddc6)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_find_cpu
```
```
In kernel/sched/rt.c (ffffffff810e914c)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/sched/rt.c:push_rt_task
```
```
In kernel/sched/deadline.c (ffffffff810ea6d8)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/sched/deadline.c:start_dl_timer
  - kernel/sched/deadline.c:task_non_contending
```
```
In kernel/locking/rwsem.c (ffffffff810fcdc2)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_mark_wake
```
```
In kernel/locking/rtmutex.c (ffffffff810ff1a7)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_adjust_pi
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:task_blocks_on_rt_mutex
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
```
```
In kernel/irq/manage.c (ffffffff8110f81e)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/irq/manage.c:setup_irq_thread
```
```
In kernel/rcu/update.c (ffffffff8111c08d)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/kcmp.c (ffffffff811290d2)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/kcmp.c:__do_sys_kcmp
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8113b932)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:__get_task_for_clock
```
```
In kernel/futex.c (ffffffff811427eb)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/futex.c:mark_wake_futex
```
```
In kernel/cgroup/cgroup.c (ffffffff8115e560)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_task_iter_next
  - kernel/cgroup/cgroup.c:cgroup_procs_write_start
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff811610db)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
```
In kernel/hung_task.c (ffffffff81187dbf)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/hung_task.c:watchdog
  - kernel/hung_task.c:watchdog
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811ab145)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In kernel/events/core.c (ffffffff8120bd66)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:alloc_perf_context
```
```
In mm/oom_kill.c (ffffffff81220620)
Location: include/linux/sched/task.h:108
Inline: True
Direct callers:
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/page_io.c (ffffffff8127eafa)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
```
```
In mm/mempolicy.c (ffffffff8129161f)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_migrate_pages
```
```
In mm/migrate.c (ffffffff812aa4c7)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - mm/migrate.c:kernel_move_pages
```
```
In mm/memory-failure.c (ffffffff812c3156)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - mm/memory-failure.c:add_to_kill
```
```
In fs/proc/base.c (ffffffff8136f119)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_lookup
  - fs/proc/base.c:next_tgid
  - fs/proc/base.c:proc_pid_lookup
```
```
In security/yama/yama_lsm.c (ffffffff814ab1a9)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_task_prctl
  - security/yama/yama_lsm.c:report_access
  - security/yama/yama_lsm.c:report_access
```
```
In drivers/tty/tty_ldsem.c (ffffffff81a72d0f)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_read
```
**Symbols:**

```
ffffffff81220620-ffffffff8122062e: get_task_struct (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Selective Inline ⚠️</summary>

```c
struct task_struct *get_task_struct(struct task_struct *t);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8104c76e)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
```
```
In kernel/fork.c (ffffffff810888b9)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
```
```
In kernel/exit.c (ffffffff8108da9b)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:mm_update_next_owner
```
```
In kernel/sys.c (ffffffff810a5351)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_prlimit64
  - kernel/sys.c:__x64_sys_prlimit64
```
```
In kernel/pid.c (ffffffff810ae55c)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/pid.c:get_pid_task
  - kernel/pid.c:find_get_task_by_vpid
```
```
In kernel/kthread.c (ffffffff810b19e6)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_stop
```
```
In kernel/smpboot.c (ffffffff810b7fed)
Location: include/linux/sched/task.h:108
Inline: True
```
```
In kernel/sched/core.c (ffffffff810c5500)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__ia32_sys_sched_setattr
  - kernel/sched/core.c:__x64_sys_sched_setattr
  - kernel/sched/core.c:do_sched_setscheduler
  - kernel/sched/core.c:wake_q_add
```
```
In kernel/sched/fair.c (ffffffff810ccdca)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_find_cpu
```
```
In kernel/sched/rt.c (ffffffff810d8c1c)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/sched/rt.c:push_rt_task
```
```
In kernel/sched/deadline.c (ffffffff810da708)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/sched/deadline.c:start_dl_timer
  - kernel/sched/deadline.c:task_non_contending
```
```
In kernel/locking/rwsem.c (ffffffff810ecfd2)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_mark_wake
```
```
In kernel/locking/rtmutex.c (ffffffff810ef397)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_adjust_pi
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:task_blocks_on_rt_mutex
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
```
```
In kernel/irq/manage.c (ffffffff8110055e)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/irq/manage.c:setup_irq_thread
```
```
In kernel/rcu/update.c (ffffffff8110d0fd)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/kcmp.c (ffffffff8111b962)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/kcmp.c:__do_sys_kcmp
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8112e2f2)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:__get_task_for_clock
```
```
In kernel/futex.c (ffffffff81135b4b)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/futex.c:mark_wake_futex
```
```
In kernel/cgroup/cgroup.c (ffffffff81151820)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_task_iter_next
  - kernel/cgroup/cgroup.c:cgroup_procs_write_start
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81154345)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
```
In kernel/hung_task.c (ffffffff8117aeff)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/hung_task.c:watchdog
  - kernel/hung_task.c:watchdog
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff8119e455)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In kernel/events/core.c (ffffffff811feb36)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:alloc_perf_context
```
```
In mm/oom_kill.c (ffffffff812137d0)
Location: include/linux/sched/task.h:108
Inline: True
Direct callers:
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/page_io.c (ffffffff8127092a)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
```
```
In mm/mempolicy.c (ffffffff8128329f)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_migrate_pages
```
```
In mm/migrate.c (ffffffff8129be27)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - mm/migrate.c:kernel_move_pages
```
```
In mm/memory-failure.c (ffffffff812b3f56)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - mm/memory-failure.c:add_to_kill
```
```
In fs/proc/base.c (ffffffff8135fba9)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_lookup
  - fs/proc/base.c:next_tgid
  - fs/proc/base.c:proc_pid_lookup
```
```
In security/yama/yama_lsm.c (ffffffff8149bbc9)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_task_prctl
  - security/yama/yama_lsm.c:report_access
  - security/yama/yama_lsm.c:report_access
```
```
In drivers/tty/tty_ldsem.c (ffffffff81a2f0df)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_read
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff8177f70a)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_map
```
**Symbols:**

```
ffffffff812137d0-ffffffff812137de: get_task_struct (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Selective Inline ⚠️</summary>

```c
struct task_struct *get_task_struct(struct task_struct *t);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105c9ce)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
```
```
In kernel/fork.c (ffffffff81099e29)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
```
```
In kernel/exit.c (ffffffff8109f017)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:mm_update_next_owner
```
```
In kernel/sys.c (ffffffff810b5f71)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_prlimit64
  - kernel/sys.c:__x64_sys_prlimit64
```
```
In kernel/pid.c (ffffffff810bf29c)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/pid.c:get_pid_task
  - kernel/pid.c:find_get_task_by_vpid
```
```
In kernel/kthread.c (ffffffff810c26f6)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_stop
```
```
In kernel/smpboot.c (ffffffff810c8cfd)
Location: include/linux/sched/task.h:108
Inline: True
```
```
In kernel/sched/core.c (ffffffff810d3850)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__ia32_sys_sched_setattr
  - kernel/sched/core.c:__x64_sys_sched_setattr
  - kernel/sched/core.c:do_sched_setscheduler
  - kernel/sched/core.c:wake_q_add
```
```
In kernel/sched/fair.c (ffffffff810da146)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_find_cpu
```
```
In kernel/sched/rt.c (ffffffff810e5d8c)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/sched/rt.c:push_rt_task
```
```
In kernel/sched/deadline.c (ffffffff810e7808)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/sched/deadline.c:start_dl_timer
  - kernel/sched/deadline.c:task_non_contending
```
```
In kernel/locking/rwsem.c (ffffffff810f9f82)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_mark_wake
```
```
In kernel/locking/rtmutex.c (ffffffff810fc367)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_adjust_pi
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:task_blocks_on_rt_mutex
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
```
```
In kernel/irq/manage.c (ffffffff8110d70e)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/irq/manage.c:setup_irq_thread
```
```
In kernel/rcu/update.c (ffffffff81119f7d)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/kcmp.c (ffffffff81126df2)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/kcmp.c:__do_sys_kcmp
```
```
In kernel/time/posix-cpu-timers.c (ffffffff81139652)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:__get_task_for_clock
```
```
In kernel/futex.c (ffffffff8114069b)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/futex.c:mark_wake_futex
```
```
In kernel/cgroup/cgroup.c (ffffffff8115c330)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_task_iter_next
  - kernel/cgroup/cgroup.c:cgroup_procs_write_start
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8115eeab)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
```
In kernel/hung_task.c (ffffffff81185b8f)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/hung_task.c:watchdog
  - kernel/hung_task.c:watchdog
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811a8f15)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In kernel/events/core.c (ffffffff81209b06)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:alloc_perf_context
```
```
In mm/oom_kill.c (ffffffff8121e3c0)
Location: include/linux/sched/task.h:108
Inline: True
Direct callers:
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/page_io.c (ffffffff8127c89a)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
```
```
In mm/mempolicy.c (ffffffff8128f42f)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_migrate_pages
```
```
In mm/migrate.c (ffffffff812a82d7)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - mm/migrate.c:kernel_move_pages
```
```
In mm/memory-failure.c (ffffffff812c0f66)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - mm/memory-failure.c:add_to_kill
```
```
In fs/proc/base.c (ffffffff8136cbe9)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_lookup
  - fs/proc/base.c:next_tgid
  - fs/proc/base.c:proc_pid_lookup
```
```
In security/yama/yama_lsm.c (ffffffff814a7249)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_task_prctl
  - security/yama/yama_lsm.c:report_access
  - security/yama/yama_lsm.c:report_access
```
```
In drivers/tty/tty_ldsem.c (ffffffff81adf11f)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_read
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff817ca4da)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_map
```
**Symbols:**

```
ffffffff8121e3c0-ffffffff8121e3ce: get_task_struct (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Selective Inline ⚠️</summary>

```c
struct task_struct *get_task_struct(struct task_struct *t);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105dee3)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
```
```
In kernel/fork.c (ffffffff810a1a92)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
```
```
In kernel/exit.c (ffffffff810a6f61)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:mm_update_next_owner
```
```
In kernel/sys.c (ffffffff810be2bb)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_prlimit64
  - kernel/sys.c:__x64_sys_prlimit64
```
```
In kernel/pid.c (ffffffff810c77bd)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/pid.c:get_pid_task
  - kernel/pid.c:find_get_task_by_vpid
```
```
In kernel/kthread.c (ffffffff810cacb6)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_stop
```
```
In kernel/smpboot.c (ffffffff810d126d)
Location: include/linux/sched/task.h:108
Inline: True
```
```
In kernel/sched/core.c (ffffffff810de7d9)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__ia32_sys_sched_setattr
  - kernel/sched/core.c:__x64_sys_sched_setattr
  - kernel/sched/core.c:do_sched_setscheduler
  - kernel/sched/core.c:wake_q_add
```
```
In kernel/sched/fair.c (ffffffff810e5b72)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_find_cpu
```
```
In kernel/sched/rt.c (ffffffff810f05a0)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/sched/rt.c:push_rt_task
```
```
In kernel/sched/deadline.c (ffffffff810f2e08)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/sched/deadline.c:start_dl_timer
  - kernel/sched/deadline.c:task_non_contending
```
```
In kernel/locking/rwsem.c (ffffffff811050f2)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_mark_wake
```
```
In kernel/locking/rtmutex.c (ffffffff81107587)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_adjust_pi
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:task_blocks_on_rt_mutex
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
```
```
In kernel/irq/manage.c (ffffffff81118c6e)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/irq/manage.c:setup_irq_thread
```
```
In kernel/rcu/update.c (ffffffff811256d9)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/kcmp.c (ffffffff8113344d)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/kcmp.c:__do_sys_kcmp
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811460f3)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:__get_task_for_clock
```
```
In kernel/futex.c (ffffffff8114d32b)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/futex.c:mark_wake_futex
```
```
In kernel/cgroup/cgroup.c (ffffffff81169460)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_task_iter_next
  - kernel/cgroup/cgroup.c:cgroup_procs_write_start
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8116c122)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
```
In kernel/hung_task.c (ffffffff811934d8)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/hung_task.c:watchdog
  - kernel/hung_task.c:watchdog
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811b6d55)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In kernel/events/core.c (ffffffff812188bd)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:alloc_perf_context
```
```
In mm/oom_kill.c (ffffffff8122d410)
Location: include/linux/sched/task.h:108
Inline: True
Direct callers:
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/page_io.c (ffffffff8128c46a)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
```
```
In mm/mempolicy.c (ffffffff8129f8b4)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_migrate_pages
```
```
In mm/migrate.c (ffffffff812b85dc)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - mm/migrate.c:kernel_move_pages
```
```
In mm/memory-failure.c (ffffffff812d1a26)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - mm/memory-failure.c:add_to_kill
```
```
In fs/proc/base.c (ffffffff813804df)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_lookup
  - fs/proc/base.c:next_tgid
  - fs/proc/base.c:proc_pid_lookup
```
```
In security/yama/yama_lsm.c (ffffffff814bfc43)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_task_prctl
  - security/yama/yama_lsm.c:report_access
  - security/yama/yama_lsm.c:report_access
```
```
In drivers/tty/tty_ldsem.c (ffffffff81aeb8a8)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_read
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff817e477a)
Location: include/linux/sched/task.h:108
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_map
```
**Symbols:**

```
ffffffff8122d410-ffffffff8122d41e: get_task_struct (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
<b>Arch</b>
<ul>
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
