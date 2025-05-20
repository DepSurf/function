# Function: <code>crypto_skcipher_setkey</code>

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
In fs/crypto/keyinfo.c (ffffffff8128a1be)
Location: include/crypto/skcipher.h:364
Inline: True
Inline callers:
  - fs/crypto/keyinfo.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff8133b01f)
Location: include/crypto/skcipher.h:364
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/keystore.c (ffffffff8133c6b3)
Location: include/crypto/skcipher.h:364
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/big_key.c (ffffffff8136b7a8)
Location: include/crypto/skcipher.h:364
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_crypt
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff8136e40d)
Location: include/crypto/skcipher.h:364
Inline: True
```
```
In crypto/cts.c (ffffffff813e7752)
Location: include/crypto/skcipher.h:364
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_setkey
```
```
In crypto/ctr.c (ffffffff813e884c)
Location: include/crypto/skcipher.h:364
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_setkey
```
```
In crypto/drbg.c (ffffffff813edbe3)
Location: include/crypto/skcipher.h:364
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
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
In fs/crypto/keyinfo.c (ffffffff8129eefe)
Location: include/crypto/skcipher.h:364
Inline: True
Inline callers:
  - fs/crypto/keyinfo.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff81350db3)
Location: include/crypto/skcipher.h:364
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/keystore.c (ffffffff81352443)
Location: include/crypto/skcipher.h:364
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/big_key.c (ffffffff81381fc8)
Location: include/crypto/skcipher.h:364
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_crypt
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff81384c2d)
Location: include/crypto/skcipher.h:364
Inline: True
```
```
In crypto/cts.c (ffffffff81400582)
Location: include/crypto/skcipher.h:364
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_setkey
```
```
In crypto/xts.c (ffffffff8140136a)
Location: include/crypto/skcipher.h:364
Inline: True
```
```
In crypto/ctr.c (ffffffff81401e5c)
Location: include/crypto/skcipher.h:364
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_setkey
```
```
In crypto/drbg.c (ffffffff81407423)
Location: include/crypto/skcipher.h:364
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
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
In fs/crypto/keyinfo.c (ffffffff812ad96d)
Location: include/crypto/skcipher.h:398
Inline: True
Inline callers:
  - fs/crypto/keyinfo.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff813658d3)
Location: include/crypto/skcipher.h:398
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/keystore.c (ffffffff813671d5)
Location: include/crypto/skcipher.h:398
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/big_key.c (ffffffff81396668)
Location: include/crypto/skcipher.h:398
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_crypt
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff8139929f)
Location: include/crypto/skcipher.h:398
Inline: True
```
```
In crypto/cts.c (ffffffff8140d882)
Location: include/crypto/skcipher.h:398
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_setkey
```
```
In crypto/xts.c (ffffffff8140e5fa)
Location: include/crypto/skcipher.h:398
Inline: True
Inline callers:
  - crypto/xts.c:setkey
```
```
In crypto/ctr.c (ffffffff8140f2a7)
Location: include/crypto/skcipher.h:398
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_setkey
```
```
In crypto/drbg.c (ffffffff81414aab)
Location: include/crypto/skcipher.h:398
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
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
In fs/crypto/keyinfo.c (ffffffff812d0e2e)
Location: include/crypto/skcipher.h:398
Inline: True
Inline callers:
  - fs/crypto/keyinfo.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff8138a593)
Location: include/crypto/skcipher.h:398
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/keystore.c (ffffffff8138be55)
Location: include/crypto/skcipher.h:398
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff813beaaf)
Location: include/crypto/skcipher.h:398
Inline: True
```
```
In crypto/cts.c (ffffffff81436312)
Location: include/crypto/skcipher.h:398
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_setkey
```
```
In crypto/xts.c (ffffffff814370bf)
Location: include/crypto/skcipher.h:398
Inline: True
Inline callers:
  - crypto/xts.c:setkey
