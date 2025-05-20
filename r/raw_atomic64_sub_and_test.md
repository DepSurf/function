# Function: <code>raw_atomic64_sub_and_test</code>

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
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81092ea1)
Location: include/linux/atomic/atomic-arch-fallback.h:4354
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_alloc_backing
```
```
In kernel/kthread.c (ffffffff81129ba2)
Location: include/linux/atomic/atomic-arch-fallback.h:4354
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffffffff81226975)
Location: include/linux/atomic/atomic-arch-fallback.h:4354
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_free
  - kernel/cgroup/cgroup.c:cgroup_sk_free
  - kernel/cgroup/cgroup.c:cgroup_get_from_fd
  - kernel/cgroup/cgroup.c:cgroup_css_set_put_fork
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:cgroup_get_from_id
  - kernel/cgroup/cgroup.c:css_killed_work_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:pressure_write
  - kernel/cgroup/cgroup.c:pressure_write
  - kernel/cgroup/cgroup.c:pressure_write
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - kernel/cgroup/cgroup.c:cgroup_do_get_tree
  - kernel/cgroup/cgroup.c:cgroup_kn_unlock
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81228be3)
Location: include/linux/atomic/atomic-arch-fallback.h:4354
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use
  - kernel/cgroup/cgroup-v1.c:cgroupstats_build
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff8122b6cf)
Location: include/linux/atomic/atomic-arch-fallback.h:4354
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_change_state
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (ffffffff8122ca75)
Location: include/linux/atomic/atomic-arch-fallback.h:4354
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy
```
```
In kernel/cgroup/cpuset.c (ffffffff8123512b)
Location: include/linux/atomic/atomic-arch-fallback.h:4354
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
In kernel/bpf/syscall.c (ffffffff812f0bb5)
Location: include/linux/atomic/atomic-arch-fallback.h:4354
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_map_free_deferred
  - kernel/bpf/syscall.c:bpf_map_alloc_percpu
  - kernel/bpf/syscall.c:bpf_map_kvcalloc
  - kernel/bpf/syscall.c:bpf_map_kzalloc
  - kernel/bpf/syscall.c:bpf_map_kmalloc_node
```
```
In kernel/bpf/helpers.c (ffffffff813214a4)
Location: include/linux/atomic/atomic-arch-fallback.h:4354
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_cgroup_release
```
```
In kernel/bpf/arraymap.c (ffffffff8132cdf4)
Location: include/linux/atomic/atomic-arch-fallback.h:4354
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr
```
```
In kernel/bpf/trampoline.c (ffffffff81337af6)
Location: include/linux/atomic/atomic-arch-fallback.h:4354
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:__bpf_tramp_exit
```
```
In kernel/bpf/memalloc.c (ffffffff8134c53e)
Location: include/linux/atomic/atomic-arch-fallback.h:4354
Inline: True
Inline callers:
  - kernel/bpf/memalloc.c:bpf_mem_cache_alloc_flags
  - kernel/bpf/memalloc.c:bpf_mem_alloc_destroy
  - kernel/bpf/memalloc.c:bpf_mem_alloc_destroy
  - kernel/bpf/memalloc.c:alloc_bulk
```
```
In kernel/bpf/cgroup_iter.c (ffffffff813557ea)
Location: include/linux/atomic/atomic-arch-fallback.h:4354
Inline: True
Inline callers:
  - kernel/bpf/cgroup_iter.c:bpf_iter_detach_cgroup
  - kernel/bpf/cgroup_iter.c:cgroup_iter_seq_fini
```
```
In kernel/bpf/bpf_cgrp_storage.c (ffffffff81355c68)
Location: include/linux/atomic/atomic-arch-fallback.h:4354
Inline: True
Inline callers:
  - kernel/bpf/bpf_cgrp_storage.c:bpf_cgrp_storage_delete_elem
  - kernel/bpf/bpf_cgrp_storage.c:bpf_cgrp_storage_update_elem
  - kernel/bpf/bpf_cgrp_storage.c:bpf_cgrp_storage_lookup_elem
```
```
In kernel/bpf/cgroup.c (ffffffff8135a88e)
Location: include/linux/atomic/atomic-arch-fallback.h:4354
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_query
  - kernel/bpf/cgroup.c:cgroup_bpf_link_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_release
  - kernel/bpf/cgroup.c:cgroup_bpf_release
  - kernel/bpf/cgroup.c:cgroup_bpf_release
