# Function: <code>dsb_sev</code>

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
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In init/main.c (c15012a4)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
```
```
In arch/arm/kernel/traps.c (c030f48c)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - arch/arm/kernel/traps.c:die
```
```
In arch/arm/kernel/smp.c (c0313734)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - arch/arm/kernel/smp.c:handle_IPI
```
```
In arch/arm/mm/flush.c (0)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
```
```
In arch/arm/mm/copypage-v6.c (0)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
```
```
In arch/arm/common/mcpm_entry.c (c03261b4)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - arch/arm/common/mcpm_entry.c:mcpm_cpu_powered_up
  - arch/arm/common/mcpm_entry.c:mcpm_cpu_suspend
  - arch/arm/common/mcpm_entry.c:mcpm_cpu_power_down
  - arch/arm/common/mcpm_entry.c:mcpm_cpu_power_down
  - arch/arm/common/mcpm_entry.c:mcpm_cpu_power_up
```
```
In arch/arm/common/mcpm_platsmp.c (c0326308)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - arch/arm/common/mcpm_platsmp.c:mcpm_boot_secondary
```
```
In arch/arm/common/bL_switcher.c (c0326700)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - arch/arm/common/bL_switcher.c:bL_switch_request_cb
  - arch/arm/common/bL_switcher.c:bL_switch_request_cb
  - arch/arm/common/bL_switcher.c:bL_switcher_thread
  - arch/arm/common/bL_switcher.c:bL_switch_to
```
```
In arch/arm/mach-actions/platsmp.c (c032c898)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
```
```
In arch/arm/mach-aspeed/platsmp.c (c032ca44)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - arch/arm/mach-aspeed/platsmp.c:aspeed_g6_boot_secondary
```
```
In arch/arm/mach-exynos/pm.c (c032d640)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - arch/arm/mach-exynos/pm.c:exynos_cpu0_enter_aftr
```
```
In arch/arm/mach-exynos/platsmp.c (c032e790)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - arch/arm/mach-exynos/platsmp.c:exynos_boot_secondary
  - arch/arm/mach-exynos/platsmp.c:exynos_boot_secondary
  - arch/arm/mach-exynos/platsmp.c:exynos_secondary_init
```
```
In arch/arm/mach-hisi/platmcpm.c (c032f530)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - arch/arm/mach-hisi/platmcpm.c:hip04_cpu_kill
  - arch/arm/mach-hisi/platmcpm.c:hip04_cpu_kill
  - arch/arm/mach-hisi/platmcpm.c:hip04_cpu_kill
  - arch/arm/mach-hisi/platmcpm.c:hip04_cpu_die
  - arch/arm/mach-hisi/platmcpm.c:hip04_cpu_die
  - arch/arm/mach-hisi/platmcpm.c:hip04_boot_secondary
```
```
In arch/arm/mach-imx/cpuidle-imx6q.c (c0332370)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - arch/arm/mach-imx/cpuidle-imx6q.c:imx6q_enter_wait
  - arch/arm/mach-imx/cpuidle-imx6q.c:imx6q_enter_wait
```
```
In arch/arm/mach-imx/src.c (c150f3f4)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - arch/arm/mach-imx/src.c:imx_src_init
  - arch/arm/mach-imx/src.c:imx_enable_cpu
```
```
In arch/arm/mach-npcm/platsmp.c (c0334e34)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - arch/arm/mach-npcm/platsmp.c:npcm7xx_smp_boot_secondary
```
```
In arch/arm/mach-omap2/omap-smp.c (c033c868)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - arch/arm/mach-omap2/omap-smp.c:omap4_boot_secondary
```
```
In arch/arm/mach-rockchip/platsmp.c (c1519548)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - arch/arm/mach-rockchip/platsmp.c:rockchip_smp_prepare_cpus
```
```
In arch/arm/mach-tegra/pm.c (c034a9c8)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - arch/arm/mach-tegra/pm.c:tegra_set_cpu_in_lp2
  - arch/arm/mach-tegra/pm.c:tegra_clear_cpu_in_lp2
```
```
In arch/arm/plat-versatile/platsmp.c (c034fb98)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - arch/arm/plat-versatile/platsmp.c:versatile_boot_secondary
  - arch/arm/plat-versatile/platsmp.c:versatile_secondary_init
```
```
In kernel/fork.c (c0354138)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - kernel/fork.c:unshare_files
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:walk_process_tree
  - kernel/fork.c:_do_fork
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:mm_release
  - kernel/fork.c:get_task_mm
  - kernel/fork.c:get_task_exe_file
  - kernel/fork.c:mmput_async_fn
  - kernel/fork.c:mmput
  - kernel/fork.c:dup_mmap
```
```
In kernel/panic.c (c0354408)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
```
```
In kernel/cpu.c (c0357b18)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - kernel/cpu.c:clear_tasks_mm_cpumask
```
```
In kernel/exit.c (c0359b08)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - kernel/exit.c:do_wait
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:do_group_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:mm_update_next_owner
  - kernel/exit.c:mm_update_next_owner
  - kernel/exit.c:mm_update_next_owner
  - kernel/exit.c:mm_update_next_owner
  - kernel/exit.c:is_current_pgrp_orphaned
  - kernel/exit.c:release_task
  - kernel/exit.c:release_task
  - kernel/exit.c:release_task
```
```
In kernel/resource.c (c035e294)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - kernel/resource.c:iomem_is_exclusive
  - kernel/resource.c:iomem_map_sanity_check
  - kernel/resource.c:__release_region
  - kernel/resource.c:__release_region
  - kernel/resource.c:__request_region
  - kernel/resource.c:__request_region
  - kernel/resource.c:reserve_region_with_split
  - kernel/resource.c:adjust_resource
  - kernel/resource.c:remove_resource
  - kernel/resource.c:insert_resource_expand_to_fit
  - kernel/resource.c:insert_resource_conflict
  - kernel/resource.c:lookup_resource
  - kernel/resource.c:allocate_resource
  - kernel/resource.c:region_intersects
  - kernel/resource.c:find_next_iomem_res
  - kernel/resource.c:release_resource
  - kernel/resource.c:request_resource_conflict
  - kernel/resource.c:release_child_resources
  - kernel/resource.c:r_stop
```
```
In kernel/ptrace.c (c036247c)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - kernel/ptrace.c:__se_sys_ptrace
  - kernel/ptrace.c:__se_sys_ptrace
  - kernel/ptrace.c:__se_sys_ptrace
  - kernel/ptrace.c:__se_sys_ptrace
  - kernel/ptrace.c:__se_sys_ptrace
  - kernel/ptrace.c:__se_sys_ptrace
  - kernel/ptrace.c:__se_sys_ptrace
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_peek_siginfo
  - kernel/ptrace.c:ptrace_may_access
  - kernel/ptrace.c:__ptrace_unlink
```
```
In kernel/user.c (c151ca54)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - kernel/user.c:uid_cache_init
  - kernel/user.c:alloc_uid
  - kernel/user.c:alloc_uid
```
```
In kernel/signal.c (c036aa90)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - kernel/signal.c:kdb_send_sig
  - kernel/signal.c:kdb_send_sig
  - kernel/signal.c:do_sigaction
  - kernel/signal.c:kernel_sigaction
  - kernel/signal.c:__se_sys_kill
  - kernel/signal.c:do_sigtimedwait
  - kernel/signal.c:do_sigtimedwait
  - kernel/signal.c:do_sigpending
  - kernel/signal.c:__set_current_blocked
  - kernel/signal.c:exit_signals
  - kernel/signal.c:exit_signals
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_notify
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:kill_pgrp
  - kernel/signal.c:dequeue_signal
  - kernel/signal.c:calculate_sigpending
```
```
In kernel/sys.c (c036b8c8)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm
  - kernel/sys.c:prctl_set_auxv
  - kernel/sys.c:prctl_set_mm_map
  - kernel/sys.c:do_prlimit
  - kernel/sys.c:do_prlimit
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__se_sys_setpgid
  - kernel/sys.c:__se_sys_getpriority
  - kernel/sys.c:__se_sys_setpriority
```
```
In kernel/umh.c (c036f5b8)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - kernel/umh.c:call_usermodehelper_exec_async
  - kernel/umh.c:call_usermodehelper_exec_async
```
```
In kernel/workqueue.c (c0376650)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_offline_cpu
  - kernel/workqueue.c:workqueue_offline_cpu
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:wq_worker_comm
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:__flush_work
  - kernel/workqueue.c:__flush_work
  - kernel/workqueue.c:drain_workqueue
  - kernel/workqueue.c:flush_workqueue_prep_pwqs
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:pool_mayday_timeout
  - kernel/workqueue.c:pool_mayday_timeout
  - kernel/workqueue.c:idle_worker_timeout
  - kernel/workqueue.c:create_worker
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:wq_worker_sleeping
```
```
In kernel/pid.c (c0377a80)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - kernel/pid.c:disable_pid_allocation
  - kernel/pid.c:alloc_pid
  - kernel/pid.c:alloc_pid
  - kernel/pid.c:alloc_pid
  - kernel/pid.c:alloc_pid
```
```
In kernel/task_work.c (c0377e44)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - kernel/task_work.c:task_work_run
```
```
In kernel/params.c (c0378ef8)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - kernel/params.c:param_set_charp
  - kernel/params.c:maybe_kfree_parameter
```
```
In kernel/kthread.c (c037a4bc)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_flush_work
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthreadd
  - kernel/kthread.c:kthreadd
  - kernel/kthread.c:kthreadd
  - kernel/kthread.c:__kthread_create_on_node
```
```
In kernel/nsproxy.c (c037bc38)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - kernel/nsproxy.c:switch_task_namespaces
```
```
In kernel/async.c (c037e6fc)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - kernel/async.c:async_unregister_domain
```
```
In kernel/ucount.c (c037fb00)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - kernel/ucount.c:inc_ucount
  - kernel/ucount.c:inc_ucount
```
```
In kernel/sched/core.c (c0387514)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - kernel/sched/core.c:tg_set_cfs_bandwidth
  - kernel/sched/core.c:tg_set_cfs_bandwidth
  - kernel/sched/core.c:cpu_util_update_eff
  - kernel/sched/core.c:cpu_cgroup_can_attach
  - kernel/sched/core.c:cpu_cgroup_fork
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:normalize_rt_tasks
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:init_idle
  - kernel/sched/core.c:sched_rr_get_interval
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:do_sched_yield
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:task_sched_runtime
  - kernel/sched/core.c:finish_task_switch
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:move_queued_task
  - kernel/sched/core.c:__hrtick_start
  - kernel/sched/core.c:hrtick
  - kernel/sched/core.c:task_rq_lock
  - kernel/sched/core.c:__task_rq_lock
```
```
In kernel/sched/cputime.c (c038f220)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In kernel/sched/idle.c (c038f978)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - kernel/sched/idle.c:dequeue_task_idle
```
```
In kernel/sched/fair.c (c039adb4)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - kernel/sched/fair.c:online_fair_sched_group
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:rq_online_fair
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:rebalance_domains
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:throttle_cfs_rq
  - kernel/sched/fair.c:dequeue_entity
```
```
In kernel/sched/rt.c (c039ef7c)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - kernel/sched/rt.c:sched_rt_handler
  - kernel/sched/rt.c:tg_set_rt_bandwidth
  - kernel/sched/rt.c:tg_set_rt_bandwidth
  - kernel/sched/rt.c:tg_set_rt_bandwidth
  - kernel/sched/rt.c:rq_offline_rt
  - kernel/sched/rt.c:rq_offline_rt
  - kernel/sched/rt.c:rq_offline_rt
  - kernel/sched/rt.c:rq_offline_rt
  - kernel/sched/rt.c:rq_online_rt
  - kernel/sched/rt.c:rq_online_rt
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:rto_push_irq_work_func
  - kernel/sched/rt.c:rto_push_irq_work_func
  - kernel/sched/rt.c:push_rt_task
  - kernel/sched/rt.c:push_rt_task
  - kernel/sched/rt.c:push_rt_task
  - kernel/sched/rt.c:push_rt_task
  - kernel/sched/rt.c:push_rt_task
  - kernel/sched/rt.c:__enqueue_rt_entity
  - kernel/sched/rt.c:update_curr_rt
  - kernel/sched/rt.c:sched_rt_period_timer
  - kernel/sched/rt.c:sched_rt_period_timer
  - kernel/sched/rt.c:sched_rt_period_timer
  - kernel/sched/rt.c:sched_rt_period_timer
  - kernel/sched/rt.c:sched_rt_period_timer
```
```
In kernel/sched/deadline.c (c03a4d74)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:dl_add_task_root_domain
  - kernel/sched/deadline.c:dl_add_task_root_domain
  - kernel/sched/deadline.c:set_cpus_allowed_dl
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:find_lock_later_rq
  - kernel/sched/deadline.c:find_lock_later_rq
  - kernel/sched/deadline.c:find_lock_later_rq
  - kernel/sched/deadline.c:find_lock_later_rq
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:update_curr_dl
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:init_dl_bw
  - kernel/sched/deadline.c:task_non_contending
```
```
In kernel/sched/wait.c (c03a60e0)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - kernel/sched/wait.c:do_wait_intr_irq
  - kernel/sched/wait.c:do_wait_intr
```
```
In kernel/sched/swait.c (c03a67f0)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - kernel/sched/swait.c:swake_up_all
  - kernel/sched/swait.c:swake_up_all
```
```
In kernel/sched/completion.c (c0e9aa9c)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - kernel/sched/completion.c:wait_for_completion_killable_timeout
  - kernel/sched/completion.c:wait_for_completion_killable_timeout
  - kernel/sched/completion.c:wait_for_completion_killable
  - kernel/sched/completion.c:wait_for_completion_killable
  - kernel/sched/completion.c:wait_for_completion_interruptible_timeout
  - kernel/sched/completion.c:wait_for_completion_interruptible_timeout
  - kernel/sched/completion.c:wait_for_completion_interruptible
  - kernel/sched/completion.c:wait_for_completion_interruptible
  - kernel/sched/completion.c:wait_for_completion_io_timeout
  - kernel/sched/completion.c:wait_for_completion_io_timeout
  - kernel/sched/completion.c:wait_for_completion_io
  - kernel/sched/completion.c:wait_for_completion_io
  - kernel/sched/completion.c:wait_for_completion_timeout
  - kernel/sched/completion.c:wait_for_completion_timeout
  - kernel/sched/completion.c:wait_for_completion
  - kernel/sched/completion.c:wait_for_completion
```
```
In kernel/sched/cpuacct.c (c03b0a84)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - kernel/sched/cpuacct.c:cpuacct_all_seq_show
  - kernel/sched/cpuacct.c:cpuusage_write
  - kernel/sched/cpuacct.c:cpuacct_cpuusage_read
```
```
In kernel/sched/cpufreq_schedutil.c (c03b21b4)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_update_shared
  - kernel/sched/cpufreq_schedutil.c:sugov_update_single
```
```
In kernel/sched/psi.c (c03b48d8)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - kernel/sched/psi.c:cgroup_move_task
  - kernel/sched/psi.c:psi_memstall_leave
  - kernel/sched/psi.c:psi_memstall_enter
```
```
In kernel/locking/mutex.c (c0e9c0ac)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - kernel/locking/mutex.c:ww_mutex_lock_interruptible
  - kernel/locking/mutex.c:ww_mutex_lock
```
```
In kernel/locking/semaphore.c (c0e9cad8)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - kernel/locking/semaphore.c:__down_timeout
  - kernel/locking/semaphore.c:__down_killable
  - kernel/locking/semaphore.c:__down_interruptible
  - kernel/locking/semaphore.c:__down
