# Function: <code>queued_spin_is_locked</code>

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
In kernel/fork.c (ffffffff8107f1d6)
Location: include/asm-generic/qspinlock.h:28
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/signal.c (ffffffff8108e0fa)
Location: include/asm-generic/qspinlock.h:28
Inline: True
Inline callers:
  - kernel/signal.c:__send_signal
```
```
In kernel/irq/migration.c (ffffffff810e25fb)
Location: include/asm-generic/qspinlock.h:28
Inline: True
Inline callers:
  - kernel/irq/migration.c:irq_move_masked_irq
```
```
In kernel/futex.c (ffffffff810ff943)
Location: include/asm-generic/qspinlock.h:28
Inline: True
Inline callers:
  - kernel/futex.c:__unqueue_futex
```
```
In kernel/debug/debug_core.c (ffffffff8112fd7a)
Location: include/asm-generic/qspinlock.h:28
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_nmicallback
```
```
In kernel/seccomp.c (ffffffff8113b85e)
Location: include/asm-generic/qspinlock.h:28
Inline: True
```
```
In mm/list_lru.c (ffffffff811b9258)
Location: include/asm-generic/qspinlock.h:28
Inline: True
```
```
In mm/pgtable-generic.c (ffffffff811d04d9)
Location: include/asm-generic/qspinlock.h:28
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pgtable_trans_huge_deposit
  - mm/pgtable-generic.c:pgtable_trans_huge_withdraw
```
```
In mm/swapfile.c (ffffffff811d30d9)
Location: include/asm-generic/qspinlock.h:28
Inline: True
Inline callers:
  - mm/swapfile.c:_enable_swap_info
```
```
In mm/frontswap.c (ffffffff811d77f5)
Location: include/asm-generic/qspinlock.h:28
Inline: True
Inline callers:
  - mm/frontswap.c:frontswap_shrink
  - mm/frontswap.c:frontswap_shrink
```
```
In mm/zswap.c (ffffffff811d81ec)
Location: include/asm-generic/qspinlock.h:28
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_param_set
```
```
In mm/huge_memory.c (ffffffff811f6114)
Location: include/asm-generic/qspinlock.h:28
Inline: True
Inline callers:
  - mm/huge_memory.c:follow_trans_huge_pmd
```
```
In fs/dcache.c (ffffffff81224407)
Location: include/asm-generic/qspinlock.h:28
Inline: True
Inline callers:
  - fs/dcache.c:__d_instantiate
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
```
```
In fs/fs-writeback.c (ffffffff81236265)
Location: include/asm-generic/qspinlock.h:28
Inline: True
Inline callers:
  - fs/fs-writeback.c:queue_io
```
```
In fs/notify/inode_mark.c (ffffffff8124fea1)
Location: include/asm-generic/qspinlock.h:28
Inline: True
Inline callers:
  - fs/notify/inode_mark.c:fsnotify_destroy_inode_mark
  - fs/notify/inode_mark.c:fsnotify_set_inode_mark_mask_locked
  - fs/notify/inode_mark.c:fsnotify_add_inode_mark
```
```
In fs/notify/mark.c (ffffffff81250685)
Location: include/asm-generic/qspinlock.h:28
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_set_mark_ignored_mask_locked
  - fs/notify/mark.c:fsnotify_duplicate_mark
```
```
In fs/notify/vfsmount_mark.c (ffffffff81250c71)
Location: include/asm-generic/qspinlock.h:28
Inline: True
Inline callers:
  - fs/notify/vfsmount_mark.c:fsnotify_destroy_vfsmount_mark
  - fs/notify/vfsmount_mark.c:fsnotify_add_vfsmount_mark
```
```
In fs/notify/dnotify/dnotify.c (ffffffff81251195)
Location: include/asm-generic/qspinlock.h:28
Inline: True
```
```
In fs/notify/inotify/inotify_user.c (ffffffff81252085)
Location: include/asm-generic/qspinlock.h:28
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_remove_from_idr
```
```
In fs/aio.c (ffffffff8125d98b)
Location: include/asm-generic/qspinlock.h:28
Inline: True
Inline callers:
  - fs/aio.c:SyS_io_cancel
```
```
In fs/ext4/mballoc.c (ffffffff812cd1c1)
Location: include/asm-generic/qspinlock.h:28
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:mb_find_extent
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:ext4_trim_fs
```
```
In fs/jbd2/transaction.c (ffffffff812e7306)
Location: include/asm-generic/qspinlock.h:28
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_refile_buffer
```
```
In fs/jbd2/checkpoint.c (ffffffff812ec985)
Location: include/asm-generic/qspinlock.h:28
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_journal_drop_transaction
```
```
In ipc/sem.c (ffffffff81327505)
Location: include/asm-generic/qspinlock.h:28
Inline: True
Inline callers:
  - ipc/sem.c:freeary
  - ipc/sem.c:SYSC_semtimedop
  - ipc/sem.c:SYSC_semtimedop
  - ipc/sem.c:SYSC_semtimedop
  - ipc/sem.c:SYSC_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:SyS_semctl
  - ipc/sem.c:exit_sem
```
```
In lib/lockref.c (ffffffff813f7d40)
Location: include/asm-generic/qspinlock.h:28
Inline: True
```
```
In drivers/iommu/intel-iommu.c (ffffffff8153898b)
Location: include/asm-generic/qspinlock.h:28
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info
  - drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info
  - drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info
  - drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info
  - drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info
  - drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info
```
```
In arch/x86/pci/i386.c (ffffffff816f5f95)
Location: include/asm-generic/qspinlock.h:28
Inline: True
Inline callers:
  - arch/x86/pci/i386.c:pcibios_fwaddrmap_lookup
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
In kernel/fork.c (ffffffff8108137c)
Location: include/asm-generic/qspinlock.h:41
Inline: True
```
```
In kernel/signal.c (ffffffff8109146c)
Location: include/asm-generic/qspinlock.h:41
Inline: True
Inline callers:
  - kernel/signal.c:__send_signal
```
```
In kernel/printk/nmi.c (ffffffff810df3d7)
Location: include/asm-generic/qspinlock.h:41
Inline: True
Inline callers:
  - kernel/printk/nmi.c:printk_nmi_flush_on_panic
```
```
In kernel/irq/migration.c (ffffffff810e808b)
Location: include/asm-generic/qspinlock.h:41
Inline: True
Inline callers:
  - kernel/irq/migration.c:irq_move_masked_irq
```
```
In kernel/futex.c (ffffffff81106d53)
Location: include/asm-generic/qspinlock.h:41
Inline: True
Inline callers:
  - kernel/futex.c:__unqueue_futex
```
```
In kernel/debug/debug_core.c (ffffffff81138814)
Location: include/asm-generic/qspinlock.h:41
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_nmicallback
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/seccomp.c (ffffffff811440f4)
Location: include/asm-generic/qspinlock.h:41
Inline: True
```
```
In mm/list_lru.c (ffffffff811d3558)
Location: include/asm-generic/qspinlock.h:41
Inline: True
```
```
In mm/pgtable-generic.c (ffffffff811ed764)
Location: include/asm-generic/qspinlock.h:41
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pgtable_trans_huge_withdraw
  - mm/pgtable-generic.c:pgtable_trans_huge_deposit
```
```
In mm/swapfile.c (ffffffff811f0f79)
Location: include/asm-generic/qspinlock.h:41
Inline: True
Inline callers:
  - mm/swapfile.c:_enable_swap_info
```
```
In mm/frontswap.c (ffffffff811f59e5)
Location: include/asm-generic/qspinlock.h:41
Inline: True
Inline callers:
  - mm/frontswap.c:frontswap_shrink
  - mm/frontswap.c:frontswap_shrink
```
```
In mm/zswap.c (ffffffff811f649b)
Location: include/asm-generic/qspinlock.h:41
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_param_set
```
```
In mm/huge_memory.c (ffffffff81214ec4)
Location: include/asm-generic/qspinlock.h:41
Inline: True
Inline callers:
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_devmap_pmd
```
```
In mm/zsmalloc.c (ffffffff8122a974)
Location: include/asm-generic/qspinlock.h:41
Inline: True
Inline callers:
  - mm/zsmalloc.c:__free_zspage
```
```
In fs/dcache.c (ffffffff8124cfd6)
Location: include/asm-generic/qspinlock.h:41
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:d_add
  - fs/dcache.c:__d_instantiate
```
```
In fs/fs-writeback.c (ffffffff8125fbd5)
Location: include/asm-generic/qspinlock.h:41
Inline: True
Inline callers:
  - fs/fs-writeback.c:queue_io
```
```
In fs/notify/inode_mark.c (ffffffff81278741)
Location: include/asm-generic/qspinlock.h:41
Inline: True
Inline callers:
  - fs/notify/inode_mark.c:fsnotify_add_inode_mark
  - fs/notify/inode_mark.c:fsnotify_set_inode_mark_mask_locked
  - fs/notify/inode_mark.c:fsnotify_destroy_inode_mark
```
```
In fs/notify/mark.c (ffffffff812792b5)
Location: include/asm-generic/qspinlock.h:41
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_duplicate_mark
  - fs/notify/mark.c:fsnotify_set_mark_ignored_mask_locked
```
```
In fs/notify/vfsmount_mark.c (ffffffff81279551)
Location: include/asm-generic/qspinlock.h:41
Inline: True
Inline callers:
  - fs/notify/vfsmount_mark.c:fsnotify_add_vfsmount_mark
  - fs/notify/vfsmount_mark.c:fsnotify_destroy_vfsmount_mark
```
```
In fs/notify/dnotify/dnotify.c (ffffffff81279995)
Location: include/asm-generic/qspinlock.h:41
Inline: True
```
```
In fs/notify/inotify/inotify_user.c (ffffffff8127a905)
Location: include/asm-generic/qspinlock.h:41
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_remove_from_idr
```
```
In fs/aio.c (ffffffff812866bb)
Location: include/asm-generic/qspinlock.h:41
Inline: True
Inline callers:
  - fs/aio.c:SyS_io_cancel
```
```
In fs/ext4/mballoc.c (ffffffff813056fa)
Location: include/asm-generic/qspinlock.h:41
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_find_extent
  - fs/ext4/mballoc.c:mb_free_blocks
```
```
In fs/jbd2/transaction.c (ffffffff8131717c)
Location: include/asm-generic/qspinlock.h:41
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:__jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer
```
```
In fs/jbd2/checkpoint.c (ffffffff8131a3f5)
Location: include/asm-generic/qspinlock.h:41
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_journal_drop_transaction
```
```
In ipc/sem.c (ffffffff8135e7ce)
Location: include/asm-generic/qspinlock.h:41
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:SYSC_semtimedop
  - ipc/sem.c:SYSC_semtimedop
  - ipc/sem.c:SYSC_semtimedop
  - ipc/sem.c:SYSC_semtimedop
  - ipc/sem.c:SyS_semctl
  - ipc/sem.c:semctl_main
  - ipc/sem.c:freeary
```
```
In security/yama/yama_lsm.c (ffffffff813d0f05)
Location: include/asm-generic/qspinlock.h:41
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:report_access
```
```
In lib/lockref.c (ffffffff8143ebf0)
Location: include/asm-generic/qspinlock.h:41
Inline: True
```
```
In drivers/iommu/iova.c (ffffffff815803f5)
Location: include/asm-generic/qspinlock.h:41
Inline: True
```
```
In drivers/iommu/intel-iommu.c (ffffffff8158d945)
Location: include/asm-generic/qspinlock.h:41
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info
  - drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info
  - drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info
  - drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info
  - drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info
  - drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info
  - drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:iommu_enable_dev_iotlb
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff8168d805)
Location: include/asm-generic/qspinlock.h:41
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_do_unreserve
```
```
In arch/x86/pci/i386.c (ffffffff8175ac55)
Location: include/asm-generic/qspinlock.h:41
Inline: True
Inline callers:
  - arch/x86/pci/i386.c:pcibios_fwaddrmap_lookup
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
In arch/x86/kernel/hpet.c (0)
Location: include/asm-generic/qspinlock.h:41
Inline: True
```
```
In kernel/fork.c (ffffffff81085de3)
Location: include/asm-generic/qspinlock.h:41
Inline: True
```
```
In kernel/signal.c (ffffffff810963fc)
Location: include/asm-generic/qspinlock.h:41
Inline: True
Inline callers:
  - kernel/signal.c:__send_signal
```
```
In kernel/printk/nmi.c (ffffffff810e59c7)
Location: include/asm-generic/qspinlock.h:41
Inline: True
Inline callers:
  - kernel/printk/nmi.c:printk_nmi_flush_on_panic
```
```
In kernel/irq/migration.c (ffffffff810eeaca)
Location: include/asm-generic/qspinlock.h:41
Inline: True
Inline callers:
  - kernel/irq/migration.c:irq_move_masked_irq
```
```
In kernel/futex.c (ffffffff8110e513)
Location: include/asm-generic/qspinlock.h:41
Inline: True
Inline callers:
  - kernel/futex.c:__unqueue_futex
```
```
In kernel/debug/debug_core.c (ffffffff811425a4)
Location: include/asm-generic/qspinlock.h:41
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_nmicallback
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/seccomp.c (ffffffff8114dfa3)
Location: include/asm-generic/qspinlock.h:41
Inline: True
```
```
In mm/list_lru.c (ffffffff811e3408)
Location: include/asm-generic/qspinlock.h:41
Inline: True
```
```
In mm/pgtable-generic.c (ffffffff811f7b3a)
Location: include/asm-generic/qspinlock.h:41
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pgtable_trans_huge_withdraw
  - mm/pgtable-generic.c:pgtable_trans_huge_deposit
```
```
In mm/swapfile.c (ffffffff812018e9)
Location: include/asm-generic/qspinlock.h:41
Inline: True
Inline callers:
  - mm/swapfile.c:_enable_swap_info
```
```
In mm/frontswap.c (ffffffff81206515)
Location: include/asm-generic/qspinlock.h:41
Inline: True
Inline callers:
  - mm/frontswap.c:frontswap_shrink
  - mm/frontswap.c:frontswap_shrink
```
```
In mm/zswap.c (ffffffff81206e38)
Location: include/asm-generic/qspinlock.h:41
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_param_set
```
```
In mm/huge_memory.c (ffffffff812274ce)
Location: include/asm-generic/qspinlock.h:41
Inline: True
Inline callers:
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_devmap_pmd
```
```
In mm/zsmalloc.c (ffffffff8123cec4)
Location: include/asm-generic/qspinlock.h:41
Inline: True
Inline callers:
  - mm/zsmalloc.c:__free_zspage
```
```
In fs/dcache.c (ffffffff81260096)
Location: include/asm-generic/qspinlock.h:41
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:d_add
  - fs/dcache.c:__d_instantiate
```
```
In fs/fs-writeback.c (ffffffff812730f5)
Location: include/asm-generic/qspinlock.h:41
Inline: True
Inline callers:
  - fs/fs-writeback.c:queue_io
```
```
In fs/notify/notification.c (ffffffff8128c061)
Location: include/asm-generic/qspinlock.h:41
Inline: True
Inline callers:
  - fs/notify/notification.c:fsnotify_flush_notify
  - fs/notify/notification.c:fsnotify_peek_first_event
```
```
In fs/notify/inode_mark.c (ffffffff8128c425)
Location: include/asm-generic/qspinlock.h:41
Inline: True
Inline callers:
  - fs/notify/inode_mark.c:fsnotify_add_inode_mark
  - fs/notify/inode_mark.c:fsnotify_set_inode_mark_mask_locked
  - fs/notify/inode_mark.c:fsnotify_destroy_inode_mark
```
```
In fs/notify/mark.c (ffffffff8128c965)
Location: include/asm-generic/qspinlock.h:41
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_set_mark_ignored_mask_locked
```
```
In fs/notify/vfsmount_mark.c (ffffffff8128d115)
Location: include/asm-generic/qspinlock.h:41
Inline: True
Inline callers:
  - fs/notify/vfsmount_mark.c:fsnotify_add_vfsmount_mark
  - fs/notify/vfsmount_mark.c:fsnotify_destroy_vfsmount_mark
```
```
In fs/notify/dnotify/dnotify.c (ffffffff8128d545)
Location: include/asm-generic/qspinlock.h:41
Inline: True
```
```
In fs/notify/inotify/inotify_user.c (ffffffff8128e4b5)
Location: include/asm-generic/qspinlock.h:41
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_remove_from_idr
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff8128f35f)
Location: include/asm-generic/qspinlock.h:41
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
```
```
In fs/aio.c (ffffffff8129a53b)
Location: include/asm-generic/qspinlock.h:41
Inline: True
Inline callers:
  - fs/aio.c:SyS_io_cancel
```
```
In fs/ext4/mballoc.c (ffffffff8131b6b8)
Location: include/asm-generic/qspinlock.h:41
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_find_extent
  - fs/ext4/mballoc.c:mb_free_blocks
