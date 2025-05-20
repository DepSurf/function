# Function: <code>css_tryget_online</code>

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
In kernel/cgroup.c (ffffffff81115ff3)
Location: include/linux/cgroup.h:340
Inline: True
Inline callers:
  - kernel/cgroup.c:cgroup_get_e_css
  - kernel/cgroup.c:css_tryget_online_from_dir
```
```
In kernel/cgroup_freezer.c (ffffffff81119f17)
Location: include/linux/cgroup.h:340
Inline: True
Inline callers:
  - kernel/cgroup_freezer.c:freezer_read
  - kernel/cgroup_freezer.c:freezer_write
```
```
In kernel/cpuset.c (ffffffff8111c727)
Location: include/linux/cgroup.h:340
Inline: True
Inline callers:
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/cpuset.c:cpuset_hotplug_workfn
  - kernel/cpuset.c:proc_cpuset_show
```
```
In mm/page-writeback.c (ffffffff8119a5f4)
Location: include/linux/cgroup.h:340
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/memcontrol.c (ffffffff811fadfb)
Location: include/linux/cgroup.h:340
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mem_cgroup_from_mm
  - mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node
  - mm/memcontrol.c:mem_cgroup_try_charge
```
```
In mm/hugetlb_cgroup.c (ffffffff812012d9)
Location: include/linux/cgroup.h:340
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In fs/fs-writeback.c (ffffffff8123ab33)
Location: include/linux/cgroup.h:340
Inline: True
Inline callers:
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In block/bio.c (ffffffff813b0fac)
Location: include/linux/cgroup.h:340
Inline: True
Inline callers:
  - block/bio.c:bio_associate_current
```
```
In block/blk-cgroup.c (ffffffff813d7c55)
Location: include/linux/cgroup.h:340
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
In kernel/cgroup.c (ffffffff811215de)
Location: include/linux/cgroup.h:339
Inline: True
Inline callers:
  - kernel/cgroup.c:css_tryget_online_from_dir
  - kernel/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup_freezer.c (ffffffff81121fc4)
Location: include/linux/cgroup.h:339
Inline: True
Inline callers:
  - kernel/cgroup_freezer.c:freezer_write
  - kernel/cgroup_freezer.c:freezer_read
```
```
In kernel/cpuset.c (ffffffff81125847)
Location: include/linux/cgroup.h:339
Inline: True
Inline callers:
  - kernel/cpuset.c:proc_cpuset_show
  - kernel/cpuset.c:cpuset_hotplug_workfn
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/cpuset.c:cpuset_write_resmask
```
```
In mm/page-writeback.c (ffffffff811aef04)
Location: include/linux/cgroup.h:339
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/memcontrol.c (ffffffff81223fd1)
Location: include/linux/cgroup.h:339
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:get_mem_cgroup_from_mm
  - mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node
```
```
In mm/hugetlb_cgroup.c (ffffffff81225ab1)
Location: include/linux/cgroup.h:339
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In fs/fs-writeback.c (ffffffff812629d3)
Location: include/linux/cgroup.h:339
Inline: True
Inline callers:
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In block/bio.c (ffffffff813f499c)
Location: include/linux/cgroup.h:339
Inline: True
Inline callers:
  - block/bio.c:bio_associate_current
```
```
In block/blk-cgroup.c (ffffffff8141d95f)
Location: include/linux/cgroup.h:339
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
In kernel/cgroup.c (ffffffff81129b5e)
Location: include/linux/cgroup.h:339
Inline: True
Inline callers:
  - kernel/cgroup.c:css_tryget_online_from_dir
  - kernel/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup_freezer.c (ffffffff8112a5f4)
Location: include/linux/cgroup.h:339
Inline: True
Inline callers:
  - kernel/cgroup_freezer.c:freezer_write
  - kernel/cgroup_freezer.c:freezer_read
```
```
In kernel/cpuset.c (ffffffff8112f234)
Location: include/linux/cgroup.h:339
Inline: True
Inline callers:
  - kernel/cpuset.c:proc_cpuset_show
  - kernel/cpuset.c:cpuset_hotplug_workfn
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/cpuset.c:cpuset_write_resmask
```
```
In mm/page-writeback.c (ffffffff811bf5b4)
Location: include/linux/cgroup.h:339
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/memcontrol.c (ffffffff812367b2)
Location: include/linux/cgroup.h:339
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:get_mem_cgroup_from_mm
  - mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node
