# Function: <code>__set_bit_le</code>

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
In fs/ext4/balloc.c (ffffffff8128feb4)
Location: include/asm-generic/bitops/le.h:67
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ialloc.c (ffffffff81292ff7)
Location: include/asm-generic/bitops/le.h:67
Inline: True
```
```
In fs/ext4/super.c (ffffffff812bb79a)
Location: include/asm-generic/bitops/le.h:67
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
```
```
In fs/ext4/mballoc.c (ffffffff812cebb7)
Location: include/asm-generic/bitops/le.h:67
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_set_bits
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_mark_used
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
In fs/ext4/balloc.c (ffffffff812bd3f6)
Location: include/asm-generic/bitops/le.h:67
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ialloc.c (ffffffff812c05a7)
Location: include/asm-generic/bitops/le.h:67
Inline: True
```
```
In fs/ext4/super.c (ffffffff812ea745)
Location: include/asm-generic/bitops/le.h:67
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
```
```
In fs/ext4/mballoc.c (ffffffff813010d7)
Location: include/asm-generic/bitops/le.h:67
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:ext4_set_bits
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
In fs/ext4/balloc.c (ffffffff812d2a46)
Location: include/asm-generic/bitops/le.h:67
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ialloc.c (ffffffff812d5bd7)
Location: include/asm-generic/bitops/le.h:67
Inline: True
```
```
In fs/ext4/super.c (ffffffff813004f4)
Location: include/asm-generic/bitops/le.h:67
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
```
```
In fs/ext4/mballoc.c (ffffffff8131714c)
Location: include/asm-generic/bitops/le.h:67
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:ext4_set_bits
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
In fs/ext4/balloc.c (ffffffff812e405a)
Location: include/asm-generic/bitops/le.h:67
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ialloc.c (ffffffff812f3e57)
Location: include/asm-generic/bitops/le.h:67
Inline: True
```
```
In fs/ext4/mballoc.c (ffffffff8130e198)
Location: include/asm-generic/bitops/le.h:67
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:ext4_set_bits
```
```
In fs/ext4/super.c (ffffffff81335315)
Location: include/asm-generic/bitops/le.h:67
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
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
In fs/ext4/balloc.c (ffffffff813089ea)
Location: include/asm-generic/bitops/le.h:68
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ialloc.c (ffffffff8131a196)
Location: include/asm-generic/bitops/le.h:68
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/mballoc.c (ffffffff813332a8)
Location: include/asm-generic/bitops/le.h:68
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:ext4_set_bits
```
```
In fs/ext4/super.c (ffffffff81359825)
Location: include/asm-generic/bitops/le.h:68
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
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
In fs/ext4/balloc.c (ffffffff81336979)
Location: include/asm-generic/bitops/le.h:68
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ialloc.c (ffffffff81347da0)
Location: include/asm-generic/bitops/le.h:68
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/mballoc.c (ffffffff81361441)
Location: include/asm-generic/bitops/le.h:68
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:ext4_set_bits
```
```
In fs/ext4/super.c (ffffffff813881a1)
Location: include/asm-generic/bitops/le.h:68
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
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
In fs/ext4/balloc.c (ffffffff8134dbf9)
Location: include/asm-generic/bitops/le.h:68
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ialloc.c (ffffffff8135ff50)
Location: include/asm-generic/bitops/le.h:68
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/mballoc.c (ffffffff813796f1)
Location: include/asm-generic/bitops/le.h:68
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:ext4_set_bits
```
```
In fs/ext4/super.c (ffffffff813a0d71)
Location: include/asm-generic/bitops/le.h:68
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
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
In fs/ext4/balloc.c (ffffffff813765d6)
Location: include/asm-generic/bitops/le.h:68
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ialloc.c (ffffffff813890c1)
Location: include/asm-generic/bitops/le.h:68
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/mballoc.c (ffffffff813a320b)
Location: include/asm-generic/bitops/le.h:68
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:ext4_set_bits
```
```
In fs/ext4/super.c (ffffffff813cb62a)
Location: include/asm-generic/bitops/le.h:68
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
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
In fs/ext4/balloc.c (ffffffff8138e846)
Location: include/asm-generic/bitops/le.h:68
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ialloc.c (ffffffff813a1a47)
Location: include/asm-generic/bitops/le.h:68
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/mballoc.c (ffffffff813bc06b)
Location: include/asm-generic/bitops/le.h:68
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:ext4_set_bits
```
```
In fs/ext4/super.c (ffffffff813e49ea)
Location: include/asm-generic/bitops/le.h:68
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
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
In fs/ext4/balloc.c (ffffffff813d9c1d)
Location: include/asm-generic/bitops/le.h:68
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_init_block_bitmap
  - fs/ext4/balloc.c:ext4_init_block_bitmap
  - fs/ext4/balloc.c:ext4_init_block_bitmap
  - fs/ext4/balloc.c:ext4_init_block_bitmap
