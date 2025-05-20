# Function: <code>arch_spin_is_locked</code>

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
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (c0352924)
Location: arch/arm/include/asm/spinlock.h:119
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/signal.c (c0365b24)
Location: arch/arm/include/asm/spinlock.h:119
Inline: True
Inline callers:
  - kernel/signal.c:__send_signal
```
```
In kernel/printk/printk_safe.c (c03c8ba0)
Location: arch/arm/include/asm/spinlock.h:119
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:printk_safe_flush_on_panic
```
```
In kernel/audit_tree.c (c04349d8)
Location: arch/arm/include/asm/spinlock.h:119
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_tree_freeing_mark
  - kernel/audit_tree.c:prune_tree_chunks
```
```
In kernel/debug/debug_core.c (c043aca0)
Location: arch/arm/include/asm/spinlock.h:119
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_nmicallback
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/seccomp.c (c0448a10)
Location: arch/arm/include/asm/spinlock.h:119
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
In mm/list_lru.c (c0512a88)
Location: arch/arm/include/asm/spinlock.h:119
Inline: True
Inline callers:
  - mm/list_lru.c:__list_lru_walk_one
  - mm/list_lru.c:__list_lru_walk_one
```
```
In mm/swapfile.c (c053b808)
Location: arch/arm/include/asm/spinlock.h:119
Inline: True
```
```
In mm/frontswap.c (c0540b70)
Location: arch/arm/include/asm/spinlock.h:119
Inline: True
Inline callers:
  - mm/frontswap.c:frontswap_shrink
  - mm/frontswap.c:frontswap_shrink
```
```
In mm/zswap.c (c0541c70)
Location: arch/arm/include/asm/spinlock.h:119
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:zswap_pool_put
```
```
In mm/zsmalloc.c (c056104c)
Location: arch/arm/include/asm/spinlock.h:119
Inline: True
Inline callers:
  - mm/zsmalloc.c:__free_zspage
```
```
In fs/dcache.c (c058a15c)
Location: arch/arm/include/asm/spinlock.h:119
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:d_add
  - fs/dcache.c:__d_instantiate
```
```
In fs/fs-writeback.c (c05a16e8)
Location: arch/arm/include/asm/spinlock.h:119
Inline: True
Inline callers:
  - fs/fs-writeback.c:queue_io
```
```
In fs/notify/notification.c (c05c0478)
Location: arch/arm/include/asm/spinlock.h:119
Inline: True
Inline callers:
  - fs/notify/notification.c:fsnotify_flush_notify
  - fs/notify/notification.c:fsnotify_peek_first_event
```
```
In fs/notify/mark.c (c05c0b9c)
Location: arch/arm/include/asm/spinlock.h:119
Inline: True
```
```
In fs/notify/dnotify/dnotify.c (c05c2150)
Location: arch/arm/include/asm/spinlock.h:119
Inline: True
```
```
In fs/notify/inotify/inotify_user.c (c05c2f08)
Location: arch/arm/include/asm/spinlock.h:119
Inline: True
```
```
In fs/notify/fanotify/fanotify_user.c (c05c49d4)
Location: arch/arm/include/asm/spinlock.h:119
Inline: True
```
```
In fs/ext4/mballoc.c (c0655610)
Location: arch/arm/include/asm/spinlock.h:119
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_find_extent
  - fs/ext4/mballoc.c:mb_free_blocks
```
```
In fs/jbd2/transaction.c (c06901d8)
Location: arch/arm/include/asm/spinlock.h:119
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:__jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer
```
```
In fs/jbd2/checkpoint.c (c0693aec)
Location: arch/arm/include/asm/spinlock.h:119
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_journal_drop_transaction
```
```
In ipc/sem.c (c06dfde0)
Location: arch/arm/include/asm/spinlock.h:119
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:ksys_semctl
  - ipc/sem.c:semctl_main
  - ipc/sem.c:freeary
```
```
In security/yama/yama_lsm.c (c075a4e0)
Location: arch/arm/include/asm/spinlock.h:119
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:report_access
```
```
In lib/lockref.c (c07d0a10)
Location: arch/arm/include/asm/spinlock.h:119
Inline: True
```
```
In drivers/iommu/rockchip-iommu.c (c09c6b8c)
Location: arch/arm/include/asm/spinlock.h:119
Inline: True
Inline callers:
  - drivers/iommu/rockchip-iommu.c:rk_iommu_map
  - drivers/iommu/rockchip-iommu.c:rk_iommu_map
```
```
In drivers/usb/dwc2/hcd_queue.c (c0b1e1f4)
Location: arch/arm/include/asm/spinlock.h:119
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_do_unreserve
```
```
In net/core/dev.c (0)
Location: arch/arm/include/asm/spinlock.h:119
Inline: True
```
```
In net/sched/sch_generic.c (c0d4c454)
Location: arch/arm/include/asm/spinlock.h:119
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
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
In arch/powerpc/mm/book3s64/hash_pgtable.c (c00000000008bb2c)
Location: arch/powerpc/include/asm/spinlock.h:56
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/hash_pgtable.c:hash__pgtable_trans_huge_withdraw
  - arch/powerpc/mm/book3s64/hash_pgtable.c:hash__pgtable_trans_huge_deposit
```
```
In arch/powerpc/mm/book3s64/radix_pgtable.c (c00000000009542c)
Location: arch/powerpc/include/asm/spinlock.h:56
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/radix_pgtable.c:radix__pgtable_trans_huge_withdraw
  - arch/powerpc/mm/book3s64/radix_pgtable.c:radix__pgtable_trans_huge_deposit
