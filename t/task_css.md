# Function: <code>task_css</code>

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
In kernel/sched/cpuacct.c (ffffffff810c99b9)
Location: include/linux/cgroup.h:428
Inline: True
Inline callers:
  - kernel/sched/cpuacct.c:cpuacct_charge
  - kernel/sched/cpuacct.c:cpuacct_account_field
```
```
In kernel/cgroup_freezer.c (ffffffff81119ca0)
Location: include/linux/cgroup.h:428
Inline: True
Inline callers:
  - kernel/cgroup_freezer.c:freezer_fork
  - kernel/cgroup_freezer.c:cgroup_freezing
```
```
In kernel/cgroup_pids.c (ffffffff8111a544)
Location: include/linux/cgroup.h:428
Inline: True
Inline callers:
  - kernel/cgroup_pids.c:pids_can_attach
  - kernel/cgroup_pids.c:pids_cancel_attach
  - kernel/cgroup_pids.c:pids_free
```
```
In kernel/cpuset.c (ffffffff8111b53f)
Location: include/linux/cgroup.h:428
Inline: True
Inline callers:
  - kernel/cpuset.c:cpuset_can_attach
  - kernel/cpuset.c:current_cpuset_is_being_rebound
  - kernel/cpuset.c:cpuset_cpus_allowed
  - kernel/cpuset.c:cpuset_cpus_allowed_fallback
  - kernel/cpuset.c:cpuset_mems_allowed
  - kernel/cpuset.c:__cpuset_node_allowed
  - kernel/cpuset.c:cpuset_print_current_mems_allowed
  - kernel/cpuset.c:__cpuset_memory_pressure_bump
  - kernel/cpuset.c:proc_cpuset_show
```
```
In mm/page-writeback.c (ffffffff8119a56d)
Location: include/linux/cgroup.h:428
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/memcontrol.c (ffffffff811f996e)
Location: include/linux/cgroup.h:428
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mem_cgroup_from_mm
  - mm/memcontrol.c:mem_cgroup_can_attach
  - mm/memcontrol.c:task_in_mem_cgroup
  - mm/memcontrol.c:mem_cgroup_print_oom_info
```
```
In mm/hugetlb_cgroup.c (ffffffff812012ea)
Location: include/linux/cgroup.h:428
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In fs/fs-writeback.c (ffffffff8123ab28)
Location: include/linux/cgroup.h:428
Inline: True
Inline callers:
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In security/device_cgroup.c (ffffffff81395636)
Location: include/linux/cgroup.h:428
Inline: True
Inline callers:
  - security/device_cgroup.c:__devcgroup_check_permission
```
```
In block/bio.c (ffffffff813b0fa1)
Location: include/linux/cgroup.h:428
Inline: True
Inline callers:
  - block/bio.c:bio_associate_current
```
```
In block/blk-core.c (ffffffff813b64fc)
Location: include/linux/cgroup.h:428
Inline: True
Inline callers:
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:get_request
```
```
In block/cfq-iosched.c (ffffffff813e1aa4)
Location: include/linux/cgroup.h:428
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_get_queue
  - block/cfq-iosched.c:check_blkcg_changed
```
```
In net/core/sock.c (ffffffff8170140c)
Location: include/linux/cgroup.h:428
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
  - net/core/sock.c:sk_alloc
```
```
In net/core/scm.c (ffffffff8170ec6d)
Location: include/linux/cgroup.h:428
Inline: True
Inline callers:
  - net/core/scm.c:scm_detach_fds
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
In kernel/sched/cpuacct.c (ffffffff810ce2c5)
Location: include/linux/cgroup.h:432
Inline: True
Inline callers:
  - kernel/sched/cpuacct.c:cpuacct_account_field
  - kernel/sched/cpuacct.c:cpuacct_charge
```
```
In kernel/cgroup_freezer.c (ffffffff81121ab0)
Location: include/linux/cgroup.h:432
Inline: True
Inline callers:
  - kernel/cgroup_freezer.c:freezer_fork
  - kernel/cgroup_freezer.c:cgroup_freezing
```
```
In kernel/cgroup_pids.c (ffffffff8112255a)
Location: include/linux/cgroup.h:432
Inline: True
Inline callers:
  - kernel/cgroup_pids.c:pids_free
  - kernel/cgroup_pids.c:pids_can_fork
  - kernel/cgroup_pids.c:pids_cancel_attach
  - kernel/cgroup_pids.c:pids_can_attach
```
```
In kernel/cpuset.c (ffffffff8112583c)
Location: include/linux/cgroup.h:432
Inline: True
Inline callers:
  - kernel/cpuset.c:proc_cpuset_show
  - kernel/cpuset.c:__cpuset_memory_pressure_bump
  - kernel/cpuset.c:cpuset_print_current_mems_allowed
  - kernel/cpuset.c:__cpuset_node_allowed
  - kernel/cpuset.c:cpuset_mems_allowed
  - kernel/cpuset.c:cpuset_cpus_allowed_fallback
  - kernel/cpuset.c:cpuset_cpus_allowed
  - kernel/cpuset.c:cpuset_can_attach
  - kernel/cpuset.c:current_cpuset_is_being_rebound
```
```
In mm/page-writeback.c (ffffffff811aee7d)
Location: include/linux/cgroup.h:432
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/memcontrol.c (ffffffff81222f03)
Location: include/linux/cgroup.h:432
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_print_oom_info
  - mm/memcontrol.c:task_in_mem_cgroup
  - mm/memcontrol.c:get_mem_cgroup_from_mm
```
```
In mm/hugetlb_cgroup.c (ffffffff81225aa3)
Location: include/linux/cgroup.h:432
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In fs/fs-writeback.c (ffffffff812629c8)
Location: include/linux/cgroup.h:432
Inline: True
Inline callers:
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In security/device_cgroup.c (ffffffff813d1386)
Location: include/linux/cgroup.h:432
Inline: True
Inline callers:
  - security/device_cgroup.c:__devcgroup_check_permission
```
```
In block/bio.c (ffffffff813f4991)
Location: include/linux/cgroup.h:432
Inline: True
Inline callers:
  - block/bio.c:bio_associate_current
```
```
In block/blk-core.c (ffffffff813fb2fa)
Location: include/linux/cgroup.h:432
Inline: True
Inline callers:
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:get_request
```
```
In block/cfq-iosched.c (ffffffff81427ce5)
Location: include/linux/cgroup.h:432
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_get_queue
  - block/cfq-iosched.c:check_blkcg_changed
```
```
In net/core/sock.c (ffffffff817676ea)
Location: include/linux/cgroup.h:432
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
  - net/core/sock.c:sk_alloc
```
```
In net/core/scm.c (ffffffff81776531)
Location: include/linux/cgroup.h:432
Inline: True
Inline callers:
  - net/core/scm.c:scm_detach_fds
  - net/core/scm.c:scm_detach_fds
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
In kernel/sched/cpuacct.c (ffffffff810d42e5)
Location: include/linux/cgroup.h:432
Inline: True
Inline callers:
  - kernel/sched/cpuacct.c:cpuacct_account_field
  - kernel/sched/cpuacct.c:cpuacct_charge
```
```
In kernel/cgroup_freezer.c (ffffffff8112a0f0)
Location: include/linux/cgroup.h:432
Inline: True
Inline callers:
  - kernel/cgroup_freezer.c:freezer_fork
  - kernel/cgroup_freezer.c:cgroup_freezing
```
```
In kernel/cgroup_pids.c (ffffffff8112ab7a)
Location: include/linux/cgroup.h:432
Inline: True
Inline callers:
  - kernel/cgroup_pids.c:pids_free
  - kernel/cgroup_pids.c:pids_cancel_attach
  - kernel/cgroup_pids.c:pids_can_attach
```
```
In kernel/cpuset.c (ffffffff8112f228)
Location: include/linux/cgroup.h:432
Inline: True
Inline callers:
  - kernel/cpuset.c:proc_cpuset_show
  - kernel/cpuset.c:__cpuset_memory_pressure_bump
  - kernel/cpuset.c:cpuset_print_current_mems_allowed
  - kernel/cpuset.c:__cpuset_node_allowed
  - kernel/cpuset.c:cpuset_mems_allowed
  - kernel/cpuset.c:cpuset_cpus_allowed_fallback
  - kernel/cpuset.c:cpuset_cpus_allowed
  - kernel/cpuset.c:cpuset_can_attach
  - kernel/cpuset.c:current_cpuset_is_being_rebound
```
```
In mm/page-writeback.c (ffffffff811bf52d)
Location: include/linux/cgroup.h:432
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/memcontrol.c (ffffffff81236799)
Location: include/linux/cgroup.h:432
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:mem_cgroup_print_oom_info
  - mm/memcontrol.c:task_in_mem_cgroup
  - mm/memcontrol.c:get_mem_cgroup_from_mm
```
```
In mm/hugetlb_cgroup.c (ffffffff81238083)
Location: include/linux/cgroup.h:432
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In fs/fs-writeback.c (ffffffff81275e18)
Location: include/linux/cgroup.h:432
Inline: True
Inline callers:
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In security/device_cgroup.c (ffffffff813e8ab6)
Location: include/linux/cgroup.h:432
Inline: True
Inline callers:
  - security/device_cgroup.c:__devcgroup_check_permission
```
```
In block/bio.c (ffffffff8140e381)
Location: include/linux/cgroup.h:432
Inline: True
Inline callers:
  - block/bio.c:bio_associate_current
```
```
In block/blk-core.c (ffffffff81414cf9)
Location: include/linux/cgroup.h:432
Inline: True
Inline callers:
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:get_request
```
```
In block/cfq-iosched.c (ffffffff814418c2)
Location: include/linux/cgroup.h:432
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_get_queue
  - block/cfq-iosched.c:check_blkcg_changed
  - block/cfq-iosched.c:check_blkcg_changed
