# Function: <code>ZSTD_decompressMultiFrame</code>

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
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (ffffffff814b81bb)
Location: lib/zstd/decompress.c:1643
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_decompressStream
  - lib/zstd/decompress.c:ZSTD_decompressDCtx
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
size_t ZSTD_decompressMultiFrame(ZSTD_DCtx *dctx, void *dst, size_t dstCapacity, const void *src, size_t srcSize, const void *dict, size_t dictSize, const ZSTD_DDict *ddict);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (ffffffff814eac60)
Location: lib/zstd/decompress.c:1643
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_decompressDCtx
Direct callers:
  - lib/zstd/decompress.c:ZSTD_decompressStream
```
**Symbols:**

```
ffffffff814e9f00-ffffffff814ea4c4: ZSTD_decompressMultiFrame (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
size_t ZSTD_decompressMultiFrame(ZSTD_DCtx *dctx, void *dst, size_t dstCapacity, const void *src, size_t srcSize, const void *dict, size_t dictSize, const ZSTD_DDict *ddict);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (ffffffff814fe9b0)
Location: lib/zstd/decompress.c:1643
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_decompressDCtx
Direct callers:
  - lib/zstd/decompress.c:ZSTD_decompressStream
```
**Symbols:**

```
ffffffff814fdc10-ffffffff814fe1d4: ZSTD_decompressMultiFrame (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
size_t ZSTD_decompressMultiFrame(ZSTD_DCtx *dctx, void *dst, size_t dstCapacity, const void *src, size_t srcSize, const void *dict, size_t dictSize, const ZSTD_DDict *ddict);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (ffffffff8152c590)
Location: lib/zstd/decompress.c:1643
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_decompressDCtx
Direct callers:
  - lib/zstd/decompress.c:ZSTD_decompressStream
```
**Symbols:**

```
ffffffff8152b890-ffffffff8152be58: ZSTD_decompressMultiFrame (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
size_t ZSTD_decompressMultiFrame(ZSTD_DCtx *dctx, void *dst, size_t dstCapacity, const void *src, size_t srcSize, const void *dict, size_t dictSize, const ZSTD_DDict *ddict);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (ffffffff8154d420)
Location: lib/zstd/decompress.c:1643
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_decompressDCtx
Direct callers:
  - lib/zstd/decompress.c:ZSTD_decompressStream
```
**Symbols:**

```
ffffffff8154c720-ffffffff8154cce8: ZSTD_decompressMultiFrame (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
size_t ZSTD_decompressMultiFrame(ZSTD_DCtx *dctx, void *dst, size_t dstCapacity, const void *src, size_t srcSize, const void *dict, size_t dictSize, const ZSTD_DDict *ddict);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (ffffffff815d7c70)
Location: lib/zstd/decompress.c:1643
Inline: False
Direct callers:
  - lib/zstd/decompress.c:ZSTD_decompressStream
  - lib/zstd/decompress.c:ZSTD_decompressDCtx
```
**Symbols:**

```
ffffffff815d7c70-ffffffff815d8238: ZSTD_decompressMultiFrame (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
size_t ZSTD_decompressMultiFrame(ZSTD_DCtx *dctx, void *dst, size_t dstCapacity, const void *src, size_t srcSize, const void *dict, size_t dictSize, const ZSTD_DDict *ddict);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (ffffffff815f5870)
Location: lib/zstd/decompress.c:1643
Inline: False
Direct callers:
  - lib/zstd/decompress.c:ZSTD_decompressStream
  - lib/zstd/decompress.c:ZSTD_decompressDCtx
```
**Symbols:**

```
ffffffff815f5870-ffffffff815f5e3d: ZSTD_decompressMultiFrame (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
size_t ZSTD_decompressMultiFrame(ZSTD_DCtx *dctx, void *dst, size_t dstCapacity, const void *src, size_t srcSize, const void *dict, size_t dictSize, const ZSTD_DDict *ddict);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (ffffffff815d7050)
Location: lib/zstd/decompress.c:1643
Inline: False
Direct callers:
  - lib/zstd/decompress.c:ZSTD_decompressStream
  - lib/zstd/decompress.c:ZSTD_decompressDCtx
```
**Symbols:**

```
ffffffff815d7050-ffffffff815d75c3: ZSTD_decompressMultiFrame (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
size_t ZSTD_decompressMultiFrame(ZSTD_DCtx *dctx, void *dst, size_t dstCapacity, const void *src, size_t srcSize, const void *dict, size_t dictSize, const ZSTD_DDict *ddict);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (ffffffff816422d0)
Location: lib/zstd/decompress.c:1643
Inline: False
Direct callers:
  - lib/zstd/decompress.c:ZSTD_decompressStream
  - lib/zstd/decompress.c:ZSTD_decompressDCtx
```
**Symbols:**

```
ffffffff816422d0-ffffffff81642870: ZSTD_decompressMultiFrame (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
size_t ZSTD_decompressMultiFrame(ZSTD_DCtx *dctx, void *dst, size_t dstCapacity, const void *src, size_t srcSize, const void *dict, size_t dictSize, const ZSTD_DDict *ddict);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress/zstd_decompress.c (ffffffff81753130)
Location: lib/zstd/decompress/zstd_decompress.c:873
Inline: False
Direct callers:
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_decompressStream
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_decompress
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_decompress_usingDict
```
**Symbols:**

```
ffffffff81753130-ffffffff817532b3: ZSTD_decompressMultiFrame (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
size_t ZSTD_decompressMultiFrame(ZSTD_DCtx *dctx, void *dst, size_t dstCapacity, const void *src, size_t srcSize, const void *dict, size_t dictSize, const ZSTD_DDict *ddict);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress/zstd_decompress.c (ffffffff81877640)
Location: lib/zstd/decompress/zstd_decompress.c:919
Inline: False
Direct callers:
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_decompressStream
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_decompress
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_decompress_usingDict
```
**Symbols:**

```
ffffffff81877640-ffffffff818777c3: ZSTD_decompressMultiFrame (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
size_t ZSTD_decompressMultiFrame(ZSTD_DCtx *dctx, void *dst, size_t dstCapacity, const void *src, size_t srcSize, const void *dict, size_t dictSize, const ZSTD_DDict *ddict);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress/zstd_decompress.c (ffffffff818b83f0)
Location: lib/zstd/decompress/zstd_decompress.c:938
Inline: False
Direct callers:
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_decompressStream
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_decompress
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_decompress_usingDict
```
**Symbols:**

```
ffffffff818b83f0-ffffffff818b8574: ZSTD_decompressMultiFrame (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
size_t ZSTD_decompressMultiFrame(ZSTD_DCtx *dctx, void *dst, size_t dstCapacity, const void *src, size_t srcSize, const void *dict, size_t dictSize, const ZSTD_DDict *ddict);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress/zstd_decompress.c (ffffffff81909fb0)
Location: lib/zstd/decompress/zstd_decompress.c:938
Inline: False
Direct callers:
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_decompressStream
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_decompress
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_decompress_usingDict
```
**Symbols:**

```
ffffffff81909fb0-ffffffff8190a134: ZSTD_decompressMultiFrame (STB_LOCAL)
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
size_t ZSTD_decompressMultiFrame(ZSTD_DCtx *dctx, void *dst, size_t dstCapacity, const void *src, size_t srcSize, const void *dict, size_t dictSize, const ZSTD_DDict *ddict);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (ffff800010659410)
Location: lib/zstd/decompress.c:1643
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_decompressDCtx
Direct callers:
  - lib/zstd/decompress.c:ZSTD_decompressStream
```
**Symbols:**

```
ffff8000106587f8-ffff800010658db0: ZSTD_decompressMultiFrame (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
size_t ZSTD_decompressMultiFrame(ZSTD_DCtx *dctx, void *dst, size_t dstCapacity, const void *src, size_t srcSize, const void *dict, size_t dictSize, const ZSTD_DDict *ddict);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (c0802c70)
Location: lib/zstd/decompress.c:1643
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_decompressDCtx
Direct callers:
  - lib/zstd/decompress.c:ZSTD_decompressStream
```
**Symbols:**

```
c0801fbc-c0802554: ZSTD_decompressMultiFrame (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
size_t ZSTD_decompressMultiFrame(ZSTD_DCtx *dctx, void *dst, size_t dstCapacity, const void *src, size_t srcSize, const void *dict, size_t dictSize, const ZSTD_DDict *ddict);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (c000000000809e2c)
Location: lib/zstd/decompress.c:1643
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_decompressDCtx
Direct callers:
  - lib/zstd/decompress.c:ZSTD_decompressStream
```
**Symbols:**

```
c000000000808ee0-c0000000008095f4: ZSTD_decompressMultiFrame (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
size_t ZSTD_decompressMultiFrame(ZSTD_DCtx *dctx, void *dst, size_t dstCapacity, const void *src, size_t srcSize, const void *dict, size_t dictSize, const ZSTD_DDict *ddict);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (ffffffe000486fea)
Location: lib/zstd/decompress.c:1643
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_decompressDCtx
Direct callers:
  - lib/zstd/decompress.c:ZSTD_decompressStream
```
**Symbols:**

```
ffffffe00048658c-ffffffe000486a6a: ZSTD_decompressMultiFrame (STB_LOCAL)
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
size_t ZSTD_decompressMultiFrame(ZSTD_DCtx *dctx, void *dst, size_t dstCapacity, const void *src, size_t srcSize, const void *dict, size_t dictSize, const ZSTD_DDict *ddict);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (ffffffff81545a00)
Location: lib/zstd/decompress.c:1643
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_decompressDCtx
Direct callers:
  - lib/zstd/decompress.c:ZSTD_decompressStream
```
**Symbols:**

```
ffffffff81544d00-ffffffff815452c8: ZSTD_decompressMultiFrame (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
size_t ZSTD_decompressMultiFrame(ZSTD_DCtx *dctx, void *dst, size_t dstCapacity, const void *src, size_t srcSize, const void *dict, size_t dictSize, const ZSTD_DDict *ddict);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (ffffffff81535ce0)
Location: lib/zstd/decompress.c:1643
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_decompressDCtx
Direct callers:
  - lib/zstd/decompress.c:ZSTD_decompressStream
```
**Symbols:**

```
ffffffff81534fe0-ffffffff815355a8: ZSTD_decompressMultiFrame (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
size_t ZSTD_decompressMultiFrame(ZSTD_DCtx *dctx, void *dst, size_t dstCapacity, const void *src, size_t srcSize, const void *dict, size_t dictSize, const ZSTD_DDict *ddict);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (ffffffff81541740)
Location: lib/zstd/decompress.c:1643
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_decompressDCtx
Direct callers:
  - lib/zstd/decompress.c:ZSTD_decompressStream
```
**Symbols:**

```
ffffffff81540a40-ffffffff81541008: ZSTD_decompressMultiFrame (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
size_t ZSTD_decompressMultiFrame(ZSTD_DCtx *dctx, void *dst, size_t dstCapacity, const void *src, size_t srcSize, const void *dict, size_t dictSize, const ZSTD_DDict *ddict);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (ffffffff8155b570)
Location: lib/zstd/decompress.c:1643
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_decompressDCtx
Direct callers:
  - lib/zstd/decompress.c:ZSTD_decompressStream
```
**Symbols:**

```
ffffffff8155a870-ffffffff8155ae38: ZSTD_decompressMultiFrame (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
