# Function: <code>skcipher_request_ctx</code>

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
In crypto/skcipher.c (ffffffff813a1b8a)
Location: include/crypto/internal/skcipher.h:115
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_encrypt_ablkcipher
  - crypto/skcipher.c:skcipher_decrypt_ablkcipher
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
In crypto/skcipher.c (ffffffff813de09a)
Location: include/crypto/internal/skcipher.h:137
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_decrypt_ablkcipher
  - crypto/skcipher.c:skcipher_encrypt_ablkcipher
```
```
In crypto/cts.c (0)
Location: include/crypto/internal/skcipher.h:137
Inline: True
```
```
In crypto/ctr.c (0)
Location: include/crypto/internal/skcipher.h:137
Inline: True
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
In crypto/skcipher.c (ffffffff813f596a)
Location: include/crypto/internal/skcipher.h:174
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_decrypt_ablkcipher
  - crypto/skcipher.c:skcipher_encrypt_ablkcipher
```
```
In crypto/cts.c (0)
Location: include/crypto/internal/skcipher.h:174
Inline: True
```
```
In crypto/xts.c (0)
Location: include/crypto/internal/skcipher.h:174
Inline: True
```
```
In crypto/ctr.c (0)
Location: include/crypto/internal/skcipher.h:174
Inline: True
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
In crypto/skcipher.c (ffffffff81401c0a)
Location: include/crypto/internal/skcipher.h:174
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_decrypt_ablkcipher
  - crypto/skcipher.c:skcipher_encrypt_ablkcipher
```
```
In crypto/cts.c (0)
Location: include/crypto/internal/skcipher.h:174
Inline: True
```
```
In crypto/xts.c (0)
Location: include/crypto/internal/skcipher.h:174
Inline: True
```
```
In crypto/ctr.c (0)
Location: include/crypto/internal/skcipher.h:174
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
In crypto/skcipher.c (ffffffff8142a25a)
Location: include/crypto/internal/skcipher.h:174
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_decrypt_ablkcipher
  - crypto/skcipher.c:skcipher_encrypt_ablkcipher
```
```
In crypto/cts.c (0)
Location: include/crypto/internal/skcipher.h:174
Inline: True
```
```
In crypto/xts.c (0)
Location: include/crypto/internal/skcipher.h:174
Inline: True
```
```
In crypto/ctr.c (0)
Location: include/crypto/internal/skcipher.h:174
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
In crypto/skcipher.c (ffffffff8145cfd0)
Location: include/crypto/internal/skcipher.h:174
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_decrypt_ablkcipher
  - crypto/skcipher.c:skcipher_encrypt_ablkcipher
```
```
In crypto/cts.c (0)
Location: include/crypto/internal/skcipher.h:174
Inline: True
```
```
In crypto/xts.c (0)
Location: include/crypto/internal/skcipher.h:174
Inline: True
```
```
In crypto/ctr.c (ffffffff8146a824)
Location: include/crypto/internal/skcipher.h:174
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_crypt
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
In crypto/skcipher.c (ffffffff8147a890)
Location: include/crypto/internal/skcipher.h:172
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_decrypt_ablkcipher
  - crypto/skcipher.c:skcipher_encrypt_ablkcipher
```
```
In crypto/cts.c (0)
Location: include/crypto/internal/skcipher.h:172
Inline: True
```
```
In crypto/xts.c (0)
Location: include/crypto/internal/skcipher.h:172
Inline: True
```
```
In crypto/ctr.c (ffffffff8148808f)
Location: include/crypto/internal/skcipher.h:172
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_crypt
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
In crypto/skcipher.c (ffffffff814a87f0)
Location: include/crypto/internal/skcipher.h:167
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_decrypt_ablkcipher
  - crypto/skcipher.c:skcipher_encrypt_ablkcipher
```
```
In crypto/cts.c (0)
Location: include/crypto/internal/skcipher.h:167
Inline: True
```
```
In crypto/xts.c (0)
Location: include/crypto/internal/skcipher.h:167
Inline: True
```
```
In crypto/ctr.c (ffffffff814b5b18)
Location: include/crypto/internal/skcipher.h:167
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_crypt
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
In crypto/skcipher.c (ffffffff814c3450)
Location: include/crypto/internal/skcipher.h:172
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_decrypt_ablkcipher
  - crypto/skcipher.c:skcipher_encrypt_ablkcipher
