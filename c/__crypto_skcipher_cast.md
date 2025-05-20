# Function: <code>__crypto_skcipher_cast</code>

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
In crypto/skcipher.c (0)
Location: include/crypto/skcipher.h:180
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
In fs/crypto/crypto.c (0)
Location: include/crypto/skcipher.h:173
Inline: True
```
```
In fs/crypto/fname.c (0)
Location: include/crypto/skcipher.h:173
Inline: True
```
```
In fs/crypto/keyinfo.c (0)
Location: include/crypto/skcipher.h:173
Inline: True
```
```
In fs/ecryptfs/crypto.c (0)
Location: include/crypto/skcipher.h:173
Inline: True
```
```
In fs/ecryptfs/keystore.c (0)
Location: include/crypto/skcipher.h:173
Inline: True
```
```
In security/keys/big_key.c (0)
Location: include/crypto/skcipher.h:173
Inline: True
```
```
In security/keys/encrypted-keys/encrypted.c (0)
Location: include/crypto/skcipher.h:173
Inline: True
```
```
In crypto/skcipher.c (ffffffff813de3d2)
Location: include/crypto/skcipher.h:173
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/skcipher.c:crypto_skcipher_exit_tfm
```
```
In crypto/seqiv.c (0)
Location: include/crypto/skcipher.h:173
Inline: True
```
```
In crypto/cts.c (0)
Location: include/crypto/skcipher.h:173
Inline: True
```
```
In crypto/ctr.c (0)
Location: include/crypto/skcipher.h:173
Inline: True
```
```
In crypto/drbg.c (0)
Location: include/crypto/skcipher.h:173
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
In fs/crypto/crypto.c (0)
Location: include/crypto/skcipher.h:173
Inline: True
```
```
In fs/crypto/fname.c (0)
Location: include/crypto/skcipher.h:173
Inline: True
```
```
In fs/crypto/keyinfo.c (0)
Location: include/crypto/skcipher.h:173
Inline: True
```
```
In fs/ecryptfs/crypto.c (0)
Location: include/crypto/skcipher.h:173
Inline: True
```
```
In fs/ecryptfs/keystore.c (0)
Location: include/crypto/skcipher.h:173
Inline: True
```
```
In security/keys/big_key.c (0)
Location: include/crypto/skcipher.h:173
Inline: True
```
```
In security/keys/encrypted-keys/encrypted.c (0)
Location: include/crypto/skcipher.h:173
Inline: True
```
```
In crypto/skcipher.c (ffffffff813f5dc2)
Location: include/crypto/skcipher.h:173
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/skcipher.c:crypto_skcipher_exit_tfm
```
```
In crypto/seqiv.c (0)
Location: include/crypto/skcipher.h:173
Inline: True
```
```
In crypto/cbc.c (0)
Location: include/crypto/skcipher.h:173
Inline: True
```
```
In crypto/cts.c (0)
Location: include/crypto/skcipher.h:173
Inline: True
```
```
In crypto/xts.c (0)
Location: include/crypto/skcipher.h:173
Inline: True
```
```
In crypto/ctr.c (0)
Location: include/crypto/skcipher.h:173
Inline: True
```
```
In crypto/drbg.c (0)
Location: include/crypto/skcipher.h:173
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
In fs/crypto/crypto.c (0)
Location: include/crypto/skcipher.h:177
Inline: True
```
```
In fs/crypto/fname.c (0)
Location: include/crypto/skcipher.h:177
Inline: True
```
```
In fs/crypto/keyinfo.c (0)
Location: include/crypto/skcipher.h:177
Inline: True
```
```
In fs/ecryptfs/crypto.c (0)
Location: include/crypto/skcipher.h:177
Inline: True
```
```
In fs/ecryptfs/keystore.c (0)
Location: include/crypto/skcipher.h:177
Inline: True
```
```
In security/keys/big_key.c (0)
Location: include/crypto/skcipher.h:177
Inline: True
```
```
In security/keys/encrypted-keys/encrypted.c (0)
Location: include/crypto/skcipher.h:177
Inline: True
```
```
In crypto/skcipher.c (ffffffff81402143)
Location: include/crypto/skcipher.h:177
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/skcipher.c:crypto_skcipher_exit_tfm
```
```
In crypto/seqiv.c (0)
Location: include/crypto/skcipher.h:177
Inline: True
```
```
In crypto/cbc.c (0)
Location: include/crypto/skcipher.h:177
Inline: True
```
```
In crypto/cts.c (0)
Location: include/crypto/skcipher.h:177
Inline: True
```
```
In crypto/xts.c (0)
Location: include/crypto/skcipher.h:177
Inline: True
```
```
In crypto/ctr.c (0)
Location: include/crypto/skcipher.h:177
Inline: True
```
```
In crypto/drbg.c (0)
Location: include/crypto/skcipher.h:177
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
In fs/crypto/crypto.c (0)
Location: include/crypto/skcipher.h:177
Inline: True
```
```
In fs/crypto/fname.c (0)
Location: include/crypto/skcipher.h:177
Inline: True
```
```
In fs/crypto/keyinfo.c (0)
Location: include/crypto/skcipher.h:177
Inline: True
```
```
In fs/ecryptfs/crypto.c (0)
Location: include/crypto/skcipher.h:177
Inline: True
```
```
In fs/ecryptfs/keystore.c (0)
Location: include/crypto/skcipher.h:177
Inline: True
```
```
In security/keys/encrypted-keys/encrypted.c (0)
Location: include/crypto/skcipher.h:177
Inline: True
```
```
In crypto/skcipher.c (ffffffff8142a7b3)
Location: include/crypto/skcipher.h:177
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/skcipher.c:crypto_skcipher_exit_tfm
```
```
In crypto/seqiv.c (0)
Location: include/crypto/skcipher.h:177
Inline: True
```
```
In crypto/cbc.c (0)
Location: include/crypto/skcipher.h:177
Inline: True
```
```
In crypto/cts.c (0)
Location: include/crypto/skcipher.h:177
Inline: True
```
```
In crypto/xts.c (0)
Location: include/crypto/skcipher.h:177
Inline: True
```
```
In crypto/ctr.c (0)
Location: include/crypto/skcipher.h:177
Inline: True
```
```
In crypto/gcm.c (0)
Location: include/crypto/skcipher.h:177
Inline: True
```
```
In crypto/drbg.c (0)
Location: include/crypto/skcipher.h:177
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
In fs/crypto/crypto.c (ffffffff812fa523)
Location: include/crypto/skcipher.h:177
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_do_page_crypto
  - fs/crypto/crypto.c:fscrypt_do_page_crypto
