# Function: <code>css_put</code>

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
In kernel/cgroup.c (ffffffff81114b28)
Location: include/linux/cgroup.h:353
Inline: True
Inline callers:
  - kernel/cgroup.c:css_killed_work_fn
  - kernel/cgroup.c:cgroup_kn_unlock
  - kernel/cgroup.c:cgroup_release_root
  - kernel/cgroup.c:css_free_work_fn
  - kernel/cgroup.c:css_free_work_fn
  - kernel/cgroup.c:css_free_work_fn
  - kernel/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup.c:cgroup_mount
```
```
In kernel/cgroup_freezer.c (ffffffff81119efa)
Location: include/linux/cgroup.h:353
Inline: True
Inline callers:
  - kernel/cgroup_freezer.c:freezer_read
  - kernel/cgroup_freezer.c:freezer_write
```
```
In kernel/cpuset.c (ffffffff8111c583)
Location: include/linux/cgroup.h:353
Inline: True
Inline callers:
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/cpuset.c:cpuset_hotplug_workfn
  - kernel/cpuset.c:proc_cpuset_show
```
```
In kernel/events/core.c (ffffffff8117eb90)
Location: include/linux/cgroup.h:353
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_free_event
```
```
In mm/page-writeback.c (ffffffff8119a60f)
Location: include/linux/cgroup.h:353
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/backing-dev.c (ffffffff811af022)
Location: include/linux/cgroup.h:353
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
```
```
In mm/memcontrol.c (ffffffff811fb235)
Location: include/linux/cgroup.h:353
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_kmem_cache_create_func
  - mm/memcontrol.c:memcg_event_remove
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:sock_release_memcg
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:task_in_mem_cgroup
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:__memcg_kmem_get_cache
  - mm/memcontrol.c:__memcg_kmem_put_cache
  - mm/memcontrol.c:__memcg_kmem_charge
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:mem_cgroup_uncharge_swap
```
```
In mm/hugetlb_cgroup.c (ffffffff81201393)
Location: include/linux/cgroup.h:353
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In fs/fs-writeback.c (ffffffff8123ab4a)
Location: include/linux/cgroup.h:353
Inline: True
Inline callers:
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In block/bio.c (ffffffff813b1a7c)
Location: include/linux/cgroup.h:353
Inline: True
Inline callers:
  - block/bio.c:bio_disassociate_task
```
```
In block/blk-cgroup.c (ffffffff813d7d01)
Location: include/linux/cgroup.h:353
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:__blkg_release_rcu
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
In kernel/cgroup.c (ffffffff8112181b)
Location: include/linux/cgroup.h:352
Inline: True
Inline callers:
  - kernel/cgroup.c:cgroup_sk_free
  - kernel/cgroup.c:cgroup_get_from_fd
  - kernel/cgroup.c:css_killed_work_fn
  - kernel/cgroup.c:css_free_work_fn
  - kernel/cgroup.c:css_free_work_fn
  - kernel/cgroup.c:css_free_work_fn
  - kernel/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup.c:cgroup_kill_sb
  - kernel/cgroup.c:cgroup_mount
  - kernel/cgroup.c:cgroup_mount
  - kernel/cgroup.c:cgroup_kn_unlock
```
```
In kernel/cgroup_freezer.c (ffffffff81121ff9)
Location: include/linux/cgroup.h:352
Inline: True
Inline callers:
  - kernel/cgroup_freezer.c:freezer_write
  - kernel/cgroup_freezer.c:freezer_read
```
```
In kernel/cpuset.c (ffffffff81125875)
Location: include/linux/cgroup.h:352
Inline: True
Inline callers:
  - kernel/cpuset.c:proc_cpuset_show
  - kernel/cpuset.c:cpuset_hotplug_workfn
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/cpuset.c:cpuset_write_resmask
```
```
In kernel/bpf/arraymap.c (ffffffff81187ac5)
Location: include/linux/cgroup.h:352
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr
```
```
In kernel/events/core.c (ffffffff8119067e)
Location: include/linux/cgroup.h:352
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_free_event
```
```
In mm/page-writeback.c (ffffffff811aef1f)
Location: include/linux/cgroup.h:352
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/backing-dev.c (ffffffff811c85c7)
Location: include/linux/cgroup.h:352
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/backing-dev.c:cgwb_release_workfn
```
```
In mm/memcontrol.c (ffffffff81224510)
Location: include/linux/cgroup.h:352
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:sock_release_memcg
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_event_remove
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:memcg_kmem_charge
  - mm/memcontrol.c:memcg_kmem_put_cache
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:memcg_kmem_cache_create_func
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:task_in_mem_cgroup
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
```
```
In mm/hugetlb_cgroup.c (ffffffff81225ada)
Location: include/linux/cgroup.h:352
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In fs/fs-writeback.c (ffffffff812629ee)
Location: include/linux/cgroup.h:352
Inline: True
Inline callers:
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In block/bio.c (ffffffff813f542c)
Location: include/linux/cgroup.h:352
Inline: True
Inline callers:
  - block/bio.c:bio_disassociate_task
```
```
In block/blk-cgroup.c (ffffffff8141e07f)
Location: include/linux/cgroup.h:352
Inline: True
Inline callers:
  - block/blk-cgroup.c:__blkg_release_rcu
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
In kernel/cgroup.c (ffffffff81129dbb)
Location: include/linux/cgroup.h:352
Inline: True
Inline callers:
  - kernel/cgroup.c:cgroup_sk_free
  - kernel/cgroup.c:cgroup_get_from_fd
  - kernel/cgroup.c:css_killed_work_fn
  - kernel/cgroup.c:css_free_work_fn
  - kernel/cgroup.c:css_free_work_fn
  - kernel/cgroup.c:css_free_work_fn
  - kernel/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup.c:cgroup_kill_sb
  - kernel/cgroup.c:cgroup_mount
  - kernel/cgroup.c:cgroup_mount
  - kernel/cgroup.c:cgroup_kn_unlock
```
```
In kernel/cgroup_freezer.c (ffffffff8112a629)
Location: include/linux/cgroup.h:352
Inline: True
Inline callers:
  - kernel/cgroup_freezer.c:freezer_write
  - kernel/cgroup_freezer.c:freezer_read
```
```
In kernel/cpuset.c (ffffffff8112f262)
Location: include/linux/cgroup.h:352
Inline: True
Inline callers:
  - kernel/cpuset.c:proc_cpuset_show
  - kernel/cpuset.c:cpuset_hotplug_workfn
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/cpuset.c:cpuset_write_resmask
```
```
In kernel/bpf/syscall.c (ffffffff8118da75)
Location: include/linux/cgroup.h:352
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:SyS_bpf
```
```
In kernel/bpf/arraymap.c (ffffffff81195985)
Location: include/linux/cgroup.h:352
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr
```
```
In kernel/events/core.c (ffffffff8119f54b)
Location: include/linux/cgroup.h:352
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_free_event
```
```
In mm/page-writeback.c (ffffffff811bf5cf)
Location: include/linux/cgroup.h:352
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/backing-dev.c (ffffffff811d86f3)
Location: include/linux/cgroup.h:352
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/backing-dev.c:cgwb_release_workfn
```
```
In mm/memcontrol.c (ffffffff81236ae0)
Location: include/linux/cgroup.h:352
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_sk_free
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_event_remove
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:memcg_kmem_charge
  - mm/memcontrol.c:memcg_kmem_put_cache
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:memcg_kmem_cache_create_func
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:task_in_mem_cgroup
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
```
```
In mm/hugetlb_cgroup.c (ffffffff812380ba)
Location: include/linux/cgroup.h:352
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In fs/fs-writeback.c (ffffffff81275e3e)
Location: include/linux/cgroup.h:352
Inline: True
Inline callers:
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In block/bio.c (ffffffff8140ee4c)
Location: include/linux/cgroup.h:352
Inline: True
Inline callers:
  - block/bio.c:bio_disassociate_task
```
```
In block/blk-cgroup.c (ffffffff8143963f)
Location: include/linux/cgroup.h:352
Inline: True
Inline callers:
  - block/blk-cgroup.c:__blkg_release_rcu
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
In kernel/cgroup/cgroup.c (ffffffff81128b9b)
Location: include/linux/cgroup.h:372
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_free
  - kernel/cgroup/cgroup.c:cgroup_get_from_fd
  - kernel/cgroup/cgroup.c:css_killed_work_fn
  - kernel/cgroup/cgroup.c:css_free_work_fn
  - kernel/cgroup/cgroup.c:css_free_work_fn
  - kernel/cgroup/cgroup.c:css_free_work_fn
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - kernel/cgroup/cgroup.c:cgroup_do_mount
  - kernel/cgroup/cgroup.c:cgroup_kn_unlock
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8112a8be)
Location: include/linux/cgroup.h:372
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_mount
```
```
In kernel/cgroup/freezer.c (ffffffff8112b319)
Location: include/linux/cgroup.h:372
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:freezer_write
  - kernel/cgroup/freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (ffffffff8112bd15)
Location: include/linux/cgroup.h:372
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy
```
```
In kernel/cgroup/cpuset.c (ffffffff811308e1)
Location: include/linux/cgroup.h:372
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In kernel/bpf/syscall.c (ffffffff81192c90)
Location: include/linux/cgroup.h:372
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:SyS_bpf
```
```
In kernel/bpf/arraymap.c (ffffffff8119cd95)
Location: include/linux/cgroup.h:372
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr
```
```
In kernel/events/core.c (ffffffff811a940b)
Location: include/linux/cgroup.h:372
Inline: True
Inline callers:
  - kernel/events/core.c:_free_event
```
```
In mm/page-writeback.c (ffffffff811c730f)
Location: include/linux/cgroup.h:372
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/backing-dev.c (ffffffff811e195f)
Location: include/linux/cgroup.h:372
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/backing-dev.c:cgwb_release_workfn
```
```
In mm/slab_common.c (ffffffff811e67c7)
Location: include/linux/cgroup.h:372
Inline: True
Inline callers:
  - mm/slab_common.c:kmemcg_deactivate_workfn
```
```
In mm/memcontrol.c (ffffffff81242571)
Location: include/linux/cgroup.h:372
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_sk_free
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_event_remove
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:memcg_kmem_charge
  - mm/memcontrol.c:memcg_kmem_put_cache
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:memcg_kmem_cache_create_func
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:task_in_mem_cgroup
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
```
```
In mm/hugetlb_cgroup.c (ffffffff81243d2c)
Location: include/linux/cgroup.h:372
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In fs/fs-writeback.c (ffffffff812832b9)
Location: include/linux/cgroup.h:372
Inline: True
Inline callers:
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In block/bio.c (ffffffff8141c96c)
Location: include/linux/cgroup.h:372
Inline: True
Inline callers:
  - block/bio.c:bio_disassociate_task
```
```
In block/blk-cgroup.c (ffffffff81446e6d)
Location: include/linux/cgroup.h:372
Inline: True
Inline callers:
  - block/blk-cgroup.c:__blkg_release_rcu
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
In kernel/kthread.c (ffffffff810ac934)
Location: include/linux/cgroup.h:384
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffffffff811351cb)
Location: include/linux/cgroup.h:384
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_free
  - kernel/cgroup/cgroup.c:cgroup_get_from_fd
  - kernel/cgroup/cgroup.c:css_killed_work_fn
  - kernel/cgroup/cgroup.c:css_free_work_fn
  - kernel/cgroup/cgroup.c:css_free_work_fn
  - kernel/cgroup/cgroup.c:css_free_work_fn
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - kernel/cgroup/cgroup.c:cgroup_do_mount
  - kernel/cgroup/cgroup.c:cgroup_kn_unlock
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8113764e)
Location: include/linux/cgroup.h:384
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_mount
```
```
In kernel/cgroup/freezer.c (ffffffff81138119)
Location: include/linux/cgroup.h:384
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:freezer_write
  - kernel/cgroup/freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (ffffffff81138b15)
