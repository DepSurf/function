# Function: <code>HUF_estimateCompressedSize</code>

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
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/zstd/huf_compress.c (ffffffff815ae9f3)
Location: lib/zstd/huf_compress.c:501
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/zstd/huf_compress.c (ffffffff815ca578)
Location: lib/zstd/huf_compress.c:501
Inline: True
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
size_t HUF_estimateCompressedSize(const HUF_CElt *CTable, const unsigned int *count, unsigned int maxSymbolValue);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/huf_compress.c (ffffffff817110fc)
Location: lib/zstd/compress/huf_compress.c:541
Inline: True
Inline callers:
  - lib/zstd/compress/huf_compress.c:HUF_compress_internal
  - lib/zstd/compress/huf_compress.c:HUF_compress_internal
```
**Symbols:**

```
ffffffff817112d0-ffffffff81711327: HUF_estimateCompressedSize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
size_t HUF_estimateCompressedSize(const HUF_CElt *CTable, const unsigned int *count, unsigned int maxSymbolValue);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/huf_compress.c (ffffffff81803bdb)
Location: lib/zstd/compress/huf_compress.c:707
Inline: True
Inline callers:
  - lib/zstd/compress/huf_compress.c:HUF_compress_internal
  - lib/zstd/compress/huf_compress.c:HUF_compress_internal
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_buildEntropyStatisticsAndEstimateSubBlockSize
  - lib/zstd/compress/zstd_compress.c:ZSTD_buildBlockEntropyStats_literals
  - lib/zstd/compress/zstd_compress.c:ZSTD_buildBlockEntropyStats_literals
```
**Symbols:**

```
ffffffff81803c70-ffffffff81803cca: HUF_estimateCompressedSize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
size_t HUF_estimateCompressedSize(const HUF_CElt *CTable, const unsigned int *count, unsigned int maxSymbolValue);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/huf_compress.c (ffffffff818445cc)
Location: lib/zstd/compress/huf_compress.c:707
Inline: True
Inline callers:
  - lib/zstd/compress/huf_compress.c:HUF_compress_internal
  - lib/zstd/compress/huf_compress.c:HUF_compress_internal
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_buildEntropyStatisticsAndEstimateSubBlockSize
  - lib/zstd/compress/zstd_compress.c:ZSTD_buildBlockEntropyStats_literals
  - lib/zstd/compress/zstd_compress.c:ZSTD_buildBlockEntropyStats_literals
```
**Symbols:**

```
ffffffff81844660-ffffffff818446ba: HUF_estimateCompressedSize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
size_t HUF_estimateCompressedSize(const HUF_CElt *CTable, const unsigned int *count, unsigned int maxSymbolValue);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/huf_compress.c (ffffffff8189618c)
Location: lib/zstd/compress/huf_compress.c:707
Inline: True
Inline callers:
  - lib/zstd/compress/huf_compress.c:HUF_compress_internal
  - lib/zstd/compress/huf_compress.c:HUF_compress_internal
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_buildEntropyStatisticsAndEstimateSubBlockSize
  - lib/zstd/compress/zstd_compress.c:ZSTD_buildBlockEntropyStats_literals
  - lib/zstd/compress/zstd_compress.c:ZSTD_buildBlockEntropyStats_literals
```
**Symbols:**

```
ffffffff81896220-ffffffff8189627a: HUF_estimateCompressedSize (STB_GLOBAL)
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
