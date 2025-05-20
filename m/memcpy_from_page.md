# Function: <code>memcpy_from_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void memcpy_from_page(char *to, struct page *page, size_t offset, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff813fb8b0)
Location: lib/iov_iter.c:365
Inline: False
Direct callers:
  - lib/iov_iter.c:copy_from_iter
  - lib/iov_iter.c:copy_from_iter
  - lib/iov_iter.c:copy_from_iter_nocache
  - lib/iov_iter.c:copy_from_iter_nocache
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
```
**Symbols:**

```
ffffffff813fb8b0-ffffffff813fb91e: memcpy_from_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void memcpy_from_page(char *to, struct page *page, size_t offset, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81442c60)
Location: lib/iov_iter.c:338
Inline: False
Direct callers:
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:copy_from_iter_nocache
  - lib/iov_iter.c:copy_from_iter
```
**Symbols:**

```
ffffffff81442c60-ffffffff81442cc4: memcpy_from_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void memcpy_from_page(char *to, struct page *page, size_t offset, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff814602b0)
Location: lib/iov_iter.c:430
Inline: False
Direct callers:
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:copy_from_iter_full_nocache
  - lib/iov_iter.c:copy_from_iter_nocache
  - lib/iov_iter.c:copy_from_iter_full
  - lib/iov_iter.c:copy_from_iter
```
**Symbols:**

```
ffffffff814602b0-ffffffff8146030e: memcpy_from_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void memcpy_from_page(char *to, struct page *page, size_t offset, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81464c90)
Location: lib/iov_iter.c:450
Inline: False
Direct callers:
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:_copy_from_iter_full_nocache
  - lib/iov_iter.c:_copy_from_iter_nocache
  - lib/iov_iter.c:_copy_from_iter_full
  - lib/iov_iter.c:_copy_from_iter
```
**Symbols:**

```
ffffffff81464c90-ffffffff81464cd0: memcpy_from_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void memcpy_from_page(char *to, struct page *page, size_t offset, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81490c10)
Location: lib/iov_iter.c:450
Inline: False
Direct callers:
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:_copy_from_iter_full_nocache
  - lib/iov_iter.c:_copy_from_iter_nocache
  - lib/iov_iter.c:_copy_from_iter_full
  - lib/iov_iter.c:_copy_from_iter
```
**Symbols:**

```
ffffffff81490c10-ffffffff81490c50: memcpy_from_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void memcpy_from_page(char *to, struct page *page, size_t offset, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff814c59c0)
Location: lib/iov_iter.c:450
Inline: False
Direct callers:
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:_copy_from_iter_full_nocache
  - lib/iov_iter.c:_copy_from_iter_nocache
  - lib/iov_iter.c:_copy_from_iter_full
  - lib/iov_iter.c:_copy_from_iter
```
**Symbols:**

```
ffffffff814c59c0-ffffffff814c5a00: memcpy_from_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void memcpy_from_page(char *to, struct page *page, size_t offset, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff814da110)
Location: lib/iov_iter.c:456
Inline: False
Direct callers:
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:_copy_from_iter_full_nocache
  - lib/iov_iter.c:_copy_from_iter_nocache
  - lib/iov_iter.c:_copy_from_iter_full
  - lib/iov_iter.c:_copy_from_iter
```
**Symbols:**

```
ffffffff814da110-ffffffff814da150: memcpy_from_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void memcpy_from_page(char *to, struct page *page, size_t offset, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81505910)
Location: lib/iov_iter.c:457
Inline: False
Direct callers:
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:_copy_from_iter_full_nocache
  - lib/iov_iter.c:_copy_from_iter_nocache
  - lib/iov_iter.c:_copy_from_iter_full
  - lib/iov_iter.c:_copy_from_iter
```
**Symbols:**

```
ffffffff81505910-ffffffff81505953: memcpy_from_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void memcpy_from_page(char *to, struct page *page, size_t offset, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff815238c0)
Location: lib/iov_iter.c:457
Inline: False
Direct callers:
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:_copy_from_iter_full_nocache
  - lib/iov_iter.c:_copy_from_iter_nocache
  - lib/iov_iter.c:_copy_from_iter_full
  - lib/iov_iter.c:_copy_from_iter
