# Function: <code>__cmpxchg_mb</code>

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
In virt/kvm/kvm_main.c (ffff8000100bc750)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - virt/kvm/kvm_main.c:kvm_make_vcpus_request_mask
```
```
In virt/kvm/arm/arm.c (ffff8000100c5d90)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - virt/kvm/arm/arm.c:kvm_arch_vcpu_should_kick
```
```
In virt/kvm/arm/vgic/vgic-mmio-v3.c (ffff8000100e44d4)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - virt/kvm/arm/vgic/vgic-mmio-v3.c:vgic_mmio_write_propbase
```
```
In kernel/fork.c (ffff8000100f1878)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - kernel/fork.c:get_mm_exe_file
```
```
In kernel/panic.c (ffff8000100f69d0)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - kernel/panic.c:panic
  - kernel/panic.c:nmi_panic
```
```
In kernel/exit.c (ffff8000100faf0c)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
```
```
In kernel/task_work.c (ffff800010124e50)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - kernel/task_work.c:task_work_run
  - kernel/task_work.c:task_work_cancel
  - kernel/task_work.c:task_work_add
```
```
In kernel/cred.c (ffff80001012cbbc)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
```
```
In kernel/smpboot.c (ffff80001012fca4)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - kernel/smpboot.c:cpu_report_death
  - kernel/smpboot.c:cpu_wait_death
```
```
In kernel/ucount.c (ffff800010130384)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - kernel/ucount.c:dec_ucount
  - kernel/ucount.c:inc_ucount
```
```
In kernel/kmod.c (ffff800010130780)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
```
```
In kernel/sched/fair.c (ffff800010142af8)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_work
```
```
In kernel/sched/psi.c (ffff80001016718c)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_poll_work
```
```
In kernel/locking/mutex.c (ffff800010168860)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
```
```
In kernel/locking/rwsem.c (ffff800010da53a8)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:down_read_killable
  - kernel/locking/rwsem.c:down_read
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
```
```
In kernel/locking/osq_lock.c (ffff80001016a63c)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_lock
```
```
In kernel/printk/printk_safe.c (ffff800010176a6c)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:__printk_safe_flush
  - kernel/printk/printk_safe.c:printk_safe_log_store
```
```
In kernel/irq/chip.c (ffff800010180130)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_chip_pm_get
```
```
In kernel/rcu/tree.c (ffff800010191050)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_eqs_special_set
```
```
In kernel/time/posix-cpu-timers.c (ffff8000101ad854)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
```
```
In kernel/module.c (ffff8000101c27c4)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - kernel/module.c:try_module_get
  - kernel/module.c:__arm64_sys_delete_module
```
```
In kernel/acct.c (ffff8000101c827c)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - kernel/acct.c:acct_process
  - kernel/acct.c:acct_pin_kill
