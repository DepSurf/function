# Function: <code>crypto_register_scomp</code>

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
<summary>In <code>4.10</code>: ✅</summary>

```c
int crypto_register_scomp(struct scomp_alg *alg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/scompress.c (ffffffff813fa950)
Location: crypto/scompress.c:315
Inline: False
```
**Symbols:**

```
ffffffff813fa950-ffffffff813fa9fd: crypto_register_scomp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int crypto_register_scomp(struct scomp_alg *alg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/scompress.c (ffffffff81407270)
Location: crypto/scompress.c:314
Inline: False
Direct callers:
  - crypto/scompress.c:crypto_register_scomps
```
**Symbols:**

```
ffffffff81407270-ffffffff8140730c: crypto_register_scomp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int crypto_register_scomp(struct scomp_alg *alg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/scompress.c (ffffffff8142fa44)
Location: crypto/scompress.c:327
Inline: True
Inline callers:
  - crypto/scompress.c:crypto_register_scomps
```
**Symbols:**

```
ffffffff8142f9b0-ffffffff8142f9db: crypto_register_scomp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int crypto_register_scomp(struct scomp_alg *alg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/scompress.c (ffffffff81462834)
Location: crypto/scompress.c:280
Inline: True
Inline callers:
  - crypto/scompress.c:crypto_register_scomps
Direct callers:
  - crypto/lzo.c:lzo_mod_init
```
**Symbols:**

```
ffffffff814627a0-ffffffff814627cb: crypto_register_scomp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int crypto_register_scomp(struct scomp_alg *alg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/scompress.c (ffffffff814804b4)
Location: crypto/scompress.c:277
Inline: True
Inline callers:
  - crypto/scompress.c:crypto_register_scomps
Direct callers:
  - crypto/lzo.c:lzo_mod_init
```
**Symbols:**

```
ffffffff81480420-ffffffff8148044b: crypto_register_scomp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int crypto_register_scomp(struct scomp_alg *alg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/scompress.c (ffffffff814ae8ad)
Location: crypto/scompress.c:257
Inline: True
Inline callers:
  - crypto/scompress.c:crypto_register_scomps
Direct callers:
  - crypto/lzo.c:lzo_mod_init
  - crypto/lzo-rle.c:lzorle_mod_init
```
**Symbols:**

```
ffffffff814ae820-ffffffff814ae84b: crypto_register_scomp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int crypto_register_scomp(struct scomp_alg *alg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/scompress.c (ffffffff814c953d)
Location: crypto/scompress.c:257
Inline: True
Inline callers:
  - crypto/scompress.c:crypto_register_scomps
Direct callers:
  - crypto/lzo.c:lzo_mod_init
  - crypto/lzo-rle.c:lzorle_mod_init
```
**Symbols:**

```
ffffffff814c94b0-ffffffff814c94db: crypto_register_scomp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int crypto_register_scomp(struct scomp_alg *alg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/scompress.c (ffffffff81528969)
Location: crypto/scompress.c:257
Inline: True
Inline callers:
  - crypto/scompress.c:crypto_register_scomps
Direct callers:
  - crypto/lzo.c:lzo_mod_init
  - crypto/lzo-rle.c:lzorle_mod_init
```
**Symbols:**

```
ffffffff815288a0-ffffffff815288cb: crypto_register_scomp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int crypto_register_scomp(struct scomp_alg *alg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/scompress.c (ffffffff81545939)
Location: crypto/scompress.c:257
Inline: True
Inline callers:
  - crypto/scompress.c:crypto_register_scomps
Direct callers:
  - crypto/lzo.c:lzo_mod_init
  - crypto/lzo-rle.c:lzorle_mod_init
```
**Symbols:**

```
ffffffff81545870-ffffffff8154589b: crypto_register_scomp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int crypto_register_scomp(struct scomp_alg *alg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/scompress.c (ffffffff8154dfb9)
Location: crypto/scompress.c:257
Inline: True
Inline callers:
  - crypto/scompress.c:crypto_register_scomps
Direct callers:
  - crypto/lzo.c:lzo_mod_init
  - crypto/lzo-rle.c:lzorle_mod_init
```
**Symbols:**

```
ffffffff8154def0-ffffffff8154df1b: crypto_register_scomp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int crypto_register_scomp(struct scomp_alg *alg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/scompress.c (ffffffff815ae829)
Location: crypto/scompress.c:257
Inline: True
Inline callers:
  - crypto/scompress.c:crypto_register_scomps
Direct callers:
  - crypto/lzo.c:lzo_mod_init
  - crypto/lzo-rle.c:lzorle_mod_init
```
**Symbols:**

```
ffffffff815ae760-ffffffff815ae78b: crypto_register_scomp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int crypto_register_scomp(struct scomp_alg *alg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/scompress.c (ffffffff81656df9)
Location: crypto/scompress.c:257
Inline: True
Inline callers:
  - crypto/scompress.c:crypto_register_scomps
Direct callers:
  - crypto/lzo.c:lzo_mod_init
  - crypto/lzo-rle.c:lzorle_mod_init
```
**Symbols:**

