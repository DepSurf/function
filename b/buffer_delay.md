# Function: <code>buffer_delay</code>

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
In fs/buffer.c (ffffffff81244a16)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/buffer.c:__block_write_begin
  - fs/buffer.c:block_truncate_page
```
```
In fs/ext4/inode.c (ffffffff81295c85)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_bh_delay_or_unwritten
  - fs/ext4/inode.c:mpage_process_page_bufs
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_da_write_end
```
```
In fs/ext4/page-io.c (ffffffff8129fec8)
Location: include/linux/buffer_head.h:126
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
In fs/buffer.c (ffffffff8126cf5a)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
```
```
In fs/ext4/inode.c (ffffffff812cc67c)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_process_page_bufs
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/page-io.c (ffffffff812ce7c4)
Location: include/linux/buffer_head.h:126
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
In fs/buffer.c (ffffffff812801ea)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
```
```
In fs/ext4/inode.c (ffffffff812e248c)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_process_page_bufs
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/page-io.c (ffffffff812e45a4)
Location: include/linux/buffer_head.h:126
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
In fs/buffer.c (ffffffff8128daca)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
```
```
In fs/ext4/inode.c (ffffffff813065f9)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_process_page_bufs
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/page-io.c (ffffffff8131e261)
Location: include/linux/buffer_head.h:126
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
In fs/buffer.c (ffffffff812b068a)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
```
```
In fs/ext4/inode.c (ffffffff8132b1c9)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_process_page_bufs
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/page-io.c (ffffffff81342881)
Location: include/linux/buffer_head.h:127
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
In fs/buffer.c (ffffffff812d847a)
Location: include/linux/buffer_head.h:130
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
```
```
In fs/ext4/inode.c (ffffffff81359873)
Location: include/linux/buffer_head.h:130
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_process_page_bufs
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/page-io.c (ffffffff81370701)
Location: include/linux/buffer_head.h:130
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
In fs/buffer.c (ffffffff812ed94d)
Location: include/linux/buffer_head.h:130
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
```
```
In fs/ext4/inode.c (ffffffff81371ba9)
Location: include/linux/buffer_head.h:130
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_process_page_bufs
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/page-io.c (ffffffff81388b91)
Location: include/linux/buffer_head.h:130
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
In fs/buffer.c (ffffffff8130f11d)
Location: include/linux/buffer_head.h:130
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
```
```
In fs/ext4/inode.c (ffffffff8139b12f)
Location: include/linux/buffer_head.h:130
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_process_page_bufs
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/page-io.c (ffffffff813b2c81)
Location: include/linux/buffer_head.h:130
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
In fs/buffer.c (ffffffff8132207d)
Location: include/linux/buffer_head.h:130
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
```
```
In fs/ext4/inode.c (ffffffff813b3bef)
Location: include/linux/buffer_head.h:130
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_process_page_bufs
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/page-io.c (ffffffff813cbcef)
Location: include/linux/buffer_head.h:130
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
In fs/buffer.c (ffffffff813596ad)
Location: include/linux/buffer_head.h:130
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
```
```
In fs/ext4/inode.c (ffffffff813feea5)
Location: include/linux/buffer_head.h:130
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:mpage_process_page
  - fs/ext4/inode.c:mpage_add_bh_to_extent
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/page-io.c (ffffffff81417e44)
Location: include/linux/buffer_head.h:130
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
In fs/buffer.c (ffffffff8136742d)
Location: include/linux/buffer_head.h:130
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
```
```
In fs/ext4/inode.c (ffffffff814080d3)
Location: include/linux/buffer_head.h:130
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_should_update_i_disksize
  - fs/ext4/inode.c:mpage_process_page
  - fs/ext4/inode.c:mpage_add_bh_to_extent
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/page-io.c (ffffffff8142b949)
Location: include/linux/buffer_head.h:130
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
In fs/buffer.c (ffffffff8136de6d)
Location: include/linux/buffer_head.h:130
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
```
```
In fs/ext4/inode.c (ffffffff81417a51)
Location: include/linux/buffer_head.h:130
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_process_page_bufs
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/page-io.c (ffffffff81432568)
Location: include/linux/buffer_head.h:130
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
In fs/buffer.c (ffffffff813bcb6d)
Location: include/linux/buffer_head.h:130
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
```
```
In fs/ext4/inode.c (ffffffff8146ad2a)
Location: include/linux/buffer_head.h:130
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:mpage_process_page
  - fs/ext4/inode.c:mpage_process_page_bufs
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/page-io.c (ffffffff81485e28)
Location: include/linux/buffer_head.h:130
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
In fs/buffer.c (ffffffff81442f74)
Location: include/linux/buffer_head.h:129
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
```
```
In fs/ext4/inode.c (ffffffff814eadc0)
Location: include/linux/buffer_head.h:129
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:mpage_process_page
  - fs/ext4/inode.c:mpage_process_page_bufs
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/page-io.c (ffffffff81509404)
Location: include/linux/buffer_head.h:129
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
In fs/buffer.c (ffffffff814d2237)
Location: include/linux/buffer_head.h:130
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
```
```
In fs/ext4/inode.c (ffffffff8158491d)
Location: include/linux/buffer_head.h:130
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_process_page
  - fs/ext4/inode.c:mpage_process_page_bufs
  - fs/ext4/inode.c:ext4_bh_delay_or_unwritten
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/page-io.c (ffffffff815a3fc2)
Location: include/linux/buffer_head.h:130
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
In fs/buffer.c (ffffffff81508b02)
Location: include/linux/buffer_head.h:133
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_folio
  - fs/buffer.c:__block_write_full_folio
