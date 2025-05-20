# Function: <code>__cmpxchg_u64</code>

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
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/powerpc/kernel/fadump.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:319
Inline: True
```
```
In arch/powerpc/kernel/smp.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:319
Inline: True
```
```
In arch/powerpc/mm/book3s64/hash_64k.c (c00000000009df00)
Location: arch/powerpc/include/asm/cmpxchg.h:319
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/hash_64k.c:__hash_page_64K
  - arch/powerpc/mm/book3s64/hash_64k.c:__hash_page_4K
```
```
In arch/powerpc/mm/book3s64/hash_hugetlbpage.c (c00000000009e4ac)
Location: arch/powerpc/include/asm/cmpxchg.h:319
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/hash_hugetlbpage.c:__hash_page_huge
```
```
In arch/powerpc/mm/book3s64/hash_hugepage.c (c00000000009f1dc)
Location: arch/powerpc/include/asm/cmpxchg.h:319
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/hash_hugepage.c:__hash_page_thp
```
```
In arch/powerpc/mm/book3s64/iommu_api.c (c0000000000a06bc)
Location: arch/powerpc/include/asm/cmpxchg.h:319
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/iommu_api.c:mm_iommu_put
```
```
In arch/powerpc/platforms/powernv/idle.c (c0000000000c75f8)
Location: arch/powerpc/include/asm/cmpxchg.h:319
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/idle.c:power9_idle_stop
  - arch/powerpc/platforms/powernv/idle.c:power7_idle_insn
  - arch/powerpc/platforms/powernv/idle.c:power7_idle_insn
```
```
In arch/powerpc/platforms/powernv/pci-ioda-tce.c (c0000000000db110)
Location: arch/powerpc/include/asm/cmpxchg.h:319
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/pci-ioda-tce.c:pnv_tce
```
```
In arch/powerpc/xmon/xmon.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:319
Inline: True
```
```
In arch/powerpc/kvm/book3s_hv_rm_mmu.c (c00000000011cad4)
Location: arch/powerpc/include/asm/cmpxchg.h:319
Inline: True
Inline callers:
  - arch/powerpc/kvm/book3s_hv_rm_mmu.c:kvmppc_get_hpa
  - arch/powerpc/kvm/book3s_hv_rm_mmu.c:kvmppc_do_h_enter
```
```
In arch/powerpc/kvm/book3s_hv_builtin.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:319
Inline: True
```
```
In arch/powerpc/kvm/book3s_hv_rm_xics.c (c000000000123974)
Location: arch/powerpc/include/asm/cmpxchg.h:319
Inline: True
Inline callers:
  - arch/powerpc/kvm/book3s_hv_rm_xics.c:xics_rm_h_cppr
  - arch/powerpc/kvm/book3s_hv_rm_xics.c:xics_rm_h_ipi
  - arch/powerpc/kvm/book3s_hv_rm_xics.c:xics_rm_h_xirr
  - arch/powerpc/kvm/book3s_hv_rm_xics.c:icp_rm_deliver_irq
  - arch/powerpc/kvm/book3s_hv_rm_xics.c:icp_rm_set_vcpu_irq
  - arch/powerpc/kvm/book3s_hv_rm_xics.c:icp_rm_set_vcpu_irq
```
```
In kernel/panic.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:319
Inline: True
```
```
In kernel/exit.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:319
Inline: True
```
```
In kernel/task_work.c (c00000000016ed14)
Location: arch/powerpc/include/asm/cmpxchg.h:319
Inline: True
Inline callers:
  - kernel/task_work.c:task_work_run
  - kernel/task_work.c:task_work_cancel
  - kernel/task_work.c:task_work_add
```
```
In kernel/smpboot.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:319
Inline: True
```
```
In kernel/ucount.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:319
Inline: True
```
```
In kernel/sched/core.c (c0000000001840e4)
Location: arch/powerpc/include/asm/cmpxchg.h:319
Inline: True
Inline callers:
  - kernel/sched/core.c:wake_up_nohz_cpu
  - kernel/sched/core.c:resched_curr
  - kernel/sched/core.c:set_nr_if_polling
