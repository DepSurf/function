# Function: <code>skcipher_request_set_callback</code>

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
In fs/crypto/crypto.c (ffffffff812889c0)
Location: include/crypto/skcipher.h:540
Inline: True
```
```
In fs/crypto/fname.c (ffffffff81289863)
Location: include/crypto/skcipher.h:540
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_decrypt
  - fs/crypto/fname.c:fname_encrypt
```
```
In fs/crypto/keyinfo.c (ffffffff8128a1b2)
Location: include/crypto/skcipher.h:540
Inline: True
Inline callers:
  - fs/crypto/keyinfo.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff813395ce)
Location: include/crypto/skcipher.h:540
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/keystore.c (ffffffff8133c6fe)
Location: include/crypto/skcipher.h:540
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/big_key.c (ffffffff8136b816)
Location: include/crypto/skcipher.h:540
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_crypt
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff8136e440)
Location: include/crypto/skcipher.h:540
Inline: True
```
```
In crypto/seqiv.c (ffffffff813de960)
Location: include/crypto/skcipher.h:540
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/cts.c (ffffffff813e79aa)
Location: include/crypto/skcipher.h:540
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
In crypto/ctr.c (ffffffff813e88cd)
Location: include/crypto/skcipher.h:540
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_crypt
```
```
In crypto/drbg.c (ffffffff813eed79)
Location: include/crypto/skcipher.h:540
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
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
In fs/crypto/crypto.c (ffffffff8129d5ea)
Location: include/crypto/skcipher.h:540
Inline: True
```
```
In fs/crypto/fname.c (ffffffff8129e523)
Location: include/crypto/skcipher.h:540
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_decrypt
  - fs/crypto/fname.c:fname_encrypt
```
```
In fs/crypto/keyinfo.c (ffffffff8129eef2)
Location: include/crypto/skcipher.h:540
Inline: True
Inline callers:
  - fs/crypto/keyinfo.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff8134f36e)
Location: include/crypto/skcipher.h:540
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/keystore.c (ffffffff8135248e)
Location: include/crypto/skcipher.h:540
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/big_key.c (ffffffff81382036)
Location: include/crypto/skcipher.h:540
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_crypt
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff81384c60)
Location: include/crypto/skcipher.h:540
Inline: True
```
```
In crypto/seqiv.c (ffffffff813f6f00)
Location: include/crypto/skcipher.h:540
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/cts.c (ffffffff814007da)
Location: include/crypto/skcipher.h:540
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
In crypto/xts.c (ffffffff81401128)
Location: include/crypto/skcipher.h:540
Inline: True
Inline callers:
  - crypto/xts.c:init_crypt
```
```
In crypto/ctr.c (ffffffff81401edd)
Location: include/crypto/skcipher.h:540
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_crypt
```
```
In crypto/drbg.c (ffffffff814085bf)
Location: include/crypto/skcipher.h:540
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
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
In fs/crypto/crypto.c (ffffffff812ac372)
Location: include/crypto/skcipher.h:574
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_do_page_crypto
```
```
In fs/crypto/fname.c (ffffffff812acfe9)
Location: include/crypto/skcipher.h:574
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_decrypt
  - fs/crypto/fname.c:fname_encrypt
```
```
In fs/crypto/keyinfo.c (ffffffff812ad956)
Location: include/crypto/skcipher.h:574
Inline: True
Inline callers:
  - fs/crypto/keyinfo.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff81363e0f)
Location: include/crypto/skcipher.h:574
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/keystore.c (ffffffff81367221)
Location: include/crypto/skcipher.h:574
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/big_key.c (ffffffff813966cf)
Location: include/crypto/skcipher.h:574
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_crypt
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff813992d7)
Location: include/crypto/skcipher.h:574
Inline: True
```
```
In crypto/seqiv.c (ffffffff81403302)
Location: include/crypto/skcipher.h:574
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/cts.c (ffffffff8140e0ab)
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
In crypto/xts.c (ffffffff8140e4b9)
Location: include/crypto/skcipher.h:574
Inline: True
Inline callers:
  - crypto/xts.c:init_crypt
```
```
In crypto/ctr.c (ffffffff8140f32d)
Location: include/crypto/skcipher.h:574
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_crypt
```
```
In crypto/drbg.c (ffffffff81415caf)
Location: include/crypto/skcipher.h:574
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
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
In fs/crypto/crypto.c (ffffffff812cfb7e)
Location: include/crypto/skcipher.h:574
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_do_page_crypto
```
```
In fs/crypto/fname.c (ffffffff812d0793)
Location: include/crypto/skcipher.h:574
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_decrypt
  - fs/crypto/fname.c:fname_encrypt
