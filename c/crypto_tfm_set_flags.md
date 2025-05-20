# Function: <code>crypto_tfm_set_flags</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/crypto/crc32c-intel_glue.c (ffffffff810763bc)
Location: include/linux/crypto.h:666
Inline: True
Inline callers:
  - arch/x86/crypto/crc32c-intel_glue.c:crc32c_intel_setkey
```
```
In fs/ext4/crypto_key.c (ffffffff812e582c)
Location: include/linux/crypto.h:666
Inline: True
Inline callers:
  - fs/ext4/crypto_key.c:ext4_derive_key_aes
  - fs/ext4/crypto_key.c:_ext4_get_encryption_info
```
```
In fs/ecryptfs/crypto.c (ffffffff81305f65)
Location: include/linux/crypto.h:666
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_ctx
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
```
```
In crypto/ablkcipher.c (ffffffff813a0380)
Location: include/linux/crypto.h:666
Inline: True
Inline callers:
  - crypto/ablkcipher.c:setkey
```
```
In crypto/skcipher.c (ffffffff813a1a39)
Location: include/linux/crypto.h:666
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_blkcipher
  - crypto/skcipher.c:skcipher_setkey_blkcipher
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
```
```
In crypto/ecb.c (ffffffff813a8e6c)
Location: include/linux/crypto.h:666
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_setkey
  - crypto/ecb.c:crypto_ecb_setkey
```
```
In crypto/cbc.c (ffffffff813a91bc)
Location: include/linux/crypto.h:666
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_setkey
  - crypto/cbc.c:crypto_cbc_setkey
```
```
In crypto/crc32c_generic.c (ffffffff813ab77c)
Location: include/linux/crypto.h:666
Inline: True
Inline callers:
  - crypto/crc32c_generic.c:chksum_setkey
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
In arch/x86/crypto/crc32c-intel_glue.c (ffffffff810779bc)
Location: include/linux/crypto.h:641
Inline: True
Inline callers:
  - arch/x86/crypto/crc32c-intel_glue.c:crc32c_intel_setkey
```
```
In fs/crypto/keyinfo.c (ffffffff8128a189)
Location: include/linux/crypto.h:641
Inline: True
Inline callers:
  - fs/crypto/keyinfo.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff8133b003)
Location: include/linux/crypto.h:641
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_ctx
```
```
In crypto/ablkcipher.c (ffffffff813dca88)
Location: include/linux/crypto.h:641
Inline: True
Inline callers:
  - crypto/ablkcipher.c:setkey
```
```
In crypto/skcipher.c (ffffffff813de015)
Location: include/linux/crypto.h:641
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
  - crypto/skcipher.c:skcipher_setkey_blkcipher
  - crypto/skcipher.c:skcipher_setkey_blkcipher
```
```
In crypto/ecb.c (ffffffff813e6e47)
Location: include/linux/crypto.h:641
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_setkey
  - crypto/ecb.c:crypto_ecb_setkey
```
```
In crypto/cbc.c (ffffffff813e7187)
Location: include/linux/crypto.h:641
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_setkey
  - crypto/cbc.c:crypto_cbc_setkey
```
```
In crypto/cts.c (ffffffff813e775a)
Location: include/linux/crypto.h:641
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_setkey
  - crypto/cts.c:crypto_cts_setkey
```
```
In crypto/xts.c (ffffffff813e80fc)
Location: include/linux/crypto.h:641
Inline: True
Inline callers:
  - crypto/xts.c:setkey
  - crypto/xts.c:setkey
  - crypto/xts.c:setkey
  - crypto/xts.c:setkey
```
```
In crypto/ctr.c (ffffffff813e8854)
Location: include/linux/crypto.h:641
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_setkey
  - crypto/ctr.c:crypto_rfc3686_setkey
  - crypto/ctr.c:crypto_ctr_setkey
  - crypto/ctr.c:crypto_ctr_setkey
```
```
In crypto/crc32c_generic.c (ffffffff813eafdc)
Location: include/linux/crypto.h:641
Inline: True
Inline callers:
  - crypto/crc32c_generic.c:chksum_setkey
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
In arch/x86/crypto/crc32c-intel_glue.c (ffffffff8107b7ac)
Location: include/linux/crypto.h:644
Inline: True
Inline callers:
  - arch/x86/crypto/crc32c-intel_glue.c:crc32c_intel_setkey
```
```
In fs/crypto/keyinfo.c (ffffffff8129eec9)
Location: include/linux/crypto.h:644
Inline: True
Inline callers:
  - fs/crypto/keyinfo.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff81350d97)
Location: include/linux/crypto.h:644
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_ctx
```
```
In crypto/ablkcipher.c (ffffffff813f4368)
Location: include/linux/crypto.h:644
Inline: True
Inline callers:
  - crypto/ablkcipher.c:setkey
```
```
In crypto/skcipher.c (ffffffff813f58e5)
Location: include/linux/crypto.h:644
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
  - crypto/skcipher.c:skcipher_setkey_blkcipher
  - crypto/skcipher.c:skcipher_setkey_blkcipher
```
```
In crypto/ecb.c (ffffffff813ffbf7)
Location: include/linux/crypto.h:644
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_setkey
  - crypto/ecb.c:crypto_ecb_setkey
```
```
In crypto/cbc.c (ffffffff813fff38)
Location: include/linux/crypto.h:644
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_setkey
  - crypto/cbc.c:crypto_cbc_setkey
```
```
In crypto/cts.c (ffffffff8140058a)
Location: include/linux/crypto.h:644
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_setkey
  - crypto/cts.c:crypto_cts_setkey
```
```
In crypto/xts.c (ffffffff81401358)
Location: include/linux/crypto.h:644
Inline: True
```
```
In crypto/ctr.c (ffffffff81401e64)
Location: include/linux/crypto.h:644
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_setkey
  - crypto/ctr.c:crypto_rfc3686_setkey
  - crypto/ctr.c:crypto_ctr_setkey
  - crypto/ctr.c:crypto_ctr_setkey
```
```
In crypto/crc32c_generic.c (ffffffff8140460c)
Location: include/linux/crypto.h:644
Inline: True
Inline callers:
  - crypto/crc32c_generic.c:chksum_setkey
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
In arch/x86/crypto/crc32c-intel_glue.c (ffffffff81079f6c)
Location: include/linux/crypto.h:644
Inline: True
Inline callers:
  - arch/x86/crypto/crc32c-intel_glue.c:crc32c_intel_setkey
```
```
In fs/crypto/keyinfo.c (ffffffff812ad92c)
Location: include/linux/crypto.h:644
Inline: True
Inline callers:
  - fs/crypto/keyinfo.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff813658b7)
Location: include/linux/crypto.h:644
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_ctx
```
```
In crypto/ablkcipher.c (ffffffff814006c5)
Location: include/linux/crypto.h:644
Inline: True
Inline callers:
  - crypto/ablkcipher.c:setkey
```
```
In crypto/skcipher.c (ffffffff814020a3)
Location: include/linux/crypto.h:644
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
  - crypto/skcipher.c:skcipher_setkey_blkcipher
  - crypto/skcipher.c:skcipher_setkey_blkcipher
```
```
In crypto/ecb.c (ffffffff8140cee7)
Location: include/linux/crypto.h:644
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_setkey
  - crypto/ecb.c:crypto_ecb_setkey
```
```
In crypto/cbc.c (ffffffff8140d248)
Location: include/linux/crypto.h:644
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_setkey
  - crypto/cbc.c:crypto_cbc_setkey
```
```
In crypto/cts.c (ffffffff8140d88a)
Location: include/linux/crypto.h:644
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_setkey
  - crypto/cts.c:crypto_cts_setkey
```
```
In crypto/xts.c (ffffffff8140e64f)
Location: include/linux/crypto.h:644
Inline: True
Inline callers:
  - crypto/xts.c:setkey
  - crypto/xts.c:setkey
  - crypto/xts.c:setkey
  - crypto/xts.c:setkey
  - crypto/xts.c:setkey
  - crypto/xts.c:setkey
