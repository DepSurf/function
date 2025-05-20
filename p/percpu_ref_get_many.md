# Function: <code>percpu_ref_get_many</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cgroup.c (ffffffff811145fd)
Location: include/linux/percpu-refcount.h:170
Inline: True
Inline callers:
  - kernel/cgroup.c:kill_css
  - kernel/cgroup.c:cgroup_get
  - kernel/cgroup.c:init_and_link_css
  - kernel/cgroup.c:find_css_set
  - kernel/cgroup.c:cgroup_get_e_css
```
```
In kernel/cpuset.c (ffffffff8111c7cb)
Location: include/linux/percpu-refcount.h:170
Inline: True
Inline callers:
  - kernel/cpuset.c:cpuset_write_resmask
```
```
In mm/backing-dev.c (ffffffff81208cb7)
Location: include/linux/percpu-refcount.h:170
Inline: True
Direct callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
```
```
In mm/memcontrol.c (ffffffff811fb39b)
Location: include/linux/percpu-refcount.h:170
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:task_in_mem_cgroup
  - mm/memcontrol.c:__memcg_kmem_get_cache
```
```
In fs/fs-writeback.c (ffffffff8123817e)
Location: include/linux/percpu-refcount.h:170
Inline: True
Inline callers:
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/aio.c (ffffffff8125b980)
Location: include/linux/percpu-refcount.h:170
Inline: True
Inline callers:
  - fs/aio.c:lookup_ioctx
  - fs/aio.c:do_io_submit
Direct callers:
  - fs/aio.c:SyS_io_setup
  - fs/aio.c:SyS_io_setup
```
```
In block/bio.c (ffffffff813b10d3)
Location: include/linux/percpu-refcount.h:170
Inline: True
Inline callers:
  - block/bio.c:bio_associate_blkcg
```
```
In block/blk-core.c (ffffffff813baa9e)
Location: include/linux/percpu-refcount.h:170
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
```
```
In block/blk-mq.c (ffffffff813c4bd5)
Location: include/linux/percpu-refcount.h:170
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_map_request
```
```
In lib/percpu-refcount.c (ffffffff813ff20d)
Location: include/linux/percpu-refcount.h:170
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_reinit
```
**Symbols:**

```
ffffffff81208cb7-ffffffff81208cd0: percpu_ref_get_many.constprop.11 (STB_LOCAL)
ffffffff8125b980-ffffffff8125b999: percpu_ref_get_many.constprop.11 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/gup.c (ffffffff810715d4)
Location: include/linux/percpu-refcount.h:168
Inline: True
Inline callers:
  - arch/x86/mm/gup.c:gup_huge_pmd
  - arch/x86/mm/gup.c:gup_pte_range
```
```
In kernel/cgroup.c (ffffffff8111bfab)
Location: include/linux/percpu-refcount.h:168
Inline: True
Inline callers:
  - kernel/cgroup.c:kill_css
  - kernel/cgroup.c:init_and_link_css
  - kernel/cgroup.c:find_css_set
  - kernel/cgroup.c:cgroup_get
  - kernel/cgroup.c:cgroup_get_e_css
```
```
In kernel/cpuset.c (ffffffff811246cb)
Location: include/linux/percpu-refcount.h:168
Inline: True
Inline callers:
  - kernel/cpuset.c:cpuset_write_resmask
```
```
In kernel/memremap.c (ffffffff8119e2f1)
Location: include/linux/percpu-refcount.h:168
Inline: True
Inline callers:
  - kernel/memremap.c:get_zone_device_page
```
```
In mm/backing-dev.c (ffffffff8122e9a6)
Location: include/linux/percpu-refcount.h:168
Inline: True
Direct callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
```
```
In mm/gup.c (0)
Location: include/linux/percpu-refcount.h:168
Inline: True
```
```
In mm/huge_memory.c (0)
Location: include/linux/percpu-refcount.h:168
Inline: True
```
```
In mm/memcontrol.c (ffffffff8122422d)
Location: include/linux/percpu-refcount.h:168
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:task_in_mem_cgroup
```
```
In fs/fs-writeback.c (ffffffff81261ac7)
Location: include/linux/percpu-refcount.h:168
Inline: True
Inline callers:
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
```
```
In fs/aio.c (ffffffff812862ae)
Location: include/linux/percpu-refcount.h:168
Inline: True
Inline callers:
  - fs/aio.c:do_io_submit
  - fs/aio.c:lookup_ioctx
Direct callers:
  - fs/aio.c:SyS_io_setup
  - fs/aio.c:SyS_io_setup
```
```
In block/bio.c (ffffffff813f4aa3)
Location: include/linux/percpu-refcount.h:168
Inline: True
```
```
In block/blk-core.c (ffffffff813fe830)
Location: include/linux/percpu-refcount.h:168
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
```
```
In block/blk-mq.c (ffffffff81408db0)
Location: include/linux/percpu-refcount.h:168
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_map_request
```
```
In lib/percpu-refcount.c (ffffffff81446a9e)
Location: include/linux/percpu-refcount.h:168
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_reinit
```
**Symbols:**

```
ffffffff8122e9a6-ffffffff8122e9bf: percpu_ref_get_many.constprop.14 (STB_LOCAL)
ffffffff81284270-ffffffff81284289: percpu_ref_get_many.constprop.16 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/gup.c (ffffffff81075145)
Location: include/linux/percpu-refcount.h:168
Inline: True
Inline callers:
  - arch/x86/mm/gup.c:gup_huge_pmd
  - arch/x86/mm/gup.c:gup_pte_range
```
```
In kernel/cgroup.c (ffffffff811242eb)
Location: include/linux/percpu-refcount.h:168
Inline: True
Inline callers:
  - kernel/cgroup.c:kill_css
  - kernel/cgroup.c:init_and_link_css
  - kernel/cgroup.c:find_css_set
  - kernel/cgroup.c:cgroup_get
  - kernel/cgroup.c:cgroup_get_e_css
```
```
In kernel/cpuset.c (ffffffff8112db44)
Location: include/linux/percpu-refcount.h:168
Inline: True
Inline callers:
  - kernel/cpuset.c:cpuset_write_resmask
```
```
In kernel/memremap.c (ffffffff811add21)
Location: include/linux/percpu-refcount.h:168
Inline: True
Inline callers:
  - kernel/memremap.c:get_zone_device_page
```
```
In mm/backing-dev.c (ffffffff81240ef5)
Location: include/linux/percpu-refcount.h:168
Inline: True
Direct callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
```
```
In mm/gup.c (0)
Location: include/linux/percpu-refcount.h:168
Inline: True
```
```
In mm/huge_memory.c (0)
Location: include/linux/percpu-refcount.h:168
Inline: True
```
```
In mm/memcontrol.c (ffffffff8123677b)
Location: include/linux/percpu-refcount.h:168
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:task_in_mem_cgroup
```
```
In fs/fs-writeback.c (ffffffff81274fc7)
Location: include/linux/percpu-refcount.h:168
Inline: True
Inline callers:
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
```
```
In fs/aio.c (ffffffff812996ce)
Location: include/linux/percpu-refcount.h:168
Inline: True
Inline callers:
  - fs/aio.c:do_io_submit
  - fs/aio.c:lookup_ioctx
Direct callers:
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
```
```
In block/bio.c (ffffffff8140e493)
Location: include/linux/percpu-refcount.h:168
Inline: True
```
```
In block/blk-core.c (ffffffff81418215)
Location: include/linux/percpu-refcount.h:168
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
```
```
In block/blk-mq.c (ffffffff814221af)
Location: include/linux/percpu-refcount.h:168
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_map_request
```
```
In lib/percpu-refcount.c (ffffffff8146515f)
Location: include/linux/percpu-refcount.h:168
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_reinit
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
```
**Symbols:**

```
ffffffff81240ef5-ffffffff81240f0e: percpu_ref_get_many.constprop.16 (STB_LOCAL)
ffffffff81297f30-ffffffff81297f49: percpu_ref_get_many.constprop.18 (STB_LOCAL)
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
In kernel/cgroup/cgroup.c (ffffffff81128af4)
Location: include/linux/percpu-refcount.h:169
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:kill_css
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/cgroup.c:cgroup_get_live
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/cpuset.c (ffffffff8112ec08)
Location: include/linux/percpu-refcount.h:169
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In kernel/memremap.c (ffffffff811b4ec1)
Location: include/linux/percpu-refcount.h:169
Inline: True
Inline callers:
  - kernel/memremap.c:devm_memremap_pages
