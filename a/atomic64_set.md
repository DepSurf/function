# Function: <code>atomic64_set</code>

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
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_setup_perfctr
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_perf_event_set_period
```
```
In arch/x86/events/amd/uncore.c (ffffffff81008284)
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_read
```
```
In arch/x86/events/amd/ibs.c (ffffffff81008d3a)
Location: arch/x86/include/asm/atomic64_64.h:31
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
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
```
```
In arch/x86/events/intel/core.c (ffffffff8100c2b8)
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_save_and_restart
```
```
In arch/x86/events/intel/bts.c (ffffffff8100c9ca)
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_update
```
```
In arch/x86/events/intel/cqm.c (ffffffff8100d882)
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
Inline callers:
  - arch/x86/events/intel/cqm.c:intel_cqm_event_count
  - arch/x86/events/intel/cqm.c:intel_cqm_xchg_rmid
```
```
In arch/x86/events/intel/cstate.c (ffffffff8100eed1)
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
```
```
In arch/x86/events/intel/pt.c (ffffffff810134d0)
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_buffer_reset_offsets
  - arch/x86/events/intel/pt.c:pt_buffer_reset_offsets
  - arch/x86/events/intel/pt.c:pt_update_head
```
```
In arch/x86/events/intel/rapl.c (ffffffff81014bc8)
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
Inline callers:
  - arch/x86/events/intel/rapl.c:__rapl_pmu_event_start
```
```
In arch/x86/events/intel/uncore.c (ffffffff81016718)
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
```
```
In arch/x86/events/intel/uncore_snb.c (ffffffff81018f2e)
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_event_start
```
```
In arch/x86/kernel/pvclock.c (ffffffff81065141)
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
Inline callers:
  - arch/x86/kernel/pvclock.c:pvclock_resume
```
```
In kernel/fork.c (ffffffff8107daa4)
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
  - kernel/fork.c:mm_init
```
```
In kernel/workqueue.c (ffffffff81098015)
Location: arch/x86/include/asm/atomic64_64.h:31
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
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
Inline callers:
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/fair.c:alloc_fair_sched_group
```
```
In kernel/acct.c (ffffffff8110bf5d)
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
Inline callers:
  - kernel/acct.c:SyS_acct
```
```
In kernel/cgroup.c (ffffffff81119ae9)
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
Inline callers:
  - kernel/cgroup.c:copy_cgroup_ns
```
```
In kernel/cgroup_pids.c (ffffffff8111a729)
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
Inline callers:
  - kernel/cgroup_pids.c:pids_css_alloc
```
```
In kernel/utsname.c (ffffffff8111dd38)
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
Inline callers:
  - kernel/utsname.c:copy_utsname
```
```
In kernel/user_namespace.c (ffffffff8111efa7)
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In kernel/pid_namespace.c (ffffffff8111f9ec)
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In kernel/audit_tree.c (ffffffff8112aee3)
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
Inline callers:
  - kernel/audit_tree.c:alloc_chunk
```
```
In kernel/trace/ring_buffer.c (ffffffff81146755)
Location: arch/x86/include/asm/atomic64_64.h:31
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
Location: arch/x86/include/asm/atomic64_64.h:31
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
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_aux_output_begin
  - kernel/events/ring_buffer.c:perf_aux_output_end
  - kernel/events/ring_buffer.c:perf_aux_output_end
```
```
In mm/slub.c (ffffffff811edbbd)
Location: arch/x86/include/asm/atomic64_64.h:31
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
Location: arch/x86/include/asm/atomic64_64.h:31
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
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
```
```
In fs/file_table.c (ffffffff8120e136)
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
Inline callers:
  - fs/file_table.c:get_empty_filp
```
```
In fs/namespace.c (ffffffff8122b6de)
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In fs/nsfs.c (ffffffff81242209)
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
Inline callers:
  - fs/nsfs.c:ns_prune_dentry
```
```
In fs/ext4/super.c (ffffffff812bd7d1)
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/ext4/sysfs.c (ffffffff812e3965)
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_store
```
```
In ipc/namespace.c (ffffffff8132e9f5)
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
Inline callers:
  - ipc/namespace.c:copy_ipcs
```
```
In block/blk-ioc.c (ffffffff813bf0c6)
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
Inline callers:
  - block/blk-ioc.c:create_task_io_context
```
```
In block/blk-cgroup.c (ffffffff813d71b7)
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_rwstat_read
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-cgroup.c:blkcg_reset_stats
  - block/blk-cgroup.c:blkcg_reset_stats
```
```
In block/cfq-iosched.c (ffffffff813ddf22)
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfqg_stats_reset
  - block/cfq-iosched.c:cfqg_stats_reset
  - block/cfq-iosched.c:cfqg_stats_reset
  - block/cfq-iosched.c:cfqg_stats_reset
  - block/cfq-iosched.c:blkg_rwstat_read
  - block/cfq-iosched.c:cfq_pd_alloc
  - block/cfq-iosched.c:cfq_pd_alloc
  - block/cfq-iosched.c:cfq_pd_alloc
  - block/cfq-iosched.c:cfq_pd_alloc
  - block/cfq-iosched.c:cfq_pd_alloc
```
```
In lib/percpu-refcount.c (ffffffff813fef22)
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_init
```
```
In drivers/md/md.c (ffffffff81692c36)
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:do_md_stop
```
```
In drivers/firmware/efi/cper.c (ffffffff816d383e)
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_next_record_id
```
```
In net/core/sock.c (ffffffff81703f63)
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
```
```
In net/core/net_namespace.c (ffffffff8170fd25)
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
Inline callers:
  - net/core/net_namespace.c:net_ns_net_init
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81763567)
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
```
```
In net/ipv4/inet_connection_sock.c (ffffffff817645d2)
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_clone_lock
```
```
In net/ipv4/tcp_input.c (ffffffff8176b2f4)
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/tcp_memcontrol.c (ffffffff817ace5d)
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
Inline callers:
  - net/ipv4/tcp_memcontrol.c:tcp_init_cgroup
```
```
In net/unix/af_unix.c (ffffffff817bdffc)
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
```
```
In net/packet/af_packet.c (ffffffff81806454)
Location: arch/x86/include/asm/atomic64_64.h:31
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
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_setup_perfctr
```
```
In arch/x86/events/amd/uncore.c (ffffffff810084d4)
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_read
```
```
In arch/x86/events/amd/ibs.c (ffffffff81009a58)
Location: arch/x86/include/asm/atomic64_64.h:31
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
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
```
```
In arch/x86/events/intel/core.c (ffffffff8100c4f8)
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_save_and_restart
```
```
In arch/x86/events/intel/bts.c (ffffffff8100cc2a)
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_update
```
```
In arch/x86/events/intel/cqm.c (ffffffff8100deca)
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
Inline callers:
  - arch/x86/events/intel/cqm.c:intel_cqm_event_count
  - arch/x86/events/intel/cqm.c:intel_cqm_xchg_rmid
```
```
In arch/x86/events/intel/pt.c (ffffffff81012db0)
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_buffer_reset_offsets
  - arch/x86/events/intel/pt.c:pt_buffer_reset_offsets
  - arch/x86/events/intel/pt.c:pt_update_head
```
```
In arch/x86/events/intel/uncore.c (ffffffff8101469f)
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
```
```
In arch/x86/events/intel/uncore_snb.c (ffffffff81018279)
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_event_start
```
```
In arch/x86/kernel/pvclock.c (ffffffff81064ee1)
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
Inline callers:
  - arch/x86/kernel/pvclock.c:pvclock_resume
```
```
In kernel/fork.c (ffffffff8107f6ca)
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
  - kernel/fork.c:mm_init
```
```
In kernel/workqueue.c (ffffffff8109bf9c)
Location: arch/x86/include/asm/atomic64_64.h:31
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
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
Inline callers:
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/fair.c:alloc_fair_sched_group
```
```
In kernel/locking/rwsem-xadd.c (ffffffff810d04ca)
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
Inline callers:
  - kernel/locking/rwsem-xadd.c:__init_rwsem
```
```
In kernel/acct.c (ffffffff811137be)
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
Inline callers:
  - kernel/acct.c:SyS_acct
```
```
In kernel/cgroup.c (ffffffff811218fa)
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
Inline callers:
  - kernel/cgroup.c:copy_cgroup_ns
```
```
In kernel/cgroup_pids.c (ffffffff811225be)
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
Inline callers:
  - kernel/cgroup_pids.c:pids_css_alloc
  - kernel/cgroup_pids.c:pids_css_alloc
```
```
In kernel/utsname.c (ffffffff81125c06)
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
Inline callers:
  - kernel/utsname.c:copy_utsname
```
```
In kernel/user_namespace.c (ffffffff81126f07)
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In kernel/pid_namespace.c (ffffffff811279ea)
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In kernel/audit_tree.c (ffffffff811330f2)
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
Inline callers:
  - kernel/audit_tree.c:alloc_chunk
```
```
In kernel/trace/ring_buffer.c (ffffffff81152a47)
Location: arch/x86/include/asm/atomic64_64.h:31
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
In kernel/trace/tracing_map.c (ffffffff81160d96)
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_sort_entries
  - kernel/trace/tracing_map.c:tracing_map_clear
  - kernel/trace/tracing_map.c:tracing_map_clear
  - kernel/trace/tracing_map.c:tracing_map_elt_clear
```
```
In kernel/events/core.c (ffffffff81190432)
Location: arch/x86/include/asm/atomic64_64.h:31
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
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_aux_output_end
  - kernel/events/ring_buffer.c:perf_aux_output_end
  - kernel/events/ring_buffer.c:perf_aux_output_begin
```
```
In mm/slub.c (ffffffff8120da5f)
Location: arch/x86/include/asm/atomic64_64.h:31
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
Location: arch/x86/include/asm/atomic64_64.h:31
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
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
```
```
In fs/file_table.c (ffffffff81234b66)
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
Inline callers:
  - fs/file_table.c:get_empty_filp
```
```
In fs/namespace.c (ffffffff81253e4e)
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In fs/nsfs.c (ffffffff8126a569)
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
Inline callers:
  - fs/nsfs.c:ns_prune_dentry
```
```
In fs/ext4/super.c (ffffffff812ec804)
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/ext4/sysfs.c (ffffffff81313935)
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_store
```
```
In ipc/namespace.c (ffffffff81363688)
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
Inline callers:
  - ipc/namespace.c:copy_ipcs
```
```
In block/blk-ioc.c (ffffffff81403001)
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
Inline callers:
  - block/blk-ioc.c:create_task_io_context
```
```
In block/blk-cgroup.c (ffffffff8141e86e)
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_reset_stats
  - block/blk-cgroup.c:blkcg_reset_stats
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-cgroup.c:blkg_rwstat_read
```
```
In block/cfq-iosched.c (ffffffff81425236)
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_pd_alloc
  - block/cfq-iosched.c:cfq_pd_alloc
  - block/cfq-iosched.c:cfq_pd_alloc
  - block/cfq-iosched.c:cfq_pd_alloc
  - block/cfq-iosched.c:cfq_pd_alloc
  - block/cfq-iosched.c:cfqg_stats_reset
  - block/cfq-iosched.c:cfqg_stats_reset
  - block/cfq-iosched.c:cfqg_stats_reset
  - block/cfq-iosched.c:cfqg_stats_reset
  - block/cfq-iosched.c:blkg_rwstat_read
```
```
In lib/percpu-refcount.c (ffffffff81446612)
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_init
```
```
In drivers/md/md.c (ffffffff816f3669)
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:do_md_stop
```
```
In drivers/firmware/efi/cper.c (ffffffff817371fe)
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_next_record_id
```
```
In net/core/sock.c (ffffffff8176aa13)
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
```
```
In net/core/net_namespace.c (ffffffff81777665)
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
Inline callers:
  - net/core/net_namespace.c:net_ns_net_init
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff817cfa20)
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
```
```
In net/ipv4/inet_connection_sock.c (ffffffff817d0b17)
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_clone_lock
```
```
In net/ipv4/tcp_input.c (ffffffff817d7aaf)
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/unix/af_unix.c (ffffffff8182af37)
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
```
```
In net/packet/af_packet.c (ffffffff81876f16)
Location: arch/x86/include/asm/atomic64_64.h:31
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
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_setup_perfctr
```
```
In arch/x86/events/amd/uncore.c (ffffffff810084f4)
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_read
```
```
In arch/x86/events/amd/ibs.c (ffffffff81009a98)
Location: arch/x86/include/asm/atomic64_64.h:31
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
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
```
```
In arch/x86/events/intel/core.c (ffffffff8100c5b8)
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_save_and_restart
```
```
In arch/x86/events/intel/bts.c (ffffffff8100ccfa)
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_update
```
```
In arch/x86/events/intel/cqm.c (ffffffff8100df8a)
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
Inline callers:
  - arch/x86/events/intel/cqm.c:intel_cqm_event_count
  - arch/x86/events/intel/cqm.c:intel_cqm_xchg_rmid
```
```
In arch/x86/events/intel/pt.c (ffffffff81012ea0)
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_buffer_reset_offsets
  - arch/x86/events/intel/pt.c:pt_buffer_reset_offsets
  - arch/x86/events/intel/pt.c:pt_update_head
```
```
In arch/x86/events/intel/uncore.c (ffffffff81014875)
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
```
```
In arch/x86/events/intel/uncore_snb.c (ffffffff8101844c)
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_event_start
```
```
In arch/x86/kernel/pvclock.c (ffffffff81068411)
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
Inline callers:
  - arch/x86/kernel/pvclock.c:pvclock_resume
```
```
In kernel/fork.c (ffffffff81083d78)
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
  - kernel/fork.c:mm_init
```
```
In kernel/workqueue.c (ffffffff810a0fe0)
Location: arch/x86/include/asm/atomic64_64.h:31
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
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
Inline callers:
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/fair.c:alloc_fair_sched_group
```
```
In kernel/locking/mutex.c (ffffffff810d502a)
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
Inline callers:
  - kernel/locking/mutex.c:__mutex_init
```
```
In kernel/locking/rwsem-xadd.c (ffffffff810d6eca)
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
Inline callers:
  - kernel/locking/rwsem-xadd.c:__init_rwsem
```
```
In kernel/acct.c (ffffffff8111aece)
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
Inline callers:
  - kernel/acct.c:SyS_acct
```
```
In kernel/cgroup.c (ffffffff81129ec4)
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
Inline callers:
  - kernel/cgroup.c:copy_cgroup_ns
```
```
In kernel/cgroup_pids.c (ffffffff8112abde)
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
Inline callers:
  - kernel/cgroup_pids.c:pids_css_alloc
  - kernel/cgroup_pids.c:pids_css_alloc
```
```
In kernel/utsname.c (ffffffff8112f646)
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
Inline callers:
  - kernel/utsname.c:copy_utsname
```
```
In kernel/user_namespace.c (ffffffff81130a2c)
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In kernel/pid_namespace.c (ffffffff811316a3)
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In kernel/audit_tree.c (ffffffff8113ce32)
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
Inline callers:
  - kernel/audit_tree.c:alloc_chunk
```
```
In kernel/trace/ring_buffer.c (ffffffff8115ca7d)
Location: arch/x86/include/asm/atomic64_64.h:31
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
In kernel/trace/tracing_map.c (ffffffff8116b7f6)
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_sort_entries
  - kernel/trace/tracing_map.c:tracing_map_clear
  - kernel/trace/tracing_map.c:tracing_map_clear
  - kernel/trace/tracing_map.c:tracing_map_elt_clear
```
```
In kernel/events/core.c (ffffffff8119f2f2)
Location: arch/x86/include/asm/atomic64_64.h:31
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
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_aux_output_end
  - kernel/events/ring_buffer.c:perf_aux_output_end
  - kernel/events/ring_buffer.c:perf_aux_output_begin
```
```
In mm/slub.c (ffffffff8121fa9f)
Location: arch/x86/include/asm/atomic64_64.h:31
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
Location: arch/x86/include/asm/atomic64_64.h:31
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
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
```
```
In fs/file_table.c (ffffffff81247716)
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
Inline callers:
  - fs/file_table.c:get_empty_filp
```
```
In fs/namespace.c (ffffffff81267159)
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In fs/nsfs.c (ffffffff8127d519)
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
Inline callers:
  - fs/nsfs.c:ns_prune_dentry
```
```
In fs/ext4/super.c (ffffffff813027c9)
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/ext4/sysfs.c (ffffffff813298d5)
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_store
```
```
In ipc/namespace.c (ffffffff81379e90)
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
Inline callers:
  - ipc/namespace.c:copy_ipcs
```
```
In block/blk-ioc.c (ffffffff8141cd31)
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
Inline callers:
  - block/blk-ioc.c:create_task_io_context
```
```
In block/blk-cgroup.c (ffffffff81439e2e)
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_reset_stats
  - block/blk-cgroup.c:blkcg_reset_stats
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-cgroup.c:blkg_rwstat_read
```
```
In block/cfq-iosched.c (ffffffff81442516)
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_pd_alloc
  - block/cfq-iosched.c:cfq_pd_alloc
  - block/cfq-iosched.c:cfq_pd_alloc
  - block/cfq-iosched.c:cfq_pd_alloc
  - block/cfq-iosched.c:cfq_pd_alloc
  - block/cfq-iosched.c:cfqg_stats_reset
  - block/cfq-iosched.c:cfqg_stats_reset
  - block/cfq-iosched.c:cfqg_stats_reset
  - block/cfq-iosched.c:cfqg_stats_reset
  - block/cfq-iosched.c:blkg_rwstat_read
```
```
In lib/percpu-refcount.c (ffffffff81464e02)
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_init
```
```
In drivers/md/md.c (ffffffff81724d69)
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:do_md_stop
```
```
In drivers/firmware/efi/cper.c (ffffffff8176a39e)
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_next_record_id
```
```
In net/core/sock.c (ffffffff81797b39)
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
```
```
In net/core/net_namespace.c (ffffffff817a46e5)
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
Inline callers:
  - net/core/net_namespace.c:net_ns_net_init
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff817ff810)
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81800997)
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_clone_lock
```
```
In net/ipv4/tcp_input.c (ffffffff81807a4f)
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/unix/af_unix.c (ffffffff8185c967)
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
```
```
In net/packet/af_packet.c (ffffffff818ac10c)
Location: arch/x86/include/asm/atomic64_64.h:31
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
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_perf_event_set_period
```
```
In arch/x86/events/amd/uncore.c (ffffffff810081a4)
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_read
```
```
In arch/x86/events/amd/ibs.c (ffffffff810097d0)
Location: arch/x86/include/asm/atomic64_64.h:31
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
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
```
```
In arch/x86/events/intel/core.c (ffffffff8100c2f8)
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_save_and_restart
```
```
In arch/x86/events/intel/bts.c (ffffffff8100ccca)
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_update
```
```
In arch/x86/events/intel/pt.c (ffffffff81011447)
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_buffer_reset_offsets
  - arch/x86/events/intel/pt.c:pt_buffer_reset_offsets
  - arch/x86/events/intel/pt.c:pt_update_head
```
```
In arch/x86/events/intel/uncore.c (ffffffff81012e95)
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
```
```
In arch/x86/events/intel/uncore_snb.c (ffffffff81016928)
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_event_start
```
```
In arch/x86/kernel/pvclock.c (ffffffff81067741)
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
Inline callers:
  - arch/x86/kernel/pvclock.c:pvclock_resume
```
```
In kernel/fork.c (ffffffff81080ca8)
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
  - kernel/fork.c:mm_init
```
```
In kernel/workqueue.c (ffffffff8109e549)
Location: arch/x86/include/asm/atomic64_64.h:31
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
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
Inline callers:
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/fair.c:alloc_fair_sched_group
```
```
In kernel/locking/mutex.c (ffffffff810d416a)
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
Inline callers:
  - kernel/locking/mutex.c:__mutex_init
```
```
In kernel/locking/rwsem-xadd.c (ffffffff810d5f2a)
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
Inline callers:
  - kernel/locking/rwsem-xadd.c:__init_rwsem
```
```
In kernel/acct.c (ffffffff8111caee)
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
Inline callers:
  - kernel/acct.c:SyS_acct
```
```
In kernel/cgroup/namespace.c (ffffffff81128eda)
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
```
```
In kernel/cgroup/pids.c (ffffffff8112b8fe)
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_css_alloc
  - kernel/cgroup/pids.c:pids_css_alloc
```
```
In kernel/utsname.c (ffffffff81130bc4)
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
Inline callers:
  - kernel/utsname.c:copy_utsname
```
```
In kernel/user_namespace.c (ffffffff8113206d)
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In kernel/pid_namespace.c (ffffffff81132ba2)
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In kernel/audit_tree.c (ffffffff8113e4a9)
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
Inline callers:
  - kernel/audit_tree.c:alloc_chunk
