# Function: <code>BIT_skipBits</code>

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
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/zstd/huf_decompress.c (ffffffff814ab985)
Location: lib/zstd/bitstream.h:308
Inline: True
Inline callers:
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
```
```
In lib/zstd/decompress.c (ffffffff814b3621)
Location: lib/zstd/bitstream.h:308
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
```
```
In lib/zstd/fse_decompress.c (ffffffff814b9a11)
Location: lib/zstd/bitstream.h:308
Inline: True
Inline callers:
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/zstd/huf_decompress.c (ffffffff814e0cc3)
Location: lib/zstd/bitstream.h:308
Inline: True
Inline callers:
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decodeLastSymbolX4
  - lib/zstd/huf_decompress.c:HUF_decodeLastSymbolX4
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
```
```
In lib/zstd/decompress.c (ffffffff814e7dcd)
Location: lib/zstd/bitstream.h:308
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
```
```
In lib/zstd/fse_decompress.c (ffffffff814ec37c)
Location: lib/zstd/bitstream.h:308
Inline: True
Inline callers:
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/zstd/huf_decompress.c (ffffffff814f461a)
Location: lib/zstd/bitstream.h:308
Inline: True
Inline callers:
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decodeLastSymbolX4
  - lib/zstd/huf_decompress.c:HUF_decodeLastSymbolX4
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
```
```
In lib/zstd/decompress.c (ffffffff814fbabd)
Location: lib/zstd/bitstream.h:308
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
```
```
In lib/zstd/fse_decompress.c (ffffffff815000f9)
Location: lib/zstd/bitstream.h:308
Inline: True
Inline callers:
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/zstd/huf_decompress.c (ffffffff815219ff)
Location: lib/zstd/bitstream.h:313
Inline: True
Inline callers:
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
```
```
In lib/zstd/decompress.c (ffffffff81529313)
Location: lib/zstd/bitstream.h:313
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
```
```
In lib/zstd/fse_decompress.c (ffffffff8152e314)
Location: lib/zstd/bitstream.h:313
Inline: True
Inline callers:
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/zstd/huf_decompress.c (ffffffff8154288f)
Location: lib/zstd/bitstream.h:313
Inline: True
Inline callers:
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
```
```
In lib/zstd/decompress.c (ffffffff8154a1a3)
Location: lib/zstd/bitstream.h:313
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
```
```
In lib/zstd/fse_decompress.c (ffffffff8154f1a4)
Location: lib/zstd/bitstream.h:313
Inline: True
Inline callers:
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/zstd/fse_decompress.c (ffffffff815cd113)
Location: lib/zstd/bitstream.h:313
Inline: True
Inline callers:
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
```
```
In lib/zstd/huf_decompress.c (ffffffff815ce289)
Location: lib/zstd/bitstream.h:313
Inline: True
Inline callers:
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
```
```
In lib/zstd/decompress.c (ffffffff815d5aa3)
Location: lib/zstd/bitstream.h:313
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
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
In lib/zstd/fse_decompress.c (ffffffff815eacb8)
Location: lib/zstd/bitstream.h:314
Inline: True
Inline callers:
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
```
```
In lib/zstd/huf_decompress.c (ffffffff815ebe5e)
Location: lib/zstd/bitstream.h:314
Inline: True
Inline callers:
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
```
```
In lib/zstd/decompress.c (ffffffff815f3785)
Location: lib/zstd/bitstream.h:314
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/zstd/huf_decompress.c (ffffffff815cd70d)
Location: lib/zstd/bitstream.h:314
Inline: True
Inline callers:
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
```
```
In lib/zstd/decompress.c (ffffffff815d4bae)
Location: lib/zstd/bitstream.h:314
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
```
```
In lib/zstd/fse_decompress.c (ffffffff815d8dc8)
Location: lib/zstd/bitstream.h:314
Inline: True
Inline callers:
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/zstd/huf_decompress.c (ffffffff81637d5d)
Location: lib/zstd/bitstream.h:314
Inline: True
Inline callers:
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
```
```
In lib/zstd/decompress.c (ffffffff8163f994)
Location: lib/zstd/bitstream.h:314
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
```
```
In lib/zstd/fse_decompress.c (ffffffff816440b8)
Location: lib/zstd/bitstream.h:314
Inline: True
Inline callers:
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/zstd/common/fse_decompress.c (ffffffff8170acba)
Location: lib/zstd/common/bitstream.h:354
Inline: True
Inline callers:
  - lib/zstd/common/fse_decompress.c:FSE_decompress_wksp_body_bmi2
  - lib/zstd/common/fse_decompress.c:FSE_decompress_wksp_body_bmi2
  - lib/zstd/common/fse_decompress.c:FSE_decompress_wksp_body_bmi2
  - lib/zstd/common/fse_decompress.c:FSE_decompress_wksp_body_bmi2
  - lib/zstd/common/fse_decompress.c:FSE_decompress_wksp_body_bmi2
  - lib/zstd/common/fse_decompress.c:FSE_decompress_wksp_body_bmi2
  - lib/zstd/common/fse_decompress.c:FSE_decompress_wksp_body_bmi2
  - lib/zstd/common/fse_decompress.c:FSE_decompress_wksp_body_bmi2
  - lib/zstd/common/fse_decompress.c:FSE_decompress_wksp_body_bmi2
  - lib/zstd/common/fse_decompress.c:FSE_decompress_wksp_body_bmi2
  - lib/zstd/common/fse_decompress.c:FSE_decompress_wksp_body_bmi2
  - lib/zstd/common/fse_decompress.c:FSE_decompress_wksp_body_bmi2
  - lib/zstd/common/fse_decompress.c:FSE_decompress_wksp_body_bmi2
  - lib/zstd/common/fse_decompress.c:FSE_decompress_wksp_body_default
  - lib/zstd/common/fse_decompress.c:FSE_decompress_wksp_body_default
  - lib/zstd/common/fse_decompress.c:FSE_decompress_wksp_body_default
  - lib/zstd/common/fse_decompress.c:FSE_decompress_wksp_body_default
  - lib/zstd/common/fse_decompress.c:FSE_decompress_wksp_body_default
  - lib/zstd/common/fse_decompress.c:FSE_decompress_wksp_body_default
  - lib/zstd/common/fse_decompress.c:FSE_decompress_wksp_body_default
  - lib/zstd/common/fse_decompress.c:FSE_decompress_wksp_body_default
  - lib/zstd/common/fse_decompress.c:FSE_decompress_wksp_body_default
  - lib/zstd/common/fse_decompress.c:FSE_decompress_wksp_body_default
  - lib/zstd/common/fse_decompress.c:FSE_decompress_wksp_body_default
  - lib/zstd/common/fse_decompress.c:FSE_decompress_wksp_body_default
  - lib/zstd/common/fse_decompress.c:FSE_decompress_wksp_body_default
  - lib/zstd/common/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/common/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/common/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/common/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/common/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/common/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/common/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/common/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/common/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/common/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/common/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/common/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/common/fse_decompress.c:FSE_decompress_usingDTable