```
```
In kernel/kexec_core.c (ffff8000101c99d0)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_kexec
```
```
In kernel/cgroup/cgroup.c (ffff8000101d8dc8)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/cgroup-v1.c (ffff8000101dca40)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In kernel/cgroup/legacy_freezer.c (ffff8000101de868)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (ffff8000101dfc10)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffff8000101e4b08)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
```
In kernel/debug/kdb/kdb_io.c (ffff8000101fce10)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
```
```
In kernel/debug/kdb/kdb_main.c (ffff800010200398)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_param_enable_nmi
```
```
In kernel/trace/ring_buffer.c (ffff800010218634)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:ring_buffer_record_on
  - kernel/trace/ring_buffer.c:ring_buffer_record_off
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
```
```
In kernel/trace/tracing_map.c (ffff80001022e1bc)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
```
```
In kernel/trace/trace_functions.c (ffff80001023006c)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
```
```
In kernel/trace/blktrace.c (ffff800010235db4)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_trace_setup_queue
  - kernel/trace/blktrace.c:__blk_trace_setup
```
```
In kernel/irq_work.c (ffff80001025afd0)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_claim
```
```
In kernel/bpf/syscall.c (ffff800010264460)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_inc_not_zero
```
```
In kernel/bpf/devmap.c (ffff80001028715c)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_notification
```
```
In kernel/events/core.c (ffff800010297658)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_swevent_set_period
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:free_event
  - kernel/events/core.c:_free_event
```
```
In kernel/events/ring_buffer.c (ffff8000102a2730)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
```
```
In kernel/events/uprobes.c (ffff8000102a6514)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - kernel/events/uprobes.c:register_for_each_vma
```
```
In kernel/jump_label.c (ffff8000102ab290)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - kernel/jump_label.c:static_key_disable_cpuslocked
```
```
In mm/filemap.c (ffff8000102afe1c)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:find_get_entry
```
```
In mm/oom_kill.c (ffff8000102b7190)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - mm/oom_kill.c:mark_oom_victim
```
```
In mm/page-writeback.c (ffff8000102bc78c)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/swap.c (ffff8000102c2d88)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - mm/swap.c:deactivate_file_page
```
```
In mm/vmscan.c (ffff8000102c9b9c)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - mm/vmscan.c:__isolate_lru_page
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
```
```
In mm/mmzone.c (ffff8000102d95e4)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - mm/mmzone.c:page_cpupid_xchg_last
```
```
In mm/backing-dev.c (ffff8000102de4d4)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
```
```
In mm/gup.c (ffff8000102f119c)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
```
```
In mm/mmap.c (ffff8000103036b4)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
```
```
In mm/rmap.c (ffff80001030b00c)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_get_anon_vma
```
```
In mm/page_alloc.c (ffff800010314f30)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - mm/page_alloc.c:set_pfnblock_flags_mask
```
```
In mm/swapfile.c (ffff8000103265ec)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/frontswap.c (ffff80001032a650)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - mm/frontswap.c:frontswap_register_ops
```
```
In mm/hugetlb.c (ffff800010335fe4)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - mm/hugetlb.c:isolate_huge_page
```
```
In mm/ksm.c (ffff800010342384)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - mm/ksm.c:reuse_ksm_page
  - mm/ksm.c:get_ksm_page
```
```
In mm/slub.c (ffff800010345b8c)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - mm/slub.c:alloc_slab_page
```
```
In mm/migrate.c (ffff800010352f14)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (ffff800010359b34)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
```
In mm/khugepaged.c (ffff80001035d854)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In mm/memcontrol.c (ffff800010363f90)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:__invalidate_reclaim_iterators
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:percpu_ref_tryget_live
```
```
In mm/hugetlb_cgroup.c (ffff80001036d75c)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In mm/memory-failure.c (ffff80001036e4e0)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - mm/memory-failure.c:get_hwpoison_page
```
```
In mm/cleancache.c (ffff8000103714d8)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - mm/cleancache.c:cleancache_register_ops
```
```
In mm/page_idle.c (ffff800010379124)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/hmm.c (ffff80001037b0f8)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - mm/hmm.c:hmm_range_register
```
```
In mm/memfd.c (ffff80001037c578)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
```
```
In fs/open.c (ffff80001037dd38)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/super.c (ffff800010386f5c)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - fs/super.c:grab_super
```
```
In fs/exec.c (ffff80001038f1dc)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - fs/exec.c:set_dumpable
  - fs/exec.c:kernel_read_file
  - fs/exec.c:do_open_execat
```
```
In fs/namei.c (ffff8000103982bc)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - fs/namei.c:do_last
```
```
In fs/dcache.c (ffff8000103a8c2c)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:__d_move
  - fs/dcache.c:d_add
```
```
In fs/inode.c (ffff8000103ac60c)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - fs/inode.c:inode_set_flags
  - fs/inode.c:generic_update_time
```
```
In fs/file.c (ffff8000103b0d90)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - fs/file.c:__fget
```
```
In fs/fs-writeback.c (ffff8000103cab24)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/nsfs.c (ffff8000103d4668)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
```
```
In fs/buffer.c (ffff8000103d9c5c)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - fs/buffer.c:block_invalidatepage
```
```
In fs/direct-io.c (ffff8000103e3e74)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - fs/direct-io.c:sb_init_dio_done_wq
```
```
In fs/notify/mark.c (ffff8000103e98ac)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_list
```
```
In fs/eventpoll.c (ffff8000103f1684)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll_callback
  - fs/eventpoll.c:ep_poll_callback
```
```
In fs/userfaultfd.c (ffff8000103f8910)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
```
```
In fs/aio.c (ffff8000103fbfec)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - fs/aio.c:lookup_ioctx
  - fs/aio.c:__get_reqs_available