```
```
In kernel/trace/ring_buffer.c (ffffffff8115face)
Location: arch/x86/include/asm/atomic64_64.h:31
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
In kernel/trace/tracing_map.c (ffffffff8116e845)
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_sort_entries
  - kernel/trace/tracing_map.c:tracing_map_clear
  - kernel/trace/tracing_map.c:tracing_map_clear
  - kernel/trace/tracing_map.c:tracing_map_elt_clear
```
```
In kernel/events/core.c (ffffffff811a90e3)
Location: arch/x86/include/asm/atomic64_64.h:31
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
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_aux_output_end
  - kernel/events/ring_buffer.c:perf_aux_output_end
  - kernel/events/ring_buffer.c:perf_aux_output_begin
```
```
In mm/slub.c (ffffffff8122b73f)
Location: arch/x86/include/asm/atomic64_64.h:31
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
Location: arch/x86/include/asm/atomic64_64.h:31
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
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
```
```
In fs/file_table.c (ffffffff81252f1f)
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
Inline callers:
  - fs/file_table.c:get_empty_filp
```
```
In fs/namespace.c (ffffffff812749a9)
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In fs/nsfs.c (ffffffff8128b0a9)
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
Inline callers:
  - fs/nsfs.c:ns_prune_dentry
```
```
In fs/ext4/super.c (ffffffff813376ec)
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/ext4/sysfs.c (ffffffff813394c1)
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_store
```
```
In ipc/namespace.c (ffffffff8138da9c)
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
Inline callers:
  - ipc/namespace.c:copy_ipcs
```
```
In block/blk-ioc.c (ffffffff8142ad91)
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
Inline callers:
  - block/blk-ioc.c:create_task_io_context
```
```
In block/blk-cgroup.c (ffffffff8144769f)
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_reset_stats
  - block/blk-cgroup.c:blkcg_reset_stats
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-cgroup.c:blkg_rwstat_read
```
```
In block/cfq-iosched.c (ffffffff8145172f)
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_pd_alloc
  - block/cfq-iosched.c:cfq_pd_alloc
  - block/cfq-iosched.c:cfq_pd_alloc
  - block/cfq-iosched.c:cfq_pd_alloc
  - block/cfq-iosched.c:cfq_pd_alloc
  - block/cfq-iosched.c:cfqg_stats_reset
  - block/cfq-iosched.c:cfqg_stats_reset
  - block/cfq-iosched.c:cfqg_stats_reset
  - block/cfq-iosched.c:cfqg_stats_reset
  - block/cfq-iosched.c:blkg_rwstat_read
```
```
In lib/percpu-refcount.c (ffffffff81469e42)
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_init
```
```
In drivers/iommu/amd_iommu.c (ffffffff815c6f74)
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc
```
```
In drivers/md/md.c (ffffffff8173cc71)
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:do_md_stop
```
```
In drivers/firmware/efi/cper.c (ffffffff8178872e)
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_next_record_id
```
```
In net/core/sock.c (ffffffff817b572d)
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
```
```
In net/core/net_namespace.c (ffffffff817c2885)
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
Inline callers:
  - net/core/net_namespace.c:net_ns_net_init
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff8181fa1e)
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81820577)
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_clone_lock
```
```
In net/ipv4/tcp_input.c (ffffffff818283ff)
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/unix/af_unix.c (ffffffff818810f5)
Location: arch/x86/include/asm/atomic64_64.h:31
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
```
```
In net/packet/af_packet.c (ffffffff818d2202)
Location: arch/x86/include/asm/atomic64_64.h:31
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
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_perf_event_set_period
```
```
In arch/x86/events/amd/uncore.c (ffffffff81008624)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_read
```
```
In arch/x86/events/amd/ibs.c (ffffffff81009f05)
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
In arch/x86/events/msr.c (ffffffff8100a93d)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
```
```
In arch/x86/events/intel/core.c (ffffffff8100c898)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_save_and_restart
```
```
In arch/x86/events/intel/bts.c (ffffffff8100d26a)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_update
```
```
In arch/x86/events/intel/pt.c (ffffffff81011b87)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_buffer_reset_offsets
  - arch/x86/events/intel/pt.c:pt_buffer_reset_offsets
  - arch/x86/events/intel/pt.c:pt_update_head
```
```
In arch/x86/events/intel/uncore.c (ffffffff810136ab)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
```
```
In arch/x86/events/intel/uncore_snb.c (ffffffff810171ac)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_event_start
```
```
In arch/x86/kernel/pvclock.c (ffffffff8106b9a1)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - arch/x86/kernel/pvclock.c:pvclock_resume
```
```
In kernel/fork.c (ffffffff81087618)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
  - kernel/fork.c:mm_init
```
```
In kernel/workqueue.c (ffffffff810a6be7)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/workqueue.c:insert_work
  - kernel/workqueue.c:set_work_pool_and_clear_pending
```
```
In kernel/locking/mutex.c (ffffffff810dc0ba)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/locking/mutex.c:__mutex_init
```
```
In kernel/locking/rwsem-xadd.c (ffffffff810ddeea)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/locking/rwsem-xadd.c:__init_rwsem
```
```
In kernel/acct.c (ffffffff8112820e)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/acct.c:SyS_acct
```
```
In kernel/cgroup/namespace.c (ffffffff81135b6e)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
```
```
In kernel/cgroup/pids.c (ffffffff811386fe)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_css_alloc
  - kernel/cgroup/pids.c:pids_css_alloc
```
```
In kernel/utsname.c (ffffffff8113db15)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/utsname.c:copy_utsname
```
```
In kernel/user_namespace.c (ffffffff8113edec)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In kernel/pid_namespace.c (ffffffff8113f98f)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In kernel/audit_tree.c (ffffffff8114b2a9)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/audit_tree.c:alloc_chunk
```
```
In kernel/trace/ring_buffer.c (ffffffff8116cb9e)
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
In kernel/trace/tracing_map.c (ffffffff8117b927)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_sort_entries
  - kernel/trace/tracing_map.c:tracing_map_clear
  - kernel/trace/tracing_map.c:tracing_map_clear
  - kernel/trace/tracing_map.c:tracing_map_elt_clear
```
```
In kernel/events/core.c (ffffffff811bc923)
Location: arch/x86/include/asm/atomic64_64.h:32
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
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_aux_output_end
  - kernel/events/ring_buffer.c:perf_aux_output_begin
```
```
In mm/vmstat.c (ffffffff811f5520)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
```
```
In mm/swap_state.c (ffffffff81225e53)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - mm/swap_state.c:swap_readahead_detect
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/slub.c (ffffffff81246e41)
Location: arch/x86/include/asm/atomic64_64.h:32
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
In mm/hugetlb_cgroup.c (ffffffff81263a09)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
```
```
In fs/file_table.c (ffffffff8127501f)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - fs/file_table.c:get_empty_filp
```
```
In fs/namespace.c (ffffffff812972d9)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In fs/nsfs.c (ffffffff812adbe9)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - fs/nsfs.c:ns_prune_dentry
```
```
In fs/ext4/super.c (ffffffff8135bbea)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/ext4/sysfs.c (ffffffff8135d831)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_store
```
```
In ipc/namespace.c (ffffffff813b2ebb)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - ipc/namespace.c:copy_ipcs
```
```
In block/blk-ioc.c (ffffffff81455f81)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - block/blk-ioc.c:create_task_io_context
```
```
In block/blk-cgroup.c (ffffffff8147428f)
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
In block/cfq-iosched.c (ffffffff8147c65d)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_pd_alloc
  - block/cfq-iosched.c:cfq_pd_alloc
  - block/cfq-iosched.c:cfq_pd_alloc
  - block/cfq-iosched.c:cfq_pd_alloc
  - block/cfq-iosched.c:cfq_pd_alloc
  - block/cfq-iosched.c:cfqg_stats_reset
  - block/cfq-iosched.c:cfqg_stats_reset
  - block/cfq-iosched.c:cfqg_stats_reset
  - block/cfq-iosched.c:cfqg_stats_reset
  - block/cfq-iosched.c:blkg_rwstat_read
```
```
In lib/percpu-refcount.c (ffffffff81496112)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_init
```
```
In lib/genalloc.c (ffffffff814a0890)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_add_virt
```
```
In drivers/iommu/iova.c (ffffffff816291e1)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
```
```
In drivers/md/md.c (ffffffff817ae839)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:do_md_stop
```
```
In drivers/firmware/efi/cper.c (ffffffff817febee)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_next_record_id
```
```
In net/core/sock.c (ffffffff8182dbea)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
```
```
In net/core/net_namespace.c (ffffffff8183c1c5)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - net/core/net_namespace.c:net_ns_net_init
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff8189e996)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
```
```
In net/ipv4/inet_connection_sock.c (ffffffff8189f537)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_clone_lock
```
```
In net/ipv4/tcp_input.c (ffffffff818a7913)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/unix/af_unix.c (ffffffff81902285)
Location: arch/x86/include/asm/atomic64_64.h:32
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
```
```
In net/packet/af_packet.c (ffffffff81956fd9)
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
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff810074f5)
Location: include/asm-generic/atomic-instrumented.h:37
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_setup_perfctr
```
```
In arch/x86/events/amd/uncore.c (ffffffff81008dd4)
Location: include/asm-generic/atomic-instrumented.h:37
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_read
```
```
In arch/x86/events/amd/ibs.c (ffffffff8100a396)
Location: include/asm-generic/atomic-instrumented.h:37
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
Location: include/asm-generic/atomic-instrumented.h:37
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_event_update
```
```
In arch/x86/events/intel/core.c (ffffffff8100cff8)
Location: include/asm-generic/atomic-instrumented.h:37
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_save_and_restart
```
```
In arch/x86/events/intel/bts.c (ffffffff8100d9da)
Location: include/asm-generic/atomic-instrumented.h:37
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_update
```
```
In arch/x86/events/intel/ds.c (ffffffff8100e7c1)
Location: include/asm-generic/atomic-instrumented.h:37
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pmu_save_and_restart_reload
```
```
In arch/x86/events/intel/pt.c (ffffffff81012579)
Location: include/asm-generic/atomic-instrumented.h:37
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_buffer_reset_offsets
  - arch/x86/events/intel/pt.c:pt_buffer_reset_offsets
  - arch/x86/events/intel/pt.c:pt_update_head
```
```
In arch/x86/events/intel/uncore.c (ffffffff81014011)
Location: include/asm-generic/atomic-instrumented.h:37
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
```
```
In arch/x86/kernel/pvclock.c (ffffffff8106e640)
Location: include/asm-generic/atomic-instrumented.h:37
Inline: True
Inline callers:
  - arch/x86/kernel/pvclock.c:pvclock_resume
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff826f2194)
Location: include/asm-generic/atomic-instrumented.h:37
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In kernel/fork.c (ffffffff8108ab37)
Location: include/asm-generic/atomic-instrumented.h:37
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
  - kernel/fork.c:mm_init
```
```
In kernel/workqueue.c (ffffffff810ac5e1)
Location: include/asm-generic/atomic-instrumented.h:37
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
Location: include/asm-generic/atomic-instrumented.h:37
Inline: True
Inline callers:
  - kernel/locking/mutex.c:__mutex_init
```
```
In kernel/locking/rwsem-xadd.c (ffffffff810e6555)
Location: include/asm-generic/atomic-instrumented.h:37
Inline: True
Inline callers:
  - kernel/locking/rwsem-xadd.c:__init_rwsem
```
```
In kernel/acct.c (ffffffff81136011)
Location: include/asm-generic/atomic-instrumented.h:37
Inline: True
Inline callers:
  - kernel/acct.c:acct_on
```
```
In kernel/cgroup/namespace.c (ffffffff8114446c)
Location: include/asm-generic/atomic-instrumented.h:37
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
```
```
In kernel/cgroup/pids.c (ffffffff81147017)
Location: include/asm-generic/atomic-instrumented.h:37
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_css_alloc
  - kernel/cgroup/pids.c:pids_css_alloc
```
```
In kernel/utsname.c (ffffffff8114c4a9)
Location: include/asm-generic/atomic-instrumented.h:37
Inline: True
Inline callers:
  - kernel/utsname.c:copy_utsname
```
```
In kernel/user_namespace.c (ffffffff8114d729)
Location: include/asm-generic/atomic-instrumented.h:37
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In kernel/pid_namespace.c (ffffffff8114e2a6)
Location: include/asm-generic/atomic-instrumented.h:37
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In kernel/audit_tree.c (ffffffff81159b16)
Location: include/asm-generic/atomic-instrumented.h:37
Inline: True
Inline callers:
  - kernel/audit_tree.c:alloc_chunk
```
```
In kernel/trace/ring_buffer.c (ffffffff8117bb5d)
Location: include/asm-generic/atomic-instrumented.h:37
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
Location: include/asm-generic/atomic-instrumented.h:37
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
Location: include/asm-generic/atomic-instrumented.h:37
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
Location: include/asm-generic/atomic-instrumented.h:37
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_aux_output_end
  - kernel/events/ring_buffer.c:perf_aux_output_begin
```
```
In mm/vmstat.c (ffffffff81216826)
Location: include/asm-generic/atomic-instrumented.h:37
Inline: True
Inline callers:
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
```
```
In mm/swap_state.c (ffffffff81248520)
Location: include/asm-generic/atomic-instrumented.h:37
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/slub.c (ffffffff81269de2)
Location: include/asm-generic/atomic-instrumented.h:37
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
Location: include/asm-generic/atomic-instrumented.h:37
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
Location: include/asm-generic/atomic-instrumented.h:37
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
```
```
In fs/file_table.c (ffffffff8129b8db)
Location: include/asm-generic/atomic-instrumented.h:37
Inline: True
Inline callers:
  - fs/file_table.c:get_empty_filp
```
```
In fs/namespace.c (ffffffff812bd4c5)
Location: include/asm-generic/atomic-instrumented.h:37
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In fs/nsfs.c (ffffffff812d5999)
Location: include/asm-generic/atomic-instrumented.h:37
Inline: True
Inline callers:
  - fs/nsfs.c:ns_prune_dentry
```
```
In fs/ext4/inode.c (ffffffff81354ad0)
Location: include/asm-generic/atomic-instrumented.h:37
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_iget
```
```
In fs/ext4/ioctl.c (ffffffff8135c43d)
Location: include/asm-generic/atomic-instrumented.h:37
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/super.c (ffffffff8138a696)
Location: include/asm-generic/atomic-instrumented.h:37
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_alloc_inode
```
```
In fs/ext4/sysfs.c (ffffffff8138bfb9)
Location: include/asm-generic/atomic-instrumented.h:37
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_store
```
```
In fs/ext4/xattr.c (ffffffff8138dfcd)
Location: include/asm-generic/atomic-instrumented.h:37
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
```
```
In fs/fat/inode.c (ffffffff813aed32)
Location: include/asm-generic/atomic-instrumented.h:37
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_build_inode
```
```
In ipc/namespace.c (ffffffff813e35e4)
Location: include/asm-generic/atomic-instrumented.h:37
Inline: True
Inline callers:
  - ipc/namespace.c:copy_ipcs
```
```
In block/blk-ioc.c (ffffffff814893cb)
Location: include/asm-generic/atomic-instrumented.h:37
Inline: True
Inline callers:
  - block/blk-ioc.c:create_task_io_context
```
```
In block/blk-cgroup.c (ffffffff814a8c9f)
Location: include/asm-generic/atomic-instrumented.h:37
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
Location: include/asm-generic/atomic-instrumented.h:37
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
Location: include/asm-generic/atomic-instrumented.h:37
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_init
```
```
In lib/genalloc.c (ffffffff814d5a24)
Location: include/asm-generic/atomic-instrumented.h:37
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_add_virt
```
```
In drivers/iommu/iova.c (ffffffff81663ef5)
Location: include/asm-generic/atomic-instrumented.h:37
Inline: True
```
```
In drivers/md/md.c (ffffffff81800209)
Location: include/asm-generic/atomic-instrumented.h:37
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:do_md_stop
```
```
In drivers/firmware/efi/cper.c (ffffffff81848402)
Location: include/asm-generic/atomic-instrumented.h:37
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_next_record_id
```
```
In net/core/sock.c (ffffffff81877fad)
Location: include/asm-generic/atomic-instrumented.h:37
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
```
```
In net/core/net_namespace.c (ffffffff81886922)
Location: include/asm-generic/atomic-instrumented.h:37
Inline: True
Inline callers:
  - net/core/net_namespace.c:net_ns_net_init
```
```
In net/ipv4/ip_fragment.c (ffffffff818e899c)
Location: include/asm-generic/atomic-instrumented.h:37
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ipv4_frags_init_net
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff818f32d1)
Location: include/asm-generic/atomic-instrumented.h:37
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
```
```
In net/ipv4/inet_connection_sock.c (ffffffff818f3f4b)
Location: include/asm-generic/atomic-instrumented.h:37
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_clone_lock
```
```
In net/ipv4/tcp_input.c (ffffffff818fcaab)
Location: include/asm-generic/atomic-instrumented.h:37
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/unix/af_unix.c (ffffffff81959c2d)
Location: include/asm-generic/atomic-instrumented.h:37
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
```
```
In net/ipv6/reassembly.c (ffffffff81990325)
Location: include/asm-generic/atomic-instrumented.h:37
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frags_init_net
```
```
In net/packet/af_packet.c (ffffffff819b3abb)
Location: include/asm-generic/atomic-instrumented.h:37
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
Location: include/asm-generic/atomic-instrumented.h:37
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_setup_perfctr
```
```
In arch/x86/events/amd/uncore.c (ffffffff81008cf4)
Location: include/asm-generic/atomic-instrumented.h:37
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_read
```
```
In arch/x86/events/amd/ibs.c (ffffffff8100a2c6)
Location: include/asm-generic/atomic-instrumented.h:37
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
Location: include/asm-generic/atomic-instrumented.h:37
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_event_update
```
```
In arch/x86/events/intel/core.c (ffffffff8100d3c8)
Location: include/asm-generic/atomic-instrumented.h:37
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_save_and_restart
```
```
In arch/x86/events/intel/bts.c (ffffffff8100deaa)
Location: include/asm-generic/atomic-instrumented.h:37
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_update
```
```
In arch/x86/events/intel/ds.c (ffffffff8100ec91)
Location: include/asm-generic/atomic-instrumented.h:37
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pmu_save_and_restart_reload
```
```
In arch/x86/events/intel/pt.c (ffffffff81012c79)
Location: include/asm-generic/atomic-instrumented.h:37
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_buffer_reset_offsets
  - arch/x86/events/intel/pt.c:pt_buffer_reset_offsets
  - arch/x86/events/intel/pt.c:pt_update_head
```
```
In arch/x86/events/intel/uncore.c (ffffffff81014711)
Location: include/asm-generic/atomic-instrumented.h:37
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
```
```
In arch/x86/kernel/pvclock.c (ffffffff81074660)
Location: include/asm-generic/atomic-instrumented.h:37
Inline: True
Inline callers:
  - arch/x86/kernel/pvclock.c:pvclock_resume
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff828a91a4)
Location: include/asm-generic/atomic-instrumented.h:37
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In kernel/fork.c (ffffffff81092b3b)
Location: include/asm-generic/atomic-instrumented.h:37
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
  - kernel/fork.c:mm_init
```
```
In kernel/workqueue.c (ffffffff810b54c1)
Location: include/asm-generic/atomic-instrumented.h:37
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
Location: include/asm-generic/atomic-instrumented.h:37
Inline: True
Inline callers:
  - kernel/locking/mutex.c:__mutex_init
```
```
In kernel/locking/rwsem-xadd.c (ffffffff810f1ad5)
Location: include/asm-generic/atomic-instrumented.h:37
Inline: True
Inline callers:
  - kernel/locking/rwsem-xadd.c:__init_rwsem
```
```
In kernel/acct.c (ffffffff811417a1)
Location: include/asm-generic/atomic-instrumented.h:37
Inline: True
Inline callers:
  - kernel/acct.c:acct_on
```
```
In kernel/cgroup/namespace.c (ffffffff8114ff7c)
Location: include/asm-generic/atomic-instrumented.h:37
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
```
```
In kernel/cgroup/pids.c (ffffffff81152b97)
Location: include/asm-generic/atomic-instrumented.h:37
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_css_alloc
  - kernel/cgroup/pids.c:pids_css_alloc
```
```
In kernel/utsname.c (ffffffff811590c9)
Location: include/asm-generic/atomic-instrumented.h:37
Inline: True
Inline callers:
  - kernel/utsname.c:copy_utsname
