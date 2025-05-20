# Function: <code>div_u64</code>

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
In arch/x86/kernel/cpu/mshyperv.c (0)
Location: include/linux/math64.h:97
Inline: True
```
```
In kernel/sched/cputime.c (ffffffff810b1640)
Location: include/linux/math64.h:97
Inline: True
Inline callers:
  - kernel/sched/cputime.c:cputime_adjust
```
```
In kernel/sched/fair.c (ffffffff810b4361)
Location: include/linux/math64.h:97
Inline: True
Inline callers:
  - kernel/sched/fair.c:detach_task_cfs_rq
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:update_group_capacity
```
```
In kernel/sched/rt.c (ffffffff810bf984)
Location: include/linux/math64.h:97
Inline: True
```
```
In kernel/time/time.c (ffffffff810eaee1)
Location: include/linux/math64.h:97
Inline: True
Inline callers:
  - kernel/time/time.c:clock_t_to_jiffies
```
```
In kernel/time/ntp.c (ffffffff810f6d20)
Location: include/linux/math64.h:97
Inline: True
Inline callers:
  - kernel/time/ntp.c:ntp_update_frequency
```
```
In mm/page-writeback.c (ffffffff81198190)
Location: include/linux/math64.h:97
Inline: True
Inline callers:
  - mm/page-writeback.c:wb_update_dirty_ratelimit
  - mm/page-writeback.c:wb_position_ratio
  - mm/page-writeback.c:wb_position_ratio
```
```
In mm/vmstat.c (0)
Location: include/linux/math64.h:97
Inline: True
```
```
In mm/slub.c (0)
Location: include/linux/math64.h:97
Inline: True
```
```
In fs/ext4/super.c (0)
Location: include/linux/math64.h:97
Inline: True
```
```
In fs/ext4/extents_status.c (0)
Location: include/linux/math64.h:97
Inline: True
```
```
In fs/jbd2/journal.c (0)
Location: include/linux/math64.h:97
Inline: True
```
```
In block/partitions/efi.c (0)
Location: include/linux/math64.h:97
Inline: True
```
```
In lib/vsprintf.c (ffffffff813f341f)
Location: include/linux/math64.h:97
Inline: True
Inline callers:
  - lib/vsprintf.c:vsscanf
```
```
In lib/kstrtox.c (ffffffff81401ca9)
Location: include/linux/math64.h:97
Inline: True
Inline callers:
  - lib/kstrtox.c:_parse_integer
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff8159c522)
Location: include/linux/math64.h:97
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:size_store
```
```
In drivers/nvdimm/label.c (0)
Location: include/linux/math64.h:97
Inline: True
```
```
In drivers/devfreq/governor_simpleondemand.c (ffffffff816edd95)
Location: include/linux/math64.h:97
Inline: True
Inline callers:
  - drivers/devfreq/governor_simpleondemand.c:devfreq_simple_ondemand_func
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/math64.h:97
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
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81f95c42)
Location: include/linux/math64.h:97
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
```
```
In kernel/sched/cputime.c (0)
Location: include/linux/math64.h:97
Inline: True
```
```
In kernel/sched/fair.c (ffffffff810b9f2f)
Location: include/linux/math64.h:97
Inline: True
Inline callers:
  - kernel/sched/fair.c:attach_task_cfs_rq
  - kernel/sched/fair.c:attach_task_cfs_rq
  - kernel/sched/fair.c:detach_task_cfs_rq
  - kernel/sched/fair.c:detach_task_cfs_rq
  - kernel/sched/fair.c:detach_task_cfs_rq
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:update_group_capacity
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
```
```
In kernel/sched/rt.c (ffffffff810c32b5)
Location: include/linux/math64.h:97
Inline: True
```
```
In kernel/time/time.c (ffffffff810f1c15)
Location: include/linux/math64.h:97
Inline: True
Inline callers:
  - kernel/time/time.c:nsecs_to_jiffies
  - kernel/time/time.c:nsec_to_clock_t
  - kernel/time/time.c:jiffies_64_to_clock_t
  - kernel/time/time.c:clock_t_to_jiffies
  - kernel/time/time.c:jiffies_to_clock_t
```
```
In kernel/time/ntp.c (ffffffff810fde90)
Location: include/linux/math64.h:97
Inline: True
Inline callers:
  - kernel/time/ntp.c:ntp_update_frequency
```
```
In kernel/events/core.c (ffffffff8119112d)
Location: include/linux/math64.h:97
Inline: True
Inline callers:
  - kernel/events/core.c:perf_cpu_time_max_percent_handler
  - kernel/events/core.c:perf_proc_update_handler
```
```
In mm/page-writeback.c (ffffffff811ad0ea)
Location: include/linux/math64.h:97
Inline: True
Inline callers:
  - mm/page-writeback.c:wb_update_dirty_ratelimit
  - mm/page-writeback.c:wb_position_ratio
  - mm/page-writeback.c:wb_position_ratio
```
```
In mm/vmstat.c (ffffffff811c5cd0)
Location: include/linux/math64.h:97
Inline: True
Inline callers:
  - mm/vmstat.c:extfrag_show_print
  - mm/vmstat.c:extfrag_show_print
  - mm/vmstat.c:unusable_show_print
  - mm/vmstat.c:fragmentation_index
  - mm/vmstat.c:fragmentation_index
```
```
In mm/slub.c (ffffffff8120c3be)
Location: include/linux/math64.h:97
Inline: True
Inline callers:
  - mm/slub.c:list_locations
```
```
In fs/ext4/super.c (ffffffff812dd416)
Location: include/linux/math64.h:97
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_es_shrink
  - fs/ext4/super.c:trace_event_raw_event_ext4_es_shrink
```
```
In fs/ext4/extents_status.c (ffffffff8130bc4a)
Location: include/linux/math64.h:97
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
```
```
In fs/jbd2/journal.c (ffffffff8131d2eb)
Location: include/linux/math64.h:97
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_seq_info_show
```
```
In block/partitions/efi.c (ffffffff8141a184)
Location: include/linux/math64.h:97
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:is_gpt_valid
  - block/partitions/efi.c:read_lba
```
```
In block/cfq-iosched.c (ffffffff814232cd)
Location: include/linux/math64.h:97
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_target_latency_us_show
  - block/cfq-iosched.c:cfq_slice_async_us_show
  - block/cfq-iosched.c:cfq_slice_sync_us_show
  - block/cfq-iosched.c:cfq_group_idle_us_show
  - block/cfq-iosched.c:cfq_slice_idle_us_show
  - block/cfq-iosched.c:cfq_target_latency_show
  - block/cfq-iosched.c:cfq_slice_async_show
  - block/cfq-iosched.c:cfq_slice_sync_show
  - block/cfq-iosched.c:cfq_group_idle_show
  - block/cfq-iosched.c:cfq_slice_idle_show
  - block/cfq-iosched.c:cfq_fifo_expire_async_show
  - block/cfq-iosched.c:cfq_fifo_expire_sync_show
  - block/cfq-iosched.c:__cfq_update_io_thinktime
  - block/cfq-iosched.c:cfq_dispatch_requests
  - block/cfq-iosched.c:cfq_dispatch_requests
  - block/cfq-iosched.c:__cfq_slice_expired
  - block/cfq-iosched.c:cfq_service_tree_add
  - block/cfq-iosched.c:cfq_service_tree_add
  - block/cfq-iosched.c:cfq_group_served
  - block/cfq-iosched.c:cfq_set_prio_slice
```
```
In lib/vsprintf.c (ffffffff8143b0b7)
Location: include/linux/math64.h:97
Inline: True
Inline callers:
  - lib/vsprintf.c:vsscanf
```
```
In lib/kstrtox.c (ffffffff81449759)
Location: include/linux/math64.h:97
Inline: True
Inline callers:
  - lib/kstrtox.c:_parse_integer
```
```
In drivers/nvdimm/core.c (ffffffff815ebd16)
Location: include/linux/math64.h:97
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:__add_badblock_range
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff815f25b5)
Location: include/linux/math64.h:97
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:size_store
```
```
In drivers/nvdimm/label.c (ffffffff815f678a)
Location: include/linux/math64.h:97
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_pmem_namespace_label_update
```
```
In drivers/cpuidle/governors/menu.c (ffffffff8171e9e7)
Location: include/linux/math64.h:97
Inline: True
Inline callers:
  - drivers/cpuidle/governors/menu.c:menu_select
```
```
In drivers/devfreq/governor_simpleondemand.c (ffffffff81752cb9)
Location: include/linux/math64.h:97
Inline: True
Inline callers:
  - drivers/devfreq/governor_simpleondemand.c:devfreq_simple_ondemand_func
  - drivers/devfreq/governor_simpleondemand.c:devfreq_simple_ondemand_func
```
```
In net/ipv4/tcp_input.c (ffffffff817de1ce)
Location: include/linux/math64.h:97
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack
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
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81fd10ef)
Location: include/linux/math64.h:97
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
```
```
In kernel/sched/cputime.c (0)
Location: include/linux/math64.h:97
Inline: True
```
```
In kernel/sched/fair.c (ffffffff810c3caa)
Location: include/linux/math64.h:97
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:update_group_capacity
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
```
```
In kernel/sched/rt.c (ffffffff810c931a)
Location: include/linux/math64.h:97
Inline: True
```
```
In kernel/time/time.c (ffffffff810f8d95)
Location: include/linux/math64.h:97
Inline: True
Inline callers:
  - kernel/time/time.c:nsecs_to_jiffies
  - kernel/time/time.c:nsec_to_clock_t
  - kernel/time/time.c:jiffies_64_to_clock_t
  - kernel/time/time.c:clock_t_to_jiffies
  - kernel/time/time.c:jiffies_to_clock_t
```
```
In kernel/time/ntp.c (ffffffff81100c80)
Location: include/linux/math64.h:97
Inline: True
Inline callers:
  - kernel/time/ntp.c:ntp_update_frequency
```
```
In kernel/trace/trace_hwlat.c (ffffffff8116d596)
Location: include/linux/math64.h:97
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/trace/trace_hwlat.c:kthread_fn
```
```
In kernel/events/core.c (ffffffff811a080d)
Location: include/linux/math64.h:97
Inline: True
Inline callers:
  - kernel/events/core.c:perf_cpu_time_max_percent_handler
  - kernel/events/core.c:perf_proc_update_handler
```
```
In mm/page-writeback.c (ffffffff811bd64a)
Location: include/linux/math64.h:97
Inline: True
Inline callers:
  - mm/page-writeback.c:wb_update_dirty_ratelimit
  - mm/page-writeback.c:wb_position_ratio
  - mm/page-writeback.c:wb_position_ratio
```
```
In mm/vmstat.c (ffffffff811d5dc0)
Location: include/linux/math64.h:97
Inline: True
Inline callers:
  - mm/vmstat.c:extfrag_show_print
  - mm/vmstat.c:extfrag_show_print
  - mm/vmstat.c:unusable_show_print
  - mm/vmstat.c:fragmentation_index
  - mm/vmstat.c:fragmentation_index
```
```
In mm/slub.c (ffffffff8121e3dd)
Location: include/linux/math64.h:97
Inline: True
Inline callers:
  - mm/slub.c:list_locations
```
```
In fs/ext4/super.c (ffffffff812f2f64)
Location: include/linux/math64.h:97
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_es_shrink
  - fs/ext4/super.c:trace_event_raw_event_ext4_es_shrink
```
```
In fs/ext4/extents_status.c (ffffffff81321c47)
Location: include/linux/math64.h:97
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
```
```
In fs/jbd2/journal.c (ffffffff81333478)
Location: include/linux/math64.h:97
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_seq_info_show
```
```
In block/blk-sysfs.c (ffffffff81419b0f)
Location: include/linux/math64.h:97
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_wb_lat_show
```
```
In block/partitions/efi.c (ffffffff814356b4)
Location: include/linux/math64.h:97
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:is_gpt_valid
  - block/partitions/efi.c:read_lba
```
```
In block/cfq-iosched.c (ffffffff8143e3cd)
Location: include/linux/math64.h:97
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_target_latency_us_show
  - block/cfq-iosched.c:cfq_slice_async_us_show
  - block/cfq-iosched.c:cfq_slice_sync_us_show
  - block/cfq-iosched.c:cfq_group_idle_us_show
  - block/cfq-iosched.c:cfq_slice_idle_us_show
  - block/cfq-iosched.c:cfq_target_latency_show
  - block/cfq-iosched.c:cfq_slice_async_show
  - block/cfq-iosched.c:cfq_slice_sync_show
  - block/cfq-iosched.c:cfq_group_idle_show
  - block/cfq-iosched.c:cfq_slice_idle_show
  - block/cfq-iosched.c:cfq_fifo_expire_async_show
  - block/cfq-iosched.c:cfq_fifo_expire_sync_show
  - block/cfq-iosched.c:__cfq_update_io_thinktime
  - block/cfq-iosched.c:cfq_dispatch_requests
  - block/cfq-iosched.c:cfq_dispatch_requests
  - block/cfq-iosched.c:__cfq_slice_expired
  - block/cfq-iosched.c:cfq_service_tree_add
  - block/cfq-iosched.c:cfq_service_tree_add
  - block/cfq-iosched.c:cfq_group_served
  - block/cfq-iosched.c:cfq_set_prio_slice
```
```
In block/blk-wbt.c (ffffffff81449ce9)
Location: include/linux/math64.h:97
Inline: True
Inline callers:
  - block/blk-wbt.c:rwb_arm_timer
  - block/blk-wbt.c:perf_trace_wbt_step
  - block/blk-wbt.c:perf_trace_wbt_lat
  - block/blk-wbt.c:trace_event_raw_event_wbt_step
  - block/blk-wbt.c:trace_event_raw_event_wbt_lat
```
```
In lib/vsprintf.c (ffffffff8145808b)
Location: include/linux/math64.h:97
Inline: True
Inline callers:
  - lib/vsprintf.c:vsscanf
```
```
In lib/kstrtox.c (ffffffff8146813f)
Location: include/linux/math64.h:97
Inline: True
Inline callers:
  - lib/kstrtox.c:_parse_integer
```
```
In drivers/nvdimm/core.c (ffffffff81618906)
Location: include/linux/math64.h:97
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:__add_badblock_range
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff8161fe13)
Location: include/linux/math64.h:97
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:size_store
```
```
In drivers/cpuidle/governors/menu.c (ffffffff81751547)
Location: include/linux/math64.h:97
Inline: True
Inline callers:
  - drivers/cpuidle/governors/menu.c:menu_select
```
```
In drivers/devfreq/governor_simpleondemand.c (ffffffff8177eaa9)
Location: include/linux/math64.h:97
Inline: True
Inline callers:
  - drivers/devfreq/governor_simpleondemand.c:devfreq_simple_ondemand_func
  - drivers/devfreq/governor_simpleondemand.c:devfreq_simple_ondemand_func
```
```
In net/ipv4/tcp_input.c (ffffffff8180e516)
Location: include/linux/math64.h:97
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack
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
In arch/x86/kernel/cpu/mshyperv.c (ffffffff820b1c46)
Location: include/linux/math64.h:97
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
```
```
In kernel/sched/cputime.c (ffffffff810b4fa5)
Location: include/linux/math64.h:97
Inline: True
Inline callers:
  - kernel/sched/cputime.c:cputime_adjust
```
```
In kernel/sched/fair.c (ffffffff810c26f0)
Location: include/linux/math64.h:97
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:update_group_capacity
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
```
```
In kernel/sched/rt.c (ffffffff810c3413)
Location: include/linux/math64.h:97
Inline: True
```
```
In kernel/time/time.c (ffffffff810fadd5)
Location: include/linux/math64.h:97
Inline: True
Inline callers:
  - kernel/time/time.c:nsecs_to_jiffies
  - kernel/time/time.c:nsec_to_clock_t
  - kernel/time/time.c:jiffies_64_to_clock_t
  - kernel/time/time.c:clock_t_to_jiffies
  - kernel/time/time.c:jiffies_to_clock_t
```
```
In kernel/time/ntp.c (ffffffff81102dc0)
Location: include/linux/math64.h:97
Inline: True
Inline callers:
  - kernel/time/ntp.c:ntp_update_frequency
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8110ab5c)
Location: include/linux/math64.h:97
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
```
```
In kernel/taskstats.c (ffffffff8115343f)
Location: include/linux/math64.h:97
Inline: True
```
```
In kernel/tsacct.c (ffffffff81153cbf)
Location: include/linux/math64.h:97
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/tsacct.c:bacct_add_tsk
```
```
In kernel/trace/trace_hwlat.c (ffffffff81170724)
Location: include/linux/math64.h:97
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/trace/trace_hwlat.c:kthread_fn
```
```
In kernel/events/core.c (ffffffff811a81ed)
Location: include/linux/math64.h:97
Inline: True
Inline callers:
  - kernel/events/core.c:perf_cpu_time_max_percent_handler
  - kernel/events/core.c:perf_proc_update_handler
```
```
In mm/page-writeback.c (ffffffff811c58cb)
Location: include/linux/math64.h:97
Inline: True
Inline callers:
  - mm/page-writeback.c:wb_update_dirty_ratelimit
  - mm/page-writeback.c:wb_position_ratio
  - mm/page-writeback.c:wb_position_ratio
```
```
In mm/vmstat.c (ffffffff811deb00)
Location: include/linux/math64.h:97
Inline: True
Inline callers:
  - mm/vmstat.c:extfrag_show_print
  - mm/vmstat.c:extfrag_show_print
  - mm/vmstat.c:unusable_show_print
  - mm/vmstat.c:fragmentation_index
  - mm/vmstat.c:fragmentation_index
```
```
In mm/slub.c (ffffffff81229eef)
Location: include/linux/math64.h:97
Inline: True
Inline callers:
  - mm/slub.c:list_locations
```
```
In fs/ext4/extents_status.c (ffffffff812f0b98)
Location: include/linux/math64.h:97
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
```
```
In fs/ext4/super.c (ffffffff81327ab2)
Location: include/linux/math64.h:97
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_es_shrink
  - fs/ext4/super.c:trace_event_raw_event_ext4_es_shrink
```
```
In fs/jbd2/journal.c (ffffffff81348218)
Location: include/linux/math64.h:97
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_seq_info_show
```
```
In block/blk-sysfs.c (ffffffff81427a3f)
Location: include/linux/math64.h:97
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_wb_lat_show
```
```
In block/partitions/efi.c (ffffffff81442205)
Location: include/linux/math64.h:97
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:read_lba
```
```
In block/cfq-iosched.c (ffffffff8144d7ad)
Location: include/linux/math64.h:97
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_target_latency_us_show
  - block/cfq-iosched.c:cfq_slice_async_us_show
  - block/cfq-iosched.c:cfq_slice_sync_us_show
  - block/cfq-iosched.c:cfq_group_idle_us_show
  - block/cfq-iosched.c:cfq_slice_idle_us_show
  - block/cfq-iosched.c:cfq_target_latency_show
  - block/cfq-iosched.c:cfq_slice_async_show
  - block/cfq-iosched.c:cfq_slice_sync_show
  - block/cfq-iosched.c:cfq_group_idle_show
  - block/cfq-iosched.c:cfq_slice_idle_show
  - block/cfq-iosched.c:cfq_fifo_expire_async_show
  - block/cfq-iosched.c:cfq_fifo_expire_sync_show
  - block/cfq-iosched.c:__cfq_update_io_thinktime
  - block/cfq-iosched.c:cfq_dispatch_requests
  - block/cfq-iosched.c:cfq_dispatch_requests
  - block/cfq-iosched.c:__cfq_slice_expired
  - block/cfq-iosched.c:cfq_service_tree_add
  - block/cfq-iosched.c:cfq_service_tree_add
  - block/cfq-iosched.c:cfq_group_served
  - block/cfq-iosched.c:cfq_set_prio_slice
```
```
In block/blk-wbt.c (ffffffff8145816d)
Location: include/linux/math64.h:97
Inline: True
Inline callers:
  - block/blk-wbt.c:rwb_arm_timer
  - block/blk-wbt.c:perf_trace_wbt_step
  - block/blk-wbt.c:perf_trace_wbt_lat
  - block/blk-wbt.c:trace_event_raw_event_wbt_step
  - block/blk-wbt.c:trace_event_raw_event_wbt_lat
```
```
In lib/kstrtox.c (ffffffff8146d888)
Location: include/linux/math64.h:97
Inline: True
Inline callers:
  - lib/kstrtox.c:_parse_integer
```
```
In drivers/nvdimm/core.c (ffffffff8162c7b1)
Location: include/linux/math64.h:97
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:__add_badblock_range
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff8163475d)
Location: include/linux/math64.h:97
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:size_store
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff817279c7)
Location: include/linux/math64.h:97
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81760878)
Location: include/linux/math64.h:97
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:get_cpu_idle_time
  - drivers/cpufreq/cpufreq.c:get_cpu_idle_time
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff817670fd)
Location: include/linux/math64.h:97
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:dbs_update
```
```
In drivers/cpuidle/governors/menu.c (ffffffff8177002f)
Location: include/linux/math64.h:97
Inline: True
Inline callers:
  - drivers/cpuidle/governors/menu.c:menu_select
```
```
In drivers/devfreq/governor_simpleondemand.c (ffffffff8179d5b7)
Location: include/linux/math64.h:97
Inline: True
Inline callers:
  - drivers/devfreq/governor_simpleondemand.c:devfreq_simple_ondemand_func
  - drivers/devfreq/governor_simpleondemand.c:devfreq_simple_ondemand_func
```
```
In net/ipv4/tcp.c (ffffffff8182357d)
Location: include/linux/math64.h:97
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff8182c305)
Location: include/linux/math64.h:97
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_synack_rtt_meas
  - net/ipv4/tcp_input.c:tcp_cwnd_reduction
  - net/ipv4/tcp_input.c:tcp_init_buffer_space
```
```
In net/ipv4/tcp_output.c (ffffffff818373b2)
Location: include/linux/math64.h:97
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_window_probe
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_established_options
```
```
In net/ipv4/tcp_timer.c (ffffffff81838623)
Location: include/linux/math64.h:97
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8183cd61)
Location: include/linux/math64.h:97
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/syncookies.c (ffffffff8186e059)
Location: include/linux/math64.h:97
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_init_timestamp
```
```
In net/ipv6/tcp_ipv6.c (ffffffff818b8c8a)
Location: include/linux/math64.h:97
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
```
```
In lib/vsprintf.c (ffffffff818f9c01)
Location: include/linux/math64.h:97
Inline: True
Inline callers:
  - lib/vsprintf.c:vsscanf
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
In arch/x86/kernel/cpu/mshyperv.c (ffffffff826b84ae)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
```
```
In kernel/sched/cputime.c (ffffffff810bc835)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - kernel/sched/cputime.c:cputime_adjust
```
```
In kernel/sched/fair.c (ffffffff810c9b0a)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:update_group_capacity
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:attach_entity_load_avg
  - kernel/sched/fair.c:reweight_entity
  - kernel/sched/fair.c:reweight_entity
```
```
In kernel/sched/rt.c (ffffffff810ca6ce)
Location: include/linux/math64.h:123
Inline: True
```
```
In kernel/time/time.c (ffffffff81105765)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - kernel/time/time.c:nsecs_to_jiffies
  - kernel/time/time.c:nsec_to_clock_t
  - kernel/time/time.c:jiffies_64_to_clock_t
  - kernel/time/time.c:clock_t_to_jiffies
  - kernel/time/time.c:jiffies_to_clock_t
```
```
In kernel/time/ntp.c (ffffffff8110dea0)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - kernel/time/ntp.c:ntp_update_frequency
```
```
In kernel/time/posix-cpu-timers.c (ffffffff81115d3b)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
```
```
In kernel/taskstats.c (ffffffff8115fc3f)
Location: include/linux/math64.h:123
Inline: True
```
```
In kernel/tsacct.c (ffffffff811604bf)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/tsacct.c:bacct_add_tsk
```
```
In kernel/trace/trace_hwlat.c (ffffffff8117d8f4)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/trace/trace_hwlat.c:kthread_fn
```
```
In kernel/events/core.c (ffffffff811bb95d)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - kernel/events/core.c:perf_cpu_time_max_percent_handler
  - kernel/events/core.c:perf_proc_update_handler
```
```
In mm/page-writeback.c (ffffffff811dbc6a)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:wb_update_dirty_ratelimit
  - mm/page-writeback.c:wb_position_ratio
  - mm/page-writeback.c:wb_position_ratio
```
```
In mm/vmstat.c (ffffffff811f47c8)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - mm/vmstat.c:unusable_show_print
  - mm/vmstat.c:__fragmentation_index
  - mm/vmstat.c:__fragmentation_index
```
```
In mm/slub.c (ffffffff8124509f)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - mm/slub.c:list_locations
```
```
In fs/ext4/extents_status.c (ffffffff813156c8)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
```
```
In fs/ext4/super.c (ffffffff8134bf68)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_es_shrink
  - fs/ext4/super.c:trace_event_raw_event_ext4_es_shrink
