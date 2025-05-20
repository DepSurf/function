# Function: <code>crypto_rng_alg</code>

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
In crypto/aead.c (0)
Location: include/crypto/rng.h:110
Inline: True
```
```
In crypto/chainiv.c (0)
Location: include/crypto/rng.h:110
Inline: True
```
```
In crypto/eseqiv.c (0)
Location: include/crypto/rng.h:110
Inline: True
```
```
In crypto/rng.c (0)
Location: include/crypto/rng.h:110
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
In security/keys/big_key.c (0)
Location: include/crypto/rng.h:110
Inline: True
```
```
In crypto/aead.c (0)
Location: include/crypto/rng.h:110
Inline: True
```
```
In crypto/rng.c (0)
Location: include/crypto/rng.h:110
Inline: True
```
```
In crypto/drbg.c (0)
Location: include/crypto/rng.h:110
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
In security/keys/big_key.c (0)
Location: include/crypto/rng.h:110
Inline: True
```
```
In crypto/aead.c (0)
Location: include/crypto/rng.h:110
Inline: True
```
```
In crypto/rng.c (0)
Location: include/crypto/rng.h:110
Inline: True
```
```
In crypto/drbg.c (0)
Location: include/crypto/rng.h:110
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
In security/keys/big_key.c (0)
Location: include/crypto/rng.h:110
Inline: True
```
```
In crypto/aead.c (0)
Location: include/crypto/rng.h:110
Inline: True
```
```
In crypto/rng.c (0)
Location: include/crypto/rng.h:110
Inline: True
```
```
In crypto/drbg.c (0)
Location: include/crypto/rng.h:110
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
In crypto/aead.c (0)
Location: include/crypto/rng.h:110
Inline: True
```
```
In crypto/rng.c (0)
Location: include/crypto/rng.h:110
Inline: True
```
```
In crypto/drbg.c (0)
Location: include/crypto/rng.h:110
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
In crypto/aead.c (ffffffff8145aebf)
Location: include/crypto/rng.h:110
Inline: True
Inline callers:
  - crypto/aead.c:aead_init_geniv
```
```
In crypto/rng.c (ffffffff8146f962)
Location: include/crypto/rng.h:110
Inline: True
Inline callers:
  - crypto/rng.c:crypto_get_default_rng
  - crypto/rng.c:crypto_rng_reset
```
```
In crypto/drbg.c (ffffffff81470193)
Location: include/crypto/rng.h:110
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_seed
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
In crypto/aead.c (ffffffff81478e44)
Location: include/crypto/rng.h:110
Inline: True
Inline callers:
  - crypto/aead.c:aead_init_geniv
```
```
In crypto/rng.c (ffffffff8148d342)
Location: include/crypto/rng.h:110
Inline: True
Inline callers:
  - crypto/rng.c:crypto_get_default_rng
  - crypto/rng.c:crypto_rng_reset
```
```
In crypto/drbg.c (ffffffff8148f297)
Location: include/crypto/rng.h:110
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_seed
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
In crypto/aead.c (ffffffff814a6d66)
Location: include/crypto/rng.h:105
Inline: True
Inline callers:
  - crypto/aead.c:aead_init_geniv
```
```
In crypto/rng.c (ffffffff814bacb7)
Location: include/crypto/rng.h:105
Inline: True
Inline callers:
  - crypto/rng.c:crypto_get_default_rng
  - crypto/rng.c:crypto_rng_reset
```
```
In crypto/drbg.c (ffffffff814bcbc7)
Location: include/crypto/rng.h:105
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_seed
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
In crypto/aead.c (ffffffff814c19d6)
Location: include/crypto/rng.h:105
Inline: True
Inline callers:
  - crypto/aead.c:aead_init_geniv
```
```
In crypto/rng.c (ffffffff814d3a87)
Location: include/crypto/rng.h:105
Inline: True
Inline callers:
  - crypto/rng.c:crypto_get_default_rng
  - crypto/rng.c:crypto_rng_reset
```
```
In crypto/drbg.c (ffffffff814d585a)
Location: include/crypto/rng.h:105
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_seed
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
In crypto/geniv.c (ffffffff81522316)
Location: include/crypto/rng.h:105
Inline: True
Inline callers:
  - crypto/geniv.c:aead_init_geniv
```
```
In crypto/rng.c (ffffffff81532fc7)
Location: include/crypto/rng.h:105
Inline: True
Inline callers:
  - crypto/rng.c:crypto_get_default_rng
  - crypto/rng.c:crypto_rng_reset
