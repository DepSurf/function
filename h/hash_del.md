# Function: <code>hash_del</code>

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
In kernel/workqueue.c (ffffffff8109a02e)
Location: include/linux/hashtable.h:100
Inline: True
Inline callers:
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:put_unbound_pool
```
```
In kernel/cgroup.c (ffffffff81114bff)
Location: include/linux/hashtable.h:100
Inline: True
```
```
In mm/ksm.c (ffffffff811e5186)
Location: include/linux/hashtable.h:100
Inline: True
Inline callers:
  - mm/ksm.c:run_store
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:__ksm_exit
```
```
In mm/huge_memory.c (ffffffff811f4309)
Location: include/linux/hashtable.h:100
Inline: True
Inline callers:
  - mm/huge_memory.c:collect_mm_slot
  - mm/huge_memory.c:__khugepaged_exit
```
```
In fs/locks.c (ffffffff8125f0dd)
Location: include/linux/hashtable.h:100
Inline: True
Inline callers:
  - fs/locks.c:locks_delete_block
  - fs/locks.c:posix_unblock_lock
  - fs/locks.c:locks_wake_up_blocks
```
```
In block/elevator.c (ffffffff813b38f0)
Location: include/linux/hashtable.h:100
Inline: True
Inline callers:
  - block/elevator.c:elv_rqhash_reposition
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
In kernel/workqueue.c (ffffffff8109e225)
Location: include/linux/hashtable.h:104
Inline: True
Inline callers:
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:process_one_work
```
```
In kernel/cgroup.c (ffffffff81fab40b)
Location: include/linux/hashtable.h:104
Inline: True
Inline callers:
  - kernel/cgroup.c:cgroup_init
```
```
In mm/ksm.c (ffffffff81203d1c)
Location: include/linux/hashtable.h:104
Inline: True
Inline callers:
  - mm/ksm.c:run_store
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/khugepaged.c (ffffffff812196e9)
Location: include/linux/hashtable.h:104
Inline: True
Inline callers:
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
```
```
In fs/locks.c (ffffffff8128aba3)
Location: include/linux/hashtable.h:104
Inline: True
Inline callers:
  - fs/locks.c:posix_unblock_lock
  - fs/locks.c:locks_wake_up_blocks
  - fs/locks.c:locks_delete_block
```
```
In block/elevator.c (ffffffff813f7850)
Location: include/linux/hashtable.h:104
Inline: True
Inline callers:
  - block/elevator.c:elv_rqhash_reposition
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
In kernel/workqueue.c (ffffffff810a2d85)
Location: include/linux/hashtable.h:104
Inline: True
Inline callers:
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:process_one_work
```
```
In kernel/cgroup.c (ffffffff81fe7681)
Location: include/linux/hashtable.h:104
Inline: True
Inline callers:
  - kernel/cgroup.c:cgroup_init
```
```
In mm/ksm.c (ffffffff81215d3c)
Location: include/linux/hashtable.h:104
Inline: True
Inline callers:
  - mm/ksm.c:run_store
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/khugepaged.c (ffffffff8122bc69)
Location: include/linux/hashtable.h:104
Inline: True
Inline callers:
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
```
```
In fs/locks.c (ffffffff8129f933)
Location: include/linux/hashtable.h:104
Inline: True
Inline callers:
  - fs/locks.c:posix_unblock_lock
  - fs/locks.c:locks_wake_up_blocks
  - fs/locks.c:locks_delete_block
```
```
In block/elevator.c (ffffffff814113e1)
Location: include/linux/hashtable.h:104
Inline: True
Inline callers:
  - block/elevator.c:elv_rqhash_find
  - block/elevator.c:elv_rqhash_reposition
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
In kernel/workqueue.c (ffffffff810a00b8)
Location: include/linux/hashtable.h:104
Inline: True
Inline callers:
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:process_one_work
```
```
In kernel/cgroup/cgroup.c (ffffffff820c7c0c)
Location: include/linux/hashtable.h:104
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
```
```
In mm/ksm.c (ffffffff81221436)
Location: include/linux/hashtable.h:104
Inline: True
Inline callers:
  - mm/ksm.c:run_store
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/khugepaged.c (ffffffff81237799)
Location: include/linux/hashtable.h:104
Inline: True
Inline callers:
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
```
```
In fs/locks.c (ffffffff812ae7a3)
Location: include/linux/hashtable.h:104
Inline: True
Inline callers:
  - fs/locks.c:posix_unblock_lock
  - fs/locks.c:locks_wake_up_blocks
  - fs/locks.c:locks_delete_block
