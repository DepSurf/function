# Function: <code>iov_iter_get_pages_alloc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
ssize_t iov_iter_get_pages_alloc(struct iov_iter *i, struct page ***pages, size_t maxsize, size_t *start);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff813fc560)
Location: lib/iov_iter.c:617
Inline: False
```
**Symbols:**

```
ffffffff813fc560-ffffffff813fc7cc: iov_iter_get_pages_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
ssize_t iov_iter_get_pages_alloc(struct iov_iter *i, struct page ***pages, size_t maxsize, size_t *start);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81442850)
Location: lib/iov_iter.c:585
Inline: False
```
**Symbols:**

```
ffffffff81442850-ffffffff81442a8b: iov_iter_get_pages_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
ssize_t iov_iter_get_pages_alloc(struct iov_iter *i, struct page ***pages, size_t maxsize, size_t *start);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff8145ff00)
Location: lib/iov_iter.c:1008
Inline: False
Direct callers:
  - fs/splice.c:default_file_splice_read
```
**Symbols:**

```
ffffffff8145ff00-ffffffff814602a4: iov_iter_get_pages_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
ssize_t iov_iter_get_pages_alloc(struct iov_iter *i, struct page ***pages, size_t maxsize, size_t *start);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff814687c0)
Location: lib/iov_iter.c:1132
Inline: False
Direct callers:
  - fs/splice.c:default_file_splice_read
```
**Symbols:**

```
ffffffff814687c0-ffffffff81468bd6: iov_iter_get_pages_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
ssize_t iov_iter_get_pages_alloc(struct iov_iter *i, struct page ***pages, size_t maxsize, size_t *start);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81494a70)
Location: lib/iov_iter.c:1134
Inline: False
Direct callers:
  - fs/splice.c:default_file_splice_read
  - block/bio.c:bio_map_user_iov
```
**Symbols:**

```
ffffffff81494a70-ffffffff81494e86: iov_iter_get_pages_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
ssize_t iov_iter_get_pages_alloc(struct iov_iter *i, struct page ***pages, size_t maxsize, size_t *start);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff814c5c10)
Location: lib/iov_iter.c:1264
Inline: False
Direct callers:
  - fs/splice.c:default_file_splice_read
  - block/bio.c:bio_map_user_iov
```
**Symbols:**

```
ffffffff814c5c10-ffffffff814c6047: iov_iter_get_pages_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
ssize_t iov_iter_get_pages_alloc(struct iov_iter *i, struct page ***pages, size_t maxsize, size_t *start);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff814da3a0)
Location: lib/iov_iter.c:1339
Inline: False
Direct callers:
  - fs/splice.c:default_file_splice_read
  - block/bio.c:bio_map_user_iov
```
**Symbols:**

```
ffffffff814da3a0-ffffffff814da810: iov_iter_get_pages_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
ssize_t iov_iter_get_pages_alloc(struct iov_iter *i, struct page ***pages, size_t maxsize, size_t *start);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81505bd0)
Location: lib/iov_iter.c:1355
Inline: False
Direct callers:
  - fs/splice.c:default_file_splice_read
  - block/bio.c:bio_map_user_iov
```
**Symbols:**

```
ffffffff81505bd0-ffffffff8150607a: iov_iter_get_pages_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
ssize_t iov_iter_get_pages_alloc(struct iov_iter *i, struct page ***pages, size_t maxsize, size_t *start);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81523bb0)
Location: lib/iov_iter.c:1355
Inline: False
Direct callers:
  - fs/splice.c:default_file_splice_read
  - block/bio.c:bio_map_user_iov
```
**Symbols:**

```
ffffffff81523bb0-ffffffff8152405a: iov_iter_get_pages_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
ssize_t iov_iter_get_pages_alloc(struct iov_iter *i, struct page ***pages, size_t maxsize, size_t *start);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81586fe0)
Location: lib/iov_iter.c:1390
Inline: False
Direct callers:
  - block/blk-map.c:bio_map_user_iov
```
**Symbols:**

```
ffffffff81586fe0-ffffffff81587488: iov_iter_get_pages_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ssize_t iov_iter_get_pages_alloc(struct iov_iter *i, struct page ***pages, size_t maxsize, size_t *start);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff815a47c0)
Location: lib/iov_iter.c:1397
Inline: False
Direct callers:
  - block/blk-map.c:bio_map_user_iov
```
**Symbols:**

```
ffffffff815a47c0-ffffffff815a4c88: iov_iter_get_pages_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ssize_t iov_iter_get_pages_alloc(struct iov_iter *i, struct page ***pages, size_t maxsize, size_t *start);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff815adf50)
Location: lib/iov_iter.c:1646
Inline: False
Direct callers:
  - block/blk-map.c:bio_map_user_iov
```
**Symbols:**

```
ffffffff815adf50-ffffffff815ae70a: iov_iter_get_pages_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
ssize_t iov_iter_get_pages_alloc(struct iov_iter *i, struct page ***pages, size_t maxsize, size_t *start);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/iov_iter.c (0)
Location: lib/iov_iter.c:1594
Inline: False
Direct callers:
  - block/blk-map.c:bio_map_user_iov
