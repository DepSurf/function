# Function: <code>crypto_register_skcipher</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int crypto_register_skcipher(struct skcipher_alg *alg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff813de560)
Location: crypto/skcipher.c:367
Inline: False
Direct callers:
  - crypto/skcipher.c:crypto_register_skciphers
```
**Symbols:**

```
ffffffff813de560-ffffffff813de5b0: crypto_register_skcipher (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int crypto_register_skcipher(struct skcipher_alg *alg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff813f5f90)
Location: crypto/skcipher.c:909
Inline: False
Direct callers:
  - crypto/skcipher.c:crypto_register_skciphers
```
**Symbols:**

```
ffffffff813f5f90-ffffffff813f5fe0: crypto_register_skcipher (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int crypto_register_skcipher(struct skcipher_alg *alg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff81402320)
Location: crypto/skcipher.c:952
Inline: False
Direct callers:
  - crypto/skcipher.c:crypto_register_skciphers
```
**Symbols:**

```
ffffffff81402320-ffffffff81402387: crypto_register_skcipher (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int crypto_register_skcipher(struct skcipher_alg *alg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff8142a990)
Location: crypto/skcipher.c:958
Inline: False
Direct callers:
  - crypto/skcipher.c:crypto_register_skciphers
```
**Symbols:**

```
ffffffff8142a990-ffffffff8142a9f7: crypto_register_skcipher (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int crypto_register_skcipher(struct skcipher_alg *alg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff8145d6e0)
Location: crypto/skcipher.c:981
Inline: False
Direct callers:
  - crypto/skcipher.c:crypto_register_skciphers
```
**Symbols:**

```
ffffffff8145d6e0-ffffffff8145d747: crypto_register_skcipher (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int crypto_register_skcipher(struct skcipher_alg *alg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff8147afb0)
Location: crypto/skcipher.c:1009
Inline: False
Direct callers:
  - crypto/skcipher.c:crypto_register_skciphers
```
**Symbols:**

```
ffffffff8147afb0-ffffffff8147b017: crypto_register_skcipher (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int crypto_register_skcipher(struct skcipher_alg *alg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff814a9000)
Location: crypto/skcipher.c:1043
Inline: False
Direct callers:
  - crypto/skcipher.c:crypto_register_skciphers
  - crypto/crypto_null.c:crypto_null_mod_init
```
**Symbols:**

```
ffffffff814a9000-ffffffff814a9066: crypto_register_skcipher (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int crypto_register_skcipher(struct skcipher_alg *alg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff814c3c70)
Location: crypto/skcipher.c:1047
Inline: False
Direct callers:
  - crypto/skcipher.c:crypto_register_skciphers
  - crypto/crypto_null.c:crypto_null_mod_init
```
**Symbols:**

```
ffffffff814c3c70-ffffffff814c3cd6: crypto_register_skcipher (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int crypto_register_skcipher(struct skcipher_alg *alg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff81522e4d)
Location: crypto/skcipher.c:815
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_register_skciphers
Direct callers:
  - crypto/crypto_null.c:crypto_null_mod_init
```
**Symbols:**

```
ffffffff81522f30-ffffffff81522f96: crypto_register_skcipher (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int crypto_register_skcipher(struct skcipher_alg *alg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff8153fd9d)
Location: crypto/skcipher.c:815
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_register_skciphers
Direct callers:
  - crypto/crypto_null.c:crypto_null_mod_init
```
**Symbols:**

```
ffffffff8153fe80-ffffffff8153fee6: crypto_register_skcipher (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int crypto_register_skcipher(struct skcipher_alg *alg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff815483cd)
Location: crypto/skcipher.c:810
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_register_skciphers
Direct callers:
  - crypto/crypto_null.c:crypto_null_mod_init
```
**Symbols:**

```
ffffffff81548630-ffffffff81548696: crypto_register_skcipher (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int crypto_register_skcipher(struct skcipher_alg *alg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff815a8bad)
Location: crypto/skcipher.c:810
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_register_skciphers
Direct callers:
  - crypto/crypto_null.c:crypto_null_mod_init
```
**Symbols:**

```
ffffffff815a8e10-ffffffff815a8e76: crypto_register_skcipher (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int crypto_register_skcipher(struct skcipher_alg *alg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff81650053)
Location: crypto/skcipher.c:810
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_register_skciphers
Direct callers:
  - crypto/crypto_null.c:crypto_null_mod_init
```
**Symbols:**

```
ffffffff816502d0-ffffffff8165034a: crypto_register_skcipher (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int crypto_register_skcipher(struct skcipher_alg *alg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff817097b3)
Location: crypto/skcipher.c:810
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_register_skciphers
Direct callers:
  - crypto/crypto_null.c:crypto_null_mod_init
```
**Symbols:**

```
ffffffff81709a50-ffffffff81709aca: crypto_register_skcipher (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int crypto_register_skcipher(struct skcipher_alg *alg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff817430d6)
Location: crypto/skcipher.c:861
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_register_skciphers
Direct callers:
  - crypto/crypto_null.c:crypto_null_mod_init
```
**Symbols:**

```
ffffffff817429a0-ffffffff817429cb: crypto_register_skcipher (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int crypto_register_skcipher(struct skcipher_alg *alg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff817863f0)
Location: crypto/skcipher.c:984
Inline: False
Direct callers:
  - crypto/skcipher.c:crypto_register_skciphers
  - crypto/crypto_null.c:crypto_null_mod_init
```
**Symbols:**

```
ffffffff817863f0-ffffffff81786476: crypto_register_skcipher (STB_GLOBAL)
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
int crypto_register_skcipher(struct skcipher_alg *alg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffff8000105be6c0)
Location: crypto/skcipher.c:1047
Inline: False
Direct callers:
  - crypto/skcipher.c:crypto_register_skciphers
  - crypto/crypto_null.c:crypto_null_mod_init
```
**Symbols:**

```
ffff8000105be6c0-ffff8000105be754: crypto_register_skcipher (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int crypto_register_skcipher(struct skcipher_alg *alg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (c076c3c4)
Location: crypto/skcipher.c:1047
Inline: False
Direct callers:
  - crypto/skcipher.c:crypto_register_skciphers
  - crypto/crypto_null.c:crypto_null_mod_init
```
**Symbols:**

```
c076c3c4-c076c448: crypto_register_skcipher (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int crypto_register_skcipher(struct skcipher_alg *alg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (c000000000745ec0)
Location: crypto/skcipher.c:1047
Inline: False
Direct callers:
  - crypto/skcipher.c:crypto_register_skciphers
  - crypto/crypto_null.c:crypto_null_mod_init
```
**Symbols:**

```
c000000000745ec0-c000000000745f68: crypto_register_skcipher (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int crypto_register_skcipher(struct skcipher_alg *alg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffe000403aa2)
Location: crypto/skcipher.c:1047
Inline: False
Direct callers:
  - crypto/skcipher.c:crypto_register_skciphers
  - crypto/crypto_null.c:crypto_null_mod_init
```
**Symbols:**

```
ffffffe000403aa2-ffffffe000403b0c: crypto_register_skcipher (STB_GLOBAL)
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
int crypto_register_skcipher(struct skcipher_alg *alg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff814bc250)
Location: crypto/skcipher.c:1047
Inline: False
Direct callers:
  - crypto/skcipher.c:crypto_register_skciphers
  - crypto/crypto_null.c:crypto_null_mod_init
```
**Symbols:**

```
ffffffff814bc250-ffffffff814bc2b6: crypto_register_skcipher (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int crypto_register_skcipher(struct skcipher_alg *alg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff814acc70)
Location: crypto/skcipher.c:1047
Inline: False
Direct callers:
  - crypto/skcipher.c:crypto_register_skciphers
  - crypto/crypto_null.c:crypto_null_mod_init
```
**Symbols:**

```
ffffffff814acc70-ffffffff814accd6: crypto_register_skcipher (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int crypto_register_skcipher(struct skcipher_alg *alg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff814b82e0)
Location: crypto/skcipher.c:1047
Inline: False
Direct callers:
  - crypto/skcipher.c:crypto_register_skciphers
  - crypto/crypto_null.c:crypto_null_mod_init
```
**Symbols:**

```
ffffffff814b82e0-ffffffff814b8346: crypto_register_skcipher (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int crypto_register_skcipher(struct skcipher_alg *alg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff814d0dc0)
Location: crypto/skcipher.c:1047
Inline: False
Direct callers:
  - crypto/skcipher.c:crypto_register_skciphers
  - crypto/crypto_null.c:crypto_null_mod_init
```
**Symbols:**

```
ffffffff814d0dc0-ffffffff814d0e26: crypto_register_skcipher (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
