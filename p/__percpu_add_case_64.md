# Function: <code>__percpu_add_case_64</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void __percpu_add_case_64(void *ptr, long unsigned int val);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffff8000101288a8)
Location: arch/arm64/include/asm/percpu.h:112
Inline: True
```
```
In kernel/rcu/srcutree.c (ffff80001018a130)
Location: arch/arm64/include/asm/percpu.h:112
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:__srcu_read_unlock
  - kernel/rcu/srcutree.c:__srcu_read_lock
```
```
In kernel/cgroup/cgroup.c (ffff8000101d8d80)
Location: arch/arm64/include/asm/percpu.h:112
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
In kernel/cgroup/cgroup-v1.c (ffff8000101dc8b0)
Location: arch/arm64/include/asm/percpu.h:112
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In kernel/cgroup/legacy_freezer.c (ffff8000101de784)
Location: arch/arm64/include/asm/percpu.h:112
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_read
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (ffff8000101dfbb4)
Location: arch/arm64/include/asm/percpu.h:112
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
  - kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy
```
```
In kernel/cgroup/cpuset.c (ffff8000101e4a7c)
Location: arch/arm64/include/asm/percpu.h:112
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
In kernel/bpf/arraymap.c (ffff80001027b8d8)
Location: arch/arm64/include/asm/percpu.h:112
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr
```
```
In kernel/bpf/cgroup.c (ffff80001028ff14)
Location: arch/arm64/include/asm/percpu.h:112
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
In kernel/events/core.c (ffff80001029bcbc)
Location: arch/arm64/include/asm/percpu.h:112
Inline: True
Inline callers:
  - kernel/events/core.c:_free_event
```
```
In mm/filemap.c (ffff8000102b2720)
Location: arch/arm64/include/asm/percpu.h:112
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
```
```
In mm/oom_kill.c (ffff8000102b7c68)
Location: arch/arm64/include/asm/percpu.h:112
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/page-writeback.c (ffff8000102bc510)
Location: arch/arm64/include/asm/percpu.h:112
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/swap.c (ffff8000102c1330)
Location: arch/arm64/include/asm/percpu.h:112
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_cache_add_active_or_unevictable
```
```
In mm/vmscan.c (ffff8000102cd8f4)
Location: arch/arm64/include/asm/percpu.h:112
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:do_shrink_slab
```
```
In mm/shmem.c (ffff8000102d3b24)
Location: arch/arm64/include/asm/percpu.h:112
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/vmstat.c (ffff8000102dbb74)
Location: arch/arm64/include/asm/percpu.h:112
Inline: True
Inline callers:
  - mm/vmstat.c:vm_events_fold_cpu
```
```
In mm/backing-dev.c (ffff8000102df548)
Location: arch/arm64/include/asm/percpu.h:112
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/backing-dev.c:cgwb_release_workfn
```
```
In mm/slab_common.c (ffff8000102e777c)
Location: arch/arm64/include/asm/percpu.h:112
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:destroy_memcg_params
```
```
In mm/compaction.c (ffff8000102ecf7c)
Location: arch/arm64/include/asm/percpu.h:112
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_do_work
  - mm/compaction.c:kcompactd_do_work
  - mm/compaction.c:kcompactd_do_work
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:fast_isolate_freepages
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
```
```
In mm/gup.c (ffff8000102f26f0)
Location: arch/arm64/include/asm/percpu.h:112
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page
```
```
In mm/memory.c (ffff8000102fa324)
Location: arch/arm64/include/asm/percpu.h:112
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_swap_page
```
```
In mm/mlock.c (ffff8000102fdb0c)
Location: arch/arm64/include/asm/percpu.h:112
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_isolated_page
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
  - mm/mlock.c:clear_page_mlock
```
```
In mm/mprotect.c (ffff800010305510)
Location: arch/arm64/include/asm/percpu.h:112
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/page_alloc.c (ffff800010317d84)
Location: arch/arm64/include/asm/percpu.h:112
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/page_alloc.c:__alloc_pages_direct_compact
```
```
In mm/page_io.c (ffff800010320a1c)
Location: arch/arm64/include/asm/percpu.h:112
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
```
```
In mm/swap_state.c (ffff8000103224f4)
Location: arch/arm64/include/asm/percpu.h:112
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/mempolicy.c (ffff80001033a18c)
Location: arch/arm64/include/asm/percpu.h:112
Inline: True
Inline callers:
  - mm/mempolicy.c:change_prot_numa
