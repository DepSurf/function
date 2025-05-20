# Function: <code>ZSTD_decompressBegin_usingDict</code>

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
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
size_t ZSTD_decompressBegin_usingDict(ZSTD_DCtx *dctx, const void *dict, size_t dictSize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (ffffffff814b71d1)
Location: lib/zstd/decompress.c:1968
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_decompressDCtx
Direct callers:
  - lib/zstd/decompress.c:ZSTD_decompressStream
```
**Symbols:**

```
ffffffff814b1580-ffffffff814b16df: ZSTD_decompressBegin_usingDict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
size_t ZSTD_decompressBegin_usingDict(ZSTD_DCtx *dctx, const void *dict, size_t dictSize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (ffffffff814e5ff0)
Location: lib/zstd/decompress.c:1968
Inline: True
Direct callers:
  - lib/zstd/decompress.c:ZSTD_decompressDCtx
```
**Symbols:**

```
ffffffff814e5ff0-ffffffff814e614f: ZSTD_decompressBegin_usingDict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
size_t ZSTD_decompressBegin_usingDict(ZSTD_DCtx *dctx, const void *dict, size_t dictSize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (ffffffff814f9ce0)
Location: lib/zstd/decompress.c:1968
Inline: True
Direct callers:
  - lib/zstd/decompress.c:ZSTD_decompressDCtx
```
**Symbols:**

```
ffffffff814f9ce0-ffffffff814f9e3f: ZSTD_decompressBegin_usingDict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
size_t ZSTD_decompressBegin_usingDict(ZSTD_DCtx *dctx, const void *dict, size_t dictSize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (ffffffff81527320)
Location: lib/zstd/decompress.c:1969
Inline: True
Direct callers:
  - lib/zstd/decompress.c:ZSTD_decompressDCtx
  - lib/zstd/decompress.c:ZSTD_decompressMultiFrame
```
**Symbols:**

```
ffffffff81527320-ffffffff81527494: ZSTD_decompressBegin_usingDict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
size_t ZSTD_decompressBegin_usingDict(ZSTD_DCtx *dctx, const void *dict, size_t dictSize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (ffffffff815481b0)
Location: lib/zstd/decompress.c:1969
Inline: True
Direct callers:
  - lib/zstd/decompress.c:ZSTD_decompressDCtx
  - lib/zstd/decompress.c:ZSTD_decompressMultiFrame
```
**Symbols:**

```
ffffffff815481b0-ffffffff81548324: ZSTD_decompressBegin_usingDict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
size_t ZSTD_decompressBegin_usingDict(ZSTD_DCtx *dctx, const void *dict, size_t dictSize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (ffffffff815d3b00)
Location: lib/zstd/decompress.c:1969
Inline: True
Direct callers:
  - lib/zstd/decompress.c:ZSTD_decompressMultiFrame
```
**Symbols:**

```
ffffffff815d3b00-ffffffff815d3c75: ZSTD_decompressBegin_usingDict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
size_t ZSTD_decompressBegin_usingDict(ZSTD_DCtx *dctx, const void *dict, size_t dictSize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (ffffffff815f19d0)
Location: lib/zstd/decompress.c:1969
Inline: True
Direct callers:
  - lib/zstd/decompress.c:ZSTD_decompressMultiFrame
```
**Symbols:**

```
ffffffff815f19d0-ffffffff815f1b4a: ZSTD_decompressBegin_usingDict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
size_t ZSTD_decompressBegin_usingDict(ZSTD_DCtx *dctx, const void *dict, size_t dictSize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (ffffffff815d3290)
Location: lib/zstd/decompress.c:1969
Inline: True
Direct callers:
  - lib/zstd/decompress.c:ZSTD_decompressMultiFrame
```
**Symbols:**

```
ffffffff815d3290-ffffffff815d3411: ZSTD_decompressBegin_usingDict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
size_t ZSTD_decompressBegin_usingDict(ZSTD_DCtx *dctx, const void *dict, size_t dictSize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (ffffffff8163de30)
Location: lib/zstd/decompress.c:1969
Inline: True
Direct callers:
  - lib/zstd/decompress.c:ZSTD_decompressMultiFrame
```
**Symbols:**

```
ffffffff8163de30-ffffffff8163dfb1: ZSTD_decompressBegin_usingDict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
size_t ZSTD_decompressBegin_usingDict(ZSTD_DCtx *dctx, const void *dict, size_t dictSize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress/zstd_decompress.c (ffffffff81752e50)
Location: lib/zstd/decompress/zstd_decompress.c:1354
Inline: True
Direct callers:
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_decompressMultiFrame
```
**Symbols:**

```
ffffffff81752e50-ffffffff81752ff4: ZSTD_decompressBegin_usingDict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
size_t ZSTD_decompressBegin_usingDict(ZSTD_DCtx *dctx, const void *dict, size_t dictSize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress/zstd_decompress.c (ffffffff81877340)
Location: lib/zstd/decompress/zstd_decompress.c:1400
Inline: True
Direct callers:
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_decompressMultiFrame
```
**Symbols:**

```
ffffffff81877340-ffffffff818774e4: ZSTD_decompressBegin_usingDict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
size_t ZSTD_decompressBegin_usingDict(ZSTD_DCtx *dctx, const void *dict, size_t dictSize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress/zstd_decompress.c (ffffffff818b80f0)
Location: lib/zstd/decompress/zstd_decompress.c:1419
Inline: True
Direct callers:
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_decompressMultiFrame
```
**Symbols:**

```
ffffffff818b80f0-ffffffff818b8294: ZSTD_decompressBegin_usingDict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
size_t ZSTD_decompressBegin_usingDict(ZSTD_DCtx *dctx, const void *dict, size_t dictSize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress/zstd_decompress.c (ffffffff81909cb0)
Location: lib/zstd/decompress/zstd_decompress.c:1419
Inline: True
Direct callers:
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_decompressMultiFrame
```
**Symbols:**

```
ffffffff81909cb0-ffffffff81909e54: ZSTD_decompressBegin_usingDict (STB_GLOBAL)
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
size_t ZSTD_decompressBegin_usingDict(ZSTD_DCtx *dctx, const void *dict, size_t dictSize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (ffff800010654420)
Location: lib/zstd/decompress.c:1969
Inline: True
Direct callers:
  - lib/zstd/decompress.c:ZSTD_decompressDCtx
  - lib/zstd/decompress.c:ZSTD_decompressMultiFrame
```
**Symbols:**

```
ffff800010654420-ffff800010654568: ZSTD_decompressBegin_usingDict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
size_t ZSTD_decompressBegin_usingDict(ZSTD_DCtx *dctx, const void *dict, size_t dictSize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (c07ff4a4)
Location: lib/zstd/decompress.c:1969
Inline: True
Direct callers:
  - lib/zstd/decompress.c:ZSTD_decompressDCtx
  - lib/zstd/decompress.c:ZSTD_decompressMultiFrame
```
**Symbols:**

```
c07ff4a4-c07ff604: ZSTD_decompressBegin_usingDict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
size_t ZSTD_decompressBegin_usingDict(ZSTD_DCtx *dctx, const void *dict, size_t dictSize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (c000000000804160)
Location: lib/zstd/decompress.c:1969
Inline: True
Direct callers:
  - lib/zstd/decompress.c:ZSTD_decompressDCtx
  - lib/zstd/decompress.c:ZSTD_decompressMultiFrame
```
**Symbols:**

```
c000000000804160-c000000000804310: ZSTD_decompressBegin_usingDict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
size_t ZSTD_decompressBegin_usingDict(ZSTD_DCtx *dctx, const void *dict, size_t dictSize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (ffffffe000482184)
Location: lib/zstd/decompress.c:1969
Inline: True
Direct callers:
  - lib/zstd/decompress.c:ZSTD_decompressDCtx
  - lib/zstd/decompress.c:ZSTD_decompressMultiFrame
```
**Symbols:**

```
ffffffe000482184-ffffffe00048232a: ZSTD_decompressBegin_usingDict (STB_GLOBAL)
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
size_t ZSTD_decompressBegin_usingDict(ZSTD_DCtx *dctx, const void *dict, size_t dictSize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (ffffffff81540790)
Location: lib/zstd/decompress.c:1969
Inline: True
Direct callers:
  - lib/zstd/decompress.c:ZSTD_decompressDCtx
  - lib/zstd/decompress.c:ZSTD_decompressMultiFrame
```
**Symbols:**

```
ffffffff81540790-ffffffff81540904: ZSTD_decompressBegin_usingDict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
size_t ZSTD_decompressBegin_usingDict(ZSTD_DCtx *dctx, const void *dict, size_t dictSize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (ffffffff81530a70)
Location: lib/zstd/decompress.c:1969
Inline: True
Direct callers:
  - lib/zstd/decompress.c:ZSTD_decompressDCtx
  - lib/zstd/decompress.c:ZSTD_decompressMultiFrame
```
**Symbols:**

```
ffffffff81530a70-ffffffff81530be4: ZSTD_decompressBegin_usingDict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
size_t ZSTD_decompressBegin_usingDict(ZSTD_DCtx *dctx, const void *dict, size_t dictSize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (ffffffff8153c4d0)
Location: lib/zstd/decompress.c:1969
Inline: True
Direct callers:
  - lib/zstd/decompress.c:ZSTD_decompressDCtx
  - lib/zstd/decompress.c:ZSTD_decompressMultiFrame
```
**Symbols:**

```
ffffffff8153c4d0-ffffffff8153c644: ZSTD_decompressBegin_usingDict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
size_t ZSTD_decompressBegin_usingDict(ZSTD_DCtx *dctx, const void *dict, size_t dictSize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (ffffffff81556300)
Location: lib/zstd/decompress.c:1969
Inline: True
Direct callers:
  - lib/zstd/decompress.c:ZSTD_decompressDCtx
  - lib/zstd/decompress.c:ZSTD_decompressMultiFrame
```
**Symbols:**

```
ffffffff81556300-ffffffff81556474: ZSTD_decompressBegin_usingDict (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
