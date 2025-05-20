# Function: <code>crypto_cbc_decrypt_segment</code>

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
In crypto/cbc.c (ffffffff813a949e)
Location: crypto/cbc.c:114
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
In crypto/cbc.c (ffffffff813e745e)
Location: crypto/cbc.c:114
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
In crypto/cbc.c (ffffffff814003c1)
Location: include/crypto/cbc.h:85
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
In crypto/cbc.c (ffffffff8140d6fc)
Location: include/crypto/cbc.h:85
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
In crypto/cbc.c (ffffffff8143617c)
Location: include/crypto/cbc.h:85
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
In crypto/cbc.c (ffffffff81468b5c)
Location: include/crypto/cbc.h:85
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
In crypto/cbc.c (ffffffff814867dd)
Location: include/crypto/cbc.h:85
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
In crypto/cbc.c (0)
Location: include/crypto/cbc.h:80
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
In crypto/cbc.c (0)
Location: include/crypto/cbc.h:80
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
In crypto/cbc.c (0)
Location: include/crypto/cbc.h:80
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_decrypt
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int crypto_cbc_decrypt_segment(struct skcipher_walk *walk, struct crypto_skcipher *skcipher);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/cbc.c (ffffffff815498f0)
Location: crypto/cbc.c:91
Inline: False
Direct callers:
  - crypto/cbc.c:crypto_cbc_decrypt
```
**Symbols:**

```
ffffffff815498f0-ffffffff815499a4: crypto_cbc_decrypt_segment (STB_LOCAL)
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
In crypto/cbc.c (0)
Location: crypto/cbc.c:92
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
In crypto/cbc.c (0)
Location: crypto/cbc.c:92
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_decrypt
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/cbc.c (ffffffff8165bd2f)
Location: crypto/cbc.c:92
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_decrypt
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int crypto_cbc_decrypt_segment(struct skcipher_walk *walk, struct crypto_skcipher *skcipher);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/cbc.c (ffffffff81715490)
Location: crypto/cbc.c:92
Inline: False
Direct callers:
  - crypto/cbc.c:crypto_cbc_decrypt
```
**Symbols:**

```
ffffffff81715490-ffffffff8171554e: crypto_cbc_decrypt_segment (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int crypto_cbc_decrypt_segment(struct skcipher_walk *walk, struct crypto_skcipher *skcipher);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/cbc.c (ffffffff81750d40)
Location: crypto/cbc.c:92
Inline: False
Direct callers:
  - crypto/cbc.c:crypto_cbc_decrypt
```
**Symbols:**

```
ffffffff81750d40-ffffffff81750dfe: crypto_cbc_decrypt_segment (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int crypto_cbc_decrypt_segment(struct crypto_lskcipher *tfm, const u8 *src, u8 *dst, unsigned int nbytes, u8 *oiv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/cbc.c (ffffffff81792c10)
Location: crypto/cbc.c:69
Inline: False
Direct callers:
  - crypto/cbc.c:crypto_cbc_decrypt
```
**Symbols:**

```
ffffffff81792c10-ffffffff81792cba: crypto_cbc_decrypt_segment (STB_LOCAL)
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
In crypto/cbc.c (ffff8000105c926c)
Location: include/crypto/cbc.h:80
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
In crypto/cbc.c (0)
Location: include/crypto/cbc.h:80
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
In crypto/cbc.c (0)
Location: include/crypto/cbc.h:80
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
In crypto/cbc.c (ffffffe00040db4a)
Location: include/crypto/cbc.h:80
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
In crypto/cbc.c (0)
Location: include/crypto/cbc.h:80
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
In crypto/cbc.c (0)
Location: include/crypto/cbc.h:80
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
In crypto/cbc.c (0)
Location: include/crypto/cbc.h:80
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
In crypto/cbc.c (0)
Location: include/crypto/cbc.h:80
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
<code>unsigned int nbytes</code>
</li>
<li>
<b>Param added. </b>
<code>u8 *oiv</code>
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
