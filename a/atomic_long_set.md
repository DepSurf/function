# Function: <code>atomic_long_set</code>

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
In arch/x86/events/core.c (ffffffff8100619e)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_setup_perfctr
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_perf_event_set_period
```
```
In arch/x86/events/amd/uncore.c (ffffffff81008284)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_read
```
```
In arch/x86/events/amd/ibs.c (ffffffff81008d3a)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_init
  - arch/x86/events/amd/ibs.c:perf_ibs_start
  - arch/x86/events/amd/ibs.c:perf_ibs_start
  - arch/x86/events/amd/ibs.c:perf_ibs_start
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
```
```
In arch/x86/events/msr.c (ffffffff81009cf5)
Location: include/asm-generic/atomic-long.h:56
Inline: True
```
```
In arch/x86/events/intel/core.c (ffffffff8100c2b8)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_save_and_restart
```
```
In arch/x86/events/intel/bts.c (ffffffff8100c9ca)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_update
```
```
In arch/x86/events/intel/cqm.c (ffffffff8100d882)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - arch/x86/events/intel/cqm.c:intel_cqm_event_count
  - arch/x86/events/intel/cqm.c:intel_cqm_xchg_rmid
```
```
In arch/x86/events/intel/cstate.c (ffffffff8100eed1)
Location: include/asm-generic/atomic-long.h:56
Inline: True
```
```
In arch/x86/events/intel/pt.c (ffffffff810134d0)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_buffer_reset_offsets
  - arch/x86/events/intel/pt.c:pt_buffer_reset_offsets
  - arch/x86/events/intel/pt.c:pt_update_head
```
```
In arch/x86/events/intel/rapl.c (ffffffff81014bc8)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - arch/x86/events/intel/rapl.c:__rapl_pmu_event_start
```
```
In arch/x86/events/intel/uncore.c (ffffffff81016718)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
```
```
In arch/x86/events/intel/uncore_snb.c (ffffffff81018f2e)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_event_start
```
```
In kernel/fork.c (ffffffff8107daa4)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
  - kernel/fork.c:mm_init
```
```
In kernel/workqueue.c (ffffffff81098015)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - kernel/workqueue.c:insert_work
  - kernel/workqueue.c:cancel_delayed_work
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/workqueue.c:__cancel_work_timer
```
```
In kernel/sched/fair.c (ffffffff810be826)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/fair.c:alloc_fair_sched_group
```
```
In kernel/acct.c (ffffffff8110bf5d)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - kernel/acct.c:SyS_acct
```
```
In kernel/cgroup.c (ffffffff81119ae9)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - kernel/cgroup.c:copy_cgroup_ns
```
```
In kernel/utsname.c (ffffffff8111dd38)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - kernel/utsname.c:copy_utsname
```
```
In kernel/user_namespace.c (ffffffff8111efa7)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In kernel/pid_namespace.c (ffffffff8111f9ec)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In kernel/audit_tree.c (ffffffff8112aee3)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - kernel/audit_tree.c:alloc_chunk
```
```
In kernel/trace/ring_buffer.c (ffffffff81146755)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:ring_buffer_alloc_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_reserve_next_event
  - kernel/trace/ring_buffer.c:rb_reserve_next_event
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
```
```
In kernel/events/core.c (ffffffff81179e57)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_period
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:__perf_event_task_sched_out
  - kernel/events/core.c:_perf_event_reset
  - kernel/events/core.c:task_clock_event_add
  - kernel/events/core.c:cpu_clock_event_add
  - kernel/events/core.c:perf_ioctl
```
```
In kernel/events/ring_buffer.c (ffffffff811858c7)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_aux_output_begin
  - kernel/events/ring_buffer.c:perf_aux_output_end
  - kernel/events/ring_buffer.c:perf_aux_output_end
```
```
In mm/slub.c (ffffffff811edbbd)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:slab_memory_callback
  - mm/slub.c:slab_memory_callback
```
```
In mm/memcontrol.c (ffffffff811fab7d)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
```
```
In mm/hugetlb_cgroup.c (ffffffff812011d9)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
```
```
In fs/file_table.c (ffffffff8120e136)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - fs/file_table.c:get_empty_filp
```
```
In fs/namespace.c (ffffffff8122b6de)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In fs/nsfs.c (ffffffff81242209)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - fs/nsfs.c:ns_prune_dentry
```
```
In ipc/namespace.c (ffffffff8132e9f5)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - ipc/namespace.c:copy_ipcs
```
```
In block/blk-ioc.c (ffffffff813bf0c6)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - block/blk-ioc.c:create_task_io_context
```
```
In lib/percpu-refcount.c (ffffffff813fef22)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_init
```
```
In net/core/net_namespace.c (ffffffff8170fd25)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - net/core/net_namespace.c:net_ns_net_init
```
```
In net/ipv4/tcp_memcontrol.c (ffffffff817ace5d)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - net/ipv4/tcp_memcontrol.c:tcp_init_cgroup
```
```
In net/unix/af_unix.c (ffffffff817bdffc)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
```
```
In net/packet/af_packet.c (ffffffff81806454)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
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
In arch/x86/events/core.c (ffffffff81006be6)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_setup_perfctr
```
```
In arch/x86/events/amd/uncore.c (ffffffff810084d4)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_read
```
```
In arch/x86/events/amd/ibs.c (ffffffff81009a58)
Location: include/asm-generic/atomic-long.h:56
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
In arch/x86/events/msr.c (ffffffff81009f6d)
Location: include/asm-generic/atomic-long.h:56
Inline: True
```
```
In arch/x86/events/intel/core.c (ffffffff8100c4f8)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_save_and_restart
```
```
In arch/x86/events/intel/bts.c (ffffffff8100cc2a)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_update
```
```
In arch/x86/events/intel/cqm.c (ffffffff8100deca)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - arch/x86/events/intel/cqm.c:intel_cqm_event_count
  - arch/x86/events/intel/cqm.c:intel_cqm_xchg_rmid
```
```
In arch/x86/events/intel/pt.c (ffffffff81012db0)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_buffer_reset_offsets
  - arch/x86/events/intel/pt.c:pt_buffer_reset_offsets
  - arch/x86/events/intel/pt.c:pt_update_head
```
```
In arch/x86/events/intel/uncore.c (ffffffff8101469f)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
```
```
In arch/x86/events/intel/uncore_snb.c (ffffffff81018279)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_event_start
```
```
In kernel/fork.c (ffffffff8107f6ca)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
  - kernel/fork.c:mm_init
```
```
In kernel/workqueue.c (ffffffff8109bf9c)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - kernel/workqueue.c:cancel_delayed_work
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:insert_work
```
```
In kernel/sched/fair.c (ffffffff810c248b)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/fair.c:alloc_fair_sched_group
```
```
In kernel/locking/rwsem-xadd.c (ffffffff810d04ca)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - kernel/locking/rwsem-xadd.c:__init_rwsem
```
```
In kernel/acct.c (ffffffff811137be)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - kernel/acct.c:SyS_acct
```
```
In kernel/cgroup.c (ffffffff811218fa)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - kernel/cgroup.c:copy_cgroup_ns
```
```
In kernel/utsname.c (ffffffff81125c06)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - kernel/utsname.c:copy_utsname
```
```
In kernel/user_namespace.c (ffffffff81126f07)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In kernel/pid_namespace.c (ffffffff811279ea)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In kernel/audit_tree.c (ffffffff811330f2)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - kernel/audit_tree.c:alloc_chunk
```
```
In kernel/trace/ring_buffer.c (ffffffff81152a47)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_alloc_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:rb_reserve_next_event
  - kernel/trace/ring_buffer.c:rb_reserve_next_event
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/events/core.c (ffffffff81190432)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:task_clock_event_add
  - kernel/events/core.c:cpu_clock_event_start
  - kernel/events/core.c:__perf_event_period
  - kernel/events/core.c:_perf_event_reset
  - kernel/events/core.c:__perf_event_task_sched_out
```
```
In kernel/events/ring_buffer.c (ffffffff81197f51)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_aux_output_end
  - kernel/events/ring_buffer.c:perf_aux_output_end
  - kernel/events/ring_buffer.c:perf_aux_output_begin
```
```
In mm/slub.c (ffffffff8120da5f)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - mm/slub.c:slab_memory_callback
  - mm/slub.c:slab_memory_callback
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:kmem_cache_open
```
```
In mm/memcontrol.c (ffffffff81894b46)
Location: include/asm-generic/atomic-long.h:56
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
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
```
```
In mm/hugetlb_cgroup.c (ffffffff81225993)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
```
```
In fs/file_table.c (ffffffff81234b66)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - fs/file_table.c:get_empty_filp
```
```
In fs/namespace.c (ffffffff81253e4e)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In fs/nsfs.c (ffffffff8126a569)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - fs/nsfs.c:ns_prune_dentry
```
```
In ipc/namespace.c (ffffffff81363688)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - ipc/namespace.c:copy_ipcs
```
```
In block/blk-ioc.c (ffffffff81403001)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - block/blk-ioc.c:create_task_io_context
```
```
In lib/percpu-refcount.c (ffffffff81446612)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_init
```
```
In net/core/net_namespace.c (ffffffff81777665)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - net/core/net_namespace.c:net_ns_net_init
```
```
In net/unix/af_unix.c (ffffffff8182af37)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
```
```
In net/packet/af_packet.c (ffffffff81876f16)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
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
In arch/x86/events/core.c (ffffffff81006be6)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_setup_perfctr
```
```
In arch/x86/events/amd/uncore.c (ffffffff810084f4)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_read
```
```
In arch/x86/events/amd/ibs.c (ffffffff81009a98)
Location: include/asm-generic/atomic-long.h:56
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
In arch/x86/events/msr.c (ffffffff81009fad)
Location: include/asm-generic/atomic-long.h:56
Inline: True
```
```
In arch/x86/events/intel/core.c (ffffffff8100c5b8)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_save_and_restart
```
```
In arch/x86/events/intel/bts.c (ffffffff8100ccfa)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_update
```
```
In arch/x86/events/intel/cqm.c (ffffffff8100df8a)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - arch/x86/events/intel/cqm.c:intel_cqm_event_count
  - arch/x86/events/intel/cqm.c:intel_cqm_xchg_rmid
```
```
In arch/x86/events/intel/pt.c (ffffffff81012ea0)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_buffer_reset_offsets
  - arch/x86/events/intel/pt.c:pt_buffer_reset_offsets
  - arch/x86/events/intel/pt.c:pt_update_head
```
```
In arch/x86/events/intel/uncore.c (ffffffff81014875)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
```
```
In arch/x86/events/intel/uncore_snb.c (ffffffff8101844c)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_event_start
```
```
In kernel/fork.c (ffffffff81083d78)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
  - kernel/fork.c:mm_init
```
```
In kernel/workqueue.c (ffffffff810a0fe0)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - kernel/workqueue.c:__cancel_work
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:insert_work
```
```
In kernel/sched/fair.c (ffffffff810c8530)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/fair.c:alloc_fair_sched_group
```
```
In kernel/locking/mutex.c (ffffffff810d502a)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - kernel/locking/mutex.c:__mutex_init
```
```
In kernel/locking/rwsem-xadd.c (ffffffff810d6eca)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - kernel/locking/rwsem-xadd.c:__init_rwsem
```
```
In kernel/acct.c (ffffffff8111aece)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - kernel/acct.c:SyS_acct
```
```
In kernel/cgroup.c (ffffffff81129ec4)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - kernel/cgroup.c:copy_cgroup_ns
```
```
In kernel/utsname.c (ffffffff8112f646)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - kernel/utsname.c:copy_utsname
```
```
In kernel/user_namespace.c (ffffffff81130a2c)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In kernel/pid_namespace.c (ffffffff811316a3)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In kernel/audit_tree.c (ffffffff8113ce32)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - kernel/audit_tree.c:alloc_chunk
```
```
In kernel/trace/ring_buffer.c (ffffffff8115ca7d)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_alloc_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/events/core.c (ffffffff8119f2f2)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:task_clock_event_add
  - kernel/events/core.c:cpu_clock_event_start
  - kernel/events/core.c:__perf_event_period
  - kernel/events/core.c:_perf_event_reset
  - kernel/events/core.c:__perf_event_task_sched_out
```
```
In kernel/events/ring_buffer.c (ffffffff811a7931)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_aux_output_end
  - kernel/events/ring_buffer.c:perf_aux_output_end
  - kernel/events/ring_buffer.c:perf_aux_output_begin
```
```
In mm/slub.c (ffffffff8121fa9f)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - mm/slub.c:slab_memory_callback
  - mm/slub.c:slab_memory_callback
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:kmem_cache_open
```
```
In mm/memcontrol.c (ffffffff818c9259)
Location: include/asm-generic/atomic-long.h:56
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
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
```
```
In mm/hugetlb_cgroup.c (ffffffff81237f73)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
```
```
In fs/file_table.c (ffffffff81247716)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - fs/file_table.c:get_empty_filp
```
```
In fs/namespace.c (ffffffff81267159)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In fs/nsfs.c (ffffffff8127d519)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - fs/nsfs.c:ns_prune_dentry
```
```
In ipc/namespace.c (ffffffff81379e90)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - ipc/namespace.c:copy_ipcs
```
```
In block/blk-ioc.c (ffffffff8141cd31)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - block/blk-ioc.c:create_task_io_context
```
```
In lib/percpu-refcount.c (ffffffff81464e02)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_init
```
```
In net/core/net_namespace.c (ffffffff817a46e5)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - net/core/net_namespace.c:net_ns_net_init
```
```
In net/unix/af_unix.c (ffffffff8185c967)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
```
```
In net/packet/af_packet.c (ffffffff818ac10c)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
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
In arch/x86/events/core.c (ffffffff81006950)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_perf_event_set_period
```
```
In arch/x86/events/amd/uncore.c (ffffffff810081a4)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_read
```
```
In arch/x86/events/amd/ibs.c (ffffffff810097d0)
Location: include/asm-generic/atomic-long.h:56
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
In arch/x86/events/msr.c (ffffffff8100a45d)
Location: include/asm-generic/atomic-long.h:56
Inline: True
```
```
In arch/x86/events/intel/core.c (ffffffff8100c2f8)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_save_and_restart
```
```
In arch/x86/events/intel/bts.c (ffffffff8100ccca)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_update
```
```
In arch/x86/events/intel/pt.c (ffffffff81011447)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_buffer_reset_offsets
  - arch/x86/events/intel/pt.c:pt_buffer_reset_offsets
  - arch/x86/events/intel/pt.c:pt_update_head
```
```
In arch/x86/events/intel/uncore.c (ffffffff81012e95)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
```
```
In arch/x86/events/intel/uncore_snb.c (ffffffff81016928)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_event_start
```
```
In kernel/fork.c (ffffffff81080ca8)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
  - kernel/fork.c:mm_init
```
```
In kernel/workqueue.c (ffffffff8109e549)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - kernel/workqueue.c:__cancel_work
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:insert_work
```
```
In kernel/sched/fair.c (ffffffff810c220f)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/fair.c:alloc_fair_sched_group
```
```
In kernel/locking/mutex.c (ffffffff810d416a)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - kernel/locking/mutex.c:__mutex_init
```
```
In kernel/locking/rwsem-xadd.c (ffffffff810d5f2a)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - kernel/locking/rwsem-xadd.c:__init_rwsem
```
```
In kernel/acct.c (ffffffff8111caee)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - kernel/acct.c:SyS_acct
```
```
In kernel/cgroup/namespace.c (ffffffff81128eda)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
```
```
In kernel/utsname.c (ffffffff81130bc4)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - kernel/utsname.c:copy_utsname
```
```
In kernel/user_namespace.c (ffffffff8113206d)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In kernel/pid_namespace.c (ffffffff81132ba2)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In kernel/audit_tree.c (ffffffff8113e4a9)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - kernel/audit_tree.c:alloc_chunk
```
```
In kernel/trace/ring_buffer.c (ffffffff8115face)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/events/core.c (ffffffff811a90e3)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - kernel/events/core.c:task_clock_event_add
  - kernel/events/core.c:cpu_clock_event_start
  - kernel/events/core.c:__perf_event_period
  - kernel/events/core.c:_perf_event_reset
  - kernel/events/core.c:__perf_event_task_sched_out
```
```
In kernel/events/ring_buffer.c (ffffffff811af0b9)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_aux_output_end
  - kernel/events/ring_buffer.c:perf_aux_output_end
  - kernel/events/ring_buffer.c:perf_aux_output_begin
```
```
In mm/slub.c (ffffffff8122b73f)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_create
  - mm/slub.c:__kmem_cache_create
  - mm/slub.c:__kmem_cache_create
  - mm/slub.c:__kmem_cache_create
  - mm/slub.c:slab_memory_callback
  - mm/slub.c:slab_memory_callback
```
```
In mm/memcontrol.c (ffffffff819007e7)
Location: include/asm-generic/atomic-long.h:56
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
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
```
```
In mm/hugetlb_cgroup.c (ffffffff81243bb9)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
```
```
In fs/file_table.c (ffffffff81252f1f)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - fs/file_table.c:get_empty_filp
```
```
In fs/namespace.c (ffffffff812749a9)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In fs/nsfs.c (ffffffff8128b0a9)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - fs/nsfs.c:ns_prune_dentry
```
```
In ipc/namespace.c (ffffffff8138da9c)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - ipc/namespace.c:copy_ipcs
```
```
In block/blk-ioc.c (ffffffff8142ad91)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - block/blk-ioc.c:create_task_io_context
```
```
In lib/percpu-refcount.c (ffffffff81469e42)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_init
```
```
In net/core/net_namespace.c (ffffffff817c2885)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - net/core/net_namespace.c:net_ns_net_init
```
```
In net/unix/af_unix.c (ffffffff818810f5)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
```
```
In net/packet/af_packet.c (ffffffff818d2202)
Location: include/asm-generic/atomic-long.h:56
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
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
In arch/x86/events/core.c (ffffffff81006d70)
Location: include/asm-generic/atomic-long.h:57
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_perf_event_set_period
```
```
In arch/x86/events/amd/uncore.c (ffffffff81008624)
Location: include/asm-generic/atomic-long.h:57
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_read
```
```
In arch/x86/events/amd/ibs.c (ffffffff81009f05)
Location: include/asm-generic/atomic-long.h:57
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
In arch/x86/events/msr.c (ffffffff8100a93d)
Location: include/asm-generic/atomic-long.h:57
Inline: True
```
```
In arch/x86/events/intel/core.c (ffffffff8100c898)
Location: include/asm-generic/atomic-long.h:57
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_save_and_restart
```
```
In arch/x86/events/intel/bts.c (ffffffff8100d26a)
Location: include/asm-generic/atomic-long.h:57
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_update
```
```
In arch/x86/events/intel/pt.c (ffffffff81011b87)
Location: include/asm-generic/atomic-long.h:57
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_buffer_reset_offsets
  - arch/x86/events/intel/pt.c:pt_buffer_reset_offsets
  - arch/x86/events/intel/pt.c:pt_update_head
