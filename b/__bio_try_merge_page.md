# Function: <code>__bio_try_merge_page</code>

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
bool __bio_try_merge_page(struct bio *bio, struct page *page, unsigned int len, unsigned int off);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff81478ce0)
Location: block/bio.c:837
Inline: False
Direct callers:
  - block/bio.c:bio_add_page
```
**Symbols:**

```
ffffffff81478ce0-ffffffff81478d34: __bio_try_merge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool __bio_try_merge_page(struct bio *bio, struct page *page, unsigned int len, unsigned int off);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff81496f40)
Location: block/bio.c:763
Inline: False
Direct callers:
  - fs/iomap.c:iomap_readpage_actor
  - block/bio.c:bio_add_page
```
**Symbols:**

```
ffffffff81496f40-ffffffff81496f94: __bio_try_merge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool __bio_try_merge_page(struct bio *bio, struct page *page, unsigned int len, unsigned int off, bool *same_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814c56a0)
Location: block/bio.c:766
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_readpage_actor
  - block/bio.c:bio_iov_iter_get_pages
  - block/bio.c:bio_add_page
```
**Symbols:**

```
ffffffff814c56a0-ffffffff814c57b0: __bio_try_merge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool __bio_try_merge_page(struct bio *bio, struct page *page, unsigned int len, unsigned int off, bool *same_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814ddcb0)
Location: block/bio.c:800
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_readpage_actor
  - block/bio.c:bio_iov_iter_get_pages
  - block/bio.c:bio_add_page
```
**Symbols:**

```
ffffffff814ddcb0-ffffffff814dddc4: __bio_try_merge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool __bio_try_merge_page(struct bio *bio, struct page *page, unsigned int len, unsigned int off, bool *same_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8153d810)
Location: block/bio.c:870
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_add_to_ioend
  - fs/iomap/buffered-io.c:iomap_readpage_actor
  - block/bio.c:__bio_iov_iter_get_pages
  - block/bio.c:bio_add_page
  - block/bio.c:bio_add_hw_page
```
**Symbols:**

```
ffffffff8153d810-ffffffff8153d93c: __bio_try_merge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool __bio_try_merge_page(struct bio *bio, struct page *page, unsigned int len, unsigned int off, bool *same_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8155a3f0)
Location: block/bio.c:870
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_add_to_ioend
  - fs/iomap/buffered-io.c:iomap_readpage_actor
  - block/bio.c:__bio_iov_iter_get_pages
  - block/bio.c:bio_add_page
  - block/bio.c:bio_add_hw_page
```
**Symbols:**

```
ffffffff8155a3f0-ffffffff8155a51c: __bio_try_merge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool __bio_try_merge_page(struct bio *bio, struct page *page, unsigned int len, unsigned int off, bool *same_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff81562bb0)
Location: block/bio.c:859
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_add_to_ioend
  - fs/iomap/buffered-io.c:iomap_readpage_actor
  - block/bio.c:bio_add_page
  - block/bio.c:bio_add_hw_page
```
**Symbols:**

```
ffffffff81562bb0-ffffffff81562cf4: __bio_try_merge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool __bio_try_merge_page(struct bio *bio, struct page *page, unsigned int len, unsigned int off, bool *same_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff815c6790)
Location: block/bio.c:942
Inline: False
Direct callers:
  - block/bio.c:__bio_iov_iter_get_pages
  - block/bio.c:bio_add_page
```
**Symbols:**

```
ffffffff815c6790-ffffffff815c68d8: __bio_try_merge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool __bio_try_merge_page(struct bio *bio, struct page *page, unsigned int len, unsigned int off, bool *same_page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff81671610)
Location: block/bio.c:891
Inline: False
Direct callers:
  - block/bio.c:bio_iov_iter_get_pages
  - block/bio.c:bio_add_folio
  - block/bio.c:bio_add_hw_page
