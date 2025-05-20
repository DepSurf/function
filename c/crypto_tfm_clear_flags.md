# Function: <code>crypto_tfm_clear_flags</code>

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
In fs/ext4/crypto_key.c (0)
Location: include/linux/crypto.h:671
Inline: True
```
```
In crypto/skcipher.c (ffffffff813a1a33)
Location: include/linux/crypto.h:671
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_blkcipher
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
```
```
In crypto/ecb.c (ffffffff813a8e63)
Location: include/linux/crypto.h:671
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_setkey
```
```
In crypto/cbc.c (ffffffff813a91b3)
Location: include/linux/crypto.h:671
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_setkey
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
In fs/crypto/keyinfo.c (0)
Location: include/linux/crypto.h:646
Inline: True
```
```
In crypto/skcipher.c (ffffffff813de003)
Location: include/linux/crypto.h:646
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
  - crypto/skcipher.c:skcipher_setkey_blkcipher
```
```
In crypto/ecb.c (ffffffff813e6e33)
Location: include/linux/crypto.h:646
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_setkey
```
```
In crypto/cbc.c (ffffffff813e7173)
Location: include/linux/crypto.h:646
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_setkey
```
```
In crypto/cts.c (ffffffff813e7743)
Location: include/linux/crypto.h:646
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_setkey
```
```
In crypto/xts.c (ffffffff813e80e6)
Location: include/linux/crypto.h:646
Inline: True
Inline callers:
  - crypto/xts.c:setkey
  - crypto/xts.c:setkey
```
```
In crypto/ctr.c (ffffffff813e8839)
Location: include/linux/crypto.h:646
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_setkey
  - crypto/ctr.c:crypto_ctr_setkey
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
In fs/crypto/keyinfo.c (0)
Location: include/linux/crypto.h:649
Inline: True
```
```
In crypto/skcipher.c (ffffffff813f58d3)
Location: include/linux/crypto.h:649
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
  - crypto/skcipher.c:skcipher_setkey_blkcipher
```
```
In crypto/ecb.c (ffffffff813ffbe3)
Location: include/linux/crypto.h:649
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_setkey
```
```
In crypto/cbc.c (ffffffff813fff23)
Location: include/linux/crypto.h:649
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_setkey
```
```
In crypto/cts.c (ffffffff81400573)
Location: include/linux/crypto.h:649
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_setkey
```
```
In crypto/xts.c (ffffffff81401305)
Location: include/linux/crypto.h:649
Inline: True
```
```
In crypto/ctr.c (ffffffff81401e49)
Location: include/linux/crypto.h:649
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_setkey
  - crypto/ctr.c:crypto_ctr_setkey
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
In fs/crypto/keyinfo.c (0)
Location: include/linux/crypto.h:649
Inline: True
```
```
In crypto/skcipher.c (ffffffff81401b73)
Location: include/linux/crypto.h:649
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
  - crypto/skcipher.c:skcipher_setkey_blkcipher
```
```
In crypto/ecb.c (ffffffff8140ced3)
Location: include/linux/crypto.h:649
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_setkey
```
```
In crypto/cbc.c (ffffffff8140d233)
Location: include/linux/crypto.h:649
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_setkey
```
```
In crypto/cts.c (ffffffff8140d873)
Location: include/linux/crypto.h:649
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_setkey
```
```
In crypto/xts.c (ffffffff8140e5bf)
Location: include/linux/crypto.h:649
Inline: True
Inline callers:
  - crypto/xts.c:setkey
  - crypto/xts.c:setkey
```
```
In crypto/ctr.c (ffffffff8140f294)
Location: include/linux/crypto.h:649
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_setkey
  - crypto/ctr.c:crypto_ctr_setkey
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
In fs/crypto/keyinfo.c (0)
Location: include/linux/crypto.h:697
Inline: True
```
```
In crypto/skcipher.c (ffffffff8142a1a3)
Location: include/linux/crypto.h:697
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
  - crypto/skcipher.c:skcipher_setkey_blkcipher
