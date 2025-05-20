# Function: <code>__crypto_aead_cast</code>

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
In crypto/aead.c (ffffffff8139ef38)
Location: include/crypto/aead.h:158
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_init_tfm
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
In crypto/aead.c (ffffffff813dbce8)
Location: include/crypto/aead.h:161
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_init_tfm
  - crypto/aead.c:crypto_aead_exit_tfm
```
```
In crypto/seqiv.c (0)
Location: include/crypto/aead.h:161
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
In crypto/aead.c (ffffffff813f35c8)
Location: include/crypto/aead.h:161
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_init_tfm
  - crypto/aead.c:crypto_aead_exit_tfm
```
```
In crypto/skcipher.c (0)
Location: include/crypto/aead.h:161
Inline: True
```
```
In crypto/seqiv.c (0)
Location: include/crypto/aead.h:161
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
In crypto/aead.c (ffffffff813ff8e8)
Location: include/crypto/aead.h:161
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_init_tfm
  - crypto/aead.c:crypto_aead_exit_tfm
```
```
In crypto/skcipher.c (0)
Location: include/crypto/aead.h:161
Inline: True
```
```
In crypto/seqiv.c (0)
Location: include/crypto/aead.h:161
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
In security/keys/big_key.c (0)
Location: include/crypto/aead.h:161
Inline: True
```
```
In crypto/aead.c (ffffffff81427eb8)
Location: include/crypto/aead.h:161
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_init_tfm
  - crypto/aead.c:crypto_aead_exit_tfm
```
```
In crypto/skcipher.c (0)
Location: include/crypto/aead.h:161
Inline: True
```
```
In crypto/seqiv.c (0)
Location: include/crypto/aead.h:161
Inline: True
```
```
In crypto/gcm.c (0)
Location: include/crypto/aead.h:161
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
In security/keys/big_key.c (ffffffff813ecdf4)
Location: include/crypto/aead.h:161
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_crypt
  - security/keys/big_key.c:big_key_crypt
```
```
In crypto/aead.c (ffffffff8145ace5)
Location: include/crypto/aead.h:161
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_init_tfm
  - crypto/aead.c:crypto_aead_exit_tfm
```
```
In crypto/skcipher.c (ffffffff8145e425)
Location: include/crypto/aead.h:161
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_decrypt
  - crypto/skcipher.c:skcipher_walk_aead_common
```
```
In crypto/seqiv.c (ffffffff8145e519)
Location: include/crypto/aead.h:161
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
  - crypto/seqiv.c:seqiv_aead_decrypt
  - crypto/seqiv.c:seqiv_aead_encrypt
  - crypto/seqiv.c:seqiv_aead_encrypt
  - crypto/seqiv.c:seqiv_aead_encrypt_complete2
```
```
In crypto/gcm.c (ffffffff8146b284)
Location: include/crypto/aead.h:161
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_rfc4106_decrypt
  - crypto/gcm.c:crypto_rfc4106_encrypt
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_gcm_decrypt
  - crypto/gcm.c:crypto_gcm_decrypt
  - crypto/gcm.c:gcm_dec_hash_continue
  - crypto/gcm.c:gcm_dec_hash_continue
  - crypto/gcm.c:gcm_dec_hash_continue
  - crypto/gcm.c:crypto_gcm_verify
  - crypto/gcm.c:crypto_gcm_verify
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:gcm_encrypt_continue
  - crypto/gcm.c:gcm_enc_copy_hash
  - crypto/gcm.c:gcm_enc_copy_hash
  - crypto/gcm.c:gcm_hash
  - crypto/gcm.c:gcm_hash
  - crypto/gcm.c:gcm_hash_init_continue
  - crypto/gcm.c:gcm_hash_assoc_continue
  - crypto/gcm.c:gcm_hash_assoc_remain_continue
  - crypto/gcm.c:gcm_hash_assoc_remain_continue
  - crypto/gcm.c:gcm_hash_crypt_continue
  - crypto/gcm.c:gcm_hash_crypt_continue
  - crypto/gcm.c:gcm_hash_len_done
  - crypto/gcm.c:crypto_gcm_init_common
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
In security/keys/big_key.c (ffffffff8140800c)
Location: include/crypto/aead.h:158
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_crypt
  - security/keys/big_key.c:big_key_crypt
