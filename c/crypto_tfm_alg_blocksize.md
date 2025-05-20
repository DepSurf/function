# Function: <code>crypto_tfm_alg_blocksize</code>

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
In fs/ecryptfs/crypto.c (ffffffff81307730)
Location: include/linux/crypto.h:651
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_set_f_namelen
```
```
In fs/ecryptfs/keystore.c (ffffffff81308bac)
Location: include/linux/crypto.h:651
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (0)
Location: include/linux/crypto.h:651
Inline: True
```
```
In crypto/cipher.c (0)
Location: include/linux/crypto.h:651
Inline: True
```
```
In crypto/ablkcipher.c (ffffffff8139fd79)
Location: include/linux/crypto.h:651
Inline: True
Inline callers:
  - crypto/ablkcipher.c:ablkcipher_walk_phys
```
```
In crypto/blkcipher.c (ffffffff813a18fa)
Location: include/linux/crypto.h:651
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_virt
  - crypto/blkcipher.c:blkcipher_walk_phys
  - crypto/blkcipher.c:blkcipher_walk_virt_block
  - crypto/blkcipher.c:blkcipher_aead_walk_virt_block
```
```
In crypto/hmac.c (ffffffff813a4be8)
Location: include/linux/crypto.h:651
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_setkey
```
```
In crypto/ecb.c (ffffffff813a8ed9)
Location: include/linux/crypto.h:651
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_crypt
```
```
In crypto/cbc.c (ffffffff813a939e)
Location: include/linux/crypto.h:651
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_encrypt
  - crypto/cbc.c:crypto_cbc_encrypt
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cbc.c:crypto_cbc_decrypt
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
In fs/ecryptfs/crypto.c (ffffffff8133b863)
Location: include/linux/crypto.h:626
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_set_f_namelen
```
```
In fs/ecryptfs/keystore.c (ffffffff8133cdda)
Location: include/linux/crypto.h:626
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/big_key.c (ffffffff8136bc86)
Location: include/linux/crypto.h:626
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_read
  - security/keys/big_key.c:big_key_preparse
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff81fc2efa)
Location: include/linux/crypto.h:626
Inline: True
```
```
In crypto/cipher.c (0)
Location: include/linux/crypto.h:626
Inline: True
```
```
In crypto/ablkcipher.c (ffffffff813dcf59)
Location: include/linux/crypto.h:626
Inline: True
Inline callers:
  - crypto/ablkcipher.c:ablkcipher_walk_phys
```
```
In crypto/blkcipher.c (ffffffff813dde9c)
Location: include/linux/crypto.h:626
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_aead_walk_virt_block
  - crypto/blkcipher.c:blkcipher_walk_virt_block
  - crypto/blkcipher.c:blkcipher_walk_phys
  - crypto/blkcipher.c:blkcipher_walk_virt
```
```
In crypto/hmac.c (ffffffff813e23e8)
Location: include/linux/crypto.h:626
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_setkey
```
```
In crypto/ecb.c (ffffffff813e6ea9)
Location: include/linux/crypto.h:626
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_crypt
```
```
In crypto/cbc.c (ffffffff813e7470)
Location: include/linux/crypto.h:626
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cbc.c:crypto_cbc_encrypt
  - crypto/cbc.c:crypto_cbc_encrypt
```
```
In crypto/cts.c (ffffffff813e7dcd)
Location: include/linux/crypto.h:626
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_init_tfm
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:cts_cbc_encrypt
```
```
In crypto/xts.c (ffffffff813e8618)
Location: include/linux/crypto.h:626
Inline: True
Inline callers:
  - crypto/xts.c:init_tfm
  - crypto/xts.c:init_tfm
```
```
In crypto/ctr.c (ffffffff813e89ac)
Location: include/linux/crypto.h:626
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
```
```
In crypto/drbg.c (ffffffff813eecf9)
Location: include/linux/crypto.h:626
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
In fs/ecryptfs/crypto.c (ffffffff813515f3)
Location: include/linux/crypto.h:629
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_set_f_namelen
```
```
In fs/ecryptfs/keystore.c (ffffffff81352b6a)
Location: include/linux/crypto.h:629
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/big_key.c (ffffffff813824a6)
Location: include/linux/crypto.h:629
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_read
  - security/keys/big_key.c:big_key_preparse
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff81fff946)
Location: include/linux/crypto.h:629
Inline: True
```
```
In crypto/cipher.c (0)
Location: include/linux/crypto.h:629
Inline: True
```
```
In crypto/ablkcipher.c (ffffffff813f4829)
Location: include/linux/crypto.h:629
Inline: True
Inline callers:
  - crypto/ablkcipher.c:ablkcipher_walk_phys
```
```
In crypto/blkcipher.c (ffffffff813f574c)
Location: include/linux/crypto.h:629
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_aead_walk_virt_block
  - crypto/blkcipher.c:blkcipher_walk_virt_block
  - crypto/blkcipher.c:blkcipher_walk_phys
  - crypto/blkcipher.c:blkcipher_walk_virt
```
```
In crypto/skcipher.c (ffffffff813f6bc9)
Location: include/linux/crypto.h:629
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_skcipher
```
```
In crypto/hmac.c (ffffffff813fb408)
Location: include/linux/crypto.h:629
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_setkey
```
```
In crypto/ecb.c (ffffffff813ffc59)
Location: include/linux/crypto.h:629
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_crypt
```
```
In crypto/cbc.c (ffffffff814003c1)
Location: include/linux/crypto.h:629
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cbc.c:crypto_cbc_decrypt
```
```
In crypto/cts.c (ffffffff81400bfd)
Location: include/linux/crypto.h:629
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_init_tfm
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:cts_cbc_encrypt
```
```
In crypto/ctr.c (ffffffff81401fbc)
Location: include/linux/crypto.h:629
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
```
```
In crypto/drbg.c (ffffffff8140853f)
Location: include/linux/crypto.h:629
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
In fs/ecryptfs/crypto.c (ffffffff81366133)
Location: include/linux/crypto.h:629
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_set_f_namelen
```
```
In fs/ecryptfs/keystore.c (ffffffff8136769f)
Location: include/linux/crypto.h:629
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/big_key.c (ffffffff81396b57)
Location: include/linux/crypto.h:629
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_read
  - security/keys/big_key.c:big_key_preparse
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff820e2bd4)
Location: include/linux/crypto.h:629
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
```
```
In crypto/cipher.c (0)
Location: include/linux/crypto.h:629
Inline: True
```
```
In crypto/ablkcipher.c (ffffffff81400b76)
Location: include/linux/crypto.h:629
Inline: True
Inline callers:
  - crypto/ablkcipher.c:ablkcipher_walk_phys
