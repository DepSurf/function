# Function: <code>crypto_cbc_decrypt</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int crypto_cbc_decrypt(struct blkcipher_desc *desc, struct scatterlist *dst, struct scatterlist *src, unsigned int nbytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/cbc.c (ffffffff813a9410)
Location: crypto/cbc.c:169
Inline: False
```
**Symbols:**

```
ffffffff813a9410-ffffffff813a9644: crypto_cbc_decrypt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int crypto_cbc_decrypt(struct blkcipher_desc *desc, struct scatterlist *dst, struct scatterlist *src, unsigned int nbytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/cbc.c (ffffffff813e73d0)
Location: crypto/cbc.c:169
Inline: False
```
**Symbols:**

```
ffffffff813e73d0-ffffffff813e7604: crypto_cbc_decrypt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int crypto_cbc_decrypt(struct skcipher_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/cbc.c (ffffffff81400350)
Location: crypto/cbc.c:63
Inline: False
```
**Symbols:**

```
ffffffff81400350-ffffffff81400551: crypto_cbc_decrypt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int crypto_cbc_decrypt(struct skcipher_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/cbc.c (ffffffff8140d690)
Location: crypto/cbc.c:64
Inline: False
```
**Symbols:**

```
ffffffff8140d690-ffffffff8140d85f: crypto_cbc_decrypt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int crypto_cbc_decrypt(struct skcipher_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/cbc.c (ffffffff81436110)
Location: crypto/cbc.c:64
Inline: False
```
**Symbols:**

```
ffffffff81436110-ffffffff814362ee: crypto_cbc_decrypt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int crypto_cbc_decrypt(struct skcipher_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/cbc.c (ffffffff81468ae0)
Location: crypto/cbc.c:64
Inline: False
```
**Symbols:**

```
ffffffff81468ae0-ffffffff81468cc0: crypto_cbc_decrypt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int crypto_cbc_decrypt(struct skcipher_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/cbc.c (0)
Location: crypto/cbc.c:64
Inline: False
```
**Symbols:**

```
ffffffff81486770-ffffffff81486928: crypto_cbc_decrypt (STB_LOCAL)
ffffffff81486ab0-ffffffff81486abc: crypto_cbc_decrypt.cold.8 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int crypto_cbc_decrypt(struct skcipher_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/cbc.c (0)
Location: crypto/cbc.c:34
Inline: False
```
**Symbols:**

```
ffffffff814b45e0-ffffffff814b479c: crypto_cbc_decrypt (STB_LOCAL)
ffffffff814b4920-ffffffff814b492c: crypto_cbc_decrypt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int crypto_cbc_decrypt(struct skcipher_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/cbc.c (0)
Location: crypto/cbc.c:34
Inline: False
```
**Symbols:**

```
ffffffff814cd350-ffffffff814cd50c: crypto_cbc_decrypt (STB_LOCAL)
ffffffff814cd690-ffffffff814cd69c: crypto_cbc_decrypt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int crypto_cbc_decrypt(struct skcipher_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/cbc.c (0)
Location: crypto/cbc.c:34
Inline: False
```
**Symbols:**

```
ffffffff8152c920-ffffffff8152cacc: crypto_cbc_decrypt (STB_LOCAL)
ffffffff8152cacc-ffffffff8152cad8: crypto_cbc_decrypt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int crypto_cbc_decrypt(struct skcipher_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/cbc.c (ffffffff81549ab0)
Location: crypto/cbc.c:154
Inline: False
```
**Symbols:**

```
ffffffff81549ab0-ffffffff81549b47: crypto_cbc_decrypt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int crypto_cbc_decrypt(struct skcipher_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/cbc.c (0)
Location: crypto/cbc.c:155
Inline: False
```
**Symbols:**

```
ffffffff81551fd0-ffffffff81552199: crypto_cbc_decrypt (STB_LOCAL)
ffffffff81be4097-ffffffff81be40a3: crypto_cbc_decrypt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int crypto_cbc_decrypt(struct skcipher_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/cbc.c (0)
Location: crypto/cbc.c:155
Inline: False
```
**Symbols:**

```
ffffffff815b2fd0-ffffffff815b3199: crypto_cbc_decrypt (STB_LOCAL)
ffffffff81cd77b6-ffffffff81cd77c2: crypto_cbc_decrypt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int crypto_cbc_decrypt(struct skcipher_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/cbc.c (ffffffff8165bcb0)
Location: crypto/cbc.c:155
Inline: False
```
**Symbols:**

```
ffffffff8165bcb0-ffffffff8165be1a: crypto_cbc_decrypt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int crypto_cbc_decrypt(struct skcipher_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/cbc.c (ffffffff81715690)
Location: crypto/cbc.c:155
Inline: False
```
**Symbols:**

```
ffffffff81715690-ffffffff81715754: crypto_cbc_decrypt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int crypto_cbc_decrypt(struct skcipher_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/cbc.c (ffffffff81750f40)
Location: crypto/cbc.c:155
Inline: False
```
**Symbols:**

```
ffffffff81750f40-ffffffff81751004: crypto_cbc_decrypt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int crypto_cbc_decrypt(struct crypto_lskcipher *tfm, const u8 *src, u8 *dst, unsigned int len, u8 *iv, u32 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/cbc.c (ffffffff81792e00)
Location: crypto/cbc.c:122
Inline: False
```
**Symbols:**

```
ffffffff81792e00-ffffffff81792e52: crypto_cbc_decrypt (STB_LOCAL)
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
int crypto_cbc_decrypt(struct skcipher_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/cbc.c (ffff8000105c9200)
Location: crypto/cbc.c:34
Inline: False
```
**Symbols:**

```
ffff8000105c9200-ffff8000105c93a8: crypto_cbc_decrypt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int crypto_cbc_decrypt(struct skcipher_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/cbc.c (c0776f78)
Location: crypto/cbc.c:34
Inline: False
```
**Symbols:**

```
c0776f78-c077710c: crypto_cbc_decrypt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int crypto_cbc_decrypt(struct skcipher_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/cbc.c (c000000000753730)
Location: crypto/cbc.c:34
Inline: False
```
**Symbols:**

```
c000000000753730-c000000000753964: crypto_cbc_decrypt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int crypto_cbc_decrypt(struct skcipher_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/cbc.c (ffffffe00040daf0)
Location: crypto/cbc.c:34
Inline: False
```
**Symbols:**

```
ffffffe00040daf0-ffffffe00040dc2e: crypto_cbc_decrypt (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int crypto_cbc_decrypt(struct skcipher_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/cbc.c (0)
Location: crypto/cbc.c:34
Inline: False
```
**Symbols:**

```
ffffffff814c5930-ffffffff814c5aec: crypto_cbc_decrypt (STB_LOCAL)
ffffffff814c5c70-ffffffff814c5c7c: crypto_cbc_decrypt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int crypto_cbc_decrypt(struct skcipher_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/cbc.c (0)
Location: crypto/cbc.c:34
Inline: False
```
**Symbols:**

```
ffffffff814b6350-ffffffff814b650c: crypto_cbc_decrypt (STB_LOCAL)
ffffffff814b6690-ffffffff814b669c: crypto_cbc_decrypt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int crypto_cbc_decrypt(struct skcipher_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/cbc.c (0)
Location: crypto/cbc.c:34
Inline: False
```
**Symbols:**

```
ffffffff814c19c0-ffffffff814c1b7c: crypto_cbc_decrypt (STB_LOCAL)
ffffffff814c1d00-ffffffff814c1d0c: crypto_cbc_decrypt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int crypto_cbc_decrypt(struct skcipher_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/cbc.c (0)
Location: crypto/cbc.c:34
Inline: False
```
**Symbols:**

```
ffffffff814da490-ffffffff814da64c: crypto_cbc_decrypt (STB_LOCAL)
ffffffff814da7d0-ffffffff814da7dc: crypto_cbc_decrypt.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct skcipher_request *req</code>
</li>
<li>
<b>Param removed. </b>
<code>struct blkcipher_desc *desc</code>
</li>
<li>
<b>Param removed. </b>
<code>struct scatterlist *dst</code>
</li>
<li>
<b>Param removed. </b>
<code>struct scatterlist *src</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int nbytes</code>
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
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
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
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct crypto_lskcipher *tfm</code>
</li>
<li>
<b>Param added. </b>
<code>const u8 *src</code>
</li>
<li>
<b>Param added. </b>
<code>u8 *dst</code>
</li>
<li>
<b>Param added. </b>
<code>unsigned int len</code>
</li>
<li>
<b>Param added. </b>
<code>u8 *iv</code>
</li>
<li>
<b>Param added. </b>
<code>u32 flags</code>
</li>
<li>
<b>Param removed. </b>
<code>struct skcipher_request *req</code>
</li>
</ul>
</details>
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
