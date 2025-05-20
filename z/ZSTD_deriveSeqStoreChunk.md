# Function: <code>ZSTD_deriveSeqStoreChunk</code>

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
void ZSTD_deriveSeqStoreChunk(seqStore_t *resultSeqStore, const seqStore_t *originalSeqStore, size_t startIdx, size_t endIdx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff81806530)
Location: lib/zstd/compress/zstd_compress.c:3308
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressBlock_splitBlock_internal
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressBlock_splitBlock_internal
  - lib/zstd/compress/zstd_compress.c:ZSTD_deriveBlockSplitsHelper
  - lib/zstd/compress/zstd_compress.c:ZSTD_deriveBlockSplitsHelper
  - lib/zstd/compress/zstd_compress.c:ZSTD_deriveBlockSplitsHelper
```
**Symbols:**

```
ffffffff81806530-ffffffff818066e0: ZSTD_deriveSeqStoreChunk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ZSTD_deriveSeqStoreChunk(seqStore_t *resultSeqStore, const seqStore_t *originalSeqStore, size_t startIdx, size_t endIdx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff81846f00)
Location: lib/zstd/compress/zstd_compress.c:3308
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressBlock_splitBlock_internal
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressBlock_splitBlock_internal
  - lib/zstd/compress/zstd_compress.c:ZSTD_deriveBlockSplitsHelper
  - lib/zstd/compress/zstd_compress.c:ZSTD_deriveBlockSplitsHelper
  - lib/zstd/compress/zstd_compress.c:ZSTD_deriveBlockSplitsHelper
```
**Symbols:**

```
ffffffff81846f00-ffffffff818470b0: ZSTD_deriveSeqStoreChunk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ZSTD_deriveSeqStoreChunk(seqStore_t *resultSeqStore, const seqStore_t *originalSeqStore, size_t startIdx, size_t endIdx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff81898ac0)
Location: lib/zstd/compress/zstd_compress.c:3308
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressBlock_splitBlock_internal
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressBlock_splitBlock_internal
  - lib/zstd/compress/zstd_compress.c:ZSTD_deriveBlockSplitsHelper
  - lib/zstd/compress/zstd_compress.c:ZSTD_deriveBlockSplitsHelper
  - lib/zstd/compress/zstd_compress.c:ZSTD_deriveBlockSplitsHelper
```
**Symbols:**

```
ffffffff81898ac0-ffffffff81898c70: ZSTD_deriveSeqStoreChunk (STB_LOCAL)
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
