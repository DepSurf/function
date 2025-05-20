# Function: <code>crypto_wait_req</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (ffffffff812cfc4d)
Location: include/linux/crypto.h:499
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_do_page_crypto
```
```
In fs/crypto/fname.c (ffffffff812d081f)
Location: include/linux/crypto.h:499
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_decrypt
  - fs/crypto/fname.c:fname_encrypt
```
```
In fs/crypto/keyinfo.c (ffffffff812d0eab)
Location: include/linux/crypto.h:499
Inline: True
Inline callers:
  - fs/crypto/keyinfo.c:derive_key_aes
```
```
In security/integrity/ima/ima_crypto.c (ffffffff81420b32)
Location: include/linux/crypto.h:499
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
```
```
In crypto/gcm.c (ffffffff8143a48e)
Location: include/linux/crypto.h:499
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (ffffffff8143cf47)
Location: include/linux/crypto.h:499
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff8144256d)
Location: include/linux/crypto.h:499
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
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
In fs/crypto/crypto.c (ffffffff812fa53a)
Location: include/linux/crypto.h:512
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_do_page_crypto
  - fs/crypto/crypto.c:fscrypt_do_page_crypto
```
```
In fs/crypto/fname.c (ffffffff812faeae)
Location: include/linux/crypto.h:512
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_encrypt
```
```
In fs/crypto/keyinfo.c (ffffffff812fba39)
Location: include/linux/crypto.h:512
Inline: True
Inline callers:
  - fs/crypto/keyinfo.c:derive_key_aes
```
```
In security/integrity/ima/ima_crypto.c (ffffffff81452fc0)
Location: include/linux/crypto.h:512
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
```
```
In crypto/gcm.c (ffffffff8146ce4a)
Location: include/linux/crypto.h:512
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (ffffffff8146fdfe)
Location: include/linux/crypto.h:512
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff8147548f)
Location: include/linux/crypto.h:512
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
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
In fs/crypto/crypto.c (ffffffff8130f88d)
Location: include/linux/crypto.h:683
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_do_page_crypto
  - fs/crypto/crypto.c:fscrypt_do_page_crypto
  - fs/crypto/crypto.c:fscrypt_do_page_crypto
  - fs/crypto/crypto.c:fscrypt_do_page_crypto
```
```
In fs/crypto/fname.c (ffffffff81310286)
Location: include/linux/crypto.h:683
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_encrypt
  - fs/crypto/fname.c:fname_encrypt
```
```
In fs/crypto/keyinfo.c (ffffffff81310fb6)
Location: include/linux/crypto.h:683
Inline: True
Inline callers:
  - fs/crypto/keyinfo.c:derive_key_aes
```
```
In security/integrity/ima/ima_crypto.c (ffffffff81470130)
Location: include/linux/crypto.h:683
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
```
```
In crypto/gcm.c (ffffffff8148943a)
Location: include/linux/crypto.h:683
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (ffffffff8149013c)
Location: include/linux/crypto.h:683
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff81493332)
Location: include/linux/crypto.h:683
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
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
In fs/crypto/crypto.c (ffffffff81336d4b)
Location: include/linux/crypto.h:680
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/crypto.c:fscrypt_crypt_block
```
```
In fs/crypto/fname.c (ffffffff813376d0)
Location: include/linux/crypto.h:680
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_encrypt
  - fs/crypto/fname.c:fname_encrypt
```
```
In fs/crypto/keyinfo.c (ffffffff813386af)
Location: include/linux/crypto.h:680
Inline: True
Inline callers:
  - fs/crypto/keyinfo.c:derive_key_aes
```
```
In security/integrity/ima/ima_crypto.c (ffffffff8149db15)
Location: include/linux/crypto.h:680
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/gcm.c (ffffffff814b7063)
Location: include/linux/crypto.h:680
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (ffffffff814bd2f7)
Location: include/linux/crypto.h:680
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff814c0f74)
Location: include/linux/crypto.h:680
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
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
In fs/crypto/crypto.c (ffffffff8134a91b)
Location: include/linux/crypto.h:680
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/crypto.c:fscrypt_crypt_block
```
```
In fs/crypto/fname.c (ffffffff8134b28e)
Location: include/linux/crypto.h:680
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_encrypt
  - fs/crypto/fname.c:fname_encrypt