```
```
In block/elevator.c (ffffffff8141eedc)
Location: include/linux/hashtable.h:104
Inline: True
Inline callers:
  - block/elevator.c:elv_rqhash_find
  - block/elevator.c:elv_rqhash_reposition
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
In kernel/workqueue.c (ffffffff810a6dcf)
Location: include/linux/hashtable.h:105
Inline: True
Inline callers:
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:process_one_work
```
```
In kernel/cgroup/cgroup.c (ffffffff826d0283)
Location: include/linux/hashtable.h:105
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
```
```
In mm/ksm.c (ffffffff8123c742)
Location: include/linux/hashtable.h:105
Inline: True
Inline callers:
  - mm/ksm.c:run_store
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/khugepaged.c (ffffffff81256b25)
Location: include/linux/hashtable.h:105
Inline: True
Inline callers:
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
```
```
In fs/locks.c (ffffffff812d218f)
Location: include/linux/hashtable.h:105
Inline: True
Inline callers:
  - fs/locks.c:posix_unblock_lock
  - fs/locks.c:locks_wake_up_blocks
  - fs/locks.c:locks_delete_block
```
```
In block/elevator.c (ffffffff814499b1)
Location: include/linux/hashtable.h:105
Inline: True
Inline callers:
  - block/elevator.c:elv_rqhash_find
  - block/elevator.c:elv_rqhash_reposition
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
In kernel/workqueue.c (ffffffff810acc95)
Location: include/linux/hashtable.h:105
Inline: True
Inline callers:
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:process_one_work
```
```
In kernel/cgroup/cgroup.c (ffffffff826fa9bb)
Location: include/linux/hashtable.h:105
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
```
```
In mm/ksm.c (ffffffff8125fcd3)
Location: include/linux/hashtable.h:105
Inline: True
Inline callers:
  - mm/ksm.c:run_store
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/khugepaged.c (ffffffff8127aaf5)
Location: include/linux/hashtable.h:105
Inline: True
Inline callers:
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
```
```
In fs/locks.c (ffffffff812fe63f)
Location: include/linux/hashtable.h:105
Inline: True
Inline callers:
  - fs/locks.c:posix_unblock_lock
  - fs/locks.c:locks_wake_up_blocks
  - fs/locks.c:locks_delete_block
```
```
In block/elevator.c (ffffffff8147c6b5)
Location: include/linux/hashtable.h:105
Inline: True
Inline callers:
  - block/elevator.c:elv_rqhash_find
  - block/elevator.c:elv_rqhash_reposition
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
In kernel/workqueue.c (ffffffff810b6515)
Location: include/linux/hashtable.h:105
Inline: True
Inline callers:
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:process_one_work
```
```
In kernel/cgroup/cgroup.c (ffffffff828b18b7)
Location: include/linux/hashtable.h:105
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
```
```
In mm/ksm.c (ffffffff81274413)
Location: include/linux/hashtable.h:105
Inline: True
Inline callers:
  - mm/ksm.c:run_store
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/khugepaged.c (ffffffff8128f105)
Location: include/linux/hashtable.h:105
Inline: True
Inline callers:
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
```
```
In fs/crypto/keyinfo.c (ffffffff81311046)
Location: include/linux/hashtable.h:105
Inline: True
Inline callers:
  - fs/crypto/keyinfo.c:put_crypt_info
```
```
In fs/locks.c (ffffffff8131433c)
Location: include/linux/hashtable.h:105
Inline: True
Inline callers:
  - fs/locks.c:locks_delete_block
  - fs/locks.c:__locks_wake_up_blocks