```
```
In mm/backing-dev.c (ffffffff811e1d54)
Location: include/linux/percpu-refcount.h:169
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
```
```
In mm/slab_common.c (ffffffff811e77ca)
Location: include/linux/percpu-refcount.h:169
Inline: True
Inline callers:
  - mm/slab_common.c:slab_deactivate_memcg_cache_rcu_sched
```
```
In mm/gup.c (ffffffff811f0cc1)
Location: include/linux/percpu-refcount.h:169
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages_fast
  - mm/gup.c:__gup_device_huge
```
```
In mm/huge_memory.c (0)
Location: include/linux/percpu-refcount.h:169
Inline: True
```
```
In mm/memcontrol.c (ffffffff8124222e)
Location: include/linux/percpu-refcount.h:169
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:task_in_mem_cgroup
```
```
In fs/fs-writeback.c (ffffffff81282530)
Location: include/linux/percpu-refcount.h:169
Inline: True
Inline callers:
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
```
```
In fs/aio.c (ffffffff812a73b7)
Location: include/linux/percpu-refcount.h:169
Inline: True
Inline callers:
  - fs/aio.c:do_io_submit
  - fs/aio.c:lookup_ioctx
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
```
```
In block/bio.c (ffffffff8141b20b)
Location: include/linux/percpu-refcount.h:169
Inline: True
```
```
In block/blk-core.c (ffffffff81425ffa)
Location: include/linux/percpu-refcount.h:169
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
```
```
In block/blk-mq.c (ffffffff8142f0f7)
Location: include/linux/percpu-refcount.h:169
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_request
```
```
In lib/percpu-refcount.c (ffffffff8146a288)
Location: include/linux/percpu-refcount.h:169
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_reinit
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
```
```
In drivers/md/md.c (ffffffff8173a9eb)
Location: include/linux/percpu-refcount.h:169
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
In kernel/kthread.c (ffffffff810ac94e)
Location: include/linux/percpu-refcount.h:170
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffffffff8113511c)
Location: include/linux/percpu-refcount.h:170
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:kill_css
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/cgroup.c:cgroup_get_live
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/cpuset.c (ffffffff8113baa8)
Location: include/linux/percpu-refcount.h:170
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In kernel/memremap.c (ffffffff811c91ff)
Location: include/linux/percpu-refcount.h:170
Inline: True
Inline callers:
  - kernel/memremap.c:devm_memremap_pages
```
```
In mm/backing-dev.c (ffffffff811f7dbb)
Location: include/linux/percpu-refcount.h:170
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
```
```
In mm/slab_common.c (ffffffff811fda0a)
Location: include/linux/percpu-refcount.h:170
Inline: True
Inline callers:
  - mm/slab_common.c:slab_deactivate_memcg_cache_rcu_sched
```
```
In mm/gup.c (ffffffff8120580f)
Location: include/linux/percpu-refcount.h:170
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:__gup_device_huge
```
```
In mm/huge_memory.c (0)
Location: include/linux/percpu-refcount.h:170
Inline: True
```
```
In mm/memcontrol.c (ffffffff81262022)
Location: include/linux/percpu-refcount.h:170
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:task_in_mem_cgroup
```
```
In fs/fs-writeback.c (ffffffff812a50a0)
Location: include/linux/percpu-refcount.h:170
Inline: True
Inline callers:
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
```
```
In fs/aio.c (ffffffff812ca74c)
Location: include/linux/percpu-refcount.h:170
Inline: True
Inline callers:
  - fs/aio.c:do_io_submit
  - fs/aio.c:lookup_ioctx
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
```
```
In block/bio.c (ffffffff81445e36)
Location: include/linux/percpu-refcount.h:170
Inline: True
```
```
In block/blk-core.c (ffffffff81451466)
Location: include/linux/percpu-refcount.h:170
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_queue_bio
```
```
In block/blk-mq.c (ffffffff8145a636)
Location: include/linux/percpu-refcount.h:170
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_request
```
```
In lib/percpu-refcount.c (ffffffff81496578)
Location: include/linux/percpu-refcount.h:170
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_reinit
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
```
```
In drivers/block/loop.c (ffffffff8166fc8f)
Location: include/linux/percpu-refcount.h:170
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_rq
```
```
In drivers/md/md.c (ffffffff817ad0cb)
Location: include/linux/percpu-refcount.h:170
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
In kernel/kthread.c (ffffffff810b396d)
Location: include/linux/percpu-refcount.h:176
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffffffff81143853)
Location: include/linux/percpu-refcount.h:176
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:kill_css
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/cgroup.c:cgroup_get_live
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/cpuset.c (ffffffff8114a8d2)
Location: include/linux/percpu-refcount.h:176
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In kernel/memremap.c (ffffffff811e9b41)
Location: include/linux/percpu-refcount.h:176
Inline: True
Inline callers:
  - kernel/memremap.c:devm_memremap_pages
```
```
In mm/backing-dev.c (ffffffff81219140)
Location: include/linux/percpu-refcount.h:176
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
```
```
In mm/slab_common.c (ffffffff8121ed61)
Location: include/linux/percpu-refcount.h:176
Inline: True
Inline callers:
  - mm/slab_common.c:slab_deactivate_memcg_cache_rcu_sched
```
```
In mm/memcontrol.c (ffffffff81286022)
Location: include/linux/percpu-refcount.h:176
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:task_in_mem_cgroup
```
```
In fs/fs-writeback.c (ffffffff812cbf5e)
Location: include/linux/percpu-refcount.h:176
Inline: True
Inline callers:
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:wbc_attach_and_unlock_inode
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
```
```
In fs/aio.c (ffffffff812f467d)
Location: include/linux/percpu-refcount.h:176
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
```
```
In block/bio.c (ffffffff81479ab5)
Location: include/linux/percpu-refcount.h:176
Inline: True
```
```
In block/blk-core.c (ffffffff81484717)
Location: include/linux/percpu-refcount.h:176
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:generic_make_request
  - block/blk-core.c:blk_queue_bio
```
```
In block/blk-mq.c (ffffffff8148eb96)
Location: include/linux/percpu-refcount.h:176
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_request
```
```
In lib/percpu-refcount.c (ffffffff814cb7d8)
Location: include/linux/percpu-refcount.h:176
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_reinit
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
```
```
In drivers/block/loop.c (ffffffff816ab980)
Location: include/linux/percpu-refcount.h:176
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_rq
```
```
In drivers/md/md.c (ffffffff817f550b)
Location: include/linux/percpu-refcount.h:176
Inline: True
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
In kernel/kthread.c (ffffffff810bcc6d)
Location: include/linux/percpu-refcount.h:177
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffffffff8114f373)
Location: include/linux/percpu-refcount.h:177
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:kill_css
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/cgroup.c:cgroup_get_live
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/cpuset.c (ffffffff81156dc7)
Location: include/linux/percpu-refcount.h:177
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In kernel/memremap.c (ffffffff811fa620)
Location: include/linux/percpu-refcount.h:177
Inline: True
Inline callers:
  - kernel/memremap.c:devm_memremap_pages
```
```
In mm/backing-dev.c (ffffffff8122bf93)
Location: include/linux/percpu-refcount.h:177
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
```
```
In mm/slab_common.c (ffffffff81231d41)
Location: include/linux/percpu-refcount.h:177
Inline: True
Inline callers:
  - mm/slab_common.c:slab_deactivate_memcg_cache_rcu_sched
```
```
In mm/memcontrol.c (ffffffff8129af82)
Location: include/linux/percpu-refcount.h:177
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_get_oom_group
  - mm/memcontrol.c:task_in_mem_cgroup
