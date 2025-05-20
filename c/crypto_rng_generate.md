# Function: <code>crypto_rng_generate</code>

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
In crypto/aead.c (ffffffff8139f0fd)
Location: include/crypto/rng.h:139
Inline: True
Inline callers:
  - crypto/aead.c:aead_init_geniv
```
```
In crypto/chainiv.c (ffffffff813a1fd2)
Location: include/crypto/rng.h:139
Inline: True
Inline callers:
  - crypto/chainiv.c:chainiv_init_common
```
```
In crypto/eseqiv.c (ffffffff813a23df)
Location: include/crypto/rng.h:139
Inline: True
Inline callers:
  - crypto/eseqiv.c:eseqiv_init
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
In security/keys/big_key.c (ffffffff8136b99e)
Location: include/crypto/rng.h:139
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_preparse
```
```
In crypto/aead.c (ffffffff813dbe99)
Location: include/crypto/rng.h:139
Inline: True
Inline callers:
  - crypto/aead.c:aead_init_geniv
```
```
In crypto/drbg.c (ffffffff813ebbf6)
Location: include/crypto/rng.h:139
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_seed
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
In security/keys/big_key.c (ffffffff813821be)
Location: include/crypto/rng.h:139
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_preparse
```
```
In crypto/aead.c (ffffffff813f3779)
Location: include/crypto/rng.h:139
Inline: True
Inline callers:
  - crypto/aead.c:aead_init_geniv
```
```
In crypto/drbg.c (ffffffff81405436)
Location: include/crypto/rng.h:139
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_seed
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
In security/keys/big_key.c (ffffffff81396860)
Location: include/crypto/rng.h:139
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_preparse
```
```
In crypto/aead.c (ffffffff813ffa8f)
Location: include/crypto/rng.h:139
Inline: True
Inline callers:
  - crypto/aead.c:aead_init_geniv
```
```
In crypto/drbg.c (ffffffff81412bc8)
Location: include/crypto/rng.h:139
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_seed
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
In crypto/aead.c (ffffffff81428083)
Location: include/crypto/rng.h:139
Inline: True
Inline callers:
  - crypto/aead.c:aead_init_geniv
```
```
In crypto/drbg.c (ffffffff8143d358)
Location: include/crypto/rng.h:139
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_seed
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
Location: include/crypto/rng.h:139
Inline: True
Inline callers:
  - crypto/aead.c:aead_init_geniv
```
```
In crypto/drbg.c (ffffffff81470193)
Location: include/crypto/rng.h:139
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
In crypto/aead.c (ffffffff81478e3c)
Location: include/crypto/rng.h:139
Inline: True
Inline callers:
  - crypto/aead.c:aead_init_geniv
```
```
In crypto/drbg.c (ffffffff8148f284)
Location: include/crypto/rng.h:139
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
In crypto/aead.c (ffffffff814a6d5e)
Location: include/crypto/rng.h:134
Inline: True
Inline callers:
  - crypto/aead.c:aead_init_geniv
```
```
In crypto/drbg.c (ffffffff814bcbb1)
Location: include/crypto/rng.h:134
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
In crypto/aead.c (ffffffff814c19ce)
Location: include/crypto/rng.h:134
Inline: True
Inline callers:
  - crypto/aead.c:aead_init_geniv
```
```
In crypto/drbg.c (ffffffff814d5844)
Location: include/crypto/rng.h:134
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
In crypto/geniv.c (ffffffff81522301)
Location: include/crypto/rng.h:134
Inline: True
Inline callers:
  - crypto/geniv.c:aead_init_geniv
```
```
In crypto/drbg.c (ffffffff8153325f)
Location: include/crypto/rng.h:134
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
In crypto/geniv.c (ffffffff8153f1ee)
Location: include/crypto/rng.h:134
Inline: True
Inline callers:
  - crypto/geniv.c:aead_init_geniv
```
```
In crypto/drbg.c (ffffffff815501af)
Location: include/crypto/rng.h:134
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
In crypto/geniv.c (ffffffff8154786e)
Location: include/crypto/rng.h:136
Inline: True
Inline callers:
  - crypto/geniv.c:aead_init_geniv
