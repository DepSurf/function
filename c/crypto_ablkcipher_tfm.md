# Function: <code>crypto_ablkcipher_tfm</code>

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
In fs/ext4/crypto.c (0)
Location: include/linux/crypto.h:757
Inline: True
```
```
In fs/ext4/crypto_key.c (ffffffff812e5960)
Location: include/linux/crypto.h:757
Inline: True
Inline callers:
  - fs/ext4/crypto_key.c:ext4_free_crypt_info
```
```
In fs/ext4/crypto_fname.c (0)
Location: include/linux/crypto.h:757
Inline: True
```
```
In fs/ecryptfs/crypto.c (0)
Location: include/linux/crypto.h:757
Inline: True
```
```
In crypto/ablkcipher.c (0)
Location: include/linux/crypto.h:757
Inline: True
```
```
In crypto/blkcipher.c (ffffffff813a0d26)
Location: include/linux/crypto.h:757
Inline: True
Inline callers:
  - crypto/blkcipher.c:skcipher_geniv_exit
```
```
In crypto/skcipher.c (ffffffff813a1c86)
Location: include/linux/crypto.h:757
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_exit_skcipher_ops_ablkcipher
```
```
In crypto/chainiv.c (0)
Location: include/linux/crypto.h:757
Inline: True
```
```
In crypto/eseqiv.c (0)
Location: include/linux/crypto.h:757
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
In crypto/ablkcipher.c (0)
Location: include/linux/crypto.h:715
Inline: True
```
```
In crypto/blkcipher.c (0)
Location: include/linux/crypto.h:715
Inline: True
```
```
In crypto/skcipher.c (ffffffff813de336)
Location: include/linux/crypto.h:715
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_exit_skcipher_ops_ablkcipher
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
In crypto/ablkcipher.c (0)
Location: include/linux/crypto.h:718
Inline: True
```
```
In crypto/blkcipher.c (0)
Location: include/linux/crypto.h:718
Inline: True
```
```
In crypto/skcipher.c (ffffffff813f5ef6)
Location: include/linux/crypto.h:718
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_exit_skcipher_ops_ablkcipher
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
In crypto/ablkcipher.c (0)
Location: include/linux/crypto.h:718
Inline: True
```
```
In crypto/blkcipher.c (0)
Location: include/linux/crypto.h:718
Inline: True
```
```
In crypto/skcipher.c (ffffffff81402286)
Location: include/linux/crypto.h:718
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_exit_skcipher_ops_ablkcipher
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
In crypto/ablkcipher.c (0)
Location: include/linux/crypto.h:766
Inline: True
```
```
In crypto/blkcipher.c (0)
Location: include/linux/crypto.h:766
Inline: True
```
```
In crypto/skcipher.c (ffffffff8142a8f6)
Location: include/linux/crypto.h:766
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_exit_skcipher_ops_ablkcipher
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
In crypto/ablkcipher.c (0)
Location: include/linux/crypto.h:779
Inline: True
```
```
In crypto/blkcipher.c (ffffffff8145c4e5)
Location: include/linux/crypto.h:779
Inline: True
Inline callers:
  - crypto/blkcipher.c:async_setkey
```
```
In crypto/skcipher.c (ffffffff8145d645)
Location: include/linux/crypto.h:779
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_exit_skcipher_ops_ablkcipher
  - crypto/skcipher.c:skcipher_decrypt_ablkcipher
  - crypto/skcipher.c:skcipher_encrypt_ablkcipher
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
In crypto/ablkcipher.c (0)
Location: include/linux/crypto.h:950
Inline: True
```
```
In crypto/blkcipher.c (ffffffff81479c25)
Location: include/linux/crypto.h:950
Inline: True
Inline callers:
  - crypto/blkcipher.c:async_setkey
```
```
In crypto/skcipher.c (ffffffff8147aed5)
Location: include/linux/crypto.h:950
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_exit_skcipher_ops_ablkcipher
  - crypto/skcipher.c:skcipher_decrypt_ablkcipher
  - crypto/skcipher.c:skcipher_encrypt_ablkcipher
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
In crypto/ablkcipher.c (0)
Location: include/linux/crypto.h:947
Inline: True
```
```
In crypto/blkcipher.c (ffffffff814a83c5)
Location: include/linux/crypto.h:947
Inline: True
Inline callers:
  - crypto/blkcipher.c:async_setkey
```
```
In crypto/skcipher.c (ffffffff814a8f15)
Location: include/linux/crypto.h:947
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_exit_skcipher_ops_ablkcipher
  - crypto/skcipher.c:skcipher_decrypt_ablkcipher
  - crypto/skcipher.c:skcipher_encrypt_ablkcipher
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
In crypto/ablkcipher.c (0)
Location: include/linux/crypto.h:947
Inline: True
```
```
In crypto/blkcipher.c (ffffffff814c3035)
Location: include/linux/crypto.h:947
Inline: True
Inline callers:
  - crypto/blkcipher.c:async_setkey
