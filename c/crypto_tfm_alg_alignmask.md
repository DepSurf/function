# Function: <code>crypto_tfm_alg_alignmask</code>

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
In crypto/cipher.c (ffffffff8139cd1f)
Location: include/linux/crypto.h:656
Inline: True
Inline callers:
  - crypto/cipher.c:cipher_crypt_unaligned
  - crypto/cipher.c:cipher_decrypt_unaligned
  - crypto/cipher.c:cipher_encrypt_unaligned
```
```
In crypto/aead.c (ffffffff8139efcf)
Location: include/linux/crypto.h:656
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_setkey
```
```
In crypto/ablkcipher.c (ffffffff8139f8f5)
Location: include/linux/crypto.h:656
Inline: True
Inline callers:
  - crypto/ablkcipher.c:ablkcipher_walk_next
  - crypto/ablkcipher.c:ablkcipher_walk_phys
```
```
In crypto/blkcipher.c (ffffffff813a191d)
Location: include/linux/crypto.h:656
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_virt
  - crypto/blkcipher.c:blkcipher_walk_phys
  - crypto/blkcipher.c:blkcipher_walk_virt_block
  - crypto/blkcipher.c:blkcipher_aead_walk_virt_block
```
```
In crypto/eseqiv.c (ffffffff813a238c)
Location: include/linux/crypto.h:656
Inline: True
Inline callers:
  - crypto/eseqiv.c:eseqiv_init
  - crypto/eseqiv.c:eseqiv_complete2
  - crypto/eseqiv.c:eseqiv_givencrypt
```
```
In crypto/ahash.c (ffffffff813a2cee)
Location: include/linux/crypto.h:656
Inline: True
Inline callers:
  - crypto/ahash.c:ahash_save_req
  - crypto/ahash.c:crypto_hash_walk_first_compat
```
```
In crypto/shash.c (ffffffff813a3583)
Location: include/linux/crypto.h:656
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_setkey
  - crypto/shash.c:crypto_shash_update
  - crypto/shash.c:crypto_shash_final
```
```
In crypto/hmac.c (ffffffff813a4b30)
Location: include/linux/crypto.h:656
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_import
  - crypto/hmac.c:hmac_init
  - crypto/hmac.c:hmac_finup
  - crypto/hmac.c:hmac_final
  - crypto/hmac.c:hmac_exit_tfm
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
In crypto/cipher.c (ffffffff813d9c76)
Location: include/linux/crypto.h:631
Inline: True
Inline callers:
  - crypto/cipher.c:cipher_decrypt_unaligned
  - crypto/cipher.c:cipher_encrypt_unaligned
  - crypto/cipher.c:cipher_crypt_unaligned
```
```
In crypto/aead.c (ffffffff813dbd7f)
Location: include/linux/crypto.h:631
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_setkey
```
```
In crypto/ablkcipher.c (ffffffff813dcf6d)
Location: include/linux/crypto.h:631
Inline: True
Inline callers:
  - crypto/ablkcipher.c:ablkcipher_walk_phys
  - crypto/ablkcipher.c:ablkcipher_walk_next
```
```
In crypto/blkcipher.c (ffffffff813dd21a)
Location: include/linux/crypto.h:631
Inline: True
Inline callers:
  - crypto/blkcipher.c:crypto_init_blkcipher_ops
  - crypto/blkcipher.c:blkcipher_aead_walk_virt_block
  - crypto/blkcipher.c:blkcipher_walk_virt_block
  - crypto/blkcipher.c:blkcipher_walk_phys
  - crypto/blkcipher.c:blkcipher_walk_virt
```
```
In crypto/seqiv.c (ffffffff813de9b1)
Location: include/linux/crypto.h:631
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/ahash.c (ffffffff813dee9e)
Location: include/linux/crypto.h:631
Inline: True
Inline callers:
  - crypto/ahash.c:ahash_save_req
```
```
In crypto/shash.c (ffffffff813df8ff)
Location: include/linux/crypto.h:631
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_final
  - crypto/shash.c:crypto_shash_update
  - crypto/shash.c:crypto_shash_setkey
```
```
In crypto/hmac.c (ffffffff813e26f6)
Location: include/linux/crypto.h:631
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_exit_tfm
  - crypto/hmac.c:hmac_finup
  - crypto/hmac.c:hmac_final
  - crypto/hmac.c:hmac_init
  - crypto/hmac.c:hmac_import
```
```
In crypto/cts.c (ffffffff813e7dc5)
Location: include/linux/crypto.h:631
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_init_tfm
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
```
```
In crypto/ctr.c (ffffffff813e8cd5)
Location: include/linux/crypto.h:631
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_init_tfm
  - crypto/ctr.c:crypto_rfc3686_crypt
```
```
In crypto/drbg.c (ffffffff813eed95)
Location: include/linux/crypto.h:631
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
  - crypto/drbg.c:drbg_init_hash_kernel
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
In crypto/cipher.c (ffffffff813f15d6)
Location: include/linux/crypto.h:634
Inline: True
Inline callers:
  - crypto/cipher.c:cipher_decrypt_unaligned
  - crypto/cipher.c:cipher_encrypt_unaligned
  - crypto/cipher.c:cipher_crypt_unaligned
```
```
In crypto/aead.c (ffffffff813f365f)
Location: include/linux/crypto.h:634
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_setkey
```
```
In crypto/ablkcipher.c (ffffffff813f483d)
Location: include/linux/crypto.h:634
Inline: True
Inline callers:
  - crypto/ablkcipher.c:ablkcipher_walk_phys
  - crypto/ablkcipher.c:ablkcipher_walk_next
```
```
In crypto/blkcipher.c (ffffffff813f4aea)
Location: include/linux/crypto.h:634
Inline: True
Inline callers:
  - crypto/blkcipher.c:crypto_init_blkcipher_ops
  - crypto/blkcipher.c:blkcipher_aead_walk_virt_block
  - crypto/blkcipher.c:blkcipher_walk_virt_block
  - crypto/blkcipher.c:blkcipher_walk_phys
  - crypto/blkcipher.c:blkcipher_walk_virt
```
```
In crypto/skcipher.c (ffffffff813f6bf3)
Location: include/linux/crypto.h:634
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_skcipher
```
```
In crypto/seqiv.c (ffffffff813f6f51)
Location: include/linux/crypto.h:634
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/ahash.c (ffffffff813f742e)
Location: include/linux/crypto.h:634
Inline: True
Inline callers:
  - crypto/ahash.c:ahash_save_req
```
```
In crypto/shash.c (ffffffff813f7e8f)
Location: include/linux/crypto.h:634
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_final
  - crypto/shash.c:crypto_shash_update
  - crypto/shash.c:crypto_shash_setkey
```
```
In crypto/hmac.c (ffffffff813fb716)
Location: include/linux/crypto.h:634
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_exit_tfm
  - crypto/hmac.c:hmac_finup
  - crypto/hmac.c:hmac_final
  - crypto/hmac.c:hmac_init
  - crypto/hmac.c:hmac_import
```
```
In crypto/cts.c (ffffffff81400bf5)
Location: include/linux/crypto.h:634
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_init_tfm
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
```
```
In crypto/ctr.c (ffffffff814022e5)
Location: include/linux/crypto.h:634
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_init_tfm
  - crypto/ctr.c:crypto_rfc3686_crypt
```
```
In crypto/drbg.c (ffffffff814085db)
Location: include/linux/crypto.h:634
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
  - crypto/drbg.c:drbg_init_hash_kernel
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
In crypto/cipher.c (ffffffff813fd856)
Location: include/linux/crypto.h:634
Inline: True
Inline callers:
  - crypto/cipher.c:cipher_decrypt_unaligned
  - crypto/cipher.c:cipher_encrypt_unaligned
  - crypto/cipher.c:cipher_crypt_unaligned
```
```
In crypto/aead.c (ffffffff813ff97f)
Location: include/linux/crypto.h:634
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_setkey
```
```
In crypto/ablkcipher.c (ffffffff81400b8a)
Location: include/linux/crypto.h:634
Inline: True
Inline callers:
  - crypto/ablkcipher.c:ablkcipher_walk_phys
  - crypto/ablkcipher.c:ablkcipher_walk_next
```
```
In crypto/blkcipher.c (ffffffff81400e1a)
Location: include/linux/crypto.h:634
Inline: True
Inline callers:
  - crypto/blkcipher.c:crypto_init_blkcipher_ops
  - crypto/blkcipher.c:blkcipher_aead_walk_virt_block
  - crypto/blkcipher.c:blkcipher_walk_virt_block
  - crypto/blkcipher.c:blkcipher_walk_phys
  - crypto/blkcipher.c:blkcipher_walk_virt
```
```
In crypto/skcipher.c (ffffffff81402fc3)
Location: include/linux/crypto.h:634
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_skcipher
```
```
In crypto/seqiv.c (ffffffff81403357)
Location: include/linux/crypto.h:634
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/ahash.c (ffffffff81403896)
Location: include/linux/crypto.h:634
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_op
  - crypto/ahash.c:ahash_save_req
  - crypto/ahash.c:crypto_ahash_setkey
```
```
In crypto/shash.c (ffffffff8140434f)
Location: include/linux/crypto.h:634
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_final
  - crypto/shash.c:crypto_shash_update
  - crypto/shash.c:crypto_shash_setkey
