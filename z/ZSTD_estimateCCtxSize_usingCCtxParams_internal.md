# Function: <code>ZSTD_estimateCCtxSize_usingCCtxParams_internal</code>

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
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
size_t ZSTD_estimateCCtxSize_usingCCtxParams_internal(const ZSTD_compressionParameters *cParams, const ldmParams_t *ldmParams, const int isStatic, const size_t buffInSize, const size_t buffOutSize, const U64 pledgedSrcSize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (0)
Location: lib/zstd/compress/zstd_compress.c:1258
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_resetCCtx_internal
  - lib/zstd/compress/zstd_compress.c:ZSTD_estimateCCtxSize_usingCCtxParams
```
**Symbols:**

```
ffffffff81711d90-ffffffff81711ef4: ZSTD_estimateCCtxSize_usingCCtxParams_internal (STB_LOCAL)
ffffffff81e96e97-ffffffff81e96f5f: ZSTD_estimateCCtxSize_usingCCtxParams_internal.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
size_t ZSTD_estimateCCtxSize_usingCCtxParams_internal(const ZSTD_compressionParameters *cParams, const ldmParams_t *ldmParams, const int isStatic, const ZSTD_paramSwitch_e useRowMatchFinder, const size_t buffInSize, const size_t buffOutSize, const U64 pledgedSrcSize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (0)
Location: lib/zstd/compress/zstd_compress.c:1389
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_resetCCtx_internal
  - lib/zstd/compress/zstd_compress.c:ZSTD_estimateCCtxSize_usingCCtxParams
```
**Symbols:**

```
ffffffff818049d0-ffffffff81804b5d: ZSTD_estimateCCtxSize_usingCCtxParams_internal (STB_LOCAL)
ffffffff8207da0d-ffffffff8207daf1: ZSTD_estimateCCtxSize_usingCCtxParams_internal.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
size_t ZSTD_estimateCCtxSize_usingCCtxParams_internal(const ZSTD_compressionParameters *cParams, const ldmParams_t *ldmParams, const int isStatic, const ZSTD_paramSwitch_e useRowMatchFinder, const size_t buffInSize, const size_t buffOutSize, const U64 pledgedSrcSize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (0)
Location: lib/zstd/compress/zstd_compress.c:1389
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_resetCCtx_internal
  - lib/zstd/compress/zstd_compress.c:ZSTD_estimateCCtxSize_usingCCtxParams
```
**Symbols:**

```
ffffffff818453d0-ffffffff8184555d: ZSTD_estimateCCtxSize_usingCCtxParams_internal (STB_LOCAL)
ffffffff820fdfc0-ffffffff820fe0a4: ZSTD_estimateCCtxSize_usingCCtxParams_internal.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
size_t ZSTD_estimateCCtxSize_usingCCtxParams_internal(const ZSTD_compressionParameters *cParams, const ldmParams_t *ldmParams, const int isStatic, const ZSTD_paramSwitch_e useRowMatchFinder, const size_t buffInSize, const size_t buffOutSize, const U64 pledgedSrcSize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (0)
Location: lib/zstd/compress/zstd_compress.c:1389
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_resetCCtx_internal
  - lib/zstd/compress/zstd_compress.c:ZSTD_estimateCCtxSize_usingCCtxParams
```
**Symbols:**

```
ffffffff81896f90-ffffffff8189711d: ZSTD_estimateCCtxSize_usingCCtxParams_internal (STB_LOCAL)
ffffffff821dc12d-ffffffff821dc211: ZSTD_estimateCCtxSize_usingCCtxParams_internal.cold (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const ZSTD_paramSwitch_e useRowMatchFinder</code>
</li>
<li>
<b>Param reordered. </b>
<code>cParams, ldmParams, isStatic, buffInSize, buffOutSize, pledgedSrcSize</code> ➡️ <code>cParams, ldmParams, isStatic, useRowMatchFinder, buffInSize, buffOutSize, pledgedSrcSize</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
