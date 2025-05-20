# Function: <code>ZSTD_writeFrameHeader</code>

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
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/zstd/compress.c (ffffffff815afae0)
Location: lib/zstd/compress.c:2431
Inline: True
```
**Symbols:**

```
ffffffff815afae0-ffffffff815afc76: ZSTD_writeFrameHeader.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/zstd/compress.c (ffffffff815cb800)
Location: lib/zstd/compress.c:2431
Inline: True
```
**Symbols:**

```
ffffffff815cb800-ffffffff815cb99b: ZSTD_writeFrameHeader.isra.0 (STB_LOCAL)
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
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
size_t ZSTD_writeFrameHeader(void *dst, size_t dstCapacity, const ZSTD_CCtx_params *params, U64 pledgedSrcSize, U32 dictID);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (0)
Location: lib/zstd/compress/zstd_compress.c:2862
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressSequences
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressEnd
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressContinue_internal
```
**Symbols:**

```
ffffffff81711ba0-ffffffff81711d8c: ZSTD_writeFrameHeader (STB_LOCAL)
ffffffff81e96e63-ffffffff81e96e97: ZSTD_writeFrameHeader.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
size_t ZSTD_writeFrameHeader(void *dst, size_t dstCapacity, const ZSTD_CCtx_params *params, U64 pledgedSrcSize, U32 dictID);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (0)
Location: lib/zstd/compress/zstd_compress.c:3921
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressSequences
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressEnd
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressContinue_internal
```
**Symbols:**

```
ffffffff818047d0-ffffffff818049bc: ZSTD_writeFrameHeader (STB_LOCAL)
ffffffff8207d9d9-ffffffff8207da0d: ZSTD_writeFrameHeader.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
size_t ZSTD_writeFrameHeader(void *dst, size_t dstCapacity, const ZSTD_CCtx_params *params, U64 pledgedSrcSize, U32 dictID);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (0)
Location: lib/zstd/compress/zstd_compress.c:3921
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressSequences
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressEnd
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressContinue_internal
```
**Symbols:**

```
ffffffff818451c0-ffffffff818453b1: ZSTD_writeFrameHeader (STB_LOCAL)
ffffffff820fdf8c-ffffffff820fdfc0: ZSTD_writeFrameHeader.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
size_t ZSTD_writeFrameHeader(void *dst, size_t dstCapacity, const ZSTD_CCtx_params *params, U64 pledgedSrcSize, U32 dictID);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (0)
Location: lib/zstd/compress/zstd_compress.c:3921
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressSequences
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressEnd
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressContinue_internal
```
**Symbols:**

```
ffffffff81896d80-ffffffff81896f71: ZSTD_writeFrameHeader (STB_LOCAL)
ffffffff821dc0f9-ffffffff821dc12d: ZSTD_writeFrameHeader.cold (STB_LOCAL)
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
<b>Regular</b>
<ul>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
