# Function: <code>__cmpxchg_case_mb_32</code>

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
<summary>In <code>arm64</code>: Duplicate, Selective Inline ⚠️</summary>

```c
u32 __cmpxchg_case_mb_32(volatile void *ptr, u32 old, u32 new);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In virt/kvm/kvm_main.c (ffff8000100bc750)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: True
Inline callers:
  - virt/kvm/kvm_main.c:kvm_make_vcpus_request_mask
```
```
In virt/kvm/arm/arm.c (ffff8000100c5d90)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: True
Inline callers:
  - virt/kvm/arm/arm.c:kvm_arch_vcpu_should_kick
```
```
In virt/kvm/arm/vgic/vgic-mmio-v3.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: False
```
```
In kernel/fork.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: False
```
```
In kernel/panic.c (ffff8000100f69d0)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: True
Inline callers:
  - kernel/panic.c:panic
  - kernel/panic.c:nmi_panic
```
```
In kernel/exit.c (ffff8000100faf0c)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
```
```
In kernel/task_work.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: False
```
```
In kernel/cred.c (ffff80001012cbc0)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: True
```
```
In kernel/smpboot.c (ffff80001012fca4)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: True
Inline callers:
  - kernel/smpboot.c:cpu_report_death
  - kernel/smpboot.c:cpu_wait_death
```
```
In kernel/ucount.c (ffff800010130384)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: True
Inline callers:
  - kernel/ucount.c:dec_ucount
  - kernel/ucount.c:inc_ucount
```
```
In kernel/kmod.c (ffff800010130780)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: True
Inline callers:
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
```
```
In kernel/sched/fair.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: False
```
```
In kernel/sched/psi.c (ffff80001016718c)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_poll_work
  - kernel/sched/psi.c:psi_poll_work
```
```
In kernel/locking/mutex.c (ffff800010168864)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: True
```
```
In kernel/locking/rwsem.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: False
```
```
In kernel/locking/osq_lock.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: False
```
```
In kernel/printk/printk_safe.c (ffff800010176a6c)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:__printk_safe_flush
  - kernel/printk/printk_safe.c:printk_safe_log_store
```
```
In kernel/irq/chip.c (ffff800010180134)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_chip_pm_get
```
```
In kernel/rcu/tree.c (ffff80001019095c)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_eqs_special_set
  - kernel/rcu/tree.c:rcu_eqs_special_set
```
```
In kernel/time/posix-cpu-timers.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: False
```
```
In kernel/module.c (ffff8000101c27c8)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: True
Inline callers:
  - kernel/module.c:try_module_get
  - kernel/module.c:__arm64_sys_delete_module
```
```
In kernel/acct.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: False
```
```
In kernel/kexec_core.c (ffff8000101c99d4)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_kexec
```
```
In kernel/cgroup/cgroup.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: False
```
```
In kernel/cgroup/cgroup-v1.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: False
```
```
In kernel/cgroup/legacy_freezer.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: False
```
```
In kernel/cgroup/rdma.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: False
```
```
In kernel/cgroup/cpuset.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: False
```
```
In kernel/debug/kdb/kdb_io.c (ffff8000101fce10)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
```
```
In kernel/debug/kdb/kdb_main.c (ffff80001020039c)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_param_enable_nmi
```
```
In kernel/trace/ring_buffer.c (ffff8000102176c4)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_record_on
  - kernel/trace/ring_buffer.c:ring_buffer_record_on
  - kernel/trace/ring_buffer.c:ring_buffer_record_off
  - kernel/trace/ring_buffer.c:ring_buffer_record_off
```
```
In kernel/trace/tracing_map.c (ffff80001022e1bc)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: True
```
```
In kernel/trace/trace_functions.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: False
```
```
In kernel/trace/blktrace.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: False
```
```
In kernel/irq_work.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: False
```
```
In kernel/bpf/syscall.c (ffff800010264464)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_inc_not_zero
```
```
In kernel/bpf/devmap.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: False
```
```
In kernel/events/core.c (ffff8000102979dc)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:_free_event
Direct callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
```
```
In kernel/events/ring_buffer.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: False
```
```
In kernel/events/uprobes.c (ffff8000102a6518)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: True
Inline callers:
  - kernel/events/uprobes.c:register_for_each_vma
```
```
In kernel/jump_label.c (ffff8000102ab290)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: True
Inline callers:
  - kernel/jump_label.c:static_key_disable_cpuslocked
```
```
In mm/filemap.c (ffff8000102afe20)
Location: arch/arm64/include/asm/cmpxchg.h:129
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
In mm/oom_kill.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: False
```
```
In mm/page-writeback.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: False
```
```
In mm/swap.c (ffff8000102c2d8c)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: True
Inline callers:
  - mm/swap.c:deactivate_file_page
```
```
In mm/vmscan.c (ffff8000102c9ba0)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: True
Inline callers:
  - mm/vmscan.c:__isolate_lru_page
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
```
```
In mm/mmzone.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: False
```
```
In mm/backing-dev.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: False
```
```
In mm/gup.c (ffff8000102f11a0)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
```
```
In mm/mmap.c (ffff8000103036bc)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
```
```
In mm/rmap.c (ffff80001030b010)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: True
Inline callers:
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_get_anon_vma
```
```
In mm/page_alloc.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: False
```
```
In mm/swapfile.c (ffff8000103265f0)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/frontswap.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: False
```
```
In mm/hugetlb.c (ffff800010335fe8)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: True
Inline callers:
  - mm/hugetlb.c:isolate_huge_page
```
```
In mm/ksm.c (ffff800010342384)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: True
Inline callers:
  - mm/ksm.c:reuse_ksm_page
  - mm/ksm.c:get_ksm_page
```
```
In mm/slub.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: False
```
```
In mm/migrate.c (ffff800010352f14)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:isolate_movable_page
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (ffff800010359b38)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
```
In mm/khugepaged.c (ffff80001035d854)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In mm/memcontrol.c (ffff800010363f98)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/hugetlb_cgroup.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: False
```
```
In mm/memory-failure.c (ffff80001036e4e4)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: True
Inline callers:
  - mm/memory-failure.c:get_hwpoison_page