Location: include/linux/cgroup.h:384
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy
```
```
In kernel/cgroup/cpuset.c (ffffffff8113d821)
Location: include/linux/cgroup.h:384
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In kernel/bpf/syscall.c (ffffffff8119ffa2)
Location: include/linux/cgroup.h:384
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:SyS_bpf
```
```
In kernel/bpf/arraymap.c (ffffffff811ac845)
Location: include/linux/cgroup.h:384
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr
```
```
In kernel/events/core.c (ffffffff811bcc6b)
Location: include/linux/cgroup.h:384
Inline: True
Inline callers:
  - kernel/events/core.c:_free_event
```
```
In mm/page-writeback.c (ffffffff811dc11f)
Location: include/linux/cgroup.h:384
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/backing-dev.c (ffffffff811f79af)
Location: include/linux/cgroup.h:384
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/backing-dev.c:cgwb_release_workfn
```
```
In mm/slab_common.c (ffffffff811fca0d)
Location: include/linux/cgroup.h:384
Inline: True
Inline callers:
  - mm/slab_common.c:kmemcg_deactivate_workfn
```
```
In mm/memcontrol.c (ffffffff812620e1)
Location: include/linux/cgroup.h:384
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_sk_free
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_event_remove
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:memcg_kmem_charge
  - mm/memcontrol.c:memcg_kmem_put_cache
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:memcg_kmem_cache_create_func
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:task_in_mem_cgroup
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
```
```
In mm/hugetlb_cgroup.c (ffffffff81263b7c)
Location: include/linux/cgroup.h:384
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In fs/fs-writeback.c (ffffffff812a5e29)
Location: include/linux/cgroup.h:384
Inline: True
Inline callers:
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In block/bio.c (ffffffff8144752c)
Location: include/linux/cgroup.h:384
Inline: True
Inline callers:
  - block/bio.c:bio_disassociate_task
```
```
In block/blk-cgroup.c (ffffffff81473a4d)
Location: include/linux/cgroup.h:384
Inline: True
Inline callers:
  - block/blk-cgroup.c:__blkg_release_rcu
  - block/blk-cgroup.c:blkg_create
```
```
In drivers/block/loop.c (ffffffff8166fdf0)
Location: include/linux/cgroup.h:384
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_rw_aio_complete
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
In kernel/kthread.c (ffffffff810b3949)
Location: include/linux/cgroup.h:384
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffffffff811438eb)
Location: include/linux/cgroup.h:384
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_free
  - kernel/cgroup/cgroup.c:cgroup_get_from_fd
  - kernel/cgroup/cgroup.c:css_killed_work_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - kernel/cgroup/cgroup.c:cgroup_do_mount
  - kernel/cgroup/cgroup.c:cgroup_kn_unlock
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81145efe)
Location: include/linux/cgroup.h:384
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_mount
```
```
In kernel/cgroup/freezer.c (ffffffff8114691e)
Location: include/linux/cgroup.h:384
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:freezer_write
  - kernel/cgroup/freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (ffffffff81147447)
Location: include/linux/cgroup.h:384
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy
```
```
In kernel/cgroup/cpuset.c (ffffffff8114c0e3)
Location: include/linux/cgroup.h:384
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In kernel/bpf/arraymap.c (ffffffff811c3e25)
Location: include/linux/cgroup.h:384
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr
```
```
In kernel/bpf/cgroup.c (ffffffff811d2833)
Location: include/linux/cgroup.h:384
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_query
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_attach
```
```
In kernel/events/core.c (ffffffff811d8f30)
Location: include/linux/cgroup.h:384
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_free_event
```
```
In mm/page-writeback.c (ffffffff811fdb47)
Location: include/linux/cgroup.h:384
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/backing-dev.c (ffffffff81218ceb)
Location: include/linux/cgroup.h:384
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/backing-dev.c:cgwb_release_workfn
```
```
In mm/slab_common.c (ffffffff8121dd5d)
Location: include/linux/cgroup.h:384
Inline: True
Inline callers:
  - mm/slab_common.c:kmemcg_deactivate_workfn
```
```
In mm/memcontrol.c (ffffffff812860e1)
Location: include/linux/cgroup.h:384
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_sk_free
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_event_remove
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:memcg_kmem_charge
  - mm/memcontrol.c:memcg_kmem_put_cache
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:memcg_kmem_cache_create_func
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:task_in_mem_cgroup
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
```
```
In mm/hugetlb_cgroup.c (ffffffff81287e94)
Location: include/linux/cgroup.h:384
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In fs/fs-writeback.c (ffffffff812cc9e4)
Location: include/linux/cgroup.h:384
Inline: True
Inline callers:
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In block/bio.c (ffffffff8147a62c)
Location: include/linux/cgroup.h:384
Inline: True
Inline callers:
  - block/bio.c:bio_disassociate_task
```
```
In block/blk-cgroup.c (ffffffff814a7e1a)
Location: include/linux/cgroup.h:384
Inline: True
Inline callers:
  - block/blk-cgroup.c:__blkg_release_rcu
  - block/blk-cgroup.c:blkg_create
```
```
In drivers/block/loop.c (ffffffff816ab8c0)
Location: include/linux/cgroup.h:384
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_rw_aio_complete
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
In kernel/kthread.c (ffffffff810bcc49)
Location: include/linux/cgroup.h:386
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffffffff8114f3fb)
Location: include/linux/cgroup.h:386
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_free
  - kernel/cgroup/cgroup.c:cgroup_get_from_fd
  - kernel/cgroup/cgroup.c:css_killed_work_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - kernel/cgroup/cgroup.c:cgroup_do_mount
  - kernel/cgroup/cgroup.c:cgroup_kn_unlock
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81151abe)
Location: include/linux/cgroup.h:386
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_mount
```
```
In kernel/cgroup/freezer.c (ffffffff811525ee)
Location: include/linux/cgroup.h:386
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:freezer_write
  - kernel/cgroup/freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (ffffffff81153117)
Location: include/linux/cgroup.h:386
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy
```
```
In kernel/cgroup/cpuset.c (ffffffff81158d2f)
Location: include/linux/cgroup.h:386
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
```
In kernel/bpf/arraymap.c (ffffffff811d5ae5)
Location: include/linux/cgroup.h:386
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr
```
```
In kernel/bpf/cgroup.c (ffffffff811e25c3)
Location: include/linux/cgroup.h:386
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_query
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_attach
```
```
In kernel/events/core.c (ffffffff811e9413)
Location: include/linux/cgroup.h:386
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_free_event
```
```
In mm/oom_kill.c (ffffffff81205dec)
Location: include/linux/cgroup.h:386
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
```
```
In mm/page-writeback.c (ffffffff81210663)
Location: include/linux/cgroup.h:386
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/backing-dev.c (ffffffff8122bb3b)
Location: include/linux/cgroup.h:386
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/backing-dev.c:cgwb_release_workfn
```
```
In mm/slab_common.c (ffffffff81230d3d)
Location: include/linux/cgroup.h:386
Inline: True
Inline callers:
  - mm/slab_common.c:kmemcg_deactivate_workfn
```
```
In mm/memcontrol.c (ffffffff8129b031)
Location: include/linux/cgroup.h:386
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_sk_free
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_event_remove
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:memcg_kmem_charge
  - mm/memcontrol.c:memcg_kmem_put_cache
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:memcg_kmem_cache_create_func
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:task_in_mem_cgroup
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
```
```
In mm/hugetlb_cgroup.c (ffffffff8129cde4)
Location: include/linux/cgroup.h:386
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In fs/fs-writeback.c (ffffffff812e1d04)
Location: include/linux/cgroup.h:386
Inline: True
Inline callers:
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/buffer.c (ffffffff812ebed4)
Location: include/linux/cgroup.h:386
Inline: True
Inline callers:
  - fs/buffer.c:alloc_page_buffers
```
```
In fs/notify/group.c (ffffffff812f9c59)
Location: include/linux/cgroup.h:386
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_put_group
```
```
In block/blk-cgroup.c (ffffffff814c27e9)
Location: include/linux/cgroup.h:386
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:__blkg_release
```
```
In drivers/block/loop.c (ffffffff816cc660)
Location: include/linux/cgroup.h:386
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_rw_aio_complete
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
In kernel/kthread.c (ffffffff810c2a35)
Location: include/linux/cgroup.h:393
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffffffff8115b29e)
Location: include/linux/cgroup.h:393
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_free
  - kernel/cgroup/cgroup.c:cgroup_get_from_fd
  - kernel/cgroup/cgroup.c:css_killed_work_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - kernel/cgroup/cgroup.c:cgroup_do_get_tree
  - kernel/cgroup/cgroup.c:cgroup_kn_unlock
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8115d92e)
Location: include/linux/cgroup.h:393
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff8115ec4c)
Location: include/linux/cgroup.h:393
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (ffffffff8115fa68)
Location: include/linux/cgroup.h:393
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy
```
```
In kernel/cgroup/cpuset.c (ffffffff81165484)
Location: include/linux/cgroup.h:393
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
```
In kernel/bpf/arraymap.c (ffffffff811ea475)
Location: include/linux/cgroup.h:393
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr
```
```
In kernel/bpf/cgroup.c (ffffffff811f9728)
Location: include/linux/cgroup.h:393
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_query
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_release
```
```
In kernel/events/core.c (ffffffff81202759)
Location: include/linux/cgroup.h:393
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_free_event
```
```
In mm/oom_kill.c (ffffffff8121c354)
Location: include/linux/cgroup.h:393
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
```
```
In mm/page-writeback.c (ffffffff8121fcc0)
Location: include/linux/cgroup.h:393
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/backing-dev.c (ffffffff8123b7e5)
Location: include/linux/cgroup.h:393
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/backing-dev.c:cgwb_release_workfn
```
```
In mm/slab_common.c (ffffffff8124227c)
Location: include/linux/cgroup.h:393
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_deactivate_kmem_caches
```
```
In mm/slub.c (ffffffff81293f13)
Location: include/linux/cgroup.h:393
Inline: True
Inline callers:
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (ffffffff812b6301)
Location: include/linux/cgroup.h:393
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_sk_free
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_event_remove
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:__memcg_kmem_charge
  - mm/memcontrol.c:memcg_kmem_cache_create_func
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
```
```
In mm/hugetlb_cgroup.c (ffffffff812b7f84)
Location: include/linux/cgroup.h:393
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In fs/fs-writeback.c (ffffffff813002bd)
Location: include/linux/cgroup.h:393
Inline: True
Inline callers:
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/buffer.c (ffffffff8130d60a)
Location: include/linux/cgroup.h:393
Inline: True
Inline callers:
  - fs/buffer.c:alloc_page_buffers
