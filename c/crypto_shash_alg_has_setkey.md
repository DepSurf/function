# Function: <code>crypto_shash_alg_has_setkey</code>

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
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/ahash.c (ffffffff8142bbc6)
Location: include/crypto/internal/hash.h:88
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_hash_alg_has_setkey
```
```
In crypto/shash.c (0)
Location: include/crypto/internal/hash.h:88
Inline: True
```
```
In crypto/hmac.c (0)
Location: include/crypto/internal/hash.h:88
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
In crypto/ahash.c (ffffffff8145e8d6)
Location: include/crypto/internal/hash.h:88
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_hash_alg_has_setkey
```
```
In crypto/shash.c (ffffffff8145f543)
Location: include/crypto/internal/hash.h:88
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_init_tfm
```
```
In crypto/hmac.c (ffffffff81463828)
Location: include/crypto/internal/hash.h:88
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
In crypto/ahash.c (ffffffff8147c246)
Location: include/crypto/internal/hash.h:88
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_hash_alg_has_setkey
```
```
In crypto/shash.c (ffffffff8147cf73)
Location: include/crypto/internal/hash.h:88
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_init_tfm
  - crypto/shash.c:crypto_init_shash_ops_async
  - crypto/shash.c:crypto_shash_setkey
```
```
In crypto/hmac.c (ffffffff814814a8)
Location: include/crypto/internal/hash.h:88
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
In crypto/ahash.c (ffffffff814aa536)
Location: include/crypto/internal/hash.h:83
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_hash_alg_has_setkey
```
```
In crypto/shash.c (ffffffff814ab263)
Location: include/crypto/internal/hash.h:83
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_init_tfm
  - crypto/shash.c:crypto_init_shash_ops_async
  - crypto/shash.c:crypto_shash_setkey
```
```
In crypto/hmac.c (ffffffff814af691)
Location: include/crypto/internal/hash.h:83
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
In crypto/ahash.c (ffffffff814c51f6)
Location: include/crypto/internal/hash.h:83
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_hash_alg_has_setkey
```
```
In crypto/shash.c (ffffffff814c5f23)
Location: include/crypto/internal/hash.h:83
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_init_tfm
  - crypto/shash.c:crypto_init_shash_ops_async
  - crypto/shash.c:crypto_shash_setkey
```
```
In crypto/hmac.c (ffffffff814ca331)
Location: include/crypto/internal/hash.h:83
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
In crypto/ahash.c (ffffffff81524126)
Location: include/crypto/internal/hash.h:94
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_hash_alg_has_setkey
```
```
In crypto/shash.c (ffffffff81525535)
Location: include/crypto/internal/hash.h:94
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_init_tfm
  - crypto/shash.c:crypto_init_shash_ops_async
  - crypto/shash.c:shash_async_setkey
```
```
In crypto/hmac.c (ffffffff81529323)
Location: include/crypto/internal/hash.h:94
Inline: True
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
In crypto/ahash.c (ffffffff81541126)
Location: include/crypto/internal/hash.h:81
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_hash_alg_has_setkey
```
```
In crypto/shash.c (ffffffff81542465)
Location: include/crypto/internal/hash.h:81
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_init_tfm
  - crypto/shash.c:crypto_init_shash_ops_async
  - crypto/shash.c:shash_async_setkey
```
```
In crypto/hmac.c (ffffffff81546337)
Location: include/crypto/internal/hash.h:81
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_create
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool crypto_shash_alg_has_setkey(struct shash_alg *alg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff8154ab05)
Location: crypto/shash.c:36
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_init_tfm
  - crypto/shash.c:crypto_init_shash_ops_async
  - crypto/shash.c:shash_async_setkey
Direct callers:
  - crypto/ahash.c:crypto_hash_alg_has_setkey
  - crypto/hmac.c:hmac_create