```
```
In crypto/cts.c (0)
Location: include/crypto/internal/skcipher.h:172
Inline: True
```
```
In crypto/xts.c (0)
Location: include/crypto/internal/skcipher.h:172
Inline: True
```
```
In crypto/ctr.c (ffffffff814ced18)
Location: include/crypto/internal/skcipher.h:172
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_crypt
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
In crypto/cts.c (0)
Location: include/crypto/internal/skcipher.h:154
Inline: True
```
```
In crypto/xts.c (0)
Location: include/crypto/internal/skcipher.h:154
Inline: True
```
```
In crypto/ctr.c (ffffffff8152dfeb)
Location: include/crypto/internal/skcipher.h:154
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_crypt
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
In crypto/cts.c (0)
Location: include/crypto/internal/skcipher.h:154
Inline: True
```
```
In crypto/xts.c (0)
Location: include/crypto/internal/skcipher.h:154
Inline: True
```
```
In crypto/ctr.c (ffffffff8154b00b)
Location: include/crypto/internal/skcipher.h:154
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_crypt
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
In crypto/cts.c (0)
Location: include/crypto/internal/skcipher.h:154
Inline: True
```
```
In crypto/xts.c (0)
Location: include/crypto/internal/skcipher.h:154
Inline: True
```
```
In crypto/ctr.c (ffffffff8155362b)
Location: include/crypto/internal/skcipher.h:154
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_crypt
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
In crypto/cts.c (ffffffff815b39bb)
Location: include/crypto/internal/skcipher.h:154
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_decrypt
```
```
In crypto/xts.c (0)
Location: include/crypto/internal/skcipher.h:154
Inline: True
```
```
In crypto/ctr.c (ffffffff815b465b)
Location: include/crypto/internal/skcipher.h:154
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_crypt
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
In crypto/cts.c (ffffffff8165c737)
Location: include/crypto/internal/skcipher.h:154
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_decrypt
```
```
In crypto/xts.c (0)
Location: include/crypto/internal/skcipher.h:154
Inline: True
```
```
In crypto/ctr.c (ffffffff8165d50b)
Location: include/crypto/internal/skcipher.h:154
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_crypt
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
In crypto/cts.c (ffffffff81716157)
Location: include/crypto/internal/skcipher.h:174
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_decrypt
```
```
In crypto/xts.c (0)
Location: include/crypto/internal/skcipher.h:174
Inline: True
```
```
In crypto/ctr.c (ffffffff8171713b)
Location: include/crypto/internal/skcipher.h:174
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_crypt
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
In crypto/cts.c (ffffffff81751a57)
Location: include/crypto/internal/skcipher.h:174
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_decrypt
```
```
In crypto/xts.c (0)
Location: include/crypto/internal/skcipher.h:174
Inline: True
```
```
In crypto/ctr.c (ffffffff81752a4b)
Location: include/crypto/internal/skcipher.h:174
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_crypt
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
In crypto/lskcipher.c (ffffffff81783e23)
Location: include/crypto/internal/skcipher.h:240
Inline: True
Inline callers:
  - crypto/lskcipher.c:crypto_lskcipher_crypt_sg
```
```
In crypto/skcipher.c (ffffffff81784823)
Location: include/crypto/internal/skcipher.h:240
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_skcipher_import
  - crypto/skcipher.c:crypto_skcipher_export
```
```
In crypto/cts.c (ffffffff817938d7)
Location: include/crypto/internal/skcipher.h:240
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_decrypt
```
```
In crypto/xts.c (0)
Location: include/crypto/internal/skcipher.h:240
Inline: True
```
```
In crypto/ctr.c (ffffffff817949bb)
Location: include/crypto/internal/skcipher.h:240
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_crypt
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
In crypto/skcipher.c (ffff8000105bdc40)
Location: include/crypto/internal/skcipher.h:172
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_decrypt_ablkcipher
  - crypto/skcipher.c:skcipher_encrypt_ablkcipher