```
```
In fs/notify/group.c (ffffffff8131a309)
Location: include/linux/cgroup.h:393
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_put_group
```
```
In block/blk-cgroup.c (ffffffff814f0e01)
Location: include/linux/cgroup.h:393
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:__blkg_release
```
```
In drivers/block/loop.c (ffffffff817080f0)
Location: include/linux/cgroup.h:393
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_rw_aio_complete
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
In kernel/kthread.c (ffffffff810c8fa4)
Location: include/linux/cgroup.h:395
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffffffff81166f5e)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_free
  - kernel/cgroup/cgroup.c:cgroup_get_from_fd
  - kernel/cgroup/cgroup.c:css_killed_work_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - kernel/cgroup/cgroup.c:cgroup_do_get_tree
  - kernel/cgroup/cgroup.c:cgroup_kn_unlock
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8116953e)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff8116a8ac)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (ffffffff8116b6c8)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy
```
```
In kernel/cgroup/cpuset.c (ffffffff81171374)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
```
In kernel/bpf/arraymap.c (ffffffff811f6bd5)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr
```
```
In kernel/bpf/cgroup.c (ffffffff812067f8)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_query
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_release
```
```
In kernel/events/core.c (ffffffff8120f586)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_free_event
```
```
In mm/oom_kill.c (ffffffff81229d24)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
```
```
In mm/page-writeback.c (ffffffff8122d770)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/backing-dev.c (ffffffff81249de3)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/backing-dev.c:cgwb_release_workfn
```
```
In mm/slab_common.c (ffffffff8125070c)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:destroy_memcg_params
```
```
In mm/slub.c (ffffffff812a3c83)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (ffffffff812c81d1)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_sk_free
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_event_remove
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:__memcg_kmem_charge
  - mm/memcontrol.c:memcg_kmem_cache_create_func
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
```
```
In mm/hugetlb_cgroup.c (ffffffff812c9e80)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In fs/fs-writeback.c (ffffffff81314af0)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/buffer.c (ffffffff813205da)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - fs/buffer.c:alloc_page_buffers
```
```
In fs/notify/group.c (ffffffff8132d129)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_put_group
```
```
In block/blk-cgroup.c (ffffffff8150a3dc)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:__blkg_release
```
```
In drivers/block/loop.c (ffffffff8172c340)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_rw_aio_complete
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void css_put(struct cgroup_subsys_state *css);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810d0994)
Location: include/linux/cgroup.h:401
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffffffff81178679)
Location: include/linux/cgroup.h:401
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_free
  - kernel/cgroup/cgroup.c:cgroup_get_from_fd
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:css_killed_work_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - kernel/cgroup/cgroup.c:cgroup_do_get_tree
  - kernel/cgroup/cgroup.c:cgroup_kn_unlock
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8117a015)
Location: include/linux/cgroup.h:401
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff8117c36b)
Location: include/linux/cgroup.h:401
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_change_state
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (ffffffff8117d294)
Location: include/linux/cgroup.h:401
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy
```
```
In kernel/cgroup/cpuset.c (ffffffff81183084)
Location: include/linux/cgroup.h:401
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_nodemasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:rebuild_root_domains
```
```
In kernel/bpf/arraymap.c (ffffffff8121a4a5)
Location: include/linux/cgroup.h:401
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr
```
```
In kernel/bpf/cgroup.c (ffffffff8122e418)
Location: include/linux/cgroup.h:401
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_query
  - kernel/bpf/cgroup.c:cgroup_bpf_link_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_release
  - kernel/bpf/cgroup.c:cgroup_bpf_release
```
```
In kernel/events/core.c (ffffffff8123a7f5)
Location: include/linux/cgroup.h:401
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_free_event
```
```
In mm/oom_kill.c (ffffffff81256b94)
Location: include/linux/cgroup.h:401
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
```
```
In mm/page-writeback.c (ffffffff8125b198)
Location: include/linux/cgroup.h:401
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/backing-dev.c (ffffffff81278004)
Location: include/linux/cgroup.h:401
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_create
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/backing-dev.c:cgwb_release_workfn
```
```
In mm/slab_common.c (ffffffff8127ed6a)
Location: include/linux/cgroup.h:401
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:destroy_memcg_params
```
```
In mm/slub.c (ffffffff812d97c0)
Location: include/linux/cgroup.h:401
Inline: True
Inline callers:
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (ffffffff812fda31)
Location: include/linux/cgroup.h:401
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_sk_free
  - mm/memcontrol.c:mem_cgroup_charge
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_event_remove
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:__memcg_kmem_charge_page
  - mm/memcontrol.c:memcg_kmem_cache_create_func
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
Direct callers:
  - mm/memcontrol.c:memcg_kmem_get_cache
```
```
In mm/hugetlb_cgroup.c (ffffffff812ffcf7)
Location: include/linux/cgroup.h:401
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_file_region
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_counter
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_cgroup_rsvd
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
```
```
In fs/fs-writeback.c (ffffffff8134e4d2)
Location: include/linux/cgroup.h:401
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/buffer.c (ffffffff81359a37)
Location: include/linux/cgroup.h:401
Inline: True
Inline callers:
  - fs/buffer.c:alloc_page_buffers
```
```
In fs/notify/group.c (ffffffff81366e9c)
Location: include/linux/cgroup.h:401
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_final_destroy_group
```
```
In block/blk-cgroup.c (ffffffff8156b590)
Location: include/linux/cgroup.h:401
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:__blkg_release
```
```
In drivers/block/loop.c (ffffffff817e7b00)
Location: include/linux/cgroup.h:401
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_rw_aio_complete
```
**Symbols:**

```
ffffffff812f6cb0-ffffffff812f6ce2: css_put (STB_LOCAL)
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
In kernel/kthread.c (ffffffff810cb574)
Location: include/linux/cgroup.h:401
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffffffff8117542e)
Location: include/linux/cgroup.h:401
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_free
  - kernel/cgroup/cgroup.c:cgroup_get_from_fd
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:css_killed_work_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - kernel/cgroup/cgroup.c:cgroup_do_get_tree
  - kernel/cgroup/cgroup.c:cgroup_kn_unlock
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81176d7f)
Location: include/linux/cgroup.h:401
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff811791c2)
Location: include/linux/cgroup.h:401
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_change_state
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (ffffffff8117a0f4)
Location: include/linux/cgroup.h:401
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy
```
```
In kernel/cgroup/cpuset.c (ffffffff8118000b)
Location: include/linux/cgroup.h:401
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_nodemasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:rebuild_root_domains
```
```
In kernel/bpf/syscall.c (ffffffff811fb617)
Location: include/linux/cgroup.h:401
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_map_free_deferred
```
```
In kernel/bpf/arraymap.c (ffffffff8121d115)
Location: include/linux/cgroup.h:401
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr
```
```
In kernel/bpf/cgroup.c (ffffffff81236957)
Location: include/linux/cgroup.h:401
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_query
  - kernel/bpf/cgroup.c:cgroup_bpf_link_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_release
  - kernel/bpf/cgroup.c:cgroup_bpf_release
```
```
In kernel/events/core.c (ffffffff81243c1c)
Location: include/linux/cgroup.h:401
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_free_event
```
```
In mm/oom_kill.c (ffffffff812617a4)
Location: include/linux/cgroup.h:401
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
```
```
In mm/page-writeback.c (ffffffff812653c2)
Location: include/linux/cgroup.h:401
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/backing-dev.c (ffffffff81282781)
Location: include/linux/cgroup.h:401
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_create
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/backing-dev.c:cgwb_release_workfn
```
```
In mm/mmap_lock.c (ffffffff81295f75)
Location: include/linux/cgroup.h:401
Inline: True
Inline callers:
  - mm/mmap_lock.c:get_mm_memcg_path
```
```
In mm/hugetlb.c (ffffffff812d3a24)
Location: include/linux/cgroup.h:401
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:coalesce_file_region
  - mm/hugetlb.c:coalesce_file_region
```
```
In mm/memcontrol.c (ffffffff8130a15d)
Location: include/linux/cgroup.h:401
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_sk_free
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:mem_cgroup_charge
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_event_remove
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:obj_cgroup_charge
  - mm/memcontrol.c:__memcg_kmem_uncharge_page
  - mm/memcontrol.c:__memcg_kmem_charge_page
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:drain_stock
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_oom_trylock
  - mm/memcontrol.c:mem_cgroup_oom_trylock
  - mm/memcontrol.c:mem_cgroup_scan_tasks
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:memcg_expand_shrinker_maps
  - mm/memcontrol.c:memcg_reparent_objcgs
  - mm/memcontrol.c:obj_cgroup_release
```
```
In mm/hugetlb_cgroup.c (ffffffff8130c097)
Location: include/linux/cgroup.h:401
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_file_region
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_counter
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_cgroup_rsvd
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
```
```
In fs/fs-writeback.c (ffffffff8135b386)
Location: include/linux/cgroup.h:401
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/buffer.c (ffffffff81367b24)
Location: include/linux/cgroup.h:401
Inline: True
Inline callers:
  - fs/buffer.c:alloc_page_buffers
```
```
In fs/notify/group.c (ffffffff813741ec)
Location: include/linux/cgroup.h:401
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_final_destroy_group
```
```
In fs/io_uring.c (ffffffff8138faa9)
Location: include/linux/cgroup.h:401
Inline: True
Inline callers:
  - fs/io_uring.c:io_ring_ctx_free
  - fs/io_uring.c:io_req_clean_work
```
```
In block/blk-cgroup.c (ffffffff81585f23)
Location: include/linux/cgroup.h:401
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:__blkg_release
```
```
In drivers/block/loop.c (ffffffff817fc9e1)
Location: include/linux/cgroup.h:401
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_rw_aio_complete
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
In kernel/kthread.c (ffffffff810cceb5)
Location: include/linux/cgroup.h:401
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffffffff81175f9e)
Location: include/linux/cgroup.h:401
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_free
  - kernel/cgroup/cgroup.c:cgroup_get_from_fd
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:css_killed_work_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - kernel/cgroup/cgroup.c:cgroup_do_get_tree
  - kernel/cgroup/cgroup.c:cgroup_kn_unlock
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81177901)
Location: include/linux/cgroup.h:401
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff81179d32)
Location: include/linux/cgroup.h:401
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_change_state
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (ffffffff8117ac74)
Location: include/linux/cgroup.h:401
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy
```
```
In kernel/cgroup/cpuset.c (ffffffff81180adb)
Location: include/linux/cgroup.h:401
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_nodemasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
```
In kernel/bpf/syscall.c (ffffffff811fc337)
Location: include/linux/cgroup.h:401
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_map_free_deferred
```
```
In kernel/bpf/arraymap.c (ffffffff81220c25)
Location: include/linux/cgroup.h:401
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr
```
```
In kernel/bpf/cgroup.c (ffffffff8123abb7)
Location: include/linux/cgroup.h:401
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_query
  - kernel/bpf/cgroup.c:cgroup_bpf_link_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_release
  - kernel/bpf/cgroup.c:cgroup_bpf_release
```
```
In kernel/events/core.c (ffffffff81248be1)
Location: include/linux/cgroup.h:401
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_free_event
```
```
In mm/oom_kill.c (ffffffff81265fd4)
Location: include/linux/cgroup.h:401
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
```
```
In mm/page-writeback.c (ffffffff812695d1)
Location: include/linux/cgroup.h:401
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/backing-dev.c (ffffffff8128784f)
Location: include/linux/cgroup.h:401
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_create
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/backing-dev.c:cgwb_release_workfn
```
```
In mm/mmap_lock.c (ffffffff8129b892)
Location: include/linux/cgroup.h:401
Inline: True
Inline callers:
  - mm/mmap_lock.c:get_mm_memcg_path
```
```
In mm/hugetlb.c (ffffffff812da8a7)
Location: include/linux/cgroup.h:401
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:coalesce_file_region
  - mm/hugetlb.c:coalesce_file_region
