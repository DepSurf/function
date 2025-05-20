# Function: <code>ktime_get</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
ktime_t ktime_get();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff810f56a0)
Location: kernel/time/timekeeping.c:682
Inline: False
Direct callers:
  - init/main.c:do_one_initcall
  - init/main.c:do_one_initcall
  - kernel/fork.c:copy_process
  - kernel/async.c:async_run_entry_fn
  - kernel/async.c:async_run_entry_fn
  - kernel/async.c:async_synchronize_cookie_domain
  - kernel/async.c:async_synchronize_cookie_domain
  - kernel/sched/clock.c:sched_clock_init
  - kernel/sched/debug.c:sched_debug_header
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image
  - kernel/power/swap.c:save_image
  - kernel/power/swap.c:save_image
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/wakelock.c:__wakelocks_gc
  - kernel/time/timer_list.c:timer_list_start
  - kernel/time/timer_list.c:sysrq_timer_list_show
  - kernel/time/clockevents.c:clockevents_program_min_delta
  - kernel/time/clockevents.c:clockevents_program_event
  - kernel/time/tick-common.c:tick_setup_device
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-oneshot.c:tick_resume_oneshot
  - kernel/time/tick-sched.c:get_cpu_idle_time_us
  - kernel/time/tick-sched.c:get_cpu_iowait_time_us
  - kernel/time/tick-sched.c:tick_sched_timer
  - kernel/time/tick-sched.c:tick_nohz_handler
  - kernel/time/tick-sched.c:__tick_nohz_idle_enter
  - kernel/time/tick-sched.c:tick_nohz_idle_exit
  - kernel/time/tick-sched.c:tick_irq_enter
  - kernel/time/tick-sched.c:tick_setup_sched_timer
  - kernel/time/timer_stats.c:tstats_show
  - kernel/time/timer_stats.c:tstats_write
  - kernel/time/timer_stats.c:tstats_write
  - kernel/futex.c:SyS_futex
  - kernel/futex_compat.c:compat_SyS_futex
  - kernel/acct.c:do_acct_process
  - kernel/delayacct.c:delayacct_end
  - kernel/delayacct.c:__delayacct_blkio_start
  - kernel/delayacct.c:__delayacct_freepages_start
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/trace/blktrace.c:__blk_add_trace
  - fs/ext4/extents_status.c:__es_shrink
  - fs/ext4/extents_status.c:__es_shrink
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - drivers/pci/quirks.c:pci_do_fixups
  - drivers/pci/quirks.c:pci_do_fixups
  - drivers/acpi/osl.c:acpi_os_get_timer
  - drivers/connector/cn_proc.c:proc_fork_connector
  - drivers/connector/cn_proc.c:proc_exec_connector
  - drivers/connector/cn_proc.c:proc_id_connector
  - drivers/connector/cn_proc.c:proc_sid_connector
  - drivers/connector/cn_proc.c:proc_ptrace_connector
  - drivers/connector/cn_proc.c:proc_comm_connector
  - drivers/connector/cn_proc.c:proc_coredump_connector
  - drivers/connector/cn_proc.c:proc_exit_connector
  - drivers/base/power/main.c:initcall_debug_start
  - drivers/base/power/main.c:dpm_show_time
  - drivers/base/power/main.c:dpm_resume_noirq
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/wakeup.c:wakeup_source_add
  - drivers/base/power/wakeup.c:wakeup_source_report_event
  - drivers/base/power/wakeup.c:print_wakeup_source_stats
  - drivers/dma-buf/fence.c:fence_signal_locked
  - drivers/usb/host/ehci-hcd.c:ehci_enable_event
  - drivers/usb/host/ehci-hcd.c:ehci_hrtimer_func
  - drivers/input/evdev.c:__evdev_queue_syn_dropped
  - drivers/input/evdev.c:evdev_events
  - drivers/power/charger-manager.c:try_charger_enable
  - drivers/power/charger-manager.c:try_charger_enable
  - drivers/md/dm.c:dm_start_request
  - drivers/md/dm.c:dm_request_fn
  - drivers/md/dm-stats.c:dm_stats_account_io
  - drivers/md/dm-stats.c:dm_stats_account_io
  - drivers/cpufreq/cpufreq_governor.c:dbs_timer
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_governor_dbs
  - drivers/cpufreq/intel_pstate.c:intel_pstate_timer_func
  - drivers/cpufreq/intel_pstate.c:intel_hwp_timer_func
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
```
**Symbols:**

```
ffffffff810f56a0-ffffffff810f5744: ktime_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
ktime_t ktime_get();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff810fc7a0)
Location: kernel/time/timekeeping.c:687
Inline: False
Direct callers:
  - kernel/async.c:async_synchronize_cookie_domain
  - kernel/async.c:async_synchronize_cookie_domain
  - kernel/async.c:async_run_entry_fn
  - kernel/async.c:async_run_entry_fn
  - kernel/sched/clock.c:sched_clock_init
  - kernel/sched/debug.c:sched_debug_header
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image
  - kernel/power/swap.c:save_image
  - kernel/power/swap.c:save_image
  - kernel/power/wakelock.c:__wakelocks_gc
  - kernel/time/timer_list.c:timer_list_start
  - kernel/time/timer_list.c:sysrq_timer_list_show
  - kernel/time/clockevents.c:clockevents_program_event
  - kernel/time/clockevents.c:clockevents_program_min_delta
  - kernel/time/tick-common.c:tick_setup_device
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-oneshot.c:tick_resume_oneshot
  - kernel/time/tick-sched.c:tick_setup_sched_timer
  - kernel/time/tick-sched.c:tick_sched_timer
  - kernel/time/tick-sched.c:tick_irq_enter
  - kernel/time/tick-sched.c:tick_nohz_handler
  - kernel/time/tick-sched.c:tick_nohz_idle_exit
  - kernel/time/tick-sched.c:__tick_nohz_idle_enter
  - kernel/time/tick-sched.c:get_cpu_iowait_time_us
  - kernel/time/tick-sched.c:get_cpu_idle_time_us
  - kernel/time/timer_stats.c:tstats_write
  - kernel/time/timer_stats.c:tstats_write
  - kernel/time/timer_stats.c:tstats_show
  - kernel/futex.c:SyS_futex
  - kernel/futex_compat.c:compat_SyS_futex
  - kernel/acct.c:do_acct_process
  - kernel/delayacct.c:__delayacct_freepages_start
  - kernel/delayacct.c:__delayacct_blkio_start
  - kernel/delayacct.c:delayacct_end
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/trace/blktrace.c:__blk_add_trace
  - fs/ext4/extents_status.c:__es_shrink
  - fs/ext4/extents_status.c:__es_shrink
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - crypto/jitterentropy-kcapi.c:jent_get_nstime
  - block/cfq-iosched.c:cfq_init_queue
  - block/cfq-iosched.c:cfq_init_queue
  - block/cfq-iosched.c:cfq_idle_slice_timer
  - block/cfq-iosched.c:cfq_completed_request
  - block/cfq-iosched.c:cfq_completed_request
  - block/cfq-iosched.c:cfq_completed_request
  - block/cfq-iosched.c:cfq_completed_request
  - block/cfq-iosched.c:cfq_insert_request
  - block/cfq-iosched.c:cfq_insert_request
  - block/cfq-iosched.c:__cfq_update_io_thinktime
  - block/cfq-iosched.c:cfq_init_icq
  - block/cfq-iosched.c:cfq_dispatch_requests
  - block/cfq-iosched.c:cfq_dispatch_requests
  - block/cfq-iosched.c:cfq_dispatch_requests
  - block/cfq-iosched.c:cfq_dispatch_requests
  - block/cfq-iosched.c:cfq_dispatch_requests
  - block/cfq-iosched.c:cfq_dispatch_requests
  - block/cfq-iosched.c:cfq_dispatch_requests
  - block/cfq-iosched.c:cfq_check_fifo
  - block/cfq-iosched.c:cfq_arm_slice_timer
  - block/cfq-iosched.c:__cfq_slice_expired
  - block/cfq-iosched.c:__cfq_set_active_queue
  - block/cfq-iosched.c:cfq_service_tree_add
  - block/cfq-iosched.c:cfq_pd_alloc
  - block/cfq-iosched.c:cfq_pd_alloc
  - block/cfq-iosched.c:cfq_pd_alloc
  - block/cfq-iosched.c:cfq_group_served
  - block/cfq-iosched.c:cfq_group_served
  - block/cfq-iosched.c:cfq_set_prio_slice
  - drivers/pci/quirks.c:pci_do_fixups
  - drivers/pci/quirks.c:pci_do_fixups
  - drivers/acpi/osl.c:acpi_os_get_timer
  - drivers/connector/cn_proc.c:proc_exit_connector
  - drivers/connector/cn_proc.c:proc_coredump_connector
  - drivers/connector/cn_proc.c:proc_comm_connector
  - drivers/connector/cn_proc.c:proc_ptrace_connector
  - drivers/connector/cn_proc.c:proc_sid_connector
  - drivers/connector/cn_proc.c:proc_id_connector
  - drivers/connector/cn_proc.c:proc_exec_connector
  - drivers/connector/cn_proc.c:proc_fork_connector
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_noirq
  - drivers/base/power/main.c:dpm_show_time
  - drivers/base/power/main.c:initcall_debug_start
  - drivers/base/power/wakeup.c:print_wakeup_source_stats
  - drivers/base/power/wakeup.c:wakeup_source_report_event
  - drivers/base/power/wakeup.c:wakeup_source_add
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_runtime_suspend
  - drivers/base/power/domain.c:genpd_runtime_suspend
  - drivers/base/power/domain.c:genpd_power_off
  - drivers/base/power/domain.c:genpd_power_off
  - drivers/base/power/domain.c:genpd_power_on
  - drivers/base/power/domain.c:genpd_power_on
  - drivers/dma-buf/fence.c:fence_signal_locked
  - drivers/usb/host/ehci-hcd.c:ehci_hrtimer_func
  - drivers/usb/host/ehci-hcd.c:ehci_enable_event
  - drivers/input/evdev.c:evdev_events
  - drivers/input/evdev.c:__evdev_queue_syn_dropped
  - drivers/power/charger-manager.c:try_charger_enable
  - drivers/power/charger-manager.c:try_charger_enable
  - drivers/md/dm-stats.c:dm_stats_account_io
  - drivers/md/dm-stats.c:dm_stats_account_io
  - drivers/md/dm-rq.c:dm_old_request_fn
  - drivers/md/dm-rq.c:dm_start_request
```
**Symbols:**

```
ffffffff810fc7a0-ffffffff810fc848: ktime_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
ktime_t ktime_get();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff810ff6c0)
Location: kernel/time/timekeeping.c:716
Inline: False
Direct callers:
  - kernel/async.c:async_synchronize_cookie_domain
  - kernel/async.c:async_synchronize_cookie_domain
  - kernel/async.c:async_run_entry_fn
  - kernel/async.c:async_run_entry_fn
  - kernel/sched/clock.c:sched_clock_init
  - kernel/sched/debug.c:sched_debug_header
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image
  - kernel/power/swap.c:save_image
  - kernel/power/swap.c:save_image
  - kernel/power/wakelock.c:__wakelocks_gc
  - kernel/time/timer.c:usleep_range
  - kernel/time/timer_list.c:timer_list_start
  - kernel/time/timer_list.c:sysrq_timer_list_show
  - kernel/time/clockevents.c:clockevents_program_event
  - kernel/time/clockevents.c:clockevents_program_min_delta
  - kernel/time/tick-common.c:tick_setup_device
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-oneshot.c:tick_resume_oneshot
  - kernel/time/tick-sched.c:tick_setup_sched_timer
  - kernel/time/tick-sched.c:tick_sched_timer
  - kernel/time/tick-sched.c:tick_irq_enter
  - kernel/time/tick-sched.c:tick_nohz_handler
  - kernel/time/tick-sched.c:tick_nohz_idle_exit
  - kernel/time/tick-sched.c:get_cpu_iowait_time_us
  - kernel/time/tick-sched.c:get_cpu_idle_time_us
  - kernel/time/timer_stats.c:tstats_write
  - kernel/time/timer_stats.c:tstats_write
  - kernel/time/timer_stats.c:tstats_show
  - kernel/futex.c:SyS_futex
  - kernel/futex_compat.c:compat_SyS_futex
  - kernel/acct.c:do_acct_process
  - kernel/delayacct.c:__delayacct_freepages_start
  - kernel/delayacct.c:__delayacct_blkio_start
  - kernel/delayacct.c:delayacct_end
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/trace/blktrace.c:__blk_add_trace
  - fs/ext4/extents_status.c:__es_shrink
  - fs/ext4/extents_status.c:__es_shrink
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - crypto/jitterentropy-kcapi.c:jent_get_nstime
  - block/blk-stat.c:blk_stat_set_issue_time
  - block/blk-stat.c:blk_stat_clear
  - block/blk-stat.c:blk_stat_clear
  - block/blk-stat.c:blk_stat_clear
  - block/blk-stat.c:blk_stat_clear
  - block/blk-stat.c:blk_stat_add
  - block/blk-stat.c:blk_stat_is_current
  - block/blk-stat.c:blk_queue_stat_get
  - block/blk-stat.c:blk_queue_stat_get
  - block/cfq-iosched.c:cfq_init_queue
  - block/cfq-iosched.c:cfq_init_queue
  - block/cfq-iosched.c:cfq_idle_slice_timer
  - block/cfq-iosched.c:cfq_completed_request
  - block/cfq-iosched.c:cfq_completed_request
  - block/cfq-iosched.c:cfq_completed_request
  - block/cfq-iosched.c:cfq_completed_request
  - block/cfq-iosched.c:cfq_insert_request
  - block/cfq-iosched.c:cfq_insert_request
  - block/cfq-iosched.c:__cfq_update_io_thinktime
  - block/cfq-iosched.c:cfq_init_icq
  - block/cfq-iosched.c:cfq_dispatch_requests
  - block/cfq-iosched.c:cfq_dispatch_requests
  - block/cfq-iosched.c:cfq_dispatch_requests
  - block/cfq-iosched.c:cfq_dispatch_requests
  - block/cfq-iosched.c:cfq_dispatch_requests
  - block/cfq-iosched.c:cfq_dispatch_request
  - block/cfq-iosched.c:cfq_dispatch_request
  - block/cfq-iosched.c:cfq_dispatch_request
  - block/cfq-iosched.c:cfq_arm_slice_timer
  - block/cfq-iosched.c:__cfq_slice_expired
  - block/cfq-iosched.c:__cfq_set_active_queue
  - block/cfq-iosched.c:cfq_service_tree_add
  - block/cfq-iosched.c:cfq_pd_alloc
  - block/cfq-iosched.c:cfq_pd_alloc
  - block/cfq-iosched.c:cfq_pd_alloc
  - block/cfq-iosched.c:cfq_group_served
  - block/cfq-iosched.c:cfq_group_served
  - block/cfq-iosched.c:cfq_set_prio_slice
  - block/blk-wbt.c:wb_timer_fn
  - drivers/pci/quirks.c:pci_do_fixups
  - drivers/pci/quirks.c:pci_do_fixups
  - drivers/acpi/osl.c:acpi_os_get_timer
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/button.c:acpi_lid_notify_state
  - drivers/acpi/button.c:acpi_lid_notify_state
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
  - drivers/acpi/cppc_acpi.c:check_pcc_chan
  - drivers/acpi/cppc_acpi.c:check_pcc_chan
  - drivers/connector/cn_proc.c:proc_exit_connector
  - drivers/connector/cn_proc.c:proc_coredump_connector
  - drivers/connector/cn_proc.c:proc_comm_connector
  - drivers/connector/cn_proc.c:proc_ptrace_connector
  - drivers/connector/cn_proc.c:proc_sid_connector
  - drivers/connector/cn_proc.c:proc_id_connector
  - drivers/connector/cn_proc.c:proc_exec_connector
  - drivers/connector/cn_proc.c:proc_fork_connector
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_noirq
  - drivers/base/power/main.c:dpm_show_time
  - drivers/base/power/wakeup.c:print_wakeup_source_stats
  - drivers/base/power/wakeup.c:wakeup_source_report_event
  - drivers/base/power/wakeup.c:wakeup_source_add
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_runtime_suspend
  - drivers/base/power/domain.c:genpd_runtime_suspend
  - drivers/base/power/domain.c:genpd_power_off
  - drivers/base/power/domain.c:genpd_power_off
  - drivers/base/power/domain.c:genpd_power_on
  - drivers/base/power/domain.c:genpd_power_on
  - drivers/misc/sram.c:atmel_securam_wait
  - drivers/misc/sram.c:atmel_securam_wait
  - drivers/dma-buf/dma-fence.c:dma_fence_signal_locked
  - drivers/usb/host/ehci-hcd.c:ehci_hrtimer_func
  - drivers/input/evdev.c:evdev_events
  - drivers/input/evdev.c:__evdev_queue_syn_dropped
  - drivers/power/supply/charger-manager.c:try_charger_enable
  - drivers/power/supply/charger-manager.c:try_charger_enable
  - drivers/md/dm-stats.c:dm_stats_account_io
  - drivers/md/dm-stats.c:dm_stats_account_io
  - drivers/md/dm-rq.c:dm_old_request_fn
  - drivers/md/dm-rq.c:dm_start_request
```
**Symbols:**

```
ffffffff810ff6c0-ffffffff810ff768: ktime_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
ktime_t ktime_get();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81101bd0)
Location: kernel/time/timekeeping.c:748
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_snapshot_khz
  - kernel/async.c:async_synchronize_cookie_domain
  - kernel/async.c:async_synchronize_cookie_domain
  - kernel/async.c:async_run_entry_fn
  - kernel/async.c:async_run_entry_fn
  - kernel/sched/clock.c:sched_clock_tick_stable
  - kernel/sched/clock.c:__sched_clock_work
  - kernel/sched/debug.c:sched_debug_header
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image
  - kernel/power/swap.c:save_image
  - kernel/power/swap.c:save_image
  - kernel/power/wakelock.c:__wakelocks_gc
  - kernel/time/timer.c:usleep_range
  - kernel/time/timer_list.c:timer_list_start
  - kernel/time/timer_list.c:sysrq_timer_list_show
  - kernel/time/clockevents.c:clockevents_program_event
  - kernel/time/clockevents.c:clockevents_program_min_delta
  - kernel/time/tick-common.c:tick_setup_device
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-oneshot.c:tick_resume_oneshot
  - kernel/time/tick-sched.c:tick_setup_sched_timer
  - kernel/time/tick-sched.c:tick_sched_timer
  - kernel/time/tick-sched.c:tick_irq_enter
  - kernel/time/tick-sched.c:tick_nohz_handler
  - kernel/time/tick-sched.c:tick_nohz_idle_exit
  - kernel/time/tick-sched.c:__tick_nohz_idle_enter
  - kernel/time/tick-sched.c:get_cpu_iowait_time_us
  - kernel/time/tick-sched.c:get_cpu_idle_time_us
  - kernel/futex.c:SyS_futex
  - kernel/futex_compat.c:compat_SyS_futex
  - kernel/acct.c:do_acct_process
  - kernel/delayacct.c:__delayacct_freepages_start
  - kernel/delayacct.c:__delayacct_blkio_start
  - kernel/delayacct.c:delayacct_end
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/trace/blktrace.c:__blk_add_trace
  - fs/ext4/extents_status.c:__es_shrink
  - fs/ext4/extents_status.c:__es_shrink
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - crypto/jitterentropy-kcapi.c:jent_get_nstime
  - block/blk-core.c:blk_start_request
  - block/blk-mq.c:blk_mq_start_request
  - block/blk-stat.c:blk_stat_add
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:throtl_tg_is_idle
  - block/cfq-iosched.c:cfq_init_queue
  - block/cfq-iosched.c:cfq_init_queue
  - block/cfq-iosched.c:cfq_idle_slice_timer
  - block/cfq-iosched.c:cfq_completed_request
  - block/cfq-iosched.c:cfq_completed_request
  - block/cfq-iosched.c:cfq_completed_request
  - block/cfq-iosched.c:cfq_completed_request
  - block/cfq-iosched.c:cfq_insert_request
  - block/cfq-iosched.c:cfq_insert_request
  - block/cfq-iosched.c:__cfq_update_io_thinktime
  - block/cfq-iosched.c:cfq_init_icq
  - block/cfq-iosched.c:cfq_dispatch_requests
  - block/cfq-iosched.c:cfq_dispatch_requests
  - block/cfq-iosched.c:cfq_dispatch_requests
  - block/cfq-iosched.c:cfq_dispatch_requests
  - block/cfq-iosched.c:cfq_dispatch_requests
  - block/cfq-iosched.c:cfq_dispatch_request
  - block/cfq-iosched.c:cfq_dispatch_request
  - block/cfq-iosched.c:cfq_dispatch_request
  - block/cfq-iosched.c:cfq_arm_slice_timer
  - block/cfq-iosched.c:__cfq_slice_expired
  - block/cfq-iosched.c:__cfq_set_active_queue
  - block/cfq-iosched.c:cfq_service_tree_add
  - block/cfq-iosched.c:cfq_pd_alloc
  - block/cfq-iosched.c:cfq_pd_alloc
  - block/cfq-iosched.c:cfq_pd_alloc
  - block/cfq-iosched.c:cfq_group_served
  - block/cfq-iosched.c:cfq_group_served
  - block/cfq-iosched.c:cfq_set_prio_slice
  - block/blk-wbt.c:wb_timer_fn
  - drivers/pci/quirks.c:pci_do_fixups
  - drivers/pci/quirks.c:pci_do_fixups
  - drivers/acpi/osl.c:acpi_os_get_timer
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/button.c:acpi_lid_notify_state
  - drivers/acpi/button.c:acpi_lid_notify_state
  - drivers/acpi/button.c:acpi_lid_notify_state
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
  - drivers/acpi/cppc_acpi.c:check_pcc_chan
  - drivers/acpi/cppc_acpi.c:check_pcc_chan
  - drivers/connector/cn_proc.c:proc_exit_connector
  - drivers/connector/cn_proc.c:proc_coredump_connector
  - drivers/connector/cn_proc.c:proc_comm_connector
  - drivers/connector/cn_proc.c:proc_ptrace_connector
  - drivers/connector/cn_proc.c:proc_sid_connector
  - drivers/connector/cn_proc.c:proc_id_connector
  - drivers/connector/cn_proc.c:proc_exec_connector
  - drivers/connector/cn_proc.c:proc_fork_connector
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_noirq
  - drivers/base/power/main.c:dpm_show_time
  - drivers/base/power/wakeup.c:print_wakeup_source_stats
  - drivers/base/power/wakeup.c:wakeup_source_add
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_runtime_suspend
  - drivers/base/power/domain.c:genpd_runtime_suspend
  - drivers/base/power/domain.c:_genpd_power_off
  - drivers/base/power/domain.c:_genpd_power_off
  - drivers/base/power/domain.c:_genpd_power_on
  - drivers/base/power/domain.c:_genpd_power_on
  - drivers/misc/sram.c:atmel_securam_wait
  - drivers/misc/sram.c:atmel_securam_wait
  - drivers/dma-buf/dma-fence.c:dma_fence_signal_locked
  - drivers/usb/host/ehci-hcd.c:ehci_hrtimer_func
  - drivers/input/evdev.c:evdev_events
  - drivers/input/evdev.c:__evdev_queue_syn_dropped
  - drivers/power/supply/charger-manager.c:try_charger_enable
  - drivers/power/supply/charger-manager.c:try_charger_enable
  - drivers/md/dm-stats.c:dm_stats_account_io
  - drivers/md/dm-stats.c:dm_stats_account_io
  - drivers/md/dm-rq.c:dm_old_request_fn
  - drivers/md/dm-rq.c:dm_start_request
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
  - net/ipv4/tcp_output.c:tcp_transmit_skb
```
**Symbols:**

```
ffffffff81101bd0-ffffffff81101c65: ktime_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
ktime_t ktime_get();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff8110cad0)
Location: kernel/time/timekeeping.c:752
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_get_on_cpu
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_prepare_all
  - arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_get_khz
  - arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_snapshot_khz
  - kernel/async.c:async_synchronize_cookie_domain
  - kernel/async.c:async_synchronize_cookie_domain
  - kernel/async.c:async_run_entry_fn
  - kernel/async.c:async_run_entry_fn
  - kernel/sched/clock.c:sched_clock_tick_stable
  - kernel/sched/clock.c:__sched_clock_work
  - kernel/sched/debug.c:sched_debug_header
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image
  - kernel/power/swap.c:save_image
  - kernel/power/swap.c:save_image
  - kernel/power/wakelock.c:__wakelocks_gc
  - kernel/time/timer.c:usleep_range
  - kernel/time/timer_list.c:timer_list_start
  - kernel/time/timer_list.c:sysrq_timer_list_show
  - kernel/time/clockevents.c:clockevents_program_event
  - kernel/time/clockevents.c:clockevents_program_min_delta
  - kernel/time/tick-common.c:tick_setup_device
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-oneshot.c:tick_resume_oneshot
  - kernel/time/tick-sched.c:tick_setup_sched_timer
  - kernel/time/tick-sched.c:tick_sched_timer
  - kernel/time/tick-sched.c:tick_irq_enter
  - kernel/time/tick-sched.c:tick_nohz_handler
  - kernel/time/tick-sched.c:tick_nohz_idle_exit
  - kernel/time/tick-sched.c:__tick_nohz_idle_enter
  - kernel/time/tick-sched.c:get_cpu_iowait_time_us
  - kernel/time/tick-sched.c:get_cpu_idle_time_us
  - kernel/futex.c:SyS_futex
  - kernel/futex_compat.c:compat_SyS_futex
  - kernel/acct.c:do_acct_process
  - kernel/delayacct.c:__delayacct_freepages_start
  - kernel/delayacct.c:__delayacct_blkio_start
  - kernel/delayacct.c:delayacct_end
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/trace/blktrace.c:__blk_add_trace
  - fs/ext4/extents_status.c:__es_shrink
  - fs/ext4/extents_status.c:__es_shrink
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - crypto/jitterentropy-kcapi.c:jent_get_nstime
  - block/blk-core.c:blk_start_request
  - block/blk-mq.c:blk_mq_start_request
  - block/blk-stat.c:blk_stat_add
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:throtl_tg_is_idle
  - block/cfq-iosched.c:cfq_init_queue
  - block/cfq-iosched.c:cfq_init_queue
  - block/cfq-iosched.c:cfq_idle_slice_timer
  - block/cfq-iosched.c:cfq_completed_request
  - block/cfq-iosched.c:cfq_completed_request
  - block/cfq-iosched.c:cfq_completed_request
  - block/cfq-iosched.c:cfq_completed_request
  - block/cfq-iosched.c:cfq_completed_request
  - block/cfq-iosched.c:cfq_completed_request
  - block/cfq-iosched.c:cfq_insert_request
  - block/cfq-iosched.c:cfq_insert_request
  - block/cfq-iosched.c:__cfq_update_io_thinktime
  - block/cfq-iosched.c:cfq_init_icq
  - block/cfq-iosched.c:cfq_dispatch_requests
  - block/cfq-iosched.c:cfq_dispatch_requests
  - block/cfq-iosched.c:cfq_dispatch_requests
  - block/cfq-iosched.c:cfq_dispatch_requests
  - block/cfq-iosched.c:cfq_dispatch_requests
  - block/cfq-iosched.c:cfq_dispatch_requests
  - block/cfq-iosched.c:cfq_dispatch_requests
  - block/cfq-iosched.c:cfq_dispatch_requests
  - block/cfq-iosched.c:__cfq_slice_expired
  - block/cfq-iosched.c:__cfq_slice_expired
  - block/cfq-iosched.c:__cfq_slice_expired
  - block/cfq-iosched.c:__cfq_set_active_queue
  - block/cfq-iosched.c:cfq_service_tree_add
  - block/cfq-iosched.c:cfq_pd_alloc
  - block/cfq-iosched.c:cfq_pd_alloc
  - block/cfq-iosched.c:cfq_pd_alloc
  - block/blk-wbt.c:wb_timer_fn
  - drivers/pci/quirks.c:pci_do_fixups
  - drivers/pci/quirks.c:pci_do_fixups
  - drivers/acpi/osl.c:acpi_os_get_timer
  - drivers/acpi/button.c:acpi_lid_input_open
  - drivers/acpi/button.c:acpi_lid_notify_state
  - drivers/acpi/button.c:acpi_lid_notify_state
  - drivers/acpi/button.c:acpi_lid_notify_state
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
  - drivers/acpi/cppc_acpi.c:check_pcc_chan
  - drivers/acpi/cppc_acpi.c:check_pcc_chan
  - drivers/connector/cn_proc.c:proc_exit_connector
  - drivers/connector/cn_proc.c:proc_coredump_connector
  - drivers/connector/cn_proc.c:proc_comm_connector
  - drivers/connector/cn_proc.c:proc_ptrace_connector
  - drivers/connector/cn_proc.c:proc_sid_connector
  - drivers/connector/cn_proc.c:proc_id_connector
  - drivers/connector/cn_proc.c:proc_exec_connector
  - drivers/connector/cn_proc.c:proc_fork_connector
  - drivers/base/dd.c:deferred_probe_work_func
  - drivers/base/dd.c:deferred_probe_work_func
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_noirq_resume_devices
  - drivers/base/power/main.c:dpm_show_time
  - drivers/base/power/wakeup.c:print_wakeup_source_stats
  - drivers/base/power/wakeup.c:wakeup_source_add
  - drivers/base/power/domain.c:genpd_total_idle_time_show
  - drivers/base/power/domain.c:genpd_active_time_show
  - drivers/base/power/domain.c:genpd_idle_states_show
  - drivers/base/power/domain.c:pm_genpd_init
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_runtime_suspend
  - drivers/base/power/domain.c:genpd_runtime_suspend
  - drivers/base/power/domain.c:_genpd_power_off
  - drivers/base/power/domain.c:_genpd_power_off
  - drivers/base/power/domain.c:_genpd_power_on
  - drivers/base/power/domain.c:_genpd_power_on
  - drivers/base/power/domain.c:genpd_update_accounting
  - drivers/misc/sram.c:atmel_securam_wait
  - drivers/misc/sram.c:atmel_securam_wait
  - drivers/dma-buf/dma-fence.c:dma_fence_signal_locked
  - drivers/usb/host/ehci-hcd.c:ehci_hrtimer_func
  - drivers/input/evdev.c:evdev_events
  - drivers/input/evdev.c:__evdev_queue_syn_dropped
  - drivers/power/supply/charger-manager.c:try_charger_enable
  - drivers/power/supply/charger-manager.c:try_charger_enable
  - drivers/md/dm-stats.c:dm_stats_account_io
  - drivers/md/dm-stats.c:dm_stats_account_io
  - drivers/md/dm-rq.c:dm_old_request_fn
  - drivers/md/dm-rq.c:dm_start_request
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
  - net/ipv4/tcp_output.c:tcp_transmit_skb
