# Function: <code>__bio_add_page</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __bio_add_page(struct bio *bio, struct page *page, unsigned int len, unsigned int off);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff81478d40)
Location: block/bio.c:866
Inline: False
Direct callers:
  - fs/iomap.c:iomap_dio_zero
  - block/bio.c:bio_add_page
```
**Symbols:**

```
ffffffff81478d40-ffffffff81478d80: __bio_add_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __bio_add_page(struct bio *bio, struct page *page, unsigned int len, unsigned int off);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff81496fa0)
Location: block/bio.c:792
Inline: False
Direct callers:
  - fs/iomap.c:iomap_dio_zero
  - fs/iomap.c:iomap_read_page_sync
  - fs/iomap.c:iomap_readpage_actor
  - block/bio.c:bio_add_page
```
**Symbols:**

```
ffffffff81496fa0-ffffffff81496fe0: __bio_add_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __bio_add_page(struct bio *bio, struct page *page, unsigned int len, unsigned int off);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814c4960)
Location: block/bio.c:795
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_read_page_sync
  - fs/iomap/direct-io.c:iomap_dio_zero
  - block/bio.c:bio_iov_iter_get_pages
  - block/bio.c:bio_add_page
```
**Symbols:**

```
ffffffff814c4960-ffffffff814c49ac: __bio_add_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __bio_add_page(struct bio *bio, struct page *page, unsigned int len, unsigned int off);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814de610)
Location: block/bio.c:831
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_read_page_sync
  - fs/iomap/direct-io.c:iomap_dio_zero
  - block/bio.c:bio_iov_iter_get_pages
  - block/bio.c:bio_add_page
```
**Symbols:**

```
ffffffff814de610-ffffffff814de684: __bio_add_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __bio_add_page(struct bio *bio, struct page *page, unsigned int len, unsigned int off);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8153dbb0)
Location: block/bio.c:903
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_read_page_sync
  - fs/iomap/direct-io.c:iomap_dio_zero
  - block/bio.c:__bio_iov_iter_get_pages
  - block/bio.c:bio_add_page
```
**Symbols:**

```
ffffffff8153dbb0-ffffffff8153dc24: __bio_add_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __bio_add_page(struct bio *bio, struct page *page, unsigned int len, unsigned int off);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8155a730)
Location: block/bio.c:903
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_read_page_sync
  - fs/iomap/direct-io.c:iomap_dio_zero
  - block/bio.c:__bio_iov_iter_get_pages
  - block/bio.c:bio_add_page
```
**Symbols:**

```
ffffffff8155a730-ffffffff8155a7a4: __bio_add_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __bio_add_page(struct bio *bio, struct page *page, unsigned int len, unsigned int off);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff81562f00)
Location: block/bio.c:892
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_read_page_sync
  - fs/iomap/direct-io.c:iomap_dio_zero
  - block/bio.c:bio_add_page
```
**Symbols:**

```
ffffffff81562f00-ffffffff81562f7d: __bio_add_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __bio_add_page(struct bio *bio, struct page *page, unsigned int len, unsigned int off);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff815c62d0)
Location: block/bio.c:975
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_add_to_ioend
  - fs/iomap/buffered-io.c:iomap_read_page_sync
  - fs/iomap/buffered-io.c:iomap_readpage_iter
  - fs/iomap/direct-io.c:iomap_dio_zero
  - block/bio.c:__bio_iov_iter_get_pages
  - block/bio.c:bio_add_page
```
**Symbols:**

```
ffffffff815c62d0-ffffffff815c634d: __bio_add_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __bio_add_page(struct bio *bio, struct page *page, unsigned int len, unsigned int off);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff81670f70)
Location: block/bio.c:1054
Inline: False
Direct callers:
  - fs/iomap/direct-io.c:iomap_dio_zero
  - block/bio.c:bio_iov_iter_get_pages
  - block/bio.c:bio_add_folio
```
**Symbols:**

```
ffffffff81670f70-ffffffff8167103d: __bio_add_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __bio_add_page(struct bio *bio, struct page *page, unsigned int len, unsigned int off);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8172c750)
Location: block/bio.c:1109
Inline: False
Direct callers:
  - fs/iomap/direct-io.c:iomap_dio_zero
  - block/bio.c:__bio_iov_iter_get_pages
  - block/bio.c:bio_add_folio
```
**Symbols:**

```
ffffffff8172c750-ffffffff8172c7b0: __bio_add_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void __bio_add_page(struct bio *bio, struct page *page, unsigned int len, unsigned int off);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8176bae4)
Location: block/bio.c:1071
Inline: True
Inline callers:
  - block/bio.c:bio_add_folio_nofail
