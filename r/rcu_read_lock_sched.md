# Function: <code>rcu_read_lock_sched</code>

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
In kernel/workqueue.c (ffffffff810970d9)
Location: include/linux/rcupdate.h:973
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_congested
  - kernel/workqueue.c:wq_pool_ids_show
  - kernel/workqueue.c:show_workqueue_state
  - kernel/workqueue.c:freeze_workqueues_busy
```
```
In kernel/sched/core.c (ffffffff810ae786)
Location: include/linux/rcupdate.h:973
Inline: True
Inline callers:
  - kernel/sched/core.c:cpuset_cpumask_can_shrink
  - kernel/sched/core.c:task_can_attach
  - kernel/sched/core.c:sched_rt_handler
  - kernel/sched/core.c:sched_rt_handler
```
```
In kernel/cgroup.c (ffffffff811145fd)
Location: include/linux/rcupdate.h:973
Inline: True
Inline callers:
  - kernel/cgroup.c:kill_css
  - kernel/cgroup.c:cgroup_get
  - kernel/cgroup.c:init_and_link_css
  - kernel/cgroup.c:css_killed_work_fn
  - kernel/cgroup.c:cgroup_kn_unlock
  - kernel/cgroup.c:cgroup_kn_lock_live
  - kernel/cgroup.c:cgroup_release_root
  - kernel/cgroup.c:css_free_work_fn
  - kernel/cgroup.c:css_free_work_fn
  - kernel/cgroup.c:css_free_work_fn
  - kernel/cgroup.c:find_css_set
  - kernel/cgroup.c:cgroup_get_e_css
  - kernel/cgroup.c:cgroup_get_e_css
  - kernel/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup.c:cgroup_mount
  - kernel/cgroup.c:cgroup_mount
  - kernel/cgroup.c:css_tryget_online_from_dir
```
```
In kernel/cgroup_freezer.c (ffffffff81119ff8)
Location: include/linux/rcupdate.h:973
Inline: True
Inline callers:
  - kernel/cgroup_freezer.c:freezer_read
  - kernel/cgroup_freezer.c:freezer_read
  - kernel/cgroup_freezer.c:freezer_write
  - kernel/cgroup_freezer.c:freezer_write
```
```
In kernel/cpuset.c (ffffffff8111c7cb)
Location: include/linux/rcupdate.h:973
Inline: True
Inline callers:
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/cpuset.c:cpuset_hotplug_workfn
  - kernel/cpuset.c:cpuset_hotplug_workfn
  - kernel/cpuset.c:proc_cpuset_show
  - kernel/cpuset.c:proc_cpuset_show
```
```
In kernel/trace/trace_events.c (ffffffff8115dccd)
Location: include/linux/rcupdate.h:973
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:p_start
```
```
In kernel/events/core.c (ffffffff8117ed52)
Location: include/linux/rcupdate.h:973
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_free_event
```
```
In mm/page-writeback.c (ffffffff8119a54a)
Location: include/linux/rcupdate.h:973
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/backing-dev.c (ffffffff81208cbb)
Location: include/linux/rcupdate.h:973
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
```
```
In mm/memcontrol.c (ffffffff811fae01)
Location: include/linux/rcupdate.h:973
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mem_cgroup_from_mm
  - mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node
  - mm/memcontrol.c:memcg_kmem_cache_create_func
  - mm/memcontrol.c:memcg_event_remove
  - mm/memcontrol.c:cancel_charge
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:sock_release_memcg
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:task_in_mem_cgroup
  - mm/memcontrol.c:task_in_mem_cgroup
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:__memcg_kmem_get_cache
  - mm/memcontrol.c:__memcg_kmem_get_cache
  - mm/memcontrol.c:__memcg_kmem_put_cache
  - mm/memcontrol.c:__memcg_kmem_charge
  - mm/memcontrol.c:__memcg_kmem_uncharge
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:mem_cgroup_uncharge_swap
```
```
In mm/hugetlb_cgroup.c (ffffffff812012fe)
Location: include/linux/rcupdate.h:973
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In fs/inode.c (ffffffff81227b52)
Location: include/linux/rcupdate.h:973
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
```
```
In fs/file.c (ffffffff8122a8f3)
Location: include/linux/rcupdate.h:973
Inline: True
```
```
In fs/fs-writeback.c (ffffffff8123817e)
Location: include/linux/rcupdate.h:973
Inline: True
Inline callers:
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:wbc_detach_inode
```
```
In fs/block_dev.c (ffffffff812486e6)
Location: include/linux/rcupdate.h:973
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_put
```
```
In fs/aio.c (ffffffff8125b984)
Location: include/linux/rcupdate.h:973
Inline: True
Inline callers:
  - fs/aio.c:lookup_ioctx
  - fs/aio.c:free_ioctx_users
  - fs/aio.c:aio_complete
  - fs/aio.c:SyS_io_setup
  - fs/aio.c:SyS_io_destroy
  - fs/aio.c:do_io_submit
  - fs/aio.c:do_io_submit
  - fs/aio.c:do_io_submit
  - fs/aio.c:SyS_io_cancel
  - fs/aio.c:SyS_io_getevents
```
```
In block/bio.c (ffffffff813b0fd2)
Location: include/linux/rcupdate.h:973
Inline: True
Inline callers:
  - block/bio.c:bio_associate_current
  - block/bio.c:bio_associate_blkcg
  - block/bio.c:bio_disassociate_task
```
```
In block/blk-core.c (ffffffff813b99e8)
Location: include/linux/rcupdate.h:973
Inline: True
Inline callers:
  - block/blk-core.c:blk_queue_enter
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_account_io_start
```
```
In block/blk-merge.c (ffffffff813c194d)
Location: include/linux/rcupdate.h:973
Inline: True
Inline callers:
  - block/blk-merge.c:attempt_merge
```
```
In block/blk-mq.c (ffffffff813c4bd5)
Location: include/linux/rcupdate.h:973
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_map_request
```
```
In block/blk-cgroup.c (ffffffff813d7e60)
Location: include/linux/rcupdate.h:973
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:__blkg_release_rcu
```
```
In lib/bug.c (ffffffff813e8c24)
Location: include/linux/rcupdate.h:973
Inline: True
```
```
In lib/percpu-refcount.c (ffffffff813ff0b1)
Location: include/linux/rcupdate.h:973
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_call_confirm_rcu
  - lib/percpu-refcount.c:percpu_ref_kill_and_confirm
  - lib/percpu-refcount.c:percpu_ref_reinit
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
Location: include/linux/rcupdate.h:982
Inline: True
Inline callers:
  - arch/x86/mm/gup.c:gup_huge_pmd
  - arch/x86/mm/gup.c:gup_huge_pmd
  - arch/x86/mm/gup.c:gup_huge_pmd
  - arch/x86/mm/gup.c:gup_pte_range
  - arch/x86/mm/gup.c:gup_pte_range
  - arch/x86/mm/gup.c:gup_pte_range
```
```
In kernel/workqueue.c (ffffffff8109b029)
Location: include/linux/rcupdate.h:982
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_pool_ids_show
  - kernel/workqueue.c:freeze_workqueues_busy
  - kernel/workqueue.c:show_workqueue_state
  - kernel/workqueue.c:workqueue_congested
```
```
In kernel/sched/core.c (ffffffff810b3485)
Location: include/linux/rcupdate.h:982
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_rt_handler
  - kernel/sched/core.c:sched_rt_handler
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:task_can_attach
  - kernel/sched/core.c:cpuset_cpumask_can_shrink
```
```
In kernel/cgroup.c (ffffffff81121823)
Location: include/linux/rcupdate.h:982
Inline: True
Inline callers:
  - kernel/cgroup.c:cgroup_sk_free
  - kernel/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup.c:cgroup_get_from_fd
  - kernel/cgroup.c:css_tryget_online_from_dir
  - kernel/cgroup.c:kill_css
  - kernel/cgroup.c:css_killed_work_fn
  - kernel/cgroup.c:init_and_link_css
  - kernel/cgroup.c:css_free_work_fn
  - kernel/cgroup.c:css_free_work_fn
  - kernel/cgroup.c:css_free_work_fn
  - kernel/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup.c:cgroup_kill_sb
  - kernel/cgroup.c:cgroup_mount
  - kernel/cgroup.c:cgroup_mount
  - kernel/cgroup.c:cgroup_mount
  - kernel/cgroup.c:cgroup_mount
  - kernel/cgroup.c:cgroup_kn_lock_live
  - kernel/cgroup.c:cgroup_kn_unlock
  - kernel/cgroup.c:find_css_set
  - kernel/cgroup.c:cgroup_get
  - kernel/cgroup.c:cgroup_get_e_css
  - kernel/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup_freezer.c (ffffffff81121fce)
Location: include/linux/rcupdate.h:982
Inline: True
Inline callers:
  - kernel/cgroup_freezer.c:freezer_write
  - kernel/cgroup_freezer.c:freezer_write
  - kernel/cgroup_freezer.c:freezer_read
  - kernel/cgroup_freezer.c:freezer_read
```
```
In kernel/cpuset.c (ffffffff81125917)
Location: include/linux/rcupdate.h:982
Inline: True
Inline callers:
  - kernel/cpuset.c:proc_cpuset_show
  - kernel/cpuset.c:proc_cpuset_show
  - kernel/cpuset.c:cpuset_hotplug_workfn
  - kernel/cpuset.c:cpuset_hotplug_workfn
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/cpuset.c:cpuset_write_resmask
```
```
In kernel/trace/ftrace.c (ffffffff81148d5d)
Location: include/linux/rcupdate.h:982
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:fpid_start
```
```
In kernel/trace/trace_events.c (ffffffff8116983d)
Location: include/linux/rcupdate.h:982
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:p_start
```
```
In kernel/bpf/arraymap.c (ffffffff81187acd)
Location: include/linux/rcupdate.h:982
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr
```
```
In kernel/events/core.c (ffffffff81190957)
Location: include/linux/rcupdate.h:982
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_free_event
```
```
In kernel/memremap.c (ffffffff8119e13a)
Location: include/linux/rcupdate.h:982
Inline: True
Inline callers:
  - kernel/memremap.c:devm_memremap_pages_release
  - kernel/memremap.c:devm_memremap_pages_release
  - kernel/memremap.c:put_zone_device_page
  - kernel/memremap.c:get_zone_device_page
```
```
In mm/page-writeback.c (ffffffff811aee5a)
Location: include/linux/rcupdate.h:982
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/backing-dev.c (ffffffff811c85b3)
Location: include/linux/rcupdate.h:982
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/backing-dev.c:cgwb_release_workfn
```
```
In mm/gup.c (ffffffff811d4c43)
Location: include/linux/rcupdate.h:982
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/huge_memory.c (ffffffff812149a7)
Location: include/linux/rcupdate.h:982
Inline: True
Inline callers:
  - mm/huge_memory.c:follow_devmap_pmd
  - mm/huge_memory.c:follow_devmap_pmd
```
```
In mm/memcontrol.c (ffffffff81224528)
Location: include/linux/rcupdate.h:982
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_uncharge_skmem
  - mm/memcontrol.c:sock_release_memcg
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_event_remove
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:memcg_kmem_uncharge
  - mm/memcontrol.c:memcg_kmem_charge
  - mm/memcontrol.c:memcg_kmem_put_cache
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:memcg_kmem_cache_create_func
  - mm/memcontrol.c:cancel_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:task_in_mem_cgroup
  - mm/memcontrol.c:task_in_mem_cgroup
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:get_mem_cgroup_from_mm
  - mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node
```
```
In mm/hugetlb_cgroup.c (ffffffff81225ab7)
Location: include/linux/rcupdate.h:982
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In fs/inode.c (ffffffff81250282)
Location: include/linux/rcupdate.h:982
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
```
```
In fs/file.c (ffffffff81253053)
Location: include/linux/rcupdate.h:982
Inline: True
```
```
In fs/fs-writeback.c (ffffffff8126195e)
Location: include/linux/rcupdate.h:982
Inline: True
Inline callers:
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:wbc_detach_inode
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/block_dev.c (ffffffff8127111c)
Location: include/linux/rcupdate.h:982
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_put
```
```
In fs/aio.c (ffffffff812867e4)
Location: include/linux/rcupdate.h:982
Inline: True
Inline callers:
  - fs/aio.c:SyS_io_getevents
  - fs/aio.c:SyS_io_cancel
  - fs/aio.c:do_io_submit
  - fs/aio.c:do_io_submit
  - fs/aio.c:do_io_submit
  - fs/aio.c:SyS_io_destroy
  - fs/aio.c:SyS_io_setup
  - fs/aio.c:aio_complete
  - fs/aio.c:lookup_ioctx
  - fs/aio.c:free_ioctx_users
```
```
In block/bio.c (ffffffff813f543d)
Location: include/linux/rcupdate.h:982
Inline: True
Inline callers:
  - block/bio.c:bio_disassociate_task
  - block/bio.c:bio_associate_current
```
```
In block/blk-core.c (ffffffff813fe759)
Location: include/linux/rcupdate.h:982
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-merge.c (ffffffff81405883)
Location: include/linux/rcupdate.h:982
Inline: True
```
```
In block/blk-mq.c (ffffffff81408db0)
Location: include/linux/rcupdate.h:982
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_map_request
  - block/blk-mq.c:blk_mq_timeout_work
```
```
In block/blk-cgroup.c (ffffffff8141e0d6)
Location: include/linux/rcupdate.h:982
Inline: True
Inline callers:
  - block/blk-cgroup.c:__blkg_release_rcu
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_create
```
```
In lib/bug.c (ffffffff8142ee94)
Location: include/linux/rcupdate.h:982
Inline: True
```
```
In lib/percpu-refcount.c (ffffffff81446a9e)
Location: include/linux/rcupdate.h:982
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_reinit
  - lib/percpu-refcount.c:percpu_ref_kill_and_confirm
  - lib/percpu-refcount.c:percpu_ref_call_confirm_rcu
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
Location: include/linux/rcupdate.h:987
Inline: True
Inline callers:
  - arch/x86/mm/gup.c:gup_huge_pmd
  - arch/x86/mm/gup.c:gup_huge_pmd
  - arch/x86/mm/gup.c:gup_huge_pmd
  - arch/x86/mm/gup.c:gup_pte_range
  - arch/x86/mm/gup.c:gup_pte_range
  - arch/x86/mm/gup.c:gup_pte_range
```
```
In kernel/workqueue.c (ffffffff8109fdf9)
Location: include/linux/rcupdate.h:987
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_pool_ids_show
  - kernel/workqueue.c:freeze_workqueues_busy
  - kernel/workqueue.c:show_workqueue_state
  - kernel/workqueue.c:workqueue_congested
```
```
In kernel/sched/core.c (ffffffff810b9ad7)
Location: include/linux/rcupdate.h:987
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_rt_handler
  - kernel/sched/core.c:sched_rt_handler
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:task_can_attach
  - kernel/sched/core.c:cpuset_cpumask_can_shrink
```
```
In kernel/cgroup.c (ffffffff81129dc3)
Location: include/linux/rcupdate.h:987
Inline: True
Inline callers:
  - kernel/cgroup.c:cgroup_sk_free
  - kernel/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup.c:cgroup_get_from_fd
  - kernel/cgroup.c:css_tryget_online_from_dir
  - kernel/cgroup.c:kill_css
  - kernel/cgroup.c:css_killed_work_fn
  - kernel/cgroup.c:init_and_link_css
  - kernel/cgroup.c:css_free_work_fn
  - kernel/cgroup.c:css_free_work_fn
  - kernel/cgroup.c:css_free_work_fn
  - kernel/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup.c:cgroup_kill_sb
  - kernel/cgroup.c:cgroup_mount
  - kernel/cgroup.c:cgroup_mount
  - kernel/cgroup.c:cgroup_mount
  - kernel/cgroup.c:cgroup_mount
  - kernel/cgroup.c:cgroup_kn_lock_live
  - kernel/cgroup.c:cgroup_kn_unlock
  - kernel/cgroup.c:find_css_set
  - kernel/cgroup.c:cgroup_get
  - kernel/cgroup.c:cgroup_get_e_css
  - kernel/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup_freezer.c (ffffffff8112a5fe)
Location: include/linux/rcupdate.h:987
Inline: True
Inline callers:
  - kernel/cgroup_freezer.c:freezer_write
  - kernel/cgroup_freezer.c:freezer_write
  - kernel/cgroup_freezer.c:freezer_read
  - kernel/cgroup_freezer.c:freezer_read
```
```
In kernel/cpuset.c (ffffffff8112f312)
Location: include/linux/rcupdate.h:987
Inline: True
Inline callers:
  - kernel/cpuset.c:proc_cpuset_show
  - kernel/cpuset.c:proc_cpuset_show
  - kernel/cpuset.c:cpuset_hotplug_workfn
  - kernel/cpuset.c:cpuset_hotplug_workfn
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/cpuset.c:cpuset_write_resmask
```
```
In kernel/trace/ftrace.c (ffffffff81152c0a)
Location: include/linux/rcupdate.h:987
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:fpid_start
```
```
In kernel/trace/trace_events.c (ffffffff81174cfa)
Location: include/linux/rcupdate.h:987
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:p_start
```
```
In kernel/bpf/syscall.c (ffffffff8118da7f)
Location: include/linux/rcupdate.h:987
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:SyS_bpf
```
```
In kernel/bpf/arraymap.c (ffffffff8119598d)
Location: include/linux/rcupdate.h:987
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr
```
```
In kernel/events/core.c (ffffffff8119f825)
Location: include/linux/rcupdate.h:987
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_free_event
```
```
In kernel/memremap.c (ffffffff811adb5a)
Location: include/linux/rcupdate.h:987
Inline: True
Inline callers:
  - kernel/memremap.c:devm_memremap_pages_release
  - kernel/memremap.c:devm_memremap_pages_release
  - kernel/memremap.c:put_zone_device_page
  - kernel/memremap.c:get_zone_device_page