```
```
In fs/crypto/keysetup_v1.c (ffffffff8134e4bd)
Location: include/linux/crypto.h:680
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/verity/hash_algs.c (ffffffff81350545)
Location: include/linux/crypto.h:680
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In security/integrity/ima/ima_crypto.c (ffffffff814b7f55)
Location: include/linux/crypto.h:680
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/gcm.c (ffffffff814d0283)
Location: include/linux/crypto.h:680
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (ffffffff814d5f80)
Location: include/linux/crypto.h:680
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff814d9da4)
Location: include/linux/crypto.h:680
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
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
In fs/crypto/crypto.c (ffffffff8139007b)
Location: include/linux/crypto.h:557
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/crypto.c:fscrypt_crypt_block
```
```
In fs/crypto/fname.c (ffffffff813908d7)
Location: include/linux/crypto.h:557
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_decrypt
  - fs/crypto/fname.c:fname_decrypt
  - fs/crypto/fname.c:fscrypt_fname_encrypt
  - fs/crypto/fname.c:fscrypt_fname_encrypt
```
```
In fs/crypto/keysetup_v1.c (ffffffff81394258)
Location: include/linux/crypto.h:557
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/verity/hash_algs.c (ffffffff81396f0c)
Location: include/linux/crypto.h:557
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In security/integrity/ima/ima_crypto.c (ffffffff81516f85)
Location: include/linux/crypto.h:557
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:calc_buffer_ahash_atfm
  - security/integrity/ima/ima_crypto.c:calc_buffer_ahash_atfm
  - security/integrity/ima/ima_crypto.c:calc_buffer_ahash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/gcm.c (ffffffff815302e3)
Location: include/linux/crypto.h:557
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (ffffffff81535b34)
Location: include/linux/crypto.h:557
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff8153933b)
Location: include/linux/crypto.h:557
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
```
```
In block/blk-crypto-fallback.c (ffffffff815825a8)
Location: include/linux/crypto.h:557
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio
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
In mm/zswap.c (ffffffff812cd5b4)
Location: include/linux/crypto.h:591
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_writeback_entry
  - mm/zswap.c:zswap_writeback_entry
```
```
In fs/crypto/crypto.c (ffffffff813a16bb)
Location: include/linux/crypto.h:591
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/crypto.c:fscrypt_crypt_block
```
```
In fs/crypto/fname.c (ffffffff813a1d57)
Location: include/linux/crypto.h:591
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_decrypt
  - fs/crypto/fname.c:fname_decrypt
  - fs/crypto/fname.c:fscrypt_fname_encrypt
  - fs/crypto/fname.c:fscrypt_fname_encrypt
```
```
In fs/crypto/keysetup_v1.c (ffffffff813a5718)
Location: include/linux/crypto.h:591
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/verity/hash_algs.c (ffffffff813a8b3c)
Location: include/linux/crypto.h:591
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In security/integrity/ima/ima_crypto.c (ffffffff81534145)
Location: include/linux/crypto.h:591
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:calc_buffer_ahash_atfm
  - security/integrity/ima/ima_crypto.c:calc_buffer_ahash_atfm
  - security/integrity/ima/ima_crypto.c:calc_buffer_ahash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/gcm.c (ffffffff8154d232)
Location: include/linux/crypto.h:591
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (ffffffff81552aa4)
Location: include/linux/crypto.h:591
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff8155612d)
Location: include/linux/crypto.h:591
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
```
```
In block/blk-crypto-fallback.c (ffffffff8159f554)
Location: include/linux/crypto.h:591
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio
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
In mm/zswap.c (ffffffff812d3ffd)
Location: include/linux/crypto.h:591
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_writeback_entry
  - mm/zswap.c:zswap_writeback_entry
