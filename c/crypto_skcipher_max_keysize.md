# Function: <code>crypto_skcipher_max_keysize</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff8146383f)
Location: include/crypto/skcipher.h:377
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_process_key_cipher
```
```
In fs/ecryptfs/keystore.c (ffffffff814695e4)
Location: include/crypto/skcipher.h:377
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
```
```
In crypto/skcipher.c (ffffffff815225b9)
Location: include/crypto/skcipher.h:377
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/skcipher.c:crypto_skcipher_setkey
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
In fs/ecryptfs/crypto.c (ffffffff8147efff)
Location: include/crypto/skcipher.h:377
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_process_key_cipher
```
```
In fs/ecryptfs/keystore.c (ffffffff81beeb13)
Location: include/crypto/skcipher.h:377
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
```
```
In crypto/skcipher.c (ffffffff8153f499)
Location: include/crypto/skcipher.h:377
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/skcipher.c:crypto_skcipher_setkey
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
In fs/ecryptfs/crypto.c (ffffffff81486a7b)
Location: include/crypto/skcipher.h:379
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
```
```
In fs/ecryptfs/keystore.c (ffffffff81be0bce)
Location: include/crypto/skcipher.h:379
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
```
```
In crypto/skcipher.c (ffffffff81547af9)
Location: include/crypto/skcipher.h:379
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/skcipher.c:crypto_skcipher_setkey
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
In fs/ecryptfs/crypto.c (ffffffff814de20b)
Location: include/crypto/skcipher.h:379
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
```
```
In fs/ecryptfs/keystore.c (ffffffff81cd13d7)
Location: include/crypto/skcipher.h:379
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
```
```
In crypto/skcipher.c (ffffffff815a82d9)
Location: include/crypto/skcipher.h:379
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/skcipher.c:crypto_skcipher_setkey
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
In fs/ecryptfs/crypto.c (ffffffff8156c245)
Location: include/crypto/skcipher.h:383
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
```
```
In fs/ecryptfs/keystore.c (ffffffff81e84552)
Location: include/crypto/skcipher.h:383
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
```
```
In crypto/skcipher.c (ffffffff8164ffe9)
Location: include/crypto/skcipher.h:383
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/skcipher.c:crypto_skcipher_setkey
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
In fs/ecryptfs/crypto.c (ffffffff81610457)
Location: include/crypto/skcipher.h:383
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
```
```
In fs/ecryptfs/keystore.c (ffffffff81611b19)
Location: include/crypto/skcipher.h:383
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
```
```
In crypto/skcipher.c (ffffffff81709739)
Location: include/crypto/skcipher.h:383
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/skcipher.c:crypto_skcipher_setkey
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
In fs/ecryptfs/crypto.c (ffffffff816482ea)
Location: include/crypto/skcipher.h:405
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
```
```
In fs/ecryptfs/keystore.c (ffffffff81649a8a)
Location: include/crypto/skcipher.h:405
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
```
```
In crypto/skcipher.c (ffffffff81743059)
Location: include/crypto/skcipher.h:405
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/skcipher.c:crypto_skcipher_setkey
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
In fs/ecryptfs/crypto.c (ffffffff8168179a)
Location: include/crypto/skcipher.h:666
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
```
```
In fs/ecryptfs/keystore.c (ffffffff81682f5a)
Location: include/crypto/skcipher.h:666
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
```
```
In crypto/skcipher.c (ffffffff817853ca)
Location: include/crypto/skcipher.h:666
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/skcipher.c:crypto_skcipher_setkey
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