```
```
In mm/slub.c (ffff80001034660c)
Location: arch/arm64/include/asm/percpu.h:112
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
```
```
In mm/migrate.c (ffff800010353150)
Location: arch/arm64/include/asm/percpu.h:112
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
```
```
In mm/huge_memory.c (ffff80001035a5c4)
Location: arch/arm64/include/asm/percpu.h:112
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_huge_page
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffff80001035c790)
Location: arch/arm64/include/asm/percpu.h:112
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_alloc_page
  - mm/khugepaged.c:khugepaged_alloc_page
```
```
In mm/memcontrol.c (ffff800010366340)
Location: arch/arm64/include/asm/percpu.h:112
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:mem_cgroup_get_oom_group
  - mm/memcontrol.c:percpu_ref_put_many
  - mm/memcontrol.c:percpu_ref_tryget_live
```
```
In mm/hugetlb_cgroup.c (ffff80001036d708)
Location: arch/arm64/include/asm/percpu.h:112
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In mm/memory-failure.c (0)
Location: arch/arm64/include/asm/percpu.h:112
Inline: False
```
```
In mm/hmm.c (ffff80001037b88c)
Location: arch/arm64/include/asm/percpu.h:112
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/dcache.c (ffff8000103a6714)
Location: arch/arm64/include/asm/percpu.h:112
Inline: True
Inline callers:
  - fs/dcache.c:__d_instantiate
  - fs/dcache.c:__d_alloc
  - fs/dcache.c:dentry_lru_isolate
  - fs/dcache.c:dentry_lru_isolate
  - fs/dcache.c:__dentry_kill
  - fs/dcache.c:d_lru_shrink_move
  - fs/dcache.c:d_shrink_add
  - fs/dcache.c:d_shrink_del
  - fs/dcache.c:d_lru_del
  - fs/dcache.c:d_lru_del
  - fs/dcache.c:d_lru_add
  - fs/dcache.c:d_lru_add
  - fs/dcache.c:dentry_unlink_inode
```
```
In fs/inode.c (ffff8000103aefe4)
Location: arch/arm64/include/asm/percpu.h:112
Inline: True
Inline callers:
  - fs/inode.c:inode_lru_isolate
  - fs/inode.c:inode_lru_isolate
  - fs/inode.c:inode_lru_list_add
  - fs/inode.c:__destroy_inode
  - fs/inode.c:__destroy_inode
  - fs/inode.c:inode_init_always
```
```
In fs/fs-writeback.c (ffff8000103caaa4)
Location: arch/arm64/include/asm/percpu.h:112
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
In fs/buffer.c (ffff8000103d928c)
Location: arch/arm64/include/asm/percpu.h:112
Inline: True
Inline callers:
  - fs/buffer.c:alloc_page_buffers
```
```
In fs/block_dev.c (ffff8000103e13f8)
Location: arch/arm64/include/asm/percpu.h:112
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_evict_inode
```
```
In fs/notify/group.c (ffff8000103e8f40)
Location: arch/arm64/include/asm/percpu.h:112
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_put_group
```
```
In fs/aio.c (ffff8000103fc514)
Location: arch/arm64/include/asm/percpu.h:112
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
In fs/io_uring.c (ffff800010405a9c)
Location: arch/arm64/include/asm/percpu.h:112
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
In fs/dax.c (ffff80001040a328)
Location: arch/arm64/include/asm/percpu.h:112
Inline: True
```
```
In fs/drop_caches.c (ffff800010429174)
Location: arch/arm64/include/asm/percpu.h:112
Inline: True
Inline callers:
  - fs/drop_caches.c:drop_caches_sysctl_handler
  - fs/drop_caches.c:drop_caches_sysctl_handler
```
```
In block/bio.c (ffff8000105db5b4)
Location: arch/arm64/include/asm/percpu.h:112
Inline: True
```
```
In block/blk-core.c (ffff8000105e42e8)
Location: arch/arm64/include/asm/percpu.h:112
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_account_io_done
  - block/blk-core.c:submit_bio
  - block/blk-core.c:submit_bio
  - block/blk-core.c:direct_make_request
  - block/blk-core.c:blk_queue_enter
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-merge.c (ffff8000105eb6ac)
Location: arch/arm64/include/asm/percpu.h:112
Inline: True
```
```
In block/blk-mq.c (ffff8000105ef68c)
Location: arch/arm64/include/asm/percpu.h:112
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_timeout_work
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/blk-mq-tag.c (ffff8000105f474c)
Location: arch/arm64/include/asm/percpu.h:112
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
```
In block/blk-mq-sched.c (ffff8000105f7108)
Location: arch/arm64/include/asm/percpu.h:112
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
```
In block/blk-cgroup.c (ffff80001060e878)
Location: arch/arm64/include/asm/percpu.h:112
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
In block/blk-throttle.c (ffff8000106119e8)
Location: arch/arm64/include/asm/percpu.h:112
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:throtl_pop_queued
  - block/blk-throttle.c:throtl_qnode_add_bio