```
```
In mm/memcontrol.c (ffffffff813109df)
Location: include/linux/cgroup.h:401
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_sk_free
  - mm/memcontrol.c:uncharge_page
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:mem_cgroup_swapin_charge_page
  - mm/memcontrol.c:mem_cgroup_charge
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_event_remove
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:obj_cgroup_charge_pages
  - mm/memcontrol.c:obj_cgroup_uncharge_pages
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:drain_stock
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_oom_trylock
  - mm/memcontrol.c:mem_cgroup_oom_trylock
  - mm/memcontrol.c:mem_cgroup_scan_tasks
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:obj_cgroup_release
```
```
In mm/hugetlb_cgroup.c (ffffffff81312697)
Location: include/linux/cgroup.h:401
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_file_region
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_counter
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_cgroup_rsvd
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
```
```
In fs/fs-writeback.c (ffffffff81361f86)
Location: include/linux/cgroup.h:401
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/notify/group.c (ffffffff8137ab85)
Location: include/linux/cgroup.h:401
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_put_group
```
```
In block/blk-cgroup.c (ffffffff8158c913)
Location: include/linux/cgroup.h:401
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:__blkg_release
```
```
In drivers/block/loop.c (ffffffff817e15b1)
Location: include/linux/cgroup.h:401
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_rw_aio_complete
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
In kernel/kthread.c (ffffffff810df904)
Location: include/linux/cgroup.h:401
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffffffff8119d551)
Location: include/linux/cgroup.h:401
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_free
  - kernel/cgroup/cgroup.c:cgroup_get_from_fd
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:css_killed_work_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - kernel/cgroup/cgroup.c:cgroup_do_get_tree
  - kernel/cgroup/cgroup.c:cgroup_kn_unlock
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8119f211)
Location: include/linux/cgroup.h:401
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff811a1652)
Location: include/linux/cgroup.h:401
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_change_state
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (ffffffff811a26a8)
Location: include/linux/cgroup.h:401
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy
```
```
In kernel/cgroup/cpuset.c (ffffffff811a88cb)
Location: include/linux/cgroup.h:401
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_nodemasks_hier
  - kernel/cgroup/cpuset.c:update_sibling_cpumasks
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
```
In kernel/bpf/syscall.c (ffffffff8122dc67)
Location: include/linux/cgroup.h:401
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_map_free_deferred
```
```
In kernel/bpf/arraymap.c (ffffffff812585e5)
Location: include/linux/cgroup.h:401
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr
```
```
In kernel/bpf/cgroup.c (ffffffff81275797)
Location: include/linux/cgroup.h:401
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_query
  - kernel/bpf/cgroup.c:cgroup_bpf_link_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_release
  - kernel/bpf/cgroup.c:cgroup_bpf_release
```
```
In kernel/events/core.c (ffffffff812839e5)
Location: include/linux/cgroup.h:401
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_free_event
```
```
In mm/oom_kill.c (ffffffff812a27f4)
Location: include/linux/cgroup.h:401
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
```
```
In mm/page-writeback.c (ffffffff812a604b)
Location: include/linux/cgroup.h:401
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/backing-dev.c (ffffffff812c6ff7)
Location: include/linux/cgroup.h:401
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_create
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/backing-dev.c:cgwb_release_workfn
```
```
In mm/mmap_lock.c (ffffffff812dc382)
Location: include/linux/cgroup.h:401
Inline: True
Inline callers:
  - mm/mmap_lock.c:get_mm_memcg_path
```
```
In mm/hugetlb.c (ffffffff8132184a)
Location: include/linux/cgroup.h:401
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:coalesce_file_region
  - mm/hugetlb.c:coalesce_file_region
```
```
In mm/memcontrol.c (ffffffff8135bcd3)
Location: include/linux/cgroup.h:401
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_sk_free
  - mm/memcontrol.c:uncharge_page
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:mem_cgroup_swapin_charge_page
  - mm/memcontrol.c:__mem_cgroup_charge
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_event_remove
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:obj_cgroup_charge_pages
  - mm/memcontrol.c:obj_cgroup_uncharge_pages
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_oom_trylock
  - mm/memcontrol.c:mem_cgroup_oom_trylock
  - mm/memcontrol.c:mem_cgroup_scan_tasks
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
```
```
In mm/hugetlb_cgroup.c (ffffffff8135e0f4)
Location: include/linux/cgroup.h:401
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_file_region
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_counter
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_cgroup_rsvd
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
```
```
In fs/fs-writeback.c (ffffffff813b07f9)
Location: include/linux/cgroup.h:401
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/notify/group.c (ffffffff813c7865)
Location: include/linux/cgroup.h:401
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_put_group
```
```
In block/blk-cgroup.c (ffffffff815f201b)
Location: include/linux/cgroup.h:401
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:__blkg_release
```
```
In drivers/block/loop.c (ffffffff8186fb8e)
Location: include/linux/cgroup.h:401
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_free_idle_workers
  - drivers/block/loop.c:loop_process_work
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:loop_queue_work
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void css_put(struct cgroup_subsys_state *css);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8107e87a)
Location: include/linux/cgroup.h:401
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_alloc_backing
```
```
In kernel/kthread.c (ffffffff810f9c66)
Location: include/linux/cgroup.h:401
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffffffff811cd896)
Location: include/linux/cgroup.h:401
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_free
  - kernel/cgroup/cgroup.c:cgroup_sk_free
  - kernel/cgroup/cgroup.c:cgroup_get_from_fd
  - kernel/cgroup/cgroup.c:cgroup_get_from_fd
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:css_killed_work_fn
  - kernel/cgroup/cgroup.c:css_killed_work_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - kernel/cgroup/cgroup.c:cgroup_do_get_tree
  - kernel/cgroup/cgroup.c:cgroup_do_get_tree
  - kernel/cgroup/cgroup.c:cgroup_kn_unlock
  - kernel/cgroup/cgroup.c:cgroup_kn_unlock
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff811cf866)
Location: include/linux/cgroup.h:401
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use
  - kernel/cgroup/cgroup-v1.c:cgroupstats_build
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff811d1f9a)
Location: include/linux/cgroup.h:401
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_change_state
  - kernel/cgroup/legacy_freezer.c:freezer_change_state
  - kernel/cgroup/legacy_freezer.c:freezer_read
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (ffffffff811d30fa)
Location: include/linux/cgroup.h:401
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy
```
```
In kernel/cgroup/cpuset.c (ffffffff811d9a7e)
Location: include/linux/cgroup.h:401
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_nodemasks_hier
  - kernel/cgroup/cpuset.c:update_nodemasks_hier
  - kernel/cgroup/cpuset.c:update_sibling_cpumasks
  - kernel/cgroup/cpuset.c:update_sibling_cpumasks
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
```
In kernel/bpf/syscall.c (ffffffff8126ff32)
Location: include/linux/cgroup.h:401
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_map_free_deferred
```
```
In kernel/bpf/arraymap.c (ffffffff812a13b5)
Location: include/linux/cgroup.h:401
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr
```
```
In kernel/bpf/cgroup.c (ffffffff812c51cf)
Location: include/linux/cgroup.h:401
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_query
  - kernel/bpf/cgroup.c:cgroup_bpf_link_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_release
  - kernel/bpf/cgroup.c:cgroup_bpf_release
```
```
In kernel/events/core.c (ffffffff812d6b43)
Location: include/linux/cgroup.h:401
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_free_event
```
```
In mm/oom_kill.c (ffffffff812fa475)
Location: include/linux/cgroup.h:401
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
```
```
In mm/page-writeback.c (ffffffff812fed37)
Location: include/linux/cgroup.h:401
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/backing-dev.c (ffffffff8132380b)
Location: include/linux/cgroup.h:401
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_create
  - mm/backing-dev.c:cgwb_create
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/backing-dev.c:cgwb_release_workfn
```
```
In mm/mmap_lock.c (ffffffff8133c2ef)
Location: include/linux/cgroup.h:401
Inline: True
Inline callers:
  - mm/mmap_lock.c:get_mm_memcg_path
```
```
In mm/hugetlb.c (ffffffff8138e955)
Location: include/linux/cgroup.h:401
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:clear_vma_resv_huge_pages
  - mm/hugetlb.c:clear_vma_resv_huge_pages
  - mm/hugetlb.c:coalesce_file_region
  - mm/hugetlb.c:coalesce_file_region
  - mm/hugetlb.c:coalesce_file_region
  - mm/hugetlb.c:coalesce_file_region
```
```
In mm/slub.c (ffffffff813a685c)
Location: include/linux/cgroup.h:401
Inline: True
```
```
In mm/memcontrol.c (ffffffff813d5c31)
Location: include/linux/cgroup.h:401
Inline: True
Inline callers:
  - mm/memcontrol.c:obj_cgroup_may_zswap
  - mm/memcontrol.c:obj_cgroup_may_zswap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_sk_free
  - mm/memcontrol.c:mem_cgroup_sk_free
  - mm/memcontrol.c:uncharge_folio
  - mm/memcontrol.c:uncharge_folio
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:mem_cgroup_swapin_charge_page
  - mm/memcontrol.c:mem_cgroup_swapin_charge_page
  - mm/memcontrol.c:__mem_cgroup_charge
  - mm/memcontrol.c:__mem_cgroup_charge
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_event_remove
  - mm/memcontrol.c:memcg_event_remove
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:obj_cgroup_charge
  - mm/memcontrol.c:obj_cgroup_charge
  - mm/memcontrol.c:drain_obj_stock
  - mm/memcontrol.c:drain_obj_stock
  - mm/memcontrol.c:__memcg_kmem_charge_page
  - mm/memcontrol.c:__memcg_kmem_charge_page
  - mm/memcontrol.c:obj_cgroup_uncharge_pages
  - mm/memcontrol.c:obj_cgroup_uncharge_pages
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_oom_trylock
  - mm/memcontrol.c:mem_cgroup_oom_trylock
  - mm/memcontrol.c:mem_cgroup_oom_trylock
  - mm/memcontrol.c:mem_cgroup_oom_trylock
  - mm/memcontrol.c:mem_cgroup_scan_tasks
  - mm/memcontrol.c:mem_cgroup_scan_tasks
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
```
```
In mm/hugetlb_cgroup.c (ffffffff813d8520)
Location: include/linux/cgroup.h:401
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_file_region
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_file_region
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_counter
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_counter
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_cgroup_rsvd
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_cgroup_rsvd
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
```
```
In fs/fs-writeback.c (ffffffff814355e9)
Location: include/linux/cgroup.h:401
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/notify/group.c (ffffffff8144ec4e)
Location: include/linux/cgroup.h:401
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_put_group
```
```
In block/blk-cgroup.c (ffffffff816a3853)
Location: include/linux/cgroup.h:401
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:__blkg_release
  - block/blk-cgroup.c:__blkg_release
```
```
In block/blk-cgroup-fc-appid.c (ffffffff816a5434)
Location: include/linux/cgroup.h:401
Inline: True
Inline callers:
  - block/blk-cgroup-fc-appid.c:blkcg_set_fc_appid
  - block/blk-cgroup-fc-appid.c:blkcg_set_fc_appid
  - block/blk-cgroup-fc-appid.c:blkcg_set_fc_appid
  - block/blk-cgroup-fc-appid.c:blkcg_set_fc_appid
```
```
In drivers/block/loop.c (ffffffff819b7688)
Location: include/linux/cgroup.h:401
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_process_work
  - drivers/block/loop.c:loop_process_work
  - drivers/block/loop.c:loop_free_idle_workers
  - drivers/block/loop.c:loop_free_idle_workers
Direct callers:
  - drivers/block/loop.c:loop_queue_work