```
**Symbols:**

```
ffffffff8110cad0-ffffffff8110cb68: ktime_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
ktime_t ktime_get();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff811184f0)
Location: kernel/time/timekeeping.c:734
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_get_on_cpu
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_prepare_all
  - arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_get_khz
  - arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_snapshot_khz
  - kernel/async.c:async_synchronize_cookie_domain
  - kernel/async.c:async_synchronize_cookie_domain
  - kernel/async.c:async_run_entry_fn
  - kernel/async.c:async_run_entry_fn
  - kernel/sched/clock.c:sched_clock_tick_stable
  - kernel/sched/clock.c:__sched_clock_work
  - kernel/sched/debug.c:sched_debug_header
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image
  - kernel/power/swap.c:save_image
  - kernel/power/swap.c:save_image
  - kernel/power/wakelock.c:wakelock_lookup_add
  - kernel/power/wakelock.c:__wakelocks_gc
  - kernel/time/timer.c:usleep_range
  - kernel/time/timer_list.c:timer_list_start
  - kernel/time/timer_list.c:sysrq_timer_list_show
  - kernel/time/clockevents.c:clockevents_program_event
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-oneshot.c:tick_resume_oneshot
  - kernel/time/tick-sched.c:tick_setup_sched_timer
  - kernel/time/tick-sched.c:tick_sched_timer
  - kernel/time/tick-sched.c:tick_irq_enter
  - kernel/time/tick-sched.c:tick_nohz_handler
  - kernel/time/tick-sched.c:tick_nohz_idle_exit
  - kernel/time/tick-sched.c:tick_nohz_idle_restart_tick
  - kernel/time/tick-sched.c:tick_nohz_irq_exit
  - kernel/time/tick-sched.c:tick_nohz_idle_enter
  - kernel/time/tick-sched.c:get_cpu_iowait_time_us
  - kernel/time/tick-sched.c:get_cpu_idle_time_us
  - kernel/futex.c:__ia32_sys_futex
  - kernel/futex.c:__x64_sys_futex
  - kernel/futex_compat.c:__x32_compat_sys_futex
  - kernel/futex_compat.c:__ia32_compat_sys_futex
  - kernel/acct.c:do_acct_process
  - kernel/delayacct.c:__delayacct_freepages_start
  - kernel/delayacct.c:__delayacct_blkio_start
  - kernel/delayacct.c:delayacct_end
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/trace/blktrace.c:__blk_add_trace
  - fs/ext4/extents_status.c:__es_shrink
  - fs/ext4/extents_status.c:__es_shrink
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - crypto/jitterentropy-kcapi.c:jent_get_nstime
  - block/blk-core.c:blk_finish_request
  - block/blk-core.c:blk_start_request
  - block/blk-core.c:blk_rq_init
  - block/blk-mq.c:blk_mq_start_request
  - block/blk-mq.c:blk_mq_get_request
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:throtl_tg_is_idle
  - block/cfq-iosched.c:cfq_init_queue
  - block/cfq-iosched.c:cfq_init_queue
  - block/cfq-iosched.c:cfq_idle_slice_timer
  - block/cfq-iosched.c:cfq_completed_request
  - block/cfq-iosched.c:cfq_completed_request
  - block/cfq-iosched.c:cfq_completed_request
  - block/cfq-iosched.c:cfq_completed_request
  - block/cfq-iosched.c:cfq_completed_request
  - block/cfq-iosched.c:cfq_completed_request
  - block/cfq-iosched.c:cfq_completed_request
  - block/cfq-iosched.c:cfq_insert_request
  - block/cfq-iosched.c:cfq_insert_request
  - block/cfq-iosched.c:__cfq_update_io_thinktime
  - block/cfq-iosched.c:cfq_init_icq
  - block/cfq-iosched.c:cfq_dispatch_requests
  - block/cfq-iosched.c:cfq_dispatch_requests
  - block/cfq-iosched.c:cfq_dispatch_requests
  - block/cfq-iosched.c:cfq_dispatch_requests
  - block/cfq-iosched.c:cfq_dispatch_requests
  - block/cfq-iosched.c:cfq_dispatch_requests
  - block/cfq-iosched.c:cfq_dispatch_requests
  - block/cfq-iosched.c:cfq_dispatch_requests
  - block/cfq-iosched.c:__cfq_slice_expired
  - block/cfq-iosched.c:__cfq_slice_expired
  - block/cfq-iosched.c:__cfq_slice_expired
  - block/cfq-iosched.c:__cfq_set_active_queue
  - block/cfq-iosched.c:cfq_service_tree_add
  - block/cfq-iosched.c:cfq_pd_alloc
  - block/cfq-iosched.c:cfq_pd_alloc
  - block/cfq-iosched.c:cfq_pd_alloc
  - block/blk-wbt.c:wb_timer_fn
  - drivers/pci/quirks.c:pci_do_fixups
  - drivers/pci/quirks.c:pci_do_fixups
  - drivers/acpi/osl.c:acpi_os_get_timer
  - drivers/acpi/button.c:acpi_lid_input_open
  - drivers/acpi/button.c:acpi_lid_notify_state
  - drivers/acpi/button.c:acpi_lid_notify_state
  - drivers/acpi/button.c:acpi_lid_notify_state
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
  - drivers/acpi/cppc_acpi.c:check_pcc_chan
  - drivers/acpi/cppc_acpi.c:check_pcc_chan
  - drivers/connector/cn_proc.c:proc_exit_connector
  - drivers/connector/cn_proc.c:proc_coredump_connector
  - drivers/connector/cn_proc.c:proc_comm_connector
  - drivers/connector/cn_proc.c:proc_ptrace_connector
  - drivers/connector/cn_proc.c:proc_sid_connector
  - drivers/connector/cn_proc.c:proc_id_connector
  - drivers/connector/cn_proc.c:proc_exec_connector
  - drivers/connector/cn_proc.c:proc_fork_connector
  - drivers/base/dd.c:deferred_probe_work_func
  - drivers/base/dd.c:deferred_probe_work_func
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_noirq_resume_devices
  - drivers/base/power/main.c:dpm_run_callback
  - drivers/base/power/main.c:dpm_show_time
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show
  - drivers/base/power/domain.c:genpd_total_idle_time_show
  - drivers/base/power/domain.c:genpd_active_time_show
  - drivers/base/power/domain.c:genpd_idle_states_show
  - drivers/base/power/domain.c:pm_genpd_init
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_runtime_suspend
  - drivers/base/power/domain.c:genpd_runtime_suspend
  - drivers/base/power/domain.c:_genpd_power_off
  - drivers/base/power/domain.c:_genpd_power_off
  - drivers/base/power/domain.c:_genpd_power_on
  - drivers/base/power/domain.c:_genpd_power_on
  - drivers/base/power/domain.c:genpd_update_accounting
  - drivers/misc/sram.c:atmel_securam_wait
  - drivers/misc/sram.c:atmel_securam_wait
  - drivers/dma-buf/dma-fence.c:dma_fence_signal_locked
  - drivers/usb/host/ehci-hcd.c:ehci_hrtimer_func
  - drivers/input/evdev.c:evdev_events
  - drivers/input/evdev.c:__evdev_queue_syn_dropped
  - drivers/power/supply/charger-manager.c:try_charger_enable
  - drivers/power/supply/charger-manager.c:try_charger_enable
  - drivers/thermal/thermal_sysfs.c:thermal_cooling_device_setup_sysfs
  - drivers/thermal/thermal_sysfs.c:reset_store
  - drivers/thermal/thermal_sysfs.c:update_time_in_state
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
  - drivers/watchdog/watchdog_dev.c:watchdog_start
  - drivers/watchdog/watchdog_dev.c:watchdog_ping
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/watchdog/watchdog_dev.c:watchdog_next_keepalive
  - drivers/md/dm-stats.c:dm_stats_account_io
  - drivers/md/dm-stats.c:dm_stats_account_io
  - drivers/md/dm-rq.c:dm_old_request_fn
  - drivers/md/dm-rq.c:dm_start_request
  - drivers/md/dm-rq.c:map_request
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
**Symbols:**

```
ffffffff811184f0-ffffffff81118589: ktime_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
ktime_t ktime_get();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81123b10)
Location: kernel/time/timekeeping.c:741
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_get_on_cpu
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_prepare_all
  - arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_get_khz
  - arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_snapshot_khz
  - kernel/async.c:async_synchronize_cookie_domain
  - kernel/async.c:async_synchronize_cookie_domain
  - kernel/async.c:async_run_entry_fn
  - kernel/async.c:async_run_entry_fn
  - kernel/sched/clock.c:__sched_clock_gtod_offset
  - kernel/sched/clock.c:__sched_clock_work
  - kernel/sched/debug.c:sched_debug_header
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image
  - kernel/power/swap.c:save_image
  - kernel/power/swap.c:save_image
  - kernel/power/wakelock.c:wakelock_lookup_add
  - kernel/power/wakelock.c:__wakelocks_gc
  - kernel/time/timer.c:usleep_range
  - kernel/time/timer_list.c:timer_list_start
  - kernel/time/timer_list.c:sysrq_timer_list_show
  - kernel/time/clockevents.c:clockevents_program_event
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-oneshot.c:tick_resume_oneshot
  - kernel/time/tick-sched.c:tick_setup_sched_timer
  - kernel/time/tick-sched.c:tick_sched_timer
  - kernel/time/tick-sched.c:tick_irq_enter
  - kernel/time/tick-sched.c:tick_nohz_handler
  - kernel/time/tick-sched.c:tick_nohz_idle_exit
  - kernel/time/tick-sched.c:tick_nohz_idle_restart_tick
  - kernel/time/tick-sched.c:tick_nohz_irq_exit
  - kernel/time/tick-sched.c:tick_nohz_idle_enter
  - kernel/time/tick-sched.c:get_cpu_iowait_time_us
  - kernel/time/tick-sched.c:get_cpu_idle_time_us
  - kernel/futex.c:__x32_compat_sys_futex
  - kernel/futex.c:__ia32_compat_sys_futex
  - kernel/futex.c:__ia32_sys_futex
  - kernel/futex.c:__x64_sys_futex
  - kernel/acct.c:do_acct_process
  - kernel/delayacct.c:__delayacct_thrashing_start
  - kernel/delayacct.c:__delayacct_freepages_start
  - kernel/delayacct.c:__delayacct_blkio_start
  - kernel/delayacct.c:delayacct_end
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/trace/blktrace.c:__blk_add_trace
  - fs/ext4/extents_status.c:__es_shrink
  - fs/ext4/extents_status.c:__es_shrink
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - crypto/jitterentropy-kcapi.c:jent_get_nstime
  - block/bio.c:__bio_clone_fast
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:blk_rq_init
  - block/blk-mq.c:blk_mq_start_request
  - block/blk-mq.c:blk_mq_get_request
  - block/bounce.c:blk_queue_bounce
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:throtl_tg_is_idle
  - block/blk-wbt.c:wb_timer_fn
  - drivers/pci/quirks.c:pci_do_fixups
  - drivers/pci/quirks.c:pci_do_fixups
  - drivers/acpi/button.c:acpi_lid_input_open
  - drivers/acpi/button.c:acpi_lid_notify_state
  - drivers/acpi/button.c:acpi_lid_notify_state
  - drivers/acpi/button.c:acpi_lid_notify_state
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
  - drivers/acpi/cppc_acpi.c:check_pcc_chan
  - drivers/acpi/cppc_acpi.c:check_pcc_chan
  - drivers/connector/cn_proc.c:proc_exit_connector
  - drivers/connector/cn_proc.c:proc_coredump_connector
  - drivers/connector/cn_proc.c:proc_comm_connector
  - drivers/connector/cn_proc.c:proc_ptrace_connector
  - drivers/connector/cn_proc.c:proc_sid_connector
  - drivers/connector/cn_proc.c:proc_id_connector
  - drivers/connector/cn_proc.c:proc_exec_connector
  - drivers/connector/cn_proc.c:proc_fork_connector
  - drivers/base/dd.c:driver_probe_device
  - drivers/base/dd.c:driver_probe_device
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_noirq_resume_devices
  - drivers/base/power/main.c:dpm_run_callback
  - drivers/base/power/main.c:dpm_show_time
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show
  - drivers/base/power/domain.c:total_idle_time_show
  - drivers/base/power/domain.c:active_time_show
  - drivers/base/power/domain.c:idle_states_show
  - drivers/base/power/domain.c:pm_genpd_init
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_runtime_suspend
  - drivers/base/power/domain.c:genpd_runtime_suspend
  - drivers/base/power/domain.c:_genpd_power_off
  - drivers/base/power/domain.c:_genpd_power_off
  - drivers/base/power/domain.c:_genpd_power_on
  - drivers/base/power/domain.c:_genpd_power_on
  - drivers/base/power/domain.c:genpd_update_accounting
  - drivers/misc/sram.c:atmel_securam_wait
  - drivers/misc/sram.c:atmel_securam_wait
  - drivers/dma-buf/dma-fence.c:dma_fence_signal_locked
  - drivers/usb/host/ehci-hcd.c:ehci_hrtimer_func
  - drivers/input/evdev.c:evdev_events
  - drivers/input/evdev.c:__evdev_queue_syn_dropped
  - drivers/media/cec/cec-adap.c:cec_transmit_msg_fh
  - drivers/media/cec/cec-adap.c:cec_wait_timeout
  - drivers/media/cec/cec-adap.c:cec_data_cancel
  - drivers/media/cec/cec-adap.c:cec_data_cancel
  - drivers/media/cec/cec-adap.c:cec_post_state_event
  - drivers/media/cec/cec-adap.c:cec_queue_msg_fh
  - drivers/media/cec/cec-adap.c:cec_queue_event_fh
  - drivers/power/supply/charger-manager.c:try_charger_enable
  - drivers/power/supply/charger-manager.c:try_charger_enable
  - drivers/thermal/thermal_sysfs.c:thermal_cooling_device_setup_sysfs
  - drivers/thermal/thermal_sysfs.c:reset_store
  - drivers/thermal/thermal_sysfs.c:update_time_in_state
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
  - drivers/watchdog/watchdog_dev.c:watchdog_start
  - drivers/watchdog/watchdog_dev.c:watchdog_ping
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/watchdog/watchdog_dev.c:watchdog_next_keepalive
  - drivers/md/dm-stats.c:dm_stats_account_io
  - drivers/md/dm-stats.c:dm_stats_account_io
  - drivers/md/dm-rq.c:dm_mq_queue_rq
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_synack_rtt_meas
  - net/ipv4/tcp_output.c:tcp_send_window_probe
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
  - net/ipv4/syncookies.c:cookie_init_timestamp
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
```
**Symbols:**

```
ffffffff81123b10-ffffffff81123ba9: ktime_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
ktime_t ktime_get();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/timekeeping.c (0)
Location: kernel/time/timekeeping.c:747
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_get_on_cpu
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_prepare_all
  - arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_get_khz
  - arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_snapshot_khz
  - kernel/fork.c:copy_process
  - kernel/async.c:async_synchronize_cookie_domain
  - kernel/async.c:async_synchronize_cookie_domain
  - kernel/async.c:async_run_entry_fn
  - kernel/async.c:async_run_entry_fn
  - kernel/sched/clock.c:__sched_clock_gtod_offset
  - kernel/sched/clock.c:__sched_clock_work
  - kernel/sched/debug.c:sched_debug_header
  - kernel/power/main.c:ksys_sync_helper
  - kernel/power/main.c:ksys_sync_helper
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image
  - kernel/power/swap.c:save_image
  - kernel/power/swap.c:save_image
  - kernel/power/wakelock.c:wakelock_lookup_add
  - kernel/power/wakelock.c:__wakelocks_gc
  - kernel/time/timer.c:usleep_range
  - kernel/time/timer_list.c:timer_list_start
  - kernel/time/timer_list.c:sysrq_timer_list_show
  - kernel/time/clockevents.c:clockevents_program_event
  - kernel/time/clockevents.c:clockevents_program_min_delta
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-oneshot.c:tick_resume_oneshot
  - kernel/time/tick-sched.c:tick_setup_sched_timer
  - kernel/time/tick-sched.c:tick_sched_timer
  - kernel/time/tick-sched.c:tick_irq_enter
  - kernel/time/tick-sched.c:tick_nohz_handler
  - kernel/time/tick-sched.c:tick_nohz_idle_exit
  - kernel/time/tick-sched.c:tick_nohz_idle_restart_tick
  - kernel/time/tick-sched.c:tick_nohz_irq_exit
  - kernel/time/tick-sched.c:tick_nohz_idle_enter
  - kernel/time/tick-sched.c:get_cpu_iowait_time_us
  - kernel/time/tick-sched.c:get_cpu_idle_time_us
  - kernel/futex.c:__ia32_sys_futex_time32
  - kernel/futex.c:__x64_sys_futex_time32
  - kernel/futex.c:__ia32_sys_futex
  - kernel/futex.c:__x64_sys_futex
  - kernel/acct.c:do_acct_process
  - kernel/delayacct.c:__delayacct_thrashing_start
  - kernel/delayacct.c:__delayacct_freepages_start
  - kernel/delayacct.c:__delayacct_blkio_start
  - kernel/delayacct.c:delayacct_end
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/trace/blktrace.c:__blk_add_trace
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - fs/ext4/extents_status.c:__es_shrink
  - fs/ext4/extents_status.c:__es_shrink
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - crypto/jitterentropy-kcapi.c:jent_get_nstime
  - block/bio.c:__bio_clone_fast
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:blk_rq_init
  - block/blk-mq.c:blk_mq_start_request
  - block/blk-mq.c:blk_mq_get_request
  - block/bounce.c:__blk_queue_bounce
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:throtl_tg_is_idle
  - block/blk-wbt.c:wb_timer_fn
  - lib/dim/rdma_dim.c:rdma_dim
  - lib/dim/rdma_dim.c:rdma_dim
  - drivers/pci/quirks.c:pci_do_fixups
  - drivers/pci/quirks.c:pci_do_fixups
  - drivers/acpi/button.c:acpi_lid_input_open
  - drivers/acpi/button.c:acpi_button_resume
  - drivers/acpi/button.c:acpi_lid_notify_state
  - drivers/acpi/button.c:acpi_lid_notify_state
  - drivers/acpi/button.c:acpi_lid_notify_state
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
  - drivers/acpi/cppc_acpi.c:check_pcc_chan
  - drivers/acpi/cppc_acpi.c:check_pcc_chan
  - drivers/connector/cn_proc.c:proc_exit_connector
  - drivers/connector/cn_proc.c:proc_coredump_connector
  - drivers/connector/cn_proc.c:proc_comm_connector
  - drivers/connector/cn_proc.c:proc_ptrace_connector
  - drivers/connector/cn_proc.c:proc_sid_connector
  - drivers/connector/cn_proc.c:proc_id_connector
  - drivers/connector/cn_proc.c:proc_exec_connector
  - drivers/connector/cn_proc.c:proc_fork_connector
  - drivers/base/dd.c:driver_probe_device
  - drivers/base/dd.c:driver_probe_device
  - drivers/base/power/main.c:dpm_suspend_start
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:dpm_suspend_end
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_noirq_resume_devices
  - drivers/base/power/main.c:dpm_run_callback
  - drivers/base/power/main.c:dpm_show_time
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show
  - drivers/base/power/domain.c:total_idle_time_show
  - drivers/base/power/domain.c:active_time_show
  - drivers/base/power/domain.c:idle_states_show
  - drivers/base/power/domain.c:pm_genpd_init
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_runtime_suspend
  - drivers/base/power/domain.c:genpd_runtime_suspend
  - drivers/base/power/domain.c:_genpd_power_off
  - drivers/base/power/domain.c:_genpd_power_off
  - drivers/base/power/domain.c:_genpd_power_on
  - drivers/base/power/domain.c:_genpd_power_on
  - drivers/base/power/domain.c:genpd_update_accounting
  - drivers/misc/sram.c:atmel_securam_wait
  - drivers/misc/sram.c:atmel_securam_wait
  - drivers/dma-buf/dma-fence.c:dma_fence_signal_locked
  - drivers/usb/dwc2/core.c:dwc2_wait_for_mode
  - drivers/usb/host/ehci-hcd.c:ehci_hrtimer_func
  - drivers/usb/host/xhci.c:xhci_handshake
  - drivers/usb/host/xhci.c:xhci_handshake
  - drivers/input/evdev.c:evdev_events
  - drivers/input/evdev.c:__evdev_queue_syn_dropped
  - drivers/media/cec/cec-adap.c:cec_transmit_msg_fh
  - drivers/media/cec/cec-adap.c:cec_wait_timeout
  - drivers/media/cec/cec-adap.c:cec_data_cancel
  - drivers/media/cec/cec-adap.c:cec_data_cancel
  - drivers/media/cec/cec-adap.c:cec_post_state_event
  - drivers/media/cec/cec-adap.c:cec_queue_msg_fh
  - drivers/media/cec/cec-adap.c:cec_queue_event_fh
  - drivers/power/supply/charger-manager.c:try_charger_enable
  - drivers/power/supply/charger-manager.c:try_charger_enable
  - drivers/thermal/thermal_sysfs.c:thermal_cooling_device_setup_sysfs
  - drivers/thermal/thermal_sysfs.c:reset_store
  - drivers/thermal/thermal_sysfs.c:update_time_in_state
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
  - drivers/watchdog/watchdog_dev.c:watchdog_start
  - drivers/watchdog/watchdog_dev.c:watchdog_ping_work
  - drivers/watchdog/watchdog_dev.c:watchdog_ping
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/watchdog/watchdog_dev.c:watchdog_next_keepalive
  - drivers/md/dm-stats.c:dm_stats_account_io
  - drivers/md/dm-stats.c:dm_stats_account_io
  - drivers/md/dm-rq.c:dm_mq_queue_rq
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
  - net/ipv4/tcp_input.c:tcp_synack_rtt_meas
  - net/ipv4/tcp_output.c:tcp_send_window_probe
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/syncookies.c:cookie_init_timestamp
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
**Symbols:**

```
ffffffff8112f7b1-ffffffff8112f7c4: ktime_get.cold (STB_LOCAL)
ffffffff8112ea10-ffffffff8112eaa5: ktime_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
ktime_t ktime_get();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff8113a860)
Location: kernel/time/timekeeping.c:747
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_get_on_cpu
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_prepare_all
  - arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_get_khz
  - arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_snapshot_khz
  - kernel/fork.c:copy_process
  - kernel/async.c:async_synchronize_cookie_domain
  - kernel/async.c:async_synchronize_cookie_domain
  - kernel/async.c:async_run_entry_fn
  - kernel/async.c:async_run_entry_fn
  - kernel/sched/clock.c:__sched_clock_gtod_offset
  - kernel/sched/clock.c:__sched_clock_work
  - kernel/sched/debug.c:sched_debug_header
  - kernel/power/main.c:ksys_sync_helper
  - kernel/power/main.c:ksys_sync_helper
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image
  - kernel/power/swap.c:save_image
  - kernel/power/swap.c:save_image
  - kernel/power/wakelock.c:wakelock_lookup_add
  - kernel/power/wakelock.c:__wakelocks_gc
  - kernel/time/timer.c:usleep_range
  - kernel/time/timer_list.c:timer_list_start
  - kernel/time/timer_list.c:sysrq_timer_list_show
  - kernel/time/clockevents.c:clockevents_program_event
  - kernel/time/clockevents.c:clockevents_program_min_delta
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-oneshot.c:tick_resume_oneshot
  - kernel/time/tick-sched.c:tick_setup_sched_timer
  - kernel/time/tick-sched.c:tick_sched_timer
  - kernel/time/tick-sched.c:tick_irq_enter
  - kernel/time/tick-sched.c:tick_nohz_handler
  - kernel/time/tick-sched.c:tick_nohz_idle_exit
  - kernel/time/tick-sched.c:tick_nohz_idle_restart_tick
  - kernel/time/tick-sched.c:tick_nohz_irq_exit
  - kernel/time/tick-sched.c:tick_nohz_idle_enter
  - kernel/time/tick-sched.c:get_cpu_iowait_time_us
  - kernel/time/tick-sched.c:get_cpu_idle_time_us
  - kernel/futex.c:__ia32_sys_futex_time32
  - kernel/futex.c:__x64_sys_futex_time32
  - kernel/futex.c:__ia32_sys_futex
  - kernel/futex.c:__x64_sys_futex
  - kernel/acct.c:do_acct_process
  - kernel/delayacct.c:__delayacct_thrashing_start
  - kernel/delayacct.c:__delayacct_freepages_start
  - kernel/delayacct.c:__delayacct_blkio_start
  - kernel/delayacct.c:delayacct_end
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/trace/blktrace.c:__blk_add_trace
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - fs/ext4/extents_status.c:__es_shrink
  - fs/ext4/extents_status.c:__es_shrink
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - crypto/jitterentropy-kcapi.c:jent_get_nstime
  - block/bio.c:__bio_clone_fast
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:blk_rq_init
  - block/blk-mq.c:blk_mq_start_request
  - block/blk-mq.c:blk_mq_get_request
  - block/blk-mq.c:blk_mq_get_request
  - block/bounce.c:__blk_queue_bounce
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:throtl_tg_is_idle
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-iocost.c:ioc_now
  - block/blk-iocost.c:ioc_refresh_params
  - block/blk-wbt.c:wb_timer_fn
  - lib/dim/rdma_dim.c:rdma_dim
  - lib/dim/rdma_dim.c:rdma_dim
  - drivers/pci/quirks.c:pci_do_fixups
  - drivers/pci/quirks.c:pci_do_fixups
  - drivers/acpi/button.c:acpi_lid_input_open
  - drivers/acpi/button.c:acpi_button_resume
  - drivers/acpi/button.c:acpi_lid_notify_state
  - drivers/acpi/button.c:acpi_lid_notify_state
  - drivers/acpi/button.c:acpi_lid_notify_state
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
  - drivers/acpi/cppc_acpi.c:check_pcc_chan
  - drivers/acpi/cppc_acpi.c:check_pcc_chan
  - drivers/connector/cn_proc.c:proc_exit_connector
  - drivers/connector/cn_proc.c:proc_coredump_connector
  - drivers/connector/cn_proc.c:proc_comm_connector
  - drivers/connector/cn_proc.c:proc_ptrace_connector
  - drivers/connector/cn_proc.c:proc_sid_connector
  - drivers/connector/cn_proc.c:proc_id_connector
  - drivers/connector/cn_proc.c:proc_exec_connector
  - drivers/connector/cn_proc.c:proc_fork_connector
  - drivers/base/dd.c:driver_probe_device
  - drivers/base/dd.c:driver_probe_device
  - drivers/base/power/main.c:dpm_suspend_start
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:dpm_suspend_end
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_noirq
  - drivers/base/power/main.c:dpm_run_callback
  - drivers/base/power/main.c:dpm_show_time
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show
  - drivers/base/power/wakeup_stats.c:prevent_suspend_time_ms_show
  - drivers/base/power/wakeup_stats.c:max_time_ms_show
  - drivers/base/power/wakeup_stats.c:total_time_ms_show
  - drivers/base/power/wakeup_stats.c:active_time_ms_show
  - drivers/base/power/domain.c:total_idle_time_show
  - drivers/base/power/domain.c:active_time_show
  - drivers/base/power/domain.c:idle_states_show
  - drivers/base/power/domain.c:pm_genpd_init
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_runtime_suspend
  - drivers/base/power/domain.c:genpd_runtime_suspend
  - drivers/base/power/domain.c:_genpd_power_off
  - drivers/base/power/domain.c:_genpd_power_off
  - drivers/base/power/domain.c:_genpd_power_on
  - drivers/base/power/domain.c:_genpd_power_on
  - drivers/base/power/domain.c:genpd_update_accounting
  - drivers/misc/sram.c:atmel_securam_wait
  - drivers/misc/sram.c:atmel_securam_wait
  - drivers/dma-buf/dma-fence.c:dma_fence_signal_locked
  - drivers/usb/dwc2/core.c:dwc2_wait_for_mode
  - drivers/usb/host/ehci-hcd.c:ehci_hrtimer_func
  - drivers/usb/host/xhci.c:xhci_handshake
  - drivers/usb/host/xhci.c:xhci_handshake
  - drivers/input/input.c:input_get_timestamp
  - drivers/input/input.c:input_repeat_key
  - drivers/media/cec/cec-adap.c:cec_transmit_msg_fh
  - drivers/media/cec/cec-adap.c:cec_wait_timeout
  - drivers/media/cec/cec-adap.c:cec_data_cancel
  - drivers/media/cec/cec-adap.c:cec_data_cancel
  - drivers/media/cec/cec-adap.c:cec_post_state_event
  - drivers/media/cec/cec-adap.c:cec_queue_msg_fh
  - drivers/media/cec/cec-adap.c:cec_queue_event_fh
  - drivers/power/supply/charger-manager.c:try_charger_enable
  - drivers/power/supply/charger-manager.c:try_charger_enable
  - drivers/thermal/thermal_sysfs.c:thermal_cooling_device_setup_sysfs
  - drivers/thermal/thermal_sysfs.c:reset_store
  - drivers/thermal/thermal_sysfs.c:update_time_in_state
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
  - drivers/watchdog/watchdog_dev.c:watchdog_start
  - drivers/watchdog/watchdog_dev.c:watchdog_ping_work
  - drivers/watchdog/watchdog_dev.c:watchdog_ping
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/watchdog/watchdog_dev.c:watchdog_next_keepalive
  - drivers/md/dm-stats.c:dm_stats_account_io
  - drivers/md/dm-stats.c:dm_stats_account_io
  - drivers/md/dm-rq.c:map_request
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
  - net/ipv4/tcp_input.c:tcp_synack_rtt_meas
  - net/ipv4/tcp_output.c:tcp_send_window_probe
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/syncookies.c:cookie_init_timestamp
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
**Symbols:**

