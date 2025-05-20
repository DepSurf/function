# Function: <code>ZSTD_readLE32</code>

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
In lib/zstd/huf_decompress.c (0)
Location: lib/zstd/mem.h:87
Inline: True
```
```
In lib/zstd/decompress.c (ffffffff814b8496)
Location: lib/zstd/mem.h:87
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_decompressStream
  - lib/zstd/decompress.c:ZSTD_decompressStream
  - lib/zstd/decompress.c:ZSTD_decompressStream
  - lib/zstd/decompress.c:ZSTD_getDictID_fromFrame
  - lib/zstd/decompress.c:ZSTD_getDictID_fromDDict
  - lib/zstd/decompress.c:ZSTD_initDDict
  - lib/zstd/decompress.c:ZSTD_loadEntropy
  - lib/zstd/decompress.c:ZSTD_decompressContinue
  - lib/zstd/decompress.c:ZSTD_decompressDCtx
  - lib/zstd/decompress.c:ZSTD_decompressBlock
  - lib/zstd/decompress.c:ZSTD_findDecompressedSize
```
```
In lib/zstd/entropy_common.c (ffffffff814b90d9)
Location: lib/zstd/mem.h:87
Inline: True
Inline callers:
  - lib/zstd/entropy_common.c:FSE_readNCount
```
```
In lib/zstd/fse_decompress.c (0)
Location: lib/zstd/mem.h:87
Inline: True
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
In lib/zstd/huf_decompress.c (0)
Location: lib/zstd/mem.h:87
Inline: True
```
```
In lib/zstd/decompress.c (ffffffff814e6527)
Location: lib/zstd/mem.h:87
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_getDictID_fromFrame
  - lib/zstd/decompress.c:ZSTD_getDictID_fromFrame
  - lib/zstd/decompress.c:ZSTD_getDictID_fromFrame
  - lib/zstd/decompress.c:ZSTD_getDictID_fromDDict
  - lib/zstd/decompress.c:ZSTD_getDictID_fromDDict
  - lib/zstd/decompress.c:ZSTD_initDDict
  - lib/zstd/decompress.c:ZSTD_initDDict
  - lib/zstd/decompress.c:ZSTD_loadEntropy
  - lib/zstd/decompress.c:ZSTD_decompressContinue
  - lib/zstd/decompress.c:ZSTD_decompressContinue
  - lib/zstd/decompress.c:ZSTD_decompressContinue
  - lib/zstd/decompress.c:ZSTD_decompressDCtx
  - lib/zstd/decompress.c:ZSTD_decompressDCtx
  - lib/zstd/decompress.c:ZSTD_decompressDCtx
  - lib/zstd/decompress.c:ZSTD_findFrameCompressedSize
  - lib/zstd/decompress.c:ZSTD_findFrameCompressedSize
  - lib/zstd/decompress.c:ZSTD_decodeLiteralsBlock
  - lib/zstd/decompress.c:ZSTD_findDecompressedSize
  - lib/zstd/decompress.c:ZSTD_findDecompressedSize
  - lib/zstd/decompress.c:ZSTD_findDecompressedSize
```
```
In lib/zstd/entropy_common.c (ffffffff814eba18)
Location: lib/zstd/mem.h:87
Inline: True
Inline callers:
  - lib/zstd/entropy_common.c:FSE_readNCount
  - lib/zstd/entropy_common.c:FSE_readNCount
  - lib/zstd/entropy_common.c:FSE_readNCount
  - lib/zstd/entropy_common.c:FSE_readNCount
```
```
In lib/zstd/fse_decompress.c (0)
Location: lib/zstd/mem.h:87
Inline: True
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
In lib/zstd/huf_decompress.c (0)
Location: lib/zstd/mem.h:87
Inline: True
```
```
In lib/zstd/decompress.c (ffffffff814fa5d7)
Location: lib/zstd/mem.h:87
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_getDictID_fromFrame
  - lib/zstd/decompress.c:ZSTD_getDictID_fromFrame
  - lib/zstd/decompress.c:ZSTD_getDictID_fromFrame
  - lib/zstd/decompress.c:ZSTD_getDictID_fromDDict
  - lib/zstd/decompress.c:ZSTD_getDictID_fromDDict
  - lib/zstd/decompress.c:ZSTD_initDDict
  - lib/zstd/decompress.c:ZSTD_initDDict
  - lib/zstd/decompress.c:ZSTD_loadEntropy
  - lib/zstd/decompress.c:ZSTD_decompressContinue
  - lib/zstd/decompress.c:ZSTD_decompressContinue
  - lib/zstd/decompress.c:ZSTD_decompressContinue
  - lib/zstd/decompress.c:ZSTD_decompressDCtx
  - lib/zstd/decompress.c:ZSTD_decompressDCtx
  - lib/zstd/decompress.c:ZSTD_decompressDCtx
  - lib/zstd/decompress.c:ZSTD_findFrameCompressedSize
  - lib/zstd/decompress.c:ZSTD_findFrameCompressedSize
  - lib/zstd/decompress.c:ZSTD_decodeLiteralsBlock
  - lib/zstd/decompress.c:ZSTD_findDecompressedSize
  - lib/zstd/decompress.c:ZSTD_findDecompressedSize
  - lib/zstd/decompress.c:ZSTD_findDecompressedSize