```
**Symbols:**

```
ffffffff819b5c50-ffffffff819b5ca9: css_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void css_put(struct cgroup_subsys_state *css);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8108feba)
Location: include/linux/cgroup_refcnt.h:76
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_alloc_backing
```
```
In kernel/kthread.c (ffffffff8111c9a6)
Location: include/linux/cgroup_refcnt.h:76
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffffffff81210f46)
Location: include/linux/cgroup_refcnt.h:76
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_free
  - kernel/cgroup/cgroup.c:cgroup_sk_free
  - kernel/cgroup/cgroup.c:cgroup_get_from_fd
  - kernel/cgroup/cgroup.c:cgroup_get_from_fd
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:cgroup_get_from_id
  - kernel/cgroup/cgroup.c:cgroup_get_from_id
  - kernel/cgroup/cgroup.c:css_killed_work_fn
  - kernel/cgroup/cgroup.c:css_killed_work_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:pressure_write
  - kernel/cgroup/cgroup.c:pressure_write
  - kernel/cgroup/cgroup.c:pressure_write
  - kernel/cgroup/cgroup.c:pressure_write
  - kernel/cgroup/cgroup.c:pressure_write
  - kernel/cgroup/cgroup.c:pressure_write
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - kernel/cgroup/cgroup.c:cgroup_do_get_tree
  - kernel/cgroup/cgroup.c:cgroup_do_get_tree
  - kernel/cgroup/cgroup.c:cgroup_kn_unlock
  - kernel/cgroup/cgroup.c:cgroup_kn_unlock
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff812130a6)
Location: include/linux/cgroup_refcnt.h:76
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use
  - kernel/cgroup/cgroup-v1.c:cgroupstats_build
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff81215cca)
Location: include/linux/cgroup_refcnt.h:76
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_change_state
  - kernel/cgroup/legacy_freezer.c:freezer_change_state
  - kernel/cgroup/legacy_freezer.c:freezer_read
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (ffffffff81217071)
Location: include/linux/cgroup_refcnt.h:76
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy
```
```
In kernel/cgroup/cpuset.c (ffffffff8121ef4e)
Location: include/linux/cgroup_refcnt.h:76
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_nodemasks_hier
  - kernel/cgroup/cpuset.c:update_nodemasks_hier
  - kernel/cgroup/cpuset.c:update_sibling_cpumasks
  - kernel/cgroup/cpuset.c:update_sibling_cpumasks
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
```
In kernel/bpf/syscall.c (ffffffff812c91dd)
Location: include/linux/cgroup_refcnt.h:76
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_map_alloc_percpu
  - kernel/bpf/syscall.c:bpf_map_kzalloc
  - kernel/bpf/syscall.c:bpf_map_kmalloc_node
```
```
In kernel/bpf/helpers.c (ffffffff812f4402)
Location: include/linux/cgroup_refcnt.h:76
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_cgroup_release
```
```
In kernel/bpf/arraymap.c (ffffffff812fe1a5)
Location: include/linux/cgroup_refcnt.h:76
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr
```
```
In kernel/bpf/memalloc.c (ffffffff8131bdfb)
Location: include/linux/cgroup_refcnt.h:76
Inline: True
Inline callers:
  - kernel/bpf/memalloc.c:alloc_bulk
```
```
In kernel/bpf/cgroup_iter.c (ffffffff8132556e)
Location: include/linux/cgroup_refcnt.h:76
Inline: True
Inline callers:
  - kernel/bpf/cgroup_iter.c:bpf_iter_detach_cgroup
  - kernel/bpf/cgroup_iter.c:bpf_iter_detach_cgroup
  - kernel/bpf/cgroup_iter.c:cgroup_iter_seq_fini
  - kernel/bpf/cgroup_iter.c:cgroup_iter_seq_fini
```
```
In kernel/bpf/bpf_cgrp_storage.c (ffffffff813259b9)
Location: include/linux/cgroup_refcnt.h:76
Inline: True
Inline callers:
  - kernel/bpf/bpf_cgrp_storage.c:bpf_cgrp_storage_delete_elem
  - kernel/bpf/bpf_cgrp_storage.c:bpf_cgrp_storage_update_elem
  - kernel/bpf/bpf_cgrp_storage.c:bpf_cgrp_storage_lookup_elem
```
```
In kernel/bpf/cgroup.c (ffffffff8132a6ef)
Location: include/linux/cgroup_refcnt.h:76
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_query
  - kernel/bpf/cgroup.c:cgroup_bpf_link_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_release
  - kernel/bpf/cgroup.c:cgroup_bpf_release
```
```
In kernel/events/core.c (ffffffff8133f90d)
Location: include/linux/cgroup_refcnt.h:76
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_free_event
```
```
In mm/oom_kill.c (ffffffff81364be5)
Location: include/linux/cgroup_refcnt.h:76
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
```
```
In mm/page-writeback.c (ffffffff813694b4)
Location: include/linux/cgroup_refcnt.h:76
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited_flags
```
```
In mm/vmscan.c (ffffffff8138239f)
Location: include/linux/cgroup_refcnt.h:76
Inline: True
Inline callers:
  - mm/vmscan.c:run_cmd
  - mm/vmscan.c:lru_gen_del_mm
```
```
In mm/backing-dev.c (ffffffff81398078)
Location: include/linux/cgroup_refcnt.h:76
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_create
  - mm/backing-dev.c:cgwb_create
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/backing-dev.c:cgwb_release_workfn
```
```
In mm/mmap_lock.c (ffffffff813b3e2f)
Location: include/linux/cgroup_refcnt.h:76
Inline: True
Inline callers:
  - mm/mmap_lock.c:get_mm_memcg_path
```
```
In mm/hugetlb.c (ffffffff8140d2aa)
Location: include/linux/cgroup_refcnt.h:76
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:clear_vma_resv_huge_pages
  - mm/hugetlb.c:clear_vma_resv_huge_pages
  - mm/hugetlb.c:coalesce_file_region
  - mm/hugetlb.c:coalesce_file_region
  - mm/hugetlb.c:coalesce_file_region
  - mm/hugetlb.c:coalesce_file_region
```
```
In mm/slub.c (ffffffff81427e3c)
Location: include/linux/cgroup_refcnt.h:76
Inline: True
```
```
In mm/memcontrol.c (ffffffff8145b618)
Location: include/linux/cgroup_refcnt.h:76
Inline: True
Inline callers:
  - mm/memcontrol.c:obj_cgroup_may_zswap
  - mm/memcontrol.c:obj_cgroup_may_zswap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_sk_free
  - mm/memcontrol.c:mem_cgroup_sk_free
  - mm/memcontrol.c:uncharge_folio
  - mm/memcontrol.c:uncharge_folio
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:mem_cgroup_swapin_charge_folio
  - mm/memcontrol.c:mem_cgroup_swapin_charge_folio
  - mm/memcontrol.c:__mem_cgroup_charge
  - mm/memcontrol.c:__mem_cgroup_charge
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_event_remove
  - mm/memcontrol.c:memcg_event_remove
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:obj_cgroup_charge
  - mm/memcontrol.c:obj_cgroup_charge
  - mm/memcontrol.c:drain_obj_stock
  - mm/memcontrol.c:drain_obj_stock
  - mm/memcontrol.c:__memcg_kmem_charge_page
  - mm/memcontrol.c:__memcg_kmem_charge_page
  - mm/memcontrol.c:obj_cgroup_uncharge_pages
  - mm/memcontrol.c:obj_cgroup_uncharge_pages
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_oom_trylock
  - mm/memcontrol.c:mem_cgroup_oom_trylock
  - mm/memcontrol.c:mem_cgroup_oom_trylock
  - mm/memcontrol.c:mem_cgroup_oom_trylock
  - mm/memcontrol.c:mem_cgroup_scan_tasks
  - mm/memcontrol.c:mem_cgroup_scan_tasks
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
Direct callers:
  - mm/memcontrol.c:memcg_write_event_control
```
```
In mm/hugetlb_cgroup.c (ffffffff8145e200)
Location: include/linux/cgroup_refcnt.h:76
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_file_region
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_file_region
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_counter
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_counter
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_cgroup_rsvd
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_cgroup_rsvd
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
```
```
In fs/fs-writeback.c (ffffffff814c3656)
Location: include/linux/cgroup_refcnt.h:76
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/notify/group.c (ffffffff814dd3ee)
Location: include/linux/cgroup_refcnt.h:76
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_put_group
```
```
In block/blk-cgroup.c (ffffffff81762722)
Location: include/linux/cgroup_refcnt.h:76
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:__blkg_release
  - block/blk-cgroup.c:__blkg_release
```
```
In block/blk-cgroup-fc-appid.c (ffffffff817642e6)
Location: include/linux/cgroup_refcnt.h:76
Inline: True
Inline callers:
  - block/blk-cgroup-fc-appid.c:blkcg_set_fc_appid
  - block/blk-cgroup-fc-appid.c:blkcg_set_fc_appid
  - block/blk-cgroup-fc-appid.c:blkcg_set_fc_appid
  - block/blk-cgroup-fc-appid.c:blkcg_set_fc_appid
```
```
In drivers/block/loop.c (ffffffff81b2c988)
Location: include/linux/cgroup_refcnt.h:76
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_process_work
  - drivers/block/loop.c:loop_process_work
  - drivers/block/loop.c:loop_free_idle_workers
  - drivers/block/loop.c:loop_free_idle_workers
Direct callers:
  - drivers/block/loop.c:loop_queue_work
```
**Symbols:**

```
ffffffff81451c80-ffffffff81451cd9: css_put (STB_LOCAL)
ffffffff81b2ad70-ffffffff81b2adc9: css_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void css_put(struct cgroup_subsys_state *css);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81092dd0)
Location: include/linux/cgroup_refcnt.h:76
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_alloc_backing
```
```
In kernel/kthread.c (ffffffff81129b36)
Location: include/linux/cgroup_refcnt.h:76
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffffffff81226936)
Location: include/linux/cgroup_refcnt.h:76
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_free
  - kernel/cgroup/cgroup.c:cgroup_sk_free
  - kernel/cgroup/cgroup.c:cgroup_get_from_fd
  - kernel/cgroup/cgroup.c:cgroup_get_from_fd
  - kernel/cgroup/cgroup.c:cgroup_css_set_put_fork
  - kernel/cgroup/cgroup.c:cgroup_css_set_put_fork
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:cgroup_get_from_id
  - kernel/cgroup/cgroup.c:cgroup_get_from_id
  - kernel/cgroup/cgroup.c:css_killed_work_fn
  - kernel/cgroup/cgroup.c:css_killed_work_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:pressure_write
  - kernel/cgroup/cgroup.c:pressure_write
  - kernel/cgroup/cgroup.c:pressure_write
  - kernel/cgroup/cgroup.c:pressure_write
  - kernel/cgroup/cgroup.c:pressure_write
  - kernel/cgroup/cgroup.c:pressure_write
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - kernel/cgroup/cgroup.c:cgroup_do_get_tree
  - kernel/cgroup/cgroup.c:cgroup_do_get_tree
  - kernel/cgroup/cgroup.c:cgroup_kn_unlock
  - kernel/cgroup/cgroup.c:cgroup_kn_unlock
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff812289b6)
Location: include/linux/cgroup_refcnt.h:76
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use
  - kernel/cgroup/cgroup-v1.c:cgroupstats_build
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff8122b5fe)
Location: include/linux/cgroup_refcnt.h:76
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_change_state
  - kernel/cgroup/legacy_freezer.c:freezer_change_state
  - kernel/cgroup/legacy_freezer.c:freezer_read
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (ffffffff8122c991)
Location: include/linux/cgroup_refcnt.h:76
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy
```
```
In kernel/cgroup/cpuset.c (ffffffff8123507e)
Location: include/linux/cgroup_refcnt.h:76
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_nodemasks_hier
  - kernel/cgroup/cpuset.c:update_nodemasks_hier
  - kernel/cgroup/cpuset.c:update_sibling_cpumasks
  - kernel/cgroup/cpuset.c:update_sibling_cpumasks
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
```
In kernel/bpf/syscall.c (ffffffff812f08fd)
Location: include/linux/cgroup_refcnt.h:76
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_map_alloc_percpu
  - kernel/bpf/syscall.c:bpf_map_kvcalloc
  - kernel/bpf/syscall.c:bpf_map_kzalloc
  - kernel/bpf/syscall.c:bpf_map_kmalloc_node
