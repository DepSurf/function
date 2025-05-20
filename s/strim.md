# Function: <code>strim</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
char *strim(char *s);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff813f2110)
Location: lib/string.c:454
Inline: True
Direct callers:
  - kernel/sched/core.c:sched_feat_write
  - kernel/cgroup.c:cgroup_release_agent_write
  - kernel/cgroup.c:__cgroup_procs_write
  - kernel/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup_freezer.c:freezer_write
  - kernel/cgroup_pids.c:pids_max_write
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/trace/ftrace.c:ftrace_pid_write
  - kernel/trace/trace.c:tracing_clock_write
  - kernel/trace/trace.c:trace_set_options
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_trigger.c:event_trigger_write
  - mm/zswap.c:__zswap_param_set
  - mm/memcontrol.c:memory_low_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:mem_cgroup_write
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_write
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/base.c:oom_score_adj_write
  - fs/proc/base.c:sched_autogroup_write
  - fs/proc/base.c:oom_adj_write
  - security/apparmor/lib.c:aa_split_fqname
  - security/apparmor/lib.c:aa_policy_init
  - security/apparmor/policy.c:aa_null_profile
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/device_cgroup.c:devcgroup_access_write
  - block/elevator.c:__elevator_change
  - block/cfq-iosched.c:__cfqg_set_weight_device
  - block/cfq-iosched.c:cfq_set_weight_on_dfl
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/thermal/thermal_core.c:policy_store
  - net/ipv4/tcp_memcontrol.c:tcp_cgroup_write
```
**Symbols:**

```
ffffffff813f2110-ffffffff813f2170: strim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
char *strim(char *s);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff81438ab0)
Location: lib/string.c:454
Inline: True
Direct callers:
  - kernel/sched/debug.c:sched_feat_write
  - kernel/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup.c:cgroup_release_agent_write
  - kernel/cgroup_freezer.c:freezer_write
  - kernel/cgroup_pids.c:pids_max_write
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/trace/trace.c:tracing_clock_write
  - kernel/trace/trace.c:trace_set_options
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_trigger.c:event_trigger_write
  - mm/zswap.c:__zswap_param_set
  - mm/memcontrol.c:swap_max_write
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:memory_low_write
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:mem_cgroup_write
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_write
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/base.c:sched_autogroup_write
  - fs/proc/base.c:oom_score_adj_write
  - fs/proc/base.c:oom_adj_write
  - security/apparmor/lib.c:aa_policy_init
  - security/apparmor/lib.c:aa_split_fqname
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_null_profile
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/device_cgroup.c:devcgroup_access_write
  - block/elevator.c:__elevator_change
  - block/cfq-iosched.c:cfq_set_weight_on_dfl
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/thermal/thermal_core.c:policy_store
```
**Symbols:**

```
ffffffff81438ab0-ffffffff81438b19: strim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
char *strim(char *s);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff81455aa0)
Location: lib/string.c:454
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_tasks_write
  - kernel/sched/debug.c:sched_feat_write
  - kernel/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup.c:cgroup_release_agent_write
  - kernel/cgroup_freezer.c:freezer_write
  - kernel/cgroup_pids.c:pids_max_write
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/trace/trace.c:tracing_clock_write
  - kernel/trace/trace.c:trace_set_options
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_trigger.c:event_trigger_write
  - mm/zswap.c:__zswap_param_set
  - mm/memcontrol.c:swap_max_write
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:memory_low_write
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:mem_cgroup_write
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_write
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/base.c:sched_autogroup_write
  - fs/proc/base.c:oom_score_adj_write
  - fs/proc/base.c:oom_adj_write
  - security/apparmor/lib.c:aa_policy_init
  - security/apparmor/lib.c:aa_split_fqname
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_null_profile
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/device_cgroup.c:devcgroup_access_write
  - block/elevator.c:__elevator_change
  - block/cfq-iosched.c:cfq_set_weight_on_dfl
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/thermal/thermal_core.c:thermal_zone_device_set_policy
```
**Symbols:**

```
ffffffff81455aa0-ffffffff81455b09: strim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
char *strim(char *s);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff818f7380)
Location: lib/string.c:454
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_schemata_write
  - kernel/sched/debug.c:sched_feat_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:__cgroup_procs_write
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write
  - kernel/cgroup/freezer.c:freezer_write
  - kernel/cgroup/pids.c:pids_max_write
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/trace/trace.c:tracing_clock_write
  - kernel/trace/trace.c:trace_set_options
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_trigger.c:event_trigger_write
  - mm/zswap.c:__zswap_param_set
  - mm/memcontrol.c:swap_max_write
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:memory_low_write
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:mem_cgroup_write
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_write
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/base.c:sched_autogroup_write
  - fs/proc/base.c:oom_score_adj_write
  - fs/proc/base.c:oom_adj_write
  - security/apparmor/lib.c:aa_policy_init
  - security/apparmor/lib.c:aa_split_fqname
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/device_cgroup.c:devcgroup_access_write
  - block/elevator.c:elv_iosched_store
  - block/cfq-iosched.c:cfq_set_weight_on_dfl
  - block/blk-mq-debugfs.c:queue_state_write
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/thermal/thermal_core.c:thermal_zone_device_set_policy
```
**Symbols:**

```
ffffffff818f7380-ffffffff818f73ee: strim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
char *strim(char *s);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff8197dd80)
Location: lib/string.c:455
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_schemata_write
  - kernel/sched/debug.c:sched_feat_write
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_max_depth_write
  - kernel/cgroup/cgroup.c:cgroup_max_descendants_write
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write_start
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write
  - kernel/cgroup/freezer.c:freezer_write
  - kernel/cgroup/pids.c:pids_max_write
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/trace/trace.c:tracing_clock_write
  - kernel/trace/trace.c:trace_set_options
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_trigger.c:event_trigger_write
  - mm/zswap.c:__zswap_param_set
  - mm/memcontrol.c:swap_max_write
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:memory_low_write
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:mem_cgroup_write
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_write
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/base.c:sched_autogroup_write
  - fs/proc/base.c:oom_score_adj_write
  - fs/proc/base.c:oom_adj_write
  - security/apparmor/lib.c:aa_policy_init
  - security/apparmor/lib.c:aa_split_fqname
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/device_cgroup.c:devcgroup_access_write
  - block/elevator.c:elv_iosched_store
  - block/cfq-iosched.c:cfq_set_weight_on_dfl
  - block/blk-mq-debugfs.c:queue_state_write
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/thermal/thermal_core.c:thermal_zone_device_set_policy
```
**Symbols:**

```
ffffffff8197dd80-ffffffff8197ddee: strim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
char *strim(char *s);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff819da270)
Location: lib/string.c:455
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_schemata_write
  - kernel/sched/debug.c:sched_feat_write
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_max_depth_write
  - kernel/cgroup/cgroup.c:cgroup_max_descendants_write
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write_start
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write
  - kernel/cgroup/freezer.c:freezer_write
  - kernel/cgroup/pids.c:pids_max_write
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/trace/trace.c:tracing_clock_write
  - kernel/trace/trace.c:trace_set_options
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_trigger.c:event_trigger_write
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:parse_action_params
  - mm/zswap.c:__zswap_param_set
  - mm/memcontrol.c:swap_max_write
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:memory_low_write
  - mm/memcontrol.c:memory_min_write
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:mem_cgroup_write
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_write
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/base.c:sched_autogroup_write
  - fs/proc/base.c:oom_score_adj_write
  - fs/proc/base.c:oom_adj_write
  - security/apparmor/lib.c:aa_policy_init
  - security/apparmor/lib.c:aa_split_fqname
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/device_cgroup.c:devcgroup_access_write
  - block/elevator.c:elv_iosched_store
  - block/cfq-iosched.c:cfq_set_weight_on_dfl
  - block/blk-mq-debugfs.c:queue_state_write
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/ata/libata-core.c:ata_parse_force_param
  - drivers/ata/libata-core.c:ata_parse_force_param
  - drivers/ata/libata-core.c:ata_parse_force_param
  - drivers/thermal/thermal_core.c:thermal_zone_device_set_policy
