# Function: <code>MEM_readLE64</code>

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
Location: lib/zstd/common/mem.h:177
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
In lib/zstd/compress/zstd_double_fast.c (ffffffff81721273)
Location: lib/zstd/common/mem.h:177
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_fillDoubleHashTable
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_fillDoubleHashTable
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_fillDoubleHashTable
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_fillDoubleHashTable
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_fillDoubleHashTable
```
```
In lib/zstd/compress/zstd_fast.c (ffffffff8172ae03)
Location: lib/zstd/common/mem.h:177
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_extDict_generic
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_extDict_generic
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_extDict_generic
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_extDict_generic
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_extDict_generic
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_extDict_generic
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_extDict_generic
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_extDict_generic
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_extDict_generic
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_extDict_generic
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_extDict_generic
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_extDict_generic
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_extDict_generic
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_extDict_generic
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_extDict_generic
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_extDict_generic
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_extDict_generic
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_extDict_generic
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_extDict_generic
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_extDict_generic
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_extDict_generic
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_extDict_generic
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_extDict_generic
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_extDict_generic
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_extDict_generic
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_extDict_generic
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_extDict_generic
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast
  - lib/zstd/compress/zstd_fast.c:ZSTD_fillHashTable
  - lib/zstd/compress/zstd_fast.c:ZSTD_fillHashTable
  - lib/zstd/compress/zstd_fast.c:ZSTD_fillHashTable
  - lib/zstd/compress/zstd_fast.c:ZSTD_fillHashTable
  - lib/zstd/compress/zstd_fast.c:ZSTD_fillHashTable
  - lib/zstd/compress/zstd_fast.c:ZSTD_fillHashTable
  - lib/zstd/compress/zstd_fast.c:ZSTD_fillHashTable
  - lib/zstd/compress/zstd_fast.c:ZSTD_fillHashTable
```
```
In lib/zstd/compress/zstd_lazy.c (ffffffff81741c2a)
Location: lib/zstd/common/mem.h:177
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2
  - lib/zstd/compress/zstd_lazy.c:ZSTD_dedicatedDictSearch_lazy_loadDictionary
  - lib/zstd/compress/zstd_lazy.c:ZSTD_dedicatedDictSearch_lazy_loadDictionary
  - lib/zstd/compress/zstd_lazy.c:ZSTD_dedicatedDictSearch_lazy_loadDictionary
  - lib/zstd/compress/zstd_lazy.c:ZSTD_dedicatedDictSearch_lazy_loadDictionary
  - lib/zstd/compress/zstd_lazy.c:ZSTD_dedicatedDictSearch_lazy_loadDictionary
  - lib/zstd/compress/zstd_lazy.c:ZSTD_dedicatedDictSearch_lazy_loadDictionary
  - lib/zstd/compress/zstd_lazy.c:ZSTD_dedicatedDictSearch_lazy_loadDictionary
  - lib/zstd/compress/zstd_lazy.c:ZSTD_dedicatedDictSearch_lazy_loadDictionary
  - lib/zstd/compress/zstd_lazy.c:ZSTD_insertAndFindFirstIndex
  - lib/zstd/compress/zstd_lazy.c:ZSTD_insertAndFindFirstIndex
  - lib/zstd/compress/zstd_lazy.c:ZSTD_insertAndFindFirstIndex
  - lib/zstd/compress/zstd_lazy.c:ZSTD_insertAndFindFirstIndex
  - lib/zstd/compress/zstd_lazy.c:ZSTD_insertAndFindFirstIndex
  - lib/zstd/compress/zstd_lazy.c:ZSTD_insertAndFindFirstIndex
  - lib/zstd/compress/zstd_lazy.c:ZSTD_insertAndFindFirstIndex
  - lib/zstd/compress/zstd_lazy.c:ZSTD_insertAndFindFirstIndex
  - lib/zstd/compress/zstd_lazy.c:ZSTD_DUBT_findBestMatch
  - lib/zstd/compress/zstd_lazy.c:ZSTD_DUBT_findBestMatch
