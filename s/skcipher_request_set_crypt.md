# Function: <code>skcipher_request_set_crypt</code>

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
In fs/crypto/crypto.c (ffffffff81288a4a)
Location: include/crypto/skcipher.h:566
Inline: True
```
```
In fs/crypto/fname.c (ffffffff812898c6)
Location: include/crypto/skcipher.h:566
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_decrypt
  - fs/crypto/fname.c:fname_encrypt
```
```
In fs/crypto/keyinfo.c (ffffffff8128a217)
Location: include/crypto/skcipher.h:566
Inline: True
Inline callers:
  - fs/crypto/keyinfo.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff813395fe)
Location: include/crypto/skcipher.h:566
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/keystore.c (ffffffff8133c734)
Location: include/crypto/skcipher.h:566
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/big_key.c (ffffffff8136b853)
Location: include/crypto/skcipher.h:566
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_crypt
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff8136e690)
Location: include/crypto/skcipher.h:566
Inline: True
```
```
In crypto/seqiv.c (ffffffff813de978)
Location: include/crypto/skcipher.h:566
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/cts.c (ffffffff813e7a18)
Location: include/crypto/skcipher.h:566
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:cts_cbc_encrypt
```
```
In crypto/ctr.c (ffffffff813e88e2)
Location: include/crypto/skcipher.h:566
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_crypt
```
```
In crypto/drbg.c (ffffffff813eb8d2)
Location: include/crypto/skcipher.h:566
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
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
In fs/crypto/crypto.c (ffffffff8129d695)
Location: include/crypto/skcipher.h:566
Inline: True
```
```
In fs/crypto/fname.c (ffffffff8129e586)
Location: include/crypto/skcipher.h:566
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_decrypt
  - fs/crypto/fname.c:fname_encrypt
```
```
In fs/crypto/keyinfo.c (ffffffff8129ef57)
Location: include/crypto/skcipher.h:566
Inline: True
Inline callers:
  - fs/crypto/keyinfo.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff8134f39e)
Location: include/crypto/skcipher.h:566
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/keystore.c (ffffffff813524c4)
Location: include/crypto/skcipher.h:566
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/big_key.c (ffffffff81382073)
Location: include/crypto/skcipher.h:566
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_crypt
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff813852ab)
Location: include/crypto/skcipher.h:566
Inline: True
```
```
In crypto/seqiv.c (ffffffff813f6f18)
Location: include/crypto/skcipher.h:566
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/cts.c (ffffffff81400848)
Location: include/crypto/skcipher.h:566
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:cts_cbc_encrypt
```
```
In crypto/xts.c (ffffffff814018f7)
Location: include/crypto/skcipher.h:566
Inline: True
Inline callers:
  - crypto/xts.c:pre_crypt
  - crypto/xts.c:pre_crypt
```
```
In crypto/ctr.c (ffffffff81401ef2)
Location: include/crypto/skcipher.h:566
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_crypt
```
```
In crypto/drbg.c (ffffffff8140504b)
Location: include/crypto/skcipher.h:566
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
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
In fs/crypto/crypto.c (ffffffff812ac3fd)
Location: include/crypto/skcipher.h:600
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_do_page_crypto
```
```
In fs/crypto/fname.c (ffffffff812ad04c)
Location: include/crypto/skcipher.h:600
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_decrypt
  - fs/crypto/fname.c:fname_encrypt
```
```
In fs/crypto/keyinfo.c (ffffffff812ad9b8)
Location: include/crypto/skcipher.h:600
Inline: True
Inline callers:
  - fs/crypto/keyinfo.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff81363e5d)
Location: include/crypto/skcipher.h:600
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/keystore.c (ffffffff81367258)
Location: include/crypto/skcipher.h:600
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/big_key.c (ffffffff8139670c)
Location: include/crypto/skcipher.h:600
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_crypt
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff813999a6)
Location: include/crypto/skcipher.h:600
Inline: True
```
```
In crypto/seqiv.c (ffffffff81403322)
Location: include/crypto/skcipher.h:600
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/cts.c (ffffffff8140e0af)
Location: include/crypto/skcipher.h:600
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:cts_cbc_encrypt
```
```
In crypto/xts.c (ffffffff8140ece6)
Location: include/crypto/skcipher.h:600
Inline: True
Inline callers:
  - crypto/xts.c:pre_crypt
  - crypto/xts.c:pre_crypt
```
```
In crypto/ctr.c (ffffffff8140f342)
Location: include/crypto/skcipher.h:600
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_crypt
```
```
In crypto/drbg.c (ffffffff814127f6)
Location: include/crypto/skcipher.h:600
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
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
In fs/crypto/crypto.c (ffffffff812cfc15)
Location: include/crypto/skcipher.h:600
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_do_page_crypto
```
```
In fs/crypto/fname.c (ffffffff812d07f6)
Location: include/crypto/skcipher.h:600
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_decrypt
  - fs/crypto/fname.c:fname_encrypt
