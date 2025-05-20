# Function: <code>crypto_skcipher_encrypt</code>

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
In fs/crypto/crypto.c (ffffffff81288a94)
Location: include/crypto/skcipher.h:407
Inline: True
```
```
In fs/crypto/fname.c (ffffffff81289336)
Location: include/crypto/skcipher.h:407
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_encrypt
```
```
In fs/crypto/keyinfo.c (ffffffff8128a222)
Location: include/crypto/skcipher.h:407
Inline: True
Inline callers:
  - fs/crypto/keyinfo.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff81339606)
Location: include/crypto/skcipher.h:407
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/keystore.c (ffffffff8133c749)
Location: include/crypto/skcipher.h:407
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/big_key.c (ffffffff8136b877)
Location: include/crypto/skcipher.h:407
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_crypt
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff8136e666)
Location: include/crypto/skcipher.h:407
Inline: True
```
```
In crypto/seqiv.c (ffffffff813de9a2)
Location: include/crypto/skcipher.h:407
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/cts.c (ffffffff813e7cdc)
Location: include/crypto/skcipher.h:407
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:cts_cbc_encrypt
```
```
In crypto/ctr.c (ffffffff813e88f5)
Location: include/crypto/skcipher.h:407
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_crypt
```
```
In crypto/drbg.c (ffffffff813eb8e9)
Location: include/crypto/skcipher.h:407
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
In fs/crypto/crypto.c (ffffffff8129d6c1)
Location: include/crypto/skcipher.h:407
Inline: True
```
```
In fs/crypto/fname.c (ffffffff8129e05e)
Location: include/crypto/skcipher.h:407
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_encrypt
```
```
In fs/crypto/keyinfo.c (ffffffff8129ef62)
Location: include/crypto/skcipher.h:407
Inline: True
Inline callers:
  - fs/crypto/keyinfo.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff8134f3a6)
Location: include/crypto/skcipher.h:407
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/keystore.c (ffffffff813524d9)
Location: include/crypto/skcipher.h:407
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/big_key.c (ffffffff81382097)
Location: include/crypto/skcipher.h:407
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_crypt
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff81385503)
Location: include/crypto/skcipher.h:407
Inline: True
```
```
In crypto/seqiv.c (ffffffff813f6f42)
Location: include/crypto/skcipher.h:407
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/cts.c (ffffffff81400b0c)
Location: include/crypto/skcipher.h:407
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:cts_cbc_encrypt
```
```
In crypto/xts.c (ffffffff81401d2c)
Location: include/crypto/skcipher.h:407
Inline: True
Inline callers:
  - crypto/xts.c:do_encrypt
```
```
In crypto/ctr.c (ffffffff81401f05)
Location: include/crypto/skcipher.h:407
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_crypt
```
```
In crypto/drbg.c (ffffffff81405061)
Location: include/crypto/skcipher.h:407
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
In fs/crypto/crypto.c (ffffffff812ac433)
Location: include/crypto/skcipher.h:441
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_do_page_crypto
```
```
In fs/crypto/fname.c (ffffffff812acab4)
Location: include/crypto/skcipher.h:441
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_encrypt
```
```
In fs/crypto/keyinfo.c (ffffffff812ad9c3)
Location: include/crypto/skcipher.h:441
Inline: True
Inline callers:
  - fs/crypto/keyinfo.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff81363e61)
Location: include/crypto/skcipher.h:441
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/keystore.c (ffffffff8136726d)
Location: include/crypto/skcipher.h:441
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/big_key.c (ffffffff81396730)
Location: include/crypto/skcipher.h:441
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_crypt
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff81399bf4)
Location: include/crypto/skcipher.h:441
Inline: True
```
```
In crypto/seqiv.c (ffffffff81403345)
Location: include/crypto/skcipher.h:441
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/cts.c (ffffffff8140dabe)
Location: include/crypto/skcipher.h:441
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:cts_cbc_encrypt
```
```
In crypto/xts.c (ffffffff8140f0d4)
Location: include/crypto/skcipher.h:441
Inline: True
Inline callers:
  - crypto/xts.c:do_encrypt
