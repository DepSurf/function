# Function: <code>of_css</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct cgroup_subsys_state *of_css(struct kernfs_open_file *of);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff81111e30)
Location: kernel/cgroup.c:461
Inline: True
Inline callers:
  - kernel/cgroup.c:cgroup_seqfile_show
  - kernel/cgroup.c:cgroup_events_show
  - kernel/cgroup.c:cgroup_pidlist_stop
  - kernel/cgroup.c:cgroup_release_agent_show
  - kernel/cgroup.c:cgroup_subtree_control_show
  - kernel/cgroup.c:cgroup_controllers_show
  - kernel/cgroup.c:cgroup_root_controllers_show
  - kernel/cgroup.c:cgroup_pidlist_next
  - kernel/cgroup.c:cgroup_pidlist_start
Direct callers:
  - kernel/sched/core.c:cpu_stats_show
  - kernel/sched/cpuacct.c:cpuacct_stats_show
  - kernel/sched/cpuacct.c:cpuacct_percpu_seq_show
  - kernel/cgroup_freezer.c:freezer_read
  - kernel/cgroup_freezer.c:freezer_write
  - kernel/cgroup_pids.c:pids_max_write
  - kernel/cpuset.c:cpuset_common_seq_show
  - kernel/cpuset.c:cpuset_write_resmask
  - mm/slab_common.c:memcg_slab_show
  - mm/memcontrol.c:mem_cgroup_oom_control_read
  - mm/memcontrol.c:memory_low_write
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memcontrol.c:memory_max_show
  - mm/memcontrol.c:memory_high_show
  - mm/memcontrol.c:memory_low_show
  - mm/memcontrol.c:memory_events_show
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:mem_cgroup_write
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_reset
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_write
  - security/device_cgroup.c:devcgroup_access_write
  - security/device_cgroup.c:devcgroup_seq_show
  - block/blk-cgroup.c:blkg_print_stat_bytes
  - block/blk-cgroup.c:blkg_print_stat_ios
  - block/blk-cgroup.c:blkg_print_stat_bytes_recursive
  - block/blk-cgroup.c:blkg_print_stat_ios_recursive
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-throttle.c:tg_print_conf_uint
  - block/blk-throttle.c:tg_print_conf_u64
  - block/blk-throttle.c:tg_print_max
  - block/blk-throttle.c:tg_set_conf
  - block/blk-throttle.c:tg_set_max
  - block/cfq-iosched.c:cfqg_print_rwstat_recursive
  - block/cfq-iosched.c:cfqg_print_stat_sectors_recursive
  - block/cfq-iosched.c:cfqg_print_stat_recursive
  - block/cfq-iosched.c:cfqg_print_rwstat
  - block/cfq-iosched.c:cfqg_print_stat_sectors
  - block/cfq-iosched.c:cfqg_print_stat
  - block/cfq-iosched.c:cfqg_print_weight_device
  - block/cfq-iosched.c:cfqg_print_leaf_weight_device
  - block/cfq-iosched.c:cfq_print_weight
  - block/cfq-iosched.c:cfq_print_leaf_weight
  - block/cfq-iosched.c:cfq_print_weight_on_dfl
  - block/cfq-iosched.c:__cfqg_set_weight_device
  - block/cfq-iosched.c:cfq_set_weight_on_dfl
  - net/core/netprio_cgroup.c:read_priomap
  - net/core/netprio_cgroup.c:write_priomap
  - net/ipv4/tcp_memcontrol.c:tcp_cgroup_reset
  - net/ipv4/tcp_memcontrol.c:tcp_cgroup_write
```
**Symbols:**

```
ffffffff81111e30-ffffffff81111e66: of_css (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct cgroup_subsys_state *of_css(struct kernfs_open_file *of);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff8111ad59)
Location: kernel/cgroup.c:498
Inline: True
Inline callers:
  - kernel/cgroup.c:cgroup_pidlist_next
  - kernel/cgroup.c:cgroup_pidlist_stop
  - kernel/cgroup.c:cgroup_pidlist_start
  - kernel/cgroup.c:cgroup_seqfile_show
  - kernel/cgroup.c:cgroup_events_show
  - kernel/cgroup.c:cgroup_subtree_control_show
  - kernel/cgroup.c:cgroup_controllers_show
  - kernel/cgroup.c:cgroup_release_agent_show
Direct callers:
  - kernel/sched/core.c:cpu_stats_show
  - kernel/sched/cpuacct.c:cpuacct_stats_show
  - kernel/sched/cpuacct.c:cpuacct_all_seq_show
  - kernel/sched/cpuacct.c:__cpuacct_percpu_seq_show
  - kernel/cgroup_freezer.c:freezer_write
  - kernel/cgroup_freezer.c:freezer_read
  - kernel/cgroup_pids.c:pids_events_show
  - kernel/cgroup_pids.c:pids_max_write
  - kernel/cpuset.c:cpuset_common_seq_show
  - kernel/cpuset.c:cpuset_write_resmask
  - mm/slab_common.c:memcg_slab_show
  - mm/memcontrol.c:swap_max_write
  - mm/memcontrol.c:swap_max_show
  - mm/memcontrol.c:memory_stat_show
  - mm/memcontrol.c:memory_events_show
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_max_show
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:memory_high_show
  - mm/memcontrol.c:memory_low_write
  - mm/memcontrol.c:memory_low_show
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:mem_cgroup_oom_control_read
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:mem_cgroup_write
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_reset
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_write
  - security/device_cgroup.c:devcgroup_access_write
  - security/device_cgroup.c:devcgroup_seq_show
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-cgroup.c:blkg_print_stat_ios_recursive
  - block/blk-cgroup.c:blkg_print_stat_bytes_recursive
  - block/blk-cgroup.c:blkg_print_stat_ios
  - block/blk-cgroup.c:blkg_print_stat_bytes
  - block/blk-throttle.c:tg_set_max
  - block/blk-throttle.c:tg_print_max
  - block/blk-throttle.c:tg_print_conf_uint
  - block/blk-throttle.c:tg_print_conf_u64
  - block/cfq-iosched.c:cfq_set_weight_on_dfl
  - block/cfq-iosched.c:cfq_print_weight_on_dfl
  - block/cfq-iosched.c:cfqg_print_stat_sectors_recursive
  - block/cfq-iosched.c:cfqg_print_stat_sectors
  - block/cfq-iosched.c:cfqg_print_rwstat_recursive
  - block/cfq-iosched.c:cfqg_print_stat_recursive
  - block/cfq-iosched.c:cfqg_print_rwstat
  - block/cfq-iosched.c:cfqg_print_stat
  - block/cfq-iosched.c:cfq_print_leaf_weight
  - block/cfq-iosched.c:cfq_print_weight
  - block/cfq-iosched.c:cfqg_print_leaf_weight_device
  - block/cfq-iosched.c:cfqg_print_weight_device
  - net/core/netprio_cgroup.c:write_priomap
  - net/core/netprio_cgroup.c:read_priomap
```
**Symbols:**

```
ffffffff81119560-ffffffff81119595: of_css (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct cgroup_subsys_state *of_css(struct kernfs_open_file *of);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff81122c16)
Location: kernel/cgroup.c:501
Inline: True
Inline callers:
  - kernel/cgroup.c:cgroup_pidlist_next
  - kernel/cgroup.c:cgroup_pidlist_stop
  - kernel/cgroup.c:cgroup_pidlist_start
  - kernel/cgroup.c:cgroup_seqfile_show
  - kernel/cgroup.c:cgroup_events_show
  - kernel/cgroup.c:cgroup_subtree_control_show
  - kernel/cgroup.c:cgroup_controllers_show
  - kernel/cgroup.c:cgroup_release_agent_show
Direct callers:
  - kernel/sched/core.c:cpu_stats_show
  - kernel/sched/cpuacct.c:cpuacct_stats_show
  - kernel/sched/cpuacct.c:cpuacct_all_seq_show
  - kernel/sched/cpuacct.c:__cpuacct_percpu_seq_show
  - kernel/cgroup_freezer.c:freezer_write
  - kernel/cgroup_freezer.c:freezer_read
  - kernel/cgroup_pids.c:pids_events_show
  - kernel/cgroup_pids.c:pids_max_write
  - kernel/cpuset.c:cpuset_common_seq_show
  - kernel/cpuset.c:cpuset_write_resmask
  - mm/slab_common.c:memcg_slab_show
  - mm/memcontrol.c:swap_max_write
  - mm/memcontrol.c:swap_max_show
  - mm/memcontrol.c:memory_stat_show
  - mm/memcontrol.c:memory_events_show
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_max_show
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:memory_high_show
  - mm/memcontrol.c:memory_low_write
  - mm/memcontrol.c:memory_low_show
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:mem_cgroup_oom_control_read
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:mem_cgroup_write
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_reset
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_write
  - security/device_cgroup.c:devcgroup_access_write
  - security/device_cgroup.c:devcgroup_seq_show
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-cgroup.c:blkg_print_stat_ios_recursive
  - block/blk-cgroup.c:blkg_print_stat_bytes_recursive
  - block/blk-cgroup.c:blkg_print_stat_ios
  - block/blk-cgroup.c:blkg_print_stat_bytes
  - block/blk-throttle.c:tg_set_max
  - block/blk-throttle.c:tg_print_max
  - block/blk-throttle.c:tg_print_conf_uint
  - block/blk-throttle.c:tg_print_conf_u64
  - block/cfq-iosched.c:cfq_set_weight_on_dfl
  - block/cfq-iosched.c:cfq_print_weight_on_dfl
  - block/cfq-iosched.c:cfqg_print_stat_sectors_recursive
  - block/cfq-iosched.c:cfqg_print_stat_sectors
  - block/cfq-iosched.c:cfqg_print_rwstat_recursive
  - block/cfq-iosched.c:cfqg_print_stat_recursive
  - block/cfq-iosched.c:cfqg_print_rwstat
  - block/cfq-iosched.c:cfqg_print_stat
  - block/cfq-iosched.c:cfq_print_leaf_weight
  - block/cfq-iosched.c:cfq_print_weight
  - block/cfq-iosched.c:cfqg_print_leaf_weight_device
  - block/cfq-iosched.c:cfqg_print_weight_device
  - net/core/netprio_cgroup.c:write_priomap
  - net/core/netprio_cgroup.c:read_priomap
```
**Symbols:**

```
ffffffff81120d30-ffffffff81120d65: of_css (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct cgroup_subsys_state *of_css(struct kernfs_open_file *of);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811280d7)
Location: kernel/cgroup/cgroup.c:455
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_procs_start
  - kernel/cgroup/cgroup.c:cgroup_seqfile_show
  - kernel/cgroup/cgroup.c:cgroup_events_show
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_show
  - kernel/cgroup/cgroup.c:cgroup_controllers_show
