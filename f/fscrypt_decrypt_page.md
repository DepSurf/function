# Function: <code>fscrypt_decrypt_page</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int fscrypt_decrypt_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (ffffffff81288b70)
Location: fs/crypto/crypto.c:277
Inline: True
Direct callers:
  - fs/crypto/crypto.c:completion_pages
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
```
**Symbols:**

```
ffffffff81288b70-ffffffff81288bb8: fscrypt_decrypt_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int fscrypt_decrypt_page(const struct inode *inode, struct page *page, unsigned int len, unsigned int offs, u64 lblk_num);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (ffffffff8129d790)
Location: fs/crypto/crypto.c:317
Inline: True
Direct callers:
  - fs/crypto/crypto.c:completion_pages
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
```
**Symbols:**

```
ffffffff8129d790-ffffffff8129d7f4: fscrypt_decrypt_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int fscrypt_decrypt_page(const struct inode *inode, struct page *page, unsigned int len, unsigned int offs, u64 lblk_num);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (ffffffff812ac510)
Location: fs/crypto/crypto.c:318
Inline: True
Direct callers:
  - fs/crypto/bio.c:completion_pages
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
```
**Symbols:**

```
ffffffff812ac510-ffffffff812ac564: fscrypt_decrypt_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int fscrypt_decrypt_page(const struct inode *inode, struct page *page, unsigned int len, unsigned int offs, u64 lblk_num);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (ffffffff812cfd30)
Location: fs/crypto/crypto.c:298
Inline: True
Direct callers:
  - fs/crypto/bio.c:completion_pages
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
```
**Symbols:**

```
ffffffff812cfd30-ffffffff812cfd84: fscrypt_decrypt_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int fscrypt_decrypt_page(const struct inode *inode, struct page *page, unsigned int len, unsigned int offs, u64 lblk_num);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (ffffffff812fa7d0)
Location: fs/crypto/crypto.c:302
Inline: True
Direct callers:
  - fs/crypto/bio.c:__fscrypt_decrypt_bio
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
```
**Symbols:**

```
ffffffff812fa7d0-ffffffff812fa824: fscrypt_decrypt_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int fscrypt_decrypt_page(const struct inode *inode, struct page *page, unsigned int len, unsigned int offs, u64 lblk_num);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (ffffffff8130fb50)
Location: fs/crypto/crypto.c:304
Inline: True
Direct callers:
  - fs/crypto/bio.c:__fscrypt_decrypt_bio
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
```
**Symbols:**

```
ffffffff8130fb50-ffffffff8130fba4: fscrypt_decrypt_page (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
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
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct inode *inode</code>
</li>
<li>
<b>Param added. </b>
<code>unsigned int len</code>
</li>
<li>
<b>Param added. </b>
<code>unsigned int offs</code>
</li>
<li>
<b>Param added. </b>
<code>u64 lblk_num</code>
</li>
<li>
<b>Param reordered. </b>
<code>page</code> ➡️ <code>inode, page, len, offs, lblk_num</code>
</li>
</ul>
</details>
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
</ul>
