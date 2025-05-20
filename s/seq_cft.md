# Function: <code>seq_cft</code>

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
Location: include/linux/cgroup.h:500
Inline: True
Inline callers:
  - kernel/cgroup.c:cgroup_seqfile_start
  - kernel/cgroup.c:cgroup_seqfile_next
  - kernel/cgroup.c:cgroup_seqfile_stop
  - kernel/cgroup.c:cgroup_seqfile_show
```
```
In kernel/cpuset.c (ffffffff8111bf1e)
Location: include/linux/cgroup.h:500
Inline: True
Inline callers:
  - kernel/cpuset.c:cpuset_common_seq_show
```
```
In block/blk-cgroup.c (ffffffff813d8736)
Location: include/linux/cgroup.h:500
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_print_stat_bytes
  - block/blk-cgroup.c:blkg_print_stat_ios
  - block/blk-cgroup.c:blkg_print_stat_bytes_recursive
  - block/blk-cgroup.c:blkg_print_stat_ios_recursive
```
```
In block/blk-throttle.c (ffffffff813d9796)
Location: include/linux/cgroup.h:500
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_print_conf_uint
  - block/blk-throttle.c:tg_print_conf_u64
  - block/blk-throttle.c:tg_print_max
```
```
In block/cfq-iosched.c (ffffffff813de316)
Location: include/linux/cgroup.h:500
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
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff81119ba7)
Location: include/linux/cgroup.h:521
Inline: True
Inline callers:
  - kernel/cgroup.c:cgroup_seqfile_show
  - kernel/cgroup.c:cgroup_seqfile_stop
  - kernel/cgroup.c:cgroup_seqfile_next
  - kernel/cgroup.c:cgroup_seqfile_start
```
```
In kernel/cpuset.c (ffffffff81123e10)
Location: include/linux/cgroup.h:521
Inline: True
Inline callers:
  - kernel/cpuset.c:cpuset_common_seq_show
```
```
In block/blk-cgroup.c (ffffffff8141e566)
Location: include/linux/cgroup.h:521
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_print_stat_ios_recursive
  - block/blk-cgroup.c:blkg_print_stat_bytes_recursive
  - block/blk-cgroup.c:blkg_print_stat_ios
  - block/blk-cgroup.c:blkg_print_stat_bytes
```
```
In block/blk-throttle.c (ffffffff8141f676)
Location: include/linux/cgroup.h:521
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_print_max
  - block/blk-throttle.c:tg_print_conf_uint
  - block/blk-throttle.c:tg_print_conf_u64
```
```
In block/cfq-iosched.c (ffffffff81424416)
Location: include/linux/cgroup.h:521
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
In kernel/cgroup.c (ffffffff81121684)
Location: include/linux/cgroup.h:538
Inline: True
Inline callers:
  - kernel/cgroup.c:cgroup_seqfile_show
  - kernel/cgroup.c:cgroup_seqfile_stop
  - kernel/cgroup.c:cgroup_seqfile_next
  - kernel/cgroup.c:cgroup_seqfile_start
```
```
In kernel/cpuset.c (ffffffff8112c2ad)
Location: include/linux/cgroup.h:538
Inline: True
Inline callers:
  - kernel/cpuset.c:cpuset_common_seq_show
```
```
In block/blk-cgroup.c (ffffffff81439b23)
Location: include/linux/cgroup.h:538
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_print_stat_ios_recursive
  - block/blk-cgroup.c:blkg_print_stat_bytes_recursive
  - block/blk-cgroup.c:blkg_print_stat_ios
  - block/blk-cgroup.c:blkg_print_stat_bytes
```
```
In block/blk-throttle.c (ffffffff8143ac33)
Location: include/linux/cgroup.h:538
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_print_max
  - block/blk-throttle.c:tg_print_conf_uint
  - block/blk-throttle.c:tg_print_conf_u64
