# Function: <code>arch_atomic_long_set</code>

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
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81008cc9)
Location: include/linux/atomic/atomic-long.h:39
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_setup_perfctr
```
```
In arch/x86/events/amd/ibs.c (ffffffff8100be6c)
Location: include/linux/atomic/atomic-long.h:39
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
In arch/x86/events/msr.c (ffffffff8100cae9)
Location: include/linux/atomic/atomic-long.h:39
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_event_update
```
```
In arch/x86/events/intel/core.c (ffffffff8100fb14)
Location: include/linux/atomic/atomic-long.h:39
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:handle_pmi_common
```
```
In arch/x86/events/intel/bts.c (ffffffff810112ee)
Location: include/linux/atomic/atomic-long.h:39
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_update
```
```
In arch/x86/events/intel/ds.c (ffffffff81012745)
Location: include/linux/atomic/atomic-long.h:39
Inline: True
```
```
In arch/x86/events/intel/pt.c (ffffffff8101a8ea)
Location: include/linux/atomic/atomic-long.h:39
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_buffer_reset_offsets
  - arch/x86/events/intel/pt.c:pt_buffer_reset_offsets
  - arch/x86/events/intel/pt.c:pt_update_head
```
```
In arch/x86/events/intel/uncore.c (ffffffff8101ceaf)
Location: include/linux/atomic/atomic-long.h:39
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff810aaeba)
Location: include/linux/atomic/atomic-long.h:39
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:param_set_local64
```
```
In kernel/fork.c (ffffffff810b1f47)
Location: include/linux/atomic/atomic-long.h:39
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
  - kernel/fork.c:mm_init
```
```
In kernel/workqueue.c (ffffffff810da120)
Location: include/linux/atomic/atomic-long.h:39
Inline: True
Inline callers:
  - kernel/workqueue.c:cancel_delayed_work
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:insert_work
  - kernel/workqueue.c:try_to_grab_pending
```
```
In kernel/locking/mutex.c (ffffffff8112c8c5)
Location: include/linux/atomic/atomic-long.h:39
Inline: True
Inline callers:
  - kernel/locking/mutex.c:__mutex_init
```
```
In kernel/locking/rwsem.c (ffffffff8112d075)
Location: include/linux/atomic/atomic-long.h:39
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
In kernel/printk/printk_ringbuffer.c (ffffffff8113d9f1)
Location: include/linux/atomic/atomic-long.h:39
Inline: True
Inline callers:
  - kernel/printk/printk_ringbuffer.c:prb_init
  - kernel/printk/printk_ringbuffer.c:prb_init
  - kernel/printk/printk_ringbuffer.c:prb_init
  - kernel/printk/printk_ringbuffer.c:prb_init
  - kernel/printk/printk_ringbuffer.c:prb_init
  - kernel/printk/printk_ringbuffer.c:prb_init
  - kernel/printk/printk_ringbuffer.c:desc_read
```
```
In kernel/time/namespace.c (ffffffff8117c06a)
Location: include/linux/atomic/atomic-long.h:39
Inline: True
Inline callers:
  - kernel/time/namespace.c:copy_time_ns
```
```
In kernel/acct.c (ffffffff8118ba4e)
Location: include/linux/atomic/atomic-long.h:39
Inline: True
Inline callers:
  - kernel/acct.c:acct_on
```
```
In kernel/cgroup/namespace.c (ffffffff8119e503)
Location: include/linux/atomic/atomic-long.h:39
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
```
```
In kernel/cgroup/misc.c (ffffffff811a9044)
Location: include/linux/atomic/atomic-long.h:39
Inline: True
Inline callers:
  - kernel/cgroup/misc.c:misc_cg_alloc
```
```
In kernel/utsname.c (ffffffff811a9334)
Location: include/linux/atomic/atomic-long.h:39
Inline: True
Inline callers:
  - kernel/utsname.c:copy_utsname
```
```
In kernel/user_namespace.c (ffffffff811aa95d)
Location: include/linux/atomic/atomic-long.h:39
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In kernel/pid_namespace.c (ffffffff811ab351)
Location: include/linux/atomic/atomic-long.h:39
Inline: True
Inline callers:
  - kernel/pid_namespace.c:create_pid_namespace
```
```
In kernel/audit_tree.c (ffffffff811b99e5)
Location: include/linux/atomic/atomic-long.h:39
Inline: True
Inline callers:
  - kernel/audit_tree.c:alloc_chunk