```
```
In crypto/ctr.c (ffffffff8140f355)
Location: include/crypto/skcipher.h:441
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_crypt
```
```
In crypto/drbg.c (ffffffff8141281f)
Location: include/crypto/skcipher.h:441
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
In fs/crypto/crypto.c (ffffffff812cfc41)
Location: include/crypto/skcipher.h:441
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_do_page_crypto
```
```
In fs/crypto/fname.c (ffffffff812d027e)
Location: include/crypto/skcipher.h:441
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_encrypt
```
```
In fs/crypto/keyinfo.c (ffffffff812d0e89)
Location: include/crypto/skcipher.h:441
Inline: True
Inline callers:
  - fs/crypto/keyinfo.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff81388bec)
Location: include/crypto/skcipher.h:441
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/keystore.c (ffffffff8138bef0)
Location: include/crypto/skcipher.h:441
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff813bf3c4)
Location: include/crypto/skcipher.h:441
Inline: True
```
```
In crypto/seqiv.c (ffffffff8142ba35)
Location: include/crypto/skcipher.h:441
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/cts.c (ffffffff8143655e)
Location: include/crypto/skcipher.h:441
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:cts_cbc_encrypt
```
```
In crypto/xts.c (ffffffff81437bb8)
Location: include/crypto/skcipher.h:441
Inline: True
Inline callers:
  - crypto/xts.c:do_encrypt
```
```
In crypto/ctr.c (ffffffff81437f25)
Location: include/crypto/skcipher.h:441
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_crypt
```
```
In crypto/gcm.c (ffffffff8143903c)
Location: include/crypto/skcipher.h:441
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (ffffffff8143cfad)
Location: include/crypto/skcipher.h:441
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
In fs/crypto/crypto.c (ffffffff812fa582)
Location: include/crypto/skcipher.h:436
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_do_page_crypto
```
```
In fs/crypto/fname.c (ffffffff812fae9d)
Location: include/crypto/skcipher.h:436
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_encrypt
```
```
In fs/crypto/keyinfo.c (ffffffff812fba28)
Location: include/crypto/skcipher.h:436
Inline: True
Inline callers:
  - fs/crypto/keyinfo.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff813b7a8f)
Location: include/crypto/skcipher.h:436
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/keystore.c (ffffffff813bab65)
Location: include/crypto/skcipher.h:436
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff813eff41)
Location: include/crypto/skcipher.h:436
Inline: True
```
```
In crypto/seqiv.c (ffffffff8145e740)
Location: include/crypto/skcipher.h:436
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/cts.c (ffffffff814690ae)
Location: include/crypto/skcipher.h:436
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:cts_cbc_encrypt
```
```
In crypto/xts.c (ffffffff8146a4fc)
Location: include/crypto/skcipher.h:436
Inline: True
Inline callers:
  - crypto/xts.c:do_encrypt
```
```
In crypto/ctr.c (ffffffff8146a87d)
Location: include/crypto/skcipher.h:436
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_crypt
```
```
In crypto/gcm.c (ffffffff8146b349)
Location: include/crypto/skcipher.h:436
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (ffffffff8146fd64)
Location: include/crypto/skcipher.h:436
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
In fs/crypto/crypto.c (ffffffff8130f862)
Location: include/crypto/skcipher.h:487
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_do_page_crypto
```
```
In fs/crypto/fname.c (ffffffff81310254)
Location: include/crypto/skcipher.h:487
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_encrypt
```
```
In fs/crypto/keyinfo.c (ffffffff81310f85)
Location: include/crypto/skcipher.h:487
Inline: True
Inline callers:
  - fs/crypto/keyinfo.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff813d0feb)
Location: include/crypto/skcipher.h:487
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/keystore.c (ffffffff813d412c)
Location: include/crypto/skcipher.h:487
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff8140b4a3)
Location: include/crypto/skcipher.h:487
Inline: True
```
```
In crypto/seqiv.c (ffffffff8147c029)
Location: include/crypto/skcipher.h:487
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/cts.c (ffffffff814870ad)
Location: include/crypto/skcipher.h:487
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:cts_cbc_encrypt
```
```
In crypto/xts.c (ffffffff81487dfe)
Location: include/crypto/skcipher.h:487
Inline: True
```
```
In crypto/ctr.c (ffffffff814880ee)
Location: include/crypto/skcipher.h:487
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_crypt
```
```
In crypto/gcm.c (ffffffff814895c7)
Location: include/crypto/skcipher.h:487
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_copy_src_to_dst
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (ffffffff814900f2)
Location: include/crypto/skcipher.h:487
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int crypto_skcipher_encrypt(struct skcipher_request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff814a8b00)
Location: crypto/skcipher.c:840
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/fname.c:fname_encrypt
  - fs/crypto/keyinfo.c:derive_key_aes
  - fs/ecryptfs/crypto.c:crypt_scatterlist
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - crypto/seqiv.c:seqiv_aead_encrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:cts_cbc_encrypt
  - crypto/ctr.c:crypto_rfc3686_crypt
  - crypto/gcm.c:crypto_rfc4543_copy_src_to_dst
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:crypto_gcm_setkey
  - crypto/drbg.c:drbg_kcapi_sym_ctr