```
```
In crypto/ahash.c (ffffffff8142befc)
Location: include/linux/crypto.h:697
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_setkey
```
```
In crypto/shash.c (ffffffff8142ca29)
Location: include/linux/crypto.h:697
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_setkey
```
```
In crypto/ecb.c (ffffffff81435933)
Location: include/linux/crypto.h:697
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_setkey
```
```
In crypto/cbc.c (ffffffff81435ca3)
Location: include/linux/crypto.h:697
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_setkey
```
```
In crypto/cts.c (ffffffff81436303)
Location: include/linux/crypto.h:697
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_setkey
```
```
In crypto/xts.c (ffffffff8143707f)
Location: include/linux/crypto.h:697
Inline: True
Inline callers:
  - crypto/xts.c:setkey
  - crypto/xts.c:setkey
```
```
In crypto/ctr.c (ffffffff81437e64)
Location: include/linux/crypto.h:697
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_setkey
  - crypto/ctr.c:crypto_ctr_setkey
```
```
In crypto/gcm.c (ffffffff81438ef4)
Location: include/linux/crypto.h:697
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_setkey
  - crypto/gcm.c:crypto_rfc4106_setkey
  - crypto/gcm.c:crypto_gcm_setkey
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
In crypto/aead.c (ffffffff8145adad)
Location: include/linux/crypto.h:710
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_setkey
```
```
In crypto/skcipher.c (ffffffff8145d3ed)
Location: include/linux/crypto.h:710
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
  - crypto/skcipher.c:skcipher_setkey_blkcipher
```
```
In crypto/ahash.c (ffffffff8145ebec)
Location: include/linux/crypto.h:710
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_setkey
```
```
In crypto/shash.c (ffffffff8145f689)
Location: include/linux/crypto.h:710
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_setkey
```
```
In crypto/ecb.c (ffffffff814684c3)
Location: include/linux/crypto.h:710
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_setkey
```
```
In crypto/cbc.c (ffffffff81468833)
Location: include/linux/crypto.h:710
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_setkey
```
```
In crypto/cts.c (ffffffff81468e53)
Location: include/linux/crypto.h:710
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_setkey
```
```
In crypto/xts.c (ffffffff81469aaa)
Location: include/linux/crypto.h:710
Inline: True
```
```
In crypto/ctr.c (ffffffff8146a7c4)
Location: include/linux/crypto.h:710
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_setkey
  - crypto/ctr.c:crypto_ctr_setkey
```
```
In crypto/gcm.c (ffffffff8146b204)
Location: include/linux/crypto.h:710
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_setkey
  - crypto/gcm.c:crypto_rfc4106_setkey
  - crypto/gcm.c:crypto_gcm_setkey
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
In crypto/aead.c (ffffffff8147891b)
Location: include/linux/crypto.h:881
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_setkey
```
```
In crypto/skcipher.c (ffffffff8147ac6d)
Location: include/linux/crypto.h:881
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
  - crypto/skcipher.c:skcipher_setkey_blkcipher
  - crypto/skcipher.c:skcipher_setkey_blkcipher
```
```
In crypto/ahash.c (ffffffff8147c53c)
Location: include/linux/crypto.h:881
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_setkey
```
```
In crypto/shash.c (ffffffff8147d0b9)
Location: include/linux/crypto.h:881
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_setkey
```
```
In crypto/ecb.c (ffffffff81486133)
Location: include/linux/crypto.h:881
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_setkey
```
```
In crypto/cbc.c (ffffffff814864a3)
Location: include/linux/crypto.h:881
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_setkey
```
```
In crypto/cts.c (ffffffff81486ad3)
Location: include/linux/crypto.h:881
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_setkey
```
```
In crypto/xts.c (ffffffff8148797a)
Location: include/linux/crypto.h:881
Inline: True
```
```
In crypto/ctr.c (ffffffff81488024)
Location: include/linux/crypto.h:881
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_setkey
  - crypto/ctr.c:crypto_ctr_setkey