Direct callers:
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:swap_readpage_bdev_sync
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:swap_writepage_bdev_sync
  - fs/buffer.c:submit_bh_wbc
  - fs/iomap/direct-io.c:iomap_dio_zero
  - fs/squashfs/block.c:squashfs_bio_read
  - block/bio.c:__bio_iov_iter_get_pages
  - block/bio.c:bio_add_page
  - drivers/md/md.c:sync_page_io
  - drivers/md/md.c:md_super_write
```
**Symbols:**

```
ffffffff81768ad0-ffffffff81768b29: __bio_add_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void __bio_add_page(struct bio *bio, struct page *page, unsigned int len, unsigned int off);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff817adf84)
Location: block/bio.c:1072
Inline: True
Inline callers:
  - block/bio.c:bio_add_folio_nofail
Direct callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/iomap/direct-io.c:iomap_dio_zero
  - fs/squashfs/block.c:squashfs_bio_read
  - block/bio.c:__bio_iov_iter_get_pages
  - drivers/md/md.c:sync_page_io
  - drivers/md/md.c:md_super_write
```
**Symbols:**

```
ffffffff817aa9c0-ffffffff817aaa19: __bio_add_page (STB_GLOBAL)
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
void __bio_add_page(struct bio *bio, struct page *page, unsigned int len, unsigned int off);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffff8000105d9e48)
Location: block/bio.c:831
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_read_page_sync
  - fs/iomap/direct-io.c:iomap_dio_zero
  - block/bio.c:bio_iov_iter_get_pages
  - block/bio.c:bio_add_page
```
**Symbols:**

```
ffff8000105d9e48-ffff8000105d9f14: __bio_add_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __bio_add_page(struct bio *bio, struct page *page, unsigned int len, unsigned int off);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (c0787430)
Location: block/bio.c:831
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_read_page_sync
  - fs/iomap/direct-io.c:iomap_dio_zero
  - block/bio.c:bio_iov_iter_get_pages
  - block/bio.c:bio_add_page
```
**Symbols:**

```
c0787430-c0787548: __bio_add_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __bio_add_page(struct bio *bio, struct page *page, unsigned int len, unsigned int off);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (c00000000076a270)
Location: block/bio.c:831
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_read_page_sync
  - fs/iomap/direct-io.c:iomap_dio_zero
  - block/bio.c:bio_iov_iter_get_pages
  - block/bio.c:bio_add_page
```
**Symbols:**

```
c00000000076a270-c00000000076a368: __bio_add_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __bio_add_page(struct bio *bio, struct page *page, unsigned int len, unsigned int off);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffe00041d812)
Location: block/bio.c:831
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_read_page_sync
  - fs/iomap/direct-io.c:iomap_dio_zero
  - block/bio.c:bio_iov_iter_get_pages
  - block/bio.c:bio_add_page
```
**Symbols:**

```
ffffffe00041d812-ffffffe00041d8c6: __bio_add_page (STB_GLOBAL)
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
void __bio_add_page(struct bio *bio, struct page *page, unsigned int len, unsigned int off);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814d6bf0)
Location: block/bio.c:831
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_read_page_sync
  - fs/iomap/direct-io.c:iomap_dio_zero
  - block/bio.c:bio_iov_iter_get_pages
  - block/bio.c:bio_add_page
```
**Symbols:**

```
ffffffff814d6bf0-ffffffff814d6c64: __bio_add_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __bio_add_page(struct bio *bio, struct page *page, unsigned int len, unsigned int off);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814c75b0)
Location: block/bio.c:831
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_read_page_sync
  - fs/iomap/direct-io.c:iomap_dio_zero
  - block/bio.c:bio_iov_iter_get_pages
  - block/bio.c:bio_add_page
```
**Symbols:**

```
ffffffff814c75b0-ffffffff814c7624: __bio_add_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __bio_add_page(struct bio *bio, struct page *page, unsigned int len, unsigned int off);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814d2c80)
Location: block/bio.c:831
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_read_page_sync
  - fs/iomap/direct-io.c:iomap_dio_zero
  - block/bio.c:bio_iov_iter_get_pages
  - block/bio.c:bio_add_page
```
**Symbols:**

```
ffffffff814d2c80-ffffffff814d2cf4: __bio_add_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __bio_add_page(struct bio *bio, struct page *page, unsigned int len, unsigned int off);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814eb800)
Location: block/bio.c:831
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_read_page_sync
  - fs/iomap/direct-io.c:iomap_dio_zero
  - block/bio.c:bio_iov_iter_get_pages
  - block/bio.c:bio_add_page
```
**Symbols:**

```
ffffffff814eb800-ffffffff814eb874: __bio_add_page (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
