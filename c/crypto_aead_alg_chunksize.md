# Function: <code>crypto_aead_alg_chunksize</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
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
Location: include/crypto/internal/aead.h:162
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
Location: include/crypto/internal/aead.h:162
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
In crypto/skcipher.c (0)
Location: include/crypto/internal/aead.h:162
Inline: True
```
```
In crypto/gcm.c (0)
Location: include/crypto/internal/aead.h:162
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
In crypto/skcipher.c (0)
Location: include/crypto/internal/aead.h:162
Inline: True
```
```
In crypto/gcm.c (0)
Location: include/crypto/internal/aead.h:162
Inline: True
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
In crypto/skcipher.c (0)
Location: include/crypto/internal/aead.h:162
Inline: True
```
```
In crypto/gcm.c (0)
Location: include/crypto/internal/aead.h:162
Inline: True
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
In crypto/skcipher.c (0)
Location: include/crypto/internal/aead.h:157
Inline: True
```
```
In crypto/gcm.c (0)
Location: include/crypto/internal/aead.h:157
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
In crypto/skcipher.c (0)
Location: include/crypto/internal/aead.h:157
Inline: True
```
```
In crypto/gcm.c (0)
Location: include/crypto/internal/aead.h:157
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff81523b7d)
Location: include/crypto/internal/aead.h:142
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
```
```
In crypto/gcm.c (ffffffff8152f796)
Location: include/crypto/internal/aead.h:142
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_create
  - crypto/gcm.c:crypto_rfc4106_create
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff81540acd)
Location: include/crypto/internal/aead.h:142
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
```
```
In crypto/gcm.c (ffffffff8154c849)
Location: include/crypto/internal/aead.h:142
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_create
  - crypto/gcm.c:crypto_rfc4106_create
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff8154912d)
Location: include/crypto/internal/aead.h:142
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
```
```
In crypto/gcm.c (ffffffff81554b0e)
Location: include/crypto/internal/aead.h:142
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_create
  - crypto/gcm.c:crypto_rfc4106_create
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff815a990d)
Location: include/crypto/internal/aead.h:142
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
```
```
In crypto/gcm.c (ffffffff815b5d0e)
Location: include/crypto/internal/aead.h:142
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_create
  - crypto/gcm.c:crypto_rfc4106_create
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff81650d6d)
Location: include/crypto/internal/aead.h:142
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
```
```
In crypto/gcm.c (ffffffff8165ef7c)
Location: include/crypto/internal/aead.h:142
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_create
  - crypto/gcm.c:crypto_rfc4106_create
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff8170a55d)
Location: include/crypto/internal/aead.h:139
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
```
```
In crypto/gcm.c (ffffffff81718cfc)
Location: include/crypto/internal/aead.h:139
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_create
  - crypto/gcm.c:crypto_rfc4106_create
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff81743dad)
Location: include/crypto/internal/aead.h:139
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
```
```
In crypto/gcm.c (ffffffff81754878)
Location: include/crypto/internal/aead.h:139
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_create
  - crypto/gcm.c:crypto_rfc4106_create
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff8178618d)
Location: include/crypto/internal/aead.h:139
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
```
```
In crypto/gcm.c (ffffffff81796007)
Location: include/crypto/internal/aead.h:139
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_create
  - crypto/gcm.c:crypto_rfc4106_create
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
In crypto/skcipher.c (0)
Location: include/crypto/internal/aead.h:157
Inline: True
```
```
In crypto/gcm.c (0)
Location: include/crypto/internal/aead.h:157
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
In crypto/skcipher.c (c076d4d4)
Location: include/crypto/internal/aead.h:157
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
```
```
In crypto/gcm.c (c0779620)
Location: include/crypto/internal/aead.h:157
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_create
  - crypto/gcm.c:crypto_rfc4106_create
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
In crypto/skcipher.c (0)
Location: include/crypto/internal/aead.h:157
Inline: True
```
```
In crypto/gcm.c (0)
Location: include/crypto/internal/aead.h:157
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
In crypto/skcipher.c (0)
Location: include/crypto/internal/aead.h:157
Inline: True
```
```
In crypto/gcm.c (0)
Location: include/crypto/internal/aead.h:157
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
In crypto/skcipher.c (0)
Location: include/crypto/internal/aead.h:157
Inline: True
```
```
In crypto/gcm.c (0)
Location: include/crypto/internal/aead.h:157
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
In crypto/skcipher.c (0)
Location: include/crypto/internal/aead.h:157
Inline: True
```
```
In crypto/gcm.c (0)
Location: include/crypto/internal/aead.h:157
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
In crypto/skcipher.c (0)
Location: include/crypto/internal/aead.h:157
Inline: True
```
```
In crypto/gcm.c (0)
Location: include/crypto/internal/aead.h:157
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
In crypto/skcipher.c (0)
Location: include/crypto/internal/aead.h:157
Inline: True
```
```
In crypto/gcm.c (0)
Location: include/crypto/internal/aead.h:157
Inline: True
```
</details>
</li>
</ul>

## Differences