```
**Symbols:**

```
ffffffff815238c0-ffffffff81523903: memcpy_from_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void memcpy_from_page(char *to, struct page *page, size_t offset, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff815879e0)
Location: lib/iov_iter.c:462
Inline: False
Direct callers:
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:_copy_from_iter_full_nocache
  - lib/iov_iter.c:_copy_from_iter_nocache
  - lib/iov_iter.c:_copy_from_iter_full
  - lib/iov_iter.c:_copy_from_iter
```
**Symbols:**

```
ffffffff815879e0-ffffffff81587a83: memcpy_from_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void memcpy_from_page(char *to, struct page *page, size_t offset, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff815a5280)
Location: lib/iov_iter.c:469
Inline: False
Direct callers:
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:_copy_from_iter_full_nocache
  - lib/iov_iter.c:_copy_from_iter_nocache
  - lib/iov_iter.c:_copy_from_iter_full
  - lib/iov_iter.c:_copy_from_iter
```
**Symbols:**

```
ffffffff815a5280-ffffffff815a5323: memcpy_from_page (STB_LOCAL)
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
In fs/ext4/verity.c (ffffffff8145e08e)
Location: include/linux/highmem.h:315
Inline: True
Inline callers:
  - fs/ext4/verity.c:pagecache_read
```
```
In lib/iov_iter.c (ffffffff815adb14)
Location: include/linux/highmem.h:315
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:_copy_from_iter_full_nocache
  - lib/iov_iter.c:_copy_from_iter_full_nocache
  - lib/iov_iter.c:_copy_from_iter_nocache
  - lib/iov_iter.c:_copy_from_iter_nocache
  - lib/iov_iter.c:_copy_from_iter_full
  - lib/iov_iter.c:_copy_from_iter_full
  - lib/iov_iter.c:_copy_from_iter
  - lib/iov_iter.c:_copy_from_iter
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
In fs/ext4/verity.c (ffffffff814b35ae)
Location: include/linux/highmem.h:301
Inline: True
Inline callers:
  - fs/ext4/verity.c:pagecache_read
```
```
In block/blk-map.c (ffffffff815d2a33)
Location: include/linux/highmem.h:301
Inline: True
Inline callers:
  - block/blk-map.c:bio_copy_kern_endio_read
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/verity.c (ffffffff8153c180)
Location: include/linux/highmem.h:372
Inline: True
Inline callers:
  - fs/ext4/verity.c:pagecache_read
```
```
In block/blk-map.c (ffffffff8167f514)
Location: include/linux/highmem.h:372
Inline: True
Inline callers:
  - block/blk-map.c:bio_copy_kern_endio_read
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
In kernel/dma/swiotlb.c (0)
Location: include/linux/highmem.h:387
Inline: False
```
```
In fs/verity/verify.c (ffffffff81506d17)
Location: include/linux/highmem.h:387
Inline: True
Inline callers:
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
```
```
In fs/ext4/verity.c (ffffffff815da840)
Location: include/linux/highmem.h:387
Inline: True
Inline callers:
  - fs/ext4/verity.c:pagecache_read
```
```
In block/blk-map.c (ffffffff8173b9e4)
Location: include/linux/highmem.h:387
Inline: True
Inline callers:
  - block/blk-map.c:bio_copy_kern_endio_read
```
```
In drivers/base/firmware_loader/sysfs.c (ffffffff81b13026)
Location: include/linux/highmem.h:387
Inline: True
Inline callers:
  - drivers/base/firmware_loader/sysfs.c:firmware_rw
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
In kernel/dma/swiotlb.c (0)
Location: include/linux/highmem.h:411
Inline: False
```
```
In block/blk-map.c (ffffffff81778124)
Location: include/linux/highmem.h:411
Inline: True
Inline callers:
  - block/blk-map.c:bio_copy_kern_endio_read
```
```
In drivers/base/firmware_loader/sysfs.c (ffffffff81b61336)
Location: include/linux/highmem.h:411
Inline: True
Inline callers:
  - drivers/base/firmware_loader/sysfs.c:firmware_rw
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
In kernel/dma/swiotlb.c (0)
Location: include/linux/highmem.h:411
Inline: False
```
```
In block/blk-map.c (ffffffff817ba504)
Location: include/linux/highmem.h:411
Inline: True
Inline callers:
  - block/blk-map.c:bio_copy_kern_endio_read