```
```
In fs/crypto/fname.c (ffffffff812fae9d)
Location: include/crypto/skcipher.h:177
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_encrypt
```
```
In fs/crypto/keyinfo.c (ffffffff812fba28)
Location: include/crypto/skcipher.h:177
Inline: True
Inline callers:
  - fs/crypto/keyinfo.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff813b7a8f)
Location: include/crypto/skcipher.h:177
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/keystore.c (ffffffff813bab65)
Location: include/crypto/skcipher.h:177
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff813eff41)
Location: include/crypto/skcipher.h:177
Inline: True
```
```
In crypto/skcipher.c (ffffffff8145d485)
Location: include/crypto/skcipher.h:177
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/skcipher.c:crypto_skcipher_exit_tfm
  - crypto/skcipher.c:skcipher_decrypt_ablkcipher
  - crypto/skcipher.c:skcipher_decrypt_ablkcipher
  - crypto/skcipher.c:skcipher_encrypt_ablkcipher
  - crypto/skcipher.c:skcipher_encrypt_ablkcipher
  - crypto/skcipher.c:skcipher_decrypt_blkcipher
  - crypto/skcipher.c:skcipher_decrypt_blkcipher
  - crypto/skcipher.c:skcipher_encrypt_blkcipher
  - crypto/skcipher.c:skcipher_encrypt_blkcipher
  - crypto/skcipher.c:skcipher_walk_skcipher
```
```
In crypto/seqiv.c (ffffffff8145e740)
Location: include/crypto/skcipher.h:177
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/cbc.c (ffffffff81468b27)
Location: include/crypto/skcipher.h:177
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_decrypt
```
```
In crypto/cts.c (ffffffff814696cb)
Location: include/crypto/skcipher.h:177
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:cts_cbc_encrypt
  - crypto/cts.c:cts_cbc_encrypt
```
```
In crypto/xts.c (ffffffff8146a3a3)
Location: include/crypto/skcipher.h:177
Inline: True
Inline callers:
  - crypto/xts.c:do_decrypt
  - crypto/xts.c:do_encrypt
  - crypto/xts.c:init_crypt
```
```
In crypto/ctr.c (ffffffff8146a819)
Location: include/crypto/skcipher.h:177
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_crypt
  - crypto/ctr.c:crypto_rfc3686_crypt
```
```
In crypto/gcm.c (ffffffff8146b349)
Location: include/crypto/skcipher.h:177
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:gcm_dec_hash_continue
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (ffffffff8146fd68)
Location: include/crypto/skcipher.h:177
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
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
In fs/crypto/crypto.c (ffffffff8130f8d6)
Location: include/crypto/skcipher.h:176
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_do_page_crypto
  - fs/crypto/crypto.c:fscrypt_do_page_crypto
```
```
In fs/crypto/fname.c (ffffffff81310254)
Location: include/crypto/skcipher.h:176
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_encrypt
```
```
In fs/crypto/keyinfo.c (ffffffff81310f85)
Location: include/crypto/skcipher.h:176
Inline: True
Inline callers:
  - fs/crypto/keyinfo.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff813d0f58)
