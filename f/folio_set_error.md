# Function: <code>folio_set_error</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff813b08aa)
Location: include/linux/page-flags.h:494
Inline: True
Inline callers:
  - mm/migrate.c:folio_migrate_flags
```
```
In fs/buffer.c (ffffffff814460e0)
Location: include/linux/page-flags.h:494
Inline: True
Inline callers:
  - fs/buffer.c:block_read_full_folio
```
```
In fs/iomap/buffered-io.c (ffffffff814886b8)
Location: include/linux/page-flags.h:494
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_finish_ioend
  - fs/iomap/buffered-io.c:iomap_read_folio
  - fs/iomap/buffered-io.c:iomap_read_end_io
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
In mm/filemap.c (ffffffff8135bd60)
Location: include/linux/page-flags.h:473
Inline: True
Inline callers:
  - mm/filemap.c:page_endio
  - mm/filemap.c:page_endio
```
```
In mm/migrate.c (ffffffff8143141e)
Location: include/linux/page-flags.h:473
Inline: True
Inline callers:
  - mm/migrate.c:folio_migrate_flags
```
```
In fs/buffer.c (ffffffff814d5068)
Location: include/linux/page-flags.h:473
Inline: True
Inline callers:
  - fs/buffer.c:block_read_full_folio
```
```
In fs/iomap/buffered-io.c (ffffffff8151c51f)
Location: include/linux/page-flags.h:473
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_finish_ioend
  - fs/iomap/buffered-io.c:iomap_read_folio
  - fs/iomap/buffered-io.c:iomap_read_end_io
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
In mm/migrate.c (ffffffff81466d9e)
Location: include/linux/page-flags.h:467
Inline: True
Inline callers:
  - mm/migrate.c:folio_migrate_flags
```
```
In fs/buffer.c (ffffffff8150b04c)
Location: include/linux/page-flags.h:467
Inline: True
Inline callers:
  - fs/buffer.c:block_read_full_folio
  - fs/buffer.c:__block_write_full_folio
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/mpage.c (ffffffff8150e4ec)
Location: include/linux/page-flags.h:467
Inline: True
Inline callers:
  - fs/mpage.c:mpage_write_end_io
  - fs/mpage.c:mpage_read_end_io
```
```
In fs/iomap/buffered-io.c (ffffffff815546d2)
Location: include/linux/page-flags.h:467
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_finish_ioend
  - fs/iomap/buffered-io.c:iomap_read_folio
  - fs/iomap/buffered-io.c:iomap_read_end_io
```
```
In fs/ext4/move_extent.c (ffffffff815cff74)
Location: include/linux/page-flags.h:467
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (ffffffff815d9e42)
Location: include/linux/page-flags.h:467
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/readpage.c (ffffffff815dba33)
Location: include/linux/page-flags.h:467
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
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
In mm/migrate.c (ffffffff81495ffe)
Location: include/linux/page-flags.h:469
Inline: True
Inline callers:
  - mm/migrate.c:folio_migrate_flags
```
```
In fs/buffer.c (ffffffff8153ff3c)
Location: include/linux/page-flags.h:469
Inline: True
Inline callers:
  - fs/buffer.c:block_read_full_folio
  - fs/buffer.c:__block_write_full_folio
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/mpage.c (ffffffff815431e0)
Location: include/linux/page-flags.h:469
Inline: True
Inline callers:
  - fs/mpage.c:mpage_write_end_io
  - fs/mpage.c:mpage_read_end_io
```
```
In fs/iomap/buffered-io.c (ffffffff8158a9b3)
Location: include/linux/page-flags.h:469
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_finish_ioend
  - fs/iomap/buffered-io.c:iomap_read_folio
  - fs/iomap/buffered-io.c:iomap_read_end_io
```
```
In fs/ext4/move_extent.c (ffffffff816087f0)
Location: include/linux/page-flags.h:469
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (ffffffff816125d1)
Location: include/linux/page-flags.h:469
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/readpage.c (ffffffff816142fc)
Location: include/linux/page-flags.h:469
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