```
```
In lib/zstd/decompress/huf_decompress.c (ffffffff8174d145)
Location: lib/zstd/common/bitstream.h:354
Inline: True
Inline callers:
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress1X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress1X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress1X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress1X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress1X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress1X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress1X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress1X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress1X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress1X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress1X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress1X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress1X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress1X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress1X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress1X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress1X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress1X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress1X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress1X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress1X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress1X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress1X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress1X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress1X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress1X1_usingDTable_internal_default
```
```
In lib/zstd/decompress/zstd_decompress_block.c (ffffffff81755d15)
Location: lib/zstd/common/bitstream.h:354
Inline: True
Inline callers:
  - lib/zstd/decompress/zstd_decompress_block.c:ZSTD_initFseState
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
In lib/zstd/decompress/huf_decompress.c (ffffffff8186ac94)
Location: lib/zstd/common/bitstream.h:363
Inline: True
Inline callers:
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress1X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress1X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress1X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress1X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress1X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress1X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress1X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress1X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress1X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress1X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress1X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress1X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress1X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress1X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress1X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress1X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress1X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress1X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress1X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress1X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress1X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress1X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress1X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress1X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress1X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress1X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress1X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress1X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress1X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress1X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress1X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress1X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress1X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress1X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress1X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress1X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
```
```
In lib/zstd/decompress/zstd_decompress_block.c (ffffffff8187a5c8)
Location: lib/zstd/common/bitstream.h:363
Inline: True
Inline callers:
  - lib/zstd/decompress/zstd_decompress_block.c:ZSTD_initFseState
