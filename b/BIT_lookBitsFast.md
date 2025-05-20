# Function: <code>BIT_lookBitsFast</code>

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
In lib/zstd/huf_decompress.c (ffffffff814ab907)
Location: lib/zstd/bitstream.h:302
Inline: True
Inline callers:
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
In lib/zstd/decompress.c (ffffffff814b3647)
Location: lib/zstd/bitstream.h:302
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
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
```
```
In lib/zstd/fse_decompress.c (ffffffff814b9b1e)
Location: lib/zstd/bitstream.h:302
Inline: True
Inline callers:
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
In lib/zstd/huf_decompress.c (ffffffff814e0cb0)
Location: lib/zstd/bitstream.h:302
Inline: True
Inline callers:
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decodeLastSymbolX4
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
```
```
In lib/zstd/decompress.c (ffffffff814e6cad)
Location: lib/zstd/bitstream.h:302
Inline: True
Inline callers:
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
```
```
In lib/zstd/fse_decompress.c (ffffffff814ec498)
Location: lib/zstd/bitstream.h:302
Inline: True
Inline callers:
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
In lib/zstd/huf_decompress.c (ffffffff814f4607)
Location: lib/zstd/bitstream.h:302
Inline: True
Inline callers:
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decodeLastSymbolX4
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
```
```
In lib/zstd/decompress.c (ffffffff814fa99d)
Location: lib/zstd/bitstream.h:302
Inline: True
Inline callers:
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
```
```
In lib/zstd/fse_decompress.c (ffffffff81500215)
Location: lib/zstd/bitstream.h:302
Inline: True
Inline callers:
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
In lib/zstd/huf_decompress.c (ffffffff815219e6)
Location: lib/zstd/bitstream.h:307
Inline: True
Inline callers:
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
In lib/zstd/decompress.c (ffffffff81528258)
Location: lib/zstd/bitstream.h:307
Inline: True
Inline callers:
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
```
```
In lib/zstd/fse_decompress.c (ffffffff8152e432)
Location: lib/zstd/bitstream.h:307
Inline: True
Inline callers:
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
In lib/zstd/huf_decompress.c (ffffffff81542876)
Location: lib/zstd/bitstream.h:307
Inline: True
Inline callers:
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
In lib/zstd/decompress.c (ffffffff815490e8)
Location: lib/zstd/bitstream.h:307
Inline: True
Inline callers:
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
```
```
In lib/zstd/fse_decompress.c (ffffffff8154f2c2)
Location: lib/zstd/bitstream.h:307
Inline: True
Inline callers:
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
In lib/zstd/fse_decompress.c (ffffffff815cd238)
Location: lib/zstd/bitstream.h:307
Inline: True
Inline callers:
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
```
```
In lib/zstd/huf_decompress.c (ffffffff815ce270)
Location: lib/zstd/bitstream.h:307
Inline: True
Inline callers:
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
In lib/zstd/decompress.c (ffffffff815d49f5)
Location: lib/zstd/bitstream.h:307
Inline: True
Inline callers:
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
In lib/zstd/fse_decompress.c (ffffffff815eaddd)
Location: lib/zstd/bitstream.h:308
Inline: True
Inline callers:
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
```
```
In lib/zstd/huf_decompress.c (ffffffff815ebe45)
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
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
```
```
In lib/zstd/decompress.c (ffffffff815f26b9)
Location: lib/zstd/bitstream.h:308
Inline: True
Inline callers:
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
In lib/zstd/huf_decompress.c (ffffffff815cd6f4)
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
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
```
```
In lib/zstd/decompress.c (ffffffff815d5041)
Location: lib/zstd/bitstream.h:308
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
```
```
In lib/zstd/fse_decompress.c (ffffffff815d8ef4)
Location: lib/zstd/bitstream.h:308
Inline: True
Inline callers:
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
In lib/zstd/huf_decompress.c (ffffffff81637d44)
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
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
```
```
In lib/zstd/decompress.c (ffffffff8163fe3c)
Location: lib/zstd/bitstream.h:308
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
```
```
In lib/zstd/fse_decompress.c (ffffffff816441e4)
Location: lib/zstd/bitstream.h:308
Inline: True
Inline callers:
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
In lib/zstd/common/fse_decompress.c (ffffffff8170ade9)
Location: lib/zstd/common/bitstream.h:347
Inline: True
Inline callers:
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
  - lib/zstd/common/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/common/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/common/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/common/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/common/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/common/fse_decompress.c:FSE_decompress_usingDTable