Direct callers:
  - kernel/sched/core.c:cpu_stats_show
  - kernel/sched/cpuacct.c:cpuacct_stats_show
  - kernel/sched/cpuacct.c:cpuacct_all_seq_show
  - kernel/sched/cpuacct.c:__cpuacct_percpu_seq_show
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_show
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_stop
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
  - kernel/cgroup/freezer.c:freezer_write
  - kernel/cgroup/freezer.c:freezer_read
  - kernel/cgroup/pids.c:pids_events_show
  - kernel/cgroup/pids.c:pids_max_write
  - kernel/cgroup/rdma.c:rdmacg_resource_read
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/cgroup/cpuset.c:cpuset_common_seq_show
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - mm/slab_common.c:memcg_slab_show
  - mm/slab_common.c:memcg_slab_next
  - mm/slab_common.c:memcg_slab_start
  - mm/memcontrol.c:swap_max_write
  - mm/memcontrol.c:swap_max_show
  - mm/memcontrol.c:memory_stat_show
  - mm/memcontrol.c:memory_events_show
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_max_show
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:memory_high_show
  - mm/memcontrol.c:memory_low_write
  - mm/memcontrol.c:memory_low_show
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:mem_cgroup_oom_control_read
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:mem_cgroup_reset
  - mm/memcontrol.c:mem_cgroup_write
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_reset
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_write
  - security/device_cgroup.c:devcgroup_access_write
  - security/device_cgroup.c:devcgroup_seq_show
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-cgroup.c:blkg_print_stat_ios_recursive
  - block/blk-cgroup.c:blkg_print_stat_bytes_recursive
  - block/blk-cgroup.c:blkg_print_stat_ios
  - block/blk-cgroup.c:blkg_print_stat_bytes
  - block/blk-throttle.c:tg_set_limit
  - block/blk-throttle.c:tg_print_limit
  - block/blk-throttle.c:tg_print_conf_uint
  - block/blk-throttle.c:tg_print_conf_u64
  - block/cfq-iosched.c:cfq_set_weight_on_dfl
  - block/cfq-iosched.c:cfq_print_weight_on_dfl
  - block/cfq-iosched.c:cfqg_print_stat_sectors_recursive
  - block/cfq-iosched.c:cfqg_print_stat_sectors
  - block/cfq-iosched.c:cfqg_print_rwstat_recursive
  - block/cfq-iosched.c:cfqg_print_stat_recursive
  - block/cfq-iosched.c:cfqg_print_rwstat
  - block/cfq-iosched.c:cfqg_print_stat
  - block/cfq-iosched.c:cfq_print_leaf_weight
  - block/cfq-iosched.c:cfq_print_weight
  - block/cfq-iosched.c:cfqg_print_leaf_weight_device
  - block/cfq-iosched.c:cfqg_print_weight_device
  - net/core/netprio_cgroup.c:write_priomap
  - net/core/netprio_cgroup.c:read_priomap
```
**Symbols:**

```
ffffffff81121520-ffffffff81121555: of_css (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct cgroup_subsys_state *of_css(struct kernfs_open_file *of);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8112d6b8)
Location: kernel/cgroup/cgroup.c:558
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_seqfile_show
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_stat_show
  - kernel/cgroup/cgroup.c:cgroup_events_show
  - kernel/cgroup/cgroup.c:cgroup_max_depth_show
  - kernel/cgroup/cgroup.c:cgroup_max_descendants_show
  - kernel/cgroup/cgroup.c:cgroup_type_show
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_show
  - kernel/cgroup/cgroup.c:cgroup_controllers_show
Direct callers:
  - kernel/sched/core.c:cpu_max_write
  - kernel/sched/core.c:cpu_max_show
  - kernel/sched/core.c:cpu_cfs_stat_show
  - kernel/sched/cpuacct.c:cpuacct_stats_show
  - kernel/sched/cpuacct.c:cpuacct_all_seq_show
  - kernel/sched/cpuacct.c:__cpuacct_percpu_seq_show
  - kernel/cgroup/stat.c:cgroup_stat_show_cputime
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_show
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_stop
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
  - kernel/cgroup/freezer.c:freezer_write
  - kernel/cgroup/freezer.c:freezer_read
  - kernel/cgroup/pids.c:pids_events_show
  - kernel/cgroup/pids.c:pids_max_write
  - kernel/cgroup/rdma.c:rdmacg_resource_read
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/cgroup/cpuset.c:cpuset_common_seq_show
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - mm/slab_common.c:memcg_slab_show
  - mm/slab_common.c:memcg_slab_next
  - mm/slab_common.c:memcg_slab_start
  - mm/memcontrol.c:swap_max_write
  - mm/memcontrol.c:swap_max_show
  - mm/memcontrol.c:memory_stat_show
  - mm/memcontrol.c:memory_events_show
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_max_show
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:memory_high_show
  - mm/memcontrol.c:memory_low_write
  - mm/memcontrol.c:memory_low_show
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:mem_cgroup_oom_control_read
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:mem_cgroup_reset
  - mm/memcontrol.c:mem_cgroup_write
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_reset
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_write
  - security/device_cgroup.c:devcgroup_access_write
  - security/device_cgroup.c:devcgroup_seq_show
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-cgroup.c:blkg_print_stat_ios_recursive
  - block/blk-cgroup.c:blkg_print_stat_bytes_recursive
  - block/blk-cgroup.c:blkg_print_stat_ios
  - block/blk-cgroup.c:blkg_print_stat_bytes
  - block/blk-throttle.c:tg_set_limit
  - block/blk-throttle.c:tg_print_limit
  - block/blk-throttle.c:tg_print_conf_uint
  - block/blk-throttle.c:tg_print_conf_u64
  - block/cfq-iosched.c:cfq_set_weight_on_dfl
  - block/cfq-iosched.c:cfq_print_weight_on_dfl
  - block/cfq-iosched.c:cfqg_print_stat_sectors_recursive
  - block/cfq-iosched.c:cfqg_print_stat_sectors
  - block/cfq-iosched.c:cfqg_print_rwstat_recursive
  - block/cfq-iosched.c:cfqg_print_stat_recursive
  - block/cfq-iosched.c:cfqg_print_rwstat
  - block/cfq-iosched.c:cfqg_print_stat
  - block/cfq-iosched.c:cfq_print_leaf_weight
  - block/cfq-iosched.c:cfq_print_weight
  - block/cfq-iosched.c:cfqg_print_leaf_weight_device
  - block/cfq-iosched.c:cfqg_print_weight_device
  - net/core/netprio_cgroup.c:write_priomap
  - net/core/netprio_cgroup.c:read_priomap
```
**Symbols:**

```
ffffffff8112cb80-ffffffff8112cbb5: of_css (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct cgroup_subsys_state *of_css(struct kernfs_open_file *of);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8113b8a8)
Location: kernel/cgroup/cgroup.c:561
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_seqfile_show
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_stat_show
  - kernel/cgroup/cgroup.c:cgroup_events_show
  - kernel/cgroup/cgroup.c:cgroup_max_depth_show
  - kernel/cgroup/cgroup.c:cgroup_max_descendants_show
  - kernel/cgroup/cgroup.c:cgroup_type_show
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_show
  - kernel/cgroup/cgroup.c:cgroup_controllers_show
Direct callers:
  - kernel/sched/core.c:cpu_max_write
  - kernel/sched/core.c:cpu_max_show
  - kernel/sched/core.c:cpu_cfs_stat_show
  - kernel/sched/cpuacct.c:cpuacct_stats_show
  - kernel/sched/cpuacct.c:cpuacct_all_seq_show
  - kernel/sched/cpuacct.c:__cpuacct_percpu_seq_show
  - kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_show
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_stop
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
  - kernel/cgroup/freezer.c:freezer_write
  - kernel/cgroup/freezer.c:freezer_read
  - kernel/cgroup/pids.c:pids_events_show
  - kernel/cgroup/pids.c:pids_max_write
  - kernel/cgroup/rdma.c:rdmacg_resource_read
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/cgroup/cpuset.c:cpuset_common_seq_show
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - mm/slab_common.c:memcg_slab_show
  - mm/slab_common.c:memcg_slab_next
  - mm/slab_common.c:memcg_slab_start
  - mm/memcontrol.c:swap_events_show
  - mm/memcontrol.c:swap_max_write
  - mm/memcontrol.c:swap_max_show
  - mm/memcontrol.c:memory_stat_show
  - mm/memcontrol.c:memory_events_show
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_max_show
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:memory_high_show
  - mm/memcontrol.c:memory_low_write
  - mm/memcontrol.c:memory_low_show
  - mm/memcontrol.c:memory_min_write
  - mm/memcontrol.c:memory_min_show
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:mem_cgroup_oom_control_read
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:mem_cgroup_reset
  - mm/memcontrol.c:mem_cgroup_write
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_reset
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_write
  - security/device_cgroup.c:devcgroup_access_write
  - security/device_cgroup.c:devcgroup_seq_show
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-cgroup.c:blkg_print_stat_ios_recursive
  - block/blk-cgroup.c:blkg_print_stat_bytes_recursive
  - block/blk-cgroup.c:blkg_print_stat_ios
  - block/blk-cgroup.c:blkg_print_stat_bytes
  - block/blk-throttle.c:tg_set_limit
  - block/blk-throttle.c:tg_print_limit
  - block/blk-throttle.c:tg_print_conf_uint
  - block/blk-throttle.c:tg_print_conf_u64
  - block/cfq-iosched.c:cfq_set_weight_on_dfl
  - block/cfq-iosched.c:cfq_print_weight_on_dfl
  - block/cfq-iosched.c:cfqg_print_stat_sectors_recursive
  - block/cfq-iosched.c:cfqg_print_stat_sectors
  - block/cfq-iosched.c:cfqg_print_rwstat_recursive
  - block/cfq-iosched.c:cfqg_print_stat_recursive
  - block/cfq-iosched.c:cfqg_print_rwstat
  - block/cfq-iosched.c:cfqg_print_stat
  - block/cfq-iosched.c:cfq_print_leaf_weight
  - block/cfq-iosched.c:cfq_print_weight
  - block/cfq-iosched.c:cfqg_print_leaf_weight_device
  - block/cfq-iosched.c:cfqg_print_weight_device
  - net/core/netprio_cgroup.c:write_priomap
  - net/core/netprio_cgroup.c:read_priomap
```
**Symbols:**

```
ffffffff8113b210-ffffffff8113b245: of_css (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct cgroup_subsys_state *of_css(struct kernfs_open_file *of);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811470a8)
Location: kernel/cgroup/cgroup.c:595
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_seqfile_show
  - kernel/cgroup/cgroup.c:cgroup_cpu_pressure_show
  - kernel/cgroup/cgroup.c:cgroup_memory_pressure_show
  - kernel/cgroup/cgroup.c:cgroup_io_pressure_show
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_stat_show
  - kernel/cgroup/cgroup.c:cgroup_events_show
  - kernel/cgroup/cgroup.c:cgroup_max_depth_show
  - kernel/cgroup/cgroup.c:cgroup_max_descendants_show
  - kernel/cgroup/cgroup.c:cgroup_type_show
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_show
  - kernel/cgroup/cgroup.c:cgroup_controllers_show
Direct callers:
  - kernel/sched/core.c:cpu_max_write
  - kernel/sched/core.c:cpu_max_show
  - kernel/sched/core.c:cpu_cfs_stat_show
  - kernel/sched/cpuacct.c:cpuacct_stats_show
  - kernel/sched/cpuacct.c:cpuacct_all_seq_show
  - kernel/sched/cpuacct.c:__cpuacct_percpu_seq_show
  - kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_show
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_stop
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
  - kernel/cgroup/freezer.c:freezer_write
  - kernel/cgroup/freezer.c:freezer_read
  - kernel/cgroup/pids.c:pids_events_show
  - kernel/cgroup/pids.c:pids_max_write
  - kernel/cgroup/rdma.c:rdmacg_resource_read
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:sched_partition_show
  - kernel/cgroup/cpuset.c:cpuset_common_seq_show
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - mm/slab_common.c:memcg_slab_show
  - mm/slab_common.c:memcg_slab_next
  - mm/slab_common.c:memcg_slab_start
  - mm/memcontrol.c:swap_events_show
  - mm/memcontrol.c:swap_max_write
  - mm/memcontrol.c:swap_max_show
  - mm/memcontrol.c:memory_oom_group_write
  - mm/memcontrol.c:memory_oom_group_show
  - mm/memcontrol.c:memory_stat_show
  - mm/memcontrol.c:memory_events_show
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_max_show
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:memory_high_show
  - mm/memcontrol.c:memory_low_write
  - mm/memcontrol.c:memory_low_show
  - mm/memcontrol.c:memory_min_write
  - mm/memcontrol.c:memory_min_show
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:mem_cgroup_oom_control_read
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:mem_cgroup_reset
  - mm/memcontrol.c:mem_cgroup_write
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_reset
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_write
  - security/device_cgroup.c:devcgroup_access_write
  - security/device_cgroup.c:devcgroup_seq_show
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-cgroup.c:blkg_print_stat_ios_recursive
  - block/blk-cgroup.c:blkg_print_stat_bytes_recursive
  - block/blk-cgroup.c:blkg_print_stat_ios
  - block/blk-cgroup.c:blkg_print_stat_bytes
  - block/blk-throttle.c:tg_set_limit
  - block/blk-throttle.c:tg_print_limit
  - block/blk-throttle.c:tg_print_conf_uint
  - block/blk-throttle.c:tg_print_conf_u64
  - net/core/netprio_cgroup.c:write_priomap
  - net/core/netprio_cgroup.c:read_priomap
