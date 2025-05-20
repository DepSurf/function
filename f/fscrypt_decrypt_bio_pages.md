# Function: <code>fscrypt_decrypt_bio_pages</code>

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
void fscrypt_decrypt_bio_pages(struct fscrypt_ctx *ctx, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (ffffffff812886a0)
Location: fs/crypto/crypto.c:431
Inline: False
Direct callers:
  - fs/ext4/readpage.c:mpage_end_io
```
**Symbols:**

```
ffffffff812886a0-ffffffff812886e5: fscrypt_decrypt_bio_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void fscrypt_decrypt_bio_pages(struct fscrypt_ctx *ctx, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (ffffffff8129d3a0)
Location: fs/crypto/crypto.c:466
Inline: False
Direct callers:
  - fs/ext4/readpage.c:mpage_end_io
```
**Symbols:**

```
ffffffff8129d3a0-ffffffff8129d3e5: fscrypt_decrypt_bio_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void fscrypt_decrypt_bio_pages(struct fscrypt_ctx *ctx, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/bio.c (ffffffff812ae1a0)
Location: fs/crypto/bio.c:57
Inline: False
Direct callers:
  - fs/ext4/readpage.c:mpage_end_io
```
**Symbols:**

```
ffffffff812ae1a0-ffffffff812ae1e5: fscrypt_decrypt_bio_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void fscrypt_decrypt_bio_pages(struct fscrypt_ctx *ctx, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/bio.c (ffffffff812d1ba0)
Location: fs/crypto/bio.c:58
Inline: False
Direct callers:
  - fs/ext4/readpage.c:mpage_end_io
```
**Symbols:**

```
ffffffff812d1ba0-ffffffff812d1be5: fscrypt_decrypt_bio_pages (STB_GLOBAL)
```
</details>
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
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
</ul>
