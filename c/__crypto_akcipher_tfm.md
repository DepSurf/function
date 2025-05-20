# Function: <code>__crypto_akcipher_tfm</code>

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
Location: include/crypto/akcipher.h:144
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
Location: include/crypto/akcipher.h:144
Inline: True
```
```
In crypto/rsa.c (0)
Location: include/crypto/akcipher.h:144
Inline: True
```
```
In crypto/rsa-pkcs1pad.c (0)
Location: include/crypto/akcipher.h:144
Inline: True
```
```
In crypto/asymmetric_keys/public_key.c (0)
Location: include/crypto/akcipher.h:144
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
Location: include/crypto/akcipher.h:144
Inline: True
```
```
In crypto/rsa.c (0)
Location: include/crypto/akcipher.h:144
Inline: True
```
```
In crypto/rsa-pkcs1pad.c (0)
Location: include/crypto/akcipher.h:144
Inline: True
```
```
In crypto/asymmetric_keys/public_key.c (0)
Location: include/crypto/akcipher.h:144
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
Location: include/crypto/akcipher.h:144
Inline: True
```
```
In crypto/rsa.c (0)
Location: include/crypto/akcipher.h:144
Inline: True
```
```
In crypto/rsa-pkcs1pad.c (0)
Location: include/crypto/akcipher.h:144
Inline: True
```
```
In crypto/asymmetric_keys/public_key.c (0)
Location: include/crypto/akcipher.h:144
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
Location: include/crypto/akcipher.h:144
Inline: True
```
```
In crypto/rsa.c (0)
Location: include/crypto/akcipher.h:144
Inline: True
```
```
In crypto/rsa-pkcs1pad.c (0)
Location: include/crypto/akcipher.h:144
Inline: True
```
```
In crypto/asymmetric_keys/public_key.c (0)
Location: include/crypto/akcipher.h:144
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
In crypto/akcipher.c (ffffffff81460175)
Location: include/crypto/akcipher.h:144
Inline: True
Inline callers:
  - crypto/akcipher.c:crypto_akcipher_init_tfm
  - crypto/akcipher.c:crypto_akcipher_exit_tfm
```
```
In crypto/rsa.c (ffffffff81460eae)
Location: include/crypto/akcipher.h:144
Inline: True
Inline callers:
  - crypto/rsa.c:rsa_verify
  - crypto/rsa.c:rsa_sign
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_enc
```
```
In crypto/rsa-pkcs1pad.c (ffffffff81461f16)
Location: include/crypto/akcipher.h:144
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify_complete_cb
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_sign
  - crypto/rsa-pkcs1pad.c:pkcs1pad_sign
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete_cb
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete_cb
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff81475482)
Location: include/crypto/akcipher.h:144
Inline: True
Inline callers:
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
In crypto/akcipher.c (ffffffff8147dbe5)
Location: include/crypto/akcipher.h:144
Inline: True
Inline callers:
  - crypto/akcipher.c:crypto_akcipher_init_tfm
  - crypto/akcipher.c:crypto_akcipher_exit_tfm
```
```
In crypto/rsa.c (ffffffff8147eafe)
Location: include/crypto/akcipher.h:144
Inline: True
Inline callers:
  - crypto/rsa.c:rsa_verify
  - crypto/rsa.c:rsa_sign
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_enc
```
```
In crypto/rsa-pkcs1pad.c (ffffffff8147fce6)
Location: include/crypto/akcipher.h:144
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify_complete_cb
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_sign
  - crypto/rsa-pkcs1pad.c:pkcs1pad_sign
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete_cb
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete_cb
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff8149330a)
Location: include/crypto/akcipher.h:144
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
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
In crypto/akcipher.c (ffffffff814abea5)
Location: include/crypto/akcipher.h:144
Inline: True
Inline callers:
  - crypto/akcipher.c:crypto_akcipher_init_tfm
  - crypto/akcipher.c:crypto_akcipher_exit_tfm