Location: include/crypto/skcipher.h:176
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/keystore.c (ffffffff813d4137)
Location: include/crypto/skcipher.h:176
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff8140b220)
Location: include/crypto/skcipher.h:176
Inline: True
```
```
In crypto/skcipher.c (ffffffff8147ad15)
Location: include/crypto/skcipher.h:176
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/skcipher.c:crypto_skcipher_exit_tfm
  - crypto/skcipher.c:skcipher_decrypt_ablkcipher
  - crypto/skcipher.c:skcipher_decrypt_ablkcipher
  - crypto/skcipher.c:skcipher_encrypt_ablkcipher
  - crypto/skcipher.c:skcipher_encrypt_ablkcipher
  - crypto/skcipher.c:skcipher_decrypt_blkcipher
  - crypto/skcipher.c:skcipher_decrypt_blkcipher
  - crypto/skcipher.c:skcipher_encrypt_blkcipher
  - crypto/skcipher.c:skcipher_encrypt_blkcipher
  - crypto/skcipher.c:skcipher_walk_skcipher
```
```
In crypto/seqiv.c (ffffffff8147c029)
Location: include/crypto/skcipher.h:176
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/cbc.c (ffffffff814867a9)
Location: include/crypto/skcipher.h:176
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_decrypt
```
```
In crypto/cts.c (ffffffff814873ff)
Location: include/crypto/skcipher.h:176
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:cts_cbc_encrypt
  - crypto/cts.c:cts_cbc_encrypt
```
```
In crypto/xts.c (ffffffff81487622)
Location: include/crypto/skcipher.h:176
Inline: True
Inline callers:
  - crypto/xts.c:xor_tweak
```
```
In crypto/ctr.c (ffffffff81488084)
Location: include/crypto/skcipher.h:176
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_crypt
  - crypto/ctr.c:crypto_rfc3686_crypt
```
```
In crypto/gcm.c (ffffffff814895c7)
Location: include/crypto/skcipher.h:176
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_copy_src_to_dst
  - crypto/gcm.c:gcm_dec_hash_continue
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (ffffffff814900f6)
Location: include/crypto/skcipher.h:176
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
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
In security/keys/encrypted-keys/encrypted.c (ffffffff81438011)
Location: include/crypto/skcipher.h:171
Inline: True
```
```
In crypto/skcipher.c (ffffffff814a8d55)
Location: include/crypto/skcipher.h:171
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/skcipher.c:crypto_skcipher_exit_tfm
  - crypto/skcipher.c:crypto_skcipher_decrypt
  - crypto/skcipher.c:crypto_skcipher_encrypt
  - crypto/skcipher.c:skcipher_decrypt_ablkcipher
  - crypto/skcipher.c:skcipher_decrypt_ablkcipher
  - crypto/skcipher.c:skcipher_encrypt_ablkcipher
  - crypto/skcipher.c:skcipher_encrypt_ablkcipher
  - crypto/skcipher.c:skcipher_decrypt_blkcipher
  - crypto/skcipher.c:skcipher_decrypt_blkcipher
  - crypto/skcipher.c:skcipher_encrypt_blkcipher
  - crypto/skcipher.c:skcipher_encrypt_blkcipher
  - crypto/skcipher.c:skcipher_walk_skcipher
```
```
In crypto/ecb.c (ffffffff814b4405)
Location: include/crypto/skcipher.h:171
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_decrypt
  - crypto/ecb.c:crypto_ecb_encrypt
```
```
In crypto/cbc.c (ffffffff814b4619)
Location: include/crypto/skcipher.h:171
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_decrypt
```
```
In crypto/cts.c (ffffffff814b5132)
Location: include/crypto/skcipher.h:171
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:cts_cbc_encrypt
```
```
In crypto/xts.c (ffffffff814b5315)
Location: include/crypto/skcipher.h:171
Inline: True
Inline callers:
  - crypto/xts.c:xor_tweak
```
```
In crypto/ctr.c (ffffffff814b5b0a)
Location: include/crypto/skcipher.h:171
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_crypt
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
In security/keys/encrypted-keys/encrypted.c (ffffffff81451dd1)
Location: include/crypto/skcipher.h:171
Inline: True
```
```
In crypto/skcipher.c (ffffffff814c39b5)
Location: include/crypto/skcipher.h:171
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/skcipher.c:crypto_skcipher_exit_tfm
  - crypto/skcipher.c:crypto_skcipher_decrypt
  - crypto/skcipher.c:crypto_skcipher_encrypt
  - crypto/skcipher.c:skcipher_decrypt_ablkcipher
  - crypto/skcipher.c:skcipher_decrypt_ablkcipher
  - crypto/skcipher.c:skcipher_encrypt_ablkcipher
  - crypto/skcipher.c:skcipher_encrypt_ablkcipher
  - crypto/skcipher.c:skcipher_decrypt_blkcipher
  - crypto/skcipher.c:skcipher_decrypt_blkcipher
  - crypto/skcipher.c:skcipher_encrypt_blkcipher
  - crypto/skcipher.c:skcipher_encrypt_blkcipher
  - crypto/skcipher.c:skcipher_walk_skcipher
```
```
In crypto/ecb.c (ffffffff814cd175)
Location: include/crypto/skcipher.h:171
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_decrypt
  - crypto/ecb.c:crypto_ecb_encrypt
```
```
In crypto/cbc.c (ffffffff814cd389)
Location: include/crypto/skcipher.h:171
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_decrypt
```
```
In crypto/cts.c (ffffffff814cdec2)
Location: include/crypto/skcipher.h:171
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:cts_cbc_encrypt
```
```
In crypto/xts.c (ffffffff814ce07b)
Location: include/crypto/skcipher.h:171
Inline: True
Inline callers:
  - crypto/xts.c:init_crypt
  - crypto/xts.c:cts_final
  - crypto/xts.c:xor_tweak