```
```
In lib/zstd/entropy_common.c (ffffffff814ff768)
Location: lib/zstd/mem.h:87
Inline: True
Inline callers:
  - lib/zstd/entropy_common.c:FSE_readNCount
  - lib/zstd/entropy_common.c:FSE_readNCount
  - lib/zstd/entropy_common.c:FSE_readNCount
  - lib/zstd/entropy_common.c:FSE_readNCount
```
```
In lib/zstd/fse_decompress.c (0)
Location: lib/zstd/mem.h:87
Inline: True
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
In lib/zstd/huf_decompress.c (0)
Location: lib/zstd/mem.h:87
Inline: True
```
```
In lib/zstd/decompress.c (ffffffff81527d67)
Location: lib/zstd/mem.h:87
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_getDictID_fromFrame
  - lib/zstd/decompress.c:ZSTD_getDictID_fromFrame
  - lib/zstd/decompress.c:ZSTD_getDictID_fromFrame
  - lib/zstd/decompress.c:ZSTD_getDictID_fromDDict
  - lib/zstd/decompress.c:ZSTD_getDictID_fromDDict
  - lib/zstd/decompress.c:ZSTD_initDDict
  - lib/zstd/decompress.c:ZSTD_initDDict
  - lib/zstd/decompress.c:ZSTD_loadEntropy
  - lib/zstd/decompress.c:ZSTD_decompressContinue
  - lib/zstd/decompress.c:ZSTD_decompressContinue
  - lib/zstd/decompress.c:ZSTD_decompressContinue
  - lib/zstd/decompress.c:ZSTD_decompressDCtx
  - lib/zstd/decompress.c:ZSTD_decompressDCtx
  - lib/zstd/decompress.c:ZSTD_decompressDCtx
  - lib/zstd/decompress.c:ZSTD_decompressBlock
  - lib/zstd/decompress.c:ZSTD_findDecompressedSize
  - lib/zstd/decompress.c:ZSTD_findDecompressedSize
  - lib/zstd/decompress.c:ZSTD_findDecompressedSize
```
```
In lib/zstd/entropy_common.c (ffffffff8152d930)
Location: lib/zstd/mem.h:87
Inline: True
Inline callers:
  - lib/zstd/entropy_common.c:FSE_readNCount
  - lib/zstd/entropy_common.c:FSE_readNCount
  - lib/zstd/entropy_common.c:FSE_readNCount
  - lib/zstd/entropy_common.c:FSE_readNCount
```
```
In lib/zstd/fse_decompress.c (0)
Location: lib/zstd/mem.h:87
Inline: True
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
In lib/zstd/huf_decompress.c (0)
Location: lib/zstd/mem.h:87
Inline: True
```
```
In lib/zstd/decompress.c (ffffffff81548bf7)
Location: lib/zstd/mem.h:87
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_getDictID_fromFrame
  - lib/zstd/decompress.c:ZSTD_getDictID_fromFrame
  - lib/zstd/decompress.c:ZSTD_getDictID_fromFrame
  - lib/zstd/decompress.c:ZSTD_getDictID_fromDDict
  - lib/zstd/decompress.c:ZSTD_getDictID_fromDDict
  - lib/zstd/decompress.c:ZSTD_initDDict
  - lib/zstd/decompress.c:ZSTD_initDDict
  - lib/zstd/decompress.c:ZSTD_loadEntropy
  - lib/zstd/decompress.c:ZSTD_decompressContinue
  - lib/zstd/decompress.c:ZSTD_decompressContinue
  - lib/zstd/decompress.c:ZSTD_decompressContinue
  - lib/zstd/decompress.c:ZSTD_decompressDCtx
  - lib/zstd/decompress.c:ZSTD_decompressDCtx
  - lib/zstd/decompress.c:ZSTD_decompressDCtx
  - lib/zstd/decompress.c:ZSTD_decompressBlock
  - lib/zstd/decompress.c:ZSTD_findDecompressedSize
  - lib/zstd/decompress.c:ZSTD_findDecompressedSize
  - lib/zstd/decompress.c:ZSTD_findDecompressedSize