```
**Symbols:**

```
ffffffff819da270-ffffffff819da2cb: strim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
char *strim(char *s);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff81a12490)
Location: lib/string.c:456
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - kernel/sched/debug.c:sched_feat_write
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_max_depth_write
  - kernel/cgroup/cgroup.c:cgroup_max_descendants_write
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write_start
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write
  - kernel/cgroup/freezer.c:freezer_write
  - kernel/cgroup/pids.c:pids_max_write
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/trace/trace.c:tracing_clock_write
  - kernel/trace/trace.c:trace_set_options
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_trigger.c:event_trigger_write
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:parse_action_params
  - mm/zswap.c:__zswap_param_set
  - mm/memcontrol.c:swap_max_write
  - mm/memcontrol.c:memory_oom_group_write
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:memory_low_write
  - mm/memcontrol.c:memory_min_write
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:mem_cgroup_write
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_write
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/base.c:sched_autogroup_write
  - fs/proc/base.c:oom_score_adj_write
  - fs/proc/base.c:oom_adj_write
  - security/apparmor/lib.c:aa_policy_init
  - security/apparmor/lib.c:aa_split_fqname
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/device_cgroup.c:devcgroup_access_write
  - block/elevator.c:elv_iosched_store
  - block/blk-mq-debugfs.c:queue_state_write
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/ata/libata-core.c:ata_parse_force_param
  - drivers/ata/libata-core.c:ata_parse_force_param
  - drivers/ata/libata-core.c:ata_parse_force_param
  - drivers/thermal/thermal_core.c:thermal_zone_device_set_policy
```
**Symbols:**

```
ffffffff81a12490-ffffffff81a124eb: strim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
char *strim(char *s);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff81a81960)
Location: lib/string.c:498
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - kernel/sched/debug.c:sched_feat_write
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_freeze_write
  - kernel/cgroup/cgroup.c:cgroup_max_depth_write
  - kernel/cgroup/cgroup.c:cgroup_max_descendants_write
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write_start
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/pids.c:pids_max_write
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/trace/trace.c:tracing_clock_write
  - kernel/trace/trace.c:trace_set_options
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_trigger.c:event_trigger_write
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:parse_action_params
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - mm/zswap.c:__zswap_param_set
  - mm/memcontrol.c:swap_max_write
  - mm/memcontrol.c:memory_oom_group_write
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:memory_low_write
  - mm/memcontrol.c:memory_min_write
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:mem_cgroup_write
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_write
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/base.c:sched_autogroup_write
  - fs/proc/base.c:oom_score_adj_write
  - fs/proc/base.c:oom_adj_write
  - security/apparmor/lib.c:aa_policy_init
  - security/apparmor/lib.c:aa_split_fqname
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/device_cgroup.c:devcgroup_access_write
  - block/elevator.c:elv_iosched_store
  - block/blk-mq-debugfs.c:queue_state_write
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/ata/libata-core.c:ata_parse_force_param
  - drivers/ata/libata-core.c:ata_parse_force_param
  - drivers/ata/libata-core.c:ata_parse_force_param
  - drivers/thermal/thermal_core.c:thermal_zone_device_set_policy
  - drivers/md/dm-init.c:str_field_delimit