```
```
In crypto/ctr.c (ffffffff8140f2af)
Location: include/linux/crypto.h:644
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_setkey
  - crypto/ctr.c:crypto_rfc3686_setkey
  - crypto/ctr.c:crypto_ctr_setkey
  - crypto/ctr.c:crypto_ctr_setkey
```
```
In crypto/crc32c_generic.c (ffffffff81411d4c)
Location: include/linux/crypto.h:644
Inline: True
Inline callers:
  - crypto/crc32c_generic.c:chksum_setkey
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
In arch/x86/crypto/crc32c-intel_glue.c (ffffffff8108065c)
Location: include/linux/crypto.h:692
Inline: True
Inline callers:
  - arch/x86/crypto/crc32c-intel_glue.c:crc32c_intel_setkey
```
```
In fs/crypto/keyinfo.c (ffffffff812d0ded)
Location: include/linux/crypto.h:692
Inline: True
Inline callers:
  - fs/crypto/keyinfo.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff8138a577)
Location: include/linux/crypto.h:692
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_ctx
```
```
In crypto/ablkcipher.c (ffffffff81428cbf)
Location: include/linux/crypto.h:692
Inline: True
Inline callers:
  - crypto/ablkcipher.c:setkey
```
```
In crypto/skcipher.c (ffffffff8142a715)
Location: include/linux/crypto.h:692
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
  - crypto/skcipher.c:skcipher_setkey_blkcipher
  - crypto/skcipher.c:skcipher_setkey_blkcipher
```
```
In crypto/ahash.c (ffffffff8142c477)
Location: include/linux/crypto.h:692
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_init_tfm
```
```
In crypto/shash.c (ffffffff8142c8f3)
Location: include/linux/crypto.h:692
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_init_tfm
  - crypto/shash.c:crypto_init_shash_ops_async
```
```
In crypto/ecb.c (ffffffff81435947)
Location: include/linux/crypto.h:692
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_setkey
  - crypto/ecb.c:crypto_ecb_setkey
```
```
In crypto/cbc.c (ffffffff81435cb8)
Location: include/linux/crypto.h:692
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_setkey
  - crypto/cbc.c:crypto_cbc_setkey
```
```
In crypto/cts.c (ffffffff8143631a)
Location: include/linux/crypto.h:692
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_setkey
  - crypto/cts.c:crypto_cts_setkey
```
```
In crypto/xts.c (ffffffff81437119)
Location: include/linux/crypto.h:692
Inline: True
Inline callers:
  - crypto/xts.c:setkey
  - crypto/xts.c:setkey
  - crypto/xts.c:setkey
  - crypto/xts.c:setkey
  - crypto/xts.c:setkey
  - crypto/xts.c:setkey
```
```
In crypto/ctr.c (ffffffff81437e7f)
Location: include/linux/crypto.h:692
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_setkey
  - crypto/ctr.c:crypto_rfc3686_setkey
  - crypto/ctr.c:crypto_ctr_setkey
  - crypto/ctr.c:crypto_ctr_setkey
```
```
In crypto/gcm.c (ffffffff81438f0f)
Location: include/linux/crypto.h:692
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_setkey
  - crypto/gcm.c:crypto_rfc4543_setkey
  - crypto/gcm.c:crypto_rfc4106_setkey
  - crypto/gcm.c:crypto_rfc4106_setkey
  - crypto/gcm.c:crypto_gcm_setkey
  - crypto/gcm.c:crypto_gcm_setkey
  - crypto/gcm.c:crypto_gcm_setkey
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/crc32c_generic.c (ffffffff8143c4bc)
Location: include/linux/crypto.h:692
Inline: True
Inline callers:
  - crypto/crc32c_generic.c:chksum_setkey
```
```
In crypto/ghash-generic.c (ffffffff8144127f)
Location: include/linux/crypto.h:692
Inline: True
Inline callers:
  - crypto/ghash-generic.c:ghash_setkey
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
In arch/x86/crypto/crc32c-intel_glue.c (ffffffff810838a7)
Location: include/linux/crypto.h:705
Inline: True
Inline callers:
  - arch/x86/crypto/crc32c-intel_glue.c:crc32c_intel_setkey
```
```
In fs/crypto/keyinfo.c (ffffffff812fb979)
Location: include/linux/crypto.h:705
Inline: True
Inline callers:
  - fs/crypto/keyinfo.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff813b92bd)
Location: include/linux/crypto.h:705
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_ctx
```
```
In crypto/aead.c (ffffffff8145ace9)
Location: include/linux/crypto.h:705
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_init_tfm
```
```
In crypto/ablkcipher.c (ffffffff8145baef)
Location: include/linux/crypto.h:705
Inline: True
Inline callers:
  - crypto/ablkcipher.c:setkey
```
```
In crypto/skcipher.c (ffffffff8145d4e9)
Location: include/linux/crypto.h:705
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/skcipher.c:skcipher_setkey
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
  - crypto/skcipher.c:skcipher_setkey_blkcipher
  - crypto/skcipher.c:skcipher_setkey_blkcipher
```
```
In crypto/ahash.c (ffffffff8145f147)
Location: include/linux/crypto.h:705
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_init_tfm
```
```
In crypto/shash.c (ffffffff8145f553)
Location: include/linux/crypto.h:705
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_init_tfm
  - crypto/shash.c:crypto_init_shash_ops_async
```
```
In crypto/ecb.c (ffffffff814684cd)
Location: include/linux/crypto.h:705
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_setkey
  - crypto/ecb.c:crypto_ecb_setkey
```
```
In crypto/cbc.c (ffffffff8146883d)
Location: include/linux/crypto.h:705
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_setkey
  - crypto/cbc.c:crypto_cbc_setkey
```
```
In crypto/cts.c (ffffffff81468e5f)
Location: include/linux/crypto.h:705
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_setkey
  - crypto/cts.c:crypto_cts_setkey
```
```
In crypto/xts.c (ffffffff81469b47)
Location: include/linux/crypto.h:705
Inline: True
```
```
In crypto/ctr.c (ffffffff8146a7d4)
Location: include/linux/crypto.h:705
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_setkey
  - crypto/ctr.c:crypto_rfc3686_setkey
  - crypto/ctr.c:crypto_ctr_setkey
  - crypto/ctr.c:crypto_ctr_setkey
```
```
In crypto/gcm.c (ffffffff8146b214)
Location: include/linux/crypto.h:705
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_setkey
  - crypto/gcm.c:crypto_rfc4543_setkey
  - crypto/gcm.c:crypto_rfc4106_setkey
  - crypto/gcm.c:crypto_rfc4106_setkey
  - crypto/gcm.c:crypto_gcm_setkey
  - crypto/gcm.c:crypto_gcm_setkey
  - crypto/gcm.c:crypto_gcm_setkey
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/crc32c_generic.c (ffffffff8146f2f7)
Location: include/linux/crypto.h:705
Inline: True
Inline callers:
  - crypto/crc32c_generic.c:chksum_setkey
```
```
In crypto/ghash-generic.c (ffffffff8147419f)
Location: include/linux/crypto.h:705
Inline: True
Inline callers:
  - crypto/ghash-generic.c:ghash_setkey
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
In arch/x86/crypto/crc32c-intel_glue.c (ffffffff8108a577)
Location: include/linux/crypto.h:876
Inline: True
Inline callers:
  - arch/x86/crypto/crc32c-intel_glue.c:crc32c_intel_setkey
```
```
In fs/crypto/keyinfo.c (ffffffff81310ecc)
Location: include/linux/crypto.h:876
Inline: True
Inline callers:
  - fs/crypto/keyinfo.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff813d282d)
Location: include/linux/crypto.h:876
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_ctx
```
```
In crypto/aead.c (ffffffff81478859)
Location: include/linux/crypto.h:876
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_init_tfm
  - crypto/aead.c:crypto_aead_setkey
```
```
In crypto/ablkcipher.c (ffffffff8147926f)
Location: include/linux/crypto.h:876
Inline: True
Inline callers:
  - crypto/ablkcipher.c:setkey
