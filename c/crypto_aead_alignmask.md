# Function: <code>crypto_aead_alignmask</code>

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
In crypto/aead.c (ffffffff8139efcf)
Location: include/crypto/aead.h:250
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_setkey
```
```
In crypto/blkcipher.c (ffffffff813a1a04)
Location: include/crypto/aead.h:250
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_aead_walk_virt_block
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
In crypto/aead.c (ffffffff813dbd7f)
Location: include/crypto/aead.h:253
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_setkey
```
```
In crypto/blkcipher.c (ffffffff813ddeb4)
Location: include/crypto/aead.h:253
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_aead_walk_virt_block
```
```
In crypto/seqiv.c (ffffffff813de9b1)
Location: include/crypto/aead.h:253
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
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
In crypto/aead.c (ffffffff813f365f)
Location: include/crypto/aead.h:253
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_setkey
```
```
In crypto/blkcipher.c (ffffffff813f5764)
Location: include/crypto/aead.h:253
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_aead_walk_virt_block
```
```
In crypto/skcipher.c (ffffffff813f6bf3)
Location: include/crypto/aead.h:253
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
```
```
In crypto/seqiv.c (ffffffff813f6f51)
Location: include/crypto/aead.h:253
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
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
In crypto/aead.c (ffffffff813ff97f)
Location: include/crypto/aead.h:253
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_setkey
```
```
In crypto/blkcipher.c (ffffffff81401a04)
Location: include/crypto/aead.h:253
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_aead_walk_virt_block
```
```
In crypto/skcipher.c (ffffffff81402fc3)
Location: include/crypto/aead.h:253
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
```
```
In crypto/seqiv.c (ffffffff81403357)
Location: include/crypto/aead.h:253
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
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
In crypto/aead.c (ffffffff81427f5f)
Location: include/crypto/aead.h:253
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_setkey
```
```
In crypto/blkcipher.c (ffffffff8142a024)
Location: include/crypto/aead.h:253
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_aead_walk_virt_block
```
```
In crypto/skcipher.c (ffffffff8142b6a9)
Location: include/crypto/aead.h:253
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
```
```
In crypto/seqiv.c (ffffffff8142ba4d)
Location: include/crypto/aead.h:253
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/gcm.c (ffffffff814391f5)
Location: include/crypto/aead.h:253
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_init_tfm
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_rfc4106_init_tfm
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_gcm_init_tfm
  - crypto/gcm.c:crypto_gcm_decrypt
  - crypto/gcm.c:gcm_dec_hash_continue
  - crypto/gcm.c:crypto_gcm_verify
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:gcm_encrypt_continue
  - crypto/gcm.c:gcm_enc_copy_hash
  - crypto/gcm.c:gcm_hash
  - crypto/gcm.c:gcm_hash_init_continue
  - crypto/gcm.c:gcm_hash_assoc_continue
  - crypto/gcm.c:gcm_hash_assoc_remain_continue
  - crypto/gcm.c:gcm_hash_crypt_continue
  - crypto/gcm.c:gcm_hash_crypt_remain_continue
  - crypto/gcm.c:gcm_hash_crypt_remain_continue
  - crypto/gcm.c:gcm_hash_len_done
  - crypto/gcm.c:crypto_gcm_init_common
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
In crypto/aead.c (ffffffff8145ad75)
Location: include/crypto/aead.h:253
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_setkey
```
```
In crypto/blkcipher.c (ffffffff8145cd64)
Location: include/crypto/aead.h:253
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_aead_walk_virt_block
```
```
In crypto/skcipher.c (ffffffff8145e3b5)
Location: include/crypto/aead.h:253
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
```
```
In crypto/seqiv.c (ffffffff8145e762)
Location: include/crypto/aead.h:253
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/gcm.c (ffffffff8146b53e)
Location: include/crypto/aead.h:253
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_init_tfm
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_rfc4106_init_tfm
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_gcm_init_tfm
  - crypto/gcm.c:crypto_gcm_decrypt
  - crypto/gcm.c:gcm_dec_hash_continue
  - crypto/gcm.c:crypto_gcm_verify
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:gcm_encrypt_continue
  - crypto/gcm.c:gcm_enc_copy_hash
  - crypto/gcm.c:gcm_hash
  - crypto/gcm.c:gcm_hash_init_continue
  - crypto/gcm.c:gcm_hash_assoc_continue
  - crypto/gcm.c:gcm_hash_assoc_remain_continue
  - crypto/gcm.c:gcm_hash_crypt_continue
  - crypto/gcm.c:gcm_hash_len_done
  - crypto/gcm.c:crypto_gcm_init_common
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
In crypto/aead.c (ffffffff814788e5)
Location: include/crypto/aead.h:250
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_setkey
```
```
In crypto/blkcipher.c (ffffffff8147a5f4)
Location: include/crypto/aead.h:250
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_aead_walk_virt_block
```
```
In crypto/skcipher.c (ffffffff8147bc75)
Location: include/crypto/aead.h:250
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
```
```
In crypto/seqiv.c (ffffffff8147c07f)
Location: include/crypto/aead.h:250
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/gcm.c (ffffffff81488bbe)
Location: include/crypto/aead.h:250
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_init_tfm
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_rfc4106_init_tfm
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_gcm_init_tfm
  - crypto/gcm.c:crypto_gcm_decrypt
  - crypto/gcm.c:gcm_dec_hash_continue
  - crypto/gcm.c:crypto_gcm_verify
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:gcm_encrypt_continue
  - crypto/gcm.c:gcm_enc_copy_hash
  - crypto/gcm.c:gcm_hash
  - crypto/gcm.c:gcm_hash_assoc_remain_continue
  - crypto/gcm.c:gcm_hash_crypt_continue
  - crypto/gcm.c:gcm_hash_len_done
  - crypto/gcm.c:gcm_hash_update
  - crypto/gcm.c:crypto_gcm_init_common
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
In crypto/aead.c (ffffffff814a6c05)
Location: include/crypto/aead.h:245
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_setkey
```
```
In crypto/blkcipher.c (ffffffff814a8624)
Location: include/crypto/aead.h:245
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_aead_walk_virt_block
```
```
In crypto/skcipher.c (ffffffff814aa017)
Location: include/crypto/aead.h:245
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
```
```
In crypto/seqiv.c (ffffffff814aa3e0)
Location: include/crypto/aead.h:245
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/gcm.c (ffffffff814b6613)
Location: include/crypto/aead.h:245
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_init_tfm
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_rfc4106_init_tfm
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_gcm_init_tfm
  - crypto/gcm.c:crypto_gcm_decrypt
  - crypto/gcm.c:gcm_dec_hash_continue
  - crypto/gcm.c:crypto_gcm_verify
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:gcm_encrypt_continue
  - crypto/gcm.c:gcm_enc_copy_hash
  - crypto/gcm.c:gcm_hash
  - crypto/gcm.c:gcm_hash_assoc_remain_continue
  - crypto/gcm.c:gcm_hash_crypt_continue
  - crypto/gcm.c:gcm_hash_len_done
  - crypto/gcm.c:gcm_hash_update
  - crypto/gcm.c:crypto_gcm_init_common
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
In crypto/aead.c (ffffffff814c1875)
Location: include/crypto/aead.h:245
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_setkey
```
```
In crypto/blkcipher.c (ffffffff814c3294)
Location: include/crypto/aead.h:245
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_aead_walk_virt_block
```
```
In crypto/skcipher.c (ffffffff814c4d07)
Location: include/crypto/aead.h:245
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
```
```
In crypto/seqiv.c (ffffffff814c50a0)
Location: include/crypto/aead.h:245
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/gcm.c (ffffffff814cf833)
Location: include/crypto/aead.h:245
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_init_tfm
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_rfc4106_init_tfm
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_gcm_init_tfm
  - crypto/gcm.c:crypto_gcm_decrypt
  - crypto/gcm.c:gcm_dec_hash_continue
  - crypto/gcm.c:crypto_gcm_verify
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:gcm_encrypt_continue
  - crypto/gcm.c:gcm_enc_copy_hash
  - crypto/gcm.c:gcm_hash
  - crypto/gcm.c:gcm_hash_assoc_remain_continue
  - crypto/gcm.c:gcm_hash_crypt_continue
  - crypto/gcm.c:gcm_hash_len_done
  - crypto/gcm.c:gcm_hash_update
  - crypto/gcm.c:crypto_gcm_init_common
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
In crypto/aead.c (ffffffff81521d05)
Location: include/crypto/aead.h:261
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_setkey
  - crypto/aead.c:setkey_unaligned
