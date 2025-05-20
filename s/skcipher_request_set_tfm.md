# Function: <code>skcipher_request_set_tfm</code>

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
In fs/crypto/crypto.c (ffffffff812889ae)
Location: include/crypto/skcipher.h:462
Inline: True
```
```
In fs/crypto/fname.c (ffffffff8128985f)
Location: include/crypto/skcipher.h:462
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_decrypt
  - fs/crypto/fname.c:fname_encrypt
```
```
In fs/crypto/keyinfo.c (ffffffff8128a195)
Location: include/crypto/skcipher.h:462
Inline: True
Inline callers:
  - fs/crypto/keyinfo.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff813395ca)
Location: include/crypto/skcipher.h:462
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/keystore.c (ffffffff8133c6f0)
Location: include/crypto/skcipher.h:462
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/big_key.c (ffffffff8136b7ff)
Location: include/crypto/skcipher.h:462
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_crypt
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff8136e43c)
Location: include/crypto/skcipher.h:462
Inline: True
```
```
In crypto/seqiv.c (ffffffff813de940)
Location: include/crypto/skcipher.h:462
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/cts.c (ffffffff813e7991)
Location: include/crypto/skcipher.h:462
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:crypto_cts_encrypt
```
```
In crypto/ctr.c (ffffffff813e88ba)
Location: include/crypto/skcipher.h:462
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_crypt
```
```
In crypto/drbg.c (ffffffff813eed70)
Location: include/crypto/skcipher.h:462
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
In fs/crypto/crypto.c (ffffffff8129d5e3)
Location: include/crypto/skcipher.h:462
Inline: True
```
```
In fs/crypto/fname.c (ffffffff8129e51f)
Location: include/crypto/skcipher.h:462
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_decrypt
  - fs/crypto/fname.c:fname_encrypt
```
```
In fs/crypto/keyinfo.c (ffffffff8129eed5)
Location: include/crypto/skcipher.h:462
Inline: True
Inline callers:
  - fs/crypto/keyinfo.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff8134f36a)
Location: include/crypto/skcipher.h:462
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/keystore.c (ffffffff81352480)
Location: include/crypto/skcipher.h:462
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/big_key.c (ffffffff8138201f)
Location: include/crypto/skcipher.h:462
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_crypt
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff81384c5c)
Location: include/crypto/skcipher.h:462
Inline: True
```
```
In crypto/seqiv.c (ffffffff813f6ee0)
Location: include/crypto/skcipher.h:462
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/cts.c (ffffffff814007c1)
Location: include/crypto/skcipher.h:462
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:crypto_cts_encrypt
```
```
In crypto/xts.c (ffffffff81401123)
Location: include/crypto/skcipher.h:462
Inline: True
Inline callers:
  - crypto/xts.c:init_crypt
```
```
In crypto/ctr.c (ffffffff81401eca)
Location: include/crypto/skcipher.h:462
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_crypt
```
```
In crypto/drbg.c (ffffffff814085b6)
Location: include/crypto/skcipher.h:462
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
In fs/crypto/crypto.c (ffffffff812ac367)
Location: include/crypto/skcipher.h:496
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_do_page_crypto
```
```
In fs/crypto/fname.c (ffffffff812acfe5)
Location: include/crypto/skcipher.h:496
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_decrypt
  - fs/crypto/fname.c:fname_encrypt
```
```
In fs/crypto/keyinfo.c (ffffffff812ad95a)
Location: include/crypto/skcipher.h:496
Inline: True
Inline callers:
  - fs/crypto/keyinfo.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff81363e0b)
Location: include/crypto/skcipher.h:496
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/keystore.c (ffffffff81367213)
Location: include/crypto/skcipher.h:496
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/big_key.c (ffffffff813966b8)
Location: include/crypto/skcipher.h:496
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_crypt
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff813992d3)
Location: include/crypto/skcipher.h:496
Inline: True
```
```
In crypto/seqiv.c (ffffffff814032d6)
Location: include/crypto/skcipher.h:496
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/cts.c (ffffffff8140e091)
Location: include/crypto/skcipher.h:496
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:crypto_cts_encrypt
```
```
In crypto/xts.c (ffffffff8140e4b5)
Location: include/crypto/skcipher.h:496
Inline: True
Inline callers:
  - crypto/xts.c:init_crypt
```
```
In crypto/ctr.c (ffffffff8140f31a)
Location: include/crypto/skcipher.h:496
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_crypt
```
```
In crypto/drbg.c (ffffffff81415ca6)
Location: include/crypto/skcipher.h:496
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
In fs/crypto/crypto.c (ffffffff812cfb7a)
Location: include/crypto/skcipher.h:496
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_do_page_crypto
```
```
In fs/crypto/fname.c (ffffffff812d078f)
Location: include/crypto/skcipher.h:496
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_decrypt
  - fs/crypto/fname.c:fname_encrypt
