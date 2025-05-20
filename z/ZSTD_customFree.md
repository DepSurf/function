# Function: <code>ZSTD_customFree</code>

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
void ZSTD_customFree(void *ptr, ZSTD_customMem customMem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/common/zstd_common.c (ffffffff8170d450)
Location: lib/zstd/common/zstd_common.c:75
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_freeCDict
  - lib/zstd/compress/zstd_compress.c:ZSTD_freeCDict
  - lib/zstd/compress/zstd_compress.c:ZSTD_freeCDict
  - lib/zstd/compress/zstd_compress.c:ZSTD_createCDict_advanced2
  - lib/zstd/compress/zstd_compress.c:ZSTD_generateSequences
  - lib/zstd/compress/zstd_compress.c:ZSTD_resetCCtx_internal
  - lib/zstd/compress/zstd_compress.c:ZSTD_freeCCtxParams
  - lib/zstd/compress/zstd_compress.c:ZSTD_freeCCtx
  - lib/zstd/compress/zstd_compress.c:ZSTD_freeCCtx
  - lib/zstd/compress/zstd_compress.c:ZSTD_freeCCtx
  - lib/zstd/compress/zstd_compress.c:ZSTD_clearAllDicts
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_decompressStream
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_freeDCtx
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_freeDCtx
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_freeDCtx
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_freeDCtx
```
**Symbols:**

```
ffffffff8170d450-ffffffff8170d47f: ZSTD_customFree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ZSTD_customFree(void *ptr, ZSTD_customMem customMem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/common/zstd_common.c (ffffffff81887aa0)
Location: lib/zstd/common/zstd_common.c:75
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_freeCDict
  - lib/zstd/compress/zstd_compress.c:ZSTD_freeCDict
  - lib/zstd/compress/zstd_compress.c:ZSTD_freeCDict
  - lib/zstd/compress/zstd_compress.c:ZSTD_createCDict_advanced2
  - lib/zstd/compress/zstd_compress.c:ZSTD_generateSequences
  - lib/zstd/compress/zstd_compress.c:ZSTD_resetCCtx_internal
  - lib/zstd/compress/zstd_compress.c:ZSTD_freeCCtxParams
  - lib/zstd/compress/zstd_compress.c:ZSTD_freeCCtx
  - lib/zstd/compress/zstd_compress.c:ZSTD_freeCCtx
  - lib/zstd/compress/zstd_compress.c:ZSTD_freeCCtx
  - lib/zstd/compress/zstd_compress.c:ZSTD_clearAllDicts
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_decompressStream
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_freeDCtx
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_freeDCtx
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_freeDCtx
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_freeDCtx
```
**Symbols:**

```
ffffffff81887aa0-ffffffff81887acf: ZSTD_customFree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ZSTD_customFree(void *ptr, ZSTD_customMem customMem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/common/zstd_common.c (ffffffff818c9e20)
Location: lib/zstd/common/zstd_common.c:75
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_freeCDict
  - lib/zstd/compress/zstd_compress.c:ZSTD_freeCDict
  - lib/zstd/compress/zstd_compress.c:ZSTD_freeCDict
  - lib/zstd/compress/zstd_compress.c:ZSTD_createCDict_advanced2
  - lib/zstd/compress/zstd_compress.c:ZSTD_generateSequences
  - lib/zstd/compress/zstd_compress.c:ZSTD_resetCCtx_internal
  - lib/zstd/compress/zstd_compress.c:ZSTD_freeCCtxParams
  - lib/zstd/compress/zstd_compress.c:ZSTD_freeCCtx
  - lib/zstd/compress/zstd_compress.c:ZSTD_freeCCtx
  - lib/zstd/compress/zstd_compress.c:ZSTD_freeCCtx
  - lib/zstd/compress/zstd_compress.c:ZSTD_clearAllDicts
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_decompressStream
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_freeDCtx
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_freeDCtx
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_freeDCtx
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_freeDCtx
```
**Symbols:**

```
ffffffff818c9e20-ffffffff818c9e4f: ZSTD_customFree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ZSTD_customFree(void *ptr, ZSTD_customMem customMem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/common/zstd_common.c (ffffffff8191b9e0)
Location: lib/zstd/common/zstd_common.c:75
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_freeCDict
  - lib/zstd/compress/zstd_compress.c:ZSTD_freeCDict
  - lib/zstd/compress/zstd_compress.c:ZSTD_freeCDict
  - lib/zstd/compress/zstd_compress.c:ZSTD_createCDict_advanced2
  - lib/zstd/compress/zstd_compress.c:ZSTD_generateSequences
  - lib/zstd/compress/zstd_compress.c:ZSTD_resetCCtx_internal
  - lib/zstd/compress/zstd_compress.c:ZSTD_freeCCtxParams
  - lib/zstd/compress/zstd_compress.c:ZSTD_freeCCtx
  - lib/zstd/compress/zstd_compress.c:ZSTD_freeCCtx
  - lib/zstd/compress/zstd_compress.c:ZSTD_freeCCtx
  - lib/zstd/compress/zstd_compress.c:ZSTD_clearAllDicts
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_decompressStream
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_freeDCtx
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_freeDCtx
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_freeDCtx
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_freeDCtx
```
**Symbols:**

```
ffffffff8191b9e0-ffffffff8191ba0f: ZSTD_customFree (STB_GLOBAL)
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