```
```
In fs/jbd2/journal.c (ffffffff8136c858)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_seq_info_show
```
```
In security/keys/proc.c (ffffffff813bad8f)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - security/keys/proc.c:proc_keys_show
  - security/keys/proc.c:proc_keys_show
  - security/keys/proc.c:proc_keys_show
  - security/keys/proc.c:proc_keys_show
```
```
In block/blk-sysfs.c (ffffffff81452aff)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_wb_lat_show
```
```
In block/blk-stat.c (ffffffff8145ff2b)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - block/blk-stat.c:blk_stat_timer_fn
```
```
In block/partitions/efi.c (ffffffff8146eb75)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:read_lba
```
```
In block/cfq-iosched.c (ffffffff81479ead)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_target_latency_us_show
  - block/cfq-iosched.c:cfq_slice_async_us_show
  - block/cfq-iosched.c:cfq_slice_sync_us_show
  - block/cfq-iosched.c:cfq_group_idle_us_show
  - block/cfq-iosched.c:cfq_slice_idle_us_show
  - block/cfq-iosched.c:cfq_target_latency_show
  - block/cfq-iosched.c:cfq_slice_async_show
  - block/cfq-iosched.c:cfq_slice_sync_show
  - block/cfq-iosched.c:cfq_group_idle_show
  - block/cfq-iosched.c:cfq_slice_idle_show
  - block/cfq-iosched.c:cfq_fifo_expire_async_show
  - block/cfq-iosched.c:cfq_fifo_expire_sync_show
  - block/cfq-iosched.c:cfq_completed_request
  - block/cfq-iosched.c:__cfq_update_io_thinktime
  - block/cfq-iosched.c:cfq_dispatch_requests
  - block/cfq-iosched.c:cfq_dispatch_requests
  - block/cfq-iosched.c:__cfq_slice_expired
  - block/cfq-iosched.c:__cfq_slice_expired
  - block/cfq-iosched.c:cfq_service_tree_add
  - block/cfq-iosched.c:cfq_service_tree_add
```
```
In block/blk-wbt.c (ffffffff81483ecd)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - block/blk-wbt.c:rwb_arm_timer
  - block/blk-wbt.c:perf_trace_wbt_step
  - block/blk-wbt.c:perf_trace_wbt_lat
  - block/blk-wbt.c:trace_event_raw_event_wbt_step
  - block/blk-wbt.c:trace_event_raw_event_wbt_lat
```
```
In lib/kstrtox.c (ffffffff81499bb8)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - lib/kstrtox.c:_parse_integer
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff8169d0dd)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:size_store
```
```
In drivers/nvdimm/badrange.c (ffffffff816a2371)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - drivers/nvdimm/badrange.c:__add_badblock_range
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81798f87)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/cpufreq/cpufreq.c (ffffffff817d6848)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:get_cpu_idle_time
  - drivers/cpufreq/cpufreq.c:get_cpu_idle_time
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff817dd01f)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:dbs_update
```
```
In drivers/cpuidle/governors/menu.c (ffffffff817e5950)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - drivers/cpuidle/governors/menu.c:menu_select
```
```
In drivers/devfreq/governor_simpleondemand.c (ffffffff818146fd)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - drivers/devfreq/governor_simpleondemand.c:devfreq_simple_ondemand_func
  - drivers/devfreq/governor_simpleondemand.c:devfreq_simple_ondemand_func
```
```
In net/ipv4/tcp.c (ffffffff818a29af)
Location: include/linux/math64.h:123
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff818ab196)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_synack_rtt_meas
  - net/ipv4/tcp_input.c:tcp_cwnd_reduction
  - net/ipv4/tcp_input.c:tcp_rcv_space_adjust
  - net/ipv4/tcp_input.c:tcp_init_buffer_space
```
```
In net/ipv4/tcp_output.c (ffffffff818b6a62)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_window_probe
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_established_options
```
```
In net/ipv4/tcp_timer.c (ffffffff818b6db2)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
```
```
In net/ipv4/tcp_ipv4.c (ffffffff818bc483)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/syncookies.c (ffffffff818ee9e9)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_init_timestamp
```
```
In net/ipv6/tcp_ipv6.c (ffffffff8193bb4c)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
```
```
In lib/vsprintf.c (ffffffff8198087f)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - lib/vsprintf.c:vsscanf
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
In arch/x86/kernel/cpu/mshyperv.c (ffffffff826e21b8)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
```
```
In kernel/sched/cputime.c (ffffffff810c3e99)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - kernel/sched/cputime.c:cputime_adjust
```
```
In kernel/sched/fair.c (ffffffff810cf173)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_group_capacity
  - kernel/sched/fair.c:attach_entity_load_avg
  - kernel/sched/fair.c:reweight_entity
  - kernel/sched/fair.c:reweight_entity
```
```
In kernel/sched/rt.c (ffffffff810d340e)
Location: include/linux/math64.h:123
Inline: True
```
```
In kernel/time/time.c (ffffffff811105c5)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - kernel/time/time.c:nsecs_to_jiffies
  - kernel/time/time.c:nsec_to_clock_t
  - kernel/time/time.c:jiffies_64_to_clock_t
  - kernel/time/time.c:clock_t_to_jiffies
  - kernel/time/time.c:jiffies_to_clock_t
```
```
In kernel/time/ntp.c (ffffffff811198b3)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - kernel/time/ntp.c:ntp_update_frequency
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811224f5)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff811631c8)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_summary
```
```
In kernel/taskstats.c (ffffffff8116ebca)
Location: include/linux/math64.h:123
Inline: True
```
```
In kernel/tsacct.c (ffffffff8116f407)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/tsacct.c:bacct_add_tsk
```
```
In kernel/trace/trace_hwlat.c (ffffffff8118cac5)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/trace/trace_hwlat.c:kthread_fn
```
```
In kernel/events/core.c (ffffffff811dbaef)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - kernel/events/core.c:perf_cpu_time_max_percent_handler
  - kernel/events/core.c:perf_proc_update_handler
```
```
In mm/page-writeback.c (ffffffff811fd598)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:wb_update_dirty_ratelimit
  - mm/page-writeback.c:wb_position_ratio
  - mm/page-writeback.c:wb_position_ratio
```
```
In mm/vmstat.c (ffffffff81215a24)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - mm/vmstat.c:unusable_show_print
  - mm/vmstat.c:__fragmentation_index
  - mm/vmstat.c:__fragmentation_index
```
```
In mm/slub.c (ffffffff8126920b)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - mm/slub.c:list_locations
```
```
In fs/ext4/extents_status.c (ffffffff813434d9)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
```
```
In fs/ext4/super.c (ffffffff81379d73)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_es_shrink
  - fs/ext4/super.c:trace_event_raw_event_ext4_es_shrink
```
```
In fs/jbd2/journal.c (ffffffff8139af34)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_seq_info_show
```
```
In security/keys/proc.c (ffffffff813ebb8f)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - security/keys/proc.c:proc_keys_show
  - security/keys/proc.c:proc_keys_show
  - security/keys/proc.c:proc_keys_show
  - security/keys/proc.c:proc_keys_show
```
```
In block/blk-sysfs.c (ffffffff81485f60)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_wb_lat_show
```
```
In block/blk-stat.c (ffffffff81493807)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - block/blk-stat.c:blk_stat_timer_fn
```
```
In block/partitions/efi.c (ffffffff814a2b45)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:find_valid_gpt
  - block/partitions/efi.c:read_lba
```
```
In block/cfq-iosched.c (ffffffff814ae855)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_target_latency_us_show
  - block/cfq-iosched.c:cfq_slice_async_us_show
  - block/cfq-iosched.c:cfq_slice_sync_us_show
  - block/cfq-iosched.c:cfq_group_idle_us_show
  - block/cfq-iosched.c:cfq_slice_idle_us_show
  - block/cfq-iosched.c:cfq_target_latency_show
  - block/cfq-iosched.c:cfq_slice_async_show
  - block/cfq-iosched.c:cfq_slice_sync_show
  - block/cfq-iosched.c:cfq_group_idle_show
  - block/cfq-iosched.c:cfq_slice_idle_show
  - block/cfq-iosched.c:cfq_fifo_expire_async_show
  - block/cfq-iosched.c:cfq_fifo_expire_sync_show
  - block/cfq-iosched.c:cfq_completed_request
  - block/cfq-iosched.c:__cfq_update_io_thinktime
  - block/cfq-iosched.c:cfq_dispatch_requests
  - block/cfq-iosched.c:cfq_dispatch_requests
  - block/cfq-iosched.c:__cfq_slice_expired
  - block/cfq-iosched.c:__cfq_slice_expired
  - block/cfq-iosched.c:cfq_service_tree_add
  - block/cfq-iosched.c:cfq_service_tree_add
```
```
In block/blk-wbt.c (ffffffff814b8ca9)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - block/blk-wbt.c:rwb_arm_timer
  - block/blk-wbt.c:perf_trace_wbt_step
  - block/blk-wbt.c:perf_trace_wbt_lat
  - block/blk-wbt.c:trace_event_raw_event_wbt_step
  - block/blk-wbt.c:trace_event_raw_event_wbt_lat
```
```
In lib/kstrtox.c (ffffffff814cee65)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - lib/kstrtox.c:_parse_integer
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff816d9dc7)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:size_store
```
```
In drivers/nvdimm/badrange.c (ffffffff816de4f5)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - drivers/nvdimm/badrange.c:__add_badblock_range
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff817dbcec)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/cpufreq/cpufreq.c (ffffffff8181f531)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:get_cpu_idle_time
  - drivers/cpufreq/cpufreq.c:get_cpu_idle_time
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff81825ca8)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:dbs_update
```
```
In drivers/cpuidle/governors/menu.c (ffffffff8182ec20)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - drivers/cpuidle/governors/menu.c:menu_select
```
```
In drivers/devfreq/governor_simpleondemand.c (ffffffff8185e5bc)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - drivers/devfreq/governor_simpleondemand.c:devfreq_simple_ondemand_func
  - drivers/devfreq/governor_simpleondemand.c:devfreq_simple_ondemand_func
```
```
In net/ipv4/tcp.c (ffffffff818f805b)
Location: include/linux/math64.h:123
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff819005d1)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_synack_rtt_meas
  - net/ipv4/tcp_input.c:tcp_cwnd_reduction
  - net/ipv4/tcp_input.c:tcp_rcv_space_adjust
  - net/ipv4/tcp_input.c:tcp_init_buffer_space
```
```
In net/ipv4/tcp_output.c (ffffffff8190c2a1)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_window_probe
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_established_options
```
```
In net/ipv4/tcp_timer.c (ffffffff8190c632)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81911e79)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/syncookies.c (ffffffff819452f9)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_init_timestamp
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81994db6)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
```
```
In net/xdp/xdp_umem.c (ffffffff819cd032)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_create
```
```
In lib/vsprintf.c (ffffffff819dc91d)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - lib/vsprintf.c:vsscanf
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
In arch/x86/kernel/cpu/mshyperv.c (ffffffff82898b06)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
```
```
In kernel/sched/cputime.c (ffffffff810cd159)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - kernel/sched/cputime.c:cputime_adjust
```
```
In kernel/sched/fair.c (ffffffff810d02de)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - kernel/sched/fair.c:attach_entity_load_avg
  - kernel/sched/fair.c:reweight_entity
  - kernel/sched/fair.c:reweight_entity
```
```
In kernel/sched/rt.c (ffffffff810dc7ae)
Location: include/linux/math64.h:123
Inline: True
```
```
In kernel/sched/pelt.c (ffffffff810e7880)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - kernel/sched/pelt.c:update_dl_rq_load_avg
  - kernel/sched/pelt.c:update_dl_rq_load_avg
  - kernel/sched/pelt.c:update_rt_rq_load_avg
  - kernel/sched/pelt.c:update_rt_rq_load_avg
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_blocked_se
  - kernel/sched/pelt.c:__update_load_avg_blocked_se
```
```
In kernel/sched/psi.c (ffffffff810ef224)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - kernel/sched/psi.c:update_stats
  - kernel/sched/psi.c:update_stats
  - kernel/sched/psi.c:update_stats
```
```
In kernel/time/time.c (ffffffff8111bbb5)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - kernel/time/time.c:nsecs_to_jiffies
  - kernel/time/time.c:nsec_to_clock_t
  - kernel/time/time.c:jiffies_64_to_clock_t
  - kernel/time/time.c:clock_t_to_jiffies
  - kernel/time/time.c:jiffies_to_clock_t
```
```
In kernel/time/ntp.c (ffffffff81124dc3)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - kernel/time/ntp.c:ntp_update_frequency
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8112dc06)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff81170128)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_summary
```
```
In kernel/taskstats.c (ffffffff8117c6ca)
Location: include/linux/math64.h:123
Inline: True
```
```
In kernel/tsacct.c (ffffffff8117cf07)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/tsacct.c:bacct_add_tsk
```
```
In kernel/trace/trace_hwlat.c (ffffffff8119a5d5)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/trace/trace_hwlat.c:kthread_fn
```
```
In kernel/events/core.c (ffffffff811ebeaf)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - kernel/events/core.c:perf_cpu_time_max_percent_handler
  - kernel/events/core.c:perf_proc_update_handler
```
```
In mm/page-writeback.c (ffffffff812100b5)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:wb_update_dirty_ratelimit
  - mm/page-writeback.c:wb_position_ratio
  - mm/page-writeback.c:wb_position_ratio
```
```
In mm/vmstat.c (ffffffff81228914)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - mm/vmstat.c:unusable_show_print
  - mm/vmstat.c:__fragmentation_index
  - mm/vmstat.c:__fragmentation_index
```
```
In mm/slub.c (ffffffff81278c23)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - mm/slub.c:list_locations
```
```
In fs/ext4/extents_status.c (ffffffff8135b0f9)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
```
```
In fs/ext4/super.c (ffffffff813926e3)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_es_shrink
  - fs/ext4/super.c:trace_event_raw_event_ext4_es_shrink
```
```
In fs/jbd2/journal.c (ffffffff813b3ca4)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_seq_info_show
```
```
In security/keys/proc.c (ffffffff8140679a)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - security/keys/proc.c:proc_keys_show
  - security/keys/proc.c:proc_keys_show
  - security/keys/proc.c:proc_keys_show
  - security/keys/proc.c:proc_keys_show
```
```
In block/blk-sysfs.c (ffffffff814a08d4)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_wb_lat_show
```
```
In block/blk-stat.c (ffffffff814ad867)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - block/blk-stat.c:blk_stat_timer_fn
```
```
In block/genhd.c (ffffffff814b1c58)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
```
```
In block/partition-generic.c (ffffffff814b31c4)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
```
```
In block/partitions/efi.c (ffffffff814bcd27)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:read_lba
```
```
In block/blk-wbt.c (ffffffff814cd05c)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - block/blk-wbt.c:rwb_arm_timer
  - block/blk-wbt.c:perf_trace_wbt_step
  - block/blk-wbt.c:perf_trace_wbt_lat
  - block/blk-wbt.c:trace_event_raw_event_wbt_step
  - block/blk-wbt.c:trace_event_raw_event_wbt_lat
```
```
In lib/kstrtox.c (ffffffff814e3775)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - lib/kstrtox.c:_parse_integer
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff816fbd64)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:size_store
```
```
In drivers/nvdimm/badrange.c (ffffffff817008b5)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - drivers/nvdimm/badrange.c:__add_badblock_range
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81803002)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/cpufreq/cpufreq.c (ffffffff8184b3d1)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:get_cpu_idle_time
  - drivers/cpufreq/cpufreq.c:get_cpu_idle_time
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff81851b88)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:dbs_update
```
```
In drivers/cpuidle/governors/menu.c (ffffffff8185ae60)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - drivers/cpuidle/governors/menu.c:menu_select
```
```
In drivers/devfreq/governor_simpleondemand.c (ffffffff8187dfbc)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - drivers/devfreq/governor_simpleondemand.c:devfreq_simple_ondemand_func
  - drivers/devfreq/governor_simpleondemand.c:devfreq_simple_ondemand_func
```
```
In net/ipv4/tcp.c (ffffffff819248a1)
Location: include/linux/math64.h:123
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff8192e729)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_synack_rtt_meas
  - net/ipv4/tcp_input.c:tcp_cwnd_reduction
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
```
In net/ipv4/tcp_output.c (ffffffff8193a57a)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_window_probe
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_established_options
```
```
In net/ipv4/tcp_timer.c (ffffffff8193bb9f)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81940643)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/tcp_rate.c (ffffffff819453f6)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp_rate.c:tcp_rate_skb_delivered
  - net/ipv4/tcp_rate.c:tcp_rate_skb_sent
```
```
In net/ipv4/tcp_recovery.c (ffffffff8194569b)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_detect_loss
```
```
In net/ipv4/syncookies.c (ffffffff81975692)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_init_timestamp
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819cb69b)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
```
```
In net/xdp/xdp_umem.c (ffffffff81a06282)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_create
```
```
In lib/vsprintf.c (ffffffff81a14e1c)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - lib/vsprintf.c:vsscanf
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
In arch/x86/kernel/cpu/mshyperv.c (ffffffff828b0709)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
```
```
In arch/x86/kernel/apic/apic.c (ffffffff828b4bba)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:calibrate_APIC_clock
```
```
In kernel/sched/cputime.c (ffffffff810d5549)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - kernel/sched/cputime.c:cputime_adjust
```
```
In kernel/sched/fair.c (ffffffff810e2b91)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/fair.c:attach_entity_load_avg
  - kernel/sched/fair.c:reweight_entity
  - kernel/sched/fair.c:reweight_entity
```
```
In kernel/sched/rt.c (ffffffff810e374d)
Location: include/linux/math64.h:123
Inline: True
```
```
In kernel/sched/pelt.c (ffffffff810ee79f)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - kernel/sched/pelt.c:update_dl_rq_load_avg
  - kernel/sched/pelt.c:update_dl_rq_load_avg
  - kernel/sched/pelt.c:update_rt_rq_load_avg
  - kernel/sched/pelt.c:update_rt_rq_load_avg
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_blocked_se
  - kernel/sched/pelt.c:__update_load_avg_blocked_se
```
```
In kernel/sched/psi.c (ffffffff810f613c)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_trigger_destroy
  - kernel/sched/psi.c:psi_poll_work
  - kernel/sched/psi.c:update_averages
  - kernel/sched/psi.c:update_averages
  - kernel/sched/psi.c:collect_percpu_times
```
```
In kernel/time/time.c (ffffffff811265f5)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - kernel/time/time.c:nsecs_to_jiffies
  - kernel/time/time.c:nsec_to_clock_t
  - kernel/time/time.c:jiffies_64_to_clock_t
  - kernel/time/time.c:clock_t_to_jiffies
  - kernel/time/time.c:jiffies_to_clock_t
```
```
In kernel/time/ntp.c (ffffffff8112f823)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - kernel/time/ntp.c:ntp_update_frequency
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8113853e)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff8117d347)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_summary
```
```
In kernel/taskstats.c (ffffffff8118956e)
Location: include/linux/math64.h:123
Inline: True
```
```
In kernel/tsacct.c (ffffffff81189dbe)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/tsacct.c:bacct_add_tsk
```
```
In kernel/trace/trace_hwlat.c (ffffffff811a8230)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/trace/trace_hwlat.c:kthread_fn
```
```
In kernel/bpf/verifier.c (ffffffff811e4686)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
```
```
In kernel/events/core.c (ffffffff81203857)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - kernel/events/core.c:perf_cpu_time_max_percent_handler
  - kernel/events/core.c:perf_proc_update_handler
```
```
In mm/page-writeback.c (ffffffff8121f75a)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:wb_update_dirty_ratelimit
  - mm/page-writeback.c:wb_position_ratio
  - mm/page-writeback.c:wb_position_ratio
```
```
In mm/vmstat.c (ffffffff81238625)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - mm/vmstat.c:unusable_show_print
  - mm/vmstat.c:__fragmentation_index
  - mm/vmstat.c:__fragmentation_index
```
```
In mm/slub.c (ffffffff81294d2e)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - mm/slub.c:list_locations
```
```
In fs/ext4/extents_status.c (ffffffff81384119)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
```
```
In fs/ext4/super.c (ffffffff813bc5a6)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_es_shrink
  - fs/ext4/super.c:trace_event_raw_event_ext4_es_shrink
```
```
In fs/jbd2/journal.c (ffffffff813de2ac)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_seq_info_show
```
```
In security/keys/proc.c (ffffffff814338e7)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - security/keys/proc.c:proc_keys_show
  - security/keys/proc.c:proc_keys_show
  - security/keys/proc.c:proc_keys_show
  - security/keys/proc.c:proc_keys_show
```
```
In block/blk-sysfs.c (ffffffff814ced4e)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_wb_lat_show
```
```
In block/blk-stat.c (ffffffff814dbaf3)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - block/blk-stat.c:blk_stat_timer_fn
```
```
In block/genhd.c (ffffffff814e0075)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
```
```
In block/partition-generic.c (ffffffff814e1771)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
```
```
In block/partitions/efi.c (ffffffff814eb3b3)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:read_lba
```
```
In block/blk-wbt.c (ffffffff814fb8cc)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - block/blk-wbt.c:rwb_arm_timer
  - block/blk-wbt.c:perf_trace_wbt_step
  - block/blk-wbt.c:perf_trace_wbt_lat
  - block/blk-wbt.c:trace_event_raw_event_wbt_step
  - block/blk-wbt.c:trace_event_raw_event_wbt_lat
```
```
In lib/kstrtox.c (ffffffff8150fb55)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - lib/kstrtox.c:_parse_integer
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff81735c81)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:__size_store
```
```
In drivers/nvdimm/badrange.c (ffffffff8173a735)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - drivers/nvdimm/badrange.c:__add_badblock_range
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81844417)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/cpufreq/cpufreq.c (ffffffff8188e455)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:get_cpu_idle_time
  - drivers/cpufreq/cpufreq.c:get_cpu_idle_time
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff818950c6)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:dbs_update
```
```
In drivers/cpuidle/governors/menu.c (ffffffff8189e809)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - drivers/cpuidle/governors/menu.c:menu_select
```
```
In drivers/devfreq/governor_simpleondemand.c (ffffffff818c861a)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - drivers/devfreq/governor_simpleondemand.c:devfreq_simple_ondemand_func
  - drivers/devfreq/governor_simpleondemand.c:devfreq_simple_ondemand_func
```
```
In net/ipv4/tcp.c (ffffffff81987d6b)
Location: include/linux/math64.h:123
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff8199706d)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_synack_rtt_meas
  - net/ipv4/tcp_input.c:tcp_cwnd_reduction
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
```
In net/ipv4/tcp_output.c (ffffffff8199e8e5)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_window_probe
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_established_options
```
```
In net/ipv4/tcp_timer.c (ffffffff8199f4de)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819a4b8c)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819a59f9)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
```
```
In net/ipv4/tcp_rate.c (ffffffff819a99f6)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp_rate.c:tcp_rate_skb_delivered
  - net/ipv4/tcp_rate.c:tcp_rate_skb_sent
```
```
In net/ipv4/tcp_recovery.c (ffffffff819a9ca0)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_detect_loss
```
```
In net/ipv4/syncookies.c (ffffffff819df1b2)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_init_timestamp
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a3a122)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
```
```
In net/xdp/xdp_umem.c (ffffffff81a75ba5)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_create
```
```
In lib/vsprintf.c (ffffffff81a8468a)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - lib/vsprintf.c:vsscanf
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
In arch/x86/kernel/cpu/mshyperv.c (ffffffff828b3b51)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
```
```
In arch/x86/kernel/apic/apic.c (ffffffff828b8013)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:calibrate_APIC_clock
```
```
In kernel/sched/cputime.c (ffffffff810dfb09)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - kernel/sched/cputime.c:cputime_adjust
```
```
In kernel/sched/fair.c (ffffffff810ed232)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/fair.c:attach_entity_load_avg
  - kernel/sched/fair.c:reweight_entity
  - kernel/sched/fair.c:reweight_entity
```
```
In kernel/sched/rt.c (ffffffff810eee1d)
Location: include/linux/math64.h:123
Inline: True
```
```
In kernel/sched/pelt.c (ffffffff810fa37f)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - kernel/sched/pelt.c:update_dl_rq_load_avg
  - kernel/sched/pelt.c:update_dl_rq_load_avg
  - kernel/sched/pelt.c:update_rt_rq_load_avg
  - kernel/sched/pelt.c:update_rt_rq_load_avg
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_blocked_se
  - kernel/sched/pelt.c:__update_load_avg_blocked_se
```
```
In kernel/sched/psi.c (ffffffff81101edc)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_trigger_destroy
  - kernel/sched/psi.c:update_averages
  - kernel/sched/psi.c:update_averages
  - kernel/sched/psi.c:collect_percpu_times
```
```
In kernel/time/time.c (ffffffff81132595)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - kernel/time/time.c:nsecs_to_jiffies
  - kernel/time/time.c:nsec_to_clock_t
  - kernel/time/time.c:jiffies_64_to_clock_t
  - kernel/time/time.c:clock_t_to_jiffies
  - kernel/time/time.c:jiffies_to_clock_t