```
**Symbols:**

```
ffffffff81cda8e9-ffffffff81cda91c: iov_iter_get_pages_alloc.cold (STB_LOCAL)
ffffffff81615a30-ffffffff81615da8: iov_iter_get_pages_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
ssize_t iov_iter_get_pages_alloc(struct iov_iter *i, struct page ***pages, size_t maxsize, size_t *start);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/iov_iter.c (0)
Location: lib/iov_iter.c:1638
Inline: False
Direct callers:
  - block/blk-map.c:bio_map_user_iov
```
**Symbols:**

```
ffffffff81e92f1b-ffffffff81e92f56: iov_iter_get_pages_alloc.cold (STB_LOCAL)
ffffffff816e2620-ffffffff816e29f1: iov_iter_get_pages_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
ssize_t iov_iter_get_pages_alloc(struct iov_iter *i, struct page ***pages, size_t maxsize, size_t *start, unsigned int gup_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff817d2f23)
Location: lib/iov_iter.c:1516
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_get_pages_alloc2
  - lib/iov_iter.c:iov_iter_get_pages_alloc2
Direct callers:
  - block/blk-map.c:bio_map_user_iov
```
**Symbols:**

```
ffffffff817d2e20-ffffffff817d2e8f: iov_iter_get_pages_alloc (STB_GLOBAL)
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
ssize_t iov_iter_get_pages_alloc(struct iov_iter *i, struct page ***pages, size_t maxsize, size_t *start);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffff80001062db40)
Location: lib/iov_iter.c:1355
Inline: False
Direct callers:
  - fs/splice.c:default_file_splice_read
  - block/bio.c:bio_map_user_iov
```
**Symbols:**

```
ffff80001062db40-ffff80001062dfc8: iov_iter_get_pages_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
ssize_t iov_iter_get_pages_alloc(struct iov_iter *i, struct page ***pages, size_t maxsize, size_t *start);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (c07d4b58)
Location: lib/iov_iter.c:1355
Inline: False
Direct callers:
  - fs/splice.c:default_file_splice_read
  - block/bio.c:bio_map_user_iov
```
**Symbols:**

```
c07d4b58-c07d4f6c: iov_iter_get_pages_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
ssize_t iov_iter_get_pages_alloc(struct iov_iter *i, struct page ***pages, size_t maxsize, size_t *start);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (c0000000007d1030)
Location: lib/iov_iter.c:1355
Inline: False
Direct callers:
  - fs/splice.c:default_file_splice_read
  - block/bio.c:bio_map_user_iov
```
**Symbols:**

```
c0000000007d1030-c0000000007d16b4: iov_iter_get_pages_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
ssize_t iov_iter_get_pages_alloc(struct iov_iter *i, struct page ***pages, size_t maxsize, size_t *start);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffe00045d804)
Location: lib/iov_iter.c:1355
Inline: False
Direct callers:
  - fs/splice.c:default_file_splice_read
  - block/bio.c:bio_map_user_iov
```
**Symbols:**

```
ffffffe00045d804-ffffffe00045dbaa: iov_iter_get_pages_alloc (STB_GLOBAL)
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
ssize_t iov_iter_get_pages_alloc(struct iov_iter *i, struct page ***pages, size_t maxsize, size_t *start);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff8151c190)
Location: lib/iov_iter.c:1355
Inline: False
Direct callers:
  - fs/splice.c:default_file_splice_read
  - block/bio.c:bio_map_user_iov
```
**Symbols:**

```
ffffffff8151c190-ffffffff8151c63a: iov_iter_get_pages_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
ssize_t iov_iter_get_pages_alloc(struct iov_iter *i, struct page ***pages, size_t maxsize, size_t *start);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff8150c480)
Location: lib/iov_iter.c:1355
Inline: False
Direct callers:
  - fs/splice.c:default_file_splice_read
  - block/bio.c:bio_map_user_iov
```
**Symbols:**

```
ffffffff8150c480-ffffffff8150c92a: iov_iter_get_pages_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
ssize_t iov_iter_get_pages_alloc(struct iov_iter *i, struct page ***pages, size_t maxsize, size_t *start);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81518220)
Location: lib/iov_iter.c:1355
Inline: False
Direct callers:
  - fs/splice.c:default_file_splice_read
  - block/bio.c:bio_map_user_iov
```
**Symbols:**

```
ffffffff81518220-ffffffff815186ca: iov_iter_get_pages_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
ssize_t iov_iter_get_pages_alloc(struct iov_iter *i, struct page ***pages, size_t maxsize, size_t *start);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81531aa0)
Location: lib/iov_iter.c:1355
Inline: False
Direct callers:
  - fs/splice.c:default_file_splice_read
  - block/bio.c:bio_map_user_iov
```
**Symbols:**

```
ffffffff81531aa0-ffffffff81531f4a: iov_iter_get_pages_alloc (STB_GLOBAL)
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
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int gup_flags</code>
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
