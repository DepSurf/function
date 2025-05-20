# Function: <code>ZSTD_getCParamsFromCCtxParams</code>

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
<summary>In <code>5.19</code>: ✅</summary>

```c
ZSTD_compressionParameters ZSTD_getCParamsFromCCtxParams(const ZSTD_CCtx_params *CCtxParams, U64 srcSizeHint, size_t dictSize, ZSTD_cParamMode_e mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff81716700)
Location: lib/zstd/compress/zstd_compress.c:1215
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_CCtx_init_compressStream2
  - lib/zstd/compress/zstd_compress.c:ZSTD_createCDict_advanced2
  - lib/zstd/compress/zstd_compress.c:ZSTD_createCDict_advanced2
  - lib/zstd/compress/zstd_compress.c:ZSTD_estimateCCtxSize_usingCCtxParams
```
**Symbols:**

```
ffffffff81716700-ffffffff817167df: ZSTD_getCParamsFromCCtxParams (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ZSTD_compressionParameters ZSTD_getCParamsFromCCtxParams(const ZSTD_CCtx_params *CCtxParams, U64 srcSizeHint, size_t dictSize, ZSTD_cParamMode_e mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff8180a720)
Location: lib/zstd/compress/zstd_compress.c:1332
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_CCtx_init_compressStream2
  - lib/zstd/compress/zstd_compress.c:ZSTD_createCDict_advanced2
  - lib/zstd/compress/zstd_compress.c:ZSTD_createCDict_advanced2
  - lib/zstd/compress/zstd_compress.c:ZSTD_estimateCCtxSize_usingCCtxParams
```
**Symbols:**

```
ffffffff8180a720-ffffffff8180a7fe: ZSTD_getCParamsFromCCtxParams (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ZSTD_compressionParameters ZSTD_getCParamsFromCCtxParams(const ZSTD_CCtx_params *CCtxParams, U64 srcSizeHint, size_t dictSize, ZSTD_cParamMode_e mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff8184b1d0)
Location: lib/zstd/compress/zstd_compress.c:1332
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_CCtx_init_compressStream2
  - lib/zstd/compress/zstd_compress.c:ZSTD_createCDict_advanced2
  - lib/zstd/compress/zstd_compress.c:ZSTD_createCDict_advanced2
  - lib/zstd/compress/zstd_compress.c:ZSTD_estimateCCtxSize_usingCCtxParams
```
**Symbols:**

```
ffffffff8184b1d0-ffffffff8184b2ae: ZSTD_getCParamsFromCCtxParams (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ZSTD_compressionParameters ZSTD_getCParamsFromCCtxParams(const ZSTD_CCtx_params *CCtxParams, U64 srcSizeHint, size_t dictSize, ZSTD_cParamMode_e mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff8189cd90)
Location: lib/zstd/compress/zstd_compress.c:1332
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_CCtx_init_compressStream2
  - lib/zstd/compress/zstd_compress.c:ZSTD_createCDict_advanced2
  - lib/zstd/compress/zstd_compress.c:ZSTD_createCDict_advanced2
  - lib/zstd/compress/zstd_compress.c:ZSTD_estimateCCtxSize_usingCCtxParams
```
**Symbols:**

```
ffffffff8189cd90-ffffffff8189ce6e: ZSTD_getCParamsFromCCtxParams (STB_GLOBAL)
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
