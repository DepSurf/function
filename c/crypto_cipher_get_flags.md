# Function: <code>crypto_cipher_get_flags</code>

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
In crypto/ecb.c (0)
Location: include/linux/crypto.h:1508
Inline: True
```
```
In crypto/cbc.c (0)
Location: include/linux/crypto.h:1508
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
In crypto/ecb.c (0)
Location: include/linux/crypto.h:1465
Inline: True
```
```
In crypto/cbc.c (0)
Location: include/linux/crypto.h:1465
Inline: True
```
```
In crypto/xts.c (0)
Location: include/linux/crypto.h:1465
Inline: True
```
```
In crypto/ctr.c (0)
Location: include/linux/crypto.h:1465
Inline: True
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
In crypto/ecb.c (0)
Location: include/linux/crypto.h:1468
Inline: True
```
```
In crypto/cbc.c (0)
Location: include/linux/crypto.h:1468
Inline: True
```
```
In crypto/xts.c (0)
Location: include/linux/crypto.h:1468
Inline: True
```
```
In crypto/ctr.c (0)
Location: include/linux/crypto.h:1468
Inline: True
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
In crypto/ecb.c (0)
Location: include/linux/crypto.h:1468
Inline: True
```
```
In crypto/cbc.c (0)
Location: include/linux/crypto.h:1468
Inline: True
```
```
In crypto/xts.c (0)
Location: include/linux/crypto.h:1468
Inline: True
```
```
In crypto/ctr.c (0)
Location: include/linux/crypto.h:1468
Inline: True
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
In crypto/ecb.c (0)
Location: include/linux/crypto.h:1516
Inline: True
```
```
In crypto/cbc.c (0)
Location: include/linux/crypto.h:1516
Inline: True
```
```
In crypto/xts.c (0)
Location: include/linux/crypto.h:1516
Inline: True
```
```
In crypto/ctr.c (0)
Location: include/linux/crypto.h:1516
Inline: True
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
In crypto/ecb.c (ffffffff814684e4)
Location: include/linux/crypto.h:1529
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_setkey
```
```
In crypto/cbc.c (ffffffff81468855)
Location: include/linux/crypto.h:1529
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_setkey
```
```
In crypto/xts.c (ffffffff81469ad8)
Location: include/linux/crypto.h:1529
Inline: True
```
```
In crypto/ctr.c (ffffffff8146a654)
Location: include/linux/crypto.h:1529
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_setkey
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
In crypto/ecb.c (ffffffff81486154)
Location: include/linux/crypto.h:1714
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_setkey
```
```
In crypto/cbc.c (ffffffff814864c5)
Location: include/linux/crypto.h:1714
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_setkey
```
```
In crypto/xts.c (ffffffff814879a8)
Location: include/linux/crypto.h:1714
Inline: True
```
```
In crypto/ctr.c (ffffffff81487eb4)
Location: include/linux/crypto.h:1714
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_setkey
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
In crypto/skcipher.c (ffffffff814a88ac)
Location: include/linux/crypto.h:1711
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_simple
```
```
In crypto/xts.c (ffffffff814b56bc)
Location: include/linux/crypto.h:1711
Inline: True
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
In crypto/skcipher.c (ffffffff814c350c)
Location: include/linux/crypto.h:1711
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_simple
```
```
In crypto/xts.c (ffffffff814ce8bc)
Location: include/linux/crypto.h:1711
Inline: True
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
In crypto/skcipher.c (ffff8000105bdd40)
Location: include/linux/crypto.h:1711
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_simple
```
```
In crypto/xts.c (ffff8000105caab8)
Location: include/linux/crypto.h:1711
Inline: True
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
In crypto/skcipher.c (c076bb84)
Location: include/linux/crypto.h:1711
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_simple
```
```
In crypto/xts.c (c07786ac)
Location: include/linux/crypto.h:1711
Inline: True
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
In crypto/skcipher.c (c000000000745230)
Location: include/linux/crypto.h:1711
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_simple
```
```
In crypto/xts.c (c00000000075543c)
Location: include/linux/crypto.h:1711
Inline: True
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
In crypto/skcipher.c (ffffffe000403252)
Location: include/linux/crypto.h:1711
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_simple
```
```
In crypto/xts.c (ffffffe00040ecce)
Location: include/linux/crypto.h:1711
Inline: True
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
In crypto/skcipher.c (ffffffff814bbaec)
Location: include/linux/crypto.h:1711
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_simple
```
```
In crypto/xts.c (ffffffff814c6e9c)
Location: include/linux/crypto.h:1711
Inline: True
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
In crypto/skcipher.c (ffffffff814ac50c)
Location: include/linux/crypto.h:1711
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_simple
```
```
In crypto/xts.c (ffffffff814b78bc)
Location: include/linux/crypto.h:1711
Inline: True
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
In crypto/skcipher.c (ffffffff814b7b7c)
Location: include/linux/crypto.h:1711
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_simple
```
```
In crypto/xts.c (ffffffff814c2f2c)
Location: include/linux/crypto.h:1711
Inline: True
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
In crypto/skcipher.c (ffffffff814d065c)
Location: include/linux/crypto.h:1711
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_simple
```
```
In crypto/xts.c (ffffffff814db9fc)
Location: include/linux/crypto.h:1711
Inline: True
```
</details>
</li>
</ul>

## Differences