```
```
In lib/zstd/entropy_common.c (ffffffff8154e7c0)
Location: lib/zstd/mem.h:87
Inline: True
Inline callers:
  - lib/zstd/entropy_common.c:FSE_readNCount
  - lib/zstd/entropy_common.c:FSE_readNCount
  - lib/zstd/entropy_common.c:FSE_readNCount
  - lib/zstd/entropy_common.c:FSE_readNCount
```
```
In lib/zstd/fse_decompress.c (0)
Location: lib/zstd/mem.h:87
Inline: True
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
In lib/zstd/compress.c (ffffffff815b95a1)
Location: lib/zstd/mem.h:87
Inline: True
Inline callers:
  - lib/zstd/compress.c:ZSTD_initCDict
  - lib/zstd/compress.c:ZSTD_compress_usingDict
  - lib/zstd/compress.c:ZSTD_loadZstdDictionary
  - lib/zstd/compress.c:ZSTD_loadZstdDictionary
  - lib/zstd/compress.c:ZSTD_loadZstdDictionary
  - lib/zstd/compress.c:ZSTD_loadZstdDictionary
```
```
In lib/zstd/entropy_common.c (ffffffff815cc6e2)
Location: lib/zstd/mem.h:87
Inline: True
Inline callers:
  - lib/zstd/entropy_common.c:FSE_readNCount
  - lib/zstd/entropy_common.c:FSE_readNCount
  - lib/zstd/entropy_common.c:FSE_readNCount
  - lib/zstd/entropy_common.c:FSE_readNCount
```
```
In lib/zstd/fse_decompress.c (0)
Location: lib/zstd/mem.h:87
Inline: True
```
```
In lib/zstd/huf_decompress.c (0)
Location: lib/zstd/mem.h:87
Inline: True
```
```
In lib/zstd/decompress.c (ffffffff815d4537)
Location: lib/zstd/mem.h:87
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_getDictID_fromFrame
  - lib/zstd/decompress.c:ZSTD_getDictID_fromFrame
  - lib/zstd/decompress.c:ZSTD_getDictID_fromFrame
  - lib/zstd/decompress.c:ZSTD_getDictID_fromDDict
  - lib/zstd/decompress.c:ZSTD_getDictID_fromDDict
  - lib/zstd/decompress.c:ZSTD_initDDict
  - lib/zstd/decompress.c:ZSTD_initDDict
  - lib/zstd/decompress.c:ZSTD_loadEntropy
  - lib/zstd/decompress.c:ZSTD_decompressContinue
  - lib/zstd/decompress.c:ZSTD_decompressContinue
  - lib/zstd/decompress.c:ZSTD_decompressContinue
  - lib/zstd/decompress.c:ZSTD_decompressMultiFrame
  - lib/zstd/decompress.c:ZSTD_decompressMultiFrame
  - lib/zstd/decompress.c:ZSTD_decompressMultiFrame
  - lib/zstd/decompress.c:ZSTD_decodeLiteralsBlock
  - lib/zstd/decompress.c:ZSTD_findDecompressedSize
  - lib/zstd/decompress.c:ZSTD_findDecompressedSize
  - lib/zstd/decompress.c:ZSTD_findDecompressedSize
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
In lib/zstd/compress.c (ffffffff815d6a86)
Location: lib/zstd/mem.h:87
Inline: True
Inline callers:
  - lib/zstd/compress.c:ZSTD_initCDict
  - lib/zstd/compress.c:ZSTD_compress_usingDict
  - lib/zstd/compress.c:ZSTD_loadZstdDictionary
  - lib/zstd/compress.c:ZSTD_loadZstdDictionary
  - lib/zstd/compress.c:ZSTD_loadZstdDictionary
  - lib/zstd/compress.c:ZSTD_loadZstdDictionary
```
```
In lib/zstd/entropy_common.c (ffffffff815ea267)
Location: lib/zstd/mem.h:87
Inline: True
Inline callers:
  - lib/zstd/entropy_common.c:FSE_readNCount
  - lib/zstd/entropy_common.c:FSE_readNCount
  - lib/zstd/entropy_common.c:FSE_readNCount
  - lib/zstd/entropy_common.c:FSE_readNCount
