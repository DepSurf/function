# Function: <code>test_bit_le</code>

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
In fs/ext4/balloc.c (ffffffff8128f136)
Location: include/asm-generic/bitops/le.h:52
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
```
```
In fs/ext4/ialloc.c (ffffffff81295670)
Location: include/asm-generic/bitops/le.h:52
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
```
```
In fs/ext4/inode.c (ffffffff8129652e)
Location: include/asm-generic/bitops/le.h:52
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
```
```
In fs/ext4/mballoc.c (ffffffff812cd14d)
Location: include/asm-generic/bitops/le.h:52
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:mb_find_order_for_block
  - fs/ext4/mballoc.c:mb_find_extent
  - fs/ext4/mballoc.c:mb_find_extent
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:ext4_mb_scan_aligned
  - fs/ext4/mballoc.c:ext4_group_add_blocks
```
```
In drivers/md/bitmap.c (ffffffff8169d9b7)
Location: include/asm-generic/bitops/le.h:52
Inline: True
Inline callers:
  - drivers/md/bitmap.c:bitmap_init_from_disk
  - drivers/md/bitmap.c:bitmap_copy_from_slot
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
In fs/ext4/balloc.c (ffffffff812bc663)
Location: include/asm-generic/bitops/le.h:52
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
```
```
In fs/ext4/ialloc.c (ffffffff812c2ccb)
Location: include/asm-generic/bitops/le.h:52
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
```
```
In fs/ext4/inode.c (ffffffff812c3acc)
Location: include/asm-generic/bitops/le.h:52
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
```
```
In fs/ext4/mballoc.c (ffffffff81305111)
Location: include/asm-generic/bitops/le.h:52
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_mb_scan_aligned
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_find_extent
  - fs/ext4/mballoc.c:mb_find_extent
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_find_order_for_block
```
```
In drivers/md/bitmap.c (ffffffff81700c09)
Location: include/asm-generic/bitops/le.h:52
Inline: True
Inline callers:
  - drivers/md/bitmap.c:bitmap_copy_from_slot
  - drivers/md/bitmap.c:bitmap_init_from_disk
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
In fs/ext4/balloc.c (ffffffff812d1cb3)
Location: include/asm-generic/bitops/le.h:52
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
```
```
In fs/ext4/ialloc.c (ffffffff812d82bb)
Location: include/asm-generic/bitops/le.h:52
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
```
```
In fs/ext4/inode.c (ffffffff812d917c)
Location: include/asm-generic/bitops/le.h:52
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
```
```
In fs/ext4/mballoc.c (ffffffff8131b0e1)
Location: include/asm-generic/bitops/le.h:52
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_mb_scan_aligned
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_find_extent
  - fs/ext4/mballoc.c:mb_find_extent
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_find_order_for_block
```
```
In drivers/md/bitmap.c (ffffffff81732970)
Location: include/asm-generic/bitops/le.h:52
Inline: True
Inline callers:
  - drivers/md/bitmap.c:bitmap_copy_from_slot
  - drivers/md/bitmap.c:bitmap_init_from_disk
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
In fs/ext4/balloc.c (ffffffff812e335a)
Location: include/asm-generic/bitops/le.h:52
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
```
```
In fs/ext4/ialloc.c (ffffffff812f664b)
Location: include/asm-generic/bitops/le.h:52
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
```
```
In fs/ext4/inode.c (ffffffff812ff892)
Location: include/asm-generic/bitops/le.h:52
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
```
```
In fs/ext4/mballoc.c (ffffffff81312513)
Location: include/asm-generic/bitops/le.h:52
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_mb_scan_aligned
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_find_extent
  - fs/ext4/mballoc.c:mb_find_extent
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_find_order_for_block
```
```
In drivers/md/bitmap.c (ffffffff8174b72e)
Location: include/asm-generic/bitops/le.h:52
Inline: True
Inline callers:
  - drivers/md/bitmap.c:bitmap_copy_from_slot
  - drivers/md/bitmap.c:bitmap_init_from_disk
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
In fs/ext4/balloc.c (ffffffff81307d4a)
Location: include/asm-generic/bitops/le.h:53
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
```
```
In fs/ext4/ialloc.c (ffffffff8131ac7b)
Location: include/asm-generic/bitops/le.h:53
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
```
```
In fs/ext4/inode.c (ffffffff81324042)
Location: include/asm-generic/bitops/le.h:53
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
```
```
In fs/ext4/mballoc.c (ffffffff81336d19)
Location: include/asm-generic/bitops/le.h:53
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_mb_scan_aligned
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_find_extent
  - fs/ext4/mballoc.c:mb_find_extent
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_find_order_for_block
```
```
In drivers/md/md-bitmap.c (ffffffff817bda8a)
Location: include/asm-generic/bitops/le.h:53
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:bitmap_copy_from_slot
  - drivers/md/md-bitmap.c:bitmap_init_from_disk
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
In fs/ext4/balloc.c (ffffffff81335c7e)
Location: include/asm-generic/bitops/le.h:53
Inline: True
```
```
In fs/ext4/ialloc.c (ffffffff81348c02)
Location: include/asm-generic/bitops/le.h:53
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
```
```
In fs/ext4/inode.c (ffffffff81350a5a)
Location: include/asm-generic/bitops/le.h:53
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
```
```
In fs/ext4/mballoc.c (ffffffff813652cf)
Location: include/asm-generic/bitops/le.h:53
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_mb_scan_aligned
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_find_extent
  - fs/ext4/mballoc.c:mb_find_extent
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_find_order_for_block
```
```
In drivers/md/md-bitmap.c (ffffffff81805a8c)
Location: include/asm-generic/bitops/le.h:53
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:bitmap_copy_from_slot
  - drivers/md/md-bitmap.c:bitmap_init_from_disk
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
In fs/ext4/balloc.c (ffffffff8134cefe)
Location: include/asm-generic/bitops/le.h:53
Inline: True
```
```
In fs/ext4/ialloc.c (ffffffff81360db2)
Location: include/asm-generic/bitops/le.h:53
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
```
```
In fs/ext4/inode.c (ffffffff81369eea)
Location: include/asm-generic/bitops/le.h:53
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
```
```
In fs/ext4/mballoc.c (ffffffff8137d68f)
Location: include/asm-generic/bitops/le.h:53
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_mb_scan_aligned
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_find_extent
  - fs/ext4/mballoc.c:mb_find_extent
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_find_order_for_block
```
```
In drivers/nvdimm/label.c (ffffffff816feac4)
Location: include/asm-generic/bitops/le.h:53
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_data_init
```
```
In drivers/md/md-bitmap.c (ffffffff81831c8f)
Location: include/asm-generic/bitops/le.h:53
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
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
In fs/ext4/balloc.c (ffffffff813758d0)
Location: include/asm-generic/bitops/le.h:53
Inline: True
```
```
In fs/ext4/ialloc.c (ffffffff81389eba)
Location: include/asm-generic/bitops/le.h:53
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
```
```
In fs/ext4/inode.c (ffffffff8139332c)
Location: include/asm-generic/bitops/le.h:53
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
```
```
In fs/ext4/mballoc.c (ffffffff813a7228)
Location: include/asm-generic/bitops/le.h:53
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_mb_scan_aligned
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_find_extent
  - fs/ext4/mballoc.c:mb_find_extent
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_find_order_for_block
```
```
In drivers/nvdimm/label.c (ffffffff81738b7b)
Location: include/asm-generic/bitops/le.h:53
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_data_init
```
```
In drivers/md/md-bitmap.c (ffffffff81874428)
Location: include/asm-generic/bitops/le.h:53
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
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
In fs/ext4/balloc.c (ffffffff8138db39)
Location: include/asm-generic/bitops/le.h:53
Inline: True
```
```
In fs/ext4/ialloc.c (ffffffff813a28da)
Location: include/asm-generic/bitops/le.h:53
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
```
```
In fs/ext4/inode.c (ffffffff813abbf3)
Location: include/asm-generic/bitops/le.h:53
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
```
```
In fs/ext4/mballoc.c (ffffffff813c00b8)
Location: include/asm-generic/bitops/le.h:53
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_mb_scan_aligned
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_find_extent
  - fs/ext4/mballoc.c:mb_find_extent
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_find_order_for_block
```
```
In drivers/nvdimm/label.c (ffffffff8175c87b)
Location: include/asm-generic/bitops/le.h:53
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_data_init
```
```
In drivers/md/md-bitmap.c (ffffffff818a6238)
Location: include/asm-generic/bitops/le.h:53
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
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
In fs/ext4/balloc.c (ffffffff813d8ec9)
Location: include/asm-generic/bitops/le.h:53
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_valid_block_bitmap
  - fs/ext4/balloc.c:ext4_valid_block_bitmap
