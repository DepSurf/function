# Function: <code>strstrip</code>

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
In kernel/sched/core.c (ffffffff810a69e5)
Location: include/linux/string.h:68
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_feat_write
```
```
In kernel/cgroup.c (ffffffff81115295)
Location: include/linux/string.h:68
Inline: True
Inline callers:
  - kernel/cgroup.c:cgroup_release_agent_write
  - kernel/cgroup.c:__cgroup_procs_write
  - kernel/cgroup.c:cgroup_subtree_control_write
```
```
In kernel/cgroup_freezer.c (ffffffff8111a123)
Location: include/linux/string.h:68
Inline: True
Inline callers:
  - kernel/cgroup_freezer.c:freezer_write
```
```
In kernel/cgroup_pids.c (ffffffff8111a32c)
Location: include/linux/string.h:68
Inline: True
Inline callers:
  - kernel/cgroup_pids.c:pids_max_write
```
```
In kernel/cpuset.c (ffffffff8111c524)
Location: include/linux/string.h:68
Inline: True
Inline callers:
  - kernel/cpuset.c:cpuset_write_resmask
```
```
In kernel/trace/ftrace.c (ffffffff81145723)
Location: include/linux/string.h:68
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_pid_write
```
```
In kernel/trace/trace.c (ffffffff8114e394)
Location: include/linux/string.h:68
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_clock_write
  - kernel/trace/trace.c:trace_set_options
```
```
In kernel/trace/blktrace.c (ffffffff8115ca06)
Location: include/linux/string.h:68
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
```
```
In kernel/trace/trace_events_filter.c (ffffffff81164f39)
Location: include/linux/string.h:68
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
```
```
In mm/zswap.c (ffffffff811d82e0)
Location: include/linux/string.h:68
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_param_set
```
```
In mm/memcontrol.c (ffffffff811f9adc)
Location: include/linux/string.h:68
Inline: True
Inline callers:
  - mm/memcontrol.c:memory_low_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:mem_cgroup_write
```
```
In mm/hugetlb_cgroup.c (ffffffff81200e9a)
Location: include/linux/string.h:68
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_write
```
```
In fs/proc/task_mmu.c (ffffffff81277036)
Location: include/linux/string.h:68
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
```
```
In fs/proc/base.c (ffffffff8127abb4)
Location: include/linux/string.h:68
Inline: True
Inline callers:
  - fs/proc/base.c:oom_score_adj_write
  - fs/proc/base.c:sched_autogroup_write
  - fs/proc/base.c:oom_adj_write
```
```
In security/device_cgroup.c (ffffffff81395aea)
Location: include/linux/string.h:68
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_access_write
```
```
In block/elevator.c (ffffffff813b36c1)
Location: include/linux/string.h:68
Inline: True
Inline callers:
  - block/elevator.c:__elevator_change
```
```
In drivers/ata/libata-core.c (ffffffff81faf6c4)
Location: include/linux/string.h:68
Inline: True
```
```
In net/ipv4/tcp_memcontrol.c (ffffffff817acf61)
Location: include/linux/string.h:68
Inline: True
Inline callers:
  - net/ipv4/tcp_memcontrol.c:tcp_cgroup_write
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
In kernel/sched/debug.c (ffffffff810c9219)
Location: include/linux/string.h:69
Inline: True
Inline callers:
  - kernel/sched/debug.c:sched_feat_write
```
```
In kernel/cgroup.c (ffffffff8111e854)
Location: include/linux/string.h:69
Inline: True
Inline callers:
  - kernel/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup.c:cgroup_release_agent_write
```
```
In kernel/cgroup_freezer.c (ffffffff81121f33)
Location: include/linux/string.h:69
Inline: True
Inline callers:
  - kernel/cgroup_freezer.c:freezer_write
```
```
In kernel/cgroup_pids.c (ffffffff8112215c)
Location: include/linux/string.h:69
Inline: True
Inline callers:
  - kernel/cgroup_pids.c:pids_max_write
```
```
In kernel/cpuset.c (ffffffff81124424)
Location: include/linux/string.h:69
Inline: True
Inline callers:
  - kernel/cpuset.c:cpuset_write_resmask
```
```
In kernel/trace/trace.c (ffffffff81157003)
Location: include/linux/string.h:69
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_clock_write
  - kernel/trace/trace.c:trace_set_options
```
```
In kernel/trace/blktrace.c (ffffffff811673bb)
Location: include/linux/string.h:69
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
```
```
In kernel/trace/trace_events_filter.c (ffffffff8116f8c2)
Location: include/linux/string.h:69
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
```
```
In mm/zswap.c (ffffffff811f6430)
Location: include/linux/string.h:69
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_param_set
```
```
In mm/memcontrol.c (ffffffff8121d87c)
Location: include/linux/string.h:69
Inline: True
Inline callers:
  - mm/memcontrol.c:swap_max_write
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:memory_low_write
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:mem_cgroup_write
```
```
In mm/hugetlb_cgroup.c (ffffffff8122560a)
Location: include/linux/string.h:69
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_write
```
```
In fs/proc/task_mmu.c (ffffffff812a359a)
Location: include/linux/string.h:69
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
```
```
In fs/proc/base.c (ffffffff812a9730)
Location: include/linux/string.h:69
Inline: True
Inline callers:
  - fs/proc/base.c:sched_autogroup_write
  - fs/proc/base.c:oom_score_adj_write
  - fs/proc/base.c:oom_adj_write
```
```
In security/device_cgroup.c (ffffffff813d183a)
Location: include/linux/string.h:69
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_access_write
```
```
In block/elevator.c (ffffffff813f73c1)
Location: include/linux/string.h:69
Inline: True
Inline callers:
  - block/elevator.c:__elevator_change
```
```
In drivers/ata/libata-core.c (ffffffff81fdc10b)
Location: include/linux/string.h:69
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
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff810440e5)
Location: include/linux/string.h:69
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_tasks_write
```
```
In kernel/sched/debug.c (ffffffff810cf239)
Location: include/linux/string.h:69
Inline: True
Inline callers:
  - kernel/sched/debug.c:sched_feat_write
```
```
In kernel/cgroup.c (ffffffff81126be4)
Location: include/linux/string.h:69
Inline: True
Inline callers:
  - kernel/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup.c:cgroup_release_agent_write
```
```
In kernel/cgroup_freezer.c (ffffffff8112a563)
Location: include/linux/string.h:69
Inline: True
Inline callers:
  - kernel/cgroup_freezer.c:freezer_write
```
```
In kernel/cgroup_pids.c (ffffffff8112a78c)
Location: include/linux/string.h:69
Inline: True
Inline callers:
  - kernel/cgroup_pids.c:pids_max_write
```
```
In kernel/cpuset.c (ffffffff8112d5b5)
Location: include/linux/string.h:69
Inline: True
Inline callers:
  - kernel/cpuset.c:cpuset_write_resmask
```
```
In kernel/trace/trace.c (ffffffff81162140)
Location: include/linux/string.h:69
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_clock_write
  - kernel/trace/trace.c:trace_set_options
```
```
In kernel/trace/blktrace.c (ffffffff81171d1b)
Location: include/linux/string.h:69
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
```
```
In kernel/trace/trace_events_filter.c (ffffffff8117b032)
Location: include/linux/string.h:69
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
```
```
In mm/zswap.c (ffffffff81206dc0)
Location: include/linux/string.h:69
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_param_set
```
```
In mm/memcontrol.c (ffffffff8122fddc)
Location: include/linux/string.h:69
Inline: True
Inline callers:
  - mm/memcontrol.c:swap_max_write
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:memory_low_write
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:mem_cgroup_write
```
```
In mm/hugetlb_cgroup.c (ffffffff81237bea)
Location: include/linux/string.h:69
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_write
```
```
In fs/proc/task_mmu.c (ffffffff812b8f7a)
Location: include/linux/string.h:69
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
```
```
In fs/proc/base.c (ffffffff812bf050)
Location: include/linux/string.h:69
Inline: True
Inline callers:
  - fs/proc/base.c:sched_autogroup_write
  - fs/proc/base.c:oom_score_adj_write
  - fs/proc/base.c:oom_adj_write
```
```
In security/device_cgroup.c (ffffffff813e8f6a)
Location: include/linux/string.h:69
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_access_write
```
```
In block/elevator.c (ffffffff81410dd1)
Location: include/linux/string.h:69
Inline: True
Inline callers:
  - block/elevator.c:__elevator_change
```
```
In drivers/ata/libata-core.c (ffffffff82019c41)
Location: include/linux/string.h:69
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
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff81042fd5)
Location: include/linux/string.h:69
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_tasks_write
```
```
In kernel/sched/debug.c (ffffffff810d0372)
Location: include/linux/string.h:69
Inline: True
Inline callers:
  - kernel/sched/debug.c:sched_feat_write
```
```
In kernel/cgroup/cgroup.c (ffffffff81126eae)
Location: include/linux/string.h:69
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:__cgroup_procs_write
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81129067)
Location: include/linux/string.h:69
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write
```
```
In kernel/cgroup/freezer.c (ffffffff8112b283)
Location: include/linux/string.h:69
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:freezer_write
```
```
In kernel/cgroup/pids.c (ffffffff8112b4ac)
Location: include/linux/string.h:69
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_max_write
```
```
In kernel/cgroup/rdma.c (ffffffff8112c031)
Location: include/linux/string.h:69
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
```
```
In kernel/cgroup/cpuset.c (ffffffff8112ebf4)
Location: include/linux/string.h:69
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In kernel/trace/trace.c (ffffffff8116554a)
Location: include/linux/string.h:69
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_clock_write
  - kernel/trace/trace.c:trace_set_options