```
```
In crypto/skcipher.c (ffffffff81523b97)
Location: include/crypto/aead.h:261
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
```
```
In crypto/seqiv.c (ffffffff81523fb0)
Location: include/crypto/aead.h:261
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/gcm.c (ffffffff8152ea33)
Location: include/crypto/aead.h:261
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_init_tfm
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_rfc4106_init_tfm
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_gcm_init_tfm
  - crypto/gcm.c:crypto_gcm_decrypt
  - crypto/gcm.c:gcm_dec_hash_continue
  - crypto/gcm.c:crypto_gcm_verify
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:gcm_encrypt_continue
  - crypto/gcm.c:gcm_enc_copy_hash
  - crypto/gcm.c:gcm_hash
  - crypto/gcm.c:gcm_hash_assoc_remain_continue
  - crypto/gcm.c:gcm_hash_crypt_continue
  - crypto/gcm.c:gcm_hash_crypt_remain_continue
  - crypto/gcm.c:gcm_hash_len_done
  - crypto/gcm.c:gcm_hash_len
  - crypto/gcm.c:gcm_hash_update
  - crypto/gcm.c:crypto_gcm_init_common
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
In crypto/aead.c (ffffffff8153eb55)
Location: include/crypto/aead.h:266
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_setkey
  - crypto/aead.c:setkey_unaligned