```
```
In fs/ext4/ialloc.c (ffffffff813ee91e)
Location: include/asm-generic/bitops/le.h:53
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
```
```
In fs/ext4/inode.c (ffffffff813f7f30)
Location: include/asm-generic/bitops/le.h:53
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
```
```
In fs/ext4/mballoc.c (ffffffff8140c1d2)
Location: include/asm-generic/bitops/le.h:53
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_mb_scan_aligned
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_find_extent
  - fs/ext4/mballoc.c:mb_find_extent
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_buddy_mark_free
  - fs/ext4/mballoc.c:mb_buddy_mark_free
  - fs/ext4/mballoc.c:mb_find_order_for_block
```
```
In drivers/nvdimm/label.c (ffffffff8181c0b8)
Location: include/asm-generic/bitops/le.h:53
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_data_init
```
```
In drivers/md/md-bitmap.c (ffffffff819762ba)
Location: include/asm-generic/bitops/le.h:53
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
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
In fs/ext4/balloc.c (ffffffff813eaad9)
Location: include/asm-generic/bitops/le.h:53
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_valid_block_bitmap
  - fs/ext4/balloc.c:ext4_valid_block_bitmap
```
```
In fs/ext4/ialloc.c (ffffffff81401080)
Location: include/asm-generic/bitops/le.h:53
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_mark_inode_used
```
```
In fs/ext4/inode.c (ffffffff81409c1e)
Location: include/asm-generic/bitops/le.h:53
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
```
```
In fs/ext4/mballoc.c (ffffffff8141f605)
Location: include/asm-generic/bitops/le.h:53
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_bb
  - fs/ext4/mballoc.c:ext4_mb_scan_aligned
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_find_extent
  - fs/ext4/mballoc.c:mb_find_extent
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_buddy_mark_free
  - fs/ext4/mballoc.c:mb_buddy_mark_free
  - fs/ext4/mballoc.c:mb_find_order_for_block