```
```
In crypto/gcm.c (ffffffff81488b04)
Location: include/linux/crypto.h:881
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_setkey
  - crypto/gcm.c:crypto_rfc4106_setkey
  - crypto/gcm.c:crypto_gcm_setkey
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
In crypto/aead.c (ffffffff814a6c3b)
Location: include/linux/crypto.h:878
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_setkey
```
```
In crypto/skcipher.c (ffffffff814a8880)
Location: include/linux/crypto.h:878
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_simple
  - crypto/skcipher.c:skcipher_setkey
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
  - crypto/skcipher.c:skcipher_setkey_blkcipher
  - crypto/skcipher.c:skcipher_setkey_blkcipher
```
```
In crypto/ahash.c (ffffffff814aae7c)
Location: include/linux/crypto.h:878
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_setkey
```
```
In crypto/shash.c (ffffffff814ab3b9)
Location: include/linux/crypto.h:878
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_setkey
```
```
In crypto/cts.c (ffffffff814b4940)
Location: include/linux/crypto.h:878
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_setkey
```
```
In crypto/xts.c (ffffffff814b568e)
Location: include/linux/crypto.h:878
Inline: True
```
```
In crypto/ctr.c (ffffffff814b5ab4)
Location: include/linux/crypto.h:878
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_setkey
```
```
In crypto/gcm.c (ffffffff814b64a4)
Location: include/linux/crypto.h:878
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_setkey
  - crypto/gcm.c:crypto_rfc4106_setkey
  - crypto/gcm.c:crypto_gcm_setkey
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
In crypto/aead.c (ffffffff814c18ab)
Location: include/linux/crypto.h:878
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_setkey
```
```
In crypto/skcipher.c (ffffffff814c34e0)
Location: include/linux/crypto.h:878
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_simple
  - crypto/skcipher.c:skcipher_setkey
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
  - crypto/skcipher.c:skcipher_setkey_blkcipher
  - crypto/skcipher.c:skcipher_setkey_blkcipher
```
```
In crypto/ahash.c (ffffffff814c5b3c)
Location: include/linux/crypto.h:878
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_setkey
```
```
In crypto/shash.c (ffffffff814c6079)
Location: include/linux/crypto.h:878
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_setkey
```
```
In crypto/cts.c (ffffffff814cd6b0)
Location: include/linux/crypto.h:878
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_setkey
```
```
In crypto/xts.c (ffffffff814ce88e)
Location: include/linux/crypto.h:878
Inline: True
```
```
In crypto/ctr.c (ffffffff814cecb4)
Location: include/linux/crypto.h:878
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_setkey
```
```
In crypto/gcm.c (ffffffff814cf6c4)
Location: include/linux/crypto.h:878
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_setkey
  - crypto/gcm.c:crypto_rfc4106_setkey
  - crypto/gcm.c:crypto_gcm_setkey
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
In crypto/aead.c (0)
Location: include/linux/crypto.h:697
Inline: True
```
```
In crypto/skcipher.c (ffffffff81522dad)
Location: include/linux/crypto.h:697
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_simple
  - crypto/skcipher.c:crypto_skcipher_setkey
```
```
In crypto/ahash.c (ffffffff815244c3)
Location: include/linux/crypto.h:697
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_setkey
```
```
In crypto/shash.c (ffffffff8152581c)
Location: include/linux/crypto.h:697
Inline: True
Inline callers:
  - crypto/shash.c:shash_async_setkey