```
```
In fs/crypto/keyinfo.c (ffffffff812d0e7e)
Location: include/crypto/skcipher.h:600
Inline: True
Inline callers:
  - fs/crypto/keyinfo.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff81388bd0)
Location: include/crypto/skcipher.h:600
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/keystore.c (ffffffff8138bedb)
Location: include/crypto/skcipher.h:600
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff813bf176)
Location: include/crypto/skcipher.h:600
Inline: True
```
```
In crypto/seqiv.c (ffffffff8142ba12)
Location: include/crypto/skcipher.h:600
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/cts.c (ffffffff81436b5f)
Location: include/crypto/skcipher.h:600
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:cts_cbc_encrypt
```
```
In crypto/xts.c (ffffffff814377b6)
Location: include/crypto/skcipher.h:600
Inline: True
Inline callers:
  - crypto/xts.c:pre_crypt
  - crypto/xts.c:pre_crypt
```
```
In crypto/ctr.c (ffffffff81437f12)
Location: include/crypto/skcipher.h:600
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_crypt
```
```
In crypto/gcm.c (ffffffff81439011)
Location: include/crypto/skcipher.h:600
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:gcm_dec_hash_continue
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (ffffffff8143cf8b)
Location: include/crypto/skcipher.h:600
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
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
In fs/crypto/crypto.c (ffffffff812fa4fa)
Location: include/crypto/skcipher.h:601
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_do_page_crypto
```
```
In fs/crypto/fname.c (ffffffff812fae86)
Location: include/crypto/skcipher.h:601
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_encrypt
```
```
In fs/crypto/keyinfo.c (ffffffff812fba0a)
Location: include/crypto/skcipher.h:601
Inline: True
Inline callers:
  - fs/crypto/keyinfo.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff813b7a20)
Location: include/crypto/skcipher.h:601
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/keystore.c (ffffffff813bab40)
Location: include/crypto/skcipher.h:601
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff813eff19)
Location: include/crypto/skcipher.h:601
Inline: True
```
```
In crypto/seqiv.c (ffffffff8145e71d)
Location: include/crypto/skcipher.h:601
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/cts.c (ffffffff8146975f)
Location: include/crypto/skcipher.h:601
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:cts_cbc_encrypt
```
```
In crypto/xts.c (ffffffff8146a133)
Location: include/crypto/skcipher.h:601
Inline: True
Inline callers:
  - crypto/xts.c:pre_crypt
  - crypto/xts.c:pre_crypt
```
```
In crypto/ctr.c (ffffffff8146a86e)
Location: include/crypto/skcipher.h:601
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_crypt
```
```
In crypto/gcm.c (ffffffff8146b326)
Location: include/crypto/skcipher.h:601
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:gcm_dec_hash_continue
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (ffffffff8146fd5d)
Location: include/crypto/skcipher.h:601
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
In fs/crypto/crypto.c (ffffffff8130f85b)
Location: include/crypto/skcipher.h:670
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_do_page_crypto
```
```
In fs/crypto/fname.c (ffffffff8131023d)
Location: include/crypto/skcipher.h:670
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_encrypt
```
```
In fs/crypto/keyinfo.c (ffffffff81310f67)
Location: include/crypto/skcipher.h:670
Inline: True
Inline callers:
  - fs/crypto/keyinfo.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff813d0f3d)
Location: include/crypto/skcipher.h:670
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/keystore.c (ffffffff813d40f5)
Location: include/crypto/skcipher.h:670
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff8140b1fc)
Location: include/crypto/skcipher.h:670
Inline: True
```
```
In crypto/seqiv.c (ffffffff8147c010)
Location: include/crypto/skcipher.h:670
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/cts.c (ffffffff81487497)
Location: include/crypto/skcipher.h:670
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:cts_cbc_encrypt
```
```
In crypto/xts.c (ffffffff8148788a)
Location: include/crypto/skcipher.h:670
Inline: True
```
```
In crypto/ctr.c (ffffffff814880de)
Location: include/crypto/skcipher.h:670
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_crypt
```
```
In crypto/gcm.c (ffffffff814895b7)
Location: include/crypto/skcipher.h:670
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_copy_src_to_dst
  - crypto/gcm.c:gcm_dec_hash_continue
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (ffffffff814900e0)
Location: include/crypto/skcipher.h:670
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
In fs/crypto/crypto.c (ffffffff81336d3b)
Location: include/crypto/skcipher.h:577
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
```
```
In fs/crypto/fname.c (ffffffff813376ae)
Location: include/crypto/skcipher.h:577
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_encrypt
```
```
In fs/crypto/keyinfo.c (ffffffff8133868b)
Location: include/crypto/skcipher.h:577
Inline: True
Inline callers:
  - fs/crypto/keyinfo.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff813fbb1b)
