# Function: <code>ZSTD_noCompressBlock</code>

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
<summary>In <code>5.8</code>: ✅</summary>

```c
size_t ZSTD_noCompressBlock(void *dst, size_t dstCapacity, const void *src, size_t srcSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress.c (ffffffff815c8bc0)
Location: lib/zstd/compress.c:434
Inline: False
```
**Symbols:**

```
ffffffff815c8bc0-ffffffff815c8c12: ZSTD_noCompressBlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
size_t ZSTD_noCompressBlock(void *dst, size_t dstCapacity, const void *src, size_t srcSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress.c (ffffffff815e6720)
Location: lib/zstd/compress.c:434
Inline: False
```
**Symbols:**

```
ffffffff815e6720-ffffffff815e6777: ZSTD_noCompressBlock (STB_GLOBAL)
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
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff817181bb)
Location: lib/zstd/compress/zstd_compress_internal.h:435
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressSequences_internal
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressSequences_internal
  - lib/zstd/compress/zstd_compress.c:ZSTD_compress_frameChunk
  - lib/zstd/compress/zstd_compress.c:ZSTD_compress_frameChunk
```
```
In lib/zstd/compress/zstd_compress_superblock.c (ffffffff81720885)
Location: lib/zstd/compress/zstd_compress_internal.h:435
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff8180bf86)
Location: lib/zstd/compress/zstd_compress_internal.h:503
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressSequences_internal
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressSequences_internal
  - lib/zstd/compress/zstd_compress.c:ZSTD_compress_frameChunk
  - lib/zstd/compress/zstd_compress.c:ZSTD_compress_frameChunk
  - lib/zstd/compress/zstd_compress.c:ZSTD_compress_frameChunk
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressSeqStore_singleBlock
```
```
In lib/zstd/compress/zstd_compress_superblock.c (ffffffff81815b26)
Location: lib/zstd/compress/zstd_compress_internal.h:503
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff8184ca2b)
Location: lib/zstd/compress/zstd_compress_internal.h:503
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressSequences_internal
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressSequences_internal
  - lib/zstd/compress/zstd_compress.c:ZSTD_compress_frameChunk
  - lib/zstd/compress/zstd_compress.c:ZSTD_compress_frameChunk
  - lib/zstd/compress/zstd_compress.c:ZSTD_compress_frameChunk
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressSeqStore_singleBlock
```
```
In lib/zstd/compress/zstd_compress_superblock.c (ffffffff81856250)
Location: lib/zstd/compress/zstd_compress_internal.h:503
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff8189e5eb)
Location: lib/zstd/compress/zstd_compress_internal.h:503
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressSequences_internal
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressSequences_internal
  - lib/zstd/compress/zstd_compress.c:ZSTD_compress_frameChunk
  - lib/zstd/compress/zstd_compress.c:ZSTD_compress_frameChunk
  - lib/zstd/compress/zstd_compress.c:ZSTD_compress_frameChunk
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressSeqStore_singleBlock
```
```
In lib/zstd/compress/zstd_compress_superblock.c (ffffffff818a7e10)
Location: lib/zstd/compress/zstd_compress_internal.h:503
Inline: True
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
</ul>
