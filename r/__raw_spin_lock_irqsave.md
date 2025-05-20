# Function: <code>__raw_spin_lock_irqsave</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff818242ea)
Location: include/linux/spinlock_api_smp.h:106
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_spin_lock_irqsave
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff8189ef9a)
Location: include/linux/spinlock_api_smp.h:106
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_spin_lock_irqsave
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff818d445a)
Location: include/linux/spinlock_api_smp.h:106
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_spin_lock_irqsave
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff8190b5ca)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_spin_lock_irqsave
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff8199573a)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_spin_lock_irqsave
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff819f1c75)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_spin_lock_irqsave
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff81a2d2a5)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_spin_lock_irqsave
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff81a9d585)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_spin_lock_irqsave
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff81ad4d65)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_spin_lock_irqsave
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff81bccb05)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_spin_lock_irqsave
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff81c45665)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_spin_lock_irqsave
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff81c388f5)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_spin_lock_irqsave
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff81d571d5)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_spin_lock_irqsave
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long unsigned int __raw_spin_lock_irqsave(raw_spinlock_t *lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff8114ec40)
Location: include/linux/spinlock_api_smp.h:104
Inline: False
Direct callers:
  - kernel/locking/spinlock.c:_raw_spin_lock_irqsave
