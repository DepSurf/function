# Function: <code>MEM_writeLE32</code>

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
In lib/zstd/compress/fse_compress.c (0)
Location: lib/zstd/common/mem.h:172
Inline: True
```
```
In lib/zstd/compress/huf_compress.c (0)
Location: lib/zstd/common/mem.h:172
Inline: True
```
```
In lib/zstd/compress/zstd_compress.c (ffffffff8171c63b)
Location: lib/zstd/common/mem.h:172
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressSequences
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressSequences_internal
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressEnd
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressEnd
  - lib/zstd/compress/zstd_compress.c:ZSTD_writeSkippableFrame
  - lib/zstd/compress/zstd_compress.c:ZSTD_writeSkippableFrame
  - lib/zstd/compress/zstd_compress.c:ZSTD_writeFrameHeader
  - lib/zstd/compress/zstd_compress.c:ZSTD_writeFrameHeader
  - lib/zstd/compress/zstd_compress.c:ZSTD_writeFrameHeader
```
```
In lib/zstd/compress/zstd_compress_literals.c (ffffffff8171cd0e)
Location: lib/zstd/common/mem.h:172
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress_literals.c:ZSTD_compressLiterals
  - lib/zstd/compress/zstd_compress_literals.c:ZSTD_compressLiterals
  - lib/zstd/compress/zstd_compress_literals.c:ZSTD_compressRleLiteralsBlock
  - lib/zstd/compress/zstd_compress_literals.c:ZSTD_noCompressLiterals
```
```
In lib/zstd/compress/zstd_compress_sequences.c (0)
Location: lib/zstd/common/mem.h:172
Inline: True
```
```
In lib/zstd/compress/zstd_compress_superblock.c (ffffffff8171faa2)
Location: lib/zstd/common/mem.h:172
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
In lib/zstd/compress/fse_compress.c (0)
Location: lib/zstd/common/mem.h:174
Inline: True
```
```
In lib/zstd/compress/huf_compress.c (0)
Location: lib/zstd/common/mem.h:174
Inline: True
```
```
In lib/zstd/compress/zstd_compress.c (ffffffff81811eab)
Location: lib/zstd/common/mem.h:174
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressSequences
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressSequences_internal
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressEnd
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressEnd
  - lib/zstd/compress/zstd_compress.c:ZSTD_writeSkippableFrame
  - lib/zstd/compress/zstd_compress.c:ZSTD_writeSkippableFrame
  - lib/zstd/compress/zstd_compress.c:ZSTD_writeFrameHeader
  - lib/zstd/compress/zstd_compress.c:ZSTD_writeFrameHeader
  - lib/zstd/compress/zstd_compress.c:ZSTD_writeFrameHeader
```
```
In lib/zstd/compress/zstd_compress_literals.c (ffffffff8181261a)
Location: lib/zstd/common/mem.h:174
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress_literals.c:ZSTD_compressLiterals
  - lib/zstd/compress/zstd_compress_literals.c:ZSTD_compressLiterals
  - lib/zstd/compress/zstd_compress_literals.c:ZSTD_compressRleLiteralsBlock
  - lib/zstd/compress/zstd_compress_literals.c:ZSTD_noCompressLiterals
```
```
In lib/zstd/compress/zstd_compress_sequences.c (0)
Location: lib/zstd/common/mem.h:174
Inline: True
```
```
In lib/zstd/compress/zstd_compress_superblock.c (ffffffff81815402)
Location: lib/zstd/common/mem.h:174
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
In lib/zstd/compress/fse_compress.c (0)
Location: lib/zstd/common/mem.h:174
Inline: True
```
```
In lib/zstd/compress/huf_compress.c (0)
Location: lib/zstd/common/mem.h:174
Inline: True
```
```
In lib/zstd/compress/zstd_compress.c (ffffffff818529ab)
Location: lib/zstd/common/mem.h:174
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressSequences
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressSequences_internal
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressEnd
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressEnd
  - lib/zstd/compress/zstd_compress.c:ZSTD_writeSkippableFrame
  - lib/zstd/compress/zstd_compress.c:ZSTD_writeSkippableFrame
  - lib/zstd/compress/zstd_compress.c:ZSTD_writeFrameHeader
  - lib/zstd/compress/zstd_compress.c:ZSTD_writeFrameHeader
  - lib/zstd/compress/zstd_compress.c:ZSTD_writeFrameHeader
```
```
In lib/zstd/compress/zstd_compress_literals.c (ffffffff8185311a)
Location: lib/zstd/common/mem.h:174
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress_literals.c:ZSTD_compressLiterals
  - lib/zstd/compress/zstd_compress_literals.c:ZSTD_compressLiterals
  - lib/zstd/compress/zstd_compress_literals.c:ZSTD_compressRleLiteralsBlock
  - lib/zstd/compress/zstd_compress_literals.c:ZSTD_noCompressLiterals
```
```
In lib/zstd/compress/zstd_compress_sequences.c (0)
Location: lib/zstd/common/mem.h:174
Inline: True
```
```
In lib/zstd/compress/zstd_compress_superblock.c (ffffffff818559fb)
Location: lib/zstd/common/mem.h:174
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
In lib/zstd/compress/fse_compress.c (0)
Location: lib/zstd/common/mem.h:174
Inline: True
```
```
In lib/zstd/compress/huf_compress.c (0)
Location: lib/zstd/common/mem.h:174
Inline: True
```
```
In lib/zstd/compress/zstd_compress.c (ffffffff818a456b)
Location: lib/zstd/common/mem.h:174
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressSequences
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressSequences_internal
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressEnd
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressEnd
  - lib/zstd/compress/zstd_compress.c:ZSTD_writeSkippableFrame
  - lib/zstd/compress/zstd_compress.c:ZSTD_writeSkippableFrame
  - lib/zstd/compress/zstd_compress.c:ZSTD_writeFrameHeader
  - lib/zstd/compress/zstd_compress.c:ZSTD_writeFrameHeader
  - lib/zstd/compress/zstd_compress.c:ZSTD_writeFrameHeader
```
```
In lib/zstd/compress/zstd_compress_literals.c (ffffffff818a4cda)
Location: lib/zstd/common/mem.h:174
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress_literals.c:ZSTD_compressLiterals
  - lib/zstd/compress/zstd_compress_literals.c:ZSTD_compressLiterals
  - lib/zstd/compress/zstd_compress_literals.c:ZSTD_compressRleLiteralsBlock
  - lib/zstd/compress/zstd_compress_literals.c:ZSTD_noCompressLiterals
```
```
In lib/zstd/compress/zstd_compress_sequences.c (0)
Location: lib/zstd/common/mem.h:174
Inline: True
```
```
In lib/zstd/compress/zstd_compress_superblock.c (ffffffff818a75bb)
Location: lib/zstd/common/mem.h:174
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