```
```
In crypto/skcipher.c (ffffffff8147ae1e)
Location: include/linux/crypto.h:876
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/skcipher.c:skcipher_setkey
  - crypto/skcipher.c:skcipher_setkey
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
  - crypto/skcipher.c:skcipher_setkey_blkcipher
  - crypto/skcipher.c:skcipher_setkey_blkcipher
  - crypto/skcipher.c:skcipher_setkey_blkcipher
```
```
In crypto/ahash.c (ffffffff8147cb30)
Location: include/linux/crypto.h:876
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_init_tfm
  - crypto/ahash.c:crypto_ahash_setkey
```
```
In crypto/shash.c (ffffffff8147cf83)
Location: include/linux/crypto.h:876
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_init_tfm
  - crypto/shash.c:crypto_init_shash_ops_async
  - crypto/shash.c:crypto_shash_setkey
```
```
In crypto/ecb.c (ffffffff8148613d)
Location: include/linux/crypto.h:876
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_setkey
  - crypto/ecb.c:crypto_ecb_setkey
```
```
In crypto/cbc.c (ffffffff814864ad)
Location: include/linux/crypto.h:876
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_setkey
  - crypto/cbc.c:crypto_cbc_setkey
```
```
In crypto/cts.c (ffffffff81486adf)
Location: include/linux/crypto.h:876
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_setkey
  - crypto/cts.c:crypto_cts_setkey
```
```
In crypto/xts.c (ffffffff81487a17)
Location: include/linux/crypto.h:876
Inline: True
```
```
In crypto/ctr.c (ffffffff81488034)
Location: include/linux/crypto.h:876
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_setkey
  - crypto/ctr.c:crypto_rfc3686_setkey
  - crypto/ctr.c:crypto_ctr_setkey
  - crypto/ctr.c:crypto_ctr_setkey
```
```
In crypto/gcm.c (ffffffff81488b14)
Location: include/linux/crypto.h:876
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_setkey
  - crypto/gcm.c:crypto_rfc4543_setkey
  - crypto/gcm.c:crypto_rfc4106_setkey
  - crypto/gcm.c:crypto_rfc4106_setkey
  - crypto/gcm.c:crypto_gcm_setkey
  - crypto/gcm.c:crypto_gcm_setkey
  - crypto/gcm.c:crypto_gcm_setkey
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/crc32c_generic.c (ffffffff8148cca7)
Location: include/linux/crypto.h:876
Inline: True
Inline callers:
  - crypto/crc32c_generic.c:chksum_setkey
```
```
In crypto/ghash-generic.c (ffffffff81491d0f)
Location: include/linux/crypto.h:876
Inline: True
Inline callers:
  - crypto/ghash-generic.c:ghash_setkey
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
In arch/x86/crypto/crc32c-intel_glue.c (ffffffff8108e377)
Location: include/linux/crypto.h:873
Inline: True
Inline callers:
  - arch/x86/crypto/crc32c-intel_glue.c:crc32c_intel_setkey
```
```
In fs/crypto/keyinfo.c (ffffffff813385fd)
Location: include/linux/crypto.h:873
Inline: True
Inline callers:
  - fs/crypto/keyinfo.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff813fd2c9)
Location: include/linux/crypto.h:873
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_ctx
```
```
In crypto/aead.c (ffffffff814a6689)
Location: include/linux/crypto.h:873
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_init_tfm
  - crypto/aead.c:crypto_aead_setkey
```
```
In crypto/ablkcipher.c (ffffffff814a78bd)
Location: include/linux/crypto.h:873
Inline: True
Inline callers:
  - crypto/ablkcipher.c:setkey
```
```
In crypto/skcipher.c (ffffffff814a8891)
Location: include/linux/crypto.h:873
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_simple
  - crypto/skcipher.c:skcipher_setkey_simple
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/skcipher.c:skcipher_setkey
  - crypto/skcipher.c:skcipher_setkey
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
  - crypto/skcipher.c:skcipher_setkey_blkcipher
  - crypto/skcipher.c:skcipher_setkey_blkcipher
  - crypto/skcipher.c:skcipher_setkey_blkcipher
```
```
In crypto/ahash.c (ffffffff814aaae0)
Location: include/linux/crypto.h:873
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_init_tfm
  - crypto/ahash.c:crypto_ahash_setkey
```
```
In crypto/shash.c (ffffffff814ab273)
Location: include/linux/crypto.h:873
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_init_tfm
  - crypto/shash.c:crypto_init_shash_ops_async
  - crypto/shash.c:crypto_shash_setkey
```
```
In crypto/cts.c (ffffffff814b4953)
Location: include/linux/crypto.h:873
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_setkey
  - crypto/cts.c:crypto_cts_setkey
```
```
In crypto/xts.c (ffffffff814b572b)
Location: include/linux/crypto.h:873
Inline: True
```
```
In crypto/ctr.c (ffffffff814b5ac4)
Location: include/linux/crypto.h:873
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_setkey
  - crypto/ctr.c:crypto_rfc3686_setkey
```
```
In crypto/gcm.c (ffffffff814b64b4)
Location: include/linux/crypto.h:873
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_setkey
  - crypto/gcm.c:crypto_rfc4543_setkey
  - crypto/gcm.c:crypto_rfc4106_setkey
  - crypto/gcm.c:crypto_rfc4106_setkey
  - crypto/gcm.c:crypto_gcm_setkey
  - crypto/gcm.c:crypto_gcm_setkey
  - crypto/gcm.c:crypto_gcm_setkey
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/crc32c_generic.c (ffffffff814ba397)
Location: include/linux/crypto.h:873
Inline: True
Inline callers:
  - crypto/crc32c_generic.c:chksum_setkey
```
```
In crypto/ghash-generic.c (ffffffff814bf3c0)
Location: include/linux/crypto.h:873
Inline: True
Inline callers:
  - crypto/ghash-generic.c:ghash_setkey
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
In arch/x86/crypto/crc32c-intel_glue.c (ffffffff8108efd7)
Location: include/linux/crypto.h:873
Inline: True
Inline callers:
  - arch/x86/crypto/crc32c-intel_glue.c:crc32c_intel_setkey
```
```
In fs/crypto/keysetup.c (ffffffff8134d74f)
Location: include/linux/crypto.h:873
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_allocate_skcipher
```
```
In fs/crypto/keysetup_v1.c (ffffffff8134e40c)
Location: include/linux/crypto.h:873
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff814171aa)
Location: include/linux/crypto.h:873
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_ctx
```
```
In crypto/aead.c (ffffffff814c1329)
Location: include/linux/crypto.h:873
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_init_tfm
  - crypto/aead.c:crypto_aead_setkey
```
```
In crypto/ablkcipher.c (ffffffff814c253d)
Location: include/linux/crypto.h:873
Inline: True
Inline callers:
  - crypto/ablkcipher.c:setkey
```
```
In crypto/skcipher.c (ffffffff814c34f1)
Location: include/linux/crypto.h:873
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_simple
  - crypto/skcipher.c:skcipher_setkey_simple
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/skcipher.c:skcipher_setkey
  - crypto/skcipher.c:skcipher_setkey
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
  - crypto/skcipher.c:skcipher_setkey_blkcipher
  - crypto/skcipher.c:skcipher_setkey_blkcipher
  - crypto/skcipher.c:skcipher_setkey_blkcipher
```
```
In crypto/ahash.c (ffffffff814c57a0)
Location: include/linux/crypto.h:873
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_init_tfm
  - crypto/ahash.c:crypto_ahash_setkey
```
```
In crypto/shash.c (ffffffff814c5f33)
Location: include/linux/crypto.h:873
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_init_tfm
  - crypto/shash.c:crypto_init_shash_ops_async
  - crypto/shash.c:crypto_shash_setkey
```
```
In crypto/cts.c (ffffffff814cd6c3)
Location: include/linux/crypto.h:873
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_setkey
  - crypto/cts.c:crypto_cts_setkey
```
```
In crypto/xts.c (ffffffff814ce92b)
Location: include/linux/crypto.h:873
Inline: True
```
```
In crypto/ctr.c (ffffffff814cecc4)
Location: include/linux/crypto.h:873
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_setkey
  - crypto/ctr.c:crypto_rfc3686_setkey
