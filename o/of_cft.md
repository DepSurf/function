# Function: <code>of_cft</code>

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
In kernel/cgroup.c (ffffffff81111e80)
Location: include/linux/cgroup.h:492
Inline: True
Inline callers:
  - kernel/cgroup.c:cgroup_seqfile_start
  - kernel/cgroup.c:cgroup_seqfile_next
  - kernel/cgroup.c:cgroup_seqfile_stop
  - kernel/cgroup.c:cgroup_seqfile_show
  - kernel/cgroup.c:cgroup_pidlist_start
```
```
In kernel/cpuset.c (ffffffff8111bf1e)
Location: include/linux/cgroup.h:492
Inline: True
Inline callers:
  - kernel/cpuset.c:cpuset_common_seq_show
  - kernel/cpuset.c:cpuset_write_resmask
```
```
In mm/memcontrol.c (ffffffff811fa647)
Location: include/linux/cgroup.h:492
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_write
```
```
In mm/hugetlb_cgroup.c (ffffffff81200df7)
Location: include/linux/cgroup.h:492
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_reset
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_write
```
```
In security/device_cgroup.c (ffffffff81395af5)
Location: include/linux/cgroup.h:492
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_access_write
```
```
In block/blk-cgroup.c (ffffffff813d8736)
Location: include/linux/cgroup.h:492
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_print_stat_bytes
  - block/blk-cgroup.c:blkg_print_stat_ios
  - block/blk-cgroup.c:blkg_print_stat_bytes_recursive
  - block/blk-cgroup.c:blkg_print_stat_ios_recursive
```
```
In block/blk-throttle.c (ffffffff813d9796)
Location: include/linux/cgroup.h:492
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_print_conf_uint
  - block/blk-throttle.c:tg_print_conf_u64
  - block/blk-throttle.c:tg_print_max
  - block/blk-throttle.c:tg_set_conf
```
```
In block/cfq-iosched.c (ffffffff813de316)
Location: include/linux/cgroup.h:492
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfqg_print_rwstat_recursive
  - block/cfq-iosched.c:cfqg_print_stat_recursive
  - block/cfq-iosched.c:cfqg_print_rwstat
  - block/cfq-iosched.c:cfqg_print_stat
```
```
In net/ipv4/tcp_memcontrol.c (ffffffff817acef5)
Location: include/linux/cgroup.h:492
Inline: True
Inline callers:
  - net/ipv4/tcp_memcontrol.c:tcp_cgroup_reset
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
In kernel/cgroup.c (ffffffff81120687)
Location: include/linux/cgroup.h:513
Inline: True
Inline callers:
  - kernel/cgroup.c:cgroup_pidlist_start
  - kernel/cgroup.c:cgroup_seqfile_show
  - kernel/cgroup.c:cgroup_seqfile_stop
  - kernel/cgroup.c:cgroup_seqfile_next
  - kernel/cgroup.c:cgroup_seqfile_start
```
```
In kernel/cpuset.c (ffffffff81123e10)
Location: include/linux/cgroup.h:513
Inline: True
Inline callers:
  - kernel/cpuset.c:cpuset_common_seq_show
  - kernel/cpuset.c:cpuset_write_resmask
```
```
In mm/memcontrol.c (ffffffff81222069)
Location: include/linux/cgroup.h:513
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_write
```
```
In mm/hugetlb_cgroup.c (ffffffff81225567)
Location: include/linux/cgroup.h:513
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_reset
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_write
```
```
In security/device_cgroup.c (ffffffff813d1845)
Location: include/linux/cgroup.h:513
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_access_write
```
```
In block/blk-cgroup.c (ffffffff8141e566)
Location: include/linux/cgroup.h:513
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_print_stat_ios_recursive
  - block/blk-cgroup.c:blkg_print_stat_bytes_recursive
  - block/blk-cgroup.c:blkg_print_stat_ios
  - block/blk-cgroup.c:blkg_print_stat_bytes
```
```
In block/blk-throttle.c (ffffffff8141f676)
Location: include/linux/cgroup.h:513
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_print_max
  - block/blk-throttle.c:tg_print_conf_uint
  - block/blk-throttle.c:tg_print_conf_u64
```
```
In block/cfq-iosched.c (ffffffff81424416)
Location: include/linux/cgroup.h:513
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfqg_print_rwstat_recursive
  - block/cfq-iosched.c:cfqg_print_stat_recursive
  - block/cfq-iosched.c:cfqg_print_rwstat
  - block/cfq-iosched.c:cfqg_print_stat
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
In kernel/cgroup.c (ffffffff81128b74)
Location: include/linux/cgroup.h:530
Inline: True
Inline callers:
  - kernel/cgroup.c:cgroup_pidlist_start
  - kernel/cgroup.c:cgroup_seqfile_show
  - kernel/cgroup.c:cgroup_seqfile_stop
  - kernel/cgroup.c:cgroup_seqfile_next
  - kernel/cgroup.c:cgroup_seqfile_start
```
```
In kernel/cpuset.c (ffffffff8112c2ad)
Location: include/linux/cgroup.h:530
Inline: True
Inline callers:
  - kernel/cpuset.c:cpuset_common_seq_show
  - kernel/cpuset.c:cpuset_write_resmask
```
```
In mm/memcontrol.c (ffffffff812347d9)
Location: include/linux/cgroup.h:530
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_write
```
```
In mm/hugetlb_cgroup.c (ffffffff81237b47)
Location: include/linux/cgroup.h:530
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_reset
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_write
```
```
In security/device_cgroup.c (ffffffff813e8f75)
Location: include/linux/cgroup.h:530
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_access_write
```
```
In block/blk-cgroup.c (ffffffff81439b23)
Location: include/linux/cgroup.h:530
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_print_stat_ios_recursive
  - block/blk-cgroup.c:blkg_print_stat_bytes_recursive
  - block/blk-cgroup.c:blkg_print_stat_ios
  - block/blk-cgroup.c:blkg_print_stat_bytes
```
```
In block/blk-throttle.c (ffffffff8143ac33)
Location: include/linux/cgroup.h:530
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_print_max
  - block/blk-throttle.c:tg_print_conf_uint
  - block/blk-throttle.c:tg_print_conf_u64
