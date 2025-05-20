# Function: <code>__lse__cmpxchg_case_mb_64</code>

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
In virt/kvm/kvm_main.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
```
```
In virt/kvm/arm/arm.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
```
```
In virt/kvm/arm/vgic/vgic-mmio-v3.c (ffff8000100e44dc)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
Inline callers:
  - virt/kvm/arm/vgic/vgic-mmio-v3.c:vgic_mmio_write_propbase
```
```
In kernel/fork.c (ffff8000100f1880)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
Inline callers:
  - kernel/fork.c:get_mm_exe_file
```
```
In kernel/panic.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
```
```
In kernel/exit.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
```
```
In kernel/task_work.c (ffff800010124e64)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
Inline callers:
  - kernel/task_work.c:task_work_run
  - kernel/task_work.c:task_work_cancel
  - kernel/task_work.c:task_work_add
```
```
In kernel/cred.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
```
```
In kernel/smpboot.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
```
```
In kernel/ucount.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
```
```
In kernel/kmod.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
```
```
In kernel/sched/fair.c (ffff800010142b04)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_work
```
```
In kernel/sched/psi.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
```
```
In kernel/locking/mutex.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
```
```
In kernel/locking/rwsem.c (ffff800010da53b0)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:down_read_killable
  - kernel/locking/rwsem.c:down_read
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
```
```
In kernel/locking/osq_lock.c (ffff80001016a644)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_lock
```
```
In kernel/printk/printk_safe.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
```
```
In kernel/irq/chip.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
```
```
In kernel/rcu/tree.c (ffff800010191058)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
```
```
In kernel/time/posix-cpu-timers.c (ffff8000101ad85c)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
```
```
In kernel/module.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
```
```
In kernel/acct.c (ffff8000101c8284)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
Inline callers:
  - kernel/acct.c:acct_process
  - kernel/acct.c:acct_pin_kill