```
**Symbols:**

```
ffffffff81a81960-ffffffff81a819c0: strim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
char *strim(char *s);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff81ab8b60)
Location: lib/string.c:500
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - kernel/sched/debug.c:sched_feat_write
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_freeze_write
  - kernel/cgroup/cgroup.c:cgroup_max_depth_write
  - kernel/cgroup/cgroup.c:cgroup_max_descendants_write
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write_start
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/pids.c:pids_max_write
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/trace/trace.c:tracing_clock_write
  - kernel/trace/trace.c:trace_set_options
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_trigger.c:event_trigger_write
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:parse_action_params
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - mm/zswap.c:__zswap_param_set
  - mm/memcontrol.c:swap_max_write
  - mm/memcontrol.c:memory_oom_group_write
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:memory_low_write
  - mm/memcontrol.c:memory_min_write
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:mem_cgroup_write
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_write
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/base.c:sched_autogroup_write
  - fs/proc/base.c:oom_score_adj_write
  - fs/proc/base.c:oom_adj_write
  - security/apparmor/lib.c:aa_policy_init
  - security/apparmor/lib.c:aa_split_fqname
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/device_cgroup.c:devcgroup_access_write
  - block/elevator.c:elv_iosched_store
  - block/blk-mq-debugfs.c:queue_state_write
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/ata/libata-core.c:ata_parse_force_param
  - drivers/ata/libata-core.c:ata_parse_force_param
  - drivers/ata/libata-core.c:ata_parse_force_param
  - drivers/thermal/thermal_core.c:thermal_zone_device_set_policy
  - drivers/md/dm-init.c:str_field_delimit
```
**Symbols:**

```
ffffffff81ab8b60-ffffffff81ab8bc0: strim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
char *strim(char *s);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff815f3850)
Location: lib/string.c:541
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - kernel/sched/debug.c:sched_feat_write
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_freeze_write
  - kernel/cgroup/cgroup.c:cgroup_max_depth_write
  - kernel/cgroup/cgroup.c:cgroup_max_descendants_write
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write_start
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/pids.c:pids_max_write
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/trace/trace.c:tracing_clock_write
  - kernel/trace/trace.c:trace_set_options
  - kernel/trace/blktrace.c:blk_trace_str2mask
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_trigger.c:event_trigger_write
  - kernel/trace/trace_events_inject.c:event_inject_write
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:parse_action_params
  - kernel/trace/trace_events_hist.c:parse_assignment
  - mm/zswap.c:__zswap_param_set
  - mm/memcontrol.c:swap_max_write
  - mm/memcontrol.c:swap_high_write
  - mm/memcontrol.c:memory_oom_group_write
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:memory_low_write
  - mm/memcontrol.c:memory_min_write
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:mem_cgroup_write
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/base.c:sched_autogroup_write
  - fs/proc/base.c:oom_score_adj_write
  - fs/proc/base.c:oom_adj_write
  - security/apparmor/lib.c:aa_policy_init
  - security/apparmor/lib.c:aa_split_fqname
  - security/apparmor/policy.c:__list_lookup_parent
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/device_cgroup.c:devcgroup_access_write
  - block/elevator.c:__elevator_change
  - block/blk-mq-debugfs.c:queue_state_write
  - lib/bootconfig.c:xbc_parse_key
  - lib/bootconfig.c:__xbc_parse_keys
  - lib/bootconfig.c:__xbc_parse_value
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/thermal/thermal_core.c:thermal_zone_device_set_policy
  - drivers/md/dm-init.c:str_field_delimit
```
**Symbols:**

```
ffffffff815f3850-ffffffff815f38aa: strim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
char *strim(char *s);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff81617ee0)
Location: lib/string.c:538
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_stringify
  - kernel/sched/debug.c:sched_feat_write
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_freeze_write
  - kernel/cgroup/cgroup.c:cgroup_max_depth_write
  - kernel/cgroup/cgroup.c:cgroup_max_descendants_write
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write_start
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/pids.c:pids_max_write
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/trace/trace.c:tracing_clock_write
  - kernel/trace/trace.c:trace_set_options
  - kernel/trace/blktrace.c:blk_trace_str2mask
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_trigger.c:event_trigger_write
  - kernel/trace/trace_events_inject.c:event_inject_write
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:parse_action_params
  - kernel/trace/trace_events_hist.c:parse_assignment
  - mm/zswap.c:__zswap_param_set
  - mm/memcontrol.c:swap_max_write
  - mm/memcontrol.c:swap_high_write
  - mm/memcontrol.c:memory_oom_group_write
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:memory_low_write
  - mm/memcontrol.c:memory_min_write
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:mem_cgroup_write
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/base.c:sched_autogroup_write
  - fs/proc/base.c:oom_score_adj_write
  - fs/proc/base.c:oom_adj_write
  - security/apparmor/lib.c:aa_policy_init
  - security/apparmor/lib.c:aa_split_fqname
  - security/apparmor/policy.c:__list_lookup_parent
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/device_cgroup.c:devcgroup_access_write
  - block/elevator.c:__elevator_change
  - block/blk-mq-debugfs.c:queue_state_write
  - lib/bootconfig.c:xbc_parse_key
  - lib/bootconfig.c:__xbc_parse_keys
  - lib/bootconfig.c:__xbc_parse_value
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/thermal/thermal_core.c:thermal_zone_device_set_policy
  - drivers/md/dm-init.c:str_field_delimit