```
```
In kernel/trace/blktrace.c (ffffffff811750c4)
Location: include/linux/string.h:69
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
```
```
In kernel/trace/trace_events_filter.c (ffffffff8117dced)
Location: include/linux/string.h:69
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
```
```
In mm/zswap.c (ffffffff81212f90)
Location: include/linux/string.h:69
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_param_set
```
```
In mm/memcontrol.c (ffffffff8123b6ec)
Location: include/linux/string.h:69
Inline: True
Inline callers:
  - mm/memcontrol.c:swap_max_write
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:memory_low_write
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:mem_cgroup_write
```
```
In mm/hugetlb_cgroup.c (ffffffff8124385a)
Location: include/linux/string.h:69
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_write
```
```
In fs/proc/task_mmu.c (ffffffff812c7284)
Location: include/linux/string.h:69
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
```
```
In fs/proc/base.c (ffffffff812cbe1a)
Location: include/linux/string.h:69
Inline: True
Inline callers:
  - fs/proc/base.c:sched_autogroup_write
  - fs/proc/base.c:oom_score_adj_write
  - fs/proc/base.c:oom_adj_write
```
```
In security/device_cgroup.c (ffffffff813f537b)
Location: include/linux/string.h:69
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_access_write
```
```
In block/elevator.c (ffffffff8141f7b3)
Location: include/linux/string.h:69
Inline: True
Inline callers:
  - block/elevator.c:elv_iosched_store
```
```
In block/blk-mq-debugfs.c (ffffffff81459bdc)
Location: include/linux/string.h:69
Inline: True
Inline callers:
  - block/blk-mq-debugfs.c:queue_state_write
```
```
In drivers/ata/libata-core.c (ffffffff820fbc70)
Location: include/linux/string.h:69
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
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff810465a5)
Location: include/linux/string.h:70
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_tasks_write
```
```
In kernel/sched/debug.c (ffffffff810d7d22)
Location: include/linux/string.h:70
Inline: True
Inline callers:
  - kernel/sched/debug.c:sched_feat_write
```
```
In kernel/cgroup/cgroup.c (ffffffff811336e8)
Location: include/linux/string.h:70
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_max_depth_write
  - kernel/cgroup/cgroup.c:cgroup_max_descendants_write
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write_start
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81135ce7)
Location: include/linux/string.h:70
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write
```
```
In kernel/cgroup/freezer.c (ffffffff81138083)
Location: include/linux/string.h:70
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:freezer_write
```
```
In kernel/cgroup/pids.c (ffffffff811382ac)
Location: include/linux/string.h:70
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_max_write
```
```
In kernel/cgroup/rdma.c (ffffffff81138e41)
Location: include/linux/string.h:70
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
```
```
In kernel/cgroup/cpuset.c (ffffffff8113ba94)
Location: include/linux/string.h:70
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In kernel/trace/trace.c (ffffffff8117248a)
Location: include/linux/string.h:70
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_clock_write
  - kernel/trace/trace.c:trace_set_options
```
```
In kernel/trace/blktrace.c (ffffffff811824a7)
Location: include/linux/string.h:70
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
```
```
In kernel/trace/trace_events_filter.c (ffffffff8118b57d)
Location: include/linux/string.h:70
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
```
```
In mm/zswap.c (ffffffff8122dad0)
Location: include/linux/string.h:70
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_param_set
```
```
In mm/memcontrol.c (ffffffff8125af6c)
Location: include/linux/string.h:70
Inline: True
Inline callers:
  - mm/memcontrol.c:swap_max_write
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:memory_low_write
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:mem_cgroup_write
```
```
In mm/hugetlb_cgroup.c (ffffffff812636aa)
Location: include/linux/string.h:70
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_write
```
```
In fs/proc/task_mmu.c (ffffffff812eb0a4)
Location: include/linux/string.h:70
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
```
```
In fs/proc/base.c (ffffffff812f0b2a)
Location: include/linux/string.h:70
Inline: True
Inline callers:
  - fs/proc/base.c:sched_autogroup_write
  - fs/proc/base.c:oom_score_adj_write
  - fs/proc/base.c:oom_adj_write
```
```
In security/device_cgroup.c (ffffffff8141d63b)
Location: include/linux/string.h:70
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_access_write
```
```
In block/elevator.c (ffffffff8144a301)
Location: include/linux/string.h:70
Inline: True
Inline callers:
  - block/elevator.c:elv_iosched_store
```
```
In block/blk-mq-debugfs.c (ffffffff814858ac)
Location: include/linux/string.h:70
Inline: True
Inline callers:
  - block/blk-mq-debugfs.c:queue_state_write
```
```
In drivers/ata/libata-core.c (ffffffff82705313)
Location: include/linux/string.h:70
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
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff81048b6f)
Location: include/linux/string.h:71
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_tasks_write
```
```
In kernel/sched/debug.c (ffffffff810ddcaa)
Location: include/linux/string.h:71
Inline: True
Inline callers:
  - kernel/sched/debug.c:sched_feat_write
```
```
In kernel/cgroup/cgroup.c (ffffffff81141da5)
Location: include/linux/string.h:71
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_max_depth_write
  - kernel/cgroup/cgroup.c:cgroup_max_descendants_write
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write_start
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81145027)
Location: include/linux/string.h:71
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write
```
```
In kernel/cgroup/freezer.c (ffffffff81146855)
Location: include/linux/string.h:71
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:freezer_write
```
```
In kernel/cgroup/pids.c (ffffffff81146bd2)
Location: include/linux/string.h:71
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_max_write
```
```
In kernel/cgroup/rdma.c (ffffffff81147618)
Location: include/linux/string.h:71
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
```
```
In kernel/cgroup/cpuset.c (ffffffff8114a34a)
Location: include/linux/string.h:71
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In kernel/trace/trace.c (ffffffff81185503)
Location: include/linux/string.h:71
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_clock_write
  - kernel/trace/trace.c:trace_set_options
```
```
In kernel/trace/blktrace.c (ffffffff81191613)
Location: include/linux/string.h:71
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
```
```
In kernel/trace/trace_events_filter.c (ffffffff81199ec1)
Location: include/linux/string.h:71
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
```
```
In kernel/trace/trace_events_hist.c (ffffffff811a2492)
Location: include/linux/string.h:71
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:parse_action_params
```
```
In mm/zswap.c (ffffffff8124fee5)
Location: include/linux/string.h:71
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_param_set
```
```
In mm/memcontrol.c (ffffffff8127eaf2)
Location: include/linux/string.h:71
Inline: True
Inline callers:
  - mm/memcontrol.c:swap_max_write
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:memory_low_write
  - mm/memcontrol.c:memory_min_write
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:mem_cgroup_write
```
```
In mm/hugetlb_cgroup.c (ffffffff812879a4)
Location: include/linux/string.h:71
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_write
```
```
In fs/proc/task_mmu.c (ffffffff8131723b)
Location: include/linux/string.h:71
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
```
```
In fs/proc/base.c (ffffffff8131d6ea)
Location: include/linux/string.h:71
Inline: True
Inline callers:
  - fs/proc/base.c:sched_autogroup_write
  - fs/proc/base.c:oom_score_adj_write
  - fs/proc/base.c:oom_adj_write
```
```
In security/device_cgroup.c (ffffffff8144f8fb)
Location: include/linux/string.h:71
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_access_write
```
```
In block/elevator.c (ffffffff8147d3f1)
Location: include/linux/string.h:71
Inline: True
Inline callers:
  - block/elevator.c:elv_iosched_store
```
```
In block/blk-mq-debugfs.c (ffffffff814ba76c)
Location: include/linux/string.h:71
Inline: True
Inline callers:
  - block/blk-mq-debugfs.c:queue_state_write
```
```
In drivers/ata/libata-core.c (ffffffff8272f145)
Location: include/linux/string.h:71
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_parse_force_param
  - drivers/ata/libata-core.c:ata_parse_force_param
  - drivers/ata/libata-core.c:ata_parse_force_param
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81058aef)
Location: include/linux/string.h:71
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
```
```
In kernel/sched/debug.c (ffffffff810e8418)
Location: include/linux/string.h:71
Inline: True
Inline callers:
  - kernel/sched/debug.c:sched_feat_write
```
```
In kernel/cgroup/cgroup.c (ffffffff8114d815)
Location: include/linux/string.h:71
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_max_depth_write
  - kernel/cgroup/cgroup.c:cgroup_max_descendants_write
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write_start
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81150b47)
Location: include/linux/string.h:71
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write
```
```
In kernel/cgroup/freezer.c (ffffffff81152525)
Location: include/linux/string.h:71
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:freezer_write
```
```
In kernel/cgroup/pids.c (ffffffff81152752)
Location: include/linux/string.h:71
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_max_write
```
```
In kernel/cgroup/rdma.c (ffffffff81153348)
Location: include/linux/string.h:71
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
```
```
In kernel/cgroup/cpuset.c (ffffffff81156cdf)
Location: include/linux/string.h:71
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In kernel/trace/trace.c (ffffffff81192e33)
Location: include/linux/string.h:71
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_clock_write
  - kernel/trace/trace.c:trace_set_options