```
```
In lib/zstd/compress/zstd_opt.c (ffffffff817464a1)
Location: lib/zstd/common/mem.h:177
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_opt.c:ZSTD_insertBtAndGetAllMatches
  - lib/zstd/compress/zstd_opt.c:ZSTD_insertBtAndGetAllMatches
  - lib/zstd/compress/zstd_opt.c:ZSTD_insertBtAndGetAllMatches
  - lib/zstd/compress/zstd_opt.c:ZSTD_insertBtAndGetAllMatches
  - lib/zstd/compress/zstd_opt.c:ZSTD_insertBt1
  - lib/zstd/compress/zstd_opt.c:ZSTD_insertBt1
  - lib/zstd/compress/zstd_opt.c:ZSTD_insertBt1
  - lib/zstd/compress/zstd_opt.c:ZSTD_insertBt1
```
```
In lib/zstd/decompress/huf_decompress.c (ffffffff8174c1b4)
Location: lib/zstd/common/mem.h:177
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
In lib/zstd/decompress/zstd_decompress.c (ffffffff8175190a)
Location: lib/zstd/common/mem.h:177
Inline: True
Inline callers:
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_getFrameHeader_advanced
```
```
In lib/zstd/decompress/zstd_decompress_block.c (ffffffff81755d66)
Location: lib/zstd/common/mem.h:177
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
In lib/zstd/compress/zstd_double_fast.c (ffffffff8181e4ce)
Location: lib/zstd/common/mem.h:179
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_7
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_7
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_7
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_7
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_7
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_7
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_7
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_7
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_7
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_7
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_7
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_7
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_6
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_6
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_6
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_6
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_6
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_6
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_6
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_6
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_6
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_6
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_6
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_6
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_5
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_5
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_5
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_5
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_5
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_5
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_5
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_5
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_5
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_5
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_5
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_5
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_4
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_4
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_4
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_4
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_4
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_4
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_4
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_7
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_7
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_7
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_7
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_7
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_7
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_7
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_7
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_7
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_6
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_6
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_6
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_6
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_6
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_6
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_6
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_6
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_6
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_5
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_5
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_5
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_5
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_5
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_5
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_5
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_5
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_5
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_4
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_4
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_4
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_4
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_4
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_fillDoubleHashTable
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_fillDoubleHashTable
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_fillDoubleHashTable
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_fillDoubleHashTable
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_fillDoubleHashTable
```
```
In lib/zstd/compress/zstd_fast.c (ffffffff8182273a)
Location: lib/zstd/common/mem.h:179
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_7_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_7_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_7_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_7_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_7_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_6_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_6_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_6_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_6_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_6_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_5_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_5_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_5_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_5_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_5_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_7_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_7_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_7_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_7_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_7_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_7_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_7_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_6_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_6_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_6_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_6_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_6_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_6_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_6_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_5_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_5_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_5_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_5_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_5_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_5_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_5_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_7_1
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_7_1
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_7_1
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_7_1
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_7_1
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_7_1
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_7_1
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_6_1
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_6_1
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_6_1
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_6_1
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_6_1
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_6_1
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_6_1
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_5_1
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_5_1
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_5_1
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_5_1
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_5_1
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_5_1
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_5_1
  - lib/zstd/compress/zstd_fast.c:ZSTD_fillHashTable
  - lib/zstd/compress/zstd_fast.c:ZSTD_fillHashTable
  - lib/zstd/compress/zstd_fast.c:ZSTD_fillHashTable
  - lib/zstd/compress/zstd_fast.c:ZSTD_fillHashTable
  - lib/zstd/compress/zstd_fast.c:ZSTD_fillHashTable
  - lib/zstd/compress/zstd_fast.c:ZSTD_fillHashTable
  - lib/zstd/compress/zstd_fast.c:ZSTD_fillHashTable
  - lib/zstd/compress/zstd_fast.c:ZSTD_fillHashTable