```
```
In fs/io_uring.c (ffff800010405d78)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - fs/io_uring.c:__arm64_sys_io_uring_enter
  - fs/io_uring.c:io_account_mem
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/io_uring.c:io_get_req
```
```
In fs/crypto/keysetup.c (ffff80001040eb2c)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:setup_per_mode_key
  - fs/crypto/keysetup.c:derive_essiv_salt
```
```
In fs/verity/enable.c (ffff800010411a40)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - fs/verity/enable.c:fsverity_ioctl_enable
```
```
In fs/verity/hash_algs.c (ffff800010411c44)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
```
```
In fs/verity/open.c (ffff800010412ea0)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
```
```
In fs/locks.c (ffff800010416188)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - fs/locks.c:locks_get_lock_context
```
```
In fs/posix_acl.c (ffff8000104269b0)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
```
```
In fs/iomap/direct-io.c (ffff80001042d30c)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
```
```
In fs/proc/task_mmu.c (ffff80001043a5f8)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/inode.c (ffff80001043b7ec)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_get_link
  - fs/proc/inode.c:proc_reg_open
  - fs/proc/inode.c:proc_reg_get_unmapped_area
  - fs/proc/inode.c:proc_reg_mmap
  - fs/proc/inode.c:proc_reg_compat_ioctl
  - fs/proc/inode.c:proc_reg_unlocked_ioctl
  - fs/proc/inode.c:proc_reg_poll
  - fs/proc/inode.c:proc_reg_write
  - fs/proc/inode.c:proc_reg_read
  - fs/proc/inode.c:proc_reg_llseek
```
```
In fs/proc/base.c (ffff800010440560)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - fs/proc/base.c:environ_read
```
```
In fs/proc/proc_sysctl.c (ffff80001044aa4c)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:drop_sysctl_table
```
```
In fs/kernfs/dir.c (ffff8000104530d0)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rmdir
  - fs/kernfs/dir.c:kernfs_iop_mkdir
  - fs/kernfs/dir.c:kernfs_find_and_get_node_by_ino
```
```
In fs/ext4/balloc.c (ffff800010460a30)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/dir.c (ffff8000104627c0)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/ialloc.c (ffff800010473dbc)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
```
```
In fs/ext4/inline.c (ffff80001047bab8)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
```
```
In fs/ext4/inode.c (ffff800010488e3c)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_update_bh_state
```
```
In fs/ext4/mballoc.c (ffff800010495388)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_process_freed_data
```
```
In fs/ext4/namei.c (ffff8000104a06c8)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:add_dirent_to_buf
```
```
In fs/ext4/super.c (ffff8000104bd040)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_grp_locked_error
```
```
In fs/fat/dir.c (ffff8000104e5d04)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_remove_entries
```
```
In fs/fat/inode.c (ffff8000104ed74c)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_inode
```
```
In fs/fat/misc.c (ffff8000104eee78)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
```
```
In fs/fat/namei_vfat.c (ffff8000104f19cc)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_unlink
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_lookup
```
```
In fs/fuse/dir.c (ffff8000105096d8)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_dir_changed
  - fs/fuse/dir.c:fuse_dir_changed
```
```
In fs/fuse/readdir.c (ffff800010515444)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
```
```
In fs/debugfs/file.c (ffff800010517054)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_file_get
```
```
In security/integrity/ima/ima_api.c (ffff8000105b0a40)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_collect_measurement
```
```
In block/bio.c (ffff8000105dd8b0)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - block/bio.c:update_io_ticks
```
```
In block/blk-core.c (ffff8000105e43a4)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-mq.c (ffff8000105f0628)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_timeout_work
```
```
In block/blk-mq-tag.c (ffff8000105f49a4)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-tag.c:blk_mq_get_tag
```
```
In block/blk-rq-qos.c (ffff800010607210)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - block/blk-rq-qos.c:rq_wait_inc_below
```
```
In block/blk-cgroup.c (ffff80001060e9f4)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkcg_scale_delay
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-iocost.c (ffff8000106154f0)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - block/blk-iocost.c:iocg_kick_delay
```
```
In lib/llist.c (ffff8000106338e4)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - lib/llist.c:llist_del_first
  - lib/llist.c:llist_add_batch
```
```
In lib/rhashtable.c (ffff800010636e94)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
```
```
In lib/errseq.c (ffff800010638188)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - lib/errseq.c:errseq_check_and_advance
  - lib/errseq.c:errseq_set
