# Function: <code>seq_css</code>

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
In kernel/sched/core.c (ffffffff810a642f)
Location: include/linux/cgroup.h:505
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_stats_show
```
```
In kernel/sched/cpuacct.c (ffffffff810c9686)
Location: include/linux/cgroup.h:505
Inline: True
Inline callers:
  - kernel/sched/cpuacct.c:cpuacct_stats_show
  - kernel/sched/cpuacct.c:cpuacct_percpu_seq_show
```
```
In kernel/cgroup.c (ffffffff8111240b)
Location: include/linux/cgroup.h:505
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
```
```
In kernel/cgroup_freezer.c (ffffffff81119ea7)
Location: include/linux/cgroup.h:505
Inline: True
Inline callers:
  - kernel/cgroup_freezer.c:freezer_read
```
```
In kernel/cgroup_pids.c (ffffffff8111a3cd)
Location: include/linux/cgroup.h:505
Inline: True
```
```
In kernel/cpuset.c (ffffffff8111bf01)
Location: include/linux/cgroup.h:505
Inline: True
Inline callers:
  - kernel/cpuset.c:cpuset_common_seq_show
```
```
In mm/slab_common.c (ffffffff811b4b56)
Location: include/linux/cgroup.h:505
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_slab_show
```
```
In mm/memcontrol.c (ffffffff811f96df)
Location: include/linux/cgroup.h:505
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_oom_control_read
  - mm/memcontrol.c:memory_max_show
  - mm/memcontrol.c:memory_high_show
  - mm/memcontrol.c:memory_low_show
  - mm/memcontrol.c:memory_events_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_stat_show
```
```
In security/device_cgroup.c (ffffffff81396017)
Location: include/linux/cgroup.h:505
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_seq_show
```
```
In block/blk-cgroup.c (ffffffff813d8741)
Location: include/linux/cgroup.h:505
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_print_stat_bytes
  - block/blk-cgroup.c:blkg_print_stat_ios
  - block/blk-cgroup.c:blkg_print_stat_bytes_recursive
  - block/blk-cgroup.c:blkg_print_stat_ios_recursive
  - block/blk-cgroup.c:blkcg_print_stat
```
```
In block/blk-throttle.c (ffffffff813d97a1)
Location: include/linux/cgroup.h:505
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_print_conf_uint
  - block/blk-throttle.c:tg_print_conf_u64
  - block/blk-throttle.c:tg_print_max
```
```
In block/cfq-iosched.c (ffffffff813de321)
Location: include/linux/cgroup.h:505
Inline: True
Inline callers:
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
```
```
In net/core/netprio_cgroup.c (ffffffff8173d9b2)
Location: include/linux/cgroup.h:505
Inline: True
Inline callers:
  - net/core/netprio_cgroup.c:read_priomap
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
In kernel/sched/core.c (ffffffff810aa42f)
Location: include/linux/cgroup.h:526
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_stats_show
```
```
In kernel/sched/cpuacct.c (ffffffff810cdd0c)
Location: include/linux/cgroup.h:526
Inline: True
Inline callers:
  - kernel/sched/cpuacct.c:cpuacct_stats_show
  - kernel/sched/cpuacct.c:cpuacct_all_seq_show
  - kernel/sched/cpuacct.c:__cpuacct_percpu_seq_show
```
```
In kernel/cgroup.c (ffffffff8111ad59)
Location: include/linux/cgroup.h:526
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
```
```
In kernel/cgroup_freezer.c (ffffffff81121d07)
Location: include/linux/cgroup.h:526
Inline: True
Inline callers:
  - kernel/cgroup_freezer.c:freezer_read
```
```
In kernel/cgroup_pids.c (ffffffff811220fd)
Location: include/linux/cgroup.h:526
Inline: True
Inline callers:
  - kernel/cgroup_pids.c:pids_events_show
```
```
In kernel/cpuset.c (ffffffff81123e01)
Location: include/linux/cgroup.h:526
Inline: True
Inline callers:
  - kernel/cpuset.c:cpuset_common_seq_show
```
```
In mm/slab_common.c (ffffffff811cdd76)
Location: include/linux/cgroup.h:526
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_slab_show
```
```
In mm/memcontrol.c (ffffffff8121da2d)
Location: include/linux/cgroup.h:526
Inline: True
Inline callers:
  - mm/memcontrol.c:swap_max_show
  - mm/memcontrol.c:memory_stat_show
  - mm/memcontrol.c:memory_events_show
  - mm/memcontrol.c:memory_max_show
  - mm/memcontrol.c:memory_high_show
  - mm/memcontrol.c:memory_low_show
  - mm/memcontrol.c:mem_cgroup_oom_control_read
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
```
```
In security/device_cgroup.c (ffffffff813d1d75)
Location: include/linux/cgroup.h:526
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_seq_show
```
```
In block/blk-cgroup.c (ffffffff8141e5bc)
Location: include/linux/cgroup.h:526
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-cgroup.c:blkg_print_stat_ios_recursive
  - block/blk-cgroup.c:blkg_print_stat_bytes_recursive
  - block/blk-cgroup.c:blkg_print_stat_ios
  - block/blk-cgroup.c:blkg_print_stat_bytes
```
```
In block/blk-throttle.c (ffffffff8141f681)
Location: include/linux/cgroup.h:526
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_print_max
  - block/blk-throttle.c:tg_print_conf_uint
  - block/blk-throttle.c:tg_print_conf_u64
```
```
In block/cfq-iosched.c (ffffffff8142482f)
Location: include/linux/cgroup.h:526
Inline: True
Inline callers:
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
```
```
In net/core/netprio_cgroup.c (ffffffff817aa172)
Location: include/linux/cgroup.h:526
Inline: True
Inline callers:
  - net/core/netprio_cgroup.c:read_priomap
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
In kernel/sched/core.c (ffffffff810b042f)
Location: include/linux/cgroup.h:543
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_stats_show
```
```
In kernel/sched/cpuacct.c (ffffffff810d3d1c)
Location: include/linux/cgroup.h:543
Inline: True
Inline callers:
  - kernel/sched/cpuacct.c:cpuacct_stats_show
  - kernel/sched/cpuacct.c:cpuacct_all_seq_show
  - kernel/sched/cpuacct.c:__cpuacct_percpu_seq_show
```
```
In kernel/cgroup.c (ffffffff81122c16)
Location: include/linux/cgroup.h:543
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
```
```
In kernel/cgroup_freezer.c (ffffffff8112a347)
Location: include/linux/cgroup.h:543
Inline: True
Inline callers:
  - kernel/cgroup_freezer.c:freezer_read
```
```
In kernel/cgroup_pids.c (ffffffff8112a72d)
Location: include/linux/cgroup.h:543
Inline: True
Inline callers:
  - kernel/cgroup_pids.c:pids_events_show
```
```
In kernel/cpuset.c (ffffffff8112c2a1)
Location: include/linux/cgroup.h:543
Inline: True
Inline callers:
  - kernel/cpuset.c:cpuset_common_seq_show
```
```
In mm/slab_common.c (ffffffff811ddec6)
Location: include/linux/cgroup.h:543
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_slab_show
```
```
In mm/memcontrol.c (ffffffff8123000d)
Location: include/linux/cgroup.h:543
Inline: True
Inline callers:
  - mm/memcontrol.c:swap_max_show
  - mm/memcontrol.c:memory_stat_show
  - mm/memcontrol.c:memory_events_show
  - mm/memcontrol.c:memory_max_show
  - mm/memcontrol.c:memory_high_show
  - mm/memcontrol.c:memory_low_show
  - mm/memcontrol.c:mem_cgroup_oom_control_read
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
```
```
In security/device_cgroup.c (ffffffff813e9495)
Location: include/linux/cgroup.h:543
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_seq_show
```
```
In block/blk-cgroup.c (ffffffff81439b7c)
Location: include/linux/cgroup.h:543
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-cgroup.c:blkg_print_stat_ios_recursive
  - block/blk-cgroup.c:blkg_print_stat_bytes_recursive
  - block/blk-cgroup.c:blkg_print_stat_ios
  - block/blk-cgroup.c:blkg_print_stat_bytes
```
```
In block/blk-throttle.c (ffffffff8143ac3e)
Location: include/linux/cgroup.h:543
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_print_max
  - block/blk-throttle.c:tg_print_conf_uint
  - block/blk-throttle.c:tg_print_conf_u64
```
```
In block/cfq-iosched.c (ffffffff8144023f)
Location: include/linux/cgroup.h:543
Inline: True
Inline callers:
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
```
```
In net/core/netprio_cgroup.c (ffffffff817d8cb2)
Location: include/linux/cgroup.h:543
Inline: True
Inline callers:
  - net/core/netprio_cgroup.c:read_priomap
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
In kernel/sched/core.c (ffffffff810ac83f)
Location: include/linux/cgroup.h:563
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_stats_show
```
```
In kernel/sched/cpuacct.c (ffffffff810d2ebc)
Location: include/linux/cgroup.h:563
Inline: True
Inline callers:
  - kernel/sched/cpuacct.c:cpuacct_stats_show
  - kernel/sched/cpuacct.c:cpuacct_all_seq_show
  - kernel/sched/cpuacct.c:__cpuacct_percpu_seq_show
```
```
In kernel/cgroup/cgroup.c (ffffffff811280d7)
Location: include/linux/cgroup.h:563
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_procs_start
  - kernel/cgroup/cgroup.c:cgroup_seqfile_show
  - kernel/cgroup/cgroup.c:cgroup_events_show
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_show
  - kernel/cgroup/cgroup.c:cgroup_controllers_show
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff811290ef)
Location: include/linux/cgroup.h:563
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_show
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_stop
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
```
```
In kernel/cgroup/freezer.c (ffffffff8112b047)
Location: include/linux/cgroup.h:563
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:freezer_read
```
```
In kernel/cgroup/pids.c (ffffffff8112b44d)
Location: include/linux/cgroup.h:563
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_events_show
```
```
In kernel/cgroup/rdma.c (ffffffff8112bb19)
Location: include/linux/cgroup.h:563
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_read
```
```
In kernel/cgroup/cpuset.c (ffffffff8112d511)
Location: include/linux/cgroup.h:563
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_common_seq_show
```
```
In mm/slab_common.c (ffffffff811e7c31)
Location: include/linux/cgroup.h:563
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_slab_show
  - mm/slab_common.c:memcg_slab_next
  - mm/slab_common.c:memcg_slab_start
```
```
In mm/memcontrol.c (ffffffff8123b91d)
Location: include/linux/cgroup.h:563
Inline: True
Inline callers:
  - mm/memcontrol.c:swap_max_show
  - mm/memcontrol.c:memory_stat_show
  - mm/memcontrol.c:memory_events_show
  - mm/memcontrol.c:memory_max_show
  - mm/memcontrol.c:memory_high_show
  - mm/memcontrol.c:memory_low_show
  - mm/memcontrol.c:mem_cgroup_oom_control_read
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
```
```
In security/device_cgroup.c (ffffffff813f58d5)
Location: include/linux/cgroup.h:563
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_seq_show
```
```
In block/blk-cgroup.c (ffffffff814472ec)
Location: include/linux/cgroup.h:563
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-cgroup.c:blkg_print_stat_ios_recursive
  - block/blk-cgroup.c:blkg_print_stat_bytes_recursive
  - block/blk-cgroup.c:blkg_print_stat_ios
  - block/blk-cgroup.c:blkg_print_stat_bytes
```
```
In block/blk-throttle.c (ffffffff8144886e)
Location: include/linux/cgroup.h:563
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_print_limit
  - block/blk-throttle.c:tg_print_conf_uint
  - block/blk-throttle.c:tg_print_conf_u64