```
```
In block/elevator.c (ffffffff8149a6a5)
Location: include/linux/hashtable.h:105
Inline: True
Inline callers:
  - block/elevator.c:elv_rqhash_find
  - block/elevator.c:elv_rqhash_reposition
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
In kernel/workqueue.c (ffffffff810bc322)
Location: include/linux/hashtable.h:105
Inline: True
Inline callers:
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:process_one_work
```
```
In kernel/cgroup/cgroup.c (ffffffff828ca5c1)
Location: include/linux/hashtable.h:105
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
```
```
In mm/ksm.c (ffffffff81290583)
Location: include/linux/hashtable.h:105
Inline: True
Inline callers:
  - mm/ksm.c:run_store
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/khugepaged.c (ffffffff812a99cf)
Location: include/linux/hashtable.h:105
Inline: True
Inline callers:
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
```
```
In fs/crypto/keyinfo.c (ffffffff813383c6)
Location: include/linux/hashtable.h:105
Inline: True
Inline callers:
  - fs/crypto/keyinfo.c:put_crypt_info
```
```
In fs/locks.c (ffffffff8133bc7c)
Location: include/linux/hashtable.h:105
Inline: True
Inline callers:
  - fs/locks.c:locks_delete_block
  - fs/locks.c:__locks_wake_up_blocks
```
```
In block/elevator.c (ffffffff814c877e)
Location: include/linux/hashtable.h:105
Inline: True
Inline callers:
  - block/elevator.c:elv_rqhash_find
  - block/elevator.c:elv_rqhash_reposition
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
In kernel/workqueue.c (ffffffff810c25e1)
Location: include/linux/hashtable.h:105
Inline: True
Inline callers:
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:process_one_work
```
```
In kernel/cgroup/cgroup.c (ffffffff828d2abf)
Location: include/linux/hashtable.h:105
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
```
```
In mm/ksm.c (ffffffff812a0303)
Location: include/linux/hashtable.h:105
Inline: True
Inline callers:
  - mm/ksm.c:run_store
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/khugepaged.c (ffffffff812baf3f)
Location: include/linux/hashtable.h:105
Inline: True
Inline callers:
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
```
```
In fs/crypto/keysetup_v1.c (ffffffff8134e552)
Location: include/linux/hashtable.h:105
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_put_direct_key
```
```
In fs/locks.c (ffffffff813541db)
Location: include/linux/hashtable.h:105
Inline: True
Inline callers:
  - fs/locks.c:locks_delete_block
  - fs/locks.c:__locks_wake_up_blocks
```
```
In block/elevator.c (ffffffff814e189e)
Location: include/linux/hashtable.h:105
Inline: True
Inline callers:
  - block/elevator.c:elv_rqhash_find
  - block/elevator.c:elv_rqhash_reposition
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
In kernel/workqueue.c (ffffffff810c8ab1)
Location: include/linux/hashtable.h:105
Inline: True
Inline callers:
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:process_one_work
```
```
In kernel/cgroup/cgroup.c (ffffffff82cf3481)
Location: include/linux/hashtable.h:105
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
```
```
In mm/ksm.c (ffffffff812d6c1a)
Location: include/linux/hashtable.h:105
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:unmerge_and_remove_all_rmap_items
```
```
In mm/khugepaged.c (ffffffff812efdfc)
Location: include/linux/hashtable.h:105
Inline: True
Inline callers:
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
```
```
In fs/io_uring.c (ffffffff8137eb07)
Location: include/linux/hashtable.h:105
Inline: True
Inline callers:
  - fs/io_uring.c:__io_poll_remove_one
  - fs/io_uring.c:io_async_task_func
```
```
In fs/crypto/keysetup_v1.c (ffffffff813945c2)
Location: include/linux/hashtable.h:105
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_put_direct_key
```
```
In fs/locks.c (ffffffff8139a79e)
Location: include/linux/hashtable.h:105
Inline: True
Inline callers:
  - fs/locks.c:locks_delete_block
  - fs/locks.c:__locks_wake_up_blocks