```
```
In crypto/blkcipher.c (ffffffff814019ec)
Location: include/linux/crypto.h:629
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_aead_walk_virt_block
  - crypto/blkcipher.c:blkcipher_walk_virt_block
  - crypto/blkcipher.c:blkcipher_walk_phys
  - crypto/blkcipher.c:blkcipher_walk_virt
```
```
In crypto/skcipher.c (ffffffff81402f99)
Location: include/linux/crypto.h:629
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_skcipher
```
```
In crypto/hmac.c (ffffffff81407ed8)
Location: include/linux/crypto.h:629
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_setkey
```
```
In crypto/ecb.c (ffffffff8140cf49)
Location: include/linux/crypto.h:629
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_crypt
```
```
In crypto/cbc.c (0)
Location: include/linux/crypto.h:629
Inline: True
```
```
In crypto/cts.c (ffffffff8140dbad)
Location: include/linux/crypto.h:629
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_init_tfm
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:cts_cbc_encrypt
```
```
In crypto/ctr.c (ffffffff8140f86c)
Location: include/linux/crypto.h:629
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
```
```
In crypto/drbg.c (ffffffff81415bff)
Location: include/linux/crypto.h:629
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
In fs/ecryptfs/crypto.c (ffffffff8138ad73)
Location: include/linux/crypto.h:677
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_set_f_namelen
```
```
In fs/ecryptfs/keystore.c (ffffffff8138c32f)
Location: include/linux/crypto.h:677
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff826eb83a)
Location: include/linux/crypto.h:677
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
```
```
In crypto/cipher.c (0)
Location: include/linux/crypto.h:677
Inline: True
```
```
In crypto/ablkcipher.c (ffffffff81429176)
Location: include/linux/crypto.h:677
Inline: True
Inline callers:
  - crypto/ablkcipher.c:ablkcipher_walk_phys
```
```
In crypto/blkcipher.c (ffffffff8142a00c)
Location: include/linux/crypto.h:677
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_aead_walk_virt_block
  - crypto/blkcipher.c:blkcipher_walk_virt_block
  - crypto/blkcipher.c:blkcipher_walk_phys
  - crypto/blkcipher.c:blkcipher_walk_virt
```
```
In crypto/skcipher.c (ffffffff8142b682)
Location: include/linux/crypto.h:677
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_skcipher
```
```
In crypto/hmac.c (ffffffff81430858)
Location: include/linux/crypto.h:677
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_setkey
```
```
In crypto/ecb.c (ffffffff814359b9)
Location: include/linux/crypto.h:677
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_crypt
```
```
In crypto/cbc.c (0)
Location: include/linux/crypto.h:677
Inline: True
```
```
In crypto/cts.c (ffffffff8143664d)
Location: include/linux/crypto.h:677
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_init_tfm
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:cts_cbc_encrypt
```
```
In crypto/ctr.c (ffffffff8143836c)
Location: include/linux/crypto.h:677
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
```
```
In crypto/drbg.c (ffffffff814403cf)
Location: include/linux/crypto.h:677
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
In fs/ecryptfs/crypto.c (ffffffff813b99fd)
Location: include/linux/crypto.h:690
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_set_f_namelen
```
```
In fs/ecryptfs/keystore.c (ffffffff813bb177)
Location: include/linux/crypto.h:690
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff82715d5f)
Location: include/linux/crypto.h:690
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
```
```
In crypto/cipher.c (ffffffff81458c78)
Location: include/linux/crypto.h:690
Inline: True
Inline callers:
  - crypto/cipher.c:cipher_crypt_unaligned
```
```
In crypto/ablkcipher.c (ffffffff8145bf25)
Location: include/linux/crypto.h:690
Inline: True
Inline callers:
  - crypto/ablkcipher.c:ablkcipher_walk_phys
  - crypto/ablkcipher.c:ablkcipher_walk_next
```
```
In crypto/blkcipher.c (ffffffff8145cd4c)
Location: include/linux/crypto.h:690
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_aead_walk_virt_block
  - crypto/blkcipher.c:blkcipher_walk_virt_block
  - crypto/blkcipher.c:blkcipher_walk_phys
  - crypto/blkcipher.c:blkcipher_walk_virt
```
```
In crypto/skcipher.c (ffffffff8145e38e)
Location: include/linux/crypto.h:690
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_skcipher
```
```
In crypto/hmac.c (ffffffff814633b8)
Location: include/linux/crypto.h:690
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_setkey
```
```
In crypto/ecb.c (ffffffff81468535)
Location: include/linux/crypto.h:690
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_crypt
```
```
In crypto/cbc.c (0)
Location: include/linux/crypto.h:690
Inline: True
```
```
In crypto/cts.c (ffffffff814691bd)
Location: include/linux/crypto.h:690
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_init_tfm
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:cts_cbc_encrypt
```
```
In crypto/ctr.c (ffffffff8146ad01)
Location: include/linux/crypto.h:690
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
```
```
In crypto/drbg.c (ffffffff814732af)
Location: include/linux/crypto.h:690
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
In fs/ecryptfs/crypto.c (ffffffff813d2f6d)
Location: include/linux/crypto.h:861
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_set_f_namelen
```
```
In fs/ecryptfs/keystore.c (ffffffff813d4778)
Location: include/linux/crypto.h:861
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff828cd1a1)
Location: include/linux/crypto.h:861
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
```
```
In crypto/cipher.c (ffffffff81476168)
Location: include/linux/crypto.h:861
Inline: True
Inline callers:
  - crypto/cipher.c:cipher_crypt_unaligned
```
```
In crypto/ablkcipher.c (ffffffff81479825)
Location: include/linux/crypto.h:861
Inline: True
Inline callers:
  - crypto/ablkcipher.c:ablkcipher_walk_phys
  - crypto/ablkcipher.c:ablkcipher_walk_next
```
```
In crypto/blkcipher.c (ffffffff8147a5dc)
Location: include/linux/crypto.h:861
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_aead_walk_virt_block
  - crypto/blkcipher.c:blkcipher_walk_virt_block
  - crypto/blkcipher.c:blkcipher_walk_phys
  - crypto/blkcipher.c:blkcipher_walk_virt