```
```
In arch/x86/events/intel/uncore.c (ffffffff810136ab)
Location: include/asm-generic/atomic-long.h:57
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
```
```
In arch/x86/events/intel/uncore_snb.c (ffffffff810171ac)
Location: include/asm-generic/atomic-long.h:57
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_event_start
```
```
In kernel/fork.c (ffffffff81087618)
Location: include/asm-generic/atomic-long.h:57
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
```
```
In kernel/workqueue.c (ffffffff810a6be7)
Location: include/asm-generic/atomic-long.h:57
Inline: True
Inline callers:
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/workqueue.c:insert_work
  - kernel/workqueue.c:set_work_pool_and_clear_pending
```
```
In kernel/locking/mutex.c (ffffffff810dc0ba)
Location: include/asm-generic/atomic-long.h:57
Inline: True
Inline callers:
  - kernel/locking/mutex.c:__mutex_init
```
```
In kernel/locking/rwsem-xadd.c (ffffffff810ddeea)
Location: include/asm-generic/atomic-long.h:57
Inline: True
Inline callers:
  - kernel/locking/rwsem-xadd.c:__init_rwsem
```
```
In kernel/acct.c (ffffffff8112820e)
Location: include/asm-generic/atomic-long.h:57
Inline: True
Inline callers:
  - kernel/acct.c:SyS_acct
```
```
In kernel/cgroup/namespace.c (ffffffff81135b6e)
Location: include/asm-generic/atomic-long.h:57
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
```
```
In kernel/utsname.c (ffffffff8113db15)
Location: include/asm-generic/atomic-long.h:57
Inline: True
Inline callers:
  - kernel/utsname.c:copy_utsname
```
```
In kernel/user_namespace.c (ffffffff8113edec)
Location: include/asm-generic/atomic-long.h:57
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In kernel/pid_namespace.c (ffffffff8113f98f)
Location: include/asm-generic/atomic-long.h:57
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In kernel/audit_tree.c (ffffffff8114b2a9)
Location: include/asm-generic/atomic-long.h:57
Inline: True
Inline callers:
  - kernel/audit_tree.c:alloc_chunk
```
```
In kernel/trace/ring_buffer.c (ffffffff8116cb9e)
Location: include/asm-generic/atomic-long.h:57
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/events/core.c (ffffffff811bc923)
Location: include/asm-generic/atomic-long.h:57
Inline: True
Inline callers:
  - kernel/events/core.c:task_clock_event_add
  - kernel/events/core.c:cpu_clock_event_start
  - kernel/events/core.c:__perf_event_period
  - kernel/events/core.c:_perf_event_reset
  - kernel/events/core.c:__perf_event_task_sched_out
```
```
In kernel/events/ring_buffer.c (ffffffff811c2d09)
Location: include/asm-generic/atomic-long.h:57
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_aux_output_end
  - kernel/events/ring_buffer.c:perf_aux_output_begin
```
```
In mm/vmstat.c (ffffffff811f5520)
Location: include/asm-generic/atomic-long.h:57
Inline: True
Inline callers:
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
```
```
In mm/swap_state.c (ffffffff81225e53)
Location: include/asm-generic/atomic-long.h:57
Inline: True
Inline callers:
  - mm/swap_state.c:swap_readahead_detect
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/slub.c (ffffffff81246e41)
Location: include/asm-generic/atomic-long.h:57
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_create
  - mm/slub.c:__kmem_cache_create
  - mm/slub.c:__kmem_cache_create
  - mm/slub.c:__kmem_cache_create
  - mm/slub.c:slab_memory_callback
  - mm/slub.c:slab_memory_callback
```
```
In mm/memcontrol.c (ffffffff8198a7f4)
Location: include/asm-generic/atomic-long.h:57
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
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
```
```
In mm/hugetlb_cgroup.c (ffffffff81263a09)
Location: include/asm-generic/atomic-long.h:57
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
```
```
In fs/file_table.c (ffffffff8127501f)
Location: include/asm-generic/atomic-long.h:57
Inline: True
Inline callers:
  - fs/file_table.c:get_empty_filp
```
```
In fs/namespace.c (ffffffff812972d9)
Location: include/asm-generic/atomic-long.h:57
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In fs/nsfs.c (ffffffff812adbe9)
Location: include/asm-generic/atomic-long.h:57
Inline: True
Inline callers:
  - fs/nsfs.c:ns_prune_dentry
```
```
In ipc/namespace.c (ffffffff813b2ebb)
Location: include/asm-generic/atomic-long.h:57
Inline: True
Inline callers:
  - ipc/namespace.c:copy_ipcs
```
```
In block/blk-ioc.c (ffffffff81455f81)
Location: include/asm-generic/atomic-long.h:57
Inline: True
Inline callers:
  - block/blk-ioc.c:create_task_io_context
```
```
In lib/percpu-refcount.c (ffffffff81496112)
Location: include/asm-generic/atomic-long.h:57
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_init
```
```
In lib/genalloc.c (ffffffff814a0890)
Location: include/asm-generic/atomic-long.h:57
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_add_virt
```
```
In net/core/net_namespace.c (ffffffff8183c1c5)
Location: include/asm-generic/atomic-long.h:57
Inline: True
Inline callers:
  - net/core/net_namespace.c:net_ns_net_init
```
```
In net/unix/af_unix.c (ffffffff81902285)
Location: include/asm-generic/atomic-long.h:57
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
```
```
In net/packet/af_packet.c (ffffffff81956fd9)
Location: include/asm-generic/atomic-long.h:57
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
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
In arch/x86/events/core.c (ffffffff810074f5)
Location: include/asm-generic/atomic-long.h:59
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_setup_perfctr
```
```
In arch/x86/events/amd/uncore.c (ffffffff81008dd4)
Location: include/asm-generic/atomic-long.h:59
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_read
```
```
In arch/x86/events/amd/ibs.c (ffffffff8100a396)
Location: include/asm-generic/atomic-long.h:59
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
In arch/x86/events/msr.c (ffffffff8100b18c)
Location: include/asm-generic/atomic-long.h:59
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_event_update
```
```
In arch/x86/events/intel/core.c (ffffffff8100cff8)
Location: include/asm-generic/atomic-long.h:59
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_save_and_restart
```
```
In arch/x86/events/intel/bts.c (ffffffff8100d9da)
Location: include/asm-generic/atomic-long.h:59
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_update
```
```
In arch/x86/events/intel/ds.c (ffffffff8100e7c1)
Location: include/asm-generic/atomic-long.h:59
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pmu_save_and_restart_reload
```
```
In arch/x86/events/intel/pt.c (ffffffff81012579)
Location: include/asm-generic/atomic-long.h:59
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_buffer_reset_offsets
  - arch/x86/events/intel/pt.c:pt_buffer_reset_offsets
  - arch/x86/events/intel/pt.c:pt_update_head
```
```
In arch/x86/events/intel/uncore.c (ffffffff81014011)
Location: include/asm-generic/atomic-long.h:59
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
```
```
In kernel/fork.c (ffffffff8108ab37)
Location: include/asm-generic/atomic-long.h:59
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
```
```
In kernel/workqueue.c (ffffffff810ac5e1)
Location: include/asm-generic/atomic-long.h:59
Inline: True
Inline callers:
  - kernel/workqueue.c:cancel_delayed_work
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:insert_work
```
```
In kernel/locking/mutex.c (ffffffff810e46f5)
Location: include/asm-generic/atomic-long.h:59
Inline: True
Inline callers:
  - kernel/locking/mutex.c:__mutex_init
```
```
In kernel/locking/rwsem-xadd.c (ffffffff810e6555)
Location: include/asm-generic/atomic-long.h:59
Inline: True
Inline callers:
  - kernel/locking/rwsem-xadd.c:__init_rwsem
```
```
In kernel/acct.c (ffffffff81136011)
Location: include/asm-generic/atomic-long.h:59
Inline: True
Inline callers:
  - kernel/acct.c:acct_on
```
```
In kernel/cgroup/namespace.c (ffffffff8114446c)
Location: include/asm-generic/atomic-long.h:59
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
```
```
In kernel/utsname.c (ffffffff8114c4a9)
Location: include/asm-generic/atomic-long.h:59
Inline: True
Inline callers:
  - kernel/utsname.c:copy_utsname
```
```
In kernel/user_namespace.c (ffffffff8114d729)
Location: include/asm-generic/atomic-long.h:59
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In kernel/pid_namespace.c (ffffffff8114e2a6)
Location: include/asm-generic/atomic-long.h:59
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In kernel/audit_tree.c (ffffffff81159b16)
Location: include/asm-generic/atomic-long.h:59
Inline: True
Inline callers:
  - kernel/audit_tree.c:alloc_chunk
```
```
In kernel/trace/ring_buffer.c (ffffffff8117bb5d)
Location: include/asm-generic/atomic-long.h:59
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/events/core.c (ffffffff811d8cc6)
Location: include/asm-generic/atomic-long.h:59
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:task_clock_event_add
  - kernel/events/core.c:cpu_clock_event_start
  - kernel/events/core.c:__perf_event_period
  - kernel/events/core.c:_perf_event_reset
  - kernel/events/core.c:__perf_event_task_sched_out
```
```
In kernel/events/ring_buffer.c (ffffffff811e30a0)
Location: include/asm-generic/atomic-long.h:59
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_aux_output_end
  - kernel/events/ring_buffer.c:perf_aux_output_begin
```
```
In mm/vmstat.c (ffffffff81216826)
Location: include/asm-generic/atomic-long.h:59
Inline: True
Inline callers:
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
```
```
In mm/swap_state.c (ffffffff81248520)
Location: include/asm-generic/atomic-long.h:59
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/slub.c (ffffffff81269de2)
Location: include/asm-generic/atomic-long.h:59
Inline: True
Inline callers:
  - mm/slub.c:slab_memory_callback
  - mm/slub.c:slab_memory_callback
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:kmem_cache_open
```
```
In mm/memcontrol.c (ffffffff819e70ed)
Location: include/asm-generic/atomic-long.h:59
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
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
```
```
In mm/hugetlb_cgroup.c (ffffffff81287b4a)
Location: include/asm-generic/atomic-long.h:59
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
```
```
In fs/file_table.c (ffffffff8129b8db)
Location: include/asm-generic/atomic-long.h:59
Inline: True
Inline callers:
  - fs/file_table.c:get_empty_filp
```
```
In fs/namespace.c (ffffffff812bd4c5)
Location: include/asm-generic/atomic-long.h:59
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In fs/nsfs.c (ffffffff812d5999)
Location: include/asm-generic/atomic-long.h:59
Inline: True
Inline callers:
  - fs/nsfs.c:ns_prune_dentry
```
```
In ipc/namespace.c (ffffffff813e35e4)
Location: include/asm-generic/atomic-long.h:59
Inline: True
Inline callers:
  - ipc/namespace.c:copy_ipcs
```
```
In block/blk-ioc.c (ffffffff814893cb)
Location: include/asm-generic/atomic-long.h:59
Inline: True
Inline callers:
  - block/blk-ioc.c:create_task_io_context
```
```
In lib/percpu-refcount.c (ffffffff814cb392)
Location: include/asm-generic/atomic-long.h:59
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_init
```
```
In lib/genalloc.c (ffffffff814d5a24)
Location: include/asm-generic/atomic-long.h:59
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_add_virt
```
```
In net/core/net_namespace.c (ffffffff81886922)
Location: include/asm-generic/atomic-long.h:59
Inline: True
Inline callers:
  - net/core/net_namespace.c:net_ns_net_init
```
```
In net/ipv4/ip_fragment.c (ffffffff818e899c)
Location: include/asm-generic/atomic-long.h:59
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ipv4_frags_init_net
```
```
In net/unix/af_unix.c (ffffffff81959c2d)
Location: include/asm-generic/atomic-long.h:59
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
```
```
In net/ipv6/reassembly.c (ffffffff81990325)
Location: include/asm-generic/atomic-long.h:59
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frags_init_net
```
```
In net/packet/af_packet.c (ffffffff819b3abb)
Location: include/asm-generic/atomic-long.h:59
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
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
In arch/x86/events/core.c (ffffffff810073d5)
Location: include/asm-generic/atomic-long.h:59
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_setup_perfctr
```
```
In arch/x86/events/amd/uncore.c (ffffffff81008cf4)
Location: include/asm-generic/atomic-long.h:59
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_read
```
```
In arch/x86/events/amd/ibs.c (ffffffff8100a2c6)
Location: include/asm-generic/atomic-long.h:59
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
In arch/x86/events/msr.c (ffffffff8100b0ec)
Location: include/asm-generic/atomic-long.h:59
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_event_update
```
```
In arch/x86/events/intel/core.c (ffffffff8100d3c8)
Location: include/asm-generic/atomic-long.h:59
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_save_and_restart
```
```
In arch/x86/events/intel/bts.c (ffffffff8100deaa)
Location: include/asm-generic/atomic-long.h:59
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_update
```
```
In arch/x86/events/intel/ds.c (ffffffff8100ec91)
Location: include/asm-generic/atomic-long.h:59
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pmu_save_and_restart_reload
```
```
In arch/x86/events/intel/pt.c (ffffffff81012c79)
Location: include/asm-generic/atomic-long.h:59
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_buffer_reset_offsets
  - arch/x86/events/intel/pt.c:pt_buffer_reset_offsets
  - arch/x86/events/intel/pt.c:pt_update_head
```
```
In arch/x86/events/intel/uncore.c (ffffffff81014711)
Location: include/asm-generic/atomic-long.h:59
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
```
```
In kernel/fork.c (ffffffff81092b3b)
Location: include/asm-generic/atomic-long.h:59
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
```
```
In kernel/workqueue.c (ffffffff810b54c1)
Location: include/asm-generic/atomic-long.h:59
Inline: True
Inline callers:
  - kernel/workqueue.c:cancel_delayed_work
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:insert_work
```
```
In kernel/locking/mutex.c (ffffffff810efc75)
Location: include/asm-generic/atomic-long.h:59
Inline: True
Inline callers:
  - kernel/locking/mutex.c:__mutex_init
```
```
In kernel/locking/rwsem-xadd.c (ffffffff810f1ad5)
Location: include/asm-generic/atomic-long.h:59
Inline: True
Inline callers:
  - kernel/locking/rwsem-xadd.c:__init_rwsem
```
```
In kernel/acct.c (ffffffff811417a1)
Location: include/asm-generic/atomic-long.h:59
Inline: True
Inline callers:
  - kernel/acct.c:acct_on
```
```
In kernel/cgroup/namespace.c (ffffffff8114ff7c)
Location: include/asm-generic/atomic-long.h:59
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
```
```
In kernel/utsname.c (ffffffff811590c9)
Location: include/asm-generic/atomic-long.h:59
Inline: True
Inline callers:
  - kernel/utsname.c:copy_utsname
```
```
In kernel/user_namespace.c (ffffffff8115a3e9)
Location: include/asm-generic/atomic-long.h:59
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In kernel/pid_namespace.c (ffffffff8115af86)
Location: include/asm-generic/atomic-long.h:59
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In kernel/audit_tree.c (ffffffff81166aad)
Location: include/asm-generic/atomic-long.h:59
Inline: True
Inline callers:
  - kernel/audit_tree.c:alloc_chunk
```
```
In kernel/trace/ring_buffer.c (ffffffff81188b31)
Location: include/asm-generic/atomic-long.h:59
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/events/core.c (ffffffff811e91c3)
Location: include/asm-generic/atomic-long.h:59
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:task_clock_event_add
  - kernel/events/core.c:cpu_clock_event_stop
  - kernel/events/core.c:cpu_clock_event_start
  - kernel/events/core.c:__perf_event_period
  - kernel/events/core.c:_perf_event_reset
  - kernel/events/core.c:__perf_event_task_sched_out
```
```
In kernel/events/ring_buffer.c (ffffffff811f3511)
Location: include/asm-generic/atomic-long.h:59
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_aux_output_end
  - kernel/events/ring_buffer.c:perf_aux_output_begin
```
```
In mm/page_alloc.c (ffffffff828b944e)
Location: include/asm-generic/atomic-long.h:59
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init_node
  - mm/page_alloc.c:free_area_init_core_hotplug
```
```
In mm/vmstat.c (ffffffff81229729)
Location: include/asm-generic/atomic-long.h:59
Inline: True
Inline callers:
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
```
```
In mm/memblock.c (ffffffff828be4df)
Location: include/asm-generic/atomic-long.h:59
Inline: True
Inline callers:
  - mm/memblock.c:reset_all_zones_managed_pages
```
```
In mm/swap_state.c (ffffffff8125caf4)
Location: include/asm-generic/atomic-long.h:59
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/slub.c (ffffffff8127e6a2)
Location: include/asm-generic/atomic-long.h:59
Inline: True
Inline callers:
  - mm/slub.c:slab_memory_callback
  - mm/slub.c:slab_memory_callback
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:kmem_cache_open
```
```
In mm/memcontrol.c (ffffffff81a2255c)
Location: include/asm-generic/atomic-long.h:59
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
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
```
```
In mm/hugetlb_cgroup.c (ffffffff8129caa2)
Location: include/asm-generic/atomic-long.h:59
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
```
```
In fs/file_table.c (ffffffff812b07ed)
Location: include/asm-generic/atomic-long.h:59
Inline: True
Inline callers:
  - fs/file_table.c:__alloc_file
```
```
In fs/namespace.c (ffffffff812d27d5)
Location: include/asm-generic/atomic-long.h:59
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In fs/nsfs.c (ffffffff812ead69)
Location: include/asm-generic/atomic-long.h:59
Inline: True
Inline callers:
  - fs/nsfs.c:ns_prune_dentry
```
```
In ipc/namespace.c (ffffffff813fdf54)
Location: include/asm-generic/atomic-long.h:59
Inline: True
Inline callers:
  - ipc/namespace.c:copy_ipcs
```
```
In block/blk-ioc.c (ffffffff814a321b)
Location: include/asm-generic/atomic-long.h:59
Inline: True
Inline callers:
  - block/blk-ioc.c:create_task_io_context
```
```
In lib/percpu-refcount.c (ffffffff814e00c2)
Location: include/asm-generic/atomic-long.h:59
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_init
```
```
In lib/genalloc.c (ffffffff814ea0af)
Location: include/asm-generic/atomic-long.h:59
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_add_virt
```
```
In drivers/tty/tty_ldsem.c (ffffffff81637935)
Location: include/asm-generic/atomic-long.h:59
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:__init_ldsem
```
```
In net/core/net_namespace.c (ffffffff818a7012)
Location: include/asm-generic/atomic-long.h:59
Inline: True
Inline callers:
  - net/core/net_namespace.c:net_ns_net_init
```
```
In net/ipv4/ip_fragment.c (ffffffff81915cec)
Location: include/asm-generic/atomic-long.h:59
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ipv4_frags_init_net
```
```
In net/unix/af_unix.c (ffffffff8198e7ae)
Location: include/asm-generic/atomic-long.h:59
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
```
```
In net/ipv6/reassembly.c (ffffffff819c6b85)
Location: include/asm-generic/atomic-long.h:59
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frags_init_net
```
```
In net/packet/af_packet.c (ffffffff819eaae8)
Location: include/asm-generic/atomic-long.h:59
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
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
In arch/x86/events/core.c (ffffffff810076a3)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_setup_perfctr
```
```
In arch/x86/events/amd/uncore.c (ffffffff81009184)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_read
```
```
In arch/x86/events/amd/ibs.c (ffffffff8100a7b7)
Location: include/asm-generic/atomic-long.h:38
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
In arch/x86/events/msr.c (ffffffff8100b5bc)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_event_update
```
```
In arch/x86/events/intel/core.c (ffffffff8100dc5e)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_save_and_restart
```
```
In arch/x86/events/intel/bts.c (ffffffff8100e779)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_update
```
```
In arch/x86/events/intel/ds.c (ffffffff8100f589)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pmu_save_and_restart_reload
```
```
In arch/x86/events/intel/pt.c (ffffffff81014019)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_buffer_reset_offsets
  - arch/x86/events/intel/pt.c:pt_buffer_reset_offsets
  - arch/x86/events/intel/pt.c:pt_update_head