```
```
In kernel/trace/ring_buffer.c (ffffffff811e145f)
Location: include/linux/atomic/atomic-long.h:39
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:reset_disabled_cpu_buffer
  - kernel/trace/ring_buffer.c:reset_disabled_cpu_buffer
  - kernel/trace/ring_buffer.c:reset_disabled_cpu_buffer
  - kernel/trace/ring_buffer.c:reset_disabled_cpu_buffer
  - kernel/trace/ring_buffer.c:reset_disabled_cpu_buffer
  - kernel/trace/ring_buffer.c:reset_disabled_cpu_buffer
  - kernel/trace/ring_buffer.c:reset_disabled_cpu_buffer
  - kernel/trace/ring_buffer.c:reset_disabled_cpu_buffer
  - kernel/trace/ring_buffer.c:reset_disabled_cpu_buffer
  - kernel/trace/ring_buffer.c:reset_disabled_cpu_buffer
  - kernel/trace/ring_buffer.c:reset_disabled_cpu_buffer
  - kernel/trace/ring_buffer.c:reset_disabled_cpu_buffer
  - kernel/trace/ring_buffer.c:reset_disabled_cpu_buffer
  - kernel/trace/ring_buffer.c:reset_disabled_cpu_buffer
  - kernel/trace/ring_buffer.c:reset_disabled_cpu_buffer
  - kernel/trace/ring_buffer.c:reset_disabled_cpu_buffer
  - kernel/trace/ring_buffer.c:reset_disabled_cpu_buffer
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
  - kernel/trace/ring_buffer.c:__rb_reserve_next
  - kernel/trace/ring_buffer.c:__rb_reserve_next
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/events/core.c (ffffffff812836b3)
Location: include/linux/atomic/atomic-long.h:39
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
  - kernel/events/core.c:cpu_clock_event_start
  - kernel/events/core.c:cpu_clock_event_start
  - kernel/events/core.c:__perf_event_period
  - kernel/events/core.c:perf_event_pause
  - kernel/events/core.c:_perf_event_reset
  - kernel/events/core.c:perf_event_context_sched_out
```
```
In mm/vmstat.c (ffffffff812c3af3)
Location: include/linux/atomic/atomic-long.h:39
Inline: True
Inline callers:
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
```
```
In mm/vmalloc.c (ffffffff812ff113)
Location: include/linux/atomic/atomic-long.h:39
Inline: True
Inline callers:
  - mm/vmalloc.c:set_iounmap_nonlazy
```
```
In mm/page_alloc.c (ffffffff81d4ede4)
Location: include/linux/atomic/atomic-long.h:39
Inline: True
Inline callers:
  - mm/page_alloc.c:zone_init_internals
```
```
In mm/memblock.c (ffffffff832da54e)
Location: include/linux/atomic/atomic-long.h:39
Inline: True
Inline callers:
  - mm/memblock.c:reset_all_zones_managed_pages
```
```
In mm/swap_state.c (ffffffff81310bf8)
Location: include/linux/atomic/atomic-long.h:39
Inline: True
Inline callers:
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/slub.c (ffffffff8133a41a)
Location: include/linux/atomic/atomic-long.h:39
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
In mm/page_counter.c (ffffffff813505ff)
Location: include/linux/atomic/atomic-long.h:39
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_cancel
```
```
In mm/memcontrol.c (ffffffff81d4c4df)
Location: include/linux/atomic/atomic-long.h:39
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
In mm/hugetlb_cgroup.c (ffffffff8135d2db)
Location: include/linux/atomic/atomic-long.h:39
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
```
```
In fs/file_table.c (ffffffff813745bd)
Location: include/linux/atomic/atomic-long.h:39
Inline: True
Inline callers:
  - fs/file_table.c:__alloc_file
```
```
In fs/namespace.c (ffffffff8139b2cc)
Location: include/linux/atomic/atomic-long.h:39
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In fs/nsfs.c (ffffffff813b86c9)
Location: include/linux/atomic/atomic-long.h:39
Inline: True
Inline callers:
  - fs/nsfs.c:ns_prune_dentry
```
```
In ipc/namespace.c (ffffffff81511302)
Location: include/linux/atomic/atomic-long.h:39
Inline: True
Inline callers:
  - ipc/namespace.c:copy_ipcs