```
```
In crypto/gcm.c (ffffffff814cf6d4)
Location: include/linux/crypto.h:873
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_setkey
  - crypto/gcm.c:crypto_rfc4543_setkey
  - crypto/gcm.c:crypto_rfc4106_setkey
  - crypto/gcm.c:crypto_rfc4106_setkey
  - crypto/gcm.c:crypto_gcm_setkey
  - crypto/gcm.c:crypto_gcm_setkey
  - crypto/gcm.c:crypto_gcm_setkey
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/crc32c_generic.c (ffffffff814d3167)
Location: include/linux/crypto.h:873
Inline: True
Inline callers:
  - crypto/crc32c_generic.c:chksum_setkey
```
```
In crypto/ghash-generic.c (ffffffff814d83c6)
Location: include/linux/crypto.h:873
Inline: True
Inline callers:
  - crypto/ghash-generic.c:ghash_setkey
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
Location: include/linux/crypto.h:692
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_allocate_skcipher
```
```
In fs/crypto/keysetup_v1.c (ffffffff813941ac)
Location: include/linux/crypto.h:692
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff81463830)
Location: include/linux/crypto.h:692
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_process_key_cipher
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_ctx
```
```
In crypto/aead.c (ffffffff81521bd9)
Location: include/linux/crypto.h:692
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_init_tfm
  - crypto/aead.c:crypto_aead_setkey
```
```
In crypto/skcipher.c (ffffffff81522dbd)
Location: include/linux/crypto.h:692
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_simple
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/skcipher.c:crypto_skcipher_setkey
```
```
In crypto/ahash.c (ffffffff81524b60)
Location: include/linux/crypto.h:692
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_init_tfm
  - crypto/ahash.c:crypto_ahash_setkey
```
```
In crypto/shash.c (ffffffff81525584)
Location: include/linux/crypto.h:692
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_init_tfm
  - crypto/shash.c:crypto_init_shash_ops_async
  - crypto/shash.c:shash_async_setkey
```
```
In crypto/cts.c (ffffffff8152cb2f)
Location: include/linux/crypto.h:692
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_setkey
```
```
In crypto/xts.c (ffffffff8152dba3)
Location: include/linux/crypto.h:692
Inline: True
```
```
In crypto/ctr.c (ffffffff8152e07c)
Location: include/linux/crypto.h:692
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_setkey
```
```
In crypto/gcm.c (ffffffff8152e90c)
Location: include/linux/crypto.h:692
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_setkey
  - crypto/gcm.c:crypto_rfc4106_setkey
  - crypto/gcm.c:crypto_gcm_setkey
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In block/blk-crypto-fallback.c (ffffffff81582fbc)
Location: include/linux/crypto.h:692
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
Location: include/linux/crypto.h:728
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_allocate_skcipher
```
```
In fs/crypto/keysetup_v1.c (ffffffff813a566c)
Location: include/linux/crypto.h:728
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff8147eff0)
Location: include/linux/crypto.h:728
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_process_key_cipher
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_ctx
```
```
In crypto/aead.c (ffffffff8153ea49)
Location: include/linux/crypto.h:728
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_init_tfm
  - crypto/aead.c:crypto_aead_setkey
```
```
In crypto/skcipher.c (ffffffff8153fd0d)
Location: include/linux/crypto.h:728
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_simple
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/skcipher.c:crypto_skcipher_setkey
```
```
In crypto/ahash.c (ffffffff81541a38)
Location: include/linux/crypto.h:728
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_init_tfm
  - crypto/ahash.c:crypto_ahash_setkey
```
```
In crypto/shash.c (ffffffff815424b4)
Location: include/linux/crypto.h:728
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_init_tfm
  - crypto/shash.c:crypto_init_shash_ops_async
  - crypto/shash.c:shash_async_setkey
```
```
In crypto/cts.c (ffffffff81549b9f)
Location: include/linux/crypto.h:728
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_setkey
```
```
In crypto/xts.c (ffffffff8154ab73)
Location: include/linux/crypto.h:728
Inline: True
```
```
In crypto/ctr.c (ffffffff8154b09c)
Location: include/linux/crypto.h:728
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_setkey
```
```
In crypto/gcm.c (ffffffff8154b88c)
Location: include/linux/crypto.h:728
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_setkey
  - crypto/gcm.c:crypto_rfc4106_setkey
  - crypto/gcm.c:crypto_gcm_setkey
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In block/blk-crypto-fallback.c (ffffffff8159fe5c)
Location: include/linux/crypto.h:728
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
Location: include/linux/crypto.h:724
Inline: True
```
```
In fs/crypto/keysetup_v1.c (ffffffff813ac74c)
Location: include/linux/crypto.h:724
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff81486a6a)
Location: include/linux/crypto.h:724
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_ctx
```
```
In crypto/aead.c (ffffffff815470f9)
Location: include/linux/crypto.h:724
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_init_tfm
  - crypto/aead.c:crypto_aead_setkey
```
```
In crypto/skcipher.c (ffffffff8154827a)
Location: include/linux/crypto.h:724
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_simple
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/skcipher.c:crypto_skcipher_setkey
```
```
In crypto/ahash.c (ffffffff8154a098)
Location: include/linux/crypto.h:724
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_init_tfm
  - crypto/ahash.c:crypto_ahash_setkey
```
```
In crypto/shash.c (ffffffff8154ab54)
Location: include/linux/crypto.h:724
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_init_tfm
  - crypto/shash.c:crypto_init_shash_ops_async
  - crypto/shash.c:shash_async_setkey
```
```
In crypto/cts.c (ffffffff815521ec)
Location: include/linux/crypto.h:724
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_setkey
```
```
In crypto/xts.c (ffffffff81553193)
Location: include/linux/crypto.h:724
Inline: True
```
```
In crypto/ctr.c (ffffffff815536bc)
Location: include/linux/crypto.h:724
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_setkey
```
```
In crypto/gcm.c (ffffffff81553e8c)
Location: include/linux/crypto.h:724
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_setkey
  - crypto/gcm.c:crypto_rfc4106_setkey
  - crypto/gcm.c:crypto_gcm_setkey
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In block/blk-crypto-fallback.c (ffffffff815a6c4c)
Location: include/linux/crypto.h:724
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
Location: include/linux/crypto.h:698
Inline: True
```
```
In fs/crypto/keysetup_v1.c (ffffffff813fc0bc)
Location: include/linux/crypto.h:698
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff814de1fa)
Location: include/linux/crypto.h:698
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_ctx
```
```
In crypto/aead.c (ffffffff815a78d9)
Location: include/linux/crypto.h:698
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_init_tfm
  - crypto/aead.c:crypto_aead_setkey
```
```
In crypto/skcipher.c (ffffffff815a8a5a)
Location: include/linux/crypto.h:698
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_simple
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/skcipher.c:crypto_skcipher_setkey
```
```
In crypto/ahash.c (ffffffff815aa878)
Location: include/linux/crypto.h:698
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_init_tfm
  - crypto/ahash.c:crypto_ahash_setkey
```
```
In crypto/shash.c (ffffffff815ab334)
Location: include/linux/crypto.h:698
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_init_tfm
  - crypto/shash.c:crypto_init_shash_ops_async
  - crypto/shash.c:shash_async_setkey
```
```
In crypto/cts.c (ffffffff815b31ec)
Location: include/linux/crypto.h:698
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_setkey
```
```
In crypto/xts.c (ffffffff815b41c3)
Location: include/linux/crypto.h:698
Inline: True
```
```
In crypto/ctr.c (ffffffff815b46ec)
Location: include/linux/crypto.h:698
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_setkey
```
```
In crypto/gcm.c (ffffffff815b4ebc)
Location: include/linux/crypto.h:698
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_setkey
  - crypto/gcm.c:crypto_rfc4106_setkey
  - crypto/gcm.c:crypto_gcm_setkey
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In block/blk-crypto-fallback.c (ffffffff8160f7bf)
Location: include/linux/crypto.h:698
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
Location: include/linux/crypto.h:707
Inline: True
```
```
In fs/crypto/keysetup_v1.c (ffffffff8146f535)
Location: include/linux/crypto.h:707
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff8156c235)
Location: include/linux/crypto.h:707
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_ctx
```
```
In crypto/aead.c (ffffffff8164ec09)
Location: include/linux/crypto.h:707
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_init_tfm
  - crypto/aead.c:crypto_aead_setkey
