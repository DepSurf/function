# Function: <code>crypto_skcipher_reqtfm</code>

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
In crypto/skcipher.c (ffffffff813a1a7e)
Location: include/crypto/skcipher.h:324
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_encrypt_blkcipher
  - crypto/skcipher.c:skcipher_decrypt_blkcipher
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
In fs/crypto/crypto.c (0)
Location: include/crypto/skcipher.h:390
Inline: True
```
```
In fs/crypto/fname.c (0)
Location: include/crypto/skcipher.h:390
Inline: True
```
```
In fs/crypto/keyinfo.c (0)
Location: include/crypto/skcipher.h:390
Inline: True
```
```
In fs/ecryptfs/crypto.c (0)
Location: include/crypto/skcipher.h:390
Inline: True
```
```
In fs/ecryptfs/keystore.c (0)
Location: include/crypto/skcipher.h:390
Inline: True
```
```
In security/keys/big_key.c (0)
Location: include/crypto/skcipher.h:390
Inline: True
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff8136e6b5)
Location: include/crypto/skcipher.h:390
Inline: True
```
```
In crypto/skcipher.c (ffffffff813de096)
Location: include/crypto/skcipher.h:390
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_decrypt_ablkcipher
  - crypto/skcipher.c:skcipher_encrypt_ablkcipher
  - crypto/skcipher.c:skcipher_decrypt_blkcipher
  - crypto/skcipher.c:skcipher_encrypt_blkcipher
```
```
In crypto/seqiv.c (0)
Location: include/crypto/skcipher.h:390
Inline: True
```
```
In crypto/cts.c (ffffffff813e7970)
Location: include/crypto/skcipher.h:390
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:crypto_cts_encrypt
```
```
In crypto/ctr.c (ffffffff813e8886)
Location: include/crypto/skcipher.h:390
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_crypt
```
```
In crypto/drbg.c (0)
Location: include/crypto/skcipher.h:390
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
Location: include/crypto/skcipher.h:390
Inline: True
```
```
In fs/crypto/fname.c (0)
Location: include/crypto/skcipher.h:390
Inline: True
```
```
In fs/crypto/keyinfo.c (0)
Location: include/crypto/skcipher.h:390
Inline: True
```
```
In fs/ecryptfs/crypto.c (0)
Location: include/crypto/skcipher.h:390
Inline: True
```
```
In fs/ecryptfs/keystore.c (0)
Location: include/crypto/skcipher.h:390
Inline: True
```
```
In security/keys/big_key.c (0)
Location: include/crypto/skcipher.h:390
Inline: True
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff813852d6)
Location: include/crypto/skcipher.h:390
Inline: True
```
```
In crypto/skcipher.c (ffffffff813f5966)
Location: include/crypto/skcipher.h:390
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_decrypt_ablkcipher
  - crypto/skcipher.c:skcipher_encrypt_ablkcipher
  - crypto/skcipher.c:skcipher_decrypt_blkcipher
  - crypto/skcipher.c:skcipher_encrypt_blkcipher
  - crypto/skcipher.c:skcipher_walk_skcipher
```
```
In crypto/seqiv.c (0)
Location: include/crypto/skcipher.h:390
Inline: True
```
```
In crypto/cbc.c (ffffffff8140037d)
Location: include/crypto/skcipher.h:390
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_decrypt
```
```
In crypto/cts.c (ffffffff814007a0)
Location: include/crypto/skcipher.h:390
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:crypto_cts_encrypt
```
```
In crypto/xts.c (ffffffff8140111c)
Location: include/crypto/skcipher.h:390
Inline: True
Inline callers:
  - crypto/xts.c:init_crypt