```
```
In lib/genalloc.c (ffff800010644334)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - lib/genalloc.c:clear_bits_ll
  - lib/genalloc.c:set_bits_ll
```
```
In lib/sbitmap.c (ffff80001066a318)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbq_wake_up
  - lib/sbitmap.c:__sbq_wake_up
```
```
In drivers/irqchip/irq-mvebu-icu.c (ffff800010679828)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - drivers/irqchip/irq-mvebu-icu.c:mvebu_icu_write_msg
```
```
In drivers/phy/phy-core.c (ffff8000106879d8)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_get
```
```
In drivers/pci/pci-driver.c (ffff8000106ec548)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_remove
```
```
In drivers/rapidio/rio.c (ffff80001073cdc0)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_unregister_mport
```
```
In drivers/acpi/apei/ghes.c (ffff8000107b0034)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
```
```
In drivers/amba/bus.c (ffff8000107b9550)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - drivers/amba/bus.c:amba_remove
  - drivers/amba/bus.c:amba_remove
  - drivers/amba/bus.c:amba_probe
```
```
In drivers/xen/grant-table.c (ffff80001082c38c)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_end_foreign_access_ref_v1
```
```
In drivers/xen/events/events_fifo.c (ffff800010833e7c)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:__evtchn_fifo_handle_events
```
```
In drivers/tty/tty_ldsem.c (ffff80001085f690)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_write_trylock
  - drivers/tty/tty_ldsem.c:ldsem_down_write
  - drivers/tty/tty_ldsem.c:ldsem_down_write
  - drivers/tty/tty_ldsem.c:ldsem_down_read_trylock
  - drivers/tty/tty_ldsem.c:ldsem_down_read
```
```
In drivers/tty/tty_audit.c (ffff8000108637ac)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_add_data
```
```
In drivers/tty/hvc/hvc_console.c (ffff800010879c68)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
```
```
In drivers/tty/serial/serial_core.c (ffff80001087e2a4)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_poll_put_char
  - drivers/tty/serial/serial_core.c:uart_poll_get_char
  - drivers/tty/serial/serial_core.c:uart_dtr_rts
  - drivers/tty/serial/serial_core.c:uart_carrier_raised
  - drivers/tty/serial/serial_core.c:uart_wait_until_sent
  - drivers/tty/serial/serial_core.c:uart_get_icount
  - drivers/tty/serial/serial_core.c:uart_wait_modem_status
  - drivers/tty/serial/serial_core.c:uart_unthrottle
  - drivers/tty/serial/serial_core.c:uart_throttle
  - drivers/tty/serial/serial_core.c:uart_send_xchar
  - drivers/tty/serial/serial_core.c:uart_flush_buffer
  - drivers/tty/serial/serial_core.c:uart_chars_in_buffer
  - drivers/tty/serial/serial_core.c:uart_write_room
  - drivers/tty/serial/serial_core.c:uart_write
  - drivers/tty/serial/serial_core.c:uart_put_char
  - drivers/tty/serial/serial_core.c:uart_shutdown
  - drivers/tty/serial/serial_core.c:uart_start
  - drivers/tty/serial/serial_core.c:uart_stop
```
```
In drivers/tty/serial/8250/8250_dw.c (ffff8000108915fc)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dw.c:dw8250_remove
```
```
In drivers/tty/serial/8250/8250_mtk.c (ffff800010892d84)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_remove
```
```
In drivers/tty/serdev/core.c (ffff8000108a9ff8)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_device_open
```
```
In drivers/char/random.c (ffff8000108b0034)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - drivers/char/random.c:do_numa_crng_init
  - drivers/char/random.c:credit_entropy_bits
```
```
In drivers/iommu/iova.c (ffff8000108cdc90)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - drivers/iommu/iova.c:queue_iova
```
```
In drivers/base/core.c (ffff8000108e6618)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/power/runtime.c (ffff8000108fe0dc)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_clean_up_links
  - drivers/base/power/runtime.c:__pm_runtime_disable
  - drivers/base/power/runtime.c:pm_runtime_barrier
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:pm_runtime_get_if_in_use
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_get_suppliers
```
```
In drivers/base/power/wakeup.c (ffff80001090508c)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:pm_system_cancel_wakeup
```
```
In drivers/dma-buf/dma-fence-array.c (ffff800010968050)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_cb_func
  - drivers/dma-buf/dma-fence-array.c:irq_dma_fence_array_work