```
**Symbols:**

```
ffffffff8154a330-ffffffff8154a346: crypto_shash_alg_has_setkey (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool crypto_shash_alg_has_setkey(struct shash_alg *alg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff815ab2e5)
Location: crypto/shash.c:36
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_init_tfm
  - crypto/shash.c:crypto_init_shash_ops_async
  - crypto/shash.c:shash_async_setkey
Direct callers:
  - crypto/ahash.c:crypto_hash_alg_has_setkey
  - crypto/hmac.c:hmac_create
```
**Symbols:**

```
ffffffff815aab10-ffffffff815aab26: crypto_shash_alg_has_setkey (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
bool crypto_shash_alg_has_setkey(struct shash_alg *alg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff81652ae1)
Location: crypto/shash.c:36
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_init_tfm
  - crypto/shash.c:crypto_init_shash_ops_async
  - crypto/shash.c:shash_async_setkey
Direct callers:
  - crypto/hmac.c:hmac_create
```
**Symbols:**

```
ffffffff816521c0-ffffffff816521dc: crypto_shash_alg_has_setkey (STB_GLOBAL)
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
In crypto/ahash.c (ffffffff8170ada6)
Location: include/crypto/internal/hash.h:81
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_hash_alg_has_setkey
```
```
In crypto/shash.c (ffffffff8170c721)
Location: include/crypto/internal/hash.h:81
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_init_tfm
  - crypto/shash.c:crypto_init_shash_ops_async
  - crypto/shash.c:shash_async_setkey
```
```
In crypto/hmac.c (ffffffff81711cb2)
Location: include/crypto/internal/hash.h:81
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_create
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
In crypto/ahash.c (ffffffff81744c94)
Location: include/crypto/internal/hash.h:81
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_clone_ahash
```
```
In crypto/shash.c (ffffffff81746109)
Location: include/crypto/internal/hash.h:81
Inline: True
Inline callers:
  - crypto/shash.c:crypto_clone_shash
  - crypto/shash.c:crypto_shash_init_tfm
  - crypto/shash.c:crypto_init_shash_ops_async
  - crypto/shash.c:shash_async_setkey
```
```
In crypto/hmac.c (ffffffff8174c875)
Location: include/crypto/internal/hash.h:81
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_create
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
In crypto/ahash.c (ffffffff8178751d)
Location: include/crypto/internal/hash.h:79
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_clone_ahash
```
```
In crypto/shash.c (ffffffff81788749)
Location: include/crypto/internal/hash.h:79
Inline: True
Inline callers:
  - crypto/shash.c:crypto_clone_shash
  - crypto/shash.c:crypto_shash_init_tfm
  - crypto/shash.c:crypto_shash_setkey
```
```
In crypto/hmac.c (ffffffff8178e944)
Location: include/crypto/internal/hash.h:79
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_create
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
In crypto/ahash.c (ffff8000105bfda0)
Location: include/crypto/internal/hash.h:83
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_hash_alg_has_setkey
```
```
In crypto/shash.c (ffff8000105c0f20)
Location: include/crypto/internal/hash.h:83
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_init_tfm
  - crypto/shash.c:crypto_init_shash_ops_async
  - crypto/shash.c:crypto_shash_setkey
```
```
In crypto/hmac.c (ffff8000105c6058)
Location: include/crypto/internal/hash.h:83
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
In crypto/ahash.c (c076d9d4)
Location: include/crypto/internal/hash.h:83
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_hash_alg_has_setkey
```
```
In crypto/shash.c (c076e84c)
Location: include/crypto/internal/hash.h:83
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_init_tfm
  - crypto/shash.c:crypto_init_shash_ops_async
  - crypto/shash.c:crypto_shash_setkey
```
```
In crypto/hmac.c (c0772d48)
Location: include/crypto/internal/hash.h:83
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
In crypto/ahash.c (c000000000747c34)
Location: include/crypto/internal/hash.h:83
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_hash_alg_has_setkey
```
```
In crypto/shash.c (c000000000749284)
Location: include/crypto/internal/hash.h:83
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_init_tfm
  - crypto/shash.c:crypto_init_shash_ops_async
  - crypto/shash.c:crypto_shash_setkey
```
```
In crypto/hmac.c (c00000000074fb14)
Location: include/crypto/internal/hash.h:83
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
In crypto/ahash.c (ffffffe000404df4)
Location: include/crypto/internal/hash.h:83
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_hash_alg_has_setkey
```
```
In crypto/shash.c (0)
Location: include/crypto/internal/hash.h:83
Inline: True
```
```
In crypto/hmac.c (0)
Location: include/crypto/internal/hash.h:83
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
In crypto/ahash.c (ffffffff814bd7d6)
Location: include/crypto/internal/hash.h:83
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_hash_alg_has_setkey
```
```
In crypto/shash.c (ffffffff814be503)
Location: include/crypto/internal/hash.h:83
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_init_tfm
  - crypto/shash.c:crypto_init_shash_ops_async
  - crypto/shash.c:crypto_shash_setkey
```
```
In crypto/hmac.c (ffffffff814c2911)
Location: include/crypto/internal/hash.h:83
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
In crypto/ahash.c (ffffffff814ae1f6)
Location: include/crypto/internal/hash.h:83
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_hash_alg_has_setkey
```
```
In crypto/shash.c (ffffffff814aef23)
Location: include/crypto/internal/hash.h:83
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_init_tfm
  - crypto/shash.c:crypto_init_shash_ops_async
  - crypto/shash.c:crypto_shash_setkey
```
```
In crypto/hmac.c (ffffffff814b3331)
Location: include/crypto/internal/hash.h:83
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
In crypto/ahash.c (ffffffff814b9866)
Location: include/crypto/internal/hash.h:83
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_hash_alg_has_setkey
```
```
In crypto/shash.c (ffffffff814ba593)
Location: include/crypto/internal/hash.h:83
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_init_tfm
  - crypto/shash.c:crypto_init_shash_ops_async
  - crypto/shash.c:crypto_shash_setkey
```
```
In crypto/hmac.c (ffffffff814be9a1)
Location: include/crypto/internal/hash.h:83
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
In crypto/ahash.c (ffffffff814d2406)
Location: include/crypto/internal/hash.h:83
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_hash_alg_has_setkey
```
```
In crypto/shash.c (ffffffff814d3043)
Location: include/crypto/internal/hash.h:83
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_init_tfm
  - crypto/shash.c:crypto_init_shash_ops_async
  - crypto/shash.c:crypto_shash_setkey
```
```
In crypto/hmac.c (ffffffff814d7471)
Location: include/crypto/internal/hash.h:83
Inline: True
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
</ul>
