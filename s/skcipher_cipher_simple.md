# Function: <code>skcipher_cipher_simple</code>

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
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff814a8875)
Location: include/crypto/internal/skcipher.h:268
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_simple
```
```
In crypto/ecb.c (ffffffff814b4405)
Location: include/crypto/internal/skcipher.h:268
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_decrypt
  - crypto/ecb.c:crypto_ecb_encrypt
```
```
In crypto/cbc.c (ffffffff814b466e)
Location: include/crypto/internal/skcipher.h:268
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cbc.c:crypto_cbc_decrypt
```
```
In crypto/ctr.c (ffffffff814b5f95)
Location: include/crypto/internal/skcipher.h:268
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_crypt
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
In crypto/skcipher.c (ffffffff814c34d5)
Location: include/crypto/internal/skcipher.h:243
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_simple
```
```
In crypto/ecb.c (ffffffff814cd175)
Location: include/crypto/internal/skcipher.h:243
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_decrypt
  - crypto/ecb.c:crypto_ecb_encrypt
```
```
In crypto/cbc.c (ffffffff814cd3de)
Location: include/crypto/internal/skcipher.h:243
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cbc.c:crypto_cbc_decrypt
```
```
In crypto/ctr.c (ffffffff814cf195)
Location: include/crypto/internal/skcipher.h:243
Inline: True
Inline callers:
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
In crypto/skcipher.c (ffffffff81522da5)
Location: include/crypto/internal/skcipher.h:204
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_simple
```
```
In crypto/ecb.c (ffffffff8152c615)
Location: include/crypto/internal/skcipher.h:204
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_decrypt
  - crypto/ecb.c:crypto_ecb_encrypt
```
```
In crypto/cbc.c (ffffffff8152ca89)
Location: include/crypto/internal/skcipher.h:204
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cbc.c:crypto_cbc_decrypt
```
```
In crypto/ctr.c (0)
Location: include/crypto/internal/skcipher.h:204
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
In crypto/skcipher.c (ffffffff8153fcf5)
Location: include/crypto/internal/skcipher.h:204
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_simple
```
```
In crypto/ecb.c (ffffffff81549605)
Location: include/crypto/internal/skcipher.h:204
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_decrypt
  - crypto/ecb.c:crypto_ecb_encrypt
```
```
In crypto/cbc.c (ffffffff815499e7)
Location: include/crypto/internal/skcipher.h:204
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_decrypt_inplace
  - crypto/cbc.c:crypto_cbc_decrypt_segment
  - crypto/cbc.c:crypto_cbc_encrypt
```
```
In crypto/ctr.c (0)
Location: include/crypto/internal/skcipher.h:204
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
In crypto/skcipher.c (ffffffff81548265)
Location: include/crypto/internal/skcipher.h:204
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_simple
```
```
In crypto/ecb.c (ffffffff81551cf5)
Location: include/crypto/internal/skcipher.h:204
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_decrypt
  - crypto/ecb.c:crypto_ecb_encrypt
```
```
In crypto/cbc.c (ffffffff815520fd)
Location: include/crypto/internal/skcipher.h:204
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cbc.c:crypto_cbc_encrypt
```
```
In crypto/ctr.c (0)
Location: include/crypto/internal/skcipher.h:204
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
In crypto/skcipher.c (ffffffff815a8a45)
Location: include/crypto/internal/skcipher.h:204
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_simple
```
```
In crypto/ecb.c (ffffffff815b2cf5)
Location: include/crypto/internal/skcipher.h:204
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_decrypt
  - crypto/ecb.c:crypto_ecb_encrypt
```
```
In crypto/cbc.c (ffffffff815b30fd)
Location: include/crypto/internal/skcipher.h:204
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cbc.c:crypto_cbc_encrypt
```
```
In crypto/ctr.c (0)
Location: include/crypto/internal/skcipher.h:204
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
In crypto/skcipher.c (ffffffff8164fe35)
Location: include/crypto/internal/skcipher.h:204
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_simple
```
```
In crypto/ecb.c (ffffffff8165b875)
Location: include/crypto/internal/skcipher.h:204
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_decrypt
  - crypto/ecb.c:crypto_ecb_encrypt
```
```
In crypto/cbc.c (ffffffff8165bd60)
Location: include/crypto/internal/skcipher.h:204
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cbc.c:crypto_cbc_decrypt_inplace
  - crypto/cbc.c:crypto_cbc_encrypt
```
```
In crypto/ctr.c (0)
Location: include/crypto/internal/skcipher.h:204
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
In crypto/skcipher.c (ffffffff81709315)
Location: include/crypto/internal/skcipher.h:234
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_simple
```
```
In crypto/ecb.c (ffffffff81715055)
Location: include/crypto/internal/skcipher.h:234
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_decrypt
  - crypto/ecb.c:crypto_ecb_encrypt
```
```
In crypto/cbc.c (ffffffff817155a3)
Location: include/crypto/internal/skcipher.h:234
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_decrypt_inplace
  - crypto/cbc.c:crypto_cbc_decrypt_segment
  - crypto/cbc.c:crypto_cbc_encrypt_inplace
  - crypto/cbc.c:crypto_cbc_encrypt_segment
```
```
In crypto/ctr.c (0)
Location: include/crypto/internal/skcipher.h:234
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
In crypto/skcipher.c (ffffffff81742b55)
Location: include/crypto/internal/skcipher.h:234
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_simple
```
```
In crypto/ecb.c (ffffffff81750905)
Location: include/crypto/internal/skcipher.h:234
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_decrypt
  - crypto/ecb.c:crypto_ecb_encrypt
