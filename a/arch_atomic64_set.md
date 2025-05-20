# Function: <code>arch_atomic64_set</code>

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
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff810074f5)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_setup_perfctr
```
```
In arch/x86/events/amd/uncore.c (ffffffff81008dd4)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_read
```
```
In arch/x86/events/amd/ibs.c (ffffffff8100a396)
Location: arch/x86/include/asm/atomic64_64.h:32
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
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_event_update
```
```
In arch/x86/events/intel/core.c (ffffffff8100cff8)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_save_and_restart
```
```
In arch/x86/events/intel/bts.c (ffffffff8100d9da)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_update
```
```
In arch/x86/events/intel/ds.c (ffffffff8100e7c1)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pmu_save_and_restart_reload
```
```
In arch/x86/events/intel/pt.c (ffffffff81012579)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_buffer_reset_offsets
  - arch/x86/events/intel/pt.c:pt_buffer_reset_offsets
  - arch/x86/events/intel/pt.c:pt_update_head
```
```
In arch/x86/events/intel/uncore.c (ffffffff81014011)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
```
```
In arch/x86/kernel/pvclock.c (ffffffff8106e640)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - arch/x86/kernel/pvclock.c:pvclock_resume
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff826f2194)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In kernel/fork.c (ffffffff8108ab37)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
  - kernel/fork.c:mm_init
```
```
In kernel/workqueue.c (ffffffff810ac5e1)
Location: arch/x86/include/asm/atomic64_64.h:32
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
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/locking/mutex.c:__mutex_init
```
```
In kernel/locking/rwsem-xadd.c (ffffffff810e6555)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/locking/rwsem-xadd.c:__init_rwsem
```
```
In kernel/acct.c (ffffffff81136011)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/acct.c:acct_on
```
```
In kernel/cgroup/namespace.c (ffffffff8114446c)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
```
```
In kernel/cgroup/pids.c (ffffffff81147017)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_css_alloc
  - kernel/cgroup/pids.c:pids_css_alloc
```
```
In kernel/utsname.c (ffffffff8114c4a9)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/utsname.c:copy_utsname
```
```
In kernel/user_namespace.c (ffffffff8114d729)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In kernel/pid_namespace.c (ffffffff8114e2a6)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In kernel/audit_tree.c (ffffffff81159b16)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/audit_tree.c:alloc_chunk
```
```
In kernel/trace/ring_buffer.c (ffffffff8117bb5d)
Location: arch/x86/include/asm/atomic64_64.h:32
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
In kernel/trace/tracing_map.c (ffffffff8118a2c1)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_clear
  - kernel/trace/tracing_map.c:tracing_map_clear
  - kernel/trace/tracing_map.c:tracing_map_elt_clear
  - kernel/trace/tracing_map.c:tracing_map_elt_clear
  - kernel/trace/tracing_map.c:tracing_map_set_var
```
```
In kernel/events/core.c (ffffffff811d8cc6)
Location: arch/x86/include/asm/atomic64_64.h:32
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
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_aux_output_end
  - kernel/events/ring_buffer.c:perf_aux_output_begin
```
```
In mm/vmstat.c (ffffffff81216826)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
```
```
In mm/swap_state.c (ffffffff81248520)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/slub.c (ffffffff81269de2)
Location: arch/x86/include/asm/atomic64_64.h:32
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
Location: arch/x86/include/asm/atomic64_64.h:32
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
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
```
```
In fs/file_table.c (ffffffff8129b8db)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - fs/file_table.c:get_empty_filp
```
```
In fs/namespace.c (ffffffff812bd4c5)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In fs/nsfs.c (ffffffff812d5999)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - fs/nsfs.c:ns_prune_dentry
```
```
In fs/ext4/inode.c (ffffffff81354ad0)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_iget
```
```
In fs/ext4/ioctl.c (ffffffff8135c43d)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/super.c (ffffffff8138a696)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_alloc_inode
```
```
In fs/ext4/sysfs.c (ffffffff8138bfb9)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_store
```
```
In fs/ext4/xattr.c (ffffffff8138dfcd)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
```
```
In fs/fat/inode.c (ffffffff813aed32)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_build_inode
```
```
In ipc/namespace.c (ffffffff813e35e4)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - ipc/namespace.c:copy_ipcs
```
```
In block/blk-ioc.c (ffffffff814893cb)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - block/blk-ioc.c:create_task_io_context
```
```
In block/blk-cgroup.c (ffffffff814a8c9f)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_reset_stats
  - block/blk-cgroup.c:blkcg_reset_stats
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-cgroup.c:blkg_rwstat_read
```
```
In block/cfq-iosched.c (ffffffff814b0d48)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_pd_alloc
  - block/cfq-iosched.c:cfq_pd_alloc
  - block/cfq-iosched.c:cfq_pd_alloc
  - block/cfq-iosched.c:cfq_pd_alloc
  - block/cfq-iosched.c:cfq_pd_alloc
  - block/cfq-iosched.c:blkg_rwstat_read
```
```
In lib/percpu-refcount.c (ffffffff814cb392)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_init
```
```
In lib/genalloc.c (ffffffff814d5a24)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_add_virt
```
```
In drivers/iommu/iova.c (ffffffff81663ef5)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
```
```
In drivers/md/md.c (ffffffff81800209)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:do_md_stop
```
```
In drivers/firmware/efi/cper.c (ffffffff81848402)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_next_record_id
```
```
In net/core/sock.c (ffffffff81877fad)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
```
```
In net/core/net_namespace.c (ffffffff81886922)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - net/core/net_namespace.c:net_ns_net_init
```
```
In net/ipv4/ip_fragment.c (ffffffff818e899c)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ipv4_frags_init_net
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff818f32d1)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
```
```
In net/ipv4/inet_connection_sock.c (ffffffff818f3f4b)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_clone_lock
```
```
In net/ipv4/tcp_input.c (ffffffff818fcaab)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/unix/af_unix.c (ffffffff81959c2d)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
```
```
In net/ipv6/reassembly.c (ffffffff81990325)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frags_init_net
```
```
In net/packet/af_packet.c (ffffffff819b3abb)
Location: arch/x86/include/asm/atomic64_64.h:32
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
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_setup_perfctr
```
```
In arch/x86/events/amd/uncore.c (ffffffff81008cf4)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_read
```
```
In arch/x86/events/amd/ibs.c (ffffffff8100a2c6)
Location: arch/x86/include/asm/atomic64_64.h:32
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
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_event_update
```
```
In arch/x86/events/intel/core.c (ffffffff8100d3c8)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_save_and_restart
```
```
In arch/x86/events/intel/bts.c (ffffffff8100deaa)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_update
```
```
In arch/x86/events/intel/ds.c (ffffffff8100ec91)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pmu_save_and_restart_reload
```
```
In arch/x86/events/intel/pt.c (ffffffff81012c79)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_buffer_reset_offsets
  - arch/x86/events/intel/pt.c:pt_buffer_reset_offsets
  - arch/x86/events/intel/pt.c:pt_update_head
```
```
In arch/x86/events/intel/uncore.c (ffffffff81014711)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
```
```
In arch/x86/kernel/pvclock.c (ffffffff81074660)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - arch/x86/kernel/pvclock.c:pvclock_resume
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff828a91a4)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In kernel/fork.c (ffffffff81092b3b)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
  - kernel/fork.c:mm_init
```
```
In kernel/workqueue.c (ffffffff810b54c1)
Location: arch/x86/include/asm/atomic64_64.h:32
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
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/locking/mutex.c:__mutex_init
```
```
In kernel/locking/rwsem-xadd.c (ffffffff810f1ad5)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/locking/rwsem-xadd.c:__init_rwsem
```
```
In kernel/acct.c (ffffffff811417a1)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/acct.c:acct_on
```
```
In kernel/cgroup/namespace.c (ffffffff8114ff7c)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
```
```
In kernel/cgroup/pids.c (ffffffff81152b97)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_css_alloc
  - kernel/cgroup/pids.c:pids_css_alloc
```
```
In kernel/utsname.c (ffffffff811590c9)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/utsname.c:copy_utsname
```
```
In kernel/user_namespace.c (ffffffff8115a3e9)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In kernel/pid_namespace.c (ffffffff8115af86)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In kernel/audit_tree.c (ffffffff81166aad)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/audit_tree.c:alloc_chunk
```
```
In kernel/trace/ring_buffer.c (ffffffff81188b31)
Location: arch/x86/include/asm/atomic64_64.h:32
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
In kernel/trace/tracing_map.c (ffffffff81197c21)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_clear
  - kernel/trace/tracing_map.c:tracing_map_clear
  - kernel/trace/tracing_map.c:tracing_map_elt_clear
  - kernel/trace/tracing_map.c:tracing_map_elt_clear
  - kernel/trace/tracing_map.c:tracing_map_set_var
```
```
In kernel/events/core.c (ffffffff811e91c3)
Location: arch/x86/include/asm/atomic64_64.h:32
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
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_aux_output_end
  - kernel/events/ring_buffer.c:perf_aux_output_begin
```
```
In mm/page_alloc.c (ffffffff828b944e)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init_node
  - mm/page_alloc.c:free_area_init_core_hotplug
```
```
In mm/vmstat.c (ffffffff81229729)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
```
```
In mm/memblock.c (ffffffff828be4df)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - mm/memblock.c:reset_all_zones_managed_pages
```
```
In mm/swap_state.c (ffffffff8125caf4)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/slub.c (ffffffff8127e6a2)
Location: arch/x86/include/asm/atomic64_64.h:32
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
Location: arch/x86/include/asm/atomic64_64.h:32
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
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
```
```
In fs/file_table.c (ffffffff812b07ed)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - fs/file_table.c:__alloc_file
```
```
In fs/namespace.c (ffffffff812d27d5)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In fs/nsfs.c (ffffffff812ead69)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - fs/nsfs.c:ns_prune_dentry
```
```
In fs/ext4/inode.c (ffffffff8136ce22)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/ioctl.c (ffffffff813748aa)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/super.c (ffffffff813a303a)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_alloc_inode
```
```
In fs/ext4/sysfs.c (ffffffff813a4b49)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_store
```
```
In fs/ext4/xattr.c (ffffffff813a6568)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
```
```
In fs/fat/inode.c (ffffffff813c7f11)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_build_inode
```
```
In ipc/namespace.c (ffffffff813fdf54)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - ipc/namespace.c:copy_ipcs
```
```
In block/blk-ioc.c (ffffffff814a321b)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - block/blk-ioc.c:create_task_io_context
```
```
In block/blk-cgroup.c (ffffffff814c0af1)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_scale_delay
  - block/blk-cgroup.c:blkcg_reset_stats
  - block/blk-cgroup.c:blkcg_reset_stats
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-cgroup.c:blkg_rwstat_read
```
```
In lib/percpu-refcount.c (ffffffff814e00c2)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_init
```
```
In lib/genalloc.c (ffffffff814ea0af)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_add_virt
```
```
In drivers/tty/tty_ldsem.c (ffffffff81637935)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:__init_ldsem
```
```
In drivers/iommu/iova.c (ffffffff81682785)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
```
```
In drivers/md/md.c (ffffffff8182c3de)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:do_md_stop
```
```
In drivers/firmware/efi/cper.c (ffffffff8187465b)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_next_record_id
  - drivers/firmware/efi/cper.c:cper_next_record_id
```
```
In net/core/sock.c (ffffffff8189848d)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
```
```
In net/core/net_namespace.c (ffffffff818a7012)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - net/core/net_namespace.c:net_ns_net_init
```
```
In net/ipv4/ip_fragment.c (ffffffff81915cec)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ipv4_frags_init_net
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81920df1)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81921a6b)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_clone_lock
```
```
In net/ipv4/tcp_input.c (ffffffff8192ac1d)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/unix/af_unix.c (ffffffff8198e7ae)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
```
```
In net/ipv6/reassembly.c (ffffffff819c6b85)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frags_init_net
```
```
In net/packet/af_packet.c (ffffffff819eaae8)
Location: arch/x86/include/asm/atomic64_64.h:32
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
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_setup_perfctr
```
```
In arch/x86/events/amd/uncore.c (ffffffff81009184)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_read
```
```
In arch/x86/events/amd/ibs.c (ffffffff8100a7b7)
Location: arch/x86/include/asm/atomic64_64.h:32
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
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_event_update
```
```
In arch/x86/events/intel/core.c (ffffffff8100dc5e)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_save_and_restart
```
```
In arch/x86/events/intel/bts.c (ffffffff8100e779)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_update
```
```
In arch/x86/events/intel/ds.c (ffffffff8100f589)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pmu_save_and_restart_reload
```
```
In arch/x86/events/intel/pt.c (ffffffff81014019)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_buffer_reset_offsets
  - arch/x86/events/intel/pt.c:pt_buffer_reset_offsets
  - arch/x86/events/intel/pt.c:pt_update_head
```
```
In arch/x86/events/intel/uncore.c (ffffffff81015b91)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
```
```
In arch/x86/kernel/pvclock.c (ffffffff810781c0)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - arch/x86/kernel/pvclock.c:pvclock_resume
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff828c198b)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In kernel/fork.c (ffffffff81096b1d)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
  - kernel/fork.c:mm_init
  - kernel/fork.c:mm_init
```
```
In kernel/workqueue.c (ffffffff810bcfc0)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/workqueue.c:insert_work
  - kernel/workqueue.c:set_work_pool_and_clear_pending
```
```
In kernel/locking/mutex.c (ffffffff810f76d5)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/locking/mutex.c:__mutex_init
```
```
In kernel/locking/rwsem.c (ffffffff810f7db5)
Location: arch/x86/include/asm/atomic64_64.h:32
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
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/acct.c:acct_on
```
```
In kernel/cgroup/namespace.c (ffffffff8115be7c)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
```
```
In kernel/cgroup/pids.c (ffffffff8115f1da)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_css_alloc
  - kernel/cgroup/pids.c:pids_css_alloc
```
```
In kernel/utsname.c (ffffffff811657fe)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/utsname.c:copy_utsname
```
```
In kernel/user_namespace.c (ffffffff81166ab7)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In kernel/pid_namespace.c (ffffffff81167636)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In kernel/audit_tree.c (ffffffff81173a0d)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/audit_tree.c:alloc_chunk
```
```
In kernel/trace/ring_buffer.c (ffffffff8119629c)
Location: arch/x86/include/asm/atomic64_64.h:32
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
In kernel/trace/tracing_map.c (ffffffff811a5801)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_clear
  - kernel/trace/tracing_map.c:tracing_map_clear
  - kernel/trace/tracing_map.c:tracing_map_elt_clear
  - kernel/trace/tracing_map.c:tracing_map_elt_clear
  - kernel/trace/tracing_map.c:tracing_map_set_var
```
```
In kernel/events/core.c (ffffffff812024d8)
Location: arch/x86/include/asm/atomic64_64.h:32
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
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
```
```
In mm/vmalloc.c (ffffffff812686a3)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - mm/vmalloc.c:set_iounmap_nonlazy
```
```
In mm/page_alloc.c (ffffffff828d6545)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init_node
  - mm/page_alloc.c:free_area_init_core_hotplug
```
```
In mm/memblock.c (ffffffff828d76ad)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - mm/memblock.c:reset_all_zones_managed_pages
```
```
In mm/swap_state.c (ffffffff81277cda)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/slub.c (ffffffff8129a571)
Location: arch/x86/include/asm/atomic64_64.h:32
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
Location: arch/x86/include/asm/atomic64_64.h:32
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
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
```
```
In fs/file_table.c (ffffffff812cd131)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - fs/file_table.c:__alloc_file
```
```
In fs/super.c (ffffffff812ce3c3)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - fs/super.c:thaw_super_locked
  - fs/super.c:thaw_super_locked
  - fs/super.c:freeze_super
```
```
In fs/namespace.c (ffffffff812efa32)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In fs/nsfs.c (ffffffff813097d9)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - fs/nsfs.c:ns_prune_dentry
```
```
In fs/aio.c (0)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
```
```
In fs/io_uring.c (0)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
```
```
In fs/ext4/inode.c (ffffffff813963cf)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/ioctl.c (ffffffff8139d386)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/super.c (ffffffff813cd270)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_alloc_inode
```
```
In fs/ext4/sysfs.c (ffffffff813cee0f)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_store
```
```
In fs/ext4/xattr.c (ffffffff813d0dc5)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
```
```
In fs/fat/inode.c (ffffffff813f2afa)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_build_inode
```
```
In fs/fuse/inode.c (ffffffff81412d54)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_conn_init
  - fs/fuse/inode.c:fuse_conn_init