```
```
In kernel/time/ntp.c (ffffffff8113b763)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - kernel/time/ntp.c:ntp_update_frequency
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff811891c7)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_summary
```
```
In kernel/taskstats.c (ffffffff811954ae)
Location: include/linux/math64.h:123
Inline: True
```
```
In kernel/tsacct.c (ffffffff81195cce)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/tsacct.c:bacct_add_tsk
```
```
In kernel/trace/trace_hwlat.c (ffffffff811b3a30)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/trace/trace_hwlat.c:kthread_fn
```
```
In kernel/bpf/verifier.c (ffffffff811f0ee6)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
```
```
In kernel/events/core.c (ffffffff81210447)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - kernel/events/core.c:perf_cpu_time_max_percent_handler
  - kernel/events/core.c:perf_proc_update_handler
```
```
In mm/page-writeback.c (ffffffff8122d202)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:wb_update_dirty_ratelimit
  - mm/page-writeback.c:wb_position_ratio
  - mm/page-writeback.c:wb_position_ratio
```
```
In mm/vmstat.c (ffffffff81246915)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - mm/vmstat.c:unusable_show_print
  - mm/vmstat.c:__fragmentation_index
  - mm/vmstat.c:__fragmentation_index
```
```
In mm/slub.c (ffffffff812a4b09)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - mm/slub.c:list_locations
```
```
In fs/ext4/extents_status.c (ffffffff8139cc94)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
```
```
In fs/ext4/super.c (ffffffff813d5876)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_es_shrink
  - fs/ext4/super.c:trace_event_raw_event_ext4_es_shrink
```
```
In fs/jbd2/journal.c (ffffffff813f82fc)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_seq_info_show
```
```
In security/keys/proc.c (ffffffff8144d657)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - security/keys/proc.c:proc_keys_show
  - security/keys/proc.c:proc_keys_show
  - security/keys/proc.c:proc_keys_show
  - security/keys/proc.c:proc_keys_show
```
```
In block/blk-sysfs.c (ffffffff814e80be)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_wb_lat_show
```
```
In block/blk-stat.c (ffffffff814f4f23)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - block/blk-stat.c:blk_stat_timer_fn
```
```
In block/genhd.c (ffffffff814f94a5)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
```
```
In block/partition-generic.c (ffffffff814fab21)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
```
```
In block/partitions/efi.c (ffffffff81504779)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:read_lba
```
```
In block/blk-wbt.c (ffffffff8151981c)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - block/blk-wbt.c:rwb_arm_timer
  - block/blk-wbt.c:perf_trace_wbt_step
  - block/blk-wbt.c:perf_trace_wbt_lat
  - block/blk-wbt.c:trace_event_raw_event_wbt_step
  - block/blk-wbt.c:trace_event_raw_event_wbt_lat
```
```
In lib/kstrtox.c (ffffffff8152da55)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - lib/kstrtox.c:_parse_integer
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff81759a0a)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:__size_store
```
```
In drivers/nvdimm/badrange.c (ffffffff8175e405)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - drivers/nvdimm/badrange.c:__add_badblock_range
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81875c35)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/cpufreq/cpufreq.c (ffffffff818c05e5)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:get_cpu_idle_time
  - drivers/cpufreq/cpufreq.c:get_cpu_idle_time
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff818c70e6)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:dbs_update
```
```
In drivers/cpuidle/governors/menu.c (ffffffff818d0c13)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - drivers/cpuidle/governors/menu.c:menu_select
```
```
In drivers/devfreq/governor_simpleondemand.c (ffffffff818faa6a)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - drivers/devfreq/governor_simpleondemand.c:devfreq_simple_ondemand_func
  - drivers/devfreq/governor_simpleondemand.c:devfreq_simple_ondemand_func
```
```
In net/ipv4/tcp.c (ffffffff819be303)
Location: include/linux/math64.h:123
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff819cdbed)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_synack_rtt_meas
  - net/ipv4/tcp_input.c:tcp_cwnd_reduction
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
```
In net/ipv4/tcp_output.c (ffffffff819d53f5)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_window_probe
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_established_options
```
```
In net/ipv4/tcp_timer.c (ffffffff819d608e)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819db88c)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819dc7b9)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
```
```
In net/ipv4/tcp_rate.c (ffffffff819e06b6)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp_rate.c:tcp_rate_skb_delivered
  - net/ipv4/tcp_rate.c:tcp_rate_skb_sent
```
```
In net/ipv4/tcp_recovery.c (ffffffff819e0960)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_detect_loss
```
```
In net/ipv4/syncookies.c (ffffffff81a16242)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_init_timestamp
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a70cc3)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
```
```
In net/xdp/xdp_umem.c (ffffffff81aaca3b)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_create
```
```
In lib/vsprintf.c (ffffffff81abb8ee)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - lib/vsprintf.c:vsscanf
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
In arch/x86/kernel/cpu/mshyperv.c (ffffffff82cd8bce)
Location: include/linux/math64.h:124
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
```
```
In arch/x86/kernel/smpboot.c (ffffffff8106a340)
Location: include/linux/math64.h:124
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:intel_set_max_freq_ratio
```
```
In arch/x86/kernel/apic/apic.c (ffffffff82cdd208)
Location: include/linux/math64.h:124
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:calibrate_APIC_clock
```
```
In kernel/sched/cputime.c (ffffffff810e7e95)
Location: include/linux/math64.h:124
Inline: True
Inline callers:
  - kernel/sched/cputime.c:cputime_adjust
```
```
In kernel/sched/fair.c (ffffffff810e9f53)
Location: include/linux/math64.h:124
Inline: True
Inline callers:
  - kernel/sched/fair.c:select_idle_cpu
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/fair.c:attach_entity_load_avg
  - kernel/sched/fair.c:reweight_entity
```
```
In kernel/sched/rt.c (ffffffff810f85a9)
Location: include/linux/math64.h:124
Inline: True
Inline callers:
  - kernel/sched/rt.c:do_balance_runtime
```
```
In kernel/sched/pelt.c (ffffffff81104665)
Location: include/linux/math64.h:124
Inline: True
Inline callers:
  - kernel/sched/pelt.c:update_dl_rq_load_avg
  - kernel/sched/pelt.c:update_dl_rq_load_avg
  - kernel/sched/pelt.c:update_rt_rq_load_avg
  - kernel/sched/pelt.c:update_rt_rq_load_avg
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_blocked_se
  - kernel/sched/pelt.c:__update_load_avg_blocked_se
```
```
In kernel/sched/psi.c (ffffffff8110c8fc)
Location: include/linux/math64.h:124
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_trigger_destroy
  - kernel/sched/psi.c:update_averages
  - kernel/sched/psi.c:update_averages
  - kernel/sched/psi.c:collect_percpu_times
```
```
In kernel/time/time.c (ffffffff81142cd5)
Location: include/linux/math64.h:124
Inline: True
Inline callers:
  - kernel/time/time.c:nsec_to_clock_t
  - kernel/time/time.c:jiffies_64_to_clock_t
  - kernel/time/time.c:clock_t_to_jiffies
  - kernel/time/time.c:jiffies_to_clock_t
```
```
In kernel/time/ntp.c (ffffffff8114a7b3)
Location: include/linux/math64.h:124
Inline: True
Inline callers:
  - kernel/time/ntp.c:ntp_update_frequency
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff8119d257)
Location: include/linux/math64.h:124
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_summary
```
```
In kernel/taskstats.c (ffffffff811aa3e9)
Location: include/linux/math64.h:124
Inline: True
Inline callers:
  - kernel/taskstats.c:fill_stats_for_tgid
  - kernel/taskstats.c:fill_stats_for_tgid
```
```
In kernel/tsacct.c (ffffffff811aad99)
Location: include/linux/math64.h:124
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/tsacct.c:bacct_add_tsk
```
```
In kernel/trace/trace_hwlat.c (ffffffff811cc129)
Location: include/linux/math64.h:124
Inline: True
```
```
In kernel/bpf/verifier.c (ffffffff8121365a)
Location: include/linux/math64.h:124
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
```
```
In kernel/events/core.c (ffffffff8123c647)
Location: include/linux/math64.h:124
Inline: True
Inline callers:
  - kernel/events/core.c:perf_cpu_time_max_percent_handler
  - kernel/events/core.c:perf_proc_update_handler
```
```
In mm/page-writeback.c (ffffffff8125ad6e)
Location: include/linux/math64.h:124
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:wb_update_dirty_ratelimit
  - mm/page-writeback.c:wb_position_ratio
  - mm/page-writeback.c:wb_position_ratio
```
```
In mm/vmstat.c (ffffffff81274d27)
Location: include/linux/math64.h:124
Inline: True
Inline callers:
  - mm/vmstat.c:unusable_show_print
  - mm/vmstat.c:__fragmentation_index
  - mm/vmstat.c:__fragmentation_index
```
```
In mm/slub.c (ffffffff812d92b1)
Location: include/linux/math64.h:124
Inline: True
Inline callers:
  - mm/slub.c:list_locations
```
```
In fs/ext4/extents_status.c (ffffffff813e83d4)
Location: include/linux/math64.h:124
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
```
```
In fs/ext4/super.c (ffffffff81421f6d)
Location: include/linux/math64.h:124
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_es_shrink
  - fs/ext4/super.c:trace_event_raw_event_ext4_es_shrink
```
```
In fs/jbd2/journal.c (ffffffff8144564c)
Location: include/linux/math64.h:124
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_seq_info_show
```
```
In security/keys/proc.c (ffffffff8149f2da)
Location: include/linux/math64.h:124
Inline: True
Inline callers:
  - security/keys/proc.c:proc_keys_show
  - security/keys/proc.c:proc_keys_show
  - security/keys/proc.c:proc_keys_show
  - security/keys/proc.c:proc_keys_show
```
```
In block/blk-sysfs.c (ffffffff81546fce)
Location: include/linux/math64.h:124
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_wb_lat_show
```
```
In block/blk-stat.c (ffffffff81555963)
Location: include/linux/math64.h:124
Inline: True
Inline callers:
  - block/blk-stat.c:blk_stat_timer_fn
```
```
In block/genhd.c (ffffffff81559f77)
Location: include/linux/math64.h:124
Inline: True
Inline callers:
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:part_stat_show
  - block/genhd.c:part_stat_show
  - block/genhd.c:part_stat_show
  - block/genhd.c:part_stat_show
  - block/genhd.c:part_stat_show
```
```
In block/partitions/efi.c (ffffffff815651c8)
Location: include/linux/math64.h:124
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:read_lba
```
```
In block/blk-wbt.c (ffffffff81579dcf)
Location: include/linux/math64.h:124
Inline: True
Inline callers:
  - block/blk-wbt.c:rwb_arm_timer
  - block/blk-wbt.c:perf_trace_wbt_step
  - block/blk-wbt.c:perf_trace_wbt_lat
  - block/blk-wbt.c:trace_event_raw_event_wbt_step
  - block/blk-wbt.c:trace_event_raw_event_wbt_lat
```
```
In lib/kstrtox.c (ffffffff815917f8)
Location: include/linux/math64.h:124
Inline: True
Inline callers:
  - lib/kstrtox.c:_parse_integer
```
```
In lib/zstd/fse_compress.c (ffffffff815acd82)
Location: include/linux/math64.h:124
Inline: True
Inline callers:
  - lib/zstd/fse_compress.c:FSE_normalizeCount
  - lib/zstd/fse_compress.c:FSE_normalizeCount
```
```
In lib/vsprintf.c (ffffffff815f743b)
Location: include/linux/math64.h:124
Inline: True
Inline callers:
  - lib/vsprintf.c:vsscanf
```
```
In drivers/idle/intel_idle.c (ffffffff82d0eb9a)
Location: include/linux/math64.h:124
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:irtl_2_usec
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff8181990c)
Location: include/linux/math64.h:124
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:__size_store
```
```
In drivers/nvdimm/badrange.c (ffffffff8181df05)
Location: include/linux/math64.h:124
Inline: True
Inline callers:
  - drivers/nvdimm/badrange.c:__add_badblock_range
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff8194a557)
Location: include/linux/math64.h:124
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/cpufreq/cpufreq.c (ffffffff8199256f)
Location: include/linux/math64.h:124
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:get_cpu_idle_time
  - drivers/cpufreq/cpufreq.c:get_cpu_idle_time
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff81999324)
Location: include/linux/math64.h:124
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:dbs_update
```
```
In drivers/cpuidle/governors/menu.c (ffffffff819a3516)
Location: include/linux/math64.h:124
Inline: True
Inline callers:
  - drivers/cpuidle/governors/menu.c:menu_select
  - drivers/cpuidle/governors/menu.c:get_typical_interval
```
```
In drivers/devfreq/governor_simpleondemand.c (ffffffff819d157b)
Location: include/linux/math64.h:124
Inline: True
Inline callers:
  - drivers/devfreq/governor_simpleondemand.c:devfreq_simple_ondemand_func
  - drivers/devfreq/governor_simpleondemand.c:devfreq_simple_ondemand_func
```
```
In net/ipv4/tcp.c (ffffffff81aaa7c8)
Location: include/linux/math64.h:124
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff81ab9db3)
Location: include/linux/math64.h:124
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_synack_rtt_meas
  - net/ipv4/tcp_input.c:tcp_ack_update_rtt
  - net/ipv4/tcp_input.c:tcp_cwnd_reduction
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
```
In net/ipv4/tcp_output.c (ffffffff81ac1d35)
Location: include/linux/math64.h:124
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_window_probe
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_established_options
  - net/ipv4/tcp_output.c:tcp_synack_options
  - net/ipv4/tcp_output.c:tcp_syn_options
```
```
In net/ipv4/tcp_timer.c (ffffffff81ac2f9c)
Location: include/linux/math64.h:124
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ac8960)
Location: include/linux/math64.h:124
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ac9889)
Location: include/linux/math64.h:124
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
```
```
In net/ipv4/tcp_rate.c (ffffffff81acdc86)
Location: include/linux/math64.h:124
Inline: True
Inline callers:
  - net/ipv4/tcp_rate.c:tcp_rate_skb_delivered
  - net/ipv4/tcp_rate.c:tcp_rate_skb_sent
```
```
In net/ipv4/tcp_recovery.c (ffffffff81acdede)
Location: include/linux/math64.h:124
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_detect_loss
```
```
In net/ipv4/syncookies.c (ffffffff81b07255)
Location: include/linux/math64.h:124
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_init_timestamp
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b6a4b7)
Location: include/linux/math64.h:124
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
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
In arch/x86/kernel/cpu/mshyperv.c (ffffffff82fc4fec)
Location: include/linux/math64.h:124
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
```
```
In arch/x86/kernel/smpboot.c (ffffffff8106b50a)
Location: include/linux/math64.h:124
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:amd_set_max_freq_ratio
  - arch/x86/kernel/smpboot.c:intel_set_max_freq_ratio
```
```
In arch/x86/kernel/apic/apic.c (ffffffff82fc959c)
Location: include/linux/math64.h:124
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:calibrate_APIC_clock
```
```
In kernel/sched/fair.c (ffffffff810e7cb3)
Location: include/linux/math64.h:124
Inline: True
Inline callers:
  - kernel/sched/fair.c:select_idle_cpu
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/fair.c:attach_entity_load_avg
  - kernel/sched/fair.c:reweight_entity
```
```
In kernel/sched/rt.c (ffffffff810f67b9)
Location: include/linux/math64.h:124
Inline: True
Inline callers:
  - kernel/sched/rt.c:do_balance_runtime
```
```
In kernel/sched/pelt.c (ffffffff81102ceb)
Location: include/linux/math64.h:124
Inline: True
Inline callers:
  - kernel/sched/pelt.c:update_dl_rq_load_avg
  - kernel/sched/pelt.c:update_dl_rq_load_avg
  - kernel/sched/pelt.c:update_rt_rq_load_avg
  - kernel/sched/pelt.c:update_rt_rq_load_avg
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_blocked_se
  - kernel/sched/pelt.c:__update_load_avg_blocked_se
```
```
In kernel/sched/psi.c (ffffffff81109b1c)
Location: include/linux/math64.h:124
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_trigger_destroy
  - kernel/sched/psi.c:update_averages
  - kernel/sched/psi.c:update_averages
  - kernel/sched/psi.c:collect_percpu_times
```
```
In kernel/time/time.c (ffffffff8113eee5)
Location: include/linux/math64.h:124
Inline: True
Inline callers:
  - kernel/time/time.c:nsec_to_clock_t
  - kernel/time/time.c:jiffies_64_to_clock_t
  - kernel/time/time.c:clock_t_to_jiffies
  - kernel/time/time.c:jiffies_to_clock_t
```
```
In kernel/time/ntp.c (ffffffff81146c73)
Location: include/linux/math64.h:124
Inline: True
Inline callers:
  - kernel/time/ntp.c:ntp_update_frequency
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff8119a297)
Location: include/linux/math64.h:124
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_summary
```
```
In kernel/taskstats.c (ffffffff811a7989)
Location: include/linux/math64.h:124
Inline: True
Inline callers:
  - kernel/taskstats.c:fill_stats_for_tgid
  - kernel/taskstats.c:fill_stats_for_tgid
```
```
In kernel/tsacct.c (ffffffff811a8349)
Location: include/linux/math64.h:124
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/tsacct.c:bacct_add_tsk
```
```
In kernel/trace/trace_hwlat.c (ffffffff811c9779)
Location: include/linux/math64.h:124
Inline: True
```
```
In kernel/bpf/verifier.c (ffffffff81214e72)
Location: include/linux/math64.h:124
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
```
```
In kernel/events/core.c (ffffffff812468e7)
Location: include/linux/math64.h:124
Inline: True
Inline callers:
  - kernel/events/core.c:perf_cpu_time_max_percent_handler
  - kernel/events/core.c:perf_proc_update_handler
```
```
In mm/page-writeback.c (ffffffff81264f02)
Location: include/linux/math64.h:124
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:wb_update_dirty_ratelimit
  - mm/page-writeback.c:wb_position_ratio
  - mm/page-writeback.c:wb_position_ratio
```
```
In mm/vmstat.c (ffffffff8127f577)
Location: include/linux/math64.h:124
Inline: True
Inline callers:
  - mm/vmstat.c:unusable_show_print
  - mm/vmstat.c:extfrag_for_order
  - mm/vmstat.c:__fragmentation_index
  - mm/vmstat.c:__fragmentation_index
```
```
In mm/slub.c (ffffffff812e48a8)
Location: include/linux/math64.h:124
Inline: True
Inline callers:
  - mm/slub.c:list_locations
```
```
In fs/ext4/extents_status.c (ffffffff813fa684)
Location: include/linux/math64.h:124
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
```
```
In fs/ext4/super.c (ffffffff8143860d)
Location: include/linux/math64.h:124
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_es_shrink
  - fs/ext4/super.c:trace_event_raw_event_ext4_es_shrink
```
```
In fs/ext4/fast_commit.c (ffffffff81457548)
Location: include/linux/math64.h:124
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_info_show
```
```
In fs/jbd2/journal.c (ffffffff81461e1c)
Location: include/linux/math64.h:124
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_seq_info_show
```
```
In security/keys/proc.c (ffffffff814bcd0a)
Location: include/linux/math64.h:124
Inline: True
Inline callers:
  - security/keys/proc.c:proc_keys_show
  - security/keys/proc.c:proc_keys_show
  - security/keys/proc.c:proc_keys_show
  - security/keys/proc.c:proc_keys_show
```
```
In block/blk-sysfs.c (ffffffff81562cbe)
Location: include/linux/math64.h:124
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_wb_lat_show
```
```
In block/blk-stat.c (ffffffff815721b3)
Location: include/linux/math64.h:124
Inline: True
Inline callers:
  - block/blk-stat.c:blk_stat_timer_fn
```
```
In block/genhd.c (ffffffff81576736)
Location: include/linux/math64.h:124
Inline: True
Inline callers:
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:part_stat_show
  - block/genhd.c:part_stat_show
  - block/genhd.c:part_stat_show
  - block/genhd.c:part_stat_show
  - block/genhd.c:part_stat_show
```
```
In block/partitions/efi.c (ffffffff815802c2)
Location: include/linux/math64.h:124
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:read_lba
```
```
In block/blk-iocost.c (ffffffff8158d884)
Location: include/linux/math64.h:124
Inline: True
Inline callers:
  - block/blk-iocost.c:transfer_surpluses
  - block/blk-iocost.c:iocg_kick_delay
```
```
In block/blk-wbt.c (ffffffff81596ce4)
Location: include/linux/math64.h:124
Inline: True
Inline callers:
  - block/blk-wbt.c:rwb_arm_timer
  - block/blk-wbt.c:perf_trace_wbt_step
  - block/blk-wbt.c:perf_trace_wbt_lat
  - block/blk-wbt.c:trace_event_raw_event_wbt_step
  - block/blk-wbt.c:trace_event_raw_event_wbt_lat
```
```
In lib/kstrtox.c (ffffffff815ae338)
Location: include/linux/math64.h:124
Inline: True
Inline callers:
  - lib/kstrtox.c:_parse_integer
```
```
In lib/zstd/fse_compress.c (ffffffff815c88c7)
Location: include/linux/math64.h:124
Inline: True
Inline callers:
  - lib/zstd/fse_compress.c:FSE_normalizeCount
  - lib/zstd/fse_compress.c:FSE_normalizeCount
```
```
In lib/vsprintf.c (ffffffff8161b866)
Location: include/linux/math64.h:124
Inline: True
Inline callers:
  - lib/vsprintf.c:vsscanf
```
```
In drivers/idle/intel_idle.c (ffffffff82ffc5a4)
Location: include/linux/math64.h:124
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:irtl_2_usec
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff81828a2c)
Location: include/linux/math64.h:124
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:__size_store
```
```
In drivers/nvdimm/badrange.c (ffffffff8182ce85)
Location: include/linux/math64.h:124
Inline: True
Inline callers:
  - drivers/nvdimm/badrange.c:__add_badblock_range
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff819500e7)
Location: include/linux/math64.h:124
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/cpufreq/cpufreq.c (ffffffff8199577f)
Location: include/linux/math64.h:124
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:get_cpu_idle_time
  - drivers/cpufreq/cpufreq.c:get_cpu_idle_time
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff8199c404)
Location: include/linux/math64.h:124
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:dbs_update
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff8199d1c6)
Location: include/linux/math64.h:124
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:get_max_boost_ratio
```
```
In drivers/cpuidle/governors/menu.c (ffffffff819a64f6)
Location: include/linux/math64.h:124
Inline: True
Inline callers:
  - drivers/cpuidle/governors/menu.c:menu_select
  - drivers/cpuidle/governors/menu.c:get_typical_interval
```
```
In drivers/devfreq/governor_simpleondemand.c (ffffffff819d11db)
Location: include/linux/math64.h:124
Inline: True
Inline callers:
  - drivers/devfreq/governor_simpleondemand.c:devfreq_simple_ondemand_func
  - drivers/devfreq/governor_simpleondemand.c:devfreq_simple_ondemand_func
