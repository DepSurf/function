# Function: <code>BIT_addBitsFast</code>

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
In lib/zstd/fse_compress.c (ffffffff815ac183)
Location: lib/zstd/bitstream.h:185
Inline: True
Inline callers:
  - lib/zstd/fse_compress.c:FSE_compress_usingCTable_generic
```
```
In lib/zstd/huf_compress.c (ffffffff815ad53f)
Location: lib/zstd/bitstream.h:185
Inline: True
```
```
In lib/zstd/compress.c (ffffffff815c9a20)
Location: lib/zstd/bitstream.h:185
Inline: True
Inline callers:
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
In lib/zstd/fse_compress.c (ffffffff815c7c78)
Location: lib/zstd/bitstream.h:185
Inline: True
Inline callers:
  - lib/zstd/fse_compress.c:FSE_compress_usingCTable_generic
```
```
In lib/zstd/huf_compress.c (ffffffff815c90a4)
Location: lib/zstd/bitstream.h:185
Inline: True
```
```
In lib/zstd/compress.c (ffffffff815e75e3)
Location: lib/zstd/bitstream.h:185
Inline: True
Inline callers:
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
In lib/zstd/compress/fse_compress.c (ffffffff81e966eb)
Location: lib/zstd/common/bitstream.h:197
Inline: True
Inline callers:
  - lib/zstd/compress/fse_compress.c:FSE_compress_usingCTable_generic
```
```
In lib/zstd/compress/huf_compress.c (ffffffff8170fa68)
Location: lib/zstd/common/bitstream.h:197
Inline: True
Inline callers:
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2
```
```
In lib/zstd/compress/zstd_compress_sequences.c (ffffffff81e97d4c)
Location: lib/zstd/common/bitstream.h:197
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress_sequences.c:ZSTD_encodeSequences_bmi2
  - lib/zstd/compress/zstd_compress_sequences.c:ZSTD_encodeSequences_default
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
In lib/zstd/compress/fse_compress.c (ffffffff8207b419)
Location: lib/zstd/common/bitstream.h:197
Inline: True
Inline callers:
  - lib/zstd/compress/fse_compress.c:FSE_compress_usingCTable_generic
```
```
In lib/zstd/compress/zstd_compress_sequences.c (ffffffff8207e62b)
Location: lib/zstd/common/bitstream.h:197
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress_sequences.c:ZSTD_encodeSequences_bmi2
  - lib/zstd/compress/zstd_compress_sequences.c:ZSTD_encodeSequences_default
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
In lib/zstd/compress/fse_compress.c (ffffffff820fba0f)
Location: lib/zstd/common/bitstream.h:197
Inline: True
Inline callers:
  - lib/zstd/compress/fse_compress.c:FSE_compress_usingCTable_generic
```
```
In lib/zstd/compress/zstd_compress_sequences.c (ffffffff820fec61)
Location: lib/zstd/common/bitstream.h:197
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress_sequences.c:ZSTD_encodeSequences_bmi2
  - lib/zstd/compress/zstd_compress_sequences.c:ZSTD_encodeSequences_default
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
In lib/zstd/compress/fse_compress.c (ffffffff821d9b7c)
Location: lib/zstd/common/bitstream.h:197
Inline: True
Inline callers:
  - lib/zstd/compress/fse_compress.c:FSE_compress_usingCTable_generic
```
```
In lib/zstd/compress/zstd_compress_sequences.c (ffffffff821dcdce)
Location: lib/zstd/common/bitstream.h:197
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress_sequences.c:ZSTD_encodeSequences_bmi2
  - lib/zstd/compress/zstd_compress_sequences.c:ZSTD_encodeSequences_default
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
