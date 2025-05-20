# Function: <code>BIT_highbit32</code>

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
In lib/zstd/huf_decompress.c (ffffffff814ab8e7)
Location: lib/zstd/bitstream.h:148
Inline: True
Inline callers:
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
```
```
In lib/zstd/decompress.c (ffffffff814b2a95)
Location: lib/zstd/bitstream.h:148
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
```
```
In lib/zstd/entropy_common.c (ffffffff814b94b1)
Location: lib/zstd/bitstream.h:148
Inline: True
Inline callers:
  - lib/zstd/entropy_common.c:HUF_readStats_wksp
  - lib/zstd/entropy_common.c:HUF_readStats_wksp
```
```
In lib/zstd/fse_decompress.c (ffffffff814b99e6)
Location: lib/zstd/bitstream.h:148
Inline: True
Inline callers:
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_buildDTable_wksp
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
In lib/zstd/huf_decompress.c (ffffffff814e0b6a)
Location: lib/zstd/bitstream.h:148
Inline: True
Inline callers:
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
```
```
In lib/zstd/decompress.c (ffffffff814e7da5)
Location: lib/zstd/bitstream.h:148
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
```
```
In lib/zstd/entropy_common.c (ffffffff814ebca6)
Location: lib/zstd/bitstream.h:148
Inline: True
Inline callers:
  - lib/zstd/entropy_common.c:HUF_readStats_wksp
  - lib/zstd/entropy_common.c:HUF_readStats_wksp
```
```
In lib/zstd/fse_decompress.c (ffffffff814ec33f)
Location: lib/zstd/bitstream.h:148
Inline: True
Inline callers:
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_buildDTable_wksp
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
In lib/zstd/huf_decompress.c (ffffffff814f4501)
Location: lib/zstd/bitstream.h:148
Inline: True
Inline callers:
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
```
```
In lib/zstd/decompress.c (ffffffff814fba95)
Location: lib/zstd/bitstream.h:148
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
```
```
In lib/zstd/entropy_common.c (ffffffff814ff9f6)
Location: lib/zstd/bitstream.h:148
Inline: True
Inline callers:
  - lib/zstd/entropy_common.c:HUF_readStats_wksp
  - lib/zstd/entropy_common.c:HUF_readStats_wksp
```
```
In lib/zstd/fse_decompress.c (ffffffff815000bc)
Location: lib/zstd/bitstream.h:148
Inline: True
Inline callers:
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_buildDTable_wksp
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
In lib/zstd/huf_decompress.c (ffffffff81521954)
Location: lib/zstd/bitstream.h:148
Inline: True
Inline callers:
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
```
```
In lib/zstd/decompress.c (ffffffff815292df)
Location: lib/zstd/bitstream.h:148
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
```
```
In lib/zstd/entropy_common.c (ffffffff8152dc1e)
Location: lib/zstd/bitstream.h:148
Inline: True
Inline callers:
  - lib/zstd/entropy_common.c:HUF_readStats_wksp
  - lib/zstd/entropy_common.c:HUF_readStats_wksp
```
```
In lib/zstd/fse_decompress.c (ffffffff8152e2a7)
Location: lib/zstd/bitstream.h:148
Inline: True
Inline callers:
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_buildDTable_wksp
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
In lib/zstd/huf_decompress.c (ffffffff815427e4)
Location: lib/zstd/bitstream.h:148
Inline: True
Inline callers:
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
```
```
In lib/zstd/decompress.c (ffffffff8154a16f)
Location: lib/zstd/bitstream.h:148
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
```
```
In lib/zstd/entropy_common.c (ffffffff8154eaae)
Location: lib/zstd/bitstream.h:148
Inline: True
Inline callers:
  - lib/zstd/entropy_common.c:HUF_readStats_wksp
  - lib/zstd/entropy_common.c:HUF_readStats_wksp
```
```
In lib/zstd/fse_decompress.c (ffffffff8154f137)
Location: lib/zstd/bitstream.h:148
Inline: True
Inline callers:
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_buildDTable_wksp
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
In lib/zstd/fse_compress.c (ffffffff815acade)
Location: lib/zstd/bitstream.h:148
Inline: True
Inline callers:
  - lib/zstd/fse_compress.c:FSE_normalizeCount
  - lib/zstd/fse_compress.c:FSE_normalizeCount
  - lib/zstd/fse_compress.c:FSE_optimalTableLog
  - lib/zstd/fse_compress.c:FSE_optimalTableLog
  - lib/zstd/fse_compress.c:FSE_buildCTable_wksp