```
```
In kernel/sched/fair.c (c000000000192880)
Location: arch/powerpc/include/asm/cmpxchg.h:319
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_work
```
```
In kernel/sched/psi.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:319
Inline: True
```
```
In kernel/locking/rwsem.c (c000000000ee7b68)
Location: arch/powerpc/include/asm/cmpxchg.h:319
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:down_read_killable
  - kernel/locking/rwsem.c:down_read
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
```
```
In kernel/locking/osq_lock.c (c0000000001c2328)
Location: arch/powerpc/include/asm/cmpxchg.h:319
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_lock
```
```
In kernel/printk/printk_safe.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:319
Inline: True
```
```
In kernel/rcu/tree.c (c0000000001ec35c)
Location: arch/powerpc/include/asm/cmpxchg.h:319
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
```
```
In kernel/time/posix-cpu-timers.c (c0000000002110f0)
Location: arch/powerpc/include/asm/cmpxchg.h:319
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
```
```
In kernel/acct.c (c000000000230274)
Location: arch/powerpc/include/asm/cmpxchg.h:319
Inline: True
Inline callers:
  - kernel/acct.c:acct_pin_kill
```
```
In kernel/kexec_core.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:319
Inline: True
```
```
In kernel/debug/kdb/kdb_io.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:319
Inline: True
```
```
In kernel/trace/ring_buffer.c (c00000000029e930)
Location: arch/powerpc/include/asm/cmpxchg.h:319
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
```
```
In kernel/trace/tracing_map.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:319
Inline: True
```
```
In kernel/trace/trace_functions.c (c0000000002ba00c)
Location: arch/powerpc/include/asm/cmpxchg.h:319
Inline: True
```
```
In kernel/trace/blktrace.c (c0000000002c1c38)
Location: arch/powerpc/include/asm/cmpxchg.h:319
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_trace_setup_queue
  - kernel/trace/blktrace.c:__blk_trace_setup
```
```
In kernel/irq_work.c (c0000000002feb1c)
Location: arch/powerpc/include/asm/cmpxchg.h:319
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_claim
```
```
In kernel/bpf/devmap.c (c000000000331528)
Location: arch/powerpc/include/asm/cmpxchg.h:319
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_notification
```
```
In kernel/events/core.c (c00000000034c204)
Location: arch/powerpc/include/asm/cmpxchg.h:319
Inline: True
Inline callers:
  - kernel/events/core.c:free_event
```
```
In kernel/jump_label.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:319
Inline: True
```
```
In mm/oom_kill.c (c00000000036e1b4)
Location: arch/powerpc/include/asm/cmpxchg.h:319
Inline: True
Inline callers:
  - mm/oom_kill.c:mark_oom_victim
```
```
In mm/vmscan.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:319
Inline: True
```
```
In mm/mmzone.c (c00000000039921c)
Location: arch/powerpc/include/asm/cmpxchg.h:319
Inline: True
Inline callers:
  - mm/mmzone.c:page_cpupid_xchg_last
```
```
In mm/mmap.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:319
Inline: True
```
```
In mm/page_alloc.c (c0000000003e6c3c)
Location: arch/powerpc/include/asm/cmpxchg.h:319
Inline: True
Inline callers:
  - mm/page_alloc.c:set_pfnblock_flags_mask
```
```
In mm/frontswap.c (c0000000004019f8)
Location: arch/powerpc/include/asm/cmpxchg.h:319
Inline: True
Inline callers:
  - mm/frontswap.c:frontswap_register_ops
```
```
In mm/ksm.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:319
Inline: True
```
```
In mm/migrate.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:319
Inline: True
```
```
In mm/huge_memory.c (c00000000043d808)
Location: arch/powerpc/include/asm/cmpxchg.h:319
Inline: True
```
```
In mm/khugepaged.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:319
Inline: True
```
```
In mm/memcontrol.c (c00000000044cd80)
Location: arch/powerpc/include/asm/cmpxchg.h:319
Inline: True
Inline callers:
  - mm/memcontrol.c:__invalidate_reclaim_iterators
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
```
```
In mm/cleancache.c (c0000000004627d0)
Location: arch/powerpc/include/asm/cmpxchg.h:319
Inline: True
Inline callers:
  - mm/cleancache.c:cleancache_register_ops