```
```
In lib/zstd/fse_decompress.c (0)
Location: lib/zstd/mem.h:87
Inline: True
```
```
In lib/zstd/huf_decompress.c (0)
Location: lib/zstd/mem.h:87
Inline: True
```
```
In lib/zstd/decompress.c (ffffffff815f21bc)
Location: lib/zstd/mem.h:87
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_getDictID_fromFrame
  - lib/zstd/decompress.c:ZSTD_getDictID_fromFrame
  - lib/zstd/decompress.c:ZSTD_getDictID_fromFrame
  - lib/zstd/decompress.c:ZSTD_getDictID_fromDDict
  - lib/zstd/decompress.c:ZSTD_getDictID_fromDDict
  - lib/zstd/decompress.c:ZSTD_initDDict
  - lib/zstd/decompress.c:ZSTD_initDDict
  - lib/zstd/decompress.c:ZSTD_loadEntropy
  - lib/zstd/decompress.c:ZSTD_decompressContinue
  - lib/zstd/decompress.c:ZSTD_decompressContinue
  - lib/zstd/decompress.c:ZSTD_decompressContinue
  - lib/zstd/decompress.c:ZSTD_decompressMultiFrame
  - lib/zstd/decompress.c:ZSTD_decompressMultiFrame
  - lib/zstd/decompress.c:ZSTD_decompressMultiFrame
  - lib/zstd/decompress.c:ZSTD_decodeLiteralsBlock
  - lib/zstd/decompress.c:ZSTD_findDecompressedSize
  - lib/zstd/decompress.c:ZSTD_findDecompressedSize
  - lib/zstd/decompress.c:ZSTD_findDecompressedSize
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
In lib/zstd/huf_decompress.c (0)
Location: lib/zstd/mem.h:87
Inline: True
```
```
In lib/zstd/decompress.c (ffffffff815d3cb7)
Location: lib/zstd/mem.h:87
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_getDictID_fromFrame
  - lib/zstd/decompress.c:ZSTD_getDictID_fromFrame
  - lib/zstd/decompress.c:ZSTD_getDictID_fromFrame
  - lib/zstd/decompress.c:ZSTD_getDictID_fromDDict
  - lib/zstd/decompress.c:ZSTD_getDictID_fromDDict
  - lib/zstd/decompress.c:ZSTD_initDDict
  - lib/zstd/decompress.c:ZSTD_initDDict
  - lib/zstd/decompress.c:ZSTD_loadEntropy
  - lib/zstd/decompress.c:ZSTD_decompressContinue
  - lib/zstd/decompress.c:ZSTD_decompressContinue
  - lib/zstd/decompress.c:ZSTD_decompressContinue
  - lib/zstd/decompress.c:ZSTD_decompressMultiFrame
  - lib/zstd/decompress.c:ZSTD_decompressMultiFrame
  - lib/zstd/decompress.c:ZSTD_decompressMultiFrame
  - lib/zstd/decompress.c:ZSTD_findFrameCompressedSize
  - lib/zstd/decompress.c:ZSTD_findFrameCompressedSize
  - lib/zstd/decompress.c:ZSTD_decodeLiteralsBlock
  - lib/zstd/decompress.c:ZSTD_findDecompressedSize
  - lib/zstd/decompress.c:ZSTD_findDecompressedSize
  - lib/zstd/decompress.c:ZSTD_findDecompressedSize
```
```
In lib/zstd/entropy_common.c (ffffffff815d836c)
Location: lib/zstd/mem.h:87
Inline: True
Inline callers:
  - lib/zstd/entropy_common.c:FSE_readNCount
  - lib/zstd/entropy_common.c:FSE_readNCount
  - lib/zstd/entropy_common.c:FSE_readNCount
  - lib/zstd/entropy_common.c:FSE_readNCount
