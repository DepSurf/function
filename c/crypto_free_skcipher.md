# Function: <code>crypto_free_skcipher</code>

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
In fs/crypto/keyinfo.c (ffffffff8128a0af)
Location: include/crypto/skcipher.h:206
Inline: True
Inline callers:
  - fs/crypto/keyinfo.c:put_crypt_info
  - fs/crypto/keyinfo.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff8133ae71)
Location: include/crypto/skcipher.h:206
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_crypto
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_crypt_stat
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff81fc2eed)
Location: include/crypto/skcipher.h:206
Inline: True
```
```
In crypto/crypto_null.c (ffffffff813e2a05)
Location: include/crypto/skcipher.h:206
Inline: True
Inline callers:
  - crypto/crypto_null.c:crypto_put_default_null_skcipher
```
```
In crypto/cts.c (ffffffff813e7d8d)
Location: include/crypto/skcipher.h:206
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_exit_tfm
```
```
In crypto/ctr.c (ffffffff813e8c5d)
Location: include/crypto/skcipher.h:206
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_exit_tfm
```
```
In crypto/drbg.c (ffffffff813eb78f)
Location: include/crypto/skcipher.h:206
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
In fs/crypto/keyinfo.c (ffffffff8129ede6)
Location: include/crypto/skcipher.h:206
Inline: True
Inline callers:
  - fs/crypto/keyinfo.c:put_crypt_info
  - fs/crypto/keyinfo.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff81350c01)
Location: include/crypto/skcipher.h:206
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_crypto
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_crypt_stat
```
```
In security/keys/big_key.c (ffffffff81fff789)
Location: include/crypto/skcipher.h:206
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_init
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff81fff939)
Location: include/crypto/skcipher.h:206
Inline: True
```
```
In crypto/crypto_null.c (ffffffff813fba25)
Location: include/crypto/skcipher.h:206
Inline: True
Inline callers:
  - crypto/crypto_null.c:crypto_put_default_null_skcipher
```
```
In crypto/cts.c (ffffffff81400bbd)
Location: include/crypto/skcipher.h:206
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_exit_tfm
```
```
In crypto/xts.c (ffffffff814011f1)
Location: include/crypto/skcipher.h:206
Inline: True
Inline callers:
  - crypto/xts.c:exit_tfm
  - crypto/xts.c:init_tfm
```
```
In crypto/ctr.c (ffffffff8140226d)
Location: include/crypto/skcipher.h:206
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_exit_tfm
```
```
In crypto/drbg.c (ffffffff81404edf)
Location: include/crypto/skcipher.h:206
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
In fs/crypto/keyinfo.c (ffffffff812ad9f7)
Location: include/crypto/skcipher.h:210
Inline: True
Inline callers:
  - fs/crypto/keyinfo.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff81365721)
Location: include/crypto/skcipher.h:210
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_crypto
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_crypt_stat
```
```
In security/keys/big_key.c (ffffffff820e2a5c)
Location: include/crypto/skcipher.h:210
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_init
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff820e2bc7)
Location: include/crypto/skcipher.h:210
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
```
```
In crypto/crypto_null.c (ffffffff814084b5)
Location: include/crypto/skcipher.h:210
Inline: True
Inline callers:
  - crypto/crypto_null.c:crypto_put_default_null_skcipher
```
```
In crypto/cts.c (ffffffff8140db6d)
Location: include/crypto/skcipher.h:210
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_exit_tfm
```
```
In crypto/xts.c (ffffffff8140e681)
Location: include/crypto/skcipher.h:210
Inline: True
Inline callers:
  - crypto/xts.c:exit_tfm
  - crypto/xts.c:init_tfm
```
```
In crypto/ctr.c (ffffffff8140f38d)
Location: include/crypto/skcipher.h:210
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_exit_tfm
```
```
In crypto/drbg.c (ffffffff814126af)
Location: include/crypto/skcipher.h:210
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
In fs/crypto/keyinfo.c (ffffffff812d0ec3)
Location: include/crypto/skcipher.h:210
Inline: True
Inline callers:
  - fs/crypto/keyinfo.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff8138a3e1)
Location: include/crypto/skcipher.h:210
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_crypto
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_crypt_stat
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff826eb82d)
Location: include/crypto/skcipher.h:210
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
```
```
In crypto/crypto_null.c (ffffffff81430ed5)
Location: include/crypto/skcipher.h:210
Inline: True
Inline callers:
  - crypto/crypto_null.c:crypto_put_default_null_skcipher
```
```
In crypto/cts.c (ffffffff8143660d)
Location: include/crypto/skcipher.h:210
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_exit_tfm
```
```
In crypto/xts.c (ffffffff81437151)
Location: include/crypto/skcipher.h:210
Inline: True
Inline callers:
  - crypto/xts.c:exit_tfm
  - crypto/xts.c:init_tfm
```
```
In crypto/ctr.c (ffffffff81437d9d)
Location: include/crypto/skcipher.h:210
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_exit_tfm
```
```
In crypto/gcm.c (ffffffff81438c7e)
Location: include/crypto/skcipher.h:210
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_exit_tfm
```
```
In crypto/drbg.c (ffffffff8143ce3f)
Location: include/crypto/skcipher.h:210
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
In fs/crypto/keyinfo.c (ffffffff812fb946)
Location: include/crypto/skcipher.h:210
Inline: True
Inline callers:
  - fs/crypto/keyinfo.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff813b9171)