```
```
In fs/crypto/crypto.c (ffffffff813a8849)
Location: include/linux/crypto.h:591
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/crypto.c:fscrypt_crypt_block
```
```
In fs/crypto/fname.c (ffffffff813a8ef7)
Location: include/linux/crypto.h:591
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_decrypt
  - fs/crypto/fname.c:fname_decrypt
  - fs/crypto/fname.c:fscrypt_fname_encrypt
  - fs/crypto/fname.c:fscrypt_fname_encrypt
```
```
In fs/crypto/keysetup_v1.c (ffffffff813ac7f8)
Location: include/linux/crypto.h:591
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/verity/hash_algs.c (ffffffff813afbac)
Location: include/linux/crypto.h:591
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In security/integrity/ima/ima_crypto.c (ffffffff8153d131)
Location: include/linux/crypto.h:591
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/gcm.c (ffffffff815551ad)
Location: include/linux/crypto.h:591
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (ffffffff8155b364)
Location: include/linux/crypto.h:591
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff8155e892)
Location: include/linux/crypto.h:591
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
```
```
In block/blk-crypto-fallback.c (ffffffff815a625b)
Location: include/linux/crypto.h:591
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio
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
In mm/zswap.c (ffffffff81319ca7)
Location: include/linux/crypto.h:591
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_writeback_entry
  - mm/zswap.c:zswap_writeback_entry
```
```
In fs/crypto/crypto.c (ffffffff813f7f89)
Location: include/linux/crypto.h:591
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/crypto.c:fscrypt_crypt_block
```
```
In fs/crypto/fname.c (ffffffff813f8687)
Location: include/linux/crypto.h:591
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_decrypt
  - fs/crypto/fname.c:fname_decrypt
  - fs/crypto/fname.c:fscrypt_fname_encrypt
  - fs/crypto/fname.c:fscrypt_fname_encrypt
```
```
In fs/crypto/keysetup_v1.c (ffffffff813fc168)
Location: include/linux/crypto.h:591
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/verity/hash_algs.c (ffffffff813ff79c)
Location: include/linux/crypto.h:591
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In security/integrity/ima/ima_crypto.c (ffffffff8159bfb1)
Location: include/linux/crypto.h:591
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/gcm.c (ffffffff815b61dd)
Location: include/linux/crypto.h:591
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (ffffffff815bbd04)
Location: include/linux/crypto.h:591
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff815bfbeb)
Location: include/linux/crypto.h:591
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
```
```
In block/blk-crypto-fallback.c (ffffffff8160ed7b)
Location: include/linux/crypto.h:591
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio
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
In mm/zswap.c (ffffffff81385596)
Location: include/linux/crypto.h:600
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_writeback_entry
  - mm/zswap.c:zswap_writeback_entry
```
```
In fs/crypto/crypto.c (ffffffff8146ad28)
Location: include/linux/crypto.h:600
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/crypto.c:fscrypt_crypt_block
```
```
In fs/crypto/fname.c (ffffffff8146b3a1)
Location: include/linux/crypto.h:600
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_decrypt
  - fs/crypto/fname.c:fname_decrypt
  - fs/crypto/fname.c:fscrypt_fname_encrypt
  - fs/crypto/fname.c:fscrypt_fname_encrypt
```
```
In fs/crypto/keysetup_v1.c (ffffffff8146f5e1)
Location: include/linux/crypto.h:600
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/verity/hash_algs.c (ffffffff814733eb)
Location: include/linux/crypto.h:600
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In security/integrity/ima/ima_crypto.c (ffffffff81640f8b)
Location: include/linux/crypto.h:600
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/gcm.c (ffffffff8165f48b)
Location: include/linux/crypto.h:600
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (ffffffff816655ce)
Location: include/linux/crypto.h:600
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff8166a13d)
Location: include/linux/crypto.h:600
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
```
```
In block/blk-crypto-fallback.c (ffffffff816c35f6)
Location: include/linux/crypto.h:600
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio
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
In mm/zswap.c (ffffffff81403306)
Location: include/linux/crypto.h:600
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_writeback_entry
  - mm/zswap.c:zswap_writeback_entry