```
```
In fs/crypto/keyinfo.c (ffffffff812d0e17)
Location: include/crypto/skcipher.h:574
Inline: True
Inline callers:
  - fs/crypto/keyinfo.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff81388b7f)
Location: include/crypto/skcipher.h:574
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/keystore.c (ffffffff8138bea4)
Location: include/crypto/skcipher.h:574
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff813beaed)
Location: include/crypto/skcipher.h:574
Inline: True
```
```
In crypto/seqiv.c (ffffffff8142b9f2)
Location: include/crypto/skcipher.h:574
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/cts.c (ffffffff81436b5b)
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
In crypto/xts.c (ffffffff81436f79)
Location: include/crypto/skcipher.h:574
Inline: True
Inline callers:
  - crypto/xts.c:init_crypt
```
```
In crypto/ctr.c (ffffffff81437efd)
Location: include/crypto/skcipher.h:574
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_crypt
```
```
In crypto/gcm.c (ffffffff81438ff9)
Location: include/crypto/skcipher.h:574
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:gcm_dec_hash_continue
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (ffffffff81440487)
Location: include/crypto/skcipher.h:574
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
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
In fs/crypto/crypto.c (ffffffff812fa478)
Location: include/crypto/skcipher.h:575
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_do_page_crypto
```
```
In fs/crypto/fname.c (ffffffff812fae64)
Location: include/crypto/skcipher.h:575
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_encrypt
```
```
In fs/crypto/keyinfo.c (ffffffff812fb9aa)
Location: include/crypto/skcipher.h:575
Inline: True
Inline callers:
  - fs/crypto/keyinfo.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff813b79df)
Location: include/crypto/skcipher.h:575
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/keystore.c (ffffffff813bab25)
Location: include/crypto/skcipher.h:575
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff813ef931)
Location: include/crypto/skcipher.h:575
Inline: True
```
```
In crypto/seqiv.c (ffffffff8145e6fe)
Location: include/crypto/skcipher.h:575
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/cts.c (ffffffff814696fb)
Location: include/crypto/skcipher.h:575
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
In crypto/xts.c (ffffffff814698d0)
Location: include/crypto/skcipher.h:575
Inline: True
Inline callers:
  - crypto/xts.c:init_crypt
```
```
In crypto/ctr.c (ffffffff8146a855)
Location: include/crypto/skcipher.h:575
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_crypt
```
```
In crypto/gcm.c (ffffffff8146b306)
Location: include/crypto/skcipher.h:575
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:gcm_dec_hash_continue
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (ffffffff81473370)
Location: include/crypto/skcipher.h:575
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
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
In fs/crypto/crypto.c (ffffffff8130f7ac)
Location: include/crypto/skcipher.h:644
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_do_page_crypto
```
```
In fs/crypto/fname.c (ffffffff8131021f)
Location: include/crypto/skcipher.h:644
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_encrypt
```
```
In fs/crypto/keyinfo.c (ffffffff81310efa)
Location: include/crypto/skcipher.h:644
Inline: True
Inline callers:
  - fs/crypto/keyinfo.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff813d0ef3)
Location: include/crypto/skcipher.h:644
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/keystore.c (ffffffff813d40e5)
Location: include/crypto/skcipher.h:644
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff8140ab81)
Location: include/crypto/skcipher.h:644
Inline: True
```
```
In crypto/seqiv.c (ffffffff8147bffc)
Location: include/crypto/skcipher.h:644
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/cts.c (ffffffff81487430)
Location: include/crypto/skcipher.h:644
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
In crypto/xts.c (ffffffff81487878)
Location: include/crypto/skcipher.h:644
Inline: True
```
```
In crypto/ctr.c (ffffffff814880c4)
Location: include/crypto/skcipher.h:644
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_crypt
```
```
In crypto/gcm.c (ffffffff814895a6)
Location: include/crypto/skcipher.h:644
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_copy_src_to_dst
  - crypto/gcm.c:gcm_dec_hash_continue
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (ffffffff8148f8e7)
Location: include/crypto/skcipher.h:644
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
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
In fs/crypto/crypto.c (ffffffff81336c8d)
Location: include/crypto/skcipher.h:551
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
```
```
In fs/crypto/fname.c (ffffffff81337688)
Location: include/crypto/skcipher.h:551
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_encrypt
```
```
In fs/crypto/keyinfo.c (ffffffff81338629)
Location: include/crypto/skcipher.h:551
Inline: True
Inline callers:
  - fs/crypto/keyinfo.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff813fbada)