```
```
In kernel/user_namespace.c (ffffffff8115a3e9)
Location: include/asm-generic/atomic-instrumented.h:37
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In kernel/pid_namespace.c (ffffffff8115af86)
Location: include/asm-generic/atomic-instrumented.h:37
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In kernel/audit_tree.c (ffffffff81166aad)
Location: include/asm-generic/atomic-instrumented.h:37
Inline: True
Inline callers:
  - kernel/audit_tree.c:alloc_chunk
```
```
In kernel/trace/ring_buffer.c (ffffffff81188b31)
Location: include/asm-generic/atomic-instrumented.h:37
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
Location: include/asm-generic/atomic-instrumented.h:37
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
Location: include/asm-generic/atomic-instrumented.h:37
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
Location: include/asm-generic/atomic-instrumented.h:37
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_aux_output_end
  - kernel/events/ring_buffer.c:perf_aux_output_begin
```
```
In mm/page_alloc.c (ffffffff828b944e)
Location: include/asm-generic/atomic-instrumented.h:37
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init_node
  - mm/page_alloc.c:free_area_init_core_hotplug
```
```
In mm/vmstat.c (ffffffff81229729)
Location: include/asm-generic/atomic-instrumented.h:37
Inline: True
Inline callers:
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
```
```
In mm/memblock.c (ffffffff828be4df)
Location: include/asm-generic/atomic-instrumented.h:37
Inline: True
Inline callers:
  - mm/memblock.c:reset_all_zones_managed_pages
```
```
In mm/swap_state.c (ffffffff8125caf4)
Location: include/asm-generic/atomic-instrumented.h:37
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/slub.c (ffffffff8127e6a2)
Location: include/asm-generic/atomic-instrumented.h:37
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
Location: include/asm-generic/atomic-instrumented.h:37
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
Location: include/asm-generic/atomic-instrumented.h:37
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
```
```
In fs/file_table.c (ffffffff812b07ed)
Location: include/asm-generic/atomic-instrumented.h:37
Inline: True
Inline callers:
  - fs/file_table.c:__alloc_file
```
```
In fs/namespace.c (ffffffff812d27d5)
Location: include/asm-generic/atomic-instrumented.h:37
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In fs/nsfs.c (ffffffff812ead69)
Location: include/asm-generic/atomic-instrumented.h:37
Inline: True
Inline callers:
  - fs/nsfs.c:ns_prune_dentry
```
```
In fs/ext4/inode.c (ffffffff8136ce22)
Location: include/asm-generic/atomic-instrumented.h:37
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/ioctl.c (ffffffff813748aa)
Location: include/asm-generic/atomic-instrumented.h:37
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/super.c (ffffffff813a303a)
Location: include/asm-generic/atomic-instrumented.h:37
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_alloc_inode
```
```
In fs/ext4/sysfs.c (ffffffff813a4b49)
Location: include/asm-generic/atomic-instrumented.h:37
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_store
```
```
In fs/ext4/xattr.c (ffffffff813a6568)
Location: include/asm-generic/atomic-instrumented.h:37
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
```
```
In fs/fat/inode.c (ffffffff813c7f11)
Location: include/asm-generic/atomic-instrumented.h:37
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_build_inode
```
```
In ipc/namespace.c (ffffffff813fdf54)
Location: include/asm-generic/atomic-instrumented.h:37
Inline: True
Inline callers:
  - ipc/namespace.c:copy_ipcs
```
```
In block/blk-ioc.c (ffffffff814a321b)
Location: include/asm-generic/atomic-instrumented.h:37
Inline: True
Inline callers:
  - block/blk-ioc.c:create_task_io_context
```
```
In block/blk-cgroup.c (ffffffff814c0af1)
Location: include/asm-generic/atomic-instrumented.h:37
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
Location: include/asm-generic/atomic-instrumented.h:37
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_init
```
```
In lib/genalloc.c (ffffffff814ea0af)
Location: include/asm-generic/atomic-instrumented.h:37
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_add_virt
```
```
In drivers/tty/tty_ldsem.c (ffffffff81637935)
Location: include/asm-generic/atomic-instrumented.h:37
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:__init_ldsem
```
```
In drivers/iommu/iova.c (ffffffff81682785)
Location: include/asm-generic/atomic-instrumented.h:37
Inline: True
```
```
In drivers/md/md.c (ffffffff8182c3de)
Location: include/asm-generic/atomic-instrumented.h:37
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:do_md_stop
```
```
In drivers/firmware/efi/cper.c (ffffffff8187465b)
Location: include/asm-generic/atomic-instrumented.h:37
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_next_record_id
  - drivers/firmware/efi/cper.c:cper_next_record_id
```
```
In net/core/sock.c (ffffffff8189848d)
Location: include/asm-generic/atomic-instrumented.h:37
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
```
```
In net/core/net_namespace.c (ffffffff818a7012)
Location: include/asm-generic/atomic-instrumented.h:37
Inline: True
Inline callers:
  - net/core/net_namespace.c:net_ns_net_init
```
```
In net/ipv4/ip_fragment.c (ffffffff81915cec)
Location: include/asm-generic/atomic-instrumented.h:37
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ipv4_frags_init_net
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81920df1)
Location: include/asm-generic/atomic-instrumented.h:37
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81921a6b)
Location: include/asm-generic/atomic-instrumented.h:37
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_clone_lock
```
```
In net/ipv4/tcp_input.c (ffffffff8192ac1d)
Location: include/asm-generic/atomic-instrumented.h:37
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/unix/af_unix.c (ffffffff8198e7ae)
Location: include/asm-generic/atomic-instrumented.h:37
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
```
```
In net/ipv6/reassembly.c (ffffffff819c6b85)
Location: include/asm-generic/atomic-instrumented.h:37
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frags_init_net
```
```
In net/packet/af_packet.c (ffffffff819eaae8)
Location: include/asm-generic/atomic-instrumented.h:37
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
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_setup_perfctr
```
```
In arch/x86/events/amd/uncore.c (ffffffff81009184)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_read
```
```
In arch/x86/events/amd/ibs.c (ffffffff8100a7b7)
Location: include/asm-generic/atomic-instrumented.h:852
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
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_event_update
```
```
In arch/x86/events/intel/core.c (ffffffff8100dc5e)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_save_and_restart
```
```
In arch/x86/events/intel/bts.c (ffffffff8100e779)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_update
```
```
In arch/x86/events/intel/ds.c (ffffffff8100f589)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pmu_save_and_restart_reload
```
```
In arch/x86/events/intel/pt.c (ffffffff81014019)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_buffer_reset_offsets
  - arch/x86/events/intel/pt.c:pt_buffer_reset_offsets
  - arch/x86/events/intel/pt.c:pt_update_head
```
```
In arch/x86/events/intel/uncore.c (ffffffff81015b91)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
```
```
In arch/x86/kernel/pvclock.c (ffffffff810781c0)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - arch/x86/kernel/pvclock.c:pvclock_resume
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff828c198b)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In kernel/fork.c (ffffffff81096b1d)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
  - kernel/fork.c:mm_init
  - kernel/fork.c:mm_init
```
```
In kernel/workqueue.c (ffffffff810bcfc0)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/workqueue.c:insert_work
  - kernel/workqueue.c:set_work_pool_and_clear_pending
```
```
In kernel/locking/mutex.c (ffffffff810f76d5)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - kernel/locking/mutex.c:__mutex_init
```
```
In kernel/locking/rwsem.c (ffffffff810f7db5)
Location: include/asm-generic/atomic-instrumented.h:852
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
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - kernel/acct.c:acct_on
```
```
In kernel/cgroup/namespace.c (ffffffff8115be7c)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
```
```
In kernel/cgroup/pids.c (ffffffff8115f1da)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_css_alloc
  - kernel/cgroup/pids.c:pids_css_alloc
```
```
In kernel/utsname.c (ffffffff811657fe)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - kernel/utsname.c:copy_utsname
```
```
In kernel/user_namespace.c (ffffffff81166ab7)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In kernel/pid_namespace.c (ffffffff81167636)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In kernel/audit_tree.c (ffffffff81173a0d)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - kernel/audit_tree.c:alloc_chunk
```
```
In kernel/trace/ring_buffer.c (ffffffff8119629c)
Location: include/asm-generic/atomic-instrumented.h:852
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
Location: include/asm-generic/atomic-instrumented.h:852
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
Location: include/asm-generic/atomic-instrumented.h:852
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
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
```
```
In mm/vmalloc.c (ffffffff812686a3)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - mm/vmalloc.c:set_iounmap_nonlazy
```
```
In mm/page_alloc.c (ffffffff828d6545)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init_node
  - mm/page_alloc.c:free_area_init_core_hotplug
```
```
In mm/memblock.c (ffffffff828d76ad)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - mm/memblock.c:reset_all_zones_managed_pages
```
```
In mm/swap_state.c (ffffffff81277cda)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/slub.c (ffffffff8129a571)
Location: include/asm-generic/atomic-instrumented.h:852
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
Location: include/asm-generic/atomic-instrumented.h:852
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
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
```
```
In fs/file_table.c (ffffffff812cd131)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - fs/file_table.c:__alloc_file
```
```
In fs/super.c (ffffffff812ce3c3)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - fs/super.c:thaw_super_locked
  - fs/super.c:thaw_super_locked
  - fs/super.c:freeze_super
```
```
In fs/namespace.c (ffffffff812efa32)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In fs/nsfs.c (ffffffff813097d9)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - fs/nsfs.c:ns_prune_dentry
```
```
In fs/aio.c (0)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
```
```
In fs/io_uring.c (0)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
```
```
In fs/ext4/inode.c (ffffffff813963cf)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/ioctl.c (ffffffff8139d386)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/super.c (ffffffff813cd270)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_alloc_inode
```
```
In fs/ext4/sysfs.c (ffffffff813cee0f)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_store
```
```
In fs/ext4/xattr.c (ffffffff813d0dc5)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
```
```
In fs/fat/inode.c (ffffffff813f2afa)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_build_inode
```
```
In fs/fuse/inode.c (ffffffff81412d54)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_conn_init
  - fs/fuse/inode.c:fuse_conn_init
```
```
In ipc/namespace.c (ffffffff8142a584)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - ipc/namespace.c:copy_ipcs
```
```
In block/blk-ioc.c (ffffffff814d12d6)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - block/blk-ioc.c:create_task_io_context
```
```
In block/blk-cgroup.c (ffffffff814ef340)
Location: include/asm-generic/atomic-instrumented.h:852
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
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_init
```
```
In lib/genalloc.c (ffffffff81516d6e)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_add_owner
```
```
In drivers/tty/tty_ldsem.c (ffffffff8166bc05)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:__init_ldsem
```
```
In drivers/iommu/iova.c (ffffffff816b9b35)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - drivers/iommu/iova.c:init_iova_flush_queue
  - drivers/iommu/iova.c:init_iova_flush_queue
```
```
In drivers/md/md.c (ffffffff8186e988)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:do_md_stop
```
```
In drivers/firmware/efi/cper.c (ffffffff818b88bb)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_next_record_id
  - drivers/firmware/efi/cper.c:cper_next_record_id
```
```
In net/core/net_namespace.c (ffffffff818f2712)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - net/core/net_namespace.c:net_ns_net_init
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff819837b9)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81984424)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_clone_lock
```
```
In net/ipv4/tcp_input.c (ffffffff8198de79)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/unix/af_unix.c (ffffffff819f9f0b)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
```
```
In net/packet/af_packet.c (ffffffff81a59437)
Location: include/asm-generic/atomic-instrumented.h:852
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
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_setup_perfctr
```
```
In arch/x86/events/amd/uncore.c (ffffffff81009584)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_read
```
```
In arch/x86/events/amd/ibs.c (ffffffff8100ad86)
Location: include/asm-generic/atomic-instrumented.h:852
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
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_event_update
```
```
In arch/x86/events/intel/core.c (ffffffff8100e29e)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_save_and_restart
```
```
In arch/x86/events/intel/bts.c (ffffffff8100ec49)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_update
```
```
In arch/x86/events/intel/ds.c (ffffffff8100fc51)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pmu_save_and_restart_reload
  - arch/x86/events/intel/ds.c:intel_pmu_save_and_restart_reload
```
```
In arch/x86/events/intel/pt.c (ffffffff81014ac0)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_buffer_reset_offsets
  - arch/x86/events/intel/pt.c:pt_buffer_reset_offsets
  - arch/x86/events/intel/pt.c:pt_update_head
```
```
In arch/x86/events/intel/uncore.c (ffffffff81016551)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
```
```
In arch/x86/kernel/pvclock.c (ffffffff81079230)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - arch/x86/kernel/pvclock.c:pvclock_resume
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff828c7e04)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff810991fa)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:param_set_local64
```
```
In kernel/fork.c (ffffffff8109d35d)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
  - kernel/fork.c:mm_init
  - kernel/fork.c:mm_init
```
```
In kernel/workqueue.c (ffffffff810c1541)
Location: include/asm-generic/atomic-instrumented.h:852
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
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - kernel/locking/mutex.c:__mutex_init
```
```
In kernel/locking/rwsem.c (ffffffff81103be5)
Location: include/asm-generic/atomic-instrumented.h:852
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
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - kernel/acct.c:acct_on
```
```
In kernel/cgroup/namespace.c (ffffffff81167a9c)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
```
```
In kernel/cgroup/pids.c (ffffffff8116aa39)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_max_write
  - kernel/cgroup/pids.c:pids_css_alloc
  - kernel/cgroup/pids.c:pids_css_alloc
  - kernel/cgroup/pids.c:pids_css_alloc
```
```
In kernel/utsname.c (ffffffff811716be)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - kernel/utsname.c:copy_utsname
```
```
In kernel/user_namespace.c (ffffffff81172977)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In kernel/pid_namespace.c (ffffffff811734f6)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In kernel/audit_tree.c (ffffffff8117f87d)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - kernel/audit_tree.c:alloc_chunk
```
```
In kernel/trace/ring_buffer.c (ffffffff811a1c6c)
Location: include/asm-generic/atomic-instrumented.h:852
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
Location: include/asm-generic/atomic-instrumented.h:852
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
Location: include/asm-generic/atomic-instrumented.h:852
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
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
```
```
In mm/vmalloc.c (ffffffff81276ff3)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - mm/vmalloc.c:set_iounmap_nonlazy
```
```
In mm/page_alloc.c (ffffffff828de9d4)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init_node
  - mm/page_alloc.c:free_area_init_core_hotplug
```
```
In mm/memblock.c (ffffffff828dfb1e)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - mm/memblock.c:reset_all_zones_managed_pages
```
```
In mm/swap_state.c (ffffffff812877ca)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/slub.c (ffffffff812aa431)
Location: include/asm-generic/atomic-instrumented.h:852
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
Location: include/asm-generic/atomic-instrumented.h:852
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
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
```
```
In fs/file_table.c (ffffffff812deb51)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - fs/file_table.c:__alloc_file
```
```
In fs/super.c (ffffffff812dfe73)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - fs/super.c:thaw_super_locked
  - fs/super.c:thaw_super_locked
  - fs/super.c:freeze_super
```
```
In fs/inode.c (ffffffff812fba8a)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - fs/inode.c:inode_init_always
```
```
In fs/namespace.c (ffffffff81301502)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In fs/nsfs.c (ffffffff8131c849)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - fs/nsfs.c:ns_prune_dentry
```
```
In fs/aio.c (0)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
```
```
In fs/io_uring.c (0)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
```
```
In fs/ext4/inode.c (ffffffff813aedd1)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/ioctl.c (ffffffff813b5df6)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/super.c (ffffffff813e674c)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_alloc_inode
```
```
In fs/ext4/sysfs.c (ffffffff813e84df)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_store
```
```
In fs/ext4/xattr.c (ffffffff813ea495)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
```
```
In fs/fat/inode.c (ffffffff8140cabb)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_build_inode
```
```
In fs/fuse/inode.c (ffffffff8142ca44)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_conn_init
  - fs/fuse/inode.c:fuse_conn_init
```
```
In ipc/namespace.c (ffffffff814442b4)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - ipc/namespace.c:copy_ipcs
```
```
In block/blk-ioc.c (ffffffff814ea686)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - block/blk-ioc.c:create_task_io_context
```
```
In block/blk-cgroup.c (ffffffff815087d0)
Location: include/asm-generic/atomic-instrumented.h:852
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
Location: include/asm-generic/atomic-instrumented.h:852
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
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_init
```
```
In lib/genalloc.c (ffffffff815377ae)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_add_owner
```
```
In drivers/tty/tty_ldsem.c (ffffffff8168e275)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:__init_ldsem
```
```
In drivers/iommu/iova.c (ffffffff816dc925)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - drivers/iommu/iova.c:init_iova_flush_queue
  - drivers/iommu/iova.c:init_iova_flush_queue
```
```
In drivers/md/md.c (ffffffff818a0765)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:do_md_stop
```
```
In drivers/firmware/efi/cper.c (ffffffff818eb2bb)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_next_record_id
  - drivers/firmware/efi/cper.c:cper_next_record_id
```
```
In net/core/net_namespace.c (ffffffff81924675)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - net/core/net_namespace.c:net_ns_net_init
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff819b9fa9)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819babd4)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_clone_lock
```
```
In net/ipv4/tcp_input.c (ffffffff819c4a49)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/unix/af_unix.c (ffffffff81a30b8b)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
```
```
In net/packet/af_packet.c (ffffffff81a8f547)
Location: include/asm-generic/atomic-instrumented.h:852
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
Location: include/asm-generic/atomic-instrumented.h:853
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_setup_perfctr
```
```
In arch/x86/events/amd/uncore.c (ffffffff8100a734)
Location: include/asm-generic/atomic-instrumented.h:853
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_read
```
```
In arch/x86/events/amd/ibs.c (ffffffff8100c000)
Location: include/asm-generic/atomic-instrumented.h:853
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
Location: include/asm-generic/atomic-instrumented.h:853
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_event_update
```
```
In arch/x86/events/intel/core.c (ffffffff8100f5d0)
Location: include/asm-generic/atomic-instrumented.h:853
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:handle_pmi_common
```
```
In arch/x86/events/intel/bts.c (ffffffff8100fff9)
Location: include/asm-generic/atomic-instrumented.h:853
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_update
```
```
In arch/x86/events/intel/ds.c (ffffffff810112b1)
Location: include/asm-generic/atomic-instrumented.h:853
Inline: True
```
```
In arch/x86/events/intel/pt.c (ffffffff81015f91)
Location: include/asm-generic/atomic-instrumented.h:853
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_buffer_reset_offsets
  - arch/x86/events/intel/pt.c:pt_buffer_reset_offsets
  - arch/x86/events/intel/pt.c:pt_update_head
  - arch/x86/events/intel/pt.c:pt_update_head
```
```
In arch/x86/events/intel/uncore.c (ffffffff81018aa1)
Location: include/asm-generic/atomic-instrumented.h:853
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
```
```
In arch/x86/kernel/pvclock.c (ffffffff81080510)
Location: include/asm-generic/atomic-instrumented.h:853
Inline: True
Inline callers:
  - arch/x86/kernel/pvclock.c:pvclock_resume
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff82ceac4a)
Location: include/asm-generic/atomic-instrumented.h:853
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff8109e88a)
Location: include/asm-generic/atomic-instrumented.h:853
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:param_set_local64
```
```
In kernel/fork.c (ffffffff810a41bd)
Location: include/asm-generic/atomic-instrumented.h:853
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
  - kernel/fork.c:mm_init
  - kernel/fork.c:mm_init
```
```
In kernel/workqueue.c (ffffffff810ca9a1)
Location: include/asm-generic/atomic-instrumented.h:853
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
Location: include/asm-generic/atomic-instrumented.h:853
Inline: True
Inline callers:
  - kernel/locking/mutex.c:__mutex_init
```
```
In kernel/locking/rwsem.c (ffffffff8110e775)
Location: include/asm-generic/atomic-instrumented.h:853
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
Location: include/asm-generic/atomic-instrumented.h:853
Inline: True
Inline callers:
  - kernel/time/namespace.c:clone_time_ns
```
```
In kernel/acct.c (ffffffff81168e2e)
Location: include/asm-generic/atomic-instrumented.h:853
Inline: True
Inline callers:
  - kernel/acct.c:acct_on
```
```
In kernel/cgroup/namespace.c (ffffffff811793f7)
Location: include/asm-generic/atomic-instrumented.h:853
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
```
```
In kernel/cgroup/pids.c (ffffffff8117c579)
Location: include/asm-generic/atomic-instrumented.h:853
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_max_write
  - kernel/cgroup/pids.c:pids_css_alloc
  - kernel/cgroup/pids.c:pids_css_alloc
  - kernel/cgroup/pids.c:pids_css_alloc
```
```
In kernel/utsname.c (ffffffff811832eb)
Location: include/asm-generic/atomic-instrumented.h:853
Inline: True
Inline callers:
  - kernel/utsname.c:clone_uts_ns
