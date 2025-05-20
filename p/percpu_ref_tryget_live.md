# Function: <code>percpu_ref_tryget_live</code>

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
In kernel/cgroup.c (ffffffff81115ffd)
Location: include/linux/percpu-refcount.h:240
Inline: True
Inline callers:
  - kernel/cgroup.c:cgroup_get_e_css
  - kernel/cgroup.c:cgroup_mount
  - kernel/cgroup.c:css_tryget_online_from_dir
```
```
In kernel/cgroup_freezer.c (ffffffff81119f1d)
Location: include/linux/percpu-refcount.h:240
Inline: True
Inline callers:
  - kernel/cgroup_freezer.c:freezer_read
  - kernel/cgroup_freezer.c:freezer_write
```
```
In kernel/cpuset.c (ffffffff8111cc30)
Location: include/linux/percpu-refcount.h:240
Inline: True
Inline callers:
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/cpuset.c:cpuset_hotplug_workfn
  - kernel/cpuset.c:proc_cpuset_show
```
```
In mm/page-writeback.c (ffffffff8119a6ac)
Location: include/linux/percpu-refcount.h:240
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/memcontrol.c (ffffffff811fae01)
Location: include/linux/percpu-refcount.h:240
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mem_cgroup_from_mm
  - mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node
  - mm/memcontrol.c:mem_cgroup_try_charge
```
```
In mm/hugetlb_cgroup.c (ffffffff812012d9)
Location: include/linux/percpu-refcount.h:240
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In fs/fs-writeback.c (ffffffff8123abb3)
Location: include/linux/percpu-refcount.h:240
Inline: True
Inline callers:
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In block/bio.c (ffffffff813b0fd2)
Location: include/linux/percpu-refcount.h:240
Inline: True
Inline callers:
  - block/bio.c:bio_associate_current
```
```
In block/blk-core.c (ffffffff813b99e8)
Location: include/linux/percpu-refcount.h:240
Inline: True
Inline callers:
  - block/blk-core.c:blk_queue_enter
  - block/blk-core.c:blk_account_io_start
```
```
In block/blk-cgroup.c (ffffffff813d7d41)
Location: include/linux/percpu-refcount.h:240
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_create
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
In arch/x86/mm/gup.c (ffffffff810715c0)
Location: include/linux/percpu-refcount.h:238
Inline: True
Inline callers:
  - arch/x86/mm/gup.c:gup_huge_pmd
  - arch/x86/mm/gup.c:gup_pte_range
```
```
In kernel/cgroup.c (ffffffff811215e4)
Location: include/linux/percpu-refcount.h:238
Inline: True
Inline callers:
  - kernel/cgroup.c:css_tryget_online_from_dir
  - kernel/cgroup.c:cgroup_mount
  - kernel/cgroup.c:cgroup_mount
  - kernel/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup_freezer.c (ffffffff81121fce)
Location: include/linux/percpu-refcount.h:238
Inline: True
Inline callers:
  - kernel/cgroup_freezer.c:freezer_write
  - kernel/cgroup_freezer.c:freezer_read
```
```
In kernel/cpuset.c (ffffffff811258ba)
Location: include/linux/percpu-refcount.h:238
Inline: True
Inline callers:
  - kernel/cpuset.c:proc_cpuset_show
  - kernel/cpuset.c:cpuset_hotplug_workfn
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/cpuset.c:cpuset_write_resmask
```
```
In kernel/memremap.c (ffffffff8119e13a)
Location: include/linux/percpu-refcount.h:238
Inline: True
Inline callers:
  - kernel/memremap.c:devm_memremap_pages_release
```
```
In mm/page-writeback.c (ffffffff811aefbb)
Location: include/linux/percpu-refcount.h:238
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/gup.c (ffffffff811d4c43)
Location: include/linux/percpu-refcount.h:238
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/huge_memory.c (ffffffff812149a7)
Location: include/linux/percpu-refcount.h:238
Inline: True
Inline callers:
  - mm/huge_memory.c:follow_devmap_pmd
```
```
In mm/memcontrol.c (ffffffff81223fdb)
Location: include/linux/percpu-refcount.h:238
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:get_mem_cgroup_from_mm
  - mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node
```
```
In mm/hugetlb_cgroup.c (ffffffff81225ab7)
Location: include/linux/percpu-refcount.h:238
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In fs/fs-writeback.c (ffffffff81262a57)
Location: include/linux/percpu-refcount.h:238
Inline: True
Inline callers:
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In block/bio.c (ffffffff813f49af)
Location: include/linux/percpu-refcount.h:238
Inline: True
Inline callers:
  - block/bio.c:bio_associate_current
```
```
In block/blk-core.c (ffffffff813fe759)
Location: include/linux/percpu-refcount.h:238
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-cgroup.c (ffffffff8141d9fe)
Location: include/linux/percpu-refcount.h:238
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_create
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
In arch/x86/mm/gup.c (ffffffff8107512d)
Location: include/linux/percpu-refcount.h:238
Inline: True
Inline callers:
  - arch/x86/mm/gup.c:gup_huge_pmd
  - arch/x86/mm/gup.c:gup_pte_range