Location: include/crypto/skcipher.h:210
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_crypto
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_crypt_stat
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff82715d6c)
Location: include/crypto/skcipher.h:210
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
```
```
In crypto/crypto_null.c (ffffffff81463a53)
Location: include/crypto/skcipher.h:210
Inline: True
Inline callers:
  - crypto/crypto_null.c:crypto_put_default_null_skcipher
```
```
In crypto/cts.c (ffffffff8146917a)
Location: include/crypto/skcipher.h:210
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_exit_tfm
```
```
In crypto/xts.c (ffffffff81469981)
Location: include/crypto/skcipher.h:210
Inline: True
Inline callers:
  - crypto/xts.c:exit_tfm
  - crypto/xts.c:init_tfm
```
```
In crypto/ctr.c (ffffffff8146a6fa)
Location: include/crypto/skcipher.h:210
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_exit_tfm
```
```
In crypto/gcm.c (ffffffff8146af7e)
Location: include/crypto/skcipher.h:210
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_exit_tfm
```
```
In crypto/drbg.c (ffffffff8146fc2f)
Location: include/crypto/skcipher.h:210
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
In fs/crypto/keyinfo.c (ffffffff8131109e)
Location: include/crypto/skcipher.h:212
Inline: True
Inline callers:
  - fs/crypto/keyinfo.c:put_crypt_info
  - fs/crypto/keyinfo.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff813d26e1)
Location: include/crypto/skcipher.h:212
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_crypto
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_crypt_stat
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff828cd1ae)
Location: include/crypto/skcipher.h:212
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
```
```
In crypto/skcipher.c (ffffffff8147af71)
Location: include/crypto/skcipher.h:212
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_alloc_sync_skcipher
```
```
In crypto/crypto_null.c (ffffffff814816c3)
Location: include/crypto/skcipher.h:212
Inline: True
Inline callers:
  - crypto/crypto_null.c:crypto_put_default_null_skcipher
```
```
In crypto/cts.c (ffffffff81486b4a)
Location: include/crypto/skcipher.h:212
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_exit_tfm
```
```
In crypto/xts.c (ffffffff81487741)
Location: include/crypto/skcipher.h:212
Inline: True
Inline callers:
  - crypto/xts.c:exit_tfm
  - crypto/xts.c:init_tfm
```
```
In crypto/ctr.c (ffffffff81487f5a)
Location: include/crypto/skcipher.h:212
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_exit_tfm
```
```
In crypto/gcm.c (ffffffff8148887e)
Location: include/crypto/skcipher.h:212
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_exit_tfm
```
```
In crypto/drbg.c (ffffffff8148d60f)
Location: include/crypto/skcipher.h:212
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
In fs/crypto/keyinfo.c (ffffffff8133841d)
Location: include/crypto/skcipher.h:207
Inline: True
Inline callers:
  - fs/crypto/keyinfo.c:put_crypt_info
  - fs/crypto/keyinfo.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff813fd185)
Location: include/crypto/skcipher.h:207
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_crypto
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_crypt_stat
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff828e6bec)
Location: include/crypto/skcipher.h:207
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
```
```
In crypto/skcipher.c (ffffffff814aa0be)
Location: include/crypto/skcipher.h:207
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_alloc_sync_skcipher
```
```
In crypto/crypto_null.c (ffffffff814af923)
Location: include/crypto/skcipher.h:207
Inline: True
Inline callers:
  - crypto/crypto_null.c:crypto_put_default_null_skcipher
```
```
In crypto/cts.c (ffffffff814b4c6a)
Location: include/crypto/skcipher.h:207
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_exit_tfm
```
```
In crypto/xts.c (ffffffff814b5431)
Location: include/crypto/skcipher.h:207
Inline: True
Inline callers:
  - crypto/xts.c:exit_tfm
  - crypto/xts.c:init_tfm
```
```
In crypto/ctr.c (ffffffff814b5a7a)
Location: include/crypto/skcipher.h:207
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_exit_tfm
```
```
In crypto/gcm.c (ffffffff814b65be)
Location: include/crypto/skcipher.h:207
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_exit_tfm
```
```
In crypto/drbg.c (ffffffff814baf8f)
Location: include/crypto/skcipher.h:207
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
In fs/crypto/keyring.c (ffffffff8134c414)
Location: include/crypto/skcipher.h:207
Inline: True
Inline callers:
  - fs/crypto/keyring.c:free_master_key
```
```
In fs/crypto/keysetup.c (ffffffff8134d6b7)
Location: include/crypto/skcipher.h:207
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:put_crypt_info
  - fs/crypto/keysetup.c:setup_per_mode_key
  - fs/crypto/keysetup.c:fscrypt_allocate_skcipher