```
```
In fs/ext4/ialloc.c (ffffffff813edca2)
Location: include/asm-generic/bitops/le.h:68
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/mballoc.c (ffffffff81407c9f)
Location: include/asm-generic/bitops/le.h:68
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_buddy_mark_free
  - fs/ext4/mballoc.c:mb_buddy_mark_free
  - fs/ext4/mballoc.c:ext4_set_bits
```
```
In fs/ext4/super.c (ffffffff8142ce36)
Location: include/asm-generic/bitops/le.h:68
Inline: True
Inline callers:
  - fs/ext4/super.c:count_overhead
  - fs/ext4/super.c:count_overhead
  - fs/ext4/super.c:count_overhead
  - fs/ext4/super.c:count_overhead
  - fs/ext4/super.c:count_overhead
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
In fs/ext4/balloc.c (ffffffff813eb8cd)
Location: include/asm-generic/bitops/le.h:68
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_init_block_bitmap
  - fs/ext4/balloc.c:ext4_init_block_bitmap
  - fs/ext4/balloc.c:ext4_init_block_bitmap
  - fs/ext4/balloc.c:ext4_init_block_bitmap
```
```
In fs/ext4/ialloc.c (ffffffff814001f2)
Location: include/asm-generic/bitops/le.h:68
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_mark_inode_used
```
```
In fs/ext4/mballoc.c (ffffffff8141a6ef)
Location: include/asm-generic/bitops/le.h:68
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_buddy_mark_free
  - fs/ext4/mballoc.c:mb_buddy_mark_free
  - fs/ext4/mballoc.c:ext4_set_bits
```
```
In fs/ext4/super.c (ffffffff81445c36)
Location: include/asm-generic/bitops/le.h:68
Inline: True
Inline callers:
  - fs/ext4/super.c:count_overhead
  - fs/ext4/super.c:count_overhead
  - fs/ext4/super.c:count_overhead
  - fs/ext4/super.c:count_overhead
  - fs/ext4/super.c:count_overhead
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
In fs/ext4/balloc.c (ffffffff813f1e0d)
Location: include/asm-generic/bitops/le.h:98
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_init_block_bitmap
  - fs/ext4/balloc.c:ext4_init_block_bitmap
  - fs/ext4/balloc.c:ext4_init_block_bitmap
  - fs/ext4/balloc.c:ext4_init_block_bitmap
```
```
In fs/ext4/ialloc.c (ffffffff8140668d)
Location: include/asm-generic/bitops/le.h:98
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_mark_inode_used
```
```
In fs/ext4/mballoc.c (ffffffff81420b9e)
Location: include/asm-generic/bitops/le.h:98
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_buddy_mark_free
  - fs/ext4/mballoc.c:mb_buddy_mark_free
  - fs/ext4/mballoc.c:ext4_set_bits
```
```
In fs/ext4/super.c (ffffffff8144b500)
Location: include/asm-generic/bitops/le.h:98
Inline: True
Inline callers:
  - fs/ext4/super.c:count_overhead
  - fs/ext4/super.c:count_overhead
  - fs/ext4/super.c:count_overhead
  - fs/ext4/super.c:count_overhead
  - fs/ext4/super.c:count_overhead
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
In fs/ext4/balloc.c (ffffffff81443e41)
Location: include/asm-generic/bitops/le.h:98
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_init_block_bitmap
  - fs/ext4/balloc.c:ext4_init_block_bitmap
  - fs/ext4/balloc.c:ext4_init_block_bitmap
  - fs/ext4/balloc.c:ext4_init_block_bitmap
```
```
In fs/ext4/ialloc.c (ffffffff81458f02)
Location: include/asm-generic/bitops/le.h:98
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_mark_inode_used
```
```
In fs/ext4/mballoc.c (ffffffff81473fa5)
Location: include/asm-generic/bitops/le.h:98
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_buddy_mark_free
  - fs/ext4/mballoc.c:mb_buddy_mark_free
  - fs/ext4/mballoc.c:ext4_set_bits