```
```
In crypto/hmac.c (ffffffff814081b6)
Location: include/linux/crypto.h:634
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_exit_tfm
  - crypto/hmac.c:hmac_init
  - crypto/hmac.c:hmac_import
```
```
In crypto/cts.c (ffffffff8140dba5)
Location: include/linux/crypto.h:634
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_init_tfm
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
```
```
In crypto/ctr.c (ffffffff8140f405)
Location: include/linux/crypto.h:634
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_init_tfm
  - crypto/ctr.c:crypto_rfc3686_crypt
```
```
In crypto/drbg.c (ffffffff81415ccb)
Location: include/linux/crypto.h:634
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
  - crypto/drbg.c:drbg_init_hash_kernel
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
In crypto/cipher.c (ffffffff81425dd6)
Location: include/linux/crypto.h:682
Inline: True
Inline callers:
  - crypto/cipher.c:cipher_decrypt_unaligned
  - crypto/cipher.c:cipher_encrypt_unaligned
  - crypto/cipher.c:cipher_crypt_unaligned
```
```
In crypto/aead.c (ffffffff81427f5f)
Location: include/linux/crypto.h:682
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_setkey
```
```
In crypto/ablkcipher.c (ffffffff8142918a)
Location: include/linux/crypto.h:682
Inline: True
Inline callers:
  - crypto/ablkcipher.c:ablkcipher_walk_phys
  - crypto/ablkcipher.c:ablkcipher_walk_next
```
```
In crypto/blkcipher.c (ffffffff8142941a)
Location: include/linux/crypto.h:682
Inline: True
Inline callers:
  - crypto/blkcipher.c:crypto_init_blkcipher_ops
  - crypto/blkcipher.c:blkcipher_aead_walk_virt_block
  - crypto/blkcipher.c:blkcipher_walk_virt_block
  - crypto/blkcipher.c:blkcipher_walk_phys
  - crypto/blkcipher.c:blkcipher_walk_virt
```
```
In crypto/skcipher.c (ffffffff8142b6a9)
Location: include/linux/crypto.h:682
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_skcipher
```
```
In crypto/seqiv.c (ffffffff8142ba4d)
Location: include/linux/crypto.h:682
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/ahash.c (ffffffff8142bff6)
Location: include/linux/crypto.h:682
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_op
  - crypto/ahash.c:ahash_save_req
  - crypto/ahash.c:crypto_ahash_setkey
```
```
In crypto/shash.c (ffffffff8142cc2f)
Location: include/linux/crypto.h:682
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_final
  - crypto/shash.c:crypto_shash_update
  - crypto/shash.c:crypto_shash_setkey
```
```
In crypto/hmac.c (ffffffff81430bd6)
Location: include/linux/crypto.h:682
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_exit_tfm
  - crypto/hmac.c:hmac_finup
  - crypto/hmac.c:hmac_final
  - crypto/hmac.c:hmac_init
  - crypto/hmac.c:hmac_import
```
```
In crypto/cts.c (ffffffff81436645)
Location: include/linux/crypto.h:682
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_init_tfm
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
```
```
In crypto/ctr.c (ffffffff81437e15)
Location: include/linux/crypto.h:682
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_init_tfm
  - crypto/ctr.c:crypto_rfc3686_crypt
```
```
In crypto/gcm.c (ffffffff814391f5)
Location: include/linux/crypto.h:682
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
```
In crypto/drbg.c (ffffffff814404a3)
Location: include/linux/crypto.h:682
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
  - crypto/drbg.c:drbg_init_hash_kernel
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
In crypto/cipher.c (ffffffff81458e79)
Location: include/linux/crypto.h:695
Inline: True
Inline callers:
  - crypto/cipher.c:crypto_init_cipher_ops
  - crypto/cipher.c:crypto_init_cipher_ops
  - crypto/cipher.c:cipher_decrypt_unaligned
  - crypto/cipher.c:cipher_encrypt_unaligned
  - crypto/cipher.c:cipher_crypt_unaligned
  - crypto/cipher.c:setkey
  - crypto/cipher.c:setkey
```
```
In crypto/aead.c (ffffffff8145ad75)
Location: include/linux/crypto.h:695
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_setkey
```
```
In crypto/ablkcipher.c (ffffffff8145ba3a)
Location: include/linux/crypto.h:695
Inline: True
Inline callers:
  - crypto/ablkcipher.c:setkey
  - crypto/ablkcipher.c:ablkcipher_walk_phys
  - crypto/ablkcipher.c:ablkcipher_walk_next
```
```
In crypto/blkcipher.c (ffffffff8145c1da)
Location: include/linux/crypto.h:695
Inline: True
Inline callers:
  - crypto/blkcipher.c:crypto_init_blkcipher_ops
  - crypto/blkcipher.c:setkey
  - crypto/blkcipher.c:blkcipher_aead_walk_virt_block
  - crypto/blkcipher.c:blkcipher_walk_virt_block
  - crypto/blkcipher.c:blkcipher_walk_phys
  - crypto/blkcipher.c:blkcipher_walk_virt
```
```
In crypto/skcipher.c (ffffffff8145d3ba)
Location: include/linux/crypto.h:695
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_skcipher
```
```
In crypto/seqiv.c (ffffffff8145e762)
Location: include/linux/crypto.h:695
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/ahash.c (ffffffff8145ecd5)
Location: include/linux/crypto.h:695
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_op
  - crypto/ahash.c:ahash_save_req
  - crypto/ahash.c:crypto_ahash_setkey
```
```
In crypto/shash.c (ffffffff8145fa0c)
Location: include/linux/crypto.h:695
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_digest
  - crypto/shash.c:crypto_shash_finup
  - crypto/shash.c:crypto_shash_final
  - crypto/shash.c:crypto_shash_update
  - crypto/shash.c:crypto_shash_setkey
```
```
In crypto/hmac.c (ffffffff81463735)
Location: include/linux/crypto.h:695
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_exit_tfm
  - crypto/hmac.c:hmac_init_tfm
  - crypto/hmac.c:hmac_finup
  - crypto/hmac.c:hmac_final
  - crypto/hmac.c:hmac_init
  - crypto/hmac.c:hmac_import
  - crypto/hmac.c:hmac_setkey
```
```
In crypto/cts.c (ffffffff814691bd)
Location: include/linux/crypto.h:695
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_init_tfm
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
```
```
In crypto/ctr.c (ffffffff8146a77d)
Location: include/linux/crypto.h:695
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_init_tfm
  - crypto/ctr.c:crypto_rfc3686_crypt
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
```
```
In crypto/gcm.c (ffffffff8146b53e)
Location: include/linux/crypto.h:695
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
```
In crypto/drbg.c (ffffffff81473383)
Location: include/linux/crypto.h:695
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
  - crypto/drbg.c:drbg_init_hash_kernel
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
In crypto/cipher.c (ffffffff81476369)
Location: include/linux/crypto.h:866
Inline: True
Inline callers:
  - crypto/cipher.c:crypto_init_cipher_ops
  - crypto/cipher.c:crypto_init_cipher_ops
  - crypto/cipher.c:cipher_decrypt_unaligned
  - crypto/cipher.c:cipher_encrypt_unaligned
  - crypto/cipher.c:cipher_crypt_unaligned
  - crypto/cipher.c:setkey
  - crypto/cipher.c:setkey
```
```
In crypto/aead.c (ffffffff814788e5)
Location: include/linux/crypto.h:866
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_setkey
```
```
In crypto/ablkcipher.c (ffffffff814791ba)
Location: include/linux/crypto.h:866
Inline: True
Inline callers:
  - crypto/ablkcipher.c:setkey
  - crypto/ablkcipher.c:ablkcipher_walk_phys
  - crypto/ablkcipher.c:ablkcipher_walk_next
```
```
In crypto/blkcipher.c (ffffffff81479ada)
Location: include/linux/crypto.h:866
Inline: True
Inline callers:
  - crypto/blkcipher.c:crypto_init_blkcipher_ops
  - crypto/blkcipher.c:setkey
  - crypto/blkcipher.c:blkcipher_aead_walk_virt_block
  - crypto/blkcipher.c:blkcipher_walk_virt_block
  - crypto/blkcipher.c:blkcipher_walk_phys
  - crypto/blkcipher.c:blkcipher_walk_virt
```
```
In crypto/skcipher.c (ffffffff8147ac3a)
Location: include/linux/crypto.h:866
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_skcipher
```
```
In crypto/seqiv.c (ffffffff8147c07f)
Location: include/linux/crypto.h:866
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/ahash.c (ffffffff8147c645)
Location: include/linux/crypto.h:866
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_op
  - crypto/ahash.c:ahash_save_req
  - crypto/ahash.c:crypto_ahash_setkey
```
```
In crypto/shash.c (ffffffff8147d48c)
Location: include/linux/crypto.h:866
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_digest
  - crypto/shash.c:crypto_shash_finup
  - crypto/shash.c:crypto_shash_final
  - crypto/shash.c:shash_final_unaligned
  - crypto/shash.c:crypto_shash_update
  - crypto/shash.c:shash_update_unaligned
  - crypto/shash.c:crypto_shash_setkey
```
```
In crypto/hmac.c (ffffffff814813b5)
Location: include/linux/crypto.h:866
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_exit_tfm
  - crypto/hmac.c:hmac_init_tfm
  - crypto/hmac.c:hmac_finup
  - crypto/hmac.c:hmac_final
  - crypto/hmac.c:hmac_init
  - crypto/hmac.c:hmac_import
  - crypto/hmac.c:hmac_setkey
