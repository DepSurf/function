# Function: <code>crypto_blkcipher_setkey</code>

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
In fs/ecryptfs/crypto.c (ffffffff81306e01)
Location: include/linux/crypto.h:1256
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
```
```
In fs/ecryptfs/keystore.c (ffffffff813078aa)
Location: include/linux/crypto.h:1256
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff81338eb3)
Location: include/linux/crypto.h:1256
Inline: True
```
```
In crypto/skcipher.c (ffffffff813a1a3c)
Location: include/linux/crypto.h:1256
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_blkcipher
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff813ddeec)
Location: include/linux/crypto.h:1213
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_blkcipher
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff813f57bc)
Location: include/linux/crypto.h:1216
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_blkcipher
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff81401a5c)
Location: include/linux/crypto.h:1216
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_blkcipher
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff8142a07c)
Location: include/linux/crypto.h:1264
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_blkcipher
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff8145cdc6)
Location: include/linux/crypto.h:1277
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_blkcipher
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff8147a65a)
Location: include/linux/crypto.h:1462
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_blkcipher
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff814a88ea)
Location: include/linux/crypto.h:1459
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_blkcipher
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff814c354a)
Location: include/linux/crypto.h:1459
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_blkcipher
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffff8000105bddb0)
Location: include/linux/crypto.h:1459
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_blkcipher
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (c076bbdc)
Location: include/linux/crypto.h:1459
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_blkcipher
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (c0000000007452b0)
Location: include/linux/crypto.h:1459
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_blkcipher
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffe0004032a4)
Location: include/linux/crypto.h:1459
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_blkcipher
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff814bbb2a)
Location: include/linux/crypto.h:1459
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_blkcipher
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff814ac54a)
Location: include/linux/crypto.h:1459
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_blkcipher
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff814b7bba)
Location: include/linux/crypto.h:1459
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_blkcipher
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff814d069a)
Location: include/linux/crypto.h:1459
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_blkcipher
```
</details>
</li>
</ul>

## Differences