```
```
In net/core/sock.c (ffffffff817946f2)
Location: include/linux/cgroup.h:432
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
  - net/core/sock.c:sk_alloc
```
```
In net/core/scm.c (ffffffff817a37b1)
Location: include/linux/cgroup.h:432
Inline: True
Inline callers:
  - net/core/scm.c:scm_detach_fds
  - net/core/scm.c:scm_detach_fds
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
In kernel/sched/cpuacct.c (ffffffff810d3475)
Location: include/linux/cgroup.h:452
Inline: True
Inline callers:
  - kernel/sched/cpuacct.c:cpuacct_account_field
  - kernel/sched/cpuacct.c:cpuacct_charge
```
```
In kernel/cgroup/freezer.c (ffffffff8112b405)
Location: include/linux/cgroup.h:452
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_freezing
```
```
In kernel/cgroup/pids.c (ffffffff8112b89a)
Location: include/linux/cgroup.h:452
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_free
  - kernel/cgroup/pids.c:pids_cancel_attach
  - kernel/cgroup/pids.c:pids_can_attach
```
```
In kernel/cgroup/rdma.c (ffffffff8112bebe)
Location: include/linux/cgroup.h:452
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffff811308a8)
Location: include/linux/cgroup.h:452
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:__cpuset_memory_pressure_bump
  - kernel/cgroup/cpuset.c:cpuset_print_current_mems_allowed
  - kernel/cgroup/cpuset.c:__cpuset_node_allowed
  - kernel/cgroup/cpuset.c:cpuset_mems_allowed
  - kernel/cgroup/cpuset.c:cpuset_cpus_allowed_fallback
  - kernel/cgroup/cpuset.c:cpuset_cpus_allowed
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/cgroup/cpuset.c:current_cpuset_is_being_rebound
```
```
In mm/page-writeback.c (ffffffff811c7274)
Location: include/linux/cgroup.h:452
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/memcontrol.c (ffffffff8124224a)
Location: include/linux/cgroup.h:452
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:mem_cgroup_print_oom_info
  - mm/memcontrol.c:task_in_mem_cgroup
  - mm/memcontrol.c:get_mem_cgroup_from_mm
```
```
In mm/hugetlb_cgroup.c (ffffffff81243cf3)
Location: include/linux/cgroup.h:452
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In fs/fs-writeback.c (ffffffff81283297)
Location: include/linux/cgroup.h:452
Inline: True
Inline callers:
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In security/device_cgroup.c (ffffffff813f4e56)
Location: include/linux/cgroup.h:452
Inline: True
Inline callers:
  - security/device_cgroup.c:__devcgroup_check_permission
```
```
In block/bio.c (ffffffff8141bf72)
Location: include/linux/cgroup.h:452
Inline: True
Inline callers:
  - block/bio.c:bio_associate_current
```
```
In block/blk-core.c (ffffffff814249d5)
Location: include/linux/cgroup.h:452
Inline: True
Inline callers:
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:get_request
```
```
In block/cfq-iosched.c (ffffffff81450a78)
Location: include/linux/cgroup.h:452
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_get_queue
  - block/cfq-iosched.c:check_blkcg_changed
```
```
In net/core/sock.c (ffffffff817b4952)
Location: include/linux/cgroup.h:452
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
  - net/core/sock.c:sk_alloc
```
```
In net/core/scm.c (ffffffff817c1840)
Location: include/linux/cgroup.h:452
Inline: True
Inline callers:
  - net/core/scm.c:scm_detach_fds
  - net/core/scm.c:scm_detach_fds
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
In kernel/sched/cpuacct.c (ffffffff810db045)
Location: include/linux/cgroup.h:474
Inline: True
Inline callers:
  - kernel/sched/cpuacct.c:cpuacct_account_field
  - kernel/sched/cpuacct.c:cpuacct_charge
```
```
In kernel/cgroup/freezer.c (ffffffff81138205)
Location: include/linux/cgroup.h:474
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_freezing
```
```
In kernel/cgroup/pids.c (ffffffff8113869a)
Location: include/linux/cgroup.h:474
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_free
  - kernel/cgroup/pids.c:pids_cancel_attach
  - kernel/cgroup/pids.c:pids_can_attach
```
```
In kernel/cgroup/rdma.c (ffffffff81138cce)
Location: include/linux/cgroup.h:474
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffff8113d7e8)
Location: include/linux/cgroup.h:474
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:__cpuset_memory_pressure_bump
  - kernel/cgroup/cpuset.c:cpuset_print_current_mems_allowed
  - kernel/cgroup/cpuset.c:__cpuset_node_allowed
  - kernel/cgroup/cpuset.c:cpuset_mems_allowed
  - kernel/cgroup/cpuset.c:cpuset_cpus_allowed_fallback
  - kernel/cgroup/cpuset.c:cpuset_cpus_allowed
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/cgroup/cpuset.c:current_cpuset_is_being_rebound
```
```
In mm/page-writeback.c (ffffffff811dc084)
Location: include/linux/cgroup.h:474
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/memcontrol.c (ffffffff8126203e)
Location: include/linux/cgroup.h:474
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:mem_cgroup_print_oom_info
  - mm/memcontrol.c:task_in_mem_cgroup
  - mm/memcontrol.c:get_mem_cgroup_from_mm
```
```
In mm/hugetlb_cgroup.c (ffffffff81263b43)
Location: include/linux/cgroup.h:474
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In fs/fs-writeback.c (ffffffff812a5e07)
Location: include/linux/cgroup.h:474
Inline: True
Inline callers:
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In security/device_cgroup.c (ffffffff8141d066)
Location: include/linux/cgroup.h:474
Inline: True
Inline callers:
  - security/device_cgroup.c:__devcgroup_check_permission
```
```
In block/blk-core.c (ffffffff8144db10)
Location: include/linux/cgroup.h:474
Inline: True
Inline callers:
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:get_request
```
```
In block/blk-mq.c (ffffffff8145bf7a)
Location: include/linux/cgroup.h:474
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_bio_to_request
```
```
In block/cfq-iosched.c (ffffffff8147e84b)
Location: include/linux/cgroup.h:474
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_set_request
  - block/cfq-iosched.c:cfq_get_queue
```
```
In net/core/sock.c (ffffffff8182cbb2)
Location: include/linux/cgroup.h:474
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
  - net/core/sock.c:sk_alloc
```
```
In net/core/scm.c (ffffffff8183b248)
Location: include/linux/cgroup.h:474
Inline: True
Inline callers:
  - net/core/scm.c:scm_detach_fds
  - net/core/scm.c:scm_detach_fds
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
In kernel/sched/cpuacct.c (ffffffff810e31b5)
Location: include/linux/cgroup.h:474
Inline: True
Inline callers:
  - kernel/sched/cpuacct.c:cpuacct_account_field
  - kernel/sched/cpuacct.c:cpuacct_charge
```
```
In kernel/cgroup/freezer.c (ffffffff81146b25)
Location: include/linux/cgroup.h:474
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_freezing
```
```
In kernel/cgroup/pids.c (ffffffff81146f95)
Location: include/linux/cgroup.h:474
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_free
  - kernel/cgroup/pids.c:pids_cancel_attach
  - kernel/cgroup/pids.c:pids_can_attach
```
```
In kernel/cgroup/rdma.c (ffffffff81147918)
Location: include/linux/cgroup.h:474
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffff8114c0a8)
Location: include/linux/cgroup.h:474
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:__cpuset_memory_pressure_bump
  - kernel/cgroup/cpuset.c:cpuset_print_current_mems_allowed
  - kernel/cgroup/cpuset.c:__cpuset_node_allowed
  - kernel/cgroup/cpuset.c:cpuset_mems_allowed
  - kernel/cgroup/cpuset.c:cpuset_cpus_allowed_fallback
  - kernel/cgroup/cpuset.c:cpuset_cpus_allowed
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/cgroup/cpuset.c:current_cpuset_is_being_rebound
```
```
In mm/page-writeback.c (ffffffff811fda3a)
Location: include/linux/cgroup.h:474
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/memcontrol.c (ffffffff8128603e)
Location: include/linux/cgroup.h:474
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:mem_cgroup_print_oom_info
  - mm/memcontrol.c:task_in_mem_cgroup
  - mm/memcontrol.c:get_mem_cgroup_from_mm
```
```
In mm/hugetlb_cgroup.c (ffffffff81287e63)
Location: include/linux/cgroup.h:474
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In fs/fs-writeback.c (ffffffff812cc9bb)
Location: include/linux/cgroup.h:474
Inline: True
Inline callers:
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In security/device_cgroup.c (ffffffff8144f329)
Location: include/linux/cgroup.h:474
Inline: True
Inline callers:
  - security/device_cgroup.c:__devcgroup_check_permission
```
```
In block/blk-core.c (ffffffff81482955)
Location: include/linux/cgroup.h:474
Inline: True
Inline callers:
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:get_request
```
```
In block/blk-mq.c (ffffffff8148eb49)
Location: include/linux/cgroup.h:474
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_bio_to_request
```
```
In block/cfq-iosched.c (ffffffff814b275c)
Location: include/linux/cgroup.h:474
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_set_request
  - block/cfq-iosched.c:cfq_get_queue
```
```
In net/core/sock.c (ffffffff8187762b)
Location: include/linux/cgroup.h:474
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
  - net/core/sock.c:sk_alloc
```
```
In net/core/scm.c (ffffffff818858ec)
Location: include/linux/cgroup.h:474
Inline: True
Inline callers:
  - net/core/scm.c:scm_detach_fds
  - net/core/scm.c:scm_detach_fds
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
In kernel/sched/cpuacct.c (ffffffff810ed8e5)
Location: include/linux/cgroup.h:476
Inline: True
Inline callers:
  - kernel/sched/cpuacct.c:cpuacct_account_field
  - kernel/sched/cpuacct.c:cpuacct_charge
