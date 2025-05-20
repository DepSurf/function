# Function: <code>ZSTD_minGain</code>

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
In lib/zstd/compress.c (ffffffff815ca000)
Location: lib/zstd/compress.c:480
Inline: True
Inline callers:
  - lib/zstd/compress.c:ZSTD_compressBlock_internal
  - lib/zstd/compress.c:ZSTD_compressSequences_internal
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
In lib/zstd/compress.c (ffffffff815e7bd5)
Location: lib/zstd/compress.c:480
Inline: True
Inline callers:
  - lib/zstd/compress.c:ZSTD_compressBlock_internal
  - lib/zstd/compress.c:ZSTD_compressSequences_internal
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
In lib/zstd/compress/zstd_compress.c (ffffffff81718235)
Location: lib/zstd/compress/zstd_compress_internal.h:460
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressSequences_internal
  - lib/zstd/compress/zstd_compress.c:ZSTD_compress_frameChunk
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressBlock_internal
```
```
In lib/zstd/compress/zstd_compress_literals.c (ffffffff8171ca56)
Location: lib/zstd/compress/zstd_compress_internal.h:460
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress_literals.c:ZSTD_compressLiterals
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
In lib/zstd/compress/zstd_compress.c (ffffffff8180c000)
Location: lib/zstd/compress/zstd_compress_internal.h:528
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressSequences_internal
  - lib/zstd/compress/zstd_compress.c:ZSTD_compress_frameChunk
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressBlock_internal
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressSeqStore_singleBlock
```
```
In lib/zstd/compress/zstd_compress_literals.c (ffffffff81812387)
Location: lib/zstd/compress/zstd_compress_internal.h:528
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress_literals.c:ZSTD_compressLiterals
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
In lib/zstd/compress/zstd_compress.c (ffffffff8184caa5)
Location: lib/zstd/compress/zstd_compress_internal.h:528
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressSequences_internal
  - lib/zstd/compress/zstd_compress.c:ZSTD_compress_frameChunk
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressBlock_internal
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressSeqStore_singleBlock
```
```
In lib/zstd/compress/zstd_compress_literals.c (ffffffff81852e87)
Location: lib/zstd/compress/zstd_compress_internal.h:528
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress_literals.c:ZSTD_compressLiterals
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
In lib/zstd/compress/zstd_compress.c (ffffffff8189e665)
Location: lib/zstd/compress/zstd_compress_internal.h:528
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressSequences_internal
  - lib/zstd/compress/zstd_compress.c:ZSTD_compress_frameChunk
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressBlock_internal
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressSeqStore_singleBlock
```
```
In lib/zstd/compress/zstd_compress_literals.c (ffffffff818a4a47)
Location: lib/zstd/compress/zstd_compress_internal.h:528
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress_literals.c:ZSTD_compressLiterals
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