```
```
In crypto/skcipher.c (ffffffff8147bc4e)
Location: include/linux/crypto.h:861
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_skcipher
```
```
In crypto/hmac.c (ffffffff8148104b)
Location: include/linux/crypto.h:861
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_setkey
```
```
In crypto/ecb.c (ffffffff814861a5)
Location: include/linux/crypto.h:861
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_crypt
```
```
In crypto/cbc.c (0)
Location: include/linux/crypto.h:861
Inline: True
```
```
In crypto/cts.c (ffffffff81486b8d)
Location: include/linux/crypto.h:861
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_init_tfm
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:cts_cbc_encrypt
```
```
In crypto/ctr.c (ffffffff81488561)
Location: include/linux/crypto.h:861
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
```
```
In crypto/drbg.c (ffffffff8148f82a)
Location: include/linux/crypto.h:861
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
In fs/ecryptfs/crypto.c (ffffffff813fd9fd)
Location: include/linux/crypto.h:858
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_set_f_namelen
```
```
In fs/ecryptfs/keystore.c (ffffffff813ff122)
Location: include/linux/crypto.h:858
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff828e6bde)
Location: include/linux/crypto.h:858
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
```
```
In crypto/cipher.c (ffffffff814a3ed8)
Location: include/linux/crypto.h:858
Inline: True
Inline callers:
  - crypto/cipher.c:cipher_crypt_unaligned
```
```
In crypto/ablkcipher.c (ffffffff814a7675)
Location: include/linux/crypto.h:858
Inline: True
Inline callers:
  - crypto/ablkcipher.c:ablkcipher_walk_phys
  - crypto/ablkcipher.c:ablkcipher_walk_next
```
```
In crypto/blkcipher.c (ffffffff814a860c)
Location: include/linux/crypto.h:858
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_aead_walk_virt_block
  - crypto/blkcipher.c:blkcipher_walk_virt_block
  - crypto/blkcipher.c:blkcipher_walk_phys
  - crypto/blkcipher.c:blkcipher_walk_virt
```
```
In crypto/skcipher.c (ffffffff814a9ff0)
Location: include/linux/crypto.h:858
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_skcipher
```
```
In crypto/hmac.c (ffffffff814af25b)
Location: include/linux/crypto.h:858
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_setkey
```
```
In crypto/ecb.c (ffffffff814b436a)
Location: include/linux/crypto.h:858
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_crypt
```
```
In crypto/cbc.c (0)
Location: include/linux/crypto.h:858
Inline: True
```
```
In crypto/cts.c (ffffffff814b4cad)
Location: include/linux/crypto.h:858
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_init_tfm
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:cts_cbc_encrypt
```
```
In crypto/ctr.c (ffffffff814b5fa7)
Location: include/linux/crypto.h:858
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
```
```
In crypto/drbg.c (ffffffff814be1bb)
Location: include/linux/crypto.h:858
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
```
```
In net/xfrm/xfrm_state.c (ffffffff819eebdd)
Location: include/linux/crypto.h:858
Inline: True
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
In fs/verity/hash_algs.c (ffffffff813500a5)
Location: include/linux/crypto.h:858
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
```
```
In fs/ecryptfs/crypto.c (ffffffff814178dd)
Location: include/linux/crypto.h:858
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_set_f_namelen
```
```
In fs/ecryptfs/keystore.c (ffffffff81419012)
Location: include/linux/crypto.h:858
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff828ef6c9)
Location: include/linux/crypto.h:858
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
```
```
In crypto/cipher.c (ffffffff814beb08)
Location: include/linux/crypto.h:858
Inline: True
Inline callers:
  - crypto/cipher.c:cipher_crypt_unaligned
```
```
In crypto/ablkcipher.c (ffffffff814c22f5)
Location: include/linux/crypto.h:858
Inline: True
Inline callers:
  - crypto/ablkcipher.c:ablkcipher_walk_phys
  - crypto/ablkcipher.c:ablkcipher_walk_next
```
```
In crypto/blkcipher.c (ffffffff814c327c)
Location: include/linux/crypto.h:858
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_aead_walk_virt_block
  - crypto/blkcipher.c:blkcipher_walk_virt_block
  - crypto/blkcipher.c:blkcipher_walk_phys
  - crypto/blkcipher.c:blkcipher_walk_virt
```
```
In crypto/skcipher.c (ffffffff814c4ce0)
Location: include/linux/crypto.h:858
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_skcipher
```
```
In crypto/hmac.c (ffffffff814c9eeb)
Location: include/linux/crypto.h:858
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_setkey
```
```
In crypto/ecb.c (ffffffff814cd0da)
Location: include/linux/crypto.h:858
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_crypt
```
```
In crypto/cbc.c (0)
Location: include/linux/crypto.h:858
Inline: True
```
```
In crypto/cts.c (ffffffff814cd77d)
Location: include/linux/crypto.h:858
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_init_tfm
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:cts_cbc_encrypt
```
```
In crypto/ctr.c (ffffffff814cf1a7)
Location: include/linux/crypto.h:858
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
```
```
In crypto/drbg.c (ffffffff814d700b)
Location: include/linux/crypto.h:858
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
```
```
In net/xfrm/xfrm_state.c (ffffffff81a25abd)
Location: include/linux/crypto.h:858
Inline: True
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
In fs/verity/hash_algs.c (ffffffff81396984)
Location: include/linux/crypto.h:677
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
```
```
In fs/ecryptfs/crypto.c (ffffffff81465dfd)
Location: include/linux/crypto.h:677
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_set_f_namelen
```
```
In fs/ecryptfs/keystore.c (ffffffff8146819e)
Location: include/linux/crypto.h:677
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff82d048dd)
Location: include/linux/crypto.h:677
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
```
```
In crypto/cipher.c (ffffffff8151f48b)
Location: include/linux/crypto.h:677
Inline: True
Inline callers:
  - crypto/cipher.c:crypto_cipher_decrypt_one
  - crypto/cipher.c:crypto_cipher_encrypt_one
```
```
In crypto/skcipher.c (ffffffff81523b70)
Location: include/linux/crypto.h:677
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_async
  - crypto/skcipher.c:skcipher_walk_virt