```
```
In net/sched/cls_api.c (ffffffff81a7ab2a)
Location: include/linux/math64.h:124
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff81ab77aa)
Location: include/linux/math64.h:124
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff81ac51f3)
Location: include/linux/math64.h:124
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_synack_rtt_meas
  - net/ipv4/tcp_input.c:tcp_ack_update_rtt
  - net/ipv4/tcp_input.c:tcp_cwnd_reduction
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
```
In net/ipv4/tcp_output.c (ffffffff81acd7a5)
Location: include/linux/math64.h:124
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_window_probe
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_established_options
  - net/ipv4/tcp_output.c:tcp_synack_options
  - net/ipv4/tcp_output.c:tcp_syn_options
```
```
In net/ipv4/tcp_timer.c (ffffffff81acea1c)
Location: include/linux/math64.h:124
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ad4900)
Location: include/linux/math64.h:124
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ad57c9)
Location: include/linux/math64.h:124
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
```
```
In net/ipv4/tcp_rate.c (ffffffff81ad9ce6)
Location: include/linux/math64.h:124
Inline: True
Inline callers:
  - net/ipv4/tcp_rate.c:tcp_rate_skb_delivered
  - net/ipv4/tcp_rate.c:tcp_rate_skb_sent
```
```
In net/ipv4/tcp_recovery.c (ffffffff81ad9f40)
Location: include/linux/math64.h:124
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_detect_loss
```
```
In net/ipv4/syncookies.c (ffffffff81b15628)
Location: include/linux/math64.h:124
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_init_timestamp
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b78fae)
Location: include/linux/math64.h:124
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
```
```
In net/mptcp/protocol.c (ffffffff81bba64c)
Location: include/linux/math64.h:124
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_rcv_space_adjust
  - net/mptcp/protocol.c:mptcp_subflow_get_send
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
In arch/x86/kernel/cpu/mshyperv.c (ffffffff831cf8ec)
Location: include/linux/math64.h:124
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
```
```
In arch/x86/kernel/smpboot.c (ffffffff8106ca30)
Location: include/linux/math64.h:124
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:intel_set_max_freq_ratio
```
```
In arch/x86/kernel/apic/apic.c (ffffffff831d3df7)
Location: include/linux/math64.h:124
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:calibrate_APIC_clock
```
```
In kernel/sched/fair.c (ffffffff810ebdf2)
Location: include/linux/math64.h:124
Inline: True
Inline callers:
  - kernel/sched/fair.c:select_idle_cpu
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/fair.c:attach_entity_load_avg
  - kernel/sched/fair.c:reweight_entity
```
```
In kernel/sched/rt.c (ffffffff810f8b8e)
Location: include/linux/math64.h:124
Inline: True
```
```
In kernel/sched/pelt.c (ffffffff81105030)
Location: include/linux/math64.h:124
Inline: True
Inline callers:
  - kernel/sched/pelt.c:update_dl_rq_load_avg
  - kernel/sched/pelt.c:update_dl_rq_load_avg
  - kernel/sched/pelt.c:update_rt_rq_load_avg
  - kernel/sched/pelt.c:update_rt_rq_load_avg
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_blocked_se
  - kernel/sched/pelt.c:__update_load_avg_blocked_se
```
```
In kernel/sched/psi.c (ffffffff8110b83c)
Location: include/linux/math64.h:124
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_trigger_destroy
  - kernel/sched/psi.c:update_averages
  - kernel/sched/psi.c:update_averages
  - kernel/sched/psi.c:collect_percpu_times
```
```
In kernel/time/time.c (ffffffff81140115)
Location: include/linux/math64.h:124
Inline: True
Inline callers:
  - kernel/time/time.c:nsec_to_clock_t
  - kernel/time/time.c:jiffies_64_to_clock_t
  - kernel/time/time.c:clock_t_to_jiffies
  - kernel/time/time.c:jiffies_to_clock_t
```
```
In kernel/time/ntp.c (ffffffff81147ddd)
Location: include/linux/math64.h:124
Inline: True
Inline callers:
  - kernel/time/ntp.c:ntp_update_frequency
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff8119b0c7)
Location: include/linux/math64.h:124
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_summary
```
```
In kernel/taskstats.c (ffffffff811a8369)
Location: include/linux/math64.h:124
Inline: True
Inline callers:
  - kernel/taskstats.c:fill_stats_for_tgid
  - kernel/taskstats.c:fill_stats_for_tgid
```
```
In kernel/tsacct.c (ffffffff811a8ec9)
Location: include/linux/math64.h:124
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/tsacct.c:bacct_add_tsk
```
```
In kernel/trace/trace_hwlat.c (ffffffff811caba4)
Location: include/linux/math64.h:124
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/trace/trace_hwlat.c:kthread_fn
```
```
In kernel/bpf/verifier.c (ffffffff812175ff)
Location: include/linux/math64.h:124
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
```
```
In kernel/events/core.c (ffffffff8124a66c)
Location: include/linux/math64.h:124
Inline: True
Inline callers:
  - kernel/events/core.c:perf_cpu_time_max_percent_handler
  - kernel/events/core.c:perf_proc_update_handler
```
```
In mm/page-writeback.c (ffffffff81269138)
Location: include/linux/math64.h:124
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:wb_update_dirty_ratelimit
  - mm/page-writeback.c:wb_position_ratio
  - mm/page-writeback.c:wb_position_ratio
```
```
In mm/vmstat.c (ffffffff812846e7)
Location: include/linux/math64.h:124
Inline: True
Inline callers:
  - mm/vmstat.c:unusable_show_print
  - mm/vmstat.c:extfrag_for_order
  - mm/vmstat.c:__fragmentation_index
  - mm/vmstat.c:__fragmentation_index
```
```
In mm/slub.c (ffffffff812ec120)
Location: include/linux/math64.h:124
Inline: True
Inline callers:
  - mm/slub.c:list_locations
```
```
In fs/ext4/extents_status.c (ffffffff81400a39)
Location: include/linux/math64.h:124
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
```
```
In fs/ext4/super.c (ffffffff8143e7bd)
Location: include/linux/math64.h:124
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_es_shrink
  - fs/ext4/super.c:trace_event_raw_event_ext4_es_shrink
```
```
In fs/ext4/fast_commit.c (ffffffff8145ced8)
Location: include/linux/math64.h:124
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_info_show
```
```
In fs/jbd2/journal.c (ffffffff814674c9)
Location: include/linux/math64.h:124
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_seq_info_show
```
```
In security/keys/proc.c (ffffffff814c2baa)
Location: include/linux/math64.h:124
Inline: True
Inline callers:
  - security/keys/proc.c:proc_keys_show
  - security/keys/proc.c:proc_keys_show
  - security/keys/proc.c:proc_keys_show
  - security/keys/proc.c:proc_keys_show
```
```
In block/blk-sysfs.c (ffffffff8156b46e)
Location: include/linux/math64.h:124
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_wb_lat_show
```
```
In block/blk-stat.c (ffffffff8157a1d7)
Location: include/linux/math64.h:124
Inline: True
Inline callers:
  - block/blk-stat.c:blk_stat_timer_fn
```
```
In block/genhd.c (ffffffff8157e49f)
Location: include/linux/math64.h:124
Inline: True
Inline callers:
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:part_stat_show
  - block/genhd.c:part_stat_show
  - block/genhd.c:part_stat_show
  - block/genhd.c:part_stat_show
  - block/genhd.c:part_stat_show
```
```
In block/partitions/efi.c (ffffffff81587e3a)
Location: include/linux/math64.h:124
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:read_lba
```
```
In block/blk-iocost.c (ffffffff81594034)
Location: include/linux/math64.h:124
Inline: True
Inline callers:
  - block/blk-iocost.c:transfer_surpluses
  - block/blk-iocost.c:iocg_kick_delay
```
```
In block/blk-wbt.c (ffffffff8159db25)
Location: include/linux/math64.h:124
Inline: True
Inline callers:
  - block/blk-wbt.c:rwb_arm_timer
  - block/blk-wbt.c:perf_trace_wbt_step
  - block/blk-wbt.c:perf_trace_wbt_lat
  - block/blk-wbt.c:trace_event_raw_event_wbt_step
  - block/blk-wbt.c:trace_event_raw_event_wbt_lat
```
```
In lib/kstrtox.c (ffffffff815b8e79)
Location: include/linux/math64.h:124
Inline: True
Inline callers:
  - lib/kstrtox.c:_kstrtoull
```
```
In drivers/idle/intel_idle.c (ffffffff832073aa)
Location: include/linux/math64.h:124
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:irtl_2_usec
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff8180bc4c)
Location: include/linux/math64.h:124
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:__size_store
```
```
In drivers/nvdimm/badrange.c (ffffffff818101d5)
Location: include/linux/math64.h:124
Inline: True
Inline callers:
  - drivers/nvdimm/badrange.c:__add_badblock_range
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81933f99)
Location: include/linux/math64.h:124
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/cpufreq/cpufreq.c (ffffffff8197a5ef)
Location: include/linux/math64.h:124
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:get_cpu_idle_time
  - drivers/cpufreq/cpufreq.c:get_cpu_idle_time
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff819810d3)
Location: include/linux/math64.h:124
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:dbs_update
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81982b64)
Location: include/linux/math64.h:124
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
```
```
In drivers/cpuidle/governors/menu.c (ffffffff8198af88)
Location: include/linux/math64.h:124
Inline: True
Inline callers:
  - drivers/cpuidle/governors/menu.c:menu_select
  - drivers/cpuidle/governors/menu.c:menu_select
```
```
In drivers/devfreq/governor_simpleondemand.c (ffffffff819b6450)
Location: include/linux/math64.h:124
Inline: True
Inline callers:
  - drivers/devfreq/governor_simpleondemand.c:devfreq_simple_ondemand_func
  - drivers/devfreq/governor_simpleondemand.c:devfreq_simple_ondemand_func
```
```
In net/sched/cls_api.c (ffffffff81a608b4)
Location: include/linux/math64.h:124
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff81aa29a8)
Location: include/linux/math64.h:124
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff81ab042a)
Location: include/linux/math64.h:124
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_synack_rtt_meas
  - net/ipv4/tcp_input.c:tcp_ack_update_rtt
  - net/ipv4/tcp_input.c:tcp_cwnd_reduction
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
```
In net/ipv4/tcp_output.c (ffffffff81ab8965)
Location: include/linux/math64.h:124
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_window_probe
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_established_options
  - net/ipv4/tcp_output.c:tcp_synack_options
  - net/ipv4/tcp_output.c:tcp_syn_options
```
```
In net/ipv4/tcp_timer.c (ffffffff81ab9bbc)
Location: include/linux/math64.h:124
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81abf9b6)
Location: include/linux/math64.h:124
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ac0834)
Location: include/linux/math64.h:124
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
```
```
In net/ipv4/tcp_rate.c (ffffffff81ac4d39)
Location: include/linux/math64.h:124
Inline: True
Inline callers:
  - net/ipv4/tcp_rate.c:tcp_rate_skb_delivered
  - net/ipv4/tcp_rate.c:tcp_rate_skb_sent
```
```
In net/ipv4/tcp_recovery.c (ffffffff81ac4fa6)
Location: include/linux/math64.h:124
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_detect_loss
```
```
In net/ipv4/syncookies.c (ffffffff81b03435)
Location: include/linux/math64.h:124
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_init_timestamp
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b67af8)
Location: include/linux/math64.h:124
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
```
```
In net/mptcp/protocol.c (ffffffff81ba98dc)
Location: include/linux/math64.h:124
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_rcv_space_adjust
  - net/mptcp/protocol.c:perf_trace_mptcp_subflow_get_send
  - net/mptcp/protocol.c:trace_event_raw_event_mptcp_subflow_get_send
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
In arch/x86/kernel/cpu/mshyperv.c (ffffffff832b1d5c)
Location: include/linux/math64.h:125
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
```
```
In arch/x86/kernel/smpboot.c (ffffffff81077a30)
Location: include/linux/math64.h:125
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:intel_set_max_freq_ratio
```
```
In arch/x86/kernel/apic/apic.c (ffffffff832b6983)
Location: include/linux/math64.h:125
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:calibrate_APIC_clock
```
```
In kernel/sched/fair.c (ffffffff81103a88)
Location: include/linux/math64.h:125
Inline: True
Inline callers:
  - kernel/sched/fair.c:select_idle_cpu
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/fair.c:attach_entity_load_avg
  - kernel/sched/fair.c:reweight_entity
```
```
In kernel/sched/rt.c (ffffffff8111404c)
Location: include/linux/math64.h:125
Inline: True
```
```
In kernel/sched/pelt.c (ffffffff81122a54)
Location: include/linux/math64.h:125
Inline: True
Inline callers:
  - kernel/sched/pelt.c:update_dl_rq_load_avg
  - kernel/sched/pelt.c:update_dl_rq_load_avg
  - kernel/sched/pelt.c:update_rt_rq_load_avg
  - kernel/sched/pelt.c:update_rt_rq_load_avg
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_blocked_se
  - kernel/sched/pelt.c:__update_load_avg_blocked_se
```
```
In kernel/sched/psi.c (ffffffff81129cc3)
Location: include/linux/math64.h:125
Inline: True
Inline callers:
  - kernel/sched/psi.c:update_averages
  - kernel/sched/psi.c:update_averages
  - kernel/sched/psi.c:collect_percpu_times
```
```
In kernel/time/time.c (ffffffff811635a5)
Location: include/linux/math64.h:125
Inline: True
Inline callers:
  - kernel/time/time.c:nsec_to_clock_t
  - kernel/time/time.c:jiffies_64_to_clock_t
  - kernel/time/time.c:clock_t_to_jiffies
  - kernel/time/time.c:jiffies_to_clock_t
```
```
In kernel/time/ntp.c (ffffffff8116b91d)
Location: include/linux/math64.h:125
Inline: True
Inline callers:
  - kernel/time/ntp.c:ntp_update_frequency
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff811c5028)
Location: include/linux/math64.h:125
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_summary
```
```
In kernel/taskstats.c (ffffffff811d1c45)
Location: include/linux/math64.h:125
Inline: True
Inline callers:
  - kernel/taskstats.c:fill_stats_for_tgid
  - kernel/taskstats.c:fill_stats_for_tgid
```
```
In kernel/tsacct.c (ffffffff811d2a19)
Location: include/linux/math64.h:125
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/tsacct.c:bacct_add_tsk
```
```
In kernel/trace/trace_hwlat.c (ffffffff811f68a9)
Location: include/linux/math64.h:125
Inline: True
```
```
In kernel/bpf/verifier.c (ffffffff8124de15)
Location: include/linux/math64.h:125
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
```
```
In kernel/events/core.c (ffffffff81283f9c)
Location: include/linux/math64.h:125
Inline: True
Inline callers:
  - kernel/events/core.c:perf_cpu_time_max_percent_handler
  - kernel/events/core.c:perf_proc_update_handler
```
```
In mm/page-writeback.c (ffffffff812a5b3b)
Location: include/linux/math64.h:125
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:wb_update_dirty_ratelimit
  - mm/page-writeback.c:wb_position_ratio
  - mm/page-writeback.c:wb_position_ratio
```
```
In mm/vmstat.c (ffffffff812c2345)
Location: include/linux/math64.h:125
Inline: True
Inline callers:
  - mm/vmstat.c:unusable_show_print
  - mm/vmstat.c:extfrag_for_order
  - mm/vmstat.c:__fragmentation_index
  - mm/vmstat.c:__fragmentation_index
```
```
In mm/slub.c (ffffffff81333410)
Location: include/linux/math64.h:125
Inline: True
Inline callers:
  - mm/slub.c:slab_debugfs_show
```
```
In fs/ext4/extents_status.c (ffffffff81453049)
Location: include/linux/math64.h:125
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
```
```
In fs/ext4/super.c (ffffffff8149243d)
Location: include/linux/math64.h:125
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_es_shrink
  - fs/ext4/super.c:trace_event_raw_event_ext4_es_shrink
```
```
In fs/ext4/fast_commit.c (ffffffff814b0f4e)
Location: include/linux/math64.h:125
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_info_show
```
```
In fs/jbd2/journal.c (ffffffff814bd469)
Location: include/linux/math64.h:125
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_seq_info_show
```
```
In security/keys/proc.c (ffffffff8151b59a)
Location: include/linux/math64.h:125
Inline: True
Inline callers:
  - security/keys/proc.c:proc_keys_show
  - security/keys/proc.c:proc_keys_show
  - security/keys/proc.c:proc_keys_show
  - security/keys/proc.c:proc_keys_show
```
```
In block/blk-sysfs.c (ffffffff815cf6ee)
Location: include/linux/math64.h:125
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_wb_lat_show
```
```
In block/blk-stat.c (ffffffff815df512)
Location: include/linux/math64.h:125
Inline: True
Inline callers:
  - block/blk-stat.c:blk_stat_timer_fn
```
```
In block/genhd.c (ffffffff815e325f)
Location: include/linux/math64.h:125
Inline: True
Inline callers:
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:part_stat_show
  - block/genhd.c:part_stat_show
  - block/genhd.c:part_stat_show
  - block/genhd.c:part_stat_show
  - block/genhd.c:part_stat_show
```
```
In block/partitions/efi.c (ffffffff815edad4)
Location: include/linux/math64.h:125
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:read_lba
```
```
In block/blk-iocost.c (ffffffff815fb4f4)
Location: include/linux/math64.h:125
Inline: True
Inline callers:
  - block/blk-iocost.c:transfer_surpluses
  - block/blk-iocost.c:iocg_kick_delay
```
```
In block/blk-wbt.c (ffffffff81606205)
Location: include/linux/math64.h:125
Inline: True
Inline callers:
  - block/blk-wbt.c:rwb_arm_timer
  - block/blk-wbt.c:perf_trace_wbt_step
  - block/blk-wbt.c:perf_trace_wbt_lat
  - block/blk-wbt.c:trace_event_raw_event_wbt_step
  - block/blk-wbt.c:trace_event_raw_event_wbt_lat
```
```
In lib/kstrtox.c (ffffffff8161f6c9)
Location: include/linux/math64.h:125
Inline: True
Inline callers:
  - lib/kstrtox.c:_kstrtoull
```
```
In drivers/idle/intel_idle.c (ffffffff832ef1e9)
Location: include/linux/math64.h:125
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:irtl_2_usec
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff8189627c)
Location: include/linux/math64.h:125
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:__size_store
```
```
In drivers/nvdimm/badrange.c (ffffffff8189a7f5)
Location: include/linux/math64.h:125
Inline: True
Inline callers:
  - drivers/nvdimm/badrange.c:__add_badblock_range
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81a235f4)
Location: include/linux/math64.h:125
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:get_cpu_idle_time
  - drivers/cpufreq/cpufreq.c:get_cpu_idle_time
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff81a2a2f7)
Location: include/linux/math64.h:125
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:dbs_update
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81a2c039)
Location: include/linux/math64.h:125
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
```
```
In drivers/cpuidle/governors/menu.c (ffffffff81a35c6c)
Location: include/linux/math64.h:125
Inline: True
Inline callers:
  - drivers/cpuidle/governors/menu.c:menu_select
  - drivers/cpuidle/governors/menu.c:menu_select
```
```
In drivers/devfreq/governor_simpleondemand.c (ffffffff81a65000)
Location: include/linux/math64.h:125
Inline: True
Inline callers:
  - drivers/devfreq/governor_simpleondemand.c:devfreq_simple_ondemand_func
  - drivers/devfreq/governor_simpleondemand.c:devfreq_simple_ondemand_func
```
```
In net/sched/cls_api.c (ffffffff81b19b33)
Location: include/linux/math64.h:125
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff81b5eb53)
Location: include/linux/math64.h:125
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff81b6d25a)
Location: include/linux/math64.h:125
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_synack_rtt_meas
  - net/ipv4/tcp_input.c:tcp_ack_update_rtt
  - net/ipv4/tcp_input.c:tcp_cwnd_reduction
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
```
In net/ipv4/tcp_output.c (ffffffff81b75b85)
Location: include/linux/math64.h:125
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_window_probe
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_established_options
  - net/ipv4/tcp_output.c:tcp_synack_options
  - net/ipv4/tcp_output.c:tcp_syn_options
```
```
In net/ipv4/tcp_timer.c (ffffffff81b76ff0)
Location: include/linux/math64.h:125
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81b7d51d)
Location: include/linux/math64.h:125
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81b7e1e6)
Location: include/linux/math64.h:125
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
```
```
In net/ipv4/tcp_rate.c (ffffffff81b834e9)
Location: include/linux/math64.h:125
Inline: True
Inline callers:
  - net/ipv4/tcp_rate.c:tcp_rate_skb_delivered
  - net/ipv4/tcp_rate.c:tcp_rate_skb_sent
```
```
In net/ipv4/tcp_recovery.c (ffffffff81b837b6)
Location: include/linux/math64.h:125
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_detect_loss
```
```
In net/ipv4/syncookies.c (ffffffff81bc56c5)
Location: include/linux/math64.h:125
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_init_timestamp
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81c2f724)
Location: include/linux/math64.h:125
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
```
```
In net/mptcp/protocol.c (ffffffff81c7832c)
Location: include/linux/math64.h:125
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_rcv_space_adjust
  - net/mptcp/protocol.c:perf_trace_mptcp_subflow_get_send
  - net/mptcp/protocol.c:trace_event_raw_event_mptcp_subflow_get_send
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
In arch/x86/kernel/cpu/aperfmperf.c (ffffffff8345d9af)
Location: include/linux/math64.h:125
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/aperfmperf.c:intel_set_max_freq_ratio
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff8346302b)
Location: include/linux/math64.h:125
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
```
```
In arch/x86/kernel/acpi/cppc.c (ffffffff810845bd)
Location: include/linux/math64.h:125
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cppc.c:init_freq_invariance_cppc
```
```
In arch/x86/kernel/apic/apic.c (ffffffff83468470)
Location: include/linux/math64.h:125
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:calibrate_APIC_clock
```
```
In kernel/sched/fair.c (ffffffff8111fa73)
Location: include/linux/math64.h:125
Inline: True
Inline callers:
  - kernel/sched/fair.c:select_idle_cpu
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/fair.c:attach_entity_load_avg
  - kernel/sched/fair.c:reweight_entity
```
```
In kernel/sched/build_policy.c (ffffffff811387ff)
Location: include/linux/math64.h:125
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:update_dl_rq_load_avg
  - kernel/sched/build_policy.c:update_dl_rq_load_avg
  - kernel/sched/build_policy.c:update_rt_rq_load_avg
  - kernel/sched/build_policy.c:update_rt_rq_load_avg
  - kernel/sched/build_policy.c:__update_load_avg_cfs_rq
  - kernel/sched/build_policy.c:__update_load_avg_cfs_rq
  - kernel/sched/build_policy.c:__update_load_avg_se
  - kernel/sched/build_policy.c:__update_load_avg_se
  - kernel/sched/build_policy.c:__update_load_avg_blocked_se
  - kernel/sched/build_policy.c:__update_load_avg_blocked_se
```
```
In kernel/sched/build_utility.c (ffffffff8114c8ef)
Location: include/linux/math64.h:125
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:psi_trigger_create
  - kernel/sched/build_utility.c:update_averages
  - kernel/sched/build_utility.c:update_averages
  - kernel/sched/build_utility.c:collect_percpu_times
  - kernel/sched/build_utility.c:__sched_core_account_forceidle
```
```
In kernel/time/time.c (ffffffff81196605)
Location: include/linux/math64.h:125
Inline: True
Inline callers:
  - kernel/time/time.c:nsec_to_clock_t
  - kernel/time/time.c:jiffies_64_to_clock_t
  - kernel/time/time.c:clock_t_to_jiffies
  - kernel/time/time.c:jiffies_to_clock_t
```
```
In kernel/time/ntp.c (ffffffff8119f833)
Location: include/linux/math64.h:125
Inline: True
Inline callers:
  - kernel/time/ntp.c:ntp_update_frequency
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff811f8b6a)
Location: include/linux/math64.h:125
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_summary
```
```
In kernel/taskstats.c (ffffffff81206456)
Location: include/linux/math64.h:125
Inline: True
Inline callers:
  - kernel/taskstats.c:fill_stats_for_tgid
  - kernel/taskstats.c:fill_stats_for_tgid
```
```
In kernel/tsacct.c (ffffffff812073a0)
Location: include/linux/math64.h:125
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/tsacct.c:bacct_add_tsk
```
```
In kernel/trace/trace_hwlat.c (ffffffff812302e4)
Location: include/linux/math64.h:125
Inline: True
```
```
In kernel/bpf/verifier.c (ffffffff81294cbf)
Location: include/linux/math64.h:125
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
```
```
In kernel/events/core.c (ffffffff812d82c1)
Location: include/linux/math64.h:125
Inline: True
Inline callers:
  - kernel/events/core.c:perf_cpu_time_max_percent_handler
  - kernel/events/core.c:perf_proc_update_handler
```
```
In mm/page-writeback.c (ffffffff812fe806)
Location: include/linux/math64.h:125
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:wb_update_dirty_ratelimit
  - mm/page-writeback.c:wb_position_ratio
  - mm/page-writeback.c:wb_position_ratio
```
```
In mm/vmstat.c (ffffffff8131fc1c)
Location: include/linux/math64.h:125
Inline: True
Inline callers:
  - mm/vmstat.c:unusable_show_print
  - mm/vmstat.c:extfrag_for_order
  - mm/vmstat.c:__fragmentation_index
  - mm/vmstat.c:__fragmentation_index
```
```
In mm/slub.c (ffffffff813a4bcc)
Location: include/linux/math64.h:125
Inline: True
Inline callers:
  - mm/slub.c:slab_debugfs_show
```
```
In fs/ext4/extents_status.c (ffffffff814d0569)
Location: include/linux/math64.h:125
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
```
```
In fs/ext4/super.c (ffffffff81517222)
Location: include/linux/math64.h:125
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_es_shrink
  - fs/ext4/super.c:trace_event_raw_event_ext4_es_shrink
```
```
In fs/ext4/fast_commit.c (ffffffff815399f6)
Location: include/linux/math64.h:125
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_info_show
```
```
In fs/jbd2/journal.c (ffffffff81548910)
Location: include/linux/math64.h:125
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_seq_info_show
```
```
In security/keys/proc.c (ffffffff815ae7c2)
Location: include/linux/math64.h:125
Inline: True
Inline callers:
  - security/keys/proc.c:proc_keys_show
  - security/keys/proc.c:proc_keys_show
  - security/keys/proc.c:proc_keys_show
  - security/keys/proc.c:proc_keys_show
```
```
In block/blk-sysfs.c (ffffffff8167ad2d)
Location: include/linux/math64.h:125
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_wb_lat_show
```
```
In block/blk-stat.c (ffffffff8168dbf6)
Location: include/linux/math64.h:125
Inline: True
Inline callers:
  - block/blk-stat.c:blk_stat_timer_fn
```
```
In block/genhd.c (ffffffff81692496)
Location: include/linux/math64.h:125
Inline: True
Inline callers:
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:part_stat_show
  - block/genhd.c:part_stat_show
  - block/genhd.c:part_stat_show
  - block/genhd.c:part_stat_show
  - block/genhd.c:part_stat_show
```
```
In block/partitions/efi.c (ffffffff8169e07b)
Location: include/linux/math64.h:125
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:is_gpt_valid
  - block/partitions/efi.c:read_lba
```
```
In block/blk-iocost.c (ffffffff816afc38)
Location: include/linux/math64.h:125
Inline: True
Inline callers:
  - block/blk-iocost.c:transfer_surpluses
  - block/blk-iocost.c:iocg_kick_delay
```
```
In block/blk-wbt.c (ffffffff816b9ec3)
Location: include/linux/math64.h:125
Inline: True
Inline callers:
  - block/blk-wbt.c:rwb_arm_timer
  - block/blk-wbt.c:perf_trace_wbt_step
  - block/blk-wbt.c:perf_trace_wbt_lat
  - block/blk-wbt.c:trace_event_raw_event_wbt_step
  - block/blk-wbt.c:trace_event_raw_event_wbt_lat
```
```
In lib/kstrtox.c (ffffffff816edb8b)
Location: include/linux/math64.h:125
Inline: True
Inline callers:
  - lib/kstrtox.c:_parse_integer_limit
```
```
In lib/zstd/compress/fse_compress.c (ffffffff8170eafe)
Location: include/linux/math64.h:125
Inline: True
Inline callers:
  - lib/zstd/compress/fse_compress.c:FSE_normalizeCount
  - lib/zstd/compress/fse_compress.c:FSE_normalizeM2
```
```
In lib/flex_proportions.c (ffffffff81777d94)
Location: include/linux/math64.h:125
Inline: True
Inline callers:
  - lib/flex_proportions.c:__fprop_add_percpu_max
```
```
In drivers/idle/intel_idle.c (ffffffff834a7200)
Location: include/linux/math64.h:125
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:irtl_2_usec
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff819df633)
Location: include/linux/math64.h:125
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:__size_store
```
```
In drivers/nvdimm/badrange.c (ffffffff819e3f25)
Location: include/linux/math64.h:125
Inline: True
Inline callers:
  - drivers/nvdimm/badrange.c:__add_badblock_range
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81b8c88f)
Location: include/linux/math64.h:125
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:get_cpu_idle_time
  - drivers/cpufreq/cpufreq.c:get_cpu_idle_time
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff81b94590)
Location: include/linux/math64.h:125
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:dbs_update
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81b96682)
Location: include/linux/math64.h:125
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
```
```
In drivers/cpufreq/amd-pstate.c (ffffffff81b972c4)
Location: include/linux/math64.h:125
Inline: True
Inline callers:
  - drivers/cpufreq/amd-pstate.c:show_amd_pstate_lowest_nonlinear_freq
  - drivers/cpufreq/amd-pstate.c:show_amd_pstate_max_freq
  - drivers/cpufreq/amd-pstate.c:amd_pstate_cpu_init
  - drivers/cpufreq/amd-pstate.c:amd_pstate_cpu_init
```
```
In drivers/cpuidle/governors/menu.c (ffffffff81ba2677)
Location: include/linux/math64.h:125
Inline: True
Inline callers:
  - drivers/cpuidle/governors/menu.c:menu_select
  - drivers/cpuidle/governors/menu.c:menu_select
```
```
In drivers/devfreq/governor_simpleondemand.c (ffffffff81bd5d12)
Location: include/linux/math64.h:125
Inline: True
Inline callers:
  - drivers/devfreq/governor_simpleondemand.c:devfreq_simple_ondemand_func
  - drivers/devfreq/governor_simpleondemand.c:devfreq_simple_ondemand_func
```
```
In net/ipv4/tcp.c (ffffffff81ced773)
Location: include/linux/math64.h:125
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff81cfc9c0)
Location: include/linux/math64.h:125
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_synack_rtt_meas
  - net/ipv4/tcp_input.c:tcp_ack_update_rtt
  - net/ipv4/tcp_input.c:tcp_cwnd_reduction
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
```
In net/ipv4/tcp_output.c (ffffffff81d05481)
Location: include/linux/math64.h:125
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_window_probe
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_established_options
  - net/ipv4/tcp_output.c:tcp_synack_options
  - net/ipv4/tcp_output.c:tcp_syn_options