```
```
In lib/zstd/huf_compress.c (ffffffff815acf72)
Location: lib/zstd/bitstream.h:148
Inline: True
Inline callers:
  - lib/zstd/huf_compress.c:HUF_sort
  - lib/zstd/huf_compress.c:HUF_sort
  - lib/zstd/huf_compress.c:HUF_setMaxHeight
```
```
In lib/zstd/entropy_common.c (ffffffff815cca17)
Location: lib/zstd/bitstream.h:148
Inline: True
Inline callers:
  - lib/zstd/entropy_common.c:HUF_readStats_wksp
  - lib/zstd/entropy_common.c:HUF_readStats_wksp
```
```
In lib/zstd/fse_decompress.c (ffffffff815cd0d4)
Location: lib/zstd/bitstream.h:148
Inline: True
Inline callers:
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_buildDTable_wksp
```
```
In lib/zstd/huf_decompress.c (ffffffff815ce23d)
Location: lib/zstd/bitstream.h:148
Inline: True
Inline callers:
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
```
```
In lib/zstd/decompress.c (ffffffff815d5dc2)
Location: lib/zstd/bitstream.h:148
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
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
In lib/zstd/fse_compress.c (ffffffff815c8623)
Location: lib/zstd/bitstream.h:148
Inline: True
Inline callers:
  - lib/zstd/fse_compress.c:FSE_normalizeCount
  - lib/zstd/fse_compress.c:FSE_normalizeCount
  - lib/zstd/fse_compress.c:FSE_optimalTableLog
  - lib/zstd/fse_compress.c:FSE_optimalTableLog
  - lib/zstd/fse_compress.c:FSE_buildCTable_wksp
```
```
In lib/zstd/huf_compress.c (ffffffff815c8ad7)
Location: lib/zstd/bitstream.h:148
Inline: True
Inline callers:
  - lib/zstd/huf_compress.c:HUF_sort
  - lib/zstd/huf_compress.c:HUF_sort
  - lib/zstd/huf_compress.c:HUF_setMaxHeight
```
```
In lib/zstd/entropy_common.c (ffffffff815ea59c)
Location: lib/zstd/bitstream.h:148
Inline: True
Inline callers:
  - lib/zstd/entropy_common.c:HUF_readStats_wksp
  - lib/zstd/entropy_common.c:HUF_readStats_wksp
```
```
In lib/zstd/fse_decompress.c (ffffffff815eac79)
Location: lib/zstd/bitstream.h:148
Inline: True
Inline callers:
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_buildDTable_wksp
```
```
In lib/zstd/huf_decompress.c (ffffffff815ebe12)
Location: lib/zstd/bitstream.h:148
Inline: True
Inline callers:
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
```
```
In lib/zstd/decompress.c (ffffffff815f3aa4)
Location: lib/zstd/bitstream.h:148
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
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
In lib/zstd/huf_decompress.c (ffffffff815cd7e0)
Location: lib/zstd/bitstream.h:148
Inline: True
Inline callers:
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
```
```
In lib/zstd/decompress.c (ffffffff815d5174)
Location: lib/zstd/bitstream.h:148
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
```
```
In lib/zstd/entropy_common.c (ffffffff815d86a7)
Location: lib/zstd/bitstream.h:148
Inline: True
Inline callers:
  - lib/zstd/entropy_common.c:HUF_readStats_wksp
  - lib/zstd/entropy_common.c:HUF_readStats_wksp
```
```
In lib/zstd/fse_decompress.c (ffffffff815d8d8e)
Location: lib/zstd/bitstream.h:148
Inline: True
Inline callers:
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_buildDTable_wksp
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
In lib/zstd/huf_decompress.c (ffffffff81637e30)
Location: lib/zstd/bitstream.h:148
Inline: True
Inline callers:
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
```
```
In lib/zstd/decompress.c (ffffffff8163fec1)
Location: lib/zstd/bitstream.h:148
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
```
```
In lib/zstd/entropy_common.c (ffffffff81643959)
Location: lib/zstd/bitstream.h:148
Inline: True
Inline callers:
  - lib/zstd/entropy_common.c:HUF_readStats_wksp
  - lib/zstd/entropy_common.c:HUF_readStats_wksp