```
```
In fs/fs-writeback.c (ffffffff812e0e87)
Location: include/linux/percpu-refcount.h:177
Inline: True
Inline callers:
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:wbc_attach_and_unlock_inode
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
```
```
In fs/aio.c (ffffffff813094fc)
Location: include/linux/percpu-refcount.h:177
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
```
```
In block/blk-core.c (ffffffff8149f734)
Location: include/linux/percpu-refcount.h:177
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:generic_make_request
```
```
In block/blk-mq.c (ffffffff814a859f)
Location: include/linux/percpu-refcount.h:177
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/blk-cgroup.c (ffffffff814c2643)
Location: include/linux/percpu-refcount.h:177
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-throttle.c (ffffffff814c4657)
Location: include/linux/percpu-refcount.h:177
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_qnode_add_bio
```
```
In lib/percpu-refcount.c (ffffffff814e0514)
Location: include/linux/percpu-refcount.h:177
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_resurrect
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
```
```
In drivers/block/loop.c (ffffffff816cc721)
Location: include/linux/percpu-refcount.h:177
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_rq
```
```
In drivers/scsi/scsi_lib.c (ffffffff817146b3)
Location: include/linux/percpu-refcount.h:177
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/md/md.c (ffffffff818213eb)
Location: include/linux/percpu-refcount.h:177
Inline: True
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
In kernel/kthread.c (ffffffff810c2a59)
Location: include/linux/percpu-refcount.h:185
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffffffff8115b199)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:kill_css
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/cgroup.c:cgroup_get_live
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/cpuset.c (ffffffff81164704)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In kernel/bpf/cgroup.c (ffffffff811f8caf)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_offline
```
```
In mm/backing-dev.c (ffffffff8123bc23)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
```
```
In mm/slab_common.c (ffffffff812422f0)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_deactivate_kmem_caches
```
```
In mm/slub.c (ffffffff81293ee3)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (ffffffff812b6252)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_get_oom_group
```
```
In mm/memremap.c (ffffffff812c2cc2)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - mm/memremap.c:devm_memremap_pages
```
```
In fs/fs-writeback.c (ffffffff812ff623)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:wbc_attach_and_unlock_inode
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
```
```
In fs/aio.c (ffffffff8132b577)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
```
```
In block/blk-core.c (ffffffff814cd804)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
```
```
In block/blk-mq.c (ffffffff814d5fdf)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/blk-mq-sched.c (ffffffff814dd5bf)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
```
In block/blk-cgroup.c (ffffffff814f0c67)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-throttle.c (ffffffff814f2e18)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_qnode_add_bio
```
```
In lib/percpu-refcount.c (ffffffff8150c4b8)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_resurrect
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
```
```
In drivers/block/loop.c (ffffffff817081b6)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_rq
```
```
In drivers/scsi/scsi_lib.c (ffffffff81750009)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/md/md.c (ffffffff818637cb)
Location: include/linux/percpu-refcount.h:185
Inline: True
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
In kernel/kthread.c (ffffffff810c8fc9)
Location: include/linux/percpu-refcount.h:185
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffffffff81166e57)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:kill_css
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/cgroup.c:cgroup_get_live
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/cpuset.c (ffffffff81170553)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
```
In kernel/bpf/cgroup.c (ffffffff81205d8a)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_offline
```
```
In mm/backing-dev.c (ffffffff8124a0d2)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
```
```
In mm/slab_common.c (ffffffff81250780)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_deactivate_kmem_caches
```
```
In mm/slub.c (ffffffff812a3c53)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (ffffffff812c8101)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_get_oom_group
```
```
In mm/memremap.c (ffffffff812d4b75)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - mm/memremap.c:memremap_pages
```
```
In fs/fs-writeback.c (ffffffff8131453f)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:wbc_attach_and_unlock_inode
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
```
```
In fs/aio.c (ffffffff8133e3c7)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
```
```
In block/blk-core.c (ffffffff814e6af4)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
```
```
In block/blk-mq.c (ffffffff814ef313)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/blk-mq-sched.c (ffffffff814f6a4f)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
```
In block/blk-cgroup.c (ffffffff8150a243)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-throttle.c (ffffffff8150c3b8)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_qnode_add_bio
```
```
In lib/percpu-refcount.c (ffffffff8152a308)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_resurrect
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
```
```
In drivers/block/loop.c (ffffffff8172c406)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_rq
```
```
In drivers/scsi/scsi_lib.c (ffffffff817741f9)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/md/md.c (ffffffff8189551b)
Location: include/linux/percpu-refcount.h:185
Inline: True
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
In kernel/kthread.c (ffffffff810d09b8)
Location: include/linux/percpu-refcount.h:185
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffffffff81178604)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_clone
  - kernel/cgroup/cgroup.c:cgroup_sk_clone
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_get_tree
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/cpuset.c (ffffffff811818a3)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:rebuild_root_domains
```
```
In kernel/bpf/cgroup.c (ffffffff8122d50a)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_offline
```
```
In mm/backing-dev.c (ffffffff81278284)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_create
  - mm/backing-dev.c:cgwb_create
```
```
In mm/slab_common.c (ffffffff8127ee26)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_deactivate_kmem_caches
```
```
In mm/hugetlb.c (ffffffff812c5825)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - mm/hugetlb.c:region_del
```
```
In mm/slub.c (ffffffff812d9792)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (ffffffff812fd95a)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_get_oom_group
```
```
In mm/memremap.c (ffffffff8130a6be)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - mm/memremap.c:memremap_pages
```
```
In fs/fs-writeback.c (ffffffff8134e054)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
```
```
In fs/aio.c (ffffffff81378237)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
```
```
In fs/io_uring.c (ffffffff813807b2)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - fs/io_uring.c:__io_sqe_files_update
  - fs/io_uring.c:io_sqe_files_register
  - fs/io_uring.c:io_file_get
  - fs/io_uring.c:__io_async_wake
```
```
In block/blk-mq-sched.c (ffffffff815574ef)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
```
In block/blk-cgroup.c (ffffffff8156b453)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-throttle.c (ffffffff8156da31)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_add_bio_tg
```
```
In lib/percpu-refcount.c (ffffffff8158da28)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_resurrect
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
```
```
In drivers/block/loop.c (ffffffff817e7bc6)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_rq
```
```
In drivers/scsi/scsi_lib.c (ffffffff81836b1b)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/md/md.c (ffffffff819629bb)
Location: include/linux/percpu-refcount.h:185
Inline: True
```
```
In drivers/md/dm.c (ffffffff819799c7)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_make_request
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
In kernel/kthread.c (ffffffff810cb598)
Location: include/linux/percpu-refcount.h:198
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffffffff8117539e)
Location: include/linux/percpu-refcount.h:198
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_clone
  - kernel/cgroup/cgroup.c:cgroup_sk_clone
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/cgroup.c:cgroup_get_live
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/cpuset.c (ffffffff8117e7a8)
Location: include/linux/percpu-refcount.h:198
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:rebuild_root_domains
```
```
In kernel/bpf/trampoline.c (ffffffff81222b30)
Location: include/linux/percpu-refcount.h:198
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:__bpf_tramp_enter
```
```
In kernel/bpf/cgroup.c (ffffffff81235a1a)
Location: include/linux/percpu-refcount.h:198
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_offline
```
```
In mm/backing-dev.c (ffffffff81282a1a)
Location: include/linux/percpu-refcount.h:198
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_create
  - mm/backing-dev.c:cgwb_create
```
```
In mm/hugetlb.c (ffffffff812d1475)
Location: include/linux/percpu-refcount.h:198
Inline: True
Inline callers:
  - mm/hugetlb.c:region_del
```
```
In mm/slub.c (ffffffff812e4233)
Location: include/linux/percpu-refcount.h:198
Inline: True
Inline callers:
  - mm/slub.c:memcg_slab_post_alloc_hook
```
```
In mm/memcontrol.c (ffffffff81309d7b)
Location: include/linux/percpu-refcount.h:198
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:mem_cgroup_charge
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:split_page_memcg
  - mm/memcontrol.c:refill_obj_stock
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:refill_stock
  - mm/memcontrol.c:mem_cgroup_get_oom_group
  - mm/memcontrol.c:memcg_reparent_objcgs
  - mm/memcontrol.c:memcg_reparent_objcgs
```
```
In mm/memremap.c (ffffffff813160c0)
Location: include/linux/percpu-refcount.h:198
Inline: True
Inline callers:
  - mm/memremap.c:pagemap_range