```
```
In net/ipv4/tcp_timer.c (ffffffff81d0691c)
Location: include/linux/math64.h:125
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81d0d478)
Location: include/linux/math64.h:125
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81d0e10c)
Location: include/linux/math64.h:125
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
```
```
In net/ipv4/tcp_rate.c (ffffffff81d13b10)
Location: include/linux/math64.h:125
Inline: True
Inline callers:
  - net/ipv4/tcp_rate.c:tcp_rate_skb_delivered
  - net/ipv4/tcp_rate.c:tcp_rate_skb_sent
```
```
In net/ipv4/tcp_recovery.c (ffffffff81d13e7c)
Location: include/linux/math64.h:125
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_detect_loss
```
```
In net/ipv4/syncookies.c (ffffffff81d5a8a5)
Location: include/linux/math64.h:125
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_init_timestamp
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81dccb1f)
Location: include/linux/math64.h:125
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
```
```
In net/mptcp/protocol.c (ffffffff81e1d3ec)
Location: include/linux/math64.h:125
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_rcv_space_adjust
  - net/mptcp/protocol.c:mptcp_subflow_get_send
  - net/mptcp/protocol.c:mptcp_subflow_get_send
  - net/mptcp/protocol.c:perf_trace_mptcp_subflow_get_send
  - net/mptcp/protocol.c:trace_event_raw_event_mptcp_subflow_get_send
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
In arch/x86/kernel/cpu/aperfmperf.c (ffffffff83e7e7e9)
Location: include/linux/math64.h:127
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/aperfmperf.c:intel_set_max_freq_ratio
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff83e85afa)
Location: include/linux/math64.h:127
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
```
```
In arch/x86/kernel/acpi/cppc.c (ffffffff8109752d)
Location: include/linux/math64.h:127
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cppc.c:init_freq_invariance_cppc
```
```
In arch/x86/kernel/apic/apic.c (ffffffff83e8c989)
Location: include/linux/math64.h:127
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:calibrate_APIC_clock
```
```
In kernel/sched/fair.c (ffffffff81145c3b)
Location: include/linux/math64.h:127
Inline: True
Inline callers:
  - kernel/sched/fair.c:select_idle_cpu
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/fair.c:attach_entity_load_avg
  - kernel/sched/fair.c:reweight_entity
```
```
In kernel/sched/build_policy.c (ffffffff81162e8f)
Location: include/linux/math64.h:127
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:update_dl_rq_load_avg
  - kernel/sched/build_policy.c:update_dl_rq_load_avg
  - kernel/sched/build_policy.c:update_rt_rq_load_avg
  - kernel/sched/build_policy.c:update_rt_rq_load_avg
  - kernel/sched/build_policy.c:__update_load_avg_cfs_rq
  - kernel/sched/build_policy.c:__update_load_avg_cfs_rq
  - kernel/sched/build_policy.c:__update_load_avg_se
  - kernel/sched/build_policy.c:__update_load_avg_se
  - kernel/sched/build_policy.c:__update_load_avg_blocked_se
  - kernel/sched/build_policy.c:__update_load_avg_blocked_se
```
```
In kernel/sched/build_utility.c (ffffffff8117babb)
Location: include/linux/math64.h:127
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:psi_trigger_destroy
  - kernel/sched/build_utility.c:psi_trigger_create
  - kernel/sched/build_utility.c:update_averages
  - kernel/sched/build_utility.c:update_averages
  - kernel/sched/build_utility.c:collect_percpu_times
  - kernel/sched/build_utility.c:__sched_core_account_forceidle
```
```
In kernel/time/time.c (ffffffff811d4625)
Location: include/linux/math64.h:127
Inline: True
Inline callers:
  - kernel/time/time.c:nsec_to_clock_t
  - kernel/time/time.c:jiffies_64_to_clock_t
  - kernel/time/time.c:clock_t_to_jiffies
  - kernel/time/time.c:jiffies_to_clock_t
```
```
In kernel/time/ntp.c (ffffffff811de553)
Location: include/linux/math64.h:127
Inline: True
Inline callers:
  - kernel/time/ntp.c:ntp_update_frequency
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff8124000a)
Location: include/linux/math64.h:127
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_summary
```
```
In kernel/taskstats.c (ffffffff8124e756)
Location: include/linux/math64.h:127
Inline: True
Inline callers:
  - kernel/taskstats.c:fill_stats_for_tgid
  - kernel/taskstats.c:fill_stats_for_tgid
```
```
In kernel/tsacct.c (ffffffff8124f730)
Location: include/linux/math64.h:127
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/tsacct.c:bacct_add_tsk
```
```
In kernel/trace/trace_hwlat.c (ffffffff8127c574)
Location: include/linux/math64.h:127
Inline: True
```
```
In kernel/bpf/verifier.c (ffffffff812ef8d8)
Location: include/linux/math64.h:127
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
```
```
In kernel/events/core.c (ffffffff81340774)
Location: include/linux/math64.h:127
Inline: True
Inline callers:
  - kernel/events/core.c:perf_cpu_time_max_percent_handler
  - kernel/events/core.c:perf_proc_update_handler
```
```
In mm/page-writeback.c (ffffffff81368f1f)
Location: include/linux/math64.h:127
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:wb_update_dirty_ratelimit
  - mm/page-writeback.c:wb_position_ratio
  - mm/page-writeback.c:wb_position_ratio
```
```
In mm/vmstat.c (ffffffff813937fc)
Location: include/linux/math64.h:127
Inline: True
Inline callers:
  - mm/vmstat.c:unusable_show_print
  - mm/vmstat.c:extfrag_for_order
  - mm/vmstat.c:__fragmentation_index
  - mm/vmstat.c:__fragmentation_index
```
```
In mm/slub.c (ffffffff81424e63)
Location: include/linux/math64.h:127
Inline: True
Inline callers:
  - mm/slub.c:slab_debugfs_show
```
```
In fs/ext4/extents_status.c (ffffffff81568ed9)
Location: include/linux/math64.h:127
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
```
```
In fs/ext4/super.c (ffffffff815b2d2f)
Location: include/linux/math64.h:127
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_es_shrink
  - fs/ext4/super.c:trace_event_raw_event_ext4_es_shrink
```
```
In fs/ext4/fast_commit.c (ffffffff815d7f06)
Location: include/linux/math64.h:127
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_info_show
```
```
In fs/jbd2/journal.c (ffffffff815e7ec0)
Location: include/linux/math64.h:127
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_seq_info_show
```
```
In security/keys/proc.c (ffffffff81658f32)
Location: include/linux/math64.h:127
Inline: True
Inline callers:
  - security/keys/proc.c:proc_keys_show
  - security/keys/proc.c:proc_keys_show
  - security/keys/proc.c:proc_keys_show
  - security/keys/proc.c:proc_keys_show
```
```
In block/blk-sysfs.c (ffffffff81737935)
Location: include/linux/math64.h:127
Inline: True
```
```
In block/blk-stat.c (ffffffff8174c4a7)
Location: include/linux/math64.h:127
Inline: True
Inline callers:
  - block/blk-stat.c:blk_stat_timer_fn
```
```
In block/genhd.c (ffffffff81751796)
Location: include/linux/math64.h:127
Inline: True
Inline callers:
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:part_stat_show
  - block/genhd.c:part_stat_show
  - block/genhd.c:part_stat_show
  - block/genhd.c:part_stat_show
  - block/genhd.c:part_stat_show
```
```
In block/partitions/efi.c (ffffffff8175cabb)
Location: include/linux/math64.h:127
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:is_gpt_valid
  - block/partitions/efi.c:read_lba
```
```
In block/blk-iocost.c (ffffffff8176df2b)
Location: include/linux/math64.h:127
Inline: True
Inline callers:
  - block/blk-iocost.c:transfer_surpluses
  - block/blk-iocost.c:iocg_kick_delay
```
```
In block/blk-wbt.c (ffffffff8177a3c3)
Location: include/linux/math64.h:127
Inline: True
Inline callers:
  - block/blk-wbt.c:rwb_arm_timer
  - block/blk-wbt.c:perf_trace_wbt_step
  - block/blk-wbt.c:perf_trace_wbt_lat
  - block/blk-wbt.c:trace_event_raw_event_wbt_step
  - block/blk-wbt.c:trace_event_raw_event_wbt_lat
```
```
In lib/kstrtox.c (ffffffff817de5cb)
Location: include/linux/math64.h:127
Inline: True
Inline callers:
  - lib/kstrtox.c:_parse_integer_limit
```
```
In lib/zstd/compress/fse_compress.c (ffffffff817fdb5e)
Location: include/linux/math64.h:127
Inline: True
Inline callers:
  - lib/zstd/compress/fse_compress.c:FSE_normalizeCount
  - lib/zstd/compress/fse_compress.c:FSE_normalizeM2
```
```
In drivers/idle/intel_idle.c (ffffffff83ede419)
Location: include/linux/math64.h:127
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:bxt_idle_state_table_update
  - drivers/idle/intel_idle.c:bxt_idle_state_table_update
  - drivers/idle/intel_idle.c:bxt_idle_state_table_update
  - drivers/idle/intel_idle.c:bxt_idle_state_table_update
  - drivers/idle/intel_idle.c:bxt_idle_state_table_update
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff81b5ab76)
Location: include/linux/math64.h:127
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:__size_store
```
```
In drivers/nvdimm/badrange.c (ffffffff81b5fc05)
Location: include/linux/math64.h:127
Inline: True
Inline callers:
  - drivers/nvdimm/badrange.c:__add_badblock_range
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81d2c2cf)
Location: include/linux/math64.h:127
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:get_cpu_idle_time
  - drivers/cpufreq/cpufreq.c:get_cpu_idle_time
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff81d3542c)
Location: include/linux/math64.h:127
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:dbs_update
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81d372c3)
Location: include/linux/math64.h:127
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
```
```
In drivers/cpufreq/amd-pstate.c (ffffffff81d38124)
Location: include/linux/math64.h:127
Inline: True
Inline callers:
  - drivers/cpufreq/amd-pstate.c:show_amd_pstate_lowest_nonlinear_freq
  - drivers/cpufreq/amd-pstate.c:show_amd_pstate_max_freq
  - drivers/cpufreq/amd-pstate.c:amd_pstate_cpu_init
  - drivers/cpufreq/amd-pstate.c:amd_pstate_cpu_init
```
```
In drivers/cpuidle/governors/menu.c (ffffffff81d445c7)
Location: include/linux/math64.h:127
Inline: True
Inline callers:
  - drivers/cpuidle/governors/menu.c:menu_select
  - drivers/cpuidle/governors/menu.c:menu_select
```
```
In drivers/devfreq/governor_simpleondemand.c (ffffffff81d82392)
Location: include/linux/math64.h:127
Inline: True
Inline callers:
  - drivers/devfreq/governor_simpleondemand.c:devfreq_simple_ondemand_func
  - drivers/devfreq/governor_simpleondemand.c:devfreq_simple_ondemand_func
```
```
In net/ipv4/tcp.c (ffffffff81eb3f9d)
Location: include/linux/math64.h:127
Inline: True
Inline callers:
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/ipv4/tcp.c:do_tcp_setsockopt
```
```
In net/ipv4/tcp_input.c (ffffffff81ec1570)
Location: include/linux/math64.h:127
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_synack_rtt_meas
  - net/ipv4/tcp_input.c:tcp_ack_update_rtt
  - net/ipv4/tcp_input.c:tcp_cwnd_reduction
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
```
In net/ipv4/tcp_output.c (ffffffff81eca571)
Location: include/linux/math64.h:127
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_window_probe
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_established_options
  - net/ipv4/tcp_output.c:tcp_synack_options
  - net/ipv4/tcp_output.c:tcp_syn_options
```
```
In net/ipv4/tcp_timer.c (ffffffff81ecbb7c)
Location: include/linux/math64.h:127
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ed2ead)
Location: include/linux/math64.h:127
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ed3bdd)
Location: include/linux/math64.h:127
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
```
```
In net/ipv4/tcp_rate.c (ffffffff81ed9b10)
Location: include/linux/math64.h:127
Inline: True
Inline callers:
  - net/ipv4/tcp_rate.c:tcp_rate_skb_delivered
  - net/ipv4/tcp_rate.c:tcp_rate_skb_sent
```
```
In net/ipv4/tcp_recovery.c (ffffffff81ed9e9c)
Location: include/linux/math64.h:127
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_detect_loss
```
```
In net/ipv4/syncookies.c (ffffffff81f24cf5)
Location: include/linux/math64.h:127
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_init_timestamp
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81f9dc32)
Location: include/linux/math64.h:127
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
```
```
In net/mptcp/protocol.c (ffffffff81ff499c)
Location: include/linux/math64.h:127
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_rcv_space_adjust
  - net/mptcp/protocol.c:mptcp_subflow_get_send
  - net/mptcp/protocol.c:mptcp_subflow_get_send
  - net/mptcp/protocol.c:perf_trace_mptcp_subflow_get_send
  - net/mptcp/protocol.c:trace_event_raw_event_mptcp_subflow_get_send
```
```
In lib/flex_proportions.c (ffffffff82020a84)
Location: include/linux/math64.h:127
Inline: True
Inline callers:
  - lib/flex_proportions.c:__fprop_add_percpu_max
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
In arch/x86/kernel/cpu/aperfmperf.c (ffffffff836a150e)
Location: include/linux/math64.h:127
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/aperfmperf.c:intel_set_max_freq_ratio
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff836a905a)
Location: include/linux/math64.h:127
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
```
```
In arch/x86/kernel/acpi/cppc.c (ffffffff8109a605)
Location: include/linux/math64.h:127
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cppc.c:init_freq_invariance_cppc
```
```
In arch/x86/kernel/apic/apic.c (ffffffff836b0219)
Location: include/linux/math64.h:127
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:calibrate_APIC_clock
```
```
In kernel/sched/fair.c (ffffffff81156a04)
Location: include/linux/math64.h:127
Inline: True
Inline callers:
  - kernel/sched/fair.c:select_idle_cpu
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/fair.c:attach_entity_load_avg
  - kernel/sched/fair.c:reweight_entity
```
```
In kernel/sched/build_policy.c (ffffffff81173529)
Location: include/linux/math64.h:127
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:update_dl_rq_load_avg
  - kernel/sched/build_policy.c:update_dl_rq_load_avg
  - kernel/sched/build_policy.c:update_rt_rq_load_avg
  - kernel/sched/build_policy.c:update_rt_rq_load_avg
  - kernel/sched/build_policy.c:__update_load_avg_cfs_rq
  - kernel/sched/build_policy.c:__update_load_avg_cfs_rq
  - kernel/sched/build_policy.c:__update_load_avg_se
  - kernel/sched/build_policy.c:__update_load_avg_se
  - kernel/sched/build_policy.c:__update_load_avg_blocked_se
  - kernel/sched/build_policy.c:__update_load_avg_blocked_se
```
```
In kernel/sched/build_utility.c (ffffffff8118c820)
Location: include/linux/math64.h:127
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:psi_trigger_destroy
  - kernel/sched/build_utility.c:psi_trigger_destroy
  - kernel/sched/build_utility.c:psi_trigger_create
  - kernel/sched/build_utility.c:update_averages
  - kernel/sched/build_utility.c:update_averages
  - kernel/sched/build_utility.c:collect_percpu_times
  - kernel/sched/build_utility.c:__sched_core_account_forceidle
```
```
In kernel/rcu/tree.c (ffffffff811c4aa5)
Location: include/linux/math64.h:127
Inline: True
Inline callers:
  - kernel/rcu/tree.c:print_cpu_stall_info
  - kernel/rcu/tree.c:print_cpu_stall_info
  - kernel/rcu/tree.c:print_cpu_stall_info
```
```
In kernel/time/time.c (ffffffff811e8915)
Location: include/linux/math64.h:127
Inline: True
Inline callers:
  - kernel/time/time.c:nsec_to_clock_t
  - kernel/time/time.c:jiffies_64_to_clock_t
  - kernel/time/time.c:clock_t_to_jiffies
  - kernel/time/time.c:jiffies_to_clock_t
```
```
In kernel/time/ntp.c (ffffffff811f2a23)
Location: include/linux/math64.h:127
Inline: True
Inline callers:
  - kernel/time/ntp.c:ntp_update_frequency
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff8125709a)
Location: include/linux/math64.h:127
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_summary
```
```
In kernel/taskstats.c (ffffffff81265b06)
Location: include/linux/math64.h:127
Inline: True
Inline callers:
  - kernel/taskstats.c:fill_stats_for_tgid
  - kernel/taskstats.c:fill_stats_for_tgid
```
```
In kernel/tsacct.c (ffffffff81266ae0)
Location: include/linux/math64.h:127
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/tsacct.c:bacct_add_tsk
```
```
In kernel/trace/trace_hwlat.c (ffffffff812940c4)
Location: include/linux/math64.h:127
Inline: True
```
```
In kernel/trace/trace_osnoise.c (ffffffff812983fc)
Location: include/linux/math64.h:127
Inline: True
Inline callers:
  - kernel/trace/trace_osnoise.c:timerlat_fd_read
  - kernel/trace/trace_osnoise.c:timerlat_fd_read
  - kernel/trace/trace_osnoise.c:timerlat_main
  - kernel/trace/trace_osnoise.c:timerlat_irq
```
```
In kernel/bpf/verifier.c (ffffffff8131c471)
Location: include/linux/math64.h:127
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
```
```
In kernel/events/core.c (ffffffff81371714)
Location: include/linux/math64.h:127
Inline: True
Inline callers:
  - kernel/events/core.c:perf_cpu_time_max_percent_handler
  - kernel/events/core.c:perf_proc_update_handler
```
```
In mm/page-writeback.c (ffffffff8139b0bf)
Location: include/linux/math64.h:127
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:wb_update_dirty_ratelimit
  - mm/page-writeback.c:wb_position_ratio
  - mm/page-writeback.c:wb_position_ratio
```
```
In mm/vmstat.c (ffffffff813c6367)
Location: include/linux/math64.h:127
Inline: True
Inline callers:
  - mm/vmstat.c:extfrag_show_print
  - mm/vmstat.c:extfrag_show_print
  - mm/vmstat.c:unusable_show_print
  - mm/vmstat.c:extfrag_for_order
```
```
In mm/slub.c (ffffffff8145a213)
Location: include/linux/math64.h:127
Inline: True
Inline callers:
  - mm/slub.c:slab_debugfs_show
```
```
In fs/ext4/extents_status.c (ffffffff815a0b92)
Location: include/linux/math64.h:127
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
```
```
In fs/ext4/super.c (ffffffff815e9a8f)
Location: include/linux/math64.h:127
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_es_shrink
  - fs/ext4/super.c:trace_event_raw_event_ext4_es_shrink
```
```
In fs/ext4/fast_commit.c (ffffffff8160fa96)
Location: include/linux/math64.h:127
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_info_show
```
```
In fs/jbd2/journal.c (ffffffff8161f7d0)
Location: include/linux/math64.h:127
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_seq_info_show
```
```
In security/keys/proc.c (ffffffff816917d2)
Location: include/linux/math64.h:127
Inline: True
Inline callers:
  - security/keys/proc.c:proc_keys_show
  - security/keys/proc.c:proc_keys_show
  - security/keys/proc.c:proc_keys_show
  - security/keys/proc.c:proc_keys_show
```
```
In block/blk-sysfs.c (ffffffff81773dd5)
Location: include/linux/math64.h:127
Inline: True
```
```
In block/blk-stat.c (ffffffff81788bd3)
Location: include/linux/math64.h:127
Inline: True
Inline callers:
  - block/blk-stat.c:blk_stat_timer_fn
```
```
In block/genhd.c (ffffffff8178dd16)
Location: include/linux/math64.h:127
Inline: True
Inline callers:
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:part_stat_show
  - block/genhd.c:part_stat_show
  - block/genhd.c:part_stat_show
  - block/genhd.c:part_stat_show
  - block/genhd.c:part_stat_show
```
```
In block/partitions/efi.c (ffffffff8179b356)
Location: include/linux/math64.h:127
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:is_gpt_valid
  - block/partitions/efi.c:read_lba
```
```
In block/blk-iocost.c (ffffffff817adab8)
Location: include/linux/math64.h:127
Inline: True
Inline callers:
  - block/blk-iocost.c:transfer_surpluses
  - block/blk-iocost.c:iocg_kick_delay
```
```
In block/blk-wbt.c (ffffffff817ba1b3)
Location: include/linux/math64.h:127
Inline: True
Inline callers:
  - block/blk-wbt.c:rwb_arm_timer
  - block/blk-wbt.c:perf_trace_wbt_step
  - block/blk-wbt.c:perf_trace_wbt_lat
  - block/blk-wbt.c:trace_event_raw_event_wbt_step
  - block/blk-wbt.c:trace_event_raw_event_wbt_lat
```
```
In lib/kstrtox.c (ffffffff8181ddab)
Location: include/linux/math64.h:127
Inline: True
Inline callers:
  - lib/kstrtox.c:_parse_integer_limit
```
```
In lib/zstd/compress/fse_compress.c (ffffffff8183e3be)
Location: include/linux/math64.h:127
Inline: True
Inline callers:
  - lib/zstd/compress/fse_compress.c:FSE_normalizeCount
  - lib/zstd/compress/fse_compress.c:FSE_normalizeM2
```
```
In drivers/idle/intel_idle.c (ffffffff83703f49)
Location: include/linux/math64.h:127
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:bxt_idle_state_table_update
  - drivers/idle/intel_idle.c:bxt_idle_state_table_update
  - drivers/idle/intel_idle.c:bxt_idle_state_table_update
  - drivers/idle/intel_idle.c:bxt_idle_state_table_update
  - drivers/idle/intel_idle.c:bxt_idle_state_table_update
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff81bae3cf)
Location: include/linux/math64.h:127
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:__size_store
```
```
In drivers/nvdimm/badrange.c (ffffffff81bb31a5)
Location: include/linux/math64.h:127
Inline: True
Inline callers:
  - drivers/nvdimm/badrange.c:__add_badblock_range
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81d9555f)
Location: include/linux/math64.h:127
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:get_cpu_idle_time
  - drivers/cpufreq/cpufreq.c:get_cpu_idle_time
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff81d9e79c)
Location: include/linux/math64.h:127
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:dbs_update
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81da0659)
Location: include/linux/math64.h:127
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
```
```
In drivers/cpufreq/amd-pstate.c (ffffffff81da1f46)
Location: include/linux/math64.h:127
Inline: True
Inline callers:
  - drivers/cpufreq/amd-pstate.c:amd_pstate_epp_cpu_init
  - drivers/cpufreq/amd-pstate.c:amd_pstate_epp_cpu_init
  - drivers/cpufreq/amd-pstate.c:show_amd_pstate_lowest_nonlinear_freq
  - drivers/cpufreq/amd-pstate.c:show_amd_pstate_max_freq
  - drivers/cpufreq/amd-pstate.c:amd_pstate_cpu_init
  - drivers/cpufreq/amd-pstate.c:amd_pstate_cpu_init
  - drivers/cpufreq/amd-pstate.c:amd_pstate_adjust_perf
```
```
In drivers/cpuidle/driver.c (ffffffff81dac9bf)
Location: include/linux/math64.h:127
Inline: True
```
```
In drivers/cpuidle/governors/menu.c (ffffffff81daea05)
Location: include/linux/math64.h:127
Inline: True
Inline callers:
  - drivers/cpuidle/governors/menu.c:menu_select
  - drivers/cpuidle/governors/menu.c:menu_select
```
```
In drivers/devfreq/governor_simpleondemand.c (ffffffff81df0753)
Location: include/linux/math64.h:127
Inline: True
Inline callers:
  - drivers/devfreq/governor_simpleondemand.c:devfreq_simple_ondemand_func
  - drivers/devfreq/governor_simpleondemand.c:devfreq_simple_ondemand_func
```
```
In net/ipv4/tcp.c (ffffffff81f12913)
Location: include/linux/math64.h:127
Inline: True
Inline callers:
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/ipv4/tcp.c:do_tcp_setsockopt
```
```
In net/ipv4/tcp_input.c (ffffffff81f1fad0)
Location: include/linux/math64.h:127
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_synack_rtt_meas
  - net/ipv4/tcp_input.c:tcp_ack_update_rtt
  - net/ipv4/tcp_input.c:tcp_cwnd_reduction
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
```
In net/ipv4/tcp_output.c (ffffffff81f290b1)
Location: include/linux/math64.h:127
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_window_probe
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_established_options
  - net/ipv4/tcp_output.c:tcp_synack_options
  - net/ipv4/tcp_output.c:tcp_syn_options