```
```
In lib/zstd/fse_decompress.c (ffffffff8164407e)
Location: lib/zstd/bitstream.h:148
Inline: True
Inline callers:
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_buildDTable_wksp
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
In lib/zstd/common/entropy_common.c (ffffffff817096c6)
Location: lib/zstd/common/bitstream.h:130
Inline: True
Inline callers:
  - lib/zstd/common/entropy_common.c:HUF_readStats_body_bmi2
  - lib/zstd/common/entropy_common.c:HUF_readStats_body_bmi2
  - lib/zstd/common/entropy_common.c:HUF_readStats_body_default
  - lib/zstd/common/entropy_common.c:HUF_readStats_body_default
  - lib/zstd/common/entropy_common.c:FSE_readNCount_body_bmi2
  - lib/zstd/common/entropy_common.c:FSE_readNCount_body_default
```
```
In lib/zstd/common/fse_decompress.c (ffffffff8170a35a)
Location: lib/zstd/common/bitstream.h:130
Inline: True
Inline callers:
  - lib/zstd/common/fse_decompress.c:FSE_buildDTable_internal
  - lib/zstd/common/fse_decompress.c:BIT_initDStream
  - lib/zstd/common/fse_decompress.c:BIT_initDStream
```
```
In lib/zstd/compress/fse_compress.c (ffffffff8170ea9e)
Location: lib/zstd/common/bitstream.h:130
Inline: True
Inline callers:
  - lib/zstd/compress/fse_compress.c:FSE_normalizeCount
  - lib/zstd/compress/fse_compress.c:FSE_normalizeCount
  - lib/zstd/compress/fse_compress.c:FSE_optimalTableLog
  - lib/zstd/compress/fse_compress.c:FSE_optimalTableLog
  - lib/zstd/compress/fse_compress.c:FSE_optimalTableLog
  - lib/zstd/compress/fse_compress.c:FSE_buildCTable_wksp
```
```
In lib/zstd/compress/huf_compress.c (ffffffff81710c52)
Location: lib/zstd/common/bitstream.h:130
Inline: True
Inline callers:
  - lib/zstd/compress/huf_compress.c:HUF_buildCTable_wksp
  - lib/zstd/compress/huf_compress.c:HUF_buildCTable_wksp
  - lib/zstd/compress/huf_compress.c:HUF_setMaxHeight
```
```
In lib/zstd/decompress/huf_decompress.c (ffffffff8174871f)
Location: lib/zstd/common/bitstream.h:130
Inline: True
Inline callers:
  - lib/zstd/decompress/huf_decompress.c:BIT_initDStream
  - lib/zstd/decompress/huf_decompress.c:BIT_initDStream
```
```
In lib/zstd/decompress/zstd_decompress_block.c (ffffffff81754fff)
Location: lib/zstd/common/bitstream.h:130
Inline: True
Inline callers:
  - lib/zstd/decompress/zstd_decompress_block.c:BIT_initDStream
  - lib/zstd/decompress/zstd_decompress_block.c:BIT_initDStream
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
In lib/zstd/compress/fse_compress.c (ffffffff817fdafe)
Location: lib/zstd/common/bitstream.h:130
Inline: True
Inline callers:
  - lib/zstd/compress/fse_compress.c:FSE_normalizeCount
  - lib/zstd/compress/fse_compress.c:FSE_normalizeCount
  - lib/zstd/compress/fse_compress.c:FSE_optimalTableLog
  - lib/zstd/compress/fse_compress.c:FSE_optimalTableLog
  - lib/zstd/compress/fse_compress.c:FSE_optimalTableLog
  - lib/zstd/compress/fse_compress.c:FSE_buildCTable_wksp
```
```
In lib/zstd/compress/huf_compress.c (ffffffff818034ad)
Location: lib/zstd/common/bitstream.h:130
Inline: True
Inline callers:
  - lib/zstd/compress/huf_compress.c:HUF_buildCTable_wksp
  - lib/zstd/compress/huf_compress.c:HUF_buildCTable_wksp
  - lib/zstd/compress/huf_compress.c:HUF_setMaxHeight
```
```
In lib/zstd/decompress/huf_decompress.c (ffffffff8186a47f)
Location: lib/zstd/common/bitstream.h:130
Inline: True
Inline callers:
  - lib/zstd/decompress/huf_decompress.c:BIT_initDStream
  - lib/zstd/decompress/huf_decompress.c:BIT_initDStream
