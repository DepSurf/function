# Function: <code>ZSTD_copySequencesToSeqStoreNoBlockDelim</code>

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
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
size_t ZSTD_copySequencesToSeqStoreNoBlockDelim(ZSTD_CCtx *cctx, ZSTD_sequencePosition *seqPos, const const ZSTD_Sequence * inSeqs, size_t inSeqsSize, const void *src, size_t blockSize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (0)
Location: lib/zstd/compress/zstd_compress.c:4544
Inline: False
```
**Symbols:**

```
ffffffff81712550-ffffffff81712a7d: ZSTD_copySequencesToSeqStoreNoBlockDelim (STB_LOCAL)
ffffffff81e96f5f-ffffffff81e96fa9: ZSTD_copySequencesToSeqStoreNoBlockDelim.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
size_t ZSTD_copySequencesToSeqStoreNoBlockDelim(ZSTD_CCtx *cctx, ZSTD_sequencePosition *seqPos, const const ZSTD_Sequence * inSeqs, size_t inSeqsSize, const void *src, size_t blockSize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (0)
Location: lib/zstd/compress/zstd_compress.c:5662
Inline: False
```
**Symbols:**

```
ffffffff81805050-ffffffff81805628: ZSTD_copySequencesToSeqStoreNoBlockDelim (STB_LOCAL)
ffffffff8207daf1-ffffffff8207db39: ZSTD_copySequencesToSeqStoreNoBlockDelim.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
size_t ZSTD_copySequencesToSeqStoreNoBlockDelim(ZSTD_CCtx *cctx, ZSTD_sequencePosition *seqPos, const const ZSTD_Sequence * inSeqs, size_t inSeqsSize, const void *src, size_t blockSize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (0)
Location: lib/zstd/compress/zstd_compress.c:5662
Inline: False
```
**Symbols:**

```
ffffffff81845a60-ffffffff8184600e: ZSTD_copySequencesToSeqStoreNoBlockDelim (STB_LOCAL)
ffffffff820fe0a4-ffffffff820fe0ec: ZSTD_copySequencesToSeqStoreNoBlockDelim.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
size_t ZSTD_copySequencesToSeqStoreNoBlockDelim(ZSTD_CCtx *cctx, ZSTD_sequencePosition *seqPos, const const ZSTD_Sequence * inSeqs, size_t inSeqsSize, const void *src, size_t blockSize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (0)
Location: lib/zstd/compress/zstd_compress.c:5662
Inline: False
```
**Symbols:**

```
ffffffff81897620-ffffffff81897bce: ZSTD_copySequencesToSeqStoreNoBlockDelim (STB_LOCAL)
ffffffff821dc211-ffffffff821dc259: ZSTD_copySequencesToSeqStoreNoBlockDelim.cold (STB_LOCAL)
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