```
```
In block/elevator.c (ffffffff815406a7)
Location: include/linux/hashtable.h:105
Inline: True
Inline callers:
  - block/elevator.c:elv_merge_requests
  - block/elevator.c:elv_merged_request
  - block/elevator.c:elv_rqhash_find
  - block/elevator.c:elv_rqhash_del
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
In kernel/workqueue.c (ffffffff810c3c11)
Location: include/linux/hashtable.h:105
Inline: True
Inline callers:
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:process_one_work
```
```
In kernel/cgroup/cgroup.c (ffffffff82fdff5b)
Location: include/linux/hashtable.h:105
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
```
```
In mm/ksm.c (ffffffff812e27a3)
Location: include/linux/hashtable.h:105
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:unmerge_and_remove_all_rmap_items
```
```
In mm/khugepaged.c (ffffffff812fb5bf)
Location: include/linux/hashtable.h:105
Inline: True
Inline callers:
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
```
```
In fs/io_uring.c (ffffffff8138ccc7)
Location: include/linux/hashtable.h:105
Inline: True
Inline callers:
  - fs/io_uring.c:__io_poll_remove_one
  - fs/io_uring.c:io_async_task_func
  - fs/io_uring.c:io_poll_task_func
```
```
In fs/crypto/keysetup_v1.c (ffffffff813a5a92)
Location: include/linux/hashtable.h:105
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_put_direct_key
```
```
In fs/locks.c (ffffffff813ac25e)
Location: include/linux/hashtable.h:105
Inline: True
Inline callers:
  - fs/locks.c:locks_delete_block
  - fs/locks.c:__locks_wake_up_blocks
```
```
In block/elevator.c (ffffffff8155ce47)
Location: include/linux/hashtable.h:105
Inline: True
Inline callers:
  - block/elevator.c:elv_merge_requests
  - block/elevator.c:elv_merged_request
  - block/elevator.c:elv_rqhash_find
  - block/elevator.c:elv_rqhash_del
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
In kernel/workqueue.c (ffffffff810c5431)
Location: include/linux/hashtable.h:105
Inline: True
Inline callers:
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:process_one_work
```
```
In kernel/cgroup/cgroup.c (ffffffff831eab4d)
Location: include/linux/hashtable.h:105
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
```
```
In mm/ksm.c (ffffffff812e9f30)
Location: include/linux/hashtable.h:105
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:unmerge_and_remove_all_rmap_items
```
```
In mm/khugepaged.c (ffffffff8130238f)
Location: include/linux/hashtable.h:105
Inline: True
Inline callers:
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
```
```
In fs/io_uring.c (ffffffff8139754c)
Location: include/linux/hashtable.h:105
Inline: True
Inline callers:
  - fs/io_uring.c:io_poll_remove_waitqs
  - fs/io_uring.c:io_async_task_func
  - fs/io_uring.c:io_poll_task_func
```
```
In fs/crypto/keysetup_v1.c (ffffffff813acaf2)
Location: include/linux/hashtable.h:105
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_put_direct_key
```
```
In fs/locks.c (ffffffff813b390e)
Location: include/linux/hashtable.h:105
Inline: True
Inline callers:
  - fs/locks.c:locks_delete_block
  - fs/locks.c:__locks_wake_up_blocks
```
```
In block/elevator.c (ffffffff815656d7)
Location: include/linux/hashtable.h:105
Inline: True
Inline callers:
  - block/elevator.c:elv_merge_requests
  - block/elevator.c:elv_merged_request
  - block/elevator.c:elv_rqhash_find
  - block/elevator.c:elv_rqhash_del
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
In kernel/workqueue.c (ffffffff810d8021)
Location: include/linux/hashtable.h:105
Inline: True
Inline callers:
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:process_one_work
```
```
In kernel/cgroup/cgroup.c (ffffffff832cf482)
Location: include/linux/hashtable.h:105
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
```
```
In mm/ksm.c (ffffffff81331e53)
Location: include/linux/hashtable.h:105
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:unmerge_and_remove_all_rmap_items
```
```
In mm/khugepaged.c (ffffffff8134c0ff)
Location: include/linux/hashtable.h:105
Inline: True
Inline callers:
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
```
```
In fs/io_uring.c (ffffffff813ee1b0)
Location: include/linux/hashtable.h:105
Inline: True
Inline callers:
  - fs/io_uring.c:io_async_task_func
  - fs/io_uring.c:io_poll_task_func
```
```
In fs/crypto/keysetup_v1.c (ffffffff813fc462)
Location: include/linux/hashtable.h:105
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_put_direct_key
```
```
In fs/locks.c (ffffffff814035ee)
Location: include/linux/hashtable.h:105
Inline: True
Inline callers:
  - fs/locks.c:locks_delete_block
  - fs/locks.c:__locks_wake_up_blocks