```
```
In fs/jbd2/transaction.c (ffffffff8132d16c)
Location: include/asm-generic/qspinlock.h:41
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:__jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer
```
```
In fs/jbd2/checkpoint.c (ffffffff813303e5)
Location: include/asm-generic/qspinlock.h:41
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_journal_drop_transaction
```
```
In ipc/sem.c (ffffffff81374fa5)
Location: include/asm-generic/qspinlock.h:41
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:SYSC_semtimedop
  - ipc/sem.c:SYSC_semtimedop
  - ipc/sem.c:SyS_semctl
  - ipc/sem.c:semctl_main
  - ipc/sem.c:freeary
```
```
In security/yama/yama_lsm.c (ffffffff813e8605)
Location: include/asm-generic/qspinlock.h:41
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:report_access
```
```
In lib/lockref.c (ffffffff8145bc40)
Location: include/asm-generic/qspinlock.h:41
Inline: True
```
```
In drivers/iommu/iova.c (ffffffff815acf95)
Location: include/asm-generic/qspinlock.h:41
Inline: True
```
```
In drivers/iommu/intel-iommu.c (ffffffff815bb0e5)
Location: include/asm-generic/qspinlock.h:41
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info
  - drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info
  - drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info
  - drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info
  - drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info
  - drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info
  - drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:iommu_enable_dev_iotlb
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff816bb8d5)
Location: include/asm-generic/qspinlock.h:41
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_do_unreserve
```
```
In arch/x86/pci/i386.c (ffffffff817871b5)
Location: include/asm-generic/qspinlock.h:41
Inline: True
Inline callers:
  - arch/x86/pci/i386.c:pcibios_fwaddrmap_lookup
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
In arch/x86/kernel/hpet.c (0)
Location: include/asm-generic/qspinlock.h:41
Inline: True
```
```
In kernel/fork.c (ffffffff810827da)
Location: include/asm-generic/qspinlock.h:41
Inline: True
```
```
In kernel/signal.c (ffffffff810936cc)
Location: include/asm-generic/qspinlock.h:41
Inline: True
Inline callers:
  - kernel/signal.c:__send_signal
```
```
In kernel/printk/printk_safe.c (ffffffff810e4f67)
Location: include/asm-generic/qspinlock.h:41
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:printk_nmi_enter
  - kernel/printk/printk_safe.c:printk_safe_flush_on_panic
```
```
In kernel/irq/migration.c (ffffffff810ee60f)
Location: include/asm-generic/qspinlock.h:41
Inline: True
Inline callers:
  - kernel/irq/migration.c:irq_move_masked_irq
```
```
In kernel/futex.c (ffffffff8110fc83)
Location: include/asm-generic/qspinlock.h:41
Inline: True
Inline callers:
  - kernel/futex.c:__unqueue_futex
```
```
In kernel/debug/debug_core.c (ffffffff81143dc4)
Location: include/asm-generic/qspinlock.h:41
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_nmicallback
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/seccomp.c (ffffffff8115064d)
Location: include/asm-generic/qspinlock.h:41
Inline: True
```
```
In mm/list_lru.c (ffffffff811ed847)
Location: include/asm-generic/qspinlock.h:41
Inline: True
```
```
In mm/pgtable-generic.c (ffffffff81202d3a)
Location: include/asm-generic/qspinlock.h:41
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pgtable_trans_huge_withdraw
  - mm/pgtable-generic.c:pgtable_trans_huge_deposit
```
```
In mm/swapfile.c (ffffffff8120cb78)
Location: include/asm-generic/qspinlock.h:41
Inline: True
Inline callers:
  - mm/swapfile.c:_enable_swap_info
```
```
In mm/frontswap.c (ffffffff81211ca5)
Location: include/asm-generic/qspinlock.h:41
Inline: True
Inline callers:
  - mm/frontswap.c:frontswap_shrink
  - mm/frontswap.c:frontswap_shrink
```
```
In mm/zswap.c (ffffffff812130a0)
Location: include/asm-generic/qspinlock.h:41
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:zswap_pool_put
```
```
In mm/huge_memory.c (ffffffff812336da)
Location: include/asm-generic/qspinlock.h:41
Inline: True
Inline callers:
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:follow_devmap_pmd
```
```
In mm/zsmalloc.c (ffffffff81249524)
Location: include/asm-generic/qspinlock.h:41
Inline: True
Inline callers:
  - mm/zsmalloc.c:__free_zspage
```
```
In fs/dcache.c (ffffffff8126d9a5)
Location: include/asm-generic/qspinlock.h:41
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:d_add
  - fs/dcache.c:__d_instantiate
```
```
In fs/fs-writeback.c (ffffffff81280505)
Location: include/asm-generic/qspinlock.h:41
Inline: True
Inline callers:
  - fs/fs-writeback.c:queue_io
```
```
In fs/notify/notification.c (ffffffff81298fe1)
Location: include/asm-generic/qspinlock.h:41
Inline: True
Inline callers:
  - fs/notify/notification.c:fsnotify_flush_notify
  - fs/notify/notification.c:fsnotify_peek_first_event
```
```
In fs/notify/mark.c (ffffffff81299545)
Location: include/asm-generic/qspinlock.h:41
Inline: True
```
```
In fs/notify/dnotify/dnotify.c (ffffffff8129a465)
Location: include/asm-generic/qspinlock.h:41
Inline: True
```
```
In fs/notify/inotify/inotify_user.c (ffffffff8129b2e5)
Location: include/asm-generic/qspinlock.h:41
Inline: True
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff8129c2fa)
Location: include/asm-generic/qspinlock.h:41
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
```
```
In fs/aio.c (ffffffff812a828b)
Location: include/asm-generic/qspinlock.h:41
Inline: True
Inline callers:
  - fs/aio.c:SyS_io_cancel
```
```
In fs/ext4/mballoc.c (ffffffff81312a9d)
Location: include/asm-generic/qspinlock.h:41
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_find_extent
  - fs/ext4/mballoc.c:mb_free_blocks
```
```
In fs/jbd2/transaction.c (ffffffff8134233c)
Location: include/asm-generic/qspinlock.h:41
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:__jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer
```
```
In fs/jbd2/checkpoint.c (ffffffff81345305)
Location: include/asm-generic/qspinlock.h:41
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_journal_drop_transaction
```
```
In ipc/sem.c (ffffffff81388a89)
Location: include/asm-generic/qspinlock.h:41
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:SYSC_semtimedop
  - ipc/sem.c:SYSC_semtimedop
  - ipc/sem.c:SyS_semctl
  - ipc/sem.c:semctl_main
  - ipc/sem.c:freeary
```
```
In security/yama/yama_lsm.c (ffffffff813f44c5)
Location: include/asm-generic/qspinlock.h:41
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:report_access
```
```
In lib/lockref.c (ffffffff81461120)
Location: include/asm-generic/qspinlock.h:41
Inline: True
```
```
In drivers/iommu/iova.c (ffffffff815c2e05)
Location: include/asm-generic/qspinlock.h:41
Inline: True
```
```
In drivers/iommu/amd_iommu.c (ffffffff815c4cfa)
Location: include/asm-generic/qspinlock.h:41
Inline: True
```
```
In drivers/iommu/intel-iommu.c (ffffffff815d0d65)
Location: include/asm-generic/qspinlock.h:41
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info
  - drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info
  - drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info
  - drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info
  - drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info
  - drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info
  - drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff816cf9d5)
Location: include/asm-generic/qspinlock.h:41
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_do_unreserve
```
```
In drivers/md/md.c (ffffffff817398de)
Location: include/asm-generic/qspinlock.h:41
Inline: True
Inline callers:
  - drivers/md/md.c:set_in_sync
```
```
In arch/x86/pci/i386.c (ffffffff817a63c5)
Location: include/asm-generic/qspinlock.h:41
Inline: True
Inline callers:
  - arch/x86/pci/i386.c:pcibios_fwaddrmap_lookup
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
In arch/x86/kernel/hpet.c (0)
Location: include/asm-generic/qspinlock.h:30
Inline: True
```
```
In kernel/fork.c (ffffffff8108961c)
Location: include/asm-generic/qspinlock.h:30
Inline: True
```
```
In kernel/signal.c (ffffffff8109a5cd)
Location: include/asm-generic/qspinlock.h:30
Inline: True
Inline callers:
  - kernel/signal.c:__send_signal
```
```
In kernel/printk/printk_safe.c (ffffffff810ed1c7)
Location: include/asm-generic/qspinlock.h:30
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:printk_nmi_enter
  - kernel/printk/printk_safe.c:printk_safe_flush_on_panic
```
```
In kernel/irq/migration.c (ffffffff810f703f)
Location: include/asm-generic/qspinlock.h:30
Inline: True
Inline callers:
  - kernel/irq/migration.c:irq_move_masked_irq
```
```
In kernel/futex.c (ffffffff8111af73)
Location: include/asm-generic/qspinlock.h:30
Inline: True
Inline callers:
  - kernel/futex.c:__unqueue_futex
```
```
In kernel/debug/debug_core.c (ffffffff81150a84)
Location: include/asm-generic/qspinlock.h:30
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_nmicallback
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/seccomp.c (ffffffff8115c881)
Location: include/asm-generic/qspinlock.h:30
Inline: True
```
```
In mm/list_lru.c (ffffffff81203ca0)
Location: include/asm-generic/qspinlock.h:30
Inline: True
```
```
In mm/pgtable-generic.c (ffffffff8121ba96)
Location: include/asm-generic/qspinlock.h:30
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pgtable_trans_huge_withdraw
  - mm/pgtable-generic.c:pgtable_trans_huge_deposit
```
```
In mm/swapfile.c (ffffffff81226a45)
Location: include/asm-generic/qspinlock.h:30
Inline: True
Inline callers:
  - mm/swapfile.c:_enable_swap_info
```
```
In mm/frontswap.c (ffffffff8122c675)
Location: include/asm-generic/qspinlock.h:30
Inline: True
Inline callers:
  - mm/frontswap.c:frontswap_shrink
  - mm/frontswap.c:frontswap_shrink
```
```
In mm/zswap.c (ffffffff8122dbfc)
Location: include/asm-generic/qspinlock.h:30
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_pool_empty
```
```
In mm/huge_memory.c (ffffffff81250f8a)
Location: include/asm-generic/qspinlock.h:30
Inline: True
Inline callers:
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:follow_devmap_pmd
```
```
In mm/zsmalloc.c (ffffffff81269944)
Location: include/asm-generic/qspinlock.h:30
Inline: True
Inline callers:
  - mm/zsmalloc.c:__free_zspage
```
```
In fs/dcache.c (ffffffff81290445)
Location: include/asm-generic/qspinlock.h:30
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:d_add
  - fs/dcache.c:__d_instantiate
```
```
In fs/fs-writeback.c (ffffffff812a3040)
Location: include/asm-generic/qspinlock.h:30
Inline: True
Inline callers:
  - fs/fs-writeback.c:queue_io
```
```
In fs/notify/notification.c (ffffffff812bc381)
Location: include/asm-generic/qspinlock.h:30
Inline: True
Inline callers:
  - fs/notify/notification.c:fsnotify_flush_notify
  - fs/notify/notification.c:fsnotify_peek_first_event
```
```
In fs/notify/mark.c (ffffffff812bc8b5)
Location: include/asm-generic/qspinlock.h:30
Inline: True
```
```
In fs/notify/dnotify/dnotify.c (ffffffff812bd846)
Location: include/asm-generic/qspinlock.h:30
Inline: True
```
```
In fs/notify/inotify/inotify_user.c (ffffffff812be6fd)
Location: include/asm-generic/qspinlock.h:30
Inline: True
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff812bf770)
Location: include/asm-generic/qspinlock.h:30
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
```
```
In fs/aio.c (ffffffff812cb83b)
Location: include/asm-generic/qspinlock.h:30
Inline: True
Inline callers:
  - fs/aio.c:SyS_io_cancel
```
```
In fs/ext4/mballoc.c (ffffffff81337258)
Location: include/asm-generic/qspinlock.h:30
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_find_extent
  - fs/ext4/mballoc.c:mb_free_blocks
```
```
In fs/jbd2/transaction.c (ffffffff8136696c)
Location: include/asm-generic/qspinlock.h:30
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:__jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer
```
```
In fs/jbd2/checkpoint.c (ffffffff813699ae)
Location: include/asm-generic/qspinlock.h:30
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_journal_drop_transaction
```
```
In ipc/sem.c (ffffffff813ad752)
Location: include/asm-generic/qspinlock.h:30
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:freeary
```
```
In security/yama/yama_lsm.c (ffffffff8141cbb5)
Location: include/asm-generic/qspinlock.h:30
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:report_access
```
```
In lib/lockref.c (ffffffff8148cff0)
Location: include/asm-generic/qspinlock.h:30
Inline: True
```
```
In drivers/iommu/iova.c (ffffffff8162a040)
Location: include/asm-generic/qspinlock.h:30
Inline: True
Inline callers:
  - drivers/iommu/iova.c:queue_iova
  - drivers/iommu/iova.c:queue_iova
```
```
In drivers/iommu/intel-iommu.c (ffffffff81637b65)
Location: include/asm-generic/qspinlock.h:30
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info
  - drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info
  - drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info
  - drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info
  - drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info
  - drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info
  - drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff8173c02e)
Location: include/asm-generic/qspinlock.h:30
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_do_unreserve
```
```
In arch/x86/pci/i386.c (ffffffff8181d645)
Location: include/asm-generic/qspinlock.h:30
Inline: True
Inline callers:
  - arch/x86/pci/i386.c:pcibios_fwaddrmap_lookup
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
In arch/x86/kernel/hpet.c (ffffffff8106b582)
Location: include/asm-generic/qspinlock.h:29
Inline: True
```
```
In kernel/fork.c (ffffffff8108cf9d)
Location: include/asm-generic/qspinlock.h:29
Inline: True
```
```
In kernel/signal.c (ffffffff8109e4dd)
Location: include/asm-generic/qspinlock.h:29
Inline: True
Inline callers:
  - kernel/signal.c:__send_signal
```
```
In kernel/printk/printk_safe.c (ffffffff810f5405)
Location: include/asm-generic/qspinlock.h:29
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:printk_safe_flush_on_panic
```
```
In kernel/irq/migration.c (ffffffff810ff36f)
Location: include/asm-generic/qspinlock.h:29
Inline: True
Inline callers:
  - kernel/irq/migration.c:irq_move_masked_irq
```
```
In kernel/futex.c (ffffffff81127e33)
Location: include/asm-generic/qspinlock.h:29
Inline: True
Inline callers:
  - kernel/futex.c:__unqueue_futex
```
```
In kernel/debug/debug_core.c (ffffffff8115f604)
Location: include/asm-generic/qspinlock.h:29
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_nmicallback
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/seccomp.c (ffffffff8116bba6)
Location: include/asm-generic/qspinlock.h:29
Inline: True
```
```
In mm/list_lru.c (ffffffff81224836)
Location: include/asm-generic/qspinlock.h:29
Inline: True
```
```
In mm/pgtable-generic.c (ffffffff8123d846)
Location: include/asm-generic/qspinlock.h:29
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pgtable_trans_huge_withdraw
  - mm/pgtable-generic.c:pgtable_trans_huge_deposit
```
```
In mm/swapfile.c (ffffffff812492d5)
Location: include/asm-generic/qspinlock.h:29
Inline: True
Inline callers:
  - mm/swapfile.c:_enable_swap_info
```
```
In mm/frontswap.c (ffffffff8124f145)
Location: include/asm-generic/qspinlock.h:29
Inline: True
Inline callers:
  - mm/frontswap.c:frontswap_shrink
  - mm/frontswap.c:frontswap_shrink
```
```
In mm/zswap.c (ffffffff8124ff7f)
Location: include/asm-generic/qspinlock.h:29
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_param_set
```
```
In mm/huge_memory.c (ffffffff8127545a)
Location: include/asm-generic/qspinlock.h:29
Inline: True
Inline callers:
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:follow_devmap_pmd
```
```
In mm/zsmalloc.c (ffffffff8128d859)
Location: include/asm-generic/qspinlock.h:29
Inline: True
Inline callers:
  - mm/zsmalloc.c:__free_zspage
```
```
In fs/dcache.c (ffffffff812b57d5)
Location: include/asm-generic/qspinlock.h:29
Inline: True
Inline callers:
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:d_add
  - fs/dcache.c:__d_instantiate
```
```
In fs/fs-writeback.c (ffffffff812c9a85)
Location: include/asm-generic/qspinlock.h:29
Inline: True
Inline callers:
  - fs/fs-writeback.c:queue_io
