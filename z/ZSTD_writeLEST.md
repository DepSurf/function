# Function: <code>ZSTD_writeLEST</code>

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
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/zstd/fse_compress.c (ffffffff815abe4e)
Location: lib/zstd/mem.h:103
Inline: True
Inline callers:
  - lib/zstd/fse_compress.c:FSE_compress_usingCTable_generic
  - lib/zstd/fse_compress.c:FSE_compress_usingCTable_generic
  - lib/zstd/fse_compress.c:FSE_compress_usingCTable_generic
  - lib/zstd/fse_compress.c:FSE_compress_usingCTable_generic
  - lib/zstd/fse_compress.c:FSE_compress_usingCTable_generic
  - lib/zstd/fse_compress.c:FSE_compress_usingCTable_generic
  - lib/zstd/fse_compress.c:FSE_compress_usingCTable_generic
  - lib/zstd/fse_compress.c:FSE_compress_usingCTable_generic
  - lib/zstd/fse_compress.c:FSE_compress_usingCTable_generic
```
```
In lib/zstd/huf_compress.c (ffffffff815ad5a9)
Location: lib/zstd/mem.h:103
Inline: True
```
```
In lib/zstd/compress.c (ffffffff815c9430)
Location: lib/zstd/mem.h:103
Inline: True
Inline callers:
  - lib/zstd/compress.c:ZSTD_compressSequences_internal
  - lib/zstd/compress.c:ZSTD_compressSequences_internal
  - lib/zstd/compress.c:ZSTD_compressSequences_internal
  - lib/zstd/compress.c:ZSTD_compressSequences_internal
  - lib/zstd/compress.c:ZSTD_compressSequences_internal
  - lib/zstd/compress.c:ZSTD_compressSequences_internal
  - lib/zstd/compress.c:ZSTD_compressSequences_internal
  - lib/zstd/compress.c:ZSTD_compressSequences_internal
  - lib/zstd/compress.c:ZSTD_compressSequences_internal
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/zstd/fse_compress.c (ffffffff815c7955)
Location: lib/zstd/mem.h:103
Inline: True
Inline callers:
  - lib/zstd/fse_compress.c:FSE_compress_usingCTable_generic
  - lib/zstd/fse_compress.c:FSE_compress_usingCTable_generic
  - lib/zstd/fse_compress.c:FSE_compress_usingCTable_generic
  - lib/zstd/fse_compress.c:FSE_compress_usingCTable_generic
  - lib/zstd/fse_compress.c:FSE_compress_usingCTable_generic
  - lib/zstd/fse_compress.c:FSE_compress_usingCTable_generic
  - lib/zstd/fse_compress.c:FSE_compress_usingCTable_generic
  - lib/zstd/fse_compress.c:FSE_compress_usingCTable_generic
  - lib/zstd/fse_compress.c:FSE_compress_usingCTable_generic
```
```
In lib/zstd/huf_compress.c (ffffffff815c910e)
Location: lib/zstd/mem.h:103
Inline: True
```
```
In lib/zstd/compress.c (ffffffff815e6fa9)
Location: lib/zstd/mem.h:103
Inline: True
Inline callers:
  - lib/zstd/compress.c:ZSTD_compressSequences_internal
  - lib/zstd/compress.c:ZSTD_compressSequences_internal
  - lib/zstd/compress.c:ZSTD_compressSequences_internal
  - lib/zstd/compress.c:ZSTD_compressSequences_internal
  - lib/zstd/compress.c:ZSTD_compressSequences_internal
  - lib/zstd/compress.c:ZSTD_compressSequences_internal
  - lib/zstd/compress.c:ZSTD_compressSequences_internal
  - lib/zstd/compress.c:ZSTD_compressSequences_internal
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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