Location: include/crypto/skcipher.h:551
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/keystore.c (ffffffff813feb4f)
Location: include/crypto/skcipher.h:551
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff81437e15)
Location: include/crypto/skcipher.h:551
Inline: True
```
```
In crypto/seqiv.c (ffffffff814aa399)
Location: include/crypto/skcipher.h:551
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/cts.c (ffffffff814b5165)
Location: include/crypto/skcipher.h:551
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
In crypto/xts.c (ffffffff814b5550)
Location: include/crypto/skcipher.h:551
Inline: True
```
```
In crypto/ctr.c (ffffffff814b5b4d)
Location: include/crypto/skcipher.h:551
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_crypt
```
```
In crypto/gcm.c (ffffffff814b6250)
Location: include/crypto/skcipher.h:551
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_copy_src_to_dst
  - crypto/gcm.c:gcm_dec_hash_continue
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (ffffffff814be27c)
Location: include/crypto/skcipher.h:551
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
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
In fs/crypto/crypto.c (ffffffff8134a85d)
Location: include/crypto/skcipher.h:581
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
```
```
In fs/crypto/fname.c (ffffffff8134b24b)
Location: include/crypto/skcipher.h:581
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_encrypt
```
```
In fs/crypto/keysetup_v1.c (ffffffff8134e438)
Location: include/crypto/skcipher.h:581
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff81415934)
Location: include/crypto/skcipher.h:581
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/keystore.c (ffffffff81418a3f)
Location: include/crypto/skcipher.h:581
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff81451bd5)
Location: include/crypto/skcipher.h:581
Inline: True
```
```
In crypto/seqiv.c (ffffffff814c5059)
Location: include/crypto/skcipher.h:581
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/cts.c (ffffffff814cdef5)
Location: include/crypto/skcipher.h:581
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
In crypto/xts.c (ffffffff814ce0a8)
Location: include/crypto/skcipher.h:581
Inline: True
Inline callers:
  - crypto/xts.c:init_crypt
  - crypto/xts.c:cts_final
```
```
In crypto/ctr.c (ffffffff814ced4d)
Location: include/crypto/skcipher.h:581
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_crypt
```
```
In crypto/gcm.c (ffffffff814cf450)
Location: include/crypto/skcipher.h:581
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_copy_src_to_dst
  - crypto/gcm.c:gcm_dec_hash_continue
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (ffffffff814d70cc)
Location: include/crypto/skcipher.h:581
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
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
In fs/crypto/crypto.c (ffffffff8138ffbd)
Location: include/crypto/skcipher.h:546
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
```
```
In fs/crypto/fname.c (ffffffff81390856)
Location: include/crypto/skcipher.h:546
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_decrypt
  - fs/crypto/fname.c:fscrypt_fname_encrypt
```
```
In fs/crypto/keysetup_v1.c (ffffffff813941d7)
Location: include/crypto/skcipher.h:546
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff81463cc6)
Location: include/crypto/skcipher.h:546
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/keystore.c (ffffffff81466ca2)
Location: include/crypto/skcipher.h:546
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff814a4351)
Location: include/crypto/skcipher.h:546
Inline: True
```
```
In crypto/seqiv.c (ffffffff81523f69)
Location: include/crypto/skcipher.h:546
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/cts.c (ffffffff8152d2a5)
Location: include/crypto/skcipher.h:546
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
In crypto/xts.c (ffffffff8152d8f8)
Location: include/crypto/skcipher.h:546
Inline: True
Inline callers:
  - crypto/xts.c:decrypt
  - crypto/xts.c:encrypt
  - crypto/xts.c:cts_final
```
```
In crypto/ctr.c (ffffffff8152e01c)
Location: include/crypto/skcipher.h:546
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_crypt
```
```
In crypto/gcm.c (ffffffff8152e670)
Location: include/crypto/skcipher.h:546
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_copy_src_to_dst
  - crypto/gcm.c:gcm_dec_hash_continue
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (ffffffff815338d9)
Location: include/crypto/skcipher.h:546
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
```
```
In block/blk-crypto-fallback.c (ffffffff81582048)
Location: include/crypto/skcipher.h:546
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_alloc_cipher_req
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
In fs/crypto/crypto.c (ffffffff813a15fd)
Location: include/crypto/skcipher.h:546
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
```
```
In fs/crypto/fname.c (ffffffff813a1cd6)
Location: include/crypto/skcipher.h:546
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_decrypt
  - fs/crypto/fname.c:fscrypt_fname_encrypt
