# Function: <code>raw_atomic64_try_cmpxchg</code>

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
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/pvclock.c (ffffffff821410cc)
Location: include/linux/atomic/atomic-arch-fallback.h:4229
Inline: True
Inline callers:
  - arch/x86/kernel/pvclock.c:pvclock_clocksource_read_nowd
  - arch/x86/kernel/pvclock.c:pvclock_clocksource_read
```
```
In kernel/fork.c (ffffffff810f230b)
Location: include/linux/atomic/atomic-arch-fallback.h:4229
Inline: True
Inline callers:
  - kernel/fork.c:get_mm_exe_file
```
```
In kernel/ucount.c (ffffffff811379ad)
Location: include/linux/atomic/atomic-arch-fallback.h:4229
Inline: True
Inline callers:
  - kernel/ucount.c:dec_ucount
```
```
In kernel/locking/rwsem.c (ffffffff8215538a)
Location: include/linux/atomic/atomic-arch-fallback.h:4229
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:down_read_killable
  - kernel/locking/rwsem.c:down_read_interruptible
  - kernel/locking/rwsem.c:down_read
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
```
```
In kernel/printk/printk_ringbuffer.c (ffffffff811a4355)
Location: include/linux/atomic/atomic-arch-fallback.h:4229
Inline: True
Inline callers:
  - kernel/printk/printk_ringbuffer.c:_prb_commit
  - kernel/printk/printk_ringbuffer.c:prb_reserve_in_last
  - kernel/printk/printk_ringbuffer.c:data_realloc
  - kernel/printk/printk_ringbuffer.c:data_alloc
  - kernel/printk/printk_ringbuffer.c:desc_reserve
  - kernel/printk/printk_ringbuffer.c:desc_reserve
  - kernel/printk/printk_ringbuffer.c:data_push_tail
```
```
In kernel/dma/swiotlb.c (ffffffff811d72ff)
Location: include/linux/atomic/atomic-arch-fallback.h:4229
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_do_find_slots
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811fd9f9)
Location: include/linux/atomic/atomic-arch-fallback.h:4229
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
```
```
In kernel/acct.c (ffffffff81212a5c)
Location: include/linux/atomic/atomic-arch-fallback.h:4229
Inline: True
Inline callers:
  - kernel/acct.c:acct_process
