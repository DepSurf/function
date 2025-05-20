# Function: <code>SHMEM_I</code>

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
In mm/shmem.c (ffffffff811a7000)
Location: include/linux/shmem_fs.h:40
Inline: True
Inline callers:
  - mm/shmem.c:shmem_destroy_callback
  - mm/shmem.c:shmem_get_inode
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
```
```
In ipc/shm.c (0)
Location: include/linux/shmem_fs.h:40
Inline: True
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
In mm/shmem.c (ffffffff811bd4f5)
Location: include/linux/shmem_fs.h:45
Inline: True
Inline callers:
  - mm/shmem.c:shmem_destroy_callback
  - mm/shmem.c:shmem_get_inode
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
```
```
In ipc/shm.c (0)
Location: include/linux/shmem_fs.h:45
Inline: True
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
In mm/shmem.c (ffffffff811cdbb5)
Location: include/linux/shmem_fs.h:42
Inline: True
Inline callers:
  - mm/shmem.c:shmem_destroy_callback
  - mm/shmem.c:shmem_get_inode
  - mm/shmem.c:shmem_getpage_gfp
```
```
In ipc/shm.c (0)
Location: include/linux/shmem_fs.h:42
Inline: True
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
In mm/shmem.c (ffffffff811d6de5)
Location: include/linux/shmem_fs.h:45
Inline: True
Inline callers:
  - mm/shmem.c:shmem_destroy_callback
  - mm/shmem.c:shmem_mcopy_atomic_pte
  - mm/shmem.c:shmem_get_inode
  - mm/shmem.c:shmem_getpage_gfp
```
```
In ipc/shm.c (0)
Location: include/linux/shmem_fs.h:45
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
In mm/shmem.c (ffffffff811ec305)
Location: include/linux/shmem_fs.h:46
Inline: True
Inline callers:
  - mm/shmem.c:shmem_destroy_callback
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_get_inode
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_alloc_and_acct_page
```
```
In ipc/shm.c (0)
Location: include/linux/shmem_fs.h:46
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
In mm/shmem.c (ffffffff8120d920)
Location: include/linux/shmem_fs.h:46
Inline: True
Inline callers:
  - mm/shmem.c:shmem_destroy_inode
  - mm/shmem.c:shmem_destroy_callback
  - mm/shmem.c:shmem_listxattr
  - mm/shmem.c:shmem_xattr_handler_set
  - mm/shmem.c:shmem_xattr_handler_get
  - mm/shmem.c:shmem_initxattrs
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_write_begin
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_get_inode
  - mm/shmem.c:shmem_lock
  - mm/shmem.c:shmem_get_policy
  - mm/shmem.c:shmem_set_policy
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_evict_inode
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_getattr
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_swap_usage
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_charge
  - mm/shmem.c:shmem_charge
  - mm/shmem.c:shmem_recalc_inode
  - mm/shmem.c:shmem_recalc_inode
```
```
In mm/memfd.c (ffffffff81293c9f)
Location: include/linux/shmem_fs.h:46
Inline: True
Inline callers:
  - mm/memfd.c:memfd_file_seals_ptr
```
```
In ipc/shm.c (ffffffff813ddb53)
Location: include/linux/shmem_fs.h:46
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
In mm/shmem.c (ffffffff812204d0)
Location: include/linux/shmem_fs.h:46
Inline: True
Inline callers:
  - mm/shmem.c:shmem_destroy_inode
  - mm/shmem.c:shmem_destroy_callback
  - mm/shmem.c:shmem_listxattr
  - mm/shmem.c:shmem_xattr_handler_set
  - mm/shmem.c:shmem_xattr_handler_get
  - mm/shmem.c:shmem_initxattrs
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_write_begin
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_get_inode
  - mm/shmem.c:shmem_lock
  - mm/shmem.c:shmem_get_policy
  - mm/shmem.c:shmem_set_policy
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_evict_inode
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_getattr
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_swap_usage
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_charge
  - mm/shmem.c:shmem_charge
  - mm/shmem.c:shmem_recalc_inode
  - mm/shmem.c:shmem_recalc_inode
