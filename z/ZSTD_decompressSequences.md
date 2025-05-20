# Function: <code>ZSTD_decompressSequences</code>

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
<summary>In <code>4.15</code>: ✅</summary>

```c
size_t ZSTD_decompressSequences(ZSTD_DCtx *dctx, void *dst, size_t maxDstSize, const void *seqStart, size_t seqSize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (ffffffff814b52e0)
Location: lib/zstd/decompress.c:1093
Inline: False
Direct callers:
  - lib/zstd/decompress.c:ZSTD_decompressStream
  - lib/zstd/decompress.c:ZSTD_decompressContinue
  - lib/zstd/decompress.c:ZSTD_decompressDCtx
  - lib/zstd/decompress.c:ZSTD_decompressBlock
```
**Symbols:**

```
ffffffff814b52e0-ffffffff814b5f04: ZSTD_decompressSequences (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
size_t ZSTD_decompressSequences(ZSTD_DCtx *dctx, void *dst, size_t maxDstSize, const void *seqStart, size_t seqSize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (ffffffff814e8ca0)
Location: lib/zstd/decompress.c:1093
Inline: False
Direct callers:
  - lib/zstd/decompress.c:ZSTD_decompressContinue
  - lib/zstd/decompress.c:ZSTD_decompressDCtx
  - lib/zstd/decompress.c:ZSTD_decompressBlock
```
**Symbols:**

```
ffffffff814e8ca0-ffffffff814e9935: ZSTD_decompressSequences (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
size_t ZSTD_decompressSequences(ZSTD_DCtx *dctx, void *dst, size_t maxDstSize, const void *seqStart, size_t seqSize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (ffffffff814fc980)
Location: lib/zstd/decompress.c:1093
Inline: False
Direct callers:
  - lib/zstd/decompress.c:ZSTD_decompressContinue
  - lib/zstd/decompress.c:ZSTD_decompressDCtx
  - lib/zstd/decompress.c:ZSTD_decompressBlock
```
**Symbols:**

```
ffffffff814fc980-ffffffff814fd638: ZSTD_decompressSequences (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
size_t ZSTD_decompressSequences(ZSTD_DCtx *dctx, void *dst, size_t maxDstSize, const void *seqStart, size_t seqSize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (ffffffff8152a160)
Location: lib/zstd/decompress.c:1093
Inline: False
Direct callers:
  - lib/zstd/decompress.c:ZSTD_decompressContinue
  - lib/zstd/decompress.c:ZSTD_decompressDCtx
  - lib/zstd/decompress.c:ZSTD_decompressBlock
```
**Symbols:**

```
ffffffff8152a160-ffffffff8152af0c: ZSTD_decompressSequences (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
size_t ZSTD_decompressSequences(ZSTD_DCtx *dctx, void *dst, size_t maxDstSize, const void *seqStart, size_t seqSize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (ffffffff8154aff0)
Location: lib/zstd/decompress.c:1093
Inline: False
Direct callers:
  - lib/zstd/decompress.c:ZSTD_decompressContinue
  - lib/zstd/decompress.c:ZSTD_decompressDCtx
  - lib/zstd/decompress.c:ZSTD_decompressBlock
```
**Symbols:**

```
ffffffff8154aff0-ffffffff8154bd9c: ZSTD_decompressSequences (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
size_t ZSTD_decompressSequences(ZSTD_DCtx *dctx, void *dst, size_t maxDstSize, const void *seqStart, size_t seqSize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (ffffffff815d68b0)
Location: lib/zstd/decompress.c:1093
Inline: False
Direct callers:
  - lib/zstd/decompress.c:ZSTD_decompressContinue
  - lib/zstd/decompress.c:ZSTD_decompressMultiFrame
  - lib/zstd/decompress.c:ZSTD_decompressBlock
```
**Symbols:**

```
ffffffff815d68b0-ffffffff815d7677: ZSTD_decompressSequences (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
size_t ZSTD_decompressSequences(ZSTD_DCtx *dctx, void *dst, size_t maxDstSize, const void *seqStart, size_t seqSize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (ffffffff815f4500)
Location: lib/zstd/decompress.c:1093
Inline: False
Direct callers:
  - lib/zstd/decompress.c:ZSTD_decompressContinue
  - lib/zstd/decompress.c:ZSTD_decompressMultiFrame
  - lib/zstd/decompress.c:ZSTD_decompressBlock
```
**Symbols:**

```
ffffffff815f4500-ffffffff815f5272: ZSTD_decompressSequences (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
size_t ZSTD_decompressSequences(ZSTD_DCtx *dctx, void *dst, size_t maxDstSize, const void *seqStart, size_t seqSize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (ffffffff815d5d00)
Location: lib/zstd/decompress.c:1093
Inline: False
Direct callers:
  - lib/zstd/decompress.c:ZSTD_decompressContinue
  - lib/zstd/decompress.c:ZSTD_decompressMultiFrame
  - lib/zstd/decompress.c:ZSTD_decompressBlock
```
**Symbols:**

```
ffffffff815d5d00-ffffffff815d6a5d: ZSTD_decompressSequences (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
size_t ZSTD_decompressSequences(ZSTD_DCtx *dctx, void *dst, size_t maxDstSize, const void *seqStart, size_t seqSize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (ffffffff81640cf0)
Location: lib/zstd/decompress.c:1093
Inline: False
Direct callers:
  - lib/zstd/decompress.c:ZSTD_decompressContinue
  - lib/zstd/decompress.c:ZSTD_decompressMultiFrame
  - lib/zstd/decompress.c:ZSTD_decompressBlock
```
**Symbols:**