```
```
In crypto/cts.c (ffffffff81486b8d)
Location: include/linux/crypto.h:866
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_init_tfm
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
```
```
In crypto/ctr.c (ffffffff81487fdd)
Location: include/linux/crypto.h:866
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_init_tfm
  - crypto/ctr.c:crypto_rfc3686_crypt
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
```
```
In crypto/gcm.c (ffffffff81488bbe)
Location: include/linux/crypto.h:866
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
```
In crypto/drbg.c (ffffffff8148f8fa)
Location: include/linux/crypto.h:866
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
  - crypto/drbg.c:drbg_init_hash_kernel
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
In crypto/cipher.c (ffffffff814a40f9)
Location: include/linux/crypto.h:863
Inline: True
Inline callers:
  - crypto/cipher.c:crypto_init_cipher_ops
  - crypto/cipher.c:crypto_init_cipher_ops
  - crypto/cipher.c:cipher_decrypt_unaligned
  - crypto/cipher.c:cipher_encrypt_unaligned
  - crypto/cipher.c:cipher_crypt_unaligned
  - crypto/cipher.c:setkey
  - crypto/cipher.c:setkey
```
```
In crypto/aead.c (ffffffff814a6c05)
Location: include/linux/crypto.h:863
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_setkey
```
```
In crypto/ablkcipher.c (ffffffff814a77fd)
Location: include/linux/crypto.h:863
Inline: True
Inline callers:
  - crypto/ablkcipher.c:setkey
  - crypto/ablkcipher.c:ablkcipher_walk_phys
  - crypto/ablkcipher.c:ablkcipher_walk_next
```
```
In crypto/blkcipher.c (ffffffff814a7a5a)
Location: include/linux/crypto.h:863
Inline: True
Inline callers:
  - crypto/blkcipher.c:crypto_init_blkcipher_ops
  - crypto/blkcipher.c:setkey
  - crypto/blkcipher.c:blkcipher_aead_walk_virt_block
  - crypto/blkcipher.c:blkcipher_walk_virt_block
  - crypto/blkcipher.c:blkcipher_walk_phys
  - crypto/blkcipher.c:blkcipher_walk_virt
```
```
In crypto/skcipher.c (ffffffff814a9bcd)
Location: include/linux/crypto.h:863
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_skcipher
```
```
In crypto/seqiv.c (ffffffff814aa3e0)
Location: include/linux/crypto.h:863
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/ahash.c (ffffffff814aafb5)
Location: include/linux/crypto.h:863
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_op
  - crypto/ahash.c:ahash_save_req
  - crypto/ahash.c:crypto_ahash_setkey
```
```
In crypto/shash.c (ffffffff814ab78c)
Location: include/linux/crypto.h:863
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_digest
  - crypto/shash.c:crypto_shash_finup
  - crypto/shash.c:crypto_shash_final
  - crypto/shash.c:shash_final_unaligned
  - crypto/shash.c:crypto_shash_update
  - crypto/shash.c:shash_update_unaligned
  - crypto/shash.c:crypto_shash_setkey
```
```
In crypto/hmac.c (ffffffff814af585)
Location: include/linux/crypto.h:863
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_exit_tfm
  - crypto/hmac.c:hmac_init_tfm
  - crypto/hmac.c:hmac_finup
  - crypto/hmac.c:hmac_final
  - crypto/hmac.c:hmac_init
  - crypto/hmac.c:hmac_import
  - crypto/hmac.c:hmac_setkey
```
```
In crypto/cts.c (ffffffff814b4cad)
Location: include/linux/crypto.h:863
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_init_tfm
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
```
```
In crypto/ctr.c (ffffffff814b5bad)
Location: include/linux/crypto.h:863
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_init_tfm
  - crypto/ctr.c:crypto_rfc3686_crypt
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
```
```
In crypto/gcm.c (ffffffff814b6613)
Location: include/linux/crypto.h:863
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
```
In crypto/drbg.c (ffffffff814be28f)
Location: include/linux/crypto.h:863
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
  - crypto/drbg.c:drbg_init_hash_kernel
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
In crypto/cipher.c (ffffffff814bed29)
Location: include/linux/crypto.h:863
Inline: True
Inline callers:
  - crypto/cipher.c:crypto_init_cipher_ops
  - crypto/cipher.c:crypto_init_cipher_ops
  - crypto/cipher.c:cipher_decrypt_unaligned
  - crypto/cipher.c:cipher_encrypt_unaligned
  - crypto/cipher.c:cipher_crypt_unaligned
  - crypto/cipher.c:setkey
  - crypto/cipher.c:setkey
```
```
In crypto/aead.c (ffffffff814c1875)
Location: include/linux/crypto.h:863
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_setkey
```
```
In crypto/ablkcipher.c (ffffffff814c247d)
Location: include/linux/crypto.h:863
Inline: True
Inline callers:
  - crypto/ablkcipher.c:setkey
  - crypto/ablkcipher.c:ablkcipher_walk_phys
  - crypto/ablkcipher.c:ablkcipher_walk_next
```
```
In crypto/blkcipher.c (ffffffff814c26ba)
Location: include/linux/crypto.h:863
Inline: True
Inline callers:
  - crypto/blkcipher.c:crypto_init_blkcipher_ops
  - crypto/blkcipher.c:setkey
  - crypto/blkcipher.c:blkcipher_aead_walk_virt_block
  - crypto/blkcipher.c:blkcipher_walk_virt_block
  - crypto/blkcipher.c:blkcipher_walk_phys
  - crypto/blkcipher.c:blkcipher_walk_virt
```
```
In crypto/skcipher.c (ffffffff814c48bd)
Location: include/linux/crypto.h:863
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_skcipher
```
```
In crypto/seqiv.c (ffffffff814c50a0)
Location: include/linux/crypto.h:863
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/ahash.c (ffffffff814c5c75)
Location: include/linux/crypto.h:863
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_op
  - crypto/ahash.c:ahash_save_req
  - crypto/ahash.c:crypto_ahash_setkey
```
```
In crypto/shash.c (ffffffff814c646c)
Location: include/linux/crypto.h:863
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_digest
  - crypto/shash.c:crypto_shash_finup
  - crypto/shash.c:crypto_shash_final
  - crypto/shash.c:shash_final_unaligned
  - crypto/shash.c:crypto_shash_update
  - crypto/shash.c:shash_update_unaligned
  - crypto/shash.c:crypto_shash_setkey
```
```
In crypto/hmac.c (ffffffff814ca215)
Location: include/linux/crypto.h:863
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_exit_tfm
  - crypto/hmac.c:hmac_init_tfm
  - crypto/hmac.c:hmac_finup
  - crypto/hmac.c:hmac_final
  - crypto/hmac.c:hmac_init
  - crypto/hmac.c:hmac_import
  - crypto/hmac.c:hmac_setkey
```
```
In crypto/cts.c (ffffffff814cd77d)
Location: include/linux/crypto.h:863
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_init_tfm
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
```
```
In crypto/ctr.c (ffffffff814cedad)
Location: include/linux/crypto.h:863
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_init_tfm
  - crypto/ctr.c:crypto_rfc3686_crypt
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
```
```
In crypto/gcm.c (ffffffff814cf833)
Location: include/linux/crypto.h:863
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
```
In crypto/drbg.c (ffffffff814d70df)
Location: include/linux/crypto.h:863
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
  - crypto/drbg.c:drbg_init_hash_kernel
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
In crypto/cipher.c (ffffffff8151f445)
Location: include/linux/crypto.h:682
Inline: True
Inline callers:
  - crypto/cipher.c:crypto_cipher_decrypt_one
  - crypto/cipher.c:crypto_cipher_encrypt_one
  - crypto/cipher.c:crypto_cipher_setkey
  - crypto/cipher.c:setkey_unaligned
```
```
In crypto/aead.c (ffffffff81521d05)
Location: include/linux/crypto.h:682
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_setkey
  - crypto/aead.c:setkey_unaligned
```
```
In crypto/skcipher.c (ffffffff81522909)
Location: include/linux/crypto.h:682
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_skcipher_setkey
  - crypto/skcipher.c:skcipher_setkey_unaligned
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_async
  - crypto/skcipher.c:skcipher_walk_virt
```
```
In crypto/seqiv.c (ffffffff81523fb0)
Location: include/linux/crypto.h:682
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/ahash.c (ffffffff81524565)
Location: include/linux/crypto.h:682
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_op
  - crypto/ahash.c:ahash_save_req
  - crypto/ahash.c:crypto_ahash_setkey
  - crypto/ahash.c:ahash_setkey_unaligned
```
```
In crypto/shash.c (ffffffff81525a57)
Location: include/linux/crypto.h:682
Inline: True
Inline callers:
  - crypto/shash.c:shash_ahash_finup
  - crypto/shash.c:shash_ahash_finup
  - crypto/shash.c:shash_async_final
  - crypto/shash.c:shash_async_update
  - crypto/shash.c:shash_async_setkey
  - crypto/shash.c:crypto_shash_digest
  - crypto/shash.c:crypto_shash_finup
  - crypto/shash.c:crypto_shash_finup
  - crypto/shash.c:shash_final_unaligned
  - crypto/shash.c:shash_update_unaligned
  - crypto/shash.c:shash_setkey_unaligned
```
```
In crypto/hmac.c (ffffffff81529685)
Location: include/linux/crypto.h:682
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_exit_tfm
  - crypto/hmac.c:hmac_init_tfm
  - crypto/hmac.c:hmac_finup
  - crypto/hmac.c:hmac_final
  - crypto/hmac.c:hmac_init
  - crypto/hmac.c:hmac_setkey
```
```
In crypto/cts.c (ffffffff8152cb9d)
Location: include/linux/crypto.h:682
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_init_tfm
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
```
```
In crypto/ctr.c (ffffffff8152e0cd)
Location: include/linux/crypto.h:682
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_init_tfm
  - crypto/ctr.c:crypto_rfc3686_crypt
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
```
```
In crypto/gcm.c (ffffffff8152ea33)
Location: include/linux/crypto.h:682
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
```
In crypto/drbg.c (ffffffff815338ec)
Location: include/linux/crypto.h:682
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
  - crypto/drbg.c:drbg_init_hash_kernel
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
In crypto/cipher.c (ffffffff8153c2a5)
Location: include/linux/crypto.h:718
Inline: True
Inline callers:
  - crypto/cipher.c:crypto_cipher_decrypt_one
  - crypto/cipher.c:crypto_cipher_encrypt_one
  - crypto/cipher.c:crypto_cipher_setkey
  - crypto/cipher.c:setkey_unaligned