```
```
In crypto/hmac.c (0)
Location: include/linux/crypto.h:677
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_setkey
```
```
In crypto/ecb.c (0)
Location: include/linux/crypto.h:677
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_crypt
```
```
In crypto/cbc.c (ffffffff8152ca38)
Location: include/linux/crypto.h:677
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_decrypt
```
```
In crypto/cts.c (ffffffff8152cb9d)
Location: include/linux/crypto.h:677
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_init_tfm
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:cts_cbc_encrypt
```
```
In crypto/ctr.c (ffffffff8152e401)
Location: include/linux/crypto.h:677
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
```
```
In crypto/drbg.c (ffffffff81533819)
Location: include/linux/crypto.h:677
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
```
```
In net/xfrm/xfrm_state.c (ffffffff81b17593)
Location: include/linux/crypto.h:677
Inline: True
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
In fs/verity/hash_algs.c (ffffffff813a85b4)
Location: include/linux/crypto.h:713
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
```
```
In fs/ecryptfs/crypto.c (ffffffff8148169d)
Location: include/linux/crypto.h:713
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_set_f_namelen
```
```
In fs/ecryptfs/keystore.c (ffffffff8148361e)
Location: include/linux/crypto.h:713
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff82ff1caa)
Location: include/linux/crypto.h:713
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
```
```
In crypto/cipher.c (ffffffff8153c2eb)
Location: include/linux/crypto.h:713
Inline: True
Inline callers:
  - crypto/cipher.c:crypto_cipher_decrypt_one
  - crypto/cipher.c:crypto_cipher_encrypt_one
```
```
In crypto/skcipher.c (ffffffff81540ac0)
Location: include/linux/crypto.h:713
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_async
  - crypto/skcipher.c:skcipher_walk_virt
```
```
In crypto/hmac.c (0)
Location: include/linux/crypto.h:713
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_setkey
```
```
In crypto/ecb.c (0)
Location: include/linux/crypto.h:713
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_crypt
```
```
In crypto/cbc.c (ffffffff815499d2)
Location: include/linux/crypto.h:713
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_decrypt_inplace
  - crypto/cbc.c:crypto_cbc_decrypt_segment
  - crypto/cbc.c:crypto_cbc_encrypt
```
```
In crypto/cts.c (ffffffff81549c0d)
Location: include/linux/crypto.h:713
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_init_tfm
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:cts_cbc_encrypt
```
```
In crypto/ctr.c (ffffffff8154b3a1)
Location: include/linux/crypto.h:713
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
```
```
In crypto/drbg.c (ffffffff81550769)
Location: include/linux/crypto.h:713
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
```
```
In net/xfrm/xfrm_state.c (ffffffff81b25653)
Location: include/linux/crypto.h:713
Inline: True
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
In fs/verity/hash_algs.c (ffffffff813af604)
Location: include/linux/crypto.h:709
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
```
```
In fs/ecryptfs/crypto.c (ffffffff81487101)
Location: include/linux/crypto.h:709
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_set_f_namelen
```
```
In fs/ecryptfs/keystore.c (ffffffff814890ae)
Location: include/linux/crypto.h:709
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff831fc634)
Location: include/linux/crypto.h:709
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
```
```
In crypto/cipher.c (ffffffff815449db)
Location: include/linux/crypto.h:709
Inline: True
Inline callers:
  - crypto/cipher.c:crypto_cipher_decrypt_one
  - crypto/cipher.c:crypto_cipher_encrypt_one
```
```
In crypto/skcipher.c (ffffffff81549120)
Location: include/linux/crypto.h:709
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_async
  - crypto/skcipher.c:skcipher_walk_virt
```
```
In crypto/hmac.c (0)
Location: include/linux/crypto.h:709
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_setkey
```
```
In crypto/ecb.c (0)
Location: include/linux/crypto.h:709
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_crypt
```
```
In crypto/cbc.c (ffffffff815520fd)
Location: include/linux/crypto.h:709
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cbc.c:crypto_cbc_encrypt
```
```
In crypto/cts.c (ffffffff8155224d)
Location: include/linux/crypto.h:709
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_init_tfm
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:cts_cbc_encrypt
```
```
In crypto/ctr.c (ffffffff815539d5)
Location: include/linux/crypto.h:709
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
```
```
In crypto/drbg.c (ffffffff81558f49)
Location: include/linux/crypto.h:709
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
```
```
In net/xfrm/xfrm_state.c (ffffffff81b13173)
Location: include/linux/crypto.h:709
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
In fs/verity/hash_algs.c (ffffffff813ff1ce)
Location: include/linux/crypto.h:683
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
```
```
In fs/ecryptfs/crypto.c (ffffffff814de8a1)
Location: include/linux/crypto.h:683
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_set_f_namelen
```
```
In fs/ecryptfs/keystore.c (ffffffff814e08ae)
Location: include/linux/crypto.h:683
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff832e3686)
Location: include/linux/crypto.h:683
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
```
```
In crypto/cipher.c (ffffffff815a517b)
Location: include/linux/crypto.h:683
Inline: True
Inline callers:
  - crypto/cipher.c:crypto_cipher_decrypt_one
  - crypto/cipher.c:crypto_cipher_encrypt_one
```
```
In crypto/skcipher.c (ffffffff815a9900)
Location: include/linux/crypto.h:683
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_async
  - crypto/skcipher.c:skcipher_walk_virt
```
```
In crypto/hmac.c (0)
Location: include/linux/crypto.h:683
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_setkey
```
```
In crypto/ecb.c (0)
Location: include/linux/crypto.h:683
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_crypt
```
```
In crypto/cbc.c (ffffffff815b30fd)
Location: include/linux/crypto.h:683
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cbc.c:crypto_cbc_encrypt
```
```
In crypto/cts.c (ffffffff815b324d)
Location: include/linux/crypto.h:683
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_init_tfm
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:cts_cbc_encrypt
```
```
In crypto/ctr.c (ffffffff815b4a05)
Location: include/linux/crypto.h:683
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
```
```
In crypto/drbg.c (ffffffff815ba209)
Location: include/linux/crypto.h:683
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
```
```
In net/xfrm/xfrm_state.c (ffffffff81bd7073)
Location: include/linux/crypto.h:683
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
In fs/verity/hash_algs.c (ffffffff81472d3c)
Location: include/linux/crypto.h:692
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
```
```
In fs/ecryptfs/crypto.c (ffffffff8156c893)
Location: include/linux/crypto.h:692
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_set_f_namelen
```
```
In fs/ecryptfs/keystore.c (ffffffff8156ea5e)
Location: include/linux/crypto.h:692
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff83499a96)
Location: include/linux/crypto.h:692
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
```
```
In crypto/cipher.c (ffffffff8164be4d)
Location: include/linux/crypto.h:692
Inline: True
Inline callers:
  - crypto/cipher.c:crypto_cipher_decrypt_one
  - crypto/cipher.c:crypto_cipher_encrypt_one
