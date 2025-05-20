# Function: <code>crypto_skcipher_get_flags</code>

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
In crypto/skcipher.c (0)
Location: include/crypto/skcipher.h:271
Inline: True
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
In crypto/skcipher.c (0)
Location: include/crypto/skcipher.h:331
Inline: True
```
```
In crypto/cts.c (0)
Location: include/crypto/skcipher.h:331
Inline: True
```
```
In crypto/ctr.c (0)
Location: include/crypto/skcipher.h:331
Inline: True
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
In crypto/skcipher.c (0)
Location: include/crypto/skcipher.h:331
Inline: True
```
```
In crypto/cbc.c (0)
Location: include/crypto/skcipher.h:331
Inline: True
```
```
In crypto/cts.c (0)
Location: include/crypto/skcipher.h:331
Inline: True
```
```
In crypto/xts.c (0)
Location: include/crypto/skcipher.h:331
Inline: True
```
```
In crypto/ctr.c (0)
Location: include/crypto/skcipher.h:331
Inline: True
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
In crypto/skcipher.c (0)
Location: include/crypto/skcipher.h:365
Inline: True
```
```
In crypto/cbc.c (0)
Location: include/crypto/skcipher.h:365
Inline: True
```
```
In crypto/cts.c (0)
Location: include/crypto/skcipher.h:365
Inline: True
```
```
In crypto/xts.c (0)
Location: include/crypto/skcipher.h:365
Inline: True
```
```
In crypto/ctr.c (0)
Location: include/crypto/skcipher.h:365
Inline: True
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
In crypto/skcipher.c (0)
Location: include/crypto/skcipher.h:365
Inline: True
```
```
In crypto/cbc.c (0)
Location: include/crypto/skcipher.h:365
Inline: True
```
```
In crypto/cts.c (0)
Location: include/crypto/skcipher.h:365
Inline: True
```
```
In crypto/xts.c (0)
Location: include/crypto/skcipher.h:365
Inline: True
```
```
In crypto/ctr.c (0)
Location: include/crypto/skcipher.h:365
Inline: True
```
```
In crypto/gcm.c (0)
Location: include/crypto/skcipher.h:365
Inline: True
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
In fs/crypto/crypto.c (ffffffff812fa523)
Location: include/crypto/skcipher.h:365
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_do_page_crypto
  - fs/crypto/crypto.c:fscrypt_do_page_crypto
```
```
In fs/crypto/fname.c (ffffffff812fae9d)
Location: include/crypto/skcipher.h:365
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_encrypt
```
```
In fs/crypto/keyinfo.c (ffffffff812fba28)
Location: include/crypto/skcipher.h:365
Inline: True
Inline callers:
  - fs/crypto/keyinfo.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff813b7a8f)
Location: include/crypto/skcipher.h:365
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/keystore.c (ffffffff813bab65)
Location: include/crypto/skcipher.h:365
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff813eff41)
Location: include/crypto/skcipher.h:365
Inline: True
```
```
In crypto/skcipher.c (ffffffff8145cee9)
Location: include/crypto/skcipher.h:365
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
  - crypto/skcipher.c:skcipher_setkey_blkcipher
```
```
In crypto/seqiv.c (ffffffff8145e740)
Location: include/crypto/skcipher.h:365
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/cbc.c (ffffffff8146883d)
Location: include/crypto/skcipher.h:365
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_setkey
```
```
In crypto/cts.c (ffffffff81469786)
Location: include/crypto/skcipher.h:365
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:cts_cbc_encrypt
  - crypto/cts.c:crypto_cts_setkey
  - crypto/cts.c:crypto_cts_setkey
```
```
In crypto/xts.c (ffffffff8146a3a3)
Location: include/crypto/skcipher.h:365
Inline: True
Inline callers:
  - crypto/xts.c:do_decrypt
  - crypto/xts.c:do_encrypt
```
```
In crypto/ctr.c (ffffffff8146a87d)
Location: include/crypto/skcipher.h:365
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_crypt
  - crypto/ctr.c:crypto_rfc3686_setkey
  - crypto/ctr.c:crypto_rfc3686_setkey
