# Function: <code>crypto_skcipher_blocksize</code>

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
In fs/ecryptfs/crypto.c (ffffffff8133b863)
Location: include/crypto/skcipher.h:319
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_set_f_namelen
```
```
In fs/ecryptfs/keystore.c (ffffffff8133cdda)
Location: include/crypto/skcipher.h:319
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/big_key.c (ffffffff8136bc86)
Location: include/crypto/skcipher.h:319
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_read
  - security/keys/big_key.c:big_key_preparse
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff81fc2efa)
Location: include/crypto/skcipher.h:319
Inline: True
```
```
In crypto/cts.c (ffffffff813e7dcd)
Location: include/crypto/skcipher.h:319
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_init_tfm
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:cts_cbc_encrypt
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
Location: include/crypto/skcipher.h:319
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_set_f_namelen
```
```
In fs/ecryptfs/keystore.c (ffffffff81352b6a)
Location: include/crypto/skcipher.h:319
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/big_key.c (ffffffff813824a6)
Location: include/crypto/skcipher.h:319
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_read
  - security/keys/big_key.c:big_key_preparse
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff81fff946)
Location: include/crypto/skcipher.h:319
Inline: True
```
```
In crypto/skcipher.c (ffffffff813f6a71)
Location: include/crypto/skcipher.h:319
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_skcipher
```
```
In crypto/cbc.c (ffffffff814003c1)
Location: include/crypto/skcipher.h:319
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cbc.c:crypto_cbc_decrypt
```
```
In crypto/cts.c (ffffffff81400bfd)
Location: include/crypto/skcipher.h:319
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_init_tfm
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:cts_cbc_encrypt
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
Location: include/crypto/skcipher.h:353
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_set_f_namelen
```
```
In fs/ecryptfs/keystore.c (ffffffff8136769f)
Location: include/crypto/skcipher.h:353
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/big_key.c (ffffffff81396b57)
Location: include/crypto/skcipher.h:353
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_read
  - security/keys/big_key.c:big_key_preparse
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff820e2bd4)
Location: include/crypto/skcipher.h:353
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
```
```
In crypto/skcipher.c (ffffffff81402e4e)
Location: include/crypto/skcipher.h:353
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_skcipher
```
```
In crypto/cbc.c (0)
Location: include/crypto/skcipher.h:353
Inline: True
```
```
In crypto/cts.c (ffffffff8140dbad)
Location: include/crypto/skcipher.h:353
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_init_tfm
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:cts_cbc_encrypt
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
Location: include/crypto/skcipher.h:353
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_set_f_namelen
```
```
In fs/ecryptfs/keystore.c (ffffffff8138c32f)
Location: include/crypto/skcipher.h:353
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff826eb83a)
Location: include/crypto/skcipher.h:353
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
```
```
In crypto/skcipher.c (ffffffff8142b4bd)
Location: include/crypto/skcipher.h:353
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_skcipher
```
```
In crypto/cbc.c (0)
Location: include/crypto/skcipher.h:353
Inline: True
```
```
In crypto/cts.c (ffffffff8143664d)
Location: include/crypto/skcipher.h:353
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_init_tfm
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:cts_cbc_encrypt
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
Location: include/crypto/skcipher.h:353
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_set_f_namelen
```
```
In fs/ecryptfs/keystore.c (ffffffff813bb177)
Location: include/crypto/skcipher.h:353
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff82715d5f)
Location: include/crypto/skcipher.h:353
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
```
```
In crypto/skcipher.c (ffffffff8145e1d9)
Location: include/crypto/skcipher.h:353
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_skcipher
```
```
In crypto/cbc.c (0)
Location: include/crypto/skcipher.h:353
Inline: True
```
```
In crypto/cts.c (ffffffff814691bd)
Location: include/crypto/skcipher.h:353
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_init_tfm
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:cts_cbc_encrypt
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
Location: include/crypto/skcipher.h:366
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_set_f_namelen
```
```
In fs/ecryptfs/keystore.c (ffffffff813d4778)
Location: include/crypto/skcipher.h:366
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff828cd1a1)
Location: include/crypto/skcipher.h:366
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
```
```
In crypto/skcipher.c (ffffffff8147ba79)
Location: include/crypto/skcipher.h:366
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_skcipher
```
```
In crypto/cbc.c (0)
Location: include/crypto/skcipher.h:366
Inline: True
```
```
In crypto/cts.c (ffffffff81486b8d)
Location: include/crypto/skcipher.h:366
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_init_tfm
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:cts_cbc_encrypt
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
Location: include/crypto/skcipher.h:301
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_set_f_namelen
```
```
In fs/ecryptfs/keystore.c (ffffffff813ff122)
Location: include/crypto/skcipher.h:301
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff828e6bde)
Location: include/crypto/skcipher.h:301
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
```
```
In crypto/skcipher.c (ffffffff814a9e19)
Location: include/crypto/skcipher.h:301
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_skcipher
```
```
In crypto/cbc.c (0)
Location: include/crypto/skcipher.h:301
Inline: True
```
```
In crypto/cts.c (ffffffff814b4cad)
Location: include/crypto/skcipher.h:301
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_init_tfm
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:cts_cbc_encrypt
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
In fs/ecryptfs/crypto.c (ffffffff814178dd)
Location: include/crypto/skcipher.h:301
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_set_f_namelen
```
```
In fs/ecryptfs/keystore.c (ffffffff81419012)
Location: include/crypto/skcipher.h:301
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff828ef6c9)
Location: include/crypto/skcipher.h:301
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
```
```
In crypto/skcipher.c (ffffffff814c4b09)
Location: include/crypto/skcipher.h:301
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_skcipher
```
```
In crypto/cbc.c (0)
Location: include/crypto/skcipher.h:301
Inline: True
```
```
In crypto/cts.c (ffffffff814cd77d)
Location: include/crypto/skcipher.h:301
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_init_tfm
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:cts_cbc_encrypt
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
In fs/ecryptfs/crypto.c (ffffffff81465dfd)
Location: include/crypto/skcipher.h:270
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_set_f_namelen
```
```
In fs/ecryptfs/keystore.c (ffffffff8146819e)
Location: include/crypto/skcipher.h:270
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff82d048dd)
Location: include/crypto/skcipher.h:270
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
```
```
In crypto/skcipher.c (ffffffff81523c8f)
Location: include/crypto/skcipher.h:270
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_async
  - crypto/skcipher.c:skcipher_walk_virt