```
```
In kernel/bpf/helpers.c (ffffffff81321465)
Location: include/linux/cgroup_refcnt.h:76
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_cgroup_release
```
```
In kernel/bpf/arraymap.c (ffffffff8132cdb5)
Location: include/linux/cgroup_refcnt.h:76
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr
```
```
In kernel/bpf/memalloc.c (ffffffff8134c4aa)
Location: include/linux/cgroup_refcnt.h:76
Inline: True
Inline callers:
  - kernel/bpf/memalloc.c:bpf_mem_cache_alloc_flags
  - kernel/bpf/memalloc.c:alloc_bulk
```
```
In kernel/bpf/cgroup_iter.c (ffffffff813557ae)
Location: include/linux/cgroup_refcnt.h:76
Inline: True
Inline callers:
  - kernel/bpf/cgroup_iter.c:bpf_iter_detach_cgroup
  - kernel/bpf/cgroup_iter.c:bpf_iter_detach_cgroup
  - kernel/bpf/cgroup_iter.c:cgroup_iter_seq_fini
  - kernel/bpf/cgroup_iter.c:cgroup_iter_seq_fini
```
```
In kernel/bpf/bpf_cgrp_storage.c (ffffffff81355c06)
Location: include/linux/cgroup_refcnt.h:76
Inline: True
Inline callers:
  - kernel/bpf/bpf_cgrp_storage.c:bpf_cgrp_storage_delete_elem
  - kernel/bpf/bpf_cgrp_storage.c:bpf_cgrp_storage_update_elem
  - kernel/bpf/bpf_cgrp_storage.c:bpf_cgrp_storage_lookup_elem
```
```
In kernel/bpf/cgroup.c (ffffffff8135a82f)
Location: include/linux/cgroup_refcnt.h:76
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_query
  - kernel/bpf/cgroup.c:cgroup_bpf_link_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_release
  - kernel/bpf/cgroup.c:cgroup_bpf_release
```
```
In kernel/events/core.c (ffffffff81370909)
Location: include/linux/cgroup_refcnt.h:76
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_free_event
```
```
In mm/oom_kill.c (ffffffff813970a5)
Location: include/linux/cgroup_refcnt.h:76
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
```
```
In mm/page-writeback.c (ffffffff8139b654)
Location: include/linux/cgroup_refcnt.h:76
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited_flags
```
```
In mm/vmscan.c (ffffffff813b3f1e)
Location: include/linux/cgroup_refcnt.h:76
Inline: True
Inline callers:
  - mm/vmscan.c:run_cmd
  - mm/vmscan.c:shrink_many
  - mm/vmscan.c:shrink_many
  - mm/vmscan.c:lru_gen_del_mm
```
```
In mm/backing-dev.c (ffffffff813caff8)
Location: include/linux/cgroup_refcnt.h:76
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_create
  - mm/backing-dev.c:cgwb_create
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/backing-dev.c:cgwb_release_workfn
```
```
In mm/mmap_lock.c (ffffffff813e877f)
Location: include/linux/cgroup_refcnt.h:76
Inline: True
Inline callers:
  - mm/mmap_lock.c:get_mm_memcg_path
```
```
In mm/hugetlb.c (ffffffff8144084a)
Location: include/linux/cgroup_refcnt.h:76
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:clear_vma_resv_huge_pages
  - mm/hugetlb.c:clear_vma_resv_huge_pages
  - mm/hugetlb.c:coalesce_file_region
  - mm/hugetlb.c:coalesce_file_region
  - mm/hugetlb.c:coalesce_file_region
  - mm/hugetlb.c:coalesce_file_region
```
```
In mm/slub.c (ffffffff8145c87c)
Location: include/linux/cgroup_refcnt.h:76
Inline: True
```
```
In mm/memcontrol.c (ffffffff81491288)
Location: include/linux/cgroup_refcnt.h:76
Inline: True
Inline callers:
  - mm/memcontrol.c:obj_cgroup_may_zswap
  - mm/memcontrol.c:obj_cgroup_may_zswap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_sk_free
  - mm/memcontrol.c:mem_cgroup_sk_free
  - mm/memcontrol.c:uncharge_folio
  - mm/memcontrol.c:uncharge_folio
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:mem_cgroup_swapin_charge_folio
  - mm/memcontrol.c:mem_cgroup_swapin_charge_folio
  - mm/memcontrol.c:__mem_cgroup_charge
  - mm/memcontrol.c:__mem_cgroup_charge
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_event_remove
  - mm/memcontrol.c:memcg_event_remove
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:obj_cgroup_charge
  - mm/memcontrol.c:obj_cgroup_charge
  - mm/memcontrol.c:drain_obj_stock
  - mm/memcontrol.c:drain_obj_stock
  - mm/memcontrol.c:__memcg_kmem_charge_page
  - mm/memcontrol.c:__memcg_kmem_charge_page
  - mm/memcontrol.c:obj_cgroup_uncharge_pages
  - mm/memcontrol.c:obj_cgroup_uncharge_pages
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_oom_trylock
  - mm/memcontrol.c:mem_cgroup_oom_trylock
  - mm/memcontrol.c:mem_cgroup_oom_trylock
  - mm/memcontrol.c:mem_cgroup_oom_trylock
  - mm/memcontrol.c:mem_cgroup_scan_tasks
  - mm/memcontrol.c:mem_cgroup_scan_tasks
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
Direct callers:
  - mm/memcontrol.c:memcg_write_event_control
```
```
In mm/hugetlb_cgroup.c (ffffffff81493ef0)
Location: include/linux/cgroup_refcnt.h:76
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_file_region
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_file_region
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_counter
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_counter
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_cgroup_rsvd
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_cgroup_rsvd
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
```
```
In fs/fs-writeback.c (ffffffff814f8a39)
Location: include/linux/cgroup_refcnt.h:76
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/notify/group.c (ffffffff81513c4e)
Location: include/linux/cgroup_refcnt.h:76
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_put_group
```
```
In block/blk-cgroup.c (ffffffff817a13ce)
Location: include/linux/cgroup_refcnt.h:76
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:__blkg_release
  - block/blk-cgroup.c:__blkg_release
```
```
In block/blk-cgroup-fc-appid.c (ffffffff817a3446)
Location: include/linux/cgroup_refcnt.h:76
Inline: True
Inline callers:
  - block/blk-cgroup-fc-appid.c:blkcg_set_fc_appid
  - block/blk-cgroup-fc-appid.c:blkcg_set_fc_appid
  - block/blk-cgroup-fc-appid.c:blkcg_set_fc_appid
  - block/blk-cgroup-fc-appid.c:blkcg_set_fc_appid
```
```
In drivers/block/loop.c (ffffffff81b7cbac)
Location: include/linux/cgroup_refcnt.h:76
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_process_work
  - drivers/block/loop.c:loop_process_work
  - drivers/block/loop.c:loop_free_idle_workers
  - drivers/block/loop.c:loop_free_idle_workers
Direct callers:
  - drivers/block/loop.c:loop_queue_work