```
```
In fs/crypto/keysetup_v1.c (ffffffff813a5697)
Location: include/crypto/skcipher.h:546
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff8147f486)
Location: include/crypto/skcipher.h:546
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/keystore.c (ffffffff81481ea2)
Location: include/crypto/skcipher.h:546
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff814c1b51)
Location: include/crypto/skcipher.h:546
Inline: True
```
```
In crypto/seqiv.c (ffffffff81540e80)
Location: include/crypto/skcipher.h:546
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/cts.c (ffffffff8154a315)
Location: include/crypto/skcipher.h:546
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
In crypto/xts.c (ffffffff8154a828)
Location: include/crypto/skcipher.h:546
Inline: True
Inline callers:
  - crypto/xts.c:xts_decrypt
  - crypto/xts.c:xts_encrypt
  - crypto/xts.c:xts_cts_final
```
```
In crypto/ctr.c (ffffffff8154b040)
Location: include/crypto/skcipher.h:546
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_crypt
```
```
In crypto/gcm.c (ffffffff8154b610)
Location: include/crypto/skcipher.h:546
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_copy_src_to_dst
  - crypto/gcm.c:gcm_dec_hash_continue
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (ffffffff81550829)
Location: include/crypto/skcipher.h:546
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
```
```
In block/blk-crypto-fallback.c (ffffffff8159f018)
Location: include/crypto/skcipher.h:546
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_alloc_cipher_req
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
In fs/crypto/crypto.c (ffffffff813a878b)
Location: include/crypto/skcipher.h:548
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
```
```
In fs/crypto/fname.c (ffffffff813a8e76)
Location: include/crypto/skcipher.h:548
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_decrypt
  - fs/crypto/fname.c:fscrypt_fname_encrypt
```
```
In fs/crypto/keysetup_v1.c (ffffffff813ac777)
Location: include/crypto/skcipher.h:548
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff81484e21)
Location: include/crypto/skcipher.h:548
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/keystore.c (ffffffff81487908)
Location: include/crypto/skcipher.h:548
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff814c7fd1)
Location: include/crypto/skcipher.h:548
Inline: True
```
```
In crypto/seqiv.c (ffffffff815494d9)
Location: include/crypto/skcipher.h:548
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/cts.c (ffffffff81552945)
Location: include/crypto/skcipher.h:548
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
In crypto/xts.c (ffffffff81552e48)
Location: include/crypto/skcipher.h:548
Inline: True
Inline callers:
  - crypto/xts.c:xts_decrypt
  - crypto/xts.c:xts_encrypt
  - crypto/xts.c:xts_cts_final
```
```
In crypto/ctr.c (ffffffff81553660)
Location: include/crypto/skcipher.h:548
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_crypt
```
```
In crypto/gcm.c (ffffffff81553c20)
Location: include/crypto/skcipher.h:548
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_copy_src_to_dst
  - crypto/gcm.c:gcm_dec_hash_continue
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (ffffffff81559009)
Location: include/crypto/skcipher.h:548
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
```
```
In block/blk-crypto-fallback.c (ffffffff815a5e28)
Location: include/crypto/skcipher.h:548
Inline: True
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
In fs/crypto/crypto.c (ffffffff813f7ecb)
Location: include/crypto/skcipher.h:548
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
```
```
In fs/crypto/fname.c (ffffffff813f8606)
Location: include/crypto/skcipher.h:548
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_decrypt
  - fs/crypto/fname.c:fscrypt_fname_encrypt
```
```
In fs/crypto/keysetup_v1.c (ffffffff813fc0e7)
Location: include/crypto/skcipher.h:548
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff814dc4a1)
Location: include/crypto/skcipher.h:548
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/keystore.c (ffffffff814df0d9)
Location: include/crypto/skcipher.h:548
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff81520ac1)
Location: include/crypto/skcipher.h:548
Inline: True
```
```
In crypto/seqiv.c (ffffffff815a9cb9)
Location: include/crypto/skcipher.h:548
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/cts.c (ffffffff815b399c)
Location: include/crypto/skcipher.h:548
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
In crypto/xts.c (ffffffff815b3e78)
Location: include/crypto/skcipher.h:548
Inline: True
Inline callers:
  - crypto/xts.c:xts_decrypt
  - crypto/xts.c:xts_encrypt
  - crypto/xts.c:xts_cts_final
```
```
In crypto/ctr.c (ffffffff815b4690)
Location: include/crypto/skcipher.h:548
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_crypt
```
```
In crypto/gcm.c (ffffffff815b4c50)
Location: include/crypto/skcipher.h:548
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_copy_src_to_dst
  - crypto/gcm.c:gcm_dec_hash_continue
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (ffffffff815ba2c9)
Location: include/crypto/skcipher.h:548
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
```
```
In block/blk-crypto-fallback.c (ffffffff8160e938)
Location: include/crypto/skcipher.h:548
Inline: True
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
In fs/crypto/crypto.c (ffffffff8146ac73)
Location: include/crypto/skcipher.h:552
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
```
```
In fs/crypto/fname.c (ffffffff8146b329)
Location: include/crypto/skcipher.h:552
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_decrypt
  - fs/crypto/fname.c:fscrypt_fname_encrypt