```
```
In ipc/namespace.c (ffffffff8142a584)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - ipc/namespace.c:copy_ipcs
```
```
In block/blk-ioc.c (ffffffff814d12d6)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - block/blk-ioc.c:create_task_io_context
```
```
In block/blk-cgroup.c (ffffffff814ef340)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_scale_delay
  - block/blk-cgroup.c:blkcg_reset_stats
  - block/blk-cgroup.c:blkcg_reset_stats
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-cgroup.c:blkg_alloc
```
```
In lib/percpu-refcount.c (ffffffff8150c01d)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_init
```
```
In lib/genalloc.c (ffffffff81516d6e)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_add_owner
```
```
In drivers/tty/tty_ldsem.c (ffffffff8166bc05)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:__init_ldsem
```
```
In drivers/iommu/iova.c (ffffffff816b9b35)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - drivers/iommu/iova.c:init_iova_flush_queue
  - drivers/iommu/iova.c:init_iova_flush_queue
```
```
In drivers/md/md.c (ffffffff8186e988)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:do_md_stop
```
```
In drivers/firmware/efi/cper.c (ffffffff818b88bb)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_next_record_id
  - drivers/firmware/efi/cper.c:cper_next_record_id
```
```
In net/core/net_namespace.c (ffffffff818f2712)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - net/core/net_namespace.c:net_ns_net_init
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff819837b9)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81984424)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_clone_lock
```
```
In net/ipv4/tcp_input.c (ffffffff8198de79)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/unix/af_unix.c (ffffffff819f9f0b)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
```
```
In net/packet/af_packet.c (ffffffff81a59437)
Location: arch/x86/include/asm/atomic64_64.h:32
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
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_setup_perfctr
```
```
In arch/x86/events/amd/uncore.c (ffffffff81009584)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_read
```
```
In arch/x86/events/amd/ibs.c (ffffffff8100ad86)
Location: arch/x86/include/asm/atomic64_64.h:32
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
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_event_update
```
```
In arch/x86/events/intel/core.c (ffffffff8100e29e)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_save_and_restart
```
```
In arch/x86/events/intel/bts.c (ffffffff8100ec49)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_update
```
```
In arch/x86/events/intel/ds.c (ffffffff8100fc51)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pmu_save_and_restart_reload
  - arch/x86/events/intel/ds.c:intel_pmu_save_and_restart_reload
```
```
In arch/x86/events/intel/pt.c (ffffffff81014ac0)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_buffer_reset_offsets
  - arch/x86/events/intel/pt.c:pt_buffer_reset_offsets
  - arch/x86/events/intel/pt.c:pt_update_head
```
```
In arch/x86/events/intel/uncore.c (ffffffff81016551)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
```
```
In arch/x86/kernel/pvclock.c (ffffffff81079230)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - arch/x86/kernel/pvclock.c:pvclock_resume
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff828c7e04)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff810991fa)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:param_set_local64
```
```
In kernel/fork.c (ffffffff8109d35d)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
  - kernel/fork.c:mm_init
  - kernel/fork.c:mm_init
```
```
In kernel/workqueue.c (ffffffff810c1541)
Location: arch/x86/include/asm/atomic64_64.h:32
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
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/locking/mutex.c:__mutex_init
```
```
In kernel/locking/rwsem.c (ffffffff81103be5)
Location: arch/x86/include/asm/atomic64_64.h:32
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
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/acct.c:acct_on
```
```
In kernel/cgroup/namespace.c (ffffffff81167a9c)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
```
```
In kernel/cgroup/pids.c (ffffffff8116aa39)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_max_write
  - kernel/cgroup/pids.c:pids_css_alloc
  - kernel/cgroup/pids.c:pids_css_alloc
  - kernel/cgroup/pids.c:pids_css_alloc
```
```
In kernel/utsname.c (ffffffff811716be)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/utsname.c:copy_utsname
```
```
In kernel/user_namespace.c (ffffffff81172977)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In kernel/pid_namespace.c (ffffffff811734f6)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In kernel/audit_tree.c (ffffffff8117f87d)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/audit_tree.c:alloc_chunk
```
```
In kernel/trace/ring_buffer.c (ffffffff811a1c6c)
Location: arch/x86/include/asm/atomic64_64.h:32
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
In kernel/trace/tracing_map.c (ffffffff811b1031)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_clear
  - kernel/trace/tracing_map.c:tracing_map_clear
  - kernel/trace/tracing_map.c:tracing_map_elt_clear
  - kernel/trace/tracing_map.c:tracing_map_elt_clear
  - kernel/trace/tracing_map.c:tracing_map_set_var
```
```
In kernel/events/core.c (ffffffff8120f308)
Location: arch/x86/include/asm/atomic64_64.h:32
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
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
```
```
In mm/vmalloc.c (ffffffff81276ff3)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - mm/vmalloc.c:set_iounmap_nonlazy
```
```
In mm/page_alloc.c (ffffffff828de9d4)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init_node
  - mm/page_alloc.c:free_area_init_core_hotplug
```
```
In mm/memblock.c (ffffffff828dfb1e)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - mm/memblock.c:reset_all_zones_managed_pages
```
```
In mm/swap_state.c (ffffffff812877ca)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/slub.c (ffffffff812aa431)
Location: arch/x86/include/asm/atomic64_64.h:32
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
Location: arch/x86/include/asm/atomic64_64.h:32
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
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
```
```
In fs/file_table.c (ffffffff812deb51)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - fs/file_table.c:__alloc_file
```
```
In fs/super.c (ffffffff812dfe73)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - fs/super.c:thaw_super_locked
  - fs/super.c:thaw_super_locked
  - fs/super.c:freeze_super
```
```
In fs/inode.c (ffffffff812fba8a)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - fs/inode.c:inode_init_always
```
```
In fs/namespace.c (ffffffff81301502)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In fs/nsfs.c (ffffffff8131c849)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - fs/nsfs.c:ns_prune_dentry
```
```
In fs/aio.c (0)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
```
```
In fs/io_uring.c (0)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
```
```
In fs/ext4/inode.c (ffffffff813aedd1)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/ioctl.c (ffffffff813b5df6)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/super.c (ffffffff813e674c)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_alloc_inode
```
```
In fs/ext4/sysfs.c (ffffffff813e84df)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_store
```
```
In fs/ext4/xattr.c (ffffffff813ea495)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
```
```
In fs/fat/inode.c (ffffffff8140cabb)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_build_inode
```
```
In fs/fuse/inode.c (ffffffff8142ca44)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_conn_init
  - fs/fuse/inode.c:fuse_conn_init
```
```
In ipc/namespace.c (ffffffff814442b4)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - ipc/namespace.c:copy_ipcs
```
```
In block/blk-ioc.c (ffffffff814ea686)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - block/blk-ioc.c:create_task_io_context
```
```
In block/blk-cgroup.c (ffffffff815087d0)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_scale_delay
  - block/blk-cgroup.c:blkcg_reset_stats
  - block/blk-cgroup.c:blkcg_reset_stats
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-cgroup.c:blkg_alloc
```
```
In block/blk-iocost.c (ffffffff81510aa4)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_pd_init
  - block/blk-iocost.c:ioc_pd_init
  - block/blk-iocost.c:ioc_pd_init
  - block/blk-iocost.c:ioc_pd_init
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:iocg_kick_waitq
  - block/blk-iocost.c:ioc_refresh_params
```
```
In lib/percpu-refcount.c (ffffffff81529e6d)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_init
```
```
In lib/genalloc.c (ffffffff815377ae)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_add_owner
```
```
In drivers/tty/tty_ldsem.c (ffffffff8168e275)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:__init_ldsem
```
```
In drivers/iommu/iova.c (ffffffff816dc925)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - drivers/iommu/iova.c:init_iova_flush_queue
  - drivers/iommu/iova.c:init_iova_flush_queue
```
```
In drivers/md/md.c (ffffffff818a0765)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:do_md_stop
```
```
In drivers/firmware/efi/cper.c (ffffffff818eb2bb)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_next_record_id
  - drivers/firmware/efi/cper.c:cper_next_record_id
```
```
In net/core/net_namespace.c (ffffffff81924675)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - net/core/net_namespace.c:net_ns_net_init
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff819b9fa9)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819babd4)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_clone_lock
```
```
In net/ipv4/tcp_input.c (ffffffff819c4a49)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/unix/af_unix.c (ffffffff81a30b8b)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
```
```
In net/packet/af_packet.c (ffffffff81a8f547)
Location: arch/x86/include/asm/atomic64_64.h:32
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
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_setup_perfctr
```
```
In arch/x86/events/amd/uncore.c (ffffffff8100a734)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_read
```
```
In arch/x86/events/amd/ibs.c (ffffffff8100c000)
Location: arch/x86/include/asm/atomic64_64.h:32
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
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_event_update
```
```
In arch/x86/events/intel/core.c (ffffffff8100f5d0)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:handle_pmi_common
```
```
In arch/x86/events/intel/bts.c (ffffffff8100fff9)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_update
```
```
In arch/x86/events/intel/ds.c (ffffffff810112b1)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
```
```
In arch/x86/events/intel/pt.c (ffffffff81015f91)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_buffer_reset_offsets
  - arch/x86/events/intel/pt.c:pt_buffer_reset_offsets
  - arch/x86/events/intel/pt.c:pt_update_head
  - arch/x86/events/intel/pt.c:pt_update_head
```
```
In arch/x86/events/intel/uncore.c (ffffffff81018aa1)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
```
```
In arch/x86/kernel/pvclock.c (ffffffff81080510)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - arch/x86/kernel/pvclock.c:pvclock_resume
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff82ceac4a)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff8109e88a)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:param_set_local64
```
```
In kernel/fork.c (ffffffff810a41bd)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
  - kernel/fork.c:mm_init
  - kernel/fork.c:mm_init
```
```
In kernel/workqueue.c (ffffffff810ca9a1)
Location: arch/x86/include/asm/atomic64_64.h:32
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
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/locking/mutex.c:__mutex_init
```
```
In kernel/locking/rwsem.c (ffffffff8110e775)
Location: arch/x86/include/asm/atomic64_64.h:32
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
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/time/namespace.c:clone_time_ns
```
```
In kernel/acct.c (ffffffff81168e2e)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/acct.c:acct_on
```
```
In kernel/cgroup/namespace.c (ffffffff811793f7)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
```
```
In kernel/cgroup/pids.c (ffffffff8117c579)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_max_write
  - kernel/cgroup/pids.c:pids_css_alloc
  - kernel/cgroup/pids.c:pids_css_alloc
  - kernel/cgroup/pids.c:pids_css_alloc
```
```
In kernel/utsname.c (ffffffff811832eb)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/utsname.c:clone_uts_ns
```
```
In kernel/user_namespace.c (ffffffff811847d7)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In kernel/pid_namespace.c (ffffffff81184fd8)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/pid_namespace.c:create_pid_namespace
```
```
In kernel/audit_tree.c (ffffffff81192a61)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/audit_tree.c:alloc_chunk
```
```
In kernel/trace/ring_buffer.c (ffffffff811b7d8b)
Location: arch/x86/include/asm/atomic64_64.h:32
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
In kernel/trace/tracing_map.c (ffffffff811c95b5)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_clear
  - kernel/trace/tracing_map.c:tracing_map_clear
  - kernel/trace/tracing_map.c:tracing_map_elt_clear
  - kernel/trace/tracing_map.c:tracing_map_elt_clear
  - kernel/trace/tracing_map.c:tracing_map_set_var
```
```
In kernel/bpf/syscall.c (ffffffff8120102d)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_raw_tracepoint_open
  - kernel/bpf/syscall.c:bpf_raw_tracepoint_open
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:map_create
```
```
In kernel/events/core.c (ffffffff8123a4e5)
Location: arch/x86/include/asm/atomic64_64.h:32
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
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
```
```
In mm/vmalloc.c (ffffffff812abb63)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - mm/vmalloc.c:set_iounmap_nonlazy
```
```
In mm/page_alloc.c (ffffffff82cfb900)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init_core
  - mm/page_alloc.c:free_area_init_core_hotplug
```
```
In mm/memblock.c (ffffffff82cfd0dc)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - mm/memblock.c:reset_all_zones_managed_pages
```
```
In mm/swap_state.c (ffffffff812b89cf)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - mm/swap_state.c:swap_ra_info
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/slub.c (ffffffff812df144)
Location: arch/x86/include/asm/atomic64_64.h:32
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
Location: arch/x86/include/asm/atomic64_64.h:32
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
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
```
```
In fs/file_table.c (ffffffff813159a1)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - fs/file_table.c:__alloc_file
```
```
In fs/inode.c (ffffffff8133482a)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - fs/inode.c:inode_init_always
```
```
In fs/namespace.c (ffffffff8133abcf)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In fs/nsfs.c (ffffffff81356599)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - fs/nsfs.c:ns_prune_dentry
```
```
In fs/ext4/inode.c (ffffffff813fae54)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/ioctl.c (ffffffff814017f8)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/super.c (ffffffff8143383e)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_alloc_inode
```
```
In fs/ext4/sysfs.c (ffffffff81435527)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_store
```
```
In fs/ext4/xattr.c (ffffffff814361a1)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_create
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
```
```
In fs/fat/inode.c (ffffffff8145aa20)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_build_inode
```
```
In fs/fuse/inode.c (ffffffff8147d49d)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_conn_init
  - fs/fuse/inode.c:fuse_conn_init
```
```
In ipc/namespace.c (ffffffff81494ee5)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
```
```
In block/blk-ioc.c (ffffffff81549626)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - block/blk-ioc.c:create_task_io_context
```
```
In block/blk-cgroup.c (ffffffff81569aea)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_scale_delay
```
```
In block/blk-cgroup-rwstat.c (ffffffff8156c164)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - block/blk-cgroup-rwstat.c:blkg_rwstat_init
```
```
In block/blk-iocost.c (ffffffff81572594)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_pd_init
  - block/blk-iocost.c:ioc_pd_init
  - block/blk-iocost.c:ioc_pd_init
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:iocg_kick_delay
  - block/blk-iocost.c:iocg_activate
  - block/blk-iocost.c:iocg_activate
```
```
In lib/percpu-refcount.c (ffffffff8158d760)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_init
```
```
In lib/genalloc.c (ffffffff8159b8ae)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_add_owner
```
```
In drivers/tty/tty_ldsem.c (ffffffff81740535)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:__init_ldsem
```
```
In drivers/iommu/iova.c (ffffffff81793505)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - drivers/iommu/iova.c:init_iova_flush_queue
  - drivers/iommu/iova.c:init_iova_flush_queue
```
```
In drivers/iommu/amd/iommu.c (ffffffff81799cf7)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_direct_map
  - drivers/iommu/amd/iommu.c:protection_domain_alloc
  - drivers/iommu/amd/iommu.c:protection_domain_free
  - drivers/iommu/amd/iommu.c:increase_address_space
```
```
In drivers/md/md.c (ffffffff81970451)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:do_md_stop
```
```
In drivers/firmware/efi/cper.c (ffffffff819be9af)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_next_record_id
  - drivers/firmware/efi/cper.c:cper_next_record_id
```
```
In net/core/net_namespace.c (ffffffff819f7eb5)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - net/core/net_namespace.c:net_ns_net_init
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81aa4a29)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81aa5466)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_clone_lock
```
```
In net/ipv4/tcp_input.c (ffffffff81ab0b56)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/unix/af_unix.c (ffffffff81b24dbb)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
```
```
In net/packet/af_packet.c (ffffffff81b8a274)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - net/packet/af_packet.c:fanout_add
  - net/packet/af_packet.c:fanout_add
  - net/packet/af_packet.c:fanout_add
