# Function: <code>crypto_aead_alg</code>

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
In crypto/aead.c (ffffffff8139eed5)
Location: include/crypto/aead.h:193
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_init_tfm
  - crypto/aead.c:aead_geniv_setauthsize
```
```
In crypto/blkcipher.c (0)
Location: include/crypto/aead.h:193
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
In crypto/aead.c (ffffffff813dbd30)
Location: include/crypto/aead.h:196
Inline: True
Inline callers:
  - crypto/aead.c:aead_geniv_setauthsize
  - crypto/aead.c:crypto_aead_init_tfm
```
```
In crypto/blkcipher.c (0)
Location: include/crypto/aead.h:196
Inline: True
```
```
In crypto/seqiv.c (ffffffff813dea34)
Location: include/crypto/aead.h:196
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
  - crypto/seqiv.c:seqiv_aead_encrypt_complete2
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
In crypto/aead.c (ffffffff813f3610)
Location: include/crypto/aead.h:196
Inline: True
Inline callers:
  - crypto/aead.c:aead_geniv_setauthsize
  - crypto/aead.c:crypto_aead_init_tfm
```
```
In crypto/blkcipher.c (0)
Location: include/crypto/aead.h:196
Inline: True
```
```
In crypto/skcipher.c (0)
Location: include/crypto/aead.h:196
Inline: True
```
```
In crypto/seqiv.c (ffffffff813f6fd4)
Location: include/crypto/aead.h:196
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
  - crypto/seqiv.c:seqiv_aead_encrypt_complete2
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
In crypto/aead.c (ffffffff813ff930)
Location: include/crypto/aead.h:196
Inline: True
Inline callers:
  - crypto/aead.c:aead_geniv_setauthsize
  - crypto/aead.c:crypto_aead_init_tfm
```
```
In crypto/blkcipher.c (0)
Location: include/crypto/aead.h:196
Inline: True
```
```
In crypto/skcipher.c (0)
Location: include/crypto/aead.h:196
Inline: True
```
```
In crypto/seqiv.c (ffffffff814033d0)
Location: include/crypto/aead.h:196
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
In security/keys/big_key.c (0)
Location: include/crypto/aead.h:196
Inline: True
```
```
In crypto/aead.c (ffffffff81427f00)
Location: include/crypto/aead.h:196
Inline: True
Inline callers:
  - crypto/aead.c:aead_geniv_setauthsize
  - crypto/aead.c:crypto_aead_init_tfm
```
```
In crypto/blkcipher.c (0)
Location: include/crypto/aead.h:196
Inline: True
```
```
In crypto/skcipher.c (0)
Location: include/crypto/aead.h:196
Inline: True
```
```
In crypto/seqiv.c (ffffffff8142bac6)
Location: include/crypto/aead.h:196
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/gcm.c (ffffffff81439ff9)
Location: include/crypto/aead.h:196
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4106_encrypt
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
In security/keys/big_key.c (ffffffff82715b9a)
Location: include/crypto/aead.h:196
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_init
  - security/keys/big_key.c:big_key_crypt
  - security/keys/big_key.c:big_key_crypt
```
```
In crypto/aead.c (ffffffff8145aeb8)
Location: include/crypto/aead.h:196
Inline: True
Inline callers:
  - crypto/aead.c:aead_init_geniv
  - crypto/aead.c:aead_geniv_setauthsize
  - crypto/aead.c:aead_geniv_setauthsize
  - crypto/aead.c:aead_geniv_setauthsize
  - crypto/aead.c:crypto_aead_init_tfm
  - crypto/aead.c:crypto_aead_exit_tfm
  - crypto/aead.c:crypto_aead_setkey
  - crypto/aead.c:crypto_aead_setkey
```
```
In crypto/blkcipher.c (ffffffff8145cd57)
Location: include/crypto/aead.h:196
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_aead_walk_virt_block
```
```
In crypto/skcipher.c (ffffffff8145e39b)
Location: include/crypto/aead.h:196
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_aead_common
```
```
In crypto/seqiv.c (ffffffff8145e5b1)
Location: include/crypto/aead.h:196
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
  - crypto/seqiv.c:seqiv_aead_encrypt
  - crypto/seqiv.c:seqiv_aead_encrypt_complete2