```
```
In fs/fs-writeback.c (ffffffff8135aefc)
Location: include/linux/percpu-refcount.h:198
Inline: True
Inline callers:
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
```
```
In fs/aio.c (ffffffff81385f37)
Location: include/linux/percpu-refcount.h:198
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
```
```
In fs/io_uring.c (ffffffff8138f06d)
Location: include/linux/percpu-refcount.h:198
Inline: True
Inline callers:
  - fs/io_uring.c:__io_sqe_files_update
  - fs/io_uring.c:io_sqe_files_register
  - fs/io_uring.c:io_sqe_files_unregister
  - fs/io_uring.c:io_file_get
  - fs/io_uring.c:io_wq_submit_work
  - fs/io_uring.c:__io_async_wake
  - fs/io_uring.c:io_async_buf_func
  - fs/io_uring.c:io_put_req_deferred_cb
  - fs/io_uring.c:io_req_free_batch
  - fs/io_uring.c:__io_req_task_cancel
  - fs/io_uring.c:io_fail_links
  - fs/io_uring.c:io_commit_cqring
```
```
In block/blk-mq-sched.c (ffffffff81573b04)
Location: include/linux/percpu-refcount.h:198
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
```
In block/blk-cgroup.c (ffffffff81585a69)
Location: include/linux/percpu-refcount.h:198
Inline: True
Inline callers:
  - block/blk-cgroup.c:bio_clone_blkg_association
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-throttle.c (ffffffff81587f4d)
Location: include/linux/percpu-refcount.h:198
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_add_bio_tg
```
```
In lib/percpu-refcount.c (ffffffff815aa6a5)
Location: include/linux/percpu-refcount.h:198
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_resurrect
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
```
```
In drivers/block/loop.c (ffffffff817fcaa6)
Location: include/linux/percpu-refcount.h:198
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_rq
```
```
In drivers/scsi/scsi_lib.c (ffffffff818475de)
Location: include/linux/percpu-refcount.h:198
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/md/md.c (ffffffff819693fb)
Location: include/linux/percpu-refcount.h:198
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
In kernel/kthread.c (ffffffff810cced9)
Location: include/linux/percpu-refcount.h:198
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffffffff81175f20)
Location: include/linux/percpu-refcount.h:198
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_clone
  - kernel/cgroup/cgroup.c:cgroup_sk_clone
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/cgroup.c:cgroup_get_live
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/cpuset.c (ffffffff8117e7ba)
Location: include/linux/percpu-refcount.h:198
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
```
In kernel/bpf/trampoline.c (ffffffff81227370)
Location: include/linux/percpu-refcount.h:198
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:__bpf_tramp_enter
```
```
In kernel/bpf/cgroup.c (ffffffff81239c6a)
Location: include/linux/percpu-refcount.h:198
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_offline
```
```
In mm/backing-dev.c (ffffffff81287b3f)
Location: include/linux/percpu-refcount.h:198
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_create
  - mm/backing-dev.c:cgwb_create
```
```
In mm/hugetlb.c (ffffffff812d7945)
Location: include/linux/percpu-refcount.h:198
Inline: True
Inline callers:
  - mm/hugetlb.c:region_del
```
```
In mm/slub.c (ffffffff812ec490)
Location: include/linux/percpu-refcount.h:198
Inline: True
Inline callers:
  - mm/slub.c:memcg_slab_post_alloc_hook
```
```
In mm/memcontrol.c (ffffffff813105e7)
Location: include/linux/percpu-refcount.h:198
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:uncharge_page
  - mm/memcontrol.c:__mem_cgroup_charge
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:split_page_memcg
  - mm/memcontrol.c:split_page_memcg
  - mm/memcontrol.c:refill_obj_stock
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:refill_stock
  - mm/memcontrol.c:mem_cgroup_get_oom_group
```
```
In mm/memremap.c (ffffffff8131c2f5)
Location: include/linux/percpu-refcount.h:198
Inline: True
Inline callers:
  - mm/memremap.c:pagemap_range
```
```
In fs/fs-writeback.c (ffffffff81361afc)
Location: include/linux/percpu-refcount.h:198
Inline: True
Inline callers:
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
```
```
In fs/aio.c (ffffffff8138d087)
Location: include/linux/percpu-refcount.h:198
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
```
```
In fs/io_uring.c (ffffffff813933aa)
Location: include/linux/percpu-refcount.h:198
Inline: True
Inline callers:
  - fs/io_uring.c:io_file_get
  - fs/io_uring.c:io_prep_rw
  - fs/io_uring.c:tctx_task_work
```
```
In block/blk-mq-sched.c (ffffffff8157bb94)
Location: include/linux/percpu-refcount.h:198
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
```
In block/blk-cgroup.c (ffffffff8158c439)
Location: include/linux/percpu-refcount.h:198
Inline: True
Inline callers:
  - block/blk-cgroup.c:bio_clone_blkg_association
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-throttle.c (ffffffff8158ed9d)
Location: include/linux/percpu-refcount.h:198
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_add_bio_tg
```
```
In lib/percpu-refcount.c (ffffffff815b52c5)
Location: include/linux/percpu-refcount.h:198
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_resurrect
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
```
```
In drivers/block/loop.c (ffffffff817e1676)
Location: include/linux/percpu-refcount.h:198
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_rq
```
```
In drivers/scsi/scsi_lib.c (ffffffff8182a79e)
Location: include/linux/percpu-refcount.h:198
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/md/md.c (ffffffff8194d38b)
Location: include/linux/percpu-refcount.h:198
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
In kernel/kthread.c (ffffffff810df93d)
Location: include/linux/percpu-refcount.h:198
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffffffff8119d4ed)
Location: include/linux/percpu-refcount.h:198
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_clone
  - kernel/cgroup/cgroup.c:cgroup_sk_clone
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_get_tree
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/cpuset.c (ffffffff811a64da)
Location: include/linux/percpu-refcount.h:198
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
```
In kernel/bpf/trampoline.c (ffffffff8125f470)
Location: include/linux/percpu-refcount.h:198
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:__bpf_tramp_enter
```
```
In kernel/bpf/cgroup.c (ffffffff812743d1)
Location: include/linux/percpu-refcount.h:198
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_offline
```
```
In mm/backing-dev.c (ffffffff812c72e1)
Location: include/linux/percpu-refcount.h:198
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_create
  - mm/backing-dev.c:cgwb_create
```
```
In mm/hugetlb.c (ffffffff8131c937)
Location: include/linux/percpu-refcount.h:198
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_vm_op_open
  - mm/hugetlb.c:region_del
  - mm/hugetlb.c:add_reservation_in_range
  - mm/hugetlb.c:add_reservation_in_range
```
```
In mm/slub.c (ffffffff813343f1)
Location: include/linux/percpu-refcount.h:198
Inline: True
Inline callers:
  - mm/slub.c:memcg_slab_post_alloc_hook
```
```
In mm/memcontrol.c (ffffffff8135b8e6)
Location: include/linux/percpu-refcount.h:198
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:uncharge_page
  - mm/memcontrol.c:charge_memcg
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:split_page_memcg
  - mm/memcontrol.c:split_page_memcg
  - mm/memcontrol.c:refill_obj_stock
  - mm/memcontrol.c:mod_objcg_state
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:refill_stock
  - mm/memcontrol.c:mem_cgroup_get_oom_group
  - mm/memcontrol.c:get_mem_cgroup_from_mm
```
```
In mm/memremap.c (ffffffff813695e1)
Location: include/linux/percpu-refcount.h:198
Inline: True
Inline callers:
  - mm/memremap.c:pagemap_range
```
```
In fs/fs-writeback.c (ffffffff813b015c)
Location: include/linux/percpu-refcount.h:198
Inline: True
Inline callers:
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:inode_do_switch_wbs
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
```
```
In fs/aio.c (ffffffff813da7e7)
Location: include/linux/percpu-refcount.h:198
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
```
```
In fs/io_uring.c (ffffffff813e156d)
Location: include/linux/percpu-refcount.h:198
Inline: True
Inline callers:
  - fs/io_uring.c:io_init_req
  - fs/io_uring.c:__io_splice_prep
  - fs/io_uring.c:io_prep_rw
  - fs/io_uring.c:tctx_task_work
  - fs/io_uring.c:io_fallback_req_func