```
```
In kernel/user_namespace.c (ffffffff811847d7)
Location: include/asm-generic/atomic-instrumented.h:853
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In kernel/pid_namespace.c (ffffffff81184fd8)
Location: include/asm-generic/atomic-instrumented.h:853
Inline: True
Inline callers:
  - kernel/pid_namespace.c:create_pid_namespace
```
```
In kernel/audit_tree.c (ffffffff81192a61)
Location: include/asm-generic/atomic-instrumented.h:853
Inline: True
Inline callers:
  - kernel/audit_tree.c:alloc_chunk
```
```
In kernel/trace/ring_buffer.c (ffffffff811b7d8b)
Location: include/asm-generic/atomic-instrumented.h:853
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
Location: include/asm-generic/atomic-instrumented.h:853
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
Location: include/asm-generic/atomic-instrumented.h:853
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
Location: include/asm-generic/atomic-instrumented.h:853
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
Location: include/asm-generic/atomic-instrumented.h:853
Inline: True
Inline callers:
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
```
```
In mm/vmalloc.c (ffffffff812abb63)
Location: include/asm-generic/atomic-instrumented.h:853
Inline: True
Inline callers:
  - mm/vmalloc.c:set_iounmap_nonlazy
```
```
In mm/page_alloc.c (ffffffff82cfb900)
Location: include/asm-generic/atomic-instrumented.h:853
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init_core
  - mm/page_alloc.c:free_area_init_core_hotplug
```
```
In mm/memblock.c (ffffffff82cfd0dc)
Location: include/asm-generic/atomic-instrumented.h:853
Inline: True
Inline callers:
  - mm/memblock.c:reset_all_zones_managed_pages
```
```
In mm/swap_state.c (ffffffff812b89cf)
Location: include/asm-generic/atomic-instrumented.h:853
Inline: True
Inline callers:
  - mm/swap_state.c:swap_ra_info
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/slub.c (ffffffff812df144)
Location: include/asm-generic/atomic-instrumented.h:853
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
Location: include/asm-generic/atomic-instrumented.h:853
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
Location: include/asm-generic/atomic-instrumented.h:853
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
```
```
In fs/file_table.c (ffffffff813159a1)
Location: include/asm-generic/atomic-instrumented.h:853
Inline: True
Inline callers:
  - fs/file_table.c:__alloc_file
```
```
In fs/inode.c (ffffffff8133482a)
Location: include/asm-generic/atomic-instrumented.h:853
Inline: True
Inline callers:
  - fs/inode.c:inode_init_always
```
```
In fs/namespace.c (ffffffff8133abcf)
Location: include/asm-generic/atomic-instrumented.h:853
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In fs/nsfs.c (ffffffff81356599)
Location: include/asm-generic/atomic-instrumented.h:853
Inline: True
Inline callers:
  - fs/nsfs.c:ns_prune_dentry
```
```
In fs/ext4/inode.c (ffffffff813fae54)
Location: include/asm-generic/atomic-instrumented.h:853
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/ioctl.c (ffffffff814017f8)
Location: include/asm-generic/atomic-instrumented.h:853
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/super.c (ffffffff8143383e)
Location: include/asm-generic/atomic-instrumented.h:853
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_alloc_inode
```
```
In fs/ext4/sysfs.c (ffffffff81435527)
Location: include/asm-generic/atomic-instrumented.h:853
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_store
```
```
In fs/ext4/xattr.c (ffffffff814361a1)
Location: include/asm-generic/atomic-instrumented.h:853
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_create
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
```
```
In fs/fat/inode.c (ffffffff8145aa20)
Location: include/asm-generic/atomic-instrumented.h:853
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_build_inode
```
```
In fs/fuse/inode.c (ffffffff8147d49d)
Location: include/asm-generic/atomic-instrumented.h:853
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_conn_init
  - fs/fuse/inode.c:fuse_conn_init
```
```
In ipc/namespace.c (ffffffff81494ee5)
Location: include/asm-generic/atomic-instrumented.h:853
Inline: True
```
```
In block/blk-ioc.c (ffffffff81549626)
Location: include/asm-generic/atomic-instrumented.h:853
Inline: True
Inline callers:
  - block/blk-ioc.c:create_task_io_context
```
```
In block/blk-cgroup.c (ffffffff81569aea)
Location: include/asm-generic/atomic-instrumented.h:853
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_scale_delay
```
```
In block/blk-cgroup-rwstat.c (ffffffff8156c164)
Location: include/asm-generic/atomic-instrumented.h:853
Inline: True
Inline callers:
  - block/blk-cgroup-rwstat.c:blkg_rwstat_init
```
```
In block/blk-iocost.c (ffffffff81572594)
Location: include/asm-generic/atomic-instrumented.h:853
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
Location: include/asm-generic/atomic-instrumented.h:853
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_init
```
```
In lib/genalloc.c (ffffffff8159b8ae)
Location: include/asm-generic/atomic-instrumented.h:853
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_add_owner
```
```
In drivers/tty/tty_ldsem.c (ffffffff81740535)
Location: include/asm-generic/atomic-instrumented.h:853
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:__init_ldsem
```
```
In drivers/iommu/iova.c (ffffffff81793505)
Location: include/asm-generic/atomic-instrumented.h:853
Inline: True
Inline callers:
  - drivers/iommu/iova.c:init_iova_flush_queue
  - drivers/iommu/iova.c:init_iova_flush_queue
```
```
In drivers/iommu/amd/iommu.c (ffffffff81799cf7)
Location: include/asm-generic/atomic-instrumented.h:853
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_direct_map
  - drivers/iommu/amd/iommu.c:protection_domain_alloc
  - drivers/iommu/amd/iommu.c:protection_domain_free
  - drivers/iommu/amd/iommu.c:increase_address_space
```
```
In drivers/md/md.c (ffffffff81970451)
Location: include/asm-generic/atomic-instrumented.h:853
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:do_md_stop
```
```
In drivers/firmware/efi/cper.c (ffffffff819be9af)
Location: include/asm-generic/atomic-instrumented.h:853
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_next_record_id
  - drivers/firmware/efi/cper.c:cper_next_record_id
```
```
In net/core/net_namespace.c (ffffffff819f7eb5)
Location: include/asm-generic/atomic-instrumented.h:853
Inline: True
Inline callers:
  - net/core/net_namespace.c:net_ns_net_init
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81aa4a29)
Location: include/asm-generic/atomic-instrumented.h:853
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81aa5466)
Location: include/asm-generic/atomic-instrumented.h:853
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_clone_lock
```
```
In net/ipv4/tcp_input.c (ffffffff81ab0b56)
Location: include/asm-generic/atomic-instrumented.h:853
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/unix/af_unix.c (ffffffff81b24dbb)
Location: include/asm-generic/atomic-instrumented.h:853
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
```
```
In net/packet/af_packet.c (ffffffff81b8a274)
Location: include/asm-generic/atomic-instrumented.h:853
Inline: True
Inline callers:
  - net/packet/af_packet.c:fanout_add
  - net/packet/af_packet.c:fanout_add
  - net/packet/af_packet.c:fanout_add
```
```
In net/mptcp/protocol.c (ffffffff81bad9a2)
Location: include/asm-generic/atomic-instrumented.h:853
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
Location: include/asm-generic/atomic-instrumented.h:853
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_setup_perfctr
```
```
In arch/x86/events/amd/uncore.c (ffffffff81009594)
Location: include/asm-generic/atomic-instrumented.h:853
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_read
```
```
In arch/x86/events/amd/ibs.c (ffffffff8100afb5)
Location: include/asm-generic/atomic-instrumented.h:853
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
Location: include/asm-generic/atomic-instrumented.h:853
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_event_update
```
```
In arch/x86/events/intel/core.c (ffffffff8100ebf1)
Location: include/asm-generic/atomic-instrumented.h:853
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:handle_pmi_common
```
```
In arch/x86/events/intel/bts.c (ffffffff8100f559)
Location: include/asm-generic/atomic-instrumented.h:853
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_update
```
```
In arch/x86/events/intel/ds.c (ffffffff810108e1)
Location: include/asm-generic/atomic-instrumented.h:853
Inline: True
```
```
In arch/x86/events/intel/pt.c (ffffffff81016431)
Location: include/asm-generic/atomic-instrumented.h:853
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_buffer_reset_offsets
  - arch/x86/events/intel/pt.c:pt_buffer_reset_offsets
  - arch/x86/events/intel/pt.c:pt_update_head
  - arch/x86/events/intel/pt.c:pt_update_head
```
```
In arch/x86/events/intel/uncore.c (ffffffff81019221)
Location: include/asm-generic/atomic-instrumented.h:853
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
```
```
In arch/x86/kernel/pvclock.c (ffffffff81080120)
Location: include/asm-generic/atomic-instrumented.h:853
Inline: True
Inline callers:
  - arch/x86/kernel/pvclock.c:pvclock_resume
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff82fd8495)
Location: include/asm-generic/atomic-instrumented.h:853
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff8109a46a)
Location: include/asm-generic/atomic-instrumented.h:853
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:param_set_local64
```
```
In kernel/fork.c (ffffffff8109fdd1)
Location: include/asm-generic/atomic-instrumented.h:853
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
  - kernel/fork.c:mm_init
  - kernel/fork.c:mm_init
```
```
In kernel/workqueue.c (ffffffff810c5ad1)
Location: include/asm-generic/atomic-instrumented.h:853
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
Location: include/asm-generic/atomic-instrumented.h:853
Inline: True
Inline callers:
  - kernel/locking/mutex.c:__mutex_init
```
```
In kernel/locking/rwsem.c (ffffffff8110b9f5)
Location: include/asm-generic/atomic-instrumented.h:853
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
Location: include/asm-generic/atomic-instrumented.h:853
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
Location: include/asm-generic/atomic-instrumented.h:853
Inline: True
Inline callers:
  - kernel/time/namespace.c:clone_time_ns
```
```
In kernel/acct.c (ffffffff811654be)
Location: include/asm-generic/atomic-instrumented.h:853
Inline: True
Inline callers:
  - kernel/acct.c:acct_on
```
```
In kernel/cgroup/namespace.c (ffffffff8117610b)
Location: include/asm-generic/atomic-instrumented.h:853
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
```
```
In kernel/cgroup/pids.c (ffffffff81179429)
Location: include/asm-generic/atomic-instrumented.h:853
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_max_write
  - kernel/cgroup/pids.c:pids_css_alloc
  - kernel/cgroup/pids.c:pids_css_alloc
  - kernel/cgroup/pids.c:pids_css_alloc
```
```
In kernel/utsname.c (ffffffff811801df)
Location: include/asm-generic/atomic-instrumented.h:853
Inline: True
Inline callers:
  - kernel/utsname.c:clone_uts_ns
```
```
In kernel/user_namespace.c (ffffffff81181827)
Location: include/asm-generic/atomic-instrumented.h:853
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In kernel/pid_namespace.c (ffffffff81182147)
Location: include/asm-generic/atomic-instrumented.h:853
Inline: True
Inline callers:
  - kernel/pid_namespace.c:create_pid_namespace
```
```
In kernel/audit_tree.c (ffffffff8118fbbc)
Location: include/asm-generic/atomic-instrumented.h:853
Inline: True
Inline callers:
  - kernel/audit_tree.c:alloc_chunk
```
```
In kernel/trace/ring_buffer.c (ffffffff811b594b)
Location: include/asm-generic/atomic-instrumented.h:853
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
Location: include/asm-generic/atomic-instrumented.h:853
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
Location: include/asm-generic/atomic-instrumented.h:853
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
Location: include/asm-generic/atomic-instrumented.h:853
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
Location: include/asm-generic/atomic-instrumented.h:853
Inline: True
Inline callers:
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
```
```
In mm/vmalloc.c (ffffffff812b7083)
Location: include/asm-generic/atomic-instrumented.h:853
Inline: True
Inline callers:
  - mm/vmalloc.c:set_iounmap_nonlazy
```
```
In mm/page_alloc.c (ffffffff82fe83a7)
Location: include/asm-generic/atomic-instrumented.h:853
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init_core
  - mm/page_alloc.c:free_area_init_core_hotplug
```
```
In mm/memblock.c (ffffffff82fe9b0d)
Location: include/asm-generic/atomic-instrumented.h:853
Inline: True
Inline callers:
  - mm/memblock.c:reset_all_zones_managed_pages
```
```
In mm/swap_state.c (ffffffff812c4e6c)
Location: include/asm-generic/atomic-instrumented.h:853
Inline: True
Inline callers:
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/slub.c (ffffffff812eaf16)
Location: include/asm-generic/atomic-instrumented.h:853
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
Location: include/asm-generic/atomic-instrumented.h:853
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
Location: include/asm-generic/atomic-instrumented.h:853
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
```
```
In fs/file_table.c (ffffffff81320efd)
Location: include/asm-generic/atomic-instrumented.h:853
Inline: True
Inline callers:
  - fs/file_table.c:__alloc_file
```
```
In fs/inode.c (ffffffff8134017f)
Location: include/asm-generic/atomic-instrumented.h:853
Inline: True
Inline callers:
  - fs/inode.c:inode_init_always
```
```
In fs/namespace.c (ffffffff81346dfc)
Location: include/asm-generic/atomic-instrumented.h:853
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In fs/nsfs.c (ffffffff81362f39)
Location: include/asm-generic/atomic-instrumented.h:853
Inline: True
Inline callers:
  - fs/nsfs.c:ns_prune_dentry
```
```
In fs/ext4/inode.c (ffffffff8140d4de)
Location: include/asm-generic/atomic-instrumented.h:853
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/ioctl.c (ffffffff814141f3)
Location: include/asm-generic/atomic-instrumented.h:853
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/super.c (ffffffff8144c9a8)
Location: include/asm-generic/atomic-instrumented.h:853
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_alloc_inode
```
```
In fs/ext4/sysfs.c (ffffffff8144df64)
Location: include/asm-generic/atomic-instrumented.h:853
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_store
```
```
In fs/ext4/xattr.c (ffffffff8144ebe1)
Location: include/asm-generic/atomic-instrumented.h:853
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_create
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
```
```
In fs/fat/inode.c (ffffffff81476d70)
Location: include/asm-generic/atomic-instrumented.h:853
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_build_inode
```
```
In fs/fuse/inode.c (ffffffff8149884b)
Location: include/asm-generic/atomic-instrumented.h:853
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_conn_init
  - fs/fuse/inode.c:fuse_conn_init
```
```
In ipc/namespace.c (ffffffff814b2875)
Location: include/asm-generic/atomic-instrumented.h:853
Inline: True
```
```
In block/blk-ioc.c (ffffffff81565456)
Location: include/asm-generic/atomic-instrumented.h:853
Inline: True
Inline callers:
  - block/blk-ioc.c:create_task_io_context
```
```
In block/blk-cgroup.c (ffffffff8158439a)
Location: include/asm-generic/atomic-instrumented.h:853
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_scale_delay
```
```
In block/blk-cgroup-rwstat.c (ffffffff81586f04)
Location: include/asm-generic/atomic-instrumented.h:853
Inline: True
Inline callers:
  - block/blk-cgroup-rwstat.c:blkg_rwstat_init
```
```
In block/blk-iocost.c (ffffffff8158e544)
Location: include/asm-generic/atomic-instrumented.h:853
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
Location: include/asm-generic/atomic-instrumented.h:853
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_init
```
```
In lib/genalloc.c (ffffffff815b714a)
Location: include/asm-generic/atomic-instrumented.h:853
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_add_owner
```
```
In drivers/tty/tty_ldsem.c (ffffffff8175c465)
Location: include/asm-generic/atomic-instrumented.h:853
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:__init_ldsem
```
```
In drivers/iommu/amd/iommu.c (ffffffff817a8427)
Location: include/asm-generic/atomic-instrumented.h:853
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_direct_map
  - drivers/iommu/amd/iommu.c:protection_domain_alloc
  - drivers/iommu/amd/iommu.c:protection_domain_free
  - drivers/iommu/amd/iommu.c:increase_address_space
```
```
In drivers/iommu/iova.c (ffffffff817bfe55)
Location: include/asm-generic/atomic-instrumented.h:853
Inline: True
Inline callers:
  - drivers/iommu/iova.c:init_iova_flush_queue
  - drivers/iommu/iova.c:init_iova_flush_queue
```
```
In drivers/md/md.c (ffffffff81c2654a)
Location: include/asm-generic/atomic-instrumented.h:853
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:do_md_stop
```
```
In drivers/firmware/efi/cper.c (ffffffff819c035f)
Location: include/asm-generic/atomic-instrumented.h:853
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_next_record_id
  - drivers/firmware/efi/cper.c:cper_next_record_id
```
```
In net/core/net_namespace.c (ffffffff819f7905)
Location: include/asm-generic/atomic-instrumented.h:853
Inline: True
Inline callers:
  - net/core/net_namespace.c:net_ns_net_init
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81aaf089)
Location: include/asm-generic/atomic-instrumented.h:853
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81aafa66)
Location: include/asm-generic/atomic-instrumented.h:853
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_clone_lock
```
```
In net/ipv4/tcp_input.c (ffffffff81abbba6)
Location: include/asm-generic/atomic-instrumented.h:853
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/unix/af_unix.c (ffffffff81b3394b)
Location: include/asm-generic/atomic-instrumented.h:853
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
```
```
In net/packet/af_packet.c (ffffffff81b9a7c8)
Location: include/asm-generic/atomic-instrumented.h:853
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
Location: include/asm-generic/atomic-instrumented.h:853
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_setup_perfctr
```
```
In arch/x86/events/amd/uncore.c (ffffffff81009f64)
Location: include/asm-generic/atomic-instrumented.h:853
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_read
```
```
In arch/x86/events/amd/ibs.c (ffffffff8100b95e)
Location: include/asm-generic/atomic-instrumented.h:853
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
Location: include/asm-generic/atomic-instrumented.h:853
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_event_update
```
```
In arch/x86/events/intel/core.c (ffffffff8100efca)
Location: include/asm-generic/atomic-instrumented.h:853
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:handle_pmi_common
```
```
In arch/x86/events/intel/bts.c (ffffffff810105ac)
Location: include/asm-generic/atomic-instrumented.h:853
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_update
```
```
In arch/x86/events/intel/ds.c (ffffffff81011881)
Location: include/asm-generic/atomic-instrumented.h:853
Inline: True
```
```
In arch/x86/events/intel/pt.c (ffffffff81017728)
Location: include/asm-generic/atomic-instrumented.h:853
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_buffer_reset_offsets
  - arch/x86/events/intel/pt.c:pt_buffer_reset_offsets
  - arch/x86/events/intel/pt.c:pt_update_head
  - arch/x86/events/intel/pt.c:pt_update_head
```
```
In arch/x86/events/intel/uncore.c (ffffffff8101a541)
Location: include/asm-generic/atomic-instrumented.h:853
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
```
```
In arch/x86/kernel/pvclock.c (ffffffff81080fb0)
Location: include/asm-generic/atomic-instrumented.h:853
Inline: True
Inline callers:
  - arch/x86/kernel/pvclock.c:pvclock_resume
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff831e2e8b)
Location: include/asm-generic/atomic-instrumented.h:853
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff8109ac2a)
Location: include/asm-generic/atomic-instrumented.h:853
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:param_set_local64
```
```
In kernel/fork.c (ffffffff810a0ae4)
Location: include/asm-generic/atomic-instrumented.h:853
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
  - kernel/fork.c:mm_init
  - kernel/fork.c:mm_init
```
```
In kernel/workqueue.c (ffffffff810c7400)
Location: include/asm-generic/atomic-instrumented.h:853
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
Location: include/asm-generic/atomic-instrumented.h:853
Inline: True
Inline callers:
  - kernel/locking/mutex.c:__mutex_init
```
```
In kernel/locking/rwsem.c (ffffffff8110d815)
Location: include/asm-generic/atomic-instrumented.h:853
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
Location: include/asm-generic/atomic-instrumented.h:853
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
Location: include/asm-generic/atomic-instrumented.h:853
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
Location: include/asm-generic/atomic-instrumented.h:853
Inline: True
Inline callers:
  - kernel/time/namespace.c:copy_time_ns
```
```
In kernel/acct.c (ffffffff8116628e)
Location: include/asm-generic/atomic-instrumented.h:853
Inline: True
Inline callers:
  - kernel/acct.c:acct_on
```
```
In kernel/cgroup/namespace.c (ffffffff81176c83)
Location: include/asm-generic/atomic-instrumented.h:853
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
```
```
In kernel/cgroup/pids.c (ffffffff81179f86)
Location: include/asm-generic/atomic-instrumented.h:853
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_max_write
  - kernel/cgroup/pids.c:pids_css_alloc
  - kernel/cgroup/pids.c:pids_css_alloc
  - kernel/cgroup/pids.c:pids_css_alloc