```
```
In crypto/rsa.c (ffffffff814acb9e)
Location: include/crypto/akcipher.h:144
Inline: True
Inline callers:
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_enc
```
```
In crypto/rsa-pkcs1pad.c (ffffffff814adeb5)
Location: include/crypto/akcipher.h:144
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify_complete_cb
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_sign
  - crypto/rsa-pkcs1pad.c:pkcs1pad_sign
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete_cb
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete_cb
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff814c0f4f)
Location: include/crypto/akcipher.h:144
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
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
In crypto/akcipher.c (ffffffff814c6b55)
Location: include/crypto/akcipher.h:144
Inline: True
Inline callers:
  - crypto/akcipher.c:crypto_akcipher_init_tfm
  - crypto/akcipher.c:crypto_akcipher_exit_tfm
```
```
In crypto/rsa.c (ffffffff814c784e)
Location: include/crypto/akcipher.h:144
Inline: True
Inline callers:
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_enc
```
```
In crypto/rsa-pkcs1pad.c (ffffffff814c8b65)
Location: include/crypto/akcipher.h:144
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify_complete_cb
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_sign
  - crypto/rsa-pkcs1pad.c:pkcs1pad_sign
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete_cb
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete_cb
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff814d9d7f)
Location: include/crypto/akcipher.h:144
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
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
In crypto/akcipher.c (ffffffff81525df5)
Location: include/crypto/akcipher.h:144
Inline: True
Inline callers:
  - crypto/akcipher.c:crypto_akcipher_init_tfm
  - crypto/akcipher.c:crypto_akcipher_exit_tfm
```
```
In crypto/rsa.c (ffffffff815267ee)
Location: include/crypto/akcipher.h:144
Inline: True
Inline callers:
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_enc
```
```
In crypto/rsa-pkcs1pad.c (ffffffff81527235)
Location: include/crypto/akcipher.h:144
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify_complete_cb
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_sign
  - crypto/rsa-pkcs1pad.c:pkcs1pad_sign
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete_cb
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete_cb
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff81539316)
Location: include/crypto/akcipher.h:144
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
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
In crypto/akcipher.c (ffffffff81542d15)
Location: include/crypto/akcipher.h:144
Inline: True
Inline callers:
  - crypto/akcipher.c:crypto_akcipher_init_tfm
  - crypto/akcipher.c:crypto_akcipher_exit_tfm
```
```
In crypto/rsa.c (ffffffff8154378e)
Location: include/crypto/akcipher.h:144
Inline: True
Inline callers:
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_enc
```
```
In crypto/rsa-pkcs1pad.c (ffffffff815441b5)
Location: include/crypto/akcipher.h:144
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify_complete_cb
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_sign
  - crypto/rsa-pkcs1pad.c:pkcs1pad_sign
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete_cb
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete_cb
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff81556108)
Location: include/crypto/akcipher.h:144
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
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
In crypto/akcipher.c (ffffffff8154b3b5)
Location: include/crypto/akcipher.h:144
Inline: True
Inline callers:
  - crypto/akcipher.c:crypto_akcipher_init_tfm
  - crypto/akcipher.c:crypto_akcipher_exit_tfm
```
```
In crypto/rsa.c (ffffffff8154bdfe)
Location: include/crypto/akcipher.h:144
Inline: True
Inline callers:
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_enc
```
```
In crypto/rsa-pkcs1pad.c (ffffffff8154c83b)
Location: include/crypto/akcipher.h:144
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify_complete_cb
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_sign
  - crypto/rsa-pkcs1pad.c:pkcs1pad_sign
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete_cb
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete_cb
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff8155e86a)
Location: include/crypto/akcipher.h:144
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
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
In crypto/akcipher.c (ffffffff815abb95)
Location: include/crypto/akcipher.h:144
Inline: True
Inline callers:
  - crypto/akcipher.c:crypto_akcipher_init_tfm
  - crypto/akcipher.c:crypto_akcipher_exit_tfm
```
```
In crypto/rsa.c (ffffffff815ac5de)
Location: include/crypto/akcipher.h:144
Inline: True
Inline callers:
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_enc
```
```
In crypto/rsa-pkcs1pad.c (ffffffff815ad01b)
Location: include/crypto/akcipher.h:144
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify_complete_cb
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_sign
  - crypto/rsa-pkcs1pad.c:pkcs1pad_sign
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete_cb
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete_cb
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff815bfbc3)
Location: include/crypto/akcipher.h:144
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
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
Location: include/crypto/akcipher.h:144
Inline: True
```
```
In crypto/rsa.c (0)
Location: include/crypto/akcipher.h:144
Inline: True
```
```
In crypto/rsa-pkcs1pad.c (0)
Location: include/crypto/akcipher.h:144
Inline: True
```
```
In crypto/asymmetric_keys/public_key.c (0)
Location: include/crypto/akcipher.h:144
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
In crypto/akcipher.c (ffffffff8170d245)
Location: include/crypto/akcipher.h:145
Inline: True
Inline callers:
  - crypto/akcipher.c:crypto_akcipher_init_tfm
  - crypto/akcipher.c:crypto_akcipher_exit_tfm
