# Function: <code>ZSTD_copySequencesToSeqStoreExplicitBlockDelim</code>

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
size_t ZSTD_copySequencesToSeqStoreExplicitBlockDelim(ZSTD_CCtx *cctx, ZSTD_sequencePosition *seqPos, const const ZSTD_Sequence * inSeqs, size_t inSeqsSize, const void *src, size_t blockSize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (0)
Location: lib/zstd/compress/zstd_compress.c:4479
Inline: False
```
**Symbols:**

```
ffffffff81712d50-ffffffff8171314f: ZSTD_copySequencesToSeqStoreExplicitBlockDelim (STB_LOCAL)
ffffffff81e96fa9-ffffffff81e96fdf: ZSTD_copySequencesToSeqStoreExplicitBlockDelim.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
size_t ZSTD_copySequencesToSeqStoreExplicitBlockDelim(ZSTD_CCtx *cctx, ZSTD_sequencePosition *seqPos, const const ZSTD_Sequence * inSeqs, size_t inSeqsSize, const void *src, size_t blockSize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (0)
Location: lib/zstd/compress/zstd_compress.c:5599
Inline: False
```
**Symbols:**

```
ffffffff81805a50-ffffffff81805f1c: ZSTD_copySequencesToSeqStoreExplicitBlockDelim (STB_LOCAL)
ffffffff8207db39-ffffffff8207db81: ZSTD_copySequencesToSeqStoreExplicitBlockDelim.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
size_t ZSTD_copySequencesToSeqStoreExplicitBlockDelim(ZSTD_CCtx *cctx, ZSTD_sequencePosition *seqPos, const const ZSTD_Sequence * inSeqs, size_t inSeqsSize, const void *src, size_t blockSize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (0)
Location: lib/zstd/compress/zstd_compress.c:5599
Inline: False
```
**Symbols:**

```
ffffffff81846440-ffffffff81846908: ZSTD_copySequencesToSeqStoreExplicitBlockDelim (STB_LOCAL)
ffffffff820fe0ec-ffffffff820fe134: ZSTD_copySequencesToSeqStoreExplicitBlockDelim.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
size_t ZSTD_copySequencesToSeqStoreExplicitBlockDelim(ZSTD_CCtx *cctx, ZSTD_sequencePosition *seqPos, const const ZSTD_Sequence * inSeqs, size_t inSeqsSize, const void *src, size_t blockSize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (0)
Location: lib/zstd/compress/zstd_compress.c:5599
Inline: False
```
**Symbols:**

```
ffffffff81898000-ffffffff818984c8: ZSTD_copySequencesToSeqStoreExplicitBlockDelim (STB_LOCAL)
ffffffff821dc259-ffffffff821dc2a1: ZSTD_copySequencesToSeqStoreExplicitBlockDelim.cold (STB_LOCAL)
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