```
```
In fs/notify/notification.c (ffffffff812e4fa1)
Location: include/asm-generic/qspinlock.h:29
Inline: True
Inline callers:
  - fs/notify/notification.c:fsnotify_flush_notify
  - fs/notify/notification.c:fsnotify_peek_first_event
```
```
In fs/notify/mark.c (ffffffff812e5325)
Location: include/asm-generic/qspinlock.h:29
Inline: True
```
```
In fs/notify/dnotify/dnotify.c (ffffffff812e64c5)
Location: include/asm-generic/qspinlock.h:29
Inline: True
```
```
In fs/notify/inotify/inotify_user.c (ffffffff812e6fe5)
Location: include/asm-generic/qspinlock.h:29
Inline: True
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff812e9297)
Location: include/asm-generic/qspinlock.h:29
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
```
```
In fs/aio.c (ffffffff812f2115)
Location: include/asm-generic/qspinlock.h:29
Inline: True
Inline callers:
  - fs/aio.c:lookup_kiocb
```
```
In fs/ext4/mballoc.c (ffffffff81365993)
Location: include/asm-generic/qspinlock.h:29
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_find_extent
  - fs/ext4/mballoc.c:mb_free_blocks
```
```
In fs/jbd2/transaction.c (ffffffff8139504c)
Location: include/asm-generic/qspinlock.h:29
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:__jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer
```
```
In fs/jbd2/checkpoint.c (ffffffff81398145)
Location: include/asm-generic/qspinlock.h:29
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_journal_drop_transaction
```
```
In ipc/sem.c (ffffffff813dd200)
Location: include/asm-generic/qspinlock.h:29
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:freeary
```
```
In security/yama/yama_lsm.c (ffffffff8144ee45)
Location: include/asm-generic/qspinlock.h:29
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:report_access
```
```
In lib/lockref.c (ffffffff814c1b70)
Location: include/asm-generic/qspinlock.h:29
Inline: True
```
```
In drivers/iommu/iova.c (ffffffff81664d50)
Location: include/asm-generic/qspinlock.h:29
Inline: True
Inline callers:
  - drivers/iommu/iova.c:queue_iova
  - drivers/iommu/iova.c:queue_iova
```
```
In drivers/iommu/intel-iommu.c (ffffffff81672ec5)
Location: include/asm-generic/qspinlock.h:29
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info
  - drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info
  - drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info
  - drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info
  - drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info
  - drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info
  - drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:iommu_enable_dev_iotlb
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff8177c885)
Location: include/asm-generic/qspinlock.h:29
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_do_unreserve
```
```
In arch/x86/pci/i386.c (ffffffff81867815)
Location: include/asm-generic/qspinlock.h:29
Inline: True
Inline callers:
  - arch/x86/pci/i386.c:pcibios_fwaddrmap_lookup
```
```
In net/core/dev.c (0)
Location: include/asm-generic/qspinlock.h:29
Inline: True
```
```
In net/sched/sch_generic.c (ffffffff818cd9e9)
Location: include/asm-generic/qspinlock.h:29
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
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
In arch/x86/kernel/hpet.c (ffffffff810715fe)
Location: include/asm-generic/qspinlock.h:29
Inline: True
```
```
In kernel/fork.c (ffffffff81094ad9)
Location: include/asm-generic/qspinlock.h:29
Inline: True
```
```
In kernel/signal.c (ffffffff810a67fd)
Location: include/asm-generic/qspinlock.h:29
Inline: True
Inline callers:
  - kernel/signal.c:__send_signal
```
```
In kernel/printk/printk_safe.c (ffffffff81100ba5)
Location: include/asm-generic/qspinlock.h:29
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:printk_safe_flush_on_panic
```
```
In kernel/irq/migration.c (ffffffff8110ab4f)
Location: include/asm-generic/qspinlock.h:29
Inline: True
Inline callers:
  - kernel/irq/migration.c:irq_move_masked_irq
```
```
In kernel/audit_tree.c (ffffffff81167091)
Location: include/asm-generic/qspinlock.h:29
Inline: True
Inline callers:
  - kernel/audit_tree.c:prune_tree_chunks
```
```
In kernel/debug/debug_core.c (ffffffff8116c353)
Location: include/asm-generic/qspinlock.h:29
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_nmicallback
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/seccomp.c (ffffffff8117941f)
Location: include/asm-generic/qspinlock.h:29
Inline: True
```
```
In mm/list_lru.c (ffffffff8123776a)
Location: include/asm-generic/qspinlock.h:29
Inline: True
Inline callers:
  - mm/list_lru.c:__list_lru_walk_one
  - mm/list_lru.c:__list_lru_walk_one
```
```
In mm/pgtable-generic.c (ffffffff81251df6)
Location: include/asm-generic/qspinlock.h:29
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pgtable_trans_huge_withdraw
  - mm/pgtable-generic.c:pgtable_trans_huge_deposit
```
```
In mm/swapfile.c (ffffffff8125dba2)
Location: include/asm-generic/qspinlock.h:29
Inline: True
Inline callers:
  - mm/swapfile.c:_enable_swap_info
```
```
In mm/frontswap.c (ffffffff812635e5)
Location: include/asm-generic/qspinlock.h:29
Inline: True
Inline callers:
  - mm/frontswap.c:frontswap_shrink
  - mm/frontswap.c:frontswap_shrink
```
```
In mm/zswap.c (ffffffff8126444f)
Location: include/asm-generic/qspinlock.h:29
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_param_set
```
```
In mm/huge_memory.c (ffffffff8128a3ba)
Location: include/asm-generic/qspinlock.h:29
Inline: True
Inline callers:
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:follow_devmap_pmd
```
```
In mm/zsmalloc.c (ffffffff812a27c9)
Location: include/asm-generic/qspinlock.h:29
Inline: True
Inline callers:
  - mm/zsmalloc.c:__free_zspage
```
```
In fs/dcache.c (ffffffff812caaf3)
Location: include/asm-generic/qspinlock.h:29
Inline: True
Inline callers:
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:d_add
  - fs/dcache.c:__d_instantiate
```
```
In fs/fs-writeback.c (ffffffff812decb5)
Location: include/asm-generic/qspinlock.h:29
Inline: True
Inline callers:
  - fs/fs-writeback.c:queue_io
```
```
In fs/notify/notification.c (ffffffff812f9ac1)
Location: include/asm-generic/qspinlock.h:29
Inline: True
Inline callers:
  - fs/notify/notification.c:fsnotify_flush_notify
  - fs/notify/notification.c:fsnotify_peek_first_event
```
```
In fs/notify/mark.c (ffffffff812f9f95)
Location: include/asm-generic/qspinlock.h:29
Inline: True
```
```
In fs/notify/dnotify/dnotify.c (ffffffff812fb085)
Location: include/asm-generic/qspinlock.h:29
Inline: True
```
```
In fs/notify/inotify/inotify_user.c (ffffffff812fbbd5)
Location: include/asm-generic/qspinlock.h:29
Inline: True
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff812fd397)
Location: include/asm-generic/qspinlock.h:29
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
```
```
In fs/aio.c (ffffffff81306ae5)
Location: include/asm-generic/qspinlock.h:29
Inline: True
Inline callers:
  - fs/aio.c:lookup_kiocb
```
```
In fs/ext4/mballoc.c (ffffffff8137dd53)
Location: include/asm-generic/qspinlock.h:29
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_find_extent
  - fs/ext4/mballoc.c:mb_free_blocks
```
```
In fs/jbd2/transaction.c (ffffffff813addbc)
Location: include/asm-generic/qspinlock.h:29
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:__jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer
```
```
In fs/jbd2/checkpoint.c (ffffffff813b0eb5)
Location: include/asm-generic/qspinlock.h:29
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_journal_drop_transaction
```
```
In ipc/sem.c (ffffffff813f7860)
Location: include/asm-generic/qspinlock.h:29
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:freeary
```
```
In security/yama/yama_lsm.c (ffffffff8146be15)
Location: include/asm-generic/qspinlock.h:29
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:report_access
```
```
In lib/lockref.c (ffffffff814d6260)
Location: include/asm-generic/qspinlock.h:29
Inline: True
```
```
In drivers/iommu/iova.c (ffffffff81683350)
Location: include/asm-generic/qspinlock.h:29
Inline: True
Inline callers:
  - drivers/iommu/iova.c:queue_iova
  - drivers/iommu/iova.c:queue_iova
```
```
In drivers/iommu/intel-iommu.c (ffffffff8168fb75)
Location: include/asm-generic/qspinlock.h:29
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info
  - drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info
  - drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info
  - drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info
  - drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info
  - drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info
  - drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info
  - drivers/iommu/intel-iommu.c:iommu_enable_dev_iotlb
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff817a2de5)
Location: include/asm-generic/qspinlock.h:29
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_do_unreserve
```
```
In net/core/dev.c (0)
Location: include/asm-generic/qspinlock.h:29
Inline: True
```
```
In net/sched/sch_generic.c (ffffffff818f8c29)
Location: include/asm-generic/qspinlock.h:29
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
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
In arch/x86/kernel/hpet.c (ffffffff8107547f)
Location: include/asm-generic/qspinlock.h:20
Inline: True
```
```
In kernel/fork.c (ffffffff8109928b)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/signal.c (ffffffff810ab51c)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - kernel/signal.c:__send_signal
```
```
In kernel/printk/printk_safe.c (ffffffff81109365)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:printk_safe_flush_on_panic
```
```
In kernel/irq/migration.c (ffffffff811141ff)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - kernel/irq/migration.c:irq_move_masked_irq
```
```
In kernel/audit_tree.c (ffffffff81173c9a)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - kernel/audit_tree.c:prune_tree_chunks
```
```
In kernel/debug/debug_core.c (ffffffff81179165)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_nmicallback
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/seccomp.c (ffffffff811862a8)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_attach_filter
  - kernel/seccomp.c:seccomp_attach_filter
  - kernel/seccomp.c:seccomp_attach_filter
  - kernel/seccomp.c:seccomp_attach_filter
```
```
In mm/list_lru.c (ffffffff81248ce5)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - mm/list_lru.c:__list_lru_walk_one
  - mm/list_lru.c:__list_lru_walk_one
```
```
In mm/pgtable-generic.c (ffffffff812640da)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pgtable_trans_huge_withdraw
  - mm/pgtable-generic.c:pgtable_trans_huge_deposit
```
```
In mm/swapfile.c (ffffffff81278d71)
Location: include/asm-generic/qspinlock.h:20
Inline: True
```
```
In mm/frontswap.c (ffffffff8127e5b5)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - mm/frontswap.c:frontswap_shrink
  - mm/frontswap.c:frontswap_shrink
```
```
In mm/zswap.c (ffffffff8127f44d)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_pool_empty
```
```
In mm/huge_memory.c (ffffffff812a4fe0)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:follow_devmap_pmd
```
```
In mm/zsmalloc.c (ffffffff812bda49)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - mm/zsmalloc.c:__free_zspage
```
```
In fs/dcache.c (ffffffff812e83d3)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:d_add
  - fs/dcache.c:__d_instantiate
```
```
In fs/fs-writeback.c (ffffffff812fd365)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - fs/fs-writeback.c:queue_io
```
```
In fs/notify/notification.c (ffffffff8131a171)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - fs/notify/notification.c:fsnotify_flush_notify
  - fs/notify/notification.c:fsnotify_peek_first_event
```
```
In fs/notify/mark.c (ffffffff8131a635)
Location: include/asm-generic/qspinlock.h:20
Inline: True
```
```
In fs/notify/dnotify/dnotify.c (ffffffff8131b955)
Location: include/asm-generic/qspinlock.h:20
Inline: True
```
```
In fs/notify/inotify/inotify_user.c (ffffffff8131c535)
Location: include/asm-generic/qspinlock.h:20
Inline: True
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff8131e1d5)
Location: include/asm-generic/qspinlock.h:20
Inline: True
```
```
In fs/ext4/mballoc.c (ffffffff813a4445)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_find_extent
  - fs/ext4/mballoc.c:mb_free_blocks
```
```
In fs/jbd2/transaction.c (ffffffff813d811e)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:__jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer
```
```
In fs/jbd2/checkpoint.c (ffffffff813db515)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_journal_drop_transaction
```
```
In ipc/sem.c (ffffffff81423d93)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:freeary
```
```
In security/yama/yama_lsm.c (ffffffff81498e05)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:report_access
```
```
In lib/lockref.c (ffffffff815020d0)
Location: include/asm-generic/qspinlock.h:20
Inline: True
```
```
In drivers/iommu/iova.c (ffffffff816ba90d)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - drivers/iommu/iova.c:queue_iova
  - drivers/iommu/iova.c:queue_iova
```
```
In drivers/iommu/intel-iommu.c (ffffffff816c7d9c)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_aux_detach_device
  - drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info
  - drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info
  - drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info
  - drivers/iommu/intel-iommu.c:domain_detach_iommu
  - drivers/iommu/intel-iommu.c:domain_detach_iommu
  - drivers/iommu/intel-iommu.c:domain_attach_iommu
  - drivers/iommu/intel-iommu.c:domain_attach_iommu
  - drivers/iommu/intel-iommu.c:iommu_enable_dev_iotlb
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff817e1ef5)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_do_unreserve
```
```
In net/core/dev.c (0)
Location: include/asm-generic/qspinlock.h:20
Inline: True
```
```
In net/sched/sch_generic.c (ffffffff819583f9)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
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
In arch/x86/kernel/hpet.c (ffffffff8107644f)
Location: include/asm-generic/qspinlock.h:20
Inline: True
```
```
In kernel/fork.c (ffffffff8109f883)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/signal.c (ffffffff810b1b2c)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - kernel/signal.c:__send_signal
```
```
In kernel/printk/printk_safe.c (ffffffff81115745)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:printk_safe_flush_on_panic
```
```
In kernel/irq/migration.c (ffffffff8112036f)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - kernel/irq/migration.c:irq_move_masked_irq
```
```
In kernel/audit_tree.c (ffffffff8117fb0a)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - kernel/audit_tree.c:prune_tree_chunks
```
```
In kernel/debug/debug_core.c (ffffffff81184fb5)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_nmicallback
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/seccomp.c (ffffffff81191f78)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_set_mode_filter
```
```
In mm/list_lru.c (ffffffff81257135)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - mm/list_lru.c:__list_lru_walk_one
  - mm/list_lru.c:__list_lru_walk_one
```
```
In mm/pgtable-generic.c (ffffffff8127294a)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pgtable_trans_huge_withdraw
  - mm/pgtable-generic.c:pgtable_trans_huge_deposit
```
```
In mm/swapfile.c (ffffffff81288851)
Location: include/asm-generic/qspinlock.h:20
Inline: True
```
```
In mm/frontswap.c (ffffffff8128e015)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - mm/frontswap.c:frontswap_shrink
  - mm/frontswap.c:frontswap_shrink
```
```
In mm/zswap.c (ffffffff8128eead)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_pool_empty
```
```
In mm/huge_memory.c (ffffffff812b64a0)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:follow_devmap_pmd
```
```
In mm/zsmalloc.c (ffffffff812cf939)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - mm/zsmalloc.c:__free_zspage
```
```
In fs/dcache.c (ffffffff812f9f63)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:d_add
  - fs/dcache.c:__d_instantiate
```
```
In fs/fs-writeback.c (ffffffff8130f855)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - fs/fs-writeback.c:queue_io
```
```
In fs/notify/notification.c (ffffffff8132cfa1)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - fs/notify/notification.c:fsnotify_flush_notify
  - fs/notify/notification.c:fsnotify_peek_first_event
```
```
In fs/notify/mark.c (ffffffff8132d475)
Location: include/asm-generic/qspinlock.h:20
Inline: True
```
```
In fs/notify/dnotify/dnotify.c (ffffffff8132e715)
Location: include/asm-generic/qspinlock.h:20
Inline: True
```
```
In fs/notify/inotify/inotify_user.c (ffffffff8132f325)
Location: include/asm-generic/qspinlock.h:20
Inline: True
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff81331015)
Location: include/asm-generic/qspinlock.h:20
Inline: True
```
```
In fs/ext4/mballoc.c (ffffffff813bd2b5)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_find_extent
  - fs/ext4/mballoc.c:mb_free_blocks
```
```
In fs/jbd2/transaction.c (ffffffff813f21fe)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:__jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer
```
```
In fs/jbd2/checkpoint.c (ffffffff813f5565)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_journal_drop_transaction
```
```
In ipc/sem.c (ffffffff8143dad3)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:freeary
```
```
In security/yama/yama_lsm.c (ffffffff814b2d35)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:report_access
```
```
In lib/lockref.c (ffffffff8151ffe0)
Location: include/asm-generic/qspinlock.h:20
Inline: True
```
```
In drivers/iommu/iova.c (ffffffff816dd74d)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - drivers/iommu/iova.c:queue_iova
  - drivers/iommu/iova.c:queue_iova