```
```
In crypto/rsa.c (0)
Location: include/crypto/akcipher.h:145
Inline: True
```
```
In crypto/rsa-pkcs1pad.c (0)
Location: include/crypto/akcipher.h:145
Inline: True
```
```
In crypto/asymmetric_keys/public_key.c (0)
Location: include/crypto/akcipher.h:145
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
In crypto/akcipher.c (ffffffff81746f75)
Location: include/crypto/akcipher.h:172
Inline: True
Inline callers:
  - crypto/akcipher.c:crypto_akcipher_init_tfm
  - crypto/akcipher.c:crypto_akcipher_exit_tfm
```
```
In crypto/sig.c (0)
Location: include/crypto/akcipher.h:172
Inline: True
```
```
In crypto/rsa.c (0)
Location: include/crypto/akcipher.h:172
Inline: True
```
```
In crypto/rsa-pkcs1pad.c (0)
Location: include/crypto/akcipher.h:172
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
In crypto/akcipher.c (ffffffff81788de5)
Location: include/crypto/akcipher.h:172
Inline: True
Inline callers:
  - crypto/akcipher.c:crypto_akcipher_init_tfm
  - crypto/akcipher.c:crypto_akcipher_exit_tfm
```
```
In crypto/sig.c (0)
Location: include/crypto/akcipher.h:172
Inline: True
```
```
In crypto/rsa.c (0)
Location: include/crypto/akcipher.h:172
Inline: True
```
```
In crypto/rsa-pkcs1pad.c (0)
Location: include/crypto/akcipher.h:172
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
In crypto/akcipher.c (ffff8000105c2058)
Location: include/crypto/akcipher.h:144
Inline: True
Inline callers:
  - crypto/akcipher.c:crypto_akcipher_init_tfm
  - crypto/akcipher.c:crypto_akcipher_exit_tfm
```
```
In crypto/rsa.c (ffff8000105c3080)
Location: include/crypto/akcipher.h:144
Inline: True
Inline callers:
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_enc
```
```
In crypto/rsa-pkcs1pad.c (ffff8000105c3f18)
Location: include/crypto/akcipher.h:144
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify_complete_cb
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_sign
  - crypto/rsa-pkcs1pad.c:pkcs1pad_sign
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete_cb
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete_cb
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete
```
```
In crypto/asymmetric_keys/public_key.c (ffff8000105d5b80)
Location: include/crypto/akcipher.h:144
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
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
In crypto/akcipher.c (c076f5ac)
Location: include/crypto/akcipher.h:144
Inline: True
Inline callers:
  - crypto/akcipher.c:crypto_akcipher_init_tfm
  - crypto/akcipher.c:crypto_akcipher_exit_tfm
```
```
In crypto/rsa.c (c0770308)
Location: include/crypto/akcipher.h:144
Inline: True
Inline callers:
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_enc
```
```
In crypto/rsa-pkcs1pad.c (c0771700)
Location: include/crypto/akcipher.h:144
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_sign
  - crypto/rsa-pkcs1pad.c:pkcs1pad_sign
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete
```
```
In crypto/asymmetric_keys/public_key.c (c0783690)
Location: include/crypto/akcipher.h:144
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
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
In crypto/akcipher.c (c00000000074a6e0)
Location: include/crypto/akcipher.h:144
Inline: True
Inline callers:
  - crypto/akcipher.c:crypto_akcipher_init_tfm
  - crypto/akcipher.c:crypto_akcipher_exit_tfm