```
```
In crypto/gcm.c (ffffffff8146b3f0)
Location: include/crypto/aead.h:196
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_rfc4106_decrypt
  - crypto/gcm.c:crypto_rfc4106_encrypt
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
In security/keys/big_key.c (ffffffff828ccfe5)
Location: include/crypto/aead.h:193
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_init
  - security/keys/big_key.c:big_key_crypt
  - security/keys/big_key.c:big_key_crypt
```
```
In crypto/aead.c (ffffffff81478e28)
Location: include/crypto/aead.h:193
Inline: True
Inline callers:
  - crypto/aead.c:aead_init_geniv
  - crypto/aead.c:aead_geniv_setauthsize
  - crypto/aead.c:aead_geniv_setauthsize
  - crypto/aead.c:aead_geniv_setauthsize
  - crypto/aead.c:crypto_aead_init_tfm
  - crypto/aead.c:crypto_aead_exit_tfm
  - crypto/aead.c:crypto_aead_setkey
  - crypto/aead.c:crypto_aead_setkey
```
```
In crypto/blkcipher.c (ffffffff8147a5e7)
Location: include/crypto/aead.h:193
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_aead_walk_virt_block
```
```
In crypto/skcipher.c (ffffffff8147bc5b)
Location: include/crypto/aead.h:193
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_aead_common
```
```
In crypto/seqiv.c (ffffffff8147be8d)
Location: include/crypto/aead.h:193
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
  - crypto/seqiv.c:seqiv_aead_encrypt
  - crypto/seqiv.c:seqiv_aead_encrypt_complete2
```
```
In crypto/gcm.c (ffffffff8148973e)
Location: include/crypto/aead.h:193
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_rfc4106_decrypt
  - crypto/gcm.c:crypto_rfc4106_encrypt
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
In security/keys/big_key.c (ffffffff828e69b4)
Location: include/crypto/aead.h:188
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_init
```
```
In crypto/aead.c (ffffffff814a6d4a)
Location: include/crypto/aead.h:188
Inline: True
Inline callers:
  - crypto/aead.c:aead_init_geniv
  - crypto/aead.c:aead_geniv_setauthsize
  - crypto/aead.c:aead_geniv_setauthsize
  - crypto/aead.c:aead_geniv_setauthsize
  - crypto/aead.c:crypto_aead_init_tfm
  - crypto/aead.c:crypto_aead_exit_tfm
  - crypto/aead.c:crypto_aead_decrypt
  - crypto/aead.c:crypto_aead_encrypt
  - crypto/aead.c:crypto_aead_setkey
  - crypto/aead.c:crypto_aead_setkey
```
```
In crypto/blkcipher.c (ffffffff814a8617)
Location: include/crypto/aead.h:188
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_aead_walk_virt_block
```
```
In crypto/skcipher.c (ffffffff814a9ffd)
Location: include/crypto/aead.h:188
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_aead_common
```
```
In crypto/seqiv.c (ffffffff814aa28d)
Location: include/crypto/aead.h:188
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt_complete2
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
In security/keys/big_key.c (ffffffff828ef46d)
Location: include/crypto/aead.h:188
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_init
```
```
In crypto/aead.c (ffffffff814c19ba)
Location: include/crypto/aead.h:188
Inline: True
Inline callers:
  - crypto/aead.c:aead_init_geniv
  - crypto/aead.c:crypto_aead_init_tfm
  - crypto/aead.c:crypto_aead_exit_tfm
  - crypto/aead.c:crypto_aead_decrypt
  - crypto/aead.c:crypto_aead_encrypt
  - crypto/aead.c:crypto_aead_setauthsize
  - crypto/aead.c:crypto_aead_setauthsize
  - crypto/aead.c:crypto_aead_setauthsize
  - crypto/aead.c:crypto_aead_setauthsize
  - crypto/aead.c:crypto_aead_setkey
  - crypto/aead.c:crypto_aead_setkey
```
```
In crypto/blkcipher.c (ffffffff814c3287)
Location: include/crypto/aead.h:188
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_aead_walk_virt_block
```
```
In crypto/skcipher.c (ffffffff814c4ced)
Location: include/crypto/aead.h:188
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_aead_common
```
```
In crypto/seqiv.c (ffffffff814c4f4d)
Location: include/crypto/aead.h:188
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt_complete2
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
In crypto/aead.c (ffffffff81521bd5)
Location: include/crypto/aead.h:194
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_init_tfm
  - crypto/aead.c:crypto_aead_exit_tfm
  - crypto/aead.c:crypto_aead_decrypt
  - crypto/aead.c:crypto_aead_encrypt
  - crypto/aead.c:crypto_aead_setauthsize
  - crypto/aead.c:crypto_aead_setauthsize
  - crypto/aead.c:crypto_aead_setauthsize
  - crypto/aead.c:crypto_aead_setauthsize
  - crypto/aead.c:crypto_aead_setkey
  - crypto/aead.c:setkey_unaligned