```
**Symbols:**

```
ffffffff814871e0-ffffffff81487239: css_put (STB_LOCAL)
ffffffff81b7b060-ffffffff81b7b0b9: css_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void css_put(struct cgroup_subsys_state *css);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8109a210)
Location: include/linux/cgroup_refcnt.h:76
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_alloc_backing
```
```
In kernel/kthread.c (ffffffff81134176)
Location: include/linux/cgroup_refcnt.h:76
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffffffff8123e5c6)
Location: include/linux/cgroup_refcnt.h:76
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_free
  - kernel/cgroup/cgroup.c:cgroup_sk_free
  - kernel/cgroup/cgroup.c:cgroup_get_from_fd
  - kernel/cgroup/cgroup.c:cgroup_get_from_fd
  - kernel/cgroup/cgroup.c:cgroup_css_set_put_fork
  - kernel/cgroup/cgroup.c:cgroup_css_set_put_fork
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:cgroup_get_from_id
  - kernel/cgroup/cgroup.c:cgroup_get_from_id
  - kernel/cgroup/cgroup.c:css_killed_work_fn
  - kernel/cgroup/cgroup.c:css_killed_work_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:pressure_write
  - kernel/cgroup/cgroup.c:pressure_write
  - kernel/cgroup/cgroup.c:pressure_write
  - kernel/cgroup/cgroup.c:pressure_write
  - kernel/cgroup/cgroup.c:pressure_write
  - kernel/cgroup/cgroup.c:pressure_write
  - kernel/cgroup/cgroup.c:cpu_local_stat_show
  - kernel/cgroup/cgroup.c:cpu_local_stat_show
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - kernel/cgroup/cgroup.c:cgroup_do_get_tree
  - kernel/cgroup/cgroup.c:cgroup_do_get_tree
  - kernel/cgroup/cgroup.c:cgroup_kn_unlock
  - kernel/cgroup/cgroup.c:cgroup_kn_unlock
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff812407c6)
Location: include/linux/cgroup_refcnt.h:76
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use
  - kernel/cgroup/cgroup-v1.c:cgroupstats_build
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff812435ee)
Location: include/linux/cgroup_refcnt.h:76
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_change_state
  - kernel/cgroup/legacy_freezer.c:freezer_change_state
  - kernel/cgroup/legacy_freezer.c:freezer_read
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (ffffffff81244a51)
Location: include/linux/cgroup_refcnt.h:76
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy
```
```
In kernel/cgroup/cpuset.c (ffffffff8124eccc)
Location: include/linux/cgroup_refcnt.h:76
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_nodemasks_hier
  - kernel/cgroup/cpuset.c:update_nodemasks_hier
  - kernel/cgroup/cpuset.c:update_sibling_cpumasks
  - kernel/cgroup/cpuset.c:update_sibling_cpumasks
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
```
In kernel/bpf/syscall.c (ffffffff8130f6dd)
Location: include/linux/cgroup_refcnt.h:76
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_map_alloc_percpu
  - kernel/bpf/syscall.c:bpf_map_kvcalloc
  - kernel/bpf/syscall.c:bpf_map_kzalloc
  - kernel/bpf/syscall.c:bpf_map_kmalloc_node
```
```
In kernel/bpf/helpers.c (ffffffff81343b95)
Location: include/linux/cgroup_refcnt.h:76
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_cgroup_release_dtor
  - kernel/bpf/helpers.c:bpf_cgroup_release
```
```
In kernel/bpf/arraymap.c (ffffffff81351105)
Location: include/linux/cgroup_refcnt.h:76
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr
```
```
In kernel/bpf/memalloc.c (ffffffff81373a38)
Location: include/linux/cgroup_refcnt.h:76
Inline: True
Inline callers:
  - kernel/bpf/memalloc.c:bpf_mem_cache_alloc_flags
  - kernel/bpf/memalloc.c:alloc_bulk
```
```
In kernel/bpf/cgroup_iter.c (ffffffff8137e12e)
Location: include/linux/cgroup_refcnt.h:76
Inline: True
Inline callers:
  - kernel/bpf/cgroup_iter.c:bpf_iter_detach_cgroup
  - kernel/bpf/cgroup_iter.c:bpf_iter_detach_cgroup
  - kernel/bpf/cgroup_iter.c:cgroup_iter_seq_fini
  - kernel/bpf/cgroup_iter.c:cgroup_iter_seq_fini
```
```
In kernel/bpf/bpf_cgrp_storage.c (ffffffff8137e736)
Location: include/linux/cgroup_refcnt.h:76
Inline: True
Inline callers:
  - kernel/bpf/bpf_cgrp_storage.c:bpf_cgrp_storage_delete_elem
  - kernel/bpf/bpf_cgrp_storage.c:bpf_cgrp_storage_update_elem
  - kernel/bpf/bpf_cgrp_storage.c:bpf_cgrp_storage_lookup_elem
```
```
In kernel/bpf/cgroup.c (ffffffff8138341f)
Location: include/linux/cgroup_refcnt.h:76
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_query
  - kernel/bpf/cgroup.c:cgroup_bpf_link_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_release
  - kernel/bpf/cgroup.c:cgroup_bpf_release
```
```
In kernel/events/core.c (ffffffff81399c09)
Location: include/linux/cgroup_refcnt.h:76
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_free_event
```
```
In mm/oom_kill.c (ffffffff813c0e19)
Location: include/linux/cgroup_refcnt.h:76
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
```
```
In mm/page-writeback.c (ffffffff813c55c4)
Location: include/linux/cgroup_refcnt.h:76
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited_flags
```
```
In mm/vmscan.c (ffffffff813dd59e)
Location: include/linux/cgroup_refcnt.h:76
Inline: True
Inline callers:
  - mm/vmscan.c:run_cmd
  - mm/vmscan.c:shrink_many
  - mm/vmscan.c:shrink_many
  - mm/vmscan.c:lru_gen_del_mm
```
```
In mm/backing-dev.c (ffffffff813f5801)
Location: include/linux/cgroup_refcnt.h:76
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_create
  - mm/backing-dev.c:cgwb_create
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/backing-dev.c:cgwb_release_workfn
```
```
In mm/workingset.c (ffffffff8140c2b2)
Location: include/linux/cgroup_refcnt.h:76
Inline: True
Inline callers:
  - mm/workingset.c:workingset_test_recent
```
```
In mm/mmap_lock.c (ffffffff8141340f)
Location: include/linux/cgroup_refcnt.h:76
Inline: True
Inline callers:
  - mm/mmap_lock.c:get_mm_memcg_path
```
```
In mm/slub.c (ffffffff81454db3)
Location: include/linux/cgroup_refcnt.h:76
Inline: True
```
```
In mm/zswap.c (ffffffff81470a58)
Location: include/linux/cgroup_refcnt.h:76
Inline: True
Inline callers:
  - mm/zswap.c:zswap_store
  - mm/zswap.c:zswap_store
  - mm/zswap.c:zswap_store
  - mm/zswap.c:zswap_store
  - mm/zswap.c:shrink_worker
```
```
In mm/hugetlb.c (ffffffff8147a782)
Location: include/linux/cgroup_refcnt.h:76
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:alloc_hugetlb_folio
  - mm/hugetlb.c:alloc_hugetlb_folio
  - mm/hugetlb.c:alloc_hugetlb_folio
  - mm/hugetlb.c:alloc_hugetlb_folio
  - mm/hugetlb.c:alloc_hugetlb_folio
  - mm/hugetlb.c:alloc_hugetlb_folio
  - mm/hugetlb.c:alloc_hugetlb_folio
  - mm/hugetlb.c:alloc_hugetlb_folio
  - mm/hugetlb.c:clear_vma_resv_huge_pages
  - mm/hugetlb.c:clear_vma_resv_huge_pages
  - mm/hugetlb.c:coalesce_file_region
  - mm/hugetlb.c:coalesce_file_region
  - mm/hugetlb.c:coalesce_file_region
  - mm/hugetlb.c:coalesce_file_region
```
```
In mm/memcontrol.c (ffffffff814c0bf8)
Location: include/linux/cgroup_refcnt.h:76
Inline: True
Inline callers:
  - mm/memcontrol.c:obj_cgroup_may_zswap
  - mm/memcontrol.c:obj_cgroup_may_zswap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_sk_free
  - mm/memcontrol.c:mem_cgroup_sk_free
  - mm/memcontrol.c:uncharge_folio
  - mm/memcontrol.c:uncharge_folio
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:mem_cgroup_swapin_charge_folio
  - mm/memcontrol.c:mem_cgroup_swapin_charge_folio
  - mm/memcontrol.c:__mem_cgroup_charge
  - mm/memcontrol.c:__mem_cgroup_charge
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_event_remove
  - mm/memcontrol.c:memcg_event_remove
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:obj_cgroup_charge
  - mm/memcontrol.c:obj_cgroup_charge
  - mm/memcontrol.c:drain_obj_stock
  - mm/memcontrol.c:drain_obj_stock
  - mm/memcontrol.c:__memcg_kmem_charge_page
  - mm/memcontrol.c:__memcg_kmem_charge_page
  - mm/memcontrol.c:obj_cgroup_uncharge_pages
  - mm/memcontrol.c:obj_cgroup_uncharge_pages
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_oom_trylock
  - mm/memcontrol.c:mem_cgroup_oom_trylock
  - mm/memcontrol.c:mem_cgroup_oom_trylock
  - mm/memcontrol.c:mem_cgroup_oom_trylock
  - mm/memcontrol.c:mem_cgroup_scan_tasks
  - mm/memcontrol.c:mem_cgroup_scan_tasks
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
Direct callers:
  - mm/memcontrol.c:memcg_write_event_control
```
```
In mm/hugetlb_cgroup.c (ffffffff814c37d0)
Location: include/linux/cgroup_refcnt.h:76
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_file_region
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_file_region
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_counter
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_counter
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_cgroup_rsvd
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_cgroup_rsvd
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
```
```
In fs/fs-writeback.c (ffffffff8152d298)
Location: include/linux/cgroup_refcnt.h:76
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/notify/group.c (ffffffff8154811e)
Location: include/linux/cgroup_refcnt.h:76
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_put_group
```
```
In block/blk-cgroup.c (ffffffff817e4f1b)
Location: include/linux/cgroup_refcnt.h:76
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:__blkg_release
  - block/blk-cgroup.c:__blkg_release
```
```
In block/blk-cgroup-fc-appid.c (ffffffff817e6f96)
Location: include/linux/cgroup_refcnt.h:76
Inline: True
Inline callers:
  - block/blk-cgroup-fc-appid.c:blkcg_set_fc_appid
  - block/blk-cgroup-fc-appid.c:blkcg_set_fc_appid
  - block/blk-cgroup-fc-appid.c:blkcg_set_fc_appid
  - block/blk-cgroup-fc-appid.c:blkcg_set_fc_appid
```
```
In drivers/block/loop.c (ffffffff81bd0ada)
Location: include/linux/cgroup_refcnt.h:76
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_process_work
  - drivers/block/loop.c:loop_process_work
  - drivers/block/loop.c:loop_free_idle_workers
  - drivers/block/loop.c:loop_free_idle_workers
Direct callers:
  - drivers/block/loop.c:loop_queue_work
```
**Symbols:**

```
ffffffff814b6ae0-ffffffff814b6b39: css_put (STB_LOCAL)
ffffffff81bcee50-ffffffff81bceea9: css_put (STB_LOCAL)
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
In kernel/kthread.c (ffff80001012886c)
Location: include/linux/cgroup.h:395
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffff8000101d8e60)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_free
  - kernel/cgroup/cgroup.c:cgroup_get_from_fd
  - kernel/cgroup/cgroup.c:css_killed_work_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - kernel/cgroup/cgroup.c:cgroup_do_get_tree
  - kernel/cgroup/cgroup.c:cgroup_kn_unlock
```
```
In kernel/cgroup/cgroup-v1.c (ffff8000101dc798)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In kernel/cgroup/legacy_freezer.c (ffff8000101de76c)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (ffff8000101df98c)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy
```
```
In kernel/cgroup/cpuset.c (ffff8000101e49fc)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
```
In kernel/bpf/arraymap.c (ffff80001027b8b0)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr
```
```
In kernel/bpf/cgroup.c (ffff80001028fee4)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_query
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_release
```
```
In kernel/events/core.c (ffff8000102974d0)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_free_event
```
```
In mm/oom_kill.c (ffff8000102b7bc4)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
```
```
In mm/page-writeback.c (ffff8000102bc650)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/backing-dev.c (ffff8000102df4ec)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/backing-dev.c:cgwb_release_workfn
```
```
In mm/slab_common.c (ffff8000102e7764)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:destroy_memcg_params
```
```
In mm/slub.c (ffff8000103459c8)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (ffff80001036b0d8)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_sk_free
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_event_remove
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:__memcg_kmem_charge
  - mm/memcontrol.c:memcg_kmem_cache_create_func
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
```
```
In mm/hugetlb_cgroup.c (ffff80001036d688)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In fs/fs-writeback.c (ffff8000103ca9f8)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/buffer.c (ffff8000103d924c)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - fs/buffer.c:alloc_page_buffers
```
```
In fs/notify/group.c (ffff8000103e8f10)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_put_group
```
```
In block/blk-cgroup.c (ffff80001060db2c)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:__blkg_release
```
```
In drivers/block/loop.c (ffff8000109222ac)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_rw_aio_complete
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
In kernel/kthread.c (c037acac)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_associate_blkcg
```
```
In kernel/cgroup/cgroup.c (c041bcb0)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_free
  - kernel/cgroup/cgroup.c:cgroup_get_from_fd
  - kernel/cgroup/cgroup.c:css_killed_work_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - kernel/cgroup/cgroup.c:cgroup_do_get_tree
  - kernel/cgroup/cgroup.c:cgroup_kn_unlock