```
```
In kernel/cgroup.c (ffffffff81129b64)
Location: include/linux/percpu-refcount.h:238
Inline: True
Inline callers:
  - kernel/cgroup.c:css_tryget_online_from_dir
  - kernel/cgroup.c:cgroup_mount
  - kernel/cgroup.c:cgroup_mount
  - kernel/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup_freezer.c (ffffffff8112a5fe)
Location: include/linux/percpu-refcount.h:238
Inline: True
Inline callers:
  - kernel/cgroup_freezer.c:freezer_write
  - kernel/cgroup_freezer.c:freezer_read
```
```
In kernel/cpuset.c (ffffffff8112f2b4)
Location: include/linux/percpu-refcount.h:238
Inline: True
Inline callers:
  - kernel/cpuset.c:proc_cpuset_show
  - kernel/cpuset.c:cpuset_hotplug_workfn
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/cpuset.c:cpuset_write_resmask
```
```
In kernel/memremap.c (ffffffff811adb5a)
Location: include/linux/percpu-refcount.h:238
Inline: True
Inline callers:
  - kernel/memremap.c:devm_memremap_pages_release
```
```
In mm/page-writeback.c (ffffffff811bf66b)
Location: include/linux/percpu-refcount.h:238
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/gup.c (ffffffff811e4c6f)
Location: include/linux/percpu-refcount.h:238
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/huge_memory.c (ffffffff81226f36)
Location: include/linux/percpu-refcount.h:238
Inline: True
Inline callers:
  - mm/huge_memory.c:follow_devmap_pmd
```
```
In mm/memcontrol.c (ffffffff812367d4)
Location: include/linux/percpu-refcount.h:238
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:get_mem_cgroup_from_mm
  - mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node
```
```
In mm/hugetlb_cgroup.c (ffffffff81238097)
Location: include/linux/percpu-refcount.h:238
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In fs/fs-writeback.c (ffffffff81275ea7)
Location: include/linux/percpu-refcount.h:238
Inline: True
Inline callers:
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In block/bio.c (ffffffff8140e39f)
Location: include/linux/percpu-refcount.h:238
Inline: True
Inline callers:
  - block/bio.c:bio_associate_current
```
```
In block/blk-core.c (ffffffff8141814b)
Location: include/linux/percpu-refcount.h:238
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-cgroup.c (ffffffff81438fbe)
Location: include/linux/percpu-refcount.h:238
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_create
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
In kernel/cgroup/cgroup.c (ffffffff81128925)
Location: include/linux/percpu-refcount.h:239
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_tryget_online_from_dir
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8112aa47)
Location: include/linux/percpu-refcount.h:239
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_mount
  - kernel/cgroup/cgroup-v1.c:cgroup1_mount
```
```
In kernel/cgroup/freezer.c (ffffffff8112b33f)
Location: include/linux/percpu-refcount.h:239
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:freezer_write
  - kernel/cgroup/freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (ffffffff8112bf67)
Location: include/linux/percpu-refcount.h:239
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffff81130933)
Location: include/linux/percpu-refcount.h:239
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In kernel/memremap.c (ffffffff811b50c6)
Location: include/linux/percpu-refcount.h:239
Inline: True
Inline callers:
  - kernel/memremap.c:devm_memremap_pages_release
```
```
In mm/page-writeback.c (ffffffff811c7463)
Location: include/linux/percpu-refcount.h:239
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/gup.c (ffffffff811f0cd1)
Location: include/linux/percpu-refcount.h:239
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages_fast
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:follow_page_pte
```
```
In mm/huge_memory.c (ffffffff812332a5)
Location: include/linux/percpu-refcount.h:239
Inline: True
Inline callers:
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:follow_devmap_pmd
```
```
In mm/memcontrol.c (ffffffff8124223a)
Location: include/linux/percpu-refcount.h:239
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:get_mem_cgroup_from_mm
  - mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node
```
```
In mm/hugetlb_cgroup.c (ffffffff81243d04)
Location: include/linux/percpu-refcount.h:239
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In fs/fs-writeback.c (ffffffff812832d5)
Location: include/linux/percpu-refcount.h:239
Inline: True
Inline callers:
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In block/bio.c (ffffffff8141bf8b)
Location: include/linux/percpu-refcount.h:239
Inline: True
Inline callers:
  - block/bio.c:bio_associate_current
```
```
In block/blk-core.c (ffffffff81425fef)
Location: include/linux/percpu-refcount.h:239
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-cgroup.c (ffffffff81446745)
Location: include/linux/percpu-refcount.h:239
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_create
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
In kernel/cgroup/cgroup.c (ffffffff81134f75)
Location: include/linux/percpu-refcount.h:240
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_tryget_online_from_dir
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff811377d7)
Location: include/linux/percpu-refcount.h:240
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_mount
  - kernel/cgroup/cgroup-v1.c:cgroup1_mount
