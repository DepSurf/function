# Function: <code>ZSTD_CCtx_setPledgedSrcSize</code>

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
size_t ZSTD_CCtx_setPledgedSrcSize(ZSTD_CCtx *cctx, long long unsigned int pledgedSrcSize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff8171bf8b)
Location: lib/zstd/compress/zstd_compress.c:892
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_initCStream_srcSize
  - lib/zstd/compress/zstd_compress.c:ZSTD_initCStream_advanced
  - lib/zstd/compress/zstd_compress.c:ZSTD_initCStream_usingCDict_advanced
  - lib/zstd/compress/zstd_compress.c:ZSTD_initCStream_internal
  - lib/zstd/compress/zstd_compress.c:ZSTD_resetCStream
Direct callers:
  - lib/zstd/zstd_compress_module.c:zstd_init_cstream
  - lib/zstd/zstd_compress_module.c:zstd_compress_cctx
```
**Symbols:**

```
ffffffff81716220-ffffffff8171625b: ZSTD_CCtx_setPledgedSrcSize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
size_t ZSTD_CCtx_setPledgedSrcSize(ZSTD_CCtx *cctx, long long unsigned int pledgedSrcSize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff8181178b)
Location: lib/zstd/compress/zstd_compress.c:1009
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_initCStream_srcSize
  - lib/zstd/compress/zstd_compress.c:ZSTD_initCStream_advanced
  - lib/zstd/compress/zstd_compress.c:ZSTD_initCStream_usingCDict_advanced
  - lib/zstd/compress/zstd_compress.c:ZSTD_initCStream_internal
  - lib/zstd/compress/zstd_compress.c:ZSTD_resetCStream
Direct callers:
  - lib/zstd/zstd_compress_module.c:zstd_reset_cstream
  - lib/zstd/zstd_compress_module.c:zstd_init_cstream
  - lib/zstd/zstd_compress_module.c:zstd_compress_cctx
```
**Symbols:**

```
ffffffff8180a230-ffffffff8180a26b: ZSTD_CCtx_setPledgedSrcSize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
size_t ZSTD_CCtx_setPledgedSrcSize(ZSTD_CCtx *cctx, long long unsigned int pledgedSrcSize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff8185226b)
Location: lib/zstd/compress/zstd_compress.c:1009
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_initCStream_srcSize
  - lib/zstd/compress/zstd_compress.c:ZSTD_initCStream_advanced
  - lib/zstd/compress/zstd_compress.c:ZSTD_initCStream_usingCDict_advanced
  - lib/zstd/compress/zstd_compress.c:ZSTD_initCStream_internal
  - lib/zstd/compress/zstd_compress.c:ZSTD_resetCStream
Direct callers:
  - lib/zstd/zstd_compress_module.c:zstd_reset_cstream
  - lib/zstd/zstd_compress_module.c:zstd_init_cstream
  - lib/zstd/zstd_compress_module.c:zstd_compress_cctx
```
**Symbols:**

```
ffffffff8184ace0-ffffffff8184ad1b: ZSTD_CCtx_setPledgedSrcSize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
size_t ZSTD_CCtx_setPledgedSrcSize(ZSTD_CCtx *cctx, long long unsigned int pledgedSrcSize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff818a3e2b)
Location: lib/zstd/compress/zstd_compress.c:1009
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_initCStream_srcSize
  - lib/zstd/compress/zstd_compress.c:ZSTD_initCStream_advanced
  - lib/zstd/compress/zstd_compress.c:ZSTD_initCStream_usingCDict_advanced
  - lib/zstd/compress/zstd_compress.c:ZSTD_initCStream_internal
  - lib/zstd/compress/zstd_compress.c:ZSTD_resetCStream
Direct callers:
  - lib/zstd/zstd_compress_module.c:zstd_reset_cstream
  - lib/zstd/zstd_compress_module.c:zstd_init_cstream
  - lib/zstd/zstd_compress_module.c:zstd_compress_cctx
```
**Symbols:**

```
ffffffff8189c8a0-ffffffff8189c8db: ZSTD_CCtx_setPledgedSrcSize (STB_GLOBAL)
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