```
```
In kernel/locking/rwsem.c (c03b5d3c)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
```
In kernel/locking/spinlock.c (c0e9f0cc)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_write_unlock_irqrestore
  - kernel/locking/spinlock.c:_raw_read_unlock_irqrestore
  - kernel/locking/spinlock.c:_raw_write_unlock_bh
  - kernel/locking/spinlock.c:_raw_read_unlock_bh
  - kernel/locking/spinlock.c:_raw_spin_unlock_irqrestore
  - kernel/locking/spinlock.c:_raw_spin_unlock_bh
```
```
In kernel/locking/rtmutex.c (c03b7d00)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_cleanup_proxy_lock
  - kernel/locking/rtmutex.c:rt_mutex_wait_proxy_lock
  - kernel/locking/rtmutex.c:rt_mutex_start_proxy_lock
  - kernel/locking/rtmutex.c:__rt_mutex_slowlock
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:mark_wakeup_next_waiter
  - kernel/locking/rtmutex.c:task_blocks_on_rt_mutex
  - kernel/locking/rtmutex.c:task_blocks_on_rt_mutex
  - kernel/locking/rtmutex.c:task_blocks_on_rt_mutex
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
```
```
In kernel/power/process.c (c03bab30)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - kernel/power/process.c:thaw_processes
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/power/suspend.c (c03bb698)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
```
```
In kernel/power/wakelock.c (c03c40bc)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - kernel/power/wakelock.c:__wakelocks_gc
```
```
In kernel/printk/printk.c (c03c49bc)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - kernel/printk/printk.c:kmsg_dump_rewind
  - kernel/printk/printk.c:kmsg_dump_get_buffer
  - kernel/printk/printk.c:kmsg_dump_get_buffer
  - kernel/printk/printk.c:kmsg_dump_get_line
  - kernel/printk/printk.c:kmsg_dump
  - kernel/printk/printk.c:register_console
  - kernel/printk/printk.c:console_flush_on_panic
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:syslog_print_all
  - kernel/printk/printk.c:syslog_print_all
  - kernel/printk/printk.c:devkmsg_open
  - kernel/printk/printk.c:devkmsg_poll
  - kernel/printk/printk.c:devkmsg_llseek
  - kernel/printk/printk.c:devkmsg_read
  - kernel/printk/printk.c:devkmsg_read
  - kernel/printk/printk.c:devkmsg_read
  - kernel/printk/printk.c:devkmsg_read
  - kernel/printk/printk.c:setup_log_buf
```
```
In kernel/printk/printk_safe.c (c03c8e28)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:vprintk_func
```
```
In kernel/irq/irqdesc.c (c03c8fc4)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:actions_show
  - kernel/irq/irqdesc.c:name_show
  - kernel/irq/irqdesc.c:wakeup_show
  - kernel/irq/irqdesc.c:type_show
  - kernel/irq/irqdesc.c:hwirq_show
  - kernel/irq/irqdesc.c:chip_name_show
```
```
In kernel/irq/handle.c (c03ca17c)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - kernel/irq/handle.c:handle_irq_event
```
```
In kernel/irq/manage.c (c03cb5ec)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_thread
  - kernel/irq/manage.c:irq_setup_affinity
```
```
In kernel/irq/spurious.c (c03cd7e8)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - kernel/irq/spurious.c:try_one_irq
  - kernel/irq/spurious.c:irq_wait_for_poll
```
```
In kernel/irq/chip.c (c03cf0e0)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_untracked_irq
  - kernel/irq/chip.c:handle_untracked_irq
  - kernel/irq/chip.c:handle_simple_irq
  - kernel/irq/chip.c:handle_nested_irq
  - kernel/irq/chip.c:handle_nested_irq
```
```
In kernel/irq/generic-chip.c (c03d0ea8)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_remove_generic_chip
  - kernel/irq/generic-chip.c:irq_setup_generic_chip
  - kernel/irq/generic-chip.c:irq_gc_set_wake
  - kernel/irq/generic-chip.c:irq_gc_eoi
  - kernel/irq/generic-chip.c:irq_gc_mask_disable_and_ack_set
  - kernel/irq/generic-chip.c:irq_gc_ack_clr_bit
  - kernel/irq/generic-chip.c:irq_gc_ack_set_bit
  - kernel/irq/generic-chip.c:irq_gc_unmask_enable_reg
  - kernel/irq/generic-chip.c:irq_gc_mask_clr_bit
  - kernel/irq/generic-chip.c:irq_gc_mask_set_bit
  - kernel/irq/generic-chip.c:irq_gc_mask_disable_reg
```
```
In kernel/irq/autoprobe.c (c03d1bd0)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - kernel/irq/autoprobe.c:probe_irq_off
  - kernel/irq/autoprobe.c:probe_irq_mask
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
```
```
In kernel/irq/cpuhotplug.c (c03d5398)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
```
```
In kernel/rcu/sync.c (c03d7e2c)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - kernel/rcu/sync.c:rcu_sync_dtor
  - kernel/rcu/sync.c:rcu_sync_exit
  - kernel/rcu/sync.c:rcu_sync_enter
```
```
In kernel/rcu/srcutree.c (c03d9abc)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:srcu_reschedule
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:srcu_gp_end
  - kernel/rcu/srcutree.c:srcu_gp_end
  - kernel/rcu/srcutree.c:srcu_gp_end
  - kernel/rcu/srcutree.c:srcu_gp_end
  - kernel/rcu/srcutree.c:srcu_gp_start
```
```
In kernel/rcu/tree.c (c03dbcb4)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:rcu_exp_wait_wake
  - kernel/rcu/tree.c:rcu_report_exp_cpu_mult
  - kernel/rcu/tree.c:rcu_iw_handler
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcu_report_dead
  - kernel/rcu/tree.c:rcutree_prepare_cpu
  - kernel/rcu/tree.c:rcu_force_quiescent_state
  - kernel/rcu/tree.c:rcu_force_quiescent_state
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_init
  - kernel/rcu/tree.c:rcu_gp_init
  - kernel/rcu/tree.c:rcu_gp_init
  - kernel/rcu/tree.c:rcu_gp_init
  - kernel/rcu/tree.c:rcu_gp_init
  - kernel/rcu/tree.c:rcu_gp_init
  - kernel/rcu/tree.c:rcu_gp_init
  - kernel/rcu/tree.c:rcu_accelerate_cbs_unlocked
  - kernel/rcu/tree.c:rcu_accelerate_cbs
  - kernel/rcu/tree.c:rcu_accelerate_cbs
```
```
In kernel/kcmp.c (c03e2e44)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - kernel/kcmp.c:__se_sys_kcmp
  - kernel/kcmp.c:get_file_raw_ptr
```
```
In kernel/freezer.c (c03e32a8)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - kernel/freezer.c:set_freezable
  - kernel/freezer.c:__refrigerator
```
```
In kernel/time/timer.c (c03ea03c)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:get_next_timer_interrupt
  - kernel/time/timer.c:add_timer_on
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:mod_timer_pending
```
```
In kernel/time/hrtimer.c (c03ec5c0)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
  - kernel/time/hrtimer.c:retrigger_next_event
```
```
In kernel/time/timekeeping.c (c03f09b4)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:xtime_update
```
```
In kernel/time/posix-timers.c (c03f716c)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:exit_itimers
  - kernel/time/posix-timers.c:exit_itimers
  - kernel/time/posix-timers.c:__se_sys_timer_delete
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/time/posix-cpu-timers.c (c03f9134)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:do_cpu_nanosleep
  - kernel/time/posix-cpu-timers.c:do_cpu_nanosleep
  - kernel/time/posix-cpu-timers.c:do_cpu_nanosleep
  - kernel/time/posix-cpu-timers.c:do_cpu_nanosleep
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:update_rlimit_cpu
```
```
In kernel/time/itimer.c (c03fab0c)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/itimer.c:set_cpu_itimer
  - kernel/time/itimer.c:do_getitimer
  - kernel/time/itimer.c:get_cpu_itimer
```
```
In kernel/time/clockevents.c (c03fb644)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - kernel/time/clockevents.c:sysfs_unbind_tick_dev
  - kernel/time/clockevents.c:sysfs_show_current_tick_dev
  - kernel/time/clockevents.c:tick_offline_cpu
  - kernel/time/clockevents.c:__clockevents_unbind
```
```
In kernel/time/tick-common.c (c03fc978)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_unfreeze
  - kernel/time/tick-common.c:tick_freeze
  - kernel/time/tick-common.c:tick_periodic
```
```
In kernel/time/tick-broadcast.c (c03fdb58)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast
  - kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_update_freq
```
```
In kernel/time/tick-sched.c (c03fe538)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_init_jiffy_update
```
```
In kernel/futex.c (c040476c)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - kernel/futex.c:do_futex
  - kernel/futex.c:do_futex
  - kernel/futex.c:do_futex
  - kernel/futex.c:do_futex
  - kernel/futex.c:futex_cleanup_begin
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait
  - kernel/futex.c:futex_wait
  - kernel/futex.c:futex_wait_setup
  - kernel/futex.c:futex_wait_setup
  - kernel/futex.c:futex_wait_queue_me
  - kernel/futex.c:fixup_pi_state_owner
  - kernel/futex.c:fixup_pi_state_owner
  - kernel/futex.c:fixup_pi_state_owner
  - kernel/futex.c:fixup_pi_state_owner
  - kernel/futex.c:fixup_pi_state_owner
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_wake
  - kernel/futex.c:attach_to_pi_owner
  - kernel/futex.c:attach_to_pi_owner
  - kernel/futex.c:attach_to_pi_state
  - kernel/futex.c:attach_to_pi_state
```
```
In kernel/acct.c (c040f210)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - kernel/acct.c:acct_collect
  - kernel/acct.c:fill_ac
```
```
In kernel/cgroup/cgroup.c (c041b4c4)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_release
  - kernel/cgroup/cgroup.c:cgroup_exit
  - kernel/cgroup/cgroup.c:cgroup_post_fork
  - kernel/cgroup/cgroup.c:cgroup_post_fork
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write
  - kernel/cgroup/cgroup.c:css_task_iter_end
  - kernel/cgroup/cgroup.c:css_task_iter_next
  - kernel/cgroup/cgroup.c:css_task_iter_start
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup.c:cgroup_migrate
  - kernel/cgroup/cgroup.c:cgroup_migrate_finish
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:task_cgroup_path
  - kernel/cgroup/cgroup.c:cgroup_path_ns
  - kernel/cgroup/cgroup.c:cgroup_do_get_tree
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/cgroup/cgroup.c:cgroup_enable_task_cg_lists
  - kernel/cgroup/cgroup.c:cgroup_enable_task_cg_lists
  - kernel/cgroup/cgroup.c:cgroup_enable_task_cg_lists
  - kernel/cgroup/cgroup.c:cgroup_show_path
  - kernel/cgroup/cgroup.c:rebind_subsystems
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/cgroup.c:cgroup_task_count
```
```
In kernel/cgroup/rstat.c (c041c7a0)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show
  - kernel/cgroup/rstat.c:cgroup_rstat_flush
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
```
```
In kernel/cgroup/namespace.c (c041c948)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:cgroupns_get
  - kernel/cgroup/namespace.c:copy_cgroup_ns
```
```
In kernel/cgroup/cgroup-v1.c (c041e864)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_release_agent
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_show
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
  - kernel/cgroup/cgroup-v1.c:cgroup_attach_task_all
```
```
In kernel/cgroup/freezer.c (c041f6ac)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_freeze
  - kernel/cgroup/freezer.c:cgroup_freeze
  - kernel/cgroup/freezer.c:cgroup_leave_frozen
  - kernel/cgroup/freezer.c:cgroup_leave_frozen
  - kernel/cgroup/freezer.c:cgroup_enter_frozen
```
```
In kernel/cgroup/cpuset.c (c042578c)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:__cpuset_memory_pressure_bump
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_bind
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:cpuset_read_u64
  - kernel/cgroup/cpuset.c:cpuset_common_seq_show
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_flag
  - kernel/cgroup/cpuset.c:cpuset_change_task_nodemask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
```
```
In kernel/utsname.c (c0425a54)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - kernel/utsname.c:utsns_get
```
```
In kernel/pid_namespace.c (c0427a4c)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_for_children_get
  - kernel/pid_namespace.c:pidns_for_children_get
  - kernel/pid_namespace.c:zap_pid_ns_processes
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
```
In kernel/stop_machine.c (c04283f4)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stopper_thread
  - kernel/stop_machine.c:stop_two_cpus
  - kernel/stop_machine.c:stop_two_cpus
```
```
In kernel/auditsc.c (c04324e0)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_getname
```
```
In kernel/audit_tree.c (c0434a04)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_tree_freeing_mark
  - kernel/audit_tree.c:audit_tree_freeing_mark
  - kernel/audit_tree.c:audit_tree_freeing_mark
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:audit_trim_trees
  - kernel/audit_tree.c:audit_remove_tree_rule
  - kernel/audit_tree.c:audit_remove_tree_rule
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:prune_tree_chunks
```
```
In kernel/kprobes.c (c0436948)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - kernel/kprobes.c:recycle_rp_inst
```
```
In kernel/debug/debug_core.c (c0439a50)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_unregister_io_module
  - kernel/debug/debug_core.c:kgdb_register_io_module
  - kernel/debug/debug_core.c:kgdb_register_io_module
  - kernel/debug/debug_core.c:kgdb_register_io_module
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/debug/kdb/kdb_support.c (c0443fb4)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:debug_kusage
  - kernel/debug/kdb/kdb_support.c:debug_kmalloc
```
```
In kernel/seccomp.c (c0448a60)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
```
```
In kernel/taskstats.c (c044c650)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
```
```
In kernel/tracepoint.c (c044d944)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - kernel/tracepoint.c:syscall_unregfunc
  - kernel/tracepoint.c:syscall_regfunc
```
```
In kernel/trace/trace_clock.c (c044dad4)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock_global
```
```
In kernel/trace/ring_buffer.c (c045869c)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_free_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_empty
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_consume
  - kernel/trace/ring_buffer.c:ring_buffer_peek
  - kernel/trace/ring_buffer.c:rb_get_reader_page
```
```
In kernel/trace/trace.c (c0466514)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_read
  - kernel/trace/trace.c:saved_cmdlines_stop
  - kernel/trace/trace.c:tracing_cpumask_write
  - kernel/trace/trace.c:trace_find_cmdline
  - kernel/trace/trace.c:tracing_stop
  - kernel/trace/trace.c:tracing_snapshot_cond_disable
  - kernel/trace/trace.c:tracing_snapshot_cond_enable
  - kernel/trace/trace.c:tracing_cond_snapshot_data
```
```
In kernel/trace/trace_sched_wakeup.c (c046c98c)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:wakeup_reset
```
```
In kernel/trace/trace_stack.c (c046deb0)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:t_stop
  - kernel/trace/trace_stack.c:stack_max_size_write
  - kernel/trace/trace_stack.c:stack_trace_call
```
```
In kernel/trace/blktrace.c (c0473808)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:__blk_trace_startstop
  - kernel/trace/blktrace.c:__blk_trace_startstop
```
```
In kernel/trace/fgraph.c (c047437c)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - kernel/trace/fgraph.c:start_graph_tracing
```
```
In kernel/trace/trace_events.c (c0476498)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:remove_event_file_dir
```
```
In kernel/trace/trace_uprobe.c (c048b7cc)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:uprobe_perf_filter
  - kernel/trace/trace_uprobe.c:uprobe_perf_close
```
```
In kernel/bpf/syscall.c (c04939f0)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_task_fd_query
```
```
In kernel/bpf/percpu_freelist.c (c04ade60)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - kernel/bpf/percpu_freelist.c:__pcpu_freelist_pop
  - kernel/bpf/percpu_freelist.c:__pcpu_freelist_pop
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_populate
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_push
```
```
In kernel/bpf/bpf_lru_list.c (c04ae56c)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
```
```
In kernel/bpf/devmap.c (c04b6d74)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_free
```
```
In kernel/bpf/cpumap.c (c04b7964)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:bq_flush_to_queue
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In kernel/events/core.c (c04cc1ec)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_exit_context
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_event_exit_task_context
  - kernel/events/core.c:perf_event_exit_task_context
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:account_event
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:_free_event
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:perf_event_task_tick
  - kernel/events/core.c:__perf_event_task_sched_out
  - kernel/events/core.c:__perf_event_task_sched_out
  - kernel/events/core.c:__perf_event_task_sched_out
  - kernel/events/core.c:perf_event_addr_filters_sync
  - kernel/events/core.c:_perf_event_enable
  - kernel/events/core.c:_perf_event_enable
  - kernel/events/core.c:perf_install_in_context
  - kernel/events/core.c:perf_install_in_context
  - kernel/events/core.c:_perf_event_disable
  - kernel/events/core.c:_perf_event_disable
  - kernel/events/core.c:perf_remove_from_context
  - kernel/events/core.c:perf_lock_task_context
  - kernel/events/core.c:perf_lock_task_context
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:event_function_call
  - kernel/events/core.c:event_function_call
  - kernel/events/core.c:perf_ctx_unlock
  - kernel/events/core.c:perf_ctx_unlock
```
```
In kernel/events/uprobes.c (c04d7690)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:uprobe_deny_signal
  - kernel/events/uprobes.c:vma_has_uprobes
  - kernel/events/uprobes.c:uprobe_mmap
  - kernel/events/uprobes.c:__uprobe_unregister
  - kernel/events/uprobes.c:find_uprobe
  - kernel/events/uprobes.c:__replace_page
```
```
In kernel/padata.c (c04d7c48)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - kernel/padata.c:padata_do_serial
  - kernel/padata.c:padata_serial_worker
  - kernel/padata.c:padata_reorder
  - kernel/padata.c:padata_find_next
  - kernel/padata.c:padata_find_next
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_parallel_worker
```
```
In mm/filemap.c (c04de0ac)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_killable
  - mm/filemap.c:__lock_page
  - mm/filemap.c:put_and_wait_on_page_locked
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:file_check_and_advance_wb_err
```
```
In mm/oom_kill.c (c04e478c)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:find_lock_task_mm
```
```
In mm/fadvise.c (c04e58b8)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - mm/fadvise.c:generic_fadvise
  - mm/fadvise.c:generic_fadvise
```
```
In mm/page-writeback.c (c04e6c24)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - mm/page-writeback.c:tag_pages_for_writeback
  - mm/page-writeback.c:tag_pages_for_writeback
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:domain_update_bandwidth
```
```
In mm/truncate.c (c04ef5ac)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_final
  - mm/truncate.c:clear_shadow_entry
```
```
In mm/vmscan.c (c04f84bc)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
```
```
In mm/shmem.c (c04f8f54)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - mm/shmem.c:shmem_reconfigure
  - mm/shmem.c:shmem_reconfigure
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_lock
  - mm/shmem.c:shmem_fault
  - mm/shmem.c:shmem_fault
  - mm/shmem.c:shmem_fault
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_evict_inode
  - mm/shmem.c:shmem_getattr
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_free_swap
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_free_inode
  - mm/shmem.c:shmem_reserve_inode
  - mm/shmem.c:shmem_reserve_inode
```
```
In mm/util.c (c050038c)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - mm/util.c:get_cmdline
```
```
In mm/vmstat.c (c0500ff4)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showfree_print
```
```
In mm/backing-dev.c (c0503e24)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_put
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:bdi_register_va
  - mm/backing-dev.c:wb_blkcg_offline
  - mm/backing-dev.c:wb_memcg_offline
  - mm/backing-dev.c:bdi_debug_stats_show
```
```
In mm/mmu_context.c (c05049b0)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - mm/mmu_context.c:unuse_mm
  - mm/mmu_context.c:use_mm
```
```
In mm/percpu.c (c050705c)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_balance_workfn
```
```
In mm/slab_common.c (c0509ac4)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:memcg_deactivate_kmem_caches
```
```
In mm/list_lru.c (c05132d0)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - mm/list_lru.c:memcg_drain_all_list_lrus
  - mm/list_lru.c:memcg_update_all_list_lrus
  - mm/list_lru.c:list_lru_walk_node
  - mm/list_lru.c:list_lru_walk_one_irq
  - mm/list_lru.c:list_lru_walk_one
  - mm/list_lru.c:list_lru_del
  - mm/list_lru.c:list_lru_del
  - mm/list_lru.c:list_lru_add
  - mm/list_lru.c:list_lru_add
```
```
In mm/workingset.c (c0513428)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - mm/workingset.c:shadow_lru_isolate
  - mm/workingset.c:shadow_lru_isolate
  - mm/workingset.c:shadow_lru_isolate
```
```
In mm/gup.c (c0514248)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
```
```
In mm/highmem.c (c0515e2c)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - mm/highmem.c:kunmap_high
  - mm/highmem.c:kmap_flush_unused
```
```
In mm/memory.c (c05169f4)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - mm/memory.c:follow_pfn
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:do_fault
  - mm/memory.c:do_fault
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:finish_mkwrite_fault
  - mm/memory.c:finish_mkwrite_fault
  - mm/memory.c:wp_page_copy
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:insert_pfn
  - mm/memory.c:insert_page
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:__pte_alloc_kernel
  - mm/memory.c:__pte_alloc
```
```
In mm/mincore.c (c051c6b4)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mlock.c (c051de50)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - mm/mlock.c:user_shm_unlock
  - mm/mlock.c:user_shm_lock
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:munlock_vma_page
```
```
In mm/mmap.c (c0521284)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_link_file
  - mm/mmap.c:__remove_shared_vm_struct
```
```
In mm/mprotect.c (c052351c)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (c052403c)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (c0524f70)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (0)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
```
```
In mm/rmap.c (c05269f0)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_referenced_one
  - mm/rmap.c:__anon_vma_prepare
```
```
In mm/vmalloc.c (c0527cd4)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - mm/vmalloc.c:s_stop
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:vwrite
  - mm/vmalloc.c:vread
  - mm/vmalloc.c:setup_vmalloc_vm
  - mm/vmalloc.c:vm_map_ram
  - mm/vmalloc.c:vm_map_ram
  - mm/vmalloc.c:vm_map_ram
  - mm/vmalloc.c:vm_map_ram
  - mm/vmalloc.c:vm_map_ram
  - mm/vmalloc.c:vm_map_ram
  - mm/vmalloc.c:vm_unmap_ram
  - mm/vmalloc.c:vm_unmap_ram
  - mm/vmalloc.c:purge_fragmented_blocks_allcpus
  - mm/vmalloc.c:purge_fragmented_blocks_allcpus
  - mm/vmalloc.c:purge_fragmented_blocks_allcpus
  - mm/vmalloc.c:find_vmap_area
  - mm/vmalloc.c:free_vmap_area_noflush
  - mm/vmalloc.c:__purge_vmap_area_lazy
