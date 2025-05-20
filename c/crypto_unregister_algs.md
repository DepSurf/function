# Function: <code>crypto_unregister_algs</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int crypto_unregister_algs(struct crypto_alg *algs, int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff8139e320)
Location: crypto/algapi.c:431
Inline: False
Direct callers:
  - crypto/crypto_null.c:crypto_null_mod_fini
```
**Symbols:**

```
ffffffff8139e320-ffffffff8139e37c: crypto_unregister_algs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int crypto_unregister_algs(struct crypto_alg *algs, int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff813db280)
Location: crypto/algapi.c:430
Inline: False
Direct callers:
  - crypto/crypto_null.c:crypto_null_mod_fini
```
**Symbols:**

```
ffffffff813db280-ffffffff813db2e3: crypto_unregister_algs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int crypto_unregister_algs(struct crypto_alg *algs, int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff813f2bc0)
Location: crypto/algapi.c:431
Inline: False
Direct callers:
  - crypto/crypto_null.c:crypto_null_mod_fini
```
**Symbols:**

```
ffffffff813f2bc0-ffffffff813f2c23: crypto_unregister_algs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int crypto_unregister_algs(struct crypto_alg *algs, int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff813feee0)
Location: crypto/algapi.c:431
Inline: False
Direct callers:
  - crypto/crypto_null.c:crypto_null_mod_fini
```
**Symbols:**

```
ffffffff813feee0-ffffffff813fef4e: crypto_unregister_algs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int crypto_unregister_algs(struct crypto_alg *algs, int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff814274a0)
Location: crypto/algapi.c:443
Inline: False
Direct callers:
  - crypto/crypto_null.c:crypto_null_mod_fini