```
ffffffff8113a860-ffffffff8113a8f5: ktime_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
ktime_t ktime_get();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff811495f0)
Location: kernel/time/timekeeping.c:747
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_get_on_cpu
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_prepare_all
  - arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_get_khz
  - arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_snapshot_khz
  - kernel/fork.c:copy_process
  - kernel/async.c:async_synchronize_cookie_domain
  - kernel/async.c:async_synchronize_cookie_domain
  - kernel/async.c:async_run_entry_fn
  - kernel/async.c:async_run_entry_fn
  - kernel/sched/clock.c:sched_clock_tick_stable
  - kernel/sched/clock.c:__sched_clock_work
  - kernel/sched/debug.c:sched_debug_header
  - kernel/power/main.c:ksys_sync_helper
  - kernel/power/main.c:ksys_sync_helper
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image
  - kernel/power/swap.c:save_image
  - kernel/power/swap.c:save_image
  - kernel/power/wakelock.c:wakelock_lookup_add
  - kernel/power/wakelock.c:__wakelocks_gc
  - kernel/time/timer.c:usleep_range
  - kernel/time/timer_list.c:timer_list_start
  - kernel/time/timer_list.c:sysrq_timer_list_show
  - kernel/time/posix-timers.c:posix_get_monotonic_ktime
  - kernel/time/clockevents.c:clockevents_program_event
  - kernel/time/clockevents.c:clockevents_program_min_delta
  - kernel/time/tick-common.c:tick_setup_device
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-oneshot.c:tick_resume_oneshot
  - kernel/time/tick-sched.c:tick_setup_sched_timer
  - kernel/time/tick-sched.c:tick_sched_timer
  - kernel/time/tick-sched.c:tick_irq_enter
  - kernel/time/tick-sched.c:tick_nohz_handler
  - kernel/time/tick-sched.c:tick_nohz_idle_exit
  - kernel/time/tick-sched.c:tick_nohz_idle_restart_tick
  - kernel/time/tick-sched.c:tick_nohz_irq_exit
  - kernel/time/tick-sched.c:tick_nohz_idle_enter
  - kernel/time/tick-sched.c:get_cpu_iowait_time_us
  - kernel/time/tick-sched.c:get_cpu_idle_time_us
  - kernel/futex.c:__ia32_sys_futex_time32
  - kernel/futex.c:__x64_sys_futex_time32
  - kernel/futex.c:__ia32_sys_futex
  - kernel/futex.c:__x64_sys_futex
  - kernel/acct.c:fill_ac
  - kernel/delayacct.c:__delayacct_thrashing_end
  - kernel/delayacct.c:__delayacct_thrashing_start
  - kernel/delayacct.c:__delayacct_freepages_end
  - kernel/delayacct.c:__delayacct_freepages_start
  - kernel/delayacct.c:__delayacct_blkio_end
  - kernel/delayacct.c:__delayacct_blkio_start
  - kernel/taskstats.c:fill_stats_for_tgid
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/trace/blktrace.c:__blk_add_trace
  - kernel/trace/blktrace.c:trace_note
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - fs/ext4/extents_status.c:__es_shrink
  - fs/ext4/extents_status.c:__es_shrink
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2_get_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - crypto/jitterentropy-kcapi.c:jent_get_nstime
  - block/bio.c:__bio_clone_fast
  - block/blk-core.c:blk_rq_init
  - block/blk-core.c:blkcg_bio_issue_check
  - block/blk-flush.c:flush_end_io
  - block/blk-flush.c:flush_end_io
  - block/blk-mq.c:blk_mq_try_issue_list_directly
  - block/blk-mq.c:blk_mq_start_request
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - block/blk-mq.c:__blk_mq_alloc_request
  - block/blk-mq.c:blk_mq_rq_ctx_init
  - block/blk-cgroup.c:blkcg_maybe_throttle_blkg
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:throtl_tg_is_idle
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-iocost.c:ioc_now
  - block/blk-wbt.c:latency_exceeded
  - block/blk-crypto-fallback.c:blk_crypto_clone_bio
  - lib/dim/net_dim.c:net_dim
  - lib/dim/rdma_dim.c:rdma_dim
  - lib/dim/rdma_dim.c:rdma_dim
  - drivers/gpio/gpiolib.c:lineevent_irq_handler
  - drivers/gpio/gpiolib.c:lineevent_irq_thread
  - drivers/pwm/pwm-lpss.c:pwm_lpss_wait_for_update
  - drivers/pwm/pwm-lpss.c:pwm_lpss_wait_for_update
  - drivers/pci/quirks.c:pci_do_fixups
  - drivers/pci/quirks.c:pci_do_fixups
  - drivers/acpi/button.c:acpi_lid_input_open
  - drivers/acpi/button.c:acpi_button_resume
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
  - drivers/acpi/cppc_acpi.c:check_pcc_chan
  - drivers/acpi/cppc_acpi.c:check_pcc_chan
  - drivers/reset/reset-brcmstb-rescal.c:brcm_rescal_reset_set
  - drivers/reset/reset-brcmstb-rescal.c:brcm_rescal_reset_set
  - drivers/connector/cn_proc.c:proc_exit_connector
  - drivers/connector/cn_proc.c:proc_coredump_connector
  - drivers/connector/cn_proc.c:proc_comm_connector
  - drivers/connector/cn_proc.c:proc_ptrace_connector
  - drivers/connector/cn_proc.c:proc_sid_connector
  - drivers/connector/cn_proc.c:proc_id_connector
  - drivers/connector/cn_proc.c:proc_exec_connector
  - drivers/connector/cn_proc.c:proc_fork_connector
  - drivers/base/dd.c:driver_probe_device
  - drivers/base/dd.c:driver_probe_device
  - drivers/base/power/main.c:dpm_suspend_start
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_end
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_noirq_resume_devices
  - drivers/base/power/main.c:dpm_show_time
  - drivers/base/power/wakeup.c:wakeup_source_activate
  - drivers/base/power/wakeup_stats.c:prevent_suspend_time_ms_show
  - drivers/base/power/wakeup_stats.c:max_time_ms_show
  - drivers/base/power/wakeup_stats.c:total_time_ms_show
  - drivers/base/power/wakeup_stats.c:active_time_ms_show
  - drivers/base/power/domain.c:total_idle_time_show
  - drivers/base/power/domain.c:active_time_show
  - drivers/base/power/domain.c:idle_states_show
  - drivers/base/power/domain.c:pm_genpd_init
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_runtime_suspend
  - drivers/base/power/domain.c:genpd_runtime_suspend
  - drivers/base/power/domain.c:genpd_power_on
  - drivers/base/power/domain.c:_genpd_power_off
  - drivers/base/power/domain.c:_genpd_power_off
  - drivers/base/power/domain.c:_genpd_power_on
  - drivers/base/power/domain.c:_genpd_power_on
  - drivers/misc/sram.c:atmel_securam_wait
  - drivers/misc/sram.c:atmel_securam_wait
  - drivers/mfd/arizona-core.c:arizona_poll_reg
  - drivers/mfd/arizona-core.c:arizona_poll_reg
  - drivers/dma-buf/dma-fence.c:dma_fence_signal_locked
  - drivers/net/phy/phy_device.c:phy_poll_reset
  - drivers/net/phy/phy_device.c:phy_poll_reset
  - drivers/net/phy/bcm84881.c:bcm84881_wait_init
  - drivers/net/phy/bcm84881.c:bcm84881_wait_init
  - drivers/usb/dwc2/core.c:dwc2_wait_for_mode
  - drivers/usb/dwc2/core.c:dwc2_wait_for_mode
  - drivers/usb/host/ehci-hcd.c:sitd_complete
  - drivers/usb/host/ehci-hcd.c:itd_complete
  - drivers/usb/host/ehci-hcd.c:scan_async
  - drivers/usb/host/ehci-hcd.c:unlink_empty_async
  - drivers/usb/host/ehci-hcd.c:end_unlink_async
  - drivers/usb/host/ehci-hcd.c:ehci_hrtimer_func
  - drivers/usb/host/ehci-hcd.c:end_free_itds
  - drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks
  - drivers/usb/host/ehci-hcd.c:ehci_handle_start_intr_unlinks
  - drivers/usb/host/xhci.c:xhci_set_usb2_hardware_lpm
  - drivers/usb/host/xhci.c:xhci_set_usb2_hardware_lpm
  - drivers/usb/host/xhci.c:xhci_handshake
  - drivers/usb/host/xhci.c:xhci_handshake
  - drivers/input/input.c:input_get_timestamp
  - drivers/input/input.c:input_repeat_key
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy
  - drivers/power/reset/mt6323-poweroff.c:mt6323_do_pwroff
  - drivers/power/reset/mt6323-poweroff.c:mt6323_do_pwroff
  - drivers/power/supply/charger-manager.c:check_charging_duration
  - drivers/power/supply/charger-manager.c:try_charger_enable
  - drivers/power/supply/charger-manager.c:try_charger_enable
  - drivers/thermal/thermal_sysfs.c:cooling_device_stats_setup
  - drivers/thermal/thermal_sysfs.c:reset_store
  - drivers/thermal/thermal_sysfs.c:time_in_state_ms_show
  - drivers/thermal/thermal_sysfs.c:thermal_cooling_device_stats_update
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
  - drivers/watchdog/watchdog_dev.c:watchdog_start
  - drivers/watchdog/watchdog_dev.c:watchdog_ping_work
  - drivers/watchdog/watchdog_dev.c:watchdog_ping
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/watchdog/watchdog_dev.c:watchdog_next_keepalive
  - drivers/md/dm-stats.c:dm_stats_account_io
  - drivers/md/dm-stats.c:dm_stats_account_io
  - drivers/md/dm-stats.c:dm_stat_round
  - drivers/md/dm-rq.c:map_request
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
  - net/ipv4/tcp_input.c:tcp_synack_rtt_meas
  - net/ipv4/tcp_output.c:tcp_send_window_probe
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
**Symbols:**

```
ffffffff811495f0-ffffffff8114968c: ktime_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ktime_t ktime_get();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81145ec0)
Location: kernel/time/timekeeping.c:817
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_get_on_cpu
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_prepare_all
  - arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_get_khz
  - arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_snapshot_khz
  - kernel/fork.c:copy_process
  - kernel/async.c:async_synchronize_cookie_domain
  - kernel/async.c:async_synchronize_cookie_domain
  - kernel/async.c:async_run_entry_fn
  - kernel/async.c:async_run_entry_fn
  - kernel/sched/clock.c:sched_clock_tick_stable
  - kernel/sched/clock.c:__sched_clock_work
  - kernel/sched/debug.c:sched_debug_header
  - kernel/power/main.c:ksys_sync_helper
  - kernel/power/main.c:ksys_sync_helper
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image
  - kernel/power/swap.c:save_image
  - kernel/power/swap.c:save_image
  - kernel/power/wakelock.c:wakelock_lookup_add
  - kernel/power/wakelock.c:__wakelocks_gc
  - kernel/time/timer.c:usleep_range
  - kernel/time/timer_list.c:timer_list_start
  - kernel/time/timer_list.c:sysrq_timer_list_show
  - kernel/time/posix-timers.c:posix_get_monotonic_ktime
  - kernel/time/clockevents.c:clockevents_program_event
  - kernel/time/clockevents.c:clockevents_program_min_delta
  - kernel/time/tick-common.c:tick_setup_device
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-oneshot.c:tick_resume_oneshot
  - kernel/time/tick-sched.c:tick_setup_sched_timer
  - kernel/time/tick-sched.c:tick_sched_timer
  - kernel/time/tick-sched.c:tick_irq_enter
  - kernel/time/tick-sched.c:tick_nohz_handler
  - kernel/time/tick-sched.c:tick_nohz_idle_exit
  - kernel/time/tick-sched.c:tick_nohz_idle_restart_tick
  - kernel/time/tick-sched.c:tick_nohz_irq_exit
  - kernel/time/tick-sched.c:tick_nohz_idle_enter
  - kernel/time/tick-sched.c:get_cpu_iowait_time_us
  - kernel/time/tick-sched.c:get_cpu_idle_time_us
  - kernel/futex.c:__ia32_sys_futex_time32
  - kernel/futex.c:__x64_sys_futex_time32
  - kernel/futex.c:__ia32_sys_futex
  - kernel/futex.c:__x64_sys_futex
  - kernel/acct.c:fill_ac
  - kernel/delayacct.c:__delayacct_thrashing_end
  - kernel/delayacct.c:__delayacct_thrashing_start
  - kernel/delayacct.c:__delayacct_freepages_end
  - kernel/delayacct.c:__delayacct_freepages_start
  - kernel/delayacct.c:__delayacct_blkio_end
  - kernel/delayacct.c:__delayacct_blkio_start
  - kernel/taskstats.c:fill_stats_for_tgid
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/trace/blktrace.c:__blk_add_trace
  - kernel/trace/blktrace.c:trace_note
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - fs/ext4/extents_status.c:__es_shrink
  - fs/ext4/extents_status.c:__es_shrink
  - fs/ext4/fast_commit.c:ext4_fc_commit
  - fs/ext4/fast_commit.c:ext4_fc_commit
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2_get_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - crypto/jitterentropy-kcapi.c:jent_get_nstime
  - block/bio.c:__bio_clone_fast
  - block/blk-core.c:submit_bio_checks
  - block/blk-core.c:submit_bio_checks
  - block/blk-core.c:blk_rq_init
  - block/blk-flush.c:flush_end_io
  - block/blk-flush.c:flush_end_io
  - block/blk-mq.c:blk_mq_try_issue_list_directly
  - block/blk-mq.c:blk_mq_start_request
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - block/blk-mq.c:__blk_mq_alloc_request
  - block/blk-mq.c:blk_mq_rq_ctx_init
  - block/blk-cgroup.c:blkcg_maybe_throttle_blkg
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:throtl_tg_is_idle
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-iocost.c:ioc_now
  - block/blk-wbt.c:latency_exceeded
  - block/blk-crypto-fallback.c:blk_crypto_clone_bio
  - lib/dim/net_dim.c:net_dim
  - lib/dim/rdma_dim.c:rdma_dim
  - lib/dim/rdma_dim.c:rdma_dim
  - drivers/gpio/gpiolib-cdev.c:debounce_work_func
  - drivers/gpio/gpiolib-cdev.c:edge_irq_handler
  - drivers/gpio/gpiolib-cdev.c:edge_irq_thread
  - drivers/pci/quirks.c:pci_do_fixups
  - drivers/pci/quirks.c:pci_do_fixups
  - drivers/acpi/button.c:acpi_lid_input_open
  - drivers/acpi/button.c:acpi_button_resume
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
  - drivers/acpi/cppc_acpi.c:check_pcc_chan
  - drivers/acpi/cppc_acpi.c:check_pcc_chan
  - drivers/xen/events/events_base.c:handle_irq_for_port
  - drivers/reset/reset-brcmstb-rescal.c:brcm_rescal_reset_set
  - drivers/reset/reset-brcmstb-rescal.c:brcm_rescal_reset_set
  - drivers/connector/cn_proc.c:proc_exit_connector
  - drivers/connector/cn_proc.c:proc_coredump_connector
  - drivers/connector/cn_proc.c:proc_comm_connector
  - drivers/connector/cn_proc.c:proc_ptrace_connector
  - drivers/connector/cn_proc.c:proc_sid_connector
  - drivers/connector/cn_proc.c:proc_id_connector
  - drivers/connector/cn_proc.c:proc_exec_connector
  - drivers/connector/cn_proc.c:proc_fork_connector
  - drivers/base/dd.c:driver_probe_device
  - drivers/base/dd.c:driver_probe_device
  - drivers/base/power/main.c:dpm_suspend_start
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_end
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_noirq_resume_devices
  - drivers/base/power/main.c:dpm_show_time
  - drivers/base/power/wakeup.c:wakeup_source_activate
  - drivers/base/power/wakeup_stats.c:prevent_suspend_time_ms_show
  - drivers/base/power/wakeup_stats.c:max_time_ms_show
  - drivers/base/power/wakeup_stats.c:total_time_ms_show
  - drivers/base/power/wakeup_stats.c:active_time_ms_show
  - drivers/base/power/domain.c:total_idle_time_show
  - drivers/base/power/domain.c:active_time_show
  - drivers/base/power/domain.c:idle_states_show
  - drivers/base/power/domain.c:pm_genpd_init
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_runtime_suspend
  - drivers/base/power/domain.c:genpd_runtime_suspend
  - drivers/base/power/domain.c:genpd_power_on
  - drivers/base/power/domain.c:_genpd_power_off
  - drivers/base/power/domain.c:_genpd_power_off
  - drivers/base/power/domain.c:_genpd_power_on
  - drivers/base/power/domain.c:_genpd_power_on
  - drivers/misc/sram.c:atmel_securam_wait
  - drivers/misc/sram.c:atmel_securam_wait
  - drivers/mfd/arizona-core.c:arizona_poll_reg
  - drivers/mfd/arizona-core.c:arizona_poll_reg
  - drivers/dma-buf/dma-fence.c:dma_fence_signal_locked
  - drivers/net/phy/phy_device.c:phy_poll_reset
  - drivers/net/phy/phy_device.c:phy_poll_reset
  - drivers/net/phy/bcm84881.c:bcm84881_wait_init
  - drivers/net/phy/bcm84881.c:bcm84881_wait_init
  - drivers/usb/dwc2/core.c:dwc2_wait_for_mode
  - drivers/usb/dwc2/core.c:dwc2_wait_for_mode
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
  - drivers/usb/host/ehci-hcd.c:sitd_complete
  - drivers/usb/host/ehci-hcd.c:itd_complete
  - drivers/usb/host/ehci-hcd.c:scan_async
  - drivers/usb/host/ehci-hcd.c:unlink_empty_async
  - drivers/usb/host/ehci-hcd.c:end_unlink_async
  - drivers/usb/host/ehci-hcd.c:ehci_hrtimer_func
  - drivers/usb/host/ehci-hcd.c:end_free_itds
  - drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks
  - drivers/usb/host/ehci-hcd.c:ehci_handle_start_intr_unlinks
  - drivers/usb/host/xhci.c:xhci_set_usb2_hardware_lpm
  - drivers/usb/host/xhci.c:xhci_set_usb2_hardware_lpm
  - drivers/usb/host/xhci.c:xhci_handshake
  - drivers/usb/host/xhci.c:xhci_handshake
  - drivers/usb/early/ehci-dbgp.c:dbgp_wait_until_done
  - drivers/usb/early/ehci-dbgp.c:dbgp_wait_until_done
  - drivers/usb/early/xhci-dbc.c:xdbc_handle_events
  - drivers/usb/early/xhci-dbc.c:xdbc_handle_events
  - drivers/usb/early/xhci-dbc.c:handshake
  - drivers/usb/early/xhci-dbc.c:handshake
  - drivers/input/input.c:input_get_timestamp
  - drivers/input/input.c:input_repeat_key
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy
  - drivers/power/reset/mt6323-poweroff.c:mt6323_do_pwroff
  - drivers/power/reset/mt6323-poweroff.c:mt6323_do_pwroff
  - drivers/power/supply/charger-manager.c:check_charging_duration
  - drivers/thermal/thermal_sysfs.c:cooling_device_stats_setup
  - drivers/thermal/thermal_sysfs.c:reset_store
  - drivers/thermal/thermal_sysfs.c:time_in_state_ms_show
  - drivers/thermal/thermal_sysfs.c:thermal_cooling_device_stats_update
  - drivers/watchdog/watchdog_dev.c:watchdog_set_last_hw_keepalive
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
  - drivers/watchdog/watchdog_dev.c:watchdog_start
  - drivers/watchdog/watchdog_dev.c:watchdog_ping_work
  - drivers/watchdog/watchdog_dev.c:watchdog_ping
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/watchdog/watchdog_dev.c:watchdog_next_keepalive
  - drivers/md/dm-stats.c:dm_stats_account_io
  - drivers/md/dm-stats.c:dm_stats_account_io
  - drivers/md/dm-stats.c:dm_stat_round
  - drivers/md/dm-rq.c:map_request
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
  - net/ipv4/tcp_input.c:tcp_synack_rtt_meas
  - net/ipv4/tcp_output.c:tcp_send_window_probe
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/mptcp/protocol.c:mptcp_rcv_space_adjust
```
**Symbols:**

```
ffffffff81145ec0-ffffffff81145f5c: ktime_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ktime_t ktime_get();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff811469a0)
Location: kernel/time/timekeeping.c:817
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_get_on_cpu
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_prepare_all
  - arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_get_khz
  - arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_snapshot_khz
  - kernel/fork.c:copy_process
  - kernel/async.c:async_synchronize_cookie_domain
  - kernel/async.c:async_synchronize_cookie_domain
  - kernel/async.c:async_run_entry_fn
  - kernel/async.c:async_run_entry_fn
  - kernel/sched/clock.c:sched_clock_tick_stable
  - kernel/sched/clock.c:__sched_clock_work
  - kernel/sched/debug.c:sched_debug_header
  - kernel/power/main.c:ksys_sync_helper
  - kernel/power/main.c:ksys_sync_helper
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image
  - kernel/power/swap.c:save_image
  - kernel/power/swap.c:save_image
  - kernel/power/wakelock.c:wakelock_lookup_add
  - kernel/power/wakelock.c:__wakelocks_gc
  - kernel/time/timer.c:usleep_range
  - kernel/time/timer_list.c:timer_list_start
  - kernel/time/timer_list.c:sysrq_timer_list_show
  - kernel/time/posix-timers.c:posix_get_monotonic_ktime
  - kernel/time/clockevents.c:clockevents_program_event
  - kernel/time/clockevents.c:clockevents_program_min_delta
  - kernel/time/tick-common.c:tick_setup_device
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-oneshot.c:tick_resume_oneshot
  - kernel/time/tick-sched.c:tick_setup_sched_timer
  - kernel/time/tick-sched.c:tick_sched_timer
  - kernel/time/tick-sched.c:tick_irq_enter
  - kernel/time/tick-sched.c:tick_nohz_handler
  - kernel/time/tick-sched.c:tick_nohz_idle_exit
  - kernel/time/tick-sched.c:tick_nohz_idle_restart_tick
  - kernel/time/tick-sched.c:tick_nohz_irq_exit
  - kernel/time/tick-sched.c:tick_nohz_idle_enter
  - kernel/time/tick-sched.c:get_cpu_iowait_time_us
  - kernel/time/tick-sched.c:get_cpu_idle_time_us
  - kernel/futex.c:__ia32_sys_futex_time32
  - kernel/futex.c:__x64_sys_futex_time32
  - kernel/futex.c:__ia32_sys_futex
  - kernel/futex.c:__x64_sys_futex
  - kernel/acct.c:fill_ac
  - kernel/delayacct.c:__delayacct_thrashing_end
  - kernel/delayacct.c:__delayacct_thrashing_start
  - kernel/delayacct.c:__delayacct_freepages_end
  - kernel/delayacct.c:__delayacct_freepages_start
  - kernel/delayacct.c:__delayacct_blkio_end
  - kernel/delayacct.c:__delayacct_blkio_start
  - kernel/taskstats.c:fill_stats_for_tgid
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/trace/blktrace.c:__blk_add_trace
  - kernel/trace/blktrace.c:trace_note
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - fs/ext4/extents_status.c:__es_shrink
  - fs/ext4/extents_status.c:__es_shrink
  - fs/ext4/fast_commit.c:ext4_fc_commit
  - fs/ext4/fast_commit.c:ext4_fc_commit
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2_get_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - crypto/jitterentropy-kcapi.c:jent_get_nstime
  - block/bio.c:__bio_clone_fast
  - block/blk-core.c:submit_bio_checks
  - block/blk-core.c:submit_bio_checks
  - block/blk-core.c:blk_rq_init
  - block/blk-flush.c:flush_end_io
  - block/blk-flush.c:flush_end_io
  - block/blk-mq.c:blk_mq_try_issue_list_directly
  - block/blk-mq.c:blk_mq_start_request
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - block/blk-mq.c:__blk_mq_alloc_request
  - block/blk-mq.c:blk_mq_rq_ctx_init
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:throtl_tg_is_idle
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-iocost.c:ioc_now
  - block/blk-wbt.c:wb_timer_fn
  - block/blk-crypto-fallback.c:blk_crypto_clone_bio
  - lib/dim/net_dim.c:net_dim
  - lib/dim/rdma_dim.c:rdma_dim
  - lib/dim/rdma_dim.c:rdma_dim
  - drivers/gpio/gpiolib-cdev.c:debounce_work_func
  - drivers/gpio/gpiolib-cdev.c:edge_irq_handler
  - drivers/gpio/gpiolib-cdev.c:edge_irq_thread
  - drivers/pci/quirks.c:pci_fixup_device
  - drivers/pci/quirks.c:pci_fixup_device
  - drivers/acpi/button.c:acpi_lid_input_open
  - drivers/acpi/button.c:acpi_button_resume
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
  - drivers/acpi/cppc_acpi.c:check_pcc_chan
  - drivers/acpi/cppc_acpi.c:check_pcc_chan
  - drivers/dma/lgm/lgm-dma.c:ldma_chan_reset
  - drivers/dma/lgm/lgm-dma.c:ldma_chan_reset
  - drivers/dma/lgm/lgm-dma.c:ldma_chan_off
  - drivers/dma/lgm/lgm-dma.c:ldma_chan_off
  - drivers/xen/events/events_base.c:handle_irq_for_port
  - drivers/regulator/core.c:_regulator_do_disable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/connector/cn_proc.c:proc_exit_connector
  - drivers/connector/cn_proc.c:proc_coredump_connector
  - drivers/connector/cn_proc.c:proc_comm_connector
  - drivers/connector/cn_proc.c:proc_ptrace_connector
  - drivers/connector/cn_proc.c:proc_sid_connector
  - drivers/connector/cn_proc.c:proc_id_connector
  - drivers/connector/cn_proc.c:proc_exec_connector
  - drivers/connector/cn_proc.c:proc_fork_connector
  - drivers/base/dd.c:driver_probe_device
  - drivers/base/dd.c:driver_probe_device
  - drivers/base/power/main.c:dpm_suspend_start
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_end
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_noirq_resume_devices
  - drivers/base/power/main.c:dpm_show_time
  - drivers/base/power/wakeup.c:wakeup_source_activate
  - drivers/base/power/wakeup_stats.c:prevent_suspend_time_ms_show
  - drivers/base/power/wakeup_stats.c:max_time_ms_show
  - drivers/base/power/wakeup_stats.c:total_time_ms_show
  - drivers/base/power/wakeup_stats.c:active_time_ms_show
  - drivers/base/power/domain.c:total_idle_time_show
  - drivers/base/power/domain.c:active_time_show
  - drivers/base/power/domain.c:idle_states_show
  - drivers/base/power/domain.c:pm_genpd_init
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_runtime_suspend
  - drivers/base/power/domain.c:genpd_runtime_suspend
  - drivers/base/power/domain.c:genpd_power_on
  - drivers/base/power/domain.c:_genpd_power_off
  - drivers/base/power/domain.c:_genpd_power_off
  - drivers/base/power/domain.c:_genpd_power_on
  - drivers/base/power/domain.c:_genpd_power_on
  - drivers/base/power/domain_governor.c:cpu_power_down_ok
  - drivers/base/power/domain_governor.c:default_power_down_ok
  - drivers/misc/sram.c:atmel_securam_wait
  - drivers/misc/sram.c:atmel_securam_wait
  - drivers/mfd/arizona-core.c:arizona_poll_reg
  - drivers/mfd/arizona-core.c:arizona_poll_reg
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
  - drivers/dma-buf/dma-fence.c:dma_fence_get_status
  - drivers/dma-buf/dma-fence.c:dma_fence_release
  - drivers/dma-buf/dma-fence.c:dma_fence_allocate_private_stub
  - drivers/dma-buf/dma-fence.c:dma_fence_get_stub
  - drivers/usb/dwc2/core.c:dwc2_wait_for_mode
  - drivers/usb/dwc2/core.c:dwc2_wait_for_mode
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
  - drivers/usb/host/ehci-hcd.c:sitd_complete
  - drivers/usb/host/ehci-hcd.c:itd_complete
  - drivers/usb/host/ehci-hcd.c:unlink_empty_async
  - drivers/usb/host/ehci-hcd.c:end_unlink_async
  - drivers/usb/host/ehci-hcd.c:ehci_hrtimer_func
  - drivers/usb/host/ehci-hcd.c:end_free_itds
  - drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks
  - drivers/usb/host/ehci-hcd.c:ehci_handle_start_intr_unlinks
  - drivers/usb/host/xhci.c:xhci_set_usb2_hardware_lpm
  - drivers/usb/host/xhci.c:xhci_set_usb2_hardware_lpm
  - drivers/usb/host/xhci.c:xhci_handshake
  - drivers/usb/host/xhci.c:xhci_handshake
  - drivers/usb/early/ehci-dbgp.c:dbgp_wait_until_done
  - drivers/usb/early/ehci-dbgp.c:dbgp_wait_until_done
  - drivers/usb/early/xhci-dbc.c:xdbc_handle_events
  - drivers/usb/early/xhci-dbc.c:xdbc_handle_events
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
  - drivers/input/input.c:input_get_timestamp
  - drivers/input/input.c:input_repeat_key
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_check_stopbit
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_check_stopbit
  - drivers/power/reset/mt6323-poweroff.c:mt6323_do_pwroff
  - drivers/power/reset/mt6323-poweroff.c:mt6323_do_pwroff
  - drivers/power/supply/charger-manager.c:check_charging_duration
  - drivers/thermal/thermal_sysfs.c:cooling_device_stats_setup
  - drivers/thermal/thermal_sysfs.c:reset_store
  - drivers/thermal/thermal_sysfs.c:time_in_state_ms_show
  - drivers/thermal/thermal_sysfs.c:thermal_cooling_device_stats_update
  - drivers/watchdog/watchdog_dev.c:watchdog_set_last_hw_keepalive
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
  - drivers/watchdog/watchdog_dev.c:watchdog_start
  - drivers/watchdog/watchdog_dev.c:watchdog_ping_work
  - drivers/watchdog/watchdog_dev.c:watchdog_ping
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/watchdog/watchdog_dev.c:watchdog_next_keepalive
  - drivers/md/dm-stats.c:dm_stats_account_io
  - drivers/md/dm-stats.c:dm_stats_account_io
  - drivers/md/dm-stats.c:dm_stat_round
  - drivers/md/dm-rq.c:map_request
  - net/bpf/test_run.c:bpf_prog_test_run_sk_lookup
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_timer_continue
  - net/bpf/test_run.c:bpf_test_timer_continue
  - net/bpf/test_run.c:bpf_test_timer_continue
  - net/ipv4/tcp_input.c:tcp_synack_rtt_meas
  - net/ipv4/tcp_output.c:tcp_send_window_probe
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/mptcp/protocol.c:mptcp_rcv_space_adjust
```
**Symbols:**

```
ffffffff811469a0-ffffffff81146a37: ktime_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
ktime_t ktime_get();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/timekeeping.c (0)
Location: kernel/time/timekeeping.c:817
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_get_on_cpu
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_prepare_all
  - arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_get_khz
  - arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_snapshot_khz
  - kernel/fork.c:copy_process
  - kernel/async.c:async_synchronize_cookie_domain
  - kernel/async.c:async_synchronize_cookie_domain
  - kernel/async.c:async_run_entry_fn
  - kernel/async.c:async_run_entry_fn
  - kernel/sched/clock.c:sched_clock_tick_stable
  - kernel/sched/clock.c:__sched_clock_work
  - kernel/sched/debug.c:sched_debug_header
  - kernel/power/main.c:ksys_sync_helper
  - kernel/power/main.c:ksys_sync_helper
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image
  - kernel/power/swap.c:save_image
  - kernel/power/swap.c:save_image
  - kernel/power/wakelock.c:wakelock_lookup_add
  - kernel/power/wakelock.c:__wakelocks_gc
  - kernel/time/timer.c:usleep_range_state
  - kernel/time/timer_list.c:timer_list_start
  - kernel/time/timer_list.c:sysrq_timer_list_show
  - kernel/time/posix-timers.c:posix_get_monotonic_ktime
  - kernel/time/clockevents.c:clockevents_program_event
  - kernel/time/clockevents.c:clockevents_program_min_delta
  - kernel/time/tick-common.c:tick_setup_device
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-oneshot.c:tick_resume_oneshot
  - kernel/time/tick-sched.c:tick_setup_sched_timer
  - kernel/time/tick-sched.c:tick_sched_timer
  - kernel/time/tick-sched.c:tick_irq_enter
  - kernel/time/tick-sched.c:tick_nohz_handler
  - kernel/time/tick-sched.c:tick_nohz_idle_exit
  - kernel/time/tick-sched.c:tick_nohz_idle_restart_tick
  - kernel/time/tick-sched.c:tick_nohz_irq_exit
  - kernel/time/tick-sched.c:tick_nohz_idle_enter
  - kernel/time/tick-sched.c:get_cpu_iowait_time_us
  - kernel/time/tick-sched.c:get_cpu_idle_time_us
  - kernel/futex.c:__ia32_sys_futex_time32
  - kernel/futex.c:__x64_sys_futex_time32
  - kernel/futex.c:__ia32_sys_futex
  - kernel/futex.c:__x64_sys_futex
  - kernel/acct.c:fill_ac
  - kernel/taskstats.c:fill_stats_for_tgid
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/trace/blktrace.c:__blk_add_trace
  - kernel/trace/blktrace.c:trace_note
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - fs/io_uring.c:io_cqring_wait
  - fs/ext4/extents_status.c:__es_shrink
  - fs/ext4/extents_status.c:__es_shrink
  - fs/ext4/fast_commit.c:ext4_fc_commit
  - fs/ext4/fast_commit.c:ext4_fc_commit
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - crypto/jitterentropy-kcapi.c:jent_get_nstime
  - block/bio.c:__bio_clone_fast
  - block/blk-core.c:submit_bio_checks
  - block/blk-core.c:blk_rq_init
  - block/blk-flush.c:flush_end_io
  - block/blk-flush.c:flush_end_io
  - block/blk-mq.c:blk_mq_try_issue_list_directly
  - block/blk-mq.c:blk_mq_start_request
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - block/blk-mq.c:__blk_mq_alloc_request
  - block/blk-mq.c:blk_mq_rq_ctx_init
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:throtl_tg_is_idle
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-iocost.c:ioc_now
  - block/blk-wbt.c:wb_timer_fn
  - block/blk-crypto-fallback.c:blk_crypto_clone_bio
  - lib/dim/net_dim.c:net_dim
  - lib/dim/rdma_dim.c:rdma_dim
  - lib/dim/rdma_dim.c:rdma_dim
  - drivers/gpio/gpiolib-cdev.c:debounce_work_func
  - drivers/gpio/gpiolib-cdev.c:edge_irq_handler
  - drivers/gpio/gpiolib-cdev.c:edge_irq_thread
  - drivers/pci/quirks.c:pci_fixup_device
  - drivers/pci/quirks.c:pci_fixup_device
  - drivers/acpi/button.c:acpi_lid_input_open
  - drivers/acpi/button.c:acpi_button_resume
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
  - drivers/acpi/cppc_acpi.c:check_pcc_chan
  - drivers/acpi/cppc_acpi.c:check_pcc_chan
  - drivers/dma/lgm/lgm-dma.c:ldma_chan_reset
  - drivers/dma/lgm/lgm-dma.c:ldma_chan_reset
  - drivers/dma/lgm/lgm-dma.c:ldma_chan_off
  - drivers/dma/lgm/lgm-dma.c:ldma_chan_off
  - drivers/xen/events/events_base.c:handle_irq_for_port
  - drivers/regulator/core.c:_regulator_do_disable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/iommu/intel/svm.c:intel_svm_page_response
  - drivers/connector/cn_proc.c:proc_exit_connector
  - drivers/connector/cn_proc.c:proc_coredump_connector
  - drivers/connector/cn_proc.c:proc_comm_connector
  - drivers/connector/cn_proc.c:proc_ptrace_connector
  - drivers/connector/cn_proc.c:proc_sid_connector
  - drivers/connector/cn_proc.c:proc_id_connector
  - drivers/connector/cn_proc.c:proc_exec_connector
  - drivers/connector/cn_proc.c:proc_fork_connector
  - drivers/base/dd.c:__driver_probe_device
  - drivers/base/dd.c:__driver_probe_device
  - drivers/base/power/main.c:dpm_suspend_start
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_end
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_noirq_resume_devices
  - drivers/base/power/main.c:dpm_show_time
  - drivers/base/power/wakeup.c:wakeup_source_report_event
  - drivers/base/power/wakeup_stats.c:prevent_suspend_time_ms_show
  - drivers/base/power/wakeup_stats.c:max_time_ms_show
  - drivers/base/power/wakeup_stats.c:total_time_ms_show
  - drivers/base/power/wakeup_stats.c:active_time_ms_show
  - drivers/base/power/domain.c:total_idle_time_show
  - drivers/base/power/domain.c:active_time_show
  - drivers/base/power/domain.c:idle_states_show
  - drivers/base/power/domain.c:pm_genpd_init
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_runtime_suspend
  - drivers/base/power/domain.c:genpd_runtime_suspend
  - drivers/base/power/domain.c:genpd_power_on
  - drivers/base/power/domain.c:_genpd_power_off
  - drivers/base/power/domain.c:_genpd_power_off
  - drivers/base/power/domain.c:_genpd_power_on
  - drivers/base/power/domain.c:_genpd_power_on
  - drivers/base/power/domain_governor.c:cpu_power_down_ok
  - drivers/base/power/domain_governor.c:default_power_down_ok
  - drivers/misc/sram.c:atmel_securam_wait
  - drivers/misc/sram.c:atmel_securam_wait
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
  - drivers/dma-buf/dma-fence.c:dma_fence_get_status
  - drivers/dma-buf/dma-fence.c:dma_fence_release
  - drivers/dma-buf/dma-fence.c:dma_fence_allocate_private_stub
  - drivers/dma-buf/dma-fence.c:dma_fence_get_stub
  - drivers/spi/spi-mem.c:spi_mem_poll_status
  - drivers/spi/spi-mem.c:spi_mem_poll_status
  - drivers/usb/dwc2/core.c:dwc2_wait_for_mode
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
  - drivers/usb/host/ehci-hcd.c:sitd_complete
  - drivers/usb/host/ehci-hcd.c:itd_complete
  - drivers/usb/host/ehci-hcd.c:unlink_empty_async
  - drivers/usb/host/ehci-hcd.c:end_unlink_async
  - drivers/usb/host/ehci-hcd.c:ehci_hrtimer_func
  - drivers/usb/host/ehci-hcd.c:end_free_itds
  - drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks
  - drivers/usb/host/ehci-hcd.c:ehci_handle_start_intr_unlinks
  - drivers/usb/host/xhci.c:xhci_set_usb2_hardware_lpm
  - drivers/usb/host/xhci.c:xhci_set_usb2_hardware_lpm
  - drivers/usb/host/xhci.c:xhci_handshake
  - drivers/usb/host/xhci.c:xhci_handshake
  - drivers/usb/early/ehci-dbgp.c:dbgp_wait_until_done
  - drivers/usb/early/ehci-dbgp.c:dbgp_wait_until_done
  - drivers/input/input.c:input_get_timestamp
  - drivers/input/input.c:input_repeat_key
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_check_stopbit
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_check_stopbit
  - drivers/power/reset/mt6323-poweroff.c:mt6323_do_pwroff
  - drivers/power/reset/mt6323-poweroff.c:mt6323_do_pwroff
  - drivers/power/supply/charger-manager.c:check_charging_duration
  - drivers/thermal/thermal_sysfs.c:cooling_device_stats_setup
  - drivers/thermal/thermal_sysfs.c:reset_store
  - drivers/thermal/thermal_sysfs.c:time_in_state_ms_show
  - drivers/thermal/thermal_sysfs.c:thermal_cooling_device_stats_update
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
  - drivers/watchdog/watchdog_dev.c:watchdog_start
  - drivers/watchdog/watchdog_dev.c:watchdog_worker_should_ping
  - drivers/watchdog/watchdog_dev.c:watchdog_ping
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/watchdog/watchdog_dev.c:watchdog_next_keepalive
  - drivers/md/dm-stats.c:dm_stats_account_io
  - drivers/md/dm-stats.c:dm_stats_account_io
  - drivers/md/dm-stats.c:dm_stat_round
  - drivers/md/dm-rq.c:map_request
  - net/bpf/test_run.c:bpf_prog_test_run_sk_lookup
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_timer_continue
  - net/bpf/test_run.c:bpf_test_timer_continue
  - net/bpf/test_run.c:bpf_test_timer_continue
  - net/ipv4/tcp_input.c:tcp_synack_rtt_meas
  - net/ipv4/tcp_output.c:tcp_send_window_probe
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/mptcp/protocol.c:mptcp_rcv_space_adjust
```
**Symbols:**

```
ffffffff81cb0d52-ffffffff81cb0d76: ktime_get.cold (STB_LOCAL)
ffffffff81169aa0-ffffffff81169b51: ktime_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
ktime_t ktime_get();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/timekeeping.c (0)
Location: kernel/time/timekeeping.c:836
Inline: False
Direct callers:
  - init/main.c:trace_initcall_finish_cb
  - init/main.c:trace_initcall_start_cb
  - kernel/fork.c:copy_process
  - kernel/async.c:async_synchronize_cookie_domain
  - kernel/async.c:async_synchronize_cookie_domain
  - kernel/async.c:async_run_entry_fn
  - kernel/async.c:async_run_entry_fn
  - kernel/sched/build_utility.c:sched_debug_header
  - kernel/sched/build_utility.c:sched_clock_tick_stable
  - kernel/sched/build_utility.c:__sched_clock_work
  - kernel/power/main.c:ksys_sync_helper
  - kernel/power/main.c:ksys_sync_helper
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image
  - kernel/power/swap.c:save_image
  - kernel/power/swap.c:save_image
  - kernel/power/wakelock.c:wakelock_lookup_add
  - kernel/power/wakelock.c:__wakelocks_gc
  - kernel/time/timer.c:usleep_range_state
  - kernel/time/timer_list.c:timer_list_start
  - kernel/time/timer_list.c:sysrq_timer_list_show
  - kernel/time/posix-timers.c:posix_get_monotonic_ktime
  - kernel/time/clockevents.c:clockevents_program_event
  - kernel/time/clockevents.c:clockevents_program_min_delta
  - kernel/time/tick-common.c:tick_setup_device
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-oneshot.c:tick_resume_oneshot
  - kernel/time/tick-sched.c:tick_setup_sched_timer
  - kernel/time/tick-sched.c:tick_sched_timer
  - kernel/time/tick-sched.c:tick_irq_enter
  - kernel/time/tick-sched.c:tick_nohz_handler
  - kernel/time/tick-sched.c:tick_nohz_idle_exit
  - kernel/time/tick-sched.c:tick_nohz_idle_restart_tick
  - kernel/time/tick-sched.c:tick_nohz_irq_exit
  - kernel/time/tick-sched.c:tick_nohz_idle_enter
  - kernel/time/tick-sched.c:get_cpu_iowait_time_us
  - kernel/time/tick-sched.c:get_cpu_idle_time_us
  - kernel/futex/syscalls.c:__ia32_sys_futex_time32
  - kernel/futex/syscalls.c:__x64_sys_futex_time32
  - kernel/futex/syscalls.c:__ia32_sys_futex
  - kernel/futex/syscalls.c:__x64_sys_futex
  - kernel/acct.c:fill_ac
  - kernel/taskstats.c:fill_stats_for_tgid
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/trace/blktrace.c:__blk_add_trace
  - kernel/trace/blktrace.c:trace_note
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - fs/ext4/extents_status.c:__es_shrink
  - fs/ext4/extents_status.c:__es_shrink
  - fs/ext4/fast_commit.c:ext4_fc_commit
  - fs/ext4/fast_commit.c:ext4_fc_commit
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - ipc/sem.c:__do_semtimedop
  - crypto/jitterentropy-kcapi.c:jent_get_nstime
  - block/blk-core.c:submit_bio_noacct
  - block/blk-flush.c:flush_end_io
  - block/blk-flush.c:flush_end_io
  - block/blk-merge.c:__blk_queue_split
  - block/blk-mq.c:blk_insert_cloned_request
  - block/blk-mq.c:blk_mq_try_issue_list_directly
  - block/blk-mq.c:blk_mq_start_request
  - block/blk-mq.c:blk_mq_end_request_batch
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - block/blk-mq.c:__blk_mq_alloc_requests
  - block/blk-mq.c:blk_rq_init
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-throttle.c:__blk_throtl_bio
  - block/blk-throttle.c:throtl_tg_is_idle
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-iocost.c:ioc_now
  - block/blk-wbt.c:wb_timer_fn
  - io_uring/io_uring.c:io_cqring_wait
  - lib/dim/net_dim.c:net_dim
  - lib/dim/rdma_dim.c:rdma_dim
  - lib/dim/rdma_dim.c:rdma_dim
  - drivers/gpio/gpiolib-cdev.c:lineinfo_changed_notify
  - drivers/gpio/gpiolib-cdev.c:lineevent_irq_handler
  - drivers/gpio/gpiolib-cdev.c:lineevent_irq_thread
  - drivers/gpio/gpiolib-cdev.c:debounce_work_func
  - drivers/gpio/gpiolib-cdev.c:edge_irq_handler
  - drivers/gpio/gpiolib-cdev.c:edge_irq_thread
  - drivers/pci/quirks.c:pci_fixup_device
  - drivers/pci/quirks.c:pci_fixup_device
  - drivers/acpi/button.c:acpi_lid_input_open
  - drivers/acpi/button.c:acpi_button_resume
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
  - drivers/acpi/cppc_acpi.c:check_pcc_chan
  - drivers/acpi/cppc_acpi.c:check_pcc_chan
  - drivers/dma/lgm/lgm-dma.c:ldma_chan_reset
  - drivers/dma/lgm/lgm-dma.c:ldma_chan_reset
  - drivers/dma/lgm/lgm-dma.c:ldma_chan_off
  - drivers/dma/lgm/lgm-dma.c:ldma_chan_off
  - drivers/xen/events/events_base.c:handle_irq_for_port
  - drivers/regulator/core.c:_regulator_do_disable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/char/random.c:random_pm_notification
  - drivers/iommu/intel/svm.c:intel_svm_page_response
  - drivers/connector/cn_proc.c:proc_exit_connector
  - drivers/connector/cn_proc.c:proc_coredump_connector
  - drivers/connector/cn_proc.c:proc_comm_connector
  - drivers/connector/cn_proc.c:proc_ptrace_connector
  - drivers/connector/cn_proc.c:proc_sid_connector
  - drivers/connector/cn_proc.c:proc_id_connector
  - drivers/connector/cn_proc.c:proc_exec_connector
  - drivers/connector/cn_proc.c:proc_fork_connector
  - drivers/base/dd.c:__driver_probe_device
  - drivers/base/dd.c:__driver_probe_device
  - drivers/base/power/main.c:dpm_suspend_start
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_end
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_noirq_resume_devices
  - drivers/base/power/main.c:dpm_show_time
  - drivers/base/power/wakeup.c:wakeup_source_activate
  - drivers/base/power/wakeup_stats.c:prevent_suspend_time_ms_show
  - drivers/base/power/wakeup_stats.c:max_time_ms_show
  - drivers/base/power/wakeup_stats.c:total_time_ms_show
  - drivers/base/power/wakeup_stats.c:active_time_ms_show
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_runtime_suspend
  - drivers/base/power/domain.c:genpd_runtime_suspend
  - drivers/base/power/domain.c:_genpd_power_off
  - drivers/base/power/domain.c:_genpd_power_off
  - drivers/base/power/domain.c:_genpd_power_on
  - drivers/base/power/domain.c:_genpd_power_on
  - drivers/base/power/domain_governor.c:cpu_power_down_ok
  - drivers/base/power/domain_governor.c:default_power_down_ok
  - drivers/misc/sram.c:atmel_securam_wait
  - drivers/misc/sram.c:atmel_securam_wait
  - drivers/dma-buf/dma-fence.c:dma_fence_describe
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
  - drivers/dma-buf/dma-fence.c:dma_fence_get_status
  - drivers/dma-buf/dma-fence.c:__dma_fence_enable_signaling
  - drivers/dma-buf/dma-fence.c:dma_fence_release
  - drivers/dma-buf/dma-fence.c:dma_fence_allocate_private_stub
  - drivers/dma-buf/dma-fence.c:dma_fence_get_stub
  - drivers/spi/spi-mem.c:spi_mem_poll_status
  - drivers/spi/spi-mem.c:spi_mem_poll_status
  - drivers/net/phy/phy_device.c:genphy_loopback
  - drivers/net/phy/phy_device.c:genphy_loopback
  - drivers/cdrom/cdrom.c:cdrom_ioctl_media_changed
  - drivers/cdrom/cdrom.c:cdrom_select_disc
  - drivers/cdrom/cdrom.c:cdrom_select_disc
  - drivers/cdrom/cdrom.c:register_cdrom
  - drivers/usb/dwc2/core.c:dwc2_wait_for_mode
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
  - drivers/usb/host/ehci-hcd.c:sitd_complete
  - drivers/usb/host/ehci-hcd.c:itd_complete
  - drivers/usb/host/ehci-hcd.c:unlink_empty_async
  - drivers/usb/host/ehci-hcd.c:end_unlink_async
  - drivers/usb/host/ehci-hcd.c:ehci_hrtimer_func
  - drivers/usb/host/ehci-hcd.c:end_free_itds
  - drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks
  - drivers/usb/host/ehci-hcd.c:ehci_handle_start_intr_unlinks
  - drivers/usb/host/xhci.c:xhci_set_usb2_hardware_lpm
  - drivers/usb/host/xhci.c:xhci_set_usb2_hardware_lpm
  - drivers/usb/host/xhci.c:xhci_handshake
  - drivers/usb/host/xhci.c:xhci_handshake
  - drivers/usb/early/ehci-dbgp.c:dbgp_wait_until_done
  - drivers/usb/early/ehci-dbgp.c:dbgp_wait_until_done
  - drivers/input/input.c:input_get_timestamp
  - drivers/input/input.c:input_repeat_key
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_check_stopbit
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_check_stopbit
  - drivers/i2c/busses/i2c-designware-amdpsp.c:psp_send_i2c_req
  - drivers/i2c/busses/i2c-designware-amdpsp.c:psp_send_i2c_req
  - drivers/i2c/busses/i2c-designware-amdpsp.c:psp_send_check_i2c_req
  - drivers/i2c/busses/i2c-designware-amdpsp.c:psp_send_check_i2c_req
  - drivers/i2c/busses/i2c-designware-amdpsp.c:psp_send_check_i2c_req
  - drivers/i2c/busses/i2c-designware-amdpsp.c:psp_send_check_i2c_req
  - drivers/power/reset/mt6323-poweroff.c:mt6323_do_pwroff
  - drivers/power/reset/mt6323-poweroff.c:mt6323_do_pwroff
  - drivers/power/supply/charger-manager.c:check_charging_duration
  - drivers/thermal/thermal_sysfs.c:cooling_device_stats_setup
  - drivers/thermal/thermal_sysfs.c:reset_store
  - drivers/thermal/thermal_sysfs.c:time_in_state_ms_show
  - drivers/thermal/thermal_sysfs.c:thermal_cooling_device_stats_update
  - drivers/watchdog/watchdog_dev.c:watchdog_set_last_hw_keepalive
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
  - drivers/watchdog/watchdog_dev.c:watchdog_start
  - drivers/watchdog/watchdog_dev.c:watchdog_worker_should_ping
  - drivers/watchdog/watchdog_dev.c:watchdog_ping
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/watchdog/watchdog_dev.c:watchdog_next_keepalive
  - drivers/md/dm.c:dm_split_and_process_bio
  - drivers/md/dm-stats.c:dm_stats_account_io
  - drivers/md/dm-stats.c:dm_stat_round
  - net/bpf/test_run.c:bpf_prog_test_run_sk_lookup
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run_xdp_live
  - net/bpf/test_run.c:bpf_test_timer_continue
  - net/bpf/test_run.c:bpf_test_timer_continue
  - net/bpf/test_run.c:bpf_test_timer_continue
  - net/ipv4/tcp_input.c:tcp_synack_rtt_meas
  - net/ipv4/tcp_output.c:tcp_send_window_probe
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/mptcp/protocol.c:mptcp_rcv_space_adjust
```
**Symbols:**

```
ffffffff81e622b9-ffffffff81e622dd: ktime_get.cold (STB_LOCAL)
ffffffff8119d6a0-ffffffff8119d757: ktime_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
ktime_t ktime_get();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/timekeeping.c (0)
Location: kernel/time/timekeeping.c:836
Inline: False
Direct callers:
  - init/main.c:trace_initcall_finish_cb
  - init/main.c:trace_initcall_start_cb
  - kernel/fork.c:copy_process
  - kernel/async.c:async_synchronize_cookie_domain
  - kernel/async.c:async_synchronize_cookie_domain
  - kernel/async.c:async_run_entry_fn
  - kernel/async.c:async_run_entry_fn
  - kernel/sched/build_utility.c:sched_debug_header
  - kernel/sched/build_utility.c:sched_clock_tick_stable
  - kernel/sched/build_utility.c:sched_clock_init
  - kernel/sched/build_utility.c:__sched_clock_work
  - kernel/power/main.c:ksys_sync_helper
  - kernel/power/main.c:ksys_sync_helper
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image
  - kernel/power/swap.c:save_image
  - kernel/power/swap.c:save_image
  - kernel/power/wakelock.c:wakelock_lookup_add
  - kernel/power/wakelock.c:__wakelocks_gc
  - kernel/time/timer.c:usleep_range_state
  - kernel/time/timer_list.c:timer_list_start
  - kernel/time/timer_list.c:sysrq_timer_list_show
  - kernel/time/posix-timers.c:posix_get_monotonic_ktime
  - kernel/time/clockevents.c:clockevents_program_event
  - kernel/time/clockevents.c:clockevents_program_min_delta
  - kernel/time/tick-common.c:tick_setup_device
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-oneshot.c:tick_resume_oneshot
  - kernel/time/tick-sched.c:tick_setup_sched_timer
  - kernel/time/tick-sched.c:tick_sched_timer
  - kernel/time/tick-sched.c:tick_irq_enter
  - kernel/time/tick-sched.c:tick_nohz_handler
  - kernel/time/tick-sched.c:tick_nohz_idle_exit
  - kernel/time/tick-sched.c:tick_nohz_idle_restart_tick
  - kernel/time/tick-sched.c:tick_nohz_irq_exit
  - kernel/time/tick-sched.c:tick_nohz_idle_enter
  - kernel/time/tick-sched.c:get_cpu_iowait_time_us
  - kernel/time/tick-sched.c:get_cpu_idle_time_us
  - kernel/futex/syscalls.c:__ia32_sys_futex_time32
  - kernel/futex/syscalls.c:__x64_sys_futex_time32
  - kernel/futex/syscalls.c:__ia32_sys_futex
  - kernel/futex/syscalls.c:__x64_sys_futex
  - kernel/acct.c:fill_ac
  - kernel/taskstats.c:fill_stats_for_tgid
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/trace/blktrace.c:__blk_add_trace
  - kernel/trace/blktrace.c:trace_note
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - fs/ext4/extents_status.c:__es_shrink
  - fs/ext4/extents_status.c:__es_shrink
  - fs/ext4/fast_commit.c:ext4_fc_commit
  - fs/ext4/fast_commit.c:ext4_fc_commit
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - ipc/sem.c:__do_semtimedop
  - crypto/jitterentropy-kcapi.c:jent_get_nstime
  - block/blk-core.c:submit_bio_noacct_nocheck
  - block/blk-flush.c:flush_end_io
  - block/blk-flush.c:flush_end_io
  - block/blk-merge.c:__bio_split_to_limits
  - block/blk-mq.c:blk_insert_cloned_request
  - block/blk-mq.c:blk_mq_start_request
  - block/blk-mq.c:blk_mq_end_request_batch
  - block/blk-mq.c:__blk_mq_end_request
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - block/blk-mq.c:__blk_mq_alloc_requests
  - block/blk-mq.c:blk_rq_init
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-iocost.c:ioc_now
  - block/blk-wbt.c:wb_timer_fn
  - io_uring/io_uring.c:io_cqring_wait
  - io_uring/cancel.c:io_sync_cancel
  - lib/dim/net_dim.c:net_dim
  - lib/dim/rdma_dim.c:rdma_dim
  - lib/dim/rdma_dim.c:rdma_dim
  - drivers/gpio/gpiolib-cdev.c:lineinfo_changed_notify
  - drivers/gpio/gpiolib-cdev.c:lineevent_irq_handler
  - drivers/gpio/gpiolib-cdev.c:lineevent_irq_thread
  - drivers/gpio/gpiolib-cdev.c:line_event_timestamp
  - drivers/pci/quirks.c:pci_fixup_device
  - drivers/pci/quirks.c:pci_fixup_device
  - drivers/acpi/button.c:acpi_lid_input_open
  - drivers/acpi/button.c:acpi_button_resume
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
  - drivers/acpi/cppc_acpi.c:check_pcc_chan
  - drivers/acpi/cppc_acpi.c:check_pcc_chan
  - drivers/dma/lgm/lgm-dma.c:ldma_chan_reset
  - drivers/dma/lgm/lgm-dma.c:ldma_chan_reset
  - drivers/dma/lgm/lgm-dma.c:ldma_chan_off
  - drivers/dma/lgm/lgm-dma.c:ldma_chan_off
  - drivers/xen/events/events_base.c:handle_irq_for_port
  - drivers/char/random.c:random_pm_notification
  - drivers/iommu/intel/svm.c:intel_svm_page_response
  - drivers/connector/cn_proc.c:proc_exit_connector
  - drivers/connector/cn_proc.c:proc_coredump_connector
  - drivers/connector/cn_proc.c:proc_comm_connector
  - drivers/connector/cn_proc.c:proc_ptrace_connector
  - drivers/connector/cn_proc.c:proc_sid_connector
  - drivers/connector/cn_proc.c:proc_id_connector
  - drivers/connector/cn_proc.c:proc_exec_connector
  - drivers/connector/cn_proc.c:proc_fork_connector
  - drivers/base/dd.c:__driver_probe_device
  - drivers/base/dd.c:__driver_probe_device
  - drivers/base/power/main.c:dpm_suspend_start
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_end
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_noirq_resume_devices
  - drivers/base/power/main.c:dpm_run_callback
  - drivers/base/power/main.c:dpm_show_time
  - drivers/base/power/wakeup.c:wakeup_source_activate
  - drivers/base/power/wakeup_stats.c:prevent_suspend_time_ms_show
  - drivers/base/power/wakeup_stats.c:max_time_ms_show
  - drivers/base/power/wakeup_stats.c:total_time_ms_show
  - drivers/base/power/wakeup_stats.c:active_time_ms_show
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_runtime_suspend
  - drivers/base/power/domain.c:genpd_runtime_suspend
  - drivers/base/power/domain.c:_genpd_power_off
  - drivers/base/power/domain.c:_genpd_power_off
  - drivers/base/power/domain.c:_genpd_power_on
  - drivers/base/power/domain.c:_genpd_power_on
  - drivers/base/power/domain_governor.c:cpu_power_down_ok
  - drivers/base/power/domain_governor.c:default_power_down_ok
  - drivers/misc/sram.c:atmel_securam_wait
  - drivers/misc/sram.c:atmel_securam_wait
  - drivers/dma-buf/dma-fence.c:dma_fence_describe
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
  - drivers/dma-buf/dma-fence.c:dma_fence_get_status
  - drivers/dma-buf/dma-fence.c:__dma_fence_enable_signaling
  - drivers/dma-buf/dma-fence.c:dma_fence_release
  - drivers/dma-buf/dma-fence.c:dma_fence_allocate_private_stub
  - drivers/dma-buf/dma-fence.c:dma_fence_get_stub
  - drivers/spi/spi-mem.c:spi_mem_poll_status
  - drivers/spi/spi-mem.c:spi_mem_poll_status
  - drivers/net/phy/phy_device.c:genphy_loopback
  - drivers/net/phy/phy_device.c:genphy_loopback
  - drivers/cdrom/cdrom.c:cdrom_ioctl_media_changed
  - drivers/cdrom/cdrom.c:cdrom_select_disc
  - drivers/cdrom/cdrom.c:cdrom_select_disc
  - drivers/cdrom/cdrom.c:register_cdrom
  - drivers/usb/dwc2/core.c:dwc2_wait_for_mode
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
  - drivers/usb/host/ehci-hcd.c:sitd_complete
  - drivers/usb/host/ehci-hcd.c:itd_complete
  - drivers/usb/host/ehci-hcd.c:unlink_empty_async
  - drivers/usb/host/ehci-hcd.c:end_unlink_async
  - drivers/usb/host/ehci-hcd.c:ehci_hrtimer_func
  - drivers/usb/host/ehci-hcd.c:end_free_itds
  - drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks
  - drivers/usb/host/ehci-hcd.c:ehci_handle_start_intr_unlinks
  - drivers/usb/host/ehci-hcd.c:ehci_handle_controller_death
  - drivers/usb/host/xhci.c:xhci_set_usb2_hardware_lpm
  - drivers/usb/host/xhci.c:xhci_set_usb2_hardware_lpm
  - drivers/usb/host/xhci.c:xhci_handshake
  - drivers/usb/host/xhci.c:xhci_handshake
  - drivers/usb/early/ehci-dbgp.c:dbgp_wait_until_done
  - drivers/usb/early/ehci-dbgp.c:dbgp_wait_until_done
  - drivers/input/input.c:input_repeat_key
  - drivers/input/input.c:input_get_timestamp
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_check_stopbit
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_check_stopbit
  - drivers/i2c/busses/i2c-designware-amdpsp.c:psp_send_i2c_req
  - drivers/i2c/busses/i2c-designware-amdpsp.c:psp_send_i2c_req
  - drivers/i2c/busses/i2c-designware-amdpsp.c:psp_send_check_i2c_req
  - drivers/i2c/busses/i2c-designware-amdpsp.c:psp_send_check_i2c_req
  - drivers/i2c/busses/i2c-designware-amdpsp.c:psp_send_check_i2c_req
  - drivers/i2c/busses/i2c-designware-amdpsp.c:psp_send_check_i2c_req
  - drivers/power/reset/mt6323-poweroff.c:mt6323_do_pwroff
  - drivers/power/reset/mt6323-poweroff.c:mt6323_do_pwroff
  - drivers/power/supply/charger-manager.c:check_charging_duration
  - drivers/thermal/thermal_sysfs.c:thermal_cooling_device_setup_sysfs
  - drivers/thermal/thermal_sysfs.c:reset_store
  - drivers/thermal/thermal_sysfs.c:time_in_state_ms_show
  - drivers/thermal/thermal_sysfs.c:thermal_cooling_device_stats_update
  - drivers/watchdog/watchdog_dev.c:watchdog_set_last_hw_keepalive
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
  - drivers/watchdog/watchdog_dev.c:watchdog_start
  - drivers/watchdog/watchdog_dev.c:watchdog_worker_should_ping
  - drivers/watchdog/watchdog_dev.c:watchdog_ping
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/watchdog/watchdog_dev.c:watchdog_update_worker
  - drivers/md/dm.c:dm_split_and_process_bio
  - drivers/md/dm-stats.c:dm_stats_account_io
  - drivers/md/dm-stats.c:dm_stat_round
  - net/bpf/test_run.c:bpf_prog_test_run_sk_lookup
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run_xdp_live
  - net/bpf/test_run.c:bpf_test_timer_continue
  - net/bpf/test_run.c:bpf_test_timer_continue
  - net/bpf/test_run.c:bpf_test_timer_continue
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/ipv4/tcp.c:do_tcp_setsockopt
  - net/ipv4/tcp_input.c:tcp_synack_rtt_meas
  - net/ipv4/tcp_output.c:tcp_send_window_probe
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/mptcp/protocol.c:mptcp_rcv_space_adjust
```
**Symbols:**

```
ffffffff8205b12a-ffffffff8205b14e: ktime_get.cold (STB_LOCAL)
ffffffff811dc300-ffffffff811dc3b7: ktime_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
ktime_t ktime_get();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/timekeeping.c (0)
Location: kernel/time/timekeeping.c:836
Inline: False
Direct callers:
  - init/main.c:trace_initcall_finish_cb
  - init/main.c:trace_initcall_start_cb
  - kernel/fork.c:copy_process
  - kernel/cpu.c:cpuhp_wait_for_sync_state
  - kernel/cpu.c:cpuhp_wait_for_sync_state
  - kernel/async.c:async_synchronize_cookie_domain
  - kernel/async.c:async_synchronize_cookie_domain
  - kernel/async.c:async_run_entry_fn
  - kernel/async.c:async_run_entry_fn
  - kernel/sched/build_utility.c:sched_debug_header
  - kernel/sched/build_utility.c:sched_clock_tick_stable
  - kernel/sched/build_utility.c:sched_clock_init
  - kernel/sched/build_utility.c:__sched_clock_work
  - kernel/power/main.c:ksys_sync_helper
  - kernel/power/main.c:ksys_sync_helper
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image
  - kernel/power/swap.c:save_image
  - kernel/power/swap.c:save_image
  - kernel/power/wakelock.c:wakelock_lookup_add
  - kernel/power/wakelock.c:__wakelocks_gc
  - kernel/time/timer.c:usleep_range_state
  - kernel/time/timer_list.c:timer_list_start
  - kernel/time/timer_list.c:sysrq_timer_list_show
  - kernel/time/posix-timers.c:posix_get_monotonic_ktime
  - kernel/time/clockevents.c:clockevents_program_event
  - kernel/time/clockevents.c:clockevents_program_min_delta
  - kernel/time/tick-common.c:tick_setup_device
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-oneshot.c:tick_resume_oneshot
  - kernel/time/tick-sched.c:tick_setup_sched_timer
  - kernel/time/tick-sched.c:tick_sched_timer
  - kernel/time/tick-sched.c:tick_irq_enter
  - kernel/time/tick-sched.c:tick_nohz_handler
  - kernel/time/tick-sched.c:tick_nohz_idle_exit
  - kernel/time/tick-sched.c:tick_nohz_idle_restart_tick
  - kernel/time/tick-sched.c:tick_nohz_irq_exit
  - kernel/time/tick-sched.c:tick_nohz_idle_enter
  - kernel/futex/syscalls.c:__ia32_sys_futex_time32
  - kernel/futex/syscalls.c:__x64_sys_futex_time32
  - kernel/futex/syscalls.c:__ia32_sys_futex
  - kernel/futex/syscalls.c:__x64_sys_futex
  - kernel/acct.c:fill_ac
  - kernel/taskstats.c:fill_stats_for_tgid
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/trace/trace_osnoise.c:osnoise_sleep
  - kernel/trace/blktrace.c:__blk_add_trace
  - kernel/trace/blktrace.c:trace_note
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - fs/ext4/fast_commit.c:ext4_fc_commit
  - fs/ext4/fast_commit.c:ext4_fc_commit
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - ipc/sem.c:__do_semtimedop
  - crypto/jitterentropy-kcapi.c:jent_get_nstime
  - block/blk-core.c:submit_bio_noacct_nocheck
  - block/blk-flush.c:flush_end_io
  - block/blk-flush.c:flush_end_io
  - block/blk-merge.c:__bio_split_to_limits
  - block/blk-mq.c:blk_insert_cloned_request
  - block/blk-mq.c:blk_mq_submit_bio
  - block/blk-mq.c:blk_mq_start_request
  - block/blk-mq.c:blk_mq_end_request_batch
  - block/blk-mq.c:blk_mq_end_request
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - block/blk-mq.c:blk_mq_alloc_request
  - block/blk-mq.c:__blk_mq_alloc_requests
  - block/blk-mq.c:__blk_mq_alloc_requests
  - block/blk-mq.c:__blk_mq_alloc_requests
  - block/blk-mq.c:blk_rq_init
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-iocost.c:ioc_now
  - block/blk-wbt.c:wb_timer_fn
  - io_uring/io_uring.c:io_cqring_wait
  - io_uring/cancel.c:io_sync_cancel
  - lib/dim/net_dim.c:net_dim
  - lib/dim/rdma_dim.c:rdma_dim
  - lib/dim/rdma_dim.c:rdma_dim
  - drivers/gpio/gpiolib-cdev.c:lineinfo_changed_notify
  - drivers/gpio/gpiolib-cdev.c:lineevent_irq_handler
  - drivers/gpio/gpiolib-cdev.c:lineevent_irq_thread
  - drivers/gpio/gpiolib-cdev.c:line_event_timestamp
  - drivers/pci/quirks.c:pci_fixup_device
  - drivers/pci/quirks.c:pci_fixup_device
  - drivers/acpi/button.c:acpi_lid_input_open
  - drivers/acpi/button.c:acpi_button_resume
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
  - drivers/acpi/cppc_acpi.c:check_pcc_chan
  - drivers/acpi/cppc_acpi.c:check_pcc_chan
  - drivers/xen/events/events_base.c:handle_irq_for_port
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/char/random.c:random_pm_notification
  - drivers/iommu/intel/svm.c:intel_svm_page_response
  - drivers/connector/cn_proc.c:proc_exit_connector
  - drivers/connector/cn_proc.c:proc_coredump_connector
  - drivers/connector/cn_proc.c:proc_comm_connector
  - drivers/connector/cn_proc.c:proc_ptrace_connector
  - drivers/connector/cn_proc.c:proc_sid_connector
  - drivers/connector/cn_proc.c:proc_id_connector
  - drivers/connector/cn_proc.c:proc_exec_connector
  - drivers/connector/cn_proc.c:proc_fork_connector
  - drivers/base/dd.c:__driver_probe_device
  - drivers/base/dd.c:__driver_probe_device
  - drivers/base/power/main.c:dpm_suspend_start
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:dpm_suspend_end
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_noirq_resume_devices
  - drivers/base/power/main.c:dpm_run_callback
  - drivers/base/power/main.c:dpm_show_time
  - drivers/base/power/wakeup.c:wakeup_source_activate
  - drivers/base/power/wakeup_stats.c:prevent_suspend_time_ms_show
  - drivers/base/power/wakeup_stats.c:max_time_ms_show
  - drivers/base/power/wakeup_stats.c:total_time_ms_show
  - drivers/base/power/wakeup_stats.c:active_time_ms_show
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_runtime_suspend
  - drivers/base/power/domain.c:genpd_runtime_suspend
  - drivers/base/power/domain.c:_genpd_power_off
  - drivers/base/power/domain.c:_genpd_power_off
  - drivers/base/power/domain.c:_genpd_power_on
  - drivers/base/power/domain.c:_genpd_power_on
  - drivers/base/power/domain_governor.c:cpu_power_down_ok
  - drivers/base/power/domain_governor.c:default_power_down_ok
  - drivers/misc/sram.c:atmel_securam_wait
  - drivers/misc/sram.c:atmel_securam_wait
  - drivers/dma-buf/dma-fence.c:dma_fence_describe
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
  - drivers/dma-buf/dma-fence.c:dma_fence_get_status
  - drivers/dma-buf/dma-fence.c:__dma_fence_enable_signaling
  - drivers/dma-buf/dma-fence.c:dma_fence_release
  - drivers/dma-buf/dma-fence.c:dma_fence_get_stub
  - drivers/dma-buf/dma-fence-unwrap.c:__dma_fence_unwrap_merge
  - drivers/dma-buf/dma-fence-unwrap.c:__dma_fence_unwrap_merge
  - drivers/spi/spi-mem.c:spi_mem_poll_status
  - drivers/spi/spi-mem.c:spi_mem_poll_status
  - drivers/net/phy/phy_device.c:genphy_loopback
  - drivers/net/phy/phy_device.c:genphy_loopback
  - drivers/cdrom/cdrom.c:cdrom_ioctl_media_changed
  - drivers/cdrom/cdrom.c:cdrom_select_disc
  - drivers/cdrom/cdrom.c:cdrom_select_disc
  - drivers/cdrom/cdrom.c:register_cdrom
  - drivers/usb/dwc2/core.c:dwc2_wait_for_mode
  - drivers/usb/host/ehci-hcd.c:sitd_complete
  - drivers/usb/host/ehci-hcd.c:itd_complete
  - drivers/usb/host/ehci-hcd.c:unlink_empty_async
  - drivers/usb/host/ehci-hcd.c:end_unlink_async
  - drivers/usb/host/ehci-hcd.c:ehci_hrtimer_func
  - drivers/usb/host/ehci-hcd.c:end_free_itds
  - drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks
  - drivers/usb/host/ehci-hcd.c:ehci_handle_start_intr_unlinks
  - drivers/usb/host/ehci-hcd.c:ehci_handle_controller_death
  - drivers/usb/host/xhci.c:xhci_set_usb2_hardware_lpm
  - drivers/usb/host/xhci.c:xhci_set_usb2_hardware_lpm
  - drivers/input/input.c:input_repeat_key
  - drivers/input/input.c:input_get_timestamp
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy
  - drivers/i2c/busses/i2c-designware-master.c:txgbe_i2c_dw_xfer_quirk
  - drivers/i2c/busses/i2c-designware-master.c:txgbe_i2c_dw_xfer_quirk
  - drivers/i2c/busses/i2c-designware-master.c:txgbe_i2c_dw_xfer_quirk
  - drivers/i2c/busses/i2c-designware-master.c:txgbe_i2c_dw_xfer_quirk
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_check_stopbit
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_check_stopbit
  - drivers/power/reset/mt6323-poweroff.c:mt6323_do_pwroff
  - drivers/power/reset/mt6323-poweroff.c:mt6323_do_pwroff
  - drivers/power/supply/charger-manager.c:check_charging_duration
  - drivers/thermal/thermal_sysfs.c:cooling_device_stats_setup
  - drivers/thermal/thermal_sysfs.c:reset_store
  - drivers/thermal/thermal_sysfs.c:time_in_state_ms_show
  - drivers/thermal/thermal_sysfs.c:thermal_cooling_device_stats_update
  - drivers/watchdog/watchdog_dev.c:watchdog_set_last_hw_keepalive
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
  - drivers/watchdog/watchdog_dev.c:watchdog_start
  - drivers/watchdog/watchdog_dev.c:watchdog_worker_should_ping
  - drivers/watchdog/watchdog_dev.c:watchdog_ping
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/watchdog/watchdog_dev.c:watchdog_update_worker
  - drivers/md/dm.c:dm_split_and_process_bio
  - drivers/md/dm-stats.c:dm_stats_account_io
  - drivers/md/dm-stats.c:dm_stat_round
  - net/bpf/test_run.c:bpf_prog_test_run_sk_lookup
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run_xdp_live
  - net/bpf/test_run.c:bpf_test_timer_continue
  - net/bpf/test_run.c:bpf_test_timer_continue
  - net/bpf/test_run.c:bpf_test_timer_continue
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/ipv4/tcp.c:do_tcp_setsockopt
  - net/ipv4/tcp_input.c:tcp_synack_rtt_meas
  - net/ipv4/tcp_output.c:tcp_send_window_probe
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/mptcp/protocol.c:mptcp_rcv_space_adjust
```
**Symbols:**

```
ffffffff820d99be-ffffffff820d99e2: ktime_get.cold (STB_LOCAL)
ffffffff811f0710-ffffffff811f07c7: ktime_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
ktime_t ktime_get();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/timekeeping.c (0)
Location: kernel/time/timekeeping.c:836
Inline: False
Direct callers:
  - init/main.c:trace_initcall_finish_cb
  - init/main.c:trace_initcall_start_cb
  - kernel/fork.c:copy_process
  - kernel/cpu.c:cpuhp_wait_for_sync_state
  - kernel/cpu.c:cpuhp_wait_for_sync_state
  - kernel/async.c:async_synchronize_cookie_domain
  - kernel/async.c:async_synchronize_cookie_domain
  - kernel/async.c:async_run_entry_fn
  - kernel/async.c:async_run_entry_fn
  - kernel/sched/build_utility.c:sched_debug_header
  - kernel/sched/build_utility.c:sched_clock_tick_stable
  - kernel/sched/build_utility.c:sched_clock_init
  - kernel/sched/build_utility.c:__sched_clock_work
  - kernel/power/main.c:ksys_sync_helper
  - kernel/power/main.c:ksys_sync_helper
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image
  - kernel/power/swap.c:save_image
  - kernel/power/swap.c:save_image
  - kernel/power/wakelock.c:wakelock_lookup_add
  - kernel/power/wakelock.c:__wakelocks_gc
  - kernel/time/timer.c:usleep_range_state
  - kernel/time/timer_list.c:timer_list_start
  - kernel/time/timer_list.c:sysrq_timer_list_show
  - kernel/time/posix-timers.c:posix_get_monotonic_ktime
  - kernel/time/clockevents.c:clockevents_program_event
  - kernel/time/clockevents.c:clockevents_program_min_delta
  - kernel/time/tick-common.c:tick_setup_device
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-oneshot.c:tick_resume_oneshot
  - kernel/time/tick-sched.c:tick_setup_sched_timer
  - kernel/time/tick-sched.c:tick_nohz_highres_handler
  - kernel/time/tick-sched.c:tick_irq_enter
  - kernel/time/tick-sched.c:tick_nohz_lowres_handler
  - kernel/time/tick-sched.c:tick_nohz_idle_exit
  - kernel/time/tick-sched.c:tick_nohz_idle_restart_tick
  - kernel/time/tick-sched.c:tick_nohz_irq_exit
  - kernel/time/tick-sched.c:tick_nohz_irq_exit
  - kernel/time/tick-sched.c:tick_nohz_idle_enter
  - kernel/futex/syscalls.c:__ia32_sys_futex_time32
  - kernel/futex/syscalls.c:__x64_sys_futex_time32
  - kernel/futex/syscalls.c:__ia32_sys_futex
  - kernel/futex/syscalls.c:__x64_sys_futex
  - kernel/acct.c:fill_ac
  - kernel/taskstats.c:fill_stats_for_tgid
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/trace/trace_osnoise.c:osnoise_sleep
  - kernel/trace/blktrace.c:__blk_add_trace
  - kernel/trace/blktrace.c:trace_note
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:scan_time_advisor
  - fs/ext4/fast_commit.c:ext4_fc_commit
  - fs/ext4/fast_commit.c:ext4_fc_commit
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - ipc/sem.c:__do_semtimedop
  - crypto/jitterentropy-kcapi.c:jent_get_nstime
  - block/blk-core.c:submit_bio_noacct_nocheck
  - block/blk-flush.c:flush_end_io
  - block/blk-flush.c:flush_end_io
  - block/blk-merge.c:__bio_split_to_limits
  - block/blk-mq.c:blk_insert_cloned_request
  - block/blk-mq.c:blk_mq_submit_bio
  - block/blk-mq.c:blk_mq_start_request
  - block/blk-mq.c:blk_mq_end_request_batch
  - block/blk-mq.c:blk_mq_end_request
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - block/blk-mq.c:blk_mq_alloc_request
  - block/blk-mq.c:__blk_mq_alloc_requests
  - block/blk-mq.c:__blk_mq_alloc_requests
  - block/blk-mq.c:blk_rq_init
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-iocost.c:ioc_now
  - block/blk-wbt.c:wb_timer_fn
  - io_uring/io_uring.c:io_cqring_wait
  - io_uring/cancel.c:io_sync_cancel
  - lib/dim/net_dim.c:net_dim
  - lib/dim/rdma_dim.c:rdma_dim
  - lib/dim/rdma_dim.c:rdma_dim
  - drivers/gpio/gpiolib-cdev.c:lineinfo_changed_notify
  - drivers/gpio/gpiolib-cdev.c:lineevent_irq_handler
  - drivers/gpio/gpiolib-cdev.c:lineevent_irq_thread
  - drivers/gpio/gpiolib-cdev.c:line_event_timestamp
  - drivers/pci/quirks.c:pci_fixup_device
  - drivers/pci/quirks.c:pci_fixup_device
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_suspend_noirq
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_suspend_noirq
  - drivers/acpi/button.c:acpi_lid_input_open
  - drivers/acpi/button.c:acpi_button_resume
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
  - drivers/acpi/cppc_acpi.c:check_pcc_chan
  - drivers/acpi/cppc_acpi.c:check_pcc_chan
  - drivers/pmdomain/core.c:genpd_runtime_resume
  - drivers/pmdomain/core.c:genpd_runtime_resume
  - drivers/pmdomain/core.c:genpd_runtime_suspend
  - drivers/pmdomain/core.c:genpd_runtime_suspend
  - drivers/pmdomain/core.c:_genpd_power_off
  - drivers/pmdomain/core.c:_genpd_power_off
  - drivers/pmdomain/core.c:_genpd_power_on
  - drivers/pmdomain/core.c:_genpd_power_on
  - drivers/pmdomain/governor.c:cpu_power_down_ok
  - drivers/pmdomain/governor.c:default_power_down_ok
  - drivers/xen/events/events_base.c:handle_irq_for_port
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/char/random.c:random_pm_notification
  - drivers/iommu/intel/svm.c:intel_svm_page_response
  - drivers/connector/cn_proc.c:proc_exit_connector
  - drivers/connector/cn_proc.c:proc_coredump_connector
  - drivers/connector/cn_proc.c:proc_comm_connector
  - drivers/connector/cn_proc.c:proc_ptrace_connector
  - drivers/connector/cn_proc.c:proc_sid_connector
  - drivers/connector/cn_proc.c:proc_id_connector
  - drivers/connector/cn_proc.c:proc_exec_connector
  - drivers/connector/cn_proc.c:proc_fork_connector
  - drivers/base/dd.c:__driver_probe_device
  - drivers/base/dd.c:__driver_probe_device
  - drivers/base/power/main.c:dpm_suspend_start
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:dpm_suspend_end
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_noirq_resume_devices
  - drivers/base/power/main.c:dpm_run_callback
  - drivers/base/power/main.c:dpm_show_time
  - drivers/base/power/wakeup.c:wakeup_source_activate
  - drivers/base/power/wakeup_stats.c:prevent_suspend_time_ms_show
  - drivers/base/power/wakeup_stats.c:max_time_ms_show
  - drivers/base/power/wakeup_stats.c:total_time_ms_show
  - drivers/base/power/wakeup_stats.c:active_time_ms_show
  - drivers/misc/sram.c:atmel_securam_wait
  - drivers/misc/sram.c:atmel_securam_wait
  - drivers/dma-buf/dma-fence.c:dma_fence_describe
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
  - drivers/dma-buf/dma-fence.c:dma_fence_get_status
  - drivers/dma-buf/dma-fence.c:__dma_fence_enable_signaling
  - drivers/dma-buf/dma-fence.c:dma_fence_release
  - drivers/dma-buf/dma-fence.c:dma_fence_get_stub
  - drivers/dma-buf/dma-fence-unwrap.c:__dma_fence_unwrap_merge
  - drivers/dma-buf/dma-fence-unwrap.c:__dma_fence_unwrap_merge
  - drivers/dma-buf/sync_file.c:sync_fill_fence_info
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_signal_ioctl
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_create
  - drivers/gpu/drm/drm_vblank.c:drm_crtc_send_vblank_event
  - drivers/gpu/drm/drm_vblank.c:drm_crtc_get_last_vbltimestamp
  - drivers/gpu/drm/drm_atomic_helper.c:commit_tail
  - drivers/gpu/drm/drm_atomic_helper.c:commit_tail
  - drivers/spi/spi-mem.c:spi_mem_poll_status
  - drivers/spi/spi-mem.c:spi_mem_poll_status
  - drivers/net/phy/phy_device.c:genphy_loopback
  - drivers/net/phy/phy_device.c:genphy_loopback
  - drivers/net/virtio_net.c:virtnet_poll
  - drivers/cdrom/cdrom.c:cdrom_ioctl_media_changed
  - drivers/cdrom/cdrom.c:cdrom_select_disc
  - drivers/cdrom/cdrom.c:cdrom_select_disc
  - drivers/cdrom/cdrom.c:register_cdrom
  - drivers/usb/dwc2/core.c:dwc2_wait_for_mode
  - drivers/usb/host/ehci-hcd.c:sitd_complete
  - drivers/usb/host/ehci-hcd.c:itd_complete
  - drivers/usb/host/ehci-hcd.c:unlink_empty_async
  - drivers/usb/host/ehci-hcd.c:end_unlink_async
  - drivers/usb/host/ehci-hcd.c:ehci_hrtimer_func
  - drivers/usb/host/ehci-hcd.c:end_free_itds
  - drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks
  - drivers/usb/host/ehci-hcd.c:ehci_handle_start_intr_unlinks
  - drivers/usb/host/ehci-hcd.c:ehci_handle_controller_death
  - drivers/usb/host/xhci.c:xhci_set_usb2_hardware_lpm
  - drivers/usb/host/xhci.c:xhci_set_usb2_hardware_lpm
  - drivers/input/input.c:input_repeat_key
  - drivers/input/input.c:input_get_timestamp
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy
  - drivers/i2c/busses/i2c-designware-common.c:__i2c_dw_disable
  - drivers/i2c/busses/i2c-designware-common.c:__i2c_dw_disable
  - drivers/i2c/busses/i2c-designware-master.c:txgbe_i2c_dw_xfer_quirk
  - drivers/i2c/busses/i2c-designware-master.c:txgbe_i2c_dw_xfer_quirk
  - drivers/i2c/busses/i2c-designware-master.c:txgbe_i2c_dw_xfer_quirk
  - drivers/i2c/busses/i2c-designware-master.c:txgbe_i2c_dw_xfer_quirk
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_check_stopbit
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_check_stopbit
  - drivers/power/reset/mt6323-poweroff.c:mt6323_do_pwroff
  - drivers/power/reset/mt6323-poweroff.c:mt6323_do_pwroff
  - drivers/power/supply/charger-manager.c:check_charging_duration
  - drivers/thermal/thermal_sysfs.c:cooling_device_stats_setup
  - drivers/thermal/thermal_sysfs.c:reset_store
  - drivers/thermal/thermal_sysfs.c:time_in_state_ms_show
  - drivers/thermal/thermal_sysfs.c:thermal_cooling_device_stats_update
  - drivers/watchdog/watchdog_dev.c:watchdog_set_last_hw_keepalive
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
  - drivers/watchdog/watchdog_dev.c:watchdog_start
  - drivers/watchdog/watchdog_dev.c:watchdog_worker_should_ping
  - drivers/watchdog/watchdog_dev.c:watchdog_ping
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/watchdog/watchdog_dev.c:watchdog_update_worker
  - drivers/md/dm.c:alloc_io
  - drivers/md/dm-stats.c:dm_stats_account_io
  - drivers/md/dm-stats.c:dm_stat_round
  - drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_check_status
  - drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_check_status
  - net/core/neighbour.c:neigh_alloc
  - net/core/neighbour.c:neigh_alloc
  - net/bpf/test_run.c:bpf_prog_test_run_sk_lookup
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run_xdp_live
  - net/bpf/test_run.c:bpf_test_timer_continue
  - net/bpf/test_run.c:bpf_test_timer_continue
  - net/bpf/test_run.c:bpf_test_timer_continue
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/ipv4/tcp.c:tcp_get_info
  - net/ipv4/tcp_input.c:tcp_synack_rtt_meas
  - net/ipv4/tcp_output.c:tcp_send_window_probe
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_timewait_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_timewait_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
  - net/ipv6/tcp_ipv6.c:tcp_v6_timewait_ack
  - net/ipv6/tcp_ipv6.c:tcp_v6_timewait_ack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/mptcp/protocol.c:mptcp_rcv_space_adjust