```
```
In crypto/skcipher.c (ffffffff8164fe4a)
Location: include/linux/crypto.h:707
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_simple
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/skcipher.c:crypto_skcipher_setkey
```
```
In crypto/ahash.c (ffffffff81651ee8)
Location: include/linux/crypto.h:707
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_init_tfm
  - crypto/ahash.c:crypto_ahash_setkey
```
```
In crypto/shash.c (ffffffff81652b32)
Location: include/linux/crypto.h:707
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_init_tfm
  - crypto/shash.c:crypto_init_shash_ops_async
  - crypto/shash.c:shash_async_setkey
```
```
In crypto/cts.c (ffffffff8165c1bc)
Location: include/linux/crypto.h:707
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_setkey
```
```
In crypto/xts.c (ffffffff8165d021)
Location: include/linux/crypto.h:707
Inline: True
```
```
In crypto/ctr.c (ffffffff8165d5ad)
Location: include/linux/crypto.h:707
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_setkey
```
```
In crypto/gcm.c (ffffffff8165dedd)
Location: include/linux/crypto.h:707
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_setkey
  - crypto/gcm.c:crypto_rfc4106_setkey
  - crypto/gcm.c:crypto_gcm_setkey
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In block/blk-crypto-fallback.c (ffffffff816c4111)
Location: include/linux/crypto.h:707
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
Location: include/linux/crypto.h:707
Inline: True
```
```
In fs/crypto/keysetup_v1.c (ffffffff81500cb5)
Location: include/linux/crypto.h:707
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff816103cc)
Location: include/linux/crypto.h:707
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_ctx
```
```
In crypto/aead.c (ffffffff817080e9)
Location: include/linux/crypto.h:707
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_init_tfm
  - crypto/aead.c:crypto_aead_setkey
```
```
In crypto/skcipher.c (ffffffff8170932a)
Location: include/linux/crypto.h:707
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_simple
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/skcipher.c:crypto_skcipher_setkey
```
```
In crypto/ahash.c (ffffffff8170b938)
Location: include/linux/crypto.h:707
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_init_tfm
  - crypto/ahash.c:crypto_ahash_setkey
```
```
In crypto/shash.c (ffffffff8170c772)
Location: include/linux/crypto.h:707
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_init_tfm
  - crypto/shash.c:crypto_init_shash_ops_async
  - crypto/shash.c:shash_async_setkey
```
```
In crypto/cts.c (ffffffff81715b5c)
Location: include/linux/crypto.h:707
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_setkey
```
```
In crypto/xts.c (ffffffff81716b01)
Location: include/linux/crypto.h:707
Inline: True
```
```
In crypto/ctr.c (ffffffff817171ed)
Location: include/linux/crypto.h:707
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_setkey
```
```
In crypto/gcm.c (ffffffff81717ecd)
Location: include/linux/crypto.h:707
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_setkey
  - crypto/gcm.c:crypto_rfc4106_setkey
  - crypto/gcm.c:crypto_gcm_setkey
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In block/blk-crypto-fallback.c (ffffffff81785617)
Location: include/linux/crypto.h:707
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
Location: include/linux/crypto.h:480
Inline: True
```
```
In fs/crypto/keysetup_v1.c (ffffffff81538344)
Location: include/linux/crypto.h:480
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff8164825d)
Location: include/linux/crypto.h:480
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_ctx
```
```
In crypto/aead.c (ffffffff81741809)
Location: include/linux/crypto.h:480
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_init_tfm
  - crypto/aead.c:crypto_aead_setkey
```
```
In crypto/skcipher.c (ffffffff81742b6c)
Location: include/linux/crypto.h:480
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_simple
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/skcipher.c:crypto_skcipher_setkey
```
```
In crypto/ahash.c (ffffffff817453ce)
Location: include/linux/crypto.h:480
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_init_tfm
  - crypto/ahash.c:crypto_ahash_setkey
```
```
In crypto/shash.c (ffffffff81746282)
Location: include/linux/crypto.h:480
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_init_tfm
  - crypto/shash.c:crypto_init_shash_ops_async
  - crypto/shash.c:shash_async_setkey
```
```
In crypto/cts.c (ffffffff8175140c)
Location: include/linux/crypto.h:480
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_setkey
```
```
In crypto/xts.c (ffffffff817523b3)
Location: include/linux/crypto.h:480
Inline: True
```
```
In crypto/ctr.c (ffffffff81752afd)
Location: include/linux/crypto.h:480
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_setkey
```
```
In crypto/gcm.c (ffffffff817537ed)
Location: include/linux/crypto.h:480
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_setkey
  - crypto/gcm.c:crypto_rfc4106_setkey
  - crypto/gcm.c:crypto_gcm_setkey
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In block/blk-crypto-fallback.c (ffffffff817c5991)
Location: include/linux/crypto.h:480
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
Location: include/linux/crypto.h:480
Inline: True
```
```
In fs/crypto/keysetup_v1.c (ffffffff8156d494)
Location: include/linux/crypto.h:480
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff8168170d)
Location: include/linux/crypto.h:480
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_ctx
```
```
In crypto/aead.c (ffffffff817826a9)
Location: include/linux/crypto.h:480
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_init_tfm
  - crypto/aead.c:crypto_aead_setkey
```
```
In crypto/lskcipher.c (ffffffff817845b8)
Location: include/linux/crypto.h:480
Inline: True
Inline callers:
  - crypto/lskcipher.c:lskcipher_setkey_simple
```
```
In crypto/skcipher.c (ffffffff81784dac)
Location: include/linux/crypto.h:480
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_simple
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/skcipher.c:crypto_skcipher_setkey
  - crypto/skcipher.c:crypto_skcipher_setkey
```
```
In crypto/ahash.c (ffffffff81787682)
Location: include/linux/crypto.h:480
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_init_tfm
  - crypto/ahash.c:crypto_ahash_init_tfm
  - crypto/ahash.c:crypto_ahash_setkey
  - crypto/ahash.c:crypto_ahash_setkey
```
```
In crypto/shash.c (ffffffff817888c2)
Location: include/linux/crypto.h:480
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_init_tfm
  - crypto/shash.c:crypto_shash_setkey
```
```
In crypto/ecb.c (ffffffff817925ac)
Location: include/linux/crypto.h:480
Inline: True
Inline callers:
  - crypto/ecb.c:lskcipher_setkey_simple2
```
```
In crypto/cts.c (ffffffff8179325c)
Location: include/linux/crypto.h:480
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_setkey
```
```
In crypto/xts.c (ffffffff81794243)
Location: include/linux/crypto.h:480
Inline: True
```
```
In crypto/ctr.c (ffffffff81794a6d)
Location: include/linux/crypto.h:480
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_setkey
```
```
In crypto/gcm.c (ffffffff817956bd)
Location: include/linux/crypto.h:480
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_setkey
  - crypto/gcm.c:crypto_rfc4106_setkey
  - crypto/gcm.c:crypto_gcm_setkey
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In block/blk-crypto-fallback.c (ffffffff8180a681)
Location: include/linux/crypto.h:480
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
Location: include/linux/crypto.h:873
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_allocate_skcipher
```
```
In fs/crypto/keysetup_v1.c (ffff80001040f620)
Location: include/linux/crypto.h:873
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffff8000104f8bf8)
Location: include/linux/crypto.h:873
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_ctx
```
```
In crypto/aead.c (ffff8000105bb644)
Location: include/linux/crypto.h:873
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_init_tfm
  - crypto/aead.c:crypto_aead_setkey
