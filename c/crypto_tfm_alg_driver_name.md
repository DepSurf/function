# Function: <code>crypto_tfm_alg_driver_name</code>

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
In fs/ecryptfs/keystore.c (ffffffff8133caf1)
Location: include/linux/crypto.h:611
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In crypto/drbg.c (ffffffff813ee323)
Location: include/linux/crypto.h:611
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_seed
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
In fs/ecryptfs/keystore.c (ffffffff81352881)
Location: include/linux/crypto.h:614
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In crypto/drbg.c (ffffffff81407b63)
Location: include/linux/crypto.h:614
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_seed
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
In fs/ecryptfs/keystore.c (ffffffff8136738d)
Location: include/linux/crypto.h:614
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In crypto/drbg.c (ffffffff81415291)
Location: include/linux/crypto.h:614
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_seed
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
In fs/ecryptfs/keystore.c (ffffffff8138c016)
Location: include/linux/crypto.h:662
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In crypto/drbg.c (ffffffff8143fa61)
Location: include/linux/crypto.h:662
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_seed
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
In fs/ecryptfs/keystore.c (ffffffff813baf05)
Location: include/linux/crypto.h:675
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In crypto/drbg.c (ffffffff8147289d)
Location: include/linux/crypto.h:675
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_seed
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
In fs/ecryptfs/keystore.c (ffffffff813d4508)
Location: include/linux/crypto.h:846
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In crypto/drbg.c (ffffffff8148fced)
Location: include/linux/crypto.h:846
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_seed
```
```
In lib/crc-t10dif.c (ffffffff814e8999)
Location: include/linux/crypto.h:846
Inline: True
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
In fs/ecryptfs/keystore.c (ffffffff813fef07)
Location: include/linux/crypto.h:843
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In crypto/drbg.c (ffffffff814be59d)
Location: include/linux/crypto.h:843
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_seed
```
```
In lib/crc-t10dif.c (ffffffff81515659)
Location: include/linux/crypto.h:843
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
In fs/verity/hash_algs.c (ffffffff813505ec)
Location: include/linux/crypto.h:843
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
```
```
In fs/ecryptfs/keystore.c (ffffffff81418df7)
Location: include/linux/crypto.h:843
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In crypto/drbg.c (ffffffff814d73ed)
Location: include/linux/crypto.h:843
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_seed
```
```
In lib/crc-t10dif.c (ffffffff81536099)
Location: include/linux/crypto.h:843
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
In fs/crypto/keysetup.c (ffffffff81393f1d)
Location: include/linux/crypto.h:662
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_allocate_skcipher
```
```
In fs/verity/hash_algs.c (ffffffff81396fd3)
Location: include/linux/crypto.h:662
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
```
```
In fs/ecryptfs/keystore.c (ffffffff81467089)
Location: include/linux/crypto.h:662
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In crypto/drbg.c (ffffffff81534a1a)
Location: include/linux/crypto.h:662
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_seed
```
```
In lib/crc-t10dif.c (ffffffff8159a711)
Location: include/linux/crypto.h:662
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
In fs/crypto/keysetup.c (ffffffff81beaf08)
Location: include/linux/crypto.h:698
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_allocate_skcipher
```
```
In fs/verity/hash_algs.c (ffffffff81beb3fc)
Location: include/linux/crypto.h:698
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
```
```
In fs/ecryptfs/keystore.c (ffffffff81482289)
Location: include/linux/crypto.h:698
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In crypto/drbg.c (ffffffff8155196a)
Location: include/linux/crypto.h:698
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_seed
```
```
In lib/crc-t10dif.c (ffffffff815b6162)
Location: include/linux/crypto.h:698
Inline: True
Inline callers:
  - lib/crc-t10dif.c:crc_t10dif_transform_show
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
In fs/crypto/keysetup.c (ffffffff81bdcf2e)
Location: include/linux/crypto.h:694
Inline: True
```
```
In fs/verity/hash_algs.c (ffffffff81bdd450)
Location: include/linux/crypto.h:694
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
```
```
In fs/ecryptfs/keystore.c (ffffffff81487cf6)
Location: include/linux/crypto.h:694
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In crypto/drbg.c (ffffffff81559f91)
Location: include/linux/crypto.h:694
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_seed
```
```
In lib/crc-t10dif.c (ffffffff815c0f92)
Location: include/linux/crypto.h:694
Inline: True
Inline callers:
  - lib/crc-t10dif.c:crc_t10dif_transform_show
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
In fs/crypto/keysetup.c (ffffffff81cc655e)
Location: include/linux/crypto.h:668
Inline: True
```
```
In fs/verity/hash_algs.c (ffffffff81cc6d57)
Location: include/linux/crypto.h:668
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
```
```
In fs/ecryptfs/keystore.c (ffffffff814df4b1)
Location: include/linux/crypto.h:668
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In crypto/drbg.c (ffffffff815bb211)
Location: include/linux/crypto.h:668
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_seed
```
```
In lib/crc-t10dif.c (ffffffff81628dff)
Location: include/linux/crypto.h:668
Inline: True
Inline callers:
  - lib/crc-t10dif.c:crc_t10dif_transform_show
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
In fs/crypto/keysetup.c (ffffffff81e789ce)
Location: include/linux/crypto.h:677
Inline: True
```
```
In fs/verity/hash_algs.c (ffffffff81e79293)
Location: include/linux/crypto.h:677
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
```
```
In fs/ecryptfs/keystore.c (ffffffff8156d507)
Location: include/linux/crypto.h:677
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In crypto/drbg.c (ffffffff81664c2f)
Location: include/linux/crypto.h:677
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_seed
```
```
In lib/crc-t10dif.c (ffffffff816f9c26)
Location: include/linux/crypto.h:677
Inline: True
Inline callers:
  - lib/crc-t10dif.c:crc_t10dif_transform_show