```
```
In fs/crypto/keysetup_v1.c (ffffffff8146f560)
Location: include/crypto/skcipher.h:552
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff8156a2a5)
Location: include/crypto/skcipher.h:552
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/keystore.c (ffffffff8156d13f)
Location: include/crypto/skcipher.h:552
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff815b4201)
Location: include/crypto/skcipher.h:552
Inline: True
```
```
In crypto/seqiv.c (ffffffff816511d6)
Location: include/crypto/skcipher.h:552
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/cts.c (ffffffff8165c71b)
Location: include/crypto/skcipher.h:552
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
In crypto/xts.c (ffffffff8165cc77)
Location: include/crypto/skcipher.h:552
Inline: True
Inline callers:
  - crypto/xts.c:xts_decrypt
  - crypto/xts.c:xts_encrypt
  - crypto/xts.c:xts_cts_final
```
```
In crypto/ctr.c (ffffffff8165d540)
Location: include/crypto/skcipher.h:552
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_crypt
```
```
In crypto/gcm.c (ffffffff8165dbf9)
Location: include/crypto/skcipher.h:552
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_copy_src_to_dst
  - crypto/gcm.c:gcm_dec_hash_continue
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (ffffffff8166335d)
Location: include/crypto/skcipher.h:552
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
```
```
In block/blk-crypto-fallback.c (ffffffff816c30b8)
Location: include/crypto/skcipher.h:552
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
In fs/crypto/crypto.c (ffffffff814fbd90)
Location: include/crypto/skcipher.h:552
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
```
```
In fs/crypto/fname.c (ffffffff814fc7a9)
Location: include/crypto/skcipher.h:552
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_decrypt
  - fs/crypto/fname.c:fscrypt_fname_encrypt
```
```
In fs/crypto/keysetup_v1.c (ffffffff81500ce0)
Location: include/crypto/skcipher.h:552
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff8160e035)
Location: include/crypto/skcipher.h:552
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/keystore.c (ffffffff816118c3)
Location: include/crypto/skcipher.h:552
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff8165efed)
Location: include/crypto/skcipher.h:552
Inline: True
```
```
In crypto/seqiv.c (ffffffff8170aa56)
Location: include/crypto/skcipher.h:552
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/cts.c (ffffffff8171613b)
Location: include/crypto/skcipher.h:552
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
In crypto/xts.c (ffffffff817166c7)
Location: include/crypto/skcipher.h:552
Inline: True
Inline callers:
  - crypto/xts.c:xts_decrypt
  - crypto/xts.c:xts_encrypt
  - crypto/xts.c:xts_cts_final
```
```
In crypto/ctr.c (ffffffff81717170)
Location: include/crypto/skcipher.h:552
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_crypt
```
```
In crypto/gcm.c (ffffffff817177a9)
Location: include/crypto/skcipher.h:552
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_copy_src_to_dst
  - crypto/gcm.c:gcm_dec_hash_continue
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (ffffffff8171d5ed)
Location: include/crypto/skcipher.h:552
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
```
```
In block/blk-crypto-fallback.c (ffffffff81784528)
Location: include/crypto/skcipher.h:552
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
In fs/crypto/crypto.c (ffffffff815330c0)
Location: include/crypto/skcipher.h:574
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
```
```
In fs/crypto/fname.c (ffffffff81533d19)
Location: include/crypto/skcipher.h:574
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_decrypt
  - fs/crypto/fname.c:fscrypt_fname_encrypt
```
```
In fs/crypto/keysetup_v1.c (ffffffff8153837a)
Location: include/crypto/skcipher.h:574
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff81645eac)
Location: include/crypto/skcipher.h:574
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/keystore.c (ffffffff81649804)
Location: include/crypto/skcipher.h:574
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff81697942)
Location: include/crypto/skcipher.h:574
Inline: True
```
```
In crypto/seqiv.c (ffffffff817442a6)
Location: include/crypto/skcipher.h:574
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/cts.c (ffffffff81751a3b)
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
In crypto/xts.c (ffffffff81751f97)
Location: include/crypto/skcipher.h:574
Inline: True
Inline callers:
  - crypto/xts.c:xts_decrypt
  - crypto/xts.c:xts_encrypt
  - crypto/xts.c:xts_cts_final