```
```
In drivers/iommu/intel-iommu.c (ffffffff816ead4c)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_aux_detach_device
  - drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info
  - drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info
  - drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info
  - drivers/iommu/intel-iommu.c:domain_detach_iommu
  - drivers/iommu/intel-iommu.c:domain_detach_iommu
  - drivers/iommu/intel-iommu.c:iommu_enable_dev_iotlb
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff81812d95)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_do_unreserve
```
```
In net/core/dev.c (0)
Location: include/asm-generic/qspinlock.h:20
Inline: True
```
```
In net/sched/sch_generic.c (ffffffff8198e8a9)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
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
In arch/x86/kernel/hpet.c (ffffffff8107d46d)
Location: include/asm-generic/qspinlock.h:20
Inline: True
```
```
In kernel/fork.c (ffffffff810a45dd)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - kernel/fork.c:copy_seccomp
```
```
In kernel/signal.c (ffffffff810ba13c)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - kernel/signal.c:__send_signal
  - kernel/signal.c:ptrace_trap_notify
```
```
In kernel/printk/printk_safe.c (ffffffff81121105)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:printk_safe_flush_on_panic
```
```
In kernel/irq/migration.c (ffffffff8112c8af)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - kernel/irq/migration.c:irq_move_masked_irq
```
```
In kernel/audit_tree.c (ffffffff81192ed2)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_tree_freeing_mark
  - kernel/audit_tree.c:create_chunk
  - kernel/audit_tree.c:untag_chunk
  - kernel/audit_tree.c:replace_chunk
```
```
In kernel/debug/debug_core.c (ffffffff81198881)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_call_nmi_hook
```
```
In kernel/seccomp.c (ffffffff811a7188)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_set_mode_strict
  - kernel/seccomp.c:seccomp_set_mode_strict
  - kernel/seccomp.c:seccomp_attach_filter
  - kernel/seccomp.c:seccomp_attach_filter
  - kernel/seccomp.c:seccomp_attach_filter
  - kernel/seccomp.c:seccomp_attach_filter
```
```
In mm/list_lru.c (ffffffff81285815)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - mm/list_lru.c:__list_lru_walk_one
  - mm/list_lru.c:__list_lru_walk_one
```
```
In mm/pgtable-generic.c (ffffffff812a370a)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pgtable_trans_huge_withdraw
  - mm/pgtable-generic.c:pgtable_trans_huge_deposit
```
```
In mm/swapfile.c (ffffffff812badb1)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - mm/swapfile.c:_enable_swap_info
```
```
In mm/frontswap.c (ffffffff812c09b5)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - mm/frontswap.c:frontswap_shrink
  - mm/frontswap.c:frontswap_shrink
```
```
In mm/zswap.c (ffffffff812c1b71)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_pool_empty
  - mm/zswap.c:zswap_pool_find_get
```
```
In mm/huge_memory.c (ffffffff812eb5c5)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:follow_devmap_pmd
```
```
In mm/zsmalloc.c (ffffffff81306314)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - mm/zsmalloc.c:__free_zspage
```
```
In fs/dcache.c (ffffffff81332034)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_add
  - fs/dcache.c:__d_instantiate
```
```
In fs/fs-writeback.c (ffffffff8134a1c5)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - fs/fs-writeback.c:queue_io
  - fs/fs-writeback.c:redirty_tail_locked
  - fs/fs-writeback.c:inode_io_list_del_locked
  - fs/fs-writeback.c:inode_io_list_del_locked
```
```
In fs/notify/notification.c (ffffffff81366d11)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - fs/notify/notification.c:fsnotify_flush_notify
  - fs/notify/notification.c:fsnotify_peek_first_event
  - fs/notify/notification.c:fsnotify_remove_first_event
  - fs/notify/notification.c:fsnotify_remove_first_event
```
```
In fs/notify/mark.c (ffffffff81367115)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - fs/notify/mark.c:__fsnotify_recalc_mask
```
```
In fs/notify/dnotify/dnotify.c (ffffffff813685f5)
Location: include/asm-generic/qspinlock.h:20
Inline: True
```
```
In fs/notify/inotify/inotify_user.c (ffffffff81368f65)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_idr_find_locked
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff8136b9b5)
Location: include/asm-generic/qspinlock.h:20
Inline: True
```
```
In fs/ext4/mballoc.c (ffffffff81408fb5)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_extent
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_find_extent
  - fs/ext4/mballoc.c:mb_free_blocks
```
```
In fs/jbd2/transaction.c (ffffffff8143f56d)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:__jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer
```
```
In fs/jbd2/checkpoint.c (ffffffff814428f5)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_journal_drop_transaction
```
```
In ipc/sem.c (ffffffff8148e648)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:lookup_undo
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:freeary
```
```
In security/yama/yama_lsm.c (ffffffff815120f6)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:report_access
```
```
In lib/lockref.c (ffffffff81583190)
Location: include/asm-generic/qspinlock.h:20
Inline: True
```
```
In drivers/iommu/iova.c (ffffffff8179452d)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - drivers/iommu/iova.c:queue_iova
  - drivers/iommu/iova.c:queue_iova
  - drivers/iommu/iova.c:fq_ring_free
  - drivers/iommu/iova.c:find_iova
```
```
In drivers/iommu/intel/iommu.c (ffffffff817a3638)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:aux_domain_add_dev
  - drivers/iommu/intel/iommu.c:auxiliary_unlink_device
  - drivers/iommu/intel/iommu.c:__dmar_remove_one_dev_info
  - drivers/iommu/intel/iommu.c:__dmar_remove_one_dev_info
  - drivers/iommu/intel/iommu.c:__dmar_remove_one_dev_info
  - drivers/iommu/intel/iommu.c:domain_attach_iommu
  - drivers/iommu/intel/iommu.c:domain_attach_iommu
  - drivers/iommu/intel/iommu.c:iommu_enable_dev_iotlb
  - drivers/iommu/intel/iommu.c:iommu_support_dev_iotlb
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff818e4edb)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_unlink
  - drivers/usb/dwc2/hcd_queue.c:dwc2_do_unreserve
```
```
In net/core/dev.c (0)
Location: include/asm-generic/qspinlock.h:20
Inline: True
```
```
In net/sched/sch_generic.c (ffffffff81a666bf)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
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
In arch/x86/kernel/hpet.c (ffffffff8107d3dd)
Location: include/asm-generic/qspinlock.h:22
Inline: True
```
```
In kernel/fork.c (ffffffff8109fa8d)
Location: include/asm-generic/qspinlock.h:22
Inline: True
Inline callers:
  - kernel/fork.c:copy_seccomp
```
```
In kernel/signal.c (ffffffff810b53ec)
Location: include/asm-generic/qspinlock.h:22
Inline: True
Inline callers:
  - kernel/signal.c:__send_signal
  - kernel/signal.c:ptrace_trap_notify
```
```
In kernel/printk/printk_safe.c (ffffffff8111bd65)
Location: include/asm-generic/qspinlock.h:22
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:printk_safe_flush_on_panic
  - kernel/printk/printk_safe.c:printk_safe_flush_on_panic
```
```
In kernel/irq/migration.c (ffffffff811282df)
Location: include/asm-generic/qspinlock.h:22
Inline: True
Inline callers:
  - kernel/irq/migration.c:irq_move_masked_irq
```
```
In kernel/audit_tree.c (ffffffff81190042)
Location: include/asm-generic/qspinlock.h:22
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_tree_freeing_mark
  - kernel/audit_tree.c:create_chunk
  - kernel/audit_tree.c:untag_chunk
  - kernel/audit_tree.c:replace_chunk
```
```
In kernel/debug/debug_core.c (ffffffff811959e1)
Location: include/asm-generic/qspinlock.h:22
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_call_nmi_hook
```
```
In kernel/seccomp.c (ffffffff811a4897)
Location: include/asm-generic/qspinlock.h:22
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_set_mode_strict
  - kernel/seccomp.c:seccomp_set_mode_strict
  - kernel/seccomp.c:seccomp_attach_filter
  - kernel/seccomp.c:seccomp_attach_filter
  - kernel/seccomp.c:seccomp_attach_filter
  - kernel/seccomp.c:seccomp_attach_filter
```
```
In mm/list_lru.c (ffffffff8128faf5)
Location: include/asm-generic/qspinlock.h:22
Inline: True
Inline callers:
  - mm/list_lru.c:__list_lru_walk_one
  - mm/list_lru.c:__list_lru_walk_one
```
```
In mm/pgtable-generic.c (ffffffff812aefea)
Location: include/asm-generic/qspinlock.h:22
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pgtable_trans_huge_withdraw
  - mm/pgtable-generic.c:pgtable_trans_huge_deposit
```
```
In mm/swapfile.c (ffffffff812c6831)
Location: include/asm-generic/qspinlock.h:22
Inline: True
Inline callers:
  - mm/swapfile.c:_enable_swap_info
```
```
In mm/frontswap.c (ffffffff812cc3d5)
Location: include/asm-generic/qspinlock.h:22
Inline: True
Inline callers:
  - mm/frontswap.c:frontswap_shrink
  - mm/frontswap.c:frontswap_shrink
```
```
In mm/zswap.c (ffffffff812cd751)
Location: include/asm-generic/qspinlock.h:22
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_pool_empty
  - mm/zswap.c:zswap_pool_find_get
```
```
In mm/huge_memory.c (ffffffff812f6685)
Location: include/asm-generic/qspinlock.h:22
Inline: True
Inline callers:
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:follow_devmap_pmd
```
```
In mm/zsmalloc.c (ffffffff81312074)
Location: include/asm-generic/qspinlock.h:22
Inline: True
Inline callers:
  - mm/zsmalloc.c:__free_zspage
```
```
In fs/dcache.c (ffffffff8133da54)
Location: include/asm-generic/qspinlock.h:22
Inline: True
Inline callers:
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_add
  - fs/dcache.c:__d_instantiate
```
```
In fs/fs-writeback.c (ffffffff813570f5)
Location: include/asm-generic/qspinlock.h:22
Inline: True
Inline callers:
  - fs/fs-writeback.c:queue_io
  - fs/fs-writeback.c:redirty_tail_locked
  - fs/fs-writeback.c:inode_io_list_del_locked
  - fs/fs-writeback.c:inode_io_list_del_locked
```
```
In fs/notify/notification.c (ffffffff81374061)
Location: include/asm-generic/qspinlock.h:22
Inline: True
Inline callers:
  - fs/notify/notification.c:fsnotify_flush_notify
  - fs/notify/notification.c:fsnotify_peek_first_event
  - fs/notify/notification.c:fsnotify_remove_first_event
  - fs/notify/notification.c:fsnotify_remove_first_event
```
```
In fs/notify/mark.c (ffffffff81374465)
Location: include/asm-generic/qspinlock.h:22
Inline: True
Inline callers:
  - fs/notify/mark.c:__fsnotify_recalc_mask
```
```
In fs/notify/dnotify/dnotify.c (ffffffff81375925)
Location: include/asm-generic/qspinlock.h:22
Inline: True
```
```
In fs/notify/inotify/inotify_user.c (ffffffff81376245)
Location: include/asm-generic/qspinlock.h:22
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_idr_find_locked
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff81379235)
Location: include/asm-generic/qspinlock.h:22
Inline: True
```
```
In fs/ext4/mballoc.c (ffffffff8141b4d5)
Location: include/asm-generic/qspinlock.h:22
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_extent
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_find_extent
  - fs/ext4/mballoc.c:mb_free_blocks
```
```
In fs/jbd2/transaction.c (ffffffff8145b7cd)
Location: include/asm-generic/qspinlock.h:22
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:__jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer
```
```
In fs/jbd2/checkpoint.c (ffffffff8145eb05)
Location: include/asm-generic/qspinlock.h:22
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_journal_drop_transaction
```
```
In ipc/sem.c (ffffffff814abd84)
Location: include/asm-generic/qspinlock.h:22
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:lookup_undo
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:freeary
```
```
In security/yama/yama_lsm.c (ffffffff8152ef96)
Location: include/asm-generic/qspinlock.h:22
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:report_access
```
```
In lib/lockref.c (ffffffff815a0010)
Location: include/asm-generic/qspinlock.h:22
Inline: True
```
```
In drivers/iommu/intel/iommu.c (ffffffff817acb69)
Location: include/asm-generic/qspinlock.h:22
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:auxiliary_unlink_device
  - drivers/iommu/intel/iommu.c:auxiliary_link_device
  - drivers/iommu/intel/iommu.c:__dmar_remove_one_dev_info
  - drivers/iommu/intel/iommu.c:__dmar_remove_one_dev_info
  - drivers/iommu/intel/iommu.c:__dmar_remove_one_dev_info
  - drivers/iommu/intel/iommu.c:domain_attach_iommu
  - drivers/iommu/intel/iommu.c:domain_attach_iommu
  - drivers/iommu/intel/iommu.c:iommu_enable_dev_iotlb
  - drivers/iommu/intel/iommu.c:domain_update_iotlb
  - drivers/iommu/intel/iommu.c:iommu_support_dev_iotlb
  - drivers/iommu/intel/iommu.c:domain_update_iommu_cap
```
```
In drivers/iommu/iova.c (ffffffff817c0fbd)
Location: include/asm-generic/qspinlock.h:22
Inline: True
Inline callers:
  - drivers/iommu/iova.c:queue_iova
  - drivers/iommu/iova.c:queue_iova
  - drivers/iommu/iova.c:fq_ring_free
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff818ee3ab)
Location: include/asm-generic/qspinlock.h:22
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_unlink
  - drivers/usb/dwc2/hcd_queue.c:dwc2_do_unreserve
```
```
In net/core/dev.c (0)
Location: include/asm-generic/qspinlock.h:22
Inline: True
```
```
In net/sched/sch_generic.c (ffffffff81a6e79f)
Location: include/asm-generic/qspinlock.h:22
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
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
In arch/x86/kernel/hpet.c (ffffffff8107e77d)
Location: include/asm-generic/qspinlock.h:22
Inline: True
```
```
In kernel/fork.c (ffffffff810a314b)
Location: include/asm-generic/qspinlock.h:22
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/signal.c (ffffffff810b6fdc)
Location: include/asm-generic/qspinlock.h:22
Inline: True
Inline callers:
  - kernel/signal.c:__send_signal
  - kernel/signal.c:ptrace_trap_notify
```
```
In kernel/printk/printk_safe.c (ffffffff8111c2e5)
Location: include/asm-generic/qspinlock.h:22
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:printk_safe_flush_on_panic
```
```
In kernel/irq/migration.c (ffffffff8112859f)
Location: include/asm-generic/qspinlock.h:22
Inline: True
Inline callers:
  - kernel/irq/migration.c:irq_move_masked_irq
```
```
In kernel/audit_tree.c (ffffffff81190f72)
Location: include/asm-generic/qspinlock.h:22
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_tree_freeing_mark
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:create_chunk
  - kernel/audit_tree.c:replace_chunk
```
```
In kernel/debug/debug_core.c (ffffffff81196981)
Location: include/asm-generic/qspinlock.h:22
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_call_nmi_hook
```
```
In kernel/seccomp.c (ffffffff811a57b2)
Location: include/asm-generic/qspinlock.h:22
Inline: True
Inline callers:
  - kernel/seccomp.c:do_seccomp
  - kernel/seccomp.c:do_seccomp
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_attach_filter
  - kernel/seccomp.c:seccomp_attach_filter
  - kernel/seccomp.c:seccomp_attach_filter
  - kernel/seccomp.c:seccomp_attach_filter
```
```
In mm/list_lru.c (ffffffff81295155)
Location: include/asm-generic/qspinlock.h:22
Inline: True
Inline callers:
  - mm/list_lru.c:__list_lru_walk_one
  - mm/list_lru.c:__list_lru_walk_one
```
```
In mm/pgtable-generic.c (ffffffff812b451a)
Location: include/asm-generic/qspinlock.h:22
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pgtable_trans_huge_withdraw
  - mm/pgtable-generic.c:pgtable_trans_huge_deposit
```
```
In mm/swapfile.c (ffffffff812cd3d1)
Location: include/asm-generic/qspinlock.h:22
Inline: True
Inline callers:
  - mm/swapfile.c:_enable_swap_info
```
```
In mm/frontswap.c (ffffffff812d31e5)
Location: include/asm-generic/qspinlock.h:22
Inline: True
Inline callers:
  - mm/frontswap.c:frontswap_shrink
  - mm/frontswap.c:frontswap_shrink
```
```
In mm/zswap.c (ffffffff812d4259)
Location: include/asm-generic/qspinlock.h:22
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_pool_empty
```
```
In mm/huge_memory.c (ffffffff812fca33)
Location: include/asm-generic/qspinlock.h:22
Inline: True
Inline callers:
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:follow_devmap_pmd
```
```
In mm/zsmalloc.c (ffffffff81317e14)
Location: include/asm-generic/qspinlock.h:22
Inline: True
Inline callers:
  - mm/zsmalloc.c:__free_zspage