```
```
In block/blk-ioc.c (ffffffff815d20b6)
Location: include/linux/atomic/atomic-long.h:39
Inline: True
Inline callers:
  - block/blk-ioc.c:create_task_io_context
```
```
In block/blk-iocost.c (ffffffff815fddc1)
Location: include/linux/atomic/atomic-long.h:39
Inline: True
Inline callers:
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-iocost.c:blk_iocost_init
```
```
In lib/percpu-refcount.c (ffffffff8161b16e)
Location: include/linux/atomic/atomic-long.h:39
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_init
```
```
In lib/genalloc.c (ffffffff81629e33)
Location: include/linux/atomic/atomic-long.h:39
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_add_owner
```
```
In drivers/tty/tty_ldsem.c (ffffffff817c0ae5)
Location: include/linux/atomic/atomic-long.h:39
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:__init_ldsem
```
```
In net/core/net_namespace.c (ffffffff81a8dd85)
Location: include/linux/atomic/atomic-long.h:39
Inline: True
Inline callers:
  - net/core/net_namespace.c:net_ns_net_init
```
```
In net/core/page_pool.c (ffffffff81ad94e8)
Location: include/linux/atomic/atomic-long.h:39
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_alloc_frag
```
```
In net/ipv4/nexthop.c (ffffffff81bb45ce)
Location: include/linux/atomic/atomic-long.h:39
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_res_grp_activity_update
  - net/ipv4/nexthop.c:nh_res_table_upkeep
  - net/ipv4/nexthop.c:nh_res_table_upkeep
```
```
In net/unix/af_unix.c (ffffffff81be6428)
Location: include/linux/atomic/atomic-long.h:39
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
```
```
In net/packet/af_packet.c (ffffffff81c55848)
Location: include/linux/atomic/atomic-long.h:39
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
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81008338)
Location: include/linux/atomic/atomic-long.h:39
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_setup_perfctr
```
```
In arch/x86/events/amd/ibs.c (ffffffff8100c8cb)
Location: include/linux/atomic/atomic-long.h:39
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
In arch/x86/events/msr.c (ffffffff8100d91c)
Location: include/linux/atomic/atomic-long.h:39
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_event_update
```
```
In arch/x86/events/intel/core.c (ffffffff810110e2)
Location: include/linux/atomic/atomic-long.h:39
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:handle_pmi_common
```
```
In arch/x86/events/intel/bts.c (ffffffff81012e2f)
Location: include/linux/atomic/atomic-long.h:39
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_buffer_reset
  - arch/x86/events/intel/bts.c:bts_update
```
```
In arch/x86/events/intel/ds.c (ffffffff8101433c)
Location: include/linux/atomic/atomic-long.h:39
Inline: True
```
```
In arch/x86/events/intel/pt.c (ffffffff8101ce1a)
Location: include/linux/atomic/atomic-long.h:39
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_buffer_reset_offsets
  - arch/x86/events/intel/pt.c:pt_buffer_reset_offsets
  - arch/x86/events/intel/pt.c:pt_update_head
```
```
In arch/x86/events/intel/uncore.c (ffffffff8101f6d3)
Location: include/linux/atomic/atomic-long.h:39
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff810c090a)
Location: include/linux/atomic/atomic-long.h:39
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:param_set_local64
```
```
In kernel/fork.c (ffffffff810c88a7)
Location: include/linux/atomic/atomic-long.h:39
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
  - kernel/fork.c:mm_init
```
```
In kernel/workqueue.c (ffffffff810f1898)
Location: include/linux/atomic/atomic-long.h:39
Inline: True
Inline callers:
  - kernel/workqueue.c:cancel_delayed_work
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:insert_work
  - kernel/workqueue.c:try_to_grab_pending
```
```
In kernel/locking/mutex.c (ffffffff8114d495)
Location: include/linux/atomic/atomic-long.h:39
Inline: True
Inline callers:
  - kernel/locking/mutex.c:__mutex_init
```
```
In kernel/locking/rwsem.c (ffffffff8114e384)
Location: include/linux/atomic/atomic-long.h:39
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
In kernel/printk/printk_ringbuffer.c (ffffffff81160dbd)
Location: include/linux/atomic/atomic-long.h:39
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
In kernel/time/namespace.c (ffffffff811b17b9)
Location: include/linux/atomic/atomic-long.h:39
Inline: True
Inline callers:
  - kernel/time/namespace.c:copy_time_ns
