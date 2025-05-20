# Function: <code>encrypt</code>

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
int encrypt(struct blkcipher_desc *desc, struct scatterlist *dst, struct scatterlist *src, unsigned int nbytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/xts.c (ffffffff813e8500)
Location: crypto/xts.c:142
Inline: False
```
**Symbols:**

```
ffffffff813e8500-ffffffff813e857c: encrypt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int encrypt(struct skcipher_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/xts.c (ffffffff81401d60)
Location: crypto/xts.c:296
Inline: False
```
**Symbols:**

```
ffffffff81401d60-ffffffff81401d86: encrypt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int encrypt(struct skcipher_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/xts.c (ffffffff8140f140)
Location: crypto/xts.c:307
Inline: False
```
**Symbols:**

```
ffffffff8140f140-ffffffff8140f166: encrypt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int encrypt(struct skcipher_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/xts.c (ffffffff81437c30)
Location: crypto/xts.c:305
Inline: False
```
**Symbols:**

```
ffffffff81437c30-ffffffff81437c56: encrypt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int encrypt(struct skcipher_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/xts.c (ffffffff8146a590)
Location: crypto/xts.c:305
Inline: False
```
**Symbols:**

```
ffffffff8146a590-ffffffff8146a5b6: encrypt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int encrypt(struct skcipher_request *req);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/xts.c (ffffffff81487d70)
Location: crypto/xts.c:161
Inline: True
```
**Symbols:**

```
ffffffff81487d70-ffffffff81487e76: encrypt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int encrypt(struct skcipher_request *req);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/xts.c (ffffffff814b55b0)
Location: crypto/xts.c:161
Inline: True
```
**Symbols:**

```
ffffffff814b55b0-ffffffff814b564d: encrypt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int encrypt(struct skcipher_request *req);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/xts.c (ffffffff814ce7d0)
Location: crypto/xts.c:261
Inline: True
```
**Symbols:**

```
ffffffff814ce7d0-ffffffff814ce844: encrypt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int encrypt(struct skcipher_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/xts.c (ffffffff8152ded0)
Location: crypto/xts.c:255
Inline: False
```
**Symbols:**

```
ffffffff8152ded0-ffffffff8152dfac: encrypt (STB_LOCAL)
```
</details>
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
int encrypt(struct skcipher_request *req);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/xts.c (ffff8000105ca9b0)
Location: crypto/xts.c:261
Inline: True
```
**Symbols:**

```
ffff8000105ca9b0-ffff8000105caa3c: encrypt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int encrypt(struct skcipher_request *req);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/xts.c (c07785a4)
Location: crypto/xts.c:261
Inline: True
```
**Symbols:**

```
c07785a4-c0778630: encrypt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int encrypt(struct skcipher_request *req);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/xts.c (c0000000007552f0)
Location: crypto/xts.c:261
Inline: True
```
**Symbols:**

```
c0000000007552f0-c0000000007553b0: encrypt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int encrypt(struct skcipher_request *req);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/xts.c (ffffffe00040ebce)
Location: crypto/xts.c:261
Inline: True
```
**Symbols:**

```
ffffffe00040ebce-ffffffe00040ec4a: encrypt (STB_LOCAL)
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
int encrypt(struct skcipher_request *req);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/xts.c (ffffffff814c6db0)
Location: crypto/xts.c:261
Inline: True
```
**Symbols:**

```
ffffffff814c6db0-ffffffff814c6e24: encrypt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int encrypt(struct skcipher_request *req);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/xts.c (ffffffff814b77d0)
Location: crypto/xts.c:261
Inline: True
```
**Symbols:**

```
ffffffff814b77d0-ffffffff814b7844: encrypt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int encrypt(struct skcipher_request *req);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/xts.c (ffffffff814c2e40)
Location: crypto/xts.c:261
Inline: True
```
**Symbols:**

```
ffffffff814c2e40-ffffffff814c2eb4: encrypt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int encrypt(struct skcipher_request *req);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/xts.c (ffffffff814db910)
Location: crypto/xts.c:261
Inline: True
```
**Symbols:**

```
ffffffff814db910-ffffffff814db984: encrypt (STB_LOCAL)
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
