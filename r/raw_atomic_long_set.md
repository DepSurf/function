# Function: <code>raw_atomic_long_set</code>

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
In arch/x86/events/core.c (ffffffff8100779e)
Location: include/linux/atomic/atomic-long.h:76
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_setup_perfctr
```
```
In arch/x86/events/amd/ibs.c (ffffffff8100eef6)
Location: include/linux/atomic/atomic-long.h:76
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_start
  - arch/x86/events/amd/ibs.c:perf_ibs_start
  - arch/x86/events/amd/ibs.c:perf_ibs_start
  - arch/x86/events/amd/ibs.c:perf_ibs_init
```
```
In arch/x86/events/msr.c (ffffffff8101021c)
Location: include/linux/atomic/atomic-long.h:76
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_event_update
```
```
In arch/x86/events/intel/core.c (ffffffff81014e32)
Location: include/linux/atomic/atomic-long.h:76
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:handle_pmi_common
```
```
In arch/x86/events/intel/bts.c (ffffffff810167b4)
Location: include/linux/atomic/atomic-long.h:76
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_buffer_reset
  - arch/x86/events/intel/bts.c:bts_update
```
```
In arch/x86/events/intel/ds.c (ffffffff81017ddc)
Location: include/linux/atomic/atomic-long.h:76
Inline: True
```
```
In arch/x86/events/intel/pt.c (ffffffff81020f3a)
Location: include/linux/atomic/atomic-long.h:76
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_buffer_reset_offsets
  - arch/x86/events/intel/pt.c:pt_buffer_reset_offsets
  - arch/x86/events/intel/pt.c:pt_update_head
```
```
In arch/x86/events/intel/uncore.c (ffffffff81023c23)
Location: include/linux/atomic/atomic-long.h:76
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff810e7e5a)
Location: include/linux/atomic/atomic-long.h:76
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:param_set_local64
```
```
In kernel/fork.c (ffffffff810f138b)
Location: include/linux/atomic/atomic-long.h:76
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
  - kernel/fork.c:mm_init
```
```
In kernel/workqueue.c (ffffffff811207ee)
Location: include/linux/atomic/atomic-long.h:76
Inline: True
Inline callers:
  - kernel/workqueue.c:__cancel_work
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:try_to_grab_pending
```
```
In kernel/locking/mutex.c (ffffffff8118d255)
Location: include/linux/atomic/atomic-long.h:76
Inline: True
Inline callers:
  - kernel/locking/mutex.c:__mutex_init
```
```
In kernel/locking/rwsem.c (ffffffff8118dfcb)
Location: include/linux/atomic/atomic-long.h:76
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:downgrade_write
  - kernel/locking/rwsem.c:up_write
  - kernel/locking/rwsem.c:down_write_trylock
  - kernel/locking/rwsem.c:down_write_killable
  - kernel/locking/rwsem.c:down_write
  - kernel/locking/rwsem.c:down_read_trylock
  - kernel/locking/rwsem.c:down_read_killable
  - kernel/locking/rwsem.c:down_read_interruptible
  - kernel/locking/rwsem.c:down_read
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_mark_wake
  - kernel/locking/rwsem.c:__init_rwsem
  - kernel/locking/rwsem.c:__init_rwsem
```
```
In kernel/printk/printk_ringbuffer.c (ffffffff811a5bbd)
Location: include/linux/atomic/atomic-long.h:76
Inline: True
Inline callers:
  - kernel/printk/printk_ringbuffer.c:prb_init
  - kernel/printk/printk_ringbuffer.c:prb_init
  - kernel/printk/printk_ringbuffer.c:prb_init
  - kernel/printk/printk_ringbuffer.c:prb_init
  - kernel/printk/printk_ringbuffer.c:prb_init
  - kernel/printk/printk_ringbuffer.c:prb_init
  - kernel/printk/printk_ringbuffer.c:prb_init
  - kernel/printk/printk_ringbuffer.c:prb_final_commit
  - kernel/printk/printk_ringbuffer.c:prb_commit
  - kernel/printk/printk_ringbuffer.c:prb_reserve
  - kernel/printk/printk_ringbuffer.c:desc_read