```
**Symbols:**

```
ffffffff81146a80-ffffffff81146ab5: of_css (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct cgroup_subsys_state *of_css(struct kernfs_open_file *of);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8115236c)
Location: kernel/cgroup/cgroup.c:630
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_seqfile_show
  - kernel/cgroup/cgroup.c:cgroup_freeze_show
  - kernel/cgroup/cgroup.c:cgroup_cpu_pressure_show
  - kernel/cgroup/cgroup.c:cgroup_memory_pressure_show
  - kernel/cgroup/cgroup.c:cgroup_io_pressure_show
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_stat_show
  - kernel/cgroup/cgroup.c:cgroup_events_show
  - kernel/cgroup/cgroup.c:cgroup_max_depth_show
  - kernel/cgroup/cgroup.c:cgroup_max_descendants_show
  - kernel/cgroup/cgroup.c:cgroup_type_show
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_show
  - kernel/cgroup/cgroup.c:cgroup_controllers_show
Direct callers:
  - kernel/sched/core.c:cpu_max_write
  - kernel/sched/core.c:cpu_max_show
  - kernel/sched/core.c:cpu_cfs_stat_show
  - kernel/sched/cpuacct.c:cpuacct_stats_show
  - kernel/sched/cpuacct.c:cpuacct_all_seq_show
  - kernel/sched/cpuacct.c:__cpuacct_percpu_seq_show
  - kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_show
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_stop
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_read
  - kernel/cgroup/pids.c:pids_events_show
  - kernel/cgroup/pids.c:pids_max_write
  - kernel/cgroup/rdma.c:rdmacg_resource_read
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:sched_partition_show
  - kernel/cgroup/cpuset.c:cpuset_common_seq_show
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - mm/slab_common.c:memcg_slab_show
  - mm/slab_common.c:memcg_slab_next
  - mm/slab_common.c:memcg_slab_start
  - mm/memcontrol.c:swap_events_show
  - mm/memcontrol.c:swap_max_write
  - mm/memcontrol.c:swap_max_show
  - mm/memcontrol.c:memory_oom_group_write
  - mm/memcontrol.c:memory_oom_group_show
  - mm/memcontrol.c:memory_stat_show
  - mm/memcontrol.c:memory_events_local_show
  - mm/memcontrol.c:memory_events_show
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_max_show
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:memory_high_show
  - mm/memcontrol.c:memory_low_write
  - mm/memcontrol.c:memory_low_show
  - mm/memcontrol.c:memory_min_write
  - mm/memcontrol.c:memory_min_show
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:mem_cgroup_oom_control_read
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:mem_cgroup_reset
  - mm/memcontrol.c:mem_cgroup_write
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_reset
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_write
  - security/device_cgroup.c:devcgroup_access_write
  - security/device_cgroup.c:devcgroup_seq_show
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-cgroup.c:blkg_print_stat_ios_recursive
  - block/blk-cgroup.c:blkg_print_stat_bytes_recursive
  - block/blk-cgroup.c:blkg_print_stat_ios
  - block/blk-cgroup.c:blkg_print_stat_bytes
  - block/blk-throttle.c:tg_set_limit
  - block/blk-throttle.c:tg_print_limit
  - block/blk-throttle.c:tg_print_conf_uint
  - block/blk-throttle.c:tg_print_conf_u64
  - net/core/netprio_cgroup.c:write_priomap
  - net/core/netprio_cgroup.c:read_priomap
```
**Symbols:**

```
ffffffff81151bd0-ffffffff81151c05: of_css (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct cgroup_subsys_state *of_css(struct kernfs_open_file *of);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8115dfbc)
Location: kernel/cgroup/cgroup.c:630
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_seqfile_show
  - kernel/cgroup/cgroup.c:cgroup_freeze_show
  - kernel/cgroup/cgroup.c:cgroup_cpu_pressure_show
  - kernel/cgroup/cgroup.c:cgroup_memory_pressure_show
  - kernel/cgroup/cgroup.c:cgroup_io_pressure_show
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_stat_show
  - kernel/cgroup/cgroup.c:cgroup_events_show
  - kernel/cgroup/cgroup.c:cgroup_max_depth_show
  - kernel/cgroup/cgroup.c:cgroup_max_descendants_show
  - kernel/cgroup/cgroup.c:cgroup_type_show
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_show
  - kernel/cgroup/cgroup.c:cgroup_controllers_show
Direct callers:
  - kernel/sched/core.c:cpu_max_write
  - kernel/sched/core.c:cpu_max_show
  - kernel/sched/core.c:cpu_cfs_stat_show
  - kernel/sched/core.c:cpu_uclamp_max_show
  - kernel/sched/core.c:cpu_uclamp_min_show
  - kernel/sched/cpuacct.c:cpuacct_stats_show
  - kernel/sched/cpuacct.c:cpuacct_all_seq_show
  - kernel/sched/cpuacct.c:__cpuacct_percpu_seq_show
  - kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_show
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_stop
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_read
  - kernel/cgroup/pids.c:pids_events_show
  - kernel/cgroup/pids.c:pids_max_write
  - kernel/cgroup/rdma.c:rdmacg_resource_read
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:sched_partition_show
  - kernel/cgroup/cpuset.c:cpuset_common_seq_show
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - mm/slab_common.c:memcg_slab_show
  - mm/slab_common.c:memcg_slab_next
  - mm/slab_common.c:memcg_slab_start
  - mm/memcontrol.c:swap_events_show
  - mm/memcontrol.c:swap_max_write
  - mm/memcontrol.c:swap_max_show
  - mm/memcontrol.c:memory_oom_group_write
  - mm/memcontrol.c:memory_oom_group_show
  - mm/memcontrol.c:memory_stat_show
  - mm/memcontrol.c:memory_events_local_show
  - mm/memcontrol.c:memory_events_show
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_max_show
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:memory_high_show
  - mm/memcontrol.c:memory_low_write
  - mm/memcontrol.c:memory_low_show
  - mm/memcontrol.c:memory_min_write
  - mm/memcontrol.c:memory_min_show
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:mem_cgroup_oom_control_read
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:mem_cgroup_reset
  - mm/memcontrol.c:mem_cgroup_write
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_reset
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_write
  - security/device_cgroup.c:devcgroup_access_write
  - security/device_cgroup.c:devcgroup_seq_show
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-cgroup.c:blkg_print_stat_ios_recursive
  - block/blk-cgroup.c:blkg_print_stat_bytes_recursive
  - block/blk-cgroup.c:blkg_print_stat_ios
  - block/blk-cgroup.c:blkg_print_stat_bytes
  - block/blk-throttle.c:tg_set_limit
  - block/blk-throttle.c:tg_print_limit
  - block/blk-throttle.c:tg_print_conf_uint
  - block/blk-throttle.c:tg_print_conf_u64
  - block/blk-iocost.c:ioc_cost_model_show
  - block/blk-iocost.c:ioc_qos_show
  - block/blk-iocost.c:ioc_weight_write
  - block/blk-iocost.c:ioc_weight_show
  - net/core/netprio_cgroup.c:write_priomap
  - net/core/netprio_cgroup.c:read_priomap
```
**Symbols:**

```
ffffffff8115d820-ffffffff8115d855: of_css (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct cgroup_subsys_state *of_css(struct kernfs_open_file *of);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81177239)
Location: kernel/cgroup/cgroup.c:623
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:__cgroup_procs_start
  - kernel/cgroup/cgroup.c:cgroup_seqfile_show
  - kernel/cgroup/cgroup.c:cgroup_freeze_show
  - kernel/cgroup/cgroup.c:cgroup_cpu_pressure_show
  - kernel/cgroup/cgroup.c:cgroup_memory_pressure_show
  - kernel/cgroup/cgroup.c:cgroup_io_pressure_show
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_stat_show
  - kernel/cgroup/cgroup.c:cgroup_events_show
  - kernel/cgroup/cgroup.c:cgroup_max_depth_show
  - kernel/cgroup/cgroup.c:cgroup_max_descendants_show
  - kernel/cgroup/cgroup.c:cgroup_type_show
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_show
  - kernel/cgroup/cgroup.c:cgroup_controllers_show
Direct callers:
  - kernel/sched/core.c:cpu_max_write
  - kernel/sched/core.c:cpu_max_show
  - kernel/sched/core.c:cpu_cfs_stat_show
  - kernel/sched/core.c:cpu_uclamp_max_show
  - kernel/sched/core.c:cpu_uclamp_min_show
  - kernel/sched/cpuacct.c:cpuacct_stats_show
  - kernel/sched/cpuacct.c:cpuacct_all_seq_show
  - kernel/sched/cpuacct.c:__cpuacct_percpu_seq_show
  - kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_show
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_stop
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_read
  - kernel/cgroup/pids.c:pids_events_show
  - kernel/cgroup/pids.c:pids_max_write
  - kernel/cgroup/rdma.c:rdmacg_resource_read
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:sched_partition_show
  - kernel/cgroup/cpuset.c:cpuset_common_seq_show
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - mm/slab_common.c:memcg_slab_show
  - mm/slab_common.c:memcg_slab_next
  - mm/slab_common.c:memcg_slab_start
  - mm/memcontrol.c:swap_events_show
  - mm/memcontrol.c:swap_max_write
  - mm/memcontrol.c:swap_max_show
  - mm/memcontrol.c:swap_high_write
  - mm/memcontrol.c:swap_high_show
  - mm/memcontrol.c:memory_oom_group_write
  - mm/memcontrol.c:memory_oom_group_show
  - mm/memcontrol.c:memory_stat_show
  - mm/memcontrol.c:memory_events_local_show
  - mm/memcontrol.c:memory_events_show
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_max_show
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:memory_high_show
  - mm/memcontrol.c:memory_low_write
  - mm/memcontrol.c:memory_low_show
  - mm/memcontrol.c:memory_min_write
  - mm/memcontrol.c:memory_min_show
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:mem_cgroup_oom_control_read
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:mem_cgroup_reset
  - mm/memcontrol.c:mem_cgroup_write
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/hugetlb_cgroup.c:hugetlb_events_local_show
  - mm/hugetlb_cgroup.c:hugetlb_events_show
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_reset
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_u64_max
  - security/device_cgroup.c:devcgroup_access_write
  - security/device_cgroup.c:devcgroup_seq_show
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-throttle.c:tg_set_limit
  - block/blk-throttle.c:tg_print_limit
  - block/blk-throttle.c:tg_print_rwstat_recursive
  - block/blk-throttle.c:tg_print_rwstat
  - block/blk-throttle.c:tg_print_conf_uint
  - block/blk-throttle.c:tg_print_conf_u64
  - block/blk-iocost.c:ioc_cost_model_show
  - block/blk-iocost.c:ioc_qos_show
  - block/blk-iocost.c:ioc_weight_write
  - block/blk-iocost.c:ioc_weight_show
  - net/core/netprio_cgroup.c:write_priomap
  - net/core/netprio_cgroup.c:read_priomap