```
```
In drivers/base/firmware_loader/sysfs.c (ffffffff81bb4dc6)
Location: include/linux/highmem.h:411
Inline: True
Inline callers:
  - drivers/base/firmware_loader/sysfs.c:firmware_rw
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
void memcpy_from_page(char *to, struct page *page, size_t offset, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffff80001062d810)
Location: lib/iov_iter.c:457
Inline: False
Direct callers:
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:_copy_from_iter_full_nocache
  - lib/iov_iter.c:_copy_from_iter_nocache
  - lib/iov_iter.c:_copy_from_iter_full
  - lib/iov_iter.c:_copy_from_iter
```
**Symbols:**

```
ffff80001062d810-ffff80001062d86c: memcpy_from_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void memcpy_from_page(char *to, struct page *page, size_t offset, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (c07d4464)
Location: lib/iov_iter.c:457
Inline: False
Direct callers:
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:_copy_from_iter_full_nocache
  - lib/iov_iter.c:_copy_from_iter_nocache
  - lib/iov_iter.c:_copy_from_iter_full
  - lib/iov_iter.c:_copy_from_iter
```
**Symbols:**

```
c07d4464-c07d44a4: memcpy_from_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void memcpy_from_page(char *to, struct page *page, size_t offset, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (c0000000007d0af0)
Location: lib/iov_iter.c:457
Inline: False
Direct callers:
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:_copy_from_iter_full_nocache
  - lib/iov_iter.c:_copy_from_iter_nocache
  - lib/iov_iter.c:_copy_from_iter_full
  - lib/iov_iter.c:_copy_from_iter
```
**Symbols:**

```
c0000000007d0af0-c0000000007d0b68: memcpy_from_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void memcpy_from_page(char *to, struct page *page, size_t offset, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffe00045d41c)
Location: lib/iov_iter.c:457
Inline: False
Direct callers:
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:_copy_from_iter_full_nocache
  - lib/iov_iter.c:_copy_from_iter_nocache
  - lib/iov_iter.c:_copy_from_iter_full
  - lib/iov_iter.c:_copy_from_iter
```
**Symbols:**

```
ffffffe00045d41c-ffffffe00045d470: memcpy_from_page (STB_LOCAL)
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
void memcpy_from_page(char *to, struct page *page, size_t offset, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff8151bea0)
Location: lib/iov_iter.c:457
Inline: False
Direct callers:
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:_copy_from_iter_full_nocache
  - lib/iov_iter.c:_copy_from_iter_nocache
  - lib/iov_iter.c:_copy_from_iter_full
  - lib/iov_iter.c:_copy_from_iter
```
**Symbols:**

```
ffffffff8151bea0-ffffffff8151bee3: memcpy_from_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void memcpy_from_page(char *to, struct page *page, size_t offset, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff8150c190)
Location: lib/iov_iter.c:457
Inline: False
Direct callers:
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:_copy_from_iter_full_nocache
  - lib/iov_iter.c:_copy_from_iter_nocache
  - lib/iov_iter.c:_copy_from_iter_full
  - lib/iov_iter.c:_copy_from_iter
```
**Symbols:**

```
ffffffff8150c190-ffffffff8150c1d3: memcpy_from_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void memcpy_from_page(char *to, struct page *page, size_t offset, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81517f30)
Location: lib/iov_iter.c:457
Inline: False
Direct callers:
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:_copy_from_iter_full_nocache
  - lib/iov_iter.c:_copy_from_iter_nocache
  - lib/iov_iter.c:_copy_from_iter_full
  - lib/iov_iter.c:_copy_from_iter
```
**Symbols:**

```
ffffffff81517f30-ffffffff81517f73: memcpy_from_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void memcpy_from_page(char *to, struct page *page, size_t offset, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81531730)
Location: lib/iov_iter.c:457
Inline: False
Direct callers:
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:_copy_from_iter_full_nocache
  - lib/iov_iter.c:_copy_from_iter_nocache
  - lib/iov_iter.c:_copy_from_iter_full
  - lib/iov_iter.c:_copy_from_iter
```
**Symbols:**

```
ffffffff81531730-ffffffff8153178b: memcpy_from_page (STB_LOCAL)
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