```
```
In kernel/cgroup/freezer.c (ffffffff811526a5)
Location: include/linux/cgroup.h:476
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_freezing
```
```
In kernel/cgroup/pids.c (ffffffff81152b15)
Location: include/linux/cgroup.h:476
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_free
  - kernel/cgroup/pids.c:pids_cancel_attach
  - kernel/cgroup/pids.c:pids_can_attach
```
```
In kernel/cgroup/rdma.c (ffffffff811531d8)
Location: include/linux/cgroup.h:476
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffff81158cf8)
Location: include/linux/cgroup.h:476
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:__cpuset_memory_pressure_bump
  - kernel/cgroup/cpuset.c:cpuset_print_current_mems_allowed
  - kernel/cgroup/cpuset.c:__cpuset_node_allowed
  - kernel/cgroup/cpuset.c:cpuset_mems_allowed
  - kernel/cgroup/cpuset.c:cpuset_cpus_allowed_fallback
  - kernel/cgroup/cpuset.c:cpuset_cpus_allowed
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/cgroup/cpuset.c:current_cpuset_is_being_rebound
```
```
In mm/page-writeback.c (ffffffff81210563)
Location: include/linux/cgroup.h:476
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/readahead.c (ffffffff81212ce2)
Location: include/linux/cgroup.h:476
Inline: True
```
```
In mm/swapfile.c (ffffffff81262aab)
Location: include/linux/cgroup.h:476
Inline: True
Inline callers:
  - mm/swapfile.c:mem_cgroup_throttle_swaprate
```
```
In mm/memcontrol.c (ffffffff8129af9f)
Location: include/linux/cgroup.h:476
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:mem_cgroup_get_oom_group
  - mm/memcontrol.c:mem_cgroup_print_oom_context
  - mm/memcontrol.c:task_in_mem_cgroup
```
```
In mm/hugetlb_cgroup.c (ffffffff8129cdb3)
Location: include/linux/cgroup.h:476
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In fs/fs-writeback.c (ffffffff812e1cdb)
Location: include/linux/cgroup.h:476
Inline: True
Inline callers:
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In security/device_cgroup.c (ffffffff8146c309)
Location: include/linux/cgroup.h:476
Inline: True
Inline callers:
  - security/device_cgroup.c:__devcgroup_check_permission
```
```
In block/bio.c (ffffffff81498374)
Location: include/linux/cgroup.h:476
Inline: True
Inline callers:
  - block/bio.c:bio_associate_blkg
```
```
In block/blk-cgroup.c (ffffffff814c337e)
Location: include/linux/cgroup.h:476
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
```
```
In net/core/sock.c (ffffffff81897a7b)
Location: include/linux/cgroup.h:476
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
  - net/core/sock.c:sk_alloc
```
```
In net/core/scm.c (ffffffff818a601c)
Location: include/linux/cgroup.h:476
Inline: True
Inline callers:
  - net/core/scm.c:scm_detach_fds
  - net/core/scm.c:scm_detach_fds
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
In kernel/sched/cpuacct.c (ffffffff810f4669)
Location: include/linux/cgroup.h:483
Inline: True
Inline callers:
  - kernel/sched/cpuacct.c:cpuacct_account_field
  - kernel/sched/cpuacct.c:cpuacct_charge
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff8115ed09)
Location: include/linux/cgroup.h:483
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:cgroup_freezing
```
```
In kernel/cgroup/pids.c (ffffffff8115f165)
Location: include/linux/cgroup.h:483
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_release
  - kernel/cgroup/pids.c:pids_cancel_attach
  - kernel/cgroup/pids.c:pids_can_attach
```
```
In kernel/cgroup/rdma.c (ffffffff8115fb22)
Location: include/linux/cgroup.h:483
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffff81165448)
Location: include/linux/cgroup.h:483
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:__cpuset_memory_pressure_bump
  - kernel/cgroup/cpuset.c:cpuset_print_current_mems_allowed
  - kernel/cgroup/cpuset.c:__cpuset_node_allowed
  - kernel/cgroup/cpuset.c:cpuset_mems_allowed
  - kernel/cgroup/cpuset.c:cpuset_cpus_allowed_fallback
  - kernel/cgroup/cpuset.c:cpuset_cpus_allowed
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/cgroup/cpuset.c:current_cpuset_is_being_rebound
```
```
In mm/page-writeback.c (ffffffff8121fc03)
Location: include/linux/cgroup.h:483
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/readahead.c (ffffffff812226e0)
Location: include/linux/cgroup.h:483
Inline: True
```
```
In mm/swapfile.c (ffffffff8127da55)
Location: include/linux/cgroup.h:483
Inline: True
Inline callers:
  - mm/swapfile.c:mem_cgroup_throttle_swaprate
```
```
In mm/memcontrol.c (ffffffff812b626f)
Location: include/linux/cgroup.h:483
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:mem_cgroup_get_oom_group
  - mm/memcontrol.c:mem_cgroup_print_oom_context
```
```
In mm/hugetlb_cgroup.c (ffffffff812b7f53)
Location: include/linux/cgroup.h:483
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In fs/fs-writeback.c (ffffffff81300298)
Location: include/linux/cgroup.h:483
Inline: True
Inline callers:
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In security/device_cgroup.c (ffffffff814999e5)
Location: include/linux/cgroup.h:483
Inline: True
Inline callers:
  - security/device_cgroup.c:__devcgroup_check_permission
```
```
In block/bio.c (ffffffff814c61f4)
Location: include/linux/cgroup.h:483
Inline: True
Inline callers:
  - block/bio.c:bio_associate_blkg
```
```
In block/blk-cgroup.c (ffffffff814f1a72)
Location: include/linux/cgroup.h:483
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
```
```
In net/core/sock.c (ffffffff818e1f9c)
Location: include/linux/cgroup.h:483
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
  - net/core/sock.c:sk_alloc
```
```
In net/core/scm.c (ffffffff818f14ad)
Location: include/linux/cgroup.h:483
Inline: True
Inline callers:
  - net/core/scm.c:scm_detach_fds
  - net/core/scm.c:scm_detach_fds
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
In kernel/sched/cpuacct.c (ffffffff811002f9)
Location: include/linux/cgroup.h:485
Inline: True
Inline callers:
  - kernel/sched/cpuacct.c:cpuacct_account_field
  - kernel/sched/cpuacct.c:cpuacct_charge
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff8116a969)
Location: include/linux/cgroup.h:485
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:cgroup_freezing
```
```
In kernel/cgroup/pids.c (ffffffff8116adc5)
Location: include/linux/cgroup.h:485
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_release
  - kernel/cgroup/pids.c:pids_cancel_attach
  - kernel/cgroup/pids.c:pids_can_attach
```
```
In kernel/cgroup/rdma.c (ffffffff8116b782)
Location: include/linux/cgroup.h:485
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffff81171338)
Location: include/linux/cgroup.h:485
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:__cpuset_memory_pressure_bump
  - kernel/cgroup/cpuset.c:cpuset_print_current_mems_allowed
  - kernel/cgroup/cpuset.c:__cpuset_node_allowed
  - kernel/cgroup/cpuset.c:cpuset_mems_allowed
  - kernel/cgroup/cpuset.c:cpuset_cpus_allowed_fallback
  - kernel/cgroup/cpuset.c:cpuset_cpus_allowed
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/cgroup/cpuset.c:current_cpuset_is_being_rebound
```
```
In mm/page-writeback.c (ffffffff8122d6b3)
Location: include/linux/cgroup.h:485
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/readahead.c (ffffffff81230190)
Location: include/linux/cgroup.h:485
Inline: True
```
```
In mm/swapfile.c (ffffffff8128d4f5)
Location: include/linux/cgroup.h:485
Inline: True
Inline callers:
  - mm/swapfile.c:mem_cgroup_throttle_swaprate
```
```
In mm/memcontrol.c (ffffffff812c814c)
Location: include/linux/cgroup.h:485
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:mem_cgroup_get_oom_group
  - mm/memcontrol.c:mem_cgroup_print_oom_context
```
```
In mm/hugetlb_cgroup.c (ffffffff812c9e43)
Location: include/linux/cgroup.h:485
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In fs/fs-writeback.c (ffffffff813122d4)
Location: include/linux/cgroup.h:485
Inline: True
Inline callers:
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In security/device_cgroup.c (ffffffff814b3be5)
Location: include/linux/cgroup.h:485
Inline: True
Inline callers:
  - security/device_cgroup.c:__devcgroup_check_permission
```
```
In block/bio.c (ffffffff814de5f4)
Location: include/linux/cgroup.h:485
Inline: True
Inline callers:
  - block/bio.c:bio_associate_blkg
```
```
In block/blk-cgroup.c (ffffffff8150b055)
Location: include/linux/cgroup.h:485
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
```
```
In net/core/sock.c (ffffffff8191416c)
Location: include/linux/cgroup.h:485
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
  - net/core/sock.c:sk_alloc
```
```
In net/core/scm.c (ffffffff819233fd)
Location: include/linux/cgroup.h:485
Inline: True
Inline callers:
  - net/core/scm.c:scm_detach_fds
  - net/core/scm.c:scm_detach_fds
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
In kernel/sched/cpuacct.c (ffffffff8110a999)
Location: include/linux/cgroup.h:491
Inline: True
Inline callers:
  - kernel/sched/cpuacct.c:cpuacct_account_field
  - kernel/sched/cpuacct.c:cpuacct_charge
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff8117c4a9)
Location: include/linux/cgroup.h:491
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:cgroup_freezing
```
```
In kernel/cgroup/pids.c (ffffffff8117c815)
Location: include/linux/cgroup.h:491
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_release
  - kernel/cgroup/pids.c:pids_cancel_attach
  - kernel/cgroup/pids.c:pids_can_attach
