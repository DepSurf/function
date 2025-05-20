# Function: <code>crypto_unregister_shashes</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int crypto_unregister_shashes(struct shash_alg *algs, int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff813a3e80)
Location: crypto/shash.c:650
Inline: False
Direct callers:
  - crypto/sha256_generic.c:sha256_generic_mod_fini
  - crypto/sha512_generic.c:sha512_generic_mod_fini
```
**Symbols:**

```
ffffffff813a3e80-ffffffff813a3ee7: crypto_unregister_shashes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int crypto_unregister_shashes(struct shash_alg *algs, int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff813dfd40)
Location: crypto/shash.c:503
Inline: False
Direct callers:
  - crypto/sha256_generic.c:sha256_generic_mod_fini
  - crypto/sha512_generic.c:sha512_generic_mod_fini
```
**Symbols:**

```
ffffffff813dfd40-ffffffff813dfdae: crypto_unregister_shashes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int crypto_unregister_shashes(struct shash_alg *algs, int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff813f82d0)
Location: crypto/shash.c:503
Inline: False
Direct callers:
  - crypto/sha256_generic.c:sha256_generic_mod_fini
  - crypto/sha512_generic.c:sha512_generic_mod_fini
```
**Symbols:**

```
ffffffff813f82d0-ffffffff813f833e: crypto_unregister_shashes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int crypto_unregister_shashes(struct shash_alg *algs, int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff814047d0)
Location: crypto/shash.c:504
Inline: False
Direct callers:
  - crypto/sha256_generic.c:sha256_generic_mod_fini
  - crypto/sha512_generic.c:sha512_generic_mod_fini
```
**Symbols:**

```
ffffffff814047d0-ffffffff81404856: crypto_unregister_shashes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int crypto_unregister_shashes(struct shash_alg *algs, int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff8142d0d0)
Location: crypto/shash.c:524
Inline: False
Direct callers:
  - crypto/sha256_generic.c:sha256_generic_mod_fini
  - crypto/sha512_generic.c:sha512_generic_mod_fini