```
```
In crypto/cbc.c (ffffffff8152ca38)
Location: include/crypto/skcipher.h:270
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_decrypt
```
```
In crypto/cts.c (ffffffff8152cb9d)
Location: include/crypto/skcipher.h:270
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_init_tfm
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:cts_cbc_encrypt
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
In fs/ecryptfs/crypto.c (ffffffff8148169d)
Location: include/crypto/skcipher.h:270
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_set_f_namelen
```
```
In fs/ecryptfs/keystore.c (ffffffff8148361e)
Location: include/crypto/skcipher.h:270
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff82ff1caa)
Location: include/crypto/skcipher.h:270
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
```
```
In crypto/skcipher.c (ffffffff81540bdf)
Location: include/crypto/skcipher.h:270
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_async
  - crypto/skcipher.c:skcipher_walk_virt
```
```
In crypto/cbc.c (ffffffff815499d2)
Location: include/crypto/skcipher.h:270
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_decrypt_inplace
  - crypto/cbc.c:crypto_cbc_decrypt_segment
  - crypto/cbc.c:crypto_cbc_encrypt
```
```
In crypto/cts.c (ffffffff81549c0d)
Location: include/crypto/skcipher.h:270
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_init_tfm
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:cts_cbc_encrypt
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
In fs/ecryptfs/crypto.c (ffffffff81487101)
Location: include/crypto/skcipher.h:272
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_set_f_namelen
```
```
In fs/ecryptfs/keystore.c (ffffffff814890ae)
Location: include/crypto/skcipher.h:272
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff831fc634)
Location: include/crypto/skcipher.h:272
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
```
```
In crypto/skcipher.c (ffffffff8154923f)
Location: include/crypto/skcipher.h:272
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_async
  - crypto/skcipher.c:skcipher_walk_virt
```
```
In crypto/cbc.c (ffffffff815520fd)
Location: include/crypto/skcipher.h:272
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cbc.c:crypto_cbc_encrypt
```
```
In crypto/cts.c (ffffffff8155224d)
Location: include/crypto/skcipher.h:272
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_init_tfm
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:cts_cbc_encrypt
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
In fs/ecryptfs/crypto.c (ffffffff814de8a1)
Location: include/crypto/skcipher.h:272
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_set_f_namelen
```
```
In fs/ecryptfs/keystore.c (ffffffff814e08ae)
Location: include/crypto/skcipher.h:272
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff832e3686)
Location: include/crypto/skcipher.h:272
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
```
```
In crypto/skcipher.c (ffffffff815a9a1f)
Location: include/crypto/skcipher.h:272
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_async
  - crypto/skcipher.c:skcipher_walk_virt
