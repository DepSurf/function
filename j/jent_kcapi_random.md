# Function: <code>jent_kcapi_random</code>

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
int jent_kcapi_random(struct crypto_rng *tfm, const u8 *src, unsigned int slen, u8 *rdata, unsigned int dlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/jitterentropy-kcapi.c (ffffffff813ef9c0)
Location: crypto/jitterentropy-kcapi.c:149
Inline: False
```
**Symbols:**

```
ffffffff813ef9c0-ffffffff813efa0c: jent_kcapi_random (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int jent_kcapi_random(struct crypto_rng *tfm, const u8 *src, unsigned int slen, u8 *rdata, unsigned int dlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/jitterentropy-kcapi.c (ffffffff81409240)
Location: crypto/jitterentropy-kcapi.c:148
Inline: False
```
**Symbols:**

```
ffffffff81409240-ffffffff8140928c: jent_kcapi_random (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int jent_kcapi_random(struct crypto_rng *tfm, const u8 *src, unsigned int slen, u8 *rdata, unsigned int dlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/jitterentropy-kcapi.c (ffffffff81416920)
Location: crypto/jitterentropy-kcapi.c:148
Inline: False
```
**Symbols:**

```
ffffffff81416920-ffffffff8141696c: jent_kcapi_random (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int jent_kcapi_random(struct crypto_rng *tfm, const u8 *src, unsigned int slen, u8 *rdata, unsigned int dlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/jitterentropy-kcapi.c (ffffffff81441100)
Location: crypto/jitterentropy-kcapi.c:148
Inline: False
```
**Symbols:**

```
ffffffff81441100-ffffffff8144114c: jent_kcapi_random (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int jent_kcapi_random(struct crypto_rng *tfm, const u8 *src, unsigned int slen, u8 *rdata, unsigned int dlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/jitterentropy-kcapi.c (ffffffff81473fd0)
Location: crypto/jitterentropy-kcapi.c:148
Inline: False
```
**Symbols:**

```
ffffffff81473fd0-ffffffff8147401c: jent_kcapi_random (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int jent_kcapi_random(struct crypto_rng *tfm, const u8 *src, unsigned int slen, u8 *rdata, unsigned int dlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/jitterentropy-kcapi.c (ffffffff81491b40)
Location: crypto/jitterentropy-kcapi.c:148
Inline: False
```
**Symbols:**

```
ffffffff81491b40-ffffffff81491b8c: jent_kcapi_random (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int jent_kcapi_random(struct crypto_rng *tfm, const u8 *src, unsigned int slen, u8 *rdata, unsigned int dlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/jitterentropy-kcapi.c (ffffffff814bf1d0)
Location: crypto/jitterentropy-kcapi.c:143
Inline: False
```
**Symbols:**

```
ffffffff814bf1d0-ffffffff814bf21d: jent_kcapi_random (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int jent_kcapi_random(struct crypto_rng *tfm, const u8 *src, unsigned int slen, u8 *rdata, unsigned int dlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/jitterentropy-kcapi.c (ffffffff814d8020)
Location: crypto/jitterentropy-kcapi.c:143
Inline: False
```
**Symbols:**

```
ffffffff814d8020-ffffffff814d806d: jent_kcapi_random (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int jent_kcapi_random(struct crypto_rng *tfm, const u8 *src, unsigned int slen, u8 *rdata, unsigned int dlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/jitterentropy-kcapi.c (0)
Location: crypto/jitterentropy-kcapi.c:138
Inline: False
```
**Symbols:**

```
ffffffff815377a0-ffffffff8153783a: jent_kcapi_random (STB_LOCAL)
ffffffff81537912-ffffffff81537939: jent_kcapi_random.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int jent_kcapi_random(struct crypto_rng *tfm, const u8 *src, unsigned int slen, u8 *rdata, unsigned int dlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/jitterentropy-kcapi.c (0)
Location: crypto/jitterentropy-kcapi.c:138
Inline: False
```
**Symbols:**

```
ffffffff81554660-ffffffff815546fa: jent_kcapi_random (STB_LOCAL)
ffffffff81bf21d4-ffffffff81bf21fb: jent_kcapi_random.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int jent_kcapi_random(struct crypto_rng *tfm, const u8 *src, unsigned int slen, u8 *rdata, unsigned int dlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/jitterentropy-kcapi.c (0)
Location: crypto/jitterentropy-kcapi.c:138
Inline: False
```
**Symbols:**

```
ffffffff8155cdd0-ffffffff8155ce6a: jent_kcapi_random (STB_LOCAL)
ffffffff81be418c-ffffffff81be41b3: jent_kcapi_random.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int jent_kcapi_random(struct crypto_rng *tfm, const u8 *src, unsigned int slen, u8 *rdata, unsigned int dlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/jitterentropy-kcapi.c (0)
Location: crypto/jitterentropy-kcapi.c:138
Inline: False
```
**Symbols:**

```
ffffffff815be100-ffffffff815be19a: jent_kcapi_random (STB_LOCAL)
ffffffff81cd7919-ffffffff81cd7940: jent_kcapi_random.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int jent_kcapi_random(struct crypto_rng *tfm, const u8 *src, unsigned int slen, u8 *rdata, unsigned int dlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/jitterentropy-kcapi.c (0)
Location: crypto/jitterentropy-kcapi.c:132
Inline: False
```
**Symbols:**

```
ffffffff81667d00-ffffffff81667da7: jent_kcapi_random (STB_LOCAL)
ffffffff81e8ab61-ffffffff81e8ab88: jent_kcapi_random.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int jent_kcapi_random(struct crypto_rng *tfm, const u8 *src, unsigned int slen, u8 *rdata, unsigned int dlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/jitterentropy-kcapi.c (ffffffff81722310)
Location: crypto/jitterentropy-kcapi.c:132
Inline: False
```
**Symbols:**

```
ffffffff81722310-ffffffff817223d5: jent_kcapi_random (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int jent_kcapi_random(struct crypto_rng *tfm, const u8 *src, unsigned int slen, u8 *rdata, unsigned int dlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/jitterentropy-kcapi.c (ffffffff8175db50)
Location: crypto/jitterentropy-kcapi.c:262
Inline: False
```
**Symbols:**

```
ffffffff8175db50-ffffffff8175dbfd: jent_kcapi_random (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int jent_kcapi_random(struct crypto_rng *tfm, const u8 *src, unsigned int slen, u8 *rdata, unsigned int dlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/jitterentropy-kcapi.c (ffffffff8179f9b0)
Location: crypto/jitterentropy-kcapi.c:275
Inline: False
```
**Symbols:**

```
ffffffff8179f9b0-ffffffff8179fa5d: jent_kcapi_random (STB_LOCAL)
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
int jent_kcapi_random(struct crypto_rng *tfm, const u8 *src, unsigned int slen, u8 *rdata, unsigned int dlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/jitterentropy-kcapi.c (ffff8000105d3d30)
Location: crypto/jitterentropy-kcapi.c:143
Inline: False
```
**Symbols:**

```
ffff8000105d3d30-ffff8000105d3dcc: jent_kcapi_random (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int jent_kcapi_random(struct crypto_rng *tfm, const u8 *src, unsigned int slen, u8 *rdata, unsigned int dlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/jitterentropy-kcapi.c (c07818e0)
Location: crypto/jitterentropy-kcapi.c:143
Inline: False
```
**Symbols:**

```
c07818e0-c0781930: jent_kcapi_random (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int jent_kcapi_random(struct crypto_rng *tfm, const u8 *src, unsigned int slen, u8 *rdata, unsigned int dlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/jitterentropy-kcapi.c (c0000000007612b0)
Location: crypto/jitterentropy-kcapi.c:143
Inline: False
```
**Symbols:**

```
c0000000007612b0-c000000000761378: jent_kcapi_random (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int jent_kcapi_random(struct crypto_rng *tfm, const u8 *src, unsigned int slen, u8 *rdata, unsigned int dlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/jitterentropy-kcapi.c (ffffffe000418274)
Location: crypto/jitterentropy-kcapi.c:143
Inline: False
```
**Symbols:**

```
ffffffe000418274-ffffffe0004182fa: jent_kcapi_random (STB_LOCAL)
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
int jent_kcapi_random(struct crypto_rng *tfm, const u8 *src, unsigned int slen, u8 *rdata, unsigned int dlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/jitterentropy-kcapi.c (ffffffff814d0600)
Location: crypto/jitterentropy-kcapi.c:143
Inline: False
```
**Symbols:**

```
ffffffff814d0600-ffffffff814d064d: jent_kcapi_random (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int jent_kcapi_random(struct crypto_rng *tfm, const u8 *src, unsigned int slen, u8 *rdata, unsigned int dlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/jitterentropy-kcapi.c (ffffffff814c1020)
Location: crypto/jitterentropy-kcapi.c:143
Inline: False
```
**Symbols:**

```
ffffffff814c1020-ffffffff814c106d: jent_kcapi_random (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int jent_kcapi_random(struct crypto_rng *tfm, const u8 *src, unsigned int slen, u8 *rdata, unsigned int dlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/jitterentropy-kcapi.c (ffffffff814cc690)
Location: crypto/jitterentropy-kcapi.c:143
Inline: False
```
**Symbols:**

```
ffffffff814cc690-ffffffff814cc6dd: jent_kcapi_random (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int jent_kcapi_random(struct crypto_rng *tfm, const u8 *src, unsigned int slen, u8 *rdata, unsigned int dlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/jitterentropy-kcapi.c (ffffffff814e51a0)
Location: crypto/jitterentropy-kcapi.c:143
Inline: False
```
**Symbols:**

```
ffffffff814e51a0-ffffffff814e51eb: jent_kcapi_random (STB_LOCAL)
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