```
```
In kernel/trace/blktrace.c (ffffffff8119e883)
Location: include/linux/string.h:71
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
```
```
In kernel/trace/trace_events_filter.c (ffffffff811a8081)
Location: include/linux/string.h:71
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
```
```
In kernel/trace/trace_events_hist.c (ffffffff811b13b4)
Location: include/linux/string.h:71
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:parse_action_params
```
```
In mm/zswap.c (ffffffff812643b5)
Location: include/linux/string.h:71
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_param_set
```
```
In mm/memcontrol.c (ffffffff81293282)
Location: include/linux/string.h:71
Inline: True
Inline callers:
  - mm/memcontrol.c:swap_max_write
  - mm/memcontrol.c:memory_oom_group_write
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:memory_low_write
  - mm/memcontrol.c:memory_min_write
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:mem_cgroup_write
```
```
In mm/hugetlb_cgroup.c (ffffffff8129c8f4)
Location: include/linux/string.h:71
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_write
```
```
In fs/proc/task_mmu.c (ffffffff8132e68b)
Location: include/linux/string.h:71
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
```
```
In fs/proc/base.c (ffffffff8133472a)
Location: include/linux/string.h:71
Inline: True
Inline callers:
  - fs/proc/base.c:sched_autogroup_write
  - fs/proc/base.c:oom_score_adj_write
  - fs/proc/base.c:oom_adj_write
```
```
In security/device_cgroup.c (ffffffff8146c8db)
Location: include/linux/string.h:71
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_access_write
```
```
In block/elevator.c (ffffffff8149acf1)
Location: include/linux/string.h:71
Inline: True
Inline callers:
  - block/elevator.c:elv_iosched_store
```
```
In block/blk-mq-debugfs.c (ffffffff814ce8f9)
Location: include/linux/string.h:71
Inline: True
Inline callers:
  - block/blk-mq-debugfs.c:queue_state_write
```
```
In drivers/ata/libata-core.c (ffffffff828e7b6d)
Location: include/linux/string.h:71
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_parse_force_param
  - drivers/ata/libata-core.c:ata_parse_force_param
  - drivers/ata/libata-core.c:ata_parse_force_param
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105c08f)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
```
```
In kernel/sched/debug.c (ffffffff810f0848)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - kernel/sched/debug.c:sched_feat_write
```
```
In kernel/cgroup/cgroup.c (ffffffff811595d5)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_freeze_write
  - kernel/cgroup/cgroup.c:cgroup_max_depth_write
  - kernel/cgroup/cgroup.c:cgroup_max_descendants_write
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write_start
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8115ca87)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff8115eb85)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_write
```
```
In kernel/cgroup/pids.c (ffffffff8115edb2)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_max_write
```
```
In kernel/cgroup/rdma.c (ffffffff8115f6d8)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
```
```
In kernel/cgroup/cpuset.c (ffffffff8116461f)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In kernel/trace/trace.c (ffffffff811a07b3)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_clock_write
  - kernel/trace/trace.c:trace_set_options
```
```
In kernel/trace/blktrace.c (ffffffff811ac563)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
```
```
In kernel/trace/trace_events_filter.c (ffffffff811b5f95)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
```
```
In kernel/trace/trace_events_hist.c (ffffffff811bf35f)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:parse_action_params
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
```
```
In mm/zswap.c (ffffffff8127f315)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_param_set
```
```
In mm/memcontrol.c (ffffffff812ae242)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - mm/memcontrol.c:swap_max_write
  - mm/memcontrol.c:memory_oom_group_write
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:memory_low_write
  - mm/memcontrol.c:memory_min_write
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:mem_cgroup_write
```
```
In mm/hugetlb_cgroup.c (ffffffff812b7ab4)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_write
```
```
In fs/proc/task_mmu.c (ffffffff813571bb)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
```
```
In fs/proc/base.c (ffffffff8135cb4a)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - fs/proc/base.c:sched_autogroup_write
  - fs/proc/base.c:oom_score_adj_write
  - fs/proc/base.c:oom_adj_write
```
```
In security/device_cgroup.c (ffffffff81499fdb)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_access_write
```
```
In block/elevator.c (ffffffff814c8de3)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - block/elevator.c:elv_iosched_store
```
```
In block/blk-mq-debugfs.c (ffffffff814fd1d7)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - block/blk-mq-debugfs.c:queue_state_write
```
```
In drivers/ata/libata-core.c (ffffffff829023b7)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_parse_force_param
  - drivers/ata/libata-core.c:ata_parse_force_param
  - drivers/ata/libata-core.c:ata_parse_force_param
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105c99f)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
```
```
In kernel/sched/debug.c (ffffffff810fb048)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - kernel/sched/debug.c:sched_feat_write
```
```
In kernel/cgroup/cgroup.c (ffffffff81165245)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_freeze_write
  - kernel/cgroup/cgroup.c:cgroup_max_depth_write
  - kernel/cgroup/cgroup.c:cgroup_max_descendants_write
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write_start
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81168687)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff8116a7e5)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_write
```
```
In kernel/cgroup/pids.c (ffffffff8116aa12)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_max_write
```
```
In kernel/cgroup/rdma.c (ffffffff8116b338)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
```
```
In kernel/cgroup/cpuset.c (ffffffff8117045f)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In kernel/trace/trace.c (ffffffff811ac1e3)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_clock_write
  - kernel/trace/trace.c:trace_set_options
```
```
In kernel/trace/blktrace.c (ffffffff811b7dc9)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
```
```
In kernel/trace/trace_events_filter.c (ffffffff811c1625)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
```
```
In kernel/trace/trace_events_hist.c (ffffffff811cabaf)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:parse_action_params
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
```
```
In mm/zswap.c (ffffffff8128ed75)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_param_set
```
```
In mm/memcontrol.c (ffffffff812bfc42)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - mm/memcontrol.c:swap_max_write
  - mm/memcontrol.c:memory_oom_group_write
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:memory_low_write
  - mm/memcontrol.c:memory_min_write
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:mem_cgroup_write
```
```
In mm/hugetlb_cgroup.c (ffffffff812c9994)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_write
```
```
In fs/proc/task_mmu.c (ffffffff8136ed2b)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
```
```
In fs/proc/base.c (ffffffff8137537a)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - fs/proc/base.c:sched_autogroup_write
  - fs/proc/base.c:oom_score_adj_write
  - fs/proc/base.c:oom_adj_write
```
```
In security/device_cgroup.c (ffffffff814b41db)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_access_write
```
```
In block/elevator.c (ffffffff814e1fc3)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - block/elevator.c:elv_iosched_store
```
```
In block/blk-mq-debugfs.c (ffffffff8151b127)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - block/blk-mq-debugfs.c:queue_state_write
```
```
In drivers/ata/libata-core.c (ffffffff8290b5d2)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_parse_force_param
  - drivers/ata/libata-core.c:ata_parse_force_param
  - drivers/ata/libata-core.c:ata_parse_force_param
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8106296a)
Location: include/linux/string.h:76
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
```
```
In kernel/sched/debug.c (ffffffff81105ba8)
Location: include/linux/string.h:76
Inline: True
Inline callers:
  - kernel/sched/debug.c:sched_feat_write
```
```
In kernel/cgroup/cgroup.c (ffffffff8117637e)
Location: include/linux/string.h:76
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_freeze_write
  - kernel/cgroup/cgroup.c:cgroup_max_depth_write
  - kernel/cgroup/cgroup.c:cgroup_max_descendants_write
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write_start
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8117a397)
Location: include/linux/string.h:76
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff8117c415)
Location: include/linux/string.h:76
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_write
```
```
In kernel/cgroup/pids.c (ffffffff8117c552)
Location: include/linux/string.h:76
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_max_write
```
```
In kernel/cgroup/rdma.c (ffffffff8117cdd6)
Location: include/linux/string.h:76
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
```
```
In kernel/cgroup/cpuset.c (ffffffff811817af)
Location: include/linux/string.h:76
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In kernel/trace/trace.c (ffffffff811c4991)
Location: include/linux/string.h:76
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_clock_write
  - kernel/trace/trace.c:trace_set_options
```
```
In kernel/trace/blktrace.c (ffffffff811d0379)
Location: include/linux/string.h:76
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_trace_str2mask
```
```
In kernel/trace/trace_events_filter.c (ffffffff811db563)
Location: include/linux/string.h:76
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
```
```
In kernel/trace/trace_events_hist.c (ffffffff811e6b75)
Location: include/linux/string.h:76
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:parse_action_params
  - kernel/trace/trace_events_hist.c:parse_assignment
```
```
In mm/zswap.c (ffffffff812c1ab5)
Location: include/linux/string.h:76
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_param_set
```
```
In mm/memcontrol.c (ffffffff812f4d82)
Location: include/linux/string.h:76
Inline: True
Inline callers:
  - mm/memcontrol.c:swap_max_write
  - mm/memcontrol.c:swap_high_write
  - mm/memcontrol.c:memory_oom_group_write
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:memory_low_write
  - mm/memcontrol.c:memory_min_write
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:mem_cgroup_write
```
```
In mm/hugetlb_cgroup.c (ffffffff812ff235)
Location: include/linux/string.h:76
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff813b704b)
Location: include/linux/string.h:76
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
```
```
In fs/proc/base.c (ffffffff813bd43e)
Location: include/linux/string.h:76
Inline: True
Inline callers:
  - fs/proc/base.c:sched_autogroup_write
  - fs/proc/base.c:oom_score_adj_write
  - fs/proc/base.c:oom_adj_write