```
```
In crypto/gcm.c (ffffffff8146b349)
Location: include/crypto/skcipher.h:365
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:gcm_dec_hash_continue
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:crypto_gcm_setkey
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (ffffffff8146fd68)
Location: include/crypto/skcipher.h:365
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
In fs/crypto/crypto.c (ffffffff8130f8db)
Location: include/crypto/skcipher.h:384
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_do_page_crypto
  - fs/crypto/crypto.c:fscrypt_do_page_crypto
```
```
In fs/crypto/fname.c (ffffffff81310260)
Location: include/crypto/skcipher.h:384
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_encrypt
```
```
In fs/crypto/keyinfo.c (ffffffff81310f91)
Location: include/crypto/skcipher.h:384
Inline: True
Inline callers:
  - fs/crypto/keyinfo.c:derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff813d0ff0)
Location: include/crypto/skcipher.h:384
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/keystore.c (ffffffff813d414d)
Location: include/crypto/skcipher.h:384
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff8140b22d)
Location: include/crypto/skcipher.h:384
Inline: True
```
```
In crypto/skcipher.c (ffffffff8147a79b)
Location: include/crypto/skcipher.h:384
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
  - crypto/skcipher.c:skcipher_setkey_blkcipher
```
```
In crypto/seqiv.c (ffffffff8147c035)
Location: include/crypto/skcipher.h:384
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/cbc.c (ffffffff814864ad)
Location: include/crypto/skcipher.h:384
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_setkey
```
```
In crypto/cts.c (ffffffff814874ca)
Location: include/crypto/skcipher.h:384
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:cts_cbc_encrypt
  - crypto/cts.c:crypto_cts_setkey
  - crypto/cts.c:crypto_cts_setkey
```
```
In crypto/xts.c (ffffffff814878d6)
Location: include/crypto/skcipher.h:384
Inline: True
```
```
In crypto/ctr.c (ffffffff814880fa)
Location: include/crypto/skcipher.h:384
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_crypt
  - crypto/ctr.c:crypto_rfc3686_setkey
  - crypto/ctr.c:crypto_rfc3686_setkey
```
```
In crypto/gcm.c (ffffffff814895cc)
Location: include/crypto/skcipher.h:384
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_copy_src_to_dst
  - crypto/gcm.c:gcm_dec_hash_continue
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:crypto_gcm_setkey
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (ffffffff8149010f)
Location: include/crypto/skcipher.h:384
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
In crypto/skcipher.c (ffffffff814a8891)
Location: include/crypto/skcipher.h:319
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_simple
  - crypto/skcipher.c:crypto_skcipher_decrypt
  - crypto/skcipher.c:crypto_skcipher_encrypt
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
  - crypto/skcipher.c:skcipher_setkey_blkcipher
```
```
In crypto/cts.c (ffffffff814b4953)
Location: include/crypto/skcipher.h:319
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_setkey
  - crypto/cts.c:crypto_cts_setkey
```
```
In crypto/xts.c (ffffffff814b56a2)
Location: include/crypto/skcipher.h:319
Inline: True
```
```
In crypto/ctr.c (ffffffff814b5ac4)
Location: include/crypto/skcipher.h:319
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_setkey
  - crypto/ctr.c:crypto_rfc3686_setkey
```
```
In crypto/gcm.c (ffffffff814b6f89)
Location: include/crypto/skcipher.h:319
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
In crypto/skcipher.c (ffffffff814c34f1)
Location: include/crypto/skcipher.h:349
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_simple
  - crypto/skcipher.c:crypto_skcipher_decrypt
  - crypto/skcipher.c:crypto_skcipher_encrypt
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
  - crypto/skcipher.c:skcipher_setkey_blkcipher
```
```
In crypto/cts.c (ffffffff814cd6c3)
Location: include/crypto/skcipher.h:349
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_setkey
  - crypto/cts.c:crypto_cts_setkey
```
```
In crypto/xts.c (ffffffff814ce8a2)
Location: include/crypto/skcipher.h:349
Inline: True
```
```
In crypto/ctr.c (ffffffff814cecc4)
Location: include/crypto/skcipher.h:349
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_setkey
  - crypto/ctr.c:crypto_rfc3686_setkey