```
```
In block/elevator.c (ffffffff815c9ac7)
Location: include/linux/hashtable.h:105
Inline: True
Inline callers:
  - block/elevator.c:elv_merge_requests
  - block/elevator.c:elv_merged_request
  - block/elevator.c:elv_rqhash_find
  - block/elevator.c:elv_rqhash_del
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
In kernel/workqueue.c (ffffffff810ee8f3)
Location: include/linux/hashtable.h:105
Inline: True
Inline callers:
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:process_one_work
```
```
In kernel/cgroup/cgroup.c (ffffffff834831c7)
Location: include/linux/hashtable.h:105
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
```
```
In mm/ksm.c (ffffffff813a2fc1)
Location: include/linux/hashtable.h:105
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:unmerge_and_remove_all_rmap_items
```
```
In mm/khugepaged.c (ffffffff813c37a5)
Location: include/linux/hashtable.h:105
Inline: True
Inline callers:
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
```
```
In fs/crypto/keysetup_v1.c (ffffffff8146f911)
Location: include/linux/hashtable.h:105
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_put_direct_key
```
```
In fs/locks.c (ffffffff814776fe)
Location: include/linux/hashtable.h:105
Inline: True
Inline callers:
  - fs/locks.c:locks_delete_block
  - fs/locks.c:__locks_wake_up_blocks
```
```
In block/elevator.c (ffffffff81674de7)
Location: include/linux/hashtable.h:105
Inline: True
Inline callers:
  - block/elevator.c:elv_merge_requests
  - block/elevator.c:elv_merged_request
  - block/elevator.c:elv_rqhash_find
  - block/elevator.c:elv_rqhash_del
```
```
In io_uring/io_uring.c (ffffffff816d1db3)
Location: include/linux/hashtable.h:105
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_poll_remove
  - io_uring/io_uring.c:io_apoll_task_func
  - io_uring/io_uring.c:io_poll_task_func
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
In kernel/workqueue.c (ffffffff8110ffa3)
Location: include/linux/hashtable.h:105
Inline: True
Inline callers:
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:process_one_work
```
```
In kernel/cgroup/cgroup.c (ffffffff83eb0988)
Location: include/linux/hashtable.h:105
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
```
```
In mm/ksm.c (ffffffff81422c5e)
Location: include/linux/hashtable.h:105
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:unmerge_and_remove_all_rmap_items
```
```
In mm/khugepaged.c (ffffffff81446b75)
Location: include/linux/hashtable.h:105
Inline: True
Inline callers:
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
```
```
In fs/crypto/keysetup_v1.c (ffffffff815010e1)
Location: include/linux/hashtable.h:105
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_put_direct_key
```
```
In fs/locks.c (ffffffff81509f4e)
Location: include/linux/hashtable.h:105
Inline: True
Inline callers:
  - fs/locks.c:locks_delete_block
  - fs/locks.c:__locks_wake_up_blocks
```
```
In block/elevator.c (ffffffff81730b67)
Location: include/linux/hashtable.h:105
Inline: True
Inline callers:
  - block/elevator.c:elv_merge_requests
  - block/elevator.c:elv_merged_request
  - block/elevator.c:elv_rqhash_find
  - block/elevator.c:elv_rqhash_del
```
```
In io_uring/poll.c (ffffffff8179d24e)
Location: include/linux/hashtable.h:105
Inline: True
Inline callers:
  - io_uring/poll.c:io_poll_disarm
  - io_uring/poll.c:io_poll_task_func
  - io_uring/poll.c:io_poll_task_func
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
In kernel/workqueue.c (ffffffff81120b22)
Location: include/linux/hashtable.h:105
Inline: True
Inline callers:
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:process_one_work
```
```
In kernel/cgroup/cgroup.c (ffffffff836d5978)
Location: include/linux/hashtable.h:105
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
```
```
In kernel/trace/trace_events_user.c (ffffffff812c530a)
Location: include/linux/hashtable.h:105
Inline: True
```
```
In mm/ksm.c (ffffffff81457cc9)
Location: include/linux/hashtable.h:105
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:unmerge_and_remove_all_rmap_items
```
```
In mm/khugepaged.c (ffffffff8147c2c8)
Location: include/linux/hashtable.h:105
Inline: True
Inline callers:
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
```
```
In fs/crypto/keysetup_v1.c (ffffffff81538771)
Location: include/linux/hashtable.h:105
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_put_direct_key
```
```
In fs/locks.c (ffffffff815416ce)
Location: include/linux/hashtable.h:105
Inline: True
Inline callers:
  - fs/locks.c:locks_delete_block
  - fs/locks.c:__locks_wake_up_blocks