```
```
In kernel/fork.c (c00000000013a27c)
Location: arch/powerpc/include/asm/spinlock.h:56
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/signal.c (c000000000154a6c)
Location: arch/powerpc/include/asm/spinlock.h:56
Inline: True
Inline callers:
  - kernel/signal.c:__send_signal
  - kernel/signal.c:ptrace_trap_notify
```
```
In kernel/printk/printk_safe.c (c0000000001d0678)
Location: arch/powerpc/include/asm/spinlock.h:56
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:printk_safe_flush_on_panic
```
```
In kernel/audit_tree.c (c00000000026981c)
Location: arch/powerpc/include/asm/spinlock.h:56
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_tree_freeing_mark
  - kernel/audit_tree.c:prune_tree_chunks
```
```
In kernel/debug/debug_core.c (c0000000002726d0)
Location: arch/powerpc/include/asm/spinlock.h:56
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_nmicallback
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/seccomp.c (c000000000286acc)
Location: arch/powerpc/include/asm/spinlock.h:56
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
In mm/list_lru.c (c0000000003b2dc0)
Location: arch/powerpc/include/asm/spinlock.h:56
Inline: True
Inline callers:
  - mm/list_lru.c:__list_lru_walk_one
  - mm/list_lru.c:__list_lru_walk_one
```
```
In mm/swapfile.c (c0000000003f8d80)
Location: arch/powerpc/include/asm/spinlock.h:56
Inline: True
Inline callers:
  - mm/swapfile.c:_enable_swap_info
```
```
In mm/frontswap.c (c0000000004014e0)
Location: arch/powerpc/include/asm/spinlock.h:56
Inline: True
Inline callers:
  - mm/frontswap.c:frontswap_shrink
  - mm/frontswap.c:frontswap_shrink
  - mm/frontswap.c:__frontswap_curr_pages
```
```
In mm/zswap.c (c000000000403650)
Location: arch/powerpc/include/asm/spinlock.h:56
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:zswap_pool_current
```
```
In mm/huge_memory.c (c00000000043f140)
Location: arch/powerpc/include/asm/spinlock.h:56
Inline: True
Inline callers:
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_devmap_pmd
```
```
In mm/zsmalloc.c (c0000000004672a8)
Location: arch/powerpc/include/asm/spinlock.h:56
Inline: True
Inline callers:
  - mm/zsmalloc.c:__free_zspage
```
```
In fs/dcache.c (c0000000004a3630)
Location: arch/powerpc/include/asm/spinlock.h:56
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:d_add
  - fs/dcache.c:__d_instantiate
```
```
In fs/fs-writeback.c (c0000000004c5108)
Location: arch/powerpc/include/asm/spinlock.h:56
Inline: True
Inline callers:
  - fs/fs-writeback.c:queue_io
  - fs/fs-writeback.c:inode_io_list_del_locked
  - fs/fs-writeback.c:inode_io_list_move_locked
```
```
In fs/notify/notification.c (c0000000004ef77c)
Location: arch/powerpc/include/asm/spinlock.h:56
Inline: True
Inline callers:
  - fs/notify/notification.c:fsnotify_flush_notify
  - fs/notify/notification.c:fsnotify_peek_first_event
  - fs/notify/notification.c:fsnotify_remove_first_event
  - fs/notify/notification.c:fsnotify_remove_queued_event
```
```
In fs/notify/mark.c (c0000000004efd88)
Location: arch/powerpc/include/asm/spinlock.h:56
Inline: True
Inline callers:
  - fs/notify/mark.c:__fsnotify_recalc_mask
```
```
In fs/notify/dnotify/dnotify.c (c0000000004f22c0)
Location: arch/powerpc/include/asm/spinlock.h:56
Inline: True
Inline callers:
  - fs/notify/dnotify/dnotify.c:dnotify_recalc_inode_mask
```
```
In fs/notify/inotify/inotify_user.c (c0000000004f3230)
Location: arch/powerpc/include/asm/spinlock.h:56
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_idr_find_locked
```
```
In fs/notify/fanotify/fanotify_user.c (c0000000004f5aa0)
Location: arch/powerpc/include/asm/spinlock.h:56
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:finish_permission_event
```
```
In fs/ext4/mballoc.c (c0000000005bcf88)
Location: arch/powerpc/include/asm/spinlock.h:56
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_find_extent
  - fs/ext4/mballoc.c:mb_free_blocks
```
```
In fs/jbd2/transaction.c (c000000000605fb0)
Location: arch/powerpc/include/asm/spinlock.h:56
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:__jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer
```
```
In fs/jbd2/checkpoint.c (c00000000060a24c)
Location: arch/powerpc/include/asm/spinlock.h:56
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_journal_drop_transaction
```
```
In ipc/sem.c (c00000000066fe60)
Location: arch/powerpc/include/asm/spinlock.h:56
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:lookup_undo
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:freeary
```
```
In security/yama/yama_lsm.c (c0000000007282d8)
Location: arch/powerpc/include/asm/spinlock.h:56
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:report_access
```
```
In lib/lockref.c (c0000000007ca9c0)
Location: arch/powerpc/include/asm/spinlock.h:56
Inline: True
Inline callers:
  - lib/lockref.c:lockref_mark_dead
```
```
In drivers/usb/dwc2/hcd_queue.c (c000000000b12f0c)
Location: arch/powerpc/include/asm/spinlock.h:56
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_do_unreserve
```
```
In net/core/dev.c (0)
Location: arch/powerpc/include/asm/spinlock.h:56
Inline: True
```
```
In net/sched/sch_generic.c (c000000000d3328c)
Location: arch/powerpc/include/asm/spinlock.h:56
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
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
