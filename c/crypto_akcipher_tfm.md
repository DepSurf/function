# Function: <code>crypto_akcipher_tfm</code>

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
Location: include/crypto/akcipher.h:133
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
Location: include/crypto/akcipher.h:133
Inline: True
```
```
In crypto/rsa-pkcs1pad.c (0)
Location: include/crypto/akcipher.h:133
Inline: True
```
```
In crypto/asymmetric_keys/public_key.c (0)
Location: include/crypto/akcipher.h:133
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
Location: include/crypto/akcipher.h:133
Inline: True
```
```
In crypto/rsa-pkcs1pad.c (0)
Location: include/crypto/akcipher.h:133
Inline: True
```
```
In crypto/asymmetric_keys/public_key.c (0)
Location: include/crypto/akcipher.h:133
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
Location: include/crypto/akcipher.h:133
Inline: True
```
```
In crypto/rsa-pkcs1pad.c (0)
Location: include/crypto/akcipher.h:133
Inline: True
```
```
In crypto/asymmetric_keys/public_key.c (0)
Location: include/crypto/akcipher.h:133
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
Location: include/crypto/akcipher.h:133
Inline: True
```
```
In crypto/rsa-pkcs1pad.c (0)
Location: include/crypto/akcipher.h:133
Inline: True
```
```
In crypto/asymmetric_keys/public_key.c (0)
Location: include/crypto/akcipher.h:133
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
In crypto/akcipher.c (0)
Location: include/crypto/akcipher.h:133
Inline: True
```
```
In crypto/rsa-pkcs1pad.c (ffffffff814615aa)
Location: include/crypto/akcipher.h:133
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_exit_tfm
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify_complete_cb
  - crypto/rsa-pkcs1pad.c:pkcs1pad_sign
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete_cb
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete_cb
```
```
In crypto/asymmetric_keys/public_key.c (0)
Location: include/crypto/akcipher.h:133
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
In crypto/akcipher.c (0)
Location: include/crypto/akcipher.h:133
Inline: True
```
```
In crypto/rsa-pkcs1pad.c (ffffffff8147f20a)
Location: include/crypto/akcipher.h:133
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_exit_tfm
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify_complete_cb
  - crypto/rsa-pkcs1pad.c:pkcs1pad_sign
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete_cb
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete_cb
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff8149312f)
Location: include/crypto/akcipher.h:133
Inline: True
Inline callers:
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
In crypto/akcipher.c (0)
Location: include/crypto/akcipher.h:133
Inline: True
```
```
In crypto/rsa-pkcs1pad.c (ffffffff814ad38a)
Location: include/crypto/akcipher.h:133
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_exit_tfm
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify_complete_cb
  - crypto/rsa-pkcs1pad.c:pkcs1pad_sign
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete_cb
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete_cb
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff814c08f6)
Location: include/crypto/akcipher.h:133
Inline: True
Inline callers:
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
In crypto/akcipher.c (0)
Location: include/crypto/akcipher.h:133
Inline: True
```
```
In crypto/rsa-pkcs1pad.c (ffffffff814c803a)
Location: include/crypto/akcipher.h:133
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_exit_tfm
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify_complete_cb
  - crypto/rsa-pkcs1pad.c:pkcs1pad_sign
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete_cb
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete_cb
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff814d9746)
Location: include/crypto/akcipher.h:133
Inline: True
Inline callers:
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
In crypto/akcipher.c (0)
Location: include/crypto/akcipher.h:133
Inline: True
```
```
In crypto/rsa-pkcs1pad.c (ffffffff8152760a)
Location: include/crypto/akcipher.h:133
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_exit_tfm
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify_complete_cb
  - crypto/rsa-pkcs1pad.c:pkcs1pad_sign
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete_cb
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete_cb
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff81539111)
Location: include/crypto/akcipher.h:133
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
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
In crypto/akcipher.c (0)
Location: include/crypto/akcipher.h:133
Inline: True
```
```
In crypto/rsa-pkcs1pad.c (ffffffff8154457a)
Location: include/crypto/akcipher.h:133
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_exit_tfm
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify_complete_cb
  - crypto/rsa-pkcs1pad.c:pkcs1pad_sign
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete_cb
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete_cb
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff81555ef1)
Location: include/crypto/akcipher.h:133
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
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
In crypto/akcipher.c (0)
Location: include/crypto/akcipher.h:133
Inline: True
```
```
In crypto/rsa-pkcs1pad.c (ffffffff8154cbfa)
Location: include/crypto/akcipher.h:133
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_exit_tfm
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify_complete_cb
  - crypto/rsa-pkcs1pad.c:pkcs1pad_sign
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete_cb
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete_cb
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff8155e66b)
Location: include/crypto/akcipher.h:133
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
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
In crypto/akcipher.c (0)
Location: include/crypto/akcipher.h:133
Inline: True
```
```
In crypto/rsa-pkcs1pad.c (ffffffff815ad3da)
Location: include/crypto/akcipher.h:133
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_exit_tfm
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify_complete_cb
  - crypto/rsa-pkcs1pad.c:pkcs1pad_sign
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete_cb
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete_cb
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff815bf9bb)
Location: include/crypto/akcipher.h:133
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
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
Location: include/crypto/akcipher.h:133
Inline: True
```
```
In crypto/rsa-pkcs1pad.c (ffffffff8165584a)
Location: include/crypto/akcipher.h:133
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_exit_tfm
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify_complete_cb
  - crypto/rsa-pkcs1pad.c:pkcs1pad_sign
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete_cb
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete_cb
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff8166a16f)
Location: include/crypto/akcipher.h:133
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_query
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
Location: include/crypto/akcipher.h:134
Inline: True
```
```
In crypto/rsa-pkcs1pad.c (ffffffff8170f9fa)
Location: include/crypto/akcipher.h:134
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_exit_tfm
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_sign
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff8172473a)
Location: include/crypto/akcipher.h:134
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_query
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
In crypto/akcipher.c (ffffffff8174744a)
Location: include/crypto/akcipher.h:161
Inline: True
Inline callers:
  - crypto/akcipher.c:crypto_exit_akcipher_ops_sig
  - crypto/akcipher.c:crypto_akcipher_sync_prep
