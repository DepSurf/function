# Function: <code>crypto_cbc_encrypt_inplace</code>

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
In crypto/cbc.c (ffffffff813a92e0)
Location: crypto/cbc.c:66
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
In crypto/cbc.c (ffffffff813e72a0)
Location: crypto/cbc.c:66
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
In crypto/cbc.c (ffffffff814002d6)
Location: include/crypto/cbc.h:42
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
In crypto/cbc.c (ffffffff8140d606)
Location: include/crypto/cbc.h:42
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
In crypto/cbc.c (ffffffff81436083)
Location: include/crypto/cbc.h:42
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
Location: include/crypto/cbc.h:42
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
Location: include/crypto/cbc.h:42
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
Location: include/crypto/cbc.h:37
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
Location: include/crypto/cbc.h:37
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
Location: include/crypto/cbc.h:37
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
In crypto/cbc.c (0)
Location: crypto/cbc.c:44
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
In crypto/cbc.c (0)
Location: crypto/cbc.c:45
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
In crypto/cbc.c (0)
Location: crypto/cbc.c:45
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
In crypto/cbc.c (0)
Location: crypto/cbc.c:45
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
int crypto_cbc_encrypt_inplace(struct skcipher_walk *walk, struct crypto_skcipher *skcipher);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/cbc.c (ffffffff817152f0)
Location: crypto/cbc.c:45
Inline: False
Direct callers:
  - crypto/cbc.c:crypto_cbc_encrypt
```
**Symbols:**

```
ffffffff817152f0-ffffffff81715397: crypto_cbc_encrypt_inplace (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int crypto_cbc_encrypt_inplace(struct skcipher_walk *walk, struct crypto_skcipher *skcipher);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/cbc.c (ffffffff81750ba0)
Location: crypto/cbc.c:45
Inline: False
Direct callers:
  - crypto/cbc.c:crypto_cbc_encrypt
```
**Symbols:**

```
ffffffff81750ba0-ffffffff81750c47: crypto_cbc_encrypt_inplace (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int crypto_cbc_encrypt_inplace(struct crypto_lskcipher *tfm, u8 *src, unsigned int nbytes, u8 *oiv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/cbc.c (ffffffff81792af0)
Location: crypto/cbc.c:30
Inline: False
Direct callers:
  - crypto/cbc.c:crypto_cbc_encrypt
```
**Symbols:**

```
ffffffff81792af0-ffffffff81792b8c: crypto_cbc_encrypt_inplace (STB_LOCAL)
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
Location: include/crypto/cbc.h:37
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
Location: include/crypto/cbc.h:37
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
Location: include/crypto/cbc.h:37
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
In crypto/cbc.c (ffffffe00040dce4)
Location: include/crypto/cbc.h:37
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
Location: include/crypto/cbc.h:37
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
Location: include/crypto/cbc.h:37
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
Location: include/crypto/cbc.h:37
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
Location: include/crypto/cbc.h:37
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
<code>u8 *src</code>
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