```
```
In lib/zstd/common/fse_decompress.c (ffffffff8188587f)
Location: lib/zstd/common/bitstream.h:363
Inline: True
Inline callers:
  - lib/zstd/common/fse_decompress.c:FSE_decompress_wksp_body_bmi2
  - lib/zstd/common/fse_decompress.c:FSE_decompress_wksp_body_bmi2
  - lib/zstd/common/fse_decompress.c:FSE_decompress_wksp_body_bmi2
  - lib/zstd/common/fse_decompress.c:FSE_decompress_wksp_body_bmi2
  - lib/zstd/common/fse_decompress.c:FSE_decompress_wksp_body_bmi2
  - lib/zstd/common/fse_decompress.c:FSE_decompress_wksp_body_bmi2
  - lib/zstd/common/fse_decompress.c:FSE_decompress_wksp_body_bmi2
  - lib/zstd/common/fse_decompress.c:FSE_decompress_wksp_body_bmi2
  - lib/zstd/common/fse_decompress.c:FSE_decompress_wksp_body_bmi2
  - lib/zstd/common/fse_decompress.c:FSE_decompress_wksp_body_bmi2
  - lib/zstd/common/fse_decompress.c:FSE_decompress_wksp_body_bmi2
  - lib/zstd/common/fse_decompress.c:FSE_decompress_wksp_body_bmi2
  - lib/zstd/common/fse_decompress.c:FSE_decompress_wksp_body_bmi2
  - lib/zstd/common/fse_decompress.c:FSE_decompress_wksp_body_default
  - lib/zstd/common/fse_decompress.c:FSE_decompress_wksp_body_default
  - lib/zstd/common/fse_decompress.c:FSE_decompress_wksp_body_default
  - lib/zstd/common/fse_decompress.c:FSE_decompress_wksp_body_default
  - lib/zstd/common/fse_decompress.c:FSE_decompress_wksp_body_default
  - lib/zstd/common/fse_decompress.c:FSE_decompress_wksp_body_default
  - lib/zstd/common/fse_decompress.c:FSE_decompress_wksp_body_default
  - lib/zstd/common/fse_decompress.c:FSE_decompress_wksp_body_default
  - lib/zstd/common/fse_decompress.c:FSE_decompress_wksp_body_default
  - lib/zstd/common/fse_decompress.c:FSE_decompress_wksp_body_default
  - lib/zstd/common/fse_decompress.c:FSE_decompress_wksp_body_default
  - lib/zstd/common/fse_decompress.c:FSE_decompress_wksp_body_default
  - lib/zstd/common/fse_decompress.c:FSE_decompress_wksp_body_default
  - lib/zstd/common/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/common/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/common/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/common/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/common/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/common/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/common/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/common/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/common/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/common/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/common/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/common/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/common/fse_decompress.c:FSE_decompress_usingDTable
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
In lib/zstd/decompress/huf_decompress.c (ffffffff818ab984)
Location: lib/zstd/common/bitstream.h:363
Inline: True
Inline callers:
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress1X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress1X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress1X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress1X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress1X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress1X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress1X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress1X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress1X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress1X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress1X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress1X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress1X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress1X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress1X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress1X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress1X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress1X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress1X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress1X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress1X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress1X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress1X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress1X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress1X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress1X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress1X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress1X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress1X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress1X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress1X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress1X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress1X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress1X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress1X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress1X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
```
```
In lib/zstd/decompress/zstd_decompress_block.c (ffffffff818bb408)
Location: lib/zstd/common/bitstream.h:363
Inline: True
Inline callers:
  - lib/zstd/decompress/zstd_decompress_block.c:ZSTD_initFseState