```
```
In fs/ext4/super.c (ffffffff8149f469)
Location: include/asm-generic/bitops/le.h:98
Inline: True
Inline callers:
  - fs/ext4/super.c:count_overhead
  - fs/ext4/super.c:count_overhead
  - fs/ext4/super.c:count_overhead
  - fs/ext4/super.c:count_overhead
  - fs/ext4/super.c:count_overhead
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
In fs/ext4/balloc.c (ffffffff814bfd1d)
Location: include/asm-generic/bitops/le.h:34
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_init_block_bitmap
  - fs/ext4/balloc.c:ext4_init_block_bitmap
  - fs/ext4/balloc.c:ext4_init_block_bitmap
  - fs/ext4/balloc.c:ext4_init_block_bitmap
```
```
In fs/ext4/ialloc.c (ffffffff814d70e7)
Location: include/asm-generic/bitops/le.h:34
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/mballoc.c (ffffffff814f6018)
Location: include/asm-generic/bitops/le.h:34
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_buddy_mark_free
  - fs/ext4/mballoc.c:mb_buddy_mark_free
  - fs/ext4/mballoc.c:mb_set_bits
```
```
In fs/ext4/super.c (ffffffff81525d09)
Location: include/asm-generic/bitops/le.h:34
Inline: True
Inline callers:
  - fs/ext4/super.c:count_overhead
  - fs/ext4/super.c:count_overhead
  - fs/ext4/super.c:count_overhead
  - fs/ext4/super.c:count_overhead
  - fs/ext4/super.c:count_overhead
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
In fs/ext4/balloc.c (ffffffff81557cfd)
Location: include/asm-generic/bitops/le.h:34
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_init_block_bitmap
  - fs/ext4/balloc.c:ext4_init_block_bitmap
  - fs/ext4/balloc.c:ext4_init_block_bitmap
  - fs/ext4/balloc.c:ext4_init_block_bitmap
```
```
In fs/ext4/ialloc.c (ffffffff8156fe6c)
Location: include/asm-generic/bitops/le.h:34
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_mark_inode_used
```
```
In fs/ext4/mballoc.c (ffffffff81590390)
Location: include/asm-generic/bitops/le.h:34
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_buddy_mark_free
  - fs/ext4/mballoc.c:mb_buddy_mark_free
  - fs/ext4/mballoc.c:mb_set_bits
```
```
In fs/ext4/super.c (ffffffff815c341b)
Location: include/asm-generic/bitops/le.h:34
Inline: True
Inline callers:
  - fs/ext4/super.c:count_overhead
  - fs/ext4/super.c:count_overhead
  - fs/ext4/super.c:count_overhead
  - fs/ext4/super.c:count_overhead
  - fs/ext4/super.c:count_overhead
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
In fs/ext4/balloc.c (ffffffff8158fa4d)
Location: include/asm-generic/bitops/le.h:34
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_init_block_bitmap
  - fs/ext4/balloc.c:ext4_init_block_bitmap
  - fs/ext4/balloc.c:ext4_init_block_bitmap
  - fs/ext4/balloc.c:ext4_init_block_bitmap
```
```
In fs/ext4/ialloc.c (ffffffff815a7cee)
Location: include/asm-generic/bitops/le.h:34
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_mark_inode_used
```
```
In fs/ext4/mballoc.c (ffffffff815c754b)
Location: include/asm-generic/bitops/le.h:34
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_buddy_mark_free
  - fs/ext4/mballoc.c:mb_buddy_mark_free
  - fs/ext4/mballoc.c:mb_set_bits
```
```
In fs/ext4/super.c (ffffffff815fab6b)
Location: include/asm-generic/bitops/le.h:34
Inline: True
Inline callers:
  - fs/ext4/super.c:count_overhead
  - fs/ext4/super.c:count_overhead
  - fs/ext4/super.c:count_overhead
  - fs/ext4/super.c:count_overhead
  - fs/ext4/super.c:count_overhead
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
In fs/ext4/balloc.c (ffffffff815c85cf)
Location: include/asm-generic/bitops/le.h:34
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_init_block_bitmap
  - fs/ext4/balloc.c:ext4_init_block_bitmap
  - fs/ext4/balloc.c:ext4_init_block_bitmap
  - fs/ext4/balloc.c:ext4_init_block_bitmap
