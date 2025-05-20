# Function: <code>MEM_writeLE16</code>

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
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/huf_compress.c (ffffffff8170ffa0)
Location: lib/zstd/common/mem.h:151
Inline: True
Inline callers:
  - lib/zstd/compress/huf_compress.c:HUF_compress4X_usingCTable_internal
  - lib/zstd/compress/huf_compress.c:HUF_compress4X_usingCTable_internal
  - lib/zstd/compress/huf_compress.c:HUF_compress4X_usingCTable_internal
```
```
In lib/zstd/compress/zstd_compress.c (ffffffff817182c0)
Location: lib/zstd/common/mem.h:151
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressSequences_internal
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressSequences_internal
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressSequences_internal
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressSequences_internal
  - lib/zstd/compress/zstd_compress.c:ZSTD_writeLastEmptyBlock
  - lib/zstd/compress/zstd_compress.c:ZSTD_writeFrameHeader
  - lib/zstd/compress/zstd_compress.c:ZSTD_writeFrameHeader
  - lib/zstd/compress/zstd_compress.c:ZSTD_compress_frameChunk
  - lib/zstd/compress/zstd_compress.c:ZSTD_compress_frameChunk
  - lib/zstd/compress/zstd_compress.c:ZSTD_compress_frameChunk
  - lib/zstd/compress/zstd_compress.c:ZSTD_compress_frameChunk
```
```
In lib/zstd/compress/zstd_compress_literals.c (ffffffff8171ccbb)
Location: lib/zstd/common/mem.h:151
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress_literals.c:ZSTD_compressLiterals
  - lib/zstd/compress/zstd_compress_literals.c:ZSTD_compressRleLiteralsBlock
  - lib/zstd/compress/zstd_compress_literals.c:ZSTD_noCompressLiterals
```
```
In lib/zstd/compress/zstd_compress_superblock.c (ffffffff8171f94d)
Location: lib/zstd/common/mem.h:151
Inline: True
```
```
In lib/zstd/decompress/huf_decompress.c (ffffffff8174896b)
Location: lib/zstd/common/mem.h:151
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
In lib/zstd/compress/huf_compress.c (ffffffff81802678)
Location: lib/zstd/common/mem.h:153
Inline: True
Inline callers:
  - lib/zstd/compress/huf_compress.c:HUF_compress4X_usingCTable_internal
  - lib/zstd/compress/huf_compress.c:HUF_compress4X_usingCTable_internal
  - lib/zstd/compress/huf_compress.c:HUF_compress4X_usingCTable_internal
```
```
In lib/zstd/compress/zstd_compress.c (ffffffff8180c08b)
Location: lib/zstd/common/mem.h:153
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressSequences_internal
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressSequences_internal
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressSequences_internal
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressSequences_internal
  - lib/zstd/compress/zstd_compress.c:ZSTD_writeLastEmptyBlock
  - lib/zstd/compress/zstd_compress.c:ZSTD_writeFrameHeader
  - lib/zstd/compress/zstd_compress.c:ZSTD_writeFrameHeader
  - lib/zstd/compress/zstd_compress.c:ZSTD_compress_frameChunk
  - lib/zstd/compress/zstd_compress.c:ZSTD_compress_frameChunk
  - lib/zstd/compress/zstd_compress.c:ZSTD_compress_frameChunk
  - lib/zstd/compress/zstd_compress.c:ZSTD_compress_frameChunk
  - lib/zstd/compress/zstd_compress.c:ZSTD_compress_frameChunk
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressSeqStore_singleBlock
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressSeqStore_singleBlock
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressSeqStore_singleBlock
```
```
In lib/zstd/compress/zstd_compress_literals.c (ffffffff81812609)
Location: lib/zstd/common/mem.h:153
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress_literals.c:ZSTD_compressLiterals
  - lib/zstd/compress/zstd_compress_literals.c:ZSTD_compressRleLiteralsBlock
  - lib/zstd/compress/zstd_compress_literals.c:ZSTD_noCompressLiterals