```
```
In block/cfq-iosched.c (ffffffff8143fe23)
Location: include/linux/cgroup.h:538
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
Location: include/linux/cgroup.h:558
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_seqfile_show
  - kernel/cgroup/cgroup.c:cgroup_seqfile_stop
  - kernel/cgroup/cgroup.c:cgroup_seqfile_next
  - kernel/cgroup/cgroup.c:cgroup_seqfile_start
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8112a14a)
Location: include/linux/cgroup.h:558
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
```
```
In kernel/cgroup/rdma.c (ffffffff8112bb94)
Location: include/linux/cgroup.h:558
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_read
```
```
In kernel/cgroup/cpuset.c (ffffffff8112d51d)
Location: include/linux/cgroup.h:558
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_common_seq_show
```
```
In block/blk-cgroup.c (ffffffff81447293)
Location: include/linux/cgroup.h:558
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_print_stat_ios_recursive
  - block/blk-cgroup.c:blkg_print_stat_bytes_recursive
  - block/blk-cgroup.c:blkg_print_stat_ios
  - block/blk-cgroup.c:blkg_print_stat_bytes
```
```
In block/blk-throttle.c (ffffffff81448863)
Location: include/linux/cgroup.h:558
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_print_limit
  - block/blk-throttle.c:tg_print_conf_uint
  - block/blk-throttle.c:tg_print_conf_u64
```
```
In block/cfq-iosched.c (ffffffff8144f0a3)
Location: include/linux/cgroup.h:558
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
In kernel/cgroup/cgroup.c (ffffffff8112d6aa)
Location: include/linux/cgroup.h:595
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_seqfile_show
  - kernel/cgroup/cgroup.c:cgroup_seqfile_stop
  - kernel/cgroup/cgroup.c:cgroup_seqfile_next
  - kernel/cgroup/cgroup.c:cgroup_seqfile_start
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff811371bb)
Location: include/linux/cgroup.h:595
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
```
```
In kernel/cgroup/rdma.c (ffffffff81138994)
Location: include/linux/cgroup.h:595
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_read
```
```
In kernel/cgroup/cpuset.c (ffffffff8113a41d)
Location: include/linux/cgroup.h:595
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_common_seq_show
```
```
In block/blk-cgroup.c (ffffffff81473e73)
Location: include/linux/cgroup.h:595
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_print_stat_ios_recursive
  - block/blk-cgroup.c:blkg_print_stat_bytes_recursive
  - block/blk-cgroup.c:blkg_print_stat_ios
  - block/blk-cgroup.c:blkg_print_stat_bytes
```
```
In block/blk-throttle.c (ffffffff81475413)
Location: include/linux/cgroup.h:595
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_print_limit
  - block/blk-throttle.c:tg_print_conf_uint
  - block/blk-throttle.c:tg_print_conf_u64
```
```
In block/cfq-iosched.c (ffffffff8147b1e3)
Location: include/linux/cgroup.h:595
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
In kernel/cgroup/cgroup.c (ffffffff8113b895)
Location: include/linux/cgroup.h:595
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_seqfile_show
  - kernel/cgroup/cgroup.c:cgroup_seqfile_stop
  - kernel/cgroup/cgroup.c:cgroup_seqfile_next
  - kernel/cgroup/cgroup.c:cgroup_seqfile_start
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff811459bb)
Location: include/linux/cgroup.h:595
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
```
```
In kernel/cgroup/rdma.c (ffffffff811472b3)
Location: include/linux/cgroup.h:595
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_read
```
```
In kernel/cgroup/cpuset.c (ffffffff81148994)
Location: include/linux/cgroup.h:595
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_common_seq_show
```
```
In block/blk-cgroup.c (ffffffff814a8363)
Location: include/linux/cgroup.h:595
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_print_stat_ios_recursive
  - block/blk-cgroup.c:blkg_print_stat_bytes_recursive
  - block/blk-cgroup.c:blkg_print_stat_ios
  - block/blk-cgroup.c:blkg_print_stat_bytes
```
```
In block/blk-throttle.c (ffffffff814a9893)
Location: include/linux/cgroup.h:595
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_print_limit
  - block/blk-throttle.c:tg_print_conf_uint
  - block/blk-throttle.c:tg_print_conf_u64
```
```
In block/cfq-iosched.c (ffffffff814af8c3)
Location: include/linux/cgroup.h:595
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
In kernel/cgroup/cgroup.c (ffffffff81147095)
Location: include/linux/cgroup.h:618
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_seqfile_show
  - kernel/cgroup/cgroup.c:cgroup_seqfile_stop
  - kernel/cgroup/cgroup.c:cgroup_seqfile_next
  - kernel/cgroup/cgroup.c:cgroup_seqfile_start
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8115157b)
Location: include/linux/cgroup.h:618
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
```
```
In kernel/cgroup/rdma.c (ffffffff81152f83)
Location: include/linux/cgroup.h:618
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_read
```
```
In kernel/cgroup/cpuset.c (ffffffff81154904)
Location: include/linux/cgroup.h:618
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_common_seq_show
```
```
In block/blk-cgroup.c (ffffffff814c1f13)
Location: include/linux/cgroup.h:618
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_print_stat_ios_recursive
  - block/blk-cgroup.c:blkg_print_stat_bytes_recursive
  - block/blk-cgroup.c:blkg_print_stat_ios
  - block/blk-cgroup.c:blkg_print_stat_bytes