Location: include/crypto/skcipher.h:577
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/keystore.c (ffffffff813feb6a)
Location: include/crypto/skcipher.h:577
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff81437fde)
Location: include/crypto/skcipher.h:577
Inline: True
```
```
In crypto/seqiv.c (ffffffff814aa3af)
Location: include/crypto/skcipher.h:577
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/cts.c (ffffffff814b51cf)
Location: include/crypto/skcipher.h:577
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:cts_cbc_encrypt
```
```
In crypto/xts.c (ffffffff814b5562)
Location: include/crypto/skcipher.h:577
Inline: True
```
```
In crypto/ctr.c (ffffffff814b5b62)
Location: include/crypto/skcipher.h:577
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_crypt
```
```
In crypto/gcm.c (ffffffff814b6261)
Location: include/crypto/skcipher.h:577
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_copy_src_to_dst
  - crypto/gcm.c:gcm_dec_hash_continue
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (ffffffff814bd2e0)
Location: include/crypto/skcipher.h:577
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
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
In fs/crypto/crypto.c (ffffffff8134a90f)
Location: include/crypto/skcipher.h:607
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
```
```
In fs/crypto/fname.c (ffffffff8134b26c)
Location: include/crypto/skcipher.h:607
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_encrypt
```
```
In fs/crypto/keysetup_v1.c (ffffffff8134e498)
Location: include/crypto/skcipher.h:607
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff81415975)
Location: include/crypto/skcipher.h:607
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/keystore.c (ffffffff81418a5a)
Location: include/crypto/skcipher.h:607
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff81451d9e)
Location: include/crypto/skcipher.h:607
Inline: True
```
```
In crypto/seqiv.c (ffffffff814c506f)
Location: include/crypto/skcipher.h:607
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/cts.c (ffffffff814cdf5f)
Location: include/crypto/skcipher.h:607
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:cts_cbc_encrypt
```
```
In crypto/xts.c (ffffffff814ce0bb)
Location: include/crypto/skcipher.h:607
Inline: True
Inline callers:
  - crypto/xts.c:init_crypt
  - crypto/xts.c:cts_final
```
```
In crypto/ctr.c (ffffffff814ced62)
Location: include/crypto/skcipher.h:607
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_crypt
```
```
In crypto/gcm.c (ffffffff814cf461)
Location: include/crypto/skcipher.h:607
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_copy_src_to_dst
  - crypto/gcm.c:gcm_dec_hash_continue
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (ffffffff814d5f60)
Location: include/crypto/skcipher.h:607
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
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
In fs/crypto/crypto.c (ffffffff8139006f)
Location: include/crypto/skcipher.h:572
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
```
```
In fs/crypto/fname.c (ffffffff813908ab)
Location: include/crypto/skcipher.h:572
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_decrypt
  - fs/crypto/fname.c:fscrypt_fname_encrypt
```
```
In fs/crypto/keysetup_v1.c (ffffffff81394233)
Location: include/crypto/skcipher.h:572
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff81463ce4)
Location: include/crypto/skcipher.h:572
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/keystore.c (ffffffff81466cbd)
Location: include/crypto/skcipher.h:572
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff814a4af3)
Location: include/crypto/skcipher.h:572
Inline: True
```
```
In crypto/seqiv.c (ffffffff81523f7f)
Location: include/crypto/skcipher.h:572
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/cts.c (ffffffff8152d30e)
Location: include/crypto/skcipher.h:572
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:cts_cbc_encrypt
```
```
In crypto/xts.c (ffffffff8152d908)
Location: include/crypto/skcipher.h:572
Inline: True
Inline callers:
  - crypto/xts.c:decrypt
  - crypto/xts.c:encrypt
  - crypto/xts.c:cts_final
```
```
In crypto/ctr.c (ffffffff8152e035)
Location: include/crypto/skcipher.h:572
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_crypt
```
```
In crypto/gcm.c (ffffffff8152e681)
Location: include/crypto/skcipher.h:572
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_copy_src_to_dst
  - crypto/gcm.c:gcm_dec_hash_continue
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (ffffffff81535b14)
Location: include/crypto/skcipher.h:572
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
```
```
In block/blk-crypto-fallback.c (ffffffff815824a0)
Location: include/crypto/skcipher.h:572
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio
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
In fs/crypto/crypto.c (ffffffff813a16af)
Location: include/crypto/skcipher.h:572
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
```
```
In fs/crypto/fname.c (ffffffff813a1d2b)
Location: include/crypto/skcipher.h:572
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_decrypt
  - fs/crypto/fname.c:fscrypt_fname_encrypt