```
```
In crypto/aead.c (ffffffff8153eb55)
Location: include/linux/crypto.h:718
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_setkey
  - crypto/aead.c:setkey_unaligned
```
```
In crypto/skcipher.c (ffffffff8153f7c9)
Location: include/linux/crypto.h:718
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_skcipher_setkey
  - crypto/skcipher.c:skcipher_setkey_unaligned
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_async
  - crypto/skcipher.c:skcipher_walk_virt
```
```
In crypto/seqiv.c (ffffffff81540eba)
Location: include/linux/crypto.h:718
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/ahash.c (ffffffff81541435)
Location: include/linux/crypto.h:718
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_op
  - crypto/ahash.c:ahash_save_req
  - crypto/ahash.c:crypto_ahash_setkey
  - crypto/ahash.c:ahash_setkey_unaligned
```
```
In crypto/shash.c (ffffffff81542987)
Location: include/linux/crypto.h:718
Inline: True
Inline callers:
  - crypto/shash.c:shash_ahash_finup
  - crypto/shash.c:shash_ahash_finup
  - crypto/shash.c:shash_async_final
  - crypto/shash.c:shash_async_update
  - crypto/shash.c:shash_async_setkey
  - crypto/shash.c:crypto_shash_digest
  - crypto/shash.c:crypto_shash_finup
  - crypto/shash.c:crypto_shash_finup
  - crypto/shash.c:shash_final_unaligned
  - crypto/shash.c:shash_update_unaligned
  - crypto/shash.c:shash_setkey_unaligned
```
```
In crypto/hmac.c (ffffffff81546635)
Location: include/linux/crypto.h:718
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_exit_tfm
  - crypto/hmac.c:hmac_init_tfm
  - crypto/hmac.c:hmac_finup
  - crypto/hmac.c:hmac_final
  - crypto/hmac.c:hmac_init
  - crypto/hmac.c:hmac_setkey
```
```
In crypto/cts.c (ffffffff81549c0d)
Location: include/linux/crypto.h:718
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_init_tfm
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
```
```
In crypto/ctr.c (ffffffff8154afcd)
Location: include/linux/crypto.h:718
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_init_tfm
  - crypto/ctr.c:crypto_rfc3686_crypt
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
```
```
In crypto/gcm.c (ffffffff8154b9b3)
Location: include/linux/crypto.h:718
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
```
In crypto/drbg.c (ffffffff8155083c)
Location: include/linux/crypto.h:718
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
  - crypto/drbg.c:drbg_init_hash_kernel
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
In crypto/cipher.c (ffffffff81544995)
Location: include/linux/crypto.h:714
Inline: True
Inline callers:
  - crypto/cipher.c:crypto_cipher_decrypt_one
  - crypto/cipher.c:crypto_cipher_encrypt_one
  - crypto/cipher.c:crypto_cipher_setkey
  - crypto/cipher.c:setkey_unaligned
```
```
In crypto/aead.c (ffffffff81547205)
Location: include/linux/crypto.h:714
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_setkey
  - crypto/aead.c:setkey_unaligned
```
```
In crypto/skcipher.c (ffffffff81547d59)
Location: include/linux/crypto.h:714
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_skcipher_setkey
  - crypto/skcipher.c:skcipher_setkey_unaligned
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_async
  - crypto/skcipher.c:skcipher_walk_virt
```
```
In crypto/seqiv.c (ffffffff81549520)
Location: include/linux/crypto.h:714
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/ahash.c (ffffffff81549a65)
Location: include/linux/crypto.h:714
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_op
  - crypto/ahash.c:ahash_save_req
  - crypto/ahash.c:crypto_ahash_setkey
  - crypto/ahash.c:ahash_setkey_unaligned
```
```
In crypto/shash.c (ffffffff8154b027)
Location: include/linux/crypto.h:714
Inline: True
Inline callers:
  - crypto/shash.c:shash_ahash_finup
  - crypto/shash.c:shash_ahash_finup
  - crypto/shash.c:shash_async_final
  - crypto/shash.c:shash_async_update
  - crypto/shash.c:shash_async_setkey
  - crypto/shash.c:crypto_shash_digest
  - crypto/shash.c:crypto_shash_finup
  - crypto/shash.c:crypto_shash_finup
  - crypto/shash.c:shash_final_unaligned
  - crypto/shash.c:shash_update_unaligned
  - crypto/shash.c:shash_setkey_unaligned
```
```
In crypto/hmac.c (ffffffff8154ecf5)
Location: include/linux/crypto.h:714
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_exit_tfm
  - crypto/hmac.c:hmac_init_tfm
  - crypto/hmac.c:hmac_finup
  - crypto/hmac.c:hmac_final
  - crypto/hmac.c:hmac_init
  - crypto/hmac.c:hmac_setkey
```
```
In crypto/cts.c (ffffffff8155224d)
Location: include/linux/crypto.h:714
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_init_tfm
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
```
```
In crypto/ctr.c (ffffffff815535ed)
Location: include/linux/crypto.h:714
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_init_tfm
  - crypto/ctr.c:crypto_rfc3686_crypt
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
```
```
In crypto/gcm.c (ffffffff81553fb3)
Location: include/linux/crypto.h:714
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
```
In crypto/drbg.c (ffffffff8155901c)
Location: include/linux/crypto.h:714
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
  - crypto/drbg.c:drbg_init_hash_kernel
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
In crypto/cipher.c (ffffffff815a5135)
Location: include/linux/crypto.h:688
Inline: True
Inline callers:
  - crypto/cipher.c:crypto_cipher_decrypt_one
  - crypto/cipher.c:crypto_cipher_encrypt_one
  - crypto/cipher.c:crypto_cipher_setkey
  - crypto/cipher.c:setkey_unaligned
```
```
In crypto/aead.c (ffffffff815a79e5)
Location: include/linux/crypto.h:688
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_setkey
  - crypto/aead.c:setkey_unaligned
```
```
In crypto/skcipher.c (ffffffff815a8539)
Location: include/linux/crypto.h:688
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_skcipher_setkey
  - crypto/skcipher.c:skcipher_setkey_unaligned
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_async
  - crypto/skcipher.c:skcipher_walk_virt
```
```
In crypto/seqiv.c (ffffffff815a9d00)
Location: include/linux/crypto.h:688
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/ahash.c (ffffffff815aa245)
Location: include/linux/crypto.h:688
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_op
  - crypto/ahash.c:ahash_save_req
  - crypto/ahash.c:crypto_ahash_setkey
  - crypto/ahash.c:ahash_setkey_unaligned
```
```
In crypto/shash.c (ffffffff815ab807)
Location: include/linux/crypto.h:688
Inline: True
Inline callers:
  - crypto/shash.c:shash_ahash_finup
  - crypto/shash.c:shash_ahash_finup
  - crypto/shash.c:shash_async_final
  - crypto/shash.c:shash_async_update
  - crypto/shash.c:shash_async_setkey
  - crypto/shash.c:crypto_shash_digest
  - crypto/shash.c:crypto_shash_finup
  - crypto/shash.c:crypto_shash_finup
  - crypto/shash.c:shash_final_unaligned
  - crypto/shash.c:shash_update_unaligned
  - crypto/shash.c:shash_setkey_unaligned
```
```
In crypto/hmac.c (ffffffff815af645)
Location: include/linux/crypto.h:688
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_exit_tfm
  - crypto/hmac.c:hmac_init_tfm
  - crypto/hmac.c:hmac_finup
  - crypto/hmac.c:hmac_final
  - crypto/hmac.c:hmac_init
  - crypto/hmac.c:hmac_setkey
