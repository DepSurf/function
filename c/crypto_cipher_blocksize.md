# Function: <code>crypto_cipher_blocksize</code>

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
In crypto/ecb.c (ffffffff813a8ed9)
Location: include/linux/crypto.h:1498
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_crypt
```
```
In crypto/cbc.c (ffffffff813a939e)
Location: include/linux/crypto.h:1498
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_encrypt
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
In crypto/ecb.c (ffffffff813e6ea9)
Location: include/linux/crypto.h:1455
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_crypt
```
```
In crypto/cbc.c (ffffffff813e7470)
Location: include/linux/crypto.h:1455
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cbc.c:crypto_cbc_encrypt
  - crypto/cbc.c:crypto_cbc_encrypt
```
```
In crypto/xts.c (ffffffff813e8618)
Location: include/linux/crypto.h:1455
Inline: True
Inline callers:
  - crypto/xts.c:init_tfm
  - crypto/xts.c:init_tfm
```
```
In crypto/ctr.c (ffffffff813e89ac)
Location: include/linux/crypto.h:1455
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
```
```
In crypto/drbg.c (ffffffff813eecf9)
Location: include/linux/crypto.h:1455
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
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
In crypto/ecb.c (ffffffff813ffc59)
Location: include/linux/crypto.h:1458
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_crypt
```
```
In crypto/ctr.c (ffffffff81401fbc)
Location: include/linux/crypto.h:1458
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
```
```
In crypto/drbg.c (ffffffff8140853f)
Location: include/linux/crypto.h:1458
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
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
In crypto/ecb.c (ffffffff8140cf49)
Location: include/linux/crypto.h:1458
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_crypt
```
```
In crypto/ctr.c (ffffffff8140f86c)
Location: include/linux/crypto.h:1458
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
```
```
In crypto/drbg.c (ffffffff81415bff)
Location: include/linux/crypto.h:1458
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
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
In crypto/ecb.c (ffffffff814359b9)
Location: include/linux/crypto.h:1506
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_crypt
```
```
In crypto/ctr.c (ffffffff8143836c)
Location: include/linux/crypto.h:1506
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
```
```
In crypto/drbg.c (ffffffff814403cf)
Location: include/linux/crypto.h:1506
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
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
In crypto/ecb.c (ffffffff81468535)
Location: include/linux/crypto.h:1519
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_crypt
```
```
In crypto/ctr.c (ffffffff8146ad01)
Location: include/linux/crypto.h:1519
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
```
```
In crypto/drbg.c (ffffffff814732af)
Location: include/linux/crypto.h:1519
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
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
In crypto/ecb.c (ffffffff814861a5)
Location: include/linux/crypto.h:1704
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_crypt
```
```
In crypto/ctr.c (ffffffff81488561)
Location: include/linux/crypto.h:1704
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
```
```
In crypto/drbg.c (ffffffff8148f82a)
Location: include/linux/crypto.h:1704
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
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
In crypto/ecb.c (ffffffff814b436a)
Location: include/linux/crypto.h:1701
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_crypt
```
```
In crypto/ctr.c (ffffffff814b5fa7)
Location: include/linux/crypto.h:1701
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
```
```
In crypto/drbg.c (ffffffff814be1bb)
Location: include/linux/crypto.h:1701
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
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
In crypto/ecb.c (ffffffff814cd0da)
Location: include/linux/crypto.h:1701
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_crypt
```
```
In crypto/ctr.c (ffffffff814cf1a7)
Location: include/linux/crypto.h:1701
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
```
```
In crypto/drbg.c (ffffffff814d700b)
Location: include/linux/crypto.h:1701
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
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
In crypto/cipher.c (ffffffff8151f48b)
Location: include/linux/crypto.h:802
Inline: True
Inline callers:
  - crypto/cipher.c:crypto_cipher_decrypt_one
  - crypto/cipher.c:crypto_cipher_encrypt_one
```
```
In crypto/ecb.c (0)
Location: include/linux/crypto.h:802
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_crypt
```
```
In crypto/ctr.c (ffffffff8152e401)
Location: include/linux/crypto.h:802
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
```
```
In crypto/drbg.c (ffffffff81533819)
Location: include/linux/crypto.h:802
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
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
In crypto/cipher.c (ffffffff8153c2eb)
Location: include/linux/crypto.h:838
Inline: True
Inline callers:
  - crypto/cipher.c:crypto_cipher_decrypt_one
  - crypto/cipher.c:crypto_cipher_encrypt_one
```
```
In crypto/ecb.c (0)
Location: include/linux/crypto.h:838
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_crypt
```
```
In crypto/ctr.c (ffffffff8154b3a1)
Location: include/linux/crypto.h:838
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
```
```
In crypto/drbg.c (ffffffff81550769)
Location: include/linux/crypto.h:838
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
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
In crypto/cipher.c (ffffffff815449db)
Location: include/crypto/internal/cipher.h:109
Inline: True
Inline callers:
  - crypto/cipher.c:crypto_cipher_decrypt_one
  - crypto/cipher.c:crypto_cipher_encrypt_one
```
```
In crypto/ecb.c (0)
Location: include/crypto/internal/cipher.h:109
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_crypt
```
```
In crypto/ctr.c (ffffffff815539d5)
Location: include/crypto/internal/cipher.h:109
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
```
```
In crypto/drbg.c (ffffffff81558f49)
Location: include/crypto/internal/cipher.h:109
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
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
In crypto/cipher.c (ffffffff815a517b)
Location: include/crypto/internal/cipher.h:109
Inline: True
Inline callers:
  - crypto/cipher.c:crypto_cipher_decrypt_one
  - crypto/cipher.c:crypto_cipher_encrypt_one