```
```
In kernel/cgroup/cgroup.c (ffffffff81226823)
Location: include/linux/atomic/atomic-arch-fallback.h:4229
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_get_from_path
  - kernel/cgroup/cgroup.c:css_tryget_online_from_dir
  - kernel/cgroup/cgroup.c:cgroup_get_from_id
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8122a2d8)
Location: include/linux/atomic/atomic-arch-fallback.h:4229
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use
  - kernel/cgroup/cgroup-v1.c:cgroupstats_build
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff8122b6ba)
Location: include/linux/atomic/atomic-arch-fallback.h:4229
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_change_state
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (ffffffff8122ccac)
Location: include/linux/atomic/atomic-arch-fallback.h:4229
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffff81235159)
Location: include/linux/atomic/atomic-arch-fallback.h:4229
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:update_nodemasks_hier
  - kernel/cgroup/cpuset.c:update_sibling_cpumasks
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
```
In kernel/bpf/syscall.c (ffffffff812eba15)
Location: include/linux/atomic/atomic-arch-fallback.h:4229
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_link_inc_not_zero
  - kernel/bpf/syscall.c:bpf_prog_inc_not_zero
  - kernel/bpf/syscall.c:__bpf_map_inc_not_zero
```
```
In kernel/bpf/helpers.c (ffffffff81321563)
Location: include/linux/atomic/atomic-arch-fallback.h:4229
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_cgroup_ancestor
  - kernel/bpf/helpers.c:bpf_cgroup_acquire
```
```
In kernel/bpf/task_iter.c (ffffffff81325613)
Location: include/linux/atomic/atomic-arch-fallback.h:4229
Inline: True
Inline callers:
  - kernel/bpf/task_iter.c:task_file_seq_get_next
```
```
In kernel/bpf/memalloc.c (ffffffff8134c573)
Location: include/linux/atomic/atomic-arch-fallback.h:4229
Inline: True
Inline callers:
  - kernel/bpf/memalloc.c:bpf_mem_cache_alloc_flags
  - kernel/bpf/memalloc.c:alloc_bulk
```
```
In kernel/events/core.c (ffffffff81377a12)
Location: include/linux/atomic/atomic-arch-fallback.h:4229
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:event_sched_out
  - kernel/events/core.c:perf_get_aux_event
```
```
In mm/page-writeback.c (ffffffff8139b763)
Location: include/linux/atomic/atomic-arch-fallback.h:4229
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited_flags
  - mm/page-writeback.c:balance_dirty_pages_ratelimited_flags
```
```
In mm/vmscan.c (ffffffff813b41cd)
Location: include/linux/atomic/atomic-arch-fallback.h:4229
Inline: True
Inline callers:
  - mm/vmscan.c:run_cmd
  - mm/vmscan.c:shrink_many
```
```
In mm/backing-dev.c (ffffffff813cadb6)
Location: include/linux/atomic/atomic-arch-fallback.h:4229
Inline: True
Inline callers:
  - mm/backing-dev.c:cleanup_offline_cgwbs_workfn
```
```
In mm/swapfile.c (ffffffff81430bfa)
Location: include/linux/atomic/atomic-arch-fallback.h:4229
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_device
```
```
In mm/slub.c (ffffffff8145c9b7)
Location: include/linux/atomic/atomic-arch-fallback.h:4229
Inline: True
```
```
In mm/memcontrol.c (ffffffff8149132f)
Location: include/linux/atomic/atomic-arch-fallback.h:4229
Inline: True
Inline callers:
  - mm/memcontrol.c:obj_cgroup_may_zswap
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:uncharge_folio
  - mm/memcontrol.c:mem_cgroup_swapin_charge_folio
  - mm/memcontrol.c:obj_cgroup_charge
  - mm/memcontrol.c:drain_obj_stock
  - mm/memcontrol.c:__memcg_kmem_charge_page
  - mm/memcontrol.c:obj_cgroup_uncharge_pages
  - mm/memcontrol.c:__get_obj_cgroup_from_memcg
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:get_mem_cgroup_from_mm
  - mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node
```
```
In mm/hugetlb_cgroup.c (ffffffff81493898)
Location: include/linux/atomic/atomic-arch-fallback.h:4229
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
```
```
In mm/memremap.c (ffffffff814a40b1)
Location: include/linux/atomic/atomic-arch-fallback.h:4229
Inline: True
Inline callers:
  - mm/memremap.c:zone_device_page_init
  - mm/memremap.c:get_dev_pagemap
```
```
In fs/file.c (ffffffff814dbec7)
Location: include/linux/atomic/atomic-arch-fallback.h:4229
Inline: True
Inline callers:
  - fs/file.c:__fget_light
  - fs/file.c:fget_task
  - fs/file.c:fget_raw
  - fs/file.c:fget
```
```
In fs/libfs.c (ffffffff814eca36)
Location: include/linux/atomic/atomic-arch-fallback.h:4229
Inline: True
Inline callers:
  - fs/libfs.c:inode_query_iversion
  - fs/libfs.c:inode_maybe_inc_iversion
```
```
In fs/fs-writeback.c (ffffffff814f8b0e)
Location: include/linux/atomic/atomic-arch-fallback.h:4229
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/aio.c (ffffffff81527a92)
Location: include/linux/atomic/atomic-arch-fallback.h:4229
Inline: True
Inline callers:
  - fs/aio.c:lookup_ioctx
```
```
In block/blk-core.c (ffffffff81772ae5)
Location: include/linux/atomic/atomic-arch-fallback.h:4229
Inline: True
Inline callers:
  - block/blk-core.c:bio_poll
  - block/blk-core.c:__submit_bio
  - block/blk-core.c:__bio_queue_enter
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-mq.c (ffffffff8177f9e4)
Location: include/linux/atomic/atomic-arch-fallback.h:4229
Inline: True
Inline callers:
  - block/blk-mq.c:blk_rq_poll
  - block/blk-mq.c:blk_mq_hctx_notify_offline
  - block/blk-mq.c:blk_mq_get_new_requests
  - block/blk-mq.c:blk_mq_timeout_work
```
```
In block/blk-mq-tag.c (ffffffff817885ee)
Location: include/linux/atomic/atomic-arch-fallback.h:4229
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
```
In block/blk-cgroup.c (ffffffff817a2a00)
Location: include/linux/atomic/atomic-arch-fallback.h:4229
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkcg_scale_delay
  - block/blk-cgroup.c:blkg_create
```
```
In io_uring/fdinfo.c (ffffffff817dcab0)
Location: include/linux/atomic/atomic-arch-fallback.h:4229
Inline: True
Inline callers:
  - io_uring/fdinfo.c:io_uring_show_fdinfo