```
```
In lib/zstd/decompress/zstd_decompress_block.c (ffffffff81879c1f)
Location: lib/zstd/common/bitstream.h:130
Inline: True
Inline callers:
  - lib/zstd/decompress/zstd_decompress_block.c:BIT_initDStream
  - lib/zstd/decompress/zstd_decompress_block.c:BIT_initDStream
```
```
In lib/zstd/common/entropy_common.c (ffffffff81884176)
Location: lib/zstd/common/bitstream.h:130
Inline: True
Inline callers:
  - lib/zstd/common/entropy_common.c:HUF_readStats_body_bmi2
  - lib/zstd/common/entropy_common.c:HUF_readStats_body_bmi2
  - lib/zstd/common/entropy_common.c:HUF_readStats_body_default
  - lib/zstd/common/entropy_common.c:HUF_readStats_body_default
  - lib/zstd/common/entropy_common.c:FSE_readNCount_body_bmi2
  - lib/zstd/common/entropy_common.c:FSE_readNCount_body_default
```
```
In lib/zstd/common/fse_decompress.c (ffffffff81884f0a)
Location: lib/zstd/common/bitstream.h:130
Inline: True
Inline callers:
  - lib/zstd/common/fse_decompress.c:FSE_buildDTable_internal
  - lib/zstd/common/fse_decompress.c:BIT_initDStream
  - lib/zstd/common/fse_decompress.c:BIT_initDStream
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
In lib/zstd/compress/fse_compress.c (ffffffff8183e35e)
Location: lib/zstd/common/bitstream.h:130
Inline: True
Inline callers:
  - lib/zstd/compress/fse_compress.c:FSE_normalizeCount
  - lib/zstd/compress/fse_compress.c:FSE_normalizeCount
  - lib/zstd/compress/fse_compress.c:FSE_optimalTableLog
  - lib/zstd/compress/fse_compress.c:FSE_optimalTableLog
  - lib/zstd/compress/fse_compress.c:FSE_optimalTableLog
  - lib/zstd/compress/fse_compress.c:FSE_buildCTable_wksp
```
```
In lib/zstd/compress/huf_compress.c (ffffffff81843e9d)
Location: lib/zstd/common/bitstream.h:130
Inline: True
Inline callers:
  - lib/zstd/compress/huf_compress.c:HUF_buildCTable_wksp
  - lib/zstd/compress/huf_compress.c:HUF_buildCTable_wksp
  - lib/zstd/compress/huf_compress.c:HUF_setMaxHeight
```
```
In lib/zstd/decompress/huf_decompress.c (ffffffff818ab0c1)
Location: lib/zstd/common/bitstream.h:130
Inline: True
Inline callers:
  - lib/zstd/decompress/huf_decompress.c:BIT_initDStream
  - lib/zstd/decompress/huf_decompress.c:BIT_initDStream
```
```
In lib/zstd/decompress/zstd_decompress_block.c (ffffffff818baa11)
Location: lib/zstd/common/bitstream.h:130
Inline: True
Inline callers:
  - lib/zstd/decompress/zstd_decompress_block.c:BIT_initDStream
  - lib/zstd/decompress/zstd_decompress_block.c:BIT_initDStream
```
```
In lib/zstd/common/entropy_common.c (ffffffff818c6686)
Location: lib/zstd/common/bitstream.h:130
Inline: True
Inline callers:
  - lib/zstd/common/entropy_common.c:HUF_readStats_body_bmi2
  - lib/zstd/common/entropy_common.c:HUF_readStats_body_bmi2
  - lib/zstd/common/entropy_common.c:HUF_readStats_body_default
  - lib/zstd/common/entropy_common.c:HUF_readStats_body_default
  - lib/zstd/common/entropy_common.c:FSE_readNCount_body_bmi2
  - lib/zstd/common/entropy_common.c:FSE_readNCount_body_default
```
```
In lib/zstd/common/fse_decompress.c (ffffffff818c741c)
Location: lib/zstd/common/bitstream.h:130
Inline: True
Inline callers:
  - lib/zstd/common/fse_decompress.c:FSE_buildDTable_internal
  - lib/zstd/common/fse_decompress.c:BIT_initDStream
  - lib/zstd/common/fse_decompress.c:BIT_initDStream
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
In lib/zstd/compress/fse_compress.c (ffffffff8188ff1e)
Location: lib/zstd/common/bitstream.h:130
Inline: True
Inline callers:
  - lib/zstd/compress/fse_compress.c:FSE_normalizeCount
  - lib/zstd/compress/fse_compress.c:FSE_normalizeCount
  - lib/zstd/compress/fse_compress.c:FSE_optimalTableLog
  - lib/zstd/compress/fse_compress.c:FSE_optimalTableLog
  - lib/zstd/compress/fse_compress.c:FSE_optimalTableLog
  - lib/zstd/compress/fse_compress.c:FSE_buildCTable_wksp
