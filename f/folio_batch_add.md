# Function: <code>folio_batch_add</code>

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
In mm/filemap.c (ffffffff812f2f06)
Location: include/linux/pagevec.h:137
Inline: True
Inline callers:
  - mm/filemap.c:filemap_get_pages
  - mm/filemap.c:filemap_get_read_batch
  - mm/filemap.c:find_lock_entries
  - mm/filemap.c:find_get_entries
```
```
In mm/shmem.c (ffffffff81318aa6)
Location: include/linux/pagevec.h:137
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
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
In mm/filemap.c (ffffffff8135d2c6)
Location: include/linux/pagevec.h:126
Inline: True
Inline callers:
  - mm/filemap.c:filemap_get_pages
  - mm/filemap.c:filemap_get_read_batch
  - mm/filemap.c:filemap_get_folios_contig
  - mm/filemap.c:filemap_get_folios
  - mm/filemap.c:find_lock_entries
  - mm/filemap.c:find_get_entries
```
```
In mm/swap.c (ffffffff81371025)
Location: include/linux/pagevec.h:126
Inline: True
Inline callers:
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:deactivate_page
  - mm/swap.c:deactivate_file_folio
  - mm/swap.c:folio_add_lru
  - mm/swap.c:folio_rotate_reclaimable
```
```
In mm/vmscan.c (ffffffff8137ebe9)
Location: include/linux/pagevec.h:126
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
```
```
In mm/shmem.c (ffffffff8138c966)
Location: include/linux/pagevec.h:126
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
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
In mm/filemap.c (ffffffff8138f325)
Location: include/linux/pagevec.h:71
Inline: True
Inline callers:
  - mm/filemap.c:filemap_get_pages
  - mm/filemap.c:filemap_get_read_batch
  - mm/filemap.c:filemap_get_folios_tag
  - mm/filemap.c:filemap_get_folios_contig
  - mm/filemap.c:filemap_get_folios
  - mm/filemap.c:find_lock_entries
  - mm/filemap.c:find_get_entries
```
```
In mm/swap.c (ffffffff813a31be)
Location: include/linux/pagevec.h:71
Inline: True
Inline callers:
  - mm/swap.c:folio_mark_lazyfree
  - mm/swap.c:folio_deactivate
  - mm/swap.c:deactivate_file_folio
  - mm/swap.c:folio_add_lru
  - mm/swap.c:folio_rotate_reclaimable
```
```
In mm/shmem.c (ffffffff813bf00c)
Location: include/linux/pagevec.h:71
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
```
```
In mm/mlock.c (ffffffff813f947d)
Location: include/linux/pagevec.h:71
Inline: True
Inline callers:
  - mm/mlock.c:munlock_folio
  - mm/mlock.c:mlock_new_folio
  - mm/mlock.c:mlock_folio
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
In mm/filemap.c (ffffffff813b89d5)
Location: include/linux/pagevec.h:71
Inline: True
Inline callers:
  - mm/filemap.c:filemap_get_pages
  - mm/filemap.c:filemap_get_read_batch
  - mm/filemap.c:filemap_get_folios_tag
  - mm/filemap.c:filemap_get_folios_contig
  - mm/filemap.c:find_lock_entries
  - mm/filemap.c:find_get_entries
```
```
In mm/swap.c (ffffffff813cce2e)
Location: include/linux/pagevec.h:71
Inline: True
Inline callers:
  - mm/swap.c:folio_mark_lazyfree
  - mm/swap.c:folio_deactivate
  - mm/swap.c:deactivate_file_folio
  - mm/swap.c:folio_add_lru
  - mm/swap.c:folio_rotate_reclaimable
```
```
In mm/shmem.c (ffffffff813ea05c)
Location: include/linux/pagevec.h:71
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
```
```
In mm/mlock.c (ffffffff8142501d)
Location: include/linux/pagevec.h:71
Inline: True
Inline callers:
  - mm/mlock.c:munlock_folio
  - mm/mlock.c:mlock_new_folio
  - mm/mlock.c:mlock_folio
```
```
In drivers/gpu/drm/drm_gem.c (ffffffff81c9c22d)
Location: include/linux/pagevec.h:71
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_gem.c:drm_gem_put_pages
  - drivers/gpu/drm/drm_gem.c:drm_gem_get_pages
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