```
```
In fs/crypto/keysetup_v1.c (ffffffff813a56f3)
Location: include/crypto/skcipher.h:572
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff8147f4a4)
Location: include/crypto/skcipher.h:572
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/keystore.c (ffffffff81481ebd)
Location: include/crypto/skcipher.h:572
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff814c22f3)
Location: include/crypto/skcipher.h:572
Inline: True
```
```
In crypto/seqiv.c (ffffffff81540e80)
Location: include/crypto/skcipher.h:572
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/cts.c (ffffffff8154a37e)
Location: include/crypto/skcipher.h:572
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:cts_cbc_encrypt
```
```
In crypto/xts.c (ffffffff8154a838)
Location: include/crypto/skcipher.h:572
Inline: True
Inline callers:
  - crypto/xts.c:xts_decrypt
  - crypto/xts.c:xts_encrypt
  - crypto/xts.c:xts_cts_final
```
```
In crypto/ctr.c (ffffffff8154b055)
Location: include/crypto/skcipher.h:572
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_crypt
```
```
In crypto/gcm.c (ffffffff8154b621)
Location: include/crypto/skcipher.h:572
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_copy_src_to_dst
  - crypto/gcm.c:gcm_dec_hash_continue
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (ffffffff81552a84)
Location: include/crypto/skcipher.h:572
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
```
```
In block/blk-crypto-fallback.c (ffffffff8159f445)
Location: include/crypto/skcipher.h:572
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio
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
In fs/crypto/crypto.c (ffffffff813a8819)
Location: include/crypto/skcipher.h:574
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
```
```
In fs/crypto/fname.c (ffffffff813a8ecb)
Location: include/crypto/skcipher.h:574
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_decrypt
  - fs/crypto/fname.c:fscrypt_fname_encrypt
```
```
In fs/crypto/keysetup_v1.c (ffffffff813ac7d3)
Location: include/crypto/skcipher.h:574
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff81484e3d)
Location: include/crypto/skcipher.h:574
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/keystore.c (ffffffff81487923)
Location: include/crypto/skcipher.h:574
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff814c8906)
Location: include/crypto/skcipher.h:574
Inline: True
```
```
In crypto/seqiv.c (ffffffff815494ef)
Location: include/crypto/skcipher.h:574
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/cts.c (ffffffff815529b1)
Location: include/crypto/skcipher.h:574
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:cts_cbc_encrypt
```
```
In crypto/xts.c (ffffffff81552e58)
Location: include/crypto/skcipher.h:574
Inline: True
Inline callers:
  - crypto/xts.c:xts_decrypt
  - crypto/xts.c:xts_encrypt
  - crypto/xts.c:xts_cts_final
```
```
In crypto/ctr.c (ffffffff81553675)
Location: include/crypto/skcipher.h:574
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_crypt
```
```
In crypto/gcm.c (ffffffff81553c31)
Location: include/crypto/skcipher.h:574
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_copy_src_to_dst
  - crypto/gcm.c:gcm_dec_hash_continue
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (ffffffff8155b344)
Location: include/crypto/skcipher.h:574
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
```
```
In block/blk-crypto-fallback.c (ffffffff815a6150)
Location: include/crypto/skcipher.h:574
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio
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
In fs/crypto/crypto.c (ffffffff813f7f59)
Location: include/crypto/skcipher.h:574
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
```
```
In fs/crypto/fname.c (ffffffff813f865b)
Location: include/crypto/skcipher.h:574
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_decrypt
  - fs/crypto/fname.c:fscrypt_fname_encrypt
```
```
In fs/crypto/keysetup_v1.c (ffffffff813fc143)
Location: include/crypto/skcipher.h:574
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff814dc4bd)
Location: include/crypto/skcipher.h:574
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/keystore.c (ffffffff814df0f5)
Location: include/crypto/skcipher.h:574
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff815213cf)
Location: include/crypto/skcipher.h:574
Inline: True
```
```
In crypto/seqiv.c (ffffffff815a9ccf)
Location: include/crypto/skcipher.h:574
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/cts.c (ffffffff815b3a0c)
Location: include/crypto/skcipher.h:574
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:cts_cbc_encrypt
```
```
In crypto/xts.c (ffffffff815b3e88)
Location: include/crypto/skcipher.h:574
Inline: True
Inline callers:
  - crypto/xts.c:xts_decrypt
  - crypto/xts.c:xts_encrypt
  - crypto/xts.c:xts_cts_final
```
```
In crypto/ctr.c (ffffffff815b46a5)
Location: include/crypto/skcipher.h:574
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_crypt
```
```
In crypto/gcm.c (ffffffff815b4c61)
Location: include/crypto/skcipher.h:574
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_copy_src_to_dst
  - crypto/gcm.c:gcm_dec_hash_continue
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (ffffffff815bbce4)
Location: include/crypto/skcipher.h:574
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
```
```
In block/blk-crypto-fallback.c (ffffffff8160ec70)
Location: include/crypto/skcipher.h:574
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio
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
In fs/crypto/crypto.c (ffffffff8146acf9)
Location: include/crypto/skcipher.h:578
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
```
```
In fs/crypto/fname.c (ffffffff8146b376)
Location: include/crypto/skcipher.h:578
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_decrypt
  - fs/crypto/fname.c:fscrypt_fname_encrypt