```
```
In io_uring/rsrc.c (ffffffff817e1aca)
Location: include/linux/atomic/atomic-arch-fallback.h:4229
Inline: True
Inline callers:
  - io_uring/rsrc.c:__io_account_mem
```
```
In lib/sbitmap.c (ffffffff818e6724)
Location: include/linux/atomic/atomic-arch-fallback.h:4229
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbitmap_queue_get_batch
```
```
In drivers/pci/p2pdma.c (ffffffff8195fcc4)
Location: include/linux/atomic/atomic-arch-fallback.h:4229
Inline: True
Inline callers:
  - drivers/pci/p2pdma.c:pci_alloc_p2pmem
  - drivers/pci/p2pdma.c:p2pmem_alloc_mmap
```
```
In drivers/tty/tty_ldsem.c (ffffffff81aa10ee)
Location: include/linux/atomic/atomic-arch-fallback.h:4229
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_write_trylock
  - drivers/tty/tty_ldsem.c:ldsem_down_read_trylock
  - drivers/tty/tty_ldsem.c:down_write_failed
  - drivers/tty/tty_ldsem.c:down_write_failed
  - drivers/tty/tty_ldsem.c:down_read_failed
  - drivers/tty/tty_ldsem.c:__ldsem_wake_readers
```
```
In drivers/md/md.c (ffffffff81d5fd11)
Location: include/linux/atomic/atomic-arch-fallback.h:4229
Inline: True
Inline callers:
  - drivers/md/md.c:md_handle_request
```
```
In net/core/skbuff.c (ffffffff81e1574d)
Location: include/linux/atomic/atomic-arch-fallback.h:4229
Inline: True
Inline callers:
  - net/core/skbuff.c:mm_account_pinned_pages
```
```
In net/mptcp/subflow.c (ffffffff8207c417)
Location: include/linux/atomic/atomic-arch-fallback.h:4229
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
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
In arch/x86/kernel/pvclock.c (ffffffff82222fdc)
Location: include/linux/atomic/atomic-arch-fallback.h:4234
Inline: True
Inline callers:
  - arch/x86/kernel/pvclock.c:pvclock_clocksource_read_nowd
  - arch/x86/kernel/pvclock.c:pvclock_clocksource_read
```
```
In kernel/cred.c (ffffffff8113e6cd)
Location: include/linux/atomic/atomic-arch-fallback.h:4234
Inline: True
Inline callers:
  - kernel/cred.c:get_task_cred
```
```
In kernel/ucount.c (ffffffff81142bbd)
Location: include/linux/atomic/atomic-arch-fallback.h:4234
Inline: True
Inline callers:
  - kernel/ucount.c:dec_ucount
```
```
In kernel/locking/rwsem.c (ffffffff822381ca)
Location: include/linux/atomic/atomic-arch-fallback.h:4234
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:down_read_killable
  - kernel/locking/rwsem.c:down_read_interruptible
  - kernel/locking/rwsem.c:down_read
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
```
```
In kernel/printk/printk_ringbuffer.c (ffffffff811b3e45)
Location: include/linux/atomic/atomic-arch-fallback.h:4234
Inline: True
Inline callers:
  - kernel/printk/printk_ringbuffer.c:_prb_commit
  - kernel/printk/printk_ringbuffer.c:prb_reserve_in_last
  - kernel/printk/printk_ringbuffer.c:data_realloc
  - kernel/printk/printk_ringbuffer.c:data_alloc
  - kernel/printk/printk_ringbuffer.c:desc_reserve
  - kernel/printk/printk_ringbuffer.c:desc_reserve
  - kernel/printk/printk_ringbuffer.c:data_push_tail
```
```
In kernel/dma/swiotlb.c (ffffffff811ec2c0)
Location: include/linux/atomic/atomic-arch-fallback.h:4234
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_search_pool_area
```
```
In kernel/time/posix-cpu-timers.c (ffffffff81213d19)
Location: include/linux/atomic/atomic-arch-fallback.h:4234
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
```
```
In kernel/acct.c (ffffffff8122a0fc)
Location: include/linux/atomic/atomic-arch-fallback.h:4234
Inline: True
Inline callers:
  - kernel/acct.c:acct_process
