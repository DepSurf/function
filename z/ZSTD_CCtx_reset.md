# Function: <code>ZSTD_CCtx_reset</code>

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
size_t ZSTD_CCtx_reset(ZSTD_CCtx *cctx, ZSTD_ResetDirective reset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff8171c369)
Location: lib/zstd/compress/zstd_compress.c:1025
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_compress2
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressStream_generic
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressStream_generic
  - lib/zstd/compress/zstd_compress.c:ZSTD_initCStream
  - lib/zstd/compress/zstd_compress.c:ZSTD_initCStream_srcSize
  - lib/zstd/compress/zstd_compress.c:ZSTD_initCStream_usingDict
  - lib/zstd/compress/zstd_compress.c:ZSTD_initCStream_advanced
  - lib/zstd/compress/zstd_compress.c:ZSTD_initCStream_usingCDict
  - lib/zstd/compress/zstd_compress.c:ZSTD_initCStream_usingCDict_advanced
  - lib/zstd/compress/zstd_compress.c:ZSTD_initCStream_internal
  - lib/zstd/compress/zstd_compress.c:ZSTD_resetCStream
  - lib/zstd/compress/zstd_compress.c:ZSTD_createCCtx_advanced
  - lib/zstd/compress/zstd_compress.c:ZSTD_createCCtx_advanced
Direct callers:
  - lib/zstd/zstd_compress_module.c:zstd_init_cstream
  - lib/zstd/zstd_compress_module.c:zstd_compress_cctx
```
**Symbols:**

```
ffffffff8171a630-ffffffff8171a6f5: ZSTD_CCtx_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
size_t ZSTD_CCtx_reset(ZSTD_CCtx *cctx, ZSTD_ResetDirective reset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff81811bb9)
Location: lib/zstd/compress/zstd_compress.c:1142
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_compress2
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressStream_generic
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressStream_generic
  - lib/zstd/compress/zstd_compress.c:ZSTD_initCStream
  - lib/zstd/compress/zstd_compress.c:ZSTD_initCStream_srcSize
  - lib/zstd/compress/zstd_compress.c:ZSTD_initCStream_usingDict
  - lib/zstd/compress/zstd_compress.c:ZSTD_initCStream_advanced
  - lib/zstd/compress/zstd_compress.c:ZSTD_initCStream_usingCDict
  - lib/zstd/compress/zstd_compress.c:ZSTD_initCStream_usingCDict_advanced
  - lib/zstd/compress/zstd_compress.c:ZSTD_initCStream_internal
  - lib/zstd/compress/zstd_compress.c:ZSTD_resetCStream
  - lib/zstd/compress/zstd_compress.c:ZSTD_createCCtx_advanced
  - lib/zstd/compress/zstd_compress.c:ZSTD_createCCtx_advanced
Direct callers:
  - lib/zstd/zstd_compress_module.c:zstd_reset_cstream
  - lib/zstd/zstd_compress_module.c:zstd_init_cstream
  - lib/zstd/zstd_compress_module.c:zstd_compress_cctx
```
**Symbols:**

```
ffffffff8180fcf0-ffffffff8180fdb5: ZSTD_CCtx_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
size_t ZSTD_CCtx_reset(ZSTD_CCtx *cctx, ZSTD_ResetDirective reset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff818526a9)
Location: lib/zstd/compress/zstd_compress.c:1142
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_compress2
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressStream_generic
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressStream_generic
  - lib/zstd/compress/zstd_compress.c:ZSTD_initCStream
  - lib/zstd/compress/zstd_compress.c:ZSTD_initCStream_srcSize
  - lib/zstd/compress/zstd_compress.c:ZSTD_initCStream_usingDict
  - lib/zstd/compress/zstd_compress.c:ZSTD_initCStream_advanced
  - lib/zstd/compress/zstd_compress.c:ZSTD_initCStream_usingCDict
  - lib/zstd/compress/zstd_compress.c:ZSTD_initCStream_usingCDict_advanced
  - lib/zstd/compress/zstd_compress.c:ZSTD_initCStream_internal
  - lib/zstd/compress/zstd_compress.c:ZSTD_resetCStream
  - lib/zstd/compress/zstd_compress.c:ZSTD_createCCtx_advanced
  - lib/zstd/compress/zstd_compress.c:ZSTD_createCCtx_advanced
Direct callers:
  - lib/zstd/zstd_compress_module.c:zstd_reset_cstream
  - lib/zstd/zstd_compress_module.c:zstd_init_cstream
  - lib/zstd/zstd_compress_module.c:zstd_compress_cctx
```
**Symbols:**

```
ffffffff818507d0-ffffffff81850895: ZSTD_CCtx_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
size_t ZSTD_CCtx_reset(ZSTD_CCtx *cctx, ZSTD_ResetDirective reset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff818a4269)
Location: lib/zstd/compress/zstd_compress.c:1142
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_compress2
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressStream_generic
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressStream_generic
  - lib/zstd/compress/zstd_compress.c:ZSTD_initCStream
  - lib/zstd/compress/zstd_compress.c:ZSTD_initCStream_srcSize
  - lib/zstd/compress/zstd_compress.c:ZSTD_initCStream_usingDict
  - lib/zstd/compress/zstd_compress.c:ZSTD_initCStream_advanced
  - lib/zstd/compress/zstd_compress.c:ZSTD_initCStream_usingCDict
  - lib/zstd/compress/zstd_compress.c:ZSTD_initCStream_usingCDict_advanced
  - lib/zstd/compress/zstd_compress.c:ZSTD_initCStream_internal
  - lib/zstd/compress/zstd_compress.c:ZSTD_resetCStream
  - lib/zstd/compress/zstd_compress.c:ZSTD_createCCtx_advanced
  - lib/zstd/compress/zstd_compress.c:ZSTD_createCCtx_advanced
Direct callers:
  - lib/zstd/zstd_compress_module.c:zstd_reset_cstream
  - lib/zstd/zstd_compress_module.c:zstd_init_cstream
  - lib/zstd/zstd_compress_module.c:zstd_compress_cctx
```
**Symbols:**

```
ffffffff818a2390-ffffffff818a2455: ZSTD_CCtx_reset (STB_GLOBAL)
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
