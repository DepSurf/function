# Function: <code>crypto_stats_decompress</code>

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
void crypto_stats_decompress(unsigned int slen, int ret, struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff81478240)
Location: crypto/algapi.c:1196
Inline: False
```
**Symbols:**

```
ffffffff81478240-ffffffff81478294: crypto_stats_decompress (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void crypto_stats_decompress(unsigned int slen, int ret, struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff814a5ff0)
Location: crypto/algapi.c:1165
Inline: False
```
**Symbols:**

```
ffffffff814a5ff0-ffffffff814a6045: crypto_stats_decompress (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void crypto_stats_decompress(unsigned int slen, int ret, struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff814bf790)
Location: crypto/algapi.c:1175
Inline: False
```
**Symbols:**

```
ffffffff814bf790-ffffffff814bf7e5: crypto_stats_decompress (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void crypto_stats_decompress(unsigned int slen, int ret, struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff81521310)
Location: crypto/algapi.c:1147
Inline: False
```
**Symbols:**

```
ffffffff81521310-ffffffff81521380: crypto_stats_decompress (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void crypto_stats_decompress(unsigned int slen, int ret, struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff8153e360)
Location: crypto/algapi.c:1166
Inline: False
Direct callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_writeback_entry
```
**Symbols:**

```
ffffffff8153e360-ffffffff8153e3d0: crypto_stats_decompress (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void crypto_stats_decompress(unsigned int slen, int ret, struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff81546a40)
Location: crypto/algapi.c:1166
Inline: False
Direct callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_writeback_entry
```
**Symbols:**

```
ffffffff81546a40-ffffffff81546ab0: crypto_stats_decompress (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void crypto_stats_decompress(unsigned int slen, int ret, struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff815a6f10)
Location: crypto/algapi.c:1148
Inline: True
Direct callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_writeback_entry
```
**Symbols:**

```
ffffffff815a6f10-ffffffff815a6f80: crypto_stats_decompress (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void crypto_stats_decompress(unsigned int slen, int ret, struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff8164e4a0)
Location: crypto/algapi.c:1190
Inline: False
Direct callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_writeback_entry
```
**Symbols:**

```
ffffffff8164e4a0-ffffffff8164e534: crypto_stats_decompress (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void crypto_stats_decompress(unsigned int slen, int ret, struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff81707770)
Location: crypto/algapi.c:1138
Inline: False
Direct callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_writeback_entry
```
**Symbols:**

```
ffffffff81707770-ffffffff81707804: crypto_stats_decompress (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void crypto_stats_decompress(unsigned int slen, int ret, struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffff8000105b9e40)
Location: crypto/algapi.c:1175
Inline: False
```
**Symbols:**

```
ffff8000105b9e40-ffff8000105b9f0c: crypto_stats_decompress (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void crypto_stats_decompress(unsigned int slen, int ret, struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (c076909c)
Location: crypto/algapi.c:1175
Inline: False
```
**Symbols:**

```
c076909c-c0769168: crypto_stats_decompress (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void crypto_stats_decompress(unsigned int slen, int ret, struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (c000000000740a60)
Location: crypto/algapi.c:1175
Inline: False
```
**Symbols:**

```
c000000000740a60-c000000000740b68: crypto_stats_decompress (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void crypto_stats_decompress(unsigned int slen, int ret, struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffe000400842)
Location: crypto/algapi.c:1175
Inline: False
```
**Symbols:**

```
ffffffe000400842-ffffffe0004008e0: crypto_stats_decompress (STB_GLOBAL)
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
void crypto_stats_decompress(unsigned int slen, int ret, struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff814b7d70)
Location: crypto/algapi.c:1175
Inline: False
```
**Symbols:**

```
ffffffff814b7d70-ffffffff814b7dc5: crypto_stats_decompress (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void crypto_stats_decompress(unsigned int slen, int ret, struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff814a8790)
Location: crypto/algapi.c:1175
Inline: False
```
**Symbols:**

```
ffffffff814a8790-ffffffff814a87e5: crypto_stats_decompress (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void crypto_stats_decompress(unsigned int slen, int ret, struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff814b3e00)
Location: crypto/algapi.c:1175
Inline: False
```
**Symbols:**

```
ffffffff814b3e00-ffffffff814b3e55: crypto_stats_decompress (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void crypto_stats_decompress(unsigned int slen, int ret, struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff814cc880)
Location: crypto/algapi.c:1175
Inline: False
```
**Symbols:**

```
ffffffff814cc880-ffffffff814cc8d5: crypto_stats_decompress (STB_GLOBAL)
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