```
```
In lib/zstd/compress/zstd_lazy.c (ffffffff8185b9fe)
Location: lib/zstd/common/mem.h:179
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_extDict_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_extDict_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_extDict_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_extDict_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_extDict_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_extDict_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dedicatedDictSearch_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dedicatedDictSearch_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dedicatedDictSearch_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dedicatedDictSearch_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dedicatedDictSearch_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dedicatedDictSearch_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dictMatchState_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dictMatchState_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dictMatchState_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dictMatchState_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dictMatchState_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dictMatchState_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_row_update
  - lib/zstd/compress/zstd_lazy.c:ZSTD_row_update
  - lib/zstd/compress/zstd_lazy.c:ZSTD_insertAndFindFirstIndex
  - lib/zstd/compress/zstd_lazy.c:ZSTD_insertAndFindFirstIndex
  - lib/zstd/compress/zstd_lazy.c:ZSTD_insertAndFindFirstIndex
  - lib/zstd/compress/zstd_lazy.c:ZSTD_insertAndFindFirstIndex
  - lib/zstd/compress/zstd_lazy.c:ZSTD_insertAndFindFirstIndex
  - lib/zstd/compress/zstd_lazy.c:ZSTD_insertAndFindFirstIndex
  - lib/zstd/compress/zstd_lazy.c:ZSTD_insertAndFindFirstIndex
  - lib/zstd/compress/zstd_lazy.c:ZSTD_insertAndFindFirstIndex
  - lib/zstd/compress/zstd_lazy.c:ZSTD_dedicatedDictSearch_lazy_loadDictionary
  - lib/zstd/compress/zstd_lazy.c:ZSTD_dedicatedDictSearch_lazy_loadDictionary
  - lib/zstd/compress/zstd_lazy.c:ZSTD_dedicatedDictSearch_lazy_loadDictionary
  - lib/zstd/compress/zstd_lazy.c:ZSTD_dedicatedDictSearch_lazy_loadDictionary
  - lib/zstd/compress/zstd_lazy.c:ZSTD_dedicatedDictSearch_lazy_loadDictionary
  - lib/zstd/compress/zstd_lazy.c:ZSTD_dedicatedDictSearch_lazy_loadDictionary
  - lib/zstd/compress/zstd_lazy.c:ZSTD_dedicatedDictSearch_lazy_loadDictionary
  - lib/zstd/compress/zstd_lazy.c:ZSTD_dedicatedDictSearch_lazy_loadDictionary
  - lib/zstd/compress/zstd_lazy.c:ZSTD_DUBT_findBestMatch
  - lib/zstd/compress/zstd_lazy.c:ZSTD_DUBT_findBestMatch
```
```
In lib/zstd/compress/zstd_opt.c (ffffffff81866a9c)
Location: lib/zstd/common/mem.h:179
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_6
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_6
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_5
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_5
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_extDict_6
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_extDict_5
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_noDict_6
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_noDict_5
  - lib/zstd/compress/zstd_opt.c:ZSTD_insertBt1
  - lib/zstd/compress/zstd_opt.c:ZSTD_insertBt1
  - lib/zstd/compress/zstd_opt.c:ZSTD_insertBt1
  - lib/zstd/compress/zstd_opt.c:ZSTD_insertBt1
```
```
In lib/zstd/decompress/huf_decompress.c (ffffffff8186ac6e)
Location: lib/zstd/common/mem.h:179
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
In lib/zstd/decompress/zstd_decompress.c (ffffffff81875b8a)
Location: lib/zstd/common/mem.h:179
Inline: True
Inline callers:
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_getFrameHeader_advanced
```
```
In lib/zstd/decompress/zstd_decompress_block.c (ffffffff8187a630)
Location: lib/zstd/common/mem.h:179
Inline: True
Inline callers:
  - lib/zstd/decompress/zstd_decompress_block.c:ZSTD_initFseState
  - lib/zstd/decompress/zstd_decompress_block.c:ZSTD_initFseState
  - lib/zstd/decompress/zstd_decompress_block.c:BIT_initDStream