```
```
In arch/x86/events/intel/uncore.c (ffffffff81015b91)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
```
```
In kernel/fork.c (ffffffff81096b1d)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
```
```
In kernel/workqueue.c (ffffffff810bcfc0)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/workqueue.c:insert_work
  - kernel/workqueue.c:set_work_pool_and_clear_pending
```
```
In kernel/locking/mutex.c (ffffffff810f76d5)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - kernel/locking/mutex.c:__mutex_init
```
```
In kernel/locking/rwsem.c (ffffffff810f7db5)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:downgrade_write
  - kernel/locking/rwsem.c:up_write
  - kernel/locking/rwsem.c:down_write_trylock
  - kernel/locking/rwsem.c:down_write_killable
  - kernel/locking/rwsem.c:down_write
  - kernel/locking/rwsem.c:down_read_trylock
  - kernel/locking/rwsem.c:down_read_killable
  - kernel/locking/rwsem.c:down_read
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_mark_wake
  - kernel/locking/rwsem.c:__init_rwsem
  - kernel/locking/rwsem.c:__init_rwsem
```
```
In kernel/acct.c (ffffffff8114caee)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - kernel/acct.c:acct_on
```
```
In kernel/cgroup/namespace.c (ffffffff8115be7c)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
```
```
In kernel/utsname.c (ffffffff811657fe)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - kernel/utsname.c:copy_utsname
```
```
In kernel/user_namespace.c (ffffffff81166ab7)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In kernel/pid_namespace.c (ffffffff81167636)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In kernel/audit_tree.c (ffffffff81173a0d)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - kernel/audit_tree.c:alloc_chunk
```
```
In kernel/trace/ring_buffer.c (ffffffff8119629c)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/events/core.c (ffffffff812024d8)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:task_clock_event_add
  - kernel/events/core.c:cpu_clock_event_start
  - kernel/events/core.c:__perf_event_period
  - kernel/events/core.c:_perf_event_reset
  - kernel/events/core.c:__perf_event_task_sched_out
```
```
In mm/vmstat.c (ffffffff812393e3)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
```
```
In mm/vmalloc.c (ffffffff812686a3)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - mm/vmalloc.c:set_iounmap_nonlazy
```
```
In mm/page_alloc.c (ffffffff828d6545)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init_node
  - mm/page_alloc.c:free_area_init_core_hotplug
```
```
In mm/memblock.c (ffffffff828d76ad)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - mm/memblock.c:reset_all_zones_managed_pages
```
```
In mm/swap_state.c (ffffffff81277cda)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/slub.c (ffffffff8129a571)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - mm/slub.c:slab_memory_callback
  - mm/slub.c:slab_memory_callback
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:kmem_cache_open
```
```
In mm/memcontrol.c (ffffffff81a9258e)
Location: include/asm-generic/atomic-long.h:38
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
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
```
```
In mm/hugetlb_cgroup.c (ffffffff812b7c5a)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
```
```
In fs/file_table.c (ffffffff812cd131)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - fs/file_table.c:__alloc_file
```
```
In fs/super.c (ffffffff812ce3c3)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - fs/super.c:thaw_super_locked
  - fs/super.c:thaw_super_locked
  - fs/super.c:freeze_super
```
```
In fs/namespace.c (ffffffff812efa32)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In fs/nsfs.c (ffffffff813097d9)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - fs/nsfs.c:ns_prune_dentry
```
```
In fs/aio.c (0)
Location: include/asm-generic/atomic-long.h:38
Inline: True
```
```
In fs/io_uring.c (0)
Location: include/asm-generic/atomic-long.h:38
Inline: True
```
```
In ipc/namespace.c (ffffffff8142a584)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - ipc/namespace.c:copy_ipcs
```
```
In block/blk-ioc.c (ffffffff814d12d6)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - block/blk-ioc.c:create_task_io_context
```
```
In lib/percpu-refcount.c (ffffffff8150c01d)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_init
```
```
In lib/genalloc.c (ffffffff81516d6e)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_add_owner
```
```
In drivers/tty/tty_ldsem.c (ffffffff8166bc05)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:__init_ldsem
```
```
In net/core/net_namespace.c (ffffffff818f2712)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - net/core/net_namespace.c:net_ns_net_init
```
```
In net/unix/af_unix.c (ffffffff819f9f0b)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
```
```
In net/packet/af_packet.c (ffffffff81a59437)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
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
In arch/x86/events/core.c (ffffffff8100782d)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_setup_perfctr
```
```
In arch/x86/events/amd/uncore.c (ffffffff81009584)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_read
```
```
In arch/x86/events/amd/ibs.c (ffffffff8100ad86)
Location: include/asm-generic/atomic-long.h:38
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
In arch/x86/events/msr.c (ffffffff8100b9cc)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_event_update
```
```
In arch/x86/events/intel/core.c (ffffffff8100e29e)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_save_and_restart
```
```
In arch/x86/events/intel/bts.c (ffffffff8100ec49)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_update
```
```
In arch/x86/events/intel/ds.c (ffffffff8100fc51)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pmu_save_and_restart_reload
  - arch/x86/events/intel/ds.c:intel_pmu_save_and_restart_reload
```
```
In arch/x86/events/intel/pt.c (ffffffff81014ac0)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_buffer_reset_offsets
  - arch/x86/events/intel/pt.c:pt_buffer_reset_offsets
  - arch/x86/events/intel/pt.c:pt_update_head
```
```
In arch/x86/events/intel/uncore.c (ffffffff81016551)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff810991fa)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:param_set_local64
```
```
In kernel/fork.c (ffffffff8109d35d)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
```
```
In kernel/workqueue.c (ffffffff810c1541)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - kernel/workqueue.c:cancel_delayed_work
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:insert_work
```
```
In kernel/locking/mutex.c (ffffffff81103475)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - kernel/locking/mutex.c:__mutex_init
```
```
In kernel/locking/rwsem.c (ffffffff81103be5)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:downgrade_write
  - kernel/locking/rwsem.c:up_write
  - kernel/locking/rwsem.c:down_write_trylock
  - kernel/locking/rwsem.c:down_write_killable
  - kernel/locking/rwsem.c:down_write
  - kernel/locking/rwsem.c:down_read_trylock
  - kernel/locking/rwsem.c:down_read_killable
  - kernel/locking/rwsem.c:down_read
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_mark_wake
  - kernel/locking/rwsem.c:__init_rwsem
  - kernel/locking/rwsem.c:__init_rwsem
```
```
In kernel/acct.c (ffffffff811587be)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - kernel/acct.c:acct_on
```
```
In kernel/cgroup/namespace.c (ffffffff81167a9c)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
```
```
In kernel/utsname.c (ffffffff811716be)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - kernel/utsname.c:copy_utsname
```
```
In kernel/user_namespace.c (ffffffff81172977)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In kernel/pid_namespace.c (ffffffff811734f6)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In kernel/audit_tree.c (ffffffff8117f87d)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - kernel/audit_tree.c:alloc_chunk
```
```
In kernel/trace/ring_buffer.c (ffffffff811a1c6c)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/events/core.c (ffffffff8120f308)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:task_clock_event_add
  - kernel/events/core.c:cpu_clock_event_start
  - kernel/events/core.c:__perf_event_period
  - kernel/events/core.c:_perf_event_reset
  - kernel/events/core.c:__perf_event_task_sched_out
```
```
In mm/vmstat.c (ffffffff812476f3)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
```
```
In mm/vmalloc.c (ffffffff81276ff3)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - mm/vmalloc.c:set_iounmap_nonlazy
```
```
In mm/page_alloc.c (ffffffff828de9d4)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init_node
  - mm/page_alloc.c:free_area_init_core_hotplug
```
```
In mm/memblock.c (ffffffff828dfb1e)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - mm/memblock.c:reset_all_zones_managed_pages
```
```
In mm/swap_state.c (ffffffff812877ca)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/slub.c (ffffffff812aa431)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - mm/slub.c:slab_memory_callback
  - mm/slub.c:slab_memory_callback
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:kmem_cache_open
```
```
In mm/memcontrol.c (ffffffff81ac9d3e)
Location: include/asm-generic/atomic-long.h:38
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
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
```
```
In mm/hugetlb_cgroup.c (ffffffff812c9b3a)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
```
```
In fs/file_table.c (ffffffff812deb51)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - fs/file_table.c:__alloc_file
```
```
In fs/super.c (ffffffff812dfe73)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - fs/super.c:thaw_super_locked
  - fs/super.c:thaw_super_locked
  - fs/super.c:freeze_super
```
```
In fs/namespace.c (ffffffff81301502)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In fs/nsfs.c (ffffffff8131c849)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - fs/nsfs.c:ns_prune_dentry
```
```
In fs/aio.c (0)
Location: include/asm-generic/atomic-long.h:38
Inline: True
```
```
In fs/io_uring.c (0)
Location: include/asm-generic/atomic-long.h:38
Inline: True
```
```
In ipc/namespace.c (ffffffff814442b4)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - ipc/namespace.c:copy_ipcs
```
```
In block/blk-ioc.c (ffffffff814ea686)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - block/blk-ioc.c:create_task_io_context
```
```
In lib/percpu-refcount.c (ffffffff81529e6d)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_init
```
```
In lib/genalloc.c (ffffffff815377ae)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_add_owner
```
```
In drivers/tty/tty_ldsem.c (ffffffff8168e275)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:__init_ldsem
```
```
In net/core/net_namespace.c (ffffffff81924675)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - net/core/net_namespace.c:net_ns_net_init
```
```
In net/unix/af_unix.c (ffffffff81a30b8b)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
```
```
In net/packet/af_packet.c (ffffffff81a8f547)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
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
In arch/x86/events/core.c (ffffffff8100888e)
Location: include/asm-generic/atomic-long.h:39
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_setup_perfctr
```
```
In arch/x86/events/amd/uncore.c (ffffffff8100a734)
Location: include/asm-generic/atomic-long.h:39
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_read
```
```
In arch/x86/events/amd/ibs.c (ffffffff8100c000)
Location: include/asm-generic/atomic-long.h:39
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
In arch/x86/events/msr.c (ffffffff8100ccd9)
Location: include/asm-generic/atomic-long.h:39
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_event_update
```
```
In arch/x86/events/intel/core.c (ffffffff8100f5d0)
Location: include/asm-generic/atomic-long.h:39
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:handle_pmi_common
```
```
In arch/x86/events/intel/bts.c (ffffffff8100fff9)
Location: include/asm-generic/atomic-long.h:39
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_update
```
```
In arch/x86/events/intel/ds.c (ffffffff810112b1)
Location: include/asm-generic/atomic-long.h:39
Inline: True
```
```
In arch/x86/events/intel/pt.c (ffffffff81015f91)
Location: include/asm-generic/atomic-long.h:39
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_buffer_reset_offsets
  - arch/x86/events/intel/pt.c:pt_buffer_reset_offsets
  - arch/x86/events/intel/pt.c:pt_update_head
  - arch/x86/events/intel/pt.c:pt_update_head
```
```
In arch/x86/events/intel/uncore.c (ffffffff81018aa1)
Location: include/asm-generic/atomic-long.h:39
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff8109e88a)
Location: include/asm-generic/atomic-long.h:39
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:param_set_local64
```
```
In kernel/fork.c (ffffffff810a41bd)
Location: include/asm-generic/atomic-long.h:39
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
```
```
In kernel/workqueue.c (ffffffff810ca9a1)
Location: include/asm-generic/atomic-long.h:39
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
In kernel/locking/mutex.c (ffffffff8110e005)
Location: include/asm-generic/atomic-long.h:39
Inline: True
Inline callers:
  - kernel/locking/mutex.c:__mutex_init
```
```
In kernel/locking/rwsem.c (ffffffff8110e775)
Location: include/asm-generic/atomic-long.h:39
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:downgrade_write
  - kernel/locking/rwsem.c:up_write
  - kernel/locking/rwsem.c:down_write_trylock
  - kernel/locking/rwsem.c:down_write_killable
  - kernel/locking/rwsem.c:down_write
  - kernel/locking/rwsem.c:down_read_trylock
  - kernel/locking/rwsem.c:down_read_killable
  - kernel/locking/rwsem.c:down_read
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_mark_wake
  - kernel/locking/rwsem.c:__init_rwsem
  - kernel/locking/rwsem.c:__init_rwsem
```
```
In kernel/time/namespace.c (ffffffff81159c26)
Location: include/asm-generic/atomic-long.h:39
Inline: True
Inline callers:
  - kernel/time/namespace.c:clone_time_ns
```
```
In kernel/acct.c (ffffffff81168e2e)
Location: include/asm-generic/atomic-long.h:39
Inline: True
Inline callers:
  - kernel/acct.c:acct_on
```
```
In kernel/cgroup/namespace.c (ffffffff811793f7)
Location: include/asm-generic/atomic-long.h:39
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
```
```
In kernel/utsname.c (ffffffff811832eb)
Location: include/asm-generic/atomic-long.h:39
Inline: True
Inline callers:
  - kernel/utsname.c:clone_uts_ns
```
```
In kernel/user_namespace.c (ffffffff811847d7)
Location: include/asm-generic/atomic-long.h:39
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In kernel/pid_namespace.c (ffffffff81184fd8)
Location: include/asm-generic/atomic-long.h:39
Inline: True
Inline callers:
  - kernel/pid_namespace.c:create_pid_namespace
```
```
In kernel/audit_tree.c (ffffffff81192a61)
Location: include/asm-generic/atomic-long.h:39
Inline: True
Inline callers:
  - kernel/audit_tree.c:alloc_chunk
```
```
In kernel/trace/ring_buffer.c (ffffffff811b7d8b)
Location: include/asm-generic/atomic-long.h:39
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
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/events/core.c (ffffffff8123a4e5)
Location: include/asm-generic/atomic-long.h:39
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
In mm/vmstat.c (ffffffff812758d3)
Location: include/asm-generic/atomic-long.h:39
Inline: True
Inline callers:
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
```
```
In mm/vmalloc.c (ffffffff812abb63)
Location: include/asm-generic/atomic-long.h:39
Inline: True
Inline callers:
  - mm/vmalloc.c:set_iounmap_nonlazy
```
```
In mm/page_alloc.c (ffffffff82cfb900)
Location: include/asm-generic/atomic-long.h:39
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init_core
  - mm/page_alloc.c:free_area_init_core_hotplug
```
```
In mm/memblock.c (ffffffff82cfd0dc)
Location: include/asm-generic/atomic-long.h:39
Inline: True
Inline callers:
  - mm/memblock.c:reset_all_zones_managed_pages
```
```
In mm/swap_state.c (ffffffff812b89cf)
Location: include/asm-generic/atomic-long.h:39
Inline: True
Inline callers:
  - mm/swap_state.c:swap_ra_info
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/slub.c (ffffffff812df144)
Location: include/asm-generic/atomic-long.h:39
Inline: True
Inline callers:
  - mm/slub.c:slab_memory_callback
  - mm/slub.c:slab_memory_callback
  - mm/slub.c:init_kmem_cache_nodes
  - mm/slub.c:init_kmem_cache_nodes
  - mm/slub.c:early_kmem_cache_node_alloc
  - mm/slub.c:early_kmem_cache_node_alloc
```
```
In mm/memcontrol.c (ffffffff81bc22f5)
Location: include/asm-generic/atomic-long.h:39
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
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
```
```
In mm/hugetlb_cgroup.c (ffffffff812ff3ac)
Location: include/asm-generic/atomic-long.h:39
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
```
```
In fs/file_table.c (ffffffff813159a1)
Location: include/asm-generic/atomic-long.h:39
Inline: True
Inline callers:
  - fs/file_table.c:__alloc_file
```
```
In fs/namespace.c (ffffffff8133abcf)
Location: include/asm-generic/atomic-long.h:39
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In fs/nsfs.c (ffffffff81356599)
Location: include/asm-generic/atomic-long.h:39
Inline: True
Inline callers:
  - fs/nsfs.c:ns_prune_dentry
```
```
In ipc/namespace.c (ffffffff81494ee5)
Location: include/asm-generic/atomic-long.h:39
Inline: True
```
```
In block/blk-ioc.c (ffffffff81549626)
Location: include/asm-generic/atomic-long.h:39
Inline: True
Inline callers:
  - block/blk-ioc.c:create_task_io_context
```
```
In lib/percpu-refcount.c (ffffffff8158d760)
Location: include/asm-generic/atomic-long.h:39
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_init
```
```
In lib/genalloc.c (ffffffff8159b8ae)
Location: include/asm-generic/atomic-long.h:39
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_add_owner
```
```
In drivers/tty/tty_ldsem.c (ffffffff81740535)
Location: include/asm-generic/atomic-long.h:39
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:__init_ldsem
```
```
In net/core/net_namespace.c (ffffffff819f7eb5)
Location: include/asm-generic/atomic-long.h:39
Inline: True
Inline callers:
  - net/core/net_namespace.c:net_ns_net_init
```
```
In net/unix/af_unix.c (ffffffff81b24dbb)
Location: include/asm-generic/atomic-long.h:39
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
```
```
In net/packet/af_packet.c (ffffffff81b8a274)
Location: include/asm-generic/atomic-long.h:39
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
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81007910)
Location: include/asm-generic/atomic-long.h:39
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_setup_perfctr
```
```
In arch/x86/events/amd/uncore.c (ffffffff81009594)
Location: include/asm-generic/atomic-long.h:39
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_read
```
```
In arch/x86/events/amd/ibs.c (ffffffff8100afb5)
Location: include/asm-generic/atomic-long.h:39
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
In arch/x86/events/msr.c (ffffffff8100bc29)
Location: include/asm-generic/atomic-long.h:39
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_event_update
```
```
In arch/x86/events/intel/core.c (ffffffff8100ebf1)
Location: include/asm-generic/atomic-long.h:39
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:handle_pmi_common
```
```
In arch/x86/events/intel/bts.c (ffffffff8100f559)
Location: include/asm-generic/atomic-long.h:39
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_update
```
```
In arch/x86/events/intel/ds.c (ffffffff810108e1)
Location: include/asm-generic/atomic-long.h:39
Inline: True
```
```
In arch/x86/events/intel/pt.c (ffffffff81016431)
Location: include/asm-generic/atomic-long.h:39
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_buffer_reset_offsets
  - arch/x86/events/intel/pt.c:pt_buffer_reset_offsets
  - arch/x86/events/intel/pt.c:pt_update_head
  - arch/x86/events/intel/pt.c:pt_update_head
