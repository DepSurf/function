# Function: <code>crypto_blkcipher_ivsize</code>

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
In security/keys/encrypted-keys/encrypted.c (ffffffff81f98251)
Location: include/linux/crypto.h:1196
Inline: True
```
```
In crypto/blkcipher.c (ffffffff813a190d)
Location: include/linux/crypto.h:1196
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_virt
  - crypto/blkcipher.c:blkcipher_walk_phys
  - crypto/blkcipher.c:blkcipher_walk_virt_block
```
```
In crypto/skcipher.c (ffffffff813a1def)
Location: include/linux/crypto.h:1196
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
In crypto/blkcipher.c (ffffffff813dde5d)
Location: include/linux/crypto.h:1153
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_virt_block
  - crypto/blkcipher.c:blkcipher_walk_phys
  - crypto/blkcipher.c:blkcipher_walk_virt
```
```
In crypto/skcipher.c (ffffffff813de49e)
Location: include/linux/crypto.h:1153
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_skcipher_init_tfm
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
In crypto/blkcipher.c (ffffffff813f570d)
Location: include/linux/crypto.h:1156
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_virt_block
  - crypto/blkcipher.c:blkcipher_walk_phys
  - crypto/blkcipher.c:blkcipher_walk_virt
```
```
In crypto/skcipher.c (ffffffff813f5e8e)
Location: include/linux/crypto.h:1156
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_skcipher_init_tfm
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
In crypto/blkcipher.c (ffffffff814019ad)
Location: include/linux/crypto.h:1156
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_virt_block
  - crypto/blkcipher.c:blkcipher_walk_phys
  - crypto/blkcipher.c:blkcipher_walk_virt
```
```
In crypto/skcipher.c (ffffffff8140220f)
Location: include/linux/crypto.h:1156
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_skcipher_init_tfm
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
In crypto/blkcipher.c (ffffffff81429fcd)
Location: include/linux/crypto.h:1204
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_virt_block
  - crypto/blkcipher.c:blkcipher_walk_phys
  - crypto/blkcipher.c:blkcipher_walk_virt
```
```
In crypto/skcipher.c (ffffffff8142a882)
Location: include/linux/crypto.h:1204
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_skcipher_init_tfm
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
In crypto/blkcipher.c (ffffffff8145cd0d)
Location: include/linux/crypto.h:1217
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_virt_block
  - crypto/blkcipher.c:blkcipher_walk_phys
  - crypto/blkcipher.c:blkcipher_walk_virt
```
```
In crypto/skcipher.c (ffffffff8145d5ea)
Location: include/linux/crypto.h:1217
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_skcipher_init_tfm
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
In crypto/blkcipher.c (ffffffff8147a59d)
Location: include/linux/crypto.h:1402
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_virt_block
  - crypto/blkcipher.c:blkcipher_walk_phys
  - crypto/blkcipher.c:blkcipher_walk_virt
```
```
In crypto/skcipher.c (ffffffff8147ae71)
Location: include/linux/crypto.h:1402
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_skcipher_init_tfm
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
In crypto/blkcipher.c (ffffffff814a85cd)
Location: include/linux/crypto.h:1399
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_virt_block
  - crypto/blkcipher.c:blkcipher_walk_phys
  - crypto/blkcipher.c:blkcipher_walk_virt
```
```
In crypto/skcipher.c (ffffffff814a8eb1)
Location: include/linux/crypto.h:1399
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_skcipher_init_tfm
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
In crypto/blkcipher.c (ffffffff814c323d)
Location: include/linux/crypto.h:1399
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_virt_block
  - crypto/blkcipher.c:blkcipher_walk_phys
  - crypto/blkcipher.c:blkcipher_walk_virt
```
```
In crypto/skcipher.c (ffffffff814c3b11)
Location: include/linux/crypto.h:1399
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
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/blkcipher.c (ffff8000105bd9d0)
Location: include/linux/crypto.h:1399
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_virt_block
  - crypto/blkcipher.c:blkcipher_walk_phys
  - crypto/blkcipher.c:blkcipher_walk_virt
```
```
In crypto/skcipher.c (ffff8000105be474)
Location: include/linux/crypto.h:1399
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_skcipher_init_tfm
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
In crypto/blkcipher.c (c076b844)
Location: include/linux/crypto.h:1399
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_virt_block
  - crypto/blkcipher.c:blkcipher_walk_phys
  - crypto/blkcipher.c:blkcipher_walk_virt
```
```
In crypto/skcipher.c (c076c174)
Location: include/linux/crypto.h:1399
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_skcipher_init_tfm
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
In crypto/blkcipher.c (c000000000744e10)
Location: include/linux/crypto.h:1399
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_virt_block
  - crypto/blkcipher.c:blkcipher_walk_phys
  - crypto/blkcipher.c:blkcipher_walk_virt
```
```
In crypto/skcipher.c (c000000000745be8)
Location: include/linux/crypto.h:1399
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_skcipher_init_tfm
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
In crypto/blkcipher.c (ffffffe000402f9c)
Location: include/linux/crypto.h:1399
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_virt_block
  - crypto/blkcipher.c:blkcipher_walk_phys
  - crypto/blkcipher.c:blkcipher_walk_virt
```
```
In crypto/skcipher.c (ffffffe00040382c)
Location: include/linux/crypto.h:1399
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
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/blkcipher.c (ffffffff814bb81d)
Location: include/linux/crypto.h:1399
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_virt_block
  - crypto/blkcipher.c:blkcipher_walk_phys
  - crypto/blkcipher.c:blkcipher_walk_virt
```
```
In crypto/skcipher.c (ffffffff814bc0f1)
Location: include/linux/crypto.h:1399
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_skcipher_init_tfm
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
In crypto/blkcipher.c (ffffffff814ac23d)
Location: include/linux/crypto.h:1399
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_virt_block
  - crypto/blkcipher.c:blkcipher_walk_phys
  - crypto/blkcipher.c:blkcipher_walk_virt
```
```
In crypto/skcipher.c (ffffffff814acb11)
Location: include/linux/crypto.h:1399
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_skcipher_init_tfm
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
In crypto/blkcipher.c (ffffffff814b78ad)
Location: include/linux/crypto.h:1399
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_virt_block
  - crypto/blkcipher.c:blkcipher_walk_phys
  - crypto/blkcipher.c:blkcipher_walk_virt
```
```
In crypto/skcipher.c (ffffffff814b8181)
Location: include/linux/crypto.h:1399
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_skcipher_init_tfm
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
In crypto/blkcipher.c (ffffffff814d038d)
Location: include/linux/crypto.h:1399
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_virt_block
  - crypto/blkcipher.c:blkcipher_walk_phys
  - crypto/blkcipher.c:blkcipher_walk_virt
```
```
In crypto/skcipher.c (ffffffff814d0c61)
Location: include/linux/crypto.h:1399
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_skcipher_init_tfm
```
</details>
</li>
</ul>

## Differences