```
```
In crypto/aead.c (ffffffff81478855)
Location: include/crypto/aead.h:158
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_init_tfm
  - crypto/aead.c:crypto_aead_exit_tfm
```
```
In crypto/skcipher.c (ffffffff8147bce5)
Location: include/crypto/aead.h:158
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_decrypt
  - crypto/skcipher.c:skcipher_walk_aead_common
```
```
In crypto/seqiv.c (ffffffff8147bde6)
Location: include/crypto/aead.h:158
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
  - crypto/seqiv.c:seqiv_aead_decrypt
  - crypto/seqiv.c:seqiv_aead_encrypt
  - crypto/seqiv.c:seqiv_aead_encrypt
  - crypto/seqiv.c:seqiv_aead_encrypt_complete2
```
```
In crypto/gcm.c (ffffffff8148955e)
Location: include/crypto/aead.h:158
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_copy_src_to_dst
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_rfc4106_decrypt
  - crypto/gcm.c:crypto_rfc4106_encrypt
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_gcm_decrypt
  - crypto/gcm.c:crypto_gcm_decrypt
  - crypto/gcm.c:gcm_dec_hash_continue
  - crypto/gcm.c:gcm_dec_hash_continue
  - crypto/gcm.c:gcm_dec_hash_continue
  - crypto/gcm.c:crypto_gcm_verify
  - crypto/gcm.c:crypto_gcm_verify
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:gcm_encrypt_continue
  - crypto/gcm.c:gcm_enc_copy_hash
  - crypto/gcm.c:gcm_enc_copy_hash
  - crypto/gcm.c:gcm_hash
  - crypto/gcm.c:gcm_hash
  - crypto/gcm.c:gcm_hash_assoc_remain_continue
  - crypto/gcm.c:gcm_hash_crypt_continue
  - crypto/gcm.c:gcm_hash_len_done
  - crypto/gcm.c:gcm_hash_update
  - crypto/gcm.c:crypto_gcm_init_common
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
In crypto/aead.c (ffffffff814a6685)
Location: include/crypto/aead.h:153
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_init_tfm
  - crypto/aead.c:crypto_aead_exit_tfm
  - crypto/aead.c:crypto_aead_decrypt
  - crypto/aead.c:crypto_aead_encrypt
```
```
In crypto/skcipher.c (ffffffff814aa095)
Location: include/crypto/aead.h:153
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_decrypt
  - crypto/skcipher.c:skcipher_walk_aead_common
```
```
In crypto/seqiv.c (ffffffff814aa1d9)
Location: include/crypto/aead.h:153
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
  - crypto/seqiv.c:seqiv_aead_encrypt
  - crypto/seqiv.c:seqiv_aead_encrypt_complete2
```
```
In crypto/gcm.c (ffffffff814b6213)
Location: include/crypto/aead.h:153
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_copy_src_to_dst
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_gcm_decrypt
  - crypto/gcm.c:crypto_gcm_decrypt
  - crypto/gcm.c:gcm_dec_hash_continue
  - crypto/gcm.c:gcm_dec_hash_continue
  - crypto/gcm.c:gcm_dec_hash_continue
  - crypto/gcm.c:crypto_gcm_verify
  - crypto/gcm.c:crypto_gcm_verify
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:gcm_encrypt_continue
  - crypto/gcm.c:gcm_enc_copy_hash
  - crypto/gcm.c:gcm_enc_copy_hash
  - crypto/gcm.c:gcm_hash
  - crypto/gcm.c:gcm_hash
  - crypto/gcm.c:gcm_hash_assoc_remain_continue
  - crypto/gcm.c:gcm_hash_crypt_continue
  - crypto/gcm.c:gcm_hash_len_done
  - crypto/gcm.c:gcm_hash_update
  - crypto/gcm.c:crypto_gcm_init_common
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
In crypto/aead.c (ffffffff814c1325)
Location: include/crypto/aead.h:153
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_init_tfm
  - crypto/aead.c:crypto_aead_exit_tfm
  - crypto/aead.c:crypto_aead_decrypt
  - crypto/aead.c:crypto_aead_encrypt
```
```
In crypto/skcipher.c (ffffffff814c4d85)
Location: include/crypto/aead.h:153
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_decrypt
  - crypto/skcipher.c:skcipher_walk_aead_common
