# Function: <code>crypto_skcipher_set_flags</code>

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
In crypto/skcipher.c (ffffffff813a1a49)
Location: include/crypto/skcipher.h:276
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_blkcipher
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
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
In fs/crypto/keyinfo.c (ffffffff8128a189)
Location: include/crypto/skcipher.h:336
Inline: True
Inline callers:
  - fs/crypto/keyinfo.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff8133b003)
Location: include/crypto/skcipher.h:336
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_ctx
```
```
In crypto/skcipher.c (ffffffff813de023)
Location: include/crypto/skcipher.h:336
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
  - crypto/skcipher.c:skcipher_setkey_blkcipher
```
```
In crypto/cts.c (ffffffff813e775a)
Location: include/crypto/skcipher.h:336
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_setkey
  - crypto/cts.c:crypto_cts_setkey
```
```
In crypto/ctr.c (ffffffff813e8854)
Location: include/crypto/skcipher.h:336
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_setkey
  - crypto/ctr.c:crypto_rfc3686_setkey
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
In fs/crypto/keyinfo.c (ffffffff8129eec9)
Location: include/crypto/skcipher.h:336
Inline: True
Inline callers:
  - fs/crypto/keyinfo.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff81350d97)
Location: include/crypto/skcipher.h:336
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_ctx
```
```
In crypto/skcipher.c (ffffffff813f58f3)
Location: include/crypto/skcipher.h:336
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
  - crypto/skcipher.c:skcipher_setkey_blkcipher
```
```
In crypto/cbc.c (ffffffff813fff48)
Location: include/crypto/skcipher.h:336
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_setkey
```
```
In crypto/cts.c (ffffffff8140058a)
Location: include/crypto/skcipher.h:336
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_setkey
  - crypto/cts.c:crypto_cts_setkey
```
```
In crypto/xts.c (ffffffff81401358)
Location: include/crypto/skcipher.h:336
Inline: True
```
```
In crypto/ctr.c (ffffffff81401e64)
Location: include/crypto/skcipher.h:336
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_setkey
  - crypto/ctr.c:crypto_rfc3686_setkey
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
In fs/crypto/keyinfo.c (ffffffff812ad92c)
Location: include/crypto/skcipher.h:370
Inline: True
Inline callers:
  - fs/crypto/keyinfo.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff813658b7)
Location: include/crypto/skcipher.h:370
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_ctx
```
```
In crypto/skcipher.c (ffffffff814020a3)
Location: include/crypto/skcipher.h:370
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
  - crypto/skcipher.c:skcipher_setkey_blkcipher
```
```
In crypto/cbc.c (ffffffff8140d258)
Location: include/crypto/skcipher.h:370
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_setkey
```
```
In crypto/cts.c (ffffffff8140d88a)
Location: include/crypto/skcipher.h:370
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_setkey
  - crypto/cts.c:crypto_cts_setkey
```
```
In crypto/xts.c (ffffffff8140e64f)
Location: include/crypto/skcipher.h:370
Inline: True
Inline callers:
  - crypto/xts.c:setkey
  - crypto/xts.c:setkey
  - crypto/xts.c:setkey
  - crypto/xts.c:setkey
  - crypto/xts.c:setkey
```
```
In crypto/ctr.c (ffffffff8140f2af)
Location: include/crypto/skcipher.h:370
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_setkey
  - crypto/ctr.c:crypto_rfc3686_setkey
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
In fs/crypto/keyinfo.c (ffffffff812d0ded)
Location: include/crypto/skcipher.h:370
Inline: True
Inline callers:
  - fs/crypto/keyinfo.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff8138a577)
Location: include/crypto/skcipher.h:370
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_ctx
```
```
In crypto/skcipher.c (ffffffff8142a715)
Location: include/crypto/skcipher.h:370
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
  - crypto/skcipher.c:skcipher_setkey_blkcipher
```
```
In crypto/cbc.c (ffffffff81435cce)
Location: include/crypto/skcipher.h:370
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_setkey
```
```
In crypto/cts.c (ffffffff8143631a)
Location: include/crypto/skcipher.h:370
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_setkey
  - crypto/cts.c:crypto_cts_setkey