```
```
In fs/crypto/keyinfo.c (ffffffff812d0e1b)
Location: include/crypto/skcipher.h:496
Inline: True
Inline callers:
  - fs/crypto/keyinfo.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff81388b7b)
Location: include/crypto/skcipher.h:496
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/keystore.c (ffffffff8138be96)
Location: include/crypto/skcipher.h:496
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff813beae9)
Location: include/crypto/skcipher.h:496
Inline: True
```
```
In crypto/seqiv.c (ffffffff8142b9c6)
Location: include/crypto/skcipher.h:496
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/cts.c (ffffffff81436b41)
Location: include/crypto/skcipher.h:496
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:crypto_cts_encrypt
```
```
In crypto/xts.c (ffffffff81436f75)
Location: include/crypto/skcipher.h:496
Inline: True
Inline callers:
  - crypto/xts.c:init_crypt
```
```
In crypto/ctr.c (ffffffff81437eea)
Location: include/crypto/skcipher.h:496
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_crypt
```
```
In crypto/gcm.c (ffffffff81438fbc)
Location: include/crypto/skcipher.h:496
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:gcm_dec_hash_continue
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (ffffffff8144047e)
Location: include/crypto/skcipher.h:496
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
In fs/crypto/crypto.c (ffffffff812fa45c)
Location: include/crypto/skcipher.h:497
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_do_page_crypto
```
```
In fs/crypto/fname.c (ffffffff812fae52)
Location: include/crypto/skcipher.h:497
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_encrypt
```
```
In fs/crypto/keyinfo.c (ffffffff812fb9a2)
Location: include/crypto/skcipher.h:497
Inline: True
Inline callers:
  - fs/crypto/keyinfo.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff813b79cb)
Location: include/crypto/skcipher.h:497
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/keystore.c (ffffffff813baaf1)
Location: include/crypto/skcipher.h:497
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff813ef92d)
Location: include/crypto/skcipher.h:497
Inline: True
```
```
In crypto/seqiv.c (ffffffff8145e6f6)
Location: include/crypto/skcipher.h:497
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/cts.c (ffffffff814696f3)
Location: include/crypto/skcipher.h:497
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:crypto_cts_encrypt
```
```
In crypto/xts.c (ffffffff814698a2)
Location: include/crypto/skcipher.h:497
Inline: True
Inline callers:
  - crypto/xts.c:init_crypt
```
```
In crypto/ctr.c (ffffffff8146a846)
Location: include/crypto/skcipher.h:497
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_crypt
```
```
In crypto/gcm.c (ffffffff8146b306)
Location: include/crypto/skcipher.h:497
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:gcm_dec_hash_continue
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (ffffffff8147335e)
Location: include/crypto/skcipher.h:497
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
In fs/crypto/crypto.c (ffffffff8130f790)
Location: include/crypto/skcipher.h:560
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_do_page_crypto
```
```
In fs/crypto/fname.c (ffffffff81310209)
Location: include/crypto/skcipher.h:560
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_encrypt
```
```
In fs/crypto/keyinfo.c (ffffffff81310ef6)
Location: include/crypto/skcipher.h:560
Inline: True
Inline callers:
  - fs/crypto/keyinfo.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff813d0edf)
Location: include/crypto/skcipher.h:560
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/keystore.c (ffffffff813d40b1)
Location: include/crypto/skcipher.h:560
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff8140ab7d)
Location: include/crypto/skcipher.h:560
Inline: True
```
```
In crypto/seqiv.c (ffffffff8147bfd0)
Location: include/crypto/skcipher.h:560
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/cts.c (ffffffff81487428)
Location: include/crypto/skcipher.h:560
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:crypto_cts_encrypt
```
```
In crypto/xts.c (ffffffff81487627)
Location: include/crypto/skcipher.h:560
Inline: True
Inline callers:
  - crypto/xts.c:xor_tweak
```
```
In crypto/ctr.c (ffffffff814880b5)
Location: include/crypto/skcipher.h:560
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_crypt
```
```
In crypto/gcm.c (ffffffff81489583)
Location: include/crypto/skcipher.h:560
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_copy_src_to_dst
  - crypto/gcm.c:gcm_dec_hash_continue
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (ffffffff8148f8d5)
Location: include/crypto/skcipher.h:560
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
In fs/crypto/crypto.c (ffffffff81336c71)
Location: include/crypto/skcipher.h:467
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
```
```
In fs/crypto/fname.c (ffffffff81337676)
Location: include/crypto/skcipher.h:467
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_encrypt
```
```
In fs/crypto/keyinfo.c (ffffffff81338625)
Location: include/crypto/skcipher.h:467
Inline: True
Inline callers:
  - fs/crypto/keyinfo.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff813fbac6)