```
```
In crypto/ctr.c (ffffffff81401e96)
Location: include/crypto/skcipher.h:390
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_crypt
```
```
In crypto/drbg.c (0)
Location: include/crypto/skcipher.h:390
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
Location: include/crypto/skcipher.h:424
Inline: True
```
```
In fs/crypto/fname.c (0)
Location: include/crypto/skcipher.h:424
Inline: True
```
```
In fs/crypto/keyinfo.c (0)
Location: include/crypto/skcipher.h:424
Inline: True
```
```
In fs/ecryptfs/crypto.c (0)
Location: include/crypto/skcipher.h:424
Inline: True
```
```
In fs/ecryptfs/keystore.c (0)
Location: include/crypto/skcipher.h:424
Inline: True
```
```
In security/keys/big_key.c (0)
Location: include/crypto/skcipher.h:424
Inline: True
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff813999d2)
Location: include/crypto/skcipher.h:424
Inline: True
```
```
In crypto/skcipher.c (ffffffff81401c06)
Location: include/crypto/skcipher.h:424
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_decrypt_ablkcipher
  - crypto/skcipher.c:skcipher_encrypt_ablkcipher
  - crypto/skcipher.c:skcipher_decrypt_blkcipher
  - crypto/skcipher.c:skcipher_encrypt_blkcipher
  - crypto/skcipher.c:skcipher_walk_skcipher
```
```
In crypto/seqiv.c (0)
Location: include/crypto/skcipher.h:424
Inline: True
```
```
In crypto/cbc.c (ffffffff8140d6bd)
Location: include/crypto/skcipher.h:424
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_decrypt
```
```
In crypto/cts.c (ffffffff8140e070)
Location: include/crypto/skcipher.h:424
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:crypto_cts_encrypt
```
```
In crypto/xts.c (ffffffff8140e4ae)
Location: include/crypto/skcipher.h:424
Inline: True
Inline callers:
  - crypto/xts.c:init_crypt
```
```
In crypto/ctr.c (ffffffff8140f2e6)
Location: include/crypto/skcipher.h:424
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_crypt
```
```
In crypto/drbg.c (0)
Location: include/crypto/skcipher.h:424
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
Location: include/crypto/skcipher.h:424
Inline: True
```
```
In fs/crypto/fname.c (0)
Location: include/crypto/skcipher.h:424
Inline: True
```
```
In fs/crypto/keyinfo.c (0)
Location: include/crypto/skcipher.h:424
Inline: True
```
```
In fs/ecryptfs/crypto.c (0)
Location: include/crypto/skcipher.h:424
Inline: True
```
```
In fs/ecryptfs/keystore.c (0)
Location: include/crypto/skcipher.h:424
Inline: True
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff813bf1a8)
Location: include/crypto/skcipher.h:424
Inline: True
```
```
In crypto/skcipher.c (ffffffff8142a256)
Location: include/crypto/skcipher.h:424
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_decrypt_ablkcipher
  - crypto/skcipher.c:skcipher_encrypt_ablkcipher
  - crypto/skcipher.c:skcipher_decrypt_blkcipher
  - crypto/skcipher.c:skcipher_encrypt_blkcipher
  - crypto/skcipher.c:skcipher_walk_skcipher
```
```
In crypto/seqiv.c (0)
Location: include/crypto/skcipher.h:424
Inline: True
```
```
In crypto/cbc.c (ffffffff8143613d)
Location: include/crypto/skcipher.h:424
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_decrypt
```
```
In crypto/cts.c (ffffffff81436b20)
Location: include/crypto/skcipher.h:424
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:crypto_cts_encrypt
```
```
In crypto/xts.c (ffffffff81436f6e)
Location: include/crypto/skcipher.h:424
Inline: True
Inline callers:
  - crypto/xts.c:init_crypt
```
```
In crypto/ctr.c (ffffffff81437eb6)
Location: include/crypto/skcipher.h:424
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_crypt
```
```
In crypto/gcm.c (0)
Location: include/crypto/skcipher.h:424
Inline: True
```
```
In crypto/drbg.c (0)
Location: include/crypto/skcipher.h:424
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
Location: include/crypto/skcipher.h:419
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_do_page_crypto
  - fs/crypto/crypto.c:fscrypt_do_page_crypto
