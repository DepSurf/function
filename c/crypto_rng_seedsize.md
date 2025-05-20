# Function: <code>crypto_rng_seedsize</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/rng.c (ffffffff813abca2)
Location: include/crypto/rng.h:195
Inline: True
Inline callers:
  - crypto/rng.c:crypto_get_default_rng
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
In security/keys/big_key.c (ffffffff81fc2d03)
Location: include/crypto/rng.h:195
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_crypto_init
```
```
In crypto/rng.c (ffffffff813eb4f2)
Location: include/crypto/rng.h:195
Inline: True
Inline callers:
  - crypto/rng.c:crypto_get_default_rng
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
In security/keys/big_key.c (ffffffff81fff712)
Location: include/crypto/rng.h:195
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_init
```
```
In crypto/rng.c (ffffffff81404c42)
Location: include/crypto/rng.h:195
Inline: True
Inline callers:
  - crypto/rng.c:crypto_get_default_rng
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
In security/keys/big_key.c (ffffffff820e29e5)
Location: include/crypto/rng.h:195
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_init
```
```
In crypto/rng.c (ffffffff814123a2)
Location: include/crypto/rng.h:195
Inline: True
Inline callers:
  - crypto/rng.c:crypto_get_default_rng
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
In crypto/rng.c (ffffffff8143cb32)
Location: include/crypto/rng.h:195
Inline: True
Inline callers:
  - crypto/rng.c:crypto_get_default_rng
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
In crypto/rng.c (ffffffff8146f962)
Location: include/crypto/rng.h:195
Inline: True
Inline callers:
  - crypto/rng.c:crypto_get_default_rng
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
In crypto/rng.c (ffffffff8148d342)
Location: include/crypto/rng.h:201
Inline: True
Inline callers:
  - crypto/rng.c:crypto_get_default_rng
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
In crypto/rng.c (ffffffff814bacb7)
Location: include/crypto/rng.h:196
Inline: True
Inline callers:
  - crypto/rng.c:crypto_get_default_rng
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
In crypto/rng.c (ffffffff814d3a87)
Location: include/crypto/rng.h:196
Inline: True
Inline callers:
  - crypto/rng.c:crypto_get_default_rng
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
In crypto/rng.c (ffffffff81532fc7)
Location: include/crypto/rng.h:196
Inline: True
Inline callers:
  - crypto/rng.c:crypto_get_default_rng
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
In crypto/rng.c (ffffffff8154ff3d)
Location: include/crypto/rng.h:196
Inline: True
Inline callers:
  - crypto/rng.c:crypto_get_default_rng
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
In crypto/rng.c (ffffffff8155856d)
Location: include/crypto/rng.h:198
Inline: True
Inline callers:
  - crypto/rng.c:crypto_get_default_rng
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
In crypto/rng.c (ffffffff815b981d)
Location: include/crypto/rng.h:198
Inline: True
Inline callers:
  - crypto/rng.c:crypto_get_default_rng
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
In crypto/rng.c (ffffffff81662d97)
Location: include/crypto/rng.h:198
Inline: True
Inline callers:
  - crypto/rng.c:crypto_get_default_rng
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
In crypto/rng.c (ffffffff8171cf77)
Location: include/crypto/rng.h:198
Inline: True
Inline callers:
  - crypto/rng.c:crypto_get_default_rng
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
In crypto/rng.c (ffffffff817587c7)
Location: include/crypto/rng.h:247
Inline: True
Inline callers:
  - crypto/rng.c:crypto_get_default_rng
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
In crypto/rng.c (ffffffff8179a6c7)
Location: include/crypto/rng.h:247
Inline: True
Inline callers:
  - crypto/rng.c:crypto_get_default_rng
```
</details>
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
In crypto/rng.c (ffff8000105d04c0)
Location: include/crypto/rng.h:196
Inline: True
Inline callers:
  - crypto/rng.c:crypto_get_default_rng
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
In crypto/rng.c (c077defc)
Location: include/crypto/rng.h:196
Inline: True
Inline callers:
  - crypto/rng.c:crypto_get_default_rng
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
In crypto/rng.c (c00000000075c714)
Location: include/crypto/rng.h:196
Inline: True
Inline callers:
  - crypto/rng.c:crypto_get_default_rng
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
In crypto/rng.c (ffffffe000415196)
Location: include/crypto/rng.h:196
Inline: True
Inline callers:
  - crypto/rng.c:crypto_get_default_rng
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
In crypto/rng.c (ffffffff814cc067)
Location: include/crypto/rng.h:196
Inline: True
Inline callers:
  - crypto/rng.c:crypto_get_default_rng
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
In crypto/rng.c (ffffffff814bca87)
Location: include/crypto/rng.h:196
Inline: True
Inline callers:
  - crypto/rng.c:crypto_get_default_rng
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
In crypto/rng.c (ffffffff814c80f7)
Location: include/crypto/rng.h:196
Inline: True
Inline callers:
  - crypto/rng.c:crypto_get_default_rng
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
In crypto/rng.c (ffffffff814e0bc7)
Location: include/crypto/rng.h:196
Inline: True
Inline callers:
  - crypto/rng.c:crypto_get_default_rng
```
</details>
</li>
</ul>

## Differences