```
```
In crypto/skcipher.c (ffffffff81540ae7)
Location: include/crypto/aead.h:266
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
```
```
In crypto/seqiv.c (ffffffff81540eba)
Location: include/crypto/aead.h:266
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/gcm.c (ffffffff8154b9b3)
Location: include/crypto/aead.h:266
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_init_tfm
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_rfc4106_init_tfm
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_gcm_init_tfm
  - crypto/gcm.c:crypto_gcm_decrypt
  - crypto/gcm.c:gcm_dec_hash_continue
  - crypto/gcm.c:crypto_gcm_verify
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:gcm_encrypt_continue
  - crypto/gcm.c:gcm_enc_copy_hash
  - crypto/gcm.c:gcm_hash
  - crypto/gcm.c:gcm_hash_assoc_remain_continue
  - crypto/gcm.c:gcm_hash_crypt_continue
  - crypto/gcm.c:gcm_hash_crypt_remain_continue
  - crypto/gcm.c:gcm_hash_len_done
  - crypto/gcm.c:gcm_hash_len
  - crypto/gcm.c:gcm_hash_update
  - crypto/gcm.c:crypto_gcm_init_common
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
In crypto/aead.c (ffffffff81547205)
Location: include/crypto/aead.h:268
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_setkey
  - crypto/aead.c:setkey_unaligned
```
```
In crypto/skcipher.c (ffffffff81549147)
Location: include/crypto/aead.h:268
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
```
```
In crypto/seqiv.c (ffffffff81549520)
Location: include/crypto/aead.h:268
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/gcm.c (ffffffff81553fb3)
Location: include/crypto/aead.h:268
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_init_tfm
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_rfc4106_init_tfm
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_gcm_init_tfm
  - crypto/gcm.c:crypto_gcm_decrypt
  - crypto/gcm.c:gcm_dec_hash_continue
  - crypto/gcm.c:crypto_gcm_verify
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:gcm_encrypt_continue
  - crypto/gcm.c:gcm_enc_copy_hash
  - crypto/gcm.c:gcm_hash
  - crypto/gcm.c:gcm_hash_assoc_remain_continue
  - crypto/gcm.c:gcm_hash_crypt_continue
  - crypto/gcm.c:gcm_hash_crypt_remain_continue
  - crypto/gcm.c:gcm_hash_crypt_remain_continue
  - crypto/gcm.c:gcm_hash_len_done
  - crypto/gcm.c:gcm_hash_update
  - crypto/gcm.c:crypto_gcm_init_common
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
In crypto/aead.c (ffffffff815a79e5)
Location: include/crypto/aead.h:268
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_setkey
  - crypto/aead.c:setkey_unaligned