```
```
In net/mptcp/protocol.c (ffffffff81bad9a2)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_finish_connect
  - net/mptcp/protocol.c:mptcp_sk_clone
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
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_setup_perfctr
```
```
In arch/x86/events/amd/uncore.c (ffffffff81009594)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_read
```
```
In arch/x86/events/amd/ibs.c (ffffffff8100afb5)
Location: arch/x86/include/asm/atomic64_64.h:32
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
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_event_update
```
```
In arch/x86/events/intel/core.c (ffffffff8100ebf1)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:handle_pmi_common
```
```
In arch/x86/events/intel/bts.c (ffffffff8100f559)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_update
```
```
In arch/x86/events/intel/ds.c (ffffffff810108e1)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
```
```
In arch/x86/events/intel/pt.c (ffffffff81016431)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_buffer_reset_offsets
  - arch/x86/events/intel/pt.c:pt_buffer_reset_offsets
  - arch/x86/events/intel/pt.c:pt_update_head
  - arch/x86/events/intel/pt.c:pt_update_head
```
```
In arch/x86/events/intel/uncore.c (ffffffff81019221)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
```
```
In arch/x86/kernel/pvclock.c (ffffffff81080120)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - arch/x86/kernel/pvclock.c:pvclock_resume
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff82fd8495)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff8109a46a)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:param_set_local64
```
```
In kernel/fork.c (ffffffff8109fdd1)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
  - kernel/fork.c:mm_init
  - kernel/fork.c:mm_init
```
```
In kernel/workqueue.c (ffffffff810c5ad1)
Location: arch/x86/include/asm/atomic64_64.h:32
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
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/locking/mutex.c:__mutex_init
```
```
In kernel/locking/rwsem.c (ffffffff8110b9f5)
Location: arch/x86/include/asm/atomic64_64.h:32
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
Location: arch/x86/include/asm/atomic64_64.h:32
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
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/time/namespace.c:clone_time_ns
```
```
In kernel/acct.c (ffffffff811654be)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/acct.c:acct_on
```
```
In kernel/cgroup/namespace.c (ffffffff8117610b)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
```
```
In kernel/cgroup/pids.c (ffffffff81179429)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_max_write
  - kernel/cgroup/pids.c:pids_css_alloc
  - kernel/cgroup/pids.c:pids_css_alloc
  - kernel/cgroup/pids.c:pids_css_alloc
```
```
In kernel/utsname.c (ffffffff811801df)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/utsname.c:clone_uts_ns
```
```
In kernel/user_namespace.c (ffffffff81181827)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In kernel/pid_namespace.c (ffffffff81182147)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/pid_namespace.c:create_pid_namespace
```
```
In kernel/audit_tree.c (ffffffff8118fbbc)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/audit_tree.c:alloc_chunk
```
```
In kernel/trace/ring_buffer.c (ffffffff811b594b)
Location: arch/x86/include/asm/atomic64_64.h:32
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
In kernel/trace/tracing_map.c (ffffffff811c6c75)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_clear
  - kernel/trace/tracing_map.c:tracing_map_clear
  - kernel/trace/tracing_map.c:tracing_map_elt_clear
  - kernel/trace/tracing_map.c:tracing_map_elt_clear
  - kernel/trace/tracing_map.c:tracing_map_set_var
```
```
In kernel/bpf/syscall.c (ffffffff81200a1d)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_raw_tracepoint_open
  - kernel/bpf/syscall.c:bpf_tracing_prog_attach
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:map_create
```
```
In kernel/events/core.c (ffffffff8124390a)
Location: arch/x86/include/asm/atomic64_64.h:32
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
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
```
```
In mm/vmalloc.c (ffffffff812b7083)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - mm/vmalloc.c:set_iounmap_nonlazy
```
```
In mm/page_alloc.c (ffffffff82fe83a7)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init_core
  - mm/page_alloc.c:free_area_init_core_hotplug
```
```
In mm/memblock.c (ffffffff82fe9b0d)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - mm/memblock.c:reset_all_zones_managed_pages
```
```
In mm/swap_state.c (ffffffff812c4e6c)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/slub.c (ffffffff812eaf16)
Location: arch/x86/include/asm/atomic64_64.h:32
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
Location: arch/x86/include/asm/atomic64_64.h:32
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
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
```
```
In fs/file_table.c (ffffffff81320efd)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - fs/file_table.c:__alloc_file
```
```
In fs/inode.c (ffffffff8134017f)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - fs/inode.c:inode_init_always
```
```
In fs/namespace.c (ffffffff81346dfc)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In fs/nsfs.c (ffffffff81362f39)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - fs/nsfs.c:ns_prune_dentry
```
```
In fs/ext4/inode.c (ffffffff8140d4de)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/ioctl.c (ffffffff814141f3)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/super.c (ffffffff8144c9a8)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_alloc_inode
```
```
In fs/ext4/sysfs.c (ffffffff8144df64)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_store
```
```
In fs/ext4/xattr.c (ffffffff8144ebe1)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_create
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
```
```
In fs/fat/inode.c (ffffffff81476d70)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_build_inode
```
```
In fs/fuse/inode.c (ffffffff8149884b)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_conn_init
  - fs/fuse/inode.c:fuse_conn_init
```
```
In ipc/namespace.c (ffffffff814b2875)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
```
```
In block/blk-ioc.c (ffffffff81565456)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - block/blk-ioc.c:create_task_io_context
```
```
In block/blk-cgroup.c (ffffffff8158439a)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_scale_delay
```
```
In block/blk-cgroup-rwstat.c (ffffffff81586f04)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - block/blk-cgroup-rwstat.c:blkg_rwstat_init
```
```
In block/blk-iocost.c (ffffffff8158e544)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_pd_init
  - block/blk-iocost.c:ioc_pd_init
  - block/blk-iocost.c:ioc_pd_init
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:iocg_kick_delay
  - block/blk-iocost.c:iocg_activate
  - block/blk-iocost.c:iocg_activate
```
```
In lib/percpu-refcount.c (ffffffff815aa297)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_init
```
```
In lib/genalloc.c (ffffffff815b714a)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_add_owner
```
```
In drivers/tty/tty_ldsem.c (ffffffff8175c465)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:__init_ldsem
```
```
In drivers/iommu/amd/iommu.c (ffffffff817a8427)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_direct_map
  - drivers/iommu/amd/iommu.c:protection_domain_alloc
  - drivers/iommu/amd/iommu.c:protection_domain_free
  - drivers/iommu/amd/iommu.c:increase_address_space
```
```
In drivers/iommu/iova.c (ffffffff817bfe55)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - drivers/iommu/iova.c:init_iova_flush_queue
  - drivers/iommu/iova.c:init_iova_flush_queue
```
```
In drivers/md/md.c (ffffffff81c2654a)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:do_md_stop
```
```
In drivers/firmware/efi/cper.c (ffffffff819c035f)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_next_record_id
  - drivers/firmware/efi/cper.c:cper_next_record_id
```
```
In net/core/net_namespace.c (ffffffff819f7905)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - net/core/net_namespace.c:net_ns_net_init
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81aaf089)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81aafa66)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_clone_lock
```
```
In net/ipv4/tcp_input.c (ffffffff81abbba6)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/unix/af_unix.c (ffffffff81b3394b)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
```
```
In net/packet/af_packet.c (ffffffff81b9a7c8)
Location: arch/x86/include/asm/atomic64_64.h:32
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
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_setup_perfctr
```
```
In arch/x86/events/amd/uncore.c (ffffffff81009f64)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_read
```
```
In arch/x86/events/amd/ibs.c (ffffffff8100b95e)
Location: arch/x86/include/asm/atomic64_64.h:32
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
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_event_update
```
```
In arch/x86/events/intel/core.c (ffffffff8100efca)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:handle_pmi_common
```
```
In arch/x86/events/intel/bts.c (ffffffff810105ac)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_update
```
```
In arch/x86/events/intel/ds.c (ffffffff81011881)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
```
```
In arch/x86/events/intel/pt.c (ffffffff81017728)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_buffer_reset_offsets
  - arch/x86/events/intel/pt.c:pt_buffer_reset_offsets
  - arch/x86/events/intel/pt.c:pt_update_head
  - arch/x86/events/intel/pt.c:pt_update_head
```
```
In arch/x86/events/intel/uncore.c (ffffffff8101a541)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
```
```
In arch/x86/kernel/pvclock.c (ffffffff81080fb0)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - arch/x86/kernel/pvclock.c:pvclock_resume
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff831e2e8b)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff8109ac2a)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:param_set_local64
```
```
In kernel/fork.c (ffffffff810a0ae4)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
  - kernel/fork.c:mm_init
  - kernel/fork.c:mm_init
```
```
In kernel/workqueue.c (ffffffff810c7400)
Location: arch/x86/include/asm/atomic64_64.h:32
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
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/locking/mutex.c:__mutex_init
```
```
In kernel/locking/rwsem.c (ffffffff8110d815)
Location: arch/x86/include/asm/atomic64_64.h:32
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
In kernel/printk/printk.c (ffffffff81119396)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/printk/printk.c:devkmsg_open
  - kernel/printk/printk.c:devkmsg_llseek
  - kernel/printk/printk.c:devkmsg_llseek
  - kernel/printk/printk.c:devkmsg_llseek
  - kernel/printk/printk.c:devkmsg_read
  - kernel/printk/printk.c:devkmsg_read
```
```
In kernel/printk/printk_ringbuffer.c (ffffffff8111d67c)
Location: arch/x86/include/asm/atomic64_64.h:32
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
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/time/namespace.c:copy_time_ns
```
```
In kernel/acct.c (ffffffff8116628e)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/acct.c:acct_on
```
```
In kernel/cgroup/namespace.c (ffffffff81176c83)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
```
```
In kernel/cgroup/pids.c (ffffffff81179f86)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_max_write
  - kernel/cgroup/pids.c:pids_css_alloc
  - kernel/cgroup/pids.c:pids_css_alloc
  - kernel/cgroup/pids.c:pids_css_alloc
```
```
In kernel/cgroup/misc.c (ffffffff81181104)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/cgroup/misc.c:misc_cg_alloc
```
```
In kernel/utsname.c (ffffffff811813c4)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/utsname.c:copy_utsname
```
```
In kernel/user_namespace.c (ffffffff8118298d)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In kernel/pid_namespace.c (ffffffff81183297)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/pid_namespace.c:create_pid_namespace
```
```
In kernel/audit_tree.c (ffffffff81190b05)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/audit_tree.c:alloc_chunk
```
```
In kernel/trace/ring_buffer.c (ffffffff811b722d)
Location: arch/x86/include/asm/atomic64_64.h:32
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
In kernel/trace/tracing_map.c (ffffffff811c7c65)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_clear
  - kernel/trace/tracing_map.c:tracing_map_clear
  - kernel/trace/tracing_map.c:tracing_map_elt_clear
  - kernel/trace/tracing_map.c:tracing_map_elt_clear
  - kernel/trace/tracing_map.c:tracing_map_set_var
```
```
In kernel/bpf/syscall.c (ffffffff8120143d)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_raw_tracepoint_open
  - kernel/bpf/syscall.c:bpf_tracing_prog_attach
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:map_create
```
```
In kernel/events/core.c (ffffffff812488b2)
Location: arch/x86/include/asm/atomic64_64.h:32
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
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
```
```
In mm/vmalloc.c (ffffffff812bc983)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - mm/vmalloc.c:set_iounmap_nonlazy
```
```
In mm/page_alloc.c (ffffffff831f3120)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init_node
  - mm/page_alloc.c:free_area_init_core_hotplug
```
```
In mm/memblock.c (ffffffff831f41b6)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - mm/memblock.c:reset_all_zones_managed_pages
```
```
In mm/swap_state.c (ffffffff812cbb09)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/slub.c (ffffffff812f29d2)
Location: arch/x86/include/asm/atomic64_64.h:32
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
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_cancel
```
```
In mm/memcontrol.c (ffffffff81c2dbef)
Location: arch/x86/include/asm/atomic64_64.h:32
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
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
```
```
In fs/file_table.c (ffffffff81326ffd)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - fs/file_table.c:__alloc_file
```
```
In fs/inode.c (ffffffff813466a5)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - fs/inode.c:inode_init_always
```
```
In fs/namespace.c (ffffffff8134d2fc)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In fs/nsfs.c (ffffffff813699d9)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - fs/nsfs.c:ns_prune_dentry
```
```
In fs/ext4/inode.c (ffffffff8141374e)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/ioctl.c (ffffffff8141a465)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/super.c (ffffffff814524d8)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_alloc_inode
```
```
In fs/ext4/sysfs.c (ffffffff81453a20)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_store
```
```
In fs/ext4/xattr.c (ffffffff81455a3e)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
```
```
In fs/fat/inode.c (ffffffff8147c7e4)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_build_inode
```
```
In fs/fuse/inode.c (ffffffff8149d8db)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_conn_init
  - fs/fuse/inode.c:fuse_conn_init
```
```
In ipc/namespace.c (ffffffff814b8ad2)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - ipc/namespace.c:copy_ipcs
```
```
In block/blk-ioc.c (ffffffff8156dac6)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - block/blk-ioc.c:create_task_io_context
```
```
In block/blk-cgroup.c (ffffffff8158b19d)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_scale_delay
```
```
In block/blk-cgroup-rwstat.c (ffffffff8158dd54)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - block/blk-cgroup-rwstat.c:blkg_rwstat_init
```
```
In block/blk-iocost.c (ffffffff815952a4)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_pd_init
  - block/blk-iocost.c:ioc_pd_init
  - block/blk-iocost.c:ioc_pd_init
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:iocg_kick_delay
  - block/blk-iocost.c:iocg_activate
  - block/blk-iocost.c:iocg_activate
```
```
In lib/percpu-refcount.c (ffffffff815b4e97)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_init
```
```
In lib/genalloc.c (ffffffff815c1fba)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_add_owner
```
```
In drivers/tty/tty_ldsem.c (ffffffff81740305)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:__init_ldsem
```
```
In drivers/iommu/amd/io_pgtable.c (ffffffff8178bef9)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
```
```
In drivers/iommu/iova.c (ffffffff817a3c45)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - drivers/iommu/iova.c:init_iova_flush_queue
  - drivers/iommu/iova.c:init_iova_flush_queue
```
```
In drivers/md/md.c (ffffffff81c1871b)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:do_md_stop
```
```
In drivers/firmware/efi/cper.c (ffffffff819a4a6f)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_next_record_id
  - drivers/firmware/efi/cper.c:cper_next_record_id
```
```
In net/core/net_namespace.c (ffffffff819dda85)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - net/core/net_namespace.c:net_ns_net_init
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81a9a397)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81a9ad76)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_clone_lock
```
```
In net/ipv4/tcp_input.c (ffffffff81aa6b66)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/nexthop.c (ffffffff81af3edb)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_res_grp_activity_update
  - net/ipv4/nexthop.c:nh_res_table_upkeep
  - net/ipv4/nexthop.c:nh_res_bucket_migrate
```
```
In net/unix/af_unix.c (ffffffff81b2134c)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
```
```
In net/packet/af_packet.c (ffffffff81b89738)
Location: arch/x86/include/asm/atomic64_64.h:32
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
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_setup_perfctr
```
```
In arch/x86/events/amd/ibs.c (ffffffff8100be6c)
Location: arch/x86/include/asm/atomic64_64.h:32
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
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_event_update
```
```
In arch/x86/events/intel/core.c (ffffffff8100fb14)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:handle_pmi_common
```
```
In arch/x86/events/intel/bts.c (ffffffff810112ee)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_update
```
```
In arch/x86/events/intel/ds.c (ffffffff81012745)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
```
```
In arch/x86/events/intel/pt.c (ffffffff8101a8ea)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_buffer_reset_offsets
  - arch/x86/events/intel/pt.c:pt_buffer_reset_offsets
  - arch/x86/events/intel/pt.c:pt_update_head
```
```
In arch/x86/events/intel/uncore.c (ffffffff8101ceaf)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
```
```
In arch/x86/kernel/pvclock.c (ffffffff8108ff40)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - arch/x86/kernel/pvclock.c:pvclock_resume
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff832c682e)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff810aaeba)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:param_set_local64
```
```
In kernel/fork.c (ffffffff810b1f47)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
  - kernel/fork.c:mm_init
  - kernel/fork.c:mm_init
  - kernel/fork.c:mm_init
```
```
In kernel/workqueue.c (ffffffff810da120)
Location: arch/x86/include/asm/atomic64_64.h:32
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
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/locking/mutex.c:__mutex_init
```
```
In kernel/locking/rwsem.c (ffffffff8112d075)
Location: arch/x86/include/asm/atomic64_64.h:32
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
In kernel/printk/printk.c (ffffffff8113974a)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/printk/printk.c:devkmsg_open
  - kernel/printk/printk.c:devkmsg_llseek
  - kernel/printk/printk.c:devkmsg_llseek
  - kernel/printk/printk.c:devkmsg_llseek
  - kernel/printk/printk.c:devkmsg_read
  - kernel/printk/printk.c:devkmsg_read