```
```
In fs/crypto/keysetup_v1.c (ffffffff8146f5b8)
Location: include/crypto/skcipher.h:578
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff8156a2c5)
Location: include/crypto/skcipher.h:578
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/keystore.c (ffffffff8156d15b)
Location: include/crypto/skcipher.h:578
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff815b4c91)
Location: include/crypto/skcipher.h:578
Inline: True
```
```
In crypto/seqiv.c (ffffffff816511dd)
Location: include/crypto/skcipher.h:578
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/cts.c (ffffffff8165c795)
Location: include/crypto/skcipher.h:578
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:cts_cbc_encrypt
```
```
In crypto/xts.c (ffffffff8165cc87)
Location: include/crypto/skcipher.h:578
Inline: True
Inline callers:
  - crypto/xts.c:xts_decrypt
  - crypto/xts.c:xts_encrypt
  - crypto/xts.c:xts_cts_final
```
```
In crypto/ctr.c (ffffffff8165d555)
Location: include/crypto/skcipher.h:578
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_crypt
```
```
In crypto/gcm.c (ffffffff8165dc03)
Location: include/crypto/skcipher.h:578
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_copy_src_to_dst
  - crypto/gcm.c:gcm_dec_hash_continue
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (ffffffff816655ae)
Location: include/crypto/skcipher.h:578
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
```
```
In block/blk-crypto-fallback.c (ffffffff816c34c8)
Location: include/crypto/skcipher.h:578
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio
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
In fs/crypto/crypto.c (ffffffff814fbe21)
Location: include/crypto/skcipher.h:578
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
```
```
In fs/crypto/fname.c (ffffffff814fc7f7)
Location: include/crypto/skcipher.h:578
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_decrypt
  - fs/crypto/fname.c:fscrypt_fname_encrypt
```
```
In fs/crypto/keysetup_v1.c (ffffffff81500d38)
Location: include/crypto/skcipher.h:578
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff8160e055)
Location: include/crypto/skcipher.h:578
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/keystore.c (ffffffff816118de)
Location: include/crypto/skcipher.h:578
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff8165fc71)
Location: include/crypto/skcipher.h:578
Inline: True
```
```
In crypto/seqiv.c (ffffffff8170aa5d)
Location: include/crypto/skcipher.h:578
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/cts.c (ffffffff817161b5)
Location: include/crypto/skcipher.h:578
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:cts_cbc_encrypt
```
```
In crypto/xts.c (ffffffff817166d7)
Location: include/crypto/skcipher.h:578
Inline: True
Inline callers:
  - crypto/xts.c:xts_decrypt
  - crypto/xts.c:xts_encrypt
  - crypto/xts.c:xts_cts_final
```
```
In crypto/ctr.c (ffffffff81717185)
Location: include/crypto/skcipher.h:578
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_crypt
```
```
In crypto/gcm.c (ffffffff817177b3)
Location: include/crypto/skcipher.h:578
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_copy_src_to_dst
  - crypto/gcm.c:gcm_dec_hash_continue
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (ffffffff817203be)
Location: include/crypto/skcipher.h:578
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
```
```
In block/blk-crypto-fallback.c (ffffffff81784957)
Location: include/crypto/skcipher.h:578
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio
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
In fs/crypto/crypto.c (ffffffff81533151)
Location: include/crypto/skcipher.h:600
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
```
```
In fs/crypto/fname.c (ffffffff81533d67)
Location: include/crypto/skcipher.h:600
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_decrypt
  - fs/crypto/fname.c:fscrypt_fname_encrypt
```
```
In fs/crypto/keysetup_v1.c (ffffffff815383c5)
Location: include/crypto/skcipher.h:600
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff81645ecb)
Location: include/crypto/skcipher.h:600
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/keystore.c (ffffffff8164982e)
Location: include/crypto/skcipher.h:600
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff816985d7)
Location: include/crypto/skcipher.h:600
Inline: True
```
```
In crypto/seqiv.c (ffffffff817442ad)
Location: include/crypto/skcipher.h:600
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/cts.c (ffffffff81751ab5)
Location: include/crypto/skcipher.h:600
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:cts_cbc_encrypt
```
```
In crypto/xts.c (ffffffff81751fa7)
Location: include/crypto/skcipher.h:600
Inline: True
Inline callers:
  - crypto/xts.c:xts_decrypt
  - crypto/xts.c:xts_encrypt
  - crypto/xts.c:xts_cts_final