```
```
In fs/crypto/fname.c (ffffffff812fae9d)
Location: include/crypto/skcipher.h:419
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_encrypt
```
```
In fs/crypto/keyinfo.c (ffffffff812fba28)
Location: include/crypto/skcipher.h:419
Inline: True
Inline callers:
  - fs/crypto/keyinfo.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff813b7a8f)
Location: include/crypto/skcipher.h:419
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/keystore.c (ffffffff813bab65)
Location: include/crypto/skcipher.h:419
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff813eff41)
Location: include/crypto/skcipher.h:419
Inline: True
```
```
In crypto/skcipher.c (ffffffff8145cfa5)
Location: include/crypto/skcipher.h:419
Inline: True
Inline callers:
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
Location: include/crypto/skcipher.h:419
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/cbc.c (ffffffff81468b27)
Location: include/crypto/skcipher.h:419
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_decrypt
```
```
In crypto/cts.c (ffffffff814696b5)
Location: include/crypto/skcipher.h:419
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
In crypto/xts.c (ffffffff8146a39c)
Location: include/crypto/skcipher.h:419
Inline: True
Inline callers:
  - crypto/xts.c:do_decrypt
  - crypto/xts.c:do_encrypt
  - crypto/xts.c:init_crypt
```
```
In crypto/ctr.c (ffffffff8146a815)
Location: include/crypto/skcipher.h:419
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_crypt
  - crypto/ctr.c:crypto_rfc3686_crypt
```
```
In crypto/gcm.c (ffffffff8146b349)
Location: include/crypto/skcipher.h:419
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:gcm_dec_hash_continue
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (ffffffff8146fd64)
Location: include/crypto/skcipher.h:419
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
Location: include/crypto/skcipher.h:462
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_do_page_crypto
  - fs/crypto/crypto.c:fscrypt_do_page_crypto
```
```
In fs/crypto/fname.c (ffffffff81310254)
Location: include/crypto/skcipher.h:462
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_encrypt
```
```
In fs/crypto/keyinfo.c (ffffffff81310f85)
Location: include/crypto/skcipher.h:462
Inline: True
Inline callers:
  - fs/crypto/keyinfo.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff813d0feb)
Location: include/crypto/skcipher.h:462
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/keystore.c (ffffffff813d412c)
Location: include/crypto/skcipher.h:462
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff8140b220)
Location: include/crypto/skcipher.h:462
Inline: True
```
```
In crypto/skcipher.c (ffffffff8147a865)
Location: include/crypto/skcipher.h:462
Inline: True
Inline callers:
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
Location: include/crypto/skcipher.h:462
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/cbc.c (ffffffff814867a9)
Location: include/crypto/skcipher.h:462
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_decrypt
```
```
In crypto/cts.c (ffffffff814873e5)
Location: include/crypto/skcipher.h:462
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
Location: include/crypto/skcipher.h:462
Inline: True
Inline callers:
  - crypto/xts.c:xor_tweak
```
```
In crypto/ctr.c (ffffffff81488075)
Location: include/crypto/skcipher.h:462
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_crypt
  - crypto/ctr.c:crypto_rfc3686_crypt
```
```
In crypto/gcm.c (ffffffff814895c7)
Location: include/crypto/skcipher.h:462
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_copy_src_to_dst
  - crypto/gcm.c:gcm_dec_hash_continue
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (ffffffff814900f2)
Location: include/crypto/skcipher.h:462
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
Location: include/crypto/skcipher.h:397
Inline: True
```
```
In crypto/skcipher.c (ffffffff814a8b65)
Location: include/crypto/skcipher.h:397
Inline: True
Inline callers:
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
Location: include/crypto/skcipher.h:397
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_decrypt
  - crypto/ecb.c:crypto_ecb_encrypt
```
```
In crypto/cbc.c (ffffffff814b4619)
Location: include/crypto/skcipher.h:397
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_decrypt
```
```
In crypto/cts.c (ffffffff814b5125)
Location: include/crypto/skcipher.h:397
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
Location: include/crypto/skcipher.h:397
Inline: True
Inline callers:
  - crypto/xts.c:xor_tweak