```
```
In fs/ext4/ialloc.c (ffffffff815e0afe)
Location: include/asm-generic/bitops/le.h:34
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_mark_inode_used
```
```
In fs/ext4/mballoc.c (ffffffff815fdd3b)
Location: include/asm-generic/bitops/le.h:34
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_buddy_mark_free
  - fs/ext4/mballoc.c:mb_buddy_mark_free
  - fs/ext4/mballoc.c:mb_set_bits
```
```
In fs/ext4/super.c (ffffffff8163374b)
Location: include/asm-generic/bitops/le.h:34
Inline: True
Inline callers:
  - fs/ext4/super.c:count_overhead
  - fs/ext4/super.c:count_overhead
  - fs/ext4/super.c:count_overhead
  - fs/ext4/super.c:count_overhead
  - fs/ext4/super.c:count_overhead
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
In fs/ext4/balloc.c (ffff800010460bd0)
Location: include/asm-generic/bitops/le.h:68
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ialloc.c (ffff800010475220)
Location: include/asm-generic/bitops/le.h:68
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/mballoc.c (ffff800010492cac)
Location: include/asm-generic/bitops/le.h:68
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:ext4_set_bits
```
```
In fs/ext4/super.c (ffff8000104bdf6c)
Location: include/asm-generic/bitops/le.h:68
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
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
In fs/ext4/balloc.c (c0621298)
Location: include/asm-generic/bitops/le.h:68
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ialloc.c (c0636888)
Location: include/asm-generic/bitops/le.h:68
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/mballoc.c (c0653fe8)
Location: include/asm-generic/bitops/le.h:68
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:ext4_set_bits
```
```
In fs/ext4/super.c (c06817d8)
Location: include/asm-generic/bitops/le.h:68
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
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
In fs/ext4/balloc.c (c00000000057d150)
Location: include/asm-generic/bitops/le.h:68
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ialloc.c (c000000000596c20)
Location: include/asm-generic/bitops/le.h:68
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/mballoc.c (c0000000005bb3b4)
Location: include/asm-generic/bitops/le.h:68
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:ext4_set_bits
```
```
In fs/ext4/super.c (c0000000005f4344)
Location: include/asm-generic/bitops/le.h:68
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
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
In fs/ext4/balloc.c (ffffffe0002eff4e)
Location: include/asm-generic/bitops/le.h:68
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ialloc.c (ffffffe000300bf4)
Location: include/asm-generic/bitops/le.h:68
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/mballoc.c (ffffffe000317866)
Location: include/asm-generic/bitops/le.h:68
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:ext4_set_bits
```
```
In fs/ext4/super.c (ffffffe000339998)
Location: include/asm-generic/bitops/le.h:68
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
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
In fs/ext4/balloc.c (ffffffff81386e26)
Location: include/asm-generic/bitops/le.h:68
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ialloc.c (ffffffff8139a027)
Location: include/asm-generic/bitops/le.h:68
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/mballoc.c (ffffffff813b464b)
Location: include/asm-generic/bitops/le.h:68
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:ext4_set_bits
```
```
In fs/ext4/super.c (ffffffff813dcfca)
Location: include/asm-generic/bitops/le.h:68
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
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
In fs/ext4/balloc.c (ffffffff813778b6)
Location: include/asm-generic/bitops/le.h:68
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ialloc.c (ffffffff8138aab7)
Location: include/asm-generic/bitops/le.h:68
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/mballoc.c (ffffffff813a50db)
Location: include/asm-generic/bitops/le.h:68
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:ext4_set_bits
```
```
In fs/ext4/super.c (ffffffff813cda4a)
Location: include/asm-generic/bitops/le.h:68
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
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
In fs/ext4/balloc.c (ffffffff813848f6)
Location: include/asm-generic/bitops/le.h:68
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ialloc.c (ffffffff81397887)
Location: include/asm-generic/bitops/le.h:68
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/mballoc.c (ffffffff813b1eab)
Location: include/asm-generic/bitops/le.h:68
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:ext4_set_bits
```
```
In fs/ext4/super.c (ffffffff813da46a)
Location: include/asm-generic/bitops/le.h:68
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
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
In fs/ext4/balloc.c (ffffffff81398471)
Location: include/asm-generic/bitops/le.h:68
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ialloc.c (ffffffff813ac158)
Location: include/asm-generic/bitops/le.h:68
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/mballoc.c (ffffffff813c69eb)
Location: include/asm-generic/bitops/le.h:68
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:ext4_set_bits
```
```
In fs/ext4/super.c (ffffffff813ef74a)
Location: include/asm-generic/bitops/le.h:68
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
```
</details>
</li>
</ul>

## Differences
