# Function: <code>MEM_write64</code>

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
In lib/zstd/common/fse_decompress.c (ffffffff8170a3f6)
Location: lib/zstd/common/mem.h:139
Inline: True
Inline callers:
  - lib/zstd/common/fse_decompress.c:FSE_buildDTable_internal
  - lib/zstd/common/fse_decompress.c:FSE_buildDTable_internal
```
```
In lib/zstd/decompress/huf_decompress.c (ffffffff8174f029)
Location: lib/zstd/common/mem.h:139
Inline: True
Inline callers:
  - lib/zstd/decompress/huf_decompress.c:HUF_readDTableX1_wksp_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_readDTableX1_wksp_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_readDTableX1_wksp_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_readDTableX1_wksp_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_readDTableX1_wksp_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_readDTableX1_wksp_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_readDTableX1_wksp_bmi2
```
```
In lib/zstd/decompress/zstd_decompress_block.c (ffffffff81755330)
Location: lib/zstd/common/mem.h:139
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
In lib/zstd/compress/fse_compress.c (ffffffff817fd6ac)
Location: lib/zstd/common/mem.h:141
Inline: True
Inline callers:
  - lib/zstd/compress/fse_compress.c:FSE_buildCTable_wksp
  - lib/zstd/compress/fse_compress.c:FSE_buildCTable_wksp
```
```
In lib/zstd/decompress/huf_decompress.c (ffffffff8187300c)
Location: lib/zstd/common/mem.h:141
Inline: True
Inline callers:
  - lib/zstd/decompress/huf_decompress.c:HUF_readDTableX1_wksp_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_readDTableX1_wksp_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_readDTableX1_wksp_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_readDTableX1_wksp_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_readDTableX1_wksp_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_readDTableX1_wksp_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_readDTableX1_wksp_bmi2
```
```
In lib/zstd/decompress/zstd_decompress_block.c (ffffffff81879f6a)
Location: lib/zstd/common/mem.h:141
Inline: True
```
```
In lib/zstd/common/fse_decompress.c (ffffffff81884fa6)
Location: lib/zstd/common/mem.h:141
Inline: True
Inline callers:
  - lib/zstd/common/fse_decompress.c:FSE_buildDTable_internal
  - lib/zstd/common/fse_decompress.c:FSE_buildDTable_internal
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
In lib/zstd/compress/fse_compress.c (ffffffff8183dee9)
Location: lib/zstd/common/mem.h:141
Inline: True
Inline callers:
  - lib/zstd/compress/fse_compress.c:FSE_buildCTable_wksp
  - lib/zstd/compress/fse_compress.c:FSE_buildCTable_wksp
```
```
In lib/zstd/decompress/huf_decompress.c (ffffffff818b3c36)
Location: lib/zstd/common/mem.h:141
Inline: True
Inline callers:
  - lib/zstd/decompress/huf_decompress.c:HUF_readDTableX1_wksp_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_readDTableX1_wksp_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_readDTableX1_wksp_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_readDTableX1_wksp_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_readDTableX1_wksp_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_readDTableX1_wksp_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_readDTableX1_wksp_bmi2
```
```
In lib/zstd/decompress/zstd_decompress_block.c (ffffffff818bad85)
Location: lib/zstd/common/mem.h:141
Inline: True
```
```
In lib/zstd/common/fse_decompress.c (ffffffff818c7498)
Location: lib/zstd/common/mem.h:141
Inline: True
Inline callers:
  - lib/zstd/common/fse_decompress.c:FSE_buildDTable_internal
  - lib/zstd/common/fse_decompress.c:FSE_buildDTable_internal
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
In lib/zstd/compress/fse_compress.c (ffffffff8188faa9)
Location: lib/zstd/common/mem.h:141
Inline: True
Inline callers:
  - lib/zstd/compress/fse_compress.c:FSE_buildCTable_wksp
  - lib/zstd/compress/fse_compress.c:FSE_buildCTable_wksp
```
```
In lib/zstd/decompress/huf_decompress.c (ffffffff819057f6)
Location: lib/zstd/common/mem.h:141
Inline: True
Inline callers:
  - lib/zstd/decompress/huf_decompress.c:HUF_readDTableX1_wksp_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_readDTableX1_wksp_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_readDTableX1_wksp_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_readDTableX1_wksp_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_readDTableX1_wksp_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_readDTableX1_wksp_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_readDTableX1_wksp_bmi2
```
```
In lib/zstd/decompress/zstd_decompress_block.c (ffffffff8190c945)
Location: lib/zstd/common/mem.h:141
Inline: True
```
```
In lib/zstd/common/fse_decompress.c (ffffffff81919058)
Location: lib/zstd/common/mem.h:141
Inline: True
Inline callers:
  - lib/zstd/common/fse_decompress.c:FSE_buildDTable_internal
  - lib/zstd/common/fse_decompress.c:FSE_buildDTable_internal
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