```
```
In fs/dcache.c (ffffffff81343d53)
Location: include/asm-generic/qspinlock.h:22
Inline: True
Inline callers:
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_add
  - fs/dcache.c:__d_instantiate
```
```
In fs/fs-writeback.c (ffffffff8135daa5)
Location: include/asm-generic/qspinlock.h:22
Inline: True
Inline callers:
  - fs/fs-writeback.c:queue_io
  - fs/fs-writeback.c:redirty_tail_locked
  - fs/fs-writeback.c:inode_io_list_del_locked
  - fs/fs-writeback.c:inode_io_list_del_locked
```
```
In fs/notify/notification.c (ffffffff8137aa01)
Location: include/asm-generic/qspinlock.h:22
Inline: True
Inline callers:
  - fs/notify/notification.c:fsnotify_flush_notify
  - fs/notify/notification.c:fsnotify_remove_first_event
  - fs/notify/notification.c:fsnotify_remove_first_event
  - fs/notify/notification.c:fsnotify_remove_first_event
```
```
In fs/notify/mark.c (ffffffff8137ae15)
Location: include/asm-generic/qspinlock.h:22
Inline: True
Inline callers:
  - fs/notify/mark.c:__fsnotify_recalc_mask
```
```
In fs/notify/dnotify/dnotify.c (ffffffff8137c2c5)
Location: include/asm-generic/qspinlock.h:22
Inline: True
```
```
In fs/notify/inotify/inotify_user.c (ffffffff8137cbe5)
Location: include/asm-generic/qspinlock.h:22
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_idr_find_locked
  - fs/notify/inotify/inotify_user.c:inotify_poll
```
```
In fs/notify/fanotify/fanotify.c (ffffffff8137ddf6)
Location: include/asm-generic/qspinlock.h:22
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_insert_event
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff81380bdc)
Location: include/asm-generic/qspinlock.h:22
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_poll
```
```
In fs/ext4/mballoc.c (ffffffff81421b6c)
Location: include/asm-generic/qspinlock.h:22
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_find_extent
  - fs/ext4/mballoc.c:mb_free_blocks
```
```
In fs/jbd2/transaction.c (ffffffff81461110)
Location: include/asm-generic/qspinlock.h:22
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:__jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer
```
```
In fs/jbd2/checkpoint.c (ffffffff81464395)
Location: include/asm-generic/qspinlock.h:22
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_journal_drop_transaction
```
```
In ipc/sem.c (ffffffff814b1c16)
Location: include/asm-generic/qspinlock.h:22
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:lookup_undo
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:freeary
```
```
In security/yama/yama_lsm.c (ffffffff81534f26)
Location: include/asm-generic/qspinlock.h:22
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:report_access
```
```
In lib/lockref.c (ffffffff815a6e00)
Location: include/asm-generic/qspinlock.h:22
Inline: True
```
```
In drivers/iommu/intel/iommu.c (ffffffff817943ed)
Location: include/asm-generic/qspinlock.h:22
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:aux_domain_add_dev
  - drivers/iommu/intel/iommu.c:auxiliary_unlink_device
  - drivers/iommu/intel/iommu.c:__dmar_remove_one_dev_info
  - drivers/iommu/intel/iommu.c:__dmar_remove_one_dev_info
  - drivers/iommu/intel/iommu.c:__dmar_remove_one_dev_info
  - drivers/iommu/intel/iommu.c:domain_attach_iommu
  - drivers/iommu/intel/iommu.c:domain_attach_iommu
  - drivers/iommu/intel/iommu.c:iommu_enable_dev_iotlb
  - drivers/iommu/intel/iommu.c:domain_update_iotlb
  - drivers/iommu/intel/iommu.c:iommu_support_dev_iotlb
  - drivers/iommu/intel/iommu.c:domain_update_iommu_cap
```
```
In drivers/iommu/iova.c (ffffffff817a440d)
Location: include/asm-generic/qspinlock.h:22
Inline: True
Inline callers:
  - drivers/iommu/iova.c:queue_iova
  - drivers/iommu/iova.c:queue_iova
  - drivers/iommu/iova.c:fq_ring_free
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff818d1bab)
Location: include/asm-generic/qspinlock.h:22
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_unlink
  - drivers/usb/dwc2/hcd_queue.c:dwc2_do_unreserve
```
```
In net/core/dev.c (0)
Location: include/asm-generic/qspinlock.h:22
Inline: True
```
```
In net/sched/sch_generic.c (ffffffff81a5702f)
Location: include/asm-generic/qspinlock.h:22
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
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
In arch/x86/kernel/hpet.c (ffffffff8108d3fd)
Location: include/asm-generic/qspinlock.h:22
Inline: True
```
```
In kernel/fork.c (ffffffff810b48ec)
Location: include/asm-generic/qspinlock.h:22
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/signal.c (ffffffff810c865c)
Location: include/asm-generic/qspinlock.h:22
Inline: True
Inline callers:
  - kernel/signal.c:__send_signal
  - kernel/signal.c:ptrace_trap_notify
```
```
In kernel/irq/migration.c (ffffffff81148b6f)
Location: include/asm-generic/qspinlock.h:22
Inline: True
Inline callers:
  - kernel/irq/migration.c:irq_move_masked_irq
```
```
In kernel/audit_tree.c (ffffffff811b9e52)
Location: include/asm-generic/qspinlock.h:22
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_tree_freeing_mark
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:create_chunk
  - kernel/audit_tree.c:replace_chunk
```
```
In kernel/debug/debug_core.c (ffffffff811bfd25)
Location: include/asm-generic/qspinlock.h:22
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_call_nmi_hook
```
```
In kernel/seccomp.c (ffffffff811cef02)
Location: include/asm-generic/qspinlock.h:22
Inline: True
Inline callers:
  - kernel/seccomp.c:do_seccomp
  - kernel/seccomp.c:do_seccomp
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_attach_filter
  - kernel/seccomp.c:seccomp_attach_filter
  - kernel/seccomp.c:seccomp_attach_filter
  - kernel/seccomp.c:seccomp_attach_filter
```
```
In mm/list_lru.c (ffffffff812d57b5)
Location: include/asm-generic/qspinlock.h:22
Inline: True
Inline callers:
  - mm/list_lru.c:__list_lru_walk_one
  - mm/list_lru.c:__list_lru_walk_one
```
```
In mm/pgtable-generic.c (ffffffff812f60fa)
Location: include/asm-generic/qspinlock.h:22
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pgtable_trans_huge_withdraw
  - mm/pgtable-generic.c:pgtable_trans_huge_deposit
```
```
In mm/swapfile.c (ffffffff8131275f)
Location: include/asm-generic/qspinlock.h:22
Inline: True
Inline callers:
  - mm/swapfile.c:_enable_swap_info
```
```
In mm/frontswap.c (ffffffff81318bd5)
Location: include/asm-generic/qspinlock.h:22
Inline: True
Inline callers:
  - mm/frontswap.c:frontswap_curr_pages
  - mm/frontswap.c:frontswap_shrink
  - mm/frontswap.c:frontswap_shrink
  - mm/frontswap.c:frontswap_shrink
```
```
In mm/zswap.c (ffffffff81319f64)
Location: include/asm-generic/qspinlock.h:22
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_pool_empty
```
```
In mm/huge_memory.c (ffffffff813468b3)
Location: include/asm-generic/qspinlock.h:22
Inline: True
Inline callers:
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:follow_devmap_pmd
```
```
In mm/zsmalloc.c (ffffffff81363b74)
Location: include/asm-generic/qspinlock.h:22
Inline: True
Inline callers:
  - mm/zsmalloc.c:__free_zspage
```
```
In fs/dcache.c (ffffffff81391683)
Location: include/asm-generic/qspinlock.h:22
Inline: True
Inline callers:
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_add
  - fs/dcache.c:__d_instantiate
```
```
In fs/fs-writeback.c (ffffffff813ac185)
Location: include/asm-generic/qspinlock.h:22
Inline: True
Inline callers:
  - fs/fs-writeback.c:queue_io
  - fs/fs-writeback.c:redirty_tail_locked
  - fs/fs-writeback.c:redirty_tail_locked
  - fs/fs-writeback.c:inode_cgwb_move_to_attached
  - fs/fs-writeback.c:inode_cgwb_move_to_attached
```
```
In fs/notify/notification.c (ffffffff813c7671)
Location: include/asm-generic/qspinlock.h:22
Inline: True
Inline callers:
  - fs/notify/notification.c:fsnotify_flush_notify
  - fs/notify/notification.c:fsnotify_remove_first_event
  - fs/notify/notification.c:fsnotify_remove_first_event
  - fs/notify/notification.c:fsnotify_remove_first_event
```
```
In fs/notify/mark.c (ffffffff813c7a05)
Location: include/asm-generic/qspinlock.h:22
Inline: True
Inline callers:
  - fs/notify/mark.c:__fsnotify_recalc_mask
```
```
In fs/notify/dnotify/dnotify.c (ffffffff813c96db)
Location: include/asm-generic/qspinlock.h:22
Inline: True
Inline callers:
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:dnotify_flush
  - fs/notify/dnotify/dnotify.c:dnotify_handle_event
```
```
In fs/notify/inotify/inotify_user.c (ffffffff813ca404)
Location: include/asm-generic/qspinlock.h:22
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_remove_from_idr
  - fs/notify/inotify/inotify_user.c:inotify_idr_find
  - fs/notify/inotify/inotify_user.c:inotify_poll
```
```
In fs/notify/fanotify/fanotify.c (ffffffff813cad36)
Location: include/asm-generic/qspinlock.h:22
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_insert_event
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff813cd926)
Location: include/asm-generic/qspinlock.h:22
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
  - fs/notify/fanotify/fanotify_user.c:fanotify_write
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_poll
```
```
In fs/ext4/mballoc.c (ffffffff814742b7)
Location: include/asm-generic/qspinlock.h:22
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_try_to_trim_range
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_find_extent
  - fs/ext4/mballoc.c:mb_free_blocks
```
```
In fs/jbd2/transaction.c (ffffffff814b65f4)
Location: include/asm-generic/qspinlock.h:22
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:__jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer
```
```
In fs/jbd2/checkpoint.c (ffffffff814b99c5)
Location: include/asm-generic/qspinlock.h:22
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_journal_drop_transaction
```
```
In ipc/sem.c (ffffffff8150a1d4)
Location: include/asm-generic/qspinlock.h:22
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:lookup_undo
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:freeary
```
```
In security/yama/yama_lsm.c (ffffffff81593436)
Location: include/asm-generic/qspinlock.h:22
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:report_access
```
```
In lib/lockref.c (ffffffff8160fd40)
Location: include/asm-generic/qspinlock.h:22
Inline: True
Inline callers:
  - lib/lockref.c:lockref_mark_dead
```
```
In drivers/iommu/intel/iommu.c (ffffffff8181c31d)
Location: include/asm-generic/qspinlock.h:22
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:aux_domain_add_dev
  - drivers/iommu/intel/iommu.c:auxiliary_unlink_device
  - drivers/iommu/intel/iommu.c:__dmar_remove_one_dev_info
  - drivers/iommu/intel/iommu.c:__dmar_remove_one_dev_info
  - drivers/iommu/intel/iommu.c:__dmar_remove_one_dev_info
  - drivers/iommu/intel/iommu.c:domain_detach_iommu
  - drivers/iommu/intel/iommu.c:domain_detach_iommu
  - drivers/iommu/intel/iommu.c:iommu_enable_dev_iotlb
  - drivers/iommu/intel/iommu.c:domain_update_iotlb
  - drivers/iommu/intel/iommu.c:iommu_support_dev_iotlb
  - drivers/iommu/intel/iommu.c:domain_update_iommu_cap
```
```
In drivers/iommu/iova.c (ffffffff8182db33)
Location: include/asm-generic/qspinlock.h:22
Inline: True
Inline callers:
  - drivers/iommu/iova.c:queue_iova
  - drivers/iommu/iova.c:queue_iova
  - drivers/iommu/iova.c:fq_ring_free
  - drivers/iommu/iova.c:free_iova
  - drivers/iommu/iova.c:find_iova
  - drivers/iommu/iova.c:remove_iova
```
```
In drivers/iommu/virtio-iommu.c (ffffffff8182e660)
Location: include/asm-generic/qspinlock.h:22
Inline: True
Inline callers:
  - drivers/iommu/virtio-iommu.c:__viommu_add_req
  - drivers/iommu/virtio-iommu.c:__viommu_sync_req
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff8196c57f)
Location: include/asm-generic/qspinlock.h:22
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_unlink
  - drivers/usb/dwc2/hcd_queue.c:dwc2_do_unreserve
```
```
In net/core/dev.c (0)
Location: include/asm-generic/qspinlock.h:22
Inline: True
```
```
In net/sched/sch_generic.c (ffffffff81b0fe64)
Location: include/asm-generic/qspinlock.h:22
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
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
In arch/x86/kernel/hpet.c (ffffffff8109d66f)
Location: include/asm-generic/qspinlock.h:51
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:read_hpet
  - arch/x86/kernel/hpet.c:read_hpet
```
```
In kernel/fork.c (ffffffff810cade0)
Location: include/asm-generic/qspinlock.h:51
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/sched/core.c (ffffffff8110b2e7)
Location: include/asm-generic/qspinlock.h:51
Inline: True
```
```
In kernel/irq/migration.c (ffffffff8116d6ab)
Location: include/asm-generic/qspinlock.h:51
Inline: True
Inline callers:
  - kernel/irq/migration.c:irq_move_masked_irq
```
```
In kernel/audit_tree.c (ffffffff811ece0e)
Location: include/asm-generic/qspinlock.h:51
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_tree_freeing_mark
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:create_chunk
  - kernel/audit_tree.c:replace_chunk
```
```
In kernel/debug/debug_core.c (ffffffff811f3221)
Location: include/asm-generic/qspinlock.h:51
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_call_nmi_hook
```
```
In kernel/seccomp.c (ffffffff81203048)
Location: include/asm-generic/qspinlock.h:51
Inline: True
Inline callers:
  - kernel/seccomp.c:do_seccomp
  - kernel/seccomp.c:do_seccomp
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_attach_filter
  - kernel/seccomp.c:seccomp_attach_filter
  - kernel/seccomp.c:seccomp_attach_filter
  - kernel/seccomp.c:seccomp_attach_filter
```
```
In mm/list_lru.c (ffffffff81334ed5)
Location: include/asm-generic/qspinlock.h:51
Inline: True
Inline callers:
  - mm/list_lru.c:__list_lru_walk_one
  - mm/list_lru.c:__list_lru_walk_one
```
```
In mm/pgtable-generic.c (ffffffff8135a0ee)
Location: include/asm-generic/qspinlock.h:51
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pgtable_trans_huge_withdraw
  - mm/pgtable-generic.c:pgtable_trans_huge_deposit
```
```
In mm/swapfile.c (ffffffff8137d2ef)
Location: include/asm-generic/qspinlock.h:51
Inline: True
Inline callers:
  - mm/swapfile.c:_enable_swap_info
```
```
In mm/zswap.c (ffffffff81384fa0)
Location: include/asm-generic/qspinlock.h:51
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_pool_empty
```
```
In mm/huge_memory.c (ffffffff813bcaf4)
Location: include/asm-generic/qspinlock.h:51
Inline: True
Inline callers:
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:follow_devmap_pmd
```
```
In mm/zsmalloc.c (ffffffff813e268d)
Location: include/asm-generic/qspinlock.h:51
Inline: True
Inline callers:
  - mm/zsmalloc.c:__zs_compact
  - mm/zsmalloc.c:__free_zspage
```
```
In fs/dcache.c (ffffffff8141362f)
Location: include/asm-generic/qspinlock.h:51
Inline: True
Inline callers:
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_add
  - fs/dcache.c:__d_instantiate
```
```
In fs/fs-writeback.c (ffffffff81432225)
Location: include/asm-generic/qspinlock.h:51
Inline: True
Inline callers:
  - fs/fs-writeback.c:queue_io
  - fs/fs-writeback.c:redirty_tail_locked
  - fs/fs-writeback.c:redirty_tail_locked
  - fs/fs-writeback.c:redirty_tail_locked
  - fs/fs-writeback.c:inode_cgwb_move_to_attached
  - fs/fs-writeback.c:inode_cgwb_move_to_attached
```
```
In fs/notify/notification.c (ffffffff8144eab3)
Location: include/asm-generic/qspinlock.h:51
Inline: True
Inline callers:
  - fs/notify/notification.c:fsnotify_flush_notify
  - fs/notify/notification.c:fsnotify_remove_first_event
  - fs/notify/notification.c:fsnotify_remove_first_event
  - fs/notify/notification.c:fsnotify_remove_first_event