Location: include/crypto/skcipher.h:467
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/keystore.c (ffffffff813feb1b)
Location: include/crypto/skcipher.h:467
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff81437e11)
Location: include/crypto/skcipher.h:467
Inline: True
```
```
In crypto/seqiv.c (ffffffff814aa371)
Location: include/crypto/skcipher.h:467
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/cts.c (ffffffff814b513f)
Location: include/crypto/skcipher.h:467
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:crypto_cts_encrypt
```
```
In crypto/xts.c (ffffffff814b531a)
Location: include/crypto/skcipher.h:467
Inline: True
Inline callers:
  - crypto/xts.c:xor_tweak
```
```
In crypto/ctr.c (ffffffff814b5b3a)
Location: include/crypto/skcipher.h:467
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_crypt
```
```
In crypto/gcm.c (ffffffff814b6233)
Location: include/crypto/skcipher.h:467
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_copy_src_to_dst
  - crypto/gcm.c:gcm_dec_hash_continue
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (ffffffff814be26a)
Location: include/crypto/skcipher.h:467
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
In fs/crypto/crypto.c (ffffffff8134a841)
Location: include/crypto/skcipher.h:497
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
```
```
In fs/crypto/fname.c (ffffffff8134b236)
Location: include/crypto/skcipher.h:497
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_encrypt
```
```
In fs/crypto/keysetup_v1.c (ffffffff8134e434)
Location: include/crypto/skcipher.h:497
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff81415924)
Location: include/crypto/skcipher.h:497
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/keystore.c (ffffffff81418a0b)
Location: include/crypto/skcipher.h:497
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff81451bd1)
Location: include/crypto/skcipher.h:497
Inline: True
```
```
In crypto/seqiv.c (ffffffff814c5031)
Location: include/crypto/skcipher.h:497
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/cts.c (ffffffff814cdecf)
Location: include/crypto/skcipher.h:497
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:crypto_cts_encrypt
```
```
In crypto/xts.c (ffffffff814ce080)
Location: include/crypto/skcipher.h:497
Inline: True
Inline callers:
  - crypto/xts.c:init_crypt
  - crypto/xts.c:cts_final
  - crypto/xts.c:xor_tweak
```
```
In crypto/ctr.c (ffffffff814ced3a)
Location: include/crypto/skcipher.h:497
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_crypt
```
```
In crypto/gcm.c (ffffffff814cf433)
Location: include/crypto/skcipher.h:497
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_copy_src_to_dst
  - crypto/gcm.c:gcm_dec_hash_continue
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (ffffffff814d70ba)
Location: include/crypto/skcipher.h:497
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
In fs/crypto/crypto.c (ffffffff8138ffa1)
Location: include/crypto/skcipher.h:462
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
```
```
In fs/crypto/fname.c (ffffffff81390849)
Location: include/crypto/skcipher.h:462
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_decrypt
  - fs/crypto/fname.c:fscrypt_fname_encrypt
```
```
In fs/crypto/keysetup_v1.c (ffffffff813941d3)
Location: include/crypto/skcipher.h:462
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff81463cb2)
Location: include/crypto/skcipher.h:462
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/keystore.c (ffffffff81466c6e)
Location: include/crypto/skcipher.h:462
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff814a434d)
Location: include/crypto/skcipher.h:462
Inline: True
```
```
In crypto/seqiv.c (ffffffff81523f41)
Location: include/crypto/skcipher.h:462
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/cts.c (ffffffff8152d27f)
Location: include/crypto/skcipher.h:462
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:crypto_cts_encrypt
```
```
In crypto/xts.c (ffffffff8152d8d4)
Location: include/crypto/skcipher.h:462
Inline: True
Inline callers:
  - crypto/xts.c:decrypt
  - crypto/xts.c:encrypt
  - crypto/xts.c:cts_final
  - crypto/xts.c:xor_tweak
```
```
In crypto/ctr.c (ffffffff8152e00d)
Location: include/crypto/skcipher.h:462
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_crypt
```
```
In crypto/gcm.c (ffffffff8152e653)
Location: include/crypto/skcipher.h:462
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_copy_src_to_dst
  - crypto/gcm.c:gcm_dec_hash_continue
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (ffffffff815338c7)
Location: include/crypto/skcipher.h:462
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
```
```
In block/blk-crypto-fallback.c (ffffffff81582038)
Location: include/crypto/skcipher.h:462
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
In fs/crypto/crypto.c (ffffffff813a15e1)
Location: include/crypto/skcipher.h:462
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
```
```
In fs/crypto/fname.c (ffffffff813a1cc9)
Location: include/crypto/skcipher.h:462
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_decrypt
  - fs/crypto/fname.c:fscrypt_fname_encrypt