```
```
In block/blk-throttle.c (ffffffff814c3d03)
Location: include/linux/cgroup.h:618
Inline: True
Inline callers:
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
In kernel/cgroup/cgroup.c (ffffffff81152355)
Location: include/linux/cgroup.h:631
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_seqfile_show
  - kernel/cgroup/cgroup.c:cgroup_seqfile_stop
  - kernel/cgroup/cgroup.c:cgroup_seqfile_next
  - kernel/cgroup/cgroup.c:cgroup_seqfile_start
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8115c84e)
Location: include/linux/cgroup.h:631
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
```
```
In kernel/cgroup/rdma.c (ffffffff8115f5c2)
Location: include/linux/cgroup.h:631
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_read
```
```
In kernel/cgroup/cpuset.c (ffffffff81160e54)
Location: include/linux/cgroup.h:631
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_common_seq_show
```
```
In block/blk-cgroup.c (ffffffff814f0644)
Location: include/linux/cgroup.h:631
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_print_stat_ios_recursive
  - block/blk-cgroup.c:blkg_print_stat_bytes_recursive
  - block/blk-cgroup.c:blkg_print_stat_ios
  - block/blk-cgroup.c:blkg_print_stat_bytes
```
```
In block/blk-throttle.c (ffffffff814f2473)
Location: include/linux/cgroup.h:631
Inline: True
Inline callers:
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
In kernel/cgroup/cgroup.c (ffffffff8115dfa5)
Location: include/linux/cgroup.h:633
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_seqfile_show
  - kernel/cgroup/cgroup.c:cgroup_seqfile_stop
  - kernel/cgroup/cgroup.c:cgroup_seqfile_next
  - kernel/cgroup/cgroup.c:cgroup_seqfile_start
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81167ffe)
Location: include/linux/cgroup.h:633
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
```
```
In kernel/cgroup/rdma.c (ffffffff8116b222)
Location: include/linux/cgroup.h:633
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_read
```
```
In kernel/cgroup/cpuset.c (ffffffff8116cb24)
Location: include/linux/cgroup.h:633
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_common_seq_show
```
```
In block/blk-cgroup.c (ffffffff81509ae4)
Location: include/linux/cgroup.h:633
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_print_stat_ios_recursive
  - block/blk-cgroup.c:blkg_print_stat_bytes_recursive
  - block/blk-cgroup.c:blkg_print_stat_ios
  - block/blk-cgroup.c:blkg_print_stat_bytes
```
```
In block/blk-throttle.c (ffffffff8150b9e3)
Location: include/linux/cgroup.h:633
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_print_limit
  - block/blk-throttle.c:tg_print_conf_uint
  - block/blk-throttle.c:tg_print_conf_u64
```
```
In block/blk-iocost.c (ffffffff81510437)
Location: include/linux/cgroup.h:633
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
In kernel/cgroup/cgroup.c (ffffffff81171055)
Location: include/linux/cgroup.h:639
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_seqfile_show
  - kernel/cgroup/cgroup.c:cgroup_seqfile_stop
  - kernel/cgroup/cgroup.c:cgroup_seqfile_next
  - kernel/cgroup/cgroup.c:cgroup_seqfile_start
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81179d2f)
Location: include/linux/cgroup.h:639
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
```
```
In kernel/cgroup/rdma.c (ffffffff8117cbd2)
Location: include/linux/cgroup.h:639
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_read
```
```
In kernel/cgroup/cpuset.c (ffffffff8117e444)
Location: include/linux/cgroup.h:639
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_common_seq_show
```
```
In mm/hugetlb_cgroup.c (ffffffff812fef15)
Location: include/linux/cgroup.h:639
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_events_local_show
  - mm/hugetlb_cgroup.c:hugetlb_events_show
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_u64_max
```
```
In block/blk-throttle.c (ffffffff8156ce45)
Location: include/linux/cgroup.h:639
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_print_limit
  - block/blk-throttle.c:tg_print_rwstat_recursive
  - block/blk-throttle.c:tg_print_rwstat
  - block/blk-throttle.c:tg_print_conf_uint
  - block/blk-throttle.c:tg_print_conf_u64