```
ffffffff81640cf0-ffffffff81641ccd: ZSTD_decompressSequences (STB_LOCAL)
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
In lib/zstd/decompress/zstd_decompress_block.c (ffffffff8175a4e4)
Location: lib/zstd/decompress/zstd_decompress_block.c:1379
Inline: True
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
In lib/zstd/decompress/zstd_decompress_block.c (ffffffff81883d32)
Location: lib/zstd/decompress/zstd_decompress_block.c:1894
Inline: True
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
In lib/zstd/decompress/zstd_decompress_block.c (ffffffff818c624b)
Location: lib/zstd/decompress/zstd_decompress_block.c:1894
Inline: True
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
In lib/zstd/decompress/zstd_decompress_block.c (ffffffff81917e0b)
Location: lib/zstd/decompress/zstd_decompress_block.c:1894
Inline: True
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
size_t ZSTD_decompressSequences(ZSTD_DCtx *dctx, void *dst, size_t maxDstSize, const void *seqStart, size_t seqSize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (ffff800010657288)
Location: lib/zstd/decompress.c:1093
Inline: False
Direct callers:
  - lib/zstd/decompress.c:ZSTD_decompressContinue
  - lib/zstd/decompress.c:ZSTD_decompressDCtx
  - lib/zstd/decompress.c:ZSTD_decompressBlock
```
**Symbols:**

```
ffff800010657288-ffff800010657f54: ZSTD_decompressSequences (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
size_t ZSTD_decompressSequences(ZSTD_DCtx *dctx, void *dst, size_t maxDstSize, const void *seqStart, size_t seqSize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (c0800a88)
Location: lib/zstd/decompress.c:1093
Inline: False
Direct callers:
  - lib/zstd/decompress.c:ZSTD_decompressContinue
  - lib/zstd/decompress.c:ZSTD_decompressDCtx
  - lib/zstd/decompress.c:ZSTD_decompressBlock
```
**Symbols:**

```
c0800a88-c08017e0: ZSTD_decompressSequences (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
size_t ZSTD_decompressSequences(ZSTD_DCtx *dctx, void *dst, size_t maxDstSize, const void *seqStart, size_t seqSize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (c000000000807610)
Location: lib/zstd/decompress.c:1093
Inline: False
Direct callers:
  - lib/zstd/decompress.c:ZSTD_decompressContinue
  - lib/zstd/decompress.c:ZSTD_decompressDCtx
  - lib/zstd/decompress.c:ZSTD_decompressBlock
```
**Symbols:**

```
c000000000807610-c0000000008083e0: ZSTD_decompressSequences (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
size_t ZSTD_decompressSequences(ZSTD_DCtx *dctx, void *dst, size_t maxDstSize, const void *seqStart, size_t seqSize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (ffffffe000484f46)
Location: lib/zstd/decompress.c:1093
Inline: False
Direct callers:
  - lib/zstd/decompress.c:ZSTD_decompressContinue
  - lib/zstd/decompress.c:ZSTD_decompressDCtx
  - lib/zstd/decompress.c:ZSTD_decompressBlock
```
**Symbols:**

```
ffffffe000484f46-ffffffe000485df2: ZSTD_decompressSequences (STB_LOCAL)
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
size_t ZSTD_decompressSequences(ZSTD_DCtx *dctx, void *dst, size_t maxDstSize, const void *seqStart, size_t seqSize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (ffffffff815435d0)
Location: lib/zstd/decompress.c:1093
Inline: False
Direct callers:
  - lib/zstd/decompress.c:ZSTD_decompressContinue
  - lib/zstd/decompress.c:ZSTD_decompressDCtx
  - lib/zstd/decompress.c:ZSTD_decompressBlock
```
**Symbols:**

```
ffffffff815435d0-ffffffff8154437c: ZSTD_decompressSequences (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
size_t ZSTD_decompressSequences(ZSTD_DCtx *dctx, void *dst, size_t maxDstSize, const void *seqStart, size_t seqSize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (ffffffff815338b0)
Location: lib/zstd/decompress.c:1093
Inline: False
Direct callers:
  - lib/zstd/decompress.c:ZSTD_decompressContinue
  - lib/zstd/decompress.c:ZSTD_decompressDCtx
  - lib/zstd/decompress.c:ZSTD_decompressBlock
```
**Symbols:**

```
ffffffff815338b0-ffffffff8153465c: ZSTD_decompressSequences (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
size_t ZSTD_decompressSequences(ZSTD_DCtx *dctx, void *dst, size_t maxDstSize, const void *seqStart, size_t seqSize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (ffffffff8153f310)
Location: lib/zstd/decompress.c:1093
Inline: False
Direct callers:
  - lib/zstd/decompress.c:ZSTD_decompressContinue
  - lib/zstd/decompress.c:ZSTD_decompressDCtx
  - lib/zstd/decompress.c:ZSTD_decompressBlock
```
**Symbols:**

```
ffffffff8153f310-ffffffff815400bc: ZSTD_decompressSequences (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
size_t ZSTD_decompressSequences(ZSTD_DCtx *dctx, void *dst, size_t maxDstSize, const void *seqStart, size_t seqSize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (ffffffff81559140)
Location: lib/zstd/decompress.c:1093
Inline: False
Direct callers:
  - lib/zstd/decompress.c:ZSTD_decompressContinue
  - lib/zstd/decompress.c:ZSTD_decompressDCtx
  - lib/zstd/decompress.c:ZSTD_decompressBlock
```
**Symbols:**

```
ffffffff81559140-ffffffff81559eec: ZSTD_decompressSequences (STB_LOCAL)
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