```
```
In crypto/sig.c (0)
Location: include/crypto/akcipher.h:161
Inline: True
```
```
In crypto/rsa-pkcs1pad.c (ffffffff8174a2aa)
Location: include/crypto/akcipher.h:161
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_exit_tfm
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_sign
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff81760e17)
Location: include/crypto/akcipher.h:161
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_query
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
In crypto/akcipher.c (ffffffff817892ba)
Location: include/crypto/akcipher.h:161
Inline: True
Inline callers:
  - crypto/akcipher.c:crypto_exit_akcipher_ops_sig
  - crypto/akcipher.c:crypto_akcipher_sync_prep
```
```
In crypto/sig.c (0)
Location: include/crypto/akcipher.h:161
Inline: True
```
```
In crypto/rsa-pkcs1pad.c (ffffffff8178c14a)
Location: include/crypto/akcipher.h:161
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_exit_tfm
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_sign
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff817a2777)
Location: include/crypto/akcipher.h:161
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_query
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
In crypto/akcipher.c (0)
Location: include/crypto/akcipher.h:133
Inline: True
```
```
In crypto/rsa-pkcs1pad.c (ffff8000105c3a74)
Location: include/crypto/akcipher.h:133
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_exit_tfm
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify_complete_cb
  - crypto/rsa-pkcs1pad.c:pkcs1pad_sign
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete_cb
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete_cb
```
```
In crypto/asymmetric_keys/public_key.c (ffff8000105d5914)
Location: include/crypto/akcipher.h:133
Inline: True
Inline callers:
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
In crypto/akcipher.c (0)
Location: include/crypto/akcipher.h:133
Inline: True
```
```
In crypto/rsa-pkcs1pad.c (c0770c98)
Location: include/crypto/akcipher.h:133
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_exit_tfm
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_sign
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
```
```
In crypto/asymmetric_keys/public_key.c (c0783148)
Location: include/crypto/akcipher.h:133
Inline: True
Inline callers:
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
In crypto/akcipher.c (0)
Location: include/crypto/akcipher.h:133
Inline: True
```
```
In crypto/rsa-pkcs1pad.c (c00000000074c730)
Location: include/crypto/akcipher.h:133
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_exit_tfm
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify_complete_cb
  - crypto/rsa-pkcs1pad.c:pkcs1pad_sign
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete_cb
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete_cb
```
```
In crypto/asymmetric_keys/public_key.c (c0000000007640a4)
Location: include/crypto/akcipher.h:133
Inline: True
Inline callers:
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
In crypto/akcipher.c (0)
Location: include/crypto/akcipher.h:133
Inline: True
```
```
In crypto/rsa-pkcs1pad.c (ffffffe0004081e0)
Location: include/crypto/akcipher.h:133
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_exit_tfm
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify_complete_cb
  - crypto/rsa-pkcs1pad.c:pkcs1pad_sign
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete_cb
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete_cb
```
```
In crypto/asymmetric_keys/public_key.c (ffffffe000419af8)
Location: include/crypto/akcipher.h:133
Inline: True
Inline callers:
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
In crypto/akcipher.c (0)
Location: include/crypto/akcipher.h:133
Inline: True
```
```
In crypto/rsa-pkcs1pad.c (ffffffff814c061a)
Location: include/crypto/akcipher.h:133
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_exit_tfm
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify_complete_cb
  - crypto/rsa-pkcs1pad.c:pkcs1pad_sign
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete_cb
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete_cb
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff814d1d26)
Location: include/crypto/akcipher.h:133
Inline: True
Inline callers:
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
In crypto/akcipher.c (0)
Location: include/crypto/akcipher.h:133
Inline: True
```
```
In crypto/rsa-pkcs1pad.c (ffffffff814b103a)
Location: include/crypto/akcipher.h:133
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_exit_tfm
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify_complete_cb
  - crypto/rsa-pkcs1pad.c:pkcs1pad_sign
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete_cb
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete_cb
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff814c2746)
Location: include/crypto/akcipher.h:133
Inline: True
Inline callers:
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
In crypto/akcipher.c (0)
Location: include/crypto/akcipher.h:133
Inline: True
```
```
In crypto/rsa-pkcs1pad.c (ffffffff814bc6aa)
Location: include/crypto/akcipher.h:133
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_exit_tfm
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify_complete_cb
  - crypto/rsa-pkcs1pad.c:pkcs1pad_sign
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete_cb
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete_cb
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff814cddb6)
Location: include/crypto/akcipher.h:133
Inline: True
Inline callers:
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
In crypto/akcipher.c (0)
Location: include/crypto/akcipher.h:133
Inline: True
```
```
In crypto/rsa-pkcs1pad.c (ffffffff814d517a)
Location: include/crypto/akcipher.h:133
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_exit_tfm
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify_complete_cb
  - crypto/rsa-pkcs1pad.c:pkcs1pad_sign
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete_cb
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete_cb
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff814e6886)
Location: include/crypto/akcipher.h:133
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:software_key_query
```
</details>
</li>
</ul>

## Differences