```
```
In mm/hugetlb_cgroup.c (ffffffff81238091)
Location: include/linux/cgroup.h:339
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In fs/fs-writeback.c (ffffffff81275e23)
Location: include/linux/cgroup.h:339
Inline: True
Inline callers:
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In block/bio.c (ffffffff8140e38c)
Location: include/linux/cgroup.h:339
Inline: True
Inline callers:
  - block/bio.c:bio_associate_current
```
```
In block/blk-cgroup.c (ffffffff81438f1f)
Location: include/linux/cgroup.h:339
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
In kernel/cgroup/cgroup.c (ffffffff8112891f)
Location: include/linux/cgroup.h:339
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_tryget_online_from_dir
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/freezer.c (ffffffff8112b332)
Location: include/linux/cgroup.h:339
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:freezer_write
  - kernel/cgroup/freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (ffffffff8112bec9)
Location: include/linux/cgroup.h:339
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffff811308b3)
Location: include/linux/cgroup.h:339
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In mm/page-writeback.c (ffffffff811c72f4)
Location: include/linux/cgroup.h:339
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/memcontrol.c (ffffffff8124223a)
Location: include/linux/cgroup.h:339
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:get_mem_cgroup_from_mm
  - mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node
```
```
In mm/hugetlb_cgroup.c (ffffffff81243cfe)
Location: include/linux/cgroup.h:339
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In fs/fs-writeback.c (ffffffff812832a2)
Location: include/linux/cgroup.h:339
Inline: True
Inline callers:
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In block/bio.c (ffffffff8141bf7d)
Location: include/linux/cgroup.h:339
Inline: True
Inline callers:
  - block/bio.c:bio_associate_current
```
```
In block/blk-cgroup.c (ffffffff8144673f)
Location: include/linux/cgroup.h:339
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
In kernel/cgroup/cgroup.c (ffffffff81134f6f)
Location: include/linux/cgroup.h:351
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_tryget_online_from_dir
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/freezer.c (ffffffff81138132)
Location: include/linux/cgroup.h:351
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:freezer_write
  - kernel/cgroup/freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (ffffffff81138cd9)
Location: include/linux/cgroup.h:351
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffff8113d7f3)
Location: include/linux/cgroup.h:351
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In mm/page-writeback.c (ffffffff811dc104)
Location: include/linux/cgroup.h:351
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/memcontrol.c (ffffffff8126202e)
Location: include/linux/cgroup.h:351
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:get_mem_cgroup_from_mm
  - mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node
```
```
In mm/hugetlb_cgroup.c (ffffffff81263b4e)
Location: include/linux/cgroup.h:351
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In fs/fs-writeback.c (ffffffff812a5e12)
Location: include/linux/cgroup.h:351
Inline: True
Inline callers:
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In block/blk-cgroup.c (ffffffff8147330f)
Location: include/linux/cgroup.h:351
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
In kernel/cgroup/cgroup.c (ffffffff811436af)
Location: include/linux/cgroup.h:351
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_tryget_online_from_dir
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/freezer.c (ffffffff811468f9)
Location: include/linux/cgroup.h:351
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:freezer_write
  - kernel/cgroup/freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (ffffffff81147923)
Location: include/linux/cgroup.h:351
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffff8114c0b2)
Location: include/linux/cgroup.h:351
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In mm/page-writeback.c (ffffffff811fdb2d)
Location: include/linux/cgroup.h:351
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/memcontrol.c (ffffffff81286057)
Location: include/linux/cgroup.h:351
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:get_mem_cgroup_from_mm
```
```
In mm/hugetlb_cgroup.c (ffffffff81287e6e)
Location: include/linux/cgroup.h:351
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In fs/fs-writeback.c (ffffffff812cc9c6)
Location: include/linux/cgroup.h:351
Inline: True
Inline callers:
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In block/blk-cgroup.c (ffffffff814a7af5)
Location: include/linux/cgroup.h:351
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
In kernel/cgroup/cgroup.c (ffffffff8114f1df)
Location: include/linux/cgroup.h:353
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_tryget_online_from_dir
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/freezer.c (ffffffff811525c9)
Location: include/linux/cgroup.h:353
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:freezer_write
  - kernel/cgroup/freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (ffffffff811531e3)