```
```
In fs/notify/mark.c (ffffffff8144eed5)
Location: include/asm-generic/qspinlock.h:51
Inline: True
Inline callers:
  - fs/notify/mark.c:__fsnotify_recalc_mask
```
```
In fs/notify/dnotify/dnotify.c (ffffffff814510d8)
Location: include/asm-generic/qspinlock.h:51
Inline: True
Inline callers:
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:dnotify_flush
  - fs/notify/dnotify/dnotify.c:dnotify_handle_event
```
```
In fs/notify/inotify/inotify_user.c (ffffffff814519c5)
Location: include/asm-generic/qspinlock.h:51
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_remove_from_idr
  - fs/notify/inotify/inotify_user.c:inotify_idr_find
  - fs/notify/inotify/inotify_user.c:inotify_poll
```
```
In fs/notify/fanotify/fanotify.c (ffffffff81452aa5)
Location: include/asm-generic/qspinlock.h:51
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_insert_event
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff8145603d)
Location: include/asm-generic/qspinlock.h:51
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
  - fs/notify/fanotify/fanotify_user.c:fanotify_write
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_poll
```
```
In fs/ext4/mballoc.c (ffffffff814f63bb)
Location: include/asm-generic/qspinlock.h:51
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_try_to_trim_range
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_find_extent
  - fs/ext4/mballoc.c:mb_free_blocks
```
```
In fs/jbd2/transaction.c (ffffffff8153ffe4)
Location: include/asm-generic/qspinlock.h:51
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:__jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer
```
```
In fs/jbd2/checkpoint.c (ffffffff81543695)
Location: include/asm-generic/qspinlock.h:51
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_journal_drop_transaction
```
```
In ipc/sem.c (ffffffff8159bf3e)
Location: include/asm-generic/qspinlock.h:51
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:lookup_undo
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:freeary
```
```
In security/yama/yama_lsm.c (ffffffff81635715)
Location: include/asm-generic/qspinlock.h:51
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:report_access
```
```
In lib/lockref.c (ffffffff816dc370)
Location: include/asm-generic/qspinlock.h:51
Inline: True
Inline callers:
  - lib/lockref.c:lockref_mark_dead
```
```
In drivers/iommu/intel/iommu.c (ffffffff8195841b)
Location: include/asm-generic/qspinlock.h:51
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_enforce_cache_coherency
  - drivers/iommu/intel/iommu.c:intel_iommu_enforce_cache_coherency
  - drivers/iommu/intel/iommu.c:__dmar_remove_one_dev_info
  - drivers/iommu/intel/iommu.c:__dmar_remove_one_dev_info
  - drivers/iommu/intel/iommu.c:__dmar_remove_one_dev_info
  - drivers/iommu/intel/iommu.c:__dmar_remove_one_dev_info
  - drivers/iommu/intel/iommu.c:__dmar_remove_one_dev_info
  - drivers/iommu/intel/iommu.c:domain_add_dev_info
  - drivers/iommu/intel/iommu.c:domain_add_dev_info
  - drivers/iommu/intel/iommu.c:iommu_enable_dev_iotlb
  - drivers/iommu/intel/iommu.c:iommu_enable_dev_iotlb
  - drivers/iommu/intel/iommu.c:iommu_support_dev_iotlb
  - drivers/iommu/intel/iommu.c:domain_update_iommu_cap
  - drivers/iommu/intel/iommu.c:domain_update_iommu_cap
```
```
In drivers/iommu/dma-iommu.c (ffffffff8196ae07)
Location: include/asm-generic/qspinlock.h:51
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_free_iova
  - drivers/iommu/dma-iommu.c:iommu_dma_free_iova
  - drivers/iommu/dma-iommu.c:fq_ring_free
```
```
In drivers/iommu/iova.c (ffffffff8196dfe2)
Location: include/asm-generic/qspinlock.h:51
Inline: True
Inline callers:
  - drivers/iommu/iova.c:free_iova
  - drivers/iommu/iova.c:find_iova
  - drivers/iommu/iova.c:remove_iova
```
```
In drivers/iommu/virtio-iommu.c (ffffffff8196f4b3)
Location: include/asm-generic/qspinlock.h:51
Inline: True
Inline callers:
  - drivers/iommu/virtio-iommu.c:__viommu_add_req
  - drivers/iommu/virtio-iommu.c:__viommu_sync_req
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff81ac6a1f)
Location: include/asm-generic/qspinlock.h:51
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_unlink
  - drivers/usb/dwc2/hcd_queue.c:dwc2_do_unreserve
```
```
In net/core/dev.c (0)
Location: include/asm-generic/qspinlock.h:51
Inline: True
```
```
In net/sched/sch_generic.c (ffffffff81c96fef)
Location: include/asm-generic/qspinlock.h:51
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
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
In arch/x86/kernel/hpet.c (ffffffff810b477f)
Location: include/asm-generic/qspinlock.h:51
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:read_hpet
  - arch/x86/kernel/hpet.c:read_hpet
```
```
In kernel/fork.c (ffffffff810e83f1)
Location: include/asm-generic/qspinlock.h:51
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/sched/core.c (ffffffff811316d7)
Location: include/asm-generic/qspinlock.h:51
Inline: True
```
```
In kernel/irq/migration.c (ffffffff811a284b)
Location: include/asm-generic/qspinlock.h:51
Inline: True
Inline callers:
  - kernel/irq/migration.c:irq_move_masked_irq
```
```
In kernel/audit_tree.c (ffffffff8123339e)
Location: include/asm-generic/qspinlock.h:51
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_tree_freeing_mark
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:create_chunk
  - kernel/audit_tree.c:replace_chunk
```
```
In kernel/debug/debug_core.c (ffffffff81239fb3)
Location: include/asm-generic/qspinlock.h:51
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_call_nmi_hook
```
```
In kernel/seccomp.c (ffffffff8124aeb8)
Location: include/asm-generic/qspinlock.h:51
Inline: True
Inline callers:
  - kernel/seccomp.c:do_seccomp
  - kernel/seccomp.c:do_seccomp
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_attach_filter
  - kernel/seccomp.c:seccomp_attach_filter
  - kernel/seccomp.c:seccomp_attach_filter
  - kernel/seccomp.c:seccomp_attach_filter
```
```
In mm/list_lru.c (ffffffff813abc35)
Location: include/asm-generic/qspinlock.h:51
Inline: True
Inline callers:
  - mm/list_lru.c:__list_lru_walk_one
  - mm/list_lru.c:__list_lru_walk_one
```
```
In mm/pgtable-generic.c (ffffffff813d4b5e)
Location: include/asm-generic/qspinlock.h:51
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pgtable_trans_huge_withdraw
  - mm/pgtable-generic.c:pgtable_trans_huge_deposit
```
```
In mm/swapfile.c (ffffffff813fa76f)
Location: include/asm-generic/qspinlock.h:51
Inline: True
Inline callers:
  - mm/swapfile.c:_enable_swap_info
```
```
In mm/zswap.c (ffffffff81402c68)
Location: include/asm-generic/qspinlock.h:51
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_pool_empty
```
```
In mm/huge_memory.c (ffffffff8143f0f8)
Location: include/asm-generic/qspinlock.h:51
Inline: True
Inline callers:
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:follow_devmap_pmd
```
```
In mm/zsmalloc.c (ffffffff81467bce)
Location: include/asm-generic/qspinlock.h:51
Inline: True
Inline callers:
  - mm/zsmalloc.c:__free_zspage
```
```
In fs/dcache.c (ffffffff8149ea17)
Location: include/asm-generic/qspinlock.h:51
Inline: True
Inline callers:
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_add
  - fs/dcache.c:__d_instantiate
```
```
In fs/fs-writeback.c (ffffffff814c0295)
Location: include/asm-generic/qspinlock.h:51
Inline: True
Inline callers:
  - fs/fs-writeback.c:queue_io
  - fs/fs-writeback.c:redirty_tail_locked
  - fs/fs-writeback.c:inode_cgwb_move_to_attached
  - fs/fs-writeback.c:inode_cgwb_move_to_attached
  - fs/fs-writeback.c:inode_io_list_move_locked
  - fs/fs-writeback.c:inode_io_list_move_locked
```
```
In fs/notify/notification.c (ffffffff814dd233)
Location: include/asm-generic/qspinlock.h:51
Inline: True
Inline callers:
  - fs/notify/notification.c:fsnotify_flush_notify
  - fs/notify/notification.c:fsnotify_remove_first_event
  - fs/notify/notification.c:fsnotify_remove_first_event
  - fs/notify/notification.c:fsnotify_remove_first_event
```
```
In fs/notify/mark.c (ffffffff814dd6c5)
Location: include/asm-generic/qspinlock.h:51
Inline: True
Inline callers:
  - fs/notify/mark.c:__fsnotify_recalc_mask
```
```
In fs/notify/dnotify/dnotify.c (ffffffff814dfb48)
Location: include/asm-generic/qspinlock.h:51
Inline: True
Inline callers:
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:dnotify_flush
  - fs/notify/dnotify/dnotify.c:dnotify_handle_event
```
```
In fs/notify/inotify/inotify_user.c (ffffffff814e0705)
Location: include/asm-generic/qspinlock.h:51
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_remove_from_idr
  - fs/notify/inotify/inotify_user.c:inotify_idr_find
  - fs/notify/inotify/inotify_user.c:inotify_poll
```
```
In fs/notify/fanotify/fanotify.c (ffffffff814e1765)
Location: include/asm-generic/qspinlock.h:51
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_insert_event
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff814e4fdd)
Location: include/asm-generic/qspinlock.h:51
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
  - fs/notify/fanotify/fanotify_user.c:fanotify_write
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_poll
```
```
In fs/ext4/mballoc.c (ffffffff81590774)
Location: include/asm-generic/qspinlock.h:51
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_try_to_trim_range
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_find_extent
  - fs/ext4/mballoc.c:mb_free_blocks
```
```
In fs/jbd2/transaction.c (ffffffff815deae4)
Location: include/asm-generic/qspinlock.h:51
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:__jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer
```
```
In fs/jbd2/checkpoint.c (ffffffff815e25e5)
Location: include/asm-generic/qspinlock.h:51
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_journal_drop_transaction
```
```
In ipc/sem.c (ffffffff8164533e)
Location: include/asm-generic/qspinlock.h:51
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:lookup_undo
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:freeary
```
```
In security/yama/yama_lsm.c (ffffffff816ec405)
Location: include/asm-generic/qspinlock.h:51
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:report_access
```
```
In lib/lockref.c (ffffffff817cc040)
Location: include/asm-generic/qspinlock.h:51
Inline: True
Inline callers:
  - lib/lockref.c:lockref_mark_dead
```
```
In drivers/iommu/intel/iommu.c (ffffffff81abf4ea)
Location: include/asm-generic/qspinlock.h:51
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_enforce_cache_coherency
  - drivers/iommu/intel/iommu.c:intel_iommu_enforce_cache_coherency
```
```
In drivers/iommu/dma-iommu.c (ffffffff81ad52e7)
Location: include/asm-generic/qspinlock.h:51
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_free_iova
  - drivers/iommu/dma-iommu.c:iommu_dma_free_iova
  - drivers/iommu/dma-iommu.c:fq_ring_free
```
```
In drivers/iommu/iova.c (ffffffff81ad8b9d)
Location: include/asm-generic/qspinlock.h:51
Inline: True
Inline callers:
  - drivers/iommu/iova.c:iova_magazine_free_pfns
  - drivers/iommu/iova.c:free_iova
  - drivers/iommu/iova.c:find_iova
  - drivers/iommu/iova.c:remove_iova
```
```
In drivers/iommu/virtio-iommu.c (ffffffff81ada1f3)
Location: include/asm-generic/qspinlock.h:51
Inline: True
Inline callers:
  - drivers/iommu/virtio-iommu.c:__viommu_add_req
  - drivers/iommu/virtio-iommu.c:__viommu_sync_req
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff81c50bcf)
Location: include/asm-generic/qspinlock.h:51
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_unlink
  - drivers/usb/dwc2/hcd_queue.c:dwc2_do_unreserve
```
```
In net/core/dev.c (0)
Location: include/asm-generic/qspinlock.h:51
Inline: True
```
```
In net/sched/sch_generic.c (ffffffff81e52dcf)
Location: include/asm-generic/qspinlock.h:51
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
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
In arch/x86/kernel/hpet.c (ffffffff810b785a)
Location: include/asm-generic/qspinlock.h:51
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:read_hpet
  - arch/x86/kernel/hpet.c:read_hpet
```
```
In kernel/fork.c (ffffffff810f4050)
Location: include/asm-generic/qspinlock.h:51
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/sched/core.c (ffffffff8113f91d)
Location: include/asm-generic/qspinlock.h:51
Inline: True
```
```
In kernel/irq/migration.c (ffffffff811b474b)
Location: include/asm-generic/qspinlock.h:51
Inline: True
Inline callers:
  - kernel/irq/migration.c:irq_move_masked_irq
```
```
In kernel/audit_tree.c (ffffffff8124a04d)
Location: include/asm-generic/qspinlock.h:51
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_tree_freeing_mark
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:create_chunk
  - kernel/audit_tree.c:replace_chunk
```
```
In kernel/debug/debug_core.c (ffffffff81250fc3)
Location: include/asm-generic/qspinlock.h:51
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_call_nmi_hook
```
```
In kernel/seccomp.c (ffffffff81262229)
Location: include/asm-generic/qspinlock.h:51
Inline: True
Inline callers:
  - kernel/seccomp.c:do_seccomp
  - kernel/seccomp.c:do_seccomp
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_attach_filter
  - kernel/seccomp.c:seccomp_attach_filter
  - kernel/seccomp.c:seccomp_attach_filter
  - kernel/seccomp.c:seccomp_attach_filter
```
```
In mm/list_lru.c (ffffffff813dffce)
Location: include/asm-generic/qspinlock.h:51
Inline: True
Inline callers:
  - mm/list_lru.c:__list_lru_walk_one
  - mm/list_lru.c:__list_lru_walk_one
```
```
In mm/pgtable-generic.c (ffffffff8140952e)
Location: include/asm-generic/qspinlock.h:51
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pgtable_trans_huge_withdraw
  - mm/pgtable-generic.c:pgtable_trans_huge_deposit
```
```
In mm/swapfile.c (ffffffff8142d6af)
Location: include/asm-generic/qspinlock.h:51
Inline: True
Inline callers:
  - mm/swapfile.c:_enable_swap_info
  - mm/swapfile.c:__del_from_avail_list
```
```
In mm/zswap.c (ffffffff814361d7)
Location: include/asm-generic/qspinlock.h:51
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_pool_empty
```
```
In mm/huge_memory.c (ffffffff814748b7)
Location: include/asm-generic/qspinlock.h:51
Inline: True
Inline callers:
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:follow_devmap_pmd
```
```
In mm/zsmalloc.c (ffffffff8149cc74)
Location: include/asm-generic/qspinlock.h:51
Inline: True
Inline callers:
  - mm/zsmalloc.c:__free_zspage
```
```
In fs/dcache.c (ffffffff814d3d37)
Location: include/asm-generic/qspinlock.h:51
Inline: True
Inline callers:
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_add
  - fs/dcache.c:__d_instantiate
```
```
In fs/fs-writeback.c (ffffffff814f5455)
Location: include/asm-generic/qspinlock.h:51
Inline: True
Inline callers:
  - fs/fs-writeback.c:queue_io
  - fs/fs-writeback.c:redirty_tail_locked
  - fs/fs-writeback.c:inode_cgwb_move_to_attached
  - fs/fs-writeback.c:inode_cgwb_move_to_attached
  - fs/fs-writeback.c:inode_io_list_move_locked
  - fs/fs-writeback.c:inode_io_list_move_locked
```
```
In fs/notify/notification.c (ffffffff81513a8f)
Location: include/asm-generic/qspinlock.h:51
Inline: True
Inline callers:
  - fs/notify/notification.c:fsnotify_flush_notify
  - fs/notify/notification.c:fsnotify_remove_first_event
  - fs/notify/notification.c:fsnotify_remove_first_event
  - fs/notify/notification.c:fsnotify_remove_first_event
```
```
In fs/notify/mark.c (ffffffff81513f25)
Location: include/asm-generic/qspinlock.h:51
Inline: True
Inline callers:
  - fs/notify/mark.c:__fsnotify_recalc_mask
```
```
In fs/notify/dnotify/dnotify.c (ffffffff815163cc)
Location: include/asm-generic/qspinlock.h:51
Inline: True
Inline callers:
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:dnotify_flush
  - fs/notify/dnotify/dnotify.c:dnotify_handle_event
```
```
In fs/notify/inotify/inotify_user.c (ffffffff81516fb5)
Location: include/asm-generic/qspinlock.h:51
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_remove_from_idr
  - fs/notify/inotify/inotify_user.c:inotify_idr_find
  - fs/notify/inotify/inotify_user.c:inotify_poll
