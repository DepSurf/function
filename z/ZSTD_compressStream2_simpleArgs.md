# Function: <code>ZSTD_compressStream2_simpleArgs</code>

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
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
size_t ZSTD_compressStream2_simpleArgs(ZSTD_CCtx *cctx, void *dst, size_t dstCapacity, size_t *dstPos, const void *src, size_t srcSize, size_t *srcPos, ZSTD_EndDirective endOp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff8171c397)
Location: lib/zstd/compress/zstd_compress.c:4388
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_compress2
```
**Symbols:**

```
ffffffff8171c2a0-ffffffff8171c333: ZSTD_compressStream2_simpleArgs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
size_t ZSTD_compressStream2_simpleArgs(ZSTD_CCtx *cctx, void *dst, size_t dstCapacity, size_t *dstPos, const void *src, size_t srcSize, size_t *srcPos, ZSTD_EndDirective endOp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff81811be7)
Location: lib/zstd/compress/zstd_compress.c:5507
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_compress2
```
**Symbols:**

```
ffffffff81811ae0-ffffffff81811b73: ZSTD_compressStream2_simpleArgs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
size_t ZSTD_compressStream2_simpleArgs(ZSTD_CCtx *cctx, void *dst, size_t dstCapacity, size_t *dstPos, const void *src, size_t srcSize, size_t *srcPos, ZSTD_EndDirective endOp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff818526d7)
Location: lib/zstd/compress/zstd_compress.c:5507
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_compress2
```
**Symbols:**

```
ffffffff818525d0-ffffffff81852663: ZSTD_compressStream2_simpleArgs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
size_t ZSTD_compressStream2_simpleArgs(ZSTD_CCtx *cctx, void *dst, size_t dstCapacity, size_t *dstPos, const void *src, size_t srcSize, size_t *srcPos, ZSTD_EndDirective endOp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff818a4297)
Location: lib/zstd/compress/zstd_compress.c:5507
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_compress2
```
**Symbols:**

```
ffffffff818a4190-ffffffff818a4223: ZSTD_compressStream2_simpleArgs (STB_GLOBAL)
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