```
```
In block/blk-mq-sched.c (ffffffff815e0f74)
Location: include/linux/percpu-refcount.h:198
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
```
In block/blk-cgroup.c (ffffffff815f1a69)
Location: include/linux/percpu-refcount.h:198
Inline: True
Inline callers:
  - block/blk-cgroup.c:bio_clone_blkg_association
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-throttle.c (ffffffff815f4dfd)
Location: include/linux/percpu-refcount.h:198
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_add_bio_tg
```
```
In lib/percpu-refcount.c (ffffffff8161b665)
Location: include/linux/percpu-refcount.h:198
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_resurrect
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
```
```
In drivers/block/loop.c (ffffffff8186fdef)
Location: include/linux/percpu-refcount.h:198
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
```
```
In drivers/scsi/scsi_lib.c (ffffffff818b61eb)
Location: include/linux/percpu-refcount.h:198
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/md/md.c (ffffffff819f279b)
Location: include/linux/percpu-refcount.h:198
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void percpu_ref_get_many(struct percpu_ref *ref, long unsigned int nr);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810f9cb6)
Location: include/linux/percpu-refcount.h:198
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffffffff811cd81a)
Location: include/linux/percpu-refcount.h:198
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_clone
  - kernel/cgroup/cgroup.c:cgroup_sk_clone
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_get_tree
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/cpuset.c (ffffffff811d792f)
Location: include/linux/percpu-refcount.h:198
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
```
In kernel/bpf/trampoline.c (ffffffff812a9ba8)
Location: include/linux/percpu-refcount.h:198
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:__bpf_tramp_enter
```
```
In kernel/bpf/cgroup.c (ffffffff812c4a80)
Location: include/linux/percpu-refcount.h:198
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_offline
```
```
In mm/backing-dev.c (ffffffff81323b1a)
Location: include/linux/percpu-refcount.h:198
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_create
  - mm/backing-dev.c:cgwb_create
```
```
In mm/hugetlb.c (ffffffff81388b79)
Location: include/linux/percpu-refcount.h:198
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_vm_op_open
  - mm/hugetlb.c:region_del
  - mm/hugetlb.c:add_reservation_in_range
  - mm/hugetlb.c:add_reservation_in_range
```
```
In mm/slub.c (ffffffff813a5f23)
Location: include/linux/percpu-refcount.h:198
Inline: True
Inline callers:
  - mm/slub.c:memcg_slab_post_alloc_hook
```
```
In mm/memcontrol.c (ffffffff813d5183)
Location: include/linux/percpu-refcount.h:198
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:uncharge_folio
  - mm/memcontrol.c:charge_memcg
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:split_page_memcg
  - mm/memcontrol.c:split_page_memcg
  - mm/memcontrol.c:refill_obj_stock
  - mm/memcontrol.c:mod_objcg_state
  - mm/memcontrol.c:get_obj_cgroup_from_page
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:__refill_stock
  - mm/memcontrol.c:mem_cgroup_get_oom_group
  - mm/memcontrol.c:get_mem_cgroup_from_mm
```
```
In mm/memremap.c (ffffffff813e7712)
Location: include/linux/percpu-refcount.h:198
Inline: True
Inline callers:
  - mm/memremap.c:pagemap_range
```
```
In fs/fs-writeback.c (ffffffff81434d67)
Location: include/linux/percpu-refcount.h:198
Inline: True
Inline callers:
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:wbc_attach_and_unlock_inode
  - fs/fs-writeback.c:inode_do_switch_wbs
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
```
```
In fs/aio.c (ffffffff814651d6)
Location: include/linux/percpu-refcount.h:198
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
```
```
In block/blk-mq.c (ffffffff816839da)
Location: include/linux/percpu-refcount.h:198
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_alloc_requests_batch
```
```
In block/blk-mq-sched.c (ffffffff8168fb39)
Location: include/linux/percpu-refcount.h:198
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
```
In block/blk-cgroup.c (ffffffff816a3888)
Location: include/linux/percpu-refcount.h:198
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-throttle.c (ffffffff816a69fe)
Location: include/linux/percpu-refcount.h:198
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_add_bio_tg
```
```
In io_uring/io_uring.c (ffffffff816d72b5)
Location: include/linux/percpu-refcount.h:198
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_wq_submit_work
  - io_uring/io_uring.c:io_issue_sqe
  - io_uring/io_uring.c:io_async_cancel
  - io_uring/io_uring.c:io_splice
  - io_uring/io_uring.c:io_tee
  - io_uring/io_uring.c:io_prep_rw
  - io_uring/io_uring.c:tctx_task_work
  - io_uring/io_uring.c:handle_prev_tw_list
Direct callers:
  - io_uring/io_uring.c:io_submit_sqes
  - io_uring/io_uring.c:io_submit_sqes
  - io_uring/io_uring.c:io_fallback_req_func
```
```
In lib/percpu-refcount.c (ffffffff816e8e71)
Location: include/linux/percpu-refcount.h:198
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_resurrect
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
```
```
In drivers/block/loop.c (ffffffff819b67b4)
Location: include/linux/percpu-refcount.h:198
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
```
```
In drivers/scsi/scsi_lib.c (ffffffff81a0173e)
Location: include/linux/percpu-refcount.h:198
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/md/md.c (ffffffff81b5b45b)
Location: include/linux/percpu-refcount.h:198
Inline: True
Inline callers:
  - drivers/md/md.c:md_write_start
```
**Symbols:**

```
ffffffff816c71f0-ffffffff816c723d: percpu_ref_get_many (STB_LOCAL)
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
In kernel/kthread.c (ffffffff8111c9f6)
Location: include/linux/percpu-refcount.h:198
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffffffff81210eba)
Location: include/linux/percpu-refcount.h:198
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_clone
  - kernel/cgroup/cgroup.c:cgroup_sk_clone
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:pressure_write
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_get_tree
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/cpuset.c (ffffffff8121c5fa)
Location: include/linux/percpu-refcount.h:198
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
```
In kernel/bpf/helpers.c (ffffffff812f44b8)
Location: include/linux/percpu-refcount.h:198
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_cgroup_ancestor
  - kernel/bpf/helpers.c:bpf_cgroup_acquire
```
```
In kernel/bpf/trampoline.c (ffffffff81308b48)
Location: include/linux/percpu-refcount.h:198
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:__bpf_tramp_enter
```
```
In kernel/bpf/cgroup_iter.c (ffffffff81325526)
Location: include/linux/percpu-refcount.h:198
Inline: True
Inline callers:
  - kernel/bpf/cgroup_iter.c:cgroup_iter_seq_init
```
```
In kernel/bpf/cgroup.c (ffffffff81329f63)
Location: include/linux/percpu-refcount.h:198
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_offline
```
```
In mm/backing-dev.c (ffffffff81398388)
Location: include/linux/percpu-refcount.h:198
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_create
  - mm/backing-dev.c:cgwb_create
```
```
In mm/hugetlb.c (ffffffff81406c01)
Location: include/linux/percpu-refcount.h:198
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_vm_op_open
  - mm/hugetlb.c:region_del
  - mm/hugetlb.c:add_reservation_in_range
  - mm/hugetlb.c:add_reservation_in_range
```
```
In mm/slub.c (ffffffff814270e3)
Location: include/linux/percpu-refcount.h:198
Inline: True
Inline callers:
  - mm/slub.c:memcg_slab_post_alloc_hook
```
```
In mm/memcontrol.c (ffffffff8145abe4)
Location: include/linux/percpu-refcount.h:198
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:uncharge_folio
  - mm/memcontrol.c:charge_memcg
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:split_page_memcg
  - mm/memcontrol.c:split_page_memcg
  - mm/memcontrol.c:refill_obj_stock
  - mm/memcontrol.c:mod_objcg_state
  - mm/memcontrol.c:get_obj_cgroup_from_page
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:__refill_stock
  - mm/memcontrol.c:mem_cgroup_get_oom_group
  - mm/memcontrol.c:get_mem_cgroup_from_mm
```
```
In mm/memremap.c (ffffffff8146f3a1)
Location: include/linux/percpu-refcount.h:198
Inline: True
Inline callers:
  - mm/memremap.c:pagemap_range