```
```
In net/ipv4/tcp_timer.c (ffffffff81f2a846)
Location: include/linux/math64.h:127
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81f31ba7)
Location: include/linux/math64.h:127
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81f32bba)
Location: include/linux/math64.h:127
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
```
```
In net/ipv4/tcp_rate.c (ffffffff81f38bf0)
Location: include/linux/math64.h:127
Inline: True
Inline callers:
  - net/ipv4/tcp_rate.c:tcp_rate_skb_delivered
  - net/ipv4/tcp_rate.c:tcp_rate_skb_sent
```
```
In net/ipv4/tcp_recovery.c (ffffffff81f38f7c)
Location: include/linux/math64.h:127
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_detect_loss
```
```
In net/ipv4/syncookies.c (ffffffff81f84885)
Location: include/linux/math64.h:127
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_init_timestamp
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81ffe768)
Location: include/linux/math64.h:127
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
```
```
In net/mptcp/protocol.c (ffffffff8207125c)
Location: include/linux/math64.h:127
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_rcv_space_adjust
  - net/mptcp/protocol.c:mptcp_subflow_get_send
  - net/mptcp/protocol.c:mptcp_subflow_get_send
  - net/mptcp/protocol.c:perf_trace_mptcp_subflow_get_send
  - net/mptcp/protocol.c:trace_event_raw_event_mptcp_subflow_get_send
```
```
In lib/flex_proportions.c (ffffffff820a0aac)
Location: include/linux/math64.h:127
Inline: True
Inline callers:
  - lib/flex_proportions.c:__fprop_add_percpu_max
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
In arch/x86/kernel/cpu/aperfmperf.c (ffffffff838d15be)
Location: include/linux/math64.h:127
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/aperfmperf.c:intel_set_max_freq_ratio
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff838d96a1)
Location: include/linux/math64.h:127
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
```
```
In arch/x86/kernel/acpi/cppc.c (ffffffff810a1e35)
Location: include/linux/math64.h:127
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cppc.c:init_freq_invariance_cppc
```
```
In arch/x86/kernel/apic/apic.c (0)
Location: include/linux/math64.h:127
Inline: True
```
```
In kernel/sched/fair.c (ffffffff81170337)
Location: include/linux/math64.h:127
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/fair.c:attach_entity_load_avg
  - kernel/sched/fair.c:reweight_entity
```
```
In kernel/sched/build_policy.c (ffffffff81180e59)
Location: include/linux/math64.h:127
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:update_dl_rq_load_avg
  - kernel/sched/build_policy.c:update_dl_rq_load_avg
  - kernel/sched/build_policy.c:update_rt_rq_load_avg
  - kernel/sched/build_policy.c:update_rt_rq_load_avg
  - kernel/sched/build_policy.c:__update_load_avg_cfs_rq
  - kernel/sched/build_policy.c:__update_load_avg_cfs_rq
  - kernel/sched/build_policy.c:__update_load_avg_se
  - kernel/sched/build_policy.c:__update_load_avg_se
  - kernel/sched/build_policy.c:__update_load_avg_blocked_se
  - kernel/sched/build_policy.c:__update_load_avg_blocked_se
```
```
In kernel/sched/build_utility.c (ffffffff8119b1c9)
Location: include/linux/math64.h:127
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:psi_trigger_destroy
  - kernel/sched/build_utility.c:psi_trigger_destroy
  - kernel/sched/build_utility.c:psi_trigger_create
  - kernel/sched/build_utility.c:update_averages
  - kernel/sched/build_utility.c:update_averages
  - kernel/sched/build_utility.c:collect_percpu_times
  - kernel/sched/build_utility.c:__sched_core_account_forceidle
```
```
In kernel/rcu/tree.c (ffffffff811d4373)
Location: include/linux/math64.h:127
Inline: True
Inline callers:
  - kernel/rcu/tree.c:print_cpu_stat_info
  - kernel/rcu/tree.c:print_cpu_stat_info
  - kernel/rcu/tree.c:print_cpu_stat_info
```
```
In kernel/time/time.c (ffffffff811fe645)
Location: include/linux/math64.h:127
Inline: True
Inline callers:
  - kernel/time/time.c:nsec_to_clock_t
  - kernel/time/time.c:jiffies_64_to_clock_t
  - kernel/time/time.c:jiffies_to_clock_t
```
```
In kernel/time/ntp.c (ffffffff81208b63)
Location: include/linux/math64.h:127
Inline: True
Inline callers:
  - kernel/time/ntp.c:ntp_update_frequency
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff81270f5a)
Location: include/linux/math64.h:127
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_summary
```
```
In kernel/taskstats.c (ffffffff8127f9b5)
Location: include/linux/math64.h:127
Inline: True
Inline callers:
  - kernel/taskstats.c:fill_stats_for_tgid
  - kernel/taskstats.c:fill_stats_for_tgid
```
```
In kernel/tsacct.c (ffffffff81280a03)
Location: include/linux/math64.h:127
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/tsacct.c:bacct_add_tsk
```
```
In kernel/trace/trace_hwlat.c (ffffffff812af724)
Location: include/linux/math64.h:127
Inline: True
```
```
In kernel/trace/trace_osnoise.c (ffffffff812b3a6e)
Location: include/linux/math64.h:127
Inline: True
Inline callers:
  - kernel/trace/trace_osnoise.c:timerlat_fd_read
  - kernel/trace/trace_osnoise.c:timerlat_fd_read
  - kernel/trace/trace_osnoise.c:timerlat_main
  - kernel/trace/trace_osnoise.c:timerlat_irq
```
```
In kernel/bpf/verifier.c (ffffffff8133e5e5)
Location: include/linux/math64.h:127
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
```
```
In kernel/events/core.c (ffffffff8139aa14)
Location: include/linux/math64.h:127
Inline: True
Inline callers:
  - kernel/events/core.c:perf_cpu_time_max_percent_handler
  - kernel/events/core.c:perf_event_max_sample_rate_handler
```
```
In mm/page-writeback.c (ffffffff813c352f)
Location: include/linux/math64.h:127
Inline: True
Inline callers:
  - mm/page-writeback.c:wb_update_dirty_ratelimit
  - mm/page-writeback.c:wb_position_ratio
  - mm/page-writeback.c:wb_position_ratio
```
```
In mm/vmstat.c (ffffffff813f0d67)
Location: include/linux/math64.h:127
Inline: True
Inline callers:
  - mm/vmstat.c:extfrag_show_print
  - mm/vmstat.c:extfrag_show_print
  - mm/vmstat.c:unusable_show_print
  - mm/vmstat.c:extfrag_for_order
```
```
In mm/slub.c (ffffffff814552e3)
Location: include/linux/math64.h:127
Inline: True
Inline callers:
  - mm/slub.c:slab_debugfs_show
```
```
In fs/buffer.c (ffffffff8153fe9b)
Location: include/linux/math64.h:127
Inline: True
Inline callers:
  - fs/buffer.c:block_read_full_folio
  - fs/buffer.c:block_read_full_folio
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_folio
  - fs/buffer.c:__block_write_full_folio
  - fs/buffer.c:folio_init_buffers
```
```
In fs/ext4/extents_status.c (ffffffff815d98a2)
Location: include/linux/math64.h:127
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
```
```
In fs/ext4/super.c (ffffffff8162247f)
Location: include/linux/math64.h:127
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_es_shrink
  - fs/ext4/super.c:trace_event_raw_event_ext4_es_shrink
```
```
In fs/ext4/fast_commit.c (ffffffff81648856)
Location: include/linux/math64.h:127
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_info_show
```
```
In fs/jbd2/journal.c (ffffffff816586e0)
Location: include/linux/math64.h:127
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_seq_info_show
```
```
In security/keys/proc.c (ffffffff816cddac)
Location: include/linux/math64.h:127
Inline: True
Inline callers:
  - security/keys/proc.c:proc_keys_show
  - security/keys/proc.c:proc_keys_show
  - security/keys/proc.c:proc_keys_show
  - security/keys/proc.c:proc_keys_show
```
```
In block/blk-sysfs.c (ffffffff817b6178)
Location: include/linux/math64.h:127
Inline: True
```
```
In block/blk-stat.c (ffffffff817cb2f3)
Location: include/linux/math64.h:127
Inline: True
Inline callers:
  - block/blk-stat.c:blk_stat_timer_fn
```
```
In block/genhd.c (ffffffff817d0576)
Location: include/linux/math64.h:127
Inline: True
Inline callers:
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:part_stat_show
  - block/genhd.c:part_stat_show
  - block/genhd.c:part_stat_show
  - block/genhd.c:part_stat_show
  - block/genhd.c:part_stat_show
```
```
In block/partitions/efi.c (ffffffff817dedb6)
Location: include/linux/math64.h:127
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:is_gpt_valid
  - block/partitions/efi.c:read_lba
```
```
In block/blk-iocost.c (ffffffff817f18c8)
Location: include/linux/math64.h:127
Inline: True
Inline callers:
  - block/blk-iocost.c:transfer_surpluses
  - block/blk-iocost.c:iocg_kick_delay
```
```
In block/blk-wbt.c (ffffffff817fe923)
Location: include/linux/math64.h:127
Inline: True
Inline callers:
  - block/blk-wbt.c:rwb_arm_timer
  - block/blk-wbt.c:perf_trace_wbt_step
  - block/blk-wbt.c:perf_trace_wbt_lat
  - block/blk-wbt.c:trace_event_raw_event_wbt_step
  - block/blk-wbt.c:trace_event_raw_event_wbt_lat
```
```
In lib/kstrtox.c (ffffffff81863c1b)
Location: include/linux/math64.h:127
Inline: True
Inline callers:
  - lib/kstrtox.c:_parse_integer_limit
```
```
In lib/zstd/compress/fse_compress.c (ffffffff8188ff7e)
Location: include/linux/math64.h:127
Inline: True
Inline callers:
  - lib/zstd/compress/fse_compress.c:FSE_normalizeCount
  - lib/zstd/compress/fse_compress.c:FSE_normalizeM2
```
```
In drivers/idle/intel_idle.c (ffffffff83937559)
Location: include/linux/math64.h:127
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:bxt_idle_state_table_update
  - drivers/idle/intel_idle.c:bxt_idle_state_table_update
  - drivers/idle/intel_idle.c:bxt_idle_state_table_update
  - drivers/idle/intel_idle.c:bxt_idle_state_table_update
  - drivers/idle/intel_idle.c:bxt_idle_state_table_update
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff81c0273f)
Location: include/linux/math64.h:127
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:__size_store
```
```
In drivers/nvdimm/badrange.c (ffffffff81c07695)
Location: include/linux/math64.h:127
Inline: True
Inline callers:
  - drivers/nvdimm/badrange.c:__add_badblock_range
```
```
In drivers/gpu/drm/drm_file.c (ffffffff81c96d1f)
Location: include/linux/math64.h:127
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_file.c:print_size
```
```
In drivers/gpu/drm/drm_vblank.c (ffffffff81cb438e)
Location: include/linux/math64.h:127
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_vblank.c:drm_calc_timestamping_constants
  - drivers/gpu/drm/drm_vblank.c:drm_calc_timestamping_constants
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81e4d07f)
Location: include/linux/math64.h:127
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:get_cpu_idle_time
  - drivers/cpufreq/cpufreq.c:get_cpu_idle_time
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff81e565de)
Location: include/linux/math64.h:127
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:dbs_update
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81e584d8)
Location: include/linux/math64.h:127
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
```
```
In drivers/cpufreq/amd-pstate.c (ffffffff81e59bd7)
Location: include/linux/math64.h:127
Inline: True
Inline callers:
  - drivers/cpufreq/amd-pstate.c:amd_pstate_epp_set_policy
  - drivers/cpufreq/amd-pstate.c:amd_pstate_epp_set_policy
  - drivers/cpufreq/amd-pstate.c:amd_pstate_epp_cpu_init
  - drivers/cpufreq/amd-pstate.c:amd_pstate_epp_cpu_init
  - drivers/cpufreq/amd-pstate.c:show_amd_pstate_lowest_nonlinear_freq
  - drivers/cpufreq/amd-pstate.c:show_amd_pstate_max_freq
  - drivers/cpufreq/amd-pstate.c:amd_pstate_cpu_init
  - drivers/cpufreq/amd-pstate.c:amd_pstate_cpu_init
  - drivers/cpufreq/amd-pstate.c:amd_pstate_adjust_perf
  - drivers/cpufreq/amd-pstate.c:amd_pstate_adjust_perf
  - drivers/cpufreq/amd-pstate.c:amd_pstate_adjust_perf
  - drivers/cpufreq/amd-pstate.c:amd_pstate_update_freq
  - drivers/cpufreq/amd-pstate.c:amd_pstate_update_freq
```
```
In drivers/cpuidle/driver.c (ffffffff81e64a5f)
Location: include/linux/math64.h:127
Inline: True
```
```
In drivers/cpuidle/governors/menu.c (ffffffff81e66dbf)
Location: include/linux/math64.h:127
Inline: True
Inline callers:
  - drivers/cpuidle/governors/menu.c:menu_select
  - drivers/cpuidle/governors/menu.c:menu_select
```
```
In drivers/devfreq/governor_simpleondemand.c (ffffffff81ea6d43)
Location: include/linux/math64.h:127
Inline: True
Inline callers:
  - drivers/devfreq/governor_simpleondemand.c:devfreq_simple_ondemand_func
  - drivers/devfreq/governor_simpleondemand.c:devfreq_simple_ondemand_func
```
```
In net/ipv4/tcp.c (ffffffff81fd6e44)
Location: include/linux/math64.h:127
Inline: True
Inline callers:
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/ipv4/tcp.c:tcp_get_info
```
```
In net/ipv4/tcp_input.c (ffffffff81fe1a65)
Location: include/linux/math64.h:127
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synrecv_state_fastopen
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_synack_rtt_meas
  - net/ipv4/tcp_input.c:tcp_ack_update_rtt
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_cwnd_reduction
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
```
In net/ipv4/tcp_output.c (ffffffff81fedbf1)
Location: include/linux/math64.h:127
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_window_probe
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_established_options
  - net/ipv4/tcp_output.c:tcp_established_options
  - net/ipv4/tcp_output.c:tcp_synack_options
  - net/ipv4/tcp_output.c:tcp_synack_options
  - net/ipv4/tcp_output.c:tcp_syn_options
  - net/ipv4/tcp_output.c:tcp_syn_options
```
```
In net/ipv4/tcp_timer.c (ffffffff81fef3f5)
Location: include/linux/math64.h:127
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ff4029)
Location: include/linux/math64.h:127
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_timewait_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_timewait_ack
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ff8c81)
Location: include/linux/math64.h:127
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
```
```
In net/ipv4/tcp_rate.c (ffffffff81ffecd0)
Location: include/linux/math64.h:127
Inline: True
Inline callers:
  - net/ipv4/tcp_rate.c:tcp_rate_skb_delivered
  - net/ipv4/tcp_rate.c:tcp_rate_skb_sent
```
```
In net/ipv4/tcp_recovery.c (ffffffff81fff05c)
Location: include/linux/math64.h:127
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_detect_loss
```
```
In net/ipv4/syncookies.c (ffffffff8204b0d5)
Location: include/linux/math64.h:127
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_init_timestamp
```
```
In net/ipv6/tcp_ipv6.c (ffffffff820cac4b)
Location: include/linux/math64.h:127
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
  - net/ipv6/tcp_ipv6.c:tcp_v6_timewait_ack
  - net/ipv6/tcp_ipv6.c:tcp_v6_timewait_ack
```
```
In net/mptcp/protocol.c (ffffffff82144865)
Location: include/linux/math64.h:127
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_rcv_space_adjust
  - net/mptcp/protocol.c:mptcp_subflow_get_send
  - net/mptcp/protocol.c:mptcp_subflow_get_send
  - net/mptcp/protocol.c:perf_trace_mptcp_subflow_get_send
  - net/mptcp/protocol.c:trace_event_raw_event_mptcp_subflow_get_send
```
```
In lib/flex_proportions.c (ffffffff82178a8c)
Location: include/linux/math64.h:127
Inline: True
Inline callers:
  - lib/flex_proportions.c:__fprop_add_percpu_max
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
In kernel/sched/cputime.c (ffff80001013f5b8)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - kernel/sched/cputime.c:cputime_adjust
```
```
In kernel/sched/fair.c (ffff800010149ec8)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/fair.c:attach_entity_load_avg
  - kernel/sched/fair.c:reweight_entity
  - kernel/sched/fair.c:reweight_entity
```
```
In kernel/sched/rt.c (ffff80001014f5b8)
Location: include/linux/math64.h:123
Inline: True
```
```
In kernel/sched/pelt.c (ffff80001015ece8)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - kernel/sched/pelt.c:update_dl_rq_load_avg
  - kernel/sched/pelt.c:update_dl_rq_load_avg
  - kernel/sched/pelt.c:update_rt_rq_load_avg
  - kernel/sched/pelt.c:update_rt_rq_load_avg
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_blocked_se
  - kernel/sched/pelt.c:__update_load_avg_blocked_se
```
```
In kernel/sched/psi.c (ffff800010166a70)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_trigger_destroy
  - kernel/sched/psi.c:update_averages
  - kernel/sched/psi.c:update_averages
  - kernel/sched/psi.c:collect_percpu_times
```
```
In kernel/time/time.c (ffff80001019a110)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - kernel/time/time.c:nsecs_to_jiffies
  - kernel/time/time.c:nsec_to_clock_t
  - kernel/time/time.c:jiffies_64_to_clock_t
  - kernel/time/time.c:clock_t_to_jiffies
  - kernel/time/time.c:jiffies_to_clock_t
```
```
In kernel/time/ntp.c (ffff8000101a5b58)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - kernel/time/ntp.c:ntp_update_frequency
```
```
In kernel/debug/kdb/kdb_main.c (ffff8000101ffbfc)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_summary
```
```
In kernel/taskstats.c (ffff80001020d730)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_user_cmd
  - kernel/taskstats.c:taskstats_user_cmd
```
```
In kernel/tsacct.c (ffff80001020df90)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/tsacct.c:bacct_add_tsk
```
```
In kernel/trace/trace_hwlat.c (ffff800010231d20)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/trace/trace_hwlat.c:kthread_fn
```
```
In kernel/bpf/verifier.c (ffff8000102745fc)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
```
```
In kernel/events/core.c (ffff8000102990b4)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - kernel/events/core.c:perf_cpu_time_max_percent_handler
  - kernel/events/core.c:perf_proc_update_handler
```
```
In mm/page-writeback.c (ffff8000102bbb84)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:wb_update_dirty_ratelimit
  - mm/page-writeback.c:wb_position_ratio
  - mm/page-writeback.c:wb_position_ratio
```
```
In mm/vmstat.c (ffff8000102d9c10)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - mm/vmstat.c:unusable_show_print
  - mm/vmstat.c:__fragmentation_index
  - mm/vmstat.c:__fragmentation_index
```
```
In mm/slub.c (ffff800010345478)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - mm/slub.c:list_locations
```
```
In fs/ext4/extents_status.c (ffff80001046fcf0)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
```
```
In fs/ext4/super.c (ffff8000104b4a8c)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_es_shrink
  - fs/ext4/super.c:trace_event_raw_event_ext4_es_shrink
```
```
In fs/jbd2/journal.c (ffff8000104d3988)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_seq_info_show
```
```
In security/keys/proc.c (ffff8000105375bc)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - security/keys/proc.c:proc_keys_show
  - security/keys/proc.c:proc_keys_show
  - security/keys/proc.c:proc_keys_show
  - security/keys/proc.c:proc_keys_show
```
```
In block/blk-sysfs.c (ffff8000105e5ea8)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_wb_lat_show
```
```
In block/blk-stat.c (ffff8000105f4ec8)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - block/blk-stat.c:blk_stat_timer_fn
```
```
In block/genhd.c (ffff8000105fae8c)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
```
```
In block/partition-generic.c (ffff8000105fca50)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
```
```
In block/partitions/efi.c (ffff800010606820)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:read_lba
```
```
In block/blk-wbt.c (ffff800010620d7c)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - block/blk-wbt.c:rwb_arm_timer
  - block/blk-wbt.c:perf_trace_wbt_step
  - block/blk-wbt.c:perf_trace_wbt_lat
  - block/blk-wbt.c:trace_event_raw_event_wbt_step
  - block/blk-wbt.c:trace_event_raw_event_wbt_lat
```
```
In lib/kstrtox.c (ffff800010639e44)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - lib/kstrtox.c:_parse_integer
```
```
In drivers/clk/meson/clk-pll.c (ffff8000107e7bb8)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - drivers/clk/meson/clk-pll.c:meson_clk_pll_set_rate
  - drivers/clk/meson/clk-pll.c:meson_clk_pll_round_rate
  - drivers/clk/meson/clk-pll.c:meson_clk_get_pll_settings
```
```
In drivers/clk/renesas/rcar-gen3-cpg.c (ffff8000107eae0c)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - drivers/clk/renesas/rcar-gen3-cpg.c:cpg_z_clk_round_rate
```
```
In drivers/nvdimm/namespace_devs.c (ffff80001095b1f0)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:__size_store
```
```
In drivers/nvdimm/badrange.c (ffff80001095fb08)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - drivers/nvdimm/badrange.c:__add_badblock_range
```
```
In drivers/net/ethernet/freescale/fec_ptp.c (ffff8000109ecae4)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_adjfreq
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffff800010abac00)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/cpufreq/cpufreq.c (ffff800010b1d058)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:get_cpu_idle_time
  - drivers/cpufreq/cpufreq.c:get_cpu_idle_time
```
```
In drivers/cpufreq/cpufreq_governor.c (ffff800010b25410)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:dbs_update
```
```
In drivers/cpuidle/governors/menu.c (ffff800010b296e8)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - drivers/cpuidle/governors/menu.c:menu_select
```
```
In drivers/devfreq/governor_simpleondemand.c (ffff800010b873bc)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - drivers/devfreq/governor_simpleondemand.c:devfreq_simple_ondemand_func
  - drivers/devfreq/governor_simpleondemand.c:devfreq_simple_ondemand_func
```
```
In net/ipv4/tcp.c (ffff800010c72524)
Location: include/linux/math64.h:123
Inline: True
```
```
In net/ipv4/tcp_input.c (ffff800010c80768)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_synack_rtt_meas
  - net/ipv4/tcp_input.c:tcp_cwnd_reduction
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
```
In net/ipv4/tcp_output.c (ffff800010c88060)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_window_probe
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_established_options
```
```
In net/ipv4/tcp_timer.c (ffff800010c890a0)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (ffff800010c8ec14)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/tcp_minisocks.c (ffff800010c8fc20)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
```
```
In net/ipv4/tcp_rate.c (ffff800010c94428)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp_rate.c:tcp_rate_skb_delivered
  - net/ipv4/tcp_rate.c:tcp_rate_skb_sent