```
```
In kernel/acct.c (ffffffff811bae01)
Location: include/linux/atomic/atomic-long.h:39
Inline: True
Inline callers:
  - kernel/acct.c:acct_on
```
```
In kernel/cgroup/namespace.c (ffffffff811ce934)
Location: include/linux/atomic/atomic-long.h:39
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
```
```
In kernel/cgroup/misc.c (ffffffff811da2d4)
Location: include/linux/atomic/atomic-long.h:39
Inline: True
Inline callers:
  - kernel/cgroup/misc.c:misc_cg_alloc
```
```
In kernel/utsname.c (ffffffff811da47f)
Location: include/linux/atomic/atomic-long.h:39
Inline: True
Inline callers:
  - kernel/utsname.c:clone_uts_ns
```
```
In kernel/user_namespace.c (ffffffff811dbfc7)
Location: include/linux/atomic/atomic-long.h:39
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In kernel/pid_namespace.c (ffffffff811dcac2)
Location: include/linux/atomic/atomic-long.h:39
Inline: True
Inline callers:
  - kernel/pid_namespace.c:create_pid_namespace
```
```
In kernel/audit_tree.c (ffffffff811ecb05)
Location: include/linux/atomic/atomic-long.h:39
Inline: True
Inline callers:
  - kernel/audit_tree.c:alloc_chunk
```
```
In kernel/trace/ring_buffer.c (ffffffff8121811b)
Location: include/linux/atomic/atomic-long.h:39
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:reset_disabled_cpu_buffer
  - kernel/trace/ring_buffer.c:reset_disabled_cpu_buffer
  - kernel/trace/ring_buffer.c:reset_disabled_cpu_buffer
  - kernel/trace/ring_buffer.c:reset_disabled_cpu_buffer
  - kernel/trace/ring_buffer.c:reset_disabled_cpu_buffer
  - kernel/trace/ring_buffer.c:reset_disabled_cpu_buffer
  - kernel/trace/ring_buffer.c:reset_disabled_cpu_buffer
  - kernel/trace/ring_buffer.c:reset_disabled_cpu_buffer
  - kernel/trace/ring_buffer.c:reset_disabled_cpu_buffer
  - kernel/trace/ring_buffer.c:reset_disabled_cpu_buffer
  - kernel/trace/ring_buffer.c:reset_disabled_cpu_buffer
  - kernel/trace/ring_buffer.c:reset_disabled_cpu_buffer
  - kernel/trace/ring_buffer.c:reset_disabled_cpu_buffer
  - kernel/trace/ring_buffer.c:reset_disabled_cpu_buffer
  - kernel/trace/ring_buffer.c:reset_disabled_cpu_buffer
  - kernel/trace/ring_buffer.c:reset_disabled_cpu_buffer
  - kernel/trace/ring_buffer.c:reset_disabled_cpu_buffer
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
In kernel/events/core.c (ffffffff812d66c7)
Location: include/linux/atomic/atomic-long.h:39
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
  - kernel/events/core.c:cpu_clock_event_start
  - kernel/events/core.c:cpu_clock_event_start
  - kernel/events/core.c:perf_event_pause
  - kernel/events/core.c:_perf_event_reset
  - kernel/events/core.c:perf_event_context_sched_out
```
```
In mm/vmstat.c (ffffffff81320f23)
Location: include/linux/atomic/atomic-long.h:39
Inline: True
Inline callers:
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
```
```
In mm/page_alloc.c (ffffffff81f1ecb7)
Location: include/linux/atomic/atomic-long.h:39
Inline: True
Inline callers:
  - mm/page_alloc.c:zone_init_internals
```
```
In mm/memblock.c (ffffffff8348f638)
Location: include/linux/atomic/atomic-long.h:39
Inline: True
Inline callers:
  - mm/memblock.c:reset_all_zones_managed_pages
```
```
In mm/swap_state.c (ffffffff8137b9cd)
Location: include/linux/atomic/atomic-long.h:39
Inline: True
Inline callers:
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/slub.c (ffffffff813ac16a)
Location: include/linux/atomic/atomic-long.h:39
Inline: True
Inline callers:
  - mm/slub.c:slab_memory_callback
  - mm/slub.c:slab_memory_callback
  - mm/slub.c:init_kmem_cache_nodes
  - mm/slub.c:init_kmem_cache_nodes
  - mm/slub.c:init_kmem_cache_nodes
  - mm/slub.c:init_kmem_cache_nodes
