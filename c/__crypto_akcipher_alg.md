# Function: <code>__crypto_akcipher_alg</code>

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
In crypto/akcipher.c (0)
Location: include/crypto/akcipher.h:139
Inline: True
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
In crypto/akcipher.c (0)
Location: include/crypto/akcipher.h:139
Inline: True
```
```
In crypto/rsa-pkcs1pad.c (0)
Location: include/crypto/akcipher.h:139
Inline: True
```
```
In crypto/asymmetric_keys/public_key.c (0)
Location: include/crypto/akcipher.h:139
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
In crypto/akcipher.c (0)
Location: include/crypto/akcipher.h:139
Inline: True
```
```
In crypto/rsa-pkcs1pad.c (0)
Location: include/crypto/akcipher.h:139
Inline: True
```
```
In crypto/asymmetric_keys/public_key.c (0)
Location: include/crypto/akcipher.h:139
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
In crypto/akcipher.c (0)
Location: include/crypto/akcipher.h:139
Inline: True
```
```
In crypto/rsa-pkcs1pad.c (0)
Location: include/crypto/akcipher.h:139
Inline: True
```
```
In crypto/asymmetric_keys/public_key.c (0)
Location: include/crypto/akcipher.h:139
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
In crypto/akcipher.c (0)
Location: include/crypto/akcipher.h:139
Inline: True
```
```
In crypto/rsa-pkcs1pad.c (0)
Location: include/crypto/akcipher.h:139
Inline: True
```
```
In crypto/asymmetric_keys/public_key.c (0)
Location: include/crypto/akcipher.h:139
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
In crypto/akcipher.c (ffffffff81460179)
Location: include/crypto/akcipher.h:139
Inline: True
Inline callers:
  - crypto/akcipher.c:crypto_akcipher_init_tfm
  - crypto/akcipher.c:crypto_akcipher_exit_tfm
```
```
In crypto/rsa-pkcs1pad.c (ffffffff81462017)
Location: include/crypto/akcipher.h:139
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_sign
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff8147537e)
Location: include/crypto/akcipher.h:139
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
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
In crypto/akcipher.c (ffffffff8147dbe9)
Location: include/crypto/akcipher.h:139
Inline: True
Inline callers:
  - crypto/akcipher.c:crypto_akcipher_init_tfm
  - crypto/akcipher.c:crypto_akcipher_exit_tfm
```
```
In crypto/rsa-pkcs1pad.c (ffffffff8147fde4)
Location: include/crypto/akcipher.h:139
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_sign
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff814931fa)
Location: include/crypto/akcipher.h:139
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_query
  - crypto/asymmetric_keys/public_key.c:software_key_query
  - crypto/asymmetric_keys/public_key.c:software_key_query
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
In crypto/akcipher.c (ffffffff814abea9)
Location: include/crypto/akcipher.h:139
Inline: True
Inline callers:
  - crypto/akcipher.c:crypto_akcipher_init_tfm
  - crypto/akcipher.c:crypto_akcipher_exit_tfm
```
```
In crypto/rsa-pkcs1pad.c (ffffffff814adff4)
Location: include/crypto/akcipher.h:139
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_sign
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff814c0d50)
Location: include/crypto/akcipher.h:139
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_query
  - crypto/asymmetric_keys/public_key.c:software_key_query
  - crypto/asymmetric_keys/public_key.c:software_key_query
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
In crypto/akcipher.c (ffffffff814c6b59)
Location: include/crypto/akcipher.h:139
Inline: True
Inline callers:
  - crypto/akcipher.c:crypto_akcipher_init_tfm
  - crypto/akcipher.c:crypto_akcipher_exit_tfm
```
```
In crypto/rsa-pkcs1pad.c (ffffffff814c8ca1)
Location: include/crypto/akcipher.h:139
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_sign
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff814d9b80)
Location: include/crypto/akcipher.h:139
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_query
  - crypto/asymmetric_keys/public_key.c:software_key_query
  - crypto/asymmetric_keys/public_key.c:software_key_query
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
In crypto/akcipher.c (ffffffff81525df9)
Location: include/crypto/akcipher.h:139
Inline: True
Inline callers:
  - crypto/akcipher.c:crypto_akcipher_init_tfm
  - crypto/akcipher.c:crypto_akcipher_exit_tfm