```
```
In security/device_cgroup.c (ffffffff81513aa5)
Location: include/linux/string.h:76
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_access_write
```
```
In block/elevator.c (ffffffff81540aa1)
Location: include/linux/string.h:76
Inline: True
Inline callers:
  - block/elevator.c:__elevator_change
```
```
In block/blk-mq-debugfs.c (ffffffff8157b3d7)
Location: include/linux/string.h:76
Inline: True
Inline callers:
  - block/blk-mq-debugfs.c:queue_state_write
```
```
In drivers/ata/libata-core.c (ffffffff82d206ec)
Location: include/linux/string.h:76
Inline: True
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81060eba)
Location: include/linux/string.h:77
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
```
```
In kernel/sched/debug.c (ffffffff811041f8)
Location: include/linux/string.h:77
Inline: True
Inline callers:
  - kernel/sched/debug.c:sched_feat_write
```
```
In kernel/cgroup/cgroup.c (ffffffff8117306e)
Location: include/linux/string.h:77
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_freeze_write
  - kernel/cgroup/cgroup.c:cgroup_max_depth_write
  - kernel/cgroup/cgroup.c:cgroup_max_descendants_write
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write_start
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8117710d)
Location: include/linux/string.h:77
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff811792c1)
Location: include/linux/string.h:77
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_write
```
```
In kernel/cgroup/pids.c (ffffffff81179402)
Location: include/linux/string.h:77
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_max_write
```
```
In kernel/cgroup/rdma.c (ffffffff81179c36)
Location: include/linux/string.h:77
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
```
```
In kernel/cgroup/cpuset.c (ffffffff8117e6af)
Location: include/linux/string.h:77
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In kernel/trace/trace.c (ffffffff811c2591)
Location: include/linux/string.h:77
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_clock_write
  - kernel/trace/trace.c:trace_set_options
```
```
In kernel/trace/blktrace.c (ffffffff811cd819)
Location: include/linux/string.h:77
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_trace_str2mask
```
```
In kernel/trace/trace_events_filter.c (ffffffff811d8693)
Location: include/linux/string.h:77
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
```
```
In kernel/trace/trace_events_hist.c (ffffffff811e4535)
Location: include/linux/string.h:77
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:parse_action_params
  - kernel/trace/trace_events_hist.c:parse_assignment
```
```
In mm/zswap.c (ffffffff812cd695)
Location: include/linux/string.h:77
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_param_set
```
```
In mm/memcontrol.c (ffffffff81300632)
Location: include/linux/string.h:77
Inline: True
Inline callers:
  - mm/memcontrol.c:swap_max_write
  - mm/memcontrol.c:swap_high_write
  - mm/memcontrol.c:memory_oom_group_write
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:memory_low_write
  - mm/memcontrol.c:memory_min_write
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:mem_cgroup_write
```
```
In mm/hugetlb_cgroup.c (ffffffff8130b575)
Location: include/linux/string.h:77
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff813c89a1)
Location: include/linux/string.h:77
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
```
```
In fs/proc/base.c (ffffffff813cf18e)
Location: include/linux/string.h:77
Inline: True
Inline callers:
  - fs/proc/base.c:sched_autogroup_write
  - fs/proc/base.c:oom_score_adj_write
  - fs/proc/base.c:oom_adj_write
```
```
In security/device_cgroup.c (ffffffff81530bf5)
Location: include/linux/string.h:77
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_access_write
```
```
In block/elevator.c (ffffffff8155d221)
Location: include/linux/string.h:77
Inline: True
Inline callers:
  - block/elevator.c:__elevator_change
```
```
In block/blk-mq-debugfs.c (ffffffff81598497)
Location: include/linux/string.h:77
Inline: True
Inline callers:
  - block/blk-mq-debugfs.c:queue_state_write
```
```
In drivers/ata/libata-core.c (ffffffff8300e4cb)
Location: include/linux/string.h:77
Inline: True
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8106107f)
Location: include/linux/string.h:77
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
```
```
In kernel/sched/debug.c (ffffffff8110631d)
Location: include/linux/string.h:77
Inline: True
Inline callers:
  - kernel/sched/debug.c:sched_feat_write
```
```
In kernel/cgroup/cgroup.c (ffffffff81173628)
Location: include/linux/string.h:77
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_freeze_write
  - kernel/cgroup/cgroup.c:cgroup_max_depth_write
  - kernel/cgroup/cgroup.c:cgroup_max_descendants_write
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write_start
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81177c9d)
Location: include/linux/string.h:77
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff81179e31)
Location: include/linux/string.h:77
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_write
```
```
In kernel/cgroup/pids.c (ffffffff81179f62)
Location: include/linux/string.h:77
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_max_write
```
```
In kernel/cgroup/rdma.c (ffffffff8117a7c6)
Location: include/linux/string.h:77
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
```
```
In kernel/cgroup/cpuset.c (ffffffff8117e6cf)
Location: include/linux/string.h:77
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In kernel/cgroup/misc.c (ffffffff81180e60)
Location: include/linux/string.h:77
Inline: True
Inline callers:
  - kernel/cgroup/misc.c:misc_cg_max_write
```
```
In kernel/trace/trace.c (ffffffff811c3611)
Location: include/linux/string.h:77
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_clock_write
  - kernel/trace/trace.c:trace_set_options
```
```
In kernel/trace/blktrace.c (ffffffff811cf8a4)
Location: include/linux/string.h:77
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
```
```
In kernel/trace/trace_events_filter.c (ffffffff811d9b14)
Location: include/linux/string.h:77
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
```
```
In kernel/trace/trace_events_hist.c (ffffffff811e5b15)
Location: include/linux/string.h:77
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:parse_action_params
  - kernel/trace/trace_events_hist.c:parse_assignment
```
```
In mm/zswap.c (ffffffff812d4125)
Location: include/linux/string.h:77
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_param_set
```
```
In mm/memcontrol.c (ffffffff813070d2)
Location: include/linux/string.h:77
Inline: True
Inline callers:
  - mm/memcontrol.c:swap_max_write
  - mm/memcontrol.c:swap_high_write
  - mm/memcontrol.c:memory_oom_group_write
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:memory_low_write
  - mm/memcontrol.c:memory_min_write
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:mem_cgroup_write
```
```
In mm/hugetlb_cgroup.c (ffffffff81311bd5)
Location: include/linux/string.h:77
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff813cf9e3)
Location: include/linux/string.h:77
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
```
```
In fs/proc/base.c (ffffffff813d58e3)
Location: include/linux/string.h:77
Inline: True
Inline callers:
  - fs/proc/base.c:sched_autogroup_write
  - fs/proc/base.c:oom_score_adj_write
  - fs/proc/base.c:oom_adj_write
```
```
In security/device_cgroup.c (ffffffff81536df7)
Location: include/linux/string.h:77
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_access_write
```
```
In block/elevator.c (ffffffff81565aab)
Location: include/linux/string.h:77
Inline: True
Inline callers:
  - block/elevator.c:__elevator_change
```
```
In block/blk-mq-debugfs.c (ffffffff8159f2b7)
Location: include/linux/string.h:77
Inline: True
Inline callers:
  - block/blk-mq-debugfs.c:queue_state_write
```
```
In drivers/pinctrl/pinmux.c (ffffffff8160d11c)
Location: include/linux/string.h:77
Inline: True
Inline callers:
  - drivers/pinctrl/pinmux.c:pinmux_select
```
```
In drivers/ata/libata-core.c (ffffffff8321945f)
Location: include/linux/string.h:77
Inline: True
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8106ad3f)
Location: include/linux/string.h:76
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
```
```
In kernel/sched/debug.c (ffffffff81123e79)
Location: include/linux/string.h:76
Inline: True
Inline callers:
  - kernel/sched/debug.c:sched_feat_write
```
```
In kernel/cgroup/cgroup.c (ffffffff8119a618)
Location: include/linux/string.h:76
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_freeze_write
  - kernel/cgroup/cgroup.c:cgroup_max_depth_write
  - kernel/cgroup/cgroup.c:cgroup_max_descendants_write
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write_start
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8119f5ef)
Location: include/linux/string.h:76
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff811a1751)
Location: include/linux/string.h:76
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_write
```
```
In kernel/cgroup/pids.c (ffffffff811a1882)
Location: include/linux/string.h:76
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_max_write
```
```
In kernel/cgroup/rdma.c (ffffffff811a2116)
Location: include/linux/string.h:76
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
```
```
In kernel/cgroup/cpuset.c (ffffffff811a63ef)
Location: include/linux/string.h:76
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In kernel/cgroup/misc.c (ffffffff811a8c80)
Location: include/linux/string.h:76
Inline: True
Inline callers:
  - kernel/cgroup/misc.c:misc_cg_max_write
```
```
In kernel/trace/trace.c (ffffffff811ee7c1)
Location: include/linux/string.h:76
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_clock_write
  - kernel/trace/trace.c:trace_set_options
```
```
In kernel/trace/trace_hwlat.c (ffffffff811f7002)
Location: include/linux/string.h:76
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:hwlat_mode_write
```
```
In kernel/trace/blktrace.c (ffffffff811fbecc)
Location: include/linux/string.h:76
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
```
```
In kernel/trace/trace_events_filter.c (ffffffff81206ee4)
Location: include/linux/string.h:76
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
```
```
In kernel/trace/trace_events_hist.c (ffffffff81216919)
Location: include/linux/string.h:76
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:parse_action_params
  - kernel/trace/trace_events_hist.c:parse_assignment