```
```
In crypto/geniv.c (ffffffff815222fa)
Location: include/crypto/aead.h:194
Inline: True
Inline callers:
  - crypto/geniv.c:aead_init_geniv
```
```
In crypto/skcipher.c (ffffffff81523b7d)
Location: include/crypto/aead.h:194
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_aead_common
```
```
In crypto/seqiv.c (ffffffff81523e5d)
Location: include/crypto/aead.h:194
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt_complete2
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
In crypto/aead.c (ffffffff8153ea45)
Location: include/crypto/aead.h:199
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_init_tfm
  - crypto/aead.c:crypto_aead_exit_tfm
  - crypto/aead.c:crypto_aead_decrypt
  - crypto/aead.c:crypto_aead_encrypt
  - crypto/aead.c:crypto_aead_setauthsize
  - crypto/aead.c:crypto_aead_setauthsize
  - crypto/aead.c:crypto_aead_setauthsize
  - crypto/aead.c:crypto_aead_setauthsize
  - crypto/aead.c:crypto_aead_setkey
  - crypto/aead.c:setkey_unaligned
```
```
In crypto/geniv.c (ffffffff8153f1da)
Location: include/crypto/aead.h:199
Inline: True
Inline callers:
  - crypto/geniv.c:aead_init_geniv
```
```
In crypto/skcipher.c (ffffffff81540acd)
Location: include/crypto/aead.h:199
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_aead_common
```
```
In crypto/seqiv.c (ffffffff81540d66)
Location: include/crypto/aead.h:199
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt_complete2
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
In crypto/aead.c (ffffffff815470f5)
Location: include/crypto/aead.h:201
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_init_tfm
  - crypto/aead.c:crypto_aead_exit_tfm
  - crypto/aead.c:crypto_aead_decrypt
  - crypto/aead.c:crypto_aead_encrypt
  - crypto/aead.c:crypto_aead_setauthsize
  - crypto/aead.c:crypto_aead_setauthsize
  - crypto/aead.c:crypto_aead_setauthsize
  - crypto/aead.c:crypto_aead_setauthsize
  - crypto/aead.c:crypto_aead_setkey
  - crypto/aead.c:setkey_unaligned
```
```
In crypto/geniv.c (ffffffff8154785a)
Location: include/crypto/aead.h:201
Inline: True
Inline callers:
  - crypto/geniv.c:aead_init_geniv
```
```
In crypto/skcipher.c (ffffffff8154912d)
Location: include/crypto/aead.h:201
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_aead_common
```
```
In crypto/seqiv.c (ffffffff815493c6)
Location: include/crypto/aead.h:201
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt_complete2
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
In crypto/aead.c (ffffffff815a78d5)
Location: include/crypto/aead.h:201
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_init_tfm
  - crypto/aead.c:crypto_aead_exit_tfm
  - crypto/aead.c:crypto_aead_decrypt
  - crypto/aead.c:crypto_aead_encrypt
  - crypto/aead.c:crypto_aead_setauthsize
  - crypto/aead.c:crypto_aead_setauthsize
  - crypto/aead.c:crypto_aead_setauthsize
  - crypto/aead.c:crypto_aead_setauthsize
  - crypto/aead.c:crypto_aead_setkey
  - crypto/aead.c:setkey_unaligned
```
```
In crypto/geniv.c (ffffffff815a803a)
Location: include/crypto/aead.h:201
Inline: True
Inline callers:
  - crypto/geniv.c:aead_init_geniv
```
```
In crypto/skcipher.c (ffffffff815a990d)
Location: include/crypto/aead.h:201
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_aead_common
```
```
In crypto/seqiv.c (ffffffff815a9ba6)
Location: include/crypto/aead.h:201
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt_complete2
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
In crypto/aead.c (ffffffff8164ec05)
Location: include/crypto/aead.h:203
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_init_tfm
  - crypto/aead.c:crypto_aead_exit_tfm
  - crypto/aead.c:crypto_aead_decrypt
  - crypto/aead.c:crypto_aead_encrypt
  - crypto/aead.c:crypto_aead_setauthsize
  - crypto/aead.c:setkey_unaligned
