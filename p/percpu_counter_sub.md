# Function: <code>percpu_counter_sub</code>

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
In fs/ext4/balloc.c (ffffffff8128f1a7)
Location: include/linux/percpu_counter.h:185
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ialloc.c (ffffffff81293b04)
Location: include/linux/percpu_counter.h:185
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_free_inode
```
```
In fs/ext4/inode.c (ffffffff81297455)
Location: include/linux/percpu_counter.h:185
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_update_reserve_space
```
```
In fs/ext4/mballoc.c (ffffffff812ce488)
Location: include/linux/percpu_counter.h:185
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
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
In mm/shmem.c (ffffffff811c0960)
Location: include/linux/percpu_counter.h:185
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_uncharge
```
```
In fs/ext4/balloc.c (ffffffff812bd785)
Location: include/linux/percpu_counter.h:185
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
```
```
In fs/ext4/ialloc.c (ffffffff812c16e6)
Location: include/linux/percpu_counter.h:185
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inode.c (ffffffff812c5a91)
Location: include/linux/percpu_counter.h:185
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_update_reserve_space
```
```
In fs/ext4/mballoc.c (ffffffff81303a6a)
Location: include/linux/percpu_counter.h:185
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
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
In mm/shmem.c (ffffffff811d0f3f)
Location: include/linux/percpu_counter.h:185
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_uncharge
```
```
In fs/ext4/balloc.c (ffffffff812d2dd5)
Location: include/linux/percpu_counter.h:185
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
```
```
In fs/ext4/ialloc.c (ffffffff812d6d18)
Location: include/linux/percpu_counter.h:185
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inode.c (ffffffff812db2c1)
Location: include/linux/percpu_counter.h:185
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_update_reserve_space
```
```
In fs/ext4/mballoc.c (ffffffff81319a2a)
Location: include/linux/percpu_counter.h:185
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
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
In mm/shmem.c (ffffffff811d99e3)
Location: include/linux/percpu_counter.h:186
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_uncharge
```
```
In fs/ext4/balloc.c (ffffffff812e43e7)
Location: include/linux/percpu_counter.h:186
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
```
```
In fs/ext4/ialloc.c (ffffffff812f501f)
Location: include/linux/percpu_counter.h:186
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inode.c (ffffffff812ffb81)
Location: include/linux/percpu_counter.h:186
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_update_reserve_space
```
```
In fs/ext4/mballoc.c (ffffffff813110c0)
Location: include/linux/percpu_counter.h:186
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
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
In mm/shmem.c (ffffffff811eed58)
Location: include/linux/percpu_counter.h:187
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_recalc_inode
```
```
In fs/ext4/balloc.c (ffffffff81308e14)
Location: include/linux/percpu_counter.h:187
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
```
```
In fs/ext4/ialloc.c (ffffffff81319771)
Location: include/linux/percpu_counter.h:187
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inode.c (ffffffff81324391)
Location: include/linux/percpu_counter.h:187
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_update_reserve_space
```
```
In fs/ext4/mballoc.c (ffffffff81335cee)
Location: include/linux/percpu_counter.h:187
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
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
In mm/shmem.c (ffffffff8120f873)
Location: include/linux/percpu_counter.h:187
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_recalc_inode
```
```
In fs/ext4/inode.c (ffffffff813525da)
Location: include/linux/percpu_counter.h:187
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_update_reserve_space
```
```
In fs/ext4/mballoc.c (ffffffff813641e5)
Location: include/linux/percpu_counter.h:187
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
```
```
In fs/ext4/super.c (ffffffff81387141)
Location: include/linux/percpu_counter.h:187
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
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
In mm/shmem.c (ffffffff81222979)
Location: include/linux/percpu_counter.h:187
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_recalc_inode
```
```
In fs/ext4/inode.c (ffffffff8136c168)
Location: include/linux/percpu_counter.h:187
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_release_space
  - fs/ext4/inode.c:ext4_da_update_reserve_space
```
```
In fs/ext4/mballoc.c (ffffffff8137c487)
Location: include/linux/percpu_counter.h:187
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
```
```
In fs/ext4/super.c (ffffffff8139fc51)
Location: include/linux/percpu_counter.h:187
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
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
In mm/shmem.c (ffffffff81231f7a)
Location: include/linux/percpu_counter.h:187
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_recalc_inode
```
```
In fs/ext4/inode.c (ffffffff8139573b)
Location: include/linux/percpu_counter.h:187
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_release_space
  - fs/ext4/inode.c:ext4_da_update_reserve_space