```
```
In crypto/ctr.c (ffffffff814ced0a)
Location: include/crypto/skcipher.h:171
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_crypt
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
In security/keys/encrypted-keys/encrypted.c (ffffffff814a4b1b)
Location: include/crypto/skcipher.h:164
Inline: True
```
```
In crypto/skcipher.c (ffffffff815225b5)
Location: include/crypto/skcipher.h:164
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/skcipher.c:crypto_skcipher_exit_tfm
  - crypto/skcipher.c:crypto_skcipher_decrypt
  - crypto/skcipher.c:crypto_skcipher_encrypt
  - crypto/skcipher.c:skcipher_walk_async
  - crypto/skcipher.c:skcipher_walk_virt
```
```
In crypto/ecb.c (ffffffff8152c615)
Location: include/crypto/skcipher.h:164
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_decrypt
  - crypto/ecb.c:crypto_ecb_encrypt
```
```
In crypto/cbc.c (ffffffff8152c958)
Location: include/crypto/skcipher.h:164
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_decrypt
```
```
In crypto/cts.c (ffffffff8152d272)
Location: include/crypto/skcipher.h:164
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:cts_cbc_encrypt
```
```
In crypto/xts.c (ffffffff8152d8bb)
Location: include/crypto/skcipher.h:164
Inline: True
Inline callers:
  - crypto/xts.c:decrypt
  - crypto/xts.c:encrypt
  - crypto/xts.c:cts_final
  - crypto/xts.c:xor_tweak
```
```
In crypto/ctr.c (ffffffff8152dfda)
Location: include/crypto/skcipher.h:164
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
In security/keys/encrypted-keys/encrypted.c (ffffffff814c231b)
Location: include/crypto/skcipher.h:164
Inline: True
```
```
In crypto/skcipher.c (ffffffff8153f495)
Location: include/crypto/skcipher.h:164
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/skcipher.c:crypto_skcipher_exit_tfm
  - crypto/skcipher.c:crypto_skcipher_decrypt
  - crypto/skcipher.c:crypto_skcipher_encrypt
  - crypto/skcipher.c:skcipher_walk_async
  - crypto/skcipher.c:skcipher_walk_virt
```
```
In crypto/ecb.c (ffffffff81549605)
Location: include/crypto/skcipher.h:164
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_decrypt
  - crypto/ecb.c:crypto_ecb_encrypt
```
```
In crypto/cbc.c (ffffffff8154979d)
Location: include/crypto/skcipher.h:164
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cbc.c:crypto_cbc_encrypt
```
```
In crypto/cts.c (ffffffff8154a2e2)
Location: include/crypto/skcipher.h:164
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:cts_cbc_encrypt
```
```
In crypto/xts.c (ffffffff8154a7eb)
Location: include/crypto/skcipher.h:164
Inline: True
Inline callers:
  - crypto/xts.c:xts_decrypt
  - crypto/xts.c:xts_encrypt
  - crypto/xts.c:xts_cts_final
  - crypto/xts.c:xts_xor_tweak
```
```
In crypto/ctr.c (ffffffff8154affa)
Location: include/crypto/skcipher.h:164
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
In security/keys/encrypted-keys/encrypted.c (ffffffff814c8938)
Location: include/crypto/skcipher.h:164
Inline: True
```
```
In crypto/skcipher.c (ffffffff81547af5)
Location: include/crypto/skcipher.h:164
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/skcipher.c:crypto_skcipher_exit_tfm
  - crypto/skcipher.c:crypto_skcipher_decrypt
  - crypto/skcipher.c:crypto_skcipher_encrypt
  - crypto/skcipher.c:skcipher_walk_async
  - crypto/skcipher.c:skcipher_walk_virt
```
```
In crypto/ecb.c (ffffffff81551cf5)
Location: include/crypto/skcipher.h:164
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_decrypt
  - crypto/ecb.c:crypto_ecb_encrypt
```
```
In crypto/cbc.c (ffffffff81552010)
Location: include/crypto/skcipher.h:164
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cbc.c:crypto_cbc_encrypt
```
```
In crypto/cts.c (ffffffff81552912)
Location: include/crypto/skcipher.h:164
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:cts_cbc_encrypt
```
```
In crypto/xts.c (ffffffff81552e0b)
Location: include/crypto/skcipher.h:164
Inline: True
Inline callers:
  - crypto/xts.c:xts_decrypt
  - crypto/xts.c:xts_encrypt
  - crypto/xts.c:xts_cts_final
  - crypto/xts.c:xts_xor_tweak
