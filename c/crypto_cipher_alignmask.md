# Function: <code>crypto_cipher_alignmask</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/ctr.c (0)
Location: include/linux/crypto.h:1460
Inline: True
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
In crypto/ctr.c (0)
Location: include/linux/crypto.h:1463
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
In crypto/ctr.c (0)
Location: include/linux/crypto.h:1463
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
In crypto/ctr.c (0)
Location: include/linux/crypto.h:1511
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
In crypto/ctr.c (ffffffff8146adfe)
Location: include/linux/crypto.h:1524
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
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
In crypto/ctr.c (ffffffff8148865e)
Location: include/linux/crypto.h:1709
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
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
In crypto/ctr.c (ffffffff814b608a)
Location: include/linux/crypto.h:1706
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
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
In crypto/ctr.c (ffffffff814cf28a)
Location: include/linux/crypto.h:1706
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/cipher.c (ffffffff8151f445)
Location: include/linux/crypto.h:807
Inline: True
Inline callers:
  - crypto/cipher.c:crypto_cipher_decrypt_one
  - crypto/cipher.c:crypto_cipher_encrypt_one
  - crypto/cipher.c:crypto_cipher_setkey
  - crypto/cipher.c:setkey_unaligned
```
```
In crypto/ctr.c (ffffffff8152e4fd)
Location: include/linux/crypto.h:807
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/cipher.c (ffffffff8153c2a5)
Location: include/linux/crypto.h:843
Inline: True
Inline callers:
  - crypto/cipher.c:crypto_cipher_decrypt_one
  - crypto/cipher.c:crypto_cipher_encrypt_one
  - crypto/cipher.c:crypto_cipher_setkey
  - crypto/cipher.c:setkey_unaligned
```
```
In crypto/ctr.c (ffffffff8154b49d)
Location: include/linux/crypto.h:843
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/cipher.c (ffffffff81544995)
Location: include/crypto/internal/cipher.h:114
Inline: True
Inline callers:
  - crypto/cipher.c:crypto_cipher_decrypt_one
  - crypto/cipher.c:crypto_cipher_encrypt_one
  - crypto/cipher.c:crypto_cipher_setkey
  - crypto/cipher.c:setkey_unaligned
```
```
In crypto/ctr.c (ffffffff81553ab8)
Location: include/crypto/internal/cipher.h:114
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/cipher.c (ffffffff815a5135)
Location: include/crypto/internal/cipher.h:114
Inline: True
Inline callers:
  - crypto/cipher.c:crypto_cipher_decrypt_one
  - crypto/cipher.c:crypto_cipher_encrypt_one
  - crypto/cipher.c:crypto_cipher_setkey
  - crypto/cipher.c:setkey_unaligned
```
```
In crypto/ctr.c (ffffffff815b4ae8)
Location: include/crypto/internal/cipher.h:114
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/cipher.c (ffffffff8164bdf5)
Location: include/crypto/internal/cipher.h:114
Inline: True
Inline callers:
  - crypto/cipher.c:crypto_cipher_decrypt_one
  - crypto/cipher.c:crypto_cipher_encrypt_one
  - crypto/cipher.c:crypto_cipher_setkey
  - crypto/cipher.c:setkey_unaligned
```
```
In crypto/ctr.c (ffffffff8165d9f9)
Location: include/crypto/internal/cipher.h:114
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/cipher.c (ffffffff81704dea)
Location: include/crypto/internal/cipher.h:114
Inline: True
Inline callers:
  - crypto/cipher.c:cipher_crypt_one
  - crypto/cipher.c:crypto_cipher_setkey
  - crypto/cipher.c:setkey_unaligned
```
```
In crypto/ctr.c (ffffffff81717589)
Location: include/crypto/internal/cipher.h:114
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/cipher.c (ffffffff8173f0ba)
Location: include/crypto/internal/cipher.h:114
Inline: True
Inline callers:
  - crypto/cipher.c:cipher_crypt_one
  - crypto/cipher.c:crypto_cipher_setkey
  - crypto/cipher.c:setkey_unaligned
```
```
In crypto/ctr.c (ffffffff81752ea9)
Location: include/crypto/internal/cipher.h:114
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/cipher.c (ffffffff8177ff3a)
Location: include/crypto/internal/cipher.h:114
Inline: True
Inline callers:
  - crypto/cipher.c:cipher_crypt_one
  - crypto/cipher.c:crypto_cipher_setkey
  - crypto/cipher.c:setkey_unaligned
```
```
In crypto/ctr.c (ffffffff81794e49)
Location: include/crypto/internal/cipher.h:114
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
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
In crypto/ctr.c (ffff8000105cb230)
Location: include/linux/crypto.h:1706
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
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
In crypto/ctr.c (c0778d78)
Location: include/linux/crypto.h:1706
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
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
In crypto/ctr.c (c000000000756200)
Location: include/linux/crypto.h:1706
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
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
In crypto/ctr.c (ffffffe00040f3c2)
Location: include/linux/crypto.h:1706
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
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
In crypto/ctr.c (ffffffff814c786a)
Location: include/linux/crypto.h:1706
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
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
In crypto/ctr.c (ffffffff814b828a)
Location: include/linux/crypto.h:1706
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
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
In crypto/ctr.c (ffffffff814c38fa)
Location: include/linux/crypto.h:1706
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
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
In crypto/ctr.c (ffffffff814dc3ca)
Location: include/linux/crypto.h:1706
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
```
</details>
</li>
</ul>

## Differences