```
```
In lib/zstd/common/fse_decompress.c (ffffffff818c7d44)
Location: lib/zstd/common/bitstream.h:363
Inline: True
Inline callers:
  - lib/zstd/common/fse_decompress.c:FSE_decompress_wksp_body_bmi2
  - lib/zstd/common/fse_decompress.c:FSE_decompress_wksp_body_bmi2
  - lib/zstd/common/fse_decompress.c:FSE_decompress_wksp_body_bmi2
  - lib/zstd/common/fse_decompress.c:FSE_decompress_wksp_body_bmi2
  - lib/zstd/common/fse_decompress.c:FSE_decompress_wksp_body_bmi2
  - lib/zstd/common/fse_decompress.c:FSE_decompress_wksp_body_bmi2
  - lib/zstd/common/fse_decompress.c:FSE_decompress_wksp_body_bmi2
  - lib/zstd/common/fse_decompress.c:FSE_decompress_wksp_body_bmi2
  - lib/zstd/common/fse_decompress.c:FSE_decompress_wksp_body_bmi2
  - lib/zstd/common/fse_decompress.c:FSE_decompress_wksp_body_bmi2
  - lib/zstd/common/fse_decompress.c:FSE_decompress_wksp_body_bmi2
  - lib/zstd/common/fse_decompress.c:FSE_decompress_wksp_body_bmi2
  - lib/zstd/common/fse_decompress.c:FSE_decompress_wksp_body_bmi2
  - lib/zstd/common/fse_decompress.c:FSE_decompress_wksp_body_default
  - lib/zstd/common/fse_decompress.c:FSE_decompress_wksp_body_default
  - lib/zstd/common/fse_decompress.c:FSE_decompress_wksp_body_default
  - lib/zstd/common/fse_decompress.c:FSE_decompress_wksp_body_default
  - lib/zstd/common/fse_decompress.c:FSE_decompress_wksp_body_default
  - lib/zstd/common/fse_decompress.c:FSE_decompress_wksp_body_default
  - lib/zstd/common/fse_decompress.c:FSE_decompress_wksp_body_default
  - lib/zstd/common/fse_decompress.c:FSE_decompress_wksp_body_default
  - lib/zstd/common/fse_decompress.c:FSE_decompress_wksp_body_default
  - lib/zstd/common/fse_decompress.c:FSE_decompress_wksp_body_default
  - lib/zstd/common/fse_decompress.c:FSE_decompress_wksp_body_default
  - lib/zstd/common/fse_decompress.c:FSE_decompress_wksp_body_default
  - lib/zstd/common/fse_decompress.c:FSE_decompress_wksp_body_default
  - lib/zstd/common/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/common/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/common/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/common/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/common/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/common/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/common/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/common/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/common/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/common/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/common/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/common/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/common/fse_decompress.c:FSE_decompress_usingDTable
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
In lib/zstd/decompress/huf_decompress.c (ffffffff818fd544)
Location: lib/zstd/common/bitstream.h:363
Inline: True
Inline callers:
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress1X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress1X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress1X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress1X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress1X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress1X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress1X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress1X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress1X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress1X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress1X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress1X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress1X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress1X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress1X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress1X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress1X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress1X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress1X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress1X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress1X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress1X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress1X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress1X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress1X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress1X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress1X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress1X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress1X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress1X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress1X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress1X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress1X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress1X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress1X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress1X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
```
```
In lib/zstd/decompress/zstd_decompress_block.c (ffffffff8190cfc8)
Location: lib/zstd/common/bitstream.h:363
Inline: True
Inline callers:
  - lib/zstd/decompress/zstd_decompress_block.c:ZSTD_initFseState