```
```
In block/cfq-iosched.c (ffffffff8143fe23)
Location: include/linux/cgroup.h:530
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfqg_print_rwstat_recursive
  - block/cfq-iosched.c:cfqg_print_stat_recursive
  - block/cfq-iosched.c:cfqg_print_rwstat
  - block/cfq-iosched.c:cfqg_print_stat
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
In kernel/cgroup/cgroup.c (ffffffff81121dd4)
Location: include/linux/cgroup.h:550
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_seqfile_show
  - kernel/cgroup/cgroup.c:cgroup_seqfile_stop
  - kernel/cgroup/cgroup.c:cgroup_seqfile_next
  - kernel/cgroup/cgroup.c:cgroup_seqfile_start
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8112a14a)
Location: include/linux/cgroup.h:550
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
```
```
In kernel/cgroup/rdma.c (ffffffff8112bb94)
Location: include/linux/cgroup.h:550
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_read
```
```
In kernel/cgroup/cpuset.c (ffffffff8112d51d)
Location: include/linux/cgroup.h:550
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_common_seq_show
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In mm/memcontrol.c (ffffffff8123b1d7)
Location: include/linux/cgroup.h:550
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_reset
  - mm/memcontrol.c:mem_cgroup_write
```
```
In mm/hugetlb_cgroup.c (ffffffff812437b7)
Location: include/linux/cgroup.h:550
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_reset
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_write
```
```
In security/device_cgroup.c (ffffffff813f5386)
Location: include/linux/cgroup.h:550
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_access_write
```
```
In block/blk-cgroup.c (ffffffff81447293)
Location: include/linux/cgroup.h:550
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_print_stat_ios_recursive
  - block/blk-cgroup.c:blkg_print_stat_bytes_recursive
  - block/blk-cgroup.c:blkg_print_stat_ios
  - block/blk-cgroup.c:blkg_print_stat_bytes
```
```
In block/blk-throttle.c (ffffffff8144a921)
Location: include/linux/cgroup.h:550
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_set_limit
  - block/blk-throttle.c:tg_print_limit
  - block/blk-throttle.c:tg_print_conf_uint
  - block/blk-throttle.c:tg_print_conf_u64
```
```
In block/cfq-iosched.c (ffffffff8144f0a3)
Location: include/linux/cgroup.h:550
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfqg_print_rwstat_recursive
  - block/cfq-iosched.c:cfqg_print_stat_recursive
  - block/cfq-iosched.c:cfqg_print_rwstat
  - block/cfq-iosched.c:cfqg_print_stat
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
In kernel/cgroup/cgroup.c (ffffffff8112d6b4)
Location: include/linux/cgroup.h:587
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_seqfile_show
  - kernel/cgroup/cgroup.c:cgroup_seqfile_stop
  - kernel/cgroup/cgroup.c:cgroup_seqfile_next
  - kernel/cgroup/cgroup.c:cgroup_seqfile_start
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff811371c2)
Location: include/linux/cgroup.h:587
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
```
```
In kernel/cgroup/rdma.c (ffffffff8113899b)
Location: include/linux/cgroup.h:587
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_read
```
```
In kernel/cgroup/cpuset.c (ffffffff8113a428)
Location: include/linux/cgroup.h:587
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_common_seq_show
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In mm/memcontrol.c (ffffffff8125aa67)
Location: include/linux/cgroup.h:587
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_reset
  - mm/memcontrol.c:mem_cgroup_write
```
```
In mm/hugetlb_cgroup.c (ffffffff81263607)
Location: include/linux/cgroup.h:587
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_reset
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_write
```
```
In security/device_cgroup.c (ffffffff8141d646)
Location: include/linux/cgroup.h:587
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_access_write
```
```
In block/blk-cgroup.c (ffffffff81473e73)
Location: include/linux/cgroup.h:587
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_print_stat_ios_recursive
  - block/blk-cgroup.c:blkg_print_stat_bytes_recursive
  - block/blk-cgroup.c:blkg_print_stat_ios
  - block/blk-cgroup.c:blkg_print_stat_bytes
```
```
In block/blk-throttle.c (ffffffff81476c51)
Location: include/linux/cgroup.h:587
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_set_limit
  - block/blk-throttle.c:tg_print_limit
  - block/blk-throttle.c:tg_print_conf_uint
  - block/blk-throttle.c:tg_print_conf_u64
```
```
In block/cfq-iosched.c (ffffffff8147b1e3)
Location: include/linux/cgroup.h:587
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfqg_print_rwstat_recursive
  - block/cfq-iosched.c:cfqg_print_stat_recursive
  - block/cfq-iosched.c:cfqg_print_rwstat
  - block/cfq-iosched.c:cfqg_print_stat
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
In kernel/cgroup/cgroup.c (ffffffff8113b8a4)
Location: include/linux/cgroup.h:587
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_seqfile_show
  - kernel/cgroup/cgroup.c:cgroup_seqfile_stop
  - kernel/cgroup/cgroup.c:cgroup_seqfile_next
  - kernel/cgroup/cgroup.c:cgroup_seqfile_start
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
In kernel/cgroup/cgroup-v1.c (ffffffff811459bb)
Location: include/linux/cgroup.h:587
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
```
```
In kernel/cgroup/rdma.c (ffffffff811472b3)
Location: include/linux/cgroup.h:587
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_read
```
```
In kernel/cgroup/cpuset.c (ffffffff81148994)
Location: include/linux/cgroup.h:587
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_common_seq_show
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In mm/memcontrol.c (ffffffff8127ea17)
Location: include/linux/cgroup.h:587
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_reset
  - mm/memcontrol.c:mem_cgroup_write
```
```
In mm/hugetlb_cgroup.c (ffffffff812878e7)
Location: include/linux/cgroup.h:587
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_reset
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_write
```
```
In security/device_cgroup.c (ffffffff8144f909)
Location: include/linux/cgroup.h:587
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_access_write
```
```
In block/blk-cgroup.c (ffffffff814a8363)
Location: include/linux/cgroup.h:587
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_print_stat_ios_recursive
  - block/blk-cgroup.c:blkg_print_stat_bytes_recursive
  - block/blk-cgroup.c:blkg_print_stat_ios
  - block/blk-cgroup.c:blkg_print_stat_bytes
```
```
In block/blk-throttle.c (ffffffff814ab361)
Location: include/linux/cgroup.h:587
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_set_limit
  - block/blk-throttle.c:tg_print_limit
  - block/blk-throttle.c:tg_print_conf_uint
  - block/blk-throttle.c:tg_print_conf_u64
```
```
In block/cfq-iosched.c (ffffffff814af8c3)
Location: include/linux/cgroup.h:587
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfqg_print_rwstat_recursive
  - block/cfq-iosched.c:cfqg_print_stat_recursive
  - block/cfq-iosched.c:cfqg_print_rwstat
  - block/cfq-iosched.c:cfqg_print_stat
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
In kernel/cgroup/cgroup.c (ffffffff811470a4)
Location: include/linux/cgroup.h:610
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_seqfile_show
  - kernel/cgroup/cgroup.c:cgroup_seqfile_stop
  - kernel/cgroup/cgroup.c:cgroup_seqfile_next
  - kernel/cgroup/cgroup.c:cgroup_seqfile_start
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
In kernel/cgroup/cgroup-v1.c (ffffffff8115157b)
Location: include/linux/cgroup.h:610
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
```
```
In kernel/cgroup/rdma.c (ffffffff81152f83)
Location: include/linux/cgroup.h:610
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_read
```
```
In kernel/cgroup/cpuset.c (ffffffff81154904)
Location: include/linux/cgroup.h:610
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_common_seq_show
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In mm/memcontrol.c (ffffffff812931a7)
Location: include/linux/cgroup.h:610
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_reset
  - mm/memcontrol.c:mem_cgroup_write