```
```
In kernel/cgroup/freezer.c (ffffffff8113813f)
Location: include/linux/percpu-refcount.h:240
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:freezer_write
  - kernel/cgroup/freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (ffffffff81138d77)
Location: include/linux/percpu-refcount.h:240
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffff8113d873)
Location: include/linux/percpu-refcount.h:240
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In kernel/memremap.c (ffffffff811c937b)
Location: include/linux/percpu-refcount.h:240
Inline: True
Inline callers:
  - kernel/memremap.c:devm_memremap_pages_release
```
```
In mm/page-writeback.c (ffffffff811dc279)
Location: include/linux/percpu-refcount.h:240
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/gup.c (ffffffff8120581f)
Location: include/linux/percpu-refcount.h:240
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:follow_page_pte
```
```
In mm/huge_memory.c (ffffffff81250be1)
Location: include/linux/percpu-refcount.h:240
Inline: True
Inline callers:
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:follow_devmap_pmd
```
```
In mm/memcontrol.c (ffffffff8126202e)
Location: include/linux/percpu-refcount.h:240
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:get_mem_cgroup_from_mm
  - mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node
```
```
In mm/hugetlb_cgroup.c (ffffffff81263b54)
Location: include/linux/percpu-refcount.h:240
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In mm/hmm.c (ffffffff8126e290)
Location: include/linux/percpu-refcount.h:240
Inline: True
Inline callers:
  - mm/hmm.c:hmm_devmem_release
```
```
In fs/fs-writeback.c (ffffffff812a5e45)
Location: include/linux/percpu-refcount.h:240
Inline: True
Inline callers:
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In block/blk-core.c (ffffffff8145145b)
Location: include/linux/percpu-refcount.h:240
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-cgroup.c (ffffffff81473315)
Location: include/linux/percpu-refcount.h:240
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_create
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
In kernel/cgroup/cgroup.c (ffffffff811436b5)
Location: include/linux/percpu-refcount.h:246
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_tryget_online_from_dir
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8114608a)
Location: include/linux/percpu-refcount.h:246
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_mount
  - kernel/cgroup/cgroup-v1.c:cgroup1_mount
```
```
In kernel/cgroup/freezer.c (ffffffff81146945)
Location: include/linux/percpu-refcount.h:246
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:freezer_write
  - kernel/cgroup/freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (ffffffff811479e0)
Location: include/linux/percpu-refcount.h:246
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffff8114c142)
Location: include/linux/percpu-refcount.h:246
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In kernel/memremap.c (ffffffff811e96b3)
Location: include/linux/percpu-refcount.h:246
Inline: True
Inline callers:
  - kernel/memremap.c:get_dev_pagemap
  - kernel/memremap.c:devm_memremap_pages_release
```
```
In mm/page-writeback.c (ffffffff811fdb7f)
Location: include/linux/percpu-refcount.h:246
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/memcontrol.c (ffffffff81286071)
Location: include/linux/percpu-refcount.h:246
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:get_mem_cgroup_from_mm
```
```
In mm/hugetlb_cgroup.c (ffffffff81287ecd)
Location: include/linux/percpu-refcount.h:246
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In mm/hmm.c (ffffffff81292790)
Location: include/linux/percpu-refcount.h:246
Inline: True
Inline callers:
  - mm/hmm.c:hmm_devmem_release
```
```
In fs/fs-writeback.c (ffffffff812ccaa9)
Location: include/linux/percpu-refcount.h:246
Inline: True
Inline callers:
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/aio.c (ffffffff812f28f2)
Location: include/linux/percpu-refcount.h:246
Inline: True
Inline callers:
  - fs/aio.c:lookup_ioctx
```
```
In block/blk-core.c (ffffffff814846ca)
Location: include/linux/percpu-refcount.h:246
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-cgroup.c (ffffffff814a7cca)
Location: include/linux/percpu-refcount.h:246
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_create
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
In kernel/cgroup/cgroup.c (ffffffff8114f1e5)
Location: include/linux/percpu-refcount.h:247
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_tryget_online_from_dir
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81151c4a)
Location: include/linux/percpu-refcount.h:247
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_mount
  - kernel/cgroup/cgroup-v1.c:cgroup1_mount
```
```
In kernel/cgroup/freezer.c (ffffffff81152614)
Location: include/linux/percpu-refcount.h:247
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:freezer_write
  - kernel/cgroup/freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (ffffffff81153299)