```
```
In block/elevator.c (ffffffff8176cdc7)
Location: include/linux/hashtable.h:105
Inline: True
Inline callers:
  - block/elevator.c:elv_merge_requests
  - block/elevator.c:elv_merged_request
  - block/elevator.c:elv_rqhash_find
  - block/elevator.c:elv_rqhash_del
```
```
In io_uring/poll.c (ffffffff817de47e)
Location: include/linux/hashtable.h:105
Inline: True
Inline callers:
  - io_uring/poll.c:io_poll_disarm
  - io_uring/poll.c:io_poll_task_func
  - io_uring/poll.c:io_poll_task_func
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
In kernel/workqueue.c (ffffffff8112a3d2)
Location: include/linux/hashtable.h:105
Inline: True
Inline callers:
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:process_one_work
```
```
In kernel/cgroup/cgroup.c (ffffffff83907ce8)
Location: include/linux/hashtable.h:105
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
```
```
In kernel/trace/trace_events_user.c (ffffffff812e1d3f)
Location: include/linux/hashtable.h:105
Inline: True
```
```
In mm/ksm.c (ffffffff81492799)
Location: include/linux/hashtable.h:105
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:unmerge_and_remove_all_rmap_items
```
```
In mm/khugepaged.c (ffffffff814ab398)
Location: include/linux/hashtable.h:105
Inline: True
Inline callers:
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
```
```
In fs/crypto/keysetup_v1.c (ffffffff8156d8f1)
Location: include/linux/hashtable.h:105
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_put_direct_key
```
```
In fs/locks.c (ffffffff81576bae)
Location: include/linux/hashtable.h:105
Inline: True
Inline callers:
  - fs/locks.c:locks_delete_block
  - fs/locks.c:__locks_wake_up_blocks
```
```
In block/elevator.c (ffffffff817aeff7)
Location: include/linux/hashtable.h:105
Inline: True
Inline callers:
  - block/elevator.c:elv_merge_requests
  - block/elevator.c:elv_merged_request
  - block/elevator.c:elv_rqhash_find
  - block/elevator.c:elv_rqhash_del
```
```
In io_uring/poll.c (ffffffff8182284e)
Location: include/linux/hashtable.h:105
Inline: True
Inline callers:
  - io_uring/poll.c:io_poll_disarm
  - io_uring/poll.c:io_poll_task_func
  - io_uring/poll.c:io_poll_task_func
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
In kernel/workqueue.c (ffff80001011e4ac)
Location: include/linux/hashtable.h:105
Inline: True
Inline callers:
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:process_one_work
```
```
In kernel/cgroup/cgroup.c (ffff80001144b064)
Location: include/linux/hashtable.h:105
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
```
```
In mm/ksm.c (ffff80001033fb3c)
Location: include/linux/hashtable.h:105
Inline: True
Inline callers:
  - mm/ksm.c:run_store
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/khugepaged.c (ffff80001035c6a4)
Location: include/linux/hashtable.h:105
Inline: True
Inline callers:
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
```
```
In fs/crypto/keysetup_v1.c (ffff80001040f910)
Location: include/linux/hashtable.h:105
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_put_direct_key
```
```
In fs/locks.c (ffff800010416490)
Location: include/linux/hashtable.h:105
Inline: True
Inline callers:
  - fs/locks.c:locks_delete_block
  - fs/locks.c:__locks_wake_up_blocks