```
```
In fs/fs-writeback.c (ffffffff814c2d67)
Location: include/linux/percpu-refcount.h:198
Inline: True
Inline callers:
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:wbc_attach_and_unlock_inode
  - fs/fs-writeback.c:inode_do_switch_wbs
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
```
```
In fs/aio.c (ffffffff814f5216)
Location: include/linux/percpu-refcount.h:198
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
```
```
In block/blk-mq.c (ffffffff8174135a)
Location: include/linux/percpu-refcount.h:198
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_alloc_requests_batch
```
```
In block/blk-mq-sched.c (ffffffff8174e6a9)
Location: include/linux/percpu-refcount.h:198
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
```
In block/blk-cgroup.c (ffffffff81763c04)
Location: include/linux/percpu-refcount.h:198
Inline: True
Inline callers:
  - block/blk-cgroup.c:blk_cgroup_bio_start
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-throttle.c (ffffffff81765924)
Location: include/linux/percpu-refcount.h:198
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_qnode_add_bio
```
```
In io_uring/io_uring.c (ffffffff8178de40)
Location: include/linux/percpu-refcount.h:198
Inline: True
Inline callers:
  - io_uring/io_uring.c:__io_req_task_work_add
  - io_uring/io_uring.c:handle_tw_list
  - io_uring/io_uring.c:__io_alloc_req_refill
  - io_uring/io_uring.c:io_fallback_req_func
```
```
In io_uring/uring_cmd.c (0)
Location: include/linux/percpu-refcount.h:198
Inline: False
```
```
In io_uring/net.c (0)
Location: include/linux/percpu-refcount.h:198
Inline: False
```
```
In io_uring/rsrc.c (ffffffff817a0c05)
Location: include/linux/percpu-refcount.h:198
Inline: True
Inline callers:
  - io_uring/rsrc.c:io_rsrc_refs_refill
```
```
In io_uring/rw.c (0)
Location: include/linux/percpu-refcount.h:198
Inline: False
```
```
In lib/percpu-refcount.c (ffffffff817d8f31)
Location: include/linux/percpu-refcount.h:198
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_resurrect
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
```
```
In drivers/pci/p2pdma.c (ffffffff8191be8e)
Location: include/linux/percpu-refcount.h:198
Inline: True
Inline callers:
  - drivers/pci/p2pdma.c:p2pmem_alloc_mmap
```
```
In drivers/block/loop.c (ffffffff81b2b9c4)
Location: include/linux/percpu-refcount.h:198
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
```
```
In drivers/scsi/scsi_lib.c (ffffffff81b7fd8e)
Location: include/linux/percpu-refcount.h:198
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/md/md.c (ffffffff81cf4e2b)
Location: include/linux/percpu-refcount.h:198
Inline: True
Inline callers:
  - drivers/md/md.c:md_write_start
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
In kernel/kthread.c (ffffffff81129b86)
Location: include/linux/percpu-refcount.h:198
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffffffff812268aa)
Location: include/linux/percpu-refcount.h:198
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_clone
  - kernel/cgroup/cgroup.c:cgroup_sk_clone
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:pressure_write
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_get_tree
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/cpuset.c (ffffffff812329ea)
Location: include/linux/percpu-refcount.h:198
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
```
In kernel/bpf/trampoline.c (ffffffff81337a68)
Location: include/linux/percpu-refcount.h:198
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:__bpf_tramp_enter
```
```
In kernel/bpf/cgroup_iter.c (ffffffff81355761)
Location: include/linux/percpu-refcount.h:198
Inline: True
Inline callers:
  - kernel/bpf/cgroup_iter.c:cgroup_iter_seq_init
```
```
In kernel/bpf/cgroup.c (ffffffff8135a0a3)
Location: include/linux/percpu-refcount.h:198
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_offline
```
```
In mm/backing-dev.c (ffffffff813cb308)
Location: include/linux/percpu-refcount.h:198
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_create
  - mm/backing-dev.c:cgwb_create
```
```
In mm/hugetlb.c (ffffffff8143a264)
Location: include/linux/percpu-refcount.h:198
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_vm_op_open
  - mm/hugetlb.c:region_del
  - mm/hugetlb.c:add_reservation_in_range
  - mm/hugetlb.c:add_reservation_in_range
```
```
In mm/slub.c (ffffffff8145c083)
Location: include/linux/percpu-refcount.h:198
Inline: True
Inline callers:
  - mm/slub.c:memcg_slab_post_alloc_hook
```
```
In mm/memcontrol.c (ffffffff81490844)
Location: include/linux/percpu-refcount.h:198
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:uncharge_folio
  - mm/memcontrol.c:charge_memcg
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:split_page_memcg
  - mm/memcontrol.c:split_page_memcg
  - mm/memcontrol.c:refill_obj_stock
  - mm/memcontrol.c:mod_objcg_state
  - mm/memcontrol.c:get_obj_cgroup_from_page
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:__refill_stock
  - mm/memcontrol.c:mem_cgroup_get_oom_group
  - mm/memcontrol.c:get_mem_cgroup_from_mm
```
```
In mm/memremap.c (ffffffff814a3b85)
Location: include/linux/percpu-refcount.h:198
Inline: True
Inline callers:
  - mm/memremap.c:pagemap_range
```
```
In fs/fs-writeback.c (ffffffff814f6343)
Location: include/linux/percpu-refcount.h:198
Inline: True
Inline callers:
  - fs/fs-writeback.c:wbc_attach_and_unlock_inode
  - fs/fs-writeback.c:inode_do_switch_wbs
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
```
```
In fs/aio.c (ffffffff8152bfe6)
Location: include/linux/percpu-refcount.h:198
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
```
```
In block/blk-mq.c (ffffffff81783023)
Location: include/linux/percpu-refcount.h:198
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_plug_list
  - block/blk-mq.c:__blk_mq_alloc_requests
```
```
In block/blk-cgroup.c (ffffffff817a1f8e)
Location: include/linux/percpu-refcount.h:198
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_activate_policy
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-throttle.c (ffffffff817a49e4)
Location: include/linux/percpu-refcount.h:198
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_qnode_add_bio
```
```
In io_uring/io_uring.c (ffffffff817c90af)
Location: include/linux/percpu-refcount.h:198
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_activate_pollwq
  - io_uring/io_uring.c:tctx_task_work
  - io_uring/io_uring.c:io_fallback_tw
  - io_uring/io_uring.c:__io_alloc_req_refill
```
```
In lib/percpu-refcount.c (ffffffff81818141)
Location: include/linux/percpu-refcount.h:198
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_resurrect
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
```
```
In drivers/pci/p2pdma.c (ffffffff8195f4a1)
Location: include/linux/percpu-refcount.h:198
Inline: True
Inline callers:
  - drivers/pci/p2pdma.c:p2pmem_alloc_mmap
