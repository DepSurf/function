# Function: <code>ZSTD_updateRep</code>

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
In lib/zstd/compress/zstd_compress.c (ffffffff8171264f)
Location: lib/zstd/compress/zstd_compress_internal.h:399
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_copySequencesToSeqStoreNoBlockDelim
  - lib/zstd/compress/zstd_compress.c:ZSTD_copySequencesToSeqStoreExplicitBlockDelim
  - lib/zstd/compress/zstd_compress.c:ZSTD_copyBlockSequences
```
```
In lib/zstd/compress/zstd_compress_superblock.c (ffffffff81720aa6)
Location: lib/zstd/compress/zstd_compress_internal.h:399
Inline: True
```
```
In lib/zstd/compress/zstd_opt.c (ffffffff81747b26)
Location: lib/zstd/compress/zstd_compress_internal.h:399
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_opt.c:ZSTD_compressBlock_opt_generic
  - lib/zstd/compress/zstd_opt.c:ZSTD_compressBlock_opt_generic
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
In lib/zstd/compress/zstd_compress.c (ffffffff8180515f)
Location: lib/zstd/compress/zstd_compress_internal.h:652
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_copySequencesToSeqStoreNoBlockDelim
  - lib/zstd/compress/zstd_compress.c:ZSTD_copySequencesToSeqStoreNoBlockDelim
  - lib/zstd/compress/zstd_compress.c:ZSTD_copySequencesToSeqStoreExplicitBlockDelim
  - lib/zstd/compress/zstd_compress.c:ZSTD_copySequencesToSeqStoreExplicitBlockDelim
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressSeqStore_singleBlock
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressSeqStore_singleBlock
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressSeqStore_singleBlock
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressSeqStore_singleBlock
  - lib/zstd/compress/zstd_compress.c:ZSTD_copyBlockSequences
  - lib/zstd/compress/zstd_compress.c:ZSTD_copyBlockSequences
```
```
In lib/zstd/compress/zstd_compress_superblock.c (ffffffff81815d59)
Location: lib/zstd/compress/zstd_compress_internal.h:652
Inline: True
```
```
In lib/zstd/compress/zstd_opt.c (ffffffff8185f0de)
Location: lib/zstd/compress/zstd_compress_internal.h:652
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_opt.c:ZSTD_compressBlock_opt2
  - lib/zstd/compress/zstd_opt.c:ZSTD_compressBlock_opt2
  - lib/zstd/compress/zstd_opt.c:ZSTD_compressBlock_opt0
  - lib/zstd/compress/zstd_opt.c:ZSTD_compressBlock_opt0
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
In lib/zstd/compress/zstd_compress.c (ffffffff81845b8a)
Location: lib/zstd/compress/zstd_compress_internal.h:652
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_copySequencesToSeqStoreNoBlockDelim
  - lib/zstd/compress/zstd_compress.c:ZSTD_copySequencesToSeqStoreNoBlockDelim
  - lib/zstd/compress/zstd_compress.c:ZSTD_copySequencesToSeqStoreExplicitBlockDelim
  - lib/zstd/compress/zstd_compress.c:ZSTD_copySequencesToSeqStoreExplicitBlockDelim
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressSeqStore_singleBlock
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressSeqStore_singleBlock
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressSeqStore_singleBlock
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressSeqStore_singleBlock
  - lib/zstd/compress/zstd_compress.c:ZSTD_copyBlockSequences
  - lib/zstd/compress/zstd_compress.c:ZSTD_copyBlockSequences
```
```
In lib/zstd/compress/zstd_compress_superblock.c (ffffffff8185647b)
Location: lib/zstd/compress/zstd_compress_internal.h:652
Inline: True
```
```
In lib/zstd/compress/zstd_opt.c (ffffffff8189fbfa)
Location: lib/zstd/compress/zstd_compress_internal.h:652
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_opt.c:ZSTD_compressBlock_opt2
  - lib/zstd/compress/zstd_opt.c:ZSTD_compressBlock_opt2
  - lib/zstd/compress/zstd_opt.c:ZSTD_compressBlock_opt0
  - lib/zstd/compress/zstd_opt.c:ZSTD_compressBlock_opt0
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
In lib/zstd/compress/zstd_compress.c (ffffffff8189774a)
Location: lib/zstd/compress/zstd_compress_internal.h:652
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_copySequencesToSeqStoreNoBlockDelim
  - lib/zstd/compress/zstd_compress.c:ZSTD_copySequencesToSeqStoreNoBlockDelim
  - lib/zstd/compress/zstd_compress.c:ZSTD_copySequencesToSeqStoreExplicitBlockDelim
  - lib/zstd/compress/zstd_compress.c:ZSTD_copySequencesToSeqStoreExplicitBlockDelim
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressSeqStore_singleBlock
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressSeqStore_singleBlock
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressSeqStore_singleBlock
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressSeqStore_singleBlock
  - lib/zstd/compress/zstd_compress.c:ZSTD_copyBlockSequences
  - lib/zstd/compress/zstd_compress.c:ZSTD_copyBlockSequences
```
```
In lib/zstd/compress/zstd_compress_superblock.c (ffffffff818a803b)
Location: lib/zstd/compress/zstd_compress_internal.h:652
Inline: True
```
```
In lib/zstd/compress/zstd_opt.c (ffffffff818f17ba)
Location: lib/zstd/compress/zstd_compress_internal.h:652
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_opt.c:ZSTD_compressBlock_opt2
  - lib/zstd/compress/zstd_opt.c:ZSTD_compressBlock_opt2
  - lib/zstd/compress/zstd_opt.c:ZSTD_compressBlock_opt0
  - lib/zstd/compress/zstd_opt.c:ZSTD_compressBlock_opt0
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