```
```
In fs/crypto/crypto.c (ffffffff814fbe50)
Location: include/linux/crypto.h:600
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/crypto.c:fscrypt_crypt_block
```
```
In fs/crypto/fname.c (ffffffff814fc822)
Location: include/linux/crypto.h:600
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_decrypt
  - fs/crypto/fname.c:fname_decrypt
  - fs/crypto/fname.c:fscrypt_fname_encrypt
  - fs/crypto/fname.c:fscrypt_fname_encrypt
```
```
In fs/crypto/keysetup_v1.c (ffffffff81500d61)
Location: include/linux/crypto.h:600
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/verity/hash_algs.c (ffffffff8150527b)
Location: include/linux/crypto.h:600
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In security/integrity/ima/ima_crypto.c (ffffffff816f8efb)
Location: include/linux/crypto.h:600
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/gcm.c (ffffffff817188bb)
Location: include/linux/crypto.h:600
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (ffffffff817203de)
Location: include/linux/crypto.h:600
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff81724708)
Location: include/linux/crypto.h:600
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
```
```
In block/blk-crypto-fallback.c (ffffffff81784a8b)
Location: include/linux/crypto.h:600
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio
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
In mm/zswap.c (ffffffff81436853)
Location: include/linux/crypto.h:392
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_writeback_entry
  - mm/zswap.c:zswap_writeback_entry
```
```
In fs/crypto/crypto.c (ffffffff81533180)
Location: include/linux/crypto.h:392
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/crypto.c:fscrypt_crypt_block
```
```
In fs/crypto/fname.c (ffffffff81533d92)
Location: include/linux/crypto.h:392
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_decrypt
  - fs/crypto/fname.c:fname_decrypt
  - fs/crypto/fname.c:fscrypt_fname_encrypt
  - fs/crypto/fname.c:fscrypt_fname_encrypt
```
```
In fs/crypto/keysetup_v1.c (ffffffff815383ee)
Location: include/linux/crypto.h:392
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff81645ef9)
Location: include/linux/crypto.h:392
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In security/keys/dh.c (ffffffff81692870)
Location: include/linux/crypto.h:392
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In security/integrity/ima/ima_crypto.c (ffffffff81733101)
Location: include/linux/crypto.h:392
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/akcipher.c (ffffffff8174750f)
Location: include/linux/crypto.h:392
Inline: True
Inline callers:
  - crypto/akcipher.c:crypto_akcipher_sync_post
```
```
In crypto/gcm.c (ffffffff8175422b)
Location: include/linux/crypto.h:392
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (ffffffff8175bcd3)
Location: include/linux/crypto.h:392
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
```
```
In block/blk-crypto-fallback.c (ffffffff817c4df0)
Location: include/linux/crypto.h:392
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio
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
In mm/zswap.c (ffffffff81470b8e)
Location: include/linux/crypto.h:392
Inline: True
Inline callers:
  - mm/zswap.c:zswap_store
  - mm/zswap.c:zswap_store
  - mm/zswap.c:__zswap_load
  - mm/zswap.c:__zswap_load
```
```
In fs/crypto/crypto.c (ffffffff8156807c)
Location: include/linux/crypto.h:392
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_crypt_data_unit
  - fs/crypto/crypto.c:fscrypt_crypt_data_unit
  - fs/crypto/crypto.c:fscrypt_crypt_data_unit
  - fs/crypto/crypto.c:fscrypt_crypt_data_unit
```
```
In fs/crypto/fname.c (ffffffff81568d22)
Location: include/linux/crypto.h:392
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_decrypt
  - fs/crypto/fname.c:fname_decrypt
  - fs/crypto/fname.c:fscrypt_fname_encrypt
  - fs/crypto/fname.c:fscrypt_fname_encrypt
```
```
In fs/crypto/keysetup_v1.c (ffffffff8156d53e)
Location: include/linux/crypto.h:392
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff8167f3b9)
Location: include/linux/crypto.h:392
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In security/keys/dh.c (ffffffff816cee40)
Location: include/linux/crypto.h:392
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In security/integrity/ima/ima_crypto.c (ffffffff81773afe)
Location: include/linux/crypto.h:392
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/akcipher.c (ffffffff8178937f)
Location: include/linux/crypto.h:392
Inline: True
Inline callers:
  - crypto/akcipher.c:crypto_akcipher_sync_post