```
**Symbols:**

```
ffffffff8142d0d0-ffffffff8142d156: crypto_unregister_shashes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int crypto_unregister_shashes(struct shash_alg *algs, int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/shash.c (0)
Location: crypto/shash.c:524
Inline: False
Direct callers:
  - crypto/sha256_generic.c:sha256_generic_mod_fini
  - crypto/sha512_generic.c:sha512_generic_mod_fini
```
**Symbols:**

```
ffffffff81460136-ffffffff81460150: crypto_unregister_shashes.cold.6 (STB_LOCAL)
ffffffff8145fd40-ffffffff8145fdb3: crypto_unregister_shashes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int crypto_unregister_shashes(struct shash_alg *algs, int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/shash.c (0)
Location: crypto/shash.c:533
Inline: False
Direct callers:
  - crypto/sha256_generic.c:sha256_generic_mod_fini
  - crypto/sha512_generic.c:sha512_generic_mod_fini
```
**Symbols:**

```
ffffffff8147dba5-ffffffff8147dbbf: crypto_unregister_shashes.cold.6 (STB_LOCAL)
ffffffff8147d7a0-ffffffff8147d813: crypto_unregister_shashes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int crypto_unregister_shashes(struct shash_alg *algs, int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/shash.c (0)
Location: crypto/shash.c:524
Inline: False
Direct callers:
  - crypto/sha256_generic.c:sha256_generic_mod_fini
  - crypto/sha512_generic.c:sha512_generic_mod_fini
```
**Symbols:**

```
ffffffff814abe59-ffffffff814abe77: crypto_unregister_shashes.cold (STB_LOCAL)
ffffffff814aba90-ffffffff814abaf8: crypto_unregister_shashes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int crypto_unregister_shashes(struct shash_alg *algs, int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/shash.c (0)
Location: crypto/shash.c:524
Inline: False
Direct callers:
  - crypto/sha256_generic.c:sha256_generic_mod_fini
  - crypto/sha512_generic.c:sha512_generic_mod_fini
```
**Symbols:**

```
ffffffff814c6b07-ffffffff814c6b25: crypto_unregister_shashes.cold (STB_LOCAL)
ffffffff814c6770-ffffffff814c67d8: crypto_unregister_shashes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void crypto_unregister_shashes(struct shash_alg *algs, int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff81525450)
Location: crypto/shash.c:582
Inline: False
Direct callers:
  - crypto/sha256_generic.c:sha256_generic_mod_fini
  - crypto/sha512_generic.c:sha512_generic_mod_fini
```
**Symbols:**

```
ffffffff81525450-ffffffff8152548f: crypto_unregister_shashes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void crypto_unregister_shashes(struct shash_alg *algs, int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff81542380)
Location: crypto/shash.c:582
Inline: False
Direct callers:
  - crypto/sha256_generic.c:sha256_generic_mod_fini
  - crypto/sha512_generic.c:sha512_generic_mod_fini
```
**Symbols:**

```
ffffffff81542380-ffffffff815423bf: crypto_unregister_shashes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void crypto_unregister_shashes(struct shash_alg *algs, int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff8154aa20)
Location: crypto/shash.c:594
Inline: False
Direct callers:
  - crypto/sha256_generic.c:sha256_generic_mod_fini
  - crypto/sha512_generic.c:sha512_generic_mod_fini
```
**Symbols:**

```
ffffffff8154aa20-ffffffff8154aa5f: crypto_unregister_shashes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void crypto_unregister_shashes(struct shash_alg *algs, int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff815ab200)
Location: crypto/shash.c:594
Inline: False
Direct callers:
  - crypto/sha256_generic.c:sha256_generic_mod_fini
  - crypto/sha512_generic.c:sha512_generic_mod_fini
```
**Symbols:**

```
ffffffff815ab200-ffffffff815ab23f: crypto_unregister_shashes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void crypto_unregister_shashes(struct shash_alg *algs, int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff81652970)
Location: crypto/shash.c:594
Inline: False
Direct callers:
  - crypto/sha256_generic.c:sha256_generic_mod_fini
  - crypto/sha512_generic.c:sha512_generic_mod_fini
```
**Symbols:**

```
ffffffff81652970-ffffffff816529c3: crypto_unregister_shashes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void crypto_unregister_shashes(struct shash_alg *algs, int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff8170c150)
Location: crypto/shash.c:593
Inline: False
Direct callers:
  - crypto/sha256_generic.c:sha256_generic_mod_fini
  - crypto/sha512_generic.c:sha512_generic_mod_fini
```
**Symbols:**

```
ffffffff8170c150-ffffffff8170c1a3: crypto_unregister_shashes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void crypto_unregister_shashes(struct shash_alg *algs, int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff81745b10)
Location: crypto/shash.c:712
Inline: False
Direct callers:
  - arch/x86/crypto/sha512_ssse3_glue.c:sha512_ssse3_mod_fini
  - arch/x86/crypto/sha512_ssse3_glue.c:sha512_ssse3_mod_fini
  - arch/x86/crypto/sha512_ssse3_glue.c:sha512_ssse3_mod_fini
  - arch/x86/crypto/sha512_ssse3_glue.c:sha512_ssse3_mod_init
  - arch/x86/crypto/sha512_ssse3_glue.c:sha512_ssse3_mod_init
  - crypto/sha256_generic.c:sha256_generic_mod_fini
  - crypto/sha512_generic.c:sha512_generic_mod_fini
  - crypto/sha3_generic.c:sha3_generic_mod_fini
```
**Symbols:**

```
ffffffff81745b10-ffffffff81745b6f: crypto_unregister_shashes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void crypto_unregister_shashes(struct shash_alg *algs, int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff81788480)
Location: crypto/shash.c:451
Inline: False
Direct callers:
  - arch/x86/crypto/sha512_ssse3_glue.c:sha512_ssse3_mod_fini
  - arch/x86/crypto/sha512_ssse3_glue.c:sha512_ssse3_mod_fini
  - arch/x86/crypto/sha512_ssse3_glue.c:sha512_ssse3_mod_fini
  - arch/x86/crypto/sha512_ssse3_glue.c:sha512_ssse3_mod_init
  - arch/x86/crypto/sha512_ssse3_glue.c:sha512_ssse3_mod_init
  - crypto/sha256_generic.c:sha256_generic_mod_fini
  - crypto/sha512_generic.c:sha512_generic_mod_fini
  - crypto/sha3_generic.c:sha3_generic_mod_fini
```
**Symbols:**

```
ffffffff81788480-ffffffff817884df: crypto_unregister_shashes (STB_GLOBAL)
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
int crypto_unregister_shashes(struct shash_alg *algs, int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffff8000105c1af8)
Location: crypto/shash.c:524
Inline: False
Direct callers:
  - crypto/sha256_generic.c:sha256_generic_mod_fini
  - crypto/sha512_generic.c:sha512_generic_mod_fini
```
**Symbols:**

```
ffff8000105c1af8-ffff8000105c1b80: crypto_unregister_shashes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int crypto_unregister_shashes(struct shash_alg *algs, int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (c076f144)
Location: crypto/shash.c:524
Inline: False
Direct callers:
  - crypto/sha256_generic.c:sha256_generic_mod_fini
  - crypto/sha512_generic.c:sha512_generic_mod_fini
```
**Symbols:**

```
c076f144-c076f1b4: crypto_unregister_shashes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int crypto_unregister_shashes(struct shash_alg *algs, int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (c00000000074a040)
Location: crypto/shash.c:524
Inline: False
Direct callers:
  - crypto/sha256_generic.c:sha256_generic_mod_fini
  - crypto/sha512_generic.c:sha512_generic_mod_fini
```
**Symbols:**

```
c00000000074a040-c00000000074a104: crypto_unregister_shashes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int crypto_unregister_shashes(struct shash_alg *algs, int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffe0004066cc)
Location: crypto/shash.c:524
Inline: False
Direct callers:
  - crypto/sha256_generic.c:sha256_generic_mod_fini
  - crypto/sha512_generic.c:sha512_generic_mod_fini
```
**Symbols:**

```
ffffffe0004066cc-ffffffe000406746: crypto_unregister_shashes (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int crypto_unregister_shashes(struct shash_alg *algs, int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/shash.c (0)
Location: crypto/shash.c:524
Inline: False
Direct callers:
  - crypto/sha256_generic.c:sha256_generic_mod_fini
  - crypto/sha512_generic.c:sha512_generic_mod_fini
```
**Symbols:**

```
ffffffff814bf0e7-ffffffff814bf105: crypto_unregister_shashes.cold (STB_LOCAL)
ffffffff814bed50-ffffffff814bedb8: crypto_unregister_shashes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int crypto_unregister_shashes(struct shash_alg *algs, int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/shash.c (0)
Location: crypto/shash.c:524
Inline: False
Direct callers:
  - crypto/sha256_generic.c:sha256_generic_mod_fini
  - crypto/sha512_generic.c:sha512_generic_mod_fini
```
**Symbols:**

```
ffffffff814afb07-ffffffff814afb25: crypto_unregister_shashes.cold (STB_LOCAL)
ffffffff814af770-ffffffff814af7d8: crypto_unregister_shashes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int crypto_unregister_shashes(struct shash_alg *algs, int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/shash.c (0)
Location: crypto/shash.c:524
Inline: False
Direct callers:
  - crypto/sha256_generic.c:sha256_generic_mod_fini
  - crypto/sha512_generic.c:sha512_generic_mod_fini
```
**Symbols:**

```
ffffffff814bb177-ffffffff814bb195: crypto_unregister_shashes.cold (STB_LOCAL)
ffffffff814bade0-ffffffff814bae48: crypto_unregister_shashes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int crypto_unregister_shashes(struct shash_alg *algs, int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/shash.c (0)
Location: crypto/shash.c:524
Inline: False
Direct callers:
  - crypto/sha256_generic.c:sha256_generic_mod_fini
  - crypto/sha512_generic.c:sha512_generic_mod_fini
```
**Symbols:**

```
ffffffff814d3c47-ffffffff814d3c65: crypto_unregister_shashes.cold (STB_LOCAL)
ffffffff814d3890-ffffffff814d38f8: crypto_unregister_shashes (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>void</code>
</li>
</ul>
</details>
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
