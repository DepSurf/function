# Function: <code>fscrypt_set_bio_crypt_ctx</code>

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
void fscrypt_set_bio_crypt_ctx(struct bio *bio, const struct inode *inode, u64 first_lblk, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/inline_crypt.c (ffffffff813a7440)
Location: fs/crypto/inline_crypt.c:242
Inline: True
Direct callers:
  - fs/crypto/bio.c:fscrypt_zeroout_range_inline_crypt
  - fs/crypto/inline_crypt.c:fscrypt_set_bio_crypt_ctx_bh
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
**Symbols:**

```
ffffffff813a7440-ffffffff813a74cd: fscrypt_set_bio_crypt_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void fscrypt_set_bio_crypt_ctx(struct bio *bio, const struct inode *inode, u64 first_lblk, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/inline_crypt.c (ffffffff813ae490)
Location: fs/crypto/inline_crypt.c:242
Inline: True
Direct callers:
  - fs/crypto/bio.c:fscrypt_zeroout_range_inline_crypt
  - fs/crypto/inline_crypt.c:fscrypt_set_bio_crypt_ctx_bh
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
**Symbols:**

```
ffffffff813ae490-ffffffff813ae51f: fscrypt_set_bio_crypt_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void fscrypt_set_bio_crypt_ctx(struct bio *bio, const struct inode *inode, u64 first_lblk, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/crypto/inline_crypt.c (ffffffff813fdf01)
Location: fs/crypto/inline_crypt.c:242
Inline: True
Direct callers:
  - fs/crypto/bio.c:fscrypt_zeroout_range_inline_crypt
  - fs/crypto/inline_crypt.c:fscrypt_set_bio_crypt_ctx_bh
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
**Symbols:**

```
ffffffff81cc6b02-ffffffff81cc6b17: fscrypt_set_bio_crypt_ctx.cold (STB_LOCAL)
ffffffff813fde80-ffffffff813fdf2f: fscrypt_set_bio_crypt_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void fscrypt_set_bio_crypt_ctx(struct bio *bio, const struct inode *inode, u64 first_lblk, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/inline_crypt.c (0)
Location: fs/crypto/inline_crypt.c:274
Inline: False
Direct callers:
  - fs/crypto/bio.c:fscrypt_zeroout_range_inline_crypt
  - fs/crypto/inline_crypt.c:fscrypt_set_bio_crypt_ctx_bh
  - fs/iomap/direct-io.c:iomap_dio_bio_iter
  - fs/iomap/direct-io.c:iomap_dio_zero
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
**Symbols:**

```
ffffffff81e79041-ffffffff81e79056: fscrypt_set_bio_crypt_ctx.cold (STB_LOCAL)
ffffffff81471830-ffffffff8147190c: fscrypt_set_bio_crypt_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void fscrypt_set_bio_crypt_ctx(struct bio *bio, const struct inode *inode, u64 first_lblk, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/inline_crypt.c (0)
Location: fs/crypto/inline_crypt.c:265
Inline: False
Direct callers:
  - fs/crypto/bio.c:fscrypt_zeroout_range_inline_crypt
  - fs/crypto/inline_crypt.c:fscrypt_set_bio_crypt_ctx_bh
  - fs/iomap/direct-io.c:iomap_dio_bio_iter
  - fs/iomap/direct-io.c:iomap_dio_zero
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
**Symbols:**

```
ffffffff8206a91c-ffffffff8206a931: fscrypt_set_bio_crypt_ctx.cold (STB_LOCAL)
ffffffff815033f0-ffffffff815034cc: fscrypt_set_bio_crypt_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void fscrypt_set_bio_crypt_ctx(struct bio *bio, const struct inode *inode, u64 first_lblk, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/inline_crypt.c (0)
Location: fs/crypto/inline_crypt.c:265
Inline: False
Direct callers:
  - fs/crypto/bio.c:fscrypt_zeroout_range_inline_crypt
  - fs/crypto/inline_crypt.c:fscrypt_set_bio_crypt_ctx_bh
  - fs/iomap/direct-io.c:iomap_dio_bio_iter
  - fs/iomap/direct-io.c:iomap_dio_zero
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
**Symbols:**

```
ffffffff820ea75d-ffffffff820ea772: fscrypt_set_bio_crypt_ctx.cold (STB_LOCAL)
ffffffff8153aca0-ffffffff8153ad7c: fscrypt_set_bio_crypt_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void fscrypt_set_bio_crypt_ctx(struct bio *bio, const struct inode *inode, u64 first_lblk, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/inline_crypt.c (0)
Location: fs/crypto/inline_crypt.c:267
Inline: False
Direct callers:
  - fs/crypto/bio.c:fscrypt_zeroout_range_inline_crypt
  - fs/crypto/inline_crypt.c:fscrypt_set_bio_crypt_ctx_bh
  - fs/iomap/direct-io.c:iomap_dio_bio_iter
  - fs/iomap/direct-io.c:iomap_dio_zero
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
**Symbols:**

```
ffffffff821c7427-ffffffff821c743c: fscrypt_set_bio_crypt_ctx.cold (STB_LOCAL)
ffffffff8156ff20-ffffffff8156fffc: fscrypt_set_bio_crypt_ctx (STB_GLOBAL)
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
