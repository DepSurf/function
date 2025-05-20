# Function: <code>crypto_ablkcipher_ivsize</code>

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
In crypto/skcipher.c (ffffffff813a1d68)
Location: include/linux/crypto.h:804
Inline: True
```
```
In crypto/chainiv.c (0)
Location: include/linux/crypto.h:804
Inline: True
```
```
In crypto/eseqiv.c (ffffffff813a2590)
Location: include/linux/crypto.h:804
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
In crypto/skcipher.c (ffffffff813de42e)
Location: include/linux/crypto.h:762
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_skcipher_init_tfm
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
In crypto/skcipher.c (ffffffff813f5e1e)
Location: include/linux/crypto.h:765
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_skcipher_init_tfm
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
In crypto/skcipher.c (ffffffff8140219f)
Location: include/linux/crypto.h:765
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_skcipher_init_tfm
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
In crypto/skcipher.c (ffffffff8142a812)
Location: include/linux/crypto.h:813
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_skcipher_init_tfm
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
In crypto/skcipher.c (ffffffff8145d561)
Location: include/linux/crypto.h:826
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
In crypto/skcipher.c (ffffffff8147adf2)
Location: include/linux/crypto.h:997
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
In crypto/skcipher.c (ffffffff814a8e32)
Location: include/linux/crypto.h:994
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
In crypto/skcipher.c (ffffffff814c3a92)
Location: include/linux/crypto.h:994
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
In crypto/skcipher.c (ffff8000105be3e4)
Location: include/linux/crypto.h:994
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
In crypto/skcipher.c (c076c1f4)
Location: include/linux/crypto.h:994
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
In crypto/skcipher.c (c000000000745b28)
Location: include/linux/crypto.h:994
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
In crypto/skcipher.c (ffffffe0004038a2)
Location: include/linux/crypto.h:994
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
In crypto/skcipher.c (ffffffff814bc072)
Location: include/linux/crypto.h:994
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
In crypto/skcipher.c (ffffffff814aca92)
Location: include/linux/crypto.h:994
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
In crypto/skcipher.c (ffffffff814b8102)
Location: include/linux/crypto.h:994
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
In crypto/skcipher.c (ffffffff814d0be2)
Location: include/linux/crypto.h:994
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_skcipher_init_tfm
```
</details>
</li>
</ul>

## Differences
