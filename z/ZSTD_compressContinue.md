# Function: <code>ZSTD_compressContinue</code>

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
size_t ZSTD_compressContinue(ZSTD_CCtx *cctx, void *dst, size_t dstCapacity, const void *src, size_t srcSize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/compress.c (ffffffff815cb88c)
Location: lib/zstd/compress.c:2539
Inline: True
Inline callers:
  - lib/zstd/compress.c:ZSTD_flushStream
  - lib/zstd/compress.c:ZSTD_compressStream
```
**Symbols:**

```
ffffffff815ca4f0-ffffffff815ca503: ZSTD_compressContinue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
size_t ZSTD_compressContinue(ZSTD_CCtx *cctx, void *dst, size_t dstCapacity, const void *src, size_t srcSize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/compress.c (ffffffff815e93a4)
Location: lib/zstd/compress.c:2539
Inline: True
Inline callers:
  - lib/zstd/compress.c:ZSTD_flushStream
  - lib/zstd/compress.c:ZSTD_compressStream
```
**Symbols:**

```
ffffffff815e80c0-ffffffff815e80d8: ZSTD_compressContinue (STB_GLOBAL)
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
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
size_t ZSTD_compressContinue(ZSTD_CCtx *cctx, void *dst, size_t dstCapacity, const void *src, size_t srcSize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff8171980f)
Location: lib/zstd/compress/zstd_compress.c:3021
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressStream_generic
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressStream_generic
```
**Symbols:**

```
ffffffff81718690-ffffffff817186ba: ZSTD_compressContinue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
size_t ZSTD_compressContinue(ZSTD_CCtx *cctx, void *dst, size_t dstCapacity, const void *src, size_t srcSize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff8180eedf)
Location: lib/zstd/compress/zstd_compress.c:4081
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressStream_generic
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressStream_generic
```
**Symbols:**

```
ffffffff8180da90-ffffffff8180daba: ZSTD_compressContinue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
size_t ZSTD_compressContinue(ZSTD_CCtx *cctx, void *dst, size_t dstCapacity, const void *src, size_t srcSize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff8184f980)
Location: lib/zstd/compress/zstd_compress.c:4081
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressStream_generic
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressStream_generic
```
**Symbols:**

```
ffffffff8184e530-ffffffff8184e55a: ZSTD_compressContinue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
size_t ZSTD_compressContinue(ZSTD_CCtx *cctx, void *dst, size_t dstCapacity, const void *src, size_t srcSize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff818a1540)
Location: lib/zstd/compress/zstd_compress.c:4081
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressStream_generic
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressStream_generic
```
**Symbols:**

```
ffffffff818a00f0-ffffffff818a011a: ZSTD_compressContinue (STB_GLOBAL)
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
