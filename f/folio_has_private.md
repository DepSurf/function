# Function: <code>folio_has_private</code>

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
In mm/truncate.c (ffffffff81307767)
Location: include/linux/page-flags.h:1089
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:mapping_evict_folio
  - mm/truncate.c:truncate_inode_partial_folio
  - mm/truncate.c:truncate_cleanup_folio
```
```
In mm/vmscan.c (ffffffff8130e612)
Location: include/linux/page-flags.h:1089
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
```
```
In fs/splice.c (ffffffff81437f22)
Location: include/linux/page-flags.h:1089
Inline: True
Inline callers:
  - fs/splice.c:page_cache_pipe_buf_try_steal
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
In mm/truncate.c (ffffffff813718d7)
Location: include/linux/page-flags.h:1068
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:mapping_evict_folio
  - mm/truncate.c:truncate_inode_partial_folio
  - mm/truncate.c:truncate_cleanup_folio
```
```
In mm/vmscan.c (ffffffff813805e0)
Location: include/linux/page-flags.h:1068
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_folio_list
```
```
In mm/migrate.c (ffffffff8143408d)
Location: include/linux/page-flags.h:1068
Inline: True
Inline callers:
  - mm/migrate.c:migrate_huge_page_move_mapping
```
```
In mm/khugepaged.c (ffffffff814499c2)
Location: include/linux/page-flags.h:1068
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In mm/memory-failure.c (ffffffff8145f464)
Location: include/linux/page-flags.h:1068
Inline: True
Inline callers:
  - mm/memory-failure.c:truncate_error_page
```
```
In fs/splice.c (ffffffff814c6b4b)
Location: include/linux/page-flags.h:1068
Inline: True
Inline callers:
  - fs/splice.c:page_cache_pipe_buf_try_steal
```
```
In fs/ext4/move_extent.c (ffffffff815999a9)
Location: include/linux/page-flags.h:1068
Inline: True
```
```
In fs/fuse/dev.c (ffffffff8161b019)
Location: include/linux/page-flags.h:1068
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
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
In mm/truncate.c (ffffffff813a39e4)
Location: include/linux/page-flags.h:1057
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:mapping_evict_folio
  - mm/truncate.c:truncate_inode_partial_folio
  - mm/truncate.c:truncate_cleanup_folio
```
```
In mm/vmscan.c (ffffffff813b1a32)
Location: include/linux/page-flags.h:1057
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_folio_list
```
```
In mm/migrate.c (ffffffff814699cd)
Location: include/linux/page-flags.h:1057
Inline: True
Inline callers:
  - mm/migrate.c:migrate_huge_page_move_mapping
```
```
In mm/khugepaged.c (ffffffff8147fa71)
Location: include/linux/page-flags.h:1057
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In mm/memory-failure.c (ffffffff81495411)
Location: include/linux/page-flags.h:1057
Inline: True
Inline callers:
  - mm/memory-failure.c:truncate_error_page
```
```
In fs/splice.c (ffffffff814fbbeb)
Location: include/linux/page-flags.h:1057
Inline: True
Inline callers:
  - fs/splice.c:page_cache_pipe_buf_try_steal
```
```
In fs/ext4/move_extent.c (ffffffff815d0244)
Location: include/linux/page-flags.h:1057
Inline: True
```
```
In fs/fuse/dev.c (ffffffff81653189)
Location: include/linux/page-flags.h:1057
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
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
In mm/filemap.c (ffffffff813b54eb)
Location: include/linux/page-flags.h:1111
Inline: True
Inline callers:
  - mm/filemap.c:filemap_release_folio
```
```
In mm/truncate.c (ffffffff813cd542)
Location: include/linux/page-flags.h:1111
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:mapping_evict_folio
  - mm/truncate.c:truncate_inode_partial_folio
  - mm/truncate.c:truncate_cleanup_folio
```
```
In mm/vmscan.c (ffffffff813d9139)
Location: include/linux/page-flags.h:1111
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_folio_list
```
```
In fs/fuse/dev.c (ffffffff8168c78d)
Location: include/linux/page-flags.h:1111
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
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