```
```
In crypto/seqiv.c (ffffffff814c4e99)
Location: include/crypto/aead.h:153
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
  - crypto/seqiv.c:seqiv_aead_encrypt
  - crypto/seqiv.c:seqiv_aead_encrypt_complete2
```
```
In crypto/gcm.c (ffffffff814cf413)
Location: include/crypto/aead.h:153
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_copy_src_to_dst
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_gcm_decrypt
  - crypto/gcm.c:crypto_gcm_decrypt
  - crypto/gcm.c:gcm_dec_hash_continue
  - crypto/gcm.c:gcm_dec_hash_continue
  - crypto/gcm.c:gcm_dec_hash_continue
  - crypto/gcm.c:crypto_gcm_verify
  - crypto/gcm.c:crypto_gcm_verify
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:gcm_encrypt_continue
  - crypto/gcm.c:gcm_enc_copy_hash
  - crypto/gcm.c:gcm_enc_copy_hash
  - crypto/gcm.c:gcm_hash
  - crypto/gcm.c:gcm_hash
  - crypto/gcm.c:gcm_hash_assoc_remain_continue
  - crypto/gcm.c:gcm_hash_crypt_continue
  - crypto/gcm.c:gcm_hash_len_done
  - crypto/gcm.c:gcm_hash_update
  - crypto/gcm.c:crypto_gcm_init_common
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
In crypto/aead.c (ffffffff81521bd5)
Location: include/crypto/aead.h:159
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_init_tfm
  - crypto/aead.c:crypto_aead_exit_tfm
  - crypto/aead.c:crypto_aead_decrypt
  - crypto/aead.c:crypto_aead_encrypt
```
```
In crypto/skcipher.c (ffffffff81523bf5)
Location: include/crypto/aead.h:159
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_decrypt
  - crypto/skcipher.c:skcipher_walk_aead_common
```
```
In crypto/seqiv.c (ffffffff81523da9)
Location: include/crypto/aead.h:159
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
  - crypto/seqiv.c:seqiv_aead_encrypt
  - crypto/seqiv.c:seqiv_aead_encrypt_complete2
```
```
In crypto/gcm.c (ffffffff8152e633)
Location: include/crypto/aead.h:159
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_copy_src_to_dst
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_gcm_decrypt
  - crypto/gcm.c:crypto_gcm_decrypt
  - crypto/gcm.c:gcm_dec_hash_continue
  - crypto/gcm.c:gcm_dec_hash_continue
  - crypto/gcm.c:gcm_dec_hash_continue
  - crypto/gcm.c:crypto_gcm_verify
  - crypto/gcm.c:crypto_gcm_verify
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:gcm_encrypt_continue
  - crypto/gcm.c:gcm_enc_copy_hash
  - crypto/gcm.c:gcm_enc_copy_hash
  - crypto/gcm.c:gcm_hash
  - crypto/gcm.c:gcm_hash
  - crypto/gcm.c:gcm_hash_assoc_remain_continue
  - crypto/gcm.c:gcm_hash_crypt_continue
  - crypto/gcm.c:gcm_hash_crypt_remain_continue
  - crypto/gcm.c:gcm_hash_len_done
  - crypto/gcm.c:gcm_hash_len
  - crypto/gcm.c:gcm_hash_update
  - crypto/gcm.c:crypto_gcm_init_common
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
In crypto/aead.c (ffffffff8153ea45)
Location: include/crypto/aead.h:159
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_init_tfm
  - crypto/aead.c:crypto_aead_exit_tfm
  - crypto/aead.c:crypto_aead_decrypt
  - crypto/aead.c:crypto_aead_encrypt
```
```
In crypto/skcipher.c (ffffffff81540b45)
Location: include/crypto/aead.h:159
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_decrypt
  - crypto/skcipher.c:skcipher_walk_aead_common
```
```
In crypto/seqiv.c (ffffffff81540c29)
Location: include/crypto/aead.h:159
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
  - crypto/seqiv.c:seqiv_aead_encrypt
  - crypto/seqiv.c:seqiv_aead_encrypt_complete2