```
```
In crypto/gcm.c (ffffffff814d01a9)
Location: include/crypto/skcipher.h:349
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
In crypto/skcipher.c (ffffffff81522dbd)
Location: include/crypto/skcipher.h:311
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_simple
  - crypto/skcipher.c:crypto_skcipher_decrypt
  - crypto/skcipher.c:crypto_skcipher_encrypt
```
```
In crypto/cts.c (ffffffff8152cb2f)
Location: include/crypto/skcipher.h:311
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_setkey
```
```
In crypto/xts.c (ffffffff8152db7e)
Location: include/crypto/skcipher.h:311
Inline: True
```
```
In crypto/ctr.c (ffffffff8152e07c)
Location: include/crypto/skcipher.h:311
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_setkey
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
In crypto/skcipher.c (ffffffff8153fd0d)
Location: include/crypto/skcipher.h:311
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_simple
  - crypto/skcipher.c:crypto_skcipher_decrypt
  - crypto/skcipher.c:crypto_skcipher_encrypt
```
```
In crypto/cts.c (ffffffff81549b9f)
Location: include/crypto/skcipher.h:311
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_setkey
```
```
In crypto/xts.c (ffffffff8154ab4e)
Location: include/crypto/skcipher.h:311
Inline: True
```
```
In crypto/ctr.c (ffffffff8154b09c)
Location: include/crypto/skcipher.h:311
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_setkey
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
In crypto/skcipher.c (ffffffff8154827a)
Location: include/crypto/skcipher.h:313
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_simple
  - crypto/skcipher.c:crypto_skcipher_decrypt
  - crypto/skcipher.c:crypto_skcipher_encrypt
```
```
In crypto/cts.c (ffffffff815521ec)
Location: include/crypto/skcipher.h:313
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_setkey
```
```
In crypto/xts.c (ffffffff8155316e)
Location: include/crypto/skcipher.h:313
Inline: True
```
```
In crypto/ctr.c (ffffffff815536bc)
Location: include/crypto/skcipher.h:313
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_setkey
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
In crypto/skcipher.c (ffffffff815a8a5a)
Location: include/crypto/skcipher.h:313
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_simple
  - crypto/skcipher.c:crypto_skcipher_decrypt
  - crypto/skcipher.c:crypto_skcipher_encrypt
```
```
In crypto/cts.c (ffffffff815b31ec)
Location: include/crypto/skcipher.h:313
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_setkey
```
```
In crypto/xts.c (ffffffff815b419e)
Location: include/crypto/skcipher.h:313
Inline: True
```
```
In crypto/ctr.c (ffffffff815b46ec)
Location: include/crypto/skcipher.h:313
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_setkey
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
In crypto/skcipher.c (ffffffff8164fe4a)
Location: include/crypto/skcipher.h:317
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_simple
  - crypto/skcipher.c:crypto_skcipher_decrypt
  - crypto/skcipher.c:crypto_skcipher_encrypt
```
```
In crypto/cts.c (ffffffff8165c1bc)
Location: include/crypto/skcipher.h:317
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_setkey
```
```
In crypto/xts.c (ffffffff8165d001)
Location: include/crypto/skcipher.h:317
Inline: True
```
```
In crypto/ctr.c (ffffffff8165d5ad)
Location: include/crypto/skcipher.h:317
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_setkey
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
In crypto/skcipher.c (ffffffff8170932a)
Location: include/crypto/skcipher.h:317
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_simple
  - crypto/skcipher.c:crypto_skcipher_decrypt
  - crypto/skcipher.c:crypto_skcipher_encrypt
```
```
In crypto/cts.c (ffffffff81715b5c)
Location: include/crypto/skcipher.h:317
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_setkey
```
```
In crypto/xts.c (ffffffff81716ae1)
Location: include/crypto/skcipher.h:317
Inline: True
```
```
In crypto/ctr.c (ffffffff817171ed)
Location: include/crypto/skcipher.h:317
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_setkey
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
In crypto/skcipher.c (ffffffff81742b6c)
Location: include/crypto/skcipher.h:339
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_simple
  - crypto/skcipher.c:crypto_skcipher_decrypt
  - crypto/skcipher.c:crypto_skcipher_encrypt
