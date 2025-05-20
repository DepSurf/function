# Function: <code>hlist_del_init</code>

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
In arch/x86/kernel/kvm.c (ffffffff81063b90)
Location: include/linux/list.h:631
Inline: True
```
```
In kernel/user.c (ffffffff8108c7c9)
Location: include/linux/list.h:631
Inline: True
Inline callers:
  - kernel/user.c:free_uid
```
```
In kernel/workqueue.c (ffffffff8109a02e)
Location: include/linux/list.h:631
Inline: True
Inline callers:
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:put_unbound_pool
```
```
In kernel/cgroup.c (ffffffff81114bff)
Location: include/linux/list.h:631
Inline: True
```
```
In mm/ksm.c (ffffffff811e5186)
Location: include/linux/list.h:631
Inline: True
Inline callers:
  - mm/ksm.c:run_store
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:__ksm_exit
```
```
In mm/huge_memory.c (ffffffff811f4309)
Location: include/linux/list.h:631
Inline: True
Inline callers:
  - mm/huge_memory.c:collect_mm_slot
  - mm/huge_memory.c:__khugepaged_exit
```
```
In fs/super.c (ffffffff8120e972)
Location: include/linux/list.h:631
Inline: True
Inline callers:
  - fs/super.c:generic_shutdown_super
```
```
In fs/dcache.c (ffffffff812236d0)
Location: include/linux/list.h:631
Inline: True
Inline callers:
  - fs/dcache.c:__dentry_kill
  - fs/dcache.c:d_delete
```
```
In fs/inode.c (ffffffff812266f1)
Location: include/linux/list.h:631
Inline: True
Inline callers:
  - fs/inode.c:__remove_inode_hash
```
```
In fs/namespace.c (ffffffff8122bf2b)
Location: include/linux/list.h:631
Inline: True
Inline callers:
  - fs/namespace.c:unhash_mnt
  - fs/namespace.c:attach_recursive_mnt
```
```
In fs/fs_pin.c (ffffffff81241f2d)
Location: include/linux/list.h:631
Inline: True
Inline callers:
  - fs/fs_pin.c:pin_remove
  - fs/fs_pin.c:pin_remove
```
```
In fs/locks.c (ffffffff8125f0dd)
Location: include/linux/list.h:631
Inline: True
Inline callers:
  - fs/locks.c:locks_delete_block
  - fs/locks.c:posix_unblock_lock
  - fs/locks.c:locks_wake_up_blocks
  - fs/locks.c:locks_unlink_lock_ctx
```
```
In fs/quota/dquot.c (ffffffff81271493)
Location: include/linux/list.h:631
Inline: True
Inline callers:
  - fs/quota/dquot.c:dqcache_shrink_scan
  - fs/quota/dquot.c:dquot_disable
```
```
In fs/fat/inode.c (ffffffff812fb4e7)
Location: include/linux/list.h:631
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_detach
  - fs/fat/inode.c:fat_detach
```
```
In block/elevator.c (ffffffff813b38f0)
Location: include/linux/list.h:631
Inline: True
Inline callers:
  - block/elevator.c:elv_rqhash_reposition
```
```
In block/blk-ioc.c (ffffffff813bec94)
Location: include/linux/list.h:631
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_destroy_icq
```
```
In drivers/clk/clk.c (ffffffff816e718b)
Location: include/linux/list.h:631
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:clk_unregister
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
In arch/x86/kernel/kvm.c (ffffffff810637b0)
Location: include/linux/list.h:631
Inline: True
```
```
In kernel/user.c (ffffffff8108f839)
Location: include/linux/list.h:631
Inline: True
Inline callers:
  - kernel/user.c:free_uid
```
```
In kernel/workqueue.c (ffffffff8109e225)
Location: include/linux/list.h:631
Inline: True
Inline callers:
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:process_one_work
```
```
In kernel/cgroup.c (ffffffff81fab40b)
Location: include/linux/list.h:631
Inline: True
Inline callers:
  - kernel/cgroup.c:cgroup_init
```
```
In mm/ksm.c (ffffffff81203d1c)
Location: include/linux/list.h:631
Inline: True
Inline callers:
  - mm/ksm.c:run_store
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/khugepaged.c (ffffffff812196e9)
Location: include/linux/list.h:631
Inline: True
Inline callers:
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
```
```
In fs/super.c (ffffffff812353a5)
Location: include/linux/list.h:631
Inline: True
Inline callers:
  - fs/super.c:generic_shutdown_super
```
```
In fs/dcache.c (ffffffff8124a6ec)
Location: include/linux/list.h:631
Inline: True
Inline callers:
  - fs/dcache.c:dentry_unlink_inode
```
```
In fs/inode.c (ffffffff8124edb1)
Location: include/linux/list.h:631
Inline: True
Inline callers:
  - fs/inode.c:__remove_inode_hash
```
```
In fs/namespace.c (ffffffff8125667a)
Location: include/linux/list.h:631
Inline: True
Inline callers:
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:unhash_mnt
```
```
In fs/fs_pin.c (ffffffff8126a27d)
Location: include/linux/list.h:631
Inline: True
Inline callers:
  - fs/fs_pin.c:pin_remove
  - fs/fs_pin.c:pin_remove
```
```
In fs/locks.c (ffffffff8128aba3)
Location: include/linux/list.h:631
Inline: True
Inline callers:
  - fs/locks.c:posix_unblock_lock
  - fs/locks.c:locks_unlink_lock_ctx
  - fs/locks.c:locks_wake_up_blocks
  - fs/locks.c:locks_delete_block
```
```
In fs/quota/dquot.c (ffffffff8129fe1a)
Location: include/linux/list.h:631
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dqcache_shrink_scan
```
```
In fs/fat/inode.c (ffffffff8132f1d7)
Location: include/linux/list.h:631
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_detach
  - fs/fat/inode.c:fat_detach
```
```
In block/elevator.c (ffffffff813f7850)
Location: include/linux/list.h:631
Inline: True
Inline callers:
  - block/elevator.c:elv_rqhash_reposition
```
```
In block/blk-ioc.c (ffffffff81402c64)
Location: include/linux/list.h:631
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_destroy_icq
```
```
In drivers/clk/clk.c (ffffffff8174b78b)
Location: include/linux/list.h:631
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:clk_unregister
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
In arch/x86/kernel/kvm.c (ffffffff81066c60)
Location: include/linux/list.h:647
Inline: True
```
```
In kernel/user.c (ffffffff810947b9)
Location: include/linux/list.h:647
Inline: True
Inline callers:
  - kernel/user.c:free_uid
```
```
In kernel/workqueue.c (ffffffff810a2d85)
Location: include/linux/list.h:647
Inline: True
Inline callers:
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:process_one_work
```
```
In kernel/ucount.c (ffffffff810ad61a)
Location: include/linux/list.h:647
Inline: True
Inline callers:
  - kernel/ucount.c:put_ucounts
```
```
In kernel/cgroup.c (ffffffff81fe7681)
Location: include/linux/list.h:647
Inline: True
Inline callers:
  - kernel/cgroup.c:cgroup_init
```
```
In mm/ksm.c (ffffffff81215d3c)
Location: include/linux/list.h:647
Inline: True
Inline callers:
  - mm/ksm.c:run_store
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/khugepaged.c (ffffffff8122bc69)
Location: include/linux/list.h:647
Inline: True
Inline callers:
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
```
```
In fs/super.c (ffffffff81247f45)
Location: include/linux/list.h:647
Inline: True
Inline callers:
  - fs/super.c:generic_shutdown_super
```
```
In fs/dcache.c (ffffffff8125d66c)
Location: include/linux/list.h:647
Inline: True
Inline callers:
  - fs/dcache.c:dentry_unlink_inode
```
```
In fs/inode.c (ffffffff81261dc1)
Location: include/linux/list.h:647
Inline: True
Inline callers:
  - fs/inode.c:__remove_inode_hash
```
```
In fs/namespace.c (ffffffff8126a1f6)
Location: include/linux/list.h:647
Inline: True
Inline callers:
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:mnt_change_mountpoint
  - fs/namespace.c:unhash_mnt
```
```
In fs/fs_pin.c (ffffffff8127d22d)
Location: include/linux/list.h:647
Inline: True
Inline callers:
  - fs/fs_pin.c:pin_remove
  - fs/fs_pin.c:pin_remove
```
```
In fs/locks.c (ffffffff8129f933)
Location: include/linux/list.h:647
Inline: True
Inline callers:
  - fs/locks.c:posix_unblock_lock
  - fs/locks.c:locks_unlink_lock_ctx
  - fs/locks.c:locks_wake_up_blocks
  - fs/locks.c:locks_delete_block
```
```
In fs/quota/dquot.c (ffffffff812b5307)
Location: include/linux/list.h:647
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dqcache_shrink_scan
```
```
In fs/fat/inode.c (ffffffff81344f37)
Location: include/linux/list.h:647
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_detach
  - fs/fat/inode.c:fat_detach
```
```
In block/elevator.c (ffffffff814113e1)
Location: include/linux/list.h:647
Inline: True
Inline callers:
  - block/elevator.c:elv_rqhash_find
  - block/elevator.c:elv_rqhash_reposition
```
```
In block/blk-ioc.c (ffffffff8141c994)
Location: include/linux/list.h:647
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_destroy_icq
```
```
In drivers/clk/clk.c (ffffffff81533ffb)
Location: include/linux/list.h:647
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:clk_unregister
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
In arch/x86/kernel/kvm.c (ffffffff81065f3d)
Location: include/linux/list.h:660
Inline: True
```
```
In kernel/user.c (ffffffff810918aa)
Location: include/linux/list.h:660
Inline: True
Inline callers:
  - kernel/user.c:free_uid
```
```
In kernel/workqueue.c (ffffffff810a00b8)
Location: include/linux/list.h:660
Inline: True
Inline callers:
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:process_one_work
```
```
In kernel/ucount.c (ffffffff810aa1f3)
Location: include/linux/list.h:660
Inline: True
Inline callers:
  - kernel/ucount.c:put_ucounts
```
```
In kernel/cgroup/cgroup.c (ffffffff820c7c0c)
Location: include/linux/list.h:660
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
```
```
In mm/ksm.c (ffffffff81221436)
Location: include/linux/list.h:660
Inline: True
Inline callers:
  - mm/ksm.c:run_store
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/khugepaged.c (ffffffff81237799)
Location: include/linux/list.h:660
Inline: True
Inline callers:
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
```
```
In fs/super.c (ffffffff81253755)
Location: include/linux/list.h:660
Inline: True
Inline callers:
  - fs/super.c:generic_shutdown_super