```
```
In fs/crypto/keysetup_v1.c (ffffffff813a5693)
Location: include/crypto/skcipher.h:462
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff8147f472)
Location: include/crypto/skcipher.h:462
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/keystore.c (ffffffff81481e6e)
Location: include/crypto/skcipher.h:462
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff814c1b4d)
Location: include/crypto/skcipher.h:462
Inline: True
```
```
In crypto/seqiv.c (ffffffff81540e48)
Location: include/crypto/skcipher.h:462
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/cts.c (ffffffff8154a2ef)
Location: include/crypto/skcipher.h:462
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:crypto_cts_encrypt
```
```
In crypto/xts.c (ffffffff8154a804)
Location: include/crypto/skcipher.h:462
Inline: True
Inline callers:
  - crypto/xts.c:xts_decrypt
  - crypto/xts.c:xts_encrypt
  - crypto/xts.c:xts_cts_final
  - crypto/xts.c:xts_xor_tweak
```
```
In crypto/ctr.c (ffffffff8154b02d)
Location: include/crypto/skcipher.h:462
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_crypt
```
```
In crypto/gcm.c (ffffffff8154b5f3)
Location: include/crypto/skcipher.h:462
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_copy_src_to_dst
  - crypto/gcm.c:gcm_dec_hash_continue
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (ffffffff81550817)
Location: include/crypto/skcipher.h:462
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
```
```
In block/blk-crypto-fallback.c (ffffffff8159f008)
Location: include/crypto/skcipher.h:462
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
In fs/crypto/crypto.c (ffffffff813a876f)
Location: include/crypto/skcipher.h:464
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
```
```
In fs/crypto/fname.c (ffffffff813a8e69)
Location: include/crypto/skcipher.h:464
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_decrypt
  - fs/crypto/fname.c:fscrypt_fname_encrypt
```
```
In fs/crypto/keysetup_v1.c (ffffffff813ac773)
Location: include/crypto/skcipher.h:464
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff81484e0d)
Location: include/crypto/skcipher.h:464
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/keystore.c (ffffffff814878d4)
Location: include/crypto/skcipher.h:464
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff814c7fcd)
Location: include/crypto/skcipher.h:464
Inline: True
```
```
In crypto/seqiv.c (ffffffff815494b1)
Location: include/crypto/skcipher.h:464
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/cts.c (ffffffff8155291f)
Location: include/crypto/skcipher.h:464
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:crypto_cts_encrypt
```
```
In crypto/xts.c (ffffffff81552e24)
Location: include/crypto/skcipher.h:464
Inline: True
Inline callers:
  - crypto/xts.c:xts_decrypt
  - crypto/xts.c:xts_encrypt
  - crypto/xts.c:xts_cts_final
  - crypto/xts.c:xts_xor_tweak
```
```
In crypto/ctr.c (ffffffff8155364d)
Location: include/crypto/skcipher.h:464
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_crypt
```
```
In crypto/gcm.c (ffffffff81553c03)
Location: include/crypto/skcipher.h:464
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_copy_src_to_dst
  - crypto/gcm.c:gcm_dec_hash_continue
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (ffffffff81558ff7)
Location: include/crypto/skcipher.h:464
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
```
```
In block/blk-crypto-fallback.c (ffffffff815a5e18)
Location: include/crypto/skcipher.h:464
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
In fs/crypto/crypto.c (ffffffff813f7eaf)
Location: include/crypto/skcipher.h:464
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
```
```
In fs/crypto/fname.c (ffffffff813f85f9)
Location: include/crypto/skcipher.h:464
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_decrypt
  - fs/crypto/fname.c:fscrypt_fname_encrypt
```
```
In fs/crypto/keysetup_v1.c (ffffffff813fc0e3)
Location: include/crypto/skcipher.h:464
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff814dc48d)
Location: include/crypto/skcipher.h:464
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/keystore.c (ffffffff814df0a5)
Location: include/crypto/skcipher.h:464
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff81520abd)
Location: include/crypto/skcipher.h:464
Inline: True
```
```
In crypto/seqiv.c (ffffffff815a9c91)
Location: include/crypto/skcipher.h:464
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/cts.c (ffffffff815b397d)
Location: include/crypto/skcipher.h:464
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:crypto_cts_encrypt
```
```
In crypto/xts.c (ffffffff815b3e54)
Location: include/crypto/skcipher.h:464
Inline: True
Inline callers:
  - crypto/xts.c:xts_decrypt
  - crypto/xts.c:xts_encrypt
  - crypto/xts.c:xts_cts_final
  - crypto/xts.c:xts_xor_tweak
```
```
In crypto/ctr.c (ffffffff815b467d)
Location: include/crypto/skcipher.h:464
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_crypt
```
```
In crypto/gcm.c (ffffffff815b4c33)
Location: include/crypto/skcipher.h:464
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_copy_src_to_dst
  - crypto/gcm.c:gcm_dec_hash_continue
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (ffffffff815ba2b7)
Location: include/crypto/skcipher.h:464
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
```
```
In block/blk-crypto-fallback.c (ffffffff8160e928)
Location: include/crypto/skcipher.h:464
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
In fs/crypto/crypto.c (ffffffff8146ac57)
Location: include/crypto/skcipher.h:468
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
```
```
In fs/crypto/fname.c (ffffffff8146b31c)
Location: include/crypto/skcipher.h:468
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_decrypt
  - fs/crypto/fname.c:fscrypt_fname_encrypt
