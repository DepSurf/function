# Function: <code>ZSTD_compressContinue_internal</code>

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
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
size_t ZSTD_compressContinue_internal(ZSTD_CCtx *cctx, void *dst, size_t dstCapacity, const void *src, size_t srcSize, U32 frame, U32 lastFrameChunk);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/compress.c (ffffffff815ca060)
Location: lib/zstd/compress.c:2490
Inline: True
Direct callers:
  - lib/zstd/compress.c:ZSTD_flushStream
  - lib/zstd/compress.c:ZSTD_compressStream
```
**Symbols:**

```
ffffffff815ca060-ffffffff815ca4ea: ZSTD_compressContinue_internal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
size_t ZSTD_compressContinue_internal(ZSTD_CCtx *cctx, void *dst, size_t dstCapacity, const void *src, size_t srcSize, U32 frame, U32 lastFrameChunk);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/compress.c (ffffffff815e7c30)
Location: lib/zstd/compress.c:2490
Inline: True
Direct callers:
  - lib/zstd/compress.c:ZSTD_flushStream
  - lib/zstd/compress.c:ZSTD_compressStream
```
**Symbols:**

```
ffffffff815e7c30-ffffffff815e80bc: ZSTD_compressContinue_internal (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
size_t ZSTD_compressContinue_internal(ZSTD_CCtx *cctx, void *dst, size_t dstCapacity, const void *src, size_t srcSize, U32 frame, U32 lastFrameChunk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff81717be0)
Location: lib/zstd/compress/zstd_compress.c:2961
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressStream_generic
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressStream_generic
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressEnd
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressBlock
```
**Symbols:**

```
ffffffff81717be0-ffffffff81717f24: ZSTD_compressContinue_internal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
size_t ZSTD_compressContinue_internal(ZSTD_CCtx *cctx, void *dst, size_t dstCapacity, const void *src, size_t srcSize, U32 frame, U32 lastFrameChunk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff8180d5b0)
Location: lib/zstd/compress/zstd_compress.c:4020
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressStream_generic
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressStream_generic
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressEnd
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressBlock
```
**Symbols:**

```
ffffffff8180d5b0-ffffffff8180d8d2: ZSTD_compressContinue_internal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
size_t ZSTD_compressContinue_internal(ZSTD_CCtx *cctx, void *dst, size_t dstCapacity, const void *src, size_t srcSize, U32 frame, U32 lastFrameChunk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff8184e050)
Location: lib/zstd/compress/zstd_compress.c:4020
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressStream_generic
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressStream_generic
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressEnd
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressBlock
```
**Symbols:**

```
ffffffff8184e050-ffffffff8184e372: ZSTD_compressContinue_internal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
size_t ZSTD_compressContinue_internal(ZSTD_CCtx *cctx, void *dst, size_t dstCapacity, const void *src, size_t srcSize, U32 frame, U32 lastFrameChunk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff8189fc10)
Location: lib/zstd/compress/zstd_compress.c:4020
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressStream_generic
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressStream_generic
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressEnd
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressBlock
```
**Symbols:**

```
ffffffff8189fc10-ffffffff8189ff32: ZSTD_compressContinue_internal (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
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