```
```
In kernel/cgroup/rdma.c (ffffffff8117d3b2)
Location: include/linux/cgroup.h:491
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffff81183048)
Location: include/linux/cgroup.h:491
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:__cpuset_memory_pressure_bump
  - kernel/cgroup/cpuset.c:cpuset_print_current_mems_allowed
  - kernel/cgroup/cpuset.c:__cpuset_node_allowed
  - kernel/cgroup/cpuset.c:cpuset_mems_allowed
  - kernel/cgroup/cpuset.c:cpuset_cpus_allowed_fallback
  - kernel/cgroup/cpuset.c:cpuset_cpus_allowed
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/cgroup/cpuset.c:current_cpuset_is_being_rebound
```
```
In mm/page-writeback.c (ffffffff8125b104)
Location: include/linux/cgroup.h:491
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/readahead.c (ffffffff8125d3d0)
Location: include/linux/cgroup.h:491
Inline: True
```
```
In mm/swapfile.c (ffffffff812bfee4)
Location: include/linux/cgroup.h:491
Inline: True
Inline callers:
  - mm/swapfile.c:cgroup_throttle_swaprate
```
```
In mm/memcontrol.c (ffffffff812fd9ac)
Location: include/linux/cgroup.h:491
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:mem_cgroup_get_oom_group
  - mm/memcontrol.c:mem_cgroup_print_oom_context
```
```
In mm/hugetlb_cgroup.c (ffffffff812ff8ad)
Location: include/linux/cgroup.h:491
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
```
```
In fs/fs-writeback.c (ffffffff81349dec)
Location: include/linux/cgroup.h:491
Inline: True
Inline callers:
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In security/device_cgroup.c (ffffffff8151349b)
Location: include/linux/cgroup.h:491
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_check_permission
```
```
In block/bio.c (ffffffff8153eadc)
Location: include/linux/cgroup.h:491
Inline: True
Inline callers:
  - block/bio.c:bio_associate_blkg
```
```
In block/blk-cgroup.c (ffffffff8156bfb8)
Location: include/linux/cgroup.h:491
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
```
```
In net/core/sock.c (ffffffff819e85e1)
Location: include/linux/cgroup.h:491
Inline: True
Inline callers:
  - net/core/sock.c:__receive_sock
  - net/core/sock.c:__receive_sock
  - net/core/sock.c:sk_alloc
  - net/core/sock.c:sk_alloc
```
```
In net/core/scm.c (ffffffff819f6acb)
Location: include/linux/cgroup.h:491
Inline: True
Inline callers:
  - net/core/scm.c:__scm_install_fd
  - net/core/scm.c:__scm_install_fd
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
In kernel/sched/cpuacct.c (ffffffff811078a9)
Location: include/linux/cgroup.h:491
Inline: True
Inline callers:
  - kernel/sched/cpuacct.c:cpuacct_account_field
  - kernel/sched/cpuacct.c:cpuacct_charge
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff8117934b)
Location: include/linux/cgroup.h:491
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:cgroup_freezing
```
```
In kernel/cgroup/pids.c (ffffffff811796c5)
Location: include/linux/cgroup.h:491
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_release
  - kernel/cgroup/pids.c:pids_cancel_attach
  - kernel/cgroup/pids.c:pids_can_attach
```
```
In kernel/cgroup/rdma.c (ffffffff8117a212)
Location: include/linux/cgroup.h:491
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffff8117ffca)
Location: include/linux/cgroup.h:491
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:__cpuset_memory_pressure_bump
  - kernel/cgroup/cpuset.c:cpuset_print_current_mems_allowed
  - kernel/cgroup/cpuset.c:__cpuset_node_allowed
  - kernel/cgroup/cpuset.c:cpuset_mems_allowed
  - kernel/cgroup/cpuset.c:cpuset_cpus_allowed_fallback
  - kernel/cgroup/cpuset.c:cpuset_cpus_allowed
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/cgroup/cpuset.c:current_cpuset_is_being_rebound
```
```
In mm/page-writeback.c (ffffffff81265305)
Location: include/linux/cgroup.h:491
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/readahead.c (ffffffff812679a7)
Location: include/linux/cgroup.h:491
Inline: True
Inline callers:
  - mm/readahead.c:page_cache_sync_ra
```
```
In mm/swapfile.c (ffffffff812cba9d)
Location: include/linux/cgroup.h:491
Inline: True
Inline callers:
  - mm/swapfile.c:cgroup_throttle_swaprate
```
```
In mm/memcontrol.c (ffffffff81309dd2)
Location: include/linux/cgroup.h:491
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:get_obj_cgroup_from_current
  - mm/memcontrol.c:mem_cgroup_get_oom_group
  - mm/memcontrol.c:mem_cgroup_print_oom_context
```
```
In mm/hugetlb_cgroup.c (ffffffff8130bbe3)
Location: include/linux/cgroup.h:491
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
```
```
In fs/fs-writeback.c (ffffffff81356ce9)
Location: include/linux/cgroup.h:491
Inline: True
Inline callers:
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/io_uring.c (ffffffff8139698a)
Location: include/linux/cgroup.h:491
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_grab_identity
  - fs/io_uring.c:io_init_identity
```
```
In security/device_cgroup.c (ffffffff815305eb)
Location: include/linux/cgroup.h:491
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_check_permission
```
```
In block/blk-cgroup.c (ffffffff815864c9)
Location: include/linux/cgroup.h:491
Inline: True
Inline callers:
  - block/blk-cgroup.c:bio_associate_blkg
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
```
```
In net/core/sock.c (ffffffff819e8253)
Location: include/linux/cgroup.h:491
Inline: True
Inline callers:
  - net/core/sock.c:__receive_sock
  - net/core/sock.c:__receive_sock
  - net/core/sock.c:sk_alloc
  - net/core/sock.c:sk_alloc
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
In kernel/sched/cpuacct.c (ffffffff81109979)
Location: include/linux/cgroup.h:491
Inline: True
Inline callers:
  - kernel/sched/cpuacct.c:cpuacct_account_field
  - kernel/sched/cpuacct.c:cpuacct_charge
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff81179eab)
Location: include/linux/cgroup.h:491
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:cgroup_freezing
```
```
In kernel/cgroup/pids.c (ffffffff8117a225)
Location: include/linux/cgroup.h:491
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_release
  - kernel/cgroup/pids.c:pids_cancel_attach
  - kernel/cgroup/pids.c:pids_can_attach
```
```
In kernel/cgroup/rdma.c (ffffffff8117ad92)
Location: include/linux/cgroup.h:491
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffff81180a9a)
Location: include/linux/cgroup.h:491
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:__cpuset_memory_pressure_bump
  - kernel/cgroup/cpuset.c:cpuset_print_current_mems_allowed
  - kernel/cgroup/cpuset.c:__cpuset_node_allowed
  - kernel/cgroup/cpuset.c:cpuset_mems_allowed
  - kernel/cgroup/cpuset.c:cpuset_cpus_allowed_fallback
  - kernel/cgroup/cpuset.c:cpuset_cpus_allowed
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/cgroup/cpuset.c:current_cpuset_is_being_rebound
```
```
In mm/page-writeback.c (ffffffff81269514)
Location: include/linux/cgroup.h:491
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/readahead.c (ffffffff8126c5b1)
Location: include/linux/cgroup.h:491
Inline: True
Inline callers:
  - mm/readahead.c:page_cache_sync_ra
```
```
In mm/swapfile.c (ffffffff812d26fc)
Location: include/linux/cgroup.h:491
Inline: True
Inline callers:
  - mm/swapfile.c:cgroup_throttle_swaprate
```
```
In mm/memcontrol.c (ffffffff81310642)
Location: include/linux/cgroup.h:491
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:__memcg_kmem_charge_page
  - mm/memcontrol.c:mem_cgroup_get_oom_group
  - mm/memcontrol.c:mem_cgroup_print_oom_context
```
```
In mm/hugetlb_cgroup.c (ffffffff813121e3)
Location: include/linux/cgroup.h:491
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
```
```
In fs/fs-writeback.c (ffffffff8135f50b)
Location: include/linux/cgroup.h:491
Inline: True
Inline callers:
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In security/device_cgroup.c (ffffffff815367eb)
Location: include/linux/cgroup.h:491
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_check_permission
```
```
In block/blk-cgroup.c (ffffffff8158ced9)
Location: include/linux/cgroup.h:491
Inline: True
Inline callers:
  - block/blk-cgroup.c:bio_associate_blkg
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
```
```
In net/core/sock.c (ffffffff819ce391)
Location: include/linux/cgroup.h:491
Inline: True
Inline callers:
  - net/core/sock.c:__receive_sock
  - net/core/sock.c:__receive_sock
  - net/core/sock.c:sk_alloc
  - net/core/sock.c:sk_alloc
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
In kernel/sched/cpuacct.c (ffffffff81127e19)
Location: include/linux/cgroup.h:491
Inline: True
Inline callers:
  - kernel/sched/cpuacct.c:cpuacct_account_field
  - kernel/sched/cpuacct.c:cpuacct_charge
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff811a17cb)
Location: include/linux/cgroup.h:491
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:cgroup_freezing
```
```
In kernel/cgroup/pids.c (ffffffff811a1b45)
Location: include/linux/cgroup.h:491
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_release
  - kernel/cgroup/pids.c:pids_cancel_attach
  - kernel/cgroup/pids.c:pids_can_attach
```
```
In kernel/cgroup/rdma.c (ffffffff811a2852)
Location: include/linux/cgroup.h:491
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffff811a888a)
Location: include/linux/cgroup.h:491
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:__cpuset_memory_pressure_bump
  - kernel/cgroup/cpuset.c:cpuset_print_current_mems_allowed
  - kernel/cgroup/cpuset.c:__cpuset_node_allowed
  - kernel/cgroup/cpuset.c:cpuset_mems_allowed
  - kernel/cgroup/cpuset.c:cpuset_cpus_allowed_fallback
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/cgroup/cpuset.c:current_cpuset_is_being_rebound
  - kernel/cgroup/cpuset.c:guarantee_online_cpus