```
```
In kernel/cgroup/misc.c (ffffffff81181104)
Location: include/asm-generic/atomic-instrumented.h:853
Inline: True
Inline callers:
  - kernel/cgroup/misc.c:misc_cg_alloc
```
```
In kernel/utsname.c (ffffffff811813c4)
Location: include/asm-generic/atomic-instrumented.h:853
Inline: True
Inline callers:
  - kernel/utsname.c:copy_utsname
```
```
In kernel/user_namespace.c (ffffffff8118298d)
Location: include/asm-generic/atomic-instrumented.h:853
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In kernel/pid_namespace.c (ffffffff81183297)
Location: include/asm-generic/atomic-instrumented.h:853
Inline: True
Inline callers:
  - kernel/pid_namespace.c:create_pid_namespace
```
```
In kernel/audit_tree.c (ffffffff81190b05)
Location: include/asm-generic/atomic-instrumented.h:853
Inline: True
Inline callers:
  - kernel/audit_tree.c:alloc_chunk
```
```
In kernel/trace/ring_buffer.c (ffffffff811b722d)
Location: include/asm-generic/atomic-instrumented.h:853
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
Location: include/asm-generic/atomic-instrumented.h:853
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
Location: include/asm-generic/atomic-instrumented.h:853
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
Location: include/asm-generic/atomic-instrumented.h:853
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
Location: include/asm-generic/atomic-instrumented.h:853
Inline: True
Inline callers:
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
```
```
In mm/vmalloc.c (ffffffff812bc983)
Location: include/asm-generic/atomic-instrumented.h:853
Inline: True
Inline callers:
  - mm/vmalloc.c:set_iounmap_nonlazy
```
```
In mm/page_alloc.c (ffffffff831f3120)
Location: include/asm-generic/atomic-instrumented.h:853
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init_node
  - mm/page_alloc.c:free_area_init_core_hotplug
```
```
In mm/memblock.c (ffffffff831f41b6)
Location: include/asm-generic/atomic-instrumented.h:853
Inline: True
Inline callers:
  - mm/memblock.c:reset_all_zones_managed_pages
```
```
In mm/swap_state.c (ffffffff812cbb09)
Location: include/asm-generic/atomic-instrumented.h:853
Inline: True
Inline callers:
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/slub.c (ffffffff812f29d2)
Location: include/asm-generic/atomic-instrumented.h:853
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
Location: include/asm-generic/atomic-instrumented.h:853
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_cancel
```
```
In mm/memcontrol.c (ffffffff81c2dbef)
Location: include/asm-generic/atomic-instrumented.h:853
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
Location: include/asm-generic/atomic-instrumented.h:853
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
```
```
In fs/file_table.c (ffffffff81326ffd)
Location: include/asm-generic/atomic-instrumented.h:853
Inline: True
Inline callers:
  - fs/file_table.c:__alloc_file
```
```
In fs/inode.c (ffffffff813466a5)
Location: include/asm-generic/atomic-instrumented.h:853
Inline: True
Inline callers:
  - fs/inode.c:inode_init_always
```
```
In fs/namespace.c (ffffffff8134d2fc)
Location: include/asm-generic/atomic-instrumented.h:853
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In fs/nsfs.c (ffffffff813699d9)
Location: include/asm-generic/atomic-instrumented.h:853
Inline: True
Inline callers:
  - fs/nsfs.c:ns_prune_dentry
```
```
In fs/ext4/inode.c (ffffffff8141374e)
Location: include/asm-generic/atomic-instrumented.h:853
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/ioctl.c (ffffffff8141a465)
Location: include/asm-generic/atomic-instrumented.h:853
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/super.c (ffffffff814524d8)
Location: include/asm-generic/atomic-instrumented.h:853
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_alloc_inode
```
```
In fs/ext4/sysfs.c (ffffffff81453a20)
Location: include/asm-generic/atomic-instrumented.h:853
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_store
```
```
In fs/ext4/xattr.c (ffffffff81455a3e)
Location: include/asm-generic/atomic-instrumented.h:853
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
```
```
In fs/fat/inode.c (ffffffff8147c7e4)
Location: include/asm-generic/atomic-instrumented.h:853
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_build_inode
```
```
In fs/fuse/inode.c (ffffffff8149d8db)
Location: include/asm-generic/atomic-instrumented.h:853
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_conn_init
  - fs/fuse/inode.c:fuse_conn_init
```
```
In ipc/namespace.c (ffffffff814b8ad2)
Location: include/asm-generic/atomic-instrumented.h:853
Inline: True
Inline callers:
  - ipc/namespace.c:copy_ipcs
```
```
In block/blk-ioc.c (ffffffff8156dac6)
Location: include/asm-generic/atomic-instrumented.h:853
Inline: True
Inline callers:
  - block/blk-ioc.c:create_task_io_context
```
```
In block/blk-cgroup.c (ffffffff8158b19d)
Location: include/asm-generic/atomic-instrumented.h:853
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_scale_delay
```
```
In block/blk-cgroup-rwstat.c (ffffffff8158dd54)
Location: include/asm-generic/atomic-instrumented.h:853
Inline: True
Inline callers:
  - block/blk-cgroup-rwstat.c:blkg_rwstat_init
```
```
In block/blk-iocost.c (ffffffff815952a4)
Location: include/asm-generic/atomic-instrumented.h:853
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
Location: include/asm-generic/atomic-instrumented.h:853
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_init
```
```
In lib/genalloc.c (ffffffff815c1fba)
Location: include/asm-generic/atomic-instrumented.h:853
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_add_owner
```
```
In drivers/tty/tty_ldsem.c (ffffffff81740305)
Location: include/asm-generic/atomic-instrumented.h:853
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:__init_ldsem
```
```
In drivers/iommu/amd/io_pgtable.c (ffffffff8178bef9)
Location: include/asm-generic/atomic-instrumented.h:853
Inline: True
```
```
In drivers/iommu/iova.c (ffffffff817a3c45)
Location: include/asm-generic/atomic-instrumented.h:853
Inline: True
Inline callers:
  - drivers/iommu/iova.c:init_iova_flush_queue
  - drivers/iommu/iova.c:init_iova_flush_queue
```
```
In drivers/md/md.c (ffffffff81c1871b)
Location: include/asm-generic/atomic-instrumented.h:853
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:do_md_stop
```
```
In drivers/firmware/efi/cper.c (ffffffff819a4a6f)
Location: include/asm-generic/atomic-instrumented.h:853
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_next_record_id
  - drivers/firmware/efi/cper.c:cper_next_record_id
```
```
In net/core/net_namespace.c (ffffffff819dda85)
Location: include/asm-generic/atomic-instrumented.h:853
Inline: True
Inline callers:
  - net/core/net_namespace.c:net_ns_net_init
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81a9a397)
Location: include/asm-generic/atomic-instrumented.h:853
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81a9ad76)
Location: include/asm-generic/atomic-instrumented.h:853
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_clone_lock
```
```
In net/ipv4/tcp_input.c (ffffffff81aa6b66)
Location: include/asm-generic/atomic-instrumented.h:853
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/nexthop.c (ffffffff81af3edb)
Location: include/asm-generic/atomic-instrumented.h:853
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_res_grp_activity_update
  - net/ipv4/nexthop.c:nh_res_table_upkeep
  - net/ipv4/nexthop.c:nh_res_bucket_migrate
```
```
In net/unix/af_unix.c (ffffffff81b2134c)
Location: include/asm-generic/atomic-instrumented.h:853
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
```
```
In net/packet/af_packet.c (ffffffff81b89738)
Location: include/asm-generic/atomic-instrumented.h:853
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
In arch/x86/kernel/pvclock.c (ffffffff8108ff40)
Location: include/linux/atomic/atomic-instrumented.h:617
Inline: True
Inline callers:
  - arch/x86/kernel/pvclock.c:pvclock_resume
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff832c682e)
Location: include/linux/atomic/atomic-instrumented.h:617
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In kernel/fork.c (ffffffff810b1f60)
Location: include/linux/atomic/atomic-instrumented.h:617
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
  - kernel/fork.c:mm_init
```
```
In kernel/printk/printk.c (ffffffff8113974a)
Location: include/linux/atomic/atomic-instrumented.h:617
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
In kernel/cgroup/pids.c (ffffffff811a18a6)
Location: include/linux/atomic/atomic-instrumented.h:617
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_max_write
  - kernel/cgroup/pids.c:pids_css_alloc
  - kernel/cgroup/pids.c:pids_css_alloc
  - kernel/cgroup/pids.c:pids_css_alloc
```
```
In kernel/trace/tracing_map.c (ffffffff811f358d)
Location: include/linux/atomic/atomic-instrumented.h:617
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
Location: include/linux/atomic/atomic-instrumented.h:617
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
In fs/inode.c (ffffffff813940c5)
Location: include/linux/atomic/atomic-instrumented.h:617
Inline: True
Inline callers:
  - fs/inode.c:inode_init_always
```
```
In fs/ext4/inode.c (ffffffff81466a90)
Location: include/linux/atomic/atomic-instrumented.h:617
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/ioctl.c (ffffffff8146d658)
Location: include/linux/atomic/atomic-instrumented.h:617
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/super.c (ffffffff814a5ac0)
Location: include/linux/atomic/atomic-instrumented.h:617
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_alloc_inode
```
```
In fs/ext4/sysfs.c (ffffffff814a7a99)
Location: include/linux/atomic/atomic-instrumented.h:617
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_store
```
```
In fs/ext4/xattr.c (ffffffff814a9a5e)
Location: include/linux/atomic/atomic-instrumented.h:617
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
```
```
In fs/fat/inode.c (ffffffff814d3ed9)
Location: include/linux/atomic/atomic-instrumented.h:617
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_build_inode
```
```
In fs/fuse/inode.c (ffffffff814f538b)
Location: include/linux/atomic/atomic-instrumented.h:617
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_conn_init
  - fs/fuse/inode.c:fuse_conn_init
```
```
In block/blk-cgroup.c (ffffffff815f019d)
Location: include/linux/atomic/atomic-instrumented.h:617
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_scale_delay
```
```
In block/blk-cgroup-rwstat.c (ffffffff815f3841)
Location: include/linux/atomic/atomic-instrumented.h:617
Inline: True
Inline callers:
  - block/blk-cgroup-rwstat.c:blkg_rwstat_init
```
```
In block/blk-iocost.c (ffffffff815fc1a5)
Location: include/linux/atomic/atomic-instrumented.h:617
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
In drivers/iommu/amd/io_pgtable.c (ffffffff81813ef7)
Location: include/linux/atomic/atomic-instrumented.h:617
Inline: True
Inline callers:
  - drivers/iommu/amd/io_pgtable.c:v1_free_pgtable
```
```
In drivers/iommu/iova.c (ffffffff8182d9d5)
Location: include/linux/atomic/atomic-instrumented.h:617
Inline: True
Inline callers:
  - drivers/iommu/iova.c:init_iova_flush_queue
  - drivers/iommu/iova.c:init_iova_flush_queue
```
```
In drivers/md/md.c (ffffffff81d27cd8)
Location: include/linux/atomic/atomic-instrumented.h:617
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:do_md_stop
```
```
In drivers/firmware/efi/cper.c (ffffffff81a51d3f)
Location: include/linux/atomic/atomic-instrumented.h:617
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_next_record_id
  - drivers/firmware/efi/cper.c:cper_next_record_id
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81b55807)
Location: include/linux/atomic/atomic-instrumented.h:617
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81b561e6)
Location: include/linux/atomic/atomic-instrumented.h:617
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_clone_lock
```
```
In net/ipv4/tcp_input.c (ffffffff81b63166)
Location: include/linux/atomic/atomic-instrumented.h:617
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
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
In arch/x86/kernel/pvclock.c (ffffffff810a0e80)
Location: include/linux/atomic/atomic-instrumented.h:658
Inline: True
Inline callers:
  - arch/x86/kernel/pvclock.c:pvclock_resume
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff834795c3)
Location: include/linux/atomic/atomic-instrumented.h:658
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In kernel/fork.c (ffffffff810c88c4)
Location: include/linux/atomic/atomic-instrumented.h:658
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
  - kernel/fork.c:mm_init
```
```
In kernel/printk/printk.c (ffffffff8115c21a)
Location: include/linux/atomic/atomic-instrumented.h:658
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
In kernel/cgroup/pids.c (ffffffff811d220c)
Location: include/linux/atomic/atomic-instrumented.h:658
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_max_write
  - kernel/cgroup/pids.c:pids_css_alloc
  - kernel/cgroup/pids.c:pids_css_alloc
  - kernel/cgroup/pids.c:pids_css_alloc
```
```
In kernel/trace/tracing_map.c (ffffffff8122cc7d)
Location: include/linux/atomic/atomic-instrumented.h:658
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
Location: include/linux/atomic/atomic-instrumented.h:658
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
In fs/inode.c (ffffffff81415dfe)
Location: include/linux/atomic/atomic-instrumented.h:658
Inline: True
Inline callers:
  - fs/inode.c:inode_init_always
```
```
In fs/ext4/inode.c (ffffffff814e6630)
Location: include/linux/atomic/atomic-instrumented.h:658
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/ioctl.c (ffffffff814edf26)
Location: include/linux/atomic/atomic-instrumented.h:658
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/super.c (ffffffff8152db21)
Location: include/linux/atomic/atomic-instrumented.h:658
Inline: True
Inline callers:
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:ext4_alloc_inode
```
```
In fs/ext4/sysfs.c (ffffffff8152f36f)
Location: include/linux/atomic/atomic-instrumented.h:658
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_store
```
```
In fs/ext4/xattr.c (ffffffff81531dc0)
Location: include/linux/atomic/atomic-instrumented.h:658
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
```
```
In fs/fat/inode.c (ffffffff81561111)
Location: include/linux/atomic/atomic-instrumented.h:658
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_build_inode
```
```
In fs/fuse/inode.c (ffffffff8158543b)
Location: include/linux/atomic/atomic-instrumented.h:658
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_conn_init
  - fs/fuse/inode.c:fuse_conn_init
```
```
In block/blk-cgroup.c (ffffffff816a1289)
Location: include/linux/atomic/atomic-instrumented.h:658
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_scale_delay
```
```
In block/blk-cgroup-rwstat.c (ffffffff816a4f31)
Location: include/linux/atomic/atomic-instrumented.h:658
Inline: True
Inline callers:
  - block/blk-cgroup-rwstat.c:blkg_rwstat_init
```
```
In block/blk-iocost.c (ffffffff816b0565)
Location: include/linux/atomic/atomic-instrumented.h:658
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
In drivers/iommu/amd/io_pgtable.c (ffffffff81954c53)
Location: include/linux/atomic/atomic-instrumented.h:658
Inline: True
Inline callers:
  - drivers/iommu/amd/io_pgtable.c:v1_free_pgtable
```
```
In drivers/iommu/dma-iommu.c (ffffffff8196c594)
Location: include/linux/atomic/atomic-instrumented.h:658
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_init_fq
  - drivers/iommu/dma-iommu.c:iommu_dma_init_fq
```
```
In drivers/md/md.c (ffffffff81ef3b6a)
Location: include/linux/atomic/atomic-instrumented.h:658
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
```
```
In drivers/firmware/efi/cper.c (ffffffff81bc0d33)
Location: include/linux/atomic/atomic-instrumented.h:658
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_next_record_id
  - drivers/firmware/efi/cper.c:cper_next_record_id
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81ce3502)
Location: include/linux/atomic/atomic-instrumented.h:658
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ce42fd)
Location: include/linux/atomic/atomic-instrumented.h:658
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_clone_lock
```
```
In net/ipv4/tcp_input.c (ffffffff81cf1e08)
Location: include/linux/atomic/atomic-instrumented.h:658
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/mptcp/protocol.c (ffffffff81e2445d)
Location: include/linux/atomic/atomic-instrumented.h:658
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
In arch/x86/kernel/pvclock.c (ffffffff810b8cd0)
Location: include/linux/atomic/atomic-instrumented.h:658
Inline: True
Inline callers:
  - arch/x86/kernel/pvclock.c:pvclock_resume
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff83ea3716)
Location: include/linux/atomic/atomic-instrumented.h:658
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In kernel/fork.c (ffffffff810e5c39)
Location: include/linux/atomic/atomic-instrumented.h:658
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
  - kernel/fork.c:mm_init
```
```
In kernel/printk/printk.c (ffffffff8118ecaa)
Location: include/linux/atomic/atomic-instrumented.h:658
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
In kernel/cgroup/pids.c (ffffffff81215fbc)
Location: include/linux/atomic/atomic-instrumented.h:658
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_max_write
  - kernel/cgroup/pids.c:pids_css_alloc
  - kernel/cgroup/pids.c:pids_css_alloc
  - kernel/cgroup/pids.c:pids_css_alloc
```
```
In kernel/trace/tracing_map.c (ffffffff812788cd)
Location: include/linux/atomic/atomic-instrumented.h:658
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
Location: include/linux/atomic/atomic-instrumented.h:658
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
In fs/inode.c (ffffffff814a126e)
Location: include/linux/atomic/atomic-instrumented.h:658
Inline: True
Inline callers:
  - fs/inode.c:inode_init_always
```
```
In fs/ext4/inode.c (ffffffff8157fdcd)
Location: include/linux/atomic/atomic-instrumented.h:658
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/ioctl.c (ffffffff81587e03)
Location: include/linux/atomic/atomic-instrumented.h:658
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/super.c (ffffffff815cbcdd)
Location: include/linux/atomic/atomic-instrumented.h:658
Inline: True
Inline callers:
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:ext4_alloc_inode
```
```
In fs/ext4/sysfs.c (ffffffff815cd07f)
Location: include/linux/atomic/atomic-instrumented.h:658
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_store
```
```
In fs/ext4/xattr.c (ffffffff815ce861)
Location: include/linux/atomic/atomic-instrumented.h:658
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_create
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
```
```
In fs/fat/inode.c (ffffffff81603599)
Location: include/linux/atomic/atomic-instrumented.h:658
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_build_inode
```
```
In fs/fuse/inode.c (ffffffff8162b63b)
Location: include/linux/atomic/atomic-instrumented.h:658
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_conn_init
  - fs/fuse/inode.c:fuse_conn_init
```
```
In block/blk-cgroup.c (ffffffff817600a8)
Location: include/linux/atomic/atomic-instrumented.h:658
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_scale_delay
```
```
In block/blk-cgroup-rwstat.c (ffffffff81763d71)
Location: include/linux/atomic/atomic-instrumented.h:658
Inline: True
Inline callers:
  - block/blk-cgroup-rwstat.c:blkg_rwstat_init
```
```
In block/blk-iocost.c (ffffffff817703cd)
Location: include/linux/atomic/atomic-instrumented.h:658
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
In drivers/iommu/amd/io_pgtable.c (ffffffff81abaac3)
Location: include/linux/atomic/atomic-instrumented.h:658
Inline: True
Inline callers:
  - drivers/iommu/amd/io_pgtable.c:v1_free_pgtable
```
```
In drivers/iommu/dma-iommu.c (ffffffff81ad6bf2)
Location: include/linux/atomic/atomic-instrumented.h:658
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_init_fq
  - drivers/iommu/dma-iommu.c:iommu_dma_init_fq
```
```
In drivers/md/md.c (ffffffff81cf9b88)
Location: include/linux/atomic/atomic-instrumented.h:658
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:do_md_stop
```
```
In drivers/firmware/efi/cper.c (ffffffff81d64623)
Location: include/linux/atomic/atomic-instrumented.h:658
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_next_record_id
  - drivers/firmware/efi/cper.c:cper_next_record_id
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81ea59d2)
Location: include/linux/atomic/atomic-instrumented.h:658
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ea6e78)
Location: include/linux/atomic/atomic-instrumented.h:658
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_clone_lock
```
```
In net/ipv4/tcp_input.c (ffffffff81eb6678)
Location: include/linux/atomic/atomic-instrumented.h:658
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/mptcp/subflow.c (ffffffff81ffefe5)
Location: include/linux/atomic/atomic-instrumented.h:658
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
In arch/x86/kernel/pvclock.c (ffffffff810bbea0)
Location: include/linux/atomic/atomic-instrumented.h:1629
Inline: True
Inline callers:
  - arch/x86/kernel/pvclock.c:pvclock_resume
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff836c79a6)
Location: include/linux/atomic/atomic-instrumented.h:1629
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In kernel/fork.c (ffffffff810f13ae)
Location: include/linux/atomic/atomic-instrumented.h:1629
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
  - kernel/fork.c:mm_init
