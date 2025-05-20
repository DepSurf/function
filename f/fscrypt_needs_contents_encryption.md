# Function: <code>fscrypt_needs_contents_encryption</code>

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
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81369721)
Location: include/linux/fscrypt.h:97
Inline: True
Inline callers:
  - fs/buffer.c:end_buffer_async_read_io
```
```
In fs/crypto/bio.c (ffffffff813a6e1f)
Location: include/linux/fscrypt.h:97
Inline: True
Inline callers:
  - fs/crypto/bio.c:fscrypt_zeroout_range
```
```
In fs/crypto/inline_crypt.c (ffffffff813a727f)
Location: include/linux/fscrypt.h:97
Inline: True
Inline callers:
  - fs/crypto/inline_crypt.c:fscrypt_mergeable_bio
```
```
In fs/ext4/inode.c (ffffffff8140b8ac)
Location: include/linux/fscrypt.h:97
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/page-io.c (ffffffff8142ba0c)
Location: include/linux/fscrypt.h:97
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/readpage.c (ffffffff8142c827)
Location: include/linux/fscrypt.h:97
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
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
In fs/buffer.c (ffffffff8136f881)
Location: include/linux/fscrypt.h:97
Inline: True
Inline callers:
  - fs/buffer.c:end_buffer_async_read_io
```
```
In fs/crypto/bio.c (ffffffff813ade8f)
Location: include/linux/fscrypt.h:97
Inline: True
Inline callers:
  - fs/crypto/bio.c:fscrypt_zeroout_range
```
```
In fs/crypto/inline_crypt.c (ffffffff813ae2e3)
Location: include/linux/fscrypt.h:97
Inline: True
Inline callers:
  - fs/crypto/inline_crypt.c:fscrypt_mergeable_bio
```
```
In fs/ext4/inode.c (ffffffff81411a62)
Location: include/linux/fscrypt.h:97
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/page-io.c (ffffffff81432629)
Location: include/linux/fscrypt.h:97
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/readpage.c (ffffffff814334f0)
Location: include/linux/fscrypt.h:97
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
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
In fs/buffer.c (ffffffff813be321)
Location: include/linux/fscrypt.h:198
Inline: True
Inline callers:
  - fs/buffer.c:end_buffer_async_read_io
```
```
In fs/crypto/bio.c (ffffffff813fd853)
Location: include/linux/fscrypt.h:198
Inline: True
Inline callers:
  - fs/crypto/bio.c:fscrypt_zeroout_range
```
```
In fs/crypto/inline_crypt.c (ffffffff813fdf69)
Location: include/linux/fscrypt.h:198
Inline: True
Inline callers:
  - fs/crypto/inline_crypt.c:fscrypt_mergeable_bio
```
```
In fs/ext4/inode.c (ffffffff8146491d)
Location: include/linux/fscrypt.h:198
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/page-io.c (ffffffff81485ee9)
Location: include/linux/fscrypt.h:198
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/readpage.c (ffffffff81486d21)
Location: include/linux/fscrypt.h:198
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
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
In fs/buffer.c (ffffffff81445f1c)
Location: include/linux/fscrypt.h:206
Inline: True
Inline callers:
  - fs/buffer.c:end_buffer_async_read_io
```
```
In fs/crypto/bio.c (ffffffff8147104f)
Location: include/linux/fscrypt.h:206
Inline: True
Inline callers:
  - fs/crypto/bio.c:fscrypt_zeroout_range
```
```
In fs/crypto/inline_crypt.c (ffffffff81471794)
Location: include/linux/fscrypt.h:206
Inline: True
Inline callers:
  - fs/crypto/inline_crypt.c:fscrypt_dio_supported
  - fs/crypto/inline_crypt.c:fscrypt_mergeable_bio
  - fs/crypto/inline_crypt.c:fscrypt_set_bio_crypt_ctx
```
```
In fs/ext4/inode.c (ffffffff814e3ff4)
Location: include/linux/fscrypt.h:206
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/page-io.c (ffffffff8150947c)
Location: include/linux/fscrypt.h:206
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/readpage.c (ffffffff8150a76a)
Location: include/linux/fscrypt.h:206
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
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
In fs/buffer.c (ffffffff814d465c)
Location: include/linux/fscrypt.h:203
Inline: True
Inline callers:
  - fs/buffer.c:end_buffer_async_read_io
```
```
In fs/crypto/bio.c (ffffffff81502b3f)
Location: include/linux/fscrypt.h:203
Inline: True
Inline callers:
  - fs/crypto/bio.c:fscrypt_zeroout_range
```
```
In fs/crypto/inline_crypt.c (ffffffff81503529)
Location: include/linux/fscrypt.h:203
Inline: True
Inline callers:
  - fs/crypto/inline_crypt.c:fscrypt_mergeable_bio
  - fs/crypto/inline_crypt.c:fscrypt_set_bio_crypt_ctx
```
```
In fs/ext4/inode.c (ffffffff8157d45d)
Location: include/linux/fscrypt.h:203
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/page-io.c (ffffffff815a404e)
Location: include/linux/fscrypt.h:203
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/readpage.c (ffffffff815a5220)
Location: include/linux/fscrypt.h:203
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
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
In fs/buffer.c (ffffffff8150adb1)
Location: include/linux/fscrypt.h:203
Inline: True
Inline callers:
  - fs/buffer.c:end_buffer_async_read_io
```
```
In fs/crypto/bio.c (ffffffff8153a11f)
Location: include/linux/fscrypt.h:203
Inline: True
Inline callers:
  - fs/crypto/bio.c:fscrypt_zeroout_range
```
```
In fs/crypto/inline_crypt.c (ffffffff8153add9)
Location: include/linux/fscrypt.h:203
Inline: True
Inline callers:
  - fs/crypto/inline_crypt.c:fscrypt_mergeable_bio
  - fs/crypto/inline_crypt.c:fscrypt_set_bio_crypt_ctx
```
```
In fs/ext4/inode.c (ffffffff815b48c5)
Location: include/linux/fscrypt.h:203
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/page-io.c (ffffffff815dab08)
Location: include/linux/fscrypt.h:203
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_folio
```
```
In fs/ext4/readpage.c (ffffffff815dbbc3)
Location: include/linux/fscrypt.h:203
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
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
In fs/buffer.c (ffffffff8153fc71)
Location: include/linux/fscrypt.h:218
Inline: True
Inline callers:
  - fs/buffer.c:end_buffer_async_read_io
```
```
In fs/crypto/bio.c (ffffffff8156f499)
Location: include/linux/fscrypt.h:218
Inline: True
Inline callers:
  - fs/crypto/bio.c:fscrypt_zeroout_range
```
```
In fs/crypto/inline_crypt.c (ffffffff815700f9)
Location: include/linux/fscrypt.h:218
Inline: True
Inline callers:
  - fs/crypto/inline_crypt.c:fscrypt_mergeable_bio
  - fs/crypto/inline_crypt.c:fscrypt_set_bio_crypt_ctx
```
```
In fs/ext4/inode.c (ffffffff815ed6d5)
Location: include/linux/fscrypt.h:218
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/page-io.c (ffffffff8161332c)
Location: include/linux/fscrypt.h:218
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_folio
```
```
In fs/ext4/readpage.c (ffffffff8161448a)
Location: include/linux/fscrypt.h:218
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
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
