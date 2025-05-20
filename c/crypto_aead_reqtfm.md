# Function: <code>crypto_aead_reqtfm</code>

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
In crypto/seqiv.c (ffffffff813de7b5)
Location: include/crypto/aead.h:304
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
  - crypto/seqiv.c:seqiv_aead_decrypt
  - crypto/seqiv.c:seqiv_aead_encrypt
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
In crypto/skcipher.c (ffffffff813f6b58)
Location: include/crypto/aead.h:304
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
```
```
In crypto/seqiv.c (ffffffff813f6d55)
Location: include/crypto/aead.h:304
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
  - crypto/seqiv.c:seqiv_aead_decrypt
  - crypto/seqiv.c:seqiv_aead_encrypt
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
In crypto/skcipher.c (ffffffff81402f28)
Location: include/crypto/aead.h:304
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
```
```
In crypto/seqiv.c (ffffffff81403135)
Location: include/crypto/aead.h:304
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
  - crypto/seqiv.c:seqiv_aead_decrypt
  - crypto/seqiv.c:seqiv_aead_encrypt
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
Location: include/crypto/aead.h:304
Inline: True
```
```
In crypto/skcipher.c (ffffffff8142b5a0)
Location: include/crypto/aead.h:304
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
```
```
In crypto/seqiv.c (ffffffff8142b815)
Location: include/crypto/aead.h:304
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
  - crypto/seqiv.c:seqiv_aead_decrypt
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/gcm.c (ffffffff81438f5d)
Location: include/crypto/aead.h:304
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_rfc4106_decrypt
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_gcm_decrypt
  - crypto/gcm.c:gcm_dec_hash_continue
  - crypto/gcm.c:crypto_gcm_verify
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:gcm_enc_copy_hash
  - crypto/gcm.c:gcm_hash
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
Location: include/crypto/aead.h:304
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_crypt
  - security/keys/big_key.c:big_key_crypt
```
```
In crypto/skcipher.c (ffffffff8145e425)
Location: include/crypto/aead.h:304
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_decrypt
  - crypto/skcipher.c:skcipher_walk_aead_common
```
```
In crypto/seqiv.c (ffffffff8145e515)
Location: include/crypto/aead.h:304
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
Location: include/crypto/aead.h:304
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
Location: include/crypto/aead.h:301
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_crypt
  - security/keys/big_key.c:big_key_crypt
```
```
In crypto/skcipher.c (ffffffff8147bce5)
Location: include/crypto/aead.h:301
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_decrypt
  - crypto/skcipher.c:skcipher_walk_aead_common
```
```
In crypto/seqiv.c (ffffffff8147bdd5)
Location: include/crypto/aead.h:301
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
  - crypto/seqiv.c:seqiv_aead_decrypt
  - crypto/seqiv.c:seqiv_aead_encrypt
  - crypto/seqiv.c:seqiv_aead_encrypt
  - crypto/seqiv.c:seqiv_aead_encrypt_complete2
```
```
In crypto/gcm.c (ffffffff8148955a)
Location: include/crypto/aead.h:301
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
In crypto/aead.c (ffffffff814a6785)
Location: include/crypto/aead.h:296
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_decrypt
  - crypto/aead.c:crypto_aead_encrypt
```
```
In crypto/skcipher.c (ffffffff814aa095)
Location: include/crypto/aead.h:296
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_decrypt
  - crypto/skcipher.c:skcipher_walk_aead_common
```
```
In crypto/seqiv.c (ffffffff814aa1d5)
Location: include/crypto/aead.h:296
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
  - crypto/seqiv.c:seqiv_aead_encrypt
  - crypto/seqiv.c:seqiv_aead_encrypt_complete2
```
```
In crypto/gcm.c (ffffffff814b6213)
Location: include/crypto/aead.h:296
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
In crypto/aead.c (ffffffff814c13f5)
Location: include/crypto/aead.h:296
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_decrypt
  - crypto/aead.c:crypto_aead_encrypt
```
```
In crypto/skcipher.c (ffffffff814c4d85)
Location: include/crypto/aead.h:296
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_decrypt
  - crypto/skcipher.c:skcipher_walk_aead_common
```
```
In crypto/seqiv.c (ffffffff814c4e95)
Location: include/crypto/aead.h:296
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
  - crypto/seqiv.c:seqiv_aead_encrypt
  - crypto/seqiv.c:seqiv_aead_encrypt_complete2
```
```
In crypto/gcm.c (ffffffff814cf413)
Location: include/crypto/aead.h:296
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
In crypto/aead.c (ffffffff81521dc5)
Location: include/crypto/aead.h:312
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_decrypt
  - crypto/aead.c:crypto_aead_encrypt