```
```
In fs/dcache.c (ffffffff8126b048)
Location: include/linux/list.h:660
Inline: True
Inline callers:
  - fs/dcache.c:dentry_unlink_inode
```
```
In fs/inode.c (ffffffff8126f681)
Location: include/linux/list.h:660
Inline: True
Inline callers:
  - fs/inode.c:__remove_inode_hash
```
```
In fs/namespace.c (ffffffff81277a0f)
Location: include/linux/list.h:660
Inline: True
Inline callers:
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:mnt_change_mountpoint
  - fs/namespace.c:unhash_mnt
```
```
In fs/fs_pin.c (ffffffff8128adbd)
Location: include/linux/list.h:660
Inline: True
Inline callers:
  - fs/fs_pin.c:pin_remove
  - fs/fs_pin.c:pin_remove
```
```
In fs/locks.c (ffffffff812ae7a3)
Location: include/linux/list.h:660
Inline: True
Inline callers:
  - fs/locks.c:posix_unblock_lock
  - fs/locks.c:locks_unlink_lock_ctx
  - fs/locks.c:locks_wake_up_blocks
  - fs/locks.c:locks_delete_block
```
```
In fs/quota/dquot.c (ffffffff812c1af2)
Location: include/linux/list.h:660
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dqcache_shrink_scan
```
```
In fs/fat/inode.c (ffffffff813599a7)
Location: include/linux/list.h:660
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_detach
  - fs/fat/inode.c:fat_detach
```
```
In block/elevator.c (ffffffff8141eedc)
Location: include/linux/list.h:660
Inline: True
Inline callers:
  - block/elevator.c:elv_rqhash_find
  - block/elevator.c:elv_rqhash_reposition
```
```
In block/blk-ioc.c (ffffffff8142a8c4)
Location: include/linux/list.h:660
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_destroy_icq
```
```
In drivers/clk/clk.c (ffffffff8154715b)
Location: include/linux/list.h:660
Inline: True
```
```
In drivers/dax/super.c (ffffffff8163d386)
Location: include/linux/list.h:660
Inline: True
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
In arch/x86/kernel/apic/vector.c (ffffffff8105b227)
Location: include/linux/list.h:661
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:free_moved_vector
  - arch/x86/kernel/apic/vector.c:clear_irq_vector
```
```
In arch/x86/kernel/kvm.c (ffffffff81069e36)
Location: include/linux/list.h:661
Inline: True
```
```
In kernel/user.c (ffffffff81098736)
Location: include/linux/list.h:661
Inline: True
Inline callers:
  - kernel/user.c:free_uid
```
```
In kernel/workqueue.c (ffffffff810a6dcf)
Location: include/linux/list.h:661
Inline: True
Inline callers:
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:process_one_work
```
```
In kernel/ucount.c (ffffffff810b0a4f)
Location: include/linux/list.h:661
Inline: True
Inline callers:
  - kernel/ucount.c:put_ucounts
```
```
In kernel/cgroup/cgroup.c (ffffffff826d0283)
Location: include/linux/list.h:661
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
```
```
In mm/ksm.c (ffffffff8123c742)
Location: include/linux/list.h:661
Inline: True
Inline callers:
  - mm/ksm.c:run_store
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/khugepaged.c (ffffffff81256b25)
Location: include/linux/list.h:661
Inline: True
Inline callers:
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
```
```
In fs/super.c (ffffffff812757d1)
Location: include/linux/list.h:661
Inline: True
Inline callers:
  - fs/super.c:generic_shutdown_super
```
```
In fs/dcache.c (ffffffff8128d8b4)
Location: include/linux/list.h:661
Inline: True
Inline callers:
  - fs/dcache.c:dentry_unlink_inode
```
```
In fs/inode.c (ffffffff81291f9a)
Location: include/linux/list.h:661
Inline: True
Inline callers:
  - fs/inode.c:__remove_inode_hash
```
```
In fs/namespace.c (ffffffff8129a446)
Location: include/linux/list.h:661
Inline: True
Inline callers:
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:mnt_change_mountpoint
  - fs/namespace.c:unhash_mnt
```
```
In fs/fs_pin.c (ffffffff812ad8f9)
Location: include/linux/list.h:661
Inline: True
Inline callers:
  - fs/fs_pin.c:pin_remove
  - fs/fs_pin.c:pin_remove
```
```
In fs/locks.c (ffffffff812d218f)
Location: include/linux/list.h:661
Inline: True
Inline callers:
  - fs/locks.c:posix_unblock_lock
  - fs/locks.c:locks_unlink_lock_ctx
  - fs/locks.c:locks_wake_up_blocks
  - fs/locks.c:locks_delete_block
```
```
In fs/quota/dquot.c (ffffffff812e5913)
Location: include/linux/list.h:661
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dqcache_shrink_scan
```
```
In fs/fat/inode.c (ffffffff8137e6ab)
Location: include/linux/list.h:661
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_detach
  - fs/fat/inode.c:fat_detach
```
```
In block/elevator.c (ffffffff814499b1)
Location: include/linux/list.h:661
Inline: True
Inline callers:
  - block/elevator.c:elv_rqhash_find
  - block/elevator.c:elv_rqhash_reposition
```
```
In block/blk-ioc.c (ffffffff81455ab0)
Location: include/linux/list.h:661
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_destroy_icq
```
```
In drivers/clk/clk.c (ffffffff815aae74)
Location: include/linux/list.h:661
Inline: True
```
```
In drivers/dax/super.c (ffffffff816a60c2)
Location: include/linux/list.h:661
Inline: True
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
In arch/x86/kernel/apic/vector.c (ffffffff8105e167)
Location: include/linux/list.h:661
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:free_moved_vector
  - arch/x86/kernel/apic/vector.c:clear_irq_vector
```
```
In arch/x86/kernel/kvm.c (ffffffff8106cab5)
Location: include/linux/list.h:661
Inline: True
```
```
In kernel/user.c (ffffffff8109be78)
Location: include/linux/list.h:661
Inline: True
Inline callers:
  - kernel/user.c:free_uid
```
```
In kernel/workqueue.c (ffffffff810acc95)
Location: include/linux/list.h:661
Inline: True
Inline callers:
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:process_one_work
```
```
In kernel/ucount.c (ffffffff810b785f)
Location: include/linux/list.h:661
Inline: True
Inline callers:
  - kernel/ucount.c:put_ucounts
```
```
In kernel/cgroup/cgroup.c (ffffffff826fa9bb)
Location: include/linux/list.h:661
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
```
```
In mm/ksm.c (ffffffff8125fcd3)
Location: include/linux/list.h:661
Inline: True
Inline callers:
  - mm/ksm.c:run_store
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/khugepaged.c (ffffffff8127aaf5)
Location: include/linux/list.h:661
Inline: True
Inline callers:
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
```
```
In fs/super.c (ffffffff8129cad5)
Location: include/linux/list.h:661
Inline: True
Inline callers:
  - fs/super.c:generic_shutdown_super
```
```
In fs/dcache.c (ffffffff812b4ba8)
Location: include/linux/list.h:661
Inline: True
Inline callers:
  - fs/dcache.c:dentry_unlink_inode
```
```
In fs/inode.c (ffffffff812b92fa)
Location: include/linux/list.h:661
Inline: True
Inline callers:
  - fs/inode.c:__remove_inode_hash
```
```
In fs/namespace.c (ffffffff812c04aa)
Location: include/linux/list.h:661
Inline: True
Inline callers:
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:mnt_change_mountpoint
  - fs/namespace.c:unhash_mnt
```
```
In fs/fs_pin.c (ffffffff812d56a9)
Location: include/linux/list.h:661
Inline: True
Inline callers:
  - fs/fs_pin.c:pin_remove
  - fs/fs_pin.c:pin_remove
```
```
In fs/locks.c (ffffffff812fe63f)
Location: include/linux/list.h:661
Inline: True
Inline callers:
  - fs/locks.c:posix_unblock_lock
  - fs/locks.c:locks_unlink_lock_ctx
  - fs/locks.c:locks_wake_up_blocks
  - fs/locks.c:locks_delete_block
```
```
In fs/quota/dquot.c (ffffffff81312f91)
Location: include/linux/list.h:661
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dqcache_shrink_scan
```
```
In fs/fat/inode.c (ffffffff813af307)
Location: include/linux/list.h:661
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_detach
  - fs/fat/inode.c:fat_detach
```
```
In block/elevator.c (ffffffff8147c6b5)
Location: include/linux/list.h:661
Inline: True
Inline callers:
  - block/elevator.c:elv_rqhash_find
  - block/elevator.c:elv_rqhash_reposition
```
```
In block/blk-ioc.c (ffffffff81488ef0)
Location: include/linux/list.h:661
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_destroy_icq
```
```
In drivers/clk/clk.c (ffffffff815e2e74)
Location: include/linux/list.h:661
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:clk_unregister
```
```
In drivers/dax/super.c (ffffffff816e1e72)
Location: include/linux/list.h:661
Inline: True
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
In arch/x86/kernel/apic/vector.c (ffffffff81063df7)
Location: include/linux/list.h:714
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:free_moved_vector
  - arch/x86/kernel/apic/vector.c:clear_irq_vector
```
```
In arch/x86/kernel/kvm.c (ffffffff81072bc5)
Location: include/linux/list.h:714
Inline: True
```
```
In kernel/fork.c (ffffffff810940e6)
Location: include/linux/list.h:714
Inline: True
```
```
In kernel/user.c (ffffffff810a4087)
Location: include/linux/list.h:714
Inline: True
Inline callers:
  - kernel/user.c:free_uid
```
```
In kernel/workqueue.c (ffffffff810b6515)
Location: include/linux/list.h:714
Inline: True
Inline callers:
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:process_one_work
```
```
In kernel/ucount.c (ffffffff810c095f)
Location: include/linux/list.h:714
Inline: True
Inline callers:
  - kernel/ucount.c:put_ucounts
```
```
In kernel/cgroup/cgroup.c (ffffffff828b18b7)
Location: include/linux/list.h:714
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
```
```
In mm/ksm.c (ffffffff81274413)
Location: include/linux/list.h:714
Inline: True
Inline callers:
  - mm/ksm.c:run_store
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/khugepaged.c (ffffffff8128f105)
Location: include/linux/list.h:714
Inline: True
Inline callers:
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
```
```
In fs/super.c (ffffffff812b1c95)
Location: include/linux/list.h:714
Inline: True
Inline callers:
  - fs/super.c:generic_shutdown_super
