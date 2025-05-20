# Function: <code>crypto_blkcipher_tfm</code>

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
In fs/ecryptfs/crypto.c (0)
Location: include/linux/crypto.h:1130
Inline: True
```
```
In fs/ecryptfs/keystore.c (0)
Location: include/linux/crypto.h:1130
Inline: True
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff81338f28)
Location: include/linux/crypto.h:1130
Inline: True
```
```
In crypto/blkcipher.c (0)
Location: include/linux/crypto.h:1130
Inline: True
```
```
In crypto/skcipher.c (ffffffff813a1c66)
Location: include/linux/crypto.h:1130
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_exit_skcipher_ops_blkcipher
```
```
In crypto/crypto_null.c (ffffffff813a521e)
Location: include/linux/crypto.h:1130
Inline: True
Inline callers:
  - crypto/crypto_null.c:crypto_put_default_null_skcipher
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
In crypto/blkcipher.c (0)
Location: include/linux/crypto.h:1087
Inline: True
```
```
In crypto/skcipher.c (ffffffff813de316)
Location: include/linux/crypto.h:1087
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_exit_skcipher_ops_blkcipher
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
In crypto/blkcipher.c (0)
Location: include/linux/crypto.h:1090
Inline: True
```
```
In crypto/skcipher.c (ffffffff813f5ed6)
Location: include/linux/crypto.h:1090
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_exit_skcipher_ops_blkcipher
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
In crypto/blkcipher.c (0)
Location: include/linux/crypto.h:1090
Inline: True
```
```
In crypto/skcipher.c (ffffffff81402266)
Location: include/linux/crypto.h:1090
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_exit_skcipher_ops_blkcipher
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
In crypto/blkcipher.c (0)
Location: include/linux/crypto.h:1138
Inline: True
```
```
In crypto/skcipher.c (ffffffff8142a8d6)
Location: include/linux/crypto.h:1138
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_exit_skcipher_ops_blkcipher
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
In crypto/blkcipher.c (0)
Location: include/linux/crypto.h:1151
Inline: True
```
```
In crypto/skcipher.c (ffffffff8145d625)
Location: include/linux/crypto.h:1151
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_exit_skcipher_ops_blkcipher
  - crypto/skcipher.c:skcipher_setkey_blkcipher
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
In crypto/blkcipher.c (0)
Location: include/linux/crypto.h:1336
Inline: True
```
```
In crypto/skcipher.c (ffffffff8147aeb5)
Location: include/linux/crypto.h:1336
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_exit_skcipher_ops_blkcipher
  - crypto/skcipher.c:skcipher_setkey_blkcipher
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
In crypto/blkcipher.c (0)
Location: include/linux/crypto.h:1333
Inline: True
```
```
In crypto/skcipher.c (ffffffff814a8ef5)
Location: include/linux/crypto.h:1333
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_exit_skcipher_ops_blkcipher
  - crypto/skcipher.c:skcipher_setkey_blkcipher
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
In crypto/blkcipher.c (0)
Location: include/linux/crypto.h:1333
Inline: True
```
```
In crypto/skcipher.c (ffffffff814c3b55)
Location: include/linux/crypto.h:1333
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_exit_skcipher_ops_blkcipher
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
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/blkcipher.c (0)
Location: include/linux/crypto.h:1333
Inline: True
```
```
In crypto/skcipher.c (ffff8000105be4d8)
Location: include/linux/crypto.h:1333
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_exit_skcipher_ops_blkcipher
  - crypto/skcipher.c:skcipher_setkey_blkcipher
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
In crypto/blkcipher.c (0)
Location: include/linux/crypto.h:1333
Inline: True
```
```
In crypto/skcipher.c (c076c258)
Location: include/linux/crypto.h:1333
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_exit_skcipher_ops_blkcipher
  - crypto/skcipher.c:skcipher_setkey_blkcipher
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
In crypto/blkcipher.c (0)
Location: include/linux/crypto.h:1333
Inline: True
```
```
In crypto/skcipher.c (c000000000745c7c)
Location: include/linux/crypto.h:1333
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_exit_skcipher_ops_blkcipher
  - crypto/skcipher.c:skcipher_setkey_blkcipher
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
In crypto/blkcipher.c (0)
Location: include/linux/crypto.h:1333
Inline: True
```
```
In crypto/skcipher.c (ffffffe0004038f2)
Location: include/linux/crypto.h:1333
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_exit_skcipher_ops_blkcipher
  - crypto/skcipher.c:skcipher_setkey_blkcipher
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
In crypto/blkcipher.c (0)
Location: include/linux/crypto.h:1333
Inline: True
```
```
In crypto/skcipher.c (ffffffff814bc135)
Location: include/linux/crypto.h:1333
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_exit_skcipher_ops_blkcipher
  - crypto/skcipher.c:skcipher_setkey_blkcipher
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
In crypto/blkcipher.c (0)
Location: include/linux/crypto.h:1333
Inline: True
```
```
In crypto/skcipher.c (ffffffff814acb55)
Location: include/linux/crypto.h:1333
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_exit_skcipher_ops_blkcipher
  - crypto/skcipher.c:skcipher_setkey_blkcipher
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
In crypto/blkcipher.c (0)
Location: include/linux/crypto.h:1333
Inline: True
```
```
In crypto/skcipher.c (ffffffff814b81c5)
Location: include/linux/crypto.h:1333
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_exit_skcipher_ops_blkcipher
  - crypto/skcipher.c:skcipher_setkey_blkcipher
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
In crypto/blkcipher.c (0)
Location: include/linux/crypto.h:1333
Inline: True
```
```
In crypto/skcipher.c (ffffffff814d0ca5)
Location: include/linux/crypto.h:1333
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_exit_skcipher_ops_blkcipher
  - crypto/skcipher.c:skcipher_setkey_blkcipher
```
</details>
</li>
</ul>

## Differences