```
```
In crypto/skcipher.c (ffffffff81523bf5)
Location: include/crypto/aead.h:312
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_decrypt
  - crypto/skcipher.c:skcipher_walk_aead_common
```
```
In crypto/seqiv.c (ffffffff81523da5)
Location: include/crypto/aead.h:312
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
  - crypto/seqiv.c:seqiv_aead_encrypt
  - crypto/seqiv.c:seqiv_aead_encrypt_complete2
```
```
In crypto/gcm.c (ffffffff8152e633)
Location: include/crypto/aead.h:312
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
In crypto/aead.c (ffffffff8153ec15)
Location: include/crypto/aead.h:317
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_decrypt
  - crypto/aead.c:crypto_aead_encrypt
```
```
In crypto/skcipher.c (ffffffff81540b45)
Location: include/crypto/aead.h:317
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_decrypt
  - crypto/skcipher.c:skcipher_walk_aead_common
```
```
In crypto/seqiv.c (ffffffff81540c25)
Location: include/crypto/aead.h:317
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
  - crypto/seqiv.c:seqiv_aead_encrypt
  - crypto/seqiv.c:seqiv_aead_encrypt_complete2
```
```
In crypto/gcm.c (ffffffff8154b5d3)
Location: include/crypto/aead.h:317
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
In crypto/aead.c (ffffffff815472b5)
Location: include/crypto/aead.h:319
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_decrypt
  - crypto/aead.c:crypto_aead_encrypt
```
```
In crypto/skcipher.c (ffffffff815491a5)
Location: include/crypto/aead.h:319
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_decrypt
  - crypto/skcipher.c:skcipher_walk_aead_common
```
```
In crypto/seqiv.c (ffffffff81549285)
Location: include/crypto/aead.h:319
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
  - crypto/seqiv.c:seqiv_aead_encrypt
  - crypto/seqiv.c:seqiv_aead_encrypt_complete2
```
```
In crypto/gcm.c (ffffffff81553be3)
Location: include/crypto/aead.h:319
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
In crypto/aead.c (ffffffff815a7a95)
Location: include/crypto/aead.h:319
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_decrypt
  - crypto/aead.c:crypto_aead_encrypt
```
```
In crypto/skcipher.c (ffffffff815a9985)
Location: include/crypto/aead.h:319
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_decrypt
  - crypto/skcipher.c:skcipher_walk_aead_common
```
```
In crypto/seqiv.c (ffffffff815a9a65)
Location: include/crypto/aead.h:319
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
  - crypto/seqiv.c:seqiv_aead_encrypt
  - crypto/seqiv.c:seqiv_aead_encrypt_complete2
```
```
In crypto/gcm.c (ffffffff815b4c13)
Location: include/crypto/aead.h:319
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
In crypto/aead.c (ffffffff8164edf5)
Location: include/crypto/aead.h:321
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_decrypt
  - crypto/aead.c:crypto_aead_encrypt
```
```
In crypto/skcipher.c (ffffffff81650e15)
Location: include/crypto/aead.h:321
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_decrypt
  - crypto/skcipher.c:skcipher_walk_aead_common
```
```
In crypto/seqiv.c (ffffffff81650f25)
Location: include/crypto/aead.h:321
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
  - crypto/seqiv.c:seqiv_aead_encrypt
  - crypto/seqiv.c:seqiv_aead_encrypt_complete2
```
```
In crypto/gcm.c (ffffffff8165db9b)
Location: include/crypto/aead.h:321
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_copy_src_to_dst
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_gcm_decrypt
  - crypto/gcm.c:gcm_dec_hash_continue
  - crypto/gcm.c:crypto_gcm_verify
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:gcm_encrypt_continue
  - crypto/gcm.c:gcm_enc_copy_hash
  - crypto/gcm.c:gcm_hash
  - crypto/gcm.c:gcm_hash_assoc_remain_continue
  - crypto/gcm.c:gcm_hash_crypt_continue
  - crypto/gcm.c:gcm_hash_crypt_remain_continue
  - crypto/gcm.c:gcm_hash_len_done
  - crypto/gcm.c:gcm_hash_update
  - crypto/gcm.c:crypto_gcm_init_common
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
In crypto/aead.c (ffffffff81708205)
Location: include/crypto/aead.h:321
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_decrypt
  - crypto/aead.c:crypto_aead_encrypt
```
```
In crypto/skcipher.c (ffffffff8170a625)
Location: include/crypto/aead.h:321
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_decrypt
  - crypto/skcipher.c:skcipher_walk_aead_common
```
```
In crypto/seqiv.c (ffffffff8170a755)
Location: include/crypto/aead.h:321
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
  - crypto/seqiv.c:seqiv_aead_encrypt
  - crypto/seqiv.c:seqiv_aead_encrypt_complete2