```
```
In block/cfq-iosched.c (ffffffff8144f4bf)
Location: include/linux/cgroup.h:563
Inline: True
Inline callers:
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
```
```
In net/core/netprio_cgroup.c (ffffffff817f7ed2)
Location: include/linux/cgroup.h:563
Inline: True
Inline callers:
  - net/core/netprio_cgroup.c:read_priomap
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
In kernel/sched/core.c (ffffffff810b378f)
Location: include/linux/cgroup.h:600
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_max_show
  - kernel/sched/core.c:cpu_cfs_stat_show
```
```
In kernel/sched/cpuacct.c (ffffffff810dab1c)
Location: include/linux/cgroup.h:600
Inline: True
Inline callers:
  - kernel/sched/cpuacct.c:cpuacct_stats_show
  - kernel/sched/cpuacct.c:cpuacct_all_seq_show
  - kernel/sched/cpuacct.c:__cpuacct_percpu_seq_show
```
```
In kernel/cgroup/cgroup.c (ffffffff8112d6b8)
Location: include/linux/cgroup.h:600
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
```
```
In kernel/cgroup/stat.c (ffffffff811356a5)
Location: include/linux/cgroup.h:600
Inline: True
Inline callers:
  - kernel/cgroup/stat.c:cgroup_stat_show_cputime
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81135d6f)
Location: include/linux/cgroup.h:600
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_show
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_stop
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
```
```
In kernel/cgroup/freezer.c (ffffffff81137f11)
Location: include/linux/cgroup.h:600
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:freezer_read
```
```
In kernel/cgroup/pids.c (ffffffff8113824d)
Location: include/linux/cgroup.h:600
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_events_show
```
```
In kernel/cgroup/rdma.c (ffffffff81138919)
Location: include/linux/cgroup.h:600
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_read
```
```
In kernel/cgroup/cpuset.c (ffffffff8113a411)
Location: include/linux/cgroup.h:600
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_common_seq_show
```
```
In mm/slab_common.c (ffffffff811fdfa1)
Location: include/linux/cgroup.h:600
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_slab_show
  - mm/slab_common.c:memcg_slab_next
  - mm/slab_common.c:memcg_slab_start
```
```
In mm/memcontrol.c (ffffffff8125b19d)
Location: include/linux/cgroup.h:600
Inline: True
Inline callers:
  - mm/memcontrol.c:swap_max_show
  - mm/memcontrol.c:memory_stat_show
  - mm/memcontrol.c:memory_events_show
  - mm/memcontrol.c:memory_max_show
  - mm/memcontrol.c:memory_high_show
  - mm/memcontrol.c:memory_low_show
  - mm/memcontrol.c:mem_cgroup_oom_control_read
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
```
```
In security/device_cgroup.c (ffffffff8141d375)
Location: include/linux/cgroup.h:600
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_seq_show
```
```
In block/blk-cgroup.c (ffffffff81473ecc)
Location: include/linux/cgroup.h:600
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-cgroup.c:blkg_print_stat_ios_recursive
  - block/blk-cgroup.c:blkg_print_stat_bytes_recursive
  - block/blk-cgroup.c:blkg_print_stat_ios
  - block/blk-cgroup.c:blkg_print_stat_bytes
```
```
In block/blk-throttle.c (ffffffff8147541e)
Location: include/linux/cgroup.h:600
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_print_limit
  - block/blk-throttle.c:tg_print_conf_uint
  - block/blk-throttle.c:tg_print_conf_u64
```
```
In block/cfq-iosched.c (ffffffff8147b5ff)
Location: include/linux/cgroup.h:600
Inline: True
Inline callers:
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
```
```
In net/core/netprio_cgroup.c (ffffffff81875792)
Location: include/linux/cgroup.h:600
Inline: True
Inline callers:
  - net/core/netprio_cgroup.c:read_priomap
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
In kernel/sched/core.c (ffffffff810ba985)
Location: include/linux/cgroup.h:600
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_max_show
  - kernel/sched/core.c:cpu_cfs_stat_show
```
```
In kernel/sched/cpuacct.c (ffffffff810e2caf)
Location: include/linux/cgroup.h:600
Inline: True
Inline callers:
  - kernel/sched/cpuacct.c:cpuacct_stats_show
  - kernel/sched/cpuacct.c:cpuacct_all_seq_show
  - kernel/sched/cpuacct.c:__cpuacct_percpu_seq_show
```
```
In kernel/cgroup/cgroup.c (ffffffff8113b8a8)
Location: include/linux/cgroup.h:600
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
```
```
In kernel/cgroup/rstat.c (ffffffff811440e8)
Location: include/linux/cgroup.h:600
Inline: True
Inline callers:
  - kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81144f95)
Location: include/linux/cgroup.h:600
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_show
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_stop
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
```
```
In kernel/cgroup/freezer.c (ffffffff811469e5)
Location: include/linux/cgroup.h:600
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:freezer_read
```
```
In kernel/cgroup/pids.c (ffffffff81146b65)
Location: include/linux/cgroup.h:600
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_events_show
```
```
In kernel/cgroup/rdma.c (ffffffff81147225)
Location: include/linux/cgroup.h:600
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_read
```
```
In kernel/cgroup/cpuset.c (ffffffff81148975)
Location: include/linux/cgroup.h:600
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_common_seq_show
```
```
In mm/slab_common.c (ffffffff8121f202)
Location: include/linux/cgroup.h:600
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_slab_show
  - mm/slab_common.c:memcg_slab_next
  - mm/slab_common.c:memcg_slab_start
```
```
In mm/memcontrol.c (ffffffff8127e8e5)
Location: include/linux/cgroup.h:600
Inline: True
Inline callers:
  - mm/memcontrol.c:swap_events_show
  - mm/memcontrol.c:swap_max_show
  - mm/memcontrol.c:memory_stat_show
  - mm/memcontrol.c:memory_events_show
  - mm/memcontrol.c:memory_max_show
  - mm/memcontrol.c:memory_high_show
  - mm/memcontrol.c:memory_low_show
  - mm/memcontrol.c:memory_min_show
  - mm/memcontrol.c:mem_cgroup_oom_control_read
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
```
```
In security/device_cgroup.c (ffffffff8144f648)
Location: include/linux/cgroup.h:600
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_seq_show
```
```
In block/blk-cgroup.c (ffffffff814a83cf)
Location: include/linux/cgroup.h:600
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-cgroup.c:blkg_print_stat_ios_recursive
  - block/blk-cgroup.c:blkg_print_stat_bytes_recursive
  - block/blk-cgroup.c:blkg_print_stat_ios
  - block/blk-cgroup.c:blkg_print_stat_bytes
```
```
In block/blk-throttle.c (ffffffff814a989e)
Location: include/linux/cgroup.h:600
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_print_limit
  - block/blk-throttle.c:tg_print_conf_uint
  - block/blk-throttle.c:tg_print_conf_u64
```
```
In block/cfq-iosched.c (ffffffff814afcd5)
Location: include/linux/cgroup.h:600
Inline: True
Inline callers:
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
```
```
In net/core/netprio_cgroup.c (ffffffff818c6ef2)
Location: include/linux/cgroup.h:600
Inline: True
Inline callers:
  - net/core/netprio_cgroup.c:read_priomap
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
In kernel/sched/core.c (ffffffff810c3ba5)
Location: include/linux/cgroup.h:623
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_max_show
  - kernel/sched/core.c:cpu_cfs_stat_show
```
```
In kernel/sched/cpuacct.c (ffffffff810ed3df)
Location: include/linux/cgroup.h:623
Inline: True
Inline callers:
  - kernel/sched/cpuacct.c:cpuacct_stats_show
  - kernel/sched/cpuacct.c:cpuacct_all_seq_show
  - kernel/sched/cpuacct.c:__cpuacct_percpu_seq_show
```
```
In kernel/cgroup/cgroup.c (ffffffff811470a8)
Location: include/linux/cgroup.h:623
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
```
```
In kernel/cgroup/rstat.c (ffffffff8114fbf8)
Location: include/linux/cgroup.h:623
Inline: True
Inline callers:
  - kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81150ab5)
Location: include/linux/cgroup.h:623
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_show
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_stop
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
```
```
In kernel/cgroup/freezer.c (ffffffff811523f5)
Location: include/linux/cgroup.h:623
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:freezer_read
```
```
In kernel/cgroup/pids.c (ffffffff811526e5)
Location: include/linux/cgroup.h:623
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_events_show
```
```
In kernel/cgroup/rdma.c (ffffffff81152ef5)
Location: include/linux/cgroup.h:623
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_read
```
```
In kernel/cgroup/cpuset.c (ffffffff811538f5)
Location: include/linux/cgroup.h:623
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:sched_partition_show
  - kernel/cgroup/cpuset.c:cpuset_common_seq_show
```
```
In mm/slab_common.c (ffffffff812321f2)
Location: include/linux/cgroup.h:623
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_slab_show
  - mm/slab_common.c:memcg_slab_next
  - mm/slab_common.c:memcg_slab_start
```
```
In mm/memcontrol.c (ffffffff81293075)
Location: include/linux/cgroup.h:623
Inline: True
Inline callers:
  - mm/memcontrol.c:swap_events_show
  - mm/memcontrol.c:swap_max_show
  - mm/memcontrol.c:memory_oom_group_show
  - mm/memcontrol.c:memory_stat_show
  - mm/memcontrol.c:memory_events_show
  - mm/memcontrol.c:memory_max_show
  - mm/memcontrol.c:memory_high_show
  - mm/memcontrol.c:memory_low_show
  - mm/memcontrol.c:memory_min_show
  - mm/memcontrol.c:mem_cgroup_oom_control_read
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
```
```
In security/device_cgroup.c (ffffffff8146c628)
Location: include/linux/cgroup.h:623
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_seq_show
```
```
In block/blk-cgroup.c (ffffffff814c201f)
Location: include/linux/cgroup.h:623
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-cgroup.c:blkg_print_stat_ios_recursive
  - block/blk-cgroup.c:blkg_print_stat_bytes_recursive
  - block/blk-cgroup.c:blkg_print_stat_ios
  - block/blk-cgroup.c:blkg_print_stat_bytes
```
```
In block/blk-throttle.c (ffffffff814c3d0e)
Location: include/linux/cgroup.h:623
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_print_limit
  - block/blk-throttle.c:tg_print_conf_uint
  - block/blk-throttle.c:tg_print_conf_u64
```
```
In net/core/netprio_cgroup.c (ffffffff818f0062)
Location: include/linux/cgroup.h:623
Inline: True
Inline callers:
  - net/core/netprio_cgroup.c:read_priomap
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
In kernel/sched/core.c (ffffffff810c9c95)
Location: include/linux/cgroup.h:636
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_max_show
  - kernel/sched/core.c:cpu_cfs_stat_show
```
```
In kernel/sched/cpuacct.c (ffffffff810f4166)
Location: include/linux/cgroup.h:636
Inline: True
Inline callers:
  - kernel/sched/cpuacct.c:cpuacct_stats_show
  - kernel/sched/cpuacct.c:cpuacct_all_seq_show
  - kernel/sched/cpuacct.c:__cpuacct_percpu_seq_show
```
```
In kernel/cgroup/cgroup.c (ffffffff8115236c)
Location: include/linux/cgroup.h:636
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
```
```
In kernel/cgroup/rstat.c (ffffffff8115baf8)
Location: include/linux/cgroup.h:636
Inline: True
Inline callers:
  - kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8115c9f5)