```
```
In crypto/rsa-pkcs1pad.c (ffffffff81527372)
Location: include/crypto/akcipher.h:139
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_sign
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff815390f0)
Location: include/crypto/akcipher.h:139
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_query
  - crypto/asymmetric_keys/public_key.c:software_key_query
  - crypto/asymmetric_keys/public_key.c:software_key_query
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
In crypto/akcipher.c (ffffffff81542d19)
Location: include/crypto/akcipher.h:139
Inline: True
Inline callers:
  - crypto/akcipher.c:crypto_akcipher_init_tfm
  - crypto/akcipher.c:crypto_akcipher_exit_tfm
```
```
In crypto/rsa-pkcs1pad.c (ffffffff815442f2)
Location: include/crypto/akcipher.h:139
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_sign
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff81555ed0)
Location: include/crypto/akcipher.h:139
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_query
  - crypto/asymmetric_keys/public_key.c:software_key_query
  - crypto/asymmetric_keys/public_key.c:software_key_query
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
In crypto/akcipher.c (ffffffff8154b3b9)
Location: include/crypto/akcipher.h:139
Inline: True
Inline callers:
  - crypto/akcipher.c:crypto_akcipher_init_tfm
  - crypto/akcipher.c:crypto_akcipher_exit_tfm
```
```
In crypto/rsa-pkcs1pad.c (ffffffff8154c962)
Location: include/crypto/akcipher.h:139
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_sign
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff8155e64a)
Location: include/crypto/akcipher.h:139
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_query
  - crypto/asymmetric_keys/public_key.c:software_key_query
  - crypto/asymmetric_keys/public_key.c:software_key_query
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
In crypto/akcipher.c (ffffffff815abb99)
Location: include/crypto/akcipher.h:139
Inline: True
Inline callers:
  - crypto/akcipher.c:crypto_akcipher_init_tfm
  - crypto/akcipher.c:crypto_akcipher_exit_tfm
```
```
In crypto/rsa-pkcs1pad.c (ffffffff815ad142)
Location: include/crypto/akcipher.h:139
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_sign
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff815bf99a)
Location: include/crypto/akcipher.h:139
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_query
  - crypto/asymmetric_keys/public_key.c:software_key_query
  - crypto/asymmetric_keys/public_key.c:software_key_query
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
In crypto/akcipher.c (0)
Location: include/crypto/akcipher.h:139
Inline: True
```
```
In crypto/rsa-pkcs1pad.c (0)
Location: include/crypto/akcipher.h:139
Inline: True
```
```
In crypto/asymmetric_keys/public_key.c (0)
Location: include/crypto/akcipher.h:139
Inline: True
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
In crypto/akcipher.c (0)
Location: include/crypto/akcipher.h:140
Inline: True
```
```
In crypto/rsa-pkcs1pad.c (0)
Location: include/crypto/akcipher.h:140
Inline: True
```
```
In crypto/asymmetric_keys/public_key.c (0)
Location: include/crypto/akcipher.h:140
Inline: True
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
In crypto/akcipher.c (0)
Location: include/crypto/akcipher.h:167
Inline: True
```
```
In crypto/sig.c (0)
Location: include/crypto/akcipher.h:167
Inline: True
```
```
In crypto/rsa-pkcs1pad.c (0)
Location: include/crypto/akcipher.h:167
Inline: True
```
```
In crypto/asymmetric_keys/public_key.c (0)
Location: include/crypto/akcipher.h:167
Inline: True
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
In crypto/akcipher.c (0)
Location: include/crypto/akcipher.h:167
Inline: True
```
```
In crypto/sig.c (0)
Location: include/crypto/akcipher.h:167
Inline: True
```
```
In crypto/rsa-pkcs1pad.c (0)
Location: include/crypto/akcipher.h:167
Inline: True
```
```
In crypto/asymmetric_keys/public_key.c (0)
Location: include/crypto/akcipher.h:167
Inline: True
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
In crypto/akcipher.c (ffff8000105c205c)
Location: include/crypto/akcipher.h:139
Inline: True
Inline callers:
  - crypto/akcipher.c:crypto_akcipher_init_tfm
  - crypto/akcipher.c:crypto_akcipher_exit_tfm
```
```
In crypto/rsa-pkcs1pad.c (ffff8000105c3fac)
Location: include/crypto/akcipher.h:139
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_sign
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
```
```
In crypto/asymmetric_keys/public_key.c (ffff8000105d5a30)
Location: include/crypto/akcipher.h:139
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_query
  - crypto/asymmetric_keys/public_key.c:software_key_query
  - crypto/asymmetric_keys/public_key.c:software_key_query
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
In crypto/akcipher.c (c076f5b0)
Location: include/crypto/akcipher.h:139
Inline: True
Inline callers:
  - crypto/akcipher.c:crypto_akcipher_init_tfm
  - crypto/akcipher.c:crypto_akcipher_exit_tfm