```
```
In mm/page-writeback.c (ffffffff812a5f8e)
Location: include/linux/cgroup.h:491
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/readahead.c (ffffffff812a92d1)
Location: include/linux/cgroup.h:491
Inline: True
Inline callers:
  - mm/readahead.c:page_cache_sync_ra
```
```
In mm/swapfile.c (ffffffff81317ffc)
Location: include/linux/cgroup.h:491
Inline: True
Inline callers:
  - mm/swapfile.c:__cgroup_throttle_swaprate
```
```
In mm/memcontrol.c (ffffffff8135b950)
Location: include/linux/cgroup.h:491
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:__memcg_kmem_charge_page
  - mm/memcontrol.c:mem_cgroup_get_oom_group
  - mm/memcontrol.c:mem_cgroup_print_oom_context
  - mm/memcontrol.c:get_mem_cgroup_from_mm
```
```
In mm/hugetlb_cgroup.c (ffffffff8135dafe)
Location: include/linux/cgroup.h:491
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
```
```
In fs/fs-writeback.c (ffffffff813abe25)
Location: include/linux/cgroup.h:491
Inline: True
Inline callers:
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In security/device_cgroup.c (ffffffff81594f18)
Location: include/linux/cgroup.h:491
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_check_permission
```
```
In block/blk-cgroup.c (ffffffff815f2739)
Location: include/linux/cgroup.h:491
Inline: True
Inline callers:
  - block/blk-cgroup.c:bio_associate_blkg
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
```
```
In net/core/sock.c (ffffffff81a7dc56)
Location: include/linux/cgroup.h:491
Inline: True
Inline callers:
  - net/core/sock.c:__receive_sock
  - net/core/sock.c:__receive_sock
  - net/core/sock.c:sk_alloc
  - net/core/sock.c:sk_alloc
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
In kernel/sched/build_utility.c (ffffffff81144087)
Location: include/linux/cgroup.h:492
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:put_prev_task_stop
  - kernel/sched/build_utility.c:cpuacct_account_field
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff811d2122)
Location: include/linux/cgroup.h:492
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:cgroup_freezing
```
```
In kernel/cgroup/pids.c (ffffffff811d2515)
Location: include/linux/cgroup.h:492
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_release
  - kernel/cgroup/pids.c:pids_cancel_attach
  - kernel/cgroup/pids.c:pids_can_attach
```
```
In kernel/cgroup/rdma.c (ffffffff811d32c7)
Location: include/linux/cgroup.h:492
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffff811d9a3d)
Location: include/linux/cgroup.h:492
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:__cpuset_memory_pressure_bump
  - kernel/cgroup/cpuset.c:cpuset_print_current_mems_allowed
  - kernel/cgroup/cpuset.c:__cpuset_node_allowed
  - kernel/cgroup/cpuset.c:cpuset_mems_allowed
  - kernel/cgroup/cpuset.c:cpuset_cpus_allowed_fallback
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/cgroup/cpuset.c:current_cpuset_is_being_rebound
  - kernel/cgroup/cpuset.c:guarantee_online_cpus
```
```
In mm/page-writeback.c (ffffffff812fec77)
Location: include/linux/cgroup.h:492
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/memcontrol.c (ffffffff813d5212)
Location: include/linux/cgroup.h:492
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:mem_cgroup_can_attach
  - mm/memcontrol.c:__memcg_kmem_charge_page
  - mm/memcontrol.c:mem_cgroup_get_oom_group
  - mm/memcontrol.c:mem_cgroup_print_oom_context
  - mm/memcontrol.c:get_mem_cgroup_from_mm
```
```
In mm/hugetlb_cgroup.c (ffffffff813d7b9b)
Location: include/linux/cgroup.h:492
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
```
```
In fs/fs-writeback.c (ffffffff81431fc8)
Location: include/linux/cgroup.h:492
Inline: True
Inline callers:
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In security/device_cgroup.c (ffffffff816370bd)
Location: include/linux/cgroup.h:492
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_check_permission
```
```
In block/blk-cgroup.c (ffffffff816a4eb5)
Location: include/linux/cgroup.h:492
Inline: True
Inline callers:
  - block/blk-cgroup.c:blk_cgroup_congested
  - block/blk-cgroup.c:bio_associate_blkg
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
```
```
In net/core/sock.c (ffffffff81bf2558)
Location: include/linux/cgroup.h:492
Inline: True
Inline callers:
  - net/core/sock.c:__receive_sock
  - net/core/sock.c:__receive_sock
  - net/core/sock.c:sk_alloc
  - net/core/sock.c:sk_alloc
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
In kernel/sched/build_utility.c (ffffffff8116fd56)
Location: include/linux/cgroup.h:434
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:put_prev_task_stop
  - kernel/sched/build_utility.c:cpuacct_account_field
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff81215e72)
Location: include/linux/cgroup.h:434
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:cgroup_freezing
```
```
In kernel/cgroup/pids.c (ffffffff81216275)
Location: include/linux/cgroup.h:434
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_release
  - kernel/cgroup/pids.c:pids_cancel_attach
  - kernel/cgroup/pids.c:pids_can_attach
```
```
In kernel/cgroup/rdma.c (ffffffff81217247)
Location: include/linux/cgroup.h:434
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffff8121ef0d)
Location: include/linux/cgroup.h:434
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:__cpuset_memory_pressure_bump
  - kernel/cgroup/cpuset.c:cpuset_print_current_mems_allowed
  - kernel/cgroup/cpuset.c:__cpuset_node_allowed
  - kernel/cgroup/cpuset.c:cpuset_mems_allowed
  - kernel/cgroup/cpuset.c:cpuset_cpus_allowed_fallback
  - kernel/cgroup/cpuset.c:cpuset_cpus_allowed
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/cgroup/cpuset.c:current_cpuset_is_being_rebound
  - kernel/cgroup/cpuset.c:guarantee_online_cpus
```
```
In mm/page-writeback.c (ffffffff813693f4)
Location: include/linux/cgroup.h:434
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited_flags
  - mm/page-writeback.c:balance_dirty_pages_ratelimited_flags
  - mm/page-writeback.c:balance_dirty_pages_ratelimited_flags
```
```
In mm/memcontrol.c (ffffffff8145ac92)
Location: include/linux/cgroup.h:434
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:mem_cgroup_can_attach
  - mm/memcontrol.c:__memcg_kmem_charge_page
  - mm/memcontrol.c:mem_cgroup_get_oom_group
  - mm/memcontrol.c:mem_cgroup_print_oom_context
  - mm/memcontrol.c:get_mem_cgroup_from_mm
```
```
In mm/hugetlb_cgroup.c (ffffffff8145da0b)
Location: include/linux/cgroup.h:434
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
```
```
In fs/fs-writeback.c (ffffffff814c0018)
Location: include/linux/cgroup.h:434
Inline: True
Inline callers:
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In security/device_cgroup.c (ffffffff816ee30d)
Location: include/linux/cgroup.h:434
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_check_permission
```
```
In block/blk-cgroup.c (ffffffff81763ce5)
Location: include/linux/cgroup.h:434
Inline: True
Inline callers:
  - block/blk-cgroup.c:blk_cgroup_congested
  - block/blk-cgroup.c:bio_associate_blkg
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
```
```
In net/core/sock.c (ffffffff81d9e6e8)
Location: include/linux/cgroup.h:434
Inline: True
Inline callers:
  - net/core/sock.c:__receive_sock
  - net/core/sock.c:__receive_sock
  - net/core/sock.c:sk_alloc
  - net/core/sock.c:sk_alloc
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
In kernel/sched/build_utility.c (ffffffff8117e6e6)
Location: include/linux/cgroup.h:433
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:put_prev_task_stop
  - kernel/sched/build_utility.c:cpuacct_account_field
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff8122b7b2)
Location: include/linux/cgroup.h:433
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:cgroup_freezing
```
```
In kernel/cgroup/pids.c (ffffffff8122bbb5)
Location: include/linux/cgroup.h:433
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_release
  - kernel/cgroup/pids.c:pids_cancel_attach
  - kernel/cgroup/pids.c:pids_can_attach
```
```
In kernel/cgroup/rdma.c (ffffffff8122cb67)
Location: include/linux/cgroup.h:433
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffff8123503d)
Location: include/linux/cgroup.h:433
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:__cpuset_memory_pressure_bump
  - kernel/cgroup/cpuset.c:cpuset_print_current_mems_allowed
  - kernel/cgroup/cpuset.c:cpuset_node_allowed
  - kernel/cgroup/cpuset.c:cpuset_mems_allowed
  - kernel/cgroup/cpuset.c:cpuset_cpus_allowed_fallback
  - kernel/cgroup/cpuset.c:cpuset_cpus_allowed
  - kernel/cgroup/cpuset.c:cpuset_fork
  - kernel/cgroup/cpuset.c:cpuset_fork
  - kernel/cgroup/cpuset.c:cpuset_can_fork
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/cgroup/cpuset.c:current_cpuset_is_being_rebound
  - kernel/cgroup/cpuset.c:guarantee_online_cpus
  - kernel/cgroup/cpuset.c:dec_dl_tasks_cs
  - kernel/cgroup/cpuset.c:inc_dl_tasks_cs
```
```
In mm/page-writeback.c (ffffffff8139b594)
Location: include/linux/cgroup.h:433
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited_flags
  - mm/page-writeback.c:balance_dirty_pages_ratelimited_flags
  - mm/page-writeback.c:balance_dirty_pages_ratelimited_flags
