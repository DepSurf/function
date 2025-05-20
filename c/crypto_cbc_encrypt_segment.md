# Function: <code>crypto_cbc_encrypt_segment</code>

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
In crypto/cbc.c (ffffffff813a92f2)
Location: crypto/cbc.c:42
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_encrypt
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
In crypto/cbc.c (ffffffff813e72b2)
Location: crypto/cbc.c:42
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_encrypt
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
In crypto/cbc.c (ffffffff8140022d)
Location: include/crypto/cbc.h:20
Inline: True
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
In crypto/cbc.c (ffffffff8140d56b)
Location: include/crypto/cbc.h:20
Inline: True
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
In crypto/cbc.c (ffffffff81435fdd)
Location: include/crypto/cbc.h:20
Inline: True
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
In crypto/cbc.c (0)
Location: include/crypto/cbc.h:20
Inline: True
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
In crypto/cbc.c (0)
Location: include/crypto/cbc.h:20
Inline: True
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
Location: include/crypto/cbc.h:15
Inline: True
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
Location: include/crypto/cbc.h:15
Inline: True
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
Location: include/crypto/cbc.h:15
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/cbc.c (ffffffff815497fc)
Location: crypto/cbc.c:16
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_encrypt
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
In crypto/cbc.c (ffffffff81551ee6)
Location: crypto/cbc.c:17
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_encrypt
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
In crypto/cbc.c (ffffffff815b2ee6)
Location: crypto/cbc.c:17
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_encrypt
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
In crypto/cbc.c (ffffffff8165baa5)
Location: crypto/cbc.c:17
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_encrypt
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int crypto_cbc_encrypt_segment(struct skcipher_walk *walk, struct crypto_skcipher *skcipher);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/cbc.c (ffffffff81715220)
Location: crypto/cbc.c:17
Inline: False
Direct callers:
  - crypto/cbc.c:crypto_cbc_encrypt
```
**Symbols:**

```
ffffffff81715220-ffffffff817152d1: crypto_cbc_encrypt_segment (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int crypto_cbc_encrypt_segment(struct skcipher_walk *walk, struct crypto_skcipher *skcipher);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/cbc.c (ffffffff81750ad0)
Location: crypto/cbc.c:17
Inline: False
Direct callers:
  - crypto/cbc.c:crypto_cbc_encrypt
```
**Symbols:**

```
ffffffff81750ad0-ffffffff81750b81: crypto_cbc_encrypt_segment (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int crypto_cbc_encrypt_segment(struct crypto_lskcipher *tfm, const u8 *src, u8 *dst, unsigned int nbytes, u8 *iv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/cbc.c (ffffffff81792a40)
Location: crypto/cbc.c:15
Inline: False
Direct callers:
  - crypto/cbc.c:crypto_cbc_encrypt
```
**Symbols:**

```
ffffffff81792a40-ffffffff81792ae0: crypto_cbc_encrypt_segment (STB_LOCAL)
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
In crypto/cbc.c (0)
Location: include/crypto/cbc.h:15
Inline: True
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
Location: include/crypto/cbc.h:15
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_encrypt
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
Location: include/crypto/cbc.h:15
Inline: True
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
In crypto/cbc.c (ffffffe00040dc80)
Location: include/crypto/cbc.h:15
Inline: True
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
Location: include/crypto/cbc.h:15
Inline: True
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
Location: include/crypto/cbc.h:15
Inline: True
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
Location: include/crypto/cbc.h:15
Inline: True
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
Location: include/crypto/cbc.h:15
Inline: True
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