```
```
In kernel/events/core.c (ffffffff81370daa)
Location: include/linux/atomic/atomic-arch-fallback.h:4354
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_free_event
```
```
In mm/oom_kill.c (ffffffff8139715b)
Location: include/linux/atomic/atomic-arch-fallback.h:4354
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
```
```
In mm/page-writeback.c (ffffffff8139b729)
Location: include/linux/atomic/atomic-arch-fallback.h:4354
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited_flags
  - mm/page-writeback.c:balance_dirty_pages_ratelimited_flags
```
```
In mm/vmscan.c (ffffffff813b41eb)
Location: include/linux/atomic/atomic-arch-fallback.h:4354
Inline: True
Inline callers:
  - mm/vmscan.c:run_cmd
  - mm/vmscan.c:shrink_many
  - mm/vmscan.c:shrink_many
  - mm/vmscan.c:lru_gen_del_mm
```
```
In mm/shmem.c (ffffffff813bedac)
Location: include/linux/atomic/atomic-arch-fallback.h:4354
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_folio
  - mm/shmem.c:shmem_swapin_folio
```
```
In mm/backing-dev.c (ffffffff813cad81)
Location: include/linux/atomic/atomic-arch-fallback.h:4354
Inline: True
Inline callers:
  - mm/backing-dev.c:cleanup_offline_cgwbs_workfn
  - mm/backing-dev.c:cgwb_create
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/backing-dev.c:cgwb_release_workfn
```
```
In mm/percpu.c (ffffffff813d0e16)
Location: include/linux/atomic/atomic-arch-fallback.h:4354
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_memcg_post_alloc_hook
```
```
In mm/gup.c (ffffffff813e6da8)
Location: include/linux/atomic/atomic-arch-fallback.h:4354
Inline: True
Inline callers:
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:gup_pte_range
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page
```
```
In mm/mmap_lock.c (ffffffff813e87d6)
Location: include/linux/atomic/atomic-arch-fallback.h:4354
Inline: True
Inline callers:
  - mm/mmap_lock.c:get_mm_memcg_path