```
```
In mm/page_alloc.c (c0534650)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:__build_all_zonelists
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_pcppages_bulk
```
```
In mm/madvise.c (c0537924)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (c0539dd0)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - mm/swap_state.c:delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/swapfile.c (c0540104)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - mm/swapfile.c:mem_cgroup_throttle_swaprate
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:__swap_duplicate
  - mm/swapfile.c:__swap_duplicate
  - mm/swapfile.c:si_swapinfo
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:has_usable_swap
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_mm
  - mm/swapfile.c:count_swap_pages
  - mm/swapfile.c:count_swap_pages
  - mm/swapfile.c:swap_type_of
  - mm/swapfile.c:swap_type_of
  - mm/swapfile.c:swap_type_of
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:swp_swapcount
  - mm/swapfile.c:swp_swapcount
  - mm/swapfile.c:__swp_swapcount
  - mm/swapfile.c:__swp_swapcount
  - mm/swapfile.c:page_swapcount
  - mm/swapfile.c:page_swapcount
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:put_swap_page
  - mm/swapfile.c:put_swap_page
  - mm/swapfile.c:put_swap_page
  - mm/swapfile.c:put_swap_page
  - mm/swapfile.c:get_swap_page_of_type
  - mm/swapfile.c:get_swap_page_of_type
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:add_to_avail_list
  - mm/swapfile.c:del_from_avail_list
  - mm/swapfile.c:scan_swap_map_try_ssd_cluster
  - mm/swapfile.c:swap_discard_work
  - mm/swapfile.c:swap_do_scheduled_discard
  - mm/swapfile.c:swap_do_scheduled_discard
```
```
In mm/swap_slots.c (c054060c)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - mm/swap_slots.c:free_swap_slot
  - mm/swap_slots.c:free_swap_slot
```
```
In mm/frontswap.c (c0540b38)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - mm/frontswap.c:frontswap_curr_pages
  - mm/frontswap.c:frontswap_shrink
  - mm/frontswap.c:frontswap_register_ops
  - mm/frontswap.c:frontswap_register_ops
```
```
In mm/zswap.c (c0541b08)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_invalidate_area
  - mm/zswap.c:zswap_frontswap_invalidate_page
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_writeback_entry
  - mm/zswap.c:zswap_writeback_entry
  - mm/zswap.c:zswap_writeback_entry
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:zswap_pool_put
```
```
In mm/dmapool.c (c0542bc0)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - mm/dmapool.c:show_pools
```
```
In mm/mmu_notifier.c (c05436b8)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_notifier_put
  - mm/mmu_notifier.c:mmu_notifier_put
  - mm/mmu_notifier.c:mmu_notifier_unregister
  - mm/mmu_notifier.c:mmu_notifier_get_locked
  - mm/mmu_notifier.c:mmu_notifier_get_locked
  - mm/mmu_notifier.c:__mmu_notifier_register
  - mm/mmu_notifier.c:__mmu_notifier_release
```
```
In mm/ksm.c (c0545d98)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - mm/ksm.c:run_store
  - mm/ksm.c:run_store
  - mm/ksm.c:run_store
  - mm/ksm.c:run_store
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:__ksm_enter
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:replace_page
  - mm/ksm.c:replace_page
  - mm/ksm.c:write_protect_page
```
```
In mm/slub.c (c054fa1c)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:unfreeze_partials
  - mm/slub.c:unfreeze_partials
  - mm/slub.c:deactivate_slab
```
```
In mm/migrate.c (c0551a5c)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - mm/migrate.c:__buffer_migrate_page
  - mm/migrate.c:__buffer_migrate_page
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:__migration_entry_wait
```
```
In mm/memcontrol.c (c055d010)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_clear_mc
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
  - mm/memcontrol.c:mem_cgroup_css_reset
  - mm/memcontrol.c:mem_cgroup_css_offline
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_event_wake
  - mm/memcontrol.c:mem_cgroup_oom_unregister_event
  - mm/memcontrol.c:mem_cgroup_oom_register_event
  - mm/memcontrol.c:mem_cgroup_oom_notify
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_unmark_under_oom
  - mm/memcontrol.c:mem_cgroup_mark_under_oom
  - mm/memcontrol.c:mem_cgroup_oom_unlock
  - mm/memcontrol.c:mem_cgroup_oom_trylock
```
```
In mm/vmpressure.c (c055d70c)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - mm/vmpressure.c:vmpressure
  - mm/vmpressure.c:vmpressure
  - mm/vmpressure.c:vmpressure
  - mm/vmpressure.c:vmpressure_work_fn
  - mm/vmpressure.c:vmpressure_work_fn
```
```
In mm/zpool.c (c055f4b8)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - mm/zpool.c:zpool_destroy_pool
  - mm/zpool.c:zpool_create_pool
  - mm/zpool.c:zpool_get_driver
  - mm/zpool.c:zpool_get_driver
  - mm/zpool.c:zpool_unregister_driver
  - mm/zpool.c:zpool_register_driver
```
```
In mm/zbud.c (c055fcb4)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - mm/zbud.c:zbud_reclaim_page
  - mm/zbud.c:zbud_reclaim_page
  - mm/zbud.c:zbud_reclaim_page
  - mm/zbud.c:zbud_reclaim_page
  - mm/zbud.c:zbud_free
  - mm/zbud.c:zbud_alloc
  - mm/zbud.c:zbud_alloc
```
```
In mm/zsmalloc.c (c05619d0)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:async_free_zspage
  - mm/zsmalloc.c:async_free_zspage
  - mm/zsmalloc.c:zs_page_putback
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_isolate
  - mm/zsmalloc.c:zs_page_isolate
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:zs_unmap_object
```
```
In mm/userfaultfd.c (c0564124)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/page_idle.c (c0564700)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/memfd.c (c0566c74)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/read_write.c (c056a0e8)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
```
```
In fs/super.c (c0570ef4)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - fs/super.c:user_get_super
  - fs/super.c:user_get_super
  - fs/super.c:get_active_super
  - fs/super.c:iterate_supers_type
  - fs/super.c:iterate_supers_type
  - fs/super.c:iterate_supers
  - fs/super.c:iterate_supers
  - fs/super.c:__iterate_supers
  - fs/super.c:__iterate_supers
  - fs/super.c:sget
  - fs/super.c:sget
  - fs/super.c:sget
  - fs/super.c:sget
  - fs/super.c:sget_fc
  - fs/super.c:sget_fc
  - fs/super.c:sget_fc
  - fs/super.c:sget_fc
  - fs/super.c:generic_shutdown_super
  - fs/super.c:grab_super
  - fs/super.c:put_super
```
```
In fs/char_dev.c (c05715fc)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - fs/char_dev.c:cdev_purge
  - fs/char_dev.c:cd_forget
  - fs/char_dev.c:chrdev_open
  - fs/char_dev.c:chrdev_open
```
```
In fs/stat.c (c0572554)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - fs/stat.c:inode_get_bytes
  - fs/stat.c:inode_sub_bytes
  - fs/stat.c:inode_add_bytes
```
```
In fs/exec.c (c0575800)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - fs/exec.c:__do_execve_file
  - fs/exec.c:__do_execve_file
  - fs/exec.c:finalize_exec
  - fs/exec.c:__set_task_comm
  - fs/exec.c:__get_task_comm
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
  - fs/exec.c:__se_sys_uselib
  - fs/exec.c:__se_sys_uselib
  - fs/exec.c:unregister_binfmt
  - fs/exec.c:__register_binfmt
```
```
In fs/pipe.c (c05778e4)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - fs/pipe.c:fifo_open
  - fs/pipe.c:fifo_open
  - fs/pipe.c:fifo_open
  - fs/pipe.c:put_pipe_info
```
```
In fs/namei.c (c058140c)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - fs/namei.c:vfs_readlink
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_unlink
  - fs/namei.c:vfs_tmpfile
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:path_init
  - fs/namei.c:__lookup_slow
  - fs/namei.c:set_root
  - fs/namei.c:inode_permission
```
```
In fs/fcntl.c (c0582b7c)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - fs/fcntl.c:fasync_insert_entry
  - fs/fcntl.c:fasync_insert_entry
  - fs/fcntl.c:fasync_insert_entry
  - fs/fcntl.c:fasync_remove_entry
  - fs/fcntl.c:fasync_remove_entry
  - fs/fcntl.c:fasync_remove_entry
  - fs/fcntl.c:send_sigurg
  - fs/fcntl.c:send_sigurg
  - fs/fcntl.c:send_sigio
  - fs/fcntl.c:send_sigio
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:f_getown
  - fs/fcntl.c:f_modown
  - fs/fcntl.c:setfl
```
```
In fs/ioctl.c (c0583aa4)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - fs/ioctl.c:do_vfs_ioctl
```
```
In fs/dcache.c (c058864c)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - fs/dcache.c:d_tmpfile
  - fs/dcache.c:d_tmpfile
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_exchange
  - fs/dcache.c:d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:d_exact_alias
  - fs/dcache.c:d_exact_alias
  - fs/dcache.c:d_exact_alias
  - fs/dcache.c:d_exact_alias
  - fs/dcache.c:d_add
  - fs/dcache.c:d_add
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_rehash
  - fs/dcache.c:d_delete
  - fs/dcache.c:d_delete
  - fs/dcache.c:__d_lookup
  - fs/dcache.c:__d_lookup
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:d_instantiate_new
  - fs/dcache.c:__d_instantiate
  - fs/dcache.c:d_set_fallthru
  - fs/dcache.c:d_alloc
  - fs/dcache.c:shrink_dcache_parent
  - fs/dcache.c:d_set_mounted
  - fs/dcache.c:d_set_mounted
  - fs/dcache.c:d_set_mounted
  - fs/dcache.c:d_set_mounted
  - fs/dcache.c:path_has_submounts
  - fs/dcache.c:d_walk
  - fs/dcache.c:d_walk
  - fs/dcache.c:d_walk
  - fs/dcache.c:d_walk
  - fs/dcache.c:d_walk
  - fs/dcache.c:d_walk
  - fs/dcache.c:d_walk
  - fs/dcache.c:dentry_lru_isolate_shrink
  - fs/dcache.c:dentry_lru_isolate
  - fs/dcache.c:dentry_lru_isolate
  - fs/dcache.c:dentry_lru_isolate
  - fs/dcache.c:shrink_dentry_list
  - fs/dcache.c:d_prune_aliases
  - fs/dcache.c:d_prune_aliases
  - fs/dcache.c:d_prune_aliases
  - fs/dcache.c:d_find_any_alias
  - fs/dcache.c:dput_to_list
  - fs/dcache.c:dput_to_list
  - fs/dcache.c:dput
  - fs/dcache.c:dput
  - fs/dcache.c:dput
  - fs/dcache.c:dput
  - fs/dcache.c:dput
  - fs/dcache.c:dput
  - fs/dcache.c:__lock_parent
  - fs/dcache.c:__lock_parent
  - fs/dcache.c:__dentry_kill
  - fs/dcache.c:__dentry_kill
  - fs/dcache.c:__dentry_kill
  - fs/dcache.c:d_drop
  - fs/dcache.c:dentry_unlink_inode
  - fs/dcache.c:dentry_unlink_inode
  - fs/dcache.c:take_dentry_name_snapshot
```
```
In fs/inode.c (c058ccc4)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - fs/inode.c:__wait_on_freeing_inode
  - fs/inode.c:__wait_on_freeing_inode
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:find_inode_nowait
  - fs/inode.c:ilookup
  - fs/inode.c:ilookup5_nowait
  - fs/inode.c:iunique
  - fs/inode.c:iunique
  - fs/inode.c:iunique
  - fs/inode.c:iget_locked
  - fs/inode.c:iget_locked
  - fs/inode.c:iget_locked
  - fs/inode.c:iget_locked
  - fs/inode.c:inode_insert5
  - fs/inode.c:inode_insert5
  - fs/inode.c:inode_insert5
  - fs/inode.c:discard_new_inode
  - fs/inode.c:unlock_new_inode
  - fs/inode.c:new_inode_pseudo
  - fs/inode.c:find_inode_fast
  - fs/inode.c:find_inode_fast
  - fs/inode.c:find_inode
  - fs/inode.c:find_inode
  - fs/inode.c:inode_lru_isolate
  - fs/inode.c:inode_lru_isolate
  - fs/inode.c:inode_lru_isolate
  - fs/inode.c:inode_lru_isolate
  - fs/inode.c:inode_lru_isolate
  - fs/inode.c:invalidate_inodes
  - fs/inode.c:invalidate_inodes
  - fs/inode.c:invalidate_inodes
  - fs/inode.c:invalidate_inodes
  - fs/inode.c:invalidate_inodes
  - fs/inode.c:evict_inodes
  - fs/inode.c:evict_inodes
  - fs/inode.c:evict_inodes
  - fs/inode.c:evict_inodes
  - fs/inode.c:evict
  - fs/inode.c:evict
  - fs/inode.c:clear_inode
  - fs/inode.c:__remove_inode_hash
  - fs/inode.c:__remove_inode_hash
  - fs/inode.c:__insert_inode_hash
  - fs/inode.c:__insert_inode_hash
  - fs/inode.c:inode_sb_list_add
```
```
In fs/file.c (c0590c78)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - fs/file.c:ksys_dup3
  - fs/file.c:replace_fd
  - fs/file.c:do_dup2
  - fs/file.c:do_dup2
  - fs/file.c:set_close_on_exec
  - fs/file.c:do_close_on_exec
  - fs/file.c:do_close_on_exec
  - fs/file.c:__close_fd_get_file
  - fs/file.c:__close_fd_get_file
  - fs/file.c:__close_fd
  - fs/file.c:__close_fd
  - fs/file.c:put_unused_fd
  - fs/file.c:__alloc_fd
  - fs/file.c:exit_files
  - fs/file.c:reset_files_struct
  - fs/file.c:get_files_struct
  - fs/file.c:dup_fd
  - fs/file.c:dup_fd
  - fs/file.c:expand_files
  - fs/file.c:expand_files
```
```
In fs/filesystems.c (c0591f9c)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - fs/filesystems.c:__get_fs_type
  - fs/filesystems.c:filesystems_proc_show
  - fs/filesystems.c:__se_sys_sysfs
  - fs/filesystems.c:__se_sys_sysfs
  - fs/filesystems.c:__se_sys_sysfs
  - fs/filesystems.c:register_filesystem
```
```
In fs/namespace.c (c0592918)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - fs/namespace.c:mntns_get
  - fs/namespace.c:current_chrooted
  - fs/namespace.c:__se_sys_pivot_root
  - fs/namespace.c:path_is_under
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:set_mount_attributes
  - fs/namespace.c:__se_sys_open_tree
  - fs/namespace.c:unlock_mount
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:drop_collected_mounts
  - fs/namespace.c:dissolve_on_fput
  - fs/namespace.c:copy_tree
  - fs/namespace.c:copy_tree
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:do_umount
  - fs/namespace.c:do_umount
  - fs/namespace.c:do_umount
  - fs/namespace.c:may_umount
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:vfs_create_mount
  - fs/namespace.c:get_mountpoint
  - fs/namespace.c:get_mountpoint
  - fs/namespace.c:sb_prepare_remount_readonly
```
```
In fs/xattr.c (c059c738)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - fs/xattr.c:simple_xattr_list_add
  - fs/xattr.c:simple_xattr_list
  - fs/xattr.c:simple_xattr_set
  - fs/xattr.c:simple_xattr_get
```
```
In fs/libfs.c (c059e540)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - fs/libfs.c:empty_dir_readdir
  - fs/libfs.c:simple_release_fs
  - fs/libfs.c:simple_pin_fs
  - fs/libfs.c:simple_pin_fs
  - fs/libfs.c:simple_empty
  - fs/libfs.c:simple_empty
  - fs/libfs.c:simple_empty
  - fs/libfs.c:dcache_readdir
  - fs/libfs.c:dcache_readdir
  - fs/libfs.c:dcache_dir_lseek
  - fs/libfs.c:scan_positives
  - fs/libfs.c:scan_positives
  - fs/libfs.c:scan_positives
```
```
In fs/fs-writeback.c (c05a6d48)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:block_dump___mark_inode_dirty
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_writeback
  - fs/fs-writeback.c:wb_writeback
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
  - fs/fs-writeback.c:writeback_single_inode
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/fs-writeback.c:inode_sleep_on_writeback
  - fs/fs-writeback.c:inode_wait_for_writeback
  - fs/fs-writeback.c:__inode_wait_for_writeback
  - fs/fs-writeback.c:inode_io_list_del
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
```
```
In fs/pnode.c (c05a817c)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - fs/pnode.c:propagate_mnt
```
```
In fs/d_path.c (c05aca30)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:prepend_path
  - fs/d_path.c:prepend_path
```
```
In fs/stack.c (c05ad128)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - fs/stack.c:fsstack_copy_inode_size
  - fs/stack.c:fsstack_copy_inode_size
```
```
In fs/fs_struct.c (c05ad7f4)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - fs/fs_struct.c:unshare_fs_struct
  - fs/fs_struct.c:unshare_fs_struct
  - fs/fs_struct.c:copy_fs_struct
  - fs/fs_struct.c:exit_fs
  - fs/fs_struct.c:exit_fs
  - fs/fs_struct.c:chroot_fs_refs
  - fs/fs_struct.c:chroot_fs_refs
  - fs/fs_struct.c:chroot_fs_refs
  - fs/fs_struct.c:set_fs_pwd
  - fs/fs_struct.c:set_fs_root
```
```
In fs/fs_pin.c (c05ae2f0)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - fs/fs_pin.c:pin_kill
  - fs/fs_pin.c:pin_kill
  - fs/fs_pin.c:pin_kill
  - fs/fs_pin.c:pin_insert
  - fs/fs_pin.c:pin_remove
  - fs/fs_pin.c:pin_remove
```
```
In fs/buffer.c (c05b3258)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - fs/buffer.c:try_to_free_buffers
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:__bforget
  - fs/buffer.c:__getblk_slow
  - fs/buffer.c:remove_inode_buffers
  - fs/buffer.c:invalidate_inode_buffers
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/buffer.c:mark_buffer_dirty_inode
```
```
In fs/block_dev.c (c05bae7c)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - fs/block_dev.c:iterate_bdevs
  - fs/block_dev.c:iterate_bdevs
  - fs/block_dev.c:iterate_bdevs
  - fs/block_dev.c:iterate_bdevs
  - fs/block_dev.c:blkdev_put
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:bd_abort_claiming
  - fs/block_dev.c:bd_finish_claiming
  - fs/block_dev.c:bd_start_claiming
  - fs/block_dev.c:bd_start_claiming
  - fs/block_dev.c:bd_start_claiming
  - fs/block_dev.c:bd_forget
  - fs/block_dev.c:bd_acquire
  - fs/block_dev.c:bd_acquire
  - fs/block_dev.c:nr_blockdev_pages
  - fs/block_dev.c:bdget
  - fs/block_dev.c:bdev_evict_inode
