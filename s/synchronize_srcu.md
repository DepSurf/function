# Function: <code>synchronize_srcu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void synchronize_srcu(struct srcu_struct *sp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcu.c (ffffffff810e40e0)
Location: kernel/rcu/srcu.c:490
Inline: False
Direct callers:
  - kernel/rcu/srcu.c:srcu_barrier
  - kernel/events/core.c:perf_pmu_unregister
  - mm/mmu_notifier.c:mmu_notifier_unregister
  - mm/mmu_notifier.c:__mmu_notifier_release
  - fs/notify/group.c:fsnotify_destroy_group
  - fs/notify/mark.c:fsnotify_mark_destroy
  - fs/quota/dquot.c:dquot_disable
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:dm_swap_table
  - net/core/netpoll.c:__netpoll_cleanup
```
**Symbols:**

```
ffffffff810e40e0-ffffffff810e4107: synchronize_srcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void synchronize_srcu(struct srcu_struct *sp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcu.c (ffffffff810ea3e0)
Location: kernel/rcu/srcu.c:490
Inline: False
Direct callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/srcu.c:srcu_barrier
  - kernel/events/core.c:perf_pmu_unregister
  - mm/mmu_notifier.c:mmu_notifier_unregister
  - mm/mmu_notifier.c:__mmu_notifier_release
  - fs/notify/mark.c:fsnotify_mark_destroy_list
  - fs/quota/dquot.c:dquot_disable
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:dm_swap_table
  - drivers/md/dm.c:__dm_destroy
  - net/core/netpoll.c:__netpoll_cleanup
```
**Symbols:**

```
ffffffff810ea3e0-ffffffff810ea41f: synchronize_srcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void synchronize_srcu(struct srcu_struct *sp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcu.c (ffffffff810f12c0)
Location: kernel/rcu/srcu.c:490
Inline: False
Direct callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/srcu.c:srcu_barrier
  - kernel/events/core.c:perf_pmu_unregister
  - mm/mmu_notifier.c:mmu_notifier_unregister
  - mm/mmu_notifier.c:__mmu_notifier_release
  - fs/notify/mark.c:fsnotify_mark_destroy_list
  - fs/quota/dquot.c:dquot_disable
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - block/blk-mq.c:blk_mq_quiesce_queue
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:dm_swap_table
  - drivers/md/dm.c:__dm_destroy
  - net/core/netpoll.c:__netpoll_cleanup
```
**Symbols:**

```
ffffffff810f12c0-ffffffff810f12ff: synchronize_srcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void synchronize_srcu(struct srcu_struct *sp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff810f2240)
Location: kernel/rcu/srcutree.c:970
Inline: True
Direct callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/events/core.c:perf_pmu_unregister
  - mm/mmu_notifier.c:mmu_notifier_unregister
  - mm/mmu_notifier.c:__mmu_notifier_release
  - fs/notify/mark.c:fsnotify_mark_destroy_workfn
  - fs/notify/mark.c:fsnotify_connector_destroy_workfn
  - fs/quota/dquot.c:dquot_disable
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - block/blk-mq.c:blk_mq_quiesce_queue
  - drivers/base/power/wakeup.c:wakeup_source_remove
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:dm_swap_table
  - drivers/md/dm.c:__dm_destroy
  - net/core/netpoll.c:__netpoll_cleanup
```
**Symbols:**

```
ffffffff810f2240-ffffffff810f230d: synchronize_srcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void synchronize_srcu(struct srcu_struct *sp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff810fbfb0)
Location: kernel/rcu/srcutree.c:971
Inline: True
Direct callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/events/core.c:perf_pmu_unregister
  - mm/mmu_notifier.c:mmu_notifier_unregister
  - mm/mmu_notifier.c:__mmu_notifier_release
  - fs/notify/mark.c:fsnotify_mark_destroy_workfn
  - fs/notify/mark.c:fsnotify_connector_destroy_workfn
  - fs/quota/dquot.c:dquot_disable
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - block/blk-mq.c:blk_mq_quiesce_queue
  - drivers/base/power/wakeup.c:wakeup_source_remove
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:dm_swap_table
  - drivers/md/dm.c:__dm_destroy
  - net/core/netpoll.c:__netpoll_cleanup
```
**Symbols:**

```
ffffffff810fbfb0-ffffffff810fc083: synchronize_srcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void synchronize_srcu(struct srcu_struct *sp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff81104480)
Location: kernel/rcu/srcutree.c:1001
Inline: True
Direct callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/events/core.c:perf_pmu_unregister
  - mm/mmu_notifier.c:mmu_notifier_unregister
  - mm/mmu_notifier.c:__mmu_notifier_release
  - fs/notify/mark.c:fsnotify_mark_destroy_workfn
  - fs/notify/mark.c:fsnotify_connector_destroy_workfn
  - fs/quota/dquot.c:dquot_disable
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - block/blk-mq.c:blk_mq_quiesce_queue
  - drivers/base/power/wakeup.c:wakeup_source_remove
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:dm_swap_table
  - drivers/md/dm.c:__dm_destroy
  - net/core/netpoll.c:__netpoll_cleanup
```
**Symbols:**

```
ffffffff81104480-ffffffff8110455c: synchronize_srcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void synchronize_srcu(struct srcu_struct *ssp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff8110fed0)
Location: kernel/rcu/srcutree.c:1019
Inline: True
Direct callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/trace_events.c:event_trace_del_tracer
  - kernel/trace/trace_events.c:ftrace_event_pid_write
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_trigger.c:set_trigger_filter
  - kernel/trace/trace_events_trigger.c:trigger_data_free
  - kernel/trace/trace_events_hist.c:hist_register_trigger
  - kernel/events/core.c:perf_pmu_unregister
  - mm/mmu_notifier.c:mmu_notifier_unregister
  - mm/mmu_notifier.c:__mmu_notifier_release
  - fs/notify/mark.c:fsnotify_mark_destroy_workfn
  - fs/notify/mark.c:fsnotify_connector_destroy_workfn
  - fs/quota/dquot.c:dquot_disable
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - block/blk-mq.c:blk_mq_quiesce_queue
  - drivers/base/power/wakeup.c:wakeup_source_remove
  - drivers/i2c/i2c-core-base.c:i2c_exit
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:dm_swap_table
  - drivers/md/dm.c:__dm_destroy
  - net/core/netpoll.c:__netpoll_cleanup
```
**Symbols:**

```
ffffffff8110fed0-ffffffff8110ffac: synchronize_srcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void synchronize_srcu(struct srcu_struct *ssp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff81118d90)
Location: kernel/rcu/srcutree.c:994
Inline: True
Direct callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/trace_events.c:event_trace_del_tracer
  - kernel/trace/trace_events.c:ftrace_event_pid_write
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_trigger.c:set_trigger_filter
  - kernel/trace/trace_events_trigger.c:trigger_data_free
  - kernel/trace/trace_events_hist.c:hist_register_trigger
  - kernel/events/core.c:perf_pmu_unregister
  - mm/mmu_notifier.c:mmu_notifier_unregister
  - mm/mmu_notifier.c:__mmu_notifier_release
  - fs/notify/mark.c:fsnotify_mark_destroy_workfn
  - fs/notify/mark.c:fsnotify_connector_destroy_workfn
  - fs/quota/dquot.c:dquot_disable
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - block/blk-mq.c:blk_mq_quiesce_queue
  - drivers/base/power/wakeup.c:wakeup_source_remove
  - drivers/i2c/i2c-core-base.c:i2c_exit
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:dm_swap_table
  - drivers/md/dm.c:__dm_destroy
  - net/core/netpoll.c:__netpoll_cleanup
```
**Symbols:**

```
ffffffff81118d90-ffffffff81118e6c: synchronize_srcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void synchronize_srcu(struct srcu_struct *ssp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff81125160)
Location: kernel/rcu/srcutree.c:995
Inline: True
Direct callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/trace_events.c:event_trace_del_tracer
  - kernel/trace/trace_events.c:ftrace_event_pid_write
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_trigger.c:set_trigger_filter
  - kernel/trace/trace_events_trigger.c:trigger_data_free
  - kernel/trace/trace_events_hist.c:hist_register_trigger
  - kernel/events/core.c:perf_pmu_unregister
  - mm/mmu_notifier.c:mmu_notifier_synchronize
  - mm/mmu_notifier.c:mmu_notifier_unregister
  - mm/mmu_notifier.c:__mmu_notifier_release
  - fs/notify/mark.c:fsnotify_mark_destroy_workfn
  - fs/notify/mark.c:fsnotify_connector_destroy_workfn
  - fs/quota/dquot.c:dquot_disable
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - block/blk-mq.c:blk_mq_quiesce_queue
  - drivers/base/power/wakeup.c:wakeup_source_remove
  - drivers/i2c/i2c-core-base.c:i2c_exit
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:dm_swap_table
  - drivers/md/dm.c:__dm_destroy
  - net/core/netpoll.c:__netpoll_cleanup
  - net/core/drop_monitor.c:net_dm_trace_off_set
```
**Symbols:**

```
ffffffff81125160-ffffffff8112523c: synchronize_srcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void synchronize_srcu(struct srcu_struct *ssp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff81132bb0)
Location: kernel/rcu/srcutree.c:1008
Inline: True
Direct callers:
  - kernel/rcu/update.c:rcu_tasks_postscan
  - kernel/trace/blktrace.c:blk_unregister_tracepoints
  - kernel/trace/trace_events.c:event_trace_del_tracer
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:process_system_preds
  - kernel/trace/trace_events_filter.c:process_system_preds
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_free
  - kernel/trace/trace_events_trigger.c:set_trigger_filter
  - kernel/trace/trace_events_trigger.c:event_trigger_free
  - kernel/trace/trace_events_hist.c:hist_register_trigger
  - kernel/events/core.c:perf_pmu_unregister
  - mm/mmu_notifier.c:mmu_notifier_synchronize
  - mm/mmu_notifier.c:mmu_notifier_unregister
  - mm/mmu_notifier.c:mn_hlist_release
  - fs/notify/mark.c:fsnotify_mark_destroy_workfn
  - fs/notify/mark.c:fsnotify_connector_destroy_workfn
  - fs/quota/dquot.c:dquot_disable
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - block/blk-mq.c:blk_mq_quiesce_queue
  - drivers/base/power/wakeup.c:wakeup_source_remove
  - drivers/i2c/i2c-core-base.c:i2c_exit
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:__bind
  - net/core/netpoll.c:__netpoll_cleanup
  - net/core/drop_monitor.c:net_dm_trace_off_set
```
**Symbols:**

```
ffffffff81132bb0-ffffffff81132c13: synchronize_srcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void synchronize_srcu(struct srcu_struct *ssp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff8112e390)
Location: kernel/rcu/srcutree.c:997
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/sgx/driver.c:sgx_release
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_mmu_notifier_release
  - kernel/tracepoint.c:tracepoint_remove_func
  - kernel/trace/blktrace.c:blk_unregister_tracepoints
  - kernel/trace/trace_events.c:event_trace_del_tracer
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:process_system_preds
  - kernel/trace/trace_events_filter.c:process_system_preds
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_free
  - kernel/trace/trace_events_trigger.c:set_trigger_filter
  - kernel/trace/trace_events_trigger.c:event_trigger_free
  - kernel/trace/trace_events_hist.c:hist_register_trigger
  - kernel/events/core.c:perf_pmu_unregister
  - mm/mmu_notifier.c:mmu_notifier_synchronize
  - mm/mmu_notifier.c:mmu_notifier_unregister
  - mm/mmu_notifier.c:mn_hlist_release
  - fs/notify/mark.c:fsnotify_mark_destroy_workfn
  - fs/notify/mark.c:fsnotify_connector_destroy_workfn
  - fs/quota/dquot.c:dquot_disable
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - block/blk-mq.c:blk_mq_quiesce_queue
  - drivers/base/power/wakeup.c:wakeup_source_remove
  - drivers/i2c/i2c-core-base.c:i2c_exit
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:__bind
  - net/core/netpoll.c:__netpoll_cleanup
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/core/drop_monitor.c:net_dm_hw_monitor_stop
```
**Symbols:**

```
ffffffff8112e390-ffffffff8112e3f3: synchronize_srcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void synchronize_srcu(struct srcu_struct *ssp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff8112e910)
Location: kernel/rcu/srcutree.c:1011
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/sgx/driver.c:sgx_release
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_mmu_notifier_release
  - kernel/tracepoint.c:tracepoint_probe_unregister
  - kernel/tracepoint.c:tracepoint_add_func
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/trace_events.c:event_trace_del_tracer
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:process_system_preds
  - kernel/trace/trace_events_filter.c:process_system_preds
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_free
  - kernel/trace/trace_events_trigger.c:set_trigger_filter
  - kernel/trace/trace_events_trigger.c:event_trigger_free
  - kernel/trace/trace_events_hist.c:hist_register_trigger
  - kernel/events/core.c:perf_pmu_unregister
  - mm/mmu_notifier.c:mmu_notifier_synchronize
  - mm/mmu_notifier.c:mmu_notifier_unregister
  - mm/mmu_notifier.c:__mmu_notifier_release
  - fs/notify/mark.c:fsnotify_mark_destroy_workfn
  - fs/notify/mark.c:fsnotify_connector_destroy_workfn
  - fs/quota/dquot.c:dquot_disable
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - block/blk-mq.c:blk_mq_quiesce_queue
  - drivers/base/core.c:device_link_release_fn
  - drivers/base/power/wakeup.c:wakeup_source_remove
  - drivers/i2c/i2c-core-base.c:i2c_exit
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:__bind
  - net/core/netpoll.c:__netpoll_cleanup
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_trace_off_set
```
**Symbols:**

```
ffffffff8112e910-ffffffff8112ea1c: synchronize_srcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void synchronize_srcu(struct srcu_struct *ssp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff8114fdf0)
Location: kernel/rcu/srcutree.c:1006
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/sgx/driver.c:sgx_release
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_mmu_notifier_release
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/trace_events.c:event_trace_del_tracer
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:process_system_preds
  - kernel/trace/trace_events_filter.c:process_system_preds
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_free
  - kernel/trace/trace_events_trigger.c:set_trigger_filter
  - kernel/trace/trace_events_trigger.c:event_trigger_free
  - kernel/trace/trace_events_hist.c:hist_register_trigger
  - kernel/events/core.c:perf_pmu_unregister
  - mm/mmu_notifier.c:mmu_notifier_synchronize
  - mm/mmu_notifier.c:mmu_notifier_unregister
  - mm/mmu_notifier.c:__mmu_notifier_release
  - fs/notify/mark.c:fsnotify_mark_destroy_workfn
  - fs/notify/mark.c:fsnotify_connector_destroy_workfn
  - fs/quota/dquot.c:dquot_disable
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - block/blk-mq.c:blk_mq_quiesce_queue
  - drivers/base/core.c:device_link_release_fn
  - drivers/base/power/wakeup.c:wakeup_source_remove
  - drivers/i2c/i2c-core-base.c:i2c_exit
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:__bind
  - net/core/netpoll.c:__netpoll_cleanup
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/core/drop_monitor.c:net_dm_hw_monitor_stop
```
**Symbols:**

```
ffffffff8114fdf0-ffffffff8114fefc: synchronize_srcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void synchronize_srcu(struct srcu_struct *ssp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff81177340)
Location: kernel/rcu/srcutree.c:1291
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/sgx/driver.c:sgx_release
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_mmu_notifier_release
  - kernel/rcu/update.c:rcu_tasks_postscan
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/trace_events.c:event_trace_del_tracer
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:process_system_preds
  - kernel/trace/trace_events_filter.c:process_system_preds
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_free
  - kernel/trace/trace_events_trigger.c:set_trigger_filter
  - kernel/trace/trace_events_trigger.c:event_trigger_free
  - kernel/events/core.c:perf_pmu_unregister
  - mm/mmu_notifier.c:mmu_notifier_synchronize
  - mm/mmu_notifier.c:mmu_notifier_unregister
  - mm/mmu_notifier.c:__mmu_notifier_release
  - fs/notify/mark.c:fsnotify_mark_destroy_workfn
  - fs/notify/mark.c:fsnotify_connector_destroy_workfn
  - fs/quota/dquot.c:dquot_disable
  - fs/proc/vmcore.c:unregister_vmcore_cb
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - block/blk-mq.c:blk_mq_update_nr_requests
  - drivers/base/core.c:device_link_release_fn
  - drivers/base/power/wakeup.c:wakeup_source_remove
  - drivers/i2c/i2c-core-base.c:i2c_exit
  - drivers/md/dm.c:dm_internal_suspend_fast
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:__bind
  - net/core/netpoll.c:__netpoll_cleanup
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/core/drop_monitor.c:net_dm_hw_monitor_stop
```
**Symbols:**

```
ffffffff81177340-ffffffff81177440: synchronize_srcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void synchronize_srcu(struct srcu_struct *ssp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff811ae700)
Location: kernel/rcu/srcutree.c:1360
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/sgx/driver.c:sgx_release
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_mmu_notifier_release
  - kernel/printk/printk.c:console_force_preferred_locked
  - kernel/printk/printk.c:unregister_console_locked
  - kernel/printk/printk.c:console_stop
  - kernel/rcu/update.c:rcu_tasks_postscan
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/trace_events.c:event_trace_del_tracer
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:process_system_preds
  - kernel/trace/trace_events_filter.c:process_system_preds
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_free
  - kernel/trace/trace_events_trigger.c:set_trigger_filter
  - kernel/trace/trace_events_trigger.c:event_trigger_free
  - kernel/trace/rv/rv.c:monitoring_on_write_data
  - kernel/trace/rv/rv.c:enabled_monitors_open
  - kernel/trace/rv/rv_reactors.c:reacting_on_write_data
  - kernel/events/core.c:perf_pmu_unregister
  - mm/mmu_notifier.c:mmu_notifier_synchronize
  - mm/mmu_notifier.c:mmu_notifier_unregister
  - mm/mmu_notifier.c:__mmu_notifier_release
  - fs/notify/mark.c:fsnotify_mark_destroy_workfn
  - fs/notify/mark.c:fsnotify_connector_destroy_workfn
  - fs/quota/dquot.c:dquot_disable
  - fs/proc/vmcore.c:unregister_vmcore_cb
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - block/blk-mq.c:blk_mq_update_nr_requests
  - block/blk-mq.c:blk_mq_timeout_work
  - block/blk-mq.c:blk_mq_quiesce_tagset
  - drivers/base/core.c:device_link_release_fn
  - drivers/base/power/wakeup.c:wakeup_source_remove
  - drivers/dax/super.c:kill_dax
  - drivers/i2c/i2c-core-base.c:i2c_exit
  - drivers/md/dm.c:dm_internal_suspend_fast
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:__bind
  - net/core/netpoll.c:__netpoll_cleanup
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/core/drop_monitor.c:net_dm_hw_monitor_stop
```
**Symbols:**

```
ffffffff811ae700-ffffffff811ae800: synchronize_srcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void synchronize_srcu(struct srcu_struct *ssp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff811c06e0)
Location: kernel/rcu/srcutree.c:1436
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/sgx/driver.c:sgx_release
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_mmu_notifier_release
  - kernel/notifier.c:srcu_notifier_chain_unregister
  - kernel/printk/printk.c:console_force_preferred_locked
  - kernel/printk/printk.c:unregister_console_locked
  - kernel/printk/printk.c:console_stop
  - kernel/rcu/update.c:rcu_tasks_postscan
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/trace_events.c:event_trace_del_tracer
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:process_system_preds
  - kernel/trace/trace_events_filter.c:process_system_preds
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_free
  - kernel/trace/trace_events_trigger.c:set_trigger_filter
  - kernel/trace/trace_events_trigger.c:event_trigger_free
  - kernel/trace/rv/rv.c:monitoring_on_write_data
  - kernel/trace/rv/rv.c:enabled_monitors_open
  - kernel/trace/rv/rv_reactors.c:reacting_on_write_data
  - kernel/events/core.c:perf_pmu_unregister
  - mm/mmu_notifier.c:mmu_notifier_synchronize
  - mm/mmu_notifier.c:mmu_notifier_unregister
  - mm/mmu_notifier.c:__mmu_notifier_release
  - fs/notify/mark.c:fsnotify_mark_destroy_workfn
  - fs/notify/mark.c:fsnotify_connector_destroy_workfn
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:quota_release_workfn
  - fs/proc/vmcore.c:unregister_vmcore_cb
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - block/blk-mq.c:blk_mq_update_nr_requests
  - block/blk-mq.c:blk_mq_timeout_work
  - block/blk-mq.c:blk_mq_quiesce_tagset
  - drivers/base/core.c:device_link_release_fn
  - drivers/base/power/wakeup.c:wakeup_source_remove
  - drivers/dax/super.c:kill_dax
  - drivers/i2c/i2c-core-base.c:i2c_exit
  - drivers/md/dm.c:dm_internal_suspend_fast
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:__bind
  - net/core/netpoll.c:__netpoll_cleanup
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/core/drop_monitor.c:net_dm_hw_monitor_stop
```
**Symbols:**

```
ffffffff811c06e0-ffffffff811c07e2: synchronize_srcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void synchronize_srcu(struct srcu_struct *ssp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff811d0bc0)
Location: kernel/rcu/srcutree.c:1456
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/sgx/driver.c:sgx_release
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_mmu_notifier_release
  - kernel/notifier.c:srcu_notifier_chain_unregister
  - kernel/printk/printk.c:console_force_preferred_locked
  - kernel/printk/printk.c:unregister_console_locked
  - kernel/printk/printk.c:console_stop
  - kernel/printk/printk.c:resume_console
  - kernel/printk/printk.c:suspend_console
  - kernel/rcu/update.c:rcu_tasks_postscan
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/trace_events.c:event_trace_del_tracer
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:process_system_preds
  - kernel/trace/trace_events_filter.c:process_system_preds
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_free
  - kernel/trace/trace_events_trigger.c:set_trigger_filter
  - kernel/trace/trace_events_trigger.c:event_trigger_free
  - kernel/trace/rv/rv.c:monitoring_on_write_data
  - kernel/trace/rv/rv.c:enabled_monitors_open
  - kernel/trace/rv/rv_reactors.c:reacting_on_write_data
  - kernel/events/core.c:perf_pmu_unregister
  - mm/mmu_notifier.c:mmu_notifier_synchronize
  - mm/mmu_notifier.c:mmu_notifier_unregister
  - mm/mmu_notifier.c:__mmu_notifier_release
  - fs/notify/mark.c:fsnotify_mark_destroy_workfn
  - fs/notify/mark.c:fsnotify_connector_destroy_workfn
  - fs/quota/dquot.c:quota_release_workfn
  - fs/proc/vmcore.c:unregister_vmcore_cb
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - block/blk-mq.c:blk_mq_update_nr_requests
  - block/blk-mq.c:blk_mq_timeout_work
  - block/blk-mq.c:blk_mq_quiesce_tagset
  - drivers/base/core.c:device_link_release_fn
  - drivers/base/power/wakeup.c:wakeup_source_remove
  - drivers/dax/super.c:kill_dax
  - drivers/gpu/drm/drm_drv.c:drm_dev_unplug
  - drivers/i2c/i2c-core-base.c:i2c_exit
  - drivers/md/dm.c:dm_internal_suspend_fast
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:__bind
  - net/core/netpoll.c:__netpoll_cleanup
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/core/drop_monitor.c:net_dm_hw_monitor_stop
```
**Symbols:**

```
ffffffff811d0bc0-ffffffff811d0cc2: synchronize_srcu (STB_GLOBAL)
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
void synchronize_srcu(struct srcu_struct *ssp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffff80001018b798)
Location: kernel/rcu/srcutree.c:995
Inline: True
Direct callers:
  - virt/kvm/eventfd.c:kvm_unregister_irq_ack_notifier
  - virt/kvm/eventfd.c:kvm_irqfd_assign
  - virt/kvm/eventfd.c:irqfd_shutdown
  - virt/kvm/eventfd.c:irqfd_resampler_shutdown
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/trace_events.c:event_trace_del_tracer
  - kernel/trace/trace_events.c:ftrace_event_pid_write
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_trigger.c:set_trigger_filter
  - kernel/trace/trace_events_trigger.c:trigger_data_free
  - kernel/trace/trace_events_hist.c:hist_register_trigger
  - kernel/events/core.c:perf_pmu_unregister
  - mm/mmu_notifier.c:mmu_notifier_synchronize
  - mm/mmu_notifier.c:mmu_notifier_unregister
  - mm/mmu_notifier.c:__mmu_notifier_release
  - fs/notify/mark.c:fsnotify_mark_destroy_workfn
  - fs/notify/mark.c:fsnotify_connector_destroy_workfn
  - fs/quota/dquot.c:dquot_disable
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - block/blk-mq.c:blk_mq_quiesce_queue
  - drivers/base/power/wakeup.c:wakeup_source_remove
  - drivers/i2c/i2c-core-base.c:i2c_exit
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:dm_swap_table
  - drivers/md/dm.c:__dm_destroy
  - net/core/netpoll.c:__netpoll_cleanup
  - net/core/drop_monitor.c:net_dm_trace_off_set
```
**Symbols:**

```
ffff80001018b798-ffff80001018b884: synchronize_srcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void synchronize_srcu(struct srcu_struct *ssp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (c03d952c)
Location: kernel/rcu/srcutree.c:995
Inline: True
Direct callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/trace_events.c:event_trace_del_tracer
  - kernel/trace/trace_events.c:ftrace_event_pid_write
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_event_perf.c:perf_trace_event_unreg
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_trigger.c:set_trigger_filter
  - kernel/trace/trace_events_trigger.c:trigger_data_free
  - kernel/events/core.c:perf_pmu_unregister
  - mm/mmu_notifier.c:mmu_notifier_synchronize
  - mm/mmu_notifier.c:mmu_notifier_unregister
  - mm/mmu_notifier.c:__mmu_notifier_release
  - fs/notify/mark.c:fsnotify_mark_destroy_workfn
  - fs/notify/mark.c:fsnotify_connector_destroy_workfn
  - fs/quota/dquot.c:dquot_disable
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - block/blk-mq.c:blk_mq_quiesce_queue
  - drivers/base/power/wakeup.c:wakeup_source_remove
  - drivers/i2c/i2c-core-base.c:i2c_exit
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:dm_swap_table
  - drivers/md/dm.c:__dm_destroy
  - net/core/netpoll.c:__netpoll_cleanup
  - net/core/drop_monitor.c:net_dm_trace_off_set
```
**Symbols:**

```
c03d952c-c03d9610: synchronize_srcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void synchronize_srcu(struct srcu_struct *ssp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (c0000000001e5250)
Location: kernel/rcu/srcutree.c:995
Inline: True
Direct callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/trace_events.c:event_trace_del_tracer
  - kernel/trace/trace_events.c:ftrace_event_pid_write
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_event_perf.c:perf_trace_event_unreg
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_trigger.c:set_trigger_filter
  - kernel/trace/trace_events_trigger.c:trigger_data_free
  - kernel/trace/trace_events_hist.c:hist_register_trigger
  - kernel/events/core.c:perf_pmu_unregister
  - mm/mmu_notifier.c:mmu_notifier_synchronize
  - mm/mmu_notifier.c:mmu_notifier_unregister
  - mm/mmu_notifier.c:__mmu_notifier_release
  - mm/mmu_notifier.c:__mmu_notifier_release
  - fs/notify/mark.c:fsnotify_mark_destroy_workfn
  - fs/notify/mark.c:fsnotify_connector_destroy_workfn
  - fs/quota/dquot.c:dquot_disable
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - block/blk-mq.c:blk_mq_quiesce_queue
  - drivers/base/power/wakeup.c:wakeup_source_remove
  - drivers/i2c/i2c-core-base.c:i2c_exit
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:dm_swap_table
  - drivers/md/dm.c:__dm_destroy
  - net/core/netpoll.c:__netpoll_cleanup
  - net/core/drop_monitor.c:net_dm_trace_off_set
```
**Symbols:**

```
c0000000001e5250-c0000000001e53a0: synchronize_srcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void synchronize_srcu(struct srcu_struct *ssp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffe00011fa40)
Location: kernel/rcu/srcutree.c:995
Inline: True
Direct callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/trace_events.c:event_trace_del_tracer
  - kernel/trace/trace_events.c:ftrace_event_pid_write
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_event_perf.c:perf_trace_event_unreg
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_trigger.c:set_trigger_filter
  - kernel/trace/trace_events_trigger.c:trigger_data_free
  - kernel/events/core.c:perf_pmu_unregister
  - mm/mmu_notifier.c:mmu_notifier_synchronize
  - mm/mmu_notifier.c:mmu_notifier_unregister
  - mm/mmu_notifier.c:__mmu_notifier_release
  - fs/notify/mark.c:fsnotify_mark_destroy_workfn
  - fs/notify/mark.c:fsnotify_connector_destroy_workfn
  - fs/quota/dquot.c:dquot_disable
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - block/blk-mq.c:blk_mq_quiesce_queue
  - drivers/i2c/i2c-core-base.c:i2c_exit
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:dm_swap_table
  - drivers/md/dm.c:__dm_destroy
  - net/core/netpoll.c:__netpoll_cleanup
  - net/core/drop_monitor.c:net_dm_trace_off_set
```
**Symbols:**

```
ffffffe00011fa40-ffffffe00011fb10: synchronize_srcu (STB_GLOBAL)
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
void synchronize_srcu(struct srcu_struct *ssp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff8111d740)
Location: kernel/rcu/srcutree.c:995
Inline: True
Direct callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/trace_events.c:event_trace_del_tracer
  - kernel/trace/trace_events.c:ftrace_event_pid_write
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_trigger.c:set_trigger_filter
  - kernel/trace/trace_events_trigger.c:trigger_data_free
  - kernel/trace/trace_events_hist.c:hist_register_trigger
  - kernel/events/core.c:perf_pmu_unregister
  - mm/mmu_notifier.c:mmu_notifier_synchronize
  - mm/mmu_notifier.c:mmu_notifier_unregister
  - mm/mmu_notifier.c:__mmu_notifier_release
  - fs/notify/mark.c:fsnotify_mark_destroy_workfn
  - fs/notify/mark.c:fsnotify_connector_destroy_workfn
  - fs/quota/dquot.c:dquot_disable
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - block/blk-mq.c:blk_mq_quiesce_queue
  - drivers/base/power/wakeup.c:wakeup_source_remove
  - drivers/nvme/host/multipath.c:nvme_mpath_set_live
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:dm_swap_table
  - drivers/md/dm.c:__dm_destroy
  - net/core/netpoll.c:__netpoll_cleanup
  - net/core/drop_monitor.c:net_dm_trace_off_set
```
**Symbols:**

```
ffffffff8111d740-ffffffff8111d81c: synchronize_srcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void synchronize_srcu(struct srcu_struct *ssp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff8110e7f0)
Location: kernel/rcu/srcutree.c:995
Inline: True
Direct callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/trace_events.c:event_trace_del_tracer
  - kernel/trace/trace_events.c:ftrace_event_pid_write
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_trigger.c:set_trigger_filter
  - kernel/trace/trace_events_trigger.c:trigger_data_free
  - kernel/trace/trace_events_hist.c:hist_register_trigger
  - kernel/events/core.c:perf_pmu_unregister
  - mm/mmu_notifier.c:mmu_notifier_synchronize
  - mm/mmu_notifier.c:mmu_notifier_unregister
  - mm/mmu_notifier.c:__mmu_notifier_release
  - fs/notify/mark.c:fsnotify_mark_destroy_workfn
  - fs/notify/mark.c:fsnotify_connector_destroy_workfn
  - fs/quota/dquot.c:dquot_disable
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - block/blk-mq.c:blk_mq_quiesce_queue
  - drivers/base/power/wakeup.c:wakeup_source_remove
  - drivers/nvme/host/multipath.c:nvme_mpath_set_live
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:dm_swap_table
  - drivers/md/dm.c:__dm_destroy
  - net/core/netpoll.c:__netpoll_cleanup
  - net/core/drop_monitor.c:net_dm_trace_off_set
```
**Symbols:**

```
ffffffff8110e7f0-ffffffff8110e8b1: synchronize_srcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void synchronize_srcu(struct srcu_struct *ssp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff8111b630)
Location: kernel/rcu/srcutree.c:995
Inline: True
Direct callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/trace_events.c:event_trace_del_tracer
  - kernel/trace/trace_events.c:ftrace_event_pid_write
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_trigger.c:set_trigger_filter
  - kernel/trace/trace_events_trigger.c:trigger_data_free
  - kernel/trace/trace_events_hist.c:hist_register_trigger
  - kernel/events/core.c:perf_pmu_unregister
  - mm/mmu_notifier.c:mmu_notifier_synchronize
  - mm/mmu_notifier.c:mmu_notifier_unregister
  - mm/mmu_notifier.c:__mmu_notifier_release
  - fs/notify/mark.c:fsnotify_mark_destroy_workfn
  - fs/notify/mark.c:fsnotify_connector_destroy_workfn
  - fs/quota/dquot.c:dquot_disable
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - block/blk-mq.c:blk_mq_quiesce_queue
  - drivers/base/power/wakeup.c:wakeup_source_remove
  - drivers/i2c/i2c-core-base.c:i2c_exit
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:dm_swap_table
  - drivers/md/dm.c:__dm_destroy
  - net/core/netpoll.c:__netpoll_cleanup
  - net/core/drop_monitor.c:net_dm_trace_off_set
```
**Symbols:**

```
ffffffff8111b630-ffffffff8111b70c: synchronize_srcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void synchronize_srcu(struct srcu_struct *ssp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff811275f0)
Location: kernel/rcu/srcutree.c:995
Inline: True
Direct callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/trace_events.c:event_trace_del_tracer
  - kernel/trace/trace_events.c:ftrace_event_pid_write
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_trigger.c:set_trigger_filter
  - kernel/trace/trace_events_trigger.c:trigger_data_free
  - kernel/trace/trace_events_hist.c:hist_register_trigger
  - kernel/events/core.c:perf_pmu_unregister
  - mm/mmu_notifier.c:mmu_notifier_synchronize
  - mm/mmu_notifier.c:mmu_notifier_unregister
  - mm/mmu_notifier.c:__mmu_notifier_release
  - fs/notify/mark.c:fsnotify_mark_destroy_workfn
  - fs/notify/mark.c:fsnotify_connector_destroy_workfn
  - fs/quota/dquot.c:dquot_disable
  - security/tomoyo/gc.c:tomoyo_try_to_gc
  - block/blk-mq.c:blk_mq_quiesce_queue
  - drivers/base/power/wakeup.c:wakeup_source_remove
  - drivers/i2c/i2c-core-base.c:i2c_exit
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:dm_swap_table
  - drivers/md/dm.c:__dm_destroy
  - net/core/netpoll.c:__netpoll_cleanup
  - net/core/drop_monitor.c:net_dm_trace_off_set
```
**Symbols:**

```
ffffffff811275f0-ffffffff811276cc: synchronize_srcu (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct srcu_struct *ssp</code>
</li>
<li>
<b>Param removed. </b>
<code>struct srcu_struct *sp</code>
</li>
</ul>
</details>
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