```
```
In block/elevator.c (ffff8000105de99c)
Location: include/linux/hashtable.h:105
Inline: True
Inline callers:
  - block/elevator.c:elv_rqhash_find
  - block/elevator.c:elv_rqhash_reposition
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
In kernel/workqueue.c (c03702bc)
Location: include/linux/hashtable.h:105
Inline: True
Inline callers:
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:process_one_work
```
```
In kernel/cgroup/cgroup.c (c1525480)
Location: include/linux/hashtable.h:105
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
```
```
In mm/ksm.c (c0545e48)
Location: include/linux/hashtable.h:105
Inline: True
Inline callers:
  - mm/ksm.c:run_store
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:ksm_do_scan
```
```
In fs/crypto/keysetup_v1.c (c05dc1a4)
Location: include/linux/hashtable.h:105
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_put_direct_key
```
```
In fs/locks.c (c05e1864)
Location: include/linux/hashtable.h:105
Inline: True
Inline callers:
  - fs/locks.c:locks_delete_block
  - fs/locks.c:__locks_wake_up_blocks
```
```
In block/elevator.c (c078b938)
Location: include/linux/hashtable.h:105
Inline: True
Inline callers:
  - block/elevator.c:elv_rqhash_find
  - block/elevator.c:elv_rqhash_reposition
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
In kernel/workqueue.c (c0000000001693f0)
Location: include/linux/hashtable.h:105
Inline: True
Inline callers:
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:process_one_work
```
```
In kernel/cgroup/cgroup.c (c00000000137085c)
Location: include/linux/hashtable.h:105
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
```
```
In mm/ksm.c (c00000000041c3e4)
Location: include/linux/hashtable.h:105
Inline: True
Inline callers:
  - mm/ksm.c:run_store
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:scan_get_next_rmap_item
```
```
In mm/khugepaged.c (c000000000445de0)
Location: include/linux/hashtable.h:105
Inline: True
Inline callers:
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
```
```
In fs/crypto/keysetup_v1.c (c00000000051d2a0)
Location: include/linux/hashtable.h:105
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_put_direct_key
```
```
In fs/locks.c (c000000000523fa4)
Location: include/linux/hashtable.h:105
Inline: True
Inline callers:
  - fs/locks.c:locks_delete_block
  - fs/locks.c:__locks_wake_up_blocks
```
```
In block/elevator.c (c0000000007706f0)
Location: include/linux/hashtable.h:105
Inline: True
Inline callers:
  - block/elevator.c:elv_rqhash_find
  - block/elevator.c:elv_rqhash_reposition
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
In kernel/workqueue.c (ffffffe0000d7cfc)
Location: include/linux/hashtable.h:105
Inline: True
Inline callers:
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:process_one_work
```
```
In kernel/cgroup/cgroup.c (ffffffe00000c426)
Location: include/linux/hashtable.h:105
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
```
```
In mm/ksm.c (ffffffe0002343d2)
Location: include/linux/hashtable.h:105
Inline: True
Inline callers:
  - mm/ksm.c:run_store
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:ksm_do_scan
```
```
In fs/crypto/keysetup_v1.c (ffffffe0002b83ac)
Location: include/linux/hashtable.h:105
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_put_direct_key
```
```
In fs/locks.c (ffffffe0002bd89c)
Location: include/linux/hashtable.h:105
Inline: True
Inline callers:
  - fs/locks.c:locks_delete_block
  - fs/locks.c:__locks_wake_up_blocks
```
```
In block/elevator.c (ffffffe000421596)
Location: include/linux/hashtable.h:105
Inline: True
Inline callers:
  - block/elevator.c:elv_rqhash_find
  - block/elevator.c:elv_rqhash_reposition
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
In kernel/workqueue.c (ffffffff810bc951)
Location: include/linux/hashtable.h:105
Inline: True
Inline callers:
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:process_one_work
```
```
In kernel/cgroup/cgroup.c (ffffffff828bb970)
Location: include/linux/hashtable.h:105
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
```
```
In mm/ksm.c (ffffffff812988e3)
Location: include/linux/hashtable.h:105
Inline: True
Inline callers:
  - mm/ksm.c:run_store
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/khugepaged.c (ffffffff812b351f)
Location: include/linux/hashtable.h:105
Inline: True
Inline callers:
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
```
```
In fs/crypto/keysetup_v1.c (ffffffff81346b32)
Location: include/linux/hashtable.h:105
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_put_direct_key
```
```
In fs/locks.c (ffffffff8134c7bb)
Location: include/linux/hashtable.h:105
Inline: True
Inline callers:
  - fs/locks.c:locks_delete_block
  - fs/locks.c:__locks_wake_up_blocks