```
```
In fs/proc_namespace.c (c05bf5c8)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
  - fs/proc_namespace.c:mounts_open_common
  - fs/proc_namespace.c:mounts_open_common
  - fs/proc_namespace.c:mounts_open_common
```
```
In fs/notify/fsnotify.c (c05bfeac)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/notify/fsnotify.c:fsnotify_sb_delete
```
```
In fs/notify/notification.c (c05c04b4)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - fs/notify/notification.c:fsnotify_flush_notify
  - fs/notify/notification.c:fsnotify_flush_notify
  - fs/notify/notification.c:fsnotify_add_event
  - fs/notify/notification.c:fsnotify_add_event
  - fs/notify/notification.c:fsnotify_add_event
```
```
In fs/notify/group.c (c05c06e8)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_group_stop_queueing
```
```
In fs/notify/mark.c (c05c0a0c)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_mark_destroy_workfn
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_find_mark
  - fs/notify/mark.c:fsnotify_find_mark
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_add_mark_list
  - fs/notify/mark.c:fsnotify_add_mark_list
  - fs/notify/mark.c:fsnotify_add_mark_list
  - fs/notify/mark.c:fsnotify_grab_connector
  - fs/notify/mark.c:fsnotify_detach_mark
  - fs/notify/mark.c:fsnotify_detach_mark
  - fs/notify/mark.c:fsnotify_prepare_user_wait
  - fs/notify/mark.c:fsnotify_prepare_user_wait
  - fs/notify/mark.c:fsnotify_put_mark
  - fs/notify/mark.c:fsnotify_put_mark
  - fs/notify/mark.c:fsnotify_put_mark
  - fs/notify/mark.c:fsnotify_connector_destroy_workfn
```
```
In fs/notify/dnotify/dnotify.c (c05c257c)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:dnotify_flush
  - fs/notify/dnotify/dnotify.c:dnotify_handle_event
```
```
In fs/notify/inotify/inotify_user.c (c05c3ab4)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:__se_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:__se_sys_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:__se_sys_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:inotify_remove_from_idr
  - fs/notify/inotify/inotify_user.c:inotify_ioctl
  - fs/notify/inotify/inotify_user.c:inotify_ioctl
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/inotify/inotify_user.c:inotify_poll
```
```
In fs/notify/fanotify/fanotify.c (c05c4570)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
```
```
In fs/notify/fanotify/fanotify_user.c (c05c47d4)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_ioctl
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
  - fs/notify/fanotify/fanotify_user.c:fanotify_write
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_poll
```
```
In fs/eventpoll.c (c05c6574)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_wait
  - fs/eventpoll.c:do_epoll_wait
  - fs/eventpoll.c:do_epoll_wait
  - fs/eventpoll.c:__do_sys_epoll_ctl
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_remove
  - fs/eventpoll.c:ep_remove
```
```
In fs/signalfd.c (c05c8a54)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - fs/signalfd.c:do_signalfd4
  - fs/signalfd.c:signalfd_read
  - fs/signalfd.c:signalfd_read
  - fs/signalfd.c:signalfd_read
  - fs/signalfd.c:signalfd_poll
```
```
In fs/timerfd.c (c05c9adc)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:timerfd_ioctl
  - fs/timerfd.c:timerfd_show
  - fs/timerfd.c:timerfd_read
  - fs/timerfd.c:timerfd_release
```
```
In fs/eventfd.c (c05ca860)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_show_fdinfo
  - fs/eventfd.c:eventfd_write
  - fs/eventfd.c:eventfd_write
  - fs/eventfd.c:eventfd_read
  - fs/eventfd.c:eventfd_read
```
```
In fs/userfaultfd.c (c05cb0e8)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_show_fdinfo
  - fs/userfaultfd.c:__wake_userfault
  - fs/userfaultfd.c:userfaultfd_ctx_read
  - fs/userfaultfd.c:userfaultfd_ctx_read
  - fs/userfaultfd.c:userfaultfd_ctx_read
  - fs/userfaultfd.c:userfaultfd_ctx_read
  - fs/userfaultfd.c:userfaultfd_ctx_read
  - fs/userfaultfd.c:userfaultfd_ctx_read
  - fs/userfaultfd.c:userfaultfd_ctx_read
  - fs/userfaultfd.c:userfaultfd_release
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/aio.c (c05d1798)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - fs/aio.c:__se_sys_io_cancel
  - fs/aio.c:__se_sys_io_submit
  - fs/aio.c:aio_poll_cancel
  - fs/aio.c:aio_poll_complete_work
  - fs/aio.c:aio_poll_complete_work
  - fs/aio.c:__se_sys_io_setup
  - fs/aio.c:__se_sys_io_setup
  - fs/aio.c:__se_sys_io_setup
  - fs/aio.c:__se_sys_io_setup
  - fs/aio.c:kill_ioctx
  - fs/aio.c:kill_ioctx
  - fs/aio.c:aio_nr_sub
  - fs/aio.c:free_ioctx_users
  - fs/aio.c:aio_migratepage
  - fs/aio.c:aio_ring_mremap
  - fs/aio.c:put_aio_ring_file
```
```
In fs/io_uring.c (c05d6100)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - fs/io_uring.c:io_submit_sqe
  - fs/io_uring.c:io_queue_link_head
  - fs/io_uring.c:__io_queue_sqe
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/io_uring.c:__io_submit_sqe
  - fs/io_uring.c:__io_submit_sqe
  - fs/io_uring.c:__io_submit_sqe
  - fs/io_uring.c:__io_submit_sqe
  - fs/io_uring.c:io_req_defer
  - fs/io_uring.c:io_req_defer
  - fs/io_uring.c:io_poll_complete_work
  - fs/io_uring.c:io_poll_complete_work
  - fs/io_uring.c:io_poll_remove_one
  - fs/io_uring.c:io_send_recvmsg
```
```
In fs/crypto/hooks.c (c05d9814)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
```
```
In fs/crypto/keyring.c (c05da9b8)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:do_remove_key
```
```
In fs/crypto/keysetup.c (c05dbd10)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
  - fs/crypto/keysetup.c:put_crypt_info
```
```
In fs/crypto/keysetup_v1.c (c05dc0f4)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:find_or_insert_direct_key
  - fs/crypto/keysetup_v1.c:find_or_insert_direct_key
  - fs/crypto/keysetup_v1.c:fscrypt_put_direct_key
```
```
In fs/locks.c (c05e1c7c)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - fs/locks.c:locks_stop
  - fs/locks.c:show_fd_locks
  - fs/locks.c:locks_remove_file
  - fs/locks.c:locks_remove_file
  - fs/locks.c:fcntl_setlk64
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_getlease
  - fs/locks.c:lease_get_mtime
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:locks_mandatory_locked
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
  - fs/locks.c:posix_test_lock
  - fs/locks.c:locks_unlink_lock_ctx
  - fs/locks.c:locks_insert_block
  - fs/locks.c:locks_delete_block
  - fs/locks.c:locks_insert_global_locks
```
```
In fs/mbcache.c (c05ede3c)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/coredump.c (c05f1660)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
```
```
In fs/drop_caches.c (c05f1bc8)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - fs/drop_caches.c:drop_pagecache_sb
  - fs/drop_caches.c:drop_pagecache_sb
  - fs/drop_caches.c:drop_pagecache_sb
  - fs/drop_caches.c:drop_pagecache_sb
```
```
In fs/fhandle.c (c05f23e4)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - fs/fhandle.c:__se_sys_open_by_handle_at
```
```
In fs/quota/dquot.c (c05f7a94)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_set_dqinfo
  - fs/quota/dquot.c:dquot_get_state
  - fs/quota/dquot.c:dquot_set_dqblk
  - fs/quota/dquot.c:do_get_dqblk
  - fs/quota/dquot.c:dquot_enable
  - fs/quota/dquot.c:dquot_resume
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:dquot_free_inode
  - fs/quota/dquot.c:dquot_free_inode
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:dquot_alloc_inode
  - fs/quota/dquot.c:dquot_alloc_inode
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:__dquot_drop
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_inodes
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqcache_shrink_scan
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_scan_active
  - fs/quota/dquot.c:dquot_scan_active
  - fs/quota/dquot.c:dquot_commit
  - fs/quota/dquot.c:dquot_commit
  - fs/quota/dquot.c:mark_info_dirty
  - fs/quota/dquot.c:unregister_quota_format
  - fs/quota/dquot.c:register_quota_format