```
```
In mm/zswap.c (ffffffff81319e05)
Location: include/linux/string.h:76
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_param_set
```
```
In mm/memcontrol.c (ffffffff81350d42)
Location: include/linux/string.h:76
Inline: True
Inline callers:
  - mm/memcontrol.c:swap_max_write
  - mm/memcontrol.c:swap_high_write
  - mm/memcontrol.c:memory_oom_group_write
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:memory_low_write
  - mm/memcontrol.c:memory_min_write
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:mem_cgroup_write
```
```
In mm/hugetlb_cgroup.c (ffffffff8135d099)
Location: include/linux/string.h:76
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff81420dc3)
Location: include/linux/string.h:76
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
```
```
In fs/proc/base.c (ffffffff81427163)
Location: include/linux/string.h:76
Inline: True
Inline callers:
  - fs/proc/base.c:sched_autogroup_write
  - fs/proc/base.c:oom_score_adj_write
  - fs/proc/base.c:oom_adj_write
```
```
In security/device_cgroup.c (ffffffff81595567)
Location: include/linux/string.h:76
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_access_write
```
```
In block/elevator.c (ffffffff815c9e7b)
Location: include/linux/string.h:76
Inline: True
Inline callers:
  - block/elevator.c:__elevator_change
```
```
In block/blk-mq-debugfs.c (ffffffff81607a67)
Location: include/linux/string.h:76
Inline: True
Inline callers:
  - block/blk-mq-debugfs.c:queue_state_write
```
```
In drivers/pinctrl/pinmux.c (ffffffff8167be5c)
Location: include/linux/string.h:76
Inline: True
Inline callers:
  - drivers/pinctrl/pinmux.c:pinmux_select
```
```
In drivers/ata/libata-core.c (ffffffff83302f36)
Location: include/linux/string.h:76
Inline: True
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81078026)
Location: include/linux/string.h:76
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
```
```
In kernel/sched/build_utility.c (ffffffff8113d2b7)
Location: include/linux/string.h:76
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sched_dynamic_write
  - kernel/sched/build_utility.c:sched_feat_write
```
```
In kernel/cgroup/cgroup.c (ffffffff811ca76f)
Location: include/linux/string.h:76
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_freeze_write
  - kernel/cgroup/cgroup.c:cgroup_max_depth_write
  - kernel/cgroup/cgroup.c:cgroup_max_descendants_write
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write_start
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff811cec8f)
Location: include/linux/string.h:76
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff811d2091)
Location: include/linux/string.h:76
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_write
```
```
In kernel/cgroup/pids.c (ffffffff811d21ea)
Location: include/linux/string.h:76
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_max_write
```
```
In kernel/cgroup/rdma.c (ffffffff811d2b76)
Location: include/linux/string.h:76
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
```
```
In kernel/cgroup/cpuset.c (ffffffff811d781f)
Location: include/linux/string.h:76
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In kernel/cgroup/misc.c (ffffffff811d9f48)
Location: include/linux/string.h:76
Inline: True
Inline callers:
  - kernel/cgroup/misc.c:misc_cg_max_write
```
```
In kernel/trace/trace.c (ffffffff81226b05)
Location: include/linux/string.h:76
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_clock_write
  - kernel/trace/trace.c:trace_set_options
```
```
In kernel/trace/trace_hwlat.c (ffffffff81230ad0)
Location: include/linux/string.h:76
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:hwlat_mode_write
```
```
In kernel/trace/blktrace.c (ffffffff81236235)
Location: include/linux/string.h:76
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
```
```
In kernel/trace/trace_events_filter.c (ffffffff81242814)
Location: include/linux/string.h:76
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
```
```
In kernel/trace/trace_events_hist.c (ffffffff81254cd7)
Location: include/linux/string.h:76
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_parse
  - kernel/trace/trace_events_hist.c:event_hist_trigger_parse
  - kernel/trace/trace_events_hist.c:parse_action_params
  - kernel/trace/trace_events_hist.c:parse_assignment
```
```
In mm/zswap.c (ffffffff81384e35)
Location: include/linux/string.h:76
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_param_set
```
```
In mm/memcontrol.c (ffffffff813c939a)
Location: include/linux/string.h:76
Inline: True
Inline callers:
  - mm/memcontrol.c:zswap_max_write
  - mm/memcontrol.c:swap_max_write
  - mm/memcontrol.c:swap_high_write
  - mm/memcontrol.c:memory_reclaim
  - mm/memcontrol.c:memory_oom_group_write
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:memory_low_write
  - mm/memcontrol.c:memory_min_write
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:mem_cgroup_write
```
```
In mm/hugetlb_cgroup.c (ffffffff813d6da1)
Location: include/linux/string.h:76
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff81498c2e)
Location: include/linux/string.h:76
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
```
```
In fs/proc/base.c (ffffffff814a0b74)
Location: include/linux/string.h:76
Inline: True
Inline callers:
  - fs/proc/base.c:sched_autogroup_write
  - fs/proc/base.c:oom_score_adj_write
  - fs/proc/base.c:oom_adj_write
```
```
In security/device_cgroup.c (ffffffff816377a5)
Location: include/linux/string.h:76
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_access_write
```
```
In block/elevator.c (ffffffff81675245)
Location: include/linux/string.h:76
Inline: True
Inline callers:
  - block/elevator.c:__elevator_change
```
```
In block/blk-mq-debugfs.c (ffffffff816bb377)
Location: include/linux/string.h:76
Inline: True
Inline callers:
  - block/blk-mq-debugfs.c:queue_state_write
```
```
In drivers/pinctrl/pinmux.c (ffffffff81797664)
Location: include/linux/string.h:76
Inline: True
Inline callers:
  - drivers/pinctrl/pinmux.c:pinmux_select
```
```
In drivers/ata/libata-core.c (ffffffff834bc1f5)
Location: include/linux/string.h:76
Inline: True
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81088c36)
Location: include/linux/string.h:76
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
```
```
In kernel/sched/build_utility.c (ffffffff81167cf7)
Location: include/linux/string.h:76
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sched_dynamic_write
  - kernel/sched/build_utility.c:sched_feat_write
```
```
In kernel/cgroup/cgroup.c (ffffffff8120db1f)
Location: include/linux/string.h:76
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_freeze_write
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cgroup_max_depth_write
  - kernel/cgroup/cgroup.c:cgroup_max_descendants_write
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write_start
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8121256f)
Location: include/linux/string.h:76
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff81215dd1)
Location: include/linux/string.h:76
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_write
```
```
In kernel/cgroup/pids.c (ffffffff81215f9a)
Location: include/linux/string.h:76
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_max_write
```
```
In kernel/cgroup/rdma.c (ffffffff81216aa6)
Location: include/linux/string.h:76
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
```
```
In kernel/cgroup/cpuset.c (ffffffff8121c4f1)
Location: include/linux/string.h:76
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In kernel/cgroup/misc.c (ffffffff8121f498)
Location: include/linux/string.h:76
Inline: True
Inline callers:
  - kernel/cgroup/misc.c:misc_cg_max_write
```
```
In kernel/trace/trace.c (ffffffff81271d85)
Location: include/linux/string.h:76
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_clock_write
  - kernel/trace/trace.c:trace_set_options
```
```
In kernel/trace/trace_hwlat.c (ffffffff8127ce70)
Location: include/linux/string.h:76
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:hwlat_mode_write
```
```
In kernel/trace/blktrace.c (ffffffff81282b9b)
Location: include/linux/string.h:76
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
```
```
In kernel/trace/trace_events_filter.c (ffffffff81290244)
Location: include/linux/string.h:76
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
```
```
In kernel/trace/trace_events_hist.c (ffffffff812a4167)
Location: include/linux/string.h:76
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_parse
  - kernel/trace/trace_events_hist.c:event_hist_trigger_parse
  - kernel/trace/trace_events_hist.c:parse_action_params
  - kernel/trace/trace_events_hist.c:parse_assignment
```
```
In mm/zswap.c (ffffffff81402b15)
Location: include/linux/string.h:76
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_param_set
```
```
In mm/memcontrol.c (ffffffff8144e68a)
Location: include/linux/string.h:76
Inline: True
Inline callers:
  - mm/memcontrol.c:zswap_max_write
  - mm/memcontrol.c:swap_max_write
  - mm/memcontrol.c:swap_high_write
  - mm/memcontrol.c:memory_reclaim
  - mm/memcontrol.c:memory_oom_group_write
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:memory_low_write
  - mm/memcontrol.c:memory_min_write
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:mem_cgroup_write
```
```
In mm/hugetlb_cgroup.c (ffffffff8145cbf1)
Location: include/linux/string.h:76
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff8152cf04)
Location: include/linux/string.h:76
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
```
```
In fs/proc/base.c (ffffffff81535b24)
Location: include/linux/string.h:76
Inline: True
Inline callers:
  - fs/proc/base.c:sched_autogroup_write
  - fs/proc/base.c:oom_score_adj_write
  - fs/proc/base.c:oom_adj_write
```
```
In security/device_cgroup.c (ffffffff816eeb35)
Location: include/linux/string.h:76
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_access_write
```
```
In block/elevator.c (ffffffff8173126e)
Location: include/linux/string.h:76
Inline: True
Inline callers:
  - block/elevator.c:elv_iosched_store