```
```
In crypto/skcipher.c (ffffffff81650d60)
Location: include/linux/crypto.h:692
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_async
  - crypto/skcipher.c:skcipher_walk_virt
```
```
In crypto/hmac.c (0)
Location: include/linux/crypto.h:692
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_setkey
```
```
In crypto/ecb.c (0)
Location: include/linux/crypto.h:692
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_crypt
```
```
In crypto/cbc.c (ffffffff8165bd2f)
Location: include/linux/crypto.h:692
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cbc.c:crypto_cbc_decrypt_inplace
  - crypto/cbc.c:crypto_cbc_encrypt
```
```
In crypto/cts.c (ffffffff8165c22d)
Location: include/linux/crypto.h:692
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_init_tfm
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:cts_cbc_encrypt
```
```
In crypto/ctr.c (ffffffff8165d8fa)
Location: include/linux/crypto.h:692
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
```
```
In crypto/drbg.c (ffffffff816632ac)
Location: include/linux/crypto.h:692
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
```
```
In net/xfrm/xfrm_state.c (ffffffff81d6da33)
Location: include/linux/crypto.h:692
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
In fs/verity/hash_algs.c (ffffffff81504ad0)
Location: include/linux/crypto.h:692
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
```
```
In fs/ecryptfs/crypto.c (ffffffff81610b53)
Location: include/linux/crypto.h:692
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_set_f_namelen
```
```
In fs/ecryptfs/keystore.c (ffffffff81613b9b)
Location: include/linux/crypto.h:692
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff83ecfbc4)
Location: include/linux/crypto.h:692
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
```
```
In crypto/cipher.c (ffffffff81704e52)
Location: include/linux/crypto.h:692
Inline: True
Inline callers:
  - crypto/cipher.c:cipher_crypt_one
```
```
In crypto/skcipher.c (ffffffff8170a550)
Location: include/linux/crypto.h:692
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_async
  - crypto/skcipher.c:skcipher_walk_virt
```
```
In crypto/hmac.c (ffffffff81711dff)
Location: include/linux/crypto.h:692
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_setkey
```
```
In crypto/ecb.c (0)
Location: include/linux/crypto.h:692
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_crypt
```
```
In crypto/cbc.c (ffffffff81715495)
Location: include/linux/crypto.h:692
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_decrypt_inplace
  - crypto/cbc.c:crypto_cbc_decrypt_segment
  - crypto/cbc.c:crypto_cbc_encrypt_inplace
  - crypto/cbc.c:crypto_cbc_encrypt_segment
```
```
In crypto/cts.c (ffffffff81715bed)
Location: include/linux/crypto.h:692
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_init_tfm
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:cts_cbc_encrypt
```
```
In crypto/ctr.c (ffffffff8171748a)
Location: include/linux/crypto.h:692
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
```
```
In crypto/drbg.c (ffffffff8171d53c)
Location: include/linux/crypto.h:692
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
```
```
In net/xfrm/xfrm_state.c (ffffffff81f39033)
Location: include/linux/crypto.h:692
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
In fs/verity/hash_algs.c (ffffffff8153c1aa)
Location: include/linux/crypto.h:465
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
```
```
In fs/ecryptfs/crypto.c (ffffffff81648a0b)
Location: include/linux/crypto.h:465
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_set_f_namelen
```
```
In fs/ecryptfs/keystore.c (ffffffff8164bbfb)
Location: include/linux/crypto.h:465
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff836f4c82)
Location: include/linux/crypto.h:465
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
```
```
In crypto/cipher.c (ffffffff8173f122)
Location: include/linux/crypto.h:465
Inline: True
Inline callers:
  - crypto/cipher.c:cipher_crypt_one
```
```
In crypto/skcipher.c (ffffffff81743da0)
Location: include/linux/crypto.h:465
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_async
  - crypto/skcipher.c:skcipher_walk_virt
```
```
In crypto/hmac.c (ffffffff8174c9cf)
Location: include/linux/crypto.h:465
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_setkey
```
```
In crypto/ecb.c (0)
Location: include/linux/crypto.h:465
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_crypt
```
```
In crypto/cbc.c (ffffffff81750d45)
Location: include/linux/crypto.h:465
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_decrypt_inplace
  - crypto/cbc.c:crypto_cbc_decrypt_segment
  - crypto/cbc.c:crypto_cbc_encrypt_inplace
  - crypto/cbc.c:crypto_cbc_encrypt_segment
```
```
In crypto/cts.c (ffffffff8175149d)
Location: include/linux/crypto.h:465
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_init_tfm
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:cts_cbc_encrypt
```
```
In crypto/ctr.c (ffffffff81752daa)
Location: include/linux/crypto.h:465
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
```
```
In crypto/drbg.c (ffffffff81758e1c)
Location: include/linux/crypto.h:465
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
```
```
In net/xfrm/xfrm_state.c (ffffffff81f988c3)
Location: include/linux/crypto.h:465
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
In fs/verity/hash_algs.c (ffffffff8157148a)
Location: include/linux/crypto.h:465
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
```
```
In fs/ecryptfs/crypto.c (ffffffff81681edb)
Location: include/linux/crypto.h:465
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_set_f_namelen
```
```
In fs/ecryptfs/keystore.c (ffffffff8168512a)
Location: include/linux/crypto.h:465
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff83927e82)
Location: include/linux/crypto.h:465
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
```
```
In crypto/cipher.c (ffffffff8177ffa2)
Location: include/linux/crypto.h:465
Inline: True
Inline callers:
  - crypto/cipher.c:cipher_crypt_one
```
```
In crypto/lskcipher.c (ffffffff81783a0b)
Location: include/linux/crypto.h:465
Inline: True
Inline callers:
  - crypto/lskcipher.c:crypto_lskcipher_crypt_unaligned
