# Function: <code>crypto_unregister_acomp</code>

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
int crypto_unregister_acomp(struct acomp_alg *alg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/acompress.c (ffffffff813fa630)
Location: crypto/acompress.c:162
Inline: False
```
**Symbols:**

```
ffffffff813fa630-ffffffff813fa644: crypto_unregister_acomp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int crypto_unregister_acomp(struct acomp_alg *alg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/acompress.c (ffffffff81406f34)
Location: crypto/acompress.c:163
Inline: True
Inline callers:
  - crypto/acompress.c:crypto_unregister_acomps
  - crypto/acompress.c:crypto_register_acomps
```
**Symbols:**

```
ffffffff81406e10-ffffffff81406e24: crypto_unregister_acomp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int crypto_unregister_acomp(struct acomp_alg *alg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/acompress.c (ffffffff8142f884)
Location: crypto/acompress.c:163
Inline: True
Inline callers:
  - crypto/acompress.c:crypto_unregister_acomps
  - crypto/acompress.c:crypto_register_acomps
```
**Symbols:**

```
ffffffff8142f760-ffffffff8142f774: crypto_unregister_acomp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int crypto_unregister_acomp(struct acomp_alg *alg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/acompress.c (ffffffff81462512)
Location: crypto/acompress.c:163
Inline: True
Inline callers:
  - crypto/acompress.c:crypto_unregister_acomps
  - crypto/acompress.c:crypto_register_acomps
```
**Symbols:**

```
ffffffff81462410-ffffffff81462424: crypto_unregister_acomp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int crypto_unregister_acomp(struct acomp_alg *alg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/acompress.c (ffffffff814801b2)
Location: crypto/acompress.c:159
Inline: True
Inline callers:
  - crypto/acompress.c:crypto_unregister_acomps
  - crypto/acompress.c:crypto_register_acomps
```
**Symbols:**

```
ffffffff81480070-ffffffff81480084: crypto_unregister_acomp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int crypto_unregister_acomp(struct acomp_alg *alg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/acompress.c (ffffffff814ae3f2)
Location: crypto/acompress.c:154
Inline: True
Inline callers:
  - crypto/acompress.c:crypto_unregister_acomps
  - crypto/acompress.c:crypto_register_acomps
```
**Symbols:**

```
ffffffff814ae2c0-ffffffff814ae2d4: crypto_unregister_acomp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int crypto_unregister_acomp(struct acomp_alg *alg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/acompress.c (ffffffff814c9082)
Location: crypto/acompress.c:154
Inline: True
Inline callers:
  - crypto/acompress.c:crypto_unregister_acomps
  - crypto/acompress.c:crypto_register_acomps
```
**Symbols:**

```
ffffffff814c8f50-ffffffff814c8f64: crypto_unregister_acomp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void crypto_unregister_acomp(struct acomp_alg *alg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/acompress.c (ffffffff81528392)
Location: crypto/acompress.c:154
Inline: True
Inline callers:
  - crypto/acompress.c:crypto_unregister_acomps
  - crypto/acompress.c:crypto_register_acomps
```
**Symbols:**

```
ffffffff81528350-ffffffff81528364: crypto_unregister_acomp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void crypto_unregister_acomp(struct acomp_alg *alg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/acompress.c (ffffffff81545342)
Location: crypto/acompress.c:162
Inline: True
Inline callers:
  - crypto/acompress.c:crypto_unregister_acomps
  - crypto/acompress.c:crypto_register_acomps
```
**Symbols:**

```
ffffffff81545300-ffffffff81545314: crypto_unregister_acomp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void crypto_unregister_acomp(struct acomp_alg *alg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/acompress.c (ffffffff8154d9d2)
Location: crypto/acompress.c:162
Inline: True
Inline callers:
  - crypto/acompress.c:crypto_unregister_acomps
  - crypto/acompress.c:crypto_register_acomps
```
**Symbols:**

```
ffffffff8154d990-ffffffff8154d9a4: crypto_unregister_acomp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void crypto_unregister_acomp(struct acomp_alg *alg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/acompress.c (ffffffff815ae1b2)
Location: crypto/acompress.c:162
Inline: True
Inline callers:
  - crypto/acompress.c:crypto_unregister_acomps
  - crypto/acompress.c:crypto_register_acomps
```
**Symbols:**

```
ffffffff815ae170-ffffffff815ae184: crypto_unregister_acomp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void crypto_unregister_acomp(struct acomp_alg *alg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/acompress.c (ffffffff816566e2)
Location: crypto/acompress.c:162
Inline: True
Inline callers:
  - crypto/acompress.c:crypto_unregister_acomps
  - crypto/acompress.c:crypto_register_acomps
```
**Symbols:**

```
ffffffff816566a0-ffffffff816566ba: crypto_unregister_acomp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void crypto_unregister_acomp(struct acomp_alg *alg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/acompress.c (ffffffff81710992)
Location: crypto/acompress.c:162
Inline: True
Inline callers:
  - crypto/acompress.c:crypto_unregister_acomps
  - crypto/acompress.c:crypto_register_acomps
```
**Symbols:**

```
ffffffff81710940-ffffffff8171095a: crypto_unregister_acomp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void crypto_unregister_acomp(struct acomp_alg *alg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/acompress.c (ffffffff8174b3f2)
Location: crypto/acompress.c:209
Inline: True
Inline callers:
  - crypto/acompress.c:crypto_unregister_acomps
  - crypto/acompress.c:crypto_register_acomps
```
**Symbols:**

```
ffffffff8174b3a0-ffffffff8174b3ba: crypto_unregister_acomp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void crypto_unregister_acomp(struct acomp_alg *alg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/acompress.c (ffffffff8178d2c2)
Location: crypto/acompress.c:209
Inline: True
Inline callers:
  - crypto/acompress.c:crypto_unregister_acomps
  - crypto/acompress.c:crypto_register_acomps
```
**Symbols:**

```
ffffffff8178d270-ffffffff8178d28a: crypto_unregister_acomp (STB_GLOBAL)
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
int crypto_unregister_acomp(struct acomp_alg *alg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/acompress.c (ffff8000105c4b78)
Location: crypto/acompress.c:154
Inline: True
Inline callers:
  - crypto/acompress.c:crypto_unregister_acomps
  - crypto/acompress.c:crypto_register_acomps
```
**Symbols:**

```
ffff8000105c4a20-ffff8000105c4a4c: crypto_unregister_acomp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int crypto_unregister_acomp(struct acomp_alg *alg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/acompress.c (c0771bf4)
Location: crypto/acompress.c:154
Inline: True
Inline callers:
  - crypto/acompress.c:crypto_unregister_acomps
  - crypto/acompress.c:crypto_register_acomps
```
**Symbols:**

```
c0771afc-c0771b1c: crypto_unregister_acomp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int crypto_unregister_acomp(struct acomp_alg *alg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/acompress.c (c00000000074df80)
Location: crypto/acompress.c:154
Inline: True
Inline callers:
  - crypto/acompress.c:crypto_unregister_acomps
  - crypto/acompress.c:crypto_register_acomps
```
**Symbols:**

```
c00000000074ddb0-c00000000074dde8: crypto_unregister_acomp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int crypto_unregister_acomp(struct acomp_alg *alg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/acompress.c (ffffffe000408fda)
Location: crypto/acompress.c:154
Inline: True
Inline callers:
  - crypto/acompress.c:crypto_unregister_acomps
  - crypto/acompress.c:crypto_register_acomps
```
**Symbols:**

```
ffffffe000408ed8-ffffffe000408f04: crypto_unregister_acomp (STB_GLOBAL)
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
int crypto_unregister_acomp(struct acomp_alg *alg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/acompress.c (ffffffff814c1662)
Location: crypto/acompress.c:154
Inline: True
Inline callers:
  - crypto/acompress.c:crypto_unregister_acomps
  - crypto/acompress.c:crypto_register_acomps
```
**Symbols:**

```
ffffffff814c1530-ffffffff814c1544: crypto_unregister_acomp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int crypto_unregister_acomp(struct acomp_alg *alg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/acompress.c (ffffffff814b2082)
Location: crypto/acompress.c:154
Inline: True
Inline callers:
  - crypto/acompress.c:crypto_unregister_acomps
  - crypto/acompress.c:crypto_register_acomps
```
**Symbols:**

```
ffffffff814b1f50-ffffffff814b1f64: crypto_unregister_acomp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int crypto_unregister_acomp(struct acomp_alg *alg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/acompress.c (ffffffff814bd6f2)
Location: crypto/acompress.c:154
Inline: True
Inline callers:
  - crypto/acompress.c:crypto_unregister_acomps
  - crypto/acompress.c:crypto_register_acomps
```
**Symbols:**

```
ffffffff814bd5c0-ffffffff814bd5d4: crypto_unregister_acomp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int crypto_unregister_acomp(struct acomp_alg *alg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/acompress.c (ffffffff814d61c2)
Location: crypto/acompress.c:154
Inline: True
Inline callers:
  - crypto/acompress.c:crypto_unregister_acomps
  - crypto/acompress.c:crypto_register_acomps
```
**Symbols:**

```
ffffffff814d6090-ffffffff814d60a4: crypto_unregister_acomp (STB_GLOBAL)
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
