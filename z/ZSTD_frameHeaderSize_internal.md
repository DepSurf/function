# Function: <code>ZSTD_frameHeaderSize_internal</code>

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
size_t ZSTD_frameHeaderSize_internal(const void *src, size_t srcSize, ZSTD_format_e format);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress/zstd_decompress.c (ffffffff81751695)
Location: lib/zstd/decompress/zstd_decompress.c:378
Inline: True
Inline callers:
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_frameHeaderSize
Direct callers:
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_decompressFrame
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_getFrameHeader_advanced
```
**Symbols:**

```
ffffffff81750c30-ffffffff81750ce2: ZSTD_frameHeaderSize_internal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
size_t ZSTD_frameHeaderSize_internal(const void *src, size_t srcSize, ZSTD_format_e format);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress/zstd_decompress.c (ffffffff81875905)
Location: lib/zstd/decompress/zstd_decompress.c:394
Inline: True
Inline callers:
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_frameHeaderSize
Direct callers:
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_decompressFrame
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_getFrameHeader_advanced
```
**Symbols:**

```
ffffffff81874e60-ffffffff81874f12: ZSTD_frameHeaderSize_internal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
size_t ZSTD_frameHeaderSize_internal(const void *src, size_t srcSize, ZSTD_format_e format);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress/zstd_decompress.c (ffffffff818b6655)
Location: lib/zstd/decompress/zstd_decompress.c:394
Inline: True
Inline callers:
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_frameHeaderSize
Direct callers:
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_decompressFrame
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_getFrameHeader_advanced
```
**Symbols:**

```
ffffffff818b5bb0-ffffffff818b5c62: ZSTD_frameHeaderSize_internal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
size_t ZSTD_frameHeaderSize_internal(const void *src, size_t srcSize, ZSTD_format_e format);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress/zstd_decompress.c (ffffffff81908215)
Location: lib/zstd/decompress/zstd_decompress.c:394
Inline: True
Inline callers:
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_frameHeaderSize
Direct callers:
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_decompressFrame
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_getFrameHeader_advanced
```
**Symbols:**

```
ffffffff81907770-ffffffff81907822: ZSTD_frameHeaderSize_internal (STB_LOCAL)
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