```
```
In crypto/cts.c (ffffffff8152cb1d)
Location: include/linux/crypto.h:697
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_setkey
```
```
In crypto/xts.c (ffffffff8152db96)
Location: include/linux/crypto.h:697
Inline: True
```
```
In crypto/ctr.c (ffffffff8152e06b)
Location: include/linux/crypto.h:697
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_setkey
```
```
In crypto/gcm.c (ffffffff8152e8fb)
Location: include/linux/crypto.h:697
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_setkey
  - crypto/gcm.c:crypto_rfc4106_setkey
  - crypto/gcm.c:crypto_gcm_setkey
  - crypto/gcm.c:crypto_gcm_setkey
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
In crypto/aead.c (0)
Location: include/linux/crypto.h:733
Inline: True
```
```
In crypto/skcipher.c (ffffffff8153fcfd)
Location: include/linux/crypto.h:733
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_simple
  - crypto/skcipher.c:crypto_skcipher_setkey
```
```
In crypto/ahash.c (ffffffff81541393)
Location: include/linux/crypto.h:733
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_setkey
```
```
In crypto/shash.c (ffffffff8154274c)
Location: include/linux/crypto.h:733
Inline: True
Inline callers:
  - crypto/shash.c:shash_async_setkey
```
```
In crypto/cts.c (ffffffff81549b8d)
Location: include/linux/crypto.h:733
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_setkey
```
```
In crypto/xts.c (ffffffff8154ab66)
Location: include/linux/crypto.h:733
Inline: True
```
```
In crypto/ctr.c (ffffffff8154b08b)
Location: include/linux/crypto.h:733
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_setkey
```
```
In crypto/gcm.c (ffffffff8154b87b)
Location: include/linux/crypto.h:733
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_setkey
  - crypto/gcm.c:crypto_rfc4106_setkey
  - crypto/gcm.c:crypto_gcm_setkey
  - crypto/gcm.c:crypto_gcm_setkey
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
In crypto/aead.c (0)
Location: include/linux/crypto.h:729
Inline: True
```
```
In crypto/skcipher.c (ffffffff8154826d)
Location: include/linux/crypto.h:729
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_simple
  - crypto/skcipher.c:crypto_skcipher_setkey
```
```
In crypto/ahash.c (ffffffff815499c3)
Location: include/linux/crypto.h:729
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_setkey
```
```
In crypto/shash.c (ffffffff8154adec)
Location: include/linux/crypto.h:729
Inline: True
Inline callers:
  - crypto/shash.c:shash_async_setkey
```
```
In crypto/cts.c (ffffffff815521dd)
Location: include/linux/crypto.h:729
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_setkey
```
```
In crypto/xts.c (ffffffff81553186)
Location: include/linux/crypto.h:729
Inline: True
```
```
In crypto/ctr.c (ffffffff815536ab)
Location: include/linux/crypto.h:729
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_setkey
```
```
In crypto/gcm.c (ffffffff81553e7b)
Location: include/linux/crypto.h:729
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_setkey
  - crypto/gcm.c:crypto_rfc4106_setkey
  - crypto/gcm.c:crypto_gcm_setkey
  - crypto/gcm.c:crypto_gcm_setkey
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
In crypto/aead.c (0)
Location: include/linux/crypto.h:703
Inline: True
```
```
In crypto/skcipher.c (ffffffff815a8a4d)
Location: include/linux/crypto.h:703
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_simple
  - crypto/skcipher.c:crypto_skcipher_setkey
```
```
In crypto/ahash.c (ffffffff815aa1a3)
Location: include/linux/crypto.h:703
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_setkey
```
```
In crypto/shash.c (ffffffff815ab5cc)
Location: include/linux/crypto.h:703
Inline: True
Inline callers:
  - crypto/shash.c:shash_async_setkey
```
```
In crypto/cts.c (ffffffff815b31dd)
Location: include/linux/crypto.h:703
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_setkey
```
```
In crypto/xts.c (ffffffff815b41b6)
Location: include/linux/crypto.h:703
Inline: True
```
```
In crypto/ctr.c (ffffffff815b46db)
Location: include/linux/crypto.h:703
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_setkey
```
```
In crypto/gcm.c (ffffffff815b4eab)
Location: include/linux/crypto.h:703
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_setkey
  - crypto/gcm.c:crypto_rfc4106_setkey
  - crypto/gcm.c:crypto_gcm_setkey
  - crypto/gcm.c:crypto_gcm_setkey
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
In crypto/aead.c (0)
Location: include/linux/crypto.h:712
Inline: True
```
```
In crypto/skcipher.c (ffffffff8164fe3d)
Location: include/linux/crypto.h:712
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_simple
  - crypto/skcipher.c:crypto_skcipher_setkey