```
```
In mm/hugetlb_cgroup.c (ffffffff8129c837)
Location: include/linux/cgroup.h:610
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_reset
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_write
```
```
In security/device_cgroup.c (ffffffff8146c8e9)
Location: include/linux/cgroup.h:610
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_access_write
```
```
In block/blk-cgroup.c (ffffffff814c1f13)
Location: include/linux/cgroup.h:610
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_print_stat_ios_recursive
  - block/blk-cgroup.c:blkg_print_stat_bytes_recursive
  - block/blk-cgroup.c:blkg_print_stat_ios
  - block/blk-cgroup.c:blkg_print_stat_bytes
```
```
In block/blk-throttle.c (ffffffff814c5761)
Location: include/linux/cgroup.h:610
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_set_limit
  - block/blk-throttle.c:tg_print_limit
  - block/blk-throttle.c:tg_print_conf_uint
  - block/blk-throttle.c:tg_print_conf_u64
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
In kernel/cgroup/cgroup.c (ffffffff81152368)
Location: include/linux/cgroup.h:623
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_seqfile_show
  - kernel/cgroup/cgroup.c:cgroup_seqfile_stop
  - kernel/cgroup/cgroup.c:cgroup_seqfile_next
  - kernel/cgroup/cgroup.c:cgroup_seqfile_start
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
In kernel/cgroup/cgroup-v1.c (ffffffff8115c84e)
Location: include/linux/cgroup.h:623
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
```
```
In kernel/cgroup/rdma.c (ffffffff8115f5c2)
Location: include/linux/cgroup.h:623
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_read
```
```
In kernel/cgroup/cpuset.c (ffffffff81160e54)
Location: include/linux/cgroup.h:623
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_common_seq_show
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In mm/memcontrol.c (ffffffff812ae157)
Location: include/linux/cgroup.h:623
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_reset
  - mm/memcontrol.c:mem_cgroup_write
```
```
In mm/hugetlb_cgroup.c (ffffffff812b79f7)
Location: include/linux/cgroup.h:623
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_reset
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_write
```
```
In security/device_cgroup.c (ffffffff81499fe9)
Location: include/linux/cgroup.h:623
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_access_write
```
```
In block/blk-cgroup.c (ffffffff814f0644)
Location: include/linux/cgroup.h:623
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_print_stat_ios_recursive
  - block/blk-cgroup.c:blkg_print_stat_bytes_recursive
  - block/blk-cgroup.c:blkg_print_stat_ios
  - block/blk-cgroup.c:blkg_print_stat_bytes
```
```
In block/blk-throttle.c (ffffffff814f3ff2)
Location: include/linux/cgroup.h:623
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_set_limit
  - block/blk-throttle.c:tg_print_limit
  - block/blk-throttle.c:tg_print_conf_uint
  - block/blk-throttle.c:tg_print_conf_u64
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
In kernel/cgroup/cgroup.c (ffffffff8115dfb8)
Location: include/linux/cgroup.h:625
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_seqfile_show
  - kernel/cgroup/cgroup.c:cgroup_seqfile_stop
  - kernel/cgroup/cgroup.c:cgroup_seqfile_next
  - kernel/cgroup/cgroup.c:cgroup_seqfile_start
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
In kernel/cgroup/cgroup-v1.c (ffffffff81167ffe)
Location: include/linux/cgroup.h:625
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
```
```
In kernel/cgroup/rdma.c (ffffffff8116b222)
Location: include/linux/cgroup.h:625
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_read
```
```
In kernel/cgroup/cpuset.c (ffffffff8116cb24)
Location: include/linux/cgroup.h:625
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_common_seq_show
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In mm/memcontrol.c (ffffffff812bfb57)
Location: include/linux/cgroup.h:625
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_reset
  - mm/memcontrol.c:mem_cgroup_write
```
```
In mm/hugetlb_cgroup.c (ffffffff812c98d7)
Location: include/linux/cgroup.h:625
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_reset
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_write
```
```
In security/device_cgroup.c (ffffffff814b41e9)
Location: include/linux/cgroup.h:625
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_access_write
```
```
In block/blk-cgroup.c (ffffffff81509ae4)
Location: include/linux/cgroup.h:625
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_print_stat_ios_recursive
  - block/blk-cgroup.c:blkg_print_stat_bytes_recursive
  - block/blk-cgroup.c:blkg_print_stat_ios
  - block/blk-cgroup.c:blkg_print_stat_bytes
```
```
In block/blk-throttle.c (ffffffff8150d582)
Location: include/linux/cgroup.h:625
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_set_limit
  - block/blk-throttle.c:tg_print_limit
  - block/blk-throttle.c:tg_print_conf_uint
  - block/blk-throttle.c:tg_print_conf_u64
```
```
In block/blk-iocost.c (ffffffff81510437)
Location: include/linux/cgroup.h:625
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_cost_model_show
  - block/blk-iocost.c:ioc_qos_show
  - block/blk-iocost.c:ioc_weight_show
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
In kernel/cgroup/cgroup.c (ffffffff81177239)
Location: include/linux/cgroup.h:631
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:__cgroup_procs_start
  - kernel/cgroup/cgroup.c:cgroup_seqfile_show
  - kernel/cgroup/cgroup.c:cgroup_seqfile_stop
  - kernel/cgroup/cgroup.c:cgroup_seqfile_next
  - kernel/cgroup/cgroup.c:cgroup_seqfile_start
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
In kernel/cgroup/cgroup-v1.c (ffffffff81179d2f)
Location: include/linux/cgroup.h:631
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
```
```
In kernel/cgroup/rdma.c (ffffffff8117cbd2)
Location: include/linux/cgroup.h:631
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_read
```
```
In kernel/cgroup/cpuset.c (ffffffff8117e444)
Location: include/linux/cgroup.h:631
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_common_seq_show
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In mm/memcontrol.c (ffffffff812f4c67)
Location: include/linux/cgroup.h:631
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_reset
  - mm/memcontrol.c:mem_cgroup_write