```
```
In crypto/cbc.c (ffffffff815b30fd)
Location: include/crypto/skcipher.h:272
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cbc.c:crypto_cbc_encrypt
```
```
In crypto/cts.c (ffffffff815b324d)
Location: include/crypto/skcipher.h:272
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_init_tfm
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:cts_cbc_encrypt
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
In fs/ecryptfs/crypto.c (ffffffff8156c893)
Location: include/crypto/skcipher.h:276
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_set_f_namelen
```
```
In fs/ecryptfs/keystore.c (ffffffff8156ea5e)
Location: include/crypto/skcipher.h:276
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff83499a96)
Location: include/crypto/skcipher.h:276
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
```
```
In crypto/skcipher.c (ffffffff81650ec3)
Location: include/crypto/skcipher.h:276
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_async
  - crypto/skcipher.c:skcipher_walk_virt
```
```
In crypto/cbc.c (ffffffff8165bd2f)
Location: include/crypto/skcipher.h:276
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cbc.c:crypto_cbc_decrypt_inplace
  - crypto/cbc.c:crypto_cbc_encrypt
```
```
In crypto/cts.c (ffffffff8165c22d)
Location: include/crypto/skcipher.h:276
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_init_tfm
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:cts_cbc_encrypt
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
In fs/ecryptfs/crypto.c (ffffffff81610b53)
Location: include/crypto/skcipher.h:276
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_set_f_namelen
```
```
In fs/ecryptfs/keystore.c (ffffffff81613b9b)
Location: include/crypto/skcipher.h:276
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff83ecfbc4)
Location: include/crypto/skcipher.h:276
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
```
```
In crypto/skcipher.c (ffffffff8170a6e3)
Location: include/crypto/skcipher.h:276
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_async
  - crypto/skcipher.c:skcipher_walk_virt
```
```
In crypto/cbc.c (ffffffff81715495)
Location: include/crypto/skcipher.h:276
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_decrypt_inplace
  - crypto/cbc.c:crypto_cbc_decrypt_segment
  - crypto/cbc.c:crypto_cbc_encrypt_inplace
  - crypto/cbc.c:crypto_cbc_encrypt_segment
```
```
In crypto/cts.c (ffffffff81715bed)
Location: include/crypto/skcipher.h:276
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_init_tfm
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:cts_cbc_encrypt
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
In fs/ecryptfs/crypto.c (ffffffff81648a0b)
Location: include/crypto/skcipher.h:298
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_set_f_namelen
```
```
In fs/ecryptfs/keystore.c (ffffffff8164bbfb)
Location: include/crypto/skcipher.h:298
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff836f4c82)
Location: include/crypto/skcipher.h:298
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
```
```
In crypto/skcipher.c (ffffffff81743f33)
Location: include/crypto/skcipher.h:298
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_async
  - crypto/skcipher.c:skcipher_walk_virt
```
```
In crypto/cbc.c (ffffffff81750d45)
Location: include/crypto/skcipher.h:298
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_decrypt_inplace
  - crypto/cbc.c:crypto_cbc_decrypt_segment
  - crypto/cbc.c:crypto_cbc_encrypt_inplace
  - crypto/cbc.c:crypto_cbc_encrypt_segment