```
```
In crypto/cts.c (ffffffff8175140c)
Location: include/crypto/skcipher.h:339
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_setkey
```
```
In crypto/xts.c (ffffffff81752391)
Location: include/crypto/skcipher.h:339
Inline: True
```
```
In crypto/ctr.c (ffffffff81752afd)
Location: include/crypto/skcipher.h:339
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_setkey
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
In crypto/skcipher.c (ffffffff81784dac)
Location: include/crypto/skcipher.h:564
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_simple
  - crypto/skcipher.c:crypto_skcipher_decrypt
  - crypto/skcipher.c:crypto_skcipher_encrypt
  - crypto/skcipher.c:crypto_skcipher_setkey
```
```
In crypto/cts.c (ffffffff8179325c)
Location: include/crypto/skcipher.h:564
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_setkey
```
```
In crypto/xts.c (ffffffff81794221)
Location: include/crypto/skcipher.h:564
Inline: True
```
```
In crypto/ctr.c (ffffffff81794a6d)
Location: include/crypto/skcipher.h:564
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_setkey
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
In crypto/skcipher.c (ffff8000105bdd2c)
Location: include/crypto/skcipher.h:349
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_simple
  - crypto/skcipher.c:crypto_skcipher_decrypt
  - crypto/skcipher.c:crypto_skcipher_encrypt
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
  - crypto/skcipher.c:skcipher_setkey_blkcipher
```
```
In crypto/cts.c (ffff8000105c957c)
Location: include/crypto/skcipher.h:349
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_setkey
  - crypto/cts.c:crypto_cts_setkey
```
```
In crypto/xts.c (ffff8000105caaa0)
Location: include/crypto/skcipher.h:349
Inline: True
```
```
In crypto/ctr.c (ffff8000105cabfc)
Location: include/crypto/skcipher.h:349
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_setkey
  - crypto/ctr.c:crypto_rfc3686_setkey
```
```
In crypto/gcm.c (ffff8000105cc68c)
Location: include/crypto/skcipher.h:349
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
In crypto/skcipher.c (c076bb70)
Location: include/crypto/skcipher.h:349
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_simple
  - crypto/skcipher.c:crypto_skcipher_decrypt
  - crypto/skcipher.c:crypto_skcipher_encrypt
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
  - crypto/skcipher.c:skcipher_setkey_blkcipher
```
```
In crypto/cts.c (c0777148)
Location: include/crypto/skcipher.h:349
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_setkey
  - crypto/cts.c:crypto_cts_setkey
```
```
In crypto/xts.c (c0778698)
Location: include/crypto/skcipher.h:349
Inline: True
```
```
In crypto/ctr.c (c07787cc)
Location: include/crypto/skcipher.h:349
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_setkey
  - crypto/ctr.c:crypto_rfc3686_setkey
```
```
In crypto/gcm.c (c077a56c)
Location: include/crypto/skcipher.h:349
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
In crypto/skcipher.c (c000000000745218)
Location: include/crypto/skcipher.h:349
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_simple
  - crypto/skcipher.c:crypto_skcipher_decrypt
  - crypto/skcipher.c:crypto_skcipher_encrypt
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
  - crypto/skcipher.c:skcipher_setkey_blkcipher
```
```
In crypto/cts.c (c000000000753ba8)
Location: include/crypto/skcipher.h:349
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_setkey
  - crypto/cts.c:crypto_cts_setkey
```
```
In crypto/xts.c (c000000000755424)
Location: include/crypto/skcipher.h:349
Inline: True
```
```
In crypto/ctr.c (c0000000007559d8)
Location: include/crypto/skcipher.h:349
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_setkey
  - crypto/ctr.c:crypto_rfc3686_setkey
```
```
In crypto/gcm.c (c000000000757adc)
Location: include/crypto/skcipher.h:349
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
In crypto/skcipher.c (ffffffe00040323c)
Location: include/crypto/skcipher.h:349
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_simple
  - crypto/skcipher.c:crypto_skcipher_decrypt
  - crypto/skcipher.c:crypto_skcipher_encrypt
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
  - crypto/skcipher.c:skcipher_setkey_blkcipher
```
```
In crypto/cts.c (ffffffe00040dd8e)
Location: include/crypto/skcipher.h:349
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_setkey
  - crypto/cts.c:crypto_cts_setkey