Location: include/linux/cgroup.h:636
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_show
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_stop
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff8115ea55)
Location: include/linux/cgroup.h:636
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/pids.c (ffffffff8115ed45)
Location: include/linux/cgroup.h:636
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_events_show
```
```
In kernel/cgroup/rdma.c (ffffffff8115f535)
Location: include/linux/cgroup.h:636
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_read
```
```
In kernel/cgroup/cpuset.c (ffffffff8115ff45)
Location: include/linux/cgroup.h:636
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:sched_partition_show
  - kernel/cgroup/cpuset.c:cpuset_common_seq_show
```
```
In mm/slab_common.c (ffffffff812426c2)
Location: include/linux/cgroup.h:636
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_slab_show
  - mm/slab_common.c:memcg_slab_next
  - mm/slab_common.c:memcg_slab_start
```
```
In mm/memcontrol.c (ffffffff812ad955)
Location: include/linux/cgroup.h:636
Inline: True
Inline callers:
  - mm/memcontrol.c:swap_events_show
  - mm/memcontrol.c:swap_max_show
  - mm/memcontrol.c:memory_oom_group_show
  - mm/memcontrol.c:memory_stat_show
  - mm/memcontrol.c:memory_events_local_show
  - mm/memcontrol.c:memory_events_show
  - mm/memcontrol.c:memory_max_show
  - mm/memcontrol.c:memory_high_show
  - mm/memcontrol.c:memory_low_show
  - mm/memcontrol.c:memory_min_show
  - mm/memcontrol.c:mem_cgroup_oom_control_read
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
```
```
In security/device_cgroup.c (ffffffff81499d28)
Location: include/linux/cgroup.h:636
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_seq_show
```
```
In block/blk-cgroup.c (ffffffff814f075c)
Location: include/linux/cgroup.h:636
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-cgroup.c:blkg_print_stat_ios_recursive
  - block/blk-cgroup.c:blkg_print_stat_bytes_recursive
  - block/blk-cgroup.c:blkg_print_stat_ios
  - block/blk-cgroup.c:blkg_print_stat_bytes
```
```
In block/blk-throttle.c (ffffffff814f247e)
Location: include/linux/cgroup.h:636
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_print_limit
  - block/blk-throttle.c:tg_print_conf_uint
  - block/blk-throttle.c:tg_print_conf_u64
```
```
In net/core/netprio_cgroup.c (ffffffff819419d2)
Location: include/linux/cgroup.h:636
Inline: True
Inline callers:
  - net/core/netprio_cgroup.c:read_priomap
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
In kernel/sched/core.c (ffffffff810d2d35)
Location: include/linux/cgroup.h:638
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_max_show
  - kernel/sched/core.c:cpu_cfs_stat_show
  - kernel/sched/core.c:cpu_uclamp_max_show
  - kernel/sched/core.c:cpu_uclamp_min_show
```
```
In kernel/sched/cpuacct.c (ffffffff810ffdf6)
Location: include/linux/cgroup.h:638
Inline: True
Inline callers:
  - kernel/sched/cpuacct.c:cpuacct_stats_show
  - kernel/sched/cpuacct.c:cpuacct_all_seq_show
  - kernel/sched/cpuacct.c:__cpuacct_percpu_seq_show
```
```
In kernel/cgroup/cgroup.c (ffffffff8115dfbc)
Location: include/linux/cgroup.h:638
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
```
```
In kernel/cgroup/rstat.c (ffffffff81167718)
Location: include/linux/cgroup.h:638
Inline: True
Inline callers:
  - kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff811685f5)
Location: include/linux/cgroup.h:638
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_show
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_stop
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff8116a6b5)
Location: include/linux/cgroup.h:638
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/pids.c (ffffffff8116a9a5)
Location: include/linux/cgroup.h:638
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_events_show
```
```
In kernel/cgroup/rdma.c (ffffffff8116b195)
Location: include/linux/cgroup.h:638
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_read
```
```
In kernel/cgroup/cpuset.c (ffffffff8116bc15)
Location: include/linux/cgroup.h:638
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:sched_partition_show
  - kernel/cgroup/cpuset.c:cpuset_common_seq_show
```
```
In mm/slab_common.c (ffffffff81250be2)
Location: include/linux/cgroup.h:638
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_slab_show
  - mm/slab_common.c:memcg_slab_next
  - mm/slab_common.c:memcg_slab_start
```
```
In mm/memcontrol.c (ffffffff812bf4a5)
Location: include/linux/cgroup.h:638
Inline: True
Inline callers:
  - mm/memcontrol.c:swap_events_show
  - mm/memcontrol.c:swap_max_show
  - mm/memcontrol.c:memory_oom_group_show
  - mm/memcontrol.c:memory_stat_show
  - mm/memcontrol.c:memory_events_local_show
  - mm/memcontrol.c:memory_events_show
  - mm/memcontrol.c:memory_max_show
  - mm/memcontrol.c:memory_high_show
  - mm/memcontrol.c:memory_low_show
  - mm/memcontrol.c:memory_min_show
  - mm/memcontrol.c:mem_cgroup_oom_control_read
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
```
```
In security/device_cgroup.c (ffffffff814b3f28)
Location: include/linux/cgroup.h:638
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_seq_show
```
```
In block/blk-cgroup.c (ffffffff81509b4c)
Location: include/linux/cgroup.h:638
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-cgroup.c:blkg_print_stat_ios_recursive
  - block/blk-cgroup.c:blkg_print_stat_bytes_recursive
  - block/blk-cgroup.c:blkg_print_stat_ios
  - block/blk-cgroup.c:blkg_print_stat_bytes
```
```
In block/blk-throttle.c (ffffffff8150b9ee)
Location: include/linux/cgroup.h:638
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_print_limit
  - block/blk-throttle.c:tg_print_conf_uint
  - block/blk-throttle.c:tg_print_conf_u64
```
```
In block/blk-iocost.c (ffffffff81510415)
Location: include/linux/cgroup.h:638
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_cost_model_show
  - block/blk-iocost.c:ioc_qos_show
  - block/blk-iocost.c:ioc_weight_show
```
```
In net/core/netprio_cgroup.c (ffffffff819768e2)
Location: include/linux/cgroup.h:638
Inline: True
Inline callers:
  - net/core/netprio_cgroup.c:read_priomap
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
In kernel/sched/core.c (ffffffff810dc985)
Location: include/linux/cgroup.h:644
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_max_show
  - kernel/sched/core.c:cpu_cfs_stat_show
  - kernel/sched/core.c:cpu_uclamp_max_show
  - kernel/sched/core.c:cpu_uclamp_min_show
```
```
In kernel/sched/cpuacct.c (ffffffff8110a486)
Location: include/linux/cgroup.h:644
Inline: True
Inline callers:
  - kernel/sched/cpuacct.c:cpuacct_stats_show
  - kernel/sched/cpuacct.c:cpuacct_all_seq_show
  - kernel/sched/cpuacct.c:__cpuacct_percpu_seq_show
```
```
In kernel/cgroup/cgroup.c (ffffffff81177239)
Location: include/linux/cgroup.h:644
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
```
```
In kernel/cgroup/rstat.c (ffffffff81178f78)
Location: include/linux/cgroup.h:644
Inline: True
Inline callers:
  - kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8117a305)
Location: include/linux/cgroup.h:644
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_show
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_stop
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff8117c1b5)
Location: include/linux/cgroup.h:644
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/pids.c (ffffffff8117c4e5)
Location: include/linux/cgroup.h:644
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_events_show
```
```
In kernel/cgroup/rdma.c (ffffffff8117cb45)
Location: include/linux/cgroup.h:644
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_read
```
```
In kernel/cgroup/cpuset.c (ffffffff8117d6e5)
Location: include/linux/cgroup.h:644
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:sched_partition_show
  - kernel/cgroup/cpuset.c:cpuset_common_seq_show
```
```
In mm/slab_common.c (ffffffff8127f252)
Location: include/linux/cgroup.h:644
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_slab_show
  - mm/slab_common.c:memcg_slab_next
  - mm/slab_common.c:memcg_slab_start
```
```
In mm/memcontrol.c (ffffffff812f47a5)
Location: include/linux/cgroup.h:644
Inline: True
Inline callers:
  - mm/memcontrol.c:swap_events_show
  - mm/memcontrol.c:swap_max_show
  - mm/memcontrol.c:swap_high_show
  - mm/memcontrol.c:memory_oom_group_show
  - mm/memcontrol.c:memory_stat_show
  - mm/memcontrol.c:memory_events_local_show
  - mm/memcontrol.c:memory_events_show
  - mm/memcontrol.c:memory_max_show
  - mm/memcontrol.c:memory_high_show
  - mm/memcontrol.c:memory_low_show
  - mm/memcontrol.c:memory_min_show
  - mm/memcontrol.c:mem_cgroup_oom_control_read
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
```
```
In mm/hugetlb_cgroup.c (ffffffff812fef2a)
Location: include/linux/cgroup.h:644
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_events_local_show
  - mm/hugetlb_cgroup.c:hugetlb_events_show
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_u64_max
```
```
In security/device_cgroup.c (ffffffff81513b28)
Location: include/linux/cgroup.h:644
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_seq_show
```
```
In block/blk-cgroup.c (ffffffff8156aa15)
Location: include/linux/cgroup.h:644
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_print_stat
```
```
In block/blk-throttle.c (ffffffff8156ce5e)
Location: include/linux/cgroup.h:644
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_print_limit
  - block/blk-throttle.c:tg_print_rwstat_recursive
  - block/blk-throttle.c:tg_print_rwstat
  - block/blk-throttle.c:tg_print_conf_uint
  - block/blk-throttle.c:tg_print_conf_u64
```
```
In block/blk-iocost.c (ffffffff81571735)
Location: include/linux/cgroup.h:644
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_cost_model_show
  - block/blk-iocost.c:ioc_qos_show
  - block/blk-iocost.c:ioc_weight_show
```
```
In net/core/netprio_cgroup.c (ffffffff81a4b622)
Location: include/linux/cgroup.h:644
Inline: True
Inline callers:
  - net/core/netprio_cgroup.c:read_priomap
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
In kernel/sched/core.c (ffffffff810d91f5)
Location: include/linux/cgroup.h:644
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_max_show
  - kernel/sched/core.c:cpu_cfs_stat_show
  - kernel/sched/core.c:cpu_uclamp_max_show
  - kernel/sched/core.c:cpu_uclamp_min_show
```
```
In kernel/sched/cpuacct.c (ffffffff81107396)
Location: include/linux/cgroup.h:644
Inline: True
Inline callers:
  - kernel/sched/cpuacct.c:cpuacct_stats_show
  - kernel/sched/cpuacct.c:cpuacct_all_seq_show
  - kernel/sched/cpuacct.c:__cpuacct_percpu_seq_show
```
```
In kernel/cgroup/cgroup.c (ffffffff81173f1c)
Location: include/linux/cgroup.h:644
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
```
```
In kernel/cgroup/rstat.c (ffffffff81175c88)
Location: include/linux/cgroup.h:644
Inline: True
Inline callers:
  - kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81177075)
Location: include/linux/cgroup.h:644
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_show
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_stop
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff81179005)
Location: include/linux/cgroup.h:644
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/pids.c (ffffffff81179395)
Location: include/linux/cgroup.h:644
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_events_show
```
```
In kernel/cgroup/rdma.c (ffffffff811799a5)
Location: include/linux/cgroup.h:644
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_read
```
```
In kernel/cgroup/cpuset.c (ffffffff8117a535)
Location: include/linux/cgroup.h:644
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:sched_partition_show
  - kernel/cgroup/cpuset.c:cpuset_common_seq_show