```
```
In crypto/xts.c (ffffffff81437119)
Location: include/crypto/skcipher.h:370
Inline: True
Inline callers:
  - crypto/xts.c:setkey
  - crypto/xts.c:setkey
  - crypto/xts.c:setkey
  - crypto/xts.c:setkey
  - crypto/xts.c:setkey
```
```
In crypto/ctr.c (ffffffff81437e7f)
Location: include/crypto/skcipher.h:370
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_setkey
  - crypto/ctr.c:crypto_rfc3686_setkey
```
```
In crypto/gcm.c (ffffffff8143a3a8)
Location: include/crypto/skcipher.h:370
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_setkey
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
In fs/crypto/keyinfo.c (ffffffff812fb979)
Location: include/crypto/skcipher.h:370
Inline: True
Inline callers:
  - fs/crypto/keyinfo.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff813b92bd)
Location: include/crypto/skcipher.h:370
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_ctx
```
```
In crypto/skcipher.c (ffffffff8145d4e9)
Location: include/crypto/skcipher.h:370
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/skcipher.c:skcipher_setkey
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
  - crypto/skcipher.c:skcipher_setkey_blkcipher
```
```
In crypto/cbc.c (ffffffff81468855)
Location: include/crypto/skcipher.h:370
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_setkey
```
```
In crypto/cts.c (ffffffff81468e5f)
Location: include/crypto/skcipher.h:370
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_setkey
  - crypto/cts.c:crypto_cts_setkey
```
```
In crypto/xts.c (ffffffff81469b47)
Location: include/crypto/skcipher.h:370
Inline: True
```
```
In crypto/ctr.c (ffffffff8146a7d4)
Location: include/crypto/skcipher.h:370
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_setkey
  - crypto/ctr.c:crypto_rfc3686_setkey
```
```
In crypto/gcm.c (ffffffff8146cd51)
Location: include/crypto/skcipher.h:370
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_setkey
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
In fs/crypto/keyinfo.c (ffffffff81310ecc)
Location: include/crypto/skcipher.h:389
Inline: True
Inline callers:
  - fs/crypto/keyinfo.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff813d282d)
Location: include/crypto/skcipher.h:389
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_ctx
```
```
In crypto/skcipher.c (ffffffff8147ae1e)
Location: include/crypto/skcipher.h:389
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/skcipher.c:skcipher_setkey
  - crypto/skcipher.c:skcipher_setkey
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
  - crypto/skcipher.c:skcipher_setkey_blkcipher
  - crypto/skcipher.c:skcipher_setkey_blkcipher
```
```
In crypto/cbc.c (ffffffff814864c5)
Location: include/crypto/skcipher.h:389
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_setkey
```
```
In crypto/cts.c (ffffffff81486adf)
Location: include/crypto/skcipher.h:389
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_setkey
  - crypto/cts.c:crypto_cts_setkey
```
```
In crypto/xts.c (ffffffff81487a17)
Location: include/crypto/skcipher.h:389
Inline: True
```
```
In crypto/ctr.c (ffffffff81488034)
Location: include/crypto/skcipher.h:389
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_setkey
  - crypto/ctr.c:crypto_rfc3686_setkey
```
```
In crypto/gcm.c (ffffffff81489321)
Location: include/crypto/skcipher.h:389
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_setkey
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
In fs/crypto/keyinfo.c (ffffffff813385fd)
Location: include/crypto/skcipher.h:324
Inline: True
Inline callers:
  - fs/crypto/keyinfo.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff813fd2c9)
Location: include/crypto/skcipher.h:324
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_ctx
```
```
In crypto/skcipher.c (ffffffff814a88ac)
Location: include/crypto/skcipher.h:324
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_simple
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/skcipher.c:skcipher_setkey
  - crypto/skcipher.c:skcipher_setkey
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
  - crypto/skcipher.c:skcipher_setkey_blkcipher
  - crypto/skcipher.c:skcipher_setkey_blkcipher
```
```
In crypto/cts.c (ffffffff814b4953)
Location: include/crypto/skcipher.h:324
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_setkey
  - crypto/cts.c:crypto_cts_setkey
```
```
In crypto/xts.c (ffffffff814b572b)
Location: include/crypto/skcipher.h:324
Inline: True
```
```
In crypto/ctr.c (ffffffff814b5ac4)
Location: include/crypto/skcipher.h:324
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_setkey
  - crypto/ctr.c:crypto_rfc3686_setkey
