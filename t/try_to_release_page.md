# Function: <code>try_to_release_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int try_to_release_page(struct page *page, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8118d820)
Location: mm/filemap.c:2719
Inline: True
Direct callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_page
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_active_list
  - fs/splice.c:page_cache_pipe_buf_steal
  - fs/buffer.c:block_invalidatepage
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
```
**Symbols:**

```
ffffffff8118d820-ffffffff8118d85f: try_to_release_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int try_to_release_page(struct page *page, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811a0430)
Location: mm/filemap.c:2892
Inline: True
Direct callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_page
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_page_list
  - mm/migrate.c:move_to_new_page
  - fs/splice.c:page_cache_pipe_buf_steal
  - fs/buffer.c:block_invalidatepage
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
```
**Symbols:**

```
ffffffff811a0430-ffffffff811a047e: try_to_release_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int try_to_release_page(struct page *page, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811af840)
Location: mm/filemap.c:3008
Inline: True
Direct callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_page
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_page_list
  - mm/migrate.c:move_to_new_page
  - fs/splice.c:page_cache_pipe_buf_steal
  - fs/buffer.c:block_invalidatepage
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
```
**Symbols:**

```
ffffffff811af840-ffffffff811af88e: try_to_release_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int try_to_release_page(struct page *page, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811b6730)
Location: mm/filemap.c:3142
Inline: True
Direct callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_page
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_page_list
  - mm/migrate.c:move_to_new_page
  - fs/splice.c:page_cache_pipe_buf_steal
  - fs/buffer.c:block_invalidatepage
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
```
**Symbols:**

```
ffffffff811b6730-ffffffff811b677e: try_to_release_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int try_to_release_page(struct page *page, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811ca800)
Location: mm/filemap.c:3318
Inline: False
Direct callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_page
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_page_list
  - mm/migrate.c:move_to_new_page
  - fs/splice.c:page_cache_pipe_buf_steal
  - fs/buffer.c:block_invalidatepage
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
```
**Symbols:**

```
ffffffff811ca800-ffffffff811ca85e: try_to_release_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int try_to_release_page(struct page *page, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811ebb10)
Location: mm/filemap.c:3318
Inline: True
Direct callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_page
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_page_list
  - mm/migrate.c:move_to_new_page
  - fs/splice.c:page_cache_pipe_buf_steal
  - fs/buffer.c:block_invalidatepage
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
```
**Symbols:**

```
ffffffff811ebb10-ffffffff811ebb6e: try_to_release_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int try_to_release_page(struct page *page, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811fc6c0)
Location: mm/filemap.c:3387
Inline: True
Direct callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_page
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_page_list
  - mm/migrate.c:move_to_new_page
  - fs/splice.c:page_cache_pipe_buf_steal
  - fs/buffer.c:block_invalidatepage
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
```
**Symbols:**

```
ffffffff811fc6c0-ffffffff811fc71e: try_to_release_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int try_to_release_page(struct page *page, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81213e20)
Location: mm/filemap.c:3514
Inline: True
Direct callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_page
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_page_list
  - mm/migrate.c:move_to_new_page
  - mm/memory-failure.c:truncate_error_page
  - fs/splice.c:page_cache_pipe_buf_steal
  - fs/buffer.c:block_invalidatepage
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
```
**Symbols:**

```
ffffffff81213e20-ffffffff81213e7f: try_to_release_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int try_to_release_page(struct page *page, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81221630)
Location: mm/filemap.c:3471
Inline: True
Direct callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_page
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_page_list
  - mm/migrate.c:move_to_new_page
  - mm/khugepaged.c:collapse_file
  - mm/memory-failure.c:truncate_error_page
  - fs/splice.c:page_cache_pipe_buf_steal
  - fs/buffer.c:block_invalidatepage
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
```
**Symbols:**

```
ffffffff81221630-ffffffff8122168f: try_to_release_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int try_to_release_page(struct page *page, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8124e2b0)
Location: mm/filemap.c:3505
Inline: False
Direct callers:
  - mm/truncate.c:invalidate_complete_page2
  - mm/truncate.c:invalidate_inode_page
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_page_list
  - mm/migrate.c:move_to_new_page
  - mm/khugepaged.c:collapse_file
  - mm/memory-failure.c:truncate_error_page
  - fs/splice.c:page_cache_pipe_buf_try_steal
  - fs/buffer.c:block_invalidatepage
```
**Symbols:**

```
ffffffff8124e2b0-ffffffff8124e30f: try_to_release_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int try_to_release_page(struct page *page, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff812586c0)
Location: mm/filemap.c:3599
Inline: False
Direct callers:
  - mm/truncate.c:invalidate_complete_page2
  - mm/truncate.c:invalidate_inode_page
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_page_list
  - mm/migrate.c:move_to_new_page
  - mm/khugepaged.c:collapse_file
  - mm/memory-failure.c:truncate_error_page
  - fs/splice.c:page_cache_pipe_buf_try_steal
  - fs/buffer.c:block_invalidatepage
```
**Symbols:**

```
ffffffff812586c0-ffffffff8125871f: try_to_release_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int try_to_release_page(struct page *page, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8125cd40)
Location: mm/filemap.c:3847
Inline: False
Direct callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_page
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_page_list
  - mm/migrate.c:move_to_new_page
  - mm/khugepaged.c:collapse_file
  - mm/memory-failure.c:truncate_error_page
  - fs/splice.c:page_cache_pipe_buf_try_steal
  - fs/buffer.c:block_invalidatepage