```
```
In mm/page-writeback.c (ffffffff811bf50a)
Location: include/linux/rcupdate.h:987
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/backing-dev.c (ffffffff811d86e3)
Location: include/linux/rcupdate.h:987
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/backing-dev.c:cgwb_release_workfn
```
```
In mm/gup.c (ffffffff811e4c6f)
Location: include/linux/rcupdate.h:987
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/huge_memory.c (ffffffff81226f36)
Location: include/linux/rcupdate.h:987
Inline: True
Inline callers:
  - mm/huge_memory.c:follow_devmap_pmd
  - mm/huge_memory.c:follow_devmap_pmd
```
```
In mm/memcontrol.c (ffffffff81236af8)
Location: include/linux/rcupdate.h:987
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_uncharge_skmem
  - mm/memcontrol.c:mem_cgroup_sk_free
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_event_remove
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:memcg_kmem_uncharge
  - mm/memcontrol.c:memcg_kmem_charge
  - mm/memcontrol.c:memcg_kmem_put_cache
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:memcg_kmem_cache_create_func
  - mm/memcontrol.c:cancel_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:task_in_mem_cgroup
  - mm/memcontrol.c:task_in_mem_cgroup
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:get_mem_cgroup_from_mm
  - mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node
```
```
In mm/hugetlb_cgroup.c (ffffffff81238097)
Location: include/linux/rcupdate.h:987
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In fs/inode.c (ffffffff81263322)
Location: include/linux/rcupdate.h:987
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
```
```
In fs/file.c (ffffffff812662b0)
Location: include/linux/rcupdate.h:987
Inline: True
```
```
In fs/fs-writeback.c (ffffffff81274e5e)
Location: include/linux/rcupdate.h:987
Inline: True
Inline callers:
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:wbc_detach_inode
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/block_dev.c (ffffffff81284a89)
Location: include/linux/rcupdate.h:987
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_put
```
```
In fs/aio.c (ffffffff8129a750)
Location: include/linux/rcupdate.h:987
Inline: True
Inline callers:
  - fs/aio.c:compat_SyS_io_getevents
  - fs/aio.c:SyS_io_cancel
  - fs/aio.c:do_io_submit
  - fs/aio.c:do_io_submit
  - fs/aio.c:do_io_submit
  - fs/aio.c:SyS_io_destroy
  - fs/aio.c:compat_SyS_io_setup
  - fs/aio.c:SyS_io_setup
  - fs/aio.c:aio_complete
  - fs/aio.c:lookup_ioctx
  - fs/aio.c:free_ioctx_users
```
```
In block/bio.c (ffffffff8140ee5d)
Location: include/linux/rcupdate.h:987
Inline: True
Inline callers:
  - block/bio.c:bio_disassociate_task
  - block/bio.c:bio_associate_current
```
```
In block/blk-core.c (ffffffff8141814b)
Location: include/linux/rcupdate.h:987
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-merge.c (ffffffff8141faf8)
Location: include/linux/rcupdate.h:987
Inline: True
```
```
In block/blk-mq.c (ffffffff814221af)
Location: include/linux/rcupdate.h:987
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_map_request
  - block/blk-mq.c:blk_mq_timeout_work
```
```
In block/blk-cgroup.c (ffffffff81439696)
Location: include/linux/rcupdate.h:987
Inline: True
Inline callers:
  - block/blk-cgroup.c:__blkg_release_rcu
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_create
```
```
In lib/bug.c (ffffffff8144b004)
Location: include/linux/rcupdate.h:987
Inline: True
```
```
In lib/percpu-refcount.c (ffffffff8146515f)
Location: include/linux/rcupdate.h:987
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_reinit
  - lib/percpu-refcount.c:percpu_ref_kill_and_confirm
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
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
In kernel/workqueue.c (ffffffff8109d629)
Location: include/linux/rcupdate.h:721
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_pool_ids_show
  - kernel/workqueue.c:freeze_workqueues_busy
  - kernel/workqueue.c:show_workqueue_state
  - kernel/workqueue.c:workqueue_congested
```
```
In kernel/sched/deadline.c (ffffffff810c9336)
Location: include/linux/rcupdate.h:721
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_cpu_busy
  - kernel/sched/deadline.c:dl_cpuset_cpumask_can_shrink
  - kernel/sched/deadline.c:dl_task_can_attach
  - kernel/sched/deadline.c:sched_dl_do_global
  - kernel/sched/deadline.c:sched_dl_global_validate
```
```
In kernel/cgroup/cgroup.c (ffffffff81128ba3)
Location: include/linux/rcupdate.h:721
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_free
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_get_from_fd
  - kernel/cgroup/cgroup.c:css_tryget_online_from_dir
  - kernel/cgroup/cgroup.c:kill_css
  - kernel/cgroup/cgroup.c:css_killed_work_fn
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:css_free_work_fn
  - kernel/cgroup/cgroup.c:css_free_work_fn
  - kernel/cgroup/cgroup.c:css_free_work_fn
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - kernel/cgroup/cgroup.c:cgroup_do_mount
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
  - kernel/cgroup/cgroup.c:cgroup_kn_unlock
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/cgroup.c:cgroup_get_live
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8112aa47)
Location: include/linux/rcupdate.h:721
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_mount
  - kernel/cgroup/cgroup-v1.c:cgroup1_mount
  - kernel/cgroup/cgroup-v1.c:cgroup1_mount
```
```
In kernel/cgroup/freezer.c (ffffffff8112b366)
Location: include/linux/rcupdate.h:721
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:freezer_write
  - kernel/cgroup/freezer.c:freezer_write
  - kernel/cgroup/freezer.c:freezer_read
  - kernel/cgroup/freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (ffffffff8112bf7f)
Location: include/linux/rcupdate.h:721
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
  - kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy
```
```
In kernel/cgroup/cpuset.c (ffffffff8113096b)
Location: include/linux/rcupdate.h:721
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In kernel/trace/ftrace.c (ffffffff8115527a)
Location: include/linux/rcupdate.h:721
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:fpid_start
```
```
In kernel/trace/trace_events.c (ffffffff8117794a)
Location: include/linux/rcupdate.h:721
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:p_start
```
```
In kernel/bpf/syscall.c (ffffffff81192c9c)
Location: include/linux/rcupdate.h:721
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:SyS_bpf
```
```
In kernel/bpf/arraymap.c (ffffffff8119cd9d)
Location: include/linux/rcupdate.h:721
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr
```
```
In kernel/events/core.c (ffffffff811a94ed)
Location: include/linux/rcupdate.h:721
Inline: True
Inline callers:
  - kernel/events/core.c:_free_event
```
```
In kernel/memremap.c (ffffffff811b4ec1)
Location: include/linux/rcupdate.h:721
Inline: True
Inline callers:
  - kernel/memremap.c:devm_memremap_pages
  - kernel/memremap.c:devm_memremap_pages_release
  - kernel/memremap.c:devm_memremap_pages_release
```
```
In mm/page-writeback.c (ffffffff811c72c2)
Location: include/linux/rcupdate.h:721
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/swap.c (ffffffff811cba42)
Location: include/linux/rcupdate.h:721
Inline: True
```
```
In mm/backing-dev.c (ffffffff811e194b)
Location: include/linux/rcupdate.h:721
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/backing-dev.c:cgwb_release_workfn
```
```
In mm/slab_common.c (ffffffff811e77ca)
Location: include/linux/rcupdate.h:721
Inline: True
Inline callers:
  - mm/slab_common.c:slab_deactivate_memcg_cache_rcu_sched
  - mm/slab_common.c:kmemcg_deactivate_workfn
```
```
In mm/gup.c (ffffffff811f0bd8)
Location: include/linux/rcupdate.h:721
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages_fast
  - mm/gup.c:__get_user_pages_fast
  - mm/gup.c:__get_user_pages_fast
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/huge_memory.c (ffffffff812332a5)
Location: include/linux/rcupdate.h:721
Inline: True
Inline callers:
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:follow_devmap_pmd
  - mm/huge_memory.c:follow_devmap_pmd
```
```
In mm/memcontrol.c (ffffffff81242577)
Location: include/linux/rcupdate.h:721
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_uncharge_skmem
  - mm/memcontrol.c:mem_cgroup_sk_free
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_event_remove
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:memcg_kmem_uncharge
  - mm/memcontrol.c:memcg_kmem_charge
  - mm/memcontrol.c:memcg_kmem_put_cache
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:memcg_kmem_cache_create_func
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:task_in_mem_cgroup
  - mm/memcontrol.c:task_in_mem_cgroup
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:get_mem_cgroup_from_mm
  - mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node
```
```
In mm/hugetlb_cgroup.c (ffffffff81243d04)
Location: include/linux/rcupdate.h:721
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In fs/inode.c (ffffffff81270b4f)
Location: include/linux/rcupdate.h:721
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
```
```
In fs/file.c (ffffffff81273a90)
Location: include/linux/rcupdate.h:721
Inline: True
```
```
In fs/fs-writeback.c (ffffffff812823a6)
Location: include/linux/rcupdate.h:721
Inline: True
Inline callers:
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:wbc_detach_inode
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/block_dev.c (ffffffff812927af)
Location: include/linux/rcupdate.h:721
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_evict_inode
```
```
In fs/aio.c (ffffffff812a84a0)
Location: include/linux/rcupdate.h:721
Inline: True
Inline callers:
  - fs/aio.c:compat_SyS_io_getevents
  - fs/aio.c:SyS_io_cancel
  - fs/aio.c:do_io_submit
  - fs/aio.c:do_io_submit
  - fs/aio.c:do_io_submit
  - fs/aio.c:SyS_io_destroy
  - fs/aio.c:compat_SyS_io_setup
  - fs/aio.c:SyS_io_setup
  - fs/aio.c:aio_complete
  - fs/aio.c:lookup_ioctx
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:free_ioctx_users
```
```
In block/bio.c (ffffffff8141c97d)
Location: include/linux/rcupdate.h:721
Inline: True
Inline callers:
  - block/bio.c:bio_disassociate_task
  - block/bio.c:bio_associate_current
```
```
In block/blk-core.c (ffffffff81425fef)
Location: include/linux/rcupdate.h:721
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-merge.c (ffffffff8142d991)
Location: include/linux/rcupdate.h:721
Inline: True
Inline callers:
  - block/blk-merge.c:attempt_merge
```
```
In block/blk-mq.c (ffffffff8142fcc3)
Location: include/linux/rcupdate.h:721
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_timeout_work
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/blk-cgroup.c (ffffffff81446eb0)
Location: include/linux/rcupdate.h:721
Inline: True
Inline callers:
  - block/blk-cgroup.c:__blkg_release_rcu
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_create
```
```
In lib/percpu-refcount.c (ffffffff8146a288)
Location: include/linux/rcupdate.h:721
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_reinit
  - lib/percpu-refcount.c:percpu_ref_kill_and_confirm
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In drivers/md/md.c (ffffffff8173fa2d)
Location: include/linux/rcupdate.h:721
Inline: True
Inline callers:
  - drivers/md/md.c:md_write_end
```
```
In lib/bug.c (ffffffff818eb274)
Location: include/linux/rcupdate.h:721
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
In kernel/workqueue.c (ffffffff810a3cc9)
Location: include/linux/rcupdate.h:743
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_pool_ids_show
  - kernel/workqueue.c:freeze_workqueues_busy
  - kernel/workqueue.c:show_workqueue_state
  - kernel/workqueue.c:workqueue_congested
```
```
In kernel/kthread.c (ffffffff810ac964)
Location: include/linux/rcupdate.h:743
Inline: True
```
```
In kernel/sched/deadline.c (ffffffff810d0a26)
Location: include/linux/rcupdate.h:743
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_cpu_busy
  - kernel/sched/deadline.c:dl_cpuset_cpumask_can_shrink
  - kernel/sched/deadline.c:dl_task_can_attach
  - kernel/sched/deadline.c:sched_dl_do_global
  - kernel/sched/deadline.c:sched_dl_global_validate
```
```
In kernel/cgroup/cgroup.c (ffffffff811351d7)
Location: include/linux/rcupdate.h:743
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_free
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_get_from_fd
  - kernel/cgroup/cgroup.c:css_tryget_online_from_dir
  - kernel/cgroup/cgroup.c:kill_css
  - kernel/cgroup/cgroup.c:css_killed_work_fn
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:css_free_work_fn
  - kernel/cgroup/cgroup.c:css_free_work_fn
  - kernel/cgroup/cgroup.c:css_free_work_fn
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - kernel/cgroup/cgroup.c:cgroup_do_mount
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
  - kernel/cgroup/cgroup.c:cgroup_kn_unlock
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/cgroup.c:cgroup_get_live
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff811377d7)
Location: include/linux/rcupdate.h:743
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_mount
  - kernel/cgroup/cgroup-v1.c:cgroup1_mount
  - kernel/cgroup/cgroup-v1.c:cgroup1_mount
```
```
In kernel/cgroup/freezer.c (ffffffff81138166)
Location: include/linux/rcupdate.h:743
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:freezer_write
  - kernel/cgroup/freezer.c:freezer_write
  - kernel/cgroup/freezer.c:freezer_read
  - kernel/cgroup/freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (ffffffff81138d8f)
Location: include/linux/rcupdate.h:743
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
  - kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy
```
```
In kernel/cgroup/cpuset.c (ffffffff8113d8ab)
Location: include/linux/rcupdate.h:743
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In kernel/trace/ftrace.c (ffffffff81161b1a)
Location: include/linux/rcupdate.h:743
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:fpid_start
```
```
In kernel/trace/trace_events.c (ffffffff811850da)
Location: include/linux/rcupdate.h:743
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:p_start
```
```
In kernel/bpf/syscall.c (ffffffff8119ffae)
Location: include/linux/rcupdate.h:743
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:SyS_bpf
```
```
In kernel/bpf/arraymap.c (ffffffff811ac851)
Location: include/linux/rcupdate.h:743
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr
```
```
In kernel/events/core.c (ffffffff811bcd35)
Location: include/linux/rcupdate.h:743
Inline: True
Inline callers:
  - kernel/events/core.c:_free_event
```
```
In kernel/memremap.c (ffffffff811c91ff)
Location: include/linux/rcupdate.h:743
Inline: True
Inline callers:
  - kernel/memremap.c:devm_memremap_pages
  - kernel/memremap.c:devm_memremap_pages_release
  - kernel/memremap.c:devm_memremap_pages_release
```
```
In mm/page-writeback.c (ffffffff811dc0d2)
Location: include/linux/rcupdate.h:743
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/swap.c (ffffffff811e0440)
Location: include/linux/rcupdate.h:743
Inline: True
```
```
In mm/backing-dev.c (ffffffff811f799b)
Location: include/linux/rcupdate.h:743
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/backing-dev.c:cgwb_release_workfn
```
```
In mm/slab_common.c (ffffffff811fda0a)
Location: include/linux/rcupdate.h:743
Inline: True
Inline callers:
  - mm/slab_common.c:slab_deactivate_memcg_cache_rcu_sched
  - mm/slab_common.c:kmemcg_deactivate_workfn
```
```
In mm/gup.c (ffffffff81205757)
Location: include/linux/rcupdate.h:743
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/huge_memory.c (ffffffff81250be1)
Location: include/linux/rcupdate.h:743
Inline: True
Inline callers:
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:follow_devmap_pmd
  - mm/huge_memory.c:follow_devmap_pmd
```
```
In mm/memcontrol.c (ffffffff81262376)
Location: include/linux/rcupdate.h:743
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_sk_free
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_event_remove
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:memcg_kmem_uncharge
  - mm/memcontrol.c:memcg_kmem_charge
  - mm/memcontrol.c:memcg_kmem_put_cache
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:memcg_kmem_cache_create_func
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:task_in_mem_cgroup
  - mm/memcontrol.c:task_in_mem_cgroup
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:get_mem_cgroup_from_mm
  - mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node
```
```
In mm/hugetlb_cgroup.c (ffffffff81263b54)
Location: include/linux/rcupdate.h:743
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In mm/hmm.c (ffffffff8126e290)
Location: include/linux/rcupdate.h:743
Inline: True
Inline callers:
  - mm/hmm.c:hmm_devmem_release
  - mm/hmm.c:hmm_devmem_release
```
```
In fs/inode.c (ffffffff8129347f)
Location: include/linux/rcupdate.h:743
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
```
```
In fs/file.c (ffffffff812963a2)
Location: include/linux/rcupdate.h:743
Inline: True
```
```
In fs/fs-writeback.c (ffffffff812a4f16)
Location: include/linux/rcupdate.h:743
Inline: True
Inline callers:
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:wbc_detach_inode
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/block_dev.c (ffffffff812b55bf)
Location: include/linux/rcupdate.h:743
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_evict_inode
```
```
In fs/aio.c (ffffffff812c9fa1)
Location: include/linux/rcupdate.h:743
Inline: True
Inline callers:
  - fs/aio.c:do_io_getevents
  - fs/aio.c:SyS_io_cancel
  - fs/aio.c:do_io_submit
  - fs/aio.c:do_io_submit
  - fs/aio.c:do_io_submit
  - fs/aio.c:SyS_io_destroy
  - fs/aio.c:compat_SyS_io_setup
  - fs/aio.c:SyS_io_setup
  - fs/aio.c:aio_complete
  - fs/aio.c:lookup_ioctx
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:free_ioctx_users
```
```
In block/bio.c (ffffffff8144753d)
Location: include/linux/rcupdate.h:743
Inline: True
Inline callers:
  - block/bio.c:bio_disassociate_task
```
```
In block/blk-core.c (ffffffff8145145b)
Location: include/linux/rcupdate.h:743
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:direct_make_request
  - block/blk-core.c:blk_queue_bio
  - block/blk-core.c:blk_queue_bio
  - block/blk-core.c:__blk_put_request
  - block/blk-core.c:blk_get_request_flags
  - block/blk-core.c:blk_queue_enter
  - block/blk-core.c:blk_queue_enter
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-merge.c (ffffffff81458bc0)
Location: include/linux/rcupdate.h:743
Inline: True
Inline callers:
  - block/blk-merge.c:attempt_merge
