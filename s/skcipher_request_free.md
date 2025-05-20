# Function: <code>skcipher_request_free</code>

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
In fs/crypto/crypto.c (ffffffff81288abc)
Location: include/crypto/skcipher.h:503
Inline: True
```
```
In fs/crypto/fname.c (ffffffff812898f6)
Location: include/crypto/skcipher.h:503
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_decrypt
  - fs/crypto/fname.c:fname_encrypt
```
```
In fs/crypto/keyinfo.c (ffffffff8128a24e)
Location: include/crypto/skcipher.h:503
Inline: True
Inline callers:
  - fs/crypto/keyinfo.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff81339631)
Location: include/crypto/skcipher.h:503
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/keystore.c (ffffffff8133c783)
Location: include/crypto/skcipher.h:503
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff8136e6b9)
Location: include/crypto/skcipher.h:503
Inline: True
```
```
In crypto/drbg.c (ffffffff813eb7a9)
Location: include/crypto/skcipher.h:503
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_fini_sym_kernel
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
In fs/crypto/crypto.c (ffffffff8129d6e5)
Location: include/crypto/skcipher.h:503
Inline: True
```
```
In fs/crypto/fname.c (ffffffff8129e5b6)
Location: include/crypto/skcipher.h:503
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_decrypt
  - fs/crypto/fname.c:fname_encrypt
```
```
In fs/crypto/keyinfo.c (ffffffff8129ef8e)
Location: include/crypto/skcipher.h:503
Inline: True
Inline callers:
  - fs/crypto/keyinfo.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff8134f3d1)
Location: include/crypto/skcipher.h:503
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/keystore.c (ffffffff81352513)
Location: include/crypto/skcipher.h:503
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff813852da)
Location: include/crypto/skcipher.h:503
Inline: True
```
```
In crypto/drbg.c (ffffffff81404ef9)
Location: include/crypto/skcipher.h:503
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_fini_sym_kernel
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
In fs/crypto/crypto.c (ffffffff812ac457)
Location: include/crypto/skcipher.h:537
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_do_page_crypto
```
```
In fs/crypto/fname.c (ffffffff812ad084)
Location: include/crypto/skcipher.h:537
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_decrypt
  - fs/crypto/fname.c:fname_encrypt
```
```
In fs/crypto/keyinfo.c (ffffffff812ad9e9)
Location: include/crypto/skcipher.h:537
Inline: True
Inline callers:
  - fs/crypto/keyinfo.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff81363e91)
Location: include/crypto/skcipher.h:537
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/keystore.c (ffffffff813672a7)
Location: include/crypto/skcipher.h:537
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff813999d6)
Location: include/crypto/skcipher.h:537
Inline: True
```
```
In crypto/drbg.c (ffffffff814126c9)
Location: include/crypto/skcipher.h:537
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_fini_sym_kernel
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
In fs/crypto/crypto.c (ffffffff812cfc61)
Location: include/crypto/skcipher.h:537
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_do_page_crypto
```
```
In fs/crypto/fname.c (ffffffff812d0834)
Location: include/crypto/skcipher.h:537
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_decrypt
  - fs/crypto/fname.c:fname_encrypt
```
```
In fs/crypto/keyinfo.c (ffffffff812d0eb5)
Location: include/crypto/skcipher.h:537
Inline: True
Inline callers:
  - fs/crypto/keyinfo.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff81388c0a)
Location: include/crypto/skcipher.h:537
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/keystore.c (ffffffff8138bf30)
Location: include/crypto/skcipher.h:537
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff813bf1ac)
Location: include/crypto/skcipher.h:537
Inline: True
```
```
In crypto/drbg.c (ffffffff8143ce59)
Location: include/crypto/skcipher.h:537
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_fini_sym_kernel
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
In fs/crypto/crypto.c (ffffffff812fa54c)
Location: include/crypto/skcipher.h:538
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_do_page_crypto
```
```
In fs/crypto/fname.c (ffffffff812faec1)
Location: include/crypto/skcipher.h:538
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_encrypt
```
```
In fs/crypto/keyinfo.c (ffffffff812fb941)
Location: include/crypto/skcipher.h:538
Inline: True
Inline callers:
  - fs/crypto/keyinfo.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff813b7a63)
