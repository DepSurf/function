# Function: <code>skcipher_request_alloc</code>

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
In fs/crypto/crypto.c (ffffffff81288978)
Location: include/crypto/skcipher.h:485
Inline: True
```
```
In fs/crypto/fname.c (ffffffff81289840)
Location: include/crypto/skcipher.h:485
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_decrypt
  - fs/crypto/fname.c:fname_encrypt
```
```
In fs/crypto/keyinfo.c (ffffffff8128a186)
Location: include/crypto/skcipher.h:485
Inline: True
Inline callers:
  - fs/crypto/keyinfo.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff813395a9)
Location: include/crypto/skcipher.h:485
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/keystore.c (ffffffff8133c6cf)
Location: include/crypto/skcipher.h:485
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff8136e424)
Location: include/crypto/skcipher.h:485
Inline: True
```
```
In crypto/drbg.c (ffffffff813eed56)
Location: include/crypto/skcipher.h:485
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
In fs/crypto/crypto.c (ffffffff8129d5aa)
Location: include/crypto/skcipher.h:485
Inline: True
```
```
In fs/crypto/fname.c (ffffffff8129e500)
Location: include/crypto/skcipher.h:485
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_decrypt
  - fs/crypto/fname.c:fname_encrypt
```
```
In fs/crypto/keyinfo.c (ffffffff8129eec6)
Location: include/crypto/skcipher.h:485
Inline: True
Inline callers:
  - fs/crypto/keyinfo.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff8134f349)
Location: include/crypto/skcipher.h:485
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/keystore.c (ffffffff8135245f)
Location: include/crypto/skcipher.h:485
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff81384c44)
Location: include/crypto/skcipher.h:485
Inline: True
```
```
In crypto/drbg.c (ffffffff8140859c)
Location: include/crypto/skcipher.h:485
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
In fs/crypto/crypto.c (ffffffff812ac34c)
Location: include/crypto/skcipher.h:519
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_do_page_crypto
```
```
In fs/crypto/fname.c (ffffffff812acfc6)
Location: include/crypto/skcipher.h:519
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_decrypt
  - fs/crypto/fname.c:fname_encrypt
```
```
In fs/crypto/keyinfo.c (ffffffff812ad929)
Location: include/crypto/skcipher.h:519
Inline: True
Inline callers:
  - fs/crypto/keyinfo.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff81363dea)
Location: include/crypto/skcipher.h:519
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/keystore.c (ffffffff813671f2)
Location: include/crypto/skcipher.h:519
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff813992bb)
Location: include/crypto/skcipher.h:519
Inline: True
```
```
In crypto/drbg.c (ffffffff81415c8c)
Location: include/crypto/skcipher.h:519
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
In fs/crypto/crypto.c (ffffffff812cfb5f)
Location: include/crypto/skcipher.h:519
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_do_page_crypto
```
```
In fs/crypto/fname.c (ffffffff812d0770)
Location: include/crypto/skcipher.h:519
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_decrypt
  - fs/crypto/fname.c:fname_encrypt
```
```
In fs/crypto/keyinfo.c (ffffffff812d0dea)
Location: include/crypto/skcipher.h:519
Inline: True
Inline callers:
  - fs/crypto/keyinfo.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff81388b5a)
Location: include/crypto/skcipher.h:519
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/keystore.c (ffffffff8138be75)
Location: include/crypto/skcipher.h:519
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff813bead1)
Location: include/crypto/skcipher.h:519
Inline: True
```
```
In crypto/drbg.c (ffffffff81440464)
Location: include/crypto/skcipher.h:519
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
In fs/crypto/crypto.c (ffffffff812fa441)
Location: include/crypto/skcipher.h:520
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_do_page_crypto
```
```
In fs/crypto/fname.c (ffffffff812fae38)
Location: include/crypto/skcipher.h:520
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_encrypt
```
```
In fs/crypto/keyinfo.c (ffffffff812fb980)
Location: include/crypto/skcipher.h:520
Inline: True
Inline callers:
  - fs/crypto/keyinfo.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff813b79aa)