```
**Symbols:**

```
ffffffff8114ec40-ffffffff8114ecb2: __raw_spin_lock_irqsave (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long unsigned int __raw_spin_lock_irqsave(raw_spinlock_t *lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff8117de10)
Location: include/linux/spinlock_api_smp.h:104
Inline: False
Direct callers:
  - kernel/locking/spinlock.c:_raw_spin_lock_irqsave
```
**Symbols:**

```
ffffffff8117de10-ffffffff8117de88: __raw_spin_lock_irqsave (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long unsigned int __raw_spin_lock_irqsave(raw_spinlock_t *lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff8118eab0)
Location: include/linux/spinlock_api_smp.h:104
Inline: False
Direct callers:
  - kernel/locking/spinlock.c:_raw_spin_lock_irqsave
```
**Symbols:**

```
ffffffff8118eab0-ffffffff8118eb28: __raw_spin_lock_irqsave (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long unsigned int __raw_spin_lock_irqsave(raw_spinlock_t *lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff8119d460)
Location: include/linux/spinlock_api_smp.h:104
Inline: False
Direct callers:
  - kernel/locking/spinlock.c:_raw_spin_lock_irqsave
```
**Symbols:**

```
ffffffff8119d460-ffffffff8119d4d8: __raw_spin_lock_irqsave (STB_LOCAL)
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
In arch/arm64/kernel/traps.c (ffff800010094504)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - arch/arm64/kernel/traps.c:call_undef_hook
  - arch/arm64/kernel/traps.c:unregister_undef_hook
  - arch/arm64/kernel/traps.c:register_undef_hook
  - arch/arm64/kernel/traps.c:die
```
```
In arch/arm64/kernel/insn.c (ffff800010da75c8)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - arch/arm64/kernel/insn.c:__aarch64_insn_write
```
```
In arch/arm64/kernel/perf_event.c (ffff8000100a45fc)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - arch/arm64/kernel/perf_event.c:armv8pmu_stop
  - arch/arm64/kernel/perf_event.c:armv8pmu_start
  - arch/arm64/kernel/perf_event.c:armv8pmu_disable_event
  - arch/arm64/kernel/perf_event.c:armv8pmu_enable_event
```
```
In arch/arm64/kernel/armv8_deprecated.c (ffff8000114365d0)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - arch/arm64/kernel/armv8_deprecated.c:armv8_deprecated_init
  - arch/arm64/kernel/armv8_deprecated.c:register_insn_emulation
  - arch/arm64/kernel/armv8_deprecated.c:run_all_insn_set_hw_mode
```
```
In arch/arm64/mm/context.c (ffff8000100afacc)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - arch/arm64/mm/context.c:check_and_switch_context
```
```
In virt/kvm/eventfd.c (ffff8000100c0c84)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - virt/kvm/eventfd.c:irqfd_wakeup
```
```
In virt/kvm/arm/vgic/vgic.c (ffff8000100dd554)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - virt/kvm/arm/vgic/vgic.c:kvm_vgic_map_is_active
  - virt/kvm/arm/vgic/vgic.c:kvm_vgic_set_owner
  - virt/kvm/arm/vgic/vgic.c:kvm_vgic_unmap_phys_irq
  - virt/kvm/arm/vgic/vgic.c:kvm_vgic_reset_mapped_irq
  - virt/kvm/arm/vgic/vgic.c:kvm_vgic_map_phys_irq
  - virt/kvm/arm/vgic/vgic.c:kvm_vgic_inject_irq
  - virt/kvm/arm/vgic/vgic.c:vgic_queue_irq_unlock
  - virt/kvm/arm/vgic/vgic.c:vgic_queue_irq_unlock
  - virt/kvm/arm/vgic/vgic.c:vgic_flush_pending_lpis
```
```
In virt/kvm/arm/vgic/vgic-v3.c (ffff8000100dfaac)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - virt/kvm/arm/vgic/vgic-v3.c:vgic_v3_lpi_sync_pending_status
```
```
In virt/kvm/arm/vgic/vgic-mmio.c (ffff8000100e2490)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - virt/kvm/arm/vgic/vgic-mmio.c:vgic_write_irq_line_level_info
  - virt/kvm/arm/vgic/vgic-mmio.c:vgic_mmio_write_config
  - virt/kvm/arm/vgic/vgic-mmio.c:vgic_mmio_write_priority
  - virt/kvm/arm/vgic/vgic-mmio.c:vgic_mmio_write_cpending
  - virt/kvm/arm/vgic/vgic-mmio.c:vgic_mmio_write_spending
  - virt/kvm/arm/vgic/vgic-mmio.c:vgic_mmio_read_pending
  - virt/kvm/arm/vgic/vgic-mmio.c:vgic_mmio_write_cenable
  - virt/kvm/arm/vgic/vgic-mmio.c:vgic_mmio_write_senable
  - virt/kvm/arm/vgic/vgic-mmio.c:vgic_mmio_write_group
```
```
In virt/kvm/arm/vgic/vgic-mmio-v2.c (ffff8000100e35d4)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - virt/kvm/arm/vgic/vgic-mmio-v2.c:vgic_mmio_write_sgipends
  - virt/kvm/arm/vgic/vgic-mmio-v2.c:vgic_mmio_write_sgipendc
  - virt/kvm/arm/vgic/vgic-mmio-v2.c:vgic_mmio_write_target
  - virt/kvm/arm/vgic/vgic-mmio-v2.c:vgic_mmio_write_sgir
```
```
In virt/kvm/arm/vgic/vgic-mmio-v3.c (ffff8000100e4ed4)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - virt/kvm/arm/vgic/vgic-mmio-v3.c:vgic_v3_dispatch_sgi
  - virt/kvm/arm/vgic/vgic-mmio-v3.c:vgic_v3_uaccess_write_pending
  - virt/kvm/arm/vgic/vgic-mmio-v3.c:vgic_mmio_write_irouter
```
```
In virt/kvm/arm/vgic/vgic-its.c (ffff8000100eadc4)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - virt/kvm/arm/vgic/vgic-its.c:vgic_enable_lpis
  - virt/kvm/arm/vgic/vgic-its.c:vgic_its_inject_cached_translation
  - virt/kvm/arm/vgic/vgic-its.c:vgic_its_inject_cached_translation
  - virt/kvm/arm/vgic/vgic-its.c:vgic_its_trigger_msi
  - virt/kvm/arm/vgic/vgic-its.c:vgic_its_resolve_lpi
  - virt/kvm/arm/vgic/vgic-its.c:vgic_its_invalidate_cache
  - virt/kvm/arm/vgic/vgic-its.c:vgic_copy_lpi_list
  - virt/kvm/arm/vgic/vgic-its.c:update_lpi_config
```
```
In virt/kvm/arm/vgic/vgic-debug.c (ffff8000100eb694)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - virt/kvm/arm/vgic/vgic-debug.c:vgic_debug_show
```
```
In kernel/panic.c (ffff8000100f6220)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
```
```
In kernel/user.c (ffff80001010a2fc)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - kernel/user.c:find_user
```
```
In kernel/signal.c (ffff80001010f940)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
  - kernel/signal.c:sigqueue_free
  - kernel/signal.c:force_sigsegv
  - kernel/signal.c:__lock_task_sighand
  - kernel/signal.c:force_sig_info_to_task
  - kernel/signal.c:flush_itimer_signals
  - kernel/signal.c:flush_signals
```
```
In kernel/workqueue.c (ffff80001012221c)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - kernel/workqueue.c:show_workqueue_state
  - kernel/workqueue.c:show_workqueue_state
  - kernel/workqueue.c:work_busy
  - kernel/workqueue.c:pwq_adjust_max_active
```
```
In kernel/pid.c (ffff800010124418)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - kernel/pid.c:free_pid
```
```
In kernel/task_work.c (ffff80001012502c)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - kernel/task_work.c:task_work_cancel
```
```
In kernel/kthread.c (ffff800010128bf0)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - kernel/kthread.c:__kthread_cancel_work_sync
  - kernel/kthread.c:__kthread_cancel_work_sync
  - kernel/kthread.c:kthread_mod_delayed_work
  - kernel/kthread.c:__kthread_cancel_work
  - kernel/kthread.c:kthread_queue_delayed_work
  - kernel/kthread.c:kthread_delayed_work_timer_fn
  - kernel/kthread.c:kthread_queue_work
  - kernel/kthread.c:__kthread_parkme
```
```
In kernel/notifier.c (ffff80001012c1a8)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - kernel/notifier.c:atomic_notifier_chain_unregister
  - kernel/notifier.c:atomic_notifier_chain_register
```
```
In kernel/async.c (ffff80001012ea78)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - kernel/async.c:async_schedule_node_domain
  - kernel/async.c:async_schedule_node_domain
  - kernel/async.c:async_run_entry_fn
  - kernel/async.c:lowest_in_progress
```
```
In kernel/ucount.c (ffff80001013004c)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - kernel/ucount.c:put_ucounts
```
```
In kernel/sched/core.c (ffff80001013de84)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_offline_group
  - kernel/sched/core.c:sched_online_group
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_activate
  - kernel/sched/core.c:init_idle
  - kernel/sched/core.c:sched_getaffinity
  - kernel/sched/core.c:do_task_dead
  - kernel/sched/core.c:sched_exec
  - kernel/sched/core.c:__balance_callback
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:sched_fork
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:wake_up_if_idle
  - kernel/sched/core.c:sched_ttwu_pending
  - kernel/sched/core.c:resched_cpu
  - kernel/sched/core.c:task_rq_lock
```
```
In kernel/sched/cputime.c (ffff80001013f49c)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - kernel/sched/cputime.c:cputime_adjust
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In kernel/sched/fair.c (ffff80001014d61c)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:unregister_fair_sched_group
  - kernel/sched/fair.c:_nohz_idle_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/fair.c:sched_cfs_slack_timer
  - kernel/sched/fair.c:sched_cfs_slack_timer
  - kernel/sched/fair.c:distribute_cfs_runtime
  - kernel/sched/fair.c:remove_entity_load_avg
  - kernel/sched/fair.c:task_numa_free
```
```
In kernel/sched/deadline.c (ffff8000101578e0)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_cpu_busy
  - kernel/sched/deadline.c:dl_cpuset_cpumask_can_shrink
  - kernel/sched/deadline.c:dl_task_can_attach
  - kernel/sched/deadline.c:sched_dl_do_global
  - kernel/sched/deadline.c:sched_dl_global_validate
  - kernel/sched/deadline.c:dl_clear_root_domain
```
```
In kernel/sched/wait.c (ffff800010158c88)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - kernel/sched/wait.c:finish_wait
  - kernel/sched/wait.c:prepare_to_wait_event
  - kernel/sched/wait.c:prepare_to_wait_exclusive
  - kernel/sched/wait.c:prepare_to_wait
  - kernel/sched/wait.c:__wake_up_common_lock
  - kernel/sched/wait.c:remove_wait_queue
  - kernel/sched/wait.c:add_wait_queue_exclusive
  - kernel/sched/wait.c:add_wait_queue
```
```
In kernel/sched/swait.c (ffff800010159818)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - kernel/sched/swait.c:finish_swait
  - kernel/sched/swait.c:prepare_to_swait_event
  - kernel/sched/swait.c:prepare_to_swait_exclusive
  - kernel/sched/swait.c:swake_up_one
```
```
In kernel/sched/completion.c (ffff8000101599d4)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - kernel/sched/completion.c:complete_all
  - kernel/sched/completion.c:complete
```
```
In kernel/sched/cpudeadline.c (ffff80001015a684)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_set
  - kernel/sched/cpudeadline.c:cpudl_clear
```
```
In kernel/sched/topology.c (ffff80001015b218)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - kernel/sched/topology.c:rq_attach_root
```
```
In kernel/sched/debug.c (ffff800010161560)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cfs_rq
```
```
In kernel/sched/cpufreq_schedutil.c (ffff8000101653f4)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_work
```
```
In kernel/locking/semaphore.c (ffff800010168960)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - kernel/locking/semaphore.c:up
  - kernel/locking/semaphore.c:down_timeout
  - kernel/locking/semaphore.c:down_trylock
  - kernel/locking/semaphore.c:down_killable
  - kernel/locking/semaphore.c:down_interruptible
  - kernel/locking/semaphore.c:down
```
```
In kernel/locking/rwsem.c (ffff8000101696e4)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:downgrade_write
```
```
In kernel/locking/rtmutex.c (ffff800010da602c)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_futex_unlock
  - kernel/locking/rtmutex.c:rt_mutex_trylock
  - kernel/locking/rtmutex.c:rt_mutex_futex_trylock
  - kernel/locking/rtmutex.c:rt_mutex_slowunlock
  - kernel/locking/rtmutex.c:rt_mutex_slowunlock
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
  - kernel/locking/rtmutex.c:rt_mutex_adjust_pi
```
```
In kernel/power/qos.c (ffff80001016cd70)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_power_read
  - kernel/power/qos.c:pm_qos_update_flags
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/qos.c:pm_qos_debug_show
```
```
In kernel/power/suspend.c (ffff8000101704e4)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - kernel/power/suspend.c:s2idle_wake
```
```
In kernel/printk/printk.c (ffff80001017308c)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - kernel/printk/printk.c:kmsg_dump_unregister
  - kernel/printk/printk.c:kmsg_dump_register
```
```
In kernel/printk/printk_safe.c (ffff800010176960)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:__printk_safe_flush
```
```
In kernel/irq/irqdesc.c (ffff800010177dd4)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:__irq_get_desc_lock
```
```
In kernel/irq/manage.c (ffff80001017c618)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - kernel/irq/manage.c:request_percpu_nmi
  - kernel/irq/manage.c:__free_percpu_irq
  - kernel/irq/manage.c:request_nmi
  - kernel/irq/manage.c:free_nmi
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:irq_wake_thread
  - kernel/irq/manage.c:irq_set_affinity_notifier
  - kernel/irq/manage.c:irq_affinity_notify
  - kernel/irq/manage.c:__irq_set_affinity
  - kernel/irq/manage.c:__synchronize_hardirq
```
```
In kernel/irq/spurious.c (ffff80001017d3d4)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - kernel/irq/spurious.c:__report_bad_irq
```
```
In kernel/irq/chip.c (ffff80001017fee8)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_cpu_offline
  - kernel/irq/chip.c:irq_cpu_online
```
```
In kernel/irq/generic-chip.c (ffff8000101815a8)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_map_generic_chip
  - kernel/irq/generic-chip.c:__irq_alloc_domain_generic_chips
```
```
In kernel/irq/proc.c (ffff800010185f7c)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - kernel/irq/proc.c:show_interrupts
  - kernel/irq/proc.c:register_handler_proc
  - kernel/irq/proc.c:irq_affinity_hint_proc_show
```
```
In kernel/irq/pm.c (ffff80001018673c)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - kernel/irq/pm.c:resume_irqs
  - kernel/irq/pm.c:suspend_device_irqs
```
```
In kernel/rcu/update.c (ffff800010188c00)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/rcu/sync.c (ffff800010189200)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - kernel/rcu/sync.c:rcu_sync_func
```
```
In kernel/rcu/srcutree.c (ffff80001018ae8c)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:__call_srcu
  - kernel/rcu/srcutree.c:__call_srcu
```
```
In kernel/rcu/tree.c (ffff80001018faf8)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - kernel/rcu/tree.c:sync_rcu_exp_select_cpus
  - kernel/rcu/tree.c:sync_rcu_exp_select_cpus
  - kernel/rcu/tree.c:sync_rcu_exp_select_cpus
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:rcu_report_exp_cpu_mult
  - kernel/rcu/tree.c:sync_rcu_preempt_exp_done_unlocked
  - kernel/rcu/tree.c:rcu_dump_cpu_stacks
  - kernel/rcu/tree.c:rcu_spawn_gp_kthread
  - kernel/rcu/tree.c:rcu_report_dead
  - kernel/rcu/tree.c:rcu_report_dead
  - kernel/rcu/tree.c:rcu_cpu_starting
  - kernel/rcu/tree.c:rcutree_offline_cpu
  - kernel/rcu/tree.c:rcutree_online_cpu
  - kernel/rcu/tree.c:rcutree_prepare_cpu
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_force_quiescent_state
  - kernel/rcu/tree.c:force_qs_rnp
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_report_qs_rnp
  - kernel/rcu/tree.c:rcu_gp_kthread
```
```
In kernel/dma/coherent.c (ffff8000101959c8)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - kernel/dma/coherent.c:__dma_release_from_coherent
  - kernel/dma/coherent.c:__dma_alloc_from_coherent
```
```
In kernel/dma/swiotlb.c (ffff800010196c54)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_tbl_unmap_single
  - kernel/dma/swiotlb.c:swiotlb_tbl_map_single
```
```
In kernel/freezer.c (ffff80001019849c)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - kernel/freezer.c:__thaw_task
  - kernel/freezer.c:freeze_task
```
```
In kernel/time/timer.c (ffff80001019ceec)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - kernel/time/timer.c:lock_timer_base
```
```
In kernel/time/hrtimer.c (ffff8000101a21e4)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_run_softirq
  - kernel/time/hrtimer.c:hrtimer_next_event_without
  - kernel/time/hrtimer.c:hrtimer_get_next_event
  - kernel/time/hrtimer.c:lock_hrtimer_base
```
```
In kernel/time/timekeeping.c (ffff8000101a568c)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:timekeeping_inject_sleeptime64
  - kernel/time/timekeeping.c:timekeeping_init
  - kernel/time/timekeeping.c:change_clocksource
  - kernel/time/timekeeping.c:timekeeping_inject_offset
  - kernel/time/timekeeping.c:pvclock_gtod_unregister_notifier
  - kernel/time/timekeeping.c:pvclock_gtod_register_notifier
```
```
In kernel/time/timer_list.c (ffff8000101a7ba8)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - kernel/time/timer_list.c:print_active_timers
```
```
In kernel/time/alarmtimer.c (ffff8000101a996c)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
  - kernel/time/alarmtimer.c:alarm_handle_timer
  - kernel/time/alarmtimer.c:alarm_try_to_cancel
  - kernel/time/alarmtimer.c:alarm_restart
  - kernel/time/alarmtimer.c:alarm_start
  - kernel/time/alarmtimer.c:alarmtimer_suspend
  - kernel/time/alarmtimer.c:alarmtimer_suspend
  - kernel/time/alarmtimer.c:alarmtimer_fired
  - kernel/time/alarmtimer.c:alarmtimer_fired
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
  - kernel/time/alarmtimer.c:alarmtimer_get_rtcdev
```
```
In kernel/time/posix-timers.c (ffff8000101ab998)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__lock_timer
  - kernel/time/posix-timers.c:release_posix_timer
  - kernel/time/posix-timers.c:posix_timer_fn
```
```
In kernel/time/clockevents.c (ffff8000101b1354)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - kernel/time/clockevents.c:tick_cleanup_dead_cpu
  - kernel/time/clockevents.c:clockevents_register_device
```
```
In kernel/time/tick-broadcast.c (ffff8000101b3d6c)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:hotplug_cpu__broadcast_tick_pull
  - kernel/time/tick-broadcast.c:tick_broadcast_switch_to_oneshot
  - kernel/time/tick-broadcast.c:tick_resume_broadcast
  - kernel/time/tick-broadcast.c:tick_suspend_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
```
```
In kernel/cgroup/cgroup.c (ffff8000101d88a8)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_free
  - kernel/cgroup/cgroup.c:cgroup_rmdir
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:css_task_iter_end
  - kernel/cgroup/cgroup.c:cgroup_file_notify
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_update_populated
```
```
In kernel/cgroup/rstat.c (ffff8000101d9a14)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_irqsafe
  - kernel/cgroup/rstat.c:cgroup_rstat_updated
```
```
In kernel/cgroup/namespace.c (ffff8000101da448)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/cgroup/namespace.c:free_cgroup_ns
```
```
In kernel/cgroup/cgroup-v1.c (ffff8000101db720)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
```
In kernel/cgroup/freezer.c (ffff8000101ddaf4)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_freeze
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/freezer.c:cgroup_update_frozen
  - kernel/cgroup/freezer.c:cgroup_update_frozen
  - kernel/cgroup/freezer.c:cgroup_update_frozen
```
```
In kernel/cgroup/cpuset.c (ffff8000101e4700)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:__cpuset_node_allowed
  - kernel/cgroup/cpuset.c:cpuset_mems_allowed
  - kernel/cgroup/cpuset.c:cpuset_cpus_allowed
```
```
In kernel/stop_machine.c (ffff8000101e8130)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stop_should_run
  - kernel/stop_machine.c:cpu_stop_queue_work
```
```
In kernel/audit.c (ffff8000101e9b00)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_end
  - kernel/audit.c:audit_get_tty
  - kernel/audit.c:audit_receive_msg
```
```
In kernel/kprobes.c (ffff8000101f8438)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - kernel/kprobes.c:pre_handler_kretprobe
  - kernel/kprobes.c:pre_handler_kretprobe
  - kernel/kprobes.c:pre_handler_kretprobe
  - kernel/kprobes.c:cleanup_rp_inst
  - kernel/kprobes.c:kprobe_flush_task
  - kernel/kprobes.c:kretprobe_hash_lock
```
```
In kernel/delayacct.c (ffff80001020cc34)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - kernel/delayacct.c:__delayacct_blkio_ticks
  - kernel/delayacct.c:__delayacct_add_tsk
  - kernel/delayacct.c:delayacct_end
```
```
In kernel/taskstats.c (ffff80001020d9b4)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
```
```
In kernel/trace/ring_buffer.c (ffff800010218de4)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_read
  - kernel/trace/ring_buffer.c:ring_buffer_read_finish
  - kernel/trace/ring_buffer.c:ring_buffer_iter_peek
  - kernel/trace/ring_buffer.c:ring_buffer_wait
```
```
In kernel/trace/trace.c (ffff800010223658)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_release
  - kernel/trace/trace.c:__tracing_open
  - kernel/trace/trace.c:trace_event_buffer_commit
  - kernel/trace/trace.c:tracing_stop
```
```
In kernel/trace/blktrace.c (ffff8000102372d8)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:__blk_add_trace
```
```
In kernel/bpf/syscall.c (ffff800010262a60)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_map_free_id
```
```
In kernel/bpf/hashtab.c (ffff800010279088)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_lru_map_delete_elem
  - kernel/bpf/hashtab.c:htab_map_delete_elem
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:__htab_percpu_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_delete_node
```
```
In kernel/bpf/bpf_lru_list.c (ffff80001027cec0)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_push_free
  - kernel/bpf/bpf_lru_list.c:bpf_lru_push_free
  - kernel/bpf/bpf_lru_list.c:bpf_lru_push_free
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
```
```
In kernel/bpf/lpm_trie.c (ffff80001027dee8)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - kernel/bpf/lpm_trie.c:trie_delete_elem
  - kernel/bpf/lpm_trie.c:trie_update_elem
```
```
In kernel/bpf/queue_stack_maps.c (ffff80001027f8c8)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - kernel/bpf/queue_stack_maps.c:queue_stack_map_push_elem
  - kernel/bpf/queue_stack_maps.c:__stack_map_get
  - kernel/bpf/queue_stack_maps.c:__queue_map_get
```
```
In kernel/bpf/btf.c (ffff800010283aa8)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
```
```
In kernel/bpf/devmap.c (ffff8000102871dc)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_notification
  - kernel/bpf/devmap.c:dev_map_hash_update_elem
  - kernel/bpf/devmap.c:dev_map_hash_delete_elem
```
```
In kernel/events/core.c (ffff8000102a1434)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init_task
  - kernel/events/core.c:perf_event_init_task
  - kernel/events/core.c:perf_event_addr_filters_apply
  - kernel/events/core.c:perf_addr_filters_splice
  - kernel/events/core.c:perf_event_mmap
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:ring_buffer_attach
  - kernel/events/core.c:ring_buffer_attach
  - kernel/events/core.c:__perf_read_group_add
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:perf_unpin_context
  - kernel/events/core.c:perf_mux_hrtimer_restart
```
```
In mm/filemap.c (ffff8000102aef60)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - mm/filemap.c:add_page_wait_queue
  - mm/filemap.c:wake_up_page_bit
  - mm/filemap.c:wake_up_page_bit
  - mm/filemap.c:replace_page_cache_page
  - mm/filemap.c:delete_from_page_cache_batch
```
```
In mm/mempool.c (ffff8000102b57ec)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - mm/mempool.c:mempool_free
  - mm/mempool.c:mempool_alloc
  - mm/mempool.c:mempool_resize
  - mm/mempool.c:mempool_resize
  - mm/mempool.c:mempool_resize
  - mm/mempool.c:mempool_resize
```
```
In mm/page-writeback.c (ffff8000102bc020)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:__cancel_dirty_page
  - mm/page-writeback.c:account_page_redirty
```
```
In mm/swap.c (ffff8000102c17fc)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:pagevec_lru_move_fn
  - mm/swap.c:__page_cache_release
```
```
In mm/truncate.c (ffff8000102c3fec)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
```
```
In mm/vmscan.c (ffff8000102ce058)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:__remove_mapping
```
```
In mm/shmem.c (ffff8000102d6b00)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_charge
```
```
In mm/vmstat.c (ffff8000102da74c)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
```
```
In mm/backing-dev.c (ffff8000102df470)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_congested_get_create
```
```
In mm/percpu.c (ffff8000102e3860)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc
```
```
In mm/slab_common.c (ffff8000102e570c)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - mm/slab_common.c:kmemcg_cache_shutdown
```
```
In mm/compaction.c (ffff8000102ec65c)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - mm/compaction.c:compact_zone
  - mm/compaction.c:fast_isolate_freepages
```
```
In mm/page_alloc.c (ffff80001031ac18)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - mm/page_alloc.c:set_hwpoison_free_buddy_page
  - mm/page_alloc.c:is_free_buddy_page
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:unreserve_highatomic_pageblock
```
```
In mm/shuffle.c (ffff800010da04e8)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - mm/shuffle.c:__shuffle_zone
  - mm/shuffle.c:__shuffle_zone
```
```
In mm/dmapool.c (ffff80001032d150)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - mm/dmapool.c:dma_pool_free
  - mm/dmapool.c:dma_pool_alloc
  - mm/dmapool.c:dma_pool_alloc
```
```
In mm/hugetlb.c (ffff80001032e61c)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_gigantic_page
  - mm/hugetlb.c:alloc_gigantic_page
```
```
In mm/slub.c (ffff8000103496bc)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - mm/slub.c:validate_store
  - mm/slub.c:list_locations
  - mm/slub.c:__kmem_cache_shrink
  - mm/slub.c:__slab_free
  - mm/slub.c:count_partial
  - mm/slub.c:free_debug_processing
```
```
In mm/memory_hotplug.c (ffff800010d9d050)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:move_pfn_range_to_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
```
```
In mm/huge_memory.c (ffff800010359ab8)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:deferred_split_huge_page
  - mm/huge_memory.c:free_transhuge_page
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/memcontrol.c (ffff80001036714c)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_css_free
```
```
In mm/swap_cgroup.c (ffff80001036cc2c)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - mm/swap_cgroup.c:swap_cgroup_record
  - mm/swap_cgroup.c:swap_cgroup_cmpxchg
```
```
In mm/memory-failure.c (ffff800010370918)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure_work_func
  - mm/memory-failure.c:memory_failure_queue
```
```
In mm/page_isolation.c (ffff800010372068)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:unset_migratetype_isolate
```
```
In mm/balloon_compaction.c (ffff800010377680)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_putback
  - mm/balloon_compaction.c:balloon_page_isolate
  - mm/balloon_compaction.c:balloon_page_enqueue
  - mm/balloon_compaction.c:balloon_page_list_dequeue
  - mm/balloon_compaction.c:balloon_page_list_enqueue
```
```
In mm/hmm.c (ffff80001037afe8)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - mm/hmm.c:hmm_range_unregister
  - mm/hmm.c:hmm_range_register
  - mm/hmm.c:hmm_invalidate_range_start
  - mm/hmm.c:notifiers_decrement
```
```
In fs/fs-writeback.c (ffff8000103caeb0)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - fs/fs-writeback.c:sb_clear_inode_writeback
  - fs/fs-writeback.c:sb_mark_inode_writeback
```
```
In fs/buffer.c (ffff8000103d81e0)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - fs/buffer.c:__set_page_dirty
```
```
In fs/direct-io.c (ffff8000103e54c4)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:dio_bio_end_io
  - fs/direct-io.c:dio_bio_end_aio
```
```
In fs/eventpoll.c (ffff8000103f1034)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
```
```
In fs/timerfd.c (ffff8000103f4824)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - fs/timerfd.c:timerfd_poll
  - fs/timerfd.c:timerfd_clock_was_set
  - fs/timerfd.c:timerfd_triggered
```
```
In fs/eventfd.c (ffff8000103f6008)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_ctx_remove_wait_queue
  - fs/eventfd.c:eventfd_signal
```
```
In fs/aio.c (ffff8000103fd33c)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - fs/aio.c:aio_complete_rw
  - fs/aio.c:aio_complete
  - fs/aio.c:kiocb_set_cancel_fn
  - fs/aio.c:aio_migratepage
```
```
In fs/io_uring.c (ffff800010401b10)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - fs/io_uring.c:io_timeout_fn
  - fs/io_uring.c:io_cqring_add_event
```
```
In fs/crypto/crypto.c (ffff80001040ab74)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
```
```
In fs/kernfs/dir.c (ffff800010452eac)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_get_parent
  - fs/kernfs/dir.c:pr_cont_kernfs_path
  - fs/kernfs/dir.c:pr_cont_kernfs_name
  - fs/kernfs/dir.c:kernfs_path_from_node
  - fs/kernfs/dir.c:kernfs_name
```
```
In fs/kernfs/file.c (ffff800010455270)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_notify
  - fs/kernfs/file.c:kernfs_notify
```
```
In fs/ext4/page-io.c (ffff8000104a36dc)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
```
```
In fs/pstore/inode.c (ffff80001051a44c)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - fs/pstore/inode.c:pstore_mkfile
  - fs/pstore/inode.c:pstore_mkfile
  - fs/pstore/inode.c:pstore_evict_inode
```
```
In security/selinux/avc.c (ffff800010546ef4)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_compute_av
  - security/selinux/avc.c:avc_compute_av
  - security/selinux/avc.c:avc_ss_reset
  - security/selinux/avc.c:avc_flush
```
```
In security/selinux/ibpkey.c (ffff800010558eac)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - security/selinux/ibpkey.c:sel_ib_pkey_flush
  - security/selinux/ibpkey.c:sel_ib_pkey_sid
```
```
In security/selinux/ss/sidtab.c (ffff80001055b2b8)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_convert
  - security/selinux/ss/sidtab.c:sidtab_convert
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
```
```
In block/bio.c (ffff8000105dd794)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - block/bio.c:bio_check_pages_dirty
```
```
In block/blk-flush.c (ffff8000105e6f10)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:flush_end_io
```
```
In block/blk-ioc.c (ffff8000105e8c34)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_clear_queue
  - block/blk-ioc.c:ioc_release_fn
  - block/blk-ioc.c:ioc_release_fn
```
```
In block/blk-mq.c (ffff8000105efefc)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
```
```
In block/genhd.c (ffff8000105fa53c)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - block/genhd.c:__disk_unblock_events
  - block/genhd.c:disk_block_events
```
```
In block/badblocks.c (ffff8000105fe7ac)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_set
```
```
In block/blk-cgroup.c (ffff80001060de64)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_lookup_create
```
```
In block/blk-iocost.c (ffff800010615ad0)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_pd_init
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:iocg_waitq_timer_fn
```
```
In block/mq-deadline.c (ffff80001061992c)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_finish_request
  - block/mq-deadline.c:deadline_next_request
```
```
In lib/percpu-refcount.c (ffff8000106355d8)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_resurrect
  - lib/percpu-refcount.c:percpu_ref_kill_and_confirm
  - lib/percpu-refcount.c:percpu_ref_switch_to_percpu
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic
```
```
In lib/once.c (ffff8000106375f8)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - lib/once.c:__do_once_start
```
```
In lib/refcount.c (ffff8000106379d4)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
```
```
In lib/percpu_counter.c (ffff80001065ef38)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - lib/percpu_counter.c:__percpu_counter_init
  - lib/percpu_counter.c:__percpu_counter_sum
  - lib/percpu_counter.c:percpu_counter_add_batch
  - lib/percpu_counter.c:percpu_counter_set
```
```
In lib/sbitmap.c (ffff800010669c24)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
```
```
In drivers/irqchip/irq-gic-common.c (ffff80001066cf1c)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-common.c:gic_configure_irq
```
```
In drivers/irqchip/irq-gic-v3-its.c (ffff800010673e44)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3-its.c:its_vpe_irq_domain_free
  - drivers/irqchip/irq-gic-v3-its.c:its_vpe_send_cmd
  - drivers/irqchip/irq-gic-v3-its.c:its_vpe_set_affinity
  - drivers/irqchip/irq-gic-v3-its.c:its_vpe_set_affinity
  - drivers/irqchip/irq-gic-v3-its.c:its_irq_domain_free
  - drivers/irqchip/irq-gic-v3-its.c:its_msi_prepare
  - drivers/irqchip/irq-gic-v3-its.c:its_create_device
  - drivers/irqchip/irq-gic-v3-its.c:its_send_single_vcommand
  - drivers/irqchip/irq-gic-v3-its.c:its_send_single_command
```
```
In drivers/irqchip/irq-bcm7038-l1.c (ffff800010676dfc)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/irqchip/irq-bcm7038-l1.c:bcm7038_l1_set_affinity
  - drivers/irqchip/irq-bcm7038-l1.c:bcm7038_l1_mask
  - drivers/irqchip/irq-bcm7038-l1.c:bcm7038_l1_unmask
  - drivers/irqchip/irq-bcm7038-l1.c:bcm7038_l1_irq_handle
```
```
In drivers/irqchip/irq-brcmstb-l2.c (ffff800010677520)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/irqchip/irq-brcmstb-l2.c:brcmstb_l2_intc_resume
  - drivers/irqchip/irq-brcmstb-l2.c:brcmstb_l2_intc_suspend
```
```
In drivers/irqchip/irq-mtk-sysirq.c (ffff800010677d2c)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/irqchip/irq-mtk-sysirq.c:mtk_sysirq_set_type
```
```
In drivers/irqchip/irq-imx-gpcv2.c (ffff8000106787d0)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/irqchip/irq-imx-gpcv2.c:imx_gpcv2_irq_set_wake
```
```
In drivers/irqchip/irq-mvebu-sei.c (ffff80001067ae10)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/irqchip/irq-mvebu-sei.c:mvebu_sei_unmask_irq
  - drivers/irqchip/irq-mvebu-sei.c:mvebu_sei_mask_irq
```
```
In drivers/irqchip/irq-imx-irqsteer.c (ffff80001067db9c)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/irqchip/irq-imx-irqsteer.c:imx_irqsteer_irq_mask
  - drivers/irqchip/irq-imx-irqsteer.c:imx_irqsteer_irq_unmask
```
```
In drivers/bus/hisi_lpc.c (ffff80001067f87c)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/bus/hisi_lpc.c:hisi_lpc_target_out
  - drivers/bus/hisi_lpc.c:hisi_lpc_target_in
```
```
In drivers/bus/fsl-mc/mc-sys.c (ffff80001068132c)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/bus/fsl-mc/mc-sys.c:mc_send_command
```
```
In drivers/pinctrl/pinctrl-amd.c (ffff800010693e64)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_pinconf_set
  - drivers/pinctrl/pinctrl-amd.c:amd_pinconf_get
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_handler
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_handler
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_handler
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_eoi
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_unmask
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_mask
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_disable
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_enable
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_dbg_show
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_set_config
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_set_value
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_get_value
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_direction_output
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_direction_input
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_get_direction
```
```
In drivers/pinctrl/pinctrl-rockchip.c (ffff80001069b228)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_irq_set_type
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_irq_set_type
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_irq_demux
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_gpio_set_config
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_gpio_set
  - drivers/pinctrl/pinctrl-rockchip.c:_rockchip_pmx_gpio_set_direction
```
```
In drivers/pinctrl/pinctrl-single.c (ffff80001069d28c)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-single.c:pcs_set_mux
```
```
In drivers/pinctrl/actions/pinctrl-owl.c (ffff8000106a1de4)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_irq_ack
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_irq_unmask
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_irq_mask
  - drivers/pinctrl/actions/pinctrl-owl.c:irq_set_type
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_direction_output
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_direction_input
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_set
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_get
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_free
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_request
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_group_config_set
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_pin_config_set
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_set_mux
```
```
In drivers/pinctrl/bcm/pinctrl-bcm2835.c (ffff8000106a3ee8)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/pinctrl/bcm/pinctrl-bcm2835.c:bcm2835_gpio_irq_set_type
  - drivers/pinctrl/bcm/pinctrl-bcm2835.c:bcm2835_gpio_irq_disable
  - drivers/pinctrl/bcm/pinctrl-bcm2835.c:bcm2835_gpio_irq_enable
```
```
In drivers/pinctrl/bcm/pinctrl-iproc-gpio.c (ffff8000106a60f8)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_pin_config_set
  - drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_pin_config_get
  - drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_gpio_get_pull
  - drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_gpio_set_pull
  - drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_gpio_set
  - drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_gpio_direction_output
  - drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_gpio_direction_input
  - drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_gpio_irq_set_type
  - drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_gpio_irq_unmask
  - drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_gpio_irq_mask
```
```
In drivers/pinctrl/bcm/pinctrl-ns2-mux.c (ffff8000106a73f8)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/pinctrl/bcm/pinctrl-ns2-mux.c:ns2_pin_config_get
  - drivers/pinctrl/bcm/pinctrl-ns2-mux.c:ns2_pin_config_get
  - drivers/pinctrl/bcm/pinctrl-ns2-mux.c:ns2_pin_config_get
  - drivers/pinctrl/bcm/pinctrl-ns2-mux.c:ns2_pin_get_pull
  - drivers/pinctrl/bcm/pinctrl-ns2-mux.c:ns2_pin_set_pull
  - drivers/pinctrl/bcm/pinctrl-ns2-mux.c:ns2_pinmux_enable
```
```
In drivers/pinctrl/mvebu/pinctrl-armada-37xx.c (ffff8000106ac304)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:armada_37xx_irq_handler
  - drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:armada_37xx_irq_handler
  - drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:armada_37xx_irq_handler
  - drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:armada_37xx_irq_set_type
  - drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:armada_37xx_irq_set_wake
  - drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:armada_37xx_irq_unmask
  - drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:armada_37xx_irq_mask
  - drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:armada_37xx_irq_ack
```
```
In drivers/pinctrl/qcom/pinctrl-msm.c (ffff8000106add2c)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_irq_set_wake
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_irq_set_type
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_irq_ack
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_irq_clear_unmask
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_irq_mask
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_set
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_direction_output
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_direction_input
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_config_group_set
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_config_group_set
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_pinmux_set_mux
```
```
In drivers/pinctrl/sh-pfc/pinctrl.c (ffff8000106b13e0)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/pinctrl/sh-pfc/pinctrl.c:sh_pfc_pinconf_set
  - drivers/pinctrl/sh-pfc/pinctrl.c:sh_pfc_pinconf_set
  - drivers/pinctrl/sh-pfc/pinctrl.c:sh_pfc_pinconf_set
  - drivers/pinctrl/sh-pfc/pinctrl.c:sh_pfc_pinconf_get
  - drivers/pinctrl/sh-pfc/pinctrl.c:sh_pfc_pinconf_get
  - drivers/pinctrl/sh-pfc/pinctrl.c:sh_pfc_pinconf_get
  - drivers/pinctrl/sh-pfc/pinctrl.c:sh_pfc_gpio_set_direction
  - drivers/pinctrl/sh-pfc/pinctrl.c:sh_pfc_gpio_disable_free
  - drivers/pinctrl/sh-pfc/pinctrl.c:sh_pfc_gpio_request_enable
  - drivers/pinctrl/sh-pfc/pinctrl.c:sh_pfc_func_set_mux
```
```
In drivers/pinctrl/sunxi/pinctrl-sunxi.c (ffff8000106b5690)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pinctrl_irq_unmask
  - drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pinctrl_irq_mask
  - drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pinctrl_irq_set_type
  - drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pinctrl_gpio_set
  - drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pmx_request
  - drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pmx_set
  - drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pconf_set
```
```
In drivers/gpio/gpiolib.c (ffff8000106bff68)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiolib_seq_next
  - drivers/gpio/gpiolib.c:gpiolib_seq_start
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpiod_request_commit
  - drivers/gpio/gpiolib.c:gpiod_request_commit
  - drivers/gpio/gpiolib.c:gpiod_request_commit
  - drivers/gpio/gpiolib.c:gpiochip_find
  - drivers/gpio/gpiolib.c:gpiochip_remove
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
```
In drivers/gpio/gpiolib-sysfs.c (ffff8000114780c8)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:gpiolib_sysfs_init
  - drivers/gpio/gpiolib-sysfs.c:gpiolib_sysfs_init
  - drivers/gpio/gpiolib-sysfs.c:gpiod_export
```
```
In drivers/gpio/gpio-mmio.c (ffff8000106cd260)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/gpio/gpio-mmio.c:bgpio_dir_out
  - drivers/gpio/gpio-mmio.c:bgpio_dir_in
  - drivers/gpio/gpio-mmio.c:bgpio_set_multiple_single_reg
  - drivers/gpio/gpio-mmio.c:bgpio_set_set
  - drivers/gpio/gpio-mmio.c:bgpio_set
```
```
In drivers/gpio/gpio-davinci.c (ffff8000106ce4a8)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/gpio/gpio-davinci.c:davinci_direction_out
  - drivers/gpio/gpio-davinci.c:davinci_direction_in
```
```
In drivers/gpio/gpio-mpc8xxx.c (ffff8000106cf9a8)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/gpio/gpio-mpc8xxx.c:mpc512x_irq_set_type
  - drivers/gpio/gpio-mpc8xxx.c:mpc512x_irq_set_type
  - drivers/gpio/gpio-mpc8xxx.c:mpc512x_irq_set_type
  - drivers/gpio/gpio-mpc8xxx.c:mpc8xxx_irq_set_type
  - drivers/gpio/gpio-mpc8xxx.c:mpc8xxx_irq_set_type
  - drivers/gpio/gpio-mpc8xxx.c:mpc8xxx_irq_mask
  - drivers/gpio/gpio-mpc8xxx.c:mpc8xxx_irq_unmask
  - drivers/gpio/gpio-mpc8xxx.c:ls1028a_gpio_dir_in_init
```
```
In drivers/gpio/gpio-mvebu.c (ffff8000106d143c)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/gpio/gpio-mvebu.c:mvebu_pwm_apply
  - drivers/gpio/gpio-mvebu.c:mvebu_pwm_get_state
  - drivers/gpio/gpio-mvebu.c:mvebu_pwm_free
  - drivers/gpio/gpio-mvebu.c:mvebu_pwm_request
```
```
In drivers/gpio/gpio-pl061.c (ffff8000106d3b78)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/gpio/gpio-pl061.c:pl061_irq_type
  - drivers/gpio/gpio-pl061.c:pl061_direction_output
  - drivers/gpio/gpio-pl061.c:pl061_direction_input
```
```
In drivers/gpio/gpio-xgene.c (ffff8000106d6944)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/gpio/gpio-xgene.c:xgene_gpio_dir_out
  - drivers/gpio/gpio-xgene.c:xgene_gpio_dir_in
  - drivers/gpio/gpio-xgene.c:xgene_gpio_set
```
```
In drivers/gpio/gpio-xilinx.c (ffff8000106d7394)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/gpio/gpio-xilinx.c:xgpio_dir_out
  - drivers/gpio/gpio-xilinx.c:xgpio_dir_in
  - drivers/gpio/gpio-xilinx.c:xgpio_set_multiple
  - drivers/gpio/gpio-xilinx.c:xgpio_set_multiple
  - drivers/gpio/gpio-xilinx.c:xgpio_set
```
```
In drivers/pci/access.c (ffff8000106db8fc)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_cfg_access_unlock
  - drivers/pci/access.c:pci_cfg_access_trylock
  - drivers/pci/access.c:pci_bus_set_ops
  - drivers/pci/access.c:pci_bus_write_config_dword
  - drivers/pci/access.c:pci_bus_write_config_word
  - drivers/pci/access.c:pci_bus_write_config_byte
  - drivers/pci/access.c:pci_bus_read_config_dword
  - drivers/pci/access.c:pci_bus_read_config_word
  - drivers/pci/access.c:pci_bus_read_config_byte
```
```
In drivers/pci/pci.c (ffff8000106e578c)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
```
```
In drivers/pci/pcie/aer.c (ffff800010704820)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
```
```
In drivers/pci/pcie/pme.c (ffff800010705d3c)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_irq
```
```
In drivers/pci/endpoint/pci-epc-core.c (ffff80001071b4fc)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_linkup
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_add_epf
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_set_bar
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_set_msix
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_set_msi
```
```
In drivers/pci/controller/pcie-xilinx-nwl.c (ffff8000107244f0)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-xilinx-nwl.c:nwl_unmask_leg_irq
  - drivers/pci/controller/pcie-xilinx-nwl.c:nwl_mask_leg_irq
```
```
In drivers/pci/controller/pcie-mobiveil.c (ffff80001072c048)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-mobiveil.c:mobiveil_unmask_intx_irq
  - drivers/pci/controller/pcie-mobiveil.c:mobiveil_mask_intx_irq
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffff80001072e950)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_free
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_alloc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pci_bottom_unmask
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pci_bottom_mask
```
```
In drivers/pci/controller/dwc/pci-keystone.c (ffff800010732a4c)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_msi_unmask
  - drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_msi_mask
```
```
In drivers/rapidio/rio.c (ffff80001073c114)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_map_outb_region
  - drivers/rapidio/rio.c:rio_map_inb_region
```
```
In drivers/video/fbdev/mx3fb.c (ffff8000107609c4)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/video/fbdev/mx3fb.c:mx3fb_probe
  - drivers/video/fbdev/mx3fb.c:mx3fb_probe
  - drivers/video/fbdev/mx3fb.c:sdc_init_panel
  - drivers/video/fbdev/mx3fb.c:sdc_disable_channel
  - drivers/video/fbdev/mx3fb.c:sdc_enable_channel
```
```
In drivers/acpi/osl.c (ffff800010764360)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_acquire_lock
```
```
In drivers/acpi/ec.c (ffff800010770a48)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_resume_noirq
  - drivers/acpi/ec.c:acpi_ec_suspend
  - drivers/acpi/ec.c:acpi_ec_event_handler
  - drivers/acpi/ec.c:acpi_ec_event_handler
  - drivers/acpi/ec.c:acpi_ec_event_handler
  - drivers/acpi/ec.c:acpi_ec_enter_noirq
  - drivers/acpi/ec.c:acpi_ec_stop
  - drivers/acpi/ec.c:acpi_ec_stop
  - drivers/acpi/ec.c:acpi_ec_stopped
  - drivers/acpi/ec.c:acpi_ec_start
  - drivers/acpi/ec.c:acpi_ec_transaction
  - drivers/acpi/ec.c:acpi_ec_transaction
  - drivers/acpi/ec.c:acpi_ec_transaction
  - drivers/acpi/ec.c:acpi_ec_transaction
  - drivers/acpi/ec.c:ec_guard
  - drivers/acpi/ec.c:ec_guard
  - drivers/acpi/ec.c:ec_transaction_completed
  - drivers/acpi/ec.c:acpi_ec_enable_event
```
```
In drivers/acpi/apei/erst.c (ffff8000107adde0)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/acpi/apei/erst.c:erst_read
  - drivers/acpi/apei/erst.c:erst_get_record_id_next
  - drivers/acpi/apei/erst.c:erst_get_record_count
```
```
In drivers/acpi/apei/ghes.c (ffff8000107b0650)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_probe
  - drivers/acpi/apei/ghes.c:ghes_notify_hed
  - drivers/acpi/apei/ghes.c:ghes_irq_func
  - drivers/acpi/apei/ghes.c:ghes_poll_func
```
```
In drivers/clk/clk.c (ffff8000107bfa74)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_enable_lock
```
```
In drivers/clk/clk-divider.c (ffff8000107c470c)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/clk/clk-divider.c:clk_divider_set_rate
```
```
In drivers/clk/clk-gate.c (ffff8000107c5718)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/clk/clk-gate.c:clk_gate_endisable
```
```
In drivers/clk/clk-multiplier.c (ffff8000107c5adc)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/clk/clk-multiplier.c:clk_multiplier_set_rate
```
```
In drivers/clk/clk-mux.c (ffff8000107c62d4)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/clk/clk-mux.c:clk_mux_set_parent
```
```
In drivers/clk/clk-fractional-divider.c (ffff8000107c710c)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/clk/clk-fractional-divider.c:clk_fd_set_rate
  - drivers/clk/clk-fractional-divider.c:clk_fd_recalc_rate
```
```
In drivers/clk/clk-xgene.c (ffff8000107c94e0)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/clk/clk-xgene.c:xgene_clk_set_rate
  - drivers/clk/clk-xgene.c:xgene_clk_disable
  - drivers/clk/clk-xgene.c:xgene_clk_enable
  - drivers/clk/clk-xgene.c:xgene_clk_pmd_set_rate
  - drivers/clk/clk-xgene.c:xgene_clk_pmd_recalc_rate
```
```
In drivers/clk/hisilicon/clkgate-separated.c (ffff8000107d01f4)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/clk/hisilicon/clkgate-separated.c:clkgate_separated_disable
  - drivers/clk/hisilicon/clkgate-separated.c:clkgate_separated_enable
```
```
In drivers/clk/hisilicon/clkdivider-hi6220.c (ffff8000107d05e4)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/clk/hisilicon/clkdivider-hi6220.c:hi6220_clkdiv_set_rate
```
```
In drivers/clk/hisilicon/clk-hisi-phase.c (ffff8000107d0a40)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/clk/hisilicon/clk-hisi-phase.c:hisi_clk_set_phase
```
```
In drivers/clk/hisilicon/reset.c (ffff8000107d13e8)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/clk/hisilicon/reset.c:hisi_reset_deassert
  - drivers/clk/hisilicon/reset.c:hisi_reset_assert
```
```
In drivers/clk/imx/clk-composite-8m.c (ffff8000107d2480)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/clk/imx/clk-composite-8m.c:imx8m_clk_composite_divider_set_rate
```
```
In drivers/clk/imx/clk-divider-gate.c (ffff8000107d2e14)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/clk/imx/clk-divider-gate.c:clk_divider_disable
  - drivers/clk/imx/clk-divider-gate.c:clk_divider_gate_set_rate
  - drivers/clk/imx/clk-divider-gate.c:clk_divider_gate_recalc_rate
```
```
In drivers/clk/imx/clk-fixup-div.c (ffff8000107d33ac)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/clk/imx/clk-fixup-div.c:clk_fixup_div_set_rate
```
```
In drivers/clk/imx/clk-fixup-mux.c (ffff8000107d365c)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/clk/imx/clk-fixup-mux.c:clk_fixup_mux_set_parent
```
```
In drivers/clk/imx/clk-gate2.c (ffff8000107d3f74)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/clk/imx/clk-gate2.c:clk_gate2_disable_unused
  - drivers/clk/imx/clk-gate2.c:clk_gate2_disable
  - drivers/clk/imx/clk-gate2.c:clk_gate2_enable
```
```
In drivers/clk/imx/clk-pfdv2.c (ffff8000107d494c)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/clk/imx/clk-pfdv2.c:clk_pfdv2_set_rate
  - drivers/clk/imx/clk-pfdv2.c:clk_pfdv2_disable
  - drivers/clk/imx/clk-pfdv2.c:clk_pfdv2_enable
```
```
In drivers/clk/imx/clk-lpcg-scu.c (ffff8000107d76c4)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/clk/imx/clk-lpcg-scu.c:clk_lpcg_scu_disable
  - drivers/clk/imx/clk-lpcg-scu.c:clk_lpcg_scu_enable
```
```
In drivers/clk/mediatek/clk-mux.c (ffff8000107e3644)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/clk/mediatek/clk-mux.c:mtk_clk_mux_set_parent_setclr_lock
  - drivers/clk/mediatek/clk-mux.c:mtk_clk_mux_set_parent_lock
```
```
In drivers/clk/meson/clk-mpll.c (ffff8000107e6cec)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/clk/meson/clk-mpll.c:mpll_set_rate
```
```
In drivers/clk/renesas/r9a06g032-clocks.c (ffff8000107eaa98)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/clk/renesas/r9a06g032-clocks.c:r9a06g032_clk_gate_set
  - drivers/clk/renesas/r9a06g032-clocks.c:r9a06g032_clk_gate_set
```
```
In drivers/clk/renesas/rcar-gen3-cpg.c (ffff8000107eb020)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/clk/renesas/rcar-gen3-cpg.c:cpg_reg_modify
```
```
In drivers/clk/renesas/renesas-cpg-mssr.c (ffff8000107ec224)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/clk/renesas/renesas-cpg-mssr.c:cpg_mstp_clock_endisable
```
```
In drivers/clk/rockchip/clk-cpu.c (ffff8000107ee6c8)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/clk/rockchip/clk-cpu.c:rockchip_cpuclk_notifier_cb
  - drivers/clk/rockchip/clk-cpu.c:rockchip_cpuclk_notifier_cb
```
```
In drivers/clk/rockchip/clk-half-divider.c (ffff8000107eef18)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/clk/rockchip/clk-half-divider.c:clk_half_divider_set_rate
```
```
In drivers/clk/rockchip/clk-inverter.c (ffff8000107ef34c)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/clk/rockchip/clk-inverter.c:rockchip_inv_set_phase
```
```
In drivers/clk/rockchip/clk-ddr.c (ffff8000107efdb8)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/clk/rockchip/clk-ddr.c:rockchip_ddrclk_sip_set_rate
```
```
In drivers/clk/rockchip/softrst.c (ffff8000107f0070)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/clk/rockchip/softrst.c:rockchip_softrst_deassert
  - drivers/clk/rockchip/softrst.c:rockchip_softrst_assert
```
```
In drivers/clk/sunxi/clk-factors.c (ffff8000107f1460)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/clk/sunxi/clk-factors.c:clk_factors_set_rate
```
```
In drivers/clk/sunxi/clk-a10-ve.c (ffff8000107f2324)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/clk/sunxi/clk-a10-ve.c:sunxi_ve_reset_deassert
  - drivers/clk/sunxi/clk-a10-ve.c:sunxi_ve_reset_assert
```
```
In drivers/clk/sunxi/clk-mod0.c (ffff8000107f268c)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/clk/sunxi/clk-mod0.c:mmc_set_phase
```
```
In drivers/clk/sunxi/clk-sun4i-display.c (ffff8000107f2954)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/clk/sunxi/clk-sun4i-display.c:sun4i_a10_display_deassert
  - drivers/clk/sunxi/clk-sun4i-display.c:sun4i_a10_display_assert
```
```
In drivers/clk/sunxi/clk-sun4i-tcon-ch1.c (ffff8000107f2c4c)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/clk/sunxi/clk-sun4i-tcon-ch1.c:tcon_ch1_set_rate
  - drivers/clk/sunxi/clk-sun4i-tcon-ch1.c:tcon_ch1_set_parent
  - drivers/clk/sunxi/clk-sun4i-tcon-ch1.c:tcon_ch1_enable
  - drivers/clk/sunxi/clk-sun4i-tcon-ch1.c:tcon_ch1_disable
```
```
In drivers/clk/sunxi/clk-sun9i-mmc.c (ffff8000107f3744)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/clk/sunxi/clk-sun9i-mmc.c:sun9i_mmc_reset_deassert
  - drivers/clk/sunxi/clk-sun9i-mmc.c:sun9i_mmc_reset_assert
```
```
In drivers/clk/sunxi/clk-usb.c (ffff8000107f3b04)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/clk/sunxi/clk-usb.c:sunxi_usb_reset_deassert
  - drivers/clk/sunxi/clk-usb.c:sunxi_usb_reset_assert
```
```
In drivers/clk/sunxi/clk-sun9i-cpus.c (ffff8000107f41fc)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/clk/sunxi/clk-sun9i-cpus.c:sun9i_a80_cpus_clk_set_rate
```
```
In drivers/clk/sunxi-ng/ccu_mmc_timing.c (ffff8000107f4bb0)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/clk/sunxi-ng/ccu_mmc_timing.c:sunxi_ccu_set_mmc_timing_mode
```
```
In drivers/clk/sunxi-ng/ccu_reset.c (ffff8000107f4e90)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/clk/sunxi-ng/ccu_reset.c:ccu_reset_deassert
  - drivers/clk/sunxi-ng/ccu_reset.c:ccu_reset_assert
```
```
In drivers/clk/sunxi-ng/ccu_div.c (ffff8000107f5210)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/clk/sunxi-ng/ccu_div.c:ccu_div_set_rate
```
```
In drivers/clk/sunxi-ng/ccu_frac.c (ffff8000107f580c)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/clk/sunxi-ng/ccu_frac.c:ccu_frac_helper_set_rate
  - drivers/clk/sunxi-ng/ccu_frac.c:ccu_frac_helper_disable
  - drivers/clk/sunxi-ng/ccu_frac.c:ccu_frac_helper_enable
```
```
In drivers/clk/sunxi-ng/ccu_gate.c (ffff8000107f5ac4)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
```
```
In drivers/clk/sunxi-ng/ccu_mux.c (ffff8000107f6450)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/clk/sunxi-ng/ccu_mux.c:ccu_mux_helper_set_parent
```
```
In drivers/clk/sunxi-ng/ccu_mult.c (ffff8000107f6910)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/clk/sunxi-ng/ccu_mult.c:ccu_mult_set_rate
```
```
In drivers/clk/sunxi-ng/ccu_phase.c (ffff8000107f6bcc)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/clk/sunxi-ng/ccu_phase.c:ccu_phase_set_phase
```
```
In drivers/clk/sunxi-ng/ccu_sdm.c (ffff8000107f7088)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/clk/sunxi-ng/ccu_sdm.c:ccu_sdm_helper_disable
  - drivers/clk/sunxi-ng/ccu_sdm.c:ccu_sdm_helper_disable
  - drivers/clk/sunxi-ng/ccu_sdm.c:ccu_sdm_helper_enable
  - drivers/clk/sunxi-ng/ccu_sdm.c:ccu_sdm_helper_enable
```
```
In drivers/clk/sunxi-ng/ccu_nk.c (ffff8000107f77c4)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/clk/sunxi-ng/ccu_nk.c:ccu_nk_set_rate
```
```
In drivers/clk/sunxi-ng/ccu_nkm.c (ffff8000107f7e98)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/clk/sunxi-ng/ccu_nkm.c:ccu_nkm_set_rate
```
```
In drivers/clk/sunxi-ng/ccu_nkmp.c (ffff8000107f8680)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/clk/sunxi-ng/ccu_nkmp.c:ccu_nkmp_set_rate
```
```
In drivers/clk/sunxi-ng/ccu_nm.c (ffff8000107f8df4)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/clk/sunxi-ng/ccu_nm.c:ccu_nm_set_rate
  - drivers/clk/sunxi-ng/ccu_nm.c:ccu_nm_set_rate
```
```
In drivers/clk/sunxi-ng/ccu_mp.c (ffff8000107f961c)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/clk/sunxi-ng/ccu_mp.c:ccu_mp_set_rate
```
```
In drivers/clk/versatile/clk-sp810.c (ffff8000107fa038)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/clk/versatile/clk-sp810.c:clk_sp810_timerclken_set_parent
```
```
In drivers/dma/virt-dma.c (ffff8000107fe900)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/dma/virt-dma.c:vchan_tx_desc_free
  - drivers/dma/virt-dma.c:vchan_tx_submit
```
```
In drivers/dma/amba-pl08x.c (ffff800010800660)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/dma/amba-pl08x.c:pl08x_debugfs_show
  - drivers/dma/amba-pl08x.c:pl08x_resume
  - drivers/dma/amba-pl08x.c:pl08x_pause
  - drivers/dma/amba-pl08x.c:pl08x_synchronize
  - drivers/dma/amba-pl08x.c:pl08x_terminate_all
  - drivers/dma/amba-pl08x.c:pl08x_prep_dma_cyclic
  - drivers/dma/amba-pl08x.c:pl08x_prep_slave_sg
  - drivers/dma/amba-pl08x.c:pl08x_prep_dma_memcpy
  - drivers/dma/amba-pl08x.c:pl08x_issue_pending
  - drivers/dma/amba-pl08x.c:pl08x_issue_pending
  - drivers/dma/amba-pl08x.c:pl08x_free_chan_resources
```
```
In drivers/dma/bcm2835-dma.c (ffff800010804b88)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/dma/bcm2835-dma.c:bcm2835_dma_synchronize
  - drivers/dma/bcm2835-dma.c:bcm2835_dma_terminate_all
  - drivers/dma/bcm2835-dma.c:bcm2835_dma_prep_dma_cyclic
  - drivers/dma/bcm2835-dma.c:bcm2835_dma_prep_slave_sg
  - drivers/dma/bcm2835-dma.c:bcm2835_dma_prep_dma_memcpy
  - drivers/dma/bcm2835-dma.c:bcm2835_dma_issue_pending
  - drivers/dma/bcm2835-dma.c:bcm2835_dma_callback
```
```
In drivers/dma/ipu/ipu_irq.c (ffff80001080ab30)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/dma/ipu/ipu_irq.c:ipu_irq_unmap
  - drivers/dma/ipu/ipu_irq.c:ipu_irq_map
  - drivers/dma/ipu/ipu_irq.c:ipu_irq_status
  - drivers/dma/ipu/ipu_irq.c:ipu_irq_ack
  - drivers/dma/ipu/ipu_irq.c:ipu_irq_mask
  - drivers/dma/ipu/ipu_irq.c:ipu_irq_unmask
```
```
In drivers/dma/ipu/ipu_idmac.c (ffff80001080d118)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/dma/ipu/ipu_idmac.c:idmac_alloc_chan_resources
  - drivers/dma/ipu/ipu_idmac.c:__idmac_terminate_all
  - drivers/dma/ipu/ipu_idmac.c:idmac_pause
  - drivers/dma/ipu/ipu_idmac.c:idmac_issue_pending
  - drivers/dma/ipu/ipu_idmac.c:idmac_prep_slave_sg
  - drivers/dma/ipu/ipu_idmac.c:ipu_gc_tasklet
  - drivers/dma/ipu/ipu_idmac.c:idmac_interrupt
  - drivers/dma/ipu/ipu_idmac.c:idmac_interrupt
  - drivers/dma/ipu/ipu_idmac.c:ipu_uninit_channel
  - drivers/dma/ipu/ipu_idmac.c:idmac_tx_submit
  - drivers/dma/ipu/ipu_idmac.c:idmac_tx_submit
  - drivers/dma/ipu/ipu_idmac.c:idmac_tx_submit
  - drivers/dma/ipu/ipu_idmac.c:idmac_tx_submit
  - drivers/dma/ipu/ipu_idmac.c:ipu_submit_buffer
```
```
In drivers/soc/fsl/qbman/qman.c (ffff80001081449c)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/soc/fsl/qbman/qman.c:qman_delete_cgr
```
```
In drivers/soc/qcom/rpmh-rsc.c (ffff80001081c7c8)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/soc/qcom/rpmh-rsc.c:rpmh_rsc_write_ctrl_data
  - drivers/soc/qcom/rpmh-rsc.c:rpmh_rsc_send_data
```
```
In drivers/soc/qcom/rpmh.c (ffff80001081cf50)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/soc/qcom/rpmh.c:rpmh_invalidate
  - drivers/soc/qcom/rpmh.c:rpmh_flush
  - drivers/soc/qcom/rpmh.c:rpmh_write_batch
  - drivers/soc/qcom/rpmh.c:__rpmh_write
```
```
In drivers/soc/renesas/rcar-sysc.c (ffff80001081e208)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/soc/renesas/rcar-sysc.c:rcar_sysc_power
```
```
In drivers/virtio/virtio.c (ffff8000108211f0)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/virtio/virtio.c:virtio_config_changed
```
```
In drivers/virtio/virtio_mmio.c (ffff800010826084)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_del_vqs
  - drivers/virtio/virtio_mmio.c:vm_interrupt
```
```
In drivers/virtio/virtio_pci_common.c (ffff8000108286b0)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/virtio/virtio_pci_common.c:vp_setup_vq
  - drivers/virtio/virtio_pci_common.c:vp_vring_interrupt
```
```
In drivers/virtio/virtio_balloon.c (ffff80001082b0a4)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_changed
```
```
In drivers/xen/grant-table.c (ffff80001082d4b4)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_cancel_free_callback
  - drivers/xen/grant-table.c:gnttab_request_free_callback
  - drivers/xen/grant-table.c:gnttab_handle_deferred
  - drivers/xen/grant-table.c:gnttab_handle_deferred
  - drivers/xen/grant-table.c:put_free_entry
  - drivers/xen/grant-table.c:get_free_entries
```
```
In drivers/xen/events/events_2l.c (ffff800010833148)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:xen_debug_interrupt
```
```
In drivers/reset/reset-meson.c (ffff80001084d9d0)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/reset/reset-meson.c:meson_reset_level
```
```
In drivers/reset/reset-simple.c (ffff80001084de28)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/reset/reset-simple.c:reset_simple_update
```
```
In drivers/tty/tty_io.c (ffff800010850fc0)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:__tty_fasync
  - drivers/tty/tty_io.c:start_tty
  - drivers/tty/tty_io.c:stop_tty
```
```
In drivers/tty/n_tty.c (ffff800010854e70)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
```
```
In drivers/tty/tty_ldisc.c (ffff80001085bf4c)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/tty/tty_ldisc.c:get_ldops
  - drivers/tty/tty_ldisc.c:tty_unregister_ldisc
  - drivers/tty/tty_ldisc.c:tty_register_ldisc
```
```
In drivers/tty/tty_port.c (ffff80001085e67c)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_close_end
  - drivers/tty/tty_port.c:tty_port_close_end
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_hangup
  - drivers/tty/tty_port.c:tty_port_tty_set
  - drivers/tty/tty_port.c:tty_port_tty_get
```
```
In drivers/tty/tty_ldsem.c (ffff80001085f520)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:ldsem_wake
```
```
In drivers/tty/tty_jobctrl.c (ffff80001085fbfc)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:tty_get_pgrp
  - drivers/tty/tty_jobctrl.c:get_current_tty
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/tty_jobctrl.c:proc_clear_tty
```
```
In drivers/tty/pty.c (ffff80001086284c)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/tty/pty.c:pty_write
```
```
In drivers/tty/sysrq.c (ffff8000108640c4)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
```
```
In drivers/tty/vt/vt_ioctl.c (ffff800010865224)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:__vt_event_dequeue
  - drivers/tty/vt/vt_ioctl.c:__vt_event_queue
```
```
In drivers/tty/vt/keyboard.c (ffff80001086f088)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:vt_clr_kbd_mode_bit
  - drivers/tty/vt/keyboard.c:vt_set_kbd_mode_bit
  - drivers/tty/vt/keyboard.c:vt_reset_keyboard
  - drivers/tty/vt/keyboard.c:vt_reset_unicode
  - drivers/tty/vt/keyboard.c:vt_do_kdskled
  - drivers/tty/vt/keyboard.c:vt_do_kdskled
  - drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl
  - drivers/tty/vt/keyboard.c:vt_do_kdsk_ioctl
  - drivers/tty/vt/keyboard.c:vt_do_kdsk_ioctl
  - drivers/tty/vt/keyboard.c:vt_do_kdsk_ioctl
  - drivers/tty/vt/keyboard.c:vt_do_kdskbmeta
  - drivers/tty/vt/keyboard.c:vt_do_kdskbmode
  - drivers/tty/vt/keyboard.c:vt_do_diacrit
  - drivers/tty/vt/keyboard.c:vt_do_diacrit
  - drivers/tty/vt/keyboard.c:vt_do_diacrit
  - drivers/tty/vt/keyboard.c:vt_do_diacrit
  - drivers/tty/vt/keyboard.c:kbd_bh
  - drivers/tty/vt/keyboard.c:vt_kbd_con_stop
  - drivers/tty/vt/keyboard.c:vt_kbd_con_start
  - drivers/tty/vt/keyboard.c:vt_get_leds
  - drivers/tty/vt/keyboard.c:setledstate
  - drivers/tty/vt/keyboard.c:compute_shiftstate
```
```
In drivers/tty/hvc/hvc_console.c (ffff80001087a224)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_remove
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
  - drivers/tty/hvc/hvc_console.c:hvc_set_winsz
  - drivers/tty/hvc/hvc_console.c:hvc_write
  - drivers/tty/hvc/hvc_console.c:hvc_hangup
  - drivers/tty/hvc/hvc_console.c:hvc_open
  - drivers/tty/hvc/hvc_console.c:hvc_port_destruct
  - drivers/tty/hvc/hvc_console.c:hvc_get_by_index
```
```
In drivers/tty/serial/serial_core.c (ffff80001088260c)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_add_one_port
  - drivers/tty/serial/serial_core.c:uart_hangup
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_send_xchar
  - drivers/tty/serial/serial_core.c:uart_flush_buffer
  - drivers/tty/serial/serial_core.c:uart_chars_in_buffer
  - drivers/tty/serial/serial_core.c:uart_write_room
  - drivers/tty/serial/serial_core.c:uart_write
  - drivers/tty/serial/serial_core.c:uart_put_char
  - drivers/tty/serial/serial_core.c:uart_shutdown
  - drivers/tty/serial/serial_core.c:uart_update_mctrl
  - drivers/tty/serial/serial_core.c:uart_start
  - drivers/tty/serial/serial_core.c:uart_stop
```
```
In drivers/tty/serial/8250/8250_core.c (ffff800010884ab0)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_unregister_port
  - drivers/tty/serial/8250/8250_core.c:serial_8250_overrun_backoff_work
  - drivers/tty/serial/8250/8250_core.c:serial8250_backup_timeout
```
```
In drivers/tty/serial/8250/8250_port.c (ffff80001088b390)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_break_ctl
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_empty
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_threshold_handle_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_stop_tx
  - drivers/tty/serial/8250/8250_port.c:autoconfig
```
```
In drivers/tty/serial/8250/8250_dma.c (ffff80001088c088)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete
```
```
In drivers/tty/serial/8250/8250_pci.c (ffff80001088fcfc)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:f815xxa_mem_serial_out
```
```
In drivers/tty/serial/8250/8250_fsl.c (ffff800010890874)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_fsl.c:fsl8250_handle_irq
```
```
In drivers/tty/serial/8250/8250_dw.c (ffff800010891120)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dw.c:dw8250_handle_irq
```
```
In drivers/tty/serial/8250/8250_mtk.c (ffff8000108926d4)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_set_termios
```
```
In drivers/tty/serial/amba-pl011.c (ffff80001089696c)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/tty/serial/amba-pl011.c:sbsa_uart_set_termios
  - drivers/tty/serial/amba-pl011.c:pl011_set_termios
  - drivers/tty/serial/amba-pl011.c:pl011_break_ctl
  - drivers/tty/serial/amba-pl011.c:pl011_int
  - drivers/tty/serial/amba-pl011.c:pl011_dma_rx_poll
  - drivers/tty/serial/amba-pl011.c:pl011_dma_tx_callback
```
```
In drivers/tty/serial/imx.c (ffff80001089b15c)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/tty/serial/imx.c:imx_uart_resume_noirq
  - drivers/tty/serial/imx.c:imx_uart_suspend_noirq
  - drivers/tty/serial/imx.c:imx_uart_console_write
  - drivers/tty/serial/imx.c:imx_uart_set_termios
  - drivers/tty/serial/imx.c:imx_uart_shutdown
  - drivers/tty/serial/imx.c:imx_uart_shutdown
  - drivers/tty/serial/imx.c:imx_uart_shutdown
  - drivers/tty/serial/imx.c:imx_uart_timeout
  - drivers/tty/serial/imx.c:imx_uart_break_ctl
  - drivers/tty/serial/imx.c:imx_uart_dma_tx_callback
```
```
In drivers/tty/serial/meson_uart.c (ffff80001089eec8)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/tty/serial/meson_uart.c:meson_uart_set_termios
  - drivers/tty/serial/meson_uart.c:meson_uart_shutdown
```
```
In drivers/tty/serial/sccnxp.c (ffff8000108a0a7c)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_console_write
  - drivers/tty/serial/sccnxp.c:sccnxp_shutdown
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_break_ctl
  - drivers/tty/serial/sccnxp.c:sccnxp_get_mctrl
  - drivers/tty/serial/sccnxp.c:sccnxp_set_mctrl
  - drivers/tty/serial/sccnxp.c:sccnxp_tx_empty
  - drivers/tty/serial/sccnxp.c:sccnxp_stop_rx
  - drivers/tty/serial/sccnxp.c:sccnxp_start_tx
  - drivers/tty/serial/sccnxp.c:sccnxp_ist
  - drivers/tty/serial/sccnxp.c:sccnxp_timer
```
```
In drivers/tty/serial/msm_serial.c (ffff8000108a2810)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/tty/serial/msm_serial.c:msm_set_termios
  - drivers/tty/serial/msm_serial.c:msm_set_termios
  - drivers/tty/serial/msm_serial.c:msm_uart_irq
  - drivers/tty/serial/msm_serial.c:msm_complete_rx_dma
  - drivers/tty/serial/msm_serial.c:msm_complete_rx_dma
  - drivers/tty/serial/msm_serial.c:msm_complete_tx_dma
```
```
In drivers/tty/serial/mvebu-uart.c (ffff8000108a5fcc)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_console_write
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_set_termios
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_break_ctl
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_tx_empty
```
```
In drivers/tty/serial/owl-uart.c (ffff8000108a7114)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/tty/serial/owl-uart.c:owl_uart_set_termios
  - drivers/tty/serial/owl-uart.c:owl_uart_shutdown
  - drivers/tty/serial/owl-uart.c:owl_uart_irq
  - drivers/tty/serial/owl-uart.c:owl_uart_tx_empty
```
```
In drivers/tty/serial/serial_mctrl_gpio.c (ffff8000108a7e48)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_irq_handle
```
```
In drivers/char/random.c (ffff8000108ac7e4)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/char/random.c:invalidate_batched_entropy
  - drivers/char/random.c:get_random_u32
  - drivers/char/random.c:get_random_u64
  - drivers/char/random.c:urandom_read
  - drivers/char/random.c:del_random_ready_callback
  - drivers/char/random.c:extract_buf
  - drivers/char/random.c:add_device_randomness
  - drivers/char/random.c:_crng_backtrack_protect
  - drivers/char/random.c:_extract_crng
  - drivers/char/random.c:crng_reseed
  - drivers/char/random.c:crng_reseed
  - drivers/char/random.c:mix_pool_bytes
```
```
In drivers/char/ttyprintk.c (ffff8000108b1e18)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/char/ttyprintk.c:tpk_write
  - drivers/char/ttyprintk.c:tpk_close
```
```
In drivers/char/virtio_console.c (ffff8000108b4c38)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:in_intr
  - drivers/char/virtio_console.c:port_fops_open
  - drivers/char/virtio_console.c:port_fops_open
  - drivers/char/virtio_console.c:__send_to_port
  - drivers/char/virtio_console.c:port_has_data
  - drivers/char/virtio_console.c:reclaim_dma_bufs
  - drivers/char/virtio_console.c:find_port_by_vq
  - drivers/char/virtio_console.c:find_port_by_id
  - drivers/char/virtio_console.c:find_port_by_vtermno
```
```
In drivers/iommu/iova.c (ffff8000108ce3e4)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/iommu/iova.c:free_cpu_cached_iovas
  - drivers/iommu/iova.c:iova_rcache_get
  - drivers/iommu/iova.c:iova_rcache_insert
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:copy_reserved_iova
  - drivers/iommu/iova.c:reserve_iova
  - drivers/iommu/iova.c:queue_iova
  - drivers/iommu/iova.c:fq_flush_timeout
  - drivers/iommu/iova.c:__free_iova
  - drivers/iommu/iova.c:find_iova
  - drivers/iommu/iova.c:alloc_iova
```
```
In drivers/iommu/arm-smmu.c (ffff8000108d1890)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/iommu/arm-smmu.c:arm_smmu_iova_to_phys_hard
  - drivers/iommu/arm-smmu.c:arm_smmu_tlb_sync_context
  - drivers/iommu/arm-smmu.c:arm_smmu_tlb_sync_global
```
```
In drivers/iommu/arm-smmu-v3.c (ffff8000108d6268)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/iommu/arm-smmu-v3.c:arm_smmu_attach_dev
  - drivers/iommu/arm-smmu-v3.c:arm_smmu_detach_dev
```
```
In drivers/iommu/rockchip-iommu.c (ffff8000108d9850)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/iommu/rockchip-iommu.c:rk_iommu_attach_device
  - drivers/iommu/rockchip-iommu.c:rk_iommu_detach_device
  - drivers/iommu/rockchip-iommu.c:rk_iommu_unmap
  - drivers/iommu/rockchip-iommu.c:rk_iommu_map
  - drivers/iommu/rockchip-iommu.c:rk_iommu_zap_iova
  - drivers/iommu/rockchip-iommu.c:rk_iommu_iova_to_phys
```
```
In drivers/iommu/qcom_iommu.c (ffff8000108db234)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/iommu/qcom_iommu.c:qcom_iommu_iova_to_phys
  - drivers/iommu/qcom_iommu.c:qcom_iommu_unmap
  - drivers/iommu/qcom_iommu.c:qcom_iommu_map
```
```
In drivers/iommu/virtio-iommu.c (ffff8000108dbd94)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/iommu/virtio-iommu.c:viommu_iotlb_sync
  - drivers/iommu/virtio-iommu.c:viommu_iova_to_phys
  - drivers/iommu/virtio-iommu.c:viommu_unmap
  - drivers/iommu/virtio-iommu.c:viommu_map
  - drivers/iommu/virtio-iommu.c:viommu_attach_dev
  - drivers/iommu/virtio-iommu.c:viommu_del_mappings
  - drivers/iommu/virtio-iommu.c:viommu_send_req_sync
```
```
In drivers/base/devres.c (ffff8000108f0204)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/base/devres.c:devres_release_group
  - drivers/base/devres.c:devres_remove_group
  - drivers/base/devres.c:devres_close_group
  - drivers/base/devres.c:devres_open_group
  - drivers/base/devres.c:devres_release_all
  - drivers/base/devres.c:devres_remove
  - drivers/base/devres.c:devres_get
  - drivers/base/devres.c:devres_find
  - drivers/base/devres.c:devres_add
```
```
In drivers/base/power/qos.c (ffff8000108fa79c)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/base/power/qos.c:dev_pm_qos_read_value
  - drivers/base/power/qos.c:dev_pm_qos_flags
```
```
In drivers/base/power/runtime.c (ffff8000108fb208)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_enable
  - drivers/base/power/runtime.c:pm_runtime_get_if_in_use
  - drivers/base/power/runtime.c:__pm_runtime_resume
  - drivers/base/power/runtime.c:__pm_runtime_suspend
  - drivers/base/power/runtime.c:__pm_runtime_idle
  - drivers/base/power/runtime.c:pm_schedule_suspend
  - drivers/base/power/runtime.c:pm_suspend_timer_fn
  - drivers/base/power/runtime.c:pm_runtime_suspended_time
  - drivers/base/power/runtime.c:pm_runtime_active_time
```
```
In drivers/base/power/wakeirq.c (ffff8000108feb38)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/base/power/wakeirq.c:dev_pm_clear_wake_irq
```
```
In drivers/base/power/wakeup.c (ffff800010903e34)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show
  - drivers/base/power/wakeup.c:pm_save_wakeup_count
  - drivers/base/power/wakeup.c:pm_wakeup_pending
  - drivers/base/power/wakeup.c:pm_wakeup_timer_fn
  - drivers/base/power/wakeup.c:wakeup_source_remove
  - drivers/base/power/wakeup.c:wakeup_source_add
  - drivers/base/power/wakeup.c:wakeup_source_record
```
```
In drivers/base/power/domain.c (ffff800010909e50)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_lock_interruptible_spin
  - drivers/base/power/domain.c:genpd_lock_nested_spin
  - drivers/base/power/domain.c:genpd_lock_spin
```
```
In drivers/base/power/domain_governor.c (ffff80001090ad28)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/base/power/domain_governor.c:default_suspend_ok
```
```
In drivers/base/power/clock_ops.c (ffff80001090b798)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/base/power/clock_ops.c:pm_clk_resume
  - drivers/base/power/clock_ops.c:pm_clk_suspend
```
```
In drivers/base/regmap/regmap.c (ffff800010913170)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_async_is_done
  - drivers/base/regmap/regmap.c:_regmap_raw_write_impl
  - drivers/base/regmap/regmap.c:_regmap_raw_write_impl
  - drivers/base/regmap/regmap.c:_regmap_raw_write_impl
  - drivers/base/regmap/regmap.c:regmap_lock_spinlock
```
```
In drivers/block/xen-blkfront.c (ffff8000109297a8)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_delay_work
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:kick_pending_request_queues
  - drivers/block/xen-blkfront.c:blkif_queue_rq
```
```
In drivers/mfd/htc-i2cpld.c (ffff80001092e350)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_chip_set
```
```
In drivers/mfd/ezx-pcap.c (ffff80001094152c)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_remove
  - drivers/mfd/ezx-pcap.c:pcap_adc_async
  - drivers/mfd/ezx-pcap.c:pcap_adc_trigger
  - drivers/mfd/ezx-pcap.c:pcap_set_ts_bits
  - drivers/mfd/ezx-pcap.c:ezx_pcap_set_bits
  - drivers/mfd/ezx-pcap.c:ezx_pcap_read
  - drivers/mfd/ezx-pcap.c:ezx_pcap_write
```
```
In drivers/dma-buf/dma-buf.c (ffff800010965bac)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll_cb
```
```
In drivers/dma-buf/dma-fence.c (ffff800010967548)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
  - drivers/dma-buf/dma-fence.c:dma_fence_remove_callback
  - drivers/dma-buf/dma-fence.c:dma_fence_get_status
  - drivers/dma-buf/dma-fence.c:dma_fence_add_callback
  - drivers/dma-buf/dma-fence.c:dma_fence_release
  - drivers/dma-buf/dma-fence.c:dma_fence_signal
```
```
In drivers/dma-buf/sw_sync.c (ffff80001096b4e0)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:timeline_fence_release
```
```
In drivers/dma-buf/sync_debug.c (ffff80001096c4b4)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/dma-buf/sync_debug.c:sync_file_debug_remove
  - drivers/dma-buf/sync_debug.c:sync_file_debug_add
  - drivers/dma-buf/sync_debug.c:sync_timeline_debug_remove
  - drivers/dma-buf/sync_debug.c:sync_timeline_debug_add
```
```
In drivers/scsi/scsi.c (ffff80001096e6b0)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_device_lookup
  - drivers/scsi/scsi.c:scsi_device_lookup_by_target
  - drivers/scsi/scsi.c:__scsi_iterate_devices
```
```
In drivers/scsi/hosts.c (ffff80001096f73c)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/scsi/hosts.c:scsi_remove_host
```
```
In drivers/scsi/scsi_error.c (ffff800010974e34)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_ioctl_reset
  - drivers/scsi/scsi_error.c:scsi_ioctl_reset
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_try_target_reset
  - drivers/scsi/scsi_error.c:scsi_try_bus_reset
  - drivers/scsi/scsi_error.c:scsi_try_host_reset
  - drivers/scsi/scsi_error.c:scsi_times_out
  - drivers/scsi/scsi_error.c:scsi_eh_scmd_add
  - drivers/scsi/scsi_error.c:scsi_eh_inc_host_failed
  - drivers/scsi/scsi_error.c:scsi_schedule_eh
```
```
In drivers/scsi/scsi_lib.c (ffff8000109770f8)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:sdev_evt_send
  - drivers/scsi/scsi_lib.c:scsi_evt_thread
  - drivers/scsi/scsi_lib.c:scsi_add_cmd_to_list
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_dec_host_busy
```
```
In drivers/scsi/scsi_scan.c (ffff80001097cd7c)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_forget_host
  - drivers/scsi/scsi_scan.c:do_scan_async
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_target_destroy
```
```
In drivers/scsi/scsi_sysfs.c (ffff80001097fe84)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
  - drivers/scsi/scsi_sysfs.c:scsi_device_dev_release_usercontext
  - drivers/scsi/scsi_sysfs.c:store_shost_eh_deadline
```
```
In drivers/ata/libata-core.c (ffff800010998928)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_detach
  - drivers/ata/libata-core.c:__ata_port_probe
  - drivers/ata/libata-core.c:ata_dev_init
  - drivers/ata/libata-core.c:ata_port_request_pm
  - drivers/ata/libata-core.c:ata_exec_internal_sg
  - drivers/ata/libata-core.c:ata_exec_internal_sg
  - drivers/ata/libata-core.c:ata_exec_internal_sg
```
```
In drivers/ata/libata-scsi.c (ffff8000109a6a68)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_dev_rescan
  - drivers/ata/libata-scsi.c:ata_scsi_dev_rescan
  - drivers/ata/libata-scsi.c:ata_scsi_user_scan
  - drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach
  - drivers/ata/libata-scsi.c:ata_scsi_handle_link_detach
  - drivers/ata/libata-scsi.c:ata_scsi_queuecmd
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_rbuf_fill
  - drivers/ata/libata-scsi.c:__ata_change_queue_depth
  - drivers/ata/libata-scsi.c:ata_scsi_slave_destroy
  - drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl
  - drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl
  - drivers/ata/libata-scsi.c:ata_scsi_unlock_native_capacity
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
  - drivers/ata/libata-scsi.c:ata_scsi_lpm_store
```
```
In drivers/ata/libata-eh.c (ffff8000109ac634)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_about_to_do
  - drivers/ata/libata-eh.c:ata_eh_detach_dev
  - drivers/ata/libata-eh.c:__ata_eh_qc_complete
  - drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn
  - drivers/ata/libata-eh.c:ata_port_wait_eh
  - drivers/ata/libata-eh.c:ata_port_wait_eh
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_cmd_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_error
```
```
In drivers/ata/libata-sff.c (ffff8000109b02f8)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_bmdma_post_internal_cmd
  - drivers/ata/libata-sff.c:ata_bmdma_error_handler
  - drivers/ata/libata-sff.c:ata_bmdma_interrupt
  - drivers/ata/libata-sff.c:ata_sff_error_handler
  - drivers/ata/libata-sff.c:ata_sff_interrupt
```
```
In drivers/ata/libata-pmp.c (ffff8000109b3f30)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_handle_link_fail
  - drivers/ata/libata-pmp.c:sata_pmp_detach
  - drivers/ata/libata-pmp.c:sata_pmp_attach
```
```
In drivers/ata/libata-acpi.c (ffff8000109b59ec)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug
```
```
In drivers/ata/libahci.c (ffff8000109bc52c)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/ata/libahci.c:ahci_transmit_led_message
  - drivers/ata/libahci.c:ahci_sw_activity_blink
  - drivers/ata/libahci.c:ahci_store_em_buffer
  - drivers/ata/libahci.c:ahci_read_em_buffer
```
```
In drivers/gpu/vga/vgaarb.c (ffff8000109c01a4)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/gpu/vga/vgaarb.c:vga_arb_release
  - drivers/gpu/vga/vgaarb.c:vga_arb_open
  - drivers/gpu/vga/vgaarb.c:vga_arb_read
  - drivers/gpu/vga/vgaarb.c:vga_client_register
  - drivers/gpu/vga/vgaarb.c:__vga_set_legacy_decoding
  - drivers/gpu/vga/vgaarb.c:vga_put
  - drivers/gpu/vga/vgaarb.c:vga_tryget
  - drivers/gpu/vga/vgaarb.c:vga_get
```
```
In drivers/spi/spi.c (ffff8000109c4e30)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_bus_lock
  - drivers/spi/spi.c:__spi_sync
  - drivers/spi/spi.c:__spi_sync
  - drivers/spi/spi.c:__spi_sync
  - drivers/spi/spi.c:__spi_sync
  - drivers/spi/spi.c:__spi_sync
  - drivers/spi/spi.c:spi_async_locked
  - drivers/spi/spi.c:spi_async
  - drivers/spi/spi.c:__spi_async
  - drivers/spi/spi.c:__spi_async
  - drivers/spi/spi.c:spi_split_transfers_maxsize
  - drivers/spi/spi.c:spi_split_transfers_maxsize
  - drivers/spi/spi.c:spi_stop_queue
  - drivers/spi/spi.c:spi_stop_queue
  - drivers/spi/spi.c:spi_start_queue
  - drivers/spi/spi.c:spi_finalize_current_message
  - drivers/spi/spi.c:spi_finalize_current_message
  - drivers/spi/spi.c:spi_get_next_queued_message
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/spi/spi.c:spi_statistics_add_transfer_stats
  - drivers/spi/spi.c:spi_statistics_transfers_split_maxsize_show
  - drivers/spi/spi.c:spi_statistics_transfer_bytes_histo16_show
  - drivers/spi/spi.c:spi_statistics_transfer_bytes_histo15_show
  - drivers/spi/spi.c:spi_statistics_transfer_bytes_histo14_show
  - drivers/spi/spi.c:spi_statistics_transfer_bytes_histo13_show
  - drivers/spi/spi.c:spi_statistics_transfer_bytes_histo12_show
  - drivers/spi/spi.c:spi_statistics_transfer_bytes_histo11_show
  - drivers/spi/spi.c:spi_statistics_transfer_bytes_histo10_show
  - drivers/spi/spi.c:spi_statistics_transfer_bytes_histo9_show
  - drivers/spi/spi.c:spi_statistics_transfer_bytes_histo8_show
  - drivers/spi/spi.c:spi_statistics_transfer_bytes_histo7_show
  - drivers/spi/spi.c:spi_statistics_transfer_bytes_histo6_show
  - drivers/spi/spi.c:spi_statistics_transfer_bytes_histo5_show
  - drivers/spi/spi.c:spi_statistics_transfer_bytes_histo4_show
  - drivers/spi/spi.c:spi_statistics_transfer_bytes_histo3_show
  - drivers/spi/spi.c:spi_statistics_transfer_bytes_histo2_show
  - drivers/spi/spi.c:spi_statistics_transfer_bytes_histo1_show
  - drivers/spi/spi.c:spi_statistics_transfer_bytes_histo0_show
  - drivers/spi/spi.c:spi_statistics_bytes_tx_show
  - drivers/spi/spi.c:spi_statistics_bytes_rx_show
  - drivers/spi/spi.c:spi_statistics_bytes_show
  - drivers/spi/spi.c:spi_statistics_spi_async_show
  - drivers/spi/spi.c:spi_statistics_spi_sync_immediate_show
  - drivers/spi/spi.c:spi_statistics_spi_sync_show
  - drivers/spi/spi.c:spi_statistics_timedout_show
  - drivers/spi/spi.c:spi_statistics_errors_show
  - drivers/spi/spi.c:spi_statistics_transfers_show
  - drivers/spi/spi.c:spi_statistics_messages_show
```
```
In drivers/net/tun.c (ffff8000109dc900)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_device_event
```
```
In drivers/net/ethernet/freescale/fec_main.c (ffff8000109e6664)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_hwtstamp
```
```
In drivers/net/ethernet/freescale/fec_ptp.c (ffff8000109ecbd4)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_ptp.c:fec_time_keep
  - drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_enable
  - drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_settime
  - drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_gettime
  - drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_adjtime
  - drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_adjfreq
  - drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_start_cyclecounter
```
```
In drivers/net/ethernet/freescale/fman/fman.c (ffff8000109ef604)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fman/fman.c:fman_set_port_params
```
```
In drivers/net/ethernet/smsc/smc91x.c (ffff8000109fcbf0)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/net/ethernet/smsc/smc91x.c:smc_hard_start_xmit
  - drivers/net/ethernet/smsc/smc91x.c:smc_hard_start_xmit
  - drivers/net/ethernet/smsc/smc91x.c:smc_hardware_send_pkt
```
```
In drivers/net/xen-netfront.c (ffff800010a084b0)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_tx_interrupt
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In drivers/usb/core/hub.c (ffff800010a13bb4)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_set_device_state
  - drivers/usb/core/hub.c:hub_quiesce
  - drivers/usb/core/hub.c:usb_hub_clear_tt_buffer
  - drivers/usb/core/hub.c:hub_tt_work
  - drivers/usb/core/hub.c:hub_tt_work
  - drivers/usb/core/hub.c:hub_resubmit_irq_urb
```
```
In drivers/usb/core/hcd.c (ffff800010a1fcf0)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hc_died
  - drivers/usb/core/hcd.c:usb_hcd_resume_root_hub
  - drivers/usb/core/hcd.c:usb_hcd_unlink_urb
  - drivers/usb/core/hcd.c:unlink1
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
  - drivers/usb/core/hcd.c:usb_hcd_poll_rh_status
```
```
In drivers/usb/core/urb.c (ffff800010a20fa8)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_scuttle_anchored_urbs
  - drivers/usb/core/urb.c:usb_get_from_anchor
  - drivers/usb/core/urb.c:usb_unpoison_anchored_urbs
  - drivers/usb/core/urb.c:usb_unanchor_urb
  - drivers/usb/core/urb.c:usb_anchor_urb
```
```
In drivers/usb/core/message.c (ffff800010a22ec8)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_sg_cancel
  - drivers/usb/core/message.c:sg_complete
  - drivers/usb/core/message.c:sg_complete
```
```
In drivers/usb/core/devio.c (ffff800010a31ac8)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:destroy_async_on_interface
  - drivers/usb/core/devio.c:destroy_async
  - drivers/usb/core/devio.c:destroy_async
  - drivers/usb/core/devio.c:async_completed
  - drivers/usb/core/devio.c:async_getcompleted
  - drivers/usb/core/devio.c:usbdev_mmap
  - drivers/usb/core/devio.c:usbdev_vm_open
  - drivers/usb/core/devio.c:dec_usb_memory_use_count
```
```
In drivers/usb/phy/phy.c (ffff800010a382a4)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/usb/phy/phy.c:usb_remove_phy
  - drivers/usb/phy/phy.c:devm_usb_get_phy_by_node
  - drivers/usb/phy/phy.c:usb_get_phy
```
```
In drivers/usb/dwc2/hcd.c (ffff800010a47d64)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_clear_tt_buffer_complete
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_endpoint_reset
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_endpoint_disable
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_endpoint_disable
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_reset_func
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
```
```
In drivers/usb/dwc2/hcd_queue.c (ffff800010a4c97c)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_free
  - drivers/usb/dwc2/hcd_queue.c:dwc2_wait_timer_fn
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffff800010a4dff4)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
```
```
In drivers/usb/host/pci-quirks.c (ffff800010a502f0)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_dev_put
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
```
```
In drivers/usb/host/ehci-hcd.c (ffff800010a59a8c)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_reset
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_disable
  - drivers/usb/host/ehci-hcd.c:ehci_urb_dequeue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_irq
  - drivers/usb/host/ehci-hcd.c:uframe_periodic_max_store
  - drivers/usb/host/ehci-hcd.c:sitd_submit
  - drivers/usb/host/ehci-hcd.c:sitd_submit
  - drivers/usb/host/ehci-hcd.c:sitd_submit
  - drivers/usb/host/ehci-hcd.c:itd_submit
  - drivers/usb/host/ehci-hcd.c:itd_submit
  - drivers/usb/host/ehci-hcd.c:itd_submit
  - drivers/usb/host/ehci-hcd.c:iso_stream_find
  - drivers/usb/host/ehci-hcd.c:ehci_clear_tt_buffer_complete
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_status_data
  - drivers/usb/host/ehci-hcd.c:ehci_hrtimer_func
  - drivers/usb/host/ehci-hcd.c:fill_registers_buffer
  - drivers/usb/host/ehci-hcd.c:fill_periodic_buffer
  - drivers/usb/host/ehci-hcd.c:fill_async_buffer
```
```
In drivers/usb/host/ohci-hcd.c (ffff800010a62648)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:ohci_shutdown
  - drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable
  - drivers/usb/host/ohci-hcd.c:ohci_urb_dequeue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:fill_registers_buffer
  - drivers/usb/host/ohci-hcd.c:fill_periodic_buffer
  - drivers/usb/host/ohci-hcd.c:fill_async_buffer
  - drivers/usb/host/ohci-hcd.c:ohci_hub_status_data
```
```
In drivers/usb/host/uhci-hcd.c (ffff800010a6cb20)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_status_data
  - drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
  - drivers/usb/host/uhci-hcd.c:uhci_fsbr_timeout
  - drivers/usb/host/uhci-hcd.c:uhci_debug_open
```
```
In drivers/usb/host/xhci.c (ffff800010a6fba8)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_clear_tt_buffer_complete
  - drivers/usb/host/xhci.c:xhci_update_hub_device
  - drivers/usb/host/xhci.c:xhci_set_usb2_hardware_lpm
  - drivers/usb/host/xhci.c:xhci_set_usb2_hardware_lpm
  - drivers/usb/host/xhci.c:xhci_change_max_exit_latency
  - drivers/usb/host/xhci.c:xhci_change_max_exit_latency
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_disable_slot
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci.c:xhci_endpoint_disable
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_suspend
```
```
In drivers/usb/host/xhci-ring.c (ffff800010a82cec)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
  - drivers/usb/host/xhci-ring.c:xhci_stop_endpoint_command_watchdog
```
```
In drivers/usb/host/xhci-hub.c (ffff800010a86d14)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_suspend
  - drivers/usb/host/xhci-hub.c:xhci_bus_suspend
  - drivers/usb/host/xhci-hub.c:xhci_bus_suspend
  - drivers/usb/host/xhci-hub.c:xhci_hub_status_data
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/usb/host/xhci-hub.c:xhci_set_port_power
```
```
In drivers/usb/host/xhci-dbgcap.c (ffff800010a8be5c)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_init
  - drivers/usb/host/xhci-dbgcap.c:xhci_do_dbc_exit
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_handle_events
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_stop
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
```
```
In drivers/usb/host/xhci-dbgtty.c (ffff800010a8c938)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgtty.c:dbc_port_activate
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_unthrottle
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_chars_in_buffer
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_write_room
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_flush_chars
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_put_char
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_write
  - drivers/usb/host/xhci-dbgtty.c:dbc_write_complete
  - drivers/usb/host/xhci-dbgtty.c:dbc_read_complete
```
```
In drivers/usb/host/xhci-debugfs.c (ffff800010a8fe88)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_port_write
```
```
In drivers/input/serio/serio.c (ffff800010a92adc)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:serio_interrupt
  - drivers/input/serio/serio.c:serio_destroy_port
  - drivers/input/serio/serio.c:serio_remove_pending_events
  - drivers/input/serio/serio.c:serio_queue_event
  - drivers/input/serio/serio.c:serio_handle_event
  - drivers/input/serio/serio.c:serio_remove_duplicate_events
```
```
In drivers/input/input.c (ffff800010a98b88)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/input/input.c:input_reset_device
  - drivers/input/input.c:input_set_keycode
  - drivers/input/input.c:input_get_keycode
  - drivers/input/input.c:input_inject_event
  - drivers/input/input.c:input_repeat_key
```
```
In drivers/input/evdev.c (ffff800010a9f944)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_handle_get_val
```
```
In drivers/rtc/interface.c (ffff800010aa9734)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_handle_legacy_irq
```
```
In drivers/rtc/rtc-sun6i.c (ffff800010aadba4)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/rtc/rtc-sun6i.c:sun6i_rtc_getalarm
  - drivers/rtc/rtc-sun6i.c:sun6i_rtc_setaie
  - drivers/rtc/rtc-sun6i.c:sun6i_rtc_osc_set_parent
```
```
In drivers/pps/kapi.c (ffff800010ac6804)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/pps/kapi.c:pps_event
```
```
In drivers/ptp/ptp_clock.c (ffff800010ac7578)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
```
```
In drivers/ptp/ptp_chardev.c (ffff800010ac8660)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/ptp/ptp_chardev.c:ptp_read
```
```
In drivers/ptp/ptp_sysfs.c (ffff800010ac8fe4)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/ptp/ptp_sysfs.c:extts_fifo_show
```
```
In drivers/power/supply/power_supply_core.c (ffff800010acc6f4)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_changed
  - drivers/power/supply/power_supply_core.c:power_supply_changed_work
  - drivers/power/supply/power_supply_core.c:power_supply_changed_work
```
```
In drivers/watchdog/watchdog_pretimeout.c (ffff800010ae124c)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_pretimeout.c:watchdog_notify_pretimeout
```
```
In drivers/md/md-bitmap.c (ffff800010af7d88)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_endwrite
```
```
In drivers/md/dm.c (ffff800010b01230)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_uevent_add
  - drivers/md/dm.c:event_callback
  - drivers/md/dm.c:dec_pending
  - drivers/md/dm.c:dec_pending
  - drivers/md/dm.c:queue_io
```
```
In drivers/md/dm-kcopyd.c (ffff800010b0b794)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:do_work
  - drivers/md/dm-kcopyd.c:process_jobs
  - drivers/md/dm-kcopyd.c:process_jobs
  - drivers/md/dm-kcopyd.c:complete_io
  - drivers/md/dm-kcopyd.c:push
```
```
In drivers/md/dm-stats.c (ffff800010b0cd74)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:free_shared_memory
```
```
In drivers/edac/ghes_edac.c (ffff800010b15560)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/edac/ghes_edac.c:ghes_edac_unregister
  - drivers/edac/ghes_edac.c:ghes_edac_register
  - drivers/edac/ghes_edac.c:ghes_edac_report_mem_error
```
```
In drivers/mmc/core/core.c (ffff800010b2f158)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_pm_notify
  - drivers/mmc/core/core.c:mmc_pm_notify
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_sw_reset
  - drivers/mmc/core/core.c:mmc_sw_reset
  - drivers/mmc/core/core.c:mmc_sw_reset
  - drivers/mmc/core/core.c:mmc_hw_reset
  - drivers/mmc/core/core.c:mmc_hw_reset
  - drivers/mmc/core/core.c:mmc_hw_reset
  - drivers/mmc/core/core.c:mmc_detach_bus
  - drivers/mmc/core/core.c:mmc_detach_bus
  - drivers/mmc/core/core.c:mmc_attach_bus
  - drivers/mmc/core/core.c:mmc_release_host
  - drivers/mmc/core/core.c:__mmc_claim_host
  - drivers/mmc/core/core.c:__mmc_claim_host
```
```
In drivers/mmc/core/block.c (ffff800010b40ca8)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/mmc/core/block.c:mmc_blk_rw_wait_cond
  - drivers/mmc/core/block.c:mmc_blk_mq_req_done
  - drivers/mmc/core/block.c:mmc_blk_mq_req_done
  - drivers/mmc/core/block.c:mmc_blk_mq_post_req
  - drivers/mmc/core/block.c:mmc_blk_cqe_complete_rq
```
```
In drivers/mmc/core/queue.c (ffff800010b43d6c)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/mmc/core/queue.c:mmc_mq_timed_out
  - drivers/mmc/core/queue.c:mmc_cqe_recovery_notifier
```
```
In drivers/mmc/host/mmci.c (ffff800010b46260)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/mmc/host/mmci.c:mmci_runtime_resume
  - drivers/mmc/host/mmci.c:mmci_runtime_suspend
  - drivers/mmc/host/mmci.c:mmci_set_ios
  - drivers/mmc/host/mmci.c:mmci_request
  - drivers/mmc/host/mmci.c:mmci_card_busy
```
```
In drivers/firmware/ti_sci.c (ffff800010b518e0)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/firmware/ti_sci.c:ti_sci_release_resource
  - drivers/firmware/ti_sci.c:ti_sci_get_free_resource
```
```
In drivers/firmware/arm_scmi/driver.c (ffff800010b56e38)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/firmware/arm_scmi/driver.c:scmi_xfer_get_init
```
```
In drivers/clocksource/sh_cmt.c (ffff800010b64bdc)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/clocksource/sh_cmt.c:sh_cmt_clocksource_read
  - drivers/clocksource/sh_cmt.c:sh_cmt_stop
  - drivers/clocksource/sh_cmt.c:sh_cmt_start
  - drivers/clocksource/sh_cmt.c:sh_cmt_set_next
  - drivers/clocksource/sh_cmt.c:sh_cmt_start_stop_ch
```
```
In drivers/clocksource/sh_tmu.c (ffff800010b65b6c)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/clocksource/sh_tmu.c:sh_tmu_start_stop_ch
```
```
In drivers/of/base.c (ffff800010b6be90)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/of/base.c:of_update_property
  - drivers/of/base.c:of_remove_property
  - drivers/of/base.c:of_add_property
  - drivers/of/base.c:of_find_node_by_phandle
  - drivers/of/base.c:of_find_matching_node_and_match
  - drivers/of/base.c:of_match_node
  - drivers/of/base.c:of_find_node_with_property
  - drivers/of/base.c:of_find_compatible_node
  - drivers/of/base.c:of_find_node_by_type
  - drivers/of/base.c:of_find_node_by_name
  - drivers/of/base.c:of_find_node_opts_by_path
  - drivers/of/base.c:of_get_next_cpu_node
  - drivers/of/base.c:of_get_next_available_child
  - drivers/of/base.c:of_get_next_child
  - drivers/of/base.c:of_get_next_parent
  - drivers/of/base.c:of_get_parent
  - drivers/of/base.c:of_device_is_available
  - drivers/of/base.c:of_device_is_compatible
  - drivers/of/base.c:of_find_all_nodes
  - drivers/of/base.c:of_find_property
  - drivers/of/base.c:of_populate_phandle_cache
  - drivers/of/base.c:of_free_phandle_cache
```
```
In drivers/of/dynamic.c (ffff800010b70f00)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/of/dynamic.c:__of_changeset_entry_apply
  - drivers/of/dynamic.c:of_detach_node
  - drivers/of/dynamic.c:of_attach_node
```
```
In drivers/of/resolver.c (ffff800010b76bb4)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/of/resolver.c:of_resolve_phandles
```
```
In drivers/mailbox/mailbox.c (ffff800010b7a914)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/mailbox/mailbox.c:mbox_request_channel
  - drivers/mailbox/mailbox.c:mbox_send_message
  - drivers/mailbox/mailbox.c:msg_submit
```
```
In drivers/mailbox/pcc.c (ffff800010b7bb38)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/mailbox/pcc.c:pcc_mbox_free_channel
  - drivers/mailbox/pcc.c:pcc_mbox_request_channel
```
```
In drivers/extcon/extcon.c (ffff800010b885f8)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_unregister_notifier_all
  - drivers/extcon/extcon.c:extcon_register_notifier_all
  - drivers/extcon/extcon.c:extcon_unregister_notifier
  - drivers/extcon/extcon.c:extcon_register_notifier
  - drivers/extcon/extcon.c:extcon_set_property
  - drivers/extcon/extcon.c:extcon_get_property
  - drivers/extcon/extcon.c:extcon_set_state
  - drivers/extcon/extcon.c:extcon_get_state
  - drivers/extcon/extcon.c:extcon_sync
  - drivers/extcon/extcon.c:extcon_sync
```
```
In drivers/memory/fsl_ifc.c (ffff800010b8b244)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/memory/fsl_ifc.c:check_nand_stat
```
```
In drivers/perf/arm-cci.c (ffff800010b91974)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/perf/arm-cci.c:cci_pmu_start
  - drivers/perf/arm-cci.c:cci_pmu_disable
  - drivers/perf/arm-cci.c:cci_pmu_enable
  - drivers/perf/arm-cci.c:pmu_handle_irq
```
```
In drivers/perf/qcom_l2_pmu.c (ffff800010b99640)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/perf/qcom_l2_pmu.c:l2_cache_event_start
  - drivers/perf/qcom_l2_pmu.c:get_l2_indirect_reg
  - drivers/perf/qcom_l2_pmu.c:set_l2_indirect_reg
```
```
In drivers/perf/xgene_pmu.c (ffff800010b9c8ac)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - drivers/perf/xgene_pmu.c:xgene_pmu_isr
```
```
In net/core/sock.c (ffff800010bad048)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffff800010bb3e50)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_dequeue_err_skb
  - net/core/skbuff.c:skb_append
  - net/core/skbuff.c:skb_unlink
  - net/core/skbuff.c:skb_queue_tail
  - net/core/skbuff.c:skb_queue_head
  - net/core/skbuff.c:skb_dequeue_tail
  - net/core/skbuff.c:skb_dequeue
  - net/core/skbuff.c:sock_zerocopy_callback