```
```
In crypto/ctr.c (ffffffff81437e77)
Location: include/crypto/skcipher.h:398
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_setkey
```
```
In crypto/gcm.c (ffffffff8143a3a0)
Location: include/crypto/skcipher.h:398
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (ffffffff8143f25b)
Location: include/crypto/skcipher.h:398
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
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
In fs/crypto/keyinfo.c (ffffffff812fb9cb)
Location: include/crypto/skcipher.h:398
Inline: True
Inline callers:
  - fs/crypto/keyinfo.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff813b92e3)
Location: include/crypto/skcipher.h:398
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/keystore.c (ffffffff813baab1)
Location: include/crypto/skcipher.h:398
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff813ef8f3)
Location: include/crypto/skcipher.h:398
Inline: True
```
```
In crypto/cts.c (ffffffff81468e6f)
Location: include/crypto/skcipher.h:398
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_setkey
```
```
In crypto/xts.c (ffffffff81469b12)
Location: include/crypto/skcipher.h:398
Inline: True
```
```
In crypto/ctr.c (ffffffff8146a7e6)
Location: include/crypto/skcipher.h:398
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_setkey
```
```
In crypto/gcm.c (ffffffff8146cd63)
Location: include/crypto/skcipher.h:398
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (ffffffff814720aa)
Location: include/crypto/skcipher.h:398
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
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
In fs/crypto/keyinfo.c (ffffffff81310f1f)
Location: include/crypto/skcipher.h:435
Inline: True
Inline callers:
  - fs/crypto/keyinfo.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff813d2853)
Location: include/crypto/skcipher.h:435
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/keystore.c (ffffffff813d4071)
Location: include/crypto/skcipher.h:435
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff8140ab43)
Location: include/crypto/skcipher.h:435
Inline: True
```
```
In crypto/cts.c (ffffffff81486aef)
Location: include/crypto/skcipher.h:435
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_setkey
```
```
In crypto/xts.c (ffffffff814879e2)
Location: include/crypto/skcipher.h:435
Inline: True
```
```
In crypto/ctr.c (ffffffff81488046)
Location: include/crypto/skcipher.h:435
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_setkey
```
```
In crypto/gcm.c (ffffffff81489331)
Location: include/crypto/skcipher.h:435
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (ffffffff8149043a)
Location: include/crypto/skcipher.h:435
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
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
In fs/crypto/keyinfo.c (ffffffff8133864d)
Location: include/crypto/skcipher.h:370
Inline: True
Inline callers:
  - fs/crypto/keyinfo.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff813fd2f3)
Location: include/crypto/skcipher.h:370
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/keystore.c (ffffffff813feadb)
Location: include/crypto/skcipher.h:370
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff81437dd3)
Location: include/crypto/skcipher.h:370
Inline: True
```
```
In crypto/cts.c (ffffffff814b4965)
Location: include/crypto/skcipher.h:370
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_setkey
```
```
In crypto/xts.c (ffffffff814b56f6)
Location: include/crypto/skcipher.h:370
Inline: True
```
```
In crypto/ctr.c (ffffffff814b5ad6)
Location: include/crypto/skcipher.h:370
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_setkey
```
```
In crypto/gcm.c (ffffffff814b6f7e)
Location: include/crypto/skcipher.h:370
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (ffffffff814bd5ea)
Location: include/crypto/skcipher.h:370
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
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
In fs/crypto/keysetup.c (ffffffff8134d758)
Location: include/crypto/skcipher.h:400
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_allocate_skcipher
```
```
In fs/crypto/keysetup_v1.c (ffffffff8134e45b)
Location: include/crypto/skcipher.h:400
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff814171d4)
Location: include/crypto/skcipher.h:400
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/keystore.c (ffffffff814189cb)
Location: include/crypto/skcipher.h:400
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff81451b93)
Location: include/crypto/skcipher.h:400
Inline: True
```
```
In crypto/cts.c (ffffffff814cd6d5)
Location: include/crypto/skcipher.h:400
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_setkey
```
```
In crypto/xts.c (ffffffff814ce8f6)
Location: include/crypto/skcipher.h:400
Inline: True
```
```
In crypto/ctr.c (ffffffff814cecd6)
Location: include/crypto/skcipher.h:400
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_setkey
```
```
In crypto/gcm.c (ffffffff814d019e)
Location: include/crypto/skcipher.h:400
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (ffffffff814d62da)
Location: include/crypto/skcipher.h:400
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int crypto_skcipher_setkey(struct crypto_skcipher *tfm, const u8 *key, unsigned int keylen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff81522900)
Location: crypto/skcipher.c:599
Inline: False
Direct callers:
  - fs/crypto/keysetup.c:fscrypt_allocate_skcipher
  - fs/crypto/keysetup_v1.c:derive_key_aes
  - fs/ecryptfs/crypto.c:ecryptfs_process_key_cipher
  - fs/ecryptfs/crypto.c:crypt_scatterlist
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - crypto/cts.c:crypto_cts_setkey
  - crypto/ctr.c:crypto_rfc3686_setkey
  - crypto/gcm.c:crypto_gcm_setkey
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - block/blk-crypto-fallback.c:blk_crypto_keyslot_evict
  - block/blk-crypto-fallback.c:blk_crypto_keyslot_program