Location: include/linux/percpu-refcount.h:247
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffff81158d84)
Location: include/linux/percpu-refcount.h:247
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
```
In kernel/memremap.c (ffffffff811fa04d)
Location: include/linux/percpu-refcount.h:247
Inline: True
Inline callers:
  - kernel/memremap.c:get_dev_pagemap
```
```
In mm/page-writeback.c (ffffffff8121069e)
Location: include/linux/percpu-refcount.h:247
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/memcontrol.c (ffffffff8129afd2)
Location: include/linux/percpu-refcount.h:247
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:memcg_kmem_charge
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:get_mem_cgroup_from_page
```
```
In mm/hugetlb_cgroup.c (ffffffff8129ce19)
Location: include/linux/percpu-refcount.h:247
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In fs/fs-writeback.c (ffffffff812e1da9)
Location: include/linux/percpu-refcount.h:247
Inline: True
Inline callers:
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/aio.c (ffffffff813069fe)
Location: include/linux/percpu-refcount.h:247
Inline: True
Inline callers:
  - fs/aio.c:lookup_ioctx
```
```
In block/blk-core.c (ffffffff8149f6bd)
Location: include/linux/percpu-refcount.h:247
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-cgroup.c (ffffffff814c27cd)
Location: include/linux/percpu-refcount.h:247
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_create
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
In kernel/cgroup/cgroup.c (ffffffff8115af13)
Location: include/linux/percpu-refcount.h:255
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_tryget_online_from_dir
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8115d917)
Location: include/linux/percpu-refcount.h:255
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff8115ec74)
Location: include/linux/percpu-refcount.h:255
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/cpuset.c (ffffffff81164b30)
Location: include/linux/percpu-refcount.h:255
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
```
In mm/slub.c (ffffffff81293fcb)
Location: include/linux/percpu-refcount.h:255
Inline: True
Inline callers:
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (ffffffff812b62a2)
Location: include/linux/percpu-refcount.h:255
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:__memcg_kmem_charge
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:get_mem_cgroup_from_page
  - mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node
```
```
In mm/hugetlb_cgroup.c (ffffffff812b7fc2)
Location: include/linux/percpu-refcount.h:255
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In mm/memremap.c (ffffffff812c24bd)
Location: include/linux/percpu-refcount.h:255
Inline: True
Inline callers:
  - mm/memremap.c:get_dev_pagemap
```
```
In fs/aio.c (ffffffff81327ff0)
Location: include/linux/percpu-refcount.h:255
Inline: True
Inline callers:
  - fs/aio.c:lookup_ioctx
```
```
In block/blk-core.c (ffffffff814cd7b2)
Location: include/linux/percpu-refcount.h:255
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-cgroup.c (ffffffff814f0de9)
Location: include/linux/percpu-refcount.h:255
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_create
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
In kernel/cgroup/cgroup.c (ffffffff81166bc3)
Location: include/linux/percpu-refcount.h:255
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_tryget_online_from_dir
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81169527)
Location: include/linux/percpu-refcount.h:255
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff8116a8d4)
Location: include/linux/percpu-refcount.h:255
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/cpuset.c (ffffffff81170a10)
Location: include/linux/percpu-refcount.h:255
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
```
In mm/slub.c (ffffffff812a3d3b)
Location: include/linux/percpu-refcount.h:255
Inline: True
Inline callers:
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (ffffffff812c817f)
Location: include/linux/percpu-refcount.h:255
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:__memcg_kmem_charge
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:get_mem_cgroup_from_page
  - mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node
```
```
In mm/memremap.c (ffffffff812d43ed)
Location: include/linux/percpu-refcount.h:255
Inline: True
Inline callers:
  - mm/memremap.c:get_dev_pagemap
```
```
In fs/aio.c (ffffffff8133ad90)
Location: include/linux/percpu-refcount.h:255
Inline: True
Inline callers:
  - fs/aio.c:lookup_ioctx
```
```
In block/blk-core.c (ffffffff814e6aa2)
Location: include/linux/percpu-refcount.h:255
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-cgroup.c (ffffffff8150a3c4)
Location: include/linux/percpu-refcount.h:255
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_create
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
In kernel/cgroup/cgroup.c (ffffffff81177d51)
Location: include/linux/percpu-refcount.h:271
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_tryget_online_from_dir
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8117b309)
Location: include/linux/percpu-refcount.h:271
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff8117c382)
Location: include/linux/percpu-refcount.h:271
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_change_state
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/cpuset.c (ffffffff81182790)
Location: include/linux/percpu-refcount.h:271
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:update_nodemasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
```
In mm/slub.c (ffffffff812d9804)
Location: include/linux/percpu-refcount.h:271
Inline: True
Inline callers:
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (ffffffff812fe211)
Location: include/linux/percpu-refcount.h:271
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_charge
  - mm/memcontrol.c:memcg_kmem_get_cache
```
```
In mm/memremap.c (ffffffff8130a09d)
Location: include/linux/percpu-refcount.h:271
Inline: True
Inline callers:
  - mm/memremap.c:get_dev_pagemap
```
```
In fs/aio.c (ffffffff81374e8e)
Location: include/linux/percpu-refcount.h:271
Inline: True
Inline callers:
  - fs/aio.c:lookup_ioctx