```
```
In crypto/ctr.c (ffffffff81752a80)
Location: include/crypto/skcipher.h:574
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_crypt
```
```
In crypto/gcm.c (ffffffff81753199)
Location: include/crypto/skcipher.h:574
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_copy_src_to_dst
  - crypto/gcm.c:gcm_dec_hash_continue
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (ffffffff81758ecd)
Location: include/crypto/skcipher.h:574
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
```
```
In block/blk-crypto-fallback.c (ffffffff817c485f)
Location: include/crypto/skcipher.h:574
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
In fs/crypto/crypto.c (ffffffff81567fbd)
Location: include/crypto/skcipher.h:919
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_crypt_data_unit
```
```
In fs/crypto/fname.c (ffffffff81568ca9)
Location: include/crypto/skcipher.h:919
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_decrypt
  - fs/crypto/fname.c:fscrypt_fname_encrypt
```
```
In fs/crypto/keysetup_v1.c (ffffffff8156d4ca)
Location: include/crypto/skcipher.h:919
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff8167f36c)
Location: include/crypto/skcipher.h:919
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/keystore.c (ffffffff81682cd4)
Location: include/crypto/skcipher.h:919
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff816d3fc2)
Location: include/crypto/skcipher.h:919
Inline: True
```
```
In crypto/seqiv.c (ffffffff81786866)
Location: include/crypto/skcipher.h:919
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/cts.c (ffffffff817938bb)
Location: include/crypto/skcipher.h:919
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
In crypto/xts.c (ffffffff81793e17)
Location: include/crypto/skcipher.h:919
Inline: True
Inline callers:
  - crypto/xts.c:xts_decrypt
  - crypto/xts.c:xts_encrypt
  - crypto/xts.c:xts_cts_final
```
```
In crypto/ctr.c (ffffffff817949f0)
Location: include/crypto/skcipher.h:919
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_crypt
```
```
In crypto/gcm.c (ffffffff81795069)
Location: include/crypto/skcipher.h:919
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_copy_src_to_dst
  - crypto/gcm.c:gcm_dec_hash_continue
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (ffffffff8179adcd)
Location: include/crypto/skcipher.h:919
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
```
```
In block/blk-crypto-fallback.c (ffffffff8180951f)
Location: include/crypto/skcipher.h:919
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
In fs/crypto/crypto.c (ffff80001040b054)
Location: include/crypto/skcipher.h:581
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
```
```
In fs/crypto/fname.c (ffff80001040bc4c)
Location: include/crypto/skcipher.h:581
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_encrypt
```
```
In fs/crypto/keysetup_v1.c (ffff80001040f664)
Location: include/crypto/skcipher.h:581
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffff8000104f6f08)
Location: include/crypto/skcipher.h:581
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/keystore.c (ffff8000104fa244)
Location: include/crypto/skcipher.h:581
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (ffff80001053cb74)
Location: include/crypto/skcipher.h:581
Inline: True
```
```
In crypto/seqiv.c (ffff8000105bfc18)
Location: include/crypto/skcipher.h:581
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/cts.c (ffff8000105c9e0c)
Location: include/crypto/skcipher.h:581
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
In crypto/xts.c (ffff8000105c9fd8)
Location: include/crypto/skcipher.h:581
Inline: True
Inline callers:
  - crypto/xts.c:init_crypt
  - crypto/xts.c:cts_final
```
```
In crypto/ctr.c (ffff8000105caca4)
Location: include/crypto/skcipher.h:581
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_crypt
```
```
In crypto/gcm.c (ffff8000105cb458)
Location: include/crypto/skcipher.h:581
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_copy_src_to_dst
  - crypto/gcm.c:gcm_dec_hash_continue
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (ffff8000105d1580)
Location: include/crypto/skcipher.h:581
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
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
In fs/crypto/crypto.c (c05d81f0)
Location: include/crypto/skcipher.h:581
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
```
```
In fs/crypto/fname.c (c05d8a10)
Location: include/crypto/skcipher.h:581
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_decrypt
  - fs/crypto/fname.c:fname_encrypt
```
```
In fs/crypto/keysetup_v1.c (c05dc334)
Location: include/crypto/skcipher.h:581
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
```
```
In fs/ecryptfs/crypto.c (c06b4bf0)
Location: include/crypto/skcipher.h:581
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_extent
```
```
In fs/ecryptfs/keystore.c (c06b7988)
Location: include/crypto/skcipher.h:581
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (c06f2de4)
Location: include/crypto/skcipher.h:581
Inline: True
```
```
In crypto/seqiv.c (c076d858)
Location: include/crypto/skcipher.h:581
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/cts.c (c0777940)
Location: include/crypto/skcipher.h:581
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
In crypto/xts.c (c0777aec)
Location: include/crypto/skcipher.h:581
Inline: True
Inline callers:
  - crypto/xts.c:init_crypt
  - crypto/xts.c:cts_final