```
```
In fs/ext4/mballoc.c (ffffffff813a6329)
Location: include/linux/percpu_counter.h:187
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
```
```
In fs/ext4/super.c (ffffffff813c9f41)
Location: include/linux/percpu_counter.h:187
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
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
In mm/shmem.c (ffffffff8124003a)
Location: include/linux/percpu_counter.h:187
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_recalc_inode
```
```
In fs/ext4/inode.c (ffffffff813ae10b)
Location: include/linux/percpu_counter.h:187
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_release_space
  - fs/ext4/inode.c:ext4_da_update_reserve_space
```
```
In fs/ext4/mballoc.c (ffffffff813bf199)
Location: include/linux/percpu_counter.h:187
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
```
```
In fs/ext4/super.c (ffffffff813e3246)
Location: include/linux/percpu_counter.h:187
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
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
In mm/shmem.c (ffffffff8126e852)
Location: include/linux/percpu_counter.h:187
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_recalc_inode
```
```
In fs/ext4/inode.c (ffffffff813fa0db)
Location: include/linux/percpu_counter.h:187
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_release_space
  - fs/ext4/inode.c:ext4_da_update_reserve_space
```
```
In fs/ext4/mballoc.c (ffffffff8140b0e2)
Location: include/linux/percpu_counter.h:187
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
```
```
In fs/ext4/super.c (ffffffff814307e6)
Location: include/linux/percpu_counter.h:187
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
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
In mm/shmem.c (ffffffff8127924f)
Location: include/linux/percpu_counter.h:191
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_recalc_inode
```
```
In fs/io_uring.c (ffffffff813999f7)
Location: include/linux/percpu_counter.h:191
Inline: True
Inline callers:
  - fs/io_uring.c:io_submit_sqes
  - fs/io_uring.c:io_iopoll_complete
  - fs/io_uring.c:io_req_free_batch
```
```
In fs/ext4/inode.c (ffffffff8140c6d9)
Location: include/linux/percpu_counter.h:191
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_release_space
  - fs/ext4/inode.c:ext4_da_update_reserve_space
```
```
In fs/ext4/mballoc.c (ffffffff8141e550)
Location: include/linux/percpu_counter.h:191
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
```
```
In fs/ext4/super.c (ffffffff81449591)
Location: include/linux/percpu_counter.h:191
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
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
In mm/shmem.c (ffffffff8127e23b)
Location: include/linux/percpu_counter.h:191
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_recalc_inode
```
```
In fs/io_uring.c (ffffffff813950f6)
Location: include/linux/percpu_counter.h:191
Inline: True
Inline callers:
  - fs/io_uring.c:io_free_work
  - fs/io_uring.c:io_submit_sqes
  - fs/io_uring.c:io_iopoll_complete
  - fs/io_uring.c:io_put_req_deferred_cb
  - fs/io_uring.c:io_submit_flush_completions
  - fs/io_uring.c:io_req_free_batch
  - fs/io_uring.c:io_req_complete_post
```
```
In fs/ext4/inode.c (ffffffff81412859)
Location: include/linux/percpu_counter.h:191
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_release_space
  - fs/ext4/inode.c:ext4_da_update_reserve_space
```
```
In fs/ext4/mballoc.c (ffffffff81424ecf)
Location: include/linux/percpu_counter.h:191
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
```
```
In fs/ext4/super.c (ffffffff8144ef01)
Location: include/linux/percpu_counter.h:191
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
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
In mm/shmem.c (ffffffff812c003c)
Location: include/linux/percpu_counter.h:191
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_recalc_inode
```
```
In fs/io_uring.c (ffffffff813e8791)
Location: include/linux/percpu_counter.h:191
Inline: True
Inline callers:
  - fs/io_uring.c:io_iopoll_complete
  - fs/io_uring.c:io_submit_flush_completions
  - fs/io_uring.c:io_req_free_batch
  - fs/io_uring.c:__io_free_req
  - fs/io_uring.c:io_req_complete_post
  - fs/io_uring.c:io_uring_drop_tctx_refs