```
```
In drivers/nvdimm/label.c (ffffffff8182b108)
Location: include/asm-generic/bitops/le.h:53
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_data_init
```
```
In drivers/md/md-bitmap.c (ffffffff8197b2aa)
Location: include/asm-generic/bitops/le.h:53
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
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
In fs/ext4/balloc.c (ffffffff813f0ffa)
Location: include/asm-generic/bitops/le.h:83
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_valid_block_bitmap
  - fs/ext4/balloc.c:ext4_valid_block_bitmap
```
```
In fs/ext4/ialloc.c (ffffffff814075c2)
Location: include/asm-generic/bitops/le.h:83
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_mark_inode_used
```
```
In fs/ext4/inode.c (ffffffff8140fddb)
Location: include/asm-generic/bitops/le.h:83
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
```
```
In fs/ext4/mballoc.c (ffffffff81425f46)
Location: include/asm-generic/bitops/le.h:83
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_bb
  - fs/ext4/mballoc.c:ext4_mb_scan_aligned
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_find_extent
  - fs/ext4/mballoc.c:mb_find_extent
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_buddy_mark_free
  - fs/ext4/mballoc.c:mb_buddy_mark_free
  - fs/ext4/mballoc.c:mb_find_order_for_block
```
```
In drivers/nvdimm/label.c (ffffffff8180e3e5)
Location: include/asm-generic/bitops/le.h:83
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_data_init
```
```
In drivers/md/md-bitmap.c (ffffffff8195f4c7)
Location: include/asm-generic/bitops/le.h:83
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
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
In fs/ext4/balloc.c (ffffffff81442f65)
Location: include/asm-generic/bitops/le.h:83
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_valid_block_bitmap
  - fs/ext4/balloc.c:ext4_valid_block_bitmap
```
```
In fs/ext4/ialloc.c (ffffffff81459e62)
Location: include/asm-generic/bitops/le.h:83
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_mark_inode_used
```
```
In fs/ext4/inode.c (ffffffff81462ea9)
Location: include/asm-generic/bitops/le.h:83
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
```
```
In fs/ext4/mballoc.c (ffffffff81479b36)
Location: include/asm-generic/bitops/le.h:83
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_bb
  - fs/ext4/mballoc.c:ext4_mb_scan_aligned
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_find_extent
  - fs/ext4/mballoc.c:mb_find_extent
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_buddy_mark_free
  - fs/ext4/mballoc.c:mb_buddy_mark_free
