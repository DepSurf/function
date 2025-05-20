# Function: <code>crypto_cipher_decrypt_one</code>

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
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/cbc.c (ffffffff814003f3)
Location: include/linux/crypto.h:1533
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_decrypt
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
In crypto/cbc.c (ffffffff8140d71f)
Location: include/linux/crypto.h:1533
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_decrypt
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
In crypto/cbc.c (ffffffff8143619f)
Location: include/linux/crypto.h:1581
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_decrypt
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
In crypto/cbc.c (ffffffff81468b84)
Location: include/linux/crypto.h:1594
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_decrypt
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
In crypto/cbc.c (ffffffff814867fd)
Location: include/linux/crypto.h:1779
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_decrypt
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
In crypto/cbc.c (ffffffff814b466e)
Location: include/linux/crypto.h:1776
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_decrypt
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
In crypto/cbc.c (ffffffff814cd3de)
Location: include/linux/crypto.h:1776
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cbc.c:crypto_cbc_decrypt
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void crypto_cipher_decrypt_one(struct crypto_cipher *tfm, u8 *dst, const u8 *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/cipher.c (ffffffff8151f420)
Location: crypto/cipher.c:86
Inline: False
Direct callers:
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cbc.c:crypto_cbc_decrypt
```
**Symbols:**

```
ffffffff8151f420-ffffffff8151f4cb: crypto_cipher_decrypt_one (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void crypto_cipher_decrypt_one(struct crypto_cipher *tfm, u8 *dst, const u8 *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/cipher.c (ffffffff8153c280)
Location: crypto/cipher.c:86
Inline: False
```
**Symbols:**

```
ffffffff8153c280-ffffffff8153c32b: crypto_cipher_decrypt_one (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void crypto_cipher_decrypt_one(struct crypto_cipher *tfm, u8 *dst, const u8 *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/cipher.c (ffffffff81544970)
Location: crypto/cipher.c:87
Inline: False
```
**Symbols:**

```
ffffffff81544970-ffffffff81544a1b: crypto_cipher_decrypt_one (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void crypto_cipher_decrypt_one(struct crypto_cipher *tfm, u8 *dst, const u8 *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/cipher.c (ffffffff815a5110)
Location: crypto/cipher.c:87
Inline: False
```
**Symbols:**

```
ffffffff815a5110-ffffffff815a51bb: crypto_cipher_decrypt_one (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void crypto_cipher_decrypt_one(struct crypto_cipher *tfm, u8 *dst, const u8 *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/cipher.c (ffffffff8164bdd0)
Location: crypto/cipher.c:87
Inline: False
```
**Symbols:**

```
ffffffff8164bdd0-ffffffff8164beae: crypto_cipher_decrypt_one (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void crypto_cipher_decrypt_one(struct crypto_cipher *tfm, u8 *dst, const u8 *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/cipher.c (ffffffff81704f10)
Location: crypto/cipher.c:87
Inline: False
```
**Symbols:**

```
ffffffff81704f10-ffffffff81704f2e: crypto_cipher_decrypt_one (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void crypto_cipher_decrypt_one(struct crypto_cipher *tfm, u8 *dst, const u8 *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/cipher.c (ffffffff8173f1e0)
Location: crypto/cipher.c:87
Inline: False
```
**Symbols:**

```
ffffffff8173f1e0-ffffffff8173f1fe: crypto_cipher_decrypt_one (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void crypto_cipher_decrypt_one(struct crypto_cipher *tfm, u8 *dst, const u8 *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/cipher.c (ffffffff81780060)
Location: crypto/cipher.c:87
Inline: False
```
**Symbols:**

```
ffffffff81780060-ffffffff8178007e: crypto_cipher_decrypt_one (STB_GLOBAL)
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
In crypto/cbc.c (ffff8000105c927c)
Location: include/linux/crypto.h:1776
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_decrypt
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
In crypto/cbc.c (c0776fec)
Location: include/linux/crypto.h:1776
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_decrypt
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
In crypto/cbc.c (c0000000007537c8)
Location: include/linux/crypto.h:1776
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_decrypt
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
In crypto/cbc.c (ffffffe00040db56)
Location: include/linux/crypto.h:1776
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_decrypt
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
In crypto/cbc.c (ffffffff814c59be)
Location: include/linux/crypto.h:1776
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_decrypt
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
In crypto/cbc.c (ffffffff814b63de)
Location: include/linux/crypto.h:1776
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_decrypt
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
In crypto/cbc.c (ffffffff814c1a4e)
Location: include/linux/crypto.h:1776
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_decrypt
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
In crypto/cbc.c (ffffffff814da51e)
Location: include/linux/crypto.h:1776
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cbc.c:crypto_cbc_decrypt
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