```
**Symbols:**

```
ffffffff8116e260-ffffffff8116e292: of_css (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct cgroup_subsys_state *of_css(struct kernfs_open_file *of);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81173f1c)
Location: kernel/cgroup/cgroup.c:620
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:__cgroup_procs_start
  - kernel/cgroup/cgroup.c:cgroup_seqfile_show
  - kernel/cgroup/cgroup.c:cgroup_freeze_show
  - kernel/cgroup/cgroup.c:cgroup_cpu_pressure_show
  - kernel/cgroup/cgroup.c:cgroup_memory_pressure_show
  - kernel/cgroup/cgroup.c:cgroup_io_pressure_show
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_stat_show
  - kernel/cgroup/cgroup.c:cgroup_events_show
  - kernel/cgroup/cgroup.c:cgroup_max_depth_show
  - kernel/cgroup/cgroup.c:cgroup_max_descendants_show
  - kernel/cgroup/cgroup.c:cgroup_type_show
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_show
  - kernel/cgroup/cgroup.c:cgroup_controllers_show
Direct callers:
  - kernel/sched/core.c:cpu_max_write
  - kernel/sched/core.c:cpu_max_show
  - kernel/sched/core.c:cpu_cfs_stat_show
  - kernel/sched/core.c:cpu_uclamp_max_show
  - kernel/sched/core.c:cpu_uclamp_min_show
  - kernel/sched/cpuacct.c:cpuacct_stats_show
  - kernel/sched/cpuacct.c:cpuacct_all_seq_show
  - kernel/sched/cpuacct.c:__cpuacct_percpu_seq_show
  - kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_show
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_stop
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_read
  - kernel/cgroup/pids.c:pids_events_show
  - kernel/cgroup/pids.c:pids_max_write
  - kernel/cgroup/rdma.c:rdmacg_resource_read
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:sched_partition_show
  - kernel/cgroup/cpuset.c:cpuset_common_seq_show
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - mm/memcontrol.c:swap_events_show
  - mm/memcontrol.c:swap_max_write
  - mm/memcontrol.c:swap_max_show
  - mm/memcontrol.c:swap_high_write
  - mm/memcontrol.c:swap_high_show
  - mm/memcontrol.c:memory_oom_group_write
  - mm/memcontrol.c:memory_oom_group_show
  - mm/memcontrol.c:memory_numa_stat_show
  - mm/memcontrol.c:memory_stat_show
  - mm/memcontrol.c:memory_events_local_show
  - mm/memcontrol.c:memory_events_show
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_max_show
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:memory_high_show
  - mm/memcontrol.c:memory_low_write
  - mm/memcontrol.c:memory_low_show
  - mm/memcontrol.c:memory_min_write
  - mm/memcontrol.c:memory_min_show
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:mem_cgroup_oom_control_read
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:mem_cgroup_reset
  - mm/memcontrol.c:mem_cgroup_write
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/hugetlb_cgroup.c:hugetlb_events_local_show
  - mm/hugetlb_cgroup.c:hugetlb_events_show
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_reset
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_u64_max
  - security/device_cgroup.c:devcgroup_access_write
  - security/device_cgroup.c:devcgroup_seq_show
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-throttle.c:tg_set_limit
  - block/blk-throttle.c:tg_print_limit
  - block/blk-throttle.c:tg_print_rwstat_recursive
  - block/blk-throttle.c:tg_print_rwstat
  - block/blk-throttle.c:tg_print_conf_uint
  - block/blk-throttle.c:tg_print_conf_u64
  - block/blk-iocost.c:ioc_cost_model_show
  - block/blk-iocost.c:ioc_qos_show
  - block/blk-iocost.c:ioc_weight_write
  - block/blk-iocost.c:ioc_weight_show
  - net/core/netprio_cgroup.c:write_priomap
  - net/core/netprio_cgroup.c:read_priomap
```
**Symbols:**

```
ffffffff8116ac90-ffffffff8116acc3: of_css (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct cgroup_subsys_state *of_css(struct kernfs_open_file *of);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81174aef)
Location: kernel/cgroup/cgroup.c:620
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:__cgroup_procs_start
  - kernel/cgroup/cgroup.c:cgroup_seqfile_show
  - kernel/cgroup/cgroup.c:cgroup_freeze_show
  - kernel/cgroup/cgroup.c:cgroup_cpu_pressure_show
  - kernel/cgroup/cgroup.c:cgroup_memory_pressure_show
  - kernel/cgroup/cgroup.c:cgroup_io_pressure_show
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_stat_show
  - kernel/cgroup/cgroup.c:cgroup_events_show
  - kernel/cgroup/cgroup.c:cgroup_max_depth_show
  - kernel/cgroup/cgroup.c:cgroup_max_descendants_show
  - kernel/cgroup/cgroup.c:cgroup_type_show
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_show
  - kernel/cgroup/cgroup.c:cgroup_controllers_show
Direct callers:
  - kernel/sched/core.c:cpu_max_write
  - kernel/sched/core.c:cpu_max_show
  - kernel/sched/core.c:cpu_cfs_stat_show
  - kernel/sched/core.c:cpu_uclamp_max_show
  - kernel/sched/core.c:cpu_uclamp_min_show
  - kernel/sched/cpuacct.c:cpuacct_stats_show
  - kernel/sched/cpuacct.c:cpuacct_all_seq_show
  - kernel/sched/cpuacct.c:__cpuacct_percpu_seq_show
  - kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_show
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_stop
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_read
  - kernel/cgroup/pids.c:pids_events_show
  - kernel/cgroup/pids.c:pids_max_write
  - kernel/cgroup/rdma.c:rdmacg_resource_read
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:sched_partition_show
  - kernel/cgroup/cpuset.c:cpuset_common_seq_show
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/misc.c:misc_cg_current_show
  - kernel/cgroup/misc.c:misc_cg_max_write
  - kernel/cgroup/misc.c:misc_cg_max_show
  - mm/memcontrol.c:swap_events_show
  - mm/memcontrol.c:swap_max_write
  - mm/memcontrol.c:swap_max_show
  - mm/memcontrol.c:swap_high_write
  - mm/memcontrol.c:swap_high_show
  - mm/memcontrol.c:memory_oom_group_write
  - mm/memcontrol.c:memory_oom_group_show
  - mm/memcontrol.c:memory_numa_stat_show
  - mm/memcontrol.c:memory_stat_show
  - mm/memcontrol.c:memory_events_local_show
  - mm/memcontrol.c:memory_events_show
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_max_show
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:memory_high_show
  - mm/memcontrol.c:memory_low_write
  - mm/memcontrol.c:memory_low_show
  - mm/memcontrol.c:memory_min_write
  - mm/memcontrol.c:memory_min_show
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:mem_cgroup_oom_control_read
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:mem_cgroup_reset
  - mm/memcontrol.c:mem_cgroup_write
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/hugetlb_cgroup.c:hugetlb_events_local_show
  - mm/hugetlb_cgroup.c:hugetlb_events_show
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_reset
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_u64_max
  - security/device_cgroup.c:devcgroup_access_write
  - security/device_cgroup.c:devcgroup_seq_show
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-throttle.c:tg_set_limit
  - block/blk-throttle.c:tg_print_limit
  - block/blk-throttle.c:tg_print_rwstat_recursive
  - block/blk-throttle.c:tg_print_rwstat
  - block/blk-throttle.c:tg_print_conf_uint
  - block/blk-throttle.c:tg_print_conf_u64
  - block/blk-iocost.c:ioc_cost_model_show
  - block/blk-iocost.c:ioc_qos_show
  - block/blk-iocost.c:ioc_weight_write
  - block/blk-iocost.c:ioc_weight_show
  - net/core/netprio_cgroup.c:write_priomap
  - net/core/netprio_cgroup.c:read_priomap
```
**Symbols:**

```
ffffffff8116b8d0-ffffffff8116b903: of_css (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct cgroup_subsys_state *of_css(struct kernfs_open_file *of);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8119bd83)
Location: kernel/cgroup/cgroup.c:651
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:__cgroup_procs_start
  - kernel/cgroup/cgroup.c:cgroup_seqfile_show
  - kernel/cgroup/cgroup.c:cgroup_freeze_show
  - kernel/cgroup/cgroup.c:cgroup_cpu_pressure_show
  - kernel/cgroup/cgroup.c:cgroup_memory_pressure_show
  - kernel/cgroup/cgroup.c:cgroup_io_pressure_show
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_stat_show
  - kernel/cgroup/cgroup.c:cgroup_events_show
  - kernel/cgroup/cgroup.c:cgroup_max_depth_show
  - kernel/cgroup/cgroup.c:cgroup_max_descendants_show
  - kernel/cgroup/cgroup.c:cgroup_type_show
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_show
  - kernel/cgroup/cgroup.c:cgroup_controllers_show
Direct callers:
  - kernel/sched/core.c:cpu_max_write
  - kernel/sched/core.c:cpu_max_show
  - kernel/sched/core.c:cpu_cfs_stat_show
  - kernel/sched/core.c:cpu_uclamp_max_show
  - kernel/sched/core.c:cpu_uclamp_min_show
  - kernel/sched/cpuacct.c:cpuacct_stats_show
  - kernel/sched/cpuacct.c:cpuacct_all_seq_show
  - kernel/sched/cpuacct.c:__cpuacct_percpu_seq_show
  - kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_show
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_stop
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_read
  - kernel/cgroup/pids.c:pids_events_show
  - kernel/cgroup/pids.c:pids_max_write
  - kernel/cgroup/rdma.c:rdmacg_resource_read
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:sched_partition_show
  - kernel/cgroup/cpuset.c:cpuset_common_seq_show
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/misc.c:misc_cg_current_show
  - kernel/cgroup/misc.c:misc_cg_max_write
  - kernel/cgroup/misc.c:misc_cg_max_show
  - mm/memcontrol.c:swap_events_show
  - mm/memcontrol.c:swap_max_write
  - mm/memcontrol.c:swap_max_show
  - mm/memcontrol.c:swap_high_write
  - mm/memcontrol.c:swap_high_show
  - mm/memcontrol.c:memory_oom_group_write
  - mm/memcontrol.c:memory_oom_group_show
  - mm/memcontrol.c:memory_numa_stat_show
  - mm/memcontrol.c:memory_stat_show
  - mm/memcontrol.c:memory_events_local_show
  - mm/memcontrol.c:memory_events_show
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_max_show
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:memory_high_show
  - mm/memcontrol.c:memory_low_write
  - mm/memcontrol.c:memory_low_show
  - mm/memcontrol.c:memory_min_write
  - mm/memcontrol.c:memory_min_show
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:mem_cgroup_oom_control_read
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:mem_cgroup_reset
  - mm/memcontrol.c:mem_cgroup_write
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/hugetlb_cgroup.c:hugetlb_events_local_show
  - mm/hugetlb_cgroup.c:hugetlb_events_show
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_reset
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_u64_max
  - security/device_cgroup.c:devcgroup_access_write
  - security/device_cgroup.c:devcgroup_seq_show
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-throttle.c:tg_set_limit
  - block/blk-throttle.c:tg_print_limit
  - block/blk-throttle.c:tg_print_rwstat_recursive
  - block/blk-throttle.c:tg_print_rwstat
  - block/blk-throttle.c:tg_print_conf_uint
  - block/blk-throttle.c:tg_print_conf_u64
  - block/blk-ioprio.c:ioprio_set_prio_policy
  - block/blk-ioprio.c:ioprio_show_prio_policy
  - block/blk-iocost.c:ioc_cost_model_show
  - block/blk-iocost.c:ioc_qos_show
  - block/blk-iocost.c:ioc_weight_write
  - block/blk-iocost.c:ioc_weight_show
  - net/core/netprio_cgroup.c:write_priomap
  - net/core/netprio_cgroup.c:read_priomap