```
```
In lib/zstd/decompress/huf_decompress.c (ffffffff8174d11c)
Location: lib/zstd/common/bitstream.h:347
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
In lib/zstd/decompress/zstd_decompress_block.c (ffffffff81755f64)
Location: lib/zstd/common/bitstream.h:347
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
In lib/zstd/decompress/huf_decompress.c (ffffffff8186ac7e)
Location: lib/zstd/common/bitstream.h:356
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
In lib/zstd/decompress/zstd_decompress_block.c (ffffffff8187a9a6)
Location: lib/zstd/common/bitstream.h:356
Inline: True
```
```
In lib/zstd/common/fse_decompress.c (ffffffff818859b7)
Location: lib/zstd/common/bitstream.h:356
Inline: True
Inline callers:
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
In lib/zstd/decompress/huf_decompress.c (ffffffff818ab96e)
Location: lib/zstd/common/bitstream.h:356
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
In lib/zstd/decompress/zstd_decompress_block.c (ffffffff818bb7e3)
Location: lib/zstd/common/bitstream.h:356
Inline: True
```
```
In lib/zstd/common/fse_decompress.c (ffffffff818c7e6d)
Location: lib/zstd/common/bitstream.h:356
Inline: True
Inline callers:
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
In lib/zstd/decompress/huf_decompress.c (ffffffff818fd52e)
Location: lib/zstd/common/bitstream.h:356
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
In lib/zstd/decompress/zstd_decompress_block.c (ffffffff8190d3a3)
Location: lib/zstd/common/bitstream.h:356
Inline: True
```
```
In lib/zstd/common/fse_decompress.c (ffffffff81919a2d)
Location: lib/zstd/common/bitstream.h:356
Inline: True
Inline callers:
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
In lib/zstd/huf_decompress.c (ffff80001064f860)
Location: lib/zstd/bitstream.h:307
Inline: True
Inline callers:
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
In lib/zstd/decompress.c (ffff8000106554a4)
Location: lib/zstd/bitstream.h:307
Inline: True
Inline callers:
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
```
```
In lib/zstd/fse_decompress.c (ffff80001065b2f4)
Location: lib/zstd/bitstream.h:307
Inline: True
Inline callers:
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
In lib/zstd/huf_decompress.c (c07fac28)
Location: lib/zstd/bitstream.h:307
Inline: True
Inline callers:
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
Location: lib/zstd/bitstream.h:307
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
```
```
In lib/zstd/fse_decompress.c (c0804a00)
Location: lib/zstd/bitstream.h:307
Inline: True
Inline callers:
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
In lib/zstd/huf_decompress.c (c0000000007fdb8c)
Location: lib/zstd/bitstream.h:307
Inline: True
Inline callers:
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decodeLastSymbolX4
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
```
```
In lib/zstd/decompress.c (c000000000805508)
Location: lib/zstd/bitstream.h:307
Inline: True
Inline callers:
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
```
```
In lib/zstd/fse_decompress.c (c00000000080c560)
Location: lib/zstd/bitstream.h:307
Inline: True
Inline callers:
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
In lib/zstd/huf_decompress.c (ffffffe00047bd02)
Location: lib/zstd/bitstream.h:307
Inline: True
Inline callers:
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
In lib/zstd/decompress.c (ffffffe000482d10)
Location: lib/zstd/bitstream.h:307
Inline: True
Inline callers:
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
```
```
In lib/zstd/fse_decompress.c (ffffffe000489012)
Location: lib/zstd/bitstream.h:307
Inline: True
Inline callers:
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
In lib/zstd/huf_decompress.c (ffffffff8153ae56)
Location: lib/zstd/bitstream.h:307
Inline: True
Inline callers:
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
In lib/zstd/decompress.c (ffffffff815416c8)
Location: lib/zstd/bitstream.h:307
Inline: True
Inline callers:
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
```
```
In lib/zstd/fse_decompress.c (ffffffff815478a2)
Location: lib/zstd/bitstream.h:307
Inline: True
Inline callers:
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
In lib/zstd/huf_decompress.c (ffffffff8152b136)
Location: lib/zstd/bitstream.h:307
Inline: True
Inline callers:
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
In lib/zstd/decompress.c (ffffffff815319a8)
Location: lib/zstd/bitstream.h:307
Inline: True
Inline callers:
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
```
```
In lib/zstd/fse_decompress.c (ffffffff81537b82)
Location: lib/zstd/bitstream.h:307
Inline: True
Inline callers:
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
In lib/zstd/huf_decompress.c (ffffffff81536b96)
Location: lib/zstd/bitstream.h:307
Inline: True
Inline callers:
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
In lib/zstd/decompress.c (ffffffff8153d408)
Location: lib/zstd/bitstream.h:307
Inline: True
Inline callers:
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
```
```
In lib/zstd/fse_decompress.c (ffffffff815435e2)
Location: lib/zstd/bitstream.h:307
Inline: True
Inline callers:
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
In lib/zstd/huf_decompress.c (ffffffff815509c6)
Location: lib/zstd/bitstream.h:307
Inline: True
Inline callers:
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
In lib/zstd/decompress.c (ffffffff81557238)
Location: lib/zstd/bitstream.h:307
Inline: True
Inline callers:
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
```
```
In lib/zstd/fse_decompress.c (ffffffff8155d412)
Location: lib/zstd/bitstream.h:307
Inline: True
Inline callers:
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
