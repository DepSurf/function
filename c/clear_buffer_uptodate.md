# Function: <code>clear_buffer_uptodate</code>

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
In fs/buffer.c (ffffffff8124265d)
Location: include/linux/buffer_head.h:116
Inline: True
Inline callers:
  - fs/buffer.c:__end_buffer_read_notouch
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_async_write
```
```
In fs/ext4/mmp.c (ffffffff812d7938)
Location: include/linux/buffer_head.h:116
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
```
```
In fs/jbd2/commit.c (ffffffff812e9898)
Location: include/linux/buffer_head.h:116
Inline: True
Inline callers:
  - fs/jbd2/commit.c:journal_end_buffer_io_sync
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
In fs/buffer.c (ffffffff8126bed9)
Location: include/linux/buffer_head.h:116
Inline: True
Inline callers:
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:__end_buffer_read_notouch
```
```
In fs/ext4/mmp.c (ffffffff8130769a)
Location: include/linux/buffer_head.h:116
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
```
```
In fs/jbd2/commit.c (ffffffff813173b8)
Location: include/linux/buffer_head.h:116
Inline: True
Inline callers:
  - fs/jbd2/commit.c:journal_end_buffer_io_sync
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
In fs/buffer.c (ffffffff8127f249)
Location: include/linux/buffer_head.h:116
Inline: True
Inline callers:
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:__end_buffer_read_notouch
```
```
In fs/ext4/mmp.c (ffffffff8131d68a)
Location: include/linux/buffer_head.h:116
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
```
```
In fs/jbd2/commit.c (ffffffff8132d3a8)
Location: include/linux/buffer_head.h:116
Inline: True
Inline callers:
  - fs/jbd2/commit.c:journal_end_buffer_io_sync
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
In fs/buffer.c (ffffffff8128cbe3)
Location: include/linux/buffer_head.h:116
Inline: True
Inline callers:
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:__end_buffer_read_notouch
```
```
In fs/ext4/mmp.c (ffffffff81314358)
Location: include/linux/buffer_head.h:116
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
```
```
In fs/jbd2/commit.c (ffffffff81342578)
Location: include/linux/buffer_head.h:116
Inline: True
Inline callers:
  - fs/jbd2/commit.c:journal_end_buffer_io_sync
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
In fs/buffer.c (ffffffff812af683)
Location: include/linux/buffer_head.h:117
Inline: True
Inline callers:
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:__end_buffer_read_notouch
```
```
In fs/ext4/mmp.c (ffffffff81338b18)
Location: include/linux/buffer_head.h:117
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
```
```
In fs/jbd2/commit.c (ffffffff81366ba8)
Location: include/linux/buffer_head.h:117
Inline: True
Inline callers:
  - fs/jbd2/commit.c:journal_end_buffer_io_sync
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
In fs/buffer.c (ffffffff812d6dd3)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:__end_buffer_read_notouch
```
```
In fs/ext4/mmp.c (ffffffff81367058)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
```
```
In fs/jbd2/commit.c (ffffffff81395451)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/jbd2/commit.c:journal_end_buffer_io_sync
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
In fs/buffer.c (ffffffff812ec553)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:__end_buffer_read_notouch
```
```
In fs/ext4/mmp.c (ffffffff8137f4d8)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
```
```
In fs/jbd2/commit.c (ffffffff813ae1c1)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/jbd2/commit.c:journal_end_buffer_io_sync
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
In fs/buffer.c (ffffffff8130dcc2)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:__end_buffer_read_notouch
```
```
In fs/ext4/inode.c (ffffffff81391c63)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/mmp.c (ffffffff813a8958)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
```
```
In fs/jbd2/commit.c (ffffffff813d8606)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/jbd2/commit.c:journal_end_buffer_io_sync
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
In fs/buffer.c (ffffffff81320ca6)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:__end_buffer_read_notouch
```
```
In fs/ext4/inode.c (ffffffff813aa5f7)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/mmp.c (ffffffff813c1868)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
```
```
In fs/jbd2/commit.c (ffffffff813f25f6)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/jbd2/commit.c:journal_end_buffer_io_sync
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
In fs/buffer.c (ffffffff8135a50a)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/buffer.c:end_buffer_read_nobh
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:end_buffer_read_sync
```
```
In fs/ext4/balloc.c (0)
Location: include/linux/buffer_head.h:120
Inline: True
```
```
In fs/ext4/ialloc.c (0)
Location: include/linux/buffer_head.h:120
Inline: True
```
```
In fs/ext4/inode.c (ffffffff813f9278)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/mmp.c (ffffffff8140dbc5)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
```
```
In fs/jbd2/commit.c (ffffffff8143fa90)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/jbd2/commit.c:journal_end_buffer_io_sync
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
In fs/buffer.c (ffffffff8136856a)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/buffer.c:end_buffer_read_nobh
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:end_buffer_read_sync
```
```
In fs/ext4/balloc.c (0)
Location: include/linux/buffer_head.h:120
Inline: True
```
```
In fs/ext4/ialloc.c (0)
Location: include/linux/buffer_head.h:120
Inline: True
```
```
In fs/ext4/inode.c (ffffffff8140ba7b)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/mmp.c (ffffffff81421037)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
```
```
In fs/ext4/fast_commit.c (ffffffff81454236)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_end_buffer_io_sync
```
```
In fs/jbd2/commit.c (ffffffff8145bb68)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/jbd2/commit.c:journal_end_buffer_io_sync
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
In fs/buffer.c (ffffffff8136f19a)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/buffer.c:end_buffer_read_nobh
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:end_buffer_read_sync
```
```
In fs/ext4/balloc.c (0)
Location: include/linux/buffer_head.h:120
Inline: True
```
```
In fs/ext4/ialloc.c (0)
Location: include/linux/buffer_head.h:120
Inline: True
```
```
In fs/ext4/inode.c (ffffffff81411c32)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/mmp.c (ffffffff814277e7)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
```
```
In fs/ext4/fast_commit.c (ffffffff81459b66)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_end_buffer_io_sync
```
```
In fs/jbd2/commit.c (ffffffff814614a8)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/jbd2/commit.c:journal_end_buffer_io_sync
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
In fs/buffer.c (ffffffff813bde3a)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/buffer.c:end_buffer_read_nobh
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:end_buffer_read_sync
```
```
In fs/ext4/balloc.c (0)
Location: include/linux/buffer_head.h:120
Inline: True
```
```
In fs/ext4/ialloc.c (0)
Location: include/linux/buffer_head.h:120
Inline: True
```
```
In fs/ext4/inode.c (ffffffff81464aee)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/mmp.c (ffffffff8147b438)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
```
```
In fs/ext4/fast_commit.c (ffffffff814adc56)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_end_buffer_io_sync
```
```
In fs/jbd2/commit.c (ffffffff814b6998)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/jbd2/commit.c:journal_end_buffer_io_sync
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
In fs/buffer.c (ffffffff81444199)
Location: include/linux/buffer_head.h:147
Inline: True
Inline callers:
  - fs/buffer.c:end_buffer_read_nobh
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:end_buffer_read_sync
```
```
In fs/ext4/balloc.c (0)
Location: include/linux/buffer_head.h:147
Inline: True
```
```
In fs/ext4/ialloc.c (0)
Location: include/linux/buffer_head.h:147
Inline: True
```
```
In fs/ext4/inode.c (ffffffff814e4188)
Location: include/linux/buffer_head.h:147
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/mmp.c (ffffffff814fd898)
Location: include/linux/buffer_head.h:147
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
```
```
In fs/ext4/fast_commit.c (ffffffff81535b40)
Location: include/linux/buffer_head.h:147
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_end_buffer_io_sync
```
```
In fs/jbd2/commit.c (ffffffff815402f3)
Location: include/linux/buffer_head.h:147
Inline: True
Inline callers:
  - fs/jbd2/commit.c:journal_end_buffer_io_sync
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
In fs/buffer.c (ffffffff814d43cb)
Location: include/linux/buffer_head.h:159
Inline: True
Inline callers:
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:end_buffer_read_sync
```
```
In fs/ext4/balloc.c (0)
Location: include/linux/buffer_head.h:159
Inline: True
```
```
In fs/ext4/ialloc.c (0)
Location: include/linux/buffer_head.h:159
Inline: True
```
```
In fs/ext4/inode.c (ffffffff8157d6a1)
Location: include/linux/buffer_head.h:159
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/mmp.c (ffffffff81598078)
Location: include/linux/buffer_head.h:159
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
```
```
In fs/ext4/fast_commit.c (ffffffff815d3fe9)
Location: include/linux/buffer_head.h:159
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_end_buffer_io_sync
```
```
In fs/jbd2/commit.c (ffffffff815dee5c)
Location: include/linux/buffer_head.h:159
Inline: True
Inline callers:
  - fs/jbd2/commit.c:journal_end_buffer_io_sync
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
In fs/buffer.c (ffffffff8150aafb)
Location: include/linux/buffer_head.h:162
Inline: True
Inline callers:
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:end_buffer_read_sync
```
```
In fs/ext4/balloc.c (0)
Location: include/linux/buffer_head.h:162
Inline: True
```
```
In fs/ext4/ialloc.c (0)
Location: include/linux/buffer_head.h:162
Inline: True
```
```
In fs/ext4/inode.c (ffffffff815b4923)
Location: include/linux/buffer_head.h:162
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/mmp.c (ffffffff815ceb28)
Location: include/linux/buffer_head.h:162
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
```
```
In fs/ext4/fast_commit.c (ffffffff8160bbc9)
Location: include/linux/buffer_head.h:162
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_end_buffer_io_sync
```
```
In fs/jbd2/commit.c (ffffffff816168bc)
Location: include/linux/buffer_head.h:162
Inline: True
Inline callers:
  - fs/jbd2/commit.c:journal_end_buffer_io_sync
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
In fs/buffer.c (ffffffff8153f96b)
Location: include/linux/buffer_head.h:160
Inline: True
Inline callers:
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:end_buffer_read_sync
```
```
In fs/ext4/balloc.c (0)
Location: include/linux/buffer_head.h:160
Inline: True
```
```
In fs/ext4/ialloc.c (0)
Location: include/linux/buffer_head.h:160
Inline: True
```
```
In fs/ext4/inode.c (ffffffff815ed763)
Location: include/linux/buffer_head.h:160
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/mmp.c (ffffffff816073a8)
Location: include/linux/buffer_head.h:160
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
```
```
In fs/ext4/fast_commit.c (ffffffff81644989)
Location: include/linux/buffer_head.h:160
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_end_buffer_io_sync
```
```
In fs/jbd2/commit.c (ffffffff8164f6dc)
Location: include/linux/buffer_head.h:160
Inline: True
Inline callers:
  - fs/jbd2/commit.c:journal_end_buffer_io_sync
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
In fs/buffer.c (ffff8000103da6e8)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:__end_buffer_read_notouch
```
```
In fs/ext4/inode.c (ffff80001047fad4)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/mmp.c (ffff800010499018)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
```
```
In fs/jbd2/commit.c (ffff8000104cdce0)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/jbd2/commit.c:journal_end_buffer_io_sync
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
In fs/buffer.c (c05b2dfc)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:__end_buffer_read_notouch
```
```
In fs/ext4/inode.c (c0640454)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/mmp.c (c065a96c)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
```
```
In fs/jbd2/commit.c (c06905cc)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/jbd2/commit.c:journal_end_buffer_io_sync
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
In fs/buffer.c (c0000000004de3a4)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:__end_buffer_read_notouch
```
```
In fs/ext4/inode.c (c0000000005a47b8)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/mmp.c (c0000000005c3150)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
```
```
In fs/jbd2/commit.c (c000000000606480)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/jbd2/commit.c:journal_end_buffer_io_sync
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
In fs/buffer.c (ffffffe00029206c)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:__end_buffer_read_notouch
```
```
In fs/ext4/inode.c (ffffffe00030825a)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/mmp.c (ffffffe00031cbb6)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
```
```
In fs/jbd2/commit.c (ffffffe00034564a)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/jbd2/commit.c:journal_end_buffer_io_sync
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
In fs/buffer.c (ffffffff81319286)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:__end_buffer_read_notouch
```
```
In fs/ext4/inode.c (ffffffff813a2bd7)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/mmp.c (ffffffff813b9e48)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
```
```
In fs/jbd2/commit.c (ffffffff813eabd6)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/jbd2/commit.c:journal_end_buffer_io_sync
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
In fs/buffer.c (ffffffff81309dd7)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:__end_buffer_read_notouch
```
```
In fs/ext4/inode.c (ffffffff81393667)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/mmp.c (ffffffff813aa8d8)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
```
```
In fs/jbd2/commit.c (ffffffff813db656)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/jbd2/commit.c:journal_end_buffer_io_sync
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
In fs/buffer.c (ffffffff81316d56)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:__end_buffer_read_notouch
```
```
In fs/ext4/inode.c (ffffffff813a0437)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/mmp.c (ffffffff813b76a8)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
```
```
In fs/jbd2/commit.c (ffffffff813e7f56)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/jbd2/commit.c:journal_end_buffer_io_sync
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
In fs/buffer.c (ffffffff81328da3)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:__end_buffer_read_notouch
```
```
In fs/ext4/inode.c (ffffffff813b445e)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/mmp.c (ffffffff813cc3b8)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
```
```
In fs/jbd2/commit.c (ffffffff813fd956)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/jbd2/commit.c:journal_end_buffer_io_sync
```
</details>
</li>
</ul>

## Differences