```
```
In crypto/gcm.c (ffffffff814b6f6d)
Location: include/crypto/skcipher.h:324
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_setkey
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
In fs/crypto/keysetup.c (ffffffff8134d74f)
Location: include/crypto/skcipher.h:354
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_allocate_skcipher
```
```
In fs/crypto/keysetup_v1.c (ffffffff8134e40c)
Location: include/crypto/skcipher.h:354
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff814171aa)
Location: include/crypto/skcipher.h:354
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_ctx
```
```
In crypto/skcipher.c (ffffffff814c350c)
Location: include/crypto/skcipher.h:354
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_simple
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/skcipher.c:skcipher_setkey
  - crypto/skcipher.c:skcipher_setkey
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
  - crypto/skcipher.c:skcipher_setkey_blkcipher
  - crypto/skcipher.c:skcipher_setkey_blkcipher
```
```
In crypto/cts.c (ffffffff814cd6c3)
Location: include/crypto/skcipher.h:354
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_setkey
  - crypto/cts.c:crypto_cts_setkey
```
```
In crypto/xts.c (ffffffff814ce92b)
Location: include/crypto/skcipher.h:354
Inline: True
```
```
In crypto/ctr.c (ffffffff814cecc4)
Location: include/crypto/skcipher.h:354
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_setkey
  - crypto/ctr.c:crypto_rfc3686_setkey