```
```
In fs/proc/task_mmu.c (c0601418)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
```
In fs/proc/inode.c (c0601ca8)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_reg_release
  - fs/proc/inode.c:proc_reg_open
  - fs/proc/inode.c:proc_entry_rundown
```
```
In fs/proc/base.c (c06078c4)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_pident_readdir
  - fs/proc/base.c:timerslack_ns_show
  - fs/proc/base.c:timerslack_ns_write
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_fill_cache
  - fs/proc/base.c:task_dump_owner
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:environ_read
  - fs/proc/base.c:proc_root_link
  - fs/proc/base.c:proc_root_link
  - fs/proc/base.c:proc_cwd_link
  - fs/proc/base.c:proc_cwd_link
```
```
In fs/proc/generic.c (c060963c)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_entry
  - fs/proc/generic.c:remove_proc_entry
  - fs/proc/generic.c:__proc_create
  - fs/proc/generic.c:proc_register
  - fs/proc/generic.c:proc_register
```
```
In fs/proc/array.c (c060a030)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - fs/proc/array.c:get_children_pid
  - fs/proc/array.c:task_state
```
```
In fs/proc/fd.c (c060bc18)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_readfd_common
  - fs/proc/fd.c:proc_fd_link
  - fs/proc/fd.c:seq_show
```
```
In fs/proc/namespaces.c (c060e1d4)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_readdir
```
```
In fs/proc/proc_sysctl.c (c060fbe4)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:unregister_sysctl_table
  - fs/proc/proc_sysctl.c:drop_sysctl_table
  - fs/proc/proc_sysctl.c:drop_sysctl_table
  - fs/proc/proc_sysctl.c:drop_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_table
  - fs/proc/proc_sysctl.c:sysctl_follow_link
  - fs/proc/proc_sysctl.c:proc_sys_compare
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_fill_cache
  - fs/proc/proc_sysctl.c:proc_sys_fill_cache
  - fs/proc/proc_sysctl.c:proc_sys_lookup
  - fs/proc/proc_sysctl.c:proc_sys_evict_inode
  - fs/proc/proc_sysctl.c:proc_sys_make_inode
  - fs/proc/proc_sysctl.c:proc_sys_make_inode
  - fs/proc/proc_sysctl.c:insert_header
```
```
In fs/proc/proc_net.c (c0611644)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - fs/proc/proc_net.c:get_proc_task_net
```
```
In fs/kernfs/dir.c (c0615200)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:kernfs_walk_and_get_ns
  - fs/kernfs/dir.c:kernfs_walk_and_get_ns
  - fs/kernfs/dir.c:__kernfs_new_node
```
```
In fs/kernfs/file.c (c0616e38)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_drain_open_files
  - fs/kernfs/file.c:kernfs_fop_open
```
```
In fs/sysfs/dir.c (c06192d4)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - fs/sysfs/dir.c:sysfs_remove_dir
```
```
In fs/sysfs/symlink.c (c06196b0)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - fs/sysfs/symlink.c:sysfs_delete_link
  - fs/sysfs/symlink.c:sysfs_do_create_link_sd
```
```
In fs/sysfs/group.c (c061a03c)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
```
```
In fs/configfs/inode.c (c061aa14)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_hash_and_remove
  - fs/configfs/inode.c:configfs_drop_dentry
  - fs/configfs/inode.c:configfs_drop_dentry
```
```
In fs/configfs/dir.c (c061c938)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
  - fs/configfs/dir.c:configfs_unregister_group
  - fs/configfs/dir.c:configfs_register_group
  - fs/configfs/dir.c:configfs_dir_lseek
  - fs/configfs/dir.c:configfs_readdir
  - fs/configfs/dir.c:configfs_readdir
  - fs/configfs/dir.c:configfs_readdir
  - fs/configfs/dir.c:configfs_dir_close
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_do_depend_item
  - fs/configfs/dir.c:detach_groups
  - fs/configfs/dir.c:detach_attrs
  - fs/configfs/dir.c:configfs_dirent_is_ready
  - fs/configfs/dir.c:configfs_remove_dirent
  - fs/configfs/dir.c:configfs_new_dirent
  - fs/configfs/dir.c:configfs_new_dirent
  - fs/configfs/dir.c:configfs_d_iput
```
```
In fs/configfs/symlink.c (c061e4c4)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - fs/configfs/symlink.c:configfs_unlink
  - fs/configfs/symlink.c:configfs_unlink
  - fs/configfs/symlink.c:configfs_unlink
  - fs/configfs/symlink.c:configfs_symlink
  - fs/configfs/symlink.c:configfs_symlink
  - fs/configfs/symlink.c:create_link
  - fs/configfs/symlink.c:create_link
  - fs/configfs/symlink.c:create_link
```
```
In fs/dcookies.c (c061fc48)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - fs/dcookies.c:dcookie_unregister
  - fs/dcookies.c:get_dcookie
```
```
In fs/ext4/balloc.c (c0621508)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (c0625254)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_rereserve_cluster
```
```
In fs/ext4/extents_status.c (c06319b4)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_delayed_clu
  - fs/ext4/extents_status.c:ext4_es_insert_delayed_block
  - fs/ext4/extents_status.c:ext4_is_pending
  - fs/ext4/extents_status.c:ext4_remove_pending
  - fs/ext4/extents_status.c:ext4_clear_inode_es
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:__es_shrink
  - fs/ext4/extents_status.c:__es_shrink
  - fs/ext4/extents_status.c:__es_shrink
  - fs/ext4/extents_status.c:__es_shrink
  - fs/ext4/extents_status.c:ext4_es_remove_extent
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:ext4_es_cache_extent
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:ext4_es_free_extent
  - fs/ext4/extents_status.c:ext4_es_scan_clu
  - fs/ext4/extents_status.c:ext4_es_scan_range
  - fs/ext4/extents_status.c:ext4_es_find_extent_range
```
```
In fs/ext4/ialloc.c (c0637f64)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inode.c (c064b4e0)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:ext4_da_release_space
  - fs/ext4/inode.c:ext4_da_reserve_space
  - fs/ext4/inode.c:ext4_da_reserve_space
  - fs/ext4/inode.c:ext4_da_update_reserve_space
```
```
In fs/ext4/mballoc.c (c06595bc)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_generate_from_pa
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_try_best_found
  - fs/ext4/mballoc.c:ext4_mb_use_best_found
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In fs/ext4/migrate.c (c065a3c0)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/super.c (c0675b9c)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_sync_fs
  - fs/ext4/super.c:ext4_init_journal_params
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:ext4_journal_commit_callback
  - fs/ext4/super.c:ext4_journal_commit_callback
```
```
In fs/jbd2/transaction.c (c069050c)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_begin_ordered_truncate
  - fs/jbd2/transaction.c:jbd2_journal_begin_ordered_truncate
  - fs/jbd2/transaction.c:jbd2_journal_file_inode
  - fs/jbd2/transaction.c:jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:journal_unmap_buffer
  - fs/jbd2/transaction.c:journal_unmap_buffer
  - fs/jbd2/transaction.c:journal_unmap_buffer
  - fs/jbd2/transaction.c:journal_unmap_buffer
  - fs/jbd2/transaction.c:journal_unmap_buffer
  - fs/jbd2/transaction.c:journal_unmap_buffer
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_unfile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:jbd2_journal_unlock_updates
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:jbd2__journal_restart
  - fs/jbd2/transaction.c:jbd2__journal_restart
  - fs/jbd2/transaction.c:jbd2_journal_extend
  - fs/jbd2/transaction.c:jbd2_journal_extend
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:wait_transaction_locked
```
```
In fs/jbd2/commit.c (c0690ce8)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_data_buffers
  - fs/jbd2/commit.c:journal_submit_data_buffers
```
```
In fs/jbd2/checkpoint.c (c0694638)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:jbd2_journal_destroy_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_journal_destroy_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
```
```
In fs/jbd2/revoke.c (c0694d08)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
  - fs/jbd2/revoke.c:insert_revoke_hash
```
```
In fs/jbd2/journal.c (c0695388)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_ack_err
  - fs/jbd2/journal.c:jbd2_journal_clear_err
  - fs/jbd2/journal.c:jbd2_journal_errno
  - fs/jbd2/journal.c:__journal_abort_soft
  - fs/jbd2/journal.c:__journal_abort_soft
  - fs/jbd2/journal.c:__journal_abort_soft
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_mark_journal_empty
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
  - fs/jbd2/journal.c:jbd2_seq_info_open
  - fs/jbd2/journal.c:jbd2_journal_get_log_tail
  - fs/jbd2/journal.c:jbd2_journal_get_log_tail
  - fs/jbd2/journal.c:jbd2_complete_transaction
  - fs/jbd2/journal.c:jbd2_complete_transaction
  - fs/jbd2/journal.c:jbd2_transaction_committed
  - fs/jbd2/journal.c:jbd2_log_wait_commit
  - fs/jbd2/journal.c:jbd2_log_wait_commit
  - fs/jbd2/journal.c:jbd2_journal_start_commit
  - fs/jbd2/journal.c:__jbd2_journal_force_commit
  - fs/jbd2/journal.c:__jbd2_journal_force_commit
  - fs/jbd2/journal.c:jbd2_log_start_commit
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:kjournald2
  - fs/jbd2/journal.c:kjournald2
  - fs/jbd2/journal.c:kjournald2
  - fs/jbd2/journal.c:kjournald2
```
```
In fs/squashfs/cache.c (c069bcbc)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - fs/squashfs/cache.c:squashfs_cache_put
  - fs/squashfs/cache.c:squashfs_cache_put
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/squashfs/cache.c:squashfs_cache_get
```
```
In fs/fat/cache.c (c06a245c)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - fs/fat/cache.c:fat_get_cluster
  - fs/fat/cache.c:fat_cache_inval_inode
```
```
In fs/fat/dir.c (c06a5a24)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/dir.c:__fat_readdir
```
```
In fs/fat/fatent.c (c06a6768)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat12_ent_put
  - fs/fat/fatent.c:fat12_ent_get
```
```
In fs/fat/file.c (c06a8534)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - fs/fat/file.c:fat_getattr
```
```
In fs/fat/inode.c (c06a9a8c)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:fat_iget
  - fs/fat/inode.c:fat_detach
  - fs/fat/inode.c:fat_detach
  - fs/fat/inode.c:fat_attach
  - fs/fat/inode.c:fat_attach
```
```
In fs/fat/nfs.c (c06ad650)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - fs/fat/nfs.c:fat_encode_fh_nostale
  - fs/fat/nfs.c:fat_encode_fh_nostale
  - fs/fat/nfs.c:fat_dget
```
```
In fs/fat/namei_vfat.c (c06ad754)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_revalidate_shortname
```
```
In fs/exportfs/expfs.c (c06bbd70)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
```
```
In fs/nls/nls_base.c (c06bc71c)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - fs/nls/nls_base.c:find_nls
```
```
In fs/fuse/dev.c (c06bf3e4)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_release
  - fs/fuse/dev.c:fuse_dev_poll
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_retrieve
  - fs/fuse/dev.c:fuse_dev_do_read
  - fs/fuse/dev.c:fuse_dev_do_read
  - fs/fuse/dev.c:fuse_dev_do_read
  - fs/fuse/dev.c:fuse_dev_do_read
  - fs/fuse/dev.c:fuse_dev_do_read
  - fs/fuse/dev.c:fuse_dev_do_read
  - fs/fuse/dev.c:fuse_dev_do_read
  - fs/fuse/dev.c:fuse_dev_do_read
  - fs/fuse/dev.c:fuse_dev_do_read
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:queue_interrupt
  - fs/fuse/dev.c:queue_interrupt
  - fs/fuse/dev.c:fuse_request_end
  - fs/fuse/dev.c:fuse_request_end
  - fs/fuse/dev.c:fuse_queue_forget
  - fs/fuse/dev.c:fuse_dev_wake_and_unlock
```
```
In fs/fuse/dir.c (c06c55fc)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_release_nowrite
  - fs/fuse/dir.c:fuse_set_nowrite
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_settime
```
```
In fs/fuse/file.c (c06cbd74)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_notify_poll_wakeup
  - fs/fuse/file.c:fuse_file_poll
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_send
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_end
  - fs/fuse/file.c:fuse_send_writepage
  - fs/fuse/file.c:fuse_send_writepage
  - fs/fuse/file.c:fuse_write_update_size
  - fs/fuse/file.c:fuse_async_req_send
  - fs/fuse/file.c:fuse_aio_complete
  - fs/fuse/file.c:fuse_aio_complete
  - fs/fuse/file.c:fuse_range_is_writeback
  - fs/fuse/file.c:fuse_prepare_release
  - fs/fuse/file.c:fuse_prepare_release
  - fs/fuse/file.c:fuse_finish_open
  - fs/fuse/file.c:fuse_link_write_file
```
```
In fs/fuse/inode.c (c06cd2f8)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_dev_free
  - fs/fuse/inode.c:fuse_dev_install
  - fs/fuse/inode.c:process_init_reply
  - fs/fuse/inode.c:fuse_iget
  - fs/fuse/inode.c:fuse_change_attributes
  - fs/fuse/inode.c:fuse_change_attributes
```
```
In fs/fuse/control.c (c06ce754)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - fs/fuse/control.c:fuse_conn_congestion_threshold_write
  - fs/fuse/control.c:fuse_conn_max_background_write
```
```
In fs/fuse/readdir.c (c06d0054)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - fs/fuse/readdir.c:parse_dirplusfile
  - fs/fuse/readdir.c:parse_dirplusfile
  - fs/fuse/readdir.c:fuse_emit
  - fs/fuse/readdir.c:fuse_emit
  - fs/fuse/readdir.c:fuse_emit
```
```
In fs/debugfs/inode.c (c06d116c)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
```
```
In fs/tracefs/inode.c (c06d4250)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - fs/tracefs/inode.c:tracefs_remove_recursive
  - fs/tracefs/inode.c:tracefs_remove_recursive
  - fs/tracefs/inode.c:tracefs_remove_recursive
```
```
In fs/pstore/platform.c (c06d51ec)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_register
  - fs/pstore/platform.c:pstore_register
```
```
In ipc/util.c (c06d8f94)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - ipc/util.c:sysvipc_proc_stop
  - ipc/util.c:sysvipc_proc_next
  - ipc/util.c:ipcget
  - ipc/util.c:ipc_addid
```
```
In ipc/msg.c (c06dba64)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:ksys_msgctl
  - ipc/msg.c:ksys_msgctl
  - ipc/msg.c:msgctl_down
  - ipc/msg.c:msgctl_down
  - ipc/msg.c:freeque
  - ipc/msg.c:newque
```
```
In ipc/sem.c (c06dfd4c)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:exit_sem
  - ipc/sem.c:exit_sem
  - ipc/sem.c:exit_sem
  - ipc/sem.c:exit_sem
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:ksys_semctl
  - ipc/sem.c:ksys_semctl
  - ipc/sem.c:ksys_semctl
  - ipc/sem.c:ksys_semctl
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:freeary
  - ipc/sem.c:freeary
  - ipc/sem.c:newary
```
```
In ipc/shm.c (c06e1b80)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:do_shmat
  - ipc/shm.c:do_shmat
  - ipc/shm.c:do_shmat
  - ipc/shm.c:ksys_shmctl
  - ipc/shm.c:ksys_shmctl
  - ipc/shm.c:ksys_shmctl
  - ipc/shm.c:ksys_shmctl
  - ipc/shm.c:ksys_shmctl
  - ipc/shm.c:shm_add_rss_swap
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_close
  - ipc/shm.c:shm_close
  - ipc/shm.c:shm_destroy
  - ipc/shm.c:__shm_open
  - ipc/shm.c:__shm_open
  - ipc/shm.c:__shm_open
```
```
In ipc/mqueue.c (c06e4f74)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - ipc/mqueue.c:__se_sys_mq_getsetattr
  - ipc/mqueue.c:__se_sys_mq_getsetattr
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
  - ipc/mqueue.c:mqueue_poll_file
  - ipc/mqueue.c:mqueue_flush_file
  - ipc/mqueue.c:mqueue_read_file
  - ipc/mqueue.c:mqueue_create_attr
  - ipc/mqueue.c:mqueue_create_attr
  - ipc/mqueue.c:mqueue_evict_inode
  - ipc/mqueue.c:mqueue_evict_inode
  - ipc/mqueue.c:mqueue_evict_inode
  - ipc/mqueue.c:mqueue_get_inode
  - ipc/mqueue.c:mqueue_get_inode
```
```
In ipc/namespace.c (c06e53a8)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - ipc/namespace.c:ipcns_get
```
```
In security/keys/gc.c (c06e5d1c)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
  - security/keys/gc.c:key_garbage_collector
  - security/keys/gc.c:key_garbage_collector
  - security/keys/gc.c:key_garbage_collector
  - security/keys/gc.c:key_garbage_collector
```
```
In security/keys/key.c (c06e72a8)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - security/keys/key.c:key_lookup
  - security/keys/key.c:key_payload_reserve
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_user_lookup
  - security/keys/key.c:key_user_lookup
  - security/keys/key.c:key_user_lookup
```
```
In security/keys/keyring.c (c06e8e40)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
  - security/keys/keyring.c:keyring_destroy
  - security/keys/keyring.c:keyring_instantiate
  - security/keys/keyring.c:key_free_user_ns
```
```
In security/keys/keyctl.c (c06eb378)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
```
```
In security/keys/proc.c (c06ee11c)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - security/keys/proc.c:proc_key_users_stop
  - security/keys/proc.c:proc_keys_stop
```
```
In security/selinux/hooks.c (c06fe20c)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_invalidate_secctx
  - security/selinux/hooks.c:selinux_task_to_inode
  - security/selinux/hooks.c:selinux_inode_setsecurity
  - security/selinux/hooks.c:selinux_inode_post_setxattr
  - security/selinux/hooks.c:selinux_inode_free_security
  - security/selinux/hooks.c:selinux_bprm_committed_creds
  - security/selinux/hooks.c:selinux_bprm_committed_creds
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:sb_finish_set_opts
  - security/selinux/hooks.c:sb_finish_set_opts
```
```
In security/selinux/ss/services.c (c071cb7c)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_read_policy
  - security/selinux/ss/services.c:security_read_policy
  - security/selinux/ss/services.c:security_netlbl_sid_to_secattr
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_init
  - security/selinux/ss/services.c:security_policycap_supported
  - security/selinux/ss/services.c:security_get_permissions
  - security/selinux/ss/services.c:security_get_permissions
  - security/selinux/ss/services.c:security_get_classes
  - security/selinux/ss/services.c:security_net_peersid_resolve
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_get_bool_value
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_fs_use
  - security/selinux/ss/services.c:security_genfs_sid
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_node_sid
  - security/selinux/ss/services.c:security_netif_sid
  - security/selinux/ss/services.c:security_ib_endport_sid
  - security/selinux/ss/services.c:security_ib_pkey_sid
  - security/selinux/ss/services.c:security_port_sid
  - security/selinux/ss/services.c:security_load_policy
  - security/selinux/ss/services.c:security_context_to_sid_core
  - security/selinux/ss/services.c:security_sid_to_context_core
  - security/selinux/ss/services.c:security_compute_av_user
  - security/selinux/ss/services.c:security_compute_av
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_bounded_transition
```
```
In security/smack/smack_lsm.c (c07214e0)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_netlabel
```
```
In security/tomoyo/audit.c (c072b820)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - security/tomoyo/audit.c:tomoyo_read_log
  - security/tomoyo/audit.c:tomoyo_write_log2
```
```
In security/tomoyo/common.c (c072fd94)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_write_answer
  - security/tomoyo/common.c:tomoyo_write_answer
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_write_profile
```
```
In security/tomoyo/gc.c (c0735540)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - security/tomoyo/gc.c:tomoyo_notify_gc
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - security/tomoyo/gc.c:tomoyo_try_to_gc
```
```
In security/apparmor/apparmorfs.c (c073de24)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:multi_transaction_read
```
```
In security/apparmor/path.c (c0742188)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
```
```
In security/apparmor/secid.c (c074fc44)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - security/apparmor/secid.c:aa_alloc_secid
```
```
In security/apparmor/file.c (c07510fc)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_inherit_files
  - security/apparmor/file.c:update_file_ctx
```
```
In security/apparmor/af_unix.c (c0759638)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_file_perm
  - security/apparmor/af_unix.c:aa_unix_file_perm
  - security/apparmor/af_unix.c:aa_unix_file_perm
```
```
In security/yama/yama_lsm.c (c075a064)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_ptracer_add
  - security/yama/yama_lsm.c:yama_relation_cleanup
```
```
In security/integrity/iint.c (c075c2c4)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - security/integrity/iint.c:integrity_inode_free
  - security/integrity/iint.c:integrity_inode_get
  - security/integrity/iint.c:integrity_iint_find
```
```
In security/integrity/ima/ima_template.c (c0762774)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
```
```
In crypto/scompress.c (c0771d84)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - crypto/scompress.c:scomp_acomp_comp_decomp
```
```
In crypto/jitterentropy-kcapi.c (c0781924)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - crypto/jitterentropy-kcapi.c:jent_kcapi_random
  - crypto/jitterentropy-kcapi.c:jent_kcapi_cleanup
```
```
In block/bio.c (c0789470)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - block/bio.c:bio_dirty_fn
  - block/bio.c:punt_bios_to_rescuer
  - block/bio.c:bio_alloc_rescue
```
```
In block/elevator.c (c078c2c0)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - block/elevator.c:elv_iosched_show
  - block/elevator.c:elevator_init_mq
  - block/elevator.c:elv_register
  - block/elevator.c:elv_register
  - block/elevator.c:elevator_get
  - block/elevator.c:elevator_get
```
```
In block/blk-sysfs.c (c0793434)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_max_sectors_store
```
```
In block/blk-flush.c (c0793f44)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - block/blk-flush.c:blk_insert_flush
```
```
In block/blk-ioc.c (c0795718)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_create_icq
  - block/blk-ioc.c:ioc_create_icq
  - block/blk-ioc.c:get_task_io_context
  - block/blk-ioc.c:get_task_io_context
  - block/blk-ioc.c:create_task_io_context
  - block/blk-ioc.c:ioc_clear_queue
  - block/blk-ioc.c:exit_io_context
  - block/blk-ioc.c:ioc_release_fn
```
```
In block/blk-mq.c (c079e014)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_exit_hctx
  - block/blk-mq.c:blk_mq_hctx_notify_dead
  - block/blk-mq.c:blk_mq_hctx_notify_dead
  - block/blk-mq.c:blk_mq_insert_requests
  - block/blk-mq.c:blk_mq_request_bypass_insert
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_wake
  - block/blk-mq.c:dispatch_rq_from_ctx
  - block/blk-mq.c:flush_busy_ctx
  - block/blk-mq.c:blk_mq_requeue_work
```
```
In block/blk-stat.c (c07a08ec)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - block/blk-stat.c:blk_stat_enable_accounting
  - block/blk-stat.c:blk_stat_remove_callback
  - block/blk-stat.c:blk_stat_add_callback
```
```
In block/blk-mq-sched.c (c07a27a8)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_request
  - block/blk-mq-sched.c:__blk_mq_sched_bio_merge
  - block/blk-mq-sched.c:blk_mq_sched_dispatch_requests
  - block/blk-mq-sched.c:blk_mq_sched_assign_ioc
```
```
In block/genhd.c (c07a4a54)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - block/genhd.c:disk_check_events
  - block/genhd.c:disk_clear_events
  - block/genhd.c:disk_clear_events
  - block/genhd.c:disk_flush_events
```
```
In block/ioprio.c (c07a8c9c)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
```
```
In block/badblocks.c (c07a9e6c)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_clear
```
```
In block/bsg.c (c07b51bc)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - block/bsg.c:bsg_ioctl
```
```
In block/blk-cgroup.c (c07b6c3c)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_can_attach
  - block/blk-cgroup.c:blkcg_init_queue
  - block/blk-cgroup.c:blkcg_init_queue
  - block/blk-cgroup.c:blkcg_destroy_blkgs
  - block/blk-cgroup.c:blkcg_destroy_blkgs
  - block/blk-cgroup.c:blkcg_destroy_blkgs
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-cgroup.c:blkg_conf_finish
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkcg_print_blkgs
  - block/blk-cgroup.c:blkcg_reset_stats
  - block/blk-cgroup.c:blkg_destroy_all
  - block/blk-cgroup.c:blkg_destroy_all
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-throttle.c (c07bd934)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_drain
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_dispatch_work_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
```
```
In block/blk-iocost.c (c07c00a0)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_qos_write
  - block/blk-iocost.c:ioc_qos_write
  - block/blk-iocost.c:ioc_weight_write
  - block/blk-iocost.c:ioc_weight_write
  - block/blk-iocost.c:ioc_weight_write
  - block/blk-iocost.c:ioc_pd_free
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-iocost.c:ioc_rqos_exit
  - block/blk-iocost.c:ioc_rqos_queue_depth_changed
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:iocg_activate
  - block/blk-iocost.c:iocg_activate
```
```
In block/mq-deadline.c (c07c348c)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - block/mq-deadline.c:deadline_read_fifo_stop
  - block/mq-deadline.c:dd_insert_requests
  - block/mq-deadline.c:dd_bio_merge
  - block/mq-deadline.c:dd_dispatch_request
```
```
In block/blk-mq-debugfs.c (c07ca314)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - block/blk-mq-debugfs.c:ctx_default_rq_list_stop
  - block/blk-mq-debugfs.c:hctx_dispatch_stop
  - block/blk-mq-debugfs.c:queue_requeue_list_stop
```
```
In block/blk-pm.c (c07d00bc)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - block/blk-pm.c:blk_pre_runtime_suspend
```
```
In lib/lockref.c (c07d09f0)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - lib/lockref.c:lockref_get_not_dead
  - lib/lockref.c:lockref_put_or_lock
  - lib/lockref.c:lockref_get_or_lock
  - lib/lockref.c:lockref_put_not_zero
  - lib/lockref.c:lockref_get_not_zero
  - lib/lockref.c:lockref_get
```
```
In lib/percpu-refcount.c (c07db13c)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
```
```
In lib/rhashtable.c (c07dbb00)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_walk_stop
  - lib/rhashtable.c:rhashtable_walk_start_check
  - lib/rhashtable.c:rhashtable_walk_exit
  - lib/rhashtable.c:rhashtable_walk_enter
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In lib/refcount.c (c07dd8a4)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
```
```
In lib/genalloc.c (c07ea53c)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_add_owner
```
```
In lib/textsearch.c (c0807e3c)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - lib/textsearch.c:textsearch_unregister
  - lib/textsearch.c:textsearch_register
```
```
In lib/percpu_counter.c (c08082f8)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - lib/percpu_counter.c:percpu_counter_cpu_dead
  - lib/percpu_counter.c:percpu_counter_cpu_dead
```
```
In drivers/irqchip/irq-al-fic.c (c0812e78)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - drivers/irqchip/irq-al-fic.c:al_fic_irq_set_type
```
```
In drivers/irqchip/irq-alpine-msi.c (c081322c)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - drivers/irqchip/irq-alpine-msi.c:alpine_msix_middle_domain_alloc
  - drivers/irqchip/irq-alpine-msi.c:alpine_msix_middle_domain_alloc
  - drivers/irqchip/irq-alpine-msi.c:alpine_msix_free_sgi
```
```
In drivers/irqchip/exynos-combiner.c (c08139b0)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - drivers/irqchip/exynos-combiner.c:combiner_handle_cascade_irq
```
```
In drivers/irqchip/irq-hip04.c (c0813fc4)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - drivers/irqchip/irq-hip04.c:hip04_irq_set_affinity
  - drivers/irqchip/irq-hip04.c:hip04_irq_set_type
  - drivers/irqchip/irq-hip04.c:hip04_unmask_irq
  - drivers/irqchip/irq-hip04.c:hip04_mask_irq
```
```
In drivers/irqchip/irq-dw-apb-ictl.c (c08144a8)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - drivers/irqchip/irq-dw-apb-ictl.c:dw_apb_ictl_resume
```
```
In drivers/irqchip/irq-gic.c (c0815d04)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic.c:gic_migrate_target
```
```
In drivers/irqchip/irq-gic-v2m.c (c0816550)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v2m.c:gicv2m_irq_domain_alloc
  - drivers/irqchip/irq-gic-v2m.c:gicv2m_unalloc_msi
```
```
In drivers/irqchip/irq-gic-v3-its.c (c081cbc4)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3-its.c:its_cpu_init
  - drivers/irqchip/irq-gic-v3-its.c:its_restore_enable
  - drivers/irqchip/irq-gic-v3-its.c:its_save_disable
```
```
In drivers/irqchip/irq-armada-370-xp.c (c081ebcc)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - drivers/irqchip/irq-armada-370-xp.c:armada_xp_set_affinity
```
```
In drivers/irqchip/irq-crossbar.c (c08206ac)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - drivers/irqchip/irq-crossbar.c:crossbar_domain_free
  - drivers/irqchip/irq-crossbar.c:crossbar_domain_alloc
```
```
In drivers/irqchip/irq-imx-gpcv2.c (c08219c8)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - drivers/irqchip/irq-imx-gpcv2.c:imx_gpcv2_irq_mask
  - drivers/irqchip/irq-imx-gpcv2.c:imx_gpcv2_irq_unmask
```
```
In drivers/irqchip/irq-meson-gpio.c (c0822468)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - drivers/irqchip/irq-meson-gpio.c:meson_gpio_irq_domain_alloc
  - drivers/irqchip/irq-meson-gpio.c:meson_gpio_irq_domain_alloc
```
```
In drivers/irqchip/qcom-pdc.c (c08227d8)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - drivers/irqchip/qcom-pdc.c:pdc_enable_intr
```
```
In drivers/phy/samsung/phy-exynos-mipi-video.c (c082c408)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - drivers/phy/samsung/phy-exynos-mipi-video.c:exynos_mipi_video_phy_power_off
  - drivers/phy/samsung/phy-exynos-mipi-video.c:exynos_mipi_video_phy_power_on
```
```
In drivers/pinctrl/pinctrl-rockchip.c (c0838e98)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_irq_set_type
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_irq_set_type
```
```
In drivers/pinctrl/pinctrl-single.c (c083f374)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-single.c:pcs_irq_handle
```
```
In drivers/gpio/gpio-mvebu.c (c086ac9c)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_level_irq_unmask
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_level_irq_mask
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_edge_irq_unmask
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_edge_irq_mask
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_irq_ack
```
```
In drivers/gpio/gpio-pl061.c (c086ea24)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - drivers/gpio/gpio-pl061.c:pl061_irq_ack
  - drivers/gpio/gpio-pl061.c:pl061_irq_unmask
  - drivers/gpio/gpio-pl061.c:pl061_irq_mask
```
```
In drivers/gpio/gpio-zevio.c (c0874454)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - drivers/gpio/gpio-zevio.c:zevio_gpio_direction_output
  - drivers/gpio/gpio-zevio.c:zevio_gpio_direction_input
  - drivers/gpio/gpio-zevio.c:zevio_gpio_set
  - drivers/gpio/gpio-zevio.c:zevio_gpio_get
```
```
In drivers/pci/access.c (c0877be4)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_cfg_access_lock
  - drivers/pci/access.c:pci_user_write_config_dword
  - drivers/pci/access.c:pci_user_write_config_word
  - drivers/pci/access.c:pci_user_write_config_byte
  - drivers/pci/access.c:pci_user_read_config_dword
  - drivers/pci/access.c:pci_user_read_config_word
  - drivers/pci/access.c:pci_user_read_config_byte
  - drivers/pci/access.c:pci_wait_cfg
```
```
In drivers/pci/pci.c (c087f350)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - drivers/pci/pci.c:resource_alignment_store
  - drivers/pci/pci.c:resource_alignment_show
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
  - drivers/pci/pci.c:pci_dev_complete_resume
  - drivers/pci/pci.c:pci_dev_adjust_pme
```
```
In drivers/pci/pci-driver.c (c08859a4)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_unregister_driver
  - drivers/pci/pci-driver.c:pci_match_device
  - drivers/pci/pci-driver.c:remove_id_store
  - drivers/pci/pci-driver.c:pci_add_dynid
```
```
In drivers/pci/pcie/pme.c (c089cf78)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_resume
  - drivers/pci/pcie/pme.c:pcie_pme_disable_interrupt
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
```
```
In drivers/rapidio/rio.c (c08c1730)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_route_clr_table
  - drivers/rapidio/rio.c:rio_route_get_entry
  - drivers/rapidio/rio.c:rio_route_add_entry
  - drivers/rapidio/rio.c:rio_get_asm
  - drivers/rapidio/rio.c:rio_get_comptag
  - drivers/rapidio/rio.c:rio_release_inb_pwrite
  - drivers/rapidio/rio.c:rio_request_inb_pwrite
  - drivers/rapidio/rio.c:rio_del_device
  - drivers/rapidio/rio.c:rio_free_net
```
```
In drivers/clk/berlin/berlin2-div.c (c08f7424)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - drivers/clk/berlin/berlin2-div.c:berlin2_div_recalc_rate
  - drivers/clk/berlin/berlin2-div.c:berlin2_div_get_parent
  - drivers/clk/berlin/berlin2-div.c:berlin2_div_set_parent
  - drivers/clk/berlin/berlin2-div.c:berlin2_div_disable
  - drivers/clk/berlin/berlin2-div.c:berlin2_div_enable
  - drivers/clk/berlin/berlin2-div.c:berlin2_div_is_enabled
```
```
In drivers/clk/mvebu/dove-divider.c (c0903df4)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - drivers/clk/mvebu/dove-divider.c:dove_set_clock
```
```
In drivers/dma/virt-dma.c (c091fa5c)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - drivers/dma/virt-dma.c:vchan_complete
```
```
In drivers/dma/amba-pl08x.c (c09229c4)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - drivers/dma/amba-pl08x.c:pl08x_irq
  - drivers/dma/amba-pl08x.c:pl08x_phy_free
```
```
In drivers/dma/mv_xor.c (c0924924)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - drivers/dma/mv_xor.c:mv_xor_tasklet
```
```
In drivers/dma/ipu/ipu_irq.c (c0927098)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - drivers/dma/ipu/ipu_irq.c:ipu_irq_handler
  - drivers/dma/ipu/ipu_irq.c:ipu_irq_handler
  - drivers/dma/ipu/ipu_irq.c:ipu_irq_handler
```
```
In drivers/dma/ipu/ipu_idmac.c (c0929054)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - drivers/dma/ipu/ipu_idmac.c:idmac_interrupt
  - drivers/dma/ipu/ipu_idmac.c:idmac_interrupt
  - drivers/dma/ipu/ipu_idmac.c:idmac_interrupt
  - drivers/dma/ipu/ipu_idmac.c:idmac_interrupt
  - drivers/dma/ipu/ipu_idmac.c:idmac_interrupt
```
```
In drivers/dma/tegra20-apb-dma.c (c0929ad8)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - drivers/dma/tegra20-apb-dma.c:tegra_dma_global_pause
```
```
In drivers/dma/ti/edma.c (c092d538)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - drivers/dma/ti/edma.c:dma_ccerr_handler
  - drivers/dma/ti/edma.c:dma_irq_handler
```
```
In drivers/dma/ti/omap-dma.c (c0930ddc)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - drivers/dma/ti/omap-dma.c:omap_dma_free_chan_resources
  - drivers/dma/ti/omap-dma.c:omap_dma_alloc_chan_resources
  - drivers/dma/ti/omap-dma.c:omap_dma_irq
  - drivers/dma/ti/omap-dma.c:omap_dma_irq
```
```
In drivers/soc/dove/pmu.c (c0933ed4)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - drivers/soc/dove/pmu.c:pmu_irq_handler
```
```
In drivers/soc/renesas/r9a06g032-smp.c (c093855c)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - drivers/soc/renesas/r9a06g032-smp.c:r9a06g032_smp_boot_secondary
```
```
In drivers/virtio/virtio.c (c093ea44)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - drivers/virtio/virtio.c:virtio_config_enable
  - drivers/virtio/virtio.c:virtio_config_disable
```
```
In drivers/virtio/virtio_balloon.c (c094872c)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:return_free_pages_to_mm
  - drivers/virtio/virtio_balloon.c:stats_request
```
```
In drivers/tty/tty_io.c (c095d68c)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:release_one_tty
  - drivers/tty/tty_io.c:redirected_tty_write
  - drivers/tty/tty_io.c:check_tty_count
  - drivers/tty/tty_io.c:tty_add_file
```
```
In drivers/tty/n_tty.c (c0960fa0)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_read
```
```
In drivers/tty/tty_ioctl.c (c0963e98)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
```
```
In drivers/tty/tty_port.c (c09661cc)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_open
```
```
In drivers/tty/tty_ldsem.c (c0e9ebd0)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_write
  - drivers/tty/tty_ldsem.c:ldsem_down_write
  - drivers/tty/tty_ldsem.c:ldsem_down_write
  - drivers/tty/tty_ldsem.c:ldsem_down_read
  - drivers/tty/tty_ldsem.c:ldsem_down_read
  - drivers/tty/tty_ldsem.c:ldsem_down_read
```
```
In drivers/tty/tty_jobctrl.c (c0967abc)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:tty_open_proc_set_tty
  - drivers/tty/tty_jobctrl.c:tty_open_proc_set_tty
```
```
In drivers/tty/pty.c (c096826c)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - drivers/tty/pty.c:pty_set_termios
  - drivers/tty/pty.c:pty_flush_buffer
  - drivers/tty/pty.c:pty_set_pktmode
```
```
In drivers/tty/sysrq.c (c0969d10)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:__sysrq_swap_key_ops
  - drivers/tty/sysrq.c:send_sig_all
```
```
In drivers/tty/vt/vt_ioctl.c (c096c330)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
```
```
In drivers/tty/vt/vc_screen.c (c096dab4)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
```
```
In drivers/tty/vt/keyboard.c (c0972aa8)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:vt_reset_keyboard
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:fn_spawn_con
```
```
In drivers/tty/vt/vt.c (c09773a8)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:vt_console_print
```
```
In drivers/tty/serial/serial_core.c (c0981158)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/tty/serial/serial_core.c:uart_line_info
  - drivers/tty/serial/serial_core.c:uart_carrier_raised
  - drivers/tty/serial/serial_core.c:uart_tty_port_shutdown
  - drivers/tty/serial/serial_core.c:uart_get_icount
  - drivers/tty/serial/serial_core.c:uart_wait_modem_status
  - drivers/tty/serial/serial_core.c:uart_wait_modem_status
  - drivers/tty/serial/serial_core.c:uart_tiocmget
  - drivers/tty/serial/serial_core.c:uart_change_speed
```
```
In drivers/tty/serial/8250/8250_core.c (c0982fd8)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial_do_unlink
  - drivers/tty/serial/8250/8250_core.c:serial8250_interrupt
```
```
In drivers/tty/serial/8250/8250_port.c (c0986c38)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
```
```
In drivers/tty/serial/amba-pl011.c (c098f73c)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - drivers/tty/serial/amba-pl011.c:pl011_console_write
  - drivers/tty/serial/amba-pl011.c:pl011_shutdown
  - drivers/tty/serial/amba-pl011.c:pl011_shutdown
  - drivers/tty/serial/amba-pl011.c:pl011_disable_interrupts
  - drivers/tty/serial/amba-pl011.c:pl011_enable_interrupts
  - drivers/tty/serial/amba-pl011.c:pl011_int
  - drivers/tty/serial/amba-pl011.c:pl011_dma_rx_callback
  - drivers/tty/serial/amba-pl011.c:pl011_dma_rx_chars
```
```
In drivers/tty/serial/imx.c (c0997f04)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - drivers/tty/serial/imx.c:imx_uart_int
  - drivers/tty/serial/imx.c:imx_uart_rxint
  - drivers/tty/serial/imx.c:imx_uart_txint
  - drivers/tty/serial/imx.c:imx_uart_rtsint
```
```
In drivers/tty/serial/meson_uart.c (c09986c8)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - drivers/tty/serial/meson_uart.c:meson_serial_port_write
  - drivers/tty/serial/meson_uart.c:meson_uart_interrupt
  - drivers/tty/serial/meson_uart.c:meson_uart_interrupt
```
```
In drivers/tty/serial/msm_serial.c (c099c038)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - drivers/tty/serial/msm_serial.c:__msm_console_write
  - drivers/tty/serial/msm_serial.c:msm_uart_irq
  - drivers/tty/serial/msm_serial.c:msm_uart_irq
  - drivers/tty/serial/msm_serial.c:msm_uart_irq
  - drivers/tty/serial/msm_serial.c:msm_uart_irq
```
```
In drivers/tty/serial/omap-serial.c (c09a0644)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - drivers/tty/serial/omap-serial.c:serial_omap_console_write
  - drivers/tty/serial/omap-serial.c:serial_omap_irq
```
```
In drivers/tty/serial/owl-uart.c (c09a28d0)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - drivers/tty/serial/owl-uart.c:owl_uart_port_write
  - drivers/tty/serial/owl-uart.c:owl_uart_irq
```
```
In drivers/tty/serial/rda-uart.c (c09a3768)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - drivers/tty/serial/rda-uart.c:rda_uart_port_write
  - drivers/tty/serial/rda-uart.c:rda_interrupt
```
```
In drivers/char/random.c (c09a8058)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - drivers/char/random.c:invalidate_batched_entropy
  - drivers/char/random.c:proc_do_uuid
  - drivers/char/random.c:add_interrupt_randomness
```
```
In drivers/char/virtio_console.c (c09b0408)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_remove
  - drivers/char/virtio_console.c:control_work_handler
  - drivers/char/virtio_console.c:control_work_handler
  - drivers/char/virtio_console.c:unplug_port
  - drivers/char/virtio_console.c:unplug_port
  - drivers/char/virtio_console.c:unplug_port
  - drivers/char/virtio_console.c:remove_port_data
  - drivers/char/virtio_console.c:remove_port_data
  - drivers/char/virtio_console.c:add_port
  - drivers/char/virtio_console.c:fill_queue
  - drivers/char/virtio_console.c:fill_queue
  - drivers/char/virtio_console.c:init_port_console
  - drivers/char/virtio_console.c:port_fops_open
  - drivers/char/virtio_console.c:port_fops_open
  - drivers/char/virtio_console.c:port_fops_open
  - drivers/char/virtio_console.c:port_fops_release
  - drivers/char/virtio_console.c:port_fops_release
```
```
In drivers/iommu/iommu.c (c09be670)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_ops_from_fwnode
  - drivers/iommu/iommu.c:iommu_device_unregister
  - drivers/iommu/iommu.c:iommu_device_register
```
```
In drivers/iommu/omap-iommu.c (c09c4280)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - drivers/iommu/omap-iommu.c:omap_iommu_detach_dev
  - drivers/iommu/omap-iommu.c:_omap_iommu_detach_dev
  - drivers/iommu/omap-iommu.c:omap_iommu_attach_dev
  - drivers/iommu/omap-iommu.c:omap_iommu_attach_dev
  - drivers/iommu/omap-iommu.c:omap_iommu_attach_dev
  - drivers/iommu/omap-iommu.c:omap_iommu_map
  - drivers/iommu/omap-iommu.c:omap_iommu_detach
  - drivers/iommu/omap-iommu.c:iopgtable_clear_entry
  - drivers/iommu/omap-iommu.c:iopte_alloc
```
```
In drivers/iommu/tegra-gart.c (c09c7250)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - drivers/iommu/tegra-gart.c:gart_iommu_iova_to_phys
  - drivers/iommu/tegra-gart.c:gart_iommu_unmap
  - drivers/iommu/tegra-gart.c:gart_iommu_map
  - drivers/iommu/tegra-gart.c:gart_iommu_detach_dev
  - drivers/iommu/tegra-gart.c:gart_iommu_attach_dev
```
```
In drivers/iommu/exynos-iommu.c (c09cac84)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - drivers/iommu/exynos-iommu.c:exynos_iommu_map
  - drivers/iommu/exynos-iommu.c:exynos_iommu_map
  - drivers/iommu/exynos-iommu.c:exynos_iommu_attach_device
  - drivers/iommu/exynos-iommu.c:exynos_iommu_detach_device
  - drivers/iommu/exynos-iommu.c:exynos_iommu_domain_free
  - drivers/iommu/exynos-iommu.c:exynos_sysmmu_irq
```
```
In drivers/base/core.c (c09d5968)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_shutdown
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:get_device_parent
  - drivers/base/core.c:devices_kset_move_last
```
```
In drivers/base/bus.c (c09d64d0)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_sort_breadthfirst
```
```
In drivers/base/dd.c (c09d96dc)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - drivers/base/dd.c:driver_detach
  - drivers/base/dd.c:driver_detach
```
```
In drivers/base/platform.c (c09db7f8)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - drivers/base/platform.c:__platform_driver_probe
```
```
In drivers/base/attribute_container.c (c09de210)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - drivers/base/attribute_container.c:attribute_container_unregister
```
```
In drivers/base/swnode.c (c09e16e0)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - drivers/base/swnode.c:software_node_find_by_name
  - drivers/base/swnode.c:software_node_to_swnode
```
```
In drivers/base/devtmpfs.c (c09e30b0)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - drivers/base/devtmpfs.c:devtmpfs_delete_node
  - drivers/base/devtmpfs.c:devtmpfs_create_node
```
```
In drivers/base/power/sysfs.c (c09e3978)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
```
```
In drivers/base/power/common.c (c09e4a94)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - drivers/base/power/common.c:dev_pm_put_subsys_data
  - drivers/base/power/common.c:dev_pm_get_subsys_data
```
```
In drivers/base/power/qos.c (c09e5eac)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - drivers/base/power/qos.c:dev_pm_qos_constraints_destroy
  - drivers/base/power/qos.c:dev_pm_qos_constraints_allocate
```
```
In drivers/base/power/runtime.c (c09e8e08)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_drop_link
  - drivers/base/power/runtime.c:pm_runtime_new_link
  - drivers/base/power/runtime.c:__pm_runtime_use_autosuspend
  - drivers/base/power/runtime.c:pm_runtime_set_autosuspend_delay
  - drivers/base/power/runtime.c:pm_runtime_irq_safe
  - drivers/base/power/runtime.c:pm_runtime_no_callbacks
  - drivers/base/power/runtime.c:pm_runtime_allow
  - drivers/base/power/runtime.c:pm_runtime_forbid
  - drivers/base/power/runtime.c:__pm_runtime_disable
  - drivers/base/power/runtime.c:pm_runtime_barrier
  - drivers/base/power/runtime.c:__pm_runtime_barrier
  - drivers/base/power/runtime.c:__pm_runtime_barrier
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:pm_runtime_work
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:__rpm_callback
  - drivers/base/power/runtime.c:__rpm_callback
  - drivers/base/power/runtime.c:pm_runtime_set_memalloc_noio
```
```
In drivers/base/power/main.c (c09ed5e0)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_pm_check_callbacks
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:dpm_propagate_wakeup_to_parent
```
```
In drivers/base/power/wakeup.c (c09ee9e0)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:device_wakeup_disable
  - drivers/base/power/wakeup.c:device_wakeup_enable
  - drivers/base/power/wakeup.c:device_wakeup_enable
```
```
In drivers/base/power/domain.c (c09f1658)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_add_device
  - drivers/base/power/domain.c:genpd_add_device
  - drivers/base/power/domain.c:genpd_free_dev_data
  - drivers/base/power/domain.c:genpd_dev_pm_qos_notifier
```
```
In drivers/base/power/clock_ops.c (c09f4bb8)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - drivers/base/power/clock_ops.c:pm_clk_destroy
  - drivers/base/power/clock_ops.c:pm_clk_remove_clk
  - drivers/base/power/clock_ops.c:pm_clk_remove_clk
  - drivers/base/power/clock_ops.c:pm_clk_remove
  - drivers/base/power/clock_ops.c:pm_clk_remove
  - drivers/base/power/clock_ops.c:__pm_clk_add
```
```
In drivers/base/firmware_loader/main.c (c09f5f18)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:device_uncache_fw_images_work
  - drivers/base/firmware_loader/main.c:device_uncache_fw_images_work
  - drivers/base/firmware_loader/main.c:device_uncache_fw_images_work
  - drivers/base/firmware_loader/main.c:dev_cache_fw_image
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/main.c:assign_fw
  - drivers/base/firmware_loader/main.c:free_fw_priv
  - drivers/base/firmware_loader/main.c:free_fw_priv
```
```
In drivers/base/regmap/regmap.c (c09f89fc)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_async_complete_cb
```
```
In drivers/block/loop.c (c0a0658c)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:loop_attr_do_show_backing_file
```
```
In drivers/mfd/ezx-pcap.c (c0a2a688)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:pcap_adc_irq
  - drivers/mfd/ezx-pcap.c:pcap_adc_irq
```
```
In drivers/mfd/omap-usb-tll.c (c0a35b7c)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - drivers/mfd/omap-usb-tll.c:omap_tll_disable
  - drivers/mfd/omap-usb-tll.c:omap_tll_enable
  - drivers/mfd/omap-usb-tll.c:omap_tll_init
  - drivers/mfd/omap-usb-tll.c:usbtll_omap_remove
  - drivers/mfd/omap-usb-tll.c:usbtll_omap_probe
```
```
In drivers/mfd/syscon.c (c0a38948)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - drivers/mfd/syscon.c:device_node_get_regmap
  - drivers/mfd/syscon.c:of_syscon_register
```
```
In drivers/dax/super.c (c0a3a408)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_get_by_host
  - drivers/dax/super.c:alloc_dax
```
```
In drivers/dma-buf/dma-buf.c (c0a3c8e4)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/dma-buf/dma-fence.c (c0a3d418)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_get_stub
```
```
In drivers/dma-buf/sw_sync.c (c0a413c4)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_release
  - drivers/dma-buf/sw_sync.c:sync_timeline_signal
```
```
In drivers/dma-buf/sync_debug.c (c0a41be0)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - drivers/dma-buf/sync_debug.c:sync_info_debugfs_show
  - drivers/dma-buf/sync_debug.c:sync_info_debugfs_show
  - drivers/dma-buf/sync_debug.c:sync_info_debugfs_show
```
```
In drivers/scsi/scsi_lib.c (c0a4cadc)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
```
```
In drivers/scsi/scsi_scan.c (c0a504a4)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:do_scan_async
  - drivers/scsi/scsi_scan.c:scsi_complete_async_scans
  - drivers/scsi/scsi_scan.c:scsi_complete_async_scans
```
```
In drivers/scsi/scsi_dh.c (c0a56518)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - drivers/scsi/scsi_dh.c:__scsi_dh_lookup
```
```
In drivers/scsi/sr.c (c0a5e738)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_kref_release
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sr.c:sr_probe
```
```
In drivers/scsi/sg.c (c0a627b0)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
```
```
In drivers/ata/libata-core.c (c0a684d0)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
```
```
In drivers/ata/libata-scsi.c (c0a74598)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_ncq_prio_enable_store
  - drivers/ata/libata-scsi.c:ata_ncq_prio_enable_store
  - drivers/ata/libata-scsi.c:ata_ncq_prio_enable_show
  - drivers/ata/libata-scsi.c:ata_scsi_park_show
```
```
In drivers/ata/libata-sff.c (c0a8227c)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_pio_task
  - drivers/ata/libata-sff.c:ata_sff_pio_task
  - drivers/ata/libata-sff.c:ata_sff_flush_pio_task
```
```
In drivers/ata/libahci.c (c0a85d50)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - drivers/ata/libahci.c:ahci_single_level_irq_intr
  - drivers/ata/libahci.c:ahci_multi_irqs_intr_hard
```
```
In drivers/ata/sata_highbank.c (c0a889c4)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - drivers/ata/sata_highbank.c:__combo_phy_reg_write
  - drivers/ata/sata_highbank.c:__combo_phy_reg_read
```
```
In drivers/mtd/mtdpart.c (c0a949a8)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - drivers/mtd/mtdpart.c:parse_mtd_partitions
  - drivers/mtd/mtdpart.c:deregister_mtd_parser
  - drivers/mtd/mtdpart.c:__register_mtd_parser
  - drivers/mtd/mtdpart.c:mtd_part_parser_get
```
```
In drivers/mtd/mtd_blkdevs.c (c0a98b80)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - drivers/mtd/mtd_blkdevs.c:mtd_queue_rq
  - drivers/mtd/mtd_blkdevs.c:mtd_blktrans_work
  - drivers/mtd/mtd_blkdevs.c:mtd_blktrans_work
```
```
In drivers/mtd/chips/chipreg.c (c0a99494)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - drivers/mtd/chips/chipreg.c:get_mtd_chip_driver
  - drivers/mtd/chips/chipreg.c:unregister_mtd_chip_driver
  - drivers/mtd/chips/chipreg.c:register_mtd_chip_driver
```
```
In drivers/net/tun.c (c0ac6fe8)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_device_event
  - drivers/net/tun.c:tun_peek_len
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_chr_poll
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_attach
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:tun_queue_purge
  - drivers/net/tun.c:tun_flow_cleanup
  - drivers/net/tun.c:tun_napi_poll
  - drivers/net/tun.c:tun_napi_poll
```
```
In drivers/net/ethernet/freescale/fec_main.c (c0accbdc)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_main.c:fec_resume
  - drivers/net/ethernet/freescale/fec_main.c:fec_resume
  - drivers/net/ethernet/freescale/fec_main.c:fec_suspend
  - drivers/net/ethernet/freescale/fec_main.c:fec_suspend
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_close
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_set_pauseparam
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_set_pauseparam
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_adjust_link
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_adjust_link
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_adjust_link
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_adjust_link
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_timeout_work
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_timeout_work
```
```
In drivers/net/ppp/ppp_generic.c (c0adcc44)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:find_compressor
  - drivers/net/ppp/ppp_generic.c:ppp_unregister_compressor
  - drivers/net/ppp/ppp_generic.c:ppp_register_compressor
  - drivers/net/ppp/ppp_generic.c:__ppp_channel_push
  - drivers/net/ppp/ppp_generic.c:ppp_mp_explode
  - drivers/net/ppp/ppp_generic.c:ppp_mp_explode
  - drivers/net/ppp/ppp_generic.c:ppp_mp_explode
  - drivers/net/ppp/ppp_generic.c:ppp_mp_explode
  - drivers/net/ppp/ppp_generic.c:ppp_push
```
```
In drivers/usb/core/hub.c (c0af0bbc)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:hub_ioctl
  - drivers/usb/core/hub.c:hub_disconnect
```
```
In drivers/usb/core/hcd.c (c0af6df4)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:hcd_bus_resume
  - drivers/usb/core/hcd.c:hcd_bus_suspend
  - drivers/usb/core/hcd.c:usb_hcd_synchronize_unlinks
  - drivers/usb/core/hcd.c:usb_hcd_flush_endpoint
  - drivers/usb/core/hcd.c:usb_hcd_flush_endpoint
  - drivers/usb/core/hcd.c:usb_hcd_flush_endpoint
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
  - drivers/usb/core/hcd.c:usb_giveback_urb_bh
  - drivers/usb/core/hcd.c:usb_giveback_urb_bh
  - drivers/usb/core/hcd.c:usb_hcd_unlink_urb_from_ep
  - drivers/usb/core/hcd.c:usb_hcd_link_urb_to_ep
  - drivers/usb/core/hcd.c:rh_call_control
  - drivers/usb/core/hcd.c:rh_call_control
```
```
In drivers/usb/core/urb.c (c0af7cfc)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_poison_anchored_urbs
  - drivers/usb/core/urb.c:usb_poison_anchored_urbs
  - drivers/usb/core/urb.c:usb_kill_anchored_urbs
  - drivers/usb/core/urb.c:usb_kill_anchored_urbs
```
```
In drivers/usb/core/message.c (c0af95d4)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_driver_set_configuration
  - drivers/usb/core/message.c:driver_set_config_work
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_sg_wait
  - drivers/usb/core/message.c:usb_sg_wait
```
```
In drivers/usb/core/driver.c (c0afd128)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_deregister
  - drivers/usb/core/driver.c:remove_id_store
  - drivers/usb/core/driver.c:usb_store_new_id
```
```
In drivers/usb/core/devio.c (c0b04e8c)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:async_completed
```
```
In drivers/usb/dwc2/core_intr.c (c0b10560)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
```
```
In drivers/usb/dwc2/hcd.c (c0b165b8)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue
```
```
In drivers/usb/dwc2/hcd_intr.c (c0b1d4ac)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
```
```
In drivers/usb/host/ehci-hcd.c (c0b29e48)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_resume
  - drivers/usb/host/ehci-hcd.c:ehci_resume
  - drivers/usb/host/ehci-hcd.c:ehci_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_remove_device
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ehci-hcd.c:ehci_shutdown
  - drivers/usb/host/ehci-hcd.c:ehci_silence_controller
  - drivers/usb/host/ehci-hcd.c:ehci_silence_controller
  - drivers/usb/host/ehci-hcd.c:set_owner
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_halt
  - drivers/usb/host/ehci-hcd.c:ehci_halt
  - drivers/usb/host/ehci-hcd.c:fill_bandwidth_buffer
```
```
In drivers/usb/host/ohci-hcd.c (c0b36bbc)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_resume
  - drivers/usb/host/ohci-hcd.c:ohci_restart
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_irq
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:finish_urb
  - drivers/usb/host/ohci-hcd.c:ohci_bus_resume
  - drivers/usb/host/ohci-hcd.c:ohci_bus_suspend
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_suspend
```
```
In drivers/usb/host/uhci-hcd.c (c0b3d18c)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_pci_resume
  - drivers/usb/host/uhci-hcd.c:uhci_pci_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_endpoint_disable
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_endpoint_disable
  - drivers/usb/host/uhci-hcd.c:uhci_rh_resume
  - drivers/usb/host/uhci-hcd.c:uhci_rh_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
```
```
In drivers/usb/host/xhci.c (c0b45584)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_shutdown
  - drivers/usb/host/xhci.c:xhci_stop
```
```
In drivers/usb/host/xhci-ring.c (c0b51654)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:handle_port_status
  - drivers/usb/host/xhci-ring.c:xhci_giveback_urb_in_irq
```
```
In drivers/usb/host/xhci-dbgcap.c (c0b5e180)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_giveback
```
```
In drivers/usb/host/xhci-dbgtty.c (c0b5efb0)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgtty.c:dbc_start_rx
  - drivers/usb/host/xhci-dbgtty.c:dbc_start_tx
```
```
In drivers/usb/musb/musb_host.c (c0b6a284)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - drivers/usb/musb/musb_host.c:musb_giveback
```
```
In drivers/usb/musb/musb_gadget_ep0.c (c0b6e268)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - drivers/usb/musb/musb_gadget_ep0.c:musb_g_ep0_irq
```
```
In drivers/usb/musb/musb_gadget.c (c0b7101c)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - drivers/usb/musb/musb_gadget.c:musb_g_reset
  - drivers/usb/musb/musb_gadget.c:musb_g_disconnect
  - drivers/usb/musb/musb_gadget.c:musb_g_suspend
  - drivers/usb/musb/musb_gadget.c:musb_g_resume
  - drivers/usb/musb/musb_gadget.c:musb_g_giveback
```
```
In drivers/input/serio/serio.c (c0b753d0)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:serio_set_drv
  - drivers/input/serio/serio.c:serio_destroy_port
  - drivers/input/serio/serio.c:serio_handle_event
```
```
In drivers/input/serio/libps2.c (c0b76f68)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_sendbyte
  - drivers/input/serio/libps2.c:ps2_do_sendbyte
```
```
In drivers/input/input.c (c0b79d2c)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - drivers/input/input.c:__input_unregister_device
  - drivers/input/input.c:input_dev_poweroff
  - drivers/input/input.c:input_dev_freeze
  - drivers/input/input.c:input_dev_resume
  - drivers/input/input.c:input_dev_suspend
```
```
In drivers/input/ff-core.c (c0b7c5d4)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - drivers/input/ff-core.c:erase_effect
  - drivers/input/ff-core.c:erase_effect
  - drivers/input/ff-core.c:input_ff_upload
```
```
In drivers/input/mousedev.c (c0b7d618)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_cleanup
  - drivers/input/mousedev.c:mousedev_read
  - drivers/input/mousedev.c:mousedev_write
  - drivers/input/mousedev.c:mousedev_open
  - drivers/input/mousedev.c:mousedev_detach_client
  - drivers/input/mousedev.c:mousedev_notify_readers
```
```
In drivers/input/evdev.c (c0b7e6c0)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_cleanup
  - drivers/input/evdev.c:evdev_read
  - drivers/input/evdev.c:evdev_open
  - drivers/input/evdev.c:evdev_detach_client
  - drivers/input/evdev.c:evdev_pass_values
```
```
In drivers/input/keyboard/atkbd.c (c0b82b6c)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_attr_set_helper
  - drivers/input/keyboard/atkbd.c:atkbd_attr_set_helper
  - drivers/input/keyboard/atkbd.c:atkbd_reconnect
  - drivers/input/keyboard/atkbd.c:atkbd_reconnect
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/input/keyboard/atkbd.c:atkbd_disconnect
  - drivers/input/keyboard/atkbd.c:atkbd_cleanup
```
```
In drivers/input/misc/uinput.c (c0b83a50)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_read
  - drivers/input/misc/uinput.c:uinput_destroy_device
  - drivers/input/misc/uinput.c:uinput_request_alloc_id
```
```
In drivers/rtc/dev.c (c0b89294)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - drivers/rtc/dev.c:rtc_dev_read
  - drivers/rtc/dev.c:rtc_dev_open
```
```
In drivers/rtc/rtc-s3c.c (c0b8efb4)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - drivers/rtc/rtc-s3c.c:s3c_rtc_probe
```
```
In drivers/i2c/i2c-dev.c (c0b97034)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:put_i2c_dev
  - drivers/i2c/i2c-dev.c:i2c_dev_get_by_minor
```
```
In drivers/pps/pps.c (c0ba5954)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - drivers/pps/pps.c:pps_cdev_ioctl
  - drivers/pps/pps.c:pps_cdev_ioctl
  - drivers/pps/pps.c:pps_cdev_ioctl
```
```
In drivers/thermal/thermal_sysfs.c (c0bb7dd0)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - drivers/thermal/thermal_sysfs.c:reset_store
  - drivers/thermal/thermal_sysfs.c:time_in_state_ms_show
  - drivers/thermal/thermal_sysfs.c:total_trans_show
  - drivers/thermal/thermal_sysfs.c:thermal_cooling_device_stats_update
```
```
In drivers/watchdog/watchdog_pretimeout.c (c0bc243c)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_pretimeout.c:watchdog_unregister_pretimeout
  - drivers/watchdog/watchdog_pretimeout.c:watchdog_register_pretimeout
  - drivers/watchdog/watchdog_pretimeout.c:watchdog_unregister_governor
  - drivers/watchdog/watchdog_pretimeout.c:watchdog_register_governor
  - drivers/watchdog/watchdog_pretimeout.c:watchdog_pretimeout_governor_set
  - drivers/watchdog/watchdog_pretimeout.c:watchdog_pretimeout_governor_get
```
```
In drivers/md/md.c (c15c1180)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_notify_reboot
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_setup_cluster
  - drivers/md/md.c:md_setup_cluster
  - drivers/md/md.c:unregister_md_cluster_operations
  - drivers/md/md.c:register_md_cluster_operations
  - drivers/md/md.c:unregister_md_personality
  - drivers/md/md.c:register_md_personality
  - drivers/md/md.c:md_seq_show
  - drivers/md/md.c:md_seq_show
  - drivers/md/md.c:md_seq_next
  - drivers/md/md.c:md_seq_start
  - drivers/md/md.c:md_seq_start
  - drivers/md/md.c:md_unregister_thread
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:__md_stop
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:md_attr_store
  - drivers/md/md.c:md_attr_store
  - drivers/md/md.c:md_attr_show
  - drivers/md/md.c:md_attr_show
  - drivers/md/md.c:max_sync_store
  - drivers/md/md.c:min_sync_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_show
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_show
  - drivers/md/md.c:rdev_size_store
  - drivers/md/md.c:set_in_sync
  - drivers/md/md.c:mddev_unlock
  - drivers/md/md.c:mddev_find
  - drivers/md/md.c:mddev_find
  - drivers/md/md.c:mddev_find
  - drivers/md/md.c:mddev_find
  - drivers/md/md.c:mddev_find
  - drivers/md/md.c:md_flush_request
  - drivers/md/md.c:md_flush_request
```
```
In drivers/md/md-bitmap.c (c0bd7c84)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:behind_writes_used_show
  - drivers/md/md-bitmap.c:can_clear_show
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_destroy
  - drivers/md/md-bitmap.c:md_bitmap_set_memory_bits
  - drivers/md/md-bitmap.c:md_bitmap_start_sync
  - drivers/md/md-bitmap.c:md_bitmap_startwrite
  - drivers/md/md-bitmap.c:md_bitmap_startwrite
  - drivers/md/md-bitmap.c:md_bitmap_startwrite
  - drivers/md/md-bitmap.c:md_bitmap_daemon_work
  - drivers/md/md-bitmap.c:md_bitmap_checkpage
```
```
In drivers/md/dm.c (c0be0b8c)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_get_from_kobject
  - drivers/md/dm.c:dm_wq_work
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_get_md
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:cleanup_mapped_device
  - drivers/md/dm.c:free_minor
  - drivers/md/dm.c:dm_cancel_deferred_remove
  - drivers/md/dm.c:dm_lock_for_deletion
  - drivers/md/dm.c:dm_blk_close
  - drivers/md/dm.c:dm_blk_open
```
```
In drivers/md/dm-kcopyd.c (c0be92dc)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:run_io_job
  - drivers/md/dm-kcopyd.c:run_io_job
```
```
In drivers/md/dm-stats.c (c0bea62c)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_kvzalloc
  - drivers/md/dm-stats.c:dm_kvzalloc
```
```
In drivers/cpufreq/cpufreq.c (c0bf8f8c)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
```
```
In drivers/cpufreq/cpufreq_stats.c (c0bfd5fc)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_record_transition
  - drivers/cpufreq/cpufreq_stats.c:store_reset
  - drivers/cpufreq/cpufreq_stats.c:show_time_in_state
```
```
In drivers/cpuidle/driver.c (c0c02a34)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - drivers/cpuidle/driver.c:cpuidle_driver_unref
  - drivers/cpuidle/driver.c:cpuidle_driver_ref
```
```
In drivers/cpuidle/sysfs.c (c0c032b8)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - drivers/cpuidle/sysfs.c:show_driver_name
  - drivers/cpuidle/sysfs.c:show_current_driver
```
```
In drivers/mmc/core/queue.c (c0c1dcfc)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - drivers/mmc/core/queue.c:mmc_mq_queue_rq
  - drivers/mmc/core/queue.c:mmc_mq_queue_rq
  - drivers/mmc/core/queue.c:mmc_mq_queue_rq
  - drivers/mmc/core/queue.c:mmc_mq_recovery_handler
```
```
In drivers/mmc/host/mmci.c (c0c21134)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - drivers/mmc/host/mmci.c:mmci_irq
```
```
In drivers/mmc/host/sdhci.c (c0c28bb0)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - drivers/mmc/host/sdhci.c:sdhci_irq
  - drivers/mmc/host/sdhci.c:sdhci_irq
```
```
In drivers/mmc/host/omap_hsmmc.c (c0c2c404)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_dma_callback
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_dma_callback
```
```
In drivers/mmc/host/cqhci.c (c0c3070c)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - drivers/mmc/host/cqhci.c:cqhci_irq
  - drivers/mmc/host/cqhci.c:cqhci_irq
```
```
In drivers/leds/led-triggers.c (c0c33c0c)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - drivers/leds/led-triggers.c:led_trigger_blink_oneshot
```
```
In drivers/firmware/memmap.c (c15be778)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - drivers/firmware/memmap.c:firmware_map_remove
  - drivers/firmware/memmap.c:firmware_map_remove
  - drivers/firmware/memmap.c:firmware_map_add_hotplug
  - drivers/firmware/memmap.c:release_firmware_map_entry
```
```
In drivers/firmware/arm_scmi/bus.c (c0c37300)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - drivers/firmware/arm_scmi/bus.c:scmi_protocol_unregister
  - drivers/firmware/arm_scmi/bus.c:scmi_protocol_register
```
```
In drivers/firmware/efi/efi.c (c0e993e8)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
```
```
In drivers/firmware/tegra/bpmp.c (c0c42764)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - drivers/firmware/tegra/bpmp.c:tegra_bpmp_handle_rx
  - drivers/firmware/tegra/bpmp.c:tegra_bpmp_handle_rx
  - drivers/firmware/tegra/bpmp.c:tegra_bpmp_handle_rx
  - drivers/firmware/tegra/bpmp.c:tegra_bpmp_transfer_atomic
  - drivers/firmware/tegra/bpmp.c:tegra_bpmp_transfer_atomic
```
```
In drivers/staging/emxx_udc/emxx_udc.c (c0c5e064)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_udc_irq
  - drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_udc_irq
  - drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_udc_irq
  - drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_udc_irq
  - drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_vbus_irq
  - drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_vbus_irq
  - drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_ep_done
```
```
In drivers/mailbox/tegra-hsp.c (c0c61114)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - drivers/mailbox/tegra-hsp.c:tegra_hsp_shared_irq
  - drivers/mailbox/tegra-hsp.c:tegra_hsp_doorbell_irq
```
```
In drivers/hwspinlock/hwspinlock_core.c (c0c61c1c)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_unlock
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_unlock
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_trylock
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_trylock
```
```
In drivers/memory/omap-gpmc.c (c0c6f618)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - drivers/memory/omap-gpmc.c:gpmc_cs_free
  - drivers/memory/omap-gpmc.c:gpmc_cs_request
  - drivers/memory/omap-gpmc.c:gpmc_cs_delete_mem
  - drivers/memory/omap-gpmc.c:gpmc_cs_insert_mem
```
```
In drivers/vme/vme.c (c0c7793c)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - drivers/vme/vme.c:vme_master_free
  - drivers/vme/vme.c:vme_master_request
  - drivers/vme/vme.c:vme_master_request
  - drivers/vme/vme.c:vme_master_request
```
```
In drivers/perf/arm-ccn.c (c0c7bda0)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - drivers/perf/arm-ccn.c:arm_ccn_pmu_xp_dt_config
```
```
In sound/sound_core.c (c0c824a8)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - sound/sound_core.c:soundcore_open
  - sound/sound_core.c:soundcore_open
  - sound/sound_core.c:sound_remove_unit
```
```
In sound/core/init.c (c0c83d3c)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - sound/core/init.c:snd_card_file_remove
  - sound/core/init.c:snd_card_file_remove
  - sound/core/init.c:snd_card_file_add
  - sound/core/init.c:snd_card_file_add
  - sound/core/init.c:snd_card_disconnect_sync
  - sound/core/init.c:snd_card_disconnect_sync
  - sound/core/init.c:snd_card_disconnect
  - sound/core/init.c:snd_card_disconnect
  - sound/core/init.c:snd_card_disconnect
  - sound/core/init.c:snd_card_disconnect
  - sound/core/init.c:snd_disconnect_release
```
```
In sound/core/control.c (c0c85e28)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - sound/core/control.c:snd_ctl_dev_disconnect
  - sound/core/control.c:snd_ctl_get_preferred_subdevice
  - sound/core/control.c:snd_ctl_read
  - sound/core/control.c:snd_ctl_read
  - sound/core/control.c:snd_ctl_read
```
```
In sound/core/timer.c (c0c8bb5c)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - sound/core/timer.c:snd_timer_user_poll
  - sound/core/timer.c:snd_timer_user_read
  - sound/core/timer.c:snd_timer_user_read
  - sound/core/timer.c:snd_timer_user_read
  - sound/core/timer.c:__snd_timer_user_ioctl
  - sound/core/timer.c:__snd_timer_user_ioctl
  - sound/core/timer.c:__snd_timer_user_ioctl
  - sound/core/timer.c:__snd_timer_user_ioctl
  - sound/core/timer.c:realloc_user_queue
  - sound/core/timer.c:snd_timer_user_tinterrupt
  - sound/core/timer.c:snd_timer_user_tinterrupt
  - sound/core/timer.c:snd_timer_user_interrupt
  - sound/core/timer.c:snd_timer_process_callbacks
  - sound/core/timer.c:snd_timer_stop_slave
  - sound/core/timer.c:snd_timer_start_slave
  - sound/core/timer.c:snd_timer_close_locked
  - sound/core/timer.c:snd_timer_close_locked
  - sound/core/timer.c:snd_timer_close_locked
  - sound/core/timer.c:snd_timer_close_locked
  - sound/core/timer.c:snd_timer_close_locked
  - sound/core/timer.c:snd_timer_open
  - sound/core/timer.c:snd_timer_open
  - sound/core/timer.c:snd_timer_open
```
```
In sound/core/pcm.c (c0c90ca8)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - sound/core/pcm.c:snd_pcm_detach_substream
```
```
In sound/core/pcm_native.c (c0c912c0)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - sound/core/pcm_native.c:snd_pcm_action_group
```
```
In net/socket.c (c0cc3178)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - net/socket.c:sock_register
  - net/socket.c:__sock_recv_ts_and_drops
```
```
In net/core/sock.c (c0cc8394)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - net/core/sock.c:sock_recv_errqueue
  - net/core/sock.c:sock_gettstamp
  - net/core/sock.c:lock_sock_nested
  - net/core/sock.c:sk_free_unlock_clone
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sk_receive_skb
```
```
In net/core/gen_estimator.c (c0cdb138)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - net/core/gen_estimator.c:est_fetch_counters
```
```
In net/core/net_namespace.c (c0cdbaa0)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - net/core/net_namespace.c:netns_get
  - net/core/net_namespace.c:get_net_ns_by_pid
```
```
In net/core/dev.c (c0ce5670)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - net/core/dev.c:netif_napi_add
  - net/core/dev.c:napi_hash_del
  - net/core/dev.c:process_backlog
  - net/core/dev.c:flush_backlog
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_remove_offload
  - net/core/dev.c:dev_add_offload
  - net/core/dev.c:__dev_remove_pack
  - net/core/dev.c:dev_add_pack
```
```
In net/core/dev_addr_lists.c (c0cfa6d0)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - net/core/dev_addr_lists.c:dev_mc_sync_multiple
  - net/core/dev_addr_lists.c:dev_mc_sync
  - net/core/dev_addr_lists.c:dev_uc_sync_multiple
  - net/core/dev_addr_lists.c:dev_uc_sync
```
```
In net/core/neighbour.c (c0cfd0b4)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_seq_stop
  - net/core/neighbour.c:__neigh_for_each_release
  - net/core/neighbour.c:neigh_for_each
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/neighbour.c:neigh_proxy_process
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:neigh_probe
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:neigh_flush_dev
  - net/core/neighbour.c:neigh_remove_one
```
```
In net/core/link_watch.c (c0d0c150)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - net/core/link_watch.c:__linkwatch_run_queue
  - net/core/link_watch.c:__linkwatch_run_queue
```
```
In net/core/net-sysfs.c (c0d222b4)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - net/core/net-sysfs.c:tx_timeout_show
  - net/core/net-sysfs.c:store_rps_dev_flow_table_cnt
  - net/core/net-sysfs.c:operstate_show
  - net/core/net-sysfs.c:address_show
```
```
In net/core/page_pool.c (c0d250c0)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_alloc_pages
```
```
In net/core/netpoll.c (c0d29278)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - net/core/netpoll.c:queue_process
  - net/core/netpoll.c:queue_process
```
```
In net/core/fib_rules.c (c0d2a57c)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_rules_unregister
  - net/core/fib_rules.c:fib_rules_register
```
```
In net/core/netprio_cgroup.c (c0d34efc)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - net/core/netprio_cgroup.c:net_prio_attach
```
```
In net/core/netclassid_cgroup.c (c0d353ec)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - net/core/netclassid_cgroup.c:update_classid_task
  - net/core/netclassid_cgroup.c:update_classid_sock
```
```
In net/core/devlink.c (c0d3bf50)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_trap_report
```
```
In net/sched/sch_generic.c (c0d4c30c)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:pfifo_fast_change_tx_queue_len
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
```
```
In net/sched/sch_api.c (c0d4e80c)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_lookup_ops
  - net/sched/sch_api.c:qdisc_set_default
  - net/sched/sch_api.c:qdisc_set_default
  - net/sched/sch_api.c:qdisc_get_default
  - net/sched/sch_api.c:unregister_qdisc
  - net/sched/sch_api.c:register_qdisc
```
```
In net/sched/cls_api.c (c0d514b8)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_cls_offload_cnt_reset
  - net/sched/cls_api.c:tc_cls_offload_cnt_update
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/sched/cls_api.c:__tcf_get_next_proto
  - net/sched/cls_api.c:unregister_tcf_proto_ops
  - net/sched/cls_api.c:register_tcf_proto_ops
  - net/sched/cls_api.c:__tcf_proto_lookup_ops
```
```
In net/sched/act_api.c (c0d58138)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_lookup_action
  - net/sched/act_api.c:tc_lookup_action_n
  - net/sched/act_api.c:tcf_unregister_action
```
```
In net/sched/ematch.c (c0d5a824)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - net/sched/ematch.c:tcf_em_unregister
  - net/sched/ematch.c:tcf_em_register
```
```
In net/netlink/af_netlink.c (c0d5cc94)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_getsockopt
  - net/netlink/af_netlink.c:netlink_set_err
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_getname
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/af_netlink.c:netlink_table_ungrab
```
```
In net/ipv4/route.c (c0d6be5c)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/ip_fragment.c (c0d6f5f8)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_expire
  - net/ipv4/ip_fragment.c:ip_expire
```
```
In net/ipv4/ip_sockglue.c (c0d788a4)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/inet_hashtables.c (c0d7a55c)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_hashtables.c:__inet_inherit_port
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_timewait_sock.c (c0d7a808)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (c0d7c038)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_add
  - net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close
```
```
In net/ipv4/tcp.c (c0d8405c)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/tcp_input.c (c0d88300)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_output.c (c0d96818)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_tsq_handler
```
```
In net/ipv4/tcp_timer.c (c0d97bfc)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_compressed_ack_kick
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer
  - net/ipv4/tcp_timer.c:tcp_delack_timer
```
```
In net/ipv4/tcp_ipv4.c (c0d98ea8)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_seq_stop
  - net/ipv4/tcp_ipv4.c:listening_get_next
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/tcp_minisocks.c (c0d9e9f8)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/tcp_cong.c (c0da012c)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_set_allowed_congestion_control
  - net/ipv4/tcp_cong.c:tcp_unregister_congestion_control
  - net/ipv4/tcp_cong.c:tcp_register_congestion_control
```
```
In net/ipv4/tcp_fastopen.c (c0da23a8)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_reset_cipher
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_ctx_destroy
```
```
In net/ipv4/tcp_ulp.c (c0da35e8)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - net/ipv4/tcp_ulp.c:tcp_unregister_ulp
  - net/ipv4/tcp_ulp.c:tcp_register_ulp
```
```
In net/ipv4/raw.c (c0da55d4)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_seq_stop
  - net/ipv4/raw.c:raw_recvmsg
  - net/ipv4/raw.c:raw_recvmsg
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (c0da7a0c)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
  - net/ipv4/udp.c:udp_rmem_release
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_lport_inuse2
```
```
In net/ipv4/arp.c (c0dae6d0)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_seq_show
```
```
In net/ipv4/icmp.c (c0db0e48)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:icmp_global_allow
```
```
In net/ipv4/igmp.c (c0dbc070)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_timer_expire
```
```
In net/ipv4/fib_semantics.c (c0dc2844)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:ip_fib_check_default
  - net/ipv4/fib_semantics.c:ip_fib_check_default
```
```
In net/ipv4/ping.c (c0dcc47c)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv4/sysctl_net_ipv4.c (c0dd25b8)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
```
```
In net/ipv4/ipmr.c (c0dd6d5c)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_vif_seq_stop
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_ioctl
  - net/ipv4/ipmr.c:ipmr_ioctl
  - net/ipv4/ipmr.c:ipmr_expire_process
  - net/ipv4/ipmr.c:reg_vif_xmit
```
```
In net/ipv4/ipmr_base.c (c0ddb250)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
```
```
In net/ipv4/syncookies.c (c0ddbb78)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:tcp_get_cookie_sock
```
```
In net/ipv4/cipso_ipv4.c (c0ddf97c)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_putdef
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_remove
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_remove
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_remove
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_add
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_add
```
```
In net/xfrm/xfrm_policy.c (c0de27f8)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_if_register_cb
  - net/xfrm/xfrm_policy.c:xfrm_policy_register_afinfo
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
```
```
In net/xfrm/xfrm_state.c (c0deb970)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_replay_timer_handler
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
  - net/xfrm/xfrm_state.c:xfrm_timer_handler
```
```
In net/xfrm/xfrm_input.c (c0df2b60)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_device.c (c0df65b8)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
  - net/xfrm/xfrm_device.c:xfrm_dev_resume
```
```
In net/unix/af_unix.c (c0df6d34)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_seq_show
  - net/unix/af_unix.c:unix_seq_stop
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_inq_len
  - net/unix/af_unix.c:unix_shutdown
  - net/unix/af_unix.c:unix_shutdown
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_accept
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_wait_for_peer
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_find_other
  - net/unix/af_unix.c:unix_find_other
  - net/unix/af_unix.c:unix_autobind
  - net/unix/af_unix.c:unix_autobind
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_listen
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_dgram_peer_wake_me
  - net/unix/af_unix.c:unix_dgram_peer_wake_disconnect
  - net/unix/af_unix.c:unix_peer_get
```
```
In net/unix/garbage.c (c0dfba50)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:scan_inflight
```
```
In net/unix/scm.c (c0dfbfc8)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - net/unix/scm.c:unix_notinflight
  - net/unix/scm.c:unix_inflight
```
```
In net/ipv6/anycast.c (c0dfe3ec)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_anycast_cleanup
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/anycast.c:ipv6_del_acaddr_hash
```
```
In net/ipv6/ip6_output.c (c0e02218)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/addrconf.c (c0e06a4c)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_disable_policy_idev
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_dad_run
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:manage_tempaddrs
  - net/ipv6/addrconf.c:check_cleanup_prefix_route
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/addrlabel.c (c0e11ef0)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
  - net/ipv6/addrlabel.c:ip6addrlbl_net_exit
  - net/ipv6/addrlabel.c:ip6addrlbl_add
```
```
In net/ipv6/route.c (c0e18534)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_sk_update_pmtu
  - net/ipv6/route.c:rt6_score_route
```
```
In net/ipv6/ip6_fib.c (c0e21038)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_del
```
```
In net/ipv6/udp.c (c0e2a758)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (c0e2d7f0)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/ipv6/raw.c:raw6_icmp_error
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/icmp.c (c0e305b8)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (c0e34254)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_timer_handler
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:inet6_mc_check
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
```
```
In net/ipv6/reassembly.c (c0e37c70)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ip6_frag_expire
  - net/ipv6/reassembly.c:ip6_frag_expire
```
```
In net/ipv6/tcp_ipv6.c (c0e3c3d4)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ipv6/datagram.c (c0e40b40)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/ipv6/ip6_flowlabel.c (c0e41f84)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6_fl_gc
```
```
In net/ipv6/ip6mr.c (c0e49b20)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:ip6mr_ioctl
  - net/ipv6/ip6mr.c:ip6mr_ioctl
  - net/ipv6/ip6mr.c:reg_vif_xmit
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/ip6mr.c:ip6mr_vif_seq_stop
```
```
In net/ipv6/xfrm6_input.c (c0e4a420)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_input_addr
  - net/ipv6/xfrm6_input.c:xfrm6_input_addr
  - net/ipv6/xfrm6_input.c:xfrm6_input_addr
```
```
In net/ipv6/calipso.c (c0e4e2b4)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_doi_remove
  - net/ipv6/calipso.c:calipso_doi_remove
  - net/ipv6/calipso.c:calipso_doi_remove
  - net/ipv6/calipso.c:calipso_doi_add
  - net/ipv6/calipso.c:calipso_doi_add
```
```
In net/ipv6/inet6_hashtables.c (c0e56680)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
```
In net/packet/af_packet.c (c0e5bd8c)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:__fanout_set_data_bpf
  - net/packet/af_packet.c:__fanout_link
  - net/packet/af_packet.c:prb_retire_rx_blk_timer_expired
