# Function: <code>fscrypt_encrypt_page</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct page *fscrypt_encrypt_page(struct inode *inode, struct page *plaintext_page, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (ffffffff81288c60)
Location: fs/crypto/crypto.c:230
Inline: False
Direct callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
**Symbols:**

```
ffffffff81288c60-ffffffff81288d52: fscrypt_encrypt_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct page *fscrypt_encrypt_page(const struct inode *inode, struct page *page, unsigned int len, unsigned int offs, u64 lblk_num, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (ffffffff8129d8b0)
Location: fs/crypto/crypto.c:248
Inline: True
Direct callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
**Symbols:**

```
ffffffff8129d8b0-ffffffff8129da1a: fscrypt_encrypt_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct page *fscrypt_encrypt_page(const struct inode *inode, struct page *page, unsigned int len, unsigned int offs, u64 lblk_num, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (ffffffff812ac570)
Location: fs/crypto/crypto.c:249
Inline: True
Direct callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
**Symbols:**

```
ffffffff812ac570-ffffffff812ac6cf: fscrypt_encrypt_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct page *fscrypt_encrypt_page(const struct inode *inode, struct page *page, unsigned int len, unsigned int offs, u64 lblk_num, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (ffffffff812cfd90)
Location: fs/crypto/crypto.c:229
Inline: False
Direct callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
**Symbols:**

```
ffffffff812cfd90-ffffffff812cfeef: fscrypt_encrypt_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct page *fscrypt_encrypt_page(const struct inode *inode, struct page *page, unsigned int len, unsigned int offs, u64 lblk_num, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (ffffffff812fa650)
Location: fs/crypto/crypto.c:233
Inline: False
Direct callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
**Symbols:**

```
ffffffff812fa650-ffffffff812fa7d0: fscrypt_encrypt_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct page *fscrypt_encrypt_page(const struct inode *inode, struct page *page, unsigned int len, unsigned int offs, u64 lblk_num, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (ffffffff8130f9d0)
Location: fs/crypto/crypto.c:235
Inline: False
Direct callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
**Symbols:**

```
ffffffff8130f9d0-ffffffff8130fb50: fscrypt_encrypt_page (STB_GLOBAL)
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
<code>struct page *page</code>
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
<b>Param removed. </b>
<code>struct page *plaintext_page</code>
</li>
<li>
<b>Param reordered. </b>
<code>inode, plaintext_page, gfp_flags</code> ➡️ <code>inode, page, len, offs, lblk_num, gfp_flags</code>
</li>
<li>
<b>Param type changed. </b>
<code>struct inode *inode</code> ➡️ <code>const struct inode *inode</code>
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
