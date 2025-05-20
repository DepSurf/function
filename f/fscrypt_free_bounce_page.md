# Function: <code>fscrypt_free_bounce_page</code>

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
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void fscrypt_free_bounce_page(struct page *bounce_page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/crypto/crypto.c (ffffffff81336f12)
Location: fs/crypto/crypto.c:128
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
Direct callers:
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_finish_bio
```
**Symbols:**

```
ffffffff813369a0-ffffffff813369c4: fscrypt_free_bounce_page.part.0 (STB_LOCAL)
ffffffff813369d0-ffffffff813369e6: fscrypt_free_bounce_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void fscrypt_free_bounce_page(struct page *bounce_page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/crypto/crypto.c (ffffffff8134aaf2)
Location: fs/crypto/crypto.c:128
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
Direct callers:
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_finish_bio
```
**Symbols:**

```
ffffffff8134a520-ffffffff8134a544: fscrypt_free_bounce_page.part.0 (STB_LOCAL)
ffffffff8134a550-ffffffff8134a566: fscrypt_free_bounce_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void fscrypt_free_bounce_page(struct page *bounce_page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (ffffffff81390243)
Location: fs/crypto/crypto.c:62
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
Direct callers:
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/ext4/page-io.c:ext4_finish_bio
```
**Symbols:**

```
ffffffff8138fd50-ffffffff8138fd7a: fscrypt_free_bounce_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void fscrypt_free_bounce_page(struct page *bounce_page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (ffffffff813a1883)
Location: fs/crypto/crypto.c:62
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
Direct callers:
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/ext4/page-io.c:ext4_finish_bio
```
**Symbols:**

```
ffffffff813a1390-ffffffff813a13ba: fscrypt_free_bounce_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void fscrypt_free_bounce_page(struct page *bounce_page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (ffffffff813a8a23)
Location: fs/crypto/crypto.c:62
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
Direct callers:
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/ext4/page-io.c:ext4_finish_bio
```
**Symbols:**

```
ffffffff813a8520-ffffffff813a854a: fscrypt_free_bounce_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void fscrypt_free_bounce_page(struct page *bounce_page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (ffffffff813f817d)
Location: fs/crypto/crypto.c:62
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
Direct callers:
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/ext4/page-io.c:ext4_finish_bio
```
**Symbols:**

```
ffffffff813f7c60-ffffffff813f7c8a: fscrypt_free_bounce_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void fscrypt_free_bounce_page(struct page *bounce_page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (ffffffff81e7861f)
Location: fs/crypto/crypto.c:62
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
Direct callers:
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/ext4/page-io.c:ext4_finish_bio
```
**Symbols:**

```
ffffffff8146a920-ffffffff8146a95a: fscrypt_free_bounce_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void fscrypt_free_bounce_page(struct page *bounce_page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (ffffffff8206a3dd)
Location: fs/crypto/crypto.c:62
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
Direct callers:
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/ext4/page-io.c:ext4_finish_bio
```
**Symbols:**

```
ffffffff814fb8b0-ffffffff814fb8ea: fscrypt_free_bounce_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void fscrypt_free_bounce_page(struct page *bounce_page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (ffffffff81533406)
Location: fs/crypto/crypto.c:62
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
Direct callers:
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/ext4/page-io.c:ext4_finish_bio
```
**Symbols:**

```
ffffffff81532bd0-ffffffff81532c0a: fscrypt_free_bounce_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void fscrypt_free_bounce_page(struct page *bounce_page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (ffffffff8156832e)
Location: fs/crypto/crypto.c:69
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
Direct callers:
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/ext4/page-io.c:ext4_finish_bio
```
**Symbols:**

```
ffffffff81567ac0-ffffffff81567afa: fscrypt_free_bounce_page (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void fscrypt_free_bounce_page(struct page *bounce_page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/crypto/crypto.c (ffff80001040b2dc)
Location: fs/crypto/crypto.c:128
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
Direct callers:
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_finish_bio
```
**Symbols:**

```
ffff80001040aab8-ffff80001040ab24: fscrypt_free_bounce_page.part.0 (STB_LOCAL)
ffff80001040ab28-ffff80001040ab58: fscrypt_free_bounce_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
void fscrypt_free_bounce_page(struct page *bounce_page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/crypto/crypto.c (c05d8528)
Location: fs/crypto/crypto.c:128
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
Direct callers:
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_finish_bio
```
**Symbols:**

```
c05d7e54-c05d7e98: fscrypt_free_bounce_page.part.0 (STB_LOCAL)
c05d7e98-c05d7ebc: fscrypt_free_bounce_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
void fscrypt_free_bounce_page(struct page *bounce_page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/crypto/crypto.c (c000000000517e60)
Location: fs/crypto/crypto.c:128
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
Direct callers:
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_finish_bio
```
**Symbols:**

```
c0000000005175c0-c000000000517618: fscrypt_free_bounce_page.part.0 (STB_LOCAL)
c000000000517620-c00000000051763c: fscrypt_free_bounce_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void fscrypt_free_bounce_page(struct page *bounce_page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (ffffffe0002b4fa4)
Location: fs/crypto/crypto.c:128
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
Direct callers:
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_finish_bio
```
**Symbols:**

```
ffffffe0002b4aa4-ffffffe0002b4ae4: fscrypt_free_bounce_page (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
void fscrypt_free_bounce_page(struct page *bounce_page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/crypto/crypto.c (ffffffff813430d2)
Location: fs/crypto/crypto.c:128
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
Direct callers:
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_finish_bio
```
**Symbols:**

```
ffffffff81342b00-ffffffff81342b24: fscrypt_free_bounce_page.part.0 (STB_LOCAL)
ffffffff81342b30-ffffffff81342b46: fscrypt_free_bounce_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
void fscrypt_free_bounce_page(struct page *bounce_page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/crypto/crypto.c (ffffffff81333db2)
Location: fs/crypto/crypto.c:128
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
Direct callers:
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_finish_bio
```
**Symbols:**

```
ffffffff813337e0-ffffffff81333804: fscrypt_free_bounce_page.part.0 (STB_LOCAL)
ffffffff81333810-ffffffff81333826: fscrypt_free_bounce_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void fscrypt_free_bounce_page(struct page *bounce_page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/crypto/crypto.c (ffffffff81340ba2)
Location: fs/crypto/crypto.c:128
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
Direct callers:
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_finish_bio
```
**Symbols:**

```
ffffffff813405d0-ffffffff813405f4: fscrypt_free_bounce_page.part.0 (STB_LOCAL)
ffffffff81340600-ffffffff81340616: fscrypt_free_bounce_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void fscrypt_free_bounce_page(struct page *bounce_page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/crypto/crypto.c (ffffffff81353ea2)
Location: fs/crypto/crypto.c:128
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
Direct callers:
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_finish_bio
```
**Symbols:**

```
ffffffff813538d0-ffffffff813538f4: fscrypt_free_bounce_page.part.0 (STB_LOCAL)
ffffffff81353900-ffffffff81353916: fscrypt_free_bounce_page (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