```
```
In crypto/skcipher.c (ffffffff81786180)
Location: include/linux/crypto.h:465
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_skcipher
```
```
In crypto/hmac.c (0)
Location: include/linux/crypto.h:465
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_setkey
```
```
In crypto/ecb.c (ffffffff8179290c)
Location: include/linux/crypto.h:465
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_decrypt2
  - crypto/ecb.c:crypto_ecb_encrypt2
```
```
In crypto/cbc.c (ffffffff81792c15)
Location: include/linux/crypto.h:465
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_decrypt_inplace
  - crypto/cbc.c:crypto_cbc_decrypt_segment
  - crypto/cbc.c:crypto_cbc_encrypt_inplace
  - crypto/cbc.c:crypto_cbc_encrypt_segment
```
```
In crypto/cts.c (ffffffff817932ed)
Location: include/linux/crypto.h:465
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_init_tfm
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:cts_cbc_encrypt
```
```
In crypto/ctr.c (ffffffff81794d4a)
Location: include/linux/crypto.h:465
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
```
```
In crypto/drbg.c (ffffffff8179ad1c)
Location: include/linux/crypto.h:465
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
```
```
In net/xfrm/xfrm_state.c (ffffffff82065c33)
Location: include/linux/crypto.h:465
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
In fs/verity/hash_algs.c (ffff800010411c18)
Location: include/linux/crypto.h:858
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
```
```
In fs/ecryptfs/crypto.c (ffff8000104f94d0)
Location: include/linux/crypto.h:858
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_set_f_namelen
```
```
In fs/ecryptfs/keystore.c (ffff8000104fa85c)
Location: include/linux/crypto.h:858
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (ffff8000114693ac)
Location: include/linux/crypto.h:858
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
```
```
In crypto/cipher.c (ffff8000105b7b80)
Location: include/linux/crypto.h:858
Inline: True
Inline callers:
  - crypto/cipher.c:cipher_crypt_unaligned
```
```
In crypto/ablkcipher.c (ffff8000105bca20)
Location: include/linux/crypto.h:858
Inline: True
Inline callers:
  - crypto/ablkcipher.c:ablkcipher_walk_phys
  - crypto/ablkcipher.c:ablkcipher_walk_next
```
```
In crypto/blkcipher.c (ffff8000105bda44)
Location: include/linux/crypto.h:858
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_aead_walk_virt_block
  - crypto/blkcipher.c:blkcipher_walk_virt_block
  - crypto/blkcipher.c:blkcipher_walk_phys
  - crypto/blkcipher.c:blkcipher_walk_virt
```
```
In crypto/skcipher.c (ffff8000105bf7a8)
Location: include/linux/crypto.h:858
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_skcipher
```
```
In crypto/hmac.c (ffff8000105c5b64)
Location: include/linux/crypto.h:858
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_setkey
```
```
In crypto/ecb.c (ffff8000105c8f24)
Location: include/linux/crypto.h:858
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_crypt
```
```
In crypto/cbc.c (0)
Location: include/linux/crypto.h:858
Inline: True
```
```
In crypto/cts.c (ffff8000105c9668)
Location: include/linux/crypto.h:858
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_init_tfm
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:cts_cbc_encrypt
```
```
In crypto/ctr.c (ffff8000105cb160)
Location: include/linux/crypto.h:858
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
```
```
In crypto/drbg.c (ffff8000105d14d0)
Location: include/linux/crypto.h:858
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
```
```
In net/xfrm/xfrm_state.c (ffff800010ce2f7c)
Location: include/linux/crypto.h:858
Inline: True
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
In fs/verity/hash_algs.c (c05de26c)
Location: include/linux/crypto.h:858
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
```
```
In fs/ecryptfs/crypto.c (c06b6d80)
Location: include/linux/crypto.h:858
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_set_f_namelen
```
```
In fs/ecryptfs/keystore.c (c06b7fac)
Location: include/linux/crypto.h:858
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (c1541ef4)
Location: include/linux/crypto.h:858
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
```
```
In crypto/cipher.c (c0766960)
Location: include/linux/crypto.h:858
Inline: True
Inline callers:
  - crypto/cipher.c:cipher_crypt_unaligned
```
```
In crypto/ablkcipher.c (c076a8d4)
Location: include/linux/crypto.h:858
Inline: True
Inline callers:
  - crypto/ablkcipher.c:ablkcipher_walk_phys
  - crypto/ablkcipher.c:ablkcipher_walk_next
```
```
In crypto/blkcipher.c (c076b890)
Location: include/linux/crypto.h:858
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_aead_walk_virt_block
  - crypto/blkcipher.c:blkcipher_walk_virt_block
  - crypto/blkcipher.c:blkcipher_walk_phys
  - crypto/blkcipher.c:blkcipher_walk_virt
```
```
In crypto/skcipher.c (c076d4c8)
Location: include/linux/crypto.h:858
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_skcipher
```
```
In crypto/hmac.c (c077290c)
Location: include/linux/crypto.h:858
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_setkey
```
```
In crypto/ecb.c (c0776bdc)
Location: include/linux/crypto.h:858
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_crypt
```
```
In crypto/cbc.c (0)
Location: include/linux/crypto.h:858
Inline: True
```
```
In crypto/cts.c (c0777208)
Location: include/linux/crypto.h:858
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_init_tfm
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:cts_cbc_encrypt
```
```
In crypto/ctr.c (c0778cb4)
Location: include/linux/crypto.h:858
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
```
```
In crypto/drbg.c (c0780440)
Location: include/linux/crypto.h:858
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
```
```
In net/xfrm/xfrm_state.c (c0dec740)
Location: include/linux/crypto.h:858
Inline: True
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
In fs/verity/hash_algs.c (c00000000051f7c0)
Location: include/linux/crypto.h:858
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
```
```
In fs/ecryptfs/crypto.c (c00000000063b850)
Location: include/linux/crypto.h:858
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_set_f_namelen
```
```
In fs/ecryptfs/keystore.c (c00000000063d0d0)
Location: include/linux/crypto.h:858
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (c000000001397524)
Location: include/linux/crypto.h:858
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
```
```
In crypto/cipher.c (c00000000073cc24)
Location: include/linux/crypto.h:858
Inline: True
Inline callers:
  - crypto/cipher.c:cipher_crypt_unaligned
```
```
In crypto/ablkcipher.c (c00000000074384c)
Location: include/linux/crypto.h:858
Inline: True
Inline callers:
  - crypto/ablkcipher.c:ablkcipher_walk_phys
  - crypto/ablkcipher.c:ablkcipher_walk_next