```
```
In mm/memfd.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:319
Inline: True
```
```
In fs/open.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:319
Inline: True
```
```
In fs/exec.c (c000000000486d3c)
Location: arch/powerpc/include/asm/cmpxchg.h:319
Inline: True
Inline callers:
  - fs/exec.c:set_dumpable
```
```
In fs/namei.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:319
Inline: True
```
```
In fs/dcache.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:319
Inline: True
```
```
In fs/inode.c (c0000000004a84a8)
Location: arch/powerpc/include/asm/cmpxchg.h:319
Inline: True
Inline callers:
  - fs/inode.c:generic_update_time
```
```
In fs/fs-writeback.c (c0000000004c98c8)
Location: arch/powerpc/include/asm/cmpxchg.h:319
Inline: True
Inline callers:
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/nsfs.c (c0000000004d72f0)
Location: arch/powerpc/include/asm/cmpxchg.h:319
Inline: True
```
```
In fs/buffer.c (c0000000004de654)
Location: arch/powerpc/include/asm/cmpxchg.h:319
Inline: True
Inline callers:
  - fs/buffer.c:block_invalidatepage
```
```
In fs/direct-io.c (c0000000004e9dcc)
Location: arch/powerpc/include/asm/cmpxchg.h:319
Inline: True
Inline callers:
  - fs/direct-io.c:sb_init_dio_done_wq
```
```
In fs/notify/mark.c (c0000000004f0a98)
Location: arch/powerpc/include/asm/cmpxchg.h:319
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_list
```
```
In fs/eventpoll.c (c0000000004fa9e4)
Location: arch/powerpc/include/asm/cmpxchg.h:319
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll_callback
  - fs/eventpoll.c:ep_poll_callback
```
```
In fs/aio.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:319
Inline: True
```
```
In fs/io_uring.c (c000000000509518)
Location: arch/powerpc/include/asm/cmpxchg.h:319
Inline: True
Inline callers:
  - fs/io_uring.c:io_account_mem
```
```
In fs/crypto/keysetup.c (c00000000051c10c)
Location: arch/powerpc/include/asm/cmpxchg.h:319
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:setup_per_mode_key
  - fs/crypto/keysetup.c:derive_essiv_salt
```
```
In fs/verity/enable.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:319
Inline: True
```
```
In fs/verity/hash_algs.c (c00000000051f8ac)
Location: arch/powerpc/include/asm/cmpxchg.h:319
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
```
```
In fs/verity/open.c (c000000000520bb8)
Location: arch/powerpc/include/asm/cmpxchg.h:319
Inline: True
```
```
In fs/locks.c (c000000000523a1c)
Location: arch/powerpc/include/asm/cmpxchg.h:319
Inline: True
Inline callers:
  - fs/locks.c:locks_get_lock_context