```
```
In block/blk-mq.c (ffffffff8145b603)
Location: include/linux/rcupdate.h:743
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_timeout_work
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/blk-cgroup.c (ffffffff81473a90)
Location: include/linux/rcupdate.h:743
Inline: True
Inline callers:
  - block/blk-cgroup.c:__blkg_release_rcu
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_create
```
```
In lib/percpu-refcount.c (ffffffff81496578)
Location: include/linux/rcupdate.h:743
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_reinit
  - lib/percpu-refcount.c:percpu_ref_kill_and_confirm
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In drivers/block/loop.c (ffffffff8166fc8f)
Location: include/linux/rcupdate.h:743
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_rq
  - drivers/block/loop.c:lo_rw_aio_complete
```
```
In drivers/md/md.c (ffffffff817b1a4d)
Location: include/linux/rcupdate.h:743
Inline: True
Inline callers:
  - drivers/md/md.c:md_write_end
```
```
In lib/bug.c (ffffffff819714a4)
Location: include/linux/rcupdate.h:743
Inline: True
Inline callers:
  - lib/bug.c:generic_bug_clear_once
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
In kernel/workqueue.c (ffffffff810aa7b9)
Location: include/linux/rcupdate.h:741
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_pool_ids_show
  - kernel/workqueue.c:freeze_workqueues_busy
  - kernel/workqueue.c:show_workqueue_state
  - kernel/workqueue.c:workqueue_congested
```
```
In kernel/kthread.c (ffffffff810b397b)
Location: include/linux/rcupdate.h:741
Inline: True
```
```
In kernel/sched/deadline.c (ffffffff810d8f35)
Location: include/linux/rcupdate.h:741
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_cpu_busy
  - kernel/sched/deadline.c:dl_cpuset_cpumask_can_shrink
  - kernel/sched/deadline.c:dl_task_can_attach
  - kernel/sched/deadline.c:sched_dl_do_global
  - kernel/sched/deadline.c:sched_dl_global_validate
```
```
In kernel/cgroup/cgroup.c (ffffffff811438f2)
Location: include/linux/rcupdate.h:741
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_free
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_get_from_fd
  - kernel/cgroup/cgroup.c:css_tryget_online_from_dir
  - kernel/cgroup/cgroup.c:kill_css
  - kernel/cgroup/cgroup.c:css_killed_work_fn
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - kernel/cgroup/cgroup.c:cgroup_do_mount
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
  - kernel/cgroup/cgroup.c:cgroup_kn_unlock
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/cgroup.c:cgroup_get_live
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8114608a)
Location: include/linux/rcupdate.h:741
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_mount
  - kernel/cgroup/cgroup-v1.c:cgroup1_mount
  - kernel/cgroup/cgroup-v1.c:cgroup1_mount
```
```
In kernel/cgroup/freezer.c (ffffffff81146945)
Location: include/linux/rcupdate.h:741
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:freezer_write
  - kernel/cgroup/freezer.c:freezer_write
  - kernel/cgroup/freezer.c:freezer_read
  - kernel/cgroup/freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (ffffffff811479e0)
Location: include/linux/rcupdate.h:741
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
  - kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy
```
```
In kernel/cgroup/cpuset.c (ffffffff8114c142)
Location: include/linux/rcupdate.h:741
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In kernel/trace/ftrace.c (ffffffff811709da)
Location: include/linux/rcupdate.h:741
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:fpid_start
```
```
In kernel/trace/trace_events.c (ffffffff8119415a)
Location: include/linux/rcupdate.h:741
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:p_start
```
```
In kernel/bpf/arraymap.c (ffffffff811c3e2c)
Location: include/linux/rcupdate.h:741
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr
```
```
In kernel/bpf/cgroup.c (ffffffff811d2839)
Location: include/linux/rcupdate.h:741
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_query
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_attach
```
```
In kernel/events/core.c (ffffffff811d93c5)
Location: include/linux/rcupdate.h:741
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_free_event
```
```
In kernel/memremap.c (ffffffff811e967f)
Location: include/linux/rcupdate.h:741
Inline: True
Inline callers:
  - kernel/memremap.c:get_dev_pagemap
  - kernel/memremap.c:get_dev_pagemap
  - kernel/memremap.c:devm_memremap_pages
  - kernel/memremap.c:devm_memremap_pages
  - kernel/memremap.c:devm_memremap_pages
  - kernel/memremap.c:devm_memremap_pages_release
  - kernel/memremap.c:devm_memremap_pages_release
```
```
In mm/page-writeback.c (ffffffff811fda01)
Location: include/linux/rcupdate.h:741
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/swap.c (ffffffff812013c3)
Location: include/linux/rcupdate.h:741
Inline: True
```
```
In mm/backing-dev.c (ffffffff81218eb0)
Location: include/linux/rcupdate.h:741
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/backing-dev.c:cgwb_release_workfn
```
```
In mm/slab_common.c (ffffffff8121ed61)
Location: include/linux/rcupdate.h:741
Inline: True
Inline callers:
  - mm/slab_common.c:slab_deactivate_memcg_cache_rcu_sched
  - mm/slab_common.c:kmemcg_deactivate_workfn
```
```
In mm/gup.c (ffffffff81226c1b)
Location: include/linux/rcupdate.h:741
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:follow_page_pte
```
```
In mm/huge_memory.c (ffffffff8127512e)
Location: include/linux/rcupdate.h:741
Inline: True
Inline callers:
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:follow_devmap_pmd
```
```
In mm/memcontrol.c (ffffffff81286451)
Location: include/linux/rcupdate.h:741
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_sk_free
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_event_remove
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:memcg_kmem_uncharge
  - mm/memcontrol.c:memcg_kmem_charge
  - mm/memcontrol.c:memcg_kmem_put_cache
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:memcg_kmem_cache_create_func
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:task_in_mem_cgroup
  - mm/memcontrol.c:task_in_mem_cgroup
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:get_mem_cgroup_from_mm
```
```
In mm/hugetlb_cgroup.c (ffffffff81287ecd)
Location: include/linux/rcupdate.h:741
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In mm/memory-failure.c (ffffffff812896c2)
Location: include/linux/rcupdate.h:741
Inline: True
```
```
In mm/hmm.c (ffffffff81292790)
Location: include/linux/rcupdate.h:741
Inline: True
Inline callers:
  - mm/hmm.c:hmm_devmem_release
  - mm/hmm.c:hmm_devmem_release
```
```
In fs/inode.c (ffffffff812b90af)
Location: include/linux/rcupdate.h:741
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
```
```
In fs/file.c (ffffffff812bc7f5)
Location: include/linux/rcupdate.h:741
Inline: True
```
```
In fs/fs-writeback.c (ffffffff812cbdd6)
Location: include/linux/rcupdate.h:741
Inline: True
Inline callers:
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:wbc_detach_inode
  - fs/fs-writeback.c:wbc_attach_and_unlock_inode
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/block_dev.c (ffffffff812dcacf)
Location: include/linux/rcupdate.h:741
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_evict_inode
```
```
In fs/aio.c (ffffffff812f31e1)
Location: include/linux/rcupdate.h:741
Inline: True
Inline callers:
  - fs/aio.c:do_io_getevents
  - fs/aio.c:__ia32_sys_io_cancel
  - fs/aio.c:__x64_sys_io_cancel
  - fs/aio.c:__x32_compat_sys_io_submit
  - fs/aio.c:__ia32_compat_sys_io_submit
  - fs/aio.c:__ia32_sys_io_submit
  - fs/aio.c:__x64_sys_io_submit
  - fs/aio.c:io_submit_one
  - fs/aio.c:io_submit_one
  - fs/aio.c:__ia32_sys_io_destroy
  - fs/aio.c:__x64_sys_io_destroy
  - fs/aio.c:__x32_compat_sys_io_setup
  - fs/aio.c:__ia32_compat_sys_io_setup
  - fs/aio.c:__ia32_sys_io_setup
  - fs/aio.c:__x64_sys_io_setup
  - fs/aio.c:aio_complete
  - fs/aio.c:lookup_ioctx
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:free_ioctx_users
```
```
In block/bio.c (ffffffff8147a63d)
Location: include/linux/rcupdate.h:741
Inline: True
Inline callers:
  - block/bio.c:bio_disassociate_task
```
```
In block/blk-core.c (ffffffff814846ca)
Location: include/linux/rcupdate.h:741
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:direct_make_request
  - block/blk-core.c:generic_make_request
  - block/blk-core.c:generic_make_request
  - block/blk-core.c:generic_make_request
  - block/blk-core.c:blk_queue_bio
  - block/blk-core.c:blk_queue_bio
  - block/blk-core.c:__blk_put_request
  - block/blk-core.c:blk_get_request
  - block/blk-core.c:blk_queue_enter
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-merge.c (ffffffff8148bcde)
Location: include/linux/rcupdate.h:741
Inline: True
```
```
In block/blk-mq.c (ffffffff8148f17c)
Location: include/linux/rcupdate.h:741
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_timeout_work
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/blk-cgroup.c (ffffffff814a7e60)
Location: include/linux/rcupdate.h:741
Inline: True
Inline callers:
  - block/blk-cgroup.c:__blkg_release_rcu
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_create
```
```
In lib/percpu-refcount.c (ffffffff814cb7d8)
Location: include/linux/rcupdate.h:741
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_reinit
  - lib/percpu-refcount.c:percpu_ref_kill_and_confirm
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In drivers/block/loop.c (ffffffff816ab980)
Location: include/linux/rcupdate.h:741
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_rq
  - drivers/block/loop.c:lo_rw_aio_complete
```
```
In drivers/dax/super.c (ffffffff816e224b)
Location: include/linux/rcupdate.h:741
Inline: True
```
```
In drivers/md/md.c (ffffffff817f55c5)
Location: include/linux/rcupdate.h:741
Inline: True
Inline callers:
  - drivers/md/md.c:md_write_end
```
```
In lib/bug.c (ffffffff819cd820)
Location: include/linux/rcupdate.h:741
Inline: True
Inline callers:
  - lib/bug.c:generic_bug_clear_once
  - lib/bug.c:module_find_bug
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
In kernel/workqueue.c (ffffffff810b3889)
Location: include/linux/rcupdate.h:711
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_pool_ids_show
  - kernel/workqueue.c:freeze_workqueues_busy
  - kernel/workqueue.c:show_workqueue_state
  - kernel/workqueue.c:workqueue_congested
```
```
In kernel/kthread.c (ffffffff810bcc7b)
Location: include/linux/rcupdate.h:711
Inline: True
```
```
In kernel/sched/deadline.c (ffffffff810e2a35)
Location: include/linux/rcupdate.h:711
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_cpu_busy
  - kernel/sched/deadline.c:dl_cpuset_cpumask_can_shrink
  - kernel/sched/deadline.c:dl_task_can_attach
  - kernel/sched/deadline.c:sched_dl_do_global
  - kernel/sched/deadline.c:sched_dl_global_validate
```
```
In kernel/cgroup/cgroup.c (ffffffff8114f402)
Location: include/linux/rcupdate.h:711
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_free
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_get_from_fd
  - kernel/cgroup/cgroup.c:css_tryget_online_from_dir
  - kernel/cgroup/cgroup.c:kill_css
  - kernel/cgroup/cgroup.c:css_killed_work_fn
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - kernel/cgroup/cgroup.c:cgroup_do_mount
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
  - kernel/cgroup/cgroup.c:cgroup_kn_unlock
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/cgroup.c:cgroup_get_live
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81151c4a)
Location: include/linux/rcupdate.h:711
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_mount
  - kernel/cgroup/cgroup-v1.c:cgroup1_mount
  - kernel/cgroup/cgroup-v1.c:cgroup1_mount
```
```
In kernel/cgroup/freezer.c (ffffffff81152614)
Location: include/linux/rcupdate.h:711
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:freezer_write
  - kernel/cgroup/freezer.c:freezer_write
  - kernel/cgroup/freezer.c:freezer_read
  - kernel/cgroup/freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (ffffffff81153299)
Location: include/linux/rcupdate.h:711
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
  - kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy
```
```
In kernel/cgroup/cpuset.c (ffffffff81158d84)
Location: include/linux/rcupdate.h:711
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
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
```
In kernel/trace/ftrace.c (ffffffff8117e47a)
Location: include/linux/rcupdate.h:711
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:fpid_start
```
```
In kernel/trace/trace_events.c (ffffffff811a237a)
Location: include/linux/rcupdate.h:711
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:p_start
```
```
In kernel/bpf/arraymap.c (ffffffff811d5aec)
Location: include/linux/rcupdate.h:711
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr
```
```
In kernel/bpf/cgroup.c (ffffffff811e25c9)
Location: include/linux/rcupdate.h:711
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_query
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_attach
```
```
In kernel/events/core.c (ffffffff811e984e)
Location: include/linux/rcupdate.h:711
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_free_event
```
```
In kernel/memremap.c (ffffffff811fa01c)
Location: include/linux/rcupdate.h:711
Inline: True
Inline callers:
  - kernel/memremap.c:get_dev_pagemap
  - kernel/memremap.c:get_dev_pagemap
  - kernel/memremap.c:devm_memremap_pages
  - kernel/memremap.c:devm_memremap_pages
```
```
In mm/oom_kill.c (ffffffff81205df6)
Location: include/linux/rcupdate.h:711
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
```
```
In mm/page-writeback.c (ffffffff8121052a)
Location: include/linux/rcupdate.h:711
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/swap.c (ffffffff81214672)
Location: include/linux/rcupdate.h:711
Inline: True
```
```
In mm/backing-dev.c (ffffffff8122bcea)
Location: include/linux/rcupdate.h:711
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/backing-dev.c:cgwb_release_workfn
```
```
In mm/slab_common.c (ffffffff81231d41)
Location: include/linux/rcupdate.h:711
Inline: True
Inline callers:
  - mm/slab_common.c:slab_deactivate_memcg_cache_rcu_sched
  - mm/slab_common.c:kmemcg_deactivate_workfn
```
```
In mm/gup.c (ffffffff81239d1b)
Location: include/linux/rcupdate.h:711
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page
```
```
In mm/memcontrol.c (ffffffff8129b3a3)
Location: include/linux/rcupdate.h:711
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_sk_free
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_event_remove
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:memcg_kmem_uncharge
  - mm/memcontrol.c:memcg_kmem_charge
  - mm/memcontrol.c:memcg_kmem_charge
  - mm/memcontrol.c:memcg_kmem_put_cache
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:memcg_kmem_cache_create_func
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:mem_cgroup_get_oom_group
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:task_in_mem_cgroup
  - mm/memcontrol.c:task_in_mem_cgroup
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:get_mem_cgroup_from_page
```
```
In mm/hugetlb_cgroup.c (ffffffff8129ce19)
Location: include/linux/rcupdate.h:711
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In mm/memory-failure.c (ffffffff8129e51b)
Location: include/linux/rcupdate.h:711
Inline: True
```
```
In fs/inode.c (ffffffff812ce1f8)
Location: include/linux/rcupdate.h:711
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
```
```
In fs/file.c (ffffffff812d1ab5)
Location: include/linux/rcupdate.h:711
Inline: True
```
```
In fs/fs-writeback.c (ffffffff812e0cff)
Location: include/linux/rcupdate.h:711
Inline: True
Inline callers:
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:wbc_detach_inode
  - fs/fs-writeback.c:wbc_attach_and_unlock_inode
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/buffer.c (ffffffff812ebeec)
Location: include/linux/rcupdate.h:711
Inline: True
Inline callers:
  - fs/buffer.c:alloc_page_buffers
```
```
In fs/block_dev.c (ffffffff812f2054)
Location: include/linux/rcupdate.h:711
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_evict_inode
```
```
In fs/notify/group.c (ffffffff812f9c6a)
Location: include/linux/rcupdate.h:711
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_put_group
```
```
In fs/aio.c (ffffffff813081e1)
Location: include/linux/rcupdate.h:711
Inline: True
Inline callers:
  - fs/aio.c:do_io_getevents
  - fs/aio.c:__ia32_sys_io_cancel
  - fs/aio.c:__x64_sys_io_cancel
  - fs/aio.c:__x32_compat_sys_io_submit
  - fs/aio.c:__ia32_compat_sys_io_submit
  - fs/aio.c:__ia32_sys_io_submit
  - fs/aio.c:__x64_sys_io_submit
  - fs/aio.c:io_submit_one
  - fs/aio.c:io_submit_one
  - fs/aio.c:io_submit_one
  - fs/aio.c:__ia32_sys_io_destroy
  - fs/aio.c:__x64_sys_io_destroy
  - fs/aio.c:__x32_compat_sys_io_setup
  - fs/aio.c:__ia32_compat_sys_io_setup
  - fs/aio.c:__ia32_sys_io_setup
  - fs/aio.c:__x64_sys_io_setup
  - fs/aio.c:aio_complete
  - fs/aio.c:lookup_ioctx
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:free_ioctx_users
```
```
In block/bio.c (ffffffff8149860c)
Location: include/linux/rcupdate.h:711
Inline: True
Inline callers:
  - block/bio.c:bio_endio
  - block/bio.c:bio_reset
  - block/bio.c:bio_free
```
```
In block/blk-core.c (ffffffff8149f6bd)
Location: include/linux/rcupdate.h:711
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_account_io_done
  - block/blk-core.c:direct_make_request
  - block/blk-core.c:generic_make_request
  - block/blk-core.c:generic_make_request
  - block/blk-core.c:generic_make_request
  - block/blk-core.c:blk_queue_enter
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-merge.c (ffffffff814a5977)
Location: include/linux/rcupdate.h:711
Inline: True
```
```
In block/blk-mq.c (ffffffff814a7a8c)
Location: include/linux/rcupdate.h:711
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_timeout_work
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/blk-mq-tag.c (ffffffff814ad253)
Location: include/linux/rcupdate.h:711
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
```
In block/blk-cgroup.c (ffffffff814c3285)
Location: include/linux/rcupdate.h:711
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:__blkg_release
  - block/blk-cgroup.c:__blkg_release