```
```
In crypto/cts.c (ffffffff815b324d)
Location: include/linux/crypto.h:688
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_init_tfm
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
```
```
In crypto/ctr.c (ffffffff815b461d)
Location: include/linux/crypto.h:688
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_init_tfm
  - crypto/ctr.c:crypto_rfc3686_crypt
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
```
```
In crypto/gcm.c (ffffffff815b4fe3)
Location: include/linux/crypto.h:688
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
```
In crypto/drbg.c (ffffffff815ba2dc)
Location: include/linux/crypto.h:688
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
  - crypto/drbg.c:drbg_init_hash_kernel
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
In crypto/cipher.c (ffffffff8164bdf5)
Location: include/linux/crypto.h:697
Inline: True
Inline callers:
  - crypto/cipher.c:crypto_cipher_decrypt_one
  - crypto/cipher.c:crypto_cipher_encrypt_one
  - crypto/cipher.c:crypto_cipher_setkey
  - crypto/cipher.c:setkey_unaligned
```
```
In crypto/aead.c (ffffffff8164ed35)
Location: include/linux/crypto.h:697
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_setkey
  - crypto/aead.c:setkey_unaligned
```
```
In crypto/skcipher.c (ffffffff8164fea9)
Location: include/linux/crypto.h:697
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_skcipher_setkey
  - crypto/skcipher.c:skcipher_setkey_unaligned
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_async
  - crypto/skcipher.c:skcipher_walk_virt
```
```
In crypto/seqiv.c (ffffffff81651200)
Location: include/linux/crypto.h:697
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/ahash.c (ffffffff81651695)
Location: include/linux/crypto.h:697
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_op
  - crypto/ahash.c:ahash_save_req
  - crypto/ahash.c:crypto_ahash_setkey
  - crypto/ahash.c:ahash_setkey_unaligned
```
```
In crypto/shash.c (ffffffff816530cb)
Location: include/linux/crypto.h:697
Inline: True
Inline callers:
  - crypto/shash.c:shash_ahash_finup
  - crypto/shash.c:shash_ahash_finup
  - crypto/shash.c:shash_async_final
  - crypto/shash.c:shash_async_update
  - crypto/shash.c:shash_async_setkey
  - crypto/shash.c:crypto_shash_digest
  - crypto/shash.c:crypto_shash_finup
  - crypto/shash.c:crypto_shash_finup
  - crypto/shash.c:shash_final_unaligned
  - crypto/shash.c:shash_update_unaligned
  - crypto/shash.c:shash_setkey_unaligned
```
```
In crypto/hmac.c (ffffffff81657d95)
Location: include/linux/crypto.h:697
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_exit_tfm
  - crypto/hmac.c:hmac_init_tfm
  - crypto/hmac.c:hmac_finup
  - crypto/hmac.c:hmac_final
  - crypto/hmac.c:hmac_init
  - crypto/hmac.c:hmac_setkey
```
```
In crypto/cts.c (ffffffff8165c22d)
Location: include/linux/crypto.h:697
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_init_tfm
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
```
```
In crypto/ctr.c (ffffffff8165d4cd)
Location: include/linux/crypto.h:697
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_init_tfm
  - crypto/ctr.c:crypto_rfc3686_crypt
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
```
```
In crypto/gcm.c (ffffffff8165e065)
Location: include/linux/crypto.h:697
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
```
In crypto/drbg.c (ffffffff81663370)
Location: include/linux/crypto.h:697
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
  - crypto/drbg.c:drbg_init_hash_kernel
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
In crypto/cipher.c (ffffffff81704dea)
Location: include/linux/crypto.h:697
Inline: True
Inline callers:
  - crypto/cipher.c:cipher_crypt_one
  - crypto/cipher.c:crypto_cipher_setkey
  - crypto/cipher.c:setkey_unaligned
```
```
In crypto/aead.c (ffffffff817086c5)
Location: include/linux/crypto.h:697
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_setkey
  - crypto/aead.c:setkey_unaligned
```
```
In crypto/skcipher.c (ffffffff817095d9)
Location: include/linux/crypto.h:697
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_skcipher_setkey
  - crypto/skcipher.c:skcipher_setkey_unaligned
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_async
  - crypto/skcipher.c:skcipher_walk_virt
```
```
In crypto/seqiv.c (ffffffff8170aa80)
Location: include/linux/crypto.h:697
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/ahash.c (ffffffff8170b375)
Location: include/linux/crypto.h:697
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_op
  - crypto/ahash.c:ahash_save_req
  - crypto/ahash.c:crypto_ahash_setkey
  - crypto/ahash.c:ahash_setkey_unaligned
```
```
In crypto/shash.c (ffffffff8170cdab)
Location: include/linux/crypto.h:697
Inline: True
Inline callers:
  - crypto/shash.c:shash_ahash_finup
  - crypto/shash.c:shash_ahash_finup
  - crypto/shash.c:shash_async_final
  - crypto/shash.c:shash_async_update
  - crypto/shash.c:shash_async_setkey
  - crypto/shash.c:crypto_shash_digest
  - crypto/shash.c:crypto_shash_finup
  - crypto/shash.c:crypto_shash_finup
  - crypto/shash.c:shash_final_unaligned
  - crypto/shash.c:shash_update_unaligned
  - crypto/shash.c:shash_setkey_unaligned
```
```
In crypto/hmac.c (ffffffff817120b5)
Location: include/linux/crypto.h:697
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_exit_tfm
  - crypto/hmac.c:hmac_init_tfm
  - crypto/hmac.c:hmac_finup
  - crypto/hmac.c:hmac_final
  - crypto/hmac.c:hmac_init
  - crypto/hmac.c:hmac_setkey
```
```
In crypto/cts.c (ffffffff81715bed)
Location: include/linux/crypto.h:697
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_init_tfm
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
```
```
In crypto/ctr.c (ffffffff81716ffd)
Location: include/linux/crypto.h:697
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_init_tfm
  - crypto/ctr.c:crypto_rfc3686_crypt
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
```
```
In crypto/gcm.c (ffffffff817179b5)
Location: include/linux/crypto.h:697
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
```
In crypto/drbg.c (ffffffff8171d600)
Location: include/linux/crypto.h:697
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
  - crypto/drbg.c:drbg_init_hash_kernel
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
In crypto/cipher.c (ffffffff8173f0ba)
Location: include/linux/crypto.h:470
Inline: True
Inline callers:
  - crypto/cipher.c:cipher_crypt_one
  - crypto/cipher.c:crypto_cipher_setkey
  - crypto/cipher.c:setkey_unaligned
```
```
In crypto/aead.c (ffffffff81741e35)
Location: include/linux/crypto.h:470
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_setkey
  - crypto/aead.c:setkey_unaligned
```
```
In crypto/skcipher.c (ffffffff81742e19)
Location: include/linux/crypto.h:470
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_skcipher_setkey
  - crypto/skcipher.c:skcipher_setkey_unaligned
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_async
  - crypto/skcipher.c:skcipher_walk_virt
```
```
In crypto/seqiv.c (ffffffff817442d0)
Location: include/linux/crypto.h:470
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/ahash.c (ffffffff8174501c)
Location: include/linux/crypto.h:470
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_op
  - crypto/ahash.c:ahash_save_req
  - crypto/ahash.c:crypto_ahash_setkey
  - crypto/ahash.c:ahash_setkey_unaligned
```
```
In crypto/shash.c (ffffffff81746a64)
Location: include/linux/crypto.h:470
Inline: True
Inline callers:
  - crypto/shash.c:shash_async_setkey
  - crypto/shash.c:crypto_shash_digest
  - crypto/shash.c:crypto_shash_finup
  - crypto/shash.c:crypto_shash_final
  - crypto/shash.c:shash_final_unaligned
  - crypto/shash.c:crypto_shash_update
  - crypto/shash.c:shash_update_unaligned
  - crypto/shash.c:shash_setkey_unaligned
```
```
In crypto/hmac.c (ffffffff8174cd85)
Location: include/linux/crypto.h:470
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_exit_tfm
  - crypto/hmac.c:hmac_clone_tfm
  - crypto/hmac.c:hmac_clone_tfm
  - crypto/hmac.c:hmac_init_tfm
  - crypto/hmac.c:hmac_finup
  - crypto/hmac.c:hmac_final
  - crypto/hmac.c:hmac_init
  - crypto/hmac.c:hmac_setkey
```
```
In crypto/cts.c (ffffffff8175149d)
Location: include/linux/crypto.h:470
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_init_tfm
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
```
```
In crypto/ctr.c (ffffffff817528fd)
Location: include/linux/crypto.h:470
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_init_tfm
  - crypto/ctr.c:crypto_rfc3686_crypt
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
```
```
In crypto/gcm.c (ffffffff81753395)
Location: include/linux/crypto.h:470
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
```
In crypto/drbg.c (ffffffff81758ee0)
Location: include/linux/crypto.h:470
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
  - crypto/drbg.c:drbg_init_hash_kernel
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
In crypto/cipher.c (ffffffff8177ff3a)
Location: include/linux/crypto.h:470
Inline: True
Inline callers:
  - crypto/cipher.c:cipher_crypt_one
  - crypto/cipher.c:crypto_cipher_setkey
  - crypto/cipher.c:setkey_unaligned
```
```
In crypto/aead.c (ffffffff81782d15)
Location: include/linux/crypto.h:470
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_setkey
  - crypto/aead.c:setkey_unaligned
```
```
In crypto/lskcipher.c (ffffffff817845c5)
Location: include/linux/crypto.h:470
Inline: True
Inline callers:
  - crypto/lskcipher.c:lskcipher_setkey_simple
  - crypto/lskcipher.c:crypto_lskcipher_crypt_sg
  - crypto/lskcipher.c:crypto_lskcipher_crypt
  - crypto/lskcipher.c:lskcipher_setkey_unaligned