```
```
In kernel/printk/printk_ringbuffer.c (ffffffff8113d9f1)
Location: arch/x86/include/asm/atomic64_64.h:32
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
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/time/namespace.c:copy_time_ns
```
```
In kernel/acct.c (ffffffff8118ba4e)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/acct.c:acct_on
```
```
In kernel/cgroup/namespace.c (ffffffff8119e503)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
```
```
In kernel/cgroup/pids.c (ffffffff811a18a6)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_max_write
  - kernel/cgroup/pids.c:pids_css_alloc
  - kernel/cgroup/pids.c:pids_css_alloc
  - kernel/cgroup/pids.c:pids_css_alloc
```
```
In kernel/cgroup/misc.c (ffffffff811a9044)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/cgroup/misc.c:misc_cg_alloc
```
```
In kernel/utsname.c (ffffffff811a9334)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/utsname.c:copy_utsname
```
```
In kernel/user_namespace.c (ffffffff811aa95d)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In kernel/pid_namespace.c (ffffffff811ab351)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/pid_namespace.c:create_pid_namespace
```
```
In kernel/audit_tree.c (ffffffff811b99e5)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/audit_tree.c:alloc_chunk
```
```
In kernel/trace/ring_buffer.c (ffffffff811e145f)
Location: arch/x86/include/asm/atomic64_64.h:32
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
In kernel/trace/tracing_map.c (ffffffff811f358d)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_clear
  - kernel/trace/tracing_map.c:tracing_map_clear
  - kernel/trace/tracing_map.c:tracing_map_elt_clear
  - kernel/trace/tracing_map.c:tracing_map_elt_clear
  - kernel/trace/tracing_map.c:tracing_map_set_var
```
```
In kernel/bpf/syscall.c (ffffffff812333e8)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:link_create
  - kernel/bpf/syscall.c:bpf_raw_tracepoint_open
  - kernel/bpf/syscall.c:bpf_tracing_prog_attach
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:map_create
```
```
In kernel/events/core.c (ffffffff812836b3)
Location: arch/x86/include/asm/atomic64_64.h:32
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
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
```
```
In mm/vmalloc.c (ffffffff812ff113)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - mm/vmalloc.c:set_iounmap_nonlazy
```
```
In mm/page_alloc.c (ffffffff81d4ede4)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - mm/page_alloc.c:zone_init_internals
```
```
In mm/memblock.c (ffffffff832da54e)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - mm/memblock.c:reset_all_zones_managed_pages
```
```
In mm/swap_state.c (ffffffff81310bf8)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/slub.c (ffffffff8133a41a)
Location: arch/x86/include/asm/atomic64_64.h:32
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
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_cancel
```
```
In mm/memcontrol.c (ffffffff81d4c4df)
Location: arch/x86/include/asm/atomic64_64.h:32
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
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
```
```
In fs/file_table.c (ffffffff813745bd)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - fs/file_table.c:__alloc_file
```
```
In fs/inode.c (ffffffff813940c5)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - fs/inode.c:inode_init_always
```
```
In fs/namespace.c (ffffffff8139b2cc)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In fs/nsfs.c (ffffffff813b86c9)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - fs/nsfs.c:ns_prune_dentry
```
```
In fs/ext4/inode.c (ffffffff81466a90)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/ioctl.c (ffffffff8146d658)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/super.c (ffffffff814a5ac0)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_alloc_inode
```
```
In fs/ext4/sysfs.c (ffffffff814a7a99)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_store
```
```
In fs/ext4/xattr.c (ffffffff814a9a5e)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
```
```
In fs/fat/inode.c (ffffffff814d3ed9)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_build_inode
```
```
In fs/fuse/inode.c (ffffffff814f538b)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_conn_init
  - fs/fuse/inode.c:fuse_conn_init
```
```
In ipc/namespace.c (ffffffff81511302)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - ipc/namespace.c:copy_ipcs
```
```
In block/blk-ioc.c (ffffffff815d20b6)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - block/blk-ioc.c:create_task_io_context
```
```
In block/blk-cgroup.c (ffffffff815f019d)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_scale_delay
```
```
In block/blk-cgroup-rwstat.c (ffffffff815f3841)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - block/blk-cgroup-rwstat.c:blkg_rwstat_init
```
```
In block/blk-iocost.c (ffffffff815fc1a5)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_pd_init
  - block/blk-iocost.c:ioc_pd_init
  - block/blk-iocost.c:ioc_pd_init
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:iocg_kick_delay
  - block/blk-iocost.c:iocg_activate
  - block/blk-iocost.c:iocg_activate
```
```
In lib/percpu-refcount.c (ffffffff8161b16e)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_init
```
```
In lib/genalloc.c (ffffffff81629e33)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_add_owner
```
```
In drivers/tty/tty_ldsem.c (ffffffff817c0ae5)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:__init_ldsem
```
```
In drivers/iommu/amd/io_pgtable.c (ffffffff81813ef7)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - drivers/iommu/amd/io_pgtable.c:v1_free_pgtable
```
```
In drivers/iommu/iova.c (ffffffff8182d9d5)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - drivers/iommu/iova.c:init_iova_flush_queue
  - drivers/iommu/iova.c:init_iova_flush_queue
```
```
In drivers/md/md.c (ffffffff81d27cd8)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:do_md_stop
```
```
In drivers/firmware/efi/cper.c (ffffffff81a51d3f)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_next_record_id
  - drivers/firmware/efi/cper.c:cper_next_record_id
```
```
In net/core/net_namespace.c (ffffffff81a8dd85)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - net/core/net_namespace.c:net_ns_net_init
```
```
In net/core/page_pool.c (ffffffff81ad94e8)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_alloc_frag
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81b55807)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81b561e6)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_clone_lock
```
```
In net/ipv4/tcp_input.c (ffffffff81b63166)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/nexthop.c (ffffffff81bb45ce)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_res_grp_activity_update
  - net/ipv4/nexthop.c:nh_res_table_upkeep
  - net/ipv4/nexthop.c:nh_res_table_upkeep
```
```
In net/unix/af_unix.c (ffffffff81be6428)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
```
```
In net/packet/af_packet.c (ffffffff81c55848)
Location: arch/x86/include/asm/atomic64_64.h:32
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
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_setup_perfctr
```
```
In arch/x86/events/amd/ibs.c (ffffffff8100c8cb)
Location: arch/x86/include/asm/atomic64_64.h:32
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
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_event_update
```
```
In arch/x86/events/intel/core.c (ffffffff810110e2)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:handle_pmi_common
```
```
In arch/x86/events/intel/bts.c (ffffffff81012e2f)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_buffer_reset
  - arch/x86/events/intel/bts.c:bts_update
```
```
In arch/x86/events/intel/ds.c (ffffffff8101433c)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
```
```
In arch/x86/events/intel/pt.c (ffffffff8101ce1a)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_buffer_reset_offsets
  - arch/x86/events/intel/pt.c:pt_buffer_reset_offsets
  - arch/x86/events/intel/pt.c:pt_update_head
```
```
In arch/x86/events/intel/uncore.c (ffffffff8101f6d3)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
```
```
In arch/x86/kernel/pvclock.c (ffffffff810a0e80)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - arch/x86/kernel/pvclock.c:pvclock_resume
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff834795c3)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff810c090a)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:param_set_local64
```
```
In kernel/fork.c (ffffffff810c88a7)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
  - kernel/fork.c:mm_init
  - kernel/fork.c:mm_init
  - kernel/fork.c:mm_init
```
```
In kernel/workqueue.c (ffffffff810f1898)
Location: arch/x86/include/asm/atomic64_64.h:32
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
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/locking/mutex.c:__mutex_init
```
```
In kernel/locking/rwsem.c (ffffffff8114e384)
Location: arch/x86/include/asm/atomic64_64.h:32
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
In kernel/printk/printk.c (ffffffff8115c21a)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/printk/printk.c:devkmsg_open
  - kernel/printk/printk.c:devkmsg_llseek
  - kernel/printk/printk.c:devkmsg_llseek
  - kernel/printk/printk.c:devkmsg_llseek
  - kernel/printk/printk.c:devkmsg_read
  - kernel/printk/printk.c:devkmsg_read
```
```
In kernel/printk/printk_ringbuffer.c (ffffffff81160dbd)
Location: arch/x86/include/asm/atomic64_64.h:32
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
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/time/namespace.c:copy_time_ns
```
```
In kernel/acct.c (ffffffff811bae01)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/acct.c:acct_on
```
```
In kernel/cgroup/namespace.c (ffffffff811ce934)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
```
```
In kernel/cgroup/pids.c (ffffffff811d220c)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_max_write
  - kernel/cgroup/pids.c:pids_css_alloc
  - kernel/cgroup/pids.c:pids_css_alloc
  - kernel/cgroup/pids.c:pids_css_alloc
```
```
In kernel/cgroup/misc.c (ffffffff811da2d4)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/cgroup/misc.c:misc_cg_alloc
```
```
In kernel/utsname.c (ffffffff811da47f)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/utsname.c:clone_uts_ns
```
```
In kernel/user_namespace.c (ffffffff811dbfc7)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In kernel/pid_namespace.c (ffffffff811dcac2)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/pid_namespace.c:create_pid_namespace
```
```
In kernel/audit_tree.c (ffffffff811ecb05)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/audit_tree.c:alloc_chunk
```
```
In kernel/trace/ring_buffer.c (ffffffff8121811b)
Location: arch/x86/include/asm/atomic64_64.h:32
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
In kernel/trace/tracing_map.c (ffffffff8122cc7d)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_clear
  - kernel/trace/tracing_map.c:tracing_map_clear
  - kernel/trace/tracing_map.c:tracing_map_elt_clear
  - kernel/trace/tracing_map.c:tracing_map_elt_clear
  - kernel/trace/tracing_map.c:tracing_map_set_var
```
```
In kernel/bpf/syscall.c (ffffffff8127643e)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_raw_tp_link_attach
  - kernel/bpf/syscall.c:bpf_perf_link_attach
  - kernel/bpf/syscall.c:bpf_tracing_prog_attach
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:map_create
```
```
In kernel/events/core.c (ffffffff812d66c7)
Location: arch/x86/include/asm/atomic64_64.h:32
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
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
```
```
In mm/page_alloc.c (ffffffff81f1ecb7)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - mm/page_alloc.c:zone_init_internals
```
```
In mm/memblock.c (ffffffff8348f638)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - mm/memblock.c:reset_all_zones_managed_pages
```
```
In mm/swap_state.c (ffffffff8137b9cd)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/slub.c (ffffffff813ac16a)
Location: arch/x86/include/asm/atomic64_64.h:32
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
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_cancel
```
```
In mm/memcontrol.c (ffffffff81f1c01c)
Location: arch/x86/include/asm/atomic64_64.h:32
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
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
```
```
In fs/file_table.c (ffffffff813f35ad)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - fs/file_table.c:__alloc_file
```
```
In fs/inode.c (ffffffff81415dfe)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - fs/inode.c:inode_init_always
```
```
In fs/namespace.c (ffffffff8141eb33)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In fs/nsfs.c (ffffffff8143df89)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - fs/nsfs.c:ns_prune_dentry
```
```
In fs/ext4/inode.c (ffffffff814e6630)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/ioctl.c (ffffffff814edf26)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/super.c (ffffffff8152db21)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:ext4_alloc_inode
```
```
In fs/ext4/sysfs.c (ffffffff8152f36f)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_store
```
```
In fs/ext4/xattr.c (ffffffff81531dc0)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
```
```
In fs/fat/inode.c (ffffffff81561111)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_build_inode
```
```
In fs/fuse/inode.c (ffffffff8158543b)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_conn_init
  - fs/fuse/inode.c:fuse_conn_init
```
```
In ipc/namespace.c (ffffffff815a3135)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
```
```
In block/blk-ioc.c (ffffffff8167d6e4)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - block/blk-ioc.c:alloc_io_context
```
```
In block/blk-cgroup.c (ffffffff816a1289)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_scale_delay
```
```
In block/blk-cgroup-rwstat.c (ffffffff816a4f31)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - block/blk-cgroup-rwstat.c:blkg_rwstat_init
```
```
In block/blk-iocost.c (ffffffff816b0565)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_pd_init
  - block/blk-iocost.c:ioc_pd_init
  - block/blk-iocost.c:ioc_pd_init
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:iocg_kick_delay
  - block/blk-iocost.c:iocg_activate
  - block/blk-iocost.c:iocg_activate
```
```
In lib/percpu-refcount.c (ffffffff816e891e)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_init
```
```
In lib/genalloc.c (ffffffff816fb103)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_add_owner
```
```
In drivers/tty/tty_ldsem.c (ffffffff818fd395)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:__init_ldsem
```
```
In drivers/iommu/amd/io_pgtable.c (ffffffff81954c53)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - drivers/iommu/amd/io_pgtable.c:v1_free_pgtable
```
```
In drivers/iommu/dma-iommu.c (ffffffff8196c594)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_init_fq
  - drivers/iommu/dma-iommu.c:iommu_dma_init_fq
```
```
In drivers/md/md.c (ffffffff81ef3b6a)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
```
```
In drivers/firmware/efi/cper.c (ffffffff81bc0d33)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_next_record_id
  - drivers/firmware/efi/cper.c:cper_next_record_id
```
```
In net/core/gen_stats.c (ffffffff81c029a5)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - net/core/gen_stats.c:gnet_stats_basic_sync_init
  - net/core/gen_stats.c:gnet_stats_basic_sync_init
```
```
In net/core/net_namespace.c (ffffffff81c03925)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - net/core/net_namespace.c:net_ns_net_init
```
```
In net/core/page_pool.c (ffffffff81c5a787)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_alloc_frag
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81ce3502)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ce42fd)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_clone_lock
```
```
In net/ipv4/tcp_input.c (ffffffff81cf1e08)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/nexthop.c (ffffffff81d4807f)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_res_grp_activity_update
  - net/ipv4/nexthop.c:nh_res_table_upkeep
  - net/ipv4/nexthop.c:nh_res_table_upkeep
```
```
In net/unix/af_unix.c (ffffffff81d7ee88)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
```
```
In net/packet/af_packet.c (ffffffff81df1925)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - net/packet/af_packet.c:fanout_add
  - net/packet/af_packet.c:fanout_add
  - net/packet/af_packet.c:fanout_add
```
```
In net/mptcp/protocol.c (ffffffff81e2445d)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_finish_connect
  - net/mptcp/protocol.c:mptcp_sk_clone
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
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_setup_perfctr
```
```
In arch/x86/events/amd/ibs.c (ffffffff8100f90c)
Location: arch/x86/include/asm/atomic64_64.h:32
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
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_event_update
```
```
In arch/x86/events/intel/core.c (ffffffff810155d3)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:handle_pmi_common
```
```
In arch/x86/events/intel/bts.c (ffffffff81016e5f)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_buffer_reset
  - arch/x86/events/intel/bts.c:bts_update
```
```
In arch/x86/events/intel/ds.c (ffffffff810184fc)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
```
```
In arch/x86/events/intel/pt.c (ffffffff810211ea)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_buffer_reset_offsets
  - arch/x86/events/intel/pt.c:pt_buffer_reset_offsets
  - arch/x86/events/intel/pt.c:pt_update_head
```
```
In arch/x86/events/intel/uncore.c (ffffffff81023f03)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
```
```
In arch/x86/kernel/pvclock.c (ffffffff810b8cd0)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - arch/x86/kernel/pvclock.c:pvclock_resume
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff83ea3716)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff810dc87a)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:param_set_local64
```
```
In kernel/fork.c (ffffffff810e5c24)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
  - kernel/fork.c:mm_init
  - kernel/fork.c:mm_init
  - kernel/fork.c:mm_init