```
```
In net/core/datagram.c (ffff800010bbcd18)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_try_recv_datagram
```
```
In net/core/link_watch.c (ffff800010bf3968)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_fire_event
  - net/core/link_watch.c:linkwatch_forget_dev
```
```
In net/core/netpoll.c (ffff800010c1098c)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - net/core/netpoll.c:refill_skbs
```
```
In net/core/drop_monitor.c (ffff800010c1b93c)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_probe
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit
  - net/core/drop_monitor.c:net_dm_hw_summary_probe
  - net/core/drop_monitor.c:net_dm_hw_reset_per_cpu_data
  - net/core/drop_monitor.c:reset_per_cpu_data
```
```
In net/sched/sch_generic.c (ffff800010c37cc4)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
```
```
In net/rfkill/core.c (ffff800010d6bc58)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_blocked
  - net/rfkill/core.c:rfkill_set_states
  - net/rfkill/core.c:rfkill_init_sw_state
  - net/rfkill/core.c:rfkill_set_sw_state
  - net/rfkill/core.c:rfkill_set_hw_state
  - net/rfkill/core.c:rfkill_set_block
  - net/rfkill/core.c:rfkill_set_block
  - net/rfkill/core.c:rfkill_fill_event
```
```
In net/rfkill/input.c (ffff800010d6d9e4)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - net/rfkill/input.c:rfkill_schedule_global_op
```
```
In net/ncsi/ncsi-rsp.c (ffff800010d76fac)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gp
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sma
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_svf
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gls
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_rc
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dp
```
```
In net/ncsi/ncsi-aen.c (ffff800010d7744c)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_hncdsc
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_cr
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_cr
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_cr
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
```
```
In net/ncsi/ncsi-manage.c (ffff800010d79284)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - net/ncsi/ncsi-manage.c:ncsi_unregister_dev
  - net/ncsi/ncsi-manage.c:ncsi_reset_dev
  - net/ncsi/ncsi-manage.c:ncsi_reset_dev
  - net/ncsi/ncsi-manage.c:ncsi_reset_dev
  - net/ncsi/ncsi-manage.c:ncsi_reset_dev
  - net/ncsi/ncsi-manage.c:ncsi_stop_dev
  - net/ncsi/ncsi-manage.c:ncsi_kick_channels
  - net/ncsi/ncsi-manage.c:ncsi_kick_channels
  - net/ncsi/ncsi-manage.c:ncsi_kick_channels
  - net/ncsi/ncsi-manage.c:ncsi_process_next_channel
  - net/ncsi/ncsi-manage.c:ncsi_process_next_channel
  - net/ncsi/ncsi-manage.c:ncsi_choose_active_channel
  - net/ncsi/ncsi-manage.c:ncsi_choose_active_channel
  - net/ncsi/ncsi-manage.c:ncsi_choose_active_channel
  - net/ncsi/ncsi-manage.c:ncsi_choose_active_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_suspend_channel
  - net/ncsi/ncsi-manage.c:ncsi_request_timeout
  - net/ncsi/ncsi-manage.c:ncsi_free_request
  - net/ncsi/ncsi-manage.c:ncsi_alloc_request
  - net/ncsi/ncsi-manage.c:ncsi_remove_package
  - net/ncsi/ncsi-manage.c:ncsi_remove_package
  - net/ncsi/ncsi-manage.c:ncsi_remove_package
  - net/ncsi/ncsi-manage.c:ncsi_add_package
  - net/ncsi/ncsi-manage.c:ncsi_add_channel
  - net/ncsi/ncsi-manage.c:ncsi_stop_channel_monitor
  - net/ncsi/ncsi-manage.c:ncsi_start_channel_monitor
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
  - net/ncsi/ncsi-manage.c:ncsi_report_link
