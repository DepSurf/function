# Function: <code>ZSTD_encodeSequences_default</code>

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
size_t ZSTD_encodeSequences_default(void *dst, size_t dstCapacity, const FSE_CTable *CTable_MatchLength, const BYTE *mlCodeTable, const FSE_CTable *CTable_OffsetBits, const BYTE *ofCodeTable, const FSE_CTable *CTable_LitLength, const BYTE *llCodeTable, const seqDef *sequences, size_t nbSeq, int longOffsets);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/zstd/compress/zstd_compress_sequences.c (0)
Location: lib/zstd/compress/zstd_compress_sequences.c:382
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress_sequences.c:ZSTD_encodeSequences
```
**Symbols:**

```
ffffffff8171dfc0-ffffffff8171f025: ZSTD_encodeSequences_default (STB_LOCAL)
ffffffff81e97f94-ffffffff81e98970: ZSTD_encodeSequences_default.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
size_t ZSTD_encodeSequences_default(void *dst, size_t dstCapacity, const FSE_CTable *CTable_MatchLength, const BYTE *mlCodeTable, const FSE_CTable *CTable_OffsetBits, const BYTE *ofCodeTable, const FSE_CTable *CTable_LitLength, const BYTE *llCodeTable, const seqDef *sequences, size_t nbSeq, int longOffsets);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/zstd/compress/zstd_compress_sequences.c (0)
Location: lib/zstd/compress/zstd_compress_sequences.c:385
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress_sequences.c:ZSTD_encodeSequences
```
**Symbols:**

```
ffffffff81813890-ffffffff81814918: ZSTD_encodeSequences_default (STB_LOCAL)
ffffffff8207eb25-ffffffff8207f663: ZSTD_encodeSequences_default.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
size_t ZSTD_encodeSequences_default(void *dst, size_t dstCapacity, const FSE_CTable *CTable_MatchLength, const BYTE *mlCodeTable, const FSE_CTable *CTable_OffsetBits, const BYTE *ofCodeTable, const FSE_CTable *CTable_LitLength, const BYTE *llCodeTable, const seqDef *sequences, size_t nbSeq, int longOffsets);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/zstd/compress/zstd_compress_sequences.c (0)
Location: lib/zstd/compress/zstd_compress_sequences.c:385
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress_sequences.c:ZSTD_encodeSequences
```
**Symbols:**

```
ffffffff818541f0-ffffffff81855036: ZSTD_encodeSequences_default (STB_LOCAL)
ffffffff820ff06d-ffffffff820ff96a: ZSTD_encodeSequences_default.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
size_t ZSTD_encodeSequences_default(void *dst, size_t dstCapacity, const FSE_CTable *CTable_MatchLength, const BYTE *mlCodeTable, const FSE_CTable *CTable_OffsetBits, const BYTE *ofCodeTable, const FSE_CTable *CTable_LitLength, const BYTE *llCodeTable, const seqDef *sequences, size_t nbSeq, int longOffsets);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/zstd/compress/zstd_compress_sequences.c (0)
Location: lib/zstd/compress/zstd_compress_sequences.c:385
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress_sequences.c:ZSTD_encodeSequences
```
**Symbols:**

```
ffffffff818a5db0-ffffffff818a6bf6: ZSTD_encodeSequences_default (STB_LOCAL)
ffffffff821dd1da-ffffffff821ddad7: ZSTD_encodeSequences_default.cold (STB_LOCAL)
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