```
```
In mm/memfd.c (ffffffff812a895f)
Location: include/linux/shmem_fs.h:46
Inline: True
Inline callers:
  - mm/memfd.c:memfd_file_seals_ptr
```
```
In ipc/shm.c (ffffffff813f81d3)
Location: include/linux/shmem_fs.h:46
Inline: True
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
In mm/shmem.c (ffffffff8122fcb3)
Location: include/linux/shmem_fs.h:47
Inline: True
Inline callers:
  - mm/shmem.c:shmem_destroy_inode
  - mm/shmem.c:shmem_free_in_core_inode
  - mm/shmem.c:shmem_listxattr
  - mm/shmem.c:shmem_xattr_handler_set
  - mm/shmem.c:shmem_xattr_handler_get
  - mm/shmem.c:shmem_initxattrs
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_write_begin
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_get_inode
  - mm/shmem.c:shmem_lock
  - mm/shmem.c:shmem_get_policy
  - mm/shmem.c:shmem_set_policy
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_evict_inode
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_getattr
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_swap_usage
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_charge
  - mm/shmem.c:shmem_charge
  - mm/shmem.c:shmem_recalc_inode
  - mm/shmem.c:shmem_recalc_inode
```
```
In mm/memfd.c (ffffffff812c50bf)
Location: include/linux/shmem_fs.h:47
Inline: True
Inline callers:
  - mm/memfd.c:memfd_file_seals_ptr
```
```
In ipc/shm.c (ffffffff814246d0)
Location: include/linux/shmem_fs.h:47
Inline: True
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
In mm/shmem.c (ffffffff8123ded3)
Location: include/linux/shmem_fs.h:47
Inline: True
Inline callers:
  - mm/shmem.c:shmem_destroy_inode
  - mm/shmem.c:shmem_free_in_core_inode
  - mm/shmem.c:shmem_listxattr
  - mm/shmem.c:shmem_xattr_handler_set
  - mm/shmem.c:shmem_xattr_handler_get
  - mm/shmem.c:shmem_initxattrs
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_write_begin
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_get_inode
  - mm/shmem.c:shmem_lock
  - mm/shmem.c:shmem_get_policy
  - mm/shmem.c:shmem_set_policy
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_evict_inode
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_getattr
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_swap_usage
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_charge
  - mm/shmem.c:shmem_charge
  - mm/shmem.c:shmem_recalc_inode
  - mm/shmem.c:shmem_recalc_inode
```
```
In mm/memfd.c (ffffffff812d6a4f)
Location: include/linux/shmem_fs.h:47
Inline: True
Inline callers:
  - mm/memfd.c:memfd_file_seals_ptr
```
```
In ipc/shm.c (ffffffff8143e420)
Location: include/linux/shmem_fs.h:47
Inline: True
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
In mm/shmem.c (ffffffff8126b2c3)
Location: include/linux/shmem_fs.h:48
Inline: True
Inline callers:
  - mm/shmem.c:shmem_destroy_inode
  - mm/shmem.c:shmem_free_in_core_inode
  - mm/shmem.c:shmem_listxattr
  - mm/shmem.c:shmem_xattr_handler_set
  - mm/shmem.c:shmem_xattr_handler_get
  - mm/shmem.c:shmem_initxattrs
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_write_begin
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_get_inode
  - mm/shmem.c:shmem_mmap
  - mm/shmem.c:shmem_lock
  - mm/shmem.c:shmem_get_policy
  - mm/shmem.c:shmem_set_policy
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_getattr
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_swap_usage
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_charge
  - mm/shmem.c:shmem_charge
  - mm/shmem.c:shmem_recalc_inode
  - mm/shmem.c:shmem_recalc_inode