```
```
In crypto/rsa-pkcs1pad.c (c07717ec)
Location: include/crypto/akcipher.h:139
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_sign
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
```
```
In crypto/asymmetric_keys/public_key.c (c07834d0)
Location: include/crypto/akcipher.h:139
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_query
  - crypto/asymmetric_keys/public_key.c:software_key_query
  - crypto/asymmetric_keys/public_key.c:software_key_query
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
In crypto/akcipher.c (c00000000074a6e4)
Location: include/crypto/akcipher.h:139
Inline: True
Inline callers:
  - crypto/akcipher.c:crypto_akcipher_init_tfm
  - crypto/akcipher.c:crypto_akcipher_exit_tfm
```
```
In crypto/rsa-pkcs1pad.c (c00000000074d8f8)
Location: include/crypto/akcipher.h:139
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_sign
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
```
```
In crypto/asymmetric_keys/public_key.c (c0000000007641e0)
Location: include/crypto/akcipher.h:139
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_query
  - crypto/asymmetric_keys/public_key.c:software_key_query
  - crypto/asymmetric_keys/public_key.c:software_key_query
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
In crypto/akcipher.c (ffffffe000406b76)
Location: include/crypto/akcipher.h:139
Inline: True
Inline callers:
  - crypto/akcipher.c:crypto_akcipher_init_tfm
  - crypto/akcipher.c:crypto_akcipher_exit_tfm
```
```
In crypto/rsa-pkcs1pad.c (ffffffe0004083c8)
Location: include/crypto/akcipher.h:139
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_sign
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
```
```
In crypto/asymmetric_keys/public_key.c (ffffffe000419ba0)
Location: include/crypto/akcipher.h:139
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_query
  - crypto/asymmetric_keys/public_key.c:software_key_query
  - crypto/asymmetric_keys/public_key.c:software_key_query
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
In crypto/akcipher.c (ffffffff814bf139)
Location: include/crypto/akcipher.h:139
Inline: True
Inline callers:
  - crypto/akcipher.c:crypto_akcipher_init_tfm
  - crypto/akcipher.c:crypto_akcipher_exit_tfm
```
```
In crypto/rsa-pkcs1pad.c (ffffffff814c1281)
Location: include/crypto/akcipher.h:139
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_sign
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff814d2160)
Location: include/crypto/akcipher.h:139
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_query
  - crypto/asymmetric_keys/public_key.c:software_key_query
  - crypto/asymmetric_keys/public_key.c:software_key_query
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
In crypto/akcipher.c (ffffffff814afb59)
Location: include/crypto/akcipher.h:139
Inline: True
Inline callers:
  - crypto/akcipher.c:crypto_akcipher_init_tfm
  - crypto/akcipher.c:crypto_akcipher_exit_tfm
```
```
In crypto/rsa-pkcs1pad.c (ffffffff814b1ca1)
Location: include/crypto/akcipher.h:139
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_sign
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff814c2b80)
Location: include/crypto/akcipher.h:139
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_query
  - crypto/asymmetric_keys/public_key.c:software_key_query
  - crypto/asymmetric_keys/public_key.c:software_key_query
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
In crypto/akcipher.c (ffffffff814bb1c9)
Location: include/crypto/akcipher.h:139
Inline: True
Inline callers:
  - crypto/akcipher.c:crypto_akcipher_init_tfm
  - crypto/akcipher.c:crypto_akcipher_exit_tfm
```
```
In crypto/rsa-pkcs1pad.c (ffffffff814bd311)
Location: include/crypto/akcipher.h:139
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_sign
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff814ce1f0)
Location: include/crypto/akcipher.h:139
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_query
  - crypto/asymmetric_keys/public_key.c:software_key_query
  - crypto/asymmetric_keys/public_key.c:software_key_query
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
In crypto/akcipher.c (ffffffff814d3c99)
Location: include/crypto/akcipher.h:139
Inline: True
Inline callers:
  - crypto/akcipher.c:crypto_akcipher_init_tfm
  - crypto/akcipher.c:crypto_akcipher_exit_tfm
```
```
In crypto/rsa-pkcs1pad.c (ffffffff814d5de1)
Location: include/crypto/akcipher.h:139
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_sign
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff814e6cc0)
Location: include/crypto/akcipher.h:139
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_query
  - crypto/asymmetric_keys/public_key.c:software_key_query
  - crypto/asymmetric_keys/public_key.c:software_key_query
```
</details>
</li>
</ul>

## Differences