```
```
In mm/hugetlb_cgroup.c (ffffffff812fef23)
Location: include/linux/cgroup.h:631
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_events_local_show
  - mm/hugetlb_cgroup.c:hugetlb_events_show
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_reset
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_u64_max
```
```
In security/device_cgroup.c (ffffffff81513ab3)
Location: include/linux/cgroup.h:631
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_access_write
```
```
In block/blk-throttle.c (ffffffff8156f802)
Location: include/linux/cgroup.h:631
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_set_limit
  - block/blk-throttle.c:tg_print_limit
  - block/blk-throttle.c:tg_print_rwstat_recursive
  - block/blk-throttle.c:tg_print_rwstat
  - block/blk-throttle.c:tg_print_conf_uint
  - block/blk-throttle.c:tg_print_conf_u64
```
```
In block/blk-iocost.c (ffffffff81571757)
Location: include/linux/cgroup.h:631
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_cost_model_show
  - block/blk-iocost.c:ioc_qos_show
  - block/blk-iocost.c:ioc_weight_show
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
In kernel/cgroup/cgroup.c (ffffffff81173f24)
Location: include/linux/cgroup.h:631
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:__cgroup_procs_start
  - kernel/cgroup/cgroup.c:cgroup_seqfile_show
  - kernel/cgroup/cgroup.c:cgroup_seqfile_stop
  - kernel/cgroup/cgroup.c:cgroup_seqfile_next
  - kernel/cgroup/cgroup.c:cgroup_seqfile_start
  - kernel/cgroup/cgroup.c:cgroup_file_poll
  - kernel/cgroup/cgroup.c:cgroup_file_write
  - kernel/cgroup/cgroup.c:cgroup_file_release
  - kernel/cgroup/cgroup.c:cgroup_file_open
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
In kernel/cgroup/cgroup-v1.c (ffffffff81176a9f)
Location: include/linux/cgroup.h:631
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
```
```
In kernel/cgroup/rdma.c (ffffffff81179a32)
Location: include/linux/cgroup.h:631
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_read
```
```
In kernel/cgroup/cpuset.c (ffffffff8117b2b4)
Location: include/linux/cgroup.h:631
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_common_seq_show
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In mm/memcontrol.c (ffffffff81300527)
Location: include/linux/cgroup.h:631
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_reset
  - mm/memcontrol.c:mem_cgroup_write
```
```
In mm/hugetlb_cgroup.c (ffffffff8130b263)
Location: include/linux/cgroup.h:631
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_events_local_show
  - mm/hugetlb_cgroup.c:hugetlb_events_show
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_reset
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_u64_max
```
```
In security/device_cgroup.c (ffffffff81530c03)
Location: include/linux/cgroup.h:631
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_access_write
```
```
In block/blk-throttle.c (ffffffff8158a612)
Location: include/linux/cgroup.h:631
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_set_limit
  - block/blk-throttle.c:tg_print_limit
  - block/blk-throttle.c:tg_print_rwstat_recursive
  - block/blk-throttle.c:tg_print_rwstat
  - block/blk-throttle.c:tg_print_conf_uint
  - block/blk-throttle.c:tg_print_conf_u64
```
```
In block/blk-iocost.c (ffffffff8158c817)
Location: include/linux/cgroup.h:631
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_cost_model_show
  - block/blk-iocost.c:ioc_qos_show
  - block/blk-iocost.c:ioc_weight_show
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
In kernel/cgroup/cgroup.c (ffffffff81174af7)
Location: include/linux/cgroup.h:631
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:__cgroup_procs_start
  - kernel/cgroup/cgroup.c:cgroup_seqfile_show
  - kernel/cgroup/cgroup.c:cgroup_seqfile_stop
  - kernel/cgroup/cgroup.c:cgroup_seqfile_next
  - kernel/cgroup/cgroup.c:cgroup_seqfile_start
  - kernel/cgroup/cgroup.c:cgroup_file_poll
  - kernel/cgroup/cgroup.c:cgroup_file_write
  - kernel/cgroup/cgroup.c:cgroup_file_release
  - kernel/cgroup/cgroup.c:cgroup_file_open
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
In kernel/cgroup/cgroup-v1.c (ffffffff8117776b)
Location: include/linux/cgroup.h:631
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
```
```
In kernel/cgroup/rdma.c (ffffffff8117a5c2)
Location: include/linux/cgroup.h:631
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_read
```
```
In kernel/cgroup/cpuset.c (ffffffff8117cf34)
Location: include/linux/cgroup.h:631
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_common_seq_show
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In mm/memcontrol.c (ffffffff81306fd7)
Location: include/linux/cgroup.h:631
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_reset
  - mm/memcontrol.c:mem_cgroup_write
```
```
In mm/hugetlb_cgroup.c (ffffffff81311eb3)
Location: include/linux/cgroup.h:631
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_events_local_show
  - mm/hugetlb_cgroup.c:hugetlb_events_show
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_reset
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_u64_max
```
```
In security/device_cgroup.c (ffffffff81536e05)
Location: include/linux/cgroup.h:631
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_access_write
```
```
In block/blk-throttle.c (ffffffff81591112)
Location: include/linux/cgroup.h:631
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_set_limit
  - block/blk-throttle.c:tg_print_limit
  - block/blk-throttle.c:tg_print_rwstat_recursive
  - block/blk-throttle.c:tg_print_rwstat
  - block/blk-throttle.c:tg_print_conf_uint
  - block/blk-throttle.c:tg_print_conf_u64
```
```
In block/blk-iocost.c (ffffffff81593557)
Location: include/linux/cgroup.h:631
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_cost_model_show
  - block/blk-iocost.c:ioc_qos_show
  - block/blk-iocost.c:ioc_weight_show
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
In kernel/cgroup/cgroup.c (ffffffff8119bd92)
Location: include/linux/cgroup.h:631
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:__cgroup_procs_start
  - kernel/cgroup/cgroup.c:cgroup_seqfile_show
  - kernel/cgroup/cgroup.c:cgroup_seqfile_stop
  - kernel/cgroup/cgroup.c:cgroup_seqfile_next
  - kernel/cgroup/cgroup.c:cgroup_seqfile_start
  - kernel/cgroup/cgroup.c:cgroup_file_poll
  - kernel/cgroup/cgroup.c:cgroup_file_write
  - kernel/cgroup/cgroup.c:cgroup_file_release
  - kernel/cgroup/cgroup.c:cgroup_file_open
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
In kernel/cgroup/cgroup-v1.c (ffffffff8119f060)
Location: include/linux/cgroup.h:631
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
```
```
In kernel/cgroup/rdma.c (ffffffff811a1f02)
Location: include/linux/cgroup.h:631
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_read
```
```
In kernel/cgroup/cpuset.c (ffffffff811a4ad4)
Location: include/linux/cgroup.h:631
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_common_seq_show
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In mm/memcontrol.c (ffffffff81350c47)
Location: include/linux/cgroup.h:631
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_reset
  - mm/memcontrol.c:mem_cgroup_write