```
```
In mm/memfd.c (ffffffff8130bab7)
Location: include/linux/shmem_fs.h:48
Inline: True
```
```
In ipc/shm.c (ffffffff8148f2d0)
Location: include/linux/shmem_fs.h:48
Inline: True
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
In mm/shmem.c (ffffffff81275c63)
Location: include/linux/shmem_fs.h:48
Inline: True
Inline callers:
  - mm/shmem.c:shmem_destroy_inode
  - mm/shmem.c:shmem_free_in_core_inode
  - mm/shmem.c:shmem_listxattr
  - mm/shmem.c:shmem_xattr_handler_set
  - mm/shmem.c:shmem_xattr_handler_get
  - mm/shmem.c:shmem_initxattrs
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_write_begin
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_get_inode
  - mm/shmem.c:shmem_mmap
  - mm/shmem.c:shmem_lock
  - mm/shmem.c:shmem_get_policy
  - mm/shmem.c:shmem_set_policy
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_getattr
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_swap_usage
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_charge
  - mm/shmem.c:shmem_charge
  - mm/shmem.c:shmem_recalc_inode
  - mm/shmem.c:shmem_recalc_inode
```
```
In mm/memfd.c (ffffffff81317b7b)
Location: include/linux/shmem_fs.h:48
Inline: True
Inline callers:
  - mm/memfd.c:__do_sys_memfd_create
  - mm/memfd.c:memfd_fcntl
  - mm/memfd.c:memfd_fcntl
```
```
In ipc/shm.c (ffffffff814ac9b0)
Location: include/linux/shmem_fs.h:48
Inline: True
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
In mm/shmem.c (ffffffff8127afa3)
Location: include/linux/shmem_fs.h:48
Inline: True
Inline callers:
  - mm/shmem.c:shmem_destroy_inode
  - mm/shmem.c:shmem_free_in_core_inode
  - mm/shmem.c:shmem_listxattr
  - mm/shmem.c:shmem_xattr_handler_set
  - mm/shmem.c:shmem_xattr_handler_get
  - mm/shmem.c:shmem_initxattrs
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_write_begin
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_get_inode
  - mm/shmem.c:shmem_lock
  - mm/shmem.c:shmem_get_policy
  - mm/shmem.c:shmem_set_policy
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_getattr
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_swap_usage
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_charge
  - mm/shmem.c:shmem_charge
  - mm/shmem.c:shmem_recalc_inode
  - mm/shmem.c:shmem_recalc_inode
```
```
In mm/memfd.c (ffffffff8131dd6b)
Location: include/linux/shmem_fs.h:48
Inline: True
Inline callers:
  - mm/memfd.c:__do_sys_memfd_create
  - mm/memfd.c:memfd_fcntl
  - mm/memfd.c:memfd_fcntl
```
```
In ipc/shm.c (ffffffff814b2b30)
Location: include/linux/shmem_fs.h:48
Inline: True
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
In mm/shmem.c (ffffffff812b8e53)
Location: include/linux/shmem_fs.h:49
Inline: True
Inline callers:
  - mm/shmem.c:shmem_destroy_inode
  - mm/shmem.c:shmem_free_in_core_inode
  - mm/shmem.c:shmem_listxattr
  - mm/shmem.c:shmem_xattr_handler_set
  - mm/shmem.c:shmem_xattr_handler_get
  - mm/shmem.c:shmem_initxattrs
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_write_begin
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_get_inode
  - mm/shmem.c:shmem_lock
  - mm/shmem.c:shmem_get_policy
  - mm/shmem.c:shmem_set_policy
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_getattr
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_swap_usage
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_charge
  - mm/shmem.c:shmem_charge
  - mm/shmem.c:shmem_recalc_inode
  - mm/shmem.c:shmem_recalc_inode
```
```
In mm/huge_memory.c (ffffffff81349617)
Location: include/linux/shmem_fs.h:49
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/memfd.c (ffffffff8136b10e)
Location: include/linux/shmem_fs.h:49
Inline: True
Inline callers:
  - mm/memfd.c:__do_sys_memfd_create
  - mm/memfd.c:memfd_fcntl
  - mm/memfd.c:memfd_fcntl
```
```
In ipc/shm.c (ffffffff8150b165)
Location: include/linux/shmem_fs.h:49
Inline: True
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
In mm/shmem.c (ffffffff81314bca)
Location: include/linux/shmem_fs.h:50
Inline: True
Inline callers:
  - mm/shmem.c:shmem_free_in_core_inode
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_get_inode
  - mm/shmem.c:shmem_swapin_folio
  - mm/shmem.c:shmem_alloc_and_acct_folio