```
```
In crypto/ctr.c (ffffffff8155361a)
Location: include/crypto/skcipher.h:164
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
In security/keys/encrypted-keys/encrypted.c (ffffffff81521402)
Location: include/crypto/skcipher.h:164
Inline: True
```
```
In crypto/skcipher.c (ffffffff815a82d5)
Location: include/crypto/skcipher.h:164
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/skcipher.c:crypto_skcipher_exit_tfm
  - crypto/skcipher.c:crypto_skcipher_decrypt
  - crypto/skcipher.c:crypto_skcipher_encrypt
  - crypto/skcipher.c:skcipher_walk_async
  - crypto/skcipher.c:skcipher_walk_virt
```
```
In crypto/ecb.c (ffffffff815b2cf5)
Location: include/crypto/skcipher.h:164
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_decrypt
  - crypto/ecb.c:crypto_ecb_encrypt
```
```
In crypto/cbc.c (ffffffff815b3010)
Location: include/crypto/skcipher.h:164
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cbc.c:crypto_cbc_encrypt
```
```
In crypto/cts.c (ffffffff815b3970)
Location: include/crypto/skcipher.h:164
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:cts_cbc_encrypt
```
```
In crypto/xts.c (ffffffff815b3e3b)
Location: include/crypto/skcipher.h:164
Inline: True
Inline callers:
  - crypto/xts.c:xts_decrypt
  - crypto/xts.c:xts_encrypt
  - crypto/xts.c:xts_cts_final
  - crypto/xts.c:xts_xor_tweak
```
```
In crypto/ctr.c (ffffffff815b464a)
Location: include/crypto/skcipher.h:164
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
In security/keys/encrypted-keys/encrypted.c (ffffffff815b4cb7)
Location: include/crypto/skcipher.h:168
Inline: True
```
```
In crypto/skcipher.c (ffffffff8164ffe5)
Location: include/crypto/skcipher.h:168
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/skcipher.c:crypto_skcipher_exit_tfm
```
```
In crypto/ecb.c (0)
Location: include/crypto/skcipher.h:168
Inline: True
```
```
In crypto/cbc.c (ffffffff8165bcf6)
Location: include/crypto/skcipher.h:168
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_decrypt
```
```
In crypto/cts.c (0)
Location: include/crypto/skcipher.h:168
Inline: True
```
```
In crypto/xts.c (0)
Location: include/crypto/skcipher.h:168
Inline: True
```
```
In crypto/ctr.c (0)
Location: include/crypto/skcipher.h:168
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
In security/keys/encrypted-keys/encrypted.c (ffffffff8165fc97)
Location: include/crypto/skcipher.h:168
Inline: True
```
```
In crypto/skcipher.c (ffffffff81709735)
Location: include/crypto/skcipher.h:168
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/skcipher.c:crypto_skcipher_exit_tfm
```
```
In crypto/ecb.c (0)
Location: include/crypto/skcipher.h:168
Inline: True
```
```
In crypto/cbc.c (0)
Location: include/crypto/skcipher.h:168
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cbc.c:crypto_cbc_encrypt
```
```
In crypto/cts.c (0)
Location: include/crypto/skcipher.h:168
Inline: True
```
```
In crypto/xts.c (0)
Location: include/crypto/skcipher.h:168
Inline: True
```
```
In crypto/ctr.c (0)
Location: include/crypto/skcipher.h:168
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
In security/keys/encrypted-keys/encrypted.c (ffffffff816985fd)
Location: include/crypto/skcipher.h:190
Inline: True
```
```
In crypto/skcipher.c (ffffffff81743055)
Location: include/crypto/skcipher.h:190
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/skcipher.c:crypto_skcipher_exit_tfm
```
```
In crypto/ecb.c (0)
Location: include/crypto/skcipher.h:190
Inline: True
```
```
In crypto/cbc.c (0)
Location: include/crypto/skcipher.h:190
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cbc.c:crypto_cbc_encrypt
```
```
In crypto/cts.c (0)
Location: include/crypto/skcipher.h:190
Inline: True
```
```
In crypto/xts.c (0)
Location: include/crypto/skcipher.h:190
Inline: True
```
```
In crypto/ctr.c (0)
Location: include/crypto/skcipher.h:190
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
In security/keys/encrypted-keys/encrypted.c (ffffffff816d4c7d)
Location: include/crypto/skcipher.h:283
Inline: True
```
```
In crypto/lskcipher.c (0)
Location: include/crypto/skcipher.h:283
Inline: True
```
```
In crypto/skcipher.c (ffffffff817853c5)
Location: include/crypto/skcipher.h:283
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/skcipher.c:crypto_skcipher_exit_tfm
```
```
In crypto/cts.c (0)
Location: include/crypto/skcipher.h:283
Inline: True
```
```
In crypto/xts.c (0)
Location: include/crypto/skcipher.h:283
Inline: True
```
```
In crypto/ctr.c (0)
Location: include/crypto/skcipher.h:283
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
In security/keys/encrypted-keys/encrypted.c (ffff80001053d5c0)
Location: include/crypto/skcipher.h:171
Inline: True
```
```
In crypto/skcipher.c (ffff8000105be2f0)
Location: include/crypto/skcipher.h:171
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/skcipher.c:crypto_skcipher_exit_tfm
  - crypto/skcipher.c:crypto_skcipher_decrypt
  - crypto/skcipher.c:crypto_skcipher_encrypt
  - crypto/skcipher.c:skcipher_decrypt_ablkcipher
  - crypto/skcipher.c:skcipher_decrypt_ablkcipher
  - crypto/skcipher.c:skcipher_encrypt_ablkcipher
  - crypto/skcipher.c:skcipher_encrypt_ablkcipher
  - crypto/skcipher.c:skcipher_decrypt_blkcipher
  - crypto/skcipher.c:skcipher_decrypt_blkcipher
  - crypto/skcipher.c:skcipher_encrypt_blkcipher
  - crypto/skcipher.c:skcipher_encrypt_blkcipher
  - crypto/skcipher.c:skcipher_walk_skcipher