```
```
In crypto/skcipher.c (ffffffff814c3b75)
Location: include/linux/crypto.h:947
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_exit_skcipher_ops_ablkcipher
  - crypto/skcipher.c:skcipher_decrypt_ablkcipher
  - crypto/skcipher.c:skcipher_encrypt_ablkcipher
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
In crypto/ablkcipher.c (0)
Location: include/linux/crypto.h:947
Inline: True
```
```
In crypto/blkcipher.c (ffff8000105bd074)
Location: include/linux/crypto.h:947
Inline: True
Inline callers:
  - crypto/blkcipher.c:async_setkey
```
```
In crypto/skcipher.c (ffff8000105be508)
Location: include/linux/crypto.h:947
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_exit_skcipher_ops_ablkcipher
  - crypto/skcipher.c:skcipher_decrypt_ablkcipher
  - crypto/skcipher.c:skcipher_encrypt_ablkcipher
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
In crypto/ablkcipher.c (0)
Location: include/linux/crypto.h:947
Inline: True
```
```
In crypto/blkcipher.c (c076b5c4)
Location: include/linux/crypto.h:947
Inline: True
Inline callers:
  - crypto/blkcipher.c:async_setkey
```
```
In crypto/skcipher.c (c076c27c)
Location: include/linux/crypto.h:947
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_exit_skcipher_ops_ablkcipher
  - crypto/skcipher.c:skcipher_decrypt_ablkcipher
  - crypto/skcipher.c:skcipher_encrypt_ablkcipher
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
In crypto/ablkcipher.c (0)
Location: include/linux/crypto.h:947
Inline: True
```
```
In crypto/blkcipher.c (c000000000744b00)
Location: include/linux/crypto.h:947
Inline: True
Inline callers:
  - crypto/blkcipher.c:async_setkey
```
```
In crypto/skcipher.c (c000000000745cbc)
Location: include/linux/crypto.h:947
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_exit_skcipher_ops_ablkcipher
  - crypto/skcipher.c:skcipher_decrypt_ablkcipher
  - crypto/skcipher.c:skcipher_encrypt_ablkcipher
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
In crypto/ablkcipher.c (0)
Location: include/linux/crypto.h:947
Inline: True
```
```
In crypto/blkcipher.c (ffffffe00040279a)
Location: include/linux/crypto.h:947
Inline: True
Inline callers:
  - crypto/blkcipher.c:async_setkey
```
```
In crypto/skcipher.c (ffffffe00040391e)
Location: include/linux/crypto.h:947
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_exit_skcipher_ops_ablkcipher
  - crypto/skcipher.c:skcipher_decrypt_ablkcipher
  - crypto/skcipher.c:skcipher_encrypt_ablkcipher
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
In crypto/ablkcipher.c (0)
Location: include/linux/crypto.h:947
Inline: True
```
```
In crypto/blkcipher.c (ffffffff814bb615)
Location: include/linux/crypto.h:947
Inline: True
Inline callers:
  - crypto/blkcipher.c:async_setkey
```
```
In crypto/skcipher.c (ffffffff814bc155)
Location: include/linux/crypto.h:947
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_exit_skcipher_ops_ablkcipher
  - crypto/skcipher.c:skcipher_decrypt_ablkcipher
  - crypto/skcipher.c:skcipher_encrypt_ablkcipher
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
In crypto/ablkcipher.c (0)
Location: include/linux/crypto.h:947
Inline: True
```
```
In crypto/blkcipher.c (ffffffff814ac035)
Location: include/linux/crypto.h:947
Inline: True
Inline callers:
  - crypto/blkcipher.c:async_setkey
```
```
In crypto/skcipher.c (ffffffff814acb75)
Location: include/linux/crypto.h:947
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_exit_skcipher_ops_ablkcipher
  - crypto/skcipher.c:skcipher_decrypt_ablkcipher
  - crypto/skcipher.c:skcipher_encrypt_ablkcipher
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
In crypto/ablkcipher.c (0)
Location: include/linux/crypto.h:947
Inline: True
```
```
In crypto/blkcipher.c (ffffffff814b76a5)
Location: include/linux/crypto.h:947
Inline: True
Inline callers:
  - crypto/blkcipher.c:async_setkey
```
```
In crypto/skcipher.c (ffffffff814b81e5)
Location: include/linux/crypto.h:947
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_exit_skcipher_ops_ablkcipher
  - crypto/skcipher.c:skcipher_decrypt_ablkcipher
  - crypto/skcipher.c:skcipher_encrypt_ablkcipher
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
In crypto/ablkcipher.c (0)
Location: include/linux/crypto.h:947
Inline: True
```
```
In crypto/blkcipher.c (ffffffff814d0185)
Location: include/linux/crypto.h:947
Inline: True
Inline callers:
  - crypto/blkcipher.c:async_setkey
```
```
In crypto/skcipher.c (ffffffff814d0cc5)
Location: include/linux/crypto.h:947
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_exit_skcipher_ops_ablkcipher
  - crypto/skcipher.c:skcipher_decrypt_ablkcipher
  - crypto/skcipher.c:skcipher_encrypt_ablkcipher
```
</details>
</li>
</ul>

## Differences