```
```
In crypto/skcipher.c (ffffffff815a9927)
Location: include/crypto/aead.h:268
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
```
```
In crypto/seqiv.c (ffffffff815a9d00)
Location: include/crypto/aead.h:268
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/gcm.c (ffffffff815b4fe3)
Location: include/crypto/aead.h:268
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_init_tfm
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_rfc4106_init_tfm
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_gcm_init_tfm
  - crypto/gcm.c:crypto_gcm_decrypt
  - crypto/gcm.c:gcm_dec_hash_continue
  - crypto/gcm.c:crypto_gcm_verify
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:gcm_encrypt_continue
  - crypto/gcm.c:gcm_enc_copy_hash
  - crypto/gcm.c:gcm_hash
  - crypto/gcm.c:gcm_hash_assoc_remain_continue
  - crypto/gcm.c:gcm_hash_crypt_continue
  - crypto/gcm.c:gcm_hash_crypt_remain_continue
  - crypto/gcm.c:gcm_hash_crypt_remain_continue
  - crypto/gcm.c:gcm_hash_len_done
  - crypto/gcm.c:gcm_hash_update
  - crypto/gcm.c:crypto_gcm_init_common
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
In crypto/aead.c (ffffffff8164ed35)
Location: include/crypto/aead.h:270
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_setkey
  - crypto/aead.c:setkey_unaligned
```
```
In crypto/skcipher.c (ffffffff81650d87)
Location: include/crypto/aead.h:270
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
```
```
In crypto/seqiv.c (ffffffff81651200)
Location: include/crypto/aead.h:270
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/gcm.c (ffffffff8165e065)
Location: include/crypto/aead.h:270
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_init_tfm
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_rfc4106_init_tfm
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_gcm_init_tfm
  - crypto/gcm.c:crypto_gcm_decrypt
  - crypto/gcm.c:gcm_dec_hash_continue
  - crypto/gcm.c:crypto_gcm_verify
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:gcm_encrypt_continue
  - crypto/gcm.c:gcm_enc_copy_hash
  - crypto/gcm.c:gcm_hash
  - crypto/gcm.c:gcm_hash_assoc_remain_continue
  - crypto/gcm.c:gcm_hash_crypt_continue
  - crypto/gcm.c:gcm_hash_crypt_remain_continue
  - crypto/gcm.c:gcm_hash_crypt_remain_continue
  - crypto/gcm.c:gcm_hash_len_done
  - crypto/gcm.c:gcm_hash_update
  - crypto/gcm.c:crypto_gcm_init_common
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
In crypto/aead.c (ffffffff817086c5)
Location: include/crypto/aead.h:270
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_setkey
  - crypto/aead.c:setkey_unaligned
```
```
In crypto/skcipher.c (ffffffff8170a577)
Location: include/crypto/aead.h:270
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
```
```
In crypto/seqiv.c (ffffffff8170aa80)
Location: include/crypto/aead.h:270
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/gcm.c (ffffffff817179b5)
Location: include/crypto/aead.h:270
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_init_tfm
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_rfc4106_init_tfm
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_gcm_init_tfm
  - crypto/gcm.c:crypto_gcm_decrypt
  - crypto/gcm.c:gcm_dec_hash_continue
  - crypto/gcm.c:crypto_gcm_verify
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:gcm_encrypt_continue
  - crypto/gcm.c:gcm_enc_copy_hash
  - crypto/gcm.c:gcm_hash
  - crypto/gcm.c:gcm_hash_assoc_remain_continue
  - crypto/gcm.c:gcm_hash_crypt_continue
  - crypto/gcm.c:gcm_hash_crypt_remain_continue
  - crypto/gcm.c:gcm_hash_crypt_remain_continue
  - crypto/gcm.c:gcm_hash_len_done
  - crypto/gcm.c:gcm_hash_update
  - crypto/gcm.c:crypto_gcm_init_common
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
In crypto/aead.c (ffffffff81741e35)
Location: include/crypto/aead.h:292
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_setkey
  - crypto/aead.c:setkey_unaligned