```
```
In crypto/ctr.c (ffffffff814b5b05)
Location: include/crypto/skcipher.h:397
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
Location: include/crypto/skcipher.h:427
Inline: True
```
```
In crypto/skcipher.c (ffffffff814c37c5)
Location: include/crypto/skcipher.h:427
Inline: True
Inline callers:
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
Location: include/crypto/skcipher.h:427
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_decrypt
  - crypto/ecb.c:crypto_ecb_encrypt
```
```
In crypto/cbc.c (ffffffff814cd389)
Location: include/crypto/skcipher.h:427
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_decrypt
```
```
In crypto/cts.c (ffffffff814cdeb5)
Location: include/crypto/skcipher.h:427
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
In crypto/xts.c (ffffffff814ce075)
Location: include/crypto/skcipher.h:427
Inline: True
Inline callers:
  - crypto/xts.c:init_crypt
  - crypto/xts.c:cts_final
  - crypto/xts.c:xor_tweak
```
```
In crypto/ctr.c (ffffffff814ced05)
Location: include/crypto/skcipher.h:427
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
Location: include/crypto/skcipher.h:392
Inline: True
```
```
In crypto/skcipher.c (ffffffff815229c5)
Location: include/crypto/skcipher.h:392
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_skcipher_decrypt
  - crypto/skcipher.c:crypto_skcipher_encrypt
  - crypto/skcipher.c:skcipher_walk_async
  - crypto/skcipher.c:skcipher_walk_virt
```
```
In crypto/ecb.c (ffffffff8152c615)
Location: include/crypto/skcipher.h:392
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_decrypt
  - crypto/ecb.c:crypto_ecb_encrypt
```
```
In crypto/cbc.c (ffffffff8152c958)
Location: include/crypto/skcipher.h:392
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_decrypt
```
```
In crypto/cts.c (ffffffff8152d265)
Location: include/crypto/skcipher.h:392
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
In crypto/xts.c (ffffffff8152d8b5)
Location: include/crypto/skcipher.h:392
Inline: True
Inline callers:
  - crypto/xts.c:decrypt
  - crypto/xts.c:encrypt
  - crypto/xts.c:cts_final
  - crypto/xts.c:xor_tweak
```
```
In crypto/ctr.c (ffffffff8152dfd5)
Location: include/crypto/skcipher.h:392
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
Location: include/crypto/skcipher.h:392
Inline: True
```
```
In crypto/skcipher.c (ffffffff8153f885)
Location: include/crypto/skcipher.h:392
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_skcipher_decrypt
  - crypto/skcipher.c:crypto_skcipher_encrypt
  - crypto/skcipher.c:skcipher_walk_async
  - crypto/skcipher.c:skcipher_walk_virt
```
```
In crypto/ecb.c (ffffffff81549605)
Location: include/crypto/skcipher.h:392
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_decrypt
  - crypto/ecb.c:crypto_ecb_encrypt
```
```
In crypto/cbc.c (0)
Location: include/crypto/skcipher.h:392
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cbc.c:crypto_cbc_encrypt
```
```
In crypto/cts.c (ffffffff8154a2d5)
Location: include/crypto/skcipher.h:392
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
In crypto/xts.c (ffffffff8154a7e5)
Location: include/crypto/skcipher.h:392
Inline: True
Inline callers:
  - crypto/xts.c:xts_decrypt
  - crypto/xts.c:xts_encrypt
  - crypto/xts.c:xts_cts_final
  - crypto/xts.c:xts_xor_tweak
```
```
In crypto/ctr.c (ffffffff8154aff5)
Location: include/crypto/skcipher.h:392
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
Location: include/crypto/skcipher.h:394
Inline: True
```
```
In crypto/skcipher.c (ffffffff81547e15)
Location: include/crypto/skcipher.h:394
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_skcipher_decrypt
  - crypto/skcipher.c:crypto_skcipher_encrypt
  - crypto/skcipher.c:skcipher_walk_async
  - crypto/skcipher.c:skcipher_walk_virt