```
```
In lib/zstd/common/fse_decompress.c (ffffffff818858d1)
Location: lib/zstd/common/mem.h:179
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
In lib/zstd/compress/zstd_double_fast.c (ffffffff8185ecd8)
Location: lib/zstd/common/mem.h:179
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_7
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_7
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_7
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_7
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_7
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_7
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_7
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_7
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_7
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_7
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_7
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_7
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_6
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_6
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_6
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_6
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_6
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_6
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_6
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_6
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_6
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_6
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_6
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_6
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_5
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_5
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_5
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_5
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_5
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_5
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_5
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_5
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_5
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_5
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_5
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_5
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_4
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_4
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_4
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_4
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_4
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_4
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_4
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_7
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_7
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_7
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_7
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_7
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_7
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_7
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_7
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_7
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_6
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_6
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_6
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_6
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_6
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_6
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_6
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_6
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_6
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_5
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_5
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_5
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_5
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_5
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_5
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_5
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_5
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_5
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_4
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_4
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_4
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_4
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_4
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_fillDoubleHashTable
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_fillDoubleHashTable
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_fillDoubleHashTable
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_fillDoubleHashTable
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_fillDoubleHashTable
```
```
In lib/zstd/compress/zstd_fast.c (ffffffff81862ffb)
Location: lib/zstd/common/mem.h:179
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_7_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_7_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_7_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_7_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_7_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_6_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_6_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_6_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_6_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_6_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_5_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_5_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_5_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_5_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_5_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_7_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_7_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_7_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_7_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_7_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_7_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_7_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_6_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_6_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_6_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_6_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_6_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_6_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_6_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_5_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_5_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_5_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_5_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_5_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_5_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_5_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_7_1
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_7_1
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_7_1
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_7_1
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_7_1
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_7_1
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_7_1
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_6_1
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_6_1
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_6_1
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_6_1
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_6_1
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_6_1
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_6_1
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_5_1
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_5_1
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_5_1
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_5_1
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_5_1
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_5_1
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_5_1
  - lib/zstd/compress/zstd_fast.c:ZSTD_fillHashTable
  - lib/zstd/compress/zstd_fast.c:ZSTD_fillHashTable
  - lib/zstd/compress/zstd_fast.c:ZSTD_fillHashTable
  - lib/zstd/compress/zstd_fast.c:ZSTD_fillHashTable
  - lib/zstd/compress/zstd_fast.c:ZSTD_fillHashTable
  - lib/zstd/compress/zstd_fast.c:ZSTD_fillHashTable
  - lib/zstd/compress/zstd_fast.c:ZSTD_fillHashTable
  - lib/zstd/compress/zstd_fast.c:ZSTD_fillHashTable
```
```
In lib/zstd/compress/zstd_lazy.c (ffffffff8189c998)
Location: lib/zstd/common/mem.h:179
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_extDict_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_extDict_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_extDict_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_extDict_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_extDict_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_extDict_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dedicatedDictSearch_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dedicatedDictSearch_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dedicatedDictSearch_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dedicatedDictSearch_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dedicatedDictSearch_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dedicatedDictSearch_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dictMatchState_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dictMatchState_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dictMatchState_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dictMatchState_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dictMatchState_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dictMatchState_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_row_update
  - lib/zstd/compress/zstd_lazy.c:ZSTD_row_update
  - lib/zstd/compress/zstd_lazy.c:ZSTD_insertAndFindFirstIndex
  - lib/zstd/compress/zstd_lazy.c:ZSTD_insertAndFindFirstIndex
  - lib/zstd/compress/zstd_lazy.c:ZSTD_insertAndFindFirstIndex
  - lib/zstd/compress/zstd_lazy.c:ZSTD_insertAndFindFirstIndex
  - lib/zstd/compress/zstd_lazy.c:ZSTD_insertAndFindFirstIndex
  - lib/zstd/compress/zstd_lazy.c:ZSTD_insertAndFindFirstIndex
  - lib/zstd/compress/zstd_lazy.c:ZSTD_insertAndFindFirstIndex
  - lib/zstd/compress/zstd_lazy.c:ZSTD_insertAndFindFirstIndex
  - lib/zstd/compress/zstd_lazy.c:ZSTD_dedicatedDictSearch_lazy_loadDictionary
  - lib/zstd/compress/zstd_lazy.c:ZSTD_dedicatedDictSearch_lazy_loadDictionary
  - lib/zstd/compress/zstd_lazy.c:ZSTD_dedicatedDictSearch_lazy_loadDictionary
  - lib/zstd/compress/zstd_lazy.c:ZSTD_dedicatedDictSearch_lazy_loadDictionary
  - lib/zstd/compress/zstd_lazy.c:ZSTD_dedicatedDictSearch_lazy_loadDictionary
  - lib/zstd/compress/zstd_lazy.c:ZSTD_dedicatedDictSearch_lazy_loadDictionary
  - lib/zstd/compress/zstd_lazy.c:ZSTD_dedicatedDictSearch_lazy_loadDictionary
  - lib/zstd/compress/zstd_lazy.c:ZSTD_dedicatedDictSearch_lazy_loadDictionary
  - lib/zstd/compress/zstd_lazy.c:ZSTD_DUBT_findBestMatch
  - lib/zstd/compress/zstd_lazy.c:ZSTD_DUBT_findBestMatch