```
```
In crypto/rsa.c (c00000000074baf4)
Location: include/crypto/akcipher.h:144
Inline: True
Inline callers:
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_enc
```
```
In crypto/rsa-pkcs1pad.c (c00000000074d818)
Location: include/crypto/akcipher.h:144
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify_complete_cb
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_sign
  - crypto/rsa-pkcs1pad.c:pkcs1pad_sign
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete_cb
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete_cb
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete
```
```
In crypto/asymmetric_keys/public_key.c (c000000000764380)
Location: include/crypto/akcipher.h:144
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
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
In crypto/akcipher.c (ffffffe000406b74)
Location: include/crypto/akcipher.h:144
Inline: True
Inline callers:
  - crypto/akcipher.c:crypto_akcipher_init_tfm
  - crypto/akcipher.c:crypto_akcipher_exit_tfm
```
```
In crypto/rsa.c (ffffffe0004079f0)
Location: include/crypto/akcipher.h:144
Inline: True
Inline callers:
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_enc
```
```
In crypto/rsa-pkcs1pad.c (ffffffe00040834e)
Location: include/crypto/akcipher.h:144
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify_complete_cb
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_sign
  - crypto/rsa-pkcs1pad.c:pkcs1pad_sign
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete_cb
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete_cb
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete
```
```
In crypto/asymmetric_keys/public_key.c (ffffffe000419d3c)
Location: include/crypto/akcipher.h:144
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
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
In crypto/akcipher.c (ffffffff814bf135)
Location: include/crypto/akcipher.h:144
Inline: True
Inline callers:
  - crypto/akcipher.c:crypto_akcipher_init_tfm
  - crypto/akcipher.c:crypto_akcipher_exit_tfm
```
```
In crypto/rsa.c (ffffffff814bfe2e)
Location: include/crypto/akcipher.h:144
Inline: True
Inline callers:
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_enc
```
```
In crypto/rsa-pkcs1pad.c (ffffffff814c1145)
Location: include/crypto/akcipher.h:144
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify_complete_cb
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_sign
  - crypto/rsa-pkcs1pad.c:pkcs1pad_sign
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete_cb
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete_cb
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff814d235f)
Location: include/crypto/akcipher.h:144
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
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
In crypto/akcipher.c (ffffffff814afb55)
Location: include/crypto/akcipher.h:144
Inline: True
Inline callers:
  - crypto/akcipher.c:crypto_akcipher_init_tfm
  - crypto/akcipher.c:crypto_akcipher_exit_tfm
```
```
In crypto/rsa.c (ffffffff814b084e)
Location: include/crypto/akcipher.h:144
Inline: True
Inline callers:
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_enc
```
```
In crypto/rsa-pkcs1pad.c (ffffffff814b1b65)
Location: include/crypto/akcipher.h:144
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify_complete_cb
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_sign
  - crypto/rsa-pkcs1pad.c:pkcs1pad_sign
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete_cb
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete_cb
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff814c2d7f)
Location: include/crypto/akcipher.h:144
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
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
In crypto/akcipher.c (ffffffff814bb1c5)
Location: include/crypto/akcipher.h:144
Inline: True
Inline callers:
  - crypto/akcipher.c:crypto_akcipher_init_tfm
  - crypto/akcipher.c:crypto_akcipher_exit_tfm
```
```
In crypto/rsa.c (ffffffff814bbebe)
Location: include/crypto/akcipher.h:144
Inline: True
Inline callers:
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_enc
```
```
In crypto/rsa-pkcs1pad.c (ffffffff814bd1d5)
Location: include/crypto/akcipher.h:144
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify_complete_cb
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_sign
  - crypto/rsa-pkcs1pad.c:pkcs1pad_sign
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete_cb
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete_cb
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff814ce3ef)
Location: include/crypto/akcipher.h:144
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
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
In crypto/akcipher.c (ffffffff814d3c95)
Location: include/crypto/akcipher.h:144
Inline: True
Inline callers:
  - crypto/akcipher.c:crypto_akcipher_init_tfm
  - crypto/akcipher.c:crypto_akcipher_exit_tfm
```
```
In crypto/rsa.c (ffffffff814d498e)
Location: include/crypto/akcipher.h:144
Inline: True
Inline callers:
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_enc
```
```
In crypto/rsa-pkcs1pad.c (ffffffff814d5ca5)
Location: include/crypto/akcipher.h:144
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify_complete_cb
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_sign
  - crypto/rsa-pkcs1pad.c:pkcs1pad_sign
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete_cb
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete_cb
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff814e6ebf)
Location: include/crypto/akcipher.h:144
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
```
</details>
</li>
</ul>

## Differences