```
```
In block/blk-mq-debugfs.c (ffffffff8177bad6)
Location: include/linux/string.h:76
Inline: True
Inline callers:
  - block/blk-mq-debugfs.c:queue_state_write
```
```
In drivers/pinctrl/pinmux.c (ffffffff818ad0e5)
Location: include/linux/string.h:76
Inline: True
Inline callers:
  - drivers/pinctrl/pinmux.c:pinmux_select
```
```
In drivers/ata/libata-core.c (ffffffff83efa461)
Location: include/linux/string.h:76
Inline: True
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8108bb36)
Location: include/linux/string.h:76
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
```
```
In kernel/sched/build_utility.c (ffffffff811783b7)
Location: include/linux/string.h:76
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sched_dynamic_write
  - kernel/sched/build_utility.c:sched_feat_write
```
```
In kernel/cgroup/cgroup.c (ffffffff8122351f)
Location: include/linux/string.h:76
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_freeze_write
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cgroup_max_depth_write
  - kernel/cgroup/cgroup.c:cgroup_max_descendants_write
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write_start
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81227ecd)
Location: include/linux/string.h:76
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff8122b711)
Location: include/linux/string.h:76
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_write
```
```
In kernel/cgroup/pids.c (ffffffff8122b8da)
Location: include/linux/string.h:76
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_max_write
```
```
In kernel/cgroup/rdma.c (ffffffff8122c397)
Location: include/linux/string.h:76
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
```
```
In kernel/cgroup/cpuset.c (ffffffff812328e1)
Location: include/linux/string.h:76
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In kernel/cgroup/misc.c (ffffffff812355c8)
Location: include/linux/string.h:76
Inline: True
Inline callers:
  - kernel/cgroup/misc.c:misc_cg_max_write
```
```
In kernel/trace/trace.c (ffffffff8128908b)
Location: include/linux/string.h:76
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_clock_write
  - kernel/trace/trace.c:trace_set_options
```
```
In kernel/trace/trace_hwlat.c (ffffffff8129473a)
Location: include/linux/string.h:76
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:hwlat_mode_write
```
```
In kernel/trace/trace_osnoise.c (ffffffff8129743e)
Location: include/linux/string.h:76
Inline: True
Inline callers:
  - kernel/trace/trace_osnoise.c:osnoise_options_write
  - kernel/trace/trace_osnoise.c:osnoise_options_write
```
```
In kernel/trace/blktrace.c (ffffffff8129f83e)
Location: include/linux/string.h:76
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
```
```
In kernel/trace/trace_events_filter.c (ffffffff812ad404)
Location: include/linux/string.h:76
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
```
```
In kernel/trace/trace_events_hist.c (ffffffff812c2027)
Location: include/linux/string.h:76
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_parse
  - kernel/trace/trace_events_hist.c:event_hist_trigger_parse
  - kernel/trace/trace_events_hist.c:parse_action_params
  - kernel/trace/trace_events_hist.c:parse_assignment
```
```
In mm/zswap.c (ffffffff81436025)
Location: include/linux/string.h:76
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_param_set
```
```
In mm/memcontrol.c (ffffffff8148414a)
Location: include/linux/string.h:76
Inline: True
Inline callers:
  - mm/memcontrol.c:zswap_max_write
  - mm/memcontrol.c:swap_max_write
  - mm/memcontrol.c:swap_high_write
  - mm/memcontrol.c:memory_reclaim
  - mm/memcontrol.c:memory_oom_group_write
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:memory_low_write
  - mm/memcontrol.c:memory_min_write
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:mem_cgroup_write
```
```
In mm/hugetlb_cgroup.c (ffffffff81492971)
Location: include/linux/string.h:76
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff81564bd4)
Location: include/linux/string.h:76
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
```
```
In fs/proc/base.c (ffffffff8156db87)
Location: include/linux/string.h:76
Inline: True
Inline callers:
  - fs/proc/base.c:sched_autogroup_write
  - fs/proc/base.c:oom_score_adj_write
  - fs/proc/base.c:oom_adj_write
```
```
In security/device_cgroup.c (ffffffff81729035)
Location: include/linux/string.h:76
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_access_write
```
```
In block/elevator.c (ffffffff8176d4b7)
Location: include/linux/string.h:76
Inline: True
Inline callers:
  - block/elevator.c:elv_iosched_store
```
```
In block/blk-mq-debugfs.c (ffffffff817bb5e9)
Location: include/linux/string.h:76
Inline: True
Inline callers:
  - block/blk-mq-debugfs.c:queue_state_write
```
```
In drivers/pinctrl/pinmux.c (ffffffff818ef917)
Location: include/linux/string.h:76
Inline: True
Inline callers:
  - drivers/pinctrl/pinmux.c:pinmux_select
```
```
In drivers/ata/libata-core.c (ffffffff837201b1)
Location: include/linux/string.h:76
Inline: True
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
In kernel/sched/build_utility.c (ffffffff811860d7)
Location: include/linux/string.h:114
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sched_dynamic_write
  - kernel/sched/build_utility.c:sched_feat_write
```
```
In kernel/cgroup/cgroup.c (ffffffff8123b20f)
Location: include/linux/string.h:114
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_freeze_write
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cgroup_max_depth_write
  - kernel/cgroup/cgroup.c:cgroup_max_descendants_write
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write_start
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8123fccd)
Location: include/linux/string.h:114
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff81243701)
Location: include/linux/string.h:114
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_write
```
```
In kernel/cgroup/pids.c (ffffffff812438da)
Location: include/linux/string.h:114
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_max_write
```
```
In kernel/cgroup/rdma.c (ffffffff812443f7)
Location: include/linux/string.h:114
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
```
```
In kernel/cgroup/cpuset.c (ffffffff8124c061)
Location: include/linux/string.h:114
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In kernel/cgroup/misc.c (ffffffff8124f218)
Location: include/linux/string.h:114
Inline: True
Inline callers:
  - kernel/cgroup/misc.c:misc_cg_max_write
```
```
In kernel/trace/trace.c (ffffffff812a43db)
Location: include/linux/string.h:114
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_clock_write
  - kernel/trace/trace.c:trace_set_options
```
```
In kernel/trace/trace_hwlat.c (ffffffff812afd9a)
Location: include/linux/string.h:114
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:hwlat_mode_write
```
```
In kernel/trace/trace_osnoise.c (ffffffff812b2a8e)
Location: include/linux/string.h:114
Inline: True
Inline callers:
  - kernel/trace/trace_osnoise.c:osnoise_options_write
  - kernel/trace/trace_osnoise.c:osnoise_options_write
```
```
In kernel/trace/blktrace.c (ffffffff812baf6e)
Location: include/linux/string.h:114
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
```
```
In kernel/trace/trace_events_filter.c (ffffffff812c9934)
Location: include/linux/string.h:114
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
```
```
In kernel/trace/trace_events_hist.c (ffffffff812de46d)
Location: include/linux/string.h:114
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_parse
  - kernel/trace/trace_events_hist.c:event_hist_trigger_parse
  - kernel/trace/trace_events_hist.c:parse_action_params
  - kernel/trace/trace_events_hist.c:parse_assignment
```
```
In mm/zswap.c (ffffffff8146fa55)
Location: include/linux/string.h:114
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_param_set
```
```
In mm/memcontrol.c (ffffffff814b38e9)
Location: include/linux/string.h:114
Inline: True
Inline callers:
  - mm/memcontrol.c:zswap_writeback_write
  - mm/memcontrol.c:zswap_max_write
  - mm/memcontrol.c:swap_max_write
  - mm/memcontrol.c:swap_high_write
  - mm/memcontrol.c:memory_reclaim
  - mm/memcontrol.c:memory_oom_group_write
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:memory_low_write
  - mm/memcontrol.c:memory_min_write
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:mem_cgroup_write
```
```
In mm/hugetlb_cgroup.c (ffffffff814c26d1)
Location: include/linux/string.h:114
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff8159b694)
Location: include/linux/string.h:114
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
```
```
In fs/proc/base.c (ffffffff815a6317)
Location: include/linux/string.h:114
Inline: True
Inline callers:
  - fs/proc/base.c:sched_autogroup_write
  - fs/proc/base.c:oom_score_adj_write
  - fs/proc/base.c:oom_adj_write
```
```
In security/device_cgroup.c (ffffffff8176a395)
Location: include/linux/string.h:114
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_access_write
```
```
In block/elevator.c (ffffffff817af6e7)
Location: include/linux/string.h:114
Inline: True
Inline callers:
  - block/elevator.c:elv_iosched_store
```
```
In block/blk-mq-debugfs.c (ffffffff817ffca6)
Location: include/linux/string.h:114
Inline: True
Inline callers:
  - block/blk-mq-debugfs.c:queue_state_write
```
```
In drivers/pinctrl/pinmux.c (ffffffff819370d7)
Location: include/linux/string.h:114
Inline: True
Inline callers:
  - drivers/pinctrl/pinmux.c:pinmux_select