```
```
In mm/memcontrol.c (ffffffff814908e7)
Location: include/linux/cgroup.h:433
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:mem_cgroup_can_attach
  - mm/memcontrol.c:__memcg_kmem_charge_page
  - mm/memcontrol.c:mem_cgroup_get_oom_group
  - mm/memcontrol.c:mem_cgroup_print_oom_context
  - mm/memcontrol.c:get_mem_cgroup_from_mm
```
```
In mm/hugetlb_cgroup.c (ffffffff814936fb)
Location: include/linux/cgroup.h:433
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
```
```
In fs/fs-writeback.c (ffffffff814f6478)
Location: include/linux/cgroup.h:433
Inline: True
Inline callers:
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In security/device_cgroup.c (ffffffff8172879d)
Location: include/linux/cgroup.h:433
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_check_permission
```
```
In block/blk-cgroup.c (ffffffff817a2d55)
Location: include/linux/cgroup.h:433
Inline: True
Inline callers:
  - block/blk-cgroup.c:blk_cgroup_congested
  - block/blk-cgroup.c:bio_associate_blkg
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
```
```
In net/core/sock.c (ffffffff81e0cef8)
Location: include/linux/cgroup.h:433
Inline: True
Inline callers:
  - net/core/sock.c:__receive_sock
  - net/core/sock.c:__receive_sock
  - net/core/sock.c:sk_alloc
  - net/core/sock.c:sk_alloc
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
In kernel/sched/build_utility.c (ffffffff81191e35)
Location: include/linux/cgroup.h:431
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:cpuacct_account_field
  - kernel/sched/build_utility.c:cpuacct_charge
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff812437a2)
Location: include/linux/cgroup.h:431
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:cgroup_freezing
```
```
In kernel/cgroup/pids.c (ffffffff81243be5)
Location: include/linux/cgroup.h:431
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_release
  - kernel/cgroup/pids.c:pids_cancel_attach
  - kernel/cgroup/pids.c:pids_can_attach
```
```
In kernel/cgroup/rdma.c (ffffffff81244c27)
Location: include/linux/cgroup.h:431
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffff8124ec8c)
Location: include/linux/cgroup.h:431
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:__cpuset_memory_pressure_bump
  - kernel/cgroup/cpuset.c:cpuset_print_current_mems_allowed
  - kernel/cgroup/cpuset.c:cpuset_node_allowed
  - kernel/cgroup/cpuset.c:cpuset_mems_allowed
  - kernel/cgroup/cpuset.c:cpuset_cpus_allowed_fallback
  - kernel/cgroup/cpuset.c:cpuset_cpus_allowed
  - kernel/cgroup/cpuset.c:cpuset_fork
  - kernel/cgroup/cpuset.c:cpuset_fork
  - kernel/cgroup/cpuset.c:cpuset_can_fork
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/cgroup/cpuset.c:current_cpuset_is_being_rebound
  - kernel/cgroup/cpuset.c:guarantee_online_cpus
  - kernel/cgroup/cpuset.c:dec_dl_tasks_cs
  - kernel/cgroup/cpuset.c:inc_dl_tasks_cs
```
```
In mm/page-writeback.c (ffffffff813c5504)
Location: include/linux/cgroup.h:431
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited_flags
  - mm/page-writeback.c:balance_dirty_pages_ratelimited_flags
  - mm/page-writeback.c:balance_dirty_pages_ratelimited_flags
```
```
In mm/memcontrol.c (ffffffff814c0257)
Location: include/linux/cgroup.h:431
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:mem_cgroup_can_attach
  - mm/memcontrol.c:current_objcg_update
  - mm/memcontrol.c:mem_cgroup_get_oom_group
  - mm/memcontrol.c:mem_cgroup_print_oom_context
  - mm/memcontrol.c:get_mem_cgroup_from_current
  - mm/memcontrol.c:get_mem_cgroup_from_mm
```
```
In mm/hugetlb_cgroup.c (ffffffff814c306d)
Location: include/linux/cgroup.h:431
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
```
```
In fs/fs-writeback.c (ffffffff8152abb8)
Location: include/linux/cgroup.h:431
Inline: True
Inline callers:
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In security/device_cgroup.c (ffffffff81769acd)
Location: include/linux/cgroup.h:431
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_check_permission
```
```
In block/blk-cgroup.c (ffffffff817e6895)
Location: include/linux/cgroup.h:431
Inline: True
Inline callers:
  - block/blk-cgroup.c:blk_cgroup_congested
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
```
```
In net/core/sock.c (ffffffff81ec9888)
Location: include/linux/cgroup.h:431
Inline: True
Inline callers:
  - net/core/sock.c:__receive_sock
  - net/core/sock.c:__receive_sock
  - net/core/sock.c:sk_alloc
  - net/core/sock.c:sk_alloc
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
In kernel/sched/cpuacct.c (ffff80001016497c)
Location: include/linux/cgroup.h:485
Inline: True
Inline callers:
  - kernel/sched/cpuacct.c:cpuacct_account_field
  - kernel/sched/cpuacct.c:cpuacct_charge
```
```
In kernel/cgroup/legacy_freezer.c (ffff8000101de8d0)
Location: include/linux/cgroup.h:485
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:cgroup_freezing
```
```
In kernel/cgroup/pids.c (ffff8000101def80)
Location: include/linux/cgroup.h:485
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_release
  - kernel/cgroup/pids.c:pids_cancel_attach
  - kernel/cgroup/pids.c:pids_can_attach
```
```
In kernel/cgroup/rdma.c (ffff8000101dfad4)
Location: include/linux/cgroup.h:485
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffff8000101e49cc)
Location: include/linux/cgroup.h:485
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:__cpuset_memory_pressure_bump
  - kernel/cgroup/cpuset.c:cpuset_print_current_mems_allowed
  - kernel/cgroup/cpuset.c:__cpuset_node_allowed
  - kernel/cgroup/cpuset.c:cpuset_mems_allowed
  - kernel/cgroup/cpuset.c:cpuset_cpus_allowed_fallback
  - kernel/cgroup/cpuset.c:cpuset_cpus_allowed
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/cgroup/cpuset.c:current_cpuset_is_being_rebound
```
```
In mm/page-writeback.c (ffff8000102bc548)
Location: include/linux/cgroup.h:485
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/readahead.c (ffff8000102bfa08)
Location: include/linux/cgroup.h:485
Inline: True
```
```
In mm/swapfile.c (ffff800010328d90)
Location: include/linux/cgroup.h:485
Inline: True
Inline callers:
  - mm/swapfile.c:mem_cgroup_throttle_swaprate
```
```
In mm/memcontrol.c (ffff80001036b05c)
Location: include/linux/cgroup.h:485
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:mem_cgroup_get_oom_group
  - mm/memcontrol.c:mem_cgroup_print_oom_context
```
```
In mm/hugetlb_cgroup.c (ffff80001036d650)
Location: include/linux/cgroup.h:485
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In fs/fs-writeback.c (ffff8000103c85c0)
Location: include/linux/cgroup.h:485
Inline: True
Inline callers:
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In security/device_cgroup.c (ffff8000105aba1c)
Location: include/linux/cgroup.h:485
Inline: True
Inline callers:
  - security/device_cgroup.c:__devcgroup_check_permission
```
```
In block/bio.c (ffff8000105dba44)
Location: include/linux/cgroup.h:485
Inline: True
Inline callers:
  - block/bio.c:bio_associate_blkg
```
```
In block/blk-cgroup.c (ffff80001060e9b0)
Location: include/linux/cgroup.h:485
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
```
```
In net/core/sock.c (ffff800010bab154)
Location: include/linux/cgroup.h:485
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
  - net/core/sock.c:sk_alloc
```
```
In net/core/scm.c (ffff800010bbe5cc)
Location: include/linux/cgroup.h:485
Inline: True
Inline callers:
  - net/core/scm.c:scm_detach_fds
  - net/core/scm.c:scm_detach_fds
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
In kernel/sched/cpuacct.c (c03b0fb4)
Location: include/linux/cgroup.h:485
Inline: True
Inline callers:
  - kernel/sched/cpuacct.c:cpuacct_account_field
  - kernel/sched/cpuacct.c:cpuacct_charge
```
```
In kernel/cgroup/legacy_freezer.c (c0420350)
Location: include/linux/cgroup.h:485
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:cgroup_freezing
```
```
In kernel/cgroup/pids.c (c04209b0)
Location: include/linux/cgroup.h:485
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_release
  - kernel/cgroup/pids.c:pids_cancel_attach
  - kernel/cgroup/pids.c:pids_can_attach
```
```
In kernel/cgroup/rdma.c (c0421414)
Location: include/linux/cgroup.h:485
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (c04257d4)
Location: include/linux/cgroup.h:485
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:__cpuset_memory_pressure_bump
  - kernel/cgroup/cpuset.c:cpuset_print_current_mems_allowed
  - kernel/cgroup/cpuset.c:__cpuset_node_allowed
  - kernel/cgroup/cpuset.c:cpuset_mems_allowed
  - kernel/cgroup/cpuset.c:cpuset_cpus_allowed_fallback
  - kernel/cgroup/cpuset.c:cpuset_cpus_allowed
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/cgroup/cpuset.c:current_cpuset_is_being_rebound
```
```
In mm/page-writeback.c (c04e8b94)
Location: include/linux/cgroup.h:485
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/readahead.c (c04eb4c4)
Location: include/linux/cgroup.h:485
Inline: True
```
```
In mm/swapfile.c (c0540120)
Location: include/linux/cgroup.h:485
Inline: True
Inline callers:
  - mm/swapfile.c:mem_cgroup_throttle_swaprate
```
```
In mm/memcontrol.c (c055c6d8)
Location: include/linux/cgroup.h:485
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:mem_cgroup_get_oom_group
  - mm/memcontrol.c:mem_cgroup_print_oom_context
