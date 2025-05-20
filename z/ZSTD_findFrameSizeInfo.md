# Function: <code>ZSTD_findFrameSizeInfo</code>

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
ZSTD_frameSizeInfo ZSTD_findFrameSizeInfo(const void *src, size_t srcSize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress/zstd_decompress.c (ffffffff81752410)
Location: lib/zstd/decompress/zstd_decompress.c:633
Inline: False
Direct callers:
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_decompressStream
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_decompressBound
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_findDecompressedSize
```
**Symbols:**

```
ffffffff81752410-ffffffff817525b7: ZSTD_findFrameSizeInfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ZSTD_frameSizeInfo ZSTD_findFrameSizeInfo(const void *src, size_t srcSize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress/zstd_decompress.c (ffffffff818766e0)
Location: lib/zstd/decompress/zstd_decompress.c:679
Inline: False
Direct callers:
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_decompressStream
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_decompressBound
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_findDecompressedSize
```
**Symbols:**

```
ffffffff818766e0-ffffffff81876887: ZSTD_findFrameSizeInfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ZSTD_frameSizeInfo ZSTD_findFrameSizeInfo(const void *src, size_t srcSize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress/zstd_decompress.c (ffffffff818b7490)
Location: lib/zstd/decompress/zstd_decompress.c:679
Inline: False
Direct callers:
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_decompressStream
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_decompressBound
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_findDecompressedSize
```
**Symbols:**

```
ffffffff818b7490-ffffffff818b762b: ZSTD_findFrameSizeInfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ZSTD_frameSizeInfo ZSTD_findFrameSizeInfo(const void *src, size_t srcSize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress/zstd_decompress.c (ffffffff81909050)
Location: lib/zstd/decompress/zstd_decompress.c:679
Inline: False
Direct callers:
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_decompressStream
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_decompressBound
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_findDecompressedSize
```
**Symbols:**

```
ffffffff81909050-ffffffff819091eb: ZSTD_findFrameSizeInfo (STB_LOCAL)
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