```
```
In kernel/dma/swiotlb.c (ffffffff836d2005)
Location: include/linux/atomic/atomic-long.h:76
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_create_default_debugfs
  - kernel/dma/swiotlb.c:swiotlb_create_default_debugfs
  - kernel/dma/swiotlb.c:io_tlb_hiwater_set
```
```
In kernel/time/namespace.c (ffffffff81206c89)
Location: include/linux/atomic/atomic-long.h:76
Inline: True
Inline callers:
  - kernel/time/namespace.c:copy_time_ns
```
```
In kernel/acct.c (ffffffff81211d5d)
Location: include/linux/atomic/atomic-long.h:76
Inline: True
Inline callers:
  - kernel/acct.c:acct_on
```
```
In kernel/cgroup/namespace.c (ffffffff81227af4)
Location: include/linux/atomic/atomic-long.h:76
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
```
```
In kernel/cgroup/misc.c (ffffffff81235a24)
Location: include/linux/atomic/atomic-long.h:76
Inline: True
Inline callers:
  - kernel/cgroup/misc.c:misc_cg_alloc
```
```
In kernel/utsname.c (ffffffff81235c2f)
Location: include/linux/atomic/atomic-long.h:76
Inline: True
Inline callers:
  - kernel/utsname.c:clone_uts_ns
```
```
In kernel/user_namespace.c (ffffffff81237cdc)
Location: include/linux/atomic/atomic-long.h:76
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In kernel/pid_namespace.c (ffffffff81238a53)
Location: include/linux/atomic/atomic-long.h:76
Inline: True
Inline callers:
  - kernel/pid_namespace.c:create_pid_namespace
```
```
In kernel/audit_tree.c (ffffffff81249d17)
Location: include/linux/atomic/atomic-long.h:76
Inline: True
Inline callers:
  - kernel/audit_tree.c:alloc_chunk
```
```
In kernel/trace/ring_buffer.c (ffffffff8127872f)
Location: include/linux/atomic/atomic-long.h:76
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:rb_reset_cpu
  - kernel/trace/ring_buffer.c:rb_reset_cpu
  - kernel/trace/ring_buffer.c:rb_reset_cpu
  - kernel/trace/ring_buffer.c:rb_reset_cpu
  - kernel/trace/ring_buffer.c:rb_reset_cpu
  - kernel/trace/ring_buffer.c:rb_reset_cpu
  - kernel/trace/ring_buffer.c:rb_reset_cpu
  - kernel/trace/ring_buffer.c:rb_reset_cpu
  - kernel/trace/ring_buffer.c:rb_reset_cpu
  - kernel/trace/ring_buffer.c:rb_reset_cpu
  - kernel/trace/ring_buffer.c:rb_reset_cpu
  - kernel/trace/ring_buffer.c:rb_reset_cpu
  - kernel/trace/ring_buffer.c:rb_reset_cpu
  - kernel/trace/ring_buffer.c:rb_reset_cpu
  - kernel/trace/ring_buffer.c:rb_reset_cpu
  - kernel/trace/ring_buffer.c:rb_reset_cpu
  - kernel/trace/ring_buffer.c:rb_reset_cpu
  - kernel/trace/ring_buffer.c:rb_reset_cpu
  - kernel/trace/ring_buffer.c:rb_reset_cpu
  - kernel/trace/ring_buffer.c:rb_reset_cpu
  - kernel/trace/ring_buffer.c:rb_reset_cpu
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/events/core.c (ffffffff81370678)
Location: include/linux/atomic/atomic-long.h:76
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:task_clock_event_init
  - kernel/events/core.c:task_clock_event_del
  - kernel/events/core.c:task_clock_event_add
  - kernel/events/core.c:task_clock_event_add
  - kernel/events/core.c:cpu_clock_event_init
  - kernel/events/core.c:cpu_clock_event_del
  - kernel/events/core.c:cpu_clock_event_add
  - kernel/events/core.c:cpu_clock_event_add
  - kernel/events/core.c:perf_event_pause
  - kernel/events/core.c:_perf_event_reset
  - kernel/events/core.c:perf_event_context_sched_out