```
```
In kernel/kexec_core.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffff8000101d8db4)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/cgroup-v1.c (ffff8000101dca48)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In kernel/cgroup/legacy_freezer.c (ffff8000101de870)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (ffff8000101dfc18)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffff8000101e4b10)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
```
In kernel/debug/kdb/kdb_io.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
```
```
In kernel/debug/kdb/kdb_main.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
```
```
In kernel/trace/ring_buffer.c (ffff800010218644)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_get_reader_page
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
In kernel/trace/tracing_map.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
```
```
In kernel/trace/trace_functions.c (ffff800010230078)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
```
```
In kernel/trace/blktrace.c (ffff800010235dbc)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_trace_setup_queue
  - kernel/trace/blktrace.c:__blk_trace_setup
```
```
In kernel/irq_work.c (ffff80001025afd8)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_claim
```
```
In kernel/bpf/syscall.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
```
```
In kernel/bpf/devmap.c (ffff800010287164)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_notification
```
```
In kernel/events/core.c (ffff8000102a0798)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_set_period
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:free_event
```
```
In kernel/events/ring_buffer.c (ffff8000102a2738)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
```
```
In kernel/events/uprobes.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
```
```
In kernel/jump_label.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
```
```
In mm/filemap.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
```
```
In mm/oom_kill.c (ffff8000102b7198)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
Inline callers:
  - mm/oom_kill.c:mark_oom_victim
```
```
In mm/page-writeback.c (ffff8000102bc794)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/swap.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
```
```
In mm/vmscan.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
```
```
In mm/mmzone.c (ffff8000102d95ec)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
Inline callers:
  - mm/mmzone.c:page_cpupid_xchg_last
```
```
In mm/backing-dev.c (ffff8000102de4dc)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
```
```
In mm/gup.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
```
```
In mm/mmap.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
```
```
In mm/rmap.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
```
```
In mm/page_alloc.c (ffff800010314f38)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
Inline callers:
  - mm/page_alloc.c:set_pfnblock_flags_mask
```
```
In mm/swapfile.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
```
```
In mm/frontswap.c (ffff80001032a658)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
Inline callers:
  - mm/frontswap.c:frontswap_register_ops
```
```
In mm/hugetlb.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
```
```
In mm/ksm.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
```
```
In mm/slub.c (ffff800010345b78)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
Inline callers:
  - mm/slub.c:alloc_slab_page
```
```
In mm/migrate.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
```
```
In mm/huge_memory.c (ffff800010356544)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
```
```
In mm/khugepaged.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
```
```
In mm/memcontrol.c (ffff800010369ec0)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:__invalidate_reclaim_iterators
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:percpu_ref_tryget_live
```
```
In mm/hugetlb_cgroup.c (ffff80001036d764)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In mm/memory-failure.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
```
```
In mm/cleancache.c (ffff8000103714e0)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
Inline callers:
  - mm/cleancache.c:cleancache_register_ops
```
```
In mm/page_idle.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
```
```
In mm/hmm.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
```
```
In mm/memfd.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
```
```
In fs/open.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
```
```
In fs/super.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
```
```
In fs/exec.c (ffff80001038f1e4)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
Inline callers:
  - fs/exec.c:set_dumpable
```
```
In fs/namei.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
```
```
In fs/dcache.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
```
```
In fs/inode.c (ffff8000103ac8d4)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
Inline callers:
  - fs/inode.c:generic_update_time
```
```
In fs/file.c (ffff8000103b0d98)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
Inline callers:
  - fs/file.c:__fget
```
```
In fs/fs-writeback.c (ffff8000103cab2c)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/nsfs.c (ffff8000103d4670)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
```
```
In fs/buffer.c (ffff8000103d9c64)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
Inline callers:
  - fs/buffer.c:block_invalidatepage
```
```
In fs/direct-io.c (ffff8000103e3e7c)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
Inline callers:
  - fs/direct-io.c:sb_init_dio_done_wq
```
```
In fs/notify/mark.c (ffff8000103e98b4)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_list
```
```
In fs/eventpoll.c (ffff8000103f168c)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll_callback
  - fs/eventpoll.c:ep_poll_callback
```
```
In fs/userfaultfd.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
```
```
In fs/aio.c (ffff8000103fbff4)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
Inline callers:
  - fs/aio.c:lookup_ioctx
```
```
In fs/io_uring.c (ffff800010405d80)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
Inline callers:
  - fs/io_uring.c:__arm64_sys_io_uring_enter
  - fs/io_uring.c:io_account_mem
  - fs/io_uring.c:io_get_req
```
```
In fs/crypto/keysetup.c (ffff80001040eb34)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:setup_per_mode_key
  - fs/crypto/keysetup.c:derive_essiv_salt
```
```
In fs/verity/enable.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
```
```
In fs/verity/hash_algs.c (ffff800010411c4c)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
```
```
In fs/verity/open.c (ffff800010412ea8)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
```
```
In fs/locks.c (ffff800010416190)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
Inline callers:
  - fs/locks.c:locks_get_lock_context
```
```
In fs/posix_acl.c (ffff8000104269b8)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
```
```
In fs/iomap/direct-io.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
```
```
In fs/proc/inode.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
```
```
In fs/proc/base.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
```
```
In fs/proc/proc_sysctl.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
```
```
In fs/kernfs/dir.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
```
```
In fs/ext4/balloc.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
```
```
In fs/ext4/dir.c (ffff8000104627c8)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/ialloc.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
```
```
In fs/ext4/inline.c (ffff80001047bac0)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
```
```
In fs/ext4/inode.c (ffff800010488e3c)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_update_bh_state
```
```
In fs/ext4/mballoc.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
```
```
In fs/ext4/namei.c (ffff8000104a06d0)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:add_dirent_to_buf
```
```
In fs/ext4/super.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
```
```
In fs/fat/dir.c (ffff8000104e5d0c)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_remove_entries
```
```
In fs/fat/inode.c (ffff8000104ed754)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_inode
```
```
In fs/fat/misc.c (ffff8000104eee80)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
```
```
In fs/fat/namei_vfat.c (ffff8000104f19d4)
Location: arch/arm64/include/asm/atomic_lse.h:379
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
In fs/fuse/dir.c (ffff800010506a18)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_dir_changed
```
```
In fs/fuse/readdir.c (ffff80001051544c)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
```
```
In fs/debugfs/file.c (ffff80001051705c)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_file_get
```
```
In security/integrity/ima/ima_api.c (ffff8000105b0a48)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_collect_measurement
```
```
In block/bio.c (ffff8000105dd8b8)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
Inline callers:
  - block/bio.c:update_io_ticks
```
```
In block/blk-core.c (ffff8000105e43ac)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-mq.c (ffff8000105ef754)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_timeout_work
```
```
In block/blk-mq-tag.c (ffff8000105f49ac)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
```
In block/blk-rq-qos.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
```
```
In block/blk-cgroup.c (ffff80001060e9fc)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkcg_scale_delay
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-iocost.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
```
```
In lib/llist.c (ffff8000106338ec)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
Inline callers:
  - lib/llist.c:llist_del_first
  - lib/llist.c:llist_add_batch
