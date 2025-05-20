# Function: <code>iomap_length</code>

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
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff813f75bf)
Location: include/linux/iomap.h:196
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_pmd_fault
  - fs/dax.c:dax_iomap_pte_fault
  - fs/dax.c:dax_iomap_iter
```
```
In fs/iomap/trace.c (ffffffff81411bb2)
Location: include/linux/iomap.h:196
Inline: True
Inline callers:
  - fs/iomap/trace.c:perf_trace_iomap_iter
  - fs/iomap/trace.c:trace_event_raw_event_iomap_iter
```
```
In fs/iomap/buffered-io.c (ffffffff81412e3b)
Location: include/linux/iomap.h:196
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
  - fs/iomap/buffered-io.c:iomap_zero_range
  - fs/iomap/buffered-io.c:iomap_file_unshare
  - fs/iomap/buffered-io.c:iomap_file_buffered_write
  - fs/iomap/buffered-io.c:iomap_readahead
  - fs/iomap/buffered-io.c:iomap_readpage_iter
```
```
In fs/iomap/direct-io.c (ffffffff81415d9e)
Location: include/linux/iomap.h:196
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:__iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_inline_iter
  - fs/iomap/direct-io.c:iomap_dio_bio_iter
```
```
In fs/iomap/fiemap.c (ffffffff814163f5)
Location: include/linux/iomap.h:196
Inline: True
Inline callers:
  - fs/iomap/fiemap.c:iomap_fiemap
  - fs/iomap/fiemap.c:iomap_fiemap
```
```
In fs/iomap/iter.c (ffffffff81416688)
Location: include/linux/iomap.h:196
Inline: True
Inline callers:
  - fs/iomap/iter.c:iomap_iter
  - fs/iomap/iter.c:iomap_iter
```
```
In fs/iomap/seek.c (ffffffff81416a88)
Location: include/linux/iomap.h:196
Inline: True
Inline callers:
  - fs/iomap/seek.c:iomap_seek_data
  - fs/iomap/seek.c:iomap_seek_hole
```
```
In fs/iomap/swapfile.c (ffffffff81416d20)
Location: include/linux/iomap.h:196
Inline: True
Inline callers:
  - fs/iomap/swapfile.c:iomap_swapfile_iter
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
In fs/dax.c (ffffffff8146a3a4)
Location: include/linux/iomap.h:202
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_pmd_fault
  - fs/dax.c:dax_iomap_pte_fault
  - fs/dax.c:dax_iomap_iter
  - fs/dax.c:dax_zero_range
```
```
In fs/iomap/trace.c (ffffffff814872c1)
Location: include/linux/iomap.h:202
Inline: True
Inline callers:
  - fs/iomap/trace.c:perf_trace_iomap_iter
  - fs/iomap/trace.c:trace_event_raw_event_iomap_iter
```
```
In fs/iomap/iter.c (ffffffff81487c09)
Location: include/linux/iomap.h:202
Inline: True
Inline callers:
  - fs/iomap/iter.c:iomap_iter
  - fs/iomap/iter.c:iomap_iter
```
```
In fs/iomap/buffered-io.c (ffffffff8148a95e)
Location: include/linux/iomap.h:202
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
  - fs/iomap/buffered-io.c:iomap_zero_range
  - fs/iomap/buffered-io.c:iomap_file_unshare
  - fs/iomap/buffered-io.c:iomap_write_iter
  - fs/iomap/buffered-io.c:iomap_readahead
  - fs/iomap/buffered-io.c:iomap_readpage_iter
```
```
In fs/iomap/direct-io.c (ffffffff8148d574)
Location: include/linux/iomap.h:202
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:__iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_inline_iter
  - fs/iomap/direct-io.c:iomap_dio_bio_iter
```
```
In fs/iomap/fiemap.c (ffffffff8148dcc8)
Location: include/linux/iomap.h:202
Inline: True
Inline callers:
  - fs/iomap/fiemap.c:iomap_fiemap
  - fs/iomap/fiemap.c:iomap_fiemap
```
```
In fs/iomap/seek.c (ffffffff8148e088)
Location: include/linux/iomap.h:202
Inline: True
Inline callers:
  - fs/iomap/seek.c:iomap_seek_data
  - fs/iomap/seek.c:iomap_seek_hole
```
```
In fs/iomap/swapfile.c (ffffffff8148e347)
Location: include/linux/iomap.h:202
Inline: True
Inline callers:
  - fs/iomap/swapfile.c:iomap_swapfile_iter
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
In fs/dax.c (ffffffff814fae51)
Location: include/linux/iomap.h:229
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_pmd_fault
  - fs/dax.c:dax_iomap_pte_fault
  - fs/dax.c:dax_iomap_iter
  - fs/dax.c:dax_zero_range
  - fs/dax.c:dax_file_unshare
```
```
In fs/iomap/trace.c (ffffffff8151ad7e)
Location: include/linux/iomap.h:229
Inline: True
Inline callers:
  - fs/iomap/trace.c:perf_trace_iomap_iter
  - fs/iomap/trace.c:trace_event_raw_event_iomap_iter
```
```
In fs/iomap/iter.c (ffffffff8151b909)
Location: include/linux/iomap.h:229
Inline: True
Inline callers:
  - fs/iomap/iter.c:iomap_iter
  - fs/iomap/iter.c:iomap_iter_advance
```
```
In fs/iomap/buffered-io.c (ffffffff8151e1fd)
Location: include/linux/iomap.h:229
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
  - fs/iomap/buffered-io.c:iomap_zero_range
  - fs/iomap/buffered-io.c:iomap_file_unshare
  - fs/iomap/buffered-io.c:iomap_write_iter
  - fs/iomap/buffered-io.c:iomap_readahead
  - fs/iomap/buffered-io.c:iomap_readpage_iter
