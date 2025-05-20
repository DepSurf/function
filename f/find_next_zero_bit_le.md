# Function: <code>find_next_zero_bit_le</code>

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
In fs/ext4/balloc.c (ffffffff8128f224)
Location: include/asm-generic/bitops/le.h:11
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
```
```
In fs/ext4/ialloc.c (ffffffff812946f6)
Location: include/asm-generic/bitops/le.h:11
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/mballoc.c (ffffffff812ce238)
Location: include/asm-generic/bitops/le.h:11
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_simple_scan_group
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
  - fs/ext4/mballoc.c:ext4_trim_fs
```
```
In drivers/nvdimm/label.c (ffffffff8159f5f9)
Location: include/asm-generic/bitops/le.h:11
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
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
In fs/ext4/balloc.c (ffffffff812bc740)
Location: include/asm-generic/bitops/le.h:11
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
```
```
In fs/ext4/ialloc.c (ffffffff812c1cf1)
Location: include/asm-generic/bitops/le.h:11
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/mballoc.c (ffffffff8130566d)
Location: include/asm-generic/bitops/le.h:11
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
  - fs/ext4/mballoc.c:ext4_mb_simple_scan_group
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In drivers/nvdimm/label.c (ffffffff815f6336)
Location: include/asm-generic/bitops/le.h:11
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
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
In fs/ext4/balloc.c (ffffffff812d1d90)
Location: include/asm-generic/bitops/le.h:11
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
```
```
In fs/ext4/ialloc.c (ffffffff812d7353)
Location: include/asm-generic/bitops/le.h:11
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/mballoc.c (ffffffff8131b62b)
Location: include/asm-generic/bitops/le.h:11
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
  - fs/ext4/mballoc.c:ext4_mb_simple_scan_group
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In drivers/nvdimm/label.c (ffffffff81624163)
Location: include/asm-generic/bitops/le.h:11
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
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
In fs/ext4/balloc.c (ffffffff812e3437)
Location: include/asm-generic/bitops/le.h:11
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
```
```
In fs/ext4/ialloc.c (ffffffff812f56e8)
Location: include/asm-generic/bitops/le.h:11
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/mballoc.c (ffffffff813131ac)
Location: include/asm-generic/bitops/le.h:11
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
  - fs/ext4/mballoc.c:ext4_mb_simple_scan_group
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In drivers/nvdimm/label.c (ffffffff81638e50)
Location: include/asm-generic/bitops/le.h:11
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
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
In fs/ext4/balloc.c (ffffffff81307e27)
Location: include/asm-generic/bitops/le.h:12
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
```
```
In fs/ext4/ialloc.c (ffffffff81318450)
Location: include/asm-generic/bitops/le.h:12
Inline: True
```
```
In fs/ext4/mballoc.c (ffffffff8133796c)
Location: include/asm-generic/bitops/le.h:12
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
  - fs/ext4/mballoc.c:ext4_mb_simple_scan_group
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In drivers/nvdimm/label.c (ffffffff816a1530)
Location: include/asm-generic/bitops/le.h:12
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
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
In fs/ext4/balloc.c (ffffffff81335d6f)
Location: include/asm-generic/bitops/le.h:12
Inline: True
```
```
In fs/ext4/ialloc.c (ffffffff81346890)
Location: include/asm-generic/bitops/le.h:12
Inline: True
```
```
In fs/ext4/mballoc.c (ffffffff81365eba)
Location: include/asm-generic/bitops/le.h:12
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
  - fs/ext4/mballoc.c:ext4_mb_simple_scan_group
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In drivers/nvdimm/label.c (ffffffff816ddcec)
Location: include/asm-generic/bitops/le.h:12
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
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
In fs/ext4/balloc.c (ffffffff8134cfef)
Location: include/asm-generic/bitops/le.h:12
Inline: True
```
```
In fs/ext4/ialloc.c (ffffffff8135e580)
Location: include/asm-generic/bitops/le.h:12
Inline: True
```
```
In fs/ext4/mballoc.c (ffffffff8137e31a)
Location: include/asm-generic/bitops/le.h:12
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
  - fs/ext4/mballoc.c:ext4_mb_simple_scan_group
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In drivers/nvdimm/label.c (ffffffff81700050)
Location: include/asm-generic/bitops/le.h:12
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
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
In fs/ext4/balloc.c (ffffffff813759cd)
Location: include/asm-generic/bitops/le.h:12
Inline: True
```
```
In fs/ext4/ialloc.c (ffffffff81387761)
Location: include/asm-generic/bitops/le.h:12
Inline: True
```
```
In fs/ext4/mballoc.c (ffffffff813a7788)
Location: include/asm-generic/bitops/le.h:12
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
  - fs/ext4/mballoc.c:ext4_mb_simple_scan_group
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In drivers/nvdimm/label.c (ffffffff81739e21)
Location: include/asm-generic/bitops/le.h:12
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
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
In fs/ext4/balloc.c (ffffffff8138dc38)
Location: include/asm-generic/bitops/le.h:12
Inline: True
```
```
In fs/ext4/ialloc.c (ffffffff813a0651)
Location: include/asm-generic/bitops/le.h:12
Inline: True
```
```
In fs/ext4/mballoc.c (ffffffff813c0628)
Location: include/asm-generic/bitops/le.h:12
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
  - fs/ext4/mballoc.c:ext4_mb_simple_scan_group
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In drivers/nvdimm/label.c (ffffffff8175db71)
Location: include/asm-generic/bitops/le.h:12
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
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
In fs/ext4/balloc.c (ffffffff813d8f50)
Location: include/asm-generic/bitops/le.h:12
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_valid_block_bitmap
```
```
In fs/ext4/ialloc.c (ffffffff813ec0d2)
Location: include/asm-generic/bitops/le.h:12
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:find_inode_bit
```
```
In fs/ext4/mballoc.c (ffffffff8140c758)
Location: include/asm-generic/bitops/le.h:12
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
  - fs/ext4/mballoc.c:ext4_mb_simple_scan_group
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In drivers/nvdimm/label.c (ffffffff8181d6c3)
Location: include/asm-generic/bitops/le.h:12
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
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
In fs/ext4/balloc.c (ffffffff813eab60)
Location: include/asm-generic/bitops/le.h:12
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_valid_block_bitmap
```
```
In fs/ext4/ialloc.c (ffffffff813fe282)
Location: include/asm-generic/bitops/le.h:12
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:find_inode_bit
```
```
In fs/ext4/mballoc.c (ffffffff8141fbc8)
Location: include/asm-generic/bitops/le.h:12
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
  - fs/ext4/mballoc.c:ext4_mb_simple_scan_group
  - fs/ext4/mballoc.c:mb_test_and_clear_bits
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In drivers/nvdimm/label.c (ffffffff8182c7e7)
Location: include/asm-generic/bitops/le.h:12
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
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
In fs/ext4/balloc.c (ffffffff813f1083)
Location: include/asm-generic/bitops/le.h:14
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_valid_block_bitmap
```
```
In fs/ext4/ialloc.c (ffffffff8140466f)
Location: include/asm-generic/bitops/le.h:14
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:find_inode_bit
```
```
In fs/ext4/mballoc.c (ffffffff81426474)
Location: include/asm-generic/bitops/le.h:14
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
  - fs/ext4/mballoc.c:ext4_mb_simple_scan_group
  - fs/ext4/mballoc.c:mb_test_and_clear_bits
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In drivers/nvdimm/label.c (ffffffff8180fafe)
Location: include/asm-generic/bitops/le.h:14
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
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
In fs/ext4/balloc.c (ffffffff81443044)
Location: include/asm-generic/bitops/le.h:14
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_valid_block_bitmap
```
```
In fs/ext4/ialloc.c (ffffffff81456e1f)
Location: include/asm-generic/bitops/le.h:14
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:find_inode_bit
```
```
In fs/ext4/mballoc.c (ffffffff8147a123)
Location: include/asm-generic/bitops/le.h:14
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_try_to_trim_range
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
  - fs/ext4/mballoc.c:ext4_mb_simple_scan_group
  - fs/ext4/mballoc.c:mb_test_and_clear_bits
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In drivers/nvdimm/label.c (ffffffff8189a04e)
Location: include/asm-generic/bitops/le.h:14
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
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
In fs/ext4/balloc.c (ffffffff814bee82)
Location: include/linux/find.h:215
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_valid_block_bitmap
```
```
In fs/ext4/ialloc.c (ffffffff814d48ff)
Location: include/linux/find.h:215
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:find_inode_bit
```
```
In fs/ext4/mballoc.c (ffffffff814fc3f1)
Location: include/linux/find.h:215
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_try_to_trim_range
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
  - fs/ext4/mballoc.c:ext4_mb_simple_scan_group
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In drivers/nvdimm/label.c (ffffffff819e2b92)
Location: include/linux/find.h:215
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
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
In fs/ext4/balloc.c (ffffffff81556d63)
Location: include/linux/find.h:417
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_valid_block_bitmap
```
```
In fs/ext4/ialloc.c (ffffffff8156d5bf)
Location: include/linux/find.h:417
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:find_inode_bit
```
```
In fs/ext4/mballoc.c (ffffffff81596b4e)
Location: include/linux/find.h:417
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_try_to_trim_range
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
  - fs/ext4/mballoc.c:ext4_mb_simple_scan_group
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In drivers/nvdimm/label.c (ffffffff81b5e776)
Location: include/linux/find.h:417
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
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
In fs/ext4/balloc.c (ffffffff8158ef34)
Location: include/linux/find.h:482
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
  - fs/ext4/balloc.c:ext4_valid_block_bitmap