```
```
In kernel/workqueue.c (ffffffff8111e277)
Location: include/linux/atomic/atomic-instrumented.h:1629
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_cpu_intensive_report
```
```
In kernel/printk/printk.c (ffffffff811a0414)
Location: include/linux/atomic/atomic-instrumented.h:1629
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
In kernel/cgroup/pids.c (ffffffff8122b8fc)
Location: include/linux/atomic/atomic-instrumented.h:1629
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_max_write
  - kernel/cgroup/pids.c:pids_css_alloc
  - kernel/cgroup/pids.c:pids_css_alloc
  - kernel/cgroup/pids.c:pids_css_alloc
```
```
In kernel/trace/tracing_map.c (ffffffff8129030f)
Location: include/linux/atomic/atomic-instrumented.h:1629
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
Location: include/linux/atomic/atomic-instrumented.h:1629
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
In fs/inode.c (ffffffff814d657e)
Location: include/linux/atomic/atomic-instrumented.h:1629
Inline: True
Inline callers:
  - fs/inode.c:inode_init_always
```
```
In fs/ext4/inode.c (ffffffff815b726f)
Location: include/linux/atomic/atomic-instrumented.h:1629
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/ioctl.c (ffffffff815be683)
Location: include/linux/atomic/atomic-instrumented.h:1629
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/super.c (ffffffff81603756)
Location: include/linux/atomic/atomic-instrumented.h:1629
Inline: True
Inline callers:
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:ext4_alloc_inode
```
```
In fs/ext4/sysfs.c (ffffffff8160502c)
Location: include/linux/atomic/atomic-instrumented.h:1629
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_store
```
```
In fs/ext4/xattr.c (ffffffff81606131)
Location: include/linux/atomic/atomic-instrumented.h:1629
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_create
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
```
```
In fs/fat/inode.c (ffffffff8163b4b9)
Location: include/linux/atomic/atomic-instrumented.h:1629
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_build_inode
```
```
In fs/fuse/inode.c (ffffffff8166386b)
Location: include/linux/atomic/atomic-instrumented.h:1629
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_conn_init
  - fs/fuse/inode.c:fuse_conn_init
```
```
In block/blk-cgroup.c (ffffffff8179f0b8)
Location: include/linux/atomic/atomic-instrumented.h:1629
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_scale_delay
```
```
In block/blk-cgroup-rwstat.c (ffffffff817a2deb)
Location: include/linux/atomic/atomic-instrumented.h:1629
Inline: True
Inline callers:
  - block/blk-cgroup-rwstat.c:blkg_rwstat_init
```
```
In block/blk-iocost.c (ffffffff817af3fd)
Location: include/linux/atomic/atomic-instrumented.h:1629
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
In drivers/iommu/amd/init.c (ffffffff83718c92)
Location: include/linux/atomic/atomic-instrumented.h:1629
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:init_iommu_one
```
```
In drivers/iommu/amd/io_pgtable.c (ffffffff81b07193)
Location: include/linux/atomic/atomic-instrumented.h:1629
Inline: True
Inline callers:
  - drivers/iommu/amd/io_pgtable.c:v1_free_pgtable
```
```
In drivers/iommu/dma-iommu.c (ffffffff81b253c2)
Location: include/linux/atomic/atomic-instrumented.h:1629
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_init_fq
  - drivers/iommu/dma-iommu.c:iommu_dma_init_fq
```
```
In drivers/md/md.c (ffffffff81d692cf)
Location: include/linux/atomic/atomic-instrumented.h:1629
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:do_md_stop
```
```
In drivers/firmware/efi/cper.c (ffffffff81dcf753)
Location: include/linux/atomic/atomic-instrumented.h:1629
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_next_record_id
  - drivers/firmware/efi/cper.c:cper_next_record_id
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81f04164)
Location: include/linux/atomic/atomic-instrumented.h:1629
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81f05652)
Location: include/linux/atomic/atomic-instrumented.h:1629
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_clone_lock
```
```
In net/ipv4/tcp_input.c (ffffffff81f14a98)
Location: include/linux/atomic/atomic-instrumented.h:1629
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/mptcp/subflow.c (ffffffff8207b205)
Location: include/linux/atomic/atomic-instrumented.h:1629
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
In arch/x86/kernel/pvclock.c (ffffffff810c3020)
Location: include/linux/atomic/atomic-instrumented.h:1629
Inline: True
Inline callers:
  - arch/x86/kernel/pvclock.c:pvclock_resume
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff838f85a6)
Location: include/linux/atomic/atomic-instrumented.h:1629
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In kernel/fork.c (ffffffff810fa77e)
Location: include/linux/atomic/atomic-instrumented.h:1629
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
  - kernel/fork.c:mm_init
```
```
In kernel/workqueue.c (ffffffff81127fa7)
Location: include/linux/atomic/atomic-instrumented.h:1629
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_cpu_intensive_report
```
```
In kernel/printk/printk.c (ffffffff811af434)
Location: include/linux/atomic/atomic-instrumented.h:1629
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
In kernel/cgroup/pids.c (ffffffff812438fc)
Location: include/linux/atomic/atomic-instrumented.h:1629
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_max_write
  - kernel/cgroup/pids.c:pids_css_alloc
  - kernel/cgroup/pids.c:pids_css_alloc
  - kernel/cgroup/pids.c:pids_css_alloc
```
```
In kernel/cgroup/misc.c (ffffffff8124f6a7)
Location: include/linux/atomic/atomic-instrumented.h:1629
Inline: True
Inline callers:
  - kernel/cgroup/misc.c:misc_cg_alloc
```
```
In kernel/trace/tracing_map.c (ffffffff812ab8cf)
Location: include/linux/atomic/atomic-instrumented.h:1629
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
Location: include/linux/atomic/atomic-instrumented.h:1629
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
Location: include/linux/atomic/atomic-instrumented.h:1629
Inline: True
Inline callers:
  - kernel/bpf/tcx.c:tcx_link_prog_attach
  - kernel/bpf/tcx.c:tcx_prog_attach
```
```
In mm/memcontrol.c (ffffffff814b2bef)
Location: include/linux/atomic/atomic-instrumented.h:1629
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_rstat_flush
```
```
In fs/inode.c (ffffffff81508953)
Location: include/linux/atomic/atomic-instrumented.h:1629
Inline: True
Inline callers:
  - fs/inode.c:inode_init_always
```
```
In fs/ext4/inode.c (ffffffff815f0001)
Location: include/linux/atomic/atomic-instrumented.h:1629
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/ioctl.c (ffffffff815f743c)
Location: include/linux/atomic/atomic-instrumented.h:1629
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/super.c (ffffffff8163c571)
Location: include/linux/atomic/atomic-instrumented.h:1629
Inline: True
Inline callers:
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:ext4_alloc_inode
```
```
In fs/ext4/sysfs.c (ffffffff8163dcec)
Location: include/linux/atomic/atomic-instrumented.h:1629
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_store
```
```
In fs/ext4/xattr.c (ffffffff8163ee5c)
Location: include/linux/atomic/atomic-instrumented.h:1629
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_create
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
```
```
In fs/fat/inode.c (ffffffff81674a18)
Location: include/linux/atomic/atomic-instrumented.h:1629
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_build_inode
```
```
In fs/fuse/inode.c (ffffffff8169d95b)
Location: include/linux/atomic/atomic-instrumented.h:1629
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_conn_init
  - fs/fuse/inode.c:fuse_conn_init
```
```
In block/blk-cgroup.c (ffffffff817e2b88)
Location: include/linux/atomic/atomic-instrumented.h:1629
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_scale_delay
```
```
In block/blk-cgroup-rwstat.c (ffffffff817e6930)
Location: include/linux/atomic/atomic-instrumented.h:1629
Inline: True
Inline callers:
  - block/blk-cgroup-rwstat.c:blkg_rwstat_init
```
```
In block/blk-iocost.c (ffffffff817f3210)
Location: include/linux/atomic/atomic-instrumented.h:1629
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
In drivers/iommu/amd/init.c (ffffffff8394c752)
Location: include/linux/atomic/atomic-instrumented.h:1629
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:init_iommu_one
```
```
In drivers/iommu/dma-iommu.c (ffffffff81b7c05a)
Location: include/linux/atomic/atomic-instrumented.h:1629
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_init_fq
  - drivers/iommu/dma-iommu.c:iommu_dma_init_fq
```
```
In drivers/net/netkit.c (ffffffff81ce5c8c)
Location: include/linux/atomic/atomic-instrumented.h:1629
Inline: True
Inline callers:
  - drivers/net/netkit.c:netkit_new_link
  - drivers/net/netkit.c:netkit_new_link
```
```
In drivers/md/md.c (ffffffff81e206d2)
Location: include/linux/atomic/atomic-instrumented.h:1629
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:do_md_stop
```
```
In drivers/firmware/efi/cper.c (ffffffff81e88483)
Location: include/linux/atomic/atomic-instrumented.h:1629
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_next_record_id
  - drivers/firmware/efi/cper.c:cper_next_record_id
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81fc849c)
Location: include/linux/atomic/atomic-instrumented.h:1629
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81fc99b8)
Location: include/linux/atomic/atomic-instrumented.h:1629
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_clone_lock
```
```
In net/ipv4/tcp_input.c (ffffffff81fd8fb9)
Location: include/linux/atomic/atomic-instrumented.h:1629
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/tcp_ao.c (ffffffff82056c31)
Location: include/linux/atomic/atomic-instrumented.h:1629
Inline: True
Inline callers:
  - net/ipv4/tcp_ao.c:tcp_ao_add_cmd
  - net/ipv4/tcp_ao.c:tcp_ao_add_cmd
  - net/ipv4/tcp_ao.c:tcp_ao_copy_all_matching
  - net/ipv4/tcp_ao.c:tcp_ao_copy_all_matching
```
```
In net/mptcp/subflow.c (ffffffff82150db1)
Location: include/linux/atomic/atomic-instrumented.h:1629
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
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/arm64/mm/context.c (ffff8000100af944)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - arch/arm64/mm/context.c:asids_init
  - arch/arm64/mm/context.c:check_and_switch_context
  - arch/arm64/mm/context.c:check_and_switch_context
```
```
In virt/kvm/arm/pmu.c (ffff8000100eeab4)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - virt/kvm/arm/pmu.c:kvm_pmu_perf_overflow
```
```
In kernel/fork.c (ffff8000100f1c08)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
  - kernel/fork.c:mm_init
  - kernel/fork.c:mm_init
```
```
In kernel/workqueue.c (ffff80001011f5f4)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/workqueue.c:insert_work
  - kernel/workqueue.c:set_work_pool_and_clear_pending
```
```
In kernel/locking/mutex.c (ffff8000101685d0)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - kernel/locking/mutex.c:__mutex_init
```
```
In kernel/locking/rwsem.c (ffff8000101696cc)
Location: include/asm-generic/atomic-instrumented.h:852
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
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - kernel/acct.c:__arm64_sys_acct
```
```
In kernel/cgroup/namespace.c (ffff8000101da390)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
```
```
In kernel/cgroup/pids.c (ffff8000101dea9c)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_max_write
  - kernel/cgroup/pids.c:pids_css_alloc
  - kernel/cgroup/pids.c:pids_css_alloc
  - kernel/cgroup/pids.c:pids_css_alloc
```
```
In kernel/utsname.c (ffff8000101e52dc)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - kernel/utsname.c:copy_utsname
```
```
In kernel/user_namespace.c (ffff8000101e6900)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In kernel/pid_namespace.c (ffff8000101e782c)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In kernel/audit_tree.c (ffff8000101f4668)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - kernel/audit_tree.c:alloc_chunk
```
```
In kernel/trace/ring_buffer.c (ffff800010218fc8)
Location: include/asm-generic/atomic-instrumented.h:852
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
In kernel/trace/tracing_map.c (ffff80001022ec88)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_clear
  - kernel/trace/tracing_map.c:tracing_map_clear
  - kernel/trace/tracing_map.c:tracing_map_elt_clear
  - kernel/trace/tracing_map.c:tracing_map_elt_clear
  - kernel/trace/tracing_map.c:tracing_map_set_var
```
```
In kernel/events/core.c (ffff800010297364)
Location: include/asm-generic/atomic-instrumented.h:852
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
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
```
```
In mm/vmalloc.c (ffff80001030d524)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - mm/vmalloc.c:set_iounmap_nonlazy
```
```
In mm/page_alloc.c (ffff8000114576f0)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init_node
  - mm/page_alloc.c:free_area_init_core_hotplug
```
```
In mm/memblock.c (ffff800011458c24)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - mm/memblock.c:reset_all_zones_managed_pages
```
```
In mm/swap_state.c (ffff800010322294)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/slub.c (ffff80001034c22c)
Location: include/asm-generic/atomic-instrumented.h:852
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
Location: include/asm-generic/atomic-instrumented.h:852
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
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
```
```
In fs/file_table.c (ffff80001038527c)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - fs/file_table.c:__alloc_file
```
```
In fs/super.c (ffff800010386bac)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - fs/super.c:thaw_super_locked
  - fs/super.c:thaw_super_locked
  - fs/super.c:freeze_super
```
```
In fs/inode.c (ffff8000103ac964)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - fs/inode.c:inode_init_always
```
```
In fs/namespace.c (ffff8000103b4cf0)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In fs/nsfs.c (ffff8000103d442c)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - fs/nsfs.c:ns_prune_dentry
```
```
In fs/aio.c (0)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
```
```
In fs/io_uring.c (0)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
```
```
In fs/ext4/inode.c (ffff8000104837c8)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/ioctl.c (ffff80001048a7d4)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/super.c (ffff8000104bf918)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_alloc_inode
```
```
In fs/ext4/sysfs.c (ffff8000104c11f8)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_store
```
```
In fs/ext4/xattr.c (ffff8000104c2a2c)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
```
```
In fs/fat/inode.c (ffff8000104ed71c)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_build_inode
```
```
In fs/fuse/inode.c (ffff800010512418)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_conn_init
  - fs/fuse/inode.c:fuse_conn_init
```
```
In ipc/namespace.c (ffff80001052cce0)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - ipc/namespace.c:copy_ipcs
```
```
In block/blk-ioc.c (ffff8000105e8d58)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - block/blk-ioc.c:create_task_io_context
```
```
In block/blk-cgroup.c (ffff80001060d2a8)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_scale_delay
  - block/blk-cgroup.c:blkcg_reset_stats
  - block/blk-cgroup.c:blkcg_reset_stats
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-cgroup.c:blkg_alloc
```
```
In block/blk-iocost.c (ffff800010615a1c)
Location: include/asm-generic/atomic-instrumented.h:852
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
In lib/percpu-refcount.c (ffff800010634de0)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_init
```
```
In lib/genalloc.c (ffff8000106448d4)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_add_owner
```
```
In drivers/tty/tty_ldsem.c (ffff80001085f5c8)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:__init_ldsem
```
```
In drivers/iommu/iova.c (ffff8000108cc8c0)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - drivers/iommu/iova.c:init_iova_flush_queue
  - drivers/iommu/iova.c:init_iova_flush_queue
```
```
In drivers/md/md.c (ffff800010aed35c)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:do_md_stop
```
```
In drivers/firmware/efi/cper.c (ffff800010b5e900)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_next_record_id
  - drivers/firmware/efi/cper.c:cper_next_record_id
```
```
In drivers/firmware/efi/arm-runtime.c (ffff8000114a78d8)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - drivers/firmware/efi/arm-runtime.c:arm_enable_runtime_services
```
```
In drivers/perf/arm-cci.c (ffff800010b919b8)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - drivers/perf/arm-cci.c:cci_pmu_start
  - drivers/perf/arm-cci.c:pmu_handle_irq
```
```
In drivers/perf/arm-ccn.c (ffff800010b9351c)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - drivers/perf/arm-ccn.c:arm_ccn_pmu_event_start
```
```
In drivers/perf/arm_pmu.c (ffff800010b947dc)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - drivers/perf/arm_pmu.c:armpmu_event_init
  - drivers/perf/arm_pmu.c:armpmu_event_set_period
  - drivers/perf/arm_pmu.c:armpmu_event_set_period
  - drivers/perf/arm_pmu.c:armpmu_event_set_period
```
```
In drivers/perf/hisilicon/hisi_uncore_pmu.c (ffff800010b966c0)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - drivers/perf/hisilicon/hisi_uncore_pmu.c:hisi_uncore_pmu_start
```
```
In drivers/perf/qcom_l2_pmu.c (ffff800010b99a3c)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - drivers/perf/qcom_l2_pmu.c:l2_cache_event_add
  - drivers/perf/qcom_l2_pmu.c:l2_cache_event_start
  - drivers/perf/qcom_l2_pmu.c:l2_cache_handle_irq
```
```
In drivers/perf/qcom_l3_pmu.c (ffff800010b9aa7c)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - drivers/perf/qcom_l3_pmu.c:qcom_l3_cache__32bit_counter_start
  - drivers/perf/qcom_l3_pmu.c:qcom_l3_cache__64bit_counter_start
```
```
In drivers/perf/xgene_pmu.c (ffff800010b9b544)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - drivers/perf/xgene_pmu.c:xgene_perf_start
```
```
In net/core/net_namespace.c (ffff800010bc0094)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - net/core/net_namespace.c:net_ns_net_init
```
```
In net/ipv4/inet_timewait_sock.c (ffff800010c6b944)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
```
```
In net/ipv4/inet_connection_sock.c (ffff800010c6c750)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_clone_lock
```
```
In net/ipv4/tcp_input.c (ffff800010c77464)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/unix/af_unix.c (ffff800010cf0e64)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
```
```
In net/packet/af_packet.c (ffff800010d5ceec)
Location: include/asm-generic/atomic-instrumented.h:852
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
In arch/arm/mm/context.c (c0322380)
Location: arch/arm/include/asm/atomic.h:290
Inline: True
Inline callers:
  - arch/arm/mm/context.c:check_and_switch_context
  - arch/arm/mm/context.c:check_and_switch_context
```
```
In arch/arm/mm/cache-l2x0-pmu.c (c0324970)
Location: arch/arm/include/asm/atomic.h:290
Inline: True
Inline callers:
  - arch/arm/mm/cache-l2x0-pmu.c:l2x0_pmu_event_configure
```
```
In arch/arm/mach-imx/mmdc.c (c0333758)
Location: arch/arm/include/asm/atomic.h:290
Inline: True
Inline callers:
  - arch/arm/mach-imx/mmdc.c:mmdc_pmu_event_add
  - arch/arm/mach-imx/mmdc.c:mmdc_pmu_event_start
```
```
In kernel/fork.c (c0350ad8)
Location: arch/arm/include/asm/atomic.h:290
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
  - kernel/fork.c:mm_init
```
```
In kernel/cgroup/pids.c (c042044c)
Location: arch/arm/include/asm/atomic.h:290
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_max_write
  - kernel/cgroup/pids.c:pids_css_alloc
  - kernel/cgroup/pids.c:pids_css_alloc
  - kernel/cgroup/pids.c:pids_css_alloc
```
```
In kernel/events/core.c (c04c7678)
Location: arch/arm/include/asm/atomic.h:290
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:task_clock_event_start
  - kernel/events/core.c:cpu_clock_event_start
  - kernel/events/core.c:__perf_event_period
  - kernel/events/core.c:_perf_event_reset
  - kernel/events/core.c:perf_adjust_period
  - kernel/events/core.c:__perf_event_task_sched_out
```
```
In fs/inode.c (c058c35c)
Location: arch/arm/include/asm/atomic.h:290
Inline: True
Inline callers:
  - fs/inode.c:inode_init_always
```
```
In fs/ext4/inode.c (c0644c8c)
Location: arch/arm/include/asm/atomic.h:290
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/ioctl.c (c064ca54)
Location: arch/arm/include/asm/atomic.h:290
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/super.c (c0683850)
Location: arch/arm/include/asm/atomic.h:290
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_alloc_inode
```
```
In fs/ext4/sysfs.c (c0684d68)
Location: arch/arm/include/asm/atomic.h:290
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_store
```
```
In fs/ext4/xattr.c (c0687660)
Location: arch/arm/include/asm/atomic.h:290
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
```
```
In fs/fat/inode.c (c06ab474)
Location: arch/arm/include/asm/atomic.h:290
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_build_inode
```
```
In fs/fuse/inode.c (c06cc0a8)
Location: arch/arm/include/asm/atomic.h:290
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_conn_init
  - fs/fuse/inode.c:fuse_conn_init
```
```
In block/blk-cgroup.c (c07b6248)
Location: arch/arm/include/asm/atomic.h:290
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_scale_delay
  - block/blk-cgroup.c:blkcg_reset_stats
  - block/blk-cgroup.c:blkcg_reset_stats
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-cgroup.c:blkg_alloc
```
```
In block/blk-iocost.c (c07c142c)
Location: arch/arm/include/asm/atomic.h:290
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_pd_init
  - block/blk-iocost.c:ioc_pd_init
  - block/blk-iocost.c:ioc_pd_init
  - block/blk-iocost.c:ioc_pd_init
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:iocg_kick_waitq
  - block/blk-iocost.c:iocg_activate
  - block/blk-iocost.c:iocg_activate
  - block/blk-iocost.c:ioc_refresh_params