```
```
In arch/x86/events/intel/uncore.c (ffffffff81019221)
Location: include/asm-generic/atomic-long.h:39
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff8109a46a)
Location: include/asm-generic/atomic-long.h:39
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:param_set_local64
```
```
In kernel/fork.c (ffffffff8109fdd1)
Location: include/asm-generic/atomic-long.h:39
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
```
```
In kernel/workqueue.c (ffffffff810c5ad1)
Location: include/asm-generic/atomic-long.h:39
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
In kernel/locking/mutex.c (ffffffff8110b2c5)
Location: include/asm-generic/atomic-long.h:39
Inline: True
Inline callers:
  - kernel/locking/mutex.c:__mutex_init
```
```
In kernel/locking/rwsem.c (ffffffff8110b9f5)
Location: include/asm-generic/atomic-long.h:39
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
In kernel/printk/printk_ringbuffer.c (ffffffff8111d2fc)
Location: include/asm-generic/atomic-long.h:39
Inline: True
Inline callers:
  - kernel/printk/printk_ringbuffer.c:prb_init
  - kernel/printk/printk_ringbuffer.c:prb_init
  - kernel/printk/printk_ringbuffer.c:prb_init
  - kernel/printk/printk_ringbuffer.c:prb_init
  - kernel/printk/printk_ringbuffer.c:prb_init
  - kernel/printk/printk_ringbuffer.c:prb_init
  - kernel/printk/printk_ringbuffer.c:data_make_reusable
```
```
In kernel/time/namespace.c (ffffffff81155c3b)
Location: include/asm-generic/atomic-long.h:39
Inline: True
Inline callers:
  - kernel/time/namespace.c:clone_time_ns
```
```
In kernel/acct.c (ffffffff811654be)
Location: include/asm-generic/atomic-long.h:39
Inline: True
Inline callers:
  - kernel/acct.c:acct_on
```
```
In kernel/cgroup/namespace.c (ffffffff8117610b)
Location: include/asm-generic/atomic-long.h:39
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
```
```
In kernel/utsname.c (ffffffff811801df)
Location: include/asm-generic/atomic-long.h:39
Inline: True
Inline callers:
  - kernel/utsname.c:clone_uts_ns
```
```
In kernel/user_namespace.c (ffffffff81181827)
Location: include/asm-generic/atomic-long.h:39
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In kernel/pid_namespace.c (ffffffff81182147)
Location: include/asm-generic/atomic-long.h:39
Inline: True
Inline callers:
  - kernel/pid_namespace.c:create_pid_namespace
```
```
In kernel/audit_tree.c (ffffffff8118fbbc)
Location: include/asm-generic/atomic-long.h:39
Inline: True
Inline callers:
  - kernel/audit_tree.c:alloc_chunk
```
```
In kernel/trace/ring_buffer.c (ffffffff811b594b)
Location: include/asm-generic/atomic-long.h:39
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
In kernel/events/core.c (ffffffff8124390a)
Location: include/asm-generic/atomic-long.h:39
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
In mm/vmstat.c (ffffffff812801b3)
Location: include/asm-generic/atomic-long.h:39
Inline: True
Inline callers:
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
```
```
In mm/vmalloc.c (ffffffff812b7083)
Location: include/asm-generic/atomic-long.h:39
Inline: True
Inline callers:
  - mm/vmalloc.c:set_iounmap_nonlazy
```
```
In mm/page_alloc.c (ffffffff82fe83a7)
Location: include/asm-generic/atomic-long.h:39
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init_core
  - mm/page_alloc.c:free_area_init_core_hotplug
```
```
In mm/memblock.c (ffffffff82fe9b0d)
Location: include/asm-generic/atomic-long.h:39
Inline: True
Inline callers:
  - mm/memblock.c:reset_all_zones_managed_pages
```
```
In mm/swap_state.c (ffffffff812c4e6c)
Location: include/asm-generic/atomic-long.h:39
Inline: True
Inline callers:
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/slub.c (ffffffff812eaf16)
Location: include/asm-generic/atomic-long.h:39
Inline: True
Inline callers:
  - mm/slub.c:slab_memory_callback
  - mm/slub.c:slab_memory_callback
  - mm/slub.c:init_kmem_cache_nodes
  - mm/slub.c:init_kmem_cache_nodes
  - mm/slub.c:early_kmem_cache_node_alloc
  - mm/slub.c:early_kmem_cache_node_alloc
```
```
In mm/memcontrol.c (ffffffff81c3b42f)
Location: include/asm-generic/atomic-long.h:39
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
In mm/hugetlb_cgroup.c (ffffffff8130b6ec)
Location: include/asm-generic/atomic-long.h:39
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
```
```
In fs/file_table.c (ffffffff81320efd)
Location: include/asm-generic/atomic-long.h:39
Inline: True
Inline callers:
  - fs/file_table.c:__alloc_file
```
```
In fs/namespace.c (ffffffff81346dfc)
Location: include/asm-generic/atomic-long.h:39
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In fs/nsfs.c (ffffffff81362f39)
Location: include/asm-generic/atomic-long.h:39
Inline: True
Inline callers:
  - fs/nsfs.c:ns_prune_dentry
```
```
In ipc/namespace.c (ffffffff814b2875)
Location: include/asm-generic/atomic-long.h:39
Inline: True
```
```
In block/blk-ioc.c (ffffffff81565456)
Location: include/asm-generic/atomic-long.h:39
Inline: True
Inline callers:
  - block/blk-ioc.c:create_task_io_context
```
```
In block/blk-iocost.c (ffffffff8158f81d)
Location: include/asm-generic/atomic-long.h:39
Inline: True
Inline callers:
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-iocost.c:blk_iocost_init
```
```
In lib/percpu-refcount.c (ffffffff815aa297)
Location: include/asm-generic/atomic-long.h:39
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_init
```
```
In lib/genalloc.c (ffffffff815b714a)
Location: include/asm-generic/atomic-long.h:39
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_add_owner
```
```
In drivers/tty/tty_ldsem.c (ffffffff8175c465)
Location: include/asm-generic/atomic-long.h:39
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:__init_ldsem
```
```
In net/core/net_namespace.c (ffffffff819f7905)
Location: include/asm-generic/atomic-long.h:39
Inline: True
Inline callers:
  - net/core/net_namespace.c:net_ns_net_init
```
```
In net/unix/af_unix.c (ffffffff81b3394b)
Location: include/asm-generic/atomic-long.h:39
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
```
```
In net/packet/af_packet.c (ffffffff81b9a7c8)
Location: include/asm-generic/atomic-long.h:39
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
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff810080ee)
Location: include/asm-generic/atomic-long.h:39
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_setup_perfctr
```
```
In arch/x86/events/amd/uncore.c (ffffffff81009f64)
Location: include/asm-generic/atomic-long.h:39
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_read
```
```
In arch/x86/events/amd/ibs.c (ffffffff8100b95e)
Location: include/asm-generic/atomic-long.h:39
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
In arch/x86/events/msr.c (ffffffff8100c5b9)
Location: include/asm-generic/atomic-long.h:39
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_event_update
```
```
In arch/x86/events/intel/core.c (ffffffff8100efca)
Location: include/asm-generic/atomic-long.h:39
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:handle_pmi_common
```
```
In arch/x86/events/intel/bts.c (ffffffff810105ac)
Location: include/asm-generic/atomic-long.h:39
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_update
```
```
In arch/x86/events/intel/ds.c (ffffffff81011881)
Location: include/asm-generic/atomic-long.h:39
Inline: True
```
```
In arch/x86/events/intel/pt.c (ffffffff81017728)
Location: include/asm-generic/atomic-long.h:39
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_buffer_reset_offsets
  - arch/x86/events/intel/pt.c:pt_buffer_reset_offsets
  - arch/x86/events/intel/pt.c:pt_update_head
  - arch/x86/events/intel/pt.c:pt_update_head
```
```
In arch/x86/events/intel/uncore.c (ffffffff8101a541)
Location: include/asm-generic/atomic-long.h:39
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff8109ac2a)
Location: include/asm-generic/atomic-long.h:39
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:param_set_local64
```
```
In kernel/fork.c (ffffffff810a0ae4)
Location: include/asm-generic/atomic-long.h:39
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
```
```
In kernel/workqueue.c (ffffffff810c7400)
Location: include/asm-generic/atomic-long.h:39
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
In kernel/locking/mutex.c (ffffffff8110d155)
Location: include/asm-generic/atomic-long.h:39
Inline: True
Inline callers:
  - kernel/locking/mutex.c:__mutex_init
```
```
In kernel/locking/rwsem.c (ffffffff8110d815)
Location: include/asm-generic/atomic-long.h:39
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
In kernel/printk/printk_ringbuffer.c (ffffffff8111d67c)
Location: include/asm-generic/atomic-long.h:39
Inline: True
Inline callers:
  - kernel/printk/printk_ringbuffer.c:prb_init
  - kernel/printk/printk_ringbuffer.c:prb_init
  - kernel/printk/printk_ringbuffer.c:prb_init
  - kernel/printk/printk_ringbuffer.c:prb_init
  - kernel/printk/printk_ringbuffer.c:prb_init
  - kernel/printk/printk_ringbuffer.c:prb_init
```
```
In kernel/time/namespace.c (ffffffff8115721a)
Location: include/asm-generic/atomic-long.h:39
Inline: True
Inline callers:
  - kernel/time/namespace.c:copy_time_ns
```
```
In kernel/acct.c (ffffffff8116628e)
Location: include/asm-generic/atomic-long.h:39
Inline: True
Inline callers:
  - kernel/acct.c:acct_on
```
```
In kernel/cgroup/namespace.c (ffffffff81176c83)
Location: include/asm-generic/atomic-long.h:39
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
```
```
In kernel/cgroup/misc.c (ffffffff81181104)
Location: include/asm-generic/atomic-long.h:39
Inline: True
Inline callers:
  - kernel/cgroup/misc.c:misc_cg_alloc
```
```
In kernel/utsname.c (ffffffff811813c4)
Location: include/asm-generic/atomic-long.h:39
Inline: True
Inline callers:
  - kernel/utsname.c:copy_utsname
```
```
In kernel/user_namespace.c (ffffffff8118298d)
Location: include/asm-generic/atomic-long.h:39
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In kernel/pid_namespace.c (ffffffff81183297)
Location: include/asm-generic/atomic-long.h:39
Inline: True
Inline callers:
  - kernel/pid_namespace.c:create_pid_namespace
```
```
In kernel/audit_tree.c (ffffffff81190b05)
Location: include/asm-generic/atomic-long.h:39
Inline: True
Inline callers:
  - kernel/audit_tree.c:alloc_chunk
```
```
In kernel/trace/ring_buffer.c (ffffffff811b722d)
Location: include/asm-generic/atomic-long.h:39
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
In kernel/events/core.c (ffffffff812488b2)
Location: include/asm-generic/atomic-long.h:39
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
In mm/vmstat.c (ffffffff812852c3)
Location: include/asm-generic/atomic-long.h:39
Inline: True
Inline callers:
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
```
```
In mm/vmalloc.c (ffffffff812bc983)
Location: include/asm-generic/atomic-long.h:39
Inline: True
Inline callers:
  - mm/vmalloc.c:set_iounmap_nonlazy
```
```
In mm/page_alloc.c (ffffffff831f3120)
Location: include/asm-generic/atomic-long.h:39
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init_node
  - mm/page_alloc.c:free_area_init_core_hotplug
```
```
In mm/memblock.c (ffffffff831f41b6)
Location: include/asm-generic/atomic-long.h:39
Inline: True
Inline callers:
  - mm/memblock.c:reset_all_zones_managed_pages
```
```
In mm/swap_state.c (ffffffff812cbb09)
Location: include/asm-generic/atomic-long.h:39
Inline: True
Inline callers:
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/slub.c (ffffffff812f29d2)
Location: include/asm-generic/atomic-long.h:39
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
In mm/page_counter.c (ffffffff813067bb)
Location: include/asm-generic/atomic-long.h:39
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_cancel
```
```
In mm/memcontrol.c (ffffffff81c2dbef)
Location: include/asm-generic/atomic-long.h:39
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
In mm/hugetlb_cgroup.c (ffffffff81311d6c)
Location: include/asm-generic/atomic-long.h:39
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
```
```
In fs/file_table.c (ffffffff81326ffd)
Location: include/asm-generic/atomic-long.h:39
Inline: True
Inline callers:
  - fs/file_table.c:__alloc_file
```
```
In fs/namespace.c (ffffffff8134d2fc)
Location: include/asm-generic/atomic-long.h:39
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In fs/nsfs.c (ffffffff813699d9)
Location: include/asm-generic/atomic-long.h:39
Inline: True
Inline callers:
  - fs/nsfs.c:ns_prune_dentry
```
```
In ipc/namespace.c (ffffffff814b8ad2)
Location: include/asm-generic/atomic-long.h:39
Inline: True
Inline callers:
  - ipc/namespace.c:copy_ipcs
```
```
In block/blk-ioc.c (ffffffff8156dac6)
Location: include/asm-generic/atomic-long.h:39
Inline: True
Inline callers:
  - block/blk-ioc.c:create_task_io_context
```
```
In block/blk-iocost.c (ffffffff815967ae)
Location: include/asm-generic/atomic-long.h:39
Inline: True
Inline callers:
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-iocost.c:blk_iocost_init
```
```
In lib/percpu-refcount.c (ffffffff815b4e97)
Location: include/asm-generic/atomic-long.h:39
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_init
```
```
In lib/genalloc.c (ffffffff815c1fba)
Location: include/asm-generic/atomic-long.h:39
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_add_owner
```
```
In drivers/tty/tty_ldsem.c (ffffffff81740305)
Location: include/asm-generic/atomic-long.h:39
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:__init_ldsem
```
```
In net/core/net_namespace.c (ffffffff819dda85)
Location: include/asm-generic/atomic-long.h:39
Inline: True
Inline callers:
  - net/core/net_namespace.c:net_ns_net_init
```
```
In net/ipv4/nexthop.c (ffffffff81af3edb)
Location: include/asm-generic/atomic-long.h:39
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_res_grp_activity_update
  - net/ipv4/nexthop.c:nh_res_table_upkeep
  - net/ipv4/nexthop.c:nh_res_bucket_migrate
```
```
In net/unix/af_unix.c (ffffffff81b2134c)
Location: include/asm-generic/atomic-long.h:39
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
```
```
In net/packet/af_packet.c (ffffffff81b89738)
Location: include/asm-generic/atomic-long.h:39
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
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81008cc9)
Location: include/linux/atomic/atomic-instrumented.h:1195
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_setup_perfctr
```
```
In arch/x86/events/amd/ibs.c (ffffffff8100be6c)
Location: include/linux/atomic/atomic-instrumented.h:1195
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
Location: include/linux/atomic/atomic-instrumented.h:1195
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_event_update
```
```
In arch/x86/events/intel/core.c (ffffffff8100fb14)
Location: include/linux/atomic/atomic-instrumented.h:1195
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:handle_pmi_common
```
```
In arch/x86/events/intel/bts.c (ffffffff810112ee)
Location: include/linux/atomic/atomic-instrumented.h:1195
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_update
```
```
In arch/x86/events/intel/ds.c (ffffffff81012745)
Location: include/linux/atomic/atomic-instrumented.h:1195
Inline: True
```
```
In arch/x86/events/intel/pt.c (ffffffff8101a8ea)
Location: include/linux/atomic/atomic-instrumented.h:1195
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_buffer_reset_offsets
  - arch/x86/events/intel/pt.c:pt_buffer_reset_offsets
  - arch/x86/events/intel/pt.c:pt_update_head
```
```
In arch/x86/events/intel/uncore.c (ffffffff8101ceaf)
Location: include/linux/atomic/atomic-instrumented.h:1195
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff810aaeba)
Location: include/linux/atomic/atomic-instrumented.h:1195
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:param_set_local64
```
```
In kernel/fork.c (ffffffff810b1f47)
Location: include/linux/atomic/atomic-instrumented.h:1195
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
  - kernel/fork.c:mm_init
```
```
In kernel/workqueue.c (ffffffff810da120)
Location: include/linux/atomic/atomic-instrumented.h:1195
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
Location: include/linux/atomic/atomic-instrumented.h:1195
Inline: True
Inline callers:
  - kernel/locking/mutex.c:__mutex_init
```
```
In kernel/locking/rwsem.c (ffffffff8112d075)
Location: include/linux/atomic/atomic-instrumented.h:1195
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
Location: include/linux/atomic/atomic-instrumented.h:1195
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
Location: include/linux/atomic/atomic-instrumented.h:1195
Inline: True
Inline callers:
  - kernel/time/namespace.c:copy_time_ns
```
```
In kernel/acct.c (ffffffff8118ba4e)
Location: include/linux/atomic/atomic-instrumented.h:1195
Inline: True
Inline callers:
  - kernel/acct.c:acct_on
```
```
In kernel/cgroup/namespace.c (ffffffff8119e503)
Location: include/linux/atomic/atomic-instrumented.h:1195
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
```
```
In kernel/cgroup/misc.c (ffffffff811a9044)
Location: include/linux/atomic/atomic-instrumented.h:1195
Inline: True
Inline callers:
  - kernel/cgroup/misc.c:misc_cg_alloc
```
```
In kernel/utsname.c (ffffffff811a9334)
Location: include/linux/atomic/atomic-instrumented.h:1195
Inline: True
Inline callers:
  - kernel/utsname.c:copy_utsname
```
```
In kernel/user_namespace.c (ffffffff811aa95d)
Location: include/linux/atomic/atomic-instrumented.h:1195
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In kernel/pid_namespace.c (ffffffff811ab351)
Location: include/linux/atomic/atomic-instrumented.h:1195
Inline: True
Inline callers:
  - kernel/pid_namespace.c:create_pid_namespace
```
```
In kernel/audit_tree.c (ffffffff811b99e5)
Location: include/linux/atomic/atomic-instrumented.h:1195
Inline: True
Inline callers:
  - kernel/audit_tree.c:alloc_chunk
```
```
In kernel/trace/ring_buffer.c (ffffffff811e145f)
Location: include/linux/atomic/atomic-instrumented.h:1195
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
Location: include/linux/atomic/atomic-instrumented.h:1195
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
Location: include/linux/atomic/atomic-instrumented.h:1195
Inline: True
Inline callers:
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
```
```
In mm/vmalloc.c (ffffffff812ff113)
Location: include/linux/atomic/atomic-instrumented.h:1195
Inline: True
Inline callers:
  - mm/vmalloc.c:set_iounmap_nonlazy
```
```
In mm/page_alloc.c (ffffffff81d4ede4)
Location: include/linux/atomic/atomic-instrumented.h:1195
Inline: True
Inline callers:
  - mm/page_alloc.c:zone_init_internals
```
```
In mm/memblock.c (ffffffff832da54e)
Location: include/linux/atomic/atomic-instrumented.h:1195
Inline: True
Inline callers:
  - mm/memblock.c:reset_all_zones_managed_pages
```
```
In mm/swap_state.c (ffffffff81310bf8)
Location: include/linux/atomic/atomic-instrumented.h:1195
Inline: True
Inline callers:
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/slub.c (ffffffff8133a41a)
Location: include/linux/atomic/atomic-instrumented.h:1195
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
Location: include/linux/atomic/atomic-instrumented.h:1195
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_cancel
```
```
In mm/memcontrol.c (ffffffff81d4c4df)
Location: include/linux/atomic/atomic-instrumented.h:1195
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
Location: include/linux/atomic/atomic-instrumented.h:1195
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
```
```
In fs/file_table.c (ffffffff813745bd)
Location: include/linux/atomic/atomic-instrumented.h:1195
Inline: True
Inline callers:
  - fs/file_table.c:__alloc_file