```
```
In fs/crypto/keysetup_v1.c (ffffffff8146f55c)
Location: include/crypto/skcipher.h:468
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff8156a295)
Location: include/crypto/skcipher.h:468
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/keystore.c (ffffffff8156d10b)
Location: include/crypto/skcipher.h:468
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff815b41fd)
Location: include/crypto/skcipher.h:468
Inline: True
```
```
In crypto/seqiv.c (ffffffff8165119a)
Location: include/crypto/skcipher.h:468
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/cts.c (ffffffff8165c6fe)
Location: include/crypto/skcipher.h:468
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:crypto_cts_encrypt
```
```
In crypto/xts.c (ffffffff8165cc53)
Location: include/crypto/skcipher.h:468
Inline: True
Inline callers:
  - crypto/xts.c:xts_decrypt
  - crypto/xts.c:xts_encrypt
  - crypto/xts.c:xts_cts_final
  - crypto/xts.c:xts_xor_tweak
```
```
In crypto/ctr.c (ffffffff8165d52d)
Location: include/crypto/skcipher.h:468
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_crypt
```
```
In crypto/gcm.c (ffffffff8165dbbd)
Location: include/crypto/skcipher.h:468
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_copy_src_to_dst
  - crypto/gcm.c:gcm_dec_hash_continue
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (ffffffff8166334c)
Location: include/crypto/skcipher.h:468
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
```
```
In block/blk-crypto-fallback.c (ffffffff816c30a8)
Location: include/crypto/skcipher.h:468
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
In fs/crypto/crypto.c (ffffffff814fbd74)
Location: include/crypto/skcipher.h:468
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
```
```
In fs/crypto/fname.c (ffffffff814fc79c)
Location: include/crypto/skcipher.h:468
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_decrypt
  - fs/crypto/fname.c:fscrypt_fname_encrypt
```
```
In fs/crypto/keysetup_v1.c (ffffffff81500cdc)
Location: include/crypto/skcipher.h:468
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff8160e025)
Location: include/crypto/skcipher.h:468
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/keystore.c (ffffffff8161188f)
Location: include/crypto/skcipher.h:468
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff8165efe9)
Location: include/crypto/skcipher.h:468
Inline: True
```
```
In crypto/seqiv.c (ffffffff8170aa1a)
Location: include/crypto/skcipher.h:468
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/cts.c (ffffffff8171611e)
Location: include/crypto/skcipher.h:468
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:crypto_cts_encrypt
```
```
In crypto/xts.c (ffffffff817166a3)
Location: include/crypto/skcipher.h:468
Inline: True
Inline callers:
  - crypto/xts.c:xts_decrypt
  - crypto/xts.c:xts_encrypt
  - crypto/xts.c:xts_cts_final
  - crypto/xts.c:xts_xor_tweak
```
```
In crypto/ctr.c (ffffffff8171715d)
Location: include/crypto/skcipher.h:468
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_crypt
```
```
In crypto/gcm.c (ffffffff8171776d)
Location: include/crypto/skcipher.h:468
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_copy_src_to_dst
  - crypto/gcm.c:gcm_dec_hash_continue
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (ffffffff8171d5dc)
Location: include/crypto/skcipher.h:468
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
```
```
In block/blk-crypto-fallback.c (ffffffff81784518)
Location: include/crypto/skcipher.h:468
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
In fs/crypto/crypto.c (ffffffff815330a4)
Location: include/crypto/skcipher.h:490
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
```
```
In fs/crypto/fname.c (ffffffff81533d0c)
Location: include/crypto/skcipher.h:490
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_decrypt
  - fs/crypto/fname.c:fscrypt_fname_encrypt
```
```
In fs/crypto/keysetup_v1.c (ffffffff81538367)
Location: include/crypto/skcipher.h:490
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff81645e9c)
Location: include/crypto/skcipher.h:490
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/keystore.c (ffffffff816497e6)
Location: include/crypto/skcipher.h:490
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff81697932)
Location: include/crypto/skcipher.h:490
Inline: True
```
```
In crypto/seqiv.c (ffffffff8174426a)
Location: include/crypto/skcipher.h:490
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/cts.c (ffffffff81751a1e)
Location: include/crypto/skcipher.h:490
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:crypto_cts_encrypt
```
```
In crypto/xts.c (ffffffff81751f73)
Location: include/crypto/skcipher.h:490
Inline: True
Inline callers:
  - crypto/xts.c:xts_decrypt
  - crypto/xts.c:xts_encrypt
  - crypto/xts.c:xts_cts_final
  - crypto/xts.c:xts_xor_tweak