```
```
In lib/crc64-rocksoft.c (ffffffff816fa1f6)
Location: include/linux/crypto.h:677
Inline: True
Inline callers:
  - lib/crc64-rocksoft.c:crc64_rocksoft_transform_show
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
In fs/crypto/keysetup.c (ffffffff814ffc90)
Location: include/linux/crypto.h:677
Inline: True
```
```
In fs/verity/hash_algs.c (ffffffff81504b1d)
Location: include/linux/crypto.h:677
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
```
```
In fs/ecryptfs/keystore.c (ffffffff81611d60)
Location: include/linux/crypto.h:677
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In crypto/drbg.c (ffffffff8171efaf)
Location: include/linux/crypto.h:677
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_seed
```
```
In lib/crc-t10dif.c (ffffffff817ec576)
Location: include/linux/crypto.h:677
Inline: True
```
```
In lib/crc64-rocksoft.c (ffffffff817ecc26)
Location: include/linux/crypto.h:677
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
In fs/crypto/keysetup.c (ffffffff81537260)
Location: include/linux/crypto.h:460
Inline: True
```
```
In fs/verity/hash_algs.c (ffffffff8153c1b4)
Location: include/linux/crypto.h:460
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
```
```
In fs/ecryptfs/keystore.c (ffffffff81649ca9)
Location: include/linux/crypto.h:460
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In crypto/drbg.c (ffffffff8175a8bf)
Location: include/linux/crypto.h:460
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_seed
```
```
In lib/crc-t10dif.c (ffffffff8182c6c6)
Location: include/linux/crypto.h:460
Inline: True
```
```
In lib/crc64-rocksoft.c (ffffffff8182cdd6)
Location: include/linux/crypto.h:460
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
In fs/crypto/keysetup.c (ffffffff8156c330)
Location: include/linux/crypto.h:460
Inline: True
```
```
In fs/verity/hash_algs.c (ffffffff81571494)
Location: include/linux/crypto.h:460
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
```
```
In fs/ecryptfs/keystore.c (ffffffff81683179)
Location: include/linux/crypto.h:460
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In crypto/drbg.c (ffffffff8179c7bf)
Location: include/linux/crypto.h:460
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_seed
```
```
In lib/crc-t10dif.c (ffffffff8187e256)
Location: include/linux/crypto.h:460
Inline: True
```
```
In lib/crc64-rocksoft.c (ffffffff8187e966)
Location: include/linux/crypto.h:460
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
In fs/verity/hash_algs.c (ffff800010411c28)
Location: include/linux/crypto.h:843
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
```
```
In fs/ecryptfs/keystore.c (ffff8000104fa584)
Location: include/linux/crypto.h:843
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In crypto/drbg.c (ffff8000105d1950)
Location: include/linux/crypto.h:843
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_seed
```
```
In lib/crc-t10dif.c (ffff8000106428c8)
Location: include/linux/crypto.h:843
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
In fs/verity/hash_algs.c (c05de27c)
Location: include/linux/crypto.h:843
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
```
```
In fs/ecryptfs/keystore.c (c06b7d04)
Location: include/linux/crypto.h:843
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In crypto/drbg.c (c078085c)
Location: include/linux/crypto.h:843
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_seed
```
```
In lib/crc-t10dif.c (c07e847c)
Location: include/linux/crypto.h:843
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
In fs/verity/hash_algs.c (c00000000051f890)
Location: include/linux/crypto.h:843
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
```
```
In fs/ecryptfs/keystore.c (c00000000063ccc8)
Location: include/linux/crypto.h:843
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In crypto/drbg.c (c0000000007601c0)
Location: include/linux/crypto.h:843
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_seed
```
```
In lib/crc-t10dif.c (c0000000007ed8fc)
Location: include/linux/crypto.h:843
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
In fs/verity/hash_algs.c (ffffffe0002b9daa)
Location: include/linux/crypto.h:843
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
```
```
In fs/ecryptfs/keystore.c (ffffffe000368dca)
Location: include/linux/crypto.h:843
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In crypto/drbg.c (ffffffe000416646)
Location: include/linux/crypto.h:843
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_seed
```
```
In lib/crc-t10dif.c (ffffffe00046eb7c)
Location: include/linux/crypto.h:843
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
In fs/verity/hash_algs.c (ffffffff81348bcc)
Location: include/linux/crypto.h:843
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
```
```
In fs/ecryptfs/keystore.c (ffffffff814113d7)
Location: include/linux/crypto.h:843
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In crypto/drbg.c (ffffffff814cf9cd)
Location: include/linux/crypto.h:843
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_seed
```
```
In lib/crc-t10dif.c (ffffffff8152e679)
Location: include/linux/crypto.h:843
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
In fs/verity/hash_algs.c (ffffffff813398ac)
Location: include/linux/crypto.h:843
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
```
```
In fs/ecryptfs/keystore.c (ffffffff81401e57)
Location: include/linux/crypto.h:843
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In crypto/drbg.c (ffffffff814c03ed)
Location: include/linux/crypto.h:843
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_seed
```
```
In lib/crc-t10dif.c (ffffffff8151e959)
Location: include/linux/crypto.h:843
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
In fs/verity/hash_algs.c (ffffffff8134669c)
Location: include/linux/crypto.h:843
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
```
```
In fs/ecryptfs/keystore.c (ffffffff8140e757)
Location: include/linux/crypto.h:843
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In crypto/drbg.c (ffffffff814cba5d)
Location: include/linux/crypto.h:843
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_seed
```
```
In lib/crc-t10dif.c (ffffffff8152a319)
Location: include/linux/crypto.h:843
Inline: True
```
```
In lib/libcrc32c.c (ffffffff8152a750)
Location: include/linux/crypto.h:843
Inline: True
Inline callers:
  - lib/libcrc32c.c:crc32c_impl
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
In fs/verity/hash_algs.c (ffffffff8135997c)
Location: include/linux/crypto.h:843
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
```
```
In fs/ecryptfs/keystore.c (ffffffff814243c7)
Location: include/linux/crypto.h:843
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In crypto/drbg.c (ffffffff814e452d)
Location: include/linux/crypto.h:843
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_seed
```
```
In lib/crc-t10dif.c (ffffffff81544119)
Location: include/linux/crypto.h:843
Inline: True
```
</details>
</li>
</ul>

## Differences
