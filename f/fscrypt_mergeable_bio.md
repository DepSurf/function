# Function: <code>fscrypt_mergeable_bio</code>

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
<summary>In <code>5.11</code>: ✅</summary>

```c
bool fscrypt_mergeable_bio(struct bio *bio, const struct inode *inode, u64 next_lblk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/inline_crypt.c (ffffffff813a7250)
Location: fs/crypto/inline_crypt.c:320
Inline: False
Direct callers:
  - fs/crypto/bio.c:fscrypt_zeroout_range_inline_crypt
  - fs/crypto/inline_crypt.c:fscrypt_mergeable_bio_bh
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
**Symbols:**

```
ffffffff813a7250-ffffffff813a7306: fscrypt_mergeable_bio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool fscrypt_mergeable_bio(struct bio *bio, const struct inode *inode, u64 next_lblk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/inline_crypt.c (ffffffff813ae2b0)
Location: fs/crypto/inline_crypt.c:320
Inline: False
Direct callers:
  - fs/crypto/bio.c:fscrypt_zeroout_range_inline_crypt
  - fs/crypto/inline_crypt.c:fscrypt_mergeable_bio_bh
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
**Symbols:**

```
ffffffff813ae2b0-ffffffff813ae360: fscrypt_mergeable_bio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
bool fscrypt_mergeable_bio(struct bio *bio, const struct inode *inode, u64 next_lblk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/inline_crypt.c (0)
Location: fs/crypto/inline_crypt.c:320
Inline: False
Direct callers:
  - fs/crypto/bio.c:fscrypt_zeroout_range_inline_crypt
  - fs/crypto/inline_crypt.c:fscrypt_mergeable_bio_bh
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
**Symbols:**

```
ffffffff81cc6b17-ffffffff81cc6b32: fscrypt_mergeable_bio.cold (STB_LOCAL)
ffffffff813fdf30-ffffffff813fdffd: fscrypt_mergeable_bio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool fscrypt_mergeable_bio(struct bio *bio, const struct inode *inode, u64 next_lblk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/inline_crypt.c (0)
Location: fs/crypto/inline_crypt.c:356
Inline: False
Direct callers:
  - fs/crypto/bio.c:fscrypt_zeroout_range_inline_crypt
  - fs/crypto/inline_crypt.c:fscrypt_mergeable_bio_bh
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
**Symbols:**

```
ffffffff81e79056-ffffffff81e7906b: fscrypt_mergeable_bio.cold (STB_LOCAL)
ffffffff81471910-ffffffff81471a09: fscrypt_mergeable_bio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
bool fscrypt_mergeable_bio(struct bio *bio, const struct inode *inode, u64 next_lblk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/inline_crypt.c (0)
Location: fs/crypto/inline_crypt.c:347
Inline: False
Direct callers:
  - fs/crypto/bio.c:fscrypt_zeroout_range_inline_crypt
  - fs/crypto/inline_crypt.c:fscrypt_mergeable_bio_bh
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
**Symbols:**

```
ffffffff8206a931-ffffffff8206a946: fscrypt_mergeable_bio.cold (STB_LOCAL)
ffffffff815034e0-ffffffff815035d9: fscrypt_mergeable_bio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool fscrypt_mergeable_bio(struct bio *bio, const struct inode *inode, u64 next_lblk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/inline_crypt.c (0)
Location: fs/crypto/inline_crypt.c:347
Inline: False
Direct callers:
  - fs/crypto/bio.c:fscrypt_zeroout_range_inline_crypt
  - fs/crypto/inline_crypt.c:fscrypt_mergeable_bio_bh
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
**Symbols:**

```
ffffffff820ea772-ffffffff820ea787: fscrypt_mergeable_bio.cold (STB_LOCAL)
ffffffff8153ad90-ffffffff8153ae89: fscrypt_mergeable_bio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool fscrypt_mergeable_bio(struct bio *bio, const struct inode *inode, u64 next_lblk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/inline_crypt.c (0)
Location: fs/crypto/inline_crypt.c:349
Inline: False
Direct callers:
  - fs/crypto/bio.c:fscrypt_zeroout_range_inline_crypt
  - fs/crypto/inline_crypt.c:fscrypt_mergeable_bio_bh
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
**Symbols:**

```
ffffffff821c743c-ffffffff821c7451: fscrypt_mergeable_bio.cold (STB_LOCAL)
ffffffff815700b0-ffffffff815701a9: fscrypt_mergeable_bio (STB_GLOBAL)
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