```
```
In crypto/ctr.c (ffffffff81752a6d)
Location: include/crypto/skcipher.h:490
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_crypt
```
```
In crypto/gcm.c (ffffffff8175315d)
Location: include/crypto/skcipher.h:490
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_copy_src_to_dst
  - crypto/gcm.c:gcm_dec_hash_continue
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (ffffffff81758ebc)
Location: include/crypto/skcipher.h:490
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
```
```
In block/blk-crypto-fallback.c (ffffffff817c484f)
Location: include/crypto/skcipher.h:490
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
In fs/crypto/crypto.c (ffffffff81567fa1)
Location: include/crypto/skcipher.h:835
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_crypt_data_unit
```
```
In fs/crypto/fname.c (ffffffff81568c9c)
Location: include/crypto/skcipher.h:835
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_decrypt
  - fs/crypto/fname.c:fscrypt_fname_encrypt
```
```
In fs/crypto/keysetup_v1.c (ffffffff8156d4b7)
Location: include/crypto/skcipher.h:835
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff8167f35c)
Location: include/crypto/skcipher.h:835
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/keystore.c (ffffffff81682cb6)
Location: include/crypto/skcipher.h:835
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff816d3fb2)
Location: include/crypto/skcipher.h:835
Inline: True
```
```
In crypto/seqiv.c (ffffffff8178682a)
Location: include/crypto/skcipher.h:835
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/cts.c (ffffffff8179389e)
Location: include/crypto/skcipher.h:835
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:crypto_cts_encrypt
```
```
In crypto/xts.c (ffffffff81793df3)
Location: include/crypto/skcipher.h:835
Inline: True
Inline callers:
  - crypto/xts.c:xts_decrypt
  - crypto/xts.c:xts_encrypt
  - crypto/xts.c:xts_cts_final
  - crypto/xts.c:xts_xor_tweak
```
```
In crypto/ctr.c (ffffffff817949dd)
Location: include/crypto/skcipher.h:835
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_crypt
```
```
In crypto/gcm.c (ffffffff8179502d)
Location: include/crypto/skcipher.h:835
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_copy_src_to_dst
  - crypto/gcm.c:gcm_dec_hash_continue
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (ffffffff8179adbc)
Location: include/crypto/skcipher.h:835
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
```
```
In block/blk-crypto-fallback.c (ffffffff8180950f)
Location: include/crypto/skcipher.h:835
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
In fs/crypto/crypto.c (ffff80001040b030)
Location: include/crypto/skcipher.h:497
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
```
```
In fs/crypto/fname.c (ffff80001040bc28)
Location: include/crypto/skcipher.h:497
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_encrypt
```
```
In fs/crypto/keysetup_v1.c (ffff80001040f648)
Location: include/crypto/skcipher.h:497
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffff8000104f6ee4)
Location: include/crypto/skcipher.h:497
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/keystore.c (ffff8000104fa22c)
Location: include/crypto/skcipher.h:497
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (ffff80001053cb6c)
Location: include/crypto/skcipher.h:497
Inline: True
```
```
In crypto/seqiv.c (ffff8000105bfbf0)
Location: include/crypto/skcipher.h:497
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/cts.c (ffff8000105c9df4)
Location: include/crypto/skcipher.h:497
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:crypto_cts_encrypt
```
```
In crypto/xts.c (ffff8000105c9fbc)
Location: include/crypto/skcipher.h:497
Inline: True
Inline callers:
  - crypto/xts.c:init_crypt
  - crypto/xts.c:cts_final
  - crypto/xts.c:xor_tweak
```
```
In crypto/ctr.c (ffff8000105cac98)
Location: include/crypto/skcipher.h:497
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_crypt
```
```
In crypto/gcm.c (ffff8000105cb43c)
Location: include/crypto/skcipher.h:497
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_copy_src_to_dst
  - crypto/gcm.c:gcm_dec_hash_continue
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (ffff8000105d155c)
Location: include/crypto/skcipher.h:497
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
In fs/crypto/crypto.c (c05d81c8)
Location: include/crypto/skcipher.h:497
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
```
```
In fs/crypto/fname.c (c05d89f4)
Location: include/crypto/skcipher.h:497
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_decrypt
  - fs/crypto/fname.c:fname_encrypt
```
```
In fs/crypto/keysetup_v1.c (c05dc328)
Location: include/crypto/skcipher.h:497
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
```
```
In fs/ecryptfs/crypto.c (c06b4bd0)
Location: include/crypto/skcipher.h:497
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_extent
```
```
In fs/ecryptfs/keystore.c (c06b7978)
Location: include/crypto/skcipher.h:497
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (c06f2ddc)
Location: include/crypto/skcipher.h:497
Inline: True
```
```
In crypto/seqiv.c (c076d834)
Location: include/crypto/skcipher.h:497
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/cts.c (c0777928)
Location: include/crypto/skcipher.h:497
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:crypto_cts_encrypt
```
```
In crypto/xts.c (c0777ac0)
Location: include/crypto/skcipher.h:497
Inline: True
Inline callers:
  - crypto/xts.c:init_crypt
  - crypto/xts.c:cts_final
  - crypto/xts.c:xor_tweak