```
```
In mm/huge_memory.c (0)
Location: include/linux/shmem_fs.h:50
Inline: True
```
```
In mm/memfd.c (0)
Location: include/linux/shmem_fs.h:50
Inline: True
```
```
In ipc/shm.c (0)
Location: include/linux/shmem_fs.h:50
Inline: True
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
In mm/shmem.c (ffffffff81388aba)
Location: include/linux/shmem_fs.h:56
Inline: True
Inline callers:
  - mm/shmem.c:shmem_free_in_core_inode
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_get_inode
  - mm/shmem.c:shmem_swapin_folio
  - mm/shmem.c:shmem_alloc_and_acct_folio
```
```
In mm/huge_memory.c (0)
Location: include/linux/shmem_fs.h:56
Inline: True
```
```
In mm/memfd.c (0)
Location: include/linux/shmem_fs.h:56
Inline: True
```
```
In ipc/shm.c (0)
Location: include/linux/shmem_fs.h:56
Inline: True
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
In mm/shmem.c (ffffffff813bacea)
Location: include/linux/shmem_fs.h:58
Inline: True
Inline callers:
  - mm/shmem.c:shmem_free_in_core_inode
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_get_inode
  - mm/shmem.c:shmem_swapin_folio
  - mm/shmem.c:shmem_alloc_and_acct_folio
```
```
In mm/huge_memory.c (0)
Location: include/linux/shmem_fs.h:58
Inline: True
```
```
In mm/memfd.c (0)
Location: include/linux/shmem_fs.h:58
Inline: True
```
```
In ipc/shm.c (0)
Location: include/linux/shmem_fs.h:58
Inline: True
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
In mm/shmem.c (ffffffff813e54ca)
Location: include/linux/shmem_fs.h:78
Inline: True
Inline callers:
  - mm/shmem.c:shmem_free_in_core_inode
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:__shmem_get_inode
  - mm/shmem.c:shmem_swapin_folio
  - mm/shmem.c:shmem_alloc_and_add_folio
```
```
In mm/huge_memory.c (0)
Location: include/linux/shmem_fs.h:78
Inline: True
```
```
In mm/memfd.c (0)
Location: include/linux/shmem_fs.h:78
Inline: True
```
```
In ipc/shm.c (0)
Location: include/linux/shmem_fs.h:78
Inline: True
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
In mm/shmem.c (ffff8000102cfa4c)
Location: include/linux/shmem_fs.h:47
Inline: True
Inline callers:
  - mm/shmem.c:shmem_destroy_inode
  - mm/shmem.c:shmem_free_in_core_inode
  - mm/shmem.c:shmem_listxattr
  - mm/shmem.c:shmem_xattr_handler_set
  - mm/shmem.c:shmem_xattr_handler_get
  - mm/shmem.c:shmem_initxattrs
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_write_begin
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_get_inode
  - mm/shmem.c:shmem_lock
  - mm/shmem.c:shmem_get_policy
  - mm/shmem.c:shmem_set_policy
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_evict_inode
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_getattr
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_swap_usage
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_charge
  - mm/shmem.c:shmem_charge
  - mm/shmem.c:shmem_recalc_inode
  - mm/shmem.c:shmem_recalc_inode
```
```
In mm/memfd.c (ffff80001037bbd0)
Location: include/linux/shmem_fs.h:47
Inline: True
Inline callers:
  - mm/memfd.c:memfd_file_seals_ptr
```
```
In ipc/shm.c (ffff800010527328)
Location: include/linux/shmem_fs.h:47
Inline: True
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
In mm/shmem.c (c04f9274)
Location: include/linux/shmem_fs.h:47
Inline: True
Inline callers:
  - mm/shmem.c:shmem_free_in_core_inode
  - mm/shmem.c:shmem_listxattr
  - mm/shmem.c:shmem_xattr_handler_set
  - mm/shmem.c:shmem_xattr_handler_get
  - mm/shmem.c:shmem_initxattrs
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_write_begin
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_get_inode
  - mm/shmem.c:shmem_mmap
  - mm/shmem.c:shmem_lock
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_evict_inode
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_getattr
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_swap_usage
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_charge
  - mm/shmem.c:shmem_charge
  - mm/shmem.c:shmem_recalc_inode
  - mm/shmem.c:shmem_recalc_inode