```
```
In crypto/skcipher.c (ffffffff81785414)
Location: include/linux/crypto.h:470
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/skcipher.c:crypto_skcipher_import
  - crypto/skcipher.c:crypto_skcipher_export
  - crypto/skcipher.c:crypto_skcipher_setkey
  - crypto/skcipher.c:skcipher_setkey_unaligned
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_skcipher
```
```
In crypto/seqiv.c (ffffffff81786890)
Location: include/linux/crypto.h:470
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/cts.c (ffffffff817932ed)
Location: include/linux/crypto.h:470
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_init_tfm
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
```
```
In crypto/ctr.c (ffffffff8179486d)
Location: include/linux/crypto.h:470
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_init_tfm
  - crypto/ctr.c:crypto_rfc3686_crypt
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
```
```
In crypto/gcm.c (ffffffff81795265)
Location: include/linux/crypto.h:470
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
```
In crypto/drbg.c (ffffffff8179ade0)
Location: include/linux/crypto.h:470
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
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
In crypto/cipher.c (ffff8000105b7e60)
Location: include/linux/crypto.h:863
Inline: True
Inline callers:
  - crypto/cipher.c:crypto_init_cipher_ops
  - crypto/cipher.c:crypto_init_cipher_ops
  - crypto/cipher.c:cipher_decrypt_unaligned
  - crypto/cipher.c:cipher_encrypt_unaligned
  - crypto/cipher.c:cipher_crypt_unaligned
  - crypto/cipher.c:setkey
  - crypto/cipher.c:setkey
```
```
In crypto/aead.c (ffff8000105bbf3c)
Location: include/linux/crypto.h:863
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_setkey
```
```
In crypto/ablkcipher.c (ffff8000105bc484)
Location: include/linux/crypto.h:863
Inline: True
Inline callers:
  - crypto/ablkcipher.c:setkey
  - crypto/ablkcipher.c:ablkcipher_walk_phys
  - crypto/ablkcipher.c:ablkcipher_walk_next
```
```
In crypto/blkcipher.c (ffff8000105bcd48)
Location: include/linux/crypto.h:863
Inline: True
Inline callers:
  - crypto/blkcipher.c:crypto_init_blkcipher_ops
  - crypto/blkcipher.c:setkey
  - crypto/blkcipher.c:blkcipher_aead_walk_virt_block
  - crypto/blkcipher.c:blkcipher_walk_virt_block
  - crypto/blkcipher.c:blkcipher_walk_phys
  - crypto/blkcipher.c:blkcipher_walk_virt
```
```
In crypto/skcipher.c (ffff8000105bebcc)
Location: include/linux/crypto.h:863
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_skcipher
```
```
In crypto/seqiv.c (ffff8000105bfc2c)
Location: include/linux/crypto.h:863
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/ahash.c (ffff8000105c0aa0)
Location: include/linux/crypto.h:863
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_op
  - crypto/ahash.c:ahash_save_req
  - crypto/ahash.c:crypto_ahash_setkey
```
```
In crypto/shash.c (ffff8000105c16e4)
Location: include/linux/crypto.h:863
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_digest
  - crypto/shash.c:crypto_shash_finup
  - crypto/shash.c:crypto_shash_final
  - crypto/shash.c:shash_final_unaligned
  - crypto/shash.c:crypto_shash_update
  - crypto/shash.c:shash_update_unaligned
  - crypto/shash.c:crypto_shash_setkey
```
```
In crypto/hmac.c (ffff8000105c5f00)
Location: include/linux/crypto.h:863
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_exit_tfm
  - crypto/hmac.c:hmac_init_tfm
  - crypto/hmac.c:hmac_finup
  - crypto/hmac.c:hmac_final
  - crypto/hmac.c:hmac_init
  - crypto/hmac.c:hmac_import
  - crypto/hmac.c:hmac_setkey
```
```
In crypto/cts.c (ffff8000105c9668)
Location: include/linux/crypto.h:863
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_init_tfm
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
```
```
In crypto/ctr.c (ffff8000105cad08)
Location: include/linux/crypto.h:863
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_init_tfm
  - crypto/ctr.c:crypto_rfc3686_crypt
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
```
```
In crypto/gcm.c (ffff8000105cb930)
Location: include/linux/crypto.h:863
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
```
In crypto/drbg.c (ffff8000105d1580)
Location: include/linux/crypto.h:863
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
  - crypto/drbg.c:drbg_init_hash_kernel
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
In crypto/cipher.c (c0766b6c)
Location: include/linux/crypto.h:863
Inline: True
Inline callers:
  - crypto/cipher.c:crypto_init_cipher_ops
  - crypto/cipher.c:crypto_init_cipher_ops
  - crypto/cipher.c:cipher_decrypt_unaligned
  - crypto/cipher.c:cipher_encrypt_unaligned
  - crypto/cipher.c:cipher_crypt_unaligned
  - crypto/cipher.c:setkey
  - crypto/cipher.c:setkey
```
```
In crypto/aead.c (c076a000)
Location: include/linux/crypto.h:863
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_setkey
```
```
In crypto/ablkcipher.c (c076aa68)
Location: include/linux/crypto.h:863
Inline: True
Inline callers:
  - crypto/ablkcipher.c:setkey
  - crypto/ablkcipher.c:ablkcipher_walk_phys
  - crypto/ablkcipher.c:ablkcipher_walk_next
```
```
In crypto/blkcipher.c (c076acec)
Location: include/linux/crypto.h:863
Inline: True
Inline callers:
  - crypto/blkcipher.c:crypto_init_blkcipher_ops
  - crypto/blkcipher.c:setkey
  - crypto/blkcipher.c:blkcipher_aead_walk_virt_block
  - crypto/blkcipher.c:blkcipher_walk_virt_block
  - crypto/blkcipher.c:blkcipher_walk_phys
  - crypto/blkcipher.c:blkcipher_walk_virt
```
```
In crypto/skcipher.c (c076d03c)
Location: include/linux/crypto.h:863
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_skcipher
```
```
In crypto/seqiv.c (c076d878)
Location: include/linux/crypto.h:863
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/ahash.c (c076e564)
Location: include/linux/crypto.h:863
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_op
  - crypto/ahash.c:ahash_save_req
  - crypto/ahash.c:crypto_ahash_setkey
```
```
In crypto/shash.c (c076ee1c)
Location: include/linux/crypto.h:863
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_digest
  - crypto/shash.c:crypto_shash_finup
  - crypto/shash.c:crypto_shash_final
  - crypto/shash.c:shash_final_unaligned
  - crypto/shash.c:crypto_shash_update
  - crypto/shash.c:shash_update_unaligned
  - crypto/shash.c:crypto_shash_setkey
```
```
In crypto/hmac.c (c0772c08)
Location: include/linux/crypto.h:863
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_exit_tfm
  - crypto/hmac.c:hmac_init_tfm
  - crypto/hmac.c:hmac_finup
  - crypto/hmac.c:hmac_final
  - crypto/hmac.c:hmac_init
  - crypto/hmac.c:hmac_import
  - crypto/hmac.c:hmac_setkey
