# Function: <code>ZSTD_getFrameHeader</code>

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
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
size_t ZSTD_getFrameHeader(ZSTD_frameHeader *zfhPtr, const void *src, size_t srcSize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress/zstd_decompress.c (ffffffff81754370)
Location: lib/zstd/decompress/zstd_decompress.c:495
Inline: True
Inline callers:
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_estimateDStreamSize_fromFrame
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_getDictID_fromFrame
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_findFrameSizeInfo
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_getDecompressedSize
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_findDecompressedSize
Direct callers:
  - lib/zstd/zstd_decompress_module.c:zstd_get_frame_header
```
**Symbols:**

```
ffffffff817525c0-ffffffff817525de: ZSTD_getFrameHeader (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
size_t ZSTD_getFrameHeader(ZSTD_frameHeader *zfhPtr, const void *src, size_t srcSize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress/zstd_decompress.c (ffffffff81878980)
Location: lib/zstd/decompress/zstd_decompress.c:511
Inline: True
Inline callers:
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_estimateDStreamSize_fromFrame
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_getDictID_fromFrame
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_findFrameSizeInfo
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_getDecompressedSize
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_findDecompressedSize
Direct callers:
  - lib/zstd/zstd_decompress_module.c:zstd_get_frame_header
```
**Symbols:**

```
ffffffff818768a0-ffffffff818768be: ZSTD_getFrameHeader (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
size_t ZSTD_getFrameHeader(ZSTD_frameHeader *zfhPtr, const void *src, size_t srcSize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress/zstd_decompress.c (ffffffff818b9730)
Location: lib/zstd/decompress/zstd_decompress.c:511
Inline: True
Inline callers:
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_estimateDStreamSize_fromFrame
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_getDictID_fromFrame
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_findFrameSizeInfo
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_getDecompressedSize
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_findDecompressedSize
Direct callers:
  - lib/zstd/zstd_decompress_module.c:zstd_get_frame_header
```
**Symbols:**

```
ffffffff818b7640-ffffffff818b765e: ZSTD_getFrameHeader (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
size_t ZSTD_getFrameHeader(ZSTD_frameHeader *zfhPtr, const void *src, size_t srcSize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress/zstd_decompress.c (ffffffff8190b2f0)
Location: lib/zstd/decompress/zstd_decompress.c:511
Inline: True
Inline callers:
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_estimateDStreamSize_fromFrame
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_getDictID_fromFrame
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_findFrameSizeInfo
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_getDecompressedSize
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_findDecompressedSize
Direct callers:
  - lib/zstd/zstd_decompress_module.c:zstd_get_frame_header
```
**Symbols:**

```
ffffffff81909200-ffffffff8190921e: ZSTD_getFrameHeader (STB_GLOBAL)
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