```
**Symbols:**

```
ffffffff811914d0-ffffffff81191523: of_css (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct cgroup_subsys_state *of_css(struct kernfs_open_file *of);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811cc013)
Location: kernel/cgroup/cgroup.c:652
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:__cgroup_procs_start
  - kernel/cgroup/cgroup.c:cgroup_seqfile_show
  - kernel/cgroup/cgroup.c:cgroup_freeze_show
  - kernel/cgroup/cgroup.c:cgroup_cpu_pressure_show
  - kernel/cgroup/cgroup.c:cgroup_memory_pressure_show
  - kernel/cgroup/cgroup.c:cgroup_io_pressure_show
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_stat_show
  - kernel/cgroup/cgroup.c:cgroup_events_show
  - kernel/cgroup/cgroup.c:cgroup_max_depth_show
  - kernel/cgroup/cgroup.c:cgroup_max_descendants_show
  - kernel/cgroup/cgroup.c:cgroup_type_show
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_show
  - kernel/cgroup/cgroup.c:cgroup_controllers_show
Direct callers:
  - kernel/sched/core.c:cpu_max_write
  - kernel/sched/core.c:cpu_max_show
  - kernel/sched/core.c:cpu_cfs_stat_show
  - kernel/sched/core.c:cpu_uclamp_max_show
  - kernel/sched/core.c:cpu_uclamp_min_show
  - kernel/sched/build_utility.c:cpuacct_stats_show
  - kernel/sched/build_utility.c:cpuacct_stats_show
  - kernel/sched/build_utility.c:cpuacct_all_seq_show
  - kernel/sched/build_utility.c:__cpuacct_percpu_seq_show
  - kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_show
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_stop
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_read
  - kernel/cgroup/pids.c:pids_events_show
  - kernel/cgroup/pids.c:pids_max_write
  - kernel/cgroup/rdma.c:rdmacg_resource_read
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:sched_partition_show
  - kernel/cgroup/cpuset.c:cpuset_common_seq_show
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/misc.c:misc_events_show
  - kernel/cgroup/misc.c:misc_cg_current_show
  - kernel/cgroup/misc.c:misc_cg_max_write
  - kernel/cgroup/misc.c:misc_cg_max_show
  - mm/memcontrol.c:zswap_max_write
  - mm/memcontrol.c:zswap_max_show
  - mm/memcontrol.c:swap_events_show
  - mm/memcontrol.c:swap_max_write
  - mm/memcontrol.c:swap_max_show
  - mm/memcontrol.c:swap_high_write
  - mm/memcontrol.c:swap_high_show
  - mm/memcontrol.c:memory_reclaim
  - mm/memcontrol.c:memory_oom_group_write
  - mm/memcontrol.c:memory_oom_group_show
  - mm/memcontrol.c:memory_numa_stat_show
  - mm/memcontrol.c:memory_stat_show
  - mm/memcontrol.c:memory_events_local_show
  - mm/memcontrol.c:memory_events_show
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_max_show
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:memory_high_show
  - mm/memcontrol.c:memory_low_write
  - mm/memcontrol.c:memory_low_show
  - mm/memcontrol.c:memory_min_write
  - mm/memcontrol.c:memory_min_show
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:mem_cgroup_oom_control_read
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:mem_cgroup_reset
  - mm/memcontrol.c:mem_cgroup_write
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/hugetlb_cgroup.c:hugetlb_events_local_show
  - mm/hugetlb_cgroup.c:hugetlb_events_show
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_reset
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_u64_max
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_numa_stat
  - security/device_cgroup.c:devcgroup_access_write
  - security/device_cgroup.c:devcgroup_seq_show
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-throttle.c:tg_set_limit
  - block/blk-throttle.c:tg_print_limit
  - block/blk-throttle.c:tg_print_rwstat_recursive
  - block/blk-throttle.c:tg_print_rwstat
  - block/blk-throttle.c:tg_print_conf_uint
  - block/blk-throttle.c:tg_print_conf_u64
  - block/blk-ioprio.c:ioprio_set_prio_policy
  - block/blk-ioprio.c:ioprio_show_prio_policy
  - block/blk-iocost.c:ioc_cost_model_show
  - block/blk-iocost.c:ioc_qos_show
  - block/blk-iocost.c:ioc_weight_write
  - block/blk-iocost.c:ioc_weight_show
  - net/core/netprio_cgroup.c:write_priomap
  - net/core/netprio_cgroup.c:read_priomap
```
**Symbols:**

```
ffffffff811c0be0-ffffffff811c0c3d: of_css (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct cgroup_subsys_state *of_css(struct kernfs_open_file *of);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8120f513)
Location: kernel/cgroup/cgroup.c:657
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:__cgroup_procs_start
  - kernel/cgroup/cgroup.c:cgroup_seqfile_show
  - kernel/cgroup/cgroup.c:cgroup_freeze_show
  - kernel/cgroup/cgroup.c:cgroup_pressure_show
  - kernel/cgroup/cgroup.c:cgroup_cpu_pressure_show
  - kernel/cgroup/cgroup.c:cgroup_memory_pressure_show
  - kernel/cgroup/cgroup.c:cgroup_io_pressure_show
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_stat_show
  - kernel/cgroup/cgroup.c:cgroup_events_show
  - kernel/cgroup/cgroup.c:cgroup_max_depth_show
  - kernel/cgroup/cgroup.c:cgroup_max_descendants_show
  - kernel/cgroup/cgroup.c:cgroup_type_show
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_show
  - kernel/cgroup/cgroup.c:cgroup_controllers_show
Direct callers:
  - kernel/sched/core.c:cpu_max_write
  - kernel/sched/core.c:cpu_max_show
  - kernel/sched/core.c:cpu_cfs_stat_show
  - kernel/sched/core.c:cpu_uclamp_max_show
  - kernel/sched/core.c:cpu_uclamp_min_show
  - kernel/sched/build_utility.c:cpuacct_stats_show
  - kernel/sched/build_utility.c:cpuacct_stats_show
  - kernel/sched/build_utility.c:cpuacct_all_seq_show
  - kernel/sched/build_utility.c:__cpuacct_percpu_seq_show
  - kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_show
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_stop
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_read
  - kernel/cgroup/pids.c:pids_events_show
  - kernel/cgroup/pids.c:pids_max_write
  - kernel/cgroup/rdma.c:rdmacg_resource_read
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:sched_partition_show
  - kernel/cgroup/cpuset.c:cpuset_common_seq_show
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/misc.c:misc_events_show
  - kernel/cgroup/misc.c:misc_cg_current_show
  - kernel/cgroup/misc.c:misc_cg_max_write
  - kernel/cgroup/misc.c:misc_cg_max_show
  - mm/memcontrol.c:zswap_max_write
  - mm/memcontrol.c:zswap_max_show
  - mm/memcontrol.c:swap_events_show
  - mm/memcontrol.c:swap_max_write
  - mm/memcontrol.c:swap_max_show
  - mm/memcontrol.c:swap_high_write
  - mm/memcontrol.c:swap_high_show
  - mm/memcontrol.c:memory_reclaim
  - mm/memcontrol.c:memory_oom_group_write
  - mm/memcontrol.c:memory_oom_group_show
  - mm/memcontrol.c:memory_numa_stat_show
  - mm/memcontrol.c:memory_stat_show
  - mm/memcontrol.c:memory_events_local_show
  - mm/memcontrol.c:memory_events_show
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_max_show
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:memory_high_show
  - mm/memcontrol.c:memory_low_write
  - mm/memcontrol.c:memory_low_show
  - mm/memcontrol.c:memory_min_write
  - mm/memcontrol.c:memory_min_show
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:mem_cgroup_oom_control_read
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:mem_cgroup_reset
  - mm/memcontrol.c:mem_cgroup_write
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/hugetlb_cgroup.c:hugetlb_events_local_show
  - mm/hugetlb_cgroup.c:hugetlb_events_show
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_reset
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_u64_max
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_numa_stat
  - security/device_cgroup.c:devcgroup_access_write
  - security/device_cgroup.c:devcgroup_seq_show
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-throttle.c:tg_set_limit
  - block/blk-throttle.c:tg_print_limit
  - block/blk-throttle.c:tg_print_rwstat_recursive
  - block/blk-throttle.c:tg_print_rwstat
  - block/blk-throttle.c:tg_print_conf_uint
  - block/blk-throttle.c:tg_print_conf_u64
  - block/blk-ioprio.c:ioprio_set_prio_policy
  - block/blk-ioprio.c:ioprio_show_prio_policy
  - block/blk-iocost.c:ioc_cost_model_show
  - block/blk-iocost.c:ioc_qos_show
  - block/blk-iocost.c:ioc_weight_write
  - block/blk-iocost.c:ioc_weight_show
  - net/core/netprio_cgroup.c:write_priomap
  - net/core/netprio_cgroup.c:read_priomap
```
**Symbols:**

```
ffffffff812030d0-ffffffff8120312c: of_css (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct cgroup_subsys_state *of_css(struct kernfs_open_file *of);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81224f23)
Location: kernel/cgroup/cgroup.c:656
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:__cgroup_procs_start
  - kernel/cgroup/cgroup.c:cgroup_seqfile_show
  - kernel/cgroup/cgroup.c:cgroup_freeze_show
  - kernel/cgroup/cgroup.c:cgroup_pressure_show
  - kernel/cgroup/cgroup.c:cgroup_cpu_pressure_show
  - kernel/cgroup/cgroup.c:cgroup_memory_pressure_show
  - kernel/cgroup/cgroup.c:cgroup_io_pressure_show
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_stat_show
  - kernel/cgroup/cgroup.c:cgroup_events_show
  - kernel/cgroup/cgroup.c:cgroup_max_depth_show
  - kernel/cgroup/cgroup.c:cgroup_max_descendants_show
  - kernel/cgroup/cgroup.c:cgroup_type_show
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_show
  - kernel/cgroup/cgroup.c:cgroup_controllers_show
Direct callers:
  - kernel/sched/core.c:cpu_max_write
  - kernel/sched/core.c:cpu_max_show
  - kernel/sched/core.c:cpu_cfs_stat_show
  - kernel/sched/core.c:cpu_uclamp_max_show
  - kernel/sched/core.c:cpu_uclamp_min_show
  - kernel/sched/build_utility.c:cpuacct_stats_show
  - kernel/sched/build_utility.c:cpuacct_stats_show
  - kernel/sched/build_utility.c:cpuacct_all_seq_show
  - kernel/sched/build_utility.c:__cpuacct_percpu_seq_show
  - kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_show
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_stop
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_read
  - kernel/cgroup/pids.c:pids_events_show
  - kernel/cgroup/pids.c:pids_max_write
  - kernel/cgroup/rdma.c:rdmacg_resource_read
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:sched_partition_show
  - kernel/cgroup/cpuset.c:cpuset_common_seq_show
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/misc.c:misc_events_show
  - kernel/cgroup/misc.c:misc_cg_current_show
  - kernel/cgroup/misc.c:misc_cg_max_write
  - kernel/cgroup/misc.c:misc_cg_max_show
  - mm/memcontrol.c:zswap_max_write
  - mm/memcontrol.c:zswap_max_show
  - mm/memcontrol.c:swap_events_show
  - mm/memcontrol.c:swap_max_write
  - mm/memcontrol.c:swap_max_show
  - mm/memcontrol.c:swap_high_write
  - mm/memcontrol.c:swap_high_show
  - mm/memcontrol.c:memory_reclaim
  - mm/memcontrol.c:memory_oom_group_write
  - mm/memcontrol.c:memory_oom_group_show
  - mm/memcontrol.c:memory_numa_stat_show
  - mm/memcontrol.c:memory_stat_show
  - mm/memcontrol.c:memory_events_local_show
  - mm/memcontrol.c:memory_events_show
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_max_show
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:memory_high_show
  - mm/memcontrol.c:memory_low_write
  - mm/memcontrol.c:memory_low_show
  - mm/memcontrol.c:memory_min_write
  - mm/memcontrol.c:memory_min_show
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:mem_cgroup_oom_control_read
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:mem_cgroup_reset
  - mm/memcontrol.c:mem_cgroup_write
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/hugetlb_cgroup.c:hugetlb_events_local_show
  - mm/hugetlb_cgroup.c:hugetlb_events_show
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_reset
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_u64_max
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_numa_stat
  - security/device_cgroup.c:devcgroup_access_write
  - security/device_cgroup.c:devcgroup_seq_show
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-throttle.c:tg_set_limit
  - block/blk-throttle.c:tg_print_limit
  - block/blk-throttle.c:tg_print_rwstat_recursive
  - block/blk-throttle.c:tg_print_rwstat
  - block/blk-throttle.c:tg_print_conf_uint
  - block/blk-throttle.c:tg_print_conf_u64
  - block/blk-ioprio.c:ioprio_set_prio_policy
  - block/blk-ioprio.c:ioprio_show_prio_policy
  - block/blk-iocost.c:ioc_cost_model_show
  - block/blk-iocost.c:ioc_qos_show
  - block/blk-iocost.c:ioc_weight_write
  - block/blk-iocost.c:ioc_weight_show
  - net/core/netprio_cgroup.c:write_priomap
  - net/core/netprio_cgroup.c:read_priomap
