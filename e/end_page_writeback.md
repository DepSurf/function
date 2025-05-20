# Function: <code>end_page_writeback</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void end_page_writeback(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8118d690)
Location: mm/filemap.c:823
Inline: True
Direct callers:
  - mm/page_io.c:end_swap_bio_write
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:swap_writepage
  - mm/migrate.c:migrate_page_copy
  - fs/buffer.c:end_buffer_async_write
  - fs/block_dev.c:bdev_write_page
  - fs/ext4/page-io.c:ext4_finish_bio
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepages_send
  - fs/fuse/file.c:fuse_writepages_fill
```
**Symbols:**

```
ffffffff8118d690-ffffffff8118d723: end_page_writeback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void end_page_writeback(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811a0290)
Location: mm/filemap.c:864
Inline: True
Direct callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:swap_writepage
  - mm/page_io.c:end_swap_bio_write
  - mm/migrate.c:migrate_page_copy
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:end_buffer_async_write
  - fs/block_dev.c:bdev_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_finish_bio
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_send
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_locked
```
**Symbols:**

```
ffffffff811a0290-ffffffff811a033f: end_page_writeback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void end_page_writeback(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811af410)
Location: mm/filemap.c:967
Inline: False
Direct callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:swap_writepage
  - mm/page_io.c:end_swap_bio_write
  - mm/migrate.c:migrate_page_copy
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:end_buffer_async_write
  - fs/block_dev.c:bdev_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_finish_bio
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_send
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_locked
```
**Symbols:**

```
ffffffff811af410-ffffffff811af474: end_page_writeback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void end_page_writeback(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811b6310)
Location: mm/filemap.c:1093
Inline: False
Direct callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:swap_writepage
  - mm/page_io.c:end_swap_bio_write
  - mm/migrate.c:migrate_page_copy
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:end_buffer_async_write
  - fs/block_dev.c:bdev_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_finish_bio
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_send
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_locked
```
**Symbols:**

```
ffffffff811b6310-ffffffff811b6374: end_page_writeback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void end_page_writeback(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811ca620)
Location: mm/filemap.c:1215
Inline: False
Direct callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:swap_writepage
  - mm/page_io.c:end_swap_bio_write
  - mm/migrate.c:migrate_page_states
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:end_buffer_async_write
  - fs/block_dev.c:bdev_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_finish_bio
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_send
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_locked
```
**Symbols:**

```
ffffffff811ca620-ffffffff811ca684: end_page_writeback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void end_page_writeback(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811eb6d0)
Location: mm/filemap.c:1215
Inline: False
Direct callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:swap_writepage
  - mm/page_io.c:end_swap_bio_write
  - mm/migrate.c:migrate_page_states
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:end_buffer_async_write
  - fs/block_dev.c:bdev_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_finish_bio
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_send
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_locked
```
**Symbols:**

```
ffffffff811eb6d0-ffffffff811eb734: end_page_writeback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void end_page_writeback(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811fc210)
Location: mm/filemap.c:1268
Inline: False
Direct callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:swap_writepage
  - mm/page_io.c:end_swap_bio_write
  - mm/migrate.c:migrate_page_states
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:end_buffer_async_write
  - fs/block_dev.c:bdev_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_finish_bio
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_send
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_locked
```
**Symbols:**

```
ffffffff811fc210-ffffffff811fc274: end_page_writeback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void end_page_writeback(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81213b80)
Location: mm/filemap.c:1316
Inline: True
Direct callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:swap_writepage
  - mm/page_io.c:end_swap_bio_write
  - mm/migrate.c:migrate_page_states
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:end_buffer_async_write
  - fs/block_dev.c:bdev_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_finish_bio
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_send
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_locked
```
**Symbols:**

```
ffffffff81213b80-ffffffff81213be7: end_page_writeback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void end_page_writeback(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81221350)
Location: mm/filemap.c:1325
Inline: True
Direct callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:swap_writepage
  - mm/page_io.c:end_swap_bio_write
  - mm/migrate.c:migrate_page_states
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:end_buffer_async_write
  - fs/block_dev.c:bdev_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_finish_bio
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_send
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_locked
```
**Symbols:**

```
ffffffff81221350-ffffffff812213b7: end_page_writeback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void end_page_writeback(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8124ed30)
Location: mm/filemap.c:1300
Inline: False
Direct callers:
  - mm/filemap.c:page_endio
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:swap_writepage
  - mm/page_io.c:end_swap_bio_write
  - mm/migrate.c:migrate_page_states
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:end_buffer_async_write
  - fs/block_dev.c:bdev_write_page
  - fs/iomap/buffered-io.c:iomap_writepage_map
  - fs/iomap/buffered-io.c:iomap_finish_page_writeback
  - fs/iomap/buffered-io.c:iomap_finish_page_writeback
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_finish_bio
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_send
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_locked
```
**Symbols:**

```
ffffffff8124ed30-ffffffff8124ed99: end_page_writeback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void end_page_writeback(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81259cc0)
Location: mm/filemap.c:1477
Inline: False
Direct callers:
  - mm/filemap.c:page_endio
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:swap_writepage
  - mm/page_io.c:end_swap_bio_write
  - mm/migrate.c:migrate_page_states
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:end_buffer_async_write
  - fs/block_dev.c:bdev_write_page
  - fs/iomap/buffered-io.c:iomap_writepage_map
  - fs/iomap/buffered-io.c:iomap_finish_page_writeback
  - fs/iomap/buffered-io.c:iomap_finish_page_writeback
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_finish_bio
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_send
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_locked
```
**Symbols:**

```
ffffffff81259cc0-ffffffff81259d95: end_page_writeback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void end_page_writeback(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8125df00)
Location: mm/filemap.c:1527
Inline: False
Direct callers:
  - mm/filemap.c:page_endio
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:swap_writepage
  - mm/page_io.c:end_swap_bio_write
  - mm/migrate.c:migrate_page_states
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:end_buffer_async_write
  - fs/block_dev.c:bdev_write_page
  - fs/iomap/buffered-io.c:iomap_writepage_map
  - fs/iomap/buffered-io.c:iomap_finish_ioend
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_finish_bio
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_send
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_locked
```
**Symbols:**

```
ffffffff8125df00-ffffffff8125dfd5: end_page_writeback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void end_page_writeback(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8129a620)
Location: mm/filemap.c:1582
Inline: False
Direct callers:
  - mm/filemap.c:page_endio
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:swap_writepage
  - mm/page_io.c:end_swap_bio_write
  - mm/migrate.c:migrate_page_states
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:end_buffer_async_write
  - fs/iomap/buffered-io.c:iomap_writepage_map
  - fs/iomap/buffered-io.c:iomap_finish_ioend
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_finish_bio
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_send
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_locked
  - block/bdev.c:bdev_write_page