```
```
In fs/namespace.c (ffffffff8139b2cc)
Location: include/linux/atomic/atomic-instrumented.h:1195
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In fs/nsfs.c (ffffffff813b86c9)
Location: include/linux/atomic/atomic-instrumented.h:1195
Inline: True
Inline callers:
  - fs/nsfs.c:ns_prune_dentry
```
```
In ipc/namespace.c (ffffffff81511302)
Location: include/linux/atomic/atomic-instrumented.h:1195
Inline: True
Inline callers:
  - ipc/namespace.c:copy_ipcs
```
```
In block/blk-ioc.c (ffffffff815d20b6)
Location: include/linux/atomic/atomic-instrumented.h:1195
Inline: True
Inline callers:
  - block/blk-ioc.c:create_task_io_context
```
```
In block/blk-iocost.c (ffffffff815fddc1)
Location: include/linux/atomic/atomic-instrumented.h:1195
Inline: True
Inline callers:
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-iocost.c:blk_iocost_init
```
```
In lib/percpu-refcount.c (ffffffff8161b16e)
Location: include/linux/atomic/atomic-instrumented.h:1195
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_init
```
```
In lib/genalloc.c (ffffffff81629e33)
Location: include/linux/atomic/atomic-instrumented.h:1195
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_add_owner
```
```
In drivers/tty/tty_ldsem.c (ffffffff817c0ae5)
Location: include/linux/atomic/atomic-instrumented.h:1195
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:__init_ldsem
```
```
In net/core/net_namespace.c (ffffffff81a8dd85)
Location: include/linux/atomic/atomic-instrumented.h:1195
Inline: True
Inline callers:
  - net/core/net_namespace.c:net_ns_net_init
```
```
In net/core/page_pool.c (ffffffff81ad94e8)
Location: include/linux/atomic/atomic-instrumented.h:1195
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_alloc_frag
```
```
In net/ipv4/nexthop.c (ffffffff81bb45ce)
Location: include/linux/atomic/atomic-instrumented.h:1195
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_res_grp_activity_update
  - net/ipv4/nexthop.c:nh_res_table_upkeep
  - net/ipv4/nexthop.c:nh_res_table_upkeep
```
```
In net/unix/af_unix.c (ffffffff81be6428)
Location: include/linux/atomic/atomic-instrumented.h:1195
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
```
```
In net/packet/af_packet.c (ffffffff81c55848)
Location: include/linux/atomic/atomic-instrumented.h:1195
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
Location: include/linux/atomic/atomic-instrumented.h:1277
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_setup_perfctr
```
```
In arch/x86/events/amd/ibs.c (ffffffff8100c8cb)
Location: include/linux/atomic/atomic-instrumented.h:1277
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
Location: include/linux/atomic/atomic-instrumented.h:1277
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_event_update
```
```
In arch/x86/events/intel/core.c (ffffffff810110e2)
Location: include/linux/atomic/atomic-instrumented.h:1277
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:handle_pmi_common
```
```
In arch/x86/events/intel/bts.c (ffffffff81012e2f)
Location: include/linux/atomic/atomic-instrumented.h:1277
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_buffer_reset
  - arch/x86/events/intel/bts.c:bts_update
```
```
In arch/x86/events/intel/ds.c (ffffffff8101433c)
Location: include/linux/atomic/atomic-instrumented.h:1277
Inline: True
```
```
In arch/x86/events/intel/pt.c (ffffffff8101ce1a)
Location: include/linux/atomic/atomic-instrumented.h:1277
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_buffer_reset_offsets
  - arch/x86/events/intel/pt.c:pt_buffer_reset_offsets
  - arch/x86/events/intel/pt.c:pt_update_head
```
```
In arch/x86/events/intel/uncore.c (ffffffff8101f6d3)
Location: include/linux/atomic/atomic-instrumented.h:1277
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff810c090a)
Location: include/linux/atomic/atomic-instrumented.h:1277
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:param_set_local64
```
```
In kernel/fork.c (ffffffff810c88a7)
Location: include/linux/atomic/atomic-instrumented.h:1277
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
  - kernel/fork.c:mm_init
```
```
In kernel/workqueue.c (ffffffff810f1898)
Location: include/linux/atomic/atomic-instrumented.h:1277
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
Location: include/linux/atomic/atomic-instrumented.h:1277
Inline: True
Inline callers:
  - kernel/locking/mutex.c:__mutex_init
```
```
In kernel/locking/rwsem.c (ffffffff8114e384)
Location: include/linux/atomic/atomic-instrumented.h:1277
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
Location: include/linux/atomic/atomic-instrumented.h:1277
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
Location: include/linux/atomic/atomic-instrumented.h:1277
Inline: True
Inline callers:
  - kernel/time/namespace.c:copy_time_ns
```
```
In kernel/acct.c (ffffffff811bae01)
Location: include/linux/atomic/atomic-instrumented.h:1277
Inline: True
Inline callers:
  - kernel/acct.c:acct_on
```
```
In kernel/cgroup/namespace.c (ffffffff811ce934)
Location: include/linux/atomic/atomic-instrumented.h:1277
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
```
```
In kernel/cgroup/misc.c (ffffffff811da2d4)
Location: include/linux/atomic/atomic-instrumented.h:1277
Inline: True
Inline callers:
  - kernel/cgroup/misc.c:misc_cg_alloc
```
```
In kernel/utsname.c (ffffffff811da47f)
Location: include/linux/atomic/atomic-instrumented.h:1277
Inline: True
Inline callers:
  - kernel/utsname.c:clone_uts_ns
```
```
In kernel/user_namespace.c (ffffffff811dbfc7)
Location: include/linux/atomic/atomic-instrumented.h:1277
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In kernel/pid_namespace.c (ffffffff811dcac2)
Location: include/linux/atomic/atomic-instrumented.h:1277
Inline: True
Inline callers:
  - kernel/pid_namespace.c:create_pid_namespace
```
```
In kernel/audit_tree.c (ffffffff811ecb05)
Location: include/linux/atomic/atomic-instrumented.h:1277
Inline: True
Inline callers:
  - kernel/audit_tree.c:alloc_chunk
```
```
In kernel/trace/ring_buffer.c (ffffffff8121811b)
Location: include/linux/atomic/atomic-instrumented.h:1277
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
Location: include/linux/atomic/atomic-instrumented.h:1277
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
Location: include/linux/atomic/atomic-instrumented.h:1277
Inline: True
Inline callers:
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
```
```
In mm/page_alloc.c (ffffffff81f1ecb7)
Location: include/linux/atomic/atomic-instrumented.h:1277
Inline: True
Inline callers:
  - mm/page_alloc.c:zone_init_internals
```
```
In mm/memblock.c (ffffffff8348f638)
Location: include/linux/atomic/atomic-instrumented.h:1277
Inline: True
Inline callers:
  - mm/memblock.c:reset_all_zones_managed_pages
```
```
In mm/swap_state.c (ffffffff8137b9cd)
Location: include/linux/atomic/atomic-instrumented.h:1277
Inline: True
Inline callers:
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/slub.c (ffffffff813ac16a)
Location: include/linux/atomic/atomic-instrumented.h:1277
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
Location: include/linux/atomic/atomic-instrumented.h:1277
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_cancel
```
```
In mm/memcontrol.c (ffffffff81f1c01c)
Location: include/linux/atomic/atomic-instrumented.h:1277
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
Location: include/linux/atomic/atomic-instrumented.h:1277
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
```
```
In fs/file_table.c (ffffffff813f35ad)
Location: include/linux/atomic/atomic-instrumented.h:1277
Inline: True
Inline callers:
  - fs/file_table.c:__alloc_file
```
```
In fs/namespace.c (ffffffff8141eb33)
Location: include/linux/atomic/atomic-instrumented.h:1277
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In fs/nsfs.c (ffffffff8143df89)
Location: include/linux/atomic/atomic-instrumented.h:1277
Inline: True
Inline callers:
  - fs/nsfs.c:ns_prune_dentry
```
```
In ipc/namespace.c (ffffffff815a3135)
Location: include/linux/atomic/atomic-instrumented.h:1277
Inline: True
```
```
In block/blk-ioc.c (ffffffff8167d6e4)
Location: include/linux/atomic/atomic-instrumented.h:1277
Inline: True
Inline callers:
  - block/blk-ioc.c:alloc_io_context
```
```
In block/blk-iocost.c (ffffffff816ae4c5)
Location: include/linux/atomic/atomic-instrumented.h:1277
Inline: True
Inline callers:
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-iocost.c:blk_iocost_init
```
```
In lib/percpu-refcount.c (ffffffff816e891e)
Location: include/linux/atomic/atomic-instrumented.h:1277
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_init
```
```
In lib/genalloc.c (ffffffff816fb103)
Location: include/linux/atomic/atomic-instrumented.h:1277
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_add_owner
```
```
In drivers/tty/tty_ldsem.c (ffffffff818fd395)
Location: include/linux/atomic/atomic-instrumented.h:1277
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:__init_ldsem
```
```
In net/core/gen_stats.c (ffffffff81c029a5)
Location: include/linux/atomic/atomic-instrumented.h:1277
Inline: True
Inline callers:
  - net/core/gen_stats.c:gnet_stats_basic_sync_init
  - net/core/gen_stats.c:gnet_stats_basic_sync_init
```
```
In net/core/net_namespace.c (ffffffff81c03925)
Location: include/linux/atomic/atomic-instrumented.h:1277
Inline: True
Inline callers:
  - net/core/net_namespace.c:net_ns_net_init
```
```
In net/core/page_pool.c (ffffffff81c5a787)
Location: include/linux/atomic/atomic-instrumented.h:1277
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_alloc_frag
```
```
In net/ipv4/nexthop.c (ffffffff81d4807f)
Location: include/linux/atomic/atomic-instrumented.h:1277
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_res_grp_activity_update
  - net/ipv4/nexthop.c:nh_res_table_upkeep
  - net/ipv4/nexthop.c:nh_res_table_upkeep
```
```
In net/unix/af_unix.c (ffffffff81d7ee88)
Location: include/linux/atomic/atomic-instrumented.h:1277
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
```
```
In net/packet/af_packet.c (ffffffff81df1925)
Location: include/linux/atomic/atomic-instrumented.h:1277
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
Location: include/linux/atomic/atomic-instrumented.h:1277
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_setup_perfctr
```
```
In arch/x86/events/amd/ibs.c (ffffffff8100f90c)
Location: include/linux/atomic/atomic-instrumented.h:1277
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
Location: include/linux/atomic/atomic-instrumented.h:1277
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_event_update
```
```
In arch/x86/events/intel/core.c (ffffffff810155d3)
Location: include/linux/atomic/atomic-instrumented.h:1277
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:handle_pmi_common
```
```
In arch/x86/events/intel/bts.c (ffffffff81016e5f)
Location: include/linux/atomic/atomic-instrumented.h:1277
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_buffer_reset
  - arch/x86/events/intel/bts.c:bts_update
```
```
In arch/x86/events/intel/ds.c (ffffffff810184fc)
Location: include/linux/atomic/atomic-instrumented.h:1277
Inline: True
```
```
In arch/x86/events/intel/pt.c (ffffffff810211ea)
Location: include/linux/atomic/atomic-instrumented.h:1277
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_buffer_reset_offsets
  - arch/x86/events/intel/pt.c:pt_buffer_reset_offsets
  - arch/x86/events/intel/pt.c:pt_update_head
```
```
In arch/x86/events/intel/uncore.c (ffffffff81023f03)
Location: include/linux/atomic/atomic-instrumented.h:1277
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff810dc87a)
Location: include/linux/atomic/atomic-instrumented.h:1277
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:param_set_local64
```
```
In kernel/fork.c (ffffffff810e5c24)
Location: include/linux/atomic/atomic-instrumented.h:1277
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
  - kernel/fork.c:mm_init
```
```
In kernel/workqueue.c (ffffffff8111485e)
Location: include/linux/atomic/atomic-instrumented.h:1277
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
Location: include/linux/atomic/atomic-instrumented.h:1277
Inline: True
Inline callers:
  - kernel/locking/mutex.c:__mutex_init
```
```
In kernel/locking/rwsem.c (ffffffff8117d314)
Location: include/linux/atomic/atomic-instrumented.h:1277
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
Location: include/linux/atomic/atomic-instrumented.h:1277
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
Location: include/linux/atomic/atomic-instrumented.h:1277
Inline: True
Inline callers:
  - kernel/time/namespace.c:copy_time_ns
```
```
In kernel/acct.c (ffffffff811fcbc1)
Location: include/linux/atomic/atomic-instrumented.h:1277
Inline: True
Inline callers:
  - kernel/acct.c:acct_on
```
```
In kernel/cgroup/namespace.c (ffffffff812121b4)
Location: include/linux/atomic/atomic-instrumented.h:1277
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
```
```
In kernel/cgroup/misc.c (ffffffff8121f864)
Location: include/linux/atomic/atomic-instrumented.h:1277
Inline: True
Inline callers:
  - kernel/cgroup/misc.c:misc_cg_alloc
```
```
In kernel/utsname.c (ffffffff8121fa3f)
Location: include/linux/atomic/atomic-instrumented.h:1277
Inline: True
Inline callers:
  - kernel/utsname.c:clone_uts_ns
```
```
In kernel/user_namespace.c (ffffffff81221827)
Location: include/linux/atomic/atomic-instrumented.h:1277
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In kernel/pid_namespace.c (ffffffff81222422)
Location: include/linux/atomic/atomic-instrumented.h:1277
Inline: True
Inline callers:
  - kernel/pid_namespace.c:create_pid_namespace
```
```
In kernel/audit_tree.c (ffffffff81233065)
Location: include/linux/atomic/atomic-instrumented.h:1277
Inline: True
Inline callers:
  - kernel/audit_tree.c:alloc_chunk
```
```
In kernel/trace/ring_buffer.c (ffffffff8126156b)
Location: include/linux/atomic/atomic-instrumented.h:1277
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
Location: include/linux/atomic/atomic-instrumented.h:1277
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
Location: include/linux/atomic/atomic-instrumented.h:1277
Inline: True
```
```
In mm/vmstat.c (ffffffff81394e14)
Location: include/linux/atomic/atomic-instrumented.h:1277
Inline: True
Inline callers:
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
```
```
In mm/page_alloc.c (ffffffff83ebe3f5)
Location: include/linux/atomic/atomic-instrumented.h:1277
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init_core
  - mm/page_alloc.c:free_area_init_core_hotplug
```
```
In mm/memblock.c (ffffffff83ec1cea)
Location: include/linux/atomic/atomic-instrumented.h:1277
Inline: True
Inline callers:
  - mm/memblock.c:reset_all_zones_managed_pages
```
```
In mm/swap_state.c (ffffffff813f9342)
Location: include/linux/atomic/atomic-instrumented.h:1277
Inline: True
Inline callers:
  - mm/swap_state.c:swap_cache_get_folio
```
```
In mm/slub.c (ffffffff8142ab0a)
Location: include/linux/atomic/atomic-instrumented.h:1277
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
Location: include/linux/atomic/atomic-instrumented.h:1277
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_cancel
```
```
In mm/memcontrol.c (ffffffff820c3fcf)
Location: include/linux/atomic/atomic-instrumented.h:1277
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
Location: include/linux/atomic/atomic-instrumented.h:1277
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
```
```
In fs/file_table.c (ffffffff8147c35d)
Location: include/linux/atomic/atomic-instrumented.h:1277
Inline: True
Inline callers:
  - fs/file_table.c:__alloc_file
```
```
In fs/namespace.c (ffffffff814ab5a3)
Location: include/linux/atomic/atomic-instrumented.h:1277
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In fs/nsfs.c (ffffffff814cc979)
Location: include/linux/atomic/atomic-instrumented.h:1277
Inline: True
Inline callers:
  - fs/nsfs.c:ns_prune_dentry
```
```
In ipc/namespace.c (ffffffff8164cce5)
Location: include/linux/atomic/atomic-instrumented.h:1277
Inline: True
```
```
In block/blk-ioc.c (ffffffff8173a2c4)
Location: include/linux/atomic/atomic-instrumented.h:1277
Inline: True
Inline callers:
  - block/blk-ioc.c:alloc_io_context
```
```
In block/blk-iocost.c (ffffffff8176d1a4)
Location: include/linux/atomic/atomic-instrumented.h:1277
Inline: True
```
```
In lib/percpu-refcount.c (ffffffff817d893d)
Location: include/linux/atomic/atomic-instrumented.h:1277
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_init
```
```
In lib/genalloc.c (ffffffff817edc83)
Location: include/linux/atomic/atomic-instrumented.h:1277
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_add_owner
```
```
In drivers/tty/tty_ldsem.c (ffffffff81a56a55)
Location: include/linux/atomic/atomic-instrumented.h:1277
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:__init_ldsem
```
```
In net/core/gen_stats.c (ffffffff81db1e55)
Location: include/linux/atomic/atomic-instrumented.h:1277
Inline: True
Inline callers:
  - net/core/gen_stats.c:gnet_stats_basic_sync_init
  - net/core/gen_stats.c:gnet_stats_basic_sync_init
```
```
In net/core/net_namespace.c (ffffffff81db2f95)
Location: include/linux/atomic/atomic-instrumented.h:1277
Inline: True
Inline callers:
  - net/core/net_namespace.c:net_ns_net_init
```
```
In net/core/page_pool.c (ffffffff81e108e7)
Location: include/linux/atomic/atomic-instrumented.h:1277
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_alloc_frag
```
```
In net/ipv4/nexthop.c (ffffffff81f115cf)
Location: include/linux/atomic/atomic-instrumented.h:1277
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_res_grp_activity_update
  - net/ipv4/nexthop.c:nh_res_table_upkeep
  - net/ipv4/nexthop.c:nh_res_bucket_migrate
```
```
In net/unix/af_unix.c (ffffffff81f4c215)
Location: include/linux/atomic/atomic-instrumented.h:1277
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
```
```
In net/packet/af_packet.c (ffffffff81fc58f5)
Location: include/linux/atomic/atomic-instrumented.h:1277
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
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff8100779e)
Location: include/linux/atomic/atomic-instrumented.h:3193
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_setup_perfctr
```
```
In arch/x86/events/amd/ibs.c (ffffffff8100eef6)
Location: include/linux/atomic/atomic-instrumented.h:3193
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
Location: include/linux/atomic/atomic-instrumented.h:3193
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_event_update
```
```
In arch/x86/events/intel/core.c (ffffffff81014e32)
Location: include/linux/atomic/atomic-instrumented.h:3193
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:handle_pmi_common
```
```
In arch/x86/events/intel/bts.c (ffffffff810167b4)
Location: include/linux/atomic/atomic-instrumented.h:3193
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_buffer_reset
  - arch/x86/events/intel/bts.c:bts_update