```
```
In crypto/ecb.c (0)
Location: include/crypto/internal/cipher.h:109
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_crypt
```
```
In crypto/ctr.c (ffffffff815b4a05)
Location: include/crypto/internal/cipher.h:109
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
```
```
In crypto/drbg.c (ffffffff815ba209)
Location: include/crypto/internal/cipher.h:109
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
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
In crypto/cipher.c (ffffffff8164be4d)
Location: include/crypto/internal/cipher.h:109
Inline: True
Inline callers:
  - crypto/cipher.c:crypto_cipher_decrypt_one
  - crypto/cipher.c:crypto_cipher_encrypt_one
```
```
In crypto/ecb.c (0)
Location: include/crypto/internal/cipher.h:109
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_crypt
```
```
In crypto/ctr.c (ffffffff8165d8fa)
Location: include/crypto/internal/cipher.h:109
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
```
```
In crypto/drbg.c (ffffffff816632ac)
Location: include/crypto/internal/cipher.h:109
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
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
In crypto/cipher.c (ffffffff81704e52)
Location: include/crypto/internal/cipher.h:109
Inline: True
Inline callers:
  - crypto/cipher.c:cipher_crypt_one
```
```
In crypto/ecb.c (0)
Location: include/crypto/internal/cipher.h:109
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_crypt
```
```
In crypto/ctr.c (ffffffff8171748a)
Location: include/crypto/internal/cipher.h:109
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
```
```
In crypto/drbg.c (ffffffff8171d53c)
Location: include/crypto/internal/cipher.h:109
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
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
In crypto/cipher.c (ffffffff8173f122)
Location: include/crypto/internal/cipher.h:109
Inline: True
Inline callers:
  - crypto/cipher.c:cipher_crypt_one
```
```
In crypto/ecb.c (0)
Location: include/crypto/internal/cipher.h:109
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_crypt
```
```
In crypto/ctr.c (ffffffff81752daa)
Location: include/crypto/internal/cipher.h:109
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
```
```
In crypto/drbg.c (ffffffff81758e1c)
Location: include/crypto/internal/cipher.h:109
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
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
In crypto/cipher.c (ffffffff8177ffa2)
Location: include/crypto/internal/cipher.h:109
Inline: True
Inline callers:
  - crypto/cipher.c:cipher_crypt_one
```
```
In crypto/ecb.c (ffffffff8179290c)
Location: include/crypto/internal/cipher.h:109
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_decrypt2
  - crypto/ecb.c:crypto_ecb_encrypt2
```
```
In crypto/ctr.c (ffffffff81794d4a)
Location: include/crypto/internal/cipher.h:109
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
```
```
In crypto/drbg.c (ffffffff8179ad1c)
Location: include/crypto/internal/cipher.h:109
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
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
In crypto/ecb.c (ffff8000105c8f24)
Location: include/linux/crypto.h:1701
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_crypt
```
```
In crypto/ctr.c (ffff8000105cb160)
Location: include/linux/crypto.h:1701
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
```
```
In crypto/drbg.c (ffff8000105d14d0)
Location: include/linux/crypto.h:1701
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
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
In crypto/ecb.c (c0776bdc)
Location: include/linux/crypto.h:1701
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_crypt
```
```
In crypto/ctr.c (c0778cb4)
Location: include/linux/crypto.h:1701
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
```
```
In crypto/drbg.c (c0780440)
Location: include/linux/crypto.h:1701
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
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
In crypto/ecb.c (c00000000075338c)
Location: include/linux/crypto.h:1701
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_crypt
```
```
In crypto/ctr.c (c0000000007560ec)
Location: include/linux/crypto.h:1701
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
```
```
In crypto/drbg.c (c00000000075fc48)
Location: include/linux/crypto.h:1701
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
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
In crypto/ecb.c (ffffffe00040d8d4)
Location: include/linux/crypto.h:1701
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_crypt
```
```
In crypto/ctr.c (ffffffe00040f320)
Location: include/linux/crypto.h:1701
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
```
```
In crypto/drbg.c (ffffffe000416254)
Location: include/linux/crypto.h:1701
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
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
In crypto/ecb.c (ffffffff814c56ba)
Location: include/linux/crypto.h:1701
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_crypt
```
```
In crypto/ctr.c (ffffffff814c7787)
Location: include/linux/crypto.h:1701
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
```
```
In crypto/drbg.c (ffffffff814cf5eb)
Location: include/linux/crypto.h:1701
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
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
In crypto/ecb.c (ffffffff814b60da)
Location: include/linux/crypto.h:1701
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_crypt
```
```
In crypto/ctr.c (ffffffff814b81a7)
Location: include/linux/crypto.h:1701
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
```
```
In crypto/drbg.c (ffffffff814c000b)
Location: include/linux/crypto.h:1701
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
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
In crypto/ecb.c (ffffffff814c174a)
Location: include/linux/crypto.h:1701
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_crypt
```
```
In crypto/ctr.c (ffffffff814c3817)
Location: include/linux/crypto.h:1701
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
```
```
In crypto/drbg.c (ffffffff814cb67b)
Location: include/linux/crypto.h:1701
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
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
In crypto/ecb.c (ffffffff814da21a)
Location: include/linux/crypto.h:1701
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_crypt
```
```
In crypto/ctr.c (ffffffff814dc2e7)
Location: include/linux/crypto.h:1701
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
```
```
In crypto/drbg.c (ffffffff814e414b)
Location: include/linux/crypto.h:1701
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
```
</details>
</li>
</ul>

## Differences