```
```
In mm/memory.c (ffffffff813f0c83)
Location: include/linux/atomic/atomic-arch-fallback.h:4354
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
```
In mm/memory_hotplug.c (ffffffff814252d5)
Location: include/linux/atomic/atomic-arch-fallback.h:4354
Inline: True
Inline callers:
  - mm/memory_hotplug.c:pfn_to_online_page
```
```
In mm/swap_state.c (ffffffff8142c46e)
Location: include/linux/atomic/atomic-arch-fallback.h:4354
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:filemap_get_incore_folio
```
```
In mm/swapfile.c (ffffffff81433e14)
Location: include/linux/atomic/atomic-arch-fallback.h:4354
Inline: True
Inline callers:
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:get_swap_device
```
```
In mm/zswap.c (ffffffff81437131)
Location: include/linux/atomic/atomic-arch-fallback.h:4354
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_free_entry
```
```
In mm/hugetlb.c (ffffffff814409db)
Location: include/linux/atomic/atomic-arch-fallback.h:4354
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:clear_vma_resv_huge_pages
  - mm/hugetlb.c:coalesce_file_region
  - mm/hugetlb.c:coalesce_file_region
```
```
In mm/slub.c (ffffffff8146237e)
Location: include/linux/atomic/atomic-arch-fallback.h:4354
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:__kmem_cache_free
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:__kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc
  - mm/slub.c:memcg_slab_post_alloc_hook
```
```
In mm/memcontrol.c (ffffffff81491345)
Location: include/linux/atomic/atomic-arch-fallback.h:4354
Inline: True
Inline callers:
  - mm/memcontrol.c:obj_cgroup_may_zswap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_sk_free
  - mm/memcontrol.c:uncharge_folio
  - mm/memcontrol.c:uncharge_folio
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:mem_cgroup_swapin_charge_folio
  - mm/memcontrol.c:__mem_cgroup_charge
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_event_remove
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:obj_cgroup_charge
  - mm/memcontrol.c:refill_obj_stock
  - mm/memcontrol.c:drain_obj_stock
  - mm/memcontrol.c:mod_objcg_state
  - mm/memcontrol.c:__memcg_kmem_uncharge_page
  - mm/memcontrol.c:__memcg_kmem_charge_page
  - mm/memcontrol.c:__memcg_kmem_charge_page
  - mm/memcontrol.c:obj_cgroup_uncharge_pages
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:drain_local_stock
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_oom_trylock
  - mm/memcontrol.c:mem_cgroup_oom_trylock
  - mm/memcontrol.c:mem_cgroup_scan_tasks
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
```
```
In mm/hugetlb_cgroup.c (ffffffff81493f12)
Location: include/linux/atomic/atomic-arch-fallback.h:4354
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_file_region
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_counter
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_cgroup_rsvd
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
```
```
In mm/memory-failure.c (ffffffff81498349)
Location: include/linux/atomic/atomic-arch-fallback.h:4354
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure_dev_pagemap
```
```
In mm/memremap.c (ffffffff814a434e)
Location: include/linux/atomic/atomic-arch-fallback.h:4354
Inline: True
Inline callers:
  - mm/memremap.c:free_zone_device_page
  - mm/memremap.c:get_dev_pagemap
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:memunmap_pages
```
```
In fs/inode.c (ffffffff814d7849)
Location: include/linux/atomic/atomic-arch-fallback.h:4354
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
```
```
In fs/fs-writeback.c (ffffffff814f8ab5)
Location: include/linux/atomic/atomic-arch-fallback.h:4354
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:wbc_detach_inode
  - fs/fs-writeback.c:cleanup_offline_cgwb
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/notify/group.c (ffffffff81513ca6)
Location: include/linux/atomic/atomic-arch-fallback.h:4354
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_put_group
```
```
In fs/aio.c (ffffffff8152992c)
Location: include/linux/atomic/atomic-arch-fallback.h:4354
Inline: True
Inline callers:
  - fs/aio.c:do_io_getevents
  - fs/aio.c:__ia32_sys_io_cancel
  - fs/aio.c:__x64_sys_io_cancel
  - fs/aio.c:__ia32_compat_sys_io_submit
  - fs/aio.c:__ia32_sys_io_submit
  - fs/aio.c:__x64_sys_io_submit
  - fs/aio.c:io_submit_one
  - fs/aio.c:io_submit_one
  - fs/aio.c:aio_poll_wake
  - fs/aio.c:aio_poll_complete_work
  - fs/aio.c:aio_poll_put_work
  - fs/aio.c:aio_fsync_work
  - fs/aio.c:aio_complete_rw
  - fs/aio.c:__ia32_sys_io_destroy
  - fs/aio.c:__x64_sys_io_destroy
  - fs/aio.c:__ia32_compat_sys_io_setup
  - fs/aio.c:__ia32_sys_io_setup
  - fs/aio.c:__x64_sys_io_setup
  - fs/aio.c:free_ioctx_users
```
```
In block/bio.c (ffffffff817694ad)
Location: include/linux/atomic/atomic-arch-fallback.h:4354
Inline: True
Inline callers:
  - block/bio.c:bio_uninit
```
```
In block/blk-core.c (ffffffff81772afa)
Location: include/linux/atomic/atomic-arch-fallback.h:4354
Inline: True
Inline callers:
  - block/blk-core.c:bio_poll
  - block/blk-core.c:__submit_bio
  - block/blk-core.c:__submit_bio
  - block/blk-core.c:__bio_queue_enter
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-mq.c (ffffffff8177f41d)
Location: include/linux/atomic/atomic-arch-fallback.h:4354
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_offline
  - block/blk-mq.c:blk_mq_dispatch_plug_list
  - block/blk-mq.c:blk_mq_end_request_batch
  - block/blk-mq.c:blk_mq_end_request_batch
```
```
In block/blk-cgroup.c (ffffffff817a2a15)
Location: include/linux/atomic/atomic-arch-fallback.h:4354
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkcg_activate_policy
  - block/blk-cgroup.c:blkcg_activate_policy
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:__blkg_release
  - block/blk-cgroup.c:blkg_free_workfn
```
```
In block/blk-cgroup-fc-appid.c (ffffffff817a3508)
Location: include/linux/atomic/atomic-arch-fallback.h:4354
Inline: True
Inline callers:
  - block/blk-cgroup-fc-appid.c:blkcg_set_fc_appid
  - block/blk-cgroup-fc-appid.c:blkcg_set_fc_appid
```
```
In block/blk-throttle.c (ffffffff817a6343)
Location: include/linux/atomic/atomic-arch-fallback.h:4354
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:throtl_pop_queued
```
```
In io_uring/io_uring.c (ffffffff817c910c)
Location: include/linux/atomic/atomic-arch-fallback.h:4354
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_activate_pollwq
  - io_uring/io_uring.c:io_activate_pollwq_cb
  - io_uring/io_uring.c:io_req_caches_free
  - io_uring/io_uring.c:io_fallback_tw
  - io_uring/io_uring.c:io_fallback_tw
  - io_uring/io_uring.c:ctx_flush_and_put
```
```
In io_uring/fdinfo.c (ffffffff817dcac2)
Location: include/linux/atomic/atomic-arch-fallback.h:4354
Inline: True
Inline callers:
  - io_uring/fdinfo.c:io_uring_show_fdinfo
```
```
In lib/percpu-refcount.c (ffffffff81818493)
Location: include/linux/atomic/atomic-arch-fallback.h:4354
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_kill_and_confirm
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In drivers/pci/p2pdma.c (ffffffff81960437)
Location: include/linux/atomic/atomic-arch-fallback.h:4354
Inline: True
Inline callers:
  - drivers/pci/p2pdma.c:pci_p2pmem_free_sgl
  - drivers/pci/p2pdma.c:p2pdma_page_free
  - drivers/pci/p2pdma.c:p2pmem_alloc_mmap
```
```
In drivers/block/loop.c (ffffffff81b7cdd1)
Location: include/linux/atomic/atomic-arch-fallback.h:4354
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_process_work
  - drivers/block/loop.c:loop_free_idle_workers
```
```
In drivers/scsi/scsi_lib.c (ffffffff81bd3ead)
Location: include/linux/atomic/atomic-arch-fallback.h:4354
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/md/md.c (ffffffff81d5f753)
Location: include/linux/atomic/atomic-arch-fallback.h:4354
Inline: True
Inline callers:
  - drivers/md/md.c:md_end_io_acct
  - drivers/md/md.c:md_write_start
  - drivers/md/md.c:mddev_init_writes_pending
  - drivers/md/md.c:md_handle_request
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81093900)
Location: include/linux/atomic/atomic-arch-fallback.h:4359
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8109a2e1)
Location: include/linux/atomic/atomic-arch-fallback.h:4359
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_alloc_backing
```
```
In kernel/fork.c (ffffffff810fe9f7)
Location: include/linux/atomic/atomic-arch-fallback.h:4359
Inline: True
Inline callers:
  - kernel/fork.c:ksys_unshare
```
```
In kernel/ptrace.c (ffffffff811118c1)
Location: include/linux/atomic/atomic-arch-fallback.h:4359
Inline: True
Inline callers:
  - kernel/ptrace.c:__ptrace_unlink
```
```
In kernel/kthread.c (ffffffff811341e2)
Location: include/linux/atomic/atomic-arch-fallback.h:4359
Inline: True
```
```
In kernel/nsproxy.c (ffffffff8113c84f)
Location: include/linux/atomic/atomic-arch-fallback.h:4359
Inline: True
Inline callers:
  - kernel/nsproxy.c:put_nsset
```
```
In kernel/cred.c (ffffffff8113f138)
Location: include/linux/atomic/atomic-arch-fallback.h:4359
Inline: True
Inline callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:revert_creds
  - kernel/cred.c:commit_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:cred_alloc_blank
  - kernel/cred.c:exit_creds
  - kernel/cred.c:exit_creds
  - kernel/cred.c:exit_creds
```
```
In kernel/cgroup/cgroup.c (ffffffff8123e605)
Location: include/linux/atomic/atomic-arch-fallback.h:4359
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_free
  - kernel/cgroup/cgroup.c:cgroup_sk_free
  - kernel/cgroup/cgroup.c:cgroup_get_from_fd
  - kernel/cgroup/cgroup.c:cgroup_css_set_put_fork
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:cgroup_get_from_id
  - kernel/cgroup/cgroup.c:css_killed_work_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:pressure_write
  - kernel/cgroup/cgroup.c:pressure_write
  - kernel/cgroup/cgroup.c:pressure_write
  - kernel/cgroup/cgroup.c:cpu_local_stat_show
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - kernel/cgroup/cgroup.c:cgroup_do_get_tree
  - kernel/cgroup/cgroup.c:cgroup_kn_unlock
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81240a2e)
Location: include/linux/atomic/atomic-arch-fallback.h:4359
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use
  - kernel/cgroup/cgroup-v1.c:cgroupstats_build
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff812436bf)
Location: include/linux/atomic/atomic-arch-fallback.h:4359
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_change_state
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (ffffffff81244b35)
Location: include/linux/atomic/atomic-arch-fallback.h:4359
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy
```
```
In kernel/cgroup/cpuset.c (ffffffff8124ed7a)
Location: include/linux/atomic/atomic-arch-fallback.h:4359
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
In kernel/user_namespace.c (ffffffff81251af5)
Location: include/linux/atomic/atomic-arch-fallback.h:4359
Inline: True
Inline callers:
  - kernel/user_namespace.c:unshare_userns
```
```
In kernel/trace/trace_events_user.c (ffffffff812e14aa)
Location: include/linux/atomic/atomic-arch-fallback.h:4359
Inline: True
Inline callers:
  - kernel/trace/trace_events_user.c:user_event_set_call_visible
```
```
In kernel/bpf/syscall.c (ffffffff8130f9b5)
Location: include/linux/atomic/atomic-arch-fallback.h:4359
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_map_free_deferred
  - kernel/bpf/syscall.c:bpf_map_alloc_percpu
  - kernel/bpf/syscall.c:bpf_map_kvcalloc
  - kernel/bpf/syscall.c:bpf_map_kzalloc
  - kernel/bpf/syscall.c:bpf_map_kmalloc_node
```
```
In kernel/bpf/helpers.c (ffffffff81343bd4)
Location: include/linux/atomic/atomic-arch-fallback.h:4359
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_cgroup_release_dtor
  - kernel/bpf/helpers.c:bpf_cgroup_release
```
```
In kernel/bpf/arraymap.c (ffffffff81351148)
Location: include/linux/atomic/atomic-arch-fallback.h:4359
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr
```
```
In kernel/bpf/trampoline.c (ffffffff8135d936)
Location: include/linux/atomic/atomic-arch-fallback.h:4359
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:__bpf_tramp_exit
```
```
In kernel/bpf/memalloc.c (ffffffff81373a9a)
Location: include/linux/atomic/atomic-arch-fallback.h:4359
Inline: True
Inline callers:
  - kernel/bpf/memalloc.c:bpf_mem_cache_alloc_flags
  - kernel/bpf/memalloc.c:bpf_mem_alloc_destroy
  - kernel/bpf/memalloc.c:bpf_mem_alloc_destroy
  - kernel/bpf/memalloc.c:alloc_bulk
```
```
In kernel/bpf/cgroup_iter.c (ffffffff8137e16a)
Location: include/linux/atomic/atomic-arch-fallback.h:4359
Inline: True
Inline callers:
  - kernel/bpf/cgroup_iter.c:bpf_iter_detach_cgroup
  - kernel/bpf/cgroup_iter.c:cgroup_iter_seq_fini
```
```
In kernel/bpf/bpf_cgrp_storage.c (ffffffff8137e798)
Location: include/linux/atomic/atomic-arch-fallback.h:4359
Inline: True
Inline callers:
  - kernel/bpf/bpf_cgrp_storage.c:bpf_cgrp_storage_delete_elem
  - kernel/bpf/bpf_cgrp_storage.c:bpf_cgrp_storage_update_elem
  - kernel/bpf/bpf_cgrp_storage.c:bpf_cgrp_storage_lookup_elem
```
```
In kernel/bpf/cgroup.c (ffffffff8138347e)
Location: include/linux/atomic/atomic-arch-fallback.h:4359
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_query
  - kernel/bpf/cgroup.c:cgroup_bpf_link_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_release
  - kernel/bpf/cgroup.c:cgroup_bpf_release
  - kernel/bpf/cgroup.c:cgroup_bpf_release
```
```
In kernel/events/core.c (ffffffff8139a0aa)
Location: include/linux/atomic/atomic-arch-fallback.h:4359
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_free_event
```
```
In kernel/watch_queue.c (ffffffff813b2ab0)
Location: include/linux/atomic/atomic-arch-fallback.h:4359
Inline: True
Inline callers:
  - kernel/watch_queue.c:free_watch
```
```
In mm/oom_kill.c (ffffffff813c0f6d)
Location: include/linux/atomic/atomic-arch-fallback.h:4359
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
```
```
In mm/page-writeback.c (ffffffff813c5699)
Location: include/linux/atomic/atomic-arch-fallback.h:4359
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited_flags
  - mm/page-writeback.c:balance_dirty_pages_ratelimited_flags
```
```
In mm/vmscan.c (ffffffff813dd86b)
Location: include/linux/atomic/atomic-arch-fallback.h:4359
Inline: True
Inline callers:
  - mm/vmscan.c:run_cmd
  - mm/vmscan.c:shrink_many
  - mm/vmscan.c:shrink_many
  - mm/vmscan.c:lru_gen_del_mm
```
```
In mm/shmem.c (ffffffff813e9dcf)
Location: include/linux/atomic/atomic-arch-fallback.h:4359
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_folio
  - mm/shmem.c:shmem_swapin_folio
```
```
In mm/backing-dev.c (ffffffff813f5d61)
Location: include/linux/atomic/atomic-arch-fallback.h:4359
Inline: True
Inline callers:
  - mm/backing-dev.c:cleanup_offline_cgwbs_workfn
  - mm/backing-dev.c:cgwb_create
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/backing-dev.c:cgwb_release_workfn
```
```
In mm/percpu.c (ffffffff813fadeb)
Location: include/linux/atomic/atomic-arch-fallback.h:4359
Inline: True
```
```
In mm/workingset.c (ffffffff8140c42b)
Location: include/linux/atomic/atomic-arch-fallback.h:4359
Inline: True
Inline callers:
  - mm/workingset.c:workingset_test_recent
```
```
In mm/gup.c (ffffffff81411a35)
Location: include/linux/atomic/atomic-arch-fallback.h:4359
Inline: True
Inline callers:
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:gup_pte_range
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page
```
```
In mm/mmap_lock.c (ffffffff81413466)
Location: include/linux/atomic/atomic-arch-fallback.h:4359
Inline: True
Inline callers:
  - mm/mmap_lock.c:get_mm_memcg_path
```
```
In mm/memory.c (ffffffff814205c4)
Location: include/linux/atomic/atomic-arch-fallback.h:4359
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
```
In mm/memory_hotplug.c (ffffffff81452516)
Location: include/linux/atomic/atomic-arch-fallback.h:4359
Inline: True
Inline callers:
  - mm/memory_hotplug.c:pfn_to_online_page