```
**Symbols:**

```
ffffffff81218510-ffffffff8121856c: of_css (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct cgroup_subsys_state *of_css(struct kernfs_open_file *of);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8123cc13)
Location: kernel/cgroup/cgroup.c:636
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:__cgroup_procs_start
  - kernel/cgroup/cgroup.c:cgroup_seqfile_show
  - kernel/cgroup/cgroup.c:cgroup_freeze_show
  - kernel/cgroup/cgroup.c:cgroup_pressure_show
  - kernel/cgroup/cgroup.c:cgroup_cpu_pressure_show
  - kernel/cgroup/cgroup.c:cgroup_memory_pressure_show
  - kernel/cgroup/cgroup.c:cgroup_io_pressure_show
  - kernel/cgroup/cgroup.c:cpu_local_stat_show
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_stat_show
  - kernel/cgroup/cgroup.c:cgroup_events_show
  - kernel/cgroup/cgroup.c:cgroup_max_depth_show
  - kernel/cgroup/cgroup.c:cgroup_max_descendants_show
  - kernel/cgroup/cgroup.c:cgroup_type_show
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_show
  - kernel/cgroup/cgroup.c:cgroup_controllers_show
Direct callers:
  - kernel/sched/core.c:cpu_max_write
  - kernel/sched/core.c:cpu_max_show
  - kernel/sched/core.c:cpu_cfs_local_stat_show
  - kernel/sched/core.c:cpu_cfs_stat_show
  - kernel/sched/core.c:cpu_uclamp_max_show
  - kernel/sched/core.c:cpu_uclamp_min_show
  - kernel/sched/build_utility.c:cpuacct_stats_show
  - kernel/sched/build_utility.c:cpuacct_stats_show
  - kernel/sched/build_utility.c:cpuacct_all_seq_show
  - kernel/sched/build_utility.c:__cpuacct_percpu_seq_show
  - kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_show
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_stop
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_read
  - kernel/cgroup/pids.c:pids_events_show
  - kernel/cgroup/pids.c:pids_max_write
  - kernel/cgroup/rdma.c:rdmacg_resource_read
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:sched_partition_show
  - kernel/cgroup/cpuset.c:cpuset_common_seq_show
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/misc.c:misc_events_show
  - kernel/cgroup/misc.c:misc_cg_current_show
  - kernel/cgroup/misc.c:misc_cg_max_write
  - kernel/cgroup/misc.c:misc_cg_max_show
  - mm/memcontrol.c:zswap_writeback_write
  - mm/memcontrol.c:zswap_writeback_show
  - mm/memcontrol.c:zswap_max_write
  - mm/memcontrol.c:zswap_max_show
  - mm/memcontrol.c:swap_events_show
  - mm/memcontrol.c:swap_max_write
  - mm/memcontrol.c:swap_max_show
  - mm/memcontrol.c:swap_high_write
  - mm/memcontrol.c:swap_high_show
  - mm/memcontrol.c:memory_reclaim
  - mm/memcontrol.c:memory_oom_group_write
  - mm/memcontrol.c:memory_oom_group_show
  - mm/memcontrol.c:memory_numa_stat_show
  - mm/memcontrol.c:memory_stat_show
  - mm/memcontrol.c:memory_events_local_show
  - mm/memcontrol.c:memory_events_show
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_max_show
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:memory_high_show
  - mm/memcontrol.c:memory_low_write
  - mm/memcontrol.c:memory_low_show
  - mm/memcontrol.c:memory_min_write
  - mm/memcontrol.c:memory_min_show
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:mem_cgroup_oom_control_read
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:mem_cgroup_reset
  - mm/memcontrol.c:mem_cgroup_write
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/hugetlb_cgroup.c:hugetlb_events_local_show
  - mm/hugetlb_cgroup.c:hugetlb_events_show
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_reset
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_u64_max
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_numa_stat
  - security/device_cgroup.c:devcgroup_access_write
  - security/device_cgroup.c:devcgroup_seq_show
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-throttle.c:tg_set_limit
  - block/blk-throttle.c:tg_print_limit
  - block/blk-throttle.c:tg_print_rwstat_recursive
  - block/blk-throttle.c:tg_print_rwstat
  - block/blk-throttle.c:tg_print_conf_uint
  - block/blk-throttle.c:tg_print_conf_u64
  - block/blk-ioprio.c:ioprio_set_prio_policy
  - block/blk-ioprio.c:ioprio_show_prio_policy
  - block/blk-iocost.c:ioc_cost_model_show
  - block/blk-iocost.c:ioc_qos_show
  - block/blk-iocost.c:ioc_weight_write
  - block/blk-iocost.c:ioc_weight_show
  - net/core/netprio_cgroup.c:write_priomap
  - net/core/netprio_cgroup.c:read_priomap
```
**Symbols:**

```
ffffffff812300d0-ffffffff8123012c: of_css (STB_GLOBAL)
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
struct cgroup_subsys_state *of_css(struct kernfs_open_file *of);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffff8000101ce6f8)
Location: kernel/cgroup/cgroup.c:630
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_seqfile_show
  - kernel/cgroup/cgroup.c:cgroup_freeze_show
  - kernel/cgroup/cgroup.c:cgroup_cpu_pressure_show
  - kernel/cgroup/cgroup.c:cgroup_memory_pressure_show
  - kernel/cgroup/cgroup.c:cgroup_io_pressure_show
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_stat_show
  - kernel/cgroup/cgroup.c:cgroup_events_show
  - kernel/cgroup/cgroup.c:cgroup_max_depth_show
  - kernel/cgroup/cgroup.c:cgroup_max_descendants_show
  - kernel/cgroup/cgroup.c:cgroup_type_show
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_show
  - kernel/cgroup/cgroup.c:cgroup_controllers_show
Direct callers:
  - kernel/sched/core.c:cpu_max_write
  - kernel/sched/core.c:cpu_max_show
  - kernel/sched/core.c:cpu_cfs_stat_show
  - kernel/sched/core.c:cpu_uclamp_max_show
  - kernel/sched/core.c:cpu_uclamp_min_show
  - kernel/sched/cpuacct.c:cpuacct_stats_show
  - kernel/sched/cpuacct.c:cpuacct_all_seq_show
  - kernel/sched/cpuacct.c:__cpuacct_percpu_seq_show
  - kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_show
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_stop
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_read
  - kernel/cgroup/pids.c:pids_events_show
  - kernel/cgroup/pids.c:pids_max_write
  - kernel/cgroup/rdma.c:rdmacg_resource_read
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:sched_partition_show
  - kernel/cgroup/cpuset.c:cpuset_common_seq_show
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - mm/slab_common.c:memcg_slab_show
  - mm/slab_common.c:memcg_slab_next
  - mm/slab_common.c:memcg_slab_start
  - mm/memcontrol.c:swap_events_show
  - mm/memcontrol.c:swap_max_write
  - mm/memcontrol.c:swap_max_show
  - mm/memcontrol.c:memory_oom_group_write
  - mm/memcontrol.c:memory_oom_group_show
  - mm/memcontrol.c:memory_stat_show
  - mm/memcontrol.c:memory_events_local_show
  - mm/memcontrol.c:memory_events_show
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_max_show
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:memory_high_show
  - mm/memcontrol.c:memory_low_write
  - mm/memcontrol.c:memory_low_show
  - mm/memcontrol.c:memory_min_write
  - mm/memcontrol.c:memory_min_show
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:mem_cgroup_oom_control_read
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:mem_cgroup_reset
  - mm/memcontrol.c:mem_cgroup_write
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_reset
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_write
  - security/device_cgroup.c:devcgroup_access_write
  - security/device_cgroup.c:devcgroup_seq_show
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-cgroup.c:blkg_print_stat_ios_recursive
  - block/blk-cgroup.c:blkg_print_stat_bytes_recursive
  - block/blk-cgroup.c:blkg_print_stat_ios
  - block/blk-cgroup.c:blkg_print_stat_bytes
  - block/blk-throttle.c:tg_set_limit
  - block/blk-throttle.c:tg_print_limit
  - block/blk-throttle.c:tg_print_conf_uint
  - block/blk-throttle.c:tg_print_conf_u64
  - block/blk-iocost.c:ioc_cost_model_show
  - block/blk-iocost.c:ioc_qos_show
  - block/blk-iocost.c:ioc_weight_write
  - block/blk-iocost.c:ioc_weight_show
  - net/core/netprio_cgroup.c:write_priomap
  - net/core/netprio_cgroup.c:read_priomap