```
```
In block/blk-iocost.c (ffff8000106158c8)
Location: arch/arm64/include/asm/percpu.h:112
Inline: True
```
```
In lib/percpu-refcount.c (ffff800010635658)
Location: arch/arm64/include/asm/percpu.h:112
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_resurrect
  - lib/percpu-refcount.c:percpu_ref_kill_and_confirm
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In drivers/block/loop.c (ffff800010924f2c)
Location: arch/arm64/include/asm/percpu.h:112
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_rq
  - drivers/block/loop.c:lo_rw_aio_complete
```
```
In drivers/dax/super.c (0)
Location: arch/arm64/include/asm/percpu.h:112
Inline: False
```
```
In drivers/scsi/scsi_lib.c (ffff80001097826c)
Location: arch/arm64/include/asm/percpu.h:112
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_end_request
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/md/md.c (ffff800010aeaa8c)
Location: arch/arm64/include/asm/percpu.h:112
Inline: True
Inline callers:
  - drivers/md/md.c:md_write_end
```
```
In net/core/neighbour.c (ffff800010be75cc)
Location: arch/arm64/include/asm/percpu.h:112
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:neigh_lookup_nodev
  - net/core/neighbour.c:neigh_lookup_nodev
  - net/core/neighbour.c:neigh_lookup
  - net/core/neighbour.c:neigh_lookup
```
```
In net/core/filter.c (ffff800010c0216c)
Location: arch/arm64/include/asm/percpu.h:112
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/ipv4/ip_forward.c (ffff800010c603bc)
Location: arch/arm64/include/asm/percpu.h:112
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffff800010c6570c)
Location: arch/arm64/include/asm/percpu.h:112
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_skb
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_output
  - net/ipv4/ip_output.c:ip_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/tcp.c (ffff800010c757e0)
Location: arch/arm64/include/asm/percpu.h:112
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_set_state
  - net/ipv4/tcp.c:tcp_set_state
  - net/ipv4/tcp.c:tcp_set_state
  - net/ipv4/tcp.c:tcp_push
```
```
In net/ipv4/tcp_input.c (ffff800010c7a500)
Location: arch/arm64/include/asm/percpu.h:112
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
  - net/ipv4/tcp_input.c:tcp_collapse_one
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_rcvq
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_send_dupack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_newly_delivered
  - net/ipv4/tcp_input.c:tcp_newly_delivered
  - net/ipv4/tcp_input.c:tcp_oow_rate_limited
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_enter_recovery
  - net/ipv4/tcp_input.c:tcp_try_undo_recovery
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_input.c:tcp_check_reno_reordering
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_input.c:tcp_shifted_skb
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
```
```
In net/ipv4/tcp_output.c (ffff800010c84f24)
Location: arch/arm64/include/asm/percpu.h:112
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_xmit_probe_skb
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_event_new_data_sent
Direct callers:
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv4/tcp_ipv4.c (ffff800010c8d3a4)
Location: arch/arm64/include/asm/percpu.h:112
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/tcp_minisocks.c (ffff800010c90304)
Location: arch/arm64/include/asm/percpu.h:112
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
```
```
In net/ipv4/tcp_fastopen.c (ffff800010c941b0)
Location: arch/arm64/include/asm/percpu.h:112
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_detect_blackhole
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/tcp_recovery.c (ffff800010c9464c)
Location: arch/arm64/include/asm/percpu.h:112
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_mark_skb_lost
```
```
In net/ipv4/datagram.c (ffff800010c96088)
Location: arch/arm64/include/asm/percpu.h:112
Inline: True
Inline callers:
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffff800010c97d4c)
Location: arch/arm64/include/asm/percpu.h:112
Inline: True
```
```
In net/ipv4/udp.c (ffff800010c9d970)
Location: arch/arm64/include/asm/percpu.h:112
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
Direct callers:
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv4/icmp.c (ffff800010ca4e30)
Location: arch/arm64/include/asm/percpu.h:112
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_out_count
```
```
In net/ipv4/af_inet.c (ffff800010cac3d4)
Location: arch/arm64/include/asm/percpu.h:112
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
```
```
In net/ipv4/ping.c (ffff800010cc0a1c)
Location: arch/arm64/include/asm/percpu.h:112
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/ipmr.c (ffff800010cccfc4)
Location: arch/arm64/include/asm/percpu.h:112
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/tcp_cubic.c (ffff800010cd2f78)
Location: arch/arm64/include/asm/percpu.h:112
Inline: True
Inline callers:
  - net/ipv4/tcp_cubic.c:bictcp_acked
  - net/ipv4/tcp_cubic.c:bictcp_acked
  - net/ipv4/tcp_cubic.c:bictcp_acked
  - net/ipv4/tcp_cubic.c:bictcp_acked