```
```
In net/ipv4/tcp_recovery.c (ffff800010c94738)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_detect_loss
```
```
In net/ipv4/syncookies.c (ffff800010cd1f08)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_init_timestamp
```
```
In net/ipv6/tcp_ipv6.c (ffff800010d39168)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
```
```
In net/xdp/xdp_umem.c (ffff800010d812fc)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_create
```
```
In lib/vsprintf.c (ffff800010d987a4)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - lib/vsprintf.c:vsscanf
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
In kernel/sched/cputime.c (c038f5f4)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - kernel/sched/cputime.c:cputime_adjust
```
```
In kernel/sched/fair.c (c0395ec8)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_h_load
  - kernel/sched/fair.c:task_h_load
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/fair.c:attach_entity_load_avg
  - kernel/sched/fair.c:reweight_entity
  - kernel/sched/fair.c:reweight_entity
```
```
In kernel/sched/rt.c (c039b9a8)
Location: include/linux/math64.h:123
Inline: True
```
```
In kernel/sched/pelt.c (c03ab410)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - kernel/sched/pelt.c:update_dl_rq_load_avg
  - kernel/sched/pelt.c:update_dl_rq_load_avg
  - kernel/sched/pelt.c:update_rt_rq_load_avg
  - kernel/sched/pelt.c:update_rt_rq_load_avg
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_blocked_se
  - kernel/sched/pelt.c:__update_load_avg_blocked_se
```
```
In kernel/sched/debug.c (c03afea4)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
```
```
In kernel/sched/psi.c (c03b3834)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_trigger_destroy
  - kernel/sched/psi.c:update_averages
  - kernel/sched/psi.c:update_averages
  - kernel/sched/psi.c:collect_percpu_times
```
```
In kernel/time/time.c (c03e5314)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - kernel/time/time.c:nsecs_to_jiffies
  - kernel/time/time.c:nsec_to_clock_t
  - kernel/time/time.c:jiffies_64_to_clock_t
  - kernel/time/time.c:jiffies_to_clock_t
```
```
In kernel/time/ntp.c (c03f0ba8)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - kernel/time/ntp.c:ntp_update_frequency
  - kernel/time/ntp.c:ntp_update_frequency
```
```
In kernel/debug/kdb/kdb_main.c (c043f4a4)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_summary
```
```
In kernel/taskstats.c (c044c198)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_user_cmd
  - kernel/taskstats.c:taskstats_user_cmd
```
```
In kernel/tsacct.c (c044ca6c)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/tsacct.c:bacct_add_tsk
```
```
In kernel/trace/ftrace.c (c044ef54)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:function_stat_show
  - kernel/trace/ftrace.c:function_stat_show
```
```
In kernel/trace/trace_hwlat.c (c046d97c)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/trace/trace_hwlat.c:kthread_fn
```
```
In kernel/bpf/verifier.c (c04a6ca8)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
```
```
In kernel/events/core.c (c04c49e0)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - kernel/events/core.c:update_perf_cpu_limits
```
```
In mm/page-writeback.c (c04e8794)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:wb_update_dirty_ratelimit
  - mm/page-writeback.c:wb_position_ratio
  - mm/page-writeback.c:wb_position_ratio
  - mm/page-writeback.c:__wb_calc_thresh
  - mm/page-writeback.c:__wb_calc_thresh
```
```
In mm/vmstat.c (c0500cf4)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - mm/vmstat.c:unusable_show_print
  - mm/vmstat.c:__fragmentation_index
  - mm/vmstat.c:__fragmentation_index
```
```
In mm/slub.c (c054a430)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - mm/slub.c:list_locations
```
```
In fs/ext4/extents_status.c (c0631298)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
```
```
In fs/ext4/super.c (c067bda8)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_es_shrink
  - fs/ext4/super.c:trace_event_raw_event_ext4_es_shrink
```
```
In fs/jbd2/journal.c (c0697798)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_seq_info_show
```
```
In security/keys/proc.c (c06ee608)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - security/keys/proc.c:proc_keys_show
  - security/keys/proc.c:proc_keys_show
  - security/keys/proc.c:proc_keys_show
  - security/keys/proc.c:proc_keys_show
```
```
In block/blk-sysfs.c (c0793730)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_wb_lat_show
```
```
In block/blk-stat.c (c07a09a8)
Location: include/linux/math64.h:123
Inline: True
```
```
In block/genhd.c (c07a5ffc)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
```
```
In block/partition-generic.c (c07a7ca0)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
```
```
In block/partitions/efi.c (c07b0ce8)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - block/partitions/efi.c:last_lba
```
```
In block/blk-wbt.c (c07c8d18)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - block/blk-wbt.c:rwb_arm_timer
  - block/blk-wbt.c:perf_trace_wbt_step
  - block/blk-wbt.c:perf_trace_wbt_lat
  - block/blk-wbt.c:trace_event_raw_event_wbt_step
  - block/blk-wbt.c:trace_event_raw_event_wbt_lat
```
```
In lib/kstrtox.c (c07df7c4)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - lib/kstrtox.c:_parse_integer
```
```
In lib/math/div64.c (c07e0990)
Location: include/linux/math64.h:123
Inline: True
```
```
In drivers/pci/setup-bus.c (c088d7dc)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
```
```
In drivers/clk/meson/clk-pll.c (c0902844)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - drivers/clk/meson/clk-pll.c:meson_clk_get_pll_range_m
  - drivers/clk/meson/clk-pll.c:__pll_params_with_frac
```
```
In drivers/clk/renesas/clk-rcar-gen2.c (c090479c)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - drivers/clk/renesas/clk-rcar-gen2.c:cpg_z_clk_round_rate
  - drivers/clk/renesas/clk-rcar-gen2.c:cpg_z_clk_recalc_rate
```
```
In drivers/clk/renesas/rcar-gen2-cpg.c (c09049cc)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - drivers/clk/renesas/rcar-gen2-cpg.c:cpg_z_clk_round_rate
  - drivers/clk/renesas/rcar-gen2-cpg.c:cpg_z_clk_recalc_rate
```
```
In drivers/clk/ti/dpll3xxx.c (c0919ba0)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - drivers/clk/ti/dpll3xxx.c:omap3_dpll5_set_rate
```
```
In drivers/net/ethernet/freescale/fec_ptp.c (c0acea44)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_adjfreq
```
```
In drivers/net/ethernet/ti/cpts.c (c0ad1834)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - drivers/net/ethernet/ti/cpts.c:cpts_ptp_adjfreq
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (c0b9a040)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/cpufreq/cpufreq.c (c0bfacb4)
Location: include/linux/math64.h:123
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (c0bffa14)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:dbs_update
```
```
In drivers/cpuidle/governors/menu.c (c0c040ac)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - drivers/cpuidle/governors/menu.c:get_typical_interval
```
```
In drivers/devfreq/governor_simpleondemand.c (c0c6a3c0)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - drivers/devfreq/governor_simpleondemand.c:devfreq_simple_ondemand_func
  - drivers/devfreq/governor_simpleondemand.c:devfreq_simple_ondemand_func
```
```
In sound/core/pcm_lib.c (c0c99508)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - sound/core/pcm_lib.c:update_audio_tstamp
```
```
In net/ipv4/tcp.c (c0d7f0a0)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_time_stamp_raw
```
```
In net/ipv4/tcp_input.c (c0d8fc3c)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_synack_rtt_meas
  - net/ipv4/tcp_input.c:tcp_ack_update_rtt
  - net/ipv4/tcp_input.c:tcp_cwnd_reduction
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
```
In net/ipv4/tcp_output.c (c0d93da0)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_update_skb_after_send
  - net/ipv4/tcp_output.c:tcp_established_options
  - net/ipv4/tcp_output.c:tcp_mstamp_refresh
```
```
In net/ipv4/tcp_timer.c (c0d98584)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (c0d9c1a0)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_timewait_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/tcp_minisocks.c (c0d9e8ec)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
```
```
In net/ipv4/tcp_rate.c (c0da2bf4)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp_rate.c:tcp_rate_skb_delivered
  - net/ipv4/tcp_rate.c:tcp_rate_skb_sent
```
```
In net/ipv4/tcp_recovery.c (c0da3068)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_detect_loss
  - net/ipv4/tcp_recovery.c:tcp_rack_skb_timeout
```
```
In net/ipv4/syncookies.c (c0ddbdac)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_init_timestamp
```
```
In net/ipv6/tcp_ipv6.c (c0e39f10)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
  - net/ipv6/tcp_ipv6.c:tcp_v6_timewait_ack
```
```
In net/xdp/xdp_umem.c (c0e7b870)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_create
```
```
In lib/vsprintf.c (c0e937c8)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - lib/vsprintf.c:vsscanf
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
In kernel/sched/cputime.c (c00000000018e6a0)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - kernel/sched/cputime.c:cputime_adjust
```
```
In kernel/sched/fair.c (c00000000019bf08)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/fair.c:attach_entity_load_avg
  - kernel/sched/fair.c:reweight_entity
  - kernel/sched/fair.c:reweight_entity
```
```
In kernel/sched/rt.c (c0000000001a1830)
Location: include/linux/math64.h:123
Inline: True
```
```
In kernel/sched/pelt.c (c0000000001b3fe0)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - kernel/sched/pelt.c:update_dl_rq_load_avg
  - kernel/sched/pelt.c:update_dl_rq_load_avg
  - kernel/sched/pelt.c:update_rt_rq_load_avg
  - kernel/sched/pelt.c:update_rt_rq_load_avg
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_blocked_se
  - kernel/sched/pelt.c:__update_load_avg_blocked_se
```
```
In kernel/sched/psi.c (c0000000001be6e0)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_trigger_destroy
  - kernel/sched/psi.c:update_averages
  - kernel/sched/psi.c:update_averages
  - kernel/sched/psi.c:collect_percpu_times
```
```
In kernel/time/time.c (c0000000001fa328)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - kernel/time/time.c:nsecs_to_jiffies
  - kernel/time/time.c:nsec_to_clock_t
  - kernel/time/time.c:jiffies_64_to_clock_t
  - kernel/time/time.c:clock_t_to_jiffies
  - kernel/time/time.c:jiffies_to_clock_t
```
```
In kernel/time/ntp.c (c000000000207944)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - kernel/time/ntp.c:ntp_update_frequency
```
```
In kernel/debug/kdb/kdb_main.c (c000000000278d0c)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_summary
```
```
In kernel/taskstats.c (c00000000028b770)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_user_cmd
  - kernel/taskstats.c:taskstats_user_cmd
```
```
In kernel/tsacct.c (c00000000028c188)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/tsacct.c:bacct_add_tsk
```
```
In kernel/trace/trace_hwlat.c (c0000000002bc51c)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/trace/trace_hwlat.c:kthread_fn
```
```
In kernel/bpf/verifier.c (c00000000031c3b0)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
```
```
In kernel/events/core.c (c0000000003482d4)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - kernel/events/core.c:perf_cpu_time_max_percent_handler
  - kernel/events/core.c:perf_proc_update_handler
```
```
In mm/page-writeback.c (c0000000003744bc)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:wb_update_dirty_ratelimit
  - mm/page-writeback.c:wb_position_ratio
  - mm/page-writeback.c:wb_position_ratio
```
```
In mm/vmstat.c (c00000000039a288)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - mm/vmstat.c:unusable_show_print
  - mm/vmstat.c:__fragmentation_index
  - mm/vmstat.c:__fragmentation_index
```
```
In mm/slub.c (c000000000423318)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - mm/slub.c:list_locations
```
```
In fs/ext4/extents_status.c (c000000000590248)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
```
```
In fs/ext4/super.c (c0000000005de3f8)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_es_shrink
  - fs/ext4/super.c:trace_event_raw_event_ext4_es_shrink
```
```
In fs/jbd2/journal.c (c00000000060ee70)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_seq_info_show
```
```
In security/keys/proc.c (c000000000686724)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - security/keys/proc.c:proc_keys_show
  - security/keys/proc.c:proc_keys_show
  - security/keys/proc.c:proc_keys_show
  - security/keys/proc.c:proc_keys_show
```
```
In block/blk-sysfs.c (c00000000077a180)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_wb_lat_show
```
```
In block/blk-stat.c (c00000000078c9d4)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - block/blk-stat.c:blk_stat_timer_fn
```
```
In block/genhd.c (c000000000793f38)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
```
```
In block/partition-generic.c (c000000000795f98)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
```
```
In block/partitions/efi.c (c0000000007a2f50)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:find_valid_gpt
  - block/partitions/efi.c:read_lba
```
```
In block/blk-wbt.c (c0000000007c1218)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - block/blk-wbt.c:rwb_arm_timer
  - block/blk-wbt.c:perf_trace_wbt_step
  - block/blk-wbt.c:perf_trace_wbt_lat
  - block/blk-wbt.c:trace_event_raw_event_wbt_step
  - block/blk-wbt.c:trace_event_raw_event_wbt_lat
```
```
In lib/kstrtox.c (c0000000007e0a70)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - lib/kstrtox.c:_parse_integer
```
```
In drivers/nvdimm/namespace_devs.c (c000000000a0bac8)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:__size_store
```
```
In drivers/nvdimm/badrange.c (c000000000a1262c)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - drivers/nvdimm/badrange.c:__add_badblock_range
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (0)
Location: include/linux/math64.h:123
Inline: True
```
```
In drivers/cpufreq/cpufreq.c (c000000000c0fb3c)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:get_cpu_idle_time
  - drivers/cpufreq/cpufreq.c:get_cpu_idle_time
```
```
In drivers/cpufreq/cpufreq_governor.c (c000000000c1a284)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:dbs_update
```
```
In drivers/cpuidle/governors/menu.c (c000000000c21180)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - drivers/cpuidle/governors/menu.c:menu_select
```
```
In drivers/devfreq/governor_simpleondemand.c (c000000000c662c4)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - drivers/devfreq/governor_simpleondemand.c:devfreq_simple_ondemand_func
  - drivers/devfreq/governor_simpleondemand.c:devfreq_simple_ondemand_func
```
```
In net/ipv4/tcp.c (c000000000d79580)
Location: include/linux/math64.h:123
Inline: True
```
```
In net/ipv4/tcp_input.c (c000000000d8b3e0)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_synack_rtt_meas
  - net/ipv4/tcp_input.c:tcp_cwnd_reduction
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
```
In net/ipv4/tcp_output.c (c000000000d94ecc)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_window_probe
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_established_options
```
```
In net/ipv4/tcp_timer.c (c000000000d962c0)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (c000000000d9d768)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/tcp_minisocks.c (c000000000d9e6ec)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
```
```
In net/ipv4/tcp_rate.c (c000000000da4b38)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp_rate.c:tcp_rate_skb_delivered
  - net/ipv4/tcp_rate.c:tcp_rate_skb_sent
```
```
In net/ipv4/tcp_recovery.c (c000000000da4f28)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_detect_loss
```
```
In net/ipv4/syncookies.c (c000000000df02bc)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_init_timestamp
```
```
In net/ipv6/tcp_ipv6.c (c000000000e6c72c)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
```
```
In net/xdp/xdp_umem.c (c000000000ec1218)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_create
```
```
In lib/vsprintf.c (c000000000edbeac)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - lib/vsprintf.c:vsscanf
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
In kernel/sched/cputime.c (ffffffe0000edb26)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - kernel/sched/cputime.c:cputime_adjust
```
```
In kernel/sched/fair.c (ffffffe0000ef340)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/fair.c:reweight_entity
  - kernel/sched/fair.c:reweight_entity
```
```
In kernel/sched/rt.c (ffffffe0000f7b32)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - kernel/sched/rt.c:do_balance_runtime
```
```
In kernel/sched/pelt.c (ffffffe00010309a)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - kernel/sched/pelt.c:update_dl_rq_load_avg
  - kernel/sched/pelt.c:update_dl_rq_load_avg
  - kernel/sched/pelt.c:update_rt_rq_load_avg
  - kernel/sched/pelt.c:update_rt_rq_load_avg
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_blocked_se
  - kernel/sched/pelt.c:__update_load_avg_blocked_se
```
```
In kernel/sched/psi.c (ffffffe000108f44)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_trigger_destroy
  - kernel/sched/psi.c:update_averages
  - kernel/sched/psi.c:update_averages
  - kernel/sched/psi.c:collect_percpu_times
```
```
In kernel/time/time.c (ffffffe00012a53c)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - kernel/time/time.c:nsecs_to_jiffies
  - kernel/time/time.c:nsec_to_clock_t
  - kernel/time/time.c:jiffies_64_to_clock_t
  - kernel/time/time.c:clock_t_to_jiffies
  - kernel/time/time.c:jiffies_to_clock_t
```
```
In kernel/time/ntp.c (ffffffe000131d90)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - kernel/time/ntp.c:ntp_update_frequency
```
```
In kernel/taskstats.c (ffffffe00016e782)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_user_cmd
  - kernel/taskstats.c:taskstats_user_cmd
```
```
In kernel/tsacct.c (ffffffe00016ee2a)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/tsacct.c:bacct_add_tsk
```
```
In kernel/trace/trace_hwlat.c (ffffffe0001894be)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/trace/trace_hwlat.c:kthread_fn
```
```
In kernel/bpf/verifier.c (ffffffe0001acfa6)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
```
```
In kernel/events/core.c (ffffffe0001cab2a)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - kernel/events/core.c:perf_cpu_time_max_percent_handler
  - kernel/events/core.c:perf_proc_update_handler
```
```
In mm/page-writeback.c (ffffffe0001dee58)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:wb_update_dirty_ratelimit
  - mm/page-writeback.c:wb_position_ratio
  - mm/page-writeback.c:wb_position_ratio
```
```
In mm/vmstat.c (ffffffe0001f4166)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - mm/vmstat.c:unusable_show_print
  - mm/vmstat.c:__fragmentation_index
  - mm/vmstat.c:__fragmentation_index
```
```
In mm/slub.c (ffffffe000238da4)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - mm/slub.c:list_locations
```
```
In fs/ext4/extents_status.c (ffffffe0002fc666)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
```
```
In fs/ext4/super.c (ffffffe00032c6e4)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_es_shrink
  - fs/ext4/super.c:trace_event_raw_event_ext4_es_shrink
```
```
In fs/jbd2/journal.c (ffffffe00034aff0)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_seq_info_show
```
```
In security/keys/proc.c (ffffffe000396a28)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - security/keys/proc.c:proc_keys_show
  - security/keys/proc.c:proc_keys_show
  - security/keys/proc.c:proc_keys_show
  - security/keys/proc.c:proc_keys_show
```
```
In block/blk-sysfs.c (ffffffe00042711e)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_wb_lat_show
```
```
In block/blk-stat.c (ffffffe000432cb0)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - block/blk-stat.c:blk_stat_timer_fn
```
```
In block/genhd.c (ffffffe000437016)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
```
```
In block/partition-generic.c (ffffffe0004387b4)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
```
```
In block/partitions/efi.c (ffffffe00044174c)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:read_lba
```
```
In block/blk-wbt.c (ffffffe0004537e2)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - block/blk-wbt.c:rwb_arm_timer
  - block/blk-wbt.c:perf_trace_wbt_step
  - block/blk-wbt.c:perf_trace_wbt_lat
  - block/blk-wbt.c:trace_event_raw_event_wbt_step
  - block/blk-wbt.c:trace_event_raw_event_wbt_lat
```
```
In lib/kstrtox.c (ffffffe0004666e6)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - lib/kstrtox.c:_parse_integer
```
```
In drivers/clk/analogbits/wrpll-cln28hpc.c (ffffffe0005155a0)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - drivers/clk/analogbits/wrpll-cln28hpc.c:wrpll_calc_output_rate
  - drivers/clk/analogbits/wrpll-cln28hpc.c:wrpll_configure_for_rate
  - drivers/clk/analogbits/wrpll-cln28hpc.c:wrpll_configure_for_rate
  - drivers/clk/analogbits/wrpll-cln28hpc.c:wrpll_configure_for_rate
  - drivers/clk/analogbits/wrpll-cln28hpc.c:wrpll_configure_for_rate
```
```
In drivers/clk/sifive/fu540-prci.c (0)
Location: include/linux/math64.h:123
Inline: True
```
```
In drivers/nvdimm/namespace_devs.c (ffffffe0005c9884)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:__size_store
```
```
In drivers/nvdimm/badrange.c (ffffffe0005cd718)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - drivers/nvdimm/badrange.c:__add_badblock_range
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffe0006bf446)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/devfreq/governor_simpleondemand.c (ffffffe000730240)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - drivers/devfreq/governor_simpleondemand.c:devfreq_simple_ondemand_func
  - drivers/devfreq/governor_simpleondemand.c:devfreq_simple_ondemand_func