```
```
In block/blk-throttle.c (ffffffff814c5f9d)
Location: include/linux/rcupdate.h:711
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:throtl_pop_queued
  - block/blk-throttle.c:throtl_qnode_add_bio
```
```
In lib/percpu-refcount.c (ffffffff814e0514)
Location: include/linux/rcupdate.h:711
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_resurrect
  - lib/percpu-refcount.c:percpu_ref_kill_and_confirm
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In drivers/block/loop.c (ffffffff816cc721)
Location: include/linux/rcupdate.h:711
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_rq
  - drivers/block/loop.c:lo_rw_aio_complete
```
```
In drivers/dax/super.c (ffffffff81705663)
Location: include/linux/rcupdate.h:711
Inline: True
```
```
In drivers/scsi/scsi_lib.c (ffffffff817146b3)
Location: include/linux/rcupdate.h:711
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_end_request
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/md/md.c (ffffffff81821425)
Location: include/linux/rcupdate.h:711
Inline: True
Inline callers:
  - drivers/md/md.c:md_write_end
```
```
In lib/bug.c (ffffffff81a06b80)
Location: include/linux/rcupdate.h:711
Inline: True
Inline callers:
  - lib/bug.c:generic_bug_clear_once
  - lib/bug.c:module_find_bug
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
In kernel/kthread.c (ffffffff810c2a67)
Location: include/linux/rcupdate.h:696
Inline: True
```
```
In kernel/sched/deadline.c (ffffffff810e9545)
Location: include/linux/rcupdate.h:696
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_cpu_busy
  - kernel/sched/deadline.c:dl_cpuset_cpumask_can_shrink
  - kernel/sched/deadline.c:dl_task_can_attach
  - kernel/sched/deadline.c:sched_dl_do_global
  - kernel/sched/deadline.c:sched_dl_global_validate
```
```
In kernel/cgroup/cgroup.c (ffffffff8115b28f)
Location: include/linux/rcupdate.h:696
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_free
  - kernel/cgroup/cgroup.c:cgroup_sk_free
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_get_from_fd
  - kernel/cgroup/cgroup.c:css_tryget_online_from_dir
  - kernel/cgroup/cgroup.c:kill_css
  - kernel/cgroup/cgroup.c:css_killed_work_fn
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - kernel/cgroup/cgroup.c:cgroup_do_get_tree
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
  - kernel/cgroup/cgroup.c:cgroup_kn_unlock
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/cgroup.c:cgroup_get_live
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8115d917)
Location: include/linux/rcupdate.h:696
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff8115ec74)
Location: include/linux/rcupdate.h:696
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_read
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (ffffffff8115fbfc)
Location: include/linux/rcupdate.h:696
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
  - kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy
```
```
In kernel/cgroup/cpuset.c (ffffffff81165503)
Location: include/linux/rcupdate.h:696
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
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
```
In kernel/trace/ftrace.c (ffffffff8118b50a)
Location: include/linux/rcupdate.h:696
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:fpid_start
```
```
In kernel/trace/trace_events.c (ffffffff811b029a)
Location: include/linux/rcupdate.h:696
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:p_start
```
```
In kernel/bpf/arraymap.c (ffffffff811ea47c)
Location: include/linux/rcupdate.h:696
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr
```
```
In kernel/bpf/cgroup.c (ffffffff811f9739)
Location: include/linux/rcupdate.h:696
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_query
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_release
  - kernel/bpf/cgroup.c:cgroup_bpf_offline
```
```
In kernel/events/core.c (ffffffff81202c57)
Location: include/linux/rcupdate.h:696
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_free_event
```
```
In mm/oom_kill.c (ffffffff8121c39c)
Location: include/linux/rcupdate.h:696
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
```
```
In mm/page-writeback.c (ffffffff8121fbca)
Location: include/linux/rcupdate.h:696
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/swap.c (ffffffff8122432d)
Location: include/linux/rcupdate.h:696
Inline: True
```
```
In mm/backing-dev.c (ffffffff8123b7d3)
Location: include/linux/rcupdate.h:696
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/backing-dev.c:cgwb_release_workfn
```
```
In mm/slab_common.c (ffffffff81242283)
Location: include/linux/rcupdate.h:696
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:memcg_deactivate_kmem_caches
```
```
In mm/gup.c (ffffffff8124afb5)
Location: include/linux/rcupdate.h:696
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page
```
```
In mm/slub.c (ffffffff812959d4)
Location: include/linux/rcupdate.h:696
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (ffffffff812b6627)
Location: include/linux/rcupdate.h:696
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_sk_free
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_event_remove
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:__memcg_kmem_uncharge
  - mm/memcontrol.c:__memcg_kmem_charge
  - mm/memcontrol.c:__memcg_kmem_charge
  - mm/memcontrol.c:memcg_kmem_put_cache
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:memcg_kmem_cache_create_func
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:mem_cgroup_get_oom_group
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:get_mem_cgroup_from_page
  - mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node
```
```
In mm/hugetlb_cgroup.c (ffffffff812b7fc2)
Location: include/linux/rcupdate.h:696
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In mm/memory-failure.c (ffffffff812ba263)
Location: include/linux/rcupdate.h:696
Inline: True
```
```
In mm/memremap.c (ffffffff812c248c)
Location: include/linux/rcupdate.h:696
Inline: True
Inline callers:
  - mm/memremap.c:get_dev_pagemap
  - mm/memremap.c:get_dev_pagemap
  - mm/memremap.c:devm_memremap_pages
  - mm/memremap.c:devm_memremap_pages
  - mm/memremap.c:devm_memremap_pages
```
```
In mm/hmm.c (ffffffff812c5004)
Location: include/linux/rcupdate.h:696
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/inode.c (ffffffff812eb0b8)
Location: include/linux/rcupdate.h:696
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
```
```
In fs/file.c (ffffffff812eeac5)
Location: include/linux/rcupdate.h:696
Inline: True
```
```
In fs/fs-writeback.c (ffffffff812ff40f)
Location: include/linux/rcupdate.h:696
Inline: True
Inline callers:
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:wbc_detach_inode
  - fs/fs-writeback.c:wbc_attach_and_unlock_inode
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/buffer.c (ffffffff8130d61f)
Location: include/linux/rcupdate.h:696
Inline: True
Inline callers:
  - fs/buffer.c:alloc_page_buffers
```
```
In fs/block_dev.c (ffffffff813139f4)
Location: include/linux/rcupdate.h:696
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_evict_inode
```
```
In fs/notify/group.c (ffffffff8131a31b)
Location: include/linux/rcupdate.h:696
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_put_group
```
```
In fs/aio.c (ffffffff81329c9a)
Location: include/linux/rcupdate.h:696
Inline: True
Inline callers:
  - fs/aio.c:do_io_getevents
  - fs/aio.c:__ia32_sys_io_cancel
  - fs/aio.c:__x64_sys_io_cancel
  - fs/aio.c:__x32_compat_sys_io_submit
  - fs/aio.c:__ia32_compat_sys_io_submit
  - fs/aio.c:__ia32_sys_io_submit
  - fs/aio.c:__x64_sys_io_submit
  - fs/aio.c:io_submit_one
  - fs/aio.c:io_submit_one
  - fs/aio.c:io_submit_one
  - fs/aio.c:aio_poll_wake
  - fs/aio.c:aio_poll_complete_work
  - fs/aio.c:aio_fsync_work
  - fs/aio.c:aio_complete_rw
  - fs/aio.c:__ia32_sys_io_destroy
  - fs/aio.c:__x64_sys_io_destroy
  - fs/aio.c:__x32_compat_sys_io_setup
  - fs/aio.c:__ia32_compat_sys_io_setup
  - fs/aio.c:__ia32_sys_io_setup
  - fs/aio.c:__x64_sys_io_setup
  - fs/aio.c:lookup_ioctx
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:free_ioctx_users
```
```
In fs/io_uring.c (ffffffff813304ba)
Location: include/linux/rcupdate.h:696
Inline: True
Inline callers:
  - fs/io_uring.c:__ia32_sys_io_uring_enter
  - fs/io_uring.c:__x64_sys_io_uring_enter
  - fs/io_uring.c:io_submit_sqe
```
```
In block/bio.c (ffffffff814c64a6)
Location: include/linux/rcupdate.h:696
Inline: True
Inline callers:
  - block/bio.c:bio_endio
  - block/bio.c:bio_reset
  - block/bio.c:bio_free
```
```
In block/blk-core.c (ffffffff814cd7b2)
Location: include/linux/rcupdate.h:696
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_account_io_done
  - block/blk-core.c:direct_make_request
  - block/blk-core.c:blk_queue_enter
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-merge.c (ffffffff814d3983)
Location: include/linux/rcupdate.h:696
Inline: True
```
```
In block/blk-mq.c (ffffffff814d5afc)
Location: include/linux/rcupdate.h:696
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_timeout_work
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/blk-mq-tag.c (ffffffff814db4c4)
Location: include/linux/rcupdate.h:696
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
```
In block/blk-mq-sched.c (ffffffff814dd5bf)
Location: include/linux/rcupdate.h:696
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
```
In block/blk-cgroup.c (ffffffff814f1954)
Location: include/linux/rcupdate.h:696
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:__blkg_release
  - block/blk-cgroup.c:__blkg_release
```
```
In block/blk-throttle.c (ffffffff814f47da)
Location: include/linux/rcupdate.h:696
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:throtl_pop_queued
  - block/blk-throttle.c:throtl_qnode_add_bio
```
```
In lib/percpu-refcount.c (ffffffff8150c4b8)
Location: include/linux/rcupdate.h:696
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_resurrect
  - lib/percpu-refcount.c:percpu_ref_kill_and_confirm
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In drivers/block/loop.c (ffffffff817081b6)
Location: include/linux/rcupdate.h:696
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_rq
  - drivers/block/loop.c:lo_rw_aio_complete
```
```
In drivers/dax/super.c (ffffffff8173f7be)
Location: include/linux/rcupdate.h:696
Inline: True
```
```
In drivers/scsi/scsi_lib.c (ffffffff81750009)
Location: include/linux/rcupdate.h:696
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_end_request
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/md/md.c (ffffffff81863cf5)
Location: include/linux/rcupdate.h:696
Inline: True
Inline callers:
  - drivers/md/md.c:md_write_end
```
```
In lib/bug.c (ffffffff81a764f0)
Location: include/linux/rcupdate.h:696
Inline: True
Inline callers:
  - lib/bug.c:generic_bug_clear_once
  - lib/bug.c:module_find_bug
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
In kernel/kthread.c (ffffffff810c8fd7)
Location: include/linux/rcupdate.h:703
Inline: True
```
```
In kernel/sched/deadline.c (ffffffff810f5025)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_cpu_busy
  - kernel/sched/deadline.c:dl_cpuset_cpumask_can_shrink
  - kernel/sched/deadline.c:dl_task_can_attach
  - kernel/sched/deadline.c:sched_dl_do_global
  - kernel/sched/deadline.c:sched_dl_global_validate
```
```
In kernel/cgroup/cgroup.c (ffffffff81166f4f)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_free
  - kernel/cgroup/cgroup.c:cgroup_sk_free
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_get_from_fd
  - kernel/cgroup/cgroup.c:css_tryget_online_from_dir
  - kernel/cgroup/cgroup.c:kill_css
  - kernel/cgroup/cgroup.c:css_killed_work_fn
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - kernel/cgroup/cgroup.c:cgroup_do_get_tree
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
  - kernel/cgroup/cgroup.c:cgroup_kn_unlock
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/cgroup.c:cgroup_get_live
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81169527)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff8116a8d4)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_read
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (ffffffff8116b85c)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
  - kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy
```
```
In kernel/cgroup/cpuset.c (ffffffff811713f3)
Location: include/linux/rcupdate.h:703
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
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
```
In kernel/trace/ftrace.c (ffffffff8119740a)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:fpid_start
```
```
In kernel/trace/trace_events.c (ffffffff811bb76a)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:p_start
```
```
In kernel/bpf/arraymap.c (ffffffff811f6bdc)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr
```
```
In kernel/bpf/cgroup.c (ffffffff81206809)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_query
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_release
  - kernel/bpf/cgroup.c:cgroup_bpf_release
  - kernel/bpf/cgroup.c:cgroup_bpf_offline
```
```
In kernel/events/core.c (ffffffff8120fb1c)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_free_event
```
```
In mm/oom_kill.c (ffffffff81229d6c)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
```
```
In mm/page-writeback.c (ffffffff8122d67a)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/swap.c (ffffffff812320c5)
Location: include/linux/rcupdate.h:703
Inline: True
```
```
In mm/backing-dev.c (ffffffff81249e43)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/backing-dev.c:cgwb_release_workfn
```
```
In mm/slab_common.c (ffffffff81250713)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:destroy_memcg_params
```
```
In mm/gup.c (ffffffff812594a5)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page
```
```
In mm/slub.c (ffffffff812a57b4)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (ffffffff812c84f7)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_sk_free
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_event_remove
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:__memcg_kmem_uncharge
  - mm/memcontrol.c:__memcg_kmem_charge
  - mm/memcontrol.c:__memcg_kmem_charge
  - mm/memcontrol.c:memcg_kmem_put_cache
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:memcg_kmem_cache_create_func
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:mem_cgroup_get_oom_group
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:get_mem_cgroup_from_page
  - mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node
```
```
In mm/hugetlb_cgroup.c (ffffffff812c9e54)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In mm/memory-failure.c (ffffffff812cc11f)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
```
```
In mm/memremap.c (ffffffff812d43bc)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - mm/memremap.c:get_dev_pagemap
  - mm/memremap.c:get_dev_pagemap
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memremap_pages
```
```
In mm/hmm.c (ffffffff812d69b4)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/inode.c (ffffffff812fcbf8)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
```
```
In fs/file.c (ffffffff81300585)
Location: include/linux/rcupdate.h:703
Inline: True
```
```
In fs/fs-writeback.c (ffffffff81314b24)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:wbc_detach_inode
  - fs/fs-writeback.c:wbc_attach_and_unlock_inode
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/buffer.c (ffffffff813205ef)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - fs/buffer.c:alloc_page_buffers
```
```
In fs/block_dev.c (ffffffff81326904)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_evict_inode
```
```
In fs/notify/group.c (ffffffff8132d13b)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_put_group
```
```
In fs/aio.c (ffffffff8133cafa)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - fs/aio.c:do_io_getevents
  - fs/aio.c:__ia32_sys_io_cancel
  - fs/aio.c:__x64_sys_io_cancel
  - fs/aio.c:__x32_compat_sys_io_submit
  - fs/aio.c:__ia32_compat_sys_io_submit
  - fs/aio.c:__ia32_sys_io_submit
  - fs/aio.c:__x64_sys_io_submit
  - fs/aio.c:io_submit_one
  - fs/aio.c:io_submit_one
  - fs/aio.c:io_submit_one
  - fs/aio.c:aio_poll_complete_work
  - fs/aio.c:aio_poll_put_work
  - fs/aio.c:aio_fsync_work
  - fs/aio.c:aio_complete_rw
  - fs/aio.c:__ia32_sys_io_destroy
  - fs/aio.c:__x64_sys_io_destroy
  - fs/aio.c:__x32_compat_sys_io_setup
  - fs/aio.c:__ia32_compat_sys_io_setup
  - fs/aio.c:__ia32_sys_io_setup
  - fs/aio.c:__x64_sys_io_setup
  - fs/aio.c:lookup_ioctx
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:free_ioctx_users
```
```
In fs/io_uring.c (ffffffff81343cd6)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - fs/io_uring.c:__ia32_sys_io_uring_enter
  - fs/io_uring.c:__ia32_sys_io_uring_enter
  - fs/io_uring.c:__x64_sys_io_uring_enter
  - fs/io_uring.c:__x64_sys_io_uring_enter
  - fs/io_uring.c:io_iopoll_getevents
  - fs/io_uring.c:io_iopoll_getevents
  - fs/io_uring.c:__io_free_req
  - fs/io_uring.c:io_get_req
  - fs/io_uring.c:io_get_req
```
```
In block/bio.c (ffffffff814de3b9)
Location: include/linux/rcupdate.h:703
Inline: True
```
```
In block/blk-core.c (ffffffff814e6aa2)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_account_io_done
  - block/blk-core.c:direct_make_request
  - block/blk-core.c:blk_queue_enter
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-merge.c (ffffffff814eccb3)
Location: include/linux/rcupdate.h:703
Inline: True
```
```
In block/blk-mq.c (ffffffff814eee2c)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_timeout_work
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/blk-mq-tag.c (ffffffff814f48f4)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
```
In block/blk-mq-sched.c (ffffffff814f6a4f)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
```
In block/blk-cgroup.c (ffffffff8150af49)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:__blkg_release
  - block/blk-cgroup.c:__blkg_release
```
```
In block/blk-throttle.c (ffffffff8150dd74)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:throtl_pop_queued
  - block/blk-throttle.c:throtl_qnode_add_bio
```
```
In lib/percpu-refcount.c (ffffffff8152a308)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_resurrect
  - lib/percpu-refcount.c:percpu_ref_kill_and_confirm
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In drivers/block/loop.c (ffffffff8172c406)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_rq
  - drivers/block/loop.c:lo_rw_aio_complete
```
```
In drivers/dax/super.c (ffffffff8176399e)
Location: include/linux/rcupdate.h:703
Inline: True
```
```
In drivers/scsi/scsi_lib.c (ffffffff817741f9)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_end_request
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/md/md.c (ffffffff81895a35)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - drivers/md/md.c:md_write_end
```
```
In lib/bug.c (ffffffff81aad900)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - lib/bug.c:generic_bug_clear_once
  - lib/bug.c:module_find_bug
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
In kernel/sched/deadline.c (ffffffff810fe745)
Location: include/linux/rcupdate.h:738
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_cpu_busy
  - kernel/sched/deadline.c:dl_cpuset_cpumask_can_shrink
  - kernel/sched/deadline.c:dl_task_can_attach
  - kernel/sched/deadline.c:sched_dl_do_global
  - kernel/sched/deadline.c:sched_dl_global_validate