```
```
In crypto/geniv.c (ffffffff8164f3e7)
Location: include/crypto/aead.h:203
Inline: True
Inline callers:
  - crypto/geniv.c:aead_init_geniv
```
```
In crypto/skcipher.c (ffffffff81650d6d)
Location: include/crypto/aead.h:203
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_aead_common
```
```
In crypto/seqiv.c (ffffffff81651086)
Location: include/crypto/aead.h:203
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt_complete2
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
In crypto/aead.c (ffffffff817080e5)
Location: include/crypto/aead.h:203
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_init_tfm
  - crypto/aead.c:crypto_aead_exit_tfm
  - crypto/aead.c:crypto_aead_decrypt
  - crypto/aead.c:crypto_aead_encrypt
  - crypto/aead.c:crypto_aead_setauthsize
  - crypto/aead.c:setkey_unaligned
```
```
In crypto/geniv.c (ffffffff817089e7)
Location: include/crypto/aead.h:203
Inline: True
Inline callers:
  - crypto/geniv.c:aead_init_geniv
```
```
In crypto/skcipher.c (ffffffff8170a55d)
Location: include/crypto/aead.h:203
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_aead_common
```
```
In crypto/seqiv.c (ffffffff8170a8db)
Location: include/crypto/aead.h:203
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt_complete2
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
In crypto/aead.c (ffffffff81741805)
Location: include/crypto/aead.h:225
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_init_tfm
  - crypto/aead.c:crypto_aead_exit_tfm
  - crypto/aead.c:crypto_aead_decrypt
  - crypto/aead.c:crypto_aead_encrypt
  - crypto/aead.c:crypto_aead_setauthsize
  - crypto/aead.c:setkey_unaligned
```
```
In crypto/geniv.c (ffffffff81742193)
Location: include/crypto/aead.h:225
Inline: True
Inline callers:
  - crypto/geniv.c:aead_init_geniv
```
```
In crypto/skcipher.c (ffffffff81743dad)
Location: include/crypto/aead.h:225
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_aead_common
```
```
In crypto/seqiv.c (ffffffff8174412b)
Location: include/crypto/aead.h:225
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt_complete2
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
In crypto/aead.c (ffffffff817826a5)
Location: include/crypto/aead.h:237
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_init_tfm
  - crypto/aead.c:crypto_aead_exit_tfm
  - crypto/aead.c:crypto_aead_decrypt
  - crypto/aead.c:crypto_aead_encrypt
  - crypto/aead.c:crypto_aead_setauthsize
  - crypto/aead.c:setkey_unaligned
```
```
In crypto/geniv.c (ffffffff81783073)
Location: include/crypto/aead.h:237
Inline: True
Inline callers:
  - crypto/geniv.c:aead_init_geniv
```
```
In crypto/skcipher.c (ffffffff8178618d)
Location: include/crypto/aead.h:237
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_aead_common
```
```
In crypto/seqiv.c (ffffffff817866eb)
Location: include/crypto/aead.h:237
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt_complete2
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
In security/keys/big_key.c (ffff80001146911c)
Location: include/crypto/aead.h:188
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_init
```
```
In crypto/aead.c (ffff8000105bc0cc)
Location: include/crypto/aead.h:188
Inline: True
Inline callers:
  - crypto/aead.c:aead_init_geniv
  - crypto/aead.c:crypto_aead_init_tfm
  - crypto/aead.c:crypto_aead_exit_tfm
  - crypto/aead.c:crypto_aead_decrypt
  - crypto/aead.c:crypto_aead_encrypt
  - crypto/aead.c:crypto_aead_setauthsize
  - crypto/aead.c:crypto_aead_setauthsize
  - crypto/aead.c:crypto_aead_setauthsize
  - crypto/aead.c:crypto_aead_setauthsize
  - crypto/aead.c:crypto_aead_setkey
  - crypto/aead.c:crypto_aead_setkey