```
```
In block/blk-iocost.c (ffffffff81571757)
Location: include/linux/cgroup.h:639
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
In kernel/cgroup/cgroup.c (ffffffff8116dc05)
Location: include/linux/cgroup.h:639
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_seqfile_show
  - kernel/cgroup/cgroup.c:cgroup_seqfile_stop
  - kernel/cgroup/cgroup.c:cgroup_seqfile_next
  - kernel/cgroup/cgroup.c:cgroup_seqfile_start
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81176a9f)
Location: include/linux/cgroup.h:639
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
```
```
In kernel/cgroup/rdma.c (ffffffff81179a32)
Location: include/linux/cgroup.h:639
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_read
```
```
In kernel/cgroup/cpuset.c (ffffffff8117b2b4)
Location: include/linux/cgroup.h:639
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_common_seq_show
```
```
In mm/hugetlb_cgroup.c (ffffffff8130b255)
Location: include/linux/cgroup.h:639
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_events_local_show
  - mm/hugetlb_cgroup.c:hugetlb_events_show
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_u64_max
```
```
In block/blk-throttle.c (ffffffff815878b5)
Location: include/linux/cgroup.h:639
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_print_limit
  - block/blk-throttle.c:tg_print_rwstat_recursive
  - block/blk-throttle.c:tg_print_rwstat
  - block/blk-throttle.c:tg_print_conf_uint
  - block/blk-throttle.c:tg_print_conf_u64
```
```
In block/blk-iocost.c (ffffffff8158c817)
Location: include/linux/cgroup.h:639
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
In kernel/cgroup/cgroup.c (ffffffff8116e895)
Location: include/linux/cgroup.h:639
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_seqfile_show
  - kernel/cgroup/cgroup.c:cgroup_seqfile_stop
  - kernel/cgroup/cgroup.c:cgroup_seqfile_next
  - kernel/cgroup/cgroup.c:cgroup_seqfile_start
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8117776b)
Location: include/linux/cgroup.h:639
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
```
```
In kernel/cgroup/rdma.c (ffffffff8117a5c2)
Location: include/linux/cgroup.h:639
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_read
```
```
In kernel/cgroup/cpuset.c (ffffffff8117cf34)
Location: include/linux/cgroup.h:639
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_common_seq_show
```
```
In mm/hugetlb_cgroup.c (ffffffff81311ea5)
Location: include/linux/cgroup.h:639
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_events_local_show
  - mm/hugetlb_cgroup.c:hugetlb_events_show
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_u64_max
```
```
In block/blk-throttle.c (ffffffff8158e705)
Location: include/linux/cgroup.h:639
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_print_limit
  - block/blk-throttle.c:tg_print_rwstat_recursive
  - block/blk-throttle.c:tg_print_rwstat
  - block/blk-throttle.c:tg_print_conf_uint
  - block/blk-throttle.c:tg_print_conf_u64
```
```
In block/blk-iocost.c (ffffffff81593557)
Location: include/linux/cgroup.h:639
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
In kernel/cgroup/cgroup.c (ffffffff81194aa5)
Location: include/linux/cgroup.h:639
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_seqfile_show
  - kernel/cgroup/cgroup.c:cgroup_seqfile_stop
  - kernel/cgroup/cgroup.c:cgroup_seqfile_next
  - kernel/cgroup/cgroup.c:cgroup_seqfile_start
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8119f060)
Location: include/linux/cgroup.h:639
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
```
```
In kernel/cgroup/rdma.c (ffffffff811a1f02)
Location: include/linux/cgroup.h:639
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_read
```
```
In kernel/cgroup/cpuset.c (ffffffff811a4ad4)
Location: include/linux/cgroup.h:639
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_common_seq_show
```
```
In mm/hugetlb_cgroup.c (ffffffff8135cc95)
Location: include/linux/cgroup.h:639
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_events_local_show
  - mm/hugetlb_cgroup.c:hugetlb_events_show
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_u64_max
```
```
In block/blk-throttle.c (ffffffff815f4475)
Location: include/linux/cgroup.h:639
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_print_limit
  - block/blk-throttle.c:tg_print_rwstat_recursive
  - block/blk-throttle.c:tg_print_rwstat
  - block/blk-throttle.c:tg_print_conf_uint
  - block/blk-throttle.c:tg_print_conf_u64