```
```
In crypto/gcm.c (ffffffff814d018d)
Location: include/crypto/skcipher.h:354
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_setkey
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
In fs/crypto/keysetup.c (ffffffff81393472)
Location: include/crypto/skcipher.h:316
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_allocate_skcipher
```
```
In fs/crypto/keysetup_v1.c (ffffffff813941ac)
Location: include/crypto/skcipher.h:316
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff81463830)
Location: include/crypto/skcipher.h:316
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_process_key_cipher
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_ctx
```
```
In crypto/skcipher.c (ffffffff815225c0)
Location: include/crypto/skcipher.h:316
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/skcipher.c:crypto_skcipher_setkey
```
```
In crypto/cts.c (ffffffff8152cb2f)
Location: include/crypto/skcipher.h:316
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_setkey
```
```
In crypto/xts.c (ffffffff8152dbee)
Location: include/crypto/skcipher.h:316
Inline: True
```
```
In crypto/ctr.c (ffffffff8152e07c)
Location: include/crypto/skcipher.h:316
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_setkey
```
```
In crypto/gcm.c (ffffffff81530200)
Location: include/crypto/skcipher.h:316
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In block/blk-crypto-fallback.c (ffffffff81582fbc)
Location: include/crypto/skcipher.h:316
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_start_using_mode
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
In fs/crypto/keysetup.c (ffffffff813a4612)
Location: include/crypto/skcipher.h:316
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_allocate_skcipher
```
```
In fs/crypto/keysetup_v1.c (ffffffff813a566c)
Location: include/crypto/skcipher.h:316
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff8147eff0)
Location: include/crypto/skcipher.h:316
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_process_key_cipher
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_ctx
```
```
In crypto/skcipher.c (ffffffff8153f4a0)
Location: include/crypto/skcipher.h:316
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/skcipher.c:crypto_skcipher_setkey
```
```
In crypto/cts.c (ffffffff81549b9f)
Location: include/crypto/skcipher.h:316
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_setkey
```
```
In crypto/xts.c (ffffffff8154abbe)
Location: include/crypto/skcipher.h:316
Inline: True
```
```
In crypto/ctr.c (ffffffff8154b09c)
Location: include/crypto/skcipher.h:316
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_setkey
```
```
In crypto/gcm.c (ffffffff8154d150)
Location: include/crypto/skcipher.h:316
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In block/blk-crypto-fallback.c (ffffffff8159fe5c)
Location: include/crypto/skcipher.h:316
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_start_using_mode
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
In fs/crypto/keysetup.c (ffffffff813ab9d7)
Location: include/crypto/skcipher.h:318
Inline: True
```
```
In fs/crypto/keysetup_v1.c (ffffffff813ac74c)
Location: include/crypto/skcipher.h:318
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff81486a6a)
Location: include/crypto/skcipher.h:318
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_ctx
```
```
In crypto/skcipher.c (ffffffff81547b00)
Location: include/crypto/skcipher.h:318
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/skcipher.c:crypto_skcipher_setkey
```
```
In crypto/cts.c (ffffffff815521ec)
Location: include/crypto/skcipher.h:318
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_setkey
```
```
In crypto/xts.c (ffffffff815531de)
Location: include/crypto/skcipher.h:318
Inline: True
```
```
In crypto/ctr.c (ffffffff815536bc)
Location: include/crypto/skcipher.h:318
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_setkey
```
```
In crypto/gcm.c (ffffffff815550cd)
Location: include/crypto/skcipher.h:318
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In block/blk-crypto-fallback.c (ffffffff815a6c4c)
Location: include/crypto/skcipher.h:318
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_start_using_mode
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
In fs/crypto/keysetup.c (ffffffff813fb286)
Location: include/crypto/skcipher.h:318
Inline: True
```
```
In fs/crypto/keysetup_v1.c (ffffffff813fc0bc)
Location: include/crypto/skcipher.h:318
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff814de1fa)
Location: include/crypto/skcipher.h:318
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_ctx
```
```
In crypto/skcipher.c (ffffffff815a82e0)
Location: include/crypto/skcipher.h:318
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/skcipher.c:crypto_skcipher_setkey
```
```
In crypto/cts.c (ffffffff815b31ec)
Location: include/crypto/skcipher.h:318
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_setkey
```
```
In crypto/xts.c (ffffffff815b420e)
Location: include/crypto/skcipher.h:318
Inline: True
```
```
In crypto/ctr.c (ffffffff815b46ec)
Location: include/crypto/skcipher.h:318
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_setkey
```
```
In crypto/gcm.c (ffffffff815b60fd)
Location: include/crypto/skcipher.h:318
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In block/blk-crypto-fallback.c (ffffffff8160f7bf)
Location: include/crypto/skcipher.h:318
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_start_using_mode
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
In fs/crypto/keysetup.c (ffffffff8146e5b8)
Location: include/crypto/skcipher.h:322
Inline: True
```
```
In fs/crypto/keysetup_v1.c (ffffffff8146f535)
Location: include/crypto/skcipher.h:322
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff8156c235)
Location: include/crypto/skcipher.h:322
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_ctx
```
```
In crypto/skcipher.c (ffffffff8164fff0)
Location: include/crypto/skcipher.h:322
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/skcipher.c:crypto_skcipher_setkey
```
```
In crypto/cts.c (ffffffff8165c1bc)
Location: include/crypto/skcipher.h:322
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_setkey
```
```
In crypto/xts.c (ffffffff8165d078)
Location: include/crypto/skcipher.h:322
Inline: True
```
```
In crypto/ctr.c (ffffffff8165d5ad)
Location: include/crypto/skcipher.h:322
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_setkey
```
```
In crypto/gcm.c (ffffffff8165f3af)
Location: include/crypto/skcipher.h:322
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In block/blk-crypto-fallback.c (ffffffff816c4111)
Location: include/crypto/skcipher.h:322
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_start_using_mode
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
In fs/crypto/keysetup.c (ffffffff814ffc08)
Location: include/crypto/skcipher.h:322
Inline: True
```
```
In fs/crypto/keysetup_v1.c (ffffffff81500cb5)
Location: include/crypto/skcipher.h:322
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff816103cc)
Location: include/crypto/skcipher.h:322
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_ctx
```
```
In crypto/skcipher.c (ffffffff81709740)
Location: include/crypto/skcipher.h:322
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/skcipher.c:crypto_skcipher_setkey
```
```
In crypto/cts.c (ffffffff81715b5c)
Location: include/crypto/skcipher.h:322
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_setkey
```
```
In crypto/xts.c (ffffffff81716b58)
Location: include/crypto/skcipher.h:322
Inline: True
```
```
In crypto/ctr.c (ffffffff817171ed)
Location: include/crypto/skcipher.h:322
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_setkey
```
```
In crypto/gcm.c (ffffffff817187df)
Location: include/crypto/skcipher.h:322
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In block/blk-crypto-fallback.c (ffffffff81785617)
Location: include/crypto/skcipher.h:322
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_start_using_mode
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
In fs/crypto/keysetup.c (ffffffff815371d8)
Location: include/crypto/skcipher.h:344
Inline: True
```
```
In fs/crypto/keysetup_v1.c (ffffffff81538344)
Location: include/crypto/skcipher.h:344
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff8164825d)
Location: include/crypto/skcipher.h:344
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_ctx
```
```
In crypto/skcipher.c (ffffffff81743060)
Location: include/crypto/skcipher.h:344
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/skcipher.c:crypto_skcipher_setkey
```
```
In crypto/cts.c (ffffffff8175140c)
Location: include/crypto/skcipher.h:344
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_setkey
```
```
In crypto/xts.c (ffffffff8175240b)
Location: include/crypto/skcipher.h:344
Inline: True
```
```
In crypto/ctr.c (ffffffff81752afd)
Location: include/crypto/skcipher.h:344
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_setkey
```
```
In crypto/gcm.c (ffffffff8175414f)
Location: include/crypto/skcipher.h:344
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In block/blk-crypto-fallback.c (ffffffff817c5991)
Location: include/crypto/skcipher.h:344
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_start_using_mode
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
In fs/crypto/keysetup.c (ffffffff8156c2a8)
Location: include/crypto/skcipher.h:569
Inline: True
```
```
In fs/crypto/keysetup_v1.c (ffffffff8156d494)
Location: include/crypto/skcipher.h:569
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff8168170d)
Location: include/crypto/skcipher.h:569
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_ctx
```
```
In crypto/skcipher.c (ffffffff817853d4)
Location: include/crypto/skcipher.h:569
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/skcipher.c:crypto_skcipher_setkey
```
```
In crypto/cts.c (ffffffff8179325c)
Location: include/crypto/skcipher.h:569
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_setkey
```
```
In crypto/xts.c (ffffffff8179429b)
Location: include/crypto/skcipher.h:569
Inline: True
```
```
In crypto/ctr.c (ffffffff81794a6d)
Location: include/crypto/skcipher.h:569
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_setkey
```
```
In crypto/gcm.c (ffffffff81795abf)
Location: include/crypto/skcipher.h:569
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In block/blk-crypto-fallback.c (ffffffff8180a681)
Location: include/crypto/skcipher.h:569
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_start_using_mode
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
In fs/crypto/keysetup.c (ffff80001040e944)
Location: include/crypto/skcipher.h:354
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_allocate_skcipher
```
```
In fs/crypto/keysetup_v1.c (ffff80001040f620)
Location: include/crypto/skcipher.h:354
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffff8000104f8bf8)
Location: include/crypto/skcipher.h:354
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_ctx
```
```
In crypto/skcipher.c (ffff8000105bdd40)
Location: include/crypto/skcipher.h:354
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_simple
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/skcipher.c:skcipher_setkey
  - crypto/skcipher.c:skcipher_setkey
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
  - crypto/skcipher.c:skcipher_setkey_blkcipher
  - crypto/skcipher.c:skcipher_setkey_blkcipher