```
```
In lib/rhashtable.c (ffff800010636e9c)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
```
```
In lib/errseq.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
```
```
In lib/genalloc.c (ffff80001064433c)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
Inline callers:
  - lib/genalloc.c:clear_bits_ll
  - lib/genalloc.c:set_bits_ll
```
```
In lib/sbitmap.c (ffff800010669d04)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
```
```
In drivers/irqchip/irq-mvebu-icu.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
```
```
In drivers/phy/phy-core.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
```
```
In drivers/pci/pci-driver.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
```
```
In drivers/rapidio/rio.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
```
```
In drivers/acpi/apei/ghes.c (ffff8000107b003c)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
```
```
In drivers/amba/bus.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
```
```
In drivers/xen/grant-table.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
```
```
In drivers/xen/events/events_fifo.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
```
```
In drivers/tty/tty_ldsem.c (ffff80001085f698)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_write_trylock
  - drivers/tty/tty_ldsem.c:ldsem_down_write
  - drivers/tty/tty_ldsem.c:ldsem_down_write
  - drivers/tty/tty_ldsem.c:ldsem_down_read_trylock
  - drivers/tty/tty_ldsem.c:ldsem_down_read
```
```
In drivers/tty/tty_audit.c (ffff8000108637b4)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_add_data
```
```
In drivers/tty/hvc/hvc_console.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
```
```
In drivers/tty/serial/serial_core.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
```
```
In drivers/tty/serial/8250/8250_dw.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
```
```
In drivers/tty/serial/8250/8250_mtk.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
```
```
In drivers/tty/serdev/core.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
```
```
In drivers/char/random.c (ffff8000108b003c)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
Inline callers:
  - drivers/char/random.c:do_numa_crng_init
```
```
In drivers/iommu/iova.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
```
```
In drivers/base/core.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
```
```
In drivers/base/power/runtime.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
```
```
In drivers/base/power/wakeup.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
```
```
In drivers/dma-buf/dma-fence-array.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
```
```
In drivers/dma-buf/dma-fence-chain.c (ffff800010968644)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
```
```
In drivers/scsi/hosts.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
```
```
In drivers/spi/spi.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
```
```
In drivers/spi/spi-omap2-mcspi.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
```
```
In drivers/net/loopback.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
```
```
In drivers/net/ethernet/freescale/fec_main.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
```
```
In drivers/cdrom/cdrom.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
```
```
In drivers/usb/core/hcd.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
```
```
In drivers/usb/core/driver.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
```
```
In drivers/usb/core/hcd-pci.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
```
```
In drivers/usb/host/xhci-pci.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
```
```
In drivers/i2c/busses/i2c-designware-master.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
```
```
In drivers/i2c/busses/i2c-sprd.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
```
```
In drivers/thermal/thermal_core.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
```
```
In drivers/md/md.c (ffff800010ae8d68)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
Inline callers:
  - drivers/md/md.c:rdev_set_badblocks
  - drivers/md/md.c:md_do_sync
```
```
In drivers/md/dm.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
```
```
In drivers/mmc/core/sdio.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
```
```
In drivers/mmc/core/sdio_bus.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
```
```
In drivers/mmc/core/block.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
```
```
In drivers/firmware/efi/efi.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
```
```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
```
```
In drivers/perf/arm-cci.c (ffff800010b912bc)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
Inline callers:
  - drivers/perf/arm-cci.c:pmu_event_update
```
```
In drivers/perf/arm_pmu.c (ffff800010b94fe4)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
Inline callers:
  - drivers/perf/arm_pmu.c:armpmu_event_update
```
```
In drivers/perf/hisilicon/hisi_uncore_pmu.c (ffff800010b96604)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
Inline callers:
  - drivers/perf/hisilicon/hisi_uncore_pmu.c:hisi_uncore_pmu_event_update