```
```
In fs/crypto/keysetup_v1.c (ffffffff8134e4cf)
Location: include/crypto/skcipher.h:207
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff81417065)
Location: include/crypto/skcipher.h:207
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_crypto
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_crypt_stat
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff828ef6d7)
Location: include/crypto/skcipher.h:207
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
```
```
In crypto/skcipher.c (ffffffff814c3c31)
Location: include/crypto/skcipher.h:207
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_alloc_sync_skcipher
```
```
In crypto/crypto_null.c (ffffffff814ca593)
Location: include/crypto/skcipher.h:207
Inline: True
Inline callers:
  - crypto/crypto_null.c:crypto_put_default_null_skcipher
```
```
In crypto/cts.c (ffffffff814cd73a)
Location: include/crypto/skcipher.h:207
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_exit_tfm
```
```
In crypto/xts.c (ffffffff814ce681)
Location: include/crypto/skcipher.h:207
Inline: True
Inline callers:
  - crypto/xts.c:exit_tfm
  - crypto/xts.c:init_tfm
```
```
In crypto/ctr.c (ffffffff814cec7a)
Location: include/crypto/skcipher.h:207
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_exit_tfm
```
```
In crypto/gcm.c (ffffffff814cf7de)
Location: include/crypto/skcipher.h:207
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_exit_tfm
```
```
In crypto/drbg.c (ffffffff814d3d5f)
Location: include/crypto/skcipher.h:207
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
In fs/crypto/keyring.c (ffffffff81391f74)
Location: include/crypto/skcipher.h:200
Inline: True
Inline callers:
  - fs/crypto/keyring.c:free_master_key
  - fs/crypto/keyring.c:free_master_key
  - fs/crypto/keyring.c:free_master_key
```
```
In fs/crypto/keysetup.c (ffffffff813933c9)
Location: include/crypto/skcipher.h:200
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:put_crypt_info
  - fs/crypto/keysetup.c:fscrypt_allocate_skcipher
```
```
In fs/crypto/keysetup_v1.c (ffffffff8139457e)
Location: include/crypto/skcipher.h:200
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_get_direct_key
  - fs/crypto/keysetup_v1.c:find_or_insert_direct_key
  - fs/crypto/keysetup_v1.c:fscrypt_put_direct_key
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff81465795)
Location: include/crypto/skcipher.h:200
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_crypto
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_crypt_stat
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff82d048e3)
Location: include/crypto/skcipher.h:200
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
```
```
In crypto/skcipher.c (ffffffff81522c00)
Location: include/crypto/skcipher.h:200
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_alloc_sync_skcipher
```
```
In crypto/crypto_null.c (ffffffff81529973)
Location: include/crypto/skcipher.h:200
Inline: True
Inline callers:
  - crypto/crypto_null.c:crypto_put_default_null_skcipher
```
```
In crypto/cts.c (ffffffff8152cb5a)
Location: include/crypto/skcipher.h:200
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_exit_tfm
```
```
In crypto/xts.c (ffffffff8152da81)
Location: include/crypto/skcipher.h:200
Inline: True
Inline callers:
  - crypto/xts.c:exit_tfm
  - crypto/xts.c:init_tfm
```
```
In crypto/ctr.c (ffffffff8152dfba)
Location: include/crypto/skcipher.h:200
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_exit_tfm
```
```
In crypto/gcm.c (ffffffff8152e9de)
Location: include/crypto/skcipher.h:200
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_exit_tfm
```
```
In crypto/drbg.c (ffffffff815330af)
Location: include/crypto/skcipher.h:200
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_fini_sym_kernel
```
```
In block/blk-crypto-fallback.c (ffffffff8158303c)
Location: include/crypto/skcipher.h:200
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
In fs/crypto/keysetup.c (ffffffff813a47c7)
Location: include/crypto/skcipher.h:200
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:put_crypt_info
  - fs/crypto/keysetup.c:fscrypt_allocate_skcipher
```
```
In fs/crypto/keysetup_v1.c (ffffffff813a572a)
Location: include/crypto/skcipher.h:200
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff81481035)
Location: include/crypto/skcipher.h:200
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_crypto
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_crypt_stat
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff82ff1cb0)
Location: include/crypto/skcipher.h:200
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
```
```
In crypto/skcipher.c (ffffffff8153fb56)
Location: include/crypto/skcipher.h:200
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_alloc_sync_skcipher
```
```
In crypto/crypto_null.c (ffffffff81546923)
Location: include/crypto/skcipher.h:200
Inline: True
Inline callers:
  - crypto/crypto_null.c:crypto_put_default_null_skcipher
```
```
In crypto/cts.c (ffffffff81549bca)
Location: include/crypto/skcipher.h:200
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_exit_tfm
```
```
In crypto/xts.c (ffffffff8154aa51)
Location: include/crypto/skcipher.h:200
Inline: True
Inline callers:
  - crypto/xts.c:xts_exit_tfm
  - crypto/xts.c:xts_init_tfm