```
```
In crypto/gcm.c (ffffffff8171774b)
Location: include/crypto/aead.h:321
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_copy_src_to_dst
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_gcm_decrypt
  - crypto/gcm.c:gcm_dec_hash_continue
  - crypto/gcm.c:crypto_gcm_verify
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:gcm_encrypt_continue
  - crypto/gcm.c:gcm_enc_copy_hash
  - crypto/gcm.c:gcm_hash
  - crypto/gcm.c:gcm_hash_assoc_remain_continue
  - crypto/gcm.c:gcm_hash_crypt_continue
  - crypto/gcm.c:gcm_hash_crypt_remain_continue
  - crypto/gcm.c:gcm_hash_len_done
  - crypto/gcm.c:gcm_hash_update
  - crypto/gcm.c:crypto_gcm_init_common
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
In crypto/aead.c (ffffffff81741e95)
Location: include/crypto/aead.h:343
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_decrypt
  - crypto/aead.c:crypto_aead_encrypt
```
```
In crypto/skcipher.c (ffffffff81743e75)
Location: include/crypto/aead.h:343
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_decrypt
  - crypto/skcipher.c:skcipher_walk_aead_common
```
```
In crypto/seqiv.c (ffffffff81743fa5)
Location: include/crypto/aead.h:343
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
  - crypto/seqiv.c:seqiv_aead_encrypt
  - crypto/seqiv.c:seqiv_aead_encrypt_complete2
```
```
In crypto/gcm.c (ffffffff8175313b)
Location: include/crypto/aead.h:343
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_copy_src_to_dst
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_gcm_decrypt
  - crypto/gcm.c:gcm_dec_hash_continue
  - crypto/gcm.c:crypto_gcm_verify
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:gcm_encrypt_continue
  - crypto/gcm.c:gcm_enc_copy_hash
  - crypto/gcm.c:gcm_hash
  - crypto/gcm.c:gcm_hash_assoc_remain_continue
  - crypto/gcm.c:gcm_hash_crypt_continue
  - crypto/gcm.c:gcm_hash_crypt_remain_continue
  - crypto/gcm.c:gcm_hash_len_done
  - crypto/gcm.c:gcm_hash_update
  - crypto/gcm.c:crypto_gcm_init_common
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
In crypto/aead.c (ffffffff81782d75)
Location: include/crypto/aead.h:355
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_decrypt
  - crypto/aead.c:crypto_aead_encrypt
```
```
In crypto/skcipher.c (ffffffff81786255)
Location: include/crypto/aead.h:355
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_decrypt
  - crypto/skcipher.c:skcipher_walk_aead_common
```
```
In crypto/seqiv.c (ffffffff81786565)
Location: include/crypto/aead.h:355
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
  - crypto/seqiv.c:seqiv_aead_encrypt
  - crypto/seqiv.c:seqiv_aead_encrypt_complete2
```
```
In crypto/gcm.c (ffffffff8179500b)
Location: include/crypto/aead.h:355
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_copy_src_to_dst
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_gcm_decrypt
  - crypto/gcm.c:gcm_dec_hash_continue
  - crypto/gcm.c:crypto_gcm_verify
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:gcm_encrypt_continue
  - crypto/gcm.c:gcm_enc_copy_hash
  - crypto/gcm.c:gcm_hash
  - crypto/gcm.c:gcm_hash_init_continue
  - crypto/gcm.c:gcm_hash_assoc_continue
  - crypto/gcm.c:gcm_hash_assoc_remain_continue
  - crypto/gcm.c:gcm_hash_crypt_continue
  - crypto/gcm.c:gcm_hash_crypt_remain_continue
  - crypto/gcm.c:gcm_hash_len_done
  - crypto/gcm.c:crypto_gcm_init_common
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
In crypto/aead.c (ffff8000105bb754)
Location: include/crypto/aead.h:296
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_decrypt
  - crypto/aead.c:crypto_aead_encrypt
```
```
In crypto/skcipher.c (ffff8000105bf8c4)
Location: include/crypto/aead.h:296
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_decrypt
  - crypto/skcipher.c:skcipher_walk_aead_common
```
```
In crypto/seqiv.c (ffff8000105bfa48)
Location: include/crypto/aead.h:296
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
  - crypto/seqiv.c:seqiv_aead_encrypt
  - crypto/seqiv.c:seqiv_aead_encrypt_complete2
```
```
In crypto/gcm.c (ffff8000105cb420)
Location: include/crypto/aead.h:296
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
In crypto/aead.c (c0769984)
Location: include/crypto/aead.h:296
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_decrypt
  - crypto/aead.c:crypto_aead_encrypt
```
```
In crypto/skcipher.c (c076d570)
Location: include/crypto/aead.h:296
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_decrypt
  - crypto/skcipher.c:skcipher_walk_aead_common