```
```
In lib/zstd/compress/zstd_compress_superblock.c (ffffffff818152ad)
Location: lib/zstd/common/mem.h:153
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
In lib/zstd/compress/huf_compress.c (ffffffff81842f68)
Location: lib/zstd/common/mem.h:153
Inline: True
Inline callers:
  - lib/zstd/compress/huf_compress.c:HUF_compress4X_usingCTable_internal
  - lib/zstd/compress/huf_compress.c:HUF_compress4X_usingCTable_internal
  - lib/zstd/compress/huf_compress.c:HUF_compress4X_usingCTable_internal
```
```
In lib/zstd/compress/zstd_compress.c (ffffffff8184cb30)
Location: lib/zstd/common/mem.h:153
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressSequences_internal
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressSequences_internal
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressSequences_internal
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressSequences_internal
  - lib/zstd/compress/zstd_compress.c:ZSTD_writeLastEmptyBlock
  - lib/zstd/compress/zstd_compress.c:ZSTD_writeFrameHeader
  - lib/zstd/compress/zstd_compress.c:ZSTD_writeFrameHeader
  - lib/zstd/compress/zstd_compress.c:ZSTD_compress_frameChunk
  - lib/zstd/compress/zstd_compress.c:ZSTD_compress_frameChunk
  - lib/zstd/compress/zstd_compress.c:ZSTD_compress_frameChunk
  - lib/zstd/compress/zstd_compress.c:ZSTD_compress_frameChunk
  - lib/zstd/compress/zstd_compress.c:ZSTD_compress_frameChunk
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressSeqStore_singleBlock
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressSeqStore_singleBlock
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressSeqStore_singleBlock
```
```
In lib/zstd/compress/zstd_compress_literals.c (ffffffff81853109)
Location: lib/zstd/common/mem.h:153
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress_literals.c:ZSTD_compressLiterals
  - lib/zstd/compress/zstd_compress_literals.c:ZSTD_compressRleLiteralsBlock
  - lib/zstd/compress/zstd_compress_literals.c:ZSTD_noCompressLiterals
```
```
In lib/zstd/compress/zstd_compress_superblock.c (ffffffff81855afb)
Location: lib/zstd/common/mem.h:153
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
In lib/zstd/compress/huf_compress.c (ffffffff81894b28)
Location: lib/zstd/common/mem.h:153
Inline: True
Inline callers:
  - lib/zstd/compress/huf_compress.c:HUF_compress4X_usingCTable_internal
  - lib/zstd/compress/huf_compress.c:HUF_compress4X_usingCTable_internal
  - lib/zstd/compress/huf_compress.c:HUF_compress4X_usingCTable_internal
```
```
In lib/zstd/compress/zstd_compress.c (ffffffff8189e6f0)
Location: lib/zstd/common/mem.h:153
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressSequences_internal
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressSequences_internal
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressSequences_internal
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressSequences_internal
  - lib/zstd/compress/zstd_compress.c:ZSTD_writeLastEmptyBlock
  - lib/zstd/compress/zstd_compress.c:ZSTD_writeFrameHeader
  - lib/zstd/compress/zstd_compress.c:ZSTD_writeFrameHeader
  - lib/zstd/compress/zstd_compress.c:ZSTD_compress_frameChunk
  - lib/zstd/compress/zstd_compress.c:ZSTD_compress_frameChunk
  - lib/zstd/compress/zstd_compress.c:ZSTD_compress_frameChunk
  - lib/zstd/compress/zstd_compress.c:ZSTD_compress_frameChunk
  - lib/zstd/compress/zstd_compress.c:ZSTD_compress_frameChunk
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressSeqStore_singleBlock
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressSeqStore_singleBlock
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressSeqStore_singleBlock
```
```
In lib/zstd/compress/zstd_compress_literals.c (ffffffff818a4cc9)
Location: lib/zstd/common/mem.h:153
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress_literals.c:ZSTD_compressLiterals
  - lib/zstd/compress/zstd_compress_literals.c:ZSTD_compressRleLiteralsBlock
  - lib/zstd/compress/zstd_compress_literals.c:ZSTD_noCompressLiterals
```
```
In lib/zstd/compress/zstd_compress_superblock.c (ffffffff818a76bb)
Location: lib/zstd/common/mem.h:153
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