```
```
In crypto/gcm.c (ffffffff8154b5d3)
Location: include/crypto/aead.h:159
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_copy_src_to_dst
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_gcm_decrypt
  - crypto/gcm.c:crypto_gcm_decrypt
  - crypto/gcm.c:gcm_dec_hash_continue
  - crypto/gcm.c:gcm_dec_hash_continue
  - crypto/gcm.c:gcm_dec_hash_continue
  - crypto/gcm.c:crypto_gcm_verify
  - crypto/gcm.c:crypto_gcm_verify
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:gcm_encrypt_continue
  - crypto/gcm.c:gcm_enc_copy_hash
  - crypto/gcm.c:gcm_enc_copy_hash
  - crypto/gcm.c:gcm_hash
  - crypto/gcm.c:gcm_hash
  - crypto/gcm.c:gcm_hash_assoc_remain_continue
  - crypto/gcm.c:gcm_hash_crypt_continue
  - crypto/gcm.c:gcm_hash_crypt_remain_continue
  - crypto/gcm.c:gcm_hash_len_done
  - crypto/gcm.c:gcm_hash_len
  - crypto/gcm.c:gcm_hash_update
  - crypto/gcm.c:crypto_gcm_init_common
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
In crypto/aead.c (ffffffff815470f5)
Location: include/crypto/aead.h:159
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_init_tfm
  - crypto/aead.c:crypto_aead_exit_tfm
  - crypto/aead.c:crypto_aead_decrypt
  - crypto/aead.c:crypto_aead_encrypt
```
```
In crypto/skcipher.c (ffffffff815491a5)
Location: include/crypto/aead.h:159
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_decrypt
  - crypto/skcipher.c:skcipher_walk_aead_common
```
```
In crypto/seqiv.c (ffffffff81549292)
Location: include/crypto/aead.h:159
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
  - crypto/seqiv.c:seqiv_aead_encrypt
  - crypto/seqiv.c:seqiv_aead_encrypt_complete2
```
```
In crypto/gcm.c (ffffffff81553be3)
Location: include/crypto/aead.h:159
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_copy_src_to_dst
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_gcm_decrypt
  - crypto/gcm.c:crypto_gcm_decrypt
  - crypto/gcm.c:gcm_dec_hash_continue
  - crypto/gcm.c:gcm_dec_hash_continue
  - crypto/gcm.c:gcm_dec_hash_continue
  - crypto/gcm.c:crypto_gcm_verify
  - crypto/gcm.c:crypto_gcm_verify
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:gcm_encrypt_continue
  - crypto/gcm.c:gcm_enc_copy_hash
  - crypto/gcm.c:gcm_enc_copy_hash
  - crypto/gcm.c:gcm_hash
  - crypto/gcm.c:gcm_hash
  - crypto/gcm.c:gcm_hash_assoc_remain_continue
  - crypto/gcm.c:gcm_hash_crypt_continue
  - crypto/gcm.c:gcm_hash_crypt_remain_continue
  - crypto/gcm.c:gcm_hash_crypt_remain_continue
  - crypto/gcm.c:gcm_hash_len_done
  - crypto/gcm.c:gcm_hash_update
  - crypto/gcm.c:crypto_gcm_init_common
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
In crypto/aead.c (ffffffff815a78d5)
Location: include/crypto/aead.h:159
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_init_tfm
  - crypto/aead.c:crypto_aead_exit_tfm
  - crypto/aead.c:crypto_aead_decrypt
  - crypto/aead.c:crypto_aead_encrypt
```
```
In crypto/skcipher.c (ffffffff815a9985)
Location: include/crypto/aead.h:159
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_decrypt
  - crypto/skcipher.c:skcipher_walk_aead_common
```
```
In crypto/seqiv.c (ffffffff815a9a72)
Location: include/crypto/aead.h:159
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
  - crypto/seqiv.c:seqiv_aead_encrypt
  - crypto/seqiv.c:seqiv_aead_encrypt_complete2