```
```
In drivers/md/md.c (c0bca848)
Location: arch/arm/include/asm/atomic.h:290
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:do_md_stop
```
```
In drivers/firmware/efi/arm-runtime.c (c15aa044)
Location: arch/arm/include/asm/atomic.h:290
Inline: True
Inline callers:
  - drivers/firmware/efi/arm-runtime.c:arm_enable_runtime_services
```
```
In drivers/perf/arm-cci.c (c0c7b070)
Location: arch/arm/include/asm/atomic.h:290
Inline: True
Inline callers:
  - drivers/perf/arm-cci.c:cci_pmu_start
  - drivers/perf/arm-cci.c:pmu_handle_irq
```
```
In drivers/perf/arm-ccn.c (c0c7d16c)
Location: arch/arm/include/asm/atomic.h:290
Inline: True
Inline callers:
  - drivers/perf/arm-ccn.c:arm_ccn_pmu_event_start
```
```
In drivers/perf/arm_pmu.c (c0c7df5c)
Location: arch/arm/include/asm/atomic.h:290
Inline: True
Inline callers:
  - drivers/perf/arm_pmu.c:armpmu_event_init
  - drivers/perf/arm_pmu.c:armpmu_event_set_period
  - drivers/perf/arm_pmu.c:armpmu_event_set_period
  - drivers/perf/arm_pmu.c:armpmu_event_set_period
```
```
In net/ipv4/inet_timewait_sock.c (c0d7a9ac)
Location: arch/arm/include/asm/atomic.h:290
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
```
```
In net/ipv4/inet_connection_sock.c (c0d7b688)
Location: arch/arm/include/asm/atomic.h:290
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_clone_lock
```
```
In net/ipv4/tcp_input.c (c0d859d8)
Location: arch/arm/include/asm/atomic.h:290
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
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
In arch/powerpc/mm/book3s64/iommu_api.c (c0000000000a0874)
Location: arch/powerpc/include/asm/atomic.h:309
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/iommu_api.c:mm_iommu_do_alloc
```
```
In kernel/fork.c (c000000000137334)
Location: arch/powerpc/include/asm/atomic.h:309
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
  - kernel/fork.c:mm_init
```
```
In kernel/workqueue.c (c00000000016689c)
Location: arch/powerpc/include/asm/atomic.h:309
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
Location: arch/powerpc/include/asm/atomic.h:309
Inline: True
Inline callers:
  - kernel/locking/mutex.c:__mutex_init
```
```
In kernel/locking/rwsem.c (c0000000001c0ec0)
Location: arch/powerpc/include/asm/atomic.h:309
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
Location: arch/powerpc/include/asm/atomic.h:309
Inline: True
Inline callers:
  - kernel/acct.c:__se_sys_acct
```
```
In kernel/cgroup/namespace.c (c000000000247618)
Location: arch/powerpc/include/asm/atomic.h:309
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
```
```
In kernel/cgroup/pids.c (c00000000024cbd8)
Location: arch/powerpc/include/asm/atomic.h:309
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_max_write
  - kernel/cgroup/pids.c:pids_css_alloc
  - kernel/cgroup/pids.c:pids_css_alloc
  - kernel/cgroup/pids.c:pids_css_alloc
```
```
In kernel/utsname.c (c0000000002556e8)
Location: arch/powerpc/include/asm/atomic.h:309
Inline: True
Inline callers:
  - kernel/utsname.c:copy_utsname
```
```
In kernel/user_namespace.c (c000000000257088)
Location: arch/powerpc/include/asm/atomic.h:309
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In kernel/pid_namespace.c (c000000000258128)
Location: arch/powerpc/include/asm/atomic.h:309
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In kernel/audit_tree.c (c000000000269c5c)
Location: arch/powerpc/include/asm/atomic.h:309
Inline: True
Inline callers:
  - kernel/audit_tree.c:alloc_chunk
```
```
In kernel/trace/tracing_map.c (c0000000002b8334)
Location: arch/powerpc/include/asm/atomic.h:309
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_clear
  - kernel/trace/tracing_map.c:tracing_map_clear
  - kernel/trace/tracing_map.c:tracing_map_elt_clear
  - kernel/trace/tracing_map.c:tracing_map_elt_clear
  - kernel/trace/tracing_map.c:tracing_map_set_var
```
```
In kernel/events/core.c (c000000000346c5c)
Location: arch/powerpc/include/asm/atomic.h:309
Inline: True
```
```
In mm/vmstat.c (c00000000039b478)
Location: arch/powerpc/include/asm/atomic.h:309
Inline: True
Inline callers:
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
```
```
In mm/vmalloc.c (c0000000003ddf50)
Location: arch/powerpc/include/asm/atomic.h:309
Inline: True
Inline callers:
  - mm/vmalloc.c:set_iounmap_nonlazy
```
```
In mm/page_alloc.c (c000000000eec3f8)
Location: arch/powerpc/include/asm/atomic.h:309
Inline: True
Inline callers:
  - mm/page_alloc.c:zone_init_internals
```
```
In mm/memblock.c (c0000000013824f0)
Location: arch/powerpc/include/asm/atomic.h:309
Inline: True
Inline callers:
  - mm/memblock.c:reset_all_zones_managed_pages
```
```
In mm/swap_state.c (c0000000003f7cec)
Location: arch/powerpc/include/asm/atomic.h:309
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/slub.c (c00000000042bb68)
Location: arch/powerpc/include/asm/atomic.h:309
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
Location: arch/powerpc/include/asm/atomic.h:309
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
Location: arch/powerpc/include/asm/atomic.h:309
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
```
```
In fs/file_table.c (c00000000047b224)
Location: arch/powerpc/include/asm/atomic.h:309
Inline: True
Inline callers:
  - fs/file_table.c:__alloc_file
```
```
In fs/super.c (c00000000047cbc8)
Location: arch/powerpc/include/asm/atomic.h:309
Inline: True
Inline callers:
  - fs/super.c:thaw_super_locked
  - fs/super.c:thaw_super_locked
  - fs/super.c:freeze_super
```
```
In fs/inode.c (c0000000004a62c0)
Location: arch/powerpc/include/asm/atomic.h:309
Inline: True
Inline callers:
  - fs/inode.c:inode_init_always
```
```
In fs/namespace.c (c0000000004b0c20)
Location: arch/powerpc/include/asm/atomic.h:309
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In fs/nsfs.c (c0000000004d7024)
Location: arch/powerpc/include/asm/atomic.h:309
Inline: True
Inline callers:
  - fs/nsfs.c:ns_prune_dentry
```
```
In fs/aio.c (0)
Location: arch/powerpc/include/asm/atomic.h:309
Inline: True
```
```
In fs/io_uring.c (0)
Location: arch/powerpc/include/asm/atomic.h:309
Inline: True
```
```
In fs/ext4/inode.c (c0000000005a883c)
Location: arch/powerpc/include/asm/atomic.h:309
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/ioctl.c (c0000000005b1bd0)
Location: arch/powerpc/include/asm/atomic.h:309
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/super.c (c0000000005f6098)
Location: arch/powerpc/include/asm/atomic.h:309
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_alloc_inode
```
```
In fs/ext4/sysfs.c (c0000000005f7b80)
Location: arch/powerpc/include/asm/atomic.h:309
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_store
```
```
In fs/ext4/xattr.c (c0000000005fa9c0)
Location: arch/powerpc/include/asm/atomic.h:309
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
```
```
In fs/fat/inode.c (c00000000062c548)
Location: arch/powerpc/include/asm/atomic.h:309
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_build_inode
```
```
In fs/fuse/inode.c (c000000000658430)
Location: arch/powerpc/include/asm/atomic.h:309
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_conn_init
  - fs/fuse/inode.c:fuse_conn_init
```
```
In ipc/namespace.c (c000000000678ce0)
Location: arch/powerpc/include/asm/atomic.h:309
Inline: True
Inline callers:
  - ipc/namespace.c:copy_ipcs
```
```
In block/blk-ioc.c (c00000000077d908)
Location: arch/powerpc/include/asm/atomic.h:309
Inline: True
Inline callers:
  - block/blk-ioc.c:create_task_io_context
```
```
In block/blk-cgroup.c (c0000000007a7c00)
Location: arch/powerpc/include/asm/atomic.h:309
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_scale_delay
  - block/blk-cgroup.c:blkcg_reset_stats
  - block/blk-cgroup.c:blkcg_reset_stats
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-cgroup.c:blkg_alloc
```
```
In block/blk-iocost.c (c0000000007b3adc)
Location: arch/powerpc/include/asm/atomic.h:309
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
In lib/percpu-refcount.c (c0000000007da52c)
Location: arch/powerpc/include/asm/atomic.h:309
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_init
```
```
In lib/genalloc.c (c0000000007efe0c)
Location: arch/powerpc/include/asm/atomic.h:309
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_add_owner
```
```
In drivers/tty/tty_ldsem.c (c0000000008feb58)
Location: arch/powerpc/include/asm/atomic.h:309
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:__init_ldsem
```
```
In drivers/md/md.c (c000000000bd30ac)
Location: arch/powerpc/include/asm/atomic.h:309
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:do_md_stop
```
```
In net/core/net_namespace.c (c000000000c996dc)
Location: arch/powerpc/include/asm/atomic.h:309
Inline: True
Inline callers:
  - net/core/net_namespace.c:net_ns_net_init
```
```
In net/ipv4/inet_timewait_sock.c (c000000000d70ff4)
Location: arch/powerpc/include/asm/atomic.h:309
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
```
```
In net/ipv4/inet_connection_sock.c (c000000000d72170)
Location: arch/powerpc/include/asm/atomic.h:309
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_clone_lock
```
```
In net/ipv4/tcp_input.c (c000000000d7f888)
Location: arch/powerpc/include/asm/atomic.h:309
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/unix/af_unix.c (c000000000e147d8)
Location: arch/powerpc/include/asm/atomic.h:309
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
```
```
In net/packet/af_packet.c (c000000000e9873c)
Location: arch/powerpc/include/asm/atomic.h:309
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
Location: arch/riscv/include/asm/atomic.h:45
Inline: True
Inline callers:
  - arch/riscv/kernel/perf_event.c:riscv_pmu_start
```
```
In kernel/fork.c (ffffffe0000bec16)
Location: arch/riscv/include/asm/atomic.h:45
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
  - kernel/fork.c:mm_init
```
```
In kernel/workqueue.c (ffffffe0000d9a6c)
Location: arch/riscv/include/asm/atomic.h:45
Inline: True
Inline callers:
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/workqueue.c:insert_work
  - kernel/workqueue.c:set_work_pool_and_clear_pending
```
```
In kernel/locking/mutex.c (ffffffe00010a408)
Location: arch/riscv/include/asm/atomic.h:45
Inline: True
Inline callers:
  - kernel/locking/mutex.c:__mutex_init
```
```
In kernel/locking/rwsem.c (ffffffe00010aa84)
Location: arch/riscv/include/asm/atomic.h:45
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
Location: arch/riscv/include/asm/atomic.h:45
Inline: True
Inline callers:
  - kernel/acct.c:__se_sys_acct
```
```
In kernel/cgroup/namespace.c (ffffffe000152a90)
Location: arch/riscv/include/asm/atomic.h:45
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
```
```
In kernel/cgroup/pids.c (ffffffe000155d6e)
Location: arch/riscv/include/asm/atomic.h:45
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_max_write
  - kernel/cgroup/pids.c:pids_css_alloc
  - kernel/cgroup/pids.c:pids_css_alloc
  - kernel/cgroup/pids.c:pids_css_alloc
```
```
In kernel/utsname.c (ffffffe00015afb8)
Location: arch/riscv/include/asm/atomic.h:45
Inline: True
Inline callers:
  - kernel/utsname.c:copy_utsname
```
```
In kernel/user_namespace.c (ffffffe00015c1b4)
Location: arch/riscv/include/asm/atomic.h:45
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In kernel/pid_namespace.c (ffffffe00015ccf2)
Location: arch/riscv/include/asm/atomic.h:45
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In kernel/audit_tree.c (ffffffe0001678ec)
Location: arch/riscv/include/asm/atomic.h:45
Inline: True
Inline callers:
  - kernel/audit_tree.c:alloc_chunk
```
```
In kernel/trace/ring_buffer.c (ffffffe000179c64)
Location: arch/riscv/include/asm/atomic.h:45
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
Location: arch/riscv/include/asm/atomic.h:45
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
Location: arch/riscv/include/asm/atomic.h:45
Inline: True
Inline callers:
  - mm/vmalloc.c:set_iounmap_nonlazy
```
```
In mm/page_alloc.c (ffffffe0000161b6)
Location: arch/riscv/include/asm/atomic.h:45
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init_node
```
```
In mm/memblock.c (ffffffe000017270)
Location: arch/riscv/include/asm/atomic.h:45
Inline: True
Inline callers:
  - mm/memblock.c:reset_all_zones_managed_pages
```
```
In mm/swap_state.c (ffffffe0002232a8)
Location: arch/riscv/include/asm/atomic.h:45
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/slub.c (ffffffe00023cb94)
Location: arch/riscv/include/asm/atomic.h:45
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:kmem_cache_open
```
```
In mm/memcontrol.c (ffffffe0008c48f2)
Location: arch/riscv/include/asm/atomic.h:45
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
Location: arch/riscv/include/asm/atomic.h:45
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
```
```
In fs/file_table.c (ffffffe000258060)
Location: arch/riscv/include/asm/atomic.h:45
Inline: True
Inline callers:
  - fs/file_table.c:__alloc_file
```
```
In fs/inode.c (ffffffe000270af6)
Location: arch/riscv/include/asm/atomic.h:45
Inline: True
Inline callers:
  - fs/inode.c:inode_init_always
```
```
In fs/namespace.c (ffffffe000277430)
Location: arch/riscv/include/asm/atomic.h:45
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In fs/nsfs.c (ffffffe00028e942)
Location: arch/riscv/include/asm/atomic.h:45
Inline: True
Inline callers:
  - fs/nsfs.c:ns_prune_dentry
```
```
In fs/ext4/inode.c (ffffffe00030beb0)
Location: arch/riscv/include/asm/atomic.h:45
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/ioctl.c (ffffffe000311cb2)
Location: arch/riscv/include/asm/atomic.h:45
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/super.c (ffffffe00033b3bc)
Location: arch/riscv/include/asm/atomic.h:45
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_alloc_inode
```
```
In fs/ext4/sysfs.c (ffffffe00033c7c6)
Location: arch/riscv/include/asm/atomic.h:45
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_store
```
```
In fs/ext4/xattr.c (ffffffe00033e234)
Location: arch/riscv/include/asm/atomic.h:45
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
```
```
In fs/fat/inode.c (ffffffe00035dcca)
Location: arch/riscv/include/asm/atomic.h:45
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_build_inode
```
```
In fs/fuse/inode.c (ffffffe00037b12c)
Location: arch/riscv/include/asm/atomic.h:45
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_conn_init
  - fs/fuse/inode.c:fuse_conn_init
```
```
In ipc/namespace.c (ffffffe00038ebee)
Location: arch/riscv/include/asm/atomic.h:45
Inline: True
Inline callers:
  - ipc/namespace.c:copy_ipcs
```
```
In block/blk-ioc.c (ffffffe000429666)
Location: arch/riscv/include/asm/atomic.h:45
Inline: True
Inline callers:
  - block/blk-ioc.c:create_task_io_context
```
```
In block/blk-cgroup.c (ffffffe000444450)
Location: arch/riscv/include/asm/atomic.h:45
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_scale_delay
  - block/blk-cgroup.c:blkcg_reset_stats
  - block/blk-cgroup.c:blkcg_reset_stats
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-cgroup.c:blkg_alloc
```
```
In block/blk-iocost.c (ffffffe00044b0c6)
Location: arch/riscv/include/asm/atomic.h:45
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
In lib/percpu-refcount.c (ffffffe000462934)
Location: arch/riscv/include/asm/atomic.h:45
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_init
```
```
In lib/genalloc.c (ffffffe000470850)
Location: arch/riscv/include/asm/atomic.h:45
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_add_owner
```
```
In drivers/tty/tty_ldsem.c (ffffffe0005379f2)
Location: arch/riscv/include/asm/atomic.h:45
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:__init_ldsem
```
```
In drivers/md/md.c (ffffffe0006e174c)
Location: arch/riscv/include/asm/atomic.h:45
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:do_md_stop
```
```
In net/core/net_namespace.c (ffffffe00074d9aa)
Location: arch/riscv/include/asm/atomic.h:45
Inline: True
Inline callers:
  - net/core/net_namespace.c:net_ns_net_init
```
```
In net/ipv4/inet_timewait_sock.c (ffffffe0007d136e)
Location: arch/riscv/include/asm/atomic.h:45
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
```
```
In net/ipv4/inet_connection_sock.c (ffffffe0007d2088)
Location: arch/riscv/include/asm/atomic.h:45
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_clone_lock
```
```
In net/ipv4/tcp_input.c (ffffffe0007da5da)
Location: arch/riscv/include/asm/atomic.h:45
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/unix/af_unix.c (ffffffe00083d16e)
Location: arch/riscv/include/asm/atomic.h:45
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
```
```
In net/packet/af_packet.c (ffffffe00089320c)
Location: arch/riscv/include/asm/atomic.h:45
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
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_setup_perfctr
```
```
In arch/x86/events/amd/uncore.c (ffffffff81009584)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_read
```
```
In arch/x86/events/amd/ibs.c (ffffffff8100ad86)
Location: include/asm-generic/atomic-instrumented.h:852
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
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_event_update
```
```
In arch/x86/events/intel/core.c (ffffffff8100e29e)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_save_and_restart
```
```
In arch/x86/events/intel/bts.c (ffffffff8100ec49)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_update
```
```
In arch/x86/events/intel/ds.c (ffffffff8100fc51)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pmu_save_and_restart_reload
  - arch/x86/events/intel/ds.c:intel_pmu_save_and_restart_reload
```
```
In arch/x86/events/intel/pt.c (ffffffff81014ac0)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_buffer_reset_offsets
  - arch/x86/events/intel/pt.c:pt_buffer_reset_offsets
  - arch/x86/events/intel/pt.c:pt_update_head
```
```
In arch/x86/events/intel/uncore.c (ffffffff81016551)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
```
```
In arch/x86/kernel/pvclock.c (ffffffff81078230)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - arch/x86/kernel/pvclock.c:pvclock_resume
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff828b2d9c)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In kernel/fork.c (ffffffff81096c7d)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
  - kernel/fork.c:mm_init
  - kernel/fork.c:mm_init
```
```
In kernel/workqueue.c (ffffffff810bb8b1)
Location: include/asm-generic/atomic-instrumented.h:852
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
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - kernel/locking/mutex.c:__mutex_init
```
```
In kernel/locking/rwsem.c (ffffffff810fcef5)
Location: include/asm-generic/atomic-instrumented.h:852
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
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - kernel/acct.c:acct_on
```
```
In kernel/cgroup/namespace.c (ffffffff811600bc)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
```
```
In kernel/cgroup/pids.c (ffffffff81163059)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_max_write
  - kernel/cgroup/pids.c:pids_css_alloc
  - kernel/cgroup/pids.c:pids_css_alloc
  - kernel/cgroup/pids.c:pids_css_alloc
```
```
In kernel/utsname.c (ffffffff81169cde)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - kernel/utsname.c:copy_utsname
```
```
In kernel/user_namespace.c (ffffffff8116af97)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In kernel/pid_namespace.c (ffffffff8116bb16)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In kernel/audit_tree.c (ffffffff81177e9d)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - kernel/audit_tree.c:alloc_chunk
```
```
In kernel/trace/ring_buffer.c (ffffffff8119a28c)
Location: include/asm-generic/atomic-instrumented.h:852
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
Location: include/asm-generic/atomic-instrumented.h:852
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
Location: include/asm-generic/atomic-instrumented.h:852
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
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
```
```
In mm/vmalloc.c (ffffffff8126f643)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - mm/vmalloc.c:set_iounmap_nonlazy
```
```
In mm/page_alloc.c (ffffffff828c7888)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init_node
  - mm/page_alloc.c:free_area_init_core_hotplug
```
```
In mm/memblock.c (ffffffff828c89d2)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - mm/memblock.c:reset_all_zones_managed_pages
```
```
In mm/swap_state.c (ffffffff8127fd66)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/slub.c (ffffffff812a2a11)
Location: include/asm-generic/atomic-instrumented.h:852
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
Location: include/asm-generic/atomic-instrumented.h:852
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
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
```
```
In fs/file_table.c (ffffffff812d7131)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - fs/file_table.c:__alloc_file
```
```
In fs/super.c (ffffffff812d8453)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - fs/super.c:thaw_super_locked
  - fs/super.c:thaw_super_locked
  - fs/super.c:freeze_super
