# Function: <code>ablkcipher_request_set_crypt</code>

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
In fs/ext4/crypto.c (ffffffff812e4f2b)
Location: include/linux/crypto.h:1052
Inline: True
Inline callers:
  - fs/ext4/crypto.c:ext4_page_crypto
```
```
In fs/ext4/crypto_key.c (ffffffff812e58c0)
Location: include/linux/crypto.h:1052
Inline: True
Inline callers:
  - fs/ext4/crypto_key.c:ext4_derive_key_aes
```
```
In fs/ext4/crypto_fname.c (ffffffff812e6134)
Location: include/linux/crypto.h:1052
Inline: True
Inline callers:
  - fs/ext4/crypto_fname.c:ext4_fname_encrypt
  - fs/ext4/crypto_fname.c:ext4_fname_decrypt
```
```
In fs/ecryptfs/crypto.c (ffffffff8130535c)
Location: include/linux/crypto.h:1052
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In crypto/skcipher.c (ffffffff813a1b96)
Location: include/linux/crypto.h:1052
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_encrypt_ablkcipher
  - crypto/skcipher.c:skcipher_decrypt_ablkcipher
```
```
In crypto/chainiv.c (ffffffff813a1ee1)
Location: include/linux/crypto.h:1052
Inline: True
Inline callers:
  - crypto/chainiv.c:chainiv_givencrypt
  - crypto/chainiv.c:async_chainiv_givencrypt
```
```
In crypto/eseqiv.c (ffffffff813a2787)
Location: include/linux/crypto.h:1052
Inline: True
Inline callers:
  - crypto/eseqiv.c:eseqiv_givencrypt
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
In crypto/skcipher.c (ffffffff813de0a6)
Location: include/linux/crypto.h:1009
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_decrypt_ablkcipher
  - crypto/skcipher.c:skcipher_encrypt_ablkcipher
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
In crypto/skcipher.c (ffffffff813f5976)
Location: include/linux/crypto.h:1012
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_decrypt_ablkcipher
  - crypto/skcipher.c:skcipher_encrypt_ablkcipher
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
In crypto/skcipher.c (ffffffff81401c16)
Location: include/linux/crypto.h:1012
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_decrypt_ablkcipher
  - crypto/skcipher.c:skcipher_encrypt_ablkcipher
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
In crypto/skcipher.c (ffffffff8142a266)
Location: include/linux/crypto.h:1060
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_decrypt_ablkcipher
  - crypto/skcipher.c:skcipher_encrypt_ablkcipher
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
In crypto/skcipher.c (ffffffff8145cfed)
Location: include/linux/crypto.h:1073
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_decrypt_ablkcipher
  - crypto/skcipher.c:skcipher_encrypt_ablkcipher
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
In crypto/skcipher.c (ffffffff8147a8ad)
Location: include/linux/crypto.h:1258
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_decrypt_ablkcipher
  - crypto/skcipher.c:skcipher_encrypt_ablkcipher
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
In crypto/skcipher.c (ffffffff814a880d)
Location: include/linux/crypto.h:1255
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_decrypt_ablkcipher
  - crypto/skcipher.c:skcipher_encrypt_ablkcipher
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
In crypto/skcipher.c (ffffffff814c346d)
Location: include/linux/crypto.h:1255
Inline: True
Inline callers:
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
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (0)
Location: include/linux/crypto.h:1255
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_decrypt_ablkcipher
  - crypto/skcipher.c:skcipher_encrypt_ablkcipher
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
In crypto/skcipher.c (c076bac8)
Location: include/linux/crypto.h:1255
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_decrypt_ablkcipher
  - crypto/skcipher.c:skcipher_encrypt_ablkcipher
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
In crypto/skcipher.c (c00000000074510c)
Location: include/linux/crypto.h:1255
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_decrypt_ablkcipher
  - crypto/skcipher.c:skcipher_encrypt_ablkcipher
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
In crypto/skcipher.c (ffffffe000403178)
Location: include/linux/crypto.h:1255
Inline: True
Inline callers:
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff814bba4d)
Location: include/linux/crypto.h:1255
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_decrypt_ablkcipher
  - crypto/skcipher.c:skcipher_encrypt_ablkcipher
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
In crypto/skcipher.c (ffffffff814ac46d)
Location: include/linux/crypto.h:1255
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_decrypt_ablkcipher
  - crypto/skcipher.c:skcipher_encrypt_ablkcipher
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
In crypto/skcipher.c (ffffffff814b7add)
Location: include/linux/crypto.h:1255
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_decrypt_ablkcipher
  - crypto/skcipher.c:skcipher_encrypt_ablkcipher
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
In crypto/skcipher.c (ffffffff814d05bd)
Location: include/linux/crypto.h:1255
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_decrypt_ablkcipher
  - crypto/skcipher.c:skcipher_encrypt_ablkcipher
```
</details>
</li>
</ul>

## Differences