```
```
In kernel/cgroup/cgroup.c (ffffffff8123e4b3)
Location: include/linux/atomic/atomic-arch-fallback.h:4234
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_get_from_path
  - kernel/cgroup/cgroup.c:css_tryget_online_from_dir
  - kernel/cgroup/cgroup.c:cgroup_get_from_id
  - kernel/cgroup/cgroup.c:cgroup_tryget_css
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff812422b5)
Location: include/linux/atomic/atomic-arch-fallback.h:4234
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:task_get_cgroup1
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use
  - kernel/cgroup/cgroup-v1.c:cgroupstats_build
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff812436aa)
Location: include/linux/atomic/atomic-arch-fallback.h:4234
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_change_state
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (ffffffff81244d6c)
Location: include/linux/atomic/atomic-arch-fallback.h:4234
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffff8124eda8)
Location: include/linux/atomic/atomic-arch-fallback.h:4234
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:update_nodemasks_hier
  - kernel/cgroup/cpuset.c:update_sibling_cpumasks
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
```
In kernel/bpf/syscall.c (ffffffff81309f65)
Location: include/linux/atomic/atomic-arch-fallback.h:4234
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_link_inc_not_zero
  - kernel/bpf/syscall.c:bpf_prog_inc_not_zero
  - kernel/bpf/syscall.c:__bpf_map_inc_not_zero
```
```
In kernel/bpf/helpers.c (ffffffff81343c93)
Location: include/linux/atomic/atomic-arch-fallback.h:4234
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_cgroup_ancestor
  - kernel/bpf/helpers.c:bpf_cgroup_acquire
```
```
In kernel/bpf/memalloc.c (ffffffff81371ecf)
Location: include/linux/atomic/atomic-arch-fallback.h:4234
Inline: True
```
```
In kernel/events/core.c (ffffffff813a0cf2)
Location: include/linux/atomic/atomic-arch-fallback.h:4234
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:event_sched_out
  - kernel/events/core.c:perf_get_aux_event
```
```
In mm/page-writeback.c (ffffffff813c56d3)
Location: include/linux/atomic/atomic-arch-fallback.h:4234
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited_flags
  - mm/page-writeback.c:balance_dirty_pages_ratelimited_flags
```
```
In mm/vmscan.c (ffffffff813dd84d)
Location: include/linux/atomic/atomic-arch-fallback.h:4234
Inline: True
Inline callers:
  - mm/vmscan.c:run_cmd
  - mm/vmscan.c:shrink_many
```
```
In mm/backing-dev.c (ffffffff813f5d96)
Location: include/linux/atomic/atomic-arch-fallback.h:4234
Inline: True
Inline callers:
  - mm/backing-dev.c:cleanup_offline_cgwbs_workfn
```
```
In mm/workingset.c (ffffffff8140c45c)
Location: include/linux/atomic/atomic-arch-fallback.h:4234
Inline: True
Inline callers:
  - mm/workingset.c:workingset_test_recent
```
```
In mm/slub.c (ffffffff81454e91)
Location: include/linux/atomic/atomic-arch-fallback.h:4234
Inline: True
```
```
In mm/swapfile.c (ffffffff8146a01a)
Location: include/linux/atomic/atomic-arch-fallback.h:4234
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_device
```
```
In mm/zswap.c (ffffffff8147121c)
Location: include/linux/atomic/atomic-arch-fallback.h:4234
Inline: True
Inline callers:
  - mm/zswap.c:zswap_store
  - mm/zswap.c:zswap_store
  - mm/zswap.c:shrink_worker
  - mm/zswap.c:zswap_lru_add
```
```
In mm/memcontrol.c (ffffffff814c0c9f)
Location: include/linux/atomic/atomic-arch-fallback.h:4234
Inline: True
Inline callers:
  - mm/memcontrol.c:obj_cgroup_may_zswap
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:uncharge_folio
  - mm/memcontrol.c:mem_cgroup_swapin_charge_folio
  - mm/memcontrol.c:obj_cgroup_charge
  - mm/memcontrol.c:drain_obj_stock
  - mm/memcontrol.c:__memcg_kmem_charge_page
  - mm/memcontrol.c:obj_cgroup_uncharge_pages
  - mm/memcontrol.c:get_obj_cgroup_from_folio
  - mm/memcontrol.c:current_objcg_update
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:get_mem_cgroup_from_current
  - mm/memcontrol.c:get_mem_cgroup_from_mm
  - mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node
```
```
In mm/hugetlb_cgroup.c (ffffffff814c320a)
Location: include/linux/atomic/atomic-arch-fallback.h:4234
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
```
```
In mm/memremap.c (ffffffff814d4f5e)
Location: include/linux/atomic/atomic-arch-fallback.h:4234
Inline: True
Inline callers:
  - mm/memremap.c:zone_device_page_init
  - mm/memremap.c:get_dev_pagemap
```
```
In fs/file.c (ffffffff8150eded)
Location: include/linux/atomic/atomic-arch-fallback.h:4234
Inline: True
Inline callers:
  - fs/file.c:__ia32_sys_dup
  - fs/file.c:__x64_sys_dup
  - fs/file.c:__ia32_sys_dup2
  - fs/file.c:__x64_sys_dup2
  - fs/file.c:__fdget_pos
  - fs/file.c:__fdget_raw
  - fs/file.c:task_lookup_next_fdget_rcu
  - fs/file.c:task_lookup_fdget_rcu
  - fs/file.c:lookup_fdget_rcu
  - fs/file.c:fget_task
  - fs/file.c:fget
  - fs/file.c:__get_file_rcu
```
```
In fs/libfs.c (ffffffff81520986)
Location: include/linux/atomic/atomic-arch-fallback.h:4234
Inline: True
Inline callers:
  - fs/libfs.c:inode_query_iversion
  - fs/libfs.c:inode_maybe_inc_iversion
```
```
In fs/fs-writeback.c (ffffffff8152d36d)
Location: include/linux/atomic/atomic-arch-fallback.h:4234
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/aio.c (ffffffff8155c822)
Location: include/linux/atomic/atomic-arch-fallback.h:4234
Inline: True
Inline callers:
  - fs/aio.c:lookup_ioctx
```
```
In block/blk-core.c (ffffffff817b4e7f)
Location: include/linux/atomic/atomic-arch-fallback.h:4234
Inline: True
Inline callers:
  - block/blk-core.c:bio_poll
  - block/blk-core.c:__submit_bio
  - block/blk-core.c:__bio_queue_enter
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-mq.c (ffffffff817c24c4)
Location: include/linux/atomic/atomic-arch-fallback.h:4234
Inline: True
Inline callers:
  - block/blk-mq.c:blk_rq_poll
  - block/blk-mq.c:blk_mq_hctx_notify_offline
  - block/blk-mq.c:blk_mq_submit_bio
  - block/blk-mq.c:blk_mq_timeout_work
```
```
In block/blk-mq-tag.c (ffffffff817cacbe)
Location: include/linux/atomic/atomic-arch-fallback.h:4234
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
```
In block/blk-cgroup.c (ffffffff817e6543)
Location: include/linux/atomic/atomic-arch-fallback.h:4234
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkcg_scale_delay
  - block/blk-cgroup.c:blkg_create