```
ffffffff81656d00-ffffffff81656d31: crypto_register_scomp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int crypto_register_scomp(struct scomp_alg *alg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/scompress.c (ffffffff81711199)
Location: crypto/scompress.c:257
Inline: True
Inline callers:
  - crypto/scompress.c:crypto_register_scomps
Direct callers:
  - crypto/lzo.c:lzo_mod_init
  - crypto/lzo-rle.c:lzorle_mod_init
```
**Symbols:**

```
ffffffff81710dd0-ffffffff81710e01: crypto_register_scomp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int crypto_register_scomp(struct scomp_alg *alg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/scompress.c (ffffffff8174bc89)
Location: crypto/scompress.c:255
Inline: True
Inline callers:
  - crypto/scompress.c:crypto_register_scomps
Direct callers:
  - crypto/lzo.c:lzo_mod_init
  - crypto/lzo-rle.c:lzorle_mod_init
```
**Symbols:**

```
ffffffff8174b8c0-ffffffff8174b8fa: crypto_register_scomp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int crypto_register_scomp(struct scomp_alg *alg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/scompress.c (ffffffff8178db69)
Location: crypto/scompress.c:261
Inline: True
Inline callers:
  - crypto/scompress.c:crypto_register_scomps
Direct callers:
  - crypto/deflate.c:deflate_mod_init
  - crypto/lzo.c:lzo_mod_init
  - crypto/lzo-rle.c:lzorle_mod_init
```
**Symbols:**

```
ffffffff8178d7a0-ffffffff8178d7da: crypto_register_scomp (STB_GLOBAL)
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
int crypto_register_scomp(struct scomp_alg *alg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/scompress.c (ffff8000105c4fdc)
Location: crypto/scompress.c:257
Inline: True
Inline callers:
  - crypto/scompress.c:crypto_register_scomps
Direct callers:
  - crypto/lzo.c:lzo_mod_init
  - crypto/lzo-rle.c:lzorle_mod_init
```
**Symbols:**

```
ffff8000105c4f08-ffff8000105c4f54: crypto_register_scomp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int crypto_register_scomp(struct scomp_alg *alg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/scompress.c (c077211c)
Location: crypto/scompress.c:257
Inline: True
Inline callers:
  - crypto/scompress.c:crypto_register_scomps
Direct callers:
  - crypto/lzo.c:lzo_mod_init
  - crypto/lzo-rle.c:lzorle_mod_init
```
**Symbols:**

```
c077207c-c07720bc: crypto_register_scomp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int crypto_register_scomp(struct scomp_alg *alg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/scompress.c (c00000000074e818)
Location: crypto/scompress.c:257
Inline: True
Inline callers:
  - crypto/scompress.c:crypto_register_scomps
Direct callers:
  - crypto/lzo.c:lzo_mod_init
  - crypto/lzo-rle.c:lzorle_mod_init
```
**Symbols:**

```
c00000000074e710-c00000000074e768: crypto_register_scomp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int crypto_register_scomp(struct scomp_alg *alg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/scompress.c (ffffffe000409546)
Location: crypto/scompress.c:257
Inline: True
Inline callers:
  - crypto/scompress.c:crypto_register_scomps
Direct callers:
  - crypto/lzo.c:lzo_mod_init
  - crypto/lzo-rle.c:lzorle_mod_init
```
**Symbols:**

```
ffffffe000409498-ffffffe0004094da: crypto_register_scomp (STB_GLOBAL)
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
int crypto_register_scomp(struct scomp_alg *alg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/scompress.c (ffffffff814c1b1d)
Location: crypto/scompress.c:257
Inline: True
Inline callers:
  - crypto/scompress.c:crypto_register_scomps
Direct callers:
  - crypto/lzo.c:lzo_mod_init
  - crypto/lzo-rle.c:lzorle_mod_init
```
**Symbols:**

```
ffffffff814c1a90-ffffffff814c1abb: crypto_register_scomp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int crypto_register_scomp(struct scomp_alg *alg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/scompress.c (ffffffff814b253d)
Location: crypto/scompress.c:257
Inline: True
Inline callers:
  - crypto/scompress.c:crypto_register_scomps
Direct callers:
  - crypto/lzo.c:lzo_mod_init
  - crypto/lzo-rle.c:lzorle_mod_init
```
**Symbols:**

```
ffffffff814b24b0-ffffffff814b24db: crypto_register_scomp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int crypto_register_scomp(struct scomp_alg *alg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/scompress.c (ffffffff814bdbad)
Location: crypto/scompress.c:257
Inline: True
Inline callers:
  - crypto/scompress.c:crypto_register_scomps
Direct callers:
  - crypto/lzo.c:lzo_mod_init
  - crypto/lzo-rle.c:lzorle_mod_init
```
**Symbols:**

```
ffffffff814bdb20-ffffffff814bdb4b: crypto_register_scomp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int crypto_register_scomp(struct scomp_alg *alg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/scompress.c (ffffffff814d667d)
Location: crypto/scompress.c:257
Inline: True
Inline callers:
  - crypto/scompress.c:crypto_register_scomps
Direct callers:
  - crypto/lzo.c:lzo_mod_init
  - crypto/lzo-rle.c:lzorle_mod_init
```
**Symbols:**

```
ffffffff814d65f0-ffffffff814d661b: crypto_register_scomp (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