```
```
In mm/memcontrol.c (ffffffff81300085)
Location: include/linux/cgroup.h:644
Inline: True
Inline callers:
  - mm/memcontrol.c:swap_events_show
  - mm/memcontrol.c:swap_max_show
  - mm/memcontrol.c:swap_high_show
  - mm/memcontrol.c:memory_oom_group_show
  - mm/memcontrol.c:memory_numa_stat_show
  - mm/memcontrol.c:memory_stat_show
  - mm/memcontrol.c:memory_events_local_show
  - mm/memcontrol.c:memory_events_show
  - mm/memcontrol.c:memory_max_show
  - mm/memcontrol.c:memory_high_show
  - mm/memcontrol.c:memory_low_show
  - mm/memcontrol.c:memory_min_show
  - mm/memcontrol.c:mem_cgroup_oom_control_read
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
```
```
In mm/hugetlb_cgroup.c (ffffffff8130b26a)
Location: include/linux/cgroup.h:644
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_events_local_show
  - mm/hugetlb_cgroup.c:hugetlb_events_show
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_u64_max
```
```
In security/device_cgroup.c (ffffffff81530c78)
Location: include/linux/cgroup.h:644
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_seq_show
```
```
In block/blk-cgroup.c (ffffffff81585465)
Location: include/linux/cgroup.h:644
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-cgroup.c:blkcg_print_stat
```
```
In block/blk-throttle.c (ffffffff815878ce)
Location: include/linux/cgroup.h:644
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_print_limit
  - block/blk-throttle.c:tg_print_rwstat_recursive
  - block/blk-throttle.c:tg_print_rwstat
  - block/blk-throttle.c:tg_print_conf_uint
  - block/blk-throttle.c:tg_print_conf_u64
```
```
In block/blk-iocost.c (ffffffff8158c7f5)
Location: include/linux/cgroup.h:644
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_cost_model_show
  - block/blk-iocost.c:ioc_qos_show
  - block/blk-iocost.c:ioc_weight_show
```
```
In net/core/netprio_cgroup.c (ffffffff81a512a2)
Location: include/linux/cgroup.h:644
Inline: True
Inline callers:
  - net/core/netprio_cgroup.c:read_priomap
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
In kernel/sched/core.c (ffffffff810dab85)
Location: include/linux/cgroup.h:644
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_max_show
  - kernel/sched/core.c:cpu_cfs_stat_show
  - kernel/sched/core.c:cpu_uclamp_max_show
  - kernel/sched/core.c:cpu_uclamp_min_show
```
```
In kernel/sched/cpuacct.c (ffffffff8110945d)
Location: include/linux/cgroup.h:644
Inline: True
Inline callers:
  - kernel/sched/cpuacct.c:cpuacct_stats_show
  - kernel/sched/cpuacct.c:cpuacct_all_seq_show
  - kernel/sched/cpuacct.c:__cpuacct_percpu_seq_show
```
```
In kernel/cgroup/cgroup.c (ffffffff81174aef)
Location: include/linux/cgroup.h:644
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
```
```
In kernel/cgroup/rstat.c (ffffffff81176808)
Location: include/linux/cgroup.h:644
Inline: True
Inline callers:
  - kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81177c05)
Location: include/linux/cgroup.h:644
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_show
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_stop
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff81179b75)
Location: include/linux/cgroup.h:644
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/pids.c (ffffffff81179ef5)
Location: include/linux/cgroup.h:644
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_events_show
```
```
In kernel/cgroup/rdma.c (ffffffff8117a535)
Location: include/linux/cgroup.h:644
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_read
```
```
In kernel/cgroup/cpuset.c (ffffffff8117b0b5)
Location: include/linux/cgroup.h:644
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:sched_partition_show
  - kernel/cgroup/cpuset.c:cpuset_common_seq_show
```
```
In kernel/cgroup/misc.c (ffffffff81180d05)
Location: include/linux/cgroup.h:644
Inline: True
Inline callers:
  - kernel/cgroup/misc.c:misc_cg_current_show
  - kernel/cgroup/misc.c:misc_cg_max_show
```
```
In mm/memcontrol.c (ffffffff81306ec5)
Location: include/linux/cgroup.h:644
Inline: True
Inline callers:
  - mm/memcontrol.c:swap_events_show
  - mm/memcontrol.c:swap_max_show
  - mm/memcontrol.c:swap_high_show
  - mm/memcontrol.c:memory_oom_group_show
  - mm/memcontrol.c:memory_numa_stat_show
  - mm/memcontrol.c:memory_stat_show
  - mm/memcontrol.c:memory_events_local_show
  - mm/memcontrol.c:memory_events_show
  - mm/memcontrol.c:memory_max_show
  - mm/memcontrol.c:memory_high_show
  - mm/memcontrol.c:memory_low_show
  - mm/memcontrol.c:memory_min_show
  - mm/memcontrol.c:mem_cgroup_oom_control_read
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
```
```
In mm/hugetlb_cgroup.c (ffffffff81311eba)
Location: include/linux/cgroup.h:644
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_events_local_show
  - mm/hugetlb_cgroup.c:hugetlb_events_show
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_u64_max
```
```
In security/device_cgroup.c (ffffffff81536e78)
Location: include/linux/cgroup.h:644
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_seq_show
```
```
In block/blk-cgroup.c (ffffffff8158c04b)
Location: include/linux/cgroup.h:644
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-cgroup.c:blkcg_print_stat
```
```
In block/blk-throttle.c (ffffffff8158e71e)
Location: include/linux/cgroup.h:644
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_print_limit
  - block/blk-throttle.c:tg_print_rwstat_recursive
  - block/blk-throttle.c:tg_print_rwstat
  - block/blk-throttle.c:tg_print_conf_uint
  - block/blk-throttle.c:tg_print_conf_u64
```
```
In block/blk-iocost.c (ffffffff81593535)
Location: include/linux/cgroup.h:644
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_cost_model_show
  - block/blk-iocost.c:ioc_qos_show
  - block/blk-iocost.c:ioc_weight_show
```
```
In net/core/netprio_cgroup.c (ffffffff81a36b12)
Location: include/linux/cgroup.h:644
Inline: True
Inline callers:
  - net/core/netprio_cgroup.c:read_priomap
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
In kernel/sched/core.c (ffffffff810ee755)
Location: include/linux/cgroup.h:644
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_max_show
  - kernel/sched/core.c:cpu_cfs_stat_show
  - kernel/sched/core.c:cpu_uclamp_max_show
  - kernel/sched/core.c:cpu_uclamp_min_show
```
```
In kernel/sched/cpuacct.c (ffffffff81127695)
Location: include/linux/cgroup.h:644
Inline: True
Inline callers:
  - kernel/sched/cpuacct.c:cpuacct_stats_show
  - kernel/sched/cpuacct.c:cpuacct_all_seq_show
  - kernel/sched/cpuacct.c:__cpuacct_percpu_seq_show
```
```
In kernel/cgroup/cgroup.c (ffffffff8119bd83)
Location: include/linux/cgroup.h:644
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
```
```
In kernel/cgroup/rstat.c (ffffffff8119e088)
Location: include/linux/cgroup.h:644
Inline: True
Inline callers:
  - kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8119f525)
Location: include/linux/cgroup.h:644
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_show
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_stop
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff811a1495)
Location: include/linux/cgroup.h:644
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/pids.c (ffffffff811a1815)
Location: include/linux/cgroup.h:644
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_events_show
```
```
In kernel/cgroup/rdma.c (ffffffff811a1e75)
Location: include/linux/cgroup.h:644
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_read
```
```
In kernel/cgroup/cpuset.c (ffffffff811a2c25)
Location: include/linux/cgroup.h:644
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:sched_partition_show
  - kernel/cgroup/cpuset.c:cpuset_common_seq_show
```
```
In kernel/cgroup/misc.c (ffffffff811a8b25)
Location: include/linux/cgroup.h:644
Inline: True
Inline callers:
  - kernel/cgroup/misc.c:misc_cg_current_show
  - kernel/cgroup/misc.c:misc_cg_max_show
```
```
In mm/memcontrol.c (ffffffff81350b85)
Location: include/linux/cgroup.h:644
Inline: True
Inline callers:
  - mm/memcontrol.c:swap_events_show
  - mm/memcontrol.c:swap_max_show
  - mm/memcontrol.c:swap_high_show
  - mm/memcontrol.c:memory_oom_group_show
  - mm/memcontrol.c:memory_numa_stat_show
  - mm/memcontrol.c:memory_stat_show
  - mm/memcontrol.c:memory_events_local_show
  - mm/memcontrol.c:memory_events_show
  - mm/memcontrol.c:memory_max_show
  - mm/memcontrol.c:memory_high_show
  - mm/memcontrol.c:memory_low_show
  - mm/memcontrol.c:memory_min_show
  - mm/memcontrol.c:mem_cgroup_oom_control_read
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
```
```
In mm/hugetlb_cgroup.c (ffffffff8135ccae)
Location: include/linux/cgroup.h:644
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_events_local_show
  - mm/hugetlb_cgroup.c:hugetlb_events_show
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_u64_max
```
```
In security/device_cgroup.c (ffffffff815955e8)
Location: include/linux/cgroup.h:644
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_seq_show
```
```
In block/blk-cgroup.c (ffffffff815f1851)
Location: include/linux/cgroup.h:644
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-cgroup.c:blkcg_print_stat
```
```
In block/blk-throttle.c (ffffffff815f448e)
Location: include/linux/cgroup.h:644
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_print_limit
  - block/blk-throttle.c:tg_print_rwstat_recursive
  - block/blk-throttle.c:tg_print_rwstat
  - block/blk-throttle.c:tg_print_conf_uint
  - block/blk-throttle.c:tg_print_conf_u64
```
```
In block/blk-ioprio.c (ffffffff815f94b5)
Location: include/linux/cgroup.h:644
Inline: True
Inline callers:
  - block/blk-ioprio.c:ioprio_show_prio_policy
```
```
In block/blk-iocost.c (ffffffff815fa6c5)
Location: include/linux/cgroup.h:644
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_cost_model_show
  - block/blk-iocost.c:ioc_qos_show
  - block/blk-iocost.c:ioc_weight_show
```
```
In net/core/netprio_cgroup.c (ffffffff81aec852)
Location: include/linux/cgroup.h:644
Inline: True
Inline callers:
  - net/core/netprio_cgroup.c:read_priomap
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
In kernel/sched/core.c (ffffffff8110ada5)
Location: include/linux/cgroup.h:645
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_max_show
  - kernel/sched/core.c:cpu_cfs_stat_show
  - kernel/sched/core.c:cpu_uclamp_max_show
  - kernel/sched/core.c:cpu_uclamp_min_show
```
```
In kernel/sched/build_utility.c (ffffffff8113c6a2)
Location: include/linux/cgroup.h:645
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:cpuacct_stats_show
  - kernel/sched/build_utility.c:cpuacct_stats_show
  - kernel/sched/build_utility.c:cpuacct_all_seq_show
  - kernel/sched/build_utility.c:__cpuacct_percpu_seq_show
```
```
In kernel/cgroup/cgroup.c (ffffffff811cc013)
Location: include/linux/cgroup.h:645
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
```
```
In kernel/cgroup/rstat.c (ffffffff811ce3f8)
Location: include/linux/cgroup.h:645
Inline: True
Inline callers:
  - kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff811cedd5)