```
```
In kernel/cgroup/cgroup-v1.c (c041ea54)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In kernel/cgroup/legacy_freezer.c (c0420220)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (c04212d0)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy
```
```
In kernel/cgroup/cpuset.c (c042581c)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
```
In kernel/bpf/arraymap.c (c04ad310)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr
```
```
In kernel/bpf/cgroup.c (c04bf59c)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_query
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_release
```
```
In kernel/events/core.c (c04c7708)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_free_event
```
```
In mm/oom_kill.c (c04e47ec)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
```
```
In mm/page-writeback.c (c04e8cf8)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/backing-dev.c (c05043c0)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/backing-dev.c:cgwb_release_workfn
```
```
In mm/slab_common.c (c050b894)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:destroy_memcg_params
```
```
In mm/slub.c (c0549724)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (c055c7c4)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_sk_free
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_event_remove
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:__memcg_kmem_charge
  - mm/memcontrol.c:memcg_kmem_cache_create_func
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
```
```
In fs/fs-writeback.c (c05a6f70)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/buffer.c (c05b1fb4)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - fs/buffer.c:alloc_page_buffers
```
```
In fs/notify/group.c (c05c0630)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_put_group
```
```
In block/blk-cgroup.c (c07b8668)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:__blkg_release
```
```
In drivers/block/loop.c (c0a07bd8)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_rw_aio_complete
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
In kernel/kthread.c (c000000000173488)
Location: include/linux/cgroup.h:395
Inline: True
```
```
In kernel/cgroup/cgroup.c (c000000000246320)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_free
  - kernel/cgroup/cgroup.c:cgroup_get_from_fd
  - kernel/cgroup/cgroup.c:css_killed_work_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - kernel/cgroup/cgroup.c:cgroup_do_get_tree
  - kernel/cgroup/cgroup.c:cgroup_kn_unlock
```
```
In kernel/cgroup/cgroup-v1.c (c00000000024a4b4)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In kernel/cgroup/legacy_freezer.c (c00000000024c820)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (c00000000024e05c)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy
```
```
In kernel/cgroup/cpuset.c (c000000000255228)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
```
In kernel/bpf/arraymap.c (c000000000324aa0)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr
```
```
In kernel/bpf/cgroup.c (c00000000033cbd4)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_query
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_release
```
```
In kernel/events/core.c (c00000000034bc6c)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - kernel/events/core.c:_free_event
```
```
In mm/oom_kill.c (c00000000036f9f8)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
```
```
In mm/page-writeback.c (c00000000037493c)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/backing-dev.c (c00000000039f0cc)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/backing-dev.c:cgwb_release_workfn
```
```
In mm/slab_common.c (c0000000003a952c)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:destroy_memcg_params
```
```
In mm/slub.c (c000000000421f90)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (c00000000045a8ac)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_sk_free
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_event_remove
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:__memcg_kmem_charge
  - mm/memcontrol.c:memcg_kmem_cache_create_func
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
```
```
In mm/hugetlb_cgroup.c (c00000000045d7c8)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In fs/fs-writeback.c (c0000000004cc47c)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/buffer.c (c0000000004dd254)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - fs/buffer.c:alloc_page_buffers
```
```
In fs/notify/group.c (c0000000004efa68)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_put_group
```
```
In block/blk-cgroup.c (c0000000007aad78)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:__blkg_release
```
```
In drivers/block/loop.c (c0000000009c7794)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_rw_aio_complete
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
In kernel/kthread.c (ffffffe0000df51c)
Location: include/linux/cgroup.h:395
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffffffe000151e04)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_free
  - kernel/cgroup/cgroup.c:cgroup_get_from_fd
  - kernel/cgroup/cgroup.c:css_killed_work_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - kernel/cgroup/cgroup.c:cgroup_do_get_tree
  - kernel/cgroup/cgroup.c:cgroup_kn_unlock
```
```
In kernel/cgroup/cgroup-v1.c (ffffffe0001546ca)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In kernel/cgroup/legacy_freezer.c (ffffffe000155b76)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (ffffffe0001569dc)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy
```
```
In kernel/cgroup/cpuset.c (ffffffe00015abec)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
```
In kernel/bpf/arraymap.c (ffffffe0001b30a8)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr
```
```
In kernel/bpf/cgroup.c (ffffffe0001c2af8)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_query
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_release
```
```
In kernel/events/core.c (ffffffe0001c9712)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - kernel/events/core.c:_free_event
```
```
In mm/oom_kill.c (ffffffe0001dbe26)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
```
```
In mm/page-writeback.c (ffffffe0001df316)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/backing-dev.c (ffffffe0001f7220)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/backing-dev.c:cgwb_release_workfn
```
```
In mm/slab_common.c (ffffffe0001fd2ce)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:destroy_memcg_params
```
```
In mm/slub.c (ffffffe000238180)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (ffffffe000248840)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_sk_free
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_event_remove
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:__memcg_kmem_charge
  - mm/memcontrol.c:memcg_kmem_cache_create_func
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
```
```
In mm/hugetlb_cgroup.c (ffffffe00024a3bc)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In fs/fs-writeback.c (ffffffe000288b9a)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/buffer.c (ffffffe000291daa)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - fs/buffer.c:alloc_page_buffers
```
```
In fs/notify/group.c (ffffffe00029d9b8)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_final_destroy_group
```
```
In block/blk-cgroup.c (ffffffe000446302)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:__blkg_release
```
```
In drivers/block/loop.c (ffffffe0005a0fa6)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_rw_aio_complete
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
In kernel/kthread.c (ffffffff810c3324)
Location: include/linux/cgroup.h:395
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffffffff8115f57e)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_free
  - kernel/cgroup/cgroup.c:cgroup_get_from_fd
  - kernel/cgroup/cgroup.c:css_killed_work_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - kernel/cgroup/cgroup.c:cgroup_do_get_tree
  - kernel/cgroup/cgroup.c:cgroup_kn_unlock
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81161b5e)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff81162ecc)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (ffffffff81163ce8)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy
```
```
In kernel/cgroup/cpuset.c (ffffffff81169994)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
```
In kernel/bpf/arraymap.c (ffffffff811ef1f5)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr
```
```
In kernel/bpf/cgroup.c (ffffffff811fee18)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_query
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_release
```
```
In kernel/events/core.c (ffffffff81207ba6)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_free_event
```
```
In mm/oom_kill.c (ffffffff81222374)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
```
```
In mm/page-writeback.c (ffffffff81225dc0)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/backing-dev.c (ffffffff81242433)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/backing-dev.c:cgwb_release_workfn
```
```
In mm/slab_common.c (ffffffff81248d5c)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:destroy_memcg_params
```
```
In mm/slub.c (ffffffff8129c263)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (ffffffff812c07b1)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_sk_free
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_event_remove
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:__memcg_kmem_charge
  - mm/memcontrol.c:memcg_kmem_cache_create_func
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
```
```
In mm/hugetlb_cgroup.c (ffffffff812c2460)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In fs/fs-writeback.c (ffffffff8130d0d0)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/buffer.c (ffffffff81318bba)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - fs/buffer.c:alloc_page_buffers
```
```
In fs/notify/group.c (ffffffff81325709)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_put_group
```
```
In block/blk-cgroup.c (ffffffff815029bc)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:__blkg_release
```
```
In drivers/block/loop.c (ffffffff816f2120)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_rw_aio_complete
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
In kernel/kthread.c (ffffffff810b1b64)
Location: include/linux/cgroup.h:395
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffffffff8115280e)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_free
  - kernel/cgroup/cgroup.c:cgroup_get_from_fd
  - kernel/cgroup/cgroup.c:css_killed_work_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - kernel/cgroup/cgroup.c:cgroup_do_get_tree
  - kernel/cgroup/cgroup.c:cgroup_kn_unlock
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81154dbe)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff8115611c)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (ffffffff81156f38)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy
```
```
In kernel/cgroup/cpuset.c (ffffffff8115cb94)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
```
In kernel/bpf/arraymap.c (ffffffff811e1f85)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr
```
```
In kernel/bpf/cgroup.c (ffffffff811f1b68)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_query
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_release
```
```
In kernel/events/core.c (ffffffff811facd6)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_free_event
```
```
In mm/oom_kill.c (ffffffff81215524)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
```
```
In mm/page-writeback.c (ffffffff81218f60)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/backing-dev.c (ffffffff81235403)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/backing-dev.c:cgwb_release_workfn
```
```
In mm/slab_common.c (ffffffff8123bd06)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:destroy_memcg_params
```
```
In mm/slub.c (ffffffff8128de14)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (ffffffff812b1871)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_sk_free
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_event_remove
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:__memcg_kmem_charge
  - mm/memcontrol.c:memcg_kmem_cache_create_func
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
```
```
In mm/hugetlb_cgroup.c (ffffffff812b34b0)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In fs/fs-writeback.c (ffffffff812fdce0)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/buffer.c (ffffffff813097aa)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - fs/buffer.c:alloc_page_buffers
```
```
In fs/notify/group.c (ffffffff813162a9)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_put_group
```
```
In block/blk-cgroup.c (ffffffff814f316c)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:__blkg_release
```
```
In drivers/block/loop.c (ffffffff816cc220)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_rw_aio_complete
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
In kernel/kthread.c (ffffffff810c2874)
Location: include/linux/cgroup.h:395
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffffffff8115d34e)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_free
  - kernel/cgroup/cgroup.c:cgroup_get_from_fd
  - kernel/cgroup/cgroup.c:css_killed_work_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - kernel/cgroup/cgroup.c:cgroup_do_get_tree
  - kernel/cgroup/cgroup.c:cgroup_kn_unlock
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8115f92e)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff81160c9c)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (ffffffff81161ab8)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy
```
```
In kernel/cgroup/cpuset.c (ffffffff81167764)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
```
In kernel/bpf/arraymap.c (ffffffff811ecfc5)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr
```
```
In kernel/bpf/cgroup.c (ffffffff811fcbe8)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_query
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_release
```
```
In kernel/events/core.c (ffffffff81205976)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_free_event
```
```
In mm/oom_kill.c (ffffffff81220114)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
```
```
In mm/page-writeback.c (ffffffff81223b60)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/backing-dev.c (ffffffff812401d3)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/backing-dev.c:cgwb_release_workfn
```
```
In mm/slab_common.c (ffffffff81246afc)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:destroy_memcg_params
```
```
In mm/slub.c (ffffffff8129a073)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (ffffffff812be5c1)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_sk_free
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_event_remove
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:__memcg_kmem_charge
  - mm/memcontrol.c:memcg_kmem_cache_create_func
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
```
```
In mm/hugetlb_cgroup.c (ffffffff812c0270)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In fs/fs-writeback.c (ffffffff8130aec0)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/buffer.c (ffffffff8131668a)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - fs/buffer.c:alloc_page_buffers
```
```
In fs/notify/group.c (ffffffff813231d9)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_put_group
```
```
In block/blk-cgroup.c (ffffffff814fea4c)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:__blkg_release
```
```
In drivers/block/loop.c (ffffffff8171f800)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_rw_aio_complete
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
In kernel/kthread.c (ffffffff810cae64)
Location: include/linux/cgroup.h:395
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffffffff8116a55e)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_free
  - kernel/cgroup/cgroup.c:cgroup_get_from_fd
  - kernel/cgroup/cgroup.c:css_killed_work_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - kernel/cgroup/cgroup.c:cgroup_do_get_tree
  - kernel/cgroup/cgroup.c:cgroup_kn_unlock
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8116cbf9)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff8116e095)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (ffffffff8116ef0c)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy
```
```
In kernel/cgroup/cpuset.c (ffffffff81174dfd)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
```
In kernel/bpf/arraymap.c (ffffffff811fb465)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr
```
```
In kernel/bpf/cgroup.c (ffffffff8120b878)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_query
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_release
```
```
In kernel/events/core.c (ffffffff812147e6)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_free_event
```
```
In mm/oom_kill.c (ffffffff8122f222)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
```
```
In mm/page-writeback.c (ffffffff81232c8a)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/backing-dev.c (ffffffff8124f906)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/backing-dev.c:cgwb_release_workfn
```
```
In mm/slab_common.c (ffffffff81256308)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:destroy_memcg_params
```
```
In mm/slub.c (ffffffff812a9edc)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (ffffffff812cf011)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_sk_free
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_event_remove
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:__memcg_kmem_charge
  - mm/memcontrol.c:memcg_kmem_cache_create_func
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
```
```
In mm/hugetlb_cgroup.c (ffffffff812d0cc0)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In fs/fs-writeback.c (ffffffff8131c5f2)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/buffer.c (ffffffff8132847a)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - fs/buffer.c:alloc_page_buffers
```
```
In fs/notify/group.c (ffffffff81334f19)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_put_group
```
```
In block/blk-cgroup.c (ffffffff81517e64)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:__blkg_release
```
```
In drivers/block/loop.c (ffffffff8173ac30)
Location: include/linux/cgroup.h:395
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_rw_aio_complete
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