```
```
In crypto/drbg.c (ffffffff81533275)
Location: include/crypto/rng.h:105
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_seed
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
In crypto/geniv.c (ffffffff8153f1f6)
Location: include/crypto/rng.h:105
Inline: True
Inline callers:
  - crypto/geniv.c:aead_init_geniv
```
```
In crypto/rng.c (ffffffff8154ff3d)
Location: include/crypto/rng.h:105
Inline: True
Inline callers:
  - crypto/rng.c:crypto_get_default_rng
  - crypto/rng.c:crypto_rng_reset
```
```
In crypto/drbg.c (ffffffff815501c5)
Location: include/crypto/rng.h:105
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_seed
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
In crypto/geniv.c (ffffffff81547876)
Location: include/crypto/rng.h:105
Inline: True
Inline callers:
  - crypto/geniv.c:aead_init_geniv
```
```
In crypto/rng.c (ffffffff8155856d)
Location: include/crypto/rng.h:105
Inline: True
Inline callers:
  - crypto/rng.c:crypto_get_default_rng
  - crypto/rng.c:crypto_rng_reset
```
```
In crypto/drbg.c (ffffffff815589b5)
Location: include/crypto/rng.h:105
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_seed
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
In crypto/geniv.c (ffffffff815a8056)
Location: include/crypto/rng.h:105
Inline: True
Inline callers:
  - crypto/geniv.c:aead_init_geniv
```
```
In crypto/rng.c (ffffffff815b981d)
Location: include/crypto/rng.h:105
Inline: True
Inline callers:
  - crypto/rng.c:crypto_get_default_rng
  - crypto/rng.c:crypto_rng_reset
```
```
In crypto/drbg.c (ffffffff815b9c65)
Location: include/crypto/rng.h:105
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_seed
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
In crypto/geniv.c (ffffffff8164f403)
Location: include/crypto/rng.h:105
Inline: True
Inline callers:
  - crypto/geniv.c:aead_init_geniv
```
```
In crypto/dh.c (ffffffff816542cf)
Location: include/crypto/rng.h:105
Inline: True
```
```
In crypto/rng.c (ffffffff81662d97)
Location: include/crypto/rng.h:105
Inline: True
Inline callers:
  - crypto/rng.c:crypto_get_default_rng
  - crypto/rng.c:crypto_rng_reset
```
```
In crypto/drbg.c (ffffffff816637c1)
Location: include/crypto/rng.h:105
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_seed
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
In crypto/geniv.c (ffffffff81708a03)
Location: include/crypto/rng.h:105
Inline: True
Inline callers:
  - crypto/geniv.c:aead_init_geniv
```
```
In crypto/dh.c (ffffffff8170e29f)
Location: include/crypto/rng.h:105
Inline: True
```
```
In crypto/rng.c (ffffffff8171cf77)
Location: include/crypto/rng.h:105
Inline: True
Inline callers:
  - crypto/rng.c:crypto_get_default_rng
  - crypto/rng.c:crypto_rng_reset
```
```
In crypto/drbg.c (ffffffff8171dac1)
Location: include/crypto/rng.h:105
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_seed
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
In crypto/geniv.c (ffffffff817421a9)
Location: include/crypto/rng.h:131
Inline: True
Inline callers:
  - crypto/geniv.c:aead_init_geniv
```
```
In crypto/dh.c (ffffffff81748b37)
Location: include/crypto/rng.h:131
Inline: True
```
```
In crypto/rng.c (ffffffff817587c7)
Location: include/crypto/rng.h:131
Inline: True
Inline callers:
  - crypto/rng.c:crypto_get_default_rng
  - crypto/rng.c:crypto_rng_reset
```
```
In crypto/drbg.c (ffffffff817593be)
Location: include/crypto/rng.h:131
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_seed
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
In crypto/geniv.c (ffffffff81783089)
Location: include/crypto/rng.h:131
Inline: True
Inline callers:
  - crypto/geniv.c:aead_init_geniv
```
```
In crypto/dh.c (ffffffff8178a9d7)
Location: include/crypto/rng.h:131
Inline: True
```
```
In crypto/rng.c (ffffffff8179a6c7)
Location: include/crypto/rng.h:131
Inline: True
Inline callers:
  - crypto/rng.c:crypto_get_default_rng
  - crypto/rng.c:crypto_rng_reset