```
```
In io_uring/rsrc.c (ffffffff81825e8a)
Location: include/linux/atomic/atomic-arch-fallback.h:4234
Inline: True
Inline callers:
  - io_uring/rsrc.c:__io_account_mem
```
```
In lib/sbitmap.c (ffffffff8192d744)
Location: include/linux/atomic/atomic-arch-fallback.h:4234
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbitmap_queue_get_batch
```
```
In drivers/pci/p2pdma.c (ffffffff819a9384)
Location: include/linux/atomic/atomic-arch-fallback.h:4234
Inline: True
Inline callers:
  - drivers/pci/p2pdma.c:pci_alloc_p2pmem
  - drivers/pci/p2pdma.c:p2pmem_alloc_mmap
```
```
In drivers/tty/tty_ldsem.c (ffffffff81af3b4e)
Location: include/linux/atomic/atomic-arch-fallback.h:4234
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_write_trylock
  - drivers/tty/tty_ldsem.c:ldsem_down_read_trylock
  - drivers/tty/tty_ldsem.c:down_write_failed
  - drivers/tty/tty_ldsem.c:down_write_failed
  - drivers/tty/tty_ldsem.c:down_read_failed
  - drivers/tty/tty_ldsem.c:__ldsem_wake_readers
```
```
In drivers/md/md.c (ffffffff81e172ed)
Location: include/linux/atomic/atomic-arch-fallback.h:4234
Inline: True
Inline callers:
  - drivers/md/md.c:md_handle_request
```
```
In net/core/skbuff.c (ffffffff81ed2aed)
Location: include/linux/atomic/atomic-arch-fallback.h:4234
Inline: True
Inline callers:
  - net/core/skbuff.c:mm_account_pinned_pages
```
```
In net/mptcp/subflow.c (ffffffff821518fe)
Location: include/linux/atomic/atomic-arch-fallback.h:4234
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
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