```
```
In crypto/ahash.c (ffffffff81651c93)
Location: include/linux/crypto.h:712
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_setkey
```
```
In crypto/shash.c (ffffffff81652e2c)
Location: include/linux/crypto.h:712
Inline: True
Inline callers:
  - crypto/shash.c:shash_async_setkey
```
```
In crypto/cts.c (ffffffff8165c1ad)
Location: include/linux/crypto.h:712
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_setkey
```
```
In crypto/xts.c (ffffffff8165d014)
Location: include/linux/crypto.h:712
Inline: True
```
```
In crypto/ctr.c (ffffffff8165d59b)
Location: include/linux/crypto.h:712
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_setkey
```
```
In crypto/gcm.c (ffffffff8165decb)
Location: include/linux/crypto.h:712
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_setkey
  - crypto/gcm.c:crypto_rfc4106_setkey
  - crypto/gcm.c:crypto_gcm_setkey
  - crypto/gcm.c:crypto_gcm_setkey
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
In crypto/aead.c (0)
Location: include/linux/crypto.h:712
Inline: True
```
```
In crypto/skcipher.c (ffffffff8170931d)
Location: include/linux/crypto.h:712
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_simple
  - crypto/skcipher.c:crypto_skcipher_setkey
```
```
In crypto/ahash.c (ffffffff8170b6f3)
Location: include/linux/crypto.h:712
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_setkey
```
```
In crypto/shash.c (ffffffff8170cabc)
Location: include/linux/crypto.h:712
Inline: True
Inline callers:
  - crypto/shash.c:shash_async_setkey
```
```
In crypto/cts.c (ffffffff81715b4d)
Location: include/linux/crypto.h:712
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_setkey
```
```
In crypto/xts.c (ffffffff81716af4)
Location: include/linux/crypto.h:712
Inline: True
```
```
In crypto/ctr.c (ffffffff817171db)
Location: include/linux/crypto.h:712
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_setkey
```
```
In crypto/gcm.c (ffffffff81717ebb)
Location: include/linux/crypto.h:712
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_setkey
  - crypto/gcm.c:crypto_rfc4106_setkey
  - crypto/gcm.c:crypto_gcm_setkey
  - crypto/gcm.c:crypto_gcm_setkey
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
In crypto/aead.c (0)
Location: include/linux/crypto.h:485
Inline: True
```
```
In crypto/skcipher.c (ffffffff81742b5d)
Location: include/linux/crypto.h:485
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_simple
  - crypto/skcipher.c:crypto_skcipher_setkey
```
```
In crypto/ahash.c (ffffffff81744a53)
Location: include/linux/crypto.h:485
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_setkey
```
```
In crypto/shash.c (ffffffff81746a7c)
Location: include/linux/crypto.h:485
Inline: True
Inline callers:
  - crypto/shash.c:shash_async_setkey
```
```
In crypto/cts.c (ffffffff817513fd)
Location: include/linux/crypto.h:485
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_setkey
```
```
In crypto/xts.c (ffffffff817523a4)
Location: include/linux/crypto.h:485
Inline: True
```
```
In crypto/ctr.c (ffffffff81752aeb)
Location: include/linux/crypto.h:485
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_setkey
```
```
In crypto/gcm.c (ffffffff817537db)
Location: include/linux/crypto.h:485
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_setkey
  - crypto/gcm.c:crypto_rfc4106_setkey
  - crypto/gcm.c:crypto_gcm_setkey
  - crypto/gcm.c:crypto_gcm_setkey
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
In crypto/aead.c (0)
Location: include/linux/crypto.h:485
Inline: True
```
```
In crypto/lskcipher.c (ffffffff817845ac)
Location: include/linux/crypto.h:485
Inline: True
Inline callers:
  - crypto/lskcipher.c:lskcipher_setkey_simple