```
```
In crypto/gcm.c (ffffffff81795b9b)
Location: include/linux/crypto.h:392
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (ffffffff8179dbd3)
Location: include/linux/crypto.h:392
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
```
```
In block/blk-crypto-fallback.c (ffffffff81809ae0)
Location: include/linux/crypto.h:392
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio
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
In fs/crypto/crypto.c (ffff80001040b0d0)
Location: include/linux/crypto.h:680
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/crypto.c:fscrypt_crypt_block
```
```
In fs/crypto/fname.c (ffff80001040bc7c)
Location: include/linux/crypto.h:680
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_encrypt
  - fs/crypto/fname.c:fname_encrypt
```
```
In fs/crypto/keysetup_v1.c (ffff80001040f6c8)
Location: include/linux/crypto.h:680
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/verity/hash_algs.c (ffff800010412204)
Location: include/linux/crypto.h:680
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In security/integrity/ima/ima_crypto.c (ffff8000105b0314)
Location: include/linux/crypto.h:680
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/gcm.c (ffff8000105cc744)
Location: include/linux/crypto.h:680
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (ffff8000105d1e3c)
Location: include/linux/crypto.h:680
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
```
```
In crypto/asymmetric_keys/public_key.c (ffff8000105d5ba4)
Location: include/linux/crypto.h:680
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
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
In fs/crypto/crypto.c (c05d8288)
Location: include/linux/crypto.h:680
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/crypto.c:fscrypt_crypt_block
```
```
In fs/crypto/fname.c (c05d8a70)
Location: include/linux/crypto.h:680
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_decrypt
  - fs/crypto/fname.c:fname_decrypt
  - fs/crypto/fname.c:fname_encrypt
  - fs/crypto/fname.c:fname_encrypt
```
```
In fs/crypto/keysetup_v1.c (c05dc3b8)
Location: include/linux/crypto.h:680
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
```
```
In fs/verity/hash_algs.c (c05de888)
Location: include/linux/crypto.h:680
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In security/integrity/ima/ima_crypto.c (c075fa48)
Location: include/linux/crypto.h:680
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/gcm.c (c077a628)
Location: include/linux/crypto.h:680
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (c077f6e4)
Location: include/linux/crypto.h:680
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
```
```
In crypto/asymmetric_keys/public_key.c (c07836b4)
Location: include/linux/crypto.h:680
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
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
In fs/crypto/crypto.c (c000000000517ba4)
Location: include/linux/crypto.h:680
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/crypto.c:fscrypt_crypt_block
```
```
In fs/crypto/fname.c (c0000000005189b8)
Location: include/linux/crypto.h:680
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_encrypt
  - fs/crypto/fname.c:fname_encrypt
```
```
In fs/crypto/keysetup_v1.c (c00000000051d188)
Location: include/linux/crypto.h:680
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/verity/hash_algs.c (c00000000051ff78)
Location: include/linux/crypto.h:680
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In security/integrity/ima/ima_crypto.c (c00000000072fde8)
Location: include/linux/crypto.h:680
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/gcm.c (c000000000757bc8)
Location: include/linux/crypto.h:680
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (c00000000075ee0c)
Location: include/linux/crypto.h:680
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
```
```
In crypto/asymmetric_keys/public_key.c (c0000000007643b4)
Location: include/linux/crypto.h:680
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
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
In fs/crypto/crypto.c (ffffffe0002b4dea)
Location: include/linux/crypto.h:680
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/crypto.c:fscrypt_crypt_block
```
```
In fs/crypto/fname.c (ffffffe0002b571a)
Location: include/linux/crypto.h:680
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_encrypt
  - fs/crypto/fname.c:fname_encrypt
