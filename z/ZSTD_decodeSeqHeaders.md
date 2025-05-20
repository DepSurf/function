# Function: <code>ZSTD_decodeSeqHeaders</code>

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
size_t ZSTD_decodeSeqHeaders(ZSTD_DCtx *dctx, int *nbSeqPtr, const void *src, size_t srcSize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (ffffffff814b27ef)
Location: lib/zstd/decompress.c:794
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
Direct callers:
  - lib/zstd/decompress.c:ZSTD_decompressSequences
```
**Symbols:**

```
ffffffff814b4ea0-ffffffff814b52dd: ZSTD_decodeSeqHeaders (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
size_t ZSTD_decodeSeqHeaders(ZSTD_DCtx *dctx, int *nbSeqPtr, const void *src, size_t srcSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (ffffffff814e7790)
Location: lib/zstd/decompress.c:794
Inline: False
Direct callers:
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequences
```
**Symbols:**

```
ffffffff814e7790-ffffffff814e7bce: ZSTD_decodeSeqHeaders (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
size_t ZSTD_decodeSeqHeaders(ZSTD_DCtx *dctx, int *nbSeqPtr, const void *src, size_t srcSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (ffffffff814fb480)
Location: lib/zstd/decompress.c:794
Inline: False
Direct callers:
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequences
```
**Symbols:**

```
ffffffff814fb480-ffffffff814fb8be: ZSTD_decodeSeqHeaders (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
size_t ZSTD_decodeSeqHeaders(ZSTD_DCtx *dctx, int *nbSeqPtr, const void *src, size_t srcSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (ffffffff81528c70)
Location: lib/zstd/decompress.c:794
Inline: False
Direct callers:
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequences
```
**Symbols:**

```
ffffffff81528c70-ffffffff815290ad: ZSTD_decodeSeqHeaders (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
size_t ZSTD_decodeSeqHeaders(ZSTD_DCtx *dctx, int *nbSeqPtr, const void *src, size_t srcSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (ffffffff81549b00)
Location: lib/zstd/decompress.c:794
Inline: False
Direct callers:
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequences
```
**Symbols:**

```
ffffffff81549b00-ffffffff81549f3d: ZSTD_decodeSeqHeaders (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
size_t ZSTD_decodeSeqHeaders(ZSTD_DCtx *dctx, int *nbSeqPtr, const void *src, size_t srcSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (ffffffff815d5400)
Location: lib/zstd/decompress.c:794
Inline: False
Direct callers:
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequences
```
**Symbols:**

```
ffffffff815d5400-ffffffff815d583d: ZSTD_decodeSeqHeaders (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
size_t ZSTD_decodeSeqHeaders(ZSTD_DCtx *dctx, int *nbSeqPtr, const void *src, size_t srcSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (ffffffff815f30d0)
Location: lib/zstd/decompress.c:794
Inline: False
Direct callers:
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequences
```
**Symbols:**

```
ffffffff815f30d0-ffffffff815f3512: ZSTD_decodeSeqHeaders (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
size_t ZSTD_decodeSeqHeaders(ZSTD_DCtx *dctx, int *nbSeqPtr, const void *src, size_t srcSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (ffffffff815d44f0)
Location: lib/zstd/decompress.c:794
Inline: False
Direct callers:
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequences
```
**Symbols:**

```
ffffffff815d44f0-ffffffff815d4932: ZSTD_decodeSeqHeaders (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
size_t ZSTD_decodeSeqHeaders(ZSTD_DCtx *dctx, int *nbSeqPtr, const void *src, size_t srcSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (ffffffff8163f2f0)
Location: lib/zstd/decompress.c:794
Inline: False
Direct callers:
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequences
```
**Symbols:**

```
ffffffff8163f2f0-ffffffff8163f732: ZSTD_decodeSeqHeaders (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
size_t ZSTD_decodeSeqHeaders(ZSTD_DCtx *dctx, int *nbSeqPtr, const void *src, size_t srcSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress/zstd_decompress_block.c (ffffffff8175a170)
Location: lib/zstd/decompress/zstd_decompress_block.c:577
Inline: False
```
**Symbols:**

```
ffffffff8175a170-ffffffff8175a3e6: ZSTD_decodeSeqHeaders (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
size_t ZSTD_decodeSeqHeaders(ZSTD_DCtx *dctx, int *nbSeqPtr, const void *src, size_t srcSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress/zstd_decompress_block.c (ffffffff81883980)
Location: lib/zstd/decompress/zstd_decompress_block.c:653
Inline: False
```
**Symbols:**

```
ffffffff81883980-ffffffff81883bf6: ZSTD_decodeSeqHeaders (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
size_t ZSTD_decodeSeqHeaders(ZSTD_DCtx *dctx, int *nbSeqPtr, const void *src, size_t srcSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress/zstd_decompress_block.c (ffffffff818c5ea0)
Location: lib/zstd/decompress/zstd_decompress_block.c:653
Inline: False
```
**Symbols:**

```
ffffffff818c5ea0-ffffffff818c6116: ZSTD_decodeSeqHeaders (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
size_t ZSTD_decodeSeqHeaders(ZSTD_DCtx *dctx, int *nbSeqPtr, const void *src, size_t srcSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress/zstd_decompress_block.c (ffffffff81917a60)
Location: lib/zstd/decompress/zstd_decompress_block.c:653
Inline: False
```
**Symbols:**

```
ffffffff81917a60-ffffffff81917cd6: ZSTD_decodeSeqHeaders (STB_GLOBAL)
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
size_t ZSTD_decodeSeqHeaders(ZSTD_DCtx *dctx, int *nbSeqPtr, const void *src, size_t srcSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (ffff800010655d10)
Location: lib/zstd/decompress.c:794
Inline: False
Direct callers:
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequences
```
**Symbols:**

```
ffff800010655d10-ffff8000106560e0: ZSTD_decodeSeqHeaders (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
size_t ZSTD_decodeSeqHeaders(ZSTD_DCtx *dctx, int *nbSeqPtr, const void *src, size_t srcSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (c080069c)
Location: lib/zstd/decompress.c:794
Inline: False
Direct callers:
  - lib/zstd/decompress.c:ZSTD_decompressSequences
```
**Symbols:**

```
c080069c-c0800a88: ZSTD_decodeSeqHeaders (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
size_t ZSTD_decodeSeqHeaders(ZSTD_DCtx *dctx, int *nbSeqPtr, const void *src, size_t srcSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (c000000000806020)
Location: lib/zstd/decompress.c:794
Inline: False
Direct callers:
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequences
```
**Symbols:**

```
c000000000806020-c00000000080652c: ZSTD_decodeSeqHeaders (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
size_t ZSTD_decodeSeqHeaders(ZSTD_DCtx *dctx, int *nbSeqPtr, const void *src, size_t srcSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (ffffffe0004839be)
Location: lib/zstd/decompress.c:794
Inline: False
Direct callers:
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequences
```
**Symbols:**

```
ffffffe0004839be-ffffffe000483cea: ZSTD_decodeSeqHeaders (STB_GLOBAL)
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
size_t ZSTD_decodeSeqHeaders(ZSTD_DCtx *dctx, int *nbSeqPtr, const void *src, size_t srcSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (ffffffff815420e0)
Location: lib/zstd/decompress.c:794
Inline: False
Direct callers:
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequences
```
**Symbols:**

```
ffffffff815420e0-ffffffff8154251d: ZSTD_decodeSeqHeaders (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
size_t ZSTD_decodeSeqHeaders(ZSTD_DCtx *dctx, int *nbSeqPtr, const void *src, size_t srcSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (ffffffff815323c0)
Location: lib/zstd/decompress.c:794
Inline: False
Direct callers:
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequences
```
**Symbols:**

```
ffffffff815323c0-ffffffff815327fd: ZSTD_decodeSeqHeaders (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
size_t ZSTD_decodeSeqHeaders(ZSTD_DCtx *dctx, int *nbSeqPtr, const void *src, size_t srcSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (ffffffff8153de20)
Location: lib/zstd/decompress.c:794
Inline: False
Direct callers:
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequences
```
**Symbols:**

```
ffffffff8153de20-ffffffff8153e25d: ZSTD_decodeSeqHeaders (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
size_t ZSTD_decodeSeqHeaders(ZSTD_DCtx *dctx, int *nbSeqPtr, const void *src, size_t srcSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (ffffffff81557c50)
Location: lib/zstd/decompress.c:794
Inline: False
Direct callers:
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequences
```
**Symbols:**

```
ffffffff81557c50-ffffffff8155808d: ZSTD_decodeSeqHeaders (STB_GLOBAL)
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