```
```
In crypto/gcm.c (ffffffff815b4c13)
Location: include/crypto/aead.h:159
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_copy_src_to_dst
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_gcm_decrypt
  - crypto/gcm.c:crypto_gcm_decrypt
  - crypto/gcm.c:gcm_dec_hash_continue
  - crypto/gcm.c:gcm_dec_hash_continue
  - crypto/gcm.c:gcm_dec_hash_continue
  - crypto/gcm.c:crypto_gcm_verify
  - crypto/gcm.c:crypto_gcm_verify
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:gcm_encrypt_continue
  - crypto/gcm.c:gcm_enc_copy_hash
  - crypto/gcm.c:gcm_enc_copy_hash
  - crypto/gcm.c:gcm_hash
  - crypto/gcm.c:gcm_hash
  - crypto/gcm.c:gcm_hash_assoc_remain_continue
  - crypto/gcm.c:gcm_hash_crypt_continue
  - crypto/gcm.c:gcm_hash_crypt_remain_continue
  - crypto/gcm.c:gcm_hash_crypt_remain_continue
  - crypto/gcm.c:gcm_hash_len_done
  - crypto/gcm.c:gcm_hash_update
  - crypto/gcm.c:crypto_gcm_init_common
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
In crypto/aead.c (ffffffff8164ec05)
Location: include/crypto/aead.h:161
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_init_tfm
  - crypto/aead.c:crypto_aead_exit_tfm
```
```
In crypto/skcipher.c (0)
Location: include/crypto/aead.h:161
Inline: True
```
```
In crypto/seqiv.c (0)
Location: include/crypto/aead.h:161
Inline: True
```
```
In crypto/gcm.c (0)
Location: include/crypto/aead.h:161
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
In crypto/aead.c (ffffffff817080e5)
Location: include/crypto/aead.h:161
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_init_tfm
  - crypto/aead.c:crypto_aead_exit_tfm
```
```
In crypto/skcipher.c (0)
Location: include/crypto/aead.h:161
Inline: True
```
```
In crypto/seqiv.c (0)
Location: include/crypto/aead.h:161
Inline: True
```
```
In crypto/gcm.c (0)
Location: include/crypto/aead.h:161
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
In crypto/aead.c (ffffffff81741805)
Location: include/crypto/aead.h:183
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_init_tfm
  - crypto/aead.c:crypto_aead_exit_tfm
```
```
In crypto/skcipher.c (0)
Location: include/crypto/aead.h:183
Inline: True
```
```
In crypto/seqiv.c (0)
Location: include/crypto/aead.h:183
Inline: True
```
```
In crypto/gcm.c (0)
Location: include/crypto/aead.h:183
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
In crypto/aead.c (ffffffff817826a5)
Location: include/crypto/aead.h:183
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_init_tfm
  - crypto/aead.c:crypto_aead_exit_tfm
```
```
In crypto/skcipher.c (0)
Location: include/crypto/aead.h:183
Inline: True
```
```
In crypto/seqiv.c (0)
Location: include/crypto/aead.h:183
Inline: True
```
```
In crypto/gcm.c (0)
Location: include/crypto/aead.h:183
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
In crypto/aead.c (ffff8000105bb638)
Location: include/crypto/aead.h:153
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_init_tfm
  - crypto/aead.c:crypto_aead_exit_tfm
  - crypto/aead.c:crypto_aead_decrypt
  - crypto/aead.c:crypto_aead_encrypt
```
```
In crypto/skcipher.c (ffff8000105bf8c4)
Location: include/crypto/aead.h:153
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_decrypt
  - crypto/skcipher.c:skcipher_walk_aead_common
```
```
In crypto/seqiv.c (ffff8000105bfa50)
Location: include/crypto/aead.h:153
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
  - crypto/seqiv.c:seqiv_aead_encrypt
  - crypto/seqiv.c:seqiv_aead_encrypt_complete2
```
```
In crypto/gcm.c (ffff8000105cb420)
Location: include/crypto/aead.h:153
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_copy_src_to_dst
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_gcm_decrypt
  - crypto/gcm.c:crypto_gcm_decrypt
  - crypto/gcm.c:gcm_dec_hash_continue
  - crypto/gcm.c:gcm_dec_hash_continue
  - crypto/gcm.c:gcm_dec_hash_continue
  - crypto/gcm.c:crypto_gcm_verify
  - crypto/gcm.c:crypto_gcm_verify
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:gcm_encrypt_continue
  - crypto/gcm.c:gcm_enc_copy_hash
  - crypto/gcm.c:gcm_enc_copy_hash
  - crypto/gcm.c:gcm_hash
  - crypto/gcm.c:gcm_hash
  - crypto/gcm.c:gcm_hash_assoc_remain_continue
  - crypto/gcm.c:gcm_hash_crypt_continue
  - crypto/gcm.c:gcm_hash_len_done
  - crypto/gcm.c:gcm_hash_update
  - crypto/gcm.c:crypto_gcm_init_common
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
In crypto/aead.c (c0769898)
Location: include/crypto/aead.h:153
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_init_tfm
  - crypto/aead.c:crypto_aead_exit_tfm
  - crypto/aead.c:crypto_aead_decrypt
  - crypto/aead.c:crypto_aead_encrypt