```
```
In mm/page_counter.c (ffffffff813c88d5)
Location: include/linux/atomic/atomic-long.h:39
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_cancel
```
```
In mm/memcontrol.c (ffffffff81f1c01c)
Location: include/linux/atomic/atomic-long.h:39
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
In mm/hugetlb_cgroup.c (ffffffff813d715b)
Location: include/linux/atomic/atomic-long.h:39
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
```
```
In fs/file_table.c (ffffffff813f35ad)
Location: include/linux/atomic/atomic-long.h:39
Inline: True
Inline callers:
  - fs/file_table.c:__alloc_file
```
```
In fs/namespace.c (ffffffff8141eb33)
Location: include/linux/atomic/atomic-long.h:39
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In fs/nsfs.c (ffffffff8143df89)
Location: include/linux/atomic/atomic-long.h:39
Inline: True
Inline callers:
  - fs/nsfs.c:ns_prune_dentry
```
```
In ipc/namespace.c (ffffffff815a3135)
Location: include/linux/atomic/atomic-long.h:39
Inline: True
```
```
In block/blk-ioc.c (ffffffff8167d6e4)
Location: include/linux/atomic/atomic-long.h:39
Inline: True
Inline callers:
  - block/blk-ioc.c:alloc_io_context
```
```
In block/blk-iocost.c (ffffffff816ae4c5)
Location: include/linux/atomic/atomic-long.h:39
Inline: True
Inline callers:
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-iocost.c:blk_iocost_init
```
```
In lib/percpu-refcount.c (ffffffff816e891e)
Location: include/linux/atomic/atomic-long.h:39
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_init
```
```
In lib/genalloc.c (ffffffff816fb103)
Location: include/linux/atomic/atomic-long.h:39
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_add_owner
```
```
In drivers/tty/tty_ldsem.c (ffffffff818fd395)
Location: include/linux/atomic/atomic-long.h:39
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:__init_ldsem
```
```
In net/core/gen_stats.c (ffffffff81c029a5)
Location: include/linux/atomic/atomic-long.h:39
Inline: True
Inline callers:
  - net/core/gen_stats.c:gnet_stats_basic_sync_init
  - net/core/gen_stats.c:gnet_stats_basic_sync_init
```
```
In net/core/net_namespace.c (ffffffff81c03925)
Location: include/linux/atomic/atomic-long.h:39
Inline: True
Inline callers:
  - net/core/net_namespace.c:net_ns_net_init
```
```
In net/core/page_pool.c (ffffffff81c5a787)
Location: include/linux/atomic/atomic-long.h:39
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_alloc_frag
```
```
In net/ipv4/nexthop.c (ffffffff81d4807f)
Location: include/linux/atomic/atomic-long.h:39
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_res_grp_activity_update
  - net/ipv4/nexthop.c:nh_res_table_upkeep
  - net/ipv4/nexthop.c:nh_res_table_upkeep
```
```
In net/unix/af_unix.c (ffffffff81d7ee88)
Location: include/linux/atomic/atomic-long.h:39
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
```
```
In net/packet/af_packet.c (ffffffff81df1925)
Location: include/linux/atomic/atomic-long.h:39
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
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81007fae)
Location: include/linux/atomic/atomic-long.h:39
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_setup_perfctr
```
```
In arch/x86/events/amd/ibs.c (ffffffff8100f90c)
Location: include/linux/atomic/atomic-long.h:39
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
In arch/x86/events/msr.c (ffffffff81010b5c)
Location: include/linux/atomic/atomic-long.h:39
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_event_update
```
```
In arch/x86/events/intel/core.c (ffffffff810155d3)
Location: include/linux/atomic/atomic-long.h:39
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:handle_pmi_common
```
```
In arch/x86/events/intel/bts.c (ffffffff81016e5f)
Location: include/linux/atomic/atomic-long.h:39
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_buffer_reset
  - arch/x86/events/intel/bts.c:bts_update
```
```
In arch/x86/events/intel/ds.c (ffffffff810184fc)
Location: include/linux/atomic/atomic-long.h:39
Inline: True
```
```
In arch/x86/events/intel/pt.c (ffffffff810211ea)
Location: include/linux/atomic/atomic-long.h:39
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_buffer_reset_offsets
  - arch/x86/events/intel/pt.c:pt_buffer_reset_offsets
  - arch/x86/events/intel/pt.c:pt_update_head
