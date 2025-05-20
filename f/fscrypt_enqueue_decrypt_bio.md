# Function: <code>fscrypt_enqueue_decrypt_bio</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void fscrypt_enqueue_decrypt_bio(struct fscrypt_ctx *ctx, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/bio.c (ffffffff812fc6a0)
Location: fs/crypto/bio.c:67
Inline: False
Direct callers:
  - fs/ext4/readpage.c:mpage_end_io
```
**Symbols:**

```
ffffffff812fc6a0-ffffffff812fc6da: fscrypt_enqueue_decrypt_bio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void fscrypt_enqueue_decrypt_bio(struct fscrypt_ctx *ctx, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/bio.c (ffffffff81311f00)
Location: fs/crypto/bio.c:67
Inline: False
Direct callers:
  - fs/ext4/readpage.c:mpage_end_io
```
**Symbols:**

```
ffffffff81311f00-ffffffff81311f3a: fscrypt_enqueue_decrypt_bio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void fscrypt_enqueue_decrypt_bio(struct fscrypt_ctx *ctx, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/bio.c (ffffffff813394a0)
Location: fs/crypto/bio.c:63
Inline: False
Direct callers:
  - fs/ext4/readpage.c:mpage_end_io
```
**Symbols:**

```
ffffffff813394a0-ffffffff813394da: fscrypt_enqueue_decrypt_bio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void fscrypt_enqueue_decrypt_bio(struct fscrypt_ctx *ctx, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/bio.c (ffffffff8134f320)
Location: fs/crypto/bio.c:63
Inline: False
```
**Symbols:**

```
ffffffff8134f320-ffffffff8134f35a: fscrypt_enqueue_decrypt_bio (STB_GLOBAL)
```
</details>
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
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void fscrypt_enqueue_decrypt_bio(struct fscrypt_ctx *ctx, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/bio.c (ffff800010410b30)
Location: fs/crypto/bio.c:63
Inline: False
```
**Symbols:**

```
ffff800010410b30-ffff800010410b80: fscrypt_enqueue_decrypt_bio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void fscrypt_enqueue_decrypt_bio(struct fscrypt_ctx *ctx, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/bio.c (c05dd2e0)
Location: fs/crypto/bio.c:63
Inline: False
```
**Symbols:**

```
c05dd2e0-c05dd320: fscrypt_enqueue_decrypt_bio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void fscrypt_enqueue_decrypt_bio(struct fscrypt_ctx *ctx, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/bio.c (c00000000051e6d0)
Location: fs/crypto/bio.c:63
Inline: False
```
**Symbols:**

```
c00000000051e6d0-c00000000051e73c: fscrypt_enqueue_decrypt_bio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void fscrypt_enqueue_decrypt_bio(struct fscrypt_ctx *ctx, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/bio.c (ffffffe0002b914e)
Location: fs/crypto/bio.c:63
Inline: False
```
**Symbols:**

```
ffffffe0002b914e-ffffffe0002b919e: fscrypt_enqueue_decrypt_bio (STB_GLOBAL)
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
void fscrypt_enqueue_decrypt_bio(struct fscrypt_ctx *ctx, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/bio.c (ffffffff81347900)
Location: fs/crypto/bio.c:63
Inline: False
```
**Symbols:**

```
ffffffff81347900-ffffffff8134793a: fscrypt_enqueue_decrypt_bio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void fscrypt_enqueue_decrypt_bio(struct fscrypt_ctx *ctx, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/bio.c (ffffffff813385e0)
Location: fs/crypto/bio.c:63
Inline: False
```
**Symbols:**

```
ffffffff813385e0-ffffffff8133861a: fscrypt_enqueue_decrypt_bio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void fscrypt_enqueue_decrypt_bio(struct fscrypt_ctx *ctx, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/bio.c (ffffffff813453d0)
Location: fs/crypto/bio.c:63
Inline: False
```
**Symbols:**

```
ffffffff813453d0-ffffffff8134540a: fscrypt_enqueue_decrypt_bio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void fscrypt_enqueue_decrypt_bio(struct fscrypt_ctx *ctx, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/bio.c (ffffffff813586b0)
Location: fs/crypto/bio.c:63
Inline: False
```
**Symbols:**

```
ffffffff813586b0-ffffffff813586ea: fscrypt_enqueue_decrypt_bio (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
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