```
```
In fs/dcache.c (ffffffff812c9fb8)
Location: include/linux/list.h:714
Inline: True
Inline callers:
  - fs/dcache.c:dentry_unlink_inode
```
```
In fs/inode.c (ffffffff812ce4ea)
Location: include/linux/list.h:714
Inline: True
Inline callers:
  - fs/inode.c:__remove_inode_hash
```
```
In fs/namespace.c (ffffffff812d56fa)
Location: include/linux/list.h:714
Inline: True
Inline callers:
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:mnt_change_mountpoint
  - fs/namespace.c:unhash_mnt
```
```
In fs/fs_pin.c (ffffffff812eaa79)
Location: include/linux/list.h:714
Inline: True
Inline callers:
  - fs/fs_pin.c:pin_remove
  - fs/fs_pin.c:pin_remove
```
```
In fs/crypto/keyinfo.c (ffffffff81311046)
Location: include/linux/list.h:714
Inline: True
Inline callers:
  - fs/crypto/keyinfo.c:put_crypt_info
```
```
In fs/locks.c (ffffffff81314081)
Location: include/linux/list.h:714
Inline: True
Inline callers:
  - fs/locks.c:locks_unlink_lock_ctx
  - fs/locks.c:locks_delete_block
  - fs/locks.c:__locks_wake_up_blocks
```
```
In fs/quota/dquot.c (ffffffff81329f21)
Location: include/linux/list.h:714
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dqcache_shrink_scan
```
```
In fs/fat/inode.c (ffffffff813c87a7)
Location: include/linux/list.h:714
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_detach
  - fs/fat/inode.c:fat_detach
```
```
In block/elevator.c (ffffffff8149a6a5)
Location: include/linux/list.h:714
Inline: True
Inline callers:
  - block/elevator.c:elv_rqhash_find
  - block/elevator.c:elv_rqhash_reposition
```
```
In block/blk-ioc.c (ffffffff814a2d90)
Location: include/linux/list.h:714
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_destroy_icq
```
```
In drivers/clk/clk.c (ffffffff815fc7f4)
Location: include/linux/list.h:714
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:clk_unregister
```
```
In drivers/dax/super.c (ffffffff81705292)
Location: include/linux/list.h:714
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff8197c39e)
Location: include/linux/list.h:714
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
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
In arch/x86/kernel/apic/vector.c (ffffffff810674ba)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:free_moved_vector
  - arch/x86/kernel/apic/vector.c:clear_irq_vector
```
```
In arch/x86/kernel/kvm.c (ffffffff81076495)
Location: include/linux/list.h:774
Inline: True
```
```
In kernel/fork.c (ffffffff81098ae7)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/user.c (ffffffff810a8d6a)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - kernel/user.c:free_uid
```
```
In kernel/workqueue.c (ffffffff810bc322)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:process_one_work
```
```
In kernel/ucount.c (ffffffff810c6a65)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - kernel/ucount.c:put_ucounts
```
```
In kernel/cgroup/cgroup.c (ffffffff828ca5c1)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
```
```
In mm/ksm.c (ffffffff81290583)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - mm/ksm.c:run_store
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/khugepaged.c (ffffffff812a99cf)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
```
```
In fs/super.c (ffffffff812cea25)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - fs/super.c:generic_shutdown_super
```
```
In fs/dcache.c (ffffffff812e6a39)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - fs/dcache.c:dentry_unlink_inode
```
```
In fs/inode.c (ffffffff812eb3ca)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - fs/inode.c:__remove_inode_hash
```
```
In fs/namespace.c (ffffffff812f388f)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:mnt_change_mountpoint
  - fs/namespace.c:unhash_mnt
```
```
In fs/fs_pin.c (ffffffff813094ea)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - fs/fs_pin.c:pin_remove
  - fs/fs_pin.c:pin_remove
```
```
In fs/crypto/keyinfo.c (ffffffff813383c6)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - fs/crypto/keyinfo.c:put_crypt_info
```
```
In fs/locks.c (ffffffff8133b972)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - fs/locks.c:locks_unlink_lock_ctx
  - fs/locks.c:locks_delete_block
  - fs/locks.c:__locks_wake_up_blocks
```
```
In fs/quota/dquot.c (ffffffff81351a8e)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dqcache_shrink_scan
```
```
In fs/fat/inode.c (ffffffff813f3337)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_detach
  - fs/fat/inode.c:fat_detach
```
```
In block/elevator.c (ffffffff814c877e)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - block/elevator.c:elv_rqhash_find
  - block/elevator.c:elv_rqhash_reposition
```
```
In block/blk-ioc.c (ffffffff814d0e40)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_destroy_icq
```
```
In drivers/clk/clk.c (ffffffff8162f454)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:clk_unregister
```
```
In drivers/dax/super.c (ffffffff8173f102)
Location: include/linux/list.h:774
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff819e56ca)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
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
In arch/x86/kernel/apic/vector.c (ffffffff81067dfa)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:free_moved_vector
  - arch/x86/kernel/apic/vector.c:clear_irq_vector
```
```
In arch/x86/kernel/kvm.c (ffffffff810774a5)
Location: include/linux/list.h:774
Inline: True
```
```
In kernel/fork.c (ffffffff8109f0a9)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/user.c (ffffffff810af33a)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - kernel/user.c:free_uid
```
```
In kernel/workqueue.c (ffffffff810c25e1)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:process_one_work
```
```
In kernel/ucount.c (ffffffff810cfb35)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - kernel/ucount.c:put_ucounts
```
```
In kernel/cgroup/cgroup.c (ffffffff828d2abf)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
```
```
In mm/ksm.c (ffffffff812a0303)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - mm/ksm.c:run_store
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/khugepaged.c (ffffffff812baf3f)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
```
```
In fs/super.c (ffffffff812e04a5)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - fs/super.c:generic_shutdown_super
```
```
In fs/dcache.c (ffffffff812f8689)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - fs/dcache.c:dentry_unlink_inode
```
```
In fs/inode.c (ffffffff812fcf0a)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - fs/inode.c:__remove_inode_hash
```
```
In fs/namespace.c (ffffffff81305450)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:mnt_change_mountpoint
  - fs/namespace.c:unhash_mnt
```
```
In fs/fs_pin.c (ffffffff8131c55a)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - fs/fs_pin.c:pin_remove
  - fs/fs_pin.c:pin_remove
```
```
In fs/crypto/keysetup_v1.c (ffffffff8134e552)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_put_direct_key
```
```
In fs/locks.c (ffffffff81353ec2)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - fs/locks.c:locks_unlink_lock_ctx
  - fs/locks.c:locks_delete_block
  - fs/locks.c:__locks_wake_up_blocks
```
```
In fs/quota/dquot.c (ffffffff81369e0e)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dqcache_shrink_scan
```
```
In fs/fat/inode.c (ffffffff8140d217)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_detach
  - fs/fat/inode.c:fat_detach
```
```
In block/elevator.c (ffffffff814e189e)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - block/elevator.c:elv_rqhash_find
  - block/elevator.c:elv_rqhash_reposition
```
```
In block/blk-ioc.c (ffffffff814ea1fd)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_destroy_icq
```
```
In drivers/clk/clk.c (ffffffff81650fa8)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:clk_unregister
```
```
In drivers/dax/super.c (ffffffff81763312)
Location: include/linux/list.h:774
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a1c6fa)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
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
In arch/x86/kernel/apic/vector.c (ffffffff8106eee4)
Location: include/linux/list.h:836
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:free_moved_vector
  - arch/x86/kernel/apic/vector.c:clear_irq_vector
```
```
In arch/x86/kernel/kvm.c (ffffffff8107f039)
Location: include/linux/list.h:836
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wake
  - arch/x86/kernel/kvm.c:apf_task_wake_all
```
```
In kernel/fork.c (ffffffff810a6125)
Location: include/linux/list.h:836
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/user.c (ffffffff810b7048)
Location: include/linux/list.h:836
Inline: True
Inline callers:
  - kernel/user.c:free_uid
```
```
In kernel/workqueue.c (ffffffff810c8ab1)
Location: include/linux/list.h:836
Inline: True
Inline callers:
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:process_one_work
```
```
In kernel/ucount.c (ffffffff810d9a35)
Location: include/linux/list.h:836
Inline: True
Inline callers:
  - kernel/ucount.c:put_ucounts
```
```
In kernel/cgroup/cgroup.c (ffffffff82cf3481)
Location: include/linux/list.h:836
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
```
```
In mm/ksm.c (ffffffff812d6c1a)
Location: include/linux/list.h:836
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:unmerge_and_remove_all_rmap_items
```
```
In mm/khugepaged.c (ffffffff812efdfc)
Location: include/linux/list.h:836
Inline: True
Inline callers:
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
```
```
In fs/super.c (ffffffff81317165)
Location: include/linux/list.h:836
Inline: True
Inline callers:
  - fs/super.c:generic_shutdown_super
```
```
In fs/dcache.c (ffffffff813315db)
Location: include/linux/list.h:836
Inline: True
Inline callers:
  - fs/dcache.c:dentry_unlink_inode
```
```
In fs/namespace.c (ffffffff813409af)
Location: include/linux/list.h:836
Inline: True
Inline callers:
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:mnt_change_mountpoint
```
```
In fs/fs_pin.c (ffffffff8135629a)
Location: include/linux/list.h:836
Inline: True
Inline callers:
  - fs/fs_pin.c:pin_remove
  - fs/fs_pin.c:pin_remove
```
```
In fs/io_uring.c (ffffffff8137eb07)
Location: include/linux/list.h:836
Inline: True
Inline callers:
  - fs/io_uring.c:__io_poll_remove_one
  - fs/io_uring.c:io_async_task_func
```
```
In fs/crypto/keysetup_v1.c (ffffffff813945c2)
Location: include/linux/list.h:836
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_put_direct_key
```
```
In fs/locks.c (ffffffff8139abb2)
Location: include/linux/list.h:836
Inline: True
Inline callers:
  - fs/locks.c:locks_unlink_lock_ctx
  - fs/locks.c:locks_delete_block
  - fs/locks.c:__locks_wake_up_blocks