Location: include/linux/cgroup.h:353
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffff81158d02)
Location: include/linux/cgroup.h:353
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
```
In mm/page-writeback.c (ffffffff81210649)
Location: include/linux/cgroup.h:353
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/memcontrol.c (ffffffff8129afb8)
Location: include/linux/cgroup.h:353
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:memcg_kmem_charge
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:get_mem_cgroup_from_page
```
```
In mm/hugetlb_cgroup.c (ffffffff8129cdbe)
Location: include/linux/cgroup.h:353
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In fs/fs-writeback.c (ffffffff812e1ce6)
Location: include/linux/cgroup.h:353
Inline: True
Inline callers:
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In block/blk-cgroup.c (ffffffff814c25c4)
Location: include/linux/cgroup.h:353
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
In kernel/cgroup/cgroup.c (ffffffff8115aecf)
Location: include/linux/cgroup.h:360
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_tryget_online_from_dir
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff8115ec25)
Location: include/linux/cgroup.h:360
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/cpuset.c (ffffffff81164b30)
Location: include/linux/cgroup.h:360
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
```
In mm/slub.c (ffffffff81293e4d)
Location: include/linux/cgroup.h:360
Inline: True
Inline callers:
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (ffffffff812b6288)
Location: include/linux/cgroup.h:360
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
In mm/hugetlb_cgroup.c (ffffffff812b7f5e)
Location: include/linux/cgroup.h:360
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In block/blk-cgroup.c (ffffffff814f0beb)
Location: include/linux/cgroup.h:360
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
In kernel/cgroup/cgroup.c (ffffffff81166b7f)
Location: include/linux/cgroup.h:362
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_tryget_online_from_dir
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff8116a885)
Location: include/linux/cgroup.h:362
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/cpuset.c (ffffffff81170a10)
Location: include/linux/cgroup.h:362
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
```
In mm/slub.c (ffffffff812a3bbd)
Location: include/linux/cgroup.h:362
Inline: True
Inline callers:
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (ffffffff812c8165)
Location: include/linux/cgroup.h:362
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
In block/blk-cgroup.c (ffffffff8150a1c7)
Location: include/linux/cgroup.h:362
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
In kernel/cgroup/cgroup.c (ffffffff81177d4a)
Location: include/linux/cgroup.h:368
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_tryget_online_from_dir
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff8117c344)
Location: include/linux/cgroup.h:368
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_change_state
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/cpuset.c (ffffffff81182790)
Location: include/linux/cgroup.h:368
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:update_nodemasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
```
In mm/slub.c (ffffffff812d9707)
Location: include/linux/cgroup.h:368
Inline: True
Inline callers:
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (ffffffff812fe1e2)
Location: include/linux/cgroup.h:368
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_charge
  - mm/memcontrol.c:memcg_kmem_get_cache