```
```
In fs/posix_acl.c (c0000000005361dc)
Location: arch/powerpc/include/asm/cmpxchg.h:319
Inline: True
```
```
In fs/iomap/direct-io.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:319
Inline: True
```
```
In fs/proc/inode.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:319
Inline: True
```
```
In fs/kernfs/dir.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:319
Inline: True
```
```
In fs/ext4/dir.c (c00000000057fb90)
Location: arch/powerpc/include/asm/cmpxchg.h:319
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inline.c (c00000000059f138)
Location: arch/powerpc/include/asm/cmpxchg.h:319
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
```
```
In fs/ext4/inode.c (c0000000005a9388)
Location: arch/powerpc/include/asm/cmpxchg.h:319
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_update_bh_state
```
```
In fs/ext4/namei.c (c0000000005ccb44)
Location: arch/powerpc/include/asm/cmpxchg.h:319
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:add_dirent_to_buf
```
```
In fs/fat/dir.c (c000000000621138)
Location: arch/powerpc/include/asm/cmpxchg.h:319
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_remove_entries
```
```
In fs/fat/inode.c (c00000000062c578)
Location: arch/powerpc/include/asm/cmpxchg.h:319
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_inode
```
```
In fs/fat/misc.c (c00000000062dff8)
Location: arch/powerpc/include/asm/cmpxchg.h:319
Inline: True
```
```
In fs/fat/namei_vfat.c (c000000000630d84)
Location: arch/powerpc/include/asm/cmpxchg.h:319
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
In fs/fuse/dir.c (c00000000064bee8)
Location: arch/powerpc/include/asm/cmpxchg.h:319
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_dir_changed
```
```
In fs/fuse/readdir.c (c00000000065dc90)
Location: arch/powerpc/include/asm/cmpxchg.h:319
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
```
```
In fs/debugfs/file.c (c00000000065ffe8)
Location: arch/powerpc/include/asm/cmpxchg.h:319
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_file_get
```
```
In security/integrity/ima/ima_api.c (c000000000730768)
Location: arch/powerpc/include/asm/cmpxchg.h:319
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_collect_measurement
```
```
In block/bio.c (c00000000076f170)
Location: arch/powerpc/include/asm/cmpxchg.h:319
Inline: True
Inline callers:
  - block/bio.c:update_io_ticks
```
```
In block/blk-mq.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:319
Inline: True
```
```
In block/blk-mq-tag.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:319
Inline: True
```
```
In block/blk-rq-qos.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:319
Inline: True
```
```
In block/blk-cgroup.c (c0000000007a7b64)
Location: arch/powerpc/include/asm/cmpxchg.h:319
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_scale_delay
```
```
In block/blk-iocost.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:319
Inline: True
```
```
In lib/llist.c (c0000000007d8ce4)
Location: arch/powerpc/include/asm/cmpxchg.h:319
Inline: True
Inline callers:
  - lib/llist.c:llist_del_first
  - lib/llist.c:llist_add_batch
```
```
In lib/rhashtable.c (c0000000007dce94)
Location: arch/powerpc/include/asm/cmpxchg.h:319
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
```
```
In lib/errseq.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:319
Inline: True
```
```
In lib/genalloc.c (c0000000007ef3bc)
Location: arch/powerpc/include/asm/cmpxchg.h:319
Inline: True
Inline callers:
  - lib/genalloc.c:clear_bits_ll
  - lib/genalloc.c:set_bits_ll
```
```
In lib/sbitmap.c (c000000000820234)
Location: arch/powerpc/include/asm/cmpxchg.h:319
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_get_shallow
  - lib/sbitmap.c:sbitmap_get
  - lib/sbitmap.c:sbitmap_resize
```
```
In drivers/rapidio/rio.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:319
Inline: True
```
```
In drivers/tty/tty_ldsem.c (c0000000008fec20)
Location: arch/powerpc/include/asm/cmpxchg.h:319
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_write_trylock
  - drivers/tty/tty_ldsem.c:ldsem_down_write
  - drivers/tty/tty_ldsem.c:ldsem_down_write
  - drivers/tty/tty_ldsem.c:ldsem_down_read_trylock
  - drivers/tty/tty_ldsem.c:ldsem_down_read
```
```
In drivers/tty/tty_audit.c (c0000000009026d8)
Location: arch/powerpc/include/asm/cmpxchg.h:319
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_add_data
```
```
In drivers/char/random.c (c000000000949940)
Location: arch/powerpc/include/asm/cmpxchg.h:319
Inline: True
Inline callers:
  - drivers/char/random.c:do_numa_crng_init
```
```
In drivers/dma-buf/dma-fence-array.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:319
Inline: True
```
```
In drivers/dma-buf/dma-fence-chain.c (c000000000a201e4)
Location: arch/powerpc/include/asm/cmpxchg.h:319
Inline: True
```
```
In drivers/vfio/vfio.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:319
Inline: True
```
```
In drivers/thermal/thermal_core.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:319
Inline: True
```
```
In drivers/md/md.c (c000000000bcda88)
Location: arch/powerpc/include/asm/cmpxchg.h:319
Inline: True
Inline callers:
  - drivers/md/md.c:rdev_set_badblocks
  - drivers/md/md.c:md_do_sync
