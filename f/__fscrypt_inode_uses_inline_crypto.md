# Function: <code>__fscrypt_inode_uses_inline_crypto</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool __fscrypt_inode_uses_inline_crypto(const struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/inline_crypt.c (ffffffff813a72cc)
Location: fs/crypto/inline_crypt.c:206
Inline: True
Inline callers:
  - fs/crypto/inline_crypt.c:fscrypt_mergeable_bio
Direct callers:
  - fs/buffer.c:end_buffer_async_read_io
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
**Symbols:**

```
ffffffff813a7190-ffffffff813a71a6: __fscrypt_inode_uses_inline_crypto (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool __fscrypt_inode_uses_inline_crypto(const struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/inline_crypt.c (ffffffff813ae32d)
Location: fs/crypto/inline_crypt.c:206
Inline: True
Inline callers:
  - fs/crypto/inline_crypt.c:fscrypt_mergeable_bio
Direct callers:
  - fs/buffer.c:end_buffer_async_read_io
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
**Symbols:**

```
ffffffff813ae1f0-ffffffff813ae206: __fscrypt_inode_uses_inline_crypto (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool __fscrypt_inode_uses_inline_crypto(const struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/crypto/inline_crypt.c (ffffffff813fdfb9)
Location: fs/crypto/inline_crypt.c:206
Inline: True
Inline callers:
  - fs/crypto/inline_crypt.c:fscrypt_mergeable_bio
Direct callers:
  - fs/buffer.c:end_buffer_async_read_io
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
**Symbols:**

```
ffffffff81cc6ae2-ffffffff81cc6b02: __fscrypt_inode_uses_inline_crypto.cold (STB_LOCAL)
ffffffff813fde60-ffffffff813fde7c: __fscrypt_inode_uses_inline_crypto (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool __fscrypt_inode_uses_inline_crypto(const struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/crypto/inline_crypt.c (ffffffff814717cb)
Location: fs/crypto/inline_crypt.c:238
Inline: True
Inline callers:
  - fs/crypto/inline_crypt.c:fscrypt_dio_supported
  - fs/crypto/inline_crypt.c:fscrypt_mergeable_bio
  - fs/crypto/inline_crypt.c:fscrypt_set_bio_crypt_ctx
Direct callers:
  - fs/buffer.c:end_buffer_async_read_io
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
**Symbols:**

```
ffffffff81e78fd9-ffffffff81e79003: __fscrypt_inode_uses_inline_crypto.cold (STB_LOCAL)
ffffffff81471730-ffffffff81471756: __fscrypt_inode_uses_inline_crypto (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool __fscrypt_inode_uses_inline_crypto(const struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/crypto/inline_crypt.c (ffffffff81503586)
Location: fs/crypto/inline_crypt.c:229
Inline: True
Inline callers:
  - fs/crypto/inline_crypt.c:fscrypt_mergeable_bio
  - fs/crypto/inline_crypt.c:fscrypt_set_bio_crypt_ctx
Direct callers:
  - fs/buffer.c:end_buffer_async_read_io
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
**Symbols:**

```
ffffffff8206a8d7-ffffffff8206a901: __fscrypt_inode_uses_inline_crypto.cold (STB_LOCAL)
ffffffff81503260-ffffffff81503286: __fscrypt_inode_uses_inline_crypto (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool __fscrypt_inode_uses_inline_crypto(const struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/crypto/inline_crypt.c (ffffffff8153ae36)
Location: fs/crypto/inline_crypt.c:229
Inline: True
Inline callers:
  - fs/crypto/inline_crypt.c:fscrypt_mergeable_bio
  - fs/crypto/inline_crypt.c:fscrypt_set_bio_crypt_ctx
Direct callers:
  - fs/buffer.c:end_buffer_async_read_io
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/page-io.c:ext4_bio_write_folio
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
**Symbols:**

```
ffffffff820ea718-ffffffff820ea742: __fscrypt_inode_uses_inline_crypto.cold (STB_LOCAL)
ffffffff8153ab10-ffffffff8153ab36: __fscrypt_inode_uses_inline_crypto (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool __fscrypt_inode_uses_inline_crypto(const struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/crypto/inline_crypt.c (ffffffff81570156)
Location: fs/crypto/inline_crypt.c:229
Inline: True
Inline callers:
  - fs/crypto/inline_crypt.c:fscrypt_mergeable_bio
  - fs/crypto/inline_crypt.c:fscrypt_set_bio_crypt_ctx
Direct callers:
  - fs/buffer.c:end_buffer_async_read_io
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/page-io.c:ext4_bio_write_folio
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
**Symbols:**

```
ffffffff821c73e2-ffffffff821c740c: __fscrypt_inode_uses_inline_crypto.cold (STB_LOCAL)
ffffffff8156fcd0-ffffffff8156fcf6: __fscrypt_inode_uses_inline_crypto (STB_GLOBAL)
```
</details>
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
