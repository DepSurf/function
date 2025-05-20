# Function: <code>buffer_unwritten</code>

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
In fs/buffer.c (ffffffff81244a22)
Location: include/linux/buffer_head.h:129
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/buffer.c:__block_write_begin
  - fs/buffer.c:block_truncate_page
```
```
In fs/dax.c (ffffffff8125dd9e)
Location: include/linux/buffer_head.h:129
Inline: True
Inline callers:
  - fs/dax.c:__dax_fault
  - fs/dax.c:__dax_fault
  - fs/dax.c:__dax_fault
  - fs/dax.c:__dax_fault
  - fs/dax.c:dax_do_io
  - fs/dax.c:dax_do_io
  - fs/dax.c:dax_zero_page_range
```
```
In fs/ext4/file.c (ffffffff81291bd4)
Location: include/linux/buffer_head.h:129
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_end_io_unwritten
```
```
In fs/ext4/inode.c (ffffffff81295c91)
Location: include/linux/buffer_head.h:129
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_bh_delay_or_unwritten
  - fs/ext4/inode.c:mpage_process_page_bufs
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:_ext4_get_block
  - fs/ext4/inode.c:ext4_da_write_end
```
```
In fs/ext4/page-io.c (ffffffff8129fee1)
Location: include/linux/buffer_head.h:129
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
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
In fs/buffer.c (ffffffff8126cf66)
Location: include/linux/buffer_head.h:129
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:__block_write_begin_int
```
```
In fs/dax.c (ffffffff81286a91)
Location: include/linux/buffer_head.h:129
Inline: True
Inline callers:
  - fs/dax.c:dax_zero_page_range
  - fs/dax.c:dax_fault
  - fs/dax.c:dax_fault
  - fs/dax.c:dax_do_io
  - fs/dax.c:dax_do_io
```
```
In fs/ext4/file.c (ffffffff812bface)
Location: include/linux/buffer_head.h:129
Inline: True
```
```
In fs/ext4/inode.c (ffffffff812cc688)
Location: include/linux/buffer_head.h:129
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:mpage_process_page_bufs
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_dio_get_block_unwritten_async
```
```
In fs/ext4/page-io.c (ffffffff812ce7dd)
Location: include/linux/buffer_head.h:129
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
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
In fs/buffer.c (ffffffff812801f6)
Location: include/linux/buffer_head.h:129
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:__block_write_begin_int
```
```
In fs/ext4/file.c (ffffffff812d4cde)
Location: include/linux/buffer_head.h:129
Inline: True
```
```
In fs/ext4/inode.c (ffffffff812e2498)
Location: include/linux/buffer_head.h:129
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:mpage_process_page_bufs
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_dio_get_block_unwritten_async
```
```
In fs/ext4/page-io.c (ffffffff812e45bd)
Location: include/linux/buffer_head.h:129
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
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
In fs/buffer.c (ffffffff812904ae)
Location: include/linux/buffer_head.h:129
Inline: True
Inline callers:
  - fs/buffer.c:page_cache_seek_hole_data
  - fs/buffer.c:submit_bh_wbc
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:__block_write_begin_int
```
```
In fs/ext4/file.c (ffffffff812f15d5)
Location: include/linux/buffer_head.h:129
Inline: True
```
```
In fs/ext4/inode.c (ffffffff81306601)
Location: include/linux/buffer_head.h:129
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:mpage_process_page_bufs
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_dio_get_block_unwritten_async
```
```
In fs/ext4/page-io.c (ffffffff8131e27a)
Location: include/linux/buffer_head.h:129
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
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
In fs/buffer.c (ffffffff812b314d)
Location: include/linux/buffer_head.h:130
Inline: True
Inline callers:
  - fs/buffer.c:page_cache_seek_hole_data
  - fs/buffer.c:submit_bh_wbc
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:__block_write_begin_int
```
```
In fs/ext4/inode.c (ffffffff8132b1d1)
Location: include/linux/buffer_head.h:130
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:mpage_process_page_bufs
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_dio_get_block_overwrite
  - fs/ext4/inode.c:ext4_dio_get_block_unwritten_async
