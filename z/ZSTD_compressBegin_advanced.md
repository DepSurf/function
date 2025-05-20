# Function: <code>ZSTD_compressBegin_advanced</code>

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
size_t ZSTD_compressBegin_advanced(ZSTD_CCtx *cctx, const void *dict, size_t dictSize, ZSTD_parameters params, long long unsigned int pledgedSrcSize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/compress.c (ffffffff815b8063)
Location: lib/zstd/compress.c:2747
Inline: True
Inline callers:
  - lib/zstd/compress.c:ZSTD_resetCStream
  - lib/zstd/compress.c:ZSTD_resetCStream
  - lib/zstd/compress.c:ZSTD_initCDict
```
**Symbols:**

```
ffffffff815b8370-ffffffff815b8981: ZSTD_compressBegin_advanced (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
size_t ZSTD_compressBegin_advanced(ZSTD_CCtx *cctx, const void *dict, size_t dictSize, ZSTD_parameters params, long long unsigned int pledgedSrcSize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/compress.c (ffffffff815d5548)
Location: lib/zstd/compress.c:2747
Inline: True
Inline callers:
  - lib/zstd/compress.c:ZSTD_resetCStream
  - lib/zstd/compress.c:ZSTD_resetCStream
  - lib/zstd/compress.c:ZSTD_initCDict
```
**Symbols:**

```
ffffffff815d5850-ffffffff815d5e66: ZSTD_compressBegin_advanced (STB_GLOBAL)
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
<summary>In <code>5.19</code>: ✅</summary>

```c
size_t ZSTD_compressBegin_advanced(ZSTD_CCtx *cctx, const void *dict, size_t dictSize, ZSTD_parameters params, long long unsigned int pledgedSrcSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff81719240)
Location: lib/zstd/compress/zstd_compress.c:3378
Inline: False
```
**Symbols:**

```
ffffffff81719240-ffffffff8171933a: ZSTD_compressBegin_advanced (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
size_t ZSTD_compressBegin_advanced(ZSTD_CCtx *cctx, const void *dict, size_t dictSize, ZSTD_parameters params, long long unsigned int pledgedSrcSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff8180e8c0)
Location: lib/zstd/compress/zstd_compress.c:4462
Inline: False
```
**Symbols:**

```
ffffffff8180e8c0-ffffffff8180e9a9: ZSTD_compressBegin_advanced (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
size_t ZSTD_compressBegin_advanced(ZSTD_CCtx *cctx, const void *dict, size_t dictSize, ZSTD_parameters params, long long unsigned int pledgedSrcSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff8184f3d0)
Location: lib/zstd/compress/zstd_compress.c:4462
Inline: False
```
**Symbols:**

```
ffffffff8184f3d0-ffffffff8184f4b9: ZSTD_compressBegin_advanced (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
size_t ZSTD_compressBegin_advanced(ZSTD_CCtx *cctx, const void *dict, size_t dictSize, ZSTD_parameters params, long long unsigned int pledgedSrcSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff818a0f90)
Location: lib/zstd/compress/zstd_compress.c:4462
Inline: False
```
**Symbols:**

```
ffffffff818a0f90-ffffffff818a1079: ZSTD_compressBegin_advanced (STB_GLOBAL)
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