```
**Symbols:**

```
ffffffff8129a620-ffffffff8129a6f2: end_page_writeback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void end_page_writeback(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/folio-compat.c (ffffffff81300b90)
Location: mm/folio-compat.c:24
Inline: False
Direct callers:
  - mm/filemap.c:page_endio
  - mm/page_io.c:sio_write_complete
  - mm/page_io.c:swap_writepage
  - mm/page_io.c:end_swap_bio_write
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:end_buffer_async_write
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_finish_bio
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_send
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_locked
  - block/bdev.c:bdev_write_page
```
**Symbols:**

```
ffffffff81300b90-ffffffff81300beb: end_page_writeback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void end_page_writeback(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/folio-compat.c (ffffffff8136b410)
Location: mm/folio-compat.c:24
Inline: False
Direct callers:
  - mm/page_io.c:sio_write_complete
  - mm/page_io.c:end_swap_bio_write
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:end_buffer_async_write
  - fs/ext4/page-io.c:ext4_finish_bio
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_send
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_locked
  - block/bdev.c:bdev_write_page
```
**Symbols:**

```
ffffffff8136b410-ffffffff8136b46b: end_page_writeback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void end_page_writeback(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/folio-compat.c (ffffffff8139d5a0)
Location: mm/folio-compat.c:25
Inline: False
Direct callers:
  - mm/page_io.c:sio_write_complete
  - mm/page_io.c:__end_swap_bio_write
  - mm/page_io.c:__end_swap_bio_write
  - fs/fuse/file.c:fuse_writepages_send
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_locked
```
**Symbols:**

```
ffffffff8139d5a0-ffffffff8139d60a: end_page_writeback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void end_page_writeback(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/folio-compat.c (ffffffff813c7300)
Location: mm/folio-compat.c:25
Inline: False
Direct callers:
  - mm/page_io.c:sio_write_complete
  - fs/fuse/file.c:fuse_writepages_send
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_locked
```
**Symbols:**

```
ffffffff813c7300-ffffffff813c7367: end_page_writeback (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void end_page_writeback(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffff8000102af290)
Location: mm/filemap.c:1325
Inline: True
Direct callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:swap_writepage
  - mm/page_io.c:end_swap_bio_write
  - mm/migrate.c:migrate_page_states
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:end_buffer_async_write
  - fs/block_dev.c:bdev_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_finish_bio
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_send
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_locked
```
**Symbols:**

```
ffff8000102af290-ffff8000102af330: end_page_writeback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void end_page_writeback(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (c04db56c)
Location: mm/filemap.c:1325
Inline: True
Direct callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:swap_writepage
  - mm/page_io.c:end_swap_bio_write
  - mm/migrate.c:migrate_page_states
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:end_buffer_async_write
  - fs/block_dev.c:bdev_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_finish_bio
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_send
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_locked
```
**Symbols:**

```
c04db56c-c04db5f4: end_page_writeback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void end_page_writeback(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (c000000000363170)
Location: mm/filemap.c:1325
Inline: True
Direct callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:swap_writepage
  - mm/page_io.c:end_swap_bio_write
  - mm/migrate.c:migrate_page_states
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:end_buffer_async_write
  - fs/block_dev.c:bdev_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_finish_bio
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_send
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_locked
```
**Symbols:**

```
c000000000363170-c00000000036324c: end_page_writeback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void end_page_writeback(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffe0001d4b38)
Location: mm/filemap.c:1325
Inline: True
Direct callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:swap_writepage
  - mm/page_io.c:end_swap_bio_write
  - mm/migrate.c:migrate_page_states
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:end_buffer_async_write
  - fs/block_dev.c:bdev_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_finish_bio
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_send
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_locked
```
**Symbols:**

```
ffffffe0001d4b38-ffffffe0001d4bbc: end_page_writeback (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void end_page_writeback(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff812199a0)
Location: mm/filemap.c:1325
Inline: True
Direct callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:swap_writepage
  - mm/page_io.c:end_swap_bio_write
  - mm/migrate.c:migrate_page_states
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:end_buffer_async_write
  - fs/block_dev.c:bdev_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_finish_bio
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_send
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_locked
```
**Symbols:**

```
ffffffff812199a0-ffffffff81219a07: end_page_writeback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void end_page_writeback(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8120cbb0)
Location: mm/filemap.c:1325
Inline: True
Direct callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:swap_writepage
  - mm/page_io.c:end_swap_bio_write
  - mm/migrate.c:migrate_page_states
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:end_buffer_async_write
  - fs/block_dev.c:bdev_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_finish_bio
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_send
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_locked
```
**Symbols:**

```
ffffffff8120cbb0-ffffffff8120cc17: end_page_writeback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void end_page_writeback(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81217740)
Location: mm/filemap.c:1325
Inline: True
Direct callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:swap_writepage
  - mm/page_io.c:end_swap_bio_write
  - mm/migrate.c:migrate_page_states
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:end_buffer_async_write
  - fs/block_dev.c:bdev_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_finish_bio
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_send
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_locked
```
**Symbols:**

```
ffffffff81217740-ffffffff812177a7: end_page_writeback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void end_page_writeback(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff812267f0)
Location: mm/filemap.c:1325
Inline: True
Direct callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:swap_writepage
  - mm/page_io.c:end_swap_bio_write
  - mm/migrate.c:migrate_page_states
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:end_buffer_async_write
  - fs/block_dev.c:bdev_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_finish_bio
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_send
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_locked
```
**Symbols:**

```
ffffffff812267f0-ffffffff81226857: end_page_writeback (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