```
```
In fs/ext4/page-io.c (ffffffff8134289a)
Location: include/linux/buffer_head.h:130
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
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
In fs/buffer.c (ffffffff812d8486)
Location: include/linux/buffer_head.h:133
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:__block_write_begin_int
```
```
In fs/ext4/inode.c (ffffffff8135987f)
Location: include/linux/buffer_head.h:133
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:mpage_process_page_bufs
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_dio_get_block_overwrite
  - fs/ext4/inode.c:ext4_dio_get_block_unwritten_async
```
```
In fs/ext4/page-io.c (ffffffff8137071a)
Location: include/linux/buffer_head.h:133
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
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
In fs/buffer.c (ffffffff812ed959)
Location: include/linux/buffer_head.h:133
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:__block_write_begin_int
```
```
In fs/ext4/inode.c (ffffffff81371bb5)
Location: include/linux/buffer_head.h:133
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:mpage_process_page_bufs
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_dio_get_block_overwrite
  - fs/ext4/inode.c:ext4_dio_get_block_unwritten_async
```
```
In fs/ext4/page-io.c (ffffffff81388ba8)
Location: include/linux/buffer_head.h:133
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
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
In fs/buffer.c (ffffffff8130f129)
Location: include/linux/buffer_head.h:133
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:__block_write_begin_int
```
```
In fs/ext4/inode.c (ffffffff8139b13b)
Location: include/linux/buffer_head.h:133
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:mpage_process_page_bufs
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_dio_get_block_unwritten_async
```
```
In fs/ext4/page-io.c (ffffffff813b2c98)
Location: include/linux/buffer_head.h:133
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
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
In fs/buffer.c (ffffffff81322089)
Location: include/linux/buffer_head.h:133
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:__block_write_begin_int
```
```
In fs/ext4/inode.c (ffffffff813b3bfb)
Location: include/linux/buffer_head.h:133
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:mpage_process_page_bufs
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_dio_get_block_unwritten_async
```
```
In fs/ext4/page-io.c (ffffffff813cbd06)
Location: include/linux/buffer_head.h:133
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
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
In fs/buffer.c (ffffffff813596b9)
Location: include/linux/buffer_head.h:133
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:__block_write_begin_int
```
```
In fs/ext4/inode.c (ffffffff813feeb1)
Location: include/linux/buffer_head.h:133
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:mpage_add_bh_to_extent
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/page-io.c (ffffffff81417e53)
Location: include/linux/buffer_head.h:133
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
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
In fs/buffer.c (ffffffff81367439)
Location: include/linux/buffer_head.h:133
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:__block_write_begin_int
```
```
In fs/ext4/inode.c (ffffffff814080db)
Location: include/linux/buffer_head.h:133
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_should_update_i_disksize
  - fs/ext4/inode.c:mpage_add_bh_to_extent
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/page-io.c (ffffffff8142b958)
Location: include/linux/buffer_head.h:133
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
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
In fs/buffer.c (ffffffff8136de79)
Location: include/linux/buffer_head.h:133
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:__block_write_begin_int
```
```
In fs/ext4/inode.c (ffffffff81417a5d)
Location: include/linux/buffer_head.h:133
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:mpage_process_page_bufs
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/page-io.c (ffffffff81432577)
Location: include/linux/buffer_head.h:133
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
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
In fs/buffer.c (ffffffff813bcb79)
Location: include/linux/buffer_head.h:133
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:__block_write_begin_int
```
```
In fs/ext4/inode.c (ffffffff8146ad36)
Location: include/linux/buffer_head.h:133
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:mpage_process_page_bufs
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/page-io.c (ffffffff81485e37)
Location: include/linux/buffer_head.h:133
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
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
In fs/buffer.c (ffffffff81442f80)
Location: include/linux/buffer_head.h:132
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:__block_write_begin_int
```
```
In fs/ext4/inode.c (ffffffff814eadcc)
Location: include/linux/buffer_head.h:132
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:mpage_process_page_bufs
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/page-io.c (ffffffff8150941b)
Location: include/linux/buffer_head.h:132
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
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
In fs/buffer.c (ffffffff814d2243)
Location: include/linux/buffer_head.h:133
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:__block_write_begin_int
```
```
In fs/ext4/inode.c (ffffffff81584929)
Location: include/linux/buffer_head.h:133
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:mpage_process_page_bufs
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_bh_delay_or_unwritten
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/page-io.c (ffffffff815a3fd9)
Location: include/linux/buffer_head.h:133
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
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
In fs/buffer.c (ffffffff81508b0e)
Location: include/linux/buffer_head.h:136
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:__block_write_begin_int
```
```
In fs/ext4/inode.c (ffffffff815bb2ee)
Location: include/linux/buffer_head.h:136
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:mpage_process_page_bufs
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/page-io.c (ffffffff815daa30)
Location: include/linux/buffer_head.h:136
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_folio
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
In fs/buffer.c (ffffffff8153d972)
Location: include/linux/buffer_head.h:134
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:__block_write_begin_int
```
```
In fs/ext4/inode.c (ffffffff815f4033)
Location: include/linux/buffer_head.h:134
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:mpage_process_page_bufs
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/page-io.c (ffffffff8161323d)
Location: include/linux/buffer_head.h:134
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_folio
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
In fs/buffer.c (ffff8000103dadd4)
Location: include/linux/buffer_head.h:133
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:__block_write_begin_int
```
```
In fs/ext4/inode.c (ffff800010488498)
Location: include/linux/buffer_head.h:133
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:mpage_process_page_bufs
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_dio_get_block_unwritten_async
```
```
In fs/ext4/page-io.c (ffff8000104a3ea8)
Location: include/linux/buffer_head.h:133
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
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
In fs/buffer.c (c05b4190)
Location: include/linux/buffer_head.h:133
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:__block_write_begin_int
```
```
In fs/ext4/inode.c (c064a668)
Location: include/linux/buffer_head.h:133
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:mpage_process_page_bufs
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_dio_get_block_unwritten_async
```
```
In fs/ext4/page-io.c (c0665d30)
Location: include/linux/buffer_head.h:133
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
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
In fs/buffer.c (c0000000004e0034)
Location: include/linux/buffer_head.h:133
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:__block_write_begin_int
```
```
In fs/ext4/inode.c (c0000000005aed80)
Location: include/linux/buffer_head.h:133
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:mpage_process_page_bufs
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_dio_get_block_unwritten_async
```
```
In fs/ext4/page-io.c (c0000000005d0fb4)
Location: include/linux/buffer_head.h:133
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
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
In fs/buffer.c (ffffffe0002937fc)
Location: include/linux/buffer_head.h:133
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:__block_write_begin_int
```
```
In fs/ext4/inode.c (ffffffe00030fedc)
Location: include/linux/buffer_head.h:133
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:mpage_process_page_bufs
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_dio_get_block_unwritten_async
```
```
In fs/ext4/page-io.c (ffffffe0003253fc)
Location: include/linux/buffer_head.h:133
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
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
In fs/buffer.c (ffffffff8131a669)
Location: include/linux/buffer_head.h:133
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:__block_write_begin_int
```
```
In fs/ext4/inode.c (ffffffff813ac1db)
Location: include/linux/buffer_head.h:133
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:mpage_process_page_bufs
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_dio_get_block_unwritten_async
```
```
In fs/ext4/page-io.c (ffffffff813c42e6)
Location: include/linux/buffer_head.h:133
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
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
In fs/buffer.c (ffffffff8130b209)
Location: include/linux/buffer_head.h:133
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:__block_write_begin_int
```
```
In fs/ext4/inode.c (ffffffff8139cc6b)
Location: include/linux/buffer_head.h:133
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:mpage_process_page_bufs
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_dio_get_block_unwritten_async
```
```
In fs/ext4/page-io.c (ffffffff813b4d66)
Location: include/linux/buffer_head.h:133
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
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
In fs/buffer.c (ffffffff81318139)
Location: include/linux/buffer_head.h:133
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:__block_write_begin_int
```
```
In fs/ext4/inode.c (ffffffff813a9a3b)
Location: include/linux/buffer_head.h:133
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:mpage_process_page_bufs
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_dio_get_block_unwritten_async
```
```
In fs/ext4/page-io.c (ffffffff813c1776)
Location: include/linux/buffer_head.h:133
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
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
In fs/buffer.c (ffffffff81329d59)
Location: include/linux/buffer_head.h:133
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:__block_write_begin_int
```
```
In fs/ext4/inode.c (ffffffff813be344)
Location: include/linux/buffer_head.h:133
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:mpage_process_page_bufs
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_dio_get_block_unwritten_async
```
```
In fs/ext4/page-io.c (ffffffff813d68d6)
Location: include/linux/buffer_head.h:133
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
</details>
</li>
</ul>

## Differences