```
```
In drivers/block/loop.c (ffffffff81b7bcc4)
Location: include/linux/percpu-refcount.h:198
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
```
```
In drivers/scsi/scsi_lib.c (ffffffff81bd3de1)
Location: include/linux/percpu-refcount.h:198
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/md/md.c (ffffffff81d5e864)
Location: include/linux/percpu-refcount.h:198
Inline: True
Inline callers:
  - drivers/md/md.c:md_account_bio
  - drivers/md/md.c:md_write_start
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
In kernel/kthread.c (ffffffff811341c6)
Location: include/linux/percpu-refcount.h:198
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffffffff8123e53a)
Location: include/linux/percpu-refcount.h:198
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_clone
  - kernel/cgroup/cgroup.c:cgroup_sk_clone
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:pressure_write
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_get_tree
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/cpuset.c (ffffffff8124c16a)
Location: include/linux/percpu-refcount.h:198
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
```
In kernel/bpf/syscall.c (ffffffff8131061f)
Location: include/linux/percpu-refcount.h:198
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:map_create
```
```
In kernel/bpf/trampoline.c (ffffffff8135d8a8)
Location: include/linux/percpu-refcount.h:198
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:__bpf_tramp_enter
```
```
In kernel/bpf/memalloc.c (ffffffff81372d35)
Location: include/linux/percpu-refcount.h:198
Inline: True
Inline callers:
  - kernel/bpf/memalloc.c:bpf_mem_alloc_init
  - kernel/bpf/memalloc.c:bpf_mem_alloc_init
```
```
In kernel/bpf/cgroup_iter.c (ffffffff8137e0e1)
Location: include/linux/percpu-refcount.h:198
Inline: True
Inline callers:
  - kernel/bpf/cgroup_iter.c:cgroup_iter_seq_init
```
```
In kernel/bpf/cgroup.c (ffffffff81382c53)
Location: include/linux/percpu-refcount.h:198
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_offline
```
```
In mm/backing-dev.c (ffffffff813f5b10)
Location: include/linux/percpu-refcount.h:198
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_create
  - mm/backing-dev.c:cgwb_create
```
```
In mm/percpu.c (ffffffff813fa0d8)
Location: include/linux/percpu-refcount.h:198
Inline: True
```
```
In mm/slub.c (ffffffff81455cbd)
Location: include/linux/percpu-refcount.h:198
Inline: True
Inline callers:
  - mm/slub.c:__memcg_slab_post_alloc_hook
```
```
In mm/hugetlb.c (ffffffff81474874)
Location: include/linux/percpu-refcount.h:198
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_vm_op_open
  - mm/hugetlb.c:region_del
  - mm/hugetlb.c:add_reservation_in_range
  - mm/hugetlb.c:add_reservation_in_range
```
```
In mm/memcontrol.c (ffffffff814c0121)
Location: include/linux/percpu-refcount.h:198
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_replace_folio
  - mm/memcontrol.c:uncharge_folio
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:split_page_memcg
  - mm/memcontrol.c:split_page_memcg
  - mm/memcontrol.c:refill_obj_stock
  - mm/memcontrol.c:mod_objcg_state
  - mm/memcontrol.c:__memcg_kmem_charge_page
  - mm/memcontrol.c:get_obj_cgroup_from_folio
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:__refill_stock
  - mm/memcontrol.c:mem_cgroup_get_oom_group
  - mm/memcontrol.c:get_mem_cgroup_from_mm
```
```
In mm/memremap.c (ffffffff814d4a25)
Location: include/linux/percpu-refcount.h:198
Inline: True
Inline callers:
  - mm/memremap.c:pagemap_range
```
```
In fs/fs-writeback.c (ffffffff8152aa83)
Location: include/linux/percpu-refcount.h:198
Inline: True
Inline callers:
  - fs/fs-writeback.c:wbc_attach_and_unlock_inode
  - fs/fs-writeback.c:inode_do_switch_wbs
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
```
```
In fs/aio.c (ffffffff81560ec6)
Location: include/linux/percpu-refcount.h:198
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
```
```
In block/blk-mq.c (ffffffff817c6ca2)
Location: include/linux/percpu-refcount.h:198
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_submit_bio
  - block/blk-mq.c:blk_mq_dispatch_plug_list
  - block/blk-mq.c:__blk_mq_alloc_requests_batch
```
```
In block/blk-cgroup.c (ffffffff817e5adb)
Location: include/linux/percpu-refcount.h:198
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_activate_policy
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-throttle.c (ffffffff817e85b4)
Location: include/linux/percpu-refcount.h:198
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_qnode_add_bio
```
```
In io_uring/io_uring.c (ffffffff81816eaf)
Location: include/linux/percpu-refcount.h:198
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_activate_pollwq
  - io_uring/io_uring.c:tctx_task_work
  - io_uring/io_uring.c:io_fallback_tw
  - io_uring/io_uring.c:__io_alloc_req_refill
  - io_uring/io_uring.c:io_fallback_req_func
```
```
In lib/percpu-refcount.c (ffffffff8185d441)
Location: include/linux/percpu-refcount.h:198
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_resurrect
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
```
```
In drivers/pci/p2pdma.c (ffffffff819a8b01)
Location: include/linux/percpu-refcount.h:198
Inline: True
Inline callers:
  - drivers/pci/p2pdma.c:p2pmem_alloc_mmap
```
```
In drivers/block/loop.c (ffffffff81bcfcf3)
Location: include/linux/percpu-refcount.h:198
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
```
```
In drivers/scsi/scsi_lib.c (ffffffff81c28a5e)
Location: include/linux/percpu-refcount.h:198
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/md/md.c (ffffffff81e15a02)
Location: include/linux/percpu-refcount.h:198
Inline: True
Inline callers:
  - drivers/md/md.c:md_account_bio
  - drivers/md/md.c:md_write_start
  - drivers/md/md.c:md_flush_request
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void percpu_ref_get_many(struct percpu_ref *ref, long unsigned int nr);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/kthread.c (ffff8000101288c4)
Location: include/linux/percpu-refcount.h:185
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffff8000101d2840)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:find_css_set
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:kill_css
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cgroup_get_live
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/cpuset.c (ffff8000101e33e4)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
```
In kernel/bpf/cgroup.c (ffff80001028f03c)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_offline
```
```
In mm/backing-dev.c (ffff8000102df8ac)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
```
```
In mm/slab_common.c (ffff8000102e786c)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_deactivate_kmem_caches
```
```
In mm/slub.c (ffff800010345900)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (ffff80001036632c)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:mem_cgroup_get_oom_group
Direct callers:
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
```
```
In fs/fs-writeback.c (ffff8000103ca354)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
```
```
In fs/aio.c (ffff8000103fd944)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
```
```
In block/blk-core.c (ffff8000105e4354)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
```
```
In block/blk-mq.c (ffff8000105ef7c4)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/blk-mq-sched.c (ffff8000105f70f4)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
```
In block/blk-cgroup.c (ffff80001060d8f0)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-throttle.c (ffff80001061061c)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_qnode_add_bio
```
```
In lib/percpu-refcount.c (ffff800010635644)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_resurrect
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
```
```
In drivers/block/loop.c (ffff800010924f14)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_rq
```
```
In drivers/scsi/scsi_lib.c (ffff800010978258)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/md/md.c (ffff800010aea9f8)
Location: include/linux/percpu-refcount.h:185
Inline: True
```
**Symbols:**

```
ffff8000101d0a30-ffff8000101d0a7c: percpu_ref_get_many.constprop.0 (STB_LOCAL)
ffff800010364968-ffff8000103649b4: percpu_ref_get_many (STB_LOCAL)
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
In kernel/kthread.c (c037acdc)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_associate_blkcg
```
```
In kernel/cgroup/cgroup.c (c041ba48)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:kill_css
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/cgroup.c:cgroup_get_live
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/cpuset.c (c0424164)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In kernel/bpf/cgroup.c (c04be864)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_offline
```
```
In mm/backing-dev.c (c0504618)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
```
```
In mm/slab_common.c (c050b914)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_deactivate_kmem_caches
```
```
In mm/slub.c (c05496c8)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (c055c600)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_get_oom_group
```
```
In fs/fs-writeback.c (c05a6994)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
```
```
In fs/aio.c (c05d12f0)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - fs/aio.c:__se_sys_io_submit
  - fs/aio.c:__se_sys_io_setup
  - fs/aio.c:__se_sys_io_setup
```
```
In block/blk-core.c (c0791624)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
```
```
In block/blk-mq.c (c079a874)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/blk-mq-sched.c (c07a2840)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
```
In block/blk-cgroup.c (c07b8488)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-throttle.c (c07ba82c)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_qnode_add_bio
```
```
In lib/percpu-refcount.c (c07db4a4)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_resurrect
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
```
```
In drivers/block/loop.c (c0a07cf0)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_rq
```
```
In drivers/scsi/scsi_lib.c (c0a4c048)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/md/md.c (c0bca0d4)
Location: include/linux/percpu-refcount.h:185
Inline: True
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
In kernel/kthread.c (c0000000001734d0)
Location: include/linux/percpu-refcount.h:185
Inline: True
```
```
In kernel/cgroup/cgroup.c (c0000000002460b0)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:kill_css
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/cgroup.c:cgroup_get_live
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/cpuset.c (c000000000253fa0)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
```
In kernel/bpf/cgroup.c (c00000000033bc20)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_offline
```
```
In mm/backing-dev.c (c00000000039f43c)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
```
```
In mm/slab_common.c (c0000000003a9670)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_deactivate_kmem_caches
```
```
In mm/slub.c (c000000000421e68)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (c00000000045a6ec)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_get_oom_group
```
```
In mm/memremap.c (c00000000046e458)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - mm/memremap.c:memremap_pages
```
```
In fs/fs-writeback.c (c0000000004cbc80)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
```
```
In fs/aio.c (c000000000506b40)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
```
```
In block/blk-core.c (c0000000007780f4)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
```
```
In block/blk-mq.c (c0000000007845e0)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/blk-mq-sched.c (c00000000078f680)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
```
In block/blk-cgroup.c (c0000000007aaa9c)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-throttle.c (c0000000007ad6bc)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_qnode_add_bio
```
```
In lib/percpu-refcount.c (c0000000007dadb4)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_resurrect
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
```
```
In drivers/block/loop.c (c0000000009c7930)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_rq
```
```
In drivers/scsi/scsi_lib.c (c000000000a326d0)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/md/md.c (c000000000bd558c)
Location: include/linux/percpu-refcount.h:185
Inline: True
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
In kernel/kthread.c (ffffffe0000df574)
Location: include/linux/percpu-refcount.h:185
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffffffe000151c42)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:kill_css
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/cgroup.c:cgroup_get_live
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/cpuset.c (ffffffe00015906a)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In kernel/bpf/cgroup.c (ffffffe0001c2178)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_offline
```
```
In mm/backing-dev.c (ffffffe0001f756a)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
```
```
In mm/slab_common.c (ffffffe0001fd3c0)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_deactivate_kmem_caches
```
```
In mm/slub.c (ffffffe00023810a)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (ffffffe0002486f2)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_get_oom_group
```
```
In fs/fs-writeback.c (ffffffe0002885d0)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:wbc_attach_and_unlock_inode
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
```
```
In fs/aio.c (ffffffe0002abd88)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - fs/aio.c:__se_sys_io_setup
  - fs/aio.c:__se_sys_io_setup