```
```
In crypto/cbc.c (ffffffff81750e53)
Location: include/crypto/internal/skcipher.h:234
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_decrypt_inplace
  - crypto/cbc.c:crypto_cbc_decrypt_segment
  - crypto/cbc.c:crypto_cbc_encrypt_inplace
  - crypto/cbc.c:crypto_cbc_encrypt_segment
```
```
In crypto/ctr.c (0)
Location: include/crypto/internal/skcipher.h:234
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
In crypto/skcipher.c (ffffffff81784d95)
Location: include/crypto/internal/skcipher.h:265
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_simple
```
```
In crypto/ctr.c (0)
Location: include/crypto/internal/skcipher.h:265
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
In crypto/skcipher.c (ffff8000105bdd0c)
Location: include/crypto/internal/skcipher.h:243
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_simple
```
```
In crypto/ecb.c (ffff8000105c8fc8)
Location: include/crypto/internal/skcipher.h:243
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_decrypt
  - crypto/ecb.c:crypto_ecb_encrypt
```
```
In crypto/cbc.c (ffff8000105c9278)
Location: include/crypto/internal/skcipher.h:243
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cbc.c:crypto_cbc_decrypt
```
```
In crypto/ctr.c (ffff8000105cb158)
Location: include/crypto/internal/skcipher.h:243
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_crypt
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
In crypto/skcipher.c (c076bb48)
Location: include/crypto/internal/skcipher.h:243
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_simple
```
```
In crypto/ecb.c (c0776c68)
Location: include/crypto/internal/skcipher.h:243
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_decrypt
  - crypto/ecb.c:crypto_ecb_encrypt
```
```
In crypto/cbc.c (c0776fe8)
Location: include/crypto/internal/skcipher.h:243
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cbc.c:crypto_cbc_encrypt
  - crypto/cbc.c:crypto_cbc_encrypt
```
```
In crypto/ctr.c (c0778cb4)
Location: include/crypto/internal/skcipher.h:243
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_crypt
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
In crypto/skcipher.c (c0000000007451f4)
Location: include/crypto/internal/skcipher.h:243
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_simple
```
```
In crypto/ecb.c (c000000000753480)
Location: include/crypto/internal/skcipher.h:243
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_decrypt
  - crypto/ecb.c:crypto_ecb_encrypt
```
```
In crypto/cbc.c (c0000000007537c4)
Location: include/crypto/internal/skcipher.h:243
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cbc.c:crypto_cbc_decrypt
```
```
In crypto/ctr.c (c0000000007560e4)
Location: include/crypto/internal/skcipher.h:243
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_crypt
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
In crypto/skcipher.c (ffffffe00040321e)
Location: include/crypto/internal/skcipher.h:243
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_simple
```
```
In crypto/ecb.c (ffffffe00040d956)
Location: include/crypto/internal/skcipher.h:243
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_decrypt
  - crypto/ecb.c:crypto_ecb_encrypt
```
```
In crypto/cbc.c (ffffffe00040db52)
Location: include/crypto/internal/skcipher.h:243
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cbc.c:crypto_cbc_decrypt
```
```
In crypto/ctr.c (ffffffe00040f316)
Location: include/crypto/internal/skcipher.h:243
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_crypt
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
In crypto/skcipher.c (ffffffff814bbab5)
Location: include/crypto/internal/skcipher.h:243
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_simple
```
```
In crypto/ecb.c (ffffffff814c5755)
Location: include/crypto/internal/skcipher.h:243
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_decrypt
  - crypto/ecb.c:crypto_ecb_encrypt
```
```
In crypto/cbc.c (ffffffff814c59be)
Location: include/crypto/internal/skcipher.h:243
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cbc.c:crypto_cbc_decrypt
```
```
In crypto/ctr.c (ffffffff814c7775)
Location: include/crypto/internal/skcipher.h:243
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_crypt
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
In crypto/skcipher.c (ffffffff814ac4d5)
Location: include/crypto/internal/skcipher.h:243
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_simple
```
```
In crypto/ecb.c (ffffffff814b6175)
Location: include/crypto/internal/skcipher.h:243
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_decrypt
  - crypto/ecb.c:crypto_ecb_encrypt
```
```
In crypto/cbc.c (ffffffff814b63de)
Location: include/crypto/internal/skcipher.h:243
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cbc.c:crypto_cbc_decrypt
```
```
In crypto/ctr.c (ffffffff814b8195)
Location: include/crypto/internal/skcipher.h:243
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_crypt
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
In crypto/skcipher.c (ffffffff814b7b45)
Location: include/crypto/internal/skcipher.h:243
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_simple
```
```
In crypto/ecb.c (ffffffff814c17e5)
Location: include/crypto/internal/skcipher.h:243
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_decrypt
  - crypto/ecb.c:crypto_ecb_encrypt
```
```
In crypto/cbc.c (ffffffff814c1a4e)
Location: include/crypto/internal/skcipher.h:243
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cbc.c:crypto_cbc_decrypt
```
```
In crypto/ctr.c (ffffffff814c3805)
Location: include/crypto/internal/skcipher.h:243
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_crypt
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
In crypto/skcipher.c (ffffffff814d0625)
Location: include/crypto/internal/skcipher.h:243
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_simple
```
```
In crypto/ecb.c (ffffffff814da2b5)
Location: include/crypto/internal/skcipher.h:243
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_decrypt
  - crypto/ecb.c:crypto_ecb_encrypt
```
```
In crypto/cbc.c (ffffffff814da51e)
Location: include/crypto/internal/skcipher.h:243
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cbc.c:crypto_cbc_decrypt
```
```
In crypto/ctr.c (ffffffff814dc2d5)
Location: include/crypto/internal/skcipher.h:243
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_crypt
```
</details>
</li>
</ul>

## Differences