```
```
In crypto/ecb.c (ffffffff81551cf5)
Location: include/crypto/skcipher.h:394
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_decrypt
  - crypto/ecb.c:crypto_ecb_encrypt
```
```
In crypto/cbc.c (0)
Location: include/crypto/skcipher.h:394
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cbc.c:crypto_cbc_encrypt
```
```
In crypto/cts.c (ffffffff81552905)
Location: include/crypto/skcipher.h:394
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
In crypto/xts.c (ffffffff81552e05)
Location: include/crypto/skcipher.h:394
Inline: True
Inline callers:
  - crypto/xts.c:xts_decrypt
  - crypto/xts.c:xts_encrypt
  - crypto/xts.c:xts_cts_final
  - crypto/xts.c:xts_xor_tweak
```
```
In crypto/ctr.c (ffffffff81553615)
Location: include/crypto/skcipher.h:394
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
Location: include/crypto/skcipher.h:394
Inline: True
```
```
In crypto/skcipher.c (ffffffff815a85f5)
Location: include/crypto/skcipher.h:394
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_skcipher_decrypt
  - crypto/skcipher.c:crypto_skcipher_encrypt
  - crypto/skcipher.c:skcipher_walk_async
  - crypto/skcipher.c:skcipher_walk_virt
```
```
In crypto/ecb.c (ffffffff815b2cf5)
Location: include/crypto/skcipher.h:394
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_decrypt
  - crypto/ecb.c:crypto_ecb_encrypt
```
```
In crypto/cbc.c (0)
Location: include/crypto/skcipher.h:394
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cbc.c:crypto_cbc_encrypt
```
```
In crypto/cts.c (ffffffff815b3955)
Location: include/crypto/skcipher.h:394
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
In crypto/xts.c (ffffffff815b3e35)
Location: include/crypto/skcipher.h:394
Inline: True
Inline callers:
  - crypto/xts.c:xts_decrypt
  - crypto/xts.c:xts_encrypt
  - crypto/xts.c:xts_cts_final
  - crypto/xts.c:xts_xor_tweak
```
```
In crypto/ctr.c (ffffffff815b4645)
Location: include/crypto/skcipher.h:394
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
Location: include/crypto/skcipher.h:398
Inline: True
```
```
In crypto/skcipher.c (ffffffff8164f985)
Location: include/crypto/skcipher.h:398
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_skcipher_decrypt
  - crypto/skcipher.c:crypto_skcipher_encrypt
  - crypto/skcipher.c:skcipher_walk_async
  - crypto/skcipher.c:skcipher_walk_virt
```
```
In crypto/ecb.c (ffffffff8165b875)
Location: include/crypto/skcipher.h:398
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_decrypt
  - crypto/ecb.c:crypto_ecb_encrypt
```
```
In crypto/cbc.c (0)
Location: include/crypto/skcipher.h:398
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cbc.c:crypto_cbc_encrypt
```
```
In crypto/cts.c (ffffffff8165c6d5)
Location: include/crypto/skcipher.h:398
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:cts_cbc_encrypt
```
```
In crypto/xts.c (ffffffff8165cc35)
Location: include/crypto/skcipher.h:398
Inline: True
Inline callers:
  - crypto/xts.c:xts_decrypt
  - crypto/xts.c:xts_encrypt
  - crypto/xts.c:xts_cts_final
  - crypto/xts.c:xts_xor_tweak
```
```
In crypto/ctr.c (ffffffff8165d4f5)
Location: include/crypto/skcipher.h:398
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
In security/keys/encrypted-keys/encrypted.c (ffffffff8165fc97)
Location: include/crypto/skcipher.h:398
Inline: True
```
```
In crypto/skcipher.c (ffffffff81708dc5)
Location: include/crypto/skcipher.h:398
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_skcipher_decrypt
  - crypto/skcipher.c:crypto_skcipher_encrypt
  - crypto/skcipher.c:skcipher_walk_async
  - crypto/skcipher.c:skcipher_walk_virt