```
```
In fs/ext4/inode.c (ffffffff815bb2e2)
Location: include/linux/buffer_head.h:133
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:mpage_process_folio
  - fs/ext4/inode.c:mpage_process_page_bufs
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/page-io.c (ffffffff815daa21)
Location: include/linux/buffer_head.h:133
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
In fs/buffer.c (ffffffff8153d966)
Location: include/linux/buffer_head.h:131
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_folio
  - fs/buffer.c:__block_write_full_folio
```
```
In fs/ext4/inode.c (ffffffff815f4027)
Location: include/linux/buffer_head.h:131
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:mpage_process_folio
  - fs/ext4/inode.c:mpage_process_page_bufs
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/page-io.c (ffffffff8161322a)
Location: include/linux/buffer_head.h:131
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
In fs/buffer.c (ffff8000103dadcc)
Location: include/linux/buffer_head.h:130
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
```
```
In fs/ext4/inode.c (ffff80001048848c)
Location: include/linux/buffer_head.h:130
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_process_page_bufs
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/page-io.c (ffff8000104a3e98)
Location: include/linux/buffer_head.h:130
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
In fs/buffer.c (c05b4184)
Location: include/linux/buffer_head.h:130
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
```
```
In fs/ext4/inode.c (c064a65c)
Location: include/linux/buffer_head.h:130
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_process_page_bufs
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/page-io.c (c0665d18)
Location: include/linux/buffer_head.h:130
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
In fs/buffer.c (c0000000004e0028)
Location: include/linux/buffer_head.h:130
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
```
```
In fs/ext4/inode.c (c0000000005aed74)
Location: include/linux/buffer_head.h:130
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_process_page_bufs
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/page-io.c (c0000000005d0f9c)
Location: include/linux/buffer_head.h:130
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
In fs/buffer.c (ffffffe0002937f2)
Location: include/linux/buffer_head.h:130
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
```
```
In fs/ext4/inode.c (ffffffe00030fed2)
Location: include/linux/buffer_head.h:130
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_process_page_bufs
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/page-io.c (ffffffe0003253e4)
Location: include/linux/buffer_head.h:130
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
In fs/buffer.c (ffffffff8131a65d)
Location: include/linux/buffer_head.h:130
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
```
```
In fs/ext4/inode.c (ffffffff813ac1cf)
Location: include/linux/buffer_head.h:130
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_process_page_bufs
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/page-io.c (ffffffff813c42cf)
Location: include/linux/buffer_head.h:130
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
In fs/buffer.c (ffffffff8130b1fd)
Location: include/linux/buffer_head.h:130
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
```
```
In fs/ext4/inode.c (ffffffff8139cc5f)
Location: include/linux/buffer_head.h:130
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_process_page_bufs
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/page-io.c (ffffffff813b4d4f)
Location: include/linux/buffer_head.h:130
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
In fs/buffer.c (ffffffff8131812d)
Location: include/linux/buffer_head.h:130
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
```
```
In fs/ext4/inode.c (ffffffff813a9a2f)
Location: include/linux/buffer_head.h:130
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_process_page_bufs
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/page-io.c (ffffffff813c175f)
Location: include/linux/buffer_head.h:130
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
In fs/buffer.c (ffffffff81329d4d)
Location: include/linux/buffer_head.h:130
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
```
```
In fs/ext4/inode.c (ffffffff813be338)
Location: include/linux/buffer_head.h:130
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_process_page_bufs
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/page-io.c (ffffffff813d68bf)
Location: include/linux/buffer_head.h:130
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
</details>
</li>
</ul>

## Differences