```
```
In crypto/skcipher.c (ffffffff81743dc7)
Location: include/crypto/aead.h:292
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
```
```
In crypto/seqiv.c (ffffffff817442d0)
Location: include/crypto/aead.h:292
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/gcm.c (ffffffff81753395)
Location: include/crypto/aead.h:292
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_init_tfm
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_rfc4106_init_tfm
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_gcm_init_tfm
  - crypto/gcm.c:crypto_gcm_decrypt
  - crypto/gcm.c:gcm_dec_hash_continue
  - crypto/gcm.c:crypto_gcm_verify
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:gcm_encrypt_continue
  - crypto/gcm.c:gcm_enc_copy_hash
  - crypto/gcm.c:gcm_hash
  - crypto/gcm.c:gcm_hash_assoc_remain_continue
  - crypto/gcm.c:gcm_hash_crypt_continue
  - crypto/gcm.c:gcm_hash_crypt_remain_continue
  - crypto/gcm.c:gcm_hash_len_done
  - crypto/gcm.c:gcm_hash_len
  - crypto/gcm.c:gcm_hash_update
  - crypto/gcm.c:crypto_gcm_init_common
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
In crypto/aead.c (ffffffff81782d15)
Location: include/crypto/aead.h:304
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_setkey
  - crypto/aead.c:setkey_unaligned