```
**Symbols:**

```
ffffffff814a8b00-ffffffff814a8b5c: crypto_skcipher_encrypt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int crypto_skcipher_encrypt(struct skcipher_request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff814c3760)
Location: crypto/skcipher.c:844
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/fname.c:fname_encrypt
  - fs/crypto/keysetup_v1.c:derive_key_aes
  - fs/ecryptfs/crypto.c:crypt_scatterlist
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - crypto/seqiv.c:seqiv_aead_encrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:cts_cbc_encrypt
  - crypto/ctr.c:crypto_rfc3686_crypt
  - crypto/gcm.c:crypto_rfc4543_copy_src_to_dst
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:crypto_gcm_setkey
  - crypto/drbg.c:drbg_kcapi_sym_ctr
```
**Symbols:**

```
ffffffff814c3760-ffffffff814c37bc: crypto_skcipher_encrypt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int crypto_skcipher_encrypt(struct skcipher_request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff81522960)
Location: crypto/skcipher.c:624
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/fname.c:fscrypt_fname_encrypt
  - fs/crypto/keysetup_v1.c:derive_key_aes
  - fs/ecryptfs/crypto.c:crypt_scatterlist
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - crypto/seqiv.c:seqiv_aead_encrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:cts_cbc_encrypt
  - crypto/xts.c:encrypt
  - crypto/ctr.c:crypto_rfc3686_crypt
  - crypto/gcm.c:crypto_rfc4543_copy_src_to_dst
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:crypto_gcm_setkey
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio
```
**Symbols:**

```
ffffffff81522960-ffffffff815229c0: crypto_skcipher_encrypt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int crypto_skcipher_encrypt(struct skcipher_request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff8153f820)
Location: crypto/skcipher.c:624
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/fname.c:fscrypt_fname_encrypt
  - fs/crypto/keysetup_v1.c:derive_key_aes
  - fs/ecryptfs/crypto.c:crypt_scatterlist
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - crypto/seqiv.c:seqiv_aead_encrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:cts_cbc_encrypt
  - crypto/xts.c:xts_encrypt
  - crypto/ctr.c:crypto_rfc3686_crypt
  - crypto/gcm.c:crypto_rfc4543_copy_src_to_dst
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:crypto_gcm_setkey
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio
```
**Symbols:**

```
ffffffff8153f820-ffffffff8153f880: crypto_skcipher_encrypt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int crypto_skcipher_encrypt(struct skcipher_request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff81547db0)
Location: crypto/skcipher.c:619
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/fname.c:fscrypt_fname_encrypt
  - fs/crypto/keysetup_v1.c:derive_key_aes
  - fs/ecryptfs/crypto.c:crypt_scatterlist
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - crypto/seqiv.c:seqiv_aead_encrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:cts_cbc_encrypt
  - crypto/xts.c:xts_encrypt
  - crypto/ctr.c:crypto_rfc3686_crypt
  - crypto/gcm.c:crypto_rfc4543_copy_src_to_dst
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:crypto_gcm_setkey
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio
```
**Symbols:**

```
ffffffff81547db0-ffffffff81547e10: crypto_skcipher_encrypt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int crypto_skcipher_encrypt(struct skcipher_request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff815a8590)
Location: crypto/skcipher.c:619
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/fname.c:fscrypt_fname_encrypt
  - fs/crypto/keysetup_v1.c:derive_key_aes
  - fs/ecryptfs/crypto.c:crypt_scatterlist
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - crypto/seqiv.c:seqiv_aead_encrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:cts_cbc_encrypt
  - crypto/xts.c:xts_encrypt
  - crypto/ctr.c:crypto_rfc3686_crypt
  - crypto/gcm.c:crypto_rfc4543_copy_src_to_dst
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:crypto_gcm_setkey
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio
```
**Symbols:**

```
ffffffff815a8590-ffffffff815a85f0: crypto_skcipher_encrypt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int crypto_skcipher_encrypt(struct skcipher_request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff8164f910)
Location: crypto/skcipher.c:619
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/fname.c:fscrypt_fname_encrypt
  - fs/crypto/keysetup_v1.c:derive_key_aes
  - fs/ecryptfs/crypto.c:crypt_scatterlist
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - crypto/seqiv.c:seqiv_aead_encrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:cts_cbc_encrypt
  - crypto/xts.c:xts_encrypt
  - crypto/ctr.c:crypto_rfc3686_crypt
  - crypto/gcm.c:crypto_rfc4543_copy_src_to_dst
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:crypto_gcm_setkey
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio
```
**Symbols:**

```
ffffffff8164f910-ffffffff8164f977: crypto_skcipher_encrypt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int crypto_skcipher_encrypt(struct skcipher_request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff81708d40)
Location: crypto/skcipher.c:619
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/fname.c:fscrypt_fname_encrypt
  - fs/crypto/keysetup_v1.c:derive_key_aes
  - fs/ecryptfs/crypto.c:crypt_scatterlist
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - crypto/seqiv.c:seqiv_aead_encrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:cts_cbc_encrypt
  - crypto/xts.c:xts_encrypt
  - crypto/ctr.c:crypto_rfc3686_crypt
  - crypto/gcm.c:crypto_rfc4543_copy_src_to_dst
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:crypto_gcm_setkey
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio
```
**Symbols:**

```
ffffffff81708d40-ffffffff81708da7: crypto_skcipher_encrypt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int crypto_skcipher_encrypt(struct skcipher_request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff81742f70)
Location: crypto/skcipher.c:637
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/fname.c:fscrypt_fname_encrypt
  - fs/crypto/keysetup_v1.c:derive_key_aes
  - fs/ecryptfs/crypto.c:crypt_scatterlist
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - crypto/seqiv.c:seqiv_aead_encrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:cts_cbc_encrypt
  - crypto/xts.c:xts_encrypt
  - crypto/ctr.c:crypto_rfc3686_crypt
  - crypto/gcm.c:crypto_rfc4543_copy_src_to_dst
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:crypto_gcm_setkey
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio
```
**Symbols:**

```
ffffffff81742f70-ffffffff81742fd0: crypto_skcipher_encrypt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int crypto_skcipher_encrypt(struct skcipher_request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff817852a0)
Location: crypto/skcipher.c:653
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_crypt_data_unit
  - fs/crypto/fname.c:fscrypt_fname_encrypt
  - fs/crypto/keysetup_v1.c:derive_key_aes
  - fs/ecryptfs/crypto.c:crypt_scatterlist
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - crypto/seqiv.c:seqiv_aead_encrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:cts_cbc_encrypt
  - crypto/xts.c:xts_encrypt
  - crypto/ctr.c:crypto_rfc3686_crypt
  - crypto/gcm.c:crypto_rfc4543_copy_src_to_dst
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:crypto_gcm_setkey
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio
```
**Symbols:**

```
ffffffff817852a0-ffffffff81785314: crypto_skcipher_encrypt (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int crypto_skcipher_encrypt(struct skcipher_request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffff8000105bdfe0)
Location: crypto/skcipher.c:844
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/fname.c:fname_encrypt
  - fs/crypto/keysetup_v1.c:derive_key_aes
  - fs/ecryptfs/crypto.c:crypt_scatterlist
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - crypto/seqiv.c:seqiv_aead_encrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:cts_cbc_encrypt
  - crypto/ctr.c:crypto_rfc3686_crypt
  - crypto/gcm.c:crypto_rfc4543_copy_src_to_dst
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:crypto_gcm_setkey
  - crypto/drbg.c:drbg_kcapi_sym_ctr
```
**Symbols:**

```
ffff8000105bdfe0-ffff8000105be054: crypto_skcipher_encrypt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int crypto_skcipher_encrypt(struct skcipher_request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (c076bde4)
Location: crypto/skcipher.c:844
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/fname.c:fname_encrypt
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
  - fs/ecryptfs/crypto.c:crypt_extent
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - crypto/seqiv.c:seqiv_aead_encrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:cts_cbc_encrypt
  - crypto/ctr.c:crypto_rfc3686_crypt
  - crypto/gcm.c:crypto_rfc4543_copy_src_to_dst
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:crypto_gcm_setkey
  - crypto/drbg.c:drbg_kcapi_sym_ctr
```
**Symbols:**

```
c076bde4-c076be4c: crypto_skcipher_encrypt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int crypto_skcipher_encrypt(struct skcipher_request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (c000000000745600)
Location: crypto/skcipher.c:844
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/fname.c:fname_encrypt
  - fs/crypto/keysetup_v1.c:derive_key_aes
  - fs/ecryptfs/crypto.c:crypt_scatterlist
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - crypto/seqiv.c:seqiv_aead_encrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:cts_cbc_encrypt
  - crypto/ctr.c:crypto_rfc3686_crypt
  - crypto/gcm.c:crypto_rfc4543_copy_src_to_dst
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:crypto_gcm_setkey
  - crypto/drbg.c:drbg_kcapi_sym_ctr
```
**Symbols:**

```
c000000000745600-c0000000007456b8: crypto_skcipher_encrypt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int crypto_skcipher_encrypt(struct skcipher_request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffe00040349a)
Location: crypto/skcipher.c:844
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/fname.c:fname_encrypt
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
  - fs/ecryptfs/crypto.c:crypt_scatterlist
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - crypto/seqiv.c:seqiv_aead_encrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:cts_cbc_encrypt
  - crypto/ctr.c:crypto_rfc3686_crypt
  - crypto/gcm.c:crypto_rfc4543_copy_src_to_dst
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:crypto_gcm_setkey
  - crypto/drbg.c:drbg_kcapi_sym_ctr
```
**Symbols:**

```
ffffffe00040349a-ffffffe000403504: crypto_skcipher_encrypt (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int crypto_skcipher_encrypt(struct skcipher_request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff814bbd40)
Location: crypto/skcipher.c:844
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/fname.c:fname_encrypt
  - fs/crypto/keysetup_v1.c:derive_key_aes
  - fs/ecryptfs/crypto.c:crypt_scatterlist
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - crypto/seqiv.c:seqiv_aead_encrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:cts_cbc_encrypt
  - crypto/ctr.c:crypto_rfc3686_crypt
  - crypto/gcm.c:crypto_rfc4543_copy_src_to_dst
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:crypto_gcm_setkey
  - crypto/drbg.c:drbg_kcapi_sym_ctr
```
**Symbols:**

```
ffffffff814bbd40-ffffffff814bbd9c: crypto_skcipher_encrypt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int crypto_skcipher_encrypt(struct skcipher_request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff814ac760)
Location: crypto/skcipher.c:844
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/fname.c:fname_encrypt
  - fs/crypto/keysetup_v1.c:derive_key_aes
  - fs/ecryptfs/crypto.c:crypt_scatterlist
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - crypto/seqiv.c:seqiv_aead_encrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:cts_cbc_encrypt
  - crypto/ctr.c:crypto_rfc3686_crypt
  - crypto/gcm.c:crypto_rfc4543_copy_src_to_dst
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:crypto_gcm_setkey
  - crypto/drbg.c:drbg_kcapi_sym_ctr
```
**Symbols:**

```
ffffffff814ac760-ffffffff814ac7bc: crypto_skcipher_encrypt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int crypto_skcipher_encrypt(struct skcipher_request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff814b7dd0)
Location: crypto/skcipher.c:844
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/fname.c:fname_encrypt
  - fs/crypto/keysetup_v1.c:derive_key_aes
  - fs/ecryptfs/crypto.c:crypt_scatterlist
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - crypto/seqiv.c:seqiv_aead_encrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:cts_cbc_encrypt
  - crypto/ctr.c:crypto_rfc3686_crypt
  - crypto/gcm.c:crypto_rfc4543_copy_src_to_dst
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:crypto_gcm_setkey
  - crypto/drbg.c:drbg_kcapi_sym_ctr
```
**Symbols:**

```
ffffffff814b7dd0-ffffffff814b7e2c: crypto_skcipher_encrypt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int crypto_skcipher_encrypt(struct skcipher_request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff814d08b0)
Location: crypto/skcipher.c:844
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/fname.c:fname_encrypt
  - fs/crypto/keysetup_v1.c:derive_key_aes
  - fs/ecryptfs/crypto.c:crypt_scatterlist
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - crypto/seqiv.c:seqiv_aead_encrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:cts_cbc_encrypt
  - crypto/ctr.c:crypto_rfc3686_crypt
  - crypto/gcm.c:crypto_rfc4543_copy_src_to_dst
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:crypto_gcm_setkey
  - crypto/drbg.c:drbg_kcapi_sym_ctr
```
**Symbols:**

```
ffffffff814d08b0-ffffffff814d090c: crypto_skcipher_encrypt (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