```
```
In crypto/cts.c (ffff8000105c957c)
Location: include/crypto/skcipher.h:354
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_setkey
  - crypto/cts.c:crypto_cts_setkey
```
```
In crypto/xts.c (ffff8000105cab4c)
Location: include/crypto/skcipher.h:354
Inline: True
```
```
In crypto/ctr.c (ffff8000105cabfc)
Location: include/crypto/skcipher.h:354
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_setkey
  - crypto/ctr.c:crypto_rfc3686_setkey
```
```
In crypto/gcm.c (ffff8000105cc670)
Location: include/crypto/skcipher.h:354
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_setkey
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
In fs/crypto/keysetup.c (c05db450)
Location: include/crypto/skcipher.h:354
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_allocate_skcipher
```
```
In fs/crypto/keysetup_v1.c (c05dc2fc)
Location: include/crypto/skcipher.h:354
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
```
```
In fs/ecryptfs/crypto.c (c06b64a4)
Location: include/crypto/skcipher.h:354
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_ctx
```
```
In crypto/skcipher.c (c076bb84)
Location: include/crypto/skcipher.h:354
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_simple
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/skcipher.c:skcipher_setkey
  - crypto/skcipher.c:skcipher_setkey
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
  - crypto/skcipher.c:skcipher_setkey_blkcipher
  - crypto/skcipher.c:skcipher_setkey_blkcipher
```
```
In crypto/cts.c (c0777148)
Location: include/crypto/skcipher.h:354
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_setkey
  - crypto/cts.c:crypto_cts_setkey