```
```
In crypto/ecb.c (ffff8000105c8fc8)
Location: include/crypto/skcipher.h:171
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_decrypt
  - crypto/ecb.c:crypto_ecb_encrypt
```
```
In crypto/cbc.c (ffff8000105c923c)
Location: include/crypto/skcipher.h:171
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_decrypt
```
```
In crypto/cts.c (ffff8000105c9de0)
Location: include/crypto/skcipher.h:171
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:cts_cbc_encrypt
```
```
In crypto/xts.c (ffff8000105c9fb4)
Location: include/crypto/skcipher.h:171
Inline: True
Inline callers:
  - crypto/xts.c:init_crypt
  - crypto/xts.c:cts_final
  - crypto/xts.c:xor_tweak
```
```
In crypto/ctr.c (ffff8000105cac64)
Location: include/crypto/skcipher.h:171
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_crypt
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
In security/keys/encrypted-keys/encrypted.c (c06f2fdc)
Location: include/crypto/skcipher.h:171
Inline: True
```
```
In crypto/skcipher.c (c076c084)
Location: include/crypto/skcipher.h:171
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/skcipher.c:crypto_skcipher_exit_tfm
  - crypto/skcipher.c:crypto_skcipher_decrypt
  - crypto/skcipher.c:crypto_skcipher_encrypt
  - crypto/skcipher.c:skcipher_decrypt_ablkcipher
  - crypto/skcipher.c:skcipher_decrypt_ablkcipher
  - crypto/skcipher.c:skcipher_encrypt_ablkcipher
  - crypto/skcipher.c:skcipher_encrypt_ablkcipher
  - crypto/skcipher.c:skcipher_decrypt_blkcipher
  - crypto/skcipher.c:skcipher_decrypt_blkcipher
  - crypto/skcipher.c:skcipher_encrypt_blkcipher
  - crypto/skcipher.c:skcipher_encrypt_blkcipher
  - crypto/skcipher.c:skcipher_walk_skcipher
```
```
In crypto/ecb.c (c0776c68)
Location: include/crypto/skcipher.h:171
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_decrypt
  - crypto/ecb.c:crypto_ecb_encrypt
```
```
In crypto/cbc.c (c0776fb4)
Location: include/crypto/skcipher.h:171
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cbc.c:crypto_cbc_encrypt
```
```
In crypto/cts.c (c077790c)
Location: include/crypto/skcipher.h:171
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:cts_cbc_encrypt
```
```
In crypto/xts.c (c0777ab4)
Location: include/crypto/skcipher.h:171
Inline: True
Inline callers:
  - crypto/xts.c:init_crypt
  - crypto/xts.c:cts_final
  - crypto/xts.c:xor_tweak
```
```
In crypto/ctr.c (c077881c)
Location: include/crypto/skcipher.h:171
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_crypt
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
In security/keys/encrypted-keys/encrypted.c (c00000000068caf8)
Location: include/crypto/skcipher.h:171
Inline: True
```
```
In crypto/skcipher.c (c0000000007459dc)
Location: include/crypto/skcipher.h:171
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/skcipher.c:crypto_skcipher_exit_tfm
  - crypto/skcipher.c:crypto_skcipher_decrypt
  - crypto/skcipher.c:crypto_skcipher_encrypt
  - crypto/skcipher.c:skcipher_decrypt_ablkcipher
  - crypto/skcipher.c:skcipher_decrypt_ablkcipher
  - crypto/skcipher.c:skcipher_encrypt_ablkcipher
  - crypto/skcipher.c:skcipher_encrypt_ablkcipher
  - crypto/skcipher.c:skcipher_decrypt_blkcipher
  - crypto/skcipher.c:skcipher_decrypt_blkcipher
  - crypto/skcipher.c:skcipher_encrypt_blkcipher
  - crypto/skcipher.c:skcipher_encrypt_blkcipher
  - crypto/skcipher.c:skcipher_walk_skcipher
```
```
In crypto/ecb.c (c000000000753480)
Location: include/crypto/skcipher.h:171
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_decrypt
  - crypto/ecb.c:crypto_ecb_encrypt
```
```
In crypto/cbc.c (c000000000753774)
Location: include/crypto/skcipher.h:171
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_decrypt
```
```
In crypto/cts.c (c0000000007546cc)
Location: include/crypto/skcipher.h:171
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:cts_cbc_encrypt
```
```
In crypto/xts.c (c000000000754948)
Location: include/crypto/skcipher.h:171
Inline: True
Inline callers:
  - crypto/xts.c:init_crypt
  - crypto/xts.c:cts_final
  - crypto/xts.c:xor_tweak