```
```
In crypto/ctr.c (ffffffff81752a95)
Location: include/crypto/skcipher.h:600
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_crypt
```
```
In crypto/gcm.c (ffffffff817531a3)
Location: include/crypto/skcipher.h:600
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_copy_src_to_dst
  - crypto/gcm.c:gcm_dec_hash_continue
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (ffffffff8175bcb3)
Location: include/crypto/skcipher.h:600
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
```
```
In block/blk-crypto-fallback.c (ffffffff817c4cb7)
Location: include/crypto/skcipher.h:600
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio
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
In fs/crypto/crypto.c (ffffffff8156804d)
Location: include/crypto/skcipher.h:945
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_crypt_data_unit
```
```
In fs/crypto/fname.c (ffffffff81568cf7)
Location: include/crypto/skcipher.h:945
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_decrypt
  - fs/crypto/fname.c:fscrypt_fname_encrypt
```
```
In fs/crypto/keysetup_v1.c (ffffffff8156d515)
Location: include/crypto/skcipher.h:945
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff8167f38b)
Location: include/crypto/skcipher.h:945
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/keystore.c (ffffffff81682cfe)
Location: include/crypto/skcipher.h:945
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff816d4c57)
Location: include/crypto/skcipher.h:945
Inline: True
```
```
In crypto/seqiv.c (ffffffff8178686d)
Location: include/crypto/skcipher.h:945
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/cts.c (ffffffff81793935)
Location: include/crypto/skcipher.h:945
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:cts_cbc_encrypt
```
```
In crypto/xts.c (ffffffff81793e27)
Location: include/crypto/skcipher.h:945
Inline: True
Inline callers:
  - crypto/xts.c:xts_decrypt
  - crypto/xts.c:xts_encrypt
  - crypto/xts.c:xts_cts_final
```
```
In crypto/ctr.c (ffffffff81794a05)
Location: include/crypto/skcipher.h:945
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_crypt
```
```
In crypto/gcm.c (ffffffff81795073)
Location: include/crypto/skcipher.h:945
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_copy_src_to_dst
  - crypto/gcm.c:gcm_dec_hash_continue
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (ffffffff8179dbb3)
Location: include/crypto/skcipher.h:945
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
```
```
In block/blk-crypto-fallback.c (ffffffff818099a7)
Location: include/crypto/skcipher.h:945
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio
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
In fs/crypto/crypto.c (ffff80001040b0c4)
Location: include/crypto/skcipher.h:607
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
```
```
In fs/crypto/fname.c (ffff80001040bc60)
Location: include/crypto/skcipher.h:607
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_encrypt
```
```
In fs/crypto/keysetup_v1.c (ffff80001040f6b0)
Location: include/crypto/skcipher.h:607
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffff8000104f6f3c)
Location: include/crypto/skcipher.h:607
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/keystore.c (ffff8000104fa264)
Location: include/crypto/skcipher.h:607
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (ffff80001053d5a4)
Location: include/crypto/skcipher.h:607
Inline: True
```
```
In crypto/seqiv.c (ffff8000105bfc1c)
Location: include/crypto/skcipher.h:607
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/cts.c (ffff8000105c9d74)
Location: include/crypto/skcipher.h:607
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:cts_cbc_encrypt
```
```
In crypto/xts.c (ffff8000105c9fe0)
Location: include/crypto/skcipher.h:607
Inline: True
Inline callers:
  - crypto/xts.c:init_crypt
  - crypto/xts.c:cts_final
```
```
In crypto/ctr.c (ffff8000105cacb4)
Location: include/crypto/skcipher.h:607
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_crypt
```
```
In crypto/gcm.c (ffff8000105cb45c)
Location: include/crypto/skcipher.h:607
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_copy_src_to_dst
  - crypto/gcm.c:gcm_dec_hash_continue
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (ffff8000105d1e1c)
Location: include/crypto/skcipher.h:607
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
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
In fs/crypto/crypto.c (c05d8260)
Location: include/crypto/skcipher.h:607
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
```
```
In fs/crypto/fname.c (c05d8a54)
Location: include/crypto/skcipher.h:607
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_decrypt
  - fs/crypto/fname.c:fname_encrypt
```
```
In fs/crypto/keysetup_v1.c (c05dc394)
Location: include/crypto/skcipher.h:607
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
```
```
In fs/ecryptfs/crypto.c (c06b4c34)
Location: include/crypto/skcipher.h:607
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_extent
```
```
In fs/ecryptfs/keystore.c (c06b79b8)
Location: include/crypto/skcipher.h:607
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (c06f2fac)
Location: include/crypto/skcipher.h:607
Inline: True
```
```
In crypto/seqiv.c (c076d864)
Location: include/crypto/skcipher.h:607
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/cts.c (c0777a2c)
Location: include/crypto/skcipher.h:607
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:cts_cbc_encrypt
```
```
In crypto/xts.c (c0777afc)
Location: include/crypto/skcipher.h:607
Inline: True
Inline callers:
  - crypto/xts.c:init_crypt
  - crypto/xts.c:cts_final
