# Function: <code>deflate_decompress</code>

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
int deflate_decompress(struct crypto_tfm *tfm, const u8 *src, unsigned int slen, u8 *dst, unsigned int *dlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/deflate.c (ffffffff8146efc0)
Location: crypto/deflate.c:265
Inline: False
```
**Symbols:**

```
ffffffff8146efc0-ffffffff8146efe2: deflate_decompress (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int deflate_decompress(struct crypto_tfm *tfm, const u8 *src, unsigned int slen, u8 *dst, unsigned int *dlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/deflate.c (ffffffff8148c970)
Location: crypto/deflate.c:265
Inline: False
```
**Symbols:**

```
ffffffff8148c970-ffffffff8148c992: deflate_decompress (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int deflate_decompress(struct crypto_tfm *tfm, const u8 *src, unsigned int slen, u8 *dst, unsigned int *dlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/deflate.c (ffffffff814ba060)
Location: crypto/deflate.c:261
Inline: False
```
**Symbols:**

```
ffffffff814ba060-ffffffff814ba082: deflate_decompress (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int deflate_decompress(struct crypto_tfm *tfm, const u8 *src, unsigned int slen, u8 *dst, unsigned int *dlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/deflate.c (ffffffff814d2e30)
Location: crypto/deflate.c:261
Inline: False
```
**Symbols:**

```
ffffffff814d2e30-ffffffff814d2e52: deflate_decompress (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision ⚠️</summary>

```c
int deflate_decompress(char *src, size_t slen, char *dst, size_t dlen);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff814eb610)
Location: security/apparmor/apparmorfs.c:1296
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:rawdata_open
```
```
In crypto/deflate.c (ffffffff815322c0)
Location: crypto/deflate.c:261
Inline: False
```
**Symbols:**

```
ffffffff814eb610-ffffffff814eb744: deflate_decompress (STB_LOCAL)
ffffffff815322c0-ffffffff815323b5: deflate_decompress (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision ⚠️</summary>

```c
int deflate_decompress(char *src, size_t slen, char *dst, size_t dlen);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff815089f0)
Location: security/apparmor/apparmorfs.c:1296
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:rawdata_open
```
```
In crypto/deflate.c (ffffffff8154f210)
Location: crypto/deflate.c:261
Inline: False
```
**Symbols:**

```
ffffffff815089f0-ffffffff81508b24: deflate_decompress (STB_LOCAL)
ffffffff8154f210-ffffffff8154f305: deflate_decompress (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision, Selective Inline ⚠️</summary>

```c
int deflate_decompress(char *src, size_t slen, char *dst, size_t dlen);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff815130d8)
Location: security/apparmor/apparmorfs.c:1296
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:rawdata_open
```
```
In crypto/deflate.c (ffffffff81557a80)
Location: crypto/deflate.c:261
Inline: False
```
**Symbols:**

```
ffffffff81557a80-ffffffff81557b75: deflate_decompress (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision, Selective Inline ⚠️</summary>

```c
int deflate_decompress(char *src, size_t slen, char *dst, size_t dlen);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff81570cd8)
Location: security/apparmor/apparmorfs.c:1296
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:rawdata_open
```
```
In crypto/deflate.c (ffffffff815b8d30)
Location: crypto/deflate.c:261
Inline: False
```
**Symbols:**

```
ffffffff815b8d30-ffffffff815b8e25: deflate_decompress (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int deflate_decompress(struct crypto_tfm *tfm, const u8 *src, unsigned int slen, u8 *dst, unsigned int *dlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/deflate.c (ffffffff816620b0)
Location: crypto/deflate.c:261
Inline: False
```
**Symbols:**

```
ffffffff816620b0-ffffffff816621c0: deflate_decompress (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int deflate_decompress(struct crypto_tfm *tfm, const u8 *src, unsigned int slen, u8 *dst, unsigned int *dlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/deflate.c (ffffffff8171c020)
Location: crypto/deflate.c:261
Inline: False
```
**Symbols:**

```
ffffffff8171c020-ffffffff8171c130: deflate_decompress (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int deflate_decompress(struct crypto_tfm *tfm, const u8 *src, unsigned int slen, u8 *dst, unsigned int *dlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/deflate.c (ffffffff817577b0)
Location: crypto/deflate.c:261
Inline: False
```
**Symbols:**

```
ffffffff817577b0-ffffffff817578c9: deflate_decompress (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int deflate_decompress(struct crypto_tfm *tfm, const u8 *src, unsigned int slen, u8 *dst, unsigned int *dlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/deflate.c (ffffffff817996b0)
Location: crypto/deflate.c:244
Inline: False
```
**Symbols:**

```
ffffffff817996b0-ffffffff817997c9: deflate_decompress (STB_LOCAL)
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
int deflate_decompress(struct crypto_tfm *tfm, const u8 *src, unsigned int slen, u8 *dst, unsigned int *dlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/deflate.c (ffff8000105cf360)
Location: crypto/deflate.c:261
Inline: False
```
**Symbols:**

```
ffff8000105cf360-ffff8000105cf3bc: deflate_decompress (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int deflate_decompress(struct crypto_tfm *tfm, const u8 *src, unsigned int slen, u8 *dst, unsigned int *dlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/deflate.c (c077d15c)
Location: crypto/deflate.c:261
Inline: False
```
**Symbols:**

```
c077d15c-c077d19c: deflate_decompress (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int deflate_decompress(struct crypto_tfm *tfm, const u8 *src, unsigned int slen, u8 *dst, unsigned int *dlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/deflate.c (c00000000075b280)
Location: crypto/deflate.c:261
Inline: False
```
**Symbols:**

```
c00000000075b280-c00000000075b2b0: deflate_decompress (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int deflate_decompress(struct crypto_tfm *tfm, const u8 *src, unsigned int slen, u8 *dst, unsigned int *dlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/deflate.c (ffffffe0004142e2)
Location: crypto/deflate.c:261
Inline: False
```
**Symbols:**

```
ffffffe0004142e2-ffffffe00041432e: deflate_decompress (STB_LOCAL)
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
int deflate_decompress(struct crypto_tfm *tfm, const u8 *src, unsigned int slen, u8 *dst, unsigned int *dlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/deflate.c (ffffffff814cb410)
Location: crypto/deflate.c:261
Inline: False
```
**Symbols:**

```
ffffffff814cb410-ffffffff814cb432: deflate_decompress (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int deflate_decompress(struct crypto_tfm *tfm, const u8 *src, unsigned int slen, u8 *dst, unsigned int *dlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/deflate.c (ffffffff814bbe30)
Location: crypto/deflate.c:261
Inline: False
```
**Symbols:**

```
ffffffff814bbe30-ffffffff814bbe52: deflate_decompress (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int deflate_decompress(struct crypto_tfm *tfm, const u8 *src, unsigned int slen, u8 *dst, unsigned int *dlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/deflate.c (ffffffff814c74a0)
Location: crypto/deflate.c:261
Inline: False
```
**Symbols:**

```
ffffffff814c74a0-ffffffff814c74c2: deflate_decompress (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int deflate_decompress(struct crypto_tfm *tfm, const u8 *src, unsigned int slen, u8 *dst, unsigned int *dlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/deflate.c (ffffffff814dff70)
Location: crypto/deflate.c:261
Inline: False
```
**Symbols:**

```
ffffffff814dff70-ffffffff814dff92: deflate_decompress (STB_LOCAL)
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
<code>const u8 *src</code> ➡️ <code>char *src</code>
</li>
<li>
<b>Param type changed. </b>
<code>unsigned int slen</code> ➡️ <code>size_t slen</code>
</li>
<li>
<b>Param type changed. </b>
<code>u8 *dst</code> ➡️ <code>char *dst</code>
</li>
<li>
<b>Param type changed. </b>
<code>unsigned int *dlen</code> ➡️ <code>size_t dlen</code>
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
<code>char *src</code> ➡️ <code>const u8 *src</code>
</li>
<li>
<b>Param type changed. </b>
<code>size_t slen</code> ➡️ <code>unsigned int slen</code>
</li>
<li>
<b>Param type changed. </b>
<code>char *dst</code> ➡️ <code>u8 *dst</code>
</li>
<li>
<b>Param type changed. </b>
<code>size_t dlen</code> ➡️ <code>unsigned int *dlen</code>
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