```
```
In crypto/ctr.c (ffffffff8154af8a)
Location: include/crypto/skcipher.h:200
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_exit_tfm
```
```
In crypto/gcm.c (ffffffff8154b95e)
Location: include/crypto/skcipher.h:200
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_exit_tfm
```
```
In crypto/drbg.c (ffffffff8154ffff)
Location: include/crypto/skcipher.h:200
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_fini_sym_kernel
```
```
In block/blk-crypto-fallback.c (ffffffff8159fedc)
Location: include/crypto/skcipher.h:200
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
In fs/crypto/keysetup.c (ffffffff813ab907)
Location: include/crypto/skcipher.h:202
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:put_crypt_info
```
```
In fs/crypto/keysetup_v1.c (ffffffff813ac80a)
Location: include/crypto/skcipher.h:202
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff81486925)
Location: include/crypto/skcipher.h:202
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_crypto
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_crypt_stat
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff831fc63a)
Location: include/crypto/skcipher.h:202
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
```
```
In crypto/skcipher.c (ffffffff815480c6)
Location: include/crypto/skcipher.h:202
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_alloc_sync_skcipher
```
```
In crypto/crypto_null.c (ffffffff8154efe3)
Location: include/crypto/skcipher.h:202
Inline: True
Inline callers:
  - crypto/crypto_null.c:crypto_put_default_null_skcipher
```
```
In crypto/cts.c (ffffffff8155220a)
Location: include/crypto/skcipher.h:202
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_exit_tfm
```
```
In crypto/xts.c (ffffffff81553071)
Location: include/crypto/skcipher.h:202
Inline: True
Inline callers:
  - crypto/xts.c:xts_exit_tfm
  - crypto/xts.c:xts_init_tfm
```
```
In crypto/ctr.c (ffffffff815535aa)
Location: include/crypto/skcipher.h:202
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_exit_tfm
```
```
In crypto/gcm.c (ffffffff81553f5e)
Location: include/crypto/skcipher.h:202
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_exit_tfm
```
```
In crypto/drbg.c (ffffffff815587ff)
Location: include/crypto/skcipher.h:202
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_fini_sym_kernel
```
```
In block/blk-crypto-fallback.c (ffffffff815a6ccc)
Location: include/crypto/skcipher.h:202
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
In fs/crypto/keysetup.c (ffffffff813fb1a3)
Location: include/crypto/skcipher.h:202
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:put_crypt_info
```
```
In fs/crypto/keysetup_v1.c (ffffffff813fc17a)
Location: include/crypto/skcipher.h:202
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff814de0b5)
Location: include/crypto/skcipher.h:202
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_crypto
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_crypt_stat
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff832e368c)
Location: include/crypto/skcipher.h:202
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
```
```
In crypto/skcipher.c (ffffffff815a88a6)
Location: include/crypto/skcipher.h:202
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_alloc_sync_skcipher
```
```
In crypto/crypto_null.c (ffffffff815af933)
Location: include/crypto/skcipher.h:202
Inline: True
Inline callers:
  - crypto/crypto_null.c:crypto_put_default_null_skcipher
```
```
In crypto/cts.c (ffffffff815b320a)
Location: include/crypto/skcipher.h:202
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_exit_tfm
```
```
In crypto/xts.c (ffffffff815b40a1)
Location: include/crypto/skcipher.h:202
Inline: True
Inline callers:
  - crypto/xts.c:xts_exit_tfm
  - crypto/xts.c:xts_init_tfm
```
```
In crypto/ctr.c (ffffffff815b45da)
Location: include/crypto/skcipher.h:202
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_exit_tfm
```
```
In crypto/gcm.c (ffffffff815b4f8e)
Location: include/crypto/skcipher.h:202
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_exit_tfm
```
```
In crypto/drbg.c (ffffffff815b9aaf)
Location: include/crypto/skcipher.h:202
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_fini_sym_kernel
```
```
In block/blk-crypto-fallback.c (ffffffff8160f83f)
Location: include/crypto/skcipher.h:202
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
In fs/crypto/keysetup.c (ffffffff8146e4c9)
Location: include/crypto/skcipher.h:206
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:put_crypt_info
```
```
In fs/crypto/keysetup_v1.c (ffffffff8146f5f3)
Location: include/crypto/skcipher.h:206
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff8156c0a1)
Location: include/crypto/skcipher.h:206
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_crypto
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_crypt_stat
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff83499a9c)
Location: include/crypto/skcipher.h:206
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
```
```
In crypto/skcipher.c (ffffffff8164fc35)
Location: include/crypto/skcipher.h:206
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_alloc_sync_skcipher
```
```
In crypto/crypto_null.c (ffffffff8165814d)
Location: include/crypto/skcipher.h:206
Inline: True
Inline callers:
  - crypto/crypto_null.c:crypto_put_default_null_skcipher
```
```
In crypto/cts.c (ffffffff8165c1ea)
Location: include/crypto/skcipher.h:206
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_exit_tfm
```
```
In crypto/xts.c (ffffffff8165cee1)
Location: include/crypto/skcipher.h:206
Inline: True
Inline callers:
  - crypto/xts.c:xts_exit_tfm
  - crypto/xts.c:xts_init_tfm
