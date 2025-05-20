# Function: <code>crypto_blkcipher_set_flags</code>

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
In fs/ecryptfs/crypto.c (ffffffff81306de6)
Location: include/linux/crypto.h:1228
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
```
```
In crypto/skcipher.c (ffffffff813a1a39)
Location: include/linux/crypto.h:1228
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
In crypto/skcipher.c (ffffffff813ddef4)
Location: include/linux/crypto.h:1185
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
In crypto/skcipher.c (ffffffff813f57c4)
Location: include/linux/crypto.h:1188
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
In crypto/skcipher.c (ffffffff81401a64)
Location: include/linux/crypto.h:1188
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
In crypto/skcipher.c (ffffffff8142a084)
Location: include/linux/crypto.h:1236
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
In crypto/skcipher.c (ffffffff8145cdb9)
Location: include/linux/crypto.h:1249
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
In crypto/skcipher.c (ffffffff8147a64b)
Location: include/linux/crypto.h:1434
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
In crypto/skcipher.c (ffffffff814a88db)
Location: include/linux/crypto.h:1431
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
In crypto/skcipher.c (ffffffff814c353b)
Location: include/linux/crypto.h:1431
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
In crypto/skcipher.c (ffff8000105bdda4)
Location: include/linux/crypto.h:1431
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
In crypto/skcipher.c (c076bbcc)
Location: include/linux/crypto.h:1431
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
In crypto/skcipher.c (c000000000745298)
Location: include/linux/crypto.h:1431
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
In crypto/skcipher.c (ffffffe0004032a2)
Location: include/linux/crypto.h:1431
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
In crypto/skcipher.c (ffffffff814bbb1b)
Location: include/linux/crypto.h:1431
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
In crypto/skcipher.c (ffffffff814ac53b)
Location: include/linux/crypto.h:1431
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
In crypto/skcipher.c (ffffffff814b7bab)
Location: include/linux/crypto.h:1431
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
In crypto/skcipher.c (ffffffff814d068b)
Location: include/linux/crypto.h:1431
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_blkcipher
```
</details>
</li>
</ul>

## Differences
