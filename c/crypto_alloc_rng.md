# Function: <code>crypto_alloc_rng</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct crypto_rng *crypto_alloc_rng(const char *alg_name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/rng.c (ffffffff813abb10)
Location: crypto/rng.c:118
Inline: True
Inline callers:
  - crypto/rng.c:crypto_get_default_rng
```
**Symbols:**

```
ffffffff813abb10-ffffffff813abb2b: crypto_alloc_rng (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct crypto_rng *crypto_alloc_rng(const char *alg_name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/rng.c (ffffffff813eb4ce)
Location: crypto/rng.c:118
Inline: True
Inline callers:
  - crypto/rng.c:crypto_get_default_rng
Direct callers:
  - security/keys/big_key.c:big_key_crypto_init
  - crypto/drbg.c:drbg_kcapi_seed
```
**Symbols:**

```
ffffffff813eb360-ffffffff813eb37b: crypto_alloc_rng (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct crypto_rng *crypto_alloc_rng(const char *alg_name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/rng.c (ffffffff81404c1e)
Location: crypto/rng.c:118
Inline: True
Inline callers:
  - crypto/rng.c:crypto_get_default_rng
Direct callers:
  - security/keys/big_key.c:big_key_init
  - crypto/drbg.c:drbg_kcapi_seed
```
**Symbols:**

```
ffffffff81404ab0-ffffffff81404acb: crypto_alloc_rng (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct crypto_rng *crypto_alloc_rng(const char *alg_name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/rng.c (ffffffff8141237e)
Location: crypto/rng.c:114
Inline: True
Inline callers:
  - crypto/rng.c:crypto_get_default_rng
Direct callers:
  - security/keys/big_key.c:big_key_init
  - crypto/drbg.c:drbg_kcapi_seed
```
**Symbols:**

```
ffffffff81412210-ffffffff8141222b: crypto_alloc_rng (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct crypto_rng *crypto_alloc_rng(const char *alg_name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/rng.c (ffffffff8143cb0e)
Location: crypto/rng.c:116
Inline: True
Inline callers:
  - crypto/rng.c:crypto_get_default_rng
Direct callers:
  - crypto/drbg.c:drbg_kcapi_seed
```
**Symbols:**

```
ffffffff8143c9a0-ffffffff8143c9bb: crypto_alloc_rng (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct crypto_rng *crypto_alloc_rng(const char *alg_name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/rng.c (ffffffff8146f93e)
Location: crypto/rng.c:116
Inline: True
Inline callers:
  - crypto/rng.c:crypto_get_default_rng
Direct callers:
  - crypto/drbg.c:drbg_kcapi_seed
```
**Symbols:**

```
ffffffff8146f7d0-ffffffff8146f7eb: crypto_alloc_rng (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct crypto_rng *crypto_alloc_rng(const char *alg_name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/rng.c (ffffffff8148d31e)
Location: crypto/rng.c:115
Inline: True
Inline callers:
  - crypto/rng.c:crypto_get_default_rng
Direct callers:
  - crypto/drbg.c:drbg_kcapi_seed
```
**Symbols:**

```
ffffffff8148d1b0-ffffffff8148d1cb: crypto_alloc_rng (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct crypto_rng *crypto_alloc_rng(const char *alg_name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/rng.c (ffffffff814bac92)
Location: crypto/rng.c:110
Inline: True
Inline callers:
  - crypto/rng.c:crypto_get_default_rng
Direct callers:
  - crypto/drbg.c:drbg_kcapi_seed
```
**Symbols:**

```
ffffffff814bab20-ffffffff814bab3b: crypto_alloc_rng (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct crypto_rng *crypto_alloc_rng(const char *alg_name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/rng.c (ffffffff814d3a62)
Location: crypto/rng.c:110
Inline: True
Inline callers:
  - crypto/rng.c:crypto_get_default_rng
Direct callers:
  - crypto/drbg.c:drbg_kcapi_seed
```
**Symbols:**

```
ffffffff814d38f0-ffffffff814d390b: crypto_alloc_rng (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct crypto_rng *crypto_alloc_rng(const char *alg_name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/rng.c (ffffffff81532fa2)
Location: crypto/rng.c:114
Inline: True
Inline callers:
  - crypto/rng.c:crypto_get_default_rng
Direct callers:
  - crypto/drbg.c:drbg_instantiate
```
**Symbols:**

```
ffffffff81532b10-ffffffff81532b2b: crypto_alloc_rng (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct crypto_rng *crypto_alloc_rng(const char *alg_name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/rng.c (ffffffff8154ff12)
Location: crypto/rng.c:114
Inline: True
Inline callers:
  - crypto/rng.c:crypto_get_default_rng
Direct callers:
  - crypto/drbg.c:drbg_instantiate
```
**Symbols:**

```
ffffffff8154fb50-ffffffff8154fb71: crypto_alloc_rng (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct crypto_rng *crypto_alloc_rng(const char *alg_name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/rng.c (ffffffff81558542)
Location: crypto/rng.c:110
Inline: True
Inline callers:
  - crypto/rng.c:crypto_get_default_rng
Direct callers:
  - crypto/drbg.c:drbg_kcapi_seed
```
**Symbols:**

```
ffffffff815584a0-ffffffff815584c1: crypto_alloc_rng (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct crypto_rng *crypto_alloc_rng(const char *alg_name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/rng.c (ffffffff815b97f2)
Location: crypto/rng.c:110
Inline: True
Inline callers:
  - crypto/rng.c:crypto_get_default_rng
Direct callers:
  - crypto/drbg.c:drbg_kcapi_seed
```
**Symbols:**

```
ffffffff815b9750-ffffffff815b9771: crypto_alloc_rng (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct crypto_rng *crypto_alloc_rng(const char *alg_name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/rng.c (ffffffff81662d6d)
Location: crypto/rng.c:110
Inline: True
Inline callers:
  - crypto/rng.c:crypto_get_default_rng
Direct callers:
  - crypto/drbg.c:drbg_kcapi_seed
```
**Symbols:**

```
ffffffff81662cc0-ffffffff81662cf0: crypto_alloc_rng (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct crypto_rng *crypto_alloc_rng(const char *alg_name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/rng.c (ffffffff8171cf4d)
Location: crypto/rng.c:110
Inline: True
Inline callers:
  - crypto/rng.c:crypto_get_default_rng
Direct callers:
  - crypto/drbg.c:drbg_kcapi_seed
```
**Symbols:**

```
ffffffff8171ce80-ffffffff8171ceb0: crypto_alloc_rng (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct crypto_rng *crypto_alloc_rng(const char *alg_name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/rng.c (ffffffff8175879d)
Location: crypto/rng.c:133
Inline: True
Inline callers:
  - crypto/rng.c:crypto_get_default_rng
Direct callers:
  - crypto/drbg.c:drbg_kcapi_seed
```
**Symbols:**

```
ffffffff817586d0-ffffffff81758700: crypto_alloc_rng (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct crypto_rng *crypto_alloc_rng(const char *alg_name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/rng.c (ffffffff8179a69d)
Location: crypto/rng.c:133
Inline: True
Inline callers:
  - crypto/rng.c:crypto_get_default_rng
Direct callers:
  - crypto/drbg.c:drbg_kcapi_seed
```
**Symbols:**

```
ffffffff8179a5d0-ffffffff8179a600: crypto_alloc_rng (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
struct crypto_rng *crypto_alloc_rng(const char *alg_name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/rng.c (ffff8000105d0494)
Location: crypto/rng.c:110
Inline: True
Inline callers:
  - crypto/rng.c:crypto_get_default_rng
Direct callers:
  - crypto/drbg.c:drbg_kcapi_seed
```
**Symbols:**

```
ffff8000105d02a8-ffff8000105d02f4: crypto_alloc_rng (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct crypto_rng *crypto_alloc_rng(const char *alg_name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/rng.c (c077ded0)
Location: crypto/rng.c:110
Inline: True
Inline callers:
  - crypto/rng.c:crypto_get_default_rng
Direct callers:
  - crypto/drbg.c:drbg_kcapi_seed
```
**Symbols:**

```
c077dd30-c077dd5c: crypto_alloc_rng (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct crypto_rng *crypto_alloc_rng(const char *alg_name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/rng.c (c00000000075c6e0)
Location: crypto/rng.c:110
Inline: True
Inline callers:
  - crypto/rng.c:crypto_get_default_rng
Direct callers:
  - crypto/drbg.c:drbg_kcapi_seed
```
**Symbols:**

```
c00000000075c460-c00000000075c4a8: crypto_alloc_rng (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct crypto_rng *crypto_alloc_rng(const char *alg_name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/rng.c (ffffffe00041516e)
Location: crypto/rng.c:110
Inline: True
Inline callers:
  - crypto/rng.c:crypto_get_default_rng
Direct callers:
  - crypto/drbg.c:drbg_kcapi_seed
```
**Symbols:**

```
ffffffe000414fb2-ffffffe000414ff4: crypto_alloc_rng (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
struct crypto_rng *crypto_alloc_rng(const char *alg_name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/rng.c (ffffffff814cc042)
Location: crypto/rng.c:110
Inline: True
Inline callers:
  - crypto/rng.c:crypto_get_default_rng
Direct callers:
  - crypto/drbg.c:drbg_kcapi_seed
```
**Symbols:**

```
ffffffff814cbed0-ffffffff814cbeeb: crypto_alloc_rng (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct crypto_rng *crypto_alloc_rng(const char *alg_name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/rng.c (ffffffff814bca62)
Location: crypto/rng.c:110
Inline: True
Inline callers:
  - crypto/rng.c:crypto_get_default_rng
Direct callers:
  - crypto/drbg.c:drbg_kcapi_seed
```
**Symbols:**

```
ffffffff814bc8f0-ffffffff814bc90b: crypto_alloc_rng (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct crypto_rng *crypto_alloc_rng(const char *alg_name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/rng.c (ffffffff814c80d2)
Location: crypto/rng.c:110
Inline: True
Inline callers:
  - crypto/rng.c:crypto_get_default_rng
Direct callers:
  - crypto/drbg.c:drbg_kcapi_seed
```
**Symbols:**

```
ffffffff814c7f60-ffffffff814c7f7b: crypto_alloc_rng (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct crypto_rng *crypto_alloc_rng(const char *alg_name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/rng.c (ffffffff814e0ba2)
Location: crypto/rng.c:110
Inline: True
Inline callers:
  - crypto/rng.c:crypto_get_default_rng
Direct callers:
  - crypto/drbg.c:drbg_kcapi_seed
```
**Symbols:**

```
ffffffff814e0a30-ffffffff814e0a4b: crypto_alloc_rng (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
