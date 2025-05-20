# Function: <code>crypto_cbc_decrypt_inplace</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/cbc.c (ffffffff813a9573)
Location: crypto/cbc.c:140
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_decrypt
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/cbc.c (ffffffff813e7533)
Location: crypto/cbc.c:140
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_decrypt
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/cbc.c (ffffffff81400484)
Location: include/crypto/cbc.h:109
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_decrypt
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/cbc.c (ffffffff8140d7b4)
Location: include/crypto/cbc.h:109
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_decrypt
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/cbc.c (ffffffff8143623a)
Location: include/crypto/cbc.h:109
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_decrypt
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/cbc.c (ffffffff81468c0a)
Location: include/crypto/cbc.h:109
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_decrypt
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/cbc.c (ffffffff81486883)
Location: include/crypto/cbc.h:109
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_decrypt
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/cbc.c (ffffffff814b46f7)
Location: include/crypto/cbc.h:104
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_decrypt
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/cbc.c (ffffffff814cd467)
Location: include/crypto/cbc.h:104
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_decrypt
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/cbc.c (ffffffff8152ca38)
Location: include/crypto/cbc.h:104
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_decrypt
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int crypto_cbc_decrypt_inplace(struct skcipher_walk *walk, struct crypto_skcipher *skcipher);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/cbc.c (0)
Location: crypto/cbc.c:121
Inline: False
Direct callers:
  - crypto/cbc.c:crypto_cbc_decrypt
```
**Symbols:**

```
ffffffff815499b0-ffffffff81549aad: crypto_cbc_decrypt_inplace (STB_LOCAL)
ffffffff81bf20d3-ffffffff81bf20df: crypto_cbc_decrypt_inplace.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/cbc.c (ffffffff815520fd)
Location: crypto/cbc.c:122
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_decrypt
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/cbc.c (ffffffff815b30fd)
Location: crypto/cbc.c:122
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_decrypt
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int crypto_cbc_decrypt_inplace(struct skcipher_walk *walk, struct crypto_skcipher *skcipher);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/cbc.c (0)
Location: crypto/cbc.c:122
Inline: False
Direct callers:
  - crypto/cbc.c:crypto_cbc_decrypt
```
**Symbols:**

```
ffffffff8165bb90-ffffffff8165bca2: crypto_cbc_decrypt_inplace (STB_LOCAL)
ffffffff81e8aa70-ffffffff81e8aa7c: crypto_cbc_decrypt_inplace.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int crypto_cbc_decrypt_inplace(struct skcipher_walk *walk, struct crypto_skcipher *skcipher);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/cbc.c (ffffffff81715560)
Location: crypto/cbc.c:122
Inline: False
Direct callers:
  - crypto/cbc.c:crypto_cbc_decrypt
```
**Symbols:**

```
ffffffff81715560-ffffffff8171567e: crypto_cbc_decrypt_inplace (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int crypto_cbc_decrypt_inplace(struct skcipher_walk *walk, struct crypto_skcipher *skcipher);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/cbc.c (ffffffff81750e10)
Location: crypto/cbc.c:122
Inline: False
Direct callers:
  - crypto/cbc.c:crypto_cbc_decrypt
```
**Symbols:**

```
ffffffff81750e10-ffffffff81750f2e: crypto_cbc_decrypt_inplace (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int crypto_cbc_decrypt_inplace(struct crypto_lskcipher *tfm, u8 *src, unsigned int nbytes, u8 *iv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/cbc.c (ffffffff81792cd0)
Location: crypto/cbc.c:94
Inline: False
Direct callers:
  - crypto/cbc.c:crypto_cbc_decrypt
```
**Symbols:**

```
ffffffff81792cd0-ffffffff81792de7: crypto_cbc_decrypt_inplace (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/cbc.c (ffff8000105c9308)
Location: include/crypto/cbc.h:104
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_decrypt
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/cbc.c (c0777070)
Location: include/crypto/cbc.h:104
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_decrypt
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/cbc.c (c000000000753880)
Location: include/crypto/cbc.h:104
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_decrypt
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/cbc.c (ffffffe00040dbbc)
Location: include/crypto/cbc.h:104
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_decrypt
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/cbc.c (ffffffff814c5a47)
Location: include/crypto/cbc.h:104
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_decrypt
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/cbc.c (ffffffff814b6467)
Location: include/crypto/cbc.h:104
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_decrypt
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/cbc.c (ffffffff814c1ad7)
Location: include/crypto/cbc.h:104
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_decrypt
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/cbc.c (ffffffff814da5a7)
Location: include/crypto/cbc.h:104
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_decrypt
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<code>u8 *src</code>
</li>
<li>
<b>Param added. </b>
<code>unsigned int nbytes</code>
</li>
<li>
<b>Param added. </b>
<code>u8 *iv</code>
</li>
<li>
<b>Param removed. </b>
<code>struct skcipher_walk *walk</code>
</li>
<li>
<b>Param removed. </b>
<code>struct crypto_skcipher *skcipher</code>
</li>
</ul>
</details>
</li>
</ul>