```
```
In mm/slub.c (ffffffff81455b3a)
Location: include/linux/atomic/atomic-arch-fallback.h:4359
Inline: True
Inline callers:
  - mm/slub.c:__memcg_slab_free_hook
```
```
In mm/swap_state.c (ffffffff81465bb4)
Location: include/linux/atomic/atomic-arch-fallback.h:4359
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:filemap_get_incore_folio
```
```
In mm/swapfile.c (ffffffff8146d21b)
Location: include/linux/atomic/atomic-arch-fallback.h:4359
Inline: True
Inline callers:
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:get_swap_device
```
```
In mm/zswap.c (ffffffff81470e7c)
Location: include/linux/atomic/atomic-arch-fallback.h:4359
Inline: True
Inline callers:
  - mm/zswap.c:zswap_store
  - mm/zswap.c:zswap_store
  - mm/zswap.c:zswap_store
  - mm/zswap.c:zswap_store
  - mm/zswap.c:zswap_store
  - mm/zswap.c:shrink_worker
  - mm/zswap.c:zswap_free_entry
```
```
In mm/hugetlb.c (ffffffff8147ab0b)
Location: include/linux/atomic/atomic-arch-fallback.h:4359
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:alloc_hugetlb_folio
  - mm/hugetlb.c:alloc_hugetlb_folio
  - mm/hugetlb.c:alloc_hugetlb_folio
  - mm/hugetlb.c:clear_vma_resv_huge_pages
  - mm/hugetlb.c:coalesce_file_region
  - mm/hugetlb.c:coalesce_file_region