```
```
In crypto/xts.c (c0778734)
Location: include/crypto/skcipher.h:354
Inline: True
```
```
In crypto/ctr.c (c07787cc)
Location: include/crypto/skcipher.h:354
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_setkey
  - crypto/ctr.c:crypto_rfc3686_setkey
```
```
In crypto/gcm.c (c077a558)
Location: include/crypto/skcipher.h:354
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_setkey
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
In fs/crypto/keysetup.c (c00000000051be8c)
Location: include/crypto/skcipher.h:354
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_allocate_skcipher
```
```
In fs/crypto/keysetup_v1.c (c00000000051d0b8)
Location: include/crypto/skcipher.h:354
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (c00000000063aa50)
Location: include/crypto/skcipher.h:354
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_ctx
```
```
In crypto/skcipher.c (c000000000745230)
Location: include/crypto/skcipher.h:354
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_simple
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/skcipher.c:skcipher_setkey
  - crypto/skcipher.c:skcipher_setkey
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
  - crypto/skcipher.c:skcipher_setkey_blkcipher
  - crypto/skcipher.c:skcipher_setkey_blkcipher
```
```
In crypto/cts.c (c000000000753ba8)
Location: include/crypto/skcipher.h:354
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_setkey
  - crypto/cts.c:crypto_cts_setkey
```
```
In crypto/xts.c (c0000000007554f0)
Location: include/crypto/skcipher.h:354
Inline: True
```
```
In crypto/ctr.c (c0000000007559d8)
Location: include/crypto/skcipher.h:354
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_setkey
  - crypto/ctr.c:crypto_rfc3686_setkey
```
```
In crypto/gcm.c (c000000000757ac4)
Location: include/crypto/skcipher.h:354
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_setkey
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
In fs/crypto/keysetup.c (ffffffe0002b786e)
Location: include/crypto/skcipher.h:354
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_allocate_skcipher
```
```
In fs/crypto/keysetup_v1.c (ffffffe0002b84ea)
Location: include/crypto/skcipher.h:354
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
```
```
In fs/ecryptfs/crypto.c (ffffffe0003674d2)
Location: include/crypto/skcipher.h:354
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_ctx
```
```
In crypto/skcipher.c (ffffffe000403252)
Location: include/crypto/skcipher.h:354
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_simple
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/skcipher.c:skcipher_setkey
  - crypto/skcipher.c:skcipher_setkey
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
  - crypto/skcipher.c:skcipher_setkey_blkcipher
  - crypto/skcipher.c:skcipher_setkey_blkcipher
```
```
In crypto/cts.c (ffffffe00040dd8e)
Location: include/crypto/skcipher.h:354
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_setkey
  - crypto/cts.c:crypto_cts_setkey
```
```
In crypto/xts.c (ffffffe00040ed34)
Location: include/crypto/skcipher.h:354
Inline: True
```
```
In crypto/ctr.c (ffffffe00040f0c6)
Location: include/crypto/skcipher.h:354
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_setkey
  - crypto/ctr.c:crypto_rfc3686_setkey
```
```
In crypto/gcm.c (ffffffe0004105d0)
Location: include/crypto/skcipher.h:354
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_setkey
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
In fs/crypto/keysetup.c (ffffffff81345d2f)
Location: include/crypto/skcipher.h:354
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_allocate_skcipher
```
```
In fs/crypto/keysetup_v1.c (ffffffff813469ec)
Location: include/crypto/skcipher.h:354
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff8140f78a)
Location: include/crypto/skcipher.h:354
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_ctx
```
```
In crypto/skcipher.c (ffffffff814bbaec)
Location: include/crypto/skcipher.h:354
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_simple
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/skcipher.c:skcipher_setkey
  - crypto/skcipher.c:skcipher_setkey
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
  - crypto/skcipher.c:skcipher_setkey_blkcipher
  - crypto/skcipher.c:skcipher_setkey_blkcipher
```
```
In crypto/cts.c (ffffffff814c5ca3)
Location: include/crypto/skcipher.h:354
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_setkey
  - crypto/cts.c:crypto_cts_setkey
```
```
In crypto/xts.c (ffffffff814c6f0b)
Location: include/crypto/skcipher.h:354
Inline: True
```
```
In crypto/ctr.c (ffffffff814c72a4)
Location: include/crypto/skcipher.h:354
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_setkey
  - crypto/ctr.c:crypto_rfc3686_setkey
