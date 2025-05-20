# Function: <code>ZSTD_compressBegin_internal</code>

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
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/zstd/compress.c (ffffffff815b8106)
Location: lib/zstd/compress.c:2738
Inline: True
Inline callers:
  - lib/zstd/compress.c:ZSTD_resetCStream
  - lib/zstd/compress.c:ZSTD_resetCStream
  - lib/zstd/compress.c:ZSTD_initCDict
  - lib/zstd/compress.c:ZSTD_compressCCtx
  - lib/zstd/compress.c:ZSTD_compress_usingDict
  - lib/zstd/compress.c:ZSTD_compressBegin
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/zstd/compress.c (ffffffff815d55eb)
Location: lib/zstd/compress.c:2738
Inline: True
Inline callers:
  - lib/zstd/compress.c:ZSTD_resetCStream
  - lib/zstd/compress.c:ZSTD_resetCStream
  - lib/zstd/compress.c:ZSTD_initCDict
  - lib/zstd/compress.c:ZSTD_compressCCtx
  - lib/zstd/compress.c:ZSTD_compress_usingDict
  - lib/zstd/compress.c:ZSTD_compressBegin
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
size_t ZSTD_compressBegin_internal(ZSTD_CCtx *cctx, const void *dict, size_t dictSize, ZSTD_dictContentType_e dictContentType, ZSTD_dictTableLoadMethod_e dtlm, const ZSTD_CDict *cdict, const ZSTD_CCtx_params *params, U64 pledgedSrcSize, ZSTD_buffered_policy_e zbuff);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff81718d90)
Location: lib/zstd/compress/zstd_compress.c:3316
Inline: True
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_CCtx_init_compressStream2
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressBegin_usingCDict_advanced
  - lib/zstd/compress/zstd_compress.c:ZSTD_compress_usingDict
  - lib/zstd/compress/zstd_compress.c:ZSTD_compress_advanced
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressBegin_usingDict
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressBegin_advanced
```
**Symbols:**

```
ffffffff81718d90-ffffffff81718f80: ZSTD_compressBegin_internal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
size_t ZSTD_compressBegin_internal(ZSTD_CCtx *cctx, const void *dict, size_t dictSize, ZSTD_dictContentType_e dictContentType, ZSTD_dictTableLoadMethod_e dtlm, const ZSTD_CDict *cdict, const ZSTD_CCtx_params *params, U64 pledgedSrcSize, ZSTD_buffered_policy_e zbuff);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff8180ea40)
Location: lib/zstd/compress/zstd_compress.c:4398
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressBegin_usingDict
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_CCtx_init_compressStream2
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressBegin_usingCDict_internal
  - lib/zstd/compress/zstd_compress.c:ZSTD_compress_usingDict
  - lib/zstd/compress/zstd_compress.c:ZSTD_compress_advanced
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressBegin_advanced
```
**Symbols:**

```
ffffffff8180e1e0-ffffffff8180e386: ZSTD_compressBegin_internal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
size_t ZSTD_compressBegin_internal(ZSTD_CCtx *cctx, const void *dict, size_t dictSize, ZSTD_dictContentType_e dictContentType, ZSTD_dictTableLoadMethod_e dtlm, const ZSTD_CDict *cdict, const ZSTD_CCtx_params *params, U64 pledgedSrcSize, ZSTD_buffered_policy_e zbuff);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff8184f550)
Location: lib/zstd/compress/zstd_compress.c:4398
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressBegin_usingDict
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_CCtx_init_compressStream2
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressBegin_usingCDict_internal
  - lib/zstd/compress/zstd_compress.c:ZSTD_compress_usingDict
  - lib/zstd/compress/zstd_compress.c:ZSTD_compress_advanced
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressBegin_advanced
```
**Symbols:**

```
ffffffff8184ecf0-ffffffff8184ee96: ZSTD_compressBegin_internal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
size_t ZSTD_compressBegin_internal(ZSTD_CCtx *cctx, const void *dict, size_t dictSize, ZSTD_dictContentType_e dictContentType, ZSTD_dictTableLoadMethod_e dtlm, const ZSTD_CDict *cdict, const ZSTD_CCtx_params *params, U64 pledgedSrcSize, ZSTD_buffered_policy_e zbuff);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff818a1110)
Location: lib/zstd/compress/zstd_compress.c:4398
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressBegin_usingDict
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_CCtx_init_compressStream2
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressBegin_usingCDict_internal
  - lib/zstd/compress/zstd_compress.c:ZSTD_compress_usingDict
  - lib/zstd/compress/zstd_compress.c:ZSTD_compress_advanced
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressBegin_advanced
```
**Symbols:**

```
ffffffff818a08b0-ffffffff818a0a56: ZSTD_compressBegin_internal (STB_LOCAL)
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