```
```
In crypto/ctr.c (ffffffff8165d48a)
Location: include/crypto/skcipher.h:206
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_exit_tfm
```
```
In crypto/gcm.c (ffffffff8165dffe)
Location: include/crypto/skcipher.h:206
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_exit_tfm
```
```
In crypto/drbg.c (ffffffff8166307f)
Location: include/crypto/skcipher.h:206
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_fini_sym_kernel
```
```
In block/blk-crypto-fallback.c (ffffffff816c4191)
Location: include/crypto/skcipher.h:206
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
In fs/crypto/keysetup.c (ffffffff814ffb08)
Location: include/crypto/skcipher.h:206
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:put_crypt_info
```
```
In fs/crypto/keysetup_v1.c (ffffffff81500d73)
Location: include/crypto/skcipher.h:206
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff81610221)
Location: include/crypto/skcipher.h:206
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_crypto
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_crypt_stat
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff83ecfbca)
Location: include/crypto/skcipher.h:206
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
```
```
In crypto/skcipher.c (ffffffff817090a8)
Location: include/crypto/skcipher.h:206
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_alloc_sync_skcipher
```
```
In crypto/crypto_null.c (ffffffff817124dd)
Location: include/crypto/skcipher.h:206
Inline: True
Inline callers:
  - crypto/crypto_null.c:crypto_put_default_null_skcipher
```
```
In crypto/cts.c (ffffffff81715b9a)
Location: include/crypto/skcipher.h:206
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_exit_tfm
```
```
In crypto/xts.c (ffffffff81716991)
Location: include/crypto/skcipher.h:206
Inline: True
Inline callers:
  - crypto/xts.c:xts_exit_tfm
  - crypto/xts.c:xts_init_tfm
```
```
In crypto/ctr.c (ffffffff81716faa)
Location: include/crypto/skcipher.h:206
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_exit_tfm
```
```
In crypto/gcm.c (ffffffff8171793e)
Location: include/crypto/skcipher.h:206
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_exit_tfm
```
```
In crypto/drbg.c (ffffffff8171d2cf)
Location: include/crypto/skcipher.h:206
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_fini_sym_kernel
```
```
In block/blk-crypto-fallback.c (ffffffff81785697)
Location: include/crypto/skcipher.h:206
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
In fs/crypto/keysetup.c (ffffffff815370d8)
Location: include/crypto/skcipher.h:228
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:put_crypt_info
```
```
In fs/crypto/keysetup_v1.c (ffffffff81538400)
Location: include/crypto/skcipher.h:228
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff816480b1)
Location: include/crypto/skcipher.h:228
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_crypto
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_crypt_stat
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff836f4c88)
Location: include/crypto/skcipher.h:228
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
```
```
In crypto/skcipher.c (ffffffff817428f8)
Location: include/crypto/skcipher.h:228
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_alloc_sync_skcipher
```
```
In crypto/crypto_null.c (ffffffff8174d17d)
Location: include/crypto/skcipher.h:228
Inline: True
Inline callers:
  - crypto/crypto_null.c:crypto_put_default_null_skcipher
```
```
In crypto/cts.c (ffffffff8175144a)
Location: include/crypto/skcipher.h:228
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_exit_tfm
```
```
In crypto/xts.c (ffffffff81752241)
Location: include/crypto/skcipher.h:228
Inline: True
Inline callers:
  - crypto/xts.c:xts_exit_tfm
  - crypto/xts.c:xts_init_tfm
```
```
In crypto/ctr.c (ffffffff817528aa)
Location: include/crypto/skcipher.h:228
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_exit_tfm
```
```
In crypto/gcm.c (ffffffff8175331e)
Location: include/crypto/skcipher.h:228
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_exit_tfm
```
```
In crypto/drbg.c (ffffffff81758b5f)
Location: include/crypto/skcipher.h:228
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_fini_sym_kernel
```
```
In block/blk-crypto-fallback.c (ffffffff817c5a3e)
Location: include/crypto/skcipher.h:228
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
In fs/crypto/keysetup.c (ffffffff8156c1a8)
Location: include/crypto/skcipher.h:345
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:put_crypt_info
```
```
In fs/crypto/keysetup_v1.c (ffffffff8156d550)
Location: include/crypto/skcipher.h:345
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff81681561)
Location: include/crypto/skcipher.h:345
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_crypto
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_crypt_stat
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff83927e88)
Location: include/crypto/skcipher.h:345
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
```
```
In crypto/skcipher.c (ffffffff81784be8)
Location: include/crypto/skcipher.h:345
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_alloc_sync_skcipher
```
```
In crypto/crypto_null.c (ffffffff8178edcd)
Location: include/crypto/skcipher.h:345
Inline: True
Inline callers:
  - crypto/crypto_null.c:crypto_put_default_null_skcipher
```
```
In crypto/cts.c (ffffffff8179329a)
Location: include/crypto/skcipher.h:345
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_exit_tfm
```
```
In crypto/xts.c (ffffffff817940c1)
Location: include/crypto/skcipher.h:345
Inline: True
Inline callers:
  - crypto/xts.c:xts_exit_tfm
  - crypto/xts.c:xts_init_tfm
```
```
In crypto/ctr.c (ffffffff8179481a)
Location: include/crypto/skcipher.h:345
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_exit_tfm
```
```
In crypto/gcm.c (ffffffff817951ee)
Location: include/crypto/skcipher.h:345
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_exit_tfm
```
```
In crypto/drbg.c (ffffffff8179aa5f)
Location: include/crypto/skcipher.h:345
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_fini_sym_kernel
```
```
In block/blk-crypto-fallback.c (ffffffff8180a72e)
Location: include/crypto/skcipher.h:345
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
In fs/crypto/keyring.c (ffff80001040cfac)
Location: include/crypto/skcipher.h:207
Inline: True
Inline callers:
  - fs/crypto/keyring.c:free_master_key
