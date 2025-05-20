# Function: <code>deflate_compress</code>

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
int deflate_compress(struct crypto_tfm *tfm, const u8 *src, unsigned int slen, u8 *dst, unsigned int *dlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/deflate.c (ffffffff8146f1d0)
Location: crypto/deflate.c:209
Inline: False
```
**Symbols:**

```
ffffffff8146f1d0-ffffffff8146f258: deflate_compress (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int deflate_compress(struct crypto_tfm *tfm, const u8 *src, unsigned int slen, u8 *dst, unsigned int *dlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/deflate.c (ffffffff8148cb80)
Location: crypto/deflate.c:209
Inline: False
```
**Symbols:**

```
ffffffff8148cb80-ffffffff8148cc08: deflate_compress (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int deflate_compress(struct crypto_tfm *tfm, const u8 *src, unsigned int slen, u8 *dst, unsigned int *dlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/deflate.c (ffffffff814ba270)
Location: crypto/deflate.c:205
Inline: False
```
**Symbols:**

```
ffffffff814ba270-ffffffff814ba2f5: deflate_compress (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int deflate_compress(struct crypto_tfm *tfm, const u8 *src, unsigned int slen, u8 *dst, unsigned int *dlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/deflate.c (ffffffff814d3040)
Location: crypto/deflate.c:205
Inline: False
```
**Symbols:**

```
ffffffff814d3040-ffffffff814d30c5: deflate_compress (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision ⚠️</summary>

```c
int deflate_compress(const char *src, size_t slen, char **dst, size_t *dlen);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy_unpack.c (ffffffff814fcb90)
Location: security/apparmor/policy_unpack.c:1102
Inline: False
Direct callers:
  - security/apparmor/policy_unpack.c:aa_unpack
```
```
In crypto/deflate.c (ffffffff81531ee0)
Location: crypto/deflate.c:205
Inline: False
```
**Symbols:**

```
ffffffff814fcb90-ffffffff814fcd94: deflate_compress (STB_LOCAL)
ffffffff81531ee0-ffffffff81531f65: deflate_compress (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision ⚠️</summary>

```c
int deflate_compress(const char *src, size_t slen, char **dst, size_t *dlen);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy_unpack.c (ffffffff81519de0)
Location: security/apparmor/policy_unpack.c:1102
Inline: False
Direct callers:
  - security/apparmor/policy_unpack.c:aa_unpack
```
```
In crypto/deflate.c (ffffffff8154ee30)
Location: crypto/deflate.c:205
Inline: False
```
**Symbols:**

```
ffffffff81519de0-ffffffff81519fe4: deflate_compress (STB_LOCAL)
ffffffff8154ee30-ffffffff8154eeb5: deflate_compress (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision ⚠️</summary>

```c
int deflate_compress(const char *src, size_t slen, char **dst, size_t *dlen);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy_unpack.c (ffffffff815206f0)
Location: security/apparmor/policy_unpack.c:1102
Inline: False
Direct callers:
  - security/apparmor/policy_unpack.c:aa_unpack
```
```
In crypto/deflate.c (ffffffff815576a0)
Location: crypto/deflate.c:205
Inline: False
```
**Symbols:**

```
ffffffff815206f0-ffffffff815208f4: deflate_compress (STB_LOCAL)
ffffffff815576a0-ffffffff81557725: deflate_compress (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision ⚠️</summary>

```c
int deflate_compress(const char *src, size_t slen, char **dst, size_t *dlen);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy_unpack.c (ffffffff8157e890)
Location: security/apparmor/policy_unpack.c:1102
Inline: False
Direct callers:
  - security/apparmor/policy_unpack.c:aa_unpack
```
```
In crypto/deflate.c (ffffffff815b8950)
Location: crypto/deflate.c:205
Inline: False
```
**Symbols:**

```
ffffffff8157e890-ffffffff8157ea94: deflate_compress (STB_LOCAL)
ffffffff815b8950-ffffffff815b89d5: deflate_compress (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int deflate_compress(struct crypto_tfm *tfm, const u8 *src, unsigned int slen, u8 *dst, unsigned int *dlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/deflate.c (ffffffff81661d60)
Location: crypto/deflate.c:205
Inline: False
```
**Symbols:**

```
ffffffff81661d60-ffffffff81661df4: deflate_compress (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int deflate_compress(struct crypto_tfm *tfm, const u8 *src, unsigned int slen, u8 *dst, unsigned int *dlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/deflate.c (ffffffff8171bc50)
Location: crypto/deflate.c:205
Inline: False
```
**Symbols:**

```
ffffffff8171bc50-ffffffff8171bce4: deflate_compress (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int deflate_compress(struct crypto_tfm *tfm, const u8 *src, unsigned int slen, u8 *dst, unsigned int *dlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/deflate.c (ffffffff817573e0)
Location: crypto/deflate.c:205
Inline: False
```
**Symbols:**

```
ffffffff817573e0-ffffffff81757474: deflate_compress (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int deflate_compress(struct crypto_tfm *tfm, const u8 *src, unsigned int slen, u8 *dst, unsigned int *dlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/deflate.c (ffffffff81799480)
Location: crypto/deflate.c:188
Inline: False
```
**Symbols:**

```
ffffffff81799480-ffffffff81799514: deflate_compress (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int deflate_compress(struct crypto_tfm *tfm, const u8 *src, unsigned int slen, u8 *dst, unsigned int *dlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/deflate.c (ffff8000105cf5d8)
Location: crypto/deflate.c:205
Inline: False
```
**Symbols:**

```
ffff8000105cf5d8-ffff8000105cf678: deflate_compress (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int deflate_compress(struct crypto_tfm *tfm, const u8 *src, unsigned int slen, u8 *dst, unsigned int *dlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/deflate.c (c077d364)
Location: crypto/deflate.c:205
Inline: False
```
**Symbols:**

```
c077d364-c077d3e0: deflate_compress (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int deflate_compress(struct crypto_tfm *tfm, const u8 *src, unsigned int slen, u8 *dst, unsigned int *dlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/deflate.c (c00000000075b5c0)
Location: crypto/deflate.c:205
Inline: False
```
**Symbols:**

```
c00000000075b5c0-c00000000075b698: deflate_compress (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int deflate_compress(struct crypto_tfm *tfm, const u8 *src, unsigned int slen, u8 *dst, unsigned int *dlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/deflate.c (ffffffe00041452a)
Location: crypto/deflate.c:205
Inline: False
```
**Symbols:**

```
ffffffe00041452a-ffffffe0004145b0: deflate_compress (STB_LOCAL)
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
int deflate_compress(struct crypto_tfm *tfm, const u8 *src, unsigned int slen, u8 *dst, unsigned int *dlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/deflate.c (ffffffff814cb620)
Location: crypto/deflate.c:205
Inline: False
```
**Symbols:**

```
ffffffff814cb620-ffffffff814cb6a5: deflate_compress (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int deflate_compress(struct crypto_tfm *tfm, const u8 *src, unsigned int slen, u8 *dst, unsigned int *dlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/deflate.c (ffffffff814bc040)
Location: crypto/deflate.c:205
Inline: False
```
**Symbols:**

```
ffffffff814bc040-ffffffff814bc0c5: deflate_compress (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int deflate_compress(struct crypto_tfm *tfm, const u8 *src, unsigned int slen, u8 *dst, unsigned int *dlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/deflate.c (ffffffff814c76b0)
Location: crypto/deflate.c:205
Inline: False
```
**Symbols:**

```
ffffffff814c76b0-ffffffff814c7735: deflate_compress (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int deflate_compress(struct crypto_tfm *tfm, const u8 *src, unsigned int slen, u8 *dst, unsigned int *dlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/deflate.c (ffffffff814e0180)
Location: crypto/deflate.c:205
Inline: False
```
**Symbols:**

```
ffffffff814e0180-ffffffff814e0205: deflate_compress (STB_LOCAL)
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
<li>
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct crypto_tfm *tfm</code>
</li>
<li>
<b>Param reordered. </b>
<code>tfm, src, slen, dst, dlen</code> ➡️ <code>src, slen, dst, dlen</code>
</li>
<li>
<b>Param type changed. </b>
<code>const u8 *src</code> ➡️ <code>const char *src</code>
</li>
<li>
<b>Param type changed. </b>
<code>unsigned int slen</code> ➡️ <code>size_t slen</code>
</li>
<li>
<b>Param type changed. </b>
<code>u8 *dst</code> ➡️ <code>char **dst</code>
</li>
<li>
<b>Param type changed. </b>
<code>unsigned int *dlen</code> ➡️ <code>size_t *dlen</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct crypto_tfm *tfm</code>
</li>
<li>
<b>Param reordered. </b>
<code>src, slen, dst, dlen</code> ➡️ <code>tfm, src, slen, dst, dlen</code>
</li>
<li>
<b>Param type changed. </b>
<code>const char *src</code> ➡️ <code>const u8 *src</code>
</li>
<li>
<b>Param type changed. </b>
<code>size_t slen</code> ➡️ <code>unsigned int slen</code>
</li>
<li>
<b>Param type changed. </b>
<code>char **dst</code> ➡️ <code>u8 *dst</code>
</li>
<li>
<b>Param type changed. </b>
<code>size_t *dlen</code> ➡️ <code>unsigned int *dlen</code>
</li>
</ul>
</details>
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