```
```
In kernel/workqueue.c (ffffffff8111485e)
Location: arch/x86/include/asm/atomic64_64.h:32
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
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/locking/mutex.c:__mutex_init
```
```
In kernel/locking/rwsem.c (ffffffff8117d314)
Location: arch/x86/include/asm/atomic64_64.h:32
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
In kernel/printk/printk.c (ffffffff8118ecaa)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/printk/printk.c:devkmsg_open
  - kernel/printk/printk.c:devkmsg_llseek
  - kernel/printk/printk.c:devkmsg_llseek
  - kernel/printk/printk.c:devkmsg_llseek
  - kernel/printk/printk.c:devkmsg_read
  - kernel/printk/printk.c:devkmsg_read
```
```
In kernel/printk/printk_ringbuffer.c (ffffffff8119435d)
Location: arch/x86/include/asm/atomic64_64.h:32
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
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/time/namespace.c:copy_time_ns
```
```
In kernel/acct.c (ffffffff811fcbc1)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/acct.c:acct_on
```
```
In kernel/cgroup/namespace.c (ffffffff812121b4)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
```
```
In kernel/cgroup/pids.c (ffffffff81215fbc)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_max_write
  - kernel/cgroup/pids.c:pids_css_alloc
  - kernel/cgroup/pids.c:pids_css_alloc
  - kernel/cgroup/pids.c:pids_css_alloc
```
```
In kernel/cgroup/misc.c (ffffffff8121f864)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/cgroup/misc.c:misc_cg_alloc
```
```
In kernel/utsname.c (ffffffff8121fa3f)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/utsname.c:clone_uts_ns
```
```
In kernel/user_namespace.c (ffffffff81221827)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In kernel/pid_namespace.c (ffffffff81222422)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/pid_namespace.c:create_pid_namespace
```
```
In kernel/audit_tree.c (ffffffff81233065)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/audit_tree.c:alloc_chunk
```
```
In kernel/trace/ring_buffer.c (ffffffff8126156b)
Location: arch/x86/include/asm/atomic64_64.h:32
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
In kernel/trace/tracing_map.c (ffffffff812788cd)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_clear
  - kernel/trace/tracing_map.c:tracing_map_clear
  - kernel/trace/tracing_map.c:tracing_map_elt_clear
  - kernel/trace/tracing_map.c:tracing_map_elt_clear
  - kernel/trace/tracing_map.c:tracing_map_set_var
```
```
In kernel/bpf/syscall.c (ffffffff812cc5ae)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_raw_tp_link_attach
  - kernel/bpf/syscall.c:bpf_perf_link_attach
  - kernel/bpf/syscall.c:bpf_tracing_prog_attach
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:map_create
```
```
In kernel/events/core.c (ffffffff8133f4a7)
Location: arch/x86/include/asm/atomic64_64.h:32
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
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
```
```
In mm/vmstat.c (ffffffff81394e14)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
```
```
In mm/page_alloc.c (ffffffff83ebe3f5)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init_core
  - mm/page_alloc.c:free_area_init_core_hotplug
```
```
In mm/memblock.c (ffffffff83ec1cea)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - mm/memblock.c:reset_all_zones_managed_pages
```
```
In mm/swap_state.c (ffffffff813f9342)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - mm/swap_state.c:swap_cache_get_folio
```
```
In mm/slub.c (ffffffff8142ab0a)
Location: arch/x86/include/asm/atomic64_64.h:32
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
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_cancel
```
```
In mm/memcontrol.c (ffffffff820c3fcf)
Location: arch/x86/include/asm/atomic64_64.h:32
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
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
```
```
In fs/file_table.c (ffffffff8147c35d)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - fs/file_table.c:__alloc_file
```
```
In fs/inode.c (ffffffff814a126e)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - fs/inode.c:inode_init_always
```
```
In fs/namespace.c (ffffffff814ab5a3)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In fs/nsfs.c (ffffffff814cc979)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - fs/nsfs.c:ns_prune_dentry
```
```
In fs/ext4/inode.c (ffffffff8157fdcd)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/ioctl.c (ffffffff81587e03)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/super.c (ffffffff815cbcdd)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:ext4_alloc_inode
```
```
In fs/ext4/sysfs.c (ffffffff815cd07f)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_store
```
```
In fs/ext4/xattr.c (ffffffff815ce861)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_create
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
```
```
In fs/fat/inode.c (ffffffff81603599)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_build_inode
```
```
In fs/fuse/inode.c (ffffffff8162b63b)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_conn_init
  - fs/fuse/inode.c:fuse_conn_init
```
```
In ipc/namespace.c (ffffffff8164cce5)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
```
```
In block/blk-ioc.c (ffffffff8173a2c4)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - block/blk-ioc.c:alloc_io_context
```
```
In block/blk-cgroup.c (ffffffff817600a8)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_scale_delay
```
```
In block/blk-cgroup-rwstat.c (ffffffff81763d71)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - block/blk-cgroup-rwstat.c:blkg_rwstat_init
```
```
In block/blk-iocost.c (ffffffff817703cd)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_pd_init
  - block/blk-iocost.c:ioc_pd_init
  - block/blk-iocost.c:ioc_pd_init
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:iocg_kick_delay
  - block/blk-iocost.c:iocg_activate
  - block/blk-iocost.c:iocg_activate
```
```
In lib/percpu-refcount.c (ffffffff817d893d)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_init
```
```
In lib/genalloc.c (ffffffff817edc83)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_add_owner
```
```
In drivers/tty/tty_ldsem.c (ffffffff81a56a55)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:__init_ldsem
```
```
In drivers/iommu/amd/io_pgtable.c (ffffffff81abaac3)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - drivers/iommu/amd/io_pgtable.c:v1_free_pgtable
```
```
In drivers/iommu/dma-iommu.c (ffffffff81ad6bf2)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_init_fq
  - drivers/iommu/dma-iommu.c:iommu_dma_init_fq
```
```
In drivers/md/md.c (ffffffff81cf9b88)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:do_md_stop
```
```
In drivers/firmware/efi/cper.c (ffffffff81d64623)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_next_record_id
  - drivers/firmware/efi/cper.c:cper_next_record_id
```
```
In net/core/gen_stats.c (ffffffff81db1e55)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - net/core/gen_stats.c:gnet_stats_basic_sync_init
  - net/core/gen_stats.c:gnet_stats_basic_sync_init
```
```
In net/core/net_namespace.c (ffffffff81db2f95)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - net/core/net_namespace.c:net_ns_net_init
```
```
In net/core/page_pool.c (ffffffff81e108e7)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_alloc_frag
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81ea59d2)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ea6e78)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_clone_lock
```
```
In net/ipv4/tcp_input.c (ffffffff81eb6678)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/nexthop.c (ffffffff81f115cf)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_res_grp_activity_update
  - net/ipv4/nexthop.c:nh_res_table_upkeep
  - net/ipv4/nexthop.c:nh_res_bucket_migrate
```
```
In net/unix/af_unix.c (ffffffff81f4c215)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
```
```
In net/packet/af_packet.c (ffffffff81fc58f5)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - net/packet/af_packet.c:fanout_add
  - net/packet/af_packet.c:fanout_add
  - net/packet/af_packet.c:fanout_add
```
```
In net/mptcp/subflow.c (ffffffff81ffefe5)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_subflow_fully_established
  - net/mptcp/subflow.c:subflow_finish_connect
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
Location: arch/x86/include/asm/atomic64_64.h:18
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_setup_perfctr
```
```
In arch/x86/events/amd/ibs.c (ffffffff8100eef6)
Location: arch/x86/include/asm/atomic64_64.h:18
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
Location: arch/x86/include/asm/atomic64_64.h:18
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_event_update
```
```
In arch/x86/events/intel/core.c (ffffffff81014e32)
Location: arch/x86/include/asm/atomic64_64.h:18
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:handle_pmi_common
```
```
In arch/x86/events/intel/bts.c (ffffffff810167b4)
Location: arch/x86/include/asm/atomic64_64.h:18
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_buffer_reset
  - arch/x86/events/intel/bts.c:bts_update
```
```
In arch/x86/events/intel/ds.c (ffffffff81017ddc)
Location: arch/x86/include/asm/atomic64_64.h:18
Inline: True
```
```
In arch/x86/events/intel/pt.c (ffffffff81020f3a)
Location: arch/x86/include/asm/atomic64_64.h:18
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_buffer_reset_offsets
  - arch/x86/events/intel/pt.c:pt_buffer_reset_offsets
  - arch/x86/events/intel/pt.c:pt_update_head
```
```
In arch/x86/events/intel/uncore.c (ffffffff81023c23)
Location: arch/x86/include/asm/atomic64_64.h:18
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
```
```
In arch/x86/kernel/pvclock.c (ffffffff810bbea0)
Location: arch/x86/include/asm/atomic64_64.h:18
Inline: True
Inline callers:
  - arch/x86/kernel/pvclock.c:pvclock_resume
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff836c79a6)
Location: arch/x86/include/asm/atomic64_64.h:18
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff810e7e5a)
Location: arch/x86/include/asm/atomic64_64.h:18
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:param_set_local64
```
```
In kernel/fork.c (ffffffff810f138b)
Location: arch/x86/include/asm/atomic64_64.h:18
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
  - kernel/fork.c:mm_init
  - kernel/fork.c:mm_init
  - kernel/fork.c:mm_init
```
```
In kernel/workqueue.c (ffffffff811207ee)
Location: arch/x86/include/asm/atomic64_64.h:18
Inline: True
Inline callers:
  - kernel/workqueue.c:__cancel_work
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:try_to_grab_pending
  - kernel/workqueue.c:wq_cpu_intensive_report
```
```
In kernel/locking/mutex.c (ffffffff8118d255)
Location: arch/x86/include/asm/atomic64_64.h:18
Inline: True
Inline callers:
  - kernel/locking/mutex.c:__mutex_init
```
```
In kernel/locking/rwsem.c (ffffffff8118dfcb)
Location: arch/x86/include/asm/atomic64_64.h:18
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
In kernel/printk/printk.c (ffffffff811a0414)
Location: arch/x86/include/asm/atomic64_64.h:18
Inline: True
Inline callers:
  - kernel/printk/printk.c:devkmsg_open
  - kernel/printk/printk.c:devkmsg_llseek
  - kernel/printk/printk.c:devkmsg_llseek
  - kernel/printk/printk.c:devkmsg_llseek
  - kernel/printk/printk.c:devkmsg_read
  - kernel/printk/printk.c:devkmsg_read
```
```
In kernel/printk/printk_ringbuffer.c (ffffffff811a5bbd)
Location: arch/x86/include/asm/atomic64_64.h:18
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
Location: arch/x86/include/asm/atomic64_64.h:18
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_create_default_debugfs
  - kernel/dma/swiotlb.c:swiotlb_create_default_debugfs
  - kernel/dma/swiotlb.c:io_tlb_hiwater_set
```
```
In kernel/time/namespace.c (ffffffff81206c89)
Location: arch/x86/include/asm/atomic64_64.h:18
Inline: True
Inline callers:
  - kernel/time/namespace.c:copy_time_ns
```
```
In kernel/acct.c (ffffffff81211d5d)
Location: arch/x86/include/asm/atomic64_64.h:18
Inline: True
Inline callers:
  - kernel/acct.c:acct_on
```
```
In kernel/cgroup/namespace.c (ffffffff81227af4)
Location: arch/x86/include/asm/atomic64_64.h:18
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
```
```
In kernel/cgroup/pids.c (ffffffff8122b8fc)
Location: arch/x86/include/asm/atomic64_64.h:18
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_max_write
  - kernel/cgroup/pids.c:pids_css_alloc
  - kernel/cgroup/pids.c:pids_css_alloc
  - kernel/cgroup/pids.c:pids_css_alloc
```
```
In kernel/cgroup/misc.c (ffffffff81235a24)
Location: arch/x86/include/asm/atomic64_64.h:18
Inline: True
Inline callers:
  - kernel/cgroup/misc.c:misc_cg_alloc
```
```
In kernel/utsname.c (ffffffff81235c2f)
Location: arch/x86/include/asm/atomic64_64.h:18
Inline: True
Inline callers:
  - kernel/utsname.c:clone_uts_ns
```
```
In kernel/user_namespace.c (ffffffff81237cdc)
Location: arch/x86/include/asm/atomic64_64.h:18
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In kernel/pid_namespace.c (ffffffff81238a53)
Location: arch/x86/include/asm/atomic64_64.h:18
Inline: True
Inline callers:
  - kernel/pid_namespace.c:create_pid_namespace
```
```
In kernel/audit_tree.c (ffffffff81249d17)
Location: arch/x86/include/asm/atomic64_64.h:18
Inline: True
Inline callers:
  - kernel/audit_tree.c:alloc_chunk
```
```
In kernel/trace/ring_buffer.c (ffffffff8127872f)
Location: arch/x86/include/asm/atomic64_64.h:18
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
In kernel/trace/tracing_map.c (ffffffff8129030f)
Location: arch/x86/include/asm/atomic64_64.h:18
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_clear
  - kernel/trace/tracing_map.c:tracing_map_clear
  - kernel/trace/tracing_map.c:tracing_map_elt_clear
  - kernel/trace/tracing_map.c:tracing_map_elt_clear
  - kernel/trace/tracing_map.c:tracing_map_set_var
```
```
In kernel/bpf/syscall.c (ffffffff812f3f4e)
Location: arch/x86/include/asm/atomic64_64.h:18
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_raw_tp_link_attach
  - kernel/bpf/syscall.c:bpf_perf_link_attach
  - kernel/bpf/syscall.c:bpf_tracing_prog_attach
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:map_create
```
```
In kernel/events/core.c (ffffffff81370678)
Location: arch/x86/include/asm/atomic64_64.h:18
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
Location: arch/x86/include/asm/atomic64_64.h:18
Inline: True
```
```
In mm/vmstat.c (ffffffff813c7921)
Location: arch/x86/include/asm/atomic64_64.h:18
Inline: True
Inline callers:
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
```
```
In mm/mm_init.c (ffffffff836e1224)
Location: arch/x86/include/asm/atomic64_64.h:18
Inline: True
Inline callers:
  - mm/mm_init.c:free_area_init_core
  - mm/mm_init.c:free_area_init_core_hotplug
```
```
In mm/memblock.c (ffffffff836e7519)
Location: arch/x86/include/asm/atomic64_64.h:18
Inline: True
Inline callers:
  - mm/memblock.c:reset_all_zones_managed_pages
```
```
In mm/swap_state.c (ffffffff8142c697)
Location: arch/x86/include/asm/atomic64_64.h:18
Inline: True
Inline callers:
  - mm/swap_state.c:swap_vma_readahead
  - mm/swap_state.c:swap_cache_get_folio
```
```
In mm/slub.c (ffffffff8145ff81)
Location: arch/x86/include/asm/atomic64_64.h:18
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
Location: arch/x86/include/asm/atomic64_64.h:18
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_cancel
```
```
In mm/memcontrol.c (ffffffff82147d7f)
Location: arch/x86/include/asm/atomic64_64.h:18
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
Location: arch/x86/include/asm/atomic64_64.h:18
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
```
```
In fs/file_table.c (ffffffff814b0ef9)
Location: arch/x86/include/asm/atomic64_64.h:18
Inline: True
Inline callers:
  - fs/file_table.c:init_file
```
```
In fs/inode.c (ffffffff814d657e)
Location: arch/x86/include/asm/atomic64_64.h:18
Inline: True
Inline callers:
  - fs/inode.c:inode_init_always
```
```
In fs/namespace.c (ffffffff814e03a3)
Location: arch/x86/include/asm/atomic64_64.h:18
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In fs/nsfs.c (ffffffff81502bb9)
Location: arch/x86/include/asm/atomic64_64.h:18
Inline: True
Inline callers:
  - fs/nsfs.c:ns_prune_dentry
```
```
In fs/ext4/inode.c (ffffffff815b726f)
Location: arch/x86/include/asm/atomic64_64.h:18
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/ioctl.c (ffffffff815be683)
Location: arch/x86/include/asm/atomic64_64.h:18
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/super.c (ffffffff81603756)
Location: arch/x86/include/asm/atomic64_64.h:18
Inline: True
Inline callers:
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:ext4_alloc_inode
```
```
In fs/ext4/sysfs.c (ffffffff8160502c)
Location: arch/x86/include/asm/atomic64_64.h:18
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_store
```
```
In fs/ext4/xattr.c (ffffffff81606131)
Location: arch/x86/include/asm/atomic64_64.h:18
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_create
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
```
```
In fs/fat/inode.c (ffffffff8163b4b9)
Location: arch/x86/include/asm/atomic64_64.h:18
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_build_inode
```
```
In fs/fuse/inode.c (ffffffff8166386b)
Location: arch/x86/include/asm/atomic64_64.h:18
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_conn_init
  - fs/fuse/inode.c:fuse_conn_init
