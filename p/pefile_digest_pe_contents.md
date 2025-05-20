# Function: <code>pefile_digest_pe_contents</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/verify_pefile.c (ffffffff813af5bd)
Location: crypto/asymmetric_keys/verify_pefile.c:245
Inline: True
Inline callers:
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/verify_pefile.c (ffffffff813f3605)
Location: crypto/asymmetric_keys/verify_pefile.c:245
Inline: True
Inline callers:
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/verify_pefile.c (ffffffff8140ce75)
Location: crypto/asymmetric_keys/verify_pefile.c:245
Inline: True
Inline callers:
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/verify_pefile.c (ffffffff8141a644)
Location: crypto/asymmetric_keys/verify_pefile.c:245
Inline: True
Inline callers:
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/verify_pefile.c (ffffffff8144577a)
Location: crypto/asymmetric_keys/verify_pefile.c:245
Inline: True
Inline callers:
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/verify_pefile.c (ffffffff814785e1)
Location: crypto/asymmetric_keys/verify_pefile.c:245
Inline: True
Inline callers:
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/verify_pefile.c (ffffffff81496812)
Location: crypto/asymmetric_keys/verify_pefile.c:245
Inline: True
Inline callers:
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int pefile_digest_pe_contents(const void *pebuf, unsigned int pelen, struct pefile_context *ctx, struct shash_desc *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/verify_pefile.c (ffffffff814c3cf0)
Location: crypto/asymmetric_keys/verify_pefile.c:241
Inline: False
Direct callers:
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
```
**Symbols:**

```
ffffffff814c3cf0-ffffffff814c3fc2: pefile_digest_pe_contents (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int pefile_digest_pe_contents(const void *pebuf, unsigned int pelen, struct pefile_context *ctx, struct shash_desc *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/verify_pefile.c (ffffffff814dcbd0)
Location: crypto/asymmetric_keys/verify_pefile.c:241
Inline: False
Direct callers:
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
```
**Symbols:**

```
ffffffff814dcbd0-ffffffff814dcea2: pefile_digest_pe_contents (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int pefile_digest_pe_contents(const void *pebuf, unsigned int pelen, struct pefile_context *ctx, struct shash_desc *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/verify_pefile.c (ffffffff8153c9a0)
Location: crypto/asymmetric_keys/verify_pefile.c:241
Inline: False
Direct callers:
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
```
**Symbols:**

```
ffffffff8153c9a0-ffffffff8153cc72: pefile_digest_pe_contents (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int pefile_digest_pe_contents(const void *pebuf, unsigned int pelen, struct pefile_context *ctx, struct shash_desc *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/verify_pefile.c (ffffffff81559500)
Location: crypto/asymmetric_keys/verify_pefile.c:241
Inline: False
Direct callers:
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
```
**Symbols:**

```
ffffffff81559500-ffffffff815597d2: pefile_digest_pe_contents (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int pefile_digest_pe_contents(const void *pebuf, unsigned int pelen, struct pefile_context *ctx, struct shash_desc *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/verify_pefile.c (ffffffff81561e30)
Location: crypto/asymmetric_keys/verify_pefile.c:241
Inline: False
Direct callers:
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
```
**Symbols:**

```
ffffffff81561e30-ffffffff815620e6: pefile_digest_pe_contents (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int pefile_digest_pe_contents(const void *pebuf, unsigned int pelen, struct pefile_context *ctx, struct shash_desc *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/verify_pefile.c (ffffffff815c3240)
Location: crypto/asymmetric_keys/verify_pefile.c:241
Inline: False
Direct callers:
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
```
**Symbols:**

```
ffffffff815c3240-ffffffff815c34f6: pefile_digest_pe_contents (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int pefile_digest_pe_contents(const void *pebuf, unsigned int pelen, struct pefile_context *ctx, struct shash_desc *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/verify_pefile.c (ffffffff8166d7f0)
Location: crypto/asymmetric_keys/verify_pefile.c:241
Inline: False
Direct callers:
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
```
**Symbols:**

```
ffffffff8166d7f0-ffffffff8166dad5: pefile_digest_pe_contents (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int pefile_digest_pe_contents(const void *pebuf, unsigned int pelen, struct pefile_context *ctx, struct shash_desc *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/verify_pefile.c (ffffffff817288c0)
Location: crypto/asymmetric_keys/verify_pefile.c:241
Inline: False
Direct callers:
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
```
**Symbols:**

```
ffffffff817288c0-ffffffff81728bb2: pefile_digest_pe_contents (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int pefile_digest_pe_contents(const void *pebuf, unsigned int pelen, struct pefile_context *ctx, struct shash_desc *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/verify_pefile.c (ffffffff81764bf0)
Location: crypto/asymmetric_keys/verify_pefile.c:245
Inline: False
Direct callers:
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
```
**Symbols:**

```
ffffffff81764bf0-ffffffff81764ee2: pefile_digest_pe_contents (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int pefile_digest_pe_contents(const void *pebuf, unsigned int pelen, struct pefile_context *ctx, struct shash_desc *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/verify_pefile.c (ffffffff817a6810)
Location: crypto/asymmetric_keys/verify_pefile.c:245
Inline: False
Direct callers:
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
```
**Symbols:**

```
ffffffff817a6810-ffffffff817a6b02: pefile_digest_pe_contents (STB_LOCAL)
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
int pefile_digest_pe_contents(const void *pebuf, unsigned int pelen, struct pefile_context *ctx, struct shash_desc *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/verify_pefile.c (ffff8000105d9140)
Location: crypto/asymmetric_keys/verify_pefile.c:241
Inline: False
Direct callers:
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
```
**Symbols:**

```
ffff8000105d9140-ffff8000105d9408: pefile_digest_pe_contents (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int pefile_digest_pe_contents(const void *pebuf, unsigned int pelen, struct pefile_context *ctx, struct shash_desc *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/verify_pefile.c (c0786658)
Location: crypto/asymmetric_keys/verify_pefile.c:241
Inline: False
Direct callers:
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
```
**Symbols:**

```
c0786658-c0786954: pefile_digest_pe_contents (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int pefile_digest_pe_contents(const void *pebuf, unsigned int pelen, struct pefile_context *ctx, struct shash_desc *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/verify_pefile.c (c000000000768f20)
Location: crypto/asymmetric_keys/verify_pefile.c:241
Inline: False
Direct callers:
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
```
**Symbols:**

```
c000000000768f20-c00000000076941c: pefile_digest_pe_contents (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/verify_pefile.c (ffffffe00041cfe6)
Location: crypto/asymmetric_keys/verify_pefile.c:241
Inline: True
Inline callers:
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
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
int pefile_digest_pe_contents(const void *pebuf, unsigned int pelen, struct pefile_context *ctx, struct shash_desc *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/verify_pefile.c (ffffffff814d51b0)
Location: crypto/asymmetric_keys/verify_pefile.c:241
Inline: False
Direct callers:
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
```
**Symbols:**

```
ffffffff814d51b0-ffffffff814d5482: pefile_digest_pe_contents (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int pefile_digest_pe_contents(const void *pebuf, unsigned int pelen, struct pefile_context *ctx, struct shash_desc *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/verify_pefile.c (ffffffff814c5bd0)
Location: crypto/asymmetric_keys/verify_pefile.c:241
Inline: False
Direct callers:
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
```
**Symbols:**

```
ffffffff814c5bd0-ffffffff814c5ea2: pefile_digest_pe_contents (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int pefile_digest_pe_contents(const void *pebuf, unsigned int pelen, struct pefile_context *ctx, struct shash_desc *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/verify_pefile.c (ffffffff814d1240)
Location: crypto/asymmetric_keys/verify_pefile.c:241
Inline: False
Direct callers:
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
```
**Symbols:**

```
ffffffff814d1240-ffffffff814d1512: pefile_digest_pe_contents (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int pefile_digest_pe_contents(const void *pebuf, unsigned int pelen, struct pefile_context *ctx, struct shash_desc *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/verify_pefile.c (ffffffff814e9cf0)
Location: crypto/asymmetric_keys/verify_pefile.c:241
Inline: False
Direct callers:
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
```
**Symbols:**

```
ffffffff814e9cf0-ffffffff814e9fc2: pefile_digest_pe_contents (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