```
```
In mm/hugetlb_cgroup.c (ffffffff8135cca7)
Location: include/linux/cgroup.h:631
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_events_local_show
  - mm/hugetlb_cgroup.c:hugetlb_events_show
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_reset
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_u64_max
```
```
In security/device_cgroup.c (ffffffff81595575)
Location: include/linux/cgroup.h:631
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_access_write
```
```
In block/blk-throttle.c (ffffffff815f8162)
Location: include/linux/cgroup.h:631
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_set_limit
  - block/blk-throttle.c:tg_print_limit
  - block/blk-throttle.c:tg_print_rwstat_recursive
  - block/blk-throttle.c:tg_print_rwstat
  - block/blk-throttle.c:tg_print_conf_uint
  - block/blk-throttle.c:tg_print_conf_u64
```
```
In block/blk-iocost.c (ffffffff815fa6e7)
Location: include/linux/cgroup.h:631
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_cost_model_show
  - block/blk-iocost.c:ioc_qos_show
  - block/blk-iocost.c:ioc_weight_show
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
In kernel/cgroup/cgroup.c (ffffffff811cc022)
Location: include/linux/cgroup.h:632
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:__cgroup_procs_start
  - kernel/cgroup/cgroup.c:cgroup_seqfile_show
  - kernel/cgroup/cgroup.c:cgroup_seqfile_stop
  - kernel/cgroup/cgroup.c:cgroup_seqfile_next
  - kernel/cgroup/cgroup.c:cgroup_seqfile_start
  - kernel/cgroup/cgroup.c:cgroup_file_poll
  - kernel/cgroup/cgroup.c:cgroup_file_write
  - kernel/cgroup/cgroup.c:cgroup_file_release
  - kernel/cgroup/cgroup.c:cgroup_file_open
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
In kernel/cgroup/cgroup-v1.c (ffffffff811cfae0)
Location: include/linux/cgroup.h:632
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
```
```
In kernel/cgroup/rdma.c (ffffffff811d2942)
Location: include/linux/cgroup.h:632
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_read
```
```
In kernel/cgroup/cpuset.c (ffffffff811d39a4)
Location: include/linux/cgroup.h:632
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_common_seq_show
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In mm/memcontrol.c (ffffffff813c91e7)
Location: include/linux/cgroup.h:632
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_reset
  - mm/memcontrol.c:mem_cgroup_write
```
```
In mm/hugetlb_cgroup.c (ffffffff813d6987)
Location: include/linux/cgroup.h:632
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_events_local_show
  - mm/hugetlb_cgroup.c:hugetlb_events_show
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_reset
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_u64_max
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_numa_stat
```
```
In security/device_cgroup.c (ffffffff816377b3)
Location: include/linux/cgroup.h:632
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_access_write
```
```
In block/blk-throttle.c (ffffffff816a97d1)
Location: include/linux/cgroup.h:632
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_set_limit
  - block/blk-throttle.c:tg_print_limit
  - block/blk-throttle.c:tg_print_rwstat_recursive
  - block/blk-throttle.c:tg_print_rwstat
  - block/blk-throttle.c:tg_print_conf_uint
  - block/blk-throttle.c:tg_print_conf_u64
```
```
In block/blk-iocost.c (ffffffff816acb36)
Location: include/linux/cgroup.h:632
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_cost_model_show
  - block/blk-iocost.c:ioc_qos_show
  - block/blk-iocost.c:ioc_weight_show
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
In kernel/cgroup/cgroup.c (ffffffff8120f522)
Location: include/linux/cgroup.h:572
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:__cgroup_procs_start
  - kernel/cgroup/cgroup.c:cgroup_seqfile_show
  - kernel/cgroup/cgroup.c:cgroup_seqfile_stop
  - kernel/cgroup/cgroup.c:cgroup_seqfile_next
  - kernel/cgroup/cgroup.c:cgroup_seqfile_start
  - kernel/cgroup/cgroup.c:cgroup_file_poll
  - kernel/cgroup/cgroup.c:cgroup_file_write
  - kernel/cgroup/cgroup.c:cgroup_file_release
  - kernel/cgroup/cgroup.c:cgroup_file_open
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
In kernel/cgroup/cgroup-v1.c (ffffffff812134d0)
Location: include/linux/cgroup.h:572
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
```
```
In kernel/cgroup/rdma.c (ffffffff81216852)
Location: include/linux/cgroup.h:572
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_read
```
```
In kernel/cgroup/cpuset.c (ffffffff81217674)
Location: include/linux/cgroup.h:572
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_common_seq_show
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In mm/memcontrol.c (ffffffff8144e4a7)
Location: include/linux/cgroup.h:572
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_reset
  - mm/memcontrol.c:mem_cgroup_write
```
```
In mm/hugetlb_cgroup.c (ffffffff8145d377)
Location: include/linux/cgroup.h:572
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_events_local_show
  - mm/hugetlb_cgroup.c:hugetlb_events_show
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_reset
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_u64_max
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_numa_stat
```
```
In security/device_cgroup.c (ffffffff816eeb43)
Location: include/linux/cgroup.h:572
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_access_write
```
```
In block/blk-throttle.c (ffffffff81768a21)
Location: include/linux/cgroup.h:572
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_set_limit
  - block/blk-throttle.c:tg_print_limit
  - block/blk-throttle.c:tg_print_rwstat_recursive
  - block/blk-throttle.c:tg_print_rwstat
  - block/blk-throttle.c:tg_print_conf_uint
  - block/blk-throttle.c:tg_print_conf_u64
```
```
In block/blk-iocost.c (ffffffff8176b686)
Location: include/linux/cgroup.h:572
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_cost_model_show
  - block/blk-iocost.c:ioc_qos_show
  - block/blk-iocost.c:ioc_weight_show
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
In kernel/cgroup/cgroup.c (ffffffff81224f32)
Location: include/linux/cgroup.h:571
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:__cgroup_procs_start
  - kernel/cgroup/cgroup.c:cgroup_seqfile_show
  - kernel/cgroup/cgroup.c:cgroup_seqfile_stop
  - kernel/cgroup/cgroup.c:cgroup_seqfile_next
  - kernel/cgroup/cgroup.c:cgroup_seqfile_start
  - kernel/cgroup/cgroup.c:cgroup_file_poll
  - kernel/cgroup/cgroup.c:cgroup_file_write
  - kernel/cgroup/cgroup.c:cgroup_file_release
  - kernel/cgroup/cgroup.c:cgroup_file_open
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
In kernel/cgroup/cgroup-v1.c (ffffffff81228de0)
Location: include/linux/cgroup.h:571
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
```
```
In kernel/cgroup/rdma.c (ffffffff8122c142)
Location: include/linux/cgroup.h:571
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_read
```
```
In kernel/cgroup/cpuset.c (ffffffff8122cfa4)
Location: include/linux/cgroup.h:571
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_common_seq_show
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In mm/memcontrol.c (ffffffff81483f67)
Location: include/linux/cgroup.h:571
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_reset
  - mm/memcontrol.c:mem_cgroup_write