```
```
In net/netlabel/netlabel_domainhash.c (c0e64268)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_init
```
```
In net/netlabel/netlabel_unlabeled.c (c15baa3c)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_init
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_netdev_handler
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
```
In net/rfkill/input.c (c0e6b734)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - net/rfkill/input.c:rfkill_start
  - net/rfkill/input.c:rfkill_op_handler
  - net/rfkill/input.c:rfkill_op_handler
  - net/rfkill/input.c:rfkill_op_handler
```
```
In lib/dec_and_lock.c (c0e7fc68)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
```
```
In lib/klist.c (c0e84818)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - lib/klist.c:klist_remove
  - lib/klist.c:klist_put
  - lib/klist.c:klist_release
  - lib/klist.c:klist_add_before
  - lib/klist.c:klist_add_behind
  - lib/klist.c:klist_add_tail
  - lib/klist.c:klist_add_head
```
```
In lib/kobject.c (c0e84dec)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - lib/kobject.c:kobj_ns_drop
  - lib/kobject.c:kobj_ns_initial
  - lib/kobject.c:kobj_ns_netlink
  - lib/kobject.c:kobj_ns_grab_current
  - lib/kobject.c:kobj_ns_current_may_mount
  - lib/kobject.c:kobj_ns_type_registered
  - lib/kobject.c:kobj_ns_type_register
  - lib/kobject.c:kset_find_obj
  - lib/kobject.c:kobject_add_internal
  - lib/kobject.c:kobj_kset_leave
```
```
In lib/xarray.c (c0e96efc)
Location: arch/arm/include/asm/spinlock.h:41
Inline: True
Inline callers:
  - lib/xarray.c:xa_clear_mark
  - lib/xarray.c:xa_set_mark
  - lib/xarray.c:xa_store
  - lib/xarray.c:xa_erase
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