```
```
In block/blk-core.c (ffffffff81544d3d)
Location: include/linux/percpu-refcount.h:271
Inline: True
Inline callers:
  - block/blk-core.c:blk_queue_enter
```
```
In block/genhd.c (ffffffff8155a703)
Location: include/linux/percpu-refcount.h:271
Inline: True
Inline callers:
  - block/genhd.c:disk_map_sector_rcu
  - block/genhd.c:disk_map_sector_rcu
```
```
In block/blk-cgroup.c (ffffffff8156b578)
Location: include/linux/percpu-refcount.h:271
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_create
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
In kernel/cgroup/cgroup.c (ffffffff81174a5f)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_tryget_online_from_dir
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff811781d9)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff811791ed)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_change_state
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/cpuset.c (ffffffff8117f6ae)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:update_nodemasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
```
In mm/memcontrol.c (ffffffff8130a734)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_charge
```
```
In mm/memremap.c (ffffffff81315d59)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - mm/memremap.c:get_dev_pagemap
```
```
In fs/aio.c (ffffffff81382e1a)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - fs/aio.c:lookup_ioctx
```
```
In fs/io_uring.c (ffffffff81396c2b)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_grab_identity
```
```
In block/blk-core.c (ffffffff815612d4)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-cgroup.c (ffffffff81586087)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_create
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
In kernel/cgroup/cgroup.c (ffffffff8117561f)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_tryget_online_from_dir
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81178d59)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff81179d5d)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_change_state
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/cpuset.c (ffffffff8117fcee)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:update_nodemasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
```
In mm/memcontrol.c (ffffffff81310333)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swapin_charge_page
```
```
In mm/memremap.c (ffffffff8131bf4c)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - mm/memremap.c:get_dev_pagemap
```
```
In fs/aio.c (ffffffff81389e8d)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - fs/aio.c:lookup_ioctx
```
```
In block/blk-core.c (ffffffff81569a24)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-cgroup.c (ffffffff8158ca77)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_create
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
In kernel/cgroup/cgroup.c (ffffffff8119cb99)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_tryget_online_from_dir
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff811a0689)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff811a167d)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_change_state
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/cpuset.c (ffffffff811a7db8)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:update_nodemasks_hier
  - kernel/cgroup/cpuset.c:update_sibling_cpumasks
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
```
In mm/swapfile.c (ffffffff81313785)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_device
```
```
In mm/memcontrol.c (ffffffff8135b660)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swapin_charge_page
```
```
In mm/memremap.c (ffffffff8136922c)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - mm/memremap.c:get_dev_pagemap
```
```
In fs/aio.c (ffffffff813d716d)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - fs/aio.c:lookup_ioctx
```
```
In block/blk-core.c (ffffffff815cc5d4)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - block/blk-core.c:blk_try_enter_queue
```
```
In block/blk-cgroup.c (ffffffff815f21ee)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_create
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
In kernel/cgroup/cgroup.c (ffffffff811ccea4)
Location: include/linux/percpu-refcount.h:306
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_tryget_online_from_dir
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff811d0de2)
Location: include/linux/percpu-refcount.h:306
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff811d1fc0)
Location: include/linux/percpu-refcount.h:306
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_change_state
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/cpuset.c (ffffffff811d8ec5)
Location: include/linux/percpu-refcount.h:306
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:update_nodemasks_hier
  - kernel/cgroup/cpuset.c:update_sibling_cpumasks
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
```
In mm/swapfile.c (ffffffff8137edd7)
Location: include/linux/percpu-refcount.h:306
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_device
```
```
In mm/memcontrol.c (ffffffff813d4e4f)
Location: include/linux/percpu-refcount.h:306
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swapin_charge_page
```
```
In mm/memremap.c (ffffffff813e7044)
Location: include/linux/percpu-refcount.h:306
Inline: True
Inline callers:
  - mm/memremap.c:get_dev_pagemap
```
```
In fs/aio.c (ffffffff81460ce9)
Location: include/linux/percpu-refcount.h:306
Inline: True
Inline callers:
  - fs/aio.c:lookup_ioctx
