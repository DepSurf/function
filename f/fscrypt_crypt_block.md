# Function: <code>fscrypt_crypt_block</code>

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
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int fscrypt_crypt_block(const struct inode *inode, fscrypt_direction_t rw, u64 lblk_num, struct page *src_page, struct page *dest_page, unsigned int len, unsigned int offs, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/crypto.c (0)
Location: fs/crypto/crypto.c:152
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_decrypt_block_inplace
  - fs/crypto/crypto.c:fscrypt_decrypt_pagecache_blocks
  - fs/crypto/crypto.c:fscrypt_encrypt_block_inplace
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
  - fs/crypto/bio.c:fscrypt_zeroout_range
```
**Symbols:**

```
ffffffff81337178-ffffffff813371b6: fscrypt_crypt_block.cold (STB_LOCAL)
ffffffff81336bc0-ffffffff81336e0e: fscrypt_crypt_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int fscrypt_crypt_block(const struct inode *inode, fscrypt_direction_t rw, u64 lblk_num, struct page *src_page, struct page *dest_page, unsigned int len, unsigned int offs, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/crypto.c (0)
Location: fs/crypto/crypto.c:152
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_decrypt_block_inplace
  - fs/crypto/crypto.c:fscrypt_decrypt_pagecache_blocks
  - fs/crypto/crypto.c:fscrypt_encrypt_block_inplace
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
  - fs/crypto/bio.c:fscrypt_zeroout_range
```
**Symbols:**

```
ffffffff8134ad48-ffffffff8134ad7d: fscrypt_crypt_block.cold (STB_LOCAL)
ffffffff8134a790-ffffffff8134a9e4: fscrypt_crypt_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int fscrypt_crypt_block(const struct inode *inode, fscrypt_direction_t rw, u64 lblk_num, struct page *src_page, struct page *dest_page, unsigned int len, unsigned int offs, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/crypto.c (0)
Location: fs/crypto/crypto.c:93
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_decrypt_block_inplace
  - fs/crypto/crypto.c:fscrypt_decrypt_pagecache_blocks
  - fs/crypto/crypto.c:fscrypt_encrypt_block_inplace
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
  - fs/crypto/bio.c:fscrypt_zeroout_range
```
**Symbols:**

```
ffffffff813904b8-ffffffff813904ed: fscrypt_crypt_block.cold (STB_LOCAL)
ffffffff8138fef0-ffffffff8139013f: fscrypt_crypt_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int fscrypt_crypt_block(const struct inode *inode, fscrypt_direction_t rw, u64 lblk_num, struct page *src_page, struct page *dest_page, unsigned int len, unsigned int offs, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/crypto.c (0)
Location: fs/crypto/crypto.c:93
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_decrypt_block_inplace
  - fs/crypto/crypto.c:fscrypt_decrypt_pagecache_blocks
  - fs/crypto/crypto.c:fscrypt_encrypt_block_inplace
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
  - fs/crypto/bio.c:fscrypt_zeroout_range
```
**Symbols:**

```
ffffffff81bead69-ffffffff81bead9e: fscrypt_crypt_block.cold (STB_LOCAL)
ffffffff813a1530-ffffffff813a177f: fscrypt_crypt_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int fscrypt_crypt_block(const struct inode *inode, fscrypt_direction_t rw, u64 lblk_num, struct page *src_page, struct page *dest_page, unsigned int len, unsigned int offs, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/crypto.c (0)
Location: fs/crypto/crypto.c:93
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_decrypt_block_inplace
  - fs/crypto/crypto.c:fscrypt_decrypt_pagecache_blocks
  - fs/crypto/crypto.c:fscrypt_encrypt_block_inplace
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
  - fs/crypto/bio.c:fscrypt_zeroout_range
```
**Symbols:**

```
ffffffff81bdcdb6-ffffffff81bdcdeb: fscrypt_crypt_block.cold (STB_LOCAL)
ffffffff813a86c0-ffffffff813a8912: fscrypt_crypt_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int fscrypt_crypt_block(const struct inode *inode, fscrypt_direction_t rw, u64 lblk_num, struct page *src_page, struct page *dest_page, unsigned int len, unsigned int offs, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/crypto.c (0)
Location: fs/crypto/crypto.c:93
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_decrypt_block_inplace
  - fs/crypto/crypto.c:fscrypt_decrypt_pagecache_blocks
  - fs/crypto/crypto.c:fscrypt_encrypt_block_inplace
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
  - fs/crypto/bio.c:fscrypt_zeroout_range
```
**Symbols:**

```
ffffffff81cc619e-ffffffff81cc61d3: fscrypt_crypt_block.cold (STB_LOCAL)
ffffffff813f7e00-ffffffff813f8052: fscrypt_crypt_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int fscrypt_crypt_block(const struct inode *inode, fscrypt_direction_t rw, u64 lblk_num, struct page *src_page, struct page *dest_page, unsigned int len, unsigned int offs, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/crypto.c (0)
Location: fs/crypto/crypto.c:101
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_decrypt_block_inplace
  - fs/crypto/crypto.c:fscrypt_decrypt_pagecache_blocks
  - fs/crypto/crypto.c:fscrypt_encrypt_block_inplace
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
  - fs/crypto/bio.c:fscrypt_zeroout_range
```
**Symbols:**

```
ffffffff81e78412-ffffffff81e7844b: fscrypt_crypt_block.cold (STB_LOCAL)
ffffffff8146ab20-ffffffff8146ae1e: fscrypt_crypt_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int fscrypt_crypt_block(const struct inode *inode, fscrypt_direction_t rw, u64 lblk_num, struct page *src_page, struct page *dest_page, unsigned int len, unsigned int offs, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (ffffffff814fbc40)
Location: fs/crypto/crypto.c:101
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_decrypt_block_inplace
  - fs/crypto/crypto.c:fscrypt_decrypt_pagecache_blocks
  - fs/crypto/crypto.c:fscrypt_encrypt_block_inplace
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
  - fs/crypto/bio.c:fscrypt_zeroout_range
```
**Symbols:**

```
ffffffff814fbc40-ffffffff814fbf53: fscrypt_crypt_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int fscrypt_crypt_block(const struct inode *inode, fscrypt_direction_t rw, u64 lblk_num, struct page *src_page, struct page *dest_page, unsigned int len, unsigned int offs, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (ffffffff81532f70)
Location: fs/crypto/crypto.c:101
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_decrypt_block_inplace
  - fs/crypto/crypto.c:fscrypt_decrypt_pagecache_blocks
  - fs/crypto/crypto.c:fscrypt_encrypt_block_inplace
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
  - fs/crypto/bio.c:fscrypt_zeroout_range
```
**Symbols:**

```
ffffffff81532f70-ffffffff81533283: fscrypt_crypt_block (STB_GLOBAL)
```
</details>
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
int fscrypt_crypt_block(const struct inode *inode, fscrypt_direction_t rw, u64 lblk_num, struct page *src_page, struct page *dest_page, unsigned int len, unsigned int offs, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (ffff80001040af80)
Location: fs/crypto/crypto.c:152
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_decrypt_block_inplace
  - fs/crypto/crypto.c:fscrypt_decrypt_pagecache_blocks
  - fs/crypto/crypto.c:fscrypt_encrypt_block_inplace
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
  - fs/crypto/bio.c:fscrypt_zeroout_range
```
**Symbols:**

```
ffff80001040af80-ffff80001040b1d0: fscrypt_crypt_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int fscrypt_crypt_block(const struct inode *inode, fscrypt_direction_t rw, u64 lblk_num, struct page *src_page, struct page *dest_page, unsigned int len, unsigned int offs, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (c05d8110)
Location: fs/crypto/crypto.c:152
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_decrypt_block_inplace
  - fs/crypto/crypto.c:fscrypt_decrypt_pagecache_blocks
  - fs/crypto/crypto.c:fscrypt_encrypt_block_inplace
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
  - fs/crypto/bio.c:fscrypt_zeroout_range
```
**Symbols:**

```
c05d8110-c05d83e4: fscrypt_crypt_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int fscrypt_crypt_block(const struct inode *inode, fscrypt_direction_t rw, u64 lblk_num, struct page *src_page, struct page *dest_page, unsigned int len, unsigned int offs, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (c000000000517a10)
Location: fs/crypto/crypto.c:152
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_decrypt_block_inplace
  - fs/crypto/crypto.c:fscrypt_decrypt_pagecache_blocks
  - fs/crypto/crypto.c:fscrypt_encrypt_block_inplace
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
  - fs/crypto/bio.c:fscrypt_zeroout_range
```
**Symbols:**

```
c000000000517a10-c000000000517d00: fscrypt_crypt_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int fscrypt_crypt_block(const struct inode *inode, fscrypt_direction_t rw, u64 lblk_num, struct page *src_page, struct page *dest_page, unsigned int len, unsigned int offs, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (ffffffe0002b4cc4)
Location: fs/crypto/crypto.c:152
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_decrypt_block_inplace
  - fs/crypto/crypto.c:fscrypt_decrypt_pagecache_blocks
  - fs/crypto/crypto.c:fscrypt_encrypt_block_inplace
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
  - fs/crypto/bio.c:fscrypt_zeroout_range
```
**Symbols:**

```
ffffffe0002b4cc4-ffffffe0002b4ebc: fscrypt_crypt_block (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int fscrypt_crypt_block(const struct inode *inode, fscrypt_direction_t rw, u64 lblk_num, struct page *src_page, struct page *dest_page, unsigned int len, unsigned int offs, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/crypto.c (0)
Location: fs/crypto/crypto.c:152
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_decrypt_block_inplace
  - fs/crypto/crypto.c:fscrypt_decrypt_pagecache_blocks
  - fs/crypto/crypto.c:fscrypt_encrypt_block_inplace
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
  - fs/crypto/bio.c:fscrypt_zeroout_range
```
**Symbols:**

```
ffffffff81343328-ffffffff8134335d: fscrypt_crypt_block.cold (STB_LOCAL)
ffffffff81342d70-ffffffff81342fc4: fscrypt_crypt_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int fscrypt_crypt_block(const struct inode *inode, fscrypt_direction_t rw, u64 lblk_num, struct page *src_page, struct page *dest_page, unsigned int len, unsigned int offs, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/crypto.c (0)
Location: fs/crypto/crypto.c:152
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_decrypt_block_inplace
  - fs/crypto/crypto.c:fscrypt_decrypt_pagecache_blocks
  - fs/crypto/crypto.c:fscrypt_encrypt_block_inplace
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
  - fs/crypto/bio.c:fscrypt_zeroout_range
```
**Symbols:**

```
ffffffff81334008-ffffffff8133403d: fscrypt_crypt_block.cold (STB_LOCAL)
ffffffff81333a50-ffffffff81333ca4: fscrypt_crypt_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int fscrypt_crypt_block(const struct inode *inode, fscrypt_direction_t rw, u64 lblk_num, struct page *src_page, struct page *dest_page, unsigned int len, unsigned int offs, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/crypto.c (0)
Location: fs/crypto/crypto.c:152
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_decrypt_block_inplace
  - fs/crypto/crypto.c:fscrypt_decrypt_pagecache_blocks
  - fs/crypto/crypto.c:fscrypt_encrypt_block_inplace
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
  - fs/crypto/bio.c:fscrypt_zeroout_range
```
**Symbols:**

```
ffffffff81340df8-ffffffff81340e2d: fscrypt_crypt_block.cold (STB_LOCAL)
ffffffff81340840-ffffffff81340a94: fscrypt_crypt_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int fscrypt_crypt_block(const struct inode *inode, fscrypt_direction_t rw, u64 lblk_num, struct page *src_page, struct page *dest_page, unsigned int len, unsigned int offs, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/crypto.c (0)
Location: fs/crypto/crypto.c:152
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_decrypt_block_inplace
  - fs/crypto/crypto.c:fscrypt_decrypt_pagecache_blocks
  - fs/crypto/crypto.c:fscrypt_encrypt_block_inplace
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
  - fs/crypto/bio.c:fscrypt_zeroout_range
```
**Symbols:**

```
ffffffff813540f8-ffffffff8135412d: fscrypt_crypt_block.cold (STB_LOCAL)
ffffffff81353b40-ffffffff81353d94: fscrypt_crypt_block (STB_GLOBAL)
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