```
```
In mm/memcontrol.c (ffffffff814c0cb5)
Location: include/linux/atomic/atomic-arch-fallback.h:4359
Inline: True
Inline callers:
  - mm/memcontrol.c:obj_cgroup_may_zswap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_sk_free
  - mm/memcontrol.c:uncharge_folio
  - mm/memcontrol.c:uncharge_folio
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:mem_cgroup_swapin_charge_folio
  - mm/memcontrol.c:__mem_cgroup_charge
  - mm/memcontrol.c:mem_cgroup_exit
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:__mem_cgroup_free
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_event_remove
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:obj_cgroup_charge
  - mm/memcontrol.c:refill_obj_stock
  - mm/memcontrol.c:drain_obj_stock
  - mm/memcontrol.c:mod_objcg_state
  - mm/memcontrol.c:__memcg_kmem_uncharge_page
  - mm/memcontrol.c:__memcg_kmem_charge_page
  - mm/memcontrol.c:obj_cgroup_uncharge_pages
  - mm/memcontrol.c:current_objcg_update
  - mm/memcontrol.c:current_objcg_update
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:drain_local_stock
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_oom_trylock
  - mm/memcontrol.c:mem_cgroup_oom_trylock
  - mm/memcontrol.c:mem_cgroup_scan_tasks
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
```
```
In mm/hugetlb_cgroup.c (ffffffff814c37f2)
Location: include/linux/atomic/atomic-arch-fallback.h:4359
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_file_region
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_counter
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_cgroup_rsvd
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
```
```
In mm/memory-failure.c (ffffffff814c7930)
Location: include/linux/atomic/atomic-arch-fallback.h:4359
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure_dev_pagemap
```
```
In mm/memremap.c (ffffffff814d518c)
Location: include/linux/atomic/atomic-arch-fallback.h:4359
Inline: True
Inline callers:
  - mm/memremap.c:free_zone_device_page
  - mm/memremap.c:get_dev_pagemap
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:memunmap_pages
```
```
In fs/open.c (ffffffff814d8d40)
Location: include/linux/atomic/atomic-arch-fallback.h:4359
Inline: True
Inline callers:
  - fs/open.c:do_faccessat