```
```
In fs/crypto/keysetup_v1.c (ffffffe0002b8580)
Location: include/linux/crypto.h:680
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
```
```
In fs/verity/hash_algs.c (ffffffe0002ba26c)
Location: include/linux/crypto.h:680
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In security/integrity/ima/ima_crypto.c (ffffffe0003f7faa)
Location: include/linux/crypto.h:680
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/gcm.c (ffffffe0004106a6)
Location: include/linux/crypto.h:680
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (ffffffe000415536)
Location: include/linux/crypto.h:680
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
```
```
In crypto/asymmetric_keys/public_key.c (ffffffe000419d5c)
Location: include/linux/crypto.h:680
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
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
In fs/crypto/crypto.c (ffffffff81342efb)
Location: include/linux/crypto.h:680
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/crypto.c:fscrypt_crypt_block
```
```
In fs/crypto/fname.c (ffffffff8134386e)
Location: include/linux/crypto.h:680
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_encrypt
  - fs/crypto/fname.c:fname_encrypt
```
```
In fs/crypto/keysetup_v1.c (ffffffff81346a9d)
Location: include/linux/crypto.h:680
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/verity/hash_algs.c (ffffffff81348b25)
Location: include/linux/crypto.h:680
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In security/integrity/ima/ima_crypto.c (ffffffff814b0535)
Location: include/linux/crypto.h:680
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/gcm.c (ffffffff814c8863)
Location: include/linux/crypto.h:680
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (ffffffff814ce560)
Location: include/linux/crypto.h:680
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff814d2384)
Location: include/linux/crypto.h:680
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
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
In fs/crypto/crypto.c (ffffffff81333bdb)
Location: include/linux/crypto.h:680
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/crypto.c:fscrypt_crypt_block
```
```
In fs/crypto/fname.c (ffffffff8133454e)
Location: include/linux/crypto.h:680
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_encrypt
  - fs/crypto/fname.c:fname_encrypt
```
```
In fs/crypto/keysetup_v1.c (ffffffff8133777d)
Location: include/linux/crypto.h:680
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/verity/hash_algs.c (ffffffff81339805)
Location: include/linux/crypto.h:680
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In security/integrity/ima/ima_crypto.c (ffffffff814a0f55)
Location: include/linux/crypto.h:680
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/gcm.c (ffffffff814b9283)
Location: include/linux/crypto.h:680
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (ffffffff814bef80)
Location: include/linux/crypto.h:680
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff814c2da4)
Location: include/linux/crypto.h:680
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
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
In fs/crypto/crypto.c (ffffffff813409cb)
Location: include/linux/crypto.h:680
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/crypto.c:fscrypt_crypt_block
```
```
In fs/crypto/fname.c (ffffffff8134133e)
Location: include/linux/crypto.h:680
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_encrypt
  - fs/crypto/fname.c:fname_encrypt
```
```
In fs/crypto/keysetup_v1.c (ffffffff8134456d)
Location: include/linux/crypto.h:680
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/verity/hash_algs.c (ffffffff813465f5)
Location: include/linux/crypto.h:680
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In security/integrity/ima/ima_crypto.c (ffffffff814ac5c5)
Location: include/linux/crypto.h:680
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/gcm.c (ffffffff814c48f3)
Location: include/linux/crypto.h:680
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (ffffffff814ca5f0)
Location: include/linux/crypto.h:680
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff814ce414)
Location: include/linux/crypto.h:680
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
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
In fs/crypto/crypto.c (ffffffff81353ccb)
Location: include/linux/crypto.h:680
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/crypto.c:fscrypt_crypt_block
```
```
In fs/crypto/fname.c (ffffffff8135463e)
Location: include/linux/crypto.h:680
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_encrypt
  - fs/crypto/fname.c:fname_encrypt
```
```
In fs/crypto/keysetup_v1.c (ffffffff8135784d)
Location: include/linux/crypto.h:680
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/verity/hash_algs.c (ffffffff813598d5)
Location: include/linux/crypto.h:680
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In security/integrity/ima/ima_crypto.c (ffffffff814c5015)
Location: include/linux/crypto.h:680
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/gcm.c (ffffffff814dd3c3)
Location: include/linux/crypto.h:680
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (ffffffff814e30c0)
Location: include/linux/crypto.h:680
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff814e6ee4)
Location: include/linux/crypto.h:680
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
```
</details>
</li>
</ul>

## Differences