```
```
In crypto/ctr.c (c077886c)
Location: include/crypto/skcipher.h:497
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_crypt
```
```
In crypto/gcm.c (c0778f38)
Location: include/crypto/skcipher.h:497
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_copy_src_to_dst
  - crypto/gcm.c:gcm_dec_hash_continue
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (c07804d4)
Location: include/crypto/skcipher.h:497
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
In fs/crypto/crypto.c (c000000000517aec)
Location: include/crypto/skcipher.h:497
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
```
```
In fs/crypto/fname.c (c000000000518954)
Location: include/crypto/skcipher.h:497
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_encrypt
```
```
In fs/crypto/keysetup_v1.c (c00000000051d0e4)
Location: include/crypto/skcipher.h:497
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (c0000000006381ec)
Location: include/crypto/skcipher.h:497
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/keystore.c (c00000000063c894)
Location: include/crypto/skcipher.h:497
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (c00000000068c8a4)
Location: include/crypto/skcipher.h:497
Inline: True
```
```
In crypto/seqiv.c (c000000000747a38)
Location: include/crypto/skcipher.h:497
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/cts.c (c0000000007546e8)
Location: include/crypto/skcipher.h:497
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:crypto_cts_encrypt
```
```
In crypto/xts.c (c00000000075495c)
Location: include/crypto/skcipher.h:497
Inline: True
Inline callers:
  - crypto/xts.c:init_crypt
  - crypto/xts.c:cts_final
  - crypto/xts.c:xor_tweak
```
```
In crypto/ctr.c (c000000000755aa4)
Location: include/crypto/skcipher.h:497
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_crypt
```
```
In crypto/gcm.c (c00000000075645c)
Location: include/crypto/skcipher.h:497
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_copy_src_to_dst
  - crypto/gcm.c:gcm_dec_hash_continue
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (c00000000075fcfc)
Location: include/crypto/skcipher.h:497
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
In fs/crypto/crypto.c (ffffffe0002b4d56)
Location: include/crypto/skcipher.h:497
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
```
```
In fs/crypto/fname.c (ffffffe0002b56d0)
Location: include/crypto/skcipher.h:497
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_encrypt
```
```
In fs/crypto/keysetup_v1.c (ffffffe0002b8512)
Location: include/crypto/skcipher.h:497
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
```
```
In fs/ecryptfs/crypto.c (ffffffe000365ab6)
Location: include/crypto/skcipher.h:497
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/keystore.c (ffffffe0003689de)
Location: include/crypto/skcipher.h:497
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffe00039a85a)
Location: include/crypto/skcipher.h:497
Inline: True
```
```
In crypto/seqiv.c (ffffffe000404c4e)
Location: include/crypto/skcipher.h:497
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/cts.c (ffffffe00040df82)
Location: include/crypto/skcipher.h:497
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:crypto_cts_encrypt
```
```
In crypto/xts.c (ffffffe00040e5f4)
Location: include/crypto/skcipher.h:497
Inline: True
Inline callers:
  - crypto/xts.c:init_crypt
  - crypto/xts.c:cts_final
  - crypto/xts.c:xor_tweak
```
```
In crypto/ctr.c (ffffffe00040f154)
Location: include/crypto/skcipher.h:497
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_crypt
```
```
In crypto/gcm.c (ffffffe00040f7a8)
Location: include/crypto/skcipher.h:497
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_copy_src_to_dst
  - crypto/gcm.c:gcm_dec_hash_continue
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (ffffffe0004162e0)
Location: include/crypto/skcipher.h:497
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
In fs/crypto/crypto.c (ffffffff81342e21)
Location: include/crypto/skcipher.h:497
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
```
```
In fs/crypto/fname.c (ffffffff81343816)
Location: include/crypto/skcipher.h:497
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_encrypt
```
```
In fs/crypto/keysetup_v1.c (ffffffff81346a14)
Location: include/crypto/skcipher.h:497
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff8140df04)
Location: include/crypto/skcipher.h:497
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/keystore.c (ffffffff81410feb)
Location: include/crypto/skcipher.h:497
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff8144a1b1)
Location: include/crypto/skcipher.h:497
Inline: True
```
```
In crypto/seqiv.c (ffffffff814bd611)
Location: include/crypto/skcipher.h:497
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/cts.c (ffffffff814c64af)
Location: include/crypto/skcipher.h:497
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:crypto_cts_encrypt
```
```
In crypto/xts.c (ffffffff814c6660)
Location: include/crypto/skcipher.h:497
Inline: True
Inline callers:
  - crypto/xts.c:init_crypt
  - crypto/xts.c:cts_final
  - crypto/xts.c:xor_tweak