```
```
In fs/fs-writeback.c (c05a4e8c)
Location: include/linux/cgroup.h:485
Inline: True
Inline callers:
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In security/device_cgroup.c (c075b56c)
Location: include/linux/cgroup.h:485
Inline: True
Inline callers:
  - security/device_cgroup.c:__devcgroup_check_permission
```
```
In block/bio.c (c07885e4)
Location: include/linux/cgroup.h:485
Inline: True
Inline callers:
  - block/bio.c:bio_associate_blkg
```
```
In block/blk-cgroup.c (c07b9220)
Location: include/linux/cgroup.h:485
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
```
```
In net/core/sock.c (c0cc9c04)
Location: include/linux/cgroup.h:485
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
  - net/core/sock.c:sk_alloc
```
```
In net/core/scm.c (c0cda108)
Location: include/linux/cgroup.h:485
Inline: True
Inline callers:
  - net/core/scm.c:scm_detach_fds
  - net/core/scm.c:scm_detach_fds
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
In kernel/sched/cpuacct.c (c0000000001bb8c0)
Location: include/linux/cgroup.h:485
Inline: True
Inline callers:
  - kernel/sched/cpuacct.c:cpuacct_account_field
  - kernel/sched/cpuacct.c:cpuacct_charge
```
```
In kernel/cgroup/legacy_freezer.c (c00000000024c978)
Location: include/linux/cgroup.h:485
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:cgroup_freezing
```
```
In kernel/cgroup/pids.c (c00000000024d178)
Location: include/linux/cgroup.h:485
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_release
  - kernel/cgroup/pids.c:pids_cancel_attach
  - kernel/cgroup/pids.c:pids_can_attach
```
```
In kernel/cgroup/rdma.c (c00000000024e1dc)
Location: include/linux/cgroup.h:485
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (c0000000002551ec)
Location: include/linux/cgroup.h:485
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:__cpuset_memory_pressure_bump
  - kernel/cgroup/cpuset.c:cpuset_print_current_mems_allowed
  - kernel/cgroup/cpuset.c:__cpuset_node_allowed
  - kernel/cgroup/cpuset.c:cpuset_mems_allowed
  - kernel/cgroup/cpuset.c:cpuset_cpus_allowed_fallback
  - kernel/cgroup/cpuset.c:cpuset_cpus_allowed
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/cgroup/cpuset.c:current_cpuset_is_being_rebound
```
```
In mm/page-writeback.c (c000000000374868)
Location: include/linux/cgroup.h:485
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/readahead.c (c000000000378964)
Location: include/linux/cgroup.h:485
Inline: True
```
```
In mm/swapfile.c (c0000000004000d4)
Location: include/linux/cgroup.h:485
Inline: True
Inline callers:
  - mm/swapfile.c:mem_cgroup_throttle_swaprate
```
```
In mm/memcontrol.c (c00000000045a798)
Location: include/linux/cgroup.h:485
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:mem_cgroup_get_oom_group
  - mm/memcontrol.c:mem_cgroup_print_oom_context
```
```
In mm/hugetlb_cgroup.c (c00000000045d784)
Location: include/linux/cgroup.h:485
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In fs/fs-writeback.c (c0000000004c9a28)
Location: include/linux/cgroup.h:485
Inline: True
Inline callers:
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In security/device_cgroup.c (c000000000729ac4)
Location: include/linux/cgroup.h:485
Inline: True
Inline callers:
  - security/device_cgroup.c:__devcgroup_check_permission
```
```
In block/bio.c (c00000000076b9f4)
Location: include/linux/cgroup.h:485
Inline: True
Inline callers:
  - block/bio.c:bio_associate_blkg
```
```
In block/blk-cgroup.c (c0000000007abf90)
Location: include/linux/cgroup.h:485
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
```
```
In net/core/sock.c (c000000000c8194c)
Location: include/linux/cgroup.h:485
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
  - net/core/sock.c:sk_alloc
```
```
In net/core/scm.c (c000000000c979b8)
Location: include/linux/cgroup.h:485
Inline: True
Inline callers:
  - net/core/scm.c:scm_detach_fds
  - net/core/scm.c:scm_detach_fds
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
In kernel/sched/cpuacct.c (ffffffe0001081dc)
Location: include/linux/cgroup.h:485
Inline: True
Inline callers:
  - kernel/sched/cpuacct.c:cpuacct_account_field
  - kernel/sched/cpuacct.c:cpuacct_charge
```
```
In kernel/cgroup/legacy_freezer.c (ffffffe000155c9c)
Location: include/linux/cgroup.h:485
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:cgroup_freezing
```
```
In kernel/cgroup/pids.c (ffffffe000155e6e)
Location: include/linux/cgroup.h:485
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_release
  - kernel/cgroup/pids.c:pids_cancel_attach
  - kernel/cgroup/pids.c:pids_can_attach
```
```
In kernel/cgroup/rdma.c (ffffffe000156ad0)
Location: include/linux/cgroup.h:485
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffe00015abc2)
Location: include/linux/cgroup.h:485
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:__cpuset_memory_pressure_bump
  - kernel/cgroup/cpuset.c:cpuset_print_current_mems_allowed
  - kernel/cgroup/cpuset.c:__cpuset_node_allowed
  - kernel/cgroup/cpuset.c:cpuset_mems_allowed
  - kernel/cgroup/cpuset.c:cpuset_cpus_allowed_fallback
  - kernel/cgroup/cpuset.c:cpuset_cpus_allowed
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/cgroup/cpuset.c:current_cpuset_is_being_rebound
```
```
In mm/page-writeback.c (ffffffe0001df170)
Location: include/linux/cgroup.h:485
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/readahead.c (ffffffe0001e1a3e)
Location: include/linux/cgroup.h:485
Inline: True
```
```
In mm/swapfile.c (ffffffe000228a5e)
Location: include/linux/cgroup.h:485
Inline: True
Inline callers:
  - mm/swapfile.c:mem_cgroup_throttle_swaprate
```
```
In mm/memcontrol.c (ffffffe00024878e)
Location: include/linux/cgroup.h:485
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:mem_cgroup_get_oom_group
  - mm/memcontrol.c:mem_cgroup_print_oom_context
```
```
In mm/hugetlb_cgroup.c (ffffffe00024a384)
Location: include/linux/cgroup.h:485
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In fs/fs-writeback.c (ffffffe000284b86)
Location: include/linux/cgroup.h:485
Inline: True
Inline callers:
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In security/device_cgroup.c (ffffffe0003f44aa)
Location: include/linux/cgroup.h:485
Inline: True
Inline callers:
  - security/device_cgroup.c:__devcgroup_check_permission
```
```
In block/bio.c (ffffffe00041e65e)
Location: include/linux/cgroup.h:485
Inline: True
Inline callers:
  - block/bio.c:bio_associate_blkg
```
```
In block/blk-cgroup.c (ffffffe000446e20)
Location: include/linux/cgroup.h:485
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
```
```
In net/core/sock.c (ffffffe00073eb46)
Location: include/linux/cgroup.h:485
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
  - net/core/sock.c:sk_alloc
```
```
In net/core/scm.c (ffffffe00074c540)
Location: include/linux/cgroup.h:485
Inline: True
Inline callers:
  - net/core/scm.c:scm_detach_fds
  - net/core/scm.c:scm_detach_fds
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
In kernel/sched/cpuacct.c (ffffffff810f9609)
Location: include/linux/cgroup.h:485
Inline: True
Inline callers:
  - kernel/sched/cpuacct.c:cpuacct_account_field
  - kernel/sched/cpuacct.c:cpuacct_charge
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff81162f89)
Location: include/linux/cgroup.h:485
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:cgroup_freezing
```
```
In kernel/cgroup/pids.c (ffffffff811633e5)
Location: include/linux/cgroup.h:485
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_release
  - kernel/cgroup/pids.c:pids_cancel_attach
  - kernel/cgroup/pids.c:pids_can_attach
```
```
In kernel/cgroup/rdma.c (ffffffff81163da2)
Location: include/linux/cgroup.h:485
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffff81169958)
Location: include/linux/cgroup.h:485
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:__cpuset_memory_pressure_bump
  - kernel/cgroup/cpuset.c:cpuset_print_current_mems_allowed
  - kernel/cgroup/cpuset.c:__cpuset_node_allowed
  - kernel/cgroup/cpuset.c:cpuset_mems_allowed
  - kernel/cgroup/cpuset.c:cpuset_cpus_allowed_fallback
  - kernel/cgroup/cpuset.c:cpuset_cpus_allowed
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/cgroup/cpuset.c:current_cpuset_is_being_rebound
```
```
In mm/page-writeback.c (ffffffff81225d03)
Location: include/linux/cgroup.h:485
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/readahead.c (ffffffff812287e0)
Location: include/linux/cgroup.h:485
Inline: True
```
```
In mm/swapfile.c (ffffffff81285ad5)
Location: include/linux/cgroup.h:485
Inline: True
Inline callers:
  - mm/swapfile.c:mem_cgroup_throttle_swaprate
```
```
In mm/memcontrol.c (ffffffff812c072c)
Location: include/linux/cgroup.h:485
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:mem_cgroup_get_oom_group
  - mm/memcontrol.c:mem_cgroup_print_oom_context
```
```
In mm/hugetlb_cgroup.c (ffffffff812c2423)
Location: include/linux/cgroup.h:485
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In fs/fs-writeback.c (ffffffff8130a8b4)
Location: include/linux/cgroup.h:485
Inline: True
Inline callers:
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In security/device_cgroup.c (ffffffff814ac1c5)
Location: include/linux/cgroup.h:485
Inline: True
Inline callers:
  - security/device_cgroup.c:__devcgroup_check_permission
```
```
In block/bio.c (ffffffff814d6bd4)
Location: include/linux/cgroup.h:485
Inline: True
Inline callers:
  - block/bio.c:bio_associate_blkg