```
```
In block/blk-cgroup.c (ffffffff816a3a10)
Location: include/linux/percpu-refcount.h:306
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_create
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
In kernel/cgroup/cgroup.c (ffffffff81210453)
Location: include/linux/percpu-refcount.h:306
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_tryget_online_from_dir
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81214942)
Location: include/linux/percpu-refcount.h:306
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff81215cf0)
Location: include/linux/percpu-refcount.h:306
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_change_state
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/cpuset.c (ffffffff8121e09e)
Location: include/linux/percpu-refcount.h:306
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:update_nodemasks_hier
  - kernel/cgroup/cpuset.c:update_sibling_cpumasks
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
```
In mm/swapfile.c (ffffffff813fd8bf)
Location: include/linux/percpu-refcount.h:306
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_device
```
```
In mm/memcontrol.c (ffffffff8145a88e)
Location: include/linux/percpu-refcount.h:306
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swapin_charge_folio
```
```
In mm/memremap.c (ffffffff8146f830)
Location: include/linux/percpu-refcount.h:306
Inline: True
Inline callers:
  - mm/memremap.c:zone_device_page_init
```
```
In fs/aio.c (ffffffff814f0c99)
Location: include/linux/percpu-refcount.h:306
Inline: True
Inline callers:
  - fs/aio.c:lookup_ioctx
```
```
In block/blk-cgroup.c (ffffffff817626f9)
Location: include/linux/percpu-refcount.h:306
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_create
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
In kernel/cgroup/cgroup.c (ffffffff81225e63)
Location: include/linux/percpu-refcount.h:306
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_tryget_online_from_dir
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8122a262)
Location: include/linux/percpu-refcount.h:306
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff8122b624)
Location: include/linux/percpu-refcount.h:306
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_change_state
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/cpuset.c (ffffffff8123419e)
Location: include/linux/percpu-refcount.h:306
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:update_nodemasks_hier
  - kernel/cgroup/cpuset.c:update_sibling_cpumasks
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
```
In mm/swapfile.c (ffffffff81430b7f)
Location: include/linux/percpu-refcount.h:306
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_device
```
```
In mm/memcontrol.c (ffffffff814904ee)
Location: include/linux/percpu-refcount.h:306
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swapin_charge_folio
```
```
In mm/memremap.c (ffffffff814a4010)
Location: include/linux/percpu-refcount.h:306
Inline: True
Inline callers:
  - mm/memremap.c:zone_device_page_init
```
```
In fs/aio.c (ffffffff81527a39)
Location: include/linux/percpu-refcount.h:306
Inline: True
Inline callers:
  - fs/aio.c:lookup_ioctx
```
```
In block/blk-cgroup.c (ffffffff817a13a5)
Location: include/linux/percpu-refcount.h:306
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_create
```
```
In drivers/md/md.c (ffffffff81d5fcaf)
Location: include/linux/percpu-refcount.h:306
Inline: True
Inline callers:
  - drivers/md/md.c:md_handle_request
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
In kernel/cgroup/cgroup.c (ffffffff8123daf3)
Location: include/linux/percpu-refcount.h:306
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_tryget_online_from_dir
  - kernel/cgroup/cgroup.c:cgroup_tryget_css
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81242102)
Location: include/linux/percpu-refcount.h:306
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff81243614)
Location: include/linux/percpu-refcount.h:306
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_change_state
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/cpuset.c (ffffffff8124dd38)
Location: include/linux/percpu-refcount.h:306
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:update_nodemasks_hier
  - kernel/cgroup/cpuset.c:update_sibling_cpumasks
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
```
In mm/swapfile.c (ffffffff81469f9f)
Location: include/linux/percpu-refcount.h:306
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_device
```
```
In mm/zswap.c (ffffffff8146f7ea)
Location: include/linux/percpu-refcount.h:306
Inline: True
Inline callers:
  - mm/zswap.c:shrink_worker
```
```
In mm/memcontrol.c (ffffffff814bfdd6)
Location: include/linux/percpu-refcount.h:306
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swapin_charge_folio
```
```
In mm/memremap.c (ffffffff814d4ec0)
Location: include/linux/percpu-refcount.h:306
Inline: True
Inline callers:
  - mm/memremap.c:zone_device_page_init
```
```
In fs/aio.c (ffffffff8155c7c9)
Location: include/linux/percpu-refcount.h:306
Inline: True
Inline callers:
  - fs/aio.c:lookup_ioctx
```
```
In block/blk-cgroup.c (ffffffff817e4ef2)
Location: include/linux/percpu-refcount.h:306
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_create
```
```
In drivers/md/md.c (ffffffff81e1728b)
Location: include/linux/percpu-refcount.h:306
Inline: True
Inline callers:
  - drivers/md/md.c:md_handle_request
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool percpu_ref_tryget_live(struct percpu_ref *ref);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffff8000101d189c)
Location: include/linux/percpu-refcount.h:255
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
Direct callers:
  - kernel/cgroup/cgroup.c:css_tryget_online_from_dir
```
```
In kernel/cgroup/cgroup-v1.c (ffff8000101dc76c)
Location: include/linux/percpu-refcount.h:255
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In kernel/cgroup/legacy_freezer.c (ffff8000101de7e4)
Location: include/linux/percpu-refcount.h:255
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/cpuset.c (ffff8000101e4144)
Location: include/linux/percpu-refcount.h:255
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
```
In mm/slub.c (ffff800010345a14)
Location: include/linux/percpu-refcount.h:255
Inline: True
Inline callers:
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (ffff800010364ad8)
Location: include/linux/percpu-refcount.h:255
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:__memcg_kmem_charge
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:get_mem_cgroup_from_page
  - mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node
