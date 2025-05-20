# Function: <code>crypto_cipher_alg</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/ecb.c (0)
Location: include/crypto/algapi.h:273
Inline: True
```
```
In crypto/cbc.c (ffffffff813a92e0)
Location: include/crypto/algapi.h:273
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_encrypt
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cbc.c:crypto_cbc_decrypt
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/ecb.c (0)
Location: include/crypto/algapi.h:349
Inline: True
```
```
In crypto/cbc.c (ffffffff813e745e)
Location: include/crypto/algapi.h:349
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cbc.c:crypto_cbc_encrypt
```
```
In crypto/xts.c (ffffffff813e84b8)
Location: include/crypto/algapi.h:349
Inline: True
Inline callers:
  - crypto/xts.c:decrypt
  - crypto/xts.c:decrypt
  - crypto/xts.c:encrypt
  - crypto/xts.c:encrypt
```
```
In crypto/ctr.c (ffffffff813e89ff)
Location: include/crypto/algapi.h:349
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/ecb.c (0)
Location: include/crypto/algapi.h:279
Inline: True
```
```
In crypto/ctr.c (ffffffff8140200f)
Location: include/crypto/algapi.h:279
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/ecb.c (0)
Location: include/crypto/algapi.h:295
Inline: True
```
```
In crypto/ctr.c (0)
Location: include/crypto/algapi.h:295
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/ecb.c (0)
Location: include/crypto/algapi.h:314
Inline: True
```
```
In crypto/ctr.c (0)
Location: include/crypto/algapi.h:314
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/ecb.c (ffffffff8146860f)
Location: include/crypto/algapi.h:321
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_decrypt
  - crypto/ecb.c:crypto_ecb_encrypt
```
```
In crypto/ctr.c (0)
Location: include/crypto/algapi.h:321
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/ecb.c (ffffffff8148627f)
Location: include/crypto/algapi.h:323
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_decrypt
  - crypto/ecb.c:crypto_ecb_encrypt
```
```
In crypto/ctr.c (0)
Location: include/crypto/algapi.h:323
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/ecb.c (ffffffff814b440e)
Location: include/crypto/algapi.h:317
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_decrypt
  - crypto/ecb.c:crypto_ecb_encrypt
```
```
In crypto/ctr.c (0)
Location: include/crypto/algapi.h:317
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/ecb.c (ffffffff814cd17e)
Location: include/crypto/algapi.h:317
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_decrypt
  - crypto/ecb.c:crypto_ecb_encrypt
```
```
In crypto/ctr.c (0)
Location: include/crypto/algapi.h:317
Inline: True
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
In crypto/cipher.c (ffffffff8151f3e5)
Location: include/crypto/algapi.h:226
Inline: True
Inline callers:
  - crypto/cipher.c:crypto_cipher_setkey
  - crypto/cipher.c:setkey_unaligned
```
```
In crypto/ecb.c (ffffffff8152c61e)
Location: include/crypto/algapi.h:226
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_decrypt
  - crypto/ecb.c:crypto_ecb_encrypt
```
```
In crypto/ctr.c (ffffffff8152e4fd)
Location: include/crypto/algapi.h:226
Inline: True
Inline callers:
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
In crypto/cipher.c (ffffffff8153c245)
Location: include/crypto/algapi.h:226
Inline: True
Inline callers:
  - crypto/cipher.c:crypto_cipher_setkey
  - crypto/cipher.c:setkey_unaligned
```
```
In crypto/ecb.c (ffffffff8154960e)
Location: include/crypto/algapi.h:226
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_decrypt
  - crypto/ecb.c:crypto_ecb_encrypt
```
```
In crypto/cbc.c (ffffffff815499e7)
Location: include/crypto/algapi.h:226
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_decrypt_inplace
  - crypto/cbc.c:crypto_cbc_decrypt_segment
```
```
In crypto/ctr.c (ffffffff8154b49d)
Location: include/crypto/algapi.h:226
Inline: True
Inline callers:
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
In crypto/cipher.c (ffffffff81544935)
Location: include/crypto/internal/cipher.h:213
Inline: True
Inline callers:
  - crypto/cipher.c:crypto_cipher_setkey
  - crypto/cipher.c:setkey_unaligned
```
```
In crypto/ecb.c (ffffffff81551cfe)
Location: include/crypto/internal/cipher.h:213
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_decrypt
  - crypto/ecb.c:crypto_ecb_encrypt
```
```
In crypto/cbc.c (ffffffff815520fd)
Location: include/crypto/internal/cipher.h:213
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_decrypt
```
```
In crypto/ctr.c (ffffffff81553ab8)
Location: include/crypto/internal/cipher.h:213
Inline: True
Inline callers:
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
In crypto/cipher.c (ffffffff815a50d5)
Location: include/crypto/internal/cipher.h:213
Inline: True
Inline callers:
  - crypto/cipher.c:crypto_cipher_setkey
  - crypto/cipher.c:setkey_unaligned
```
```
In crypto/ecb.c (ffffffff815b2cfe)
Location: include/crypto/internal/cipher.h:213
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_decrypt
  - crypto/ecb.c:crypto_ecb_encrypt
```
```
In crypto/cbc.c (ffffffff815b30fd)
Location: include/crypto/internal/cipher.h:213
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_decrypt
```
```
In crypto/ctr.c (ffffffff815b4ae8)
Location: include/crypto/internal/cipher.h:213
Inline: True
Inline callers:
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
In crypto/cipher.c (ffffffff8164bc85)
Location: include/crypto/internal/cipher.h:213
Inline: True
Inline callers:
  - crypto/cipher.c:crypto_cipher_setkey
  - crypto/cipher.c:setkey_unaligned