```
```
In mm/cleancache.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: False
```
```
In mm/page_idle.c (ffff800010379128)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/hmm.c (ffff80001037b0fc)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: True
Inline callers:
  - mm/hmm.c:hmm_range_register
```
```
In mm/memfd.c (ffff80001037c584)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
```
```
In fs/open.c (ffff80001037dd40)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/super.c (ffff800010386f60)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: True
Inline callers:
  - fs/super.c:grab_super
```
```
In fs/exec.c (ffff80001038c850)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: True
Inline callers:
  - fs/exec.c:kernel_read_file
  - fs/exec.c:kernel_read_file
  - fs/exec.c:do_open_execat
  - fs/exec.c:do_open_execat
```
```
In fs/namei.c (ffff8000103982c0)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: True
Inline callers:
  - fs/namei.c:do_last
```
```
In fs/dcache.c (ffff8000103a8c2c)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:__d_move
  - fs/dcache.c:d_add
```
```
In fs/inode.c (ffff8000103ac60c)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: True
Inline callers:
  - fs/inode.c:inode_set_flags
```
```
In fs/file.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: False
```
```
In fs/fs-writeback.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: False
```
```
In fs/nsfs.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: False
```
```
In fs/buffer.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: False
```
```
In fs/direct-io.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: False
```
```
In fs/notify/mark.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: False
```
```
In fs/eventpoll.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: False
```
```
In fs/userfaultfd.c (ffff8000103f8914)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
```
```
In fs/aio.c (ffff8000103fab7c)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: True
Inline callers:
  - fs/aio.c:__get_reqs_available
```
```
In fs/io_uring.c (ffff800010406320)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: True
Inline callers:
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_wq_submit_work
```
```
In fs/crypto/keysetup.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: False
```
```
In fs/verity/enable.c (ffff800010411a44)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: True
Inline callers:
  - fs/verity/enable.c:fsverity_ioctl_enable
```
```
In fs/verity/hash_algs.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: False
```
```
In fs/verity/open.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: False
```
```
In fs/locks.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: False
```
```
In fs/posix_acl.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: False
```
```
In fs/iomap/direct-io.c (ffff80001042d30c)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
```
```
In fs/proc/task_mmu.c (ffff80001043a5fc)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/inode.c (ffff80001043b7f4)
Location: arch/arm64/include/asm/cmpxchg.h:129
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
In fs/proc/base.c (ffff800010440564)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: True
Inline callers:
  - fs/proc/base.c:environ_read