```
```
In lib/zstd/compress/zstd_opt.c (ffffffff818a76d9)
Location: lib/zstd/common/mem.h:179
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_6
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_6
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_5
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_5
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_extDict_6
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_extDict_5
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_noDict_6
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_noDict_5
  - lib/zstd/compress/zstd_opt.c:ZSTD_insertBt1
  - lib/zstd/compress/zstd_opt.c:ZSTD_insertBt1
  - lib/zstd/compress/zstd_opt.c:ZSTD_insertBt1
  - lib/zstd/compress/zstd_opt.c:ZSTD_insertBt1
```
```
In lib/zstd/decompress/huf_decompress.c (ffffffff818ab95e)
Location: lib/zstd/common/mem.h:179
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
In lib/zstd/decompress/zstd_decompress.c (ffffffff818b6920)
Location: lib/zstd/common/mem.h:179
Inline: True
Inline callers:
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_getFrameHeader_advanced
```
```
In lib/zstd/decompress/zstd_decompress_block.c (ffffffff818bb470)
Location: lib/zstd/common/mem.h:179
Inline: True
Inline callers:
  - lib/zstd/decompress/zstd_decompress_block.c:ZSTD_initFseState
  - lib/zstd/decompress/zstd_decompress_block.c:ZSTD_initFseState
  - lib/zstd/decompress/zstd_decompress_block.c:BIT_initDStream
```
```
In lib/zstd/common/fse_decompress.c (ffffffff818c7d92)
Location: lib/zstd/common/mem.h:179
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
In lib/zstd/compress/zstd_double_fast.c (ffffffff818b0898)
Location: lib/zstd/common/mem.h:179
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_7
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_7
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_7
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_7
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_7
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_7
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_7
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_7
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_7
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_7
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_7
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_7
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_6
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_6
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_6
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_6
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_6
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_6
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_6
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_6
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_6
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_6
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_6
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_6
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_5
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_5
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_5
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_5
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_5
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_5
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_5
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_5
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_5
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_5
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_5
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_5
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_4
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_4
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_4
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_4
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_4
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_4
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_4
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_7
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_7
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_7
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_7
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_7
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_7
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_7
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_7
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_7
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_6
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_6
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_6
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_6
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_6
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_6
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_6
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_6
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_6
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_5
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_5
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_5
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_5
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_5
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_5
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_5
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_5
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_5
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_4
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_4
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_4
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_4
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_4
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_fillDoubleHashTable
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_fillDoubleHashTable
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_fillDoubleHashTable
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_fillDoubleHashTable
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_fillDoubleHashTable
```
```
In lib/zstd/compress/zstd_fast.c (ffffffff818b4bbb)
Location: lib/zstd/common/mem.h:179
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_7_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_7_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_7_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_7_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_7_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_6_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_6_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_6_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_6_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_6_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_5_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_5_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_5_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_5_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_5_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_7_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_7_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_7_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_7_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_7_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_7_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_7_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_6_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_6_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_6_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_6_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_6_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_6_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_6_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_5_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_5_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_5_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_5_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_5_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_5_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_5_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_7_1
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_7_1
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_7_1
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_7_1
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_7_1
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_7_1
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_7_1
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_6_1
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_6_1
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_6_1
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_6_1
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_6_1
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_6_1
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_6_1
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_5_1
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_5_1
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_5_1
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_5_1
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_5_1
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_5_1
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_5_1
  - lib/zstd/compress/zstd_fast.c:ZSTD_fillHashTable
  - lib/zstd/compress/zstd_fast.c:ZSTD_fillHashTable
  - lib/zstd/compress/zstd_fast.c:ZSTD_fillHashTable
  - lib/zstd/compress/zstd_fast.c:ZSTD_fillHashTable
  - lib/zstd/compress/zstd_fast.c:ZSTD_fillHashTable
  - lib/zstd/compress/zstd_fast.c:ZSTD_fillHashTable
  - lib/zstd/compress/zstd_fast.c:ZSTD_fillHashTable
  - lib/zstd/compress/zstd_fast.c:ZSTD_fillHashTable