```
```
In crypto/ecb.c (ffffffff81715055)
Location: include/crypto/skcipher.h:398
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_decrypt
  - crypto/ecb.c:crypto_ecb_encrypt
```
```
In crypto/cbc.c (0)
Location: include/crypto/skcipher.h:398
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cbc.c:crypto_cbc_encrypt
```
```
In crypto/cts.c (ffffffff817160f5)
Location: include/crypto/skcipher.h:398
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:cts_cbc_encrypt
```
```
In crypto/xts.c (ffffffff81716685)
Location: include/crypto/skcipher.h:398
Inline: True
Inline callers:
  - crypto/xts.c:xts_decrypt
  - crypto/xts.c:xts_encrypt
  - crypto/xts.c:xts_cts_final
  - crypto/xts.c:xts_xor_tweak
```
```
In crypto/ctr.c (ffffffff81717125)
Location: include/crypto/skcipher.h:398
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
In security/keys/encrypted-keys/encrypted.c (ffffffff816985fd)
Location: include/crypto/skcipher.h:420
Inline: True
```
```
In crypto/skcipher.c (ffffffff81742fe5)
Location: include/crypto/skcipher.h:420
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_skcipher_decrypt
  - crypto/skcipher.c:crypto_skcipher_encrypt
  - crypto/skcipher.c:skcipher_walk_async
  - crypto/skcipher.c:skcipher_walk_virt
```
```
In crypto/ecb.c (ffffffff81750905)
Location: include/crypto/skcipher.h:420
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_decrypt
  - crypto/ecb.c:crypto_ecb_encrypt
```
```
In crypto/cbc.c (0)
Location: include/crypto/skcipher.h:420
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cbc.c:crypto_cbc_encrypt
```
```
In crypto/cts.c (ffffffff817519f5)
Location: include/crypto/skcipher.h:420
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:cts_cbc_encrypt
```
```
In crypto/xts.c (ffffffff81751f55)
Location: include/crypto/skcipher.h:420
Inline: True
Inline callers:
  - crypto/xts.c:xts_decrypt
  - crypto/xts.c:xts_encrypt
  - crypto/xts.c:xts_cts_final
  - crypto/xts.c:xts_xor_tweak
```
```
In crypto/ctr.c (ffffffff81752a35)
Location: include/crypto/skcipher.h:420
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
In security/keys/encrypted-keys/encrypted.c (ffffffff816d4c7d)
Location: include/crypto/skcipher.h:693
Inline: True
```
```
In crypto/lskcipher.c (ffffffff81784675)
Location: include/crypto/skcipher.h:693
Inline: True
Inline callers:
  - crypto/lskcipher.c:crypto_lskcipher_decrypt_sg
  - crypto/lskcipher.c:crypto_lskcipher_encrypt_sg
  - crypto/lskcipher.c:crypto_lskcipher_crypt_sg
```
```
In crypto/skcipher.c (ffffffff817847f5)
Location: include/crypto/skcipher.h:693
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_skcipher_import
  - crypto/skcipher.c:crypto_skcipher_export
  - crypto/skcipher.c:crypto_skcipher_decrypt
  - crypto/skcipher.c:crypto_skcipher_encrypt
  - crypto/skcipher.c:skcipher_walk_skcipher
```
```
In crypto/cts.c (ffffffff81793875)
Location: include/crypto/skcipher.h:693
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:cts_cbc_encrypt
```
```
In crypto/xts.c (ffffffff81793dd5)
Location: include/crypto/skcipher.h:693
Inline: True
Inline callers:
  - crypto/xts.c:xts_decrypt
  - crypto/xts.c:xts_encrypt
  - crypto/xts.c:xts_cts_final
  - crypto/xts.c:xts_xor_tweak