```
```
In net/xfrm/xfrm_policy.c (ffff800010ce0f18)
Location: arch/arm64/include/asm/percpu.h:112
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
```
```
In net/xfrm/xfrm_input.c (ffff800010ceaeac)
Location: arch/arm64/include/asm/percpu.h:112
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffff800010cec7b0)
Location: arch/arm64/include/asm/percpu.h:112
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/xfrm/xfrm_output.c:xfrm_output_one
  - net/xfrm/xfrm_output.c:xfrm_output_one
  - net/xfrm/xfrm_output.c:xfrm_output_one
  - net/xfrm/xfrm_output.c:xfrm_output_one
  - net/xfrm/xfrm_output.c:xfrm_output_one
  - net/xfrm/xfrm_output.c:xfrm_output_one
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/xfrm/xfrm_device.c (ffff800010cee5a0)
Location: arch/arm64/include/asm/percpu.h:112
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/ipv6/ip6_output.c (ffff800010cf8c88)
Location: arch/arm64/include/asm/percpu.h:112
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_flush_pending_frames
  - net/ipv6/ip6_output.c:__ip6_flush_pending_frames
  - net/ipv6/ip6_output.c:ip6_send_skb
  - net/ipv6/ip6_output.c:ip6_send_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_output
  - net/ipv6/ip6_output.c:ip6_output
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
Direct callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/route.c (ffff800010d11f0c)
Location: arch/arm64/include/asm/percpu.h:112
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:ip6_pkt_drop
```
```
In net/ipv6/ndisc.c (ffff800010d21c18)
Location: arch/arm64/include/asm/percpu.h:112
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffff800010d25570)
Location: arch/arm64/include/asm/percpu.h:112
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffff800010d29cbc)
Location: arch/arm64/include/asm/percpu.h:112
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/ipv6/icmp.c (ffff800010d2c100)
Location: arch/arm64/include/asm/percpu.h:112
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_xrlim_allow
  - net/ipv6/icmp.c:icmpv6_xrlim_allow
```
```
In net/ipv6/mcast.c (ffff800010d2fe64)
Location: arch/arm64/include/asm/percpu.h:112
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_sendpack
```
```
In net/ipv6/tcp_ipv6.c (ffff800010d38ac0)
Location: arch/arm64/include/asm/percpu.h:112
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
```
```
In net/ipv6/ping.c (ffff800010d3a5b8)
Location: arch/arm64/include/asm/percpu.h:112
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/ip6mr.c (ffff800010d42dd8)
Location: arch/arm64/include/asm/percpu.h:112
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_forward2_finish
  - net/ipv6/ip6mr.c:ip6mr_forward2_finish
  - net/ipv6/ip6mr.c:ip6mr_forward2_finish
  - net/ipv6/ip6mr.c:ip6mr_forward2_finish
```
```
In net/ipv6/xfrm6_input.c (ffff800010d49080)
Location: arch/arm64/include/asm/percpu.h:112
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_input_addr
  - net/ipv6/xfrm6_input.c:xfrm6_input_addr
  - net/ipv6/xfrm6_input.c:xfrm6_input_addr
```
```
In net/ipv6/netfilter.c (ffff800010d4a838)
Location: arch/arm64/include/asm/percpu.h:112
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
**Symbols:**

```
ffff800010c769a0-ffff800010c769b4: __percpu_add_case_64 (STB_LOCAL)
ffff800010c81528-ffff800010c8153c: __percpu_add_case_64 (STB_LOCAL)
ffff800010c98c40-ffff800010c98c54: __percpu_add_case_64 (STB_LOCAL)
ffff800010cf8090-ffff800010cf80a4: __percpu_add_case_64 (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
