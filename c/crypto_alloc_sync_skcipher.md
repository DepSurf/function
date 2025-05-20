# Function: <code>crypto_alloc_sync_skcipher</code>

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
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct crypto_sync_skcipher *crypto_alloc_sync_skcipher(const char *alg_name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff8147af40)
Location: crypto/skcipher.c:958
Inline: False
Direct callers:
  - crypto/crypto_null.c:crypto_get_default_null_skcipher
```
**Symbols:**

```
ffffffff8147af40-ffffffff8147af86: crypto_alloc_sync_skcipher (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct crypto_sync_skcipher *crypto_alloc_sync_skcipher(const char *alg_name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/skcipher.c (0)
Location: crypto/skcipher.c:992
Inline: False
Direct callers:
  - crypto/crypto_null.c:crypto_get_default_null_skcipher
```
**Symbols:**

```
ffffffff814aa0b0-ffffffff814aa0d7: crypto_alloc_sync_skcipher.cold (STB_LOCAL)
ffffffff814a8fa0-ffffffff814a8fdd: crypto_alloc_sync_skcipher (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct crypto_sync_skcipher *crypto_alloc_sync_skcipher(const char *alg_name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff814c3c00)
Location: crypto/skcipher.c:996
Inline: False
Direct callers:
  - crypto/crypto_null.c:crypto_get_default_null_skcipher
```
**Symbols:**

```
ffffffff814c3c00-ffffffff814c3c46: crypto_alloc_sync_skcipher (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct crypto_sync_skcipher *crypto_alloc_sync_skcipher(const char *alg_name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff81522bd0)
Location: crypto/skcipher.c:765
Inline: False
Direct callers:
  - crypto/crypto_null.c:crypto_get_default_null_skcipher
```
**Symbols:**

```
ffffffff81522bd0-ffffffff81522c15: crypto_alloc_sync_skcipher (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct crypto_sync_skcipher *crypto_alloc_sync_skcipher(const char *alg_name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff8153fb20)
Location: crypto/skcipher.c:765
Inline: False
Direct callers:
  - crypto/crypto_null.c:crypto_get_default_null_skcipher
```
**Symbols:**

```
ffffffff8153fb20-ffffffff8153fb6b: crypto_alloc_sync_skcipher (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct crypto_sync_skcipher *crypto_alloc_sync_skcipher(const char *alg_name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff81548090)
Location: crypto/skcipher.c:760
Inline: False
Direct callers:
  - crypto/crypto_null.c:crypto_get_default_null_skcipher
```
**Symbols:**

```
ffffffff81548090-ffffffff815480db: crypto_alloc_sync_skcipher (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct crypto_sync_skcipher *crypto_alloc_sync_skcipher(const char *alg_name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff815a8870)
Location: crypto/skcipher.c:760
Inline: False
Direct callers:
  - crypto/crypto_null.c:crypto_get_default_null_skcipher
```
**Symbols:**

```
ffffffff815a8870-ffffffff815a88bb: crypto_alloc_sync_skcipher (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct crypto_sync_skcipher *crypto_alloc_sync_skcipher(const char *alg_name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff8164fbf0)
Location: crypto/skcipher.c:760
Inline: False
Direct callers:
  - crypto/crypto_null.c:crypto_get_default_null_skcipher
```
**Symbols:**

```
ffffffff8164fbf0-ffffffff8164fc59: crypto_alloc_sync_skcipher (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct crypto_sync_skcipher *crypto_alloc_sync_skcipher(const char *alg_name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff81709060)
Location: crypto/skcipher.c:760
Inline: False
Direct callers:
  - crypto/crypto_null.c:crypto_get_default_null_skcipher
```
**Symbols:**

```
ffffffff81709060-ffffffff817090cc: crypto_alloc_sync_skcipher (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct crypto_sync_skcipher *crypto_alloc_sync_skcipher(const char *alg_name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff817428b0)
Location: crypto/skcipher.c:807
Inline: False
Direct callers:
  - crypto/crypto_null.c:crypto_get_default_null_skcipher
```
**Symbols:**

```
ffffffff817428b0-ffffffff8174291c: crypto_alloc_sync_skcipher (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct crypto_sync_skcipher *crypto_alloc_sync_skcipher(const char *alg_name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff81784ba0)
Location: crypto/skcipher.c:906
Inline: False
Direct callers:
  - crypto/crypto_null.c:crypto_get_default_null_skcipher
```
**Symbols:**

```
ffffffff81784ba0-ffffffff81784c0c: crypto_alloc_sync_skcipher (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
struct crypto_sync_skcipher *crypto_alloc_sync_skcipher(const char *alg_name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffff8000105be5f0)
Location: crypto/skcipher.c:996
Inline: False
Direct callers:
  - crypto/crypto_null.c:crypto_get_default_null_skcipher
```
**Symbols:**

```
ffff8000105be5f0-ffff8000105be66c: crypto_alloc_sync_skcipher (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct crypto_sync_skcipher *crypto_alloc_sync_skcipher(const char *alg_name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (c076c320)
Location: crypto/skcipher.c:996
Inline: False
Direct callers:
  - crypto/crypto_null.c:crypto_get_default_null_skcipher
```
**Symbols:**

```
c076c320-c076c398: crypto_alloc_sync_skcipher (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct crypto_sync_skcipher *crypto_alloc_sync_skcipher(const char *alg_name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (c000000000745de0)
Location: crypto/skcipher.c:996
Inline: False
Direct callers:
  - crypto/crypto_null.c:crypto_get_default_null_skcipher
```
**Symbols:**

```
c000000000745de0-c000000000745e6c: crypto_alloc_sync_skcipher (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct crypto_sync_skcipher *crypto_alloc_sync_skcipher(const char *alg_name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffe0004039f6)
Location: crypto/skcipher.c:996
Inline: False
Direct callers:
  - crypto/crypto_null.c:crypto_get_default_null_skcipher
```
**Symbols:**

```
ffffffe0004039f6-ffffffe000403a60: crypto_alloc_sync_skcipher (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
struct crypto_sync_skcipher *crypto_alloc_sync_skcipher(const char *alg_name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff814bc1e0)
Location: crypto/skcipher.c:996
Inline: False
Direct callers:
  - crypto/crypto_null.c:crypto_get_default_null_skcipher
```
**Symbols:**

```
ffffffff814bc1e0-ffffffff814bc226: crypto_alloc_sync_skcipher (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct crypto_sync_skcipher *crypto_alloc_sync_skcipher(const char *alg_name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff814acc00)
Location: crypto/skcipher.c:996
Inline: False
Direct callers:
  - crypto/crypto_null.c:crypto_get_default_null_skcipher
```
**Symbols:**

```
ffffffff814acc00-ffffffff814acc46: crypto_alloc_sync_skcipher (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct crypto_sync_skcipher *crypto_alloc_sync_skcipher(const char *alg_name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff814b8270)
Location: crypto/skcipher.c:996
Inline: False
Direct callers:
  - crypto/crypto_null.c:crypto_get_default_null_skcipher
```
**Symbols:**

```
ffffffff814b8270-ffffffff814b82b6: crypto_alloc_sync_skcipher (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct crypto_sync_skcipher *crypto_alloc_sync_skcipher(const char *alg_name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff814d0d50)
Location: crypto/skcipher.c:996
Inline: False
Direct callers:
  - crypto/crypto_null.c:crypto_get_default_null_skcipher
```
**Symbols:**

```
ffffffff814d0d50-ffffffff814d0d96: crypto_alloc_sync_skcipher (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
