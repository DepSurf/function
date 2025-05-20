# Function: <code>__crypto_shash_cast</code>

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
In crypto/shash.c (0)
Location: include/crypto/internal/hash.h:241
Inline: True
```
```
In crypto/hmac.c (0)
Location: include/crypto/internal/hash.h:241
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
In crypto/shash.c (0)
Location: include/crypto/internal/hash.h:234
Inline: True
```
```
In crypto/hmac.c (0)
Location: include/crypto/internal/hash.h:234
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
In crypto/shash.c (0)
Location: include/crypto/internal/hash.h:234
Inline: True
```
```
In crypto/hmac.c (0)
Location: include/crypto/internal/hash.h:234
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
In crypto/shash.c (0)
Location: include/crypto/internal/hash.h:244
Inline: True
```
```
In crypto/hmac.c (0)
Location: include/crypto/internal/hash.h:244
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
In crypto/shash.c (0)
Location: include/crypto/internal/hash.h:256
Inline: True
```
```
In crypto/hmac.c (0)
Location: include/crypto/internal/hash.h:256
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
In crypto/shash.c (ffffffff8145f535)
Location: include/crypto/internal/hash.h:251
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_init_tfm
```
```
In crypto/hmac.c (ffffffff81463735)
Location: include/crypto/internal/hash.h:251
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_exit_tfm
  - crypto/hmac.c:hmac_init_tfm
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
In crypto/shash.c (ffffffff8147cf65)
Location: include/crypto/internal/hash.h:251
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_init_tfm
```
```
In crypto/hmac.c (ffffffff814813b5)
Location: include/crypto/internal/hash.h:251
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_exit_tfm
  - crypto/hmac.c:hmac_init_tfm
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
In crypto/shash.c (ffffffff814ab255)
Location: include/crypto/internal/hash.h:240
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_init_tfm
```
```
In crypto/hmac.c (ffffffff814af585)
Location: include/crypto/internal/hash.h:240
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_exit_tfm
  - crypto/hmac.c:hmac_init_tfm
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
In crypto/shash.c (ffffffff814c5f15)
Location: include/crypto/internal/hash.h:240
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_init_tfm
```
```
In crypto/hmac.c (ffffffff814ca215)
Location: include/crypto/internal/hash.h:240
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_exit_tfm
  - crypto/hmac.c:hmac_init_tfm
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff81525515)
Location: include/crypto/internal/hash.h:252
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_init_tfm
  - crypto/shash.c:crypto_shash_exit_tfm
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff81542445)
Location: include/crypto/internal/hash.h:245
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_init_tfm
  - crypto/shash.c:crypto_shash_exit_tfm
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff8154aae5)
Location: include/crypto/internal/hash.h:239
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_init_tfm
  - crypto/shash.c:crypto_shash_exit_tfm
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff815ab2c5)
Location: include/crypto/internal/hash.h:239
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_init_tfm
  - crypto/shash.c:crypto_shash_exit_tfm
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff81652ac5)
Location: include/crypto/internal/hash.h:239
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_init_tfm
  - crypto/shash.c:crypto_shash_exit_tfm
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff8170c705)
Location: include/crypto/internal/hash.h:267
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_init_tfm
  - crypto/shash.c:crypto_shash_exit_tfm
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff81746215)
Location: include/crypto/internal/hash.h:277
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_init_tfm
  - crypto/shash.c:crypto_shash_exit_tfm
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff81788855)
Location: include/crypto/internal/hash.h:270
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_init_tfm
  - crypto/shash.c:crypto_shash_exit_tfm
```
</details>
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
In crypto/shash.c (ffff8000105c0f08)
Location: include/crypto/internal/hash.h:240
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_init_tfm
```
```
In crypto/hmac.c (ffff8000105c5f00)
Location: include/crypto/internal/hash.h:240
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_exit_tfm
  - crypto/hmac.c:hmac_init_tfm
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
In crypto/shash.c (c076e838)
Location: include/crypto/internal/hash.h:240
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_init_tfm
```
```
In crypto/hmac.c (c0772c08)
Location: include/crypto/internal/hash.h:240
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_exit_tfm
  - crypto/hmac.c:hmac_init_tfm
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
In crypto/shash.c (c000000000749270)
Location: include/crypto/internal/hash.h:240
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_init_tfm
```
```
In crypto/hmac.c (c00000000074f92c)
Location: include/crypto/internal/hash.h:240
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_exit_tfm
  - crypto/hmac.c:hmac_init_tfm
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
In crypto/shash.c (ffffffe000405d0c)
Location: include/crypto/internal/hash.h:240
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_init_tfm
```
```
In crypto/hmac.c (ffffffe000409f9c)
Location: include/crypto/internal/hash.h:240
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_exit_tfm
  - crypto/hmac.c:hmac_init_tfm
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
In crypto/shash.c (ffffffff814be4f5)
Location: include/crypto/internal/hash.h:240
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_init_tfm
```
```
In crypto/hmac.c (ffffffff814c27f5)
Location: include/crypto/internal/hash.h:240
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_exit_tfm
  - crypto/hmac.c:hmac_init_tfm
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
In crypto/shash.c (ffffffff814aef15)
Location: include/crypto/internal/hash.h:240
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_init_tfm
```
```
In crypto/hmac.c (ffffffff814b3215)
Location: include/crypto/internal/hash.h:240
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_exit_tfm
  - crypto/hmac.c:hmac_init_tfm
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
In crypto/shash.c (ffffffff814ba585)
Location: include/crypto/internal/hash.h:240
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_init_tfm
```
```
In crypto/hmac.c (ffffffff814be885)
Location: include/crypto/internal/hash.h:240
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_exit_tfm
  - crypto/hmac.c:hmac_init_tfm
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
In crypto/shash.c (ffffffff814d3035)
Location: include/crypto/internal/hash.h:240
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_init_tfm
```
```
In crypto/hmac.c (ffffffff814d7355)
Location: include/crypto/internal/hash.h:240
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_exit_tfm
  - crypto/hmac.c:hmac_init_tfm
```
</details>
</li>
</ul>

## Differences