```
```
In drivers/nvdimm/label.c (ffffffff818989f5)
Location: include/asm-generic/bitops/le.h:83
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_data_init
```
```
In drivers/md/md-bitmap.c (ffffffff81a04e16)
Location: include/asm-generic/bitops/le.h:83
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int test_bit_le(int nr, const void *addr);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff814bed9f)
Location: include/asm-generic/bitops/le.h:19
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_valid_block_bitmap
  - fs/ext4/balloc.c:ext4_valid_block_bitmap
```
```
In fs/ext4/ialloc.c (ffffffff814d7b14)
Location: include/asm-generic/bitops/le.h:19
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_mark_inode_used
Direct callers:
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
```
```
In fs/ext4/inode.c (ffffffff814e2a9d)
Location: include/asm-generic/bitops/le.h:19
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
```
```
In fs/ext4/mballoc.c (ffffffff814fbba2)
Location: include/asm-generic/bitops/le.h:19
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_bb
  - fs/ext4/mballoc.c:ext4_mb_scan_aligned
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_find_extent
  - fs/ext4/mballoc.c:mb_find_extent
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_buddy_mark_free
  - fs/ext4/mballoc.c:mb_buddy_mark_free
  - fs/ext4/mballoc.c:mb_find_order_for_block
```
```
In drivers/nvdimm/label.c (ffffffff819e28ea)
Location: include/asm-generic/bitops/le.h:19
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_data_init
```
```
In drivers/md/md-bitmap.c (ffffffff81b6cb0d)
Location: include/asm-generic/bitops/le.h:19
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
```
**Symbols:**

```
ffffffff814d4860-ffffffff814d4875: test_bit_le (STB_LOCAL)
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
In fs/ext4/balloc.c (ffffffff81556c8f)
Location: include/asm-generic/bitops/le.h:19
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_valid_block_bitmap
  - fs/ext4/balloc.c:ext4_valid_block_bitmap
```
```
In fs/ext4/ialloc.c (ffffffff8157088a)
Location: include/asm-generic/bitops/le.h:19
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_mark_inode_used
```
```
In fs/ext4/inode.c (ffffffff8157bee7)
Location: include/asm-generic/bitops/le.h:19
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
```
```
In fs/ext4/mballoc.c (ffffffff81596382)
Location: include/asm-generic/bitops/le.h:19
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_bb
  - fs/ext4/mballoc.c:ext4_mb_scan_aligned
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_find_extent
  - fs/ext4/mballoc.c:mb_find_extent
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_buddy_mark_free
  - fs/ext4/mballoc.c:mb_buddy_mark_free
  - fs/ext4/mballoc.c:mb_find_order_for_block
```
```
In drivers/nvdimm/label.c (ffffffff81b5e4e3)
Location: include/asm-generic/bitops/le.h:19
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_data_init
```
```
In drivers/md/md-bitmap.c (ffffffff81d08c1d)
Location: include/asm-generic/bitops/le.h:19
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
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
In fs/ext4/balloc.c (ffffffff8158ea4f)
Location: include/asm-generic/bitops/le.h:19
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_valid_block_bitmap
  - fs/ext4/balloc.c:ext4_valid_block_bitmap
```
```
In fs/ext4/ialloc.c (ffffffff815a867a)
Location: include/asm-generic/bitops/le.h:19
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_mark_inode_used
```
```
In fs/ext4/inode.c (ffffffff815b32e7)
Location: include/asm-generic/bitops/le.h:19
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
```
```
In fs/ext4/mballoc.c (ffffffff815ccd55)
Location: include/asm-generic/bitops/le.h:19
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_bb
  - fs/ext4/mballoc.c:ext4_mb_scan_aligned
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_find_extent
  - fs/ext4/mballoc.c:mb_find_extent
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_buddy_mark_free
  - fs/ext4/mballoc.c:mb_buddy_mark_free
  - fs/ext4/mballoc.c:mb_find_order_for_block