Location: include/crypto/skcipher.h:538
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/keystore.c (ffffffff813bab93)
Location: include/crypto/skcipher.h:538
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff813eff5b)
Location: include/crypto/skcipher.h:538
Inline: True
```
```
In crypto/drbg.c (ffffffff8146fc49)
Location: include/crypto/skcipher.h:538
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_fini_sym_kernel
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
In fs/crypto/crypto.c (ffffffff8130f89d)
Location: include/crypto/skcipher.h:607
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_do_page_crypto
```
```
In fs/crypto/fname.c (ffffffff81310292)
Location: include/crypto/skcipher.h:607
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_encrypt
```
```
In fs/crypto/keyinfo.c (ffffffff81310e91)
Location: include/crypto/skcipher.h:607
Inline: True
Inline callers:
  - fs/crypto/keyinfo.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff813d0fbe)
Location: include/crypto/skcipher.h:607
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/keystore.c (ffffffff813d4196)
Location: include/crypto/skcipher.h:607
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff8140b256)
Location: include/crypto/skcipher.h:607
Inline: True
```
```
In crypto/drbg.c (ffffffff8148d629)
Location: include/crypto/skcipher.h:607
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_fini_sym_kernel
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
In fs/crypto/crypto.c (ffffffff81336d55)
Location: include/crypto/skcipher.h:514
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
```
```
In fs/crypto/fname.c (ffffffff813376da)
Location: include/crypto/skcipher.h:514
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_encrypt
```
```
In fs/crypto/keyinfo.c (ffffffff813386b9)
Location: include/crypto/skcipher.h:514
Inline: True
Inline callers:
  - fs/crypto/keyinfo.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff813fbb4f)
Location: include/crypto/skcipher.h:514
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/keystore.c (ffffffff813febac)
Location: include/crypto/skcipher.h:514
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff81438011)
Location: include/crypto/skcipher.h:514
Inline: True
```
```
In crypto/drbg.c (ffffffff814bafa9)
Location: include/crypto/skcipher.h:514
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_fini_sym_kernel
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
In fs/crypto/crypto.c (ffffffff8134a925)
Location: include/crypto/skcipher.h:544
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
```
```
In fs/crypto/fname.c (ffffffff8134b298)
Location: include/crypto/skcipher.h:544
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_encrypt
```
```
In fs/crypto/keysetup_v1.c (ffffffff8134e4c7)
Location: include/crypto/skcipher.h:544
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff814159ad)
Location: include/crypto/skcipher.h:544
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/keystore.c (ffffffff81418a9c)
Location: include/crypto/skcipher.h:544
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff81451dd1)
Location: include/crypto/skcipher.h:544
Inline: True
```
```
In crypto/drbg.c (ffffffff814d3d79)
Location: include/crypto/skcipher.h:544
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_fini_sym_kernel
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
In fs/crypto/crypto.c (ffffffff81390085)
Location: include/crypto/skcipher.h:509
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
```
```
In fs/crypto/fname.c (ffffffff813908e1)
Location: include/crypto/skcipher.h:509
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_decrypt
  - fs/crypto/fname.c:fscrypt_fname_encrypt
```
```
In fs/crypto/keysetup_v1.c (ffffffff81394262)
Location: include/crypto/skcipher.h:509
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff81463d1b)
Location: include/crypto/skcipher.h:509
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/keystore.c (ffffffff81466cff)
Location: include/crypto/skcipher.h:509
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff814a4b1b)
Location: include/crypto/skcipher.h:509
Inline: True
```
```
In crypto/drbg.c (ffffffff815330c9)
Location: include/crypto/skcipher.h:509
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_fini_sym_kernel
```
```
In block/blk-crypto-fallback.c (ffffffff815825d4)
Location: include/crypto/skcipher.h:509
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
In fs/crypto/crypto.c (ffffffff813a16c5)
Location: include/crypto/skcipher.h:509
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
```
```
In fs/crypto/fname.c (ffffffff813a1d61)
Location: include/crypto/skcipher.h:509
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_decrypt
  - fs/crypto/fname.c:fscrypt_fname_encrypt