```
```
In crypto/skcipher.c (c076d570)
Location: include/crypto/aead.h:153
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_decrypt
  - crypto/skcipher.c:skcipher_walk_aead_common
```
```
In crypto/seqiv.c (c076d6a4)
Location: include/crypto/aead.h:153
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
  - crypto/seqiv.c:seqiv_aead_encrypt
  - crypto/seqiv.c:seqiv_aead_encrypt_complete2
```
```
In crypto/gcm.c (c0778f28)
Location: include/crypto/aead.h:153
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_copy_src_to_dst
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_gcm_decrypt
  - crypto/gcm.c:crypto_gcm_decrypt
  - crypto/gcm.c:gcm_dec_hash_continue
  - crypto/gcm.c:gcm_dec_hash_continue
  - crypto/gcm.c:gcm_dec_hash_continue
  - crypto/gcm.c:crypto_gcm_verify
  - crypto/gcm.c:crypto_gcm_verify
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:gcm_encrypt_continue
  - crypto/gcm.c:gcm_enc_copy_hash
  - crypto/gcm.c:gcm_enc_copy_hash
  - crypto/gcm.c:gcm_hash
  - crypto/gcm.c:gcm_hash
  - crypto/gcm.c:gcm_hash_assoc_remain_continue
  - crypto/gcm.c:gcm_hash_crypt_continue
  - crypto/gcm.c:gcm_hash_len_done
  - crypto/gcm.c:gcm_hash_update
  - crypto/gcm.c:crypto_gcm_init_common
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
In crypto/aead.c (c000000000741f30)
Location: include/crypto/aead.h:153
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_init_tfm
  - crypto/aead.c:crypto_aead_exit_tfm
  - crypto/aead.c:crypto_aead_decrypt
  - crypto/aead.c:crypto_aead_encrypt
```
```
In crypto/skcipher.c (c000000000747630)
Location: include/crypto/aead.h:153
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_decrypt
  - crypto/skcipher.c:skcipher_walk_aead_common
```
```
In crypto/seqiv.c (c000000000747814)
Location: include/crypto/aead.h:153
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
  - crypto/seqiv.c:seqiv_aead_encrypt
  - crypto/seqiv.c:seqiv_aead_encrypt_complete2
```
```
In crypto/gcm.c (c000000000756444)
Location: include/crypto/aead.h:153
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_copy_src_to_dst
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_gcm_decrypt
  - crypto/gcm.c:crypto_gcm_decrypt
  - crypto/gcm.c:gcm_dec_hash_continue
  - crypto/gcm.c:gcm_dec_hash_continue
  - crypto/gcm.c:gcm_dec_hash_continue
  - crypto/gcm.c:crypto_gcm_verify
  - crypto/gcm.c:crypto_gcm_verify
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:gcm_encrypt_continue
  - crypto/gcm.c:gcm_enc_copy_hash
  - crypto/gcm.c:gcm_enc_copy_hash
  - crypto/gcm.c:gcm_hash
  - crypto/gcm.c:gcm_hash
  - crypto/gcm.c:gcm_hash_assoc_remain_continue
  - crypto/gcm.c:gcm_hash_crypt_continue
  - crypto/gcm.c:gcm_hash_len_done
  - crypto/gcm.c:gcm_hash_update
  - crypto/gcm.c:crypto_gcm_init_common
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
In crypto/aead.c (ffffffe0004010a4)
Location: include/crypto/aead.h:153
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_init_tfm
  - crypto/aead.c:crypto_aead_exit_tfm
  - crypto/aead.c:crypto_aead_decrypt
  - crypto/aead.c:crypto_aead_encrypt
```
```
In crypto/skcipher.c (ffffffe0004049f4)
Location: include/crypto/aead.h:153
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_decrypt
  - crypto/skcipher.c:skcipher_walk_aead_common
```
```
In crypto/seqiv.c (ffffffe000404b26)
Location: include/crypto/aead.h:153
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
  - crypto/seqiv.c:seqiv_aead_encrypt
  - crypto/seqiv.c:seqiv_aead_encrypt_complete2