```
```
In fs/proc/proc_sysctl.c (ffff80001044aa50)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:drop_sysctl_table
```
```
In fs/kernfs/dir.c (ffff8000104530d8)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rmdir
  - fs/kernfs/dir.c:kernfs_iop_mkdir
  - fs/kernfs/dir.c:kernfs_find_and_get_node_by_ino
```
```
In fs/ext4/balloc.c (ffff800010460a34)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/dir.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: False
```
```
In fs/ext4/ialloc.c (ffff800010473dc0)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: True
```
```
In fs/ext4/inline.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: False
```
```
In fs/ext4/inode.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: False
```
```
In fs/ext4/mballoc.c (ffff80001049538c)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_process_freed_data
```
```
In fs/ext4/namei.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: False
```
```
In fs/ext4/super.c (ffff8000104bd044)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_grp_locked_error
```
```
In fs/fat/dir.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: False
```
```
In fs/fat/inode.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: False
```
```
In fs/fat/misc.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: False
```
```
In fs/fat/namei_vfat.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: False
```
```
In fs/fuse/dir.c (ffff8000105096d8)
Location: arch/arm64/include/asm/cmpxchg.h:129
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
```
```
In fs/fuse/readdir.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: False
```
```
In fs/debugfs/file.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: False
```
```
In security/integrity/ima/ima_api.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: False
```
```
In block/bio.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: False
```
```
In block/blk-core.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: False
```
```
In block/blk-mq.c (ffff8000105f0628)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
```
In block/blk-mq-tag.c (ffff8000105f45cc)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-tag.c:blk_mq_get_tag
```
```
In block/blk-rq-qos.c (ffff800010607214)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: True
Inline callers:
  - block/blk-rq-qos.c:rq_wait_inc_below
```
```
In block/blk-cgroup.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: False
```
```
In block/blk-iocost.c (ffff8000106154f0)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: True
Inline callers:
  - block/blk-iocost.c:iocg_kick_delay
```
```
In lib/llist.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: False
```
```
In lib/rhashtable.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: False
```
```
In lib/errseq.c (ffff800010638188)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: True
Inline callers:
  - lib/errseq.c:errseq_check_and_advance
  - lib/errseq.c:errseq_check_and_advance
  - lib/errseq.c:errseq_set
  - lib/errseq.c:errseq_set
```
```
In lib/genalloc.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: False
```
```
In lib/sbitmap.c (ffff80001066a318)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbq_wake_up
  - lib/sbitmap.c:__sbq_wake_up
  - lib/sbitmap.c:__sbq_wake_up
  - lib/sbitmap.c:__sbq_wake_up
```
```
In drivers/irqchip/irq-mvebu-icu.c (ffff800010679828)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: True
Inline callers:
  - drivers/irqchip/irq-mvebu-icu.c:mvebu_icu_write_msg
  - drivers/irqchip/irq-mvebu-icu.c:mvebu_icu_write_msg
```
```
In drivers/phy/phy-core.c (ffff8000106879dc)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_get
```
```
In drivers/pci/pci-driver.c (ffff8000106ec54c)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_remove
```
```
In drivers/rapidio/rio.c (ffff80001073cdc0)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_unregister_mport
```
```
In drivers/acpi/apei/ghes.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: False
```
```
In drivers/amba/bus.c (ffff8000107b9554)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: True
Inline callers:
  - drivers/amba/bus.c:amba_remove
  - drivers/amba/bus.c:amba_remove
  - drivers/amba/bus.c:amba_probe
```
```
In drivers/xen/grant-table.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: False
```
```
In drivers/xen/events/events_fifo.c (ffff800010833e7c)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:__evtchn_fifo_handle_events
  - drivers/xen/events/events_fifo.c:__evtchn_fifo_handle_events
```
```
In drivers/tty/tty_ldsem.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: False
```
```
In drivers/tty/tty_audit.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: False
```
```
In drivers/tty/hvc/hvc_console.c (ffff800010879c6c)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
```
```
In drivers/tty/serial/serial_core.c (ffff80001087e2a8)
Location: arch/arm64/include/asm/cmpxchg.h:129
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
In drivers/tty/serial/8250/8250_dw.c (ffff800010891600)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dw.c:dw8250_remove
```
```
In drivers/tty/serial/8250/8250_mtk.c (ffff800010892d88)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_remove
```
```
In drivers/tty/serdev/core.c (ffff8000108a9ffc)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_device_open
```
```
In drivers/char/random.c (ffff8000108aeb64)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: True
Inline callers:
  - drivers/char/random.c:credit_entropy_bits
```
```
In drivers/iommu/iova.c (ffff8000108cdc90)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: True
Inline callers:
  - drivers/iommu/iova.c:queue_iova
```
```
In drivers/base/core.c (ffff8000108e661c)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/power/runtime.c (ffff8000108fe0e0)
Location: arch/arm64/include/asm/cmpxchg.h:129
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
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:pm_system_cancel_wakeup
```
```
In drivers/dma-buf/dma-fence-array.c (ffff800010968050)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_cb_func
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_cb_func
  - drivers/dma-buf/dma-fence-array.c:irq_dma_fence_array_work
  - drivers/dma-buf/dma-fence-array.c:irq_dma_fence_array_work
```
```
In drivers/dma-buf/dma-fence-chain.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: False
```
```
In drivers/scsi/hosts.c (ffff80001096fb8c)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/spi/spi.c (ffff8000109c9604)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_pump_messages
```
```
In drivers/spi/spi-omap2-mcspi.c (ffff8000109cdac8)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: True
Inline callers:
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_probe
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_setup
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_set_cs
```
```
In drivers/net/loopback.c (ffff8000109d0278)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In drivers/net/ethernet/freescale/fec_main.c (ffff8000109e67d4)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_main.c:fec_drv_remove
  - drivers/net/ethernet/freescale/fec_main.c:fec_probe
```
```
In drivers/cdrom/cdrom.c (ffff800010a10198)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: True
```
```
In drivers/usb/core/hcd.c (ffff800010a1c36c)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_end_port_resume
```
```
In drivers/usb/core/driver.c (ffff800010a25940)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
```
```
In drivers/usb/core/hcd-pci.c (ffff800010a37150)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
```
In drivers/usb/host/xhci-pci.c (ffff800010a90f40)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: True
Inline callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffff800010aba208)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffff800010aba670)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: True
```
```
In drivers/i2c/busses/i2c-sprd.c (ffff800010abca68)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-sprd.c:sprd_i2c_remove
  - drivers/i2c/busses/i2c-sprd.c:sprd_i2c_probe