```
```
In crypto/blkcipher.c (c000000000744e60)
Location: include/linux/crypto.h:858
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_aead_walk_virt_block
  - crypto/blkcipher.c:blkcipher_walk_virt_block
  - crypto/blkcipher.c:blkcipher_walk_phys
  - crypto/blkcipher.c:blkcipher_walk_virt
```
```
In crypto/skcipher.c (c00000000074754c)
Location: include/linux/crypto.h:858
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_skcipher
```
```
In crypto/hmac.c (c00000000074f458)
Location: include/linux/crypto.h:858
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_setkey
```
```
In crypto/ecb.c (c00000000075338c)
Location: include/linux/crypto.h:858
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_crypt
```
```
In crypto/cbc.c (0)
Location: include/linux/crypto.h:858
Inline: True
```
```
In crypto/cts.c (c000000000753cc8)
Location: include/linux/crypto.h:858
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_init_tfm
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:cts_cbc_encrypt
```
```
In crypto/ctr.c (c0000000007560ec)
Location: include/linux/crypto.h:858
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
```
```
In crypto/drbg.c (c00000000075fc48)
Location: include/linux/crypto.h:858
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
```
```
In net/xfrm/xfrm_state.c (c000000000e06420)
Location: include/linux/crypto.h:858
Inline: True
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
In fs/verity/hash_algs.c (ffffffe0002b9da2)
Location: include/linux/crypto.h:858
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
```
```
In fs/ecryptfs/crypto.c (ffffffe000367c32)
Location: include/linux/crypto.h:858
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_set_f_namelen
```
```
In fs/ecryptfs/keystore.c (ffffffe000369042)
Location: include/linux/crypto.h:858
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffe0000245fe)
Location: include/linux/crypto.h:858
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
```
```
In crypto/cipher.c (ffffffe0003fe31c)
Location: include/linux/crypto.h:858
Inline: True
Inline callers:
  - crypto/cipher.c:cipher_crypt_unaligned
```
```
In crypto/ablkcipher.c (ffffffe000402232)
Location: include/linux/crypto.h:858
Inline: True
Inline callers:
  - crypto/ablkcipher.c:ablkcipher_walk_phys
  - crypto/ablkcipher.c:ablkcipher_walk_next
```
```
In crypto/blkcipher.c (ffffffe000402ff6)
Location: include/linux/crypto.h:858
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_aead_walk_virt_block
  - crypto/blkcipher.c:blkcipher_walk_virt_block
  - crypto/blkcipher.c:blkcipher_walk_phys
  - crypto/blkcipher.c:blkcipher_walk_virt
```
```
In crypto/skcipher.c (ffffffe0004048ee)
Location: include/linux/crypto.h:858
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_skcipher
```
```
In crypto/hmac.c (ffffffe000409c92)
Location: include/linux/crypto.h:858
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_setkey
```
```
In crypto/ecb.c (ffffffe00040d8d4)
Location: include/linux/crypto.h:858
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_crypt
```
```
In crypto/cbc.c (0)
Location: include/linux/crypto.h:858
Inline: True
```
```
In crypto/cts.c (ffffffe00040e334)
Location: include/linux/crypto.h:858
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_init_tfm
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:cts_cbc_encrypt
```
```
In crypto/ctr.c (ffffffe00040f320)
Location: include/linux/crypto.h:858
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
```
```
In crypto/drbg.c (ffffffe000416254)
Location: include/linux/crypto.h:858
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
```
```
In net/xfrm/xfrm_state.c (ffffffe00083184e)
Location: include/linux/crypto.h:858
Inline: True
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
In fs/verity/hash_algs.c (ffffffff81348685)
Location: include/linux/crypto.h:858
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
```
```
In fs/ecryptfs/crypto.c (ffffffff8140febd)
Location: include/linux/crypto.h:858
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_set_f_namelen
```
```
In fs/ecryptfs/keystore.c (ffffffff814115f2)
Location: include/linux/crypto.h:858
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff828d857d)
Location: include/linux/crypto.h:858
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
```
```
In crypto/cipher.c (ffffffff814b70e8)
Location: include/linux/crypto.h:858
Inline: True
Inline callers:
  - crypto/cipher.c:cipher_crypt_unaligned
```
```
In crypto/ablkcipher.c (ffffffff814ba8d5)
Location: include/linux/crypto.h:858
Inline: True
Inline callers:
  - crypto/ablkcipher.c:ablkcipher_walk_phys
  - crypto/ablkcipher.c:ablkcipher_walk_next
```
```
In crypto/blkcipher.c (ffffffff814bb85c)
Location: include/linux/crypto.h:858
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_aead_walk_virt_block
  - crypto/blkcipher.c:blkcipher_walk_virt_block
  - crypto/blkcipher.c:blkcipher_walk_phys
  - crypto/blkcipher.c:blkcipher_walk_virt
```
```
In crypto/skcipher.c (ffffffff814bd2c0)
Location: include/linux/crypto.h:858
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_skcipher
```
```
In crypto/hmac.c (ffffffff814c24cb)
Location: include/linux/crypto.h:858
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_setkey
```
```
In crypto/ecb.c (ffffffff814c56ba)
Location: include/linux/crypto.h:858
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_crypt
```
```
In crypto/cbc.c (0)
Location: include/linux/crypto.h:858
Inline: True
```
```
In crypto/cts.c (ffffffff814c5d5d)
Location: include/linux/crypto.h:858
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_init_tfm
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:cts_cbc_encrypt
```
```
In crypto/ctr.c (ffffffff814c7787)
Location: include/linux/crypto.h:858
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
```
```
In crypto/drbg.c (ffffffff814cf5eb)
Location: include/linux/crypto.h:858
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
```
```
In net/xfrm/xfrm_state.c (ffffffff819c514d)
Location: include/linux/crypto.h:858
Inline: True
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
In fs/verity/hash_algs.c (ffffffff81339365)
Location: include/linux/crypto.h:858
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
```
```
In fs/ecryptfs/crypto.c (ffffffff8140093d)
Location: include/linux/crypto.h:858
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_set_f_namelen
```
```
In fs/ecryptfs/keystore.c (ffffffff81402072)
Location: include/linux/crypto.h:858
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff828d0c99)
Location: include/linux/crypto.h:858
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
```
```
In crypto/cipher.c (ffffffff814a7b08)
Location: include/linux/crypto.h:858
Inline: True
Inline callers:
  - crypto/cipher.c:cipher_crypt_unaligned