```
```
In drivers/dma-buf/dma-fence-chain.c (ffff80001096863c)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
```
```
In drivers/scsi/hosts.c (ffff80001096fb88)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/spi/spi.c (ffff8000109c9600)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_pump_messages
```
```
In drivers/spi/spi-omap2-mcspi.c (ffff8000109cdac4)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_probe
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_setup
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_set_cs
```
```
In drivers/net/loopback.c (ffff8000109d0274)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In drivers/net/ethernet/freescale/fec_main.c (ffff8000109e67d0)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_main.c:fec_drv_remove
  - drivers/net/ethernet/freescale/fec_main.c:fec_probe
```
```
In drivers/cdrom/cdrom.c (ffff800010a10194)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
```
```
In drivers/usb/core/hcd.c (ffff800010a1c368)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_end_port_resume
```
```
In drivers/usb/core/driver.c (ffff800010a2593c)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
```
```
In drivers/usb/core/hcd-pci.c (ffff800010a3714c)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
```
In drivers/usb/host/xhci-pci.c (ffff800010a90f3c)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffff800010aba204)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffff800010aba66c)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
```
```
In drivers/i2c/busses/i2c-sprd.c (ffff800010abca64)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-sprd.c:sprd_i2c_remove
  - drivers/i2c/busses/i2c-sprd.c:sprd_i2c_probe
```
```
In drivers/thermal/thermal_core.c (ffff800010ad5840)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:__thermal_cooling_device_register
```
```
In drivers/md/md.c (ffff800010ae8d60)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - drivers/md/md.c:rdev_set_badblocks
  - drivers/md/md.c:md_do_sync
```
```
In drivers/md/dm.c (ffff800010b014f4)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm.c:dm_get_numa_node
```
```
In drivers/cpufreq/cpufreq_governor.c (ffff800010b25c04)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:dbs_update_util_handler
```
```
In drivers/mmc/core/sdio.c (ffff800010b3a414)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
```
```
In drivers/mmc/core/sdio_bus.c (ffff800010b3b224)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
```
In drivers/mmc/core/block.c (ffff800010b41750)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - drivers/mmc/core/block.c:mmc_blk_remove
```
```
In drivers/firmware/efi/efi.c (ffff800010d9f338)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffff800010b7e9ec)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request
```
```
In drivers/perf/arm-cci.c (ffff800010b91ba4)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - drivers/perf/arm-cci.c:cci_pmu_event_init
  - drivers/perf/arm-cci.c:pmu_event_update
```
```
In drivers/perf/arm_pmu.c (ffff800010b94fdc)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - drivers/perf/arm_pmu.c:armpmu_event_update
```
```
In drivers/perf/hisilicon/hisi_uncore_pmu.c (ffff800010b965fc)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - drivers/perf/hisilicon/hisi_uncore_pmu.c:hisi_uncore_pmu_event_update
```
```
In drivers/perf/qcom_l2_pmu.c (ffff800010b98e4c)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - drivers/perf/qcom_l2_pmu.c:l2_cache_event_update
```
```
In drivers/perf/qcom_l3_pmu.c (ffff800010b9a6a0)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - drivers/perf/qcom_l3_pmu.c:qcom_l3_cache__32bit_counter_update
  - drivers/perf/qcom_l3_pmu.c:qcom_l3_cache__64bit_counter_update
```
```
In drivers/perf/xgene_pmu.c (ffff800010b9c09c)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - drivers/perf/xgene_pmu.c:xgene_perf_event_update
```
```
In net/core/sock.c (ffff800010bae7fc)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sk_dst_check
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffff800010bb47a4)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - net/core/skbuff.c:__copy_skb_header
  - net/core/skbuff.c:skb_dump
```
```
In net/core/dev.c (ffff800010bd4350)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:napi_complete_done
  - net/core/dev.c:napi_schedule_prep
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/dst.c (ffff800010be08bc)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - net/core/dst.c:__dst_destroy_metrics_generic
  - net/core/dst.c:dst_cow_metrics_generic