```
```
In crypto/gcm.c (ffffffff814c876d)
Location: include/crypto/skcipher.h:354
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_setkey
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
In fs/crypto/keysetup.c (ffffffff81336a0f)
Location: include/crypto/skcipher.h:354
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_allocate_skcipher
```
```
In fs/crypto/keysetup_v1.c (ffffffff813376cc)
Location: include/crypto/skcipher.h:354
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff8140020a)
Location: include/crypto/skcipher.h:354
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_ctx
```
```
In crypto/skcipher.c (ffffffff814ac50c)
Location: include/crypto/skcipher.h:354
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_simple
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/skcipher.c:skcipher_setkey
  - crypto/skcipher.c:skcipher_setkey
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
  - crypto/skcipher.c:skcipher_setkey_blkcipher
  - crypto/skcipher.c:skcipher_setkey_blkcipher
```
```
In crypto/cts.c (ffffffff814b66c3)
Location: include/crypto/skcipher.h:354
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_setkey
  - crypto/cts.c:crypto_cts_setkey
```
```
In crypto/xts.c (ffffffff814b792b)
Location: include/crypto/skcipher.h:354
Inline: True
```
```
In crypto/ctr.c (ffffffff814b7cc4)
Location: include/crypto/skcipher.h:354
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_setkey
  - crypto/ctr.c:crypto_rfc3686_setkey
```
```
In crypto/gcm.c (ffffffff814b918d)
Location: include/crypto/skcipher.h:354
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_setkey
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
In fs/crypto/keysetup.c (ffffffff813437ff)
Location: include/crypto/skcipher.h:354
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_allocate_skcipher
```
```
In fs/crypto/keysetup_v1.c (ffffffff813444bc)
Location: include/crypto/skcipher.h:354
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff8140cb0a)
Location: include/crypto/skcipher.h:354
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_ctx
```
```
In crypto/skcipher.c (ffffffff814b7b7c)
Location: include/crypto/skcipher.h:354
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_simple
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/skcipher.c:skcipher_setkey
  - crypto/skcipher.c:skcipher_setkey
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
  - crypto/skcipher.c:skcipher_setkey_blkcipher
  - crypto/skcipher.c:skcipher_setkey_blkcipher
```
```
In crypto/cts.c (ffffffff814c1d33)
Location: include/crypto/skcipher.h:354
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_setkey
  - crypto/cts.c:crypto_cts_setkey
```
```
In crypto/xts.c (ffffffff814c2f9b)
Location: include/crypto/skcipher.h:354
Inline: True
```
```
In crypto/ctr.c (ffffffff814c3334)
Location: include/crypto/skcipher.h:354
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_setkey
  - crypto/ctr.c:crypto_rfc3686_setkey
```
```
In crypto/gcm.c (ffffffff814c47fd)
Location: include/crypto/skcipher.h:354
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_setkey
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
In fs/crypto/keysetup.c (ffffffff81356adf)
Location: include/crypto/skcipher.h:354
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_allocate_skcipher
```
```
In fs/crypto/keysetup_v1.c (ffffffff8135779c)
Location: include/crypto/skcipher.h:354
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff8142278a)
Location: include/crypto/skcipher.h:354
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_ctx
```
```
In crypto/skcipher.c (ffffffff814d065c)
Location: include/crypto/skcipher.h:354
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_simple
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/skcipher.c:skcipher_setkey
  - crypto/skcipher.c:skcipher_setkey
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
  - crypto/skcipher.c:skcipher_setkey_blkcipher
  - crypto/skcipher.c:skcipher_setkey_blkcipher
```
```
In crypto/cts.c (ffffffff814da803)
Location: include/crypto/skcipher.h:354
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_setkey
  - crypto/cts.c:crypto_cts_setkey
```
```
In crypto/xts.c (ffffffff814dba6b)
Location: include/crypto/skcipher.h:354
Inline: True
```
```
In crypto/ctr.c (ffffffff814dbe04)
Location: include/crypto/skcipher.h:354
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_setkey
  - crypto/ctr.c:crypto_rfc3686_setkey
```
```
In crypto/gcm.c (ffffffff814dd2cd)
Location: include/crypto/skcipher.h:354
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_setkey
```
</details>
</li>
</ul>

## Differences