Location: include/crypto/skcipher.h:520
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/keystore.c (ffffffff813baad0)
Location: include/crypto/skcipher.h:520
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff813ef915)
Location: include/crypto/skcipher.h:520
Inline: True
```
```
In crypto/drbg.c (ffffffff81473344)
Location: include/crypto/skcipher.h:520
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
In fs/crypto/crypto.c (ffffffff8130f773)
Location: include/crypto/skcipher.h:589
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_do_page_crypto
```
```
In fs/crypto/fname.c (ffffffff813101eb)
Location: include/crypto/skcipher.h:589
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_encrypt
```
```
In fs/crypto/keyinfo.c (ffffffff81310ed3)
Location: include/crypto/skcipher.h:589
Inline: True
Inline callers:
  - fs/crypto/keyinfo.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff813d0ebe)
Location: include/crypto/skcipher.h:589
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/keystore.c (ffffffff813d4090)
Location: include/crypto/skcipher.h:589
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff8140ab65)
Location: include/crypto/skcipher.h:589
Inline: True
```
```
In crypto/drbg.c (ffffffff8148f8b9)
Location: include/crypto/skcipher.h:589
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
In fs/crypto/crypto.c (ffffffff81336c55)
Location: include/crypto/skcipher.h:496
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
```
```
In fs/crypto/fname.c (ffffffff81337658)
Location: include/crypto/skcipher.h:496
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_encrypt
```
```
In fs/crypto/keyinfo.c (ffffffff81338604)
Location: include/crypto/skcipher.h:496
Inline: True
Inline callers:
  - fs/crypto/keyinfo.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff813fbaa5)
Location: include/crypto/skcipher.h:496
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/keystore.c (ffffffff813feafa)
Location: include/crypto/skcipher.h:496
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff81437df5)
Location: include/crypto/skcipher.h:496
Inline: True
```
```
In crypto/drbg.c (ffffffff814be250)
Location: include/crypto/skcipher.h:496
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
In fs/crypto/crypto.c (ffffffff8134a825)
Location: include/crypto/skcipher.h:526
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
```
```
In fs/crypto/fname.c (ffffffff8134b218)
Location: include/crypto/skcipher.h:526
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_encrypt
```
```
In fs/crypto/keysetup_v1.c (ffffffff8134e413)
Location: include/crypto/skcipher.h:526
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff81415906)
Location: include/crypto/skcipher.h:526
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/keystore.c (ffffffff814189ea)
Location: include/crypto/skcipher.h:526
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff81451bb5)
Location: include/crypto/skcipher.h:526
Inline: True
```
```
In crypto/drbg.c (ffffffff814d70a0)
Location: include/crypto/skcipher.h:526
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
In fs/crypto/crypto.c (ffffffff8138ff85)
Location: include/crypto/skcipher.h:491
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
```
```
In fs/crypto/fname.c (ffffffff8139082c)
Location: include/crypto/skcipher.h:491
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_decrypt
  - fs/crypto/fname.c:fscrypt_fname_encrypt
```
```
In fs/crypto/keysetup_v1.c (ffffffff813941b3)
Location: include/crypto/skcipher.h:491
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff81463c96)
Location: include/crypto/skcipher.h:491
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/keystore.c (ffffffff81466c4e)
Location: include/crypto/skcipher.h:491
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff814a4332)
Location: include/crypto/skcipher.h:491
Inline: True
```
```
In crypto/drbg.c (ffffffff815338ae)
Location: include/crypto/skcipher.h:491
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
```
```
In block/blk-crypto-fallback.c (ffffffff81582026)
Location: include/crypto/skcipher.h:491
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
In fs/crypto/crypto.c (ffffffff813a15c5)
Location: include/crypto/skcipher.h:491
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
```
```
In fs/crypto/fname.c (ffffffff813a1cac)
Location: include/crypto/skcipher.h:491
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_decrypt
  - fs/crypto/fname.c:fscrypt_fname_encrypt
