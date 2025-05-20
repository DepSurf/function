# Function: <code>arch_atomic_set</code>

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
In arch/x86/kernel/tboot.c (ffffffff826ddd9a)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff8104b5ac)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:fake_panic_set
  - arch/x86/kernel/cpu/mcheck/mce.c:fake_panic_set
  - arch/x86/kernel/cpu/mcheck/mce.c:fake_panic_set
  - arch/x86/kernel/cpu/mcheck/mce.c:fake_panic_set
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
```
```
In arch/x86/kernel/cpu/mcheck/mce_amd.c (ffffffff81051313)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In arch/x86/kernel/cpu/mcheck/therm_throt.c (ffffffff81051e44)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff810557ad)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In arch/x86/kernel/reboot.c (ffffffff81059535)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff8105bed9)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_target
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
```
```
In arch/x86/kernel/kgdb.c (ffffffff8106a132)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In arch/x86/mm/init_64.c (ffffffff819e8366)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pagetable
```
```
In kernel/fork.c (ffffffff8108aaf8)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
  - kernel/fork.c:mm_init
  - kernel/fork.c:mm_init
```
```
In kernel/softirq.c (ffffffff81094727)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/softirq.c:tasklet_hrtimer_init
```
```
In kernel/user.c (ffffffff8109bf6e)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/user.c:alloc_uid
```
```
In kernel/workqueue.c (ffffffff810af6c4)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_offline_cpu
  - kernel/workqueue.c:__alloc_workqueue_key
  - kernel/workqueue.c:flush_workqueue_prep_pwqs
```
```
In kernel/pid.c (ffffffff810b0d64)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/pid.c:alloc_pid
```
```
In kernel/nsproxy.c (ffffffff810b42ce)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/nsproxy.c:create_new_namespaces
```
```
In kernel/cred.c (ffffffff810b5a8e)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:cred_alloc_blank
```
```
In kernel/smpboot.c (ffffffff810b7751)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/smpboot.c:cpu_wait_death
  - kernel/smpboot.c:cpu_check_up_prepare
```
```
In kernel/groups.c (ffffffff810b81f8)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/groups.c:groups_alloc
```
```
In kernel/sched/core.c (ffffffff826f590a)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init
```
```
In kernel/sched/fair.c (ffffffff810cdc4e)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_fault
```
```
In kernel/sched/cpupri.c (ffffffff810da174)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_init
```
```
In kernel/sched/topology.c (ffffffff810db327)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:init_defrootdomain
```
```
In kernel/sched/autogroup.c (ffffffff810dd3fa)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
  - kernel/sched/autogroup.c:autogroup_init
```
```
In kernel/locking/mutex.c (ffffffff810e4714)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/locking/mutex.c:__mutex_init
```
```
In kernel/locking/rwsem-xadd.c (ffffffff810e657c)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/locking/rwsem-xadd.c:__init_rwsem
```
```
In kernel/power/swap.c (ffffffff810ee34a)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:save_image
```
```
In kernel/irq/manage.c (ffffffff810f67fd)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_notifier
```
```
In kernel/rcu/srcutree.c (ffffffff811038bc)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
```
```
In kernel/rcu/tree.c (ffffffff81105363)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/rcu/tree.c:_rcu_barrier
```
```
In kernel/time/posix-clock.c (ffffffff81122965)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/time/posix-clock.c:posix_clock_register
```
```
In kernel/futex.c (ffffffff826f927b)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/futex.c:futex_init
```
```
In kernel/module.c (ffffffff8113293e)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/module.c:load_module
```
```
In kernel/kexec_core.c (ffffffff81137c00)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_free_reserved_phys_range
  - kernel/kexec_core.c:crash_kexec
```
```
In kernel/cgroup/cgroup.c (ffffffff8113d290)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:find_css_set
```
```
In kernel/cgroup/namespace.c (ffffffff81144485)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
```
```
In kernel/utsname.c (ffffffff8114c4a3)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/utsname.c:copy_utsname
```
```
In kernel/user_namespace.c (ffffffff8114d768)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In kernel/pid_namespace.c (ffffffff8114e2d8)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In kernel/stop_machine.c (ffffffff8114f1f4)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:stop_machine_cpuslocked
  - kernel/stop_machine.c:stop_two_cpus
  - kernel/stop_machine.c:multi_cpu_stop
  - kernel/stop_machine.c:cpu_stop_init_done
```
```
In kernel/audit_watch.c (ffffffff811588d8)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_init_watch
```
```
In kernel/audit_tree.c (ffffffff8115aebc)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_make_tree
```
```
In kernel/debug/debug_core.c (ffffffff8115e87e)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_tasklet_bpt
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff8116366f)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In kernel/hung_task.c (ffffffff81169b15)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/hung_task.c:reset_hung_task_detector
```
```
In kernel/seccomp.c (ffffffff8116bb42)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In kernel/relay.c (ffffffff8116c62c)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/relay.c:__relay_reset
```
```
In kernel/trace/ftrace.c (ffffffff811779f3)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_graph_init_task
  - kernel/trace/ftrace.c:ftrace_graph_init_task
  - kernel/trace/ftrace.c:register_ftrace_graph
  - kernel/trace/ftrace.c:register_ftrace_graph
```
```
In kernel/trace/tracing_map.c (ffffffff8118a3ad)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_create
  - kernel/trace/tracing_map.c:tracing_map_clear
```
```
In kernel/trace/blktrace.c (ffffffff81190fed)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:do_blk_trace_setup
```
```
In kernel/trace/trace_events.c (ffffffff81192c3c)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_create_new_event
  - kernel/trace/trace_events.c:trace_create_new_event
```
```
In kernel/bpf/syscall.c (ffffffff811b5df7)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:map_create
```
```
In kernel/bpf/btf.c (ffffffff811c925a)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_new_fd
```
```
In kernel/bpf/sockmap.c (ffffffff811cd322)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In kernel/events/core.c (ffffffff811d860f)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:alloc_perf_context
```
```
In kernel/events/ring_buffer.c (ffffffff811e321b)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc
  - kernel/events/ring_buffer.c:rb_alloc_aux
  - kernel/events/ring_buffer.c:perf_aux_output_skip
  - kernel/events/ring_buffer.c:perf_aux_output_end
  - kernel/events/ring_buffer.c:perf_aux_output_begin
  - kernel/events/ring_buffer.c:perf_output_put_handle
```
```
In kernel/events/uprobes.c (ffffffff811e5db7)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__create_xol_area
```
```
In kernel/padata.c (ffffffff811e72d6)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_alloc_pd
```
```
In kernel/jump_label.c (ffffffff811e85d7)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/jump_label.c:static_key_enable_cpuslocked
```
```
In mm/filemap.c (ffffffff811f0c9a)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/page_alloc.c (ffffffff811f7033)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:make_alloc_exact
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:check_new_page_bad
  - mm/page_alloc.c:init_cma_reserved_pageblock
  - mm/page_alloc.c:init_cma_reserved_pageblock
  - mm/page_alloc.c:__free_pages_bootmem
  - mm/page_alloc.c:__free_pages_bootmem
  - mm/page_alloc.c:__free_pages_bootmem
  - mm/page_alloc.c:bad_page
```
```
In mm/backing-dev.c (ffffffff81218c05)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_alloc_node
  - mm/backing-dev.c:wb_congested_get_create
  - mm/backing-dev.c:default_bdi_init
```
```
In mm/rmap.c (ffffffff81240424)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - mm/rmap.c:hugepage_add_new_anon_rmap
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:anon_vma_ctor
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:__anon_vma_prepare
```
```
In mm/vmalloc.c (ffffffff81242bbe)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - mm/vmalloc.c:set_iounmap_nonlazy
```
```
In mm/swap_state.c (ffffffff812482f3)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - mm/swap_state.c:init_swap_address_space
  - mm/swap_state.c:swap_cluster_readahead
```
```
In mm/frontswap.c (ffffffff8124f06f)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_invalidate_area
```
```
In mm/zswap.c (ffffffff8124f94e)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - mm/zswap.c:zswap_pool_create
```
```
In mm/hugetlb.c (ffffffff812522b4)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:update_and_free_page
  - mm/hugetlb.c:update_and_free_page
  - mm/hugetlb.c:update_and_free_page
  - mm/hugetlb.c:dequeue_huge_page_nodemask
  - mm/hugetlb.c:resv_map_alloc
```
```
In mm/mempolicy.c (ffffffff8125d0af)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:__mpol_dup
```
```
In mm/memory_hotplug.c (ffffffff8126b72c)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - mm/memory_hotplug.c:generic_online_page
  - mm/memory_hotplug.c:put_page_bootmem
```
```
In mm/huge_memory.c (ffffffff81273fb6)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In mm/memcontrol.c (ffffffff8127f7c5)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_select_victim_node
```
```
In mm/zpool.c (ffffffff8128bdf9)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - mm/zpool.c:zpool_register_driver
```
```
In mm/zsmalloc.c (ffffffff8128cdbf)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - mm/zsmalloc.c:reset_page
```
```
In mm/hmm.c (ffffffff81292b1c)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In fs/super.c (ffffffff8129d30b)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/super.c:sget_userns
```
```
In fs/exec.c (ffffffff812a2421)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In fs/dcache.c (ffffffff812b732a)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/dcache.c:__d_alloc
```
```
In fs/inode.c (ffffffff812b825f)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/inode.c:inode_init_always
  - fs/inode.c:inode_init_always
  - fs/inode.c:inode_init_always
  - fs/inode.c:inode_init_always
```
```
In fs/file.c (ffffffff812bc290)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/file.c:dup_fd
```
```
In fs/namespace.c (ffffffff812bd510)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In fs/block_dev.c (ffffffff812dc5f7)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_direct_IO
```
```
In fs/notify/group.c (ffffffff812e50c4)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_alloc_group
  - fs/notify/group.c:fsnotify_alloc_group
  - fs/notify/group.c:fsnotify_alloc_group
```
```
In fs/notify/mark.c (ffffffff812e5302)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_init_mark
```
```
In fs/eventfd.c (ffffffff812eeeb1)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/eventfd.c:do_eventfd
```
```
In fs/userfaultfd.c (ffffffff812ef8b3)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/userfaultfd.c:__ia32_sys_userfaultfd
  - fs/userfaultfd.c:__x64_sys_userfaultfd
  - fs/userfaultfd.c:dup_userfaultfd
```
```
In fs/aio.c (ffffffff812f5195)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/aio.c:__ia32_sys_io_destroy
  - fs/aio.c:__x64_sys_io_destroy
  - fs/aio.c:exit_aio
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
```
```
In fs/mbcache.c (ffffffff8130a5bb)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/posix_acl.c (ffffffff8130ad27)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/posix_acl.c:posix_acl_clone
  - fs/posix_acl.c:posix_acl_alloc
```
```
In fs/coredump.c (ffffffff8130c5e8)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/iomap.c (ffffffff8130f864)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/iomap.c:iomap_dio_rw
```
```
In fs/quota/dquot.c (ffffffff813123cf)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/quota/dquot.c:dqget
```
```
In fs/proc/generic.c (ffffffff813203fd)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/proc/generic.c:__proc_create
```
```
In fs/kernfs/dir.c (ffffffff8132c350)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/kernfs/dir.c:__kernfs_new_node
  - fs/kernfs/dir.c:__kernfs_new_node
```
```
In fs/kernfs/file.c (ffffffff8132e52b)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_fop_open
  - fs/kernfs/file.c:kernfs_fop_open
```
```
In fs/configfs/dir.c (ffffffff8133243f)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_new_dirent
```
```
In fs/configfs/item.c (ffffffff813345a8)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/configfs/item.c:config_group_init_type_name
  - fs/configfs/item.c:config_item_init_type_name
```
```
In fs/ext4/mballoc.c (ffffffff81365cca)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
```
```
In fs/ext4/page-io.c (ffffffff8137027f)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_init_io_end
```
```
In fs/ext4/super.c (ffffffff8137e0e0)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_alloc_inode
```
```
In fs/jbd2/transaction.c (ffffffff81392cb4)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
```
```
In fs/jbd2/journal.c (ffffffff8139b4f9)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_init_common
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/ecryptfs/main.c (ffffffff813b5ed5)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_get_lower_file
```
```
In fs/ecryptfs/super.c (ffffffff813b60fd)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/ecryptfs/super.c:ecryptfs_alloc_inode
```
```
In fs/ecryptfs/miscdev.c (ffffffff827152aa)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/ecryptfs/miscdev.c:ecryptfs_init_ecryptfs_miscdev
```
```
In fs/fuse/dev.c (ffffffff813c00eb)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_request_init
```
```
In fs/fuse/file.c (ffffffff813cbcbb)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_file_alloc
```
```
In fs/fuse/inode.c (ffffffff813cd827)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_conn_init
  - fs/fuse/inode.c:fuse_conn_init
  - fs/fuse/inode.c:fuse_conn_init
```
```
In fs/debugfs/file.c (ffffffff813d1865)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_atomic_t_set
  - fs/debugfs/file.c:debugfs_file_get
```
```
In ipc/util.c (ffffffff813d6246)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In ipc/msg.c (ffffffff827157aa)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - ipc/msg.c:msg_init
  - ipc/msg.c:msg_init
```
```
In ipc/sem.c (ffffffff813dd07e)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - ipc/sem.c:copy_semundo
  - ipc/sem.c:do_semtimedop
```
```
In ipc/namespace.c (ffffffff813e360d)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - ipc/namespace.c:copy_ipcs
```
```
In security/keys/key.c (ffffffff813e4d87)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_user_lookup
  - security/keys/key.c:key_user_lookup
  - security/keys/key.c:key_user_lookup
```
```
In security/selinux/avc.c (ffffffff813f7efb)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - security/selinux/avc.c:selinux_avc_init
  - security/selinux/avc.c:selinux_avc_init
```
```
In security/selinux/ss/services.c (ffffffff814147ac)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
```
```
In security/tomoyo/condition.c (ffffffff81426f48)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
```
```
In security/tomoyo/gc.c (ffffffff8142b39d)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In security/tomoyo/memory.c (ffffffff8142bdd8)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_name
  - security/tomoyo/memory.c:tomoyo_get_group
```
```
In security/apparmor/apparmorfs.c (ffffffff81432c81)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_write_access
```
```
In security/apparmor/lib.c (ffffffff8143576a)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - security/apparmor/lib.c:aa_str_alloc
```
```
In security/apparmor/match.c (ffffffff81436131)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
```
```
In security/apparmor/policy_unpack.c (ffffffff8143f9c2)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:aa_loaddata_alloc
```
```
In security/apparmor/policy_ns.c (ffffffff81445c7f)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:alloc_ns
```
```
In security/apparmor/label.c (ffffffff81446f8f)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_alloc
  - security/apparmor/label.c:aa_alloc_proxy
```
```
In crypto/api.c (ffffffff81458764)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - crypto/api.c:crypto_alg_mod_lookup
```
```
In crypto/algapi.c (ffffffff8145957a)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - crypto/algapi.c:__crypto_register_alg
  - crypto/algapi.c:crypto_check_alg
```
```
In block/bio.c (ffffffff8147a6d0)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - block/bio.c:bio_reset
  - block/bio.c:bio_init
  - block/bio.c:bio_init
```
```
In block/blk-tag.c (ffffffff81485b39)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - block/blk-tag.c:__blk_queue_init_tags
```
```
In block/blk-ioc.c (ffffffff814893cb)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - block/blk-ioc.c:create_task_io_context
  - block/blk-ioc.c:create_task_io_context
```
```
In block/blk-mq.c (ffffffff814916b6)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/bsg.c (ffffffff814a5591)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - block/bsg.c:bsg_open
```
```
In block/bsg-lib.c (ffffffff814a6984)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_request_fn
```
```
In block/blk-cgroup.c (ffffffff814a759f)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_alloc
```
```
In block/blk-wbt.c (ffffffff814b9bf9)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_init
```
```
In lib/rhashtable.c (ffffffff814ccd59)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_init
```
```
In lib/cpu_rmap.c (ffffffff814f2a03)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - lib/cpu_rmap.c:alloc_cpu_rmap
```
```
In lib/sbitmap.c (ffffffff814f8994)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In drivers/pinctrl/core.c (ffffffff814fccd0)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:create_pinctrl
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff81541101)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
```
```
In drivers/rapidio/rio.c (ffffffff8154ab1d)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_register_mport
  - drivers/rapidio/rio.c:rio_mport_initialize
  - drivers/rapidio/rio.c:rio_del_device
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff81553d3d)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:register_framebuffer
```
```
In drivers/acpi/ec.c (ffffffff8157a315)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_add_query_handler
```
```
In drivers/acpi/apei/ghes.c (ffffffff815d6932)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
```
```
In drivers/clk/clk.c (ffffffff815e3f0e)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_register
```
```
In drivers/dma/dmaengine.c (ffffffff815e8adf)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaengine_get_unmap_data
  - drivers/dma/dmaengine.c:dma_async_device_register
```
```
In drivers/xen/balloon.c (ffffffff815f3e53)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_process
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff815fe17d)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_open
```
```
In drivers/reset/core.c (ffffffff8160eb48)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/reset/core.c:__reset_control_get_from_lookup
```
```
In drivers/tty/tty_io.c (ffffffff8161262b)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:alloc_tty_struct
```
```
In drivers/tty/tty_buffer.c (ffffffff81619599)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_init
  - drivers/tty/tty_buffer.c:tty_buffer_init
  - drivers/tty/tty_buffer.c:tty_buffer_free_all
```
```
In drivers/tty/tty_port.c (ffffffff816198a2)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_init
```
```
In drivers/tty/serial/serial_core.c (ffffffff81630c65)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_add_one_port
```
```
In drivers/char/virtio_console.c (ffffffff8164be3b)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:add_port
```
```
In drivers/char/hw_random/core.c (ffffffff8164e561)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In drivers/char/agp/backend.c (ffffffff8164f2a4)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/char/agp/backend.c:agp_alloc_bridge
  - drivers/char/agp/backend.c:agp_alloc_bridge
```
```
In drivers/iommu/iova.c (ffffffff81664c94)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/iommu/iova.c:fq_flush_timeout
```
```
In drivers/connector/cn_queue.c (ffffffff81678a8a)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/connector/cn_queue.c:cn_queue_alloc_dev
  - drivers/connector/cn_queue.c:cn_queue_add_callback
```
```
In drivers/base/core.c (ffffffff8167f04f)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In drivers/base/power/runtime.c (ffffffff816900a0)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_init
  - drivers/base/power/runtime.c:pm_runtime_init
```
```
In drivers/base/power/wakeup.c (ffffffff81695628)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:pm_wakeup_clear
```
```
In drivers/base/power/domain.c (ffffffff816979ea)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/base/power/domain.c:pm_genpd_init
```
```
In drivers/base/firmware_loader/main.c (ffffffff8169a9aa)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
```
```
In drivers/block/loop.c (ffffffff816abb86)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_add
  - drivers/block/loop.c:lo_rw_aio
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In drivers/mfd/mfd-core.c (ffffffff816c57ea)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_add_devices
```
```
In drivers/nvdimm/core.c (ffffffff816d1619)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff816d3f3c)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_create
```
```
In drivers/nvdimm/dimm.c (ffffffff816d4cbf)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In drivers/dma-buf/dma-fence.c (ffffffff816e3af9)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_init
```
```
In drivers/dma-buf/dma-fence-array.c (ffffffff816e4b6b)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_create
```
```
In drivers/dma-buf/sw_sync.c (ffffffff816e6baa)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open
```
```
In drivers/scsi/scsi.c (ffffffff816e9316)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_finish_command
  - drivers/scsi/scsi.c:scsi_finish_command
  - drivers/scsi/scsi.c:scsi_finish_command
```
```
In drivers/scsi/scsi_lib.c (ffffffff816f2970)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:__scsi_queue_insert
  - drivers/scsi/scsi_lib.c:__scsi_queue_insert
  - drivers/scsi/scsi_lib.c:__scsi_queue_insert
```
```
In drivers/scsi/scsi_scan.c (ffffffff816f3990)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
```
```
In drivers/scsi/sd.c (ffffffff817003f5)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
```
```
In drivers/scsi/sr.c (ffffffff8170463a)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_probe
```
```
In drivers/scsi/sg.c (ffffffff81707f07)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_open
```
```
In drivers/ata/libata-core.c (ffffffff8170c614)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_init
  - drivers/ata/libata-core.c:ata_host_alloc
```
```
In drivers/net/phy/sfp-bus.c (ffffffff8173afb8)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_bus_get
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81743bbc)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
```
```
In drivers/usb/core/usb.c (ffffffff817508c8)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/usb/core/usb.c:usb_alloc_dev
```
```
In drivers/usb/core/hub.c (ffffffff81758d53)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_probe
```
```
In drivers/usb/core/hcd.c (ffffffff8175ab20)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:__usb_create_hcd
```
```
In drivers/usb/core/urb.c (ffffffff8175d6cf)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In drivers/usb/core/driver.c (ffffffff8176210c)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_unbind_interface
```
```
In drivers/usb/core/config.c (ffffffff8176300b)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_configuration
```
```
In drivers/usb/core/file.c (ffffffff81764def)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In drivers/thermal/thermal_core.c (ffffffff817e7116)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff817ef5b2)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
```
```
In drivers/md/md.c (ffffffff818002ce)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_run
  - drivers/md/md.c:max_corrected_read_errors_store
  - drivers/md/md.c:md_rdev_init
  - drivers/md/md.c:md_rdev_init
  - drivers/md/md.c:md_rdev_init
  - drivers/md/md.c:errors_store
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:mddev_init
  - drivers/md/md.c:mddev_init
  - drivers/md/md.c:mddev_init
  - drivers/md/md.c:md_flush_request
```
```
In drivers/md/md-bitmap.c (ffffffff818051ba)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:bitmap_create
```
```
In drivers/md/dm.c (ffffffff81809896)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_create
  - drivers/md/dm.c:dm_create
  - drivers/md/dm.c:dm_create
  - drivers/md/dm.c:dm_create
  - drivers/md/dm.c:dm_create
  - drivers/md/dm.c:dm_create
  - drivers/md/dm.c:dec_pending
  - drivers/md/dm.c:dm_get_table_device
  - drivers/md/dm.c:alloc_io
  - drivers/md/dm.c:alloc_io
```
```
In drivers/md/dm-table.c (ffffffff8180b5cd)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_get_device
```
```
In drivers/md/dm-stripe.c (ffffffff8180edf1)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:stripe_ctr
```
```
In drivers/md/dm-io.c (ffffffff818124a7)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/md/dm-io.c:dm_io
  - drivers/md/dm-io.c:sync_io
```
```
In drivers/md/dm-kcopyd.c (ffffffff81813409)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
  - drivers/md/dm-kcopyd.c:dm_kcopyd_copy
```
```
In drivers/md/dm-stats.c (ffffffff81814742)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In drivers/opp/core.c (ffffffff8181e48f)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/opp/core.c:_opp_add
  - drivers/opp/core.c:dev_pm_opp_get_opp_table
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff818261b3)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_stop
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
  - drivers/cpufreq/cpufreq_governor.c:dbs_update_util_handler
  - drivers/cpufreq/cpufreq_governor.c:dbs_work_handler
```
```
In drivers/mmc/core/sdio_irq.c (ffffffff81840c5c)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_irq.c:sdio_release_irq
  - drivers/mmc/core/sdio_irq.c:sdio_claim_irq
```
```
In net/core/sock.c (ffffffff81874fe2)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_alloc
```
```
In net/core/skbuff.c (ffffffff8187fed2)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:sock_zerocopy_realloc
  - net/core/skbuff.c:sock_zerocopy_alloc
  - net/core/skbuff.c:__skb_clone
  - net/core/skbuff.c:__build_skb
  - net/core/skbuff.c:__build_skb
  - net/core/skbuff.c:__alloc_skb
  - net/core/skbuff.c:__alloc_skb
  - net/core/skbuff.c:__alloc_skb
```
```
In net/core/net_namespace.c (ffffffff81887e59)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/core/net_namespace.c:copy_net_ns
  - net/core/net_namespace.c:setup_net
  - net/core/net_namespace.c:setup_net
```
```
In net/core/dev.c (ffffffff8189070a)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/core/dev.c:__dev_kfree_skb_irq
```
```
In net/core/dst.c (ffffffff8189f6f7)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/core/dst.c:__metadata_dst_init
  - net/core/dst.c:dst_cow_metrics_generic
```
```
In net/core/neighbour.c (ffffffff818a518f)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:__neigh_create
```
```
In net/core/filter.c (ffffffff818b827f)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/core/filter.c:__sk_attach_prog
```
```
In net/core/netpoll.c (ffffffff818bed54)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/core/netpoll.c:__netpoll_setup
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:zap_completion_queue
```
```
In net/core/fib_rules.c (ffffffff818c20df)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_default_rule_add
```
```
In net/sched/sch_generic.c (ffffffff818cd27f)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_alloc
```
```
In net/ipv4/route.c (ffffffff818e2595)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_genid_init
  - net/ipv4/route.c:rt_genid_init
  - net/ipv4/route.c:rt_genid_init
```
```
In net/ipv4/inetpeer.c (ffffffff818e7b46)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff818f32e3)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
```
```
In net/ipv4/inet_connection_sock.c (ffffffff818f3e99)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_hash_add
```
```
In net/ipv4/tcp.c (ffffffff818f5cdc)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv4/tcp.c:skb_entail
```
```
In net/ipv4/tcp_input.c (ffffffff818fca95)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/tcp_output.c (ffffffff81909e29)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8190f247)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81916a47)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/devinet.c (ffffffff819282e8)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_init
```
```
In net/ipv4/igmp.c (ffffffff8192e5fb)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv4/igmp.c:__ip_mc_inc_group
```
```
In net/ipv4/fib_semantics.c (ffffffff81933cfc)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_rebalance
```
```
In net/ipv4/inet_fragment.c (ffffffff8193944f)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff8193cbff)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:proc_tfo_blackhole_detect_timeout
```
```
In net/ipv4/ipmr.c (ffffffff81942853)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv4/syncookies.c (ffffffff81945200)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:tcp_get_cookie_sock
```
```
In net/ipv4/cipso_ipv4.c (ffffffff8194724d)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff8194d47e)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
```
```
In net/xfrm/xfrm_state.c (ffffffff81950e9a)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
```
```
In net/xfrm/xfrm_input.c (ffffffff819558d6)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:secpath_dup
```
```
In net/unix/af_unix.c (ffffffff8195a71b)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
```
```
In net/ipv6/af_inet6.c (ffffffff8195e80a)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In net/ipv6/anycast.c (ffffffff8195f3d9)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
```
```
In net/ipv6/addrconf.c (ffffffff81968b5e)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/route.c (ffffffff819701a4)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_upper_bound_set
```
```
In net/ipv6/ip6_fib.c (ffffffff8197b424)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_metric_set
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff8197d9f6)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In net/ipv6/mcast.c (ffffffff8198e28f)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
```
```
In net/ipv6/exthdrs.c (ffffffff81997869)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_dup_options
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff8199a109)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:fl_create
```
```
In net/ipv6/ip6mr.c (ffffffff8199f047)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/ipv6/calipso.c (ffffffff819a658b)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_doi_add
```
```
In net/packet/af_packet.c (ffffffff819b3cf8)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
```
```
In net/xdp/xdp_umem.c (ffffffff819cd0f5)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_create
```
```
In lib/dump_stack.c (ffffffff819ce3a5)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - lib/dump_stack.c:dump_stack
```
```
In lib/klist.c (ffffffff819cfe5d)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - lib/klist.c:klist_node_init
```
```
In lib/kobject.c (ffffffff819d1448)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - lib/kobject.c:kset_register
  - lib/kobject.c:kobject_init
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
In arch/x86/kernel/tboot.c (ffffffff828941dd)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81048c6c)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:fake_panic_set
  - arch/x86/kernel/cpu/mce/core.c:fake_panic_set
  - arch/x86/kernel/cpu/mce/core.c:fake_panic_set
  - arch/x86/kernel/cpu/mce/core.c:fake_panic_set
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff8104e9ca)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff8104f4c4)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff81052e4d)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In arch/x86/kernel/reboot.c (ffffffff8105f1e5)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff81061bb9)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_target
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
```
```
In arch/x86/kernel/kgdb.c (ffffffff8106fec2)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In arch/x86/mm/init_64.c (ffffffff81a23956)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pagetable
```
```
In kernel/fork.c (ffffffff81092afc)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
  - kernel/fork.c:mm_init
  - kernel/fork.c:mm_init
```
```
In kernel/softirq.c (ffffffff8109ca87)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/softirq.c:tasklet_hrtimer_init
```
```
In kernel/user.c (ffffffff810a416e)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/user.c:alloc_uid
```
```
In kernel/workqueue.c (ffffffff810b8834)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_offline_cpu
  - kernel/workqueue.c:__alloc_workqueue_key
  - kernel/workqueue.c:flush_workqueue_prep_pwqs
```
```
In kernel/pid.c (ffffffff810b9e5b)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/pid.c:alloc_pid
```
```
In kernel/nsproxy.c (ffffffff810bd41e)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/nsproxy.c:create_new_namespaces
```
```
In kernel/cred.c (ffffffff810bec8e)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:cred_alloc_blank
```
```
In kernel/smpboot.c (ffffffff810c0851)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/smpboot.c:cpu_wait_death
  - kernel/smpboot.c:cpu_check_up_prepare
```
```
In kernel/groups.c (ffffffff810c12d8)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/groups.c:groups_alloc
```
```
In kernel/sched/core.c (ffffffff828ac74f)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init
```
```
In kernel/sched/fair.c (ffffffff810d6e5e)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_fault
```
```
In kernel/sched/cpupri.c (ffffffff810e3cc4)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_init
```
```
In kernel/sched/topology.c (ffffffff810e4f30)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:init_defrootdomain
```
```
In kernel/sched/autogroup.c (ffffffff810e7b4a)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
  - kernel/sched/autogroup.c:autogroup_init
```
```
In kernel/locking/mutex.c (ffffffff810efc94)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/locking/mutex.c:__mutex_init
```
```
In kernel/locking/rwsem-xadd.c (ffffffff810f1afc)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/locking/rwsem-xadd.c:__init_rwsem
```
```
In kernel/power/swap.c (ffffffff810f99ba)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:save_image
```
```
In kernel/irq/manage.c (ffffffff81101f6d)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_notifier
```
```
In kernel/rcu/srcutree.c (ffffffff8110f1d7)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
```
```
In kernel/rcu/tree.c (ffffffff81110b97)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In kernel/time/posix-clock.c (ffffffff8112e045)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/time/posix-clock.c:posix_clock_register
```
```
In kernel/futex.c (ffffffff828b0155)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/futex.c:futex_init
```
```
In kernel/module.c (ffffffff8113e26a)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/module.c:load_module
```
```
In kernel/kexec_core.c (ffffffff81143420)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_free_reserved_phys_range
  - kernel/kexec_core.c:crash_kexec
```
```
In kernel/cgroup/cgroup.c (ffffffff81148b60)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:find_css_set
```
```
In kernel/cgroup/namespace.c (ffffffff8114ff95)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
```
```
In kernel/utsname.c (ffffffff811590c3)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/utsname.c:copy_utsname
```
```
In kernel/user_namespace.c (ffffffff8115a428)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In kernel/pid_namespace.c (ffffffff8115afb8)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In kernel/stop_machine.c (ffffffff8115bed4)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:stop_machine_cpuslocked
  - kernel/stop_machine.c:stop_two_cpus
  - kernel/stop_machine.c:multi_cpu_stop
  - kernel/stop_machine.c:cpu_stop_init_done
```
```
In kernel/audit_watch.c (ffffffff811657f8)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_init_watch
```
```
In kernel/audit_tree.c (ffffffff81167c1c)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_make_tree
```
```
In kernel/debug/debug_core.c (ffffffff8116b50e)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_tasklet_bpt
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff811705cf)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In kernel/hung_task.c (ffffffff81176955)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/hung_task.c:reset_hung_task_detector
```
```
In kernel/seccomp.c (ffffffff811793a2)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In kernel/relay.c (ffffffff8117a05c)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/relay.c:__relay_reset
```
```
In kernel/trace/tracing_map.c (ffffffff81197d0d)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_create
  - kernel/trace/tracing_map.c:tracing_map_clear
```
```
In kernel/trace/blktrace.c (ffffffff8119dc92)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:do_blk_trace_setup
```
```
In kernel/trace/fgraph.c (ffffffff811a09ca)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/trace/fgraph.c:register_ftrace_graph
  - kernel/trace/fgraph.c:register_ftrace_graph
  - kernel/trace/fgraph.c:ftrace_graph_init_task
  - kernel/trace/fgraph.c:ftrace_graph_init_task
```
```
In kernel/trace/trace_events.c (ffffffff811a0dac)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_create_new_event
  - kernel/trace/trace_events.c:trace_create_new_event
```
```
In kernel/bpf/syscall.c (ffffffff811c41e8)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:bpf_prog_load
```
```
In kernel/bpf/btf.c (ffffffff811dcb7a)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_new_fd
```
```
In kernel/events/core.c (ffffffff811e874f)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:alloc_perf_context
```
```
In kernel/events/ring_buffer.c (ffffffff811f36de)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc
  - kernel/events/ring_buffer.c:rb_alloc_aux
  - kernel/events/ring_buffer.c:perf_aux_output_skip
  - kernel/events/ring_buffer.c:perf_aux_output_end
  - kernel/events/ring_buffer.c:perf_aux_output_begin
  - kernel/events/ring_buffer.c:perf_output_put_handle
```
```
In kernel/events/uprobes.c (ffffffff811f6907)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__create_xol_area
```
```
In kernel/padata.c (ffffffff811f8026)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_alloc_pd
```
```
In kernel/jump_label.c (ffffffff811f929c)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/jump_label.c:static_key_enable_cpuslocked
  - kernel/jump_label.c:static_key_slow_inc_cpuslocked
```
```
In mm/filemap.c (ffffffff81202af6)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/page_alloc.c (ffffffff812093d3)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:make_alloc_exact
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:check_new_page_bad
  - mm/page_alloc.c:init_cma_reserved_pageblock
  - mm/page_alloc.c:init_cma_reserved_pageblock
  - mm/page_alloc.c:memblock_free_pages
  - mm/page_alloc.c:memblock_free_pages
  - mm/page_alloc.c:memblock_free_pages
  - mm/page_alloc.c:bad_page
```
```
In mm/backing-dev.c (ffffffff8122b980)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_alloc_node
  - mm/backing-dev.c:wb_congested_get_create
  - mm/backing-dev.c:default_bdi_init
```
```
In mm/rmap.c (ffffffff81254b24)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - mm/rmap.c:hugepage_add_new_anon_rmap
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:anon_vma_ctor
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:__anon_vma_prepare
```
```
In mm/vmalloc.c (ffffffff812572fe)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - mm/vmalloc.c:set_iounmap_nonlazy
```
```
In mm/swap_state.c (ffffffff8125c8be)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - mm/swap_state.c:init_swap_address_space
  - mm/swap_state.c:swap_cluster_readahead
```
```
In mm/frontswap.c (ffffffff8126355f)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_invalidate_area
```
```
In mm/zswap.c (ffffffff81263c6e)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - mm/zswap.c:zswap_pool_create
```
```
In mm/hugetlb.c (ffffffff81266522)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:update_and_free_page
  - mm/hugetlb.c:update_and_free_page
  - mm/hugetlb.c:update_and_free_page
  - mm/hugetlb.c:dequeue_huge_page_nodemask
  - mm/hugetlb.c:resv_map_alloc
```
```
In mm/mempolicy.c (ffffffff81271977)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:__mpol_dup
```
```
In mm/memory_hotplug.c (ffffffff8127ffbc)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - mm/memory_hotplug.c:generic_online_page
  - mm/memory_hotplug.c:put_page_bootmem
```
```
In mm/huge_memory.c (ffffffff81288fdb)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In mm/memcontrol.c (ffffffff81294110)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_select_victim_node
```
```
In mm/zpool.c (ffffffff812a0d59)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - mm/zpool.c:zpool_register_driver
```
```
In mm/zsmalloc.c (ffffffff812a1d3f)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - mm/zsmalloc.c:reset_page
```
```
In fs/super.c (ffffffff812b2295)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/super.c:sget_userns
```
```
In fs/exec.c (ffffffff812b7582)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In fs/dcache.c (ffffffff812cc4f7)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/dcache.c:__d_alloc
```
```
In fs/inode.c (ffffffff812cd3af)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/inode.c:inode_init_always
  - fs/inode.c:inode_init_always
  - fs/inode.c:inode_init_always
  - fs/inode.c:inode_init_always
```
```
In fs/file.c (ffffffff812d1550)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/file.c:dup_fd
```
```
In fs/namespace.c (ffffffff812d2820)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In fs/block_dev.c (ffffffff812f1d5d)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_direct_IO
```
```
In fs/notify/group.c (ffffffff812f9ba4)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_alloc_group
  - fs/notify/group.c:fsnotify_alloc_group
  - fs/notify/group.c:fsnotify_alloc_group
```
```
In fs/notify/mark.c (ffffffff812f9f72)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_init_mark
```
```
In fs/eventfd.c (ffffffff81303841)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/eventfd.c:do_eventfd
```
```
In fs/userfaultfd.c (ffffffff81304233)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/userfaultfd.c:__ia32_sys_userfaultfd
  - fs/userfaultfd.c:__x64_sys_userfaultfd
  - fs/userfaultfd.c:dup_userfaultfd
```
```
In fs/aio.c (ffffffff8130952d)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:io_submit_one
  - fs/aio.c:__ia32_sys_io_destroy
  - fs/aio.c:__x64_sys_io_destroy
  - fs/aio.c:exit_aio
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
```
```
In fs/crypto/keyinfo.c (ffffffff8131167d)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In fs/mbcache.c (ffffffff8131ff2b)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/posix_acl.c (ffffffff81320567)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/posix_acl.c:posix_acl_clone
  - fs/posix_acl.c:posix_acl_alloc
```
```
In fs/coredump.c (ffffffff81321e48)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/iomap.c (ffffffff813267e7)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/iomap.c:iomap_dio_rw
```
```
In fs/quota/dquot.c (ffffffff81328f4f)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/quota/dquot.c:dqget
```
```
In fs/proc/generic.c (ffffffff813374e4)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/proc/generic.c:__proc_create
```
```
In fs/kernfs/dir.c (ffffffff81343d40)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/kernfs/dir.c:__kernfs_new_node
  - fs/kernfs/dir.c:__kernfs_new_node
```
```
In fs/kernfs/file.c (ffffffff8134591b)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_fop_open
  - fs/kernfs/file.c:kernfs_fop_open
```
```
In fs/configfs/dir.c (ffffffff8134987f)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_new_dirent
```
```
In fs/configfs/item.c (ffffffff8134b8c8)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/configfs/item.c:config_group_init_type_name
  - fs/configfs/item.c:config_item_init_type_name
```
```
In fs/ext4/mballoc.c (ffffffff8137e11d)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
```
```
In fs/ext4/page-io.c (ffffffff8138870f)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_init_io_end
```
```
In fs/ext4/super.c (ffffffff8139698e)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_alloc_inode
```
```
In fs/jbd2/transaction.c (ffffffff813ab9bb)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
```
```
In fs/jbd2/journal.c (ffffffff813b42b9)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_init_common
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/ecryptfs/main.c (ffffffff813cf43a)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_get_lower_file
```
```
In fs/ecryptfs/super.c (ffffffff813cf65d)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/ecryptfs/super.c:ecryptfs_alloc_inode
```
```
In fs/ecryptfs/miscdev.c (ffffffff828cc703)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/ecryptfs/miscdev.c:ecryptfs_init_ecryptfs_miscdev
```
```
In fs/fuse/dev.c (ffffffff813d96a3)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/fuse/dev.c:__fuse_request_alloc
```
```
In fs/fuse/file.c (ffffffff813e4d75)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_file_alloc
```
```
In fs/fuse/inode.c (ffffffff813e6c01)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_conn_init
  - fs/fuse/inode.c:fuse_conn_init
  - fs/fuse/inode.c:fuse_conn_init
```
```
In fs/debugfs/file.c (ffffffff813ebf65)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_atomic_t_set
  - fs/debugfs/file.c:debugfs_file_get
```
```
In ipc/util.c (ffffffff813f0895)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In ipc/msg.c (ffffffff828ccc01)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - ipc/msg.c:msg_init
  - ipc/msg.c:msg_init
```
```
In ipc/sem.c (ffffffff813f76de)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - ipc/sem.c:copy_semundo
  - ipc/sem.c:do_semtimedop
```
```
In ipc/namespace.c (ffffffff813fdf81)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - ipc/namespace.c:copy_ipcs
```
```
In security/keys/key.c (ffffffff813ff5a2)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_user_lookup
  - security/keys/key.c:key_user_lookup
  - security/keys/key.c:key_user_lookup
```
```
In security/selinux/avc.c (ffffffff814139ab)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - security/selinux/avc.c:selinux_avc_init
  - security/selinux/avc.c:selinux_avc_init
```
```
In security/selinux/ss/sidtab.c (ffffffff81424bb6)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_convert
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_init
  - security/selinux/ss/sidtab.c:sidtab_init
```
```
In security/selinux/ss/services.c (ffffffff81430d90)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
```
```
In security/tomoyo/condition.c (ffffffff81443666)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
```
```
In security/tomoyo/gc.c (ffffffff81447cbd)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In security/tomoyo/memory.c (ffffffff814486f8)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_name
  - security/tomoyo/memory.c:tomoyo_get_group
```
```
In security/apparmor/apparmorfs.c (ffffffff8144f931)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_write_access
```
```
In security/apparmor/lib.c (ffffffff8145235a)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - security/apparmor/lib.c:aa_str_alloc
```
```
In security/apparmor/match.c (ffffffff81452d51)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
```
```
In security/apparmor/policy_unpack.c (ffffffff8145c8b2)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:aa_loaddata_alloc
```
```
In security/apparmor/policy_ns.c (ffffffff81462b9b)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:alloc_ns
```
```
In security/apparmor/label.c (ffffffff81463ebc)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_alloc
  - security/apparmor/label.c:aa_alloc_proxy
```
```
In crypto/api.c (ffffffff81475ba4)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - crypto/api.c:crypto_alg_mod_lookup
```
```
In crypto/algapi.c (ffffffff81476caa)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - crypto/algapi.c:__crypto_register_alg
  - crypto/algapi.c:crypto_check_alg
```
```
In block/bio.c (ffffffff814983ee)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - block/bio.c:bio_reset
  - block/bio.c:bio_init
  - block/bio.c:bio_init
```
```
In block/blk-ioc.c (ffffffff814a321b)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - block/blk-ioc.c:create_task_io_context
  - block/blk-ioc.c:create_task_io_context
```
```
In block/blk-mq.c (ffffffff814ab149)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/bsg.c (ffffffff814bffaa)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - block/bsg.c:bsg_open
```
```
In block/bsg-lib.c (ffffffff814c09b9)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_queue_rq
```
```
In block/blk-cgroup.c (ffffffff814c14d2)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_css_alloc
```
```
In block/blk-wbt.c (ffffffff814cdd19)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_init
```
```
In lib/rhashtable.c (ffffffff814e12f0)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_init
```
```
In lib/cpu_rmap.c (ffffffff81506d33)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - lib/cpu_rmap.c:alloc_cpu_rmap
```
```
In lib/sbitmap.c (ffffffff8150ce04)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In drivers/pinctrl/core.c (ffffffff81511730)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:create_pinctrl
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff81558461)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
```
```
In drivers/rapidio/rio.c (ffffffff815621ed)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_register_mport
  - drivers/rapidio/rio.c:rio_mport_initialize
  - drivers/rapidio/rio.c:rio_del_device
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff8156b51d)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:register_framebuffer
```
```
In drivers/acpi/ec.c (ffffffff81591b65)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_add_query_handler
```
```
In drivers/acpi/apei/ghes.c (ffffffff815f0202)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
```
```
In drivers/clk/clk.c (ffffffff815fe2fc)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_register
```
```
In drivers/dma/dmaengine.c (ffffffff8160292f)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaengine_get_unmap_data
  - drivers/dma/dmaengine.c:dma_async_device_register
```
```
In drivers/xen/balloon.c (ffffffff8160ecb8)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_process
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff8161924d)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_open
```
```
In drivers/reset/core.c (ffffffff8162b338)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/reset/core.c:__reset_control_get_from_lookup
```
```
In drivers/tty/tty_io.c (ffffffff8162f6cb)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:alloc_tty_struct
```
```
In drivers/tty/tty_buffer.c (ffffffff81636809)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_init
  - drivers/tty/tty_buffer.c:tty_buffer_init
```
```
In drivers/tty/tty_port.c (ffffffff81636b12)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_init
```
```
In drivers/tty/serial/serial_core.c (ffffffff8164ee15)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_add_one_port
```
```
In drivers/char/virtio_console.c (ffffffff81669fab)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:add_port
```
```
In drivers/char/hw_random/core.c (ffffffff8166c7f1)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In drivers/char/agp/backend.c (ffffffff8166cdc4)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/char/agp/backend.c:agp_alloc_bridge
  - drivers/char/agp/backend.c:agp_alloc_bridge
```
```
In drivers/iommu/iova.c (ffffffff81683294)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/iommu/iova.c:fq_flush_timeout
```
```
In drivers/connector/cn_queue.c (ffffffff81697b7a)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/connector/cn_queue.c:cn_queue_alloc_dev
  - drivers/connector/cn_queue.c:cn_queue_add_callback
```
```
In drivers/base/core.c (ffffffff8169f48f)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In drivers/base/power/runtime.c (ffffffff816b06f9)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_init
  - drivers/base/power/runtime.c:pm_runtime_init
```
```
In drivers/base/power/wakeup.c (ffffffff816b5c98)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:pm_wakeup_clear
```
```
In drivers/base/power/domain.c (ffffffff816b6eca)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/base/power/domain.c:pm_genpd_init
```
```
In drivers/base/firmware_loader/main.c (ffffffff816bb1a0)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
```
```
In drivers/block/loop.c (ffffffff816cc934)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_add
  - drivers/block/loop.c:lo_rw_aio
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In drivers/mfd/mfd-core.c (ffffffff816e6bd4)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_add_devices
```
```
In drivers/nvdimm/core.c (ffffffff816f2ca9)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff816f58ea)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:__nvdimm_create
```
```
In drivers/nvdimm/dimm.c (ffffffff816f6a07)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In drivers/dma-buf/dma-fence.c (ffffffff81706d93)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_init
```
```
In drivers/dma-buf/dma-fence-array.c (ffffffff81707edb)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_create
```
```
In drivers/dma-buf/sw_sync.c (ffffffff81709dba)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open
```
```
In drivers/scsi/scsi.c (ffffffff8170ce16)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_finish_command
  - drivers/scsi/scsi.c:scsi_finish_command
  - drivers/scsi/scsi.c:scsi_finish_command
```
```
In drivers/scsi/scsi_lib.c (ffffffff817155cc)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:__scsi_queue_insert
  - drivers/scsi/scsi_lib.c:__scsi_queue_insert
  - drivers/scsi/scsi_lib.c:__scsi_queue_insert
```
```
In drivers/scsi/scsi_scan.c (ffffffff8171752c)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
```
```
In drivers/scsi/sd.c (ffffffff81721bad)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
```
```
In drivers/scsi/sr.c (ffffffff81726aaa)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_probe
```
```
In drivers/scsi/sg.c (ffffffff81729017)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_open
```
```
In drivers/ata/libata-core.c (ffffffff8172ea94)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_init
  - drivers/ata/libata-core.c:ata_host_alloc
```
```
In drivers/net/phy/sfp-bus.c (ffffffff8175e598)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_bus_get
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff8176686c)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
```
```
In drivers/usb/core/usb.c (ffffffff81774d0e)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/usb/core/usb.c:usb_alloc_dev
```
```
In drivers/usb/core/hub.c (ffffffff8177d2c3)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_probe
```
```
In drivers/usb/core/hcd.c (ffffffff8177f050)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:__usb_create_hcd
```
```
In drivers/usb/core/urb.c (ffffffff81781d0f)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In drivers/usb/core/driver.c (ffffffff8178671c)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_unbind_interface
```
```
In drivers/usb/core/config.c (ffffffff8178764b)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_configuration
```
```
In drivers/usb/core/file.c (ffffffff8178946f)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In drivers/media/cec/cec-notifier.c (ffffffff81808d47)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In drivers/thermal/thermal_core.c (ffffffff81812237)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff8181b47f)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
```
```
In drivers/md/md.c (ffffffff8182c4d0)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_run
  - drivers/md/md.c:max_corrected_read_errors_store
  - drivers/md/md.c:md_rdev_init
  - drivers/md/md.c:md_rdev_init
  - drivers/md/md.c:md_rdev_init
  - drivers/md/md.c:errors_store
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:mddev_init
  - drivers/md/md.c:mddev_init
  - drivers/md/md.c:mddev_init
  - drivers/md/md.c:md_flush_request
```
```
In drivers/md/md-bitmap.c (ffffffff818313ba)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
```
```
In drivers/md/dm.c (ffffffff81835996)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_create
  - drivers/md/dm.c:dm_create
  - drivers/md/dm.c:dm_create
  - drivers/md/dm.c:dm_create
  - drivers/md/dm.c:dm_get_table_device
  - drivers/md/dm.c:alloc_io
```
```
In drivers/md/dm-table.c (ffffffff818375cd)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_get_device
```
```
In drivers/md/dm-stripe.c (ffffffff8183add1)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:stripe_ctr
```
```
In drivers/md/dm-io.c (ffffffff8183e427)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/md/dm-io.c:dm_io
  - drivers/md/dm-io.c:sync_io
```
```
In drivers/md/dm-kcopyd.c (ffffffff8183f3ee)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
  - drivers/md/dm-kcopyd.c:dm_kcopyd_copy
```
```
In drivers/md/dm-stats.c (ffffffff81840752)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In drivers/opp/core.c (ffffffff8184a28d)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/opp/core.c:_opp_add
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff818522a3)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_stop
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
  - drivers/cpufreq/cpufreq_governor.c:dbs_update_util_handler
  - drivers/cpufreq/cpufreq_governor.c:dbs_work_handler
```
```
In drivers/mmc/core/sdio_irq.c (ffffffff8186cc0c)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_irq.c:sdio_release_irq
  - drivers/mmc/core/sdio_irq.c:sdio_claim_irq
```
```
In drivers/firmware/efi/efi.c (ffffffff81a234b5)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
```
```
In drivers/devfreq/devfreq.c (ffffffff8187d1a5)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In drivers/nvmem/core.c (ffffffff818870e2)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In net/core/sock.c (ffffffff818958a4)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_alloc
```
```
In net/core/skbuff.c (ffffffff8189d240)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_ext_add
  - net/core/skbuff.c:skb_ext_add
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:sock_zerocopy_realloc
  - net/core/skbuff.c:sock_zerocopy_alloc
  - net/core/skbuff.c:__skb_clone
  - net/core/skbuff.c:__build_skb
  - net/core/skbuff.c:__build_skb
  - net/core/skbuff.c:__alloc_skb
  - net/core/skbuff.c:__alloc_skb
  - net/core/skbuff.c:__alloc_skb
```
```
In net/core/net_namespace.c (ffffffff818a8969)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/core/net_namespace.c:copy_net_ns
  - net/core/net_namespace.c:setup_net
  - net/core/net_namespace.c:setup_net
```
```
In net/core/dev.c (ffffffff818b105a)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/core/dev.c:__dev_kfree_skb_irq
```
```
In net/core/dst.c (ffffffff818c20b7)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/core/dst.c:__metadata_dst_init
  - net/core/dst.c:dst_cow_metrics_generic
```
```
In net/core/neighbour.c (ffffffff818c4994)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:___neigh_create
```
```
In net/core/filter.c (ffffffff818decdf)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/core/filter.c:__sk_attach_prog
```
```
In net/core/skmsg.c (ffffffff818e6325)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_init
```
```
In net/core/netpoll.c (ffffffff818e7b4f)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/core/netpoll.c:__netpoll_setup
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:zap_completion_queue
```
```
In net/core/fib_rules.c (ffffffff818eaf9f)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_default_rule_add
```
```
In net/sched/sch_generic.c (ffffffff818f85df)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_alloc
```
```
In net/sched/cls_api.c (ffffffff818ff5fc)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_get_ext
```
```
In net/sched/act_api.c (ffffffff81902453)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_idr_create
  - net/sched/act_api.c:tcf_idr_create
```
```
In net/ipv4/route.c (ffffffff8190f435)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_genid_init
  - net/ipv4/route.c:rt_genid_init
  - net/ipv4/route.c:rt_genid_init
```
```
In net/ipv4/inetpeer.c (ffffffff819149f6)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81920e03)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819219b9)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_hash_add
```
```
In net/ipv4/tcp.c (ffffffff81923939)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv4/tcp.c:skb_entail
```
```
In net/ipv4/tcp_input.c (ffffffff8192ac07)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/tcp_output.c (ffffffff819380da)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8193d676)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In net/ipv4/tcp_fastopen.c (ffffffff819451f7)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/devinet.c (ffffffff81957548)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_init
```
```
In net/ipv4/igmp.c (ffffffff8195db2f)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv4/igmp.c:__ip_mc_inc_group
```
```
In net/ipv4/fib_semantics.c (ffffffff81963c32)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_rebalance
```
```
In net/ipv4/inet_fragment.c (ffffffff81969042)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In net/ipv4/metrics.c (ffffffff8196c716)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff8196ca3f)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:proc_tfo_blackhole_detect_timeout
```
```
In net/ipv4/ipmr.c (ffffffff81972923)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv4/syncookies.c (ffffffff819754f0)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:tcp_get_cookie_sock
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81978e1d)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff8197d5ed)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
```
```
In net/xfrm/xfrm_state.c (ffffffff819843ea)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
```
```
In net/unix/af_unix.c (ffffffff8198f40b)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
```
```
In net/ipv6/af_inet6.c (ffffffff81993375)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In net/ipv6/anycast.c (ffffffff81993fcc)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
```
```
In net/ipv6/addrconf.c (ffffffff8199e481)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/route.c (ffffffff819a5dd4)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_upper_bound_set
```
```
In net/ipv6/ip6_fib.c (ffffffff819b1104)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_metric_set
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff819b4d4c)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In net/ipv6/mcast.c (ffffffff819c4b82)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
```
```
In net/ipv6/exthdrs.c (ffffffff819ce139)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_dup_options
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff819d069b)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:fl_create
```
```
In net/ipv6/ip6mr.c (ffffffff819d5b67)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/ipv6/calipso.c (ffffffff819dd0eb)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_doi_add
```
```
In net/packet/af_packet.c (ffffffff819ead65)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
```
```
In net/xdp/xdp_umem.c (ffffffff81a06345)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_create
```
```
In lib/dump_stack.c (ffffffff81a0785e)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - lib/dump_stack.c:dump_stack
```
```
In lib/klist.c (ffffffff81a0949d)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - lib/klist.c:klist_node_init
```
```
In lib/kobject.c (ffffffff81a0aa08)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - lib/kobject.c:kset_register
  - lib/kobject.c:kobject_init
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
In arch/x86/kernel/tboot.c (ffffffff828ab99c)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104bd1c)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:fake_panic_set
  - arch/x86/kernel/cpu/mce/core.c:fake_panic_set
  - arch/x86/kernel/cpu/mce/core.c:fake_panic_set
  - arch/x86/kernel/cpu/mce/core.c:fake_panic_set
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81051a8e)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff810525e7)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff81055ffd)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In arch/x86/kernel/reboot.c (ffffffff810625e6)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff81065216)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_target
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
```
```
In arch/x86/kernel/kgdb.c (ffffffff81073fbf)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In arch/x86/mm/init_64.c (ffffffff81a93c82)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pagetable
```
```
In kernel/fork.c (ffffffff81098426)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:mm_init
  - kernel/fork.c:mm_init
  - kernel/fork.c:mm_init
```
```
In kernel/softirq.c (ffffffff810a0d35)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/softirq.c:tasklet_init
```
```
In kernel/user.c (ffffffff810a8e4e)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/user.c:alloc_uid
```
```
In kernel/workqueue.c (ffffffff810be340)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_offline_cpu
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:flush_workqueue_prep_pwqs
```
```
In kernel/pid.c (ffffffff810bfd49)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/pid.c:alloc_pid
```
```
In kernel/nsproxy.c (ffffffff810c3451)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/nsproxy.c:create_new_namespaces
```
```
In kernel/cred.c (ffffffff810c4d03)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:cred_alloc_blank
```
```
In kernel/smpboot.c (ffffffff810c693c)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/smpboot.c:cpu_wait_death
  - kernel/smpboot.c:cpu_check_up_prepare
```
```
In kernel/groups.c (ffffffff810c73c8)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/groups.c:groups_alloc
```
```
In kernel/sched/core.c (ffffffff828c4fea)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init
```
```
In kernel/sched/fair.c (ffffffff810deb3a)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_fault
```
```
In kernel/sched/cpupri.c (ffffffff810ea8b7)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_init
```
```
In kernel/sched/topology.c (ffffffff810ebedb)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:init_defrootdomain
```
```
In kernel/sched/autogroup.c (ffffffff810eeabf)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
  - kernel/sched/autogroup.c:autogroup_init
```
```
In kernel/sched/psi.c (ffffffff810f61a7)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_trigger_destroy
  - kernel/sched/psi.c:psi_poll_work
  - kernel/sched/psi.c:group_init
```
```
In kernel/locking/mutex.c (ffffffff810f76f4)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/locking/mutex.c:__mutex_init
```
```
In kernel/locking/rwsem.c (ffffffff810f7abc)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:__init_rwsem
```
```
In kernel/power/swap.c (ffffffff811020fe)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:save_image
```
```
In kernel/irq/manage.c (ffffffff8110b219)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_notifier
```
```
In kernel/rcu/srcutree.c (ffffffff81118f42)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
```
```
In kernel/rcu/tree.c (ffffffff8111a5f0)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In kernel/time/posix-clock.c (ffffffff81138a55)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/time/posix-clock.c:posix_clock_register
```
```
In kernel/futex.c (ffffffff828c8ccd)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/futex.c:futex_init
```
```
In kernel/module.c (ffffffff81149d5a)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/module.c:load_module
```
```
In kernel/kexec_core.c (ffffffff8114e762)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_free_reserved_phys_range
  - kernel/kexec_core.c:crash_kexec
```
```
In kernel/cgroup/cgroup.c (ffffffff811541b0)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:init_cgroup_root
  - kernel/cgroup/cgroup.c:find_css_set
```
```
In kernel/cgroup/namespace.c (ffffffff8115be91)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
```
```
In kernel/utsname.c (ffffffff811657f8)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/utsname.c:copy_utsname
```
```
In kernel/user_namespace.c (ffffffff81166b05)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In kernel/pid_namespace.c (ffffffff81167668)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In kernel/stop_machine.c (ffffffff8116858a)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:stop_machine_cpuslocked
  - kernel/stop_machine.c:stop_two_cpus
  - kernel/stop_machine.c:multi_cpu_stop
  - kernel/stop_machine.c:cpu_stop_init_done
```
```
In kernel/audit_watch.c (ffffffff81172368)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_init_watch
```
```
In kernel/audit_tree.c (ffffffff81174857)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_make_tree
```
```
In kernel/debug/debug_core.c (ffffffff811782ce)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_tasklet_bpt
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff8117d7df)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In kernel/hung_task.c (ffffffff81183745)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/hung_task.c:reset_hung_task_detector
```
```
In kernel/seccomp.c (ffffffff81186232)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
```
```
In kernel/relay.c (ffffffff81186e9d)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/relay.c:__relay_reset
```
```
In kernel/trace/trace.c (ffffffff8119a541)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
```
```
In kernel/trace/tracing_map.c (ffffffff811a58ee)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_create
  - kernel/trace/tracing_map.c:tracing_map_clear
```
```
In kernel/trace/blktrace.c (ffffffff811ab987)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:do_blk_trace_setup
```
```
In kernel/trace/fgraph.c (ffffffff811ae7aa)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/trace/fgraph.c:start_graph_tracing
  - kernel/trace/fgraph.c:start_graph_tracing
  - kernel/trace/fgraph.c:ftrace_graph_init_task
  - kernel/trace/fgraph.c:ftrace_graph_init_task
```
```
In kernel/trace/trace_events.c (ffffffff811aecfc)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_create_new_event
  - kernel/trace/trace_events.c:trace_create_new_event
```
```
In kernel/bpf/syscall.c (ffffffff811d51c7)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:map_create
```
```
In kernel/bpf/btf.c (ffffffff811f22bc)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_new_fd
```
```
In kernel/events/core.c (ffffffff811ffabc)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:alloc_perf_context
```
```
In kernel/events/ring_buffer.c (ffffffff8120b3cd)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc
  - kernel/events/ring_buffer.c:rb_alloc_aux
  - kernel/events/ring_buffer.c:perf_aux_output_skip
  - kernel/events/ring_buffer.c:perf_aux_output_end
  - kernel/events/ring_buffer.c:perf_aux_output_begin
  - kernel/events/ring_buffer.c:perf_output_put_handle
```
```
In kernel/events/uprobes.c (ffffffff8120e6c1)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__create_xol_area
```
```
In kernel/padata.c (ffffffff8120feb1)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_alloc_pd
```
```
In kernel/jump_label.c (ffffffff8121121c)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/jump_label.c:static_key_enable_cpuslocked
  - kernel/jump_label.c:static_key_slow_inc_cpuslocked
```
```
In mm/filemap.c (ffffffff81219f27)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/shmem.c (ffffffff81232222)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_inode
```
```
In mm/backing-dev.c (ffffffff8123b5f5)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_alloc_node
  - mm/backing-dev.c:wb_congested_get_create
  - mm/backing-dev.c:default_bdi_init
```
```
In mm/rmap.c (ffffffff81266de0)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - mm/rmap.c:hugepage_add_new_anon_rmap
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:anon_vma_ctor
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:__anon_vma_prepare
```
```
In mm/page_alloc.c (ffffffff812728ef)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:memmap_init_zone_device
  - mm/page_alloc.c:memmap_init_zone_device
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:make_alloc_exact
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:prep_new_page
  - mm/page_alloc.c:prep_new_page
  - mm/page_alloc.c:prep_new_page
  - mm/page_alloc.c:check_new_page_bad
  - mm/page_alloc.c:init_cma_reserved_pageblock
  - mm/page_alloc.c:init_cma_reserved_pageblock
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:bad_page
```
```
In mm/swap_state.c (ffffffff81277a97)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - mm/swap_state.c:init_swap_address_space
  - mm/swap_state.c:swap_cluster_readahead
```
```
In mm/frontswap.c (ffffffff8127e4af)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_invalidate_area
```
```
In mm/zswap.c (ffffffff8127ebf6)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - mm/zswap.c:zswap_pool_create
```
```
In mm/hugetlb.c (ffffffff812817be)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:update_and_free_page
  - mm/hugetlb.c:update_and_free_page
  - mm/hugetlb.c:update_and_free_page
  - mm/hugetlb.c:dequeue_huge_page_nodemask
  - mm/hugetlb.c:resv_map_alloc
```
```
In mm/mempolicy.c (ffffffff8128cf98)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:__mpol_dup
```
```
In mm/memory_hotplug.c (ffffffff8129bfee)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__online_page_free
  - mm/memory_hotplug.c:put_page_bootmem
```
```
In mm/huge_memory.c (ffffffff812a3c98)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In mm/memcontrol.c (ffffffff812b0341)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_select_victim_node
```
```
In mm/zpool.c (ffffffff812bbfd9)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - mm/zpool.c:zpool_register_driver
```
```
In mm/zsmalloc.c (ffffffff812bcfcf)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - mm/zsmalloc.c:reset_page
```
```
In mm/hmm.c (ffffffff812c420a)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - mm/hmm.c:hmm_mirror_register
```
```
In fs/super.c (ffffffff812ce183)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/super.c:alloc_super
```
```
In fs/exec.c (ffffffff812d4a21)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In fs/dcache.c (ffffffff812e90ee)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/dcache.c:__d_alloc
```
```
In fs/inode.c (ffffffff812e9fef)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/inode.c:inode_init_always
  - fs/inode.c:inode_init_always
  - fs/inode.c:inode_init_always
  - fs/inode.c:inode_init_always
```
```
In fs/file.c (ffffffff812ee570)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/file.c:dup_fd
```
```
In fs/namespace.c (ffffffff812ef9e1)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In fs/fsopen.c (ffffffff8130bf68)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/fsopen.c:__ia32_sys_fspick
  - fs/fsopen.c:__x64_sys_fspick
  - fs/fsopen.c:__ia32_sys_fsopen
  - fs/fsopen.c:__x64_sys_fsopen
```
```
In fs/block_dev.c (ffffffff8131272a)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_direct_IO
```
```
In fs/notify/group.c (ffffffff8131a241)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_alloc_group
  - fs/notify/group.c:fsnotify_alloc_group
  - fs/notify/group.c:fsnotify_alloc_group
```
```
In fs/notify/mark.c (ffffffff8131a602)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_init_mark
```
```
In fs/eventfd.c (ffffffff81324de5)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/eventfd.c:do_eventfd
```
```
In fs/userfaultfd.c (ffffffff81325510)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/userfaultfd.c:__ia32_sys_userfaultfd
  - fs/userfaultfd.c:__x64_sys_userfaultfd
  - fs/userfaultfd.c:dup_userfaultfd
```
```
In fs/aio.c (ffffffff8132b5bd)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:__ia32_sys_io_destroy
  - fs/aio.c:__x64_sys_io_destroy
  - fs/aio.c:exit_aio
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
```
```
In fs/io_uring.c (ffffffff81331025)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_submit_sqe
```
```
In fs/crypto/keyinfo.c (ffffffff81338bb3)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In fs/mbcache.c (ffffffff813477cb)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/posix_acl.c (ffffffff81347e27)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/posix_acl.c:posix_acl_clone
  - fs/posix_acl.c:posix_acl_alloc
```
```
In fs/coredump.c (ffffffff81349c9b)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/iomap/buffered-io.c (ffffffff8134b7f3)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In fs/iomap/direct-io.c (ffffffff8134d1aa)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_rw
```
```
In fs/quota/dquot.c (ffffffff81350ac8)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/quota/dquot.c:dqget
```
```
In fs/proc/generic.c (ffffffff8135f615)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/proc/generic.c:__proc_create
```
```
In fs/kernfs/dir.c (ffffffff8136bfd4)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/kernfs/dir.c:__kernfs_new_node
```
```
In fs/kernfs/file.c (ffffffff8136d963)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_fop_open
  - fs/kernfs/file.c:kernfs_fop_open
```
```
In fs/configfs/dir.c (ffffffff81371681)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_new_dirent
  - fs/configfs/dir.c:new_fragment
```
```
In fs/configfs/item.c (ffffffff81374248)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/configfs/item.c:config_group_init_type_name
  - fs/configfs/item.c:config_item_init_type_name
```
```
In fs/ext4/mballoc.c (ffffffff813a7606)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
```
```
In fs/ext4/page-io.c (ffffffff813b27ef)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_init_io_end
```
```
In fs/ext4/super.c (ffffffff813c0a00)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_alloc_inode
```
```
In fs/jbd2/transaction.c (ffffffff813d5bd3)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
```
```
In fs/jbd2/journal.c (ffffffff813de8c9)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_init_common
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/ecryptfs/main.c (ffffffff813fa006)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_get_lower_file
```
```
In fs/ecryptfs/super.c (ffffffff813fa22f)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/ecryptfs/super.c:ecryptfs_alloc_inode
```
```
In fs/ecryptfs/miscdev.c (ffffffff828e6062)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/ecryptfs/miscdev.c:ecryptfs_init_ecryptfs_miscdev
```
```
In fs/fuse/dev.c (ffffffff81405241)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/fuse/dev.c:__fuse_request_alloc
```
```
In fs/fuse/file.c (ffffffff81410678)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_file_alloc
```
```
In fs/fuse/inode.c (ffffffff81412c31)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_conn_init
  - fs/fuse/inode.c:fuse_conn_init
  - fs/fuse/inode.c:fuse_conn_init
```
```
In fs/debugfs/file.c (ffffffff814181b5)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_atomic_t_set
  - fs/debugfs/file.c:debugfs_file_get
```
```
In ipc/util.c (ffffffff8141cd75)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In ipc/msg.c (ffffffff828e658b)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - ipc/msg.c:msg_init
  - ipc/msg.c:msg_init
```
```
In ipc/sem.c (ffffffff81423be2)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - ipc/sem.c:copy_semundo
  - ipc/sem.c:find_alloc_undo
```
```
In ipc/namespace.c (ffffffff8142a5b2)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - ipc/namespace.c:copy_ipcs
```
```
In security/keys/key.c (ffffffff8142bcba)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_user_lookup
  - security/keys/key.c:key_user_lookup
  - security/keys/key.c:key_user_lookup
```
```
In security/selinux/avc.c (ffffffff8144149b)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - security/selinux/avc.c:selinux_avc_init
  - security/selinux/avc.c:selinux_avc_init
```
```
In security/selinux/ss/sidtab.c (ffffffff8145279b)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_convert
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_init
  - security/selinux/ss/sidtab.c:sidtab_init
```
```
In security/selinux/ss/services.c (ffffffff8145e7a9)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
```
```
In security/tomoyo/condition.c (ffffffff8147128a)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
```
```
In security/tomoyo/gc.c (ffffffff814758d7)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In security/tomoyo/memory.c (ffffffff81476346)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_name
  - security/tomoyo/memory.c:tomoyo_get_group
```
```
In security/apparmor/apparmorfs.c (ffffffff8147d611)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_write_access
```
```
In security/apparmor/lib.c (ffffffff8147fd1a)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - security/apparmor/lib.c:aa_str_alloc
```
```
In security/apparmor/match.c (ffffffff81480707)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
```
```
In security/apparmor/policy_unpack.c (ffffffff81489e3d)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:aa_loaddata_alloc
```
```
In security/apparmor/policy_ns.c (ffffffff8148fed6)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:alloc_ns
```
```
In security/apparmor/label.c (ffffffff81491172)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_alloc
  - security/apparmor/label.c:aa_alloc_proxy
```
```
In crypto/api.c (ffffffff814a3a98)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - crypto/api.c:crypto_alg_mod_lookup
```
```
In crypto/algapi.c (ffffffff814a49ad)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - crypto/algapi.c:__crypto_register_alg
  - crypto/algapi.c:crypto_check_alg
```
```
In block/bio.c (ffffffff814c626e)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - block/bio.c:bio_reset
  - block/bio.c:bio_init
  - block/bio.c:bio_init
```
```
In block/blk-core.c (ffffffff814cad35)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - block/blk-core.c:blk_rq_init
```
```
In block/blk-ioc.c (ffffffff814d12d6)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - block/blk-ioc.c:create_task_io_context
  - block/blk-ioc.c:create_task_io_context
```
```
In block/blk-mq.c (ffffffff814d94ee)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/bsg.c (ffffffff814ee6de)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - block/bsg.c:bsg_open
```
```
In block/bsg-lib.c (ffffffff814ef19d)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_queue_rq
```
```
In block/blk-cgroup.c (ffffffff814efc6d)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_css_alloc
```
```
In block/blk-wbt.c (ffffffff814fc5ba)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_init
```
```
In lib/rhashtable.c (ffffffff8150d0ba)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_init
```
```
In lib/cpu_rmap.c (ffffffff81534f53)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - lib/cpu_rmap.c:alloc_cpu_rmap
```
```
In lib/sbitmap.c (ffffffff8153b02f)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbq_wake_up
```
```
In drivers/pinctrl/core.c (ffffffff8153fd33)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:create_pinctrl
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff81588471)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
```
```
In drivers/rapidio/rio.c (ffffffff815926ad)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_register_mport
  - drivers/rapidio/rio.c:rio_mport_initialize
  - drivers/rapidio/rio.c:rio_del_device
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff8159b9ed)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:register_framebuffer
```
```
In drivers/acpi/ec.c (ffffffff815c2a34)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_add_query_handler
```
```
In drivers/acpi/apei/ghes.c (ffffffff81621f88)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
```
```
In drivers/clk/clk.c (ffffffff8162f852)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_core_init
```
```
In drivers/dma/dmaengine.c (ffffffff81635148)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaengine_get_unmap_data
  - drivers/dma/dmaengine.c:dma_async_device_register
```
```
In drivers/xen/balloon.c (ffffffff81642a7b)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_process
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff8164cf44)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_open
```
```
In drivers/reset/core.c (ffffffff8165f2b3)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In drivers/tty/tty_io.c (ffffffff8166358b)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:alloc_tty_struct
```
```
In drivers/tty/tty_buffer.c (ffffffff8166aa59)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_init
  - drivers/tty/tty_buffer.c:tty_buffer_init
```
```
In drivers/tty/tty_port.c (ffffffff8166ad62)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_init
```
```
In drivers/tty/serial/serial_core.c (ffffffff816839c5)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_add_one_port
```
```
In drivers/char/virtio_console.c (ffffffff8169f79a)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:add_port
```
```
In drivers/char/hw_random/core.c (ffffffff816a242b)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In drivers/char/agp/backend.c (ffffffff816a29d4)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/char/agp/backend.c:agp_alloc_bridge
  - drivers/char/agp/backend.c:agp_alloc_bridge
```
```
In drivers/iommu/iova.c (ffffffff816ba844)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/iommu/iova.c:fq_flush_timeout
  - drivers/iommu/iova.c:init_iova_flush_queue
```
```
In drivers/connector/cn_queue.c (ffffffff816d06fa)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/connector/cn_queue.c:cn_queue_alloc_dev
  - drivers/connector/cn_queue.c:cn_queue_add_callback
```
```
In drivers/lightnvm/core.c (ffffffff816d1bb6)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_alloc_dev
```
```
In drivers/base/core.c (ffffffff816d7ac5)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In drivers/base/power/runtime.c (ffffffff816ea305)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_init
  - drivers/base/power/runtime.c:pm_runtime_init
```
```
In drivers/base/power/wakeup.c (ffffffff816efac8)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:pm_wakeup_clear
```
```
In drivers/base/power/domain.c (ffffffff816f0d5a)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/base/power/domain.c:pm_genpd_init
```
```
In drivers/base/firmware_loader/main.c (ffffffff816f5a22)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
```
```
In drivers/block/loop.c (ffffffff81707dfd)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_add
  - drivers/block/loop.c:lo_rw_aio
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In drivers/mfd/mfd-core.c (ffffffff81720264)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_add_devices
```
```
In drivers/nvdimm/core.c (ffffffff8172c27f)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff8172f0e1)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:__nvdimm_create
```
```
In drivers/nvdimm/dimm.c (ffffffff81730307)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In drivers/dax/bus.c (ffffffff817404d0)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In drivers/dma-buf/dma-fence.c (ffffffff81741efb)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_init
```
```
In drivers/dma-buf/dma-fence-array.c (ffffffff81743180)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_create
```
```
In drivers/dma-buf/sw_sync.c (ffffffff817455ca)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open
```
```
In drivers/scsi/scsi.c (ffffffff817484f5)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_finish_command
  - drivers/scsi/scsi.c:scsi_finish_command
  - drivers/scsi/scsi.c:scsi_finish_command
```
```
In drivers/scsi/scsi_lib.c (ffffffff81750e4c)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:__scsi_queue_insert
  - drivers/scsi/scsi_lib.c:__scsi_queue_insert
  - drivers/scsi/scsi_lib.c:__scsi_queue_insert
```
```
In drivers/scsi/scsi_scan.c (ffffffff8175221d)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
```
```
In drivers/scsi/sd.c (ffffffff8175ff97)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
```
```
In drivers/scsi/sr.c (ffffffff817621dd)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_probe
```
```
In drivers/scsi/sg.c (ffffffff81764368)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_open
```
```
In drivers/ata/libata-core.c (ffffffff8176a284)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_init
  - drivers/ata/libata-core.c:ata_host_alloc
```
```
In drivers/net/phy/sfp-bus.c (ffffffff8179bc18)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_bus_get
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817a56bd)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
```
```
In drivers/usb/core/usb.c (ffffffff817b2e04)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/usb/core/usb.c:usb_alloc_dev
```
```
In drivers/usb/core/hub.c (ffffffff817bb83c)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_probe
```
```
In drivers/usb/core/hcd.c (ffffffff817bc1bf)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:__usb_create_hcd
```
```
In drivers/usb/core/urb.c (ffffffff817bf9cf)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_init_urb
```
```
In drivers/usb/core/config.c (ffffffff817c60a4)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_configuration
```
```
In drivers/usb/core/file.c (ffffffff817c791f)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In drivers/media/cec/cec-notifier.c (ffffffff8184a5d2)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In drivers/thermal/thermal_core.c (ffffffff81854286)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff8185d6c2)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
```
```
In drivers/md/md.c (ffffffff8186ea1b)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_run
  - drivers/md/md.c:max_corrected_read_errors_store
  - drivers/md/md.c:md_rdev_init
  - drivers/md/md.c:md_rdev_init
  - drivers/md/md.c:md_rdev_init
  - drivers/md/md.c:errors_store
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:mddev_init
  - drivers/md/md.c:mddev_init
  - drivers/md/md.c:mddev_init
  - drivers/md/md.c:mddev_init
  - drivers/md/md.c:submit_flushes
```
```
In drivers/md/md-bitmap.c (ffffffff81873f57)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
```
```
In drivers/md/dm.c (ffffffff81877f58)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:dm_get_table_device
  - drivers/md/dm.c:alloc_io
```
```
In drivers/md/dm-table.c (ffffffff8187a254)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_get_device
```
```
In drivers/md/dm-stripe.c (ffffffff8187d982)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:stripe_ctr
```
```
In drivers/md/dm-io.c (ffffffff81881122)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/md/dm-io.c:dm_io
  - drivers/md/dm-io.c:sync_io
```
```
In drivers/md/dm-kcopyd.c (ffffffff818821ae)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
  - drivers/md/dm-kcopyd.c:dm_kcopyd_copy
```
```
In drivers/md/dm-stats.c (ffffffff81883605)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In drivers/opp/core.c (ffffffff8188d11b)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/opp/core.c:_opp_add
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff818957f3)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_stop
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
  - drivers/cpufreq/cpufreq_governor.c:dbs_update_util_handler
  - drivers/cpufreq/cpufreq_governor.c:dbs_work_handler
```
```
In drivers/mmc/core/sdio_irq.c (ffffffff818b0a7b)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_irq.c:sdio_release_irq
  - drivers/mmc/core/sdio_irq.c:sdio_claim_irq
```
```
In drivers/firmware/efi/efi.c (ffffffff81a935f2)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
```
```
In drivers/devfreq/devfreq.c (ffffffff818c7426)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
```
In drivers/nvmem/core.c (ffffffff818d12c6)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In net/core/sock.c (ffffffff818dfdc5)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_alloc
```
```
In net/core/skbuff.c (ffffffff818e7ac6)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_ext_add
  - net/core/skbuff.c:skb_ext_add
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:sock_zerocopy_realloc
  - net/core/skbuff.c:sock_zerocopy_alloc
  - net/core/skbuff.c:__skb_clone
  - net/core/skbuff.c:__build_skb_around
  - net/core/skbuff.c:__build_skb_around
  - net/core/skbuff.c:__alloc_skb
  - net/core/skbuff.c:__alloc_skb
  - net/core/skbuff.c:__alloc_skb
```
```
In net/core/net_namespace.c (ffffffff818f3fb6)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/core/net_namespace.c:copy_net_ns
  - net/core/net_namespace.c:copy_net_ns
  - net/core/net_namespace.c:setup_net
  - net/core/net_namespace.c:setup_net
```
```
In net/core/dev.c (ffffffff818fe065)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/core/dev.c:__dev_kfree_skb_irq
```
```
In net/core/dst.c (ffffffff8190e815)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/core/dst.c:__metadata_dst_init
  - net/core/dst.c:dst_cow_metrics_generic
```
```
In net/core/neighbour.c (ffffffff819143a4)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:___neigh_create
```
```
In net/core/filter.c (ffffffff8192cc1f)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/core/filter.c:__sk_attach_prog
```
```
In net/core/page_pool.c (ffffffff81934575)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_create
  - net/core/page_pool.c:page_pool_create
```
```
In net/core/skmsg.c (ffffffff81935cc5)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_init
```
```
In net/core/netpoll.c (ffffffff819374cf)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/core/netpoll.c:__netpoll_setup
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:zap_completion_queue
```
```
In net/core/fib_rules.c (ffffffff8193aa3e)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_default_rule_add
```
```
In net/core/devlink.c (ffffffff81947a62)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_health_reporter_create
```
```
In net/sched/sch_generic.c (ffffffff81957dae)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_alloc
```
```
In net/sched/cls_api.c (ffffffff8196222c)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tcf_block_get_ext
```
```
In net/sched/act_api.c (ffffffff819636d0)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_idr_create
  - net/sched/act_api.c:tcf_idr_create
```
```
In net/ipv4/route.c (ffffffff81971625)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_genid_init
  - net/ipv4/route.c:rt_genid_init
  - net/ipv4/route.c:rt_genid_init
```
```
In net/ipv4/inetpeer.c (ffffffff81976e1d)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff819837cc)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81984365)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_hash_add
```
```
In net/ipv4/tcp.c (ffffffff81986358)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv4/tcp.c:skb_entail
```
```
In net/ipv4/tcp_input.c (ffffffff8198de63)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/tcp_output.c (ffffffff8199b531)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819a1a80)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In net/ipv4/tcp_fastopen.c (ffffffff819a97d8)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/devinet.c (ffffffff819bbf68)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_init
```
```
In net/ipv4/igmp.c (ffffffff819c2edb)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv4/igmp.c:____ip_mc_inc_group
```
```
In net/ipv4/fib_semantics.c (ffffffff819c9702)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/ipv4/inet_fragment.c (ffffffff819cfa03)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frags_init
```
```
In net/ipv4/metrics.c (ffffffff819d341c)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In net/ipv4/nexthop.c (ffffffff819d591b)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff819d61df)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:proc_tfo_blackhole_detect_timeout
```
```
In net/ipv4/ipmr.c (ffffffff819dc3c2)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv4/syncookies.c (ffffffff819df0af)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:tcp_get_cookie_sock
```
```
In net/ipv4/cipso_ipv4.c (ffffffff819e2936)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff819e6a42)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
```
```
In net/xfrm/xfrm_state.c (ffffffff819ee0df)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
```
```
In net/unix/af_unix.c (ffffffff819fac1d)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
```
```
In net/ipv6/af_inet6.c (ffffffff819fee17)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In net/ipv6/anycast.c (ffffffff819ffabb)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
```
```
In net/ipv6/addrconf.c (ffffffff81a0a522)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/route.c (ffffffff81a123b8)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_upper_bound_set
```
```
In net/ipv6/ip6_fib.c (ffffffff81a1f484)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_metric_set
  - net/ipv6/ip6_fib.c:fib6_info_alloc
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81a2345b)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In net/ipv6/mcast.c (ffffffff81a339ea)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
```
```
In net/ipv6/exthdrs.c (ffffffff81a3cd48)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_dup_options
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81a3f6a0)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:fl_create
```
```
In net/ipv6/ip6mr.c (ffffffff81a44c39)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/ipv6/calipso.c (ffffffff81a4bcfe)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_doi_add
```
```
In net/packet/af_packet.c (ffffffff81a59e8c)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
```
```
In net/xdp/xdp_umem.c (ffffffff81a75c54)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_create
```
```
In lib/dump_stack.c (ffffffff81a771ee)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - lib/dump_stack.c:dump_stack
```
```
In lib/klist.c (ffffffff81a78e1e)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - lib/klist.c:klist_node_init
```
```
In lib/kobject.c (ffffffff81a7a3b6)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - lib/kobject.c:kset_register
  - lib/kobject.c:kobject_init
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
In arch/x86/kernel/tboot.c (ffffffff828ae9aa)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104c6dc)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:fake_panic_set
  - arch/x86/kernel/cpu/mce/core.c:fake_panic_set
  - arch/x86/kernel/cpu/mce/core.c:fake_panic_set
  - arch/x86/kernel/cpu/mce/core.c:fake_panic_set
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff810523a9)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff81052ed7)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff8105693d)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In arch/x86/kernel/reboot.c (ffffffff81062e57)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff81065886)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_target
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
```
```
In arch/x86/kernel/kgdb.c (ffffffff81074f7f)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In arch/x86/mm/init_64.c (ffffffff81acb562)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pagetable
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff828ca0b5)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_common
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus
```
```
In kernel/fork.c (ffffffff8109ea00)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:mm_init
  - kernel/fork.c:mm_init
  - kernel/fork.c:mm_init
```
```
In kernel/softirq.c (ffffffff810a72f5)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/softirq.c:tasklet_init
```
```
In kernel/user.c (ffffffff810af41e)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/user.c:alloc_uid
```
```
In kernel/workqueue.c (ffffffff810c48e0)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_offline_cpu
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:flush_workqueue_prep_pwqs
```
```
In kernel/pid.c (ffffffff810c6119)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/pid.c:alloc_pid
```
```
In kernel/nsproxy.c (ffffffff810cc561)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/nsproxy.c:create_new_namespaces
```
```
In kernel/cred.c (ffffffff810cde13)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:cred_alloc_blank
```
```
In kernel/smpboot.c (ffffffff810cfa1c)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/smpboot.c:cpu_wait_death
  - kernel/smpboot.c:cpu_check_up_prepare
```
```
In kernel/groups.c (ffffffff810d0498)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/groups.c:groups_alloc
```
```
In kernel/sched/core.c (ffffffff828cd624)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init
```
```
In kernel/sched/fair.c (ffffffff810e908a)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_fault
```
```
In kernel/sched/cpupri.c (ffffffff810f6287)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_init
```
```
In kernel/sched/topology.c (ffffffff810f7aaf)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:init_defrootdomain
```
```
In kernel/sched/autogroup.c (ffffffff810fa6bf)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
  - kernel/sched/autogroup.c:autogroup_init
```
```
In kernel/sched/membarrier.c (ffffffff811018cf)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/sched/membarrier.c:membarrier_exec_mmap
```
```
In kernel/sched/psi.c (ffffffff81101f47)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_trigger_destroy
  - kernel/sched/psi.c:psi_poll_work
  - kernel/sched/psi.c:group_init
```
```
In kernel/locking/mutex.c (ffffffff81103494)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/locking/mutex.c:__mutex_init
```
```
In kernel/locking/rwsem.c (ffffffff811038ec)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:__init_rwsem
```
```
In kernel/power/swap.c (ffffffff8110e50e)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:save_image
```
```
In kernel/irq/manage.c (ffffffff81117c39)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_notifier
```
```
In kernel/rcu/srcutree.c (ffffffff81125312)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
```
```
In kernel/rcu/tree.c (ffffffff811269f0)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In kernel/futex.c (ffffffff828d123e)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/futex.c:futex_init
```
```
In kernel/module.c (ffffffff811559cc)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/module.c:load_module
```
```
In kernel/kexec_core.c (ffffffff8115a472)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_free_reserved_phys_range
  - kernel/kexec_core.c:crash_kexec
```
```
In kernel/cgroup/cgroup.c (ffffffff8115fe00)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:init_cgroup_root
  - kernel/cgroup/cgroup.c:find_css_set
```
```
In kernel/cgroup/namespace.c (ffffffff81167ab1)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
```
```
In kernel/utsname.c (ffffffff811716b8)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/utsname.c:copy_utsname
```
```
In kernel/user_namespace.c (ffffffff811729c5)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In kernel/pid_namespace.c (ffffffff81173528)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In kernel/stop_machine.c (ffffffff8117443a)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:stop_two_cpus
  - kernel/stop_machine.c:multi_cpu_stop
  - kernel/stop_machine.c:cpu_stop_init_done
```
```
In kernel/audit_watch.c (ffffffff8117e218)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_init_watch
```
```
In kernel/audit_tree.c (ffffffff811806c7)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_make_tree
```
```
In kernel/debug/debug_core.c (ffffffff8118419e)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_tasklet_bpt
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff8118965f)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In kernel/hung_task.c (ffffffff8118f5b5)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/hung_task.c:reset_hung_task_detector
```
```
In kernel/seccomp.c (ffffffff81191f02)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
```
```
In kernel/relay.c (ffffffff81192dbd)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/relay.c:__relay_reset
```
```
In kernel/trace/trace.c (ffffffff811a5df1)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
```
```
In kernel/trace/tracing_map.c (ffffffff811b111e)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_create
  - kernel/trace/tracing_map.c:tracing_map_clear
```
```
In kernel/trace/blktrace.c (ffffffff811b71e7)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:do_blk_trace_setup
```
```
In kernel/trace/fgraph.c (ffffffff811b9f2a)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/trace/fgraph.c:start_graph_tracing
  - kernel/trace/fgraph.c:start_graph_tracing
  - kernel/trace/fgraph.c:ftrace_graph_init_task
  - kernel/trace/fgraph.c:ftrace_graph_init_task
```
```
In kernel/trace/trace_events.c (ffffffff811ba35c)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_create_new_event
  - kernel/trace/trace_events.c:trace_create_new_event
```
```
In kernel/bpf/syscall.c (ffffffff811e18ec)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:map_create
```
```
In kernel/bpf/btf.c (ffffffff811fe9cc)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_new_fd
```
```
In kernel/events/core.c (ffffffff8120cc1c)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:alloc_perf_context
```
```
In kernel/events/ring_buffer.c (ffffffff812186ad)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc
  - kernel/events/ring_buffer.c:rb_alloc_aux
  - kernel/events/ring_buffer.c:perf_aux_output_skip
  - kernel/events/ring_buffer.c:perf_aux_output_end
  - kernel/events/ring_buffer.c:perf_aux_output_begin
  - kernel/events/ring_buffer.c:perf_output_put_handle
```
```
In kernel/events/uprobes.c (ffffffff8121bd01)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__create_xol_area
```
```
In kernel/padata.c (ffffffff8121d8a4)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_alloc_pd
```
```
In kernel/jump_label.c (ffffffff8121eecc)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In mm/filemap.c (ffffffff81227897)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/shmem.c (ffffffff81240452)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_inode
```
```
In mm/backing-dev.c (ffffffff81249b15)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_alloc_node
  - mm/backing-dev.c:wb_congested_get_create
  - mm/backing-dev.c:default_bdi_init
```
```
In mm/rmap.c (ffffffff81275700)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - mm/rmap.c:hugepage_add_new_anon_rmap
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:anon_vma_ctor
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:__anon_vma_prepare
```
```
In mm/page_alloc.c (ffffffff8128174f)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:memmap_init_zone_device
  - mm/page_alloc.c:memmap_init_zone_device
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:make_alloc_exact
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:prep_new_page
  - mm/page_alloc.c:prep_new_page
  - mm/page_alloc.c:prep_new_page
  - mm/page_alloc.c:check_new_page_bad
  - mm/page_alloc.c:init_cma_reserved_pageblock
  - mm/page_alloc.c:init_cma_reserved_pageblock
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:bad_page
```
```
In mm/swap_state.c (ffffffff81287587)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - mm/swap_state.c:init_swap_address_space
  - mm/swap_state.c:swap_cluster_readahead
```
```
In mm/frontswap.c (ffffffff8128df0f)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_invalidate_area
```
```
In mm/zswap.c (ffffffff8128e636)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - mm/zswap.c:zswap_pool_create
```
```
In mm/hugetlb.c (ffffffff81290b1e)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:update_and_free_page
  - mm/hugetlb.c:update_and_free_page
  - mm/hugetlb.c:update_and_free_page
  - mm/hugetlb.c:dequeue_huge_page_nodemask
  - mm/hugetlb.c:resv_map_alloc
```
```
In mm/mempolicy.c (ffffffff8129cbc8)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:__mpol_dup
```
```
In mm/memory_hotplug.c (ffffffff812abd5e)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__online_page_free
  - mm/memory_hotplug.c:put_page_bootmem
```
```
In mm/huge_memory.c (ffffffff812b5198)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In mm/memcontrol.c (ffffffff812c1e31)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_select_victim_node
```
```
In mm/zpool.c (ffffffff812cdeb9)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - mm/zpool.c:zpool_register_driver
```
```
In mm/zsmalloc.c (ffffffff812ceebf)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - mm/zsmalloc.c:reset_page
```
```
In fs/super.c (ffffffff812dfbd3)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/super.c:alloc_super
```
```
In fs/exec.c (ffffffff812e65a1)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In fs/dcache.c (ffffffff812fac8e)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/dcache.c:__d_alloc
```
```
In fs/inode.c (ffffffff812fba8a)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/inode.c:inode_init_always
  - fs/inode.c:inode_init_always
  - fs/inode.c:inode_init_always
  - fs/inode.c:inode_init_always
```
```
In fs/file.c (ffffffff81300030)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/file.c:dup_fd
```
```
In fs/namespace.c (ffffffff813014b1)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In fs/fsopen.c (ffffffff8131ef78)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/fsopen.c:__ia32_sys_fspick
  - fs/fsopen.c:__x64_sys_fspick
  - fs/fsopen.c:__ia32_sys_fsopen
  - fs/fsopen.c:__x64_sys_fsopen
```
```
In fs/block_dev.c (ffffffff81325679)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_direct_IO
```
```
In fs/notify/group.c (ffffffff8132d061)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_alloc_group
  - fs/notify/group.c:fsnotify_alloc_group
  - fs/notify/group.c:fsnotify_alloc_group
```
```
In fs/notify/mark.c (ffffffff8132d422)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_init_mark
```
```
In fs/eventfd.c (ffffffff81337b75)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/eventfd.c:do_eventfd
```
```
In fs/userfaultfd.c (ffffffff813382a0)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/userfaultfd.c:__ia32_sys_userfaultfd
  - fs/userfaultfd.c:__x64_sys_userfaultfd
  - fs/userfaultfd.c:dup_userfaultfd
```
```
In fs/aio.c (ffffffff8133e40d)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:__ia32_sys_io_destroy
  - fs/aio.c:__x64_sys_io_destroy
  - fs/aio.c:exit_aio
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
```
```
In fs/io_uring.c (ffffffff81344bb1)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_get_req
```
```
In fs/crypto/keyring.c (ffffffff8134c805)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/crypto/keyring.c:add_master_key
```
```
In fs/crypto/keysetup_v1.c (ffffffff8134e69f)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
```
```
In fs/mbcache.c (ffffffff8135f7db)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/posix_acl.c (ffffffff813600c7)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/posix_acl.c:posix_acl_clone
  - fs/posix_acl.c:posix_acl_alloc
```
```
In fs/coredump.c (ffffffff81361f3b)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/iomap/buffered-io.c (ffffffff81363ac3)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In fs/iomap/direct-io.c (ffffffff8136545a)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_rw
```
```
In fs/quota/dquot.c (ffffffff81368e48)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/quota/dquot.c:dqget
```
```
In fs/proc/generic.c (ffffffff81377875)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/proc/generic.c:__proc_create
```
```
In fs/kernfs/dir.c (ffffffff81384193)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/kernfs/dir.c:__kernfs_new_node
```
```
In fs/kernfs/file.c (ffffffff81385ca3)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_fop_open
  - fs/kernfs/file.c:kernfs_fop_open
```
```
In fs/configfs/dir.c (ffffffff81389ad1)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_new_dirent
  - fs/configfs/dir.c:new_fragment
```
```
In fs/configfs/item.c (ffffffff8138c4c8)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/configfs/item.c:config_group_init_type_name
  - fs/configfs/item.c:config_item_init_type_name
```
```
In fs/ext4/mballoc.c (ffffffff813c04a0)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
```
```
In fs/ext4/page-io.c (ffffffff813cb83f)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_init_io_end
```
```
In fs/ext4/super.c (ffffffff813d9d50)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_alloc_inode
```
```
In fs/jbd2/transaction.c (ffffffff813efc0a)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
```
```
In fs/jbd2/journal.c (ffffffff813f8989)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_init_common
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/ecryptfs/main.c (ffffffff81413ed6)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_get_lower_file
```
```
In fs/ecryptfs/super.c (ffffffff814140ff)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/ecryptfs/super.c:ecryptfs_alloc_inode
```
```
In fs/ecryptfs/miscdev.c (ffffffff828eeb28)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/ecryptfs/miscdev.c:ecryptfs_init_ecryptfs_miscdev
```
```
In fs/fuse/dev.c (ffffffff8141f366)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_request_alloc
```
```
In fs/fuse/file.c (ffffffff8142a288)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_file_alloc
```
```
In fs/fuse/inode.c (ffffffff8142c91b)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_conn_init
  - fs/fuse/inode.c:fuse_conn_init
  - fs/fuse/inode.c:fuse_conn_init
```
```
In fs/debugfs/file.c (ffffffff81432075)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_atomic_t_set
  - fs/debugfs/file.c:debugfs_file_get
```
```
In ipc/util.c (ffffffff81436bc5)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In ipc/msg.c (ffffffff828ef044)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - ipc/msg.c:msg_init
  - ipc/msg.c:msg_init
```
```
In ipc/sem.c (ffffffff8143d922)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - ipc/sem.c:copy_semundo
  - ipc/sem.c:find_alloc_undo
```
```
In ipc/namespace.c (ffffffff814442e2)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - ipc/namespace.c:copy_ipcs
```
```
In security/keys/key.c (ffffffff81445a0a)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_user_lookup
  - security/keys/key.c:key_user_lookup
  - security/keys/key.c:key_user_lookup
```
```
In security/selinux/avc.c (ffffffff8145ad7b)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - security/selinux/avc.c:selinux_avc_init
  - security/selinux/avc.c:selinux_avc_init
```
```
In security/selinux/ss/services.c (ffffffff81478559)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
```
```
In security/tomoyo/condition.c (ffffffff8148b02a)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
```
```
In security/tomoyo/gc.c (ffffffff8148f677)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In security/tomoyo/memory.c (ffffffff814900e6)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_name
  - security/tomoyo/memory.c:tomoyo_get_group
```
```
In security/apparmor/apparmorfs.c (ffffffff814972e1)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_write_access
```
```
In security/apparmor/lib.c (ffffffff81499a1a)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - security/apparmor/lib.c:aa_str_alloc
```
```
In security/apparmor/match.c (ffffffff8149a407)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
```
```
In security/apparmor/policy_unpack.c (ffffffff814a3cfd)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:aa_loaddata_alloc
```
```
In security/apparmor/policy_ns.c (ffffffff814a9d96)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:alloc_ns
```
```
In security/apparmor/label.c (ffffffff814ab022)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_alloc
  - security/apparmor/label.c:aa_alloc_proxy
```
```
In crypto/api.c (ffffffff814be6c8)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - crypto/api.c:crypto_alg_mod_lookup
```
```
In crypto/algapi.c (ffffffff814bf63d)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - crypto/algapi.c:__crypto_register_alg
  - crypto/algapi.c:crypto_check_alg
```
```
In block/bio.c (ffffffff814dea2d)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - block/bio.c:bio_reset
  - block/bio.c:bio_init
  - block/bio.c:bio_init
```
```
In block/blk-core.c (ffffffff814e3f15)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - block/blk-core.c:blk_rq_init
```
```
In block/blk-ioc.c (ffffffff814ea686)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - block/blk-ioc.c:create_task_io_context
  - block/blk-ioc.c:create_task_io_context
```
```
In block/blk-mq.c (ffffffff814f28ae)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/bsg.c (ffffffff81507b3e)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - block/bsg.c:bsg_open
```
```
In block/bsg-lib.c (ffffffff8150864d)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_queue_rq
```
```
In block/blk-cgroup.c (ffffffff8150911d)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_css_alloc
```
```
In block/blk-iocost.c (ffffffff81511ffb)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - block/blk-iocost.c:blk_iocost_init
```
```
In block/blk-wbt.c (ffffffff8151a50a)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_init
```
```
In lib/rhashtable.c (ffffffff8152af0a)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_init
```
```
In lib/cpu_rmap.c (ffffffff81555d63)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - lib/cpu_rmap.c:alloc_cpu_rmap
```
```
In lib/sbitmap.c (ffffffff8155be4f)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbq_wake_up
```
```
In drivers/pinctrl/core.c (ffffffff81560bd3)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:create_pinctrl
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff815a9e71)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
```
```
In drivers/rapidio/rio.c (ffffffff815b392d)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_register_mport
  - drivers/rapidio/rio.c:rio_mport_initialize
  - drivers/rapidio/rio.c:rio_del_device
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff815bcfed)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:register_framebuffer
```
```
In drivers/acpi/ec.c (ffffffff815e3de4)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_add_query_handler
```
```
In drivers/acpi/apei/ghes.c (ffffffff81643a68)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
```
```
In drivers/clk/clk.c (ffffffff81651c4f)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_core_init
```
```
In drivers/dma/dmaengine.c (ffffffff81656e58)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaengine_get_unmap_data
  - drivers/dma/dmaengine.c:dma_async_device_register
```
```
In drivers/xen/balloon.c (ffffffff81665023)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_process
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff8166f684)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_open
```
```
In drivers/reset/core.c (ffffffff816819ed)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In drivers/tty/tty_io.c (ffffffff81685bfb)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:alloc_tty_struct
```
```
In drivers/tty/tty_buffer.c (ffffffff8168d149)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_init
  - drivers/tty/tty_buffer.c:tty_buffer_init
```
```
In drivers/tty/tty_port.c (ffffffff8168d432)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_init
```
```
In drivers/tty/serial/serial_core.c (ffffffff816a6065)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_add_one_port
```
```
In drivers/char/virtio_console.c (ffffffff816c253a)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:add_port
```
```
In drivers/char/hw_random/core.c (ffffffff816c51cc)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In drivers/char/agp/backend.c (ffffffff816c5764)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/char/agp/backend.c:agp_alloc_bridge
  - drivers/char/agp/backend.c:agp_alloc_bridge
```
```
In drivers/iommu/iova.c (ffffffff816dd684)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/iommu/iova.c:fq_flush_timeout
  - drivers/iommu/iova.c:init_iova_flush_queue
```
```
In drivers/connector/cn_queue.c (ffffffff816f451a)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/connector/cn_queue.c:cn_queue_alloc_dev
  - drivers/connector/cn_queue.c:cn_queue_add_callback
```
```
In drivers/lightnvm/core.c (ffffffff816f5aa6)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_alloc_dev
```
```
In drivers/base/core.c (ffffffff816fbbaa)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/power/runtime.c (ffffffff8170e365)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_init
  - drivers/base/power/runtime.c:pm_runtime_init
```
```
In drivers/base/power/wakeup.c (ffffffff81713af8)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:pm_wakeup_clear
```
```
In drivers/base/power/domain.c (ffffffff817151fa)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/base/power/domain.c:pm_genpd_init
```
```
In drivers/base/firmware_loader/main.c (ffffffff81719e22)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
```
```
In drivers/block/loop.c (ffffffff8172c04d)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_add
  - drivers/block/loop.c:lo_rw_aio
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In drivers/mfd/mfd-core.c (ffffffff81744534)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_add_devices
```
```
In drivers/nvdimm/core.c (ffffffff817504cf)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff8175347c)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:__nvdimm_create
```
```
In drivers/nvdimm/dimm.c (ffffffff81754397)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In drivers/dax/bus.c (ffffffff817646d0)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In drivers/dma-buf/dma-fence.c (ffffffff817667db)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In drivers/dma-buf/dma-fence-array.c (ffffffff817670ea)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_create
```
```
In drivers/dma-buf/sw_sync.c (ffffffff8176974a)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open
```
```
In drivers/scsi/scsi.c (ffffffff8176c645)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_finish_command
  - drivers/scsi/scsi.c:scsi_finish_command
  - drivers/scsi/scsi.c:scsi_finish_command
```
```
In drivers/scsi/scsi_lib.c (ffffffff817750b2)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:__scsi_queue_insert
  - drivers/scsi/scsi_lib.c:__scsi_queue_insert
  - drivers/scsi/scsi_lib.c:__scsi_queue_insert
```
```
In drivers/scsi/scsi_scan.c (ffffffff8177649d)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
```
```
In drivers/scsi/sd.c (ffffffff81783ef7)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
```
```
In drivers/scsi/sr.c (ffffffff817861cd)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_probe
```
```
In drivers/scsi/sg.c (ffffffff81788358)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_open
```
```
In drivers/ata/libata-core.c (ffffffff8178e2e4)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_init
  - drivers/ata/libata-core.c:ata_host_alloc
```
```
In drivers/net/phy/sfp-bus.c (ffffffff817bf6c8)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_bus_get
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817c7d1d)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
```
```
In drivers/vfio/vfio.c (ffffffff817d0670)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_fops_open
  - drivers/vfio/vfio.c:vfio_add_group_dev
  - drivers/vfio/vfio.c:vfio_add_group_dev
  - drivers/vfio/vfio.c:vfio_add_group_dev
  - drivers/vfio/vfio.c:vfio_add_group_dev
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff817d4687)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff817d775c)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_probe
```
```
In drivers/usb/core/usb.c (ffffffff817e3534)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/usb/core/usb.c:usb_alloc_dev
```
```
In drivers/usb/core/hub.c (ffffffff817ec04a)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_probe
```
```
In drivers/usb/core/hcd.c (ffffffff817ec9ef)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:__usb_create_hcd
```
```
In drivers/usb/core/urb.c (ffffffff817f034f)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_init_urb
```
```
In drivers/usb/core/config.c (ffffffff817f6b58)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_configuration
```
```
In drivers/usb/core/file.c (ffffffff817f843f)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In drivers/media/cec/cec-notifier.c (ffffffff8187bdc2)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In drivers/thermal/thermal_core.c (ffffffff81887ab1)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
```
```
In drivers/md/md.c (ffffffff818a07f8)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_run
  - drivers/md/md.c:max_corrected_read_errors_store
  - drivers/md/md.c:md_rdev_init
  - drivers/md/md.c:md_rdev_init
  - drivers/md/md.c:md_rdev_init
  - drivers/md/md.c:errors_store
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:mddev_init
  - drivers/md/md.c:mddev_init
  - drivers/md/md.c:mddev_init
  - drivers/md/md.c:mddev_init
  - drivers/md/md.c:submit_flushes
```
```
In drivers/md/md-bitmap.c (ffffffff818a5d67)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
```
```
In drivers/md/dm.c (ffffffff818a9d88)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:dm_get_table_device
  - drivers/md/dm.c:alloc_io
```
```
In drivers/md/dm-table.c (ffffffff818ac034)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_get_device
```
```
In drivers/md/dm-stripe.c (ffffffff818af762)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:stripe_ctr
```
```
In drivers/md/dm-io.c (ffffffff818b2ff3)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/md/dm-io.c:dm_io
  - drivers/md/dm-io.c:sync_io
```
```
In drivers/md/dm-kcopyd.c (ffffffff818b404e)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
  - drivers/md/dm-kcopyd.c:dm_kcopyd_copy
```
```
In drivers/md/dm-stats.c (ffffffff818b54d8)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In drivers/edac/ghes_edac.c (ffffffff818bcff2)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/edac/ghes_edac.c:ghes_edac_register
```
```
In drivers/opp/core.c (ffffffff818bf35b)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/opp/core.c:_opp_add
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff818c7813)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_stop
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
  - drivers/cpufreq/cpufreq_governor.c:dbs_update_util_handler
  - drivers/cpufreq/cpufreq_governor.c:dbs_work_handler
```
```
In drivers/mmc/core/sdio_irq.c (ffffffff818e2f21)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_irq.c:sdio_release_irq
  - drivers/mmc/core/sdio_irq.c:sdio_claim_irq
```
```
In drivers/firmware/efi/efi.c (ffffffff81acade0)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff818f415c)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
```
```
In drivers/devfreq/devfreq.c (ffffffff818f98e4)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
```
In drivers/nvmem/core.c (ffffffff819036c6)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In net/core/sock.c (ffffffff81911f7f)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_alloc
```
```
In net/core/skbuff.c (ffffffff81919f96)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_ext_add
  - net/core/skbuff.c:skb_ext_add
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:sock_zerocopy_realloc
  - net/core/skbuff.c:sock_zerocopy_alloc
  - net/core/skbuff.c:__skb_clone
  - net/core/skbuff.c:__build_skb_around
  - net/core/skbuff.c:__build_skb_around
  - net/core/skbuff.c:__alloc_skb
  - net/core/skbuff.c:__alloc_skb
  - net/core/skbuff.c:__alloc_skb
```
```
In net/core/net_namespace.c (ffffffff81925f76)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/core/net_namespace.c:copy_net_ns
  - net/core/net_namespace.c:copy_net_ns
  - net/core/net_namespace.c:setup_net
  - net/core/net_namespace.c:setup_net
```
```
In net/core/dev.c (ffffffff81930395)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/core/dev.c:__dev_kfree_skb_irq
```
```
In net/core/dst.c (ffffffff81940e75)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/core/dst.c:__metadata_dst_init
  - net/core/dst.c:dst_cow_metrics_generic
```
```
In net/core/neighbour.c (ffffffff81946a14)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:___neigh_create
```
```
In net/core/filter.c (ffffffff8195ef1f)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/core/filter.c:__sk_attach_prog
```
```
In net/core/page_pool.c (ffffffff819671a5)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_create
  - net/core/page_pool.c:page_pool_create
```
```
In net/core/skmsg.c (ffffffff81968d85)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_init
```
```
In net/core/netpoll.c (ffffffff8196a38f)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/core/netpoll.c:__netpoll_setup
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:zap_completion_queue
```
```
In net/core/fib_rules.c (ffffffff8196d8fe)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_default_rule_add
```
```
In net/core/devlink.c (ffffffff81984381)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_traps_register
  - net/core/devlink.c:devlink_health_reporter_create
```
```
In net/sched/sch_generic.c (ffffffff8198e24e)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_alloc
```
```
In net/sched/cls_api.c (ffffffff81999400)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tcf_block_get_ext
```
```
In net/sched/act_api.c (ffffffff8199a250)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_idr_create
  - net/sched/act_api.c:tcf_idr_create
```
```
In net/ipv4/route.c (ffffffff819a8035)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_genid_init
  - net/ipv4/route.c:rt_genid_init
  - net/ipv4/route.c:rt_genid_init
```
```
In net/ipv4/inetpeer.c (ffffffff819ad7ad)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff819b9fbc)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819bab15)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_hash_add
```
```
In net/ipv4/tcp.c (ffffffff819bcae8)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv4/tcp.c:skb_entail
```
```
In net/ipv4/tcp_input.c (ffffffff819c4a33)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/tcp_output.c (ffffffff819d1f51)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819d8741)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In net/ipv4/tcp_fastopen.c (ffffffff819e0498)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/devinet.c (ffffffff819f2c68)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_init
```
```
In net/ipv4/igmp.c (ffffffff819f9a7b)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv4/igmp.c:____ip_mc_inc_group
```
```
In net/ipv4/fib_semantics.c (ffffffff81a002e5)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/ipv4/inet_fragment.c (ffffffff81a06593)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frags_init
```
```
In net/ipv4/metrics.c (ffffffff81a09f8c)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In net/ipv4/nexthop.c (ffffffff81a0c48b)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81a0cccf)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:proc_tfo_blackhole_detect_timeout
```
```
In net/ipv4/ipmr.c (ffffffff81a133b2)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv4/syncookies.c (ffffffff81a1613f)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:tcp_get_cookie_sock
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81a19926)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a1da32)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
```
```
In net/xfrm/xfrm_state.c (ffffffff81a24f4f)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
```
```
In net/unix/af_unix.c (ffffffff81a318ad)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
```
```
In net/ipv6/af_inet6.c (ffffffff81a35a17)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In net/ipv6/anycast.c (ffffffff81a3669b)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
```
```
In net/ipv6/addrconf.c (ffffffff81a411d2)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/route.c (ffffffff81a48fa8)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_upper_bound_set
```
```
In net/ipv6/ip6_fib.c (ffffffff81a56104)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_metric_set
  - net/ipv6/ip6_fib.c:fib6_info_alloc
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81a59e40)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In net/ipv6/mcast.c (ffffffff81a6a53a)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
```
```
In net/ipv6/exthdrs.c (ffffffff81a739c8)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_dup_options
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81a76310)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:fl_create
```
```
In net/ipv6/ip6mr.c (ffffffff81a7b829)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/ipv6/calipso.c (ffffffff81a828ce)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_doi_add
```
```
In net/packet/af_packet.c (ffffffff81a8ff9c)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
```
```
In net/xdp/xdp_umem.c (ffffffff81aacad5)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_create
```
```
In lib/dump_stack.c (ffffffff81aae5d8)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - lib/dump_stack.c:dump_stack
```
```
In lib/klist.c (ffffffff81ab01c2)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - lib/klist.c:klist_node_init
```
```
In lib/kobject.c (ffffffff81ab1716)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - lib/kobject.c:kset_register
  - lib/kobject.c:kobject_init
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
In arch/x86/kernel/ioport.c (ffffffff8103721f)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
  - arch/x86/kernel/ioport.c:ksys_ioperm
```
```
In arch/x86/kernel/tboot.c (ffffffff82cd38a3)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81050f2c)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:fake_panic_set
  - arch/x86/kernel/cpu/mce/core.c:fake_panic_set
  - arch/x86/kernel/cpu/mce/core.c:fake_panic_set
  - arch/x86/kernel/cpu/mce/core.c:fake_panic_set
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:mce_start
  - arch/x86/kernel/cpu/mce/core.c:mce_start
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81056594)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:threshold_create_bank
```
```
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff81057e95)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff8105b86d)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:reload_store
  - arch/x86/kernel/cpu/microcode/core.c:reload_store
```
```
In arch/x86/kernel/reboot.c (ffffffff81068ed7)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff8106c1d9)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_target
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
```
```
In arch/x86/kernel/kgdb.c (ffffffff8107c18f)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - arch/x86/kernel/kgdb.c:kgdb_arch_handle_exception
  - arch/x86/kernel/kgdb.c:kgdb_arch_handle_exception
```
```
In arch/x86/mm/init_64.c (ffffffff81bc3a64)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pagetable
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff82ceca01)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_common
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus
```
```
In kernel/fork.c (ffffffff810a4c7b)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/fork.c:copy_signal
  - kernel/fork.c:copy_signal
  - kernel/fork.c:copy_sighand
  - kernel/fork.c:mm_init
  - kernel/fork.c:mm_init
  - kernel/fork.c:mm_init
  - kernel/fork.c:dup_task_struct
  - kernel/fork.c:dup_task_struct
  - kernel/fork.c:dup_task_struct
```
```
In kernel/softirq.c (ffffffff810aea45)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/softirq.c:tasklet_init
```
```
In kernel/user.c (ffffffff810b712e)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/user.c:alloc_uid
```
```
In kernel/workqueue.c (ffffffff810c818f)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/workqueue.c:unbind_workers
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:flush_workqueue_prep_pwqs
```
```
In kernel/pid.c (ffffffff810cdf6f)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/pid.c:alloc_pid
```
```
In kernel/nsproxy.c (ffffffff810d5aa1)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/nsproxy.c:create_new_namespaces
```
```
In kernel/cred.c (ffffffff810d7b98)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:cred_alloc_blank
```
```
In kernel/smpboot.c (ffffffff810d991c)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/smpboot.c:cpu_wait_death
  - kernel/smpboot.c:cpu_check_up_prepare
```
```
In kernel/groups.c (ffffffff810da2f8)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/groups.c:groups_alloc
```
```
In kernel/sched/core.c (ffffffff82ceea1e)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init
```
```
In kernel/sched/fair.c (ffffffff810ef1d7)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_group
```
```
In kernel/sched/cpupri.c (ffffffff810ffbd7)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_init
```
```
In kernel/sched/topology.c (ffffffff81100e1f)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/sched/topology.c:sd_init
  - kernel/sched/topology.c:init_defrootdomain
  - kernel/sched/topology.c:init_rootdomain
```
```
In kernel/sched/autogroup.c (ffffffff81104a9f)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
  - kernel/sched/autogroup.c:autogroup_init
```
```
In kernel/sched/cpufreq_schedutil.c (ffffffff8110b05b)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_kthread_create
```
```
In kernel/sched/membarrier.c (ffffffff8110c15f)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/sched/membarrier.c:membarrier_exec_mmap
```
```
In kernel/sched/psi.c (ffffffff8110c967)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_trigger_destroy
  - kernel/sched/psi.c:psi_poll_work
  - kernel/sched/psi.c:group_init
```
```
In kernel/locking/mutex.c (ffffffff8110e024)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/locking/mutex.c:__mutex_init
```
```
In kernel/locking/rwsem.c (ffffffff8110e43c)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:__init_rwsem
```
```
In kernel/locking/percpu-rwsem.c (ffffffff8110f14c)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:__percpu_init_rwsem
```
```
In kernel/power/swap.c (ffffffff8111959e)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:save_image
```
```
In kernel/printk/printk_safe.c (ffffffff82ceff3b)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:printk_safe_init
  - kernel/printk/printk_safe.c:printk_safe_init
```
```
In kernel/irq/manage.c (ffffffff81122f39)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_notifier
```
```
In kernel/rcu/update.c (ffffffff81130075)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_trace_pregp_step
```
```
In kernel/rcu/srcutree.c (ffffffff811324b7)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
```
```
In kernel/rcu/tree.c (ffffffff81134fe1)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_implicit_dynticks_qs
  - kernel/rcu/tree.c:rcu_implicit_dynticks_qs
```
```
In kernel/time/namespace.c (ffffffff81159c0a)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/time/namespace.c:clone_time_ns
```
```
In kernel/futex.c (ffffffff82cf207d)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/futex.c:futex_init
```
```
In kernel/module.c (ffffffff81166bb9)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/module.c:load_module
```
```
In kernel/kexec_core.c (ffffffff8116b242)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_free_reserved_phys_range
  - kernel/kexec_core.c:crash_kexec
```
```
In kernel/cgroup/cgroup.c (ffffffff81170150)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:init_cgroup_root
  - kernel/cgroup/cgroup.c:find_css_set
```
```
In kernel/cgroup/namespace.c (ffffffff81179410)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
```
```
In kernel/utsname.c (ffffffff811832e5)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/utsname.c:clone_uts_ns
```
```
In kernel/user_namespace.c (ffffffff81184825)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In kernel/pid_namespace.c (ffffffff81185007)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/pid_namespace.c:create_pid_namespace
```
```
In kernel/stop_machine.c (ffffffff8118630a)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:stop_machine_cpuslocked
  - kernel/stop_machine.c:stop_machine_cpuslocked
  - kernel/stop_machine.c:stop_two_cpus
  - kernel/stop_machine.c:stop_two_cpus
  - kernel/stop_machine.c:multi_cpu_stop
  - kernel/stop_machine.c:stop_one_cpu
```
```
In kernel/audit_watch.c (ffffffff81191874)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_watch.c:audit_to_watch
```
```
In kernel/audit_tree.c (ffffffff8119298b)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/audit_tree.c:alloc_tree
```
```
In kernel/debug/debug_core.c (ffffffff8119822e)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_tasklet_bpt
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff8119d6ff)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In kernel/hung_task.c (ffffffff811a4075)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/hung_task.c:reset_hung_task_detector
```
```
In kernel/seccomp.c (ffffffff811a7112)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
```
```
In kernel/relay.c (ffffffff811a7bfd)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/relay.c:__relay_reset
  - kernel/relay.c:__relay_reset
```
```
In kernel/trace/ring_buffer.c (ffffffff811b6f92)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
```
```
In kernel/trace/trace.c (ffffffff811bed96)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:tracing_buffers_splice_read
```
```
In kernel/trace/tracing_map.c (ffffffff811c96da)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_create
  - kernel/trace/tracing_map.c:tracing_map_clear
```
```
In kernel/trace/blktrace.c (ffffffff811d081e)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:do_blk_trace_setup
```
```
In kernel/trace/fgraph.c (ffffffff811d2e84)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/trace/fgraph.c:ftrace_graph_init_task
  - kernel/trace/fgraph.c:ftrace_graph_init_task
  - kernel/trace/fgraph.c:ftrace_graph_init_idle_task
  - kernel/trace/fgraph.c:ftrace_graph_init_idle_task
  - kernel/trace/fgraph.c:alloc_retstack_tasklist
  - kernel/trace/fgraph.c:alloc_retstack_tasklist
```
```
In kernel/trace/trace_events.c (ffffffff811d6f60)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_trace_add_tracer
  - kernel/trace/trace_events.c:event_trace_add_tracer
  - kernel/trace/trace_events.c:trace_module_notify
  - kernel/trace/trace_events.c:trace_module_notify
  - kernel/trace/trace_events.c:trace_add_event_call
  - kernel/trace/trace_events.c:trace_add_event_call
```
```
In kernel/trace/bpf_trace.c (ffffffff82cf6c06)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:send_signal_irq_work_init
```
```
In kernel/bpf/ringbuf.c (ffffffff8121e505)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In kernel/bpf/trampoline.c (ffffffff8121ef98)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_lookup
```
```
In kernel/bpf/btf.c (ffffffff81224ada)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_parse_vmlinux
  - kernel/bpf/btf.c:btf_parse
```
```
In kernel/bpf/dispatcher.c (ffffffff8122639a)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/bpf/dispatcher.c:bpf_dispatcher_change_prog
```
```
In kernel/bpf/stackmap.c (ffffffff82cf7bb8)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_init
```
```
In kernel/bpf/bpf_struct_ops.c (ffffffff8122f90f)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_sys_lookup_elem
```
```
In kernel/events/core.c (ffffffff8123a4b5)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:alloc_perf_context
```
```
In kernel/events/ring_buffer.c (ffffffff8124426e)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc
  - kernel/events/ring_buffer.c:rb_alloc_aux
  - kernel/events/ring_buffer.c:perf_aux_output_skip
  - kernel/events/ring_buffer.c:perf_aux_output_end
  - kernel/events/ring_buffer.c:perf_aux_output_begin
  - kernel/events/ring_buffer.c:perf_output_end
```
```
In kernel/events/uprobes.c (ffffffff812483e1)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__create_xol_area
  - kernel/events/uprobes.c:alloc_uprobe
```
```
In kernel/padata.c (ffffffff812499bf)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_alloc_pd
```
```
In kernel/jump_label.c (ffffffff8124ad12)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/jump_label.c:static_key_enable_cpuslocked
  - kernel/jump_label.c:static_key_slow_inc_cpuslocked
```
```
In kernel/watch_queue.c (ffffffff8124d52c)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/watch_queue.c:watch_queue_init
  - kernel/watch_queue.c:init_watch
```
```
In mm/filemap.c (ffffffff812541d6)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/shmem.c (0)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In mm/backing-dev.c (ffffffff81277d73)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_alloc
  - mm/backing-dev.c:wb_congested_get_create
```
```
In mm/rmap.c (ffffffff812a6b03)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - mm/rmap.c:hugepage_add_new_anon_rmap
  - mm/rmap.c:hugepage_add_new_anon_rmap
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:anon_vma_ctor
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:__anon_vma_prepare
```
```
In mm/page_alloc.c (ffffffff812b3c39)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:init_unavailable_range
  - mm/page_alloc.c:init_unavailable_range
  - mm/page_alloc.c:memmap_init_zone_device
  - mm/page_alloc.c:memmap_init_zone_device
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:make_alloc_exact
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:prep_new_page
  - mm/page_alloc.c:check_new_page_bad
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:prep_compound_page
  - mm/page_alloc.c:prep_compound_page
  - mm/page_alloc.c:prep_compound_page
  - mm/page_alloc.c:bad_page
```
```
In mm/swap_state.c (ffffffff812b9dd3)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - mm/swap_state.c:init_swap_address_space
  - mm/swap_state.c:swap_cluster_readahead
```
```
In mm/frontswap.c (ffffffff812c08af)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_invalidate_area
```
```
In mm/zswap.c (ffffffff812c12ea)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - mm/zswap.c:zswap_pool_create
```
```
In mm/hugetlb.c (ffffffff812c3c62)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:update_and_free_page
  - mm/hugetlb.c:destroy_compound_gigantic_page
  - mm/hugetlb.c:destroy_compound_gigantic_page
  - mm/hugetlb.c:destroy_compound_gigantic_page
  - mm/hugetlb.c:dequeue_huge_page_nodemask
  - mm/hugetlb.c:resv_map_alloc
```
```
In mm/mempolicy.c (ffffffff812cd9ab)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - mm/mempolicy.c:shared_policy_replace
  - mm/mempolicy.c:__mpol_dup
  - mm/mempolicy.c:mpol_new
```
```
In mm/memory_hotplug.c (ffffffff812e1651)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - mm/memory_hotplug.c:put_page_bootmem
```
```
In mm/huge_memory.c (ffffffff812e876c)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - mm/huge_memory.c:get_huge_zero_page
```
```
In mm/memcontrol.c (ffffffff812f61f5)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_online
```
```
In mm/zpool.c (ffffffff813041c9)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - mm/zpool.c:zpool_register_driver
```
```
In mm/zsmalloc.c (ffffffff813056bf)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - mm/zsmalloc.c:reset_page
```
```
In mm/page_reporting.c (ffffffff8130cf6b)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - mm/page_reporting.c:page_reporting_register
  - mm/page_reporting.c:page_reporting_process
  - mm/page_reporting.c:page_reporting_cycle
```
```
In fs/super.c (ffffffff81316b5d)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/super.c:alloc_super
```
```
In fs/exec.c (ffffffff8131db9b)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/exec.c:unshare_sighand
```
```
In fs/dcache.c (ffffffff81330a4e)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/dcache.c:__d_alloc
```
```
In fs/inode.c (ffffffff8133482a)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/inode.c:inode_init_always
  - fs/inode.c:inode_init_always
  - fs/inode.c:inode_init_always
  - fs/inode.c:inode_init_always
```
```
In fs/file.c (ffffffff81339160)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/file.c:dup_fd
```
```
In fs/namespace.c (ffffffff8133ab75)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In fs/fsopen.c (ffffffff81358def)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/fsopen.c:__do_sys_fspick
  - fs/fsopen.c:__ia32_sys_fsopen
  - fs/fsopen.c:__x64_sys_fsopen
```
```
In fs/block_dev.c (ffffffff8135fbdd)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_direct_IO
```
```
In fs/notify/group.c (ffffffff81366de4)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_alloc_group
  - fs/notify/group.c:fsnotify_alloc_group
  - fs/notify/group.c:fsnotify_alloc_group
```
```
In fs/notify/mark.c (ffffffff8136724b)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_init_mark
```
```
In fs/eventfd.c (ffffffff813716e7)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/eventfd.c:do_eventfd
```
```
In fs/userfaultfd.c (ffffffff81372099)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/userfaultfd.c:__do_sys_userfaultfd
  - fs/userfaultfd.c:dup_userfaultfd
```
```
In fs/aio.c (ffffffff81378271)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:__ia32_sys_io_destroy
  - fs/aio.c:__x64_sys_io_destroy
  - fs/aio.c:exit_aio
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
```
```
In fs/io_uring.c (ffffffff8137e818)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/io_uring.c:io_init_req
```
```
In fs/io-wq.c (ffffffff8138b513)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/io-wq.c:io_wq_create
  - fs/io-wq.c:io_wq_create
  - fs/io-wq.c:io_wq_create
  - fs/io-wq.c:io_wq_manager
  - fs/io-wq.c:create_io_worker
```
```
In fs/crypto/keyring.c (ffffffff8139208b)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/crypto/keyring.c:add_new_master_key
```
```
In fs/crypto/keysetup_v1.c (ffffffff81394509)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_get_direct_key
```
```
In fs/mbcache.c (ffffffff813a551b)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/posix_acl.c (ffffffff813a5e36)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/posix_acl.c:posix_acl_from_mode
  - fs/posix_acl.c:posix_acl_clone
```
```
In fs/coredump.c (ffffffff813a7cec)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/coredump.c:zap_threads
```
```
In fs/iomap/buffered-io.c (ffffffff813aa6b3)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In fs/iomap/direct-io.c (ffffffff813ad4d0)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_rw
```
```
In fs/quota/dquot.c (ffffffff813ae9fb)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/quota/dquot.c:get_empty_dquot
```
```
In fs/proc/generic.c (ffffffff813c06e5)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/proc/generic.c:__proc_create
```
```
In fs/kernfs/inode.c (ffffffff813cd105)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In fs/kernfs/dir.c (ffffffff813ce43b)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/kernfs/dir.c:__kernfs_new_node
  - fs/kernfs/dir.c:__kernfs_new_node
```
```
In fs/kernfs/file.c (ffffffff813d060a)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_get_open_node
  - fs/kernfs/file.c:kernfs_get_open_node
```
```
In fs/configfs/dir.c (ffffffff813d69ad)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_register_group
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_new_dirent
```
```
In fs/configfs/item.c (ffffffff813d7818)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/configfs/item.c:config_group_init_type_name
  - fs/configfs/item.c:config_item_init_type_name
```
```
In fs/ext4/mballoc.c (ffffffff8140c5d0)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
```
```
In fs/ext4/page-io.c (ffffffff81417a5b)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_init_io_end
```
```
In fs/ext4/super.c (ffffffff81425f69)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_alloc_inode
  - fs/ext4/super.c:ext4_alloc_inode
```
```
In fs/jbd2/transaction.c (ffffffff8143c76d)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_get_transaction
  - fs/jbd2/transaction.c:jbd2_get_transaction
  - fs/jbd2/transaction.c:jbd2_get_transaction
  - fs/jbd2/transaction.c:jbd2_get_transaction
```
```
In fs/jbd2/journal.c (ffffffff814459f3)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_init_common
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/ecryptfs/main.c (ffffffff81462104)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_get_lower_file
```
```
In fs/ecryptfs/super.c (ffffffff8146233f)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/ecryptfs/super.c:ecryptfs_alloc_inode
```
```
In fs/ecryptfs/miscdev.c (ffffffff82d03e95)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/ecryptfs/miscdev.c:ecryptfs_init_ecryptfs_miscdev
```
```
In fs/fuse/dev.c (ffffffff8146e842)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_get_req
```
```
In fs/fuse/file.c (ffffffff8147a2e6)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_file_alloc
```
```
In fs/fuse/inode.c (ffffffff8147d37b)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_conn_init
  - fs/fuse/inode.c:fuse_conn_init
  - fs/fuse/inode.c:fuse_conn_init
```
```
In fs/debugfs/file.c (ffffffff81481c75)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_atomic_t_set
  - fs/debugfs/file.c:debugfs_file_get
```
```
In ipc/util.c (ffffffff81486e75)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In ipc/msg.c (ffffffff82d04333)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - ipc/msg.c:msg_init
  - ipc/msg.c:msg_init
```
```
In ipc/sem.c (ffffffff8148e44d)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - ipc/sem.c:copy_semundo
  - ipc/sem.c:find_alloc_undo
```
```
In ipc/namespace.c (ffffffff81494f13)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In security/keys/key.c (ffffffff81496d6a)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_user_lookup
  - security/keys/key.c:key_user_lookup
  - security/keys/key.c:key_user_lookup
```
```
In security/selinux/avc.c (ffffffff814ae08b)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - security/selinux/avc.c:selinux_avc_init
  - security/selinux/avc.c:selinux_avc_init
```
```
In security/selinux/ss/services.c (ffffffff814cda22)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
```
```
In security/tomoyo/condition.c (ffffffff814e1aec)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_commit_condition
```
```
In security/tomoyo/gc.c (ffffffff814e6903)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - security/tomoyo/gc.c:tomoyo_collect_entry
  - security/tomoyo/gc.c:tomoyo_collect_entry
  - security/tomoyo/gc.c:tomoyo_collect_entry
```
```
In security/tomoyo/memory.c (ffffffff814e744b)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_name
  - security/tomoyo/memory.c:tomoyo_get_group
```
```
In security/apparmor/apparmorfs.c (ffffffff814eef71)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_write_access
```
```
In security/apparmor/lib.c (ffffffff814f210a)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - security/apparmor/lib.c:aa_str_alloc
```
```
In security/apparmor/match.c (ffffffff814f2eb3)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
```
```
In security/apparmor/policy_unpack.c (ffffffff814feb64)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:aa_loaddata_alloc
```
```
In security/apparmor/policy_ns.c (ffffffff815077ab)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:alloc_ns
```
```
In security/apparmor/label.c (ffffffff81509a24)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_alloc
  - security/apparmor/label.c:aa_alloc_proxy
```
```
In crypto/api.c (ffffffff8151ecf8)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - crypto/api.c:crypto_alg_mod_lookup
```
```
In crypto/algapi.c (ffffffff81520b2d)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - crypto/algapi.c:__crypto_register_alg
  - crypto/algapi.c:crypto_check_alg
```
```
In block/bio.c (ffffffff8153f19f)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_reset
```
```
In block/blk-core.c (ffffffff81542795)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - block/blk-core.c:blk_rq_init
```
```
In block/blk-ioc.c (ffffffff81549626)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - block/blk-ioc.c:create_task_io_context
  - block/blk-ioc.c:create_task_io_context
```
```
In block/blk-mq.c (ffffffff81551693)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_hctx
  - block/blk-mq.c:blk_mq_rq_ctx_init
```
```
In block/bsg.c (ffffffff81568c87)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In block/bsg-lib.c (ffffffff8156973d)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_queue_rq
```
```
In block/blk-cgroup.c (ffffffff8156a259)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_css_alloc
```
```
In block/blk-iocost.c (ffffffff81572fb7)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - block/blk-iocost.c:blk_iocost_init
```
```
In block/blk-wbt.c (ffffffff8157ac5a)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_init
```
```
In block/keyslot-manager.c (ffffffff81581476)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - block/keyslot-manager.c:blk_ksm_get_slot_for_key
```
```
In lib/rhashtable.c (ffffffff8158e482)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_init
```
```
In lib/refcount.c (ffffffff8158f770)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In lib/cpu_rmap.c (ffffffff815df473)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - lib/cpu_rmap.c:alloc_cpu_rmap
```
```
In lib/sbitmap.c (ffffffff815e5943)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbq_wake_up
```
```
In lib/dump_stack.c (ffffffff815e8337)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - lib/dump_stack.c:dump_stack
```
```
In lib/klist.c (ffffffff815ea082)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - lib/klist.c:klist_node_init
```
```
In lib/kobject.c (ffffffff815eb7e3)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - lib/kobject.c:kset_create_and_add
  - lib/kobject.c:kobject_create_and_add
```
```
In drivers/pinctrl/core.c (ffffffff8160354a)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:create_pinctrl
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff81652c91)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
```
```
In drivers/rapidio/rio.c (ffffffff8165ce3d)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_register_mport
  - drivers/rapidio/rio.c:rio_mport_initialize
  - drivers/rapidio/rio.c:rio_del_device
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff81666e57)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:do_register_framebuffer
```
```
In drivers/acpi/ec.c (ffffffff8168f3c4)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_add_query_handler
```
```
In drivers/acpi/apei/ghes.c (ffffffff82d152c5)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_init
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_alloc
```
```
In drivers/clk/clk.c (ffffffff81700cf6)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_core_init
```
```
In drivers/dma/dmaengine.c (ffffffff817071d8)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaengine_get_unmap_data
  - drivers/dma/dmaengine.c:dma_async_device_register
```
```
In drivers/xen/balloon.c (ffffffff81713fcb)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/xen/balloon.c:increase_reservation
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff8171f4a4)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_open
```
```
In drivers/reset/core.c (ffffffff81732929)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/reset/core.c:__reset_control_get_internal
```
```
In drivers/tty/tty_io.c (ffffffff8173765b)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:alloc_tty_struct
```
```
In drivers/tty/tty_buffer.c (ffffffff8173f219)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_init
  - drivers/tty/tty_buffer.c:tty_buffer_init
```
```
In drivers/tty/tty_port.c (ffffffff8173f4a2)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_init
```
```
In drivers/tty/serial/serial_core.c (ffffffff8175b0db)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_add_one_port
```
```
In drivers/char/virtio_console.c (ffffffff81776119)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In drivers/char/hw_random/core.c (ffffffff81779235)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:hwrng_init
```
```
In drivers/char/agp/backend.c (ffffffff8177a414)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/char/agp/backend.c:agp_alloc_bridge
  - drivers/char/agp/backend.c:agp_alloc_bridge
```
```
In drivers/iommu/iova.c (ffffffff81794464)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/iommu/iova.c:fq_flush_timeout
  - drivers/iommu/iova.c:init_iova_flush_queue
```
```
In drivers/connector/cn_queue.c (ffffffff817acc5a)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/connector/cn_queue.c:cn_queue_alloc_dev
  - drivers/connector/cn_queue.c:cn_queue_alloc_callback_entry
```
```
In drivers/lightnvm/core.c (ffffffff817ae5a6)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_alloc_dev
```
```
In drivers/base/core.c (ffffffff817b53b5)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/power/runtime.c (ffffffff817c9cb5)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_init
  - drivers/base/power/runtime.c:pm_runtime_init
```
```
In drivers/base/power/wakeup.c (ffffffff817cf5c8)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:pm_wakeup_clear
```
```
In drivers/base/power/domain.c (ffffffff817d1d4a)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/base/power/domain.c:pm_genpd_init
```
```
In drivers/base/firmware_loader/main.c (ffffffff817d4f29)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In drivers/block/loop.c (ffffffff817e7a0d)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_add
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In drivers/nvdimm/core.c (ffffffff8180ec51)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:alloc_nvdimm_map
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff8181201c)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:__nvdimm_create
```
```
In drivers/nvdimm/dimm.c (ffffffff81812f66)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In drivers/dax/bus.c (ffffffff81824240)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/dax/bus.c:alloc_dax_region
```
```
In drivers/dma-buf/dma-fence.c (ffffffff8182703b)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_init
```
```
In drivers/dma-buf/dma-fence-array.c (ffffffff81827553)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_create
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_create
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffff818278e6)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_init
```
```
In drivers/dma-buf/sw_sync.c (ffffffff8182b99e)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_timeline_create
```
```
In drivers/scsi/scsi.c (ffffffff8182e948)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_finish_command
  - drivers/scsi/scsi.c:scsi_finish_command
  - drivers/scsi/scsi.c:scsi_finish_command
```
```
In drivers/scsi/scsi_lib.c (ffffffff8183809b)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:__scsi_queue_insert
  - drivers/scsi/scsi_lib.c:__scsi_queue_insert
  - drivers/scsi/scsi_lib.c:__scsi_queue_insert
```
```
In drivers/scsi/scsi_scan.c (ffffffff818397a3)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
```
```
In drivers/scsi/sd.c (ffffffff81847dd3)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
```
```
In drivers/scsi/sr.c (ffffffff8184acea)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_probe
```
```
In drivers/scsi/sg.c (ffffffff8184ed39)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_add_sfp
  - drivers/scsi/sg.c:sg_alloc
  - drivers/scsi/sg.c:sg_alloc
```
```
In drivers/ata/libata-core.c (ffffffff818524a4)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_init
  - drivers/ata/libata-core.c:ata_host_alloc
```
```
In drivers/net/phy/phy_device.c (ffffffff8188491d)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_package_join
```
```
In drivers/net/phy/sfp-bus.c (ffffffff818889d4)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_bus_get
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81892460)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
```
```
In drivers/vfio/vfio.c (ffffffff8189b6b0)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_fops_open
  - drivers/vfio/vfio.c:vfio_add_group_dev
  - drivers/vfio/vfio.c:vfio_create_group
  - drivers/vfio/vfio.c:vfio_create_group
  - drivers/vfio/vfio.c:vfio_create_group
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff818a3cf0)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_reflck_attach
```
```
In drivers/usb/core/usb.c (ffffffff818b2084)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/usb/core/usb.c:usb_alloc_dev
```
```
In drivers/usb/core/hub.c (ffffffff818bb661)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_probe
```
```
In drivers/usb/core/hcd.c (ffffffff818bc4e4)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:__usb_create_hcd
```
```
In drivers/usb/core/urb.c (ffffffff818c0650)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_alloc_urb
```
```
In drivers/usb/core/config.c (ffffffff818c6e46)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_configuration
```
```
In drivers/usb/core/file.c (ffffffff818c84d8)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/usb/core/file.c:init_usb_class
```
```
In drivers/thermal/thermal_core.c (ffffffff81956a8a)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
```
```
In drivers/md/md.c (ffffffff819704d4)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_run
  - drivers/md/md.c:max_corrected_read_errors_store
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:errors_store
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:mddev_init
  - drivers/md/md.c:mddev_init
  - drivers/md/md.c:mddev_init
  - drivers/md/md.c:mddev_init
  - drivers/md/md.c:submit_flushes
```
```
In drivers/md/md-bitmap.c (ffffffff81975ca2)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
```
```
In drivers/md/dm.c (ffffffff8197a2ec)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:dm_get_table_device
  - drivers/md/dm.c:alloc_io
```
```
In drivers/md/dm-table.c (ffffffff8197c8d2)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_get_device
```
```
In drivers/md/dm-stripe.c (ffffffff8197f9e6)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:stripe_ctr
```
```
In drivers/md/dm-io.c (ffffffff81983633)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/md/dm-io.c:dm_io
  - drivers/md/dm-io.c:sync_io
```
```
In drivers/md/dm-kcopyd.c (ffffffff81983fdd)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
  - drivers/md/dm-kcopyd.c:dm_kcopyd_copy
```
```
In drivers/md/dm-stats.c (ffffffff81986222)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In drivers/edac/ghes_edac.c (ffffffff8198d645)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/edac/ghes_edac.c:ghes_edac_register
```
```
In drivers/opp/core.c (ffffffff81990b4c)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/opp/core.c:_opp_add
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff81999723)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_stop
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
  - drivers/cpufreq/cpufreq_governor.c:dbs_update_util_handler
  - drivers/cpufreq/cpufreq_governor.c:dbs_work_handler
```
```
In drivers/mmc/core/sdio_irq.c (ffffffff819b5d1e)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In drivers/firmware/efi/efi.c (ffffffff81bc32e0)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff819ca95a)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
```
```
In drivers/devfreq/devfreq.c (ffffffff819d046c)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
```
In drivers/nvmem/core.c (ffffffff819db043)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/nvmem/core.c:nvmem_register
```
```
In net/core/sock.c (ffffffff819e3f26)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_alloc
```
```
In net/core/skbuff.c (ffffffff819f4352)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_ext_add
  - net/core/skbuff.c:__skb_ext_alloc
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:pskb_carve_inside_header
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:sock_zerocopy_realloc
  - net/core/skbuff.c:sock_zerocopy_alloc
  - net/core/skbuff.c:skb_morph
  - net/core/skbuff.c:__build_skb_around
  - net/core/skbuff.c:__build_skb_around
  - net/core/skbuff.c:__alloc_skb
  - net/core/skbuff.c:__alloc_skb
  - net/core/skbuff.c:__alloc_skb
```
```
In net/core/net_namespace.c (ffffffff819f9f25)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/core/net_namespace.c:copy_net_ns
  - net/core/net_namespace.c:copy_net_ns
  - net/core/net_namespace.c:setup_net
  - net/core/net_namespace.c:setup_net
```
```
In net/core/dev.c (ffffffff81a048ea)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/core/dev.c:__dev_kfree_skb_irq
```
```
In net/core/dst.c (ffffffff81a10d05)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/core/dst.c:__metadata_dst_init
  - net/core/dst.c:dst_cow_metrics_generic
  - net/core/dst.c:dst_alloc
```
```
In net/core/neighbour.c (ffffffff81a1315b)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:neigh_alloc
```
```
In net/core/filter.c (ffffffff81a3223f)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/core/filter.c:__sk_attach_prog
```
```
In net/core/flow_offload.c (ffffffff81a36d7c)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/core/flow_offload.c:flow_indr_dev_register
```
```
In net/core/page_pool.c (ffffffff81a3a4c5)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_init
  - net/core/page_pool.c:page_pool_init
```
```
In net/core/skmsg.c (ffffffff81a3cb49)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_init
```
```
In net/core/netpoll.c (ffffffff81a3e236)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/core/netpoll.c:__netpoll_setup
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:zap_completion_queue
```
```
In net/core/fib_rules.c (ffffffff81a4029e)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_default_rule_add
```
```
In net/core/devlink.c (ffffffff81a543bc)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_health_reporter_create
```
```
In net/sched/sch_generic.c (ffffffff81a65ed4)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_alloc
```
```
In net/sched/cls_api.c (ffffffff81a6c6ae)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_create
  - net/sched/cls_api.c:tcf_proto_create
```
```
In net/sched/act_api.c (ffffffff81a728f0)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_idr_create
  - net/sched/act_api.c:tcf_idr_create
```
```
In net/ipv4/route.c (ffffffff81a90d45)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_genid_init
  - net/ipv4/route.c:rt_genid_init
  - net/ipv4/route.c:rt_genid_init
```
```
In net/ipv4/inetpeer.c (ffffffff81a9774e)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81aa4a3c)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81aa53a5)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_hash_add
```
```
In net/ipv4/tcp.c (ffffffff81aa7a38)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv4/tcp.c:skb_entail
```
```
In net/ipv4/tcp_input.c (ffffffff81ab0b3e)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/tcp_output.c (ffffffff81abae0d)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_queue_skb
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tso_fragment
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ac4def)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81acdac1)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_create_child
```
```
In net/ipv4/devinet.c (ffffffff81ae0d6e)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_init
```
```
In net/ipv4/igmp.c (ffffffff81ae7809)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv4/igmp.c:____ip_mc_inc_group
```
```
In net/ipv4/fib_semantics.c (ffffffff81aef62d)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_rebalance
```
```
In net/ipv4/inet_fragment.c (ffffffff81af6250)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frags_init
```
```
In net/ipv4/metrics.c (ffffffff81afa822)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In net/ipv4/nexthop.c (ffffffff81afd575)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_add
  - net/ipv4/nexthop.c:nh_group_rebalance
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81afda7f)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:proc_tfo_blackhole_detect_timeout
```
```
In net/ipv4/ipmr.c (ffffffff81b038ee)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv4/syncookies.c (ffffffff81b0711d)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:tcp_get_cookie_sock
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81b0af73)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b0dfa2)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
```
```
In net/xfrm/xfrm_state.c (ffffffff81b16b7f)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
```
```
In net/unix/af_unix.c (ffffffff81b25db7)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_autobind
```
```
In net/ipv6/af_inet6.c (ffffffff81b2aa01)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_net_init
```
```
In net/ipv6/anycast.c (ffffffff81b2b78f)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
```
```
In net/ipv6/addrconf.c (ffffffff81b36cbe)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_dev
```
```
In net/ipv6/route.c (ffffffff81b42100)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In net/ipv6/ip6_fib.c (ffffffff81b4e61a)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_info_alloc
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81b523fa)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In net/ipv6/mcast.c (ffffffff81b609e8)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mca_alloc
```
```
In net/ipv6/exthdrs.c (ffffffff81b6dbf6)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_dup_options
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81b70472)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:fl_create
```
```
In net/ipv6/ip6mr.c (ffffffff81b766e5)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/ipv6/calipso.c (ffffffff81b7dbae)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_doi_add
```
```
In net/packet/af_packet.c (ffffffff81b8a4cf)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/packet/af_packet.c:fanout_add
  - net/packet/af_packet.c:fanout_add
  - net/packet/af_packet.c:fanout_add
```
```
In net/xdp/xdp_umem.c (ffffffff81ba84a7)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_reg
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
In arch/x86/kernel/ioport.c (ffffffff810382df)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
  - arch/x86/kernel/ioport.c:ksys_ioperm
```
```
In arch/x86/kernel/tboot.c (ffffffff82fbf6cc)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/cpu/aperfmperf.c (ffffffff8104bfca)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_get_on_cpu
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff810501fc)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:fake_panic_set
  - arch/x86/kernel/cpu/mce/core.c:fake_panic_set
  - arch/x86/kernel/cpu/mce/core.c:fake_panic_set
  - arch/x86/kernel/cpu/mce/core.c:fake_panic_set
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:mce_start
  - arch/x86/kernel/cpu/mce/core.c:mce_start
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff810554a4)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:threshold_create_bank
```
```
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff81056c15)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff8105a2bd)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:reload_store
  - arch/x86/kernel/cpu/microcode/core.c:reload_store
```
```
In arch/x86/kernel/cpu/sgx/driver.c (ffffffff810656bb)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/driver.c:sgx_open
```
```
In arch/x86/kernel/reboot.c (ffffffff8106ab27)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff8106dab9)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_target
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
```
```
In arch/x86/kernel/kgdb.c (ffffffff8107c07f)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/kgdb.c:kgdb_arch_handle_exception
  - arch/x86/kernel/kgdb.c:kgdb_arch_handle_exception
```
```
In arch/x86/mm/init_64.c (ffffffff81c3c98d)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pagetable
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff82fd905b)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_common
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus
```
```
In kernel/fork.c (ffffffff810a038b)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/fork.c:copy_signal
  - kernel/fork.c:copy_signal
  - kernel/fork.c:copy_sighand
  - kernel/fork.c:mm_init
  - kernel/fork.c:mm_init
  - kernel/fork.c:mm_init
  - kernel/fork.c:mm_init
  - kernel/fork.c:dup_task_struct
  - kernel/fork.c:dup_task_struct
  - kernel/fork.c:dup_task_struct
```
```
In kernel/softirq.c (ffffffff810aa215)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/softirq.c:tasklet_init
  - kernel/softirq.c:tasklet_setup
```
```
In kernel/user.c (ffffffff810b22ee)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/user.c:alloc_uid
```
```
In kernel/workqueue.c (ffffffff810c32f0)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/workqueue.c:unbind_workers
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:flush_workqueue_prep_pwqs
```
```
In kernel/pid.c (ffffffff810c8a51)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/pid.c:alloc_pid
```
```
In kernel/nsproxy.c (ffffffff810d0581)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/nsproxy.c:create_new_namespaces
```
```
In kernel/cred.c (ffffffff810d29c8)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:cred_alloc_blank
```
```
In kernel/smpboot.c (ffffffff810d4acc)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/smpboot.c:cpu_wait_death
  - kernel/smpboot.c:cpu_check_up_prepare
```
```
In kernel/groups.c (ffffffff810d5a58)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/groups.c:groups_alloc
```
```
In kernel/sched/core.c (ffffffff82fdb11d)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:affine_move_task
```
```
In kernel/sched/fair.c (ffffffff810ed1b1)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_group
```
```
In kernel/sched/cpupri.c (ffffffff810fe6a7)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_init
```
```
In kernel/sched/topology.c (ffffffff810ff96f)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/sched/topology.c:sd_init
  - kernel/sched/topology.c:init_defrootdomain
```
```
In kernel/sched/autogroup.c (ffffffff8110311f)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
  - kernel/sched/autogroup.c:autogroup_init
```
```
In kernel/sched/membarrier.c (ffffffff8110933f)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/sched/membarrier.c:membarrier_exec_mmap
```
```
In kernel/sched/psi.c (ffffffff811098f5)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/sched/psi.c:poll_timer_fn
```
```
In kernel/locking/mutex.c (ffffffff8110b2e4)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/locking/mutex.c:__mutex_init
```
```
In kernel/locking/rwsem.c (ffffffff8110b6fc)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:__init_rwsem
```
```
In kernel/locking/percpu-rwsem.c (ffffffff8110c30c)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:__percpu_init_rwsem
```
```
In kernel/power/swap.c (ffffffff81114dde)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:save_image
```
```
In kernel/irq/manage.c (ffffffff8111ef29)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_notifier
```
```
In kernel/rcu/update.c (ffffffff8112beb5)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_trace_pregp_step
```
```
In kernel/rcu/srcutree.c (ffffffff8112dca7)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
```
```
In kernel/rcu/tree.c (ffffffff8112f7b2)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/rcu/tree.c:fill_page_cache_func
```
```
In kernel/time/namespace.c (ffffffff81155c1a)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/time/namespace.c:clone_time_ns
```
```
In kernel/futex.c (ffffffff82fdeb52)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/futex.c:futex_init
```
```
In kernel/module.c (ffffffff8116334d)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/module.c:load_module
```
```
In kernel/kexec_core.c (ffffffff81167982)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_free_reserved_phys_range
  - kernel/kexec_core.c:crash_kexec
```
```
In kernel/cgroup/cgroup.c (ffffffff8116cc8f)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:init_cgroup_root
  - kernel/cgroup/cgroup.c:find_css_set
```
```
In kernel/cgroup/namespace.c (ffffffff81176123)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
```
```
In kernel/utsname.c (ffffffff811801d5)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/utsname.c:clone_uts_ns
```
```
In kernel/user_namespace.c (ffffffff81181875)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In kernel/pid_namespace.c (ffffffff81182173)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/pid_namespace.c:create_pid_namespace
```
```
In kernel/stop_machine.c (ffffffff8118349a)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:stop_machine_cpuslocked
  - kernel/stop_machine.c:stop_machine_cpuslocked
  - kernel/stop_machine.c:stop_two_cpus
  - kernel/stop_machine.c:stop_two_cpus
  - kernel/stop_machine.c:multi_cpu_stop
  - kernel/stop_machine.c:stop_one_cpu
```
```
In kernel/audit_watch.c (ffffffff8118ea24)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_watch.c:audit_to_watch
```
```
In kernel/audit_tree.c (ffffffff8118fadb)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/audit_tree.c:alloc_tree
```
```
In kernel/kprobes.c (ffffffff81194be9)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
```
```
In kernel/debug/debug_core.c (ffffffff8119546e)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_tasklet_bpt
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff8119a73f)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
```
```
In kernel/hung_task.c (ffffffff811a11d5)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/hung_task.c:reset_hung_task_detector
```
```
In kernel/seccomp.c (ffffffff811a47fd)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_attach_filter
```
```
In kernel/relay.c (ffffffff811a5fed)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/relay.c:__relay_reset
```
```
In kernel/trace/trace.c (ffffffff811b9cfc)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
```
```
In kernel/trace/tracing_map.c (ffffffff811c6d9a)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_create
  - kernel/trace/tracing_map.c:tracing_map_clear
```
```
In kernel/trace/blktrace.c (ffffffff811cdc40)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:do_blk_trace_setup
```
```
In kernel/trace/fgraph.c (ffffffff811cffe4)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/trace/fgraph.c:ftrace_graph_init_task
  - kernel/trace/fgraph.c:ftrace_graph_init_idle_task
  - kernel/trace/fgraph.c:alloc_retstack_tasklist
```
```
In kernel/trace/trace_events.c (ffffffff811d4409)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_trace_add_tracer
  - kernel/trace/trace_events.c:event_trace_add_tracer
  - kernel/trace/trace_events.c:__trace_early_add_events
  - kernel/trace/trace_events.c:__trace_early_add_events
  - kernel/trace/trace_events.c:trace_module_notify
  - kernel/trace/trace_events.c:trace_module_notify
  - kernel/trace/trace_events.c:trace_add_event_call
  - kernel/trace/trace_events.c:trace_add_event_call
```
```
In kernel/irq_work.c (ffffffff811f6077)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_single
```
```
In kernel/bpf/trampoline.c (ffffffff812225ee)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_lookup
```
```
In kernel/bpf/btf.c (ffffffff81224153)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_parse_module
  - kernel/bpf/btf.c:btf_parse_vmlinux
  - kernel/bpf/btf.c:btf_parse
```
```
In kernel/bpf/dispatcher.c (ffffffff8122cf8a)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/bpf/dispatcher.c:bpf_dispatcher_change_prog
```
```
In kernel/bpf/bpf_struct_ops.c (ffffffff81237e0a)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_sys_lookup_elem
```
```
In kernel/events/core.c (ffffffff8123e0d7)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:alloc_perf_context
```
```
In kernel/events/ring_buffer.c (ffffffff8124e90f)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc
  - kernel/events/ring_buffer.c:rb_alloc_aux
  - kernel/events/ring_buffer.c:perf_aux_output_skip
  - kernel/events/ring_buffer.c:perf_aux_output_end
  - kernel/events/ring_buffer.c:perf_aux_output_begin
  - kernel/events/ring_buffer.c:perf_output_end
```
```
In kernel/events/uprobes.c (ffffffff81252af1)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__create_xol_area
  - kernel/events/uprobes.c:alloc_uprobe
```
```
In kernel/padata.c (ffffffff81253c1b)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/padata.c:padata_alloc_pd
```
```
In kernel/jump_label.c (ffffffff81255102)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/jump_label.c:static_key_enable_cpuslocked
  - kernel/jump_label.c:static_key_slow_inc_cpuslocked
```
```
In kernel/watch_queue.c (ffffffff8125799c)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/watch_queue.c:watch_queue_init
  - kernel/watch_queue.c:init_watch
```
```
In mm/filemap.c (ffffffff81be6a76)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/shmem.c (0)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
```
```
In mm/backing-dev.c (ffffffff81282387)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_alloc
```
```
In mm/gup.c (ffffffff81293a76)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - mm/gup.c:pin_user_pages_locked
  - mm/gup.c:pin_user_pages
  - mm/gup.c:internal_get_user_pages_fast
  - mm/gup.c:internal_get_user_pages_fast
  - mm/gup.c:get_user_pages_unlocked
  - mm/gup.c:get_user_pages
  - mm/gup.c:__get_user_pages_remote
  - mm/gup.c:__get_user_pages_remote
```
```
In mm/rmap.c (ffffffff812b1fa3)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - mm/rmap.c:hugepage_add_new_anon_rmap
  - mm/rmap.c:hugepage_add_new_anon_rmap
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:anon_vma_ctor
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:__anon_vma_prepare
```
```
In mm/page_alloc.c (ffffffff812bf6ed)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:make_alloc_exact
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:check_new_page_bad
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:prep_compound_page
  - mm/page_alloc.c:prep_compound_page
  - mm/page_alloc.c:prep_compound_page
  - mm/page_alloc.c:bad_page
```
```
In mm/swap_state.c (ffffffff812c5843)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - mm/swap_state.c:init_swap_address_space
  - mm/swap_state.c:swap_cluster_readahead
```
```
In mm/frontswap.c (ffffffff812cc2cf)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_invalidate_area
```
```
In mm/zswap.c (ffffffff812cce0a)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - mm/zswap.c:zswap_pool_create
```
```
In mm/hugetlb.c (ffffffff812cf8a8)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:update_and_free_page
  - mm/hugetlb.c:update_and_free_page
  - mm/hugetlb.c:update_and_free_page
  - mm/hugetlb.c:update_and_free_page
  - mm/hugetlb.c:dequeue_huge_page_nodemask
  - mm/hugetlb.c:resv_map_alloc
```
```
In mm/mempolicy.c (ffffffff812d88db)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - mm/mempolicy.c:shared_policy_replace
  - mm/mempolicy.c:__mpol_dup
  - mm/mempolicy.c:mpol_new
```
```
In mm/memory_hotplug.c (ffffffff812ec5a1)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - mm/memory_hotplug.c:put_page_bootmem
```
```
In mm/huge_memory.c (ffffffff812f3a7c)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - mm/huge_memory.c:get_huge_zero_page
```
```
In mm/memcontrol.c (ffffffff81301fc5)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_online
```
```
In mm/zpool.c (ffffffff8130ff89)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - mm/zpool.c:zpool_register_driver
```
```
In mm/zsmalloc.c (ffffffff8131141f)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - mm/zsmalloc.c:reset_page
```
```
In mm/page_reporting.c (ffffffff81318ebb)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - mm/page_reporting.c:page_reporting_register
  - mm/page_reporting.c:page_reporting_process
  - mm/page_reporting.c:page_reporting_cycle
```
```
In fs/super.c (ffffffff81322041)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/super.c:alloc_super
```
```
In fs/exec.c (ffffffff813289fb)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/exec.c:unshare_sighand
```
```
In fs/dcache.c (ffffffff8133c3be)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/dcache.c:__d_alloc
```
```
In fs/inode.c (ffffffff8134017f)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/inode.c:inode_init_always
  - fs/inode.c:inode_init_always
  - fs/inode.c:inode_init_always
  - fs/inode.c:inode_init_always
```
```
In fs/file.c (ffffffff81344dd2)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/file.c:dup_fd
```
```
In fs/namespace.c (ffffffff81346d85)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In fs/fsopen.c (ffffffff8136576f)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/fsopen.c:__do_sys_fspick
  - fs/fsopen.c:__ia32_sys_fsopen
  - fs/fsopen.c:__x64_sys_fsopen
```
```
In fs/block_dev.c (ffffffff8136d459)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_direct_IO
```
```
In fs/notify/group.c (ffffffff81374134)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_alloc_group
  - fs/notify/group.c:fsnotify_alloc_group
  - fs/notify/group.c:fsnotify_alloc_group
```
```
In fs/notify/mark.c (ffffffff813745ab)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_init_mark
```
```
In fs/eventfd.c (ffffffff8137f4a7)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/eventfd.c:do_eventfd
```
```
In fs/userfaultfd.c (ffffffff8137fedc)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/userfaultfd.c:__do_sys_userfaultfd
  - fs/userfaultfd.c:dup_userfaultfd
```
```
In fs/aio.c (ffffffff81385f76)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:__ia32_sys_io_destroy
  - fs/aio.c:__x64_sys_io_destroy
  - fs/aio.c:exit_aio
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
```
```
In fs/io_uring.c (ffffffff81393f78)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/io_uring.c:io_sq_offload_create
  - fs/io_uring.c:io_uring_alloc_task_context
  - fs/io_uring.c:io_init_req
  - fs/io_uring.c:io_timeout_fn
  - fs/io_uring.c:io_flush_timeouts
  - fs/io_uring.c:io_kill_timeouts
  - fs/io_uring.c:io_init_identity
```
```
In fs/io-wq.c (ffffffff8139c6f9)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/io-wq.c:io_wq_create
  - fs/io-wq.c:io_wq_create
  - fs/io-wq.c:io_wq_create
  - fs/io-wq.c:io_wq_manager
  - fs/io-wq.c:create_io_worker
```
```
In fs/crypto/keyring.c (ffffffff813a3407)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/crypto/keyring.c:add_new_master_key
```
```
In fs/crypto/keysetup_v1.c (ffffffff813a59f7)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_get_direct_key
```
```
In fs/mbcache.c (ffffffff813b627b)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/posix_acl.c (ffffffff813b6b86)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/posix_acl.c:posix_acl_from_mode
  - fs/posix_acl.c:posix_acl_clone
```
```
In fs/coredump.c (ffffffff813b8b79)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/coredump.c:zap_threads
```
```
In fs/iomap/direct-io.c (ffffffff813bea82)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:__iomap_dio_rw
```
```
In fs/quota/dquot.c (ffffffff813bffeb)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/quota/dquot.c:get_empty_dquot
```
```
In fs/proc/generic.c (ffffffff813d2535)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/proc/generic.c:__proc_create
```
```
In fs/kernfs/inode.c (ffffffff813ded35)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
```
```
In fs/kernfs/dir.c (ffffffff813e006b)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/kernfs/dir.c:__kernfs_new_node
  - fs/kernfs/dir.c:__kernfs_new_node
```
```
In fs/kernfs/file.c (ffffffff813e21da)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_get_open_node
  - fs/kernfs/file.c:kernfs_get_open_node
```
```
In fs/configfs/dir.c (ffffffff813e867d)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_register_group
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_new_dirent
```
```
In fs/configfs/item.c (ffffffff813e94b8)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/configfs/item.c:config_group_init_type_name
  - fs/configfs/item.c:config_item_init_type_name
```
```
In fs/ext4/mballoc.c (ffffffff8141fa3f)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
```
```
In fs/ext4/page-io.c (ffffffff8142b55b)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_init_io_end
```
```
In fs/ext4/super.c (ffffffff8144c629)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_alloc_inode
  - fs/ext4/super.c:ext4_alloc_inode
```
```
In fs/ext4/fast_commit.c (ffffffff81456732)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_init_inode
```
```
In fs/jbd2/transaction.c (ffffffff81458b4d)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_get_transaction
  - fs/jbd2/transaction.c:jbd2_get_transaction
  - fs/jbd2/transaction.c:jbd2_get_transaction
  - fs/jbd2/transaction.c:jbd2_get_transaction
```
```
In fs/jbd2/journal.c (ffffffff81463b4d)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_init_common
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/ecryptfs/main.c (ffffffff81bee37a)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_get_lower_file
```
```
In fs/ecryptfs/super.c (ffffffff8147dc8f)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/ecryptfs/super.c:ecryptfs_alloc_inode
```
```
In fs/ecryptfs/miscdev.c (ffffffff82ff11e1)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/ecryptfs/miscdev.c:ecryptfs_init_ecryptfs_miscdev
```
```
In fs/fuse/dev.c (ffffffff81488fc2)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_get_req
```
```
In fs/fuse/file.c (ffffffff81494fe0)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_file_alloc
```
```
In fs/fuse/inode.c (ffffffff8149872a)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_conn_init
  - fs/fuse/inode.c:fuse_conn_init
  - fs/fuse/inode.c:fuse_conn_init
```
```
In fs/fuse/dax.c (ffffffff8149cab7)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
```
```
In fs/debugfs/file.c (ffffffff8149f385)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_atomic_t_set
  - fs/debugfs/file.c:debugfs_file_get
```
```
In ipc/util.c (ffffffff814a4495)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In ipc/msg.c (ffffffff82ff1700)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - ipc/msg.c:msg_init
  - ipc/msg.c:msg_init
```
```
In ipc/sem.c (ffffffff814abb8d)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - ipc/sem.c:copy_semundo
  - ipc/sem.c:find_alloc_undo
```
```
In ipc/namespace.c (ffffffff814b28a3)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
```
```
In security/keys/key.c (ffffffff814b47da)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_user_lookup
  - security/keys/key.c:key_user_lookup
  - security/keys/key.c:key_user_lookup
```
```
In security/selinux/avc.c (ffffffff814cbb1b)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - security/selinux/avc.c:selinux_avc_init
  - security/selinux/avc.c:selinux_avc_init
```
```
In security/selinux/ss/services.c (ffffffff814eb088)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
```
```
In security/smack/smack_access.c (ffffffff814f4a1e)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - security/smack/smack_access.c:smack_populate_secattr
```
```
In security/tomoyo/condition.c (ffffffff814fee6c)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_commit_condition
```
```
In security/tomoyo/gc.c (ffffffff81503d03)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - security/tomoyo/gc.c:tomoyo_collect_entry
  - security/tomoyo/gc.c:tomoyo_collect_entry
  - security/tomoyo/gc.c:tomoyo_collect_entry
```
```
In security/tomoyo/memory.c (ffffffff8150481b)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_name
  - security/tomoyo/memory.c:tomoyo_get_group
```
```
In security/apparmor/apparmorfs.c (ffffffff8150c3f1)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_write_access
```
```
In security/apparmor/lib.c (ffffffff8150f30a)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - security/apparmor/lib.c:aa_str_alloc
```
```
In security/apparmor/match.c (ffffffff81510083)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
```
```
In security/apparmor/policy_unpack.c (ffffffff8151bdc4)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:aa_loaddata_alloc
```
```
In security/apparmor/policy_ns.c (ffffffff8152484b)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:alloc_ns
```
```
In security/apparmor/label.c (ffffffff81526894)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_alloc
  - security/apparmor/label.c:aa_alloc_proxy
```
```
In crypto/api.c (ffffffff8153bb48)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - crypto/api.c:crypto_alg_mod_lookup
```
```
In crypto/algapi.c (ffffffff8153d9bd)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - crypto/algapi.c:__crypto_register_alg
  - crypto/algapi.c:crypto_check_alg
```
```
In block/bio.c (ffffffff8155b997)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_reset
```
```
In block/blk-core.c (ffffffff8155f13d)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - block/blk-core.c:blk_alloc_queue
  - block/blk-core.c:blk_rq_init
```
```
In block/blk-ioc.c (ffffffff81565456)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - block/blk-ioc.c:create_task_io_context
  - block/blk-ioc.c:create_task_io_context
```
```
In block/blk-mq.c (ffffffff8157084a)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_tag_set
  - block/blk-mq.c:blk_mq_alloc_hctx
  - block/blk-mq.c:blk_mq_alloc_hctx
  - block/blk-mq.c:blk_mq_rq_ctx_init
```
```
In block/bsg.c (ffffffff815835b7)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
```
```
In block/bsg-lib.c (ffffffff81583e8d)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_queue_rq
```
```
In block/blk-cgroup.c (ffffffff81584ca9)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_css_alloc
```
```
In block/blk-iocost.c (ffffffff8158f92a)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - block/blk-iocost.c:blk_iocost_init
```
```
In block/blk-wbt.c (ffffffff81597d2c)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_init
```
```
In block/keyslot-manager.c (ffffffff8159e4a6)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - block/keyslot-manager.c:blk_ksm_get_slot_for_key
```
```
In lib/rhashtable.c (ffffffff815aaff2)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_init
```
```
In lib/refcount.c (ffffffff815ac2a0)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
```
```
In lib/cpu_rmap.c (ffffffff815fcc13)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - lib/cpu_rmap.c:alloc_cpu_rmap
```
```
In lib/sbitmap.c (ffffffff81609d03)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbq_wake_up
```
```
In lib/dump_stack.c (ffffffff81bf4a37)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - lib/dump_stack.c:dump_stack
```
```
In lib/klist.c (ffffffff8160e9c2)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - lib/klist.c:klist_node_init
```
```
In lib/kobject.c (ffffffff81610103)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - lib/kobject.c:kset_create_and_add
  - lib/kobject.c:kobject_create_and_add
```
```
In drivers/pinctrl/core.c (ffffffff8162845a)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:create_pinctrl
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff8163b112)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:linereq_create
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff81675651)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
```
```
In drivers/rapidio/rio.c (ffffffff8167e31d)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_register_mport
  - drivers/rapidio/rio.c:rio_mport_initialize
  - drivers/rapidio/rio.c:rio_del_device
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff81687a37)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:do_register_framebuffer
```
```
In drivers/acpi/ec.c (ffffffff816ad094)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_add_query_handler
```
```
In drivers/acpi/thermal.c (ffffffff81704e83)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/acpi/thermal.c:acpi_thermal_add
```
```
In drivers/acpi/apei/ghes.c (ffffffff8170e77f)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_alloc
```
```
In drivers/clk/clk.c (ffffffff8171e216)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_core_init
```
```
In drivers/dma/dmaengine.c (ffffffff81724617)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaengine_get_unmap_data
  - drivers/dma/dmaengine.c:dma_async_device_register
```
```
In drivers/xen/balloon.c (ffffffff81730f9b)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/xen/balloon.c:increase_reservation
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff8173c404)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_open
```
```
In drivers/reset/core.c (ffffffff8174eae9)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/reset/core.c:__reset_control_get_internal
```
```
In drivers/tty/tty_io.c (ffffffff81753a1b)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:alloc_tty_struct
```
```
In drivers/tty/tty_buffer.c (ffffffff8175b149)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_init
  - drivers/tty/tty_buffer.c:tty_buffer_init
```
```
In drivers/tty/tty_port.c (ffffffff8175b3d2)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_init
```
```
In drivers/tty/serial/serial_core.c (ffffffff817761bb)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_add_one_port
```
```
In drivers/char/virtio_console.c (ffffffff81790e49)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
```
```
In drivers/char/hw_random/core.c (ffffffff81793a41)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:hwrng_init
```
```
In drivers/char/agp/backend.c (ffffffff81794ac4)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/char/agp/backend.c:agp_alloc_bridge
  - drivers/char/agp/backend.c:agp_alloc_bridge
```
```
In drivers/iommu/ioasid.c (ffffffff817bfb92)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/iommu/ioasid.c:ioasid_alloc
```
```
In drivers/iommu/iova.c (ffffffff817c0ef4)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/iommu/iova.c:fq_flush_timeout
  - drivers/iommu/iova.c:init_iova_flush_queue
```
```
In drivers/connector/cn_queue.c (ffffffff817c182a)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/connector/cn_queue.c:cn_queue_alloc_dev
  - drivers/connector/cn_queue.c:cn_queue_alloc_callback_entry
```
```
In drivers/lightnvm/core.c (ffffffff817c3136)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_alloc_dev
```
```
In drivers/base/core.c (ffffffff817c9ab3)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/power/runtime.c (ffffffff817de7a5)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_init
  - drivers/base/power/runtime.c:pm_runtime_init
```
```
In drivers/base/power/wakeup.c (ffffffff817e3bc8)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:pm_wakeup_clear
```
```
In drivers/base/power/domain.c (ffffffff817e62bc)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/base/power/domain.c:pm_genpd_init
```
```
In drivers/base/firmware_loader/main.c (ffffffff817e9ff5)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
```
```
In drivers/block/loop.c (ffffffff817fc8f7)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_add
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
```
```
In drivers/nvdimm/core.c (ffffffff8181d7c1)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:alloc_nvdimm_map
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff81820bec)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:__nvdimm_create
```
```
In drivers/nvdimm/dimm.c (ffffffff81822196)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
```
```
In drivers/dax/bus.c (ffffffff818340ed)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/dax/bus.c:alloc_dax_region
```
```
In drivers/dma-buf/dma-fence.c (ffffffff81837ae1)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_init
```
```
In drivers/dma-buf/dma-fence-array.c (ffffffff81838004)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_create
```
```
In drivers/dma-buf/sw_sync.c (ffffffff8183c803)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_timeline_create
```
```
In drivers/scsi/scsi.c (ffffffff8183f988)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_finish_command
  - drivers/scsi/scsi.c:scsi_finish_command
  - drivers/scsi/scsi.c:scsi_finish_command
```
```
In drivers/scsi/scsi_lib.c (ffffffff81848978)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:__scsi_queue_insert
  - drivers/scsi/scsi_lib.c:__scsi_queue_insert
  - drivers/scsi/scsi_lib.c:__scsi_queue_insert
```
```
In drivers/scsi/scsi_scan.c (ffffffff8184a023)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
```
```
In drivers/scsi/sd.c (ffffffff81857a2f)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
```
```
In drivers/scsi/sr.c (ffffffff8185b0ec)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_probe
```
```
In drivers/scsi/sg.c (ffffffff8185f6b9)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_add_sfp
  - drivers/scsi/sg.c:sg_alloc
  - drivers/scsi/sg.c:sg_alloc
```
```
In drivers/ata/libata-core.c (ffffffff81862804)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_init
  - drivers/ata/libata-core.c:ata_host_alloc
```
```
In drivers/net/phy/phy_device.c (ffffffff8189304d)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_package_join
```
```
In drivers/net/phy/sfp-bus.c (ffffffff81896c64)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_bus_get
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff818a097b)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
```
```
In drivers/vfio/vfio.c (ffffffff818aa110)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_fops_open
  - drivers/vfio/vfio.c:vfio_add_group_dev
  - drivers/vfio/vfio.c:vfio_create_group
  - drivers/vfio/vfio.c:vfio_create_group
  - drivers/vfio/vfio.c:vfio_create_group
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff818b2cc0)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_reflck_attach
```
```
In drivers/usb/core/usb.c (ffffffff818c0a58)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/usb/core/usb.c:usb_alloc_dev
```
```
In drivers/usb/core/hub.c (ffffffff81c1c18a)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_probe
```
```
In drivers/usb/core/hcd.c (ffffffff818c9244)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:__usb_create_hcd
```
```
In drivers/usb/core/urb.c (ffffffff818cc56c)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_alloc_urb
```
```
In drivers/usb/core/config.c (ffffffff818d2a86)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_configuration
```
```
In drivers/usb/core/file.c (ffffffff818d3688)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/usb/core/file.c:init_usb_class
```
```
In drivers/thermal/thermal_core.c (ffffffff8195abc3)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
```
```
In drivers/md/md.c (ffffffff81c265cd)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_run
  - drivers/md/md.c:max_corrected_read_errors_store
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:errors_store
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:mddev_init
  - drivers/md/md.c:mddev_init
  - drivers/md/md.c:mddev_init
  - drivers/md/md.c:mddev_init
  - drivers/md/md.c:submit_flushes
```
```
In drivers/md/md-bitmap.c (ffffffff8197ac92)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
```
```
In drivers/md/dm.c (ffffffff8197e920)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:dm_get_table_device
  - drivers/md/dm.c:alloc_io
```
```
In drivers/md/dm-table.c (ffffffff81980f0d)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_get_device
```
```
In drivers/md/dm-stripe.c (ffffffff81983dd6)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:stripe_ctr
```
```
In drivers/md/dm-io.c (ffffffff81987753)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/md/dm-io.c:dm_io
  - drivers/md/dm-io.c:sync_io
```
```
In drivers/md/dm-kcopyd.c (ffffffff819880ed)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
  - drivers/md/dm-kcopyd.c:dm_kcopyd_copy
```
```
In drivers/md/dm-stats.c (ffffffff8198a282)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
```
```
In drivers/edac/ghes_edac.c (ffffffff819912ef)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/edac/ghes_edac.c:ghes_edac_register
```
```
In drivers/opp/core.c (ffffffff819948ec)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/opp/core.c:_opp_add
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff8199c803)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_stop
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
  - drivers/cpufreq/cpufreq_governor.c:dbs_update_util_handler
  - drivers/cpufreq/cpufreq_governor.c:dbs_work_handler
```
```
In drivers/mmc/core/sdio_irq.c (ffffffff819b829e)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
```
```
In drivers/firmware/efi/efi.c (ffffffff81c3c20b)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff819c9e5a)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
```
```
In drivers/devfreq/devfreq.c (ffffffff819cfed4)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
```
In drivers/nvmem/core.c (ffffffff819da684)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/nvmem/core.c:nvmem_register
```
```
In net/core/sock.c (ffffffff819e3866)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_alloc
```
```
In net/core/skbuff.c (ffffffff819f4372)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_ext_add
  - net/core/skbuff.c:__skb_ext_alloc
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:pskb_carve_inside_header
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:sock_zerocopy_realloc
  - net/core/skbuff.c:sock_zerocopy_alloc
  - net/core/skbuff.c:skb_morph
  - net/core/skbuff.c:__build_skb_around
  - net/core/skbuff.c:__build_skb_around
  - net/core/skbuff.c:__alloc_skb
  - net/core/skbuff.c:__alloc_skb
  - net/core/skbuff.c:__alloc_skb
```
```
In net/core/net_namespace.c (ffffffff819f9aa5)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/core/net_namespace.c:copy_net_ns
  - net/core/net_namespace.c:copy_net_ns
  - net/core/net_namespace.c:setup_net
  - net/core/net_namespace.c:setup_net
```
```
In net/core/dev.c (ffffffff81a0566a)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/core/dev.c:__dev_kfree_skb_irq
```
```
In net/core/dst.c (ffffffff81a110c5)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/core/dst.c:__metadata_dst_init
  - net/core/dst.c:dst_cow_metrics_generic
  - net/core/dst.c:dst_alloc
```
```
In net/core/neighbour.c (ffffffff81a1353b)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:neigh_alloc
```
```
In net/core/filter.c (ffffffff81a3457f)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/core/filter.c:__sk_attach_prog
```
```
In net/core/flow_offload.c (ffffffff81a3912c)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/core/flow_offload.c:flow_indr_dev_register
```
```
In net/core/page_pool.c (ffffffff81a3ca55)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_init
  - net/core/page_pool.c:page_pool_init
```
```
In net/core/skmsg.c (ffffffff81a3e71b)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_init
```
```
In net/core/netpoll.c (ffffffff81a40fdc)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/core/netpoll.c:__netpoll_setup
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:zap_completion_queue
```
```
In net/core/fib_rules.c (ffffffff81a42f9e)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_default_rule_add
```
```
In net/core/devlink.c (ffffffff81a5a61e)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/core/devlink.c:__devlink_health_reporter_create
```
```
In net/sched/sch_generic.c (ffffffff81a6dfd8)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_alloc
```
```
In net/sched/cls_api.c (ffffffff81a74f6e)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_create
  - net/sched/cls_api.c:tcf_proto_create
```
```
In net/sched/act_api.c (ffffffff81a7b4b0)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_idr_create
  - net/sched/act_api.c:tcf_idr_create
```
```
In net/ipv4/route.c (ffffffff81a9aba5)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_genid_init
  - net/ipv4/route.c:rt_genid_init
  - net/ipv4/route.c:rt_genid_init
```
```
In net/ipv4/inetpeer.c (ffffffff81aa16f4)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81aaf09c)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81aaf9a7)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_hash_add
```
```
In net/ipv4/tcp.c (ffffffff81ab20b8)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/ipv4/tcp.c:skb_entail
```
```
In net/ipv4/tcp_input.c (ffffffff81abbb8e)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/tcp_output.c (ffffffff81ac61ad)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_queue_skb
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tso_fragment
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ad077f)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81ad9b0b)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_create_child
```
```
In net/ipv4/devinet.c (ffffffff81aedbee)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_init
```
```
In net/ipv4/igmp.c (ffffffff81af46e9)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/ipv4/igmp.c:____ip_mc_inc_group
```
```
In net/ipv4/fib_semantics.c (ffffffff81afc526)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_rebalance
```
```
In net/ipv4/inet_fragment.c (ffffffff81b030c0)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frags_init
```
```
In net/ipv4/metrics.c (ffffffff81b07fe2)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
```
```
In net/ipv4/nexthop.c (ffffffff81b0b750)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:nh_group_rebalance
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81b0baef)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:proc_tfo_blackhole_detect_timeout
```
```
In net/ipv4/ipmr.c (ffffffff81b11a63)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv4/syncookies.c (ffffffff81b1530e)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:tcp_get_cookie_sock
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81b19353)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b1c492)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
```
```
In net/xfrm/xfrm_state.c (ffffffff81b24d5f)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
```
```
In net/unix/af_unix.c (ffffffff81b34758)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_autobind
```
```
In net/ipv6/af_inet6.c (ffffffff81b39391)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_net_init
```
```
In net/ipv6/anycast.c (ffffffff81b3a1af)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
```
```
In net/ipv6/addrconf.c (ffffffff81b459ee)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_dev
```
```
In net/ipv6/route.c (ffffffff81b50a30)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
```
```
In net/ipv6/ip6_fib.c (ffffffff81b5d285)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_info_alloc
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81b6106d)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
```
```
In net/ipv6/mcast.c (ffffffff81b6f158)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mca_alloc
```
```
In net/ipv6/exthdrs.c (ffffffff81b7c6a6)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_dup_options
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81b7f323)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:fl_create
```
```
In net/ipv6/ip6mr.c (ffffffff81b854aa)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/ipv6/calipso.c (ffffffff81b8ccde)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_doi_add
```
```
In net/packet/af_packet.c (ffffffff81b9ab05)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/packet/af_packet.c:fanout_add
  - net/packet/af_packet.c:fanout_add
  - net/packet/af_packet.c:fanout_add
```
```
In net/xdp/xdp_umem.c (ffffffff81bb8216)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_reg
```
```
In net/xdp/xsk_buff_pool.c (ffffffff81bb9a54)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_create_and_assign_umem
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
In arch/x86/kernel/ioport.c (ffffffff81039e1f)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
  - arch/x86/kernel/ioport.c:ksys_ioperm
```
```
In arch/x86/kernel/tboot.c (ffffffff831c9e75)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/cpu/aperfmperf.c (ffffffff8104db0a)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_get_on_cpu
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81052c60)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:fake_panic_set
  - arch/x86/kernel/cpu/mce/core.c:fake_panic_set
  - arch/x86/kernel/cpu/mce/core.c:fake_panic_set
  - arch/x86/kernel/cpu/mce/core.c:fake_panic_set
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:mce_start
  - arch/x86/kernel/cpu/mce/core.c:mce_start
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81056b94)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:threshold_create_bank
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff8105ac6b)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:reload_store
  - arch/x86/kernel/cpu/microcode/core.c:reload_store
```
```
In arch/x86/kernel/cpu/sgx/driver.c (ffffffff81065d8b)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/driver.c:sgx_open
```
```
In arch/x86/kernel/reboot.c (ffffffff8106b5f7)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff8106e526)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_target
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
```
```
In arch/x86/kernel/kgdb.c (ffffffff8107d22f)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/kgdb.c:kgdb_arch_handle_exception
  - arch/x86/kernel/kgdb.c:kgdb_arch_handle_exception
```
```
In arch/x86/mm/init_64.c (ffffffff81c2ee69)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pagetable
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff831e38d8)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_common
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus
```
```
In kernel/fork.c (ffffffff810a114b)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/fork.c:copy_signal
  - kernel/fork.c:copy_signal
  - kernel/fork.c:copy_sighand
  - kernel/fork.c:mm_init
  - kernel/fork.c:mm_init
  - kernel/fork.c:mm_init
  - kernel/fork.c:mm_init
  - kernel/fork.c:dup_task_struct
  - kernel/fork.c:dup_task_struct
  - kernel/fork.c:dup_task_struct
```
```
In kernel/softirq.c (ffffffff810ab235)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/softirq.c:tasklet_init
  - kernel/softirq.c:tasklet_setup
```
```
In kernel/user.c (ffffffff810b392e)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/user.c:alloc_uid
```
```
In kernel/workqueue.c (ffffffff810c8efe)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_offline_cpu
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:flush_workqueue_prep_pwqs
```
```
In kernel/pid.c (ffffffff810ca4eb)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/pid.c:alloc_pid
```
```
In kernel/nsproxy.c (ffffffff810d2161)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/nsproxy.c:create_new_namespaces
```
```
In kernel/cred.c (ffffffff810d45e8)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:cred_alloc_blank
```
```
In kernel/smpboot.c (ffffffff810d66ec)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/smpboot.c:cpu_wait_death
  - kernel/smpboot.c:cpu_check_up_prepare
```
```
In kernel/groups.c (ffffffff810d7b1f)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/groups.c:__do_sys_setgroups
```
```
In kernel/sched/core.c (ffffffff831e5c1b)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:affine_move_task
```
```
In kernel/sched/fair.c (ffffffff810f0ad6)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_group
```
```
In kernel/sched/cpupri.c (ffffffff81100a87)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_init
```
```
In kernel/sched/topology.c (ffffffff81101c0d)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/sched/topology.c:sd_init
  - kernel/sched/topology.c:init_defrootdomain
```
```
In kernel/sched/autogroup.c (ffffffff8110545f)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
  - kernel/sched/autogroup.c:autogroup_init
```
```
In kernel/sched/membarrier.c (ffffffff8110b1df)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/sched/membarrier.c:membarrier_exec_mmap
```
```
In kernel/sched/psi.c (ffffffff8110b355)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/sched/psi.c:poll_timer_fn
```
```
In kernel/locking/mutex.c (ffffffff8110d174)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/locking/mutex.c:__mutex_init
```
```
In kernel/locking/rwsem.c (ffffffff8110d51c)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:__init_rwsem
```
```
In kernel/locking/percpu-rwsem.c (ffffffff8110e14c)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:__percpu_init_rwsem
```
```
In kernel/power/swap.c (ffffffff8111574e)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:save_image
```
```
In kernel/irq/manage.c (ffffffff8111f1a9)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_notifier
```
```
In kernel/rcu/update.c (ffffffff8112c345)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_trace_pregp_step
```
```
In kernel/rcu/srcutree.c (ffffffff8112e1f7)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
```
```
In kernel/rcu/tree.c (ffffffff8112fb42)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/rcu/tree.c:fill_page_cache_func
```
```
In kernel/time/namespace.c (ffffffff811571f9)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/time/namespace.c:copy_time_ns
```
```
In kernel/futex.c (ffffffff831e9660)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/futex.c:futex_init
```
```
In kernel/module.c (ffffffff81163f6a)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/module.c:load_module
```
```
In kernel/kexec_core.c (ffffffff81168712)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_free_reserved_phys_range
  - kernel/kexec_core.c:crash_kexec
```
```
In kernel/cgroup/cgroup.c (ffffffff8116d8ff)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:init_cgroup_root
  - kernel/cgroup/cgroup.c:find_css_set
```
```
In kernel/cgroup/namespace.c (ffffffff81176c9b)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
```
```
In kernel/utsname.c (ffffffff811813ba)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/utsname.c:copy_utsname
```
```
In kernel/user_namespace.c (ffffffff811829c5)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In kernel/pid_namespace.c (ffffffff811832c3)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/pid_namespace.c:create_pid_namespace
```
```
In kernel/stop_machine.c (ffffffff811845ca)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:stop_machine_cpuslocked
  - kernel/stop_machine.c:stop_machine_cpuslocked
  - kernel/stop_machine.c:stop_two_cpus
  - kernel/stop_machine.c:stop_two_cpus
  - kernel/stop_machine.c:multi_cpu_stop
  - kernel/stop_machine.c:stop_one_cpu
```
```
In kernel/audit_watch.c (ffffffff8118f854)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_watch.c:audit_to_watch
```
```
In kernel/audit_tree.c (ffffffff81190a1b)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/audit_tree.c:alloc_tree
```
```
In kernel/kprobes.c (ffffffff81195be9)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
```
```
In kernel/debug/debug_core.c (ffffffff81196a66)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff8119b57f)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
```
```
In kernel/hung_task.c (ffffffff811a1e35)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/hung_task.c:reset_hung_task_detector
```
```
In kernel/seccomp.c (ffffffff811a52ed)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_attach_filter
```
```
In kernel/relay.c (ffffffff811a699d)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/relay.c:__relay_reset
```
```
In kernel/trace/trace.c (ffffffff811ba395)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
```
```
In kernel/trace/tracing_map.c (ffffffff811c7d8a)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_create
  - kernel/trace/tracing_map.c:tracing_map_clear
```
```
In kernel/trace/blktrace.c (ffffffff811cf2e0)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:do_blk_trace_setup
```
```
In kernel/trace/fgraph.c (ffffffff811d1184)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/trace/fgraph.c:start_graph_tracing
  - kernel/trace/fgraph.c:ftrace_graph_init_task
  - kernel/trace/fgraph.c:ftrace_graph_init_idle_task
```
```
In kernel/trace/trace_events.c (ffffffff811d5ab8)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_trace_add_tracer
  - kernel/trace/trace_events.c:event_trace_add_tracer
  - kernel/trace/trace_events.c:__trace_early_add_events
  - kernel/trace/trace_events.c:__trace_early_add_events
  - kernel/trace/trace_events.c:trace_module_notify
  - kernel/trace/trace_events.c:trace_module_notify
  - kernel/trace/trace_events.c:trace_add_event_call
  - kernel/trace/trace_events.c:trace_add_event_call
```
```
In kernel/irq_work.c (ffffffff811f6f67)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_single
```
```
In kernel/bpf/trampoline.c (ffffffff8122707c)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_get
```
```
In kernel/bpf/btf.c (ffffffff81228c23)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_parse_module
  - kernel/bpf/btf.c:btf_parse_vmlinux
  - kernel/bpf/btf.c:btf_parse
```
```
In kernel/bpf/dispatcher.c (ffffffff81231de6)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/bpf/dispatcher.c:bpf_dispatcher_change_prog
```
```
In kernel/bpf/bpf_struct_ops.c (ffffffff8123c61b)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_sys_lookup_elem
```
```
In kernel/events/core.c (ffffffff81248a0c)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:alloc_perf_context
```
```
In kernel/events/ring_buffer.c (ffffffff8125321a)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc
  - kernel/events/ring_buffer.c:rb_alloc_aux
  - kernel/events/ring_buffer.c:perf_aux_output_skip
  - kernel/events/ring_buffer.c:perf_aux_output_end
  - kernel/events/ring_buffer.c:perf_aux_output_begin
  - kernel/events/ring_buffer.c:perf_output_end
```
```
In kernel/events/uprobes.c (ffffffff81256b53)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__create_xol_area
  - kernel/events/uprobes.c:alloc_uprobe
```
```
In kernel/padata.c (ffffffff812582b1)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/padata.c:padata_alloc_pd
```
```
In kernel/jump_label.c (ffffffff81259602)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/jump_label.c:static_key_enable_cpuslocked
  - kernel/jump_label.c:static_key_slow_inc_cpuslocked
```
```
In kernel/watch_queue.c (ffffffff8125bdfc)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/watch_queue.c:watch_queue_init
  - kernel/watch_queue.c:init_watch
```
```
In mm/filemap.c (ffffffff81bd880c)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/shmem.c (0)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
```
```
In mm/backing-dev.c (ffffffff81287497)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_alloc
```
```
In mm/gup.c (ffffffff81299416)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - mm/gup.c:pin_user_pages_locked
  - mm/gup.c:internal_get_user_pages_fast
  - mm/gup.c:get_user_pages_unlocked
  - mm/gup.c:__get_user_pages_remote
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:__gup_longterm_locked
```
```
In mm/rmap.c (ffffffff812b7673)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - mm/rmap.c:hugepage_add_new_anon_rmap
  - mm/rmap.c:hugepage_add_new_anon_rmap
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:anon_vma_ctor
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:__anon_vma_prepare
```
```
In mm/page_alloc.c (ffffffff812c4d6d)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:make_alloc_exact
  - mm/page_alloc.c:page_frag_alloc_align
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:check_new_page_bad
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:prep_compound_page
  - mm/page_alloc.c:prep_compound_page
  - mm/page_alloc.c:prep_compound_page
  - mm/page_alloc.c:bad_page
```
```
In mm/memory_hotplug.c (ffffffff812c6e41)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - mm/memory_hotplug.c:put_page_bootmem
```
```
In mm/swap_state.c (ffffffff812cc518)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - mm/swap_state.c:init_swap_address_space
  - mm/swap_state.c:swap_cluster_readahead
```
```
In mm/frontswap.c (ffffffff812d2e7f)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_invalidate_area
```
```
In mm/zswap.c (ffffffff812d39aa)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - mm/zswap.c:zswap_pool_create
```
```
In mm/hugetlb.c (ffffffff812d60f8)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:update_and_free_page
  - mm/hugetlb.c:update_and_free_page
  - mm/hugetlb.c:update_and_free_page
  - mm/hugetlb.c:remove_hugetlb_page
  - mm/hugetlb.c:dequeue_huge_page_nodemask
  - mm/hugetlb.c:resv_map_alloc
```
```
In mm/mempolicy.c (ffffffff812dff6b)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - mm/mempolicy.c:shared_policy_replace
  - mm/mempolicy.c:__mpol_dup
  - mm/mempolicy.c:mpol_new
```
```
In mm/huge_memory.c (ffffffff812fbe9e)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
```
```
In mm/memcontrol.c (ffffffff81308655)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_online
```
```
In mm/zpool.c (ffffffff81316059)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - mm/zpool.c:zpool_register_driver
```
```
In mm/zsmalloc.c (ffffffff813174ef)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - mm/zsmalloc.c:reset_page
```
```
In mm/page_reporting.c (ffffffff8131f0ab)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - mm/page_reporting.c:page_reporting_register
  - mm/page_reporting.c:page_reporting_process
  - mm/page_reporting.c:page_reporting_cycle
```
```
In fs/super.c (ffffffff8132810d)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/super.c:alloc_super
```
```
In fs/exec.c (ffffffff8132fc1e)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/exec.c:begin_new_exec
```
```
In fs/dcache.c (ffffffff8134284e)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/dcache.c:__d_alloc
```
```
In fs/inode.c (ffffffff813466a5)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/inode.c:inode_init_always
  - fs/inode.c:inode_init_always
  - fs/inode.c:inode_init_always
  - fs/inode.c:inode_init_always
```
```
In fs/file.c (ffffffff8134b162)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/file.c:dup_fd
```
```
In fs/namespace.c (ffffffff8134d285)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In fs/fsopen.c (ffffffff8136c1af)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/fsopen.c:__do_sys_fspick
  - fs/fsopen.c:__ia32_sys_fsopen
  - fs/fsopen.c:__x64_sys_fsopen
```
```
In fs/block_dev.c (ffffffff81373cf6)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_direct_IO
```
```
In fs/notify/group.c (ffffffff8137aa85)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/notify/group.c:__fsnotify_alloc_group
  - fs/notify/group.c:__fsnotify_alloc_group
```
```
In fs/notify/mark.c (ffffffff8137af5b)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_init_mark
```
```
In fs/eventfd.c (ffffffff81386127)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/eventfd.c:do_eventfd
```
```
In fs/userfaultfd.c (ffffffff81386b8c)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/userfaultfd.c:__do_sys_userfaultfd
  - fs/userfaultfd.c:dup_userfaultfd
```
```
In fs/aio.c (ffffffff8138d0c6)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:__ia32_sys_io_destroy
  - fs/aio.c:__x64_sys_io_destroy
  - fs/aio.c:exit_aio
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
```
```
In fs/io_uring.c (ffffffff813971a8)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/io_uring.c:io_kill_timeouts
  - fs/io_uring.c:io_uring_alloc_task_context
  - fs/io_uring.c:io_uring_alloc_task_context
  - fs/io_uring.c:io_uring_alloc_task_context
  - fs/io_uring.c:io_get_sq_data
  - fs/io_uring.c:io_get_sq_data
  - fs/io_uring.c:io_rsrc_data_alloc
  - fs/io_uring.c:io_init_req
  - fs/io_uring.c:io_timeout_fn
  - fs/io_uring.c:io_commit_cqring
```
```
In fs/io-wq.c (ffffffff813a37b7)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/io-wq.c:io_wq_create
  - fs/io-wq.c:io_wq_create
  - fs/io-wq.c:io_wq_create
  - fs/io-wq.c:io_wq_create
  - fs/io-wq.c:create_io_worker
```
```
In fs/crypto/keyring.c (ffffffff813aa647)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/crypto/keyring.c:add_new_master_key
```
```
In fs/crypto/keysetup_v1.c (ffffffff813aca57)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_get_direct_key
```
```
In fs/mbcache.c (ffffffff813bd25b)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/posix_acl.c (ffffffff813bdbe6)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/posix_acl.c:posix_acl_from_mode
  - fs/posix_acl.c:posix_acl_clone
```
```
In fs/coredump.c (ffffffff813bfc76)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/coredump.c:zap_threads
```
```
In fs/iomap/direct-io.c (ffffffff813c56fe)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:__iomap_dio_rw
```
```
In fs/quota/dquot.c (ffffffff813c92ba)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/quota/dquot.c:dqget
```
```
In fs/proc/generic.c (ffffffff813d9335)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/proc/generic.c:__proc_create
```
```
In fs/kernfs/inode.c (ffffffff813e5a55)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
```
```
In fs/kernfs/dir.c (ffffffff813e6c1b)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/kernfs/dir.c:__kernfs_new_node
  - fs/kernfs/dir.c:__kernfs_new_node
```
```
In fs/kernfs/file.c (ffffffff813e9254)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_fop_open
  - fs/kernfs/file.c:kernfs_fop_open
```
```
In fs/configfs/dir.c (ffffffff813eef8d)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_register_group
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_new_dirent
```
```
In fs/configfs/item.c (ffffffff813f0028)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/configfs/item.c:config_group_init_type_name
  - fs/configfs/item.c:config_item_init_type_name
```
```
In fs/ext4/mballoc.c (ffffffff81426311)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
```
```
In fs/ext4/page-io.c (ffffffff814320ab)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_init_io_end
```
```
In fs/ext4/super.c (ffffffff81452155)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_alloc_inode
  - fs/ext4/super.c:ext4_alloc_inode
```
```
In fs/ext4/fast_commit.c (ffffffff8145c0e2)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_init_inode
```
```
In fs/jbd2/transaction.c (ffffffff8145e4cd)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_get_transaction
  - fs/jbd2/transaction.c:jbd2_get_transaction
  - fs/jbd2/transaction.c:jbd2_get_transaction
  - fs/jbd2/transaction.c:jbd2_get_transaction
```
```
In fs/jbd2/journal.c (ffffffff8146814d)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_init_common
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/ecryptfs/main.c (ffffffff81be0405)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_get_lower_file
```
```
In fs/ecryptfs/super.c (ffffffff8148384f)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/ecryptfs/super.c:ecryptfs_alloc_inode
```
```
In fs/ecryptfs/miscdev.c (ffffffff831fba91)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/ecryptfs/miscdev.c:ecryptfs_init_ecryptfs_miscdev
```
```
In fs/fuse/dev.c (ffffffff8148e8c7)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_get_req
```
```
In fs/fuse/file.c (ffffffff8149a040)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_file_alloc
```
```
In fs/fuse/inode.c (ffffffff8149d7ba)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_conn_init
  - fs/fuse/inode.c:fuse_conn_init
  - fs/fuse/inode.c:fuse_conn_init
```
```
In fs/fuse/dax.c (ffffffff814a2ae7)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
```
```
In fs/debugfs/file.c (ffffffff814a5365)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_atomic_t_set
  - fs/debugfs/file.c:debugfs_file_get
```
```
In ipc/util.c (ffffffff814aa465)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In ipc/msg.c (ffffffff831fbfb0)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - ipc/msg.c:msg_init
  - ipc/msg.c:msg_init
```
```
In ipc/sem.c (ffffffff814b1a1d)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - ipc/sem.c:copy_semundo
  - ipc/sem.c:find_alloc_undo
```
```
In ipc/namespace.c (ffffffff814b8b00)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - ipc/namespace.c:copy_ipcs
```
```
In security/keys/key.c (ffffffff814ba591)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_user_lookup
  - security/keys/key.c:key_user_lookup
  - security/keys/key.c:key_user_lookup
```
```
In security/selinux/avc.c (ffffffff814d214b)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - security/selinux/avc.c:selinux_avc_init
  - security/selinux/avc.c:selinux_avc_init
```
```
In security/selinux/ss/services.c (ffffffff814f1d81)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
```
```
In security/smack/smack_access.c (ffffffff814fb98e)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - security/smack/smack_access.c:smack_populate_secattr
```
```
In security/tomoyo/condition.c (ffffffff815058cc)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_commit_condition
```
```
In security/tomoyo/gc.c (ffffffff8150a8b3)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - security/tomoyo/gc.c:tomoyo_collect_entry
  - security/tomoyo/gc.c:tomoyo_collect_entry
  - security/tomoyo/gc.c:tomoyo_collect_entry
```
```
In security/tomoyo/memory.c (ffffffff8150b39b)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_name
  - security/tomoyo/memory.c:tomoyo_get_group
```
```
In security/apparmor/apparmorfs.c (ffffffff81512d71)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_write_access
```
```
In security/apparmor/lib.c (ffffffff81515cfa)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - security/apparmor/lib.c:aa_str_alloc
```
```
In security/apparmor/match.c (ffffffff81516917)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
```
```
In security/apparmor/policy_unpack.c (ffffffff81522494)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:aa_loaddata_alloc
```
```
In security/apparmor/policy_ns.c (ffffffff8152a983)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:alloc_ns
```
```
In security/apparmor/label.c (ffffffff8152c224)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_alloc
  - security/apparmor/label.c:aa_alloc_proxy
```
```
In security/landlock/object.c (ffffffff81537947)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - security/landlock/object.c:landlock_create_object
```
```
In security/landlock/ruleset.c (ffffffff81538294)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - security/landlock/ruleset.c:landlock_merge_ruleset
  - security/landlock/ruleset.c:landlock_merge_ruleset
  - security/landlock/ruleset.c:landlock_create_ruleset
```
```
In crypto/api.c (ffffffff81544238)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - crypto/api.c:crypto_alg_mod_lookup
```
```
In crypto/algapi.c (ffffffff8154609d)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - crypto/algapi.c:__crypto_register_alg
  - crypto/algapi.c:crypto_check_alg
```
```
In block/bio.c (ffffffff81563b02)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - block/bio.c:bio_kmalloc
  - block/bio.c:bio_kmalloc
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_reset
```
```
In block/blk-core.c (ffffffff815679aa)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - block/blk-core.c:blk_alloc_queue
  - block/blk-core.c:blk_rq_init
```
```
In block/blk-ioc.c (ffffffff8156dac6)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - block/blk-ioc.c:create_task_io_context
  - block/blk-ioc.c:create_task_io_context
```
```
In block/blk-mq.c (ffffffff81578849)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_tag_set
  - block/blk-mq.c:blk_mq_alloc_hctx
  - block/blk-mq.c:blk_mq_rq_ctx_init
```
```
In block/bsg.c (ffffffff8158a3c7)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
```
```
In block/bsg-lib.c (ffffffff8158ac8d)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_queue_rq
```
```
In block/blk-cgroup.c (ffffffff8158b969)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_css_alloc
```
```
In block/blk-iocost.c (ffffffff815968ac)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - block/blk-iocost.c:blk_iocost_init
```
```
In block/blk-wbt.c (ffffffff8159eb0e)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_init
```
```
In block/keyslot-manager.c (ffffffff815a529f)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - block/keyslot-manager.c:blk_ksm_get_slot_for_key
```
```
In lib/rhashtable.c (ffffffff815b5b00)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_init
```
```
In lib/refcount.c (ffffffff815b6f70)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
```
```
In lib/cpu_rmap.c (ffffffff815df982)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - lib/cpu_rmap.c:alloc_cpu_rmap
```
```
In lib/sbitmap.c (ffffffff815ecee3)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbq_wake_up
  - lib/sbitmap.c:sbitmap_queue_init_node
  - lib/sbitmap.c:sbitmap_queue_init_node
  - lib/sbitmap.c:sbitmap_queue_init_node
```
```
In lib/dump_stack.c (ffffffff81be693d)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - lib/dump_stack.c:dump_stack
```
```
In lib/klist.c (ffffffff815f2152)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - lib/klist.c:klist_node_init
```
```
In lib/kobject.c (ffffffff815f3843)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - lib/kobject.c:kset_create_and_add
  - lib/kobject.c:kobject_create_and_add
```
```
In drivers/pinctrl/core.c (ffffffff8160bf3a)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:create_pinctrl
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff8161e775)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:linereq_create
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff81657b81)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
```
```
In drivers/rapidio/rio.c (ffffffff8166119d)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_register_mport
  - drivers/rapidio/rio.c:rio_mport_initialize
  - drivers/rapidio/rio.c:rio_del_device
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff8166a6a7)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:do_register_framebuffer
```
```
In drivers/acpi/ec.c (ffffffff8168f6b4)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_add_query_handler
```
```
In drivers/acpi/thermal.c (ffffffff816e6550)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/acpi/thermal.c:acpi_thermal_add
```
```
In drivers/acpi/apei/ghes.c (ffffffff816efdb8)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
```
```
In drivers/clk/clk.c (ffffffff816ff269)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_core_init
```
```
In drivers/dma/dmaengine.c (ffffffff817058d7)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaengine_get_unmap_data
  - drivers/dma/dmaengine.c:dma_async_device_register
```
```
In drivers/xen/balloon.c (ffffffff81714c9e)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_process
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff8171ff64)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_open
```
```
In drivers/reset/core.c (ffffffff8173276d)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/reset/core.c:__reset_control_get_internal
```
```
In drivers/tty/tty_io.c (ffffffff817378bb)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:alloc_tty_struct
```
```
In drivers/tty/tty_buffer.c (ffffffff8173efe9)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_init
  - drivers/tty/tty_buffer.c:tty_buffer_init
```
```
In drivers/tty/tty_port.c (ffffffff8173f272)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_init
```
```
In drivers/tty/serial/serial_core.c (ffffffff81759946)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_add_one_port
```
```
In drivers/char/virtio_console.c (ffffffff81773f19)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
```
```
In drivers/char/hw_random/core.c (ffffffff81776bfa)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
```
```
In drivers/char/agp/backend.c (ffffffff81777774)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/char/agp/backend.c:agp_alloc_bridge
  - drivers/char/agp/backend.c:agp_alloc_bridge
```
```
In drivers/iommu/ioasid.c (ffffffff817a2db2)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/iommu/ioasid.c:ioasid_alloc
```
```
In drivers/iommu/iova.c (ffffffff817a4344)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/iommu/iova.c:fq_flush_timeout
  - drivers/iommu/iova.c:init_iova_flush_queue
```
```
In drivers/connector/cn_queue.c (ffffffff817a4d4a)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/connector/cn_queue.c:cn_queue_alloc_dev
  - drivers/connector/cn_queue.c:cn_queue_add_callback
```
```
In drivers/lightnvm/core.c (ffffffff817a64d6)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_alloc_dev
```
```
In drivers/base/core.c (ffffffff817ad2ac)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/power/runtime.c (ffffffff817c2b75)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_init
  - drivers/base/power/runtime.c:pm_runtime_init
```
```
In drivers/base/power/wakeup.c (ffffffff817c8008)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:pm_wakeup_clear
```
```
In drivers/base/power/domain.c (ffffffff817ca6bf)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/base/power/domain.c:pm_genpd_init
```
```
In drivers/base/firmware_loader/main.c (ffffffff817ce705)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
```
```
In drivers/block/loop.c (ffffffff817e14af)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_add
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
```
```
In drivers/nvdimm/core.c (ffffffff81800a31)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:alloc_nvdimm_map
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff81803eec)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:__nvdimm_create
```
```
In drivers/nvdimm/dimm.c (ffffffff818054a6)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
```
```
In drivers/dax/bus.c (ffffffff818172d9)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/dax/bus.c:alloc_dax_region
```
```
In drivers/dma-buf/dma-fence.c (ffffffff8181a71f)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_init
```
```
In drivers/dma-buf/dma-fence-array.c (ffffffff8181b2f4)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_create
```
```
In drivers/dma-buf/sw_sync.c (ffffffff8181fb4a)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open
```
```
In drivers/scsi/scsi.c (ffffffff81822be8)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_finish_command
  - drivers/scsi/scsi.c:scsi_finish_command
  - drivers/scsi/scsi.c:scsi_finish_command
```
```
In drivers/scsi/scsi_lib.c (ffffffff8182bd2f)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:__scsi_queue_insert
  - drivers/scsi/scsi_lib.c:__scsi_queue_insert
  - drivers/scsi/scsi_lib.c:__scsi_queue_insert
```
```
In drivers/scsi/scsi_scan.c (ffffffff8182d7a3)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
```
```
In drivers/scsi/sd.c (ffffffff8183a9b1)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
```
```
In drivers/scsi/sr.c (ffffffff8183e0dc)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_probe
```
```
In drivers/scsi/sg.c (ffffffff818426b9)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_add_sfp
  - drivers/scsi/sg.c:sg_alloc
  - drivers/scsi/sg.c:sg_alloc
```
```
In drivers/ata/libata-core.c (ffffffff81845604)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_init
  - drivers/ata/libata-core.c:ata_host_alloc
```
```
In drivers/net/phy/phy_device.c (ffffffff818754dd)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_package_join
```
```
In drivers/net/phy/sfp-bus.c (ffffffff81879115)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_bus_get
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81883007)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
```
```
In drivers/vfio/vfio.c (ffffffff8188d660)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_fops_open
  - drivers/vfio/vfio.c:vfio_register_group_dev
  - drivers/vfio/vfio.c:vfio_create_group
  - drivers/vfio/vfio.c:vfio_create_group
  - drivers/vfio/vfio.c:vfio_create_group
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff81897377)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_probe
```
```
In drivers/usb/core/usb.c (ffffffff818a3cd8)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/usb/core/usb.c:usb_alloc_dev
```
```
In drivers/usb/core/hub.c (ffffffff81c0e070)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_probe
```
```
In drivers/usb/core/hcd.c (ffffffff818ac7a4)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:__usb_create_hcd
```
```
In drivers/usb/core/urb.c (ffffffff818afa9b)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_alloc_urb
```
```
In drivers/usb/core/config.c (ffffffff818b6016)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_configuration
```
```
In drivers/usb/core/file.c (ffffffff818b6bf7)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
```
```
In drivers/thermal/thermal_core.c (ffffffff8193f983)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
```
```
In drivers/thermal/intel/therm_throt.c (ffffffff819475ca)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/thermal/intel/therm_throt.c:intel_init_thermal
```
```
In drivers/md/md.c (ffffffff81c1879a)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_run
  - drivers/md/md.c:max_corrected_read_errors_store
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:errors_store
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:mddev_init
  - drivers/md/md.c:mddev_init
  - drivers/md/md.c:mddev_init
  - drivers/md/md.c:mddev_init
  - drivers/md/md.c:submit_flushes
```
```
In drivers/md/md-bitmap.c (ffffffff8195eec2)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
```
```
In drivers/md/dm.c (ffffffff81962770)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:__split_and_process_bio
  - drivers/md/dm.c:dm_get_table_device
```
```
In drivers/md/dm-table.c (ffffffff81965119)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_get_device
```
```
In drivers/md/dm-stripe.c (ffffffff819681c6)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:stripe_ctr
```
```
In drivers/md/dm-io.c (ffffffff8196be27)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/md/dm-io.c:dm_io
  - drivers/md/dm-io.c:sync_io
```
```
In drivers/md/dm-kcopyd.c (ffffffff8196c5f4)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
  - drivers/md/dm-kcopyd.c:dm_kcopyd_copy
```
```
In drivers/md/dm-stats.c (ffffffff8196e837)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
```
```
In drivers/edac/ghes_edac.c (ffffffff81975852)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/edac/ghes_edac.c:ghes_edac_register
```
```
In drivers/opp/core.c (ffffffff8197981b)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/opp/core.c:_opp_add
  - drivers/opp/core.c:_add_opp_table_indexed
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff819814d3)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_stop
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
  - drivers/cpufreq/cpufreq_governor.c:dbs_update_util_handler
  - drivers/cpufreq/cpufreq_governor.c:dbs_work_handler
```
```
In drivers/mmc/core/sdio_irq.c (ffffffff8199cab8)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_irq.c:sdio_release_irq
  - drivers/mmc/core/sdio_irq.c:sdio_claim_irq
```
```
In drivers/firmware/efi/efi.c (ffffffff81c2e6ab)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff819aee6a)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
```
```
In drivers/devfreq/devfreq.c (ffffffff819b5033)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
```
In drivers/nvmem/core.c (ffffffff819c00bb)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/nvmem/core.c:nvmem_register
```
```
In net/core/sock.c (ffffffff819c98e6)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_alloc
```
```
In net/core/skbuff.c (ffffffff819da532)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_ext_add
  - net/core/skbuff.c:__skb_ext_alloc
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:pskb_carve_inside_header
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:msg_zerocopy_realloc
  - net/core/skbuff.c:msg_zerocopy_alloc
  - net/core/skbuff.c:skb_morph
  - net/core/skbuff.c:__alloc_skb
  - net/core/skbuff.c:__build_skb_around
  - net/core/skbuff.c:__build_skb_around
```
```
In net/core/net_namespace.c (ffffffff819dfc66)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/core/net_namespace.c:copy_net_ns
  - net/core/net_namespace.c:copy_net_ns
  - net/core/net_namespace.c:setup_net
  - net/core/net_namespace.c:setup_net
```
```
In net/core/dev.c (ffffffff819ede8a)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/core/dev.c:__dev_kfree_skb_irq
```
```
In net/core/dst.c (ffffffff819f7f35)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/core/dst.c:__metadata_dst_init
  - net/core/dst.c:dst_cow_metrics_generic
  - net/core/dst.c:dst_alloc
```
```
In net/core/neighbour.c (ffffffff819f964b)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:neigh_alloc
```
```
In net/core/filter.c (ffffffff81a1b5ef)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/core/filter.c:__sk_attach_prog
```
```
In net/core/flow_offload.c (ffffffff81a203dc)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/core/flow_offload.c:flow_indr_dev_register
```
```
In net/core/page_pool.c (ffffffff81a239ae)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_create
  - net/core/page_pool.c:page_pool_create
```
```
In net/core/netpoll.c (ffffffff81a25c98)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/core/netpoll.c:__netpoll_setup
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:zap_completion_queue
```
```
In net/core/fib_rules.c (ffffffff81a27bee)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_default_rule_add
```
```
In net/core/devlink.c (ffffffff81a3c94e)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/core/devlink.c:__devlink_health_reporter_create
```
```
In net/core/skmsg.c (ffffffff81a4c928)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_init
```
```
In net/sched/sch_generic.c (ffffffff81a56848)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_alloc
```
```
In net/sched/cls_api.c (ffffffff81a62665)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tcf_block_get_ext
```
```
In net/sched/act_api.c (ffffffff81a64230)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_idr_create
  - net/sched/act_api.c:tcf_idr_create
```
```
In net/ipv4/route.c (ffffffff81a85f35)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_genid_init
  - net/ipv4/route.c:rt_genid_init
  - net/ipv4/route.c:rt_genid_init
```
```
In net/ipv4/inetpeer.c (ffffffff81a8c65d)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81a9a3aa)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81a9acb9)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_hash_add
```
```
In net/ipv4/tcp.c (ffffffff81a9d348)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/ipv4/tcp.c:skb_entail
```
```
In net/ipv4/tcp_input.c (ffffffff81aa6b4e)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/tcp_output.c (ffffffff81ab13bd)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_queue_skb
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tso_fragment
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81abb860)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81ac4b59)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_create_child
```
```
In net/ipv4/devinet.c (ffffffff81ad93be)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_init
```
```
In net/ipv4/igmp.c (ffffffff81adfd25)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/ipv4/igmp.c:____ip_mc_inc_group
```
```
In net/ipv4/fib_semantics.c (ffffffff81ae7d3b)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_rebalance
```
```
In net/ipv4/inet_fragment.c (ffffffff81aed718)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frags_init
```
```
In net/ipv4/metrics.c (ffffffff81af3842)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
```
```
In net/ipv4/nexthop.c (ffffffff81af9380)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:nh_hthr_group_rebalance
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81af974f)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:proc_tfo_blackhole_detect_timeout
```
```
In net/ipv4/ipmr.c (ffffffff81b00312)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv4/syncookies.c (ffffffff81b0311e)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:tcp_get_cookie_sock
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81b06dd3)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b0a182)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
```
```
In net/xfrm/xfrm_state.c (ffffffff81b1297f)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
```
```
In net/unix/af_unix.c (ffffffff81b22567)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_autobind
```
```
In net/ipv6/af_inet6.c (ffffffff81b26f78)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_net_init
```
```
In net/ipv6/anycast.c (ffffffff81b27e9b)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
```
```
In net/ipv6/addrconf.c (ffffffff81b3372c)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_dev
```
```
In net/ipv6/route.c (ffffffff81b3eb30)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
```
```
In net/ipv6/ip6_fib.c (ffffffff81b4b4c0)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_info_alloc
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81b4f33d)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
```
```
In net/ipv6/mcast.c (ffffffff81b60076)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
```
```
In net/ipv6/exthdrs.c (ffffffff81b6b266)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_dup_options
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81b6dba7)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:fl_create
```
```
In net/ipv6/ip6mr.c (ffffffff81b7401a)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/ipv6/calipso.c (ffffffff81b7bb8e)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_doi_add
```
```
In net/packet/af_packet.c (ffffffff81b89a34)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/packet/af_packet.c:fanout_add
  - net/packet/af_packet.c:fanout_add
  - net/packet/af_packet.c:fanout_add
```
```
In net/xdp/xdp_umem.c (ffffffff81ba73d8)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_reg
```
```
In net/xdp/xsk_buff_pool.c (ffffffff81ba8a34)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_create_and_assign_umem
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
In arch/x86/kernel/ioport.c (ffffffff8103f7cf)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
  - arch/x86/kernel/ioport.c:ksys_ioperm
```
```
In arch/x86/kernel/tboot.c (ffffffff832ab276)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/cpu/aperfmperf.c (ffffffff810552bb)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_get_on_cpu
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8105b160)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:fake_panic_set
  - arch/x86/kernel/cpu/mce/core.c:fake_panic_set
  - arch/x86/kernel/cpu/mce/core.c:fake_panic_set
  - arch/x86/kernel/cpu/mce/core.c:fake_panic_set
  - arch/x86/kernel/cpu/mce/core.c:mce_end
  - arch/x86/kernel/cpu/mce/core.c:mce_end
  - arch/x86/kernel/cpu/mce/core.c:mce_end
  - arch/x86/kernel/cpu/mce/core.c:mce_start
  - arch/x86/kernel/cpu/mce/core.c:mce_start
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff8105f7b0)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:threshold_create_bank
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff810641ab)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:reload_store
  - arch/x86/kernel/cpu/microcode/core.c:reload_store
```
```
In arch/x86/kernel/cpu/sgx/driver.c (ffffffff8106feab)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/driver.c:sgx_open
```
```
In arch/x86/kernel/reboot.c (ffffffff810760e7)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff81079e5f)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_target
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
```
```
In arch/x86/kernel/kgdb.c (ffffffff8108bb4f)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/kgdb.c:kgdb_arch_handle_exception
  - arch/x86/kernel/kgdb.c:kgdb_arch_handle_exception
```
```
In arch/x86/mm/init_64.c (ffffffff81d4d56a)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pagetable
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff832c735a)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_common
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus
```
```
In kernel/fork.c (ffffffff810b256b)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/fork.c:copy_signal
  - kernel/fork.c:copy_signal
  - kernel/fork.c:copy_sighand
  - kernel/fork.c:mm_init
  - kernel/fork.c:mm_init
  - kernel/fork.c:mm_init
  - kernel/fork.c:dup_task_struct
  - kernel/fork.c:dup_task_struct
  - kernel/fork.c:dup_task_struct
```
```
In kernel/softirq.c (ffffffff810bcd55)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/softirq.c:tasklet_init
  - kernel/softirq.c:tasklet_setup
```
```
In kernel/user.c (ffffffff810c5ace)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/user.c:alloc_uid
```
```
In kernel/workqueue.c (ffffffff810dbb53)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_offline_cpu
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:flush_workqueue_prep_pwqs
```
```
In kernel/pid.c (ffffffff810dd33b)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/pid.c:alloc_pid
```
```
In kernel/nsproxy.c (ffffffff810e52a1)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/nsproxy.c:create_new_namespaces
```
```
In kernel/cred.c (ffffffff810e77c8)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:cred_alloc_blank
```
```
In kernel/smpboot.c (ffffffff810e9b17)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/smpboot.c:cpu_wait_death
  - kernel/smpboot.c:cpu_check_up_prepare
```
```
In kernel/ucount.c (ffffffff810ea077)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/ucount.c:alloc_ucounts
```
```
In kernel/groups.c (ffffffff810eb3cf)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/groups.c:__do_sys_setgroups
```
```
In kernel/sched/core.c (ffffffff832c9c6f)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:affine_move_task
```
```
In kernel/sched/fair.c (ffffffff81109556)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_group
```
```
In kernel/sched/cpupri.c (ffffffff8111cba1)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_init
```
```
In kernel/sched/topology.c (ffffffff8111e468)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/sched/topology.c:sd_init
  - kernel/sched/topology.c:init_defrootdomain
```
```
In kernel/sched/autogroup.c (ffffffff811230cf)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
  - kernel/sched/autogroup.c:autogroup_init
```
```
In kernel/sched/membarrier.c (ffffffff81129a3f)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/sched/membarrier.c:membarrier_exec_mmap
```
```
In kernel/sched/psi.c (ffffffff81129ba5)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/sched/psi.c:poll_timer_fn
```
```
In kernel/sched/core_sched.c (ffffffff8112c5a9)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/sched/core_sched.c:sched_core_share_pid
```
```
In kernel/locking/mutex.c (ffffffff8112c8e4)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/locking/mutex.c:__mutex_init
```
```
In kernel/locking/rwsem.c (ffffffff8112cd6c)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:__init_rwsem
```
```
In kernel/locking/percpu-rwsem.c (ffffffff8112d89c)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:__percpu_init_rwsem
```
```
In kernel/power/swap.c (ffffffff8113596e)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:save_image
```
```
In kernel/irq/manage.c (ffffffff8113f639)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_notifier
```
```
In kernel/rcu/update.c (ffffffff8114d0a5)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_trace_pregp_step
```
```
In kernel/rcu/srcutree.c (ffffffff8114f6a7)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
```
```
In kernel/rcu/tree.c (ffffffff81150a90)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/rcu/tree.c:kfree_rcu_shrink_count
  - kernel/rcu/tree.c:fill_page_cache_func
  - kernel/rcu/tree.c:fill_page_cache_func
```
```
In kernel/time/namespace.c (ffffffff8117c049)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/time/namespace.c:copy_time_ns
```
```
In kernel/futex.c (ffffffff832cdc61)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/futex.c:futex_init
```
```
In kernel/module.c (ffffffff8118965e)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/module.c:load_module
```
```
In kernel/kexec_core.c (ffffffff8118e442)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_free_reserved_phys_range
  - kernel/kexec_core.c:crash_kexec
```
```
In kernel/cgroup/cgroup.c (ffffffff81193185)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:init_cgroup_root
  - kernel/cgroup/cgroup.c:find_css_set
```
```
In kernel/cgroup/namespace.c (ffffffff8119e51b)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
```
```
In kernel/utsname.c (ffffffff811a932a)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/utsname.c:copy_utsname
```
```
In kernel/user_namespace.c (ffffffff811aa995)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In kernel/pid_namespace.c (ffffffff811ab37d)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/pid_namespace.c:create_pid_namespace
```
```
In kernel/stop_machine.c (ffffffff811ac8fa)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:stop_machine_cpuslocked
  - kernel/stop_machine.c:stop_machine_cpuslocked
  - kernel/stop_machine.c:stop_two_cpus
  - kernel/stop_machine.c:stop_two_cpus
  - kernel/stop_machine.c:multi_cpu_stop
  - kernel/stop_machine.c:stop_one_cpu
```
```
In kernel/audit_watch.c (ffffffff811b8734)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_watch.c:audit_to_watch
```
```
In kernel/audit_tree.c (ffffffff811b98fb)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/audit_tree.c:alloc_tree
```
```
In kernel/kprobes.c (ffffffff811beb52)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
```
```
In kernel/debug/debug_core.c (ffffffff811bfe3c)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff811c54df)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
```
```
In kernel/hung_task.c (ffffffff811cb5f5)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/hung_task.c:reset_hung_task_detector
```
```
In kernel/seccomp.c (ffffffff811cea3d)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_attach_filter
```
```
In kernel/relay.c (ffffffff811d018d)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/relay.c:__relay_reset
```
```
In kernel/trace/trace.c (ffffffff811e4bbc)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
```
```
In kernel/trace/tracing_map.c (ffffffff811f36da)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_create
  - kernel/trace/tracing_map.c:tracing_map_clear
```
```
In kernel/trace/blktrace.c (ffffffff811fb940)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:do_blk_trace_setup
```
```
In kernel/trace/fgraph.c (ffffffff811fde84)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/trace/fgraph.c:start_graph_tracing
  - kernel/trace/fgraph.c:ftrace_graph_init_task
```
```
In kernel/trace/trace_events.c (ffffffff8120169a)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_module_notify
  - kernel/trace/trace_events.c:trace_add_event_call
  - kernel/trace/trace_events.c:trace_create_new_event
  - kernel/trace/trace_events.c:trace_create_new_event
```
```
In kernel/trace/trace_dynevent.c (ffffffff81222407)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/trace/trace_dynevent.c:trace_event_dyn_put_ref
```
```
In kernel/irq_work.c (ffffffff81228537)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_single
```
```
In kernel/bpf/trampoline.c (ffffffff8125f17c)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_get
```
```
In kernel/bpf/btf.c (ffffffff81260f13)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_parse_module
  - kernel/bpf/btf.c:btf_parse_vmlinux
  - kernel/bpf/btf.c:btf_parse
```
```
In kernel/bpf/dispatcher.c (ffffffff8126ae66)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/bpf/dispatcher.c:bpf_dispatcher_change_prog
```
```
In kernel/bpf/bpf_struct_ops.c (ffffffff81276fd5)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_sys_lookup_elem
```
```
In kernel/events/core.c (ffffffff81283810)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:alloc_perf_context
```
```
In kernel/events/ring_buffer.c (ffffffff8128eb1b)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc
  - kernel/events/ring_buffer.c:rb_alloc_aux
  - kernel/events/ring_buffer.c:perf_aux_output_skip
  - kernel/events/ring_buffer.c:perf_aux_output_end
  - kernel/events/ring_buffer.c:perf_aux_output_begin
  - kernel/events/ring_buffer.c:perf_output_end
```
```
In kernel/events/uprobes.c (ffffffff812928f3)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__create_xol_area
  - kernel/events/uprobes.c:alloc_uprobe
```
```
In kernel/padata.c (ffffffff81293e4b)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/padata.c:padata_alloc_pd
```
```
In kernel/jump_label.c (ffffffff812952c1)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/jump_label.c:static_key_enable_cpuslocked
  - kernel/jump_label.c:static_key_slow_inc_cpuslocked
```
```
In kernel/watch_queue.c (ffffffff81297cac)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/watch_queue.c:watch_queue_init
  - kernel/watch_queue.c:init_watch
```
```
In mm/filemap.c (ffffffff81cb9e66)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/shmem.c (0)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
```
```
In mm/backing-dev.c (ffffffff812c6e17)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_alloc
  - mm/backing-dev.c:wb_init
```
```
In mm/rmap.c (ffffffff812f9d83)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - mm/rmap.c:hugepage_add_new_anon_rmap
  - mm/rmap.c:hugepage_add_new_anon_rmap
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:anon_vma_ctor
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:__anon_vma_prepare
```
```
In mm/page_alloc.c (ffffffff8130921d)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:page_frag_alloc_align
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:split_page
  - mm/page_alloc.c:check_new_page_bad
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:prep_compound_page
  - mm/page_alloc.c:prep_compound_page
  - mm/page_alloc.c:bad_page
```
```
In mm/swap_state.c (ffffffff813116f7)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - mm/swap_state.c:init_swap_address_space
  - mm/swap_state.c:swap_cluster_readahead
```
```
In mm/frontswap.c (ffffffff813188cf)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_invalidate_area
```
```
In mm/zswap.c (ffffffff8131962c)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - mm/zswap.c:zswap_pool_create
```
```
In mm/hugetlb.c (ffffffff81325506)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_and_dissolve_huge_page
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:remove_hugetlb_page
  - mm/hugetlb.c:dequeue_huge_page_nodemask
  - mm/hugetlb.c:resv_map_alloc
```
```
In mm/mempolicy.c (ffffffff813274ab)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - mm/mempolicy.c:shared_policy_replace
  - mm/mempolicy.c:__mpol_dup
  - mm/mempolicy.c:mpol_new
```
```
In mm/kfence/core.c (ffffffff8133bd2f)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
```
```
In mm/huge_memory.c (ffffffff81345cd2)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
```
```
In mm/memcontrol.c (ffffffff8135385a)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - mm/memcontrol.c:__mem_cgroup_flush_stats
```
```
In mm/zpool.c (ffffffff81362179)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - mm/zpool.c:zpool_register_driver
```
```
In mm/zsmalloc.c (ffffffff81363a4f)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - mm/zsmalloc.c:reset_page
```
```
In mm/page_reporting.c (ffffffff8136c4b2)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - mm/page_reporting.c:page_reporting_register
  - mm/page_reporting.c:page_reporting_process
  - mm/page_reporting.c:page_reporting_cycle
```
```
In mm/bootmem_info.c (ffffffff8136cb71)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - mm/bootmem_info.c:put_page_bootmem
```
```
In fs/super.c (ffffffff813756dd)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/super.c:alloc_super
```
```
In fs/exec.c (ffffffff8137d247)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/exec.c:begin_new_exec
```
```
In fs/dcache.c (ffffffff8139016e)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/dcache.c:__d_alloc
```
```
In fs/inode.c (ffffffff813940c5)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/inode.c:inode_init_always
  - fs/inode.c:inode_init_always
  - fs/inode.c:inode_init_always
  - fs/inode.c:inode_init_always
```
```
In fs/file.c (ffffffff81398fc2)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/file.c:dup_fd
```
```
In fs/namespace.c (ffffffff8139b255)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In fs/fsopen.c (ffffffff813bae7f)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/fsopen.c:__do_sys_fspick
  - fs/fsopen.c:__ia32_sys_fsopen
  - fs/fsopen.c:__x64_sys_fsopen
```
```
In fs/notify/group.c (ffffffff813c7766)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/notify/group.c:__fsnotify_alloc_group
  - fs/notify/group.c:__fsnotify_alloc_group
```
```
In fs/notify/mark.c (ffffffff813c7bbb)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_init_mark
```
```
In fs/eventfd.c (ffffffff813d33f7)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/eventfd.c:do_eventfd
```
```
In fs/userfaultfd.c (ffffffff813d3e8c)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/userfaultfd.c:__do_sys_userfaultfd
  - fs/userfaultfd.c:__do_sys_userfaultfd
  - fs/userfaultfd.c:dup_userfaultfd
  - fs/userfaultfd.c:dup_userfaultfd
```
```
In fs/aio.c (ffffffff813da826)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:__ia32_sys_io_destroy
  - fs/aio.c:__x64_sys_io_destroy
  - fs/aio.c:exit_aio
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
```
```
In fs/io_uring.c (ffffffff813e5d86)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/io_uring.c:io_kill_timeouts
  - fs/io_uring.c:io_uring_alloc_task_context
  - fs/io_uring.c:io_uring_alloc_task_context
  - fs/io_uring.c:io_uring_alloc_task_context
  - fs/io_uring.c:io_get_sq_data
  - fs/io_uring.c:io_get_sq_data
  - fs/io_uring.c:io_rsrc_data_alloc
  - fs/io_uring.c:io_wq_submit_work
  - fs/io_uring.c:io_req_prep
  - fs/io_uring.c:io_timeout_fn
  - fs/io_uring.c:io_arm_poll_handler
  - fs/io_uring.c:__io_commit_cqring_flush
  - fs/io_uring.c:__io_prep_linked_timeout
  - fs/io_uring.c:__io_prep_linked_timeout
```
```
In fs/io-wq.c (ffffffff813f2d10)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/io-wq.c:io_wq_create
  - fs/io-wq.c:io_wq_create
  - fs/io-wq.c:create_io_worker
```
```
In fs/crypto/keyring.c (ffffffff813f9ed7)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/crypto/keyring.c:add_new_master_key
```
```
In fs/crypto/keysetup_v1.c (ffffffff813fc3c7)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_get_direct_key
```
```
In fs/mbcache.c (ffffffff8140d00f)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/posix_acl.c (ffffffff8140d9ec)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/posix_acl.c:posix_acl_from_mode
  - fs/posix_acl.c:posix_acl_clone
```
```
In fs/coredump.c (ffffffff8140faa6)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/coredump.c:zap_threads
```
```
In fs/iomap/direct-io.c (ffffffff81415ad6)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:__iomap_dio_rw
```
```
In fs/quota/dquot.c (ffffffff81419b1c)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/quota/dquot.c:dqget
```
```
In fs/proc/generic.c (ffffffff8142aa65)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/proc/generic.c:__proc_create
```
```
In fs/kernfs/inode.c (ffffffff81437625)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
```
```
In fs/kernfs/dir.c (ffffffff814387bb)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/kernfs/dir.c:__kernfs_new_node
  - fs/kernfs/dir.c:__kernfs_new_node
```
```
In fs/kernfs/file.c (ffffffff8143afc8)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_fop_open
  - fs/kernfs/file.c:kernfs_fop_open
```
```
In fs/configfs/dir.c (ffffffff81440e4d)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_register_group
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_new_dirent
```
```
In fs/configfs/item.c (ffffffff81441f18)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/configfs/item.c:config_group_init_type_name
  - fs/configfs/item.c:config_item_init_type_name
```
```
In fs/ext4/mballoc.c (ffffffff81479fd3)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_init
```
```
In fs/ext4/page-io.c (ffffffff8148591b)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_init_io_end
```
```
In fs/ext4/super.c (ffffffff814a5762)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_alloc_inode
  - fs/ext4/super.c:ext4_alloc_inode
```
```
In fs/ext4/fast_commit.c (ffffffff814af959)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_init_inode
```
```
In fs/ext4/orphan.c (ffffffff814b226a)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/ext4/orphan.c:ext4_init_orphan_info
```
```
In fs/jbd2/transaction.c (ffffffff814b433e)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
```
```
In fs/jbd2/journal.c (ffffffff814be74d)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_init_common
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/ecryptfs/main.c (ffffffff81cd0b5a)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_get_lower_file
```
```
In fs/ecryptfs/super.c (ffffffff814dafff)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/ecryptfs/super.c:ecryptfs_alloc_inode
```
```
In fs/ecryptfs/miscdev.c (ffffffff832e2ae3)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/ecryptfs/miscdev.c:ecryptfs_init_ecryptfs_miscdev
```
```
In fs/fuse/dev.c (ffffffff814e6337)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_get_req
```
```
In fs/fuse/file.c (ffffffff814f1a69)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_file_alloc
```
```
In fs/fuse/inode.c (ffffffff814f68b4)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_fill_super_common
  - fs/fuse/inode.c:fuse_conn_init
  - fs/fuse/inode.c:fuse_conn_init
  - fs/fuse/inode.c:fuse_conn_init
  - fs/fuse/inode.c:fuse_sync_fs_writes
```
```
In fs/fuse/dax.c (ffffffff814fab81)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
```
```
In fs/debugfs/file.c (ffffffff814fd4d5)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_atomic_t_set
  - fs/debugfs/file.c:debugfs_file_get
```
```
In ipc/util.c (ffffffff81502985)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In ipc/msg.c (ffffffff832e3002)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - ipc/msg.c:msg_init
  - ipc/msg.c:msg_init
```
```
In ipc/sem.c (ffffffff81509fcd)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - ipc/sem.c:copy_semundo
  - ipc/sem.c:find_alloc_undo
```
```
In ipc/namespace.c (ffffffff81511330)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - ipc/namespace.c:copy_ipcs
```
```
In security/keys/key.c (ffffffff81512dc1)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_user_lookup
  - security/keys/key.c:key_user_lookup
  - security/keys/key.c:key_user_lookup
```
```
In security/selinux/avc.c (ffffffff8152af52)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - security/selinux/avc.c:selinux_avc_init
  - security/selinux/avc.c:selinux_avc_init
```
```
In security/selinux/ss/services.c (ffffffff8154c45e)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
```
```
In security/smack/smack_access.c (ffffffff815565fe)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - security/smack/smack_access.c:smack_populate_secattr
```
```
In security/tomoyo/condition.c (ffffffff8156270c)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_commit_condition
```
```
In security/tomoyo/gc.c (ffffffff81567fa4)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - security/tomoyo/gc.c:tomoyo_collect_entry
  - security/tomoyo/gc.c:tomoyo_collect_entry
  - security/tomoyo/gc.c:tomoyo_collect_entry
```
```
In security/tomoyo/memory.c (ffffffff81568bf4)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_name
  - security/tomoyo/memory.c:tomoyo_get_group
```
```
In security/apparmor/apparmorfs.c (ffffffff81570971)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_write_access
```
```
In security/apparmor/lib.c (ffffffff81573cfa)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - security/apparmor/lib.c:aa_str_alloc
```
```
In security/apparmor/match.c (ffffffff81574917)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
```
```
In security/apparmor/policy_unpack.c (ffffffff815806e4)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:aa_loaddata_alloc
```
```
In security/apparmor/policy_ns.c (ffffffff81588d2f)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:alloc_ns
```
```
In security/apparmor/label.c (ffffffff8158a612)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_alloc
  - security/apparmor/label.c:aa_alloc_proxy
```
```
In security/landlock/object.c (ffffffff81596147)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - security/landlock/object.c:landlock_create_object
```
```
In security/landlock/ruleset.c (ffffffff8159695a)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - security/landlock/ruleset.c:landlock_merge_ruleset
  - security/landlock/ruleset.c:landlock_merge_ruleset
  - security/landlock/ruleset.c:landlock_create_ruleset
```
```
In security/integrity/ima/ima_policy.c (ffffffff832e7705)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_init_policy
```
```
In crypto/api.c (ffffffff815a49d8)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - crypto/api.c:crypto_alg_mod_lookup
```
```
In crypto/algapi.c (ffffffff815a686d)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - crypto/algapi.c:__crypto_register_alg
  - crypto/algapi.c:crypto_check_alg
```
```
In block/fops.c (ffffffff815c5f22)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - block/fops.c:__blkdev_direct_IO
```
```
In block/bio.c (ffffffff815c74c9)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - block/bio.c:bio_kmalloc
  - block/bio.c:bio_kmalloc
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_reset
```
```
In block/blk-core.c (ffffffff815ce699)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - block/blk-core.c:blk_alloc_queue
```
```
In block/blk-flush.c (ffffffff815d0679)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - block/blk-flush.c:blk_flush_complete_seq
```
```
In block/blk-ioc.c (ffffffff815d20b6)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - block/blk-ioc.c:create_task_io_context
  - block/blk-ioc.c:create_task_io_context
```
```
In block/blk-mq.c (ffffffff815dd979)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_tag_set
  - block/blk-mq.c:blk_mq_alloc_hctx
  - block/blk-mq.c:blk_mq_rq_ctx_init
```
```
In block/bsg-lib.c (ffffffff815efd5d)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_queue_rq
```
```
In block/blk-cgroup.c (ffffffff815f0c84)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_css_alloc
```
```
In block/blk-throttle.c (ffffffff815f7d9d)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:throtl_start_new_slice_with_credit
```
```
In block/blk-iocost.c (ffffffff815fdec2)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - block/blk-iocost.c:blk_iocost_init
```
```
In block/blk-wbt.c (ffffffff8160727e)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_init
```
```
In block/keyslot-manager.c (ffffffff8160dd48)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - block/keyslot-manager.c:blk_ksm_get_slot_for_key
```
```
In lib/rhashtable.c (ffffffff8161bf97)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_init
```
```
In lib/refcount.c (ffffffff8161d520)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
```
```
In lib/cpu_rmap.c (ffffffff8164b5c2)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - lib/cpu_rmap.c:alloc_cpu_rmap
```
```
In lib/sbitmap.c (ffffffff81659e03)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbq_wake_up
  - lib/sbitmap.c:sbitmap_queue_min_shallow_depth
  - lib/sbitmap.c:sbitmap_queue_resize
  - lib/sbitmap.c:sbitmap_queue_init_node
  - lib/sbitmap.c:sbitmap_queue_init_node
  - lib/sbitmap.c:sbitmap_queue_init_node
```
```
In lib/klist.c (ffffffff8165f4e4)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - lib/klist.c:klist_add_before
  - lib/klist.c:klist_add_behind
  - lib/klist.c:klist_add_tail
  - lib/klist.c:klist_add_head
```
```
In lib/kobject.c (ffffffff81660a13)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - lib/kobject.c:kset_create_and_add
  - lib/kobject.c:kobject_create_and_add
```
```
In drivers/pinctrl/core.c (ffffffff8167ac4a)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:create_pinctrl
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff8168e122)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:linereq_create
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff816c9bb0)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
```
```
In drivers/rapidio/rio.c (ffffffff816d3f2d)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_register_mport
  - drivers/rapidio/rio.c:rio_mport_initialize
  - drivers/rapidio/rio.c:rio_del_device
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff816de956)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:do_register_framebuffer
```
```
In drivers/acpi/ec.c (ffffffff81705114)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_add_query_handler
```
```
In drivers/acpi/thermal.c (ffffffff8175f8a0)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/acpi/thermal.c:acpi_thermal_add
```
```
In drivers/acpi/apei/ghes.c (ffffffff81769e5e)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
```
```
In drivers/clk/clk.c (ffffffff81779b30)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_core_init
```
```
In drivers/dma/dmaengine.c (ffffffff81780e27)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaengine_get_unmap_data
  - drivers/dma/dmaengine.c:dma_async_device_register
```
```
In drivers/xen/balloon.c (ffffffff81791bc4)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_thread
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff8179f024)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_open
```
```
In drivers/reset/core.c (ffffffff817b305f)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/reset/core.c:__reset_control_get_internal
```
```
In drivers/tty/tty_io.c (ffffffff817b834b)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:alloc_tty_struct
```
```
In drivers/tty/tty_buffer.c (ffffffff817bf779)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_init
  - drivers/tty/tty_buffer.c:tty_buffer_init
```
```
In drivers/tty/tty_port.c (ffffffff817bfa02)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_init
```
```
In drivers/tty/serial/serial_core.c (ffffffff817dda66)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_add_one_port
```
```
In drivers/char/virtio_console.c (ffffffff817fa2f9)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
```
```
In drivers/char/hw_random/core.c (ffffffff817fc5ca)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:set_current_rng
```
```
In drivers/char/agp/backend.c (ffffffff817fd5c4)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/char/agp/backend.c:agp_alloc_bridge
  - drivers/char/agp/backend.c:agp_alloc_bridge
```
```
In drivers/iommu/ioasid.c (ffffffff8182c0f2)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/iommu/ioasid.c:ioasid_alloc
```
```
In drivers/iommu/iova.c (ffffffff8182d564)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/iommu/iova.c:fq_flush_timeout
  - drivers/iommu/iova.c:init_iova_flush_queue
```
```
In drivers/connector/cn_queue.c (ffffffff818306ca)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/connector/cn_queue.c:cn_queue_alloc_dev
  - drivers/connector/cn_queue.c:cn_queue_add_callback
```
```
In drivers/base/core.c (ffffffff818365a2)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/power/runtime.c (ffffffff8184cf05)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_init
  - drivers/base/power/runtime.c:pm_runtime_init
```
```
In drivers/base/power/wakeup.c (ffffffff81852474)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:pm_wakeup_clear
```
```
In drivers/base/power/domain.c (ffffffff8185478f)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/base/power/domain.c:pm_genpd_init
```
```
In drivers/base/firmware_loader/main.c (ffffffff81858fb5)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
```
```
In drivers/block/loop.c (ffffffff8186d35f)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_add
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
```
```
In drivers/nvdimm/core.c (ffffffff8188ae31)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:alloc_nvdimm_map
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff8188ebab)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:__nvdimm_create
```
```
In drivers/nvdimm/dimm.c (ffffffff8188fb36)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
```
```
In drivers/dax/bus.c (ffffffff818a1929)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
```
```
In drivers/dma-buf/dma-fence.c (ffffffff818a49fb)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
```
```
In drivers/dma-buf/dma-fence-array.c (ffffffff818a5764)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_create
```
```
In drivers/dma-buf/sw_sync.c (ffffffff818aa20a)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open
```
```
In drivers/scsi/scsi.c (ffffffff818ad528)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_finish_command
  - drivers/scsi/scsi.c:scsi_finish_command
  - drivers/scsi/scsi.c:scsi_finish_command
```
```
In drivers/scsi/scsi_lib.c (ffffffff818b78f1)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:__scsi_queue_insert
  - drivers/scsi/scsi_lib.c:__scsi_queue_insert
  - drivers/scsi/scsi_lib.c:__scsi_queue_insert
```
```
In drivers/scsi/scsi_scan.c (ffffffff818b91f3)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
```
```
In drivers/scsi/sd.c (ffffffff818c706a)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
```
```
In drivers/scsi/sr.c (ffffffff818cab9b)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_probe
```
```
In drivers/scsi/sg.c (ffffffff818cf7c9)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_add_sfp
  - drivers/scsi/sg.c:sg_alloc
  - drivers/scsi/sg.c:sg_alloc
```
```
In drivers/ata/libata-core.c (ffffffff818d2094)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_init
  - drivers/ata/libata-core.c:ata_host_alloc
```
```
In drivers/net/phy/phy_device.c (ffffffff81905fad)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_package_join
```
```
In drivers/net/phy/sfp-bus.c (ffffffff81909f65)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_bus_get
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff819149a7)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
```
```
In drivers/vfio/vfio.c (ffffffff81920bc0)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_fops_open
  - drivers/vfio/vfio.c:vfio_register_group_dev
  - drivers/vfio/vfio.c:vfio_create_group
  - drivers/vfio/vfio.c:vfio_create_group
  - drivers/vfio/vfio.c:vfio_create_group
```
```
In drivers/usb/core/usb.c (ffffffff81938938)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/usb/core/usb.c:usb_alloc_dev
```
```
In drivers/usb/core/hub.c (ffffffff81d1514a)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_probe
```
```
In drivers/usb/core/hcd.c (ffffffff819417f4)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:__usb_create_hcd
```
```
In drivers/usb/core/urb.c (ffffffff81944beb)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_alloc_urb
```
```
In drivers/usb/core/config.c (ffffffff8194b66d)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_configuration
```
```
In drivers/usb/core/file.c (ffffffff8194c59a)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
```
```
In drivers/thermal/thermal_core.c (ffffffff819e4293)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
```
```
In drivers/thermal/intel/therm_throt.c (ffffffff819ec439)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/thermal/intel/therm_throt.c:intel_init_thermal
```
```
In drivers/md/md.c (ffffffff81d27d86)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_run
  - drivers/md/md.c:max_corrected_read_errors_store
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:errors_store
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:mddev_init
  - drivers/md/md.c:mddev_init
  - drivers/md/md.c:mddev_init
  - drivers/md/md.c:mddev_init
  - drivers/md/md.c:submit_flushes
```
```
In drivers/md/md-bitmap.c (ffffffff81a04802)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
```
```
In drivers/md/dm.c (ffffffff81a099bf)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:__split_and_process_bio
  - drivers/md/dm.c:dm_get_table_device
```
```
In drivers/md/dm-table.c (ffffffff81a0d099)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_get_device
```
```
In drivers/md/dm-stripe.c (ffffffff81a105d6)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:stripe_ctr
```
```
In drivers/md/dm-io.c (ffffffff81a142e7)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/md/dm-io.c:dm_io
  - drivers/md/dm-io.c:sync_io
```
```
In drivers/md/dm-kcopyd.c (ffffffff81a14949)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
  - drivers/md/dm-kcopyd.c:dm_kcopyd_copy
```
```
In drivers/md/dm-stats.c (ffffffff81a17097)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
```
```
In drivers/edac/ghes_edac.c (ffffffff81a1e56a)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/edac/ghes_edac.c:ghes_edac_register
```
```
In drivers/opp/core.c (ffffffff81a2282b)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/opp/core.c:_opp_add
  - drivers/opp/core.c:_add_opp_table_indexed
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff81a2a723)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_stop
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
  - drivers/cpufreq/cpufreq_governor.c:dbs_update_util_handler
  - drivers/cpufreq/cpufreq_governor.c:dbs_work_handler
```
```
In drivers/mmc/core/sdio_irq.c (ffffffff81a494a9)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_irq.c:sdio_release_irq
  - drivers/mmc/core/sdio_irq.c:sdio_claim_irq
```
```
In drivers/firmware/efi/efi.c (ffffffff81d4cd6b)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81a5d46a)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
```
```
In drivers/devfreq/devfreq.c (ffffffff81a63ba3)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
```
In drivers/nvmem/core.c (ffffffff81a6f80b)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/nvmem/core.c:nvmem_register
```
```
In net/core/sock.c (ffffffff81a78c9f)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_alloc
  - net/core/sock.c:sock_set_timestamping
  - net/core/sock.c:sock_set_timestamping
```
```
In net/core/skbuff.c (ffffffff81a8a542)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_ext_add
  - net/core/skbuff.c:__skb_ext_alloc
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:pskb_carve_inside_header
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:msg_zerocopy_realloc
  - net/core/skbuff.c:msg_zerocopy_alloc
  - net/core/skbuff.c:__skb_clone
  - net/core/skbuff.c:__alloc_skb
  - net/core/skbuff.c:__build_skb_around
  - net/core/skbuff.c:__build_skb_around
```
```
In net/core/net_namespace.c (ffffffff81a90066)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/core/net_namespace.c:copy_net_ns
  - net/core/net_namespace.c:copy_net_ns
  - net/core/net_namespace.c:setup_net
  - net/core/net_namespace.c:setup_net
```
```
In net/core/dev.c (ffffffff81a9f12a)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/core/dev.c:__dev_kfree_skb_irq
```
```
In net/core/dst.c (ffffffff81aa9b75)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/core/dst.c:__metadata_dst_init
  - net/core/dst.c:dst_cow_metrics_generic
  - net/core/dst.c:dst_alloc
```
```
In net/core/neighbour.c (ffffffff81aac69b)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:neigh_alloc
```
```
In net/core/filter.c (ffffffff81aceccf)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/core/filter.c:__sk_attach_prog
```
```
In net/core/flow_offload.c (ffffffff81ad45b5)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/core/flow_offload.c:flow_indr_dev_register
```
```
In net/core/page_pool.c (ffffffff81ad7fde)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_create
  - net/core/page_pool.c:page_pool_create
```
```
In net/core/netpoll.c (ffffffff81ada9f8)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/core/netpoll.c:__netpoll_setup
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:zap_completion_queue
```
```
In net/core/fib_rules.c (ffffffff81adc98e)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_default_rule_add
```
```
In net/core/devlink.c (ffffffff81af6122)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_alloc_ns
  - net/core/devlink.c:__devlink_health_reporter_create
  - net/core/devlink.c:devlink_nl_cmd_rate_new_doit
```
```
In net/core/skmsg.c (ffffffff81b060c8)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_init
```
```
In net/sched/sch_generic.c (ffffffff81b0f644)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_alloc
```
```
In net/sched/cls_api.c (ffffffff81b1b966)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tcf_block_get_ext
```
```
In net/sched/act_api.c (ffffffff81b1d5d0)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_idr_create
  - net/sched/act_api.c:tcf_idr_create
```
```
In net/ipv4/route.c (ffffffff81b40735)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_genid_init
  - net/ipv4/route.c:rt_genid_init
  - net/ipv4/route.c:rt_genid_init
```
```
In net/ipv4/inetpeer.c (ffffffff81b4779d)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81b5581a)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81b574cb)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_complete_hashdance
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_hash_add
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
```
```
In net/ipv4/tcp.c (ffffffff81b59218)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/ipv4/tcp.c:skb_entail
```
```
In net/ipv4/tcp_input.c (ffffffff81b6314e)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/tcp_output.c (ffffffff81b6e2cd)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_queue_skb
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tso_fragment
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81b78a83)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81b83309)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_create_child
```
```
In net/ipv4/devinet.c (ffffffff81b98423)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_init
```
```
In net/ipv4/igmp.c (ffffffff81b9f2b3)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/ipv4/igmp.c:____ip_mc_inc_group
```
```
In net/ipv4/fib_frontend.c (ffffffff81ba1df3)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
```
```
In net/ipv4/fib_semantics.c (ffffffff81ba7bd6)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_rebalance
```
```
In net/ipv4/inet_fragment.c (ffffffff81badad8)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frags_init
```
```
In net/ipv4/metrics.c (ffffffff81bb3d62)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
```
```
In net/ipv4/nexthop.c (ffffffff81bb9ed0)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:nh_hthr_group_rebalance
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81bba29f)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:proc_tfo_blackhole_detect_timeout
```
```
In net/ipv4/ipmr.c (ffffffff81bc2402)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv4/syncookies.c (ffffffff81bc535e)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:tcp_get_cookie_sock
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81bc9c48)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff81bccfb1)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
```
```
In net/xfrm/xfrm_state.c (ffffffff81bd681f)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
```
```
In net/unix/af_unix.c (ffffffff81be9270)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
```
```
In net/ipv6/af_inet6.c (ffffffff81bec9e4)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_net_init
```
```
In net/ipv6/anycast.c (ffffffff81bedddb)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
```
```
In net/ipv6/addrconf.c (ffffffff81bf9d9c)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_dev
```
```
In net/ipv6/route.c (ffffffff81c05480)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
```
```
In net/ipv6/ip6_fib.c (ffffffff81c12800)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_info_alloc
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81c1664d)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
```
```
In net/ipv6/mcast.c (ffffffff81c27946)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
```
```
In net/ipv6/exthdrs.c (ffffffff81c330c6)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_dup_options
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81c35a67)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:fl_create
```
```
In net/ipv6/ip6mr.c (ffffffff81c3e8c9)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/ipv6/calipso.c (ffffffff81c4688e)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_doi_add
```
```
In net/packet/af_packet.c (ffffffff81c55b44)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/packet/af_packet.c:fanout_add
  - net/packet/af_packet.c:fanout_add
  - net/packet/af_packet.c:fanout_add
```
```
In net/xdp/xdp_umem.c (ffffffff81c74f38)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_reg
```
```
In net/xdp/xsk_buff_pool.c (ffffffff81c76784)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_create_and_assign_umem
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
In arch/x86/kernel/ioport.c (ffffffff81046efb)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
  - arch/x86/kernel/ioport.c:ksys_ioperm
```
```
In arch/x86/kernel/tboot.c (ffffffff8345b225)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81067bc5)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:fake_panic_set
  - arch/x86/kernel/cpu/mce/core.c:fake_panic_set
  - arch/x86/kernel/cpu/mce/core.c:fake_panic_set
  - arch/x86/kernel/cpu/mce/core.c:fake_panic_set
  - arch/x86/kernel/cpu/mce/core.c:mce_end
  - arch/x86/kernel/cpu/mce/core.c:mce_end
  - arch/x86/kernel/cpu/mce/core.c:mce_end
  - arch/x86/kernel/cpu/mce/core.c:mce_start
  - arch/x86/kernel/cpu/mce/core.c:mce_start
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff8106c076)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:threshold_create_bank
```
```
In arch/x86/kernel/cpu/sgx/driver.c (ffffffff8107d7bd)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/driver.c:sgx_open
```
```
In arch/x86/kernel/reboot.c (ffffffff81084e16)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:nmi_shootdown_cpus
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff81088cb1)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_target
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
```
```
In arch/x86/kernel/kgdb.c (ffffffff8109c3ac)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/kgdb.c:kgdb_arch_handle_exception
  - arch/x86/kernel/kgdb.c:kgdb_arch_handle_exception
```
```
In arch/x86/mm/init_64.c (ffffffff81f1d274)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pagetable
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff8347a171)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_common
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus
```
```
In kernel/fork.c (ffffffff810ca86c)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_signal
  - kernel/fork.c:copy_signal
  - kernel/fork.c:mm_init
  - kernel/fork.c:mm_init
  - kernel/fork.c:mm_init
  - kernel/fork.c:dup_task_struct
  - kernel/fork.c:dup_task_struct
  - kernel/fork.c:dup_task_struct
```
```
In kernel/softirq.c (ffffffff810d3be5)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/softirq.c:tasklet_init
  - kernel/softirq.c:tasklet_setup
```
```
In kernel/user.c (ffffffff810dd0ce)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/user.c:alloc_uid
```
```
In kernel/workqueue.c (ffffffff810f5b72)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:flush_workqueue_prep_pwqs
```
```
In kernel/pid.c (ffffffff810f6c52)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/pid.c:alloc_pid
```
```
In kernel/nsproxy.c (ffffffff810ff095)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/nsproxy.c:create_new_namespaces
```
```
In kernel/cred.c (ffffffff81101a53)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:cred_alloc_blank
```
```
In kernel/smpboot.c (ffffffff8110479f)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/smpboot.c:cpu_wait_death
  - kernel/smpboot.c:cpu_check_up_prepare
```
```
In kernel/ucount.c (ffffffff81104cf1)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/ucount.c:alloc_ucounts
```
```
In kernel/groups.c (ffffffff811062f6)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/groups.c:__do_sys_setgroups
```
```
In kernel/sched/core.c (ffffffff8347cec7)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:affine_move_task
```
```
In kernel/sched/fair.c (ffffffff8111da2a)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_group
```
```
In kernel/sched/build_utility.c (ffffffff81144d4e)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sched_autogroup_create_attach
  - kernel/sched/build_utility.c:autogroup_init
  - kernel/sched/build_utility.c:membarrier_exec_mmap
  - kernel/sched/build_utility.c:psi_trigger_create
  - kernel/sched/build_utility.c:poll_timer_fn
  - kernel/sched/build_utility.c:sched_core_share_pid
  - kernel/sched/build_utility.c:sd_init
  - kernel/sched/build_utility.c:init_defrootdomain
  - kernel/sched/build_utility.c:cpupri_init
```
```
In kernel/locking/mutex.c (ffffffff8114d4b4)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/locking/mutex.c:__mutex_init
```
```
In kernel/locking/rwsem.c (ffffffff8114e00c)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:__init_rwsem
```
```
In kernel/locking/percpu-rwsem.c (ffffffff8114e8ac)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:__percpu_init_rwsem
```
```
In kernel/power/swap.c (ffffffff81157dc6)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:save_image
```
```
In kernel/irq/manage.c (ffffffff811630cd)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_notifier
```
```
In kernel/rcu/update.c (ffffffff81173ca5)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_trace_pregp_step
  - kernel/rcu/update.c:rcu_barrier_tasks_generic
```
```
In kernel/rcu/srcutree.c (ffffffff811771cd)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
```
```
In kernel/rcu/tree.c (ffffffff81178490)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/rcu/tree.c:kfree_rcu_shrink_count
  - kernel/rcu/tree.c:fill_page_cache_func
  - kernel/rcu/tree.c:fill_page_cache_func
```
```
In kernel/module/main.c (ffffffff8118f40e)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/module/main.c:load_module
```
```
In kernel/time/namespace.c (ffffffff811b1799)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/time/namespace.c:copy_time_ns
```
```
In kernel/futex/core.c (ffffffff834818dc)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/futex/core.c:futex_init
```
```
In kernel/futex/pi.c (ffffffff811b4af9)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/futex/pi.c:refill_pi_state_cache
```
```
In kernel/kexec_core.c (ffffffff811bd9f0)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_free_reserved_phys_range
  - kernel/kexec_core.c:crash_kexec
```
```
In kernel/cgroup/cgroup.c (ffffffff811c36e5)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:init_cgroup_root
  - kernel/cgroup/cgroup.c:find_css_set
```
```
In kernel/cgroup/namespace.c (ffffffff811ce948)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
```
```
In kernel/utsname.c (ffffffff811da475)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/utsname.c:clone_uts_ns
```
```
In kernel/user_namespace.c (ffffffff811dbff0)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In kernel/pid_namespace.c (ffffffff811dcae6)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/pid_namespace.c:create_pid_namespace
```
```
In kernel/stop_machine.c (ffffffff811de431)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:stop_core_cpuslocked
  - kernel/stop_machine.c:stop_core_cpuslocked
  - kernel/stop_machine.c:stop_machine_cpuslocked
  - kernel/stop_machine.c:stop_machine_cpuslocked
  - kernel/stop_machine.c:stop_two_cpus
  - kernel/stop_machine.c:stop_two_cpus
  - kernel/stop_machine.c:multi_cpu_stop
  - kernel/stop_machine.c:stop_one_cpu
```
```
In kernel/audit_watch.c (ffffffff811eb661)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_watch.c:audit_to_watch
```
```
In kernel/audit_tree.c (ffffffff811eca1a)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/audit_tree.c:alloc_tree
```
```
In kernel/debug/debug_core.c (ffffffff811f333d)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff811f918f)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
```
```
In kernel/hung_task.c (ffffffff811ff2c5)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/hung_task.c:reset_hung_task_detector
```
```
In kernel/seccomp.c (ffffffff81202b67)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_attach_filter
```
```
In kernel/relay.c (ffffffff81205367)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/relay.c:relay_open
  - kernel/relay.c:__relay_reset
```
```
In kernel/trace/trace.c (ffffffff8121bf33)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
```
```
In kernel/trace/tracing_map.c (ffffffff8122cdee)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_create
  - kernel/trace/tracing_map.c:tracing_map_clear
```
```
In kernel/trace/blktrace.c (ffffffff81235c47)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:do_blk_trace_setup
```
```
In kernel/trace/fgraph.c (ffffffff81238859)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/trace/fgraph.c:start_graph_tracing
  - kernel/trace/fgraph.c:ftrace_graph_init_task
```
```
In kernel/trace/trace_events.c (ffffffff8123c905)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_module_notify
  - kernel/trace/trace_events.c:trace_add_event_call
  - kernel/trace/trace_events.c:trace_create_new_event
  - kernel/trace/trace_events.c:trace_create_new_event
```
```
In kernel/trace/trace_dynevent.c (ffffffff812621b7)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/trace/trace_dynevent.c:trace_event_dyn_put_ref
```
```
In kernel/trace/rethook.c (ffffffff812690dc)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/trace/rethook.c:rethook_alloc
```
```
In kernel/irq_work.c (ffffffff812695b7)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_single
```
```
In kernel/bpf/trampoline.c (ffffffff812a97e3)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_get
```
```
In kernel/bpf/btf.c (ffffffff812ac5bb)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_parse_module
  - kernel/bpf/btf.c:btf_parse_vmlinux
  - kernel/bpf/btf.c:btf_parse
```
```
In kernel/bpf/dispatcher.c (ffffffff812b99f1)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/bpf/dispatcher.c:bpf_dispatcher_change_prog
```
```
In kernel/bpf/bpf_struct_ops.c (ffffffff812c6c14)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_sys_lookup_elem
```
```
In kernel/events/core.c (ffffffff812d683a)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:alloc_perf_context
```
```
In kernel/events/ring_buffer.c (ffffffff812e3a1f)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc
  - kernel/events/ring_buffer.c:rb_alloc_aux
  - kernel/events/ring_buffer.c:perf_aux_output_skip
  - kernel/events/ring_buffer.c:perf_aux_output_end
  - kernel/events/ring_buffer.c:perf_aux_output_begin
  - kernel/events/ring_buffer.c:perf_output_put_handle
```
```
In kernel/events/uprobes.c (ffffffff812e82ea)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__create_xol_area
  - kernel/events/uprobes.c:alloc_uprobe
```
```
In kernel/padata.c (ffffffff812e9e77)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/padata.c:padata_alloc_pd
```
```
In kernel/jump_label.c (ffffffff812eb089)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/jump_label.c:static_key_enable_cpuslocked
  - kernel/jump_label.c:static_key_slow_inc_cpuslocked
```
```
In kernel/watch_queue.c (ffffffff812edf8c)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/watch_queue.c:watch_queue_init
  - kernel/watch_queue.c:init_watch
```
```
In mm/filemap.c (ffffffff81e6b4af)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - mm/filemap.c:filemap_unaccount_folio
```
```
In mm/vmscan.c (ffffffff813128f9)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd
```
```
In mm/shmem.c (0)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
```
```
In mm/backing-dev.c (ffffffff81324206)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_init
  - mm/backing-dev.c:wb_init
```
```
In mm/rmap.c (ffffffff81360083)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - mm/rmap.c:hugepage_add_new_anon_rmap
  - mm/rmap.c:hugepage_add_new_anon_rmap
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:anon_vma_ctor
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:__anon_vma_prepare
```
```
In mm/page_alloc.c (ffffffff81371719)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:memmap_init_compound
  - mm/page_alloc.c:memmap_init_compound
  - mm/page_alloc.c:memmap_init_compound
  - mm/page_alloc.c:page_frag_alloc_align
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:split_page
  - mm/page_alloc.c:check_new_pages
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:prep_compound_page
  - mm/page_alloc.c:prep_compound_page
  - mm/page_alloc.c:bad_page
```
```
In mm/madvise.c (ffffffff81377f50)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - mm/madvise.c:anon_vma_name_alloc
```
```
In mm/swap_state.c (ffffffff8137c82b)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - mm/swap_state.c:init_swap_address_space
  - mm/swap_state.c:swap_cluster_readahead
```
```
In mm/frontswap.c (ffffffff8138415e)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_invalidate_area
```
```
In mm/zswap.c (ffffffff81384918)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - mm/zswap.c:zswap_pool_create
```
```
In mm/hugetlb.c (ffffffff81389adb)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - mm/hugetlb.c:demote_free_huge_page
  - mm/hugetlb.c:demote_free_huge_page
  - mm/hugetlb.c:alloc_and_dissolve_huge_page
  - mm/hugetlb.c:__prep_compound_gigantic_page
  - mm/hugetlb.c:__prep_compound_gigantic_page
  - mm/hugetlb.c:__prep_compound_gigantic_page
  - mm/hugetlb.c:__remove_hugetlb_page
  - mm/hugetlb.c:__destroy_compound_gigantic_page
  - mm/hugetlb.c:__destroy_compound_gigantic_page
  - mm/hugetlb.c:__destroy_compound_gigantic_page
  - mm/hugetlb.c:dequeue_huge_page_nodemask
  - mm/hugetlb.c:resv_map_alloc
```
```
In mm/mempolicy.c (ffffffff8139654c)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - mm/mempolicy.c:shared_policy_replace
  - mm/mempolicy.c:shared_policy_replace
  - mm/mempolicy.c:__mpol_dup
  - mm/mempolicy.c:mpol_new
```
```
In mm/kfence/core.c (ffffffff813ae6df)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
```
```
In mm/huge_memory.c (ffffffff813bbe90)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
```
```
In mm/memcontrol.c (ffffffff813cb6e6)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:__mem_cgroup_flush_stats
```
```
In mm/zpool.c (ffffffff813dec49)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - mm/zpool.c:zpool_register_driver
```
```
In mm/zsmalloc.c (ffffffff813e1e50)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:__free_zspage
```
```
In mm/memremap.c (ffffffff813e7c51)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - mm/memremap.c:free_zone_device_page
```
```
In mm/page_reporting.c (ffffffff813ead50)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - mm/page_reporting.c:page_reporting_register
  - mm/page_reporting.c:page_reporting_process
  - mm/page_reporting.c:page_reporting_cycle
```
```
In mm/bootmem_info.c (ffffffff813eaf0b)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - mm/bootmem_info.c:put_page_bootmem
```
```
In fs/super.c (ffffffff813f4a70)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/super.c:alloc_super
```
```
In fs/exec.c (ffffffff813fce3b)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/exec.c:begin_new_exec
```
```
In fs/dcache.c (ffffffff81411d55)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/dcache.c:__d_alloc
```
```
In fs/inode.c (ffffffff81415dfe)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/inode.c:inode_init_always
  - fs/inode.c:inode_init_always
  - fs/inode.c:inode_init_always
  - fs/inode.c:inode_init_always
```
```
In fs/file.c (ffffffff8141b8d8)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/file.c:dup_fd
```
```
In fs/namespace.c (ffffffff8141eab9)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In fs/fsopen.c (ffffffff81440c69)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/fsopen.c:__ia32_sys_fspick
  - fs/fsopen.c:__x64_sys_fspick
  - fs/fsopen.c:__ia32_sys_fsopen
  - fs/fsopen.c:__x64_sys_fsopen
```
```
In fs/notify/group.c (ffffffff8144eb69)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_alloc_group
  - fs/notify/group.c:fsnotify_alloc_group
```
```
In fs/notify/mark.c (ffffffff8144f2eb)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
```
```
In fs/eventfd.c (ffffffff8145c9c5)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/eventfd.c:do_eventfd
```
```
In fs/userfaultfd.c (ffffffff8145d88c)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/userfaultfd.c:__do_sys_userfaultfd
  - fs/userfaultfd.c:__do_sys_userfaultfd
  - fs/userfaultfd.c:dup_userfaultfd
  - fs/userfaultfd.c:dup_userfaultfd
```
```
In fs/aio.c (ffffffff81465222)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:__ia32_sys_io_destroy
  - fs/aio.c:__x64_sys_io_destroy
  - fs/aio.c:exit_aio
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
```
```
In fs/crypto/keyring.c (ffffffff8146d0a4)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/crypto/keyring.c:add_new_master_key
```
```
In fs/crypto/keysetup_v1.c (ffffffff8146f84e)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_get_direct_key
```
```
In fs/mbcache.c (ffffffff814821ae)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/posix_acl.c (ffffffff81482f3c)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/posix_acl.c:posix_acl_from_mode
  - fs/posix_acl.c:posix_acl_clone
```
```
In fs/coredump.c (ffffffff81484812)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/coredump.c:coredump_wait
```
```
In fs/iomap/direct-io.c (ffffffff8148d2b5)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:__iomap_dio_rw
```
```
In fs/quota/dquot.c (ffffffff81490592)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/quota/dquot.c:dqget
```
```
In fs/proc/generic.c (ffffffff814a403d)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/proc/generic.c:__proc_create
```
```
In fs/kernfs/inode.c (ffffffff814b229f)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
```
```
In fs/kernfs/dir.c (ffffffff814b32ce)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/kernfs/dir.c:__kernfs_new_node
  - fs/kernfs/dir.c:__kernfs_new_node
```
```
In fs/kernfs/file.c (ffffffff814b6051)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_fop_open
```
```
In fs/configfs/dir.c (ffffffff814bc9bd)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_register_group
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_new_dirent
```
```
In fs/configfs/item.c (ffffffff814bdb6c)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/configfs/item.c:config_group_init_type_name
  - fs/configfs/item.c:config_item_init_type_name
```
```
In fs/ext4/mballoc.c (ffffffff814fb5e0)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_init
```
```
In fs/ext4/page-io.c (ffffffff81508dbb)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_init_io_end
```
```
In fs/ext4/super.c (ffffffff8152d7c7)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:ext4_alloc_inode
  - fs/ext4/super.c:ext4_alloc_inode
```
```
In fs/ext4/fast_commit.c (ffffffff81537db5)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_init_inode
```
```
In fs/ext4/orphan.c (ffffffff8153ae79)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/ext4/orphan.c:ext4_init_orphan_info
```
```
In fs/jbd2/transaction.c (ffffffff8153dbda)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
```
```
In fs/jbd2/journal.c (ffffffff8154955d)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_init_common
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/ecryptfs/main.c (ffffffff81e83d9c)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_get_lower_file
```
```
In fs/ecryptfs/super.c (ffffffff815689b4)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/ecryptfs/super.c:ecryptfs_alloc_inode
```
```
In fs/ecryptfs/miscdev.c (ffffffff83498d56)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/ecryptfs/miscdev.c:ecryptfs_init_ecryptfs_miscdev
```
```
In fs/fuse/dev.c (ffffffff81574ec2)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_get_req
```
```
In fs/fuse/file.c (ffffffff815814d5)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_file_alloc
```
```
In fs/fuse/inode.c (ffffffff815866e4)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_fill_super_common
  - fs/fuse/inode.c:fuse_conn_init
  - fs/fuse/inode.c:fuse_conn_init
  - fs/fuse/inode.c:fuse_conn_init
  - fs/fuse/inode.c:fuse_sync_fs_writes
```
```
In fs/fuse/dax.c (ffffffff8158b17c)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
```
```
In fs/debugfs/file.c (ffffffff8158ddd5)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_atomic_t_set
  - fs/debugfs/file.c:debugfs_file_get
```
```
In ipc/util.c (ffffffff81593f05)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In ipc/msg.c (ffffffff834992ec)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - ipc/msg.c:msg_init
  - ipc/msg.c:msg_init
```
```
In ipc/sem.c (ffffffff8159bd25)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - ipc/sem.c:copy_semundo
  - ipc/sem.c:find_alloc_undo
```
```
In ipc/namespace.c (ffffffff815a3162)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
```
```
In security/keys/key.c (ffffffff815a51d3)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_user_lookup
  - security/keys/key.c:key_user_lookup
  - security/keys/key.c:key_user_lookup
```
```
In security/selinux/avc.c (ffffffff815c0942)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - security/selinux/avc.c:selinux_avc_init
  - security/selinux/avc.c:selinux_avc_init
```
```
In security/selinux/ss/services.c (ffffffff815e52ee)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
```
```
In security/smack/smack_access.c (ffffffff815f09da)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - security/smack/smack_access.c:smack_populate_secattr
```
```
In security/tomoyo/condition.c (ffffffff815fd7ec)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_commit_condition
```
```
In security/tomoyo/gc.c (ffffffff81603ba3)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - security/tomoyo/gc.c:tomoyo_collect_entry
  - security/tomoyo/gc.c:tomoyo_collect_entry
  - security/tomoyo/gc.c:tomoyo_collect_entry
```
```
In security/tomoyo/memory.c (ffffffff81604917)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_name
  - security/tomoyo/memory.c:tomoyo_get_group
```
```
In security/apparmor/apparmorfs.c (ffffffff8160d2ad)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_write_access
```
```
In security/apparmor/lib.c (ffffffff816115f9)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - security/apparmor/lib.c:aa_str_alloc
```
```
In security/apparmor/match.c (ffffffff816123f1)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
```
```
In security/apparmor/policy_unpack.c (ffffffff8161f8cb)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:aa_loaddata_alloc
```
```
In security/apparmor/policy_ns.c (ffffffff816295fb)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:alloc_ns
```
```
In security/apparmor/label.c (ffffffff8162ba7c)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_alloc
  - security/apparmor/label.c:aa_alloc_proxy
```
```
In security/landlock/object.c (ffffffff816384c7)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - security/landlock/object.c:landlock_create_object
```
```
In security/landlock/ruleset.c (ffffffff81638e5c)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - security/landlock/ruleset.c:landlock_merge_ruleset
  - security/landlock/ruleset.c:landlock_merge_ruleset
  - security/landlock/ruleset.c:landlock_create_ruleset
```
```
In security/integrity/ima/ima_policy.c (ffffffff8349ea48)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_init_policy
```
```
In crypto/api.c (ffffffff8164b82c)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - crypto/api.c:crypto_alg_mod_lookup
```
```
In crypto/algapi.c (ffffffff8164c90d)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - crypto/algapi.c:__crypto_register_alg
  - crypto/algapi.c:crypto_check_alg
```
```
In block/fops.c (ffffffff81670a39)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - block/fops.c:__blkdev_direct_IO
```
```
In block/bio.c (ffffffff816723a5)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - block/bio.c:bio_init_clone
  - block/bio.c:bio_init_clone
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_reset
```
```
In block/blk-core.c (ffffffff81678fc3)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - block/blk-core.c:blk_alloc_queue
```
```
In block/blk-flush.c (ffffffff8167be71)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - block/blk-flush.c:blk_flush_complete_seq
```
```
In block/blk-ioc.c (ffffffff8167d6ef)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - block/blk-ioc.c:alloc_io_context
```
```
In block/blk-mq.c (ffffffff81686767)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_hctx
```
```
In block/bsg-lib.c (ffffffff816a0d0a)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_queue_rq
```
```
In block/blk-cgroup.c (ffffffff816a211a)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_css_alloc
```
```
In block/blk-iocost.c (ffffffff816ae5c0)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - block/blk-iocost.c:blk_iocost_init
```
```
In block/blk-wbt.c (ffffffff816bae1d)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_init
```
```
In block/blk-crypto-profile.c (ffffffff816c27fa)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - block/blk-crypto-profile.c:blk_crypto_get_keyslot
```
```
In io_uring/io_uring.c (ffffffff81e8ebe7)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_uring_alloc_task_context
  - io_uring/io_uring.c:io_uring_alloc_task_context
  - io_uring/io_uring.c:io_uring_alloc_task_context
  - io_uring/io_uring.c:io_get_sq_data
  - io_uring/io_uring.c:io_get_sq_data
  - io_uring/io_uring.c:io_rsrc_data_alloc
  - io_uring/io_uring.c:io_wq_submit_work
  - io_uring/io_uring.c:io_timeout_fn
  - io_uring/io_uring.c:io_poll_add_prep
  - io_uring/io_uring.c:__io_arm_poll_handler
  - io_uring/io_uring.c:__io_arm_ltimeout
  - io_uring/io_uring.c:__io_arm_ltimeout
```
```
In io_uring/io-wq.c (ffffffff816db86e)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_wq_create
  - io_uring/io-wq.c:io_wq_create
  - io_uring/io-wq.c:create_io_worker
```
```
In lib/rhashtable.c (ffffffff816e99c0)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_init
```
```
In lib/refcount.c (ffffffff816eb36b)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - lib/refcount.c:refcount_dec_and_lock_irqsave
  - lib/refcount.c:refcount_dec_and_lock
  - lib/refcount.c:refcount_dec_and_mutex_lock
```
```
In lib/cpu_rmap.c (ffffffff81762022)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - lib/cpu_rmap.c:alloc_cpu_rmap
```
```
In lib/sbitmap.c (ffffffff817724c4)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbq_wake_up
  - lib/sbitmap.c:sbitmap_queue_min_shallow_depth
  - lib/sbitmap.c:sbitmap_queue_resize
  - lib/sbitmap.c:sbitmap_queue_recalculate_wake_batch
  - lib/sbitmap.c:sbitmap_queue_init_node
  - lib/sbitmap.c:sbitmap_queue_init_node
  - lib/sbitmap.c:sbitmap_queue_init_node
```
```
In lib/klist.c (ffffffff81778c17)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - lib/klist.c:klist_add_before
  - lib/klist.c:klist_add_behind
  - lib/klist.c:klist_add_tail
  - lib/klist.c:klist_add_head
```
```
In lib/kobject.c (ffffffff8177a54b)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - lib/kobject.c:kset_create_and_add
  - lib/kobject.c:kobject_create_and_add
```
```
In drivers/pinctrl/core.c (ffffffff81796308)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:create_pinctrl
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff817acc73)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:linereq_create
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff817efe94)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
```
```
In drivers/rapidio/rio.c (ffffffff817fdddd)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_register_mport
  - drivers/rapidio/rio.c:rio_mport_initialize
  - drivers/rapidio/rio.c:rio_del_device
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff818087c1)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:do_register_framebuffer
```
```
In drivers/acpi/ec.c (ffffffff818331d4)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_add_query_handler
```
```
In drivers/acpi/thermal.c (ffffffff81893203)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/acpi/thermal.c:acpi_thermal_add
```
```
In drivers/acpi/apei/ghes.c (ffffffff8189e984)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_alloc
```
```
In drivers/clk/clk.c (ffffffff818afe6c)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_core_init
```
```
In drivers/dma/dmaengine.c (ffffffff818b75c8)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaengine_get_unmap_data
  - drivers/dma/dmaengine.c:dma_async_device_register
```
```
In drivers/xen/balloon.c (ffffffff818ca846)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_thread
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff818d8c14)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_open
```
```
In drivers/reset/core.c (ffffffff818eeaa6)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/reset/core.c:__reset_control_get_internal
```
```
In drivers/tty/tty_io.c (ffffffff818f42e5)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:alloc_tty_struct
```
```
In drivers/tty/tty_buffer.c (ffffffff818fbd2d)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_init
  - drivers/tty/tty_buffer.c:tty_buffer_init
```
```
In drivers/tty/tty_port.c (ffffffff818fc022)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_init
```
```
In drivers/tty/serial/serial_core.c (ffffffff8191c5e1)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_add_one_port
```
```
In drivers/char/virtio_console.c (ffffffff819376cf)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
```
```
In drivers/char/hw_random/core.c (ffffffff8193b225)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:set_current_rng
```
```
In drivers/char/agp/backend.c (ffffffff8193c554)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/char/agp/backend.c:agp_alloc_bridge
  - drivers/char/agp/backend.c:agp_alloc_bridge
```
```
In drivers/iommu/dma-iommu.c (ffffffff8196c67f)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_init_fq
  - drivers/iommu/dma-iommu.c:fq_flush_timeout
```
```
In drivers/connector/cn_queue.c (ffffffff819719ea)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/connector/cn_queue.c:cn_queue_alloc_dev
  - drivers/connector/cn_queue.c:cn_queue_add_callback
```
```
In drivers/base/core.c (ffffffff819785a2)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/power/runtime.c (ffffffff819922d6)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_init
  - drivers/base/power/runtime.c:pm_runtime_init
```
```
In drivers/base/power/wakeup.c (ffffffff819982f0)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:pm_wakeup_clear
```
```
In drivers/base/power/domain.c (ffffffff8199ae28)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/base/power/domain.c:pm_genpd_init
```
```
In drivers/base/firmware_loader/main.c (ffffffff8199f7a1)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:alloc_lookup_fw_priv
```
```
In drivers/block/loop.c (ffffffff819b70af)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
```
```
In drivers/nvdimm/core.c (ffffffff819d456d)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:alloc_nvdimm_map
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff819d805a)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:__nvdimm_create
```
```
In drivers/nvdimm/dimm.c (ffffffff819d9574)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
```
```
In drivers/dax/bus.c (ffffffff819eb062)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/dax/bus.c:alloc_dax_region
```
```
In drivers/dma-buf/dma-fence.c (ffffffff819ee60d)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
```
```
In drivers/dma-buf/dma-fence-array.c (ffffffff819ef570)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_create
```
```
In drivers/dma-buf/sw_sync.c (ffffffff819f4a3a)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open
```
```
In drivers/scsi/scsi.c (ffffffff819f8228)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_finish_command
  - drivers/scsi/scsi.c:scsi_finish_command
  - drivers/scsi/scsi.c:scsi_finish_command
```
```
In drivers/scsi/scsi_lib.c (ffffffff81a0305a)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:__scsi_queue_insert
  - drivers/scsi/scsi_lib.c:__scsi_queue_insert
  - drivers/scsi/scsi_lib.c:__scsi_queue_insert
```
```
In drivers/scsi/scsi_scan.c (ffffffff81a04e63)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
```
```
In drivers/scsi/sd.c (ffffffff81a13d4b)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
```
```
In drivers/scsi/sg.c (ffffffff81a1dfde)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_add_sfp
  - drivers/scsi/sg.c:sg_alloc
  - drivers/scsi/sg.c:sg_alloc
```
```
In drivers/ata/libata-core.c (ffffffff81a22614)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_init
  - drivers/ata/libata-core.c:ata_host_alloc
```
```
In drivers/net/phy/phy_device.c (ffffffff81a58d70)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_package_join
```
```
In drivers/net/phy/sfp-bus.c (ffffffff81a5d662)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_bus_get
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81a69fbd)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
```
```
In drivers/vfio/vfio.c (ffffffff81a772e0)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_fops_open
  - drivers/vfio/vfio.c:__vfio_register_dev
  - drivers/vfio/vfio.c:vfio_create_group
```
```
In drivers/usb/core/usb.c (ffffffff81a901e0)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/usb/core/usb.c:usb_alloc_dev
```
```
In drivers/usb/core/hub.c (ffffffff81edfcec)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_probe
```
```
In drivers/usb/core/hcd.c (ffffffff81a9a1f0)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:__usb_create_hcd
```
```
In drivers/usb/core/urb.c (ffffffff81a9c65f)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_init_urb
```
```
In drivers/usb/core/config.c (ffffffff81ee1a4d)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_configuration
```
```
In drivers/usb/core/file.c (ffffffff81aa5093)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/usb/core/file.c:usb_register_dev
```
```
In drivers/thermal/thermal_core.c (ffffffff81b49525)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
```
```
In drivers/thermal/intel/therm_throt.c (ffffffff81b52424)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/thermal/intel/therm_throt.c:intel_init_thermal
```
```
In drivers/md/md.c (ffffffff81ef3d65)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_run
  - drivers/md/md.c:max_corrected_read_errors_store
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:errors_store
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:mddev_init
  - drivers/md/md.c:mddev_init
  - drivers/md/md.c:mddev_init
  - drivers/md/md.c:mddev_init
  - drivers/md/md.c:submit_flushes
```
```
In drivers/md/md-bitmap.c (ffffffff81b6c4c4)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
```
```
In drivers/md/dm.c (ffffffff81b712f8)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:dm_split_and_process_bio
  - drivers/md/dm.c:dm_get_table_device
```
```
In drivers/md/dm-table.c (ffffffff81b759f9)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_get_device
```
```
In drivers/md/dm-stripe.c (ffffffff81b78820)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:stripe_ctr
```
```
In drivers/md/dm-io.c (ffffffff81b7cb40)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/md/dm-io.c:dm_io
  - drivers/md/dm-io.c:sync_io
```
```
In drivers/md/dm-kcopyd.c (ffffffff81b7d3d1)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
  - drivers/md/dm-kcopyd.c:dm_kcopyd_copy
```
```
In drivers/md/dm-stats.c (ffffffff81b7fd5b)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
```
```
In drivers/edac/ghes_edac.c (ffffffff81b86ce5)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/edac/ghes_edac.c:ghes_edac_register
```
```
In drivers/opp/core.c (ffffffff81b8b8d9)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/opp/core.c:_opp_add
  - drivers/opp/core.c:_add_opp_table_indexed
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff81b94a40)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_stop
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
  - drivers/cpufreq/cpufreq_governor.c:dbs_update_util_handler
  - drivers/cpufreq/cpufreq_governor.c:dbs_work_handler
```
```
In drivers/mmc/core/sdio_irq.c (ffffffff81bb779d)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_irq.c:sdio_release_irq
  - drivers/mmc/core/sdio_irq.c:sdio_claim_irq
```
```
In drivers/firmware/efi/efi.c (ffffffff81f1c9ab)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81bcc7ce)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
```
```
In drivers/devfreq/devfreq.c (ffffffff81bd4936)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
```
In drivers/nvmem/core.c (ffffffff81be0bf3)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/nvmem/core.c:nvmem_register
```
```
In drivers/hte/hte.c (ffffffff81be4b4a)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/hte/hte.c:hte_ts_put
```
```
In net/core/sock.c (ffffffff81bec716)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_alloc
  - net/core/sock.c:sock_set_timestamping
  - net/core/sock.c:sock_set_timestamping
```
```
In net/core/skbuff.c (ffffffff81bff9a2)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_ext_add
  - net/core/skbuff.c:__skb_ext_alloc
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:pskb_carve_inside_header
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:msg_zerocopy_realloc
  - net/core/skbuff.c:msg_zerocopy_realloc
  - net/core/skbuff.c:__skb_clone
  - net/core/skbuff.c:__alloc_skb
  - net/core/skbuff.c:__build_skb_around
  - net/core/skbuff.c:__build_skb_around
```
```
In net/core/net_namespace.c (ffffffff81c05e85)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/core/net_namespace.c:copy_net_ns
  - net/core/net_namespace.c:copy_net_ns
  - net/core/net_namespace.c:setup_net
  - net/core/net_namespace.c:setup_net
```
```
In net/core/dev.c (ffffffff81c0f38a)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/core/dev.c:__dev_kfree_skb_irq
```
```
In net/core/dst.c (ffffffff81c21ff5)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/core/dst.c:__metadata_dst_init
  - net/core/dst.c:dst_cow_metrics_generic
  - net/core/dst.c:dst_alloc
```
```
In net/core/neighbour.c (ffffffff81c25577)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:neigh_alloc
```
```
In net/core/filter.c (ffffffff81c4c369)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/core/filter.c:__sk_attach_prog
```
```
In net/core/flow_offload.c (ffffffff81c52b57)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/core/flow_offload.c:flow_indr_dev_register
```
```
In net/core/gro.c (ffffffff81c549fa)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/core/gro.c:skb_gro_receive
```
```
In net/core/page_pool.c (ffffffff81c58d52)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_init
  - net/core/page_pool.c:page_pool_init
```
```
In net/core/netpoll.c (ffffffff81c5c107)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/core/netpoll.c:__netpoll_setup
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:zap_completion_queue
```
```
In net/core/fib_rules.c (ffffffff81c5ddce)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_default_rule_add
```
```
In net/core/devlink.c (ffffffff81c7e993)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_linecard_create
  - net/core/devlink.c:devlink_alloc_ns
  - net/core/devlink.c:__devlink_health_reporter_create
  - net/core/devlink.c:devlink_nl_cmd_rate_new_doit
```
```
In net/core/skmsg.c (ffffffff81c8b418)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_init
```
```
In net/sched/sch_generic.c (ffffffff81c96811)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_alloc
```
```
In net/sched/cls_api.c (ffffffff81ca2ce6)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tcf_block_get_ext
```
```
In net/sched/act_api.c (ffffffff81ca4baf)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_idr_create
  - net/sched/act_api.c:tcf_idr_create
```
```
In net/ipv4/route.c (ffffffff81ccc9b5)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_genid_init
  - net/ipv4/route.c:rt_genid_init
  - net/ipv4/route.c:rt_genid_init
```
```
In net/ipv4/inetpeer.c (ffffffff81cd49b3)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81ce3514)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ce5458)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_complete_hashdance
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_hash_add
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
```
```
In net/ipv4/tcp.c (ffffffff81ce97c2)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_skb_entail
```
```
In net/ipv4/tcp_input.c (ffffffff81cf1df2)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/tcp_output.c (ffffffff81cfd74d)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_queue_skb
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tso_fragment
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81d08c5e)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_sk_init
  - net/ipv4/tcp_ipv4.c:tcp_sk_init
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81d13912)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_create_child
```
```
In net/ipv4/devinet.c (ffffffff81d2a270)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_init
```
```
In net/ipv4/igmp.c (ffffffff81d316c8)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/ipv4/igmp.c:____ip_mc_inc_group
```
```
In net/ipv4/fib_frontend.c (ffffffff81d344b2)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
```
```
In net/ipv4/fib_semantics.c (ffffffff81d3a57a)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_rebalance
```
```
In net/ipv4/inet_fragment.c (ffffffff81d4223a)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_find
  - net/ipv4/inet_fragment.c:inet_frags_init
```
```
In net/ipv4/metrics.c (ffffffff81d475c3)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
```
```
In net/ipv4/nexthop.c (ffffffff81d4ded5)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:nh_hthr_group_rebalance
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81d4e2cf)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:proc_tfo_blackhole_detect_timeout
```
```
In net/ipv4/ipmr.c (ffffffff81d571e2)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv4/syncookies.c (ffffffff81d5a522)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:tcp_get_cookie_sock
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81d5f2da)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff81d62ed3)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
```
```
In net/xfrm/xfrm_state.c (ffffffff81d6d0ef)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
```
```
In net/unix/af_unix.c (ffffffff81d7ff0f)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_autobind
  - net/unix/af_unix.c:unix_create_addr
```
```
In net/ipv6/af_inet6.c (ffffffff81d84e9d)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_net_init
```
```
In net/ipv6/anycast.c (ffffffff81d86339)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
```
```
In net/ipv6/addrconf.c (ffffffff81d93175)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_dev
```
```
In net/ipv6/route.c (ffffffff81d9df0c)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ip6_dst_gc
  - net/ipv6/route.c:ip6_dst_gc
```
```
In net/ipv6/ip6_fib.c (ffffffff81dadcfe)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_info_alloc
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81db1d27)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
```
```
In net/ipv6/mcast.c (ffffffff81dc4cc5)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
```
```
In net/ipv6/exthdrs.c (ffffffff81dd0825)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_dup_options
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81dd34f7)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:fl_create
```
```
In net/ipv6/ip6mr.c (ffffffff81ddd07b)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/ipv6/calipso.c (ffffffff81de531d)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_doi_add
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff81deb876)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_build_state
```
```
In net/packet/af_packet.c (ffffffff81df1b7d)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/packet/af_packet.c:fanout_add
  - net/packet/af_packet.c:fanout_add
  - net/packet/af_packet.c:fanout_add
```
```
In net/xdp/xdp_umem.c (ffffffff81e19164)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_reg
```
```
In net/xdp/xsk_buff_pool.c (ffffffff81e1a61c)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_dma_map
  - net/xdp/xsk_buff_pool.c:xp_create_and_assign_umem
```
```
In net/mctp/device.c (ffffffff81e38368)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/mctp/device.c:mctp_add_dev
```
```
In net/mctp/route.c (ffffffff81e399f2)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/mctp/route.c:mctp_route_add
  - net/mctp/route.c:mctp_key_alloc
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
In arch/x86/kernel/ioport.c (ffffffff8105105b)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
  - arch/x86/kernel/ioport.c:ksys_ioperm
```
```
In arch/x86/kernel/tboot.c (ffffffff83e7b545)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81077515)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:fake_panic_set
  - arch/x86/kernel/cpu/mce/core.c:fake_panic_set
  - arch/x86/kernel/cpu/mce/core.c:fake_panic_set
  - arch/x86/kernel/cpu/mce/core.c:fake_panic_set
  - arch/x86/kernel/cpu/mce/core.c:mce_end
  - arch/x86/kernel/cpu/mce/core.c:mce_end
  - arch/x86/kernel/cpu/mce/core.c:mce_end
  - arch/x86/kernel/cpu/mce/core.c:mce_start
  - arch/x86/kernel/cpu/mce/core.c:mce_start
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff8107c090)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:threshold_create_bank
```
```
In arch/x86/kernel/cpu/sgx/driver.c (ffffffff8108ed1d)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/driver.c:sgx_open
```
```
In arch/x86/kernel/reboot.c (ffffffff81098157)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:nmi_shootdown_cpus
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff8109c8d0)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_target
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
```
```
In arch/x86/kernel/kgdb.c (ffffffff810b308c)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/kgdb.c:kgdb_arch_handle_exception
  - arch/x86/kernel/kgdb.c:kgdb_arch_handle_exception
```
```
In arch/x86/mm/init_64.c (ffffffff820c53da)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pagetable
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff83ea479c)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_common
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_dump_state
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus
```
```
In kernel/fork.c (ffffffff810e4ebb)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/fork.c:copy_signal
  - kernel/fork.c:copy_signal
  - kernel/fork.c:copy_sighand
  - kernel/fork.c:mm_init
  - kernel/fork.c:mm_init
  - kernel/fork.c:mm_init
  - kernel/fork.c:dup_task_struct
  - kernel/fork.c:dup_task_struct
  - kernel/fork.c:dup_task_struct
```
```
In kernel/softirq.c (ffffffff810f2975)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/softirq.c:tasklet_init
  - kernel/softirq.c:tasklet_setup
```
```
In kernel/user.c (ffffffff810fd3ee)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/user.c:alloc_uid
```
```
In kernel/workqueue.c (ffffffff811180b2)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:flush_workqueue_prep_pwqs
```
```
In kernel/pid.c (ffffffff81119332)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/pid.c:alloc_pid
```
```
In kernel/nsproxy.c (ffffffff81123d85)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/nsproxy.c:create_new_namespaces
```
```
In kernel/cred.c (ffffffff81126c23)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:cred_alloc_blank
```
```
In kernel/smpboot.c (ffffffff8112a00b)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/smpboot.c:cpu_wait_death
  - kernel/smpboot.c:cpu_check_up_prepare
```
```
In kernel/ucount.c (ffffffff8112a601)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/ucount.c:alloc_ucounts
```
```
In kernel/groups.c (ffffffff8112bf43)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/groups.c:__do_sys_setgroups
```
```
In kernel/sched/core.c (ffffffff83ea82e5)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:affine_move_task
```
```
In kernel/sched/fair.c (ffffffff81144dcd)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_group
```
```
In kernel/sched/build_utility.c (ffffffff8117113e)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sched_autogroup_create_attach
  - kernel/sched/build_utility.c:autogroup_init
  - kernel/sched/build_utility.c:membarrier_exec_mmap
  - kernel/sched/build_utility.c:psi_trigger_destroy
  - kernel/sched/build_utility.c:psi_trigger_create
  - kernel/sched/build_utility.c:psi_group_change
  - kernel/sched/build_utility.c:poll_timer_fn
  - kernel/sched/build_utility.c:psi_poll_worker
  - kernel/sched/build_utility.c:psi_poll_worker
  - kernel/sched/build_utility.c:group_init
  - kernel/sched/build_utility.c:sched_core_share_pid
  - kernel/sched/build_utility.c:sd_init
  - kernel/sched/build_utility.c:init_defrootdomain
  - kernel/sched/build_utility.c:cpupri_init
```
```
In kernel/locking/mutex.c (ffffffff8117c594)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/locking/mutex.c:__mutex_init
```
```
In kernel/locking/rwsem.c (ffffffff8117cf5c)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:__init_rwsem
```
```
In kernel/locking/percpu-rwsem.c (ffffffff8117d94c)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:__percpu_init_rwsem
```
```
In kernel/power/swap.c (ffffffff81188d76)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:save_image
```
```
In kernel/irq/manage.c (ffffffff81196cdd)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_notifier
```
```
In kernel/rcu/update.c (ffffffff811aae5a)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_barrier_tasks_generic
```
```
In kernel/rcu/srcutree.c (ffffffff811ae8bd)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
```
```
In kernel/rcu/tree.c (ffffffff811b1cd0)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/rcu/tree.c:kfree_rcu_shrink_count
  - kernel/rcu/tree.c:fill_page_cache_func
  - kernel/rcu/tree.c:fill_page_cache_func
```
```
In kernel/module/main.c (ffffffff811cc320)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/module/main.c:load_module
```
```
In kernel/time/namespace.c (ffffffff811f24e9)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/time/namespace.c:copy_time_ns
```
```
In kernel/futex/core.c (ffffffff83eaea84)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/futex/core.c:futex_init
```
```
In kernel/futex/pi.c (ffffffff811f5bb9)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/futex/pi.c:refill_pi_state_cache
```
```
In kernel/kexec_core.c (ffffffff811ffb24)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_shrink_memory
  - kernel/kexec_core.c:crash_kexec
```
```
In kernel/cgroup/cgroup.c (ffffffff812057f5)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:init_cgroup_root
  - kernel/cgroup/cgroup.c:find_css_set
```
```
In kernel/cgroup/namespace.c (ffffffff812121c8)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
```
```
In kernel/utsname.c (ffffffff8121fa35)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/utsname.c:clone_uts_ns
```
```
In kernel/user_namespace.c (ffffffff81221850)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In kernel/pid_namespace.c (ffffffff81222446)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/pid_namespace.c:create_pid_namespace
```
```
In kernel/stop_machine.c (ffffffff81223f81)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:stop_core_cpuslocked
  - kernel/stop_machine.c:stop_core_cpuslocked
  - kernel/stop_machine.c:stop_machine_cpuslocked
  - kernel/stop_machine.c:stop_machine_cpuslocked
  - kernel/stop_machine.c:stop_two_cpus
  - kernel/stop_machine.c:stop_two_cpus
  - kernel/stop_machine.c:multi_cpu_stop
  - kernel/stop_machine.c:stop_one_cpu
```
```
In kernel/audit_watch.c (ffffffff81231a61)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_watch.c:audit_to_watch
```
```
In kernel/audit_tree.c (ffffffff81232f5a)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/audit_tree.c:alloc_tree
```
```
In kernel/debug/debug_core.c (ffffffff8123a0c9)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff8124067f)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
```
```
In kernel/hung_task.c (ffffffff81246be5)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/hung_task.c:reset_hung_task_detector
```
```
In kernel/seccomp.c (ffffffff8124a9c7)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_attach_filter
```
```
In kernel/relay.c (ffffffff8124d438)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/relay.c:relay_open
  - kernel/relay.c:__relay_reset
```
```
In kernel/trace/trace.c (ffffffff81265c04)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
```
```
In kernel/trace/tracing_map.c (ffffffff81278a4e)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_create
  - kernel/trace/tracing_map.c:tracing_map_clear
```
```
In kernel/trace/blktrace.c (ffffffff81282687)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:do_blk_trace_setup
```
```
In kernel/trace/fgraph.c (ffffffff812856f9)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/trace/fgraph.c:start_graph_tracing
  - kernel/trace/fgraph.c:ftrace_graph_init_task
```
```
In kernel/trace/trace_events.c (ffffffff81289f95)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_module_notify
  - kernel/trace/trace_events.c:trace_add_event_call
  - kernel/trace/trace_events.c:trace_create_new_event
  - kernel/trace/trace_events.c:trace_create_new_event
```
```
In kernel/trace/trace_dynevent.c (ffffffff812b3957)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/trace/trace_dynevent.c:trace_event_dyn_put_ref
```
```
In kernel/trace/rethook.c (ffffffff812bb41c)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/trace/rethook.c:rethook_alloc
```
```
In kernel/irq_work.c (ffffffff812be457)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_single
```
```
In kernel/bpf/ringbuf.c (ffffffff81304c41)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/bpf/ringbuf.c:bpf_user_ringbuf_drain
  - kernel/bpf/ringbuf.c:bpf_ringbuf_alloc
```
```
In kernel/bpf/trampoline.c (ffffffff8130867c)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_lookup
```
```
In kernel/bpf/btf.c (ffffffff8130bf3b)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_parse_module
  - kernel/bpf/btf.c:btf_parse_vmlinux
  - kernel/bpf/btf.c:btf_parse
```
```
In kernel/bpf/memalloc.c (ffffffff8131bbb0)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/bpf/memalloc.c:__free_rcu_tasks_trace
```
```
In kernel/bpf/dispatcher.c (ffffffff8131cbbc)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/bpf/dispatcher.c:bpf_dispatcher_change_prog
```
```
In kernel/bpf/bpf_struct_ops.c (ffffffff8132c484)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_sys_lookup_elem
```
```
In kernel/events/core.c (ffffffff83eb950a)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:find_get_pmu_context
  - kernel/events/core.c:find_get_pmu_context
  - kernel/events/core.c:alloc_perf_context
```
```
In kernel/events/ring_buffer.c (ffffffff8134c0cf)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc
  - kernel/events/ring_buffer.c:rb_alloc_aux
  - kernel/events/ring_buffer.c:perf_aux_output_skip
  - kernel/events/ring_buffer.c:perf_aux_output_end
  - kernel/events/ring_buffer.c:perf_aux_output_begin
  - kernel/events/ring_buffer.c:perf_output_put_handle
```
```
In kernel/events/uprobes.c (ffffffff81352068)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__create_xol_area
  - kernel/events/uprobes.c:alloc_uprobe
```
```
In kernel/padata.c (ffffffff81353dda)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/padata.c:padata_alloc_pd
```
```
In kernel/jump_label.c (ffffffff813550c9)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/jump_label.c:static_key_enable_cpuslocked
  - kernel/jump_label.c:static_key_slow_inc_cpuslocked
```
```
In kernel/watch_queue.c (ffffffff813583bc)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - kernel/watch_queue.c:watch_queue_init
  - kernel/watch_queue.c:init_watch
```
```
In mm/filemap.c (ffffffff81359a51)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - mm/filemap.c:filemap_unaccount_folio
```
```
In mm/vmscan.c (ffffffff81385d40)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd
```
```
In mm/shmem.c (0)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
```
```
In mm/backing-dev.c (ffffffff81398b06)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_init
  - mm/backing-dev.c:wb_init
```
```
In mm/rmap.c (ffffffff813daff3)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - mm/rmap.c:hugepage_add_new_anon_rmap
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:anon_vma_ctor
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:__anon_vma_prepare
```
```
In mm/page_alloc.c (ffffffff813eee49)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:init_unavailable_range
  - mm/page_alloc.c:init_unavailable_range
  - mm/page_alloc.c:memmap_init_compound
  - mm/page_alloc.c:memmap_init_compound
  - mm/page_alloc.c:memmap_init_compound
  - mm/page_alloc.c:memmap_init_compound
  - mm/page_alloc.c:__init_zone_device_page
  - mm/page_alloc.c:__init_zone_device_page
  - mm/page_alloc.c:__init_zone_device_page
  - mm/page_alloc.c:memmap_init_range
  - mm/page_alloc.c:memmap_init_range
  - mm/page_alloc.c:make_alloc_exact
  - mm/page_alloc.c:page_frag_alloc_align
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:split_page
  - mm/page_alloc.c:check_new_pages
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:prep_compound_page
  - mm/page_alloc.c:prep_compound_page
  - mm/page_alloc.c:prep_compound_page
  - mm/page_alloc.c:bad_page
```
```
In mm/madvise.c (ffffffff813f5850)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - mm/madvise.c:anon_vma_name_alloc
```
```
In mm/swap_state.c (ffffffff813f9ffb)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - mm/swap_state.c:init_swap_address_space
  - mm/swap_state.c:swap_cluster_readahead
```
```
In mm/frontswap.c (ffffffff81401c6e)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_invalidate_area
```
```
In mm/zswap.c (ffffffff81402548)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - mm/zswap.c:zswap_pool_create
```
```
In mm/hugetlb.c (ffffffff8140a942)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - mm/hugetlb.c:demote_free_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:__prep_compound_gigantic_folio
  - mm/hugetlb.c:__prep_compound_gigantic_folio
  - mm/hugetlb.c:__prep_compound_gigantic_folio
  - mm/hugetlb.c:__prep_compound_gigantic_folio
  - mm/hugetlb.c:__destroy_compound_gigantic_folio
  - mm/hugetlb.c:__destroy_compound_gigantic_folio
  - mm/hugetlb.c:__destroy_compound_gigantic_folio
  - mm/hugetlb.c:__destroy_compound_gigantic_folio
  - mm/hugetlb.c:dequeue_huge_page_nodemask
  - mm/hugetlb.c:resv_map_alloc
```
```
In mm/mempolicy.c (ffffffff81415e5c)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - mm/mempolicy.c:shared_policy_replace
  - mm/mempolicy.c:shared_policy_replace
  - mm/mempolicy.c:__mpol_dup
  - mm/mempolicy.c:mpol_new
```
```
In mm/kfence/core.c (ffffffff8142eb6f)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
```
```
In mm/memory-tiers.c (ffffffff83ec697e)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - mm/memory-tiers.c:memory_tier_init
```
```
In mm/huge_memory.c (ffffffff8143e3d8)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - mm/huge_memory.c:mm_get_huge_zero_page
```
```
In mm/memcontrol.c (ffffffff814503b6)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:__mem_cgroup_flush_stats
```
```
In mm/zpool.c (ffffffff81465919)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - mm/zpool.c:zpool_register_driver
```
```
In mm/zsmalloc.c (ffffffff81469433)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:__free_zspage
```
```
In mm/memremap.c (ffffffff8146f84a)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - mm/memremap.c:zone_device_page_init
  - mm/memremap.c:free_zone_device_page
```
```
In mm/page_reporting.c (ffffffff81472ef9)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - mm/page_reporting.c:page_reporting_register
  - mm/page_reporting.c:page_reporting_process
  - mm/page_reporting.c:page_reporting_cycle
```
```
In mm/bootmem_info.c (ffffffff8147310b)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - mm/bootmem_info.c:put_page_bootmem
```
```
In fs/super.c (ffffffff8147db80)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/super.c:alloc_super
```
```
In fs/exec.c (ffffffff81483e2e)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/exec.c:unshare_sighand
```
```
In fs/dcache.c (ffffffff8149cab5)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/dcache.c:__d_alloc
```
```
In fs/inode.c (ffffffff814a126e)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/inode.c:inode_init_always
  - fs/inode.c:inode_init_always
  - fs/inode.c:inode_init_always
  - fs/inode.c:inode_init_always
```
```
In fs/file.c (ffffffff814a7a18)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/file.c:dup_fd
```
```
In fs/namespace.c (ffffffff814ab529)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In fs/fsopen.c (ffffffff814cfb69)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/fsopen.c:__ia32_sys_fspick
  - fs/fsopen.c:__x64_sys_fspick
  - fs/fsopen.c:__ia32_sys_fsopen
  - fs/fsopen.c:__x64_sys_fsopen
```
```
In fs/notify/group.c (ffffffff814dd2fe)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_alloc_group
  - fs/notify/group.c:fsnotify_alloc_group
```
```
In fs/notify/mark.c (ffffffff814ddb1b)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_init_mark
```
```
In fs/eventfd.c (ffffffff814ec0a5)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/eventfd.c:do_eventfd
```
```
In fs/userfaultfd.c (ffffffff814ecd85)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/userfaultfd.c:new_userfaultfd
  - fs/userfaultfd.c:new_userfaultfd
  - fs/userfaultfd.c:dup_userfaultfd
  - fs/userfaultfd.c:dup_userfaultfd
```
```
In fs/aio.c (ffffffff814f5262)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:__ia32_sys_io_destroy
  - fs/aio.c:__x64_sys_io_destroy
  - fs/aio.c:exit_aio
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
```
```
In fs/crypto/keyring.c (ffffffff814fe827)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
```
```
In fs/crypto/keysetup_v1.c (ffffffff8150101e)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_get_direct_key
```
```
In fs/mbcache.c (ffffffff81514d16)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/posix_acl.c (ffffffff815161a8)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/posix_acl.c:posix_acl_from_mode
  - fs/posix_acl.c:posix_acl_clone
```
```
In fs/coredump.c (ffffffff81517d12)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/coredump.c:coredump_wait
```
```
In fs/iomap/direct-io.c (ffffffff81520815)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:__iomap_dio_rw
```
```
In fs/quota/dquot.c (ffffffff81524112)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/quota/dquot.c:dqget
```
```
In fs/proc/generic.c (ffffffff8153944d)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/proc/generic.c:__proc_create
```
```
In fs/kernfs/inode.c (ffffffff81548e13)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
```
```
In fs/kernfs/dir.c (ffffffff81549f3e)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/kernfs/dir.c:__kernfs_new_node
  - fs/kernfs/dir.c:__kernfs_new_node
```
```
In fs/kernfs/file.c (ffffffff8154d600)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_fop_open
```
```
In fs/configfs/dir.c (ffffffff8155451d)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_register_group
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_new_dirent
```
```
In fs/configfs/item.c (ffffffff8155589c)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/configfs/item.c:config_group_init_type_name
  - fs/configfs/item.c:config_item_init_type_name
```
```
In fs/ext4/mballoc.c (ffffffff81595cd9)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_init
```
```
In fs/ext4/page-io.c (ffffffff815a392b)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_init_io_end
```
```
In fs/ext4/super.c (ffffffff815cb989)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:ext4_alloc_inode
  - fs/ext4/super.c:ext4_alloc_inode
```
```
In fs/ext4/fast_commit.c (ffffffff815d5f95)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_init_inode
```
```
In fs/ext4/orphan.c (ffffffff815d9435)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/ext4/orphan.c:ext4_init_orphan_info
```
```
In fs/jbd2/transaction.c (ffffffff815dc44a)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
```
```
In fs/jbd2/journal.c (ffffffff815e95cd)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_init_common
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/ecryptfs/main.c (ffffffff8160bfb4)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_get_lower_file
```
```
In fs/ecryptfs/super.c (ffffffff8160c324)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/ecryptfs/super.c:ecryptfs_alloc_inode
```
```
In fs/ecryptfs/miscdev.c (ffffffff83ece9e5)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/ecryptfs/miscdev.c:ecryptfs_init_ecryptfs_miscdev
```
```
In fs/fuse/dev.c (ffffffff81619563)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_request_alloc
```
```
In fs/fuse/file.c (ffffffff81627335)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_file_alloc
```
```
In fs/fuse/inode.c (ffffffff8162c974)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_fill_super_common
  - fs/fuse/inode.c:fuse_conn_init
  - fs/fuse/inode.c:fuse_conn_init
  - fs/fuse/inode.c:fuse_conn_init
  - fs/fuse/inode.c:fuse_sync_fs_writes
```
```
In fs/fuse/dax.c (ffffffff8163197c)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
```
```
In fs/debugfs/file.c (ffffffff81634b75)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_atomic_t_set
  - fs/debugfs/file.c:debugfs_file_get
```
```
In ipc/util.c (ffffffff8163cac5)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In ipc/sem.c (ffffffff81645115)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - ipc/sem.c:copy_semundo
  - ipc/sem.c:find_alloc_undo
```
```
In ipc/namespace.c (ffffffff8164cd12)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
```
```
In security/keys/key.c (ffffffff8164efc3)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_user_lookup
  - security/keys/key.c:key_user_lookup
  - security/keys/key.c:key_user_lookup
```
```
In security/selinux/avc.c (ffffffff8166cef2)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - security/selinux/avc.c:selinux_avc_init
  - security/selinux/avc.c:selinux_avc_init
```
```
In security/selinux/ss/services.c (ffffffff8169473e)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
```
```
In security/smack/smack_access.c (ffffffff816a0e0a)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - security/smack/smack_access.c:smack_populate_secattr
```
```
In security/tomoyo/condition.c (ffffffff816ae65c)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_commit_condition
```
```
In security/tomoyo/gc.c (ffffffff816b4d73)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - security/tomoyo/gc.c:tomoyo_collect_entry
  - security/tomoyo/gc.c:tomoyo_collect_entry
  - security/tomoyo/gc.c:tomoyo_collect_entry
```
```
In security/tomoyo/memory.c (ffffffff816b5c07)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_name
  - security/tomoyo/memory.c:tomoyo_get_group
```
```
In security/apparmor/apparmorfs.c (ffffffff816bf21d)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_write_access
```
```
In security/apparmor/lib.c (ffffffff816c4299)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - security/apparmor/lib.c:aa_str_alloc
```
```
In security/apparmor/match.c (ffffffff816c50a1)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
```
```
In security/apparmor/policy_unpack.c (ffffffff816d2cdb)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:aa_loaddata_alloc
```
```
In security/apparmor/policy_ns.c (ffffffff816ddc49)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:alloc_ns
```
```
In security/apparmor/label.c (ffffffff816e035b)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_alloc
  - security/apparmor/label.c:aa_alloc_proxy
```
```
In security/apparmor/notify.c (ffffffff816ea702)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - security/apparmor/notify.c:aa_new_listener
  - security/apparmor/notify.c:aa_new_listener
```
```
In security/landlock/object.c (ffffffff816ef927)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - security/landlock/object.c:landlock_create_object
```
```
In security/landlock/ruleset.c (ffffffff816f037c)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - security/landlock/ruleset.c:landlock_merge_ruleset
  - security/landlock/ruleset.c:landlock_merge_ruleset
  - security/landlock/ruleset.c:landlock_create_ruleset
```
```
In security/integrity/ima/ima_policy.c (ffffffff83ed69ca)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_init_policy
```
```
In crypto/api.c (ffffffff817048cc)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - crypto/api.c:crypto_alg_mod_lookup
```
```
In crypto/algapi.c (ffffffff81705153)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_check_alg
```
```
In block/fops.c (ffffffff8172c0d3)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - block/fops.c:__blkdev_direct_IO
```
```
In block/bio.c (ffffffff8172dcf5)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - block/bio.c:bio_init_clone
  - block/bio.c:bio_init_clone
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_reset
```
```
In block/blk-core.c (ffffffff81735451)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - block/blk-core.c:blk_alloc_queue
  - block/blk-core.c:blk_alloc_queue
```
```
In block/blk-flush.c (ffffffff817386ef)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - block/blk-flush.c:blk_flush_complete_seq
```
```
In block/blk-ioc.c (ffffffff8173a2cf)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - block/blk-ioc.c:alloc_io_context
```
```
In block/blk-mq.c (ffffffff81745027)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_hctx
```
```
In block/bsg-lib.c (ffffffff8175f8aa)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_queue_rq
```
```
In block/blk-cgroup.c (ffffffff817617ec)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_css_alloc
```
```
In block/blk-iocost.c (ffffffff8176d2bc)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
```
```
In block/blk-wbt.c (ffffffff8177b4cd)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_init
```
```
In block/blk-crypto-profile.c (ffffffff81783b5a)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - block/blk-crypto-profile.c:blk_crypto_get_keyslot
```
```
In io_uring/io_uring.c (ffffffff81788bbe)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_eventfd_register
  - io_uring/io_uring.c:io_eventfd_register
  - io_uring/io_uring.c:io_wq_submit_work
  - io_uring/io_uring.c:__io_arm_ltimeout
  - io_uring/io_uring.c:__io_arm_ltimeout
```
```
In io_uring/timeout.c (ffffffff81799f7e)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - io_uring/timeout.c:io_kill_timeouts
  - io_uring/timeout.c:io_timeout_fn
  - io_uring/timeout.c:io_flush_timeouts
```
```
In io_uring/sqpoll.c (ffffffff8179a0d3)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - io_uring/sqpoll.c:io_get_sq_data
  - io_uring/sqpoll.c:io_get_sq_data
```
```
In io_uring/tctx.c (ffffffff8179bbf6)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - io_uring/tctx.c:io_uring_alloc_task_context
  - io_uring/tctx.c:io_uring_alloc_task_context
  - io_uring/tctx.c:io_uring_alloc_task_context
```
```
In io_uring/poll.c (ffffffff8179d3eb)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - io_uring/poll.c:__io_arm_poll_handler
```
```
In io_uring/rsrc.c (ffffffff817a06fe)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - io_uring/rsrc.c:io_rsrc_data_alloc
```
```
In io_uring/notif.c (ffffffff817a5312)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - io_uring/notif.c:io_alloc_notif
```
```
In io_uring/io-wq.c (ffffffff817a7947)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_wq_create
  - io_uring/io-wq.c:io_wq_create
  - io_uring/io-wq.c:create_io_worker
```
```
In lib/rhashtable.c (ffffffff817d9b60)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_init
```
```
In lib/refcount.c (ffffffff817dba1b)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - lib/refcount.c:refcount_dec_and_lock_irqsave
  - lib/refcount.c:refcount_dec_and_lock
  - lib/refcount.c:refcount_dec_and_mutex_lock
```
```
In lib/cpu_rmap.c (ffffffff818911e3)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - lib/cpu_rmap.c:alloc_cpu_rmap
```
```
In lib/sbitmap.c (ffffffff818a2d97)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_queue_wake_up
  - lib/sbitmap.c:sbitmap_queue_init_node
  - lib/sbitmap.c:sbitmap_queue_init_node
  - lib/sbitmap.c:sbitmap_queue_init_node
  - lib/sbitmap.c:sbitmap_queue_init_node
```
```
In drivers/pinctrl/core.c (ffffffff818ab9be)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:create_pinctrl
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff818c5f48)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:linereq_create
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff81918044)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
```
```
In drivers/rapidio/rio.c (ffffffff8192af2d)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_register_mport
  - drivers/rapidio/rio.c:rio_mport_initialize
  - drivers/rapidio/rio.c:rio_del_device
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff819368aa)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:do_register_framebuffer
```
```
In drivers/acpi/ec.c (ffffffff81966cb4)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_add_query_handler
```
```
In drivers/acpi/thermal.c (ffffffff819dabee)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/acpi/thermal.c:acpi_thermal_add
```
```
In drivers/acpi/apei/ghes.c (ffffffff819e7ca4)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_alloc
```
```
In drivers/clk/clk.c (ffffffff819fc1bf)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_core_init
```
```
In drivers/dma/dmaengine.c (ffffffff81a044f8)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaengine_get_unmap_data
  - drivers/dma/dmaengine.c:dma_async_device_register
```
```
In drivers/xen/balloon.c (ffffffff81a1b3f2)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_thread
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff81a2b674)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_open
```
```
In drivers/reset/core.c (ffffffff81a46706)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/reset/core.c:__reset_control_get_internal
```
```
In drivers/tty/tty_io.c (ffffffff81a4cb54)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:alloc_tty_struct
```
```
In drivers/tty/tty_buffer.c (ffffffff81a55161)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_init
  - drivers/tty/tty_buffer.c:tty_buffer_init
```
```
In drivers/tty/tty_port.c (ffffffff81a55592)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_init
```
```
In drivers/tty/serial/serial_core.c (ffffffff81a78591)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_add_one_port
```
```
In drivers/char/random.c (ffffffff81a94d91)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/char/random.c:try_to_generate_entropy
```
```
In drivers/char/virtio_console.c (ffffffff81a97bdf)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
```
```
In drivers/char/hw_random/core.c (ffffffff81a9b8fc)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
```
```
In drivers/char/agp/backend.c (ffffffff81a9cf84)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/char/agp/backend.c:agp_alloc_bridge
  - drivers/char/agp/backend.c:agp_alloc_bridge
```
```
In drivers/iommu/dma-iommu.c (ffffffff81ad6cc8)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_init_fq
  - drivers/iommu/dma-iommu.c:fq_flush_timeout
```
```
In drivers/connector/cn_queue.c (ffffffff81adcbda)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/connector/cn_queue.c:cn_queue_alloc_dev
  - drivers/connector/cn_queue.c:cn_queue_alloc_callback_entry
```
```
In drivers/base/core.c (ffffffff81ae4e5c)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/power/runtime.c (ffffffff81b02716)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_init
  - drivers/base/power/runtime.c:pm_runtime_init
```
```
In drivers/base/power/wakeup.c (ffffffff81b09350)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:pm_wakeup_clear
```
```
In drivers/base/power/domain.c (ffffffff81b0bf88)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/base/power/domain.c:pm_genpd_init
```
```
In drivers/base/firmware_loader/main.c (ffffffff81b11241)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:alloc_lookup_fw_priv
```
```
In drivers/block/loop.c (ffffffff81b2c385)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
```
```
In drivers/nvdimm/core.c (ffffffff81b4edbd)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:alloc_nvdimm_map
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff81b52f0a)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:__nvdimm_create
```
```
In drivers/nvdimm/dimm.c (ffffffff81b54654)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
```
```
In drivers/dax/bus.c (ffffffff81b67bc2)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/dax/bus.c:alloc_dax_region
```
```
In drivers/dma-buf/dma-fence.c (ffffffff81b6baad)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
```
```
In drivers/dma-buf/dma-fence-array.c (ffffffff81b6cb20)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_create
```
```
In drivers/dma-buf/sw_sync.c (ffffffff81b71e9a)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open
```
```
In drivers/scsi/scsi.c (ffffffff81b75bf8)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_finish_command
  - drivers/scsi/scsi.c:scsi_finish_command
  - drivers/scsi/scsi.c:scsi_finish_command
```
```
In drivers/scsi/hosts.c (ffffffff81b76e66)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/scsi/scsi_lib.c (ffffffff81b81c09)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:__scsi_queue_insert
  - drivers/scsi/scsi_lib.c:__scsi_queue_insert
  - drivers/scsi/scsi_lib.c:__scsi_queue_insert
```
```
In drivers/scsi/scsi_scan.c (ffffffff81b83b13)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
```
```
In drivers/scsi/sd.c (ffffffff81b94126)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
```
```
In drivers/scsi/sg.c (ffffffff81b9f30e)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_add_sfp
  - drivers/scsi/sg.c:sg_alloc
  - drivers/scsi/sg.c:sg_alloc
```
```
In drivers/ata/libata-core.c (ffffffff81ba3d54)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_init
  - drivers/ata/libata-core.c:ata_host_alloc
```
```
In drivers/net/phy/phy_device.c (ffffffff81be2af0)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_package_join
```
```
In drivers/net/phy/sfp-bus.c (ffffffff81be8212)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_bus_get
```
```
In drivers/net/pse-pd/pse_core.c (0)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81bfcbbd)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
```
```
In drivers/usb/core/usb.c (ffffffff81c120e0)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/usb/core/usb.c:usb_alloc_dev
```
```
In drivers/usb/core/hub.c (ffffffff81c1cb36)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_probe
```
```
In drivers/usb/core/hcd.c (ffffffff81c1e770)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:__usb_create_hcd
```
```
In drivers/usb/core/urb.c (ffffffff81c215cf)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_init_urb
```
```
In drivers/usb/core/config.c (ffffffff81c2a6d9)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_configuration
```
```
In drivers/usb/core/file.c (ffffffff81c2ba33)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/usb/core/file.c:usb_register_dev
```
```
In drivers/thermal/thermal_core.c (ffffffff81ce0ad7)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register_with_trips
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
```
```
In drivers/thermal/intel/therm_throt.c (ffffffff81cea5e4)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/thermal/intel/therm_throt.c:intel_init_thermal
```
```
In drivers/md/md.c (ffffffff81cf9da9)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_run
  - drivers/md/md.c:max_corrected_read_errors_store
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:errors_store
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:mddev_init
  - drivers/md/md.c:mddev_init
  - drivers/md/md.c:mddev_init
  - drivers/md/md.c:mddev_init
  - drivers/md/md.c:submit_flushes
```
```
In drivers/md/md-bitmap.c (ffffffff81d08592)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
```
```
In drivers/md/dm.c (ffffffff81d0e108)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:dm_split_and_process_bio
  - drivers/md/dm.c:dm_get_table_device
```
```
In drivers/md/dm-table.c (ffffffff81d12d29)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_get_device
```
```
In drivers/md/dm-stripe.c (ffffffff81d15e60)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:stripe_ctr
```
```
In drivers/md/dm-io.c (ffffffff81d1a9f3)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/md/dm-io.c:dm_io
  - drivers/md/dm-io.c:sync_io
```
```
In drivers/md/dm-kcopyd.c (ffffffff81d1b290)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
  - drivers/md/dm-kcopyd.c:dm_kcopyd_copy
```
```
In drivers/md/dm-stats.c (ffffffff81d1d46b)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
```
```
In drivers/edac/ghes_edac.c (ffffffff81d25cc6)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
```
```
In drivers/opp/core.c (ffffffff81d2aff1)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/opp/core.c:_opp_add
  - drivers/opp/core.c:_add_opp_table_indexed
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff81d34e78)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_stop
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
  - drivers/cpufreq/cpufreq_governor.c:dbs_update_util_handler
  - drivers/cpufreq/cpufreq_governor.c:dbs_work_handler
```
```
In drivers/mmc/core/sdio_irq.c (ffffffff81d5c34d)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_irq.c:sdio_release_irq
  - drivers/mmc/core/sdio_irq.c:sdio_claim_irq
```
```
In drivers/firmware/efi/efi.c (ffffffff820c4a04)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81d76e9a)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc
```
```
In drivers/devfreq/devfreq.c (ffffffff81d80a34)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
```
In drivers/nvmem/core.c (ffffffff81d8c4dd)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/nvmem/core.c:nvmem_register
```
```
In drivers/hte/hte.c (ffffffff81d90c09)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - drivers/hte/hte.c:hte_ts_put
```
```
In net/core/sock.c (ffffffff81d9a59b)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/core/sock.c:sock_init_data_uid
  - net/core/sock.c:sock_init_data_uid
  - net/core/sock.c:sock_init_data_uid
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_alloc
  - net/core/sock.c:sock_set_timestamping
  - net/core/sock.c:sock_set_timestamping
  - net/core/sock.c:sock_set_timestamping
```
```
In net/core/skbuff.c (ffffffff81da4eef)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_ext_maybe_cow
  - net/core/skbuff.c:__skb_ext_alloc
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:pskb_carve_inside_header
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:msg_zerocopy_realloc
  - net/core/skbuff.c:msg_zerocopy_realloc
  - net/core/skbuff.c:__skb_clone
  - net/core/skbuff.c:__alloc_skb
  - net/core/skbuff.c:__build_skb_around
  - net/core/skbuff.c:__build_skb_around
  - net/core/skbuff.c:slab_build_skb
  - net/core/skbuff.c:slab_build_skb
```
```
In net/core/net_namespace.c (ffffffff81db5785)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/core/net_namespace.c:copy_net_ns
  - net/core/net_namespace.c:copy_net_ns
  - net/core/net_namespace.c:setup_net
  - net/core/net_namespace.c:setup_net
```
```
In net/core/dev.c (ffffffff81dbf10d)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/core/dev.c:__dev_kfree_skb_irq
```
```
In net/core/dst.c (ffffffff81dd4155)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/core/dst.c:__metadata_dst_init
  - net/core/dst.c:dst_cow_metrics_generic
  - net/core/dst.c:dst_alloc
```
```
In net/core/neighbour.c (ffffffff81dd8907)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:neigh_alloc
```
```
In net/core/filter.c (ffffffff81e010e9)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/core/filter.c:__sk_attach_prog
```
```
In net/core/flow_offload.c (ffffffff81e08117)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/core/flow_offload.c:flow_indr_dev_register
```
```
In net/core/gro.c (ffffffff81e0a1aa)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/core/gro.c:skb_gro_receive
```
```
In net/core/page_pool.c (ffffffff81e0ec42)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_init
  - net/core/page_pool.c:page_pool_init
```
```
In net/core/netpoll.c (ffffffff81e125b2)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/core/netpoll.c:__netpoll_setup
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:zap_completion_queue
```
```
In net/core/fib_rules.c (ffffffff81e145be)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_default_rule_add
```
```
In net/core/devlink.c (ffffffff81e376a3)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_linecard_create
  - net/core/devlink.c:devlink_alloc_ns
  - net/core/devlink.c:__devlink_health_reporter_create
  - net/core/devlink.c:devlink_nl_cmd_rate_new_doit
```
```
In net/core/skmsg.c (ffffffff81e47823)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_init
```
```
In net/sched/sch_generic.c (ffffffff81e52420)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_alloc
```
```
In net/sched/cls_api.c (ffffffff81e6051b)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tcf_block_get_ext
```
```
In net/sched/act_api.c (ffffffff81e6196f)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_idr_create
  - net/sched/act_api.c:tcf_idr_create
```
```
In net/ipv4/route.c (ffffffff81e8c965)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_genid_init
  - net/ipv4/route.c:rt_genid_init
  - net/ipv4/route.c:rt_genid_init
```
```
In net/ipv4/inetpeer.c (ffffffff81e94c93)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81ea59e4)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ea8648)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_complete_hashdance
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_hash_add
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
```
```
In net/ipv4/tcp.c (ffffffff81ead502)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_skb_entail
```
```
In net/ipv4/tcp_input.c (ffffffff81eb6662)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/tcp_output.c (ffffffff81ec235d)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_queue_skb
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tso_fragment
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ecd7f8)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_sk_init
  - net/ipv4/tcp_ipv4.c:tcp_sk_init
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81ed98d2)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_create_child
```
```
In net/ipv4/devinet.c (ffffffff81ef1d60)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_init
```
```
In net/ipv4/igmp.c (ffffffff81ef9ea7)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/ipv4/igmp.c:____ip_mc_inc_group
```
```
In net/ipv4/fib_frontend.c (ffffffff81efc992)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
```
```
In net/ipv4/fib_semantics.c (ffffffff81f02eda)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_rebalance
```
```
In net/ipv4/inet_fragment.c (ffffffff81f0b07a)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_find
  - net/ipv4/inet_fragment.c:inet_frags_init
```
```
In net/ipv4/metrics.c (ffffffff81f10a43)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
```
```
In net/ipv4/nexthop.c (ffffffff81f17815)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:nh_hthr_group_rebalance
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81f17c6f)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:proc_tfo_blackhole_detect_timeout
```
```
In net/ipv4/ipmr.c (ffffffff81f2087f)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv4/syncookies.c (ffffffff81f24952)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:tcp_get_cookie_sock
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81f2997a)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f2daa1)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
```
```
In net/xfrm/xfrm_state.c (ffffffff81f3855f)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
```
```
In net/unix/af_unix.c (ffffffff81f4bc71)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_autobind
  - net/unix/af_unix.c:unix_create_addr
```
```
In net/ipv6/af_inet6.c (ffffffff81f52a34)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_net_init
```
```
In net/ipv6/anycast.c (ffffffff81f53e89)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
```
```
In net/ipv6/addrconf.c (ffffffff81f61905)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_dev
```
```
In net/ipv6/route.c (ffffffff81f6ceec)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ip6_dst_gc
  - net/ipv6/route.c:ip6_dst_gc
```
```
In net/ipv6/ip6_fib.c (ffffffff81f7d7b2)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_info_alloc
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81f80b32)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt
```
```
In net/ipv6/mcast.c (ffffffff81f95815)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
```
```
In net/ipv6/exthdrs.c (ffffffff81fa1bf5)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_dup_options
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81fa4aa7)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:fl_create
```
```
In net/ipv6/ip6mr.c (ffffffff81fae501)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/ipv6/calipso.c (ffffffff81fb7aed)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_doi_add
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff81fbf4d6)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_build_state
```
```
In net/packet/af_packet.c (ffffffff81fc5b4d)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/packet/af_packet.c:fanout_add
  - net/packet/af_packet.c:fanout_add
  - net/packet/af_packet.c:fanout_add
```
```
In net/xdp/xdp_umem.c (ffffffff81ff0304)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_reg
```
```
In net/xdp/xsk_buff_pool.c (ffffffff81ff1b39)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_dma_map
  - net/xdp/xsk_buff_pool.c:xp_create_and_assign_umem
```
```
In net/mctp/device.c (ffffffff820115c8)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/mctp/device.c:mctp_add_dev
```
```
In net/mctp/route.c (ffffffff82012ac2)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - net/mctp/route.c:mctp_route_add
  - net/mctp/route.c:mctp_key_alloc
```
```
In lib/klist.c (ffffffff82021a07)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - lib/klist.c:klist_add_before
  - lib/klist.c:klist_add_behind
  - lib/klist.c:klist_add_tail
  - lib/klist.c:klist_add_head
```
```
In lib/kobject.c (ffffffff820230ae)
Location: arch/x86/include/asm/atomic.h:39
Inline: True
Inline callers:
  - lib/kobject.c:kset_register
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
In arch/x86/kernel/ioport.c (ffffffff81051d8c)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
  - arch/x86/kernel/ioport.c:ksys_ioperm
```
```
In arch/x86/kernel/tboot.c (ffffffff8369dbcf)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81079775)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:fake_panic_set
  - arch/x86/kernel/cpu/mce/core.c:fake_panic_set
  - arch/x86/kernel/cpu/mce/core.c:fake_panic_set
  - arch/x86/kernel/cpu/mce/core.c:fake_panic_set
  - arch/x86/kernel/cpu/mce/core.c:mce_end
  - arch/x86/kernel/cpu/mce/core.c:mce_end
  - arch/x86/kernel/cpu/mce/core.c:mce_end
  - arch/x86/kernel/cpu/mce/core.c:mce_start
  - arch/x86/kernel/cpu/mce/core.c:mce_start
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff8107e3f8)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:threshold_create_bank
```
```
In arch/x86/kernel/cpu/sgx/driver.c (ffffffff81091c0d)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/driver.c:sgx_open
```
```
In arch/x86/kernel/reboot.c (ffffffff8109b207)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:nmi_shootdown_cpus
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff8109f81d)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_target
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
```
```
In arch/x86/kernel/kgdb.c (ffffffff810b618d)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - arch/x86/kernel/kgdb.c:kgdb_arch_handle_exception
  - arch/x86/kernel/kgdb.c:kgdb_arch_handle_exception
```
```
In arch/x86/mm/init_64.c (ffffffff8214943a)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pagetable
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff836c8b1c)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_common
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_dump_state
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus
```
```
In kernel/fork.c (ffffffff810f055b)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - kernel/fork.c:copy_signal
  - kernel/fork.c:copy_signal
  - kernel/fork.c:copy_sighand
  - kernel/fork.c:mm_init
  - kernel/fork.c:mm_init
  - kernel/fork.c:mm_init
  - kernel/fork.c:dup_task_struct
  - kernel/fork.c:dup_task_struct
  - kernel/fork.c:dup_task_struct
```
```
In kernel/cpu.c (ffffffff836c9f7a)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - kernel/cpu.c:boot_cpu_hotplug_init
```
```
In kernel/softirq.c (ffffffff810fea35)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - kernel/softirq.c:tasklet_init
  - kernel/softirq.c:tasklet_setup
```
```
In kernel/user.c (ffffffff8110941e)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - kernel/user.c:alloc_uid
```
```
In kernel/workqueue.c (ffffffff811252e4)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:flush_workqueue_prep_pwqs
```
```
In kernel/pid.c (ffffffff81126802)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - kernel/pid.c:alloc_pid
```
```
In kernel/nsproxy.c (ffffffff81131051)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - kernel/nsproxy.c:create_new_namespaces
```
```
In kernel/cred.c (ffffffff811340c3)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:cred_alloc_blank
```
```
In kernel/ucount.c (ffffffff81137651)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - kernel/ucount.c:alloc_ucounts
```
```
In kernel/groups.c (ffffffff81138da3)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - kernel/groups.c:__do_sys_setgroups
```
```
In kernel/sched/core.c (ffffffff836ccbb5)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:affine_move_task
```
```
In kernel/sched/fair.c (ffffffff811552e6)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_group
```
```
In kernel/sched/build_utility.c (ffffffff8118193e)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sched_autogroup_create_attach
  - kernel/sched/build_utility.c:autogroup_init
  - kernel/sched/build_utility.c:membarrier_exec_mmap
  - kernel/sched/build_utility.c:psi_trigger_destroy
  - kernel/sched/build_utility.c:psi_trigger_create
  - kernel/sched/build_utility.c:psi_group_change
  - kernel/sched/build_utility.c:poll_timer_fn
  - kernel/sched/build_utility.c:psi_rtpoll_work
  - kernel/sched/build_utility.c:psi_rtpoll_work
  - kernel/sched/build_utility.c:group_init
  - kernel/sched/build_utility.c:sched_core_share_pid
  - kernel/sched/build_utility.c:sd_init
  - kernel/sched/build_utility.c:init_defrootdomain
  - kernel/sched/build_utility.c:cpupri_init
```
```
In kernel/locking/mutex.c (ffffffff8118d274)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - kernel/locking/mutex.c:__mutex_init
```
```
In kernel/locking/rwsem.c (ffffffff8118dc0c)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:__init_rwsem
```
```
In kernel/locking/percpu-rwsem.c (ffffffff8118e5ec)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:__percpu_init_rwsem
```
```
In kernel/power/swap.c (ffffffff81199f26)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:save_image
```
```
In kernel/irq/manage.c (ffffffff811a878d)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_notifier
```
```
In kernel/rcu/update.c (ffffffff811bcd81)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_barrier_tasks_generic
```
```
In kernel/rcu/srcutree.c (ffffffff811c08ae)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
```
```
In kernel/rcu/tree.c (ffffffff811c3afe)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - kernel/rcu/tree.c:kfree_rcu_shrink_count
  - kernel/rcu/tree.c:fill_page_cache_func
  - kernel/rcu/tree.c:fill_page_cache_func
  - kernel/rcu/tree.c:kfree_rcu_monitor
  - kernel/rcu/tree.c:kfree_rcu_monitor
  - kernel/rcu/tree.c:kfree_rcu_monitor
```
```
In kernel/module/main.c (ffffffff811df6c9)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - kernel/module/main.c:load_module
```
```
In kernel/time/namespace.c (ffffffff81206c69)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - kernel/time/namespace.c:copy_time_ns
```
```
In kernel/futex/core.c (ffffffff836d3a46)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - kernel/futex/core.c:futex_init
```
```
In kernel/futex/pi.c (ffffffff8120a3b9)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - kernel/futex/pi.c:refill_pi_state_cache
```
```
In kernel/kexec_core.c (ffffffff812138b5)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - kernel/kexec_core.c:__crash_shrink_memory
  - kernel/kexec_core.c:crash_kexec
```
```
In kernel/cgroup/cgroup.c (ffffffff8121b265)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:init_cgroup_root
  - kernel/cgroup/cgroup.c:find_css_set
```
```
In kernel/cgroup/namespace.c (ffffffff81227b0c)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
```
```
In kernel/utsname.c (ffffffff81235c25)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - kernel/utsname.c:clone_uts_ns
```
```
In kernel/user_namespace.c (ffffffff81237d05)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In kernel/pid_namespace.c (ffffffff81238a7d)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - kernel/pid_namespace.c:create_pid_namespace
```
```
In kernel/stop_machine.c (ffffffff8123a5a1)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:stop_core_cpuslocked
  - kernel/stop_machine.c:stop_machine_cpuslocked
  - kernel/stop_machine.c:stop_two_cpus
  - kernel/stop_machine.c:multi_cpu_stop
  - kernel/stop_machine.c:cpu_stop_init_done
```
```
In kernel/audit_watch.c (ffffffff812486f1)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_watch.c:audit_to_watch
```
```
In kernel/audit_tree.c (ffffffff81249be1)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - kernel/audit_tree.c:alloc_tree
```
```
In kernel/debug/debug_core.c (ffffffff812510d9)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff8125770f)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
```
```
In kernel/hung_task.c (ffffffff8125dc55)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - kernel/hung_task.c:reset_hung_task_detector
```
```
In kernel/seccomp.c (ffffffff81261cc7)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_attach_filter
```
```
In kernel/relay.c (ffffffff812647b8)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - kernel/relay.c:relay_open
  - kernel/relay.c:__relay_reset
```
```
In kernel/trace/trace.c (ffffffff8127cf74)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
```
```
In kernel/trace/tracing_map.c (ffffffff8129048e)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_create
  - kernel/trace/tracing_map.c:tracing_map_clear
```
```
In kernel/trace/blktrace.c (ffffffff8129f324)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:do_blk_trace_setup
```
```
In kernel/trace/fgraph.c (ffffffff812a23ba)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - kernel/trace/fgraph.c:start_graph_tracing
  - kernel/trace/fgraph.c:ftrace_graph_init_task
```
```
In kernel/trace/trace_events.c (ffffffff812a6c3a)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_module_notify
  - kernel/trace/trace_events.c:trace_add_event_call
  - kernel/trace/trace_events.c:trace_create_new_event
  - kernel/trace/trace_events.c:trace_create_new_event
```
```
In kernel/trace/trace_events_user.c (ffffffff812c67b4)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_events_user.c:user_event_parse
  - kernel/trace/trace_events_user.c:user_event_mm_alloc
  - kernel/trace/trace_events_user.c:user_event_mm_alloc
  - kernel/trace/trace_events_user.c:delayed_destroy_user_event
```
```
In kernel/trace/trace_dynevent.c (ffffffff812d6227)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_dynevent.c:trace_event_dyn_put_ref
```
```
In kernel/trace/rethook.c (ffffffff812df03c)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - kernel/trace/rethook.c:rethook_alloc
```
```
In kernel/irq_work.c (ffffffff812e5097)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_single
```
```
In kernel/bpf/syscall.c (ffffffff812f28ac)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_map_copy_value
```
```
In kernel/bpf/helpers.c (ffffffff81320ca6)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_obj_new_impl
```
```
In kernel/bpf/hashtab.c (ffffffff8132b523)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:bpf_percpu_hash_copy
  - kernel/bpf/hashtab.c:__bpf_hash_map_seq_show
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_elem
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_elem
```
```
In kernel/bpf/arraymap.c (ffffffff8132d176)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:__bpf_array_map_seq_show
  - kernel/bpf/arraymap.c:bpf_percpu_array_copy
```
```
In kernel/bpf/local_storage.c (ffffffff81332478)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc
  - kernel/bpf/local_storage.c:cgroup_storage_update_elem
```
```
In kernel/bpf/ringbuf.c (ffffffff813335ef)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - kernel/bpf/ringbuf.c:bpf_user_ringbuf_drain
  - kernel/bpf/ringbuf.c:bpf_ringbuf_alloc
```
```
In kernel/bpf/trampoline.c (ffffffff8133745c)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_lookup
```
```
In kernel/bpf/btf.c (ffffffff8133af9b)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_parse_module
  - kernel/bpf/btf.c:btf_parse_vmlinux
  - kernel/bpf/btf.c:btf_parse
```
```
In kernel/bpf/memalloc.c (ffffffff8134b5dd)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - kernel/bpf/memalloc.c:__free_rcu_tasks_trace
```
```
In kernel/bpf/dispatcher.c (ffffffff8134c8c1)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - kernel/bpf/dispatcher.c:bpf_dispatcher_change_prog
```
```
In kernel/bpf/bpf_struct_ops.c (ffffffff8135d1b4)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_sys_lookup_elem
```
```
In kernel/bpf/cpumask.c (ffffffff8135d57b)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - kernel/bpf/cpumask.c:bpf_cpumask_create
```
```
In kernel/events/core.c (ffffffff836deb3a)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:find_get_pmu_context
  - kernel/events/core.c:find_get_pmu_context
  - kernel/events/core.c:alloc_perf_context
```
```
In kernel/events/ring_buffer.c (ffffffff8137d11f)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc
  - kernel/events/ring_buffer.c:rb_alloc_aux
  - kernel/events/ring_buffer.c:perf_aux_output_skip
  - kernel/events/ring_buffer.c:perf_aux_output_end
  - kernel/events/ring_buffer.c:perf_aux_output_begin
  - kernel/events/ring_buffer.c:perf_output_put_handle
```
```
In kernel/events/uprobes.c (ffffffff81383278)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__create_xol_area
  - kernel/events/uprobes.c:alloc_uprobe
```
```
In kernel/padata.c (ffffffff81384fda)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - kernel/padata.c:padata_alloc_pd
```
```
In kernel/jump_label.c (ffffffff813865b9)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - kernel/jump_label.c:static_key_enable_cpuslocked
  - kernel/jump_label.c:static_key_slow_inc_cpuslocked
```
```
In kernel/watch_queue.c (ffffffff81389c4c)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - kernel/watch_queue.c:watch_queue_init
  - kernel/watch_queue.c:init_watch
```
```
In mm/filemap.c (ffffffff8138b39e)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - mm/filemap.c:filemap_unaccount_folio
```
```
In mm/vmscan.c (ffffffff813b9000)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd
```
```
In mm/shmem.c (0)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
```
```
In mm/backing-dev.c (ffffffff813cba66)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_init
  - mm/backing-dev.c:wb_init
```
```
In mm/mm_init.c (ffffffff8214bfbc)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - mm/mm_init.c:memmap_init_range
  - mm/mm_init.c:memmap_init_range
  - mm/mm_init.c:init_unavailable_range
  - mm/mm_init.c:init_unavailable_range
```
```
In mm/rmap.c (ffffffff8140f74b)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - mm/rmap.c:hugepage_add_new_anon_rmap
  - mm/rmap.c:folio_add_new_anon_rmap
  - mm/rmap.c:folio_add_new_anon_rmap
  - mm/rmap.c:folio_add_new_anon_rmap
  - mm/rmap.c:anon_vma_ctor
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:__anon_vma_prepare
```
```
In mm/page_alloc.c (ffffffff81422c19)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:make_alloc_exact
  - mm/page_alloc.c:page_frag_alloc_align
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:__rmqueue_pcplist
  - mm/page_alloc.c:split_page
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:prep_compound_page
  - mm/page_alloc.c:prep_compound_page
  - mm/page_alloc.c:prep_compound_page
  - mm/page_alloc.c:bad_page
```
```
In mm/madvise.c (ffffffff814285a0)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - mm/madvise.c:anon_vma_name_alloc
```
```
In mm/swap_state.c (ffffffff8142cf3b)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - mm/swap_state.c:init_swap_address_space
  - mm/swap_state.c:swap_cluster_readahead
```
```
In mm/frontswap.c (ffffffff81434bfe)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_invalidate_area
```
```
In mm/zswap.c (ffffffff81435401)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - mm/zswap.c:zswap_pool_create
```
```
In mm/hugetlb.c (ffffffff8143de82)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - mm/hugetlb.c:demote_free_hugetlb_folio
  - mm/hugetlb.c:demote_free_hugetlb_folio
  - mm/hugetlb.c:demote_free_hugetlb_folio
  - mm/hugetlb.c:__prep_compound_gigantic_folio
  - mm/hugetlb.c:__prep_compound_gigantic_folio
  - mm/hugetlb.c:__prep_compound_gigantic_folio
  - mm/hugetlb.c:__prep_compound_gigantic_folio
  - mm/hugetlb.c:__update_and_free_hugetlb_folio
  - mm/hugetlb.c:__update_and_free_hugetlb_folio
  - mm/hugetlb.c:__update_and_free_hugetlb_folio
  - mm/hugetlb.c:__update_and_free_hugetlb_folio
  - mm/hugetlb.c:resv_map_alloc
```
```
In mm/mempolicy.c (ffffffff8144943c)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - mm/mempolicy.c:shared_policy_replace
  - mm/mempolicy.c:shared_policy_replace
  - mm/mempolicy.c:__mpol_dup
  - mm/mempolicy.c:mpol_new
```
```
In mm/kfence/core.c (ffffffff8146431f)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
```
```
In mm/memory-tiers.c (ffffffff836eb96e)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - mm/memory-tiers.c:memory_tier_init
```
```
In mm/huge_memory.c (ffffffff81473bac)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - mm/huge_memory.c:mm_get_huge_zero_page
```
```
In mm/memcontrol.c (ffffffff81485ea6)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_online
```
```
In mm/zpool.c (ffffffff8149b399)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - mm/zpool.c:zpool_register_driver
```
```
In mm/zsmalloc.c (ffffffff8149c933)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_create_pool
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:__free_zspage
```
```
In mm/memremap.c (ffffffff814a402a)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - mm/memremap.c:zone_device_page_init
  - mm/memremap.c:free_zone_device_page
```
```
In mm/page_reporting.c (ffffffff814a7667)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - mm/page_reporting.c:page_reporting_register
  - mm/page_reporting.c:page_reporting_process
  - mm/page_reporting.c:page_reporting_cycle
```
```
In mm/bootmem_info.c (ffffffff814a787b)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - mm/bootmem_info.c:put_page_bootmem
```
```
In fs/super.c (ffffffff814b2906)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - fs/super.c:alloc_super
```
```
In fs/exec.c (ffffffff814b866e)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - fs/exec.c:unshare_sighand
```
```
In fs/dcache.c (ffffffff814d1e71)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - fs/dcache.c:__d_alloc
```
```
In fs/inode.c (ffffffff814d657e)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - fs/inode.c:inode_init_always
  - fs/inode.c:inode_init_always
  - fs/inode.c:inode_init_always
  - fs/inode.c:inode_init_always
```
```
In fs/file.c (ffffffff814dc9f8)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - fs/file.c:dup_fd
```
```
In fs/namespace.c (ffffffff814e0329)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In fs/fsopen.c (ffffffff81505e26)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - fs/fsopen.c:__ia32_sys_fspick
  - fs/fsopen.c:__x64_sys_fspick
  - fs/fsopen.c:__ia32_sys_fsopen
  - fs/fsopen.c:__x64_sys_fsopen
```
```
In fs/mnt_idmapping.c (ffffffff81506d63)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - fs/mnt_idmapping.c:alloc_mnt_idmap
```
```
In fs/notify/group.c (ffffffff81513b5e)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_alloc_group
  - fs/notify/group.c:fsnotify_alloc_group
```
```
In fs/notify/mark.c (ffffffff815142fb)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_init_mark
```
```
In fs/eventpoll.c (ffffffff8151e849)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_create
```
```
In fs/eventfd.c (ffffffff81523265)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - fs/eventfd.c:do_eventfd
```
```
In fs/userfaultfd.c (ffffffff81523ab5)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - fs/userfaultfd.c:new_userfaultfd
  - fs/userfaultfd.c:new_userfaultfd
  - fs/userfaultfd.c:dup_userfaultfd
  - fs/userfaultfd.c:dup_userfaultfd
```
```
In fs/aio.c (ffffffff8152c032)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:__ia32_sys_io_destroy
  - fs/aio.c:__x64_sys_io_destroy
  - fs/aio.c:exit_aio
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
```
```
In fs/crypto/keyring.c (ffffffff81535cf7)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
```
```
In fs/crypto/keysetup_v1.c (ffffffff815386ae)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_get_direct_key
```
```
In fs/mbcache.c (ffffffff8154c716)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/posix_acl.c (ffffffff8154db28)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - fs/posix_acl.c:posix_acl_from_mode
  - fs/posix_acl.c:posix_acl_clone
```
```
In fs/coredump.c (ffffffff8154f61a)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - fs/coredump.c:coredump_wait
```
```
In fs/iomap/direct-io.c (ffffffff8155881a)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:__iomap_dio_rw
```
```
In fs/quota/dquot.c (ffffffff8155c51a)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - fs/quota/dquot.c:dqget
```
```
In fs/proc/generic.c (ffffffff8157168d)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - fs/proc/generic.c:__proc_create
```
```
In fs/kernfs/inode.c (ffffffff815809e3)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
```
```
In fs/kernfs/dir.c (ffffffff81581b5e)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - fs/kernfs/dir.c:__kernfs_new_node
  - fs/kernfs/dir.c:__kernfs_new_node
```
```
In fs/kernfs/file.c (ffffffff815851b0)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_fop_open
```
```
In fs/configfs/dir.c (ffffffff8158c29d)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_register_group
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_new_dirent
```
```
In fs/configfs/item.c (ffffffff8158d63c)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - fs/configfs/item.c:config_group_init_type_name
  - fs/configfs/item.c:config_item_init_type_name
```
```
In fs/ext4/mballoc.c (ffffffff815cc77d)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_init
```
```
In fs/ext4/page-io.c (ffffffff815da3bb)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_init_io_end
```
```
In fs/ext4/super.c (ffffffff81603435)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:ext4_alloc_inode
  - fs/ext4/super.c:ext4_alloc_inode
```
```
In fs/ext4/fast_commit.c (ffffffff8160db45)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_init_inode
```
```
In fs/ext4/orphan.c (ffffffff81610fb1)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - fs/ext4/orphan.c:ext4_init_orphan_info
```
```
In fs/jbd2/transaction.c (ffffffff81613ef9)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
```
```
In fs/jbd2/journal.c (ffffffff816213dd)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_init_common
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/ecryptfs/main.c (ffffffff81643e98)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_get_lower_file
```
```
In fs/ecryptfs/super.c (ffffffff81644214)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - fs/ecryptfs/super.c:ecryptfs_alloc_inode
```
```
In fs/ecryptfs/miscdev.c (ffffffff836f3a75)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - fs/ecryptfs/miscdev.c:ecryptfs_init_ecryptfs_miscdev
```
```
In fs/fuse/dev.c (ffffffff816516b3)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_request_alloc
```
```
In fs/fuse/file.c (ffffffff8165f6f5)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_file_alloc
```
```
In fs/fuse/inode.c (ffffffff81664ba4)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_fill_super_common
  - fs/fuse/inode.c:fuse_conn_init
  - fs/fuse/inode.c:fuse_conn_init
  - fs/fuse/inode.c:fuse_conn_init
  - fs/fuse/inode.c:fuse_sync_fs_writes
```
```
In fs/fuse/dax.c (ffffffff81669bbc)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
```
```
In fs/debugfs/file.c (ffffffff8166ce85)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_atomic_t_set
  - fs/debugfs/file.c:debugfs_file_get
```
```
In ipc/util.c (ffffffff81674fd5)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In ipc/sem.c (ffffffff8167d600)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - ipc/sem.c:copy_semundo
  - ipc/sem.c:find_alloc_undo
```
```
In ipc/namespace.c (ffffffff8168551b)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
```
```
In security/keys/key.c (ffffffff8168782c)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_user_lookup
  - security/keys/key.c:key_user_lookup
  - security/keys/key.c:key_user_lookup
```
```
In security/selinux/avc.c (ffffffff816a556d)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - security/selinux/avc.c:selinux_avc_init
  - security/selinux/avc.c:selinux_avc_init
```
```
In security/selinux/ss/services.c (ffffffff816ccc31)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
```
```
In security/smack/smack_access.c (ffffffff816d974a)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - security/smack/smack_access.c:smack_populate_secattr
```
```
In security/tomoyo/condition.c (ffffffff816e708c)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_commit_condition
```
```
In security/tomoyo/gc.c (ffffffff816ed753)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - security/tomoyo/gc.c:tomoyo_collect_entry
  - security/tomoyo/gc.c:tomoyo_collect_entry
  - security/tomoyo/gc.c:tomoyo_collect_entry
```
```
In security/tomoyo/memory.c (ffffffff816ee603)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_name
  - security/tomoyo/memory.c:tomoyo_get_group
```
```
In security/apparmor/apparmorfs.c (ffffffff816f7d2d)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_write_access
```
```
In security/apparmor/audit.c (ffffffff816fa678)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - security/apparmor/audit.c:aa_dup_audit_data
```
```
In security/apparmor/lib.c (ffffffff816fce69)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - security/apparmor/lib.c:aa_str_alloc
```
```
In security/apparmor/match.c (ffffffff816fdae7)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
```
```
In security/apparmor/policy.c (ffffffff8170614e)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_alloc_pdb
```
```
In security/apparmor/policy_unpack.c (ffffffff8170bcdb)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:aa_loaddata_alloc
```
```
In security/apparmor/policy_ns.c (ffffffff81717269)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:alloc_ns
```
```
In security/apparmor/label.c (ffffffff8171998c)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_alloc
  - security/apparmor/label.c:aa_alloc_proxy
```
```
In security/apparmor/notify.c (ffffffff817245a2)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - security/apparmor/notify.c:aa_new_listener
  - security/apparmor/notify.c:aa_new_listener
```
```
In security/landlock/object.c (ffffffff81729dd7)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - security/landlock/object.c:landlock_create_object
```
```
In security/landlock/ruleset.c (ffffffff8172a737)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - security/landlock/ruleset.c:landlock_merge_ruleset
  - security/landlock/ruleset.c:landlock_merge_ruleset
  - security/landlock/ruleset.c:landlock_create_ruleset
```
```
In security/integrity/ima/ima_policy.c (ffffffff836fbb5a)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_init_policy
```
```
In crypto/api.c (ffffffff8173e968)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - crypto/api.c:__crypto_alloc_tfmgfp
  - crypto/api.c:crypto_alg_mod_lookup
```
```
In crypto/algapi.c (ffffffff8173f423)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_check_alg
```
```
In crypto/jitterentropy-testing.c (ffffffff8175e5c2)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
```
```
In block/fops.c (ffffffff817681b6)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
```
```
In block/bio.c (ffffffff81769f35)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - block/bio.c:bio_init_clone
  - block/bio.c:bio_init_clone
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_reset
```
```
In block/blk-core.c (ffffffff817719d4)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - block/blk-core.c:blk_alloc_queue
  - block/blk-core.c:blk_alloc_queue
```
```
In block/blk-flush.c (ffffffff81774cfb)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - block/blk-flush.c:blk_flush_complete_seq
```
```
In block/blk-ioc.c (ffffffff817769cf)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - block/blk-ioc.c:alloc_io_context
```
```
In block/blk-mq.c (ffffffff81780f97)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_hctx
```
```
In block/bsg-lib.c (ffffffff8179e78d)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_queue_rq
```
```
In block/blk-cgroup.c (ffffffff817a09d9)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_css_alloc
```
```
In block/blk-iocost.c (ffffffff817acdb6)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - block/blk-iocost.c:blk_iocost_init
```
```
In block/blk-wbt.c (ffffffff817bafd1)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_init
```
```
In block/blk-crypto-profile.c (ffffffff817c3e4a)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - block/blk-crypto-profile.c:blk_crypto_get_keyslot
```
```
In io_uring/io_uring.c (ffffffff817d05a7)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_uring_try_cancel_requests
  - io_uring/io_uring.c:io_eventfd_register
  - io_uring/io_uring.c:io_eventfd_register
  - io_uring/io_uring.c:io_cqring_wait
  - io_uring/io_uring.c:io_cqring_wait
  - io_uring/io_uring.c:io_wq_submit_work
  - io_uring/io_uring.c:__io_arm_ltimeout
  - io_uring/io_uring.c:__io_arm_ltimeout
```
```
In io_uring/timeout.c (ffffffff817d9cf6)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - io_uring/timeout.c:io_timeout_fn
  - io_uring/timeout.c:io_flush_timeouts
```
```
In io_uring/sqpoll.c (ffffffff817db133)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - io_uring/sqpoll.c:io_get_sq_data
  - io_uring/sqpoll.c:io_get_sq_data
```
```
In io_uring/tctx.c (ffffffff817dcd26)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - io_uring/tctx.c:io_uring_alloc_task_context
  - io_uring/tctx.c:io_uring_alloc_task_context
  - io_uring/tctx.c:io_uring_alloc_task_context
```
```
In io_uring/poll.c (ffffffff817de61b)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - io_uring/poll.c:__io_arm_poll_handler
```
```
In io_uring/rsrc.c (ffffffff817e229c)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - io_uring/rsrc.c:io_rsrc_ref_quiesce
  - io_uring/rsrc.c:io_rsrc_ref_quiesce
```
```
In io_uring/notif.c (ffffffff817e62e2)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - io_uring/notif.c:io_alloc_notif
```
```
In io_uring/io-wq.c (ffffffff817e890a)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_wq_create
  - io_uring/io-wq.c:io_wq_create
  - io_uring/io-wq.c:create_io_worker
```
```
In lib/rhashtable.c (ffffffff81818ee0)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_init
```
```
In lib/refcount.c (ffffffff8181ac8b)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - lib/refcount.c:refcount_dec_and_lock_irqsave
  - lib/refcount.c:refcount_dec_and_lock
  - lib/refcount.c:refcount_dec_and_mutex_lock
```
```
In lib/rcuref.c (ffffffff8181ada2)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - lib/rcuref.c:rcuref_put_slowpath
  - lib/rcuref.c:rcuref_put_slowpath
  - lib/rcuref.c:rcuref_get_slowpath
  - lib/rcuref.c:rcuref_get_slowpath
```
```
In lib/cpu_rmap.c (ffffffff818d3443)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - lib/cpu_rmap.c:alloc_cpu_rmap
```
```
In lib/sbitmap.c (ffffffff818e5276)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_queue_wake_up
  - lib/sbitmap.c:sbitmap_queue_init_node
  - lib/sbitmap.c:sbitmap_queue_init_node
  - lib/sbitmap.c:sbitmap_queue_init_node
  - lib/sbitmap.c:sbitmap_queue_init_node
```
```
In drivers/pinctrl/core.c (ffffffff818ee8fe)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:create_pinctrl
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff81909000)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:linereq_create
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff8195b666)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
```
```
In drivers/rapidio/rio.c (ffffffff8196f19d)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_register_mport
  - drivers/rapidio/rio.c:rio_mport_initialize
  - drivers/rapidio/rio.c:rio_del_device
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff8197a93a)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:do_register_framebuffer
```
```
In drivers/acpi/ec.c (ffffffff819ad251)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_add_query_handler
```
```
In drivers/acpi/thermal.c (ffffffff81a2280a)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - drivers/acpi/thermal.c:acpi_thermal_add
```
```
In drivers/acpi/apei/ghes.c (ffffffff81a303b4)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_alloc
```
```
In drivers/clk/clk.c (ffffffff81a44c64)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_core_init
```
```
In drivers/dma/dmaengine.c (ffffffff81a4d358)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaengine_get_unmap_data
  - drivers/dma/dmaengine.c:dma_async_device_register
```
```
In drivers/xen/balloon.c (ffffffff81a64587)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_thread
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff81a74e14)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_open
```
```
In drivers/reset/core.c (ffffffff81a908b7)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - drivers/reset/core.c:__reset_control_get_internal
```
```
In drivers/tty/tty_io.c (ffffffff81a96e44)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:alloc_tty_struct
```
```
In drivers/tty/tty_buffer.c (ffffffff81a9f741)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_init
  - drivers/tty/tty_buffer.c:tty_buffer_init
```
```
In drivers/tty/tty_port.c (ffffffff81a9fb72)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_init
```
```
In drivers/tty/serial/serial_core.c (ffffffff81ac3049)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:serial_core_add_one_port
```
```
In drivers/char/random.c (ffffffff81ae05b1)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - drivers/char/random.c:try_to_generate_entropy
```
```
In drivers/char/virtio_console.c (ffffffff81ae33f9)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
```
```
In drivers/char/hw_random/core.c (ffffffff81ae7254)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
```
```
In drivers/char/agp/backend.c (ffffffff81ae88e4)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - drivers/char/agp/backend.c:agp_alloc_bridge
  - drivers/char/agp/backend.c:agp_alloc_bridge
```
```
In drivers/iommu/dma-iommu.c (ffffffff81b25498)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_init_fq
  - drivers/iommu/dma-iommu.c:fq_flush_timeout
```
```
In drivers/connector/cn_queue.c (ffffffff81b2ae4a)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - drivers/connector/cn_queue.c:cn_queue_alloc_dev
  - drivers/connector/cn_queue.c:cn_queue_alloc_callback_entry
```
```
In drivers/base/core.c (ffffffff81b331fe)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/power/runtime.c (ffffffff81b507c6)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_init
  - drivers/base/power/runtime.c:pm_runtime_init
```
```
In drivers/base/power/wakeup.c (ffffffff81b57370)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:pm_wakeup_clear
```
```
In drivers/base/power/domain.c (ffffffff81b59fc8)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - drivers/base/power/domain.c:pm_genpd_init
```
```
In drivers/base/firmware_loader/main.c (ffffffff81b5f576)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:alloc_lookup_fw_priv
```
```
In drivers/block/loop.c (ffffffff81b7c60e)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
```
```
In drivers/nvdimm/core.c (ffffffff81ba220d)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:alloc_nvdimm_map
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff81ba63aa)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:__nvdimm_create
```
```
In drivers/nvdimm/dimm.c (ffffffff81ba7ba4)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
```
```
In drivers/dax/bus.c (ffffffff81bbad4a)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - drivers/dax/bus.c:alloc_dax_region
```
```
In drivers/dma-buf/dma-fence.c (ffffffff81bbf30f)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_allocate_private_stub
  - drivers/dma-buf/dma-fence.c:dma_fence_get_stub
```
```
In drivers/dma-buf/dma-fence-array.c (ffffffff81bc0260)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_create
```
```
In drivers/dma-buf/sw_sync.c (ffffffff81bc559f)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_timeline_create
```
```
In drivers/scsi/scsi.c (ffffffff81bc9518)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_finish_command
  - drivers/scsi/scsi.c:scsi_finish_command
  - drivers/scsi/scsi.c:scsi_finish_command
```
```
In drivers/scsi/hosts.c (ffffffff81bcaaf6)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/scsi/scsi_lib.c (ffffffff81bd56d3)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:__scsi_queue_insert
  - drivers/scsi/scsi_lib.c:__scsi_queue_insert
  - drivers/scsi/scsi_lib.c:__scsi_queue_insert
```
```
In drivers/scsi/scsi_scan.c (ffffffff81bd786e)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
```
```
In drivers/scsi/sd.c (ffffffff81bea676)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
```
```
In drivers/scsi/sg.c (ffffffff81bf5a2e)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_add_sfp
  - drivers/scsi/sg.c:sg_alloc
  - drivers/scsi/sg.c:sg_alloc
```
```
In drivers/ata/libata-core.c (ffffffff81bfa454)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_init
  - drivers/ata/libata-core.c:ata_host_alloc
```
```
In drivers/net/phy/phy_device.c (ffffffff81c3a741)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_package_join
```
```
In drivers/net/phy/sfp-bus.c (ffffffff81c405b2)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_bus_get
```
```
In drivers/net/pse-pd/pse_core.c (0)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81c6223d)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
```
```
In drivers/usb/core/usb.c (ffffffff81c78ea0)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - drivers/usb/core/usb.c:usb_alloc_dev
```
```
In drivers/usb/core/hub.c (ffffffff81c83a3a)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_probe
```
```
In drivers/usb/core/hcd.c (ffffffff81c85670)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:__usb_create_hcd
```
```
In drivers/usb/core/urb.c (ffffffff81c8854f)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_init_urb
```
```
In drivers/usb/core/config.c (ffffffff81c9166e)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_configuration
```
```
In drivers/usb/core/file.c (ffffffff81c929e3)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - drivers/usb/core/file.c:usb_register_dev
```
```
In drivers/thermal/thermal_core.c (ffffffff81d48d2c)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register_with_trips
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
```
```
In drivers/thermal/intel/therm_throt.c (ffffffff81d531dc)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - drivers/thermal/intel/therm_throt.c:intel_init_thermal
```
```
In drivers/md/md.c (ffffffff81d694d8)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_run
  - drivers/md/md.c:max_corrected_read_errors_store
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:errors_store
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:mddev_init
  - drivers/md/md.c:mddev_init
  - drivers/md/md.c:mddev_init
  - drivers/md/md.c:submit_flushes
```
```
In drivers/md/md-bitmap.c (ffffffff81d71722)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
```
```
In drivers/md/dm.c (ffffffff81d77708)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:dm_split_and_process_bio
  - drivers/md/dm.c:dm_get_table_device
```
```
In drivers/md/dm-table.c (ffffffff82148904)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_get_device
```
```
In drivers/md/dm-stripe.c (ffffffff81d7f0db)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:stripe_ctr
```
```
In drivers/md/dm-io.c (ffffffff81d83b53)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - drivers/md/dm-io.c:dm_io
  - drivers/md/dm-io.c:sync_io
```
```
In drivers/md/dm-kcopyd.c (ffffffff81d84400)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
  - drivers/md/dm-kcopyd.c:dm_kcopyd_copy
```
```
In drivers/md/dm-stats.c (ffffffff81d86660)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
```
```
In drivers/edac/ghes_edac.c (ffffffff81d8eedc)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
```
```
In drivers/opp/core.c (ffffffff81d94276)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - drivers/opp/core.c:_opp_add
  - drivers/opp/core.c:_add_opp_table_indexed
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff81d9e1e8)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_stop
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
  - drivers/cpufreq/cpufreq_governor.c:dbs_update_util_handler
  - drivers/cpufreq/cpufreq_governor.c:dbs_work_handler
```
```
In drivers/mmc/core/sdio_irq.c (ffffffff81dc6dc1)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_irq.c:sdio_release_irq
  - drivers/mmc/core/sdio_irq.c:sdio_claim_irq
```
```
In drivers/firmware/efi/efi.c (ffffffff82148a74)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81de4dda)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc
```
```
In drivers/devfreq/devfreq.c (ffffffff81deede1)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
```
In drivers/nvmem/core.c (ffffffff81dfab70)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - drivers/nvmem/core.c:nvmem_register
```
```
In drivers/hte/hte.c (ffffffff81dfee9a)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - drivers/hte/hte.c:hte_ts_put
```
```
In net/core/sock.c (ffffffff81e08dfb)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - net/core/sock.c:sock_init_data_uid
  - net/core/sock.c:sock_init_data_uid
  - net/core/sock.c:sock_init_data_uid
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_alloc
  - net/core/sock.c:sock_set_timestamping
  - net/core/sock.c:sock_set_timestamping
  - net/core/sock.c:sock_set_timestamping
```
```
In net/core/skbuff.c (ffffffff81e13aaf)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_ext_maybe_cow
  - net/core/skbuff.c:__skb_ext_alloc
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:pskb_carve_inside_header
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:msg_zerocopy_realloc
  - net/core/skbuff.c:msg_zerocopy_realloc
  - net/core/skbuff.c:__skb_clone
  - net/core/skbuff.c:__alloc_skb
  - net/core/skbuff.c:__build_skb_around
  - net/core/skbuff.c:__build_skb_around
  - net/core/skbuff.c:slab_build_skb
  - net/core/skbuff.c:slab_build_skb
```
```
In net/core/net_namespace.c (ffffffff81e25d55)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - net/core/net_namespace.c:copy_net_ns
  - net/core/net_namespace.c:copy_net_ns
  - net/core/net_namespace.c:setup_net
  - net/core/net_namespace.c:setup_net
```
```
In net/core/dev.c (ffffffff81e2eddd)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - net/core/dev.c:dev_kfree_skb_irq_reason
```
```
In net/core/dst.c (ffffffff81e44ee7)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - net/core/dst.c:__metadata_dst_init
  - net/core/dst.c:dst_cow_metrics_generic
  - net/core/dst.c:dst_alloc
```
```
In net/core/neighbour.c (ffffffff81e49667)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:neigh_alloc
```
```
In net/core/filter.c (ffffffff81e72ba9)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - net/core/filter.c:__sk_attach_prog
```
```
In net/core/flow_offload.c (ffffffff81e7aa37)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - net/core/flow_offload.c:flow_indr_dev_register
```
```
In net/core/gro.c (ffffffff81e7c9ae)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - net/core/gro.c:skb_gro_receive
```
```
In net/core/page_pool.c (ffffffff81e822c9)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_init
  - net/core/page_pool.c:page_pool_init
```
```
In net/core/netpoll.c (ffffffff81e85df2)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - net/core/netpoll.c:__netpoll_setup
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:zap_completion_queue
```
```
In net/core/fib_rules.c (ffffffff81e87ece)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_default_rule_add
```
```
In net/core/skmsg.c (ffffffff81ea1cb3)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_init
```
```
In net/sched/sch_generic.c (ffffffff81eadc90)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_alloc
```
```
In net/sched/cls_api.c (ffffffff81ebb60b)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tcf_block_get_ext
```
```
In net/sched/act_api.c (ffffffff81ebde1f)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_idr_create
  - net/sched/act_api.c:tcf_idr_create
```
```
In net/ipv4/route.c (ffffffff81eeb095)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_genid_init
  - net/ipv4/route.c:rt_genid_init
  - net/ipv4/route.c:rt_genid_init
```
```
In net/ipv4/inetpeer.c (ffffffff81ef3463)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/ip_output.c (ffffffff81efc1f0)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_queue_xmit
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81f04176)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81f06ec8)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_complete_hashdance
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_hash_add
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
```
```
In net/ipv4/tcp.c (ffffffff81f0bc12)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_skb_entail
```
```
In net/ipv4/tcp_input.c (ffffffff81f14a82)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/tcp_output.c (ffffffff81f2096d)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_queue_skb
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_clone_payload
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81f2c4ae)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_sk_init
  - net/ipv4/tcp_ipv4.c:tcp_sk_init
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81f389ab)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_create_child
```
```
In net/ipv4/datagram.c (ffffffff81f3aa2f)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (0)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff81f51850)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_init
```
```
In net/ipv4/af_inet.c (ffffffff81f53788)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
```
```
In net/ipv4/igmp.c (ffffffff81f59947)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - net/ipv4/igmp.c:____ip_mc_inc_group
```
```
In net/ipv4/fib_frontend.c (ffffffff81f5c3c2)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
```
```
In net/ipv4/fib_semantics.c (ffffffff81f628d1)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_rebalance
```
```
In net/ipv4/inet_fragment.c (ffffffff81f6ac3e)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_find
  - net/ipv4/inet_fragment.c:inet_frags_init
```
```
In net/ipv4/metrics.c (ffffffff81f70733)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
```
```
In net/ipv4/nexthop.c (ffffffff81f774f5)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:nh_hthr_group_rebalance
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81f778cf)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:proc_tfo_blackhole_detect_timeout
```
```
In net/ipv4/ipmr.c (ffffffff81f8109f)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv4/syncookies.c (ffffffff81f844e2)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:tcp_get_cookie_sock
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81f8952a)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f8d771)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
```
```
In net/xfrm/xfrm_state.c (ffffffff81f97f4f)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
```
```
In net/xfrm/xfrm_output.c (0)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
```
```
In net/unix/af_unix.c (ffffffff81faba21)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_autobind
  - net/unix/af_unix.c:unix_create_addr
```
```
In net/ipv6/af_inet6.c (ffffffff81fb2434)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_net_init
```
```
In net/ipv6/anycast.c (ffffffff81fb3879)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
```
```
In net/ipv6/addrconf.c (ffffffff81fc1737)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_dev
```
```
In net/ipv6/route.c (ffffffff81fcd011)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ip6_dst_gc
  - net/ipv6/route.c:ip6_dst_gc
```
```
In net/ipv6/ip6_fib.c (ffffffff81fdd9bf)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_info_alloc
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81fe09a6)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt
```
```
In net/ipv6/mcast.c (ffffffff81ff61c5)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
```
```
In net/ipv6/exthdrs.c (ffffffff82002475)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_dup_options
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff82005357)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:fl_create
```
```
In net/ipv6/ip6mr.c (ffffffff8200f981)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/ipv6/calipso.c (ffffffff8201828d)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_doi_add
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff82020466)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_build_state
```
```
In net/packet/af_packet.c (ffffffff8202a097)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - net/packet/af_packet.c:fanout_add
  - net/packet/af_packet.c:fanout_add
  - net/packet/af_packet.c:fanout_add
```
```
In net/devlink/leftover.c (ffffffff8203e942)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - net/devlink/leftover.c:devlink_nl_cmd_rate_new_doit
```
```
In net/devlink/core.c (ffffffff820420ed)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - net/devlink/core.c:devlink_alloc_ns
```
```
In net/xdp/xdp_umem.c (ffffffff8206c4af)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_reg
```
```
In net/xdp/xsk_buff_pool.c (ffffffff8206dd37)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_dma_map
  - net/xdp/xsk_buff_pool.c:xp_create_and_assign_umem
```
```
In net/mctp/device.c (ffffffff8208e3a8)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - net/mctp/device.c:mctp_add_dev
```
```
In net/mctp/route.c (ffffffff8208f8c1)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - net/mctp/route.c:mctp_route_add
  - net/mctp/route.c:mctp_key_alloc
```
```
In lib/klist.c (ffffffff820a1a47)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - lib/klist.c:klist_add_before
  - lib/klist.c:klist_add_behind
  - lib/klist.c:klist_add_tail
  - lib/klist.c:klist_add_head
```
```
In lib/kobject.c (ffffffff820a311e)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - lib/kobject.c:kset_register
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
In arch/x86/kernel/ioport.c (ffffffff81058fac)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
  - arch/x86/kernel/ioport.c:ksys_ioperm
```
```
In arch/x86/kernel/tboot.c (ffffffff838cd78f)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81080ff5)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:fake_panic_set
  - arch/x86/kernel/cpu/mce/core.c:fake_panic_set
  - arch/x86/kernel/cpu/mce/core.c:fake_panic_set
  - arch/x86/kernel/cpu/mce/core.c:fake_panic_set
  - arch/x86/kernel/cpu/mce/core.c:mce_end
  - arch/x86/kernel/cpu/mce/core.c:mce_end
  - arch/x86/kernel/cpu/mce/core.c:mce_end
  - arch/x86/kernel/cpu/mce/core.c:mce_start
  - arch/x86/kernel/cpu/mce/core.c:mce_start
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81085907)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:threshold_create_bank
```
```
In arch/x86/kernel/cpu/sgx/driver.c (ffffffff81098fec)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/driver.c:sgx_open
```
```
In arch/x86/kernel/reboot.c (ffffffff810a2847)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:nmi_shootdown_cpus
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff810a6cad)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_target
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
```
```
In arch/x86/kernel/kgdb.c (ffffffff810bd5cd)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - arch/x86/kernel/kgdb.c:kgdb_arch_handle_exception
  - arch/x86/kernel/kgdb.c:kgdb_arch_handle_exception
```
```
In arch/x86/mm/init_64.c (ffffffff8222befa)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pagetable
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff838f977a)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_common
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_dump_state
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus
```
```
In kernel/fork.c (ffffffff810f98bb)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - kernel/fork.c:copy_signal
  - kernel/fork.c:copy_signal
  - kernel/fork.c:copy_sighand
  - kernel/fork.c:mm_init
  - kernel/fork.c:mm_init
  - kernel/fork.c:mm_init
  - kernel/fork.c:dup_task_struct
  - kernel/fork.c:dup_task_struct
  - kernel/fork.c:dup_task_struct
```
```
In kernel/cpu.c (ffffffff838fac2a)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - kernel/cpu.c:boot_cpu_hotplug_init
```
```
In kernel/softirq.c (ffffffff811080e5)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - kernel/softirq.c:tasklet_init
  - kernel/softirq.c:tasklet_setup
```
```
In kernel/user.c (ffffffff81112db1)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - kernel/user.c:alloc_uid
```
```
In kernel/workqueue.c (ffffffff8112fb08)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:flush_workqueue_prep_pwqs
```
```
In kernel/pid.c (ffffffff81130df2)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - kernel/pid.c:alloc_pid
```
```
In kernel/nsproxy.c (ffffffff8113bda1)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - kernel/nsproxy.c:create_new_namespaces
```
```
In kernel/ucount.c (ffffffff81142860)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - kernel/ucount.c:alloc_ucounts
```
```
In kernel/groups.c (ffffffff81143ae3)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - kernel/groups.c:__do_sys_setgroups
```
```
In kernel/sched/core.c (ffffffff838fdf96)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:affine_move_task
```
```
In kernel/sched/fair.c (ffffffff81161d46)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_group
```
```
In kernel/sched/build_utility.c (ffffffff8119021d)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sched_autogroup_create_attach
  - kernel/sched/build_utility.c:autogroup_init
  - kernel/sched/build_utility.c:membarrier_exec_mmap
  - kernel/sched/build_utility.c:psi_trigger_destroy
  - kernel/sched/build_utility.c:psi_trigger_create
  - kernel/sched/build_utility.c:psi_group_change
  - kernel/sched/build_utility.c:poll_timer_fn
  - kernel/sched/build_utility.c:psi_rtpoll_work
  - kernel/sched/build_utility.c:psi_rtpoll_work
  - kernel/sched/build_utility.c:group_init
  - kernel/sched/build_utility.c:sched_core_share_pid
  - kernel/sched/build_utility.c:sd_init
  - kernel/sched/build_utility.c:init_defrootdomain
  - kernel/sched/build_utility.c:cpupri_init
```
```
In kernel/locking/mutex.c (ffffffff8119bc24)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - kernel/locking/mutex.c:__mutex_init
```
```
In kernel/locking/rwsem.c (ffffffff8119c5bc)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:__init_rwsem
```
```
In kernel/locking/percpu-rwsem.c (ffffffff8119cf9c)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:__percpu_init_rwsem
```
```
In kernel/power/swap.c (ffffffff811a8f83)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:save_image
```
```
In kernel/printk/nbcon.c (ffffffff811b3c65)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - kernel/printk/nbcon.c:nbcon_free
  - kernel/printk/nbcon.c:nbcon_init
```
```
In kernel/irq/manage.c (ffffffff811b820d)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_notifier
```
```
In kernel/rcu/update.c (ffffffff811cd1a1)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_barrier_tasks_generic
```
```
In kernel/rcu/srcutree.c (ffffffff811d0d8e)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
```
```
In kernel/rcu/tree.c (ffffffff811d46fe)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - kernel/rcu/tree.c:kfree_rcu_shrink_count
  - kernel/rcu/tree.c:fill_page_cache_func
  - kernel/rcu/tree.c:fill_page_cache_func
  - kernel/rcu/tree.c:kfree_rcu_monitor
  - kernel/rcu/tree.c:kfree_rcu_monitor
  - kernel/rcu/tree.c:kfree_rcu_monitor
```
```
In kernel/module/main.c (ffffffff811f53f9)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - kernel/module/main.c:load_module
```
```
In kernel/time/namespace.c (ffffffff8121de79)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - kernel/time/namespace.c:copy_time_ns
```
```
In kernel/futex/core.c (ffffffff83905a39)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - kernel/futex/core.c:futex_init
```
```
In kernel/futex/pi.c (ffffffff81221902)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - kernel/futex/pi.c:refill_pi_state_cache
```
```
In kernel/kexec_core.c (ffffffff8122b814)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - kernel/kexec_core.c:__crash_shrink_memory
  - kernel/kexec_core.c:crash_kexec
```
```
In kernel/cgroup/cgroup.c (ffffffff81233095)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:init_cgroup_root
  - kernel/cgroup/cgroup.c:find_css_set
```
```
In kernel/cgroup/namespace.c (ffffffff8123f91c)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
```
```
In kernel/utsname.c (ffffffff8124f8a5)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - kernel/utsname.c:clone_uts_ns
```
```
In kernel/user_namespace.c (ffffffff81251805)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In kernel/pid_namespace.c (ffffffff8125274d)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - kernel/pid_namespace.c:create_pid_namespace
```
```
In kernel/stop_machine.c (ffffffff81254271)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:stop_core_cpuslocked
  - kernel/stop_machine.c:stop_machine_cpuslocked
  - kernel/stop_machine.c:stop_two_cpus
  - kernel/stop_machine.c:multi_cpu_stop
  - kernel/stop_machine.c:cpu_stop_init_done
```
```
In kernel/audit_watch.c (ffffffff8126239e)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_init_watch
```
```
In kernel/audit_tree.c (ffffffff81263af1)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - kernel/audit_tree.c:alloc_tree
```
```
In kernel/debug/debug_core.c (ffffffff8126af29)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff812715cf)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
```
```
In kernel/hung_task.c (ffffffff81277b95)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - kernel/hung_task.c:reset_hung_task_detector
```
```
In kernel/seccomp.c (ffffffff8127bef6)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_attach_filter
```
```
In kernel/relay.c (ffffffff8127e5db)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - kernel/relay.c:relay_open
  - kernel/relay.c:__relay_reset
```
```
In kernel/trace/trace.c (ffffffff81297eb0)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
```
```
In kernel/trace/tracing_map.c (ffffffff812aba7d)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_create
  - kernel/trace/tracing_map.c:tracing_map_clear
```
```
In kernel/trace/blktrace.c (ffffffff812baa33)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:do_blk_trace_setup
```
```
In kernel/trace/fgraph.c (ffffffff812bdb80)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - kernel/trace/fgraph.c:start_graph_tracing
  - kernel/trace/fgraph.c:ftrace_graph_init_task
```
```
In kernel/trace/trace_events.c (ffffffff812c363a)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_module_notify
  - kernel/trace/trace_events.c:trace_add_event_call
  - kernel/trace/trace_events.c:trace_create_new_event
  - kernel/trace/trace_events.c:trace_create_new_event
```
```
In kernel/trace/trace_events_user.c (ffffffff812e326a)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_events_user.c:user_event_parse
  - kernel/trace/trace_events_user.c:user_event_parse
  - kernel/trace/trace_events_user.c:user_event_mm_alloc
  - kernel/trace/trace_events_user.c:user_event_mm_alloc
  - kernel/trace/trace_events_user.c:delayed_destroy_user_event
```
```
In kernel/trace/trace_dynevent.c (ffffffff812f3d37)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_dynevent.c:trace_event_dyn_put_ref
```
```
In kernel/irq_work.c (ffffffff81303147)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_single
```
```
In kernel/bpf/syscall.c (ffffffff8131174f)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_map_copy_value
```
```
In kernel/bpf/helpers.c (ffffffff813431ac)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_obj_new_impl
```
```
In kernel/bpf/hashtab.c (ffffffff8134f9d9)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:bpf_percpu_hash_copy
  - kernel/bpf/hashtab.c:__bpf_hash_map_seq_show
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_elem
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_elem
```
```
In kernel/bpf/arraymap.c (ffffffff813514dc)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:__bpf_array_map_seq_show
  - kernel/bpf/arraymap.c:bpf_percpu_array_copy
```
```
In kernel/bpf/local_storage.c (ffffffff81356a2e)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc
  - kernel/bpf/local_storage.c:cgroup_storage_update_elem
```
```
In kernel/bpf/ringbuf.c (ffffffff81357f2a)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - kernel/bpf/ringbuf.c:bpf_ringbuf_alloc
```
```
In kernel/bpf/trampoline.c (ffffffff8135d33a)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_lookup
```
```
In kernel/bpf/btf.c (ffffffff81361129)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_parse_module
  - kernel/bpf/btf.c:btf_parse_vmlinux
  - kernel/bpf/btf.c:btf_parse
```
```
In kernel/bpf/memalloc.c (ffffffff81372c68)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - kernel/bpf/memalloc.c:bpf_mem_refill
  - kernel/bpf/memalloc.c:__free_by_rcu
  - kernel/bpf/memalloc.c:__free_rcu_tasks_trace
```
```
In kernel/bpf/dispatcher.c (ffffffff81373dda)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - kernel/bpf/dispatcher.c:bpf_dispatcher_change_prog
```
```
In kernel/bpf/bpf_struct_ops.c (ffffffff813858c4)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_sys_lookup_elem
```
```
In kernel/bpf/cpumask.c (ffffffff813862db)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - kernel/bpf/cpumask.c:bpf_cpumask_create
```
```
In kernel/events/core.c (ffffffff8391117a)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:find_get_pmu_context
  - kernel/events/core.c:find_get_pmu_context
  - kernel/events/core.c:alloc_perf_context
```
```
In kernel/events/ring_buffer.c (ffffffff813a637f)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc
  - kernel/events/ring_buffer.c:rb_alloc_aux
  - kernel/events/ring_buffer.c:perf_aux_output_skip
  - kernel/events/ring_buffer.c:perf_aux_output_end
  - kernel/events/ring_buffer.c:perf_aux_output_begin
  - kernel/events/ring_buffer.c:perf_output_put_handle
```
```
In kernel/events/uprobes.c (ffffffff813ac6a6)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__create_xol_area
  - kernel/events/uprobes.c:alloc_uprobe
```
```
In kernel/padata.c (ffffffff813ae349)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - kernel/padata.c:padata_alloc_pd
```
```
In kernel/jump_label.c (ffffffff813afa79)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - kernel/jump_label.c:static_key_enable_cpuslocked
  - kernel/jump_label.c:static_key_slow_inc_cpuslocked
```
```
In kernel/watch_queue.c (ffffffff813b36cb)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - kernel/watch_queue.c:watch_queue_init
  - kernel/watch_queue.c:init_watch
```
```
In mm/filemap.c (ffffffff813b4ec5)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - mm/filemap.c:filemap_unaccount_folio
```
```
In mm/vmscan.c (ffffffff813e2000)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd
```
```
In mm/shrinker.c (ffffffff813e3abe)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - mm/shrinker.c:shrinker_register
```
```
In mm/shmem.c (0)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
```
```
In mm/backing-dev.c (ffffffff813f63a6)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_init
  - mm/backing-dev.c:wb_init
```
```
In mm/mm_init.c (ffffffff8222eb52)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - mm/mm_init.c:memmap_init_range
  - mm/mm_init.c:memmap_init_range
  - mm/mm_init.c:init_unavailable_range
  - mm/mm_init.c:init_unavailable_range
```
```
In mm/rmap.c (ffffffff8143c0c4)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - mm/rmap.c:hugetlb_add_new_anon_rmap
  - mm/rmap.c:folio_add_new_anon_rmap
  - mm/rmap.c:folio_add_new_anon_rmap
  - mm/rmap.c:folio_add_new_anon_rmap
  - mm/rmap.c:folio_add_new_anon_rmap
  - mm/rmap.c:folio_add_new_anon_rmap
  - mm/rmap.c:anon_vma_ctor
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:__anon_vma_prepare
```
```
In mm/page_alloc.c (ffffffff8144faf9)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:make_alloc_exact
  - mm/page_alloc.c:page_frag_alloc_align
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:__rmqueue_pcplist
  - mm/page_alloc.c:split_page
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:prep_compound_page
  - mm/page_alloc.c:prep_compound_page
  - mm/page_alloc.c:prep_compound_page
  - mm/page_alloc.c:bad_page
```
```
In mm/madvise.c (ffffffff81461e50)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - mm/madvise.c:anon_vma_name_alloc
```
```
In mm/swap_state.c (ffffffff8146664b)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - mm/swap_state.c:init_swap_address_space
  - mm/swap_state.c:swap_cluster_readahead
```
```
In mm/zswap.c (ffffffff8146e617)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - mm/zswap.c:zswap_pool_create
  - mm/zswap.c:zswap_pool_create
```
```
In mm/hugetlb.c (ffffffff8391ac13)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - mm/hugetlb.c:gather_bootmem_prealloc
  - mm/hugetlb.c:gather_bootmem_prealloc
  - mm/hugetlb.c:gather_bootmem_prealloc
  - mm/hugetlb.c:__prep_compound_gigantic_folio
  - mm/hugetlb.c:__prep_compound_gigantic_folio
  - mm/hugetlb.c:__prep_compound_gigantic_folio
  - mm/hugetlb.c:__prep_compound_gigantic_folio
  - mm/hugetlb.c:__destroy_compound_gigantic_folio
  - mm/hugetlb.c:__destroy_compound_gigantic_folio
  - mm/hugetlb.c:__destroy_compound_gigantic_folio
  - mm/hugetlb.c:__destroy_compound_gigantic_folio
  - mm/hugetlb.c:resv_map_alloc
```
```
In mm/mempolicy.c (ffffffff81482e4f)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - mm/mempolicy.c:shared_policy_replace
  - mm/mempolicy.c:shared_policy_replace
  - mm/mempolicy.c:__mpol_dup
  - mm/mempolicy.c:mpol_new
```
```
In mm/kfence/core.c (ffffffff8149369f)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
```
```
In mm/memory-tiers.c (ffffffff8149afa1)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - mm/memory-tiers.c:alloc_memory_type
```
```
In mm/huge_memory.c (ffffffff814a30b9)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - mm/huge_memory.c:mm_get_huge_zero_page
```
```
In mm/memcontrol.c (ffffffff814b4e3f)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_online
```
```
In mm/zpool.c (ffffffff814caa79)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - mm/zpool.c:zpool_register_driver
```
```
In mm/zsmalloc.c (ffffffff814cc0b2)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_create_pool
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:__free_zspage
```
```
In mm/memremap.c (ffffffff814d4eda)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - mm/memremap.c:zone_device_page_init
  - mm/memremap.c:free_zone_device_page
```
```
In mm/page_reporting.c (ffffffff814d8697)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - mm/page_reporting.c:page_reporting_register
  - mm/page_reporting.c:page_reporting_process
  - mm/page_reporting.c:page_reporting_cycle
```
```
In mm/bootmem_info.c (ffffffff814d88ab)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - mm/bootmem_info.c:put_page_bootmem
```
```
In fs/super.c (ffffffff814e52ce)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - fs/super.c:alloc_super
```
```
In fs/exec.c (ffffffff814eab7e)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - fs/exec.c:unshare_sighand
```
```
In fs/namei.c (ffffffff814f187f)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - fs/namei.c:getname_kernel
```
```
In fs/dcache.c (ffffffff8150483b)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - fs/dcache.c:__d_alloc
```
```
In fs/inode.c (ffffffff81508953)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - fs/inode.c:inode_init_always
  - fs/inode.c:inode_init_always
  - fs/inode.c:inode_init_always
  - fs/inode.c:inode_init_always
```
```
In fs/file.c (ffffffff8150f1b8)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - fs/file.c:dup_fd
```
```
In fs/namespace.c (ffffffff815135f5)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In fs/fsopen.c (ffffffff8153aacb)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - fs/fsopen.c:fscontext_alloc_log
```
```
In fs/mnt_idmapping.c (ffffffff8153bb2f)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - fs/mnt_idmapping.c:alloc_mnt_idmap
```
```
In fs/notify/group.c (ffffffff81547ff5)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_alloc_group
  - fs/notify/group.c:fsnotify_alloc_group
```
```
In fs/notify/mark.c (ffffffff815487cb)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_init_mark
```
```
In fs/eventpoll.c (ffffffff81552e4a)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_create
```
```
In fs/eventfd.c (ffffffff81557994)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - fs/eventfd.c:do_eventfd
```
```
In fs/userfaultfd.c (ffffffff81558035)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - fs/userfaultfd.c:new_userfaultfd
  - fs/userfaultfd.c:new_userfaultfd
  - fs/userfaultfd.c:dup_userfaultfd
  - fs/userfaultfd.c:dup_userfaultfd
```
```
In fs/aio.c (ffffffff81560f12)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:__ia32_sys_io_destroy
  - fs/aio.c:__x64_sys_io_destroy
  - fs/aio.c:exit_aio
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
```
```
In fs/crypto/keyring.c (ffffffff8156acf4)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
```
```
In fs/crypto/keysetup_v1.c (ffffffff8156d82d)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_get_direct_key
```
```
In fs/backing-file.c (ffffffff815818ae)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
```
```
In fs/mbcache.c (ffffffff81582546)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/posix_acl.c (ffffffff81583974)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - fs/posix_acl.c:posix_acl_from_mode
  - fs/posix_acl.c:posix_acl_clone
```
```
In fs/coredump.c (ffffffff8158545a)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - fs/coredump.c:coredump_wait
```
```
In fs/iomap/direct-io.c (ffffffff8158ef49)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:__iomap_dio_rw
```
```
In fs/quota/dquot.c (ffffffff81592cda)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - fs/quota/dquot.c:dqget
```
```
In fs/proc/generic.c (ffffffff815aa03d)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - fs/proc/generic.c:__proc_create
```
```
In fs/kernfs/inode.c (ffffffff815b9473)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
```
```
In fs/kernfs/dir.c (ffffffff815ba5fe)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - fs/kernfs/dir.c:__kernfs_new_node
  - fs/kernfs/dir.c:__kernfs_new_node
```
```
In fs/kernfs/file.c (ffffffff815bdc5e)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_fop_open
```
```
In fs/configfs/dir.c (ffffffff815c25c1)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_new_dirent
  - fs/configfs/dir.c:new_fragment
```
```
In fs/configfs/item.c (ffffffff815c637c)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - fs/configfs/item.c:config_group_init_type_name
  - fs/configfs/item.c:config_item_init_type_name
```
```
In fs/ext4/mballoc.c (ffffffff8160520d)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_init
```
```
In fs/ext4/page-io.c (ffffffff81612b7b)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_init_io_end
```
```
In fs/ext4/super.c (ffffffff8163c251)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:ext4_alloc_inode
  - fs/ext4/super.c:ext4_alloc_inode
```
```
In fs/ext4/fast_commit.c (ffffffff81646905)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_init_inode
```
```
In fs/ext4/orphan.c (ffffffff81649d71)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - fs/ext4/orphan.c:ext4_init_orphan_info
```
```
In fs/jbd2/transaction.c (ffffffff8164cce9)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
```
```
In fs/jbd2/journal.c (ffffffff8165afdf)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_init_common
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/ecryptfs/main.c (ffffffff8167d42b)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_get_lower_file
```
```
In fs/ecryptfs/super.c (ffffffff8167d7a4)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - fs/ecryptfs/super.c:ecryptfs_alloc_inode
```
```
In fs/ecryptfs/miscdev.c (ffffffff83926c45)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - fs/ecryptfs/miscdev.c:ecryptfs_init_ecryptfs_miscdev
```
```
In fs/fuse/dev.c (ffffffff8168acc3)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_request_alloc
```
```
In fs/fuse/file.c (ffffffff81699564)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_file_alloc
```
```
In fs/fuse/inode.c (ffffffff8169d83a)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_conn_init
  - fs/fuse/inode.c:fuse_conn_init
  - fs/fuse/inode.c:fuse_conn_init
  - fs/fuse/inode.c:fuse_sync_bucket_alloc
  - fs/fuse/inode.c:fuse_iget
```
```
In fs/fuse/dax.c (ffffffff816a3ef0)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
```
```
In fs/debugfs/file.c (ffffffff816a7435)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_atomic_t_set
  - fs/debugfs/file.c:debugfs_file_get
```
```
In fs/tracefs/event_inode.c (ffffffff816abe29)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - fs/tracefs/event_inode.c:eventfs_create_events_dir
  - fs/tracefs/event_inode.c:eventfs_create_dir
```
```
In ipc/util.c (ffffffff816b1395)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In ipc/sem.c (ffffffff816b99d0)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - ipc/sem.c:copy_semundo
  - ipc/sem.c:find_alloc_undo
```
```
In ipc/namespace.c (ffffffff816c193b)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
```
```
In security/keys/key.c (ffffffff816c3d3c)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_user_lookup
  - security/keys/key.c:key_user_lookup
  - security/keys/key.c:key_user_lookup
```
```
In security/selinux/avc.c (ffffffff816e1fad)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - security/selinux/avc.c:selinux_avc_init
  - security/selinux/avc.c:selinux_avc_init
```
```
In security/selinux/ss/services.c (ffffffff81709249)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
```
```
In security/smack/smack_access.c (ffffffff817161c5)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - security/smack/smack_access.c:smack_populate_secattr
```
```
In security/tomoyo/condition.c (ffffffff81723d9c)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_commit_condition
```
```
In security/tomoyo/gc.c (ffffffff8172a523)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - security/tomoyo/gc.c:tomoyo_collect_entry
  - security/tomoyo/gc.c:tomoyo_collect_entry
  - security/tomoyo/gc.c:tomoyo_collect_entry
```
```
In security/tomoyo/memory.c (ffffffff8172b3d3)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_name
  - security/tomoyo/memory.c:tomoyo_get_group
```
```
In security/apparmor/apparmorfs.c (ffffffff81734a9d)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_write_access
```
```
In security/apparmor/audit.c (ffffffff81737288)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - security/apparmor/audit.c:aa_dup_audit_data
```
```
In security/apparmor/lib.c (ffffffff8173a3c9)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - security/apparmor/lib.c:aa_str_alloc
```
```
In security/apparmor/match.c (ffffffff8173b075)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
```
```
In security/apparmor/policy.c (ffffffff81743a8a)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_alloc_pdb
```
```
In security/apparmor/policy_unpack.c (ffffffff817499ba)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:aa_loaddata_alloc
```
```
In security/apparmor/policy_ns.c (ffffffff81755df8)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:alloc_ns
```
```
In security/apparmor/label.c (ffffffff8175842c)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_alloc
  - security/apparmor/label.c:aa_alloc_proxy
```
```
In security/apparmor/notify.c (ffffffff817658e9)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - security/apparmor/notify.c:aa_new_listener
  - security/apparmor/notify.c:aa_new_listener
```
```
In security/landlock/object.c (ffffffff8176b147)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - security/landlock/object.c:landlock_create_object
```
```
In security/landlock/ruleset.c (ffffffff8176bdd7)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - security/landlock/ruleset.c:landlock_merge_ruleset
  - security/landlock/ruleset.c:landlock_merge_ruleset
  - security/landlock/ruleset.c:landlock_create_ruleset
```
```
In security/integrity/ima/ima_policy.c (ffffffff8392f14a)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_init_policy
```
```
In crypto/api.c (ffffffff8177f7e8)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - crypto/api.c:__crypto_alloc_tfmgfp
  - crypto/api.c:crypto_alg_mod_lookup
```
```
In crypto/algapi.c (ffffffff817802a3)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_check_alg
```
```
In block/fops.c (ffffffff817a9df6)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
```
```
In block/bio.c (ffffffff817ac0e5)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - block/bio.c:bio_init_clone
  - block/bio.c:bio_init_clone
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_reset
```
```
In block/blk-core.c (ffffffff817b3d18)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - block/blk-core.c:blk_alloc_queue
  - block/blk-core.c:blk_alloc_queue
```
```
In block/blk-flush.c (ffffffff817b703c)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - block/blk-flush.c:blk_flush_complete_seq
```
```
In block/blk-ioc.c (ffffffff817b8bff)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - block/blk-ioc.c:alloc_io_context
```
```
In block/blk-mq.c (ffffffff817c37f9)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_hctx
```
```
In block/bsg-lib.c (ffffffff817e2209)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_queue_rq
```
```
In block/blk-cgroup.c (ffffffff817e4538)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_css_alloc
```
```
In block/blk-iocost.c (ffffffff817f0bb5)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - block/blk-iocost.c:blk_iocost_init
```
```
In block/blk-wbt.c (ffffffff817ff720)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_init
```
```
In block/blk-crypto-profile.c (ffffffff81808ada)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - block/blk-crypto-profile.c:blk_crypto_get_keyslot
```
```
In io_uring/io_uring.c (ffffffff81813dca)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_uring_try_cancel_requests
  - io_uring/io_uring.c:io_cqring_wait
  - io_uring/io_uring.c:io_cqring_wait
  - io_uring/io_uring.c:io_wq_submit_work
  - io_uring/io_uring.c:__io_arm_ltimeout
  - io_uring/io_uring.c:__io_arm_ltimeout
  - io_uring/io_uring.c:io_ring_ctx_alloc
```
```
In io_uring/timeout.c (ffffffff8181df06)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - io_uring/timeout.c:io_timeout_fn
  - io_uring/timeout.c:io_flush_timeouts
```
```
In io_uring/sqpoll.c (ffffffff8181f452)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - io_uring/sqpoll.c:io_get_sq_data
  - io_uring/sqpoll.c:io_get_sq_data
```
```
In io_uring/tctx.c (ffffffff8182103a)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - io_uring/tctx.c:io_uring_alloc_task_context
  - io_uring/tctx.c:io_uring_alloc_task_context
  - io_uring/tctx.c:io_uring_alloc_task_context
```
```
In io_uring/poll.c (ffffffff818229eb)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - io_uring/poll.c:__io_arm_poll_handler
```
```
In io_uring/rsrc.c (ffffffff8182664c)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - io_uring/rsrc.c:io_rsrc_ref_quiesce
  - io_uring/rsrc.c:io_rsrc_ref_quiesce
```
```
In io_uring/notif.c (ffffffff8182a502)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - io_uring/notif.c:io_alloc_notif
```
```
In io_uring/waitid.c (ffffffff8182ac83)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - io_uring/waitid.c:io_waitid
```
```
In io_uring/register.c (ffffffff8182afdd)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - io_uring/register.c:io_eventfd_register
  - io_uring/register.c:io_eventfd_register
```
```
In io_uring/io-wq.c (ffffffff8182e6ec)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_wq_create
  - io_uring/io-wq.c:io_wq_create
  - io_uring/io-wq.c:create_io_worker
```
```
In lib/rhashtable.c (ffffffff8185e230)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_init
```
```
In lib/refcount.c (ffffffff8186000b)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - lib/refcount.c:refcount_dec_and_lock_irqsave
  - lib/refcount.c:refcount_dec_and_lock
  - lib/refcount.c:refcount_dec_and_mutex_lock
```
```
In lib/rcuref.c (ffffffff8186011d)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - lib/rcuref.c:rcuref_put_slowpath
  - lib/rcuref.c:rcuref_put_slowpath
  - lib/rcuref.c:rcuref_get_slowpath
  - lib/rcuref.c:rcuref_get_slowpath
```
```
In lib/cpu_rmap.c (ffffffff81925523)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - lib/cpu_rmap.c:alloc_cpu_rmap
```
```
In lib/closure.c (ffffffff8223bf77)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - lib/closure.c:__closure_sync
  - lib/closure.c:__closure_wake_up
  - lib/closure.c:closure_put
```
```
In lib/stackdepot.c (ffffffff81928287)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - lib/stackdepot.c:depot_alloc_stack
  - lib/stackdepot.c:depot_alloc_stack
```
```
In lib/sbitmap.c (ffffffff8192c276)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_queue_wake_up
  - lib/sbitmap.c:sbitmap_queue_init_node
  - lib/sbitmap.c:sbitmap_queue_init_node
  - lib/sbitmap.c:sbitmap_queue_init_node
  - lib/sbitmap.c:sbitmap_queue_init_node
```
```
In drivers/pinctrl/core.c (ffffffff819360bd)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:create_pinctrl
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff81951b46)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:linereq_create
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff819a4c4a)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
```
```
In drivers/rapidio/rio.c (ffffffff819b908d)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_register_mport
  - drivers/rapidio/rio.c:rio_mport_initialize
  - drivers/rapidio/rio.c:rio_del_device
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff819c409b)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:do_register_framebuffer
```
```
In drivers/acpi/ec.c (ffffffff819f76d0)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_add_query_handler
```
```
In drivers/acpi/thermal.c (ffffffff81a6d155)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - drivers/acpi/thermal.c:acpi_thermal_add
```
```
In drivers/acpi/apei/ghes.c (ffffffff81a7b8c4)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_alloc
```
```
In drivers/clk/clk.c (ffffffff81a90774)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_core_init
```
```
In drivers/dma/dmaengine.c (ffffffff81a98ff8)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaengine_get_unmap_data
  - drivers/dma/dmaengine.c:dma_async_device_register
```
```
In drivers/pmdomain/core.c (ffffffff81aa1988)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - drivers/pmdomain/core.c:pm_genpd_init
```
```
In drivers/xen/balloon.c (ffffffff81ab6de7)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_thread
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff81ac6fa3)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_open
```
```
In drivers/reset/core.c (ffffffff81ae3329)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - drivers/reset/core.c:__reset_control_get_internal
```
```
In drivers/tty/tty_io.c (ffffffff81ae9864)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:alloc_tty_struct
```
```
In drivers/tty/tty_buffer.c (ffffffff81af2181)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_init
  - drivers/tty/tty_buffer.c:tty_buffer_init
```
```
In drivers/tty/tty_port.c (ffffffff81af25c2)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_init
```
```
In drivers/tty/serial/serial_core.c (ffffffff81b15eed)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:serial_core_add_one_port
```
```
In drivers/char/random.c (ffffffff81b339b1)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - drivers/char/random.c:try_to_generate_entropy
```
```
In drivers/char/virtio_console.c (ffffffff81b367e8)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
```
```
In drivers/char/hw_random/core.c (ffffffff81b3a624)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
```
```
In drivers/char/agp/backend.c (ffffffff81b3bd73)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - drivers/char/agp/backend.c:agp_alloc_bridge
  - drivers/char/agp/backend.c:agp_alloc_bridge
```
```
In drivers/iommu/dma-iommu.c (ffffffff81b7c14d)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_init_fq
  - drivers/iommu/dma-iommu.c:fq_flush_timeout
```
```
In drivers/iommu/iommu-sva.c (ffffffff81b81080)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - drivers/iommu/iommu-sva.c:iommu_sva_bind_device
```
```
In drivers/connector/cn_queue.c (ffffffff81b82129)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - drivers/connector/cn_queue.c:cn_queue_alloc_dev
  - drivers/connector/cn_queue.c:cn_queue_alloc_callback_entry
```
```
In drivers/base/core.c (ffffffff81b8ab3d)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/power/runtime.c (ffffffff81ba8d46)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_init
  - drivers/base/power/runtime.c:pm_runtime_init
```
```
In drivers/base/power/wakeup.c (ffffffff81baf960)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:pm_wakeup_clear
```
```
In drivers/base/firmware_loader/main.c (ffffffff81bb2f85)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:alloc_lookup_fw_priv
```
```
In drivers/block/loop.c (ffffffff81bd053e)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
```
```
In drivers/nvdimm/core.c (ffffffff81bf63cc)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:alloc_nvdimm_map
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff81bfa659)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:__nvdimm_create
```
```
In drivers/nvdimm/dimm.c (ffffffff81bfbf33)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
```
```
In drivers/dax/bus.c (ffffffff81c0f554)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - drivers/dax/bus.c:alloc_dax_region
```
```
In drivers/dma-buf/dma-fence.c (ffffffff81c13a8e)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_allocate_private_stub
  - drivers/dma-buf/dma-fence.c:dma_fence_get_stub
```
```
In drivers/dma-buf/dma-fence-array.c (ffffffff81c149e0)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_create
```
```
In drivers/dma-buf/sw_sync.c (ffffffff81c19dbe)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_timeline_create
```
```
In drivers/scsi/scsi.c (ffffffff81c1e108)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_finish_command
  - drivers/scsi/scsi.c:scsi_finish_command
  - drivers/scsi/scsi.c:scsi_finish_command
```
```
In drivers/scsi/hosts.c (ffffffff81c1f726)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/scsi/scsi_lib.c (ffffffff81c2a32b)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:__scsi_queue_insert
  - drivers/scsi/scsi_lib.c:__scsi_queue_insert
  - drivers/scsi/scsi_lib.c:__scsi_queue_insert
```
```
In drivers/scsi/scsi_scan.c (ffffffff81c2c50e)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
```
```
In drivers/scsi/sd.c (ffffffff81c3fcc5)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
```
```
In drivers/scsi/sg.c (ffffffff81c4b3cd)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_add_sfp
  - drivers/scsi/sg.c:sg_alloc
  - drivers/scsi/sg.c:sg_alloc
```
```
In drivers/ata/libata-core.c (ffffffff81c4fe74)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_init
  - drivers/ata/libata-core.c:ata_host_alloc
```
```
In drivers/gpu/drm/drm_atomic.c (ffffffff81c7b275)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_atomic.c:drm_atomic_state_init
```
```
In drivers/gpu/drm/drm_auth.c (ffffffff81c7e897)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_auth.c:drm_master_create
```
```
In drivers/gpu/drm/drm_connector.c (ffffffff81c87331)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_connector.c:drm_mode_create_tile_group
```
```
In drivers/gpu/drm/drm_drv.c (ffffffff81c8b7e2)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_drv.c:drm_dev_init
```
```
In drivers/gpu/drm/drm_gem.c (ffffffff81c9b73c)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_gem.c:drm_gem_private_object_init
```
```
In drivers/gpu/drm/drm_mode_object.c (ffffffff81ca3e70)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
```
```
In drivers/gpu/drm/drm_syncobj.c (ffffffff81cafd80)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_create
```
```
In drivers/gpu/drm/drm_atomic_helper.c (ffffffff81cc3ed1)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_atomic_helper.c:drm_atomic_helper_setup_commit
```
```
In drivers/net/phy/phy_device.c (ffffffff81cf03c0)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_package_join
```
```
In drivers/net/phy/sfp-bus.c (ffffffff81cf5c11)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_bus_get
```
```
In drivers/net/pse-pd/pse_core.c (0)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81d18c6c)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
```
```
In drivers/usb/core/usb.c (ffffffff81d2d8cb)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - drivers/usb/core/usb.c:usb_alloc_dev
```
```
In drivers/usb/core/hub.c (ffffffff81d38419)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_probe
```
```
In drivers/usb/core/hcd.c (ffffffff81d3a2b4)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:__usb_create_hcd
```
```
In drivers/usb/core/urb.c (ffffffff81d3cf9f)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_init_urb
```
```
In drivers/usb/core/config.c (ffffffff81d4622e)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_configuration
```
```
In drivers/thermal/thermal_core.c (ffffffff81dff17a)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register_with_trips
  - drivers/thermal/thermal_core.c:thermal_bind_cdev_to_trip
```
```
In drivers/thermal/intel/therm_throt.c (ffffffff81e09ee4)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - drivers/thermal/intel/therm_throt.c:intel_init_thermal
```
```
In drivers/md/md.c (ffffffff81e20069)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_run
  - drivers/md/md.c:max_corrected_read_errors_store
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:errors_store
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:mddev_init
  - drivers/md/md.c:mddev_init
  - drivers/md/md.c:mddev_init
  - drivers/md/md.c:mddev_init
  - drivers/md/md.c:submit_flushes
```
```
In drivers/md/md-bitmap.c (ffffffff81e28801)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
```
```
In drivers/md/dm.c (ffffffff81e2e938)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:dm_get_table_device
  - drivers/md/dm.c:alloc_io
```
```
In drivers/md/dm-table.c (ffffffff8222b336)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_get_device
```
```
In drivers/md/dm-stripe.c (ffffffff81e366fb)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:stripe_ctr
```
```
In drivers/md/dm-io.c (ffffffff81e3b233)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - drivers/md/dm-io.c:dm_io
  - drivers/md/dm-io.c:sync_io
```
```
In drivers/md/dm-kcopyd.c (ffffffff81e3bc10)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
  - drivers/md/dm-kcopyd.c:dm_kcopyd_copy
```
```
In drivers/md/dm-stats.c (ffffffff81e3dd98)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
```
```
In drivers/edac/ghes_edac.c (ffffffff81e467ec)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
```
```
In drivers/opp/core.c (ffffffff81e4bd96)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - drivers/opp/core.c:_opp_add
  - drivers/opp/core.c:_add_opp_table_indexed
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff81e55f78)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_stop
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
  - drivers/cpufreq/cpufreq_governor.c:dbs_update_util_handler
  - drivers/cpufreq/cpufreq_governor.c:dbs_work_handler
```
```
In drivers/mmc/core/sdio_irq.c (ffffffff81e7f701)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_irq.c:sdio_release_irq
  - drivers/mmc/core/sdio_irq.c:sdio_claim_irq
```
```
In drivers/firmware/efi/efi.c (ffffffff8222b494)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81e9aeca)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc
```
```
In drivers/devfreq/devfreq.c (ffffffff81ea5394)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
```
In drivers/nvmem/core.c (ffffffff81eb1bef)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - drivers/nvmem/core.c:nvmem_register
```
```
In drivers/hte/hte.c (ffffffff81eb618a)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - drivers/hte/hte.c:hte_ts_put
```
```
In drivers/dpll/dpll_core.c (ffffffff81eb6bad)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - drivers/dpll/dpll_core.c:dpll_pin_get
  - drivers/dpll/dpll_core.c:dpll_device_get
  - drivers/dpll/dpll_core.c:dpll_xa_ref_dpll_add
  - drivers/dpll/dpll_core.c:dpll_xa_ref_pin_add
```
```
In net/core/sock.c (ffffffff81ec586b)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - net/core/sock.c:sock_init_data_uid
  - net/core/sock.c:sock_init_data_uid
  - net/core/sock.c:sock_init_data_uid
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_alloc
  - net/core/sock.c:sock_set_timestamping
  - net/core/sock.c:sock_set_timestamping
  - net/core/sock.c:sock_set_timestamping
```
```
In net/core/skbuff.c (ffffffff81ed0c6f)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_ext_maybe_cow
  - net/core/skbuff.c:__skb_ext_alloc
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:pskb_carve_inside_header
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:msg_zerocopy_realloc
  - net/core/skbuff.c:msg_zerocopy_realloc
  - net/core/skbuff.c:__skb_clone
  - net/core/skbuff.c:__alloc_skb
  - net/core/skbuff.c:__build_skb_around
  - net/core/skbuff.c:__build_skb_around
  - net/core/skbuff.c:slab_build_skb
  - net/core/skbuff.c:slab_build_skb
```
```
In net/core/net_namespace.c (ffffffff81ee3ce4)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - net/core/net_namespace.c:copy_net_ns
  - net/core/net_namespace.c:copy_net_ns
  - net/core/net_namespace.c:setup_net
  - net/core/net_namespace.c:setup_net
```
```
In net/core/dev.c (ffffffff81eeda5d)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - net/core/dev.c:dev_kfree_skb_irq_reason
```
```
In net/core/dst.c (ffffffff81f03b67)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - net/core/dst.c:__metadata_dst_init
  - net/core/dst.c:dst_cow_metrics_generic
  - net/core/dst.c:dst_alloc
```
```
In net/core/neighbour.c (ffffffff81f08355)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:neigh_alloc
```
```
In net/core/filter.c (ffffffff81f3231c)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - net/core/filter.c:__sk_attach_prog
```
```
In net/core/flow_offload.c (ffffffff81f3ac06)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - net/core/flow_offload.c:flow_indr_dev_register
```
```
In net/core/gro.c (ffffffff81f3ccfe)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - net/core/gro.c:skb_gro_receive
```
```
In net/core/page_pool.c (ffffffff81f432a8)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_init
  - net/core/page_pool.c:page_pool_init
```
```
In net/core/netpoll.c (ffffffff81f47e04)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - net/core/netpoll.c:__netpoll_setup
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:zap_completion_queue
```
```
In net/core/fib_rules.c (ffffffff81f49eda)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_default_rule_add
```
```
In net/core/skmsg.c (ffffffff81f65f66)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_init
```
```
In net/sched/sch_generic.c (ffffffff81f70720)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_alloc
```
```
In net/sched/cls_api.c (ffffffff81f7e82d)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tcf_block_get_ext
```
```
In net/sched/act_api.c (ffffffff81f8102f)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_idr_create
  - net/sched/act_api.c:tcf_idr_create
```
```
In net/ipv4/route.c (ffffffff81faf0b5)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_genid_init
  - net/ipv4/route.c:rt_genid_init
  - net/ipv4/route.c:rt_genid_init
```
```
In net/ipv4/inetpeer.c (ffffffff81fb73f3)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/ip_output.c (ffffffff81fc003f)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_queue_xmit
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81fc84c6)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81fcb1e8)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_complete_hashdance
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_hash_add
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
```
```
In net/ipv4/tcp.c (ffffffff81fcfcc2)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_skb_entail
```
```
In net/ipv4/tcp_input.c (ffffffff81fd8fa3)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/tcp_output.c (ffffffff81fe506d)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_queue_skb
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_clone_payload
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ff1431)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_sk_init
  - net/ipv4/tcp_ipv4.c:tcp_sk_init
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81ffea8b)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_create_child
```
```
In net/ipv4/datagram.c (ffffffff82000b15)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (0)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff82017b0f)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_init
```
```
In net/ipv4/af_inet.c (ffffffff82019b21)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
```
```
In net/ipv4/igmp.c (ffffffff8201fe37)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - net/ipv4/igmp.c:____ip_mc_inc_group
```
```
In net/ipv4/fib_frontend.c (ffffffff82022922)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
```
```
In net/ipv4/fib_semantics.c (ffffffff82028ea1)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_rebalance
```
```
In net/ipv4/inet_fragment.c (ffffffff820312ee)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_find
  - net/ipv4/inet_fragment.c:inet_frags_init
```
```
In net/ipv4/metrics.c (ffffffff82036e92)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
```
```
In net/ipv4/nexthop.c (ffffffff8203dcc5)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:nh_hthr_group_rebalance
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff8203dfaf)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:proc_tfo_blackhole_detect_timeout
```
```
In net/ipv4/ipmr.c (ffffffff8204771f)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv4/syncookies.c (ffffffff8204ae8d)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:tcp_get_cookie_sock
```
```
In net/ipv4/tcp_sigpool.c (ffffffff8204cf53)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - net/ipv4/tcp_sigpool.c:tcp_sigpool_alloc_ahash
  - net/ipv4/tcp_sigpool.c:tcp_sigpool_alloc_ahash
```
```
In net/ipv4/cipso_ipv4.c (ffffffff82050c8a)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_add
```
```
In net/ipv4/tcp_ao.c (ffffffff8205438d)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - net/ipv4/tcp_ao.c:tcp_ao_alloc_info
```
```
In net/xfrm/xfrm_policy.c (ffffffff8205b118)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
```
```
In net/xfrm/xfrm_state.c (ffffffff820652bf)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
```
```
In net/xfrm/xfrm_output.c (0)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
```
```
In net/unix/af_unix.c (ffffffff82078e40)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_autobind
  - net/unix/af_unix.c:unix_create_addr
```
```
In net/ipv6/af_inet6.c (ffffffff8207fbc4)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_net_init
```
```
In net/ipv6/anycast.c (ffffffff8208111e)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
```
```
In net/ipv6/addrconf.c (ffffffff8208ec6f)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_dev
```
```
In net/ipv6/route.c (ffffffff8209a826)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ip6_dst_gc
  - net/ipv6/route.c:ip6_dst_gc
```
```
In net/ipv6/ip6_fib.c (ffffffff820ab03d)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_metric_set
  - net/ipv6/ip6_fib.c:fib6_info_alloc
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff820aefb9)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt
```
```
In net/ipv6/mcast.c (ffffffff820c3e04)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
```
```
In net/ipv6/exthdrs.c (ffffffff820d1275)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_dup_options
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff820d4159)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:fl_create
```
```
In net/ipv6/ip6mr.c (ffffffff820de911)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/ipv6/calipso.c (ffffffff820e725d)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_doi_add
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff820ef599)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_build_state
```
```
In net/packet/af_packet.c (ffffffff820f9b95)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - net/packet/af_packet.c:fanout_add
  - net/packet/af_packet.c:fanout_add
  - net/packet/af_packet.c:fanout_add
```
```
In net/devlink/core.c (ffffffff820fec27)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - net/devlink/core.c:devlink_alloc_ns
  - net/devlink/core.c:devlink_rel_nested_in_add
```
```
In net/devlink/rate.c (ffffffff82119501)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - net/devlink/rate.c:devlink_nl_rate_new_doit
```
```
In net/xdp/xdp_umem.c (ffffffff821402ad)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_reg
```
```
In net/xdp/xsk_buff_pool.c (ffffffff82141db6)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_dma_map
  - net/xdp/xsk_buff_pool.c:xp_create_and_assign_umem
```
```
In net/mctp/device.c (ffffffff8216489b)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - net/mctp/device.c:mctp_add_dev
```
```
In net/mctp/route.c (ffffffff82165dd0)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - net/mctp/route.c:mctp_route_add
  - net/mctp/route.c:mctp_key_alloc
```
```
In lib/klist.c (ffffffff82179ac7)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - lib/klist.c:klist_add_before
  - lib/klist.c:klist_add_behind
  - lib/klist.c:klist_add_tail
  - lib/klist.c:klist_add_head
```
```
In lib/kobject.c (ffffffff8217b199)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - lib/kobject.c:kset_register
```
```
In lib/objpool.c (ffffffff82191cf2)
Location: arch/x86/include/asm/atomic.h:26
Inline: True
Inline callers:
  - lib/objpool.c:objpool_init
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
In arch/x86/kernel/tboot.c (ffffffff8289c9c9)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104c84c)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:fake_panic_set
  - arch/x86/kernel/cpu/mce/core.c:fake_panic_set
  - arch/x86/kernel/cpu/mce/core.c:fake_panic_set
  - arch/x86/kernel/cpu/mce/core.c:fake_panic_set
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff810524a9)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff81052fd7)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff810564bd)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In arch/x86/kernel/reboot.c (ffffffff81062947)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff81065376)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_target
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
```
```
In arch/x86/kernel/kgdb.c (ffffffff81073f7f)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In arch/x86/mm/init_64.c (ffffffff81a6a3d2)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pagetable
```
```
In kernel/fork.c (ffffffff81098320)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:mm_init
  - kernel/fork.c:mm_init
  - kernel/fork.c:mm_init
```
```
In kernel/softirq.c (ffffffff810a0c15)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/softirq.c:tasklet_init
```
```
In kernel/user.c (ffffffff810a978e)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/user.c:alloc_uid
```
```
In kernel/workqueue.c (ffffffff810bec50)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_offline_cpu
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:flush_workqueue_prep_pwqs
```
```
In kernel/pid.c (ffffffff810c0499)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/pid.c:alloc_pid
```
```
In kernel/nsproxy.c (ffffffff810c68e1)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/nsproxy.c:create_new_namespaces
```
```
In kernel/cred.c (ffffffff810c8193)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:cred_alloc_blank
```
```
In kernel/smpboot.c (ffffffff810c9d9c)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/smpboot.c:cpu_wait_death
  - kernel/smpboot.c:cpu_check_up_prepare
```
```
In kernel/groups.c (ffffffff810ca818)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/groups.c:groups_alloc
```
```
In kernel/sched/core.c (ffffffff828b63b4)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init
```
```
In kernel/sched/fair.c (ffffffff810e323a)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_fault
```
```
In kernel/sched/cpupri.c (ffffffff810ef687)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_init
```
```
In kernel/sched/topology.c (ffffffff810f0eaf)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:init_defrootdomain
```
```
In kernel/sched/autogroup.c (ffffffff810f3a9f)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
  - kernel/sched/autogroup.c:autogroup_init
```
```
In kernel/sched/membarrier.c (ffffffff810fabdf)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/sched/membarrier.c:membarrier_exec_mmap
```
```
In kernel/sched/psi.c (ffffffff810fb257)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_trigger_destroy
  - kernel/sched/psi.c:psi_poll_work
  - kernel/sched/psi.c:group_init
```
```
In kernel/locking/mutex.c (ffffffff810fc7a4)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/locking/mutex.c:__mutex_init
```
```
In kernel/locking/rwsem.c (ffffffff810fcbfc)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:__init_rwsem
```
```
In kernel/power/swap.c (ffffffff81106ade)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:save_image
```
```
In kernel/irq/manage.c (ffffffff81110219)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_notifier
```
```
In kernel/rcu/srcutree.c (ffffffff8111d8f2)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
```
```
In kernel/rcu/tree.c (ffffffff8111efd0)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In kernel/futex.c (ffffffff828ba0ef)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/futex.c:futex_init
```
```
In kernel/module.c (ffffffff8114dfec)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/module.c:load_module
```
```
In kernel/kexec_core.c (ffffffff81152a92)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_free_reserved_phys_range
  - kernel/kexec_core.c:crash_kexec
```
```
In kernel/cgroup/cgroup.c (ffffffff81158420)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:init_cgroup_root
  - kernel/cgroup/cgroup.c:find_css_set
```
```
In kernel/cgroup/namespace.c (ffffffff811600d1)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
```
```
In kernel/utsname.c (ffffffff81169cd8)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/utsname.c:copy_utsname
```
```
In kernel/user_namespace.c (ffffffff8116afe5)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In kernel/pid_namespace.c (ffffffff8116bb48)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In kernel/stop_machine.c (ffffffff8116ca5a)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:stop_two_cpus
  - kernel/stop_machine.c:multi_cpu_stop
  - kernel/stop_machine.c:cpu_stop_init_done
```
```
In kernel/audit_watch.c (ffffffff81176838)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_init_watch
```
```
In kernel/audit_tree.c (ffffffff81178ce7)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_make_tree
```
```
In kernel/debug/debug_core.c (ffffffff8117c7be)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_tasklet_bpt
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff81181c7f)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In kernel/hung_task.c (ffffffff81187bd5)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/hung_task.c:reset_hung_task_detector
```
```
In kernel/seccomp.c (ffffffff8118a522)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
```
```
In kernel/relay.c (ffffffff8118b3dd)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/relay.c:__relay_reset
```
```
In kernel/trace/trace.c (ffffffff8119e411)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
```
```
In kernel/trace/tracing_map.c (ffffffff811a973e)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_create
  - kernel/trace/tracing_map.c:tracing_map_clear
```
```
In kernel/trace/blktrace.c (ffffffff811af807)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:do_blk_trace_setup
```
```
In kernel/trace/fgraph.c (ffffffff811b254a)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/trace/fgraph.c:start_graph_tracing
  - kernel/trace/fgraph.c:start_graph_tracing
  - kernel/trace/fgraph.c:ftrace_graph_init_task
  - kernel/trace/fgraph.c:ftrace_graph_init_task
```
```
In kernel/trace/trace_events.c (ffffffff811b297c)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_create_new_event
  - kernel/trace/trace_events.c:trace_create_new_event
```
```
In kernel/bpf/syscall.c (ffffffff811d9f0c)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:map_create
```
```
In kernel/bpf/btf.c (ffffffff811f6fec)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_new_fd
```
```
In kernel/events/core.c (ffffffff8120523c)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:alloc_perf_context
```
```
In kernel/events/ring_buffer.c (ffffffff81210cfd)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc
  - kernel/events/ring_buffer.c:rb_alloc_aux
  - kernel/events/ring_buffer.c:perf_aux_output_skip
  - kernel/events/ring_buffer.c:perf_aux_output_end
  - kernel/events/ring_buffer.c:perf_aux_output_begin
  - kernel/events/ring_buffer.c:perf_output_put_handle
```
```
In kernel/events/uprobes.c (ffffffff81214351)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__create_xol_area
```
```
In kernel/padata.c (ffffffff81215ef4)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_alloc_pd
```
```
In kernel/jump_label.c (ffffffff8121751c)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In mm/filemap.c (ffffffff8121fee7)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/shmem.c (ffffffff81238aa2)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_inode
```
```
In mm/backing-dev.c (ffffffff81242165)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_alloc_node
  - mm/backing-dev.c:wb_congested_get_create
  - mm/backing-dev.c:default_bdi_init
```
```
In mm/rmap.c (ffffffff8126dd50)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - mm/rmap.c:hugepage_add_new_anon_rmap
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:anon_vma_ctor
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:__anon_vma_prepare
```
```
In mm/page_alloc.c (ffffffff81279d9f)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:memmap_init_zone_device
  - mm/page_alloc.c:memmap_init_zone_device
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:make_alloc_exact
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:prep_new_page
  - mm/page_alloc.c:prep_new_page
  - mm/page_alloc.c:prep_new_page
  - mm/page_alloc.c:check_new_page_bad
  - mm/page_alloc.c:init_cma_reserved_pageblock
  - mm/page_alloc.c:init_cma_reserved_pageblock
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:bad_page
```
```
In mm/swap_state.c (ffffffff8127fb57)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - mm/swap_state.c:init_swap_address_space
```
```
In mm/frontswap.c (ffffffff812864ef)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_invalidate_area
```
```
In mm/zswap.c (ffffffff81286c16)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - mm/zswap.c:zswap_pool_create
```
```
In mm/hugetlb.c (ffffffff812890fe)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:update_and_free_page
  - mm/hugetlb.c:update_and_free_page
  - mm/hugetlb.c:update_and_free_page
  - mm/hugetlb.c:dequeue_huge_page_nodemask
  - mm/hugetlb.c:resv_map_alloc
```
```
In mm/mempolicy.c (ffffffff812951a8)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:__mpol_dup
```
```
In mm/memory_hotplug.c (ffffffff812a433e)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__online_page_free
  - mm/memory_hotplug.c:put_page_bootmem
```
```
In mm/huge_memory.c (ffffffff812ad778)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In mm/memcontrol.c (ffffffff812ba411)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_select_victim_node
```
```
In mm/zpool.c (ffffffff812c6499)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - mm/zpool.c:zpool_register_driver
```
```
In mm/zsmalloc.c (ffffffff812c749f)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - mm/zsmalloc.c:reset_page
```
```
In fs/super.c (ffffffff812d81b3)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/super.c:alloc_super
```
```
In fs/exec.c (ffffffff812deb81)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In fs/dcache.c (ffffffff812f326e)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/dcache.c:__d_alloc
```
```
In fs/inode.c (ffffffff812f406a)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/inode.c:inode_init_always
  - fs/inode.c:inode_init_always
  - fs/inode.c:inode_init_always
  - fs/inode.c:inode_init_always
```
```
In fs/file.c (ffffffff812f8610)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/file.c:dup_fd
```
```
In fs/namespace.c (ffffffff812f9a91)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In fs/fsopen.c (ffffffff81317558)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/fsopen.c:__ia32_sys_fspick
  - fs/fsopen.c:__x64_sys_fspick
  - fs/fsopen.c:__ia32_sys_fsopen
  - fs/fsopen.c:__x64_sys_fsopen
```
```
In fs/block_dev.c (ffffffff8131dc59)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_direct_IO
```
```
In fs/notify/group.c (ffffffff81325641)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_alloc_group
  - fs/notify/group.c:fsnotify_alloc_group
  - fs/notify/group.c:fsnotify_alloc_group
```
```
In fs/notify/mark.c (ffffffff81325a02)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_init_mark
```
```
In fs/eventfd.c (ffffffff81330155)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/eventfd.c:do_eventfd
```
```
In fs/userfaultfd.c (ffffffff81330880)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/userfaultfd.c:__ia32_sys_userfaultfd
  - fs/userfaultfd.c:__x64_sys_userfaultfd
  - fs/userfaultfd.c:dup_userfaultfd
```
```
In fs/aio.c (ffffffff813369ed)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:__ia32_sys_io_destroy
  - fs/aio.c:__x64_sys_io_destroy
  - fs/aio.c:exit_aio
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
```
```
In fs/io_uring.c (ffffffff8133d191)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_get_req
```
```
In fs/crypto/keyring.c (ffffffff81344de5)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/crypto/keyring.c:add_master_key
```
```
In fs/crypto/keysetup_v1.c (ffffffff81346c7f)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
```
```
In fs/mbcache.c (ffffffff81357dbb)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/posix_acl.c (ffffffff813586a7)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/posix_acl.c:posix_acl_clone
  - fs/posix_acl.c:posix_acl_alloc
```
```
In fs/coredump.c (ffffffff8135a51b)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/iomap/buffered-io.c (ffffffff8135c0a3)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In fs/iomap/direct-io.c (ffffffff8135da3a)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_rw
```
```
In fs/quota/dquot.c (ffffffff81361428)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/quota/dquot.c:dqget
```
```
In fs/proc/generic.c (ffffffff8136fe55)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/proc/generic.c:__proc_create
```
```
In fs/kernfs/dir.c (ffffffff8137c773)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/kernfs/dir.c:__kernfs_new_node
```
```
In fs/kernfs/file.c (ffffffff8137e283)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_fop_open
  - fs/kernfs/file.c:kernfs_fop_open
```
```
In fs/configfs/dir.c (ffffffff813820b1)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_new_dirent
  - fs/configfs/dir.c:new_fragment
```
```
In fs/configfs/item.c (ffffffff81384aa8)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/configfs/item.c:config_group_init_type_name
  - fs/configfs/item.c:config_item_init_type_name
```
```
In fs/ext4/mballoc.c (ffffffff813b8a80)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
```
```
In fs/ext4/page-io.c (ffffffff813c3e1f)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_init_io_end
```
```
In fs/ext4/super.c (ffffffff813d2330)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_alloc_inode
```
```
In fs/jbd2/transaction.c (ffffffff813e81ea)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
```
```
In fs/jbd2/journal.c (ffffffff813f0f69)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_init_common
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/ecryptfs/main.c (ffffffff8140c4b6)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_get_lower_file
```
```
In fs/ecryptfs/super.c (ffffffff8140c6df)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/ecryptfs/super.c:ecryptfs_alloc_inode
```
```
In fs/ecryptfs/miscdev.c (ffffffff828d79dc)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/ecryptfs/miscdev.c:ecryptfs_init_ecryptfs_miscdev
```
```
In fs/fuse/dev.c (ffffffff81417946)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_request_alloc
```
```
In fs/fuse/file.c (ffffffff81422868)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_file_alloc
```
```
In fs/fuse/inode.c (ffffffff81424efb)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_conn_init
  - fs/fuse/inode.c:fuse_conn_init
  - fs/fuse/inode.c:fuse_conn_init
```
```
In fs/debugfs/file.c (ffffffff8142a655)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_atomic_t_set
  - fs/debugfs/file.c:debugfs_file_get
```
```
In ipc/util.c (ffffffff8142f1a5)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In ipc/msg.c (ffffffff828d7ef8)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - ipc/msg.c:msg_init
  - ipc/msg.c:msg_init
```
```
In ipc/sem.c (ffffffff81435f02)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - ipc/sem.c:copy_semundo
  - ipc/sem.c:find_alloc_undo
```
```
In ipc/namespace.c (ffffffff8143c8c2)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - ipc/namespace.c:copy_ipcs
```
```
In security/keys/key.c (ffffffff8143dfea)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_user_lookup
  - security/keys/key.c:key_user_lookup
  - security/keys/key.c:key_user_lookup
```
```
In security/selinux/avc.c (ffffffff8145335b)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - security/selinux/avc.c:selinux_avc_init
  - security/selinux/avc.c:selinux_avc_init
```
```
In security/selinux/ss/services.c (ffffffff81470b39)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
```
```
In security/tomoyo/condition.c (ffffffff8148360a)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
```
```
In security/tomoyo/gc.c (ffffffff81487c57)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In security/tomoyo/memory.c (ffffffff814886c6)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_name
  - security/tomoyo/memory.c:tomoyo_get_group
```
```
In security/apparmor/apparmorfs.c (ffffffff8148f8c1)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_write_access
```
```
In security/apparmor/lib.c (ffffffff81491ffa)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - security/apparmor/lib.c:aa_str_alloc
```
```
In security/apparmor/match.c (ffffffff814929e7)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
```
```
In security/apparmor/policy_unpack.c (ffffffff8149c2dd)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:aa_loaddata_alloc
```
```
In security/apparmor/policy_ns.c (ffffffff814a2376)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:alloc_ns
```
```
In security/apparmor/label.c (ffffffff814a3602)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_alloc
  - security/apparmor/label.c:aa_alloc_proxy
```
```
In crypto/api.c (ffffffff814b6ca8)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - crypto/api.c:crypto_alg_mod_lookup
```
```
In crypto/algapi.c (ffffffff814b7c1d)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - crypto/algapi.c:__crypto_register_alg
  - crypto/algapi.c:crypto_check_alg
```
```
In block/bio.c (ffffffff814d700d)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - block/bio.c:bio_reset
  - block/bio.c:bio_init
  - block/bio.c:bio_init
```
```
In block/blk-core.c (ffffffff814dc4f5)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - block/blk-core.c:blk_rq_init
```
```
In block/blk-ioc.c (ffffffff814e2c66)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - block/blk-ioc.c:create_task_io_context
  - block/blk-ioc.c:create_task_io_context
```
```
In block/blk-mq.c (ffffffff814eae8e)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/bsg.c (ffffffff8150011e)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - block/bsg.c:bsg_open
```
```
In block/bsg-lib.c (ffffffff81500c2d)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_queue_rq
```
```
In block/blk-cgroup.c (ffffffff815016fd)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_css_alloc
```
```
In block/blk-iocost.c (ffffffff8150a5db)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - block/blk-iocost.c:blk_iocost_init
```
```
In block/blk-wbt.c (ffffffff81512aea)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_init
```
```
In lib/rhashtable.c (ffffffff815234ea)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_init
```
```
In lib/cpu_rmap.c (ffffffff8154e343)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - lib/cpu_rmap.c:alloc_cpu_rmap
```
```
In lib/sbitmap.c (ffffffff8155443f)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbq_wake_up
```
```
In drivers/pinctrl/core.c (ffffffff815591c3)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:create_pinctrl
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff8159d641)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
```
```
In drivers/rapidio/rio.c (ffffffff815a7b9d)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_register_mport
  - drivers/rapidio/rio.c:rio_mport_initialize
  - drivers/rapidio/rio.c:rio_del_device
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff815b113d)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:register_framebuffer
```
```
In drivers/acpi/ec.c (ffffffff815d5cd4)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_add_query_handler
```
```
In drivers/clk/clk.c (ffffffff81617caf)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_core_init
```
```
In drivers/dma/dmaengine.c (ffffffff8161ccf8)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaengine_get_unmap_data
  - drivers/dma/dmaengine.c:dma_async_device_register
```
```
In drivers/xen/balloon.c (ffffffff8162abb6)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_process
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff81635744)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_open
```
```
In drivers/reset/core.c (ffffffff8164746d)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In drivers/tty/tty_io.c (ffffffff8164b67b)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:alloc_tty_struct
```
```
In drivers/tty/tty_buffer.c (ffffffff81652bc9)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_init
  - drivers/tty/tty_buffer.c:tty_buffer_init
```
```
In drivers/tty/tty_port.c (ffffffff81652eb2)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_init
```
```
In drivers/tty/serial/serial_core.c (ffffffff8166bac5)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_add_one_port
```
```
In drivers/char/virtio_console.c (ffffffff81687f8a)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:add_port
```
```
In drivers/char/hw_random/core.c (ffffffff8168ac1c)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In drivers/char/agp/backend.c (ffffffff8168b1b4)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/char/agp/backend.c:agp_alloc_bridge
  - drivers/char/agp/backend.c:agp_alloc_bridge
```
```
In drivers/iommu/iova.c (ffffffff816a30d4)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/iommu/iova.c:fq_flush_timeout
  - drivers/iommu/iova.c:init_iova_flush_queue
```
```
In drivers/connector/cn_queue.c (ffffffff816b9d0a)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/connector/cn_queue.c:cn_queue_alloc_dev
  - drivers/connector/cn_queue.c:cn_queue_add_callback
```
```
In drivers/lightnvm/core.c (ffffffff816bb296)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_alloc_dev
```
```
In drivers/base/core.c (ffffffff816c139a)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/power/runtime.c (ffffffff816d3ab5)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_init
  - drivers/base/power/runtime.c:pm_runtime_init
```
```
In drivers/base/power/wakeup.c (ffffffff816d9e28)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:pm_wakeup_clear
```
```
In drivers/base/power/domain.c (ffffffff816db52a)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/base/power/domain.c:pm_genpd_init
```
```
In drivers/base/firmware_loader/main.c (ffffffff816e0152)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
```
```
In drivers/block/loop.c (ffffffff816f1e2d)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_add
  - drivers/block/loop.c:lo_rw_aio
```
```
In drivers/mfd/mfd-core.c (ffffffff817025d4)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_add_devices
```
```
In drivers/nvdimm/core.c (ffffffff81704bbf)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff81707b6c)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:__nvdimm_create
```
```
In drivers/nvdimm/dimm.c (ffffffff81708a87)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In drivers/dax/bus.c (ffffffff81718dc0)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In drivers/dma-buf/dma-fence.c (ffffffff8171aecb)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In drivers/dma-buf/dma-fence-array.c (ffffffff8171b7da)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_create
```
```
In drivers/dma-buf/sw_sync.c (ffffffff8171de3a)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open
```
```
In drivers/scsi/scsi.c (ffffffff81720d35)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_finish_command
  - drivers/scsi/scsi.c:scsi_finish_command
  - drivers/scsi/scsi.c:scsi_finish_command
```
```
In drivers/scsi/scsi_lib.c (ffffffff817297a2)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:__scsi_queue_insert
  - drivers/scsi/scsi_lib.c:__scsi_queue_insert
  - drivers/scsi/scsi_lib.c:__scsi_queue_insert
```
```
In drivers/scsi/scsi_scan.c (ffffffff8172ab8d)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
```
```
In drivers/scsi/sd.c (ffffffff817385e7)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
```
```
In drivers/scsi/sr.c (ffffffff8173a8bd)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_probe
```
```
In drivers/scsi/sg.c (ffffffff8173ca48)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_open
```
```
In drivers/nvme/host/core.c (ffffffff81746e60)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/nvme/host/core.c:nvme_alloc_ns
  - drivers/nvme/host/core.c:nvme_alloc_ns_head
  - drivers/nvme/host/core.c:nvme_init_identify
  - drivers/nvme/host/core.c:nvme_init_subsystem
```
```
In drivers/ata/libata-core.c (ffffffff81753474)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_init
  - drivers/ata/libata-core.c:ata_host_alloc
```
```
In drivers/net/phy/sfp-bus.c (ffffffff81784198)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_bus_get
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff8178c7fd)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
```
```
In drivers/usb/core/usb.c (ffffffff8179b914)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/usb/core/usb.c:usb_alloc_dev
```
```
In drivers/usb/core/hub.c (ffffffff817a442a)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_probe
```
```
In drivers/usb/core/hcd.c (ffffffff817a4dcf)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:__usb_create_hcd
```
```
In drivers/usb/core/urb.c (ffffffff817a872f)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_init_urb
```
```
In drivers/usb/core/config.c (ffffffff817aef38)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_configuration
```
```
In drivers/usb/core/file.c (ffffffff817b081f)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In drivers/media/cec/cec-notifier.c (ffffffff81824332)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In drivers/thermal/thermal_core.c (ffffffff8182d931)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
```
```
In drivers/md/md.c (ffffffff81846678)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_run
  - drivers/md/md.c:max_corrected_read_errors_store
  - drivers/md/md.c:md_rdev_init
  - drivers/md/md.c:md_rdev_init
  - drivers/md/md.c:md_rdev_init
  - drivers/md/md.c:errors_store
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:mddev_init
  - drivers/md/md.c:mddev_init
  - drivers/md/md.c:mddev_init
  - drivers/md/md.c:mddev_init
  - drivers/md/md.c:submit_flushes
```
```
In drivers/md/md-bitmap.c (ffffffff8184bbe7)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
```
```
In drivers/md/dm.c (ffffffff8184fc08)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:dm_get_table_device
  - drivers/md/dm.c:alloc_io
```
```
In drivers/md/dm-table.c (ffffffff81851eb4)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_get_device
```
```
In drivers/md/dm-stripe.c (ffffffff818555e2)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:stripe_ctr
```
```
In drivers/md/dm-io.c (ffffffff81858e73)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/md/dm-io.c:dm_io
  - drivers/md/dm-io.c:sync_io
```
```
In drivers/md/dm-kcopyd.c (ffffffff81859ece)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
  - drivers/md/dm-kcopyd.c:dm_kcopyd_copy
```
```
In drivers/md/dm-stats.c (ffffffff8185b358)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In drivers/opp/core.c (ffffffff81863a7b)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/opp/core.c:_opp_add
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff8186bf33)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_stop
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
  - drivers/cpufreq/cpufreq_governor.c:dbs_update_util_handler
  - drivers/cpufreq/cpufreq_governor.c:dbs_work_handler
```
```
In drivers/mmc/core/sdio_irq.c (ffffffff818868e1)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_irq.c:sdio_release_irq
  - drivers/mmc/core/sdio_irq.c:sdio_claim_irq
```
```
In drivers/firmware/efi/efi.c (ffffffff81a69c50)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff8189548c)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
```
```
In drivers/devfreq/devfreq.c (ffffffff8189ac14)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
```
In drivers/nvmem/core.c (ffffffff818a2af6)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In net/core/sock.c (ffffffff818b1f7f)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_alloc
```
```
In net/core/skbuff.c (ffffffff818b9f96)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_ext_add
  - net/core/skbuff.c:skb_ext_add
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:sock_zerocopy_realloc
  - net/core/skbuff.c:sock_zerocopy_alloc
  - net/core/skbuff.c:__skb_clone
  - net/core/skbuff.c:__build_skb_around
  - net/core/skbuff.c:__build_skb_around
  - net/core/skbuff.c:__alloc_skb
  - net/core/skbuff.c:__alloc_skb
  - net/core/skbuff.c:__alloc_skb
```
```
In net/core/net_namespace.c (ffffffff818c5f76)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/core/net_namespace.c:copy_net_ns
  - net/core/net_namespace.c:copy_net_ns
  - net/core/net_namespace.c:setup_net
  - net/core/net_namespace.c:setup_net
```
```
In net/core/dev.c (ffffffff818d0395)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/core/dev.c:__dev_kfree_skb_irq
```
```
In net/core/dst.c (ffffffff818e0e45)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/core/dst.c:__metadata_dst_init
  - net/core/dst.c:dst_cow_metrics_generic
```
```
In net/core/neighbour.c (ffffffff818e69e4)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:___neigh_create
```
```
In net/core/filter.c (ffffffff818feeef)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/core/filter.c:__sk_attach_prog
```
```
In net/core/page_pool.c (ffffffff81907175)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_create
  - net/core/page_pool.c:page_pool_create
```
```
In net/core/skmsg.c (ffffffff81908d55)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_init
```
```
In net/core/netpoll.c (ffffffff8190a35f)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/core/netpoll.c:__netpoll_setup
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:zap_completion_queue
```
```
In net/core/fib_rules.c (ffffffff8190d8ce)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_default_rule_add
```
```
In net/core/devlink.c (ffffffff819241f1)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_traps_register
  - net/core/devlink.c:devlink_health_reporter_create
```
```
In net/sched/sch_generic.c (ffffffff8192e0be)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_alloc
```
```
In net/sched/cls_api.c (ffffffff81939270)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tcf_block_get_ext
```
```
In net/sched/act_api.c (ffffffff8193a0c0)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_idr_create
  - net/sched/act_api.c:tcf_idr_create
```
```
In net/ipv4/route.c (ffffffff81947ea5)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_genid_init
  - net/ipv4/route.c:rt_genid_init
  - net/ipv4/route.c:rt_genid_init
```
```
In net/ipv4/inetpeer.c (ffffffff8194d61d)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81959e2c)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
```
```
In net/ipv4/inet_connection_sock.c (ffffffff8195a985)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_hash_add
```
```
In net/ipv4/tcp.c (ffffffff8195c958)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv4/tcp.c:skb_entail
```
```
In net/ipv4/tcp_input.c (ffffffff819648a3)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/tcp_output.c (ffffffff81971dc1)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819785b1)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81980308)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/devinet.c (ffffffff81992a08)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_init
```
```
In net/ipv4/igmp.c (ffffffff8199981b)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv4/igmp.c:____ip_mc_inc_group
```
```
In net/ipv4/fib_semantics.c (ffffffff819a0085)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/ipv4/inet_fragment.c (ffffffff819a6333)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frags_init
```
```
In net/ipv4/metrics.c (ffffffff819a9d2c)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In net/ipv4/nexthop.c (ffffffff819ac22b)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff819aca6f)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:proc_tfo_blackhole_detect_timeout
```
```
In net/ipv4/ipmr.c (ffffffff819b2bb2)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv4/syncookies.c (ffffffff819b57cf)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:tcp_get_cookie_sock
```
```
In net/ipv4/cipso_ipv4.c (ffffffff819b8fb6)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff819bd0c2)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
```
```
In net/xfrm/xfrm_state.c (ffffffff819c45df)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
```
```
In net/unix/af_unix.c (ffffffff819d0f3d)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
```
```
In net/ipv6/af_inet6.c (ffffffff819d50a7)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In net/ipv6/anycast.c (ffffffff819d5d2b)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
```
```
In net/ipv6/addrconf.c (ffffffff819e0862)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/route.c (ffffffff819e8638)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_upper_bound_set
```
```
In net/ipv6/ip6_fib.c (ffffffff819f5794)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_metric_set
  - net/ipv6/ip6_fib.c:fib6_info_alloc
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff819f94d0)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In net/ipv6/mcast.c (ffffffff81a09bca)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
```
```
In net/ipv6/exthdrs.c (ffffffff81a13058)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_dup_options
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81a159a0)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:fl_create
```
```
In net/ipv6/ip6mr.c (ffffffff81a1aeb9)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/ipv6/calipso.c (ffffffff81a21f5e)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_doi_add
```
```
In net/packet/af_packet.c (ffffffff81a2f62c)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
```
```
In net/xdp/xdp_umem.c (ffffffff81a4be65)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_create
```
```
In lib/dump_stack.c (ffffffff81a4d428)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - lib/dump_stack.c:dump_stack
```
```
In lib/klist.c (ffffffff81a4f012)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - lib/klist.c:klist_node_init
```
```
In lib/kobject.c (ffffffff81a50566)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - lib/kobject.c:kset_register
  - lib/kobject.c:kobject_init
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
In arch/x86/kernel/tboot.c (ffffffff82894b60)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8103bbfc)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:fake_panic_set
  - arch/x86/kernel/cpu/mce/core.c:fake_panic_set
  - arch/x86/kernel/cpu/mce/core.c:fake_panic_set
  - arch/x86/kernel/cpu/mce/core.c:fake_panic_set
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81041e99)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff81042a00)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff810466cd)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In arch/x86/kernel/reboot.c (ffffffff81052d21)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff810556c6)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_target
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
```
```
In arch/x86/kernel/kgdb.c (ffffffff81063fcf)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In arch/x86/mm/init_64.c (ffffffff81a26894)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pagetable
```
```
In kernel/fork.c (ffffffff81086d66)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:mm_init
  - kernel/fork.c:mm_init
  - kernel/fork.c:mm_init
```
```
In kernel/softirq.c (ffffffff8108f635)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/softirq.c:tasklet_init
```
```
In kernel/user.c (ffffffff81098148)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/user.c:alloc_uid
```
```
In kernel/workqueue.c (ffffffff810ad47a)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_offline_cpu
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:flush_workqueue_prep_pwqs
```
```
In kernel/pid.c (ffffffff810aec9d)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/pid.c:alloc_pid
```
```
In kernel/nsproxy.c (ffffffff810b5101)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/nsproxy.c:create_new_namespaces
```
```
In kernel/cred.c (ffffffff810b69b3)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:cred_alloc_blank
```
```
In kernel/smpboot.c (ffffffff810b85bc)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/smpboot.c:cpu_wait_death
  - kernel/smpboot.c:cpu_check_up_prepare
```
```
In kernel/groups.c (ffffffff810b9028)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/groups.c:groups_alloc
```
```
In kernel/sched/core.c (ffffffff828ae5a2)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init
```
```
In kernel/sched/fair.c (ffffffff810d234a)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_fault
```
```
In kernel/sched/cpupri.c (ffffffff810df6f7)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_init
```
```
In kernel/sched/topology.c (ffffffff810e0f1f)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:init_defrootdomain
```
```
In kernel/sched/autogroup.c (ffffffff810e3bcf)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
  - kernel/sched/autogroup.c:autogroup_init
```
```
In kernel/sched/membarrier.c (ffffffff810eadff)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/sched/membarrier.c:membarrier_exec_mmap
```
```
In kernel/sched/psi.c (ffffffff810eb477)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_trigger_destroy
  - kernel/sched/psi.c:psi_poll_work
  - kernel/sched/psi.c:group_init
```
```
In kernel/locking/mutex.c (ffffffff810ec9b4)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/locking/mutex.c:__mutex_init
```
```
In kernel/locking/rwsem.c (ffffffff810ece0c)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:__init_rwsem
```
```
In kernel/power/swap.c (ffffffff810f79ce)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:save_image
```
```
In kernel/irq/manage.c (ffffffff81100f49)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_notifier
```
```
In kernel/rcu/srcutree.c (ffffffff8110e992)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
```
```
In kernel/rcu/tree.c (ffffffff811109e0)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In kernel/futex.c (ffffffff828b2782)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/futex.c:futex_init
```
```
In kernel/module.c (ffffffff8114129c)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/module.c:load_module
```
```
In kernel/kexec_core.c (ffffffff81145d72)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_free_reserved_phys_range
  - kernel/kexec_core.c:crash_kexec
```
```
In kernel/cgroup/cgroup.c (ffffffff8114b870)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:init_cgroup_root
  - kernel/cgroup/cgroup.c:find_css_set
```
```
In kernel/cgroup/namespace.c (ffffffff8115333b)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
```
```
In kernel/utsname.c (ffffffff8115ced8)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/utsname.c:copy_utsname
```
```
In kernel/user_namespace.c (ffffffff8115e1e5)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In kernel/pid_namespace.c (ffffffff8115ed48)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In kernel/stop_machine.c (ffffffff8115fbfa)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:stop_two_cpus
  - kernel/stop_machine.c:multi_cpu_stop
  - kernel/stop_machine.c:cpu_stop_init_done
```
```
In kernel/audit_watch.c (ffffffff811699d8)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_init_watch
```
```
In kernel/audit_tree.c (ffffffff8116be87)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_make_tree
```
```
In kernel/debug/debug_core.c (ffffffff8116f95e)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_tasklet_bpt
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff81174dbf)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In kernel/hung_task.c (ffffffff8117ad15)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/hung_task.c:reset_hung_task_detector
```
```
In kernel/seccomp.c (ffffffff8117d652)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
```
```
In kernel/relay.c (ffffffff8117e4dd)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/relay.c:__relay_reset
```
```
In kernel/trace/trace.c (ffffffff81191471)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
```
```
In kernel/trace/tracing_map.c (ffffffff8119c6be)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_create
  - kernel/trace/tracing_map.c:tracing_map_clear
```
```
In kernel/trace/blktrace.c (ffffffff811a2657)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:do_blk_trace_setup
```
```
In kernel/trace/fgraph.c (ffffffff811a535a)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/trace/fgraph.c:start_graph_tracing
  - kernel/trace/fgraph.c:start_graph_tracing
  - kernel/trace/fgraph.c:ftrace_graph_init_task
  - kernel/trace/fgraph.c:ftrace_graph_init_task
```
```
In kernel/trace/trace_events.c (ffffffff811a578c)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_create_new_event
  - kernel/trace/trace_events.c:trace_create_new_event
```
```
In kernel/bpf/syscall.c (ffffffff811ccccc)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:map_create
```
```
In kernel/bpf/btf.c (ffffffff811e9d3c)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_new_fd
```
```
In kernel/events/core.c (ffffffff811f7fcc)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:alloc_perf_context
```
```
In kernel/events/ring_buffer.c (ffffffff81203a8d)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc
  - kernel/events/ring_buffer.c:rb_alloc_aux
  - kernel/events/ring_buffer.c:perf_aux_output_skip
  - kernel/events/ring_buffer.c:perf_aux_output_end
  - kernel/events/ring_buffer.c:perf_aux_output_begin
  - kernel/events/ring_buffer.c:perf_output_put_handle
```
```
In kernel/events/uprobes.c (ffffffff812070c1)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__create_xol_area
```
```
In kernel/padata.c (ffffffff81208c54)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_alloc_pd
```
```
In kernel/jump_label.c (ffffffff8120a27c)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In mm/filemap.c (ffffffff81213097)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/shmem.c (ffffffff8122bae2)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_inode
```
```
In mm/backing-dev.c (ffffffff81235135)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_alloc_node
  - mm/backing-dev.c:wb_congested_get_create
  - mm/backing-dev.c:default_bdi_init
```
```
In mm/rmap.c (ffffffff8125fd80)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - mm/rmap.c:hugepage_add_new_anon_rmap
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:anon_vma_ctor
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:__anon_vma_prepare
```
```
In mm/page_alloc.c (ffffffff8126bc8f)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:memmap_init_zone_device
  - mm/page_alloc.c:memmap_init_zone_device
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:make_alloc_exact
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:prep_new_page
  - mm/page_alloc.c:prep_new_page
  - mm/page_alloc.c:prep_new_page
  - mm/page_alloc.c:check_new_page_bad
  - mm/page_alloc.c:init_cma_reserved_pageblock
  - mm/page_alloc.c:init_cma_reserved_pageblock
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:bad_page
```
```
In mm/swap_state.c (ffffffff812719f7)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - mm/swap_state.c:init_swap_address_space
  - mm/swap_state.c:swap_cluster_readahead
```
```
In mm/frontswap.c (ffffffff8127834f)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_invalidate_area
```
```
In mm/zswap.c (ffffffff81278a76)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - mm/zswap.c:zswap_pool_create
```
```
In mm/hugetlb.c (ffffffff8127af9e)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:update_and_free_page
  - mm/hugetlb.c:update_and_free_page
  - mm/hugetlb.c:update_and_free_page
  - mm/hugetlb.c:dequeue_huge_page_nodemask
  - mm/hugetlb.c:resv_map_alloc
```
```
In mm/mempolicy.c (ffffffff81286db8)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:__mpol_dup
```
```
In mm/memory_hotplug.c (ffffffff81295e0e)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__online_page_free
  - mm/memory_hotplug.c:put_page_bootmem
```
```
In mm/huge_memory.c (ffffffff8129edf8)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In mm/memcontrol.c (ffffffff812ab5d1)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_select_victim_node
```
```
In mm/zpool.c (ffffffff812b74d9)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - mm/zpool.c:zpool_register_driver
```
```
In mm/zsmalloc.c (ffffffff812b84df)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - mm/zsmalloc.c:reset_page
```
```
In fs/super.c (ffffffff812c8e33)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/super.c:alloc_super
```
```
In fs/exec.c (ffffffff812cecb5)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In fs/dcache.c (ffffffff812e3e9e)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/dcache.c:__d_alloc
```
```
In fs/inode.c (ffffffff812e4c9a)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/inode.c:inode_init_always
  - fs/inode.c:inode_init_always
  - fs/inode.c:inode_init_always
  - fs/inode.c:inode_init_always
```
```
In fs/file.c (ffffffff812e9230)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/file.c:dup_fd
```
```
In fs/namespace.c (ffffffff812ea6b1)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In fs/fsopen.c (ffffffff81308148)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/fsopen.c:__ia32_sys_fspick
  - fs/fsopen.c:__x64_sys_fspick
  - fs/fsopen.c:__ia32_sys_fsopen
  - fs/fsopen.c:__x64_sys_fsopen
```
```
In fs/block_dev.c (ffffffff8130e7f9)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_direct_IO
```
```
In fs/notify/group.c (ffffffff813161e1)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_alloc_group
  - fs/notify/group.c:fsnotify_alloc_group
  - fs/notify/group.c:fsnotify_alloc_group
```
```
In fs/notify/mark.c (ffffffff813165a2)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_init_mark
```
```
In fs/eventfd.c (ffffffff81320d75)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/eventfd.c:do_eventfd
```
```
In fs/userfaultfd.c (ffffffff81321470)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/userfaultfd.c:__ia32_sys_userfaultfd
  - fs/userfaultfd.c:__x64_sys_userfaultfd
  - fs/userfaultfd.c:dup_userfaultfd
```
```
In fs/aio.c (ffffffff8132736d)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:__ia32_sys_io_destroy
  - fs/aio.c:__x64_sys_io_destroy
  - fs/aio.c:exit_aio
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
```
```
In fs/io_uring.c (ffffffff8132de51)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_get_req
```
```
In fs/crypto/keyring.c (ffffffff81335ac5)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/crypto/keyring.c:add_master_key
```
```
In fs/crypto/keysetup_v1.c (ffffffff8133795f)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
```
```
In fs/mbcache.c (ffffffff81348a6b)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/posix_acl.c (ffffffff81349357)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/posix_acl.c:posix_acl_clone
  - fs/posix_acl.c:posix_acl_alloc
```
```
In fs/coredump.c (ffffffff8134b1c5)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/iomap/buffered-io.c (ffffffff8134cd43)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In fs/iomap/direct-io.c (ffffffff8134e6da)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_rw
```
```
In fs/quota/dquot.c (ffffffff813520c8)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/quota/dquot.c:dqget
```
```
In fs/proc/generic.c (ffffffff813608e5)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/proc/generic.c:__proc_create
```
```
In fs/kernfs/dir.c (ffffffff8136d243)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/kernfs/dir.c:__kernfs_new_node
```
```
In fs/kernfs/file.c (ffffffff8136ed2d)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_fop_open
  - fs/kernfs/file.c:kernfs_fop_open
```
```
In fs/configfs/dir.c (ffffffff81372b41)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_new_dirent
  - fs/configfs/dir.c:new_fragment
```
```
In fs/configfs/item.c (ffffffff81375538)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/configfs/item.c:config_group_init_type_name
  - fs/configfs/item.c:config_item_init_type_name
```
```
In fs/ext4/mballoc.c (ffffffff813a9510)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
```
```
In fs/ext4/page-io.c (ffffffff813b489f)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_init_io_end
```
```
In fs/ext4/super.c (ffffffff813c2db0)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_alloc_inode
```
```
In fs/jbd2/transaction.c (ffffffff813d8c6a)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
```
```
In fs/jbd2/journal.c (ffffffff813e19e9)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_init_common
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/ecryptfs/main.c (ffffffff813fcf36)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_get_lower_file
```
```
In fs/ecryptfs/super.c (ffffffff813fd15f)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/ecryptfs/super.c:ecryptfs_alloc_inode
```
```
In fs/ecryptfs/miscdev.c (ffffffff828d00f8)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/ecryptfs/miscdev.c:ecryptfs_init_ecryptfs_miscdev
```
```
In fs/fuse/dev.c (ffffffff814083c6)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_request_alloc
```
```
In fs/fuse/file.c (ffffffff814132e8)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_file_alloc
```
```
In fs/fuse/inode.c (ffffffff8141597b)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_conn_init
  - fs/fuse/inode.c:fuse_conn_init
  - fs/fuse/inode.c:fuse_conn_init
```
```
In fs/debugfs/file.c (ffffffff8141b0d5)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_atomic_t_set
  - fs/debugfs/file.c:debugfs_file_get
```
```
In ipc/util.c (ffffffff8141fc25)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In ipc/msg.c (ffffffff828d0614)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - ipc/msg.c:msg_init
  - ipc/msg.c:msg_init
```
```
In ipc/sem.c (ffffffff81426982)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - ipc/sem.c:copy_semundo
  - ipc/sem.c:find_alloc_undo
```
```
In ipc/namespace.c (ffffffff8142d332)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - ipc/namespace.c:copy_ipcs
```
```
In security/keys/key.c (ffffffff8142ea5a)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_user_lookup
  - security/keys/key.c:key_user_lookup
  - security/keys/key.c:key_user_lookup
```
```
In security/selinux/avc.c (ffffffff81443d9b)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - security/selinux/avc.c:selinux_avc_init
  - security/selinux/avc.c:selinux_avc_init
```
```
In security/selinux/ss/services.c (ffffffff81461559)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
```
```
In security/tomoyo/condition.c (ffffffff8147402a)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
```
```
In security/tomoyo/gc.c (ffffffff81478677)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In security/tomoyo/memory.c (ffffffff814790e6)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_name
  - security/tomoyo/memory.c:tomoyo_get_group
```
```
In security/apparmor/apparmorfs.c (ffffffff814802e1)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_write_access
```
```
In security/apparmor/lib.c (ffffffff81482a1a)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - security/apparmor/lib.c:aa_str_alloc
```
```
In security/apparmor/match.c (ffffffff81483407)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
```
```
In security/apparmor/policy_unpack.c (ffffffff8148ccfd)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:aa_loaddata_alloc
```
```
In security/apparmor/policy_ns.c (ffffffff81492d96)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:alloc_ns
```
```
In security/apparmor/label.c (ffffffff81494022)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_alloc
  - security/apparmor/label.c:aa_alloc_proxy
```
```
In crypto/api.c (ffffffff814a76c8)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - crypto/api.c:crypto_alg_mod_lookup
```
```
In crypto/algapi.c (ffffffff814a863d)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - crypto/algapi.c:__crypto_register_alg
  - crypto/algapi.c:crypto_check_alg
```
```
In block/bio.c (ffffffff814c79cd)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - block/bio.c:bio_reset
  - block/bio.c:bio_init
  - block/bio.c:bio_init
```
```
In block/blk-core.c (ffffffff814ccea5)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - block/blk-core.c:blk_rq_init
```
```
In block/blk-ioc.c (ffffffff814d35f6)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - block/blk-ioc.c:create_task_io_context
  - block/blk-ioc.c:create_task_io_context
```
```
In block/blk-mq.c (ffffffff814db3de)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/bsg.c (ffffffff814f062e)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - block/bsg.c:bsg_open
```
```
In block/bsg-lib.c (ffffffff814f113d)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_queue_rq
```
```
In block/blk-cgroup.c (ffffffff814f1c0d)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_css_alloc
```
```
In block/blk-iocost.c (ffffffff814faa6b)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - block/blk-iocost.c:blk_iocost_init
```
```
In block/blk-wbt.c (ffffffff81502e0a)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_init
```
```
In lib/rhashtable.c (ffffffff815137ca)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_init
```
```
In lib/cpu_rmap.c (ffffffff8153e623)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - lib/cpu_rmap.c:alloc_cpu_rmap
```
```
In lib/sbitmap.c (ffffffff815446bf)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbq_wake_up
```
```
In drivers/pinctrl/core.c (ffffffff81549683)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:create_pinctrl
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff8158c7d1)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
```
```
In drivers/rapidio/rio.c (ffffffff81596d3d)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_register_mport
  - drivers/rapidio/rio.c:rio_mport_initialize
  - drivers/rapidio/rio.c:rio_del_device
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff815a02cd)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:register_framebuffer
```
```
In drivers/acpi/ec.c (ffffffff815bf894)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_add_query_handler
```
```
In drivers/clk/clk.c (ffffffff8160c1df)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_core_init
```
```
In drivers/dma/dmaengine.c (ffffffff816113e8)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaengine_get_unmap_data
  - drivers/dma/dmaengine.c:dma_async_device_register
```
```
In drivers/reset/core.c (ffffffff816278cd)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In drivers/tty/tty_io.c (ffffffff8162bacb)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:alloc_tty_struct
```
```
In drivers/tty/tty_buffer.c (ffffffff81633009)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_init
  - drivers/tty/tty_buffer.c:tty_buffer_init
```
```
In drivers/tty/tty_port.c (ffffffff816332f2)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_init
```
```
In drivers/tty/serial/serial_core.c (ffffffff8164ac25)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_add_one_port
```
```
In drivers/char/virtio_console.c (ffffffff81665aaa)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:add_port
```
```
In drivers/char/hw_random/core.c (ffffffff8166861c)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In drivers/char/agp/backend.c (ffffffff81668bb4)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/char/agp/backend.c:agp_alloc_bridge
  - drivers/char/agp/backend.c:agp_alloc_bridge
```
```
In drivers/iommu/iova.c (ffffffff81680ac4)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/iommu/iova.c:fq_flush_timeout
  - drivers/iommu/iova.c:init_iova_flush_queue
```
```
In drivers/connector/cn_queue.c (ffffffff8169794a)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/connector/cn_queue.c:cn_queue_alloc_dev
  - drivers/connector/cn_queue.c:cn_queue_add_callback
```
```
In drivers/base/core.c (ffffffff8169c64a)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/power/runtime.c (ffffffff816aed65)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_init
  - drivers/base/power/runtime.c:pm_runtime_init
```
```
In drivers/base/power/wakeup.c (ffffffff816b44a8)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:pm_wakeup_clear
```
```
In drivers/base/power/domain.c (ffffffff816b5baa)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/base/power/domain.c:pm_genpd_init
```
```
In drivers/base/firmware_loader/main.c (ffffffff816ba792)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
```
```
In drivers/block/loop.c (ffffffff816cbf2d)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_add
  - drivers/block/loop.c:lo_rw_aio
```
```
In drivers/mfd/mfd-core.c (ffffffff816d63e4)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_add_devices
```
```
In drivers/nvdimm/core.c (ffffffff816d863f)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff816db5ec)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:__nvdimm_create
```
```
In drivers/nvdimm/dimm.c (ffffffff816dc507)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In drivers/dax/bus.c (ffffffff816f12f0)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In drivers/dma-buf/dma-fence.c (ffffffff816f432b)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In drivers/dma-buf/dma-fence-array.c (ffffffff816f4c3a)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_create
```
```
In drivers/dma-buf/sw_sync.c (ffffffff816f729a)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open
```
```
In drivers/scsi/scsi.c (ffffffff816fa165)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_finish_command
  - drivers/scsi/scsi.c:scsi_finish_command
  - drivers/scsi/scsi.c:scsi_finish_command
```
```
In drivers/scsi/scsi_lib.c (ffffffff81702bb4)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:__scsi_queue_insert
  - drivers/scsi/scsi_lib.c:__scsi_queue_insert
  - drivers/scsi/scsi_lib.c:__scsi_queue_insert
```
```
In drivers/scsi/scsi_scan.c (ffffffff81703fad)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
```
```
In drivers/scsi/scsi_transport_fc.c (ffffffff828e904f)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/scsi/scsi_transport_fc.c:fc_transport_init
```
```
In drivers/scsi/sd.c (ffffffff8171a287)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
```
```
In drivers/scsi/sr.c (ffffffff8171c55d)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_probe
```
```
In drivers/scsi/sg.c (ffffffff8171e6e8)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_open
```
```
In drivers/nvme/host/core.c (ffffffff81728ae4)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/nvme/host/core.c:nvme_alloc_ns
  - drivers/nvme/host/core.c:nvme_alloc_ns_head
  - drivers/nvme/host/core.c:nvme_init_identify
  - drivers/nvme/host/core.c:nvme_init_subsystem
```
```
In drivers/ata/libata-core.c (ffffffff81733314)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_init
  - drivers/ata/libata-core.c:ata_host_alloc
```
```
In drivers/net/phy/sfp-bus.c (ffffffff81763ae8)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_bus_get
```
```
In drivers/net/vxlan.c (ffffffff81770e56)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/net/vxlan.c:__vxlan_sock_add
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817755cd)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
```
```
In drivers/vfio/vfio.c (ffffffff8177a720)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_fops_open
  - drivers/vfio/vfio.c:vfio_add_group_dev
  - drivers/vfio/vfio.c:vfio_add_group_dev
  - drivers/vfio/vfio.c:vfio_add_group_dev
  - drivers/vfio/vfio.c:vfio_add_group_dev
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff8177e737)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff8178180c)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_probe
```
```
In drivers/usb/core/usb.c (ffffffff8178d5a4)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/usb/core/usb.c:usb_alloc_dev
```
```
In drivers/usb/core/hub.c (ffffffff81795f9b)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_probe
```
```
In drivers/usb/core/hcd.c (ffffffff817968df)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:__usb_create_hcd
```
```
In drivers/usb/core/urb.c (ffffffff8179a13f)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_init_urb
```
```
In drivers/usb/core/config.c (ffffffff817a0938)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_configuration
```
```
In drivers/usb/core/file.c (ffffffff817a21e0)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/usb/core/file.c:usb_register_dev
```
```
In drivers/media/cec/cec-notifier.c (ffffffff817eb9d2)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In drivers/thermal/thermal_core.c (ffffffff817f4fc1)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
```
```
In drivers/md/md.c (ffffffff8180dcd8)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_run
  - drivers/md/md.c:max_corrected_read_errors_store
  - drivers/md/md.c:md_rdev_init
  - drivers/md/md.c:md_rdev_init
  - drivers/md/md.c:md_rdev_init
  - drivers/md/md.c:errors_store
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:mddev_init
  - drivers/md/md.c:mddev_init
  - drivers/md/md.c:mddev_init
  - drivers/md/md.c:mddev_init
  - drivers/md/md.c:submit_flushes
```
```
In drivers/md/md-bitmap.c (ffffffff81813207)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
```
```
In drivers/md/dm.c (ffffffff81817218)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:dm_get_table_device
  - drivers/md/dm.c:alloc_io
```
```
In drivers/md/dm-table.c (ffffffff818194c4)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_get_device
```
```
In drivers/md/dm-stripe.c (ffffffff8181cbf2)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:stripe_ctr
```
```
In drivers/md/dm-io.c (ffffffff81820483)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/md/dm-io.c:dm_io
  - drivers/md/dm-io.c:sync_io
```
```
In drivers/md/dm-kcopyd.c (ffffffff818214de)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
  - drivers/md/dm-kcopyd.c:dm_kcopyd_copy
```
```
In drivers/md/dm-stats.c (ffffffff81822922)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In drivers/opp/core.c (ffffffff8182c72b)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/opp/core.c:_opp_add
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff81834be3)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_stop
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
  - drivers/cpufreq/cpufreq_governor.c:dbs_update_util_handler
  - drivers/cpufreq/cpufreq_governor.c:dbs_work_handler
```
```
In drivers/firmware/efi/efi.c (ffffffff81a26120)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
```
```
In drivers/devfreq/devfreq.c (ffffffff818580e4)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
```
In drivers/nvmem/core.c (ffffffff8185e266)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In net/core/sock.c (ffffffff8186becf)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_alloc
```
```
In net/core/skbuff.c (ffffffff81873ee6)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_ext_add
  - net/core/skbuff.c:skb_ext_add
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:sock_zerocopy_realloc
  - net/core/skbuff.c:sock_zerocopy_alloc
  - net/core/skbuff.c:__skb_clone
  - net/core/skbuff.c:__build_skb_around
  - net/core/skbuff.c:__build_skb_around
  - net/core/skbuff.c:__alloc_skb
  - net/core/skbuff.c:__alloc_skb
  - net/core/skbuff.c:__alloc_skb
```
```
In net/core/net_namespace.c (ffffffff8187feb6)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/core/net_namespace.c:copy_net_ns
  - net/core/net_namespace.c:copy_net_ns
  - net/core/net_namespace.c:setup_net
  - net/core/net_namespace.c:setup_net
```
```
In net/core/dev.c (ffffffff81886235)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/core/dev.c:__dev_kfree_skb_irq
```
```
In net/core/dst.c (ffffffff8189ac85)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/core/dst.c:__metadata_dst_init
  - net/core/dst.c:dst_cow_metrics_generic
```
```
In net/core/neighbour.c (ffffffff818a0824)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:___neigh_create
```
```
In net/core/filter.c (ffffffff818b8d1f)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/core/filter.c:__sk_attach_prog
```
```
In net/core/page_pool.c (ffffffff818c0f85)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_create
  - net/core/page_pool.c:page_pool_create
```
```
In net/core/skmsg.c (ffffffff818c2b65)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_init
```
```
In net/core/netpoll.c (ffffffff818c420f)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/core/netpoll.c:__netpoll_setup
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:zap_completion_queue
```
```
In net/core/fib_rules.c (ffffffff818c768e)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_default_rule_add
```
```
In net/core/devlink.c (ffffffff818ddfa1)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_traps_register
  - net/core/devlink.c:devlink_health_reporter_create
```
```
In net/sched/sch_generic.c (ffffffff818e7bbe)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_alloc
```
```
In net/sched/cls_api.c (ffffffff818f2d70)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tcf_block_get_ext
```
```
In net/sched/act_api.c (ffffffff818f3bc0)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_idr_create
  - net/sched/act_api.c:tcf_idr_create
```
```
In net/ipv4/route.c (ffffffff81901995)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_genid_init
  - net/ipv4/route.c:rt_genid_init
  - net/ipv4/route.c:rt_genid_init
```
```
In net/ipv4/inetpeer.c (ffffffff8190710d)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff8191391c)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81914475)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_hash_add
```
```
In net/ipv4/tcp.c (ffffffff81916448)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv4/tcp.c:skb_entail
```
```
In net/ipv4/tcp_input.c (ffffffff8191e393)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/tcp_output.c (ffffffff8192b891)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81932071)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81939dc8)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/devinet.c (ffffffff8194c4c8)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_init
```
```
In net/ipv4/igmp.c (ffffffff819532db)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv4/igmp.c:____ip_mc_inc_group
```
```
In net/ipv4/fib_semantics.c (ffffffff81959b45)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/ipv4/inet_fragment.c (ffffffff8195fdf3)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frags_init
```
```
In net/ipv4/metrics.c (ffffffff819637ec)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In net/ipv4/nexthop.c (ffffffff81965ceb)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff8196909f)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:proc_tfo_blackhole_detect_timeout
```
```
In net/ipv4/ipmr.c (ffffffff8196f1e2)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv4/syncookies.c (ffffffff819725bf)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:tcp_get_cookie_sock
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81975da6)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff81979eb2)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
```
```
In net/xfrm/xfrm_state.c (ffffffff819813cf)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
```
```
In net/unix/af_unix.c (ffffffff8198dcfd)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
```
```
In net/ipv6/af_inet6.c (ffffffff81991e67)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In net/ipv6/anycast.c (ffffffff81992aeb)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
```
```
In net/ipv6/addrconf.c (ffffffff8199d622)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/route.c (ffffffff819a53f8)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_upper_bound_set
```
```
In net/ipv6/ip6_fib.c (ffffffff819b2554)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_metric_set
  - net/ipv6/ip6_fib.c:fib6_info_alloc
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff819b6290)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In net/ipv6/mcast.c (ffffffff819c698a)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
```
```
In net/ipv6/exthdrs.c (ffffffff819cfe18)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_dup_options
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff819d2760)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:fl_create
```
```
In net/ipv6/ip6mr.c (ffffffff819d7c79)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/ipv6/calipso.c (ffffffff819ded1e)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_doi_add
```
```
In net/packet/af_packet.c (ffffffff819ec81c)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
```
```
In net/xdp/xdp_umem.c (ffffffff81a08a55)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_create
```
```
In lib/dump_stack.c (ffffffff81a0a542)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - lib/dump_stack.c:dump_stack
```
```
In lib/klist.c (ffffffff81a0c112)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - lib/klist.c:klist_node_init
```
```
In lib/kobject.c (ffffffff81a0d666)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - lib/kobject.c:kset_register
  - lib/kobject.c:kobject_init
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
In arch/x86/kernel/tboot.c (ffffffff828af98c)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104c68c)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:fake_panic_set
  - arch/x86/kernel/cpu/mce/core.c:fake_panic_set
  - arch/x86/kernel/cpu/mce/core.c:fake_panic_set
  - arch/x86/kernel/cpu/mce/core.c:fake_panic_set
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81052359)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff81052e87)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff810568ed)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In arch/x86/kernel/reboot.c (ffffffff81062df7)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff81065826)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_target
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
```
```
In arch/x86/kernel/kgdb.c (ffffffff81073f2f)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In arch/x86/mm/init_64.c (ffffffff81ad67e2)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pagetable
```
```
In kernel/fork.c (ffffffff810982d0)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:mm_init
  - kernel/fork.c:mm_init
  - kernel/fork.c:mm_init
```
```
In kernel/softirq.c (ffffffff810a0bc5)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/softirq.c:tasklet_init
```
```
In kernel/user.c (ffffffff810a8cee)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/user.c:alloc_uid
```
```
In kernel/workqueue.c (ffffffff810be1b0)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_offline_cpu
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:flush_workqueue_prep_pwqs
```
```
In kernel/pid.c (ffffffff810bf9e9)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/pid.c:alloc_pid
```
```
In kernel/nsproxy.c (ffffffff810c5e31)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/nsproxy.c:create_new_namespaces
```
```
In kernel/cred.c (ffffffff810c76e3)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:cred_alloc_blank
```
```
In kernel/smpboot.c (ffffffff810c92cc)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/smpboot.c:cpu_wait_death
  - kernel/smpboot.c:cpu_check_up_prepare
```
```
In kernel/groups.c (ffffffff810c9d48)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/groups.c:groups_alloc
```
```
In kernel/sched/core.c (ffffffff828c9316)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init
```
```
In kernel/sched/fair.c (ffffffff810df5ba)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_fault
```
```
In kernel/sched/cpupri.c (ffffffff810ec7b7)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_init
```
```
In kernel/sched/topology.c (ffffffff810edfdf)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:init_defrootdomain
```
```
In kernel/sched/autogroup.c (ffffffff810f0bef)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
  - kernel/sched/autogroup.c:autogroup_init
```
```
In kernel/sched/membarrier.c (ffffffff810f7d9f)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/sched/membarrier.c:membarrier_exec_mmap
```
```
In kernel/sched/psi.c (ffffffff810f8417)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_trigger_destroy
  - kernel/sched/psi.c:psi_poll_work
  - kernel/sched/psi.c:group_init
```
```
In kernel/locking/mutex.c (ffffffff810f9964)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/locking/mutex.c:__mutex_init
```
```
In kernel/locking/rwsem.c (ffffffff810f9dbc)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:__init_rwsem
```
```
In kernel/power/swap.c (ffffffff811049de)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:save_image
```
```
In kernel/irq/manage.c (ffffffff8110e109)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_notifier
```
```
In kernel/rcu/srcutree.c (ffffffff8111b7e2)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
```
```
In kernel/rcu/tree.c (ffffffff8111cec0)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In kernel/futex.c (ffffffff828cce72)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/futex.c:futex_init
```
```
In kernel/module.c (ffffffff8114be9c)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/module.c:load_module
```
```
In kernel/kexec_core.c (ffffffff81150942)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_free_reserved_phys_range
  - kernel/kexec_core.c:crash_kexec
```
```
In kernel/cgroup/cgroup.c (ffffffff811561f0)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:init_cgroup_root
  - kernel/cgroup/cgroup.c:find_css_set
```
```
In kernel/cgroup/namespace.c (ffffffff8115dea1)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
```
```
In kernel/utsname.c (ffffffff81167aa8)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/utsname.c:copy_utsname
```
```
In kernel/user_namespace.c (ffffffff81168db5)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In kernel/pid_namespace.c (ffffffff81169918)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In kernel/stop_machine.c (ffffffff8116a82a)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:stop_two_cpus
  - kernel/stop_machine.c:multi_cpu_stop
  - kernel/stop_machine.c:cpu_stop_init_done
```
```
In kernel/audit_watch.c (ffffffff81174608)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_init_watch
```
```
In kernel/audit_tree.c (ffffffff81176ab7)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_make_tree
```
```
In kernel/debug/debug_core.c (ffffffff8117a58e)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_tasklet_bpt
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff8117fa4f)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In kernel/hung_task.c (ffffffff811859a5)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/hung_task.c:reset_hung_task_detector
```
```
In kernel/seccomp.c (ffffffff811882f2)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
```
```
In kernel/relay.c (ffffffff811891ad)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/relay.c:__relay_reset
```
```
In kernel/trace/trace.c (ffffffff8119c1e1)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
```
```
In kernel/trace/tracing_map.c (ffffffff811a750e)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_create
  - kernel/trace/tracing_map.c:tracing_map_clear
```
```
In kernel/trace/blktrace.c (ffffffff811ad5d7)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:do_blk_trace_setup
```
```
In kernel/trace/fgraph.c (ffffffff811b031a)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/trace/fgraph.c:start_graph_tracing
  - kernel/trace/fgraph.c:start_graph_tracing
  - kernel/trace/fgraph.c:ftrace_graph_init_task
  - kernel/trace/fgraph.c:ftrace_graph_init_task
```
```
In kernel/trace/trace_events.c (ffffffff811b074c)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_create_new_event
  - kernel/trace/trace_events.c:trace_create_new_event
```
```
In kernel/bpf/syscall.c (ffffffff811d7cdc)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:map_create
```
```
In kernel/bpf/btf.c (ffffffff811f4dbc)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_new_fd
```
```
In kernel/events/core.c (ffffffff8120300c)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:alloc_perf_context
```
```
In kernel/events/ring_buffer.c (ffffffff8120ea9d)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc
  - kernel/events/ring_buffer.c:rb_alloc_aux
  - kernel/events/ring_buffer.c:perf_aux_output_skip
  - kernel/events/ring_buffer.c:perf_aux_output_end
  - kernel/events/ring_buffer.c:perf_aux_output_begin
  - kernel/events/ring_buffer.c:perf_output_put_handle
```
```
In kernel/events/uprobes.c (ffffffff812120f1)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__create_xol_area
```
```
In kernel/padata.c (ffffffff81213c94)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_alloc_pd
```
```
In kernel/jump_label.c (ffffffff812152bc)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In mm/filemap.c (ffffffff8121dc87)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/shmem.c (ffffffff81236842)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_inode
```
```
In mm/backing-dev.c (ffffffff8123ff05)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_alloc_node
  - mm/backing-dev.c:wb_congested_get_create
  - mm/backing-dev.c:default_bdi_init
```
```
In mm/rmap.c (ffffffff8126baf0)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - mm/rmap.c:hugepage_add_new_anon_rmap
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:anon_vma_ctor
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:__anon_vma_prepare
```
```
In mm/page_alloc.c (ffffffff81277b3f)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:memmap_init_zone_device
  - mm/page_alloc.c:memmap_init_zone_device
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:make_alloc_exact
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:prep_new_page
  - mm/page_alloc.c:prep_new_page
  - mm/page_alloc.c:prep_new_page
  - mm/page_alloc.c:check_new_page_bad
  - mm/page_alloc.c:init_cma_reserved_pageblock
  - mm/page_alloc.c:init_cma_reserved_pageblock
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:bad_page
```
```
In mm/swap_state.c (ffffffff8127d977)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - mm/swap_state.c:init_swap_address_space
  - mm/swap_state.c:swap_cluster_readahead
```
```
In mm/frontswap.c (ffffffff812842ff)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_invalidate_area
```
```
In mm/zswap.c (ffffffff81284a26)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - mm/zswap.c:zswap_pool_create
```
```
In mm/hugetlb.c (ffffffff81286f0e)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:update_and_free_page
  - mm/hugetlb.c:update_and_free_page
  - mm/hugetlb.c:update_and_free_page
  - mm/hugetlb.c:dequeue_huge_page_nodemask
  - mm/hugetlb.c:resv_map_alloc
```
```
In mm/mempolicy.c (ffffffff81292fb8)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:__mpol_dup
```
```
In mm/memory_hotplug.c (ffffffff812a214e)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__online_page_free
  - mm/memory_hotplug.c:put_page_bootmem
```
```
In mm/huge_memory.c (ffffffff812ab588)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In mm/memcontrol.c (ffffffff812b8221)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_select_victim_node
```
```
In mm/zpool.c (ffffffff812c42a9)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - mm/zpool.c:zpool_register_driver
```
```
In mm/zsmalloc.c (ffffffff812c52af)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - mm/zsmalloc.c:reset_page
```
```
In fs/super.c (ffffffff812d5fc3)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/super.c:alloc_super
```
```
In fs/exec.c (ffffffff812dc991)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In fs/dcache.c (ffffffff812f107e)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/dcache.c:__d_alloc
```
```
In fs/inode.c (ffffffff812f1e7a)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/inode.c:inode_init_always
  - fs/inode.c:inode_init_always
  - fs/inode.c:inode_init_always
  - fs/inode.c:inode_init_always
```
```
In fs/file.c (ffffffff812f6420)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/file.c:dup_fd
```
```
In fs/namespace.c (ffffffff812f7881)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In fs/fsopen.c (ffffffff81315028)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/fsopen.c:__ia32_sys_fspick
  - fs/fsopen.c:__x64_sys_fspick
  - fs/fsopen.c:__ia32_sys_fsopen
  - fs/fsopen.c:__x64_sys_fsopen
```
```
In fs/block_dev.c (ffffffff8131b729)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_direct_IO
```
```
In fs/notify/group.c (ffffffff81323111)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_alloc_group
  - fs/notify/group.c:fsnotify_alloc_group
  - fs/notify/group.c:fsnotify_alloc_group
```
```
In fs/notify/mark.c (ffffffff813234d2)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_init_mark
```
```
In fs/eventfd.c (ffffffff8132dc25)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/eventfd.c:do_eventfd
```
```
In fs/userfaultfd.c (ffffffff8132e350)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/userfaultfd.c:__ia32_sys_userfaultfd
  - fs/userfaultfd.c:__x64_sys_userfaultfd
  - fs/userfaultfd.c:dup_userfaultfd
```
```
In fs/aio.c (ffffffff813344bd)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:__ia32_sys_io_destroy
  - fs/aio.c:__x64_sys_io_destroy
  - fs/aio.c:exit_aio
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
```
```
In fs/io_uring.c (ffffffff8133ac61)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_get_req
```
```
In fs/crypto/keyring.c (ffffffff813428b5)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/crypto/keyring.c:add_master_key
```
```
In fs/crypto/keysetup_v1.c (ffffffff8134474f)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
```
```
In fs/mbcache.c (ffffffff8135588b)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/posix_acl.c (ffffffff81356177)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/posix_acl.c:posix_acl_clone
  - fs/posix_acl.c:posix_acl_alloc
```
```
In fs/coredump.c (ffffffff81357feb)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/iomap/buffered-io.c (ffffffff81359b73)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In fs/iomap/direct-io.c (ffffffff8135b50a)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_rw
```
```
In fs/quota/dquot.c (ffffffff8135eef8)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/quota/dquot.c:dqget
```
```
In fs/proc/generic.c (ffffffff8136d925)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/proc/generic.c:__proc_create
```
```
In fs/kernfs/dir.c (ffffffff8137a243)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/kernfs/dir.c:__kernfs_new_node
```
```
In fs/kernfs/file.c (ffffffff8137bd53)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_fop_open
  - fs/kernfs/file.c:kernfs_fop_open
```
```
In fs/configfs/dir.c (ffffffff8137fb81)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_new_dirent
  - fs/configfs/dir.c:new_fragment
```
```
In fs/configfs/item.c (ffffffff81382578)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/configfs/item.c:config_group_init_type_name
  - fs/configfs/item.c:config_item_init_type_name
```
```
In fs/ext4/mballoc.c (ffffffff813b62e0)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
```
```
In fs/ext4/page-io.c (ffffffff813c12af)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_init_io_end
```
```
In fs/ext4/super.c (ffffffff813cf7c0)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_alloc_inode
```
```
In fs/jbd2/transaction.c (ffffffff813e556a)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
```
```
In fs/jbd2/journal.c (ffffffff813ee2e9)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_init_common
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/ecryptfs/main.c (ffffffff81409836)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_get_lower_file
```
```
In fs/ecryptfs/super.c (ffffffff81409a5f)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/ecryptfs/super.c:ecryptfs_alloc_inode
```
```
In fs/ecryptfs/miscdev.c (ffffffff828ea75c)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/ecryptfs/miscdev.c:ecryptfs_init_ecryptfs_miscdev
```
```
In fs/fuse/dev.c (ffffffff81413ae6)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_request_alloc
```
```
In fs/fuse/file.c (ffffffff8141ea08)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_file_alloc
```
```
In fs/fuse/inode.c (ffffffff8142109b)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_conn_init
  - fs/fuse/inode.c:fuse_conn_init
  - fs/fuse/inode.c:fuse_conn_init
```
```
In fs/debugfs/file.c (ffffffff814267f5)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_atomic_t_set
  - fs/debugfs/file.c:debugfs_file_get
```
```
In ipc/util.c (ffffffff8142b345)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In ipc/msg.c (ffffffff828eac78)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - ipc/msg.c:msg_init
  - ipc/msg.c:msg_init
```
```
In ipc/sem.c (ffffffff814320a2)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - ipc/sem.c:copy_semundo
  - ipc/sem.c:find_alloc_undo
```
```
In ipc/namespace.c (ffffffff81438a62)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - ipc/namespace.c:copy_ipcs
```
```
In security/keys/key.c (ffffffff8143a18a)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_user_lookup
  - security/keys/key.c:key_user_lookup
  - security/keys/key.c:key_user_lookup
```
```
In security/selinux/avc.c (ffffffff8144f3fb)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - security/selinux/avc.c:selinux_avc_init
  - security/selinux/avc.c:selinux_avc_init
```
```
In security/selinux/ss/services.c (ffffffff8146cbd9)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
```
```
In security/tomoyo/condition.c (ffffffff8147f6aa)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
```
```
In security/tomoyo/gc.c (ffffffff81483cf7)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In security/tomoyo/memory.c (ffffffff81484766)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_name
  - security/tomoyo/memory.c:tomoyo_get_group
```
```
In security/apparmor/apparmorfs.c (ffffffff8148b961)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_write_access
```
```
In security/apparmor/lib.c (ffffffff8148e09a)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - security/apparmor/lib.c:aa_str_alloc
```
```
In security/apparmor/match.c (ffffffff8148ea87)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
```
```
In security/apparmor/policy_unpack.c (ffffffff8149837d)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:aa_loaddata_alloc
```
```
In security/apparmor/policy_ns.c (ffffffff8149e416)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:alloc_ns
```
```
In security/apparmor/label.c (ffffffff8149f6a2)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_alloc
  - security/apparmor/label.c:aa_alloc_proxy
```
```
In crypto/api.c (ffffffff814b2d38)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - crypto/api.c:crypto_alg_mod_lookup
```
```
In crypto/algapi.c (ffffffff814b3cad)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - crypto/algapi.c:__crypto_register_alg
  - crypto/algapi.c:crypto_check_alg
```
```
In block/bio.c (ffffffff814d309d)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - block/bio.c:bio_reset
  - block/bio.c:bio_init
  - block/bio.c:bio_init
```
```
In block/blk-core.c (ffffffff814d8585)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - block/blk-core.c:blk_rq_init
```
```
In block/blk-ioc.c (ffffffff814decf6)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - block/blk-ioc.c:create_task_io_context
  - block/blk-ioc.c:create_task_io_context
```
```
In block/blk-mq.c (ffffffff814e6f1e)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/bsg.c (ffffffff814fc1ae)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - block/bsg.c:bsg_open
```
```
In block/bsg-lib.c (ffffffff814fccbd)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_queue_rq
```
```
In block/blk-cgroup.c (ffffffff814fd78d)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_css_alloc
```
```
In block/blk-iocost.c (ffffffff8150666b)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - block/blk-iocost.c:blk_iocost_init
```
```
In block/blk-wbt.c (ffffffff8150eb7a)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_init
```
```
In lib/rhashtable.c (ffffffff8151f57a)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_init
```
```
In lib/cpu_rmap.c (ffffffff8154a083)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - lib/cpu_rmap.c:alloc_cpu_rmap
```
```
In lib/sbitmap.c (ffffffff8155017f)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbq_wake_up
```
```
In drivers/pinctrl/core.c (ffffffff81554f03)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:create_pinctrl
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff8159dbc1)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
```
```
In drivers/rapidio/rio.c (ffffffff815a812d)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_register_mport
  - drivers/rapidio/rio.c:rio_mport_initialize
  - drivers/rapidio/rio.c:rio_del_device
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff815b16cd)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:register_framebuffer
```
```
In drivers/acpi/ec.c (ffffffff815d80c4)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_add_query_handler
```
```
In drivers/acpi/apei/ghes.c (ffffffff816378a8)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
```
```
In drivers/clk/clk.c (ffffffff81645a8f)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_core_init
```
```
In drivers/dma/dmaengine.c (ffffffff8164ac98)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaengine_get_unmap_data
  - drivers/dma/dmaengine.c:dma_async_device_register
```
```
In drivers/xen/balloon.c (ffffffff81658e63)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_process
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff816634c4)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_open
```
```
In drivers/reset/core.c (ffffffff8167582d)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In drivers/tty/tty_io.c (ffffffff81679a3b)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:alloc_tty_struct
```
```
In drivers/tty/tty_buffer.c (ffffffff81680f89)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_init
  - drivers/tty/tty_buffer.c:tty_buffer_init
```
```
In drivers/tty/tty_port.c (ffffffff81681272)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_init
```
```
In drivers/tty/serial/serial_core.c (ffffffff81699ea5)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_add_one_port
```
```
In drivers/char/virtio_console.c (ffffffff816b626a)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:add_port
```
```
In drivers/char/hw_random/core.c (ffffffff816b8e8c)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In drivers/char/agp/backend.c (ffffffff816b9424)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/char/agp/backend.c:agp_alloc_bridge
  - drivers/char/agp/backend.c:agp_alloc_bridge
```
```
In drivers/iommu/iova.c (ffffffff816d1344)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/iommu/iova.c:fq_flush_timeout
  - drivers/iommu/iova.c:init_iova_flush_queue
```
```
In drivers/connector/cn_queue.c (ffffffff816e81da)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/connector/cn_queue.c:cn_queue_alloc_dev
  - drivers/connector/cn_queue.c:cn_queue_add_callback
```
```
In drivers/lightnvm/core.c (ffffffff816e9766)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_alloc_dev
```
```
In drivers/base/core.c (ffffffff816ef86a)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/power/runtime.c (ffffffff81702025)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_init
  - drivers/base/power/runtime.c:pm_runtime_init
```
```
In drivers/base/power/wakeup.c (ffffffff817077b8)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:pm_wakeup_clear
```
```
In drivers/base/power/domain.c (ffffffff81708eba)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/base/power/domain.c:pm_genpd_init
```
```
In drivers/base/firmware_loader/main.c (ffffffff8170d6cc)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
```
```
In drivers/block/loop.c (ffffffff8171f50d)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_add
  - drivers/block/loop.c:lo_rw_aio
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In drivers/mfd/mfd-core.c (ffffffff817379f4)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_add_devices
```
```
In drivers/nvdimm/core.c (ffffffff8174398f)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff8174693c)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:__nvdimm_create
```
```
In drivers/nvdimm/dimm.c (ffffffff81747857)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In drivers/dax/bus.c (ffffffff81757b90)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In drivers/dma-buf/dma-fence.c (ffffffff81759c9b)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In drivers/dma-buf/dma-fence-array.c (ffffffff8175a5aa)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_create
```
```
In drivers/dma-buf/sw_sync.c (ffffffff8175cc0a)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open
```
```
In drivers/scsi/scsi.c (ffffffff8175fb05)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_finish_command
  - drivers/scsi/scsi.c:scsi_finish_command
  - drivers/scsi/scsi.c:scsi_finish_command
```
```
In drivers/scsi/scsi_lib.c (ffffffff81768572)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:__scsi_queue_insert
  - drivers/scsi/scsi_lib.c:__scsi_queue_insert
  - drivers/scsi/scsi_lib.c:__scsi_queue_insert
```
```
In drivers/scsi/scsi_scan.c (ffffffff8176995d)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
```
```
In drivers/scsi/sd.c (ffffffff81778d77)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
```
```
In drivers/scsi/sr.c (ffffffff8177b04d)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_probe
```
```
In drivers/scsi/sg.c (ffffffff8177d1d8)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_open
```
```
In drivers/ata/libata-core.c (ffffffff81783164)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_init
  - drivers/ata/libata-core.c:ata_host_alloc
```
```
In drivers/net/phy/sfp-bus.c (ffffffff817b4548)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_bus_get
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817bcb9d)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
```
```
In drivers/vfio/vfio.c (ffffffff817c54f0)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_fops_open
  - drivers/vfio/vfio.c:vfio_add_group_dev
  - drivers/vfio/vfio.c:vfio_add_group_dev
  - drivers/vfio/vfio.c:vfio_add_group_dev
  - drivers/vfio/vfio.c:vfio_add_group_dev
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff817c9507)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff817cc5dc)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_probe
```
```
In drivers/usb/core/usb.c (ffffffff817d83b4)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/usb/core/usb.c:usb_alloc_dev
```
```
In drivers/usb/core/hub.c (ffffffff817e0eca)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_probe
```
```
In drivers/usb/core/hcd.c (ffffffff817e186f)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:__usb_create_hcd
```
```
In drivers/usb/core/urb.c (ffffffff817e51cf)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_init_urb
```
```
In drivers/usb/core/config.c (ffffffff817eb9d8)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_configuration
```
```
In drivers/usb/core/file.c (ffffffff817ed2bf)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In drivers/media/cec/cec-notifier.c (ffffffff81871272)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In drivers/thermal/thermal_core.c (ffffffff8187cf61)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
```
```
In drivers/md/md.c (ffffffff81895ca8)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_run
  - drivers/md/md.c:max_corrected_read_errors_store
  - drivers/md/md.c:md_rdev_init
  - drivers/md/md.c:md_rdev_init
  - drivers/md/md.c:md_rdev_init
  - drivers/md/md.c:errors_store
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:mddev_init
  - drivers/md/md.c:mddev_init
  - drivers/md/md.c:mddev_init
  - drivers/md/md.c:mddev_init
  - drivers/md/md.c:submit_flushes
```
```
In drivers/md/md-bitmap.c (ffffffff8189b217)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
```
```
In drivers/md/dm.c (ffffffff8189f238)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:dm_get_table_device
  - drivers/md/dm.c:alloc_io
```
```
In drivers/md/dm-table.c (ffffffff818a14e4)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_get_device
```
```
In drivers/md/dm-stripe.c (ffffffff818a4c12)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:stripe_ctr
```
```
In drivers/md/dm-io.c (ffffffff818a84a3)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/md/dm-io.c:dm_io
  - drivers/md/dm-io.c:sync_io
```
```
In drivers/md/dm-kcopyd.c (ffffffff818a94fe)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
  - drivers/md/dm-kcopyd.c:dm_kcopyd_copy
```
```
In drivers/md/dm-stats.c (ffffffff818aa988)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In drivers/edac/ghes_edac.c (ffffffff818b24a2)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/edac/ghes_edac.c:ghes_edac_register
```
```
In drivers/opp/core.c (ffffffff818b480b)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/opp/core.c:_opp_add
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff818bccc3)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_stop
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
  - drivers/cpufreq/cpufreq_governor.c:dbs_update_util_handler
  - drivers/cpufreq/cpufreq_governor.c:dbs_work_handler
```
```
In drivers/mmc/core/sdio_irq.c (ffffffff818d7d81)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_irq.c:sdio_release_irq
  - drivers/mmc/core/sdio_irq.c:sdio_claim_irq
```
```
In drivers/firmware/efi/efi.c (ffffffff81ad6060)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
```
```
In drivers/devfreq/devfreq.c (ffffffff818ea304)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
```
In drivers/nvmem/core.c (ffffffff818f40e6)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In net/core/sock.c (ffffffff81902f7f)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_alloc
```
```
In net/core/skbuff.c (ffffffff8190af96)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_ext_add
  - net/core/skbuff.c:skb_ext_add
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:sock_zerocopy_realloc
  - net/core/skbuff.c:sock_zerocopy_alloc
  - net/core/skbuff.c:__skb_clone
  - net/core/skbuff.c:__build_skb_around
  - net/core/skbuff.c:__build_skb_around
  - net/core/skbuff.c:__alloc_skb
  - net/core/skbuff.c:__alloc_skb
  - net/core/skbuff.c:__alloc_skb
```
```
In net/core/net_namespace.c (ffffffff81916f76)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/core/net_namespace.c:copy_net_ns
  - net/core/net_namespace.c:copy_net_ns
  - net/core/net_namespace.c:setup_net
  - net/core/net_namespace.c:setup_net
```
```
In net/core/dev.c (ffffffff81921395)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/core/dev.c:__dev_kfree_skb_irq
```
```
In net/core/dst.c (ffffffff81931e75)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/core/dst.c:__metadata_dst_init
  - net/core/dst.c:dst_cow_metrics_generic
```
```
In net/core/neighbour.c (ffffffff81937a14)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:___neigh_create
```
```
In net/core/filter.c (ffffffff8194ff1f)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/core/filter.c:__sk_attach_prog
```
```
In net/core/page_pool.c (ffffffff819581a5)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_create
  - net/core/page_pool.c:page_pool_create
```
```
In net/core/skmsg.c (ffffffff81959d85)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_init
```
```
In net/core/netpoll.c (ffffffff8195b38f)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/core/netpoll.c:__netpoll_setup
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:zap_completion_queue
```
```
In net/core/fib_rules.c (ffffffff8195e8fe)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_default_rule_add
```
```
In net/core/devlink.c (ffffffff81975381)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_traps_register
  - net/core/devlink.c:devlink_health_reporter_create
```
```
In net/sched/sch_generic.c (ffffffff8197f24e)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_alloc
```
```
In net/sched/cls_api.c (ffffffff8198a400)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tcf_block_get_ext
```
```
In net/sched/act_api.c (ffffffff8198b250)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_idr_create
  - net/sched/act_api.c:tcf_idr_create
```
```
In net/netfilter/nfnetlink_log.c (ffffffff8199bbe4)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/netfilter/nfnetlink_log.c:nfulnl_recv_config
```
```
In net/netfilter/nf_conntrack_core.c (ffffffff819a0b95)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_core.c:nf_conntrack_init_net
  - net/netfilter/nf_conntrack_core.c:__nf_conntrack_alloc
  - net/netfilter/nf_conntrack_core.c:nf_conntrack_hash_check_insert
  - net/netfilter/nf_conntrack_core.c:nf_ct_tmpl_alloc
```
```
In net/netfilter/nf_conntrack_expect.c (ffffffff819a1c87)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_expect.c:nf_ct_expect_alloc
```
```
In net/netfilter/nf_conntrack_helper.c (ffffffff819a38b7)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_helper.c:nf_conntrack_helper_register
```
```
In net/ipv4/route.c (ffffffff819b2675)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_genid_init
  - net/ipv4/route.c:rt_genid_init
  - net/ipv4/route.c:rt_genid_init
```
```
In net/ipv4/inetpeer.c (ffffffff819b7ded)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff819c45fc)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819c5155)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_hash_add
```
```
In net/ipv4/tcp.c (ffffffff819c7128)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv4/tcp.c:skb_entail
```
```
In net/ipv4/tcp_input.c (ffffffff819cf073)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/tcp_output.c (ffffffff819dc591)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819e2d81)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In net/ipv4/tcp_fastopen.c (ffffffff819eaad8)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/devinet.c (ffffffff819fd2a8)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_init
```
```
In net/ipv4/igmp.c (ffffffff81a040bb)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv4/igmp.c:____ip_mc_inc_group
```
```
In net/ipv4/fib_semantics.c (ffffffff81a0a925)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/ipv4/inet_fragment.c (ffffffff81a10bd3)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frags_init
```
```
In net/ipv4/metrics.c (ffffffff81a145cc)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In net/ipv4/nexthop.c (ffffffff81a16acb)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81a1730f)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:proc_tfo_blackhole_detect_timeout
```
```
In net/ipv4/ipmr.c (ffffffff81a1d452)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv4/syncookies.c (ffffffff81a2006f)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:tcp_get_cookie_sock
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81a23a36)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a27b42)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
```
```
In net/xfrm/xfrm_state.c (ffffffff81a2f05f)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
```
```
In net/unix/af_unix.c (ffffffff81a3b9bd)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
```
```
In net/ipv6/af_inet6.c (ffffffff81a3fb27)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In net/ipv6/anycast.c (ffffffff81a407ab)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
```
```
In net/ipv6/addrconf.c (ffffffff81a4b2e2)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/route.c (ffffffff81a530b8)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_upper_bound_set
```
```
In net/ipv6/ip6_fib.c (ffffffff81a60214)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_metric_set
  - net/ipv6/ip6_fib.c:fib6_info_alloc
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81a63f50)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In net/ipv6/mcast.c (ffffffff81a7464a)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
```
```
In net/ipv6/exthdrs.c (ffffffff81a7dad8)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_dup_options
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81a80420)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:fl_create
```
```
In net/ipv6/ip6mr.c (ffffffff81a85939)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/ipv6/calipso.c (ffffffff81a8c9de)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_doi_add
```
```
In net/packet/af_packet.c (ffffffff81a9b1dc)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
```
```
In net/xdp/xdp_umem.c (ffffffff81ab7d15)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_create
```
```
In lib/dump_stack.c (ffffffff81ab9818)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - lib/dump_stack.c:dump_stack
```
```
In lib/klist.c (ffffffff81abb402)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - lib/klist.c:klist_node_init
```
```
In lib/kobject.c (ffffffff81abc956)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - lib/kobject.c:kset_register
  - lib/kobject.c:kobject_init
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
In arch/x86/kernel/tboot.c (ffffffff828af9ba)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104da9c)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:fake_panic_set
  - arch/x86/kernel/cpu/mce/core.c:fake_panic_set
  - arch/x86/kernel/cpu/mce/core.c:fake_panic_set
  - arch/x86/kernel/cpu/mce/core.c:fake_panic_set
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81053799)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff81054307)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff81057e3d)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In arch/x86/kernel/reboot.c (ffffffff810643b7)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff81066e06)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_target
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
```
```
In arch/x86/kernel/kgdb.c (ffffffff81075f8f)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In arch/x86/mm/init_64.c (ffffffff81ae2ca2)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pagetable
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff828cb0f2)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_common
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus
```
```
In kernel/fork.c (ffffffff8109fec7)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:mm_init
  - kernel/fork.c:mm_init
  - kernel/fork.c:mm_init
```
```
In kernel/softirq.c (ffffffff810a8b45)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/softirq.c:tasklet_init
```
```
In kernel/user.c (ffffffff810b0dda)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/user.c:alloc_uid
```
```
In kernel/workqueue.c (ffffffff810c6512)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_offline_cpu
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:flush_workqueue_prep_pwqs
```
```
In kernel/pid.c (ffffffff810c7e17)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/pid.c:alloc_pid
```
```
In kernel/nsproxy.c (ffffffff810ce271)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/nsproxy.c:create_new_namespaces
```
```
In kernel/cred.c (ffffffff810cfbb3)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:cred_alloc_blank
```
```
In kernel/smpboot.c (ffffffff810d1837)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/smpboot.c:cpu_wait_death
  - kernel/smpboot.c:cpu_check_up_prepare
```
```
In kernel/groups.c (ffffffff810d2298)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/groups.c:groups_alloc
```
```
In kernel/sched/core.c (ffffffff828ce60a)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init
```
```
In kernel/sched/fair.c (ffffffff810eb162)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_fault
```
```
In kernel/sched/cpupri.c (ffffffff810f77f7)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_init
```
```
In kernel/sched/topology.c (ffffffff810f901f)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:init_defrootdomain
```
```
In kernel/sched/autogroup.c (ffffffff810fbc7f)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
  - kernel/sched/autogroup.c:autogroup_init
```
```
In kernel/sched/membarrier.c (ffffffff81102edf)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/sched/membarrier.c:membarrier_exec_mmap
```
```
In kernel/sched/psi.c (ffffffff81103557)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_trigger_destroy
  - kernel/sched/psi.c:psi_poll_work
  - kernel/sched/psi.c:group_init
```
```
In kernel/locking/mutex.c (ffffffff81104ac4)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/locking/mutex.c:__mutex_init
```
```
In kernel/locking/rwsem.c (ffffffff81104f2c)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:__init_rwsem
```
```
In kernel/power/swap.c (ffffffff8110fdbe)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:load_image
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:save_image
```
```
In kernel/irq/manage.c (ffffffff81119642)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_notifier
```
```
In kernel/rcu/srcutree.c (ffffffff81126a42)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
```
```
In kernel/rcu/tree.c (ffffffff8112a460)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In kernel/futex.c (ffffffff828d226c)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/futex.c:futex_init
```
```
In kernel/module.c (ffffffff81158b87)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/module.c:load_module
```
```
In kernel/kexec_core.c (ffffffff8115d762)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_free_reserved_phys_range
  - kernel/kexec_core.c:crash_kexec
```
```
In kernel/cgroup/cgroup.c (ffffffff81163ad0)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:init_cgroup_root
  - kernel/cgroup/cgroup.c:find_css_set
```
```
In kernel/cgroup/namespace.c (ffffffff8116b10f)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
```
```
In kernel/utsname.c (ffffffff81175188)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/utsname.c:copy_utsname
```
```
In kernel/user_namespace.c (ffffffff811764a5)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In kernel/pid_namespace.c (ffffffff81177038)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In kernel/stop_machine.c (ffffffff81177f9a)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:stop_two_cpus
  - kernel/stop_machine.c:multi_cpu_stop
  - kernel/stop_machine.c:cpu_stop_init_done
```
```
In kernel/audit_watch.c (ffffffff81181ee8)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_init_watch
```
```
In kernel/audit_tree.c (ffffffff81184397)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_make_tree
```
```
In kernel/debug/debug_core.c (ffffffff81187ebe)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_tasklet_bpt
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff8118d36f)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In kernel/hung_task.c (ffffffff811932f5)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/hung_task.c:reset_hung_task_detector
```
```
In kernel/seccomp.c (ffffffff81195c52)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
```
```
In kernel/relay.c (ffffffff81196afd)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/relay.c:__relay_reset
```
```
In kernel/trace/trace.c (ffffffff811a9e81)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
```
```
In kernel/trace/tracing_map.c (ffffffff811b52ae)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_create
  - kernel/trace/tracing_map.c:tracing_map_clear
```
```
In kernel/trace/blktrace.c (ffffffff811bb4a7)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:do_blk_trace_setup
```
```
In kernel/trace/fgraph.c (ffffffff811be39d)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/trace/fgraph.c:start_graph_tracing
  - kernel/trace/fgraph.c:start_graph_tracing
  - kernel/trace/fgraph.c:ftrace_graph_init_task
  - kernel/trace/fgraph.c:ftrace_graph_init_task
```
```
In kernel/trace/trace_events.c (ffffffff811be7dc)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_create_new_event
  - kernel/trace/trace_events.c:trace_create_new_event
```
```
In kernel/bpf/syscall.c (ffffffff811e607c)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:map_create
```
```
In kernel/bpf/btf.c (ffffffff812032dc)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_new_fd
```
```
In kernel/events/core.c (ffffffff81212bdc)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:alloc_perf_context
```
```
In kernel/events/ring_buffer.c (ffffffff8121d9ad)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc
  - kernel/events/ring_buffer.c:rb_alloc_aux
  - kernel/events/ring_buffer.c:perf_aux_output_skip
  - kernel/events/ring_buffer.c:perf_aux_output_end
  - kernel/events/ring_buffer.c:perf_aux_output_begin
  - kernel/events/ring_buffer.c:perf_output_put_handle
```
```
In kernel/events/uprobes.c (ffffffff81221071)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__create_xol_area
```
```
In kernel/padata.c (ffffffff81222ed4)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_alloc_pd
```
```
In kernel/jump_label.c (ffffffff812242ac)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In mm/filemap.c (ffffffff8122ccf7)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/shmem.c (ffffffff81243b72)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_inode
```
```
In mm/backing-dev.c (ffffffff8124f665)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_alloc_node
  - mm/backing-dev.c:wb_congested_get_create
  - mm/backing-dev.c:default_bdi_init
```
```
In mm/rmap.c (ffffffff8127b480)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - mm/rmap.c:hugepage_add_new_anon_rmap
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:anon_vma_ctor
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:__anon_vma_prepare
```
```
In mm/page_alloc.c (ffffffff8128772f)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:memmap_init_zone_device
  - mm/page_alloc.c:memmap_init_zone_device
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:make_alloc_exact
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:prep_new_page
  - mm/page_alloc.c:prep_new_page
  - mm/page_alloc.c:prep_new_page
  - mm/page_alloc.c:check_new_page_bad
  - mm/page_alloc.c:init_cma_reserved_pageblock
  - mm/page_alloc.c:init_cma_reserved_pageblock
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:bad_page
```
```
In mm/swap_state.c (ffffffff8128d527)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - mm/swap_state.c:init_swap_address_space
  - mm/swap_state.c:swap_cluster_readahead
```
```
In mm/frontswap.c (ffffffff8129412f)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_invalidate_area
```
```
In mm/zswap.c (ffffffff812946c6)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - mm/zswap.c:zswap_pool_create
```
```
In mm/hugetlb.c (ffffffff812975de)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:update_and_free_page
  - mm/hugetlb.c:update_and_free_page
  - mm/hugetlb.c:update_and_free_page
  - mm/hugetlb.c:dequeue_huge_page_nodemask
  - mm/hugetlb.c:resv_map_alloc
```
```
In mm/mempolicy.c (ffffffff812a2db8)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:__mpol_dup
```
```
In mm/memory_hotplug.c (ffffffff812b23de)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__online_page_free
  - mm/memory_hotplug.c:put_page_bootmem
```
```
In mm/huge_memory.c (ffffffff812bb8ef)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In mm/memcontrol.c (ffffffff812c8b51)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_select_victim_node
```
```
In mm/zpool.c (ffffffff812d4d49)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - mm/zpool.c:zpool_register_driver
```
```
In mm/zsmalloc.c (ffffffff812d5d8f)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - mm/zsmalloc.c:reset_page
```
```
In fs/super.c (ffffffff812e7923)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/super.c:alloc_super
```
```
In fs/exec.c (ffffffff812ed73c)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In fs/dcache.c (ffffffff8130223e)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/dcache.c:__d_alloc
```
```
In fs/inode.c (ffffffff8130344a)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/inode.c:inode_init_always
  - fs/inode.c:inode_init_always
  - fs/inode.c:inode_init_always
  - fs/inode.c:inode_init_always
```
```
In fs/file.c (ffffffff81307630)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/file.c:dup_fd
```
```
In fs/namespace.c (ffffffff81308b91)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In fs/fsopen.c (ffffffff81326b98)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/fsopen.c:__ia32_sys_fspick
  - fs/fsopen.c:__x64_sys_fspick
  - fs/fsopen.c:__ia32_sys_fsopen
  - fs/fsopen.c:__x64_sys_fsopen
```
```
In fs/block_dev.c (ffffffff8132d509)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_direct_IO
```
```
In fs/notify/group.c (ffffffff81334e51)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_alloc_group
  - fs/notify/group.c:fsnotify_alloc_group
  - fs/notify/group.c:fsnotify_alloc_group
```
```
In fs/notify/mark.c (ffffffff81335362)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_init_mark
```
```
In fs/eventfd.c (ffffffff81340a05)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/eventfd.c:do_eventfd
```
```
In fs/userfaultfd.c (ffffffff81340c50)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/userfaultfd.c:__ia32_sys_userfaultfd
  - fs/userfaultfd.c:__x64_sys_userfaultfd
  - fs/userfaultfd.c:dup_userfaultfd
```
```
In fs/aio.c (ffffffff81346931)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:__ia32_sys_io_destroy
  - fs/aio.c:__x64_sys_io_destroy
  - fs/aio.c:exit_aio
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
```
```
In fs/io_uring.c (ffffffff8134de11)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_get_req
```
```
In fs/crypto/keyring.c (ffffffff81355bb5)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/crypto/keyring.c:add_master_key
```
```
In fs/crypto/keysetup_v1.c (ffffffff81357a2f)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
```
```
In fs/mbcache.c (ffffffff81368eab)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/posix_acl.c (ffffffff81369847)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/posix_acl.c:posix_acl_clone
  - fs/posix_acl.c:posix_acl_alloc
```
```
In fs/coredump.c (ffffffff8136b722)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/iomap/buffered-io.c (ffffffff8136d283)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In fs/iomap/direct-io.c (ffffffff8136ec5a)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_rw
```
```
In fs/quota/dquot.c (ffffffff8137191f)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/quota/dquot.c:dqget
```
```
In fs/proc/generic.c (ffffffff81381258)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/proc/generic.c:__proc_create
```
```
In fs/kernfs/dir.c (ffffffff8138d2d4)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/kernfs/dir.c:__kernfs_new_node
```
```
In fs/kernfs/file.c (ffffffff8138f8db)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_fop_open
  - fs/kernfs/file.c:kernfs_fop_open
```
```
In fs/configfs/dir.c (ffffffff813930d1)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_new_dirent
  - fs/configfs/dir.c:new_fragment
```
```
In fs/configfs/item.c (ffffffff81396098)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/configfs/item.c:config_group_init_type_name
  - fs/configfs/item.c:config_item_init_type_name
```
```
In fs/ext4/mballoc.c (ffffffff813cb004)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
```
```
In fs/ext4/page-io.c (ffffffff813d640f)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_init_io_end
```
```
In fs/ext4/super.c (ffffffff813e4dc0)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_alloc_inode
```
```
In fs/jbd2/transaction.c (ffffffff813fab35)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
```
```
In fs/jbd2/journal.c (ffffffff81403f39)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_init_common
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/ecryptfs/main.c (ffffffff8141f4f6)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_get_lower_file
```
```
In fs/ecryptfs/super.c (ffffffff8141f71f)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/ecryptfs/super.c:ecryptfs_alloc_inode
```
```
In fs/ecryptfs/miscdev.c (ffffffff828efb72)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/ecryptfs/miscdev.c:ecryptfs_init_ecryptfs_miscdev
```
```
In fs/fuse/dev.c (ffffffff8142a966)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_request_alloc
```
```
In fs/fuse/file.c (ffffffff81435768)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_file_alloc
```
```
In fs/fuse/inode.c (ffffffff81437f1b)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_conn_init
  - fs/fuse/inode.c:fuse_conn_init
  - fs/fuse/inode.c:fuse_conn_init
```
```
In fs/debugfs/file.c (ffffffff8143d6b5)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_atomic_t_set
  - fs/debugfs/file.c:debugfs_file_get
```
```
In ipc/util.c (ffffffff81442295)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In ipc/msg.c (ffffffff828f008e)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - ipc/msg.c:msg_init
  - ipc/msg.c:msg_init
```
```
In ipc/sem.c (ffffffff81449172)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - ipc/sem.c:copy_semundo
  - ipc/sem.c:find_alloc_undo
```
```
In ipc/namespace.c (ffffffff8144fbd2)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - ipc/namespace.c:copy_ipcs
```
```
In security/keys/key.c (ffffffff814512bb)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_user_lookup
  - security/keys/key.c:key_user_lookup
  - security/keys/key.c:key_user_lookup
```
```
In security/selinux/avc.c (ffffffff8146680b)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - security/selinux/avc.c:selinux_avc_init
  - security/selinux/avc.c:selinux_avc_init
```
```
In security/selinux/ss/services.c (ffffffff814843f8)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
```
```
In security/tomoyo/condition.c (ffffffff814971da)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
```
```
In security/tomoyo/gc.c (ffffffff8149b837)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In security/tomoyo/memory.c (ffffffff8149c2a6)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_name
  - security/tomoyo/memory.c:tomoyo_get_group
```
```
In security/apparmor/apparmorfs.c (ffffffff814a3741)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_write_access
```
```
In security/apparmor/lib.c (ffffffff814a5faa)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - security/apparmor/lib.c:aa_str_alloc
```
```
In security/apparmor/match.c (ffffffff814a6997)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
```
```
In security/apparmor/policy_unpack.c (ffffffff814b04cd)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:aa_loaddata_alloc
```
```
In security/apparmor/policy_ns.c (ffffffff814b6a06)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:alloc_ns
```
```
In security/apparmor/label.c (ffffffff814b7cd2)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_alloc
  - security/apparmor/label.c:aa_alloc_proxy
```
```
In crypto/api.c (ffffffff814cb7b8)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - crypto/api.c:crypto_alg_mod_lookup
```
```
In crypto/algapi.c (ffffffff814cc72d)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - crypto/algapi.c:__crypto_register_alg
  - crypto/algapi.c:crypto_check_alg
```
```
In block/bio.c (ffffffff814ec1bd)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - block/bio.c:bio_reset
  - block/bio.c:bio_init
  - block/bio.c:bio_init
```
```
In block/blk-core.c (ffffffff814f1195)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - block/blk-core.c:blk_rq_init
```
```
In block/blk-ioc.c (ffffffff814f7b66)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - block/blk-ioc.c:create_task_io_context
  - block/blk-ioc.c:create_task_io_context
```
```
In block/blk-mq.c (ffffffff814ffebf)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/bsg.c (ffffffff8151525e)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - block/bsg.c:bsg_open
```
```
In block/bsg-lib.c (ffffffff81515d6d)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_queue_rq
```
```
In block/blk-cgroup.c (ffffffff81516d4d)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_css_alloc
```
```
In block/blk-iocost.c (ffffffff8151f95b)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - block/blk-iocost.c:blk_iocost_init
```
```
In block/blk-wbt.c (ffffffff8152834a)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_init
```
```
In lib/rhashtable.c (ffffffff81538f9a)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_init
```
```
In lib/cpu_rmap.c (ffffffff81563ed3)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - lib/cpu_rmap.c:alloc_cpu_rmap
```
```
In lib/sbitmap.c (ffffffff81569fbf)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbq_wake_up
```
```
In drivers/pinctrl/core.c (ffffffff8156ed93)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:create_pinctrl
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff815b7ff1)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
```
```
In drivers/rapidio/rio.c (ffffffff815c225d)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_register_mport
  - drivers/rapidio/rio.c:rio_mport_initialize
  - drivers/rapidio/rio.c:rio_del_device
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff815cb13d)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:register_framebuffer
```
```
In drivers/acpi/ec.c (ffffffff815f1f84)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_add_query_handler
```
```
In drivers/acpi/apei/ghes.c (ffffffff81651be8)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
```
```
In drivers/clk/clk.c (ffffffff8166001f)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_core_init
```
```
In drivers/dma/dmaengine.c (ffffffff81665238)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaengine_get_unmap_data
  - drivers/dma/dmaengine.c:dma_async_device_register
```
```
In drivers/xen/balloon.c (ffffffff81673473)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_process
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff8167da84)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_open
```
```
In drivers/reset/core.c (ffffffff8168fe8d)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In drivers/tty/tty_io.c (ffffffff8169409b)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:alloc_tty_struct
```
```
In drivers/tty/tty_buffer.c (ffffffff8169b5d9)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_init
  - drivers/tty/tty_buffer.c:tty_buffer_init
```
```
In drivers/tty/tty_port.c (ffffffff8169b8c2)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_init
```
```
In drivers/tty/serial/serial_core.c (ffffffff816b4aa5)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_add_one_port
```
```
In drivers/char/virtio_console.c (ffffffff816d085a)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:add_port
```
```
In drivers/char/hw_random/core.c (ffffffff816d345c)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In drivers/char/agp/backend.c (ffffffff816d39f4)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/char/agp/backend.c:agp_alloc_bridge
  - drivers/char/agp/backend.c:agp_alloc_bridge
```
```
In drivers/iommu/iova.c (ffffffff816ebc54)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/iommu/iova.c:fq_flush_timeout
  - drivers/iommu/iova.c:init_iova_flush_queue
```
```
In drivers/connector/cn_queue.c (ffffffff817028da)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/connector/cn_queue.c:cn_queue_alloc_dev
  - drivers/connector/cn_queue.c:cn_queue_add_callback
```
```
In drivers/lightnvm/core.c (ffffffff81703fa6)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_alloc_dev
```
```
In drivers/base/core.c (ffffffff8170a0aa)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/power/runtime.c (ffffffff8171c855)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_init
  - drivers/base/power/runtime.c:pm_runtime_init
```
```
In drivers/base/power/wakeup.c (ffffffff817221e8)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:pm_wakeup_clear
```
```
In drivers/base/power/domain.c (ffffffff81723a2a)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/base/power/domain.c:pm_genpd_init
```
```
In drivers/base/firmware_loader/main.c (ffffffff81728486)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
```
```
In drivers/block/loop.c (ffffffff8173a93d)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_add
  - drivers/block/loop.c:lo_rw_aio
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In drivers/mfd/mfd-core.c (ffffffff81752e34)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_add_devices
```
```
In drivers/nvdimm/core.c (ffffffff8175eddf)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff81761d7c)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:__nvdimm_create
```
```
In drivers/nvdimm/dimm.c (ffffffff81762c97)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In drivers/dax/bus.c (ffffffff81773030)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In drivers/dma-buf/dma-fence.c (ffffffff8177520b)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In drivers/dma-buf/dma-fence-array.c (ffffffff81775b6a)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_create
```
```
In drivers/dma-buf/sw_sync.c (ffffffff817782aa)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open
```
```
In drivers/scsi/scsi.c (ffffffff8177b165)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_finish_command
  - drivers/scsi/scsi.c:scsi_finish_command
  - drivers/scsi/scsi.c:scsi_finish_command
```
```
In drivers/scsi/scsi_lib.c (ffffffff81783ca5)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:__scsi_queue_insert
  - drivers/scsi/scsi_lib.c:__scsi_queue_insert
  - drivers/scsi/scsi_lib.c:__scsi_queue_insert
```
```
In drivers/scsi/scsi_scan.c (ffffffff817850ad)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
```
```
In drivers/scsi/sd.c (ffffffff81792b97)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
```
```
In drivers/scsi/sr.c (ffffffff81794bbd)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_probe
```
```
In drivers/scsi/sg.c (ffffffff81797007)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_open
```
```
In drivers/ata/libata-core.c (ffffffff8179d024)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_init
  - drivers/ata/libata-core.c:ata_host_alloc
```
```
In drivers/net/phy/sfp-bus.c (ffffffff817ce518)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_bus_get
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817d77a8)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
```
```
In drivers/vfio/vfio.c (ffffffff817df790)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_fops_open
  - drivers/vfio/vfio.c:vfio_add_group_dev
  - drivers/vfio/vfio.c:vfio_add_group_dev
  - drivers/vfio/vfio.c:vfio_add_group_dev
  - drivers/vfio/vfio.c:vfio_add_group_dev
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff817e37a7)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff817e687c)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_probe
```
```
In drivers/usb/core/usb.c (ffffffff817f2654)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/usb/core/usb.c:usb_alloc_dev
```
```
In drivers/usb/core/hub.c (ffffffff817fb1ba)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_probe
```
```
In drivers/usb/core/hcd.c (ffffffff817fbc5f)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:__usb_create_hcd
```
```
In drivers/usb/core/urb.c (ffffffff817ff42f)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_init_urb
```
```
In drivers/usb/core/config.c (ffffffff81805c18)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_configuration
```
```
In drivers/usb/core/file.c (ffffffff818074ff)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In drivers/media/cec/cec-notifier.c (ffffffff8188b232)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In drivers/media/cec/cec-pin.c (ffffffff8188b8fa)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/media/cec/cec-pin.c:cec_pin_changed
  - drivers/media/cec/cec-pin.c:cec_pin_adap_enable
  - drivers/media/cec/cec-pin.c:cec_pin_adap_enable
  - drivers/media/cec/cec-pin.c:cec_pin_timer
```
```
In drivers/thermal/thermal_core.c (ffffffff81898991)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
```
```
In drivers/md/md.c (ffffffff818b1bba)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_run
  - drivers/md/md.c:max_corrected_read_errors_store
  - drivers/md/md.c:md_rdev_init
  - drivers/md/md.c:md_rdev_init
  - drivers/md/md.c:md_rdev_init
  - drivers/md/md.c:errors_store
  - drivers/md/md.c:super_1_load
  - drivers/md/md.c:mddev_init
  - drivers/md/md.c:mddev_init
  - drivers/md/md.c:mddev_init
  - drivers/md/md.c:mddev_init
  - drivers/md/md.c:submit_flushes
```
```
In drivers/md/md-bitmap.c (ffffffff818b7377)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
```
```
In drivers/md/dm.c (ffffffff818ba360)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:dm_get_table_device
  - drivers/md/dm.c:alloc_io
```
```
In drivers/md/dm-table.c (ffffffff818bd724)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_get_device
```
```
In drivers/md/dm-stripe.c (ffffffff818c0e52)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:stripe_ctr
```
```
In drivers/md/dm-io.c (ffffffff818c46e3)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/md/dm-io.c:dm_io
  - drivers/md/dm-io.c:sync_io
```
```
In drivers/md/dm-kcopyd.c (ffffffff818c590e)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
  - drivers/md/dm-kcopyd.c:dm_kcopyd_copy
```
```
In drivers/md/dm-stats.c (ffffffff818c65a0)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In drivers/edac/ghes_edac.c (ffffffff818ce752)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/edac/ghes_edac.c:ghes_edac_register
```
```
In drivers/opp/core.c (ffffffff818d0abb)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/opp/core.c:_opp_add
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff818d8fb3)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_stop
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
  - drivers/cpufreq/cpufreq_governor.c:dbs_update_util_handler
  - drivers/cpufreq/cpufreq_governor.c:dbs_work_handler
```
```
In drivers/mmc/core/sdio_irq.c (ffffffff818f48a1)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_irq.c:sdio_release_irq
  - drivers/mmc/core/sdio_irq.c:sdio_claim_irq
```
```
In drivers/firmware/efi/efi.c (ffffffff81ae2520)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81905bec)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
```
```
In drivers/devfreq/devfreq.c (ffffffff8190b384)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
```
In drivers/nvmem/core.c (ffffffff81915186)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In net/core/sock.c (ffffffff81923eef)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_alloc
```
```
In net/core/skbuff.c (ffffffff8192c096)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_ext_add
  - net/core/skbuff.c:skb_ext_add
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:sock_zerocopy_realloc
  - net/core/skbuff.c:sock_zerocopy_alloc
  - net/core/skbuff.c:__skb_clone
  - net/core/skbuff.c:__build_skb_around
  - net/core/skbuff.c:__build_skb_around
  - net/core/skbuff.c:__alloc_skb
  - net/core/skbuff.c:__alloc_skb
  - net/core/skbuff.c:__alloc_skb
```
```
In net/core/net_namespace.c (ffffffff81938186)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/core/net_namespace.c:copy_net_ns
  - net/core/net_namespace.c:copy_net_ns
  - net/core/net_namespace.c:setup_net
  - net/core/net_namespace.c:setup_net
```
```
In net/core/dev.c (ffffffff81943205)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/core/dev.c:__dev_kfree_skb_irq
```
```
In net/core/dst.c (ffffffff81953545)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/core/dst.c:__metadata_dst_init
  - net/core/dst.c:dst_cow_metrics_generic
```
```
In net/core/neighbour.c (ffffffff819591e4)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:___neigh_create
```
```
In net/core/filter.c (ffffffff819718ef)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/core/filter.c:__sk_attach_prog
```
```
In net/core/page_pool.c (ffffffff8197a2b5)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_create
  - net/core/page_pool.c:page_pool_create
```
```
In net/core/skmsg.c (ffffffff8197bfa5)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_init
```
```
In net/core/netpoll.c (ffffffff8197d5af)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/core/netpoll.c:__netpoll_setup
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:zap_completion_queue
```
```
In net/core/fib_rules.c (ffffffff81980b6e)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_default_rule_add
```
```
In net/core/devlink.c (ffffffff81997871)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_traps_register
  - net/core/devlink.c:devlink_health_reporter_create
```
```
In net/sched/sch_generic.c (ffffffff819a17ae)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_alloc
```
```
In net/sched/cls_api.c (ffffffff819ab76f)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tcf_block_get_ext
```
```
In net/sched/act_api.c (ffffffff819adac0)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_idr_create
  - net/sched/act_api.c:tcf_idr_create
```
```
In net/ipv4/route.c (ffffffff819bbd35)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_genid_init
  - net/ipv4/route.c:rt_genid_init
  - net/ipv4/route.c:rt_genid_init
```
```
In net/ipv4/inetpeer.c (ffffffff819c166c)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff819ce19c)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819cec25)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_hash_add
```
```
In net/ipv4/tcp.c (ffffffff819d0c78)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv4/tcp.c:skb_entail
```
```
In net/ipv4/tcp_input.c (ffffffff819d8c03)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/tcp_output.c (ffffffff819e6211)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819ecea1)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In net/ipv4/tcp_fastopen.c (ffffffff819f49ab)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/devinet.c (ffffffff81a07638)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_init
```
```
In net/ipv4/igmp.c (ffffffff81a0e62b)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv4/igmp.c:____ip_mc_inc_group
```
```
In net/ipv4/fib_semantics.c (ffffffff81a15105)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/ipv4/inet_fragment.c (ffffffff81a1b48f)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frags_init
```
```
In net/ipv4/metrics.c (ffffffff81a1efdc)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In net/ipv4/nexthop.c (ffffffff81a214fb)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81a21d3f)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:proc_tfo_blackhole_detect_timeout
```
```
In net/ipv4/ipmr.c (ffffffff81a285bf)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv4/syncookies.c (ffffffff81a2b56f)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:tcp_get_cookie_sock
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81a2ee1a)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a33172)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
```
```
In net/xfrm/xfrm_state.c (ffffffff81a3a2bf)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
```
```
In net/unix/af_unix.c (ffffffff81a46d0d)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
```
```
In net/ipv6/af_inet6.c (ffffffff81a4b667)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In net/ipv6/anycast.c (ffffffff81a4c3ab)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
```
```
In net/ipv6/addrconf.c (ffffffff81a5723d)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/route.c (ffffffff81a5f008)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_upper_bound_set
```
```
In net/ipv6/ip6_fib.c (ffffffff81a6c6d4)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_metric_set
  - net/ipv6/ip6_fib.c:fib6_info_alloc
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81a70450)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
```
```
In net/ipv6/mcast.c (ffffffff81a80cef)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
```
```
In net/ipv6/exthdrs.c (ffffffff81a8a328)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_dup_options
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81a8cdd0)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:fl_create
```
```
In net/ipv6/ip6mr.c (ffffffff81a923a6)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/ipv6/calipso.c (ffffffff81a9863c)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_doi_add
```
```
In net/packet/af_packet.c (ffffffff81aa7f44)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
```
```
In net/xdp/xdp_umem.c (ffffffff81ac4135)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_create
```
```
In lib/dump_stack.c (ffffffff81ac5c68)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - lib/dump_stack.c:dump_stack
```
```
In lib/klist.c (ffffffff81ac7872)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - lib/klist.c:klist_node_init
```
```
In lib/kobject.c (ffffffff81ac8dd6)
Location: arch/x86/include/asm/atomic.h:41
Inline: True
Inline callers:
  - lib/kobject.c:kset_register
  - lib/kobject.c:kobject_init
```
</details>
</li>
</ul>

## Differences