```
```
In crypto/ctr.c (c0778890)
Location: include/crypto/skcipher.h:607
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_crypt
```
```
In crypto/gcm.c (c0778f5c)
Location: include/crypto/skcipher.h:607
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_copy_src_to_dst
  - crypto/gcm.c:gcm_dec_hash_continue
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (c077f6c0)
Location: include/crypto/skcipher.h:607
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
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
In fs/crypto/crypto.c (c000000000517b90)
Location: include/crypto/skcipher.h:607
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
```
```
In fs/crypto/fname.c (c000000000518990)
Location: include/crypto/skcipher.h:607
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_encrypt
```
```
In fs/crypto/keysetup_v1.c (c00000000051d160)
Location: include/crypto/skcipher.h:607
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (c000000000638258)
Location: include/crypto/skcipher.h:607
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/keystore.c (c00000000063c8d0)
Location: include/crypto/skcipher.h:607
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (c00000000068cad8)
Location: include/crypto/skcipher.h:607
Inline: True
```
```
In crypto/seqiv.c (c000000000747a6c)
Location: include/crypto/skcipher.h:607
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/cts.c (c000000000754780)
Location: include/crypto/skcipher.h:607
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:cts_cbc_encrypt
```
```
In crypto/xts.c (c0000000007549a0)
Location: include/crypto/skcipher.h:607
Inline: True
Inline callers:
  - crypto/xts.c:init_crypt
  - crypto/xts.c:cts_final
```
```
In crypto/ctr.c (c000000000755ac0)
Location: include/crypto/skcipher.h:607
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_crypt
```
```
In crypto/gcm.c (c000000000756498)
Location: include/crypto/skcipher.h:607
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_copy_src_to_dst
  - crypto/gcm.c:gcm_dec_hash_continue
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (c00000000075ede8)
Location: include/crypto/skcipher.h:607
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
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
In fs/crypto/crypto.c (ffffffe0002b4db6)
Location: include/crypto/skcipher.h:607
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
```
```
In fs/crypto/fname.c (ffffffe0002b56fe)
Location: include/crypto/skcipher.h:607
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_encrypt
```
```
In fs/crypto/keysetup_v1.c (ffffffe0002b8566)
Location: include/crypto/skcipher.h:607
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
```
```
In fs/ecryptfs/crypto.c (ffffffe000365b06)
Location: include/crypto/skcipher.h:607
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/keystore.c (ffffffe000368a16)
Location: include/crypto/skcipher.h:607
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffe00039a9f8)
Location: include/crypto/skcipher.h:607
Inline: True
```
```
In crypto/seqiv.c (ffffffe000404c6e)
Location: include/crypto/skcipher.h:607
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/cts.c (ffffffe00040dffc)
Location: include/crypto/skcipher.h:607
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:cts_cbc_encrypt
```
```
In crypto/xts.c (ffffffe00040e604)
Location: include/crypto/skcipher.h:607
Inline: True
Inline callers:
  - crypto/xts.c:init_crypt
  - crypto/xts.c:cts_final
```
```
In crypto/ctr.c (ffffffe00040f1b2)
Location: include/crypto/skcipher.h:607
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_crypt
```
```
In crypto/gcm.c (ffffffe00040f7ae)
Location: include/crypto/skcipher.h:607
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_copy_src_to_dst
  - crypto/gcm.c:gcm_dec_hash_continue
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (ffffffe0004155ac)
Location: include/crypto/skcipher.h:607
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
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
In fs/crypto/crypto.c (ffffffff81342eef)
Location: include/crypto/skcipher.h:607
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
```
```
In fs/crypto/fname.c (ffffffff8134384c)
Location: include/crypto/skcipher.h:607
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_encrypt
```
```
In fs/crypto/keysetup_v1.c (ffffffff81346a78)
Location: include/crypto/skcipher.h:607
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff8140df55)
Location: include/crypto/skcipher.h:607
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/keystore.c (ffffffff8141103a)
Location: include/crypto/skcipher.h:607
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff8144a37e)
Location: include/crypto/skcipher.h:607
Inline: True
```
```
In crypto/seqiv.c (ffffffff814bd64f)
Location: include/crypto/skcipher.h:607
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/cts.c (ffffffff814c653f)
Location: include/crypto/skcipher.h:607
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:cts_cbc_encrypt
```
```
In crypto/xts.c (ffffffff814c669b)
Location: include/crypto/skcipher.h:607
Inline: True
Inline callers:
  - crypto/xts.c:init_crypt
  - crypto/xts.c:cts_final