```
```
In crypto/cts.c (0)
Location: include/crypto/internal/skcipher.h:172
Inline: True
```
```
In crypto/xts.c (0)
Location: include/crypto/internal/skcipher.h:172
Inline: True
```
```
In crypto/ctr.c (ffff8000105cac74)
Location: include/crypto/internal/skcipher.h:172
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_crypt
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
In crypto/skcipher.c (c076baa8)
Location: include/crypto/internal/skcipher.h:172
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_decrypt_ablkcipher
  - crypto/skcipher.c:skcipher_encrypt_ablkcipher
```
```
In crypto/cts.c (c077790c)
Location: include/crypto/internal/skcipher.h:172
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_decrypt
```
```
In crypto/xts.c (0)
Location: include/crypto/internal/skcipher.h:172
Inline: True
```
```
In crypto/ctr.c (c0778838)
Location: include/crypto/internal/skcipher.h:172
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_crypt
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
In crypto/skcipher.c (c0000000007450e4)
Location: include/crypto/internal/skcipher.h:172
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_decrypt_ablkcipher
  - crypto/skcipher.c:skcipher_encrypt_ablkcipher
```
```
In crypto/cts.c (0)
Location: include/crypto/internal/skcipher.h:172
Inline: True
```
```
In crypto/xts.c (0)
Location: include/crypto/internal/skcipher.h:172
Inline: True
```
```
In crypto/ctr.c (c000000000755a7c)
Location: include/crypto/internal/skcipher.h:172
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_crypt
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
In crypto/skcipher.c (ffffffe00040317e)
Location: include/crypto/internal/skcipher.h:172
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_decrypt_ablkcipher
  - crypto/skcipher.c:skcipher_encrypt_ablkcipher
```
```
In crypto/cts.c (0)
Location: include/crypto/internal/skcipher.h:172
Inline: True
```
```
In crypto/xts.c (0)
Location: include/crypto/internal/skcipher.h:172
Inline: True
```
```
In crypto/ctr.c (ffffffe00040f11e)
Location: include/crypto/internal/skcipher.h:172
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_crypt
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
In crypto/skcipher.c (ffffffff814bba30)
Location: include/crypto/internal/skcipher.h:172
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_decrypt_ablkcipher
  - crypto/skcipher.c:skcipher_encrypt_ablkcipher
```
```
In crypto/cts.c (0)
Location: include/crypto/internal/skcipher.h:172
Inline: True
```
```
In crypto/xts.c (0)
Location: include/crypto/internal/skcipher.h:172
Inline: True
```
```
In crypto/ctr.c (ffffffff814c72f8)
Location: include/crypto/internal/skcipher.h:172
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_crypt
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
In crypto/skcipher.c (ffffffff814ac450)
Location: include/crypto/internal/skcipher.h:172
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_decrypt_ablkcipher
  - crypto/skcipher.c:skcipher_encrypt_ablkcipher
```
```
In crypto/cts.c (0)
Location: include/crypto/internal/skcipher.h:172
Inline: True
```
```
In crypto/xts.c (0)
Location: include/crypto/internal/skcipher.h:172
Inline: True
```
```
In crypto/ctr.c (ffffffff814b7d18)
Location: include/crypto/internal/skcipher.h:172
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_crypt
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
In crypto/skcipher.c (ffffffff814b7ac0)
Location: include/crypto/internal/skcipher.h:172
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_decrypt_ablkcipher
  - crypto/skcipher.c:skcipher_encrypt_ablkcipher
```
```
In crypto/cts.c (0)
Location: include/crypto/internal/skcipher.h:172
Inline: True
```
```
In crypto/xts.c (0)
Location: include/crypto/internal/skcipher.h:172
Inline: True
```
```
In crypto/ctr.c (ffffffff814c3388)
Location: include/crypto/internal/skcipher.h:172
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_crypt
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
In crypto/skcipher.c (ffffffff814d05a0)
Location: include/crypto/internal/skcipher.h:172
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_decrypt_ablkcipher
  - crypto/skcipher.c:skcipher_encrypt_ablkcipher
```
```
In crypto/cts.c (0)
Location: include/crypto/internal/skcipher.h:172
Inline: True
```
```
In crypto/xts.c (0)
Location: include/crypto/internal/skcipher.h:172
Inline: True
```
```
In crypto/ctr.c (ffffffff814dbe58)
Location: include/crypto/internal/skcipher.h:172
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_crypt
```
</details>
</li>
</ul>

## Differences