Location: include/linux/cgroup.h:645
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_show
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_stop
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff811d1dd5)
Location: include/linux/cgroup.h:645
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/pids.c (ffffffff811d2175)
Location: include/linux/cgroup.h:645
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_events_show
```
```
In kernel/cgroup/rdma.c (ffffffff811d28b5)
Location: include/linux/cgroup.h:645
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_read
```
```
In kernel/cgroup/cpuset.c (ffffffff811d3aa5)
Location: include/linux/cgroup.h:645
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:sched_partition_show
  - kernel/cgroup/cpuset.c:cpuset_common_seq_show
```
```
In kernel/cgroup/misc.c (ffffffff811d9d25)
Location: include/linux/cgroup.h:645
Inline: True
Inline callers:
  - kernel/cgroup/misc.c:misc_events_show
  - kernel/cgroup/misc.c:misc_cg_current_show
  - kernel/cgroup/misc.c:misc_cg_max_show
```
```
In mm/memcontrol.c (ffffffff813c9a75)
Location: include/linux/cgroup.h:645
Inline: True
Inline callers:
  - mm/memcontrol.c:zswap_max_show
  - mm/memcontrol.c:swap_events_show
  - mm/memcontrol.c:swap_max_show
  - mm/memcontrol.c:swap_high_show
  - mm/memcontrol.c:memory_oom_group_show
  - mm/memcontrol.c:memory_numa_stat_show
  - mm/memcontrol.c:memory_stat_show
  - mm/memcontrol.c:memory_events_local_show
  - mm/memcontrol.c:memory_events_show
  - mm/memcontrol.c:memory_max_show
  - mm/memcontrol.c:memory_high_show
  - mm/memcontrol.c:memory_low_show
  - mm/memcontrol.c:memory_min_show
  - mm/memcontrol.c:mem_cgroup_oom_control_read
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
```
```
In mm/hugetlb_cgroup.c (ffffffff813d698e)
Location: include/linux/cgroup.h:645
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_events_local_show
  - mm/hugetlb_cgroup.c:hugetlb_events_show
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_u64_max
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_numa_stat
```
```
In security/device_cgroup.c (ffffffff81637828)
Location: include/linux/cgroup.h:645
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_seq_show
```
```
In block/blk-cgroup.c (ffffffff816a23bb)
Location: include/linux/cgroup.h:645
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-cgroup.c:blkcg_print_stat
```
```
In block/blk-throttle.c (ffffffff816a5e9e)
Location: include/linux/cgroup.h:645
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_print_limit
  - block/blk-throttle.c:tg_print_rwstat_recursive
  - block/blk-throttle.c:tg_print_rwstat
  - block/blk-throttle.c:tg_print_conf_uint
  - block/blk-throttle.c:tg_print_conf_u64
```
```
In block/blk-ioprio.c (ffffffff816ab3d5)
Location: include/linux/cgroup.h:645
Inline: True
Inline callers:
  - block/blk-ioprio.c:ioprio_show_prio_policy
```
```
In block/blk-iocost.c (ffffffff816acb15)
Location: include/linux/cgroup.h:645
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_cost_model_show
  - block/blk-iocost.c:ioc_qos_show
  - block/blk-iocost.c:ioc_weight_show
```
```
In net/core/netprio_cgroup.c (ffffffff81c6f357)
Location: include/linux/cgroup.h:645
Inline: True
Inline callers:
  - net/core/netprio_cgroup.c:read_priomap
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
In kernel/sched/core.c (ffffffff8112fbc5)
Location: include/linux/cgroup.h:585
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_max_show
  - kernel/sched/core.c:cpu_cfs_stat_show
  - kernel/sched/core.c:cpu_uclamp_max_show
  - kernel/sched/core.c:cpu_uclamp_min_show
```
```
In kernel/sched/build_utility.c (ffffffff8116d2ec)
Location: include/linux/cgroup.h:585
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:cpuacct_stats_show
  - kernel/sched/build_utility.c:cpuacct_stats_show
  - kernel/sched/build_utility.c:cpuacct_all_seq_show
  - kernel/sched/build_utility.c:__cpuacct_percpu_seq_show
```
```
In kernel/cgroup/cgroup.c (ffffffff8120f513)
Location: include/linux/cgroup.h:585
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
```
```
In kernel/cgroup/rstat.c (ffffffff81211bea)
Location: include/linux/cgroup.h:585
Inline: True
Inline callers:
  - kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff812126d5)
Location: include/linux/cgroup.h:585
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_show
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_stop
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff81215af5)
Location: include/linux/cgroup.h:585
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/pids.c (ffffffff81215f15)
Location: include/linux/cgroup.h:585
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_events_show
```
```
In kernel/cgroup/rdma.c (ffffffff812167c5)
Location: include/linux/cgroup.h:585
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_read
```
```
In kernel/cgroup/cpuset.c (ffffffff81217785)
Location: include/linux/cgroup.h:585
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:sched_partition_show
  - kernel/cgroup/cpuset.c:cpuset_common_seq_show
```
```
In kernel/cgroup/misc.c (ffffffff8121f245)
Location: include/linux/cgroup.h:585
Inline: True
Inline callers:
  - kernel/cgroup/misc.c:misc_events_show
  - kernel/cgroup/misc.c:misc_cg_current_show
  - kernel/cgroup/misc.c:misc_cg_max_show
```
```
In mm/memcontrol.c (ffffffff8144fe35)
Location: include/linux/cgroup.h:585
Inline: True
Inline callers:
  - mm/memcontrol.c:zswap_max_show
  - mm/memcontrol.c:swap_events_show
  - mm/memcontrol.c:swap_max_show
  - mm/memcontrol.c:swap_high_show
  - mm/memcontrol.c:memory_oom_group_show
  - mm/memcontrol.c:memory_numa_stat_show
  - mm/memcontrol.c:memory_stat_show
  - mm/memcontrol.c:memory_events_local_show
  - mm/memcontrol.c:memory_events_show
  - mm/memcontrol.c:memory_max_show
  - mm/memcontrol.c:memory_high_show
  - mm/memcontrol.c:memory_low_show
  - mm/memcontrol.c:memory_min_show
  - mm/memcontrol.c:mem_cgroup_oom_control_read
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
```
```
In mm/hugetlb_cgroup.c (ffffffff8145d37e)
Location: include/linux/cgroup.h:585
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_events_local_show
  - mm/hugetlb_cgroup.c:hugetlb_events_show
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_u64_max
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_numa_stat
```
```
In security/device_cgroup.c (ffffffff816eebc8)
Location: include/linux/cgroup.h:585
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_seq_show
```
```
In block/blk-cgroup.c (ffffffff81761a45)
Location: include/linux/cgroup.h:585
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-cgroup.c:blkcg_print_stat
```
```
In block/blk-throttle.c (ffffffff81764eae)
Location: include/linux/cgroup.h:585
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_print_limit
  - block/blk-throttle.c:tg_print_rwstat_recursive
  - block/blk-throttle.c:tg_print_rwstat
  - block/blk-throttle.c:tg_print_conf_uint
  - block/blk-throttle.c:tg_print_conf_u64
```
```
In block/blk-ioprio.c (ffffffff81769dc5)
Location: include/linux/cgroup.h:585
Inline: True
Inline callers:
  - block/blk-ioprio.c:ioprio_show_prio_policy
```
```
In block/blk-iocost.c (ffffffff8176b665)
Location: include/linux/cgroup.h:585
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_cost_model_show
  - block/blk-iocost.c:ioc_qos_show
  - block/blk-iocost.c:ioc_weight_show
```
```
In net/core/netprio_cgroup.c (ffffffff81e27157)
Location: include/linux/cgroup.h:585
Inline: True
Inline callers:
  - net/core/netprio_cgroup.c:read_priomap
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
In kernel/sched/core.c (ffffffff8113d635)
Location: include/linux/cgroup.h:584
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_max_show
  - kernel/sched/core.c:cpu_cfs_stat_show
  - kernel/sched/core.c:cpu_uclamp_max_show
  - kernel/sched/core.c:cpu_uclamp_min_show
```
```
In kernel/sched/build_utility.c (ffffffff8117d8ec)
Location: include/linux/cgroup.h:584
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:cpuacct_stats_show
  - kernel/sched/build_utility.c:cpuacct_stats_show
  - kernel/sched/build_utility.c:cpuacct_all_seq_show
  - kernel/sched/build_utility.c:__cpuacct_percpu_seq_show
```
```
In kernel/cgroup/cgroup.c (ffffffff81224f23)
Location: include/linux/cgroup.h:584
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
```
```
In kernel/cgroup/rstat.c (ffffffff8122754a)
Location: include/linux/cgroup.h:584
Inline: True
Inline callers:
  - kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81227fe5)
Location: include/linux/cgroup.h:584
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_show
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_stop
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff8122b425)
Location: include/linux/cgroup.h:584
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/pids.c (ffffffff8122b855)
Location: include/linux/cgroup.h:584
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_events_show
```
```
In kernel/cgroup/rdma.c (ffffffff8122c0b5)
Location: include/linux/cgroup.h:584
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_read
```
```
In kernel/cgroup/cpuset.c (ffffffff8122d0b5)
Location: include/linux/cgroup.h:584
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:sched_partition_show
  - kernel/cgroup/cpuset.c:cpuset_common_seq_show
```
```
In kernel/cgroup/misc.c (ffffffff81235375)
Location: include/linux/cgroup.h:584
Inline: True
Inline callers:
  - kernel/cgroup/misc.c:misc_events_show
  - kernel/cgroup/misc.c:misc_cg_current_show
  - kernel/cgroup/misc.c:misc_cg_max_show
```
```
In mm/memcontrol.c (ffffffff81485745)
Location: include/linux/cgroup.h:584
Inline: True
Inline callers:
  - mm/memcontrol.c:zswap_max_show
  - mm/memcontrol.c:swap_events_show
  - mm/memcontrol.c:swap_max_show
  - mm/memcontrol.c:swap_high_show
  - mm/memcontrol.c:memory_oom_group_show
  - mm/memcontrol.c:memory_numa_stat_show
  - mm/memcontrol.c:memory_stat_show
  - mm/memcontrol.c:memory_events_local_show
  - mm/memcontrol.c:memory_events_show
  - mm/memcontrol.c:memory_max_show
  - mm/memcontrol.c:memory_high_show
  - mm/memcontrol.c:memory_low_show
  - mm/memcontrol.c:memory_min_show
  - mm/memcontrol.c:mem_cgroup_oom_control_read
  - mm/memcontrol.c:memcg_numa_stat_show
```
```
In mm/hugetlb_cgroup.c (ffffffff8149212e)
Location: include/linux/cgroup.h:584
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_events_local_show
  - mm/hugetlb_cgroup.c:hugetlb_events_show
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_u64_max
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_numa_stat
```
```
In security/device_cgroup.c (ffffffff817290c8)
Location: include/linux/cgroup.h:584
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_seq_show
```
```
In block/blk-cgroup.c (ffffffff817a0b95)
Location: include/linux/cgroup.h:584
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-cgroup.c:blkcg_print_stat
```
```
In block/blk-throttle.c (ffffffff817a3f8e)
Location: include/linux/cgroup.h:584
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_print_limit
  - block/blk-throttle.c:tg_print_rwstat_recursive
  - block/blk-throttle.c:tg_print_rwstat
  - block/blk-throttle.c:tg_print_conf_uint
  - block/blk-throttle.c:tg_print_conf_u64
```
```
In block/blk-ioprio.c (ffffffff817a8e15)
Location: include/linux/cgroup.h:584
Inline: True
Inline callers:
  - block/blk-ioprio.c:ioprio_show_prio_policy
```
```
In block/blk-iocost.c (ffffffff817aa765)
Location: include/linux/cgroup.h:584
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_cost_model_show
  - block/blk-iocost.c:ioc_qos_show
  - block/blk-iocost.c:ioc_weight_show
