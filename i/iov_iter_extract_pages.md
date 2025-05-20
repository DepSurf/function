# Function: <code>iov_iter_extract_pages</code>

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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
ssize_t iov_iter_extract_pages(struct iov_iter *i, struct page ***pages, size_t maxsize, unsigned int maxpages, iov_iter_extraction_t extraction_flags, size_t *offset0);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/iov_iter.c (0)
Location: lib/iov_iter.c:1819
Inline: False
Direct callers:
  - fs/direct-io.c:do_direct_IO
  - block/bio.c:__bio_iov_iter_get_pages
  - block/blk-map.c:bio_map_user_iov
  - net/core/skbuff.c:skb_splice_from_iter
```
**Symbols:**

```
ffffffff820f87ed-ffffffff820f8854: iov_iter_extract_pages.cold (STB_LOCAL)
ffffffff81814490-ffffffff8181493f: iov_iter_extract_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
ssize_t iov_iter_extract_pages(struct iov_iter *i, struct page ***pages, size_t maxsize, unsigned int maxpages, iov_iter_extraction_t extraction_flags, size_t *offset0);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/iov_iter.c (0)
Location: lib/iov_iter.c:1632
Inline: False
Direct callers:
  - fs/direct-io.c:do_direct_IO
  - block/bio.c:__bio_iov_iter_get_pages
  - block/blk-map.c:bio_map_user_iov
  - block/bio-integrity.c:bio_integrity_map_user
  - block/bio-integrity.c:bio_integrity_map_user
  - net/core/skbuff.c:skb_splice_from_iter
```
**Symbols:**

```
ffffffff821d6381-ffffffff821d63cf: iov_iter_extract_pages.cold (STB_LOCAL)
ffffffff81859490-ffffffff818599c1: iov_iter_extract_pages (STB_GLOBAL)
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
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
