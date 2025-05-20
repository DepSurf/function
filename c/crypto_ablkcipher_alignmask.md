# Function: <code>crypto_ablkcipher_alignmask</code>

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
In crypto/ablkcipher.c (0)
Location: include/linux/crypto.h:826
Inline: True
```
```
In crypto/eseqiv.c (ffffffff813a238c)
Location: include/linux/crypto.h:826
Inline: True
Inline callers:
  - crypto/eseqiv.c:eseqiv_init
  - crypto/eseqiv.c:eseqiv_complete2
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
In crypto/ablkcipher.c (0)
Location: include/linux/crypto.h:784
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
In crypto/ablkcipher.c (0)
Location: include/linux/crypto.h:787
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
In crypto/ablkcipher.c (0)
Location: include/linux/crypto.h:787
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
In crypto/ablkcipher.c (0)
Location: include/linux/crypto.h:835
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
In crypto/ablkcipher.c (ffffffff8145ba3a)
Location: include/linux/crypto.h:848
Inline: True
Inline callers:
  - crypto/ablkcipher.c:setkey
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
In crypto/ablkcipher.c (ffffffff814791ba)
Location: include/linux/crypto.h:1019
Inline: True
Inline callers:
  - crypto/ablkcipher.c:setkey
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
In crypto/ablkcipher.c (ffffffff814a77fd)
Location: include/linux/crypto.h:1016
Inline: True
Inline callers:
  - crypto/ablkcipher.c:setkey
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
In crypto/ablkcipher.c (ffffffff814c247d)
Location: include/linux/crypto.h:1016
Inline: True
Inline callers:
  - crypto/ablkcipher.c:setkey
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
In crypto/ablkcipher.c (ffff8000105bc484)
Location: include/linux/crypto.h:1016
Inline: True
Inline callers:
  - crypto/ablkcipher.c:setkey
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
In crypto/ablkcipher.c (c076aa68)
Location: include/linux/crypto.h:1016
Inline: True
Inline callers:
  - crypto/ablkcipher.c:setkey
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
In crypto/ablkcipher.c (c000000000743a98)
Location: include/linux/crypto.h:1016
Inline: True
Inline callers:
  - crypto/ablkcipher.c:setkey
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
In crypto/ablkcipher.c (ffffffe000401d62)
Location: include/linux/crypto.h:1016
Inline: True
Inline callers:
  - crypto/ablkcipher.c:setkey
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
In crypto/ablkcipher.c (ffffffff814baa5d)
Location: include/linux/crypto.h:1016
Inline: True
Inline callers:
  - crypto/ablkcipher.c:setkey
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
In crypto/ablkcipher.c (ffffffff814ab47d)
Location: include/linux/crypto.h:1016
Inline: True
Inline callers:
  - crypto/ablkcipher.c:setkey
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
In crypto/ablkcipher.c (ffffffff814b6aed)
Location: include/linux/crypto.h:1016
Inline: True
Inline callers:
  - crypto/ablkcipher.c:setkey
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
In crypto/ablkcipher.c (ffffffff814cf57d)
Location: include/linux/crypto.h:1016
Inline: True
Inline callers:
  - crypto/ablkcipher.c:setkey
```
</details>
</li>
</ul>

## Differences
