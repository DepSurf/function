# Function: <code>crypto_akcipher_reqtfm</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/rsa.c (ffffffff813e08c9)
Location: include/crypto/akcipher.h:167
Inline: True
Inline callers:
  - crypto/rsa.c:rsa_verify
  - crypto/rsa.c:rsa_sign
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_enc
```
```
In crypto/rsa-pkcs1pad.c (ffffffff813e10ee)
Location: include/crypto/akcipher.h:167
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_sign
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete
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
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/rsa.c (ffffffff813f8e49)
Location: include/crypto/akcipher.h:167
Inline: True
Inline callers:
  - crypto/rsa.c:rsa_verify
  - crypto/rsa.c:rsa_sign
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_enc
```
```
In crypto/rsa-pkcs1pad.c (ffffffff813fa132)
Location: include/crypto/akcipher.h:167
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_sign
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete
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
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/rsa.c (ffffffff81405909)
Location: include/crypto/akcipher.h:167
Inline: True
Inline callers:
  - crypto/rsa.c:rsa_verify
  - crypto/rsa.c:rsa_sign
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_enc
```
```
In crypto/rsa-pkcs1pad.c (ffffffff81406942)
Location: include/crypto/akcipher.h:167
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_sign
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete
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
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/rsa.c (ffffffff8142e1f9)
Location: include/crypto/akcipher.h:167
Inline: True
Inline callers:
  - crypto/rsa.c:rsa_verify
  - crypto/rsa.c:rsa_sign
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_enc
```
```
In crypto/rsa-pkcs1pad.c (ffffffff8142f282)
Location: include/crypto/akcipher.h:167
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_sign
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete
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
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/rsa.c (ffffffff81460eae)
Location: include/crypto/akcipher.h:167
Inline: True
Inline callers:
  - crypto/rsa.c:rsa_verify
  - crypto/rsa.c:rsa_sign
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_enc
```
```
In crypto/rsa-pkcs1pad.c (ffffffff81461f05)
Location: include/crypto/akcipher.h:167
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
Location: include/crypto/akcipher.h:167
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
In crypto/rsa.c (ffffffff8147eafe)
Location: include/crypto/akcipher.h:167
Inline: True
Inline callers:
  - crypto/rsa.c:rsa_verify
  - crypto/rsa.c:rsa_sign
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_enc
```
```
In crypto/rsa-pkcs1pad.c (ffffffff8147fcd5)
Location: include/crypto/akcipher.h:167
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
Location: include/crypto/akcipher.h:167
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
In crypto/rsa.c (ffffffff814acb9e)
Location: include/crypto/akcipher.h:167
Inline: True
Inline callers:
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_enc
```
```
In crypto/rsa-pkcs1pad.c (ffffffff814adeb5)
Location: include/crypto/akcipher.h:167
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
Location: include/crypto/akcipher.h:167
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
In crypto/rsa.c (ffffffff814c784e)
Location: include/crypto/akcipher.h:167
Inline: True
Inline callers:
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_enc
```
```
In crypto/rsa-pkcs1pad.c (ffffffff814c8b65)
Location: include/crypto/akcipher.h:167
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
Location: include/crypto/akcipher.h:167
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
In crypto/rsa.c (ffffffff815267ee)
Location: include/crypto/akcipher.h:167
Inline: True
Inline callers:
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_enc
```
```
In crypto/rsa-pkcs1pad.c (ffffffff81527235)
Location: include/crypto/akcipher.h:167
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
Location: include/crypto/akcipher.h:167
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
In crypto/rsa.c (ffffffff8154378e)
Location: include/crypto/akcipher.h:167
Inline: True
Inline callers:
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_enc
```
```
In crypto/rsa-pkcs1pad.c (ffffffff815441b5)
Location: include/crypto/akcipher.h:167
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
Location: include/crypto/akcipher.h:167
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
In crypto/rsa.c (ffffffff8154bdfe)
Location: include/crypto/akcipher.h:167
Inline: True
Inline callers:
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_enc
```
```
In crypto/rsa-pkcs1pad.c (ffffffff8154c825)
Location: include/crypto/akcipher.h:167
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
Location: include/crypto/akcipher.h:167
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
In crypto/rsa.c (ffffffff815ac5de)
Location: include/crypto/akcipher.h:167
Inline: True
Inline callers:
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_enc
```
```
In crypto/rsa-pkcs1pad.c (ffffffff815ad005)
Location: include/crypto/akcipher.h:167
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
Location: include/crypto/akcipher.h:167
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
In crypto/rsa.c (ffffffff8165487e)
Location: include/crypto/akcipher.h:167
Inline: True
Inline callers:
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_enc
```
```
In crypto/rsa-pkcs1pad.c (ffffffff81655425)
Location: include/crypto/akcipher.h:167
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify_complete_cb
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_sign
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete_cb
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete_cb
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff8166a114)
Location: include/crypto/akcipher.h:167
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
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/rsa.c (ffffffff8170ed3e)
Location: include/crypto/akcipher.h:168
Inline: True
Inline callers:
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_enc
```
```
In crypto/rsa-pkcs1pad.c (ffffffff8170f655)
Location: include/crypto/akcipher.h:168
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_sign
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff817246df)
Location: include/crypto/akcipher.h:168
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
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/akcipher.c (ffffffff81747846)
Location: include/crypto/akcipher.h:195
Inline: True
Inline callers:
  - crypto/akcipher.c:crypto_akcipher_sync_decrypt
  - crypto/akcipher.c:crypto_akcipher_sync_encrypt
