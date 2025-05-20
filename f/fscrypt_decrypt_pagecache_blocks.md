# Function: <code>fscrypt_decrypt_pagecache_blocks</code>

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
int fscrypt_decrypt_pagecache_blocks(struct page *page, unsigned int len, unsigned int offs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (ffffffff81336f80)
Location: fs/crypto/crypto.c:301
Inline: False
Direct callers:
  - fs/crypto/bio.c:__fscrypt_decrypt_bio
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
```
**Symbols:**

```
ffffffff81336f80-ffffffff8133706e: fscrypt_decrypt_pagecache_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int fscrypt_decrypt_pagecache_blocks(struct page *page, unsigned int len, unsigned int offs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (ffffffff8134ab60)
Location: fs/crypto/crypto.c:299
Inline: False
Direct callers:
  - fs/crypto/bio.c:__fscrypt_decrypt_bio
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
```
**Symbols:**

```
ffffffff8134ab60-ffffffff8134ac4e: fscrypt_decrypt_pagecache_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int fscrypt_decrypt_pagecache_blocks(struct page *page, unsigned int len, unsigned int offs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (ffffffff813902d0)
Location: fs/crypto/crypto.c:247
Inline: False
Direct callers:
  - fs/buffer.c:decrypt_bh
  - fs/crypto/bio.c:fscrypt_decrypt_bio
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
```
**Symbols:**

```
ffffffff813902d0-ffffffff813903be: fscrypt_decrypt_pagecache_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int fscrypt_decrypt_pagecache_blocks(struct page *page, unsigned int len, unsigned int offs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (ffffffff813a1910)
Location: fs/crypto/crypto.c:247
Inline: False
Direct callers:
  - fs/buffer.c:decrypt_bh
  - fs/crypto/bio.c:fscrypt_decrypt_bio
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
```
**Symbols:**

```
ffffffff813a1910-ffffffff813a19fe: fscrypt_decrypt_pagecache_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int fscrypt_decrypt_pagecache_blocks(struct page *page, unsigned int len, unsigned int offs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (ffffffff813a8ab0)
Location: fs/crypto/crypto.c:247
Inline: False
Direct callers:
  - fs/buffer.c:decrypt_bh
  - fs/crypto/bio.c:fscrypt_decrypt_bio
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
```
**Symbols:**

```
ffffffff813a8ab0-ffffffff813a8b9e: fscrypt_decrypt_pagecache_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int fscrypt_decrypt_pagecache_blocks(struct page *page, unsigned int len, unsigned int offs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/crypto.c (0)
Location: fs/crypto/crypto.c:247
Inline: False
Direct callers:
  - fs/buffer.c:decrypt_bh
  - fs/crypto/bio.c:fscrypt_decrypt_bio
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
```
**Symbols:**

```
ffffffff81cc624c-ffffffff81cc62d0: fscrypt_decrypt_pagecache_blocks.cold (STB_LOCAL)
ffffffff813f8200-ffffffff813f830e: fscrypt_decrypt_pagecache_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int fscrypt_decrypt_pagecache_blocks(struct page *page, unsigned int len, unsigned int offs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/crypto.c (0)
Location: fs/crypto/crypto.c:255
Inline: False
Direct callers:
  - fs/buffer.c:decrypt_bh
  - fs/crypto/bio.c:fscrypt_decrypt_bio
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
```
**Symbols:**

```
ffffffff81e78643-ffffffff81e787c7: fscrypt_decrypt_pagecache_blocks.cold (STB_LOCAL)
ffffffff8146aee0-ffffffff8146af43: fscrypt_decrypt_pagecache_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int fscrypt_decrypt_pagecache_blocks(struct page *page, unsigned int len, unsigned int offs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/crypto.c (0)
Location: fs/crypto/crypto.c:255
Inline: False
Direct callers:
  - fs/buffer.c:decrypt_bh
  - fs/crypto/bio.c:fscrypt_decrypt_bio
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
```
**Symbols:**

```
ffffffff8206a401-ffffffff8206a585: fscrypt_decrypt_pagecache_blocks.cold (STB_LOCAL)
ffffffff814fc050-ffffffff814fc0b3: fscrypt_decrypt_pagecache_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int fscrypt_decrypt_pagecache_blocks(struct folio *folio, size_t len, size_t offs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/crypto.c (0)
Location: fs/crypto/crypto.c:254
Inline: False
Direct callers:
  - fs/buffer.c:decrypt_bh
  - fs/crypto/bio.c:fscrypt_decrypt_bio
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
```
**Symbols:**

```
ffffffff820ea257-ffffffff820ea304: fscrypt_decrypt_pagecache_blocks.cold (STB_LOCAL)
ffffffff815334c0-ffffffff81533624: fscrypt_decrypt_pagecache_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int fscrypt_decrypt_pagecache_blocks(struct folio *folio, size_t len, size_t offs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/crypto.c (0)
Location: fs/crypto/crypto.c:266
Inline: False
Direct callers:
  - fs/buffer.c:decrypt_bh
  - fs/crypto/bio.c:fscrypt_decrypt_bio
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
```
**Symbols:**

```
ffffffff821c6d0c-ffffffff821c6db9: fscrypt_decrypt_pagecache_blocks.cold (STB_LOCAL)
ffffffff81568420-ffffffff81568588: fscrypt_decrypt_pagecache_blocks (STB_GLOBAL)
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
int fscrypt_decrypt_pagecache_blocks(struct page *page, unsigned int len, unsigned int offs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (ffff80001040b3e0)
Location: fs/crypto/crypto.c:299
Inline: False
Direct callers:
  - fs/crypto/bio.c:__fscrypt_decrypt_bio
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
```
**Symbols:**

```
ffff80001040b3e0-ffff80001040b4fc: fscrypt_decrypt_pagecache_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int fscrypt_decrypt_pagecache_blocks(struct page *page, unsigned int len, unsigned int offs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (c05d8600)
Location: fs/crypto/crypto.c:299
Inline: False
Direct callers:
  - fs/crypto/bio.c:__fscrypt_decrypt_bio
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
```
**Symbols:**

```
c05d8600-c05d876c: fscrypt_decrypt_pagecache_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int fscrypt_decrypt_pagecache_blocks(struct page *page, unsigned int len, unsigned int offs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (c000000000517f80)
Location: fs/crypto/crypto.c:299
Inline: False
Direct callers:
  - fs/crypto/bio.c:__fscrypt_decrypt_bio
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
```
**Symbols:**

```
c000000000517f80-c000000000518118: fscrypt_decrypt_pagecache_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int fscrypt_decrypt_pagecache_blocks(struct page *page, unsigned int len, unsigned int offs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (ffffffe0002b5034)
Location: fs/crypto/crypto.c:299
Inline: False
Direct callers:
  - fs/crypto/bio.c:__fscrypt_decrypt_bio
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
```
**Symbols:**

```
ffffffe0002b5034-ffffffe0002b5108: fscrypt_decrypt_pagecache_blocks (STB_GLOBAL)
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
int fscrypt_decrypt_pagecache_blocks(struct page *page, unsigned int len, unsigned int offs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (ffffffff81343140)
Location: fs/crypto/crypto.c:299
Inline: False
Direct callers:
  - fs/crypto/bio.c:__fscrypt_decrypt_bio
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
```
**Symbols:**

```
ffffffff81343140-ffffffff8134322e: fscrypt_decrypt_pagecache_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int fscrypt_decrypt_pagecache_blocks(struct page *page, unsigned int len, unsigned int offs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (ffffffff81333e20)
Location: fs/crypto/crypto.c:299
Inline: False
Direct callers:
  - fs/crypto/bio.c:__fscrypt_decrypt_bio
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
```
**Symbols:**

```
ffffffff81333e20-ffffffff81333f0e: fscrypt_decrypt_pagecache_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int fscrypt_decrypt_pagecache_blocks(struct page *page, unsigned int len, unsigned int offs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (ffffffff81340c10)
Location: fs/crypto/crypto.c:299
Inline: False
Direct callers:
  - fs/crypto/bio.c:__fscrypt_decrypt_bio
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
```
**Symbols:**

```
ffffffff81340c10-ffffffff81340cfe: fscrypt_decrypt_pagecache_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int fscrypt_decrypt_pagecache_blocks(struct page *page, unsigned int len, unsigned int offs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (ffffffff81353f10)
Location: fs/crypto/crypto.c:299
Inline: False
Direct callers:
  - fs/crypto/bio.c:__fscrypt_decrypt_bio
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
```
**Symbols:**

```
ffffffff81353f10-ffffffff81353ffe: fscrypt_decrypt_pagecache_blocks (STB_GLOBAL)
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct folio *folio</code>
</li>
<li>
<b>Param removed. </b>
<code>struct page *page</code>
</li>
<li>
<b>Param type changed. </b>
<code>unsigned int len</code> ➡️ <code>size_t len</code>
</li>
<li>
<b>Param type changed. </b>
<code>unsigned int offs</code> ➡️ <code>size_t offs</code>
</li>
</ul>
</details>
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