```
```
In fs/aio.c (ffff8000103fbfa4)
Location: include/linux/percpu-refcount.h:255
Inline: True
Inline callers:
  - fs/aio.c:lookup_ioctx
```
```
In block/blk-core.c (ffff8000105e42d4)
Location: include/linux/percpu-refcount.h:255
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-cgroup.c (ffff80001060dae4)
Location: include/linux/percpu-refcount.h:255
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_create
```
**Symbols:**

```
ffff8000101d0048-ffff8000101d00f0: percpu_ref_tryget_live (STB_LOCAL)
ffff800010364ad8-ffff800010364b80: percpu_ref_tryget_live (STB_LOCAL)
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
In kernel/cgroup/cgroup.c (c041b608)
Location: include/linux/percpu-refcount.h:255
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_tryget_online_from_dir
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/cgroup-v1.c (c041ea24)
Location: include/linux/percpu-refcount.h:255
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In kernel/cgroup/legacy_freezer.c (c042026c)
Location: include/linux/percpu-refcount.h:255
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/cpuset.c (c04250a4)
Location: include/linux/percpu-refcount.h:255
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
```
In mm/slub.c (c05497d0)
Location: include/linux/percpu-refcount.h:255
Inline: True
Inline callers:
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (c055c714)
Location: include/linux/percpu-refcount.h:255
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:__memcg_kmem_charge
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:get_mem_cgroup_from_page
  - mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node
```
```
In fs/aio.c (c05ced64)
Location: include/linux/percpu-refcount.h:255
Inline: True
Inline callers:
  - fs/aio.c:lookup_ioctx
```
```
In block/blk-core.c (c07915d0)
Location: include/linux/percpu-refcount.h:255
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-cgroup.c (c07b8638)
Location: include/linux/percpu-refcount.h:255
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_create
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
In kernel/cgroup/cgroup.c (c000000000245c60)
Location: include/linux/percpu-refcount.h:255
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_tryget_online_from_dir
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/cgroup-v1.c (c00000000024a484)
Location: include/linux/percpu-refcount.h:255
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In kernel/cgroup/legacy_freezer.c (c00000000024c8a0)
Location: include/linux/percpu-refcount.h:255
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/cpuset.c (c000000000254704)
Location: include/linux/percpu-refcount.h:255
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
```
In mm/slub.c (c000000000422010)
Location: include/linux/percpu-refcount.h:255
Inline: True
Inline callers:
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (c00000000045a800)
Location: include/linux/percpu-refcount.h:255
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:__memcg_kmem_charge
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:get_mem_cgroup_from_page
  - mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node
```
```
In mm/memremap.c (c00000000046dab8)
Location: include/linux/percpu-refcount.h:255
Inline: True
Inline callers:
  - mm/memremap.c:get_dev_pagemap
```
```
In fs/aio.c (c000000000504000)
Location: include/linux/percpu-refcount.h:255
Inline: True
Inline callers:
  - fs/aio.c:lookup_ioctx
```
```
In block/blk-core.c (c000000000778034)
Location: include/linux/percpu-refcount.h:255
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-cgroup.c (c0000000007aad20)
Location: include/linux/percpu-refcount.h:255
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_create
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
In kernel/cgroup/cgroup.c (ffffffe000151968)
Location: include/linux/percpu-refcount.h:255
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_tryget_online_from_dir
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/cgroup-v1.c (ffffffe0001546ea)
Location: include/linux/percpu-refcount.h:255
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In kernel/cgroup/legacy_freezer.c (ffffffe000155be2)
Location: include/linux/percpu-refcount.h:255
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/cpuset.c (ffffffe00015a4fc)
Location: include/linux/percpu-refcount.h:255
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
```
In mm/slub.c (ffffffe000238082)
Location: include/linux/percpu-refcount.h:255
Inline: True
Inline callers:
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (ffffffe0002487bc)
Location: include/linux/percpu-refcount.h:255
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:__memcg_kmem_charge
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:get_mem_cgroup_from_page
  - mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node
```
```
In fs/aio.c (ffffffe0002a92b6)
Location: include/linux/percpu-refcount.h:255
Inline: True
Inline callers:
  - fs/aio.c:lookup_ioctx
```
```
In block/blk-core.c (ffffffe000425b5c)
Location: include/linux/percpu-refcount.h:255
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-cgroup.c (ffffffe000446274)
Location: include/linux/percpu-refcount.h:255
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_create
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
In kernel/cgroup/cgroup.c (ffffffff8115f1e3)
Location: include/linux/percpu-refcount.h:255
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_tryget_online_from_dir
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81161b47)
Location: include/linux/percpu-refcount.h:255
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff81162ef4)
Location: include/linux/percpu-refcount.h:255
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/cpuset.c (ffffffff81169030)
Location: include/linux/percpu-refcount.h:255
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
```
In mm/slub.c (ffffffff8129c31b)
Location: include/linux/percpu-refcount.h:255
Inline: True
Inline callers:
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (ffffffff812c075f)
Location: include/linux/percpu-refcount.h:255
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:__memcg_kmem_charge
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:get_mem_cgroup_from_page
  - mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node
