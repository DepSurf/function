# Function: <code>fscrypt_set_bio_crypt_ctx_bh</code>

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
void fscrypt_set_bio_crypt_ctx_bh(struct bio *bio, const struct buffer_head *first_bh, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/inline_crypt.c (ffffffff813a74d0)
Location: fs/crypto/inline_crypt.c:291
Inline: False
Direct callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/ext4/page-io.c:io_submit_init_bio
```
**Symbols:**

```
ffffffff813a74d0-ffffffff813a7537: fscrypt_set_bio_crypt_ctx_bh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void fscrypt_set_bio_crypt_ctx_bh(struct bio *bio, const struct buffer_head *first_bh, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/inline_crypt.c (ffffffff813ae520)
Location: fs/crypto/inline_crypt.c:291
Inline: False
Direct callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/ext4/page-io.c:ext4_bio_write_page
```
**Symbols:**

```
ffffffff813ae520-ffffffff813ae587: fscrypt_set_bio_crypt_ctx_bh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void fscrypt_set_bio_crypt_ctx_bh(struct bio *bio, const struct buffer_head *first_bh, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/inline_crypt.c (0)
Location: fs/crypto/inline_crypt.c:291
Inline: False
Direct callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/ext4/page-io.c:ext4_bio_write_page
```
**Symbols:**

```
ffffffff81cc6b77-ffffffff81cc6bbc: fscrypt_set_bio_crypt_ctx_bh.cold (STB_LOCAL)
ffffffff813fe0a0-ffffffff813fe12a: fscrypt_set_bio_crypt_ctx_bh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void fscrypt_set_bio_crypt_ctx_bh(struct bio *bio, const struct buffer_head *first_bh, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/inline_crypt.c (0)
Location: fs/crypto/inline_crypt.c:323
Inline: False
Direct callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/ext4/page-io.c:ext4_bio_write_page
```
**Symbols:**

```
ffffffff81e79088-ffffffff81e790d7: fscrypt_set_bio_crypt_ctx_bh.cold (STB_LOCAL)
ffffffff81471b70-ffffffff81471bfe: fscrypt_set_bio_crypt_ctx_bh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void fscrypt_set_bio_crypt_ctx_bh(struct bio *bio, const struct buffer_head *first_bh, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/inline_crypt.c (0)
Location: fs/crypto/inline_crypt.c:314
Inline: False
Direct callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/ext4/page-io.c:ext4_bio_write_page
```
**Symbols:**

```
ffffffff8206a963-ffffffff8206a9b2: fscrypt_set_bio_crypt_ctx_bh.cold (STB_LOCAL)
ffffffff81503770-ffffffff815037fe: fscrypt_set_bio_crypt_ctx_bh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void fscrypt_set_bio_crypt_ctx_bh(struct bio *bio, const struct buffer_head *first_bh, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/inline_crypt.c (0)
Location: fs/crypto/inline_crypt.c:314
Inline: False
Direct callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/ext4/page-io.c:ext4_bio_write_folio
```
**Symbols:**

```
ffffffff820ea7a4-ffffffff820ea800: fscrypt_set_bio_crypt_ctx_bh.cold (STB_LOCAL)
ffffffff8153b020-ffffffff8153b0aa: fscrypt_set_bio_crypt_ctx_bh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void fscrypt_set_bio_crypt_ctx_bh(struct bio *bio, const struct buffer_head *first_bh, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/inline_crypt.c (ffffffff81570010)
Location: fs/crypto/inline_crypt.c:316
Inline: False
Direct callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/ext4/page-io.c:ext4_bio_write_folio
```
**Symbols:**

```
ffffffff81570010-ffffffff81570099: fscrypt_set_bio_crypt_ctx_bh (STB_GLOBAL)
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