```
```
In fs/crypto/keysetup_v1.c (ffffffff813a5722)
Location: include/crypto/skcipher.h:509
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff8147f4db)
Location: include/crypto/skcipher.h:509
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/keystore.c (ffffffff81481eff)
Location: include/crypto/skcipher.h:509
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff814c231b)
Location: include/crypto/skcipher.h:509
Inline: True
```
```
In crypto/drbg.c (ffffffff81550019)
Location: include/crypto/skcipher.h:509
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_fini_sym_kernel
```
```
In block/blk-crypto-fallback.c (ffffffff8159f580)
Location: include/crypto/skcipher.h:509
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
In fs/crypto/crypto.c (ffffffff813a8853)
Location: include/crypto/skcipher.h:511
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
```
```
In fs/crypto/fname.c (ffffffff813a8f01)
Location: include/crypto/skcipher.h:511
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_decrypt
  - fs/crypto/fname.c:fscrypt_fname_encrypt
```
```
In fs/crypto/keysetup_v1.c (ffffffff813ac802)
Location: include/crypto/skcipher.h:511
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff81484e71)
Location: include/crypto/skcipher.h:511
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/keystore.c (ffffffff81487965)
Location: include/crypto/skcipher.h:511
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff814c8938)
Location: include/crypto/skcipher.h:511
Inline: True
```
```
In crypto/drbg.c (ffffffff81558819)
Location: include/crypto/skcipher.h:511
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_fini_sym_kernel
```
```
In block/blk-crypto-fallback.c (ffffffff815a6287)
Location: include/crypto/skcipher.h:511
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
In fs/crypto/crypto.c (ffffffff813f7f93)
Location: include/crypto/skcipher.h:511
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
```
```
In fs/crypto/fname.c (ffffffff813f8691)
Location: include/crypto/skcipher.h:511
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_decrypt
  - fs/crypto/fname.c:fscrypt_fname_encrypt
```
```
In fs/crypto/keysetup_v1.c (ffffffff813fc172)
Location: include/crypto/skcipher.h:511
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff814dc4f1)
Location: include/crypto/skcipher.h:511
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/keystore.c (ffffffff814df137)
Location: include/crypto/skcipher.h:511
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff81521402)
Location: include/crypto/skcipher.h:511
Inline: True
```
```
In crypto/drbg.c (ffffffff815b9ac9)
Location: include/crypto/skcipher.h:511
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_fini_sym_kernel
```
```
In block/blk-crypto-fallback.c (ffffffff8160eda7)
Location: include/crypto/skcipher.h:511
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
In fs/crypto/crypto.c (ffffffff8146ad3a)
Location: include/crypto/skcipher.h:515
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
```
```
In fs/crypto/fname.c (ffffffff8146b3ab)
Location: include/crypto/skcipher.h:515
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_decrypt
  - fs/crypto/fname.c:fscrypt_fname_encrypt
```
```
In fs/crypto/keysetup_v1.c (ffffffff8146f5eb)
Location: include/crypto/skcipher.h:515
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff8156a2f7)
Location: include/crypto/skcipher.h:515
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/keystore.c (ffffffff8156d19c)
Location: include/crypto/skcipher.h:515
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff815b4cb7)
Location: include/crypto/skcipher.h:515
Inline: True
```
```
In crypto/drbg.c (ffffffff81663099)
Location: include/crypto/skcipher.h:515
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_fini_sym_kernel
```
```
In block/blk-crypto-fallback.c (ffffffff816c362d)
Location: include/crypto/skcipher.h:515
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
In fs/crypto/crypto.c (ffffffff814fbe62)
Location: include/crypto/skcipher.h:515
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
```
```
In fs/crypto/fname.c (ffffffff814fc82c)
Location: include/crypto/skcipher.h:515
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_decrypt
  - fs/crypto/fname.c:fscrypt_fname_encrypt
```
```
In fs/crypto/keysetup_v1.c (ffffffff81500d6b)
Location: include/crypto/skcipher.h:515
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff8160e087)
Location: include/crypto/skcipher.h:515
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/keystore.c (ffffffff8161191f)
Location: include/crypto/skcipher.h:515
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff8165fc97)
Location: include/crypto/skcipher.h:515
Inline: True
```
```
In crypto/drbg.c (ffffffff8171d2e9)
Location: include/crypto/skcipher.h:515
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_fini_sym_kernel
```
```
In block/blk-crypto-fallback.c (ffffffff81784ac1)
Location: include/crypto/skcipher.h:515
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
In fs/crypto/crypto.c (ffffffff81533192)
Location: include/crypto/skcipher.h:537
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
```
```
In fs/crypto/fname.c (ffffffff81533d9c)
Location: include/crypto/skcipher.h:537
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_decrypt
  - fs/crypto/fname.c:fscrypt_fname_encrypt