```
```
In crypto/skcipher.c (ffffffff81784d9d)
Location: include/linux/crypto.h:485
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_simple
  - crypto/skcipher.c:crypto_skcipher_setkey
  - crypto/skcipher.c:crypto_skcipher_setkey
```
```
In crypto/ahash.c (ffffffff8178709f)
Location: include/linux/crypto.h:485
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_setkey
```
```
In crypto/shash.c (ffffffff81788611)
Location: include/linux/crypto.h:485
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_setkey
```
```
In crypto/ecb.c (ffffffff8179259d)
Location: include/linux/crypto.h:485
Inline: True
Inline callers:
  - crypto/ecb.c:lskcipher_setkey_simple2
```
```
In crypto/cts.c (ffffffff8179324d)
Location: include/linux/crypto.h:485
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_setkey
```
```
In crypto/xts.c (ffffffff81794234)
Location: include/linux/crypto.h:485
Inline: True
```
```
In crypto/ctr.c (ffffffff81794a5b)
Location: include/linux/crypto.h:485
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_setkey
```
```
In crypto/gcm.c (ffffffff817956ab)
Location: include/linux/crypto.h:485
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_setkey
  - crypto/gcm.c:crypto_rfc4106_setkey
  - crypto/gcm.c:crypto_gcm_setkey
  - crypto/gcm.c:crypto_gcm_setkey
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
In crypto/aead.c (ffff8000105bbf68)
Location: include/linux/crypto.h:878
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_setkey
```
```
In crypto/skcipher.c (ffff8000105bdd10)
Location: include/linux/crypto.h:878
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_simple
  - crypto/skcipher.c:skcipher_setkey
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
  - crypto/skcipher.c:skcipher_setkey_blkcipher
  - crypto/skcipher.c:skcipher_setkey_blkcipher
```
```
In crypto/ahash.c (ffff8000105c0d28)
Location: include/linux/crypto.h:878
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_setkey
```
```
In crypto/shash.c (ffff8000105c1140)
Location: include/linux/crypto.h:878
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_setkey
```
```
In crypto/cts.c (ffff8000105c9560)
Location: include/linux/crypto.h:878
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_setkey
```
```
In crypto/xts.c (ffff8000105caa84)
Location: include/linux/crypto.h:878
Inline: True
```
```
In crypto/ctr.c (ffff8000105cabec)
Location: include/linux/crypto.h:878
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_setkey
```
```
In crypto/gcm.c (ffff8000105cb764)
Location: include/linux/crypto.h:878
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_setkey
  - crypto/gcm.c:crypto_rfc4106_setkey
  - crypto/gcm.c:crypto_gcm_setkey
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
In crypto/aead.c (c076a030)
Location: include/linux/crypto.h:878
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_setkey
```
```
In crypto/skcipher.c (c076bb4c)
Location: include/linux/crypto.h:878
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_simple
  - crypto/skcipher.c:skcipher_setkey
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
  - crypto/skcipher.c:skcipher_setkey_blkcipher
  - crypto/skcipher.c:skcipher_setkey_blkcipher
```
```
In crypto/ahash.c (c076e418)
Location: include/linux/crypto.h:878
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_setkey
```
```
In crypto/shash.c (c076e9fc)
Location: include/linux/crypto.h:878
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_setkey
```
```
In crypto/cts.c (c0777124)
Location: include/linux/crypto.h:878
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_setkey
```
```
In crypto/xts.c (c077866c)
Location: include/linux/crypto.h:878
Inline: True
```
```
In crypto/ctr.c (c07787b8)
Location: include/linux/crypto.h:878
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_setkey
```
```
In crypto/gcm.c (c07791cc)
Location: include/linux/crypto.h:878
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_setkey
  - crypto/gcm.c:crypto_rfc4106_setkey
  - crypto/gcm.c:crypto_gcm_setkey
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
In crypto/aead.c (c00000000074286c)
Location: include/linux/crypto.h:878
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_setkey
```
```
In crypto/skcipher.c (c000000000745200)
Location: include/linux/crypto.h:878
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_simple
  - crypto/skcipher.c:skcipher_setkey
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
  - crypto/skcipher.c:skcipher_setkey_blkcipher
  - crypto/skcipher.c:skcipher_setkey_blkcipher