```
```
In ipc/namespace.c (ffffffff816854f1)
Location: arch/x86/include/asm/atomic64_64.h:18
Inline: True
```
```
In block/blk-ioc.c (ffffffff817769c4)
Location: arch/x86/include/asm/atomic64_64.h:18
Inline: True
Inline callers:
  - block/blk-ioc.c:alloc_io_context
```
```
In block/blk-cgroup.c (ffffffff8179f0b8)
Location: arch/x86/include/asm/atomic64_64.h:18
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_scale_delay
```
```
In block/blk-cgroup-rwstat.c (ffffffff817a2deb)
Location: arch/x86/include/asm/atomic64_64.h:18
Inline: True
Inline callers:
  - block/blk-cgroup-rwstat.c:blkg_rwstat_init
```
```
In block/blk-iocost.c (ffffffff817af3fd)
Location: arch/x86/include/asm/atomic64_64.h:18
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_pd_init
  - block/blk-iocost.c:ioc_pd_init
  - block/blk-iocost.c:ioc_pd_init
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:iocg_kick_delay
  - block/blk-iocost.c:iocg_activate
  - block/blk-iocost.c:iocg_activate
```
```
In lib/percpu-refcount.c (ffffffff81817b46)
Location: arch/x86/include/asm/atomic64_64.h:18
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_init
```
```
In lib/genalloc.c (ffffffff8182e093)
Location: arch/x86/include/asm/atomic64_64.h:18
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_add_owner
```
```
In drivers/tty/tty_ldsem.c (ffffffff81aa1035)
Location: arch/x86/include/asm/atomic64_64.h:18
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:__init_ldsem
```
```
In drivers/iommu/amd/init.c (ffffffff83718c92)
Location: arch/x86/include/asm/atomic64_64.h:18
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:init_iommu_one
```
```
In drivers/iommu/amd/io_pgtable.c (ffffffff81b07193)
Location: arch/x86/include/asm/atomic64_64.h:18
Inline: True
Inline callers:
  - drivers/iommu/amd/io_pgtable.c:v1_free_pgtable
```
```
In drivers/iommu/intel/perfmon.c (ffffffff81b1ae88)
Location: arch/x86/include/asm/atomic64_64.h:18
Inline: True
Inline callers:
  - drivers/iommu/intel/perfmon.c:iommu_pmu_start
```
```
In drivers/iommu/dma-iommu.c (ffffffff81b253c2)
Location: arch/x86/include/asm/atomic64_64.h:18
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_init_fq
  - drivers/iommu/dma-iommu.c:iommu_dma_init_fq
```
```
In drivers/md/md.c (ffffffff81d692cf)
Location: arch/x86/include/asm/atomic64_64.h:18
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:do_md_stop
```
```
In drivers/firmware/efi/cper.c (ffffffff81dcf753)
Location: arch/x86/include/asm/atomic64_64.h:18
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_next_record_id
  - drivers/firmware/efi/cper.c:cper_next_record_id
```
```
In net/core/gen_stats.c (ffffffff81e22425)
Location: arch/x86/include/asm/atomic64_64.h:18
Inline: True
Inline callers:
  - net/core/gen_stats.c:gnet_stats_basic_sync_init
  - net/core/gen_stats.c:gnet_stats_basic_sync_init
```
```
In net/core/net_namespace.c (ffffffff81e23565)
Location: arch/x86/include/asm/atomic64_64.h:18
Inline: True
Inline callers:
  - net/core/net_namespace.c:net_ns_net_init
```
```
In net/core/page_pool.c (ffffffff81e841cb)
Location: arch/x86/include/asm/atomic64_64.h:18
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_alloc_frag
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81f04164)
Location: arch/x86/include/asm/atomic64_64.h:18
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81f05652)
Location: arch/x86/include/asm/atomic64_64.h:18
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_clone_lock
```
```
In net/ipv4/tcp_input.c (ffffffff81f14a98)
Location: arch/x86/include/asm/atomic64_64.h:18
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/nexthop.c (ffffffff81f712bb)
Location: arch/x86/include/asm/atomic64_64.h:18
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_res_grp_activity_update
  - net/ipv4/nexthop.c:nh_res_table_upkeep
  - net/ipv4/nexthop.c:nh_res_bucket_migrate
```
```
In net/unix/af_unix.c (ffffffff81fabff5)
Location: arch/x86/include/asm/atomic64_64.h:18
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
```
```
In net/packet/af_packet.c (ffffffff82029e42)
Location: arch/x86/include/asm/atomic64_64.h:18
Inline: True
Inline callers:
  - net/packet/af_packet.c:fanout_add
  - net/packet/af_packet.c:fanout_add
  - net/packet/af_packet.c:fanout_add
```
```
In net/mptcp/subflow.c (ffffffff8207b205)
Location: arch/x86/include/asm/atomic64_64.h:18
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_subflow_fully_established
  - net/mptcp/subflow.c:subflow_finish_connect
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
Location: arch/x86/include/asm/atomic64_64.h:18
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_setup_perfctr
```
```
In arch/x86/events/amd/ibs.c (ffffffff81014636)
Location: arch/x86/include/asm/atomic64_64.h:18
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
Location: arch/x86/include/asm/atomic64_64.h:18
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_event_update
```
```
In arch/x86/events/intel/core.c (ffffffff81019ded)
Location: arch/x86/include/asm/atomic64_64.h:18
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:handle_pmi_common
```
```
In arch/x86/events/intel/bts.c (ffffffff8101c2f4)
Location: arch/x86/include/asm/atomic64_64.h:18
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_buffer_reset
  - arch/x86/events/intel/bts.c:bts_update
```
```
In arch/x86/events/intel/ds.c (ffffffff8101d94c)
Location: arch/x86/include/asm/atomic64_64.h:18
Inline: True
```
```
In arch/x86/events/intel/pt.c (ffffffff8102705a)
Location: arch/x86/include/asm/atomic64_64.h:18
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_buffer_reset_offsets
  - arch/x86/events/intel/pt.c:pt_buffer_reset_offsets
  - arch/x86/events/intel/pt.c:pt_update_head
```
```
In arch/x86/events/intel/uncore.c (ffffffff81029d53)
Location: arch/x86/include/asm/atomic64_64.h:18
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
```
```
In arch/x86/kernel/pvclock.c (ffffffff810c3020)
Location: arch/x86/include/asm/atomic64_64.h:18
Inline: True
Inline callers:
  - arch/x86/kernel/pvclock.c:pvclock_resume
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff838f85a6)
Location: arch/x86/include/asm/atomic64_64.h:18
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff810f01ea)
Location: arch/x86/include/asm/atomic64_64.h:18
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:param_set_local64
```
```
In kernel/fork.c (ffffffff810fa75b)
Location: arch/x86/include/asm/atomic64_64.h:18
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
  - kernel/fork.c:mm_init
  - kernel/fork.c:mm_init
  - kernel/fork.c:mm_init
```
```
In kernel/workqueue.c (ffffffff8112917e)
Location: arch/x86/include/asm/atomic64_64.h:18
Inline: True
Inline callers:
  - kernel/workqueue.c:__cancel_work
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:try_to_grab_pending
  - kernel/workqueue.c:wq_cpu_intensive_report
```
```
In kernel/cred.c (ffffffff8113f064)
Location: arch/x86/include/asm/atomic64_64.h:18
Inline: True
Inline callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:cred_alloc_blank
```
```
In kernel/locking/mutex.c (ffffffff8119bc05)
Location: arch/x86/include/asm/atomic64_64.h:18
Inline: True
Inline callers:
  - kernel/locking/mutex.c:__mutex_init
```
```
In kernel/locking/rwsem.c (ffffffff8119c97b)
Location: arch/x86/include/asm/atomic64_64.h:18
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
In kernel/printk/printk.c (ffffffff811af434)
Location: arch/x86/include/asm/atomic64_64.h:18
Inline: True
Inline callers:
  - kernel/printk/printk.c:devkmsg_open
  - kernel/printk/printk.c:devkmsg_llseek
  - kernel/printk/printk.c:devkmsg_llseek
  - kernel/printk/printk.c:devkmsg_llseek
  - kernel/printk/printk.c:devkmsg_read
  - kernel/printk/printk.c:devkmsg_read
```
```
In kernel/printk/nbcon.c (ffffffff811b3c28)
Location: arch/x86/include/asm/atomic64_64.h:18
Inline: True
Inline callers:
  - kernel/printk/nbcon.c:nbcon_init
```
```
In kernel/printk/printk_ringbuffer.c (ffffffff811b56ad)
Location: arch/x86/include/asm/atomic64_64.h:18
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
Location: arch/x86/include/asm/atomic64_64.h:18
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
```
```
In kernel/dma/swiotlb.c (ffffffff83903cb5)
Location: arch/x86/include/asm/atomic64_64.h:18
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_create_default_debugfs
  - kernel/dma/swiotlb.c:swiotlb_create_default_debugfs
  - kernel/dma/swiotlb.c:io_tlb_hiwater_set
```
```
In kernel/time/namespace.c (ffffffff8121de99)
Location: arch/x86/include/asm/atomic64_64.h:18
Inline: True
Inline callers:
  - kernel/time/namespace.c:copy_time_ns
```
```
In kernel/acct.c (ffffffff81229408)
Location: arch/x86/include/asm/atomic64_64.h:18
Inline: True
Inline callers:
  - kernel/acct.c:acct_on
```
```
In kernel/cgroup/namespace.c (ffffffff8123f904)
Location: arch/x86/include/asm/atomic64_64.h:18
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
```
```
In kernel/cgroup/pids.c (ffffffff812438fc)
Location: arch/x86/include/asm/atomic64_64.h:18
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_max_write
  - kernel/cgroup/pids.c:pids_css_alloc
  - kernel/cgroup/pids.c:pids_css_alloc
  - kernel/cgroup/pids.c:pids_css_alloc
```
```
In kernel/cgroup/misc.c (ffffffff8124f6a7)
Location: arch/x86/include/asm/atomic64_64.h:18
Inline: True
Inline callers:
  - kernel/cgroup/misc.c:misc_cg_alloc
```
```
In kernel/utsname.c (ffffffff8124f8af)
Location: arch/x86/include/asm/atomic64_64.h:18
Inline: True
Inline callers:
  - kernel/utsname.c:clone_uts_ns
```
```
In kernel/user_namespace.c (ffffffff812517dc)
Location: arch/x86/include/asm/atomic64_64.h:18
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In kernel/pid_namespace.c (ffffffff81252723)
Location: arch/x86/include/asm/atomic64_64.h:18
Inline: True
Inline callers:
  - kernel/pid_namespace.c:create_pid_namespace
```
```
In kernel/audit_tree.c (ffffffff81263c27)
Location: arch/x86/include/asm/atomic64_64.h:18
Inline: True
Inline callers:
  - kernel/audit_tree.c:alloc_chunk
```
```
In kernel/trace/ring_buffer.c (ffffffff81293270)
Location: arch/x86/include/asm/atomic64_64.h:18
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
In kernel/trace/tracing_map.c (ffffffff812ab8cf)
Location: arch/x86/include/asm/atomic64_64.h:18
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_clear
  - kernel/trace/tracing_map.c:tracing_map_clear
  - kernel/trace/tracing_map.c:tracing_map_elt_clear
  - kernel/trace/tracing_map.c:tracing_map_elt_clear
  - kernel/trace/tracing_map.c:tracing_map_set_var
```
```
In kernel/bpf/syscall.c (ffffffff81312e7d)
Location: arch/x86/include/asm/atomic64_64.h:18
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_raw_tp_link_attach
  - kernel/bpf/syscall.c:bpf_perf_link_attach
  - kernel/bpf/syscall.c:bpf_tracing_prog_attach
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:map_create
```
```
In kernel/bpf/tcx.c (ffffffff8137ba52)
Location: arch/x86/include/asm/atomic64_64.h:18
Inline: True
Inline callers:
  - kernel/bpf/tcx.c:tcx_link_prog_attach
  - kernel/bpf/tcx.c:tcx_prog_attach
```
```
In kernel/events/core.c (ffffffff81399978)
Location: arch/x86/include/asm/atomic64_64.h:18
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
Location: arch/x86/include/asm/atomic64_64.h:18
Inline: True
```
```
In mm/vmstat.c (ffffffff813f2301)
Location: arch/x86/include/asm/atomic64_64.h:18
Inline: True
Inline callers:
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
```
```
In mm/mm_init.c (ffffffff83913b24)
Location: arch/x86/include/asm/atomic64_64.h:18
Inline: True
Inline callers:
  - mm/mm_init.c:free_area_init_core
  - mm/mm_init.c:free_area_init_core_hotplug
```
```
In mm/memblock.c (ffffffff83919ac9)
Location: arch/x86/include/asm/atomic64_64.h:18
Inline: True
Inline callers:
  - mm/memblock.c:reset_all_zones_managed_pages
```
```
In mm/slub.c (ffffffff8145d321)
Location: arch/x86/include/asm/atomic64_64.h:18
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
Location: arch/x86/include/asm/atomic64_64.h:18
Inline: True
Inline callers:
  - mm/swap_state.c:swap_vma_readahead
  - mm/swap_state.c:swap_cache_get_folio
```
```
In mm/zswap.c (ffffffff81470555)
Location: arch/x86/include/asm/atomic64_64.h:18
Inline: True
Inline callers:
  - mm/zswap.c:zswap_lruvec_state_init
```
```
In mm/page_counter.c (ffffffff814b1be0)
Location: arch/x86/include/asm/atomic64_64.h:18
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_cancel
```
```
In mm/memcontrol.c (ffffffff814b2bef)
Location: arch/x86/include/asm/atomic64_64.h:18
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_rstat_flush
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
Location: arch/x86/include/asm/atomic64_64.h:18
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
```
```
In fs/file_table.c (ffffffff814e2702)
Location: arch/x86/include/asm/atomic64_64.h:18
Inline: True
Inline callers:
  - fs/file_table.c:init_file
```
```
In fs/inode.c (ffffffff81508953)
Location: arch/x86/include/asm/atomic64_64.h:18
Inline: True
Inline callers:
  - fs/inode.c:inode_init_always
```
```
In fs/namespace.c (ffffffff81513664)
Location: arch/x86/include/asm/atomic64_64.h:18
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In fs/nsfs.c (ffffffff81537809)
Location: arch/x86/include/asm/atomic64_64.h:18
Inline: True
Inline callers:
  - fs/nsfs.c:ns_prune_dentry
```
```
In fs/ext4/inode.c (ffffffff815f0001)
Location: arch/x86/include/asm/atomic64_64.h:18
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/ioctl.c (ffffffff815f743c)
Location: arch/x86/include/asm/atomic64_64.h:18
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/super.c (ffffffff8163c571)
Location: arch/x86/include/asm/atomic64_64.h:18
Inline: True
Inline callers:
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:ext4_alloc_inode
```
```
In fs/ext4/sysfs.c (ffffffff8163dcec)
Location: arch/x86/include/asm/atomic64_64.h:18
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_store
```
```
In fs/ext4/xattr.c (ffffffff8163ee5c)
Location: arch/x86/include/asm/atomic64_64.h:18
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_create
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
```
```
In fs/fat/inode.c (ffffffff81674a18)
Location: arch/x86/include/asm/atomic64_64.h:18
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_build_inode
```
```
In fs/fuse/inode.c (ffffffff8169d95b)
Location: arch/x86/include/asm/atomic64_64.h:18
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_conn_init
  - fs/fuse/inode.c:fuse_conn_init
```
```
In ipc/namespace.c (ffffffff816c1911)
Location: arch/x86/include/asm/atomic64_64.h:18
Inline: True
```
```
In block/blk-ioc.c (ffffffff817b8bf4)
Location: arch/x86/include/asm/atomic64_64.h:18
Inline: True
Inline callers:
  - block/blk-ioc.c:alloc_io_context
