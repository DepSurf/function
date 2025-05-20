# Function: <code>__ll_sc_atomic64_sub_return</code>

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
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffff800010128938)
Location: arch/arm64/include/asm/atomic_ll_sc.h:211
Inline: True
```
```
In kernel/acct.c (ffff8000101c7f70)
Location: arch/arm64/include/asm/atomic_ll_sc.h:211
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffff8000101d0854)
Location: arch/arm64/include/asm/atomic_ll_sc.h:211
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_killed_work_fn
```
```
In kernel/cgroup/cgroup-v1.c (ffff8000101dcab0)
Location: arch/arm64/include/asm/atomic_ll_sc.h:211
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In kernel/cgroup/legacy_freezer.c (ffff8000101de844)
Location: arch/arm64/include/asm/atomic_ll_sc.h:211
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (ffff8000101dfa28)
Location: arch/arm64/include/asm/atomic_ll_sc.h:211
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy
```
```
In kernel/cgroup/cpuset.c (ffff8000101e4b34)
Location: arch/arm64/include/asm/atomic_ll_sc.h:211
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
In kernel/audit_tree.c (ffff8000101f5534)
Location: arch/arm64/include/asm/atomic_ll_sc.h:211
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_put_chunk
```
```
In kernel/bpf/arraymap.c (ffff80001027b924)
Location: arch/arm64/include/asm/atomic_ll_sc.h:211
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr
```
```
In kernel/bpf/cgroup.c (ffff80001028ff80)
Location: arch/arm64/include/asm/atomic_ll_sc.h:211
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_query
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_release
  - kernel/bpf/cgroup.c:cgroup_bpf_release
```
```
In kernel/events/core.c (ffff80001029c48c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:211
Inline: True
Inline callers:
  - kernel/events/core.c:put_event
  - kernel/events/core.c:_free_event
```
```
In mm/oom_kill.c (ffff8000102b7cb8)
Location: arch/arm64/include/asm/atomic_ll_sc.h:211
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
```
```
In mm/page-writeback.c (ffff8000102bc770)
Location: arch/arm64/include/asm/atomic_ll_sc.h:211
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/swap.c (0)
Location: arch/arm64/include/asm/atomic_ll_sc.h:211
Inline: True
```
```
In mm/backing-dev.c (ffff8000102df860)
Location: arch/arm64/include/asm/atomic_ll_sc.h:211
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/backing-dev.c:cgwb_release_workfn
```
```
In mm/slab_common.c (ffff8000102e7894)
Location: arch/arm64/include/asm/atomic_ll_sc.h:211
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:destroy_memcg_params
```
```
In mm/gup.c (ffff8000102f283c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:211
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page
```
```
In mm/slub.c (ffff800010346734)
Location: arch/arm64/include/asm/atomic_ll_sc.h:211
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
  - mm/slub.c:alloc_slab_page
```
```
In mm/page_counter.c (ffff800010360ad0)
Location: arch/arm64/include/asm/atomic_ll_sc.h:211
Inline: True
```
```
In mm/memcontrol.c (ffff800010364cf8)
Location: arch/arm64/include/asm/atomic_ll_sc.h:211
Inline: True
Inline callers:
  - mm/memcontrol.c:percpu_ref_put_many
```
```
In mm/hugetlb_cgroup.c (ffff80001036d7a0)
Location: arch/arm64/include/asm/atomic_ll_sc.h:211
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In mm/memory-failure.c (0)
Location: arch/arm64/include/asm/atomic_ll_sc.h:211
Inline: True
```
```
In mm/hmm.c (ffff80001037b9bc)
Location: arch/arm64/include/asm/atomic_ll_sc.h:211
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/file_table.c (ffff800010385758)
Location: arch/arm64/include/asm/atomic_ll_sc.h:211
Inline: True
```
```
In fs/inode.c (ffff8000103acf10)
Location: arch/arm64/include/asm/atomic_ll_sc.h:211
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
```
```
In fs/fs-writeback.c (ffff8000103cab5c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:211
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:wbc_detach_inode
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/buffer.c (ffff8000103d92f0)
Location: arch/arm64/include/asm/atomic_ll_sc.h:211
Inline: True
Inline callers:
  - fs/buffer.c:alloc_page_buffers
```
```
In fs/block_dev.c (ffff8000103e14a0)
Location: arch/arm64/include/asm/atomic_ll_sc.h:211
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_evict_inode
```
```
In fs/notify/group.c (ffff8000103e8f84)
Location: arch/arm64/include/asm/atomic_ll_sc.h:211
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_put_group
```
```
In fs/notify/mark.c (ffff8000103e93ec)
Location: arch/arm64/include/asm/atomic_ll_sc.h:211
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_drop_object
```
```
In fs/aio.c (ffff8000103fc590)
Location: arch/arm64/include/asm/atomic_ll_sc.h:211
Inline: True
Inline callers:
  - fs/aio.c:do_io_getevents
  - fs/aio.c:__arm64_sys_io_cancel
  - fs/aio.c:__arm64_compat_sys_io_submit
  - fs/aio.c:__arm64_sys_io_submit
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
  - fs/aio.c:free_ioctx_users
```
```
In fs/io_uring.c (ffff800010405e00)
Location: arch/arm64/include/asm/atomic_ll_sc.h:211
Inline: True
Inline callers:
  - fs/io_uring.c:__arm64_sys_io_uring_enter
  - fs/io_uring.c:io_iopoll_getevents
  - fs/io_uring.c:io_iopoll_getevents
  - fs/io_uring.c:__io_free_req
  - fs/io_uring.c:io_get_req
```
```
In block/bio.c (ffff8000105db608)
Location: arch/arm64/include/asm/atomic_ll_sc.h:211
Inline: True
```
```
In block/blk-core.c (ffff8000105e41ac)
Location: arch/arm64/include/asm/atomic_ll_sc.h:211
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_done
  - block/blk-core.c:direct_make_request
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-ioc.c (ffff8000105e88e8)
Location: arch/arm64/include/asm/atomic_ll_sc.h:211
Inline: True
```
```
In block/blk-merge.c (ffff8000105eba24)
Location: arch/arm64/include/asm/atomic_ll_sc.h:211
Inline: True
```
```
In block/blk-mq-sched.c (ffff8000105f71f4)
Location: arch/arm64/include/asm/atomic_ll_sc.h:211
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
```
In block/blk-cgroup.c (ffff80001060ea60)
Location: arch/arm64/include/asm/atomic_ll_sc.h:211
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:__blkg_release
  - block/blk-cgroup.c:__blkg_release
```
```
In block/blk-throttle.c (ffff800010611c7c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:211
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:throtl_pop_queued
```
```
In lib/percpu-refcount.c (ffff8000106355c8)
Location: arch/arm64/include/asm/atomic_ll_sc.h:211
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_kill_and_confirm
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In drivers/block/loop.c (ffff800010922340)
Location: arch/arm64/include/asm/atomic_ll_sc.h:211
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_rw_aio_complete
```
```
In drivers/dax/super.c (0)
Location: arch/arm64/include/asm/atomic_ll_sc.h:211
Inline: True
```
```
In drivers/scsi/scsi_lib.c (ffff80001097836c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:211
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/md/md.c (ffff800010aeab30)
Location: arch/arm64/include/asm/atomic_ll_sc.h:211
Inline: True
Inline callers:
  - drivers/md/md.c:md_write_end
```
```
In net/unix/scm.c (ffff800010cf5514)
Location: arch/arm64/include/asm/atomic_ll_sc.h:211
Inline: True
Inline callers:
  - net/unix/scm.c:unix_notinflight
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