```
```
In crypto/blkcipher.c (ffff8000105bda50)
Location: include/crypto/aead.h:188
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_aead_walk_virt_block
```
```
In crypto/skcipher.c (ffff8000105bf7b4)
Location: include/crypto/aead.h:188
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_aead_common
```
```
In crypto/seqiv.c (ffff8000105bfb00)
Location: include/crypto/aead.h:188
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt_complete2
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
In security/keys/big_key.c (c1541c54)
Location: include/crypto/aead.h:188
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_init
```
```
In crypto/aead.c (c076a128)
Location: include/crypto/aead.h:188
Inline: True
Inline callers:
  - crypto/aead.c:aead_init_geniv
  - crypto/aead.c:crypto_aead_init_tfm
  - crypto/aead.c:crypto_aead_exit_tfm
  - crypto/aead.c:crypto_aead_decrypt
  - crypto/aead.c:crypto_aead_encrypt
  - crypto/aead.c:crypto_aead_setauthsize
  - crypto/aead.c:crypto_aead_setauthsize
  - crypto/aead.c:crypto_aead_setauthsize
  - crypto/aead.c:crypto_aead_setauthsize
  - crypto/aead.c:crypto_aead_setkey
  - crypto/aead.c:crypto_aead_setkey
```
```
In crypto/blkcipher.c (c076b89c)
Location: include/crypto/aead.h:188
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_aead_walk_virt_block
```
```
In crypto/skcipher.c (c076d4d4)
Location: include/crypto/aead.h:188
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_aead_common
```
```
In crypto/seqiv.c (c076d75c)
Location: include/crypto/aead.h:188
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt_complete2
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
In security/keys/big_key.c (c0000000013971b4)
Location: include/crypto/aead.h:188
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_init
```
```
In crypto/aead.c (c000000000742a28)
Location: include/crypto/aead.h:188
Inline: True
Inline callers:
  - crypto/aead.c:aead_init_geniv
  - crypto/aead.c:crypto_aead_init_tfm
  - crypto/aead.c:crypto_aead_exit_tfm
  - crypto/aead.c:crypto_aead_decrypt
  - crypto/aead.c:crypto_aead_encrypt
  - crypto/aead.c:crypto_aead_setauthsize
  - crypto/aead.c:crypto_aead_setauthsize
  - crypto/aead.c:crypto_aead_setauthsize
  - crypto/aead.c:crypto_aead_setauthsize
  - crypto/aead.c:crypto_aead_setkey
  - crypto/aead.c:crypto_aead_setkey
```
```
In crypto/blkcipher.c (c000000000744e6c)
Location: include/crypto/aead.h:188
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_aead_walk_virt_block
```
```
In crypto/skcipher.c (c00000000074755c)
Location: include/crypto/aead.h:188
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_aead_common
```
```
In crypto/seqiv.c (c000000000747908)
Location: include/crypto/aead.h:188
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt_complete2
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
In security/keys/big_key.c (ffffffe000024362)
Location: include/crypto/aead.h:188
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_init
```
```
In crypto/aead.c (ffffffe00040184c)
Location: include/crypto/aead.h:188
Inline: True
Inline callers:
  - crypto/aead.c:aead_init_geniv
  - crypto/aead.c:crypto_aead_init_tfm
  - crypto/aead.c:crypto_aead_exit_tfm
  - crypto/aead.c:crypto_aead_decrypt
  - crypto/aead.c:crypto_aead_encrypt
  - crypto/aead.c:crypto_aead_setauthsize
  - crypto/aead.c:crypto_aead_setauthsize
  - crypto/aead.c:crypto_aead_setauthsize
  - crypto/aead.c:crypto_aead_setauthsize
  - crypto/aead.c:crypto_aead_setkey
  - crypto/aead.c:crypto_aead_setkey
```
```
In crypto/blkcipher.c (ffffffe000403000)
Location: include/crypto/aead.h:188
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_aead_walk_virt_block
```
```
In crypto/skcipher.c (ffffffe0004048fa)
Location: include/crypto/aead.h:188
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_aead_common
```
```
In crypto/seqiv.c (ffffffe000404bdc)
Location: include/crypto/aead.h:188
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt_complete2
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
In security/keys/big_key.c (ffffffff828d8321)
Location: include/crypto/aead.h:188
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_init
```
```
In crypto/aead.c (ffffffff814b9f9a)
Location: include/crypto/aead.h:188
Inline: True
Inline callers:
  - crypto/aead.c:aead_init_geniv
  - crypto/aead.c:crypto_aead_init_tfm
  - crypto/aead.c:crypto_aead_exit_tfm
  - crypto/aead.c:crypto_aead_decrypt
  - crypto/aead.c:crypto_aead_encrypt
  - crypto/aead.c:crypto_aead_setauthsize
  - crypto/aead.c:crypto_aead_setauthsize
  - crypto/aead.c:crypto_aead_setauthsize
  - crypto/aead.c:crypto_aead_setauthsize
  - crypto/aead.c:crypto_aead_setkey
  - crypto/aead.c:crypto_aead_setkey