```
```
In kernel/trace/ftrace.c (ffffffff811aca7a)
Location: include/linux/rcupdate.h:738
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:fnpid_start
  - kernel/trace/ftrace.c:fpid_start
```
```
In kernel/trace/trace_events.c (ffffffff811d426a)
Location: include/linux/rcupdate.h:738
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:np_start
  - kernel/trace/trace_events.c:p_start
```
```
In kernel/trace/trace_events_inject.c (ffffffff811dd9d0)
Location: include/linux/rcupdate.h:738
Inline: True
Inline callers:
  - kernel/trace/trace_events_inject.c:event_inject_write
```
```
In fs/file.c (ffffffff81339735)
Location: include/linux/rcupdate.h:738
Inline: True
Inline callers:
  - fs/file.c:__fd_install
```
```
In lib/bug.c (ffffffff815e7970)
Location: include/linux/rcupdate.h:738
Inline: True
Inline callers:
  - lib/bug.c:generic_bug_clear_once
  - lib/bug.c:find_bug
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
In kernel/sched/deadline.c (ffffffff810fd095)
Location: include/linux/rcupdate.h:754
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_cpu_busy
  - kernel/sched/deadline.c:dl_cpuset_cpumask_can_shrink
  - kernel/sched/deadline.c:dl_task_can_attach
  - kernel/sched/deadline.c:sched_dl_do_global
  - kernel/sched/deadline.c:sched_dl_global_validate
```
```
In kernel/trace/ftrace.c (ffffffff811aa38a)
Location: include/linux/rcupdate.h:754
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:fnpid_start
  - kernel/trace/ftrace.c:fpid_start
```
```
In kernel/trace/trace_events.c (ffffffff811d13ea)
Location: include/linux/rcupdate.h:754
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:np_start
  - kernel/trace/trace_events.c:p_start
```
```
In kernel/trace/trace_events_inject.c (ffffffff811daad0)
Location: include/linux/rcupdate.h:754
Inline: True
Inline callers:
  - kernel/trace/trace_events_inject.c:event_inject_write
```
```
In fs/file.c (ffffffff81344c14)
Location: include/linux/rcupdate.h:754
Inline: True
Inline callers:
  - fs/file.c:fd_install
```
```
In lib/bug.c (ffffffff8160cb30)
Location: include/linux/rcupdate.h:754
Inline: True
Inline callers:
  - lib/bug.c:generic_bug_clear_once
  - lib/bug.c:find_bug
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
In kernel/sched/deadline.c (ffffffff810ff435)
Location: include/linux/rcupdate.h:761
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_cpu_busy
  - kernel/sched/deadline.c:dl_cpuset_cpumask_can_shrink
  - kernel/sched/deadline.c:dl_task_can_attach
  - kernel/sched/deadline.c:sched_dl_do_global
  - kernel/sched/deadline.c:sched_dl_global_validate
```
```
In kernel/livepatch/core.c (ffffffff8113634d)
Location: include/linux/rcupdate.h:761
Inline: True
Inline callers:
  - kernel/livepatch/core.c:klp_init_object
```
```
In kernel/trace/ftrace.c (ffffffff811aaf6a)
Location: include/linux/rcupdate.h:761
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:fnpid_start
  - kernel/trace/ftrace.c:fpid_start
```
```
In kernel/trace/trace_events.c (ffffffff811d256a)
Location: include/linux/rcupdate.h:761
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:np_start
  - kernel/trace/trace_events.c:p_start
```
```
In kernel/trace/trace_events_inject.c (ffffffff811dc040)
Location: include/linux/rcupdate.h:761
Inline: True
Inline callers:
  - kernel/trace/trace_events_inject.c:event_inject_write
```
```
In kernel/trace/trace_kprobe.c (ffffffff811eb5d9)
Location: include/linux/rcupdate.h:761
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_kprobe.c:append_trace_kprobe
```
```
In fs/file.c (ffffffff8134a9a4)
Location: include/linux/rcupdate.h:761
Inline: True
Inline callers:
  - fs/file.c:fd_install
```
```
In lib/bug.c (ffffffff815efe00)
Location: include/linux/rcupdate.h:761
Inline: True
Inline callers:
  - lib/bug.c:generic_bug_clear_once
  - lib/bug.c:find_bug
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
In kernel/sched/deadline.c (ffffffff8111b435)
Location: include/linux/rcupdate.h:775
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_cpu_busy
  - kernel/sched/deadline.c:dl_cpuset_cpumask_can_shrink
  - kernel/sched/deadline.c:dl_task_can_attach
  - kernel/sched/deadline.c:sched_dl_do_global
  - kernel/sched/deadline.c:sched_dl_global_validate
```
```
In kernel/livepatch/core.c (ffffffff81158f0d)
Location: include/linux/rcupdate.h:775
Inline: True
Inline callers:
  - kernel/livepatch/core.c:klp_init_object
```
```
In kernel/trace/ftrace.c (ffffffff811d4c4a)
Location: include/linux/rcupdate.h:775
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:fnpid_start
  - kernel/trace/ftrace.c:fpid_start
```
```
In kernel/trace/trace_events.c (ffffffff811ff2ca)
Location: include/linux/rcupdate.h:775
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:np_start
  - kernel/trace/trace_events.c:p_start
```
```
In kernel/trace/trace_events_inject.c (ffffffff8120b770)
Location: include/linux/rcupdate.h:775
Inline: True
Inline callers:
  - kernel/trace/trace_events_inject.c:event_inject_write
```
```
In kernel/trace/trace_kprobe.c (ffffffff8121c469)
Location: include/linux/rcupdate.h:775
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_kprobe.c:append_trace_kprobe
```
```
In fs/file.c (ffffffff81398757)
Location: include/linux/rcupdate.h:775
Inline: True
Inline callers:
  - fs/file.c:fd_install
```
```
In lib/bug.c (ffffffff8165cf10)
Location: include/linux/rcupdate.h:775
Inline: True
Inline callers:
  - lib/bug.c:generic_bug_clear_once
  - lib/bug.c:find_bug
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
In kernel/sched/build_policy.c (ffffffff8113b0c5)
Location: include/linux/rcupdate.h:783
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:dl_cpu_busy
  - kernel/sched/build_policy.c:dl_cpuset_cpumask_can_shrink
  - kernel/sched/build_policy.c:sched_dl_do_global
  - kernel/sched/build_policy.c:sched_dl_global_validate
```
```
In kernel/livepatch/core.c (ffffffff8118246a)
Location: include/linux/rcupdate.h:783
Inline: True
Inline callers:
  - kernel/livepatch/core.c:klp_init_object
```
```
In kernel/trace/ftrace.c (ffffffff81209d5a)
Location: include/linux/rcupdate.h:783
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:fnpid_start
  - kernel/trace/ftrace.c:fpid_start
```
```
In kernel/trace/trace_events.c (ffffffff8123a7ca)
Location: include/linux/rcupdate.h:783
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:np_start
  - kernel/trace/trace_events.c:p_start
```
```
In kernel/trace/trace_events_inject.c (ffffffff8124789f)
Location: include/linux/rcupdate.h:783
Inline: True
Inline callers:
  - kernel/trace/trace_events_inject.c:event_inject_write
```
```
In kernel/trace/trace_kprobe.c (ffffffff8125cf0d)
Location: include/linux/rcupdate.h:783
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_kprobe.c:append_trace_kprobe
```
```
In fs/file.c (ffffffff8141ab27)
Location: include/linux/rcupdate.h:783
Inline: True
Inline callers:
  - fs/file.c:fd_install
```
```
In lib/bug.c (ffffffff81776320)
Location: include/linux/rcupdate.h:783
Inline: True
Inline callers:
  - lib/bug.c:generic_bug_clear_once
  - lib/bug.c:find_bug
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
In kernel/sched/build_policy.c (ffffffff81165a65)
Location: include/linux/rcupdate.h:861
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:dl_cpu_busy
  - kernel/sched/build_policy.c:dl_cpuset_cpumask_can_shrink
  - kernel/sched/build_policy.c:sched_dl_do_global
  - kernel/sched/build_policy.c:sched_dl_global_validate
```
```
In kernel/livepatch/core.c (ffffffff811bd13a)
Location: include/linux/rcupdate.h:861
Inline: True
Inline callers:
  - kernel/livepatch/core.c:klp_init_object
```
```
In kernel/trace/ftrace.c (ffffffff812523aa)
Location: include/linux/rcupdate.h:861
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:fnpid_start
  - kernel/trace/ftrace.c:fpid_start
```
```
In kernel/trace/trace_events.c (ffffffff812879aa)
Location: include/linux/rcupdate.h:861
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:np_start
  - kernel/trace/trace_events.c:p_start
```
```
In kernel/trace/trace_events_inject.c (ffffffff812959bd)
Location: include/linux/rcupdate.h:861
Inline: True
Inline callers:
  - kernel/trace/trace_events_inject.c:trace_inject_entry
```
```
In kernel/trace/trace_kprobe.c (ffffffff812abecc)
Location: include/linux/rcupdate.h:861
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_kprobe.c:append_trace_kprobe
```
```
In fs/file.c (ffffffff814a66f7)
Location: include/linux/rcupdate.h:861
Inline: True
Inline callers:
  - fs/file.c:fd_install
```
```
In lib/bug.c (ffffffff8201ed50)
Location: include/linux/rcupdate.h:861
Inline: True
Inline callers:
  - lib/bug.c:generic_bug_clear_once
  - lib/bug.c:find_bug
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
In kernel/sched/build_policy.c (ffffffff8116d099)
Location: include/linux/rcupdate.h:837
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:dl_bw_manage
  - kernel/sched/build_policy.c:dl_cpuset_cpumask_can_shrink
  - kernel/sched/build_policy.c:sched_dl_do_global
  - kernel/sched/build_policy.c:sched_dl_global_validate
```
```
In kernel/livepatch/core.c (ffffffff811cf94a)
Location: include/linux/rcupdate.h:837
Inline: True
Inline callers:
  - kernel/livepatch/core.c:klp_init_object
```
```
In kernel/trace/ftrace.c (ffffffff8126967a)
Location: include/linux/rcupdate.h:837
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:fnpid_start
  - kernel/trace/ftrace.c:fpid_start
```
```
In kernel/trace/trace_events.c (ffffffff812a469a)
Location: include/linux/rcupdate.h:837
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:np_start
  - kernel/trace/trace_events.c:p_start
```
```
In kernel/trace/trace_events_inject.c (ffffffff812b28cd)
Location: include/linux/rcupdate.h:837
Inline: True
Inline callers:
  - kernel/trace/trace_events_inject.c:trace_inject_entry
```
```
In kernel/trace/trace_events_user.c (ffffffff812c5fea)
Location: include/linux/rcupdate.h:837
Inline: True
Inline callers:
  - kernel/trace/trace_events_user.c:update_enable_bit_for
```
```
In kernel/trace/trace_kprobe.c (ffffffff812ce6cc)
Location: include/linux/rcupdate.h:837
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_kprobe.c:append_trace_kprobe
```
```
In fs/file.c (ffffffff814db6b7)
Location: include/linux/rcupdate.h:837
Inline: True
Inline callers:
  - fs/file.c:fd_install
```
```
In lib/bug.c (ffffffff8209ed60)
Location: include/linux/rcupdate.h:837
Inline: True
Inline callers:
  - lib/bug.c:generic_bug_clear_once
  - lib/bug.c:find_bug
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
In arch/x86/mm/ioremap.c (ffffffff810d0dc7)
Location: include/linux/rcupdate.h:838
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_check_ram
```
```
In arch/x86/mm/mmap.c (ffffffff810d2776)
Location: include/linux/rcupdate.h:838
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:pfn_modify_allowed
```
```
In arch/x86/mm/physaddr.c (ffffffff810d3d99)
Location: include/linux/rcupdate.h:838
Inline: True
Inline callers:
  - arch/x86/mm/physaddr.c:__virt_addr_valid
```
```
In kernel/sched/build_policy.c (ffffffff81179ad9)
Location: include/linux/rcupdate.h:838
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:dl_bw_manage
  - kernel/sched/build_policy.c:dl_cpuset_cpumask_can_shrink
  - kernel/sched/build_policy.c:sched_dl_do_global
  - kernel/sched/build_policy.c:sched_dl_global_validate
```
```
In kernel/power/snapshot.c (ffffffff811a7ad2)
Location: include/linux/rcupdate.h:838
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:saveable_page
  - kernel/power/snapshot.c:clear_or_poison_free_pages
  - kernel/power/snapshot.c:create_basic_memory_bitmaps
```
```
In kernel/livepatch/core.c (ffffffff811e459a)
Location: include/linux/rcupdate.h:838
Inline: True
Inline callers:
  - kernel/livepatch/core.c:klp_init_object
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff8127519e)
Location: include/linux/rcupdate.h:838
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/trace/ftrace.c (ffffffff812837da)
Location: include/linux/rcupdate.h:838
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:fnpid_start
  - kernel/trace/ftrace.c:fpid_start
```
```
In kernel/trace/trace_events.c (ffffffff812bfffa)
Location: include/linux/rcupdate.h:838
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:np_start
  - kernel/trace/trace_events.c:p_start
```
```
In kernel/trace/trace_events_inject.c (ffffffff812cee7d)
Location: include/linux/rcupdate.h:838
Inline: True
Inline callers:
  - kernel/trace/trace_events_inject.c:trace_inject_entry
```
```
In kernel/trace/trace_events_user.c (ffffffff812e285a)
Location: include/linux/rcupdate.h:838
Inline: True
Inline callers:
  - kernel/trace/trace_events_user.c:update_enable_bit_for
```
```
In kernel/trace/trace_kprobe.c (ffffffff812ec0cc)
Location: include/linux/rcupdate.h:838
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_kprobe.c:append_trace_kprobe
```
```
In kernel/iomem.c (ffffffff813b0db7)
Location: include/linux/rcupdate.h:838
Inline: True
Inline callers:
  - kernel/iomem.c:try_ram_remap
```
```
In mm/vmscan.c (ffffffff813d623c)
Location: include/linux/rcupdate.h:838
Inline: True
```
```
In mm/mm_init.c (ffffffff83912d7f)
Location: include/linux/rcupdate.h:838
Inline: True
Inline callers:
  - mm/mm_init.c:init_unavailable_range
  - mm/mm_init.c:reserve_bootmem_region
```
```
In mm/compaction.c (ffffffff81403e72)
Location: include/linux/rcupdate.h:838
Inline: True
Inline callers:
  - mm/compaction.c:fast_isolate_freepages
```
```
In mm/memory.c (ffffffff8141d377)
Location: include/linux/rcupdate.h:838
Inline: True
Inline callers:
  - mm/memory.c:vmf_insert_pfn_prot
```
```
In mm/vmalloc.c (ffffffff8143ee9f)
Location: include/linux/rcupdate.h:838
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap_pfn_apply
  - mm/vmalloc.c:vmap_pages_pud_range
```
```
In mm/page_alloc.c (ffffffff81449202)
Location: include/linux/rcupdate.h:838
Inline: True
Inline callers:
  - mm/page_alloc.c:__pageblock_pfn_to_page
```
```
In mm/memory_hotplug.c (ffffffff8222a08d)
Location: include/linux/rcupdate.h:838
Inline: True
Inline callers:
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:do_migrate_range
```
```
In mm/memory-failure.c (ffffffff814c9242)
Location: include/linux/rcupdate.h:838
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
```
```
In mm/bootmem_info.c (ffffffff839206b5)
Location: include/linux/rcupdate.h:838
Inline: True
Inline callers:
  - mm/bootmem_info.c:register_page_bootmem_info_node
```
```
In fs/file.c (ffffffff8150ddcd)
Location: include/linux/rcupdate.h:838
Inline: True
Inline callers:
  - fs/file.c:fd_install
```
```
In fs/proc/kcore.c (ffffffff815b59c7)
Location: include/linux/rcupdate.h:838
Inline: True
Inline callers:
  - fs/proc/kcore.c:kclist_add_private
```
```
In drivers/acpi/apei/ghes.c (ffffffff81a7b350)
Location: include/linux/rcupdate.h:838
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81acc27b)
Location: include/linux/rcupdate.h:838
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/edac/edac_mc.c (ffffffff81e4113b)
Location: include/linux/rcupdate.h:838
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_scrub_block
```
```
In drivers/ras/cec.c (ffffffff81eaf3bd)
Location: include/linux/rcupdate.h:838
Inline: True
Inline callers:
  - drivers/ras/cec.c:cec_add_elem
```
```
In lib/bug.c (ffffffff82176d60)
Location: include/linux/rcupdate.h:838
Inline: True
Inline callers:
  - lib/bug.c:generic_bug_clear_once
  - lib/bug.c:find_bug
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
In kernel/kthread.c (ffff800010128894)
Location: include/linux/rcupdate.h:703
Inline: True
```
```
In kernel/sched/deadline.c (ffff8000101578c0)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_cpu_busy
  - kernel/sched/deadline.c:dl_cpuset_cpumask_can_shrink
  - kernel/sched/deadline.c:dl_task_can_attach
  - kernel/sched/deadline.c:sched_dl_do_global
  - kernel/sched/deadline.c:sched_dl_global_validate
```
```
In kernel/cgroup/cgroup.c (ffff8000101d8d6c)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:css_killed_work_fn
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/cgroup-v1.c (ffff8000101dc8a0)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In kernel/cgroup/legacy_freezer.c (ffff8000101de774)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_read
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (ffff8000101dfba0)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
  - kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy
```
```
In kernel/cgroup/cpuset.c (ffff8000101e4a68)
Location: include/linux/rcupdate.h:703
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
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
```
In kernel/trace/ftrace.c (ffff80001020f81c)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:fpid_start
```
```
In kernel/trace/trace_events.c (ffff800010239d80)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:p_start
```
```
In kernel/bpf/arraymap.c (ffff80001027b8c4)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr
```
```
In kernel/bpf/cgroup.c (ffff80001028ff00)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_query
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_release
  - kernel/bpf/cgroup.c:cgroup_bpf_release
  - kernel/bpf/cgroup.c:cgroup_bpf_offline
```
```
In kernel/events/core.c (ffff80001029bca4)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - kernel/events/core.c:_free_event
```
```
In mm/oom_kill.c (ffff8000102b7c54)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
```
```
In mm/page-writeback.c (ffff8000102bc4fc)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/swap.c (0)
Location: include/linux/rcupdate.h:703
Inline: True
```
```
In mm/backing-dev.c (ffff8000102df534)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/backing-dev.c:cgwb_release_workfn
```
```
In mm/slab_common.c (ffff8000102e776c)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:destroy_memcg_params
```
```
In mm/gup.c (ffff8000102f26dc)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page
```
```
In mm/slub.c (ffff8000103465f8)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (ffff80001036632c)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:mem_cgroup_get_oom_group
  - mm/memcontrol.c:percpu_ref_put_many
  - mm/memcontrol.c:percpu_ref_tryget_live
```
```
In mm/hugetlb_cgroup.c (ffff80001036d6f4)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In mm/memory-failure.c (0)
Location: include/linux/rcupdate.h:703
Inline: True
```
```
In mm/hmm.c (ffff80001037b87c)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/inode.c (ffff8000103acdb8)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
```
```
In fs/file.c (ffff8000103b226c)
Location: include/linux/rcupdate.h:703
Inline: True
```
```
In fs/fs-writeback.c (ffff8000103caa90)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:wbc_detach_inode
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/buffer.c (ffff8000103d9278)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - fs/buffer.c:alloc_page_buffers
```
```
In fs/block_dev.c (ffff8000103e13e0)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_evict_inode
```
```
In fs/notify/group.c (ffff8000103e8f2c)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_put_group
```
```
In fs/aio.c (ffff8000103fc500)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - fs/aio.c:do_io_getevents
  - fs/aio.c:__arm64_sys_io_cancel
  - fs/aio.c:__arm64_compat_sys_io_submit
  - fs/aio.c:__arm64_sys_io_submit
  - fs/aio.c:io_submit_one
  - fs/aio.c:io_submit_one
  - fs/aio.c:io_submit_one
  - fs/aio.c:io_submit_one
  - fs/aio.c:aio_poll_wake
  - fs/aio.c:aio_poll_complete_work
  - fs/aio.c:aio_poll_put_work
  - fs/aio.c:aio_fsync_work
  - fs/aio.c:aio_complete_rw
  - fs/aio.c:__arm64_sys_io_destroy
  - fs/aio.c:__arm64_compat_sys_io_setup
  - fs/aio.c:__arm64_sys_io_setup
  - fs/aio.c:lookup_ioctx
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:free_ioctx_users
```
```
In fs/io_uring.c (ffff800010405a88)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - fs/io_uring.c:__arm64_sys_io_uring_enter
  - fs/io_uring.c:__arm64_sys_io_uring_enter
  - fs/io_uring.c:io_iopoll_getevents
  - fs/io_uring.c:io_iopoll_getevents
  - fs/io_uring.c:__io_free_req
  - fs/io_uring.c:io_get_req
  - fs/io_uring.c:io_get_req
```
```
In block/bio.c (ffff8000105db5a0)
Location: include/linux/rcupdate.h:703
Inline: True
```
```
In block/blk-core.c (ffff8000105e42d4)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_account_io_done
  - block/blk-core.c:direct_make_request
  - block/blk-core.c:blk_queue_enter
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-merge.c (ffff8000105eb698)
Location: include/linux/rcupdate.h:703
Inline: True
```
```
In block/blk-mq.c (ffff8000105ef678)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_timeout_work
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/blk-mq-tag.c (ffff8000105f4738)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
```
In block/blk-mq-sched.c (ffff8000105f70f4)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
```
In block/blk-cgroup.c (ffff80001060e860)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:__blkg_release
  - block/blk-cgroup.c:__blkg_release
```
```
In block/blk-throttle.c (ffff8000106119d4)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:throtl_pop_queued
  - block/blk-throttle.c:throtl_qnode_add_bio
```
```
In lib/percpu-refcount.c (ffff800010635644)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_resurrect
  - lib/percpu-refcount.c:percpu_ref_kill_and_confirm
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In drivers/block/loop.c (ffff800010924f14)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_rq
  - drivers/block/loop.c:lo_rw_aio_complete
```
```
In drivers/dax/super.c (0)
Location: include/linux/rcupdate.h:703
Inline: True
```
```
In drivers/scsi/scsi_lib.c (ffff800010978258)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_end_request
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/md/md.c (ffff800010aeaa78)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - drivers/md/md.c:md_write_end
```
```
In lib/bug.c (ffff800010d83c18)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - lib/bug.c:generic_bug_clear_once
  - lib/bug.c:module_find_bug
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
In kernel/kthread.c (c037ad0c)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_associate_blkcg
  - kernel/kthread.c:kthread_associate_blkcg
```
```
In kernel/sched/deadline.c (c03a562c)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_cpu_busy
  - kernel/sched/deadline.c:dl_cpuset_cpumask_can_shrink
  - kernel/sched/deadline.c:dl_task_can_attach
  - kernel/sched/deadline.c:sched_dl_do_global
  - kernel/sched/deadline.c:sched_dl_global_validate
```
```
In kernel/cgroup/cgroup.c (c041bc88)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_free
  - kernel/cgroup/cgroup.c:cgroup_sk_free
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_get_from_fd
  - kernel/cgroup/cgroup.c:css_tryget_online_from_dir
  - kernel/cgroup/cgroup.c:kill_css
  - kernel/cgroup/cgroup.c:css_killed_work_fn
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - kernel/cgroup/cgroup.c:cgroup_do_get_tree
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
  - kernel/cgroup/cgroup.c:cgroup_kn_unlock
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/cgroup.c:cgroup_get_live
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/cgroup-v1.c (c041ea24)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In kernel/cgroup/legacy_freezer.c (c042022c)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_read
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (c04214e4)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
  - kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy
```
```
In kernel/cgroup/cpuset.c (c0425890)
Location: include/linux/rcupdate.h:703
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
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
```
In kernel/trace/ftrace.c (c044f2d8)
Location: include/linux/rcupdate.h:703
Inline: True
```
```
In kernel/trace/trace_events.c (c0475454)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:p_start
```
```
In kernel/bpf/arraymap.c (c04ad31c)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr
```
```
In kernel/bpf/cgroup.c (c04bf5a8)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_query
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_release
  - kernel/bpf/cgroup.c:cgroup_bpf_release
  - kernel/bpf/cgroup.c:cgroup_bpf_offline
```
```
In kernel/events/core.c (c04c79d0)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_free_event
```
```
In mm/oom_kill.c (c04e47f8)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
```
```
In mm/page-writeback.c (c04e8b3c)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/swap.c (0)
Location: include/linux/rcupdate.h:703
Inline: True
```
```
In mm/backing-dev.c (c05043d0)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/backing-dev.c:cgwb_release_workfn
```
```
In mm/slab_common.c (c050b8a0)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:destroy_memcg_params
```
```
In mm/gup.c (0)
Location: include/linux/rcupdate.h:703
Inline: True
```
```
In mm/slub.c (c054b21c)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (c055cacc)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_sk_free
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_event_remove
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:__memcg_kmem_uncharge
  - mm/memcontrol.c:__memcg_kmem_charge
  - mm/memcontrol.c:__memcg_kmem_charge
  - mm/memcontrol.c:memcg_kmem_put_cache
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:memcg_kmem_cache_create_func
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:drain_stock
  - mm/memcontrol.c:mem_cgroup_get_oom_group
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:get_mem_cgroup_from_page
  - mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node
```
```
In mm/hmm.c (c056659c)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/inode.c (c058dc94)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
```
```
In fs/file.c (c0591678)
Location: include/linux/rcupdate.h:703
Inline: True
```
```
In fs/fs-writeback.c (c05a7034)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:wbc_detach_inode
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/buffer.c (c05b1fdc)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - fs/buffer.c:alloc_page_buffers
```
```
In fs/block_dev.c (c05b9918)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_evict_inode
```
```
In fs/notify/group.c (c05c0648)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_put_group
```
```
In fs/aio.c (c05cfaf8)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - fs/aio.c:do_io_getevents
  - fs/aio.c:__se_sys_io_cancel
  - fs/aio.c:__se_sys_io_submit
  - fs/aio.c:__se_sys_io_submit
  - fs/aio.c:__se_sys_io_submit
  - fs/aio.c:__se_sys_io_submit
  - fs/aio.c:aio_poll_wake
  - fs/aio.c:aio_poll_complete_work
  - fs/aio.c:aio_poll_put_work
  - fs/aio.c:aio_fsync_work
  - fs/aio.c:aio_complete_rw
  - fs/aio.c:__se_sys_io_destroy
  - fs/aio.c:__se_sys_io_setup
  - fs/aio.c:__se_sys_io_setup
  - fs/aio.c:__se_sys_io_setup
  - fs/aio.c:lookup_ioctx
  - fs/aio.c:free_ioctx_users
```
```
In fs/io_uring.c (c05d7234)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - fs/io_uring.c:__se_sys_io_uring_enter
  - fs/io_uring.c:__se_sys_io_uring_enter
  - fs/io_uring.c:io_iopoll_getevents
  - fs/io_uring.c:io_iopoll_getevents
  - fs/io_uring.c:__io_free_req
  - fs/io_uring.c:io_get_req
  - fs/io_uring.c:io_get_req
```
```
In block/bio.c (c078831c)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - block/bio.c:__bio_associate_blkg
  - block/bio.c:__bio_associate_blkg
```
```
In block/blk-core.c (c07915d0)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_account_io_done
  - block/blk-core.c:direct_make_request
  - block/blk-core.c:generic_make_request
  - block/blk-core.c:blk_queue_enter
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-merge.c (c0797c54)
Location: include/linux/rcupdate.h:703
Inline: True
```
```
In block/blk-mq.c (c079aeb4)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_timeout_work
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/blk-mq-tag.c (c07a0364)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
```
In block/blk-mq-sched.c (c07a2840)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
```
In block/blk-cgroup.c (c07b906c)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:__blkg_release
  - block/blk-cgroup.c:__blkg_release
```
```
In block/blk-throttle.c (c07bc144)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:throtl_pop_queued
  - block/blk-throttle.c:throtl_qnode_add_bio
```
```
In lib/percpu-refcount.c (c07db4a4)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_resurrect
  - lib/percpu-refcount.c:percpu_ref_kill_and_confirm
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In drivers/block/loop.c (c0a07cf0)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_rq
  - drivers/block/loop.c:lo_rw_aio_complete
```
```
In drivers/dax/super.c (0)
Location: include/linux/rcupdate.h:703
Inline: True
```
```
In drivers/scsi/scsi_lib.c (c0a4c048)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_end_request
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/md/md.c (c0bccc70)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - drivers/md/md.c:md_write_end
```
```
In lib/bug.c (c0e7eed8)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - lib/bug.c:generic_bug_clear_once
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
In kernel/kthread.c (c000000000173520)
Location: include/linux/rcupdate.h:703
Inline: True
```
```
In kernel/sched/deadline.c (c0000000001ac47c)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_cpu_busy
  - kernel/sched/deadline.c:dl_cpuset_cpumask_can_shrink
  - kernel/sched/deadline.c:dl_task_can_attach
  - kernel/sched/deadline.c:sched_dl_do_global
  - kernel/sched/deadline.c:sched_dl_global_validate
```
```
In kernel/cgroup/cgroup.c (c0000000002462f0)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_free
  - kernel/cgroup/cgroup.c:cgroup_sk_free
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_get_from_fd
  - kernel/cgroup/cgroup.c:css_tryget_online_from_dir
  - kernel/cgroup/cgroup.c:kill_css
  - kernel/cgroup/cgroup.c:css_killed_work_fn
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - kernel/cgroup/cgroup.c:cgroup_do_get_tree
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
  - kernel/cgroup/cgroup.c:cgroup_kn_unlock
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/cgroup.c:cgroup_get_live
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/cgroup-v1.c (c00000000024a750)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In kernel/cgroup/legacy_freezer.c (c00000000024c82c)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_read
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (c00000000024e2d0)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
  - kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy
```
```
In kernel/cgroup/cpuset.c (c0000000002552f0)
Location: include/linux/rcupdate.h:703
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
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
```
In kernel/trace/ftrace.c (c00000000028e938)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:fpid_start
```
```
In kernel/trace/trace_events.c (c0000000002c7d28)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:p_start
```
```
In kernel/bpf/arraymap.c (c000000000324ab0)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr
```
```
In kernel/bpf/cgroup.c (c00000000033cc00)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_query
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_release
  - kernel/bpf/cgroup.c:cgroup_bpf_release
  - kernel/bpf/cgroup.c:cgroup_bpf_offline
```
```
In kernel/events/core.c (c00000000034be10)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - kernel/events/core.c:_free_event
```
```
In mm/oom_kill.c (c00000000036fab0)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
```
```
In mm/page-writeback.c (c000000000374b90)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/swap.c (c00000000037be40)
Location: include/linux/rcupdate.h:703
Inline: True
```
```
In mm/backing-dev.c (c00000000039f1a0)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/backing-dev.c:cgwb_release_workfn
```
```
In mm/slab_common.c (c0000000003a9538)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:destroy_memcg_params
```
```
In mm/gup.c (c0000000003b7140)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page
```
```
In mm/slub.c (c000000000424598)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (c00000000045ad80)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_sk_free
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_event_remove
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:__memcg_kmem_uncharge
  - mm/memcontrol.c:__memcg_kmem_charge
  - mm/memcontrol.c:__memcg_kmem_charge
  - mm/memcontrol.c:memcg_kmem_put_cache
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:memcg_kmem_cache_create_func
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:mem_cgroup_get_oom_group
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:get_mem_cgroup_from_page
  - mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node
```
```
In mm/hugetlb_cgroup.c (c00000000045d860)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In mm/memory-failure.c (c000000000461364)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
```
```
In mm/memremap.c (c00000000046da68)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - mm/memremap.c:get_dev_pagemap
  - mm/memremap.c:get_dev_pagemap
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memremap_pages
```
```
In mm/hmm.c (c000000000470a20)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/inode.c (c0000000004a8594)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
```
```
In fs/file.c (c0000000004ae0ac)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - fs/file.c:__fd_install
```
```
In fs/fs-writeback.c (c0000000004cc580)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:wbc_detach_inode
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/buffer.c (c0000000004dd2c0)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - fs/buffer.c:alloc_page_buffers
```
```
In fs/block_dev.c (c0000000004e73c8)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_evict_inode
```
```
In fs/notify/group.c (c0000000004efaa0)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_put_group
```
```
In fs/aio.c (c000000000505248)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - fs/aio.c:do_io_getevents
  - fs/aio.c:__se_sys_io_cancel
  - fs/aio.c:__se_compat_sys_io_submit
  - fs/aio.c:__se_sys_io_submit
  - fs/aio.c:io_submit_one
  - fs/aio.c:io_submit_one
  - fs/aio.c:io_submit_one
  - fs/aio.c:io_submit_one
  - fs/aio.c:aio_poll_wake
  - fs/aio.c:aio_poll_complete_work
  - fs/aio.c:aio_poll_put_work
  - fs/aio.c:aio_fsync_work
  - fs/aio.c:aio_complete_rw
  - fs/aio.c:__se_sys_io_destroy
  - fs/aio.c:__se_compat_sys_io_setup
  - fs/aio.c:__se_sys_io_setup
  - fs/aio.c:lookup_ioctx
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:free_ioctx_users
```
```
In fs/io_uring.c (c00000000050e738)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - fs/io_uring.c:__se_sys_io_uring_enter
  - fs/io_uring.c:__se_sys_io_uring_enter
  - fs/io_uring.c:io_iopoll_getevents
  - fs/io_uring.c:io_iopoll_getevents
  - fs/io_uring.c:__io_free_req
  - fs/io_uring.c:io_get_req
  - fs/io_uring.c:io_get_req
```
```
In block/bio.c (c00000000076b64c)
Location: include/linux/rcupdate.h:703
Inline: True
```
```
In block/blk-core.c (c000000000778034)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_account_io_done
  - block/blk-core.c:direct_make_request
  - block/blk-core.c:blk_queue_enter
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-merge.c (c000000000780cd0)
Location: include/linux/rcupdate.h:703
Inline: True
```
```
In block/blk-mq.c (c000000000783d68)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_timeout_work
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/blk-mq-tag.c (c00000000078c014)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
```
In block/blk-mq-sched.c (c00000000078f680)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
```
In block/blk-cgroup.c (c0000000007abdb0)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:__blkg_release
  - block/blk-cgroup.c:__blkg_release
```
```
In block/blk-throttle.c (c0000000007afa04)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:throtl_pop_queued
  - block/blk-throttle.c:throtl_qnode_add_bio
```
```
In lib/percpu-refcount.c (c0000000007dadb4)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_resurrect
  - lib/percpu-refcount.c:percpu_ref_kill_and_confirm
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In drivers/block/loop.c (c0000000009c7930)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_rq
  - drivers/block/loop.c:lo_rw_aio_complete
```
```
In drivers/dax/super.c (c000000000a19fd4)
Location: include/linux/rcupdate.h:703
Inline: True
```
```
In drivers/scsi/scsi_lib.c (c000000000a326d0)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_end_request
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/md/md.c (c000000000bd6e90)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - drivers/md/md.c:md_write_end
```
```
In lib/bug.c (c000000000ec2a38)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - lib/bug.c:generic_bug_clear_once
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
In kernel/kthread.c (ffffffe0000df53e)
Location: include/linux/rcupdate.h:703
Inline: True
```
```
In kernel/sched/deadline.c (ffffffe0000fe5e4)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_cpu_busy
  - kernel/sched/deadline.c:dl_cpuset_cpumask_can_shrink
  - kernel/sched/deadline.c:dl_task_can_attach
  - kernel/sched/deadline.c:sched_dl_do_global
  - kernel/sched/deadline.c:sched_dl_global_validate
```
```
In kernel/cgroup/cgroup.c (ffffffe000151dce)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_free
  - kernel/cgroup/cgroup.c:cgroup_sk_free
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_get_from_fd
  - kernel/cgroup/cgroup.c:css_tryget_online_from_dir
  - kernel/cgroup/cgroup.c:kill_css
  - kernel/cgroup/cgroup.c:css_killed_work_fn
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - kernel/cgroup/cgroup.c:cgroup_do_get_tree
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
  - kernel/cgroup/cgroup.c:cgroup_kn_unlock
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/cgroup.c:cgroup_get_live
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/cgroup-v1.c (ffffffe00015482c)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In kernel/cgroup/legacy_freezer.c (ffffffe000155c20)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_read
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (ffffffe000156b8e)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
  - kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy
```
```
In kernel/cgroup/cpuset.c (ffffffe00015ac72)
Location: include/linux/rcupdate.h:703
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
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
```
In kernel/trace/ftrace.c (ffffffe00017061c)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:fpid_start
```
```
In kernel/trace/trace_events.c (ffffffe000190c0e)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:p_start
```
```
In kernel/bpf/arraymap.c (ffffffe0001b30b8)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr
```
```
In kernel/bpf/cgroup.c (ffffffe0001c2b10)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_query
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_release
  - kernel/bpf/cgroup.c:cgroup_bpf_release
  - kernel/bpf/cgroup.c:cgroup_bpf_offline