```
```
In drivers/ata/libata-core.c (ffffffff83953b81)
Location: include/linux/string.h:114
Inline: True
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
In kernel/sched/debug.c (ffff800010160cd4)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - kernel/sched/debug.c:sched_feat_write
```
```
In kernel/cgroup/cgroup.c (ffff8000101d6cd0)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_freeze_write
  - kernel/cgroup/cgroup.c:cgroup_max_depth_write
  - kernel/cgroup/cgroup.c:cgroup_max_descendants_write
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write_start
```
```
In kernel/cgroup/cgroup-v1.c (ffff8000101db188)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write
```
```
In kernel/cgroup/legacy_freezer.c (ffff8000101de6b8)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_write
```
```
In kernel/cgroup/pids.c (ffff8000101dea7c)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_max_write
```
```
In kernel/cgroup/rdma.c (ffff8000101df5e4)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
```
```
In kernel/cgroup/cpuset.c (ffff8000101e3308)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In kernel/trace/trace.c (ffff800010229194)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_clock_write
  - kernel/trace/trace.c:trace_set_options
```
```
In kernel/trace/blktrace.c (ffff800010235f8c)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
```
```
In kernel/trace/trace_events_filter.c (ffff800010240d24)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
```
```
In kernel/trace/trace_events_hist.c (ffff80001024a028)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:parse_action_params
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
```
```
In mm/zswap.c (ffff80001032bab0)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_param_set
```
```
In mm/memcontrol.c (ffff800010363bfc)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - mm/memcontrol.c:swap_max_write
  - mm/memcontrol.c:memory_oom_group_write
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:memory_low_write
  - mm/memcontrol.c:memory_min_write
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:mem_cgroup_write
```
```
In mm/hugetlb_cgroup.c (ffff80001036d0fc)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_write
```
```
In fs/proc/task_mmu.c (ffff8000104391a0)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
```
```
In fs/proc/base.c (ffff800010440324)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - fs/proc/base.c:sched_autogroup_write
  - fs/proc/base.c:oom_score_adj_write
  - fs/proc/base.c:oom_adj_write
```
```
In security/device_cgroup.c (ffff8000105ac178)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_access_write
```
```
In block/elevator.c (ffff8000105df1e4)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - block/elevator.c:elv_iosched_store
```
```
In block/blk-mq-debugfs.c (ffff800010623c8c)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - block/blk-mq-debugfs.c:queue_state_write
```
```
In drivers/ata/libata-core.c (ffff80001149adac)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_parse_force_param
  - drivers/ata/libata-core.c:ata_parse_force_param
  - drivers/ata/libata-core.c:ata_parse_force_param
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
In kernel/sched/debug.c (c03ac3dc)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - kernel/sched/debug.c:sched_feat_write
```
```
In kernel/cgroup/cgroup.c (c04199a4)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_freeze_write
  - kernel/cgroup/cgroup.c:cgroup_max_depth_write
  - kernel/cgroup/cgroup.c:cgroup_max_descendants_write
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write_start
```
```
In kernel/cgroup/cgroup-v1.c (c041ce7c)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write
```
```
In kernel/cgroup/legacy_freezer.c (c0420160)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_write
```
```
In kernel/cgroup/pids.c (c0420414)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_max_write
```
```
In kernel/cgroup/rdma.c (c0420f04)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
```
```
In kernel/cgroup/cpuset.c (c04240b8)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In kernel/trace/trace.c (c04667c4)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_clock_write
  - kernel/trace/trace.c:trace_set_options
```
```
In kernel/trace/blktrace.c (c04723e4)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
```
```
In kernel/trace/trace_events_filter.c (c047c75c)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
```
```
In mm/zswap.c (c0541b3c)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_param_set
```
```
In mm/memcontrol.c (c0555c0c)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - mm/memcontrol.c:swap_max_write
  - mm/memcontrol.c:memory_oom_group_write
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:memory_low_write
  - mm/memcontrol.c:memory_min_write
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:mem_cgroup_write
```
```
In fs/proc/task_mmu.c (c060013c)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
```
```
In fs/proc/base.c (c0605f28)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - fs/proc/base.c:sched_autogroup_write
  - fs/proc/base.c:oom_score_adj_write
  - fs/proc/base.c:oom_adj_write
```
```
In security/device_cgroup.c (c075bbf4)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_access_write
```
```
In block/elevator.c (c078c0d8)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - block/elevator.c:elv_iosched_store
```
```
In block/blk-mq-debugfs.c (c07cad80)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - block/blk-mq-debugfs.c:queue_state_write
```
```
In drivers/ata/libata-core.c (c159bcb8)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_parse_force_param
  - drivers/ata/libata-core.c:ata_parse_force_param
  - drivers/ata/libata-core.c:ata_parse_force_param
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
In arch/powerpc/platforms/pseries/lpar.c (c000000001361514)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - arch/powerpc/platforms/pseries/lpar.c:cmo_free_hint
```
```
In kernel/sched/debug.c (c0000000001b79e4)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - kernel/sched/debug.c:sched_feat_write
```
```
In kernel/cgroup/cgroup.c (c000000000242f60)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_freeze_write
  - kernel/cgroup/cgroup.c:cgroup_max_depth_write
  - kernel/cgroup/cgroup.c:cgroup_max_descendants_write
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write_start
```
```
In kernel/cgroup/cgroup-v1.c (c0000000002478a8)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write
```
```
In kernel/cgroup/legacy_freezer.c (c00000000024c47c)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_write
```
```
In kernel/cgroup/pids.c (c00000000024ca5c)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_max_write
```
```
In kernel/cgroup/rdma.c (c00000000024d990)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
```
```
In kernel/cgroup/cpuset.c (c000000000253c24)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In kernel/trace/trace.c (c0000000002b058c)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_clock_write
  - kernel/trace/trace.c:trace_set_options
```
```
In kernel/trace/blktrace.c (c0000000002c1ee8)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
```
```
In kernel/trace/trace_events_filter.c (c0000000002d1dc0)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
```
```
In kernel/trace/trace_events_hist.c (c0000000002e4e54)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:parse_action_params
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
```
```
In mm/zswap.c (c0000000004034a4)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_param_set
```
```
In mm/memcontrol.c (c00000000044d6bc)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - mm/memcontrol.c:swap_max_write
  - mm/memcontrol.c:memory_oom_group_write
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:memory_low_write
  - mm/memcontrol.c:memory_min_write
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:mem_cgroup_write
```
```
In mm/hugetlb_cgroup.c (c00000000045d0b8)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_write
```
```
In fs/proc/task_mmu.c (c00000000054bf90)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
```
```
In fs/proc/base.c (c0000000005549b0)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - fs/proc/base.c:sched_autogroup_write
  - fs/proc/base.c:oom_score_adj_write
  - fs/proc/base.c:oom_adj_write
```
```
In security/device_cgroup.c (c00000000072a4a0)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_access_write
```
```
In block/elevator.c (c0000000007712fc)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - block/elevator.c:elv_iosched_store
```
```
In block/blk-mq-debugfs.c (c0000000007c3728)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - block/blk-mq-debugfs.c:queue_state_write
```
```
In drivers/ata/libata-core.c (c0000000013aee5c)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_parse_force_param
  - drivers/ata/libata-core.c:ata_parse_force_param
  - drivers/ata/libata-core.c:ata_parse_force_param
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
In kernel/sched/debug.c (ffffffe000104ba4)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - kernel/sched/debug.c:sched_feat_write
```
```
In kernel/cgroup/cgroup.c (ffffffe00014fe0e)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_freeze_write
  - kernel/cgroup/cgroup.c:cgroup_max_depth_write
  - kernel/cgroup/cgroup.c:cgroup_max_descendants_write
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write_start
```
```
In kernel/cgroup/cgroup-v1.c (ffffffe000153798)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write
```
```
In kernel/cgroup/legacy_freezer.c (ffffffe000155b12)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_write
```
```
In kernel/cgroup/pids.c (ffffffe000155d48)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_max_write
```
```
In kernel/cgroup/rdma.c (ffffffe000156686)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
```
```
In kernel/cgroup/cpuset.c (ffffffe000158f70)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In kernel/trace/trace.c (ffffffe00018394e)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_clock_write
  - kernel/trace/trace.c:trace_set_options
```
```
In kernel/trace/blktrace.c (ffffffe00018d444)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
```
```
In kernel/trace/trace_events_filter.c (ffffffe000195e64)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
```
```
In mm/zswap.c (ffffffe00022a6aa)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_param_set
```
```
In mm/memcontrol.c (ffffffe000240ca8)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - mm/memcontrol.c:swap_max_write
  - mm/memcontrol.c:memory_oom_group_write
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:memory_low_write
  - mm/memcontrol.c:memory_min_write
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:mem_cgroup_write
```
```
In mm/hugetlb_cgroup.c (ffffffe000249ebc)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_write
```
```
In fs/proc/task_mmu.c (ffffffe0002d2f4a)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
```
```
In fs/proc/base.c (ffffffe0002d768e)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - fs/proc/base.c:sched_autogroup_write
  - fs/proc/base.c:oom_score_adj_write
  - fs/proc/base.c:oom_adj_write
```
```
In security/device_cgroup.c (ffffffe0003f4904)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_access_write
```
```
In block/elevator.c (ffffffe000421c4c)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - block/elevator.c:elv_iosched_store
```
```
In block/blk-mq-debugfs.c (ffffffe000455136)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - block/blk-mq-debugfs.c:queue_state_write
```
```
In drivers/ata/libata-core.c (ffffffe00003412a)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_parse_force_param
  - drivers/ata/libata-core.c:ata_parse_force_param
  - drivers/ata/libata-core.c:ata_parse_force_param
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105c51f)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
```
```
In kernel/sched/debug.c (ffffffff810f4378)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - kernel/sched/debug.c:sched_feat_write
```
```
In kernel/cgroup/cgroup.c (ffffffff8115d865)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_freeze_write
  - kernel/cgroup/cgroup.c:cgroup_max_depth_write
  - kernel/cgroup/cgroup.c:cgroup_max_descendants_write
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write_start
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81160ca7)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff81162e05)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_write
```
```
In kernel/cgroup/pids.c (ffffffff81163032)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_max_write
```
```
In kernel/cgroup/rdma.c (ffffffff81163958)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
```
```
In kernel/cgroup/cpuset.c (ffffffff81168a7f)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In kernel/trace/trace.c (ffffffff811a4803)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_clock_write
  - kernel/trace/trace.c:trace_set_options
