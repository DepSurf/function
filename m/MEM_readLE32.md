# Function: <code>MEM_readLE32</code>

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
In lib/zstd/common/entropy_common.c (ffffffff81709d3e)
Location: lib/zstd/common/mem.h:167
Inline: True
Inline callers:
  - lib/zstd/common/entropy_common.c:FSE_readNCount_body_bmi2
  - lib/zstd/common/entropy_common.c:FSE_readNCount_body_bmi2
  - lib/zstd/common/entropy_common.c:FSE_readNCount_body_bmi2
  - lib/zstd/common/entropy_common.c:FSE_readNCount_body_bmi2
  - lib/zstd/common/entropy_common.c:FSE_readNCount_body_default
  - lib/zstd/common/entropy_common.c:FSE_readNCount_body_default
  - lib/zstd/common/entropy_common.c:FSE_readNCount_body_default
  - lib/zstd/common/entropy_common.c:FSE_readNCount_body_default
```
```
In lib/zstd/common/fse_decompress.c (0)
Location: lib/zstd/common/mem.h:167
Inline: True
```
```
In lib/zstd/compress/zstd_compress.c (ffffffff81718cbc)
Location: lib/zstd/common/mem.h:167
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_compress_insertDictionary
  - lib/zstd/compress/zstd_compress.c:ZSTD_compress_insertDictionary
  - lib/zstd/compress/zstd_compress.c:ZSTD_loadCEntropy
  - lib/zstd/compress/zstd_compress.c:ZSTD_loadCEntropy
  - lib/zstd/compress/zstd_compress.c:ZSTD_loadCEntropy
```
```
In lib/zstd/compress/zstd_opt.c (ffffffff81746ac4)
Location: lib/zstd/common/mem.h:167
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_opt.c:ZSTD_insertBtAndGetAllMatches
  - lib/zstd/compress/zstd_opt.c:ZSTD_insertBtAndGetAllMatches
```
```
In lib/zstd/decompress/huf_decompress.c (0)
Location: lib/zstd/common/mem.h:167
Inline: True
```
```
In lib/zstd/decompress/zstd_ddict.c (ffffffff81750604)
Location: lib/zstd/common/mem.h:167
Inline: True
Inline callers:
  - lib/zstd/decompress/zstd_ddict.c:ZSTD_initDDict_internal
  - lib/zstd/decompress/zstd_ddict.c:ZSTD_initDDict_internal
```
```
In lib/zstd/decompress/zstd_decompress.c (ffffffff8175488b)
Location: lib/zstd/common/mem.h:167
Inline: True
Inline callers:
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_decompressStream
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_decompressStream
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_getDictID_fromDict
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_getDictID_fromDict
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_loadDEntropy
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_decompressMultiFrame
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_decompressMultiFrame
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_decompressFrame
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_findFrameSizeInfo
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_findFrameSizeInfo
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_findDecompressedSize
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_findDecompressedSize
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_getFrameHeader_advanced
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_getFrameHeader_advanced
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_getFrameHeader_advanced
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_getFrameHeader_advanced
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_getFrameHeader_advanced
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_isFrame
```
```
In lib/zstd/decompress/zstd_decompress_block.c (ffffffff81759dd1)
Location: lib/zstd/common/mem.h:167
Inline: True
Inline callers:
  - lib/zstd/decompress/zstd_decompress_block.c:ZSTD_decodeLiteralsBlock
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
In lib/zstd/compress/zstd_compress.c (ffffffff8180e0fc)
Location: lib/zstd/common/mem.h:169
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_compress_insertDictionary
  - lib/zstd/compress/zstd_compress.c:ZSTD_compress_insertDictionary
  - lib/zstd/compress/zstd_compress.c:ZSTD_loadCEntropy
  - lib/zstd/compress/zstd_compress.c:ZSTD_loadCEntropy
  - lib/zstd/compress/zstd_compress.c:ZSTD_loadCEntropy
```
```
In lib/zstd/compress/zstd_opt.c (ffffffff8185e68b)
Location: lib/zstd/common/mem.h:169
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_opt.c:ZSTD_insertAndFindFirstIndexHash3
  - lib/zstd/compress/zstd_opt.c:ZSTD_insertAndFindFirstIndexHash3
```
```
In lib/zstd/decompress/huf_decompress.c (0)
Location: lib/zstd/common/mem.h:169
Inline: True
```
```
In lib/zstd/decompress/zstd_ddict.c (ffffffff81874764)
Location: lib/zstd/common/mem.h:169
Inline: True
Inline callers:
  - lib/zstd/decompress/zstd_ddict.c:ZSTD_initDDict_internal
  - lib/zstd/decompress/zstd_ddict.c:ZSTD_initDDict_internal