```
```
In crypto/ctr.c (ffffffff814c7342)
Location: include/crypto/skcipher.h:607
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_crypt
```
```
In crypto/gcm.c (ffffffff814c7a41)
Location: include/crypto/skcipher.h:607
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_copy_src_to_dst
  - crypto/gcm.c:gcm_dec_hash_continue
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (ffffffff814ce540)
Location: include/crypto/skcipher.h:607
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
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
In fs/crypto/crypto.c (ffffffff81333bcf)
Location: include/crypto/skcipher.h:607
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
```
```
In fs/crypto/fname.c (ffffffff8133452c)
Location: include/crypto/skcipher.h:607
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_encrypt
```
```
In fs/crypto/keysetup_v1.c (ffffffff81337758)
Location: include/crypto/skcipher.h:607
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff813fe9d5)
Location: include/crypto/skcipher.h:607
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/keystore.c (ffffffff81401aba)
Location: include/crypto/skcipher.h:607
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff8143adce)
Location: include/crypto/skcipher.h:607
Inline: True
```
```
In crypto/seqiv.c (ffffffff814ae06f)
Location: include/crypto/skcipher.h:607
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/cts.c (ffffffff814b6f5f)
Location: include/crypto/skcipher.h:607
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:cts_cbc_encrypt
```
```
In crypto/xts.c (ffffffff814b70bb)
Location: include/crypto/skcipher.h:607
Inline: True
Inline callers:
  - crypto/xts.c:init_crypt
  - crypto/xts.c:cts_final
```
```
In crypto/ctr.c (ffffffff814b7d62)
Location: include/crypto/skcipher.h:607
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_crypt
```
```
In crypto/gcm.c (ffffffff814b8461)
Location: include/crypto/skcipher.h:607
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_copy_src_to_dst
  - crypto/gcm.c:gcm_dec_hash_continue
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (ffffffff814bef60)
Location: include/crypto/skcipher.h:607
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
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
In fs/crypto/crypto.c (ffffffff813409bf)
Location: include/crypto/skcipher.h:607
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
```
```
In fs/crypto/fname.c (ffffffff8134131c)
Location: include/crypto/skcipher.h:607
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_encrypt
```
```
In fs/crypto/keysetup_v1.c (ffffffff81344548)
Location: include/crypto/skcipher.h:607
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff8140b2d5)
Location: include/crypto/skcipher.h:607
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/keystore.c (ffffffff8140e3ba)
Location: include/crypto/skcipher.h:607
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff8144641e)
Location: include/crypto/skcipher.h:607
Inline: True
```
```
In crypto/seqiv.c (ffffffff814b96df)
Location: include/crypto/skcipher.h:607
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/cts.c (ffffffff814c25cf)
Location: include/crypto/skcipher.h:607
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:cts_cbc_encrypt
```
```
In crypto/xts.c (ffffffff814c272b)
Location: include/crypto/skcipher.h:607
Inline: True
Inline callers:
  - crypto/xts.c:init_crypt
  - crypto/xts.c:cts_final
```
```
In crypto/ctr.c (ffffffff814c33d2)
Location: include/crypto/skcipher.h:607
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_crypt
```
```
In crypto/gcm.c (ffffffff814c3ad1)
Location: include/crypto/skcipher.h:607
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_copy_src_to_dst
  - crypto/gcm.c:gcm_dec_hash_continue
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (ffffffff814ca5d0)
Location: include/crypto/skcipher.h:607
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
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
In fs/crypto/crypto.c (ffffffff81353cbf)
Location: include/crypto/skcipher.h:607
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
```
```
In fs/crypto/fname.c (ffffffff8135461c)
Location: include/crypto/skcipher.h:607
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_encrypt
```
```
In fs/crypto/keysetup_v1.c (ffffffff81357828)
Location: include/crypto/skcipher.h:607
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff81420f75)
Location: include/crypto/skcipher.h:607
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/keystore.c (ffffffff8142402a)
Location: include/crypto/skcipher.h:607
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff8145d74e)
Location: include/crypto/skcipher.h:607
Inline: True
```
```
In crypto/seqiv.c (ffffffff814d217f)
Location: include/crypto/skcipher.h:607
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/cts.c (ffffffff814db09f)
Location: include/crypto/skcipher.h:607
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:cts_cbc_encrypt
```
```
In crypto/xts.c (ffffffff814db1fb)
Location: include/crypto/skcipher.h:607
Inline: True
Inline callers:
  - crypto/xts.c:init_crypt
  - crypto/xts.c:cts_final
```
```
In crypto/ctr.c (ffffffff814dbea2)
Location: include/crypto/skcipher.h:607
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_crypt
```
```
In crypto/gcm.c (ffffffff814dc5a1)
Location: include/crypto/skcipher.h:607
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_copy_src_to_dst
  - crypto/gcm.c:gcm_dec_hash_continue
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (ffffffff814e30a0)
Location: include/crypto/skcipher.h:607
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
```
</details>
</li>
</ul>

## Differences