```
```
In fs/crypto/keysetup_v1.c (ffffffff813a5673)
Location: include/crypto/skcipher.h:491
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff8147f456)
Location: include/crypto/skcipher.h:491
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/keystore.c (ffffffff81481e4e)
Location: include/crypto/skcipher.h:491
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff814c1b32)
Location: include/crypto/skcipher.h:491
Inline: True
```
```
In crypto/drbg.c (ffffffff815507fe)
Location: include/crypto/skcipher.h:491
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
```
```
In block/blk-crypto-fallback.c (ffffffff8159eff6)
Location: include/crypto/skcipher.h:491
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
In fs/crypto/crypto.c (ffffffff813a8754)
Location: include/crypto/skcipher.h:493
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
```
```
In fs/crypto/fname.c (ffffffff813a8e4c)
Location: include/crypto/skcipher.h:493
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_decrypt
  - fs/crypto/fname.c:fscrypt_fname_encrypt
```
```
In fs/crypto/keysetup_v1.c (ffffffff813ac753)
Location: include/crypto/skcipher.h:493
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff81484de9)
Location: include/crypto/skcipher.h:493
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/keystore.c (ffffffff814878b4)
Location: include/crypto/skcipher.h:493
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff814c7fb2)
Location: include/crypto/skcipher.h:493
Inline: True
```
```
In crypto/drbg.c (ffffffff81558fde)
Location: include/crypto/skcipher.h:493
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
```
```
In block/blk-crypto-fallback.c (ffffffff815a5e06)
Location: include/crypto/skcipher.h:493
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
In fs/crypto/crypto.c (ffffffff813f7e94)
Location: include/crypto/skcipher.h:493
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
```
```
In fs/crypto/fname.c (ffffffff813f85dc)
Location: include/crypto/skcipher.h:493
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_decrypt
  - fs/crypto/fname.c:fscrypt_fname_encrypt
```
```
In fs/crypto/keysetup_v1.c (ffffffff813fc0c3)
Location: include/crypto/skcipher.h:493
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff814dc469)
Location: include/crypto/skcipher.h:493
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/keystore.c (ffffffff814df085)
Location: include/crypto/skcipher.h:493
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff81520aa2)
Location: include/crypto/skcipher.h:493
Inline: True
```
```
In crypto/drbg.c (ffffffff815ba29e)
Location: include/crypto/skcipher.h:493
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
```
```
In block/blk-crypto-fallback.c (ffffffff8160e916)
Location: include/crypto/skcipher.h:493
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
In fs/crypto/crypto.c (ffffffff8146ac3c)
Location: include/crypto/skcipher.h:497
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
```
```
In fs/crypto/fname.c (ffffffff8146b303)
Location: include/crypto/skcipher.h:497
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_decrypt
  - fs/crypto/fname.c:fscrypt_fname_encrypt
```
```
In fs/crypto/keysetup_v1.c (ffffffff8146f53c)
Location: include/crypto/skcipher.h:497
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff8156a271)
Location: include/crypto/skcipher.h:497
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/keystore.c (ffffffff8156d0eb)
Location: include/crypto/skcipher.h:497
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff815b41e2)
Location: include/crypto/skcipher.h:497
Inline: True
```
```
In crypto/drbg.c (ffffffff81663333)
Location: include/crypto/skcipher.h:497
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
```
```
In block/blk-crypto-fallback.c (ffffffff816c3096)
Location: include/crypto/skcipher.h:497
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
In fs/crypto/crypto.c (ffffffff814fbd59)
Location: include/crypto/skcipher.h:497
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
```
```
In fs/crypto/fname.c (ffffffff814fc783)
Location: include/crypto/skcipher.h:497
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_decrypt
  - fs/crypto/fname.c:fscrypt_fname_encrypt
```
```
In fs/crypto/keysetup_v1.c (ffffffff81500cbc)
Location: include/crypto/skcipher.h:497
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff8160e001)
Location: include/crypto/skcipher.h:497
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/keystore.c (ffffffff8161186f)
Location: include/crypto/skcipher.h:497
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff8165efce)
Location: include/crypto/skcipher.h:497
Inline: True
```
```
In crypto/drbg.c (ffffffff8171d5c3)
Location: include/crypto/skcipher.h:497
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
```
```
In block/blk-crypto-fallback.c (ffffffff81784506)
Location: include/crypto/skcipher.h:497
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
In fs/crypto/crypto.c (ffffffff81533089)
Location: include/crypto/skcipher.h:519
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
```
```
In fs/crypto/fname.c (ffffffff81533cf3)
Location: include/crypto/skcipher.h:519
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_decrypt
  - fs/crypto/fname.c:fscrypt_fname_encrypt