```
**Symbols:**

```
ffffffff81671610-ffffffff81671782: __bio_try_merge_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool __bio_try_merge_page(struct bio *bio, struct page *page, unsigned int len, unsigned int off, bool *same_page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8172ce00)
Location: block/bio.c:946
Inline: False
Direct callers:
  - block/bio.c:__bio_iov_iter_get_pages
  - block/bio.c:bio_add_folio
  - block/bio.c:bio_add_hw_page
```
**Symbols:**

```
ffffffff8172ce00-ffffffff8172cfd3: __bio_try_merge_page (STB_LOCAL)
```
</details>
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
<summary>In <code>arm64</code>: ✅</summary>

```c
bool __bio_try_merge_page(struct bio *bio, struct page *page, unsigned int len, unsigned int off, bool *same_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffff8000105da198)
Location: block/bio.c:800
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_readpage_actor
  - block/bio.c:bio_iov_iter_get_pages
  - block/bio.c:bio_add_page
```
**Symbols:**

```
ffff8000105da198-ffff8000105da2f8: __bio_try_merge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool __bio_try_merge_page(struct bio *bio, struct page *page, unsigned int len, unsigned int off, bool *same_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (c0787eb4)
Location: block/bio.c:800
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_readpage_actor
  - block/bio.c:bio_iov_iter_get_pages
  - block/bio.c:bio_add_page
```
**Symbols:**

```
c0787eb4-c0788008: __bio_try_merge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool __bio_try_merge_page(struct bio *bio, struct page *page, unsigned int len, unsigned int off, bool *same_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (c00000000076b010)
Location: block/bio.c:800
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_readpage_actor
  - block/bio.c:bio_iov_iter_get_pages
  - block/bio.c:bio_add_page
```
**Symbols:**

```
c00000000076b010-c00000000076b11c: __bio_try_merge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool __bio_try_merge_page(struct bio *bio, struct page *page, unsigned int len, unsigned int off, bool *same_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffe00041e022)
Location: block/bio.c:800
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_readpage_actor
  - block/bio.c:bio_iov_iter_get_pages
  - block/bio.c:bio_add_page
```
**Symbols:**

```
ffffffe00041e022-ffffffe00041e0ec: __bio_try_merge_page (STB_GLOBAL)
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
bool __bio_try_merge_page(struct bio *bio, struct page *page, unsigned int len, unsigned int off, bool *same_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814d6290)
Location: block/bio.c:800
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_readpage_actor
  - block/bio.c:bio_iov_iter_get_pages
  - block/bio.c:bio_add_page
```
**Symbols:**

```
ffffffff814d6290-ffffffff814d63a4: __bio_try_merge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool __bio_try_merge_page(struct bio *bio, struct page *page, unsigned int len, unsigned int off, bool *same_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814c6c50)
Location: block/bio.c:800
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_readpage_actor
  - block/bio.c:bio_iov_iter_get_pages
  - block/bio.c:bio_add_page
```
**Symbols:**

```
ffffffff814c6c50-ffffffff814c6d09: __bio_try_merge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool __bio_try_merge_page(struct bio *bio, struct page *page, unsigned int len, unsigned int off, bool *same_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814d2320)
Location: block/bio.c:800
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_readpage_actor
  - block/bio.c:bio_iov_iter_get_pages
  - block/bio.c:bio_add_page
```
**Symbols:**

```
ffffffff814d2320-ffffffff814d2434: __bio_try_merge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool __bio_try_merge_page(struct bio *bio, struct page *page, unsigned int len, unsigned int off, bool *same_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814eae40)
Location: block/bio.c:800
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_readpage_actor
  - block/bio.c:bio_iov_iter_get_pages
  - block/bio.c:bio_add_page
```
**Symbols:**

```
ffffffff814eae40-ffffffff814eaf54: __bio_try_merge_page (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool *same_page</code>
</li>
</ul>
</details>
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