```
```
In net/core/netprio_cgroup.c (ffffffff81e9c6c7)
Location: include/linux/cgroup.h:584
Inline: True
Inline callers:
  - net/core/netprio_cgroup.c:read_priomap
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
In kernel/sched/core.c (ffffffff81148795)
Location: include/linux/cgroup.h:582
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_max_show
  - kernel/sched/core.c:cpu_cfs_local_stat_show
  - kernel/sched/core.c:cpu_cfs_stat_show
  - kernel/sched/core.c:cpu_uclamp_max_show
  - kernel/sched/core.c:cpu_uclamp_min_show
```
```
In kernel/sched/build_utility.c (ffffffff8118b5bc)
Location: include/linux/cgroup.h:582
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:cpuacct_stats_show
  - kernel/sched/build_utility.c:cpuacct_stats_show
  - kernel/sched/build_utility.c:cpuacct_all_seq_show
  - kernel/sched/build_utility.c:__cpuacct_percpu_seq_show
```
```
In kernel/cgroup/cgroup.c (ffffffff8123cc13)
Location: include/linux/cgroup.h:582
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
```
```
In kernel/cgroup/rstat.c (ffffffff8123f35a)
Location: include/linux/cgroup.h:582
Inline: True
Inline callers:
  - kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8123fde5)
Location: include/linux/cgroup.h:582
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_show
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_stop
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff81243415)
Location: include/linux/cgroup.h:582
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/pids.c (ffffffff81243855)
Location: include/linux/cgroup.h:582
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_events_show
```
```
In kernel/cgroup/rdma.c (ffffffff812440e5)
Location: include/linux/cgroup.h:582
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_read
```
```
In kernel/cgroup/cpuset.c (ffffffff81245305)
Location: include/linux/cgroup.h:582
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:sched_partition_show
  - kernel/cgroup/cpuset.c:cpuset_common_seq_show
```
```
In kernel/cgroup/misc.c (ffffffff8124efc5)
Location: include/linux/cgroup.h:582
Inline: True
Inline callers:
  - kernel/cgroup/misc.c:misc_events_show
  - kernel/cgroup/misc.c:misc_cg_current_show
  - kernel/cgroup/misc.c:misc_cg_max_show
```
```
In mm/memcontrol.c (ffffffff814b3e65)
Location: include/linux/cgroup.h:582
Inline: True
Inline callers:
  - mm/memcontrol.c:zswap_writeback_show
  - mm/memcontrol.c:zswap_max_show
  - mm/memcontrol.c:swap_events_show
  - mm/memcontrol.c:swap_max_show
  - mm/memcontrol.c:swap_high_show
  - mm/memcontrol.c:memory_oom_group_show
  - mm/memcontrol.c:memory_numa_stat_show
  - mm/memcontrol.c:memory_stat_show
  - mm/memcontrol.c:memory_events_local_show
  - mm/memcontrol.c:memory_events_show
  - mm/memcontrol.c:memory_max_show
  - mm/memcontrol.c:memory_high_show
  - mm/memcontrol.c:memory_low_show
  - mm/memcontrol.c:memory_min_show
  - mm/memcontrol.c:mem_cgroup_oom_control_read
  - mm/memcontrol.c:memcg_numa_stat_show
```
```
In mm/hugetlb_cgroup.c (ffffffff814c1b3e)
Location: include/linux/cgroup.h:582
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_events_local_show
  - mm/hugetlb_cgroup.c:hugetlb_events_show
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_u64_max
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_numa_stat
```
```
In security/device_cgroup.c (ffffffff8176a428)
Location: include/linux/cgroup.h:582
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_seq_show
```
```
In block/blk-cgroup.c (ffffffff817e46f5)
Location: include/linux/cgroup.h:582
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-cgroup.c:blkcg_print_stat
```
```
In block/blk-throttle.c (ffffffff817e7b5e)
Location: include/linux/cgroup.h:582
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_print_limit
  - block/blk-throttle.c:tg_print_rwstat_recursive
  - block/blk-throttle.c:tg_print_rwstat
  - block/blk-throttle.c:tg_print_conf_uint
  - block/blk-throttle.c:tg_print_conf_u64
```
```
In block/blk-ioprio.c (ffffffff817ecba5)
Location: include/linux/cgroup.h:582
Inline: True
Inline callers:
  - block/blk-ioprio.c:ioprio_show_prio_policy
```
```
In block/blk-iocost.c (ffffffff817ee515)
Location: include/linux/cgroup.h:582
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_cost_model_show
  - block/blk-iocost.c:ioc_qos_show
  - block/blk-iocost.c:ioc_weight_show
```
```
In net/core/netprio_cgroup.c (ffffffff81f5ee5a)
Location: include/linux/cgroup.h:582
Inline: True
Inline callers:
  - net/core/netprio_cgroup.c:read_priomap
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
In kernel/sched/core.c (ffff800010133000)
Location: include/linux/cgroup.h:638
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_max_show
  - kernel/sched/core.c:cpu_cfs_stat_show
  - kernel/sched/core.c:cpu_uclamp_max_show
  - kernel/sched/core.c:cpu_uclamp_min_show
```
```
In kernel/sched/cpuacct.c (ffff8000101642d8)
Location: include/linux/cgroup.h:638
Inline: True
Inline callers:
  - kernel/sched/cpuacct.c:cpuacct_stats_show
  - kernel/sched/cpuacct.c:cpuacct_all_seq_show
  - kernel/sched/cpuacct.c:__cpuacct_percpu_seq_show
```
```
In kernel/cgroup/cgroup.c (ffff8000101ce6f8)
Location: include/linux/cgroup.h:638
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
```
```
In kernel/cgroup/rstat.c (ffff8000101d9ddc)
Location: include/linux/cgroup.h:638
Inline: True
Inline callers:
  - kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show
```
```
In kernel/cgroup/cgroup-v1.c (ffff8000101db064)
Location: include/linux/cgroup.h:638
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_show
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_stop
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
```
```
In kernel/cgroup/legacy_freezer.c (ffff8000101de3d0)
Location: include/linux/cgroup.h:638
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/pids.c (ffff8000101dea08)
Location: include/linux/cgroup.h:638
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_events_show
```
```
In kernel/cgroup/rdma.c (ffff8000101df400)
Location: include/linux/cgroup.h:638
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_read
```
```
In kernel/cgroup/cpuset.c (ffff8000101dfff0)
Location: include/linux/cgroup.h:638
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:sched_partition_show
  - kernel/cgroup/cpuset.c:cpuset_common_seq_show
```
```
In mm/slab_common.c (ffff8000102e7e54)
Location: include/linux/cgroup.h:638
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_slab_show
  - mm/slab_common.c:memcg_slab_next
  - mm/slab_common.c:memcg_slab_start
```
```
In mm/memcontrol.c (ffff8000103612e0)
Location: include/linux/cgroup.h:638
Inline: True
Inline callers:
  - mm/memcontrol.c:swap_events_show
  - mm/memcontrol.c:swap_max_show
  - mm/memcontrol.c:memory_oom_group_show
  - mm/memcontrol.c:memory_stat_show
  - mm/memcontrol.c:memory_events_local_show
  - mm/memcontrol.c:memory_events_show
  - mm/memcontrol.c:memory_max_show
  - mm/memcontrol.c:memory_high_show
  - mm/memcontrol.c:memory_low_show
  - mm/memcontrol.c:memory_min_show
  - mm/memcontrol.c:mem_cgroup_oom_control_read
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
```
```
In security/device_cgroup.c (ffff8000105abe64)
Location: include/linux/cgroup.h:638
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_seq_show
```
```
In block/blk-cgroup.c (ffff80001060c9b8)
Location: include/linux/cgroup.h:638
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-cgroup.c:blkg_print_stat_ios_recursive
  - block/blk-cgroup.c:blkg_print_stat_bytes_recursive
  - block/blk-cgroup.c:blkg_print_stat_ios
  - block/blk-cgroup.c:blkg_print_stat_bytes
```
```
In block/blk-throttle.c (ffff80001060f630)
Location: include/linux/cgroup.h:638
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_print_limit
  - block/blk-throttle.c:tg_print_conf_uint
  - block/blk-throttle.c:tg_print_conf_u64
```
```
In block/blk-iocost.c (ffff800010613be8)
Location: include/linux/cgroup.h:638
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_cost_model_show
  - block/blk-iocost.c:ioc_qos_show
  - block/blk-iocost.c:ioc_weight_show
```
```
In net/core/netprio_cgroup.c (ffff800010c1cf78)
Location: include/linux/cgroup.h:638
Inline: True
Inline callers:
  - net/core/netprio_cgroup.c:read_priomap
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
In kernel/sched/core.c (c03835cc)
Location: include/linux/cgroup.h:638
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_max_show
  - kernel/sched/core.c:cpu_cfs_stat_show
  - kernel/sched/core.c:cpu_uclamp_max_show
  - kernel/sched/core.c:cpu_uclamp_min_show
```
```
In kernel/sched/cpuacct.c (c03b0814)
Location: include/linux/cgroup.h:638
Inline: True
Inline callers:
  - kernel/sched/cpuacct.c:cpuacct_stats_show
  - kernel/sched/cpuacct.c:cpuacct_all_seq_show
  - kernel/sched/cpuacct.c:__cpuacct_percpu_seq_show
```
```
In kernel/cgroup/cgroup.c (c041a984)
Location: include/linux/cgroup.h:638
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
```
```
In kernel/cgroup/rstat.c (c041c750)
Location: include/linux/cgroup.h:638
Inline: True
Inline callers:
  - kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show
```
```
In kernel/cgroup/cgroup-v1.c (c041cef4)
Location: include/linux/cgroup.h:638
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_show
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_stop
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
```
```
In kernel/cgroup/legacy_freezer.c (c041fef0)
Location: include/linux/cgroup.h:638
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/pids.c (c04203a8)
Location: include/linux/cgroup.h:638
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_events_show
```
```
In kernel/cgroup/rdma.c (c0420d10)
Location: include/linux/cgroup.h:638
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_read
```
```
In kernel/cgroup/cpuset.c (c0421b18)
Location: include/linux/cgroup.h:638
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:sched_partition_show
  - kernel/cgroup/cpuset.c:cpuset_common_seq_show
```
```
In mm/slab_common.c (c050bf0c)
Location: include/linux/cgroup.h:638
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_slab_show
  - mm/slab_common.c:memcg_slab_next
  - mm/slab_common.c:memcg_slab_start
```
```
In mm/memcontrol.c (c05538a4)
Location: include/linux/cgroup.h:638
Inline: True
Inline callers:
  - mm/memcontrol.c:swap_events_show
  - mm/memcontrol.c:swap_max_show
  - mm/memcontrol.c:memory_oom_group_show
  - mm/memcontrol.c:memory_stat_show
  - mm/memcontrol.c:memory_events_local_show
  - mm/memcontrol.c:memory_events_show
  - mm/memcontrol.c:memory_max_show
  - mm/memcontrol.c:memory_high_show
  - mm/memcontrol.c:memory_low_show
  - mm/memcontrol.c:memory_min_show
  - mm/memcontrol.c:mem_cgroup_oom_control_read
  - mm/memcontrol.c:memcg_stat_show
```
```
In security/device_cgroup.c (c075b940)
Location: include/linux/cgroup.h:638
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_seq_show
```
```
In block/blk-cgroup.c (c07b74cc)
Location: include/linux/cgroup.h:638
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-cgroup.c:blkg_print_stat_ios_recursive
  - block/blk-cgroup.c:blkg_print_stat_bytes_recursive
  - block/blk-cgroup.c:blkg_print_stat_ios
  - block/blk-cgroup.c:blkg_print_stat_bytes
