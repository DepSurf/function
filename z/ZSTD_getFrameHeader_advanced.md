# Function: <code>ZSTD_getFrameHeader_advanced</code>

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
size_t ZSTD_getFrameHeader_advanced(ZSTD_frameHeader *zfhPtr, const void *src, size_t srcSize, ZSTD_format_e format);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress/zstd_decompress.c (ffffffff81751740)
Location: lib/zstd/decompress/zstd_decompress.c:409
Inline: False
Direct callers:
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_decompressStream
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_estimateDStreamSize_fromFrame
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_getDictID_fromFrame
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_findFrameSizeInfo
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_getDecompressedSize
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_findDecompressedSize
```
**Symbols:**

```
ffffffff81751740-ffffffff8175195a: ZSTD_getFrameHeader_advanced (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
size_t ZSTD_getFrameHeader_advanced(ZSTD_frameHeader *zfhPtr, const void *src, size_t srcSize, ZSTD_format_e format);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress/zstd_decompress.c (ffffffff818759c0)
Location: lib/zstd/decompress/zstd_decompress.c:425
Inline: False
Direct callers:
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_decompressStream
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_estimateDStreamSize_fromFrame
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_getDictID_fromFrame
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_findFrameSizeInfo
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_getDecompressedSize
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_findDecompressedSize
```
**Symbols:**

```
ffffffff818759c0-ffffffff81875bda: ZSTD_getFrameHeader_advanced (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
size_t ZSTD_getFrameHeader_advanced(ZSTD_frameHeader *zfhPtr, const void *src, size_t srcSize, ZSTD_format_e format);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress/zstd_decompress.c (ffffffff818b6710)
Location: lib/zstd/decompress/zstd_decompress.c:425
Inline: False
Direct callers:
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_decompressStream
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_estimateDStreamSize_fromFrame
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_getDictID_fromFrame
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_findFrameSizeInfo
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_getDecompressedSize
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_findDecompressedSize
```
**Symbols:**

```
ffffffff818b6710-ffffffff818b6934: ZSTD_getFrameHeader_advanced (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
size_t ZSTD_getFrameHeader_advanced(ZSTD_frameHeader *zfhPtr, const void *src, size_t srcSize, ZSTD_format_e format);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress/zstd_decompress.c (ffffffff819082d0)
Location: lib/zstd/decompress/zstd_decompress.c:425
Inline: False
Direct callers:
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_decompressStream
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_estimateDStreamSize_fromFrame
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_getDictID_fromFrame
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_findFrameSizeInfo
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_getDecompressedSize
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_findDecompressedSize
```
**Symbols:**

```
ffffffff819082d0-ffffffff819084f4: ZSTD_getFrameHeader_advanced (STB_GLOBAL)
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