```
```
In lib/zstd/decompress/zstd_decompress.c (ffffffff81878f5c)
Location: lib/zstd/common/mem.h:169
Inline: True
Inline callers:
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_decompressStream
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_decompressStream
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_getDictID_fromDict
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_getDictID_fromDict
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_loadDEntropy
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_decompressMultiFrame
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_decompressMultiFrame
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_decompressFrame
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_findFrameSizeInfo
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_findFrameSizeInfo
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_findDecompressedSize
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_findDecompressedSize
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_readSkippableFrame
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_readSkippableFrame
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_readSkippableFrame
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_getFrameHeader_advanced
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_getFrameHeader_advanced
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_getFrameHeader_advanced
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_getFrameHeader_advanced
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_getFrameHeader_advanced
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_isFrame
```
```
In lib/zstd/decompress/zstd_decompress_block.c (ffffffff8188330c)
Location: lib/zstd/common/mem.h:169
Inline: True
Inline callers:
  - lib/zstd/decompress/zstd_decompress_block.c:ZSTD_decodeLiteralsBlock
```
```
In lib/zstd/common/entropy_common.c (ffffffff8188482e)
Location: lib/zstd/common/mem.h:169
Inline: True
Inline callers:
  - lib/zstd/common/entropy_common.c:FSE_readNCount_body_bmi2
  - lib/zstd/common/entropy_common.c:FSE_readNCount_body_bmi2
  - lib/zstd/common/entropy_common.c:FSE_readNCount_body_bmi2
  - lib/zstd/common/entropy_common.c:FSE_readNCount_body_bmi2
  - lib/zstd/common/entropy_common.c:FSE_readNCount_body_default
  - lib/zstd/common/entropy_common.c:FSE_readNCount_body_default
  - lib/zstd/common/entropy_common.c:FSE_readNCount_body_default
  - lib/zstd/common/entropy_common.c:FSE_readNCount_body_default
```
```
In lib/zstd/common/fse_decompress.c (0)
Location: lib/zstd/common/mem.h:169
Inline: True
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
In lib/zstd/compress/zstd_compress.c (ffffffff8184ec0c)
Location: lib/zstd/common/mem.h:169
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_compress_insertDictionary
  - lib/zstd/compress/zstd_compress.c:ZSTD_compress_insertDictionary
  - lib/zstd/compress/zstd_compress.c:ZSTD_loadCEntropy
  - lib/zstd/compress/zstd_compress.c:ZSTD_loadCEntropy
  - lib/zstd/compress/zstd_compress.c:ZSTD_loadCEntropy
```
```
In lib/zstd/compress/zstd_opt.c (ffffffff8189f23b)
Location: lib/zstd/common/mem.h:169
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_opt.c:ZSTD_insertAndFindFirstIndexHash3
  - lib/zstd/compress/zstd_opt.c:ZSTD_insertAndFindFirstIndexHash3
```
```
In lib/zstd/decompress/huf_decompress.c (0)
Location: lib/zstd/common/mem.h:169
Inline: True
```
```
In lib/zstd/decompress/zstd_ddict.c (ffffffff818b54c4)
Location: lib/zstd/common/mem.h:169
Inline: True
Inline callers:
  - lib/zstd/decompress/zstd_ddict.c:ZSTD_initDDict_internal
  - lib/zstd/decompress/zstd_ddict.c:ZSTD_initDDict_internal
```
```
In lib/zstd/decompress/zstd_decompress.c (ffffffff818b9d0c)
Location: lib/zstd/common/mem.h:169
Inline: True
Inline callers:
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_decompressStream
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_decompressStream
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_getDictID_fromDict
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_getDictID_fromDict
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_loadDEntropy
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_decompressMultiFrame
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_decompressMultiFrame
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_decompressFrame
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_findFrameSizeInfo
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_findFrameSizeInfo
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_findDecompressedSize
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_findDecompressedSize
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_readSkippableFrame
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_readSkippableFrame
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_readSkippableFrame
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_getFrameHeader_advanced
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_getFrameHeader_advanced
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_getFrameHeader_advanced
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_getFrameHeader_advanced
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_getFrameHeader_advanced
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_isFrame
```
```
In lib/zstd/decompress/zstd_decompress_block.c (ffffffff818c5861)
Location: lib/zstd/common/mem.h:169
Inline: True
Inline callers:
  - lib/zstd/decompress/zstd_decompress_block.c:ZSTD_decodeLiteralsBlock