```
```
In mm/hugetlb_cgroup.c (ffffffff81492127)
Location: include/linux/cgroup.h:571
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_events_local_show
  - mm/hugetlb_cgroup.c:hugetlb_events_show
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_reset
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_u64_max
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_numa_stat
```
```
In security/device_cgroup.c (ffffffff81729043)
Location: include/linux/cgroup.h:571
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_access_write
```
```
In block/blk-throttle.c (ffffffff817a7b82)
Location: include/linux/cgroup.h:571
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_set_limit
  - block/blk-throttle.c:tg_print_limit
  - block/blk-throttle.c:tg_print_rwstat_recursive
  - block/blk-throttle.c:tg_print_rwstat
  - block/blk-throttle.c:tg_print_conf_uint
  - block/blk-throttle.c:tg_print_conf_u64
```
```
In block/blk-iocost.c (ffffffff817aa786)
Location: include/linux/cgroup.h:571
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_cost_model_show
  - block/blk-iocost.c:ioc_qos_show
  - block/blk-iocost.c:ioc_weight_show
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
In kernel/cgroup/cgroup.c (ffffffff8123cc22)
Location: include/linux/cgroup.h:569
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:__cgroup_procs_start
  - kernel/cgroup/cgroup.c:cgroup_seqfile_show
  - kernel/cgroup/cgroup.c:cgroup_seqfile_stop
  - kernel/cgroup/cgroup.c:cgroup_seqfile_next
  - kernel/cgroup/cgroup.c:cgroup_seqfile_start
  - kernel/cgroup/cgroup.c:cgroup_file_poll
  - kernel/cgroup/cgroup.c:cgroup_file_write
  - kernel/cgroup/cgroup.c:cgroup_file_release
  - kernel/cgroup/cgroup.c:cgroup_file_open
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
In kernel/cgroup/cgroup-v1.c (ffffffff81240c30)
Location: include/linux/cgroup.h:569
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
```
```
In kernel/cgroup/rdma.c (ffffffff81244172)
Location: include/linux/cgroup.h:569
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_read
```
```
In kernel/cgroup/cpuset.c (ffffffff81245164)
Location: include/linux/cgroup.h:569
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_common_seq_show
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In mm/memcontrol.c (ffffffff814b3407)
Location: include/linux/cgroup.h:569
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_reset
  - mm/memcontrol.c:mem_cgroup_write
```
```
In mm/hugetlb_cgroup.c (ffffffff814c1b37)
Location: include/linux/cgroup.h:569
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_events_local_show
  - mm/hugetlb_cgroup.c:hugetlb_events_show
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_reset
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_u64_max
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_numa_stat
```
```
In security/device_cgroup.c (ffffffff8176a3a3)
Location: include/linux/cgroup.h:569
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_access_write
```
```
In block/blk-throttle.c (ffffffff817eb902)
Location: include/linux/cgroup.h:569
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_set_limit
  - block/blk-throttle.c:tg_print_limit
  - block/blk-throttle.c:tg_print_rwstat_recursive
  - block/blk-throttle.c:tg_print_rwstat
  - block/blk-throttle.c:tg_print_conf_uint
  - block/blk-throttle.c:tg_print_conf_u64
```
```
In block/blk-iocost.c (ffffffff817ee536)
Location: include/linux/cgroup.h:569
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_cost_model_show
  - block/blk-iocost.c:ioc_qos_show
  - block/blk-iocost.c:ioc_weight_show
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
In kernel/cgroup/cgroup.c (ffff8000101ce6f4)
Location: include/linux/cgroup.h:625
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_seqfile_show
  - kernel/cgroup/cgroup.c:cgroup_seqfile_stop
  - kernel/cgroup/cgroup.c:cgroup_seqfile_next
  - kernel/cgroup/cgroup.c:cgroup_seqfile_start
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
In kernel/cgroup/cgroup-v1.c (ffff8000101dab18)
Location: include/linux/cgroup.h:625
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
```
```
In kernel/cgroup/rdma.c (ffff8000101df4a4)
Location: include/linux/cgroup.h:625
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_read
```
```
In kernel/cgroup/cpuset.c (ffff8000101e1368)
Location: include/linux/cgroup.h:625
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_common_seq_show
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In mm/memcontrol.c (ffff8000103615a0)
Location: include/linux/cgroup.h:625
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_reset
  - mm/memcontrol.c:mem_cgroup_write
```
```
In mm/hugetlb_cgroup.c (ffff80001036d038)
Location: include/linux/cgroup.h:625
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_reset
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_write
```
```
In security/device_cgroup.c (ffff8000105ac168)
Location: include/linux/cgroup.h:625
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_access_write
```
```
In block/blk-cgroup.c (ffff80001060c938)
Location: include/linux/cgroup.h:625
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_print_stat_ios_recursive
  - block/blk-cgroup.c:blkg_print_stat_bytes_recursive
  - block/blk-cgroup.c:blkg_print_stat_ios
  - block/blk-cgroup.c:blkg_print_stat_bytes
```
```
In block/blk-throttle.c (ffff800010611474)
Location: include/linux/cgroup.h:625
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_set_limit
  - block/blk-throttle.c:tg_print_limit
  - block/blk-throttle.c:tg_print_conf_uint
  - block/blk-throttle.c:tg_print_conf_u64
```
```
In block/blk-iocost.c (ffff800010613bf0)
Location: include/linux/cgroup.h:625
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_cost_model_show
  - block/blk-iocost.c:ioc_qos_show
  - block/blk-iocost.c:ioc_weight_show
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
In kernel/cgroup/cgroup.c (c041a9a4)
Location: include/linux/cgroup.h:625
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:__cgroup_procs_start
  - kernel/cgroup/cgroup.c:cgroup_seqfile_show
  - kernel/cgroup/cgroup.c:cgroup_seqfile_stop
  - kernel/cgroup/cgroup.c:cgroup_seqfile_next
  - kernel/cgroup/cgroup.c:cgroup_seqfile_start
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
In kernel/cgroup/cgroup-v1.c (c041d118)
Location: include/linux/cgroup.h:625
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
```
```
In kernel/cgroup/rdma.c (c0420db8)
Location: include/linux/cgroup.h:625
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_read
```
```
In kernel/cgroup/cpuset.c (c0421a34)
Location: include/linux/cgroup.h:625
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_common_seq_show
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In mm/memcontrol.c (c0553a1c)
Location: include/linux/cgroup.h:625
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_reset
  - mm/memcontrol.c:mem_cgroup_write
