# Function: <code>fscrypt_get_ctx</code>

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
struct fscrypt_ctx *fscrypt_get_ctx(struct inode *inode, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (ffffffff812884b0)
Location: fs/crypto/crypto.c:92
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_zeroout_range
  - fs/crypto/crypto.c:fscrypt_encrypt_page
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
**Symbols:**

```
ffffffff812884b0-ffffffff8128858b: fscrypt_get_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct fscrypt_ctx *fscrypt_get_ctx(const struct inode *inode, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (ffffffff8129d1e0)
Location: fs/crypto/crypto.c:91
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_zeroout_range
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
**Symbols:**

```
ffffffff8129d1e0-ffffffff8129d2b1: fscrypt_get_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct fscrypt_ctx *fscrypt_get_ctx(const struct inode *inode, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/crypto/crypto.c (ffffffff812ac190)
Location: fs/crypto/crypto.c:91
Inline: True
Direct callers:
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
**Symbols:**

```
ffffffff812ac190-ffffffff812ac24a: fscrypt_get_ctx.part.5 (STB_LOCAL)
ffffffff812ac250-ffffffff812ac274: fscrypt_get_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct fscrypt_ctx *fscrypt_get_ctx(const struct inode *inode, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/crypto/crypto.c (ffffffff812cfded)
Location: fs/crypto/crypto.c:91
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_encrypt_page
Direct callers:
  - fs/crypto/crypto.c:fscrypt_encrypt_page
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
**Symbols:**

```
ffffffff812cf9d0-ffffffff812cfa8a: fscrypt_get_ctx.part.6 (STB_LOCAL)
ffffffff812cfa90-ffffffff812cfab4: fscrypt_get_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct fscrypt_ctx *fscrypt_get_ctx(const struct inode *inode, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/crypto/crypto.c (ffffffff812fa6b8)
Location: fs/crypto/crypto.c:98
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_encrypt_page
Direct callers:
  - fs/crypto/crypto.c:fscrypt_encrypt_page
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
**Symbols:**

```
ffffffff812fa190-ffffffff812fa24a: fscrypt_get_ctx.part.7 (STB_LOCAL)
ffffffff812fa250-ffffffff812fa274: fscrypt_get_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct fscrypt_ctx *fscrypt_get_ctx(const struct inode *inode, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/crypto/crypto.c (ffffffff8130fa38)
Location: fs/crypto/crypto.c:98
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_encrypt_page
Direct callers:
  - fs/crypto/crypto.c:fscrypt_encrypt_page
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
**Symbols:**

```
ffffffff8130f470-ffffffff8130f52a: fscrypt_get_ctx.part.7 (STB_LOCAL)
ffffffff8130f530-ffffffff8130f554: fscrypt_get_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct fscrypt_ctx *fscrypt_get_ctx(gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (ffffffff813368f0)
Location: fs/crypto/crypto.c:90
Inline: True
Direct callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
**Symbols:**

```
ffffffff813368f0-ffffffff8133699d: fscrypt_get_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct fscrypt_ctx *fscrypt_get_ctx(gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (ffffffff8134a470)
Location: fs/crypto/crypto.c:90
Inline: True
```
**Symbols:**

```
ffffffff8134a470-ffffffff8134a51d: fscrypt_get_ctx (STB_GLOBAL)
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
struct fscrypt_ctx *fscrypt_get_ctx(gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (ffff80001040ab58)
Location: fs/crypto/crypto.c:90
Inline: True
```
**Symbols:**

```
ffff80001040ab58-ffff80001040aca4: fscrypt_get_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct fscrypt_ctx *fscrypt_get_ctx(gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (c05d7da0)
Location: fs/crypto/crypto.c:90
Inline: True
```
**Symbols:**

```
c05d7da0-c05d7e54: fscrypt_get_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct fscrypt_ctx *fscrypt_get_ctx(gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (c000000000517480)
Location: fs/crypto/crypto.c:90
Inline: True
```
**Symbols:**

```
c000000000517480-c0000000005175c0: fscrypt_get_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct fscrypt_ctx *fscrypt_get_ctx(gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (ffffffe0002b4968)
Location: fs/crypto/crypto.c:90
Inline: True
```
**Symbols:**

```
ffffffe0002b4968-ffffffe0002b4a24: fscrypt_get_ctx (STB_GLOBAL)
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
struct fscrypt_ctx *fscrypt_get_ctx(gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (ffffffff81342a50)
Location: fs/crypto/crypto.c:90
Inline: True
```
**Symbols:**

```
ffffffff81342a50-ffffffff81342afd: fscrypt_get_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct fscrypt_ctx *fscrypt_get_ctx(gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (ffffffff81333730)
Location: fs/crypto/crypto.c:90
Inline: True
```
**Symbols:**

```
ffffffff81333730-ffffffff813337dd: fscrypt_get_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct fscrypt_ctx *fscrypt_get_ctx(gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (ffffffff81340520)
Location: fs/crypto/crypto.c:90
Inline: True
```
**Symbols:**

```
ffffffff81340520-ffffffff813405cd: fscrypt_get_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct fscrypt_ctx *fscrypt_get_ctx(gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (ffffffff81353820)
Location: fs/crypto/crypto.c:90
Inline: True
```
**Symbols:**

```
ffffffff81353820-ffffffff813538cd: fscrypt_get_ctx (STB_GLOBAL)
```
</details>
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
<li>
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>const struct inode *inode</code>
</li>
<li>
<b>Param reordered. </b>
<code>inode, gfp_flags</code> ➡️ <code>gfp_flags</code>
</li>
</ul>
</details>
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