```
```
In net/core/neighbour.c (ffff800010be7620)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/core/filter.c (ffff800010bfdef4)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - net/core/filter.c:bpf_setsockopt
  - net/core/filter.c:bpf_get_skb_set_tunnel_proto
  - net/core/filter.c:bpf_skb_set_tunnel_key
  - net/core/filter.c:bpf_clear_redirect_map
```
```
In net/core/sock_diag.c (ffff800010c03c60)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_gen_cookie
```
```
In net/core/netpoll.c (ffff800010c11020)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_poll_dev
```
```
In net/core/lwtunnel.c (ffff800010c1df84)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - net/core/lwtunnel.c:lwtunnel_encap_del_ops
  - net/core/lwtunnel.c:lwtunnel_encap_add_ops
```
```
In net/core/dst_cache.c (ffff800010c2215c)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - net/core/dst_cache.c:dst_cache_set_ip6
  - net/core/dst_cache.c:dst_cache_set_ip4
```
```
In net/core/bpf_sk_storage.c (ffff800010c31abc)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:sk_storage_alloc
```
```
In net/netfilter/nf_queue.c (ffff800010c55e04)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue
```
```
In net/ipv4/route.c (ffff800010c5bf9c)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:rt_cache_route
  - net/ipv4/route.c:rt_cache_route
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ip_idents_reserve
  - net/ipv4/route.c:ip_idents_reserve
```
```
In net/ipv4/protocol.c (ffff800010c5dddc)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - net/ipv4/protocol.c:inet_del_offload
  - net/ipv4/protocol.c:inet_del_protocol
  - net/ipv4/protocol.c:inet_add_offload
  - net/ipv4/protocol.c:inet_add_protocol
```
```
In net/ipv4/ip_options.c (ffff800010c60ef4)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/ip_output.c (ffff800010c6236c)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/ip_sockglue.c (ffff800010c66870)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
```
```
In net/ipv4/tcp.c (ffff800010c704cc)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
```
```
In net/ipv4/tcp_output.c (ffff800010c829a4)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_wfree
  - net/ipv4/tcp_output.c:tcp_release_cb
```
```
In net/ipv4/tcp_ipv4.c (ffff800010c8bb34)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:inet_sk_rx_dst_set
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_minisocks.c (ffff800010c8f97c)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/tcp_fastopen.c (ffff800010c940ec)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
```
```
In net/ipv4/udp.c (ffff800010c9e31c)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/arp.c (ffff800010ca1a98)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
```
```
In net/ipv4/icmp.c (ffff800010ca3d48)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
```
```
In net/ipv4/ipmr.c (ffff800010ccb4a4)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/xfrm/xfrm_policy.c (ffff800010ce0f64)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/xfrm/xfrm_input.c (ffff800010ceb0e4)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffff800010cec08c)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/ipv6/ip6_output.c (ffff800010cfc5ec)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/route.c (ffff800010d11208)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_create_rt_rcu
```
```
In net/ipv6/ip6_fib.c (ffff800010d18e98)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_new_sernum
```
```
In net/ipv6/tcp_ipv6.c (ffff800010d371bc)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
```
```
In net/ipv6/ip6_flowlabel.c (ffff800010d3fc90)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup
  - net/ipv6/ip6_flowlabel.c:fl_lookup
```
```
In net/ipv6/ip6mr.c (ffff800010d43e3c)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/fib6_rules.c (ffff800010d4b198)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
```
```
In net/ipv6/seg6_local.c (ffff800010d50e24)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
```
```
In net/ipv6/ip6_icmp.c (ffff800010d53b30)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - net/ipv6/ip6_icmp.c:inet6_unregister_icmp_sender
  - net/ipv6/ip6_icmp.c:inet6_register_icmp_sender
```
```
In net/ipv6/protocol.c (ffff800010d54314)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - net/ipv6/protocol.c:inet6_del_offload
  - net/ipv6/protocol.c:inet6_add_offload
  - net/ipv6/protocol.c:inet6_del_protocol
  - net/ipv6/protocol.c:inet6_add_protocol
```
```
In net/xdp/xdp_umem.c (ffff800010d813b8)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_create
```
```
In lib/dec_and_lock.c (ffff800010d84730)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
```
```
In lib/dump_stack.c (ffff800010d84b88)
Location: arch/arm64/include/asm/cmpxchg.h:175
Inline: True
Inline callers:
  - lib/dump_stack.c:dump_stack
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
