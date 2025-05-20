# Function: <code>crypto_ablkcipher_setkey</code>

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
In fs/ext4/crypto_key.c (ffffffff812e5856)
Location: include/linux/crypto.h:865
Inline: True
Inline callers:
  - fs/ext4/crypto_key.c:ext4_derive_key_aes
  - fs/ext4/crypto_key.c:_ext4_get_encryption_info
```
```
In fs/ecryptfs/crypto.c (ffffffff813053c8)
Location: include/linux/crypto.h:865
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In crypto/skcipher.c (ffffffff813a1b5c)
Location: include/linux/crypto.h:865
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
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
In crypto/skcipher.c (ffffffff813de00c)
Location: include/linux/crypto.h:823
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
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
In crypto/skcipher.c (ffffffff813f58dc)
Location: include/linux/crypto.h:826
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
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
In crypto/skcipher.c (ffffffff81401b7c)
Location: include/linux/crypto.h:826
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
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
In crypto/skcipher.c (ffffffff8142a1ac)
Location: include/linux/crypto.h:874
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
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
In crypto/skcipher.c (ffffffff8145cef7)
Location: include/linux/crypto.h:887
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
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
In crypto/skcipher.c (ffffffff8147a7ac)
Location: include/linux/crypto.h:1058
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
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
In crypto/skcipher.c (ffffffff814a895c)
Location: include/linux/crypto.h:1055
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
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
In crypto/skcipher.c (ffffffff814c35bc)
Location: include/linux/crypto.h:1055
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
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffff8000105bde44)
Location: include/linux/crypto.h:1055
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
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
In crypto/skcipher.c (c076bc64)
Location: include/linux/crypto.h:1055
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
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
In crypto/skcipher.c (c000000000745370)
Location: include/linux/crypto.h:1055
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
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
In crypto/skcipher.c (ffffffe00040331c)
Location: include/linux/crypto.h:1055
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff814bbb9c)
Location: include/linux/crypto.h:1055
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
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
In crypto/skcipher.c (ffffffff814ac5bc)
Location: include/linux/crypto.h:1055
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
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
In crypto/skcipher.c (ffffffff814b7c2c)
Location: include/linux/crypto.h:1055
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
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
In crypto/skcipher.c (ffffffff814d070c)
Location: include/linux/crypto.h:1055
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
```
</details>
</li>
</ul>

## Differences
