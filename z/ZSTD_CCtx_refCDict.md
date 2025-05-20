# Function: <code>ZSTD_CCtx_refCDict</code>

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
size_t ZSTD_CCtx_refCDict(ZSTD_CCtx *cctx, const ZSTD_CDict *cdict);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff8171c007)
Location: lib/zstd/compress/zstd_compress.c:986
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_initCStream
  - lib/zstd/compress/zstd_compress.c:ZSTD_initCStream_srcSize
  - lib/zstd/compress/zstd_compress.c:ZSTD_initCStream_usingCDict
  - lib/zstd/compress/zstd_compress.c:ZSTD_initCStream_usingCDict_advanced
  - lib/zstd/compress/zstd_compress.c:ZSTD_initCStream_internal
```
**Symbols:**

```
ffffffff8171a560-ffffffff8171a5a7: ZSTD_CCtx_refCDict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
size_t ZSTD_CCtx_refCDict(ZSTD_CCtx *cctx, const ZSTD_CDict *cdict);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff81811817)
Location: lib/zstd/compress/zstd_compress.c:1103
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_initCStream
  - lib/zstd/compress/zstd_compress.c:ZSTD_initCStream_srcSize
  - lib/zstd/compress/zstd_compress.c:ZSTD_initCStream_usingCDict
  - lib/zstd/compress/zstd_compress.c:ZSTD_initCStream_usingCDict_advanced
  - lib/zstd/compress/zstd_compress.c:ZSTD_initCStream_internal
```
**Symbols:**

```
ffffffff8180fc00-ffffffff8180fc47: ZSTD_CCtx_refCDict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
size_t ZSTD_CCtx_refCDict(ZSTD_CCtx *cctx, const ZSTD_CDict *cdict);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff81852307)
Location: lib/zstd/compress/zstd_compress.c:1103
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_initCStream
  - lib/zstd/compress/zstd_compress.c:ZSTD_initCStream_srcSize
  - lib/zstd/compress/zstd_compress.c:ZSTD_initCStream_usingCDict
  - lib/zstd/compress/zstd_compress.c:ZSTD_initCStream_usingCDict_advanced
  - lib/zstd/compress/zstd_compress.c:ZSTD_initCStream_internal
```
**Symbols:**

```
ffffffff818506e0-ffffffff81850727: ZSTD_CCtx_refCDict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
size_t ZSTD_CCtx_refCDict(ZSTD_CCtx *cctx, const ZSTD_CDict *cdict);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff818a3ec7)
Location: lib/zstd/compress/zstd_compress.c:1103
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_initCStream
  - lib/zstd/compress/zstd_compress.c:ZSTD_initCStream_srcSize
  - lib/zstd/compress/zstd_compress.c:ZSTD_initCStream_usingCDict
  - lib/zstd/compress/zstd_compress.c:ZSTD_initCStream_usingCDict_advanced
  - lib/zstd/compress/zstd_compress.c:ZSTD_initCStream_internal
```
**Symbols:**

```
ffffffff818a22a0-ffffffff818a22e7: ZSTD_CCtx_refCDict (STB_GLOBAL)
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
