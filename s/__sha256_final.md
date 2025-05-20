# Function: <code>__sha256_final</code>

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
int __sha256_final(struct sha256_state *sctx, u8 *out, int digest_words);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/crypto/sha256.c (ffffffff81531360)
Location: lib/crypto/sha256.c:246
Inline: False
Direct callers:
  - lib/crypto/sha256.c:sha224_final
  - lib/crypto/sha256.c:sha256_final
```
**Symbols:**

```
ffffffff81531360-ffffffff81531437: __sha256_final (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __sha256_final(struct sha256_state *sctx, u8 *out, int digest_words);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/crypto/sha256.c (ffffffff81595560)
Location: lib/crypto/sha256.c:244
Inline: False
Direct callers:
  - lib/crypto/sha256.c:sha224_final
  - lib/crypto/sha256.c:sha256_final
```
**Symbols:**

```
ffffffff81595560-ffffffff81595626: __sha256_final (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void __sha256_final(struct sha256_state *sctx, u8 *out, int digest_words);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/crypto/sha256.c (ffffffff815b1041)
Location: lib/crypto/sha256.c:160
Inline: True
Inline callers:
  - lib/crypto/sha256.c:sha256
Direct callers:
  - lib/crypto/sha256.c:sha224_final
```
**Symbols:**

```
ffffffff815b0ec0-ffffffff815b0f8e: __sha256_final (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void __sha256_final(struct sha256_state *sctx, u8 *out, int digest_words);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/crypto/sha256.c (ffffffff815bbe51)
Location: lib/crypto/sha256.c:160
Inline: True
Inline callers:
  - lib/crypto/sha256.c:sha256
Direct callers:
  - lib/crypto/sha256.c:sha224_final
```
**Symbols:**

```
ffffffff815bbcd0-ffffffff815bbd9e: __sha256_final (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void __sha256_final(struct sha256_state *sctx, u8 *out, int digest_words);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/crypto/sha256.c (ffffffff81622c89)
Location: lib/crypto/sha256.c:160
Inline: True
Inline callers:
  - lib/crypto/sha256.c:sha256
Direct callers:
  - lib/crypto/sha256.c:sha224_final
```
**Symbols:**

```
ffffffff81622ad0-ffffffff81622bc5: __sha256_final (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/crypto/sha256.c (ffffffff816f2841)
Location: lib/crypto/sha256.c:160
Inline: True
Inline callers:
  - lib/crypto/sha256.c:sha256
  - lib/crypto/sha256.c:sha224_final
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/crypto/sha256.c (ffffffff817e4651)
Location: lib/crypto/sha256.c:160
Inline: True
Inline callers:
  - lib/crypto/sha256.c:sha256
  - lib/crypto/sha256.c:sha224_final
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/crypto/sha256.c (ffffffff818247c3)
Location: lib/crypto/sha256.c:140
Inline: True
Inline callers:
  - lib/crypto/sha256.c:sha256
  - lib/crypto/sha256.c:sha224_final
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/crypto/sha256.c (ffffffff8186a803)
Location: lib/crypto/sha256.c:140
Inline: True
Inline callers:
  - lib/crypto/sha256.c:sha256
  - lib/crypto/sha256.c:sha224_final
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
int __sha256_final(struct sha256_state *sctx, u8 *out, int digest_words);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/crypto/sha256.c (ffff80001063d3c8)
Location: lib/crypto/sha256.c:246
Inline: False
Direct callers:
  - lib/crypto/sha256.c:sha224_final
  - lib/crypto/sha256.c:sha256_final
```
**Symbols:**

```
ffff80001063d3c8-ffff80001063d4e8: __sha256_final (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __sha256_final(struct sha256_state *sctx, u8 *out, int digest_words);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/crypto/sha256.c (c07e3838)
Location: lib/crypto/sha256.c:246
Inline: False
Direct callers:
  - lib/crypto/sha256.c:sha224_final
  - lib/crypto/sha256.c:sha256_final
```
**Symbols:**

```
c07e3838-c07e392c: __sha256_final (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __sha256_final(struct sha256_state *sctx, u8 *out, int digest_words);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/crypto/sha256.c (c0000000007e4db0)
Location: lib/crypto/sha256.c:246
Inline: False
Direct callers:
  - lib/crypto/sha256.c:sha224_final
  - lib/crypto/sha256.c:sha256_final
```
**Symbols:**

```
c0000000007e4db0-c0000000007e4ee4: __sha256_final (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __sha256_final(struct sha256_state *sctx, u8 *out, int digest_words);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/crypto/sha256.c (ffffffe00046b0f4)
Location: lib/crypto/sha256.c:246
Inline: False
Direct callers:
  - lib/crypto/sha256.c:sha224_final
  - lib/crypto/sha256.c:sha256_final
```
**Symbols:**

```
ffffffe00046b0f4-ffffffe00046b214: __sha256_final (STB_LOCAL)
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
int __sha256_final(struct sha256_state *sctx, u8 *out, int digest_words);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/crypto/sha256.c (ffffffff81529940)
Location: lib/crypto/sha256.c:246
Inline: False
Direct callers:
  - lib/crypto/sha256.c:sha224_final
  - lib/crypto/sha256.c:sha256_final
```
**Symbols:**

```
ffffffff81529940-ffffffff81529a17: __sha256_final (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __sha256_final(struct sha256_state *sctx, u8 *out, int digest_words);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/crypto/sha256.c (ffffffff81519c20)
Location: lib/crypto/sha256.c:246
Inline: False
Direct callers:
  - lib/crypto/sha256.c:sha224_final
  - lib/crypto/sha256.c:sha256_final
```
**Symbols:**

```
ffffffff81519c20-ffffffff81519cf7: __sha256_final (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __sha256_final(struct sha256_state *sctx, u8 *out, int digest_words);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/crypto/sha256.c (ffffffff815259d0)
Location: lib/crypto/sha256.c:246
Inline: False
Direct callers:
  - lib/crypto/sha256.c:sha224_final
  - lib/crypto/sha256.c:sha256_final
```
**Symbols:**

```
ffffffff815259d0-ffffffff81525aa7: __sha256_final (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __sha256_final(struct sha256_state *sctx, u8 *out, int digest_words);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/crypto/sha256.c (ffffffff8153f350)
Location: lib/crypto/sha256.c:246
Inline: False
Direct callers:
  - lib/crypto/sha256.c:sha224_final
  - lib/crypto/sha256.c:sha256_final
```
**Symbols:**

```
ffffffff8153f350-ffffffff8153f427: __sha256_final (STB_LOCAL)
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
