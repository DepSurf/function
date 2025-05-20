# Function: <code>set_buffer_new</code>

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
In fs/ext4/balloc.c (ffffffff81290055)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/inode.c (ffffffff81297155)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_da_get_block_prep
```
```
In fs/fat/inode.c (ffffffff812fb681)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_get_block
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
In fs/buffer.c (ffffffff8126e116)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
```
```
In fs/ext4/balloc.c (ffffffff812bd56c)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/inode.c (ffffffff812c477e)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_da_get_block_prep
```
```
In fs/fat/inode.c (ffffffff813319c8)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_get_block
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
In fs/buffer.c (ffffffff8128136f)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
```
```
In fs/ext4/balloc.c (ffffffff812d2bbc)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/inode.c (ffffffff812d9e2e)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_da_get_block_prep
```
```
In fs/fat/inode.c (ffffffff81347768)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_get_block
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
In fs/buffer.c (ffffffff8128ec59)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
```
```
In fs/ext4/balloc.c (ffffffff812e4173)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/inode.c (ffffffff812fdad6)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_da_get_block_prep
```
```
In fs/fat/inode.c (ffffffff8135c193)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_get_block
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
In fs/buffer.c (ffffffff812b1839)
Location: include/linux/buffer_head.h:124
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
```
```
In fs/ext4/balloc.c (ffffffff81308b21)
Location: include/linux/buffer_head.h:124
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/inode.c (ffffffff813222b6)
Location: include/linux/buffer_head.h:124
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_da_get_block_prep
```
```
In fs/fat/inode.c (ffffffff81380e93)
Location: include/linux/buffer_head.h:124
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_get_block
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
In fs/buffer.c (ffffffff812d95c0)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
```
```
In fs/ext4/balloc.c (ffffffff81336b54)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/inode.c (ffffffff81351579)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_da_get_block_prep
```
```
In fs/fat/inode.c (ffffffff813af630)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_get_block
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
In fs/buffer.c (ffffffff812eea91)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
```
```
In fs/ext4/balloc.c (ffffffff8134ddd4)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/inode.c (ffffffff8136a3a5)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_da_get_block_prep
```
```
In fs/fat/inode.c (ffffffff813c8ad5)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_get_block
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
In fs/buffer.c (ffffffff81310299)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
```
```
In fs/ext4/balloc.c (ffffffff813767b5)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/inode.c (ffffffff81393a04)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
```
```
In fs/fat/inode.c (ffffffff813f3663)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_get_block
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
In fs/buffer.c (ffffffff81323269)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
```
```
In fs/ext4/balloc.c (ffffffff8138ea25)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/inode.c (ffffffff813ac3a4)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
```
```
In fs/fat/inode.c (ffffffff8140d543)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_get_block
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
In fs/buffer.c (ffffffff8135b96f)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/buffer.c:iomap_to_bh
  - fs/buffer.c:iomap_to_bh
  - fs/buffer.c:iomap_to_bh
  - fs/buffer.c:iomap_to_bh
```
```
In fs/ext4/balloc.c (ffffffff813da0b7)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/inode.c (ffffffff813f86d4)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
```
```
In fs/fat/inode.c (ffffffff8145b249)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/fat/inode.c:__fat_get_block
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
In fs/buffer.c (ffffffff81369f1f)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/buffer.c:iomap_to_bh
  - fs/buffer.c:iomap_to_bh
  - fs/buffer.c:iomap_to_bh
  - fs/buffer.c:iomap_to_bh
```
```
In fs/ext4/balloc.c (ffffffff813ebd7b)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/inode.c (ffffffff8140a374)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
```
```
In fs/fat/inode.c (ffffffff81477599)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/fat/inode.c:__fat_get_block
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
In fs/buffer.c (ffffffff8136f09f)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/buffer.c:iomap_to_bh
  - fs/buffer.c:iomap_to_bh
  - fs/buffer.c:iomap_to_bh
  - fs/buffer.c:iomap_to_bh
```
```
In fs/ext4/balloc.c (ffffffff813f22bb)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/inode.c (ffffffff81410544)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
```
```
In fs/fat/inode.c (ffffffff8147d00b)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/fat/inode.c:__fat_get_block
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
In fs/buffer.c (ffffffff813bdcf9)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/buffer.c:iomap_to_bh
  - fs/buffer.c:iomap_to_bh
  - fs/buffer.c:iomap_to_bh
  - fs/buffer.c:iomap_to_bh
