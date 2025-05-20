# Function: <code>page_cache_async_readahead</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void page_cache_async_readahead(struct address_space *mapping, struct file_ra_state *ra, struct file *filp, struct page *page, long unsigned int offset, long unsigned int req_size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/readahead.c (ffffffff8119c250)
Location: mm/readahead.c:514
Inline: True
Direct callers:
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:filemap_fault
  - fs/splice.c:__generic_file_splice_read
```
**Symbols:**

```
ffffffff8119c250-ffffffff8119c2bd: page_cache_async_readahead (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void page_cache_async_readahead(struct address_space *mapping, struct file_ra_state *ra, struct file *filp, struct page *page, long unsigned int offset, long unsigned int req_size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/readahead.c (ffffffff811b1450)
Location: mm/readahead.c:513
Inline: True
Direct callers:
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_read_iter
  - fs/splice.c:__generic_file_splice_read
```
**Symbols:**

```
ffffffff811b1450-ffffffff811b14bd: page_cache_async_readahead (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void page_cache_async_readahead(struct address_space *mapping, struct file_ra_state *ra, struct file *filp, struct page *page, long unsigned int offset, long unsigned int req_size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/readahead.c (ffffffff811c1a80)
Location: mm/readahead.c:530
Inline: True
Direct callers:
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_read_iter
```
**Symbols:**

```
ffffffff811c1a80-ffffffff811c1aed: page_cache_async_readahead (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void page_cache_async_readahead(struct address_space *mapping, struct file_ra_state *ra, struct file *filp, struct page *page, long unsigned int offset, long unsigned int req_size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/readahead.c (ffffffff811c9d20)
Location: mm/readahead.c:530
Inline: True
Direct callers:
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_read_iter
```
**Symbols:**

```
ffffffff811c9d20-ffffffff811c9d8c: page_cache_async_readahead (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void page_cache_async_readahead(struct address_space *mapping, struct file_ra_state *ra, struct file *filp, struct page *page, long unsigned int offset, long unsigned int req_size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/readahead.c (ffffffff811debe0)
Location: mm/readahead.c:530
Inline: True
Direct callers:
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_read_iter
```
**Symbols:**

```
ffffffff811debe0-ffffffff811dec5c: page_cache_async_readahead (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void page_cache_async_readahead(struct address_space *mapping, struct file_ra_state *ra, struct file *filp, struct page *page, long unsigned int offset, long unsigned int req_size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/readahead.c (ffffffff81200350)
Location: mm/readahead.c:543
Inline: True
Direct callers:
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
```
**Symbols:**

```
ffffffff81200350-ffffffff812003d6: page_cache_async_readahead (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void page_cache_async_readahead(struct address_space *mapping, struct file_ra_state *ra, struct file *filp, struct page *page, long unsigned int offset, long unsigned int req_size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/readahead.c (ffffffff81212c50)
Location: mm/readahead.c:544
Inline: True
Direct callers:
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
```
**Symbols:**

```
ffffffff81212c50-ffffffff81212d0d: page_cache_async_readahead (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void page_cache_async_readahead(struct address_space *mapping, struct file_ra_state *ra, struct file *filp, struct page *page, long unsigned int offset, long unsigned int req_size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/readahead.c (ffffffff81222620)
Location: mm/readahead.c:547
Inline: True
Direct callers:
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
```
**Symbols:**

```
ffffffff81222620-ffffffff812226f2: page_cache_async_readahead (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void page_cache_async_readahead(struct address_space *mapping, struct file_ra_state *ra, struct file *filp, struct page *page, long unsigned int offset, long unsigned int req_size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/readahead.c (ffffffff812300d0)
Location: mm/readahead.c:547
Inline: True
Direct callers:
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
```
**Symbols:**

```
ffffffff812300d0-ffffffff812301a2: page_cache_async_readahead (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void page_cache_async_readahead(struct address_space *mapping, struct file_ra_state *ra, struct file *filp, struct page *page, long unsigned int index, long unsigned int req_count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/readahead.c (ffffffff8125d310)
Location: mm/readahead.c:604
Inline: True
Direct callers:
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - fs/verity/enable.c:read_file_data_page
```
**Symbols:**

```
ffffffff8125d310-ffffffff8125d3e2: page_cache_async_readahead (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8125df6f)
Location: include/linux/pagemap.h:856
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read_get_pages
```
```
In fs/verity/enable.c (ffffffff813a79b6)
Location: include/linux/pagemap.h:856
Inline: True
Inline callers:
  - fs/verity/enable.c:read_file_data_page
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81260c3f)
Location: include/linux/pagemap.h:898
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_get_pages
```
```
In fs/verity/enable.c (ffffffff813aea14)
Location: include/linux/pagemap.h:898
Inline: True
Inline callers:
  - fs/verity/enable.c:read_file_data_page
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8129d6bc)
Location: include/linux/pagemap.h:901
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_get_pages
```
```
In fs/verity/enable.c (ffffffff813fe5b1)
Location: include/linux/pagemap.h:901
Inline: True
Inline callers:
  - fs/verity/enable.c:read_file_data_page
```
</details>
</li>
<li>
In <code>5.19</code>: Absent ⚠️
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
void page_cache_async_readahead(struct address_space *mapping, struct file_ra_state *ra, struct file *filp, struct page *page, long unsigned int offset, long unsigned int req_size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/readahead.c (ffff8000102bf920)
Location: mm/readahead.c:547
Inline: True
Direct callers:
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
```
**Symbols:**

```
ffff8000102bf920-ffff8000102bfa18: page_cache_async_readahead (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void page_cache_async_readahead(struct address_space *mapping, struct file_ra_state *ra, struct file *filp, struct page *page, long unsigned int offset, long unsigned int req_size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/readahead.c (c04eb3e0)
Location: mm/readahead.c:547
Inline: True
Direct callers:
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
```
**Symbols:**

```
c04eb3e0-c04eb4d8: page_cache_async_readahead (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void page_cache_async_readahead(struct address_space *mapping, struct file_ra_state *ra, struct file *filp, struct page *page, long unsigned int offset, long unsigned int req_size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/readahead.c (c0000000003787d0)
Location: mm/readahead.c:547
Inline: True
Direct callers:
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
```
**Symbols:**

```
c0000000003787d0-c000000000378978: page_cache_async_readahead (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void page_cache_async_readahead(struct address_space *mapping, struct file_ra_state *ra, struct file *filp, struct page *page, long unsigned int offset, long unsigned int req_size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/readahead.c (ffffffe0001e1988)
Location: mm/readahead.c:547
Inline: True
Direct callers:
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
```
**Symbols:**

```
ffffffe0001e1988-ffffffe0001e1a4c: page_cache_async_readahead (STB_GLOBAL)
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
void page_cache_async_readahead(struct address_space *mapping, struct file_ra_state *ra, struct file *filp, struct page *page, long unsigned int offset, long unsigned int req_size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/readahead.c (ffffffff81228720)
Location: mm/readahead.c:547
Inline: True
Direct callers:
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
```
**Symbols:**

```
ffffffff81228720-ffffffff812287f2: page_cache_async_readahead (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void page_cache_async_readahead(struct address_space *mapping, struct file_ra_state *ra, struct file *filp, struct page *page, long unsigned int offset, long unsigned int req_size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/readahead.c (ffffffff8121b860)
Location: mm/readahead.c:547
Inline: True
Direct callers:
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
```
**Symbols:**

```
ffffffff8121b860-ffffffff8121b932: page_cache_async_readahead (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void page_cache_async_readahead(struct address_space *mapping, struct file_ra_state *ra, struct file *filp, struct page *page, long unsigned int offset, long unsigned int req_size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/readahead.c (ffffffff812264c0)
Location: mm/readahead.c:547
Inline: True
Direct callers:
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
```
**Symbols:**

```
ffffffff812264c0-ffffffff81226592: page_cache_async_readahead (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void page_cache_async_readahead(struct address_space *mapping, struct file_ra_state *ra, struct file *filp, struct page *page, long unsigned int offset, long unsigned int req_size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/readahead.c (ffffffff812357f0)
Location: mm/readahead.c:547
Inline: True
Direct callers:
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
```
**Symbols:**

```
ffffffff812357f0-ffffffff812358c2: page_cache_async_readahead (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int index</code>
</li>
<li>
<b>Param added. </b>
<code>long unsigned int req_count</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int offset</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int req_size</code>
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