```
```
In drivers/thermal/thermal_core.c (ffff800010ad5840)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:__thermal_cooling_device_register
```
```
In drivers/md/md.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: False
```
```
In drivers/md/dm.c (ffff800010b014f4)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm.c:dm_get_numa_node
  - drivers/md/dm.c:dm_get_numa_node
```
```
In drivers/cpufreq/cpufreq_governor.c (ffff800010b25c08)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:dbs_update_util_handler
```
```
In drivers/mmc/core/sdio.c (ffff800010b3a418)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: True
```
```
In drivers/mmc/core/sdio_bus.c (ffff800010b3b228)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
```
In drivers/mmc/core/block.c (ffff800010b41754)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: True
Inline callers:
  - drivers/mmc/core/block.c:mmc_blk_remove
```
```
In drivers/firmware/efi/efi.c (ffff800010d9f33c)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffff800010b7e9f0)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request
```
```
In drivers/perf/arm-cci.c (ffff800010b91ba8)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: True
Inline callers:
  - drivers/perf/arm-cci.c:cci_pmu_event_init
```
```
In drivers/perf/arm_pmu.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: False
```
```
In drivers/perf/hisilicon/hisi_uncore_pmu.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: False
```
```
In drivers/perf/qcom_l2_pmu.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: False
```
```
In drivers/perf/qcom_l3_pmu.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: False
```
```
In drivers/perf/xgene_pmu.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: False
```
```
In net/core/sock.c (ffff800010bae7fc)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: True
Inline callers:
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sk_dst_check
  - net/core/sock.c:sk_dst_check
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffff800010bb47a8)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: True
Inline callers:
  - net/core/skbuff.c:__copy_skb_header
  - net/core/skbuff.c:skb_dump
```
```
In net/core/dev.c (ffff800010bd4350)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:dev_fill_metadata_dst
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/dst.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: False
```
```
In net/core/neighbour.c (ffff800010be7624)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/core/filter.c (ffff800010bfdef4)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: True
Inline callers:
  - net/core/filter.c:bpf_setsockopt
  - net/core/filter.c:bpf_setsockopt
  - net/core/filter.c:bpf_skb_set_tunnel_key
  - net/core/filter.c:bpf_skb_set_tunnel_key
```
```
In net/core/sock_diag.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: False
```
```
In net/core/netpoll.c (ffff800010c11020)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_poll_dev
```
```
In net/core/lwtunnel.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: False
```
```
In net/core/dst_cache.c (ffff800010c22160)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: True
Inline callers:
  - net/core/dst_cache.c:dst_cache_set_ip6
  - net/core/dst_cache.c:dst_cache_set_ip4
```
```
In net/core/bpf_sk_storage.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: False
```
```
In net/netfilter/nf_queue.c (ffff800010c55e08)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue
```
```
In net/ipv4/route.c (ffff800010c5bfa0)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:rt_cache_route
  - net/ipv4/route.c:rt_cache_route
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ip_idents_reserve
  - net/ipv4/route.c:ip_idents_reserve
  - net/ipv4/route.c:ip_idents_reserve
  - net/ipv4/route.c:ip_idents_reserve
```
```
In net/ipv4/protocol.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: False
```
```
In net/ipv4/ip_options.c (ffff800010c60ef8)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/ip_output.c (ffff800010c62370)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/ip_sockglue.c (ffff800010c66874)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
```
```
In net/ipv4/tcp.c (ffff800010c724d8)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: True
```
```
In net/ipv4/tcp_output.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: False
```
```
In net/ipv4/tcp_ipv4.c (ffff800010c8bb38)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:inet_sk_rx_dst_set
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_minisocks.c (ffff800010c8f980)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/tcp_fastopen.c (ffff800010c940f0)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
```
```
In net/ipv4/udp.c (ffff800010c9e320)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/arp.c (ffff800010ca1a9c)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: True
```
```
In net/ipv4/icmp.c (ffff800010ca3d4c)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: True
```
```
In net/ipv4/ipmr.c (ffff800010ccb4a8)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/xfrm/xfrm_policy.c (ffff800010ce0f68)
Location: arch/arm64/include/asm/cmpxchg.h:129
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
In net/xfrm/xfrm_input.c (ffff800010ceb0e8)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffff800010cec090)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/ipv6/ip6_output.c (ffff800010cfc5f0)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/route.c (ffff800010d1120c)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_create_rt_rcu
  - net/ipv6/route.c:ip6_create_rt_rcu
```
```
In net/ipv6/ip6_fib.c (ffff800010d18e98)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_new_sernum
```
```
In net/ipv6/tcp_ipv6.c (ffff800010d371c0)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
```
```
In net/ipv6/ip6_flowlabel.c (ffff800010d3fc94)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup
  - net/ipv6/ip6_flowlabel.c:fl_lookup
```
```
In net/ipv6/ip6mr.c (ffff800010d43e40)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/fib6_rules.c (ffff800010d4b19c)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
```
```
In net/ipv6/seg6_local.c (ffff800010d50e28)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
```
```
In net/ipv6/ip6_icmp.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: False
```
```
In net/ipv6/protocol.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: False
```
```
In net/xdp/xdp_umem.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: False
```
```
In lib/dec_and_lock.c (ffff800010d84734)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: True
```
```
In lib/dump_stack.c (ffff800010d84b88)
Location: arch/arm64/include/asm/cmpxchg.h:129
Inline: True
Inline callers:
  - lib/dump_stack.c:dump_stack
```
**Symbols:**

```
ffff8000102952c8-ffff8000102952f0: __cmpxchg_case_mb_32 (STB_LOCAL)
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
<b>Arch</b>
<ul>
</ul>
