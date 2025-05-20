# Function: <code>ZSTD_getCParams</code>

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
ZSTD_compressionParameters ZSTD_getCParams(int compressionLevel, long long unsigned int srcSize, size_t dictSize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/compress.c (ffffffff815b149d)
Location: lib/zstd/compress.c:3411
Inline: True
Inline callers:
  - lib/zstd/compress.c:ZSTD_getParams
```
**Symbols:**

```
ffffffff815b0fe0-ffffffff815b1175: ZSTD_getCParams (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
ZSTD_compressionParameters ZSTD_getCParams(int compressionLevel, long long unsigned int srcSize, size_t dictSize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/compress.c (ffffffff815cbe92)
Location: lib/zstd/compress.c:3411
Inline: True
Inline callers:
  - lib/zstd/compress.c:ZSTD_getParams
```
**Symbols:**

```
ffffffff815cb9a0-ffffffff815cbb3a: ZSTD_getCParams (STB_GLOBAL)
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
ZSTD_compressionParameters ZSTD_getCParams(int compressionLevel, long long unsigned int srcSizeHint, size_t dictSize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff8171b9af)
Location: lib/zstd/compress/zstd_compress.c:5082
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressBegin_usingCDict_advanced
```
**Symbols:**

```
ffffffff8171c7d0-ffffffff8171c835: ZSTD_getCParams (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
ZSTD_compressionParameters ZSTD_getCParams(int compressionLevel, long long unsigned int srcSizeHint, size_t dictSize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff8180e536)
Location: lib/zstd/compress/zstd_compress.c:6100
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressBegin_usingCDict_internal
```
**Symbols:**

```
ffffffff818120c0-ffffffff81812125: ZSTD_getCParams (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
ZSTD_compressionParameters ZSTD_getCParams(int compressionLevel, long long unsigned int srcSizeHint, size_t dictSize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff8184f046)
Location: lib/zstd/compress/zstd_compress.c:6100
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressBegin_usingCDict_internal
```
**Symbols:**

```
ffffffff81852bc0-ffffffff81852c25: ZSTD_getCParams (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
ZSTD_compressionParameters ZSTD_getCParams(int compressionLevel, long long unsigned int srcSizeHint, size_t dictSize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff818a0c06)
Location: lib/zstd/compress/zstd_compress.c:6100
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressBegin_usingCDict_internal
```
**Symbols:**

```
ffffffff818a4780-ffffffff818a47e5: ZSTD_getCParams (STB_GLOBAL)
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