```
```
In fs/quota/dquot.c (ffffffff813af289)
Location: include/linux/list.h:836
Inline: True
Inline callers:
  - fs/quota/dquot.c:dqcache_shrink_scan
  - fs/quota/dquot.c:invalidate_dquots
```
```
In fs/fat/inode.c (ffffffff8145af47)
Location: include/linux/list.h:836
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_detach
  - fs/fat/inode.c:fat_detach
```
```
In block/elevator.c (ffffffff815406a7)
Location: include/linux/list.h:836
Inline: True
Inline callers:
  - block/elevator.c:elv_merge_requests
  - block/elevator.c:elv_merged_request
  - block/elevator.c:elv_rqhash_find
  - block/elevator.c:elv_rqhash_del
```
```
In block/blk-ioc.c (ffffffff8154919d)
Location: include/linux/list.h:836
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_destroy_icq
```
```
In drivers/clk/clk.c (ffffffff81700768)
Location: include/linux/list.h:836
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:__clk_core_init
```
```
In drivers/dax/super.c (ffffffff818231b2)
Location: include/linux/list.h:836
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b0daba)
Location: include/linux/list.h:836
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
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
In arch/x86/kernel/apic/vector.c (ffffffff8107048b)
Location: include/linux/list.h:863
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:free_moved_vector
  - arch/x86/kernel/apic/vector.c:clear_irq_vector
```
```
In arch/x86/kernel/kvm.c (ffffffff8107ec69)
Location: include/linux/list.h:863
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wake
  - arch/x86/kernel/kvm.c:apf_task_wake_all
```
```
In kernel/fork.c (ffffffff810a1ef3)
Location: include/linux/list.h:863
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/user.c (ffffffff810b2208)
Location: include/linux/list.h:863
Inline: True
Inline callers:
  - kernel/user.c:free_uid
```
```
In kernel/workqueue.c (ffffffff810c3c11)
Location: include/linux/list.h:863
Inline: True
Inline callers:
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:process_one_work
```
```
In kernel/ucount.c (ffffffff810d4be5)
Location: include/linux/list.h:863
Inline: True
Inline callers:
  - kernel/ucount.c:put_ucounts
```
```
In kernel/cgroup/cgroup.c (ffffffff82fdff5b)
Location: include/linux/list.h:863
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
```
```
In mm/ksm.c (ffffffff812e27a3)
Location: include/linux/list.h:863
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:unmerge_and_remove_all_rmap_items
```
```
In mm/khugepaged.c (ffffffff812fb5bf)
Location: include/linux/list.h:863
Inline: True
Inline callers:
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
```
```
In fs/super.c (ffffffff81322675)
Location: include/linux/list.h:863
Inline: True
Inline callers:
  - fs/super.c:generic_shutdown_super
```
```
In fs/dcache.c (ffffffff8133cf6b)
Location: include/linux/list.h:863
Inline: True
Inline callers:
  - fs/dcache.c:dentry_unlink_inode
```
```
In fs/namespace.c (ffffffff8134ca3f)
Location: include/linux/list.h:863
Inline: True
Inline callers:
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:mnt_change_mountpoint
```
```
In fs/fs_pin.c (ffffffff81362bda)
Location: include/linux/list.h:863
Inline: True
Inline callers:
  - fs/fs_pin.c:pin_remove
  - fs/fs_pin.c:pin_remove
```
```
In fs/io_uring.c (ffffffff8138ccc7)
Location: include/linux/list.h:863
Inline: True
Inline callers:
  - fs/io_uring.c:__io_poll_remove_one
  - fs/io_uring.c:io_async_task_func
  - fs/io_uring.c:io_poll_task_func
```
```
In fs/crypto/keysetup_v1.c (ffffffff813a5a92)
Location: include/linux/list.h:863
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_put_direct_key
```
```
In fs/locks.c (ffffffff813ac672)
Location: include/linux/list.h:863
Inline: True
Inline callers:
  - fs/locks.c:locks_unlink_lock_ctx
  - fs/locks.c:locks_delete_block
  - fs/locks.c:__locks_wake_up_blocks
```
```
In fs/quota/dquot.c (ffffffff813c0879)
Location: include/linux/list.h:863
Inline: True
Inline callers:
  - fs/quota/dquot.c:dqcache_shrink_scan
  - fs/quota/dquot.c:invalidate_dquots
```
```
In fs/fat/inode.c (ffffffff81477297)
Location: include/linux/list.h:863
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_detach
  - fs/fat/inode.c:fat_detach
```
```
In block/elevator.c (ffffffff8155ce47)
Location: include/linux/list.h:863
Inline: True
Inline callers:
  - block/elevator.c:elv_merge_requests
  - block/elevator.c:elv_merged_request
  - block/elevator.c:elv_rqhash_find
  - block/elevator.c:elv_rqhash_del
```
```
In block/blk-ioc.c (ffffffff81564f7d)
Location: include/linux/list.h:863
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_destroy_icq
```
```
In drivers/clk/clk.c (ffffffff8171dc88)
Location: include/linux/list.h:863
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:__clk_core_init
```
```
In drivers/dax/super.c (ffffffff81831ef2)
Location: include/linux/list.h:863
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b1bcca)
Location: include/linux/list.h:863
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
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
In arch/x86/kernel/apic/vector.c (ffffffff81070d3b)
Location: include/linux/list.h:863
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:free_moved_vector
  - arch/x86/kernel/apic/vector.c:clear_irq_vector
```
```
In arch/x86/kernel/kvm.c (ffffffff8107f8f9)
Location: include/linux/list.h:863
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wake
  - arch/x86/kernel/kvm.c:apf_task_wake_all
```
```
In kernel/fork.c (ffffffff810a28af)
Location: include/linux/list.h:863
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/user.c (ffffffff810b3848)
Location: include/linux/list.h:863
Inline: True
Inline callers:
  - kernel/user.c:free_uid
```
```
In kernel/workqueue.c (ffffffff810c5431)
Location: include/linux/list.h:863
Inline: True
Inline callers:
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:process_one_work
```
```
In kernel/ucount.c (ffffffff810d6ba5)
Location: include/linux/list.h:863
Inline: True
Inline callers:
  - kernel/ucount.c:put_ucounts
```
```
In kernel/cgroup/cgroup.c (ffffffff831eab4d)
Location: include/linux/list.h:863
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
```
```
In kernel/bpf/trampoline.c (ffffffff81227aaf)
Location: include/linux/list.h:863
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_unlink_prog
  - kernel/bpf/trampoline.c:bpf_trampoline_link_prog
```
```
In mm/ksm.c (ffffffff812e9f30)
Location: include/linux/list.h:863
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:unmerge_and_remove_all_rmap_items
```
```
In mm/khugepaged.c (ffffffff8130238f)
Location: include/linux/list.h:863
Inline: True
Inline callers:
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
```
```
In fs/super.c (ffffffff813285ed)
Location: include/linux/list.h:863
Inline: True
Inline callers:
  - fs/super.c:generic_shutdown_super
```
```
In fs/dcache.c (ffffffff813433eb)
Location: include/linux/list.h:863
Inline: True
Inline callers:
  - fs/dcache.c:dentry_unlink_inode
```
```
In fs/namespace.c (ffffffff8135360d)
Location: include/linux/list.h:863
Inline: True
Inline callers:
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:mnt_change_mountpoint
```
```
In fs/fs_pin.c (ffffffff8136967a)
Location: include/linux/list.h:863
Inline: True
Inline callers:
  - fs/fs_pin.c:pin_remove
  - fs/fs_pin.c:pin_remove
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff81380bfc)
Location: include/linux/list.h:863
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
```
```
In fs/io_uring.c (ffffffff8139754c)
Location: include/linux/list.h:863
Inline: True
Inline callers:
  - fs/io_uring.c:io_poll_remove_waitqs
  - fs/io_uring.c:io_async_task_func
  - fs/io_uring.c:io_poll_task_func
```
```
In fs/crypto/keysetup_v1.c (ffffffff813acaf2)
Location: include/linux/list.h:863
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_put_direct_key
```
```
In fs/locks.c (ffffffff813b3d22)
Location: include/linux/list.h:863
Inline: True
Inline callers:
  - fs/locks.c:locks_unlink_lock_ctx
  - fs/locks.c:locks_delete_block
  - fs/locks.c:__locks_wake_up_blocks
```
```
In fs/quota/dquot.c (ffffffff813c7589)
Location: include/linux/list.h:863
Inline: True
Inline callers:
  - fs/quota/dquot.c:dqcache_shrink_scan
  - fs/quota/dquot.c:invalidate_dquots
```
```
In fs/fat/inode.c (ffffffff8147cd07)
Location: include/linux/list.h:863
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_detach
  - fs/fat/inode.c:fat_detach
```
```
In block/elevator.c (ffffffff815656d7)
Location: include/linux/list.h:863
Inline: True
Inline callers:
  - block/elevator.c:elv_merge_requests
  - block/elevator.c:elv_merged_request
  - block/elevator.c:elv_rqhash_find
  - block/elevator.c:elv_rqhash_del
```
```
In block/blk-ioc.c (ffffffff8156d5ed)
Location: include/linux/list.h:863
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_destroy_icq
```
```
In drivers/clk/clk.c (ffffffff816fed18)
Location: include/linux/list.h:863
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:__clk_core_init
```
```
In drivers/dax/super.c (ffffffff81815622)
Location: include/linux/list.h:863
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b099bd)
Location: include/linux/list.h:863
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
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
In arch/x86/kernel/apic/vector.c (ffffffff8107c9da)
Location: include/linux/list.h:863
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:free_moved_vector
  - arch/x86/kernel/apic/vector.c:clear_irq_vector
```
```
In arch/x86/kernel/kvm.c (ffffffff8108e6d9)
Location: include/linux/list.h:863
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wake
  - arch/x86/kernel/kvm.c:apf_task_wake_all
```
```
In kernel/fork.c (ffffffff810b3fd6)
Location: include/linux/list.h:863
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/user.c (ffffffff810c59e8)
Location: include/linux/list.h:863
Inline: True
Inline callers:
  - kernel/user.c:free_uid
```
```
In kernel/workqueue.c (ffffffff810d8021)
Location: include/linux/list.h:863
Inline: True
Inline callers:
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:process_one_work
```
```
In kernel/ucount.c (ffffffff810e9ea9)
Location: include/linux/list.h:863
Inline: True
Inline callers:
  - kernel/ucount.c:put_ucounts
