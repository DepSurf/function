# Function: <code>iomap_iter</code>

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
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int iomap_iter(struct iomap_iter *iter, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/iter.c (ffffffff81416640)
Location: fs/iomap/iter.c:57
Inline: False
Direct callers:
  - fs/dax.c:dax_iomap_pmd_fault
  - fs/dax.c:dax_iomap_pmd_fault
  - fs/dax.c:dax_iomap_pte_fault
  - fs/dax.c:dax_iomap_pte_fault
  - fs/dax.c:dax_iomap_rw
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
  - fs/iomap/buffered-io.c:iomap_zero_range
  - fs/iomap/buffered-io.c:iomap_file_unshare
  - fs/iomap/buffered-io.c:iomap_file_buffered_write
  - fs/iomap/buffered-io.c:iomap_readahead
  - fs/iomap/buffered-io.c:iomap_readahead
  - fs/iomap/buffered-io.c:iomap_readpage
  - fs/iomap/direct-io.c:__iomap_dio_rw
  - fs/iomap/fiemap.c:iomap_bmap
  - fs/iomap/fiemap.c:iomap_fiemap
  - fs/iomap/seek.c:iomap_seek_data
  - fs/iomap/seek.c:iomap_seek_hole
  - fs/iomap/swapfile.c:iomap_swapfile_activate
```
**Symbols:**

```
ffffffff81416640-ffffffff81416851: iomap_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int iomap_iter(struct iomap_iter *iter, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/iter.c (ffffffff81487bd0)
Location: fs/iomap/iter.c:57
Inline: False
Direct callers:
  - fs/dax.c:dax_iomap_pmd_fault
  - fs/dax.c:dax_iomap_pmd_fault
  - fs/dax.c:dax_iomap_pte_fault
  - fs/dax.c:dax_iomap_pte_fault
  - fs/dax.c:dax_iomap_rw
  - fs/dax.c:dax_zero_range
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
  - fs/iomap/buffered-io.c:iomap_zero_range
  - fs/iomap/buffered-io.c:iomap_file_unshare
  - fs/iomap/buffered-io.c:iomap_file_buffered_write
  - fs/iomap/buffered-io.c:iomap_readahead
  - fs/iomap/buffered-io.c:iomap_readahead
  - fs/iomap/buffered-io.c:iomap_read_folio
  - fs/iomap/direct-io.c:__iomap_dio_rw
  - fs/iomap/fiemap.c:iomap_bmap
  - fs/iomap/fiemap.c:iomap_fiemap
  - fs/iomap/seek.c:iomap_seek_data
  - fs/iomap/seek.c:iomap_seek_hole
  - fs/iomap/swapfile.c:iomap_swapfile_activate
```
**Symbols:**

```
ffffffff81487bd0-ffffffff81487df5: iomap_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int iomap_iter(struct iomap_iter *iter, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/iter.c (ffffffff8151b8d0)
Location: fs/iomap/iter.c:74
Inline: False
Direct callers:
  - fs/dax.c:dax_dedupe_file_range_compare
  - fs/dax.c:dax_dedupe_file_range_compare
  - fs/dax.c:dax_iomap_pmd_fault
  - fs/dax.c:dax_iomap_pmd_fault
  - fs/dax.c:dax_iomap_pte_fault
  - fs/dax.c:dax_iomap_pte_fault
  - fs/dax.c:dax_iomap_rw
  - fs/dax.c:dax_zero_range
  - fs/dax.c:dax_file_unshare
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
  - fs/iomap/buffered-io.c:iomap_zero_range
  - fs/iomap/buffered-io.c:iomap_file_unshare
  - fs/iomap/buffered-io.c:iomap_file_buffered_write
  - fs/iomap/buffered-io.c:iomap_readahead
  - fs/iomap/buffered-io.c:iomap_readahead
  - fs/iomap/buffered-io.c:iomap_read_folio
  - fs/iomap/direct-io.c:__iomap_dio_rw
  - fs/iomap/fiemap.c:iomap_bmap
  - fs/iomap/fiemap.c:iomap_fiemap
  - fs/iomap/seek.c:iomap_seek_data
  - fs/iomap/seek.c:iomap_seek_hole
  - fs/iomap/swapfile.c:iomap_swapfile_activate
```
**Symbols:**

```
ffffffff8151b8d0-ffffffff8151ba09: iomap_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int iomap_iter(struct iomap_iter *iter, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/iter.c (ffffffff81553b90)
Location: fs/iomap/iter.c:74
Inline: False
Direct callers:
  - fs/dax.c:dax_dedupe_file_range_compare
  - fs/dax.c:dax_dedupe_file_range_compare
  - fs/dax.c:dax_iomap_pmd_fault
  - fs/dax.c:dax_iomap_pmd_fault
  - fs/dax.c:dax_iomap_pte_fault
  - fs/dax.c:dax_iomap_pte_fault
  - fs/dax.c:dax_iomap_rw
  - fs/dax.c:dax_zero_range
  - fs/dax.c:dax_file_unshare
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
  - fs/iomap/buffered-io.c:iomap_zero_range
  - fs/iomap/buffered-io.c:iomap_file_unshare
  - fs/iomap/buffered-io.c:iomap_file_buffered_write
  - fs/iomap/buffered-io.c:iomap_readahead
  - fs/iomap/buffered-io.c:iomap_readahead
  - fs/iomap/buffered-io.c:iomap_read_folio
  - fs/iomap/direct-io.c:__iomap_dio_rw
  - fs/iomap/fiemap.c:iomap_bmap
  - fs/iomap/fiemap.c:iomap_fiemap
  - fs/iomap/seek.c:iomap_seek_data
  - fs/iomap/seek.c:iomap_seek_hole
  - fs/iomap/swapfile.c:iomap_swapfile_activate
```
**Symbols:**

```
ffffffff81553b90-ffffffff81553cc9: iomap_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int iomap_iter(struct iomap_iter *iter, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/iter.c (ffffffff81589b50)
Location: fs/iomap/iter.c:74
Inline: False
Direct callers:
  - fs/dax.c:dax_dedupe_file_range_compare
  - fs/dax.c:dax_dedupe_file_range_compare
  - fs/dax.c:dax_iomap_pmd_fault
  - fs/dax.c:dax_iomap_pmd_fault
  - fs/dax.c:dax_iomap_pte_fault
  - fs/dax.c:dax_iomap_pte_fault
  - fs/dax.c:dax_iomap_rw
  - fs/dax.c:dax_zero_range
  - fs/dax.c:dax_file_unshare
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
  - fs/iomap/buffered-io.c:iomap_zero_range
  - fs/iomap/buffered-io.c:iomap_file_unshare
  - fs/iomap/buffered-io.c:iomap_file_buffered_write
  - fs/iomap/buffered-io.c:iomap_readahead
  - fs/iomap/buffered-io.c:iomap_readahead
  - fs/iomap/buffered-io.c:iomap_read_folio
  - fs/iomap/direct-io.c:__iomap_dio_rw
  - fs/iomap/fiemap.c:iomap_bmap
  - fs/iomap/fiemap.c:iomap_fiemap
  - fs/iomap/seek.c:iomap_seek_data
  - fs/iomap/seek.c:iomap_seek_hole
  - fs/iomap/swapfile.c:iomap_swapfile_activate
```
**Symbols:**

```
ffffffff81589b50-ffffffff81589c89: iomap_iter (STB_GLOBAL)
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