```
**Symbols:**

```
ffffffff8125cd40-ffffffff8125cd9f: try_to_release_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int try_to_release_page(struct page *page, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81298cb0)
Location: mm/filemap.c:3958
Inline: False
Direct callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_page
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_page_list
  - mm/migrate.c:move_to_new_page
  - mm/khugepaged.c:collapse_file
  - mm/memory-failure.c:truncate_error_page
  - fs/splice.c:page_cache_pipe_buf_try_steal
  - fs/buffer.c:block_invalidatepage
```
**Symbols:**

```
ffffffff81298cb0-ffffffff81298d12: try_to_release_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int try_to_release_page(struct page *page, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/folio-compat.c (ffffffff81300ef0)
Location: mm/folio-compat.c:148
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_active_list
  - mm/migrate.c:move_to_new_folio
  - mm/khugepaged.c:collapse_file
  - mm/memory-failure.c:truncate_error_page
```
**Symbols:**

```
ffffffff81300ef0-ffffffff81300f51: try_to_release_page (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int try_to_release_page(struct page *page, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffff8000102ae1d8)
Location: mm/filemap.c:3471
Inline: True
Direct callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_page
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_page_list
  - mm/migrate.c:move_to_new_page
  - mm/khugepaged.c:collapse_file
  - mm/memory-failure.c:truncate_error_page
  - fs/splice.c:page_cache_pipe_buf_steal
  - fs/buffer.c:block_invalidatepage
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
```
**Symbols:**

```
ffff8000102ae1d8-ffff8000102ae274: try_to_release_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int try_to_release_page(struct page *page, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (c04db750)
Location: mm/filemap.c:3471
Inline: True
Direct callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_page
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_page_list
  - mm/migrate.c:move_to_new_page
  - fs/splice.c:page_cache_pipe_buf_steal
  - fs/buffer.c:block_invalidatepage
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
```
**Symbols:**

```
c04db750-c04db7d8: try_to_release_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int try_to_release_page(struct page *page, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (c000000000362f60)
Location: mm/filemap.c:3471
Inline: False
Direct callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_page
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_page_list
  - mm/migrate.c:move_to_new_page
  - mm/khugepaged.c:collapse_file
  - mm/memory-failure.c:truncate_error_page
  - fs/splice.c:page_cache_pipe_buf_steal
  - fs/buffer.c:block_invalidatepage
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
```
**Symbols:**

```
c000000000362f60-c000000000363048: try_to_release_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int try_to_release_page(struct page *page, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffe0001d4e14)
Location: mm/filemap.c:3471
Inline: True
Direct callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_page
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_page_list
  - mm/migrate.c:move_to_new_page
  - fs/splice.c:page_cache_pipe_buf_steal
  - fs/buffer.c:block_invalidatepage
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
```
**Symbols:**

```
ffffffe0001d4e14-ffffffe0001d4ea2: try_to_release_page (STB_GLOBAL)
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
int try_to_release_page(struct page *page, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81219c80)
Location: mm/filemap.c:3471
Inline: True
Direct callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_page
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_page_list
  - mm/migrate.c:move_to_new_page
  - mm/khugepaged.c:collapse_file
  - mm/memory-failure.c:truncate_error_page
  - fs/splice.c:page_cache_pipe_buf_steal
  - fs/buffer.c:block_invalidatepage
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
```
**Symbols:**

```
ffffffff81219c80-ffffffff81219cdf: try_to_release_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int try_to_release_page(struct page *page, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8120ce90)
Location: mm/filemap.c:3471
Inline: True
Direct callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_page
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_page_list
  - mm/migrate.c:move_to_new_page
  - mm/khugepaged.c:collapse_file
  - mm/memory-failure.c:truncate_error_page
  - fs/splice.c:page_cache_pipe_buf_steal
  - fs/buffer.c:block_invalidatepage
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
```
**Symbols:**

```
ffffffff8120ce90-ffffffff8120ceef: try_to_release_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int try_to_release_page(struct page *page, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81217a20)
Location: mm/filemap.c:3471
Inline: True
Direct callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_page
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_page_list
  - mm/migrate.c:move_to_new_page
  - mm/khugepaged.c:collapse_file
  - mm/memory-failure.c:truncate_error_page
  - fs/splice.c:page_cache_pipe_buf_steal
  - fs/buffer.c:block_invalidatepage
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
```
**Symbols:**

```
ffffffff81217a20-ffffffff81217a7f: try_to_release_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int try_to_release_page(struct page *page, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81226ae0)
Location: mm/filemap.c:3471
Inline: True
Direct callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_page
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_page_list
  - mm/migrate.c:move_to_new_page
  - mm/khugepaged.c:collapse_file
  - mm/memory-failure.c:truncate_error_page
  - fs/splice.c:page_cache_pipe_buf_steal
  - fs/buffer.c:block_invalidatepage
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
```
**Symbols:**

```
ffffffff81226ae0-ffffffff81226b3f: try_to_release_page (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>gfp_t gfp</code>
</li>
<li>
<b>Param removed. </b>
<code>gfp_t gfp_mask</code>
</li>
</ul>
</details>
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