```
**Symbols:**

```
ffffffff821b52bd-ffffffff821b52e1: ktime_get.cold (STB_LOCAL)
ffffffff81206850-ffffffff81206907: ktime_get (STB_GLOBAL)
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
ktime_t ktime_get();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffff8000101a38a0)
Location: kernel/time/timekeeping.c:747
Inline: True
Direct callers:
  - virt/kvm/kvm_main.c:kvm_vcpu_block
  - virt/kvm/kvm_main.c:kvm_vcpu_block
  - virt/kvm/kvm_main.c:kvm_vcpu_block
  - virt/kvm/kvm_main.c:kvm_vcpu_block
  - virt/kvm/arm/arch_timer.c:kvm_timer_vcpu_put
  - virt/kvm/arm/arch_timer.c:kvm_timer_vcpu_load
  - kernel/fork.c:copy_process
  - kernel/async.c:async_synchronize_cookie_domain
  - kernel/async.c:async_synchronize_cookie_domain
  - kernel/async.c:async_run_entry_fn
  - kernel/async.c:async_run_entry_fn
  - kernel/sched/debug.c:sched_debug_header
  - kernel/power/main.c:ksys_sync_helper
  - kernel/power/main.c:ksys_sync_helper
  - kernel/power/wakelock.c:wakelock_lookup_add
  - kernel/power/wakelock.c:__wakelocks_gc
  - kernel/time/timer.c:usleep_range
  - kernel/time/timer_list.c:timer_list_start
  - kernel/time/timer_list.c:sysrq_timer_list_show
  - kernel/time/clockevents.c:clockevents_program_event
  - kernel/time/clockevents.c:clockevents_program_min_delta
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-oneshot.c:tick_resume_oneshot
  - kernel/time/tick-sched.c:tick_setup_sched_timer
  - kernel/time/tick-sched.c:tick_sched_timer
  - kernel/time/tick-sched.c:tick_irq_enter
  - kernel/time/tick-sched.c:tick_nohz_handler
  - kernel/time/tick-sched.c:tick_nohz_idle_exit
  - kernel/time/tick-sched.c:tick_nohz_idle_restart_tick
  - kernel/time/tick-sched.c:tick_nohz_irq_exit
  - kernel/time/tick-sched.c:tick_nohz_idle_enter
  - kernel/time/tick-sched.c:get_cpu_iowait_time_us
  - kernel/time/tick-sched.c:get_cpu_idle_time_us
  - kernel/futex.c:__arm64_sys_futex_time32
  - kernel/futex.c:__arm64_sys_futex
  - kernel/acct.c:do_acct_process
  - kernel/delayacct.c:__delayacct_thrashing_start
  - kernel/delayacct.c:__delayacct_freepages_start
  - kernel/delayacct.c:__delayacct_blkio_start
  - kernel/delayacct.c:delayacct_end
  - kernel/taskstats.c:taskstats_user_cmd
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/trace/blktrace.c:__blk_add_trace
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - fs/ext4/extents_status.c:__es_shrink
  - fs/ext4/extents_status.c:__es_shrink
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - crypto/jitterentropy-kcapi.c:jent_get_nstime
  - block/bio.c:__bio_clone_fast
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:blk_rq_init
  - block/blk-mq.c:blk_mq_start_request
  - block/blk-mq.c:blk_mq_get_request
  - block/blk-mq.c:blk_mq_get_request
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:throtl_tg_is_idle
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-iocost.c:ioc_now
  - block/blk-iocost.c:ioc_refresh_params
  - block/blk-wbt.c:wb_timer_fn
  - lib/dim/rdma_dim.c:rdma_dim
  - lib/dim/rdma_dim.c:rdma_dim
  - drivers/pci/quirks.c:pci_do_fixups
  - drivers/pci/quirks.c:pci_do_fixups
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_startup_port
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_startup_port
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_startup_port_v2
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_startup_port_v2
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_deassert_core_reset
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_deassert_core_reset
  - drivers/acpi/button.c:acpi_lid_input_open
  - drivers/acpi/button.c:acpi_button_resume
  - drivers/acpi/button.c:acpi_lid_notify_state
  - drivers/acpi/button.c:acpi_lid_notify_state
  - drivers/acpi/button.c:acpi_lid_notify_state
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
  - drivers/acpi/cppc_acpi.c:check_pcc_chan
  - drivers/acpi/cppc_acpi.c:check_pcc_chan
  - drivers/clk/bcm/clk-bcm2835.c:bcm2835_clock_off
  - drivers/clk/bcm/clk-bcm2835.c:bcm2835_clock_off
  - drivers/clk/bcm/clk-bcm2835.c:bcm2835_pll_on
  - drivers/clk/bcm/clk-bcm2835.c:bcm2835_pll_on
  - drivers/clk/imx/clk-frac-pll.c:clk_pll_set_rate
  - drivers/clk/imx/clk-frac-pll.c:clk_pll_set_rate
  - drivers/clk/imx/clk-frac-pll.c:clk_pll_prepare
  - drivers/clk/imx/clk-frac-pll.c:clk_pll_prepare
  - drivers/clk/imx/clk-pfdv2.c:clk_pfdv2_enable
  - drivers/clk/imx/clk-pfdv2.c:clk_pfdv2_enable
  - drivers/clk/imx/clk-pllv4.c:clk_pllv4_enable
  - drivers/clk/imx/clk-pllv4.c:clk_pllv4_enable
  - drivers/soc/imx/gpcv2.c:imx_gpc_pu_pgc_sw_pxx_req
  - drivers/soc/imx/gpcv2.c:imx_gpc_pu_pgc_sw_pxx_req
  - drivers/soc/mediatek/mtk-infracfg.c:mtk_infracfg_clear_bus_protection
  - drivers/soc/mediatek/mtk-infracfg.c:mtk_infracfg_clear_bus_protection
  - drivers/soc/mediatek/mtk-infracfg.c:mtk_infracfg_set_bus_protection
  - drivers/soc/mediatek/mtk-infracfg.c:mtk_infracfg_set_bus_protection
  - drivers/soc/mediatek/mtk-scpsys.c:scpsys_power_off
  - drivers/soc/mediatek/mtk-scpsys.c:scpsys_power_off
  - drivers/soc/mediatek/mtk-scpsys.c:scpsys_power_off
  - drivers/soc/mediatek/mtk-scpsys.c:scpsys_power_off
  - drivers/soc/mediatek/mtk-scpsys.c:scpsys_power_on
  - drivers/soc/mediatek/mtk-scpsys.c:scpsys_power_on
  - drivers/soc/mediatek/mtk-scpsys.c:scpsys_power_on
  - drivers/soc/mediatek/mtk-scpsys.c:scpsys_power_on
  - drivers/soc/amlogic/meson-clk-measure.c:meson_measure_best_id
  - drivers/soc/amlogic/meson-clk-measure.c:meson_measure_best_id
  - drivers/soc/rockchip/pm_domains.c:rockchip_pd_power
  - drivers/soc/rockchip/pm_domains.c:rockchip_pd_power
  - drivers/soc/rockchip/pm_domains.c:rockchip_pmu_set_idle_request
  - drivers/soc/rockchip/pm_domains.c:rockchip_pmu_set_idle_request
  - drivers/soc/rockchip/pm_domains.c:rockchip_pmu_set_idle_request
  - drivers/soc/rockchip/pm_domains.c:rockchip_pmu_set_idle_request
  - drivers/tty/serial/mvebu-uart.c:wait_for_xmitr
  - drivers/tty/serial/mvebu-uart.c:wait_for_xmitr
  - drivers/iommu/arm-smmu.c:arm_smmu_iova_to_phys_hard
  - drivers/iommu/arm-smmu.c:arm_smmu_iova_to_phys_hard
  - drivers/iommu/arm-smmu-v3.c:arm_smmu_cmdq_issue_cmdlist
  - drivers/iommu/arm-smmu-v3.c:arm_smmu_cmdq_issue_cmdlist
  - drivers/iommu/arm-smmu-v3.c:arm_smmu_cmdq_issue_cmdlist
  - drivers/iommu/rockchip-iommu.c:rk_iommu_enable
  - drivers/iommu/rockchip-iommu.c:rk_iommu_enable
  - drivers/iommu/rockchip-iommu.c:rk_iommu_enable
  - drivers/iommu/rockchip-iommu.c:rk_iommu_enable
  - drivers/iommu/rockchip-iommu.c:rk_iommu_disable
  - drivers/iommu/rockchip-iommu.c:rk_iommu_disable
  - drivers/iommu/rockchip-iommu.c:rk_iommu_disable_stall
  - drivers/iommu/rockchip-iommu.c:rk_iommu_disable_stall
  - drivers/iommu/rockchip-iommu.c:rk_iommu_enable_stall
  - drivers/iommu/rockchip-iommu.c:rk_iommu_enable_stall
  - drivers/iommu/rockchip-iommu.c:rk_iommu_enable_stall
  - drivers/iommu/qcom_iommu.c:qcom_iommu_tlb_sync
  - drivers/iommu/qcom_iommu.c:qcom_iommu_tlb_sync
  - drivers/connector/cn_proc.c:proc_exit_connector
  - drivers/connector/cn_proc.c:proc_coredump_connector
  - drivers/connector/cn_proc.c:proc_comm_connector
  - drivers/connector/cn_proc.c:proc_ptrace_connector
  - drivers/connector/cn_proc.c:proc_sid_connector
  - drivers/connector/cn_proc.c:proc_id_connector
  - drivers/connector/cn_proc.c:proc_exec_connector
  - drivers/connector/cn_proc.c:proc_fork_connector
  - drivers/base/dd.c:driver_probe_device
  - drivers/base/dd.c:driver_probe_device
  - drivers/base/power/main.c:dpm_suspend_start
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:dpm_suspend_end
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_noirq
  - drivers/base/power/main.c:dpm_run_callback
  - drivers/base/power/main.c:dpm_show_time
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show
  - drivers/base/power/wakeup_stats.c:prevent_suspend_time_ms_show
  - drivers/base/power/wakeup_stats.c:max_time_ms_show
  - drivers/base/power/wakeup_stats.c:total_time_ms_show
  - drivers/base/power/wakeup_stats.c:active_time_ms_show
  - drivers/base/power/domain.c:total_idle_time_show
  - drivers/base/power/domain.c:active_time_show
  - drivers/base/power/domain.c:idle_states_show
  - drivers/base/power/domain.c:pm_genpd_init
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_runtime_suspend
  - drivers/base/power/domain.c:genpd_runtime_suspend
  - drivers/base/power/domain.c:genpd_update_accounting
  - drivers/misc/sram.c:atmel_securam_wait
  - drivers/misc/sram.c:atmel_securam_wait
  - drivers/mfd/lochnagar-i2c.c:lochnagar_update_config
  - drivers/mfd/lochnagar-i2c.c:lochnagar_update_config
  - drivers/dma-buf/dma-fence.c:dma_fence_signal_locked
  - drivers/spi/spi-omap2-mcspi.c:mcspi_wait_for_reg_bit
  - drivers/spi/spi-omap2-mcspi.c:mcspi_wait_for_reg_bit
  - drivers/usb/phy/phy-mxs-usb.c:mxs_phy_init
  - drivers/usb/phy/phy-mxs-usb.c:mxs_phy_init
  - drivers/usb/dwc2/core.c:dwc2_wait_for_mode
  - drivers/usb/host/ehci-hcd.c:ehci_hrtimer_func
  - drivers/usb/host/xhci.c:xhci_handshake
  - drivers/usb/host/xhci.c:xhci_handshake
  - drivers/input/input.c:input_get_timestamp
  - drivers/input/input.c:input_repeat_key
  - drivers/media/cec/cec-adap.c:cec_transmit_msg_fh
  - drivers/media/cec/cec-adap.c:cec_wait_timeout
  - drivers/media/cec/cec-adap.c:cec_data_cancel
  - drivers/media/cec/cec-adap.c:cec_data_cancel
  - drivers/media/cec/cec-adap.c:cec_post_state_event
  - drivers/media/cec/cec-adap.c:cec_queue_msg_fh
  - drivers/media/cec/cec-adap.c:cec_queue_event_fh
  - drivers/media/cec/cec-pin.c:cec_pin_timer
  - drivers/media/cec/cec-pin.c:cec_pin_update
  - drivers/power/supply/charger-manager.c:try_charger_enable
  - drivers/power/supply/charger-manager.c:try_charger_enable
  - drivers/thermal/thermal_sysfs.c:thermal_cooling_device_setup_sysfs
  - drivers/thermal/thermal_sysfs.c:reset_store
  - drivers/thermal/thermal_sysfs.c:update_time_in_state
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
  - drivers/watchdog/watchdog_dev.c:watchdog_start
  - drivers/watchdog/watchdog_dev.c:watchdog_ping_work
  - drivers/watchdog/watchdog_dev.c:watchdog_ping
  - drivers/watchdog/watchdog_dev.c:watchdog_ping
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/watchdog/watchdog_dev.c:watchdog_next_keepalive
  - drivers/md/dm-stats.c:dm_stats_account_io
  - drivers/md/dm-stats.c:dm_stats_account_io
  - drivers/md/dm-rq.c:map_request
  - drivers/firmware/arm_scmi/driver.c:scmi_do_xfer
  - drivers/firmware/arm_scmi/driver.c:scmi_do_xfer
  - drivers/firmware/arm_scmi/driver.c:scmi_xfer_done_no_timeout
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
  - net/ipv4/tcp_input.c:tcp_synack_rtt_meas
  - net/ipv4/tcp_output.c:tcp_send_window_probe
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/syncookies.c:cookie_init_timestamp
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
**Symbols:**