```
**Symbols:**

```
ffffffff81617ee0-ffffffff81617f3a: strim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
char *strim(char *s);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff815fb500)
Location: lib/string.c:538
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_stringify
  - kernel/sched/debug.c:sched_feat_write
  - kernel/cgroup/cgroup.c:cgroup_freeze_write
  - kernel/cgroup/cgroup.c:cgroup_max_depth_write
  - kernel/cgroup/cgroup.c:cgroup_max_descendants_write
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write_start
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/pids.c:pids_max_write
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/misc.c:misc_cg_max_write
  - kernel/trace/trace.c:tracing_clock_write
  - kernel/trace/trace.c:trace_set_options
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_trigger.c:event_trigger_write
  - kernel/trace/trace_events_inject.c:event_inject_write
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:parse_action_params
  - kernel/trace/trace_events_hist.c:parse_assignment
  - mm/zswap.c:__zswap_param_set
  - mm/memcontrol.c:swap_max_write
  - mm/memcontrol.c:swap_high_write
  - mm/memcontrol.c:memory_oom_group_write
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:memory_low_write
  - mm/memcontrol.c:memory_min_write
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:mem_cgroup_write
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/base.c:sched_autogroup_write
  - fs/proc/base.c:oom_score_adj_write
  - fs/proc/base.c:oom_adj_write
  - security/apparmor/lib.c:aa_policy_init
  - security/apparmor/lib.c:aa_split_fqname
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/device_cgroup.c:devcgroup_access_write
  - block/elevator.c:__elevator_change
  - block/blk-mq-debugfs.c:queue_state_write
  - lib/bootconfig.c:xbc_parse_key
  - lib/bootconfig.c:__xbc_parse_keys
  - lib/bootconfig.c:__xbc_parse_value
  - drivers/pinctrl/pinmux.c:pinmux_select
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/thermal/thermal_core.c:thermal_zone_device_set_policy
  - drivers/md/dm-init.c:str_field_delimit
```
**Symbols:**

```
ffffffff815fb500-ffffffff815fb55a: strim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
char *strim(char *s);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff81668dd0)
Location: lib/string.c:539
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_stringify
  - kernel/sched/debug.c:sched_feat_write
  - kernel/cgroup/cgroup.c:cgroup_freeze_write
  - kernel/cgroup/cgroup.c:cgroup_max_depth_write
  - kernel/cgroup/cgroup.c:cgroup_max_descendants_write
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write_start
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/pids.c:pids_max_write
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/misc.c:misc_cg_max_write
  - kernel/trace/trace.c:tracing_clock_write
  - kernel/trace/trace.c:trace_set_options
  - kernel/trace/trace_hwlat.c:hwlat_mode_write
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_trigger.c:event_trigger_write
  - kernel/trace/trace_events_inject.c:event_inject_write
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:parse_action_params
  - kernel/trace/trace_events_hist.c:parse_assignment
  - mm/zswap.c:__zswap_param_set
  - mm/memcontrol.c:swap_max_write
  - mm/memcontrol.c:swap_high_write
  - mm/memcontrol.c:memory_oom_group_write
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:memory_low_write
  - mm/memcontrol.c:memory_min_write
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:mem_cgroup_write
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/base.c:sched_autogroup_write
  - fs/proc/base.c:oom_score_adj_write
  - fs/proc/base.c:oom_adj_write
  - security/apparmor/lib.c:aa_policy_init
  - security/apparmor/lib.c:aa_split_fqname
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/device_cgroup.c:devcgroup_access_write
  - block/elevator.c:__elevator_change
  - block/blk-mq-debugfs.c:queue_state_write
  - lib/bootconfig.c:xbc_parse_key
  - lib/bootconfig.c:__xbc_parse_keys
  - lib/bootconfig.c:__xbc_parse_value
  - drivers/pinctrl/pinmux.c:pinmux_select
  - drivers/pci/pci.c:reset_method_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/thermal/thermal_core.c:thermal_zone_device_set_policy
  - drivers/md/dm-init.c:str_field_delimit