```
```
In crypto/ablkcipher.c (ffff8000105bc558)
Location: include/linux/crypto.h:873
Inline: True
Inline callers:
  - crypto/ablkcipher.c:setkey
```
```
In crypto/skcipher.c (ffff8000105bdd2c)
Location: include/linux/crypto.h:873
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_simple
  - crypto/skcipher.c:skcipher_setkey_simple
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/skcipher.c:skcipher_setkey
  - crypto/skcipher.c:skcipher_setkey
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
  - crypto/skcipher.c:skcipher_setkey_blkcipher
  - crypto/skcipher.c:skcipher_setkey_blkcipher
  - crypto/skcipher.c:skcipher_setkey_blkcipher
```
```
In crypto/ahash.c (ffff8000105c04b4)
Location: include/linux/crypto.h:873
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_init_tfm
  - crypto/ahash.c:crypto_ahash_setkey
```
```
In crypto/shash.c (ffff8000105c0f34)
Location: include/linux/crypto.h:873
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_init_tfm
  - crypto/shash.c:crypto_init_shash_ops_async
  - crypto/shash.c:crypto_shash_setkey
```
```
In crypto/cts.c (ffff8000105c957c)
Location: include/linux/crypto.h:873
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_setkey
  - crypto/cts.c:crypto_cts_setkey
```
```
In crypto/xts.c (ffff8000105cab4c)
Location: include/linux/crypto.h:873
Inline: True
```
```
In crypto/ctr.c (ffff8000105cabfc)
Location: include/linux/crypto.h:873
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_setkey
  - crypto/ctr.c:crypto_rfc3686_setkey
```
```
In crypto/gcm.c (ffff8000105cb770)
Location: include/linux/crypto.h:873
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_setkey
  - crypto/gcm.c:crypto_rfc4543_setkey
  - crypto/gcm.c:crypto_rfc4106_setkey
  - crypto/gcm.c:crypto_rfc4106_setkey
  - crypto/gcm.c:crypto_gcm_setkey
  - crypto/gcm.c:crypto_gcm_setkey
  - crypto/gcm.c:crypto_gcm_setkey
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/crc32c_generic.c (ffff8000105cf770)
Location: include/linux/crypto.h:873
Inline: True
Inline callers:
  - crypto/crc32c_generic.c:chksum_setkey
```
```
In crypto/ghash-generic.c (ffff8000105d41f8)
Location: include/linux/crypto.h:873
Inline: True
Inline callers:
  - crypto/ghash-generic.c:ghash_setkey
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
Location: include/linux/crypto.h:873
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_allocate_skcipher
```
```
In fs/crypto/keysetup_v1.c (c05dc2fc)
Location: include/linux/crypto.h:873
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
```
```
In fs/ecryptfs/crypto.c (c06b64a4)
Location: include/linux/crypto.h:873
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_ctx
```
```
In crypto/aead.c (c076989c)
Location: include/linux/crypto.h:873
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_init_tfm
  - crypto/aead.c:crypto_aead_setkey
```
```
In crypto/ablkcipher.c (c076ab14)
Location: include/linux/crypto.h:873
Inline: True
Inline callers:
  - crypto/ablkcipher.c:setkey
```
```
In crypto/skcipher.c (c076bb70)
Location: include/linux/crypto.h:873
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_simple
  - crypto/skcipher.c:skcipher_setkey_simple
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/skcipher.c:skcipher_setkey
  - crypto/skcipher.c:skcipher_setkey
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
  - crypto/skcipher.c:skcipher_setkey_blkcipher
  - crypto/skcipher.c:skcipher_setkey_blkcipher
  - crypto/skcipher.c:skcipher_setkey_blkcipher
```
```
In crypto/ahash.c (c076e010)
Location: include/linux/crypto.h:873
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_init_tfm
  - crypto/ahash.c:crypto_ahash_setkey
```
```
In crypto/shash.c (c076e860)
Location: include/linux/crypto.h:873
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_init_tfm
  - crypto/shash.c:crypto_init_shash_ops_async
  - crypto/shash.c:crypto_shash_setkey
```
```
In crypto/cts.c (c0777148)
Location: include/linux/crypto.h:873
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_setkey
  - crypto/cts.c:crypto_cts_setkey
```
```
In crypto/xts.c (c0778734)
Location: include/linux/crypto.h:873
Inline: True
```
```
In crypto/ctr.c (c07787cc)
Location: include/linux/crypto.h:873
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_setkey
  - crypto/ctr.c:crypto_rfc3686_setkey
```
```
In crypto/gcm.c (c07791dc)
Location: include/linux/crypto.h:873
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_setkey
  - crypto/gcm.c:crypto_rfc4543_setkey
  - crypto/gcm.c:crypto_rfc4106_setkey
  - crypto/gcm.c:crypto_rfc4106_setkey
  - crypto/gcm.c:crypto_gcm_setkey
  - crypto/gcm.c:crypto_gcm_setkey
  - crypto/gcm.c:crypto_gcm_setkey
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/crc32c_generic.c (c077d48c)
Location: include/linux/crypto.h:873
Inline: True
Inline callers:
  - crypto/crc32c_generic.c:chksum_setkey
```
```
In crypto/ghash-generic.c (c0781cf4)
Location: include/linux/crypto.h:873
Inline: True
Inline callers:
  - crypto/ghash-generic.c:ghash_setkey
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
Location: include/linux/crypto.h:873
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_allocate_skcipher
```
```
In fs/crypto/keysetup_v1.c (c00000000051d0b8)
Location: include/linux/crypto.h:873
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (c00000000063aa50)
Location: include/linux/crypto.h:873
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_ctx
```
```
In crypto/aead.c (c000000000741f38)
Location: include/linux/crypto.h:873
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_init_tfm
  - crypto/aead.c:crypto_aead_setkey
```
```
In crypto/ablkcipher.c (c000000000743bd0)
Location: include/linux/crypto.h:873
Inline: True
Inline callers:
  - crypto/ablkcipher.c:setkey
```
```
In crypto/skcipher.c (c000000000745218)
Location: include/linux/crypto.h:873
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_simple
  - crypto/skcipher.c:skcipher_setkey_simple
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/skcipher.c:skcipher_setkey
  - crypto/skcipher.c:skcipher_setkey
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
  - crypto/skcipher.c:skcipher_setkey_blkcipher
  - crypto/skcipher.c:skcipher_setkey_blkcipher
  - crypto/skcipher.c:skcipher_setkey_blkcipher
```
```
In crypto/ahash.c (c00000000074854c)
Location: include/linux/crypto.h:873
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_init_tfm
  - crypto/ahash.c:crypto_ahash_setkey
```
```
In crypto/shash.c (c00000000074929c)
Location: include/linux/crypto.h:873
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_init_tfm
  - crypto/shash.c:crypto_init_shash_ops_async
  - crypto/shash.c:crypto_shash_setkey
```
```
In crypto/cts.c (c000000000753ba8)
Location: include/linux/crypto.h:873
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_setkey
  - crypto/cts.c:crypto_cts_setkey
```
```
In crypto/xts.c (c0000000007554f0)
Location: include/linux/crypto.h:873
Inline: True
```
```
In crypto/ctr.c (c0000000007559d8)
Location: include/linux/crypto.h:873
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_setkey
  - crypto/ctr.c:crypto_rfc3686_setkey
```
```
In crypto/gcm.c (c000000000756814)
Location: include/linux/crypto.h:873
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_setkey
  - crypto/gcm.c:crypto_rfc4543_setkey
  - crypto/gcm.c:crypto_rfc4106_setkey
  - crypto/gcm.c:crypto_rfc4106_setkey
  - crypto/gcm.c:crypto_gcm_setkey
  - crypto/gcm.c:crypto_gcm_setkey
  - crypto/gcm.c:crypto_gcm_setkey
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/crc32c_generic.c (c00000000075b7b0)
Location: include/linux/crypto.h:873
Inline: True
Inline callers:
  - crypto/crc32c_generic.c:chksum_setkey