```
```
In kernel/events/core.c (ffffffe0001c97ea)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - kernel/events/core.c:_free_event
```
```
In mm/oom_kill.c (ffffffe0001dbec4)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
```
```
In mm/page-writeback.c (ffffffe0001df326)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/swap.c (0)
Location: include/linux/rcupdate.h:703
Inline: True
```
```
In mm/backing-dev.c (ffffffe0001f735e)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/backing-dev.c:cgwb_release_workfn
```
```
In mm/slab_common.c (ffffffe0001fd2f8)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:destroy_memcg_params
```
```
In mm/gup.c (ffffffe000204bb4)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page
```
```
In mm/slub.c (ffffffe0002394c4)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (ffffffe000248af8)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_sk_free
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_event_remove
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:__memcg_kmem_uncharge
  - mm/memcontrol.c:__memcg_kmem_charge
  - mm/memcontrol.c:__memcg_kmem_charge
  - mm/memcontrol.c:memcg_kmem_put_cache
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:memcg_kmem_cache_create_func
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:mem_cgroup_get_oom_group
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:get_mem_cgroup_from_page
  - mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node
```
```
In mm/hugetlb_cgroup.c (ffffffe00024a416)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In mm/hmm.c (ffffffe000251fea)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/inode.c (ffffffe000271be2)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
```
```
In fs/file.c (ffffffe00027631a)
Location: include/linux/rcupdate.h:703
Inline: True
```
```
In fs/fs-writeback.c (ffffffe000288c20)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:wbc_detach_inode
  - fs/fs-writeback.c:wbc_attach_and_unlock_inode
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/buffer.c (ffffffe000291df4)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - fs/buffer.c:alloc_page_buffers
```
```
In fs/block_dev.c (ffffffe000297c1a)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_evict_inode
```
```
In fs/notify/group.c (ffffffe00029d9d2)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_final_destroy_group
```
```
In fs/aio.c (ffffffe0002aa16e)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - fs/aio.c:do_io_getevents
  - fs/aio.c:__se_sys_io_cancel
  - fs/aio.c:__se_sys_io_submit
  - fs/aio.c:aio_poll_wake
  - fs/aio.c:aio_poll_complete_work
  - fs/aio.c:aio_poll_put_work
  - fs/aio.c:aio_fsync_work
  - fs/aio.c:aio_complete_rw
  - fs/aio.c:__se_sys_io_destroy
  - fs/aio.c:__se_sys_io_setup
  - fs/aio.c:__se_sys_io_setup
  - fs/aio.c:__se_sys_io_setup
  - fs/aio.c:lookup_ioctx
  - fs/aio.c:free_ioctx_users
```
```
In fs/io_uring.c (ffffffe0002b0d78)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - fs/io_uring.c:__se_sys_io_uring_enter
  - fs/io_uring.c:__se_sys_io_uring_enter
  - fs/io_uring.c:io_iopoll_getevents
  - fs/io_uring.c:io_iopoll_getevents
  - fs/io_uring.c:__io_free_req
  - fs/io_uring.c:io_get_req
  - fs/io_uring.c:io_get_req
```
```
In block/bio.c (ffffffe00041e3f0)
Location: include/linux/rcupdate.h:703
Inline: True
```
```
In block/blk-core.c (ffffffe000425b5c)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_account_io_done
  - block/blk-core.c:direct_make_request
  - block/blk-core.c:blk_queue_enter
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-merge.c (ffffffe00042b718)
Location: include/linux/rcupdate.h:703
Inline: True
```
```
In block/blk-mq.c (ffffffe00042d436)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_timeout_work
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/blk-mq-tag.c (ffffffe0004326d0)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
```
In block/blk-mq-sched.c (ffffffe0004347f2)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
```
In block/blk-cgroup.c (ffffffe000446cec)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:__blkg_release
  - block/blk-cgroup.c:__blkg_release
```
```
In block/blk-throttle.c (ffffffe0004492a4)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:throtl_pop_queued
  - block/blk-throttle.c:throtl_qnode_add_bio
```
```
In lib/percpu-refcount.c (ffffffe000462e44)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_resurrect
  - lib/percpu-refcount.c:percpu_ref_kill_and_confirm
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In drivers/block/loop.c (ffffffe0005a1076)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_rq
  - drivers/block/loop.c:lo_rw_aio_complete
```
```
In drivers/dax/super.c (0)
Location: include/linux/rcupdate.h:703
Inline: True
```
```
In drivers/scsi/scsi_lib.c (ffffffe0005dfce2)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_end_request
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/md/md.c (ffffffe0006de2ec)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - drivers/md/md.c:md_write_end
```
```
In lib/bug.c (ffffffe0008ae1fe)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - lib/bug.c:generic_bug_clear_once
  - lib/bug.c:module_find_bug
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
In kernel/kthread.c (ffffffff810c3357)
Location: include/linux/rcupdate.h:703
Inline: True
```
```
In kernel/sched/deadline.c (ffffffff810ee425)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_cpu_busy
  - kernel/sched/deadline.c:dl_cpuset_cpumask_can_shrink
  - kernel/sched/deadline.c:dl_task_can_attach
  - kernel/sched/deadline.c:sched_dl_do_global
  - kernel/sched/deadline.c:sched_dl_global_validate
```
```
In kernel/cgroup/cgroup.c (ffffffff8115f56f)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_free
  - kernel/cgroup/cgroup.c:cgroup_sk_free
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_get_from_fd
  - kernel/cgroup/cgroup.c:css_tryget_online_from_dir
  - kernel/cgroup/cgroup.c:kill_css
  - kernel/cgroup/cgroup.c:css_killed_work_fn
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - kernel/cgroup/cgroup.c:cgroup_do_get_tree
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
  - kernel/cgroup/cgroup.c:cgroup_kn_unlock
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/cgroup.c:cgroup_get_live
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81161b47)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff81162ef4)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_read
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (ffffffff81163e7c)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
  - kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy
```
```
In kernel/cgroup/cpuset.c (ffffffff81169a13)
Location: include/linux/rcupdate.h:703
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
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
```
In kernel/trace/ftrace.c (ffffffff8118fa2a)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:fpid_start
```
```
In kernel/trace/trace_events.c (ffffffff811b3d8a)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:p_start
```
```
In kernel/bpf/arraymap.c (ffffffff811ef1fc)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr
```
```
In kernel/bpf/cgroup.c (ffffffff811fee29)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_query
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_release
  - kernel/bpf/cgroup.c:cgroup_bpf_release
  - kernel/bpf/cgroup.c:cgroup_bpf_offline
```
```
In kernel/events/core.c (ffffffff8120813c)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_free_event
```
```
In mm/oom_kill.c (ffffffff812223bc)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
```
```
In mm/page-writeback.c (ffffffff81225cca)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/swap.c (ffffffff8122a715)
Location: include/linux/rcupdate.h:703
Inline: True
```
```
In mm/backing-dev.c (ffffffff81242493)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/backing-dev.c:cgwb_release_workfn
```
```
In mm/slab_common.c (ffffffff81248d63)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:destroy_memcg_params
```
```
In mm/gup.c (ffffffff81251af5)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page
```
```
In mm/slub.c (ffffffff8129dd94)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (ffffffff812c0ad7)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_sk_free
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_event_remove
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:__memcg_kmem_uncharge
  - mm/memcontrol.c:__memcg_kmem_charge
  - mm/memcontrol.c:__memcg_kmem_charge
  - mm/memcontrol.c:memcg_kmem_put_cache
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:memcg_kmem_cache_create_func
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:mem_cgroup_get_oom_group
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:get_mem_cgroup_from_page
  - mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node
```
```
In mm/hugetlb_cgroup.c (ffffffff812c2434)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In mm/memory-failure.c (ffffffff812c46ff)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
```
```
In mm/memremap.c (ffffffff812cc99c)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - mm/memremap.c:get_dev_pagemap
  - mm/memremap.c:get_dev_pagemap
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memremap_pages
```
```
In mm/hmm.c (ffffffff812cef94)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/inode.c (ffffffff812f51d8)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
```
```
In fs/file.c (ffffffff812f8b65)
Location: include/linux/rcupdate.h:703
Inline: True
```
```
In fs/fs-writeback.c (ffffffff8130d104)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:wbc_detach_inode
  - fs/fs-writeback.c:wbc_attach_and_unlock_inode
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/buffer.c (ffffffff81318bcf)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - fs/buffer.c:alloc_page_buffers
```
```
In fs/block_dev.c (ffffffff8131eee4)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_evict_inode
```
```
In fs/notify/group.c (ffffffff8132571b)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_put_group
```
```
In fs/aio.c (ffffffff813350da)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - fs/aio.c:do_io_getevents
  - fs/aio.c:__ia32_sys_io_cancel
  - fs/aio.c:__x64_sys_io_cancel
  - fs/aio.c:__x32_compat_sys_io_submit
  - fs/aio.c:__ia32_compat_sys_io_submit
  - fs/aio.c:__ia32_sys_io_submit
  - fs/aio.c:__x64_sys_io_submit
  - fs/aio.c:io_submit_one
  - fs/aio.c:io_submit_one
  - fs/aio.c:io_submit_one
  - fs/aio.c:aio_poll_complete_work
  - fs/aio.c:aio_poll_put_work
  - fs/aio.c:aio_fsync_work
  - fs/aio.c:aio_complete_rw
  - fs/aio.c:__ia32_sys_io_destroy
  - fs/aio.c:__x64_sys_io_destroy
  - fs/aio.c:__x32_compat_sys_io_setup
  - fs/aio.c:__ia32_compat_sys_io_setup
  - fs/aio.c:__ia32_sys_io_setup
  - fs/aio.c:__x64_sys_io_setup
  - fs/aio.c:lookup_ioctx
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:free_ioctx_users
```
```
In fs/io_uring.c (ffffffff8133c2b6)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - fs/io_uring.c:__ia32_sys_io_uring_enter
  - fs/io_uring.c:__ia32_sys_io_uring_enter
  - fs/io_uring.c:__x64_sys_io_uring_enter
  - fs/io_uring.c:__x64_sys_io_uring_enter
  - fs/io_uring.c:io_iopoll_getevents
  - fs/io_uring.c:io_iopoll_getevents
  - fs/io_uring.c:__io_free_req
  - fs/io_uring.c:io_get_req
  - fs/io_uring.c:io_get_req
```
```
In block/bio.c (ffffffff814d6999)
Location: include/linux/rcupdate.h:703
Inline: True
```
```
In block/blk-core.c (ffffffff814df082)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_account_io_done
  - block/blk-core.c:direct_make_request
  - block/blk-core.c:blk_queue_enter
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-merge.c (ffffffff814e5293)
Location: include/linux/rcupdate.h:703
Inline: True
```
```
In block/blk-mq.c (ffffffff814e740c)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_timeout_work
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/blk-mq-tag.c (ffffffff814eced4)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
```
In block/blk-mq-sched.c (ffffffff814ef02f)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
```
In block/blk-cgroup.c (ffffffff81503529)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:__blkg_release
  - block/blk-cgroup.c:__blkg_release
```
```
In block/blk-throttle.c (ffffffff81506354)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:throtl_pop_queued
  - block/blk-throttle.c:throtl_qnode_add_bio
```
```
In lib/percpu-refcount.c (ffffffff815228e8)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_resurrect
  - lib/percpu-refcount.c:percpu_ref_kill_and_confirm
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In drivers/block/loop.c (ffffffff816f21e6)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_rq
  - drivers/block/loop.c:lo_rw_aio_complete
```
```
In drivers/dax/super.c (ffffffff8171808e)
Location: include/linux/rcupdate.h:703
Inline: True
```
```
In drivers/scsi/scsi_lib.c (ffffffff817288e9)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_end_request
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/md/md.c (ffffffff8183b8b5)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - drivers/md/md.c:md_write_end
```
```
In lib/bug.c (ffffffff81a4c750)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - lib/bug.c:generic_bug_clear_once
  - lib/bug.c:module_find_bug
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
In kernel/kthread.c (ffffffff810b1b97)
Location: include/linux/rcupdate.h:703
Inline: True
```
```
In kernel/sched/deadline.c (ffffffff810de4b5)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_cpu_busy
  - kernel/sched/deadline.c:dl_cpuset_cpumask_can_shrink
  - kernel/sched/deadline.c:dl_task_can_attach
  - kernel/sched/deadline.c:sched_dl_do_global
  - kernel/sched/deadline.c:sched_dl_global_validate
```
```
In kernel/cgroup/cgroup.c (ffffffff811527ff)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_free
  - kernel/cgroup/cgroup.c:cgroup_sk_free
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_get_from_fd
  - kernel/cgroup/cgroup.c:css_tryget_online_from_dir
  - kernel/cgroup/cgroup.c:kill_css
  - kernel/cgroup/cgroup.c:css_killed_work_fn
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - kernel/cgroup/cgroup.c:cgroup_do_get_tree
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
  - kernel/cgroup/cgroup.c:cgroup_kn_unlock
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/cgroup.c:cgroup_get_live
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81154da7)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff81156144)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_read
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (ffffffff811570cc)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
  - kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy
```
```
In kernel/cgroup/cpuset.c (ffffffff8115cc13)
Location: include/linux/rcupdate.h:703
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
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
```
In kernel/trace/ftrace.c (ffffffff81182b6a)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:fpid_start
```
```
In kernel/trace/trace_events.c (ffffffff811a6b8a)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:p_start
```
```
In kernel/bpf/arraymap.c (ffffffff811e1f8c)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr
```
```
In kernel/bpf/cgroup.c (ffffffff811f1b79)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_query
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_release
  - kernel/bpf/cgroup.c:cgroup_bpf_release
  - kernel/bpf/cgroup.c:cgroup_bpf_offline
```
```
In kernel/events/core.c (ffffffff811fb263)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_free_event
```
```
In mm/oom_kill.c (ffffffff8121556c)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
```
```
In mm/page-writeback.c (ffffffff81218e6a)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/swap.c (ffffffff8121d835)
Location: include/linux/rcupdate.h:703
Inline: True
```
```
In mm/backing-dev.c (ffffffff81235463)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/backing-dev.c:cgwb_release_workfn
```
```
In mm/slab_common.c (ffffffff8123bd0d)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:destroy_memcg_params
```
```
In mm/gup.c (ffffffff81244a8c)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page
```
```
In mm/slub.c (ffffffff8128f910)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (ffffffff812b1b63)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_sk_free
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_event_remove
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:__memcg_kmem_uncharge
  - mm/memcontrol.c:__memcg_kmem_charge
  - mm/memcontrol.c:__memcg_kmem_charge
  - mm/memcontrol.c:memcg_kmem_put_cache
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:memcg_kmem_cache_create_func
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:mem_cgroup_get_oom_group
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:get_mem_cgroup_from_page
  - mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node
