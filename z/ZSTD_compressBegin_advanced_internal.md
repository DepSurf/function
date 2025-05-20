# Function: <code>ZSTD_compressBegin_advanced_internal</code>

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
size_t ZSTD_compressBegin_advanced_internal(ZSTD_CCtx *cctx, const void *dict, size_t dictSize, ZSTD_dictContentType_e dictContentType, ZSTD_dictTableLoadMethod_e dtlm, const ZSTD_CDict *cdict, const ZSTD_CCtx_params *params, long long unsigned int pledgedSrcSize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff817192c4)
Location: lib/zstd/compress/zstd_compress.c:3358
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressBegin_advanced
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressBegin_advanced
```
**Symbols:**

```
ffffffff81719190-ffffffff81719232: ZSTD_compressBegin_advanced_internal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
size_t ZSTD_compressBegin_advanced_internal(ZSTD_CCtx *cctx, const void *dict, size_t dictSize, ZSTD_dictContentType_e dictContentType, ZSTD_dictTableLoadMethod_e dtlm, const ZSTD_CDict *cdict, const ZSTD_CCtx_params *params, long long unsigned int pledgedSrcSize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff8180e914)
Location: lib/zstd/compress/zstd_compress.c:4442
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressBegin_advanced
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressBegin_advanced
```
**Symbols:**

```
ffffffff8180e800-ffffffff8180e8a2: ZSTD_compressBegin_advanced_internal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
size_t ZSTD_compressBegin_advanced_internal(ZSTD_CCtx *cctx, const void *dict, size_t dictSize, ZSTD_dictContentType_e dictContentType, ZSTD_dictTableLoadMethod_e dtlm, const ZSTD_CDict *cdict, const ZSTD_CCtx_params *params, long long unsigned int pledgedSrcSize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff8184f424)
Location: lib/zstd/compress/zstd_compress.c:4442
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressBegin_advanced
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressBegin_advanced
```
**Symbols:**

```
ffffffff8184f310-ffffffff8184f3b2: ZSTD_compressBegin_advanced_internal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
size_t ZSTD_compressBegin_advanced_internal(ZSTD_CCtx *cctx, const void *dict, size_t dictSize, ZSTD_dictContentType_e dictContentType, ZSTD_dictTableLoadMethod_e dtlm, const ZSTD_CDict *cdict, const ZSTD_CCtx_params *params, long long unsigned int pledgedSrcSize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff818a0fe4)
Location: lib/zstd/compress/zstd_compress.c:4442
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressBegin_advanced
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressBegin_advanced
```
**Symbols:**

```
ffffffff818a0ed0-ffffffff818a0f72: ZSTD_compressBegin_advanced_internal (STB_GLOBAL)
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