```
```
In crypto/sig.c (ffffffff81747bd9)
Location: include/crypto/akcipher.h:195
Inline: True
Inline callers:
  - crypto/sig.c:crypto_sig_verify
  - crypto/sig.c:crypto_sig_sign
```
```
In crypto/rsa.c (ffffffff8174969e)
Location: include/crypto/akcipher.h:195
Inline: True
Inline callers:
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_enc
```
```
In crypto/rsa-pkcs1pad.c (ffffffff8174a6c5)
Location: include/crypto/akcipher.h:195
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_sign
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete
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
In crypto/akcipher.c (ffffffff817896b6)
Location: include/crypto/akcipher.h:195
Inline: True
Inline callers:
  - crypto/akcipher.c:crypto_akcipher_sync_decrypt
  - crypto/akcipher.c:crypto_akcipher_sync_encrypt
```
```
In crypto/sig.c (ffffffff81789a49)
Location: include/crypto/akcipher.h:195
Inline: True
Inline callers:
  - crypto/sig.c:crypto_sig_verify
  - crypto/sig.c:crypto_sig_sign
```
```
In crypto/rsa.c (ffffffff8178b53e)
Location: include/crypto/akcipher.h:195
Inline: True
Inline callers:
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_enc
```
```
In crypto/rsa-pkcs1pad.c (ffffffff8178c285)
Location: include/crypto/akcipher.h:195
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_sign
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete
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
In crypto/rsa.c (ffff8000105c3078)
Location: include/crypto/akcipher.h:167
Inline: True
Inline callers:
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_enc
```
```
In crypto/rsa-pkcs1pad.c (ffff8000105c3f18)
Location: include/crypto/akcipher.h:167
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
Location: include/crypto/akcipher.h:167
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
In crypto/rsa.c (c0770308)
Location: include/crypto/akcipher.h:167
Inline: True
Inline callers:
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_enc
```
```
In crypto/rsa-pkcs1pad.c (c0771700)
Location: include/crypto/akcipher.h:167
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
Location: include/crypto/akcipher.h:167
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
In crypto/rsa.c (c00000000074baf0)
Location: include/crypto/akcipher.h:167
Inline: True
Inline callers:
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_enc
```
```
In crypto/rsa-pkcs1pad.c (c00000000074d818)
Location: include/crypto/akcipher.h:167
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
Location: include/crypto/akcipher.h:167
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
In crypto/rsa.c (ffffffe0004079ea)
Location: include/crypto/akcipher.h:167
Inline: True
Inline callers:
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_enc
```
```
In crypto/rsa-pkcs1pad.c (ffffffe00040834e)
Location: include/crypto/akcipher.h:167
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
Location: include/crypto/akcipher.h:167
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
In crypto/rsa.c (ffffffff814bfe2e)
Location: include/crypto/akcipher.h:167
Inline: True
Inline callers:
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_enc
```
```
In crypto/rsa-pkcs1pad.c (ffffffff814c1145)
Location: include/crypto/akcipher.h:167
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
Location: include/crypto/akcipher.h:167
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
In crypto/rsa.c (ffffffff814b084e)
Location: include/crypto/akcipher.h:167
Inline: True
Inline callers:
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_enc
```
```
In crypto/rsa-pkcs1pad.c (ffffffff814b1b65)
Location: include/crypto/akcipher.h:167
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
Location: include/crypto/akcipher.h:167
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
In crypto/rsa.c (ffffffff814bbebe)
Location: include/crypto/akcipher.h:167
Inline: True
Inline callers:
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_enc
```
```
In crypto/rsa-pkcs1pad.c (ffffffff814bd1d5)
Location: include/crypto/akcipher.h:167
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
Location: include/crypto/akcipher.h:167
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
In crypto/rsa.c (ffffffff814d498e)
Location: include/crypto/akcipher.h:167
Inline: True
Inline callers:
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_enc
```
```
In crypto/rsa-pkcs1pad.c (ffffffff814d5ca5)
Location: include/crypto/akcipher.h:167
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
Location: include/crypto/akcipher.h:167
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
