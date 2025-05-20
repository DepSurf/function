# Function: <code>folio_wait_writeback</code>

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
void folio_wait_writeback(struct folio *folio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff812fcb30)
Location: mm/page-writeback.c:3006
Inline: False
Direct callers:
  - mm/page-writeback.c:folio_wait_stable
  - mm/page-writeback.c:folio_write_one
  - mm/page-writeback.c:folio_write_one
  - mm/folio-compat.c:wait_on_page_writeback
  - mm/folio-compat.c:wait_on_page_writeback
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_partial_folio
  - mm/vmscan.c:shrink_page_list
  - mm/shmem.c:shmem_swapin_folio
  - mm/shmem.c:shmem_swapin_folio
  - fs/splice.c:page_cache_pipe_buf_try_steal
```
**Symbols:**

```
ffffffff812fcb30-ffffffff812fcbc8: folio_wait_writeback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void folio_wait_writeback(struct folio *folio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff81366ea0)
Location: mm/page-writeback.c:3144
Inline: False
Direct callers:
  - mm/page-writeback.c:folio_wait_stable
  - mm/page-writeback.c:folio_write_one
  - mm/page-writeback.c:folio_write_one
  - mm/folio-compat.c:wait_on_page_writeback
  - mm/folio-compat.c:wait_on_page_writeback
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_partial_folio
  - mm/vmscan.c:shrink_folio_list
  - mm/shmem.c:shmem_swapin_folio
  - mm/shmem.c:shmem_swapin_folio
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
  - fs/splice.c:page_cache_pipe_buf_try_steal
```
**Symbols:**

```
ffffffff81366ea0-ffffffff81366f38: folio_wait_writeback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void folio_wait_writeback(struct folio *folio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff81399520)
Location: mm/page-writeback.c:3085
Inline: False
Direct callers:
  - mm/filemap.c:__filemap_fdatawait_range
  - mm/page-writeback.c:folio_wait_stable
  - mm/page-writeback.c:write_cache_pages
  - mm/folio-compat.c:wait_on_page_writeback
  - mm/folio-compat.c:wait_on_page_writeback
  - mm/folio-compat.c:wait_on_page_writeback
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_partial_folio
  - mm/vmscan.c:shrink_folio_list
  - mm/shmem.c:shmem_swapin_folio
  - mm/shmem.c:shmem_swapin_folio
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
  - mm/migrate.c:migrate_folio_unmap
  - fs/splice.c:page_cache_pipe_buf_try_steal
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
```
**Symbols:**

```
ffffffff81399520-ffffffff813995b8: folio_wait_writeback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void folio_wait_writeback(struct folio *folio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff813c3320)
Location: mm/page-writeback.c:3057
Inline: False
Direct callers:
  - mm/filemap.c:__filemap_fdatawait_range
  - mm/page-writeback.c:folio_wait_stable
  - mm/page-writeback.c:write_cache_pages
  - mm/folio-compat.c:wait_on_page_writeback
  - mm/folio-compat.c:wait_on_page_writeback
  - mm/folio-compat.c:wait_on_page_writeback
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_partial_folio
  - mm/vmscan.c:shrink_folio_list
  - mm/shmem.c:shmem_swapin_folio
  - mm/shmem.c:shmem_swapin_folio
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
  - mm/migrate.c:migrate_folio_unmap
  - mm/memory-failure.c:soft_offline_in_use_page
  - fs/splice.c:page_cache_pipe_buf_try_steal
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
```
**Symbols:**

```
ffffffff813c3320-ffffffff813c33b6: folio_wait_writeback (STB_GLOBAL)
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