```
```
In mm/vmscan.c (ffffffff813a993f)
Location: include/linux/atomic/atomic-long.h:76
Inline: True
```
```
In mm/vmstat.c (ffffffff813c7921)
Location: include/linux/atomic/atomic-long.h:76
Inline: True
Inline callers:
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
```
```
In mm/mm_init.c (ffffffff836e1224)
Location: include/linux/atomic/atomic-long.h:76
Inline: True
Inline callers:
  - mm/mm_init.c:free_area_init_core
  - mm/mm_init.c:free_area_init_core_hotplug
```
```
In mm/memblock.c (ffffffff836e7519)
Location: include/linux/atomic/atomic-long.h:76
Inline: True
Inline callers:
  - mm/memblock.c:reset_all_zones_managed_pages
```
```
In mm/swap_state.c (ffffffff8142c697)
Location: include/linux/atomic/atomic-long.h:76
Inline: True
Inline callers:
  - mm/swap_state.c:swap_vma_readahead
  - mm/swap_state.c:swap_cache_get_folio
```
```
In mm/slub.c (ffffffff8145ff81)
Location: include/linux/atomic/atomic-long.h:76
Inline: True
Inline callers:
  - mm/slub.c:slab_memory_callback
  - mm/slub.c:slab_memory_callback
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:early_kmem_cache_node_alloc
  - mm/slub.c:early_kmem_cache_node_alloc
```
```
In mm/page_counter.c (ffffffff81482860)
Location: include/linux/atomic/atomic-long.h:76
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_cancel
```
```
In mm/memcontrol.c (ffffffff82147d7f)
Location: include/linux/atomic/atomic-long.h:76
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
```
```
In mm/hugetlb_cgroup.c (ffffffff81493003)
Location: include/linux/atomic/atomic-long.h:76
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
```
```
In fs/file_table.c (ffffffff814b0ef9)
Location: include/linux/atomic/atomic-long.h:76
Inline: True
Inline callers:
  - fs/file_table.c:init_file
```
```
In fs/namespace.c (ffffffff814e03a3)
Location: include/linux/atomic/atomic-long.h:76
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In fs/nsfs.c (ffffffff81502bb9)
Location: include/linux/atomic/atomic-long.h:76
Inline: True
Inline callers:
  - fs/nsfs.c:ns_prune_dentry
```
```
In ipc/namespace.c (ffffffff816854f1)
Location: include/linux/atomic/atomic-long.h:76
Inline: True
```
```
In block/blk-ioc.c (ffffffff817769c4)
Location: include/linux/atomic/atomic-long.h:76
Inline: True
Inline callers:
  - block/blk-ioc.c:alloc_io_context
```
```
In block/blk-iocost.c (ffffffff817accb4)
Location: include/linux/atomic/atomic-long.h:76
Inline: True
Inline callers:
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-iocost.c:blk_iocost_init
```
```
In lib/percpu-refcount.c (ffffffff81817b46)
Location: include/linux/atomic/atomic-long.h:76
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_init
```
```
In lib/genalloc.c (ffffffff8182e093)
Location: include/linux/atomic/atomic-long.h:76
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_add_owner
```
```
In drivers/tty/tty_ldsem.c (ffffffff81aa1035)
Location: include/linux/atomic/atomic-long.h:76
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:__init_ldsem
```
```
In drivers/iommu/intel/perfmon.c (ffffffff81b1ae88)
Location: include/linux/atomic/atomic-long.h:76
Inline: True
Inline callers:
  - drivers/iommu/intel/perfmon.c:iommu_pmu_start