```
```
In block/blk-core.c (ffffffe000425b66)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
```
```
In block/blk-mq.c (ffffffe00042d8e0)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/blk-mq-sched.c (ffffffe0004347f2)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
```
In block/blk-cgroup.c (ffffffe00044612c)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-throttle.c (ffffffe000447e24)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_qnode_add_bio
```
```
In lib/percpu-refcount.c (ffffffe000462e44)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_resurrect
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
```
```
In drivers/block/loop.c (ffffffe0005a1076)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_rq
```
```
In drivers/scsi/scsi_lib.c (ffffffe0005dfce2)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/md/md.c (ffffffe0006ddefa)
Location: include/linux/percpu-refcount.h:185
Inline: True
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
In kernel/kthread.c (ffffffff810c3349)
Location: include/linux/percpu-refcount.h:185
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffffffff8115f477)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:kill_css
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/cgroup.c:cgroup_get_live
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/cpuset.c (ffffffff81168b73)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
```
In kernel/bpf/cgroup.c (ffffffff811fe3aa)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_offline
```
```
In mm/backing-dev.c (ffffffff81242722)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
```
```
In mm/slab_common.c (ffffffff81248dd0)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_deactivate_kmem_caches
```
```
In mm/slub.c (ffffffff8129c233)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (ffffffff812c06e1)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_get_oom_group
```
```
In mm/memremap.c (ffffffff812cd155)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - mm/memremap.c:memremap_pages
```
```
In fs/fs-writeback.c (ffffffff8130cb1f)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:wbc_attach_and_unlock_inode
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
```
```
In fs/aio.c (ffffffff813369a7)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
```
```
In block/blk-core.c (ffffffff814df0d4)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
```
```
In block/blk-mq.c (ffffffff814e78f3)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/blk-mq-sched.c (ffffffff814ef02f)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
```
In block/blk-cgroup.c (ffffffff81502823)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-throttle.c (ffffffff81504998)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_qnode_add_bio
```
```
In lib/percpu-refcount.c (ffffffff815228e8)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_resurrect
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
```
```
In drivers/block/loop.c (ffffffff816f21e6)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_rq
```
```
In drivers/scsi/scsi_lib.c (ffffffff817288e9)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/md/md.c (ffffffff8183b39b)
Location: include/linux/percpu-refcount.h:185
Inline: True
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
In kernel/kthread.c (ffffffff810b1b89)
Location: include/linux/percpu-refcount.h:185
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffffffff81152707)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:kill_css
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/cgroup.c:cgroup_get_live
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/cpuset.c (ffffffff8115bd83)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
```
In kernel/bpf/cgroup.c (ffffffff811f10fa)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_offline
```
```
In mm/backing-dev.c (ffffffff812356f2)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
```
```
In mm/slab_common.c (ffffffff8123bd7a)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_deactivate_kmem_caches
```
```
In mm/slub.c (ffffffff8128dde3)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (ffffffff812b179b)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_get_oom_group
```
```
In mm/memremap.c (ffffffff812bdfc5)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - mm/memremap.c:memremap_pages
```
```
In fs/fs-writeback.c (ffffffff812fd73f)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:wbc_attach_and_unlock_inode
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
```
```
In fs/aio.c (ffffffff81327327)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
```
```
In block/blk-core.c (ffffffff814cfa74)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
```
```
In block/blk-mq.c (ffffffff814d7e63)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/blk-mq-sched.c (ffffffff814df56f)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
```
In block/blk-cgroup.c (ffffffff814f2fd3)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-throttle.c (ffffffff814f4e58)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_qnode_add_bio
```
```
In lib/percpu-refcount.c (ffffffff81512bc8)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_resurrect
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
```
```
In drivers/block/loop.c (ffffffff816cc2e6)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_rq
```
```
In drivers/scsi/scsi_lib.c (ffffffff81701d19)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/md/md.c (ffffffff81802a0b)
Location: include/linux/percpu-refcount.h:185
Inline: True
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
In kernel/kthread.c (ffffffff810c2899)
Location: include/linux/percpu-refcount.h:185
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffffffff8115d247)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:kill_css
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/cgroup.c:cgroup_get_live
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/cpuset.c (ffffffff81166943)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
```
In kernel/bpf/cgroup.c (ffffffff811fc17a)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_offline
```
```
In mm/backing-dev.c (ffffffff812404c2)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
```
```
In mm/slab_common.c (ffffffff81246b70)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_deactivate_kmem_caches
```
```
In mm/slub.c (ffffffff8129a043)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (ffffffff812be4f1)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_get_oom_group
```
```
In mm/memremap.c (ffffffff812caf65)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - mm/memremap.c:memremap_pages
```
```
In fs/fs-writeback.c (ffffffff8130a90f)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:wbc_attach_and_unlock_inode
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
```
```
In fs/aio.c (ffffffff81334477)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
```
```
In block/blk-core.c (ffffffff814db164)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
```
```
In block/blk-mq.c (ffffffff814e3983)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/blk-mq-sched.c (ffffffff814eb0bf)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
```
In block/blk-cgroup.c (ffffffff814fe8b3)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-throttle.c (ffffffff81500a28)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_qnode_add_bio
```
```
In lib/percpu-refcount.c (ffffffff8151e978)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_resurrect
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
```
```
In drivers/block/loop.c (ffffffff8171f8c6)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_rq
```
```
In drivers/scsi/scsi_lib.c (ffffffff817676b9)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/md/md.c (ffffffff8188a9cb)
Location: include/linux/percpu-refcount.h:185
Inline: True
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
In kernel/kthread.c (ffffffff810cae89)
Location: include/linux/percpu-refcount.h:185
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffffffff8116a3ac)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:kill_css
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/cgroup.c:cgroup_get_live
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/cpuset.c (ffffffff81173fb8)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
```
In kernel/bpf/cgroup.c (ffffffff8120ad9a)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_offline
```
```
In mm/backing-dev.c (ffffffff8124fbd2)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
```
```
In mm/slab_common.c (ffffffff8125638a)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_deactivate_kmem_caches
```
```
In mm/slub.c (ffffffff812a9e8b)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (ffffffff812ceee1)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_get_oom_group
```
```
In mm/memremap.c (ffffffff812dbca3)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - mm/memremap.c:memremap_pages
```
```
In fs/fs-writeback.c (ffffffff8131c017)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:wbc_attach_and_unlock_inode
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
```
```
In fs/aio.c (ffffffff813468d7)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
```
```
In block/blk-core.c (ffffffff814f3f65)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
```
```
In block/blk-mq.c (ffffffff814fced3)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/blk-mq-sched.c (ffffffff81504096)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
```
In block/blk-cgroup.c (ffffffff81517c77)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-throttle.c (ffffffff81519983)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_qnode_add_bio
```
```
In lib/percpu-refcount.c (ffffffff81538218)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_resurrect
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
```
```
In drivers/block/loop.c (ffffffff8173ad06)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_rq
```
```
In drivers/scsi/scsi_lib.c (ffffffff81782dce)
Location: include/linux/percpu-refcount.h:185
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/md/md.c (ffffffff818a8ba4)
Location: include/linux/percpu-refcount.h:185
Inline: True
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
<b>Arch</b>
<ul>
</ul>
