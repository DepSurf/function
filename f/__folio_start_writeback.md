# Function: <code>__folio_start_writeback</code>

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
bool __folio_start_writeback(struct folio *folio, bool keep_write);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff812feeb0)
Location: mm/page-writeback.c:2930
Inline: False
Direct callers:
  - mm/folio-compat.c:set_page_writeback
  - mm/folio-compat.c:set_page_writeback
  - fs/iomap/buffered-io.c:iomap_writepage_map
  - fs/ext4/page-io.c:ext4_bio_write_page
```
**Symbols:**

```
ffffffff812feeb0-ffffffff812ff1c8: __folio_start_writeback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool __folio_start_writeback(struct folio *folio, bool keep_write);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff81369670)
Location: mm/page-writeback.c:3068
Inline: False
Direct callers:
  - mm/folio-compat.c:set_page_writeback
  - mm/folio-compat.c:set_page_writeback
  - mm/page_io.c:swap_writepage
  - fs/iomap/buffered-io.c:iomap_writepage_map
  - fs/ext4/page-io.c:ext4_bio_write_page
```
**Symbols:**

```
ffffffff81369670-ffffffff813698e6: __folio_start_writeback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool __folio_start_writeback(struct folio *folio, bool keep_write);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff8139b810)
Location: mm/page-writeback.c:3009
Inline: False
Direct callers:
  - mm/folio-compat.c:set_page_writeback
  - mm/folio-compat.c:set_page_writeback
  - mm/folio-compat.c:set_page_writeback
  - mm/page_io.c:swap_writepage
  - fs/buffer.c:__block_write_full_folio
  - fs/buffer.c:__block_write_full_folio
  - fs/mpage.c:__mpage_writepage
  - fs/iomap/buffered-io.c:iomap_writepage_map
  - fs/ext4/page-io.c:ext4_bio_write_folio
  - fs/fuse/file.c:fuse_writepages_fill
```
**Symbols:**

```
ffffffff8139b810-ffffffff8139ba83: __folio_start_writeback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __folio_start_writeback(struct folio *folio, bool keep_write);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff813c4280)
Location: mm/page-writeback.c:2985
Inline: False
Direct callers:
  - mm/folio-compat.c:set_page_writeback
  - mm/folio-compat.c:set_page_writeback
  - mm/folio-compat.c:set_page_writeback
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:swap_writepage_bdev_sync
  - mm/page_io.c:swap_writepage_fs
  - mm/page_io.c:swap_writepage
  - fs/buffer.c:__block_write_full_folio
  - fs/buffer.c:__block_write_full_folio
  - fs/mpage.c:__mpage_writepage
  - fs/iomap/buffered-io.c:iomap_writepage_map
  - fs/ext4/page-io.c:ext4_bio_write_folio
  - fs/fuse/file.c:fuse_writepages_fill
```
**Symbols:**

```
ffffffff813c4280-ffffffff813c44e4: __folio_start_writeback (STB_GLOBAL)
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>bool</code> ➡️ <code>void</code>
</li>
</ul>
</details>
</li>
</ul>