```
```
In fs/crypto/keysetup_v1.c (ffffffff815383f8)
Location: include/crypto/skcipher.h:537
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff81645f03)
Location: include/crypto/skcipher.h:537
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/keystore.c (ffffffff8164986f)
Location: include/crypto/skcipher.h:537
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff816985fd)
Location: include/crypto/skcipher.h:537
Inline: True
```
```
In crypto/drbg.c (ffffffff81758b79)
Location: include/crypto/skcipher.h:537
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_fini_sym_kernel
```
```
In block/blk-crypto-fallback.c (ffffffff817c4e21)
Location: include/crypto/skcipher.h:537
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
In fs/crypto/crypto.c (ffffffff8156808e)
Location: include/crypto/skcipher.h:882
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_crypt_data_unit
```
```
In fs/crypto/fname.c (ffffffff81568d2c)
Location: include/crypto/skcipher.h:882
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_decrypt
  - fs/crypto/fname.c:fscrypt_fname_encrypt
```
```
In fs/crypto/keysetup_v1.c (ffffffff8156d548)
Location: include/crypto/skcipher.h:882
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff8167f3c3)
Location: include/crypto/skcipher.h:882
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/keystore.c (ffffffff81682d3f)
Location: include/crypto/skcipher.h:882
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff816d4c7d)
Location: include/crypto/skcipher.h:882
Inline: True
```
```
In crypto/drbg.c (ffffffff8179aa79)
Location: include/crypto/skcipher.h:882
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_fini_sym_kernel
```
```
In block/blk-crypto-fallback.c (ffffffff81809b11)
Location: include/crypto/skcipher.h:882
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
In fs/crypto/crypto.c (ffff80001040b0e0)
Location: include/crypto/skcipher.h:544
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
```
```
In fs/crypto/fname.c (ffff80001040bc8c)
Location: include/crypto/skcipher.h:544
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_encrypt
```
```
In fs/crypto/keysetup_v1.c (ffff80001040f6dc)
Location: include/crypto/skcipher.h:544
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffff8000104f6f68)
Location: include/crypto/skcipher.h:544
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/keystore.c (ffff8000104fa288)
Location: include/crypto/skcipher.h:544
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (ffff80001053d5c0)
Location: include/crypto/skcipher.h:544
Inline: True
```
```
In crypto/drbg.c (ffff8000105d0800)
Location: include/crypto/skcipher.h:544
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_fini_sym_kernel
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
In fs/crypto/crypto.c (c05d8294)
Location: include/crypto/skcipher.h:544
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
```
```
In fs/crypto/fname.c (c05d8a7c)
Location: include/crypto/skcipher.h:544
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_decrypt
  - fs/crypto/fname.c:fname_encrypt