```
```
In mm/memfd.c (c0567114)
Location: include/linux/shmem_fs.h:47
Inline: True
Inline callers:
  - mm/memfd.c:__se_sys_memfd_create
  - mm/memfd.c:memfd_fcntl
  - mm/memfd.c:memfd_fcntl
```
```
In ipc/shm.c (c06e02fc)
Location: include/linux/shmem_fs.h:47
Inline: True
Inline callers:
  - ipc/shm.c:shm_add_rss_swap
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
In mm/shmem.c (c00000000038d814)
Location: include/linux/shmem_fs.h:47
Inline: True
Inline callers:
  - mm/shmem.c:shmem_destroy_inode
  - mm/shmem.c:shmem_free_in_core_inode
  - mm/shmem.c:shmem_listxattr
  - mm/shmem.c:shmem_xattr_handler_set
  - mm/shmem.c:shmem_xattr_handler_get
  - mm/shmem.c:shmem_initxattrs
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_write_begin
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_get_inode
  - mm/shmem.c:shmem_lock
  - mm/shmem.c:shmem_get_policy
  - mm/shmem.c:shmem_set_policy
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_evict_inode
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_swap_usage
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_charge
  - mm/shmem.c:shmem_charge
  - mm/shmem.c:shmem_recalc_inode
  - mm/shmem.c:shmem_recalc_inode
```
```
In mm/memfd.c (c000000000470cf0)
Location: include/linux/shmem_fs.h:47
Inline: True
Inline callers:
  - mm/memfd.c:memfd_file_seals_ptr
```
```
In ipc/shm.c (c0000000006707a0)
Location: include/linux/shmem_fs.h:47
Inline: True
Inline callers:
  - ipc/shm.c:shm_add_rss_swap
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
In mm/shmem.c (ffffffe0001ed170)
Location: include/linux/shmem_fs.h:47
Inline: True
Inline callers:
  - mm/shmem.c:shmem_free_in_core_inode
  - mm/shmem.c:shmem_listxattr
  - mm/shmem.c:shmem_xattr_handler_set
  - mm/shmem.c:shmem_xattr_handler_get
  - mm/shmem.c:shmem_initxattrs
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_write_begin
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_get_inode
  - mm/shmem.c:shmem_mmap
  - mm/shmem.c:shmem_lock
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_evict_inode
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_getattr
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_swap_usage
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_charge
  - mm/shmem.c:shmem_charge
  - mm/shmem.c:shmem_recalc_inode
  - mm/shmem.c:shmem_recalc_inode
```
```
In mm/memfd.c (ffffffe000252376)
Location: include/linux/shmem_fs.h:47
Inline: True
Inline callers:
  - mm/memfd.c:memfd_file_seals_ptr
```
```
In ipc/shm.c (ffffffe00038aa9c)
Location: include/linux/shmem_fs.h:47
Inline: True
Inline callers:
  - ipc/shm.c:shm_add_rss_swap
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
In mm/shmem.c (ffffffff81236523)
Location: include/linux/shmem_fs.h:47
Inline: True
Inline callers:
  - mm/shmem.c:shmem_destroy_inode
  - mm/shmem.c:shmem_free_in_core_inode
  - mm/shmem.c:shmem_listxattr
  - mm/shmem.c:shmem_xattr_handler_set
  - mm/shmem.c:shmem_xattr_handler_get
  - mm/shmem.c:shmem_initxattrs
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_write_begin
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_get_inode
  - mm/shmem.c:shmem_lock
  - mm/shmem.c:shmem_get_policy
  - mm/shmem.c:shmem_set_policy
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_evict_inode
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_getattr
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_swap_usage
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_charge
  - mm/shmem.c:shmem_charge
  - mm/shmem.c:shmem_recalc_inode
  - mm/shmem.c:shmem_recalc_inode