```
```
In block/blk-iocost.c (ffffffff815fa6e7)
Location: include/linux/cgroup.h:639
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
In kernel/cgroup/cgroup.c (ffffffff811c5525)
Location: include/linux/cgroup.h:640
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_seqfile_show
  - kernel/cgroup/cgroup.c:cgroup_seqfile_stop
  - kernel/cgroup/cgroup.c:cgroup_seqfile_next
  - kernel/cgroup/cgroup.c:cgroup_seqfile_start
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff811cfae0)
Location: include/linux/cgroup.h:640
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
```
```
In kernel/cgroup/rdma.c (ffffffff811d2942)
Location: include/linux/cgroup.h:640
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_read
```
```
In kernel/cgroup/cpuset.c (ffffffff811d39a4)
Location: include/linux/cgroup.h:640
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_common_seq_show
```
```
In mm/hugetlb_cgroup.c (ffffffff813d6975)
Location: include/linux/cgroup.h:640
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_events_local_show
  - mm/hugetlb_cgroup.c:hugetlb_events_show
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_u64_max
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_numa_stat
```
```
In block/blk-throttle.c (ffffffff816a5e85)
Location: include/linux/cgroup.h:640
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_print_limit
  - block/blk-throttle.c:tg_print_rwstat_recursive
  - block/blk-throttle.c:tg_print_rwstat
  - block/blk-throttle.c:tg_print_conf_uint
  - block/blk-throttle.c:tg_print_conf_u64
```
```
In block/blk-iocost.c (ffffffff816acb36)
Location: include/linux/cgroup.h:640
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
In kernel/cgroup/cgroup.c (ffffffff81207ce5)
Location: include/linux/cgroup.h:580
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_seqfile_show
  - kernel/cgroup/cgroup.c:cgroup_seqfile_stop
  - kernel/cgroup/cgroup.c:cgroup_seqfile_next
  - kernel/cgroup/cgroup.c:cgroup_seqfile_start
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff812134d0)
Location: include/linux/cgroup.h:580
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
```
```
In kernel/cgroup/rdma.c (ffffffff81216852)
Location: include/linux/cgroup.h:580
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_read
```
```
In kernel/cgroup/cpuset.c (ffffffff81217674)
Location: include/linux/cgroup.h:580
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_common_seq_show
```
```
In mm/hugetlb_cgroup.c (ffffffff8145d365)
Location: include/linux/cgroup.h:580
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_events_local_show
  - mm/hugetlb_cgroup.c:hugetlb_events_show
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_u64_max
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_numa_stat
```
```
In block/blk-throttle.c (ffffffff81764e95)
Location: include/linux/cgroup.h:580
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_print_limit
  - block/blk-throttle.c:tg_print_rwstat_recursive
  - block/blk-throttle.c:tg_print_rwstat
  - block/blk-throttle.c:tg_print_conf_uint
  - block/blk-throttle.c:tg_print_conf_u64
```
```
In block/blk-iocost.c (ffffffff8176b686)
Location: include/linux/cgroup.h:580
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
In kernel/cgroup/cgroup.c (ffffffff8121d475)
Location: include/linux/cgroup.h:579
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_seqfile_show
  - kernel/cgroup/cgroup.c:cgroup_seqfile_stop
  - kernel/cgroup/cgroup.c:cgroup_seqfile_next
  - kernel/cgroup/cgroup.c:cgroup_seqfile_start
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81228de0)
Location: include/linux/cgroup.h:579
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
```
```
In kernel/cgroup/rdma.c (ffffffff8122c142)
Location: include/linux/cgroup.h:579
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_read
```
```
In kernel/cgroup/cpuset.c (ffffffff8122cfa4)
Location: include/linux/cgroup.h:579
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_common_seq_show
```
```
In mm/hugetlb_cgroup.c (ffffffff81492115)
Location: include/linux/cgroup.h:579
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_events_local_show
  - mm/hugetlb_cgroup.c:hugetlb_events_show
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_u64_max
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_numa_stat
```
```
In block/blk-throttle.c (ffffffff817a3f75)
Location: include/linux/cgroup.h:579
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_print_limit
  - block/blk-throttle.c:tg_print_rwstat_recursive
  - block/blk-throttle.c:tg_print_rwstat
  - block/blk-throttle.c:tg_print_conf_uint
  - block/blk-throttle.c:tg_print_conf_u64