```
```
In arch/x86/events/intel/ds.c (ffffffff81017ddc)
Location: include/linux/atomic/atomic-instrumented.h:3193
Inline: True
```
```
In arch/x86/events/intel/pt.c (ffffffff81020f3a)
Location: include/linux/atomic/atomic-instrumented.h:3193
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_buffer_reset_offsets
  - arch/x86/events/intel/pt.c:pt_buffer_reset_offsets
  - arch/x86/events/intel/pt.c:pt_update_head
```
```
In arch/x86/events/intel/uncore.c (ffffffff81023c23)
Location: include/linux/atomic/atomic-instrumented.h:3193
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff810e7e5a)
Location: include/linux/atomic/atomic-instrumented.h:3193
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:param_set_local64
```
```
In kernel/fork.c (ffffffff810f138b)
Location: include/linux/atomic/atomic-instrumented.h:3193
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
  - kernel/fork.c:mm_init
```
```
In kernel/workqueue.c (ffffffff811207ee)
Location: include/linux/atomic/atomic-instrumented.h:3193
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
Location: include/linux/atomic/atomic-instrumented.h:3193
Inline: True
Inline callers:
  - kernel/locking/mutex.c:__mutex_init
```
```
In kernel/locking/rwsem.c (ffffffff8118dfcb)
Location: include/linux/atomic/atomic-instrumented.h:3193
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
Location: include/linux/atomic/atomic-instrumented.h:3193
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
Location: include/linux/atomic/atomic-instrumented.h:3193
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_create_default_debugfs
  - kernel/dma/swiotlb.c:swiotlb_create_default_debugfs
  - kernel/dma/swiotlb.c:io_tlb_hiwater_set
```
```
In kernel/time/namespace.c (ffffffff81206c89)
Location: include/linux/atomic/atomic-instrumented.h:3193
Inline: True
Inline callers:
  - kernel/time/namespace.c:copy_time_ns
```
```
In kernel/acct.c (ffffffff81211d5d)
Location: include/linux/atomic/atomic-instrumented.h:3193
Inline: True
Inline callers:
  - kernel/acct.c:acct_on
```
```
In kernel/cgroup/namespace.c (ffffffff81227af4)
Location: include/linux/atomic/atomic-instrumented.h:3193
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
```
```
In kernel/cgroup/misc.c (ffffffff81235a24)
Location: include/linux/atomic/atomic-instrumented.h:3193
Inline: True
Inline callers:
  - kernel/cgroup/misc.c:misc_cg_alloc
```
```
In kernel/utsname.c (ffffffff81235c2f)
Location: include/linux/atomic/atomic-instrumented.h:3193
Inline: True
Inline callers:
  - kernel/utsname.c:clone_uts_ns
```
```
In kernel/user_namespace.c (ffffffff81237cdc)
Location: include/linux/atomic/atomic-instrumented.h:3193
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In kernel/pid_namespace.c (ffffffff81238a53)
Location: include/linux/atomic/atomic-instrumented.h:3193
Inline: True
Inline callers:
  - kernel/pid_namespace.c:create_pid_namespace
```
```
In kernel/audit_tree.c (ffffffff81249d17)
Location: include/linux/atomic/atomic-instrumented.h:3193
Inline: True
Inline callers:
  - kernel/audit_tree.c:alloc_chunk
```
```
In kernel/trace/ring_buffer.c (ffffffff8127872f)
Location: include/linux/atomic/atomic-instrumented.h:3193
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
Location: include/linux/atomic/atomic-instrumented.h:3193
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
Location: include/linux/atomic/atomic-instrumented.h:3193
Inline: True
```
```
In mm/vmstat.c (ffffffff813c7921)
Location: include/linux/atomic/atomic-instrumented.h:3193
Inline: True
Inline callers:
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
```
```
In mm/mm_init.c (ffffffff836e1224)
Location: include/linux/atomic/atomic-instrumented.h:3193
Inline: True
Inline callers:
  - mm/mm_init.c:free_area_init_core
  - mm/mm_init.c:free_area_init_core_hotplug
```
```
In mm/memblock.c (ffffffff836e7519)
Location: include/linux/atomic/atomic-instrumented.h:3193
Inline: True
Inline callers:
  - mm/memblock.c:reset_all_zones_managed_pages
```
```
In mm/swap_state.c (ffffffff8142c697)
Location: include/linux/atomic/atomic-instrumented.h:3193
Inline: True
Inline callers:
  - mm/swap_state.c:swap_vma_readahead
  - mm/swap_state.c:swap_cache_get_folio
```
```
In mm/slub.c (ffffffff8145ff81)
Location: include/linux/atomic/atomic-instrumented.h:3193
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
Location: include/linux/atomic/atomic-instrumented.h:3193
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_cancel
```
```
In mm/memcontrol.c (ffffffff82147d7f)
Location: include/linux/atomic/atomic-instrumented.h:3193
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
Location: include/linux/atomic/atomic-instrumented.h:3193
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
```
```
In fs/file_table.c (ffffffff814b0ef9)
Location: include/linux/atomic/atomic-instrumented.h:3193
Inline: True
Inline callers:
  - fs/file_table.c:init_file
```
```
In fs/namespace.c (ffffffff814e03a3)
Location: include/linux/atomic/atomic-instrumented.h:3193
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In fs/nsfs.c (ffffffff81502bb9)
Location: include/linux/atomic/atomic-instrumented.h:3193
Inline: True
Inline callers:
  - fs/nsfs.c:ns_prune_dentry
```
```
In ipc/namespace.c (ffffffff816854f1)
Location: include/linux/atomic/atomic-instrumented.h:3193
Inline: True
```
```
In block/blk-ioc.c (ffffffff817769c4)
Location: include/linux/atomic/atomic-instrumented.h:3193
Inline: True
Inline callers:
  - block/blk-ioc.c:alloc_io_context
```
```
In block/blk-iocost.c (ffffffff817accb4)
Location: include/linux/atomic/atomic-instrumented.h:3193
Inline: True
Inline callers:
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-iocost.c:blk_iocost_init
```
```
In lib/percpu-refcount.c (ffffffff81817b46)
Location: include/linux/atomic/atomic-instrumented.h:3193
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_init
```
```
In lib/genalloc.c (ffffffff8182e093)
Location: include/linux/atomic/atomic-instrumented.h:3193
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_add_owner
```
```
In drivers/tty/tty_ldsem.c (ffffffff81aa1035)
Location: include/linux/atomic/atomic-instrumented.h:3193
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:__init_ldsem
```
```
In drivers/iommu/intel/perfmon.c (ffffffff81b1ae88)
Location: include/linux/atomic/atomic-instrumented.h:3193
Inline: True
Inline callers:
  - drivers/iommu/intel/perfmon.c:iommu_pmu_start
```
```
In net/core/gen_stats.c (ffffffff81e22425)
Location: include/linux/atomic/atomic-instrumented.h:3193
Inline: True
Inline callers:
  - net/core/gen_stats.c:gnet_stats_basic_sync_init
  - net/core/gen_stats.c:gnet_stats_basic_sync_init
```
```
In net/core/net_namespace.c (ffffffff81e23565)
Location: include/linux/atomic/atomic-instrumented.h:3193
Inline: True
Inline callers:
  - net/core/net_namespace.c:net_ns_net_init
```
```
In net/core/page_pool.c (ffffffff81e841cb)
Location: include/linux/atomic/atomic-instrumented.h:3193
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_alloc_frag
```
```
In net/ipv4/nexthop.c (ffffffff81f712bb)
Location: include/linux/atomic/atomic-instrumented.h:3193
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_res_grp_activity_update
  - net/ipv4/nexthop.c:nh_res_table_upkeep
  - net/ipv4/nexthop.c:nh_res_bucket_migrate
```
```
In net/unix/af_unix.c (ffffffff81fabff5)
Location: include/linux/atomic/atomic-instrumented.h:3193
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
```
```
In net/packet/af_packet.c (ffffffff82029e42)
Location: include/linux/atomic/atomic-instrumented.h:3193
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
Location: include/linux/atomic/atomic-instrumented.h:3193
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_setup_perfctr
```
```
In arch/x86/events/amd/ibs.c (ffffffff81014636)
Location: include/linux/atomic/atomic-instrumented.h:3193
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
Location: include/linux/atomic/atomic-instrumented.h:3193
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_event_update
```
```
In arch/x86/events/intel/core.c (ffffffff81019ded)
Location: include/linux/atomic/atomic-instrumented.h:3193
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:handle_pmi_common
```
```
In arch/x86/events/intel/bts.c (ffffffff8101c2f4)
Location: include/linux/atomic/atomic-instrumented.h:3193
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_buffer_reset
  - arch/x86/events/intel/bts.c:bts_update
```
```
In arch/x86/events/intel/ds.c (ffffffff8101d94c)
Location: include/linux/atomic/atomic-instrumented.h:3193
Inline: True
```
```
In arch/x86/events/intel/pt.c (ffffffff8102705a)
Location: include/linux/atomic/atomic-instrumented.h:3193
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_buffer_reset_offsets
  - arch/x86/events/intel/pt.c:pt_buffer_reset_offsets
  - arch/x86/events/intel/pt.c:pt_update_head
```
```
In arch/x86/events/intel/uncore.c (ffffffff81029d53)
Location: include/linux/atomic/atomic-instrumented.h:3193
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff810f01ea)
Location: include/linux/atomic/atomic-instrumented.h:3193
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:param_set_local64
```
```
In kernel/fork.c (ffffffff810fa75b)
Location: include/linux/atomic/atomic-instrumented.h:3193
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
  - kernel/fork.c:mm_init
```
```
In kernel/workqueue.c (ffffffff8112917e)
Location: include/linux/atomic/atomic-instrumented.h:3193
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
Location: include/linux/atomic/atomic-instrumented.h:3193
Inline: True
Inline callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:cred_alloc_blank
```
```
In kernel/locking/mutex.c (ffffffff8119bc05)
Location: include/linux/atomic/atomic-instrumented.h:3193
Inline: True
Inline callers:
  - kernel/locking/mutex.c:__mutex_init
```
```
In kernel/locking/rwsem.c (ffffffff8119c97b)
Location: include/linux/atomic/atomic-instrumented.h:3193
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
Location: include/linux/atomic/atomic-instrumented.h:3193
Inline: True
Inline callers:
  - kernel/printk/nbcon.c:nbcon_init
```
```
In kernel/printk/printk_ringbuffer.c (ffffffff811b56ad)
Location: include/linux/atomic/atomic-instrumented.h:3193
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
Location: include/linux/atomic/atomic-instrumented.h:3193
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
```
```
In kernel/dma/swiotlb.c (ffffffff83903cb5)
Location: include/linux/atomic/atomic-instrumented.h:3193
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_create_default_debugfs
  - kernel/dma/swiotlb.c:swiotlb_create_default_debugfs
  - kernel/dma/swiotlb.c:io_tlb_hiwater_set
```
```
In kernel/time/namespace.c (ffffffff8121de99)
Location: include/linux/atomic/atomic-instrumented.h:3193
Inline: True
Inline callers:
  - kernel/time/namespace.c:copy_time_ns
```
```
In kernel/acct.c (ffffffff81229408)
Location: include/linux/atomic/atomic-instrumented.h:3193
Inline: True
Inline callers:
  - kernel/acct.c:acct_on
```
```
In kernel/cgroup/namespace.c (ffffffff8123f904)
Location: include/linux/atomic/atomic-instrumented.h:3193
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
```
```
In kernel/utsname.c (ffffffff8124f8af)
Location: include/linux/atomic/atomic-instrumented.h:3193
Inline: True
Inline callers:
  - kernel/utsname.c:clone_uts_ns
```
```
In kernel/user_namespace.c (ffffffff812517dc)
Location: include/linux/atomic/atomic-instrumented.h:3193
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In kernel/pid_namespace.c (ffffffff81252723)
Location: include/linux/atomic/atomic-instrumented.h:3193
Inline: True
Inline callers:
  - kernel/pid_namespace.c:create_pid_namespace
```
```
In kernel/audit_tree.c (ffffffff81263c27)
Location: include/linux/atomic/atomic-instrumented.h:3193
Inline: True
Inline callers:
  - kernel/audit_tree.c:alloc_chunk
```
```
In kernel/trace/ring_buffer.c (ffffffff81293270)
Location: include/linux/atomic/atomic-instrumented.h:3193
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
Location: include/linux/atomic/atomic-instrumented.h:3193
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
Location: include/linux/atomic/atomic-instrumented.h:3193
Inline: True
```
```
In mm/vmstat.c (ffffffff813f2301)
Location: include/linux/atomic/atomic-instrumented.h:3193
Inline: True
Inline callers:
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
```
```
In mm/mm_init.c (ffffffff83913b24)
Location: include/linux/atomic/atomic-instrumented.h:3193
Inline: True
Inline callers:
  - mm/mm_init.c:free_area_init_core
  - mm/mm_init.c:free_area_init_core_hotplug
```
```
In mm/memblock.c (ffffffff83919ac9)
Location: include/linux/atomic/atomic-instrumented.h:3193
Inline: True
Inline callers:
  - mm/memblock.c:reset_all_zones_managed_pages
```
```
In mm/slub.c (ffffffff8145d321)
Location: include/linux/atomic/atomic-instrumented.h:3193
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
Location: include/linux/atomic/atomic-instrumented.h:3193
Inline: True
Inline callers:
  - mm/swap_state.c:swap_vma_readahead
  - mm/swap_state.c:swap_cache_get_folio
```
```
In mm/zswap.c (ffffffff81470555)
Location: include/linux/atomic/atomic-instrumented.h:3193
Inline: True
Inline callers:
  - mm/zswap.c:zswap_lruvec_state_init
```
```
In mm/page_counter.c (ffffffff814b1be0)
Location: include/linux/atomic/atomic-instrumented.h:3193
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_cancel
```
```
In mm/memcontrol.c (ffffffff8222a6b0)
Location: include/linux/atomic/atomic-instrumented.h:3193
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
Location: include/linux/atomic/atomic-instrumented.h:3193
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
```
```
In fs/file_table.c (ffffffff814e2702)
Location: include/linux/atomic/atomic-instrumented.h:3193
Inline: True
Inline callers:
  - fs/file_table.c:init_file
```
```
In fs/namespace.c (ffffffff81513664)
Location: include/linux/atomic/atomic-instrumented.h:3193
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In fs/nsfs.c (ffffffff81537809)
Location: include/linux/atomic/atomic-instrumented.h:3193
Inline: True
Inline callers:
  - fs/nsfs.c:ns_prune_dentry
```
```
In ipc/namespace.c (ffffffff816c1911)
Location: include/linux/atomic/atomic-instrumented.h:3193
Inline: True
```
```
In block/blk-ioc.c (ffffffff817b8bf4)
Location: include/linux/atomic/atomic-instrumented.h:3193
Inline: True
Inline callers:
  - block/blk-ioc.c:alloc_io_context
```
```
In block/blk-iocost.c (ffffffff817f0ab3)
Location: include/linux/atomic/atomic-instrumented.h:3193
Inline: True
Inline callers:
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-iocost.c:blk_iocost_init
```
```
In lib/percpu-refcount.c (ffffffff8185ce42)
Location: include/linux/atomic/atomic-instrumented.h:3193
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_init
```
```
In lib/genalloc.c (ffffffff8187fc53)
Location: include/linux/atomic/atomic-instrumented.h:3193
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_add_owner
```
```
In drivers/tty/tty_ldsem.c (ffffffff81af3a95)
Location: include/linux/atomic/atomic-instrumented.h:3193
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:__init_ldsem
```
```
In drivers/iommu/intel/perfmon.c (ffffffff81b709b8)
Location: include/linux/atomic/atomic-instrumented.h:3193
Inline: True
Inline callers:
  - drivers/iommu/intel/perfmon.c:iommu_pmu_start
```
```
In drivers/net/virtio_net.c (ffffffff81d0c990)
Location: include/linux/atomic/atomic-instrumented.h:3193
Inline: True
```
```
In net/core/skbuff.c (ffffffff81ed1361)
Location: include/linux/atomic/atomic-instrumented.h:3193
Inline: True
Inline callers:
  - net/core/skbuff.c:napi_pp_put_page
```
```
In net/core/gen_stats.c (ffffffff81ee0365)
Location: include/linux/atomic/atomic-instrumented.h:3193
Inline: True
Inline callers:
  - net/core/gen_stats.c:gnet_stats_basic_sync_init
  - net/core/gen_stats.c:gnet_stats_basic_sync_init
```
```
In net/core/net_namespace.c (ffffffff81ee14c5)
Location: include/linux/atomic/atomic-instrumented.h:3193
Inline: True
Inline callers:
  - net/core/net_namespace.c:net_ns_net_init
```
```
In net/core/xdp.c (ffffffff81f397a7)
Location: include/linux/atomic/atomic-instrumented.h:3193
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_return
```
```
In net/core/page_pool.c (ffffffff81f448aa)
Location: include/linux/atomic/atomic-instrumented.h:3193
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
Location: include/linux/atomic/atomic-instrumented.h:3193
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_res_grp_activity_update
  - net/ipv4/nexthop.c:nh_res_table_upkeep
  - net/ipv4/nexthop.c:nh_res_bucket_migrate
```
```
In net/unix/af_unix.c (ffffffff82079415)
Location: include/linux/atomic/atomic-instrumented.h:3193
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
```
```
In net/packet/af_packet.c (ffffffff820f9941)
Location: include/linux/atomic/atomic-instrumented.h:3193
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
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In virt/kvm/arm/pmu.c (ffff8000100eeab4)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - virt/kvm/arm/pmu.c:kvm_pmu_perf_overflow
```
```
In kernel/fork.c (ffff8000100f1c08)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
```
```
In kernel/workqueue.c (ffff80001011f5f4)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/workqueue.c:insert_work
  - kernel/workqueue.c:set_work_pool_and_clear_pending
```
```
In kernel/locking/mutex.c (ffff8000101685d0)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - kernel/locking/mutex.c:__mutex_init
```
```
In kernel/locking/rwsem.c (ffff8000101696cc)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:downgrade_write
  - kernel/locking/rwsem.c:up_write
  - kernel/locking/rwsem.c:down_write_trylock
  - kernel/locking/rwsem.c:down_write_killable
  - kernel/locking/rwsem.c:down_write
  - kernel/locking/rwsem.c:down_read_trylock
  - kernel/locking/rwsem.c:down_read_killable
  - kernel/locking/rwsem.c:down_read
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_mark_wake
  - kernel/locking/rwsem.c:__init_rwsem
  - kernel/locking/rwsem.c:__init_rwsem
```
```
In kernel/acct.c (ffff8000101c7844)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - kernel/acct.c:__arm64_sys_acct
```
```
In kernel/cgroup/namespace.c (ffff8000101da390)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
```
```
In kernel/utsname.c (ffff8000101e52dc)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - kernel/utsname.c:copy_utsname
```
```
In kernel/user_namespace.c (ffff8000101e6900)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In kernel/pid_namespace.c (ffff8000101e782c)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In kernel/audit_tree.c (ffff8000101f4668)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - kernel/audit_tree.c:alloc_chunk
```
```
In kernel/trace/ring_buffer.c (ffff800010218fc8)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/events/core.c (ffff800010297364)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:task_clock_event_add
  - kernel/events/core.c:task_clock_event_stop
  - kernel/events/core.c:cpu_clock_event_add
  - kernel/events/core.c:__perf_event_account_interrupt
  - kernel/events/core.c:_perf_event_reset
  - kernel/events/core.c:perf_event_task_tick
  - kernel/events/core.c:__perf_event_task_sched_out