```
ffff8000101a38a0-ffff8000101a393c: ktime_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
ktime_t ktime_get();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (c03ed760)
Location: kernel/time/timekeeping.c:747
Inline: True
Direct callers:
  - arch/arm/mach-meson/platsmp.c:meson8b_smp_boot_secondary
  - arch/arm/mach-meson/platsmp.c:meson8b_smp_boot_secondary
  - kernel/fork.c:copy_process
  - kernel/async.c:async_synchronize_cookie_domain
  - kernel/async.c:async_synchronize_cookie_domain
  - kernel/async.c:async_run_entry_fn
  - kernel/async.c:async_run_entry_fn
  - kernel/sched/debug.c:sched_debug_header
  - kernel/power/main.c:ksys_sync_helper
  - kernel/power/main.c:ksys_sync_helper
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/swap.c:swsusp_read
  - kernel/power/swap.c:swsusp_read
  - kernel/power/swap.c:swsusp_read
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:swsusp_write
  - kernel/power/swap.c:swsusp_write
  - kernel/power/swap.c:swsusp_write
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/wakelock.c:wakelock_lookup_add
  - kernel/power/wakelock.c:__wakelocks_gc
  - kernel/time/timer.c:usleep_range
  - kernel/time/timer_list.c:timer_list_start
  - kernel/time/timer_list.c:sysrq_timer_list_show
  - kernel/time/clockevents.c:clockevents_program_event
  - kernel/time/clockevents.c:clockevents_program_min_delta
  - kernel/time/tick-common.c:tick_setup_device
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-oneshot.c:tick_resume_oneshot
  - kernel/time/tick-sched.c:tick_setup_sched_timer
  - kernel/time/tick-sched.c:tick_sched_timer
  - kernel/time/tick-sched.c:tick_irq_enter
  - kernel/time/tick-sched.c:tick_nohz_handler
  - kernel/time/tick-sched.c:tick_nohz_idle_exit
  - kernel/time/tick-sched.c:tick_nohz_idle_restart_tick
  - kernel/time/tick-sched.c:tick_nohz_irq_exit
  - kernel/time/tick-sched.c:tick_nohz_idle_enter
  - kernel/time/tick-sched.c:get_cpu_iowait_time_us
  - kernel/time/tick-sched.c:get_cpu_idle_time_us
  - kernel/futex.c:__se_sys_futex_time32
  - kernel/futex.c:__se_sys_futex
  - kernel/acct.c:fill_ac
  - kernel/delayacct.c:__delayacct_thrashing_start
  - kernel/delayacct.c:__delayacct_freepages_start
  - kernel/delayacct.c:__delayacct_blkio_start
  - kernel/delayacct.c:delayacct_end
  - kernel/taskstats.c:taskstats_user_cmd
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/trace/blktrace.c:__blk_add_trace
  - kernel/trace/blktrace.c:trace_note
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - fs/ext4/extents_status.c:__es_shrink
  - fs/ext4/extents_status.c:__es_shrink
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - crypto/jitterentropy-kcapi.c:jent_get_nstime
  - block/bio.c:__bio_clone_fast
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:blk_rq_init
  - block/blk-mq.c:blk_mq_start_request
  - block/blk-mq.c:blk_mq_get_request
  - block/blk-mq.c:blk_mq_get_request
  - block/bounce.c:__blk_queue_bounce
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:throtl_tg_is_idle
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-iocost.c:ioc_now
  - block/blk-iocost.c:ioc_refresh_params
  - block/blk-wbt.c:wb_timer_fn
  - lib/dim/rdma_dim.c:rdma_dim
  - lib/dim/rdma_dim.c:rdma_dim
  - drivers/bus/ti-sysc.c:sysc_init_module
  - drivers/bus/ti-sysc.c:sysc_init_module
  - drivers/bus/ti-sysc.c:sysc_init_module
  - drivers/bus/ti-sysc.c:sysc_init_module
  - drivers/bus/ti-sysc.c:sysc_reset_done_quirk_wdt
  - drivers/bus/ti-sysc.c:sysc_reset_done_quirk_wdt
  - drivers/bus/ti-sysc.c:sysc_reset_done_quirk_wdt
  - drivers/bus/ti-sysc.c:sysc_reset_done_quirk_wdt
  - drivers/phy/samsung/phy-exynos-pcie.c:exynos5440_pcie_phy_power_off
  - drivers/phy/samsung/phy-exynos-pcie.c:exynos5440_pcie_phy_power_off
  - drivers/pci/quirks.c:pci_do_fixups
  - drivers/pci/quirks.c:pci_do_fixups
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_pm_resume
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_pm_resume
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_pm_resume
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_pm_resume
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_pm_suspend
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_pm_suspend
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_startup_port
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_startup_port
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_startup_port_v2
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_startup_port_v2
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_check_cfg_cpld
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_check_cfg_cpld
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_deassert_core_reset
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_deassert_core_reset
  - drivers/pci/controller/dwc/pcie-uniphier.c:uniphier_pcie_probe
  - drivers/pci/controller/dwc/pcie-uniphier.c:uniphier_pcie_probe
  - drivers/clk/clk-milbeaut.c:m10v_clk_divider_set_rate
  - drivers/clk/clk-milbeaut.c:m10v_clk_divider_set_rate
  - drivers/clk/imx/clk-frac-pll.c:clk_pll_set_rate
  - drivers/clk/imx/clk-frac-pll.c:clk_pll_set_rate
  - drivers/clk/imx/clk-frac-pll.c:clk_pll_prepare
  - drivers/clk/imx/clk-frac-pll.c:clk_pll_prepare
  - drivers/clk/imx/clk-pfdv2.c:clk_pfdv2_enable
  - drivers/clk/imx/clk-pfdv2.c:clk_pfdv2_enable
  - drivers/clk/imx/clk-pllv4.c:clk_pllv4_enable
  - drivers/clk/imx/clk-pllv4.c:clk_pllv4_enable
  - drivers/clk/imx/clk-pll14xx.c:clk_pll14xx_wait_lock
  - drivers/clk/imx/clk-pll14xx.c:clk_pll14xx_wait_lock
  - drivers/clk/samsung/clk-pll.c:samsung_pll46xx_set_rate
  - drivers/clk/samsung/clk-pll.c:samsung_pll46xx_set_rate
  - drivers/clk/samsung/clk-pll.c:samsung_pll45xx_set_rate
  - drivers/clk/samsung/clk-pll.c:samsung_pll45xx_set_rate
  - drivers/soc/imx/gpcv2.c:imx_gpc_pu_pgc_sw_pxx_req
  - drivers/soc/imx/gpcv2.c:imx_gpc_pu_pgc_sw_pxx_req
  - drivers/soc/mediatek/mtk-infracfg.c:mtk_infracfg_clear_bus_protection
  - drivers/soc/mediatek/mtk-infracfg.c:mtk_infracfg_clear_bus_protection
  - drivers/soc/mediatek/mtk-infracfg.c:mtk_infracfg_set_bus_protection
  - drivers/soc/mediatek/mtk-infracfg.c:mtk_infracfg_set_bus_protection
  - drivers/soc/mediatek/mtk-scpsys.c:scpsys_power_off
  - drivers/soc/mediatek/mtk-scpsys.c:scpsys_power_off
  - drivers/soc/mediatek/mtk-scpsys.c:scpsys_power_off
  - drivers/soc/mediatek/mtk-scpsys.c:scpsys_power_off
  - drivers/soc/mediatek/mtk-scpsys.c:scpsys_power_on
  - drivers/soc/mediatek/mtk-scpsys.c:scpsys_power_on
  - drivers/soc/mediatek/mtk-scpsys.c:scpsys_power_on
  - drivers/soc/mediatek/mtk-scpsys.c:scpsys_power_on
  - drivers/soc/amlogic/meson-clk-measure.c:meson_measure_id
  - drivers/soc/amlogic/meson-clk-measure.c:meson_measure_id
  - drivers/soc/rockchip/pm_domains.c:rockchip_pd_power
  - drivers/soc/rockchip/pm_domains.c:rockchip_pd_power
  - drivers/soc/rockchip/pm_domains.c:rockchip_pmu_set_idle_request
  - drivers/soc/rockchip/pm_domains.c:rockchip_pmu_set_idle_request
  - drivers/soc/rockchip/pm_domains.c:rockchip_pmu_set_idle_request
  - drivers/soc/rockchip/pm_domains.c:rockchip_pmu_set_idle_request
  - drivers/soc/tegra/pmc.c:tegra_powergate_set
  - drivers/soc/tegra/pmc.c:tegra_powergate_set
  - drivers/tty/serial/mvebu-uart.c:wait_for_xmitr
  - drivers/tty/serial/mvebu-uart.c:wait_for_xmitr
  - drivers/iommu/rockchip-iommu.c:rk_iommu_enable
  - drivers/iommu/rockchip-iommu.c:rk_iommu_enable
  - drivers/iommu/rockchip-iommu.c:rk_iommu_enable
  - drivers/iommu/rockchip-iommu.c:rk_iommu_enable
  - drivers/iommu/rockchip-iommu.c:rk_iommu_disable
  - drivers/iommu/rockchip-iommu.c:rk_iommu_disable
  - drivers/iommu/qcom_iommu.c:qcom_iommu_tlb_sync
  - drivers/iommu/qcom_iommu.c:qcom_iommu_tlb_sync
  - drivers/connector/cn_proc.c:proc_exit_connector
  - drivers/connector/cn_proc.c:proc_coredump_connector
  - drivers/connector/cn_proc.c:proc_comm_connector
  - drivers/connector/cn_proc.c:proc_ptrace_connector
  - drivers/connector/cn_proc.c:proc_sid_connector
  - drivers/connector/cn_proc.c:proc_id_connector
  - drivers/connector/cn_proc.c:proc_exec_connector
  - drivers/connector/cn_proc.c:proc_fork_connector
  - drivers/base/dd.c:driver_probe_device
  - drivers/base/dd.c:driver_probe_device
  - drivers/base/power/main.c:dpm_suspend_start
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:dpm_suspend_end
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_noirq
  - drivers/base/power/main.c:dpm_run_callback
  - drivers/base/power/main.c:dpm_show_time
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show
  - drivers/base/power/wakeup.c:wakeup_source_report_event
  - drivers/base/power/wakeup_stats.c:prevent_suspend_time_ms_show
  - drivers/base/power/wakeup_stats.c:max_time_ms_show
  - drivers/base/power/wakeup_stats.c:total_time_ms_show
  - drivers/base/power/wakeup_stats.c:active_time_ms_show
  - drivers/base/power/domain.c:total_idle_time_show
  - drivers/base/power/domain.c:active_time_show
  - drivers/base/power/domain.c:idle_states_show
  - drivers/base/power/domain.c:pm_genpd_init
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_runtime_suspend
  - drivers/base/power/domain.c:genpd_runtime_suspend
  - drivers/base/power/domain.c:genpd_update_accounting
  - drivers/misc/sram.c:atmel_securam_wait
  - drivers/misc/sram.c:atmel_securam_wait
  - drivers/mfd/lochnagar-i2c.c:lochnagar_update_config
  - drivers/mfd/lochnagar-i2c.c:lochnagar_update_config
  - drivers/mfd/arizona-core.c:arizona_poll_reg
  - drivers/mfd/arizona-core.c:arizona_poll_reg
  - drivers/dma-buf/dma-fence.c:dma_fence_signal_locked
  - drivers/spi/spi-omap2-mcspi.c:mcspi_wait_for_reg_bit
  - drivers/spi/spi-omap2-mcspi.c:mcspi_wait_for_reg_bit
  - drivers/net/ethernet/ti/davinci_mdio.c:davinci_mdio_runtime_suspend
  - drivers/net/ethernet/ti/davinci_mdio.c:davinci_mdio_runtime_suspend
  - drivers/usb/phy/phy-mxs-usb.c:mxs_phy_init
  - drivers/usb/phy/phy-mxs-usb.c:mxs_phy_init
  - drivers/usb/dwc2/core.c:dwc2_wait_for_mode
  - drivers/usb/host/ehci-hcd.c:ehci_hrtimer_func
  - drivers/usb/host/xhci.c:xhci_handshake
  - drivers/usb/host/xhci.c:xhci_handshake
  - drivers/input/input.c:input_get_timestamp
  - drivers/input/input.c:input_repeat_key
  - drivers/i2c/busses/i2c-s3c2410.c:s3c24xx_i2c_wait_idle
  - drivers/i2c/busses/i2c-s3c2410.c:s3c24xx_i2c_wait_idle
  - drivers/media/cec/cec-adap.c:cec_transmit_msg_fh
  - drivers/media/cec/cec-adap.c:cec_wait_timeout
  - drivers/media/cec/cec-adap.c:cec_data_cancel
  - drivers/media/cec/cec-adap.c:cec_data_cancel
  - drivers/media/cec/cec-adap.c:cec_post_state_event
  - drivers/media/cec/cec-adap.c:cec_queue_msg_fh
  - drivers/media/cec/cec-adap.c:cec_queue_event_fh
  - drivers/power/supply/charger-manager.c:try_charger_enable
  - drivers/power/supply/charger-manager.c:try_charger_enable
  - drivers/thermal/thermal_sysfs.c:thermal_cooling_device_setup_sysfs
  - drivers/thermal/thermal_sysfs.c:reset_store
  - drivers/thermal/thermal_sysfs.c:update_time_in_state
  - drivers/thermal/armada_thermal.c:armada_wait_sensor_validity
  - drivers/thermal/armada_thermal.c:armada_wait_sensor_validity
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
  - drivers/watchdog/watchdog_dev.c:watchdog_start
  - drivers/watchdog/watchdog_dev.c:watchdog_ping_work
  - drivers/watchdog/watchdog_dev.c:watchdog_ping
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/watchdog/watchdog_dev.c:watchdog_next_keepalive
  - drivers/md/dm-stats.c:dm_stats_account_io
  - drivers/md/dm-stats.c:dm_stats_account_io
  - drivers/md/dm-stats.c:dm_stat_round
  - drivers/md/dm-rq.c:map_request
  - drivers/mmc/host/sdhci.c:sdhci_enable_clk
  - drivers/mmc/host/sdhci.c:sdhci_enable_clk
  - drivers/mmc/host/sdhci.c:sdhci_enable_clk
  - drivers/mmc/host/sdhci.c:sdhci_enable_clk
  - drivers/mmc/host/sdhci.c:sdhci_reset
  - drivers/mmc/host/sdhci.c:sdhci_reset
  - drivers/mmc/host/cqhci.c:cqhci_off
  - drivers/mmc/host/cqhci.c:cqhci_off
  - drivers/firmware/arm_scmi/driver.c:scmi_do_xfer
  - drivers/firmware/arm_scmi/driver.c:scmi_do_xfer
  - drivers/firmware/arm_scmi/driver.c:scmi_xfer_done_no_timeout
  - drivers/firmware/tegra/bpmp.c:tegra_bpmp_probe
  - drivers/firmware/tegra/bpmp.c:tegra_bpmp_probe
  - drivers/firmware/tegra/bpmp.c:tegra_bpmp_transfer_atomic
  - drivers/firmware/tegra/bpmp.c:tegra_bpmp_transfer_atomic
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
  - net/ipv4/tcp.c:tcp_time_stamp_raw
  - net/ipv4/tcp_input.c:tcp_synack_rtt_meas
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_mstamp_refresh
  - net/ipv4/tcp_ipv4.c:tcp_v4_timewait_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/syncookies.c:cookie_init_timestamp
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
  - net/ipv6/tcp_ipv6.c:tcp_v6_timewait_ack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
**Symbols:**

```
c03ed760-c03ed894: ktime_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
ktime_t ktime_get();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (c000000000204600)
Location: kernel/time/timekeeping.c:747
Inline: False
Direct callers:
  - arch/powerpc/platforms/pseries/lpar.c:pseries_lpar_resize_hpt
  - arch/powerpc/platforms/pseries/lpar.c:pseries_lpar_resize_hpt
  - arch/powerpc/platforms/pseries/lpar.c:pseries_lpar_resize_hpt
  - kernel/fork.c:copy_process
  - kernel/async.c:async_synchronize_cookie_domain
  - kernel/async.c:async_synchronize_cookie_domain
  - kernel/async.c:async_run_entry_fn
  - kernel/async.c:async_run_entry_fn
  - kernel/sched/debug.c:sched_debug_header
  - kernel/power/main.c:ksys_sync_helper
  - kernel/power/main.c:ksys_sync_helper
  - kernel/power/wakelock.c:wakelock_lookup_add
  - kernel/power/wakelock.c:__wakelocks_gc
  - kernel/time/timer.c:usleep_range
  - kernel/time/timer_list.c:timer_list_start
  - kernel/time/timer_list.c:sysrq_timer_list_show
  - kernel/time/clockevents.c:clockevents_program_event
  - kernel/time/clockevents.c:clockevents_program_min_delta
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-oneshot.c:tick_resume_oneshot
  - kernel/time/tick-sched.c:tick_setup_sched_timer
  - kernel/time/tick-sched.c:tick_sched_timer
  - kernel/time/tick-sched.c:tick_irq_enter
  - kernel/time/tick-sched.c:tick_nohz_handler
  - kernel/time/tick-sched.c:tick_nohz_idle_exit
  - kernel/time/tick-sched.c:tick_nohz_idle_restart_tick
  - kernel/time/tick-sched.c:tick_nohz_irq_exit
  - kernel/time/tick-sched.c:tick_nohz_idle_enter
  - kernel/time/tick-sched.c:get_cpu_iowait_time_us
  - kernel/time/tick-sched.c:get_cpu_idle_time_us
  - kernel/futex.c:__se_sys_futex_time32
  - kernel/futex.c:__se_sys_futex
  - kernel/acct.c:do_acct_process
  - kernel/delayacct.c:__delayacct_thrashing_start
  - kernel/delayacct.c:__delayacct_freepages_start
  - kernel/delayacct.c:__delayacct_blkio_start
  - kernel/delayacct.c:delayacct_end
  - kernel/taskstats.c:taskstats_user_cmd
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/trace/blktrace.c:__blk_add_trace
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - fs/ext4/extents_status.c:__es_shrink
  - fs/ext4/extents_status.c:__es_shrink
  - fs/ext4/extents_status.c:__es_shrink
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - crypto/jitterentropy-kcapi.c:jent_get_nstime
  - block/bio.c:__bio_clone_fast
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:blk_rq_init
  - block/blk-mq.c:blk_mq_start_request
  - block/blk-mq.c:blk_mq_get_request
  - block/blk-mq.c:blk_mq_get_request
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:throtl_tg_is_idle
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-iocost.c:ioc_now
  - block/blk-iocost.c:ioc_refresh_params
  - block/blk-wbt.c:wb_timer_fn
  - lib/dim/rdma_dim.c:rdma_dim
  - lib/dim/rdma_dim.c:rdma_dim
  - drivers/pci/quirks.c:pci_do_fixups
  - drivers/pci/quirks.c:pci_do_fixups
  - drivers/connector/cn_proc.c:proc_exit_connector
  - drivers/connector/cn_proc.c:proc_coredump_connector
  - drivers/connector/cn_proc.c:proc_comm_connector
  - drivers/connector/cn_proc.c:proc_ptrace_connector
  - drivers/connector/cn_proc.c:proc_sid_connector
  - drivers/connector/cn_proc.c:proc_id_connector
  - drivers/connector/cn_proc.c:proc_exec_connector
  - drivers/connector/cn_proc.c:proc_fork_connector
  - drivers/base/dd.c:driver_probe_device
  - drivers/base/dd.c:driver_probe_device
  - drivers/base/power/main.c:dpm_suspend_start
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:dpm_suspend_end
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_noirq
  - drivers/base/power/main.c:dpm_run_callback
  - drivers/base/power/main.c:dpm_show_time
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show
  - drivers/base/power/wakeup_stats.c:prevent_suspend_time_ms_show
  - drivers/base/power/wakeup_stats.c:max_time_ms_show
  - drivers/base/power/wakeup_stats.c:total_time_ms_show
  - drivers/base/power/wakeup_stats.c:active_time_ms_show
  - drivers/base/power/domain.c:total_idle_time_show
  - drivers/base/power/domain.c:active_time_show
  - drivers/base/power/domain.c:idle_states_show
  - drivers/base/power/domain.c:pm_genpd_init
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_runtime_suspend
  - drivers/base/power/domain.c:genpd_runtime_suspend
  - drivers/base/power/domain.c:genpd_update_accounting
  - drivers/misc/sram.c:atmel_securam_wait
  - drivers/misc/sram.c:atmel_securam_wait
  - drivers/mfd/lochnagar-i2c.c:lochnagar_update_config
  - drivers/mfd/lochnagar-i2c.c:lochnagar_update_config
  - drivers/mfd/arizona-core.c:arizona_poll_reg
  - drivers/mfd/arizona-core.c:arizona_poll_reg
  - drivers/dma-buf/dma-fence.c:dma_fence_signal_locked
  - drivers/usb/dwc2/core.c:dwc2_wait_for_mode
  - drivers/usb/host/ehci-hcd.c:ehci_hrtimer_func
  - drivers/usb/host/xhci.c:xhci_handshake
  - drivers/usb/host/xhci.c:xhci_handshake
  - drivers/input/input.c:input_get_timestamp
  - drivers/input/input.c:input_repeat_key
  - drivers/media/cec/cec-adap.c:cec_transmit_msg_fh
  - drivers/media/cec/cec-adap.c:cec_wait_timeout
  - drivers/media/cec/cec-adap.c:cec_data_cancel
  - drivers/media/cec/cec-adap.c:cec_data_cancel
  - drivers/media/cec/cec-adap.c:cec_post_state_event
  - drivers/media/cec/cec-adap.c:cec_queue_msg_fh
  - drivers/media/cec/cec-adap.c:cec_queue_event_fh
  - drivers/power/supply/charger-manager.c:try_charger_enable
  - drivers/power/supply/charger-manager.c:try_charger_enable
  - drivers/thermal/thermal_sysfs.c:thermal_cooling_device_setup_sysfs
  - drivers/thermal/thermal_sysfs.c:reset_store
  - drivers/thermal/thermal_sysfs.c:update_time_in_state
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
  - drivers/watchdog/watchdog_dev.c:watchdog_start
  - drivers/watchdog/watchdog_dev.c:watchdog_ping_work
  - drivers/watchdog/watchdog_dev.c:watchdog_ping
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/watchdog/watchdog_dev.c:watchdog_next_keepalive
  - drivers/md/dm-stats.c:dm_stats_account_io
  - drivers/md/dm-stats.c:dm_stats_account_io
  - drivers/md/dm-rq.c:map_request
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
  - net/ipv4/tcp_input.c:tcp_synack_rtt_meas
  - net/ipv4/tcp_output.c:tcp_send_window_probe
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/syncookies.c:cookie_init_timestamp
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
**Symbols:**