```
```
In lib/zstd/fse_decompress.c (0)
Location: lib/zstd/mem.h:87
Inline: True
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
In lib/zstd/huf_decompress.c (0)
Location: lib/zstd/mem.h:87
Inline: True
```
```
In lib/zstd/decompress.c (ffffffff8163ea12)
Location: lib/zstd/mem.h:87
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_getDictID_fromFrame
  - lib/zstd/decompress.c:ZSTD_getDictID_fromFrame
  - lib/zstd/decompress.c:ZSTD_getDictID_fromFrame
  - lib/zstd/decompress.c:ZSTD_getDictID_fromDDict
  - lib/zstd/decompress.c:ZSTD_getDictID_fromDDict
  - lib/zstd/decompress.c:ZSTD_initDDict
  - lib/zstd/decompress.c:ZSTD_initDDict
  - lib/zstd/decompress.c:ZSTD_loadEntropy
  - lib/zstd/decompress.c:ZSTD_decompressContinue
  - lib/zstd/decompress.c:ZSTD_decompressContinue
  - lib/zstd/decompress.c:ZSTD_decompressContinue
  - lib/zstd/decompress.c:ZSTD_decompressMultiFrame
  - lib/zstd/decompress.c:ZSTD_decompressMultiFrame
  - lib/zstd/decompress.c:ZSTD_decompressMultiFrame
  - lib/zstd/decompress.c:ZSTD_findFrameCompressedSize
  - lib/zstd/decompress.c:ZSTD_findFrameCompressedSize
  - lib/zstd/decompress.c:ZSTD_decodeLiteralsBlock
  - lib/zstd/decompress.c:ZSTD_findDecompressedSize
  - lib/zstd/decompress.c:ZSTD_findDecompressedSize
  - lib/zstd/decompress.c:ZSTD_findDecompressedSize
  - lib/zstd/decompress.c:ZSTD_findDecompressedSize
```
```
In lib/zstd/entropy_common.c (ffffffff81643644)
Location: lib/zstd/mem.h:87
Inline: True
Inline callers:
  - lib/zstd/entropy_common.c:FSE_readNCount
  - lib/zstd/entropy_common.c:FSE_readNCount
  - lib/zstd/entropy_common.c:FSE_readNCount
  - lib/zstd/entropy_common.c:FSE_readNCount
