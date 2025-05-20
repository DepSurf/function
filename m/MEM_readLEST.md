# Function: <code>MEM_readLEST</code>

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
In lib/zstd/common/fse_decompress.c (ffffffff8170ad0b)
Location: lib/zstd/common/mem.h:187
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
  - lib/zstd/common/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/common/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/common/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/common/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/common/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/common/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/common/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/common/fse_decompress.c:BIT_initDStream
```
```
In lib/zstd/decompress/huf_decompress.c (ffffffff8174c1b4)
Location: lib/zstd/common/mem.h:187
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
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
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
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress1X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress1X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:BIT_initDStream
```
```
In lib/zstd/decompress/zstd_decompress_block.c (ffffffff81755d66)
Location: lib/zstd/common/mem.h:187
Inline: True
Inline callers:
  - lib/zstd/decompress/zstd_decompress_block.c:ZSTD_initFseState
  - lib/zstd/decompress/zstd_decompress_block.c:ZSTD_initFseState
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
In lib/zstd/decompress/huf_decompress.c (ffffffff8186ac6e)
Location: lib/zstd/common/mem.h:189
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
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
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
  - lib/zstd/decompress/huf_decompress.c:BIT_initDStream
```
```
In lib/zstd/decompress/zstd_decompress_block.c (ffffffff8187a630)
Location: lib/zstd/common/mem.h:189
Inline: True
Inline callers:
  - lib/zstd/decompress/zstd_decompress_block.c:ZSTD_initFseState
  - lib/zstd/decompress/zstd_decompress_block.c:ZSTD_initFseState
  - lib/zstd/decompress/zstd_decompress_block.c:BIT_initDStream
```
```
In lib/zstd/common/fse_decompress.c (ffffffff818858d1)
Location: lib/zstd/common/mem.h:189
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
  - lib/zstd/common/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/common/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/common/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/common/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/common/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/common/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/common/fse_decompress.c:FSE_decompress_usingDTable
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
In lib/zstd/decompress/huf_decompress.c (ffffffff818ab95e)
Location: lib/zstd/common/mem.h:189
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
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
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
  - lib/zstd/decompress/huf_decompress.c:BIT_initDStream
```
```
In lib/zstd/decompress/zstd_decompress_block.c (ffffffff818bb470)
Location: lib/zstd/common/mem.h:189
Inline: True
Inline callers:
  - lib/zstd/decompress/zstd_decompress_block.c:ZSTD_initFseState
  - lib/zstd/decompress/zstd_decompress_block.c:ZSTD_initFseState
  - lib/zstd/decompress/zstd_decompress_block.c:BIT_initDStream
```
```
In lib/zstd/common/fse_decompress.c (ffffffff818c7d92)
Location: lib/zstd/common/mem.h:189
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
  - lib/zstd/common/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/common/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/common/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/common/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/common/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/common/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/common/fse_decompress.c:FSE_decompress_usingDTable
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
In lib/zstd/decompress/huf_decompress.c (ffffffff818fd51e)
Location: lib/zstd/common/mem.h:189
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
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
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
  - lib/zstd/decompress/huf_decompress.c:BIT_initDStream
```
```
In lib/zstd/decompress/zstd_decompress_block.c (ffffffff8190d030)
Location: lib/zstd/common/mem.h:189
Inline: True
Inline callers:
  - lib/zstd/decompress/zstd_decompress_block.c:ZSTD_initFseState
  - lib/zstd/decompress/zstd_decompress_block.c:ZSTD_initFseState
  - lib/zstd/decompress/zstd_decompress_block.c:BIT_initDStream
```
```
In lib/zstd/common/fse_decompress.c (ffffffff81919952)
Location: lib/zstd/common/mem.h:189
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
  - lib/zstd/common/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/common/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/common/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/common/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/common/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/common/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/common/fse_decompress.c:FSE_decompress_usingDTable
  - lib/zstd/common/fse_decompress.c:BIT_initDStream
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