```
```
In crypto/cts.c (c0777208)
Location: include/linux/crypto.h:863
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_init_tfm
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
```
```
In crypto/ctr.c (c07788d4)
Location: include/linux/crypto.h:863
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_init_tfm
  - crypto/ctr.c:crypto_rfc3686_crypt
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
```
```
In crypto/gcm.c (c0779368)
Location: include/linux/crypto.h:863
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
```
In crypto/drbg.c (c07804f8)
Location: include/linux/crypto.h:863
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
  - crypto/drbg.c:drbg_init_hash_kernel
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
In crypto/cipher.c (c00000000073cf78)
Location: include/linux/crypto.h:863
Inline: True
Inline callers:
  - crypto/cipher.c:crypto_init_cipher_ops
  - crypto/cipher.c:crypto_init_cipher_ops
  - crypto/cipher.c:cipher_decrypt_unaligned
  - crypto/cipher.c:cipher_encrypt_unaligned
  - crypto/cipher.c:cipher_crypt_unaligned
  - crypto/cipher.c:setkey
  - crypto/cipher.c:setkey_unaligned
```
```
In crypto/aead.c (c000000000742838)
Location: include/linux/crypto.h:863
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_setkey
```
```
In crypto/ablkcipher.c (c000000000743a98)
Location: include/linux/crypto.h:863
Inline: True
Inline callers:
  - crypto/ablkcipher.c:setkey
  - crypto/ablkcipher.c:ablkcipher_walk_phys
  - crypto/ablkcipher.c:ablkcipher_walk_next
```
```
In crypto/blkcipher.c (c000000000743df0)
Location: include/linux/crypto.h:863
Inline: True
Inline callers:
  - crypto/blkcipher.c:crypto_init_blkcipher_ops
  - crypto/blkcipher.c:setkey
  - crypto/blkcipher.c:blkcipher_aead_walk_virt_block
  - crypto/blkcipher.c:blkcipher_walk_virt_block
  - crypto/blkcipher.c:blkcipher_walk_phys
  - crypto/blkcipher.c:blkcipher_walk_virt
```
```
In crypto/skcipher.c (c000000000746f28)
Location: include/linux/crypto.h:863
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_skcipher
```
```
In crypto/seqiv.c (c000000000747a84)
Location: include/linux/crypto.h:863
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/ahash.c (c000000000748dd0)
Location: include/linux/crypto.h:863
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_op
  - crypto/ahash.c:ahash_save_req
  - crypto/ahash.c:crypto_ahash_setkey
```
```
In crypto/shash.c (c000000000749b4c)
Location: include/linux/crypto.h:863
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_digest
  - crypto/shash.c:crypto_shash_finup
  - crypto/shash.c:crypto_shash_final
  - crypto/shash.c:shash_final_unaligned
  - crypto/shash.c:crypto_shash_update
  - crypto/shash.c:shash_update_unaligned
  - crypto/shash.c:crypto_shash_setkey
```
```
In crypto/hmac.c (c00000000074f92c)
Location: include/linux/crypto.h:863
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_exit_tfm
  - crypto/hmac.c:hmac_init_tfm
  - crypto/hmac.c:hmac_finup
  - crypto/hmac.c:hmac_final
  - crypto/hmac.c:hmac_init
  - crypto/hmac.c:hmac_import
  - crypto/hmac.c:hmac_setkey
```
```
In crypto/cts.c (c000000000753cc8)
Location: include/linux/crypto.h:863
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_init_tfm
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
```
```
In crypto/ctr.c (c000000000755b38)
Location: include/linux/crypto.h:863
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_init_tfm
  - crypto/ctr.c:crypto_rfc3686_crypt
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
```
```
In crypto/gcm.c (c000000000756a78)
Location: include/linux/crypto.h:863
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
```
In crypto/drbg.c (c00000000075fd24)
Location: include/linux/crypto.h:863
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
  - crypto/drbg.c:drbg_init_hash_kernel
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
In crypto/cipher.c (ffffffe0003fe59c)
Location: include/linux/crypto.h:863
Inline: True
Inline callers:
  - crypto/cipher.c:crypto_init_cipher_ops
  - crypto/cipher.c:crypto_init_cipher_ops
  - crypto/cipher.c:cipher_decrypt_unaligned
  - crypto/cipher.c:cipher_encrypt_unaligned
  - crypto/cipher.c:cipher_crypt_unaligned
  - crypto/cipher.c:setkey
  - crypto/cipher.c:setkey
```
```
In crypto/aead.c (ffffffe00040171c)
Location: include/linux/crypto.h:863
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_setkey
```
```
In crypto/ablkcipher.c (ffffffe000401d62)
Location: include/linux/crypto.h:863
Inline: True
Inline callers:
  - crypto/ablkcipher.c:setkey
  - crypto/ablkcipher.c:ablkcipher_walk_phys
  - crypto/ablkcipher.c:ablkcipher_walk_next
```
```
In crypto/blkcipher.c (ffffffe0004024a4)
Location: include/linux/crypto.h:863
Inline: True
Inline callers:
  - crypto/blkcipher.c:crypto_init_blkcipher_ops
  - crypto/blkcipher.c:setkey
  - crypto/blkcipher.c:blkcipher_aead_walk_virt_block
  - crypto/blkcipher.c:blkcipher_walk_virt_block
  - crypto/blkcipher.c:blkcipher_walk_phys
  - crypto/blkcipher.c:blkcipher_walk_virt
```
```
In crypto/skcipher.c (ffffffe000403dae)
Location: include/linux/crypto.h:863
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_skcipher
```
```
In crypto/seqiv.c (ffffffe000404c8e)
Location: include/linux/crypto.h:863
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/ahash.c (ffffffe000405966)
Location: include/linux/crypto.h:863
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_op
  - crypto/ahash.c:ahash_save_req
  - crypto/ahash.c:crypto_ahash_setkey
```
```
In crypto/shash.c (ffffffe00040637e)
Location: include/linux/crypto.h:863
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_digest
  - crypto/shash.c:crypto_shash_finup
  - crypto/shash.c:crypto_shash_final
  - crypto/shash.c:shash_final_unaligned
  - crypto/shash.c:crypto_shash_update
  - crypto/shash.c:shash_update_unaligned
  - crypto/shash.c:crypto_shash_setkey
```
```
In crypto/hmac.c (ffffffe000409f9c)
Location: include/linux/crypto.h:863
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_exit_tfm
  - crypto/hmac.c:hmac_init_tfm
  - crypto/hmac.c:hmac_finup
  - crypto/hmac.c:hmac_final
  - crypto/hmac.c:hmac_init
  - crypto/hmac.c:hmac_import
  - crypto/hmac.c:hmac_setkey
```
```
In crypto/cts.c (ffffffe00040e334)
Location: include/linux/crypto.h:863
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_init_tfm
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
```
```
In crypto/ctr.c (ffffffe00040f1fa)
Location: include/linux/crypto.h:863
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_init_tfm
  - crypto/ctr.c:crypto_rfc3686_crypt
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
```
```
In crypto/gcm.c (ffffffe00040fc7c)
Location: include/linux/crypto.h:863
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
```
In crypto/drbg.c (ffffffe0004162fc)
Location: include/linux/crypto.h:863
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
  - crypto/drbg.c:drbg_init_hash_kernel
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
In crypto/cipher.c (ffffffff814b7309)
Location: include/linux/crypto.h:863
Inline: True
Inline callers:
  - crypto/cipher.c:crypto_init_cipher_ops
  - crypto/cipher.c:crypto_init_cipher_ops
  - crypto/cipher.c:cipher_decrypt_unaligned
  - crypto/cipher.c:cipher_encrypt_unaligned
  - crypto/cipher.c:cipher_crypt_unaligned
  - crypto/cipher.c:setkey
  - crypto/cipher.c:setkey
```
```
In crypto/aead.c (ffffffff814b9e55)
Location: include/linux/crypto.h:863
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_setkey
```
```
In crypto/ablkcipher.c (ffffffff814baa5d)
Location: include/linux/crypto.h:863
Inline: True
Inline callers:
  - crypto/ablkcipher.c:setkey
  - crypto/ablkcipher.c:ablkcipher_walk_phys
  - crypto/ablkcipher.c:ablkcipher_walk_next
```
```
In crypto/blkcipher.c (ffffffff814bac9a)
Location: include/linux/crypto.h:863
Inline: True
Inline callers:
  - crypto/blkcipher.c:crypto_init_blkcipher_ops
  - crypto/blkcipher.c:setkey
  - crypto/blkcipher.c:blkcipher_aead_walk_virt_block
  - crypto/blkcipher.c:blkcipher_walk_virt_block
  - crypto/blkcipher.c:blkcipher_walk_phys
  - crypto/blkcipher.c:blkcipher_walk_virt
```
```
In crypto/skcipher.c (ffffffff814bce9d)
Location: include/linux/crypto.h:863
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_skcipher
```
```
In crypto/seqiv.c (ffffffff814bd680)
Location: include/linux/crypto.h:863
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/ahash.c (ffffffff814be255)
Location: include/linux/crypto.h:863
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_op
  - crypto/ahash.c:ahash_save_req
  - crypto/ahash.c:crypto_ahash_setkey
```
```
In crypto/shash.c (ffffffff814bea4c)
Location: include/linux/crypto.h:863
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_digest
  - crypto/shash.c:crypto_shash_finup
  - crypto/shash.c:crypto_shash_final
  - crypto/shash.c:shash_final_unaligned
  - crypto/shash.c:crypto_shash_update
  - crypto/shash.c:shash_update_unaligned
  - crypto/shash.c:crypto_shash_setkey
```
```
In crypto/hmac.c (ffffffff814c27f5)
Location: include/linux/crypto.h:863
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_exit_tfm
  - crypto/hmac.c:hmac_init_tfm
  - crypto/hmac.c:hmac_finup
  - crypto/hmac.c:hmac_final
  - crypto/hmac.c:hmac_init
  - crypto/hmac.c:hmac_import
  - crypto/hmac.c:hmac_setkey
```
```
In crypto/cts.c (ffffffff814c5d5d)
Location: include/linux/crypto.h:863
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_init_tfm
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
```
```
In crypto/ctr.c (ffffffff814c738d)
Location: include/linux/crypto.h:863
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_init_tfm
  - crypto/ctr.c:crypto_rfc3686_crypt
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
```
```
In crypto/gcm.c (ffffffff814c7e13)
Location: include/linux/crypto.h:863
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
```
In crypto/drbg.c (ffffffff814cf6bf)
Location: include/linux/crypto.h:863
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
  - crypto/drbg.c:drbg_init_hash_kernel
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
In crypto/cipher.c (ffffffff814a7d29)
Location: include/linux/crypto.h:863
Inline: True
Inline callers:
  - crypto/cipher.c:crypto_init_cipher_ops
  - crypto/cipher.c:crypto_init_cipher_ops
  - crypto/cipher.c:cipher_decrypt_unaligned
  - crypto/cipher.c:cipher_encrypt_unaligned
  - crypto/cipher.c:cipher_crypt_unaligned
  - crypto/cipher.c:setkey
  - crypto/cipher.c:setkey
```
```
In crypto/aead.c (ffffffff814aa875)
Location: include/linux/crypto.h:863
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_setkey
```
```
In crypto/ablkcipher.c (ffffffff814ab47d)
Location: include/linux/crypto.h:863
Inline: True
Inline callers:
  - crypto/ablkcipher.c:setkey
  - crypto/ablkcipher.c:ablkcipher_walk_phys
  - crypto/ablkcipher.c:ablkcipher_walk_next