```
**Symbols:**

```
ffffffff814274a0-ffffffff8142750e: crypto_unregister_algs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int crypto_unregister_algs(struct crypto_alg *algs, int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/algapi.c (0)
Location: crypto/algapi.c:451
Inline: False
Direct callers:
  - crypto/crypto_null.c:crypto_null_mod_fini
  - crypto/crypto_null.c:crypto_null_mod_init
```
**Symbols:**

```
ffffffff8145a745-ffffffff8145a75f: crypto_unregister_algs.cold.23 (STB_LOCAL)
ffffffff8145a1b0-ffffffff8145a20b: crypto_unregister_algs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int crypto_unregister_algs(struct crypto_alg *algs, int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/algapi.c (0)
Location: crypto/algapi.c:460
Inline: False
Direct callers:
  - crypto/crypto_null.c:crypto_null_mod_fini
  - crypto/crypto_null.c:crypto_null_mod_init
```
**Symbols:**

```
ffffffff814782ab-ffffffff814782c5: crypto_unregister_algs.cold.24 (STB_LOCAL)
ffffffff81477a30-ffffffff81477a8e: crypto_unregister_algs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int crypto_unregister_algs(struct crypto_alg *algs, int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/algapi.c (0)
Location: crypto/algapi.c:441
Inline: False
Direct callers:
  - crypto/crypto_null.c:crypto_null_mod_fini
  - crypto/crypto_null.c:crypto_null_mod_init
```
**Symbols:**

```
ffffffff814a60e2-ffffffff814a6100: crypto_unregister_algs.cold (STB_LOCAL)
ffffffff814a56e0-ffffffff814a5733: crypto_unregister_algs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int crypto_unregister_algs(struct crypto_alg *algs, int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/algapi.c (0)
Location: crypto/algapi.c:459
Inline: False
Direct callers:
  - crypto/crypto_null.c:crypto_null_mod_fini
  - crypto/crypto_null.c:crypto_null_mod_init
```
**Symbols:**

```
ffffffff814c0d6c-ffffffff814c0d8a: crypto_unregister_algs.cold (STB_LOCAL)
ffffffff814c0390-ffffffff814c03e3: crypto_unregister_algs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void crypto_unregister_algs(struct crypto_alg *algs, int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff815209f0)
Location: crypto/algapi.c:487
Inline: False
Direct callers:
  - crypto/crypto_null.c:crypto_null_mod_fini
  - crypto/crypto_null.c:crypto_null_mod_init
```
**Symbols:**

```
ffffffff815209f0-ffffffff81520a2f: crypto_unregister_algs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void crypto_unregister_algs(struct crypto_alg *algs, int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff8153d880)
Location: crypto/algapi.c:487
Inline: False
Direct callers:
  - crypto/crypto_null.c:crypto_null_mod_fini
  - crypto/crypto_null.c:crypto_null_mod_init
```
**Symbols:**

```
ffffffff8153d880-ffffffff8153d8bf: crypto_unregister_algs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void crypto_unregister_algs(struct crypto_alg *algs, int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff81545f60)
Location: crypto/algapi.c:487
Inline: False
Direct callers:
  - crypto/crypto_null.c:crypto_null_mod_fini
  - crypto/crypto_null.c:crypto_null_mod_init
```
**Symbols:**

```
ffffffff81545f60-ffffffff81545f9f: crypto_unregister_algs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void crypto_unregister_algs(struct crypto_alg *algs, int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff815a63e0)
Location: crypto/algapi.c:487
Inline: False
Direct callers:
  - crypto/crypto_null.c:crypto_null_mod_fini
  - crypto/crypto_null.c:crypto_null_mod_init
```
**Symbols:**

```
ffffffff815a63e0-ffffffff815a641f: crypto_unregister_algs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void crypto_unregister_algs(struct crypto_alg *algs, int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff8164d7d0)
Location: crypto/algapi.c:503
Inline: False
Direct callers:
  - crypto/crypto_null.c:crypto_null_mod_fini
  - crypto/crypto_null.c:crypto_null_mod_init
```
**Symbols:**

```
ffffffff8164d7d0-ffffffff8164d81a: crypto_unregister_algs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void crypto_unregister_algs(struct crypto_alg *algs, int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff81706880)
Location: crypto/algapi.c:524
Inline: False
Direct callers:
  - crypto/crypto_null.c:crypto_null_mod_fini
  - crypto/crypto_null.c:crypto_null_mod_init
```
**Symbols:**

```
ffffffff81706880-ffffffff817068ca: crypto_unregister_algs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void crypto_unregister_algs(struct crypto_alg *algs, int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff81740930)
Location: crypto/algapi.c:536
Inline: False
Direct callers:
  - crypto/crypto_null.c:crypto_null_mod_fini
  - crypto/crypto_null.c:crypto_null_mod_init
```
**Symbols:**

```
ffffffff81740930-ffffffff8174097b: crypto_unregister_algs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void crypto_unregister_algs(struct crypto_alg *algs, int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff817817d0)
Location: crypto/algapi.c:537
Inline: False
Direct callers:
  - crypto/crypto_null.c:crypto_null_mod_fini
  - crypto/crypto_null.c:crypto_null_mod_init
```
**Symbols:**

```
ffffffff817817d0-ffffffff8178181b: crypto_unregister_algs (STB_GLOBAL)
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
int crypto_unregister_algs(struct crypto_alg *algs, int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffff8000105b9a18)
Location: crypto/algapi.c:459
Inline: False
Direct callers:
  - crypto/crypto_null.c:crypto_null_mod_fini
  - crypto/crypto_null.c:crypto_null_mod_init
```
**Symbols:**

```
ffff8000105b9a18-ffff8000105b9a9c: crypto_unregister_algs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int crypto_unregister_algs(struct crypto_alg *algs, int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (c07683bc)
Location: crypto/algapi.c:459
Inline: False
Direct callers:
  - crypto/crypto_null.c:crypto_null_mod_fini
  - crypto/crypto_null.c:crypto_null_mod_init
```
**Symbols:**

```
c07683bc-c0768424: crypto_unregister_algs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int crypto_unregister_algs(struct crypto_alg *algs, int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (c00000000073ff20)
Location: crypto/algapi.c:459
Inline: False
Direct callers:
  - crypto/crypto_null.c:crypto_null_mod_fini
  - crypto/crypto_null.c:crypto_null_mod_init
```
**Symbols:**

```
c00000000073ff20-c00000000073ffd4: crypto_unregister_algs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int crypto_unregister_algs(struct crypto_alg *algs, int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffe0003ffe6e)
Location: crypto/algapi.c:459
Inline: False
Direct callers:
  - crypto/crypto_null.c:crypto_null_mod_fini
  - crypto/crypto_null.c:crypto_null_mod_init
```
**Symbols:**

```
ffffffe0003ffe6e-ffffffe0003ffee8: crypto_unregister_algs (STB_GLOBAL)
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
int crypto_unregister_algs(struct crypto_alg *algs, int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/algapi.c (0)
Location: crypto/algapi.c:459
Inline: False
Direct callers:
  - crypto/crypto_null.c:crypto_null_mod_fini
  - crypto/crypto_null.c:crypto_null_mod_init
```
**Symbols:**

```
ffffffff814b934c-ffffffff814b936a: crypto_unregister_algs.cold (STB_LOCAL)
ffffffff814b8970-ffffffff814b89c3: crypto_unregister_algs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int crypto_unregister_algs(struct crypto_alg *algs, int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/algapi.c (0)
Location: crypto/algapi.c:459
Inline: False
Direct callers:
  - crypto/crypto_null.c:crypto_null_mod_fini
  - crypto/crypto_null.c:crypto_null_mod_init
```
**Symbols:**

```
ffffffff814a9d6c-ffffffff814a9d8a: crypto_unregister_algs.cold (STB_LOCAL)
ffffffff814a9390-ffffffff814a93e3: crypto_unregister_algs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int crypto_unregister_algs(struct crypto_alg *algs, int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/algapi.c (0)
Location: crypto/algapi.c:459
Inline: False
Direct callers:
  - crypto/crypto_null.c:crypto_null_mod_fini
  - crypto/crypto_null.c:crypto_null_mod_init
```
**Symbols:**

```
ffffffff814b53dc-ffffffff814b53fa: crypto_unregister_algs.cold (STB_LOCAL)
ffffffff814b4a00-ffffffff814b4a53: crypto_unregister_algs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int crypto_unregister_algs(struct crypto_alg *algs, int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/algapi.c (0)
Location: crypto/algapi.c:459
Inline: False
Direct callers:
  - crypto/crypto_null.c:crypto_null_mod_fini
  - crypto/crypto_null.c:crypto_null_mod_init
```
**Symbols:**

```
ffffffff814cde5c-ffffffff814cde7a: crypto_unregister_algs.cold (STB_LOCAL)
ffffffff814cd480-ffffffff814cd4d3: crypto_unregister_algs (STB_GLOBAL)
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