```
```
In crypto/blkcipher.c (ffffffff814bb867)
Location: include/crypto/aead.h:188
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_aead_walk_virt_block
```
```
In crypto/skcipher.c (ffffffff814bd2cd)
Location: include/crypto/aead.h:188
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_aead_common
```
```
In crypto/seqiv.c (ffffffff814bd52d)
Location: include/crypto/aead.h:188
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt_complete2
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
In security/keys/big_key.c (ffffffff828d0a3d)
Location: include/crypto/aead.h:188
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_init
```
```
In crypto/aead.c (ffffffff814aa9ba)
Location: include/crypto/aead.h:188
Inline: True
Inline callers:
  - crypto/aead.c:aead_init_geniv
  - crypto/aead.c:crypto_aead_init_tfm
  - crypto/aead.c:crypto_aead_exit_tfm
  - crypto/aead.c:crypto_aead_decrypt
  - crypto/aead.c:crypto_aead_encrypt
  - crypto/aead.c:crypto_aead_setauthsize
  - crypto/aead.c:crypto_aead_setauthsize
  - crypto/aead.c:crypto_aead_setauthsize
  - crypto/aead.c:crypto_aead_setauthsize
  - crypto/aead.c:crypto_aead_setkey
  - crypto/aead.c:crypto_aead_setkey
```
```
In crypto/blkcipher.c (ffffffff814ac287)
Location: include/crypto/aead.h:188
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_aead_walk_virt_block
```
```
In crypto/skcipher.c (ffffffff814adced)
Location: include/crypto/aead.h:188
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_aead_common
```
```
In crypto/seqiv.c (ffffffff814adf4d)
Location: include/crypto/aead.h:188
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt_complete2
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
In security/keys/big_key.c (ffffffff828eb0a1)
Location: include/crypto/aead.h:188
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_init
```
```
In crypto/aead.c (ffffffff814b602a)
Location: include/crypto/aead.h:188
Inline: True
Inline callers:
  - crypto/aead.c:aead_init_geniv
  - crypto/aead.c:crypto_aead_init_tfm
  - crypto/aead.c:crypto_aead_exit_tfm
  - crypto/aead.c:crypto_aead_decrypt
  - crypto/aead.c:crypto_aead_encrypt
  - crypto/aead.c:crypto_aead_setauthsize
  - crypto/aead.c:crypto_aead_setauthsize
  - crypto/aead.c:crypto_aead_setauthsize
  - crypto/aead.c:crypto_aead_setauthsize
  - crypto/aead.c:crypto_aead_setkey
  - crypto/aead.c:crypto_aead_setkey
```
```
In crypto/blkcipher.c (ffffffff814b78f7)
Location: include/crypto/aead.h:188
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_aead_walk_virt_block
```
```
In crypto/skcipher.c (ffffffff814b935d)
Location: include/crypto/aead.h:188
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_aead_common
```
```
In crypto/seqiv.c (ffffffff814b95bd)
Location: include/crypto/aead.h:188
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt_complete2
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
In security/keys/big_key.c (ffffffff828f04b7)
Location: include/crypto/aead.h:188
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_init
```
```
In crypto/aead.c (ffffffff814ceaca)
Location: include/crypto/aead.h:188
Inline: True
Inline callers:
  - crypto/aead.c:aead_init_geniv
  - crypto/aead.c:crypto_aead_init_tfm
  - crypto/aead.c:crypto_aead_exit_tfm
  - crypto/aead.c:crypto_aead_decrypt
  - crypto/aead.c:crypto_aead_encrypt
  - crypto/aead.c:crypto_aead_setauthsize
  - crypto/aead.c:crypto_aead_setauthsize
  - crypto/aead.c:crypto_aead_setauthsize
  - crypto/aead.c:crypto_aead_setauthsize
  - crypto/aead.c:crypto_aead_setkey
  - crypto/aead.c:crypto_aead_setkey
```
```
In crypto/blkcipher.c (ffffffff814d03d7)
Location: include/crypto/aead.h:188
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_aead_walk_virt_block
```
```
In crypto/skcipher.c (ffffffff814d1dfd)
Location: include/crypto/aead.h:188
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_aead_common
```
```
In crypto/seqiv.c (ffffffff814d205d)
Location: include/crypto/aead.h:188
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt_complete2
```
</details>
</li>
</ul>

## Differences