```
```
In crypto/blkcipher.c (ffffffff814ab6ba)
Location: include/linux/crypto.h:863
Inline: True
Inline callers:
  - crypto/blkcipher.c:crypto_init_blkcipher_ops
  - crypto/blkcipher.c:setkey
  - crypto/blkcipher.c:blkcipher_aead_walk_virt_block
  - crypto/blkcipher.c:blkcipher_walk_virt_block
  - crypto/blkcipher.c:blkcipher_walk_phys
  - crypto/blkcipher.c:blkcipher_walk_virt
```
```
In crypto/skcipher.c (ffffffff814ad8bd)
Location: include/linux/crypto.h:863
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_skcipher
```
```
In crypto/seqiv.c (ffffffff814ae0a0)
Location: include/linux/crypto.h:863
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/ahash.c (ffffffff814aec75)
Location: include/linux/crypto.h:863
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_op
  - crypto/ahash.c:ahash_save_req
  - crypto/ahash.c:crypto_ahash_setkey
```
```
In crypto/shash.c (ffffffff814af46c)
Location: include/linux/crypto.h:863
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_digest
  - crypto/shash.c:crypto_shash_finup
  - crypto/shash.c:crypto_shash_final
  - crypto/shash.c:shash_final_unaligned
  - crypto/shash.c:crypto_shash_update
  - crypto/shash.c:shash_update_unaligned
  - crypto/shash.c:crypto_shash_setkey
```
```
In crypto/hmac.c (ffffffff814b3215)
Location: include/linux/crypto.h:863
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_exit_tfm
  - crypto/hmac.c:hmac_init_tfm
  - crypto/hmac.c:hmac_finup
  - crypto/hmac.c:hmac_final
  - crypto/hmac.c:hmac_init
  - crypto/hmac.c:hmac_import
  - crypto/hmac.c:hmac_setkey
```
```
In crypto/cts.c (ffffffff814b677d)
Location: include/linux/crypto.h:863
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_init_tfm
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
```
```
In crypto/ctr.c (ffffffff814b7dad)
Location: include/linux/crypto.h:863
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_init_tfm
  - crypto/ctr.c:crypto_rfc3686_crypt
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
```
```
In crypto/gcm.c (ffffffff814b8833)
Location: include/linux/crypto.h:863
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
```
In crypto/drbg.c (ffffffff814c00df)
Location: include/linux/crypto.h:863
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
  - crypto/drbg.c:drbg_init_hash_kernel
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
In crypto/cipher.c (ffffffff814b3399)
Location: include/linux/crypto.h:863
Inline: True
Inline callers:
  - crypto/cipher.c:crypto_init_cipher_ops
  - crypto/cipher.c:crypto_init_cipher_ops
  - crypto/cipher.c:cipher_decrypt_unaligned
  - crypto/cipher.c:cipher_encrypt_unaligned
  - crypto/cipher.c:cipher_crypt_unaligned
  - crypto/cipher.c:setkey
  - crypto/cipher.c:setkey
```
```
In crypto/aead.c (ffffffff814b5ee5)
Location: include/linux/crypto.h:863
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_setkey
```
```
In crypto/ablkcipher.c (ffffffff814b6aed)
Location: include/linux/crypto.h:863
Inline: True
Inline callers:
  - crypto/ablkcipher.c:setkey
  - crypto/ablkcipher.c:ablkcipher_walk_phys
  - crypto/ablkcipher.c:ablkcipher_walk_next
```
```
In crypto/blkcipher.c (ffffffff814b6d2a)
Location: include/linux/crypto.h:863
Inline: True
Inline callers:
  - crypto/blkcipher.c:crypto_init_blkcipher_ops
  - crypto/blkcipher.c:setkey
  - crypto/blkcipher.c:blkcipher_aead_walk_virt_block
  - crypto/blkcipher.c:blkcipher_walk_virt_block
  - crypto/blkcipher.c:blkcipher_walk_phys
  - crypto/blkcipher.c:blkcipher_walk_virt
```
```
In crypto/skcipher.c (ffffffff814b8f2d)
Location: include/linux/crypto.h:863
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_skcipher
```
```
In crypto/seqiv.c (ffffffff814b9710)
Location: include/linux/crypto.h:863
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/ahash.c (ffffffff814ba2e5)
Location: include/linux/crypto.h:863
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_op
  - crypto/ahash.c:ahash_save_req
  - crypto/ahash.c:crypto_ahash_setkey
```
```
In crypto/shash.c (ffffffff814baadc)
Location: include/linux/crypto.h:863
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_digest
  - crypto/shash.c:crypto_shash_finup
  - crypto/shash.c:crypto_shash_final
  - crypto/shash.c:shash_final_unaligned
  - crypto/shash.c:crypto_shash_update
  - crypto/shash.c:shash_update_unaligned
  - crypto/shash.c:crypto_shash_setkey
```
```
In crypto/hmac.c (ffffffff814be885)
Location: include/linux/crypto.h:863
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_exit_tfm
  - crypto/hmac.c:hmac_init_tfm
  - crypto/hmac.c:hmac_finup
  - crypto/hmac.c:hmac_final
  - crypto/hmac.c:hmac_init
  - crypto/hmac.c:hmac_import
  - crypto/hmac.c:hmac_setkey
```
```
In crypto/cts.c (ffffffff814c1ded)
Location: include/linux/crypto.h:863
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_init_tfm
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
```
```
In crypto/ctr.c (ffffffff814c341d)
Location: include/linux/crypto.h:863
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_init_tfm
  - crypto/ctr.c:crypto_rfc3686_crypt
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
```
```
In crypto/gcm.c (ffffffff814c3ea3)
Location: include/linux/crypto.h:863
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
```
In crypto/drbg.c (ffffffff814cb74f)
Location: include/linux/crypto.h:863
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
  - crypto/drbg.c:drbg_init_hash_kernel
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
In crypto/cipher.c (ffffffff814cbe19)
Location: include/linux/crypto.h:863
Inline: True
Inline callers:
  - crypto/cipher.c:crypto_init_cipher_ops
  - crypto/cipher.c:crypto_init_cipher_ops
  - crypto/cipher.c:cipher_decrypt_unaligned
  - crypto/cipher.c:cipher_encrypt_unaligned
  - crypto/cipher.c:cipher_crypt_unaligned
  - crypto/cipher.c:setkey
  - crypto/cipher.c:setkey
```
```
In crypto/aead.c (ffffffff814ce985)
Location: include/linux/crypto.h:863
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_setkey
```
```
In crypto/ablkcipher.c (ffffffff814cf57d)
Location: include/linux/crypto.h:863
Inline: True
Inline callers:
  - crypto/ablkcipher.c:setkey
  - crypto/ablkcipher.c:ablkcipher_walk_phys
  - crypto/ablkcipher.c:ablkcipher_walk_next
```
```
In crypto/blkcipher.c (ffffffff814cf7ba)
Location: include/linux/crypto.h:863
Inline: True
Inline callers:
  - crypto/blkcipher.c:crypto_init_blkcipher_ops
  - crypto/blkcipher.c:setkey
  - crypto/blkcipher.c:blkcipher_aead_walk_virt_block
  - crypto/blkcipher.c:blkcipher_walk_virt_block
  - crypto/blkcipher.c:blkcipher_walk_phys
  - crypto/blkcipher.c:blkcipher_walk_virt
```
```
In crypto/skcipher.c (ffffffff814d19ed)
Location: include/linux/crypto.h:863
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_skcipher
```
```
In crypto/seqiv.c (ffffffff814d21b0)
Location: include/linux/crypto.h:863
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/ahash.c (ffffffff814d2d95)
Location: include/linux/crypto.h:863
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_op
  - crypto/ahash.c:ahash_save_req
  - crypto/ahash.c:crypto_ahash_setkey
```
```
In crypto/shash.c (ffffffff814d358c)
Location: include/linux/crypto.h:863
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_digest
  - crypto/shash.c:crypto_shash_finup
  - crypto/shash.c:crypto_shash_final
  - crypto/shash.c:shash_final_unaligned
  - crypto/shash.c:crypto_shash_update
  - crypto/shash.c:shash_update_unaligned
  - crypto/shash.c:crypto_shash_setkey
```
```
In crypto/hmac.c (ffffffff814d7355)
Location: include/linux/crypto.h:863
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_exit_tfm
  - crypto/hmac.c:hmac_init_tfm
  - crypto/hmac.c:hmac_finup
  - crypto/hmac.c:hmac_final
  - crypto/hmac.c:hmac_init
  - crypto/hmac.c:hmac_import
  - crypto/hmac.c:hmac_setkey
```
```
In crypto/cts.c (ffffffff814da8bd)
Location: include/linux/crypto.h:863
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_init_tfm
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
```
```
In crypto/ctr.c (ffffffff814dbeed)
Location: include/linux/crypto.h:863
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_init_tfm
  - crypto/ctr.c:crypto_rfc3686_crypt
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
```
```
In crypto/gcm.c (ffffffff814dc973)
Location: include/linux/crypto.h:863
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
```
In crypto/drbg.c (ffffffff814e421f)
Location: include/linux/crypto.h:863
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
  - crypto/drbg.c:drbg_init_hash_kernel
```
</details>
</li>
</ul>

## Differences