```
```
In net/core/gen_stats.c (ffffffff81e22425)
Location: include/linux/atomic/atomic-long.h:76
Inline: True
Inline callers:
  - net/core/gen_stats.c:gnet_stats_basic_sync_init
  - net/core/gen_stats.c:gnet_stats_basic_sync_init
```
```
In net/core/net_namespace.c (ffffffff81e23565)
Location: include/linux/atomic/atomic-long.h:76
Inline: True
Inline callers:
  - net/core/net_namespace.c:net_ns_net_init
```
```
In net/core/page_pool.c (ffffffff81e841cb)
Location: include/linux/atomic/atomic-long.h:76
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_alloc_frag
```
```
In net/ipv4/nexthop.c (ffffffff81f712bb)
Location: include/linux/atomic/atomic-long.h:76
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_res_grp_activity_update
  - net/ipv4/nexthop.c:nh_res_table_upkeep
  - net/ipv4/nexthop.c:nh_res_bucket_migrate
```
```
In net/unix/af_unix.c (ffffffff81fabff5)
Location: include/linux/atomic/atomic-long.h:76
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
```
```
In net/packet/af_packet.c (ffffffff82029e42)
Location: include/linux/atomic/atomic-long.h:76
Inline: True
Inline callers:
  - net/packet/af_packet.c:fanout_add
  - net/packet/af_packet.c:fanout_add
  - net/packet/af_packet.c:fanout_add
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
In arch/x86/events/core.c (ffffffff8100cebe)
Location: include/linux/atomic/atomic-long.h:76
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_setup_perfctr
```
```
In arch/x86/events/amd/ibs.c (ffffffff81014636)
Location: include/linux/atomic/atomic-long.h:76
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_start
  - arch/x86/events/amd/ibs.c:perf_ibs_start
  - arch/x86/events/amd/ibs.c:perf_ibs_start
  - arch/x86/events/amd/ibs.c:perf_ibs_init
```
```
In arch/x86/events/msr.c (ffffffff810159ec)
Location: include/linux/atomic/atomic-long.h:76
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_event_update
```
```
In arch/x86/events/intel/core.c (ffffffff81019ded)
Location: include/linux/atomic/atomic-long.h:76
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:handle_pmi_common
```
```
In arch/x86/events/intel/bts.c (ffffffff8101c2f4)
Location: include/linux/atomic/atomic-long.h:76
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_buffer_reset
  - arch/x86/events/intel/bts.c:bts_update
```
```
In arch/x86/events/intel/ds.c (ffffffff8101d94c)
Location: include/linux/atomic/atomic-long.h:76
Inline: True
```
```
In arch/x86/events/intel/pt.c (ffffffff8102705a)
Location: include/linux/atomic/atomic-long.h:76
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_buffer_reset_offsets
  - arch/x86/events/intel/pt.c:pt_buffer_reset_offsets
  - arch/x86/events/intel/pt.c:pt_update_head
```
```
In arch/x86/events/intel/uncore.c (ffffffff81029d53)
Location: include/linux/atomic/atomic-long.h:76
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff810f01ea)
Location: include/linux/atomic/atomic-long.h:76
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:param_set_local64
```
```
In kernel/fork.c (ffffffff810fa75b)
Location: include/linux/atomic/atomic-long.h:76
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
  - kernel/fork.c:mm_init
```
```
In kernel/workqueue.c (ffffffff8112917e)
Location: include/linux/atomic/atomic-long.h:76
Inline: True
Inline callers:
  - kernel/workqueue.c:__cancel_work
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:try_to_grab_pending
```
```
In kernel/cred.c (ffffffff8113f064)
Location: include/linux/atomic/atomic-long.h:76
Inline: True
Inline callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:cred_alloc_blank
```
```
In kernel/locking/mutex.c (ffffffff8119bc05)
Location: include/linux/atomic/atomic-long.h:76
Inline: True
Inline callers:
  - kernel/locking/mutex.c:__mutex_init