```
```
In crypto/gcm.c (ffffffe00040f79c)
Location: include/crypto/aead.h:153
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_copy_src_to_dst
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_gcm_decrypt
  - crypto/gcm.c:crypto_gcm_decrypt
  - crypto/gcm.c:gcm_dec_hash_continue
  - crypto/gcm.c:gcm_dec_hash_continue
  - crypto/gcm.c:gcm_dec_hash_continue
  - crypto/gcm.c:crypto_gcm_verify
  - crypto/gcm.c:crypto_gcm_verify
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:gcm_encrypt_continue
  - crypto/gcm.c:gcm_enc_copy_hash
  - crypto/gcm.c:gcm_enc_copy_hash
  - crypto/gcm.c:gcm_hash
  - crypto/gcm.c:gcm_hash
  - crypto/gcm.c:gcm_hash_assoc_remain_continue
  - crypto/gcm.c:gcm_hash_crypt_continue
  - crypto/gcm.c:gcm_hash_len_done
  - crypto/gcm.c:gcm_hash_update
  - crypto/gcm.c:crypto_gcm_init_common
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
In crypto/aead.c (ffffffff814b9905)
Location: include/crypto/aead.h:153
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_init_tfm
  - crypto/aead.c:crypto_aead_exit_tfm
  - crypto/aead.c:crypto_aead_decrypt
  - crypto/aead.c:crypto_aead_encrypt
```
```
In crypto/skcipher.c (ffffffff814bd365)
Location: include/crypto/aead.h:153
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_decrypt
  - crypto/skcipher.c:skcipher_walk_aead_common
```
```
In crypto/seqiv.c (ffffffff814bd479)
Location: include/crypto/aead.h:153
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
  - crypto/seqiv.c:seqiv_aead_encrypt
  - crypto/seqiv.c:seqiv_aead_encrypt_complete2
```
```
In crypto/gcm.c (ffffffff814c79f3)
Location: include/crypto/aead.h:153
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_copy_src_to_dst
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_gcm_decrypt
  - crypto/gcm.c:crypto_gcm_decrypt
  - crypto/gcm.c:gcm_dec_hash_continue
  - crypto/gcm.c:gcm_dec_hash_continue
  - crypto/gcm.c:gcm_dec_hash_continue
  - crypto/gcm.c:crypto_gcm_verify
  - crypto/gcm.c:crypto_gcm_verify
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:gcm_encrypt_continue
  - crypto/gcm.c:gcm_enc_copy_hash
  - crypto/gcm.c:gcm_enc_copy_hash
  - crypto/gcm.c:gcm_hash
  - crypto/gcm.c:gcm_hash
  - crypto/gcm.c:gcm_hash_assoc_remain_continue
  - crypto/gcm.c:gcm_hash_crypt_continue
  - crypto/gcm.c:gcm_hash_len_done
  - crypto/gcm.c:gcm_hash_update
  - crypto/gcm.c:crypto_gcm_init_common
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
In crypto/aead.c (ffffffff814aa325)
Location: include/crypto/aead.h:153
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_init_tfm
  - crypto/aead.c:crypto_aead_exit_tfm
  - crypto/aead.c:crypto_aead_decrypt
  - crypto/aead.c:crypto_aead_encrypt
```
```
In crypto/skcipher.c (ffffffff814add85)
Location: include/crypto/aead.h:153
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_decrypt
  - crypto/skcipher.c:skcipher_walk_aead_common
```
```
In crypto/seqiv.c (ffffffff814ade99)
Location: include/crypto/aead.h:153
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
  - crypto/seqiv.c:seqiv_aead_encrypt
  - crypto/seqiv.c:seqiv_aead_encrypt_complete2