```
```
In kernel/cgroup/cgroup.c (ffffffff832cf482)
Location: include/linux/list.h:863
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
```
```
In kernel/bpf/trampoline.c (ffffffff8125fd13)
Location: include/linux/list.h:863
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_unlink_prog
  - kernel/bpf/trampoline.c:bpf_trampoline_link_prog
```
```
In mm/ksm.c (ffffffff81331e53)
Location: include/linux/list.h:863
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:unmerge_and_remove_all_rmap_items
```
```
In mm/khugepaged.c (ffffffff8134c0ff)
Location: include/linux/list.h:863
Inline: True
Inline callers:
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
```
```
In fs/super.c (ffffffff81375bbd)
Location: include/linux/list.h:863
Inline: True
Inline callers:
  - fs/super.c:generic_shutdown_super
```
```
In fs/dcache.c (ffffffff81390d2b)
Location: include/linux/list.h:863
Inline: True
Inline callers:
  - fs/dcache.c:dentry_unlink_inode
```
```
In fs/namespace.c (ffffffff813a1a5d)
Location: include/linux/list.h:863
Inline: True
Inline callers:
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:mnt_change_mountpoint
```
```
In fs/fs_pin.c (ffffffff813b837a)
Location: include/linux/list.h:863
Inline: True
Inline callers:
  - fs/fs_pin.c:pin_remove
  - fs/fs_pin.c:pin_remove
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff813cdbbc)
Location: include/linux/list.h:863
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
```
```
In fs/io_uring.c (ffffffff813ee1b0)
Location: include/linux/list.h:863
Inline: True
Inline callers:
  - fs/io_uring.c:io_async_task_func
  - fs/io_uring.c:io_poll_task_func
```
```
In fs/crypto/keysetup_v1.c (ffffffff813fc462)
Location: include/linux/list.h:863
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_put_direct_key
```
```
In fs/locks.c (ffffffff81403a10)
Location: include/linux/list.h:863
Inline: True
Inline callers:
  - fs/locks.c:locks_unlink_lock_ctx
  - fs/locks.c:locks_delete_block
  - fs/locks.c:__locks_wake_up_blocks
```
```
In fs/quota/dquot.c (ffffffff81417af9)
Location: include/linux/list.h:863
Inline: True
Inline callers:
  - fs/quota/dquot.c:dqcache_shrink_scan
  - fs/quota/dquot.c:invalidate_dquots
```
```
In fs/fat/inode.c (ffffffff814d4427)
Location: include/linux/list.h:863
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_detach
  - fs/fat/inode.c:fat_detach
```
```
In block/elevator.c (ffffffff815c9ac7)
Location: include/linux/list.h:863
Inline: True
Inline callers:
  - block/elevator.c:elv_merge_requests
  - block/elevator.c:elv_merged_request
  - block/elevator.c:elv_rqhash_find
  - block/elevator.c:elv_rqhash_del
```
```
In block/blk-ioc.c (ffffffff815d1bdd)
Location: include/linux/list.h:863
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_destroy_icq
```
```
In drivers/clk/clk.c (ffffffff81779518)
Location: include/linux/list.h:863
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:__clk_core_init
```
```
In drivers/dax/super.c (ffffffff8189fdc2)
Location: include/linux/list.h:863
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81bcc94d)
Location: include/linux/list.h:863
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
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
In arch/x86/kernel/apic/vector.c (ffffffff8108bf0a)
Location: include/linux/list.h:909
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:free_moved_vector
  - arch/x86/kernel/apic/vector.c:clear_irq_vector
```
```
In arch/x86/kernel/kvm.c (ffffffff8109f1ce)
Location: include/linux/list.h:909
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wake
  - arch/x86/kernel/kvm.c:apf_task_wake_all
```
```
In kernel/fork.c (ffffffff810ca2f5)
Location: include/linux/list.h:909
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/user.c (ffffffff810dcfea)
Location: include/linux/list.h:909
Inline: True
Inline callers:
  - kernel/user.c:free_uid
```
```
In kernel/workqueue.c (ffffffff810ee8f3)
Location: include/linux/list.h:909
Inline: True
Inline callers:
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:process_one_work
```
```
In kernel/ucount.c (ffffffff81104b30)
Location: include/linux/list.h:909
Inline: True
Inline callers:
  - kernel/ucount.c:put_ucounts
```
```
In kernel/cgroup/cgroup.c (ffffffff834831c7)
Location: include/linux/list.h:909
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
```
```
In kernel/bpf/trampoline.c (ffffffff812aa541)
Location: include/linux/list.h:909
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_unlink_prog
  - kernel/bpf/trampoline.c:bpf_trampoline_link_prog
```
```
In mm/ksm.c (ffffffff813a2fc1)
Location: include/linux/list.h:909
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:unmerge_and_remove_all_rmap_items
```
```
In mm/khugepaged.c (ffffffff813c37a5)
Location: include/linux/list.h:909
Inline: True
Inline callers:
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
```
```
In fs/super.c (ffffffff813f3f4d)
Location: include/linux/list.h:909
Inline: True
Inline callers:
  - fs/super.c:generic_shutdown_super
```
```
In fs/dcache.c (ffffffff81411faa)
Location: include/linux/list.h:909
Inline: True
Inline callers:
  - fs/dcache.c:dentry_unlink_inode
```
```
In fs/namespace.c (ffffffff81425468)
Location: include/linux/list.h:909
Inline: True
Inline callers:
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:mnt_change_mountpoint
```
```
In fs/fs_pin.c (ffffffff8143dc29)
Location: include/linux/list.h:909
Inline: True
Inline callers:
  - fs/fs_pin.c:pin_remove
  - fs/fs_pin.c:pin_remove
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff81455e08)
Location: include/linux/list.h:909
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
```
```
In fs/crypto/keysetup_v1.c (ffffffff8146f911)
Location: include/linux/list.h:909
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_put_direct_key
```
```
In fs/locks.c (ffffffff814778c0)
Location: include/linux/list.h:909
Inline: True
Inline callers:
  - fs/locks.c:locks_unlink_lock_ctx
  - fs/locks.c:locks_delete_block
  - fs/locks.c:__locks_wake_up_blocks
```
```
In fs/quota/dquot.c (ffffffff8148f419)
Location: include/linux/list.h:909
Inline: True
Inline callers:
  - fs/quota/dquot.c:dqcache_shrink_scan
  - fs/quota/dquot.c:invalidate_dquots
```
```
In fs/fat/inode.c (ffffffff8155ed17)
Location: include/linux/list.h:909
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_detach
  - fs/fat/inode.c:fat_detach
```
```
In block/elevator.c (ffffffff81674de7)
Location: include/linux/list.h:909
Inline: True
Inline callers:
  - block/elevator.c:elv_merge_requests
  - block/elevator.c:elv_merged_request
  - block/elevator.c:elv_rqhash_find
  - block/elevator.c:elv_rqhash_del
```
```
In block/blk-ioc.c (ffffffff8167dafd)
Location: include/linux/list.h:909
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_destroy_icq
```
```
In io_uring/io_uring.c (ffffffff816d1db3)
Location: include/linux/list.h:909
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_poll_remove
  - io_uring/io_uring.c:io_poll_remove_all
  - io_uring/io_uring.c:io_apoll_task_func
  - io_uring/io_uring.c:io_poll_task_func
```
```
In drivers/clk/clk.c (ffffffff818af898)
Location: include/linux/list.h:909
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:__clk_core_init
```
```
In net/xfrm/xfrm_policy.c (ffffffff81d6265d)
Location: include/linux/list.h:909
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
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
In arch/x86/kernel/apic/vector.c (ffffffff810a041d)
Location: include/linux/list.h:909
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:free_moved_vector
  - arch/x86/kernel/apic/vector.c:clear_irq_vector
```
```
In arch/x86/kernel/kvm.c (ffffffff810b672a)
Location: include/linux/list.h:909
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wake
  - arch/x86/kernel/kvm.c:apf_task_wake_all
```
```
In kernel/fork.c (ffffffff810e7948)
Location: include/linux/list.h:909
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/user.c (ffffffff810fd1ea)
Location: include/linux/list.h:909
Inline: True
Inline callers:
  - kernel/user.c:free_uid
```
```
In kernel/workqueue.c (ffffffff8110ffa3)
Location: include/linux/list.h:909
Inline: True
Inline callers:
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:process_one_work
```
```
In kernel/ucount.c (ffffffff8112a420)
Location: include/linux/list.h:909
Inline: True
Inline callers:
  - kernel/ucount.c:put_ucounts
```
```
In kernel/cgroup/cgroup.c (ffffffff83eb0988)
Location: include/linux/list.h:909
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
```
```
In kernel/bpf/trampoline.c (ffffffff81309b0e)
Location: include/linux/list.h:909
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_unlink_prog
  - kernel/bpf/trampoline.c:__bpf_trampoline_link_prog
```
```
In mm/ksm.c (ffffffff81422c5e)
Location: include/linux/list.h:909
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:unmerge_and_remove_all_rmap_items
```
```
In mm/khugepaged.c (ffffffff81446b75)
Location: include/linux/list.h:909
Inline: True
Inline callers:
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
```
```
In fs/super.c (ffffffff8147cf17)
Location: include/linux/list.h:909
Inline: True
Inline callers:
  - fs/super.c:generic_shutdown_super
```
```
In fs/dcache.c (ffffffff8149cd8a)
Location: include/linux/list.h:909
Inline: True
Inline callers:
  - fs/dcache.c:dentry_unlink_inode
```
```
In fs/namespace.c (ffffffff814b1be8)
Location: include/linux/list.h:909
Inline: True
Inline callers:
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:mnt_change_mountpoint
```
```
In fs/fs_pin.c (ffffffff814cc5c9)
Location: include/linux/list.h:909
Inline: True
Inline callers:
  - fs/fs_pin.c:pin_remove
  - fs/fs_pin.c:pin_remove
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff814e4d76)
Location: include/linux/list.h:909
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
```
```
In fs/crypto/keysetup_v1.c (ffffffff815010e1)
Location: include/linux/list.h:909
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_put_direct_key
```
```
In fs/locks.c (ffffffff8150a130)
Location: include/linux/list.h:909
Inline: True
Inline callers:
  - fs/locks.c:locks_unlink_lock_ctx
  - fs/locks.c:locks_delete_block
  - fs/locks.c:__locks_wake_up_blocks