```
```
In crypto/ctr.c (c000000000755a64)
Location: include/crypto/skcipher.h:171
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_crypt
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
In security/keys/encrypted-keys/encrypted.c (ffffffe00039aa1c)
Location: include/crypto/skcipher.h:171
Inline: True
```
```
In crypto/skcipher.c (ffffffe000403758)
Location: include/crypto/skcipher.h:171
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/skcipher.c:crypto_skcipher_exit_tfm
  - crypto/skcipher.c:crypto_skcipher_decrypt
  - crypto/skcipher.c:crypto_skcipher_encrypt
  - crypto/skcipher.c:skcipher_decrypt_ablkcipher
  - crypto/skcipher.c:skcipher_decrypt_ablkcipher
  - crypto/skcipher.c:skcipher_encrypt_ablkcipher
  - crypto/skcipher.c:skcipher_encrypt_ablkcipher
  - crypto/skcipher.c:skcipher_decrypt_blkcipher
  - crypto/skcipher.c:skcipher_decrypt_blkcipher
  - crypto/skcipher.c:skcipher_encrypt_blkcipher
  - crypto/skcipher.c:skcipher_encrypt_blkcipher
  - crypto/skcipher.c:skcipher_walk_skcipher
```
```
In crypto/ecb.c (ffffffe00040d956)
Location: include/crypto/skcipher.h:171
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_decrypt
  - crypto/ecb.c:crypto_ecb_encrypt
```
```
In crypto/cbc.c (ffffffe00040db1e)
Location: include/crypto/skcipher.h:171
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_decrypt
```
```
In crypto/cts.c (ffffffe00040df78)
Location: include/crypto/skcipher.h:171
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:cts_cbc_encrypt
```
```
In crypto/xts.c (ffffffe00040e5f0)
Location: include/crypto/skcipher.h:171
Inline: True
Inline callers:
  - crypto/xts.c:init_crypt
  - crypto/xts.c:cts_final
  - crypto/xts.c:xor_tweak
```
```
In crypto/ctr.c (ffffffe00040f11e)
Location: include/crypto/skcipher.h:171
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_crypt
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
In security/keys/encrypted-keys/encrypted.c (ffffffff8144a3b1)
Location: include/crypto/skcipher.h:171
Inline: True
```
```
In crypto/skcipher.c (ffffffff814bbf95)
Location: include/crypto/skcipher.h:171
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/skcipher.c:crypto_skcipher_exit_tfm
  - crypto/skcipher.c:crypto_skcipher_decrypt
  - crypto/skcipher.c:crypto_skcipher_encrypt
  - crypto/skcipher.c:skcipher_decrypt_ablkcipher
  - crypto/skcipher.c:skcipher_decrypt_ablkcipher
  - crypto/skcipher.c:skcipher_encrypt_ablkcipher
  - crypto/skcipher.c:skcipher_encrypt_ablkcipher
  - crypto/skcipher.c:skcipher_decrypt_blkcipher
  - crypto/skcipher.c:skcipher_decrypt_blkcipher
  - crypto/skcipher.c:skcipher_encrypt_blkcipher
  - crypto/skcipher.c:skcipher_encrypt_blkcipher
  - crypto/skcipher.c:skcipher_walk_skcipher
```
```
In crypto/ecb.c (ffffffff814c5755)
Location: include/crypto/skcipher.h:171
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_decrypt
  - crypto/ecb.c:crypto_ecb_encrypt
```
```
In crypto/cbc.c (ffffffff814c5969)
Location: include/crypto/skcipher.h:171
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_decrypt
```
```
In crypto/cts.c (ffffffff814c64a2)
Location: include/crypto/skcipher.h:171
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:cts_cbc_encrypt
```
```
In crypto/xts.c (ffffffff814c665b)
Location: include/crypto/skcipher.h:171
Inline: True
Inline callers:
  - crypto/xts.c:init_crypt
  - crypto/xts.c:cts_final
  - crypto/xts.c:xor_tweak
```
```
In crypto/ctr.c (ffffffff814c72ea)
Location: include/crypto/skcipher.h:171
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_crypt
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
In security/keys/encrypted-keys/encrypted.c (ffffffff8143ae01)
Location: include/crypto/skcipher.h:171
Inline: True
```
```
In crypto/skcipher.c (ffffffff814ac9b5)
Location: include/crypto/skcipher.h:171
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/skcipher.c:crypto_skcipher_exit_tfm
  - crypto/skcipher.c:crypto_skcipher_decrypt
  - crypto/skcipher.c:crypto_skcipher_encrypt
  - crypto/skcipher.c:skcipher_decrypt_ablkcipher
  - crypto/skcipher.c:skcipher_decrypt_ablkcipher
  - crypto/skcipher.c:skcipher_encrypt_ablkcipher
  - crypto/skcipher.c:skcipher_encrypt_ablkcipher
  - crypto/skcipher.c:skcipher_decrypt_blkcipher
  - crypto/skcipher.c:skcipher_decrypt_blkcipher
  - crypto/skcipher.c:skcipher_encrypt_blkcipher
  - crypto/skcipher.c:skcipher_encrypt_blkcipher
  - crypto/skcipher.c:skcipher_walk_skcipher
