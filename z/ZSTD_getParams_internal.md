# Function: <code>ZSTD_getParams_internal</code>

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
ZSTD_parameters ZSTD_getParams_internal(int compressionLevel, long long unsigned int srcSizeHint, size_t dictSize, ZSTD_cParamMode_e mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff81711a10)
Location: lib/zstd/compress/zstd_compress.c:5092
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_getParams
  - lib/zstd/compress/zstd_compress.c:ZSTD_compress_usingDict
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressBegin_usingDict
```
**Symbols:**

```
ffffffff81711a10-ffffffff81711ad5: ZSTD_getParams_internal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ZSTD_parameters ZSTD_getParams_internal(int compressionLevel, long long unsigned int srcSizeHint, size_t dictSize, ZSTD_cParamMode_e mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff81804540)
Location: lib/zstd/compress/zstd_compress.c:6110
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_getParams
  - lib/zstd/compress/zstd_compress.c:ZSTD_compress_usingDict
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressBegin_usingDict
```
**Symbols:**

```
ffffffff81804540-ffffffff81804605: ZSTD_getParams_internal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ZSTD_parameters ZSTD_getParams_internal(int compressionLevel, long long unsigned int srcSizeHint, size_t dictSize, ZSTD_cParamMode_e mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff81844f30)
Location: lib/zstd/compress/zstd_compress.c:6110
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_getParams
  - lib/zstd/compress/zstd_compress.c:ZSTD_compress_usingDict
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressBegin_usingDict
```
**Symbols:**

```
ffffffff81844f30-ffffffff81844ff5: ZSTD_getParams_internal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ZSTD_parameters ZSTD_getParams_internal(int compressionLevel, long long unsigned int srcSizeHint, size_t dictSize, ZSTD_cParamMode_e mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff81896af0)
Location: lib/zstd/compress/zstd_compress.c:6110
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_getParams
  - lib/zstd/compress/zstd_compress.c:ZSTD_compress_usingDict
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressBegin_usingDict
```
**Symbols:**

```
ffffffff81896af0-ffffffff81896bb5: ZSTD_getParams_internal (STB_LOCAL)
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