```
```
In fs/quota/dquot.c (ffffffff81522ec9)
Location: include/linux/list.h:909
Inline: True
Inline callers:
  - fs/quota/dquot.c:dqcache_shrink_scan
  - fs/quota/dquot.c:invalidate_dquots
```
```
In fs/fat/inode.c (ffffffff81600f37)
Location: include/linux/list.h:909
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_detach
  - fs/fat/inode.c:fat_detach
```
```
In block/elevator.c (ffffffff81730b67)
Location: include/linux/list.h:909
Inline: True
Inline callers:
  - block/elevator.c:elv_merge_requests
  - block/elevator.c:elv_merged_request
  - block/elevator.c:elv_rqhash_find
  - block/elevator.c:elv_rqhash_del
```
```
In block/blk-ioc.c (ffffffff8173a71d)
Location: include/linux/list.h:909
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_destroy_icq
```
```
In io_uring/poll.c (ffffffff8179d24e)
Location: include/linux/list.h:909
Inline: True
Inline callers:
  - io_uring/poll.c:io_poll_disarm
  - io_uring/poll.c:io_poll_remove_all_table
  - io_uring/poll.c:io_poll_task_func
  - io_uring/poll.c:io_poll_task_func
```
```
In drivers/clk/clk.c (ffffffff819fbac8)
Location: include/linux/list.h:909
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:__clk_core_init
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f2d15d)
Location: include/linux/list.h:909
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
```
```
In net/mctp/af_mctp.c (ffffffff8201034e)
Location: include/linux/list.h:909
Inline: True
```
```
In net/mctp/route.c (ffffffff8201364b)
Location: include/linux/list.h:909
Inline: True
Inline callers:
  - net/mctp/route.c:__mctp_key_done_in
  - net/mctp/route.c:__mctp_key_done_in
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
In arch/x86/kernel/apic/vector.c (ffffffff810a339d)
Location: include/linux/list.h:924
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:free_moved_vector
  - arch/x86/kernel/apic/vector.c:clear_irq_vector
```
```
In arch/x86/kernel/kvm.c (ffffffff810b983a)
Location: include/linux/list.h:924
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wake
  - arch/x86/kernel/kvm.c:apf_task_wake_all
```
```
In kernel/fork.c (ffffffff810f34f9)
Location: include/linux/list.h:924
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/user.c (ffffffff811091ea)
Location: include/linux/list.h:924
Inline: True
Inline callers:
  - kernel/user.c:free_uid
```
```
In kernel/workqueue.c (ffffffff81120b22)
Location: include/linux/list.h:924
Inline: True
Inline callers:
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:process_one_work
```
```
In kernel/ucount.c (ffffffff81137470)
Location: include/linux/list.h:924
Inline: True
Inline callers:
  - kernel/ucount.c:put_ucounts
```
```
In kernel/irq/resend.c (ffffffff811abf69)
Location: include/linux/list.h:924
Inline: True
Inline callers:
  - kernel/irq/resend.c:clear_irq_resend
  - kernel/irq/resend.c:resend_irqs
```
```
In kernel/cgroup/cgroup.c (ffffffff836d5978)
Location: include/linux/list.h:924
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
```
```
In kernel/trace/trace_events_user.c (ffffffff812c530a)
Location: include/linux/list.h:924
Inline: True
```
```
In kernel/bpf/trampoline.c (ffffffff8133894e)
Location: include/linux/list.h:924
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_unlink_prog
  - kernel/bpf/trampoline.c:__bpf_trampoline_link_prog
```
```
In mm/ksm.c (ffffffff81457cc9)
Location: include/linux/list.h:924
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:unmerge_and_remove_all_rmap_items
```
```
In mm/khugepaged.c (ffffffff8147c2c8)
Location: include/linux/list.h:924
Inline: True
Inline callers:
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
```
```
In fs/super.c (ffffffff814b1ce7)
Location: include/linux/list.h:924
Inline: True
Inline callers:
  - fs/super.c:generic_shutdown_super
```
```
In fs/dcache.c (ffffffff814d21aa)
Location: include/linux/list.h:924
Inline: True
Inline callers:
  - fs/dcache.c:dentry_unlink_inode
```
```
In fs/namespace.c (ffffffff814e6c37)
Location: include/linux/list.h:924
Inline: True
Inline callers:
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:mnt_change_mountpoint
```
```
In fs/fs_pin.c (ffffffff81502809)
Location: include/linux/list.h:924
Inline: True
Inline callers:
  - fs/fs_pin.c:pin_remove
  - fs/fs_pin.c:pin_remove
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff8151bdc6)
Location: include/linux/list.h:924
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
```
```
In fs/crypto/keysetup_v1.c (ffffffff81538771)
Location: include/linux/list.h:924
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_put_direct_key
```
```
In fs/locks.c (ffffffff815418b0)
Location: include/linux/list.h:924
Inline: True
Inline callers:
  - fs/locks.c:locks_unlink_lock_ctx
  - fs/locks.c:locks_delete_block
  - fs/locks.c:__locks_wake_up_blocks
```
```
In fs/quota/dquot.c (ffffffff8155b0bb)
Location: include/linux/list.h:924
Inline: True
Inline callers:
  - fs/quota/dquot.c:dqcache_shrink_scan
  - fs/quota/dquot.c:invalidate_dquots
```
```
In fs/fat/inode.c (ffffffff81638e27)
Location: include/linux/list.h:924
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_detach
  - fs/fat/inode.c:fat_detach
```
```
In block/elevator.c (ffffffff8176cdc7)
Location: include/linux/list.h:924
Inline: True
Inline callers:
  - block/elevator.c:elv_merge_requests
  - block/elevator.c:elv_merged_request
  - block/elevator.c:elv_rqhash_find
  - block/elevator.c:elv_rqhash_del
```
```
In block/blk-ioc.c (ffffffff81776e35)
Location: include/linux/list.h:924
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_destroy_icq
```
```
In io_uring/poll.c (ffffffff817de47e)
Location: include/linux/list.h:924
Inline: True
Inline callers:
  - io_uring/poll.c:io_poll_disarm
  - io_uring/poll.c:io_poll_remove_all_table
  - io_uring/poll.c:io_poll_task_func
  - io_uring/poll.c:io_poll_task_func
```
```
In drivers/clk/clk.c (ffffffff81a44578)
Location: include/linux/list.h:924
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:__clk_core_init
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f8cc5d)
Location: include/linux/list.h:924
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
```
```
In net/mctp/af_mctp.c (ffffffff8208d71e)
Location: include/linux/list.h:924
Inline: True
```
```
In net/mctp/route.c (ffffffff8209046b)
Location: include/linux/list.h:924
Inline: True
Inline callers:
  - net/mctp/route.c:__mctp_key_done_in
  - net/mctp/route.c:__mctp_key_done_in
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
In arch/x86/kernel/apic/vector.c (ffffffff810aa2dd)
Location: include/linux/list.h:1013
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:free_moved_vector
  - arch/x86/kernel/apic/vector.c:clear_irq_vector
```
```
In arch/x86/kernel/kvm.c (ffffffff810c0c66)
Location: include/linux/list.h:1013
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wake
  - arch/x86/kernel/kvm.c:apf_task_wake_all
```
```
In kernel/fork.c (ffffffff810fc8a9)
Location: include/linux/list.h:1013
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/user.c (ffffffff81112b7a)
Location: include/linux/list.h:1013
Inline: True
Inline callers:
  - kernel/user.c:free_uid
```
```
In kernel/workqueue.c (ffffffff8112a3d2)
Location: include/linux/list.h:1013
Inline: True
Inline callers:
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:process_one_work
```
```
In kernel/ucount.c (ffffffff81142650)
Location: include/linux/list.h:1013
Inline: True
Inline callers:
  - kernel/ucount.c:put_ucounts
```
```
In kernel/irq/resend.c (ffffffff811bbb69)
Location: include/linux/list.h:1013
Inline: True
Inline callers:
  - kernel/irq/resend.c:clear_irq_resend
  - kernel/irq/resend.c:resend_irqs
```
```
In kernel/cgroup/cgroup.c (ffffffff83907ce8)
Location: include/linux/list.h:1013
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
```
```
In kernel/trace/trace_events_user.c (ffffffff812e1d3f)
Location: include/linux/list.h:1013
Inline: True
```
```
In kernel/bpf/trampoline.c (ffffffff8135ea7e)
Location: include/linux/list.h:1013
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_unlink_prog
  - kernel/bpf/trampoline.c:__bpf_trampoline_link_prog
```
```
In mm/ksm.c (ffffffff81492799)
Location: include/linux/list.h:1013
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:unmerge_and_remove_all_rmap_items
```
```
In mm/khugepaged.c (ffffffff814ab398)
Location: include/linux/list.h:1013
Inline: True
Inline callers:
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
```
```
In fs/super.c (ffffffff814e3b49)
Location: include/linux/list.h:1013
Inline: True
```
```
In fs/dcache.c (ffffffff81504bea)
Location: include/linux/list.h:1013
Inline: True
Inline callers:
  - fs/dcache.c:dentry_unlink_inode
```
```
In fs/namespace.c (ffffffff8151aa77)
Location: include/linux/list.h:1013
Inline: True
Inline callers:
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:mnt_change_mountpoint
```
```
In fs/libfs.c (ffffffff8152250e)
Location: include/linux/list.h:1013
Inline: True
Inline callers:
  - fs/libfs.c:dcache_readdir
  - fs/libfs.c:dcache_dir_lseek
```
```
In fs/fs_pin.c (ffffffff81537459)
Location: include/linux/list.h:1013
Inline: True
Inline callers:
  - fs/fs_pin.c:pin_remove
  - fs/fs_pin.c:pin_remove
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff815503c6)
Location: include/linux/list.h:1013
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
```
```
In fs/crypto/keysetup_v1.c (ffffffff8156d8f1)
Location: include/linux/list.h:1013
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_put_direct_key
```
```
In fs/locks.c (ffffffff81576d90)
Location: include/linux/list.h:1013
Inline: True
Inline callers:
  - fs/locks.c:locks_unlink_lock_ctx
  - fs/locks.c:locks_delete_block
  - fs/locks.c:__locks_wake_up_blocks
```
```
In fs/quota/dquot.c (ffffffff81591af6)
Location: include/linux/list.h:1013
Inline: True
Inline callers:
  - fs/quota/dquot.c:dqcache_shrink_scan
  - fs/quota/dquot.c:invalidate_dquots
