# Function: <code>crypto_ablkcipher_set_flags</code>

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
In fs/ext4/crypto_key.c (ffffffff812e582c)
Location: include/linux/crypto.h:837
Inline: True
Inline callers:
  - fs/ext4/crypto_key.c:ext4_derive_key_aes
```
```
In fs/ecryptfs/crypto.c (ffffffff81305f65)
Location: include/linux/crypto.h:837
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_ctx
```
```
In crypto/ablkcipher.c (ffffffff813a0380)
Location: include/linux/crypto.h:837
Inline: True
Inline callers:
  - crypto/ablkcipher.c:setkey
```
```
In crypto/skcipher.c (ffffffff813a1b59)
Location: include/linux/crypto.h:837
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
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
In crypto/ablkcipher.c (ffffffff813dca88)
Location: include/linux/crypto.h:795
Inline: True
Inline callers:
  - crypto/ablkcipher.c:setkey
```
```
In crypto/skcipher.c (ffffffff813de015)
Location: include/linux/crypto.h:795
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
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
In crypto/ablkcipher.c (ffffffff813f4368)
Location: include/linux/crypto.h:798
Inline: True
Inline callers:
  - crypto/ablkcipher.c:setkey
```
```
In crypto/skcipher.c (ffffffff813f58e5)
Location: include/linux/crypto.h:798
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
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
In crypto/ablkcipher.c (ffffffff814006c5)
Location: include/linux/crypto.h:798
Inline: True
Inline callers:
  - crypto/ablkcipher.c:setkey
```
```
In crypto/skcipher.c (ffffffff81401b85)
Location: include/linux/crypto.h:798
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
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
In crypto/ablkcipher.c (ffffffff81428cbf)
Location: include/linux/crypto.h:846
Inline: True
Inline callers:
  - crypto/ablkcipher.c:setkey
```
```
In crypto/skcipher.c (ffffffff8142a1b5)
Location: include/linux/crypto.h:846
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
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
In crypto/ablkcipher.c (ffffffff8145baef)
Location: include/linux/crypto.h:859
Inline: True
Inline callers:
  - crypto/ablkcipher.c:setkey
```
```
In crypto/skcipher.c (ffffffff8145cee9)
Location: include/linux/crypto.h:859
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
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
In crypto/ablkcipher.c (ffffffff8147926f)
Location: include/linux/crypto.h:1030
Inline: True
Inline callers:
  - crypto/ablkcipher.c:setkey
```
```
In crypto/skcipher.c (ffffffff8147a79b)
Location: include/linux/crypto.h:1030
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
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
In crypto/ablkcipher.c (ffffffff814a78bd)
Location: include/linux/crypto.h:1027
Inline: True
Inline callers:
  - crypto/ablkcipher.c:setkey
```
```
In crypto/skcipher.c (ffffffff814a894b)
Location: include/linux/crypto.h:1027
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
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
In crypto/ablkcipher.c (ffffffff814c253d)
Location: include/linux/crypto.h:1027
Inline: True
Inline callers:
  - crypto/ablkcipher.c:setkey
```
```
In crypto/skcipher.c (ffffffff814c35ab)
Location: include/linux/crypto.h:1027
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
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
In crypto/ablkcipher.c (ffff8000105bc558)
Location: include/linux/crypto.h:1027
Inline: True
Inline callers:
  - crypto/ablkcipher.c:setkey
```
```
In crypto/skcipher.c (ffff8000105bde38)
Location: include/linux/crypto.h:1027
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
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
In crypto/ablkcipher.c (c076ab14)
Location: include/linux/crypto.h:1027
Inline: True
Inline callers:
  - crypto/ablkcipher.c:setkey
```
```
In crypto/skcipher.c (c076bc50)
Location: include/linux/crypto.h:1027
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
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
In crypto/ablkcipher.c (c000000000743bd0)
Location: include/linux/crypto.h:1027
Inline: True
Inline callers:
  - crypto/ablkcipher.c:setkey
```
```
In crypto/skcipher.c (c000000000745358)
Location: include/linux/crypto.h:1027
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
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
In crypto/ablkcipher.c (ffffffe000401e02)
Location: include/linux/crypto.h:1027
Inline: True
Inline callers:
  - crypto/ablkcipher.c:setkey
```
```
In crypto/skcipher.c (ffffffe00040331a)
Location: include/linux/crypto.h:1027
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
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
In crypto/ablkcipher.c (ffffffff814bab1d)
Location: include/linux/crypto.h:1027
Inline: True
Inline callers:
  - crypto/ablkcipher.c:setkey
```
```
In crypto/skcipher.c (ffffffff814bbb8b)
Location: include/linux/crypto.h:1027
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
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
In crypto/ablkcipher.c (ffffffff814ab53d)
Location: include/linux/crypto.h:1027
Inline: True
Inline callers:
  - crypto/ablkcipher.c:setkey
```
```
In crypto/skcipher.c (ffffffff814ac5ab)
Location: include/linux/crypto.h:1027
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
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
In crypto/ablkcipher.c (ffffffff814b6bad)
Location: include/linux/crypto.h:1027
Inline: True
Inline callers:
  - crypto/ablkcipher.c:setkey
```
```
In crypto/skcipher.c (ffffffff814b7c1b)
Location: include/linux/crypto.h:1027
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
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
In crypto/ablkcipher.c (ffffffff814cf63d)
Location: include/linux/crypto.h:1027
Inline: True
Inline callers:
  - crypto/ablkcipher.c:setkey
```
```
In crypto/skcipher.c (ffffffff814d06fb)
Location: include/linux/crypto.h:1027
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
```
</details>
</li>
</ul>

## Differences
