# Function: <code>ZSTD_compressSeqStore_singleBlock</code>

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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
size_t ZSTD_compressSeqStore_singleBlock(ZSTD_CCtx *zc, const seqStore_t * seqStore, const repcodes_t * dRep, const repcodes_t * cRep, void *dst, size_t dstCapacity, const void *src, size_t srcSize, U32 lastBlock, U32 isPartition);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (0)
Location: lib/zstd/compress/zstd_compress.c:3407
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressBlock_splitBlock_internal
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressBlock_splitBlock_internal
```
**Symbols:**

```
ffffffff8180b8b0-ffffffff8180bcef: ZSTD_compressSeqStore_singleBlock (STB_LOCAL)
ffffffff8207df17-ffffffff8207df3c: ZSTD_compressSeqStore_singleBlock.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
size_t ZSTD_compressSeqStore_singleBlock(ZSTD_CCtx *zc, const seqStore_t * seqStore, const repcodes_t * dRep, const repcodes_t * cRep, void *dst, size_t dstCapacity, const void *src, size_t srcSize, U32 lastBlock, U32 isPartition);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (0)
Location: lib/zstd/compress/zstd_compress.c:3407
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressBlock_splitBlock_internal
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressBlock_splitBlock_internal
```
**Symbols:**

```
ffffffff8184c340-ffffffff8184c797: ZSTD_compressSeqStore_singleBlock (STB_LOCAL)
ffffffff820fe48e-ffffffff820fe4b3: ZSTD_compressSeqStore_singleBlock.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
size_t ZSTD_compressSeqStore_singleBlock(ZSTD_CCtx *zc, const seqStore_t * seqStore, const repcodes_t * dRep, const repcodes_t * cRep, void *dst, size_t dstCapacity, const void *src, size_t srcSize, U32 lastBlock, U32 isPartition);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (0)
Location: lib/zstd/compress/zstd_compress.c:3407
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressBlock_splitBlock_internal
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressBlock_splitBlock_internal
```
**Symbols:**

```
ffffffff8189df00-ffffffff8189e357: ZSTD_compressSeqStore_singleBlock (STB_LOCAL)
ffffffff821dc5fb-ffffffff821dc620: ZSTD_compressSeqStore_singleBlock.cold (STB_LOCAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