```
```
In kernel/locking/rwsem.c (ffffffff8119c97b)
Location: include/linux/atomic/atomic-long.h:76
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:downgrade_write
  - kernel/locking/rwsem.c:up_write
  - kernel/locking/rwsem.c:down_write_trylock
  - kernel/locking/rwsem.c:down_write_killable
  - kernel/locking/rwsem.c:down_write
  - kernel/locking/rwsem.c:down_read_trylock
  - kernel/locking/rwsem.c:down_read_killable
  - kernel/locking/rwsem.c:down_read_interruptible
  - kernel/locking/rwsem.c:down_read
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_mark_wake
  - kernel/locking/rwsem.c:__init_rwsem
  - kernel/locking/rwsem.c:__init_rwsem
```
```
In kernel/printk/nbcon.c (ffffffff811b3c28)
Location: include/linux/atomic/atomic-long.h:76
Inline: True
Inline callers:
  - kernel/printk/nbcon.c:nbcon_init
```
```
In kernel/printk/printk_ringbuffer.c (ffffffff811b56ad)
Location: include/linux/atomic/atomic-long.h:76
Inline: True
Inline callers:
  - kernel/printk/printk_ringbuffer.c:prb_init
  - kernel/printk/printk_ringbuffer.c:prb_init
  - kernel/printk/printk_ringbuffer.c:prb_init
  - kernel/printk/printk_ringbuffer.c:prb_init
  - kernel/printk/printk_ringbuffer.c:prb_init
  - kernel/printk/printk_ringbuffer.c:prb_init
  - kernel/printk/printk_ringbuffer.c:prb_init
  - kernel/printk/printk_ringbuffer.c:prb_final_commit
  - kernel/printk/printk_ringbuffer.c:prb_commit
  - kernel/printk/printk_ringbuffer.c:prb_reserve
  - kernel/printk/printk_ringbuffer.c:desc_read
```
```
In kernel/rcu/rcu_segcblist.c (ffffffff811e32b4)
Location: include/linux/atomic/atomic-long.h:76
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
```
```
In kernel/dma/swiotlb.c (ffffffff83903cb5)
Location: include/linux/atomic/atomic-long.h:76
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_create_default_debugfs
  - kernel/dma/swiotlb.c:swiotlb_create_default_debugfs
  - kernel/dma/swiotlb.c:io_tlb_hiwater_set
```
```
In kernel/time/namespace.c (ffffffff8121de99)
Location: include/linux/atomic/atomic-long.h:76
Inline: True
Inline callers:
  - kernel/time/namespace.c:copy_time_ns
```
```
In kernel/acct.c (ffffffff81229408)
Location: include/linux/atomic/atomic-long.h:76
Inline: True
Inline callers:
  - kernel/acct.c:acct_on
```
```
In kernel/cgroup/namespace.c (ffffffff8123f904)
Location: include/linux/atomic/atomic-long.h:76
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
```
```
In kernel/utsname.c (ffffffff8124f8af)
Location: include/linux/atomic/atomic-long.h:76
Inline: True
Inline callers:
  - kernel/utsname.c:clone_uts_ns
```
```
In kernel/user_namespace.c (ffffffff812517dc)
Location: include/linux/atomic/atomic-long.h:76
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In kernel/pid_namespace.c (ffffffff81252723)
Location: include/linux/atomic/atomic-long.h:76
Inline: True
Inline callers:
  - kernel/pid_namespace.c:create_pid_namespace
```
```
In kernel/audit_tree.c (ffffffff81263c27)
Location: include/linux/atomic/atomic-long.h:76
Inline: True
Inline callers:
  - kernel/audit_tree.c:alloc_chunk