```
```
In crypto/drbg.c (ffffffff8155899f)
Location: include/crypto/rng.h:136
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
In crypto/geniv.c (ffffffff815a804e)
Location: include/crypto/rng.h:136
Inline: True
Inline callers:
  - crypto/geniv.c:aead_init_geniv
```
```
In crypto/drbg.c (ffffffff815b9c4f)
Location: include/crypto/rng.h:136
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
In crypto/geniv.c (ffffffff8164f3fb)
Location: include/crypto/rng.h:136
Inline: True
Inline callers:
  - crypto/geniv.c:aead_init_geniv
```
```
In crypto/dh.c (ffffffff816542bf)
Location: include/crypto/rng.h:136
Inline: True
```
```
In crypto/drbg.c (ffffffff816637ab)
Location: include/crypto/rng.h:136
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
In crypto/geniv.c (ffffffff817089fb)
Location: include/crypto/rng.h:136
Inline: True
Inline callers:
  - crypto/geniv.c:aead_init_geniv
```
```
In crypto/dh.c (ffffffff8170e28f)
Location: include/crypto/rng.h:136
Inline: True
```
```
In crypto/drbg.c (ffffffff8171daab)
Location: include/crypto/rng.h:136
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
Location: include/crypto/rng.h:181
Inline: True
Inline callers:
  - crypto/geniv.c:aead_init_geniv
```
```
In crypto/dh.c (ffffffff81748b37)
Location: include/crypto/rng.h:181
Inline: True
```
```
In crypto/drbg.c (ffffffff817593be)
Location: include/crypto/rng.h:181
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
Location: include/crypto/rng.h:181
Inline: True
Inline callers:
  - crypto/geniv.c:aead_init_geniv
```
```
In crypto/dh.c (ffffffff8178a9d7)
Location: include/crypto/rng.h:181
Inline: True
```
```
In crypto/drbg.c (ffffffff8179b2be)
Location: include/crypto/rng.h:181
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
In crypto/aead.c (ffff8000105bc0d0)
Location: include/crypto/rng.h:134
Inline: True
Inline callers:
  - crypto/aead.c:aead_init_geniv
```
```
In crypto/drbg.c (ffff8000105d10e4)
Location: include/crypto/rng.h:134
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
In crypto/aead.c (c076a12c)
Location: include/crypto/rng.h:134
Inline: True
Inline callers:
  - crypto/aead.c:aead_init_geniv
```
```
In crypto/drbg.c (c077f154)
Location: include/crypto/rng.h:134
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
In crypto/aead.c (c000000000742a34)
Location: include/crypto/rng.h:134
Inline: True
Inline callers:
  - crypto/aead.c:aead_init_geniv
```
```
In crypto/drbg.c (c00000000075e42c)
Location: include/crypto/rng.h:134
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
In crypto/aead.c (ffffffe00040184c)
Location: include/crypto/rng.h:134
Inline: True
Inline callers:
  - crypto/aead.c:aead_init_geniv
```
```
In crypto/drbg.c (ffffffe000415ee6)
Location: include/crypto/rng.h:134
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
In crypto/aead.c (ffffffff814b9fae)
Location: include/crypto/rng.h:134
Inline: True
Inline callers:
  - crypto/aead.c:aead_init_geniv
```
```
In crypto/drbg.c (ffffffff814cde24)
Location: include/crypto/rng.h:134
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
In crypto/aead.c (ffffffff814aa9ce)
Location: include/crypto/rng.h:134
Inline: True
Inline callers:
  - crypto/aead.c:aead_init_geniv
```
```
In crypto/drbg.c (ffffffff814be844)
Location: include/crypto/rng.h:134
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
In crypto/aead.c (ffffffff814b603e)
Location: include/crypto/rng.h:134
Inline: True
Inline callers:
  - crypto/aead.c:aead_init_geniv
```
```
In crypto/drbg.c (ffffffff814c9eb4)
Location: include/crypto/rng.h:134
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
In crypto/aead.c (ffffffff814ceade)
Location: include/crypto/rng.h:134
Inline: True
Inline callers:
  - crypto/aead.c:aead_init_geniv
```
```
In crypto/drbg.c (ffffffff814e2984)
Location: include/crypto/rng.h:134
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_seed
```
</details>
</li>
</ul>

## Differences