```
```
In security/device_cgroup.c (c075bbf0)
Location: include/linux/cgroup.h:625
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_access_write
```
```
In block/blk-cgroup.c (c07b6854)
Location: include/linux/cgroup.h:625
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_print_stat_ios_recursive
  - block/blk-cgroup.c:blkg_print_stat_bytes_recursive
  - block/blk-cgroup.c:blkg_print_stat_ios
  - block/blk-cgroup.c:blkg_print_stat_bytes
```
```
In block/blk-throttle.c (c07bb978)
Location: include/linux/cgroup.h:625
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_set_limit
  - block/blk-throttle.c:tg_print_limit
  - block/blk-throttle.c:tg_print_conf_uint
  - block/blk-throttle.c:tg_print_conf_u64
```
```
In block/blk-iocost.c (c07bf428)
Location: include/linux/cgroup.h:625
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_cost_model_show
  - block/blk-iocost.c:ioc_qos_show
  - block/blk-iocost.c:ioc_weight_show
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
In kernel/cgroup/cgroup.c (c0000000002385a8)
Location: include/linux/cgroup.h:625
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_seqfile_show
  - kernel/cgroup/cgroup.c:cgroup_seqfile_stop
  - kernel/cgroup/cgroup.c:cgroup_seqfile_next
  - kernel/cgroup/cgroup.c:cgroup_seqfile_start
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
In kernel/cgroup/cgroup-v1.c (c000000000248c94)
Location: include/linux/cgroup.h:625
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
```
```
In kernel/cgroup/rdma.c (c00000000024d66c)
Location: include/linux/cgroup.h:625
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_read
```
```
In kernel/cgroup/cpuset.c (c00000000024fc6c)
Location: include/linux/cgroup.h:625
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_common_seq_show
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In mm/memcontrol.c (c00000000044d358)
Location: include/linux/cgroup.h:625
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_reset
  - mm/memcontrol.c:mem_cgroup_write
```
```
In mm/hugetlb_cgroup.c (c00000000045cfc8)
Location: include/linux/cgroup.h:625
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_reset
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_write
```
```
In security/device_cgroup.c (c00000000072a498)
Location: include/linux/cgroup.h:625
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_access_write
```
```
In block/blk-cgroup.c (c0000000007a9950)
Location: include/linux/cgroup.h:625
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_print_stat_ios_recursive
  - block/blk-cgroup.c:blkg_print_stat_bytes_recursive
  - block/blk-cgroup.c:blkg_print_stat_ios
  - block/blk-cgroup.c:blkg_print_stat_bytes
```
```
In block/blk-throttle.c (c0000000007af070)
Location: include/linux/cgroup.h:625
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_set_limit
  - block/blk-throttle.c:tg_print_limit
  - block/blk-throttle.c:tg_print_conf_uint
  - block/blk-throttle.c:tg_print_conf_u64
```
```
In block/blk-iocost.c (c0000000007b2f30)
Location: include/linux/cgroup.h:625
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_cost_model_show
  - block/blk-iocost.c:ioc_qos_show
  - block/blk-iocost.c:ioc_weight_show
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
In kernel/cgroup/cgroup.c (ffffffe000149038)
Location: include/linux/cgroup.h:625
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_seqfile_show
  - kernel/cgroup/cgroup.c:cgroup_seqfile_stop
  - kernel/cgroup/cgroup.c:cgroup_seqfile_next
  - kernel/cgroup/cgroup.c:cgroup_seqfile_start
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
In kernel/cgroup/cgroup-v1.c (ffffffe000153066)
Location: include/linux/cgroup.h:625
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
```
```
In kernel/cgroup/rdma.c (ffffffe000156568)
Location: include/linux/cgroup.h:625
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_read
```
```
In kernel/cgroup/cpuset.c (ffffffe000158238)
Location: include/linux/cgroup.h:625
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_common_seq_show
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In mm/memcontrol.c (ffffffe000240bd0)
Location: include/linux/cgroup.h:625
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_reset
  - mm/memcontrol.c:mem_cgroup_write
```
```
In mm/hugetlb_cgroup.c (ffffffe000249e20)
Location: include/linux/cgroup.h:625
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_reset
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_write
```
```
In security/device_cgroup.c (ffffffe0003f4900)
Location: include/linux/cgroup.h:625
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_access_write
```
```
In block/blk-cgroup.c (ffffffe0004455ae)
Location: include/linux/cgroup.h:625
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_print_stat_ios_recursive
  - block/blk-cgroup.c:blkg_print_stat_bytes_recursive
  - block/blk-cgroup.c:blkg_print_stat_ios
  - block/blk-cgroup.c:blkg_print_stat_bytes
```
```
In block/blk-throttle.c (ffffffe000448d86)
Location: include/linux/cgroup.h:625
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_set_limit
  - block/blk-throttle.c:tg_print_limit
  - block/blk-throttle.c:tg_print_conf_uint
  - block/blk-throttle.c:tg_print_conf_u64
```
```
In block/blk-iocost.c (ffffffe00044b5b2)
Location: include/linux/cgroup.h:625
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_cost_model_show
  - block/blk-iocost.c:ioc_qos_show
  - block/blk-iocost.c:ioc_weight_show
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
In kernel/cgroup/cgroup.c (ffffffff811565d8)
Location: include/linux/cgroup.h:625
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_seqfile_show
  - kernel/cgroup/cgroup.c:cgroup_seqfile_stop
  - kernel/cgroup/cgroup.c:cgroup_seqfile_next
  - kernel/cgroup/cgroup.c:cgroup_seqfile_start
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
In kernel/cgroup/cgroup-v1.c (ffffffff8116061e)
Location: include/linux/cgroup.h:625
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
```
```
In kernel/cgroup/rdma.c (ffffffff81163842)
Location: include/linux/cgroup.h:625
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_read
```
```
In kernel/cgroup/cpuset.c (ffffffff81165144)
Location: include/linux/cgroup.h:625
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_common_seq_show
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In mm/memcontrol.c (ffffffff812b8137)
Location: include/linux/cgroup.h:625
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_reset
  - mm/memcontrol.c:mem_cgroup_write
```
```
In mm/hugetlb_cgroup.c (ffffffff812c1eb7)
Location: include/linux/cgroup.h:625
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_reset
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_write
```
```
In security/device_cgroup.c (ffffffff814ac7c9)
Location: include/linux/cgroup.h:625
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_access_write
```
```
In block/blk-cgroup.c (ffffffff815020c4)
Location: include/linux/cgroup.h:625
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_print_stat_ios_recursive
  - block/blk-cgroup.c:blkg_print_stat_bytes_recursive
  - block/blk-cgroup.c:blkg_print_stat_ios
  - block/blk-cgroup.c:blkg_print_stat_bytes
```
```
In block/blk-throttle.c (ffffffff81505b62)
Location: include/linux/cgroup.h:625
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_set_limit
  - block/blk-throttle.c:tg_print_limit
  - block/blk-throttle.c:tg_print_conf_uint
  - block/blk-throttle.c:tg_print_conf_u64
