# Function: <code>crypto_free_ablkcipher</code>

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
In fs/ext4/crypto_key.c (ffffffff812e58fc)
Location: include/linux/crypto.h:767
Inline: True
Inline callers:
  - fs/ext4/crypto_key.c:ext4_derive_key_aes
  - fs/ext4/crypto_key.c:ext4_free_crypt_info
```
```
In fs/ecryptfs/crypto.c (ffffffff8130597a)
Location: include/linux/crypto.h:767
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_crypt_stat
```
```
In crypto/blkcipher.c (ffffffff813a0d26)
Location: include/linux/crypto.h:767
Inline: True
Inline callers:
  - crypto/blkcipher.c:skcipher_geniv_exit
```
```
In crypto/skcipher.c (ffffffff813a1c86)
Location: include/linux/crypto.h:767
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_exit_skcipher_ops_ablkcipher
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
In crypto/skcipher.c (ffffffff813de336)
Location: include/linux/crypto.h:725
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_exit_skcipher_ops_ablkcipher
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
In crypto/skcipher.c (ffffffff813f5ef6)
Location: include/linux/crypto.h:728
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_exit_skcipher_ops_ablkcipher
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
In crypto/skcipher.c (ffffffff81402286)
Location: include/linux/crypto.h:728
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_exit_skcipher_ops_ablkcipher
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
In crypto/skcipher.c (ffffffff8142a8f6)
Location: include/linux/crypto.h:776
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_exit_skcipher_ops_ablkcipher
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
In crypto/skcipher.c (ffffffff8145d645)
Location: include/linux/crypto.h:789
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_exit_skcipher_ops_ablkcipher
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
In crypto/skcipher.c (ffffffff8147aed5)
Location: include/linux/crypto.h:960
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_exit_skcipher_ops_ablkcipher
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
In crypto/skcipher.c (ffffffff814a8f15)
Location: include/linux/crypto.h:957
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_exit_skcipher_ops_ablkcipher
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
In crypto/skcipher.c (ffffffff814c3b75)
Location: include/linux/crypto.h:957
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_exit_skcipher_ops_ablkcipher
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
In crypto/skcipher.c (ffff8000105be508)
Location: include/linux/crypto.h:957
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_exit_skcipher_ops_ablkcipher
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
In crypto/skcipher.c (c076c27c)
Location: include/linux/crypto.h:957
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_exit_skcipher_ops_ablkcipher
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
In crypto/skcipher.c (c000000000745cbc)
Location: include/linux/crypto.h:957
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_exit_skcipher_ops_ablkcipher
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
In crypto/skcipher.c (ffffffe00040391e)
Location: include/linux/crypto.h:957
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_exit_skcipher_ops_ablkcipher
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
In crypto/skcipher.c (ffffffff814bc155)
Location: include/linux/crypto.h:957
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_exit_skcipher_ops_ablkcipher
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
In crypto/skcipher.c (ffffffff814acb75)
Location: include/linux/crypto.h:957
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_exit_skcipher_ops_ablkcipher
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
In crypto/skcipher.c (ffffffff814b81e5)
Location: include/linux/crypto.h:957
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_exit_skcipher_ops_ablkcipher
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
In crypto/skcipher.c (ffffffff814d0cc5)
Location: include/linux/crypto.h:957
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_exit_skcipher_ops_ablkcipher
```
</details>
</li>
</ul>

## Differences
