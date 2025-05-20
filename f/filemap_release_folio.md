# Function: <code>filemap_release_folio</code>

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
bool filemap_release_folio(struct folio *folio, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff812ef460)
Location: mm/filemap.c:3965
Inline: False
Direct callers:
  - mm/folio-compat.c:try_to_release_page
  - mm/folio-compat.c:try_to_release_page
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:mapping_evict_folio
  - mm/vmscan.c:shrink_page_list
  - fs/splice.c:page_cache_pipe_buf_try_steal
  - fs/buffer.c:block_invalidate_folio
```
**Symbols:**

```
ffffffff812ef460-ffffffff812ef4c2: filemap_release_folio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool filemap_release_folio(struct folio *folio, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81359fa0)
Location: mm/filemap.c:3959
Inline: False
Direct callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:mapping_evict_folio
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_folio_list
  - mm/migrate.c:move_to_new_folio
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/khugepaged.c:collapse_file
  - mm/memory-failure.c:truncate_error_page
  - fs/splice.c:page_cache_pipe_buf_try_steal
  - fs/buffer.c:block_invalidate_folio
```
**Symbols:**

```
ffffffff81359fa0-ffffffff8135a002: filemap_release_folio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool filemap_release_folio(struct folio *folio, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8138b9e0)
Location: mm/filemap.c:4072
Inline: False
Direct callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:mapping_evict_folio
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_folio_list
  - mm/migrate.c:move_to_new_folio
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/khugepaged.c:collapse_file
  - mm/memory-failure.c:truncate_error_page
  - fs/splice.c:page_cache_pipe_buf_try_steal
  - fs/buffer.c:block_invalidate_folio
```
**Symbols:**

```
ffffffff8138b9e0-ffffffff8138ba3f: filemap_release_folio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool filemap_release_folio(struct folio *folio, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff813b54c0)
Location: mm/filemap.c:4079
Inline: False
Direct callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:mapping_evict_folio
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_folio_list
  - mm/migrate.c:move_to_new_folio
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/khugepaged.c:collapse_file
  - mm/memory-failure.c:truncate_error_folio
  - fs/splice.c:page_cache_pipe_buf_try_steal
  - fs/buffer.c:block_invalidate_folio
```
**Symbols:**

```
ffffffff813b54c0-ffffffff813b5560: filemap_release_folio (STB_GLOBAL)
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
