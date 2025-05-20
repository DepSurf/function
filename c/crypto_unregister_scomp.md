# Function: <code>crypto_unregister_scomp</code>

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
int crypto_unregister_scomp(struct scomp_alg *alg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/scompress.c (ffffffff813faa00)
Location: crypto/scompress.c:342
Inline: False
Direct callers:
  - crypto/lzo.c:lzo_mod_fini
```
**Symbols:**

```
ffffffff813faa00-ffffffff813faa4d: crypto_unregister_scomp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int crypto_unregister_scomp(struct scomp_alg *alg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/scompress.c (ffffffff81407310)
Location: crypto/scompress.c:341
Inline: False
Direct callers:
  - crypto/scompress.c:crypto_unregister_scomps
  - crypto/scompress.c:crypto_register_scomps
  - crypto/lzo.c:lzo_mod_fini
```
**Symbols:**

```
ffffffff81407310-ffffffff81407353: crypto_unregister_scomp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int crypto_unregister_scomp(struct scomp_alg *alg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/scompress.c (ffffffff8142fb24)
Location: crypto/scompress.c:339
Inline: True
Inline callers:
  - crypto/scompress.c:crypto_unregister_scomps
  - crypto/scompress.c:crypto_register_scomps
Direct callers:
  - crypto/lzo.c:lzo_mod_fini
```
**Symbols:**

```
ffffffff8142f9e0-ffffffff8142f9f4: crypto_unregister_scomp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int crypto_unregister_scomp(struct scomp_alg *alg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/scompress.c (ffffffff81462914)
Location: crypto/scompress.c:292
Inline: True
Inline callers:
  - crypto/scompress.c:crypto_unregister_scomps
  - crypto/scompress.c:crypto_register_scomps
Direct callers:
  - crypto/lzo.c:lzo_mod_fini
```
**Symbols:**

```
ffffffff814627d0-ffffffff814627e4: crypto_unregister_scomp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int crypto_unregister_scomp(struct scomp_alg *alg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/scompress.c (ffffffff81480592)
Location: crypto/scompress.c:289
Inline: True
Inline callers:
  - crypto/scompress.c:crypto_unregister_scomps
  - crypto/scompress.c:crypto_register_scomps
Direct callers:
  - crypto/lzo.c:lzo_mod_fini
```
**Symbols:**

```
ffffffff81480450-ffffffff81480464: crypto_unregister_scomp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int crypto_unregister_scomp(struct scomp_alg *alg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/scompress.c (ffffffff814ae982)
Location: crypto/scompress.c:269
Inline: True
Inline callers:
  - crypto/scompress.c:crypto_unregister_scomps
  - crypto/scompress.c:crypto_register_scomps
Direct callers:
  - crypto/lzo.c:lzo_mod_fini
  - crypto/lzo-rle.c:lzorle_mod_fini
```
**Symbols:**

```
ffffffff814ae850-ffffffff814ae864: crypto_unregister_scomp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int crypto_unregister_scomp(struct scomp_alg *alg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/scompress.c (ffffffff814c9612)
Location: crypto/scompress.c:269
Inline: True
Inline callers:
  - crypto/scompress.c:crypto_unregister_scomps
  - crypto/scompress.c:crypto_register_scomps
Direct callers:
  - crypto/lzo.c:lzo_mod_fini
  - crypto/lzo-rle.c:lzorle_mod_fini
```
**Symbols:**

```
ffffffff814c94e0-ffffffff814c94f4: crypto_unregister_scomp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void crypto_unregister_scomp(struct scomp_alg *alg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/scompress.c (ffffffff81528912)
Location: crypto/scompress.c:269
Inline: True
Inline callers:
  - crypto/scompress.c:crypto_unregister_scomps
  - crypto/scompress.c:crypto_register_scomps
Direct callers:
  - crypto/lzo.c:lzo_mod_fini
  - crypto/lzo-rle.c:lzorle_mod_fini
```
**Symbols:**

```
ffffffff815288d0-ffffffff815288e4: crypto_unregister_scomp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void crypto_unregister_scomp(struct scomp_alg *alg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/scompress.c (ffffffff815458e2)
Location: crypto/scompress.c:269
Inline: True
Inline callers:
  - crypto/scompress.c:crypto_unregister_scomps
  - crypto/scompress.c:crypto_register_scomps
Direct callers:
  - crypto/lzo.c:lzo_mod_fini
  - crypto/lzo-rle.c:lzorle_mod_fini
```
**Symbols:**

```
ffffffff815458a0-ffffffff815458b4: crypto_unregister_scomp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void crypto_unregister_scomp(struct scomp_alg *alg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/scompress.c (ffffffff8154df62)
Location: crypto/scompress.c:269
Inline: True
Inline callers:
  - crypto/scompress.c:crypto_unregister_scomps
  - crypto/scompress.c:crypto_register_scomps
Direct callers:
  - crypto/lzo.c:lzo_mod_fini
  - crypto/lzo-rle.c:lzorle_mod_fini
```
**Symbols:**

```
ffffffff8154df20-ffffffff8154df34: crypto_unregister_scomp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void crypto_unregister_scomp(struct scomp_alg *alg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/scompress.c (ffffffff815ae7d2)
Location: crypto/scompress.c:269
Inline: True
Inline callers:
  - crypto/scompress.c:crypto_unregister_scomps
  - crypto/scompress.c:crypto_register_scomps
Direct callers:
  - crypto/lzo.c:lzo_mod_fini
  - crypto/lzo-rle.c:lzorle_mod_fini
```
**Symbols:**

```
ffffffff815ae790-ffffffff815ae7a4: crypto_unregister_scomp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void crypto_unregister_scomp(struct scomp_alg *alg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/scompress.c (ffffffff81656d82)
Location: crypto/scompress.c:269
Inline: True
Inline callers:
  - crypto/scompress.c:crypto_unregister_scomps
  - crypto/scompress.c:crypto_register_scomps
Direct callers:
  - crypto/lzo.c:lzo_mod_fini
  - crypto/lzo-rle.c:lzorle_mod_fini
```
**Symbols:**

```
ffffffff81656d40-ffffffff81656d5a: crypto_unregister_scomp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void crypto_unregister_scomp(struct scomp_alg *alg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/scompress.c (ffffffff81710e72)
Location: crypto/scompress.c:269
Inline: True
Inline callers:
  - crypto/scompress.c:crypto_unregister_scomps
  - crypto/scompress.c:crypto_register_scomps
Direct callers:
  - crypto/lzo.c:lzo_mod_fini
  - crypto/lzo-rle.c:lzorle_mod_fini
```
**Symbols:**

```
ffffffff81710e20-ffffffff81710e3a: crypto_unregister_scomp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void crypto_unregister_scomp(struct scomp_alg *alg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/scompress.c (ffffffff8174b962)
Location: crypto/scompress.c:268
Inline: True
Inline callers:
  - crypto/scompress.c:crypto_unregister_scomps
  - crypto/scompress.c:crypto_register_scomps
Direct callers:
  - crypto/lzo.c:lzo_mod_fini
  - crypto/lzo-rle.c:lzorle_mod_fini
```
**Symbols:**

```
ffffffff8174b910-ffffffff8174b92a: crypto_unregister_scomp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void crypto_unregister_scomp(struct scomp_alg *alg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/scompress.c (ffffffff8178d842)
Location: crypto/scompress.c:274
Inline: True
Inline callers:
  - crypto/scompress.c:crypto_unregister_scomps
  - crypto/scompress.c:crypto_register_scomps
Direct callers:
  - crypto/deflate.c:deflate_mod_fini
  - crypto/lzo.c:lzo_mod_fini
  - crypto/lzo-rle.c:lzorle_mod_fini
```
**Symbols:**

```
ffffffff8178d7f0-ffffffff8178d80a: crypto_unregister_scomp (STB_GLOBAL)
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
int crypto_unregister_scomp(struct scomp_alg *alg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/scompress.c (ffff8000105c50b0)
Location: crypto/scompress.c:269
Inline: True
Inline callers:
  - crypto/scompress.c:crypto_unregister_scomps
  - crypto/scompress.c:crypto_register_scomps
Direct callers:
  - crypto/lzo.c:lzo_mod_fini
  - crypto/lzo-rle.c:lzorle_mod_fini
```
**Symbols:**

```
ffff8000105c4f58-ffff8000105c4f84: crypto_unregister_scomp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int crypto_unregister_scomp(struct scomp_alg *alg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/scompress.c (c07721b4)
Location: crypto/scompress.c:269
Inline: True
Inline callers:
  - crypto/scompress.c:crypto_unregister_scomps
  - crypto/scompress.c:crypto_register_scomps
Direct callers:
  - crypto/lzo.c:lzo_mod_fini
  - crypto/lzo-rle.c:lzorle_mod_fini
```
**Symbols:**

```
c07720bc-c07720dc: crypto_unregister_scomp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int crypto_unregister_scomp(struct scomp_alg *alg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/scompress.c (c00000000074e940)
Location: crypto/scompress.c:269
Inline: True
Inline callers:
  - crypto/scompress.c:crypto_unregister_scomps
  - crypto/scompress.c:crypto_register_scomps
Direct callers:
  - crypto/lzo.c:lzo_mod_fini
  - crypto/lzo-rle.c:lzorle_mod_fini
```
**Symbols:**

```
c00000000074e770-c00000000074e7a8: crypto_unregister_scomp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int crypto_unregister_scomp(struct scomp_alg *alg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/scompress.c (ffffffe0004095dc)
Location: crypto/scompress.c:269
Inline: True
Inline callers:
  - crypto/scompress.c:crypto_unregister_scomps
  - crypto/scompress.c:crypto_register_scomps
Direct callers:
  - crypto/lzo.c:lzo_mod_fini
  - crypto/lzo-rle.c:lzorle_mod_fini
```
**Symbols:**

```
ffffffe0004094da-ffffffe000409506: crypto_unregister_scomp (STB_GLOBAL)
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
int crypto_unregister_scomp(struct scomp_alg *alg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/scompress.c (ffffffff814c1bf2)
Location: crypto/scompress.c:269
Inline: True
Inline callers:
  - crypto/scompress.c:crypto_unregister_scomps
  - crypto/scompress.c:crypto_register_scomps
Direct callers:
  - crypto/lzo.c:lzo_mod_fini
  - crypto/lzo-rle.c:lzorle_mod_fini
```
**Symbols:**

```
ffffffff814c1ac0-ffffffff814c1ad4: crypto_unregister_scomp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int crypto_unregister_scomp(struct scomp_alg *alg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/scompress.c (ffffffff814b2612)
Location: crypto/scompress.c:269
Inline: True
Inline callers:
  - crypto/scompress.c:crypto_unregister_scomps
  - crypto/scompress.c:crypto_register_scomps
Direct callers:
  - crypto/lzo.c:lzo_mod_fini
  - crypto/lzo-rle.c:lzorle_mod_fini
```
**Symbols:**

```
ffffffff814b24e0-ffffffff814b24f4: crypto_unregister_scomp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int crypto_unregister_scomp(struct scomp_alg *alg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/scompress.c (ffffffff814bdc82)
Location: crypto/scompress.c:269
Inline: True
Inline callers:
  - crypto/scompress.c:crypto_unregister_scomps
  - crypto/scompress.c:crypto_register_scomps
Direct callers:
  - crypto/lzo.c:lzo_mod_fini
  - crypto/lzo-rle.c:lzorle_mod_fini
```
**Symbols:**

```
ffffffff814bdb50-ffffffff814bdb64: crypto_unregister_scomp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int crypto_unregister_scomp(struct scomp_alg *alg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/scompress.c (ffffffff814d6752)
Location: crypto/scompress.c:269
Inline: True
Inline callers:
  - crypto/scompress.c:crypto_unregister_scomps
  - crypto/scompress.c:crypto_register_scomps
Direct callers:
  - crypto/lzo.c:lzo_mod_fini
  - crypto/lzo-rle.c:lzorle_mod_fini
```
**Symbols:**

```
ffffffff814d6620-ffffffff814d6634: crypto_unregister_scomp (STB_GLOBAL)
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