```
```
In block/blk-throttle.c (c07b9cd4)
Location: include/linux/cgroup.h:638
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_print_limit
  - block/blk-throttle.c:tg_print_conf_uint
  - block/blk-throttle.c:tg_print_conf_u64
```
```
In block/blk-iocost.c (c07bf41c)
Location: include/linux/cgroup.h:638
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_cost_model_show
  - block/blk-iocost.c:ioc_qos_show
  - block/blk-iocost.c:ioc_weight_show
```
```
In net/core/netprio_cgroup.c (c0d34e20)
Location: include/linux/cgroup.h:638
Inline: True
Inline callers:
  - net/core/netprio_cgroup.c:read_priomap
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
In kernel/sched/core.c (c00000000017de14)
Location: include/linux/cgroup.h:638
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_max_show
  - kernel/sched/core.c:cpu_cfs_stat_show
  - kernel/sched/core.c:cpu_uclamp_max_show
  - kernel/sched/core.c:cpu_uclamp_min_show
```
```
In kernel/sched/cpuacct.c (c0000000001bb100)
Location: include/linux/cgroup.h:638
Inline: True
Inline callers:
  - kernel/sched/cpuacct.c:cpuacct_stats_show
  - kernel/sched/cpuacct.c:cpuacct_all_seq_show
  - kernel/sched/cpuacct.c:__cpuacct_percpu_seq_show
```
```
In kernel/cgroup/cgroup.c (c0000000002385b8)
Location: include/linux/cgroup.h:638
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
```
```
In kernel/cgroup/rstat.c (c000000000247008)
Location: include/linux/cgroup.h:638
Inline: True
Inline callers:
  - kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show
```
```
In kernel/cgroup/cgroup-v1.c (c0000000002479a4)
Location: include/linux/cgroup.h:638
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_show
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_stop
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
```
```
In kernel/cgroup/legacy_freezer.c (c00000000024c20c)
Location: include/linux/cgroup.h:638
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/pids.c (c00000000024c9d0)
Location: include/linux/cgroup.h:638
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_events_show
```
```
In kernel/cgroup/rdma.c (c00000000024d59c)
Location: include/linux/cgroup.h:638
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_read
```
```
In kernel/cgroup/cpuset.c (c00000000024eb10)
Location: include/linux/cgroup.h:638
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:sched_partition_show
  - kernel/cgroup/cpuset.c:cpuset_common_seq_show
```
```
In mm/slab_common.c (c0000000003a9e38)
Location: include/linux/cgroup.h:638
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_slab_show
  - mm/slab_common.c:memcg_slab_next
  - mm/slab_common.c:memcg_slab_start
```
```
In mm/memcontrol.c (c00000000044c6c4)
Location: include/linux/cgroup.h:638
Inline: True
Inline callers:
  - mm/memcontrol.c:swap_events_show
  - mm/memcontrol.c:swap_max_show
  - mm/memcontrol.c:memory_oom_group_show
  - mm/memcontrol.c:memory_stat_show
  - mm/memcontrol.c:memory_events_local_show
  - mm/memcontrol.c:memory_events_show
  - mm/memcontrol.c:memory_max_show
  - mm/memcontrol.c:memory_high_show
  - mm/memcontrol.c:memory_low_show
  - mm/memcontrol.c:memory_min_show
  - mm/memcontrol.c:mem_cgroup_oom_control_read
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
```
```
In security/device_cgroup.c (c00000000072a014)
Location: include/linux/cgroup.h:638
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_seq_show
```
```
In block/blk-cgroup.c (c0000000007a99d8)
Location: include/linux/cgroup.h:638
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-cgroup.c:blkg_print_stat_ios_recursive
  - block/blk-cgroup.c:blkg_print_stat_bytes_recursive
  - block/blk-cgroup.c:blkg_print_stat_ios
  - block/blk-cgroup.c:blkg_print_stat_bytes
```
```
In block/blk-throttle.c (c0000000007aca20)
Location: include/linux/cgroup.h:638
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_print_limit
  - block/blk-throttle.c:tg_print_conf_uint
  - block/blk-throttle.c:tg_print_conf_u64
```
```
In block/blk-iocost.c (c0000000007b2f20)
Location: include/linux/cgroup.h:638
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_cost_model_show
  - block/blk-iocost.c:ioc_qos_show
  - block/blk-iocost.c:ioc_weight_show
```
```
In net/core/netprio_cgroup.c (c000000000d0dfb0)
Location: include/linux/cgroup.h:638
Inline: True
Inline callers:
  - net/core/netprio_cgroup.c:read_priomap
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
In kernel/sched/core.c (ffffffe0000e5d44)
Location: include/linux/cgroup.h:638
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_max_show
  - kernel/sched/core.c:cpu_cfs_stat_show
```
```
In kernel/sched/cpuacct.c (ffffffe000107bc6)
Location: include/linux/cgroup.h:638
Inline: True
Inline callers:
  - kernel/sched/cpuacct.c:cpuacct_stats_show
  - kernel/sched/cpuacct.c:cpuacct_all_seq_show
  - kernel/sched/cpuacct.c:__cpuacct_percpu_seq_show
```
```
In kernel/cgroup/cgroup.c (ffffffe00014903e)
Location: include/linux/cgroup.h:638
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
```
```
In kernel/cgroup/rstat.c (ffffffe0001526b4)
Location: include/linux/cgroup.h:638
Inline: True
Inline callers:
  - kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show
```
```
In kernel/cgroup/cgroup-v1.c (ffffffe0001536ba)
Location: include/linux/cgroup.h:638
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_show
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_stop
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
```
```
In kernel/cgroup/legacy_freezer.c (ffffffe000155990)
Location: include/linux/cgroup.h:638
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/pids.c (ffffffe000155cf2)
Location: include/linux/cgroup.h:638
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_events_show
```
```
In kernel/cgroup/rdma.c (ffffffe0001564ea)
Location: include/linux/cgroup.h:638
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_read
```
```
In kernel/cgroup/cpuset.c (ffffffe000156ee0)
Location: include/linux/cgroup.h:638
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:sched_partition_show
  - kernel/cgroup/cpuset.c:cpuset_common_seq_show
```
```
In mm/slab_common.c (ffffffe0001fd912)
Location: include/linux/cgroup.h:638
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_slab_show
  - mm/slab_common.c:memcg_slab_next
  - mm/slab_common.c:memcg_slab_start
```
```
In mm/memcontrol.c (ffffffe000240a64)
Location: include/linux/cgroup.h:638
Inline: True
Inline callers:
  - mm/memcontrol.c:swap_events_show
  - mm/memcontrol.c:swap_max_show
  - mm/memcontrol.c:memory_oom_group_show
  - mm/memcontrol.c:memory_stat_show
  - mm/memcontrol.c:memory_events_local_show
  - mm/memcontrol.c:memory_events_show
  - mm/memcontrol.c:memory_max_show
  - mm/memcontrol.c:memory_high_show
  - mm/memcontrol.c:memory_low_show
  - mm/memcontrol.c:memory_min_show
  - mm/memcontrol.c:mem_cgroup_oom_control_read
  - mm/memcontrol.c:memcg_stat_show
```
```
In security/device_cgroup.c (ffffffe0003f4d76)
Location: include/linux/cgroup.h:638
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_seq_show
```
```
In block/blk-cgroup.c (ffffffe000445606)
Location: include/linux/cgroup.h:638
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-cgroup.c:blkg_print_stat_ios_recursive
  - block/blk-cgroup.c:blkg_print_stat_bytes_recursive
  - block/blk-cgroup.c:blkg_print_stat_ios
  - block/blk-cgroup.c:blkg_print_stat_bytes
```
```
In block/blk-throttle.c (ffffffe0004474ee)
Location: include/linux/cgroup.h:638
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_print_limit
  - block/blk-throttle.c:tg_print_conf_uint
  - block/blk-throttle.c:tg_print_conf_u64
```
```
In block/blk-iocost.c (ffffffe00044b5a8)
Location: include/linux/cgroup.h:638
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_cost_model_show
  - block/blk-iocost.c:ioc_qos_show
  - block/blk-iocost.c:ioc_weight_show
```
```
In net/core/netprio_cgroup.c (ffffffe000796cfe)
Location: include/linux/cgroup.h:638
Inline: True
Inline callers:
  - net/core/netprio_cgroup.c:read_priomap
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
In kernel/sched/core.c (ffffffff810cd0b5)
Location: include/linux/cgroup.h:638
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_max_show
  - kernel/sched/core.c:cpu_cfs_stat_show
  - kernel/sched/core.c:cpu_uclamp_max_show
  - kernel/sched/core.c:cpu_uclamp_min_show
```
```
In kernel/sched/cpuacct.c (ffffffff810f9106)
Location: include/linux/cgroup.h:638
Inline: True
Inline callers:
  - kernel/sched/cpuacct.c:cpuacct_stats_show
  - kernel/sched/cpuacct.c:cpuacct_all_seq_show
  - kernel/sched/cpuacct.c:__cpuacct_percpu_seq_show
```
```
In kernel/cgroup/cgroup.c (ffffffff811565dc)
Location: include/linux/cgroup.h:638
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
```
```
In kernel/cgroup/rstat.c (ffffffff8115fd38)
Location: include/linux/cgroup.h:638
Inline: True
Inline callers:
  - kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81160c15)
Location: include/linux/cgroup.h:638
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_show
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_stop
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff81162cd5)
Location: include/linux/cgroup.h:638
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/pids.c (ffffffff81162fc5)
Location: include/linux/cgroup.h:638
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_events_show
```
```
In kernel/cgroup/rdma.c (ffffffff811637b5)
Location: include/linux/cgroup.h:638
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_read
```
```
In kernel/cgroup/cpuset.c (ffffffff81164235)
Location: include/linux/cgroup.h:638
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:sched_partition_show
  - kernel/cgroup/cpuset.c:cpuset_common_seq_show
```
```
In mm/slab_common.c (ffffffff81249232)
Location: include/linux/cgroup.h:638
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_slab_show
  - mm/slab_common.c:memcg_slab_next
  - mm/slab_common.c:memcg_slab_start
```
```
In mm/memcontrol.c (ffffffff812b7a85)
Location: include/linux/cgroup.h:638
Inline: True
Inline callers:
  - mm/memcontrol.c:swap_events_show
  - mm/memcontrol.c:swap_max_show
  - mm/memcontrol.c:memory_oom_group_show
  - mm/memcontrol.c:memory_stat_show
  - mm/memcontrol.c:memory_events_local_show
  - mm/memcontrol.c:memory_events_show
  - mm/memcontrol.c:memory_max_show
  - mm/memcontrol.c:memory_high_show
  - mm/memcontrol.c:memory_low_show
  - mm/memcontrol.c:memory_min_show
  - mm/memcontrol.c:mem_cgroup_oom_control_read
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
```
```
In security/device_cgroup.c (ffffffff814ac508)
Location: include/linux/cgroup.h:638
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_seq_show
```
```
In block/blk-cgroup.c (ffffffff8150212c)
Location: include/linux/cgroup.h:638
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-cgroup.c:blkg_print_stat_ios_recursive
  - block/blk-cgroup.c:blkg_print_stat_bytes_recursive
  - block/blk-cgroup.c:blkg_print_stat_ios
  - block/blk-cgroup.c:blkg_print_stat_bytes
```
```
In block/blk-throttle.c (ffffffff81503fce)
Location: include/linux/cgroup.h:638
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_print_limit
  - block/blk-throttle.c:tg_print_conf_uint
  - block/blk-throttle.c:tg_print_conf_u64