```
```
In mm/hugetlb_cgroup.c (ffffffff812b3484)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In mm/memory-failure.c (ffffffff812b573f)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
```
```
In mm/memremap.c (ffffffff812bd80c)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - mm/memremap.c:get_dev_pagemap
  - mm/memremap.c:get_dev_pagemap
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memremap_pages
```
```
In mm/hmm.c (ffffffff812bfc26)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/inode.c (ffffffff812e5df8)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
```
```
In fs/file.c (ffffffff812e9785)
Location: include/linux/rcupdate.h:703
Inline: True
```
```
In fs/fs-writeback.c (ffffffff812fdd14)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:wbc_detach_inode
  - fs/fs-writeback.c:wbc_attach_and_unlock_inode
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/buffer.c (ffffffff813097bf)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - fs/buffer.c:alloc_page_buffers
```
```
In fs/block_dev.c (ffffffff8130fa84)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_evict_inode
```
```
In fs/notify/group.c (ffffffff813162bb)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_put_group
```
```
In fs/aio.c (ffffffff81325a6a)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - fs/aio.c:do_io_getevents
  - fs/aio.c:__ia32_sys_io_cancel
  - fs/aio.c:__x64_sys_io_cancel
  - fs/aio.c:__x32_compat_sys_io_submit
  - fs/aio.c:__ia32_compat_sys_io_submit
  - fs/aio.c:__ia32_sys_io_submit
  - fs/aio.c:__x64_sys_io_submit
  - fs/aio.c:io_submit_one
  - fs/aio.c:io_submit_one
  - fs/aio.c:io_submit_one
  - fs/aio.c:aio_poll_wake
  - fs/aio.c:aio_poll_complete_work
  - fs/aio.c:aio_poll_put_work
  - fs/aio.c:aio_fsync_work
  - fs/aio.c:aio_complete_rw
  - fs/aio.c:__ia32_sys_io_destroy
  - fs/aio.c:__x64_sys_io_destroy
  - fs/aio.c:__x32_compat_sys_io_setup
  - fs/aio.c:__ia32_compat_sys_io_setup
  - fs/aio.c:__ia32_sys_io_setup
  - fs/aio.c:__x64_sys_io_setup
  - fs/aio.c:lookup_ioctx
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:free_ioctx_users
```
```
In fs/io_uring.c (ffffffff8132cf86)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - fs/io_uring.c:__ia32_sys_io_uring_enter
  - fs/io_uring.c:__ia32_sys_io_uring_enter
  - fs/io_uring.c:__x64_sys_io_uring_enter
  - fs/io_uring.c:__x64_sys_io_uring_enter
  - fs/io_uring.c:io_iopoll_getevents
  - fs/io_uring.c:io_iopoll_getevents
  - fs/io_uring.c:__io_free_req
  - fs/io_uring.c:io_get_req
  - fs/io_uring.c:io_get_req
```
```
In block/bio.c (ffffffff814c7359)
Location: include/linux/rcupdate.h:703
Inline: True
```
```
In block/blk-core.c (ffffffff814cfa22)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_account_io_done
  - block/blk-core.c:direct_make_request
  - block/blk-core.c:blk_queue_enter
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-merge.c (ffffffff814d5942)
Location: include/linux/rcupdate.h:703
Inline: True
```
```
In block/blk-mq.c (ffffffff814d797c)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_timeout_work
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/blk-mq-tag.c (ffffffff814dd424)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
```
In block/blk-mq-sched.c (ffffffff814df56f)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
```
In block/blk-cgroup.c (ffffffff814f39e9)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:__blkg_release
  - block/blk-cgroup.c:__blkg_release
```
```
In block/blk-throttle.c (ffffffff814f6814)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:throtl_pop_queued
  - block/blk-throttle.c:throtl_qnode_add_bio
```
```
In lib/percpu-refcount.c (ffffffff81512bc8)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_resurrect
  - lib/percpu-refcount.c:percpu_ref_kill_and_confirm
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In drivers/block/loop.c (ffffffff816cc2e6)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_rq
  - drivers/block/loop.c:lo_rw_aio_complete
```
```
In drivers/dax/super.c (ffffffff816f05be)
Location: include/linux/rcupdate.h:703
Inline: True
```
```
In drivers/scsi/scsi_lib.c (ffffffff81701d19)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_end_request
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/md/md.c (ffffffff81802f15)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - drivers/md/md.c:md_write_end
```
```
In lib/bug.c (ffffffff81a09880)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - lib/bug.c:generic_bug_clear_once
  - lib/bug.c:module_find_bug
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
In kernel/kthread.c (ffffffff810c28a7)
Location: include/linux/rcupdate.h:703
Inline: True
```
```
In kernel/sched/deadline.c (ffffffff810eb555)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_cpu_busy
  - kernel/sched/deadline.c:dl_cpuset_cpumask_can_shrink
  - kernel/sched/deadline.c:dl_task_can_attach
  - kernel/sched/deadline.c:sched_dl_do_global
  - kernel/sched/deadline.c:sched_dl_global_validate
```
```
In kernel/cgroup/cgroup.c (ffffffff8115d33f)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_free
  - kernel/cgroup/cgroup.c:cgroup_sk_free
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_get_from_fd
  - kernel/cgroup/cgroup.c:css_tryget_online_from_dir
  - kernel/cgroup/cgroup.c:kill_css
  - kernel/cgroup/cgroup.c:css_killed_work_fn
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - kernel/cgroup/cgroup.c:cgroup_do_get_tree
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
  - kernel/cgroup/cgroup.c:cgroup_kn_unlock
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/cgroup.c:cgroup_get_live
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8115f917)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff81160cc4)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_read
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (ffffffff81161c4c)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
  - kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy
```
```
In kernel/cgroup/cpuset.c (ffffffff811677e3)
Location: include/linux/rcupdate.h:703
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
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
```
In kernel/trace/ftrace.c (ffffffff8118d7fa)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:fpid_start
```
```
In kernel/trace/trace_events.c (ffffffff811b1b5a)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:p_start
```
```
In kernel/bpf/arraymap.c (ffffffff811ecfcc)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr
```
```
In kernel/bpf/cgroup.c (ffffffff811fcbf9)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_query
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_release
  - kernel/bpf/cgroup.c:cgroup_bpf_release
  - kernel/bpf/cgroup.c:cgroup_bpf_offline
```
```
In kernel/events/core.c (ffffffff81205f0c)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_free_event
```
```
In mm/oom_kill.c (ffffffff8122015c)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
```
```
In mm/page-writeback.c (ffffffff81223a6a)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/swap.c (ffffffff812284b5)
Location: include/linux/rcupdate.h:703
Inline: True
```
```
In mm/backing-dev.c (ffffffff81240233)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/backing-dev.c:cgwb_release_workfn
```
```
In mm/slab_common.c (ffffffff81246b03)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:destroy_memcg_params
```
```
In mm/gup.c (ffffffff8124f895)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page
```
```
In mm/slub.c (ffffffff8129bba4)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (ffffffff812be8e7)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_sk_free
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_event_remove
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:__memcg_kmem_uncharge
  - mm/memcontrol.c:__memcg_kmem_charge
  - mm/memcontrol.c:__memcg_kmem_charge
  - mm/memcontrol.c:memcg_kmem_put_cache
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:memcg_kmem_cache_create_func
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:mem_cgroup_get_oom_group
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:get_mem_cgroup_from_page
  - mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node
```
```
In mm/hugetlb_cgroup.c (ffffffff812c0244)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In mm/memory-failure.c (ffffffff812c250f)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
```
```
In mm/memremap.c (ffffffff812ca7ac)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - mm/memremap.c:get_dev_pagemap
  - mm/memremap.c:get_dev_pagemap
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memremap_pages
```
```
In mm/hmm.c (ffffffff812ccda4)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/inode.c (ffffffff812f2fe8)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
```
```
In fs/file.c (ffffffff812f6975)
Location: include/linux/rcupdate.h:703
Inline: True
```
```
In fs/fs-writeback.c (ffffffff8130aef4)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:wbc_detach_inode
  - fs/fs-writeback.c:wbc_attach_and_unlock_inode
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/buffer.c (ffffffff8131669f)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - fs/buffer.c:alloc_page_buffers
```
```
In fs/block_dev.c (ffffffff8131c9b4)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_evict_inode
```
```
In fs/notify/group.c (ffffffff813231eb)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_put_group
```
```
In fs/aio.c (ffffffff81332baa)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - fs/aio.c:do_io_getevents
  - fs/aio.c:__ia32_sys_io_cancel
  - fs/aio.c:__x64_sys_io_cancel
  - fs/aio.c:__x32_compat_sys_io_submit
  - fs/aio.c:__ia32_compat_sys_io_submit
  - fs/aio.c:__ia32_sys_io_submit
  - fs/aio.c:__x64_sys_io_submit
  - fs/aio.c:io_submit_one
  - fs/aio.c:io_submit_one
  - fs/aio.c:io_submit_one
  - fs/aio.c:aio_poll_complete_work
  - fs/aio.c:aio_poll_put_work
  - fs/aio.c:aio_fsync_work
  - fs/aio.c:aio_complete_rw
  - fs/aio.c:__ia32_sys_io_destroy
  - fs/aio.c:__x64_sys_io_destroy
  - fs/aio.c:__x32_compat_sys_io_setup
  - fs/aio.c:__ia32_compat_sys_io_setup
  - fs/aio.c:__ia32_sys_io_setup
  - fs/aio.c:__x64_sys_io_setup
  - fs/aio.c:lookup_ioctx
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:free_ioctx_users
```
```
In fs/io_uring.c (ffffffff81339d86)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - fs/io_uring.c:__ia32_sys_io_uring_enter
  - fs/io_uring.c:__ia32_sys_io_uring_enter
  - fs/io_uring.c:__x64_sys_io_uring_enter
  - fs/io_uring.c:__x64_sys_io_uring_enter
  - fs/io_uring.c:io_iopoll_getevents
  - fs/io_uring.c:io_iopoll_getevents
  - fs/io_uring.c:__io_free_req
  - fs/io_uring.c:io_get_req
  - fs/io_uring.c:io_get_req
```
```
In block/bio.c (ffffffff814d2a29)
Location: include/linux/rcupdate.h:703
Inline: True
```
```
In block/blk-core.c (ffffffff814db112)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_account_io_done
  - block/blk-core.c:direct_make_request
  - block/blk-core.c:blk_queue_enter
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-merge.c (ffffffff814e1323)
Location: include/linux/rcupdate.h:703
Inline: True
```
```
In block/blk-mq.c (ffffffff814e349c)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_timeout_work
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/blk-mq-tag.c (ffffffff814e8f64)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
```
In block/blk-mq-sched.c (ffffffff814eb0bf)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
```
In block/blk-cgroup.c (ffffffff814ff5b9)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:__blkg_release
  - block/blk-cgroup.c:__blkg_release
```
```
In block/blk-throttle.c (ffffffff815023e4)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:throtl_pop_queued
  - block/blk-throttle.c:throtl_qnode_add_bio
```
```
In lib/percpu-refcount.c (ffffffff8151e978)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_resurrect
  - lib/percpu-refcount.c:percpu_ref_kill_and_confirm
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In drivers/block/loop.c (ffffffff8171f8c6)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_rq
  - drivers/block/loop.c:lo_rw_aio_complete
```
```
In drivers/dax/super.c (ffffffff81756e5e)
Location: include/linux/rcupdate.h:703
Inline: True
```
```
In drivers/scsi/scsi_lib.c (ffffffff817676b9)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_end_request
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/md/md.c (ffffffff8188aee5)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - drivers/md/md.c:md_write_end
```
```
In lib/bug.c (ffffffff81ab8b40)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - lib/bug.c:generic_bug_clear_once
  - lib/bug.c:module_find_bug
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
In kernel/kthread.c (ffffffff810caeac)
Location: include/linux/rcupdate.h:703
Inline: True
```
```
In kernel/sched/deadline.c (ffffffff810f6595)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_cpu_busy
  - kernel/sched/deadline.c:dl_cpuset_cpumask_can_shrink
  - kernel/sched/deadline.c:dl_task_can_attach
  - kernel/sched/deadline.c:sched_dl_do_global
  - kernel/sched/deadline.c:sched_dl_global_validate
```
```
In kernel/cgroup/cgroup.c (ffffffff8116a53f)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_free
  - kernel/cgroup/cgroup.c:cgroup_sk_free
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_get_from_fd
  - kernel/cgroup/cgroup.c:css_tryget_online_from_dir
  - kernel/cgroup/cgroup.c:kill_css
  - kernel/cgroup/cgroup.c:css_killed_work_fn
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - kernel/cgroup/cgroup.c:cgroup_do_get_tree
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
  - kernel/cgroup/cgroup.c:cgroup_kn_unlock
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/cgroup.c:cgroup_get_live
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8116cbc2)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff8116e0d2)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_read
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (ffffffff8116f0ae)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
  - kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy
```
```
In kernel/cgroup/cpuset.c (ffffffff81174e5a)
Location: include/linux/rcupdate.h:703
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
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
```
In kernel/trace/ftrace.c (ffffffff8119b38a)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:fpid_start
```
```
In kernel/trace/trace_events.c (ffffffff811bfbfa)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:p_start
```
```
In kernel/bpf/arraymap.c (ffffffff811fb46c)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr
```
```
In kernel/bpf/cgroup.c (ffffffff8120b889)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_query
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_release
  - kernel/bpf/cgroup.c:cgroup_bpf_release
  - kernel/bpf/cgroup.c:cgroup_bpf_offline
```
```
In kernel/events/core.c (ffffffff81214daa)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_free_event
```
```
In mm/oom_kill.c (ffffffff8122f268)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
```
```
In mm/page-writeback.c (ffffffff81232e72)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/swap.c (ffffffff81237805)
Location: include/linux/rcupdate.h:703
Inline: True
```
```
In mm/backing-dev.c (ffffffff8124f965)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/backing-dev.c:cgwb_release_workfn
```
```
In mm/slab_common.c (ffffffff8125630f)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:destroy_memcg_params
```
```
In mm/gup.c (ffffffff8125f205)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page
```
```
In mm/slub.c (ffffffff812aba8e)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (ffffffff812cf347)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_sk_free
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_event_remove
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:__memcg_kmem_uncharge
  - mm/memcontrol.c:__memcg_kmem_charge
  - mm/memcontrol.c:__memcg_kmem_charge
  - mm/memcontrol.c:memcg_kmem_put_cache
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:memcg_kmem_cache_create_func
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:mem_cgroup_get_oom_group
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:get_mem_cgroup_from_page
  - mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node
```
```
In mm/hugetlb_cgroup.c (ffffffff812d0d1a)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In mm/memory-failure.c (ffffffff812d2f9a)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
```
```
In mm/memremap.c (ffffffff812db4ae)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - mm/memremap.c:get_dev_pagemap
  - mm/memremap.c:get_dev_pagemap
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memremap_pages
```
```
In mm/hmm.c (ffffffff812ddb34)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/inode.c (ffffffff81304918)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
```
```
In fs/file.c (ffffffff81307ba5)
Location: include/linux/rcupdate.h:703
Inline: True
```
```
In fs/fs-writeback.c (ffffffff8131c64c)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:wbc_detach_inode
  - fs/fs-writeback.c:wbc_attach_and_unlock_inode
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/buffer.c (ffffffff8132848f)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - fs/buffer.c:alloc_page_buffers
```
```
In fs/block_dev.c (ffffffff8132ea92)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_evict_inode
```
```
In fs/notify/group.c (ffffffff81334f2b)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_put_group
```
```
In fs/aio.c (ffffffff81345d3a)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - fs/aio.c:do_io_getevents
  - fs/aio.c:__ia32_sys_io_cancel
  - fs/aio.c:__x64_sys_io_cancel
  - fs/aio.c:__x32_compat_sys_io_submit
  - fs/aio.c:__ia32_compat_sys_io_submit
  - fs/aio.c:__ia32_sys_io_submit
  - fs/aio.c:__x64_sys_io_submit
  - fs/aio.c:io_submit_one
  - fs/aio.c:io_submit_one
  - fs/aio.c:io_submit_one
  - fs/aio.c:aio_poll_wake
  - fs/aio.c:aio_poll_complete_work
  - fs/aio.c:aio_poll_put_work
  - fs/aio.c:aio_fsync_work
  - fs/aio.c:aio_complete_rw
  - fs/aio.c:__ia32_sys_io_destroy
  - fs/aio.c:__x64_sys_io_destroy
  - fs/aio.c:__x32_compat_sys_io_setup
  - fs/aio.c:__ia32_compat_sys_io_setup
  - fs/aio.c:__ia32_sys_io_setup
  - fs/aio.c:__x64_sys_io_setup
  - fs/aio.c:lookup_ioctx
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:free_ioctx_users
```
```
In fs/io_uring.c (ffffffff8134d750)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - fs/io_uring.c:__ia32_sys_io_uring_enter
  - fs/io_uring.c:__ia32_sys_io_uring_enter
  - fs/io_uring.c:__x64_sys_io_uring_enter
  - fs/io_uring.c:__x64_sys_io_uring_enter
  - fs/io_uring.c:io_iopoll_getevents
  - fs/io_uring.c:io_iopoll_getevents
  - fs/io_uring.c:__io_free_req
  - fs/io_uring.c:io_get_req
  - fs/io_uring.c:io_get_req
```
```
In block/bio.c (ffffffff814eb549)
Location: include/linux/rcupdate.h:703
Inline: True
```
```
In block/blk-core.c (ffffffff814f3f18)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_account_io_done
  - block/blk-core.c:direct_make_request
  - block/blk-core.c:blk_queue_enter
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-merge.c (ffffffff814fa1af)
Location: include/linux/rcupdate.h:703
Inline: True
```
```
In block/blk-mq.c (ffffffff814fc38c)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_timeout_work
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/blk-mq-tag.c (ffffffff81501f04)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
```
In block/blk-mq-sched.c (ffffffff81504096)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
```
In block/blk-cgroup.c (ffffffff8151873e)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:__blkg_release
  - block/blk-cgroup.c:__blkg_release
```
```
In block/blk-throttle.c (ffffffff8151b724)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:throtl_pop_queued
  - block/blk-throttle.c:throtl_qnode_add_bio
```
```
In lib/percpu-refcount.c (ffffffff81538218)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_resurrect
  - lib/percpu-refcount.c:percpu_ref_kill_and_confirm
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In drivers/block/loop.c (ffffffff8173ad06)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_rq
  - drivers/block/loop.c:lo_rw_aio_complete
```
```
In drivers/dax/super.c (ffffffff817722be)
Location: include/linux/rcupdate.h:703
Inline: True
```
```
In drivers/scsi/scsi_lib.c (ffffffff81782dce)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_end_request
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/md/md.c (ffffffff818aa125)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - drivers/md/md.c:md_write_end
```
```
In lib/bug.c (ffffffff81ac4f70)
Location: include/linux/rcupdate.h:703
Inline: True
Inline callers:
  - lib/bug.c:generic_bug_clear_once
  - lib/bug.c:module_find_bug
```
</details>
</li>
</ul>

## Differences