```
```
In kernel/trace/ring_buffer.c (ffffffff81293270)
Location: include/linux/atomic/atomic-long.h:76
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:rb_reset_cpu
  - kernel/trace/ring_buffer.c:rb_reset_cpu
  - kernel/trace/ring_buffer.c:rb_reset_cpu
  - kernel/trace/ring_buffer.c:rb_reset_cpu
  - kernel/trace/ring_buffer.c:rb_reset_cpu
  - kernel/trace/ring_buffer.c:rb_reset_cpu
  - kernel/trace/ring_buffer.c:rb_reset_cpu
  - kernel/trace/ring_buffer.c:rb_reset_cpu
  - kernel/trace/ring_buffer.c:rb_reset_cpu
  - kernel/trace/ring_buffer.c:rb_reset_cpu
  - kernel/trace/ring_buffer.c:rb_reset_cpu
  - kernel/trace/ring_buffer.c:rb_reset_cpu
  - kernel/trace/ring_buffer.c:rb_reset_cpu
  - kernel/trace/ring_buffer.c:rb_reset_cpu
  - kernel/trace/ring_buffer.c:rb_reset_cpu
  - kernel/trace/ring_buffer.c:rb_reset_cpu
  - kernel/trace/ring_buffer.c:rb_reset_cpu
  - kernel/trace/ring_buffer.c:rb_reset_cpu
  - kernel/trace/ring_buffer.c:rb_reset_cpu
  - kernel/trace/ring_buffer.c:rb_reset_cpu
  - kernel/trace/ring_buffer.c:rb_reset_cpu
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/events/core.c (ffffffff81399978)
Location: include/linux/atomic/atomic-long.h:76
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:task_clock_event_init
  - kernel/events/core.c:task_clock_event_del
  - kernel/events/core.c:task_clock_event_add
  - kernel/events/core.c:task_clock_event_add
  - kernel/events/core.c:cpu_clock_event_init
  - kernel/events/core.c:cpu_clock_event_del
  - kernel/events/core.c:cpu_clock_event_add
  - kernel/events/core.c:cpu_clock_event_add
  - kernel/events/core.c:perf_event_pause
  - kernel/events/core.c:_perf_event_reset
  - kernel/events/core.c:perf_event_context_sched_out
```
```
In mm/vmscan.c (ffffffff813d312f)
Location: include/linux/atomic/atomic-long.h:76
Inline: True
```
```
In mm/vmstat.c (ffffffff813f2301)
Location: include/linux/atomic/atomic-long.h:76
Inline: True
Inline callers:
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
```
```
In mm/mm_init.c (ffffffff83913b24)
Location: include/linux/atomic/atomic-long.h:76
Inline: True
Inline callers:
  - mm/mm_init.c:free_area_init_core
  - mm/mm_init.c:free_area_init_core_hotplug
```
```
In mm/memblock.c (ffffffff83919ac9)
Location: include/linux/atomic/atomic-long.h:76
Inline: True
Inline callers:
  - mm/memblock.c:reset_all_zones_managed_pages
```
```
In mm/slub.c (ffffffff8145d321)
Location: include/linux/atomic/atomic-long.h:76
Inline: True
Inline callers:
  - mm/slub.c:slab_memory_callback
  - mm/slub.c:slab_memory_callback
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:early_kmem_cache_node_alloc
  - mm/slub.c:early_kmem_cache_node_alloc
```
```
In mm/swap_state.c (ffffffff81465dd6)
Location: include/linux/atomic/atomic-long.h:76
Inline: True
Inline callers:
  - mm/swap_state.c:swap_vma_readahead
  - mm/swap_state.c:swap_cache_get_folio
```
```
In mm/zswap.c (ffffffff81470555)
Location: include/linux/atomic/atomic-long.h:76
Inline: True
Inline callers:
  - mm/zswap.c:zswap_lruvec_state_init
```
```
In mm/page_counter.c (ffffffff814b1be0)
Location: include/linux/atomic/atomic-long.h:76
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_cancel
```
```
In mm/memcontrol.c (ffffffff8222a6b0)
Location: include/linux/atomic/atomic-long.h:76
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
```
```
In mm/hugetlb_cgroup.c (ffffffff814c2a38)
Location: include/linux/atomic/atomic-long.h:76
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
```
```
In fs/file_table.c (ffffffff814e2702)
Location: include/linux/atomic/atomic-long.h:76
Inline: True
Inline callers:
  - fs/file_table.c:init_file
