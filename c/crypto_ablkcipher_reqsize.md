# Function: <code>crypto_ablkcipher_reqsize</code>

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
Location: include/linux/crypto.h:941
Inline: True
```
```
In fs/ext4/crypto_key.c (0)
Location: include/linux/crypto.h:941
Inline: True
```
```
In fs/ext4/crypto_fname.c (0)
Location: include/linux/crypto.h:941
Inline: True
```
```
In fs/ecryptfs/crypto.c (0)
Location: include/linux/crypto.h:941
Inline: True
```
```
In crypto/blkcipher.c (0)
Location: include/linux/crypto.h:941
Inline: True
```
```
In crypto/skcipher.c (0)
Location: include/linux/crypto.h:941
Inline: True
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
In crypto/skcipher.c (0)
Location: include/linux/crypto.h:899
Inline: True
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
In crypto/skcipher.c (0)
Location: include/linux/crypto.h:902
Inline: True
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
In crypto/skcipher.c (0)
Location: include/linux/crypto.h:902
Inline: True
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
In crypto/skcipher.c (0)
Location: include/linux/crypto.h:950
Inline: True
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
In crypto/skcipher.c (ffffffff8145d567)
Location: include/linux/crypto.h:963
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_skcipher_init_tfm
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
In crypto/skcipher.c (ffffffff8147adf8)
Location: include/linux/crypto.h:1148
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_skcipher_init_tfm
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
In crypto/skcipher.c (ffffffff814a8e38)
Location: include/linux/crypto.h:1145
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_skcipher_init_tfm
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
In crypto/skcipher.c (ffffffff814c3a98)
Location: include/linux/crypto.h:1145
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_skcipher_init_tfm
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
In crypto/skcipher.c (ffff8000105be3ec)
Location: include/linux/crypto.h:1145
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_skcipher_init_tfm
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
In crypto/skcipher.c (c076c1fc)
Location: include/linux/crypto.h:1145
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_skcipher_init_tfm
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
In crypto/skcipher.c (c000000000745b30)
Location: include/linux/crypto.h:1145
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_skcipher_init_tfm
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
In crypto/skcipher.c (ffffffe0004038a8)
Location: include/linux/crypto.h:1145
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_skcipher_init_tfm
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
In crypto/skcipher.c (ffffffff814bc078)
Location: include/linux/crypto.h:1145
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_skcipher_init_tfm
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
In crypto/skcipher.c (ffffffff814aca98)
Location: include/linux/crypto.h:1145
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_skcipher_init_tfm
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
In crypto/skcipher.c (ffffffff814b8108)
Location: include/linux/crypto.h:1145
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_skcipher_init_tfm
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
In crypto/skcipher.c (ffffffff814d0be8)
Location: include/linux/crypto.h:1145
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_skcipher_init_tfm
```
</details>
</li>
</ul>

## Differences
