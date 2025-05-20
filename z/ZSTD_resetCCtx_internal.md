# Function: <code>ZSTD_resetCCtx_internal</code>

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
size_t ZSTD_resetCCtx_internal(ZSTD_CCtx *zc, ZSTD_CCtx_params params, const U64 pledgedSrcSize, const ZSTD_compResetPolicy_e crp, const ZSTD_buffered_policy_e zbuff);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (0)
Location: lib/zstd/compress/zstd_compress.c:1558
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressBegin_internal
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressBegin_internal
  - lib/zstd/compress/zstd_compress.c:ZSTD_resetCCtx_usingCDict
  - lib/zstd/compress/zstd_compress.c:ZSTD_resetCCtx_usingCDict
```
**Symbols:**

```
ffffffff81713d40-ffffffff817148ab: ZSTD_resetCCtx_internal (STB_LOCAL)
ffffffff81e9711d-ffffffff81e97202: ZSTD_resetCCtx_internal.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
size_t ZSTD_resetCCtx_internal(ZSTD_CCtx *zc, const ZSTD_CCtx_params *params, const U64 pledgedSrcSize, const size_t loadedDictSize, const ZSTD_compResetPolicy_e crp, const ZSTD_buffered_policy_e zbuff);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (0)
Location: lib/zstd/compress/zstd_compress.c:1748
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressBegin_usingDict
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressBegin_internal
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressBegin_internal
  - lib/zstd/compress/zstd_compress.c:ZSTD_resetCCtx_usingCDict
  - lib/zstd/compress/zstd_compress.c:ZSTD_resetCCtx_byCopyingCDict
```
**Symbols:**

```
ffffffff81807790-ffffffff818084bc: ZSTD_resetCCtx_internal (STB_LOCAL)
ffffffff8207dca5-ffffffff8207ddce: ZSTD_resetCCtx_internal.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
size_t ZSTD_resetCCtx_internal(ZSTD_CCtx *zc, const ZSTD_CCtx_params *params, const U64 pledgedSrcSize, const size_t loadedDictSize, const ZSTD_compResetPolicy_e crp, const ZSTD_buffered_policy_e zbuff);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (0)
Location: lib/zstd/compress/zstd_compress.c:1748
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressBegin_usingDict
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressBegin_internal
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressBegin_internal
  - lib/zstd/compress/zstd_compress.c:ZSTD_resetCCtx_usingCDict
  - lib/zstd/compress/zstd_compress.c:ZSTD_resetCCtx_byCopyingCDict
```
**Symbols:**

```
ffffffff81848170-ffffffff81848ea7: ZSTD_resetCCtx_internal (STB_LOCAL)
ffffffff820fe258-ffffffff820fe37e: ZSTD_resetCCtx_internal.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
size_t ZSTD_resetCCtx_internal(ZSTD_CCtx *zc, const ZSTD_CCtx_params *params, const U64 pledgedSrcSize, const size_t loadedDictSize, const ZSTD_compResetPolicy_e crp, const ZSTD_buffered_policy_e zbuff);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (0)
Location: lib/zstd/compress/zstd_compress.c:1748
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressBegin_usingDict
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressBegin_internal
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressBegin_internal
  - lib/zstd/compress/zstd_compress.c:ZSTD_resetCCtx_usingCDict
  - lib/zstd/compress/zstd_compress.c:ZSTD_resetCCtx_byCopyingCDict
```
**Symbols:**

```
ffffffff81899d30-ffffffff8189aa67: ZSTD_resetCCtx_internal (STB_LOCAL)
ffffffff821dc3c5-ffffffff821dc4eb: ZSTD_resetCCtx_internal.cold (STB_LOCAL)
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
<code>const size_t loadedDictSize</code>
</li>
<li>
<b>Param reordered. </b>
<code>zc, params, pledgedSrcSize, crp, zbuff</code> ➡️ <code>zc, params, pledgedSrcSize, loadedDictSize, crp, zbuff</code>
</li>
<li>
<b>Param type changed. </b>
<code>ZSTD_CCtx_params params</code> ➡️ <code>const ZSTD_CCtx_params *params</code>
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