```
```
In mm/memremap.c (ffffffff812cc9cd)
Location: include/linux/percpu-refcount.h:255
Inline: True
Inline callers:
  - mm/memremap.c:get_dev_pagemap
```
```
In fs/aio.c (ffffffff81333370)
Location: include/linux/percpu-refcount.h:255
Inline: True
Inline callers:
  - fs/aio.c:lookup_ioctx
```
```
In block/blk-core.c (ffffffff814df082)
Location: include/linux/percpu-refcount.h:255
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-cgroup.c (ffffffff815029a4)
Location: include/linux/percpu-refcount.h:255
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_create
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
In kernel/cgroup/cgroup.c (ffffffff81152473)
Location: include/linux/percpu-refcount.h:255
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_tryget_online_from_dir
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81154da7)
Location: include/linux/percpu-refcount.h:255
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff81156144)
Location: include/linux/percpu-refcount.h:255
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/cpuset.c (ffffffff8115c23a)
Location: include/linux/percpu-refcount.h:255
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
```
In mm/slub.c (ffffffff8128decc)
Location: include/linux/percpu-refcount.h:255
Inline: True
Inline callers:
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (ffffffff812b181f)
Location: include/linux/percpu-refcount.h:255
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:__memcg_kmem_charge
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:get_mem_cgroup_from_page
  - mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node
```
```
In mm/memremap.c (ffffffff812bd83d)
Location: include/linux/percpu-refcount.h:255
Inline: True
Inline callers:
  - mm/memremap.c:get_dev_pagemap
```
```
In fs/aio.c (ffffffff81323fe0)
Location: include/linux/percpu-refcount.h:255
Inline: True
Inline callers:
  - fs/aio.c:lookup_ioctx
```
```
In block/blk-core.c (ffffffff814cfa22)
Location: include/linux/percpu-refcount.h:255
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-cgroup.c (ffffffff814f3154)
Location: include/linux/percpu-refcount.h:255
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_create
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
In kernel/cgroup/cgroup.c (ffffffff8115cfb3)
Location: include/linux/percpu-refcount.h:255
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_tryget_online_from_dir
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8115f917)
Location: include/linux/percpu-refcount.h:255
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff81160cc4)
Location: include/linux/percpu-refcount.h:255
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/cpuset.c (ffffffff81166e00)
Location: include/linux/percpu-refcount.h:255
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
```
In mm/slub.c (ffffffff8129a12b)
Location: include/linux/percpu-refcount.h:255
Inline: True
Inline callers:
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (ffffffff812be56f)
Location: include/linux/percpu-refcount.h:255
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:__memcg_kmem_charge
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:get_mem_cgroup_from_page
  - mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node
```
```
In mm/memremap.c (ffffffff812ca7dd)
Location: include/linux/percpu-refcount.h:255
Inline: True
Inline callers:
  - mm/memremap.c:get_dev_pagemap
```
```
In fs/aio.c (ffffffff81330e40)
Location: include/linux/percpu-refcount.h:255
Inline: True
Inline callers:
  - fs/aio.c:lookup_ioctx
```
```
In block/blk-core.c (ffffffff814db112)
Location: include/linux/percpu-refcount.h:255
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-cgroup.c (ffffffff814fea34)
Location: include/linux/percpu-refcount.h:255
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_create
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
In kernel/cgroup/cgroup.c (ffffffff8116a0ba)
Location: include/linux/percpu-refcount.h:255
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_tryget_online_from_dir
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8116cbc2)
Location: include/linux/percpu-refcount.h:255
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff8116e0d2)
Location: include/linux/percpu-refcount.h:255
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/cpuset.c (ffffffff8117455c)
Location: include/linux/percpu-refcount.h:255
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
```
In mm/slub.c (ffffffff812a9fa8)
Location: include/linux/percpu-refcount.h:255
Inline: True
Inline callers:
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (ffffffff812cef95)
Location: include/linux/percpu-refcount.h:255
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:__memcg_kmem_charge
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:get_mem_cgroup_from_page
  - mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node
```
```
In mm/memremap.c (ffffffff812db4f4)
Location: include/linux/percpu-refcount.h:255
Inline: True
Inline callers:
  - mm/memremap.c:get_dev_pagemap
```
```
In fs/aio.c (ffffffff81343a1d)
Location: include/linux/percpu-refcount.h:255
Inline: True
Inline callers:
  - fs/aio.c:lookup_ioctx
```
```
In block/blk-core.c (ffffffff814f3f18)
Location: include/linux/percpu-refcount.h:255
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-cgroup.c (ffffffff81517d98)
Location: include/linux/percpu-refcount.h:255
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_create
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