```
```
In drivers/md/dm.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:319
Inline: True
```
```
In net/core/sock.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:319
Inline: True
```
```
In net/core/skbuff.c (c000000000c89c08)
Location: arch/powerpc/include/asm/cmpxchg.h:319
Inline: True
```
```
In net/core/dev.c (c000000000cb29f4)
Location: arch/powerpc/include/asm/cmpxchg.h:319
Inline: True
Inline callers:
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:napi_complete_done
  - net/core/dev.c:napi_schedule_prep
```
```
In net/core/dst.c (c000000000cc14d0)
Location: arch/powerpc/include/asm/cmpxchg.h:319
Inline: True
Inline callers:
  - net/core/dst.c:__dst_destroy_metrics_generic
  - net/core/dst.c:dst_cow_metrics_generic
```
```
In net/core/filter.c (c000000000cdf4c4)
Location: arch/powerpc/include/asm/cmpxchg.h:319
Inline: True
Inline callers:
  - net/core/filter.c:bpf_get_skb_set_tunnel_proto
  - net/core/filter.c:bpf_clear_redirect_map
```
```
In net/core/sock_diag.c (c000000000ced668)
Location: arch/powerpc/include/asm/cmpxchg.h:319
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_gen_cookie
```
```
In net/core/netpoll.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:319
Inline: True
```
```
In net/core/lwtunnel.c (c000000000d0edcc)
Location: arch/powerpc/include/asm/cmpxchg.h:319
Inline: True
Inline callers:
  - net/core/lwtunnel.c:lwtunnel_encap_del_ops
  - net/core/lwtunnel.c:lwtunnel_encap_add_ops
```
```
In net/core/bpf_sk_storage.c (c000000000d2ab38)
Location: arch/powerpc/include/asm/cmpxchg.h:319
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:sk_storage_alloc
```
```
In net/ipv4/route.c (c000000000d5be7c)
Location: arch/powerpc/include/asm/cmpxchg.h:319
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_cache_route
```
```
In net/ipv4/protocol.c (c000000000d6053c)
Location: arch/powerpc/include/asm/cmpxchg.h:319
Inline: True
Inline callers:
  - net/ipv4/protocol.c:inet_del_offload
  - net/ipv4/protocol.c:inet_del_protocol
  - net/ipv4/protocol.c:inet_add_offload
  - net/ipv4/protocol.c:inet_add_protocol
```
```
In net/ipv4/tcp.c (c000000000d7564c)
Location: arch/powerpc/include/asm/cmpxchg.h:319
Inline: True
```
```
In net/ipv4/tcp_output.c (c000000000d8d360)
Location: arch/powerpc/include/asm/cmpxchg.h:319
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_wfree
  - net/ipv4/tcp_output.c:tcp_release_cb
```
```
In net/ipv6/route.c (c000000000e41680)
Location: arch/powerpc/include/asm/cmpxchg.h:319
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pol_route
```
```
In net/ipv6/ip6_fib.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:319
Inline: True
```
```
In net/ipv6/ip6_icmp.c (c000000000e8c48c)
Location: arch/powerpc/include/asm/cmpxchg.h:319
Inline: True
Inline callers:
  - net/ipv6/ip6_icmp.c:inet6_unregister_icmp_sender
  - net/ipv6/ip6_icmp.c:inet6_register_icmp_sender
```
```
In net/ipv6/protocol.c (c000000000e8cd7c)
Location: arch/powerpc/include/asm/cmpxchg.h:319
Inline: True
Inline callers:
  - net/ipv6/protocol.c:inet6_del_offload
  - net/ipv6/protocol.c:inet6_add_offload
  - net/ipv6/protocol.c:inet6_del_protocol
  - net/ipv6/protocol.c:inet6_add_protocol
```
```
In net/xdp/xdp_umem.c (c000000000ec1320)
Location: arch/powerpc/include/asm/cmpxchg.h:319
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_create
```
```
In lib/dump_stack.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:319
Inline: True
```
</details>
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