```
```
In fs/crypto/keysetup_v1.c (ffffffff8153834b)
Location: include/crypto/skcipher.h:519
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff81645e7f)
Location: include/crypto/skcipher.h:519
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/keystore.c (ffffffff816497bf)
Location: include/crypto/skcipher.h:519
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff81697917)
Location: include/crypto/skcipher.h:519
Inline: True
```
```
In crypto/drbg.c (ffffffff81758ea3)
Location: include/crypto/skcipher.h:519
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
```
```
In block/blk-crypto-fallback.c (ffffffff817c483a)
Location: include/crypto/skcipher.h:519
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
In fs/crypto/crypto.c (ffffffff81567f86)
Location: include/crypto/skcipher.h:864
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_crypt_data_unit
```
```
In fs/crypto/fname.c (ffffffff81568c83)
Location: include/crypto/skcipher.h:864
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_decrypt
  - fs/crypto/fname.c:fscrypt_fname_encrypt
```
```
In fs/crypto/keysetup_v1.c (ffffffff8156d49b)
Location: include/crypto/skcipher.h:864
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff8167f33f)
Location: include/crypto/skcipher.h:864
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/keystore.c (ffffffff81682c8f)
Location: include/crypto/skcipher.h:864
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff816d3f97)
Location: include/crypto/skcipher.h:864
Inline: True
```
```
In crypto/drbg.c (ffffffff8179ada3)
Location: include/crypto/skcipher.h:864
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
```
```
In block/blk-crypto-fallback.c (ffffffff818094fa)
Location: include/crypto/skcipher.h:864
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
In fs/crypto/crypto.c (ffff80001040b018)
Location: include/crypto/skcipher.h:526
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
```
```
In fs/crypto/fname.c (ffff80001040bc10)
Location: include/crypto/skcipher.h:526
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_encrypt
```
```
In fs/crypto/keysetup_v1.c (ffff80001040f638)
Location: include/crypto/skcipher.h:526
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffff8000104f6ecc)
Location: include/crypto/skcipher.h:526
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/keystore.c (ffff8000104fa214)
Location: include/crypto/skcipher.h:526
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (ffff80001053cb58)
Location: include/crypto/skcipher.h:526
Inline: True
```
```
In crypto/drbg.c (ffff8000105d1544)
Location: include/crypto/skcipher.h:526
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
In fs/crypto/crypto.c (c05d81ac)
Location: include/crypto/skcipher.h:526
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
```
```
In fs/crypto/fname.c (c05d89dc)
Location: include/crypto/skcipher.h:526
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_decrypt
  - fs/crypto/fname.c:fname_encrypt