```
```
In fs/notify/fanotify/fanotify.c (ffffffff81518025)
Location: include/asm-generic/qspinlock.h:51
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_insert_event
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff8151b22d)
Location: include/asm-generic/qspinlock.h:51
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_poll
```
```
In fs/ext4/mballoc.c (ffffffff815c7927)
Location: include/asm-generic/qspinlock.h:51
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_try_to_trim_range
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_find_extent
  - fs/ext4/mballoc.c:mb_free_blocks
```
```
In fs/jbd2/transaction.c (ffffffff81616544)
Location: include/asm-generic/qspinlock.h:51
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:__jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer
```
```
In fs/jbd2/checkpoint.c (ffffffff81619f55)
Location: include/asm-generic/qspinlock.h:51
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_journal_drop_transaction
```
```
In ipc/sem.c (ffffffff8167d830)
Location: include/asm-generic/qspinlock.h:51
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:lookup_undo
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:freeary
```
```
In security/yama/yama_lsm.c (ffffffff81726835)
Location: include/asm-generic/qspinlock.h:51
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:report_access
```
```
In lib/lockref.c (ffffffff8180a480)
Location: include/asm-generic/qspinlock.h:51
Inline: True
Inline callers:
  - lib/lockref.c:lockref_mark_dead
```
```
In drivers/iommu/intel/iommu.c (ffffffff81b0beda)
Location: include/asm-generic/qspinlock.h:51
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_enforce_cache_coherency
  - drivers/iommu/intel/iommu.c:intel_iommu_enforce_cache_coherency
```
```
In drivers/iommu/dma-iommu.c (ffffffff81b23a97)
Location: include/asm-generic/qspinlock.h:51
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_free_iova
  - drivers/iommu/dma-iommu.c:iommu_dma_free_iova
  - drivers/iommu/dma-iommu.c:fq_ring_free
```
```
In drivers/iommu/iova.c (ffffffff81b26b35)
Location: include/asm-generic/qspinlock.h:51
Inline: True
Inline callers:
  - drivers/iommu/iova.c:iova_magazine_free_pfns
  - drivers/iommu/iova.c:free_iova
  - drivers/iommu/iova.c:find_iova
  - drivers/iommu/iova.c:remove_iova
```
```
In drivers/iommu/virtio-iommu.c (ffffffff81b28323)
Location: include/asm-generic/qspinlock.h:51
Inline: True
Inline callers:
  - drivers/iommu/virtio-iommu.c:__viommu_add_req
  - drivers/iommu/virtio-iommu.c:__viommu_sync_req
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff81cb814f)
Location: include/asm-generic/qspinlock.h:51
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_unlink
  - drivers/usb/dwc2/hcd_queue.c:dwc2_do_unreserve
```
```
In net/core/dev.c (0)
Location: include/asm-generic/qspinlock.h:51
Inline: True
```
```
In net/sched/sch_generic.c (ffffffff81eae65b)
Location: include/asm-generic/qspinlock.h:51
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
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
In arch/x86/kernel/hpet.c (ffffffff810bec9a)
Location: include/asm-generic/qspinlock.h:51
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:read_hpet
  - arch/x86/kernel/hpet.c:read_hpet
```
```
In kernel/fork.c (ffffffff810fd412)
Location: include/asm-generic/qspinlock.h:51
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/sched/core.c (ffffffff8114a87d)
Location: include/asm-generic/qspinlock.h:51
Inline: True
```
```
In kernel/irq/migration.c (ffffffff811c45cb)
Location: include/asm-generic/qspinlock.h:51
Inline: True
Inline callers:
  - kernel/irq/migration.c:irq_move_masked_irq
```
```
In kernel/rcu/tree.c (ffffffff811d3f1f)
Location: include/asm-generic/qspinlock.h:51
Inline: True
Inline callers:
  - kernel/rcu/tree.c:show_rcu_nocb_state
  - kernel/rcu/tree.c:show_rcu_nocb_state
  - kernel/rcu/tree.c:show_rcu_nocb_state
  - kernel/rcu/tree.c:show_rcu_nocb_gp_state
```
```
In kernel/audit_tree.c (ffffffff81263f5d)
Location: include/asm-generic/qspinlock.h:51
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_tree_freeing_mark
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:create_chunk
  - kernel/audit_tree.c:replace_chunk
```
```
In kernel/debug/debug_core.c (ffffffff8126ae13)
Location: include/asm-generic/qspinlock.h:51
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_call_nmi_hook
```
```
In kernel/seccomp.c (ffffffff8127c469)
Location: include/asm-generic/qspinlock.h:51
Inline: True
Inline callers:
  - kernel/seccomp.c:do_seccomp
  - kernel/seccomp.c:do_seccomp
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_attach_filter
  - kernel/seccomp.c:seccomp_attach_filter
  - kernel/seccomp.c:seccomp_attach_filter
  - kernel/seccomp.c:seccomp_attach_filter
```
```
In mm/list_lru.c (ffffffff8140a87e)
Location: include/asm-generic/qspinlock.h:51
Inline: True
Inline callers:
  - mm/list_lru.c:__list_lru_walk_one
  - mm/list_lru.c:__list_lru_walk_one
```
```
In mm/pgtable-generic.c (ffffffff81435d1e)
Location: include/asm-generic/qspinlock.h:51
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pgtable_trans_huge_withdraw
  - mm/pgtable-generic.c:pgtable_trans_huge_deposit
```
```
In mm/swapfile.c (ffffffff8146722f)
Location: include/asm-generic/qspinlock.h:51
Inline: True
Inline callers:
  - mm/swapfile.c:_enable_swap_info
  - mm/swapfile.c:__del_from_avail_list
```
```
In mm/zswap.c (ffffffff8146fc13)
Location: include/asm-generic/qspinlock.h:51
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_pool_empty
```
```
In mm/huge_memory.c (ffffffff814a3f08)
Location: include/asm-generic/qspinlock.h:51
Inline: True
Inline callers:
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:follow_devmap_pmd
```
```
In mm/zsmalloc.c (ffffffff814cc444)
Location: include/asm-generic/qspinlock.h:51
Inline: True
Inline callers:
  - mm/zsmalloc.c:__free_zspage
```
```
In fs/dcache.c (ffffffff815063fc)
Location: include/asm-generic/qspinlock.h:51
Inline: True
Inline callers:
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_add
  - fs/dcache.c:__d_instantiate
```
```
In fs/fs-writeback.c (ffffffff81529b65)
Location: include/asm-generic/qspinlock.h:51
Inline: True
Inline callers:
  - fs/fs-writeback.c:queue_io
  - fs/fs-writeback.c:redirty_tail_locked
  - fs/fs-writeback.c:inode_cgwb_move_to_attached
  - fs/fs-writeback.c:inode_cgwb_move_to_attached
  - fs/fs-writeback.c:inode_io_list_move_locked
  - fs/fs-writeback.c:inode_io_list_move_locked
```
```
In fs/notify/notification.c (ffffffff81547f1f)
Location: include/asm-generic/qspinlock.h:51
Inline: True
Inline callers:
  - fs/notify/notification.c:fsnotify_flush_notify
  - fs/notify/notification.c:fsnotify_remove_first_event
  - fs/notify/notification.c:fsnotify_remove_first_event
  - fs/notify/notification.c:fsnotify_remove_first_event
```
```
In fs/notify/mark.c (ffffffff815483f5)
Location: include/asm-generic/qspinlock.h:51
Inline: True
Inline callers:
  - fs/notify/mark.c:__fsnotify_recalc_mask
```
```
In fs/notify/dnotify/dnotify.c (ffffffff8154a78a)
Location: include/asm-generic/qspinlock.h:51
Inline: True
Inline callers:
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:dnotify_flush
  - fs/notify/dnotify/dnotify.c:dnotify_handle_event
```
```
In fs/notify/inotify/inotify_user.c (ffffffff8154b3a5)
Location: include/asm-generic/qspinlock.h:51
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_remove_from_idr
  - fs/notify/inotify/inotify_user.c:inotify_idr_find
  - fs/notify/inotify/inotify_user.c:inotify_poll
```
```
In fs/notify/fanotify/fanotify.c (ffffffff8154c405)
Location: include/asm-generic/qspinlock.h:51
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_insert_event
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff8154f82d)
Location: include/asm-generic/qspinlock.h:51
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_poll
```
```
In fs/ext4/mballoc.c (ffffffff815ff561)
Location: include/asm-generic/qspinlock.h:51
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_try_to_trim_range
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_find_extent
  - fs/ext4/mballoc.c:mb_free_blocks
```
```
In fs/jbd2/transaction.c (ffffffff8164f364)
Location: include/asm-generic/qspinlock.h:51
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:__jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer
```
```
In fs/jbd2/checkpoint.c (ffffffff81652eb5)
Location: include/asm-generic/qspinlock.h:51
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_journal_drop_transaction
```
```
In ipc/sem.c (ffffffff816b9bfe)
Location: include/asm-generic/qspinlock.h:51
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:lookup_undo
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:freeary
```
```
In security/yama/yama_lsm.c (ffffffff81767a55)
Location: include/asm-generic/qspinlock.h:51
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:report_access
```
```
In lib/lockref.c (ffffffff81850c60)
Location: include/asm-generic/qspinlock.h:51
Inline: True
Inline callers:
  - lib/lockref.c:lockref_mark_dead
```
```
In drivers/iommu/intel/iommu.c (ffffffff81b5fc7a)
Location: include/asm-generic/qspinlock.h:51
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_enforce_cache_coherency
  - drivers/iommu/intel/iommu.c:intel_iommu_enforce_cache_coherency
```
```
In drivers/iommu/dma-iommu.c (ffffffff81b79557)
Location: include/asm-generic/qspinlock.h:51
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:queue_iova
  - drivers/iommu/dma-iommu.c:queue_iova
  - drivers/iommu/dma-iommu.c:fq_ring_free_locked
```
```
In drivers/iommu/iova.c (ffffffff81b7dc35)
Location: include/asm-generic/qspinlock.h:51
Inline: True
Inline callers:
  - drivers/iommu/iova.c:iova_magazine_free_pfns
  - drivers/iommu/iova.c:free_iova
  - drivers/iommu/iova.c:find_iova
  - drivers/iommu/iova.c:remove_iova
```
```
In drivers/iommu/virtio-iommu.c (ffffffff81b7f293)
Location: include/asm-generic/qspinlock.h:51
Inline: True
Inline callers:
  - drivers/iommu/virtio-iommu.c:__viommu_add_req
  - drivers/iommu/virtio-iommu.c:__viommu_sync_req
```
```
In drivers/gpu/drm/drm_file.c (ffffffff81c972b5)
Location: include/asm-generic/qspinlock.h:51
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_file.c:drm_send_event_helper
```
```
In drivers/gpu/drm/drm_vblank.c (ffffffff81cb687b)
Location: include/asm-generic/qspinlock.h:51
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_vblank.c:drm_handle_vblank_events
  - drivers/gpu/drm/drm_vblank.c:drm_vblank_restore
  - drivers/gpu/drm/drm_vblank.c:drm_vblank_restore
  - drivers/gpu/drm/drm_vblank.c:drm_vblank_enable
  - drivers/gpu/drm/drm_vblank.c:drm_crtc_arm_vblank_event
  - drivers/gpu/drm/drm_vblank.c:drm_vblank_disable_and_save
  - drivers/gpu/drm/drm_vblank.c:store_vblank
```
```
In drivers/gpu/drm/drm_vblank_work.c (ffffffff81cb7cc8)
Location: include/asm-generic/qspinlock.h:51
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_vblank_work.c:drm_vblank_cancel_pending_works
  - drivers/gpu/drm/drm_vblank_work.c:drm_handle_vblank_works
```
```
In drivers/gpu/drm/drm_debugfs_crc.c (ffffffff81cbb208)
Location: include/asm-generic/qspinlock.h:51
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_debugfs_crc.c:crtc_crc_poll
  - drivers/gpu/drm/drm_debugfs_crc.c:crtc_crc_read
  - drivers/gpu/drm/drm_debugfs_crc.c:crtc_crc_read
  - drivers/gpu/drm/drm_debugfs_crc.c:crtc_crc_read
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff81d6cebf)
Location: include/asm-generic/qspinlock.h:51
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_unlink
  - drivers/usb/dwc2/hcd_queue.c:dwc2_do_unreserve
```
```
In net/core/dev.c (0)
Location: include/asm-generic/qspinlock.h:51
Inline: True
```
```
In net/sched/sch_generic.c (ffffffff81f710d6)
Location: include/asm-generic/qspinlock.h:51
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
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
In virt/kvm/arm/mmu.c (ffff8000100c97ec)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - virt/kvm/arm/mmu.c:unmap_stage2_range
```
```
In kernel/fork.c (ffff8000100f3f24)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/signal.c (ffff80001010d7b0)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - kernel/signal.c:__send_signal
```
```
In kernel/printk/printk_safe.c (ffff800010176e28)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:printk_safe_flush_on_panic
```
```
In kernel/audit_tree.c (ffff8000101f499c)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - kernel/audit_tree.c:prune_tree_chunks
```
```
In kernel/debug/debug_core.c (ffff8000101fab90)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_nmicallback
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/seccomp.c (ffff8000102098f8)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_set_mode_filter
```
```
In mm/list_lru.c (ffff8000102eeb40)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - mm/list_lru.c:__list_lru_walk_one
  - mm/list_lru.c:__list_lru_walk_one
```
```
In mm/pgtable-generic.c (ffff8000103083d8)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pgtable_trans_huge_withdraw
  - mm/pgtable-generic.c:pgtable_trans_huge_deposit
```
```
In mm/swapfile.c (ffff800010323838)
Location: include/asm-generic/qspinlock.h:20
Inline: True
```
```
In mm/frontswap.c (ffff80001032a2e0)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - mm/frontswap.c:frontswap_shrink
  - mm/frontswap.c:frontswap_shrink
```
```
In mm/zswap.c (ffff80001032bbb4)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:zswap_pool_put
```
```
In mm/huge_memory.c (ffff800010357200)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_devmap_pmd
```
```
In mm/zsmalloc.c (ffff800010374538)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - mm/zsmalloc.c:__free_zspage
```
```
In fs/dcache.c (ffff8000103a8b10)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:d_add
  - fs/dcache.c:__d_instantiate
```
```
In fs/fs-writeback.c (ffff8000103c6cf0)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - fs/fs-writeback.c:queue_io
```
```
In fs/notify/notification.c (ffff8000103e8c80)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - fs/notify/notification.c:fsnotify_flush_notify
  - fs/notify/notification.c:fsnotify_peek_first_event
```
```
In fs/notify/mark.c (ffff8000103e9310)
Location: include/asm-generic/qspinlock.h:20
Inline: True
```
```
In fs/notify/dnotify/dnotify.c (ffff8000103eb080)
Location: include/asm-generic/qspinlock.h:20
Inline: True
```
```
In fs/notify/inotify/inotify_user.c (ffff8000103ebe9c)
Location: include/asm-generic/qspinlock.h:20
Inline: True
```
```
In fs/notify/fanotify/fanotify_user.c (ffff8000103edda4)
Location: include/asm-generic/qspinlock.h:20
Inline: True
```
```
In fs/ext4/mballoc.c (ffff800010493fa4)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_find_extent
  - fs/ext4/mballoc.c:mb_free_blocks
```
```
In fs/jbd2/transaction.c (ffff8000104cc8d0)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:__jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer
```
```
In fs/jbd2/checkpoint.c (ffff8000104d0fa0)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_journal_drop_transaction
```
```
In ipc/sem.c (ffff800010525914)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:freeary
```
```
In security/yama/yama_lsm.c (ffff8000105aa590)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:report_access
```
```
In lib/lockref.c (ffff800010628ff0)
Location: include/asm-generic/qspinlock.h:20
Inline: True
```
```
In drivers/iommu/iova.c (ffff8000108cdbb8)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - drivers/iommu/iova.c:queue_iova
  - drivers/iommu/iova.c:queue_iova
```
```
In drivers/iommu/rockchip-iommu.c (ffff8000108d9194)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - drivers/iommu/rockchip-iommu.c:rk_iommu_map
  - drivers/iommu/rockchip-iommu.c:rk_iommu_map
```
```
In drivers/iommu/virtio-iommu.c (ffff8000108dbc24)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - drivers/iommu/virtio-iommu.c:__viommu_add_req
  - drivers/iommu/virtio-iommu.c:__viommu_sync_req