```
```
In fs/fat/inode.c (ffffffff81672317)
Location: include/linux/list.h:1013
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_detach
  - fs/fat/inode.c:fat_detach
```
```
In block/elevator.c (ffffffff817aeff7)
Location: include/linux/list.h:1013
Inline: True
Inline callers:
  - block/elevator.c:elv_merge_requests
  - block/elevator.c:elv_merged_request
  - block/elevator.c:elv_rqhash_find
  - block/elevator.c:elv_rqhash_del
```
```
In block/blk-ioc.c (ffffffff817b9065)
Location: include/linux/list.h:1013
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_destroy_icq
```
```
In io_uring/poll.c (ffffffff8182284e)
Location: include/linux/list.h:1013
Inline: True
Inline callers:
  - io_uring/poll.c:io_poll_disarm
  - io_uring/poll.c:io_poll_remove_all_table
  - io_uring/poll.c:io_poll_task_func
  - io_uring/poll.c:io_poll_task_func
```
```
In io_uring/waitid.c (ffffffff8182ad27)
Location: include/linux/list.h:1013
Inline: True
Inline callers:
  - io_uring/waitid.c:io_waitid
  - io_uring/waitid.c:io_waitid_complete
```
```
In io_uring/futex.c (ffffffff8182ee55)
Location: include/linux/list.h:1013
Inline: True
Inline callers:
  - io_uring/futex.c:io_futexv_complete
  - io_uring/futex.c:io_futex_complete
```
```
In drivers/clk/clk.c (ffffffff81a90088)
Location: include/linux/list.h:1013
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:__clk_core_init
```
```
In net/core/page_pool_user.c (ffffffff81f45785)
Location: include/linux/list.h:1013
Inline: True
Inline callers:
  - net/core/page_pool_user.c:page_pool_netdevice_event
```
```
In net/xfrm/xfrm_policy.c (ffffffff8205a5ed)
Location: include/linux/list.h:1013
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
```
```
In net/mctp/af_mctp.c (ffffffff82163bde)
Location: include/linux/list.h:1013
Inline: True
```
```
In net/mctp/route.c (ffffffff821669ab)
Location: include/linux/list.h:1013
Inline: True
Inline callers:
  - net/mctp/route.c:__mctp_key_done_in
  - net/mctp/route.c:__mctp_key_done_in
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
In kernel/fork.c (ffff8000100f4158)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/user.c (ffff80001010a424)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - kernel/user.c:free_uid
```
```
In kernel/workqueue.c (ffff80001011e4ac)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:process_one_work
```
```
In kernel/ucount.c (ffff800010130090)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - kernel/ucount.c:put_ucounts
```
```
In kernel/cgroup/cgroup.c (ffff80001144b064)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
```
```
In mm/ksm.c (ffff80001033fb3c)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - mm/ksm.c:run_store
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/khugepaged.c (ffff80001035c6a4)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
```
```
In fs/super.c (ffff800010388108)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - fs/super.c:generic_shutdown_super
```
```
In fs/dcache.c (ffff8000103a5de8)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - fs/dcache.c:dentry_unlink_inode
```
```
In fs/inode.c (ffff8000103ad340)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - fs/inode.c:__remove_inode_hash
```
```
In fs/namespace.c (ffff8000103b8b0c)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:mnt_change_mountpoint
  - fs/namespace.c:unhash_mnt
```
```
In fs/fs_pin.c (ffff8000103d3f38)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - fs/fs_pin.c:pin_remove
  - fs/fs_pin.c:pin_remove
```
```
In fs/crypto/keysetup_v1.c (ffff80001040f910)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_put_direct_key
```
```
In fs/locks.c (ffff800010416580)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - fs/locks.c:locks_unlink_lock_ctx
  - fs/locks.c:locks_delete_block
  - fs/locks.c:__locks_wake_up_blocks
```
```
In fs/quota/dquot.c (ffff800010431f4c)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dqcache_shrink_scan
```
```
In fs/fat/inode.c (ffff8000104ede90)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_detach
  - fs/fat/inode.c:fat_detach
```
```
In block/elevator.c (ffff8000105de99c)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - block/elevator.c:elv_rqhash_find
  - block/elevator.c:elv_rqhash_reposition
```
```
In block/blk-ioc.c (ffff8000105e851c)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_destroy_icq
```
```
In drivers/clk/clk.c (ffff8000107c1710)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:clk_unregister
```
```
In drivers/dax/super.c (ffff800010962fd0)
Location: include/linux/list.h:774
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffff800010cd8968)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
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
In kernel/fork.c (c03520ec)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/user.c (c036346c)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - kernel/user.c:free_uid
```
```
In kernel/workqueue.c (c03702bc)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:process_one_work
```
```
In kernel/ucount.c (c037f8d8)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - kernel/ucount.c:put_ucounts
```
```
In kernel/cgroup/cgroup.c (c1525480)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
```
```
In mm/ksm.c (c0545e48)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - mm/ksm.c:run_store
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:ksm_do_scan
```
```
In fs/super.c (c056ec18)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - fs/super.c:generic_shutdown_super
```
```
In fs/dcache.c (c05874c8)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - fs/dcache.c:dentry_unlink_inode
```
```
In fs/inode.c (c058bf20)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - fs/inode.c:__remove_inode_hash
```
```
In fs/namespace.c (c0596458)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:mnt_change_mountpoint
  - fs/namespace.c:unhash_mnt
```
```
In fs/fs_pin.c (c05ae128)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - fs/fs_pin.c:pin_remove
  - fs/fs_pin.c:pin_remove
```
```
In fs/crypto/keysetup_v1.c (c05dc1a4)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_put_direct_key
```
```
In fs/locks.c (c05e2020)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - fs/locks.c:locks_unlink_lock_ctx
  - fs/locks.c:locks_delete_block
  - fs/locks.c:__locks_wake_up_blocks
```
```
In fs/quota/dquot.c (c05fa158)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dqcache_shrink_scan
```
```
In fs/fat/inode.c (c06a940c)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_detach
  - fs/fat/inode.c:fat_detach
```
```
In block/elevator.c (c078b938)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - block/elevator.c:elv_rqhash_find
  - block/elevator.c:elv_rqhash_reposition
```
```
In block/blk-ioc.c (c0794f50)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_destroy_icq
```
```
In drivers/clk/clk.c (c08edfac)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:clk_unregister
```
```
In drivers/dax/super.c (c0a39f4c)
Location: include/linux/list.h:774
Inline: True
```
```
In net/xfrm/xfrm_policy.c (c0de253c)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
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
In kernel/fork.c (c000000000139850)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/user.c (c000000000151388)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - kernel/user.c:free_uid
```
```
In kernel/workqueue.c (c0000000001693f0)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:process_one_work
```
```
In kernel/ucount.c (c000000000179484)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - kernel/ucount.c:put_ucounts
```
```
In kernel/cgroup/cgroup.c (c00000000137085c)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
```
```
In mm/ksm.c (c00000000041c3e4)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - mm/ksm.c:run_store
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:scan_get_next_rmap_item
```
```
In mm/khugepaged.c (c000000000445de0)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
```
```
In fs/super.c (c00000000047c098)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - fs/super.c:generic_shutdown_super
```
```
In fs/dcache.c (c00000000049f150)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - fs/dcache.c:dentry_unlink_inode
```
```
In fs/inode.c (c0000000004a8bc0)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - fs/inode.c:__remove_inode_hash
```
```
In fs/namespace.c (c0000000004b5b78)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:mnt_change_mountpoint
  - fs/namespace.c:unhash_mnt
```
```
In fs/fs_pin.c (c0000000004d6a88)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - fs/fs_pin.c:pin_remove
  - fs/fs_pin.c:pin_remove
```
```
In fs/crypto/keysetup_v1.c (c00000000051d2a0)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_put_direct_key
```
```
In fs/locks.c (c000000000525310)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - fs/locks.c:locks_unlink_lock_ctx
  - fs/locks.c:locks_delete_block
  - fs/locks.c:__locks_wake_up_blocks
```
```
In fs/quota/dquot.c (c0000000005431b0)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dqcache_shrink_scan
```
```
In fs/fat/inode.c (c00000000062cc78)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_detach
  - fs/fat/inode.c:fat_detach
```
```
In block/elevator.c (c0000000007706f0)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - block/elevator.c:elv_rqhash_find
  - block/elevator.c:elv_rqhash_reposition
```
```
In block/blk-ioc.c (c00000000077d140)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_destroy_icq
```
```
In drivers/dax/super.c (c000000000a19300)
Location: include/linux/list.h:774
Inline: True
```
```
In net/xfrm/xfrm_policy.c (c000000000df9190)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
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
In kernel/fork.c (ffffffe0000c014c)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/user.c (ffffffe0000cce7a)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - kernel/user.c:free_uid
```
```
In kernel/workqueue.c (ffffffe0000d7cfc)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:process_one_work
```
```
In kernel/ucount.c (ffffffe0000e35a4)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - kernel/ucount.c:put_ucounts
```
```
In kernel/cgroup/cgroup.c (ffffffe00000c426)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
```
```
In mm/ksm.c (ffffffe0002343d2)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - mm/ksm.c:run_store
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:ksm_do_scan
```
```
In fs/super.c (ffffffe000259bb0)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - fs/super.c:generic_shutdown_super
```
```
In fs/dcache.c (ffffffe00026cc80)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - fs/dcache.c:dentry_unlink_inode
```
```
In fs/inode.c (ffffffe000271e1e)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - fs/inode.c:__remove_inode_hash
```
```
In fs/namespace.c (ffffffe00027af3a)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:mnt_change_mountpoint
  - fs/namespace.c:unhash_mnt
```
```
In fs/fs_pin.c (ffffffe00028e5a6)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - fs/fs_pin.c:pin_remove
  - fs/fs_pin.c:pin_remove
```
```
In fs/crypto/keysetup_v1.c (ffffffe0002b83ac)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_put_direct_key
```
```
In fs/locks.c (ffffffe0002bd5a6)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - fs/locks.c:locks_unlink_lock_ctx
  - fs/locks.c:locks_delete_block
  - fs/locks.c:__locks_wake_up_blocks
```
```
In fs/quota/dquot.c (ffffffe0002ce404)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dqcache_shrink_scan
```
```
In fs/fat/inode.c (ffffffe00035e312)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_detach
  - fs/fat/inode.c:fat_detach
```
```
In block/elevator.c (ffffffe000421596)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - block/elevator.c:elv_rqhash_find
  - block/elevator.c:elv_rqhash_reposition