```
**Symbols:**

```
ffffffff81668dd0-ffffffff81668e2a: strim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
char *strim(char *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string_helpers.c (ffffffff816ecb00)
Location: lib/string_helpers.c:823
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_stringify
  - kernel/sched/build_utility.c:sched_dynamic_write
  - kernel/sched/build_utility.c:sched_feat_write
  - kernel/cgroup/cgroup.c:cgroup_freeze_write
  - kernel/cgroup/cgroup.c:cgroup_max_depth_write
  - kernel/cgroup/cgroup.c:cgroup_max_descendants_write
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write_start
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/pids.c:pids_max_write
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/misc.c:misc_cg_max_write
  - kernel/trace/trace.c:tracing_clock_write
  - kernel/trace/trace.c:tracing_set_trace_write
  - kernel/trace/trace.c:trace_set_options
  - kernel/trace/trace_hwlat.c:hwlat_mode_write
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_trigger.c:event_trigger_write
  - kernel/trace/trace_events_inject.c:event_inject_write
  - kernel/trace/trace_events_hist.c:event_hist_trigger_parse
  - kernel/trace/trace_events_hist.c:event_hist_trigger_parse
  - kernel/trace/trace_events_hist.c:parse_action_params
  - kernel/trace/trace_events_hist.c:parse_assignment
  - mm/zswap.c:__zswap_param_set
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
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/base.c:sched_autogroup_write
  - fs/proc/base.c:oom_score_adj_write
  - fs/proc/base.c:oom_adj_write
  - security/apparmor/lib.c:aa_policy_init
  - security/apparmor/lib.c:aa_split_fqname
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/device_cgroup.c:devcgroup_access_write
  - block/elevator.c:__elevator_change
  - block/blk-mq-debugfs.c:queue_state_write
  - lib/bootconfig.c:xbc_parse_key
  - lib/bootconfig.c:__xbc_parse_keys
  - lib/bootconfig.c:__xbc_parse_value
  - drivers/pinctrl/pinmux.c:pinmux_select
  - drivers/pci/pci.c:reset_method_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/thermal/thermal_core.c:thermal_zone_device_set_policy
  - drivers/md/dm-init.c:str_field_delimit
  - drivers/md/dm-init.c:str_field_delimit
```
**Symbols:**

```
ffffffff816ecb00-ffffffff816ecb65: strim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
char *strim(char *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string_helpers.c (ffffffff817dd3e0)
Location: lib/string_helpers.c:867
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_acpi_madt_oem_check
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
  - kernel/sched/build_utility.c:sched_dynamic_write
  - kernel/sched/build_utility.c:sched_feat_write
  - kernel/cgroup/cgroup.c:cgroup_freeze_write
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cgroup_max_depth_write
  - kernel/cgroup/cgroup.c:cgroup_max_descendants_write
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write_start
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/pids.c:pids_max_write
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/misc.c:misc_cg_max_write
  - kernel/trace/trace.c:tracing_clock_write
  - kernel/trace/trace.c:tracing_set_trace_write
  - kernel/trace/trace.c:trace_set_options
  - kernel/trace/trace_hwlat.c:hwlat_mode_write
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_trigger.c:event_trigger_write
  - kernel/trace/trace_events_inject.c:event_inject_write
  - kernel/trace/trace_events_hist.c:event_hist_trigger_parse
  - kernel/trace/trace_events_hist.c:event_hist_trigger_parse
  - kernel/trace/trace_events_hist.c:parse_action_params
  - kernel/trace/trace_events_hist.c:parse_assignment
  - kernel/trace/rv/rv.c:enabled_monitors_write
  - kernel/trace/rv/rv_reactors.c:monitor_reactors_write
  - mm/zswap.c:__zswap_param_set
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
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/base.c:sched_autogroup_write
  - fs/proc/base.c:oom_score_adj_write
  - fs/proc/base.c:oom_adj_write
  - security/apparmor/lib.c:aa_policy_init
  - security/apparmor/lib.c:aa_split_fqname
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_new_learning_profile
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/device_cgroup.c:devcgroup_access_write
  - block/elevator.c:elv_iosched_store
  - block/blk-mq-debugfs.c:queue_state_write
  - lib/bootconfig.c:xbc_parse_tree
  - lib/bootconfig.c:xbc_parse_tree
  - lib/bootconfig.c:__xbc_parse_keys
  - lib/bootconfig.c:__xbc_parse_value
  - drivers/pinctrl/pinmux.c:pinmux_select
  - drivers/pci/pci.c:reset_method_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/thermal/thermal_core.c:thermal_zone_device_set_policy
  - drivers/md/dm-init.c:dm_parse_device_entry
  - drivers/md/dm-init.c:dm_parse_device_entry
  - drivers/md/dm-init.c:dm_parse_device_entry
  - drivers/md/dm-init.c:dm_parse_device_entry
  - drivers/md/dm-init.c:dm_parse_table_entry
  - drivers/md/dm-init.c:dm_parse_table_entry
  - drivers/md/dm-init.c:dm_parse_table_entry
  - drivers/md/dm-init.c:dm_parse_table_entry
```
**Symbols:**

```
ffffffff817dd3e0-ffffffff817dd445: strim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
char *strim(char *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string_helpers.c (ffffffff8181cbf0)
Location: lib/string_helpers.c:867
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mon_config_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_acpi_madt_oem_check
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
  - kernel/sched/build_utility.c:sched_dynamic_write
  - kernel/sched/build_utility.c:sched_feat_write
  - kernel/cgroup/cgroup.c:cgroup_freeze_write
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cgroup_max_depth_write
  - kernel/cgroup/cgroup.c:cgroup_max_descendants_write
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write_start
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/pids.c:pids_max_write
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/misc.c:misc_cg_max_write
  - kernel/trace/trace.c:tracing_clock_write
  - kernel/trace/trace.c:tracing_set_trace_write
  - kernel/trace/trace.c:trace_set_options
  - kernel/trace/trace_hwlat.c:hwlat_mode_write
  - kernel/trace/trace_osnoise.c:osnoise_options_write
  - kernel/trace/trace_osnoise.c:osnoise_options_write
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_trigger.c:event_trigger_write
  - kernel/trace/trace_events_inject.c:event_inject_write
  - kernel/trace/trace_events_hist.c:event_hist_trigger_parse
  - kernel/trace/trace_events_hist.c:event_hist_trigger_parse
  - kernel/trace/trace_events_hist.c:parse_action_params
  - kernel/trace/trace_events_hist.c:parse_assignment
  - kernel/trace/rv/rv.c:enabled_monitors_write
  - kernel/trace/rv/rv_reactors.c:monitor_reactors_write
  - mm/zswap.c:__zswap_param_set
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
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/base.c:sched_autogroup_write
  - fs/proc/base.c:oom_score_adj_write
  - fs/proc/base.c:oom_adj_write
  - security/apparmor/lib.c:aa_policy_init
  - security/apparmor/lib.c:aa_split_fqname
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_new_learning_profile
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/device_cgroup.c:devcgroup_access_write
  - block/elevator.c:elv_iosched_store
  - block/blk-mq-debugfs.c:queue_state_write
  - lib/bootconfig.c:xbc_parse_tree
  - lib/bootconfig.c:xbc_parse_tree
  - lib/bootconfig.c:__xbc_parse_keys
  - lib/bootconfig.c:__xbc_parse_value
  - drivers/pinctrl/pinmux.c:pinmux_select
  - drivers/pci/pci.c:reset_method_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/thermal/thermal_core.c:thermal_zone_device_set_policy
  - drivers/md/dm-init.c:dm_parse_device_entry
  - drivers/md/dm-init.c:dm_parse_device_entry
  - drivers/md/dm-init.c:dm_parse_device_entry
  - drivers/md/dm-init.c:dm_parse_device_entry
  - drivers/md/dm-init.c:dm_parse_table_entry
  - drivers/md/dm-init.c:dm_parse_table_entry
  - drivers/md/dm-init.c:dm_parse_table_entry
  - drivers/md/dm-init.c:dm_parse_table_entry
```
**Symbols:**

```
ffffffff8181cbf0-ffffffff8181cc55: strim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
char *strim(char *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string_helpers.c (ffffffff81862a00)
Location: lib/string_helpers.c:884
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mon_config_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_stringify
  - kernel/sched/build_utility.c:sched_dynamic_write
  - kernel/sched/build_utility.c:sched_feat_write
  - kernel/cgroup/cgroup.c:cgroup_freeze_write
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cgroup_max_depth_write
  - kernel/cgroup/cgroup.c:cgroup_max_descendants_write
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write_start
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/pids.c:pids_max_write
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/misc.c:misc_cg_max_write
  - kernel/trace/trace.c:tracing_clock_write
  - kernel/trace/trace.c:tracing_set_trace_write
  - kernel/trace/trace.c:trace_set_options
  - kernel/trace/trace_hwlat.c:hwlat_mode_write
  - kernel/trace/trace_osnoise.c:osnoise_options_write
  - kernel/trace/trace_osnoise.c:osnoise_options_write
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_trigger.c:event_trigger_write
  - kernel/trace/trace_events_inject.c:event_inject_write
  - kernel/trace/trace_events_hist.c:event_hist_trigger_parse
  - kernel/trace/trace_events_hist.c:event_hist_trigger_parse
  - kernel/trace/trace_events_hist.c:parse_action_params
  - kernel/trace/trace_events_hist.c:parse_assignment
  - kernel/trace/rv/rv.c:enabled_monitors_write
  - kernel/trace/rv/rv_reactors.c:monitor_reactors_write
  - mm/zswap.c:__zswap_param_set
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
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/base.c:sched_autogroup_write
  - fs/proc/base.c:oom_score_adj_write
  - fs/proc/base.c:oom_adj_write
  - fs/debugfs/file.c:debugfs_write_file_str
  - security/apparmor/lib.c:aa_policy_init
  - security/apparmor/lib.c:aa_split_fqname
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_new_learning_profile
  - security/apparmor/lsm.c:do_setattr
  - security/device_cgroup.c:devcgroup_access_write
  - block/elevator.c:elv_iosched_store
  - block/blk-mq-debugfs.c:queue_state_write
  - lib/bootconfig.c:xbc_parse_tree
  - lib/bootconfig.c:xbc_parse_tree
  - lib/bootconfig.c:__xbc_parse_keys
  - lib/bootconfig.c:__xbc_parse_value
  - drivers/pinctrl/pinmux.c:pinmux_select
  - drivers/pci/pci.c:reset_method_store
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/thermal/thermal_core.c:thermal_zone_device_set_policy
  - drivers/md/dm-init.c:dm_parse_device_entry
  - drivers/md/dm-init.c:dm_parse_device_entry
  - drivers/md/dm-init.c:dm_parse_device_entry
  - drivers/md/dm-init.c:dm_parse_device_entry
  - drivers/md/dm-init.c:dm_parse_table_entry
  - drivers/md/dm-init.c:dm_parse_table_entry
  - drivers/md/dm-init.c:dm_parse_table_entry
  - drivers/md/dm-init.c:dm_parse_table_entry
```
**Symbols:**

```
ffffffff81862a00-ffffffff81862a65: strim (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
char *strim(char *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffff800010d92ef0)
Location: lib/string.c:500
Inline: False
Direct callers:
  - kernel/sched/debug.c:sched_feat_write
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_freeze_write
  - kernel/cgroup/cgroup.c:cgroup_max_depth_write
  - kernel/cgroup/cgroup.c:cgroup_max_descendants_write
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write_start
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/pids.c:pids_max_write
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/trace/trace.c:tracing_clock_write
  - kernel/trace/trace.c:trace_set_options
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_trigger.c:event_trigger_write
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:parse_action_params
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - mm/zswap.c:__zswap_param_set
  - mm/memcontrol.c:swap_max_write
  - mm/memcontrol.c:memory_oom_group_write
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:memory_low_write
  - mm/memcontrol.c:memory_min_write
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:mem_cgroup_write
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_write
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/base.c:sched_autogroup_write
  - fs/proc/base.c:oom_score_adj_write
  - fs/proc/base.c:oom_adj_write
  - security/apparmor/lib.c:aa_policy_init
  - security/apparmor/lib.c:aa_split_fqname
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/device_cgroup.c:devcgroup_access_write
  - block/elevator.c:elv_iosched_store
  - block/blk-mq-debugfs.c:queue_state_write
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/ata/libata-core.c:ata_parse_force_param
  - drivers/ata/libata-core.c:ata_parse_force_param
  - drivers/ata/libata-core.c:ata_parse_force_param
  - drivers/thermal/thermal_core.c:thermal_zone_device_set_policy
  - drivers/md/dm-init.c:str_field_delimit
```
**Symbols:**

```
ffff800010d92ef0-ffff800010d92f64: strim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
char *strim(char *s);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/string.c (c0e8f880)
Location: lib/string.c:500
Inline: True
Direct callers:
  - kernel/sched/debug.c:sched_feat_write
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_freeze_write
  - kernel/cgroup/cgroup.c:cgroup_max_depth_write
  - kernel/cgroup/cgroup.c:cgroup_max_descendants_write
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write_start
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/pids.c:pids_max_write
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/trace/trace.c:tracing_clock_write
  - kernel/trace/trace.c:trace_set_options
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_trigger.c:event_trigger_write
  - mm/zswap.c:__zswap_param_set
  - mm/memcontrol.c:swap_max_write
  - mm/memcontrol.c:memory_oom_group_write
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:memory_low_write
  - mm/memcontrol.c:memory_min_write
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:mem_cgroup_write
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/base.c:sched_autogroup_write
  - fs/proc/base.c:oom_score_adj_write
  - fs/proc/base.c:oom_adj_write
  - security/apparmor/lib.c:aa_policy_init
  - security/apparmor/lib.c:aa_split_fqname
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/device_cgroup.c:devcgroup_access_write
  - block/elevator.c:elv_iosched_store
  - block/blk-mq-debugfs.c:queue_state_write
  - drivers/ata/libata-core.c:ata_parse_force_param
  - drivers/ata/libata-core.c:ata_parse_force_param
  - drivers/ata/libata-core.c:ata_parse_force_param
  - drivers/mtd/nand/raw/nand_base.c:sanitize_string
  - drivers/thermal/thermal_core.c:thermal_zone_device_set_policy
  - drivers/md/dm-init.c:str_field_delimit
```
**Symbols:**

```
c0e8f880-c0e8f914: strim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
char *strim(char *s);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/string.c (c000000000ed7350)
Location: lib/string.c:500
Inline: True
Direct callers:
  - arch/powerpc/platforms/pseries/lpar.c:cmo_free_hint
  - kernel/sched/debug.c:sched_feat_write
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_freeze_write
  - kernel/cgroup/cgroup.c:cgroup_max_depth_write
  - kernel/cgroup/cgroup.c:cgroup_max_descendants_write
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write_start
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/pids.c:pids_max_write
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/trace/trace.c:tracing_clock_write
  - kernel/trace/trace.c:trace_set_options
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_trigger.c:event_trigger_write
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:parse_action_params
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - mm/zswap.c:__zswap_param_set
  - mm/memcontrol.c:swap_max_write
  - mm/memcontrol.c:memory_oom_group_write
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:memory_low_write
  - mm/memcontrol.c:memory_min_write
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:mem_cgroup_write
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_write
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/base.c:sched_autogroup_write
  - fs/proc/base.c:oom_score_adj_write
  - fs/proc/base.c:oom_adj_write
  - security/apparmor/lib.c:aa_policy_init
  - security/apparmor/lib.c:aa_split_fqname
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/device_cgroup.c:devcgroup_access_write
  - block/elevator.c:elv_iosched_store
  - block/blk-mq-debugfs.c:queue_state_write
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/ata/libata-core.c:ata_parse_force_param
  - drivers/ata/libata-core.c:ata_parse_force_param
  - drivers/ata/libata-core.c:ata_parse_force_param
  - drivers/thermal/thermal_core.c:thermal_zone_device_set_policy
  - drivers/md/dm-init.c:str_field_delimit
```
**Symbols:**

```
c000000000ed7350-c000000000ed7408: strim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
char *strim(char *s);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffe0008bd2ac)
Location: lib/string.c:500
Inline: True
Direct callers:
  - kernel/sched/debug.c:sched_feat_write
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_freeze_write
  - kernel/cgroup/cgroup.c:cgroup_max_depth_write
  - kernel/cgroup/cgroup.c:cgroup_max_descendants_write
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write_start
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/pids.c:pids_max_write
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/trace/trace.c:tracing_clock_write
  - kernel/trace/trace.c:trace_set_options
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_trigger.c:event_trigger_write
  - mm/zswap.c:__zswap_param_set
  - mm/memcontrol.c:swap_max_write
  - mm/memcontrol.c:memory_oom_group_write
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:memory_low_write
  - mm/memcontrol.c:memory_min_write
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:mem_cgroup_write
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_write
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/base.c:sched_autogroup_write
  - fs/proc/base.c:oom_score_adj_write
  - fs/proc/base.c:oom_adj_write
  - security/apparmor/lib.c:aa_policy_init
  - security/apparmor/lib.c:aa_split_fqname
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/device_cgroup.c:devcgroup_access_write
  - block/elevator.c:elv_iosched_store
  - block/blk-mq-debugfs.c:queue_state_write
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/ata/libata-core.c:ata_parse_force_param
  - drivers/ata/libata-core.c:ata_parse_force_param
  - drivers/ata/libata-core.c:ata_parse_force_param
  - drivers/thermal/thermal_core.c:thermal_zone_device_set_policy
  - drivers/md/dm-init.c:str_field_delimit
```
**Symbols:**

```
ffffffe0008bd2ac-ffffffe0008bd31e: strim (STB_GLOBAL)
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
char *strim(char *s);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff81a579b0)
Location: lib/string.c:500
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - kernel/sched/debug.c:sched_feat_write
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_freeze_write
  - kernel/cgroup/cgroup.c:cgroup_max_depth_write
  - kernel/cgroup/cgroup.c:cgroup_max_descendants_write
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write_start
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/pids.c:pids_max_write
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/trace/trace.c:tracing_clock_write
  - kernel/trace/trace.c:trace_set_options
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_trigger.c:event_trigger_write
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:parse_action_params
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - mm/zswap.c:__zswap_param_set
  - mm/memcontrol.c:swap_max_write
  - mm/memcontrol.c:memory_oom_group_write
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:memory_low_write
  - mm/memcontrol.c:memory_min_write
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:mem_cgroup_write
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_write
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/base.c:sched_autogroup_write
  - fs/proc/base.c:oom_score_adj_write
  - fs/proc/base.c:oom_adj_write
  - security/apparmor/lib.c:aa_policy_init
  - security/apparmor/lib.c:aa_split_fqname
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/device_cgroup.c:devcgroup_access_write
  - block/elevator.c:elv_iosched_store
  - block/blk-mq-debugfs.c:queue_state_write
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/ata/libata-core.c:ata_parse_force_param
  - drivers/ata/libata-core.c:ata_parse_force_param
  - drivers/ata/libata-core.c:ata_parse_force_param
  - drivers/thermal/thermal_core.c:thermal_zone_device_set_policy
  - drivers/md/dm-init.c:str_field_delimit
```
**Symbols:**

```
ffffffff81a579b0-ffffffff81a57a10: strim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
char *strim(char *s);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff81a14a90)
Location: lib/string.c:500
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - kernel/sched/debug.c:sched_feat_write
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_freeze_write
  - kernel/cgroup/cgroup.c:cgroup_max_depth_write
  - kernel/cgroup/cgroup.c:cgroup_max_descendants_write
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write_start
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/pids.c:pids_max_write
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/trace/trace.c:tracing_clock_write
  - kernel/trace/trace.c:trace_set_options
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_trigger.c:event_trigger_write
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:parse_action_params
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - mm/zswap.c:__zswap_param_set
  - mm/memcontrol.c:swap_max_write
  - mm/memcontrol.c:memory_oom_group_write
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:memory_low_write
  - mm/memcontrol.c:memory_min_write
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:mem_cgroup_write
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_write
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/base.c:sched_autogroup_write
  - fs/proc/base.c:oom_score_adj_write
  - fs/proc/base.c:oom_adj_write
  - security/apparmor/lib.c:aa_policy_init
  - security/apparmor/lib.c:aa_split_fqname
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/device_cgroup.c:devcgroup_access_write
  - block/elevator.c:elv_iosched_store
  - block/blk-mq-debugfs.c:queue_state_write
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/ata/libata-core.c:ata_parse_force_param
  - drivers/ata/libata-core.c:ata_parse_force_param
  - drivers/ata/libata-core.c:ata_parse_force_param
  - drivers/thermal/thermal_core.c:thermal_zone_device_set_policy
  - drivers/md/dm-init.c:str_field_delimit
```
**Symbols:**

```
ffffffff81a14a90-ffffffff81a14af0: strim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
char *strim(char *s);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff81ac3da0)
Location: lib/string.c:500
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - kernel/sched/debug.c:sched_feat_write
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_freeze_write
  - kernel/cgroup/cgroup.c:cgroup_max_depth_write
  - kernel/cgroup/cgroup.c:cgroup_max_descendants_write
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write_start
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/pids.c:pids_max_write
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/trace/trace.c:tracing_clock_write
  - kernel/trace/trace.c:trace_set_options
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_trigger.c:event_trigger_write
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:parse_action_params
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - mm/zswap.c:__zswap_param_set
  - mm/memcontrol.c:swap_max_write
  - mm/memcontrol.c:memory_oom_group_write
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:memory_low_write
  - mm/memcontrol.c:memory_min_write
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:mem_cgroup_write
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_write
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/base.c:sched_autogroup_write
  - fs/proc/base.c:oom_score_adj_write
  - fs/proc/base.c:oom_adj_write
  - security/apparmor/lib.c:aa_policy_init
  - security/apparmor/lib.c:aa_split_fqname
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/device_cgroup.c:devcgroup_access_write
  - block/elevator.c:elv_iosched_store
  - block/blk-mq-debugfs.c:queue_state_write
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/ata/libata-core.c:ata_parse_force_param
  - drivers/ata/libata-core.c:ata_parse_force_param
  - drivers/ata/libata-core.c:ata_parse_force_param
  - drivers/thermal/thermal_core.c:thermal_zone_device_set_policy
```
**Symbols:**

```
ffffffff81ac3da0-ffffffff81ac3e00: strim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
char *strim(char *s);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff81ad0270)
Location: lib/string.c:500
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_write
  - kernel/sched/debug.c:sched_feat_write
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_freeze_write
  - kernel/cgroup/cgroup.c:cgroup_max_depth_write
  - kernel/cgroup/cgroup.c:cgroup_max_descendants_write
  - kernel/cgroup/cgroup.c:cgroup_type_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write_start
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/pids.c:pids_max_write
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/trace/trace.c:tracing_clock_write
  - kernel/trace/trace.c:trace_set_options
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_trigger.c:event_trigger_write
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:parse_action_params
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - mm/zswap.c:__zswap_param_set
  - mm/memcontrol.c:swap_max_write
  - mm/memcontrol.c:memory_oom_group_write
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:memory_low_write
  - mm/memcontrol.c:memory_min_write
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:mem_cgroup_write
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_write
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/base.c:sched_autogroup_write
  - fs/proc/base.c:oom_score_adj_write
  - fs/proc/base.c:oom_adj_write
  - security/apparmor/lib.c:aa_policy_init
  - security/apparmor/lib.c:aa_split_fqname
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/device_cgroup.c:devcgroup_access_write
  - block/elevator.c:elv_iosched_store
  - block/blk-mq-debugfs.c:queue_state_write
  - drivers/nvdimm/namespace_devs.c:alt_name_store
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/ata/libata-core.c:ata_parse_force_param
  - drivers/ata/libata-core.c:ata_parse_force_param
  - drivers/ata/libata-core.c:ata_parse_force_param
  - drivers/thermal/thermal_core.c:thermal_zone_device_set_policy
  - drivers/md/dm-init.c:str_field_delimit
```
**Symbols:**

```
ffffffff81ad0270-ffffffff81ad02d0: strim (STB_GLOBAL)
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