```
```
In block/blk-iocost.c (ffffffff817aa786)
Location: include/linux/cgroup.h:579
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
In kernel/cgroup/cgroup.c (ffffffff81235005)
Location: include/linux/cgroup.h:577
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_seqfile_show
  - kernel/cgroup/cgroup.c:cgroup_seqfile_stop
  - kernel/cgroup/cgroup.c:cgroup_seqfile_next
  - kernel/cgroup/cgroup.c:cgroup_seqfile_start
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81240c30)
Location: include/linux/cgroup.h:577
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
```
```
In kernel/cgroup/rdma.c (ffffffff81244172)
Location: include/linux/cgroup.h:577
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_read
```
```
In kernel/cgroup/cpuset.c (ffffffff81245164)
Location: include/linux/cgroup.h:577
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_common_seq_show
```
```
In mm/hugetlb_cgroup.c (ffffffff814c1b25)
Location: include/linux/cgroup.h:577
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_events_local_show
  - mm/hugetlb_cgroup.c:hugetlb_events_show
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_u64_max
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_numa_stat
```
```
In block/blk-throttle.c (ffffffff817e7b45)
Location: include/linux/cgroup.h:577
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_print_limit
  - block/blk-throttle.c:tg_print_rwstat_recursive
  - block/blk-throttle.c:tg_print_rwstat
  - block/blk-throttle.c:tg_print_conf_uint
  - block/blk-throttle.c:tg_print_conf_u64
```
```
In block/blk-iocost.c (ffffffff817ee536)
Location: include/linux/cgroup.h:577
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
In kernel/cgroup/cgroup.c (ffff8000101ce6ec)
Location: include/linux/cgroup.h:633
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_seqfile_show
  - kernel/cgroup/cgroup.c:cgroup_seqfile_stop
  - kernel/cgroup/cgroup.c:cgroup_seqfile_next
  - kernel/cgroup/cgroup.c:cgroup_seqfile_start
```
```
In kernel/cgroup/cgroup-v1.c (ffff8000101dab18)
Location: include/linux/cgroup.h:633
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
```
```
In kernel/cgroup/rdma.c (ffff8000101df4a4)
Location: include/linux/cgroup.h:633
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_read
```
```
In kernel/cgroup/cpuset.c (ffff8000101e1368)
Location: include/linux/cgroup.h:633
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_common_seq_show
```
```
In block/blk-cgroup.c (ffff80001060c938)
Location: include/linux/cgroup.h:633
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_print_stat_ios_recursive
  - block/blk-cgroup.c:blkg_print_stat_bytes_recursive
  - block/blk-cgroup.c:blkg_print_stat_ios
  - block/blk-cgroup.c:blkg_print_stat_bytes
```
```
In block/blk-throttle.c (ffff80001060f638)
Location: include/linux/cgroup.h:633
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_print_limit
  - block/blk-throttle.c:tg_print_conf_uint
  - block/blk-throttle.c:tg_print_conf_u64
```
```
In block/blk-iocost.c (ffff800010613bf0)
Location: include/linux/cgroup.h:633
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
In kernel/cgroup/cgroup.c (c0411c4c)
Location: include/linux/cgroup.h:633
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_seqfile_show
  - kernel/cgroup/cgroup.c:cgroup_seqfile_stop
  - kernel/cgroup/cgroup.c:cgroup_seqfile_next
  - kernel/cgroup/cgroup.c:cgroup_seqfile_start
```
```
In kernel/cgroup/cgroup-v1.c (c041d118)
Location: include/linux/cgroup.h:633
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
```
```
In kernel/cgroup/rdma.c (c0420db8)
Location: include/linux/cgroup.h:633
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_read
```
```
In kernel/cgroup/cpuset.c (c0421a34)
Location: include/linux/cgroup.h:633
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_common_seq_show
```
```
In block/blk-cgroup.c (c07b6854)
Location: include/linux/cgroup.h:633
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_print_stat_ios_recursive
  - block/blk-cgroup.c:blkg_print_stat_bytes_recursive
  - block/blk-cgroup.c:blkg_print_stat_ios
  - block/blk-cgroup.c:blkg_print_stat_bytes
```
```
In block/blk-throttle.c (c07b9ce0)
Location: include/linux/cgroup.h:633
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_print_limit
  - block/blk-throttle.c:tg_print_conf_uint
  - block/blk-throttle.c:tg_print_conf_u64