```
```
In block/blk-iocost.c (ffffffff815089f5)
Location: include/linux/cgroup.h:638
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_cost_model_show
  - block/blk-iocost.c:ioc_qos_show
  - block/blk-iocost.c:ioc_weight_show
```
```
In net/core/netprio_cgroup.c (ffffffff81916752)
Location: include/linux/cgroup.h:638
Inline: True
Inline callers:
  - net/core/netprio_cgroup.c:read_priomap
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
In kernel/sched/core.c (ffffffff810bb8b5)
Location: include/linux/cgroup.h:638
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_max_show
  - kernel/sched/core.c:cpu_cfs_stat_show
  - kernel/sched/core.c:cpu_uclamp_max_show
  - kernel/sched/core.c:cpu_uclamp_min_show
```
```
In kernel/sched/cpuacct.c (ffffffff810e92e6)
Location: include/linux/cgroup.h:638
Inline: True
Inline callers:
  - kernel/sched/cpuacct.c:cpuacct_stats_show
  - kernel/sched/cpuacct.c:cpuacct_all_seq_show
  - kernel/sched/cpuacct.c:__cpuacct_percpu_seq_show
```
```
In kernel/cgroup/cgroup.c (ffffffff811498fc)
Location: include/linux/cgroup.h:638
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
```
```
In kernel/cgroup/rstat.c (ffffffff81152fb8)
Location: include/linux/cgroup.h:638
Inline: True
Inline callers:
  - kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81153e85)
Location: include/linux/cgroup.h:638
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_show
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_stop
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff81155f25)
Location: include/linux/cgroup.h:638
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/pids.c (ffffffff81156215)
Location: include/linux/cgroup.h:638
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_events_show
```
```
In kernel/cgroup/rdma.c (ffffffff81156a05)
Location: include/linux/cgroup.h:638
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_read
```
```
In kernel/cgroup/cpuset.c (ffffffff81157485)
Location: include/linux/cgroup.h:638
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:sched_partition_show
  - kernel/cgroup/cpuset.c:cpuset_common_seq_show
```
```
In mm/slab_common.c (ffffffff8123c1e2)
Location: include/linux/cgroup.h:638
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_slab_show
  - mm/slab_common.c:memcg_slab_next
  - mm/slab_common.c:memcg_slab_start
```
```
In mm/memcontrol.c (ffffffff812a8c55)
Location: include/linux/cgroup.h:638
Inline: True
Inline callers:
  - mm/memcontrol.c:swap_events_show
  - mm/memcontrol.c:swap_max_show
  - mm/memcontrol.c:memory_oom_group_show
  - mm/memcontrol.c:memory_stat_show
  - mm/memcontrol.c:memory_events_local_show
  - mm/memcontrol.c:memory_events_show
  - mm/memcontrol.c:memory_max_show
  - mm/memcontrol.c:memory_high_show
  - mm/memcontrol.c:memory_low_show
  - mm/memcontrol.c:memory_min_show
  - mm/memcontrol.c:mem_cgroup_oom_control_read
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
```
```
In security/device_cgroup.c (ffffffff8149cf28)
Location: include/linux/cgroup.h:638
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_seq_show
```
```
In block/blk-cgroup.c (ffffffff814f266c)
Location: include/linux/cgroup.h:638
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-cgroup.c:blkg_print_stat_ios_recursive
  - block/blk-cgroup.c:blkg_print_stat_bytes_recursive
  - block/blk-cgroup.c:blkg_print_stat_ios
  - block/blk-cgroup.c:blkg_print_stat_bytes
```
```
In block/blk-throttle.c (ffffffff814f448e)
Location: include/linux/cgroup.h:638
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_print_limit
  - block/blk-throttle.c:tg_print_conf_uint
  - block/blk-throttle.c:tg_print_conf_u64
```
```
In block/blk-iocost.c (ffffffff814f8ea5)
Location: include/linux/cgroup.h:638
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_cost_model_show
  - block/blk-iocost.c:ioc_qos_show
  - block/blk-iocost.c:ioc_weight_show
```
```
In net/core/netprio_cgroup.c (ffffffff818d0502)
Location: include/linux/cgroup.h:638
Inline: True
Inline callers:
  - net/core/netprio_cgroup.c:read_priomap
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
In kernel/sched/core.c (ffffffff810cc6a5)
Location: include/linux/cgroup.h:638
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_max_show
  - kernel/sched/core.c:cpu_cfs_stat_show
```
```
In kernel/sched/cpuacct.c (ffffffff810f6326)
Location: include/linux/cgroup.h:638
Inline: True
Inline callers:
  - kernel/sched/cpuacct.c:cpuacct_stats_show
  - kernel/sched/cpuacct.c:cpuacct_all_seq_show
  - kernel/sched/cpuacct.c:__cpuacct_percpu_seq_show
```
```
In kernel/cgroup/cgroup.c (ffffffff811543ac)
Location: include/linux/cgroup.h:638
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
```
```
In kernel/cgroup/rstat.c (ffffffff8115db08)
Location: include/linux/cgroup.h:638
Inline: True
Inline callers:
  - kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8115e9e5)
Location: include/linux/cgroup.h:638
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_show
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_stop
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff81160aa5)
Location: include/linux/cgroup.h:638
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/pids.c (ffffffff81160d95)
Location: include/linux/cgroup.h:638
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_events_show
```
```
In kernel/cgroup/rdma.c (ffffffff81161585)
Location: include/linux/cgroup.h:638
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_read
```
```
In kernel/cgroup/cpuset.c (ffffffff81162005)
Location: include/linux/cgroup.h:638
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:sched_partition_show
  - kernel/cgroup/cpuset.c:cpuset_common_seq_show
```
```
In mm/slab_common.c (ffffffff81246fd2)
Location: include/linux/cgroup.h:638
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_slab_show
  - mm/slab_common.c:memcg_slab_next
  - mm/slab_common.c:memcg_slab_start
```
```
In mm/memcontrol.c (ffffffff812b5895)
Location: include/linux/cgroup.h:638
Inline: True
Inline callers:
  - mm/memcontrol.c:swap_events_show
  - mm/memcontrol.c:swap_max_show
  - mm/memcontrol.c:memory_oom_group_show
  - mm/memcontrol.c:memory_stat_show
  - mm/memcontrol.c:memory_events_local_show
  - mm/memcontrol.c:memory_events_show
  - mm/memcontrol.c:memory_max_show
  - mm/memcontrol.c:memory_high_show
  - mm/memcontrol.c:memory_low_show
  - mm/memcontrol.c:memory_min_show
  - mm/memcontrol.c:mem_cgroup_oom_control_read
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
```
```
In security/device_cgroup.c (ffffffff814a85a8)
Location: include/linux/cgroup.h:638
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_seq_show
```
```
In block/blk-cgroup.c (ffffffff814fe1bc)
Location: include/linux/cgroup.h:638
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-cgroup.c:blkg_print_stat_ios_recursive
  - block/blk-cgroup.c:blkg_print_stat_bytes_recursive
  - block/blk-cgroup.c:blkg_print_stat_ios
  - block/blk-cgroup.c:blkg_print_stat_bytes
```
```
In block/blk-throttle.c (ffffffff8150005e)
Location: include/linux/cgroup.h:638
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_print_limit
  - block/blk-throttle.c:tg_print_conf_uint
  - block/blk-throttle.c:tg_print_conf_u64
```
```
In block/blk-iocost.c (ffffffff81504a85)
Location: include/linux/cgroup.h:638
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_cost_model_show
  - block/blk-iocost.c:ioc_qos_show
  - block/blk-iocost.c:ioc_weight_show
```
```
In net/core/netprio_cgroup.c (ffffffff819678e2)
Location: include/linux/cgroup.h:638
Inline: True
Inline callers:
  - net/core/netprio_cgroup.c:read_priomap
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
In kernel/sched/core.c (ffffffff810d4e85)
Location: include/linux/cgroup.h:638
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_max_show
  - kernel/sched/core.c:cpu_cfs_stat_show
  - kernel/sched/core.c:cpu_uclamp_max_show
  - kernel/sched/core.c:cpu_uclamp_min_show
```
```
In kernel/sched/cpuacct.c (ffffffff81101346)
Location: include/linux/cgroup.h:638
Inline: True
Inline callers:
  - kernel/sched/cpuacct.c:cpuacct_stats_show
  - kernel/sched/cpuacct.c:cpuacct_all_seq_show
  - kernel/sched/cpuacct.c:__cpuacct_percpu_seq_show
```
```
In kernel/cgroup/cgroup.c (ffffffff811612ac)
Location: include/linux/cgroup.h:638
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
```
```
In kernel/cgroup/rstat.c (ffffffff8116ad68)
Location: include/linux/cgroup.h:638
Inline: True
Inline callers:
  - kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8116b3d5)
Location: include/linux/cgroup.h:638
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_show
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_stop
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff8116de25)
Location: include/linux/cgroup.h:638
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/pids.c (ffffffff8116e1e5)
Location: include/linux/cgroup.h:638
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_events_show
```
```
In kernel/cgroup/rdma.c (ffffffff8116e9d5)
Location: include/linux/cgroup.h:638
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_read
```
```
In kernel/cgroup/cpuset.c (ffffffff8116f585)
Location: include/linux/cgroup.h:638
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:sched_partition_show
  - kernel/cgroup/cpuset.c:cpuset_common_seq_show
```
```
In mm/slab_common.c (ffffffff81256802)
Location: include/linux/cgroup.h:638
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_slab_show
  - mm/slab_common.c:memcg_slab_next
  - mm/slab_common.c:memcg_slab_start
```
```
In mm/memcontrol.c (ffffffff812c5db5)
Location: include/linux/cgroup.h:638
Inline: True
Inline callers:
  - mm/memcontrol.c:swap_events_show
  - mm/memcontrol.c:swap_max_show
  - mm/memcontrol.c:memory_oom_group_show
  - mm/memcontrol.c:memory_stat_show
  - mm/memcontrol.c:memory_events_local_show
  - mm/memcontrol.c:memory_events_show
  - mm/memcontrol.c:memory_max_show
  - mm/memcontrol.c:memory_high_show
  - mm/memcontrol.c:memory_low_show
  - mm/memcontrol.c:memory_min_show
  - mm/memcontrol.c:mem_cgroup_oom_control_read
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
```
```
In security/device_cgroup.c (ffffffff814c0f58)
Location: include/linux/cgroup.h:638
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_seq_show
```
```
In block/blk-cgroup.c (ffffffff8151723c)
Location: include/linux/cgroup.h:638
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-cgroup.c:blkg_print_stat_ios_recursive
  - block/blk-cgroup.c:blkg_print_stat_bytes_recursive
  - block/blk-cgroup.c:blkg_print_stat_ios
  - block/blk-cgroup.c:blkg_print_stat_bytes
```
```
In block/blk-throttle.c (ffffffff8151922e)
Location: include/linux/cgroup.h:638
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_print_limit
  - block/blk-throttle.c:tg_print_conf_uint
  - block/blk-throttle.c:tg_print_conf_u64
```
```
In block/blk-iocost.c (ffffffff8151e0a5)
Location: include/linux/cgroup.h:638
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_cost_model_show
  - block/blk-iocost.c:ioc_qos_show
  - block/blk-iocost.c:ioc_weight_show
```
```
In net/core/netprio_cgroup.c (ffffffff81989b77)
Location: include/linux/cgroup.h:638
Inline: True
Inline callers:
  - net/core/netprio_cgroup.c:read_priomap
```
</details>
</li>
</ul>

## Differences