```
```
In fs/file_table.c (ffffffff814e29ba)
Location: include/linux/atomic/atomic-arch-fallback.h:4359
Inline: True
Inline callers:
  - fs/file_table.c:__fput
  - fs/file_table.c:init_file
```
```
In fs/inode.c (ffffffff81509b59)
Location: include/linux/atomic/atomic-arch-fallback.h:4359
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
```
```
In fs/fs-writeback.c (ffffffff8152d314)
Location: include/linux/atomic/atomic-arch-fallback.h:4359
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:wbc_detach_inode
  - fs/fs-writeback.c:cleanup_offline_cgwb
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/fs_context.c (ffffffff81538c2d)
Location: include/linux/atomic/atomic-arch-fallback.h:4359
Inline: True
Inline callers:
  - fs/fs_context.c:put_fs_context
```
```
In fs/notify/group.c (ffffffff81548176)
Location: include/linux/atomic/atomic-arch-fallback.h:4359
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_put_group
```
```
In fs/aio.c (ffffffff8155e7fc)
Location: include/linux/atomic/atomic-arch-fallback.h:4359
Inline: True
Inline callers:
  - fs/aio.c:do_io_getevents
  - fs/aio.c:__ia32_sys_io_cancel
  - fs/aio.c:__x64_sys_io_cancel
  - fs/aio.c:__ia32_compat_sys_io_submit
  - fs/aio.c:__ia32_sys_io_submit
  - fs/aio.c:__x64_sys_io_submit
  - fs/aio.c:io_submit_one
  - fs/aio.c:io_submit_one
  - fs/aio.c:aio_poll_wake
  - fs/aio.c:aio_poll_complete_work
  - fs/aio.c:aio_poll_put_work
  - fs/aio.c:aio_fsync_work
  - fs/aio.c:aio_fsync_work
  - fs/aio.c:aio_complete_rw
  - fs/aio.c:__ia32_sys_io_destroy
  - fs/aio.c:__x64_sys_io_destroy
  - fs/aio.c:__ia32_compat_sys_io_setup
  - fs/aio.c:__ia32_sys_io_setup
  - fs/aio.c:__x64_sys_io_setup
  - fs/aio.c:free_ioctx_users
