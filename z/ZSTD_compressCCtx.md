# Function: <code>ZSTD_compressCCtx</code>

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
<summary>In <code>5.8</code>: ✅</summary>

```c
size_t ZSTD_compressCCtx(ZSTD_CCtx *ctx, void *dst, size_t dstCapacity, const void *src, size_t srcSize, ZSTD_parameters params);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress.c (ffffffff815ca640)
Location: lib/zstd/compress.c:2831
Inline: False
```
**Symbols:**

```
ffffffff815ca640-ffffffff815cab90: ZSTD_compressCCtx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
size_t ZSTD_compressCCtx(ZSTD_CCtx *ctx, void *dst, size_t dstCapacity, const void *src, size_t srcSize, ZSTD_parameters params);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress.c (ffffffff815e8210)
Location: lib/zstd/compress.c:2831
Inline: False
```
**Symbols:**

```
ffffffff815e8210-ffffffff815e8765: ZSTD_compressCCtx (STB_GLOBAL)
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
size_t ZSTD_compressCCtx(ZSTD_CCtx *cctx, void *dst, size_t dstCapacity, const void *src, size_t srcSize, int compressionLevel);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff8171a930)
Location: lib/zstd/compress/zstd_compress.c:3530
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_compress
```
**Symbols:**

```
ffffffff81719f60-ffffffff81719f89: ZSTD_compressCCtx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
size_t ZSTD_compressCCtx(ZSTD_CCtx *cctx, void *dst, size_t dstCapacity, const void *src, size_t srcSize, int compressionLevel);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff81810030)
Location: lib/zstd/compress/zstd_compress.c:4612
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_compress
```
**Symbols:**

```
ffffffff8180f590-ffffffff8180f5b9: ZSTD_compressCCtx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
size_t ZSTD_compressCCtx(ZSTD_CCtx *cctx, void *dst, size_t dstCapacity, const void *src, size_t srcSize, int compressionLevel);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff81850b10)
Location: lib/zstd/compress/zstd_compress.c:4612
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_compress
```
**Symbols:**

```
ffffffff81850080-ffffffff818500a9: ZSTD_compressCCtx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
size_t ZSTD_compressCCtx(ZSTD_CCtx *cctx, void *dst, size_t dstCapacity, const void *src, size_t srcSize, int compressionLevel);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff818a26d0)
Location: lib/zstd/compress/zstd_compress.c:4612
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_compress
```
**Symbols:**

```
ffffffff818a1c40-ffffffff818a1c69: ZSTD_compressCCtx (STB_GLOBAL)
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