```
```
In lib/zstd/common/fse_decompress.c (ffffffff81919904)
Location: lib/zstd/common/bitstream.h:363
Inline: True
Inline callers:
  - lib/zstd/common/fse_decompress.c:FSE_decompress_wksp_body_bmi2
  - lib/zstd/common/fse_decompress.c:FSE_decompress_wksp_body_bmi2
  - lib/zstd/common/fse_decompress.c:FSE_decompress_wksp_body_bmi2
  - lib/zstd/common/fse_decompress.c:FSE_decompress_wksp_body_bmi2
  - lib/zstd/common/fse_decompress.c:FSE_decompress_wksp_body_bmi2
  - lib/zstd/common/fse_decompress.c:FSE_decompress_wksp_body_bmi2
  - lib/zstd/common/fse_decompress.c:FSE_decompress_wksp_body_bmi2
  - lib/zstd/common/fse_decompress.c:FSE_decompress_wksp_body_bmi2
  - lib/zstd/common/fse_decompress.c:FSE_decompress_wksp_body_bmi2
  - lib/zstd/common/fse_decompress.c:FSE_decompress_wksp_body_bmi2
  - lib/zstd/common/fse_decompress.c:FSE_decompress_wksp_body_bmi2
  - lib/zstd/common/fse_decompress.c:FSE_decompress_wksp_body_bmi2
  - lib/zstd/common/fse_decompress.c:FSE_decompress_wksp_body_bmi2
  - lib/zstd/common/fse_decompress.c:FSE_decompress_wksp_body_default
  - lib/zstd/common/fse_decompress.c:FSE_decompress_wksp_body_default
  - lib/zstd/common/fse_decompress.c:FSE_decompress_wksp_body_default
  - lib/zstd/common/fse_decompress.c:FSE_decompress_wksp_body_default
  - lib/zstd/common/fse_decompress.c:FSE_decompress_wksp_body_default
  - lib/zstd/common/fse_decompress.c:FSE_decompress_wksp_body_default
  - lib/zstd/common/fse_decompress.c:FSE_decompress_wksp_body_default
  - lib/zstd/common/fse_decompress.c:FSE_decompress_wksp_body_default
  - lib/zstd/common/fse_decompress.c:FSE_decompress_wksp_body_default
  - lib/zstd/common/fse_decompress.c:FSE_decompress_wksp_body_default
  - lib/zstd/common/fse_decompress.c:FSE_decompress_wksp_body_default
  - lib/zstd/common/fse_decompress.c:FSE_decompress_wksp_body_default
  - lib/zstd/common/fse_decompress.c:FSE_decompress_wksp_body_default
  - lib/zstd/common/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/common/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/common/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/common/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/common/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/common/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/common/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/common/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/common/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/common/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/common/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/common/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/common/fse_decompress.c:FSE_decompress_usingDTable
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/zstd/huf_decompress.c (ffff80001064f878)
Location: lib/zstd/bitstream.h:313
Inline: True
Inline callers:
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
```
```
In lib/zstd/decompress.c (ffff800010656274)
Location: lib/zstd/bitstream.h:313
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
```
```
In lib/zstd/fse_decompress.c (ffff80001065af24)
Location: lib/zstd/bitstream.h:313
Inline: True
Inline callers:
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/zstd/huf_decompress.c (c07fac40)
Location: lib/zstd/bitstream.h:313
Inline: True
Inline callers:
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
```
```
In lib/zstd/decompress.c (c080123c)
Location: lib/zstd/bitstream.h:313
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
```
```
In lib/zstd/fse_decompress.c (c0804554)
Location: lib/zstd/bitstream.h:313
Inline: True
Inline callers:
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/zstd/huf_decompress.c (c0000000007fdba8)
Location: lib/zstd/bitstream.h:313
Inline: True
Inline callers:
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decodeLastSymbolX4
  - lib/zstd/huf_decompress.c:HUF_decodeLastSymbolX4
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
```
```
In lib/zstd/decompress.c (c00000000080671c)
Location: lib/zstd/bitstream.h:313
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
```
```
In lib/zstd/fse_decompress.c (c00000000080c148)
Location: lib/zstd/bitstream.h:313
Inline: True
Inline callers:
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/zstd/huf_decompress.c (ffffffe00047bdde)
Location: lib/zstd/bitstream.h:313
Inline: True
Inline callers:
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
```
```
In lib/zstd/decompress.c (ffffffe000483e86)
Location: lib/zstd/bitstream.h:313
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
```
```
In lib/zstd/fse_decompress.c (ffffffe0004889da)
Location: lib/zstd/bitstream.h:313
Inline: True
Inline callers:
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/zstd/huf_decompress.c (ffffffff8153ae6f)
Location: lib/zstd/bitstream.h:313
Inline: True
Inline callers:
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
```
```
In lib/zstd/decompress.c (ffffffff81542783)
Location: lib/zstd/bitstream.h:313
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
```
```
In lib/zstd/fse_decompress.c (ffffffff81547784)
Location: lib/zstd/bitstream.h:313
Inline: True
Inline callers:
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/zstd/huf_decompress.c (ffffffff8152b14f)
Location: lib/zstd/bitstream.h:313
Inline: True
Inline callers:
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
```
```
In lib/zstd/decompress.c (ffffffff81532a63)
Location: lib/zstd/bitstream.h:313
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
```
```
In lib/zstd/fse_decompress.c (ffffffff81537a64)
Location: lib/zstd/bitstream.h:313
Inline: True
Inline callers:
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/zstd/huf_decompress.c (ffffffff81536baf)
Location: lib/zstd/bitstream.h:313
Inline: True
Inline callers:
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
```
```
In lib/zstd/decompress.c (ffffffff8153e4c3)
Location: lib/zstd/bitstream.h:313
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
```
```
In lib/zstd/fse_decompress.c (ffffffff815434c4)
Location: lib/zstd/bitstream.h:313
Inline: True
Inline callers:
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/zstd/huf_decompress.c (ffffffff815509df)
Location: lib/zstd/bitstream.h:313
Inline: True
Inline callers:
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
```
```
In lib/zstd/decompress.c (ffffffff815582f3)
Location: lib/zstd/bitstream.h:313
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decodeSequenceLong
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
```
```
In lib/zstd/fse_decompress.c (ffffffff8155d2f4)
Location: lib/zstd/bitstream.h:313
Inline: True
Inline callers:
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
```
</details>
</li>
</ul>

## Differences