```
```
In drivers/nvdimm/label.c (ffffffff81bb1a95)
Location: include/asm-generic/bitops/le.h:19
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_data_init
```
```
In drivers/md/md-bitmap.c (ffffffff81d71d90)
Location: include/asm-generic/bitops/le.h:19
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
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
In fs/ext4/balloc.c (ffffffff815c775f)
Location: include/asm-generic/bitops/le.h:19
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_valid_block_bitmap
  - fs/ext4/balloc.c:ext4_valid_block_bitmap
```
```
In fs/ext4/ialloc.c (ffffffff815e142a)
Location: include/asm-generic/bitops/le.h:19
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_mark_inode_used
```
```
In fs/ext4/inode.c (ffffffff815ec0f7)
Location: include/asm-generic/bitops/le.h:19
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
```
```
In fs/ext4/mballoc.c (ffffffff8160151e)
Location: include/asm-generic/bitops/le.h:19
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_mark_context
  - fs/ext4/mballoc.c:ext4_mb_scan_aligned
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_find_extent
  - fs/ext4/mballoc.c:mb_find_extent
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_buddy_mark_free
  - fs/ext4/mballoc.c:mb_buddy_mark_free
  - fs/ext4/mballoc.c:mb_find_order_for_block
```
```
In drivers/nvdimm/label.c (ffffffff81c05f85)
Location: include/asm-generic/bitops/le.h:19
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_data_init
```
```
In drivers/md/md-bitmap.c (ffffffff81e28e63)
Location: include/asm-generic/bitops/le.h:19
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
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
In fs/ext4/balloc.c (ffff80001045fb5c)
Location: include/asm-generic/bitops/le.h:53
Inline: True
```
```
In fs/ext4/ialloc.c (ffff800010475f14)
Location: include/asm-generic/bitops/le.h:53
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
```
```
In fs/ext4/inode.c (ffff80001048043c)
Location: include/asm-generic/bitops/le.h:53
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
```
```
In fs/ext4/mballoc.c (ffff800010496cec)
Location: include/asm-generic/bitops/le.h:53
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_mb_scan_aligned
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_find_extent
  - fs/ext4/mballoc.c:mb_find_extent
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_find_order_for_block
```
```
In drivers/nvdimm/label.c (ffff80001095df7c)
Location: include/asm-generic/bitops/le.h:53
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_data_init
```
```
In drivers/md/md-bitmap.c (ffff800010afb14c)
Location: include/asm-generic/bitops/le.h:53
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
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
In fs/ext4/balloc.c (c0620328)
Location: include/asm-generic/bitops/le.h:53
Inline: True
```
```
In fs/ext4/ialloc.c (c063794c)
Location: include/asm-generic/bitops/le.h:53
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
```
```
In fs/ext4/inode.c (c0641868)
Location: include/asm-generic/bitops/le.h:53
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
```
```
In fs/ext4/mballoc.c (c0658d84)
Location: include/asm-generic/bitops/le.h:53
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_mb_scan_aligned
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_find_extent
  - fs/ext4/mballoc.c:mb_find_extent
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_find_order_for_block
```
```
In drivers/md/md-bitmap.c (0)
Location: include/asm-generic/bitops/le.h:53
Inline: True
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
In fs/ext4/balloc.c (c00000000057bdf8)
Location: include/asm-generic/bitops/le.h:53
Inline: True
```
```
In fs/ext4/ialloc.c (c000000000597d6c)
Location: include/asm-generic/bitops/le.h:53
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
```
```
In fs/ext4/inode.c (c0000000005a4ab8)
Location: include/asm-generic/bitops/le.h:53
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
```
```
In fs/ext4/mballoc.c (c0000000005c0fb4)
Location: include/asm-generic/bitops/le.h:53
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_mb_scan_aligned
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_find_extent
  - fs/ext4/mballoc.c:mb_find_extent
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_find_order_for_block
```
```
In drivers/nvdimm/label.c (c000000000a0fcd8)
Location: include/asm-generic/bitops/le.h:53
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_data_init
```
```
In drivers/md/md-bitmap.c (0)
Location: include/asm-generic/bitops/le.h:53
Inline: True
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
In fs/ext4/balloc.c (ffffffe0002ef25a)
Location: include/asm-generic/bitops/le.h:53
Inline: True
```
```
In fs/ext4/ialloc.c (ffffffe0003018e6)
Location: include/asm-generic/bitops/le.h:53
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
```
```
In fs/ext4/inode.c (ffffffe00030917e)
Location: include/asm-generic/bitops/le.h:53
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
```
```
In fs/ext4/mballoc.c (ffffffe00031b70a)
Location: include/asm-generic/bitops/le.h:53
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_mb_scan_aligned
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_find_extent
  - fs/ext4/mballoc.c:mb_find_extent
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_find_order_for_block
```
```
In drivers/nvdimm/label.c (ffffffe0005cbfd6)
Location: include/asm-generic/bitops/le.h:53
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_data_init
```
```
In drivers/md/md-bitmap.c (0)
Location: include/asm-generic/bitops/le.h:53
Inline: True
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
In fs/ext4/balloc.c (ffffffff81386119)
Location: include/asm-generic/bitops/le.h:53
Inline: True
```
```
In fs/ext4/ialloc.c (ffffffff8139aeba)
Location: include/asm-generic/bitops/le.h:53
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
```
```
In fs/ext4/inode.c (ffffffff813a41d3)
Location: include/asm-generic/bitops/le.h:53
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
```
```
In fs/ext4/mballoc.c (ffffffff813b8698)
Location: include/asm-generic/bitops/le.h:53
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_mb_scan_aligned
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_find_extent
  - fs/ext4/mballoc.c:mb_find_extent
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_find_order_for_block
```
```
In drivers/nvdimm/label.c (ffffffff81710f6b)
Location: include/asm-generic/bitops/le.h:53
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_data_init
```
```
In drivers/md/md-bitmap.c (ffffffff8184c0b8)
Location: include/asm-generic/bitops/le.h:53
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
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
In fs/ext4/balloc.c (ffffffff81376ba9)
Location: include/asm-generic/bitops/le.h:53
Inline: True
```
```
In fs/ext4/ialloc.c (ffffffff8138b94a)
Location: include/asm-generic/bitops/le.h:53
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
```
```
In fs/ext4/inode.c (ffffffff81394c63)
Location: include/asm-generic/bitops/le.h:53
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
```
```
In fs/ext4/mballoc.c (ffffffff813a9128)
Location: include/asm-generic/bitops/le.h:53
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_mb_scan_aligned
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_find_extent
  - fs/ext4/mballoc.c:mb_find_extent
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_find_order_for_block
```
```
In drivers/nvdimm/label.c (ffffffff816e49eb)
Location: include/asm-generic/bitops/le.h:53
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_data_init
```
```
In drivers/md/md-bitmap.c (ffffffff818136d8)
Location: include/asm-generic/bitops/le.h:53
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
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
In fs/ext4/balloc.c (ffffffff81383be9)
Location: include/asm-generic/bitops/le.h:53
Inline: True
```
```
In fs/ext4/ialloc.c (ffffffff8139871a)
Location: include/asm-generic/bitops/le.h:53
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
```
```
In fs/ext4/inode.c (ffffffff813a1a33)
Location: include/asm-generic/bitops/le.h:53
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
```
```
In fs/ext4/mballoc.c (ffffffff813b5ef8)
Location: include/asm-generic/bitops/le.h:53
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_mb_scan_aligned
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_find_extent
  - fs/ext4/mballoc.c:mb_find_extent
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_find_order_for_block
```
```
In drivers/nvdimm/label.c (ffffffff8174fd3b)
Location: include/asm-generic/bitops/le.h:53
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_data_init
```
```
In drivers/md/md-bitmap.c (ffffffff8189b6e8)
Location: include/asm-generic/bitops/le.h:53
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
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
In fs/ext4/balloc.c (ffffffff8139770b)
Location: include/asm-generic/bitops/le.h:53
Inline: True
```
```
In fs/ext4/ialloc.c (ffffffff813acb3a)
Location: include/asm-generic/bitops/le.h:53
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
```
```
In fs/ext4/inode.c (ffffffff813b664f)
Location: include/asm-generic/bitops/le.h:53
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
```
```
In fs/ext4/mballoc.c (ffffffff813cabe8)
Location: include/asm-generic/bitops/le.h:53
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_mb_scan_aligned
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_find_extent
  - fs/ext4/mballoc.c:mb_find_extent
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_find_order_for_block
```
```
In drivers/nvdimm/label.c (ffffffff8176b1bb)
Location: include/asm-generic/bitops/le.h:53
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_data_init
```
```
In drivers/md/md-bitmap.c (ffffffff818b787f)
Location: include/asm-generic/bitops/le.h:53
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
