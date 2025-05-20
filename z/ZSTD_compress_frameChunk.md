# Function: <code>ZSTD_compress_frameChunk</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
size_t ZSTD_compress_frameChunk(ZSTD_CCtx *cctx, void *dst, size_t dstCapacity, const void *src, size_t srcSize, U32 lastFrameChunk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (0)
Location: lib/zstd/compress/zstd_compress.c:2787
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressContinue_internal
```
**Symbols:**

```
ffffffff817177c0-ffffffff81717bd6: ZSTD_compress_frameChunk (STB_LOCAL)
ffffffff81e97376-ffffffff81e973c0: ZSTD_compress_frameChunk.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
size_t ZSTD_compress_frameChunk(ZSTD_CCtx *cctx, void *dst, size_t dstCapacity, const void *src, size_t srcSize, U32 lastFrameChunk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (0)
Location: lib/zstd/compress/zstd_compress.c:3841
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressContinue_internal
```
**Symbols:**

```
ffffffff8180d010-ffffffff8180d59e: ZSTD_compress_frameChunk (STB_LOCAL)
ffffffff8207dfa0-ffffffff8207dffa: ZSTD_compress_frameChunk.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
size_t ZSTD_compress_frameChunk(ZSTD_CCtx *cctx, void *dst, size_t dstCapacity, const void *src, size_t srcSize, U32 lastFrameChunk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (0)
Location: lib/zstd/compress/zstd_compress.c:3841
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressContinue_internal
```
**Symbols:**

```
ffffffff8184dac0-ffffffff8184e03d: ZSTD_compress_frameChunk (STB_LOCAL)
ffffffff820fe517-ffffffff820fe571: ZSTD_compress_frameChunk.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
size_t ZSTD_compress_frameChunk(ZSTD_CCtx *cctx, void *dst, size_t dstCapacity, const void *src, size_t srcSize, U32 lastFrameChunk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (0)
Location: lib/zstd/compress/zstd_compress.c:3841
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressContinue_internal
```
**Symbols:**

```
ffffffff8189f680-ffffffff8189fbfd: ZSTD_compress_frameChunk (STB_LOCAL)
ffffffff821dc684-ffffffff821dc6de: ZSTD_compress_frameChunk.cold (STB_LOCAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
