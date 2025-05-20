# Function: <code>sha224_final</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int sha224_final(struct sha256_state *sctx, u8 *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/crypto/sha256.c (ffffffff81531450)
Location: lib/crypto/sha256.c:281
Inline: False
Direct callers:
  - crypto/sha256_generic.c:crypto_sha256_final
```
**Symbols:**

```
ffffffff81531450-ffffffff81531460: sha224_final (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void sha224_final(struct sha256_state *sctx, u8 *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/crypto/sha256.c (ffffffff81595640)
Location: lib/crypto/sha256.c:277
Inline: False
Direct callers:
  - crypto/sha256_generic.c:crypto_sha256_finup
```
**Symbols:**

```
ffffffff81595640-ffffffff81595650: sha224_final (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void sha224_final(struct sha256_state *sctx, u8 *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/crypto/sha256.c (ffffffff815b0fb0)
Location: lib/crypto/sha256.c:193
Inline: False
Direct callers:
  - crypto/sha256_generic.c:crypto_sha256_finup
```
**Symbols:**

```
ffffffff815b0fb0-ffffffff815b0fc5: sha224_final (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void sha224_final(struct sha256_state *sctx, u8 *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/crypto/sha256.c (ffffffff815bbdc0)
Location: lib/crypto/sha256.c:193
Inline: False
Direct callers:
  - crypto/sha256_generic.c:crypto_sha256_finup
```
**Symbols:**

```
ffffffff815bbdc0-ffffffff815bbdd5: sha224_final (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void sha224_final(struct sha256_state *sctx, u8 *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/crypto/sha256.c (ffffffff81622bf0)
Location: lib/crypto/sha256.c:193
Inline: False
Direct callers:
  - crypto/sha256_generic.c:crypto_sha256_finup
```
**Symbols:**

```
ffffffff81622bf0-ffffffff81622c05: sha224_final (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void sha224_final(struct sha256_state *sctx, u8 *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/crypto/sha256.c (ffffffff816f2910)
Location: lib/crypto/sha256.c:193
Inline: False
Direct callers:
  - crypto/sha256_generic.c:crypto_sha256_finup
```
**Symbols:**

```
ffffffff816f2910-ffffffff816f2a10: sha224_final (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void sha224_final(struct sha256_state *sctx, u8 *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/crypto/sha256.c (ffffffff817e4730)
Location: lib/crypto/sha256.c:193
Inline: False
Direct callers:
  - crypto/sha256_generic.c:crypto_sha256_finup
```
**Symbols:**

```
ffffffff817e4730-ffffffff817e4830: sha224_final (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void sha224_final(struct sha256_state *sctx, u8 *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/crypto/sha256.c (ffffffff818248f0)
Location: lib/crypto/sha256.c:152
Inline: False
Direct callers:
  - crypto/sha256_generic.c:crypto_sha256_finup
```
**Symbols:**

```
ffffffff818248f0-ffffffff81824975: sha224_final (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void sha224_final(struct sha256_state *sctx, u8 *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/crypto/sha256.c (ffffffff8186a930)
Location: lib/crypto/sha256.c:152
Inline: False
Direct callers:
  - crypto/sha256_generic.c:crypto_sha256_finup
```
**Symbols:**

```
ffffffff8186a930-ffffffff8186a9b5: sha224_final (STB_GLOBAL)
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
int sha224_final(struct sha256_state *sctx, u8 *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/crypto/sha256.c (ffff80001063d500)
Location: lib/crypto/sha256.c:281
Inline: False
Direct callers:
  - crypto/sha256_generic.c:crypto_sha256_final
```
**Symbols:**

```
ffff80001063d500-ffff80001063d518: sha224_final (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int sha224_final(struct sha256_state *sctx, u8 *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/crypto/sha256.c (c07e3944)
Location: lib/crypto/sha256.c:281
Inline: False
Direct callers:
  - crypto/sha256_generic.c:crypto_sha256_final
```
**Symbols:**

```
c07e3944-c07e395c: sha224_final (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int sha224_final(struct sha256_state *sctx, u8 *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/crypto/sha256.c (c0000000007e4f00)
Location: lib/crypto/sha256.c:281
Inline: False
Direct callers:
  - crypto/sha256_generic.c:crypto_sha256_final
```
**Symbols:**

```
c0000000007e4f00-c0000000007e4f10: sha224_final (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int sha224_final(struct sha256_state *sctx, u8 *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/crypto/sha256.c (ffffffe00046b22e)
Location: lib/crypto/sha256.c:281
Inline: False
Direct callers:
  - crypto/sha256_generic.c:crypto_sha256_final
```
**Symbols:**

```
ffffffe00046b22e-ffffffe00046b248: sha224_final (STB_GLOBAL)
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
int sha224_final(struct sha256_state *sctx, u8 *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/crypto/sha256.c (ffffffff81529a30)
Location: lib/crypto/sha256.c:281
Inline: False
Direct callers:
  - crypto/sha256_generic.c:crypto_sha256_final
```
**Symbols:**

```
ffffffff81529a30-ffffffff81529a40: sha224_final (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int sha224_final(struct sha256_state *sctx, u8 *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/crypto/sha256.c (ffffffff81519d10)
Location: lib/crypto/sha256.c:281
Inline: False
Direct callers:
  - crypto/sha256_generic.c:crypto_sha256_final
```
**Symbols:**

```
ffffffff81519d10-ffffffff81519d20: sha224_final (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int sha224_final(struct sha256_state *sctx, u8 *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/crypto/sha256.c (ffffffff81525ac0)
Location: lib/crypto/sha256.c:281
Inline: False
Direct callers:
  - crypto/sha256_generic.c:crypto_sha256_final
```
**Symbols:**

```
ffffffff81525ac0-ffffffff81525ad0: sha224_final (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int sha224_final(struct sha256_state *sctx, u8 *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/crypto/sha256.c (ffffffff8153f440)
Location: lib/crypto/sha256.c:281
Inline: False
Direct callers:
  - crypto/sha256_generic.c:crypto_sha256_final
```
**Symbols:**

```
ffffffff8153f440-ffffffff8153f450: sha224_final (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