```
```
In mm/vmstat.c (ffff8000102dba68)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
```
```
In mm/vmalloc.c (ffff80001030d524)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - mm/vmalloc.c:set_iounmap_nonlazy
```
```
In mm/page_alloc.c (ffff8000114576f0)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init_node
  - mm/page_alloc.c:free_area_init_core_hotplug
```
```
In mm/memblock.c (ffff800011458c24)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - mm/memblock.c:reset_all_zones_managed_pages
```
```
In mm/swap_state.c (ffff800010322294)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/slub.c (ffff80001034c22c)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - mm/slub.c:slab_memory_callback
  - mm/slub.c:slab_memory_callback
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:kmem_cache_open
```
```
In mm/memcontrol.c (ffff800010d9d698)
Location: include/asm-generic/atomic-long.h:38
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
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
```
```
In mm/hugetlb_cgroup.c (ffff80001036d27c)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
```
```
In fs/file_table.c (ffff80001038527c)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - fs/file_table.c:__alloc_file
```
```
In fs/super.c (ffff800010386bac)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - fs/super.c:thaw_super_locked
  - fs/super.c:thaw_super_locked
  - fs/super.c:freeze_super
```
```
In fs/namespace.c (ffff8000103b4cf0)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In fs/nsfs.c (ffff8000103d442c)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - fs/nsfs.c:ns_prune_dentry
```
```
In fs/aio.c (0)
Location: include/asm-generic/atomic-long.h:38
Inline: True
```
```
In fs/io_uring.c (0)
Location: include/asm-generic/atomic-long.h:38
Inline: True
```
```
In ipc/namespace.c (ffff80001052cce0)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - ipc/namespace.c:copy_ipcs
```
```
In block/blk-ioc.c (ffff8000105e8d58)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - block/blk-ioc.c:create_task_io_context
```
```
In lib/percpu-refcount.c (ffff800010634de0)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_init
```
```
In lib/genalloc.c (ffff8000106448d4)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_add_owner
```
```
In drivers/tty/tty_ldsem.c (ffff80001085f5c8)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:__init_ldsem
```
```
In drivers/perf/arm-cci.c (ffff800010b919b8)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - drivers/perf/arm-cci.c:cci_pmu_start
  - drivers/perf/arm-cci.c:pmu_handle_irq
```
```
In drivers/perf/arm-ccn.c (ffff800010b9351c)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - drivers/perf/arm-ccn.c:arm_ccn_pmu_event_start
```
```
In drivers/perf/arm_pmu.c (ffff800010b947dc)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - drivers/perf/arm_pmu.c:armpmu_event_init
  - drivers/perf/arm_pmu.c:armpmu_event_set_period
  - drivers/perf/arm_pmu.c:armpmu_event_set_period
  - drivers/perf/arm_pmu.c:armpmu_event_set_period
```
```
In drivers/perf/hisilicon/hisi_uncore_pmu.c (ffff800010b966c0)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - drivers/perf/hisilicon/hisi_uncore_pmu.c:hisi_uncore_pmu_start
```
```
In drivers/perf/qcom_l2_pmu.c (ffff800010b99a3c)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - drivers/perf/qcom_l2_pmu.c:l2_cache_event_add
  - drivers/perf/qcom_l2_pmu.c:l2_cache_event_start
  - drivers/perf/qcom_l2_pmu.c:l2_cache_handle_irq
```
```
In drivers/perf/qcom_l3_pmu.c (ffff800010b9aa7c)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - drivers/perf/qcom_l3_pmu.c:qcom_l3_cache__32bit_counter_start
  - drivers/perf/qcom_l3_pmu.c:qcom_l3_cache__64bit_counter_start
```
```
In drivers/perf/xgene_pmu.c (ffff800010b9b544)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - drivers/perf/xgene_pmu.c:xgene_perf_start
```
```
In net/core/net_namespace.c (ffff800010bc0094)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - net/core/net_namespace.c:net_ns_net_init
```
```
In net/unix/af_unix.c (ffff800010cf0e64)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
```
```
In net/packet/af_packet.c (ffff800010d5ceec)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
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
In kernel/fork.c (c0350ad4)
Location: include/asm-generic/atomic-long.h:532
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
```
```
In kernel/workqueue.c (c037284c)
Location: include/asm-generic/atomic-long.h:532
Inline: True
Inline callers:
  - kernel/workqueue.c:cancel_delayed_work
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:insert_work
```
```
In kernel/locking/mutex.c (c03b4cd0)
Location: include/asm-generic/atomic-long.h:532
Inline: True
Inline callers:
  - kernel/locking/mutex.c:__mutex_init
```
```
In kernel/locking/rwsem.c (c03b5640)
Location: include/asm-generic/atomic-long.h:532
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:downgrade_write
  - kernel/locking/rwsem.c:up_write
  - kernel/locking/rwsem.c:down_write_trylock
  - kernel/locking/rwsem.c:down_write_killable
  - kernel/locking/rwsem.c:down_write
  - kernel/locking/rwsem.c:down_read_trylock
  - kernel/locking/rwsem.c:down_read_killable
  - kernel/locking/rwsem.c:down_read
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_mark_wake
  - kernel/locking/rwsem.c:__init_rwsem
  - kernel/locking/rwsem.c:__init_rwsem
```
```
In kernel/acct.c (c040ee60)
Location: include/asm-generic/atomic-long.h:532
Inline: True
Inline callers:
  - kernel/acct.c:__se_sys_acct
```
```
In kernel/cgroup/namespace.c (c041cbf8)
Location: include/asm-generic/atomic-long.h:532
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
```
```
In kernel/utsname.c (c0425b88)
Location: include/asm-generic/atomic-long.h:532
Inline: True
Inline callers:
  - kernel/utsname.c:copy_utsname
```
```
In kernel/user_namespace.c (c0426ffc)
Location: include/asm-generic/atomic-long.h:532
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In kernel/pid_namespace.c (c0427c1c)
Location: include/asm-generic/atomic-long.h:532
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In kernel/audit_tree.c (c0434c6c)
Location: include/asm-generic/atomic-long.h:532
Inline: True
Inline callers:
  - kernel/audit_tree.c:alloc_chunk
```
```
In kernel/trace/ring_buffer.c (c045ab3c)
Location: include/asm-generic/atomic-long.h:532
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
```
```
In kernel/events/core.c (c04c7500)
Location: include/asm-generic/atomic-long.h:532
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In mm/vmalloc.c (c0529068)
Location: include/asm-generic/atomic-long.h:532
Inline: True
Inline callers:
  - mm/vmalloc.c:set_iounmap_nonlazy
```
```
In mm/page_alloc.c (c1531bd8)
Location: include/asm-generic/atomic-long.h:532
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init_node
```
```
In mm/memblock.c (c1532ba8)
Location: include/asm-generic/atomic-long.h:532
Inline: True
Inline callers:
  - mm/memblock.c:reset_all_zones_managed_pages
```
```
In mm/swap_state.c (c053a954)
Location: include/asm-generic/atomic-long.h:532
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/slub.c (c054f4f4)
Location: include/asm-generic/atomic-long.h:532
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:kmem_cache_open
```
```
In mm/memcontrol.c (c0e98e28)
Location: include/asm-generic/atomic-long.h:532
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
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
```
```
In fs/file_table.c (c056e158)
Location: include/asm-generic/atomic-long.h:532
Inline: True
Inline callers:
  - fs/file_table.c:__alloc_file
```
```
In fs/super.c (c056f448)
Location: include/asm-generic/atomic-long.h:532
Inline: True
Inline callers:
  - fs/super.c:thaw_super_locked
  - fs/super.c:thaw_super_locked
  - fs/super.c:freeze_super
```
```
In fs/namespace.c (c0592a1c)
Location: include/asm-generic/atomic-long.h:532
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In fs/nsfs.c (c05ae458)
Location: include/asm-generic/atomic-long.h:532
Inline: True
Inline callers:
  - fs/nsfs.c:ns_prune_dentry
```
```
In fs/aio.c (0)
Location: include/asm-generic/atomic-long.h:532
Inline: True
```
```
In fs/io_uring.c (0)
Location: include/asm-generic/atomic-long.h:532
Inline: True
```
```
In ipc/namespace.c (c06e55dc)
Location: include/asm-generic/atomic-long.h:532
Inline: True
Inline callers:
  - ipc/namespace.c:copy_ipcs
```
```
In block/blk-ioc.c (c07954b0)
Location: include/asm-generic/atomic-long.h:532
Inline: True
Inline callers:
  - block/blk-ioc.c:create_task_io_context
```
```
In lib/percpu-refcount.c (c07dae90)
Location: include/asm-generic/atomic-long.h:532
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_init
```
```
In lib/genalloc.c (c07ea50c)
Location: include/asm-generic/atomic-long.h:532
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_add_owner
```
```
In drivers/tty/tty_ldsem.c (c09669ec)
Location: include/asm-generic/atomic-long.h:532
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:__init_ldsem
```
```
In net/core/net_namespace.c (c0cdbc10)
Location: include/asm-generic/atomic-long.h:532
Inline: True
Inline callers:
  - net/core/net_namespace.c:net_ns_net_init
```
```
In net/unix/af_unix.c (c0df792c)
Location: include/asm-generic/atomic-long.h:532
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
```
```
In net/packet/af_packet.c (c0e5ddac)
Location: include/asm-generic/atomic-long.h:532
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
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
In kernel/fork.c (c000000000137334)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
```
```
In kernel/workqueue.c (c00000000016689c)
Location: include/asm-generic/atomic-long.h:38
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
In kernel/locking/mutex.c (c0000000001c0358)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - kernel/locking/mutex.c:__mutex_init
```
```
In kernel/locking/rwsem.c (c0000000001c0ec0)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:downgrade_write
  - kernel/locking/rwsem.c:up_write
  - kernel/locking/rwsem.c:down_write_trylock
  - kernel/locking/rwsem.c:down_write_killable
  - kernel/locking/rwsem.c:down_write
  - kernel/locking/rwsem.c:down_read_trylock
  - kernel/locking/rwsem.c:down_read_killable
  - kernel/locking/rwsem.c:down_read
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_mark_wake
  - kernel/locking/rwsem.c:__init_rwsem
  - kernel/locking/rwsem.c:__init_rwsem
```
```
In kernel/acct.c (c000000000230418)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - kernel/acct.c:__se_sys_acct
```
```
In kernel/cgroup/namespace.c (c000000000247618)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
```
```
In kernel/utsname.c (c0000000002556e8)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - kernel/utsname.c:copy_utsname
```
```
In kernel/user_namespace.c (c000000000257088)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In kernel/pid_namespace.c (c000000000258128)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In kernel/audit_tree.c (c000000000269c5c)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - kernel/audit_tree.c:alloc_chunk
```
```
In kernel/events/core.c (c000000000346c5c)
Location: include/asm-generic/atomic-long.h:38
Inline: True
```
```
In mm/vmstat.c (c00000000039b478)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
```
```
In mm/vmalloc.c (c0000000003ddf50)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - mm/vmalloc.c:set_iounmap_nonlazy
```
```
In mm/page_alloc.c (c000000000eec3f8)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - mm/page_alloc.c:zone_init_internals
```
```
In mm/memblock.c (c0000000013824f0)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - mm/memblock.c:reset_all_zones_managed_pages
```
```
In mm/swap_state.c (c0000000003f7cec)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/slub.c (c00000000042bb68)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - mm/slub.c:slab_memory_callback
  - mm/slub.c:slab_memory_callback
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:kmem_cache_open
```
```
In mm/memcontrol.c (c00000000045bd00)
Location: include/asm-generic/atomic-long.h:38
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
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
```
```
In mm/hugetlb_cgroup.c (c00000000045d618)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
```
```
In fs/file_table.c (c00000000047b224)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - fs/file_table.c:__alloc_file
```
```
In fs/super.c (c00000000047cbc8)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - fs/super.c:thaw_super_locked
  - fs/super.c:thaw_super_locked
  - fs/super.c:freeze_super
```
```
In fs/namespace.c (c0000000004b0c20)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In fs/nsfs.c (c0000000004d7024)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - fs/nsfs.c:ns_prune_dentry
```
```
In fs/aio.c (0)
Location: include/asm-generic/atomic-long.h:38
Inline: True
```
```
In fs/io_uring.c (0)
Location: include/asm-generic/atomic-long.h:38
Inline: True
```
```
In ipc/namespace.c (c000000000678ce0)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - ipc/namespace.c:copy_ipcs
```
```
In block/blk-ioc.c (c00000000077d908)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - block/blk-ioc.c:create_task_io_context
```
```
In lib/percpu-refcount.c (c0000000007da52c)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_init
```
```
In lib/genalloc.c (c0000000007efe0c)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_add_owner
```
```
In drivers/tty/tty_ldsem.c (c0000000008feb58)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:__init_ldsem
```
```
In net/core/net_namespace.c (c000000000c996dc)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - net/core/net_namespace.c:net_ns_net_init
```
```
In net/unix/af_unix.c (c000000000e147d8)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
```
```
In net/packet/af_packet.c (c000000000e9873c)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
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
In arch/riscv/kernel/perf_event.c (ffffffe0000b9538)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - arch/riscv/kernel/perf_event.c:riscv_pmu_start
```
```
In kernel/fork.c (ffffffe0000bec16)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
```
```
In kernel/workqueue.c (ffffffe0000d9a6c)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/workqueue.c:insert_work
  - kernel/workqueue.c:set_work_pool_and_clear_pending
```
```
In kernel/locking/mutex.c (ffffffe00010a408)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - kernel/locking/mutex.c:__mutex_init
```
```
In kernel/locking/rwsem.c (ffffffe00010aa84)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:downgrade_write
  - kernel/locking/rwsem.c:up_write
  - kernel/locking/rwsem.c:down_write_trylock
  - kernel/locking/rwsem.c:down_write_killable
  - kernel/locking/rwsem.c:down_write
  - kernel/locking/rwsem.c:down_read_trylock
  - kernel/locking/rwsem.c:down_read_killable
  - kernel/locking/rwsem.c:down_read
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_mark_wake
  - kernel/locking/rwsem.c:__init_rwsem
  - kernel/locking/rwsem.c:__init_rwsem
```
```
In kernel/acct.c (ffffffe000147e2c)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - kernel/acct.c:__se_sys_acct
```
```
In kernel/cgroup/namespace.c (ffffffe000152a90)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
```
```
In kernel/utsname.c (ffffffe00015afb8)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - kernel/utsname.c:copy_utsname
```
```
In kernel/user_namespace.c (ffffffe00015c1b4)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In kernel/pid_namespace.c (ffffffe00015ccf2)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In kernel/audit_tree.c (ffffffe0001678ec)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - kernel/audit_tree.c:alloc_chunk
```
```
In kernel/trace/ring_buffer.c (ffffffe000179c64)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
```
```
In kernel/events/core.c (ffffffe0001cdede)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - kernel/events/core.c:task_clock_event_add
  - kernel/events/core.c:cpu_clock_event_add
  - kernel/events/core.c:cpu_clock_event_stop
  - kernel/events/core.c:__perf_event_account_interrupt
  - kernel/events/core.c:_perf_event_reset
  - kernel/events/core.c:perf_event_task_tick
  - kernel/events/core.c:__perf_event_task_sched_out
```
```
In mm/vmalloc.c (ffffffe0002162d6)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - mm/vmalloc.c:set_iounmap_nonlazy
```
```
In mm/page_alloc.c (ffffffe0000161b6)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init_node
```
```
In mm/memblock.c (ffffffe000017270)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - mm/memblock.c:reset_all_zones_managed_pages
```
```
In mm/swap_state.c (ffffffe0002232a8)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/slub.c (ffffffe00023cb94)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:kmem_cache_open
```
```
In mm/memcontrol.c (ffffffe0008c48f2)
Location: include/asm-generic/atomic-long.h:38
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
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
```
```
In mm/hugetlb_cgroup.c (ffffffe00024a096)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
```
```
In fs/file_table.c (ffffffe000258060)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - fs/file_table.c:__alloc_file
```
```
In fs/namespace.c (ffffffe000277430)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In fs/nsfs.c (ffffffe00028e942)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - fs/nsfs.c:ns_prune_dentry
```
```
In ipc/namespace.c (ffffffe00038ebee)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - ipc/namespace.c:copy_ipcs
```
```
In block/blk-ioc.c (ffffffe000429666)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - block/blk-ioc.c:create_task_io_context
```
```
In lib/percpu-refcount.c (ffffffe000462934)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_init
```
```
In lib/genalloc.c (ffffffe000470850)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_add_owner
```
```
In drivers/tty/tty_ldsem.c (ffffffe0005379f2)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:__init_ldsem
```
```
In net/core/net_namespace.c (ffffffe00074d9aa)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - net/core/net_namespace.c:net_ns_net_init
```
```
In net/unix/af_unix.c (ffffffe00083d16e)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
```
```
In net/packet/af_packet.c (ffffffe00089320c)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
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
In arch/x86/events/core.c (ffffffff8100782d)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_setup_perfctr
```
```
In arch/x86/events/amd/uncore.c (ffffffff81009584)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_read
```
```
In arch/x86/events/amd/ibs.c (ffffffff8100ad86)
Location: include/asm-generic/atomic-long.h:38
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
In arch/x86/events/msr.c (ffffffff8100b9cc)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_event_update
```
```
In arch/x86/events/intel/core.c (ffffffff8100e29e)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_save_and_restart
```
```
In arch/x86/events/intel/bts.c (ffffffff8100ec49)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_update
```
```
In arch/x86/events/intel/ds.c (ffffffff8100fc51)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pmu_save_and_restart_reload
  - arch/x86/events/intel/ds.c:intel_pmu_save_and_restart_reload
```
```
In arch/x86/events/intel/pt.c (ffffffff81014ac0)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_buffer_reset_offsets
  - arch/x86/events/intel/pt.c:pt_buffer_reset_offsets
  - arch/x86/events/intel/pt.c:pt_update_head
```
```
In arch/x86/events/intel/uncore.c (ffffffff81016551)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
```
```
In kernel/fork.c (ffffffff81096c7d)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
```
```
In kernel/workqueue.c (ffffffff810bb8b1)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - kernel/workqueue.c:cancel_delayed_work
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:insert_work
```
```
In kernel/locking/mutex.c (ffffffff810fc785)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - kernel/locking/mutex.c:__mutex_init
```
```
In kernel/locking/rwsem.c (ffffffff810fcef5)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:downgrade_write
  - kernel/locking/rwsem.c:up_write
  - kernel/locking/rwsem.c:down_write_trylock
  - kernel/locking/rwsem.c:down_write_killable
  - kernel/locking/rwsem.c:down_write
  - kernel/locking/rwsem.c:down_read_trylock
  - kernel/locking/rwsem.c:down_read_killable
  - kernel/locking/rwsem.c:down_read
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_mark_wake
  - kernel/locking/rwsem.c:__init_rwsem
  - kernel/locking/rwsem.c:__init_rwsem