```
c000000000204600-c0000000002046dc: ktime_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
ktime_t ktime_get();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffe000130444)
Location: kernel/time/timekeeping.c:747
Inline: True
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/async.c:async_synchronize_cookie_domain
  - kernel/async.c:async_synchronize_cookie_domain
  - kernel/async.c:async_run_entry_fn
  - kernel/async.c:async_run_entry_fn
  - kernel/sched/debug.c:sched_debug_header
  - kernel/time/timer.c:usleep_range
  - kernel/time/timer_list.c:timer_list_start
  - kernel/time/timer_list.c:sysrq_timer_list_show
  - kernel/time/clockevents.c:clockevents_program_event
  - kernel/time/clockevents.c:clockevents_program_min_delta
  - kernel/time/tick-oneshot.c:tick_resume_oneshot
  - kernel/time/tick-sched.c:tick_setup_sched_timer
  - kernel/time/tick-sched.c:tick_sched_timer
  - kernel/time/tick-sched.c:tick_irq_enter
  - kernel/time/tick-sched.c:tick_nohz_handler
  - kernel/time/tick-sched.c:tick_nohz_idle_exit
  - kernel/time/tick-sched.c:tick_nohz_idle_restart_tick
  - kernel/time/tick-sched.c:tick_nohz_irq_exit
  - kernel/time/tick-sched.c:tick_nohz_idle_enter
  - kernel/time/tick-sched.c:get_cpu_iowait_time_us
  - kernel/time/tick-sched.c:get_cpu_idle_time_us
  - kernel/futex.c:__se_sys_futex
  - kernel/acct.c:do_acct_process
  - kernel/delayacct.c:__delayacct_thrashing_start
  - kernel/delayacct.c:__delayacct_freepages_start
  - kernel/delayacct.c:__delayacct_blkio_start
  - kernel/delayacct.c:delayacct_end
  - kernel/taskstats.c:taskstats_user_cmd
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/trace/blktrace.c:__blk_add_trace
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - fs/ext4/extents_status.c:__es_shrink
  - fs/ext4/extents_status.c:__es_shrink
  - fs/ext4/extents_status.c:__es_shrink
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - crypto/jitterentropy-kcapi.c:jent_get_nstime
  - block/bio.c:__bio_clone_fast
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:blk_rq_init
  - block/blk-mq.c:blk_mq_start_request
  - block/blk-mq.c:blk_mq_get_request
  - block/blk-mq.c:blk_mq_get_request
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:throtl_tg_is_idle
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-iocost.c:ioc_now
  - block/blk-iocost.c:ioc_refresh_params
  - block/blk-wbt.c:wb_timer_fn
  - lib/dim/rdma_dim.c:rdma_dim
  - lib/dim/rdma_dim.c:rdma_dim
  - drivers/pci/quirks.c:pci_do_fixups
  - drivers/pci/quirks.c:pci_do_fixups
  - drivers/connector/cn_proc.c:proc_exit_connector
  - drivers/connector/cn_proc.c:proc_coredump_connector
  - drivers/connector/cn_proc.c:proc_comm_connector
  - drivers/connector/cn_proc.c:proc_ptrace_connector
  - drivers/connector/cn_proc.c:proc_sid_connector
  - drivers/connector/cn_proc.c:proc_id_connector
  - drivers/connector/cn_proc.c:proc_exec_connector
  - drivers/connector/cn_proc.c:proc_fork_connector
  - drivers/base/dd.c:driver_probe_device
  - drivers/base/dd.c:driver_probe_device
  - drivers/base/power/domain.c:total_idle_time_show
  - drivers/base/power/domain.c:active_time_show
  - drivers/base/power/domain.c:idle_states_show
  - drivers/base/power/domain.c:pm_genpd_init
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_runtime_suspend
  - drivers/base/power/domain.c:genpd_runtime_suspend
  - drivers/base/power/domain.c:genpd_update_accounting
  - drivers/misc/sram.c:atmel_securam_wait
  - drivers/misc/sram.c:atmel_securam_wait
  - drivers/mfd/lochnagar-i2c.c:lochnagar_update_config
  - drivers/mfd/lochnagar-i2c.c:lochnagar_update_config
  - drivers/mfd/arizona-core.c:arizona_poll_reg
  - drivers/mfd/arizona-core.c:arizona_poll_reg
  - drivers/dma-buf/dma-fence.c:dma_fence_signal_locked
  - drivers/usb/dwc2/core.c:dwc2_wait_for_mode
  - drivers/usb/host/ehci-hcd.c:ehci_hrtimer_func
  - drivers/usb/host/xhci.c:xhci_handshake
  - drivers/usb/host/xhci.c:xhci_handshake
  - drivers/input/input.c:input_get_timestamp
  - drivers/input/input.c:input_repeat_key
  - drivers/media/cec/cec-adap.c:cec_transmit_msg_fh
  - drivers/media/cec/cec-adap.c:cec_wait_timeout
  - drivers/media/cec/cec-adap.c:cec_data_cancel
  - drivers/media/cec/cec-adap.c:cec_data_cancel
  - drivers/media/cec/cec-adap.c:cec_post_state_event
  - drivers/media/cec/cec-adap.c:cec_queue_msg_fh
  - drivers/media/cec/cec-adap.c:cec_queue_event_fh
  - drivers/power/supply/charger-manager.c:try_charger_enable
  - drivers/power/supply/charger-manager.c:try_charger_enable
  - drivers/thermal/thermal_sysfs.c:thermal_cooling_device_setup_sysfs
  - drivers/thermal/thermal_sysfs.c:reset_store
  - drivers/thermal/thermal_sysfs.c:update_time_in_state
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
  - drivers/watchdog/watchdog_dev.c:watchdog_start
  - drivers/watchdog/watchdog_dev.c:watchdog_ping_work
  - drivers/watchdog/watchdog_dev.c:watchdog_ping
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/watchdog/watchdog_dev.c:watchdog_next_keepalive
  - drivers/md/dm-stats.c:dm_stats_account_io
  - drivers/md/dm-stats.c:dm_stats_account_io
  - drivers/md/dm-rq.c:map_request
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
  - net/ipv4/tcp_input.c:tcp_synack_rtt_meas
  - net/ipv4/tcp_output.c:tcp_send_window_probe
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/syncookies.c:cookie_init_timestamp
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
**Symbols:**

```
ffffffe000130444-ffffffe0001304cc: ktime_get (STB_GLOBAL)
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
ktime_t ktime_get();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81133010)
Location: kernel/time/timekeeping.c:747
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_get_on_cpu
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_prepare_all
  - arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_get_khz
  - arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_snapshot_khz
  - kernel/fork.c:copy_process
  - kernel/async.c:async_synchronize_cookie_domain
  - kernel/async.c:async_synchronize_cookie_domain
  - kernel/async.c:async_run_entry_fn
  - kernel/async.c:async_run_entry_fn
  - kernel/sched/clock.c:__sched_clock_gtod_offset
  - kernel/sched/clock.c:__sched_clock_work
  - kernel/sched/debug.c:sched_debug_header
  - kernel/power/main.c:ksys_sync_helper
  - kernel/power/main.c:ksys_sync_helper
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image
  - kernel/power/swap.c:save_image
  - kernel/power/swap.c:save_image
  - kernel/power/wakelock.c:wakelock_lookup_add
  - kernel/power/wakelock.c:__wakelocks_gc
  - kernel/time/timer.c:usleep_range
  - kernel/time/timer_list.c:timer_list_start
  - kernel/time/timer_list.c:sysrq_timer_list_show
  - kernel/time/clockevents.c:clockevents_program_event
  - kernel/time/clockevents.c:clockevents_program_min_delta
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-oneshot.c:tick_resume_oneshot
  - kernel/time/tick-sched.c:tick_setup_sched_timer
  - kernel/time/tick-sched.c:tick_sched_timer
  - kernel/time/tick-sched.c:tick_irq_enter
  - kernel/time/tick-sched.c:tick_nohz_handler
  - kernel/time/tick-sched.c:tick_nohz_idle_exit
  - kernel/time/tick-sched.c:tick_nohz_idle_restart_tick
  - kernel/time/tick-sched.c:tick_nohz_irq_exit
  - kernel/time/tick-sched.c:tick_nohz_idle_enter
  - kernel/time/tick-sched.c:get_cpu_iowait_time_us
  - kernel/time/tick-sched.c:get_cpu_idle_time_us
  - kernel/futex.c:__ia32_sys_futex_time32
  - kernel/futex.c:__x64_sys_futex_time32
  - kernel/futex.c:__ia32_sys_futex
  - kernel/futex.c:__x64_sys_futex
  - kernel/acct.c:do_acct_process
  - kernel/delayacct.c:__delayacct_thrashing_start
  - kernel/delayacct.c:__delayacct_freepages_start
  - kernel/delayacct.c:__delayacct_blkio_start
  - kernel/delayacct.c:delayacct_end
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/trace/blktrace.c:__blk_add_trace
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - fs/ext4/extents_status.c:__es_shrink
  - fs/ext4/extents_status.c:__es_shrink
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - crypto/jitterentropy-kcapi.c:jent_get_nstime
  - block/bio.c:__bio_clone_fast
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:blk_rq_init
  - block/blk-mq.c:blk_mq_start_request
  - block/blk-mq.c:blk_mq_get_request
  - block/blk-mq.c:blk_mq_get_request
  - block/bounce.c:__blk_queue_bounce
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:throtl_tg_is_idle
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-iocost.c:ioc_now
  - block/blk-iocost.c:ioc_refresh_params
  - block/blk-wbt.c:wb_timer_fn
  - lib/dim/rdma_dim.c:rdma_dim
  - lib/dim/rdma_dim.c:rdma_dim
  - drivers/pci/quirks.c:pci_do_fixups
  - drivers/pci/quirks.c:pci_do_fixups
  - drivers/acpi/button.c:acpi_lid_input_open
  - drivers/acpi/button.c:acpi_button_resume
  - drivers/acpi/button.c:acpi_lid_notify_state
  - drivers/acpi/button.c:acpi_lid_notify_state
  - drivers/acpi/button.c:acpi_lid_notify_state
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
  - drivers/acpi/cppc_acpi.c:check_pcc_chan
  - drivers/acpi/cppc_acpi.c:check_pcc_chan
  - drivers/connector/cn_proc.c:proc_exit_connector
  - drivers/connector/cn_proc.c:proc_coredump_connector
  - drivers/connector/cn_proc.c:proc_comm_connector
  - drivers/connector/cn_proc.c:proc_ptrace_connector
  - drivers/connector/cn_proc.c:proc_sid_connector
  - drivers/connector/cn_proc.c:proc_id_connector
  - drivers/connector/cn_proc.c:proc_exec_connector
  - drivers/connector/cn_proc.c:proc_fork_connector
  - drivers/base/dd.c:driver_probe_device
  - drivers/base/dd.c:driver_probe_device
  - drivers/base/power/main.c:dpm_suspend_start
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:dpm_suspend_end
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_noirq
  - drivers/base/power/main.c:dpm_run_callback
  - drivers/base/power/main.c:dpm_show_time
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show
  - drivers/base/power/wakeup_stats.c:prevent_suspend_time_ms_show
  - drivers/base/power/wakeup_stats.c:max_time_ms_show
  - drivers/base/power/wakeup_stats.c:total_time_ms_show
  - drivers/base/power/wakeup_stats.c:active_time_ms_show
  - drivers/base/power/domain.c:total_idle_time_show
  - drivers/base/power/domain.c:active_time_show
  - drivers/base/power/domain.c:idle_states_show
  - drivers/base/power/domain.c:pm_genpd_init
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_runtime_suspend
  - drivers/base/power/domain.c:genpd_runtime_suspend
  - drivers/base/power/domain.c:_genpd_power_off
  - drivers/base/power/domain.c:_genpd_power_off
  - drivers/base/power/domain.c:_genpd_power_on
  - drivers/base/power/domain.c:_genpd_power_on
  - drivers/base/power/domain.c:genpd_update_accounting
  - drivers/misc/sram.c:atmel_securam_wait
  - drivers/misc/sram.c:atmel_securam_wait
  - drivers/dma-buf/dma-fence.c:dma_fence_signal_locked
  - drivers/usb/dwc2/core.c:dwc2_wait_for_mode
  - drivers/usb/host/ehci-hcd.c:ehci_hrtimer_func
  - drivers/usb/host/xhci.c:xhci_handshake
  - drivers/usb/host/xhci.c:xhci_handshake
  - drivers/input/input.c:input_get_timestamp
  - drivers/input/input.c:input_repeat_key
  - drivers/media/cec/cec-adap.c:cec_transmit_msg_fh
  - drivers/media/cec/cec-adap.c:cec_wait_timeout
  - drivers/media/cec/cec-adap.c:cec_data_cancel
  - drivers/media/cec/cec-adap.c:cec_data_cancel
  - drivers/media/cec/cec-adap.c:cec_post_state_event
  - drivers/media/cec/cec-adap.c:cec_queue_msg_fh
  - drivers/media/cec/cec-adap.c:cec_queue_event_fh
  - drivers/thermal/thermal_sysfs.c:thermal_cooling_device_setup_sysfs
  - drivers/thermal/thermal_sysfs.c:reset_store
  - drivers/thermal/thermal_sysfs.c:update_time_in_state
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
  - drivers/watchdog/watchdog_dev.c:watchdog_start
  - drivers/watchdog/watchdog_dev.c:watchdog_ping_work
  - drivers/watchdog/watchdog_dev.c:watchdog_ping
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/watchdog/watchdog_dev.c:watchdog_next_keepalive
  - drivers/md/dm-stats.c:dm_stats_account_io
  - drivers/md/dm-stats.c:dm_stats_account_io
  - drivers/md/dm-rq.c:map_request
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
  - net/ipv4/tcp_input.c:tcp_synack_rtt_meas
  - net/ipv4/tcp_output.c:tcp_send_window_probe
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/syncookies.c:cookie_init_timestamp
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
**Symbols:**

