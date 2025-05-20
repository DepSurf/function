# Function: <code>fscrypt_release_ctx</code>

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
void fscrypt_release_ctx(struct fscrypt_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (ffffffff81288760)
Location: fs/crypto/crypto.c:63
Inline: True
Direct callers:
  - fs/crypto/crypto.c:fscrypt_restore_control_page
  - fs/crypto/crypto.c:completion_pages
  - fs/crypto/crypto.c:fscrypt_zeroout_range
  - fs/crypto/crypto.c:fscrypt_encrypt_page
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:mpage_end_io
```
**Symbols:**

```
ffffffff81288760-ffffffff812887ed: fscrypt_release_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void fscrypt_release_ctx(struct fscrypt_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (ffffffff8129d460)
Location: fs/crypto/crypto.c:62
Inline: True
Direct callers:
  - fs/crypto/crypto.c:fscrypt_restore_control_page
  - fs/crypto/crypto.c:completion_pages
  - fs/crypto/crypto.c:fscrypt_zeroout_range
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:mpage_end_io
```
**Symbols:**

```
ffffffff8129d460-ffffffff8129d4ed: fscrypt_release_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void fscrypt_release_ctx(struct fscrypt_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (ffffffff812ac0d0)
Location: fs/crypto/crypto.c:62
Inline: True
Direct callers:
  - fs/crypto/crypto.c:fscrypt_restore_control_page
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/crypto/bio.c:completion_pages
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:mpage_end_io
```
**Symbols:**

```
ffffffff812ac0d0-ffffffff812ac15d: fscrypt_release_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void fscrypt_release_ctx(struct fscrypt_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (ffffffff812cf910)
Location: fs/crypto/crypto.c:62
Inline: True
Direct callers:
  - fs/crypto/crypto.c:fscrypt_restore_control_page
  - fs/crypto/crypto.c:fscrypt_encrypt_page
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/crypto/bio.c:completion_pages
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:mpage_end_io
```
**Symbols:**

```
ffffffff812cf910-ffffffff812cf99d: fscrypt_release_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void fscrypt_release_ctx(struct fscrypt_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (ffffffff812fa0d0)
Location: fs/crypto/crypto.c:69
Inline: True
Direct callers:
  - fs/crypto/crypto.c:fscrypt_restore_control_page
  - fs/crypto/crypto.c:fscrypt_encrypt_page
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/crypto/bio.c:completion_pages
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:mpage_end_io
```
**Symbols:**

```
ffffffff812fa0d0-ffffffff812fa15d: fscrypt_release_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void fscrypt_release_ctx(struct fscrypt_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (ffffffff8130f3b0)
Location: fs/crypto/crypto.c:69
Inline: True
Direct callers:
  - fs/crypto/crypto.c:fscrypt_restore_control_page
  - fs/crypto/crypto.c:fscrypt_encrypt_page
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/crypto/bio.c:completion_pages
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:mpage_end_io
```
**Symbols:**

```
ffffffff8130f3b0-ffffffff8130f43d: fscrypt_release_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void fscrypt_release_ctx(struct fscrypt_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (ffffffff81336880)
Location: fs/crypto/crypto.c:68
Inline: True
Direct callers:
  - fs/crypto/bio.c:completion_pages
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:mpage_end_io
```
**Symbols:**

```
ffffffff81336880-ffffffff813368e5: fscrypt_release_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void fscrypt_release_ctx(struct fscrypt_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (ffffffff8134a400)
Location: fs/crypto/crypto.c:68
Inline: True
Direct callers:
  - fs/crypto/bio.c:completion_pages
```
**Symbols:**

```
ffffffff8134a400-ffffffff8134a465: fscrypt_release_ctx (STB_GLOBAL)
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
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void fscrypt_release_ctx(struct fscrypt_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (ffff80001040aca8)
Location: fs/crypto/crypto.c:68
Inline: True
Direct callers:
  - fs/crypto/bio.c:completion_pages
```
**Symbols:**

```
ffff80001040aca8-ffff80001040ad98: fscrypt_release_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void fscrypt_release_ctx(struct fscrypt_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (c05d7d30)
Location: fs/crypto/crypto.c:68
Inline: True
Direct callers:
  - fs/crypto/bio.c:completion_pages
```
**Symbols:**

```
c05d7d30-c05d7da0: fscrypt_release_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void fscrypt_release_ctx(struct fscrypt_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (c0000000005173c0)
Location: fs/crypto/crypto.c:68
Inline: True
Direct callers:
  - fs/crypto/bio.c:completion_pages
```
**Symbols:**

```
c0000000005173c0-c000000000517480: fscrypt_release_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void fscrypt_release_ctx(struct fscrypt_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (ffffffe0002b48f0)
Location: fs/crypto/crypto.c:68
Inline: True
Direct callers:
  - fs/crypto/bio.c:completion_pages
```
**Symbols:**

```
ffffffe0002b48f0-ffffffe0002b4968: fscrypt_release_ctx (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void fscrypt_release_ctx(struct fscrypt_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (ffffffff813429e0)
Location: fs/crypto/crypto.c:68
Inline: True
Direct callers:
  - fs/crypto/bio.c:completion_pages
```
**Symbols:**

```
ffffffff813429e0-ffffffff81342a45: fscrypt_release_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void fscrypt_release_ctx(struct fscrypt_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (ffffffff813336c0)
Location: fs/crypto/crypto.c:68
Inline: True
Direct callers:
  - fs/crypto/bio.c:completion_pages
```
**Symbols:**

```
ffffffff813336c0-ffffffff81333725: fscrypt_release_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void fscrypt_release_ctx(struct fscrypt_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (ffffffff813404b0)
Location: fs/crypto/crypto.c:68
Inline: True
Direct callers:
  - fs/crypto/bio.c:completion_pages
```
**Symbols:**

```
ffffffff813404b0-ffffffff81340515: fscrypt_release_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void fscrypt_release_ctx(struct fscrypt_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (ffffffff813537b0)
Location: fs/crypto/crypto.c:68
Inline: True
Direct callers:
  - fs/crypto/bio.c:completion_pages
```
**Symbols:**

```
ffffffff813537b0-ffffffff81353815: fscrypt_release_ctx (STB_GLOBAL)
```
</details>
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
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
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