```
**Symbols:**

```
ffffffff81522900-ffffffff81522958: crypto_skcipher_setkey (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int crypto_skcipher_setkey(struct crypto_skcipher *tfm, const u8 *key, unsigned int keylen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff8153f7c0)
Location: crypto/skcipher.c:599
Inline: False
Direct callers:
  - fs/crypto/keysetup.c:fscrypt_allocate_skcipher
  - fs/crypto/keysetup_v1.c:derive_key_aes
  - fs/ecryptfs/crypto.c:ecryptfs_process_key_cipher
  - fs/ecryptfs/crypto.c:crypt_scatterlist
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - crypto/cts.c:crypto_cts_setkey
  - crypto/ctr.c:crypto_rfc3686_setkey
  - crypto/gcm.c:crypto_gcm_setkey
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - block/blk-crypto-fallback.c:blk_crypto_keyslot_evict
  - block/blk-crypto-fallback.c:blk_crypto_keyslot_program
```
**Symbols:**

```
ffffffff8153f7c0-ffffffff8153f818: crypto_skcipher_setkey (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int crypto_skcipher_setkey(struct crypto_skcipher *tfm, const u8 *key, unsigned int keylen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff81547d50)
Location: crypto/skcipher.c:594
Inline: False
Direct callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - fs/ecryptfs/crypto.c:crypt_scatterlist
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - crypto/cts.c:crypto_cts_setkey
  - crypto/ctr.c:crypto_rfc3686_setkey
  - crypto/gcm.c:crypto_gcm_setkey
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - block/blk-crypto-fallback.c:blk_crypto_keyslot_evict
  - block/blk-crypto-fallback.c:blk_crypto_keyslot_program
```
**Symbols:**

```
ffffffff81547d50-ffffffff81547da8: crypto_skcipher_setkey (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int crypto_skcipher_setkey(struct crypto_skcipher *tfm, const u8 *key, unsigned int keylen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff815a8530)
Location: crypto/skcipher.c:594
Inline: False
Direct callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - fs/ecryptfs/crypto.c:crypt_scatterlist
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - crypto/cts.c:crypto_cts_setkey
  - crypto/ctr.c:crypto_rfc3686_setkey
  - crypto/gcm.c:crypto_gcm_setkey
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - block/blk-crypto-fallback.c:blk_crypto_keyslot_evict
  - block/blk-crypto-fallback.c:blk_crypto_keyslot_program
```
**Symbols:**

```
ffffffff815a8530-ffffffff815a8588: crypto_skcipher_setkey (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int crypto_skcipher_setkey(struct crypto_skcipher *tfm, const u8 *key, unsigned int keylen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff8164fea0)
Location: crypto/skcipher.c:594
Inline: False
Direct callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - fs/ecryptfs/crypto.c:crypt_scatterlist
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - crypto/cts.c:crypto_cts_setkey
  - crypto/ctr.c:crypto_rfc3686_setkey
  - crypto/gcm.c:crypto_gcm_setkey
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - block/blk-crypto-fallback.c:blk_crypto_fallback_keyslot_evict
  - block/blk-crypto-fallback.c:blk_crypto_fallback_keyslot_program
```
**Symbols:**

```
ffffffff8164fea0-ffffffff8164ff10: crypto_skcipher_setkey (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int crypto_skcipher_setkey(struct crypto_skcipher *tfm, const u8 *key, unsigned int keylen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff817095d0)
Location: crypto/skcipher.c:594
Inline: False
Direct callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - fs/ecryptfs/crypto.c:crypt_scatterlist
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - crypto/cts.c:crypto_cts_setkey
  - crypto/ctr.c:crypto_rfc3686_setkey
  - crypto/gcm.c:crypto_gcm_setkey
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - block/blk-crypto-fallback.c:blk_crypto_fallback_keyslot_evict
  - block/blk-crypto-fallback.c:blk_crypto_fallback_keyslot_program
```
**Symbols:**

```
ffffffff817095d0-ffffffff81709640: crypto_skcipher_setkey (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int crypto_skcipher_setkey(struct crypto_skcipher *tfm, const u8 *key, unsigned int keylen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff81742e10)
Location: crypto/skcipher.c:612
Inline: False
Direct callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - fs/ecryptfs/crypto.c:crypt_scatterlist
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - crypto/cts.c:crypto_cts_setkey
  - crypto/ctr.c:crypto_rfc3686_setkey
  - crypto/gcm.c:crypto_gcm_setkey
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - block/blk-crypto-fallback.c:blk_crypto_fallback_keyslot_evict
  - block/blk-crypto-fallback.c:blk_crypto_fallback_keyslot_program
```
**Symbols:**

```
ffffffff81742e10-ffffffff81742e80: crypto_skcipher_setkey (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int crypto_skcipher_setkey(struct crypto_skcipher *tfm, const u8 *key, unsigned int keylen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff817850e0)
Location: crypto/skcipher.c:616
Inline: False
Direct callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - fs/ecryptfs/crypto.c:crypt_scatterlist
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - crypto/cts.c:crypto_cts_setkey
  - crypto/ctr.c:crypto_rfc3686_setkey
  - crypto/gcm.c:crypto_gcm_setkey
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - block/blk-crypto-fallback.c:blk_crypto_fallback_keyslot_evict
  - block/blk-crypto-fallback.c:blk_crypto_fallback_keyslot_program
```
**Symbols:**

```
ffffffff817850e0-ffffffff81785176: crypto_skcipher_setkey (STB_GLOBAL)
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
In fs/crypto/keysetup.c (ffff80001040e958)
Location: include/crypto/skcipher.h:400
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_allocate_skcipher
```
```
In fs/crypto/keysetup_v1.c (ffff80001040f66c)
Location: include/crypto/skcipher.h:400
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffff8000104f8c24)
Location: include/crypto/skcipher.h:400
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/keystore.c (ffff8000104fa1fc)
Location: include/crypto/skcipher.h:400
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (ffff80001053cb3c)
Location: include/crypto/skcipher.h:400
Inline: True
```
```
In crypto/cts.c (ffff8000105c958c)
Location: include/crypto/skcipher.h:400
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_setkey
```
```
In crypto/xts.c (ffff8000105caafc)
Location: include/crypto/skcipher.h:400
Inline: True
```
```
In crypto/ctr.c (ffff8000105cac0c)
Location: include/crypto/skcipher.h:400
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_setkey
```
```
In crypto/gcm.c (ffff8000105cc684)
Location: include/crypto/skcipher.h:400
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (ffff8000105d2a14)
Location: include/crypto/skcipher.h:400
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
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
In fs/crypto/keysetup.c (c05db468)
Location: include/crypto/skcipher.h:400
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_allocate_skcipher
```
```
In fs/crypto/keysetup_v1.c (c05dc354)
Location: include/crypto/skcipher.h:400
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
```
```
In fs/ecryptfs/crypto.c (c06b64d0)
Location: include/crypto/skcipher.h:400
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - fs/ecryptfs/crypto.c:crypt_extent
```
```
In fs/ecryptfs/keystore.c (c06b7944)
Location: include/crypto/skcipher.h:400
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (c06f2da8)
Location: include/crypto/skcipher.h:400
Inline: True
```
```
In crypto/cts.c (c0777158)
Location: include/crypto/skcipher.h:400
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_setkey
```
```
In crypto/xts.c (c0778700)
Location: include/crypto/skcipher.h:400
Inline: True
```
```
In crypto/ctr.c (c07787dc)
Location: include/crypto/skcipher.h:400
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_setkey
```
```
In crypto/gcm.c (c077a568)
Location: include/crypto/skcipher.h:400
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (c077f844)
Location: include/crypto/skcipher.h:400
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
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
In fs/crypto/keysetup.c (c00000000051bea8)
Location: include/crypto/skcipher.h:400
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_allocate_skcipher
```
```
In fs/crypto/keysetup_v1.c (c00000000051d110)
Location: include/crypto/skcipher.h:400
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (c00000000063aa88)
Location: include/crypto/skcipher.h:400
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/keystore.c (c00000000063c84c)
Location: include/crypto/skcipher.h:400
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (c00000000068c85c)
Location: include/crypto/skcipher.h:400
Inline: True
```
```
In crypto/cts.c (c000000000753bb8)
Location: include/crypto/skcipher.h:400
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_setkey
```
```
In crypto/xts.c (c00000000075548c)
Location: include/crypto/skcipher.h:400
Inline: True
```
```
In crypto/ctr.c (c0000000007559f0)
Location: include/crypto/skcipher.h:400
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_setkey
```
```
In crypto/gcm.c (c000000000757ad4)
Location: include/crypto/skcipher.h:400
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (c00000000075f040)
Location: include/crypto/skcipher.h:400
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
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
In fs/crypto/keysetup.c (ffffffe0002b7870)
Location: include/crypto/skcipher.h:400
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_allocate_skcipher
```
```
In fs/crypto/keysetup_v1.c (ffffffe0002b852c)
Location: include/crypto/skcipher.h:400
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
```
```
In fs/ecryptfs/crypto.c (ffffffe0003674f6)
Location: include/crypto/skcipher.h:400
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/keystore.c (ffffffe0003689ac)
Location: include/crypto/skcipher.h:400
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffe00039a82e)
Location: include/crypto/skcipher.h:400
Inline: True
```
```
In crypto/cts.c (ffffffe00040dd90)
Location: include/crypto/skcipher.h:400
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_setkey
```
```
In crypto/xts.c (ffffffe00040ecd6)
Location: include/crypto/skcipher.h:400
Inline: True
```
```
In crypto/ctr.c (ffffffe00040f0d2)
Location: include/crypto/skcipher.h:400
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_setkey
```
```
In crypto/gcm.c (ffffffe0004105d8)
Location: include/crypto/skcipher.h:400
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (ffffffe000417242)
Location: include/crypto/skcipher.h:400
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
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
In fs/crypto/keysetup.c (ffffffff81345d38)
Location: include/crypto/skcipher.h:400
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_allocate_skcipher
```
```
In fs/crypto/keysetup_v1.c (ffffffff81346a3b)
Location: include/crypto/skcipher.h:400
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff8140f7b4)
Location: include/crypto/skcipher.h:400
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/keystore.c (ffffffff81410fab)
Location: include/crypto/skcipher.h:400
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff8144a173)
Location: include/crypto/skcipher.h:400
Inline: True
```
```
In crypto/cts.c (ffffffff814c5cb5)
Location: include/crypto/skcipher.h:400
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_setkey
```
```
In crypto/xts.c (ffffffff814c6ed6)
Location: include/crypto/skcipher.h:400
Inline: True
```
```
In crypto/ctr.c (ffffffff814c72b6)
Location: include/crypto/skcipher.h:400
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_setkey
```
```
In crypto/gcm.c (ffffffff814c877e)
Location: include/crypto/skcipher.h:400
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (ffffffff814ce8ba)
Location: include/crypto/skcipher.h:400
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
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
In fs/crypto/keysetup.c (ffffffff81336a18)
Location: include/crypto/skcipher.h:400
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_allocate_skcipher
```
```
In fs/crypto/keysetup_v1.c (ffffffff8133771b)
Location: include/crypto/skcipher.h:400
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff81400234)
Location: include/crypto/skcipher.h:400
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/keystore.c (ffffffff81401a2b)
Location: include/crypto/skcipher.h:400
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff8143abc3)
Location: include/crypto/skcipher.h:400
Inline: True
```
```
In crypto/cts.c (ffffffff814b66d5)
Location: include/crypto/skcipher.h:400
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_setkey
```
```
In crypto/xts.c (ffffffff814b78f6)
Location: include/crypto/skcipher.h:400
Inline: True
```
```
In crypto/ctr.c (ffffffff814b7cd6)
Location: include/crypto/skcipher.h:400
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_setkey
```
```
In crypto/gcm.c (ffffffff814b919e)
Location: include/crypto/skcipher.h:400
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (ffffffff814bf2da)
Location: include/crypto/skcipher.h:400
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
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
In fs/crypto/keysetup.c (ffffffff81343808)
Location: include/crypto/skcipher.h:400
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_allocate_skcipher
```
```
In fs/crypto/keysetup_v1.c (ffffffff8134450b)
Location: include/crypto/skcipher.h:400
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff8140cb34)
Location: include/crypto/skcipher.h:400
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/keystore.c (ffffffff8140e32b)
Location: include/crypto/skcipher.h:400
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff81446213)
Location: include/crypto/skcipher.h:400
Inline: True
```
```
In crypto/cts.c (ffffffff814c1d45)
Location: include/crypto/skcipher.h:400
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_setkey
```
```
In crypto/xts.c (ffffffff814c2f66)
Location: include/crypto/skcipher.h:400
Inline: True
```
```
In crypto/ctr.c (ffffffff814c3346)
Location: include/crypto/skcipher.h:400
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_setkey
```
```
In crypto/gcm.c (ffffffff814c480e)
Location: include/crypto/skcipher.h:400
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (ffffffff814ca94a)
Location: include/crypto/skcipher.h:400
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
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
In fs/crypto/keysetup.c (ffffffff81356ae8)
Location: include/crypto/skcipher.h:400
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_allocate_skcipher
```
```
In fs/crypto/keysetup_v1.c (ffffffff813577eb)
Location: include/crypto/skcipher.h:400
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff814227b4)
Location: include/crypto/skcipher.h:400
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/keystore.c (ffffffff81423f9b)
Location: include/crypto/skcipher.h:400
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff8145d543)
Location: include/crypto/skcipher.h:400
Inline: True
```
```
In crypto/cts.c (ffffffff814da815)
Location: include/crypto/skcipher.h:400
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_setkey
```
```
In crypto/xts.c (ffffffff814dba36)
Location: include/crypto/skcipher.h:400
Inline: True
```
```
In crypto/ctr.c (ffffffff814dbe16)
Location: include/crypto/skcipher.h:400
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_setkey
```
```
In crypto/gcm.c (ffffffff814dd2de)
Location: include/crypto/skcipher.h:400
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (ffffffff814e341a)
Location: include/crypto/skcipher.h:400
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