```
```
In block/blk-cgroup.c (ffffffff81503635)
Location: include/linux/cgroup.h:485
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
```
```
In net/core/sock.c (ffffffff818b416c)
Location: include/linux/cgroup.h:485
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
  - net/core/sock.c:sk_alloc
```
```
In net/core/scm.c (ffffffff818c33fd)
Location: include/linux/cgroup.h:485
Inline: True
Inline callers:
  - net/core/scm.c:scm_detach_fds
  - net/core/scm.c:scm_detach_fds
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
In kernel/sched/cpuacct.c (ffffffff810e97e9)
Location: include/linux/cgroup.h:485
Inline: True
Inline callers:
  - kernel/sched/cpuacct.c:cpuacct_account_field
  - kernel/sched/cpuacct.c:cpuacct_charge
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff811561d9)
Location: include/linux/cgroup.h:485
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:cgroup_freezing
```
```
In kernel/cgroup/pids.c (ffffffff81156635)
Location: include/linux/cgroup.h:485
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_release
  - kernel/cgroup/pids.c:pids_cancel_attach
  - kernel/cgroup/pids.c:pids_can_attach
```
```
In kernel/cgroup/rdma.c (ffffffff81156ff2)
Location: include/linux/cgroup.h:485
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffff8115cb58)
Location: include/linux/cgroup.h:485
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:__cpuset_memory_pressure_bump
  - kernel/cgroup/cpuset.c:cpuset_print_current_mems_allowed
  - kernel/cgroup/cpuset.c:__cpuset_node_allowed
  - kernel/cgroup/cpuset.c:cpuset_mems_allowed
  - kernel/cgroup/cpuset.c:cpuset_cpus_allowed_fallback
  - kernel/cgroup/cpuset.c:cpuset_cpus_allowed
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/cgroup/cpuset.c:current_cpuset_is_being_rebound
```
```
In mm/page-writeback.c (ffffffff81218ea3)
Location: include/linux/cgroup.h:485
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/readahead.c (ffffffff8121b920)
Location: include/linux/cgroup.h:485
Inline: True
```
```
In mm/swapfile.c (ffffffff81277945)
Location: include/linux/cgroup.h:485
Inline: True
Inline callers:
  - mm/swapfile.c:mem_cgroup_throttle_swaprate
```
```
In mm/memcontrol.c (ffffffff812b17ec)
Location: include/linux/cgroup.h:485
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:mem_cgroup_get_oom_group
  - mm/memcontrol.c:mem_cgroup_print_oom_context
```
```
In mm/hugetlb_cgroup.c (ffffffff812b3473)
Location: include/linux/cgroup.h:485
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In fs/fs-writeback.c (ffffffff812fb4d4)
Location: include/linux/cgroup.h:485
Inline: True
Inline callers:
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In security/device_cgroup.c (ffffffff8149cbe5)
Location: include/linux/cgroup.h:485
Inline: True
Inline callers:
  - security/device_cgroup.c:__devcgroup_check_permission
```
```
In block/bio.c (ffffffff814c7594)
Location: include/linux/cgroup.h:485
Inline: True
Inline callers:
  - block/bio.c:bio_associate_blkg
```
```
In block/blk-cgroup.c (ffffffff814f3af5)
Location: include/linux/cgroup.h:485
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
```
```
In net/core/sock.c (ffffffff8186e0bc)
Location: include/linux/cgroup.h:485
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
  - net/core/sock.c:sk_alloc
```
```
In net/core/scm.c (ffffffff8187d33d)
Location: include/linux/cgroup.h:485
Inline: True
Inline callers:
  - net/core/scm.c:scm_detach_fds
  - net/core/scm.c:scm_detach_fds
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
In kernel/sched/cpuacct.c (ffffffff810f6829)
Location: include/linux/cgroup.h:485
Inline: True
Inline callers:
  - kernel/sched/cpuacct.c:cpuacct_account_field
  - kernel/sched/cpuacct.c:cpuacct_charge
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff81160d59)
Location: include/linux/cgroup.h:485
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:cgroup_freezing
```
```
In kernel/cgroup/pids.c (ffffffff811611b5)
Location: include/linux/cgroup.h:485
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_release
  - kernel/cgroup/pids.c:pids_cancel_attach
  - kernel/cgroup/pids.c:pids_can_attach
```
```
In kernel/cgroup/rdma.c (ffffffff81161b72)
Location: include/linux/cgroup.h:485
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffff81167728)
Location: include/linux/cgroup.h:485
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:__cpuset_memory_pressure_bump
  - kernel/cgroup/cpuset.c:cpuset_print_current_mems_allowed
  - kernel/cgroup/cpuset.c:__cpuset_node_allowed
  - kernel/cgroup/cpuset.c:cpuset_mems_allowed
  - kernel/cgroup/cpuset.c:cpuset_cpus_allowed_fallback
  - kernel/cgroup/cpuset.c:cpuset_cpus_allowed
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/cgroup/cpuset.c:current_cpuset_is_being_rebound
```
```
In mm/page-writeback.c (ffffffff81223aa3)
Location: include/linux/cgroup.h:485
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/readahead.c (ffffffff81226580)
Location: include/linux/cgroup.h:485
Inline: True
```
```
In mm/swapfile.c (ffffffff812838e5)
Location: include/linux/cgroup.h:485
Inline: True
Inline callers:
  - mm/swapfile.c:mem_cgroup_throttle_swaprate
```
```
In mm/memcontrol.c (ffffffff812be53c)
Location: include/linux/cgroup.h:485
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:mem_cgroup_get_oom_group
  - mm/memcontrol.c:mem_cgroup_print_oom_context
```
```
In mm/hugetlb_cgroup.c (ffffffff812c0233)
Location: include/linux/cgroup.h:485
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In fs/fs-writeback.c (ffffffff813086a4)
Location: include/linux/cgroup.h:485
Inline: True
Inline callers:
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In security/device_cgroup.c (ffffffff814a8265)
Location: include/linux/cgroup.h:485
Inline: True
Inline callers:
  - security/device_cgroup.c:__devcgroup_check_permission
```
```
In block/bio.c (ffffffff814d2c64)
Location: include/linux/cgroup.h:485
Inline: True
Inline callers:
  - block/bio.c:bio_associate_blkg
```
```
In block/blk-cgroup.c (ffffffff814ff6c5)
Location: include/linux/cgroup.h:485
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
```
```
In net/core/sock.c (ffffffff8190516c)
Location: include/linux/cgroup.h:485
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
  - net/core/sock.c:sk_alloc
```
```
In net/core/scm.c (ffffffff819143fd)
Location: include/linux/cgroup.h:485
Inline: True
Inline callers:
  - net/core/scm.c:scm_detach_fds
  - net/core/scm.c:scm_detach_fds
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
In kernel/sched/cpuacct.c (ffffffff8110187b)
Location: include/linux/cgroup.h:485
Inline: True
Inline callers:
  - kernel/sched/cpuacct.c:cpuacct_account_field
  - kernel/sched/cpuacct.c:cpuacct_charge
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff8116e194)
Location: include/linux/cgroup.h:485
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:cgroup_freezing
```
```
In kernel/cgroup/pids.c (ffffffff8116e605)
Location: include/linux/cgroup.h:485
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_release
  - kernel/cgroup/pids.c:pids_cancel_attach
  - kernel/cgroup/pids.c:pids_can_attach
```
```
In kernel/cgroup/rdma.c (ffffffff8116efd7)
Location: include/linux/cgroup.h:485
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffff81174dbd)
Location: include/linux/cgroup.h:485
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:__cpuset_memory_pressure_bump
  - kernel/cgroup/cpuset.c:cpuset_print_current_mems_allowed
  - kernel/cgroup/cpuset.c:__cpuset_node_allowed
  - kernel/cgroup/cpuset.c:cpuset_mems_allowed
  - kernel/cgroup/cpuset.c:cpuset_cpus_allowed_fallback
  - kernel/cgroup/cpuset.c:cpuset_cpus_allowed
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/cgroup/cpuset.c:current_cpuset_is_being_rebound
```
```
In mm/page-writeback.c (ffffffff81232be7)
Location: include/linux/cgroup.h:485
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/readahead.c (ffffffff8123588f)
Location: include/linux/cgroup.h:485
Inline: True
```
```
In mm/swapfile.c (ffffffff81293535)
Location: include/linux/cgroup.h:485
Inline: True
Inline callers:
  - mm/swapfile.c:mem_cgroup_throttle_swaprate
```
```
In mm/memcontrol.c (ffffffff812cef5d)
Location: include/linux/cgroup.h:485
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:mem_cgroup_get_oom_group
  - mm/memcontrol.c:mem_cgroup_print_oom_context
```
```
In mm/hugetlb_cgroup.c (ffffffff812d0c81)
Location: include/linux/cgroup.h:485
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In fs/fs-writeback.c (ffffffff81318097)
Location: include/linux/cgroup.h:485
Inline: True
Inline callers:
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In security/device_cgroup.c (ffffffff814c0c53)
Location: include/linux/cgroup.h:485
Inline: True
Inline callers:
  - security/device_cgroup.c:__devcgroup_check_permission
```
```
In block/bio.c (ffffffff814eb7ed)
Location: include/linux/cgroup.h:485
Inline: True
Inline callers:
  - block/bio.c:bio_associate_blkg
```
```
In block/blk-cgroup.c (ffffffff8151885d)
Location: include/linux/cgroup.h:485
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
```
```
In net/core/sock.c (ffffffff819262f6)
Location: include/linux/cgroup.h:485
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
  - net/core/sock.c:sk_alloc
```
```
In net/core/scm.c (ffffffff81935781)
Location: include/linux/cgroup.h:485
Inline: True
Inline callers:
  - net/core/scm.c:scm_detach_fds
  - net/core/scm.c:scm_detach_fds
```
</details>
</li>
</ul>

## Differences