```
```
In drivers/usb/dwc2/hcd_queue.c (ffff800010a4beac)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_do_unreserve
```
```
In net/core/dev.c (0)
Location: include/asm-generic/qspinlock.h:20
Inline: True
```
```
In net/sched/sch_generic.c (ffff800010c3a2a8)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
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
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff8107544f)
Location: include/asm-generic/qspinlock.h:20
Inline: True
```
```
In kernel/fork.c (ffffffff810991a3)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/signal.c (ffffffff810abe9c)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - kernel/signal.c:__send_signal
```
```
In kernel/printk/printk_safe.c (ffffffff8110dd25)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:printk_safe_flush_on_panic
```
```
In kernel/irq/migration.c (ffffffff8111894f)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - kernel/irq/migration.c:irq_move_masked_irq
```
```
In kernel/audit_tree.c (ffffffff8117812a)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - kernel/audit_tree.c:prune_tree_chunks
```
```
In kernel/debug/debug_core.c (ffffffff8117d5d5)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_nmicallback
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/seccomp.c (ffffffff8118a598)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_set_mode_filter
```
```
In mm/list_lru.c (ffffffff8124f785)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - mm/list_lru.c:__list_lru_walk_one
  - mm/list_lru.c:__list_lru_walk_one
```
```
In mm/pgtable-generic.c (ffffffff8126af9a)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pgtable_trans_huge_withdraw
  - mm/pgtable-generic.c:pgtable_trans_huge_deposit
```
```
In mm/swapfile.c (ffffffff81280e31)
Location: include/asm-generic/qspinlock.h:20
Inline: True
```
```
In mm/frontswap.c (ffffffff812865f5)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - mm/frontswap.c:frontswap_shrink
  - mm/frontswap.c:frontswap_shrink
```
```
In mm/zswap.c (ffffffff8128748d)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_pool_empty
```
```
In mm/huge_memory.c (ffffffff812aea80)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:follow_devmap_pmd
```
```
In mm/zsmalloc.c (ffffffff812c7f19)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - mm/zsmalloc.c:__free_zspage
```
```
In fs/dcache.c (ffffffff812f2543)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:d_add
  - fs/dcache.c:__d_instantiate
```
```
In fs/fs-writeback.c (ffffffff81307e35)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - fs/fs-writeback.c:queue_io
```
```
In fs/notify/notification.c (ffffffff81325581)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - fs/notify/notification.c:fsnotify_flush_notify
  - fs/notify/notification.c:fsnotify_peek_first_event
```
```
In fs/notify/mark.c (ffffffff81325a55)
Location: include/asm-generic/qspinlock.h:20
Inline: True
```
```
In fs/notify/dnotify/dnotify.c (ffffffff81326cf5)
Location: include/asm-generic/qspinlock.h:20
Inline: True
```
```
In fs/notify/inotify/inotify_user.c (ffffffff81327905)
Location: include/asm-generic/qspinlock.h:20
Inline: True
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff813295f5)
Location: include/asm-generic/qspinlock.h:20
Inline: True
```
```
In fs/ext4/mballoc.c (ffffffff813b5895)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_find_extent
  - fs/ext4/mballoc.c:mb_free_blocks
```
```
In fs/jbd2/transaction.c (ffffffff813ea7de)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:__jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer
```
```
In fs/jbd2/checkpoint.c (ffffffff813edb45)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_journal_drop_transaction
```
```
In ipc/sem.c (ffffffff814360b3)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:freeary
```
```
In security/yama/yama_lsm.c (ffffffff814ab315)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:report_access
```
```
In lib/lockref.c (ffffffff815185c0)
Location: include/asm-generic/qspinlock.h:20
Inline: True
```
```
In drivers/iommu/iova.c (ffffffff816a319d)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - drivers/iommu/iova.c:queue_iova
  - drivers/iommu/iova.c:queue_iova
```
```
In drivers/iommu/intel-iommu.c (ffffffff816b082c)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_aux_detach_device
  - drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info
  - drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info
  - drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info
  - drivers/iommu/intel-iommu.c:domain_detach_iommu
  - drivers/iommu/intel-iommu.c:domain_detach_iommu
  - drivers/iommu/intel-iommu.c:iommu_enable_dev_iotlb
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff817cb175)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_do_unreserve
```
```
In net/core/dev.c (0)
Location: include/asm-generic/qspinlock.h:20
Inline: True
```
```
In net/sched/sch_generic.c (ffffffff8192e719)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
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
In arch/x86/kernel/hpet.c (ffffffff8106527e)
Location: include/asm-generic/qspinlock.h:20
Inline: True
```
```
In kernel/fork.c (ffffffff81087bf3)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/signal.c (ffffffff8109a82c)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - kernel/signal.c:__send_signal
```
```
In kernel/printk/printk_safe.c (ffffffff810fea85)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:printk_safe_flush_on_panic
```
```
In kernel/irq/migration.c (ffffffff811099bf)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - kernel/irq/migration.c:irq_move_masked_irq
```
```
In kernel/rcu/tree.c (ffffffff81115108)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - kernel/rcu/tree.c:show_rcu_gp_kthreads
  - kernel/rcu/tree.c:show_rcu_gp_kthreads
  - kernel/rcu/tree.c:show_rcu_gp_kthreads
  - kernel/rcu/tree.c:show_rcu_gp_kthreads
```
```
In kernel/audit_tree.c (ffffffff8116b2ca)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - kernel/audit_tree.c:prune_tree_chunks
```
```
In kernel/debug/debug_core.c (ffffffff81170725)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_nmicallback
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/seccomp.c (ffffffff8117d6c8)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_set_mode_filter
```
```
In mm/list_lru.c (ffffffff81242725)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - mm/list_lru.c:__list_lru_walk_one
  - mm/list_lru.c:__list_lru_walk_one
```
```
In mm/pgtable-generic.c (ffffffff8125cfca)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pgtable_trans_huge_withdraw
  - mm/pgtable-generic.c:pgtable_trans_huge_deposit
```
```
In mm/swapfile.c (ffffffff81272ca1)
Location: include/asm-generic/qspinlock.h:20
Inline: True
```
```
In mm/frontswap.c (ffffffff81278455)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - mm/frontswap.c:frontswap_shrink
  - mm/frontswap.c:frontswap_shrink
```
```
In mm/zswap.c (ffffffff812792ed)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_pool_empty
```
```
In mm/huge_memory.c (ffffffff8129ffc3)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:follow_devmap_pmd
```
```
In mm/zsmalloc.c (ffffffff812b8f59)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - mm/zsmalloc.c:__free_zspage
```
```
In fs/dcache.c (ffffffff812e3173)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:d_add
  - fs/dcache.c:__d_instantiate
```
```
In fs/fs-writeback.c (ffffffff812f8a55)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - fs/fs-writeback.c:queue_io
```
```
In fs/notify/notification.c (ffffffff81316121)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - fs/notify/notification.c:fsnotify_flush_notify
  - fs/notify/notification.c:fsnotify_peek_first_event
```
```
In fs/notify/mark.c (ffffffff813165f5)
Location: include/asm-generic/qspinlock.h:20
Inline: True
```
```
In fs/notify/dnotify/dnotify.c (ffffffff81317895)
Location: include/asm-generic/qspinlock.h:20
Inline: True
```
```
In fs/notify/inotify/inotify_user.c (ffffffff813184a5)
Location: include/asm-generic/qspinlock.h:20
Inline: True
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff8131a195)
Location: include/asm-generic/qspinlock.h:20
Inline: True
```
```
In fs/ext4/mballoc.c (ffffffff813a6325)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_find_extent
  - fs/ext4/mballoc.c:mb_free_blocks
```
```
In fs/jbd2/transaction.c (ffffffff813db25e)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:__jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer
```
```
In fs/jbd2/checkpoint.c (ffffffff813de5c5)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_journal_drop_transaction
```
```
In ipc/sem.c (ffffffff81426b33)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:freeary
```
```
In security/yama/yama_lsm.c (ffffffff8149bd35)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:report_access
```
```
In lib/lockref.c (ffffffff815088c0)
Location: include/asm-generic/qspinlock.h:20
Inline: True
```
```
In drivers/iommu/iova.c (ffffffff81680b8d)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - drivers/iommu/iova.c:queue_iova
  - drivers/iommu/iova.c:queue_iova
```
```
In drivers/iommu/intel-iommu.c (ffffffff8168e17c)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_aux_detach_device
  - drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info
  - drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info
  - drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info
  - drivers/iommu/intel-iommu.c:domain_detach_iommu
  - drivers/iommu/intel-iommu.c:domain_detach_iommu
  - drivers/iommu/intel-iommu.c:iommu_enable_dev_iotlb
```
```
In net/core/dev.c (0)
Location: include/asm-generic/qspinlock.h:20
Inline: True
```
```
In net/sched/sch_generic.c (ffffffff818e8219)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
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
In arch/x86/kernel/hpet.c (ffffffff810753ff)
Location: include/asm-generic/qspinlock.h:20
Inline: True
```
```
In kernel/fork.c (ffffffff81099153)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/signal.c (ffffffff810ab3fc)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - kernel/signal.c:__send_signal
```
```
In kernel/printk/printk_safe.c (ffffffff8110bc15)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:printk_safe_flush_on_panic
```
```
In kernel/irq/migration.c (ffffffff8111683f)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - kernel/irq/migration.c:irq_move_masked_irq
```
```
In kernel/audit_tree.c (ffffffff81175efa)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - kernel/audit_tree.c:prune_tree_chunks
```
```
In kernel/debug/debug_core.c (ffffffff8117b3a5)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_nmicallback
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/seccomp.c (ffffffff81188368)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_set_mode_filter
```
```
In mm/list_lru.c (ffffffff8124d525)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - mm/list_lru.c:__list_lru_walk_one
  - mm/list_lru.c:__list_lru_walk_one
```
```
In mm/pgtable-generic.c (ffffffff81268d3a)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pgtable_trans_huge_withdraw
  - mm/pgtable-generic.c:pgtable_trans_huge_deposit
```
```
In mm/swapfile.c (ffffffff8127ec41)
Location: include/asm-generic/qspinlock.h:20
Inline: True
```
```
In mm/frontswap.c (ffffffff81284405)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - mm/frontswap.c:frontswap_shrink
  - mm/frontswap.c:frontswap_shrink
```
```
In mm/zswap.c (ffffffff8128529d)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_pool_empty
```
```
In mm/huge_memory.c (ffffffff812ac890)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:follow_devmap_pmd
```
```
In mm/zsmalloc.c (ffffffff812c5d29)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - mm/zsmalloc.c:__free_zspage
```
```
In fs/dcache.c (ffffffff812f0353)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:d_add
  - fs/dcache.c:__d_instantiate
```
```
In fs/fs-writeback.c (ffffffff81305c25)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - fs/fs-writeback.c:queue_io
```
```
In fs/notify/notification.c (ffffffff81323051)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - fs/notify/notification.c:fsnotify_flush_notify
  - fs/notify/notification.c:fsnotify_peek_first_event
```
```
In fs/notify/mark.c (ffffffff81323525)
Location: include/asm-generic/qspinlock.h:20
Inline: True
```
```
In fs/notify/dnotify/dnotify.c (ffffffff813247c5)
Location: include/asm-generic/qspinlock.h:20
Inline: True
```
```
In fs/notify/inotify/inotify_user.c (ffffffff813253d5)
Location: include/asm-generic/qspinlock.h:20
Inline: True
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff813270c5)
Location: include/asm-generic/qspinlock.h:20
Inline: True
```
```
In fs/ext4/mballoc.c (ffffffff813b30f5)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_find_extent
  - fs/ext4/mballoc.c:mb_free_blocks
```
```
In fs/jbd2/transaction.c (ffffffff813e7b5e)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:__jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer
```
```
In fs/jbd2/checkpoint.c (ffffffff813eaec5)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_journal_drop_transaction
```
```
In ipc/sem.c (ffffffff81432253)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:freeary
```
```
In security/yama/yama_lsm.c (ffffffff814a73b5)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:report_access
```
```
In lib/lockref.c (ffffffff81514650)
Location: include/asm-generic/qspinlock.h:20
Inline: True
```
```
In drivers/iommu/iova.c (ffffffff816d140d)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - drivers/iommu/iova.c:queue_iova
  - drivers/iommu/iova.c:queue_iova
```
```
In drivers/iommu/intel-iommu.c (ffffffff816dea0c)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_aux_detach_device
  - drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info
  - drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info
  - drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info
  - drivers/iommu/intel-iommu.c:domain_detach_iommu
  - drivers/iommu/intel-iommu.c:domain_detach_iommu
  - drivers/iommu/intel-iommu.c:iommu_enable_dev_iotlb
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff81807c15)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_do_unreserve
```
```
In net/core/dev.c (0)
Location: include/asm-generic/qspinlock.h:20
Inline: True
```
```
In net/sched/sch_generic.c (ffffffff8197f8a9)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
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
In arch/x86/kernel/hpet.c (ffffffff8107745f)
Location: include/asm-generic/qspinlock.h:20
Inline: True
```
```
In kernel/fork.c (ffffffff810a0d8c)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/signal.c (ffffffff810b34dc)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - kernel/signal.c:__send_signal
```
```
In kernel/printk/printk_safe.c (ffffffff81117125)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:printk_safe_flush_on_panic
```
```
In kernel/irq/migration.c (ffffffff81121e7f)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - kernel/irq/migration.c:irq_move_masked_irq
```
```
In kernel/audit_tree.c (ffffffff811837e2)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - kernel/audit_tree.c:prune_tree_chunks
```
```
In kernel/debug/debug_core.c (ffffffff81188cc5)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_nmicallback
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/seccomp.c (ffffffff81195cc8)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_set_mode_filter
```
```
In mm/list_lru.c (ffffffff8125d0a5)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - mm/list_lru.c:__list_lru_walk_one
  - mm/list_lru.c:__list_lru_walk_one
```
```
In mm/pgtable-generic.c (ffffffff812786ca)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pgtable_trans_huge_withdraw
  - mm/pgtable-generic.c:pgtable_trans_huge_deposit
```
```
In mm/swapfile.c (ffffffff8128e7e1)
Location: include/asm-generic/qspinlock.h:20
Inline: True
```
```
In mm/frontswap.c (ffffffff81293ff1)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - mm/frontswap.c:frontswap_shrink
  - mm/frontswap.c:frontswap_shrink
```
```
In mm/zswap.c (ffffffff812953f2)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_pool_empty
```
```
In mm/huge_memory.c (ffffffff812bcc10)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:follow_devmap_pmd
```
```
In mm/zsmalloc.c (ffffffff812d7579)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - mm/zsmalloc.c:__free_zspage
```
```
In fs/dcache.c (ffffffff81301459)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:d_add
  - fs/dcache.c:__d_instantiate
```
```
In fs/fs-writeback.c (ffffffff81317165)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - fs/fs-writeback.c:queue_io
```
```
In fs/notify/notification.c (ffffffff81334d93)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - fs/notify/notification.c:fsnotify_flush_notify
  - fs/notify/notification.c:fsnotify_peek_first_event
```
```
In fs/notify/mark.c (ffffffff813353b5)
Location: include/asm-generic/qspinlock.h:20
Inline: True
```
```
In fs/notify/dnotify/dnotify.c (ffffffff81336545)
Location: include/asm-generic/qspinlock.h:20
Inline: True
```
```
In fs/notify/inotify/inotify_user.c (ffffffff81337775)
Location: include/asm-generic/qspinlock.h:20
Inline: True
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff81339225)
Location: include/asm-generic/qspinlock.h:20
Inline: True
```
```
In fs/ext4/mballoc.c (ffffffff813c7c3e)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_find_extent
  - fs/ext4/mballoc.c:mb_free_blocks
```
```
In fs/jbd2/transaction.c (ffffffff813fd35e)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:__jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer
```
```
In fs/jbd2/checkpoint.c (ffffffff81400825)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_journal_drop_transaction
```
```
In ipc/sem.c (ffffffff81449321)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:freeary
```
```
In security/yama/yama_lsm.c (ffffffff814bfd15)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:report_access
```
```
In lib/lockref.c (ffffffff8152e0a0)
Location: include/asm-generic/qspinlock.h:20
Inline: True
```
```
In drivers/iommu/iova.c (ffffffff816ebd1d)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - drivers/iommu/iova.c:queue_iova
  - drivers/iommu/iova.c:queue_iova
```
```
In drivers/iommu/intel-iommu.c (ffffffff816f8a3c)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_aux_detach_device
  - drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info
  - drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info
  - drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info
  - drivers/iommu/intel-iommu.c:domain_detach_iommu
  - drivers/iommu/intel-iommu.c:domain_detach_iommu
  - drivers/iommu/intel-iommu.c:iommu_enable_dev_iotlb
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff81821d25)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_do_unreserve
```
```
In net/core/dev.c (0)
Location: include/asm-generic/qspinlock.h:20
Inline: True
```
```
In net/sched/sch_generic.c (ffffffff819a1e05)
Location: include/asm-generic/qspinlock.h:20
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
```
</details>
</li>
</ul>

## Differences