```
```
In net/ncsi/ncsi-netlink.c (ffff800010d7d444)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
```
```
In net/xdp/xsk.c (ffff800010d7f450)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_destruct_skb
```
```
In net/xdp/xdp_umem.c (ffff800010d80ce4)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_del_sk_umem
  - net/xdp/xdp_umem.c:xdp_add_sk_umem
```
```
In lib/dec_and_lock.c (ffff800010d84874)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
```
```
In lib/flex_proportions.c (ffff800010d8806c)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
```
```
In lib/idr.c (ffff800010d88cec)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - lib/idr.c:ida_destroy
  - lib/idr.c:ida_free
  - lib/idr.c:ida_alloc_range
```
```
In lib/klist.c (ffff800010d89c10)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - lib/klist.c:klist_next
  - lib/klist.c:klist_prev
```
```
In lib/xarray.c (ffff800010d9ac5c)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - lib/xarray.c:xa_destroy
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (c0e9f550)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_spin_lock_irqsave
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (c000000000ee9ee8)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_spin_lock_irqsave
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffe0008c97c4)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_spin_lock_irqsave
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff81a73bd5)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_spin_lock_irqsave
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff81a2fe55)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_spin_lock_irqsave
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff81adffe5)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_spin_lock_irqsave
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff81aec995)
Location: include/linux/spinlock_api_smp.h:104
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_spin_lock_irqsave
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