```
```
In fs/ext4/inode.c (ffffffff8146566c)
Location: include/linux/percpu_counter.h:191
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_release_space
  - fs/ext4/inode.c:ext4_da_update_reserve_space
```
```
In fs/ext4/mballoc.c (ffffffff81478d6a)
Location: include/linux/percpu_counter.h:191
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
```
```
In fs/ext4/super.c (ffffffff814a2a50)
Location: include/linux/percpu_counter.h:191
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
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
In mm/shmem.c (ffffffff8131ca8e)
Location: include/linux/percpu_counter.h:191
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_alloc_and_acct_folio
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_recalc_inode
```
```
In fs/ext4/inode.c (ffffffff814e4fc0)
Location: include/linux/percpu_counter.h:191
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_release_space
  - fs/ext4/inode.c:ext4_da_update_reserve_space
```
```
In fs/ext4/mballoc.c (ffffffff814fb590)
Location: include/linux/percpu_counter.h:191
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
```
```
In fs/ext4/super.c (ffffffff81529e86)
Location: include/linux/percpu_counter.h:191
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
```
```
In io_uring/io_uring.c (ffffffff81e8f852)
Location: include/linux/percpu_counter.h:191
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_uring_drop_tctx_refs
  - io_uring/io_uring.c:__io_put_task
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
In mm/shmem.c (ffffffff8139055b)
Location: include/linux/percpu_counter.h:222
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_get_folio_gfp
  - mm/shmem.c:shmem_alloc_and_acct_folio
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_recalc_inode
```
```
In fs/ext4/inode.c (ffffffff8157e630)
Location: include/linux/percpu_counter.h:222
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_release_space
  - fs/ext4/inode.c:ext4_da_update_reserve_space
```
```
In fs/ext4/mballoc.c (ffffffff81595db0)
Location: include/linux/percpu_counter.h:222
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
```
```
In fs/ext4/super.c (ffffffff815c8816)
Location: include/linux/percpu_counter.h:222
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
```
```
In io_uring/io_uring.c (ffffffff8178a965)
Location: include/linux/percpu_counter.h:222
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_uring_drop_tctx_refs
  - io_uring/io_uring.c:__io_put_task
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
In mm/shmem.c (ffffffff813c2e6c)
Location: include/linux/percpu_counter.h:218
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_get_folio_gfp
  - mm/shmem.c:shmem_alloc_and_acct_folio
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_recalc_inode
```
```
In fs/ext4/inode.c (ffffffff815b6040)
Location: include/linux/percpu_counter.h:218
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_release_space
  - fs/ext4/inode.c:ext4_da_update_reserve_space
```
```
In fs/ext4/mballoc.c (ffffffff815cc71d)
Location: include/linux/percpu_counter.h:218
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
```
```
In fs/ext4/super.c (ffffffff8160058e)
Location: include/linux/percpu_counter.h:218
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
```
```
In io_uring/io_uring.c (ffffffff817cb405)
Location: include/linux/percpu_counter.h:218
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_uring_drop_tctx_refs
  - io_uring/io_uring.c:io_put_task_remote
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
In mm/shmem.c (ffffffff813e80e1)
Location: include/linux/percpu_counter.h:275
Inline: True
Inline callers:
  - mm/shmem.c:shmem_inode_unacct_blocks
  - mm/shmem.c:shmem_inode_acct_blocks
```
```
In fs/ext4/inode.c (ffffffff815eede0)
Location: include/linux/percpu_counter.h:275
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_release_space
  - fs/ext4/inode.c:ext4_da_update_reserve_space
```
```
In fs/ext4/mballoc.c (ffffffff816051ad)
Location: include/linux/percpu_counter.h:275
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
```
```
In fs/ext4/super.c (ffffffff816392de)
Location: include/linux/percpu_counter.h:275
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
```
```
In io_uring/io_uring.c (ffffffff8180f8f5)
Location: include/linux/percpu_counter.h:275
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_uring_drop_tctx_refs
  - io_uring/io_uring.c:io_put_task_remote
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
In mm/shmem.c (ffff8000102d308c)
Location: include/linux/percpu_counter.h:187
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_recalc_inode
```
```
In fs/ext4/inode.c (ffff800010482b28)
Location: include/linux/percpu_counter.h:187
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_release_space
  - fs/ext4/inode.c:ext4_da_update_reserve_space