```
```
In lib/zstd/compress/huf_compress.c (ffffffff81895a5d)
Location: lib/zstd/common/bitstream.h:130
Inline: True
Inline callers:
  - lib/zstd/compress/huf_compress.c:HUF_buildCTable_wksp
  - lib/zstd/compress/huf_compress.c:HUF_buildCTable_wksp
  - lib/zstd/compress/huf_compress.c:HUF_setMaxHeight
```
```
In lib/zstd/decompress/huf_decompress.c (ffffffff818fcc81)
Location: lib/zstd/common/bitstream.h:130
Inline: True
Inline callers:
  - lib/zstd/decompress/huf_decompress.c:BIT_initDStream
  - lib/zstd/decompress/huf_decompress.c:BIT_initDStream
```
```
In lib/zstd/decompress/zstd_decompress_block.c (ffffffff8190c5d1)
Location: lib/zstd/common/bitstream.h:130
Inline: True
Inline callers:
  - lib/zstd/decompress/zstd_decompress_block.c:BIT_initDStream
  - lib/zstd/decompress/zstd_decompress_block.c:BIT_initDStream
```
```
In lib/zstd/common/entropy_common.c (ffffffff81918246)
Location: lib/zstd/common/bitstream.h:130
Inline: True
Inline callers:
  - lib/zstd/common/entropy_common.c:HUF_readStats_body_bmi2
  - lib/zstd/common/entropy_common.c:HUF_readStats_body_bmi2
  - lib/zstd/common/entropy_common.c:HUF_readStats_body_default
  - lib/zstd/common/entropy_common.c:HUF_readStats_body_default
  - lib/zstd/common/entropy_common.c:FSE_readNCount_body_bmi2
  - lib/zstd/common/entropy_common.c:FSE_readNCount_body_default
```
```
In lib/zstd/common/fse_decompress.c (ffffffff81918fdc)
Location: lib/zstd/common/bitstream.h:130
Inline: True
Inline callers:
  - lib/zstd/common/fse_decompress.c:FSE_buildDTable_internal
  - lib/zstd/common/fse_decompress.c:BIT_initDStream
  - lib/zstd/common/fse_decompress.c:BIT_initDStream
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
In lib/zstd/huf_decompress.c (ffff80001064f7d4)
Location: lib/zstd/bitstream.h:148
Inline: True
Inline callers:
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
```
```
In lib/zstd/decompress.c (ffff80001065624c)
Location: lib/zstd/bitstream.h:148
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
```
```
In lib/zstd/entropy_common.c (ffff80001065abfc)
Location: lib/zstd/bitstream.h:148
Inline: True
Inline callers:
  - lib/zstd/entropy_common.c:HUF_readStats_wksp
  - lib/zstd/entropy_common.c:HUF_readStats_wksp
```
```
In lib/zstd/fse_decompress.c (ffff80001065aee4)
Location: lib/zstd/bitstream.h:148
Inline: True
Inline callers:
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_buildDTable_wksp
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
In lib/zstd/huf_decompress.c (c07fab9c)
Location: lib/zstd/bitstream.h:148
Inline: True
Inline callers:
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
```
```
In lib/zstd/decompress.c (c0800be8)
Location: lib/zstd/bitstream.h:148
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
```
```
In lib/zstd/entropy_common.c (c08041b0)
Location: lib/zstd/bitstream.h:148
Inline: True
Inline callers:
  - lib/zstd/entropy_common.c:HUF_readStats_wksp
  - lib/zstd/entropy_common.c:HUF_readStats_wksp
```
```
In lib/zstd/fse_decompress.c (c080484c)
Location: lib/zstd/bitstream.h:148
Inline: True
Inline callers:
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_buildDTable_wksp
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
In lib/zstd/huf_decompress.c (c0000000007fd9c4)
Location: lib/zstd/bitstream.h:148
Inline: True
Inline callers:
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
```
```
In lib/zstd/decompress.c (c0000000008066f0)
Location: lib/zstd/bitstream.h:148
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
```
```
In lib/zstd/entropy_common.c (c00000000080bbc4)
Location: lib/zstd/bitstream.h:148
Inline: True
Inline callers:
  - lib/zstd/entropy_common.c:HUF_readStats_wksp
  - lib/zstd/entropy_common.c:HUF_readStats_wksp