```
```
In crypto/ctr.c (ffffffff817949a5)
Location: include/crypto/skcipher.h:693
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
In security/keys/encrypted-keys/encrypted.c (ffff80001053d5c0)
Location: include/crypto/skcipher.h:427
Inline: True
```
```
In crypto/skcipher.c (ffff8000105be074)
Location: include/crypto/skcipher.h:427
Inline: True
Inline callers:
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
Location: include/crypto/skcipher.h:427
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_decrypt
  - crypto/ecb.c:crypto_ecb_encrypt
```
```
In crypto/cbc.c (ffff8000105c9230)
Location: include/crypto/skcipher.h:427
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_decrypt
```
```
In crypto/cts.c (ffff8000105c9dd4)
Location: include/crypto/skcipher.h:427
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
In crypto/xts.c (ffff8000105c9fac)
Location: include/crypto/skcipher.h:427
Inline: True
Inline callers:
  - crypto/xts.c:init_crypt
  - crypto/xts.c:cts_final
  - crypto/xts.c:xor_tweak
```
```
In crypto/ctr.c (ffff8000105cac58)
Location: include/crypto/skcipher.h:427
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
Location: include/crypto/skcipher.h:427
Inline: True
```
```
In crypto/skcipher.c (c076be60)
Location: include/crypto/skcipher.h:427
Inline: True
Inline callers:
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
Location: include/crypto/skcipher.h:427
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_decrypt
  - crypto/ecb.c:crypto_ecb_encrypt
```
```
In crypto/cbc.c (c0776fb4)
Location: include/crypto/skcipher.h:427
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cbc.c:crypto_cbc_encrypt
```
```
In crypto/cts.c (c0777908)
Location: include/crypto/skcipher.h:427
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
In crypto/xts.c (c0777aac)
Location: include/crypto/skcipher.h:427
Inline: True
Inline callers:
  - crypto/xts.c:init_crypt
  - crypto/xts.c:cts_final
  - crypto/xts.c:xor_tweak
```
```
In crypto/ctr.c (c0778818)
Location: include/crypto/skcipher.h:427
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
Location: include/crypto/skcipher.h:427
Inline: True
```
```
In crypto/skcipher.c (c0000000007456ec)
Location: include/crypto/skcipher.h:427
Inline: True
Inline callers:
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
Location: include/crypto/skcipher.h:427
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_decrypt
  - crypto/ecb.c:crypto_ecb_encrypt
```
```
In crypto/cbc.c (c000000000753770)
Location: include/crypto/skcipher.h:427
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_decrypt
```
```
In crypto/cts.c (c0000000007546c8)
Location: include/crypto/skcipher.h:427
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
In crypto/xts.c (c000000000754940)
Location: include/crypto/skcipher.h:427
Inline: True
Inline callers:
  - crypto/xts.c:init_crypt
  - crypto/xts.c:cts_final
  - crypto/xts.c:xor_tweak
```
```
In crypto/ctr.c (c000000000755a5c)
Location: include/crypto/skcipher.h:427
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
In security/keys/encrypted-keys/encrypted.c (ffffffe00039aa12)
Location: include/crypto/skcipher.h:427
Inline: True
```
```
In crypto/skcipher.c (ffffffe000403520)
Location: include/crypto/skcipher.h:427
Inline: True
Inline callers:
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
Location: include/crypto/skcipher.h:427
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_decrypt
  - crypto/ecb.c:crypto_ecb_encrypt
```
```
In crypto/cbc.c (ffffffe00040db12)
Location: include/crypto/skcipher.h:427
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_decrypt
```
```
In crypto/cts.c (ffffffe00040df76)
Location: include/crypto/skcipher.h:427
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
In crypto/xts.c (ffffffe00040e5ea)
Location: include/crypto/skcipher.h:427
Inline: True
Inline callers:
  - crypto/xts.c:init_crypt
  - crypto/xts.c:cts_final
  - crypto/xts.c:xor_tweak