```
```
In fs/namespace.c (ffffffff81513664)
Location: include/linux/atomic/atomic-long.h:76
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In fs/nsfs.c (ffffffff81537809)
Location: include/linux/atomic/atomic-long.h:76
Inline: True
Inline callers:
  - fs/nsfs.c:ns_prune_dentry
```
```
In ipc/namespace.c (ffffffff816c1911)
Location: include/linux/atomic/atomic-long.h:76
Inline: True
```
```
In block/blk-ioc.c (ffffffff817b8bf4)
Location: include/linux/atomic/atomic-long.h:76
Inline: True
Inline callers:
  - block/blk-ioc.c:alloc_io_context
```
```
In block/blk-iocost.c (ffffffff817f0ab3)
Location: include/linux/atomic/atomic-long.h:76
Inline: True
Inline callers:
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-iocost.c:blk_iocost_init
```
```
In lib/percpu-refcount.c (ffffffff8185ce42)
Location: include/linux/atomic/atomic-long.h:76
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_init
```
```
In lib/genalloc.c (ffffffff8187fc53)
Location: include/linux/atomic/atomic-long.h:76
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_add_owner
```
```
In drivers/tty/tty_ldsem.c (ffffffff81af3a95)
Location: include/linux/atomic/atomic-long.h:76
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:__init_ldsem
```
```
In drivers/iommu/intel/perfmon.c (ffffffff81b709b8)
Location: include/linux/atomic/atomic-long.h:76
Inline: True
Inline callers:
  - drivers/iommu/intel/perfmon.c:iommu_pmu_start
```
```
In drivers/net/virtio_net.c (ffffffff81d0c990)
Location: include/linux/atomic/atomic-long.h:76
Inline: True
```
```
In net/core/skbuff.c (ffffffff81ed1361)
Location: include/linux/atomic/atomic-long.h:76
Inline: True
Inline callers:
  - net/core/skbuff.c:napi_pp_put_page
```
```
In net/core/gen_stats.c (ffffffff81ee0365)
Location: include/linux/atomic/atomic-long.h:76
Inline: True
Inline callers:
  - net/core/gen_stats.c:gnet_stats_basic_sync_init
  - net/core/gen_stats.c:gnet_stats_basic_sync_init
```
```
In net/core/net_namespace.c (ffffffff81ee14c5)
Location: include/linux/atomic/atomic-long.h:76
Inline: True
Inline callers:
  - net/core/net_namespace.c:net_ns_net_init
```
```
In net/core/xdp.c (ffffffff81f397a7)
Location: include/linux/atomic/atomic-long.h:76
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_return
```
```
In net/core/page_pool.c (ffffffff81f448aa)
Location: include/linux/atomic/atomic-long.h:76
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_alloc_frag
  - net/core/page_pool.c:page_pool_alloc_frag
  - net/core/page_pool.c:page_pool_put_page_bulk
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
  - net/core/page_pool.c:__page_pool_alloc_page_order
```
```
In net/ipv4/nexthop.c (ffffffff82037a1b)
Location: include/linux/atomic/atomic-long.h:76
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_res_grp_activity_update
  - net/ipv4/nexthop.c:nh_res_table_upkeep
  - net/ipv4/nexthop.c:nh_res_bucket_migrate
```
```
In net/unix/af_unix.c (ffffffff82079415)
Location: include/linux/atomic/atomic-long.h:76
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
```
```
In net/packet/af_packet.c (ffffffff820f9941)
Location: include/linux/atomic/atomic-long.h:76
Inline: True
Inline callers:
  - net/packet/af_packet.c:fanout_add
  - net/packet/af_packet.c:fanout_add
  - net/packet/af_packet.c:fanout_add
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