```
```
In kernel/trace/blktrace.c (ffffffff811b03e9)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
```
```
In kernel/trace/trace_events_filter.c (ffffffff811b9c45)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
```
```
In kernel/trace/trace_events_hist.c (ffffffff811c31cf)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:parse_action_params
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
```
```
In mm/zswap.c (ffffffff81287355)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_param_set
```
```
In mm/memcontrol.c (ffffffff812b8222)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - mm/memcontrol.c:swap_max_write
  - mm/memcontrol.c:memory_oom_group_write
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:memory_low_write
  - mm/memcontrol.c:memory_min_write
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:mem_cgroup_write
```
```
In mm/hugetlb_cgroup.c (ffffffff812c1f74)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_write
```
```
In fs/proc/task_mmu.c (ffffffff8136730b)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
```
```
In fs/proc/base.c (ffffffff8136d95a)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - fs/proc/base.c:sched_autogroup_write
  - fs/proc/base.c:oom_score_adj_write
  - fs/proc/base.c:oom_adj_write
```
```
In security/device_cgroup.c (ffffffff814ac7bb)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_access_write
```
```
In block/elevator.c (ffffffff814da5a3)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - block/elevator.c:elv_iosched_store
```
```
In block/blk-mq-debugfs.c (ffffffff81513707)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - block/blk-mq-debugfs.c:queue_state_write
```
```
In drivers/ata/libata-core.c (ffffffff828f2f8f)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_parse_force_param
  - drivers/ata/libata-core.c:ata_parse_force_param
  - drivers/ata/libata-core.c:ata_parse_force_param
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8104c6ef)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
```
```
In kernel/sched/debug.c (ffffffff810e4558)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - kernel/sched/debug.c:sched_feat_write
```
```
In kernel/cgroup/cgroup.c (ffffffff81150b55)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_freeze_write
  - kernel/cgroup/cgroup.c:cgroup_max_depth_write
  - kernel/cgroup/cgroup.c:cgroup_max_descendants_write
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write_start
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81153f17)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff81156055)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_write
```
```
In kernel/cgroup/pids.c (ffffffff81156282)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_max_write
```
```
In kernel/cgroup/rdma.c (ffffffff81156ba8)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
```
```
In kernel/cgroup/cpuset.c (ffffffff8115bc8f)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In kernel/trace/trace.c (ffffffff811977b3)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_clock_write
  - kernel/trace/trace.c:trace_set_options
```
```
In kernel/trace/blktrace.c (ffffffff811a3239)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
```
```
In kernel/trace/trace_events_filter.c (ffffffff811aca25)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
```
```
In kernel/trace/trace_events_hist.c (ffffffff811b5faf)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:parse_action_params
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
```
```
In mm/zswap.c (ffffffff812791b5)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_param_set
```
```
In mm/memcontrol.c (ffffffff812a93f2)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - mm/memcontrol.c:swap_max_write
  - mm/memcontrol.c:memory_oom_group_write
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:memory_low_write
  - mm/memcontrol.c:memory_min_write
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:mem_cgroup_write
```
```
In mm/hugetlb_cgroup.c (ffffffff812b2fc4)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_write
```
```
In fs/proc/task_mmu.c (ffffffff81357fab)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
```
```
In fs/proc/base.c (ffffffff8135e3ea)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - fs/proc/base.c:sched_autogroup_write
  - fs/proc/base.c:oom_score_adj_write
  - fs/proc/base.c:oom_adj_write
```
```
In security/device_cgroup.c (ffffffff8149d1db)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_access_write
```
```
In block/elevator.c (ffffffff814caf53)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - block/elevator.c:elv_iosched_store
```
```
In block/blk-mq-debugfs.c (ffffffff81503a17)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - block/blk-mq-debugfs.c:queue_state_write
```
```
In drivers/ata/libata-core.c (ffffffff828ea43a)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_parse_force_param
  - drivers/ata/libata-core.c:ata_parse_force_param
  - drivers/ata/libata-core.c:ata_parse_force_param
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105c94f)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
```
```
In kernel/sched/debug.c (ffffffff810f1578)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - kernel/sched/debug.c:sched_feat_write
```
```
In kernel/cgroup/cgroup.c (ffffffff8115b635)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_freeze_write
  - kernel/cgroup/cgroup.c:cgroup_max_depth_write
  - kernel/cgroup/cgroup.c:cgroup_max_descendants_write
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write_start
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8115ea77)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff81160bd5)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_write
```
```
In kernel/cgroup/pids.c (ffffffff81160e02)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_max_write
```
```
In kernel/cgroup/rdma.c (ffffffff81161728)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
```
```
In kernel/cgroup/cpuset.c (ffffffff8116684f)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In kernel/trace/trace.c (ffffffff811a25d3)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_clock_write
  - kernel/trace/trace.c:trace_set_options
```
```
In kernel/trace/blktrace.c (ffffffff811ae1b9)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
```
```
In kernel/trace/trace_events_filter.c (ffffffff811b7a15)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
```
```
In kernel/trace/trace_events_hist.c (ffffffff811c0f9f)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:parse_action_params
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
```
```
In mm/zswap.c (ffffffff81285165)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_param_set
```
```
In mm/memcontrol.c (ffffffff812b6032)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - mm/memcontrol.c:swap_max_write
  - mm/memcontrol.c:memory_oom_group_write
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:memory_low_write
  - mm/memcontrol.c:memory_min_write
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:mem_cgroup_write
```
```
In mm/hugetlb_cgroup.c (ffffffff812bfd84)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_write
```
```
In fs/proc/task_mmu.c (ffffffff81364ddb)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
```
```
In fs/proc/base.c (ffffffff8136b42a)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - fs/proc/base.c:sched_autogroup_write
  - fs/proc/base.c:oom_score_adj_write
  - fs/proc/base.c:oom_adj_write
```
```
In security/device_cgroup.c (ffffffff814a885b)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_access_write
```
```
In block/elevator.c (ffffffff814d6633)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - block/elevator.c:elv_iosched_store
```
```
In block/blk-mq-debugfs.c (ffffffff8150f797)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - block/blk-mq-debugfs.c:queue_state_write
```
```
In drivers/ata/libata-core.c (ffffffff829069cd)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_parse_force_param
  - drivers/ata/libata-core.c:ata_parse_force_param
  - drivers/ata/libata-core.c:ata_parse_force_param
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105de5f)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
```
```
In kernel/sched/debug.c (ffffffff810fc568)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - kernel/sched/debug.c:sched_feat_write
```
```
In kernel/cgroup/cgroup.c (ffffffff81168715)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_freeze_write
  - kernel/cgroup/cgroup.c:cgroup_max_depth_write
  - kernel/cgroup/cgroup.c:cgroup_max_descendants_write
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write_start
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8116b357)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff8116dfb5)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_write
```
```
In kernel/cgroup/pids.c (ffffffff8116e252)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_max_write
```
```
In kernel/cgroup/rdma.c (ffffffff8116eb78)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
```
```
In kernel/cgroup/cpuset.c (ffffffff81173eaf)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In kernel/trace/trace.c (ffffffff811b0363)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_clock_write
  - kernel/trace/trace.c:trace_set_options
```
```
In kernel/trace/blktrace.c (ffffffff811bc089)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
```
```
In kernel/trace/trace_events_filter.c (ffffffff811c5ab5)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
```
```
In kernel/trace/trace_events_hist.c (ffffffff811cf03f)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:parse_action_params
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
```
```
In mm/zswap.c (ffffffff812952c5)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_param_set
```
```
In mm/memcontrol.c (ffffffff812c6712)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - mm/memcontrol.c:swap_max_write
  - mm/memcontrol.c:memory_oom_group_write
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:memory_low_write
  - mm/memcontrol.c:memory_min_write
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:mem_cgroup_write
```
```
In mm/hugetlb_cgroup.c (ffffffff812d07c4)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_write
```
```
In fs/proc/task_mmu.c (ffffffff81377e1b)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
```
```
In fs/proc/base.c (ffffffff8137f21a)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - fs/proc/base.c:sched_autogroup_write
  - fs/proc/base.c:oom_score_adj_write
  - fs/proc/base.c:oom_adj_write
```
```
In security/device_cgroup.c (ffffffff814c121a)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_access_write
```
```
In block/elevator.c (ffffffff814ef243)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - block/elevator.c:elv_iosched_store
```
```
In block/blk-mq-debugfs.c (ffffffff81528fb7)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - block/blk-mq-debugfs.c:queue_state_write
```
```
In drivers/ata/libata-core.c (ffffffff8290c634)
Location: include/linux/string.h:75
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_parse_force_param
  - drivers/ata/libata-core.c:ata_parse_force_param
  - drivers/ata/libata-core.c:ata_parse_force_param
```
</details>
</li>
</ul>

## Differences