```
```
In crypto/ahash.c (c000000000748bcc)
Location: include/linux/crypto.h:878
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_setkey
```
```
In crypto/shash.c (c0000000007494c0)
Location: include/linux/crypto.h:878
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_setkey
```
```
In crypto/cts.c (c000000000753b90)
Location: include/linux/crypto.h:878
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_setkey
```
```
In crypto/xts.c (c00000000075540c)
Location: include/linux/crypto.h:878
Inline: True
```
```
In crypto/ctr.c (c0000000007559cc)
Location: include/linux/crypto.h:878
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_setkey
```
```
In crypto/gcm.c (c000000000756808)
Location: include/linux/crypto.h:878
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_setkey
  - crypto/gcm.c:crypto_rfc4106_setkey
  - crypto/gcm.c:crypto_gcm_setkey
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
In crypto/aead.c (ffffffe00040173c)
Location: include/linux/crypto.h:878
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_setkey
```
```
In crypto/skcipher.c (ffffffe000403222)
Location: include/linux/crypto.h:878
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_simple
  - crypto/skcipher.c:skcipher_setkey
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
  - crypto/skcipher.c:skcipher_setkey_blkcipher
  - crypto/skcipher.c:skcipher_setkey_blkcipher
```
```
In crypto/ahash.c (ffffffe000405b8c)
Location: include/linux/crypto.h:878
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_setkey
```
```
In crypto/shash.c (ffffffe000405f2a)
Location: include/linux/crypto.h:878
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_setkey
```
```
In crypto/cts.c (ffffffe00040dd74)
Location: include/linux/crypto.h:878
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_setkey
```
```
In crypto/xts.c (ffffffe00040ec8c)
Location: include/linux/crypto.h:878
Inline: True
```
```
In crypto/ctr.c (ffffffe00040f0b4)
Location: include/linux/crypto.h:878
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_setkey
```
```
In crypto/gcm.c (ffffffe00040fa96)
Location: include/linux/crypto.h:878
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_setkey
  - crypto/gcm.c:crypto_rfc4106_setkey
  - crypto/gcm.c:crypto_gcm_setkey
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
In crypto/aead.c (ffffffff814b9e8b)
Location: include/linux/crypto.h:878
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_setkey
```
```
In crypto/skcipher.c (ffffffff814bbac0)
Location: include/linux/crypto.h:878
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_simple
  - crypto/skcipher.c:skcipher_setkey
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
  - crypto/skcipher.c:skcipher_setkey_blkcipher
  - crypto/skcipher.c:skcipher_setkey_blkcipher
```
```
In crypto/ahash.c (ffffffff814be11c)
Location: include/linux/crypto.h:878
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_setkey
```
```
In crypto/shash.c (ffffffff814be659)
Location: include/linux/crypto.h:878
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_setkey
```
```
In crypto/cts.c (ffffffff814c5c90)
Location: include/linux/crypto.h:878
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_setkey
```
```
In crypto/xts.c (ffffffff814c6e6e)
Location: include/linux/crypto.h:878
Inline: True
```
```
In crypto/ctr.c (ffffffff814c7294)
Location: include/linux/crypto.h:878
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_setkey
```
```
In crypto/gcm.c (ffffffff814c7ca4)
Location: include/linux/crypto.h:878
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_setkey
  - crypto/gcm.c:crypto_rfc4106_setkey
  - crypto/gcm.c:crypto_gcm_setkey
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
In crypto/aead.c (ffffffff814aa8ab)
Location: include/linux/crypto.h:878
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_setkey
```
```
In crypto/skcipher.c (ffffffff814ac4e0)
Location: include/linux/crypto.h:878
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_simple
  - crypto/skcipher.c:skcipher_setkey
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
  - crypto/skcipher.c:skcipher_setkey_blkcipher
  - crypto/skcipher.c:skcipher_setkey_blkcipher
