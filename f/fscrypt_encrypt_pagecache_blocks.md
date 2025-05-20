# Function: <code>fscrypt_encrypt_pagecache_blocks</code>

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
<summary>In <code>5.3</code>: ✅</summary>

```c
struct page *fscrypt_encrypt_pagecache_blocks(struct page *page, unsigned int len, unsigned int offs, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (ffffffff81336e10)
Location: fs/crypto/crypto.c:219
Inline: False
Direct callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
**Symbols:**

```
ffffffff81336e10-ffffffff81336f49: fscrypt_encrypt_pagecache_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct page *fscrypt_encrypt_pagecache_blocks(struct page *page, unsigned int len, unsigned int offs, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (ffffffff8134a9f0)
Location: fs/crypto/crypto.c:217
Inline: False
Direct callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
**Symbols:**

```
ffffffff8134a9f0-ffffffff8134ab29: fscrypt_encrypt_pagecache_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct page *fscrypt_encrypt_pagecache_blocks(struct page *page, unsigned int len, unsigned int offs, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (ffffffff81390140)
Location: fs/crypto/crypto.c:164
Inline: False
Direct callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
**Symbols:**

```
ffffffff81390140-ffffffff81390292: fscrypt_encrypt_pagecache_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct page *fscrypt_encrypt_pagecache_blocks(struct page *page, unsigned int len, unsigned int offs, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (ffffffff813a1780)
Location: fs/crypto/crypto.c:164
Inline: False
Direct callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
**Symbols:**

```
ffffffff813a1780-ffffffff813a18d2: fscrypt_encrypt_pagecache_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct page *fscrypt_encrypt_pagecache_blocks(struct page *page, unsigned int len, unsigned int offs, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (ffffffff813a8920)
Location: fs/crypto/crypto.c:164
Inline: False
Direct callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
**Symbols:**

```
ffffffff813a8920-ffffffff813a8a72: fscrypt_encrypt_pagecache_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct page *fscrypt_encrypt_pagecache_blocks(struct page *page, unsigned int len, unsigned int offs, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/crypto.c (0)
Location: fs/crypto/crypto.c:164
Inline: False
Direct callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
**Symbols:**

```
ffffffff81cc61d3-ffffffff81cc624c: fscrypt_encrypt_pagecache_blocks.cold (STB_LOCAL)
ffffffff813f8060-ffffffff813f81cc: fscrypt_encrypt_pagecache_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct page *fscrypt_encrypt_pagecache_blocks(struct page *page, unsigned int len, unsigned int offs, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/crypto.c (0)
Location: fs/crypto/crypto.c:172
Inline: False
Direct callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
**Symbols:**

```
ffffffff81e7844b-ffffffff81e78643: fscrypt_encrypt_pagecache_blocks.cold (STB_LOCAL)
ffffffff8146ae20-ffffffff8146ae97: fscrypt_encrypt_pagecache_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct page *fscrypt_encrypt_pagecache_blocks(struct page *page, unsigned int len, unsigned int offs, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/crypto.c (0)
Location: fs/crypto/crypto.c:172
Inline: False
Direct callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
**Symbols:**

```
ffffffff8206a209-ffffffff8206a401: fscrypt_encrypt_pagecache_blocks.cold (STB_LOCAL)
ffffffff814fbf70-ffffffff814fbfe7: fscrypt_encrypt_pagecache_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct page *fscrypt_encrypt_pagecache_blocks(struct page *page, unsigned int len, unsigned int offs, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/crypto.c (0)
Location: fs/crypto/crypto.c:172
Inline: False
Direct callers:
  - fs/ext4/page-io.c:ext4_bio_write_folio
```
**Symbols:**

```
ffffffff820ea1e2-ffffffff820ea257: fscrypt_encrypt_pagecache_blocks.cold (STB_LOCAL)
ffffffff815332a0-ffffffff81533454: fscrypt_encrypt_pagecache_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct page *fscrypt_encrypt_pagecache_blocks(struct page *page, unsigned int len, unsigned int offs, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/crypto.c (0)
Location: fs/crypto/crypto.c:180
Inline: False
Direct callers:
  - fs/ext4/page-io.c:ext4_bio_write_folio
```
**Symbols:**

```
ffffffff821c6c7d-ffffffff821c6d0c: fscrypt_encrypt_pagecache_blocks.cold (STB_LOCAL)
ffffffff815681a0-ffffffff8156837e: fscrypt_encrypt_pagecache_blocks (STB_GLOBAL)
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
struct page *fscrypt_encrypt_pagecache_blocks(struct page *page, unsigned int len, unsigned int offs, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (ffff80001040b1d0)
Location: fs/crypto/crypto.c:217
Inline: False
Direct callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
**Symbols:**

```
ffff80001040b1d0-ffff80001040b36c: fscrypt_encrypt_pagecache_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct page *fscrypt_encrypt_pagecache_blocks(struct page *page, unsigned int len, unsigned int offs, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (c05d83e4)
Location: fs/crypto/crypto.c:217
Inline: False
Direct callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
**Symbols:**

```
c05d83e4-c05d85c0: fscrypt_encrypt_pagecache_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct page *fscrypt_encrypt_pagecache_blocks(struct page *page, unsigned int len, unsigned int offs, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (c000000000517d00)
Location: fs/crypto/crypto.c:217
Inline: False
Direct callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
**Symbols:**

```
c000000000517d00-c000000000517f34: fscrypt_encrypt_pagecache_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct page *fscrypt_encrypt_pagecache_blocks(struct page *page, unsigned int len, unsigned int offs, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (ffffffe0002b4ebc)
Location: fs/crypto/crypto.c:217
Inline: False
Direct callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
**Symbols:**

```
ffffffe0002b4ebc-ffffffe0002b4fde: fscrypt_encrypt_pagecache_blocks (STB_GLOBAL)
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
struct page *fscrypt_encrypt_pagecache_blocks(struct page *page, unsigned int len, unsigned int offs, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (ffffffff81342fd0)
Location: fs/crypto/crypto.c:217
Inline: False
Direct callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
**Symbols:**

```
ffffffff81342fd0-ffffffff81343109: fscrypt_encrypt_pagecache_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct page *fscrypt_encrypt_pagecache_blocks(struct page *page, unsigned int len, unsigned int offs, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (ffffffff81333cb0)
Location: fs/crypto/crypto.c:217
Inline: False
Direct callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
**Symbols:**

```
ffffffff81333cb0-ffffffff81333de9: fscrypt_encrypt_pagecache_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct page *fscrypt_encrypt_pagecache_blocks(struct page *page, unsigned int len, unsigned int offs, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (ffffffff81340aa0)
Location: fs/crypto/crypto.c:217
Inline: False
Direct callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
**Symbols:**

```
ffffffff81340aa0-ffffffff81340bd9: fscrypt_encrypt_pagecache_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct page *fscrypt_encrypt_pagecache_blocks(struct page *page, unsigned int len, unsigned int offs, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (ffffffff81353da0)
Location: fs/crypto/crypto.c:217
Inline: False
Direct callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
**Symbols:**

```
ffffffff81353da0-ffffffff81353ed9: fscrypt_encrypt_pagecache_blocks (STB_GLOBAL)
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