```
```
In crypto/seqiv.c (c076d698)
Location: include/crypto/aead.h:296
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
  - crypto/seqiv.c:seqiv_aead_encrypt
  - crypto/seqiv.c:seqiv_aead_encrypt_complete2
```
```
In crypto/gcm.c (c0778f28)
Location: include/crypto/aead.h:296
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
In crypto/aead.c (c0000000007420bc)
Location: include/crypto/aead.h:296
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_decrypt
  - crypto/aead.c:crypto_aead_encrypt
```
```
In crypto/skcipher.c (c000000000747630)
Location: include/crypto/aead.h:296
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_decrypt
  - crypto/skcipher.c:skcipher_walk_aead_common
```
```
In crypto/seqiv.c (c000000000747810)
Location: include/crypto/aead.h:296
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
  - crypto/seqiv.c:seqiv_aead_encrypt
  - crypto/seqiv.c:seqiv_aead_encrypt_complete2
```
```
In crypto/gcm.c (c000000000756438)
Location: include/crypto/aead.h:296
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
In crypto/aead.c (ffffffe00040119a)
Location: include/crypto/aead.h:296
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_decrypt
  - crypto/aead.c:crypto_aead_encrypt
```
```
In crypto/skcipher.c (ffffffe0004049f4)
Location: include/crypto/aead.h:296
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_decrypt
  - crypto/skcipher.c:skcipher_walk_aead_common
```
```
In crypto/seqiv.c (ffffffe000404b24)
Location: include/crypto/aead.h:296
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
  - crypto/seqiv.c:seqiv_aead_encrypt
  - crypto/seqiv.c:seqiv_aead_encrypt_complete2
```
```
In crypto/gcm.c (ffffffe00040f796)
Location: include/crypto/aead.h:296
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
In crypto/aead.c (ffffffff814b99d5)
Location: include/crypto/aead.h:296
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_decrypt
  - crypto/aead.c:crypto_aead_encrypt
```
```
In crypto/skcipher.c (ffffffff814bd365)
Location: include/crypto/aead.h:296
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_decrypt
  - crypto/skcipher.c:skcipher_walk_aead_common
```
```
In crypto/seqiv.c (ffffffff814bd475)
Location: include/crypto/aead.h:296
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
  - crypto/seqiv.c:seqiv_aead_encrypt
  - crypto/seqiv.c:seqiv_aead_encrypt_complete2
```
```
In crypto/gcm.c (ffffffff814c79f3)
Location: include/crypto/aead.h:296
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
In crypto/aead.c (ffffffff814aa3f5)
Location: include/crypto/aead.h:296
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_decrypt
  - crypto/aead.c:crypto_aead_encrypt
```
```
In crypto/skcipher.c (ffffffff814add85)
Location: include/crypto/aead.h:296
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_decrypt
  - crypto/skcipher.c:skcipher_walk_aead_common
```
```
In crypto/seqiv.c (ffffffff814ade95)
Location: include/crypto/aead.h:296
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
  - crypto/seqiv.c:seqiv_aead_encrypt
  - crypto/seqiv.c:seqiv_aead_encrypt_complete2
```
```
In crypto/gcm.c (ffffffff814b8413)
Location: include/crypto/aead.h:296
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
In crypto/aead.c (ffffffff814b5a65)
Location: include/crypto/aead.h:296
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_decrypt
  - crypto/aead.c:crypto_aead_encrypt
```
```
In crypto/skcipher.c (ffffffff814b93f5)
Location: include/crypto/aead.h:296
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_decrypt
  - crypto/skcipher.c:skcipher_walk_aead_common
```
```
In crypto/seqiv.c (ffffffff814b9505)
Location: include/crypto/aead.h:296
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
  - crypto/seqiv.c:seqiv_aead_encrypt
  - crypto/seqiv.c:seqiv_aead_encrypt_complete2
```
```
In crypto/gcm.c (ffffffff814c3a83)
Location: include/crypto/aead.h:296
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
In crypto/aead.c (ffffffff814ce505)
Location: include/crypto/aead.h:296
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_decrypt
  - crypto/aead.c:crypto_aead_encrypt
```
```
In crypto/skcipher.c (ffffffff814d1e95)
Location: include/crypto/aead.h:296
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_decrypt
  - crypto/skcipher.c:skcipher_walk_aead_common
```
```
In crypto/seqiv.c (ffffffff814d1fa5)
Location: include/crypto/aead.h:296
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
  - crypto/seqiv.c:seqiv_aead_encrypt
  - crypto/seqiv.c:seqiv_aead_encrypt_complete2
```
```
In crypto/gcm.c (ffffffff814dc553)
Location: include/crypto/aead.h:296
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