```
```
In block/blk-iocost.c (c07bf428)
Location: include/linux/cgroup.h:633
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
Location: include/linux/cgroup.h:633
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_seqfile_show
  - kernel/cgroup/cgroup.c:cgroup_seqfile_stop
  - kernel/cgroup/cgroup.c:cgroup_seqfile_next
  - kernel/cgroup/cgroup.c:cgroup_seqfile_start
```
```
In kernel/cgroup/cgroup-v1.c (c000000000248c94)
Location: include/linux/cgroup.h:633
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
```
```
In kernel/cgroup/rdma.c (c00000000024d66c)
Location: include/linux/cgroup.h:633
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_read
```
```
In kernel/cgroup/cpuset.c (c00000000024fc6c)
Location: include/linux/cgroup.h:633
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_common_seq_show
```
```
In block/blk-cgroup.c (c0000000007a9950)
Location: include/linux/cgroup.h:633
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_print_stat_ios_recursive
  - block/blk-cgroup.c:blkg_print_stat_bytes_recursive
  - block/blk-cgroup.c:blkg_print_stat_ios
  - block/blk-cgroup.c:blkg_print_stat_bytes
```
```
In block/blk-throttle.c (c0000000007aca30)
Location: include/linux/cgroup.h:633
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_print_limit
  - block/blk-throttle.c:tg_print_conf_uint
  - block/blk-throttle.c:tg_print_conf_u64
```
```
In block/blk-iocost.c (c0000000007b2f30)
Location: include/linux/cgroup.h:633
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
Location: include/linux/cgroup.h:633
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_seqfile_show
  - kernel/cgroup/cgroup.c:cgroup_seqfile_stop
  - kernel/cgroup/cgroup.c:cgroup_seqfile_next
  - kernel/cgroup/cgroup.c:cgroup_seqfile_start
```
```
In kernel/cgroup/cgroup-v1.c (ffffffe000153066)
Location: include/linux/cgroup.h:633
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
```
```
In kernel/cgroup/rdma.c (ffffffe000156568)
Location: include/linux/cgroup.h:633
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_read
```
```
In kernel/cgroup/cpuset.c (ffffffe000158238)
Location: include/linux/cgroup.h:633
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_common_seq_show
```
```
In block/blk-cgroup.c (ffffffe0004455ae)
Location: include/linux/cgroup.h:633
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_print_stat_ios_recursive
  - block/blk-cgroup.c:blkg_print_stat_bytes_recursive
  - block/blk-cgroup.c:blkg_print_stat_ios
  - block/blk-cgroup.c:blkg_print_stat_bytes
```
```
In block/blk-throttle.c (ffffffe0004474f8)
Location: include/linux/cgroup.h:633
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_print_limit
  - block/blk-throttle.c:tg_print_conf_uint
  - block/blk-throttle.c:tg_print_conf_u64
```
```
In block/blk-iocost.c (ffffffe00044b5b2)
Location: include/linux/cgroup.h:633
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
In kernel/cgroup/cgroup.c (ffffffff811565c5)
Location: include/linux/cgroup.h:633
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_seqfile_show
  - kernel/cgroup/cgroup.c:cgroup_seqfile_stop
  - kernel/cgroup/cgroup.c:cgroup_seqfile_next
  - kernel/cgroup/cgroup.c:cgroup_seqfile_start
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8116061e)
Location: include/linux/cgroup.h:633
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
```
```
In kernel/cgroup/rdma.c (ffffffff81163842)
Location: include/linux/cgroup.h:633
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_read
```
```
In kernel/cgroup/cpuset.c (ffffffff81165144)
Location: include/linux/cgroup.h:633
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_common_seq_show
```
```
In block/blk-cgroup.c (ffffffff815020c4)
Location: include/linux/cgroup.h:633
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_print_stat_ios_recursive
  - block/blk-cgroup.c:blkg_print_stat_bytes_recursive
  - block/blk-cgroup.c:blkg_print_stat_ios
  - block/blk-cgroup.c:blkg_print_stat_bytes
```
```
In block/blk-throttle.c (ffffffff81503fc3)
Location: include/linux/cgroup.h:633
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_print_limit
  - block/blk-throttle.c:tg_print_conf_uint
  - block/blk-throttle.c:tg_print_conf_u64