```
ffffffff81133010-ffffffff811330a5: ktime_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
ktime_t ktime_get();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81125a70)
Location: kernel/time/timekeeping.c:747
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_get_on_cpu
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_prepare_all
  - arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_get_khz
  - arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_snapshot_khz
  - kernel/fork.c:copy_process
  - kernel/async.c:async_synchronize_cookie_domain
  - kernel/async.c:async_synchronize_cookie_domain
  - kernel/async.c:async_run_entry_fn
  - kernel/async.c:async_run_entry_fn
  - kernel/sched/clock.c:__sched_clock_gtod_offset
  - kernel/sched/clock.c:__sched_clock_work
  - kernel/sched/debug.c:sched_debug_header
  - kernel/power/main.c:ksys_sync_helper
  - kernel/power/main.c:ksys_sync_helper
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image
  - kernel/power/swap.c:save_image
  - kernel/power/swap.c:save_image
  - kernel/power/wakelock.c:wakelock_lookup_add
  - kernel/power/wakelock.c:__wakelocks_gc
  - kernel/time/timer.c:usleep_range
  - kernel/time/timer_list.c:timer_list_start
  - kernel/time/timer_list.c:sysrq_timer_list_show
  - kernel/time/clockevents.c:clockevents_program_event
  - kernel/time/clockevents.c:clockevents_program_min_delta
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-oneshot.c:tick_resume_oneshot
  - kernel/time/tick-sched.c:tick_setup_sched_timer
  - kernel/time/tick-sched.c:tick_sched_timer
  - kernel/time/tick-sched.c:tick_irq_enter
  - kernel/time/tick-sched.c:tick_nohz_handler
  - kernel/time/tick-sched.c:tick_nohz_idle_exit
  - kernel/time/tick-sched.c:tick_nohz_idle_restart_tick
  - kernel/time/tick-sched.c:tick_nohz_irq_exit
  - kernel/time/tick-sched.c:tick_nohz_irq_exit
  - kernel/time/tick-sched.c:tick_nohz_idle_enter
  - kernel/time/tick-sched.c:get_cpu_iowait_time_us
  - kernel/time/tick-sched.c:get_cpu_idle_time_us
  - kernel/futex.c:__ia32_sys_futex_time32
  - kernel/futex.c:__x64_sys_futex_time32
  - kernel/futex.c:__ia32_sys_futex
  - kernel/futex.c:__x64_sys_futex
  - kernel/acct.c:do_acct_process
  - kernel/delayacct.c:__delayacct_thrashing_start
  - kernel/delayacct.c:__delayacct_freepages_start
  - kernel/delayacct.c:__delayacct_blkio_start
  - kernel/delayacct.c:delayacct_end
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/trace/blktrace.c:__blk_add_trace
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - fs/ext4/extents_status.c:__es_shrink
  - fs/ext4/extents_status.c:__es_shrink
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - crypto/jitterentropy-kcapi.c:jent_get_nstime
  - block/bio.c:__bio_clone_fast
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:blk_rq_init
  - block/blk-mq.c:blk_mq_start_request
  - block/blk-mq.c:blk_mq_get_request
  - block/blk-mq.c:blk_mq_get_request
  - block/bounce.c:__blk_queue_bounce
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:throtl_tg_is_idle
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-iocost.c:ioc_now
  - block/blk-iocost.c:ioc_refresh_params
  - block/blk-wbt.c:wb_timer_fn
  - lib/dim/rdma_dim.c:rdma_dim
  - lib/dim/rdma_dim.c:rdma_dim
  - drivers/pci/quirks.c:pci_do_fixups
  - drivers/pci/quirks.c:pci_do_fixups
  - drivers/acpi/button.c:acpi_lid_input_open
  - drivers/acpi/button.c:acpi_button_resume
  - drivers/acpi/button.c:acpi_lid_notify_state
  - drivers/acpi/button.c:acpi_lid_notify_state
  - drivers/acpi/button.c:acpi_lid_notify_state
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
  - drivers/acpi/cppc_acpi.c:check_pcc_chan
  - drivers/acpi/cppc_acpi.c:check_pcc_chan
  - drivers/connector/cn_proc.c:proc_exit_connector
  - drivers/connector/cn_proc.c:proc_coredump_connector
  - drivers/connector/cn_proc.c:proc_comm_connector
  - drivers/connector/cn_proc.c:proc_ptrace_connector
  - drivers/connector/cn_proc.c:proc_sid_connector
  - drivers/connector/cn_proc.c:proc_id_connector
  - drivers/connector/cn_proc.c:proc_exec_connector
  - drivers/connector/cn_proc.c:proc_fork_connector
  - drivers/base/dd.c:driver_probe_device
  - drivers/base/dd.c:driver_probe_device
  - drivers/base/power/main.c:dpm_suspend_start
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:dpm_suspend_end
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_noirq
  - drivers/base/power/main.c:dpm_run_callback
  - drivers/base/power/main.c:dpm_show_time
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show
  - drivers/base/power/wakeup_stats.c:prevent_suspend_time_ms_show
  - drivers/base/power/wakeup_stats.c:max_time_ms_show
  - drivers/base/power/wakeup_stats.c:total_time_ms_show
  - drivers/base/power/wakeup_stats.c:active_time_ms_show
  - drivers/base/power/domain.c:total_idle_time_show
  - drivers/base/power/domain.c:active_time_show
  - drivers/base/power/domain.c:idle_states_show
  - drivers/base/power/domain.c:pm_genpd_init
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_runtime_suspend
  - drivers/base/power/domain.c:genpd_runtime_suspend
  - drivers/base/power/domain.c:_genpd_power_off
  - drivers/base/power/domain.c:_genpd_power_off
  - drivers/base/power/domain.c:_genpd_power_on
  - drivers/base/power/domain.c:_genpd_power_on
  - drivers/base/power/domain.c:genpd_update_accounting
  - drivers/misc/sram.c:atmel_securam_wait
  - drivers/misc/sram.c:atmel_securam_wait
  - drivers/dma-buf/dma-fence.c:dma_fence_signal_locked
  - drivers/usb/host/xhci.c:xhci_handshake
  - drivers/usb/host/xhci.c:xhci_handshake
  - drivers/input/input.c:input_get_timestamp
  - drivers/input/input.c:input_repeat_key
  - drivers/media/cec/cec-adap.c:cec_transmit_msg_fh
  - drivers/media/cec/cec-adap.c:cec_wait_timeout
  - drivers/media/cec/cec-adap.c:cec_data_cancel
  - drivers/media/cec/cec-adap.c:cec_data_cancel
  - drivers/media/cec/cec-adap.c:cec_post_state_event
  - drivers/media/cec/cec-adap.c:cec_queue_msg_fh
  - drivers/media/cec/cec-adap.c:cec_queue_event_fh
  - drivers/thermal/thermal_sysfs.c:thermal_cooling_device_setup_sysfs
  - drivers/thermal/thermal_sysfs.c:reset_store
  - drivers/thermal/thermal_sysfs.c:update_time_in_state
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
  - drivers/watchdog/watchdog_dev.c:watchdog_start
  - drivers/watchdog/watchdog_dev.c:watchdog_ping_work
  - drivers/watchdog/watchdog_dev.c:watchdog_ping
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/watchdog/watchdog_dev.c:watchdog_next_keepalive
  - drivers/md/dm-stats.c:dm_stats_account_io
  - drivers/md/dm-stats.c:dm_stats_account_io
  - drivers/md/dm-rq.c:map_request
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
  - net/ipv4/tcp_input.c:tcp_synack_rtt_meas
  - net/ipv4/tcp_output.c:tcp_send_window_probe
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/syncookies.c:cookie_init_timestamp
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
**Symbols:**

```
ffffffff81125a70-ffffffff81125b05: ktime_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
ktime_t ktime_get();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81130d30)
Location: kernel/time/timekeeping.c:747
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_get_on_cpu
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_prepare_all
  - arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_get_khz
  - arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_snapshot_khz
  - kernel/fork.c:copy_process
  - kernel/async.c:async_synchronize_cookie_domain
  - kernel/async.c:async_synchronize_cookie_domain
  - kernel/async.c:async_run_entry_fn
  - kernel/async.c:async_run_entry_fn
  - kernel/sched/clock.c:__sched_clock_gtod_offset
  - kernel/sched/clock.c:__sched_clock_work
  - kernel/sched/debug.c:sched_debug_header
  - kernel/power/main.c:ksys_sync_helper
  - kernel/power/main.c:ksys_sync_helper
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image
  - kernel/power/swap.c:save_image
  - kernel/power/swap.c:save_image
  - kernel/power/wakelock.c:wakelock_lookup_add
  - kernel/power/wakelock.c:__wakelocks_gc
  - kernel/time/timer.c:usleep_range
  - kernel/time/timer_list.c:timer_list_start
  - kernel/time/timer_list.c:sysrq_timer_list_show
  - kernel/time/clockevents.c:clockevents_program_event
  - kernel/time/clockevents.c:clockevents_program_min_delta
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-oneshot.c:tick_resume_oneshot
  - kernel/time/tick-sched.c:tick_setup_sched_timer
  - kernel/time/tick-sched.c:tick_sched_timer
  - kernel/time/tick-sched.c:tick_irq_enter
  - kernel/time/tick-sched.c:tick_nohz_handler
  - kernel/time/tick-sched.c:tick_nohz_idle_exit
  - kernel/time/tick-sched.c:tick_nohz_idle_restart_tick
  - kernel/time/tick-sched.c:tick_nohz_irq_exit
  - kernel/time/tick-sched.c:tick_nohz_idle_enter
  - kernel/time/tick-sched.c:get_cpu_iowait_time_us
  - kernel/time/tick-sched.c:get_cpu_idle_time_us
  - kernel/futex.c:__ia32_sys_futex_time32
  - kernel/futex.c:__x64_sys_futex_time32
  - kernel/futex.c:__ia32_sys_futex
  - kernel/futex.c:__x64_sys_futex
  - kernel/acct.c:do_acct_process
  - kernel/delayacct.c:__delayacct_thrashing_start
  - kernel/delayacct.c:__delayacct_freepages_start
  - kernel/delayacct.c:__delayacct_blkio_start
  - kernel/delayacct.c:delayacct_end
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/trace/blktrace.c:__blk_add_trace
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - fs/ext4/extents_status.c:__es_shrink
  - fs/ext4/extents_status.c:__es_shrink
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - crypto/jitterentropy-kcapi.c:jent_get_nstime
  - block/bio.c:__bio_clone_fast
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:blk_rq_init
  - block/blk-mq.c:blk_mq_start_request
  - block/blk-mq.c:blk_mq_get_request
  - block/blk-mq.c:blk_mq_get_request
  - block/bounce.c:__blk_queue_bounce
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:throtl_tg_is_idle
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-iocost.c:ioc_now
  - block/blk-iocost.c:ioc_refresh_params
  - block/blk-wbt.c:wb_timer_fn
  - lib/dim/rdma_dim.c:rdma_dim
  - lib/dim/rdma_dim.c:rdma_dim
  - drivers/pci/quirks.c:pci_do_fixups
  - drivers/pci/quirks.c:pci_do_fixups
  - drivers/acpi/button.c:acpi_lid_input_open
  - drivers/acpi/button.c:acpi_button_resume
  - drivers/acpi/button.c:acpi_lid_notify_state
  - drivers/acpi/button.c:acpi_lid_notify_state
  - drivers/acpi/button.c:acpi_lid_notify_state
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
  - drivers/acpi/cppc_acpi.c:check_pcc_chan
  - drivers/acpi/cppc_acpi.c:check_pcc_chan
  - drivers/connector/cn_proc.c:proc_exit_connector
  - drivers/connector/cn_proc.c:proc_coredump_connector
  - drivers/connector/cn_proc.c:proc_comm_connector
  - drivers/connector/cn_proc.c:proc_ptrace_connector
  - drivers/connector/cn_proc.c:proc_sid_connector
  - drivers/connector/cn_proc.c:proc_id_connector
  - drivers/connector/cn_proc.c:proc_exec_connector
  - drivers/connector/cn_proc.c:proc_fork_connector
  - drivers/base/dd.c:driver_probe_device
  - drivers/base/dd.c:driver_probe_device
  - drivers/base/power/main.c:dpm_suspend_start
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:dpm_suspend_end
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_noirq
  - drivers/base/power/main.c:dpm_run_callback
  - drivers/base/power/main.c:dpm_show_time
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show
  - drivers/base/power/wakeup_stats.c:prevent_suspend_time_ms_show
  - drivers/base/power/wakeup_stats.c:max_time_ms_show
  - drivers/base/power/wakeup_stats.c:total_time_ms_show
  - drivers/base/power/wakeup_stats.c:active_time_ms_show
  - drivers/base/power/domain.c:total_idle_time_show
  - drivers/base/power/domain.c:active_time_show
  - drivers/base/power/domain.c:idle_states_show
  - drivers/base/power/domain.c:pm_genpd_init
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_runtime_suspend
  - drivers/base/power/domain.c:genpd_runtime_suspend
  - drivers/base/power/domain.c:_genpd_power_off
  - drivers/base/power/domain.c:_genpd_power_off
  - drivers/base/power/domain.c:_genpd_power_on
  - drivers/base/power/domain.c:_genpd_power_on
  - drivers/base/power/domain.c:genpd_update_accounting
  - drivers/misc/sram.c:atmel_securam_wait
  - drivers/misc/sram.c:atmel_securam_wait
  - drivers/dma-buf/dma-fence.c:dma_fence_signal_locked
  - drivers/usb/dwc2/core.c:dwc2_wait_for_mode
  - drivers/usb/host/ehci-hcd.c:ehci_hrtimer_func
  - drivers/usb/host/xhci.c:xhci_handshake
  - drivers/usb/host/xhci.c:xhci_handshake
  - drivers/input/input.c:input_get_timestamp
  - drivers/input/input.c:input_repeat_key
  - drivers/media/cec/cec-adap.c:cec_transmit_msg_fh
  - drivers/media/cec/cec-adap.c:cec_wait_timeout
  - drivers/media/cec/cec-adap.c:cec_data_cancel
  - drivers/media/cec/cec-adap.c:cec_data_cancel
  - drivers/media/cec/cec-adap.c:cec_post_state_event
  - drivers/media/cec/cec-adap.c:cec_queue_msg_fh
  - drivers/media/cec/cec-adap.c:cec_queue_event_fh
  - drivers/power/supply/charger-manager.c:try_charger_enable
  - drivers/power/supply/charger-manager.c:try_charger_enable
  - drivers/thermal/thermal_sysfs.c:thermal_cooling_device_setup_sysfs
  - drivers/thermal/thermal_sysfs.c:reset_store
  - drivers/thermal/thermal_sysfs.c:update_time_in_state
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
  - drivers/watchdog/watchdog_dev.c:watchdog_start
  - drivers/watchdog/watchdog_dev.c:watchdog_ping_work
  - drivers/watchdog/watchdog_dev.c:watchdog_ping
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/watchdog/watchdog_dev.c:watchdog_next_keepalive
  - drivers/md/dm-stats.c:dm_stats_account_io
  - drivers/md/dm-stats.c:dm_stats_account_io
  - drivers/md/dm-rq.c:map_request
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
  - net/ipv4/tcp_input.c:tcp_synack_rtt_meas
  - net/ipv4/tcp_output.c:tcp_send_window_probe
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/syncookies.c:cookie_init_timestamp
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
**Symbols:**