```
```
In crypto/drbg.c (ffffffff8179b2be)
Location: include/crypto/rng.h:131
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_seed
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
In crypto/aead.c (ffff8000105bc0dc)
Location: include/crypto/rng.h:105
Inline: True
Inline callers:
  - crypto/aead.c:aead_init_geniv
```
```
In crypto/rng.c (ffff8000105d04c0)
Location: include/crypto/rng.h:105
Inline: True
Inline callers:
  - crypto/rng.c:crypto_get_default_rng
  - crypto/rng.c:crypto_rng_reset
```
```
In crypto/drbg.c (ffff8000105d10f4)
Location: include/crypto/rng.h:105
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_seed
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
In crypto/aead.c (c076a138)
Location: include/crypto/rng.h:105
Inline: True
Inline callers:
  - crypto/aead.c:aead_init_geniv
```
```
In crypto/rng.c (c077defc)
Location: include/crypto/rng.h:105
Inline: True
Inline callers:
  - crypto/rng.c:crypto_get_default_rng
  - crypto/rng.c:crypto_rng_reset
```
```
In crypto/drbg.c (c077f164)
Location: include/crypto/rng.h:105
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_seed
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
In crypto/aead.c (c000000000742a40)
Location: include/crypto/rng.h:105
Inline: True
Inline callers:
  - crypto/aead.c:aead_init_geniv
```
```
In crypto/rng.c (c00000000075c714)
Location: include/crypto/rng.h:105
Inline: True
Inline callers:
  - crypto/rng.c:crypto_get_default_rng
  - crypto/rng.c:crypto_rng_reset
```
```
In crypto/drbg.c (c00000000075e440)
Location: include/crypto/rng.h:105
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_seed
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
In crypto/aead.c (ffffffe000401862)
Location: include/crypto/rng.h:105
Inline: True
Inline callers:
  - crypto/aead.c:aead_init_geniv
```
```
In crypto/rng.c (ffffffe000415196)
Location: include/crypto/rng.h:105
Inline: True
Inline callers:
  - crypto/rng.c:crypto_get_default_rng
  - crypto/rng.c:crypto_rng_reset
```
```
In crypto/drbg.c (ffffffe000415ef4)
Location: include/crypto/rng.h:105
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_seed
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
In crypto/aead.c (ffffffff814b9fb6)
Location: include/crypto/rng.h:105
Inline: True
Inline callers:
  - crypto/aead.c:aead_init_geniv
```
```
In crypto/rng.c (ffffffff814cc067)
Location: include/crypto/rng.h:105
Inline: True
Inline callers:
  - crypto/rng.c:crypto_get_default_rng
  - crypto/rng.c:crypto_rng_reset
```
```
In crypto/drbg.c (ffffffff814cde3a)
Location: include/crypto/rng.h:105
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_seed
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
In crypto/aead.c (ffffffff814aa9d6)
Location: include/crypto/rng.h:105
Inline: True
Inline callers:
  - crypto/aead.c:aead_init_geniv
```
```
In crypto/rng.c (ffffffff814bca87)
Location: include/crypto/rng.h:105
Inline: True
Inline callers:
  - crypto/rng.c:crypto_get_default_rng
  - crypto/rng.c:crypto_rng_reset
```
```
In crypto/drbg.c (ffffffff814be85a)
Location: include/crypto/rng.h:105
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_seed
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
In crypto/aead.c (ffffffff814b6046)
Location: include/crypto/rng.h:105
Inline: True
Inline callers:
  - crypto/aead.c:aead_init_geniv
```
```
In crypto/rng.c (ffffffff814c80f7)
Location: include/crypto/rng.h:105
Inline: True
Inline callers:
  - crypto/rng.c:crypto_get_default_rng
  - crypto/rng.c:crypto_rng_reset
```
```
In crypto/drbg.c (ffffffff814c9eca)
Location: include/crypto/rng.h:105
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_seed
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
In crypto/aead.c (ffffffff814ceae6)
Location: include/crypto/rng.h:105
Inline: True
Inline callers:
  - crypto/aead.c:aead_init_geniv
```
```
In crypto/rng.c (ffffffff814e0bc7)
Location: include/crypto/rng.h:105
Inline: True
Inline callers:
  - crypto/rng.c:crypto_get_default_rng
  - crypto/rng.c:crypto_rng_reset
```
```
In crypto/drbg.c (ffffffff814e299a)
Location: include/crypto/rng.h:105
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_seed
```
</details>
</li>
</ul>

## Differences