```
```
In crypto/ctr.c (ffffffe00040f11c)
Location: include/crypto/skcipher.h:427
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
Location: include/crypto/skcipher.h:427
Inline: True
```
```
In crypto/skcipher.c (ffffffff814bbda5)
Location: include/crypto/skcipher.h:427
Inline: True
Inline callers:
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
Location: include/crypto/skcipher.h:427
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_decrypt
  - crypto/ecb.c:crypto_ecb_encrypt
```
```
In crypto/cbc.c (ffffffff814c5969)
Location: include/crypto/skcipher.h:427
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_decrypt
```
```
In crypto/cts.c (ffffffff814c6495)
Location: include/crypto/skcipher.h:427
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
In crypto/xts.c (ffffffff814c6655)
Location: include/crypto/skcipher.h:427
Inline: True
Inline callers:
  - crypto/xts.c:init_crypt
  - crypto/xts.c:cts_final
  - crypto/xts.c:xor_tweak
```
```
In crypto/ctr.c (ffffffff814c72e5)
Location: include/crypto/skcipher.h:427
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
Location: include/crypto/skcipher.h:427
Inline: True
```
```
In crypto/skcipher.c (ffffffff814ac7c5)
Location: include/crypto/skcipher.h:427
Inline: True
Inline callers:
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
Location: include/crypto/skcipher.h:427
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_decrypt
  - crypto/ecb.c:crypto_ecb_encrypt
```
```
In crypto/cbc.c (ffffffff814b6389)
Location: include/crypto/skcipher.h:427
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_decrypt
```
```
In crypto/cts.c (ffffffff814b6eb5)
Location: include/crypto/skcipher.h:427
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
In crypto/xts.c (ffffffff814b7075)
Location: include/crypto/skcipher.h:427
Inline: True
Inline callers:
  - crypto/xts.c:init_crypt
  - crypto/xts.c:cts_final
  - crypto/xts.c:xor_tweak
```
```
In crypto/ctr.c (ffffffff814b7d05)
Location: include/crypto/skcipher.h:427
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
Location: include/crypto/skcipher.h:427
Inline: True
```
```
In crypto/skcipher.c (ffffffff814b7e35)
Location: include/crypto/skcipher.h:427
Inline: True
Inline callers:
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
Location: include/crypto/skcipher.h:427
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_decrypt
  - crypto/ecb.c:crypto_ecb_encrypt
```
```
In crypto/cbc.c (ffffffff814c19f9)
Location: include/crypto/skcipher.h:427
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_decrypt
```
```
In crypto/cts.c (ffffffff814c2525)
Location: include/crypto/skcipher.h:427
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
In crypto/xts.c (ffffffff814c26e5)
Location: include/crypto/skcipher.h:427
Inline: True
Inline callers:
  - crypto/xts.c:init_crypt
  - crypto/xts.c:cts_final
  - crypto/xts.c:xor_tweak
```
```
In crypto/ctr.c (ffffffff814c3375)
Location: include/crypto/skcipher.h:427
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
Location: include/crypto/skcipher.h:427
Inline: True
```
```
In crypto/skcipher.c (ffffffff814d0915)
Location: include/crypto/skcipher.h:427
Inline: True
Inline callers:
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
Location: include/crypto/skcipher.h:427
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_decrypt
  - crypto/ecb.c:crypto_ecb_encrypt
```
```
In crypto/cbc.c (ffffffff814da4c9)
Location: include/crypto/skcipher.h:427
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_decrypt
```
```
In crypto/cts.c (ffffffff814daff5)
Location: include/crypto/skcipher.h:427
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
In crypto/xts.c (ffffffff814db1b5)
Location: include/crypto/skcipher.h:427
Inline: True
Inline callers:
  - crypto/xts.c:init_crypt
  - crypto/xts.c:cts_final
  - crypto/xts.c:xor_tweak
```
```
In crypto/ctr.c (ffffffff814dbe45)
Location: include/crypto/skcipher.h:427
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_crypt
  - crypto/ctr.c:crypto_ctr_crypt
```
</details>
</li>
</ul>

## Differences