```
**Symbols:**

```
ffff8000101cde38-ffff8000101cde80: of_css (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct cgroup_subsys_state *of_css(struct kernfs_open_file *of);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (c041a984)
Location: kernel/cgroup/cgroup.c:630
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:__cgroup_procs_start
  - kernel/cgroup/cgroup.c:cgroup_seqfile_show
  - kernel/cgroup/cgroup.c:cgroup_freeze_show
  - kernel/cgroup/cgroup.c:cgroup_cpu_pressure_show
  - kernel/cgroup/cgroup.c:cgroup_memory_pressure_show
  - kernel/cgroup/cgroup.c:cgroup_io_pressure_show
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_stat_show
  - kernel/cgroup/cgroup.c:cgroup_events_show
  - kernel/cgroup/cgroup.c:cgroup_max_depth_show
  - kernel/cgroup/cgroup.c:cgroup_max_descendants_show
  - kernel/cgroup/cgroup.c:cgroup_type_show
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_show
  - kernel/cgroup/cgroup.c:cgroup_controllers_show
Direct callers:
  - kernel/sched/core.c:cpu_max_write
  - kernel/sched/core.c:cpu_max_show
  - kernel/sched/core.c:cpu_cfs_stat_show
  - kernel/sched/core.c:cpu_uclamp_max_show
  - kernel/sched/core.c:cpu_uclamp_min_show
  - kernel/sched/cpuacct.c:cpuacct_stats_show
  - kernel/sched/cpuacct.c:cpuacct_all_seq_show
  - kernel/sched/cpuacct.c:__cpuacct_percpu_seq_show
  - kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_show
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_stop
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_read
  - kernel/cgroup/pids.c:pids_events_show
  - kernel/cgroup/pids.c:pids_max_write
  - kernel/cgroup/rdma.c:rdmacg_resource_read
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:sched_partition_show
  - kernel/cgroup/cpuset.c:cpuset_common_seq_show
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - mm/slab_common.c:memcg_slab_show
  - mm/slab_common.c:memcg_slab_next
  - mm/slab_common.c:memcg_slab_start
  - mm/memcontrol.c:swap_events_show
  - mm/memcontrol.c:swap_max_write
  - mm/memcontrol.c:swap_max_show
  - mm/memcontrol.c:memory_oom_group_write
  - mm/memcontrol.c:memory_oom_group_show
  - mm/memcontrol.c:memory_stat_show
  - mm/memcontrol.c:memory_events_local_show
  - mm/memcontrol.c:memory_events_show
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_max_show
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:memory_high_show
  - mm/memcontrol.c:memory_low_write
  - mm/memcontrol.c:memory_low_show
  - mm/memcontrol.c:memory_min_write
  - mm/memcontrol.c:memory_min_show
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:mem_cgroup_oom_control_read
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:mem_cgroup_reset
  - mm/memcontrol.c:mem_cgroup_write
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - security/device_cgroup.c:devcgroup_access_write
  - security/device_cgroup.c:devcgroup_seq_show
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-cgroup.c:blkg_print_stat_ios_recursive
  - block/blk-cgroup.c:blkg_print_stat_bytes_recursive
  - block/blk-cgroup.c:blkg_print_stat_ios
  - block/blk-cgroup.c:blkg_print_stat_bytes
  - block/blk-throttle.c:tg_set_limit
  - block/blk-throttle.c:tg_print_limit
  - block/blk-throttle.c:tg_print_conf_uint
  - block/blk-throttle.c:tg_print_conf_u64
  - block/blk-iocost.c:ioc_cost_model_show
  - block/blk-iocost.c:ioc_qos_show
  - block/blk-iocost.c:ioc_weight_write
  - block/blk-iocost.c:ioc_weight_show
  - net/core/netprio_cgroup.c:write_priomap
  - net/core/netprio_cgroup.c:read_priomap
```
**Symbols:**

```
c0411340-c041137c: of_css (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct cgroup_subsys_state *of_css(struct kernfs_open_file *of);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (c0000000002385b8)
Location: kernel/cgroup/cgroup.c:630
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_seqfile_show
  - kernel/cgroup/cgroup.c:cgroup_freeze_show
  - kernel/cgroup/cgroup.c:cgroup_cpu_pressure_show
  - kernel/cgroup/cgroup.c:cgroup_memory_pressure_show
  - kernel/cgroup/cgroup.c:cgroup_io_pressure_show
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_stat_show
  - kernel/cgroup/cgroup.c:cgroup_events_show
  - kernel/cgroup/cgroup.c:cgroup_max_depth_show
  - kernel/cgroup/cgroup.c:cgroup_max_descendants_show
  - kernel/cgroup/cgroup.c:cgroup_type_show
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_show
  - kernel/cgroup/cgroup.c:cgroup_controllers_show
Direct callers:
  - kernel/sched/core.c:cpu_max_write
  - kernel/sched/core.c:cpu_max_show
  - kernel/sched/core.c:cpu_cfs_stat_show
  - kernel/sched/core.c:cpu_uclamp_max_show
  - kernel/sched/core.c:cpu_uclamp_min_show
  - kernel/sched/cpuacct.c:cpuacct_stats_show
  - kernel/sched/cpuacct.c:cpuacct_all_seq_show
  - kernel/sched/cpuacct.c:__cpuacct_percpu_seq_show
  - kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_show
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_stop
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_read
  - kernel/cgroup/pids.c:pids_events_show
  - kernel/cgroup/pids.c:pids_max_write
  - kernel/cgroup/rdma.c:rdmacg_resource_read
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:sched_partition_show
  - kernel/cgroup/cpuset.c:cpuset_common_seq_show
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - mm/slab_common.c:memcg_slab_show
  - mm/slab_common.c:memcg_slab_next
  - mm/slab_common.c:memcg_slab_start
  - mm/memcontrol.c:swap_events_show
  - mm/memcontrol.c:swap_max_write
  - mm/memcontrol.c:swap_max_show
  - mm/memcontrol.c:memory_oom_group_write
  - mm/memcontrol.c:memory_oom_group_show
  - mm/memcontrol.c:memory_stat_show
  - mm/memcontrol.c:memory_events_local_show
  - mm/memcontrol.c:memory_events_show
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_max_show
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:memory_high_show
  - mm/memcontrol.c:memory_low_write
  - mm/memcontrol.c:memory_low_show
  - mm/memcontrol.c:memory_min_write
  - mm/memcontrol.c:memory_min_show
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:mem_cgroup_oom_control_read
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:mem_cgroup_reset
  - mm/memcontrol.c:mem_cgroup_write
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_reset
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_write
  - security/device_cgroup.c:devcgroup_access_write
  - security/device_cgroup.c:devcgroup_seq_show
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-cgroup.c:blkg_print_stat_ios_recursive
  - block/blk-cgroup.c:blkg_print_stat_bytes_recursive
  - block/blk-cgroup.c:blkg_print_stat_ios
  - block/blk-cgroup.c:blkg_print_stat_bytes
  - block/blk-throttle.c:tg_set_limit
  - block/blk-throttle.c:tg_print_limit
  - block/blk-throttle.c:tg_print_conf_uint
  - block/blk-throttle.c:tg_print_conf_u64
  - block/blk-iocost.c:ioc_cost_model_show
  - block/blk-iocost.c:ioc_qos_show
  - block/blk-iocost.c:ioc_weight_write
  - block/blk-iocost.c:ioc_weight_show
  - net/core/netprio_cgroup.c:write_priomap
  - net/core/netprio_cgroup.c:read_priomap
```
**Symbols:**

```
c000000000237850-c000000000237888: of_css (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct cgroup_subsys_state *of_css(struct kernfs_open_file *of);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffe00014903e)
Location: kernel/cgroup/cgroup.c:630
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_seqfile_show
  - kernel/cgroup/cgroup.c:cgroup_freeze_show
  - kernel/cgroup/cgroup.c:cgroup_cpu_pressure_show
  - kernel/cgroup/cgroup.c:cgroup_memory_pressure_show
  - kernel/cgroup/cgroup.c:cgroup_io_pressure_show
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_stat_show
  - kernel/cgroup/cgroup.c:cgroup_events_show
  - kernel/cgroup/cgroup.c:cgroup_max_depth_show
  - kernel/cgroup/cgroup.c:cgroup_max_descendants_show
  - kernel/cgroup/cgroup.c:cgroup_type_show
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_show
  - kernel/cgroup/cgroup.c:cgroup_controllers_show
Direct callers:
  - kernel/sched/core.c:cpu_max_write
  - kernel/sched/core.c:cpu_max_show
  - kernel/sched/core.c:cpu_cfs_stat_show
  - kernel/sched/cpuacct.c:cpuacct_stats_show
  - kernel/sched/cpuacct.c:cpuacct_all_seq_show
  - kernel/sched/cpuacct.c:__cpuacct_percpu_seq_show
  - kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_show
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_stop
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_read
  - kernel/cgroup/pids.c:pids_events_show
  - kernel/cgroup/pids.c:pids_max_write
  - kernel/cgroup/rdma.c:rdmacg_resource_read
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:sched_partition_show
  - kernel/cgroup/cpuset.c:cpuset_common_seq_show
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - mm/slab_common.c:memcg_slab_show
  - mm/slab_common.c:memcg_slab_next
  - mm/slab_common.c:memcg_slab_start
  - mm/memcontrol.c:swap_events_show
  - mm/memcontrol.c:swap_max_write
  - mm/memcontrol.c:swap_max_show
  - mm/memcontrol.c:memory_oom_group_write
  - mm/memcontrol.c:memory_oom_group_show
  - mm/memcontrol.c:memory_stat_show
  - mm/memcontrol.c:memory_events_local_show
  - mm/memcontrol.c:memory_events_show
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_max_show
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:memory_high_show
  - mm/memcontrol.c:memory_low_write
  - mm/memcontrol.c:memory_low_show
  - mm/memcontrol.c:memory_min_write
  - mm/memcontrol.c:memory_min_show
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:mem_cgroup_oom_control_read
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:mem_cgroup_reset
  - mm/memcontrol.c:mem_cgroup_write
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_reset
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_write
  - security/device_cgroup.c:devcgroup_access_write
  - security/device_cgroup.c:devcgroup_seq_show
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-cgroup.c:blkg_print_stat_ios_recursive
  - block/blk-cgroup.c:blkg_print_stat_bytes_recursive
  - block/blk-cgroup.c:blkg_print_stat_ios
  - block/blk-cgroup.c:blkg_print_stat_bytes
  - block/blk-throttle.c:tg_set_limit
  - block/blk-throttle.c:tg_print_limit
  - block/blk-throttle.c:tg_print_conf_uint
  - block/blk-throttle.c:tg_print_conf_u64
  - block/blk-iocost.c:ioc_cost_model_show
  - block/blk-iocost.c:ioc_qos_show
  - block/blk-iocost.c:ioc_weight_write
  - block/blk-iocost.c:ioc_weight_show
  - net/core/netprio_cgroup.c:write_priomap
  - net/core/netprio_cgroup.c:read_priomap
```
**Symbols:**

```
ffffffe0001485b4-ffffffe0001485ee: of_css (STB_GLOBAL)
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
struct cgroup_subsys_state *of_css(struct kernfs_open_file *of);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811565dc)
Location: kernel/cgroup/cgroup.c:630
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_seqfile_show
  - kernel/cgroup/cgroup.c:cgroup_freeze_show
  - kernel/cgroup/cgroup.c:cgroup_cpu_pressure_show
  - kernel/cgroup/cgroup.c:cgroup_memory_pressure_show
  - kernel/cgroup/cgroup.c:cgroup_io_pressure_show
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_stat_show
  - kernel/cgroup/cgroup.c:cgroup_events_show
  - kernel/cgroup/cgroup.c:cgroup_max_depth_show
  - kernel/cgroup/cgroup.c:cgroup_max_descendants_show
  - kernel/cgroup/cgroup.c:cgroup_type_show
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_show
  - kernel/cgroup/cgroup.c:cgroup_controllers_show
Direct callers:
  - kernel/sched/core.c:cpu_max_write
  - kernel/sched/core.c:cpu_max_show
  - kernel/sched/core.c:cpu_cfs_stat_show
  - kernel/sched/core.c:cpu_uclamp_max_show
  - kernel/sched/core.c:cpu_uclamp_min_show
  - kernel/sched/cpuacct.c:cpuacct_stats_show
  - kernel/sched/cpuacct.c:cpuacct_all_seq_show
  - kernel/sched/cpuacct.c:__cpuacct_percpu_seq_show
  - kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_show
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_stop
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_read
  - kernel/cgroup/pids.c:pids_events_show
  - kernel/cgroup/pids.c:pids_max_write
  - kernel/cgroup/rdma.c:rdmacg_resource_read
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:sched_partition_show
  - kernel/cgroup/cpuset.c:cpuset_common_seq_show
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - mm/slab_common.c:memcg_slab_show
  - mm/slab_common.c:memcg_slab_next
  - mm/slab_common.c:memcg_slab_start
  - mm/memcontrol.c:swap_events_show
  - mm/memcontrol.c:swap_max_write
  - mm/memcontrol.c:swap_max_show
  - mm/memcontrol.c:memory_oom_group_write
  - mm/memcontrol.c:memory_oom_group_show
  - mm/memcontrol.c:memory_stat_show
  - mm/memcontrol.c:memory_events_local_show
  - mm/memcontrol.c:memory_events_show
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_max_show
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:memory_high_show
  - mm/memcontrol.c:memory_low_write
  - mm/memcontrol.c:memory_low_show
  - mm/memcontrol.c:memory_min_write
  - mm/memcontrol.c:memory_min_show
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:mem_cgroup_oom_control_read
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:mem_cgroup_reset
  - mm/memcontrol.c:mem_cgroup_write
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_reset
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_write
  - security/device_cgroup.c:devcgroup_access_write
  - security/device_cgroup.c:devcgroup_seq_show
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-cgroup.c:blkg_print_stat_ios_recursive
  - block/blk-cgroup.c:blkg_print_stat_bytes_recursive
  - block/blk-cgroup.c:blkg_print_stat_ios
  - block/blk-cgroup.c:blkg_print_stat_bytes
  - block/blk-throttle.c:tg_set_limit
  - block/blk-throttle.c:tg_print_limit
  - block/blk-throttle.c:tg_print_conf_uint
  - block/blk-throttle.c:tg_print_conf_u64
  - block/blk-iocost.c:ioc_cost_model_show
  - block/blk-iocost.c:ioc_qos_show
  - block/blk-iocost.c:ioc_weight_write
  - block/blk-iocost.c:ioc_weight_show
  - net/core/netprio_cgroup.c:write_priomap
  - net/core/netprio_cgroup.c:read_priomap
```
**Symbols:**

```
ffffffff81155e40-ffffffff81155e75: of_css (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct cgroup_subsys_state *of_css(struct kernfs_open_file *of);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811498fc)
Location: kernel/cgroup/cgroup.c:630
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_seqfile_show
  - kernel/cgroup/cgroup.c:cgroup_freeze_show
  - kernel/cgroup/cgroup.c:cgroup_cpu_pressure_show
  - kernel/cgroup/cgroup.c:cgroup_memory_pressure_show
  - kernel/cgroup/cgroup.c:cgroup_io_pressure_show
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_stat_show
  - kernel/cgroup/cgroup.c:cgroup_events_show
  - kernel/cgroup/cgroup.c:cgroup_max_depth_show
  - kernel/cgroup/cgroup.c:cgroup_max_descendants_show
  - kernel/cgroup/cgroup.c:cgroup_type_show
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_show
  - kernel/cgroup/cgroup.c:cgroup_controllers_show
Direct callers:
  - kernel/sched/core.c:cpu_max_write
  - kernel/sched/core.c:cpu_max_show
  - kernel/sched/core.c:cpu_cfs_stat_show
  - kernel/sched/core.c:cpu_uclamp_max_show
  - kernel/sched/core.c:cpu_uclamp_min_show
  - kernel/sched/cpuacct.c:cpuacct_stats_show
  - kernel/sched/cpuacct.c:cpuacct_all_seq_show
  - kernel/sched/cpuacct.c:__cpuacct_percpu_seq_show
  - kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_show
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_stop
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_read
  - kernel/cgroup/pids.c:pids_events_show
  - kernel/cgroup/pids.c:pids_max_write
  - kernel/cgroup/rdma.c:rdmacg_resource_read
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:sched_partition_show
  - kernel/cgroup/cpuset.c:cpuset_common_seq_show
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - mm/slab_common.c:memcg_slab_show
  - mm/slab_common.c:memcg_slab_next
  - mm/slab_common.c:memcg_slab_start
  - mm/memcontrol.c:swap_events_show
  - mm/memcontrol.c:swap_max_write
  - mm/memcontrol.c:swap_max_show
  - mm/memcontrol.c:memory_oom_group_write
  - mm/memcontrol.c:memory_oom_group_show
  - mm/memcontrol.c:memory_stat_show
  - mm/memcontrol.c:memory_events_local_show
  - mm/memcontrol.c:memory_events_show
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_max_show
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:memory_high_show
  - mm/memcontrol.c:memory_low_write
  - mm/memcontrol.c:memory_low_show
  - mm/memcontrol.c:memory_min_write
  - mm/memcontrol.c:memory_min_show
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:mem_cgroup_oom_control_read
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:mem_cgroup_reset
  - mm/memcontrol.c:mem_cgroup_write
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_reset
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_write
  - security/device_cgroup.c:devcgroup_access_write
  - security/device_cgroup.c:devcgroup_seq_show
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-cgroup.c:blkg_print_stat_ios_recursive
  - block/blk-cgroup.c:blkg_print_stat_bytes_recursive
  - block/blk-cgroup.c:blkg_print_stat_ios
  - block/blk-cgroup.c:blkg_print_stat_bytes
  - block/blk-throttle.c:tg_set_limit
  - block/blk-throttle.c:tg_print_limit
  - block/blk-throttle.c:tg_print_conf_uint
  - block/blk-throttle.c:tg_print_conf_u64
  - block/blk-iocost.c:ioc_cost_model_show
  - block/blk-iocost.c:ioc_qos_show
  - block/blk-iocost.c:ioc_weight_write
  - block/blk-iocost.c:ioc_weight_show
  - net/core/netprio_cgroup.c:write_priomap
  - net/core/netprio_cgroup.c:read_priomap
```
**Symbols:**

```
ffffffff81149160-ffffffff81149195: of_css (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct cgroup_subsys_state *of_css(struct kernfs_open_file *of);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811543ac)
Location: kernel/cgroup/cgroup.c:630
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_seqfile_show
  - kernel/cgroup/cgroup.c:cgroup_freeze_show
  - kernel/cgroup/cgroup.c:cgroup_cpu_pressure_show
  - kernel/cgroup/cgroup.c:cgroup_memory_pressure_show
  - kernel/cgroup/cgroup.c:cgroup_io_pressure_show
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_stat_show
  - kernel/cgroup/cgroup.c:cgroup_events_show
  - kernel/cgroup/cgroup.c:cgroup_max_depth_show
  - kernel/cgroup/cgroup.c:cgroup_max_descendants_show
  - kernel/cgroup/cgroup.c:cgroup_type_show
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_show
  - kernel/cgroup/cgroup.c:cgroup_controllers_show
Direct callers:
  - kernel/sched/core.c:cpu_max_write
  - kernel/sched/core.c:cpu_max_show
  - kernel/sched/core.c:cpu_cfs_stat_show
  - kernel/sched/cpuacct.c:cpuacct_stats_show
  - kernel/sched/cpuacct.c:cpuacct_all_seq_show
  - kernel/sched/cpuacct.c:__cpuacct_percpu_seq_show
  - kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_show
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_stop
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_read
  - kernel/cgroup/pids.c:pids_events_show
  - kernel/cgroup/pids.c:pids_max_write
  - kernel/cgroup/rdma.c:rdmacg_resource_read
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:sched_partition_show
  - kernel/cgroup/cpuset.c:cpuset_common_seq_show
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - mm/slab_common.c:memcg_slab_show
  - mm/slab_common.c:memcg_slab_next
  - mm/slab_common.c:memcg_slab_start
  - mm/memcontrol.c:swap_events_show
  - mm/memcontrol.c:swap_max_write
  - mm/memcontrol.c:swap_max_show
  - mm/memcontrol.c:memory_oom_group_write
  - mm/memcontrol.c:memory_oom_group_show
  - mm/memcontrol.c:memory_stat_show
  - mm/memcontrol.c:memory_events_local_show
  - mm/memcontrol.c:memory_events_show
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_max_show
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:memory_high_show
  - mm/memcontrol.c:memory_low_write
  - mm/memcontrol.c:memory_low_show
  - mm/memcontrol.c:memory_min_write
  - mm/memcontrol.c:memory_min_show
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:mem_cgroup_oom_control_read
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:mem_cgroup_reset
  - mm/memcontrol.c:mem_cgroup_write
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_reset
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_write
  - security/device_cgroup.c:devcgroup_access_write
  - security/device_cgroup.c:devcgroup_seq_show
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-cgroup.c:blkg_print_stat_ios_recursive
  - block/blk-cgroup.c:blkg_print_stat_bytes_recursive
  - block/blk-cgroup.c:blkg_print_stat_ios
  - block/blk-cgroup.c:blkg_print_stat_bytes
  - block/blk-throttle.c:tg_set_limit
  - block/blk-throttle.c:tg_print_limit
  - block/blk-throttle.c:tg_print_conf_uint
  - block/blk-throttle.c:tg_print_conf_u64
  - block/blk-iocost.c:ioc_cost_model_show
  - block/blk-iocost.c:ioc_qos_show
  - block/blk-iocost.c:ioc_weight_write
  - block/blk-iocost.c:ioc_weight_show
  - net/core/netprio_cgroup.c:write_priomap
  - net/core/netprio_cgroup.c:read_priomap
```
**Symbols:**

```
ffffffff81153c10-ffffffff81153c45: of_css (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct cgroup_subsys_state *of_css(struct kernfs_open_file *of);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811612ac)
Location: kernel/cgroup/cgroup.c:630
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_seqfile_show
  - kernel/cgroup/cgroup.c:cgroup_freeze_show
  - kernel/cgroup/cgroup.c:cgroup_cpu_pressure_show
  - kernel/cgroup/cgroup.c:cgroup_memory_pressure_show
  - kernel/cgroup/cgroup.c:cgroup_io_pressure_show
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_stat_show
  - kernel/cgroup/cgroup.c:cgroup_events_show
  - kernel/cgroup/cgroup.c:cgroup_max_depth_show
  - kernel/cgroup/cgroup.c:cgroup_max_descendants_show
  - kernel/cgroup/cgroup.c:cgroup_type_show
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_show
  - kernel/cgroup/cgroup.c:cgroup_controllers_show
Direct callers:
  - kernel/sched/core.c:cpu_max_write
  - kernel/sched/core.c:cpu_max_show
  - kernel/sched/core.c:cpu_cfs_stat_show
  - kernel/sched/core.c:cpu_uclamp_max_show
  - kernel/sched/core.c:cpu_uclamp_min_show
  - kernel/sched/cpuacct.c:cpuacct_stats_show
  - kernel/sched/cpuacct.c:cpuacct_all_seq_show
  - kernel/sched/cpuacct.c:__cpuacct_percpu_seq_show
  - kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_show
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_stop
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_read
  - kernel/cgroup/pids.c:pids_events_show
  - kernel/cgroup/pids.c:pids_max_write
  - kernel/cgroup/rdma.c:rdmacg_resource_read
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:sched_partition_show
  - kernel/cgroup/cpuset.c:cpuset_common_seq_show
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - mm/slab_common.c:memcg_slab_show
  - mm/slab_common.c:memcg_slab_next
  - mm/slab_common.c:memcg_slab_start
  - mm/memcontrol.c:swap_events_show
  - mm/memcontrol.c:swap_max_write
  - mm/memcontrol.c:swap_max_show
  - mm/memcontrol.c:memory_oom_group_write
  - mm/memcontrol.c:memory_oom_group_show
  - mm/memcontrol.c:memory_stat_show
  - mm/memcontrol.c:memory_events_local_show
  - mm/memcontrol.c:memory_events_show
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_max_show
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:memory_high_show
  - mm/memcontrol.c:memory_low_write
  - mm/memcontrol.c:memory_low_show
  - mm/memcontrol.c:memory_min_write
  - mm/memcontrol.c:memory_min_show
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:mem_cgroup_oom_control_read
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:mem_cgroup_reset
  - mm/memcontrol.c:mem_cgroup_write
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_reset
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_write
  - security/device_cgroup.c:devcgroup_access_write
  - security/device_cgroup.c:devcgroup_seq_show
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-cgroup.c:blkg_print_stat_ios_recursive
  - block/blk-cgroup.c:blkg_print_stat_bytes_recursive
  - block/blk-cgroup.c:blkg_print_stat_ios
  - block/blk-cgroup.c:blkg_print_stat_bytes
  - block/blk-throttle.c:tg_set_limit
  - block/blk-throttle.c:tg_print_limit
  - block/blk-throttle.c:tg_print_conf_uint
  - block/blk-throttle.c:tg_print_conf_u64
  - block/blk-iocost.c:ioc_cost_model_show
  - block/blk-iocost.c:ioc_qos_show
  - block/blk-iocost.c:ioc_weight_write
  - block/blk-iocost.c:ioc_weight_show
  - net/core/netprio_cgroup.c:write_priomap
  - net/core/netprio_cgroup.c:read_priomap
```
**Symbols:**

```
ffffffff81160b10-ffffffff81160b45: of_css (STB_GLOBAL)
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