```
ffffffff81130d30-ffffffff81130dc5: ktime_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
ktime_t ktime_get();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff8113d750)
Location: kernel/time/timekeeping.c:747
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_get_on_cpu
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_prepare_all
  - arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_get_khz
  - arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_snapshot_khz
  - kernel/fork.c:copy_process
  - kernel/async.c:async_synchronize_cookie_domain
  - kernel/async.c:async_synchronize_cookie_domain
  - kernel/async.c:async_run_entry_fn
  - kernel/async.c:async_run_entry_fn
  - kernel/sched/clock.c:__sched_clock_gtod_offset
  - kernel/sched/clock.c:__sched_clock_work
  - kernel/sched/debug.c:sched_debug_header
  - kernel/power/main.c:ksys_sync_helper
  - kernel/power/main.c:ksys_sync_helper
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image
  - kernel/power/swap.c:save_image
  - kernel/power/swap.c:save_image
  - kernel/power/wakelock.c:wakelock_lookup_add
  - kernel/power/wakelock.c:__wakelocks_gc
  - kernel/time/timer.c:usleep_range
  - kernel/time/timer_list.c:timer_list_start
  - kernel/time/timer_list.c:sysrq_timer_list_show
  - kernel/time/clockevents.c:clockevents_program_event
  - kernel/time/clockevents.c:clockevents_program_min_delta
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-oneshot.c:tick_resume_oneshot
  - kernel/time/tick-sched.c:tick_setup_sched_timer
  - kernel/time/tick-sched.c:tick_sched_timer
  - kernel/time/tick-sched.c:tick_irq_enter
  - kernel/time/tick-sched.c:tick_nohz_handler
  - kernel/time/tick-sched.c:tick_nohz_idle_exit
  - kernel/time/tick-sched.c:tick_nohz_idle_restart_tick
  - kernel/time/tick-sched.c:tick_nohz_irq_exit
  - kernel/time/tick-sched.c:tick_nohz_idle_enter
  - kernel/time/tick-sched.c:get_cpu_iowait_time_us
  - kernel/time/tick-sched.c:get_cpu_idle_time_us
  - kernel/futex.c:__ia32_sys_futex_time32
  - kernel/futex.c:__x64_sys_futex_time32
  - kernel/futex.c:__ia32_sys_futex
  - kernel/futex.c:__x64_sys_futex
  - kernel/acct.c:do_acct_process
  - kernel/delayacct.c:__delayacct_thrashing_start
  - kernel/delayacct.c:__delayacct_freepages_start
  - kernel/delayacct.c:__delayacct_blkio_start
  - kernel/delayacct.c:delayacct_end
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/trace/blktrace.c:__blk_add_trace
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - fs/ext4/extents_status.c:__es_shrink
  - fs/ext4/extents_status.c:__es_shrink
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - crypto/jitterentropy-kcapi.c:jent_get_nstime
  - block/bio.c:__bio_clone_fast
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:blk_rq_init
  - block/blk-mq.c:blk_mq_start_request
  - block/blk-mq.c:blk_mq_get_request
  - block/blk-mq.c:blk_mq_get_request
  - block/bounce.c:__blk_queue_bounce
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:throtl_tg_is_idle
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-iocost.c:ioc_now
  - block/blk-iocost.c:ioc_refresh_params
  - block/blk-wbt.c:wb_timer_fn
  - lib/dim/rdma_dim.c:rdma_dim
  - lib/dim/rdma_dim.c:rdma_dim
  - drivers/pci/quirks.c:pci_do_fixups
  - drivers/pci/quirks.c:pci_do_fixups
  - drivers/acpi/button.c:acpi_lid_input_open
  - drivers/acpi/button.c:acpi_button_resume
  - drivers/acpi/button.c:acpi_lid_notify_state
  - drivers/acpi/button.c:acpi_lid_notify_state
  - drivers/acpi/button.c:acpi_lid_notify_state
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
  - drivers/acpi/cppc_acpi.c:check_pcc_chan
  - drivers/acpi/cppc_acpi.c:check_pcc_chan
  - drivers/connector/cn_proc.c:proc_exit_connector
  - drivers/connector/cn_proc.c:proc_coredump_connector
  - drivers/connector/cn_proc.c:proc_comm_connector
  - drivers/connector/cn_proc.c:proc_ptrace_connector
  - drivers/connector/cn_proc.c:proc_sid_connector
  - drivers/connector/cn_proc.c:proc_id_connector
  - drivers/connector/cn_proc.c:proc_exec_connector
  - drivers/connector/cn_proc.c:proc_fork_connector
  - drivers/base/dd.c:driver_probe_device
  - drivers/base/dd.c:driver_probe_device
  - drivers/base/power/main.c:dpm_suspend_start
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:dpm_suspend_end
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_noirq
  - drivers/base/power/main.c:dpm_run_callback
  - drivers/base/power/main.c:dpm_show_time
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show
  - drivers/base/power/wakeup_stats.c:prevent_suspend_time_ms_show
  - drivers/base/power/wakeup_stats.c:max_time_ms_show
  - drivers/base/power/wakeup_stats.c:total_time_ms_show
  - drivers/base/power/wakeup_stats.c:active_time_ms_show
  - drivers/base/power/domain.c:total_idle_time_show
  - drivers/base/power/domain.c:active_time_show
  - drivers/base/power/domain.c:idle_states_show
  - drivers/base/power/domain.c:pm_genpd_init
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_runtime_suspend
  - drivers/base/power/domain.c:genpd_runtime_suspend
  - drivers/base/power/domain.c:_genpd_power_off
  - drivers/base/power/domain.c:_genpd_power_off
  - drivers/base/power/domain.c:_genpd_power_on
  - drivers/base/power/domain.c:_genpd_power_on
  - drivers/base/power/domain.c:genpd_update_accounting
  - drivers/misc/sram.c:atmel_securam_wait
  - drivers/misc/sram.c:atmel_securam_wait
  - drivers/dma-buf/dma-fence.c:dma_fence_signal_locked
  - drivers/usb/dwc2/core.c:dwc2_wait_for_mode
  - drivers/usb/host/ehci-hcd.c:ehci_hrtimer_func
  - drivers/usb/host/xhci.c:xhci_handshake
  - drivers/usb/host/xhci.c:xhci_handshake
  - drivers/input/input.c:input_get_timestamp
  - drivers/input/input.c:input_repeat_key
  - drivers/media/cec/cec-adap.c:cec_transmit_msg_fh
  - drivers/media/cec/cec-adap.c:cec_wait_timeout
  - drivers/media/cec/cec-adap.c:cec_data_cancel
  - drivers/media/cec/cec-adap.c:cec_data_cancel
  - drivers/media/cec/cec-adap.c:cec_post_state_event
  - drivers/media/cec/cec-adap.c:cec_queue_msg_fh
  - drivers/media/cec/cec-adap.c:cec_queue_event_fh
  - drivers/media/cec/cec-pin.c:cec_pin_timer
  - drivers/media/cec/cec-pin.c:cec_pin_update
  - drivers/power/supply/charger-manager.c:try_charger_enable
  - drivers/power/supply/charger-manager.c:try_charger_enable
  - drivers/thermal/thermal_sysfs.c:thermal_cooling_device_setup_sysfs
  - drivers/thermal/thermal_sysfs.c:reset_store
  - drivers/thermal/thermal_sysfs.c:update_time_in_state
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
  - drivers/watchdog/watchdog_dev.c:watchdog_start
  - drivers/watchdog/watchdog_dev.c:watchdog_ping_work
  - drivers/watchdog/watchdog_dev.c:watchdog_ping
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/watchdog/watchdog_dev.c:watchdog_next_keepalive
  - drivers/md/dm-stats.c:dm_stats_account_io
  - drivers/md/dm-stats.c:dm_stats_account_io
  - drivers/md/dm-rq.c:map_request
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
  - net/ipv4/tcp_input.c:tcp_synack_rtt_meas
  - net/ipv4/tcp_output.c:tcp_send_window_probe
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/syncookies.c:cookie_init_timestamp
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
**Symbols:**

```
ffffffff8113d750-ffffffff8113d7e5: ktime_get (STB_GLOBAL)
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