```
```
In fs/crypto/keysetup_v1.c (c05dc3c4)
Location: include/crypto/skcipher.h:544
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
```
```
In fs/ecryptfs/crypto.c (c06b4c74)
Location: include/crypto/skcipher.h:544
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_extent
```
```
In fs/ecryptfs/keystore.c (c06b79e0)
Location: include/crypto/skcipher.h:544
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (c06f2fdc)
Location: include/crypto/skcipher.h:544
Inline: True
```
```
In crypto/drbg.c (c077e1a8)
Location: include/crypto/skcipher.h:544
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_fini_sym_kernel
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
In fs/crypto/crypto.c (c000000000517bb0)
Location: include/crypto/skcipher.h:544
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
```
```
In fs/crypto/fname.c (c0000000005189c4)
Location: include/crypto/skcipher.h:544
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_encrypt
```
```
In fs/crypto/keysetup_v1.c (c00000000051d198)
Location: include/crypto/skcipher.h:544
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (c000000000638290)
Location: include/crypto/skcipher.h:544
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/keystore.c (c00000000063c904)
Location: include/crypto/skcipher.h:544
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (c00000000068caf8)
Location: include/crypto/skcipher.h:544
Inline: True
```
```
In crypto/drbg.c (c00000000075cbb4)
Location: include/crypto/skcipher.h:544
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_fini_sym_kernel
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
In fs/crypto/crypto.c (ffffffe0002b4dfa)
Location: include/crypto/skcipher.h:544
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
```
```
In fs/crypto/fname.c (ffffffe0002b572a)
Location: include/crypto/skcipher.h:544
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_encrypt
```
```
In fs/crypto/keysetup_v1.c (ffffffe0002b8590)
Location: include/crypto/skcipher.h:544
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
```
```
In fs/ecryptfs/crypto.c (ffffffe000365b36)
Location: include/crypto/skcipher.h:544
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/keystore.c (ffffffe000368a46)
Location: include/crypto/skcipher.h:544
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffe00039aa18)
Location: include/crypto/skcipher.h:544
Inline: True
```
```
In crypto/drbg.c (ffffffe000415452)
Location: include/crypto/skcipher.h:544
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_fini_sym_kernel
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
In fs/crypto/crypto.c (ffffffff81342f05)
Location: include/crypto/skcipher.h:544
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
```
```
In fs/crypto/fname.c (ffffffff81343878)
Location: include/crypto/skcipher.h:544
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_encrypt
```
```
In fs/crypto/keysetup_v1.c (ffffffff81346aa7)
Location: include/crypto/skcipher.h:544
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff8140df8d)
Location: include/crypto/skcipher.h:544
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/keystore.c (ffffffff8141107c)
Location: include/crypto/skcipher.h:544
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff8144a3b1)
Location: include/crypto/skcipher.h:544
Inline: True
```
```
In crypto/drbg.c (ffffffff814cc359)
Location: include/crypto/skcipher.h:544
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_fini_sym_kernel
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
In fs/crypto/crypto.c (ffffffff81333be5)
Location: include/crypto/skcipher.h:544
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
```
```
In fs/crypto/fname.c (ffffffff81334558)
Location: include/crypto/skcipher.h:544
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_encrypt
```
```
In fs/crypto/keysetup_v1.c (ffffffff81337787)
Location: include/crypto/skcipher.h:544
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff813fea0d)
Location: include/crypto/skcipher.h:544
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/keystore.c (ffffffff81401afc)
Location: include/crypto/skcipher.h:544
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff8143ae01)
Location: include/crypto/skcipher.h:544
Inline: True
```
```
In crypto/drbg.c (ffffffff814bcd79)
Location: include/crypto/skcipher.h:544
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_fini_sym_kernel
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
In fs/crypto/crypto.c (ffffffff813409d5)
Location: include/crypto/skcipher.h:544
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
```
```
In fs/crypto/fname.c (ffffffff81341348)
Location: include/crypto/skcipher.h:544
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_encrypt
```
```
In fs/crypto/keysetup_v1.c (ffffffff81344577)
Location: include/crypto/skcipher.h:544
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff8140b30d)
Location: include/crypto/skcipher.h:544
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/keystore.c (ffffffff8140e3fc)
Location: include/crypto/skcipher.h:544
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff81446451)
Location: include/crypto/skcipher.h:544
Inline: True
```
```
In crypto/drbg.c (ffffffff814c83e9)
Location: include/crypto/skcipher.h:544
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_fini_sym_kernel
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
In fs/crypto/crypto.c (ffffffff81353cd5)
Location: include/crypto/skcipher.h:544
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
```
```
In fs/crypto/fname.c (ffffffff81354648)
Location: include/crypto/skcipher.h:544
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_encrypt
```
```
In fs/crypto/keysetup_v1.c (ffffffff81357857)
Location: include/crypto/skcipher.h:544
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff81420fad)
Location: include/crypto/skcipher.h:544
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/keystore.c (ffffffff8142406c)
Location: include/crypto/skcipher.h:544
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff8145d781)
Location: include/crypto/skcipher.h:544
Inline: True
```
```
In crypto/drbg.c (ffffffff814e0eb9)
Location: include/crypto/skcipher.h:544
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_fini_sym_kernel
```
</details>
</li>
</ul>

## Differences