```
```
In arch/x86/events/intel/uncore.c (ffffffff81023f03)
Location: include/linux/atomic/atomic-long.h:39
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff810dc87a)
Location: include/linux/atomic/atomic-long.h:39
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:param_set_local64
```
```
In kernel/fork.c (ffffffff810e5c24)
Location: include/linux/atomic/atomic-long.h:39
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
  - kernel/fork.c:mm_init
```
```
In kernel/workqueue.c (ffffffff8111485e)
Location: include/linux/atomic/atomic-long.h:39
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
In kernel/locking/mutex.c (ffffffff8117c575)
Location: include/linux/atomic/atomic-long.h:39
Inline: True
Inline callers:
  - kernel/locking/mutex.c:__mutex_init
```
```
In kernel/locking/rwsem.c (ffffffff8117d314)
Location: include/linux/atomic/atomic-long.h:39
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
In kernel/printk/printk_ringbuffer.c (ffffffff8119435d)
Location: include/linux/atomic/atomic-long.h:39
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
In kernel/time/namespace.c (ffffffff811f2509)
Location: include/linux/atomic/atomic-long.h:39
Inline: True
Inline callers:
  - kernel/time/namespace.c:copy_time_ns
```
```
In kernel/acct.c (ffffffff811fcbc1)
Location: include/linux/atomic/atomic-long.h:39
Inline: True
Inline callers:
  - kernel/acct.c:acct_on
```
```
In kernel/cgroup/namespace.c (ffffffff812121b4)
Location: include/linux/atomic/atomic-long.h:39
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
```
```
In kernel/cgroup/misc.c (ffffffff8121f864)
Location: include/linux/atomic/atomic-long.h:39
Inline: True
Inline callers:
  - kernel/cgroup/misc.c:misc_cg_alloc
```
```
In kernel/utsname.c (ffffffff8121fa3f)
Location: include/linux/atomic/atomic-long.h:39
Inline: True
Inline callers:
  - kernel/utsname.c:clone_uts_ns
```
```
In kernel/user_namespace.c (ffffffff81221827)
Location: include/linux/atomic/atomic-long.h:39
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In kernel/pid_namespace.c (ffffffff81222422)
Location: include/linux/atomic/atomic-long.h:39
Inline: True
Inline callers:
  - kernel/pid_namespace.c:create_pid_namespace
```
```
In kernel/audit_tree.c (ffffffff81233065)
Location: include/linux/atomic/atomic-long.h:39
Inline: True
Inline callers:
  - kernel/audit_tree.c:alloc_chunk
```
```
In kernel/trace/ring_buffer.c (ffffffff8126156b)
Location: include/linux/atomic/atomic-long.h:39
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:reset_disabled_cpu_buffer
  - kernel/trace/ring_buffer.c:reset_disabled_cpu_buffer
  - kernel/trace/ring_buffer.c:reset_disabled_cpu_buffer
  - kernel/trace/ring_buffer.c:reset_disabled_cpu_buffer
  - kernel/trace/ring_buffer.c:reset_disabled_cpu_buffer
  - kernel/trace/ring_buffer.c:reset_disabled_cpu_buffer
  - kernel/trace/ring_buffer.c:reset_disabled_cpu_buffer
  - kernel/trace/ring_buffer.c:reset_disabled_cpu_buffer
  - kernel/trace/ring_buffer.c:reset_disabled_cpu_buffer
  - kernel/trace/ring_buffer.c:reset_disabled_cpu_buffer
  - kernel/trace/ring_buffer.c:reset_disabled_cpu_buffer
  - kernel/trace/ring_buffer.c:reset_disabled_cpu_buffer
  - kernel/trace/ring_buffer.c:reset_disabled_cpu_buffer
  - kernel/trace/ring_buffer.c:reset_disabled_cpu_buffer
  - kernel/trace/ring_buffer.c:reset_disabled_cpu_buffer
  - kernel/trace/ring_buffer.c:reset_disabled_cpu_buffer
  - kernel/trace/ring_buffer.c:reset_disabled_cpu_buffer
  - kernel/trace/ring_buffer.c:reset_disabled_cpu_buffer
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
In kernel/events/core.c (ffffffff8133f4a7)
Location: include/linux/atomic/atomic-long.h:39
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
  - kernel/events/core.c:cpu_clock_event_start
  - kernel/events/core.c:cpu_clock_event_start
  - kernel/events/core.c:perf_event_pause
  - kernel/events/core.c:_perf_event_reset
  - kernel/events/core.c:perf_event_context_sched_out