```
```
In crypto/ghash-generic.c (c0000000007618d0)
Location: include/linux/crypto.h:873
Inline: True
Inline callers:
  - crypto/ghash-generic.c:ghash_setkey
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
Location: include/linux/crypto.h:873
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_allocate_skcipher
```
```
In fs/crypto/keysetup_v1.c (ffffffe0002b84ea)
Location: include/linux/crypto.h:873
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
```
```
In fs/ecryptfs/crypto.c (ffffffe0003674d2)
Location: include/linux/crypto.h:873
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_ctx
```
```
In crypto/aead.c (ffffffe0004010a4)
Location: include/linux/crypto.h:873
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_init_tfm
  - crypto/aead.c:crypto_aead_setkey
```
```
In crypto/ablkcipher.c (ffffffe000401e02)
Location: include/linux/crypto.h:873
Inline: True
Inline callers:
  - crypto/ablkcipher.c:setkey
```
```
In crypto/skcipher.c (ffffffe00040323c)
Location: include/linux/crypto.h:873
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_simple
  - crypto/skcipher.c:skcipher_setkey_simple
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/skcipher.c:skcipher_setkey
  - crypto/skcipher.c:skcipher_setkey
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
  - crypto/skcipher.c:skcipher_setkey_blkcipher
  - crypto/skcipher.c:skcipher_setkey_blkcipher
  - crypto/skcipher.c:skcipher_setkey_blkcipher
```
```
In crypto/ahash.c (ffffffe000405414)
Location: include/linux/crypto.h:873
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_init_tfm
  - crypto/ahash.c:crypto_ahash_setkey
```
```
In crypto/shash.c (ffffffe000405d30)
Location: include/linux/crypto.h:873
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_init_tfm
  - crypto/shash.c:crypto_init_shash_ops_async
  - crypto/shash.c:crypto_shash_setkey
```
```
In crypto/cts.c (ffffffe00040dd8e)
Location: include/linux/crypto.h:873
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_setkey
  - crypto/cts.c:crypto_cts_setkey
```
```
In crypto/xts.c (ffffffe00040ed34)
Location: include/linux/crypto.h:873
Inline: True
```
```
In crypto/ctr.c (ffffffe00040f0c6)
Location: include/linux/crypto.h:873
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_setkey
  - crypto/ctr.c:crypto_rfc3686_setkey
```
```
In crypto/gcm.c (ffffffe00040faa8)
Location: include/linux/crypto.h:873
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_setkey
  - crypto/gcm.c:crypto_rfc4543_setkey
  - crypto/gcm.c:crypto_rfc4106_setkey
  - crypto/gcm.c:crypto_rfc4106_setkey
  - crypto/gcm.c:crypto_gcm_setkey
  - crypto/gcm.c:crypto_gcm_setkey
  - crypto/gcm.c:crypto_gcm_setkey
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/crc32c_generic.c (ffffffe0004146a0)
Location: include/linux/crypto.h:873
Inline: True
Inline callers:
  - crypto/crc32c_generic.c:chksum_setkey
```
```
In crypto/ghash-generic.c (ffffffe00041852a)
Location: include/linux/crypto.h:873
Inline: True
Inline callers:
  - crypto/ghash-generic.c:ghash_setkey
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
In arch/x86/crypto/crc32c-intel_glue.c (ffffffff8108df97)
Location: include/linux/crypto.h:873
Inline: True
Inline callers:
  - arch/x86/crypto/crc32c-intel_glue.c:crc32c_intel_setkey
```
```
In fs/crypto/keysetup.c (ffffffff81345d2f)
Location: include/linux/crypto.h:873
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_allocate_skcipher
```
```
In fs/crypto/keysetup_v1.c (ffffffff813469ec)
Location: include/linux/crypto.h:873
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff8140f78a)
Location: include/linux/crypto.h:873
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_ctx
```
```
In crypto/aead.c (ffffffff814b9909)
Location: include/linux/crypto.h:873
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_init_tfm
  - crypto/aead.c:crypto_aead_setkey
```
```
In crypto/ablkcipher.c (ffffffff814bab1d)
Location: include/linux/crypto.h:873
Inline: True
Inline callers:
  - crypto/ablkcipher.c:setkey
```
```
In crypto/skcipher.c (ffffffff814bbad1)
Location: include/linux/crypto.h:873
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_simple
  - crypto/skcipher.c:skcipher_setkey_simple
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/skcipher.c:skcipher_setkey
  - crypto/skcipher.c:skcipher_setkey
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
  - crypto/skcipher.c:skcipher_setkey_blkcipher
  - crypto/skcipher.c:skcipher_setkey_blkcipher
  - crypto/skcipher.c:skcipher_setkey_blkcipher
```
```
In crypto/ahash.c (ffffffff814bdd80)
Location: include/linux/crypto.h:873
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_init_tfm
  - crypto/ahash.c:crypto_ahash_setkey
```
```
In crypto/shash.c (ffffffff814be513)
Location: include/linux/crypto.h:873
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_init_tfm
  - crypto/shash.c:crypto_init_shash_ops_async
  - crypto/shash.c:crypto_shash_setkey
```
```
In crypto/cts.c (ffffffff814c5ca3)
Location: include/linux/crypto.h:873
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_setkey
  - crypto/cts.c:crypto_cts_setkey
```
```
In crypto/xts.c (ffffffff814c6f0b)
Location: include/linux/crypto.h:873
Inline: True
```
```
In crypto/ctr.c (ffffffff814c72a4)
Location: include/linux/crypto.h:873
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_setkey
  - crypto/ctr.c:crypto_rfc3686_setkey
```
```
In crypto/gcm.c (ffffffff814c7cb4)
Location: include/linux/crypto.h:873
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_setkey
  - crypto/gcm.c:crypto_rfc4543_setkey
  - crypto/gcm.c:crypto_rfc4106_setkey
  - crypto/gcm.c:crypto_rfc4106_setkey
  - crypto/gcm.c:crypto_gcm_setkey
  - crypto/gcm.c:crypto_gcm_setkey
  - crypto/gcm.c:crypto_gcm_setkey
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/crc32c_generic.c (ffffffff814cb747)
Location: include/linux/crypto.h:873
Inline: True
Inline callers:
  - crypto/crc32c_generic.c:chksum_setkey
```
```
In crypto/ghash-generic.c (ffffffff814d09a6)
Location: include/linux/crypto.h:873
Inline: True
Inline callers:
  - crypto/ghash-generic.c:ghash_setkey
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
In arch/x86/crypto/crc32c-intel_glue.c (ffffffff8107caa7)
Location: include/linux/crypto.h:873
Inline: True
Inline callers:
  - arch/x86/crypto/crc32c-intel_glue.c:crc32c_intel_setkey
```
```
In fs/crypto/keysetup.c (ffffffff81336a0f)
Location: include/linux/crypto.h:873
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_allocate_skcipher
```
```
In fs/crypto/keysetup_v1.c (ffffffff813376cc)
Location: include/linux/crypto.h:873
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff8140020a)
Location: include/linux/crypto.h:873
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_ctx
```
```
In crypto/aead.c (ffffffff814aa329)
Location: include/linux/crypto.h:873
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_init_tfm
  - crypto/aead.c:crypto_aead_setkey
```
```
In crypto/ablkcipher.c (ffffffff814ab53d)
Location: include/linux/crypto.h:873
Inline: True
Inline callers:
  - crypto/ablkcipher.c:setkey
```
```
In crypto/skcipher.c (ffffffff814ac4f1)
Location: include/linux/crypto.h:873
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_simple
  - crypto/skcipher.c:skcipher_setkey_simple
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/skcipher.c:skcipher_setkey
  - crypto/skcipher.c:skcipher_setkey
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
  - crypto/skcipher.c:skcipher_setkey_blkcipher
  - crypto/skcipher.c:skcipher_setkey_blkcipher
  - crypto/skcipher.c:skcipher_setkey_blkcipher
```
```
In crypto/ahash.c (ffffffff814ae7a0)
Location: include/linux/crypto.h:873
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_init_tfm
  - crypto/ahash.c:crypto_ahash_setkey