```
```
In lib/zstd/compress/zstd_lazy.c (ffffffff818ee558)
Location: lib/zstd/common/mem.h:179
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_extDict_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_extDict_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_extDict_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_extDict_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_extDict_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_extDict_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dedicatedDictSearch_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dedicatedDictSearch_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dedicatedDictSearch_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dedicatedDictSearch_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dedicatedDictSearch_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dedicatedDictSearch_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dictMatchState_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dictMatchState_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dictMatchState_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dictMatchState_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dictMatchState_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dictMatchState_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_row_update
  - lib/zstd/compress/zstd_lazy.c:ZSTD_row_update
  - lib/zstd/compress/zstd_lazy.c:ZSTD_insertAndFindFirstIndex
  - lib/zstd/compress/zstd_lazy.c:ZSTD_insertAndFindFirstIndex
  - lib/zstd/compress/zstd_lazy.c:ZSTD_insertAndFindFirstIndex
  - lib/zstd/compress/zstd_lazy.c:ZSTD_insertAndFindFirstIndex
  - lib/zstd/compress/zstd_lazy.c:ZSTD_insertAndFindFirstIndex
  - lib/zstd/compress/zstd_lazy.c:ZSTD_insertAndFindFirstIndex
  - lib/zstd/compress/zstd_lazy.c:ZSTD_insertAndFindFirstIndex
  - lib/zstd/compress/zstd_lazy.c:ZSTD_insertAndFindFirstIndex
  - lib/zstd/compress/zstd_lazy.c:ZSTD_dedicatedDictSearch_lazy_loadDictionary
  - lib/zstd/compress/zstd_lazy.c:ZSTD_dedicatedDictSearch_lazy_loadDictionary
  - lib/zstd/compress/zstd_lazy.c:ZSTD_dedicatedDictSearch_lazy_loadDictionary
  - lib/zstd/compress/zstd_lazy.c:ZSTD_dedicatedDictSearch_lazy_loadDictionary
  - lib/zstd/compress/zstd_lazy.c:ZSTD_dedicatedDictSearch_lazy_loadDictionary
  - lib/zstd/compress/zstd_lazy.c:ZSTD_dedicatedDictSearch_lazy_loadDictionary
  - lib/zstd/compress/zstd_lazy.c:ZSTD_dedicatedDictSearch_lazy_loadDictionary
  - lib/zstd/compress/zstd_lazy.c:ZSTD_dedicatedDictSearch_lazy_loadDictionary
  - lib/zstd/compress/zstd_lazy.c:ZSTD_DUBT_findBestMatch
  - lib/zstd/compress/zstd_lazy.c:ZSTD_DUBT_findBestMatch
```
```
In lib/zstd/compress/zstd_opt.c (ffffffff818f9299)
Location: lib/zstd/common/mem.h:179
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_6
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_6
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_5
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_5
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_extDict_6
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_extDict_5
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_noDict_6
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_noDict_5
  - lib/zstd/compress/zstd_opt.c:ZSTD_insertBt1
  - lib/zstd/compress/zstd_opt.c:ZSTD_insertBt1
  - lib/zstd/compress/zstd_opt.c:ZSTD_insertBt1
  - lib/zstd/compress/zstd_opt.c:ZSTD_insertBt1
```
```
In lib/zstd/decompress/huf_decompress.c (ffffffff818fd51e)
Location: lib/zstd/common/mem.h:179
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
In lib/zstd/decompress/zstd_decompress.c (ffffffff819084e0)
Location: lib/zstd/common/mem.h:179
Inline: True
Inline callers:
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_getFrameHeader_advanced
```
```
In lib/zstd/decompress/zstd_decompress_block.c (ffffffff8190d030)
Location: lib/zstd/common/mem.h:179
Inline: True
Inline callers:
  - lib/zstd/decompress/zstd_decompress_block.c:ZSTD_initFseState
  - lib/zstd/decompress/zstd_decompress_block.c:ZSTD_initFseState
  - lib/zstd/decompress/zstd_decompress_block.c:BIT_initDStream
```
```
In lib/zstd/common/fse_decompress.c (ffffffff81919952)
Location: lib/zstd/common/mem.h:179
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