```
```
In fs/crypto/keysetup.c (ffff80001040e72c)
Location: include/crypto/skcipher.h:207
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:put_crypt_info
  - fs/crypto/keysetup.c:setup_per_mode_key
  - fs/crypto/keysetup.c:fscrypt_allocate_skcipher
```
```
In fs/crypto/keysetup_v1.c (ffff80001040f6e4)
Location: include/crypto/skcipher.h:207
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffff8000104f8ab8)
Location: include/crypto/skcipher.h:207
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_crypto
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_crypt_stat
```
```
In security/keys/encrypted-keys/encrypted.c (ffff8000114693b8)
Location: include/crypto/skcipher.h:207
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
```
```
In crypto/skcipher.c (ffff8000105be65c)
Location: include/crypto/skcipher.h:207
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_alloc_sync_skcipher
```
```
In crypto/crypto_null.c (ffff8000105c6314)
Location: include/crypto/skcipher.h:207
Inline: True
Inline callers:
  - crypto/crypto_null.c:crypto_put_default_null_skcipher
```
```
In crypto/cts.c (ffff8000105c961c)
Location: include/crypto/skcipher.h:207
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_exit_tfm
```
```
In crypto/xts.c (ffff8000105ca51c)
Location: include/crypto/skcipher.h:207
Inline: True
Inline callers:
  - crypto/xts.c:exit_tfm
  - crypto/xts.c:init_tfm
```
```
In crypto/ctr.c (ffff8000105cab94)
Location: include/crypto/skcipher.h:207
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_exit_tfm
```
```
In crypto/gcm.c (ffff8000105cb8d0)
Location: include/crypto/skcipher.h:207
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_exit_tfm
```
```
In crypto/drbg.c (ffff8000105d07ec)
Location: include/crypto/skcipher.h:207
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
In fs/crypto/keyring.c (c05d9fb8)
Location: include/crypto/skcipher.h:207
Inline: True
Inline callers:
  - fs/crypto/keyring.c:free_master_key
```
```
In fs/crypto/keysetup.c (c05db204)
Location: include/crypto/skcipher.h:207
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:put_crypt_info
  - fs/crypto/keysetup.c:setup_per_mode_key
  - fs/crypto/keysetup.c:fscrypt_allocate_skcipher
```
```
In fs/crypto/keysetup_v1.c (c05dc3cc)
Location: include/crypto/skcipher.h:207
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
```
```
In fs/ecryptfs/crypto.c (c06b636c)
Location: include/crypto/skcipher.h:207
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_crypto
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_crypt_stat
```
```
In security/keys/encrypted-keys/encrypted.c (c1541ef8)
Location: include/crypto/skcipher.h:207
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
```
```
In crypto/skcipher.c (c076c384)
Location: include/crypto/skcipher.h:207
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_alloc_sync_skcipher
```
```
In crypto/crypto_null.c (c0772fe0)
Location: include/crypto/skcipher.h:207
Inline: True
Inline callers:
  - crypto/crypto_null.c:crypto_put_default_null_skcipher
```
```
In crypto/cts.c (c07771c0)
Location: include/crypto/skcipher.h:207
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_exit_tfm
```
```
In crypto/xts.c (c077814c)
Location: include/crypto/skcipher.h:207
Inline: True
Inline callers:
  - crypto/xts.c:exit_tfm
  - crypto/xts.c:init_tfm
```
```
In crypto/ctr.c (c0778770)
Location: include/crypto/skcipher.h:207
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_exit_tfm
```
```
In crypto/gcm.c (c077930c)
Location: include/crypto/skcipher.h:207
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_exit_tfm
```
```
In crypto/drbg.c (c077e18c)
Location: include/crypto/skcipher.h:207
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
In fs/crypto/keyring.c (c00000000051a3d4)
Location: include/crypto/skcipher.h:207
Inline: True
Inline callers:
  - fs/crypto/keyring.c:free_master_key
```
```
In fs/crypto/keysetup.c (c00000000051bcfc)
Location: include/crypto/skcipher.h:207
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:put_crypt_info
  - fs/crypto/keysetup.c:setup_per_mode_key
  - fs/crypto/keysetup.c:fscrypt_allocate_skcipher
```
```
In fs/crypto/keysetup_v1.c (c00000000051d1a4)
Location: include/crypto/skcipher.h:207
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (c00000000063a858)
Location: include/crypto/skcipher.h:207
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_crypto
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_crypt_stat
```
```
In security/keys/encrypted-keys/encrypted.c (c000000001397528)
Location: include/crypto/skcipher.h:207
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
```
```
In crypto/skcipher.c (c000000000745e58)
Location: include/crypto/skcipher.h:207
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_alloc_sync_skcipher
```
```
In crypto/crypto_null.c (c00000000074febc)
Location: include/crypto/skcipher.h:207
Inline: True
Inline callers:
  - crypto/crypto_null.c:crypto_put_default_null_skcipher