```
```
In kernel/acct.c (ffffffff81150dde)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - kernel/acct.c:acct_on
```
```
In kernel/cgroup/namespace.c (ffffffff811600bc)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
```
```
In kernel/utsname.c (ffffffff81169cde)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - kernel/utsname.c:copy_utsname
```
```
In kernel/user_namespace.c (ffffffff8116af97)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In kernel/pid_namespace.c (ffffffff8116bb16)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In kernel/audit_tree.c (ffffffff81177e9d)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - kernel/audit_tree.c:alloc_chunk
```
```
In kernel/trace/ring_buffer.c (ffffffff8119a28c)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/events/core.c (ffffffff81207928)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:task_clock_event_add
  - kernel/events/core.c:cpu_clock_event_start
  - kernel/events/core.c:__perf_event_period
  - kernel/events/core.c:_perf_event_reset
  - kernel/events/core.c:__perf_event_task_sched_out
```
```
In mm/vmstat.c (ffffffff8123fd43)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
```
```
In mm/vmalloc.c (ffffffff8126f643)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - mm/vmalloc.c:set_iounmap_nonlazy
```
```
In mm/page_alloc.c (ffffffff828c7888)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init_node
  - mm/page_alloc.c:free_area_init_core_hotplug
```
```
In mm/memblock.c (ffffffff828c89d2)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - mm/memblock.c:reset_all_zones_managed_pages
```
```
In mm/swap_state.c (ffffffff8127fd66)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/slub.c (ffffffff812a2a11)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - mm/slub.c:slab_memory_callback
  - mm/slub.c:slab_memory_callback
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:kmem_cache_open
```
```
In mm/memcontrol.c (ffffffff81a68bae)
Location: include/asm-generic/atomic-long.h:38
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
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
```
```
In mm/hugetlb_cgroup.c (ffffffff812c211a)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
```
```
In fs/file_table.c (ffffffff812d7131)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - fs/file_table.c:__alloc_file
```
```
In fs/super.c (ffffffff812d8453)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - fs/super.c:thaw_super_locked
  - fs/super.c:thaw_super_locked
  - fs/super.c:freeze_super
```
```
In fs/namespace.c (ffffffff812f9ae2)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In fs/nsfs.c (ffffffff81314e29)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - fs/nsfs.c:ns_prune_dentry
```
```
In fs/aio.c (0)
Location: include/asm-generic/atomic-long.h:38
Inline: True
```
```
In fs/io_uring.c (0)
Location: include/asm-generic/atomic-long.h:38
Inline: True
```
```
In ipc/namespace.c (ffffffff8143c894)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - ipc/namespace.c:copy_ipcs
```
```
In block/blk-ioc.c (ffffffff814e2c66)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - block/blk-ioc.c:create_task_io_context
```
```
In lib/percpu-refcount.c (ffffffff8152244d)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_init
```
```
In lib/genalloc.c (ffffffff8152fd8e)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_add_owner
```
```
In drivers/tty/tty_ldsem.c (ffffffff81653cf5)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:__init_ldsem
```
```
In net/core/net_namespace.c (ffffffff818c4675)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - net/core/net_namespace.c:net_ns_net_init
```
```
In net/unix/af_unix.c (ffffffff819d021b)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
```
```
In net/packet/af_packet.c (ffffffff81a2ebd7)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
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
In arch/x86/events/core.c (ffffffff81005fcd)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_setup_perfctr
```
```
In arch/x86/events/amd/uncore.c (ffffffff8100827f)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_read
```
```
In arch/x86/events/amd/ibs.c (ffffffff81009713)
Location: include/asm-generic/atomic-long.h:38
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
In arch/x86/events/msr.c (ffffffff8100a28a)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_event_start
  - arch/x86/events/msr.c:msr_event_update
```
```
In arch/x86/events/intel/core.c (ffffffff8100ceed)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_save_and_restart
```
```
In arch/x86/events/intel/bts.c (ffffffff8100d9a9)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_update
```
```
In arch/x86/events/intel/ds.c (ffffffff8100e9c9)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pmu_save_and_restart_reload
  - arch/x86/events/intel/ds.c:intel_pmu_save_and_restart_reload
```
```
In arch/x86/events/intel/pt.c (ffffffff81013d90)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_buffer_reset_offsets
  - arch/x86/events/intel/pt.c:pt_buffer_reset_offsets
  - arch/x86/events/intel/pt.c:pt_update_head
```
```
In arch/x86/events/intel/uncore.c (ffffffff81015981)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
```
```
In kernel/fork.c (ffffffff810856fd)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
```
```
In kernel/workqueue.c (ffffffff810aa350)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - kernel/workqueue.c:cancel_delayed_work
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:insert_work
```
```
In kernel/locking/mutex.c (ffffffff810ec995)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - kernel/locking/mutex.c:__mutex_init
```
```
In kernel/locking/rwsem.c (ffffffff810ed105)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:downgrade_write
  - kernel/locking/rwsem.c:up_write
  - kernel/locking/rwsem.c:down_write_trylock
  - kernel/locking/rwsem.c:down_write_killable
  - kernel/locking/rwsem.c:down_write
  - kernel/locking/rwsem.c:down_read_trylock
  - kernel/locking/rwsem.c:down_read_killable
  - kernel/locking/rwsem.c:down_read
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_mark_wake
  - kernel/locking/rwsem.c:__init_rwsem
  - kernel/locking/rwsem.c:__init_rwsem
```
```
In kernel/rcu/rcu_segcblist.c (ffffffff81116790)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
```
```
In kernel/acct.c (ffffffff8114408e)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - kernel/acct.c:acct_on
```
```
In kernel/cgroup/namespace.c (ffffffff81153326)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
```
```
In kernel/utsname.c (ffffffff8115cede)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - kernel/utsname.c:copy_utsname
```
```
In kernel/user_namespace.c (ffffffff8115e197)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In kernel/pid_namespace.c (ffffffff8115ed16)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In kernel/audit_tree.c (ffffffff8116b03d)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - kernel/audit_tree.c:alloc_chunk
```
```
In kernel/trace/ring_buffer.c (ffffffff8118d30c)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/events/core.c (ffffffff811faa58)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:task_clock_event_add
  - kernel/events/core.c:cpu_clock_event_start
  - kernel/events/core.c:__perf_event_period
  - kernel/events/core.c:_perf_event_reset
  - kernel/events/core.c:__perf_event_task_sched_out
```
```
In mm/vmstat.c (ffffffff81232d43)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
```
```
In mm/vmalloc.c (ffffffff812615b3)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - mm/vmalloc.c:set_iounmap_nonlazy
```
```
In mm/page_alloc.c (ffffffff828bffad)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init_node
  - mm/page_alloc.c:free_area_init_core_hotplug
```
```
In mm/memblock.c (ffffffff828c10f7)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - mm/memblock.c:reset_all_zones_managed_pages
```
```
In mm/swap_state.c (ffffffff81271b92)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/slub.c (ffffffff812944e1)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - mm/slub.c:slab_memory_callback
  - mm/slub.c:slab_memory_callback
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:kmem_cache_open
```
```
In mm/memcontrol.c (ffffffff81a2566e)
Location: include/asm-generic/atomic-long.h:38
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
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
```
```
In mm/hugetlb_cgroup.c (ffffffff812b316a)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
```
```
In fs/file_table.c (ffffffff812c7db1)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - fs/file_table.c:__alloc_file
```
```
In fs/super.c (ffffffff812c90d3)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - fs/super.c:thaw_super_locked
  - fs/super.c:thaw_super_locked
  - fs/super.c:freeze_super
```
```
In fs/namespace.c (ffffffff812ea702)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In fs/nsfs.c (ffffffff81305a19)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - fs/nsfs.c:ns_prune_dentry
```
```
In fs/aio.c (0)
Location: include/asm-generic/atomic-long.h:38
Inline: True
```
```
In fs/io_uring.c (0)
Location: include/asm-generic/atomic-long.h:38
Inline: True
```
```
In ipc/namespace.c (ffffffff8142d304)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - ipc/namespace.c:copy_ipcs
```
```
In block/blk-ioc.c (ffffffff814d35f6)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - block/blk-ioc.c:create_task_io_context
```
```
In lib/percpu-refcount.c (ffffffff8151273d)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_init
```
```
In lib/genalloc.c (ffffffff8152006e)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_add_owner
```
```
In drivers/tty/tty_ldsem.c (ffffffff816340d5)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:__init_ldsem
```
```
In net/core/net_namespace.c (ffffffff8187e5b5)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - net/core/net_namespace.c:net_ns_net_init
```
```
In net/unix/af_unix.c (ffffffff8198cfdb)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
```
```
In net/packet/af_packet.c (ffffffff819ebdc7)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
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
In arch/x86/events/core.c (ffffffff810077ed)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_setup_perfctr
```
```
In arch/x86/events/amd/uncore.c (ffffffff81009544)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_read
```
```
In arch/x86/events/amd/ibs.c (ffffffff8100ad46)
Location: include/asm-generic/atomic-long.h:38
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
In arch/x86/events/msr.c (ffffffff8100b98c)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_event_update
```
```
In arch/x86/events/intel/core.c (ffffffff8100e25e)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_save_and_restart
```
```
In arch/x86/events/intel/bts.c (ffffffff8100ec09)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_update
```
```
In arch/x86/events/intel/ds.c (ffffffff8100fc11)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pmu_save_and_restart_reload
  - arch/x86/events/intel/ds.c:intel_pmu_save_and_restart_reload
```
```
In arch/x86/events/intel/pt.c (ffffffff81014a80)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_buffer_reset_offsets
  - arch/x86/events/intel/pt.c:pt_buffer_reset_offsets
  - arch/x86/events/intel/pt.c:pt_update_head
```
```
In arch/x86/events/intel/uncore.c (ffffffff81016511)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
```
```
In kernel/fork.c (ffffffff81096c2d)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
```
```
In kernel/workqueue.c (ffffffff810bae11)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - kernel/workqueue.c:cancel_delayed_work
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:insert_work
```
```
In kernel/locking/mutex.c (ffffffff810f9945)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - kernel/locking/mutex.c:__mutex_init
```
```
In kernel/locking/rwsem.c (ffffffff810fa0b5)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:downgrade_write
  - kernel/locking/rwsem.c:up_write
  - kernel/locking/rwsem.c:down_write_trylock
  - kernel/locking/rwsem.c:down_write_killable
  - kernel/locking/rwsem.c:down_write
  - kernel/locking/rwsem.c:down_read_trylock
  - kernel/locking/rwsem.c:down_read_killable
  - kernel/locking/rwsem.c:down_read
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_mark_wake
  - kernel/locking/rwsem.c:__init_rwsem
  - kernel/locking/rwsem.c:__init_rwsem
```
```
In kernel/acct.c (ffffffff8114ec8e)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - kernel/acct.c:acct_on
```
```
In kernel/cgroup/namespace.c (ffffffff8115de8c)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
```
```
In kernel/utsname.c (ffffffff81167aae)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - kernel/utsname.c:copy_utsname
```
```
In kernel/user_namespace.c (ffffffff81168d67)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In kernel/pid_namespace.c (ffffffff811698e6)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In kernel/audit_tree.c (ffffffff81175c6d)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - kernel/audit_tree.c:alloc_chunk
```
```
In kernel/trace/ring_buffer.c (ffffffff8119805c)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/events/core.c (ffffffff812056f8)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:task_clock_event_add
  - kernel/events/core.c:cpu_clock_event_start
  - kernel/events/core.c:__perf_event_period
  - kernel/events/core.c:_perf_event_reset
  - kernel/events/core.c:__perf_event_task_sched_out
```
```
In mm/vmstat.c (ffffffff8123dae3)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
```
```
In mm/vmalloc.c (ffffffff8126d3e3)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - mm/vmalloc.c:set_iounmap_nonlazy
```
```
In mm/page_alloc.c (ffffffff828da608)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init_node
  - mm/page_alloc.c:free_area_init_core_hotplug
```
```
In mm/memblock.c (ffffffff828db752)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - mm/memblock.c:reset_all_zones_managed_pages
```
```
In mm/swap_state.c (ffffffff8127dbba)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/slub.c (ffffffff812a0821)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - mm/slub.c:slab_memory_callback
  - mm/slub.c:slab_memory_callback
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:kmem_cache_open
```
```
In mm/memcontrol.c (ffffffff81ad4fbe)
Location: include/asm-generic/atomic-long.h:38
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
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
```
```
In mm/hugetlb_cgroup.c (ffffffff812bff2a)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
```
```
In fs/file_table.c (ffffffff812d4f41)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - fs/file_table.c:__alloc_file
```
```
In fs/super.c (ffffffff812d6263)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - fs/super.c:thaw_super_locked
  - fs/super.c:thaw_super_locked
  - fs/super.c:freeze_super
```
```
In fs/namespace.c (ffffffff812f78d2)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In fs/nsfs.c (ffffffff81312c19)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - fs/nsfs.c:ns_prune_dentry
```
```
In fs/aio.c (0)
Location: include/asm-generic/atomic-long.h:38
Inline: True
```
```
In fs/io_uring.c (0)
Location: include/asm-generic/atomic-long.h:38
Inline: True
```
```
In ipc/namespace.c (ffffffff81438a34)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - ipc/namespace.c:copy_ipcs
```
```
In block/blk-ioc.c (ffffffff814decf6)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - block/blk-ioc.c:create_task_io_context
```
```
In lib/percpu-refcount.c (ffffffff8151e4dd)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_init
```
```
In lib/genalloc.c (ffffffff8152bace)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_add_owner
```
```
In drivers/tty/tty_ldsem.c (ffffffff816820b5)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:__init_ldsem
```
```
In net/core/net_namespace.c (ffffffff81915675)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - net/core/net_namespace.c:net_ns_net_init
```
```
In net/unix/af_unix.c (ffffffff81a3ac9b)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
```
```
In net/packet/af_packet.c (ffffffff81a9a787)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
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
In arch/x86/events/core.c (ffffffff8100794d)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_setup_perfctr
```
```
In arch/x86/events/amd/uncore.c (ffffffff810096a4)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_read
```
```
In arch/x86/events/amd/ibs.c (ffffffff8100acd6)
Location: include/asm-generic/atomic-long.h:38
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
In arch/x86/events/msr.c (ffffffff8100bb6c)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_event_update
```
```
In arch/x86/events/intel/core.c (ffffffff8100e42e)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_save_and_restart
```
```
In arch/x86/events/intel/bts.c (ffffffff8100edd9)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_update
```
```
In arch/x86/events/intel/ds.c (ffffffff8100fe21)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pmu_save_and_restart_reload
  - arch/x86/events/intel/ds.c:intel_pmu_save_and_restart_reload
```
```
In arch/x86/events/intel/pt.c (ffffffff81014cc0)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_buffer_reset_offsets
  - arch/x86/events/intel/pt.c:pt_buffer_reset_offsets
  - arch/x86/events/intel/pt.c:pt_update_head
```
```
In arch/x86/events/intel/uncore.c (ffffffff81016751)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff8109a6ca)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:param_set_local64
```
```
In kernel/fork.c (ffffffff8109eacd)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
```
```
In kernel/workqueue.c (ffffffff810c42d1)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - kernel/workqueue.c:cancel_delayed_work
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:insert_work
```
```
In kernel/locking/mutex.c (ffffffff81104aa5)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - kernel/locking/mutex.c:__mutex_init
```
```
In kernel/locking/rwsem.c (ffffffff81105225)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:downgrade_write
  - kernel/locking/rwsem.c:up_write
  - kernel/locking/rwsem.c:down_write_trylock
  - kernel/locking/rwsem.c:down_write_killable
  - kernel/locking/rwsem.c:down_write
  - kernel/locking/rwsem.c:down_read_trylock
  - kernel/locking/rwsem.c:down_read_killable
  - kernel/locking/rwsem.c:down_read
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_mark_wake
  - kernel/locking/rwsem.c:__init_rwsem
  - kernel/locking/rwsem.c:__init_rwsem
```
```
In kernel/acct.c (ffffffff8115ba6e)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - kernel/acct.c:acct_on
```
```
In kernel/cgroup/namespace.c (ffffffff8116b0f7)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
```
```
In kernel/utsname.c (ffffffff8117518e)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - kernel/utsname.c:copy_utsname
```
```
In kernel/user_namespace.c (ffffffff81176457)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In kernel/pid_namespace.c (ffffffff81177006)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In kernel/audit_tree.c (ffffffff8118355d)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - kernel/audit_tree.c:alloc_chunk
```
```
In kernel/trace/ring_buffer.c (ffffffff811a5c8c)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/events/core.c (ffffffff81214568)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:task_clock_event_add
  - kernel/events/core.c:cpu_clock_event_start
  - kernel/events/core.c:__perf_event_period
  - kernel/events/core.c:_perf_event_reset
  - kernel/events/core.c:__perf_event_task_sched_out
```
```
In mm/vmstat.c (ffffffff8124d213)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
```
```
In mm/vmalloc.c (ffffffff8127cd73)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - mm/vmalloc.c:set_iounmap_nonlazy
```
```
In mm/page_alloc.c (ffffffff828dfa29)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init_node
  - mm/page_alloc.c:free_area_init_core_hotplug
```
```
In mm/memblock.c (ffffffff828e0b73)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - mm/memblock.c:reset_all_zones_managed_pages
```
```
In mm/swap_state.c (ffffffff8128d76a)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/slub.c (ffffffff812b0961)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - mm/slub.c:slab_memory_callback
  - mm/slub.c:slab_memory_callback
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:kmem_cache_open
```
```
In mm/memcontrol.c (ffffffff81ae148e)
Location: include/asm-generic/atomic-long.h:38
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
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
```
```
In mm/hugetlb_cgroup.c (ffffffff812d096a)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
```
```
In fs/file_table.c (ffffffff812e5da1)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - fs/file_table.c:__alloc_file
```
```
In fs/super.c (ffffffff812e6e23)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - fs/super.c:thaw_super_locked
  - fs/super.c:thaw_super_locked
  - fs/super.c:freeze_super
```
```
In fs/namespace.c (ffffffff81308be2)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In fs/nsfs.c (ffffffff81324449)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - fs/nsfs.c:ns_prune_dentry
```
```
In fs/aio.c (0)
Location: include/asm-generic/atomic-long.h:38
Inline: True
```
```
In fs/io_uring.c (0)
Location: include/asm-generic/atomic-long.h:38
Inline: True
```
```
In ipc/namespace.c (ffffffff8144fba4)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - ipc/namespace.c:copy_ipcs
```
```
In block/blk-ioc.c (ffffffff814f7b66)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - block/blk-ioc.c:create_task_io_context
```
```
In lib/percpu-refcount.c (ffffffff81537d4d)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_init
```
```
In lib/genalloc.c (ffffffff8154536e)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_add_owner
```
```
In drivers/tty/tty_ldsem.c (ffffffff8169c6f5)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:__init_ldsem
```
```
In net/core/net_namespace.c (ffffffff81936855)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - net/core/net_namespace.c:net_ns_net_init
```
```
In net/unix/af_unix.c (ffffffff81a45f1b)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
```
```
In net/packet/af_packet.c (ffffffff81aa74da)
Location: include/asm-generic/atomic-long.h:38
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
```
</details>
</li>
</ul>

## Differences