```
```
In block/blk-cgroup.c (ffffffff817e2b88)
Location: arch/x86/include/asm/atomic64_64.h:18
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_scale_delay
```
```
In block/blk-cgroup-rwstat.c (ffffffff817e6930)
Location: arch/x86/include/asm/atomic64_64.h:18
Inline: True
Inline callers:
  - block/blk-cgroup-rwstat.c:blkg_rwstat_init
```
```
In block/blk-iocost.c (ffffffff817f3210)
Location: arch/x86/include/asm/atomic64_64.h:18
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_pd_init
  - block/blk-iocost.c:ioc_pd_init
  - block/blk-iocost.c:ioc_pd_init
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:iocg_kick_delay
  - block/blk-iocost.c:iocg_activate
  - block/blk-iocost.c:iocg_activate
```
```
In lib/percpu-refcount.c (ffffffff8185ce42)
Location: arch/x86/include/asm/atomic64_64.h:18
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_init
```
```
In lib/genalloc.c (ffffffff8187fc53)
Location: arch/x86/include/asm/atomic64_64.h:18
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_add_owner
```
```
In drivers/tty/tty_ldsem.c (ffffffff81af3a95)
Location: arch/x86/include/asm/atomic64_64.h:18
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:__init_ldsem
```
```
In drivers/iommu/amd/init.c (ffffffff8394c752)
Location: arch/x86/include/asm/atomic64_64.h:18
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:init_iommu_one
```
```
In drivers/iommu/intel/perfmon.c (ffffffff81b709b8)
Location: arch/x86/include/asm/atomic64_64.h:18
Inline: True
Inline callers:
  - drivers/iommu/intel/perfmon.c:iommu_pmu_start
```
```
In drivers/iommu/dma-iommu.c (ffffffff81b7c05a)
Location: arch/x86/include/asm/atomic64_64.h:18
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_init_fq
  - drivers/iommu/dma-iommu.c:iommu_dma_init_fq
```
```
In drivers/net/netkit.c (ffffffff81ce5c8c)
Location: arch/x86/include/asm/atomic64_64.h:18
Inline: True
Inline callers:
  - drivers/net/netkit.c:netkit_new_link
  - drivers/net/netkit.c:netkit_new_link
```
```
In drivers/net/virtio_net.c (ffffffff81d0c990)
Location: arch/x86/include/asm/atomic64_64.h:18
Inline: True
```
```
In drivers/md/md.c (ffffffff81e206d2)
Location: arch/x86/include/asm/atomic64_64.h:18
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:do_md_stop
```
```
In drivers/firmware/efi/cper.c (ffffffff81e88483)
Location: arch/x86/include/asm/atomic64_64.h:18
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_next_record_id
  - drivers/firmware/efi/cper.c:cper_next_record_id
```
```
In net/core/skbuff.c (ffffffff81ed1361)
Location: arch/x86/include/asm/atomic64_64.h:18
Inline: True
Inline callers:
  - net/core/skbuff.c:napi_pp_put_page
```
```
In net/core/gen_stats.c (ffffffff81ee0365)
Location: arch/x86/include/asm/atomic64_64.h:18
Inline: True
Inline callers:
  - net/core/gen_stats.c:gnet_stats_basic_sync_init
  - net/core/gen_stats.c:gnet_stats_basic_sync_init
```
```
In net/core/net_namespace.c (ffffffff81ee14c5)
Location: arch/x86/include/asm/atomic64_64.h:18
Inline: True
Inline callers:
  - net/core/net_namespace.c:net_ns_net_init
```
```
In net/core/xdp.c (ffffffff81f397a7)
Location: arch/x86/include/asm/atomic64_64.h:18
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_return
```
```
In net/core/page_pool.c (ffffffff81f448aa)
Location: arch/x86/include/asm/atomic64_64.h:18
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_alloc_frag
  - net/core/page_pool.c:page_pool_alloc_frag
  - net/core/page_pool.c:page_pool_put_page_bulk
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
  - net/core/page_pool.c:__page_pool_alloc_page_order
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81fc849c)
Location: arch/x86/include/asm/atomic64_64.h:18
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81fc99b8)
Location: arch/x86/include/asm/atomic64_64.h:18
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_clone_lock
```
```
In net/ipv4/tcp_input.c (ffffffff81fd8fb9)
Location: arch/x86/include/asm/atomic64_64.h:18
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/nexthop.c (ffffffff82037a1b)
Location: arch/x86/include/asm/atomic64_64.h:18
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_res_grp_activity_update
  - net/ipv4/nexthop.c:nh_res_table_upkeep
  - net/ipv4/nexthop.c:nh_res_bucket_migrate
```
```
In net/ipv4/tcp_ao.c (ffffffff82056c31)
Location: arch/x86/include/asm/atomic64_64.h:18
Inline: True
Inline callers:
  - net/ipv4/tcp_ao.c:tcp_ao_add_cmd
  - net/ipv4/tcp_ao.c:tcp_ao_add_cmd
  - net/ipv4/tcp_ao.c:tcp_ao_copy_all_matching
  - net/ipv4/tcp_ao.c:tcp_ao_copy_all_matching
```
```
In net/unix/af_unix.c (ffffffff82079415)
Location: arch/x86/include/asm/atomic64_64.h:18
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
```
```
In net/packet/af_packet.c (ffffffff820f9941)
Location: arch/x86/include/asm/atomic64_64.h:18
Inline: True
Inline callers:
  - net/packet/af_packet.c:fanout_add
  - net/packet/af_packet.c:fanout_add
  - net/packet/af_packet.c:fanout_add
```
```
In net/mptcp/subflow.c (ffffffff82150db1)
Location: arch/x86/include/asm/atomic64_64.h:18
Inline: True
Inline callers:
  - net/mptcp/subflow.c:__mptcp_subflow_fully_established
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
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff8100782d)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_setup_perfctr
```
```
In arch/x86/events/amd/uncore.c (ffffffff81009584)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_read
```
```
In arch/x86/events/amd/ibs.c (ffffffff8100ad86)
Location: arch/x86/include/asm/atomic64_64.h:32
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
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_event_update
```
```
In arch/x86/events/intel/core.c (ffffffff8100e29e)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_save_and_restart
```
```
In arch/x86/events/intel/bts.c (ffffffff8100ec49)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_update
```
```
In arch/x86/events/intel/ds.c (ffffffff8100fc51)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pmu_save_and_restart_reload
  - arch/x86/events/intel/ds.c:intel_pmu_save_and_restart_reload
```
```
In arch/x86/events/intel/pt.c (ffffffff81014ac0)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_buffer_reset_offsets
  - arch/x86/events/intel/pt.c:pt_buffer_reset_offsets
  - arch/x86/events/intel/pt.c:pt_update_head
```
```
In arch/x86/events/intel/uncore.c (ffffffff81016551)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
```
```
In arch/x86/kernel/pvclock.c (ffffffff81078230)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - arch/x86/kernel/pvclock.c:pvclock_resume
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff828b2d9c)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In kernel/fork.c (ffffffff81096c7d)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
  - kernel/fork.c:mm_init
  - kernel/fork.c:mm_init
```
```
In kernel/workqueue.c (ffffffff810bb8b1)
Location: arch/x86/include/asm/atomic64_64.h:32
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
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/locking/mutex.c:__mutex_init
```
```
In kernel/locking/rwsem.c (ffffffff810fcef5)
Location: arch/x86/include/asm/atomic64_64.h:32
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
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/acct.c:acct_on
```
```
In kernel/cgroup/namespace.c (ffffffff811600bc)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
```
```
In kernel/cgroup/pids.c (ffffffff81163059)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_max_write
  - kernel/cgroup/pids.c:pids_css_alloc
  - kernel/cgroup/pids.c:pids_css_alloc
  - kernel/cgroup/pids.c:pids_css_alloc
```
```
In kernel/utsname.c (ffffffff81169cde)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/utsname.c:copy_utsname
```
```
In kernel/user_namespace.c (ffffffff8116af97)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In kernel/pid_namespace.c (ffffffff8116bb16)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In kernel/audit_tree.c (ffffffff81177e9d)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/audit_tree.c:alloc_chunk
```
```
In kernel/trace/ring_buffer.c (ffffffff8119a28c)
Location: arch/x86/include/asm/atomic64_64.h:32
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
In kernel/trace/tracing_map.c (ffffffff811a9651)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_clear
  - kernel/trace/tracing_map.c:tracing_map_clear
  - kernel/trace/tracing_map.c:tracing_map_elt_clear
  - kernel/trace/tracing_map.c:tracing_map_elt_clear
  - kernel/trace/tracing_map.c:tracing_map_set_var
```
```
In kernel/events/core.c (ffffffff81207928)
Location: arch/x86/include/asm/atomic64_64.h:32
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
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
```
```
In mm/vmalloc.c (ffffffff8126f643)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - mm/vmalloc.c:set_iounmap_nonlazy
```
```
In mm/page_alloc.c (ffffffff828c7888)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init_node
  - mm/page_alloc.c:free_area_init_core_hotplug
```
```
In mm/memblock.c (ffffffff828c89d2)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - mm/memblock.c:reset_all_zones_managed_pages
```
```
In mm/swap_state.c (ffffffff8127fd66)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/slub.c (ffffffff812a2a11)
Location: arch/x86/include/asm/atomic64_64.h:32
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
Location: arch/x86/include/asm/atomic64_64.h:32
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
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
```
```
In fs/file_table.c (ffffffff812d7131)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - fs/file_table.c:__alloc_file
```
```
In fs/super.c (ffffffff812d8453)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - fs/super.c:thaw_super_locked
  - fs/super.c:thaw_super_locked
  - fs/super.c:freeze_super
```
```
In fs/inode.c (ffffffff812f406a)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - fs/inode.c:inode_init_always
```
```
In fs/namespace.c (ffffffff812f9ae2)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In fs/nsfs.c (ffffffff81314e29)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - fs/nsfs.c:ns_prune_dentry
```
```
In fs/aio.c (0)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
```
```
In fs/io_uring.c (0)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
```
```
In fs/ext4/inode.c (ffffffff813a73b1)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/ioctl.c (ffffffff813ae3d6)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/super.c (ffffffff813ded2c)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_alloc_inode
```
```
In fs/ext4/sysfs.c (ffffffff813e0abf)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_store
```
```
In fs/ext4/xattr.c (ffffffff813e2a75)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
```
```
In fs/fat/inode.c (ffffffff8140509b)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_build_inode
```
```
In fs/fuse/inode.c (ffffffff81425024)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_conn_init
  - fs/fuse/inode.c:fuse_conn_init
```
```
In ipc/namespace.c (ffffffff8143c894)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - ipc/namespace.c:copy_ipcs
```
```
In block/blk-ioc.c (ffffffff814e2c66)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - block/blk-ioc.c:create_task_io_context
```
```
In block/blk-cgroup.c (ffffffff81500db0)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_scale_delay
  - block/blk-cgroup.c:blkcg_reset_stats
  - block/blk-cgroup.c:blkcg_reset_stats
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-cgroup.c:blkg_alloc
```
```
In block/blk-iocost.c (ffffffff81509084)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_pd_init
  - block/blk-iocost.c:ioc_pd_init
  - block/blk-iocost.c:ioc_pd_init
  - block/blk-iocost.c:ioc_pd_init
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:iocg_kick_waitq
  - block/blk-iocost.c:ioc_refresh_params
```
```
In lib/percpu-refcount.c (ffffffff8152244d)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_init
```
```
In lib/genalloc.c (ffffffff8152fd8e)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_add_owner
```
```
In drivers/tty/tty_ldsem.c (ffffffff81653cf5)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:__init_ldsem
```
```
In drivers/iommu/iova.c (ffffffff816a2375)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - drivers/iommu/iova.c:init_iova_flush_queue
  - drivers/iommu/iova.c:init_iova_flush_queue
```
```
In drivers/md/md.c (ffffffff818465e5)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:do_md_stop
```
```
In net/core/net_namespace.c (ffffffff818c4675)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - net/core/net_namespace.c:net_ns_net_init
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81959e19)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
```
```
In net/ipv4/inet_connection_sock.c (ffffffff8195aa44)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_clone_lock
```
```
In net/ipv4/tcp_input.c (ffffffff819648b9)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/unix/af_unix.c (ffffffff819d021b)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
```
```
In net/packet/af_packet.c (ffffffff81a2ebd7)
Location: arch/x86/include/asm/atomic64_64.h:32
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
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_setup_perfctr
```
```
In arch/x86/events/amd/uncore.c (ffffffff8100827f)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_read
```
```
In arch/x86/events/amd/ibs.c (ffffffff81009713)
Location: arch/x86/include/asm/atomic64_64.h:32
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
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_event_start
  - arch/x86/events/msr.c:msr_event_update
```
```
In arch/x86/events/intel/core.c (ffffffff8100ceed)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_save_and_restart
```
```
In arch/x86/events/intel/bts.c (ffffffff8100d9a9)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_update
```
```
In arch/x86/events/intel/ds.c (ffffffff8100e9c9)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pmu_save_and_restart_reload
  - arch/x86/events/intel/ds.c:intel_pmu_save_and_restart_reload
```
```
In arch/x86/events/intel/pt.c (ffffffff81013d90)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_buffer_reset_offsets
  - arch/x86/events/intel/pt.c:pt_buffer_reset_offsets
  - arch/x86/events/intel/pt.c:pt_update_head
```
```
In arch/x86/events/intel/uncore.c (ffffffff81015981)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
```
```
In arch/x86/kernel/pvclock.c (ffffffff81067ae0)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - arch/x86/kernel/pvclock.c:pvclock_resume
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff828aaf1d)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In kernel/fork.c (ffffffff810856fd)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
  - kernel/fork.c:mm_init
  - kernel/fork.c:mm_init
```
```
In kernel/workqueue.c (ffffffff810aa350)
Location: arch/x86/include/asm/atomic64_64.h:32
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
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/locking/mutex.c:__mutex_init
```
```
In kernel/locking/rwsem.c (ffffffff810ed105)
Location: arch/x86/include/asm/atomic64_64.h:32
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
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
```
```
In kernel/acct.c (ffffffff8114408e)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/acct.c:acct_on
```
```
In kernel/cgroup/namespace.c (ffffffff81153326)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
```
```
In kernel/cgroup/pids.c (ffffffff811562a9)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_max_write
  - kernel/cgroup/pids.c:pids_css_alloc
  - kernel/cgroup/pids.c:pids_css_alloc
  - kernel/cgroup/pids.c:pids_css_alloc
```
```
In kernel/utsname.c (ffffffff8115cede)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/utsname.c:copy_utsname
```
```
In kernel/user_namespace.c (ffffffff8115e197)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In kernel/pid_namespace.c (ffffffff8115ed16)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In kernel/audit_tree.c (ffffffff8116b03d)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/audit_tree.c:alloc_chunk
```
```
In kernel/trace/ring_buffer.c (ffffffff8118d30c)
Location: arch/x86/include/asm/atomic64_64.h:32
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
In kernel/trace/tracing_map.c (ffffffff8119c5d1)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_clear
  - kernel/trace/tracing_map.c:tracing_map_clear
  - kernel/trace/tracing_map.c:tracing_map_elt_clear
  - kernel/trace/tracing_map.c:tracing_map_elt_clear
  - kernel/trace/tracing_map.c:tracing_map_set_var
```
```
In kernel/events/core.c (ffffffff811faa58)
Location: arch/x86/include/asm/atomic64_64.h:32
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
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
```
```
In mm/vmalloc.c (ffffffff812615b3)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - mm/vmalloc.c:set_iounmap_nonlazy
```
```
In mm/page_alloc.c (ffffffff828bffad)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init_node
  - mm/page_alloc.c:free_area_init_core_hotplug
```
```
In mm/memblock.c (ffffffff828c10f7)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - mm/memblock.c:reset_all_zones_managed_pages
```
```
In mm/swap_state.c (ffffffff81271b92)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/slub.c (ffffffff812944e1)
Location: arch/x86/include/asm/atomic64_64.h:32
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
Location: arch/x86/include/asm/atomic64_64.h:32
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
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
```
```
In fs/file_table.c (ffffffff812c7db1)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - fs/file_table.c:__alloc_file
```
```
In fs/super.c (ffffffff812c90d3)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - fs/super.c:thaw_super_locked
  - fs/super.c:thaw_super_locked
  - fs/super.c:freeze_super