```
```
In fs/ext4/mballoc.c (ffff800010495e5c)
Location: include/linux/percpu_counter.h:187
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
```
```
In fs/ext4/super.c (ffff8000104bc7c4)
Location: include/linux/percpu_counter.h:187
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
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
In mm/shmem.c (c04fb2e0)
Location: include/linux/percpu_counter.h:187
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_recalc_inode
```
```
In fs/ext4/inode.c (c0643fa4)
Location: include/linux/percpu_counter.h:187
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_release_space
  - fs/ext4/inode.c:ext4_da_update_reserve_space
```
```
In fs/ext4/mballoc.c (c0657a10)
Location: include/linux/percpu_counter.h:187
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
```
```
In fs/ext4/super.c (c067fe34)
Location: include/linux/percpu_counter.h:187
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
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
In mm/shmem.c (c000000000391e90)
Location: include/linux/percpu_counter.h:187
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_recalc_inode
```
```
In fs/ext4/inode.c (c0000000005a77d8)
Location: include/linux/percpu_counter.h:187
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_release_space
  - fs/ext4/inode.c:ext4_da_update_reserve_space
```
```
In fs/ext4/mballoc.c (c0000000005bfbc0)
Location: include/linux/percpu_counter.h:187
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
```
```
In fs/ext4/super.c (c0000000005f2584)
Location: include/linux/percpu_counter.h:187
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
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
In mm/shmem.c (ffffffe0001ee54c)
Location: include/linux/percpu_counter.h:187
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_recalc_inode
```
```
In fs/ext4/inode.c (ffffffe00030b33c)
Location: include/linux/percpu_counter.h:187
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_release_space
  - fs/ext4/inode.c:ext4_da_update_reserve_space
```
```
In fs/ext4/mballoc.c (ffffffe00031a9ca)
Location: include/linux/percpu_counter.h:187
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
```
```
In fs/ext4/super.c (ffffffe00033850a)
Location: include/linux/percpu_counter.h:187
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
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
In mm/shmem.c (ffffffff8123868a)
Location: include/linux/percpu_counter.h:187
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_recalc_inode
```
```
In fs/ext4/inode.c (ffffffff813a66eb)
Location: include/linux/percpu_counter.h:187
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_release_space
  - fs/ext4/inode.c:ext4_da_update_reserve_space
```
```
In fs/ext4/mballoc.c (ffffffff813b7779)
Location: include/linux/percpu_counter.h:187
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
```
```
In fs/ext4/super.c (ffffffff813db826)
Location: include/linux/percpu_counter.h:187
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
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
In mm/shmem.c (ffffffff8122b696)
Location: include/linux/percpu_counter.h:187
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_recalc_inode
```
```
In fs/ext4/inode.c (ffffffff8139717b)
Location: include/linux/percpu_counter.h:187
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_release_space
  - fs/ext4/inode.c:ext4_da_update_reserve_space
```
```
In fs/ext4/mballoc.c (ffffffff813a8209)
Location: include/linux/percpu_counter.h:187
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
```
```
In fs/ext4/super.c (ffffffff813cc2a6)
Location: include/linux/percpu_counter.h:187
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
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
In mm/shmem.c (ffffffff8123642a)
Location: include/linux/percpu_counter.h:187
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_recalc_inode
```
```
In fs/ext4/inode.c (ffffffff813a3f4b)
Location: include/linux/percpu_counter.h:187
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_release_space
  - fs/ext4/inode.c:ext4_da_update_reserve_space
```
```
In fs/ext4/mballoc.c (ffffffff813b4fd9)
Location: include/linux/percpu_counter.h:187
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
```
```
In fs/ext4/super.c (ffffffff813d8cc6)
Location: include/linux/percpu_counter.h:187
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
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
In mm/shmem.c (ffffffff81246715)
Location: include/linux/percpu_counter.h:187
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_recalc_inode
```
```
In fs/ext4/inode.c (ffffffff813b861b)
Location: include/linux/percpu_counter.h:187
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_release_space
  - fs/ext4/inode.c:ext4_da_update_reserve_space
```
```
In fs/ext4/mballoc.c (ffffffff813c9c28)
Location: include/linux/percpu_counter.h:187
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
```
```
In fs/ext4/super.c (ffffffff813edfa8)
Location: include/linux/percpu_counter.h:187
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
```
</details>
</li>
</ul>

## Differences
