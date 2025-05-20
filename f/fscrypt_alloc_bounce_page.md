# Function: <code>fscrypt_alloc_bounce_page</code>

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
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct page *fscrypt_alloc_bounce_page(struct fscrypt_ctx *ctx, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (ffffffff812ac5fc)
Location: fs/crypto/crypto.c:208
Inline: True
Direct callers:
  - fs/crypto/bio.c:fscrypt_zeroout_range
```
**Symbols:**

```
ffffffff812ac6d0-ffffffff812ac702: fscrypt_alloc_bounce_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct page *fscrypt_alloc_bounce_page(struct fscrypt_ctx *ctx, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (ffffffff812cfe1c)
Location: fs/crypto/crypto.c:188
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_encrypt_page
Direct callers:
  - fs/crypto/bio.c:fscrypt_zeroout_range
```
**Symbols:**

```
ffffffff812cfef0-ffffffff812cff22: fscrypt_alloc_bounce_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct page *fscrypt_alloc_bounce_page(struct fscrypt_ctx *ctx, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (ffffffff812fa6d8)
Location: fs/crypto/crypto.c:192
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_encrypt_page
Direct callers:
  - fs/crypto/bio.c:fscrypt_zeroout_range
```
**Symbols:**

```
ffffffff812fa280-ffffffff812fa2b2: fscrypt_alloc_bounce_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct page *fscrypt_alloc_bounce_page(struct fscrypt_ctx *ctx, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (ffffffff8130fa58)
Location: fs/crypto/crypto.c:194
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_encrypt_page
Direct callers:
  - fs/crypto/bio.c:fscrypt_zeroout_range
```
**Symbols:**

```
ffffffff8130f5d0-ffffffff8130f602: fscrypt_alloc_bounce_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct page *fscrypt_alloc_bounce_page(gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (ffffffff81336eb5)
Location: fs/crypto/crypto.c:117
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
Direct callers:
  - fs/crypto/bio.c:fscrypt_zeroout_range
```
**Symbols:**

```
ffffffff81336a60-ffffffff81336a79: fscrypt_alloc_bounce_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct page *fscrypt_alloc_bounce_page(gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (ffffffff8134aa95)
Location: fs/crypto/crypto.c:117
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
Direct callers:
  - fs/crypto/bio.c:fscrypt_zeroout_range
```
**Symbols:**

```
ffffffff8134a5e0-ffffffff8134a5f9: fscrypt_alloc_bounce_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct page *fscrypt_alloc_bounce_page(gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (ffffffff813901e5)
Location: fs/crypto/crypto.c:50
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
Direct callers:
  - fs/crypto/bio.c:fscrypt_zeroout_range
```
**Symbols:**

```
ffffffff8138fd80-ffffffff8138fd99: fscrypt_alloc_bounce_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct page *fscrypt_alloc_bounce_page(gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (ffffffff813a1825)
Location: fs/crypto/crypto.c:50
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
Direct callers:
  - fs/crypto/bio.c:fscrypt_zeroout_range
```
**Symbols:**

```
ffffffff813a13c0-ffffffff813a13d9: fscrypt_alloc_bounce_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct page *fscrypt_alloc_bounce_page(gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (ffffffff813a89c5)
Location: fs/crypto/crypto.c:50
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
Direct callers:
  - fs/crypto/bio.c:fscrypt_zeroout_range
```
**Symbols:**

```
ffffffff813a8550-ffffffff813a8569: fscrypt_alloc_bounce_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct page *fscrypt_alloc_bounce_page(gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (ffffffff813f811f)
Location: fs/crypto/crypto.c:50
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
Direct callers:
  - fs/crypto/bio.c:fscrypt_zeroout_range
```
**Symbols:**

```
ffffffff813f7c90-ffffffff813f7ca9: fscrypt_alloc_bounce_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct page *fscrypt_alloc_bounce_page(gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (ffffffff81e78596)
Location: fs/crypto/crypto.c:50
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
Direct callers:
  - fs/crypto/bio.c:fscrypt_zeroout_range
```
**Symbols:**

```
ffffffff8146a960-ffffffff8146a981: fscrypt_alloc_bounce_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct page *fscrypt_alloc_bounce_page(gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (ffffffff8206a354)
Location: fs/crypto/crypto.c:50
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
Direct callers:
  - fs/crypto/bio.c:fscrypt_zeroout_range
```
**Symbols:**

```
ffffffff814fb900-ffffffff814fb921: fscrypt_alloc_bounce_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct page *fscrypt_alloc_bounce_page(gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (ffffffff815333a1)
Location: fs/crypto/crypto.c:50
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
Direct callers:
  - fs/crypto/bio.c:fscrypt_zeroout_range
```
**Symbols:**

```
ffffffff81532c20-ffffffff81532c41: fscrypt_alloc_bounce_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct page *fscrypt_alloc_bounce_page(gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (ffffffff81568296)
Location: fs/crypto/crypto.c:50
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
Direct callers:
  - fs/crypto/bio.c:fscrypt_zeroout_range
```
**Symbols:**

```
ffffffff81567b10-ffffffff81567b44: fscrypt_alloc_bounce_page (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
struct page *fscrypt_alloc_bounce_page(gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (ffff80001040b278)
Location: fs/crypto/crypto.c:117
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
Direct callers:
  - fs/crypto/bio.c:fscrypt_zeroout_range
```
**Symbols:**

```
ffff80001040ad98-ffff80001040adcc: fscrypt_alloc_bounce_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct page *fscrypt_alloc_bounce_page(gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (c05d84a0)
Location: fs/crypto/crypto.c:117
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
Direct callers:
  - fs/crypto/bio.c:fscrypt_zeroout_range
```
**Symbols:**

```
c05d7f28-c05d7f54: fscrypt_alloc_bounce_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct page *fscrypt_alloc_bounce_page(gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (c000000000517df0)
Location: fs/crypto/crypto.c:117
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
Direct callers:
  - fs/crypto/bio.c:fscrypt_zeroout_range
```
**Symbols:**

```
c000000000517730-c000000000517770: fscrypt_alloc_bounce_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct page *fscrypt_alloc_bounce_page(gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (ffffffe0002b4f5a)
Location: fs/crypto/crypto.c:117
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
Direct callers:
  - fs/crypto/bio.c:fscrypt_zeroout_range
```
**Symbols:**

```
ffffffe0002b4ae4-ffffffe0002b4b16: fscrypt_alloc_bounce_page (STB_GLOBAL)
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
struct page *fscrypt_alloc_bounce_page(gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (ffffffff81343075)
Location: fs/crypto/crypto.c:117
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
Direct callers:
  - fs/crypto/bio.c:fscrypt_zeroout_range
```
**Symbols:**

```
ffffffff81342bc0-ffffffff81342bd9: fscrypt_alloc_bounce_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct page *fscrypt_alloc_bounce_page(gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (ffffffff81333d55)
Location: fs/crypto/crypto.c:117
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
Direct callers:
  - fs/crypto/bio.c:fscrypt_zeroout_range
```
**Symbols:**

```
ffffffff813338a0-ffffffff813338b9: fscrypt_alloc_bounce_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct page *fscrypt_alloc_bounce_page(gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (ffffffff81340b45)
Location: fs/crypto/crypto.c:117
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
Direct callers:
  - fs/crypto/bio.c:fscrypt_zeroout_range
```
**Symbols:**

```
ffffffff81340690-ffffffff813406a9: fscrypt_alloc_bounce_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct page *fscrypt_alloc_bounce_page(gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (ffffffff81353e45)
Location: fs/crypto/crypto.c:117
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
Direct callers:
  - fs/crypto/bio.c:fscrypt_zeroout_range
```
**Symbols:**

```
ffffffff81353990-ffffffff813539a9: fscrypt_alloc_bounce_page (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct fscrypt_ctx *ctx</code>
</li>
<li>
<b>Param reordered. </b>
<code>ctx, gfp_flags</code> ➡️ <code>gfp_flags</code>
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