```
```
In mm/memfd.c (ffffffff812cf02f)
Location: include/linux/shmem_fs.h:47
Inline: True
Inline callers:
  - mm/memfd.c:memfd_file_seals_ptr
```
```
In ipc/shm.c (ffffffff81436a00)
Location: include/linux/shmem_fs.h:47
Inline: True
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
In mm/shmem.c (ffffffff81229583)
Location: include/linux/shmem_fs.h:47
Inline: True
Inline callers:
  - mm/shmem.c:shmem_destroy_inode
  - mm/shmem.c:shmem_free_in_core_inode
  - mm/shmem.c:shmem_listxattr
  - mm/shmem.c:shmem_xattr_handler_set
  - mm/shmem.c:shmem_xattr_handler_get
  - mm/shmem.c:shmem_initxattrs
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_write_begin
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_get_inode
  - mm/shmem.c:shmem_lock
  - mm/shmem.c:shmem_get_policy
  - mm/shmem.c:shmem_set_policy
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_evict_inode
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_getattr
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_swap_usage
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_charge
  - mm/shmem.c:shmem_charge
  - mm/shmem.c:shmem_recalc_inode
  - mm/shmem.c:shmem_recalc_inode
```
```
In mm/memfd.c (ffffffff812bfcbf)
Location: include/linux/shmem_fs.h:47
Inline: True
Inline callers:
  - mm/memfd.c:memfd_file_seals_ptr
```
```
In ipc/shm.c (ffffffff81427480)
Location: include/linux/shmem_fs.h:47
Inline: True
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
In mm/shmem.c (ffffffff812342c3)
Location: include/linux/shmem_fs.h:47
Inline: True
Inline callers:
  - mm/shmem.c:shmem_destroy_inode
  - mm/shmem.c:shmem_free_in_core_inode
  - mm/shmem.c:shmem_listxattr
  - mm/shmem.c:shmem_xattr_handler_set
  - mm/shmem.c:shmem_xattr_handler_get
  - mm/shmem.c:shmem_initxattrs
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_write_begin
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_get_inode
  - mm/shmem.c:shmem_lock
  - mm/shmem.c:shmem_get_policy
  - mm/shmem.c:shmem_set_policy
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_evict_inode
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_getattr
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_swap_usage
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_charge
  - mm/shmem.c:shmem_charge
  - mm/shmem.c:shmem_recalc_inode
  - mm/shmem.c:shmem_recalc_inode
```
```
In mm/memfd.c (ffffffff812cce3f)
Location: include/linux/shmem_fs.h:47
Inline: True
Inline callers:
  - mm/memfd.c:memfd_file_seals_ptr
```
```
In ipc/shm.c (ffffffff81432ba0)
Location: include/linux/shmem_fs.h:47
Inline: True
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
In mm/shmem.c (ffffffff812439e3)
Location: include/linux/shmem_fs.h:47
Inline: True
Inline callers:
  - mm/shmem.c:shmem_destroy_inode
  - mm/shmem.c:shmem_free_in_core_inode
  - mm/shmem.c:shmem_listxattr
  - mm/shmem.c:shmem_xattr_handler_set
  - mm/shmem.c:shmem_xattr_handler_get
  - mm/shmem.c:shmem_initxattrs
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_write_begin
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_get_inode
  - mm/shmem.c:shmem_lock
  - mm/shmem.c:shmem_get_policy
  - mm/shmem.c:shmem_set_policy
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_evict_inode
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_getattr
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_swap_usage
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_charge
  - mm/shmem.c:shmem_charge
  - mm/shmem.c:shmem_recalc_inode
  - mm/shmem.c:shmem_recalc_inode
```
```
In mm/memfd.c (ffffffff812ddbdf)
Location: include/linux/shmem_fs.h:47
Inline: True
Inline callers:
  - mm/memfd.c:memfd_file_seals_ptr
```
```
In ipc/shm.c (ffffffff81449e20)
Location: include/linux/shmem_fs.h:47
Inline: True
```
</details>
</li>
</ul>

## Differences
