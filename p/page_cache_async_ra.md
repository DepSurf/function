# Function: <code>page_cache_async_ra</code>

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
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void page_cache_async_ra(struct readahead_control *ractl, struct file_ra_state *ra, struct page *page, long unsigned int req_count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/readahead.c (ffffffff812676b0)
Location: mm/readahead.c:581
Inline: True
Direct callers:
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read_get_pages
  - fs/verity/enable.c:read_file_data_page
```
**Symbols:**

```
ffffffff812676b0-ffffffff8126777b: page_cache_async_ra (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void page_cache_async_ra(struct readahead_control *ractl, struct page *page, long unsigned int req_count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/readahead.c (ffffffff8126c2c0)
Location: mm/readahead.c:582
Inline: True
Direct callers:
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_get_pages
  - fs/verity/enable.c:read_file_data_page
```
**Symbols:**

```
ffffffff8126c2c0-ffffffff8126c385: page_cache_async_ra (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void page_cache_async_ra(struct readahead_control *ractl, struct page *page, long unsigned int req_count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/readahead.c (ffffffff812a8fd0)
Location: mm/readahead.c:584
Inline: True
Direct callers:
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_get_pages
  - fs/verity/enable.c:read_file_data_page
```
**Symbols:**

```
ffffffff812a8fd0-ffffffff812a9095: page_cache_async_ra (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void page_cache_async_ra(struct readahead_control *ractl, struct folio *folio, long unsigned int req_count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/readahead.c (ffffffff81302440)
Location: mm/readahead.c:703
Inline: True
Direct callers:
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_get_pages
  - fs/verity/enable.c:read_file_data_page
```
**Symbols:**

```
ffffffff81302440-ffffffff813024b9: page_cache_async_ra (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void page_cache_async_ra(struct readahead_control *ractl, struct folio *folio, long unsigned int req_count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/readahead.c (ffffffff8136cbf0)
Location: mm/readahead.c:713
Inline: True
Direct callers:
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_get_pages
  - fs/verity/enable.c:build_merkle_tree_level
```
**Symbols:**

```
ffffffff8136cbf0-ffffffff8136cc69: page_cache_async_ra (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void page_cache_async_ra(struct readahead_control *ractl, struct folio *folio, long unsigned int req_count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/readahead.c (ffffffff8139ee50)
Location: mm/readahead.c:712
Inline: True
Direct callers:
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_get_pages
```
**Symbols:**

```
ffffffff8139ee50-ffffffff8139eec9: page_cache_async_ra (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void page_cache_async_ra(struct readahead_control *ractl, struct folio *folio, long unsigned int req_count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/readahead.c (ffffffff813c8ab0)
Location: mm/readahead.c:697
Inline: True
Direct callers:
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_get_pages
```
**Symbols:**

```
ffffffff813c8ab0-ffffffff813c8b28: page_cache_async_ra (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct file_ra_state *ra</code>
</li>
<li>
<b>Param reordered. </b>
<code>ractl, ra, page, req_count</code> ➡️ <code>ractl, page, req_count</code>
</li>
</ul>
</details>
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
<code>struct folio *folio</code>
</li>
<li>
<b>Param removed. </b>
<code>struct page *page</code>
</li>
</ul>
</details>
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