```
```
In fs/coredump.c (ffffffff8158670d)
Location: include/linux/atomic/atomic-arch-fallback.h:4359
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/array.c (ffffffff815abbb2)
Location: include/linux/atomic/atomic-arch-fallback.h:4359
Inline: True
Inline callers:
  - fs/proc/array.c:task_state
```
```
In security/keys/keyctl.c (ffffffff816c953e)
Location: include/linux/atomic/atomic-arch-fallback.h:4359
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_session_to_parent
```
```
In security/keys/process_keys.c (ffffffff816cb5c7)
Location: include/linux/atomic/atomic-arch-fallback.h:4359
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/request_key.c (ffffffff816cbee6)
Location: include/linux/atomic/atomic-arch-fallback.h:4359
Inline: True
Inline callers:
  - security/keys/request_key.c:call_sbin_request_key
```
```
In security/keys/request_key_auth.c (ffffffff816cccb8)
Location: include/linux/atomic/atomic-arch-fallback.h:4359
Inline: True
```
```
In security/apparmor/audit.c (ffffffff81736e4a)
Location: include/linux/atomic/atomic-arch-fallback.h:4359
Inline: True
```
```
In security/apparmor/domain.c (ffffffff81742035)
Location: include/linux/atomic/atomic-arch-fallback.h:4359
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:may_change_ptraced_domain
```
```
In security/apparmor/lsm.c (ffffffff81752a76)
Location: include/linux/atomic/atomic-arch-fallback.h:4359
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
```
```
In block/bio.c (ffffffff817ab52d)
Location: include/linux/atomic/atomic-arch-fallback.h:4359
Inline: True
Inline callers:
  - block/bio.c:bio_uninit
```
```
In block/blk-core.c (ffffffff817b4e94)
Location: include/linux/atomic/atomic-arch-fallback.h:4359
Inline: True
Inline callers:
  - block/blk-core.c:bio_poll
  - block/blk-core.c:__submit_bio
  - block/blk-core.c:__submit_bio
  - block/blk-core.c:__bio_queue_enter
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-mq.c (ffffffff817c1f0d)
Location: include/linux/atomic/atomic-arch-fallback.h:4359
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_offline
  - block/blk-mq.c:blk_mq_dispatch_plug_list
  - block/blk-mq.c:blk_mq_end_request_batch
  - block/blk-mq.c:blk_mq_end_request_batch