```
```
In fs/inode.c (ffffffff812f406a)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - fs/inode.c:inode_init_always
```
```
In fs/namespace.c (ffffffff812f9ae2)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In fs/nsfs.c (ffffffff81314e29)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - fs/nsfs.c:ns_prune_dentry
```
```
In fs/aio.c (0)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
```
```
In fs/io_uring.c (0)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
```
```
In fs/ext4/inode.c (ffffffff813a73b1)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/ioctl.c (ffffffff813ae3d6)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/super.c (ffffffff813ded2c)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_alloc_inode
```
```
In fs/ext4/sysfs.c (ffffffff813e0abf)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_store
```
```
In fs/ext4/xattr.c (ffffffff813e2a75)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
```
```
In fs/fat/inode.c (ffffffff8140509b)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_build_inode
```
```
In fs/fuse/inode.c (ffffffff81425024)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_conn_init
  - fs/fuse/inode.c:fuse_conn_init
```
```
In ipc/namespace.c (ffffffff8143c894)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - ipc/namespace.c:copy_ipcs
```
```
In block/blk-ioc.c (ffffffff814e2c66)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - block/blk-ioc.c:create_task_io_context
```
```
In block/blk-cgroup.c (ffffffff81500db0)
Location: include/asm-generic/atomic-instrumented.h:852
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
Location: include/asm-generic/atomic-instrumented.h:852
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
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_init
```
```
In lib/genalloc.c (ffffffff8152fd8e)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_add_owner
```
```
In drivers/tty/tty_ldsem.c (ffffffff81653cf5)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:__init_ldsem
```
```
In drivers/iommu/iova.c (ffffffff816a2375)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - drivers/iommu/iova.c:init_iova_flush_queue
  - drivers/iommu/iova.c:init_iova_flush_queue
```
```
In drivers/md/md.c (ffffffff818465e5)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:do_md_stop
```
```
In net/core/net_namespace.c (ffffffff818c4675)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - net/core/net_namespace.c:net_ns_net_init
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81959e19)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
```
```
In net/ipv4/inet_connection_sock.c (ffffffff8195aa44)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_clone_lock
```
```
In net/ipv4/tcp_input.c (ffffffff819648b9)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/unix/af_unix.c (ffffffff819d021b)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
```
```
In net/packet/af_packet.c (ffffffff81a2ebd7)
Location: include/asm-generic/atomic-instrumented.h:852
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
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_setup_perfctr
```
```
In arch/x86/events/amd/uncore.c (ffffffff8100827f)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_read
```
```
In arch/x86/events/amd/ibs.c (ffffffff81009713)
Location: include/asm-generic/atomic-instrumented.h:852
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
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_event_start
  - arch/x86/events/msr.c:msr_event_update
```
```
In arch/x86/events/intel/core.c (ffffffff8100ceed)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_save_and_restart
```
```
In arch/x86/events/intel/bts.c (ffffffff8100d9a9)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_update
```
```
In arch/x86/events/intel/ds.c (ffffffff8100e9c9)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pmu_save_and_restart_reload
  - arch/x86/events/intel/ds.c:intel_pmu_save_and_restart_reload
```
```
In arch/x86/events/intel/pt.c (ffffffff81013d90)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_buffer_reset_offsets
  - arch/x86/events/intel/pt.c:pt_buffer_reset_offsets
  - arch/x86/events/intel/pt.c:pt_update_head
```
```
In arch/x86/events/intel/uncore.c (ffffffff81015981)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
```
```
In arch/x86/kernel/pvclock.c (ffffffff81067ae0)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - arch/x86/kernel/pvclock.c:pvclock_resume
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff828aaf1d)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In kernel/fork.c (ffffffff810856fd)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
  - kernel/fork.c:mm_init
  - kernel/fork.c:mm_init
```
```
In kernel/workqueue.c (ffffffff810aa350)
Location: include/asm-generic/atomic-instrumented.h:852
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
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - kernel/locking/mutex.c:__mutex_init
```
```
In kernel/locking/rwsem.c (ffffffff810ed105)
Location: include/asm-generic/atomic-instrumented.h:852
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
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
```
```
In kernel/acct.c (ffffffff8114408e)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - kernel/acct.c:acct_on
```
```
In kernel/cgroup/namespace.c (ffffffff81153326)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
```
```
In kernel/cgroup/pids.c (ffffffff811562a9)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_max_write
  - kernel/cgroup/pids.c:pids_css_alloc
  - kernel/cgroup/pids.c:pids_css_alloc
  - kernel/cgroup/pids.c:pids_css_alloc
```
```
In kernel/utsname.c (ffffffff8115cede)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - kernel/utsname.c:copy_utsname
```
```
In kernel/user_namespace.c (ffffffff8115e197)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In kernel/pid_namespace.c (ffffffff8115ed16)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In kernel/audit_tree.c (ffffffff8116b03d)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - kernel/audit_tree.c:alloc_chunk
```
```
In kernel/trace/ring_buffer.c (ffffffff8118d30c)
Location: include/asm-generic/atomic-instrumented.h:852
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
Location: include/asm-generic/atomic-instrumented.h:852
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
Location: include/asm-generic/atomic-instrumented.h:852
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
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
```
```
In mm/vmalloc.c (ffffffff812615b3)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - mm/vmalloc.c:set_iounmap_nonlazy
```
```
In mm/page_alloc.c (ffffffff828bffad)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init_node
  - mm/page_alloc.c:free_area_init_core_hotplug
```
```
In mm/memblock.c (ffffffff828c10f7)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - mm/memblock.c:reset_all_zones_managed_pages
```
```
In mm/swap_state.c (ffffffff81271b92)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/slub.c (ffffffff812944e1)
Location: include/asm-generic/atomic-instrumented.h:852
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
Location: include/asm-generic/atomic-instrumented.h:852
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
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
```
```
In fs/file_table.c (ffffffff812c7db1)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - fs/file_table.c:__alloc_file
```
```
In fs/super.c (ffffffff812c90d3)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - fs/super.c:thaw_super_locked
  - fs/super.c:thaw_super_locked
  - fs/super.c:freeze_super
```
```
In fs/inode.c (ffffffff812e4c9a)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - fs/inode.c:inode_init_always
```
```
In fs/namespace.c (ffffffff812ea702)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In fs/nsfs.c (ffffffff81305a19)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - fs/nsfs.c:ns_prune_dentry
```
```
In fs/aio.c (0)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
```
```
In fs/io_uring.c (0)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
```
```
In fs/ext4/inode.c (ffffffff81397e41)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/ioctl.c (ffffffff8139ee66)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/super.c (ffffffff813cf7ac)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_alloc_inode
```
```
In fs/ext4/sysfs.c (ffffffff813d153f)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_store
```
```
In fs/ext4/xattr.c (ffffffff813d34f5)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
```
```
In fs/fat/inode.c (ffffffff813f5b1b)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_build_inode
```
```
In fs/fuse/inode.c (ffffffff81415aa4)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_conn_init
  - fs/fuse/inode.c:fuse_conn_init
```
```
In ipc/namespace.c (ffffffff8142d304)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - ipc/namespace.c:copy_ipcs
```
```
In block/blk-ioc.c (ffffffff814d35f6)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - block/blk-ioc.c:create_task_io_context
```
```
In block/blk-cgroup.c (ffffffff814f12c0)
Location: include/asm-generic/atomic-instrumented.h:852
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
Location: include/asm-generic/atomic-instrumented.h:852
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
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_init
```
```
In lib/genalloc.c (ffffffff8152006e)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_add_owner
```
```
In drivers/tty/tty_ldsem.c (ffffffff816340d5)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:__init_ldsem
```
```
In drivers/iommu/iova.c (ffffffff8167fd65)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - drivers/iommu/iova.c:init_iova_flush_queue
  - drivers/iommu/iova.c:init_iova_flush_queue
```
```
In drivers/md/md.c (ffffffff8180dc45)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:do_md_stop
```
```
In drivers/firmware/efi/cper.c (ffffffff818459bb)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_next_record_id
  - drivers/firmware/efi/cper.c:cper_next_record_id
```
```
In net/core/net_namespace.c (ffffffff8187e5b5)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - net/core/net_namespace.c:net_ns_net_init
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81913909)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81914534)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_clone_lock
```
```
In net/ipv4/tcp_input.c (ffffffff8191e3a9)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/unix/af_unix.c (ffffffff8198cfdb)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
```
```
In net/packet/af_packet.c (ffffffff819ebdc7)
Location: include/asm-generic/atomic-instrumented.h:852
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
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_setup_perfctr
```
```
In arch/x86/events/amd/uncore.c (ffffffff81009544)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_read
```
```
In arch/x86/events/amd/ibs.c (ffffffff8100ad46)
Location: include/asm-generic/atomic-instrumented.h:852
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
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_event_update
```
```
In arch/x86/events/intel/core.c (ffffffff8100e25e)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_save_and_restart
```
```
In arch/x86/events/intel/bts.c (ffffffff8100ec09)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_update
```
```
In arch/x86/events/intel/ds.c (ffffffff8100fc11)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pmu_save_and_restart_reload
  - arch/x86/events/intel/ds.c:intel_pmu_save_and_restart_reload
```
```
In arch/x86/events/intel/pt.c (ffffffff81014a80)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_buffer_reset_offsets
  - arch/x86/events/intel/pt.c:pt_buffer_reset_offsets
  - arch/x86/events/intel/pt.c:pt_update_head
```
```
In arch/x86/events/intel/uncore.c (ffffffff81016511)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
```
```
In arch/x86/kernel/pvclock.c (ffffffff810781e0)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - arch/x86/kernel/pvclock.c:pvclock_resume
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff828c5c9b)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In kernel/fork.c (ffffffff81096c2d)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
  - kernel/fork.c:mm_init
  - kernel/fork.c:mm_init
```
```
In kernel/workqueue.c (ffffffff810bae11)
Location: include/asm-generic/atomic-instrumented.h:852
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
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - kernel/locking/mutex.c:__mutex_init
```
```
In kernel/locking/rwsem.c (ffffffff810fa0b5)
Location: include/asm-generic/atomic-instrumented.h:852
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
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - kernel/acct.c:acct_on
```
```
In kernel/cgroup/namespace.c (ffffffff8115de8c)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
```
```
In kernel/cgroup/pids.c (ffffffff81160e29)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_max_write
  - kernel/cgroup/pids.c:pids_css_alloc
  - kernel/cgroup/pids.c:pids_css_alloc
  - kernel/cgroup/pids.c:pids_css_alloc
```
```
In kernel/utsname.c (ffffffff81167aae)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - kernel/utsname.c:copy_utsname
```
```
In kernel/user_namespace.c (ffffffff81168d67)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In kernel/pid_namespace.c (ffffffff811698e6)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In kernel/audit_tree.c (ffffffff81175c6d)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - kernel/audit_tree.c:alloc_chunk
```
```
In kernel/trace/ring_buffer.c (ffffffff8119805c)
Location: include/asm-generic/atomic-instrumented.h:852
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
Location: include/asm-generic/atomic-instrumented.h:852
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
Location: include/asm-generic/atomic-instrumented.h:852
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
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
```
```
In mm/vmalloc.c (ffffffff8126d3e3)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - mm/vmalloc.c:set_iounmap_nonlazy
```
```
In mm/page_alloc.c (ffffffff828da608)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init_node
  - mm/page_alloc.c:free_area_init_core_hotplug
```
```
In mm/memblock.c (ffffffff828db752)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - mm/memblock.c:reset_all_zones_managed_pages
```
```
In mm/swap_state.c (ffffffff8127dbba)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/slub.c (ffffffff812a0821)
Location: include/asm-generic/atomic-instrumented.h:852
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
Location: include/asm-generic/atomic-instrumented.h:852
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
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
```
```
In fs/file_table.c (ffffffff812d4f41)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - fs/file_table.c:__alloc_file
```
```
In fs/super.c (ffffffff812d6263)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - fs/super.c:thaw_super_locked
  - fs/super.c:thaw_super_locked
  - fs/super.c:freeze_super
```
```
In fs/inode.c (ffffffff812f1e7a)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - fs/inode.c:inode_init_always
```
```
In fs/namespace.c (ffffffff812f78d2)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In fs/nsfs.c (ffffffff81312c19)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - fs/nsfs.c:ns_prune_dentry
```
```
In fs/aio.c (0)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
```
```
In fs/io_uring.c (0)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
```
```
In fs/ext4/inode.c (ffffffff813a4c11)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/ioctl.c (ffffffff813abc36)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/super.c (ffffffff813dc0d3)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_alloc_inode
```
```
In fs/ext4/sysfs.c (ffffffff813dde3f)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_store
```
```
In fs/ext4/xattr.c (ffffffff813dfdf5)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
```
```
In fs/fat/inode.c (ffffffff8140241b)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_build_inode
```
```
In fs/fuse/inode.c (ffffffff814211c4)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_conn_init
  - fs/fuse/inode.c:fuse_conn_init
```
```
In ipc/namespace.c (ffffffff81438a34)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - ipc/namespace.c:copy_ipcs
```
```
In block/blk-ioc.c (ffffffff814decf6)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - block/blk-ioc.c:create_task_io_context
```
```
In block/blk-cgroup.c (ffffffff814fce40)
Location: include/asm-generic/atomic-instrumented.h:852
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
Location: include/asm-generic/atomic-instrumented.h:852
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
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_init
```
```
In lib/genalloc.c (ffffffff8152bace)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_add_owner
```
```
In drivers/tty/tty_ldsem.c (ffffffff816820b5)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:__init_ldsem
```
```
In drivers/iommu/iova.c (ffffffff816d05e5)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - drivers/iommu/iova.c:init_iova_flush_queue
  - drivers/iommu/iova.c:init_iova_flush_queue
```
```
In drivers/md/md.c (ffffffff81895c15)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:do_md_stop
```
```
In drivers/firmware/efi/cper.c (ffffffff818e011b)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_next_record_id
  - drivers/firmware/efi/cper.c:cper_next_record_id
```
```
In net/core/net_namespace.c (ffffffff81915675)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - net/core/net_namespace.c:net_ns_net_init
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff819c45e9)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819c5214)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_clone_lock
```
```
In net/ipv4/tcp_input.c (ffffffff819cf089)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/unix/af_unix.c (ffffffff81a3ac9b)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
```
```
In net/packet/af_packet.c (ffffffff81a9a787)
Location: include/asm-generic/atomic-instrumented.h:852
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
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_setup_perfctr
```
```
In arch/x86/events/amd/uncore.c (ffffffff810096a4)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_read
```
```
In arch/x86/events/amd/ibs.c (ffffffff8100acd6)
Location: include/asm-generic/atomic-instrumented.h:852
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
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_event_update
```
```
In arch/x86/events/intel/core.c (ffffffff8100e42e)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_save_and_restart
```
```
In arch/x86/events/intel/bts.c (ffffffff8100edd9)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_update
```
```
In arch/x86/events/intel/ds.c (ffffffff8100fe21)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pmu_save_and_restart_reload
  - arch/x86/events/intel/ds.c:intel_pmu_save_and_restart_reload
```
```
In arch/x86/events/intel/pt.c (ffffffff81014cc0)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_buffer_reset_offsets
  - arch/x86/events/intel/pt.c:pt_buffer_reset_offsets
  - arch/x86/events/intel/pt.c:pt_update_head
```
```
In arch/x86/events/intel/uncore.c (ffffffff81016751)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
```
```
In arch/x86/kernel/pvclock.c (ffffffff8107a2e0)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - arch/x86/kernel/pvclock.c:pvclock_resume
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff828c8e41)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff8109a6ca)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:param_set_local64
```
```
In kernel/fork.c (ffffffff8109eacd)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
  - kernel/fork.c:mm_init
  - kernel/fork.c:mm_init
```
```
In kernel/workqueue.c (ffffffff810c42d1)
Location: include/asm-generic/atomic-instrumented.h:852
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
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - kernel/locking/mutex.c:__mutex_init
```
```
In kernel/locking/rwsem.c (ffffffff81105225)
Location: include/asm-generic/atomic-instrumented.h:852
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
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - kernel/acct.c:acct_on
```
```
In kernel/cgroup/namespace.c (ffffffff8116b0f7)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
```
```
In kernel/cgroup/pids.c (ffffffff8116e279)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_max_write
  - kernel/cgroup/pids.c:pids_css_alloc
  - kernel/cgroup/pids.c:pids_css_alloc
  - kernel/cgroup/pids.c:pids_css_alloc
```
```
In kernel/utsname.c (ffffffff8117518e)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - kernel/utsname.c:copy_utsname
```
```
In kernel/user_namespace.c (ffffffff81176457)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In kernel/pid_namespace.c (ffffffff81177006)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In kernel/audit_tree.c (ffffffff8118355d)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - kernel/audit_tree.c:alloc_chunk
```
```
In kernel/trace/ring_buffer.c (ffffffff811a5c8c)
Location: include/asm-generic/atomic-instrumented.h:852
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
Location: include/asm-generic/atomic-instrumented.h:852
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
Location: include/asm-generic/atomic-instrumented.h:852
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
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
```
```
In mm/vmalloc.c (ffffffff8127cd73)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - mm/vmalloc.c:set_iounmap_nonlazy
```
```
In mm/page_alloc.c (ffffffff828dfa29)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init_node
  - mm/page_alloc.c:free_area_init_core_hotplug
```
```
In mm/memblock.c (ffffffff828e0b73)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - mm/memblock.c:reset_all_zones_managed_pages
```
```
In mm/swap_state.c (ffffffff8128d76a)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/slub.c (ffffffff812b0961)
Location: include/asm-generic/atomic-instrumented.h:852
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
Location: include/asm-generic/atomic-instrumented.h:852
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
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
```
```
In fs/file_table.c (ffffffff812e5da1)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - fs/file_table.c:__alloc_file
```
```
In fs/super.c (ffffffff812e6e23)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - fs/super.c:thaw_super_locked
  - fs/super.c:thaw_super_locked
  - fs/super.c:freeze_super
```
```
In fs/inode.c (ffffffff8130344a)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - fs/inode.c:inode_init_always
```
```
In fs/namespace.c (ffffffff81308be2)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In fs/nsfs.c (ffffffff81324449)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - fs/nsfs.c:ns_prune_dentry
```
```
In fs/aio.c (0)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
```
```
In fs/io_uring.c (0)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
```
```
In fs/ext4/inode.c (ffffffff813b9326)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/ioctl.c (ffffffff813c05d6)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/super.c (ffffffff813f14ad)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_alloc_inode
```
```
In fs/ext4/sysfs.c (ffffffff813f325f)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_store
```
```
In fs/ext4/xattr.c (ffffffff813f5215)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
```
```
In fs/fat/inode.c (ffffffff814183eb)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_build_inode
```
```
In fs/fuse/inode.c (ffffffff81438044)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_conn_init
  - fs/fuse/inode.c:fuse_conn_init
```
```
In ipc/namespace.c (ffffffff8144fba4)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - ipc/namespace.c:copy_ipcs
```
```
In block/blk-ioc.c (ffffffff814f7b66)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - block/blk-ioc.c:create_task_io_context
```
```
In block/blk-cgroup.c (ffffffff81515ef0)
Location: include/asm-generic/atomic-instrumented.h:852
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
Location: include/asm-generic/atomic-instrumented.h:852
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
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_init
```
```
In lib/genalloc.c (ffffffff8154536e)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_add_owner
```
```
In drivers/tty/tty_ldsem.c (ffffffff8169c6f5)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:__init_ldsem
```
```
In drivers/iommu/iova.c (ffffffff816eab75)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - drivers/iommu/iova.c:init_iova_flush_queue
  - drivers/iommu/iova.c:init_iova_flush_queue
```
```
In drivers/md/md.c (ffffffff818b1a69)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:do_md_stop
```
```
In drivers/firmware/efi/cper.c (ffffffff818fcbbb)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_next_record_id
  - drivers/firmware/efi/cper.c:cper_next_record_id
```
```
In net/core/net_namespace.c (ffffffff81936855)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - net/core/net_namespace.c:net_ns_net_init
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff819ce189)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819cece4)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_clone_lock
```
```
In net/ipv4/tcp_input.c (ffffffff819d8c19)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/unix/af_unix.c (ffffffff81a45f1b)
Location: include/asm-generic/atomic-instrumented.h:852
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
```
```
In net/packet/af_packet.c (ffffffff81aa74da)
Location: include/asm-generic/atomic-instrumented.h:852
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