```
```
In lib/zstd/fse_decompress.c (0)
Location: lib/zstd/mem.h:87
Inline: True
```
</details>
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
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/zstd/huf_decompress.c (0)
Location: lib/zstd/mem.h:87
Inline: True
```
```
In lib/zstd/decompress.c (ffff800010654eb8)
Location: lib/zstd/mem.h:87
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_getDictID_fromFrame
  - lib/zstd/decompress.c:ZSTD_getDictID_fromFrame
  - lib/zstd/decompress.c:ZSTD_getDictID_fromFrame
  - lib/zstd/decompress.c:ZSTD_getDictID_fromDDict
  - lib/zstd/decompress.c:ZSTD_getDictID_fromDDict
  - lib/zstd/decompress.c:ZSTD_initDDict
  - lib/zstd/decompress.c:ZSTD_initDDict
  - lib/zstd/decompress.c:ZSTD_loadEntropy
  - lib/zstd/decompress.c:ZSTD_decompressContinue
  - lib/zstd/decompress.c:ZSTD_decompressContinue
  - lib/zstd/decompress.c:ZSTD_decompressContinue
  - lib/zstd/decompress.c:ZSTD_decompressDCtx
  - lib/zstd/decompress.c:ZSTD_decompressDCtx
  - lib/zstd/decompress.c:ZSTD_decompressDCtx
  - lib/zstd/decompress.c:ZSTD_decompressBlock
  - lib/zstd/decompress.c:ZSTD_findDecompressedSize
  - lib/zstd/decompress.c:ZSTD_findDecompressedSize
  - lib/zstd/decompress.c:ZSTD_findDecompressedSize
```
```
In lib/zstd/entropy_common.c (ffff80001065a900)
Location: lib/zstd/mem.h:87
Inline: True
Inline callers:
  - lib/zstd/entropy_common.c:FSE_readNCount
  - lib/zstd/entropy_common.c:FSE_readNCount
  - lib/zstd/entropy_common.c:FSE_readNCount
  - lib/zstd/entropy_common.c:FSE_readNCount
```
```
In lib/zstd/fse_decompress.c (0)
Location: lib/zstd/mem.h:87
Inline: True
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
In lib/zstd/huf_decompress.c (c07faccc)
Location: lib/zstd/mem.h:87
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
  - lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal
```
```
In lib/zstd/decompress.c (c07ffee4)
Location: lib/zstd/mem.h:87
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_getDictID_fromFrame
  - lib/zstd/decompress.c:ZSTD_getDictID_fromFrame
  - lib/zstd/decompress.c:ZSTD_getDictID_fromFrame
  - lib/zstd/decompress.c:ZSTD_getDictID_fromDDict
  - lib/zstd/decompress.c:ZSTD_getDictID_fromDDict
  - lib/zstd/decompress.c:ZSTD_initDDict
  - lib/zstd/decompress.c:ZSTD_initDDict
  - lib/zstd/decompress.c:ZSTD_loadEntropy
  - lib/zstd/decompress.c:ZSTD_decompressContinue
  - lib/zstd/decompress.c:ZSTD_decompressContinue
  - lib/zstd/decompress.c:ZSTD_decompressContinue
  - lib/zstd/decompress.c:ZSTD_decompressDCtx
  - lib/zstd/decompress.c:ZSTD_decompressDCtx
  - lib/zstd/decompress.c:ZSTD_decompressDCtx
  - lib/zstd/decompress.c:ZSTD_decompressBlock
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_decompressSequences
  - lib/zstd/decompress.c:ZSTD_findDecompressedSize
  - lib/zstd/decompress.c:ZSTD_findDecompressedSize
  - lib/zstd/decompress.c:ZSTD_findDecompressedSize
```
```
In lib/zstd/entropy_common.c (c0803f18)
Location: lib/zstd/mem.h:87
Inline: True
Inline callers:
  - lib/zstd/entropy_common.c:FSE_readNCount
  - lib/zstd/entropy_common.c:FSE_readNCount
  - lib/zstd/entropy_common.c:FSE_readNCount
  - lib/zstd/entropy_common.c:FSE_readNCount
```
```
In lib/zstd/fse_decompress.c (c08044c8)
Location: lib/zstd/mem.h:87
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
In lib/zstd/huf_decompress.c (0)
Location: lib/zstd/mem.h:87
Inline: True
```
```
In lib/zstd/decompress.c (c000000000804d80)
Location: lib/zstd/mem.h:87
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_getDictID_fromFrame
  - lib/zstd/decompress.c:ZSTD_getDictID_fromFrame
  - lib/zstd/decompress.c:ZSTD_getDictID_fromFrame
  - lib/zstd/decompress.c:ZSTD_getDictID_fromDDict
  - lib/zstd/decompress.c:ZSTD_getDictID_fromDDict
  - lib/zstd/decompress.c:ZSTD_initDDict
  - lib/zstd/decompress.c:ZSTD_initDDict
  - lib/zstd/decompress.c:ZSTD_loadEntropy
  - lib/zstd/decompress.c:ZSTD_decompressContinue
  - lib/zstd/decompress.c:ZSTD_decompressContinue
  - lib/zstd/decompress.c:ZSTD_decompressContinue
  - lib/zstd/decompress.c:ZSTD_decompressDCtx
  - lib/zstd/decompress.c:ZSTD_decompressDCtx
  - lib/zstd/decompress.c:ZSTD_decompressDCtx
  - lib/zstd/decompress.c:ZSTD_decompressBlock
  - lib/zstd/decompress.c:ZSTD_findDecompressedSize
  - lib/zstd/decompress.c:ZSTD_findDecompressedSize
  - lib/zstd/decompress.c:ZSTD_findDecompressedSize
```
```
In lib/zstd/entropy_common.c (c00000000080b7d4)
Location: lib/zstd/mem.h:87
Inline: True
Inline callers:
  - lib/zstd/entropy_common.c:FSE_readNCount
  - lib/zstd/entropy_common.c:FSE_readNCount
  - lib/zstd/entropy_common.c:FSE_readNCount
  - lib/zstd/entropy_common.c:FSE_readNCount
```
```
In lib/zstd/fse_decompress.c (0)
Location: lib/zstd/mem.h:87
Inline: True
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
In lib/zstd/huf_decompress.c (0)
Location: lib/zstd/mem.h:87
Inline: True
```
```
In lib/zstd/decompress.c (ffffffe00048317a)
Location: lib/zstd/mem.h:87
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_getDictID_fromFrame
  - lib/zstd/decompress.c:ZSTD_getDictID_fromFrame
  - lib/zstd/decompress.c:ZSTD_getDictID_fromFrame
  - lib/zstd/decompress.c:ZSTD_getDictID_fromDDict
  - lib/zstd/decompress.c:ZSTD_getDictID_fromDDict
  - lib/zstd/decompress.c:ZSTD_initDDict
  - lib/zstd/decompress.c:ZSTD_initDDict
  - lib/zstd/decompress.c:ZSTD_loadEntropy
  - lib/zstd/decompress.c:ZSTD_decompressContinue
  - lib/zstd/decompress.c:ZSTD_decompressContinue
  - lib/zstd/decompress.c:ZSTD_decompressContinue
  - lib/zstd/decompress.c:ZSTD_decompressDCtx
  - lib/zstd/decompress.c:ZSTD_decompressDCtx
  - lib/zstd/decompress.c:ZSTD_decompressDCtx
  - lib/zstd/decompress.c:ZSTD_decompressBlock
  - lib/zstd/decompress.c:ZSTD_findDecompressedSize
  - lib/zstd/decompress.c:ZSTD_findDecompressedSize
  - lib/zstd/decompress.c:ZSTD_findDecompressedSize
```
```
In lib/zstd/entropy_common.c (ffffffe00048833e)
Location: lib/zstd/mem.h:87
Inline: True
Inline callers:
  - lib/zstd/entropy_common.c:FSE_readNCount
  - lib/zstd/entropy_common.c:FSE_readNCount
  - lib/zstd/entropy_common.c:FSE_readNCount
  - lib/zstd/entropy_common.c:FSE_readNCount
```
```
In lib/zstd/fse_decompress.c (0)
Location: lib/zstd/mem.h:87
Inline: True
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
In lib/zstd/huf_decompress.c (0)
Location: lib/zstd/mem.h:87
Inline: True
```
```
In lib/zstd/decompress.c (ffffffff815411d7)
Location: lib/zstd/mem.h:87
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_getDictID_fromFrame
  - lib/zstd/decompress.c:ZSTD_getDictID_fromFrame
  - lib/zstd/decompress.c:ZSTD_getDictID_fromFrame
  - lib/zstd/decompress.c:ZSTD_getDictID_fromDDict
  - lib/zstd/decompress.c:ZSTD_getDictID_fromDDict
  - lib/zstd/decompress.c:ZSTD_initDDict
  - lib/zstd/decompress.c:ZSTD_initDDict
  - lib/zstd/decompress.c:ZSTD_loadEntropy
  - lib/zstd/decompress.c:ZSTD_decompressContinue
  - lib/zstd/decompress.c:ZSTD_decompressContinue
  - lib/zstd/decompress.c:ZSTD_decompressContinue
  - lib/zstd/decompress.c:ZSTD_decompressDCtx
  - lib/zstd/decompress.c:ZSTD_decompressDCtx
  - lib/zstd/decompress.c:ZSTD_decompressDCtx
  - lib/zstd/decompress.c:ZSTD_decompressBlock
  - lib/zstd/decompress.c:ZSTD_findDecompressedSize
  - lib/zstd/decompress.c:ZSTD_findDecompressedSize
  - lib/zstd/decompress.c:ZSTD_findDecompressedSize
```
```
In lib/zstd/entropy_common.c (ffffffff81546da0)
Location: lib/zstd/mem.h:87
Inline: True
Inline callers:
  - lib/zstd/entropy_common.c:FSE_readNCount
  - lib/zstd/entropy_common.c:FSE_readNCount
  - lib/zstd/entropy_common.c:FSE_readNCount
  - lib/zstd/entropy_common.c:FSE_readNCount
```
```
In lib/zstd/fse_decompress.c (0)
Location: lib/zstd/mem.h:87
Inline: True
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
In lib/zstd/huf_decompress.c (0)
Location: lib/zstd/mem.h:87
Inline: True
```
```
In lib/zstd/decompress.c (ffffffff815314b7)
Location: lib/zstd/mem.h:87
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_getDictID_fromFrame
  - lib/zstd/decompress.c:ZSTD_getDictID_fromFrame
  - lib/zstd/decompress.c:ZSTD_getDictID_fromFrame
  - lib/zstd/decompress.c:ZSTD_getDictID_fromDDict
  - lib/zstd/decompress.c:ZSTD_getDictID_fromDDict
  - lib/zstd/decompress.c:ZSTD_initDDict
  - lib/zstd/decompress.c:ZSTD_initDDict
  - lib/zstd/decompress.c:ZSTD_loadEntropy
  - lib/zstd/decompress.c:ZSTD_decompressContinue
  - lib/zstd/decompress.c:ZSTD_decompressContinue
  - lib/zstd/decompress.c:ZSTD_decompressContinue
  - lib/zstd/decompress.c:ZSTD_decompressDCtx
  - lib/zstd/decompress.c:ZSTD_decompressDCtx
  - lib/zstd/decompress.c:ZSTD_decompressDCtx
  - lib/zstd/decompress.c:ZSTD_decompressBlock
  - lib/zstd/decompress.c:ZSTD_findDecompressedSize
  - lib/zstd/decompress.c:ZSTD_findDecompressedSize
  - lib/zstd/decompress.c:ZSTD_findDecompressedSize
```
```
In lib/zstd/entropy_common.c (ffffffff81537080)
Location: lib/zstd/mem.h:87
Inline: True
Inline callers:
  - lib/zstd/entropy_common.c:FSE_readNCount
  - lib/zstd/entropy_common.c:FSE_readNCount
  - lib/zstd/entropy_common.c:FSE_readNCount
  - lib/zstd/entropy_common.c:FSE_readNCount
```
```
In lib/zstd/fse_decompress.c (0)
Location: lib/zstd/mem.h:87
Inline: True
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
In lib/zstd/huf_decompress.c (0)
Location: lib/zstd/mem.h:87
Inline: True
```
```
In lib/zstd/decompress.c (ffffffff8153cf17)
Location: lib/zstd/mem.h:87
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_getDictID_fromFrame
  - lib/zstd/decompress.c:ZSTD_getDictID_fromFrame
  - lib/zstd/decompress.c:ZSTD_getDictID_fromFrame
  - lib/zstd/decompress.c:ZSTD_getDictID_fromDDict
  - lib/zstd/decompress.c:ZSTD_getDictID_fromDDict
  - lib/zstd/decompress.c:ZSTD_initDDict
  - lib/zstd/decompress.c:ZSTD_initDDict
  - lib/zstd/decompress.c:ZSTD_loadEntropy
  - lib/zstd/decompress.c:ZSTD_decompressContinue
  - lib/zstd/decompress.c:ZSTD_decompressContinue
  - lib/zstd/decompress.c:ZSTD_decompressContinue
  - lib/zstd/decompress.c:ZSTD_decompressDCtx
  - lib/zstd/decompress.c:ZSTD_decompressDCtx
  - lib/zstd/decompress.c:ZSTD_decompressDCtx
  - lib/zstd/decompress.c:ZSTD_decompressBlock
  - lib/zstd/decompress.c:ZSTD_findDecompressedSize
  - lib/zstd/decompress.c:ZSTD_findDecompressedSize
  - lib/zstd/decompress.c:ZSTD_findDecompressedSize
```
```
In lib/zstd/entropy_common.c (ffffffff81542ae0)
Location: lib/zstd/mem.h:87
Inline: True
Inline callers:
  - lib/zstd/entropy_common.c:FSE_readNCount
  - lib/zstd/entropy_common.c:FSE_readNCount
  - lib/zstd/entropy_common.c:FSE_readNCount
  - lib/zstd/entropy_common.c:FSE_readNCount
```
```
In lib/zstd/fse_decompress.c (0)
Location: lib/zstd/mem.h:87
Inline: True
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
In lib/zstd/huf_decompress.c (0)
Location: lib/zstd/mem.h:87
Inline: True
```
```
In lib/zstd/decompress.c (ffffffff81556d47)
Location: lib/zstd/mem.h:87
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_getDictID_fromFrame
  - lib/zstd/decompress.c:ZSTD_getDictID_fromFrame
  - lib/zstd/decompress.c:ZSTD_getDictID_fromFrame
  - lib/zstd/decompress.c:ZSTD_getDictID_fromDDict
  - lib/zstd/decompress.c:ZSTD_getDictID_fromDDict
  - lib/zstd/decompress.c:ZSTD_initDDict
  - lib/zstd/decompress.c:ZSTD_initDDict
  - lib/zstd/decompress.c:ZSTD_loadEntropy
  - lib/zstd/decompress.c:ZSTD_decompressContinue
  - lib/zstd/decompress.c:ZSTD_decompressContinue
  - lib/zstd/decompress.c:ZSTD_decompressContinue
  - lib/zstd/decompress.c:ZSTD_decompressDCtx
  - lib/zstd/decompress.c:ZSTD_decompressDCtx
  - lib/zstd/decompress.c:ZSTD_decompressDCtx
  - lib/zstd/decompress.c:ZSTD_decompressBlock
  - lib/zstd/decompress.c:ZSTD_findDecompressedSize
  - lib/zstd/decompress.c:ZSTD_findDecompressedSize
  - lib/zstd/decompress.c:ZSTD_findDecompressedSize
```
```
In lib/zstd/entropy_common.c (ffffffff8155c910)
Location: lib/zstd/mem.h:87
Inline: True
Inline callers:
  - lib/zstd/entropy_common.c:FSE_readNCount
  - lib/zstd/entropy_common.c:FSE_readNCount
  - lib/zstd/entropy_common.c:FSE_readNCount
  - lib/zstd/entropy_common.c:FSE_readNCount
```
```
In lib/zstd/fse_decompress.c (0)
Location: lib/zstd/mem.h:87
Inline: True
```
</details>
</li>
</ul>

## Differences