```
```
In crypto/shash.c (ffffffff814aef33)
Location: include/linux/crypto.h:873
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_init_tfm
  - crypto/shash.c:crypto_init_shash_ops_async
  - crypto/shash.c:crypto_shash_setkey
```
```
In crypto/cts.c (ffffffff814b66c3)
Location: include/linux/crypto.h:873
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_setkey
  - crypto/cts.c:crypto_cts_setkey
```
```
In crypto/xts.c (ffffffff814b792b)
Location: include/linux/crypto.h:873
Inline: True
```
```
In crypto/ctr.c (ffffffff814b7cc4)
Location: include/linux/crypto.h:873
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_setkey
  - crypto/ctr.c:crypto_rfc3686_setkey
```
```
In crypto/gcm.c (ffffffff814b86d4)
Location: include/linux/crypto.h:873
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_setkey
  - crypto/gcm.c:crypto_rfc4543_setkey
  - crypto/gcm.c:crypto_rfc4106_setkey
  - crypto/gcm.c:crypto_rfc4106_setkey
  - crypto/gcm.c:crypto_gcm_setkey
  - crypto/gcm.c:crypto_gcm_setkey
  - crypto/gcm.c:crypto_gcm_setkey
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/crc32c_generic.c (ffffffff814bc167)
Location: include/linux/crypto.h:873
Inline: True
Inline callers:
  - crypto/crc32c_generic.c:chksum_setkey
```
```
In crypto/ghash-generic.c (ffffffff814c13c6)
Location: include/linux/crypto.h:873
Inline: True
Inline callers:
  - crypto/ghash-generic.c:ghash_setkey
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
In arch/x86/crypto/crc32c-intel_glue.c (ffffffff8108df47)
Location: include/linux/crypto.h:873
Inline: True
Inline callers:
  - arch/x86/crypto/crc32c-intel_glue.c:crc32c_intel_setkey
```
```
In fs/crypto/keysetup.c (ffffffff813437ff)
Location: include/linux/crypto.h:873
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_allocate_skcipher
```
```
In fs/crypto/keysetup_v1.c (ffffffff813444bc)
Location: include/linux/crypto.h:873
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff8140cb0a)
Location: include/linux/crypto.h:873
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_ctx
```
```
In crypto/aead.c (ffffffff814b5999)
Location: include/linux/crypto.h:873
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_init_tfm
  - crypto/aead.c:crypto_aead_setkey
```
```
In crypto/ablkcipher.c (ffffffff814b6bad)
Location: include/linux/crypto.h:873
Inline: True
Inline callers:
  - crypto/ablkcipher.c:setkey
```
```
In crypto/skcipher.c (ffffffff814b7b61)
Location: include/linux/crypto.h:873
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_simple
  - crypto/skcipher.c:skcipher_setkey_simple
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/skcipher.c:skcipher_setkey
  - crypto/skcipher.c:skcipher_setkey
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
  - crypto/skcipher.c:skcipher_setkey_blkcipher
  - crypto/skcipher.c:skcipher_setkey_blkcipher
  - crypto/skcipher.c:skcipher_setkey_blkcipher
```
```
In crypto/ahash.c (ffffffff814b9e10)
Location: include/linux/crypto.h:873
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_init_tfm
  - crypto/ahash.c:crypto_ahash_setkey
```
```
In crypto/shash.c (ffffffff814ba5a3)
Location: include/linux/crypto.h:873
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_init_tfm
  - crypto/shash.c:crypto_init_shash_ops_async
  - crypto/shash.c:crypto_shash_setkey
```
```
In crypto/cts.c (ffffffff814c1d33)
Location: include/linux/crypto.h:873
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_setkey
  - crypto/cts.c:crypto_cts_setkey
```
```
In crypto/xts.c (ffffffff814c2f9b)
Location: include/linux/crypto.h:873
Inline: True
```
```
In crypto/ctr.c (ffffffff814c3334)
Location: include/linux/crypto.h:873
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_setkey
  - crypto/ctr.c:crypto_rfc3686_setkey
```
```
In crypto/gcm.c (ffffffff814c3d44)
Location: include/linux/crypto.h:873
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_setkey
  - crypto/gcm.c:crypto_rfc4543_setkey
  - crypto/gcm.c:crypto_rfc4106_setkey
  - crypto/gcm.c:crypto_rfc4106_setkey
  - crypto/gcm.c:crypto_gcm_setkey
  - crypto/gcm.c:crypto_gcm_setkey
  - crypto/gcm.c:crypto_gcm_setkey
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/crc32c_generic.c (ffffffff814c77d7)
Location: include/linux/crypto.h:873
Inline: True
Inline callers:
  - crypto/crc32c_generic.c:chksum_setkey
```
```
In crypto/ghash-generic.c (ffffffff814cca36)
Location: include/linux/crypto.h:873
Inline: True
Inline callers:
  - crypto/ghash-generic.c:ghash_setkey
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
In arch/x86/crypto/crc32c-intel_glue.c (ffffffff81090327)
Location: include/linux/crypto.h:873
Inline: True
Inline callers:
  - arch/x86/crypto/crc32c-intel_glue.c:crc32c_intel_setkey
```
```
In fs/crypto/keysetup.c (ffffffff81356adf)
Location: include/linux/crypto.h:873
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_allocate_skcipher
```
```
In fs/crypto/keysetup_v1.c (ffffffff8135779c)
Location: include/linux/crypto.h:873
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff8142278a)
Location: include/linux/crypto.h:873
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_ctx
```
```
In crypto/aead.c (ffffffff814ce439)
Location: include/linux/crypto.h:873
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_init_tfm
  - crypto/aead.c:crypto_aead_setkey
```
```
In crypto/ablkcipher.c (ffffffff814cf63d)
Location: include/linux/crypto.h:873
Inline: True
Inline callers:
  - crypto/ablkcipher.c:setkey
```
```
In crypto/skcipher.c (ffffffff814d0641)
Location: include/linux/crypto.h:873
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_simple
  - crypto/skcipher.c:skcipher_setkey_simple
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/skcipher.c:skcipher_setkey
  - crypto/skcipher.c:skcipher_setkey
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
  - crypto/skcipher.c:skcipher_setkey_blkcipher
  - crypto/skcipher.c:skcipher_setkey_blkcipher
  - crypto/skcipher.c:skcipher_setkey_blkcipher
```
```
In crypto/ahash.c (ffffffff814d28c0)
Location: include/linux/crypto.h:873
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_init_tfm
  - crypto/ahash.c:crypto_ahash_setkey
```
```
In crypto/shash.c (ffffffff814d3053)
Location: include/linux/crypto.h:873
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_init_tfm
  - crypto/shash.c:crypto_init_shash_ops_async
  - crypto/shash.c:crypto_shash_setkey
```
```
In crypto/cts.c (ffffffff814da803)
Location: include/linux/crypto.h:873
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_setkey
  - crypto/cts.c:crypto_cts_setkey
```
```
In crypto/xts.c (ffffffff814dba6b)
Location: include/linux/crypto.h:873
Inline: True
```
```
In crypto/ctr.c (ffffffff814dbe04)
Location: include/linux/crypto.h:873
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_setkey
  - crypto/ctr.c:crypto_rfc3686_setkey
```
```
In crypto/gcm.c (ffffffff814dc814)
Location: include/linux/crypto.h:873
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_setkey
  - crypto/gcm.c:crypto_rfc4543_setkey
  - crypto/gcm.c:crypto_rfc4106_setkey
  - crypto/gcm.c:crypto_rfc4106_setkey
  - crypto/gcm.c:crypto_gcm_setkey
  - crypto/gcm.c:crypto_gcm_setkey
  - crypto/gcm.c:crypto_gcm_setkey
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/crc32c_generic.c (ffffffff814e02a7)
Location: include/linux/crypto.h:873
Inline: True
Inline callers:
  - crypto/crc32c_generic.c:chksum_setkey
```
```
In crypto/ghash-generic.c (ffffffff814e5506)
Location: include/linux/crypto.h:873
Inline: True
Inline callers:
  - crypto/ghash-generic.c:ghash_setkey
```
</details>
</li>
</ul>

## Differences
