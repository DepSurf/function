# Function: <code>ZSTD_compress_usingDict</code>

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
size_t ZSTD_compress_usingDict(ZSTD_CCtx *ctx, void *dst, size_t dstCapacity, const void *src, size_t srcSize, const void *dict, size_t dictSize, ZSTD_parameters params);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress.c (ffffffff815cab90)
Location: lib/zstd/compress.c:2825
Inline: False
```
**Symbols:**

```
ffffffff815cab90-ffffffff815cb16e: ZSTD_compress_usingDict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
size_t ZSTD_compress_usingDict(ZSTD_CCtx *ctx, void *dst, size_t dstCapacity, const void *src, size_t srcSize, const void *dict, size_t dictSize, ZSTD_parameters params);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress.c (ffffffff815e8ab0)
Location: lib/zstd/compress.c:2825
Inline: False
```
**Symbols:**

```
ffffffff815e8ab0-ffffffff815e9093: ZSTD_compress_usingDict (STB_GLOBAL)
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
size_t ZSTD_compress_usingDict(ZSTD_CCtx *cctx, void *dst, size_t dstCapacity, const void *src, size_t srcSize, const void *dict, size_t dictSize, int compressionLevel);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff81719df0)
Location: lib/zstd/compress/zstd_compress.c:3514
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_compress
```
**Symbols:**

```
ffffffff81719df0-ffffffff81719f58: ZSTD_compress_usingDict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
size_t ZSTD_compress_usingDict(ZSTD_CCtx *cctx, void *dst, size_t dstCapacity, const void *src, size_t srcSize, const void *dict, size_t dictSize, int compressionLevel);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff8180f480)
Location: lib/zstd/compress/zstd_compress.c:4597
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_compress
```
**Symbols:**

```
ffffffff8180f480-ffffffff8180f572: ZSTD_compress_usingDict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
size_t ZSTD_compress_usingDict(ZSTD_CCtx *cctx, void *dst, size_t dstCapacity, const void *src, size_t srcSize, const void *dict, size_t dictSize, int compressionLevel);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff8184ff70)
Location: lib/zstd/compress/zstd_compress.c:4597
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_compress
```
**Symbols:**

```
ffffffff8184ff70-ffffffff81850062: ZSTD_compress_usingDict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
size_t ZSTD_compress_usingDict(ZSTD_CCtx *cctx, void *dst, size_t dstCapacity, const void *src, size_t srcSize, const void *dict, size_t dictSize, int compressionLevel);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff818a1b30)
Location: lib/zstd/compress/zstd_compress.c:4597
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_compress
```
**Symbols:**

```
ffffffff818a1b30-ffffffff818a1c22: ZSTD_compress_usingDict (STB_GLOBAL)
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