```
```
In crypto/xts.c (ffffffe00040eca8)
Location: include/crypto/skcipher.h:349
Inline: True
```
```
In crypto/ctr.c (ffffffe00040f0c6)
Location: include/crypto/skcipher.h:349
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_setkey
  - crypto/ctr.c:crypto_rfc3686_setkey
```
```
In crypto/gcm.c (ffffffe000410602)
Location: include/crypto/skcipher.h:349
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
In crypto/skcipher.c (ffffffff814bbad1)
Location: include/crypto/skcipher.h:349
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_simple
  - crypto/skcipher.c:crypto_skcipher_decrypt
  - crypto/skcipher.c:crypto_skcipher_encrypt
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
  - crypto/skcipher.c:skcipher_setkey_blkcipher
```
```
In crypto/cts.c (ffffffff814c5ca3)
Location: include/crypto/skcipher.h:349
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_setkey
  - crypto/cts.c:crypto_cts_setkey
```
```
In crypto/xts.c (ffffffff814c6e82)
Location: include/crypto/skcipher.h:349
Inline: True
```
```
In crypto/ctr.c (ffffffff814c72a4)
Location: include/crypto/skcipher.h:349
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_setkey
  - crypto/ctr.c:crypto_rfc3686_setkey
```
```
In crypto/gcm.c (ffffffff814c8789)
Location: include/crypto/skcipher.h:349
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
In crypto/skcipher.c (ffffffff814ac4f1)
Location: include/crypto/skcipher.h:349
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_simple
  - crypto/skcipher.c:crypto_skcipher_decrypt
  - crypto/skcipher.c:crypto_skcipher_encrypt
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
  - crypto/skcipher.c:skcipher_setkey_blkcipher
```
```
In crypto/cts.c (ffffffff814b66c3)
Location: include/crypto/skcipher.h:349
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_setkey
  - crypto/cts.c:crypto_cts_setkey
```
```
In crypto/xts.c (ffffffff814b78a2)
Location: include/crypto/skcipher.h:349
Inline: True
```
```
In crypto/ctr.c (ffffffff814b7cc4)
Location: include/crypto/skcipher.h:349
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_setkey
  - crypto/ctr.c:crypto_rfc3686_setkey
```
```
In crypto/gcm.c (ffffffff814b91a9)
Location: include/crypto/skcipher.h:349
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
In crypto/skcipher.c (ffffffff814b7b61)
Location: include/crypto/skcipher.h:349
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_simple
  - crypto/skcipher.c:crypto_skcipher_decrypt
  - crypto/skcipher.c:crypto_skcipher_encrypt
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
  - crypto/skcipher.c:skcipher_setkey_blkcipher
```
```
In crypto/cts.c (ffffffff814c1d33)
Location: include/crypto/skcipher.h:349
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_setkey
  - crypto/cts.c:crypto_cts_setkey
```
```
In crypto/xts.c (ffffffff814c2f12)
Location: include/crypto/skcipher.h:349
Inline: True
```
```
In crypto/ctr.c (ffffffff814c3334)
Location: include/crypto/skcipher.h:349
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_setkey
  - crypto/ctr.c:crypto_rfc3686_setkey
```
```
In crypto/gcm.c (ffffffff814c4819)
Location: include/crypto/skcipher.h:349
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
In crypto/skcipher.c (ffffffff814d0641)
Location: include/crypto/skcipher.h:349
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_simple
  - crypto/skcipher.c:crypto_skcipher_decrypt
  - crypto/skcipher.c:crypto_skcipher_encrypt
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
  - crypto/skcipher.c:skcipher_setkey_blkcipher
```
```
In crypto/cts.c (ffffffff814da803)
Location: include/crypto/skcipher.h:349
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_setkey
  - crypto/cts.c:crypto_cts_setkey
```
```
In crypto/xts.c (ffffffff814db9e2)
Location: include/crypto/skcipher.h:349
Inline: True
```
```
In crypto/ctr.c (ffffffff814dbe04)
Location: include/crypto/skcipher.h:349
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_setkey
  - crypto/ctr.c:crypto_rfc3686_setkey
```
```
In crypto/gcm.c (ffffffff814dd2e9)
Location: include/crypto/skcipher.h:349
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_setkey
```
</details>
</li>
</ul>

## Differences
