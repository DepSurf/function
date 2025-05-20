# Function: <code>add_to_page_cache_lru</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int add_to_page_cache_lru(struct page *page, struct address_space *mapping, long unsigned int offset, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8118df20)
Location: mm/filemap.c:679
Inline: False
Direct callers:
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:filemap_fault
  - mm/readahead.c:read_cache_pages
  - mm/readahead.c:__do_page_cache_readahead
  - fs/splice.c:__generic_file_splice_read
  - fs/mpage.c:mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
**Symbols:**

```
ffffffff8118df20-ffffffff8118dfb0: add_to_page_cache_lru (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int add_to_page_cache_lru(struct page *page, struct address_space *mapping, long unsigned int offset, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811a0fb0)
Location: mm/filemap.c:715
Inline: False
Direct callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:pagecache_get_page
  - mm/readahead.c:__do_page_cache_readahead
  - mm/readahead.c:read_cache_pages
  - fs/splice.c:__generic_file_splice_read
  - fs/mpage.c:mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
**Symbols:**

```
ffffffff811a0fb0-ffffffff811a108e: add_to_page_cache_lru (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int add_to_page_cache_lru(struct page *page, struct address_space *mapping, long unsigned int offset, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811b0bb0)
Location: mm/filemap.c:679
Inline: False
Direct callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:pagecache_get_page
  - mm/readahead.c:__do_page_cache_readahead
  - mm/readahead.c:read_cache_pages
  - fs/mpage.c:mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
**Symbols:**

```
ffffffff811b0bb0-ffffffff811b0c8e: add_to_page_cache_lru (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int add_to_page_cache_lru(struct page *page, struct address_space *mapping, long unsigned int offset, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811b80e0)
Location: mm/filemap.c:797
Inline: False
Direct callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:pagecache_get_page
  - mm/readahead.c:__do_page_cache_readahead
  - mm/readahead.c:read_cache_pages
  - fs/mpage.c:mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
**Symbols:**

```
ffffffff811b80e0-ffffffff811b81be: add_to_page_cache_lru (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int add_to_page_cache_lru(struct page *page, struct address_space *mapping, long unsigned int offset, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811cc7d0)
Location: mm/filemap.c:898
Inline: False
Direct callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:pagecache_get_page
  - mm/readahead.c:__do_page_cache_readahead
  - mm/readahead.c:read_cache_pages
  - fs/mpage.c:mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
**Symbols:**

```
ffffffff811cc7d0-ffffffff811cc8ae: add_to_page_cache_lru (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int add_to_page_cache_lru(struct page *page, struct address_space *mapping, long unsigned int offset, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811ed5b0)
Location: mm/filemap.c:898
Inline: False
Direct callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:pagecache_get_page
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_cache_pages
  - fs/mpage.c:mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
**Symbols:**

```
ffffffff811ed5b0-ffffffff811ed690: add_to_page_cache_lru (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int add_to_page_cache_lru(struct page *page, struct address_space *mapping, long unsigned int offset, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811feb80)
Location: mm/filemap.c:879
Inline: False
Direct callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:pagecache_get_page
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_cache_pages
  - fs/mpage.c:mpage_readpages
  - fs/iomap.c:iomap_readpages_actor
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
**Symbols:**

```
ffffffff811feb80-ffffffff811fec42: add_to_page_cache_lru (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int add_to_page_cache_lru(struct page *page, struct address_space *mapping, long unsigned int offset, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81215e80)
Location: mm/filemap.c:927
Inline: False
Direct callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:pagecache_get_page
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_cache_pages
  - fs/mpage.c:mpage_readpages
  - fs/iomap/buffered-io.c:iomap_readpages_actor
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
**Symbols:**

```
ffffffff81215e80-ffffffff81215f48: add_to_page_cache_lru (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int add_to_page_cache_lru(struct page *page, struct address_space *mapping, long unsigned int offset, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81223780)
Location: mm/filemap.c:936
Inline: False
Direct callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:pagecache_get_page
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_cache_pages
  - fs/mpage.c:mpage_readpages
  - fs/iomap/buffered-io.c:iomap_readpages_actor
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
**Symbols:**

```
ffffffff81223780-ffffffff81223848: add_to_page_cache_lru (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int add_to_page_cache_lru(struct page *page, struct address_space *mapping, long unsigned int offset, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81250e50)
Location: mm/filemap.c:911
Inline: False
Direct callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:pagecache_get_page
  - mm/readahead.c:page_cache_readahead_unbounded
  - mm/readahead.c:read_cache_pages
```
**Symbols:**

```
ffffffff81250e50-ffffffff81250f18: add_to_page_cache_lru (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int add_to_page_cache_lru(struct page *page, struct address_space *mapping, long unsigned int offset, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8125b190)
Location: mm/filemap.c:936
Inline: False
Direct callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:generic_file_buffered_read_get_pages
  - mm/filemap.c:pagecache_get_page
  - mm/readahead.c:page_cache_ra_unbounded
  - mm/readahead.c:read_cache_pages
```
**Symbols:**

```
ffffffff8125b190-ffffffff8125b258: add_to_page_cache_lru (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int add_to_page_cache_lru(struct page *page, struct address_space *mapping, long unsigned int offset, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8125ee20)
Location: mm/filemap.c:960
Inline: False
Direct callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_get_pages
  - mm/filemap.c:pagecache_get_page
  - mm/readahead.c:readahead_expand
  - mm/readahead.c:readahead_expand
  - mm/readahead.c:page_cache_ra_unbounded
  - mm/readahead.c:read_cache_pages
```
**Symbols:**

```
ffffffff8125ee20-ffffffff8125eee8: add_to_page_cache_lru (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int add_to_page_cache_lru(struct page *page, struct address_space *mapping, long unsigned int offset, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8129c230)
Location: mm/filemap.c:977
Inline: False
Direct callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_get_pages
  - mm/filemap.c:pagecache_get_page
  - mm/readahead.c:readahead_expand
  - mm/readahead.c:readahead_expand
  - mm/readahead.c:page_cache_ra_unbounded
  - mm/readahead.c:read_cache_pages
  - mm/secretmem.c:secretmem_fault
```
**Symbols:**

```
ffffffff8129c230-ffffffff8129c2f8: add_to_page_cache_lru (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int add_to_page_cache_lru(struct page *page, struct address_space *mapping, long unsigned int index, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/folio-compat.c (ffffffff81300fc0)
Location: mm/folio-compat.c:113
Inline: False
Direct callers:
  - mm/readahead.c:readahead_expand
  - mm/readahead.c:readahead_expand
  - mm/secretmem.c:secretmem_fault
```
**Symbols:**

```
ffffffff81300fc0-ffffffff81301034: add_to_page_cache_lru (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int add_to_page_cache_lru(struct page *page, struct address_space *mapping, long unsigned int index, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/folio-compat.c (ffffffff8136b800)
Location: mm/folio-compat.c:85
Inline: False
Direct callers:
  - mm/readahead.c:readahead_expand
  - mm/readahead.c:readahead_expand
  - mm/secretmem.c:secretmem_fault
```
**Symbols:**

```
ffffffff8136b800-ffffffff8136b874: add_to_page_cache_lru (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int add_to_page_cache_lru(struct page *page, struct address_space *mapping, long unsigned int index, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/folio-compat.c (ffffffff8139da20)
Location: mm/folio-compat.c:86
Inline: False
Direct callers:
  - mm/secretmem.c:secretmem_fault
  - fs/squashfs/block.c:squashfs_bio_read_cached
  - fs/squashfs/block.c:squashfs_bio_read_cached
```
**Symbols:**

```
ffffffff8139da20-ffffffff8139daab: add_to_page_cache_lru (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int add_to_page_cache_lru(struct page *page, struct address_space *mapping, long unsigned int index, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/folio-compat.c (ffffffff813c7790)
Location: mm/folio-compat.c:80
Inline: False
Direct callers:
  - fs/squashfs/block.c:squashfs_bio_read_cached
  - fs/squashfs/block.c:squashfs_bio_read_cached
```
**Symbols:**

```
ffffffff813c7790-ffffffff813c7818: add_to_page_cache_lru (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int add_to_page_cache_lru(struct page *page, struct address_space *mapping, long unsigned int offset, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffff8000102b1140)
Location: mm/filemap.c:936
Inline: False
Direct callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:pagecache_get_page
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_cache_pages
  - fs/mpage.c:mpage_readpages
  - fs/iomap/buffered-io.c:iomap_readpages_actor
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
**Symbols:**

```
ffff8000102b1140-ffff8000102b1250: add_to_page_cache_lru (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int add_to_page_cache_lru(struct page *page, struct address_space *mapping, long unsigned int offset, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (c04dda2c)
Location: mm/filemap.c:936
Inline: False
Direct callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:pagecache_get_page
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_cache_pages
  - fs/mpage.c:mpage_readpages
  - fs/iomap/buffered-io.c:iomap_readpages_actor
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
**Symbols:**

```
c04dda2c-c04ddb58: add_to_page_cache_lru (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int add_to_page_cache_lru(struct page *page, struct address_space *mapping, long unsigned int offset, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (c000000000366730)
Location: mm/filemap.c:936
Inline: False
Direct callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:pagecache_get_page
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_cache_pages
  - fs/mpage.c:mpage_readpages
  - fs/iomap/buffered-io.c:iomap_readpages_actor
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
**Symbols:**

```
c000000000366730-c000000000366878: add_to_page_cache_lru (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int add_to_page_cache_lru(struct page *page, struct address_space *mapping, long unsigned int offset, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffe0001d6998)
Location: mm/filemap.c:936
Inline: False
Direct callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:pagecache_get_page
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_cache_pages
  - fs/mpage.c:mpage_readpages
  - fs/iomap/buffered-io.c:iomap_readpages_actor
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
**Symbols:**

```
ffffffe0001d6998-ffffffe0001d6a54: add_to_page_cache_lru (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int add_to_page_cache_lru(struct page *page, struct address_space *mapping, long unsigned int offset, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8121bdd0)
Location: mm/filemap.c:936
Inline: False
Direct callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:pagecache_get_page
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_cache_pages
  - fs/mpage.c:mpage_readpages
  - fs/iomap/buffered-io.c:iomap_readpages_actor
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
**Symbols:**

```
ffffffff8121bdd0-ffffffff8121be98: add_to_page_cache_lru (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int add_to_page_cache_lru(struct page *page, struct address_space *mapping, long unsigned int offset, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8120efc0)
Location: mm/filemap.c:936
Inline: False
Direct callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:pagecache_get_page
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_cache_pages
  - fs/mpage.c:mpage_readpages
  - fs/iomap/buffered-io.c:iomap_readpages_actor
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
**Symbols:**

```
ffffffff8120efc0-ffffffff8120f088: add_to_page_cache_lru (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int add_to_page_cache_lru(struct page *page, struct address_space *mapping, long unsigned int offset, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81219b70)
Location: mm/filemap.c:936
Inline: False
Direct callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:pagecache_get_page
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_cache_pages
  - fs/mpage.c:mpage_readpages
  - fs/iomap/buffered-io.c:iomap_readpages_actor
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
**Symbols:**

```
ffffffff81219b70-ffffffff81219c38: add_to_page_cache_lru (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int add_to_page_cache_lru(struct page *page, struct address_space *mapping, long unsigned int offset, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81228c70)
Location: mm/filemap.c:936
Inline: False
Direct callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:pagecache_get_page
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_cache_pages
  - fs/mpage.c:mpage_readpages
  - fs/iomap/buffered-io.c:iomap_readpages_actor
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
**Symbols:**

```
ffffffff81228c70-ffffffff81228d38: add_to_page_cache_lru (STB_GLOBAL)
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
<code>long unsigned int index</code>
</li>
<li>
<b>Param added. </b>
<code>gfp_t gfp</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int offset</code>
</li>
<li>
<b>Param removed. </b>
<code>gfp_t gfp_mask</code>
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