```
```
In crypto/cts.c (ffffffff8175149d)
Location: include/crypto/skcipher.h:298
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_init_tfm
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:cts_cbc_encrypt
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
In fs/ecryptfs/crypto.c (ffffffff81681edb)
Location: include/crypto/skcipher.h:456
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_set_f_namelen
```
```
In fs/ecryptfs/keystore.c (ffffffff8168512a)
Location: include/crypto/skcipher.h:456
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff83927e82)
Location: include/crypto/skcipher.h:456
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
```
```
In crypto/skcipher.c (ffffffff81785f2d)
Location: include/crypto/skcipher.h:456
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_skcipher
```
```
In crypto/cts.c (ffffffff817932ed)
Location: include/crypto/skcipher.h:456
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_init_tfm
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:cts_cbc_encrypt
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
In fs/ecryptfs/crypto.c (ffff8000104f94d0)
Location: include/crypto/skcipher.h:301
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_set_f_namelen
```
```
In fs/ecryptfs/keystore.c (ffff8000104fa85c)
Location: include/crypto/skcipher.h:301
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (ffff8000114693ac)
Location: include/crypto/skcipher.h:301
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
```
```
In crypto/skcipher.c (ffff8000105bf560)
Location: include/crypto/skcipher.h:301
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_skcipher
```
```
In crypto/cbc.c (0)
Location: include/crypto/skcipher.h:301
Inline: True
```
```
In crypto/cts.c (ffff8000105c9668)
Location: include/crypto/skcipher.h:301
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_init_tfm
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:cts_cbc_encrypt
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
In fs/ecryptfs/crypto.c (c06b6d80)
Location: include/crypto/skcipher.h:301
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_set_f_namelen
```
```
In fs/ecryptfs/keystore.c (c06b7fac)
Location: include/crypto/skcipher.h:301
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (c1541ef4)
Location: include/crypto/skcipher.h:301
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
```
```
In crypto/skcipher.c (c076d2bc)
Location: include/crypto/skcipher.h:301
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_skcipher
```
```
In crypto/cbc.c (0)
Location: include/crypto/skcipher.h:301
Inline: True
```
```
In crypto/cts.c (c0777208)
Location: include/crypto/skcipher.h:301
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_init_tfm
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:cts_cbc_encrypt
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
In fs/ecryptfs/crypto.c (c00000000063b850)
Location: include/crypto/skcipher.h:301
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_set_f_namelen
```
```
In fs/ecryptfs/keystore.c (c00000000063d0d0)
Location: include/crypto/skcipher.h:301
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (c000000001397524)
Location: include/crypto/skcipher.h:301
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
```
```
In crypto/skcipher.c (c0000000007472b4)
Location: include/crypto/skcipher.h:301
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_skcipher
```
```
In crypto/cbc.c (0)
Location: include/crypto/skcipher.h:301
Inline: True
```
```
In crypto/cts.c (c000000000753cc8)
Location: include/crypto/skcipher.h:301
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_init_tfm
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:cts_cbc_encrypt
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
In fs/ecryptfs/crypto.c (ffffffe000367c32)
Location: include/crypto/skcipher.h:301
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_set_f_namelen
```
```
In fs/ecryptfs/keystore.c (ffffffe000369042)
Location: include/crypto/skcipher.h:301
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffe0000245fe)
Location: include/crypto/skcipher.h:301
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
```
```
In crypto/skcipher.c (ffffffe00040471e)
Location: include/crypto/skcipher.h:301
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_skcipher
```
```
In crypto/cbc.c (0)
Location: include/crypto/skcipher.h:301
Inline: True
```
```
In crypto/cts.c (ffffffe00040e334)
Location: include/crypto/skcipher.h:301
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_init_tfm
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:cts_cbc_encrypt
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
In fs/ecryptfs/crypto.c (ffffffff8140febd)
Location: include/crypto/skcipher.h:301
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_set_f_namelen
```
```
In fs/ecryptfs/keystore.c (ffffffff814115f2)
Location: include/crypto/skcipher.h:301
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff828d857d)
Location: include/crypto/skcipher.h:301
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
```
```
In crypto/skcipher.c (ffffffff814bd0e9)
Location: include/crypto/skcipher.h:301
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_skcipher
```
```
In crypto/cbc.c (0)
Location: include/crypto/skcipher.h:301
Inline: True
```
```
In crypto/cts.c (ffffffff814c5d5d)
Location: include/crypto/skcipher.h:301
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_init_tfm
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:cts_cbc_encrypt
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
In fs/ecryptfs/crypto.c (ffffffff8140093d)
Location: include/crypto/skcipher.h:301
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_set_f_namelen
```
```
In fs/ecryptfs/keystore.c (ffffffff81402072)
Location: include/crypto/skcipher.h:301
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff828d0c99)
Location: include/crypto/skcipher.h:301
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
```
```
In crypto/skcipher.c (ffffffff814adb09)
Location: include/crypto/skcipher.h:301
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_skcipher
```
```
In crypto/cbc.c (0)
Location: include/crypto/skcipher.h:301
Inline: True
```
```
In crypto/cts.c (ffffffff814b677d)
Location: include/crypto/skcipher.h:301
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_init_tfm
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:cts_cbc_encrypt
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
In fs/ecryptfs/crypto.c (ffffffff8140d23d)
Location: include/crypto/skcipher.h:301
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_set_f_namelen
```
```
In fs/ecryptfs/keystore.c (ffffffff8140e972)
Location: include/crypto/skcipher.h:301
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff828eb2fd)
Location: include/crypto/skcipher.h:301
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
```
```
In crypto/skcipher.c (ffffffff814b9179)
Location: include/crypto/skcipher.h:301
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_skcipher
```
```
In crypto/cbc.c (0)
Location: include/crypto/skcipher.h:301
Inline: True
```
```
In crypto/cts.c (ffffffff814c1ded)
Location: include/crypto/skcipher.h:301
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_init_tfm
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:cts_cbc_encrypt
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
In fs/ecryptfs/crypto.c (ffffffff81422ebd)
Location: include/crypto/skcipher.h:301
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_set_f_namelen
```
```
In fs/ecryptfs/keystore.c (ffffffff814245e2)
Location: include/crypto/skcipher.h:301
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff828f0713)
Location: include/crypto/skcipher.h:301
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
```
```
In crypto/skcipher.c (ffffffff814d1c39)
Location: include/crypto/skcipher.h:301
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_skcipher
```
```
In crypto/cbc.c (0)
Location: include/crypto/skcipher.h:301
Inline: True
```
```
In crypto/cts.c (ffffffff814da8bd)
Location: include/crypto/skcipher.h:301
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_init_tfm
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:cts_cbc_encrypt
```
</details>
</li>
</ul>

## Differences