```
```
In lib/zstd/fse_decompress.c (c00000000080bfb4)
Location: lib/zstd/bitstream.h:148
Inline: True
Inline callers:
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_buildDTable_wksp
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
In lib/zstd/huf_decompress.c (ffffffe00047c12c)
Location: lib/zstd/bitstream.h:148
Inline: True
Inline callers:
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
```
```
In lib/zstd/decompress.c (ffffffe000483e5c)
Location: lib/zstd/bitstream.h:148
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
```
```
In lib/zstd/entropy_common.c (ffffffe000488612)
Location: lib/zstd/bitstream.h:148
Inline: True
Inline callers:
  - lib/zstd/entropy_common.c:HUF_readStats_wksp
  - lib/zstd/entropy_common.c:HUF_readStats_wksp
```
```
In lib/zstd/fse_decompress.c (ffffffe000488958)
Location: lib/zstd/bitstream.h:148
Inline: True
Inline callers:
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_buildDTable_wksp
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
In lib/zstd/huf_decompress.c (ffffffff8153adc4)
Location: lib/zstd/bitstream.h:148
Inline: True
Inline callers:
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
```
```
In lib/zstd/decompress.c (ffffffff8154274f)
Location: lib/zstd/bitstream.h:148
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
```
```
In lib/zstd/entropy_common.c (ffffffff8154708e)
Location: lib/zstd/bitstream.h:148
Inline: True
Inline callers:
  - lib/zstd/entropy_common.c:HUF_readStats_wksp
  - lib/zstd/entropy_common.c:HUF_readStats_wksp
```
```
In lib/zstd/fse_decompress.c (ffffffff81547717)
Location: lib/zstd/bitstream.h:148
Inline: True
Inline callers:
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_buildDTable_wksp
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
In lib/zstd/huf_decompress.c (ffffffff8152b0a4)
Location: lib/zstd/bitstream.h:148
Inline: True
Inline callers:
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
```
```
In lib/zstd/decompress.c (ffffffff81532a2f)
Location: lib/zstd/bitstream.h:148
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
```
```
In lib/zstd/entropy_common.c (ffffffff8153736e)
Location: lib/zstd/bitstream.h:148
Inline: True
Inline callers:
  - lib/zstd/entropy_common.c:HUF_readStats_wksp
  - lib/zstd/entropy_common.c:HUF_readStats_wksp
```
```
In lib/zstd/fse_decompress.c (ffffffff815379f7)
Location: lib/zstd/bitstream.h:148
Inline: True
Inline callers:
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_buildDTable_wksp
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
In lib/zstd/huf_decompress.c (ffffffff81536b04)
Location: lib/zstd/bitstream.h:148
Inline: True
Inline callers:
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
```
```
In lib/zstd/decompress.c (ffffffff8153e48f)
Location: lib/zstd/bitstream.h:148
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
```
```
In lib/zstd/entropy_common.c (ffffffff81542dce)
Location: lib/zstd/bitstream.h:148
Inline: True
Inline callers:
  - lib/zstd/entropy_common.c:HUF_readStats_wksp
  - lib/zstd/entropy_common.c:HUF_readStats_wksp
```
```
In lib/zstd/fse_decompress.c (ffffffff81543457)
Location: lib/zstd/bitstream.h:148
Inline: True
Inline callers:
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_buildDTable_wksp
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
In lib/zstd/huf_decompress.c (ffffffff81550934)
Location: lib/zstd/bitstream.h:148
Inline: True
Inline callers:
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
```
```
In lib/zstd/decompress.c (ffffffff815582bf)
Location: lib/zstd/bitstream.h:148
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
```
```
In lib/zstd/entropy_common.c (ffffffff8155cbfe)
Location: lib/zstd/bitstream.h:148
Inline: True
Inline callers:
  - lib/zstd/entropy_common.c:HUF_readStats_wksp
  - lib/zstd/entropy_common.c:HUF_readStats_wksp
```
```
In lib/zstd/fse_decompress.c (ffffffff8155d287)
Location: lib/zstd/bitstream.h:148
Inline: True
Inline callers:
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/fse_decompress.c:FSE_buildDTable_wksp
```
</details>
</li>
</ul>

## Differences
