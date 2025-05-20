# Function: <code>decrypt</code>

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
int decrypt(struct blkcipher_desc *desc, struct scatterlist *dst, struct scatterlist *src, unsigned int nbytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/xts.c (ffffffff813e8480)
Location: crypto/xts.c:153
Inline: False
```
**Symbols:**

```
ffffffff813e8480-ffffffff813e84fc: decrypt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int decrypt(struct skcipher_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/xts.c (ffffffff81401c40)
Location: crypto/xts.c:340
Inline: False
```
**Symbols:**

```
ffffffff81401c40-ffffffff81401c66: decrypt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int decrypt(struct skcipher_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/xts.c (ffffffff8140f010)
Location: crypto/xts.c:359
Inline: False
```
**Symbols:**

```
ffffffff8140f010-ffffffff8140f036: decrypt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int decrypt(struct skcipher_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/xts.c (ffffffff81437af0)
Location: crypto/xts.c:355
Inline: False
```
**Symbols:**

```
ffffffff81437af0-ffffffff81437b16: decrypt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int decrypt(struct skcipher_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/xts.c (ffffffff8146a430)
Location: crypto/xts.c:355
Inline: False
```
**Symbols:**

```
ffffffff8146a430-ffffffff8146a456: decrypt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int decrypt(struct skcipher_request *req);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/xts.c (ffffffff81487830)
Location: crypto/xts.c:172
Inline: True
```
**Symbols:**

```
ffffffff81487830-ffffffff81487936: decrypt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int decrypt(struct skcipher_request *req);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/xts.c (ffffffff814b5510)
Location: crypto/xts.c:172
Inline: True
```
**Symbols:**

```
ffffffff814b5510-ffffffff814b55ad: decrypt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int decrypt(struct skcipher_request *req);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/xts.c (ffffffff814ce760)
Location: crypto/xts.c:278
Inline: True
```
**Symbols:**

```
ffffffff814ce760-ffffffff814ce7ce: decrypt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int decrypt(struct skcipher_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/xts.c (ffffffff8152d8b0)
Location: crypto/xts.c:272
Inline: False
```
**Symbols:**

```
ffffffff8152d8b0-ffffffff8152d986: decrypt (STB_LOCAL)
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
int decrypt(struct skcipher_request *req);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/xts.c (ffff8000105ca920)
Location: crypto/xts.c:278
Inline: True
```
**Symbols:**

```
ffff8000105ca920-ffff8000105ca9ac: decrypt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int decrypt(struct skcipher_request *req);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/xts.c (c0778518)
Location: crypto/xts.c:278
Inline: True
```
**Symbols:**

```
c0778518-c07785a4: decrypt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int decrypt(struct skcipher_request *req);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/xts.c (c000000000755230)
Location: crypto/xts.c:278
Inline: True
```
**Symbols:**

```
c000000000755230-c0000000007552f0: decrypt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int decrypt(struct skcipher_request *req);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/xts.c (ffffffe00040eb52)
Location: crypto/xts.c:278
Inline: True
```
**Symbols:**

```
ffffffe00040eb52-ffffffe00040ebce: decrypt (STB_LOCAL)
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
int decrypt(struct skcipher_request *req);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/xts.c (ffffffff814c6d40)
Location: crypto/xts.c:278
Inline: True
```
**Symbols:**

```
ffffffff814c6d40-ffffffff814c6dae: decrypt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int decrypt(struct skcipher_request *req);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/xts.c (ffffffff814b7760)
Location: crypto/xts.c:278
Inline: True
```
**Symbols:**

```
ffffffff814b7760-ffffffff814b77ce: decrypt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int decrypt(struct skcipher_request *req);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/xts.c (ffffffff814c2dd0)
Location: crypto/xts.c:278
Inline: True
```
**Symbols:**

```
ffffffff814c2dd0-ffffffff814c2e3e: decrypt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int decrypt(struct skcipher_request *req);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/xts.c (ffffffff814db8a0)
Location: crypto/xts.c:278
Inline: True
```
**Symbols:**

```
ffffffff814db8a0-ffffffff814db90e: decrypt (STB_LOCAL)
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