```
```
In block/elevator.c (ffffffff814d9e7e)
Location: include/linux/hashtable.h:105
Inline: True
Inline callers:
  - block/elevator.c:elv_rqhash_find
  - block/elevator.c:elv_rqhash_reposition
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
In kernel/workqueue.c (ffffffff810ab1b1)
Location: include/linux/hashtable.h:105
Inline: True
Inline callers:
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:process_one_work
```
```
In kernel/cgroup/cgroup.c (ffffffff828b4003)
Location: include/linux/hashtable.h:105
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
```
```
In mm/ksm.c (ffffffff8128a4a3)
Location: include/linux/hashtable.h:105
Inline: True
Inline callers:
  - mm/ksm.c:run_store
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/khugepaged.c (ffffffff812a489f)
Location: include/linux/hashtable.h:105
Inline: True
Inline callers:
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
```
```
In fs/crypto/keysetup_v1.c (ffffffff81337812)
Location: include/linux/hashtable.h:105
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_put_direct_key
```
```
In fs/locks.c (ffffffff8133d49b)
Location: include/linux/hashtable.h:105
Inline: True
Inline callers:
  - fs/locks.c:locks_delete_block
  - fs/locks.c:__locks_wake_up_blocks
```
```
In block/elevator.c (ffffffff814ca82e)
Location: include/linux/hashtable.h:105
Inline: True
Inline callers:
  - block/elevator.c:elv_rqhash_find
  - block/elevator.c:elv_rqhash_reposition
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
In kernel/workqueue.c (ffffffff810bbeb1)
Location: include/linux/hashtable.h:105
Inline: True
Inline callers:
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:process_one_work
```
```
In kernel/cgroup/cgroup.c (ffffffff828ce6f3)
Location: include/linux/hashtable.h:105
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
```
```
In mm/ksm.c (ffffffff812966f3)
Location: include/linux/hashtable.h:105
Inline: True
Inline callers:
  - mm/ksm.c:run_store
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/khugepaged.c (ffffffff812b132f)
Location: include/linux/hashtable.h:105
Inline: True
Inline callers:
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
```
```
In fs/crypto/keysetup_v1.c (ffffffff81344602)
Location: include/linux/hashtable.h:105
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_put_direct_key
```
```
In fs/locks.c (ffffffff8134a28b)
Location: include/linux/hashtable.h:105
Inline: True
Inline callers:
  - fs/locks.c:locks_delete_block
  - fs/locks.c:__locks_wake_up_blocks
```
```
In block/elevator.c (ffffffff814d5f0e)
Location: include/linux/hashtable.h:105
Inline: True
Inline callers:
  - block/elevator.c:elv_rqhash_find
  - block/elevator.c:elv_rqhash_reposition
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
In kernel/workqueue.c (ffffffff810c0e81)
Location: include/linux/hashtable.h:105
Inline: True
Inline callers:
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:process_one_work
```
```
In kernel/cgroup/cgroup.c (ffffffff828d3aed)
Location: include/linux/hashtable.h:105
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
```
```
In mm/ksm.c (ffffffff812a64df)
Location: include/linux/hashtable.h:105
Inline: True
Inline callers:
  - mm/ksm.c:run_store
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/khugepaged.c (ffffffff812c166f)
Location: include/linux/hashtable.h:105
Inline: True
Inline callers:
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
```
```
In fs/crypto/keysetup_v1.c (ffffffff813578e2)
Location: include/linux/hashtable.h:105
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_put_direct_key
```
```
In fs/locks.c (ffffffff8135c727)
Location: include/linux/hashtable.h:105
Inline: True
Inline callers:
  - fs/locks.c:locks_delete_block
  - fs/locks.c:__locks_wake_up_blocks
```
```
In block/elevator.c (ffffffff814eeb0e)
Location: include/linux/hashtable.h:105
Inline: True
Inline callers:
  - block/elevator.c:elv_rqhash_find
  - block/elevator.c:elv_rqhash_reposition
```
</details>
</li>
</ul>

## Differences
