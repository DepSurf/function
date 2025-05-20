# Function: <code>ZSTD_CCtxParams_init_internal</code>

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
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff8171b8db)
Location: lib/zstd/compress/zstd_compress.c:268
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressBegin_usingCDict_advanced
  - lib/zstd/compress/zstd_compress.c:ZSTD_compress_usingDict
  - lib/zstd/compress/zstd_compress.c:ZSTD_compress_advanced
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressBegin_usingDict
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressBegin_advanced
  - lib/zstd/compress/zstd_compress.c:ZSTD_CCtxParams_init_advanced
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ZSTD_CCtxParams_init_internal(ZSTD_CCtx_params *cctxParams, const ZSTD_parameters *params, int compressionLevel);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff81805f30)
Location: lib/zstd/compress/zstd_compress.c:335
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressBegin_usingCDict_internal
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressBegin_usingCDict_internal
  - lib/zstd/compress/zstd_compress.c:ZSTD_compress_usingDict
  - lib/zstd/compress/zstd_compress.c:ZSTD_compress_advanced
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressBegin_usingDict
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressBegin_advanced
  - lib/zstd/compress/zstd_compress.c:ZSTD_CCtxParams_init_advanced
```
**Symbols:**

```
ffffffff81805f30-ffffffff81806008: ZSTD_CCtxParams_init_internal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ZSTD_CCtxParams_init_internal(ZSTD_CCtx_params *cctxParams, const ZSTD_parameters *params, int compressionLevel);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff81846920)
Location: lib/zstd/compress/zstd_compress.c:335
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressBegin_usingCDict_internal
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressBegin_usingCDict_internal
  - lib/zstd/compress/zstd_compress.c:ZSTD_compress_usingDict
  - lib/zstd/compress/zstd_compress.c:ZSTD_compress_advanced
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressBegin_usingDict
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressBegin_advanced
  - lib/zstd/compress/zstd_compress.c:ZSTD_CCtxParams_init_advanced
```
**Symbols:**

```
ffffffff81846920-ffffffff818469f8: ZSTD_CCtxParams_init_internal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ZSTD_CCtxParams_init_internal(ZSTD_CCtx_params *cctxParams, const ZSTD_parameters *params, int compressionLevel);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff818984e0)
Location: lib/zstd/compress/zstd_compress.c:335
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressBegin_usingCDict_internal
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressBegin_usingCDict_internal
  - lib/zstd/compress/zstd_compress.c:ZSTD_compress_usingDict
  - lib/zstd/compress/zstd_compress.c:ZSTD_compress_advanced
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressBegin_usingDict
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressBegin_advanced
  - lib/zstd/compress/zstd_compress.c:ZSTD_CCtxParams_init_advanced
```
**Symbols:**

```
ffffffff818984e0-ffffffff818985b8: ZSTD_CCtxParams_init_internal (STB_LOCAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