```
```
In drivers/perf/qcom_l2_pmu.c (ffff800010b98e54)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
Inline callers:
  - drivers/perf/qcom_l2_pmu.c:l2_cache_event_update
```
```
In drivers/perf/qcom_l3_pmu.c (ffff800010b9a6a8)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
Inline callers:
  - drivers/perf/qcom_l3_pmu.c:qcom_l3_cache__32bit_counter_update
  - drivers/perf/qcom_l3_pmu.c:qcom_l3_cache__64bit_counter_update
```
```
In drivers/perf/xgene_pmu.c (ffff800010b9c0a4)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
Inline callers:
  - drivers/perf/xgene_pmu.c:xgene_perf_event_update
```
```
In net/core/sock.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
```
```
In net/core/skbuff.c (ffff800010bb2d4c)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
```
```
In net/core/dev.c (ffff800010bd3c50)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
Inline callers:
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:napi_complete_done
  - net/core/dev.c:napi_schedule_prep
```
```
In net/core/dst.c (ffff800010be08c4)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
Inline callers:
  - net/core/dst.c:__dst_destroy_metrics_generic
  - net/core/dst.c:dst_cow_metrics_generic
```
```
In net/core/neighbour.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
```
```
In net/core/filter.c (ffff800010bffc5c)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
Inline callers:
  - net/core/filter.c:bpf_get_skb_set_tunnel_proto
  - net/core/filter.c:bpf_clear_redirect_map
```
```
In net/core/sock_diag.c (ffff800010c03c68)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_gen_cookie
```
```
In net/core/netpoll.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
```
```
In net/core/lwtunnel.c (ffff800010c1df8c)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
Inline callers:
  - net/core/lwtunnel.c:lwtunnel_encap_del_ops
  - net/core/lwtunnel.c:lwtunnel_encap_add_ops
```
```
In net/core/dst_cache.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
```
```
In net/core/bpf_sk_storage.c (ffff800010c31ac4)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:sk_storage_alloc
```
```
In net/netfilter/nf_queue.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
```
```
In net/ipv4/route.c (ffff800010c5a39c)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_cache_route
```
```
In net/ipv4/protocol.c (ffff800010c5dde4)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
Inline callers:
  - net/ipv4/protocol.c:inet_del_offload
  - net/ipv4/protocol.c:inet_del_protocol
  - net/ipv4/protocol.c:inet_add_offload
  - net/ipv4/protocol.c:inet_add_protocol
```
```
In net/ipv4/ip_options.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
```
```
In net/ipv4/ip_output.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
```
```
In net/ipv4/ip_sockglue.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
```
```
In net/ipv4/tcp.c (ffff800010c704d4)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
```
```
In net/ipv4/tcp_output.c (ffff800010c829ac)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_wfree
  - net/ipv4/tcp_output.c:tcp_release_cb
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
```
```
In net/ipv4/tcp_minisocks.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
```
```
In net/ipv4/tcp_fastopen.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
```
```
In net/ipv4/arp.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
```
```
In net/ipv4/icmp.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
```
```
In net/xfrm/xfrm_policy.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
```
```
In net/xfrm/xfrm_input.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
```
```
In net/xfrm/xfrm_output.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
```
```
In net/ipv6/ip6_output.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
```
```
In net/ipv6/route.c (ffff800010d14918)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pol_route
```
```
In net/ipv6/ip6_fib.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
```
```
In net/ipv6/ip6_flowlabel.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
```
```
In net/ipv6/ip6mr.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
```
```
In net/ipv6/fib6_rules.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
```
```
In net/ipv6/seg6_local.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
```
```
In net/ipv6/ip6_icmp.c (ffff800010d53b38)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
Inline callers:
  - net/ipv6/ip6_icmp.c:inet6_unregister_icmp_sender
  - net/ipv6/ip6_icmp.c:inet6_register_icmp_sender
```
```
In net/ipv6/protocol.c (ffff800010d5431c)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
Inline callers:
  - net/ipv6/protocol.c:inet6_del_offload
  - net/ipv6/protocol.c:inet6_add_offload
  - net/ipv6/protocol.c:inet6_del_protocol
  - net/ipv6/protocol.c:inet6_add_protocol
```
```
In net/xdp/xdp_umem.c (ffff800010d81394)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_create
```
```
In lib/dec_and_lock.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
```
```
In lib/dump_stack.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:379
Inline: True
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