```
```
In crypto/ablkcipher.c (ffffffff814ab2f5)
Location: include/linux/crypto.h:858
Inline: True
Inline callers:
  - crypto/ablkcipher.c:ablkcipher_walk_phys
  - crypto/ablkcipher.c:ablkcipher_walk_next
```
```
In crypto/blkcipher.c (ffffffff814ac27c)
Location: include/linux/crypto.h:858
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_aead_walk_virt_block
  - crypto/blkcipher.c:blkcipher_walk_virt_block
  - crypto/blkcipher.c:blkcipher_walk_phys
  - crypto/blkcipher.c:blkcipher_walk_virt
```
```
In crypto/skcipher.c (ffffffff814adce0)
Location: include/linux/crypto.h:858
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_skcipher
```
```
In crypto/hmac.c (ffffffff814b2eeb)
Location: include/linux/crypto.h:858
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_setkey
```
```
In crypto/ecb.c (ffffffff814b60da)
Location: include/linux/crypto.h:858
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_crypt
```
```
In crypto/cbc.c (0)
Location: include/linux/crypto.h:858
Inline: True
```
```
In crypto/cts.c (ffffffff814b677d)
Location: include/linux/crypto.h:858
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_init_tfm
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:cts_cbc_encrypt
```
```
In crypto/ctr.c (ffffffff814b81a7)
Location: include/linux/crypto.h:858
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
```
```
In crypto/drbg.c (ffffffff814c000b)
Location: include/linux/crypto.h:858
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
```
```
In net/xfrm/xfrm_state.c (ffffffff81981f3d)
Location: include/linux/crypto.h:858
Inline: True
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
In fs/verity/hash_algs.c (ffffffff81346155)
Location: include/linux/crypto.h:858
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
```
```
In fs/ecryptfs/crypto.c (ffffffff8140d23d)
Location: include/linux/crypto.h:858
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_set_f_namelen
```
```
In fs/ecryptfs/keystore.c (ffffffff8140e972)
Location: include/linux/crypto.h:858
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff828eb2fd)
Location: include/linux/crypto.h:858
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
```
```
In crypto/cipher.c (ffffffff814b3178)
Location: include/linux/crypto.h:858
Inline: True
Inline callers:
  - crypto/cipher.c:cipher_crypt_unaligned
```
```
In crypto/ablkcipher.c (ffffffff814b6965)
Location: include/linux/crypto.h:858
Inline: True
Inline callers:
  - crypto/ablkcipher.c:ablkcipher_walk_phys
  - crypto/ablkcipher.c:ablkcipher_walk_next
```
```
In crypto/blkcipher.c (ffffffff814b78ec)
Location: include/linux/crypto.h:858
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_aead_walk_virt_block
  - crypto/blkcipher.c:blkcipher_walk_virt_block
  - crypto/blkcipher.c:blkcipher_walk_phys
  - crypto/blkcipher.c:blkcipher_walk_virt
```
```
In crypto/skcipher.c (ffffffff814b9350)
Location: include/linux/crypto.h:858
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_skcipher
```
```
In crypto/hmac.c (ffffffff814be55b)
Location: include/linux/crypto.h:858
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_setkey
```
```
In crypto/ecb.c (ffffffff814c174a)
Location: include/linux/crypto.h:858
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_crypt
```
```
In crypto/cbc.c (0)
Location: include/linux/crypto.h:858
Inline: True
```
```
In crypto/cts.c (ffffffff814c1ded)
Location: include/linux/crypto.h:858
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_init_tfm
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:cts_cbc_encrypt
```
```
In crypto/ctr.c (ffffffff814c3817)
Location: include/linux/crypto.h:858
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
```
```
In crypto/drbg.c (ffffffff814cb67b)
Location: include/linux/crypto.h:858
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
```
```
In net/xfrm/xfrm_state.c (ffffffff81a2fbcd)
Location: include/linux/crypto.h:858
Inline: True
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
In fs/verity/hash_algs.c (ffffffff81359435)
Location: include/linux/crypto.h:858
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
```
```
In fs/ecryptfs/crypto.c (ffffffff81422ebd)
Location: include/linux/crypto.h:858
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_set_f_namelen
```
```
In fs/ecryptfs/keystore.c (ffffffff814245e2)
Location: include/linux/crypto.h:858
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff828f0713)
Location: include/linux/crypto.h:858
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
```
```
In crypto/cipher.c (ffffffff814cbbf8)
Location: include/linux/crypto.h:858
Inline: True
Inline callers:
  - crypto/cipher.c:cipher_crypt_unaligned
```
```
In crypto/ablkcipher.c (ffffffff814cf3f5)
Location: include/linux/crypto.h:858
Inline: True
Inline callers:
  - crypto/ablkcipher.c:ablkcipher_walk_phys
  - crypto/ablkcipher.c:ablkcipher_walk_next
```
```
In crypto/blkcipher.c (ffffffff814d03cc)
Location: include/linux/crypto.h:858
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_aead_walk_virt_block
  - crypto/blkcipher.c:blkcipher_walk_virt_block
  - crypto/blkcipher.c:blkcipher_walk_phys
  - crypto/blkcipher.c:blkcipher_walk_virt
```
```
In crypto/skcipher.c (ffffffff814d1df0)
Location: include/linux/crypto.h:858
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_skcipher
```
```
In crypto/hmac.c (ffffffff814d702b)
Location: include/linux/crypto.h:858
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_setkey
```
```
In crypto/ecb.c (ffffffff814da21a)
Location: include/linux/crypto.h:858
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_crypt
```
```
In crypto/cbc.c (0)
Location: include/linux/crypto.h:858
Inline: True
```
```
In crypto/cts.c (ffffffff814da8bd)
Location: include/linux/crypto.h:858
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_init_tfm
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:cts_cbc_encrypt
```
```
In crypto/ctr.c (ffffffff814dc2e7)
Location: include/linux/crypto.h:858
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
```
```
In crypto/drbg.c (ffffffff814e414b)
Location: include/linux/crypto.h:858
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
```
```
In net/xfrm/xfrm_state.c (ffffffff81a3b56d)
Location: include/linux/crypto.h:858
Inline: True
```
</details>
</li>
</ul>

## Differences