```
```
In fs/iomap/direct-io.c (ffffffff81520b46)
Location: include/linux/iomap.h:229
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:__iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_inline_iter
  - fs/iomap/direct-io.c:iomap_dio_bio_iter
```
```
In fs/iomap/fiemap.c (ffffffff815214b8)
Location: include/linux/iomap.h:229
Inline: True
Inline callers:
  - fs/iomap/fiemap.c:iomap_fiemap
  - fs/iomap/fiemap.c:iomap_fiemap
```
```
In fs/iomap/seek.c (ffffffff815218a8)
Location: include/linux/iomap.h:229
Inline: True
Inline callers:
  - fs/iomap/seek.c:iomap_seek_data
  - fs/iomap/seek.c:iomap_seek_hole
```
```
In fs/iomap/swapfile.c (ffffffff81521bcf)
Location: include/linux/iomap.h:229
Inline: True
Inline callers:
  - fs/iomap/swapfile.c:iomap_swapfile_iter
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
In fs/dax.c (ffffffff815322a4)
Location: include/linux/iomap.h:230
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_pmd_fault
  - fs/dax.c:dax_iomap_pte_fault
  - fs/dax.c:dax_iomap_iter
  - fs/dax.c:dax_zero_range
  - fs/dax.c:dax_unshare_iter
```
```
In fs/iomap/trace.c (ffffffff815527de)
Location: include/linux/iomap.h:230
Inline: True
Inline callers:
  - fs/iomap/trace.c:perf_trace_iomap_iter
  - fs/iomap/trace.c:trace_event_raw_event_iomap_iter
```
```
In fs/iomap/iter.c (ffffffff81553bc9)
Location: include/linux/iomap.h:230
Inline: True
Inline callers:
  - fs/iomap/iter.c:iomap_iter
  - fs/iomap/iter.c:iomap_iter_advance
```
```
In fs/iomap/buffered-io.c (ffffffff81556363)
Location: include/linux/iomap.h:230
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
  - fs/iomap/buffered-io.c:iomap_zero_range
  - fs/iomap/buffered-io.c:iomap_file_unshare
  - fs/iomap/buffered-io.c:iomap_write_iter
  - fs/iomap/buffered-io.c:iomap_readahead
  - fs/iomap/buffered-io.c:iomap_readpage_iter
```
```
In fs/iomap/direct-io.c (ffffffff81558ad6)
Location: include/linux/iomap.h:230
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:__iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_inline_iter
  - fs/iomap/direct-io.c:iomap_dio_bio_iter
```
```
In fs/iomap/fiemap.c (ffffffff815594f8)
Location: include/linux/iomap.h:230
Inline: True
Inline callers:
  - fs/iomap/fiemap.c:iomap_fiemap
  - fs/iomap/fiemap.c:iomap_fiemap
```
```
In fs/iomap/seek.c (ffffffff815598e8)
Location: include/linux/iomap.h:230
Inline: True
Inline callers:
  - fs/iomap/seek.c:iomap_seek_data
  - fs/iomap/seek.c:iomap_seek_hole
```
```
In fs/iomap/swapfile.c (ffffffff81559c0f)
Location: include/linux/iomap.h:230
Inline: True
Inline callers:
  - fs/iomap/swapfile.c:iomap_swapfile_iter
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
In fs/dax.c (ffffffff81567194)
Location: include/linux/iomap.h:234
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_pmd_fault
  - fs/dax.c:dax_iomap_pte_fault
  - fs/dax.c:dax_iomap_iter
  - fs/dax.c:dax_zero_range
  - fs/dax.c:dax_unshare_iter
```
```
In fs/iomap/trace.c (ffffffff8158879e)
Location: include/linux/iomap.h:234
Inline: True
Inline callers:
  - fs/iomap/trace.c:perf_trace_iomap_iter
  - fs/iomap/trace.c:trace_event_raw_event_iomap_iter
```
```
In fs/iomap/iter.c (ffffffff81589b89)
Location: include/linux/iomap.h:234
Inline: True
Inline callers:
  - fs/iomap/iter.c:iomap_iter
  - fs/iomap/iter.c:iomap_iter_advance
```
```
In fs/iomap/buffered-io.c (ffffffff8158c82f)
Location: include/linux/iomap.h:234
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
  - fs/iomap/buffered-io.c:iomap_zero_range
  - fs/iomap/buffered-io.c:iomap_file_unshare
  - fs/iomap/buffered-io.c:iomap_write_iter
  - fs/iomap/buffered-io.c:iomap_readahead
  - fs/iomap/buffered-io.c:iomap_readpage_iter
```
```
In fs/iomap/direct-io.c (ffffffff8158f219)
Location: include/linux/iomap.h:234
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:__iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_inline_iter
  - fs/iomap/direct-io.c:iomap_dio_bio_iter
```
```
In fs/iomap/fiemap.c (ffffffff8158fc88)
Location: include/linux/iomap.h:234
Inline: True
Inline callers:
  - fs/iomap/fiemap.c:iomap_fiemap
  - fs/iomap/fiemap.c:iomap_fiemap
```
```
In fs/iomap/seek.c (ffffffff81590078)
Location: include/linux/iomap.h:234
Inline: True
Inline callers:
  - fs/iomap/seek.c:iomap_seek_data
  - fs/iomap/seek.c:iomap_seek_hole
```
```
In fs/iomap/swapfile.c (ffffffff815903cf)
Location: include/linux/iomap.h:234
Inline: True
Inline callers:
  - fs/iomap/swapfile.c:iomap_swapfile_iter
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