```
```
In crypto/skcipher.c (ffffffff817861a7)
Location: include/crypto/aead.h:304
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
```
```
In crypto/seqiv.c (ffffffff81786890)
Location: include/crypto/aead.h:304
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/gcm.c (ffffffff81795265)
Location: include/crypto/aead.h:304
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_init_tfm
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_rfc4106_init_tfm
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_gcm_init_tfm
  - crypto/gcm.c:crypto_gcm_decrypt
  - crypto/gcm.c:gcm_dec_hash_continue
  - crypto/gcm.c:crypto_gcm_verify
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:gcm_encrypt_continue
  - crypto/gcm.c:gcm_enc_copy_hash
  - crypto/gcm.c:gcm_hash
  - crypto/gcm.c:gcm_hash_init_continue
  - crypto/gcm.c:gcm_hash_assoc_continue
  - crypto/gcm.c:gcm_hash_assoc_remain_continue
  - crypto/gcm.c:gcm_hash_crypt_continue
  - crypto/gcm.c:gcm_hash_crypt_remain_continue
  - crypto/gcm.c:gcm_hash_len_done
  - crypto/gcm.c:gcm_hash_len
  - crypto/gcm.c:crypto_gcm_init_common
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
In crypto/aead.c (ffff8000105bbf3c)
Location: include/crypto/aead.h:245
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_setkey
```
```
In crypto/blkcipher.c (ffff8000105bda5c)
Location: include/crypto/aead.h:245
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_aead_walk_virt_block
```
```
In crypto/skcipher.c (ffff8000105bf7cc)
Location: include/crypto/aead.h:245
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
```
```
In crypto/seqiv.c (ffff8000105bfc2c)
Location: include/crypto/aead.h:245
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/gcm.c (ffff8000105cb930)
Location: include/crypto/aead.h:245
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_init_tfm
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_rfc4106_init_tfm
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_gcm_init_tfm
  - crypto/gcm.c:crypto_gcm_decrypt
  - crypto/gcm.c:gcm_dec_hash_continue
  - crypto/gcm.c:crypto_gcm_verify
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:gcm_encrypt_continue
  - crypto/gcm.c:gcm_enc_copy_hash
  - crypto/gcm.c:gcm_hash
  - crypto/gcm.c:gcm_hash_assoc_remain_continue
  - crypto/gcm.c:gcm_hash_crypt_continue
  - crypto/gcm.c:gcm_hash_len_done
  - crypto/gcm.c:gcm_hash_update
  - crypto/gcm.c:crypto_gcm_init_common
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
In crypto/aead.c (c076a000)
Location: include/crypto/aead.h:245
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_setkey
```
```
In crypto/blkcipher.c (c076b8a8)
Location: include/crypto/aead.h:245
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_aead_walk_virt_block
```
```
In crypto/skcipher.c (c076d4ec)
Location: include/crypto/aead.h:245
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
```
```
In crypto/seqiv.c (c076d878)
Location: include/crypto/aead.h:245
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/gcm.c (c0779368)
Location: include/crypto/aead.h:245
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_init_tfm
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_rfc4106_init_tfm
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_gcm_init_tfm
  - crypto/gcm.c:crypto_gcm_decrypt
  - crypto/gcm.c:gcm_dec_hash_continue
  - crypto/gcm.c:crypto_gcm_verify
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:gcm_encrypt_continue
  - crypto/gcm.c:gcm_enc_copy_hash
  - crypto/gcm.c:gcm_hash
  - crypto/gcm.c:gcm_hash_assoc_remain_continue
  - crypto/gcm.c:gcm_hash_crypt_continue
  - crypto/gcm.c:gcm_hash_len_done
  - crypto/gcm.c:gcm_hash_update
  - crypto/gcm.c:crypto_gcm_init_common
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
In crypto/aead.c (c000000000742838)
Location: include/crypto/aead.h:245
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_setkey
```
```
In crypto/blkcipher.c (c000000000744e78)
Location: include/crypto/aead.h:245
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_aead_walk_virt_block
```
```
In crypto/skcipher.c (c000000000747574)
Location: include/crypto/aead.h:245
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
```
```
In crypto/seqiv.c (c000000000747a84)
Location: include/crypto/aead.h:245
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/gcm.c (c000000000756a78)
Location: include/crypto/aead.h:245
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_init_tfm
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_rfc4106_init_tfm
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_gcm_init_tfm
  - crypto/gcm.c:crypto_gcm_decrypt
  - crypto/gcm.c:gcm_dec_hash_continue
  - crypto/gcm.c:crypto_gcm_verify
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:gcm_encrypt_continue
  - crypto/gcm.c:gcm_enc_copy_hash
  - crypto/gcm.c:gcm_hash
  - crypto/gcm.c:gcm_hash_assoc_remain_continue
  - crypto/gcm.c:gcm_hash_crypt_continue
  - crypto/gcm.c:gcm_hash_len_done
  - crypto/gcm.c:gcm_hash_update
  - crypto/gcm.c:crypto_gcm_init_common
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
In crypto/aead.c (ffffffe00040171c)
Location: include/crypto/aead.h:245
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_setkey
```
```
In crypto/blkcipher.c (ffffffe00040300a)
Location: include/crypto/aead.h:245
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_aead_walk_virt_block
```
```
In crypto/skcipher.c (ffffffe000404912)
Location: include/crypto/aead.h:245
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
```
```
In crypto/seqiv.c (ffffffe000404c8e)
Location: include/crypto/aead.h:245
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/gcm.c (ffffffe00040fc7c)
Location: include/crypto/aead.h:245
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_init_tfm
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_rfc4106_init_tfm
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_gcm_init_tfm
  - crypto/gcm.c:crypto_gcm_decrypt
  - crypto/gcm.c:gcm_dec_hash_continue
  - crypto/gcm.c:crypto_gcm_verify
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:gcm_encrypt_continue
  - crypto/gcm.c:gcm_enc_copy_hash
  - crypto/gcm.c:gcm_hash
  - crypto/gcm.c:gcm_hash_assoc_remain_continue
  - crypto/gcm.c:gcm_hash_crypt_continue
  - crypto/gcm.c:gcm_hash_len_done
  - crypto/gcm.c:gcm_hash_update
  - crypto/gcm.c:crypto_gcm_init_common
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
In crypto/aead.c (ffffffff814b9e55)
Location: include/crypto/aead.h:245
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_setkey
```
```
In crypto/blkcipher.c (ffffffff814bb874)
Location: include/crypto/aead.h:245
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_aead_walk_virt_block
```
```
In crypto/skcipher.c (ffffffff814bd2e7)
Location: include/crypto/aead.h:245
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
```
```
In crypto/seqiv.c (ffffffff814bd680)
Location: include/crypto/aead.h:245
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/gcm.c (ffffffff814c7e13)
Location: include/crypto/aead.h:245
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_init_tfm
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_rfc4106_init_tfm
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_gcm_init_tfm
  - crypto/gcm.c:crypto_gcm_decrypt
  - crypto/gcm.c:gcm_dec_hash_continue
  - crypto/gcm.c:crypto_gcm_verify
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:gcm_encrypt_continue
  - crypto/gcm.c:gcm_enc_copy_hash
  - crypto/gcm.c:gcm_hash
  - crypto/gcm.c:gcm_hash_assoc_remain_continue
  - crypto/gcm.c:gcm_hash_crypt_continue
  - crypto/gcm.c:gcm_hash_len_done
  - crypto/gcm.c:gcm_hash_update
  - crypto/gcm.c:crypto_gcm_init_common
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
In crypto/aead.c (ffffffff814aa875)
Location: include/crypto/aead.h:245
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_setkey
```
```
In crypto/blkcipher.c (ffffffff814ac294)
Location: include/crypto/aead.h:245
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_aead_walk_virt_block
```
```
In crypto/skcipher.c (ffffffff814add07)
Location: include/crypto/aead.h:245
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
```
```
In crypto/seqiv.c (ffffffff814ae0a0)
Location: include/crypto/aead.h:245
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/gcm.c (ffffffff814b8833)
Location: include/crypto/aead.h:245
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_init_tfm
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_rfc4106_init_tfm
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_gcm_init_tfm
  - crypto/gcm.c:crypto_gcm_decrypt
  - crypto/gcm.c:gcm_dec_hash_continue
  - crypto/gcm.c:crypto_gcm_verify
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:gcm_encrypt_continue
  - crypto/gcm.c:gcm_enc_copy_hash
  - crypto/gcm.c:gcm_hash
  - crypto/gcm.c:gcm_hash_assoc_remain_continue
  - crypto/gcm.c:gcm_hash_crypt_continue
  - crypto/gcm.c:gcm_hash_len_done
  - crypto/gcm.c:gcm_hash_update
  - crypto/gcm.c:crypto_gcm_init_common
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
In crypto/aead.c (ffffffff814b5ee5)
Location: include/crypto/aead.h:245
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_setkey
```
```
In crypto/blkcipher.c (ffffffff814b7904)
Location: include/crypto/aead.h:245
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_aead_walk_virt_block
```
```
In crypto/skcipher.c (ffffffff814b9377)
Location: include/crypto/aead.h:245
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
```
```
In crypto/seqiv.c (ffffffff814b9710)
Location: include/crypto/aead.h:245
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/gcm.c (ffffffff814c3ea3)
Location: include/crypto/aead.h:245
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_init_tfm
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_rfc4106_init_tfm
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_gcm_init_tfm
  - crypto/gcm.c:crypto_gcm_decrypt
  - crypto/gcm.c:gcm_dec_hash_continue
  - crypto/gcm.c:crypto_gcm_verify
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:gcm_encrypt_continue
  - crypto/gcm.c:gcm_enc_copy_hash
  - crypto/gcm.c:gcm_hash
  - crypto/gcm.c:gcm_hash_assoc_remain_continue
  - crypto/gcm.c:gcm_hash_crypt_continue
  - crypto/gcm.c:gcm_hash_len_done
  - crypto/gcm.c:gcm_hash_update
  - crypto/gcm.c:crypto_gcm_init_common
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
In crypto/aead.c (ffffffff814ce985)
Location: include/crypto/aead.h:245
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_setkey
```
```
In crypto/blkcipher.c (ffffffff814d03e4)
Location: include/crypto/aead.h:245
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_aead_walk_virt_block
```
```
In crypto/skcipher.c (ffffffff814d1e17)
Location: include/crypto/aead.h:245
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
```
```
In crypto/seqiv.c (ffffffff814d21b0)
Location: include/crypto/aead.h:245
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/gcm.c (ffffffff814dc973)
Location: include/crypto/aead.h:245
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_init_tfm
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_rfc4106_init_tfm
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_gcm_init_tfm
  - crypto/gcm.c:crypto_gcm_decrypt
  - crypto/gcm.c:gcm_dec_hash_continue
  - crypto/gcm.c:crypto_gcm_verify
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:gcm_encrypt_continue
  - crypto/gcm.c:gcm_enc_copy_hash
  - crypto/gcm.c:gcm_hash
  - crypto/gcm.c:gcm_hash_assoc_remain_continue
  - crypto/gcm.c:gcm_hash_crypt_continue
  - crypto/gcm.c:gcm_hash_len_done
  - crypto/gcm.c:gcm_hash_update
  - crypto/gcm.c:crypto_gcm_init_common
```
</details>
</li>
</ul>

## Differences