```
```
In net/ipv4/tcp.c (ffffffe0007d52d2)
Location: include/linux/math64.h:123
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffe0007e26e2)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_synack_rtt_meas
  - net/ipv4/tcp_input.c:tcp_cwnd_reduction
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
```
In net/ipv4/tcp_output.c (ffffffe0007e92f6)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_window_probe
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_established_options
```
```
In net/ipv4/tcp_timer.c (ffffffe0007ea03c)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffe0007eeefe)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/tcp_minisocks.c (ffffffe0007efa86)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
```
```
In net/ipv4/tcp_rate.c (ffffffe0007f38a2)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp_rate.c:tcp_rate_skb_delivered
  - net/ipv4/tcp_rate.c:tcp_rate_skb_sent
```
```
In net/ipv4/tcp_recovery.c (ffffffe0007f3b50)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_detect_loss
```
```
In net/ipv4/syncookies.c (ffffffe00082330c)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_init_timestamp
```
```
In net/ipv6/tcp_ipv6.c (ffffffe0008764f6)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
```
```
In net/xdp/xdp_umem.c (ffffffe0008ad7d4)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_create
```
```
In lib/vsprintf.c (ffffffe0008c008a)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - lib/vsprintf.c:vsscanf
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
In arch/x86/kernel/cpu/mshyperv.c (ffffffff828a1b70)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
```
```
In arch/x86/kernel/apic/apic.c (ffffffff828a601a)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:calibrate_APIC_clock
```
```
In kernel/sched/cputime.c (ffffffff810d9cf9)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - kernel/sched/cputime.c:cputime_adjust
```
```
In kernel/sched/fair.c (ffffffff810e7392)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/fair.c:attach_entity_load_avg
  - kernel/sched/fair.c:reweight_entity
  - kernel/sched/fair.c:reweight_entity
```
```
In kernel/sched/rt.c (ffffffff810e87dd)
Location: include/linux/math64.h:123
Inline: True
```
```
In kernel/sched/pelt.c (ffffffff810f377f)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - kernel/sched/pelt.c:update_dl_rq_load_avg
  - kernel/sched/pelt.c:update_dl_rq_load_avg
  - kernel/sched/pelt.c:update_rt_rq_load_avg
  - kernel/sched/pelt.c:update_rt_rq_load_avg
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_blocked_se
  - kernel/sched/pelt.c:__update_load_avg_blocked_se
```
```
In kernel/sched/psi.c (ffffffff810fb1ec)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_trigger_destroy
  - kernel/sched/psi.c:update_averages
  - kernel/sched/psi.c:update_averages
  - kernel/sched/psi.c:collect_percpu_times
```
```
In kernel/time/time.c (ffffffff8112ad45)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - kernel/time/time.c:nsecs_to_jiffies
  - kernel/time/time.c:nsec_to_clock_t
  - kernel/time/time.c:jiffies_64_to_clock_t
  - kernel/time/time.c:clock_t_to_jiffies
  - kernel/time/time.c:jiffies_to_clock_t
```
```
In kernel/time/ntp.c (ffffffff81133f13)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - kernel/time/ntp.c:ntp_update_frequency
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff811817e7)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_summary
```
```
In kernel/taskstats.c (ffffffff8118dace)
Location: include/linux/math64.h:123
Inline: True
```
```
In kernel/tsacct.c (ffffffff8118e2ee)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/tsacct.c:bacct_add_tsk
```
```
In kernel/trace/trace_hwlat.c (ffffffff811ac050)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/trace/trace_hwlat.c:kthread_fn
```
```
In kernel/bpf/verifier.c (ffffffff811e9506)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
```
```
In kernel/events/core.c (ffffffff81208a97)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - kernel/events/core.c:perf_cpu_time_max_percent_handler
  - kernel/events/core.c:perf_proc_update_handler
```
```
In mm/page-writeback.c (ffffffff81225852)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:wb_update_dirty_ratelimit
  - mm/page-writeback.c:wb_position_ratio
  - mm/page-writeback.c:wb_position_ratio
```
```
In mm/vmstat.c (ffffffff8123ef65)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - mm/vmstat.c:unusable_show_print
  - mm/vmstat.c:__fragmentation_index
  - mm/vmstat.c:__fragmentation_index
```
```
In mm/slub.c (ffffffff8129d0e9)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - mm/slub.c:list_locations
```
```
In fs/ext4/extents_status.c (ffffffff81395274)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
```
```
In fs/ext4/super.c (ffffffff813cde56)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_es_shrink
  - fs/ext4/super.c:trace_event_raw_event_ext4_es_shrink
```
```
In fs/jbd2/journal.c (ffffffff813f08dc)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_seq_info_show
```
```
In security/keys/proc.c (ffffffff81445c37)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - security/keys/proc.c:proc_keys_show
  - security/keys/proc.c:proc_keys_show
  - security/keys/proc.c:proc_keys_show
  - security/keys/proc.c:proc_keys_show
```
```
In block/blk-sysfs.c (ffffffff814e069e)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_wb_lat_show
```
```
In block/blk-stat.c (ffffffff814ed503)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - block/blk-stat.c:blk_stat_timer_fn
```
```
In block/genhd.c (ffffffff814f1a85)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
```
```
In block/partition-generic.c (ffffffff814f3101)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
```
```
In block/partitions/efi.c (ffffffff814fcd59)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:read_lba
```
```
In block/blk-wbt.c (ffffffff81511dfc)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - block/blk-wbt.c:rwb_arm_timer
  - block/blk-wbt.c:perf_trace_wbt_step
  - block/blk-wbt.c:perf_trace_wbt_lat
  - block/blk-wbt.c:trace_event_raw_event_wbt_step
  - block/blk-wbt.c:trace_event_raw_event_wbt_lat
```
```
In lib/kstrtox.c (ffffffff81526035)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - lib/kstrtox.c:_parse_integer
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff8170e0fa)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:__size_store
```
```
In drivers/nvdimm/badrange.c (ffffffff81712af5)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - drivers/nvdimm/badrange.c:__add_badblock_range
```
```
In drivers/nvme/host/pci.c (ffffffff8174dc13)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - drivers/nvme/host/pci.c:nvme_setup_io_queues
  - drivers/nvme/host/pci.c:nvme_setup_io_queues
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81864d05)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:get_cpu_idle_time
  - drivers/cpufreq/cpufreq.c:get_cpu_idle_time
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff8186b806)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:dbs_update
```
```
In drivers/cpuidle/governors/menu.c (ffffffff818745f3)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - drivers/cpuidle/governors/menu.c:menu_select
```
```
In drivers/devfreq/governor_simpleondemand.c (ffffffff8189bd9a)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - drivers/devfreq/governor_simpleondemand.c:devfreq_simple_ondemand_func
  - drivers/devfreq/governor_simpleondemand.c:devfreq_simple_ondemand_func
```
```
In net/ipv4/tcp.c (ffffffff8195e173)
Location: include/linux/math64.h:123
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff8196da5d)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_synack_rtt_meas
  - net/ipv4/tcp_input.c:tcp_cwnd_reduction
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
```
In net/ipv4/tcp_output.c (ffffffff81975265)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_window_probe
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_established_options
```
```
In net/ipv4/tcp_timer.c (ffffffff81975efe)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8197b6fc)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/tcp_minisocks.c (ffffffff8197c629)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
```
```
In net/ipv4/tcp_rate.c (ffffffff81980526)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp_rate.c:tcp_rate_skb_delivered
  - net/ipv4/tcp_rate.c:tcp_rate_skb_sent
```
```
In net/ipv4/tcp_recovery.c (ffffffff819807d0)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_detect_loss
```
```
In net/ipv4/syncookies.c (ffffffff819b58d2)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_init_timestamp
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a10353)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
```
```
In net/xdp/xdp_umem.c (ffffffff81a4bdcb)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_create
```
```
In lib/vsprintf.c (ffffffff81a5a73e)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - lib/vsprintf.c:vsscanf
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
In arch/x86/kernel/cpu/mshyperv.c (ffffffff82899c5f)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8289e158)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:calibrate_APIC_clock
```
```
In kernel/sched/cputime.c (ffffffff810c8779)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - kernel/sched/cputime.c:cputime_adjust
```
```
In kernel/sched/fair.c (ffffffff810d6532)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/fair.c:attach_entity_load_avg
  - kernel/sched/fair.c:reweight_entity
  - kernel/sched/fair.c:reweight_entity
```
```
In kernel/sched/rt.c (ffffffff810d81dd)
Location: include/linux/math64.h:123
Inline: True
```
```
In kernel/sched/pelt.c (ffffffff810e388f)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - kernel/sched/pelt.c:update_dl_rq_load_avg
  - kernel/sched/pelt.c:update_dl_rq_load_avg
  - kernel/sched/pelt.c:update_rt_rq_load_avg
  - kernel/sched/pelt.c:update_rt_rq_load_avg
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_blocked_se
  - kernel/sched/pelt.c:__update_load_avg_blocked_se
```
```
In kernel/sched/psi.c (ffffffff810eb40c)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_trigger_destroy
  - kernel/sched/psi.c:update_averages
  - kernel/sched/psi.c:update_averages
  - kernel/sched/psi.c:collect_percpu_times
```
```
In kernel/time/time.c (ffffffff8111d5b5)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - kernel/time/time.c:nsecs_to_jiffies
  - kernel/time/time.c:nsec_to_clock_t
  - kernel/time/time.c:jiffies_64_to_clock_t
  - kernel/time/time.c:clock_t_to_jiffies
  - kernel/time/time.c:jiffies_to_clock_t
```
```
In kernel/time/ntp.c (ffffffff81126973)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - kernel/time/ntp.c:ntp_update_frequency
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff81174927)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_summary
```
```
In kernel/taskstats.c (ffffffff81180be8)
Location: include/linux/math64.h:123
Inline: True
```
```
In kernel/tsacct.c (ffffffff8118141b)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/tsacct.c:bacct_add_tsk
```
```
In kernel/trace/trace_hwlat.c (ffffffff8119ef3a)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/trace/trace_hwlat.c:kthread_fn
```
```
In kernel/bpf/verifier.c (ffffffff811dc2c6)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
```
```
In kernel/events/core.c (ffffffff811fb827)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - kernel/events/core.c:perf_cpu_time_max_percent_handler
  - kernel/events/core.c:perf_proc_update_handler
```
```
In mm/page-writeback.c (ffffffff812189f2)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:wb_update_dirty_ratelimit
  - mm/page-writeback.c:wb_position_ratio
  - mm/page-writeback.c:wb_position_ratio
```
```
In mm/vmstat.c (ffffffff81231f65)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - mm/vmstat.c:unusable_show_print
  - mm/vmstat.c:__fragmentation_index
  - mm/vmstat.c:__fragmentation_index
```
```
In mm/slub.c (ffffffff8128ec79)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - mm/slub.c:list_locations
```
```
In fs/ext4/extents_status.c (ffffffff81385d04)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
```
```
In fs/ext4/super.c (ffffffff813be8d6)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_es_shrink
  - fs/ext4/super.c:trace_event_raw_event_ext4_es_shrink
```
```
In fs/jbd2/journal.c (ffffffff813e135c)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_seq_info_show
```
```
In security/keys/proc.c (ffffffff81436687)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - security/keys/proc.c:proc_keys_show
  - security/keys/proc.c:proc_keys_show
  - security/keys/proc.c:proc_keys_show
  - security/keys/proc.c:proc_keys_show
```
```
In block/blk-sysfs.c (ffffffff814d103e)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_wb_lat_show
```
```
In block/blk-stat.c (ffffffff814dda53)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - block/blk-stat.c:blk_stat_timer_fn
```
```
In block/genhd.c (ffffffff814e1fb5)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
```
```
In block/partition-generic.c (ffffffff814e3611)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
```
```
In block/partitions/efi.c (ffffffff814ed269)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:read_lba
```
```
In block/blk-wbt.c (ffffffff8150211c)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - block/blk-wbt.c:rwb_arm_timer
  - block/blk-wbt.c:perf_trace_wbt_step
  - block/blk-wbt.c:perf_trace_wbt_lat
  - block/blk-wbt.c:trace_event_raw_event_wbt_step
  - block/blk-wbt.c:trace_event_raw_event_wbt_lat
```
```
In lib/kstrtox.c (ffffffff81516315)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - lib/kstrtox.c:_parse_integer
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff816e1b7a)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:__size_store
```
```
In drivers/nvdimm/badrange.c (ffffffff816e6575)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - drivers/nvdimm/badrange.c:__add_badblock_range
```
```
In drivers/nvdimm/btt.c (ffffffff816ecf40)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - drivers/nvdimm/btt.c:btt_write_pg
  - drivers/nvdimm/btt.c:btt_read_pg
```
```
In drivers/nvdimm/blk.c (ffffffff816eeec7)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - drivers/nvdimm/blk.c:nd_blk_probe
```
```
In drivers/nvme/host/pci.c (ffffffff8172dab3)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - drivers/nvme/host/pci.c:nvme_setup_io_queues
  - drivers/nvme/host/pci.c:nvme_setup_io_queues
```
```
In drivers/cpufreq/cpufreq.c (ffffffff8182d9b5)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:get_cpu_idle_time
  - drivers/cpufreq/cpufreq.c:get_cpu_idle_time
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff818344b6)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:dbs_update
```
```
In drivers/cpuidle/governors/menu.c (ffffffff8183e4a3)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - drivers/cpuidle/governors/menu.c:menu_select
```
```
In drivers/devfreq/governor_simpleondemand.c (ffffffff8185926a)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - drivers/devfreq/governor_simpleondemand.c:devfreq_simple_ondemand_func
  - drivers/devfreq/governor_simpleondemand.c:devfreq_simple_ondemand_func
```
```
In net/ipv4/tcp.c (ffffffff81917c63)
Location: include/linux/math64.h:123
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff8192754d)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_synack_rtt_meas
  - net/ipv4/tcp_input.c:tcp_cwnd_reduction
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
```
In net/ipv4/tcp_output.c (ffffffff8192ed25)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_window_probe
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_established_options
```
```
In net/ipv4/tcp_timer.c (ffffffff8192f9be)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819351bc)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819360e9)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
```
```
In net/ipv4/tcp_rate.c (ffffffff81939fe6)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp_rate.c:tcp_rate_skb_delivered
  - net/ipv4/tcp_rate.c:tcp_rate_skb_sent
```
```
In net/ipv4/tcp_recovery.c (ffffffff8193a290)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_detect_loss
```
```
In net/ipv4/syncookies.c (ffffffff819726c2)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_init_timestamp
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819cd113)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
```
```
In net/xdp/xdp_umem.c (ffffffff81a089bb)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_create
```
```
In lib/vsprintf.c (ffffffff81a1781e)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - lib/vsprintf.c:vsscanf
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
In arch/x86/kernel/cpu/mshyperv.c (ffffffff828b4b33)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
```
```
In arch/x86/kernel/apic/apic.c (ffffffff828b8f2a)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:calibrate_APIC_clock
```
```
In kernel/sched/cputime.c (ffffffff810d6039)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - kernel/sched/cputime.c:cputime_adjust
```
```
In kernel/sched/fair.c (ffffffff810e3762)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/fair.c:attach_entity_load_avg
  - kernel/sched/fair.c:reweight_entity
  - kernel/sched/fair.c:reweight_entity
```
```
In kernel/sched/rt.c (ffffffff810e534d)
Location: include/linux/math64.h:123
Inline: True
```
```
In kernel/sched/pelt.c (ffffffff810f08af)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - kernel/sched/pelt.c:update_dl_rq_load_avg
  - kernel/sched/pelt.c:update_dl_rq_load_avg
  - kernel/sched/pelt.c:update_rt_rq_load_avg
  - kernel/sched/pelt.c:update_rt_rq_load_avg
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_blocked_se
  - kernel/sched/pelt.c:__update_load_avg_blocked_se
```
```
In kernel/sched/psi.c (ffffffff810f83ac)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_trigger_destroy
  - kernel/sched/psi.c:update_averages
  - kernel/sched/psi.c:update_averages
  - kernel/sched/psi.c:collect_percpu_times
```
```
In kernel/time/time.c (ffffffff81128a65)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - kernel/time/time.c:nsecs_to_jiffies
  - kernel/time/time.c:nsec_to_clock_t
  - kernel/time/time.c:jiffies_64_to_clock_t
  - kernel/time/time.c:clock_t_to_jiffies
  - kernel/time/time.c:jiffies_to_clock_t
```
```
In kernel/time/ntp.c (ffffffff81131c33)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - kernel/time/ntp.c:ntp_update_frequency
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff8117f5b7)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_summary
```
```
In kernel/taskstats.c (ffffffff8118b89e)
Location: include/linux/math64.h:123
Inline: True
```
```
In kernel/tsacct.c (ffffffff8118c0be)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/tsacct.c:bacct_add_tsk
```
```
In kernel/trace/trace_hwlat.c (ffffffff811a9e20)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/trace/trace_hwlat.c:kthread_fn
```
```
In kernel/bpf/verifier.c (ffffffff811e72d6)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
```
```
In kernel/events/core.c (ffffffff81206837)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - kernel/events/core.c:perf_cpu_time_max_percent_handler
  - kernel/events/core.c:perf_proc_update_handler
```
```
In mm/page-writeback.c (ffffffff812235f2)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:wb_update_dirty_ratelimit
  - mm/page-writeback.c:wb_position_ratio
  - mm/page-writeback.c:wb_position_ratio
```
```
In mm/vmstat.c (ffffffff8123cd05)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - mm/vmstat.c:unusable_show_print
  - mm/vmstat.c:__fragmentation_index
  - mm/vmstat.c:__fragmentation_index
```
```
In mm/slub.c (ffffffff8129aef9)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - mm/slub.c:list_locations
```
```
In fs/ext4/extents_status.c (ffffffff81392bd4)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
```
```
In fs/ext4/super.c (ffffffff813cb2e6)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_es_shrink
  - fs/ext4/super.c:trace_event_raw_event_ext4_es_shrink
```
```
In fs/jbd2/journal.c (ffffffff813edc5c)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_seq_info_show
```
```
In security/keys/proc.c (ffffffff81441cd7)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - security/keys/proc.c:proc_keys_show
  - security/keys/proc.c:proc_keys_show
  - security/keys/proc.c:proc_keys_show
  - security/keys/proc.c:proc_keys_show
```
```
In block/blk-sysfs.c (ffffffff814dc72e)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_wb_lat_show
```
```
In block/blk-stat.c (ffffffff814e9593)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - block/blk-stat.c:blk_stat_timer_fn
```
```
In block/genhd.c (ffffffff814edb15)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
```
```
In block/partition-generic.c (ffffffff814ef191)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
```
```
In block/partitions/efi.c (ffffffff814f8de9)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:read_lba
```
```
In block/blk-wbt.c (ffffffff8150de8c)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - block/blk-wbt.c:rwb_arm_timer
  - block/blk-wbt.c:perf_trace_wbt_step
  - block/blk-wbt.c:perf_trace_wbt_lat
  - block/blk-wbt.c:trace_event_raw_event_wbt_step
  - block/blk-wbt.c:trace_event_raw_event_wbt_lat
```
```
In lib/kstrtox.c (ffffffff815220c5)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - lib/kstrtox.c:_parse_integer
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff8174ceca)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:__size_store
```
```
In drivers/nvdimm/badrange.c (ffffffff817518c5)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - drivers/nvdimm/badrange.c:__add_badblock_range
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff8186b0e5)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/cpufreq/cpufreq.c (ffffffff818b5a95)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:get_cpu_idle_time
  - drivers/cpufreq/cpufreq.c:get_cpu_idle_time
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff818bc596)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:dbs_update
```
```
In drivers/cpuidle/governors/menu.c (ffffffff818c60c3)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - drivers/cpuidle/governors/menu.c:menu_select
```
```
In drivers/devfreq/governor_simpleondemand.c (ffffffff818eb48a)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - drivers/devfreq/governor_simpleondemand.c:devfreq_simple_ondemand_func
  - drivers/devfreq/governor_simpleondemand.c:devfreq_simple_ondemand_func
```
```
In net/ipv4/tcp.c (ffffffff819c8943)
Location: include/linux/math64.h:123
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff819d822d)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_synack_rtt_meas
  - net/ipv4/tcp_input.c:tcp_cwnd_reduction
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
```
In net/ipv4/tcp_output.c (ffffffff819dfa35)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_window_probe
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_established_options
```
```
In net/ipv4/tcp_timer.c (ffffffff819e06ce)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819e5ecc)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819e6df9)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
```
```
In net/ipv4/tcp_rate.c (ffffffff819eacf6)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp_rate.c:tcp_rate_skb_delivered
  - net/ipv4/tcp_rate.c:tcp_rate_skb_sent
```
```
In net/ipv4/tcp_recovery.c (ffffffff819eafa0)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_detect_loss
```
```
In net/ipv4/syncookies.c (ffffffff81a20172)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_init_timestamp
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a7add3)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
```
```
In net/xdp/xdp_umem.c (ffffffff81ab7c7b)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_create
```
```
In lib/vsprintf.c (ffffffff81ac6b2e)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - lib/vsprintf.c:vsscanf
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
In arch/x86/kernel/cpu/mshyperv.c (ffffffff828b4b54)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
```
```
In arch/x86/kernel/apic/apic.c (ffffffff828b902b)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:calibrate_APIC_clock
```
```
In kernel/sched/cputime.c (ffffffff810e1949)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - kernel/sched/cputime.c:cputime_adjust
```
```
In kernel/sched/fair.c (ffffffff810ef34f)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/fair.c:attach_entity_load_avg
  - kernel/sched/fair.c:reweight_entity
  - kernel/sched/fair.c:reweight_entity
```
```
In kernel/sched/rt.c (ffffffff810ef831)
Location: include/linux/math64.h:123
Inline: True
```
```
In kernel/sched/pelt.c (ffffffff810fb94f)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - kernel/sched/pelt.c:update_dl_rq_load_avg
  - kernel/sched/pelt.c:update_dl_rq_load_avg
  - kernel/sched/pelt.c:update_rt_rq_load_avg
  - kernel/sched/pelt.c:update_rt_rq_load_avg
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_blocked_se
  - kernel/sched/pelt.c:__update_load_avg_blocked_se
```
```
In kernel/sched/psi.c (ffffffff811034ec)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_trigger_destroy
  - kernel/sched/psi.c:update_averages
  - kernel/sched/psi.c:update_averages
  - kernel/sched/psi.c:collect_percpu_times
```
```
In kernel/time/time.c (ffffffff811350b5)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - kernel/time/time.c:nsecs_to_jiffies
  - kernel/time/time.c:nsec_to_clock_t
  - kernel/time/time.c:jiffies_64_to_clock_t
  - kernel/time/time.c:jiffies_to_clock_t
```
```
In kernel/time/ntp.c (ffffffff8113e653)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - kernel/time/ntp.c:ntp_update_frequency
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff8118ced7)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_summary
```
```
In kernel/taskstats.c (ffffffff81199213)
Location: include/linux/math64.h:123
Inline: True
```
```
In kernel/tsacct.c (ffffffff81199a52)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/tsacct.c:bacct_add_tsk
```
```
In kernel/trace/trace_hwlat.c (ffffffff811b7c60)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/trace/trace_hwlat.c:kthread_fn
```
```
In kernel/bpf/verifier.c (ffffffff811f5686)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
```
```
In kernel/events/core.c (ffffffff812155a7)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - kernel/events/core.c:perf_cpu_time_max_percent_handler
  - kernel/events/core.c:perf_proc_update_handler
```
```
In mm/page-writeback.c (ffffffff812327ec)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:wb_update_dirty_ratelimit
  - mm/page-writeback.c:wb_position_ratio
  - mm/page-writeback.c:wb_position_ratio
```
```
In mm/vmstat.c (ffffffff8124c435)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - mm/vmstat.c:unusable_show_print
  - mm/vmstat.c:__fragmentation_index
  - mm/vmstat.c:__fragmentation_index
```
```
In mm/slub.c (ffffffff812aadd9)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - mm/slub.c:list_locations
```
```
In fs/ext4/extents_status.c (ffffffff813a6baf)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
  - fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show
```
```
In fs/ext4/super.c (ffffffff813e0536)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_es_shrink
  - fs/ext4/super.c:trace_event_raw_event_ext4_es_shrink
```
```
In fs/jbd2/journal.c (ffffffff8140377c)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_seq_info_show
```
```
In security/keys/proc.c (ffffffff8145900f)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - security/keys/proc.c:proc_keys_show
  - security/keys/proc.c:proc_keys_show
  - security/keys/proc.c:proc_keys_show
  - security/keys/proc.c:proc_keys_show
```
```
In block/blk-sysfs.c (ffffffff814f559e)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_wb_lat_show
```
```
In block/blk-stat.c (ffffffff81502593)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - block/blk-stat.c:blk_stat_timer_fn
```
```
In block/genhd.c (ffffffff81506ba2)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
```
```
In block/partition-generic.c (ffffffff81508221)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
```
```
In block/partitions/efi.c (ffffffff81511e49)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:read_lba
```
```
In block/blk-wbt.c (ffffffff815274ac)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - block/blk-wbt.c:rwb_arm_timer
  - block/blk-wbt.c:perf_trace_wbt_step
  - block/blk-wbt.c:perf_trace_wbt_lat
  - block/blk-wbt.c:trace_event_raw_event_wbt_step
  - block/blk-wbt.c:trace_event_raw_event_wbt_lat
```
```
In lib/kstrtox.c (ffffffff8153ba45)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - lib/kstrtox.c:_parse_integer
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff8176834a)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:__size_store
```
```
In drivers/nvdimm/badrange.c (ffffffff8176ce25)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - drivers/nvdimm/badrange.c:__add_badblock_range
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81885075)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/cpufreq/cpufreq.c (ffffffff818d1d45)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:get_cpu_idle_time
  - drivers/cpufreq/cpufreq.c:get_cpu_idle_time
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff818d8886)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:dbs_update
```
```
In drivers/cpuidle/governors/menu.c (ffffffff818e2523)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - drivers/cpuidle/governors/menu.c:menu_select
```
```
In drivers/devfreq/governor_simpleondemand.c (ffffffff8190c50a)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - drivers/devfreq/governor_simpleondemand.c:devfreq_simple_ondemand_func
  - drivers/devfreq/governor_simpleondemand.c:devfreq_simple_ondemand_func
```
```
In net/ipv4/tcp.c (ffffffff819d2493)
Location: include/linux/math64.h:123
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff819e1e6d)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_synack_rtt_meas
  - net/ipv4/tcp_input.c:tcp_cwnd_reduction
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
```
In net/ipv4/tcp_output.c (ffffffff819e96e5)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_window_probe
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_established_options
```
```
In net/ipv4/tcp_timer.c (ffffffff819ea38e)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819efb8c)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819f0ac9)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
```
```
In net/ipv4/tcp_rate.c (ffffffff819f4b76)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp_rate.c:tcp_rate_skb_delivered
  - net/ipv4/tcp_rate.c:tcp_rate_skb_sent
```
```
In net/ipv4/tcp_recovery.c (ffffffff819f4e20)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_detect_loss
```
```
In net/ipv4/syncookies.c (ffffffff81a2b672)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_init_timestamp
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a87613)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
```
```
In net/xdp/xdp_umem.c (ffffffff81ac409b)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_create
```
```
In lib/vsprintf.c (ffffffff81ad300e)
Location: include/linux/math64.h:123
Inline: True
Inline callers:
  - lib/vsprintf.c:vsscanf
```
</details>
</li>
</ul>

## Differences