```
```
In block/blk-cgroup.c (ffffffff8156b3b5)
Location: include/linux/cgroup.h:368
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
In kernel/cgroup/cgroup.c (ffffffff81174a57)
Location: include/linux/cgroup.h:368
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_tryget_online_from_dir
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff811791e5)
Location: include/linux/cgroup.h:368
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_change_state
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/cpuset.c (ffffffff8117f6ae)
Location: include/linux/cgroup.h:368
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:update_nodemasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
```
In mm/memcontrol.c (ffffffff8130a65d)
Location: include/linux/cgroup.h:368
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_charge
```
```
In fs/io_uring.c (ffffffff8139699d)
Location: include/linux/cgroup.h:368
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_grab_identity
```
```
In block/blk-cgroup.c (ffffffff81585ebd)
Location: include/linux/cgroup.h:368
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
In kernel/cgroup/cgroup.c (ffffffff81175617)
Location: include/linux/cgroup.h:368
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_tryget_online_from_dir
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff81179d55)
Location: include/linux/cgroup.h:368
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_change_state
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/cpuset.c (ffffffff8117fcee)
Location: include/linux/cgroup.h:368
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:update_nodemasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
```
In mm/memcontrol.c (ffffffff813102c3)
Location: include/linux/cgroup.h:368
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swapin_charge_page
```
```
In block/blk-cgroup.c (ffffffff8158c8ad)
Location: include/linux/cgroup.h:368
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
In kernel/cgroup/cgroup.c (ffffffff8119cb91)
Location: include/linux/cgroup.h:368
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_tryget_online_from_dir
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff811a1675)
Location: include/linux/cgroup.h:368
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_change_state
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/cpuset.c (ffffffff811a7db8)
Location: include/linux/cgroup.h:368
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:update_nodemasks_hier
  - kernel/cgroup/cpuset.c:update_sibling_cpumasks
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
```
In mm/memcontrol.c (ffffffff8135b5f0)
Location: include/linux/cgroup.h:368
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swapin_charge_page
```
```
In block/blk-cgroup.c (ffffffff815f1fad)
Location: include/linux/cgroup.h:368
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
In kernel/cgroup/cgroup.c (ffffffff811cce9e)
Location: include/linux/cgroup.h:368
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_tryget_online_from_dir
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff811d1fba)
Location: include/linux/cgroup.h:368
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_change_state
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/cpuset.c (ffffffff811d8ec5)
Location: include/linux/cgroup.h:368
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:update_nodemasks_hier
  - kernel/cgroup/cpuset.c:update_sibling_cpumasks
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
```
In mm/memcontrol.c (ffffffff813d4d9b)
Location: include/linux/cgroup.h:368
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swapin_charge_page
```
```
In block/blk-cgroup.c (ffffffff816a37ea)
Location: include/linux/cgroup.h:368
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
In kernel/cgroup/cgroup.c (ffffffff8121044d)
Location: include/linux/cgroup_refcnt.h:61
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_tryget_online_from_dir
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff81215cea)
Location: include/linux/cgroup_refcnt.h:61
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_change_state
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/cpuset.c (ffffffff8121e09e)
Location: include/linux/cgroup_refcnt.h:61
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:update_nodemasks_hier
  - kernel/cgroup/cpuset.c:update_sibling_cpumasks
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
```
In mm/memcontrol.c (ffffffff8145a811)
Location: include/linux/cgroup_refcnt.h:61
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swapin_charge_folio
```
```
In block/blk-cgroup.c (ffffffff817624fe)
Location: include/linux/cgroup_refcnt.h:61
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
In kernel/cgroup/cgroup.c (ffffffff81225e5d)
Location: include/linux/cgroup_refcnt.h:61
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_tryget_online_from_dir
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff8122b61e)
Location: include/linux/cgroup_refcnt.h:61
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_change_state
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/cpuset.c (ffffffff8123419e)
Location: include/linux/cgroup_refcnt.h:61
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:update_nodemasks_hier
  - kernel/cgroup/cpuset.c:update_sibling_cpumasks
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
```
In mm/memcontrol.c (ffffffff81490471)
Location: include/linux/cgroup_refcnt.h:61
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swapin_charge_folio
```
```
In block/blk-cgroup.c (ffffffff817a1191)
Location: include/linux/cgroup_refcnt.h:61
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_create
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
In kernel/cgroup/cgroup.c (ffffffff8123daed)
Location: include/linux/cgroup_refcnt.h:61
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_tryget_online_from_dir
  - kernel/cgroup/cgroup.c:cgroup_tryget_css
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff8124360e)
Location: include/linux/cgroup_refcnt.h:61
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_change_state
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/cpuset.c (ffffffff8124dd38)
Location: include/linux/cgroup_refcnt.h:61
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:update_nodemasks_hier
  - kernel/cgroup/cpuset.c:update_sibling_cpumasks
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
```
In mm/zswap.c (ffffffff8146f6b7)
Location: include/linux/cgroup_refcnt.h:61
Inline: True
Inline callers:
  - mm/zswap.c:shrink_worker
```
```
In mm/memcontrol.c (ffffffff814bfd28)
Location: include/linux/cgroup_refcnt.h:61
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swapin_charge_folio
```
```
In block/blk-cgroup.c (ffffffff817e4cde)
Location: include/linux/cgroup_refcnt.h:61
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_create
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
In kernel/cgroup/cgroup.c (ffff8000101d89d4)
Location: include/linux/cgroup.h:362
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_tryget_online_from_dir
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/legacy_freezer.c (ffff8000101de748)
Location: include/linux/cgroup.h:362
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/cpuset.c (ffff8000101e4144)
Location: include/linux/cgroup.h:362
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
```
In mm/slub.c (ffff800010345870)
Location: include/linux/cgroup.h:362
Inline: True
Inline callers:
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (ffff80001036b078)
Location: include/linux/cgroup.h:362
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
In block/blk-cgroup.c (ffff80001060d878)
Location: include/linux/cgroup.h:362
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_create
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
In kernel/cgroup/cgroup.c (c041b5b0)
Location: include/linux/cgroup.h:362
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_tryget_online_from_dir
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/legacy_freezer.c (c04201f4)
Location: include/linux/cgroup.h:362
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/cpuset.c (c04250a4)
Location: include/linux/cgroup.h:362
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
```
In mm/slub.c (c054962c)
Location: include/linux/cgroup.h:362
Inline: True
Inline callers:
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (c055c700)
Location: include/linux/cgroup.h:362
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
In block/blk-cgroup.c (c07b8408)
Location: include/linux/cgroup.h:362
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
In kernel/cgroup/cgroup.c (c000000000245bd8)
Location: include/linux/cgroup.h:362
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_tryget_online_from_dir
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/legacy_freezer.c (c00000000024c7f0)
Location: include/linux/cgroup.h:362
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/cpuset.c (c000000000254704)
Location: include/linux/cgroup.h:362
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
```
In mm/slub.c (c000000000421dbc)
Location: include/linux/cgroup.h:362
Inline: True
Inline callers:
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (c00000000045a7b4)
Location: include/linux/cgroup.h:362
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
In block/blk-cgroup.c (c0000000007aaa00)
Location: include/linux/cgroup.h:362
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
In kernel/cgroup/cgroup.c (ffffffe000151956)
Location: include/linux/cgroup.h:362
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_tryget_online_from_dir
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/legacy_freezer.c (ffffffe000155b82)
Location: include/linux/cgroup.h:362
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/cpuset.c (ffffffe00015a4fc)
Location: include/linux/cgroup.h:362
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
```
In mm/slub.c (ffffffe000238082)
Location: include/linux/cgroup.h:362
Inline: True
Inline callers:
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (ffffffe0002487b0)
Location: include/linux/cgroup.h:362
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
In block/blk-cgroup.c (ffffffe0004460c4)
Location: include/linux/cgroup.h:362
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
In kernel/cgroup/cgroup.c (ffffffff8115f19f)
Location: include/linux/cgroup.h:362
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_tryget_online_from_dir
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff81162ea5)
Location: include/linux/cgroup.h:362
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/cpuset.c (ffffffff81169030)
Location: include/linux/cgroup.h:362
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
```
In mm/slub.c (ffffffff8129c19d)
Location: include/linux/cgroup.h:362
Inline: True
Inline callers:
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (ffffffff812c0745)
Location: include/linux/cgroup.h:362
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
In block/blk-cgroup.c (ffffffff815027a7)
Location: include/linux/cgroup.h:362
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
In kernel/cgroup/cgroup.c (ffffffff8115242f)
Location: include/linux/cgroup.h:362
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_tryget_online_from_dir
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff811560f5)
Location: include/linux/cgroup.h:362
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/cpuset.c (ffffffff8115c23a)
Location: include/linux/cgroup.h:362
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
```
In mm/slub.c (ffffffff8128dd5d)
Location: include/linux/cgroup.h:362
Inline: True
Inline callers:
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (ffffffff812b1805)
Location: include/linux/cgroup.h:362
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
In block/blk-cgroup.c (ffffffff814f2f57)
Location: include/linux/cgroup.h:362
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
In kernel/cgroup/cgroup.c (ffffffff8115cf6f)
Location: include/linux/cgroup.h:362
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_tryget_online_from_dir
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff81160c75)
Location: include/linux/cgroup.h:362
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/cpuset.c (ffffffff81166e00)
Location: include/linux/cgroup.h:362
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
```
In mm/slub.c (ffffffff81299fad)
Location: include/linux/cgroup.h:362
Inline: True
Inline callers:
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (ffffffff812be555)
Location: include/linux/cgroup.h:362
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
In block/blk-cgroup.c (ffffffff814fe837)
Location: include/linux/cgroup.h:362
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
In kernel/cgroup/cgroup.c (ffffffff8116a0a2)
Location: include/linux/cgroup.h:362
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_tryget_online_from_dir
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff8116e063)
Location: include/linux/cgroup.h:362
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/cpuset.c (ffffffff8117455c)
Location: include/linux/cgroup.h:362
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
```
In mm/slub.c (ffffffff812a9df2)
Location: include/linux/cgroup.h:362
Inline: True
Inline callers:
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (ffffffff812cef76)
Location: include/linux/cgroup.h:362
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
In block/blk-cgroup.c (ffffffff81517bfb)
Location: include/linux/cgroup.h:362
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_create
```
</details>
</li>
</ul>

## Differences