```
```
In mm/vmscan.c (ffffffff813777ba)
Location: include/linux/atomic/atomic-long.h:39
Inline: True
```
```
In mm/vmstat.c (ffffffff81394e14)
Location: include/linux/atomic/atomic-long.h:39
Inline: True
Inline callers:
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
```
```
In mm/page_alloc.c (ffffffff83ebe3f5)
Location: include/linux/atomic/atomic-long.h:39
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init_core
  - mm/page_alloc.c:free_area_init_core_hotplug
```
```
In mm/memblock.c (ffffffff83ec1cea)
Location: include/linux/atomic/atomic-long.h:39
Inline: True
Inline callers:
  - mm/memblock.c:reset_all_zones_managed_pages
```
```
In mm/swap_state.c (ffffffff813f9342)
Location: include/linux/atomic/atomic-long.h:39
Inline: True
Inline callers:
  - mm/swap_state.c:swap_cache_get_folio
```
```
In mm/slub.c (ffffffff8142ab0a)
Location: include/linux/atomic/atomic-long.h:39
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
In mm/page_counter.c (ffffffff8144cfa5)
Location: include/linux/atomic/atomic-long.h:39
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_cancel
```
```
In mm/memcontrol.c (ffffffff820c3fcf)
Location: include/linux/atomic/atomic-long.h:39
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
In mm/hugetlb_cgroup.c (ffffffff8145cfb3)
Location: include/linux/atomic/atomic-long.h:39
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
```
```
In fs/file_table.c (ffffffff8147c35d)
Location: include/linux/atomic/atomic-long.h:39
Inline: True
Inline callers:
  - fs/file_table.c:__alloc_file
```
```
In fs/namespace.c (ffffffff814ab5a3)
Location: include/linux/atomic/atomic-long.h:39
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In fs/nsfs.c (ffffffff814cc979)
Location: include/linux/atomic/atomic-long.h:39
Inline: True
Inline callers:
  - fs/nsfs.c:ns_prune_dentry
```
```
In ipc/namespace.c (ffffffff8164cce5)
Location: include/linux/atomic/atomic-long.h:39
Inline: True
```
```
In block/blk-ioc.c (ffffffff8173a2c4)
Location: include/linux/atomic/atomic-long.h:39
Inline: True
Inline callers:
  - block/blk-ioc.c:alloc_io_context
```
```
In block/blk-iocost.c (ffffffff8176d1a4)
Location: include/linux/atomic/atomic-long.h:39
Inline: True
```
```
In lib/percpu-refcount.c (ffffffff817d893d)
Location: include/linux/atomic/atomic-long.h:39
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_init
```
```
In lib/genalloc.c (ffffffff817edc83)
Location: include/linux/atomic/atomic-long.h:39
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_add_owner
```
```
In drivers/tty/tty_ldsem.c (ffffffff81a56a55)
Location: include/linux/atomic/atomic-long.h:39
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:__init_ldsem
```
```
In net/core/gen_stats.c (ffffffff81db1e55)
Location: include/linux/atomic/atomic-long.h:39
Inline: True
Inline callers:
  - net/core/gen_stats.c:gnet_stats_basic_sync_init
  - net/core/gen_stats.c:gnet_stats_basic_sync_init
```
```
In net/core/net_namespace.c (ffffffff81db2f95)
Location: include/linux/atomic/atomic-long.h:39
Inline: True
Inline callers:
  - net/core/net_namespace.c:net_ns_net_init
```
```
In net/core/page_pool.c (ffffffff81e108e7)
Location: include/linux/atomic/atomic-long.h:39
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_alloc_frag
```
```
In net/ipv4/nexthop.c (ffffffff81f115cf)
Location: include/linux/atomic/atomic-long.h:39
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_res_grp_activity_update
  - net/ipv4/nexthop.c:nh_res_table_upkeep
  - net/ipv4/nexthop.c:nh_res_bucket_migrate
```
```
In net/unix/af_unix.c (ffffffff81f4c215)
Location: include/linux/atomic/atomic-long.h:39
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
```
```
In net/packet/af_packet.c (ffffffff81fc58f5)
Location: include/linux/atomic/atomic-long.h:39
Inline: True
Inline callers:
  - net/packet/af_packet.c:fanout_add
  - net/packet/af_packet.c:fanout_add
  - net/packet/af_packet.c:fanout_add
```
</details>
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