```
```
In block/blk-iocost.c (ffffffff81508a17)
Location: include/linux/cgroup.h:633
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
In kernel/cgroup/cgroup.c (ffffffff811498e5)
Location: include/linux/cgroup.h:633
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_seqfile_show
  - kernel/cgroup/cgroup.c:cgroup_seqfile_stop
  - kernel/cgroup/cgroup.c:cgroup_seqfile_next
  - kernel/cgroup/cgroup.c:cgroup_seqfile_start
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8115388e)
Location: include/linux/cgroup.h:633
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
```
```
In kernel/cgroup/rdma.c (ffffffff81156a92)
Location: include/linux/cgroup.h:633
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_read
```
```
In kernel/cgroup/cpuset.c (ffffffff811580a4)
Location: include/linux/cgroup.h:633
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_common_seq_show
```
```
In block/blk-cgroup.c (ffffffff814f25d4)
Location: include/linux/cgroup.h:633
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_print_stat_ios_recursive
  - block/blk-cgroup.c:blkg_print_stat_bytes_recursive
  - block/blk-cgroup.c:blkg_print_stat_ios
  - block/blk-cgroup.c:blkg_print_stat_bytes
```
```
In block/blk-throttle.c (ffffffff814f4483)
Location: include/linux/cgroup.h:633
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_print_limit
  - block/blk-throttle.c:tg_print_conf_uint
  - block/blk-throttle.c:tg_print_conf_u64
```
```
In block/blk-iocost.c (ffffffff814f8ec7)
Location: include/linux/cgroup.h:633
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
In kernel/cgroup/cgroup.c (ffffffff81154395)
Location: include/linux/cgroup.h:633
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_seqfile_show
  - kernel/cgroup/cgroup.c:cgroup_seqfile_stop
  - kernel/cgroup/cgroup.c:cgroup_seqfile_next
  - kernel/cgroup/cgroup.c:cgroup_seqfile_start
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8115e3ee)
Location: include/linux/cgroup.h:633
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
```
```
In kernel/cgroup/rdma.c (ffffffff81161612)
Location: include/linux/cgroup.h:633
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_read
```
```
In kernel/cgroup/cpuset.c (ffffffff81162f14)
Location: include/linux/cgroup.h:633
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_common_seq_show
```
```
In block/blk-cgroup.c (ffffffff814fe154)
Location: include/linux/cgroup.h:633
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_print_stat_ios_recursive
  - block/blk-cgroup.c:blkg_print_stat_bytes_recursive
  - block/blk-cgroup.c:blkg_print_stat_ios
  - block/blk-cgroup.c:blkg_print_stat_bytes
```
```
In block/blk-throttle.c (ffffffff81500053)
Location: include/linux/cgroup.h:633
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_print_limit
  - block/blk-throttle.c:tg_print_conf_uint
  - block/blk-throttle.c:tg_print_conf_u64
```
```
In block/blk-iocost.c (ffffffff81504aa7)
Location: include/linux/cgroup.h:633
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
In kernel/cgroup/cgroup.c (ffffffff81161295)
Location: include/linux/cgroup.h:633
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_seqfile_show
  - kernel/cgroup/cgroup.c:cgroup_seqfile_stop
  - kernel/cgroup/cgroup.c:cgroup_seqfile_next
  - kernel/cgroup/cgroup.c:cgroup_seqfile_start
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8116b81e)
Location: include/linux/cgroup.h:633
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
```
```
In kernel/cgroup/rdma.c (ffffffff8116ea62)
Location: include/linux/cgroup.h:633
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_read
```
```
In kernel/cgroup/cpuset.c (ffffffff8116f4b4)
Location: include/linux/cgroup.h:633
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_common_seq_show
```
```
In block/blk-cgroup.c (ffffffff81516414)
Location: include/linux/cgroup.h:633
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_print_stat_ios_recursive
  - block/blk-cgroup.c:blkg_print_stat_bytes_recursive
  - block/blk-cgroup.c:blkg_print_stat_ios
  - block/blk-cgroup.c:blkg_print_stat_bytes
```
```
In block/blk-throttle.c (ffffffff81519223)
Location: include/linux/cgroup.h:633
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_print_limit
  - block/blk-throttle.c:tg_print_conf_uint
  - block/blk-throttle.c:tg_print_conf_u64
```
```
In block/blk-iocost.c (ffffffff8151e0c7)
Location: include/linux/cgroup.h:633
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