```
```
In lib/zstd/common/entropy_common.c (ffffffff818c6d3e)
Location: lib/zstd/common/mem.h:169
Inline: True
Inline callers:
  - lib/zstd/common/entropy_common.c:FSE_readNCount_body_bmi2
  - lib/zstd/common/entropy_common.c:FSE_readNCount_body_bmi2
  - lib/zstd/common/entropy_common.c:FSE_readNCount_body_bmi2
  - lib/zstd/common/entropy_common.c:FSE_readNCount_body_bmi2
  - lib/zstd/common/entropy_common.c:FSE_readNCount_body_default
  - lib/zstd/common/entropy_common.c:FSE_readNCount_body_default
  - lib/zstd/common/entropy_common.c:FSE_readNCount_body_default
  - lib/zstd/common/entropy_common.c:FSE_readNCount_body_default
```
```
In lib/zstd/common/fse_decompress.c (0)
Location: lib/zstd/common/mem.h:169
Inline: True
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
In lib/zstd/compress/zstd_compress.c (ffffffff818a07cc)
Location: lib/zstd/common/mem.h:169
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_compress_insertDictionary
  - lib/zstd/compress/zstd_compress.c:ZSTD_compress_insertDictionary
  - lib/zstd/compress/zstd_compress.c:ZSTD_loadCEntropy
  - lib/zstd/compress/zstd_compress.c:ZSTD_loadCEntropy
  - lib/zstd/compress/zstd_compress.c:ZSTD_loadCEntropy
```
```
In lib/zstd/compress/zstd_opt.c (ffffffff818f0dfb)
Location: lib/zstd/common/mem.h:169
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_opt.c:ZSTD_insertAndFindFirstIndexHash3
  - lib/zstd/compress/zstd_opt.c:ZSTD_insertAndFindFirstIndexHash3
```
```
In lib/zstd/decompress/huf_decompress.c (0)
Location: lib/zstd/common/mem.h:169
Inline: True
```
```
In lib/zstd/decompress/zstd_ddict.c (ffffffff81907084)
Location: lib/zstd/common/mem.h:169
Inline: True
Inline callers:
  - lib/zstd/decompress/zstd_ddict.c:ZSTD_initDDict_internal
  - lib/zstd/decompress/zstd_ddict.c:ZSTD_initDDict_internal
```
```
In lib/zstd/decompress/zstd_decompress.c (ffffffff8190b8cc)
Location: lib/zstd/common/mem.h:169
Inline: True
Inline callers:
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_decompressStream
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_decompressStream
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_getDictID_fromDict
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_getDictID_fromDict
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_loadDEntropy
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_decompressMultiFrame
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_decompressMultiFrame
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_decompressFrame
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_findFrameSizeInfo
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_findFrameSizeInfo
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_findDecompressedSize
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_findDecompressedSize
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_readSkippableFrame
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_readSkippableFrame
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_readSkippableFrame
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_getFrameHeader_advanced
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_getFrameHeader_advanced
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_getFrameHeader_advanced
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_getFrameHeader_advanced
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_getFrameHeader_advanced
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_isFrame
```
```
In lib/zstd/decompress/zstd_decompress_block.c (ffffffff81917421)
Location: lib/zstd/common/mem.h:169
Inline: True
Inline callers:
  - lib/zstd/decompress/zstd_decompress_block.c:ZSTD_decodeLiteralsBlock
```
```
In lib/zstd/common/entropy_common.c (ffffffff819188fe)
Location: lib/zstd/common/mem.h:169
Inline: True
Inline callers:
  - lib/zstd/common/entropy_common.c:FSE_readNCount_body_bmi2
  - lib/zstd/common/entropy_common.c:FSE_readNCount_body_bmi2
  - lib/zstd/common/entropy_common.c:FSE_readNCount_body_bmi2
  - lib/zstd/common/entropy_common.c:FSE_readNCount_body_bmi2
  - lib/zstd/common/entropy_common.c:FSE_readNCount_body_default
  - lib/zstd/common/entropy_common.c:FSE_readNCount_body_default
  - lib/zstd/common/entropy_common.c:FSE_readNCount_body_default
  - lib/zstd/common/entropy_common.c:FSE_readNCount_body_default
```
```
In lib/zstd/common/fse_decompress.c (0)
Location: lib/zstd/common/mem.h:169
Inline: True
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