```
```
In fs/ext4/balloc.c (ffffffff8144429b)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/inode.c (ffffffff81465bb4)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
```
```
In fs/fat/inode.c (ffffffff814d4728)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/fat/inode.c:__fat_get_block
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
In fs/buffer.c (ffffffff814429cc)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/buffer.c:iomap_to_bh
  - fs/buffer.c:iomap_to_bh
  - fs/buffer.c:iomap_to_bh
  - fs/buffer.c:iomap_to_bh
```
```
In fs/ext4/balloc.c (ffffffff814c0188)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/inode.c (ffffffff814e5560)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
```
```
In fs/fat/inode.c (ffffffff81561697)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/fat/inode.c:__fat_get_block
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
In fs/buffer.c (ffffffff814d19ca)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/buffer.c:iomap_to_bh
  - fs/buffer.c:iomap_to_bh
  - fs/buffer.c:iomap_to_bh
  - fs/buffer.c:iomap_to_bh
```
```
In fs/ext4/balloc.c (ffffffff815581a9)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/inode.c (ffffffff8157ec30)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
```
```
In fs/fat/inode.c (ffffffff81603d47)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/fat/inode.c:__fat_get_block
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
In fs/buffer.c (ffffffff815080da)
Location: include/linux/buffer_head.h:130
Inline: True
Inline callers:
  - fs/buffer.c:iomap_to_bh
  - fs/buffer.c:iomap_to_bh
  - fs/buffer.c:iomap_to_bh
  - fs/buffer.c:iomap_to_bh
```
```
In fs/ext4/balloc.c (ffffffff8158fecb)
Location: include/linux/buffer_head.h:130
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/inode.c (ffffffff815b29c0)
Location: include/linux/buffer_head.h:130
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
```
```
In fs/fat/inode.c (ffffffff8163bc67)
Location: include/linux/buffer_head.h:130
Inline: True
Inline callers:
  - fs/fat/inode.c:__fat_get_block
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
In fs/buffer.c (ffffffff8153ce3a)
Location: include/linux/buffer_head.h:128
Inline: True
Inline callers:
  - fs/buffer.c:iomap_to_bh
  - fs/buffer.c:iomap_to_bh
  - fs/buffer.c:iomap_to_bh
  - fs/buffer.c:iomap_to_bh
```
```
In fs/ext4/balloc.c (ffffffff815c8a5a)
Location: include/linux/buffer_head.h:128
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/inode.c (ffffffff815eb7c0)
Location: include/linux/buffer_head.h:128
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
```
```
In fs/fat/inode.c (ffffffff816751c7)
Location: include/linux/buffer_head.h:128
Inline: True
Inline callers:
  - fs/fat/inode.c:__fat_get_block
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
In fs/buffer.c (ffff8000103dc5cc)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
```
```
In fs/ext4/balloc.c (ffff800010460de8)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/inode.c (ffff8000104807b0)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
```
```
In fs/fat/inode.c (ffff8000104ee218)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_get_block
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
In fs/buffer.c (c05b5980)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
```
```
In fs/ext4/balloc.c (c0621618)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/inode.c (c063febc)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
```
```
In fs/fat/inode.c (c06abe50)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_get_block
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
In fs/buffer.c (c0000000004e19c8)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
```
```
In fs/ext4/balloc.c (c00000000057d418)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/inode.c (c0000000005a2910)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
```
```
In fs/fat/inode.c (c00000000062d0e8)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_get_block
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
In fs/buffer.c (ffffffe0002948fc)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
```
```
In fs/ext4/balloc.c (ffffffe0002f0166)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/inode.c (ffffffe000309898)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
```
```
In fs/fat/inode.c (ffffffe00035e620)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_get_block
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
In fs/buffer.c (ffffffff8131b849)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
```
```
In fs/ext4/balloc.c (ffffffff81387005)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/inode.c (ffffffff813a4984)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
```
```
In fs/fat/inode.c (ffffffff81405b23)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_get_block
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
In fs/buffer.c (ffffffff8130c3e9)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
```
```
In fs/ext4/balloc.c (ffffffff81377a95)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/inode.c (ffffffff81395414)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
```
```
In fs/fat/inode.c (ffffffff813f65a3)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_get_block
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
In fs/buffer.c (ffffffff81319319)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
```
```
In fs/ext4/balloc.c (ffffffff81384ad5)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/inode.c (ffffffff813a21e4)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
```
```
In fs/fat/inode.c (ffffffff81402ea3)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_get_block
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
In fs/buffer.c (ffffffff8132af57)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
```
```
In fs/ext4/balloc.c (ffffffff8139864e)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/inode.c (ffffffff813b5664)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
```
```
In fs/fat/inode.c (ffffffff81418b03)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_get_block
```
</details>
</li>
</ul>

## Differences
