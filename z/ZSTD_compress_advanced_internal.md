# Function: <code>ZSTD_compress_advanced_internal</code>

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
size_t ZSTD_compress_advanced_internal(ZSTD_CCtx *cctx, void *dst, size_t dstCapacity, const void *src, size_t srcSize, const void *dict, size_t dictSize, const ZSTD_CCtx_params *params);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff81719eeb)
Location: lib/zstd/compress/zstd_compress.c:3500
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_compress_usingDict
  - lib/zstd/compress/zstd_compress.c:ZSTD_compress_advanced
```
**Symbols:**

```
ffffffff81719d10-ffffffff81719df0: ZSTD_compress_advanced_internal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
size_t ZSTD_compress_advanced_internal(ZSTD_CCtx *cctx, void *dst, size_t dstCapacity, const void *src, size_t srcSize, const void *dict, size_t dictSize, const ZSTD_CCtx_params *params);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff8180f4ff)
Location: lib/zstd/compress/zstd_compress.c:4583
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_compress_usingDict
  - lib/zstd/compress/zstd_compress.c:ZSTD_compress_advanced
```
**Symbols:**

```
ffffffff8180f3a0-ffffffff8180f470: ZSTD_compress_advanced_internal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
size_t ZSTD_compress_advanced_internal(ZSTD_CCtx *cctx, void *dst, size_t dstCapacity, const void *src, size_t srcSize, const void *dict, size_t dictSize, const ZSTD_CCtx_params *params);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff8184ffef)
Location: lib/zstd/compress/zstd_compress.c:4583
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_compress_usingDict
  - lib/zstd/compress/zstd_compress.c:ZSTD_compress_advanced
```
**Symbols:**

```
ffffffff8184fe90-ffffffff8184ff60: ZSTD_compress_advanced_internal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
size_t ZSTD_compress_advanced_internal(ZSTD_CCtx *cctx, void *dst, size_t dstCapacity, const void *src, size_t srcSize, const void *dict, size_t dictSize, const ZSTD_CCtx_params *params);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff818a1baf)
Location: lib/zstd/compress/zstd_compress.c:4583
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_compress_usingDict
  - lib/zstd/compress/zstd_compress.c:ZSTD_compress_advanced
```
**Symbols:**

```
ffffffff818a1a50-ffffffff818a1b20: ZSTD_compress_advanced_internal (STB_GLOBAL)
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