```
```
In crypto/ctr.c (ffffffff814c731a)
Location: include/crypto/skcipher.h:497
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_crypt
```
```
In crypto/gcm.c (ffffffff814c7a13)
Location: include/crypto/skcipher.h:497
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_copy_src_to_dst
  - crypto/gcm.c:gcm_dec_hash_continue
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (ffffffff814cf69a)
Location: include/crypto/skcipher.h:497
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
In fs/crypto/crypto.c (ffffffff81333b01)
Location: include/crypto/skcipher.h:497
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
```
```
In fs/crypto/fname.c (ffffffff813344f6)
Location: include/crypto/skcipher.h:497
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_encrypt
```
```
In fs/crypto/keysetup_v1.c (ffffffff813376f4)
Location: include/crypto/skcipher.h:497
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff813fe984)
Location: include/crypto/skcipher.h:497
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/keystore.c (ffffffff81401a6b)
Location: include/crypto/skcipher.h:497
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff8143ac01)
Location: include/crypto/skcipher.h:497
Inline: True
```
```
In crypto/seqiv.c (ffffffff814ae031)
Location: include/crypto/skcipher.h:497
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/cts.c (ffffffff814b6ecf)
Location: include/crypto/skcipher.h:497
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:crypto_cts_encrypt
```
```
In crypto/xts.c (ffffffff814b7080)
Location: include/crypto/skcipher.h:497
Inline: True
Inline callers:
  - crypto/xts.c:init_crypt
  - crypto/xts.c:cts_final
  - crypto/xts.c:xor_tweak
```
```
In crypto/ctr.c (ffffffff814b7d3a)
Location: include/crypto/skcipher.h:497
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_crypt
```
```
In crypto/gcm.c (ffffffff814b8433)
Location: include/crypto/skcipher.h:497
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_copy_src_to_dst
  - crypto/gcm.c:gcm_dec_hash_continue
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (ffffffff814c00ba)
Location: include/crypto/skcipher.h:497
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
In fs/crypto/crypto.c (ffffffff813408f1)
Location: include/crypto/skcipher.h:497
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
```
```
In fs/crypto/fname.c (ffffffff813412e6)
Location: include/crypto/skcipher.h:497
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_encrypt
```
```
In fs/crypto/keysetup_v1.c (ffffffff813444e4)
Location: include/crypto/skcipher.h:497
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff8140b284)
Location: include/crypto/skcipher.h:497
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/keystore.c (ffffffff8140e36b)
Location: include/crypto/skcipher.h:497
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff81446251)
Location: include/crypto/skcipher.h:497
Inline: True
```
```
In crypto/seqiv.c (ffffffff814b96a1)
Location: include/crypto/skcipher.h:497
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/cts.c (ffffffff814c253f)
Location: include/crypto/skcipher.h:497
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:crypto_cts_encrypt
```
```
In crypto/xts.c (ffffffff814c26f0)
Location: include/crypto/skcipher.h:497
Inline: True
Inline callers:
  - crypto/xts.c:init_crypt
  - crypto/xts.c:cts_final
  - crypto/xts.c:xor_tweak
```
```
In crypto/ctr.c (ffffffff814c33aa)
Location: include/crypto/skcipher.h:497
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_crypt
```
```
In crypto/gcm.c (ffffffff814c3aa3)
Location: include/crypto/skcipher.h:497
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_copy_src_to_dst
  - crypto/gcm.c:gcm_dec_hash_continue
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (ffffffff814cb72a)
Location: include/crypto/skcipher.h:497
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
In fs/crypto/crypto.c (ffffffff81353bf1)
Location: include/crypto/skcipher.h:497
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
```
```
In fs/crypto/fname.c (ffffffff813545e6)
Location: include/crypto/skcipher.h:497
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_encrypt
```
```
In fs/crypto/keysetup_v1.c (ffffffff813577c4)
Location: include/crypto/skcipher.h:497
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff81420f24)
Location: include/crypto/skcipher.h:497
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/keystore.c (ffffffff81423fdb)
Location: include/crypto/skcipher.h:497
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff8145d581)
Location: include/crypto/skcipher.h:497
Inline: True
```
```
In crypto/seqiv.c (ffffffff814d2141)
Location: include/crypto/skcipher.h:497
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/cts.c (ffffffff814db00f)
Location: include/crypto/skcipher.h:497
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:crypto_cts_encrypt
```
```
In crypto/xts.c (ffffffff814db1c0)
Location: include/crypto/skcipher.h:497
Inline: True
Inline callers:
  - crypto/xts.c:init_crypt
  - crypto/xts.c:cts_final
  - crypto/xts.c:xor_tweak
```
```
In crypto/ctr.c (ffffffff814dbe7a)
Location: include/crypto/skcipher.h:497
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_crypt
```
```
In crypto/gcm.c (ffffffff814dc573)
Location: include/crypto/skcipher.h:497
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_copy_src_to_dst
  - crypto/gcm.c:gcm_dec_hash_continue
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (ffffffff814e41fa)
Location: include/crypto/skcipher.h:497
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
```
</details>
</li>
</ul>

## Differences
