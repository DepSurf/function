# Function: <code>ZSTD_buildBlockEntropyStats</code>

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
<summary>In <code>6.2</code>: ✅</summary>

```c
size_t ZSTD_buildBlockEntropyStats(seqStore_t *seqStorePtr, const ZSTD_entropyCTables_t *prevEntropy, ZSTD_entropyCTables_t *nextEntropy, const ZSTD_CCtx_params *cctxParams, ZSTD_entropyCTablesMetadata_t *entropyMetadata, void *workspace, size_t wkspSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff8180c5f0)
Location: lib/zstd/compress/zstd_compress.c:3120
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_buildEntropyStatisticsAndEstimateSubBlockSize
  - lib/zstd/compress/zstd_compress_superblock.c:ZSTD_compressSuperBlock
```
**Symbols:**

```
ffffffff8180c5f0-ffffffff8180c77c: ZSTD_buildBlockEntropyStats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
size_t ZSTD_buildBlockEntropyStats(seqStore_t *seqStorePtr, const ZSTD_entropyCTables_t *prevEntropy, ZSTD_entropyCTables_t *nextEntropy, const ZSTD_CCtx_params *cctxParams, ZSTD_entropyCTablesMetadata_t *entropyMetadata, void *workspace, size_t wkspSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff8184d090)
Location: lib/zstd/compress/zstd_compress.c:3120
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_buildEntropyStatisticsAndEstimateSubBlockSize
  - lib/zstd/compress/zstd_compress_superblock.c:ZSTD_compressSuperBlock
```
**Symbols:**

```
ffffffff8184d090-ffffffff8184d21e: ZSTD_buildBlockEntropyStats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
size_t ZSTD_buildBlockEntropyStats(seqStore_t *seqStorePtr, const ZSTD_entropyCTables_t *prevEntropy, ZSTD_entropyCTables_t *nextEntropy, const ZSTD_CCtx_params *cctxParams, ZSTD_entropyCTablesMetadata_t *entropyMetadata, void *workspace, size_t wkspSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff8189ec50)
Location: lib/zstd/compress/zstd_compress.c:3120
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_buildEntropyStatisticsAndEstimateSubBlockSize
  - lib/zstd/compress/zstd_compress_superblock.c:ZSTD_compressSuperBlock
```
**Symbols:**

```
ffffffff8189ec50-ffffffff8189edde: ZSTD_buildBlockEntropyStats (STB_GLOBAL)
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