```
```
In crypto/cts.c (c000000000753c60)
Location: include/crypto/skcipher.h:207
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_exit_tfm
```
```
In crypto/xts.c (c0000000007550a8)
Location: include/crypto/skcipher.h:207
Inline: True
Inline callers:
  - crypto/xts.c:exit_tfm
  - crypto/xts.c:init_tfm
```
```
In crypto/ctr.c (c000000000755960)
Location: include/crypto/skcipher.h:207
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_exit_tfm
```
```
In crypto/gcm.c (c0000000007569e8)
Location: include/crypto/skcipher.h:207
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_exit_tfm
```
```
In crypto/drbg.c (c00000000075cb94)
Location: include/crypto/skcipher.h:207
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
In fs/crypto/keyring.c (ffffffe0002b64e0)
Location: include/crypto/skcipher.h:207
Inline: True
Inline callers:
  - fs/crypto/keyring.c:free_master_key
```
```
In fs/crypto/keysetup.c (ffffffe0002b77ca)
Location: include/crypto/skcipher.h:207
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:put_crypt_info
  - fs/crypto/keysetup.c:setup_per_mode_key
  - fs/crypto/keysetup.c:fscrypt_allocate_skcipher
```
```
In fs/crypto/keysetup_v1.c (ffffffe0002b859a)
Location: include/crypto/skcipher.h:207
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
```
```
In fs/ecryptfs/crypto.c (ffffffe00036739c)
Location: include/crypto/skcipher.h:207
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_crypto
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_crypt_stat
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffe000024602)
Location: include/crypto/skcipher.h:207
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
```
```
In crypto/skcipher.c (ffffffe000403a50)
Location: include/crypto/skcipher.h:207
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_alloc_sync_skcipher
```
```
In crypto/crypto_null.c (ffffffe00040a384)
Location: include/crypto/skcipher.h:207
Inline: True
Inline callers:
  - crypto/crypto_null.c:crypto_put_default_null_skcipher
```
```
In crypto/cts.c (ffffffe00040e2f2)
Location: include/crypto/skcipher.h:207
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_exit_tfm
```
```
In crypto/xts.c (ffffffe00040ea74)
Location: include/crypto/skcipher.h:207
Inline: True
Inline callers:
  - crypto/xts.c:exit_tfm
  - crypto/xts.c:init_tfm
```
```
In crypto/ctr.c (ffffffe00040f048)
Location: include/crypto/skcipher.h:207
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_exit_tfm
```
```
In crypto/gcm.c (ffffffe00040fc1e)
Location: include/crypto/skcipher.h:207
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_exit_tfm
```
```
In crypto/drbg.c (ffffffe00041543e)
Location: include/crypto/skcipher.h:207
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
In fs/crypto/keyring.c (ffffffff813449f4)
Location: include/crypto/skcipher.h:207
Inline: True
Inline callers:
  - fs/crypto/keyring.c:free_master_key
```
```
In fs/crypto/keysetup.c (ffffffff81345c97)
Location: include/crypto/skcipher.h:207
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:put_crypt_info
  - fs/crypto/keysetup.c:setup_per_mode_key
  - fs/crypto/keysetup.c:fscrypt_allocate_skcipher
```
```
In fs/crypto/keysetup_v1.c (ffffffff81346aaf)
Location: include/crypto/skcipher.h:207
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff8140f645)
Location: include/crypto/skcipher.h:207
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_crypto
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_crypt_stat
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff828d858b)
Location: include/crypto/skcipher.h:207
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
```
```
In crypto/skcipher.c (ffffffff814bc211)
Location: include/crypto/skcipher.h:207
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_alloc_sync_skcipher
```
```
In crypto/crypto_null.c (ffffffff814c2b73)
Location: include/crypto/skcipher.h:207
Inline: True
Inline callers:
  - crypto/crypto_null.c:crypto_put_default_null_skcipher
```
```
In crypto/cts.c (ffffffff814c5d1a)
Location: include/crypto/skcipher.h:207
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_exit_tfm
```
```
In crypto/xts.c (ffffffff814c6c61)
Location: include/crypto/skcipher.h:207
Inline: True
Inline callers:
  - crypto/xts.c:exit_tfm
  - crypto/xts.c:init_tfm
```
```
In crypto/ctr.c (ffffffff814c725a)
Location: include/crypto/skcipher.h:207
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_exit_tfm
```
```
In crypto/gcm.c (ffffffff814c7dbe)
Location: include/crypto/skcipher.h:207
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_exit_tfm
```
```
In crypto/drbg.c (ffffffff814cc33f)
Location: include/crypto/skcipher.h:207
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
In fs/crypto/keyring.c (ffffffff813356d4)
Location: include/crypto/skcipher.h:207
Inline: True
Inline callers:
  - fs/crypto/keyring.c:free_master_key
```
```
In fs/crypto/keysetup.c (ffffffff81336977)
Location: include/crypto/skcipher.h:207
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:put_crypt_info
  - fs/crypto/keysetup.c:setup_per_mode_key
  - fs/crypto/keysetup.c:fscrypt_allocate_skcipher