```
```
In fs/inode.c (ffffffff812e4c9a)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - fs/inode.c:inode_init_always
```
```
In fs/namespace.c (ffffffff812ea702)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In fs/nsfs.c (ffffffff81305a19)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - fs/nsfs.c:ns_prune_dentry
```
```
In fs/aio.c (0)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
```
```
In fs/io_uring.c (0)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
```
```
In fs/ext4/inode.c (ffffffff81397e41)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/ioctl.c (ffffffff8139ee66)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/super.c (ffffffff813cf7ac)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_alloc_inode
```
```
In fs/ext4/sysfs.c (ffffffff813d153f)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_store
```
```
In fs/ext4/xattr.c (ffffffff813d34f5)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
```
```
In fs/fat/inode.c (ffffffff813f5b1b)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_build_inode
```
```
In fs/fuse/inode.c (ffffffff81415aa4)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_conn_init
  - fs/fuse/inode.c:fuse_conn_init
```
```
In ipc/namespace.c (ffffffff8142d304)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - ipc/namespace.c:copy_ipcs
```
```
In block/blk-ioc.c (ffffffff814d35f6)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - block/blk-ioc.c:create_task_io_context
```
```
In block/blk-cgroup.c (ffffffff814f12c0)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_scale_delay
  - block/blk-cgroup.c:blkcg_reset_stats
  - block/blk-cgroup.c:blkcg_reset_stats
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-cgroup.c:blkg_alloc
```
```
In block/blk-iocost.c (ffffffff814f9534)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_pd_init
  - block/blk-iocost.c:ioc_pd_init
  - block/blk-iocost.c:ioc_pd_init
  - block/blk-iocost.c:ioc_pd_init
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:iocg_kick_waitq
  - block/blk-iocost.c:ioc_refresh_params
```
```
In lib/percpu-refcount.c (ffffffff8151273d)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_init
```
```
In lib/genalloc.c (ffffffff8152006e)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_add_owner
```
```
In drivers/tty/tty_ldsem.c (ffffffff816340d5)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:__init_ldsem
```
```
In drivers/iommu/iova.c (ffffffff8167fd65)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - drivers/iommu/iova.c:init_iova_flush_queue
  - drivers/iommu/iova.c:init_iova_flush_queue
```
```
In drivers/md/md.c (ffffffff8180dc45)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:do_md_stop
```
```
In drivers/firmware/efi/cper.c (ffffffff818459bb)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_next_record_id
  - drivers/firmware/efi/cper.c:cper_next_record_id
```
```
In net/core/net_namespace.c (ffffffff8187e5b5)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - net/core/net_namespace.c:net_ns_net_init
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81913909)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81914534)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_clone_lock
```
```
In net/ipv4/tcp_input.c (ffffffff8191e3a9)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/unix/af_unix.c (ffffffff8198cfdb)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
```
```
In net/packet/af_packet.c (ffffffff819ebdc7)
Location: arch/x86/include/asm/atomic64_64.h:32
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
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_setup_perfctr
```
```
In arch/x86/events/amd/uncore.c (ffffffff81009544)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_read
```
```
In arch/x86/events/amd/ibs.c (ffffffff8100ad46)
Location: arch/x86/include/asm/atomic64_64.h:32
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
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_event_update
```
```
In arch/x86/events/intel/core.c (ffffffff8100e25e)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_save_and_restart
```
```
In arch/x86/events/intel/bts.c (ffffffff8100ec09)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_update
```
```
In arch/x86/events/intel/ds.c (ffffffff8100fc11)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pmu_save_and_restart_reload
  - arch/x86/events/intel/ds.c:intel_pmu_save_and_restart_reload
```
```
In arch/x86/events/intel/pt.c (ffffffff81014a80)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_buffer_reset_offsets
  - arch/x86/events/intel/pt.c:pt_buffer_reset_offsets
  - arch/x86/events/intel/pt.c:pt_update_head
```
```
In arch/x86/events/intel/uncore.c (ffffffff81016511)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
```
```
In arch/x86/kernel/pvclock.c (ffffffff810781e0)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - arch/x86/kernel/pvclock.c:pvclock_resume
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff828c5c9b)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In kernel/fork.c (ffffffff81096c2d)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
  - kernel/fork.c:mm_init
  - kernel/fork.c:mm_init
```
```
In kernel/workqueue.c (ffffffff810bae11)
Location: arch/x86/include/asm/atomic64_64.h:32
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
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/locking/mutex.c:__mutex_init
```
```
In kernel/locking/rwsem.c (ffffffff810fa0b5)
Location: arch/x86/include/asm/atomic64_64.h:32
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
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/acct.c:acct_on
```
```
In kernel/cgroup/namespace.c (ffffffff8115de8c)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
```
```
In kernel/cgroup/pids.c (ffffffff81160e29)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_max_write
  - kernel/cgroup/pids.c:pids_css_alloc
  - kernel/cgroup/pids.c:pids_css_alloc
  - kernel/cgroup/pids.c:pids_css_alloc
```
```
In kernel/utsname.c (ffffffff81167aae)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/utsname.c:copy_utsname
```
```
In kernel/user_namespace.c (ffffffff81168d67)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In kernel/pid_namespace.c (ffffffff811698e6)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In kernel/audit_tree.c (ffffffff81175c6d)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/audit_tree.c:alloc_chunk
```
```
In kernel/trace/ring_buffer.c (ffffffff8119805c)
Location: arch/x86/include/asm/atomic64_64.h:32
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
In kernel/trace/tracing_map.c (ffffffff811a7421)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_clear
  - kernel/trace/tracing_map.c:tracing_map_clear
  - kernel/trace/tracing_map.c:tracing_map_elt_clear
  - kernel/trace/tracing_map.c:tracing_map_elt_clear
  - kernel/trace/tracing_map.c:tracing_map_set_var
```
```
In kernel/events/core.c (ffffffff812056f8)
Location: arch/x86/include/asm/atomic64_64.h:32
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
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
```
```
In mm/vmalloc.c (ffffffff8126d3e3)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - mm/vmalloc.c:set_iounmap_nonlazy
```
```
In mm/page_alloc.c (ffffffff828da608)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init_node
  - mm/page_alloc.c:free_area_init_core_hotplug
```
```
In mm/memblock.c (ffffffff828db752)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - mm/memblock.c:reset_all_zones_managed_pages
```
```
In mm/swap_state.c (ffffffff8127dbba)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/slub.c (ffffffff812a0821)
Location: arch/x86/include/asm/atomic64_64.h:32
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
Location: arch/x86/include/asm/atomic64_64.h:32
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
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
```
```
In fs/file_table.c (ffffffff812d4f41)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - fs/file_table.c:__alloc_file
```
```
In fs/super.c (ffffffff812d6263)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - fs/super.c:thaw_super_locked
  - fs/super.c:thaw_super_locked
  - fs/super.c:freeze_super
```
```
In fs/inode.c (ffffffff812f1e7a)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - fs/inode.c:inode_init_always
```
```
In fs/namespace.c (ffffffff812f78d2)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In fs/nsfs.c (ffffffff81312c19)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - fs/nsfs.c:ns_prune_dentry
```
```
In fs/aio.c (0)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
```
```
In fs/io_uring.c (0)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
```
```
In fs/ext4/inode.c (ffffffff813a4c11)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/ioctl.c (ffffffff813abc36)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/super.c (ffffffff813dc0d3)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_alloc_inode
```
```
In fs/ext4/sysfs.c (ffffffff813dde3f)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_store
```
```
In fs/ext4/xattr.c (ffffffff813dfdf5)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
```
```
In fs/fat/inode.c (ffffffff8140241b)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_build_inode
```
```
In fs/fuse/inode.c (ffffffff814211c4)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_conn_init
  - fs/fuse/inode.c:fuse_conn_init
```
```
In ipc/namespace.c (ffffffff81438a34)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - ipc/namespace.c:copy_ipcs
```
```
In block/blk-ioc.c (ffffffff814decf6)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - block/blk-ioc.c:create_task_io_context
```
```
In block/blk-cgroup.c (ffffffff814fce40)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_scale_delay
  - block/blk-cgroup.c:blkcg_reset_stats
  - block/blk-cgroup.c:blkcg_reset_stats
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-cgroup.c:blkg_alloc
```
```
In block/blk-iocost.c (ffffffff81505114)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_pd_init
  - block/blk-iocost.c:ioc_pd_init
  - block/blk-iocost.c:ioc_pd_init
  - block/blk-iocost.c:ioc_pd_init
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:iocg_kick_waitq
  - block/blk-iocost.c:ioc_refresh_params
```
```
In lib/percpu-refcount.c (ffffffff8151e4dd)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_init
```
```
In lib/genalloc.c (ffffffff8152bace)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_add_owner
```
```
In drivers/tty/tty_ldsem.c (ffffffff816820b5)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:__init_ldsem
```
```
In drivers/iommu/iova.c (ffffffff816d05e5)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - drivers/iommu/iova.c:init_iova_flush_queue
  - drivers/iommu/iova.c:init_iova_flush_queue
```
```
In drivers/md/md.c (ffffffff81895c15)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:do_md_stop
```
```
In drivers/firmware/efi/cper.c (ffffffff818e011b)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_next_record_id
  - drivers/firmware/efi/cper.c:cper_next_record_id
```
```
In net/core/net_namespace.c (ffffffff81915675)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - net/core/net_namespace.c:net_ns_net_init
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff819c45e9)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819c5214)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_clone_lock
```
```
In net/ipv4/tcp_input.c (ffffffff819cf089)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/unix/af_unix.c (ffffffff81a3ac9b)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
```
```
In net/packet/af_packet.c (ffffffff81a9a787)
Location: arch/x86/include/asm/atomic64_64.h:32
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
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_setup_perfctr
```
```
In arch/x86/events/amd/uncore.c (ffffffff810096a4)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_read
```
```
In arch/x86/events/amd/ibs.c (ffffffff8100acd6)
Location: arch/x86/include/asm/atomic64_64.h:32
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
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_event_update
```
```
In arch/x86/events/intel/core.c (ffffffff8100e42e)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_save_and_restart
```
```
In arch/x86/events/intel/bts.c (ffffffff8100edd9)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_update
```
```
In arch/x86/events/intel/ds.c (ffffffff8100fe21)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pmu_save_and_restart_reload
  - arch/x86/events/intel/ds.c:intel_pmu_save_and_restart_reload
```
```
In arch/x86/events/intel/pt.c (ffffffff81014cc0)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_buffer_reset_offsets
  - arch/x86/events/intel/pt.c:pt_buffer_reset_offsets
  - arch/x86/events/intel/pt.c:pt_update_head
```
```
In arch/x86/events/intel/uncore.c (ffffffff81016751)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
```
```
In arch/x86/kernel/pvclock.c (ffffffff8107a2e0)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - arch/x86/kernel/pvclock.c:pvclock_resume
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff828c8e41)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff8109a6ca)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:param_set_local64
```
```
In kernel/fork.c (ffffffff8109eacd)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
  - kernel/fork.c:mm_init
  - kernel/fork.c:mm_init
```
```
In kernel/workqueue.c (ffffffff810c42d1)
Location: arch/x86/include/asm/atomic64_64.h:32
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
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/locking/mutex.c:__mutex_init
```
```
In kernel/locking/rwsem.c (ffffffff81105225)
Location: arch/x86/include/asm/atomic64_64.h:32
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
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/acct.c:acct_on
```
```
In kernel/cgroup/namespace.c (ffffffff8116b0f7)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
```
```
In kernel/cgroup/pids.c (ffffffff8116e279)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_max_write
  - kernel/cgroup/pids.c:pids_css_alloc
  - kernel/cgroup/pids.c:pids_css_alloc
  - kernel/cgroup/pids.c:pids_css_alloc
```
```
In kernel/utsname.c (ffffffff8117518e)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/utsname.c:copy_utsname
```
```
In kernel/user_namespace.c (ffffffff81176457)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In kernel/pid_namespace.c (ffffffff81177006)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In kernel/audit_tree.c (ffffffff8118355d)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/audit_tree.c:alloc_chunk
```
```
In kernel/trace/ring_buffer.c (ffffffff811a5c8c)
Location: arch/x86/include/asm/atomic64_64.h:32
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
In kernel/trace/tracing_map.c (ffffffff811b51c1)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_clear
  - kernel/trace/tracing_map.c:tracing_map_clear
  - kernel/trace/tracing_map.c:tracing_map_elt_clear
  - kernel/trace/tracing_map.c:tracing_map_elt_clear
  - kernel/trace/tracing_map.c:tracing_map_set_var
```
```
In kernel/events/core.c (ffffffff81214568)
Location: arch/x86/include/asm/atomic64_64.h:32
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
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
```
```
In mm/vmalloc.c (ffffffff8127cd73)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - mm/vmalloc.c:set_iounmap_nonlazy
```
```
In mm/page_alloc.c (ffffffff828dfa29)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init_node
  - mm/page_alloc.c:free_area_init_core_hotplug
```
```
In mm/memblock.c (ffffffff828e0b73)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - mm/memblock.c:reset_all_zones_managed_pages
```
```
In mm/swap_state.c (ffffffff8128d76a)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/slub.c (ffffffff812b0961)
Location: arch/x86/include/asm/atomic64_64.h:32
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
Location: arch/x86/include/asm/atomic64_64.h:32
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
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
```
```
In fs/file_table.c (ffffffff812e5da1)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - fs/file_table.c:__alloc_file
```
```
In fs/super.c (ffffffff812e6e23)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - fs/super.c:thaw_super_locked
  - fs/super.c:thaw_super_locked
  - fs/super.c:freeze_super
```
```
In fs/inode.c (ffffffff8130344a)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - fs/inode.c:inode_init_always
```
```
In fs/namespace.c (ffffffff81308be2)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In fs/nsfs.c (ffffffff81324449)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - fs/nsfs.c:ns_prune_dentry
```
```
In fs/aio.c (0)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
```
```
In fs/io_uring.c (0)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
```
```
In fs/ext4/inode.c (ffffffff813b9326)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/ioctl.c (ffffffff813c05d6)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/super.c (ffffffff813f14ad)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_alloc_inode
```
```
In fs/ext4/sysfs.c (ffffffff813f325f)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_store
```
```
In fs/ext4/xattr.c (ffffffff813f5215)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
```
```
In fs/fat/inode.c (ffffffff814183eb)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_build_inode
```
```
In fs/fuse/inode.c (ffffffff81438044)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_conn_init
  - fs/fuse/inode.c:fuse_conn_init
```
```
In ipc/namespace.c (ffffffff8144fba4)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - ipc/namespace.c:copy_ipcs
```
```
In block/blk-ioc.c (ffffffff814f7b66)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - block/blk-ioc.c:create_task_io_context
```
```
In block/blk-cgroup.c (ffffffff81515ef0)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_scale_delay
  - block/blk-cgroup.c:blkcg_reset_stats
  - block/blk-cgroup.c:blkcg_reset_stats
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-cgroup.c:blkg_alloc
```
```
In block/blk-iocost.c (ffffffff8151e774)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_pd_init
  - block/blk-iocost.c:ioc_pd_init
  - block/blk-iocost.c:ioc_pd_init
  - block/blk-iocost.c:ioc_pd_init
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:iocg_kick_waitq
  - block/blk-iocost.c:ioc_refresh_params
```
```
In lib/percpu-refcount.c (ffffffff81537d4d)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_init
```
```
In lib/genalloc.c (ffffffff8154536e)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_add_owner
```
```
In drivers/tty/tty_ldsem.c (ffffffff8169c6f5)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:__init_ldsem
```
```
In drivers/iommu/iova.c (ffffffff816eab75)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - drivers/iommu/iova.c:init_iova_flush_queue
  - drivers/iommu/iova.c:init_iova_flush_queue
```
```
In drivers/md/md.c (ffffffff818b1a69)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:do_md_stop
```
```
In drivers/firmware/efi/cper.c (ffffffff818fcbbb)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_next_record_id
  - drivers/firmware/efi/cper.c:cper_next_record_id
```
```
In net/core/net_namespace.c (ffffffff81936855)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - net/core/net_namespace.c:net_ns_net_init
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff819ce189)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819cece4)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_clone_lock
```
```
In net/ipv4/tcp_input.c (ffffffff819d8c19)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/unix/af_unix.c (ffffffff81a45f1b)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
```
```
In net/packet/af_packet.c (ffffffff81aa74da)
Location: arch/x86/include/asm/atomic64_64.h:32
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