```
```
In crypto/ctr.c (c0778878)
Location: include/crypto/skcipher.h:581
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_crypt
```
```
In crypto/gcm.c (c0778f58)
Location: include/crypto/skcipher.h:581
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_copy_src_to_dst
  - crypto/gcm.c:gcm_dec_hash_continue
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (c07804e8)
Location: include/crypto/skcipher.h:581
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
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
In fs/crypto/crypto.c (c000000000517b14)
Location: include/crypto/skcipher.h:581
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
```
```
In fs/crypto/fname.c (c000000000518984)
Location: include/crypto/skcipher.h:581
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_encrypt
```
```
In fs/crypto/keysetup_v1.c (c00000000051d0f4)
Location: include/crypto/skcipher.h:581
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (c00000000063820c)
Location: include/crypto/skcipher.h:581
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/keystore.c (c00000000063c8c0)
Location: include/crypto/skcipher.h:581
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (c00000000068c8ac)
Location: include/crypto/skcipher.h:581
Inline: True
```
```
In crypto/seqiv.c (c000000000747a6c)
Location: include/crypto/skcipher.h:581
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/cts.c (c00000000075470c)
Location: include/crypto/skcipher.h:581
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
Location: include/crypto/skcipher.h:581
Inline: True
Inline callers:
  - crypto/xts.c:init_crypt
  - crypto/xts.c:cts_final
```
```
In crypto/ctr.c (c000000000755ab0)
Location: include/crypto/skcipher.h:581
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_crypt
```
```
In crypto/gcm.c (c000000000756498)
Location: include/crypto/skcipher.h:581
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_copy_src_to_dst
  - crypto/gcm.c:gcm_dec_hash_continue
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (c00000000075fd20)
Location: include/crypto/skcipher.h:581
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
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
In fs/crypto/crypto.c (ffffffe0002b4d5c)
Location: include/crypto/skcipher.h:581
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
```
```
In fs/crypto/fname.c (ffffffe0002b56d0)
Location: include/crypto/skcipher.h:581
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_encrypt
```
```
In fs/crypto/keysetup_v1.c (ffffffe0002b8512)
Location: include/crypto/skcipher.h:581
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
```
```
In fs/ecryptfs/crypto.c (ffffffe000365ab6)
Location: include/crypto/skcipher.h:581
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/keystore.c (ffffffe0003689ea)
Location: include/crypto/skcipher.h:581
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffe00039a85e)
Location: include/crypto/skcipher.h:581
Inline: True
```
```
In crypto/seqiv.c (ffffffe000404c62)
Location: include/crypto/skcipher.h:581
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/cts.c (ffffffe00040df9a)
Location: include/crypto/skcipher.h:581
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
In crypto/xts.c (ffffffe00040e600)
Location: include/crypto/skcipher.h:581
Inline: True
Inline callers:
  - crypto/xts.c:init_crypt
  - crypto/xts.c:cts_final
```
```
In crypto/ctr.c (ffffffe00040f1a6)
Location: include/crypto/skcipher.h:581
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_crypt
```
```
In crypto/gcm.c (ffffffe00040f7bc)
Location: include/crypto/skcipher.h:581
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_copy_src_to_dst
  - crypto/gcm.c:gcm_dec_hash_continue
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (ffffffe0004162e6)
Location: include/crypto/skcipher.h:581
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
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
In fs/crypto/crypto.c (ffffffff81342e3d)
Location: include/crypto/skcipher.h:581
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
```
```
In fs/crypto/fname.c (ffffffff8134382b)
Location: include/crypto/skcipher.h:581
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_encrypt
```
```
In fs/crypto/keysetup_v1.c (ffffffff81346a18)
Location: include/crypto/skcipher.h:581
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff8140df14)
Location: include/crypto/skcipher.h:581
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/keystore.c (ffffffff8141101f)
Location: include/crypto/skcipher.h:581
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff8144a1b5)
Location: include/crypto/skcipher.h:581
Inline: True
```
```
In crypto/seqiv.c (ffffffff814bd639)
Location: include/crypto/skcipher.h:581
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/cts.c (ffffffff814c64d5)
Location: include/crypto/skcipher.h:581
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
In crypto/xts.c (ffffffff814c6688)
Location: include/crypto/skcipher.h:581
Inline: True
Inline callers:
  - crypto/xts.c:init_crypt
  - crypto/xts.c:cts_final
