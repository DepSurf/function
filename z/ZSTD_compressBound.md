# Function: <code>ZSTD_compressBound</code>

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
size_t ZSTD_compressBound(size_t srcSize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/compress.c (ffffffff815cb875)
Location: lib/zstd/compress.c:38
Inline: True
Inline callers:
  - lib/zstd/compress.c:ZSTD_flushStream
  - lib/zstd/compress.c:ZSTD_compressStream
  - lib/zstd/compress.c:ZSTD_initCStream_usingCDict
  - lib/zstd/compress.c:ZSTD_initCStream_usingCDict
  - lib/zstd/compress.c:ZSTD_CStreamOutSize
  - lib/zstd/compress.c:ZSTD_CStreamWorkspaceBound
```
**Symbols:**

```
ffffffff815af450-ffffffff815af45f: ZSTD_compressBound (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
size_t ZSTD_compressBound(size_t srcSize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/compress.c (ffffffff815e8810)
Location: lib/zstd/compress.c:38
Inline: True
Inline callers:
  - lib/zstd/compress.c:ZSTD_endStream
  - lib/zstd/compress.c:ZSTD_flushStream
  - lib/zstd/compress.c:ZSTD_compressStream
  - lib/zstd/compress.c:ZSTD_initCStream_usingCDict
  - lib/zstd/compress.c:ZSTD_initCStream_usingCDict
  - lib/zstd/compress.c:ZSTD_CStreamOutSize
  - lib/zstd/compress.c:ZSTD_CStreamWorkspaceBound
```
**Symbols:**

```
ffffffff815cb0c0-ffffffff815cb0d4: ZSTD_compressBound (STB_GLOBAL)
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
size_t ZSTD_compressBound(size_t srcSize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff8171978c)
Location: lib/zstd/compress/zstd_compress.c:53
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressStream_generic
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressStream_generic
  - lib/zstd/compress/zstd_compress.c:ZSTD_generateSequences
  - lib/zstd/compress/zstd_compress.c:ZSTD_resetCCtx_internal
Direct callers:
  - lib/zstd/zstd_compress_module.c:zstd_compress_bound
```
**Symbols:**

```
ffffffff81715000-ffffffff81715035: ZSTD_compressBound (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
size_t ZSTD_compressBound(size_t srcSize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff8180ee5c)
Location: lib/zstd/compress/zstd_compress.c:64
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressStream_generic
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressStream_generic
  - lib/zstd/compress/zstd_compress.c:ZSTD_generateSequences
  - lib/zstd/compress/zstd_compress.c:ZSTD_resetCCtx_internal
Direct callers:
  - lib/zstd/zstd_compress_module.c:zstd_compress_bound
```
**Symbols:**

```
ffffffff81808df0-ffffffff81808e25: ZSTD_compressBound (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
size_t ZSTD_compressBound(size_t srcSize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff8184f903)
Location: lib/zstd/compress/zstd_compress.c:64
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressStream_generic
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressStream_generic
  - lib/zstd/compress/zstd_compress.c:ZSTD_generateSequences
  - lib/zstd/compress/zstd_compress.c:ZSTD_resetCCtx_internal
Direct callers:
  - lib/zstd/zstd_compress_module.c:zstd_compress_bound
```
**Symbols:**

```
ffffffff818497e0-ffffffff81849815: ZSTD_compressBound (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
size_t ZSTD_compressBound(size_t srcSize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff818a14c3)
Location: lib/zstd/compress/zstd_compress.c:64
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressStream_generic
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressStream_generic
  - lib/zstd/compress/zstd_compress.c:ZSTD_generateSequences
  - lib/zstd/compress/zstd_compress.c:ZSTD_resetCCtx_internal
Direct callers:
  - lib/zstd/zstd_compress_module.c:zstd_compress_bound
```
**Symbols:**

```
ffffffff8189b3a0-ffffffff8189b3d5: ZSTD_compressBound (STB_GLOBAL)
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