```
```
In fs/crypto/keysetup_v1.c (c05dc314)
Location: include/crypto/skcipher.h:526
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
```
```
In fs/ecryptfs/crypto.c (c06b4bb4)
Location: include/crypto/skcipher.h:526
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_extent
```
```
In fs/ecryptfs/keystore.c (c06b7960)
Location: include/crypto/skcipher.h:526
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (c06f2dc4)
Location: include/crypto/skcipher.h:526
Inline: True
```
```
In crypto/drbg.c (c07804c4)
Location: include/crypto/skcipher.h:526
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
In fs/crypto/crypto.c (c000000000517ac8)
Location: include/crypto/skcipher.h:526
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
```
```
In fs/crypto/fname.c (c000000000518938)
Location: include/crypto/skcipher.h:526
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_encrypt
```
```
In fs/crypto/keysetup_v1.c (c00000000051d0d4)
Location: include/crypto/skcipher.h:526
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (c0000000006381d0)
Location: include/crypto/skcipher.h:526
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/keystore.c (c00000000063c878)
Location: include/crypto/skcipher.h:526
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (c00000000068c888)
Location: include/crypto/skcipher.h:526
Inline: True
```
```
In crypto/drbg.c (c00000000075fce0)
Location: include/crypto/skcipher.h:526
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
In fs/crypto/crypto.c (ffffffe0002b4d3e)
Location: include/crypto/skcipher.h:526
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
```
```
In fs/crypto/fname.c (ffffffe0002b56b6)
Location: include/crypto/skcipher.h:526
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_encrypt
```
```
In fs/crypto/keysetup_v1.c (ffffffe0002b84ec)
Location: include/crypto/skcipher.h:526
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
```
```
In fs/ecryptfs/crypto.c (ffffffe000365a9a)
Location: include/crypto/skcipher.h:526
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/keystore.c (ffffffe0003689c2)
Location: include/crypto/skcipher.h:526
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffe00039a842)
Location: include/crypto/skcipher.h:526
Inline: True
```
```
In crypto/drbg.c (ffffffe0004162c4)
Location: include/crypto/skcipher.h:526
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
In fs/crypto/crypto.c (ffffffff81342e05)
Location: include/crypto/skcipher.h:526
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
```
```
In fs/crypto/fname.c (ffffffff813437f8)
Location: include/crypto/skcipher.h:526
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_encrypt
```
```
In fs/crypto/keysetup_v1.c (ffffffff813469f3)
Location: include/crypto/skcipher.h:526
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff8140dee6)
Location: include/crypto/skcipher.h:526
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/keystore.c (ffffffff81410fca)
Location: include/crypto/skcipher.h:526
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff8144a195)
Location: include/crypto/skcipher.h:526
Inline: True
```
```
In crypto/drbg.c (ffffffff814cf680)
Location: include/crypto/skcipher.h:526
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
In fs/crypto/crypto.c (ffffffff81333ae5)
Location: include/crypto/skcipher.h:526
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
```
```
In fs/crypto/fname.c (ffffffff813344d8)
Location: include/crypto/skcipher.h:526
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_encrypt
```
```
In fs/crypto/keysetup_v1.c (ffffffff813376d3)
Location: include/crypto/skcipher.h:526
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff813fe966)
Location: include/crypto/skcipher.h:526
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/keystore.c (ffffffff81401a4a)
Location: include/crypto/skcipher.h:526
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff8143abe5)
Location: include/crypto/skcipher.h:526
Inline: True
```
```
In crypto/drbg.c (ffffffff814c00a0)
Location: include/crypto/skcipher.h:526
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
In fs/crypto/crypto.c (ffffffff813408d5)
Location: include/crypto/skcipher.h:526
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
```
```
In fs/crypto/fname.c (ffffffff813412c8)
Location: include/crypto/skcipher.h:526
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_encrypt
```
```
In fs/crypto/keysetup_v1.c (ffffffff813444c3)
Location: include/crypto/skcipher.h:526
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff8140b266)
Location: include/crypto/skcipher.h:526
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/keystore.c (ffffffff8140e34a)
Location: include/crypto/skcipher.h:526
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff81446235)
Location: include/crypto/skcipher.h:526
Inline: True
```
```
In crypto/drbg.c (ffffffff814cb710)
Location: include/crypto/skcipher.h:526
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
In fs/crypto/crypto.c (ffffffff81353bd5)
Location: include/crypto/skcipher.h:526
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
```
```
In fs/crypto/fname.c (ffffffff813545c8)
Location: include/crypto/skcipher.h:526
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_encrypt
```
```
In fs/crypto/keysetup_v1.c (ffffffff813577a3)
Location: include/crypto/skcipher.h:526
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff81420f06)
Location: include/crypto/skcipher.h:526
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/keystore.c (ffffffff81423fba)
Location: include/crypto/skcipher.h:526
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff8145d565)
Location: include/crypto/skcipher.h:526
Inline: True
```
```
In crypto/drbg.c (ffffffff814e41e0)
Location: include/crypto/skcipher.h:526
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
```
</details>
</li>
</ul>

## Differences