```
```
In crypto/ctr.c (ffffffff814c732d)
Location: include/crypto/skcipher.h:581
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_crypt
```
```
In crypto/gcm.c (ffffffff814c7a30)
Location: include/crypto/skcipher.h:581
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_copy_src_to_dst
  - crypto/gcm.c:gcm_dec_hash_continue
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (ffffffff814cf6ac)
Location: include/crypto/skcipher.h:581
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
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
In fs/crypto/crypto.c (ffffffff81333b1d)
Location: include/crypto/skcipher.h:581
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
```
```
In fs/crypto/fname.c (ffffffff8133450b)
Location: include/crypto/skcipher.h:581
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_encrypt
```
```
In fs/crypto/keysetup_v1.c (ffffffff813376f8)
Location: include/crypto/skcipher.h:581
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff813fe994)
Location: include/crypto/skcipher.h:581
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/keystore.c (ffffffff81401a9f)
Location: include/crypto/skcipher.h:581
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff8143ac05)
Location: include/crypto/skcipher.h:581
Inline: True
```
```
In crypto/seqiv.c (ffffffff814ae059)
Location: include/crypto/skcipher.h:581
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/cts.c (ffffffff814b6ef5)
Location: include/crypto/skcipher.h:581
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
In crypto/xts.c (ffffffff814b70a8)
Location: include/crypto/skcipher.h:581
Inline: True
Inline callers:
  - crypto/xts.c:init_crypt
  - crypto/xts.c:cts_final
```
```
In crypto/ctr.c (ffffffff814b7d4d)
Location: include/crypto/skcipher.h:581
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_crypt
```
```
In crypto/gcm.c (ffffffff814b8450)
Location: include/crypto/skcipher.h:581
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_copy_src_to_dst
  - crypto/gcm.c:gcm_dec_hash_continue
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (ffffffff814c00cc)
Location: include/crypto/skcipher.h:581
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
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
In fs/crypto/crypto.c (ffffffff8134090d)
Location: include/crypto/skcipher.h:581
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
```
```
In fs/crypto/fname.c (ffffffff813412fb)
Location: include/crypto/skcipher.h:581
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_encrypt
```
```
In fs/crypto/keysetup_v1.c (ffffffff813444e8)
Location: include/crypto/skcipher.h:581
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff8140b294)
Location: include/crypto/skcipher.h:581
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/keystore.c (ffffffff8140e39f)
Location: include/crypto/skcipher.h:581
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff81446255)
Location: include/crypto/skcipher.h:581
Inline: True
```
```
In crypto/seqiv.c (ffffffff814b96c9)
Location: include/crypto/skcipher.h:581
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/cts.c (ffffffff814c2565)
Location: include/crypto/skcipher.h:581
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
In crypto/xts.c (ffffffff814c2718)
Location: include/crypto/skcipher.h:581
Inline: True
Inline callers:
  - crypto/xts.c:init_crypt
  - crypto/xts.c:cts_final
```
```
In crypto/ctr.c (ffffffff814c33bd)
Location: include/crypto/skcipher.h:581
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_crypt
```
```
In crypto/gcm.c (ffffffff814c3ac0)
Location: include/crypto/skcipher.h:581
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_copy_src_to_dst
  - crypto/gcm.c:gcm_dec_hash_continue
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (ffffffff814cb73c)
Location: include/crypto/skcipher.h:581
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
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
In fs/crypto/crypto.c (ffffffff81353c0d)
Location: include/crypto/skcipher.h:581
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
```
```
In fs/crypto/fname.c (ffffffff813545fb)
Location: include/crypto/skcipher.h:581
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_encrypt
```
```
In fs/crypto/keysetup_v1.c (ffffffff813577c8)
Location: include/crypto/skcipher.h:581
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff81420f34)
Location: include/crypto/skcipher.h:581
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/keystore.c (ffffffff8142400f)
Location: include/crypto/skcipher.h:581
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff8145d585)
Location: include/crypto/skcipher.h:581
Inline: True
```
```
In crypto/seqiv.c (ffffffff814d2169)
Location: include/crypto/skcipher.h:581
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/cts.c (ffffffff814db035)
Location: include/crypto/skcipher.h:581
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
In crypto/xts.c (ffffffff814db1e8)
Location: include/crypto/skcipher.h:581
Inline: True
Inline callers:
  - crypto/xts.c:init_crypt
  - crypto/xts.c:cts_final
```
```
In crypto/ctr.c (ffffffff814dbe8d)
Location: include/crypto/skcipher.h:581
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_crypt
```
```
In crypto/gcm.c (ffffffff814dc590)
Location: include/crypto/skcipher.h:581
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_copy_src_to_dst
  - crypto/gcm.c:gcm_dec_hash_continue
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (ffffffff814e420c)
Location: include/crypto/skcipher.h:581
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
```
</details>
</li>
</ul>

## Differences