```
```
In crypto/ecb.c (ffffffff814b6175)
Location: include/crypto/skcipher.h:171
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_decrypt
  - crypto/ecb.c:crypto_ecb_encrypt
```
```
In crypto/cbc.c (ffffffff814b6389)
Location: include/crypto/skcipher.h:171
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_decrypt
```
```
In crypto/cts.c (ffffffff814b6ec2)
Location: include/crypto/skcipher.h:171
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:cts_cbc_encrypt
```
```
In crypto/xts.c (ffffffff814b707b)
Location: include/crypto/skcipher.h:171
Inline: True
Inline callers:
  - crypto/xts.c:init_crypt
  - crypto/xts.c:cts_final
  - crypto/xts.c:xor_tweak
```
```
In crypto/ctr.c (ffffffff814b7d0a)
Location: include/crypto/skcipher.h:171
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_crypt
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
In security/keys/encrypted-keys/encrypted.c (ffffffff81446451)
Location: include/crypto/skcipher.h:171
Inline: True
```
```
In crypto/skcipher.c (ffffffff814b8025)
Location: include/crypto/skcipher.h:171
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/skcipher.c:crypto_skcipher_exit_tfm
  - crypto/skcipher.c:crypto_skcipher_decrypt
  - crypto/skcipher.c:crypto_skcipher_encrypt
  - crypto/skcipher.c:skcipher_decrypt_ablkcipher
  - crypto/skcipher.c:skcipher_decrypt_ablkcipher
  - crypto/skcipher.c:skcipher_encrypt_ablkcipher
  - crypto/skcipher.c:skcipher_encrypt_ablkcipher
  - crypto/skcipher.c:skcipher_decrypt_blkcipher
  - crypto/skcipher.c:skcipher_decrypt_blkcipher
  - crypto/skcipher.c:skcipher_encrypt_blkcipher
  - crypto/skcipher.c:skcipher_encrypt_blkcipher
  - crypto/skcipher.c:skcipher_walk_skcipher
```
```
In crypto/ecb.c (ffffffff814c17e5)
Location: include/crypto/skcipher.h:171
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_decrypt
  - crypto/ecb.c:crypto_ecb_encrypt
```
```
In crypto/cbc.c (ffffffff814c19f9)
Location: include/crypto/skcipher.h:171
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_decrypt
```
```
In crypto/cts.c (ffffffff814c2532)
Location: include/crypto/skcipher.h:171
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:cts_cbc_encrypt
```
```
In crypto/xts.c (ffffffff814c26eb)
Location: include/crypto/skcipher.h:171
Inline: True
Inline callers:
  - crypto/xts.c:init_crypt
  - crypto/xts.c:cts_final
  - crypto/xts.c:xor_tweak
```
```
In crypto/ctr.c (ffffffff814c337a)
Location: include/crypto/skcipher.h:171
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_crypt
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
In security/keys/encrypted-keys/encrypted.c (ffffffff8145d781)
Location: include/crypto/skcipher.h:171
Inline: True
```
```
In crypto/skcipher.c (ffffffff814d0b05)
Location: include/crypto/skcipher.h:171
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/skcipher.c:crypto_skcipher_exit_tfm
  - crypto/skcipher.c:crypto_skcipher_decrypt
  - crypto/skcipher.c:crypto_skcipher_encrypt
  - crypto/skcipher.c:skcipher_decrypt_ablkcipher
  - crypto/skcipher.c:skcipher_decrypt_ablkcipher
  - crypto/skcipher.c:skcipher_encrypt_ablkcipher
  - crypto/skcipher.c:skcipher_encrypt_ablkcipher
  - crypto/skcipher.c:skcipher_decrypt_blkcipher
  - crypto/skcipher.c:skcipher_decrypt_blkcipher
  - crypto/skcipher.c:skcipher_encrypt_blkcipher
  - crypto/skcipher.c:skcipher_encrypt_blkcipher
  - crypto/skcipher.c:skcipher_walk_skcipher
```
```
In crypto/ecb.c (ffffffff814da2b5)
Location: include/crypto/skcipher.h:171
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_decrypt
  - crypto/ecb.c:crypto_ecb_encrypt
```
```
In crypto/cbc.c (ffffffff814da4c9)
Location: include/crypto/skcipher.h:171
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_decrypt
```
```
In crypto/cts.c (ffffffff814db002)
Location: include/crypto/skcipher.h:171
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:cts_cbc_encrypt
```
```
In crypto/xts.c (ffffffff814db1bb)
Location: include/crypto/skcipher.h:171
Inline: True
Inline callers:
  - crypto/xts.c:init_crypt
  - crypto/xts.c:cts_final
  - crypto/xts.c:xor_tweak
```
```
In crypto/ctr.c (ffffffff814dbe4a)
Location: include/crypto/skcipher.h:171
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_crypt
  - crypto/ctr.c:crypto_ctr_crypt
```
</details>
</li>
</ul>

## Differences