```
```
In block/blk-ioc.c (ffffffe00042916e)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_destroy_icq
```
```
In drivers/clk/clk.c (ffffffe00050f3fa)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:clk_unregister
```
```
In drivers/dax/super.c (ffffffe0005d06ba)
Location: include/linux/list.h:774
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffe000828e74)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
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
In arch/x86/kernel/apic/vector.c (ffffffff810678ea)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:free_moved_vector
  - arch/x86/kernel/apic/vector.c:clear_irq_vector
```
```
In arch/x86/kernel/kvm.c (ffffffff810764a5)
Location: include/linux/list.h:774
Inline: True
```
```
In kernel/fork.c (ffffffff810989c9)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/user.c (ffffffff810a96aa)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - kernel/user.c:free_uid
```
```
In kernel/workqueue.c (ffffffff810bc951)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:process_one_work
```
```
In kernel/ucount.c (ffffffff810c9eb5)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - kernel/ucount.c:put_ucounts
```
```
In kernel/cgroup/cgroup.c (ffffffff828bb970)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
```
```
In mm/ksm.c (ffffffff812988e3)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - mm/ksm.c:run_store
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/khugepaged.c (ffffffff812b351f)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
```
```
In fs/super.c (ffffffff812d8a85)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - fs/super.c:generic_shutdown_super
```
```
In fs/dcache.c (ffffffff812f0c69)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - fs/dcache.c:dentry_unlink_inode
```
```
In fs/inode.c (ffffffff812f54ea)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - fs/inode.c:__remove_inode_hash
```
```
In fs/namespace.c (ffffffff812fda30)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:mnt_change_mountpoint
  - fs/namespace.c:unhash_mnt
```
```
In fs/fs_pin.c (ffffffff81314b3a)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - fs/fs_pin.c:pin_remove
  - fs/fs_pin.c:pin_remove
```
```
In fs/crypto/keysetup_v1.c (ffffffff81346b32)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_put_direct_key
```
```
In fs/locks.c (ffffffff8134c4a2)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - fs/locks.c:locks_unlink_lock_ctx
  - fs/locks.c:locks_delete_block
  - fs/locks.c:__locks_wake_up_blocks
```
```
In fs/quota/dquot.c (ffffffff813623ee)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dqcache_shrink_scan
```
```
In fs/fat/inode.c (ffffffff814057f7)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_detach
  - fs/fat/inode.c:fat_detach
```
```
In block/elevator.c (ffffffff814d9e7e)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - block/elevator.c:elv_rqhash_find
  - block/elevator.c:elv_rqhash_reposition
```
```
In block/blk-ioc.c (ffffffff814e27dd)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_destroy_icq
```
```
In drivers/clk/clk.c (ffffffff81617008)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:clk_unregister
```
```
In drivers/dax/super.c (ffffffff81717a02)
Location: include/linux/list.h:774
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff819bbd8a)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
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
In arch/x86/kernel/apic/vector.c (ffffffff81057c5a)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:free_moved_vector
  - arch/x86/kernel/apic/vector.c:clear_irq_vector
```
```
In arch/x86/kernel/kvm.c (ffffffff81066465)
Location: include/linux/list.h:774
Inline: True
```
```
In kernel/fork.c (ffffffff81087433)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/user.c (ffffffff8109806a)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - kernel/user.c:free_uid
```
```
In kernel/workqueue.c (ffffffff810ab1b1)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:process_one_work
```
```
In kernel/ucount.c (ffffffff810b86d5)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - kernel/ucount.c:put_ucounts
```
```
In kernel/cgroup/cgroup.c (ffffffff828b4003)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
```
```
In mm/ksm.c (ffffffff8128a4a3)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - mm/ksm.c:run_store
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/khugepaged.c (ffffffff812a489f)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
```
```
In fs/super.c (ffffffff812c9705)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - fs/super.c:generic_shutdown_super
```
```
In fs/dcache.c (ffffffff812e1899)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - fs/dcache.c:dentry_unlink_inode
```
```
In fs/inode.c (ffffffff812e610a)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - fs/inode.c:__remove_inode_hash
```
```
In fs/namespace.c (ffffffff812ee650)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:mnt_change_mountpoint
  - fs/namespace.c:unhash_mnt
```
```
In fs/fs_pin.c (ffffffff8130574a)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - fs/fs_pin.c:pin_remove
  - fs/fs_pin.c:pin_remove
```
```
In fs/crypto/keysetup_v1.c (ffffffff81337812)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_put_direct_key
```
```
In fs/locks.c (ffffffff8133d182)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - fs/locks.c:locks_unlink_lock_ctx
  - fs/locks.c:locks_delete_block
  - fs/locks.c:__locks_wake_up_blocks
```
```
In fs/quota/dquot.c (ffffffff8135308e)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dqcache_shrink_scan
```
```
In fs/fat/inode.c (ffffffff813f6277)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_detach
  - fs/fat/inode.c:fat_detach
```
```
In block/elevator.c (ffffffff814ca82e)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - block/elevator.c:elv_rqhash_find
  - block/elevator.c:elv_rqhash_reposition
```
```
In block/blk-ioc.c (ffffffff814d316d)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_destroy_icq
```
```
In drivers/clk/clk.c (ffffffff8160b538)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:clk_unregister
```
```
In drivers/dax/super.c (ffffffff816eff32)
Location: include/linux/list.h:774
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81978b7a)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
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
In arch/x86/kernel/apic/vector.c (ffffffff81067d9a)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:free_moved_vector
  - arch/x86/kernel/apic/vector.c:clear_irq_vector
```
```
In arch/x86/kernel/kvm.c (ffffffff81076455)
Location: include/linux/list.h:774
Inline: True
```
```
In kernel/fork.c (ffffffff81098979)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/user.c (ffffffff810a8c0a)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - kernel/user.c:free_uid
```
```
In kernel/workqueue.c (ffffffff810bbeb1)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:process_one_work
```
```
In kernel/ucount.c (ffffffff810c93e5)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - kernel/ucount.c:put_ucounts
```
```
In kernel/cgroup/cgroup.c (ffffffff828ce6f3)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
```
```
In mm/ksm.c (ffffffff812966f3)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - mm/ksm.c:run_store
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/khugepaged.c (ffffffff812b132f)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
```
```
In fs/super.c (ffffffff812d6895)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - fs/super.c:generic_shutdown_super
```
```
In fs/dcache.c (ffffffff812eea79)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - fs/dcache.c:dentry_unlink_inode
```
```
In fs/inode.c (ffffffff812f32fa)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - fs/inode.c:__remove_inode_hash
```
```
In fs/namespace.c (ffffffff812fb820)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:mnt_change_mountpoint
  - fs/namespace.c:unhash_mnt
```
```
In fs/fs_pin.c (ffffffff8131292a)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - fs/fs_pin.c:pin_remove
  - fs/fs_pin.c:pin_remove
```
```
In fs/crypto/keysetup_v1.c (ffffffff81344602)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_put_direct_key
```
```
In fs/locks.c (ffffffff81349f72)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - fs/locks.c:locks_unlink_lock_ctx
  - fs/locks.c:locks_delete_block
  - fs/locks.c:__locks_wake_up_blocks
```
```
In fs/quota/dquot.c (ffffffff8135febe)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dqcache_shrink_scan
```
```
In fs/fat/inode.c (ffffffff81402b77)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_detach
  - fs/fat/inode.c:fat_detach
```
```
In block/elevator.c (ffffffff814d5f0e)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - block/elevator.c:elv_rqhash_find
  - block/elevator.c:elv_rqhash_reposition
```
```
In block/blk-ioc.c (ffffffff814de86d)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_destroy_icq
```
```
In drivers/clk/clk.c (ffffffff81644de8)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:clk_unregister
```
```
In drivers/dax/super.c (ffffffff817567d2)
Location: include/linux/list.h:774
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a2680a)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
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
In arch/x86/kernel/apic/vector.c (ffffffff8106944a)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:free_moved_vector
  - arch/x86/kernel/apic/vector.c:clear_irq_vector
```
```
In arch/x86/kernel/kvm.c (ffffffff810784a5)
Location: include/linux/list.h:774
Inline: True
```
```
In kernel/fork.c (ffffffff810a05a0)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/user.c (ffffffff810b0d0a)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - kernel/user.c:free_uid
```
```
In kernel/workqueue.c (ffffffff810c0e81)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:process_one_work
```
```
In kernel/ucount.c (ffffffff810d1945)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - kernel/ucount.c:put_ucounts
```
```
In kernel/cgroup/cgroup.c (ffffffff828d3aed)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
```
```
In mm/ksm.c (ffffffff812a64df)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - mm/ksm.c:run_store
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/khugepaged.c (ffffffff812c166f)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
```
```
In fs/super.c (ffffffff812e6765)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - fs/super.c:generic_shutdown_super
```
```
In fs/dcache.c (ffffffff812ff059)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - fs/dcache.c:dentry_unlink_inode
```
```
In fs/inode.c (ffffffff8130306a)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - fs/inode.c:__remove_inode_hash
```
```
In fs/namespace.c (ffffffff8130cb5d)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:mnt_change_mountpoint
  - fs/namespace.c:unhash_mnt
```
```
In fs/fs_pin.c (ffffffff8132416a)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - fs/fs_pin.c:pin_remove
  - fs/fs_pin.c:pin_remove
```
```
In fs/crypto/keysetup_v1.c (ffffffff813578e2)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_put_direct_key
```
```
In fs/locks.c (ffffffff8135cc93)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - fs/locks.c:locks_unlink_lock_ctx
  - fs/locks.c:locks_delete_block
  - fs/locks.c:__locks_wake_up_blocks
```
```
In fs/quota/dquot.c (ffffffff8137297a)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dqcache_shrink_scan
```
```
In fs/fat/inode.c (ffffffff81416527)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_detach
  - fs/fat/inode.c:fat_detach
```
```
In block/elevator.c (ffffffff814eeb0e)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - block/elevator.c:elv_rqhash_find
  - block/elevator.c:elv_rqhash_reposition
```
```
In block/blk-ioc.c (ffffffff814f76cd)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_destroy_icq
```
```
In drivers/clk/clk.c (ffffffff8165f308)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:clk_unregister
```
```
In drivers/dax/super.c (ffffffff81771bc2)
Location: include/linux/list.h:774
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a31cba)
Location: include/linux/list.h:774
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
```
</details>
</li>
</ul>

## Differences