```
```
In crypto/ecb.c (ffffffff8165b87e)
Location: include/crypto/internal/cipher.h:213
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_decrypt
  - crypto/ecb.c:crypto_ecb_encrypt
```
```
In crypto/cbc.c (ffffffff8165bd60)
Location: include/crypto/internal/cipher.h:213
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cbc.c:crypto_cbc_decrypt_inplace
```
```
In crypto/ctr.c (ffffffff8165d9f9)
Location: include/crypto/internal/cipher.h:213
Inline: True
Inline callers:
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
In crypto/cipher.c (ffffffff81705015)
Location: include/crypto/internal/cipher.h:213
Inline: True
Inline callers:
  - crypto/cipher.c:crypto_cipher_setkey
  - crypto/cipher.c:setkey_unaligned
```
```
In crypto/ecb.c (ffffffff8171505e)
Location: include/crypto/internal/cipher.h:213
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_decrypt
  - crypto/ecb.c:crypto_ecb_encrypt
```
```
In crypto/cbc.c (ffffffff817155ab)
Location: include/crypto/internal/cipher.h:213
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_decrypt_inplace
  - crypto/cbc.c:crypto_cbc_decrypt_segment
  - crypto/cbc.c:crypto_cbc_encrypt_inplace
  - crypto/cbc.c:crypto_cbc_encrypt_segment
```
```
In crypto/ctr.c (ffffffff81717589)
Location: include/crypto/internal/cipher.h:213
Inline: True
Inline callers:
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
In crypto/cipher.c (ffffffff8173f2e5)
Location: include/crypto/internal/cipher.h:215
Inline: True
Inline callers:
  - crypto/cipher.c:crypto_cipher_setkey
  - crypto/cipher.c:setkey_unaligned
```
```
In crypto/ecb.c (ffffffff8175090e)
Location: include/crypto/internal/cipher.h:215
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_decrypt
  - crypto/ecb.c:crypto_ecb_encrypt
```
```
In crypto/cbc.c (ffffffff81750e5b)
Location: include/crypto/internal/cipher.h:215
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_decrypt_inplace
  - crypto/cbc.c:crypto_cbc_decrypt_segment
  - crypto/cbc.c:crypto_cbc_encrypt_inplace
  - crypto/cbc.c:crypto_cbc_encrypt_segment
```
```
In crypto/ctr.c (ffffffff81752ea9)
Location: include/crypto/internal/cipher.h:215
Inline: True
Inline callers:
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
In crypto/cipher.c (ffffffff81780165)
Location: include/crypto/internal/cipher.h:215
Inline: True
Inline callers:
  - crypto/cipher.c:crypto_cipher_setkey
  - crypto/cipher.c:setkey_unaligned
```
```
In crypto/ecb.c (ffffffff81792908)
Location: include/crypto/internal/cipher.h:215
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_decrypt2
  - crypto/ecb.c:crypto_ecb_encrypt2
```
```
In crypto/ctr.c (ffffffff81794e49)
Location: include/crypto/internal/cipher.h:215
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_crypt
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/ecb.c (ffff8000105c8fd4)
Location: include/crypto/algapi.h:317
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_decrypt
  - crypto/ecb.c:crypto_ecb_encrypt
```
```
In crypto/ctr.c (0)
Location: include/crypto/algapi.h:317
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/ecb.c (c0776c70)
Location: include/crypto/algapi.h:317
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_decrypt
  - crypto/ecb.c:crypto_ecb_encrypt
```
```
In crypto/ctr.c (0)
Location: include/crypto/algapi.h:317
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/ecb.c (c000000000753488)
Location: include/crypto/algapi.h:317
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_decrypt
  - crypto/ecb.c:crypto_ecb_encrypt
```
```
In crypto/ctr.c (0)
Location: include/crypto/algapi.h:317
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/ecb.c (ffffffe00040d95c)
Location: include/crypto/algapi.h:317
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_decrypt
  - crypto/ecb.c:crypto_ecb_encrypt
```
```
In crypto/ctr.c (0)
Location: include/crypto/algapi.h:317
Inline: True
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/ecb.c (ffffffff814c575e)
Location: include/crypto/algapi.h:317
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_decrypt
  - crypto/ecb.c:crypto_ecb_encrypt
```
```
In crypto/ctr.c (0)
Location: include/crypto/algapi.h:317
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/ecb.c (ffffffff814b617e)
Location: include/crypto/algapi.h:317
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_decrypt
  - crypto/ecb.c:crypto_ecb_encrypt
```
```
In crypto/ctr.c (0)
Location: include/crypto/algapi.h:317
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/ecb.c (ffffffff814c17ee)
Location: include/crypto/algapi.h:317
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_decrypt
  - crypto/ecb.c:crypto_ecb_encrypt
```
```
In crypto/ctr.c (0)
Location: include/crypto/algapi.h:317
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/ecb.c (ffffffff814da2be)
Location: include/crypto/algapi.h:317
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_decrypt
  - crypto/ecb.c:crypto_ecb_encrypt
```
```
In crypto/ctr.c (0)
Location: include/crypto/algapi.h:317
Inline: True
```
</details>
</li>
</ul>

## Differences
