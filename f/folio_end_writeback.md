# Function: <code>folio_end_writeback</code>

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
<summary>In <code>5.19</code>: ✅</summary>

```c
void folio_end_writeback(struct folio *folio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff812f01c0)
Location: mm/filemap.c:1625
Inline: False
Direct callers:
  - mm/folio-compat.c:end_page_writeback
  - mm/folio-compat.c:end_page_writeback
  - mm/migrate.c:folio_migrate_flags
  - fs/iomap/buffered-io.c:iomap_writepage_map
  - fs/iomap/buffered-io.c:iomap_finish_ioend
```
**Symbols:**

```
ffffffff812f01c0-ffffffff812f025e: folio_end_writeback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void folio_end_writeback(struct folio *folio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8135b560)
Location: mm/filemap.c:1593
Inline: False
Direct callers:
  - mm/filemap.c:page_endio
  - mm/folio-compat.c:end_page_writeback
  - mm/folio-compat.c:end_page_writeback
  - mm/page_io.c:swap_writepage
  - mm/migrate.c:folio_migrate_flags
  - fs/iomap/buffered-io.c:iomap_writepage_map
  - fs/iomap/buffered-io.c:iomap_finish_ioend
```
**Symbols:**

```
ffffffff8135b560-ffffffff8135b5fe: folio_end_writeback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void folio_end_writeback(struct folio *folio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8138d3c0)
Location: mm/filemap.c:1597
Inline: False
Direct callers:
  - mm/folio-compat.c:end_page_writeback
  - mm/folio-compat.c:end_page_writeback
  - mm/folio-compat.c:end_page_writeback
  - mm/page_io.c:swap_writepage
  - mm/migrate.c:folio_migrate_flags
  - fs/buffer.c:__block_write_full_folio
  - fs/buffer.c:end_buffer_async_write
  - fs/mpage.c:mpage_write_end_io
  - fs/iomap/buffered-io.c:iomap_writepage_map
  - fs/iomap/buffered-io.c:iomap_finish_ioend
  - fs/ext4/page-io.c:ext4_finish_bio
  - fs/fuse/file.c:fuse_writepages_fill
```
**Symbols:**

```
ffffffff8138d3c0-ffffffff8138d45e: folio_end_writeback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void folio_end_writeback(struct folio *folio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff813b6f50)
Location: mm/filemap.c:1578
Inline: False
Direct callers:
  - mm/folio-compat.c:end_page_writeback
  - mm/folio-compat.c:end_page_writeback
  - mm/folio-compat.c:end_page_writeback
  - mm/page_io.c:swap_writepage
  - mm/page_io.c:__end_swap_bio_write
  - mm/page_io.c:__end_swap_bio_write
  - mm/migrate.c:folio_migrate_flags
  - fs/buffer.c:__block_write_full_folio
  - fs/buffer.c:end_buffer_async_write
  - fs/mpage.c:mpage_write_end_io
  - fs/iomap/buffered-io.c:iomap_writepage_map
  - fs/iomap/buffered-io.c:iomap_finish_ioend
  - fs/ext4/page-io.c:ext4_finish_bio
  - fs/fuse/file.c:fuse_writepages_fill
```
**Symbols:**

```
ffffffff813b6f50-ffffffff813b6fe7: folio_end_writeback (STB_GLOBAL)
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
<b>Regular</b>
<ul>
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
