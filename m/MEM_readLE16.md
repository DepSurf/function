# Function: <code>MEM_readLE16</code>

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
In lib/zstd/decompress/huf_decompress.c (ffffffff8174baa5)
Location: lib/zstd/common/mem.h:146
Inline: True
Inline callers:
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
```
```
In lib/zstd/decompress/zstd_decompress.c (ffffffff8175191f)
Location: lib/zstd/common/mem.h:146
Inline: True
Inline callers:
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_getFrameHeader_advanced
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_getFrameHeader_advanced
```
```
In lib/zstd/decompress/zstd_decompress_block.c (ffffffff8175a3d5)
Location: lib/zstd/common/mem.h:146
Inline: True
Inline callers:
  - lib/zstd/decompress/zstd_decompress_block.c:ZSTD_decodeSeqHeaders
  - lib/zstd/decompress/zstd_decompress_block.c:ZSTD_decodeLiteralsBlock
  - lib/zstd/decompress/zstd_decompress_block.c:ZSTD_decodeLiteralsBlock
  - lib/zstd/decompress/zstd_decompress_block.c:ZSTD_decodeLiteralsBlock
  - lib/zstd/decompress/zstd_decompress_block.c:ZSTD_decodeLiteralsBlock
  - lib/zstd/decompress/zstd_decompress_block.c:ZSTD_getcBlockSize
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
In lib/zstd/decompress/huf_decompress.c (ffffffff8187062a)
Location: lib/zstd/common/mem.h:148
Inline: True
Inline callers:
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
```
```
In lib/zstd/decompress/zstd_decompress.c (ffffffff81875b9f)
Location: lib/zstd/common/mem.h:148
Inline: True
Inline callers:
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_getFrameHeader_advanced
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_getFrameHeader_advanced
```
```
In lib/zstd/decompress/zstd_decompress_block.c (ffffffff81883be5)
Location: lib/zstd/common/mem.h:148
Inline: True
Inline callers:
  - lib/zstd/decompress/zstd_decompress_block.c:ZSTD_decodeSeqHeaders
  - lib/zstd/decompress/zstd_decompress_block.c:ZSTD_decodeLiteralsBlock
  - lib/zstd/decompress/zstd_decompress_block.c:ZSTD_decodeLiteralsBlock
  - lib/zstd/decompress/zstd_decompress_block.c:ZSTD_decodeLiteralsBlock
  - lib/zstd/decompress/zstd_decompress_block.c:ZSTD_decodeLiteralsBlock
  - lib/zstd/decompress/zstd_decompress_block.c:ZSTD_getcBlockSize
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
In lib/zstd/decompress/huf_decompress.c (ffffffff818b130a)
Location: lib/zstd/common/mem.h:148
Inline: True
Inline callers:
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
```
```
In lib/zstd/decompress/zstd_decompress.c (ffffffff818b6874)
Location: lib/zstd/common/mem.h:148
Inline: True
Inline callers:
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_getFrameHeader_advanced
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_getFrameHeader_advanced
```
```
In lib/zstd/decompress/zstd_decompress_block.c (ffffffff818c6105)
Location: lib/zstd/common/mem.h:148
Inline: True
Inline callers:
  - lib/zstd/decompress/zstd_decompress_block.c:ZSTD_decodeSeqHeaders
  - lib/zstd/decompress/zstd_decompress_block.c:ZSTD_decodeLiteralsBlock
  - lib/zstd/decompress/zstd_decompress_block.c:ZSTD_decodeLiteralsBlock
  - lib/zstd/decompress/zstd_decompress_block.c:ZSTD_decodeLiteralsBlock
  - lib/zstd/decompress/zstd_decompress_block.c:ZSTD_decodeLiteralsBlock
  - lib/zstd/decompress/zstd_decompress_block.c:ZSTD_getcBlockSize
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
In lib/zstd/decompress/huf_decompress.c (ffffffff81902eca)
Location: lib/zstd/common/mem.h:148
Inline: True
Inline callers:
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2
```
```
In lib/zstd/decompress/zstd_decompress.c (ffffffff81908434)
Location: lib/zstd/common/mem.h:148
Inline: True
Inline callers:
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_getFrameHeader_advanced
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_getFrameHeader_advanced
```
```
In lib/zstd/decompress/zstd_decompress_block.c (ffffffff81917cc5)
Location: lib/zstd/common/mem.h:148
Inline: True
Inline callers:
  - lib/zstd/decompress/zstd_decompress_block.c:ZSTD_decodeSeqHeaders
  - lib/zstd/decompress/zstd_decompress_block.c:ZSTD_decodeLiteralsBlock
  - lib/zstd/decompress/zstd_decompress_block.c:ZSTD_decodeLiteralsBlock
  - lib/zstd/decompress/zstd_decompress_block.c:ZSTD_decodeLiteralsBlock
  - lib/zstd/decompress/zstd_decompress_block.c:ZSTD_decodeLiteralsBlock
  - lib/zstd/decompress/zstd_decompress_block.c:ZSTD_getcBlockSize
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