```
```
In crypto/gcm.c (ffffffff814b8413)
Location: include/crypto/aead.h:153
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_copy_src_to_dst
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_gcm_decrypt
  - crypto/gcm.c:crypto_gcm_decrypt
  - crypto/gcm.c:gcm_dec_hash_continue
  - crypto/gcm.c:gcm_dec_hash_continue
  - crypto/gcm.c:gcm_dec_hash_continue
  - crypto/gcm.c:crypto_gcm_verify
  - crypto/gcm.c:crypto_gcm_verify
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:gcm_encrypt_continue
  - crypto/gcm.c:gcm_enc_copy_hash
  - crypto/gcm.c:gcm_enc_copy_hash
  - crypto/gcm.c:gcm_hash
  - crypto/gcm.c:gcm_hash
  - crypto/gcm.c:gcm_hash_assoc_remain_continue
  - crypto/gcm.c:gcm_hash_crypt_continue
  - crypto/gcm.c:gcm_hash_len_done
  - crypto/gcm.c:gcm_hash_update
  - crypto/gcm.c:crypto_gcm_init_common
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
In crypto/aead.c (ffffffff814b5995)
Location: include/crypto/aead.h:153
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_init_tfm
  - crypto/aead.c:crypto_aead_exit_tfm
  - crypto/aead.c:crypto_aead_decrypt
  - crypto/aead.c:crypto_aead_encrypt
```
```
In crypto/skcipher.c (ffffffff814b93f5)
Location: include/crypto/aead.h:153
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_decrypt
  - crypto/skcipher.c:skcipher_walk_aead_common
```
```
In crypto/seqiv.c (ffffffff814b9509)
Location: include/crypto/aead.h:153
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
  - crypto/seqiv.c:seqiv_aead_encrypt
  - crypto/seqiv.c:seqiv_aead_encrypt_complete2
```
```
In crypto/gcm.c (ffffffff814c3a83)
Location: include/crypto/aead.h:153
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_copy_src_to_dst
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_gcm_decrypt
  - crypto/gcm.c:crypto_gcm_decrypt
  - crypto/gcm.c:gcm_dec_hash_continue
  - crypto/gcm.c:gcm_dec_hash_continue
  - crypto/gcm.c:gcm_dec_hash_continue
  - crypto/gcm.c:crypto_gcm_verify
  - crypto/gcm.c:crypto_gcm_verify
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:gcm_encrypt_continue
  - crypto/gcm.c:gcm_enc_copy_hash
  - crypto/gcm.c:gcm_enc_copy_hash
  - crypto/gcm.c:gcm_hash
  - crypto/gcm.c:gcm_hash
  - crypto/gcm.c:gcm_hash_assoc_remain_continue
  - crypto/gcm.c:gcm_hash_crypt_continue
  - crypto/gcm.c:gcm_hash_len_done
  - crypto/gcm.c:gcm_hash_update
  - crypto/gcm.c:crypto_gcm_init_common
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
In crypto/aead.c (ffffffff814ce435)
Location: include/crypto/aead.h:153
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_init_tfm
  - crypto/aead.c:crypto_aead_exit_tfm
  - crypto/aead.c:crypto_aead_decrypt
  - crypto/aead.c:crypto_aead_encrypt
```
```
In crypto/skcipher.c (ffffffff814d1e95)
Location: include/crypto/aead.h:153
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_decrypt
  - crypto/skcipher.c:skcipher_walk_aead_common
```
```
In crypto/seqiv.c (ffffffff814d1fa9)
Location: include/crypto/aead.h:153
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
  - crypto/seqiv.c:seqiv_aead_encrypt
  - crypto/seqiv.c:seqiv_aead_encrypt_complete2
```
```
In crypto/gcm.c (ffffffff814dc553)
Location: include/crypto/aead.h:153
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_copy_src_to_dst
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_gcm_decrypt
  - crypto/gcm.c:crypto_gcm_decrypt
  - crypto/gcm.c:gcm_dec_hash_continue
  - crypto/gcm.c:gcm_dec_hash_continue
  - crypto/gcm.c:gcm_dec_hash_continue
  - crypto/gcm.c:crypto_gcm_verify
  - crypto/gcm.c:crypto_gcm_verify
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:gcm_encrypt_continue
  - crypto/gcm.c:gcm_enc_copy_hash
  - crypto/gcm.c:gcm_enc_copy_hash
  - crypto/gcm.c:gcm_hash
  - crypto/gcm.c:gcm_hash
  - crypto/gcm.c:gcm_hash_assoc_remain_continue
  - crypto/gcm.c:gcm_hash_crypt_continue
  - crypto/gcm.c:gcm_hash_len_done
  - crypto/gcm.c:gcm_hash_update
  - crypto/gcm.c:crypto_gcm_init_common
```
</details>
</li>
</ul>

## Differences
