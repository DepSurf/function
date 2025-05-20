# Function: <code>page_cache_sync_ra</code>

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
<summary>In <code>5.11</code>: ✅</summary>

```c
void page_cache_sync_ra(struct readahead_control *ractl, struct file_ra_state *ra, long unsigned int req_count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/readahead.c (ffffffff81267900)
Location: mm/readahead.c:552
Inline: False
Direct callers:
  - mm/filemap.c:do_sync_mmap_readahead
  - mm/filemap.c:generic_file_buffered_read_get_pages
  - mm/khugepaged.c:page_cache_sync_readahead
  - fs/verity/enable.c:read_file_data_page
  - fs/ext4/dir.c:ext4_readdir
```
**Symbols:**

```
ffffffff81267900-ffffffff812679de: page_cache_sync_ra (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void page_cache_sync_ra(struct readahead_control *ractl, long unsigned int req_count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/readahead.c (ffffffff8126c510)
Location: mm/readahead.c:553
Inline: False
Direct callers:
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_get_pages
  - mm/khugepaged.c:page_cache_sync_readahead
  - fs/verity/enable.c:read_file_data_page
  - fs/ext4/dir.c:ext4_readdir
```
**Symbols:**

```
ffffffff8126c510-ffffffff8126c5e5: page_cache_sync_ra (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void page_cache_sync_ra(struct readahead_control *ractl, long unsigned int req_count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/readahead.c (ffffffff812a9230)
Location: mm/readahead.c:555
Inline: False
Direct callers:
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_get_pages
  - mm/khugepaged.c:page_cache_sync_readahead
  - fs/verity/enable.c:read_file_data_page
  - fs/ext4/dir.c:ext4_readdir
```
**Symbols:**

```
ffffffff812a9230-ffffffff812a9305: page_cache_sync_ra (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void page_cache_sync_ra(struct readahead_control *ractl, long unsigned int req_count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/readahead.c (ffffffff813023a0)
Location: mm/readahead.c:675
Inline: False
Direct callers:
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_get_pages
  - mm/khugepaged.c:page_cache_sync_readahead
  - fs/verity/enable.c:read_file_data_page
  - fs/ext4/dir.c:ext4_readdir
```
**Symbols:**

```
ffffffff813023a0-ffffffff81302437: page_cache_sync_ra (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void page_cache_sync_ra(struct readahead_control *ractl, long unsigned int req_count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/readahead.c (ffffffff8136cb40)
Location: mm/readahead.c:685
Inline: False
Direct callers:
  - mm/filemap.c:do_sync_mmap_readahead
  - mm/filemap.c:filemap_get_pages
  - mm/khugepaged.c:page_cache_sync_readahead
  - fs/verity/enable.c:build_merkle_tree_level
```
**Symbols:**

```
ffffffff8136cb40-ffffffff8136cbd7: page_cache_sync_ra (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void page_cache_sync_ra(struct readahead_control *ractl, long unsigned int req_count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/readahead.c (ffffffff8139eda0)
Location: mm/readahead.c:684
Inline: False
Direct callers:
  - mm/filemap.c:do_sync_mmap_readahead
  - mm/filemap.c:filemap_get_pages
  - mm/khugepaged.c:page_cache_sync_readahead
```
**Symbols:**

```
ffffffff8139eda0-ffffffff8139ee37: page_cache_sync_ra (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void page_cache_sync_ra(struct readahead_control *ractl, long unsigned int req_count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/readahead.c (ffffffff813c8a00)
Location: mm/readahead.c:669
Inline: False
Direct callers:
  - mm/filemap.c:do_sync_mmap_readahead
  - mm/filemap.c:filemap_get_pages
  - mm/khugepaged.c:page_cache_sync_readahead
```
**Symbols:**

```
ffffffff813c8a00-ffffffff813c8a97: page_cache_sync_ra (STB_GLOBAL)
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
<code>ractl, ra, req_count</code> ➡️ <code>ractl, req_count</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
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