```
```
In fs/ext4/ialloc.c (ffffffff815a54af)
Location: include/linux/find.h:482
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:find_inode_bit
```
```
In fs/ext4/mballoc.c (ffffffff815cd56e)
Location: include/linux/find.h:482
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_try_to_trim_range
  - fs/ext4/mballoc.c:ext4_mb_new_blocks_simple
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
  - fs/ext4/mballoc.c:ext4_mb_simple_scan_group
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In drivers/nvdimm/label.c (ffffffff81bb1d26)
Location: include/linux/find.h:482
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
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
In fs/ext4/balloc.c (ffffffff815c7c44)
Location: include/linux/find.h:482
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
  - fs/ext4/balloc.c:ext4_valid_block_bitmap
```
```
In fs/ext4/ialloc.c (ffffffff815de31f)
Location: include/linux/find.h:482
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:find_inode_bit
```
```
In fs/ext4/mballoc.c (ffffffff81605dee)
Location: include/linux/find.h:482
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_try_to_trim_range
  - fs/ext4/mballoc.c:ext4_mb_new_blocks_simple
  - fs/ext4/mballoc.c:ext4_mb_release_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
  - fs/ext4/mballoc.c:ext4_mb_simple_scan_group
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In drivers/nvdimm/label.c (ffffffff81c06216)
Location: include/linux/find.h:482
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
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
In fs/ext4/balloc.c (ffff80001045fc94)
Location: include/asm-generic/bitops/le.h:12
Inline: True
```
```
In fs/ext4/ialloc.c (ffff800010473af8)
Location: include/asm-generic/bitops/le.h:12
Inline: True
```
```
In fs/ext4/mballoc.c (ffff80001049725c)
Location: include/asm-generic/bitops/le.h:12
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
  - fs/ext4/mballoc.c:ext4_mb_simple_scan_group
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In drivers/nvdimm/label.c (ffff80001095f258)
Location: include/asm-generic/bitops/le.h:12
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
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
In fs/ext4/balloc.c (c062046c)
Location: include/asm-generic/bitops/le.h:12
Inline: True
```
```
In fs/ext4/ialloc.c (c0634b6c)
Location: include/asm-generic/bitops/le.h:12
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:find_inode_bit
```
```
In fs/ext4/mballoc.c (c0659558)
Location: include/asm-generic/bitops/le.h:12
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_mb_release_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
  - fs/ext4/mballoc.c:ext4_mb_simple_scan_group
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
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
In fs/ext4/balloc.c (c00000000057bf14)
Location: include/asm-generic/bitops/le.h:12
Inline: True
```
```
In fs/ext4/ialloc.c (c000000000595050)
Location: include/asm-generic/bitops/le.h:12
Inline: True
```
```
In fs/ext4/mballoc.c (c0000000005c17dc)
Location: include/asm-generic/bitops/le.h:12
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
  - fs/ext4/mballoc.c:ext4_mb_simple_scan_group
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In drivers/nvdimm/label.c (c000000000a119e8)
Location: include/asm-generic/bitops/le.h:12
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
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
In fs/ext4/balloc.c (ffffffe0002ef38a)
Location: include/asm-generic/bitops/le.h:12
Inline: True
```
```
In fs/ext4/ialloc.c (ffffffe0002ff858)
Location: include/asm-generic/bitops/le.h:12
Inline: True
```
```
In fs/ext4/mballoc.c (ffffffe00031bc48)
Location: include/asm-generic/bitops/le.h:12
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
  - fs/ext4/mballoc.c:ext4_mb_simple_scan_group
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In drivers/nvdimm/label.c (ffffffe0005ccfaa)
Location: include/asm-generic/bitops/le.h:12
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
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
In fs/ext4/balloc.c (ffffffff81386218)
Location: include/asm-generic/bitops/le.h:12
Inline: True
```
```
In fs/ext4/ialloc.c (ffffffff81398c31)
Location: include/asm-generic/bitops/le.h:12
Inline: True
```
```
In fs/ext4/mballoc.c (ffffffff813b8c08)
Location: include/asm-generic/bitops/le.h:12
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
  - fs/ext4/mballoc.c:ext4_mb_simple_scan_group
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In drivers/nvdimm/label.c (ffffffff81712261)
Location: include/asm-generic/bitops/le.h:12
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
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
In fs/ext4/balloc.c (ffffffff81376ca8)
Location: include/asm-generic/bitops/le.h:12
Inline: True
```
```
In fs/ext4/ialloc.c (ffffffff813896c1)
Location: include/asm-generic/bitops/le.h:12
Inline: True
```
```
In fs/ext4/mballoc.c (ffffffff813a9698)
Location: include/asm-generic/bitops/le.h:12
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
  - fs/ext4/mballoc.c:ext4_mb_simple_scan_group
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In drivers/nvdimm/label.c (ffffffff816e5ce1)
Location: include/asm-generic/bitops/le.h:12
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
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
In fs/ext4/balloc.c (ffffffff81383ce8)
Location: include/asm-generic/bitops/le.h:12
Inline: True
```
```
In fs/ext4/ialloc.c (ffffffff81396491)
Location: include/asm-generic/bitops/le.h:12
Inline: True
```
```
In fs/ext4/mballoc.c (ffffffff813b6468)
Location: include/asm-generic/bitops/le.h:12
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
  - fs/ext4/mballoc.c:ext4_mb_simple_scan_group
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In drivers/nvdimm/label.c (ffffffff81751031)
Location: include/asm-generic/bitops/le.h:12
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
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
In fs/ext4/balloc.c (ffffffff81397811)
Location: include/asm-generic/bitops/le.h:12
Inline: True
```
```
In fs/ext4/ialloc.c (ffffffff813aa6f1)
Location: include/asm-generic/bitops/le.h:12
Inline: True
```
```
In fs/ext4/mballoc.c (ffffffff813cb188)
Location: include/asm-generic/bitops/le.h:12
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
  - fs/ext4/mballoc.c:ext4_mb_simple_scan_group
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In drivers/nvdimm/label.c (ffffffff8176c4b1)
Location: include/asm-generic/bitops/le.h:12
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
```
</details>
</li>
</ul>

## Differences