```
```
In block/blk-cgroup.c (ffffffff817e6558)
Location: include/linux/atomic/atomic-arch-fallback.h:4359
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkcg_activate_policy
  - block/blk-cgroup.c:blkcg_activate_policy
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:__blkg_release
  - block/blk-cgroup.c:blkg_free_workfn
```
```
In block/blk-cgroup-fc-appid.c (ffffffff817e7058)
Location: include/linux/atomic/atomic-arch-fallback.h:4359
Inline: True
Inline callers:
  - block/blk-cgroup-fc-appid.c:blkcg_set_fc_appid
  - block/blk-cgroup-fc-appid.c:blkcg_set_fc_appid
```
```
In block/blk-throttle.c (ffffffff817ea083)
Location: include/linux/atomic/atomic-arch-fallback.h:4359
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:throtl_pop_queued
```
```
In io_uring/io_uring.c (ffffffff81816f09)
Location: include/linux/atomic/atomic-arch-fallback.h:4359
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_activate_pollwq
  - io_uring/io_uring.c:io_activate_pollwq_cb
  - io_uring/io_uring.c:io_ring_ctx_free
  - io_uring/io_uring.c:io_req_caches_free
  - io_uring/io_uring.c:io_init_req
  - io_uring/io_uring.c:io_fallback_tw
  - io_uring/io_uring.c:io_fallback_tw
  - io_uring/io_uring.c:ctx_flush_and_put
  - io_uring/io_uring.c:io_clean_op
  - io_uring/io_uring.c:io_fallback_req_func
```
```
In io_uring/register.c (ffffffff8182bdb8)
Location: include/linux/atomic/atomic-arch-fallback.h:4359
Inline: True
Inline callers:
  - io_uring/register.c:__io_uring_register
  - io_uring/register.c:io_unregister_personality
```
```
In lib/percpu-refcount.c (ffffffff8185d793)
Location: include/linux/atomic/atomic-arch-fallback.h:4359
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_kill_and_confirm
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In drivers/pci/p2pdma.c (ffffffff819a9b27)
Location: include/linux/atomic/atomic-arch-fallback.h:4359
Inline: True
Inline callers:
  - drivers/pci/p2pdma.c:pci_p2pmem_free_sgl
  - drivers/pci/p2pdma.c:p2pdma_page_free
  - drivers/pci/p2pdma.c:p2pmem_alloc_mmap
```
```
In drivers/base/firmware_loader/main.c (ffffffff81bb3c9c)
Location: include/linux/atomic/atomic-arch-fallback.h:4359
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
```
```
In drivers/block/loop.c (ffffffff81bd0d67)
Location: include/linux/atomic/atomic-arch-fallback.h:4359
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_process_work
  - drivers/block/loop.c:loop_free_idle_workers
```
```
In drivers/scsi/scsi_lib.c (ffffffff81c28b27)
Location: include/linux/atomic/atomic-arch-fallback.h:4359
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/usb/core/devio.c (ffffffff81d4df56)
Location: include/linux/atomic/atomic-arch-fallback.h:4359
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:async_completed
  - drivers/usb/core/devio.c:free_async
```
```
In drivers/md/md.c (ffffffff81e16b0f)
Location: include/linux/atomic/atomic-arch-fallback.h:4359
Inline: True
Inline callers:
  - drivers/md/md.c:md_end_clone_io
  - drivers/md/md.c:md_write_start
  - drivers/md/md.c:mddev_init
  - drivers/md/md.c:submit_flushes
  - drivers/md/md.c:md_end_flush
  - drivers/md/md.c:md_handle_request
  - drivers/md/md.c:md_handle_request
```
```
In net/core/sock.c (ffffffff81ec668f)
Location: include/linux/atomic/atomic-arch-fallback.h:4359
Inline: True
Inline callers:
  - net/core/sock.c:__sk_destruct
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_getsockopt
```
```
In net/unix/af_unix.c (ffffffff8207c11f)
Location: include/linux/atomic/atomic-arch-fallback.h:4359
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:init_peercred
```
```
In net/dns_resolver/dns_key.c (ffffffff83d5212c)
Location: include/linux/atomic/atomic-arch-fallback.h:4359
Inline: True
Inline callers:
  - net/dns_resolver/dns_key.c:exit_dns_resolver
  - net/dns_resolver/dns_key.c:init_dns_resolver
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