```
```
In block/blk-iocost.c (ffffffff81508a17)
Location: include/linux/cgroup.h:625
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_cost_model_show
  - block/blk-iocost.c:ioc_qos_show
  - block/blk-iocost.c:ioc_weight_show
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
In kernel/cgroup/cgroup.c (ffffffff811498f8)
Location: include/linux/cgroup.h:625
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_seqfile_show
  - kernel/cgroup/cgroup.c:cgroup_seqfile_stop
  - kernel/cgroup/cgroup.c:cgroup_seqfile_next
  - kernel/cgroup/cgroup.c:cgroup_seqfile_start
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
In kernel/cgroup/cgroup-v1.c (ffffffff8115388e)
Location: include/linux/cgroup.h:625
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
```
```
In kernel/cgroup/rdma.c (ffffffff81156a92)
Location: include/linux/cgroup.h:625
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_read
```
```
In kernel/cgroup/cpuset.c (ffffffff811580a4)
Location: include/linux/cgroup.h:625
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_common_seq_show
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In mm/memcontrol.c (ffffffff812a9307)
Location: include/linux/cgroup.h:625
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_reset
  - mm/memcontrol.c:mem_cgroup_write
```
```
In mm/hugetlb_cgroup.c (ffffffff812b2f07)
Location: include/linux/cgroup.h:625
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_reset
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_write
```
```
In security/device_cgroup.c (ffffffff8149d1e9)
Location: include/linux/cgroup.h:625
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_access_write
```
```
In block/blk-cgroup.c (ffffffff814f25d4)
Location: include/linux/cgroup.h:625
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_print_stat_ios_recursive
  - block/blk-cgroup.c:blkg_print_stat_bytes_recursive
  - block/blk-cgroup.c:blkg_print_stat_ios
  - block/blk-cgroup.c:blkg_print_stat_bytes
```
```
In block/blk-throttle.c (ffffffff814f6022)
Location: include/linux/cgroup.h:625
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_set_limit
  - block/blk-throttle.c:tg_print_limit
  - block/blk-throttle.c:tg_print_conf_uint
  - block/blk-throttle.c:tg_print_conf_u64
```
```
In block/blk-iocost.c (ffffffff814f8ec7)
Location: include/linux/cgroup.h:625
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_cost_model_show
  - block/blk-iocost.c:ioc_qos_show
  - block/blk-iocost.c:ioc_weight_show
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
In kernel/cgroup/cgroup.c (ffffffff811543a8)
Location: include/linux/cgroup.h:625
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_seqfile_show
  - kernel/cgroup/cgroup.c:cgroup_seqfile_stop
  - kernel/cgroup/cgroup.c:cgroup_seqfile_next
  - kernel/cgroup/cgroup.c:cgroup_seqfile_start
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
In kernel/cgroup/cgroup-v1.c (ffffffff8115e3ee)
Location: include/linux/cgroup.h:625
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
```
```
In kernel/cgroup/rdma.c (ffffffff81161612)
Location: include/linux/cgroup.h:625
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_read
```
```
In kernel/cgroup/cpuset.c (ffffffff81162f14)
Location: include/linux/cgroup.h:625
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_common_seq_show
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In mm/memcontrol.c (ffffffff812b5f47)
Location: include/linux/cgroup.h:625
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_reset
  - mm/memcontrol.c:mem_cgroup_write
```
```
In mm/hugetlb_cgroup.c (ffffffff812bfcc7)
Location: include/linux/cgroup.h:625
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_reset
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_write
```
```
In security/device_cgroup.c (ffffffff814a8869)
Location: include/linux/cgroup.h:625
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_access_write
```
```
In block/blk-cgroup.c (ffffffff814fe154)
Location: include/linux/cgroup.h:625
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_print_stat_ios_recursive
  - block/blk-cgroup.c:blkg_print_stat_bytes_recursive
  - block/blk-cgroup.c:blkg_print_stat_ios
  - block/blk-cgroup.c:blkg_print_stat_bytes
```
```
In block/blk-throttle.c (ffffffff81501bf2)
Location: include/linux/cgroup.h:625
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_set_limit
  - block/blk-throttle.c:tg_print_limit
  - block/blk-throttle.c:tg_print_conf_uint
  - block/blk-throttle.c:tg_print_conf_u64
```
```
In block/blk-iocost.c (ffffffff81504aa7)
Location: include/linux/cgroup.h:625
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_cost_model_show
  - block/blk-iocost.c:ioc_qos_show
  - block/blk-iocost.c:ioc_weight_show
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
In kernel/cgroup/cgroup.c (ffffffff811612a8)
Location: include/linux/cgroup.h:625
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_seqfile_show
  - kernel/cgroup/cgroup.c:cgroup_seqfile_stop
  - kernel/cgroup/cgroup.c:cgroup_seqfile_next
  - kernel/cgroup/cgroup.c:cgroup_seqfile_start
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
In kernel/cgroup/cgroup-v1.c (ffffffff8116b81e)
Location: include/linux/cgroup.h:625
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
```
```
In kernel/cgroup/rdma.c (ffffffff8116ea62)
Location: include/linux/cgroup.h:625
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_read
```
```
In kernel/cgroup/cpuset.c (ffffffff8116f4b4)
Location: include/linux/cgroup.h:625
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_common_seq_show
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In mm/memcontrol.c (ffffffff812c6507)
Location: include/linux/cgroup.h:625
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_reset
  - mm/memcontrol.c:mem_cgroup_write
```
```
In mm/hugetlb_cgroup.c (ffffffff812d0707)
Location: include/linux/cgroup.h:625
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_reset
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_write
```
```
In security/device_cgroup.c (ffffffff814c1228)
Location: include/linux/cgroup.h:625
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_access_write
```
```
In block/blk-cgroup.c (ffffffff81516414)
Location: include/linux/cgroup.h:625
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_print_stat_ios_recursive
  - block/blk-cgroup.c:blkg_print_stat_bytes_recursive
  - block/blk-cgroup.c:blkg_print_stat_ios
  - block/blk-cgroup.c:blkg_print_stat_bytes
```
```
In block/blk-throttle.c (ffffffff8151af12)
Location: include/linux/cgroup.h:625
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_set_limit
  - block/blk-throttle.c:tg_print_limit
  - block/blk-throttle.c:tg_print_conf_uint
  - block/blk-throttle.c:tg_print_conf_u64
```
```
In block/blk-iocost.c (ffffffff8151e0c7)
Location: include/linux/cgroup.h:625
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_cost_model_show
  - block/blk-iocost.c:ioc_qos_show
  - block/blk-iocost.c:ioc_weight_show
```
</details>
</li>
</ul>

## Differences
