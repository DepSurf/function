# Function: <code>ZSTD_buildSequencesStatistics</code>

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
ZSTD_symbolEncodingTypeStats_t ZSTD_buildSequencesStatistics(seqStore_t *seqStorePtr, size_t nbSeq, const ZSTD_fseCTables_t *prevEntropy, ZSTD_fseCTables_t *nextEntropy, BYTE *dst, const const BYTE * dstEnd, ZSTD_strategy strategy, unsigned int *countWorkspace, void *entropyWorkspace, size_t entropyWkspSize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff8180b1b0)
Location: lib/zstd/compress/zstd_compress.c:2360
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_buildBlockEntropyStats
```
**Symbols:**

```
ffffffff8180b1b0-ffffffff8180b55c: ZSTD_buildSequencesStatistics (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ZSTD_symbolEncodingTypeStats_t ZSTD_buildSequencesStatistics(seqStore_t *seqStorePtr, size_t nbSeq, const ZSTD_fseCTables_t *prevEntropy, ZSTD_fseCTables_t *nextEntropy, BYTE *dst, const const BYTE * dstEnd, ZSTD_strategy strategy, unsigned int *countWorkspace, void *entropyWorkspace, size_t entropyWkspSize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff8184bc50)
Location: lib/zstd/compress/zstd_compress.c:2360
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_buildBlockEntropyStats
```
**Symbols:**

```
ffffffff8184bc50-ffffffff8184bffc: ZSTD_buildSequencesStatistics (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ZSTD_symbolEncodingTypeStats_t ZSTD_buildSequencesStatistics(seqStore_t *seqStorePtr, size_t nbSeq, const ZSTD_fseCTables_t *prevEntropy, ZSTD_fseCTables_t *nextEntropy, BYTE *dst, const const BYTE * dstEnd, ZSTD_strategy strategy, unsigned int *countWorkspace, void *entropyWorkspace, size_t entropyWkspSize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff8189d810)
Location: lib/zstd/compress/zstd_compress.c:2360
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_buildBlockEntropyStats
```
**Symbols:**

```
ffffffff8189d810-ffffffff8189dbbc: ZSTD_buildSequencesStatistics (STB_LOCAL)
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
