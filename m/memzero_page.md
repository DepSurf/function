# Function: <code>memzero_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void memzero_page(struct page *page, size_t offset, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff813fc0e0)
Location: lib/iov_iter.c:379
Inline: False
Direct callers:
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:iov_iter_zero
```
**Symbols:**

```
ffffffff813fc0e0-ffffffff813fc14a: memzero_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff8144367a)
Location: lib/iov_iter.c:352
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_zero
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void memzero_page(struct page *page, size_t offset, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81460380)
Location: lib/iov_iter.c:444
Inline: False
Direct callers:
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:iov_iter_zero
```
**Symbols:**

```
ffffffff81460380-ffffffff814603dd: memzero_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void memzero_page(struct page *page, size_t offset, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81464cd0)
Location: lib/iov_iter.c:464
Inline: False
Direct callers:
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:iov_iter_zero
```
**Symbols:**

```
ffffffff81464cd0-ffffffff81464d0f: memzero_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void memzero_page(struct page *page, size_t offset, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81490c50)
Location: lib/iov_iter.c:464
Inline: False
Direct callers:
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:iov_iter_zero
```
**Symbols:**

```
ffffffff81490c50-ffffffff81490c8f: memzero_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void memzero_page(struct page *page, size_t offset, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff814c5a60)
Location: lib/iov_iter.c:464
Inline: False
Direct callers:
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:iov_iter_zero
```
**Symbols:**

```
ffffffff814c5a60-ffffffff814c5a9f: memzero_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void memzero_page(struct page *page, size_t offset, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff814da200)
Location: lib/iov_iter.c:470
Inline: False
Direct callers:
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:iov_iter_zero
```
**Symbols:**

```
ffffffff814da200-ffffffff814da23f: memzero_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void memzero_page(struct page *page, size_t offset, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81505a20)
Location: lib/iov_iter.c:471
Inline: False
Direct callers:
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:iov_iter_zero
```
**Symbols:**

```
ffffffff81505a20-ffffffff81505a5f: memzero_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void memzero_page(struct page *page, size_t offset, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff815239d0)
Location: lib/iov_iter.c:471
Inline: False
Direct callers:
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:iov_iter_zero
```
**Symbols:**

```
ffffffff815239d0-ffffffff81523a0f: memzero_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void memzero_page(struct page *page, size_t offset, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81587720)
Location: lib/iov_iter.c:476
Inline: False
Direct callers:
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:pipe_zero
```
**Symbols:**

```
ffffffff81587720-ffffffff81587762: memzero_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void memzero_page(struct page *page, size_t offset, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff815a5120)
Location: lib/iov_iter.c:483
Inline: False
Direct callers:
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:pipe_zero
```
**Symbols:**

```
ffffffff815a5120-ffffffff815a5162: memzero_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff815b006b)
Location: include/linux/highmem.h:336
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:iov_iter_zero
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff815c6ef8)
Location: include/linux/highmem.h:322
Inline: True
Inline callers:
  - block/bio.c:zero_fill_bio
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff81671e10)
Location: include/linux/highmem.h:393
Inline: True
Inline callers:
  - block/bio.c:zero_fill_bio
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/squashfs/file.c (ffffffff815ef0e9)
Location: include/linux/highmem.h:408
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readahead
```
```
In block/bio.c (ffffffff8172d9f0)
Location: include/linux/highmem.h:408
Inline: True
Inline callers:
  - block/bio.c:zero_fill_bio
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/squashfs/file.c (ffffffff816270c6)
Location: include/linux/highmem.h:432
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readahead
```
```
In block/bio.c (ffffffff81769d9b)
Location: include/linux/highmem.h:432
Inline: True
Inline callers:
  - block/bio.c:zero_fill_bio
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/squashfs/file.c (ffffffff81660200)
Location: include/linux/highmem.h:432
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readahead
```
```
In block/bio.c (ffffffff817abf4b)
Location: include/linux/highmem.h:432
Inline: True
Inline callers:
  - block/bio.c:zero_fill_bio_iter
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
void memzero_page(struct page *page, size_t offset, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffff80001062d8d0)
Location: lib/iov_iter.c:471
Inline: False
Direct callers:
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:iov_iter_zero
```
**Symbols:**

```
ffff80001062d8d0-ffff80001062d92c: memzero_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void memzero_page(struct page *page, size_t offset, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (c07d4510)
Location: lib/iov_iter.c:471
Inline: False
Direct callers:
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:iov_iter_zero
```
**Symbols:**

```
c07d4510-c07d4548: memzero_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void memzero_page(struct page *page, size_t offset, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (c0000000007d0c70)
Location: lib/iov_iter.c:471
Inline: False
Direct callers:
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:iov_iter_zero
```
**Symbols:**

```
c0000000007d0c70-c0000000007d0ce8: memzero_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void memzero_page(struct page *page, size_t offset, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffe00045d6d6)
Location: lib/iov_iter.c:471
Inline: False
Direct callers:
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:iov_iter_zero
```
**Symbols:**

```
ffffffe00045d6d6-ffffffe00045d72a: memzero_page (STB_LOCAL)
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
void memzero_page(struct page *page, size_t offset, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff8151bfb0)
Location: lib/iov_iter.c:471
Inline: False
Direct callers:
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:iov_iter_zero
```
**Symbols:**

```
ffffffff8151bfb0-ffffffff8151bfef: memzero_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void memzero_page(struct page *page, size_t offset, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff8150c2a0)
Location: lib/iov_iter.c:471
Inline: False
Direct callers:
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:iov_iter_zero
```
**Symbols:**

```
ffffffff8150c2a0-ffffffff8150c2df: memzero_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void memzero_page(struct page *page, size_t offset, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81518040)
Location: lib/iov_iter.c:471
Inline: False
Direct callers:
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:iov_iter_zero
```
**Symbols:**

```
ffffffff81518040-ffffffff8151807f: memzero_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void memzero_page(struct page *page, size_t offset, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81531810)
Location: lib/iov_iter.c:471
Inline: False
Direct callers:
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:iov_iter_zero
```
**Symbols:**

```
ffffffff81531810-ffffffff81531867: memzero_page (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