```
```
In fs/crypto/keysetup_v1.c (ffffffff8133778f)
Location: include/crypto/skcipher.h:207
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff814000c5)
Location: include/crypto/skcipher.h:207
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_crypto
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_crypt_stat
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff828d0ca7)
Location: include/crypto/skcipher.h:207
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
```
```
In crypto/skcipher.c (ffffffff814acc31)
Location: include/crypto/skcipher.h:207
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_alloc_sync_skcipher
```
```
In crypto/crypto_null.c (ffffffff814b3593)
Location: include/crypto/skcipher.h:207
Inline: True
Inline callers:
  - crypto/crypto_null.c:crypto_put_default_null_skcipher
```
```
In crypto/cts.c (ffffffff814b673a)
Location: include/crypto/skcipher.h:207
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_exit_tfm
```
```
In crypto/xts.c (ffffffff814b7681)
Location: include/crypto/skcipher.h:207
Inline: True
Inline callers:
  - crypto/xts.c:exit_tfm
  - crypto/xts.c:init_tfm
```
```
In crypto/ctr.c (ffffffff814b7c7a)
Location: include/crypto/skcipher.h:207
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_exit_tfm
```
```
In crypto/gcm.c (ffffffff814b87de)
Location: include/crypto/skcipher.h:207
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_exit_tfm
```
```
In crypto/drbg.c (ffffffff814bcd5f)
Location: include/crypto/skcipher.h:207
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
In fs/crypto/keyring.c (ffffffff813424c4)
Location: include/crypto/skcipher.h:207
Inline: True
Inline callers:
  - fs/crypto/keyring.c:free_master_key
```
```
In fs/crypto/keysetup.c (ffffffff81343767)
Location: include/crypto/skcipher.h:207
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:put_crypt_info
  - fs/crypto/keysetup.c:setup_per_mode_key
  - fs/crypto/keysetup.c:fscrypt_allocate_skcipher
```
```
In fs/crypto/keysetup_v1.c (ffffffff8134457f)
Location: include/crypto/skcipher.h:207
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff8140c9c5)
Location: include/crypto/skcipher.h:207
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_crypto
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_crypt_stat
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff828eb30b)
Location: include/crypto/skcipher.h:207
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
```
```
In crypto/skcipher.c (ffffffff814b82a1)
Location: include/crypto/skcipher.h:207
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_alloc_sync_skcipher
```
```
In crypto/crypto_null.c (ffffffff814bec03)
Location: include/crypto/skcipher.h:207
Inline: True
Inline callers:
  - crypto/crypto_null.c:crypto_put_default_null_skcipher
```
```
In crypto/cts.c (ffffffff814c1daa)
Location: include/crypto/skcipher.h:207
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_exit_tfm
```
```
In crypto/xts.c (ffffffff814c2cf1)
Location: include/crypto/skcipher.h:207
Inline: True
Inline callers:
  - crypto/xts.c:exit_tfm
  - crypto/xts.c:init_tfm
```
```
In crypto/ctr.c (ffffffff814c32ea)
Location: include/crypto/skcipher.h:207
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_exit_tfm
```
```
In crypto/gcm.c (ffffffff814c3e4e)
Location: include/crypto/skcipher.h:207
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_exit_tfm
```
```
In crypto/drbg.c (ffffffff814c83cf)
Location: include/crypto/skcipher.h:207
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
In fs/crypto/keyring.c (ffffffff813557c4)
Location: include/crypto/skcipher.h:207
Inline: True
Inline callers:
  - fs/crypto/keyring.c:free_master_key
```
```
In fs/crypto/keysetup.c (ffffffff81356a05)
Location: include/crypto/skcipher.h:207
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:put_crypt_info
  - fs/crypto/keysetup.c:setup_per_mode_key
  - fs/crypto/keysetup.c:fscrypt_allocate_skcipher
```
```
In fs/crypto/keysetup_v1.c (ffffffff8135785f)
Location: include/crypto/skcipher.h:207
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff81422645)
Location: include/crypto/skcipher.h:207
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_crypto
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_crypt_stat
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff828f0721)
Location: include/crypto/skcipher.h:207
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
```
```
In crypto/skcipher.c (ffffffff814d0d81)
Location: include/crypto/skcipher.h:207
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_alloc_sync_skcipher
```
```
In crypto/crypto_null.c (ffffffff814d76d3)
Location: include/crypto/skcipher.h:207
Inline: True
Inline callers:
  - crypto/crypto_null.c:crypto_put_default_null_skcipher
```
```
In crypto/cts.c (ffffffff814da87a)
Location: include/crypto/skcipher.h:207
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_exit_tfm
```
```
In crypto/xts.c (ffffffff814db7c1)
Location: include/crypto/skcipher.h:207
Inline: True
Inline callers:
  - crypto/xts.c:exit_tfm
  - crypto/xts.c:init_tfm
```
```
In crypto/ctr.c (ffffffff814dbdba)
Location: include/crypto/skcipher.h:207
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_exit_tfm
```
```
In crypto/gcm.c (ffffffff814dc91e)
Location: include/crypto/skcipher.h:207
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_exit_tfm
```
```
In crypto/drbg.c (ffffffff814e0e9f)
Location: include/crypto/skcipher.h:207
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_fini_sym_kernel
```
</details>
</li>
</ul>

## Differences