```
```
In crypto/ahash.c (ffffffff814aeb3c)
Location: include/linux/crypto.h:878
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_setkey
```
```
In crypto/shash.c (ffffffff814af079)
Location: include/linux/crypto.h:878
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_setkey
```
```
In crypto/cts.c (ffffffff814b66b0)
Location: include/linux/crypto.h:878
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_setkey
```
```
In crypto/xts.c (ffffffff814b788e)
Location: include/linux/crypto.h:878
Inline: True
```
```
In crypto/ctr.c (ffffffff814b7cb4)
Location: include/linux/crypto.h:878
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_setkey
```
```
In crypto/gcm.c (ffffffff814b86c4)
Location: include/linux/crypto.h:878
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_setkey
  - crypto/gcm.c:crypto_rfc4106_setkey
  - crypto/gcm.c:crypto_gcm_setkey
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
In crypto/aead.c (ffffffff814b5f1b)
Location: include/linux/crypto.h:878
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_setkey
```
```
In crypto/skcipher.c (ffffffff814b7b50)
Location: include/linux/crypto.h:878
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_simple
  - crypto/skcipher.c:skcipher_setkey
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
  - crypto/skcipher.c:skcipher_setkey_blkcipher
  - crypto/skcipher.c:skcipher_setkey_blkcipher
```
```
In crypto/ahash.c (ffffffff814ba1ac)
Location: include/linux/crypto.h:878
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_setkey
```
```
In crypto/shash.c (ffffffff814ba6e9)
Location: include/linux/crypto.h:878
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_setkey
```
```
In crypto/cts.c (ffffffff814c1d20)
Location: include/linux/crypto.h:878
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_setkey
```
```
In crypto/xts.c (ffffffff814c2efe)
Location: include/linux/crypto.h:878
Inline: True
```
```
In crypto/ctr.c (ffffffff814c3324)
Location: include/linux/crypto.h:878
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_setkey
```
```
In crypto/gcm.c (ffffffff814c3d34)
Location: include/linux/crypto.h:878
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_setkey
  - crypto/gcm.c:crypto_rfc4106_setkey
  - crypto/gcm.c:crypto_gcm_setkey
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
In crypto/aead.c (ffffffff814ce9bb)
Location: include/linux/crypto.h:878
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_setkey
```
```
In crypto/skcipher.c (ffffffff814d0630)
Location: include/linux/crypto.h:878
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_simple
  - crypto/skcipher.c:skcipher_setkey
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
  - crypto/skcipher.c:skcipher_setkey_blkcipher
  - crypto/skcipher.c:skcipher_setkey_blkcipher
```
```
In crypto/ahash.c (ffffffff814d2c5c)
Location: include/linux/crypto.h:878
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_setkey
```
```
In crypto/shash.c (ffffffff814d3199)
Location: include/linux/crypto.h:878
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_setkey
```
```
In crypto/cts.c (ffffffff814da7f0)
Location: include/linux/crypto.h:878
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_setkey
```
```
In crypto/xts.c (ffffffff814db9ce)
Location: include/linux/crypto.h:878
Inline: True
```
```
In crypto/ctr.c (ffffffff814dbdf4)
Location: include/linux/crypto.h:878
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_setkey
```
```
In crypto/gcm.c (ffffffff814dc804)
Location: include/linux/crypto.h:878
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_setkey
  - crypto/gcm.c:crypto_rfc4106_setkey
  - crypto/gcm.c:crypto_gcm_setkey
  - crypto/gcm.c:crypto_gcm_setkey
```
</details>
</li>
</ul>

## Differences
