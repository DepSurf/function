# Function: <code>ZSTD_compressEnd</code>

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
size_t ZSTD_compressEnd(ZSTD_CCtx *cctx, void *dst, size_t dstCapacity, const void *src, size_t srcSize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/compress.c (ffffffff815ca510)
Location: lib/zstd/compress.c:2806
Inline: True
Direct callers:
  - lib/zstd/compress.c:ZSTD_endStream
  - lib/zstd/compress.c:ZSTD_compressStream_generic
  - lib/zstd/compress.c:ZSTD_compressCCtx
  - lib/zstd/compress.c:ZSTD_compress_usingDict
```
**Symbols:**

```
ffffffff815ca510-ffffffff815ca633: ZSTD_compressEnd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
size_t ZSTD_compressEnd(ZSTD_CCtx *cctx, void *dst, size_t dstCapacity, const void *src, size_t srcSize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/compress.c (ffffffff815e80e0)
Location: lib/zstd/compress.c:2806
Inline: True
Direct callers:
  - lib/zstd/compress.c:ZSTD_endStream
  - lib/zstd/compress.c:ZSTD_endStream
  - lib/zstd/compress.c:ZSTD_compressCCtx
  - lib/zstd/compress.c:ZSTD_compress_usingDict
```
**Symbols:**

```
ffffffff815e80e0-ffffffff815e8208: ZSTD_compressEnd (STB_GLOBAL)
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
size_t ZSTD_compressEnd(ZSTD_CCtx *cctx, void *dst, size_t dstCapacity, const void *src, size_t srcSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff817194a0)
Location: lib/zstd/compress/zstd_compress.c:3456
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressStream_generic
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressStream_generic
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressStream_generic
  - lib/zstd/compress/zstd_compress.c:ZSTD_compress_usingCDict
  - lib/zstd/compress/zstd_compress.c:ZSTD_compress_usingDict
  - lib/zstd/compress/zstd_compress.c:ZSTD_compress_advanced
```
**Symbols:**

```
ffffffff817194a0-ffffffff81719616: ZSTD_compressEnd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
size_t ZSTD_compressEnd(ZSTD_CCtx *cctx, void *dst, size_t dstCapacity, const void *src, size_t srcSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff8180eb60)
Location: lib/zstd/compress/zstd_compress.c:4540
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressStream_generic
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressStream_generic
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressStream_generic
  - lib/zstd/compress/zstd_compress.c:ZSTD_compress_usingCDict
  - lib/zstd/compress/zstd_compress.c:ZSTD_compress_usingCDict_advanced
  - lib/zstd/compress/zstd_compress.c:ZSTD_compress_usingDict
  - lib/zstd/compress/zstd_compress.c:ZSTD_compress_advanced
```
**Symbols:**

```
ffffffff8180eb60-ffffffff8180ecd6: ZSTD_compressEnd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
size_t ZSTD_compressEnd(ZSTD_CCtx *cctx, void *dst, size_t dstCapacity, const void *src, size_t srcSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff8184f670)
Location: lib/zstd/compress/zstd_compress.c:4540
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressStream_generic
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressStream_generic
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressStream_generic
  - lib/zstd/compress/zstd_compress.c:ZSTD_compress_usingCDict
  - lib/zstd/compress/zstd_compress.c:ZSTD_compress_usingCDict_advanced
  - lib/zstd/compress/zstd_compress.c:ZSTD_compress_usingDict
  - lib/zstd/compress/zstd_compress.c:ZSTD_compress_advanced
```
**Symbols:**

```
ffffffff8184f670-ffffffff8184f7e6: ZSTD_compressEnd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
size_t ZSTD_compressEnd(ZSTD_CCtx *cctx, void *dst, size_t dstCapacity, const void *src, size_t srcSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff818a1230)
Location: lib/zstd/compress/zstd_compress.c:4540
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressStream_generic
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressStream_generic
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressStream_generic
  - lib/zstd/compress/zstd_compress.c:ZSTD_compress_usingCDict
  - lib/zstd/compress/zstd_compress.c:ZSTD_compress_usingCDict_advanced
  - lib/zstd/compress/zstd_compress.c:ZSTD_compress_usingDict
  - lib/zstd/compress/zstd_compress.c:ZSTD_compress_advanced
```
**Symbols:**

```
ffffffff818a1230-ffffffff818a13a6: ZSTD_compressEnd (STB_GLOBAL)
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
