# Function: <code>ZSTD_getCParams_internal</code>

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
ZSTD_compressionParameters ZSTD_getCParams_internal(int compressionLevel, long long unsigned int srcSizeHint, size_t dictSize, ZSTD_cParamMode_e mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff817117c0)
Location: lib/zstd/compress/zstd_compress.c:5055
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_getParams_internal
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressBegin_usingCDict_advanced
  - lib/zstd/compress/zstd_compress.c:ZSTD_createCDict_byReference
  - lib/zstd/compress/zstd_compress.c:ZSTD_createCDict
  - lib/zstd/compress/zstd_compress.c:ZSTD_createCDict_advanced2
  - lib/zstd/compress/zstd_compress.c:ZSTD_estimateCDictSize
  - lib/zstd/compress/zstd_compress.c:ZSTD_estimateCStreamSize
  - lib/zstd/compress/zstd_compress.c:ZSTD_estimateCCtxSize
  - lib/zstd/compress/zstd_compress.c:ZSTD_getCParamsFromCCtxParams
```
**Symbols:**

```
ffffffff817117c0-ffffffff81711a04: ZSTD_getCParams_internal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ZSTD_compressionParameters ZSTD_getCParams_internal(int compressionLevel, long long unsigned int srcSizeHint, size_t dictSize, ZSTD_cParamMode_e mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff818042e0)
Location: lib/zstd/compress/zstd_compress.c:6072
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_getParams_internal
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressBegin_usingCDict_internal
  - lib/zstd/compress/zstd_compress.c:ZSTD_createCDict_byReference
  - lib/zstd/compress/zstd_compress.c:ZSTD_createCDict
  - lib/zstd/compress/zstd_compress.c:ZSTD_createCDict_advanced2
  - lib/zstd/compress/zstd_compress.c:ZSTD_estimateCDictSize
  - lib/zstd/compress/zstd_compress.c:ZSTD_estimateCStreamSize
  - lib/zstd/compress/zstd_compress.c:ZSTD_estimateCCtxSize
  - lib/zstd/compress/zstd_compress.c:ZSTD_getCParamsFromCCtxParams
```
**Symbols:**

```
ffffffff818042e0-ffffffff81804524: ZSTD_getCParams_internal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ZSTD_compressionParameters ZSTD_getCParams_internal(int compressionLevel, long long unsigned int srcSizeHint, size_t dictSize, ZSTD_cParamMode_e mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff81844cd0)
Location: lib/zstd/compress/zstd_compress.c:6072
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_getParams_internal
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressBegin_usingCDict_internal
  - lib/zstd/compress/zstd_compress.c:ZSTD_createCDict_byReference
  - lib/zstd/compress/zstd_compress.c:ZSTD_createCDict
  - lib/zstd/compress/zstd_compress.c:ZSTD_createCDict_advanced2
  - lib/zstd/compress/zstd_compress.c:ZSTD_estimateCDictSize
  - lib/zstd/compress/zstd_compress.c:ZSTD_estimateCStreamSize
  - lib/zstd/compress/zstd_compress.c:ZSTD_estimateCCtxSize
  - lib/zstd/compress/zstd_compress.c:ZSTD_getCParamsFromCCtxParams
```
**Symbols:**

```
ffffffff81844cd0-ffffffff81844f14: ZSTD_getCParams_internal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ZSTD_compressionParameters ZSTD_getCParams_internal(int compressionLevel, long long unsigned int srcSizeHint, size_t dictSize, ZSTD_cParamMode_e mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff81896890)
Location: lib/zstd/compress/zstd_compress.c:6072
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_getParams_internal
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressBegin_usingCDict_internal
  - lib/zstd/compress/zstd_compress.c:ZSTD_createCDict_byReference
  - lib/zstd/compress/zstd_compress.c:ZSTD_createCDict
  - lib/zstd/compress/zstd_compress.c:ZSTD_createCDict_advanced2
  - lib/zstd/compress/zstd_compress.c:ZSTD_estimateCDictSize
  - lib/zstd/compress/zstd_compress.c:ZSTD_estimateCStreamSize
  - lib/zstd/compress/zstd_compress.c:ZSTD_estimateCCtxSize
  - lib/zstd/compress/zstd_compress.c:ZSTD_getCParamsFromCCtxParams
```
**Symbols:**

```
ffffffff81896890-ffffffff81896ad4: ZSTD_getCParams_internal (STB_LOCAL)
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
