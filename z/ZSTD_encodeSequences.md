# Function: <code>ZSTD_encodeSequences</code>

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
<summary>In <code>5.19</code>: ✅</summary>

```c
size_t ZSTD_encodeSequences(void *dst, size_t dstCapacity, const FSE_CTable *CTable_MatchLength, const BYTE *mlCodeTable, const FSE_CTable *CTable_OffsetBits, const BYTE *ofCodeTable, const FSE_CTable *CTable_LitLength, const BYTE *llCodeTable, const seqDef *sequences, size_t nbSeq, int longOffsets, int bmi2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress_sequences.c (ffffffff8171f680)
Location: lib/zstd/compress/zstd_compress_sequences.c:416
Inline: False
```
**Symbols:**

```
ffffffff8171f680-ffffffff8171f6ff: ZSTD_encodeSequences (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
size_t ZSTD_encodeSequences(void *dst, size_t dstCapacity, const FSE_CTable *CTable_MatchLength, const BYTE *mlCodeTable, const FSE_CTable *CTable_OffsetBits, const BYTE *ofCodeTable, const FSE_CTable *CTable_LitLength, const BYTE *llCodeTable, const seqDef *sequences, size_t nbSeq, int longOffsets, int bmi2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress_sequences.c (ffffffff81814fc0)
Location: lib/zstd/compress/zstd_compress_sequences.c:419
Inline: False
```
**Symbols:**

```
ffffffff81814fc0-ffffffff8181503f: ZSTD_encodeSequences (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
size_t ZSTD_encodeSequences(void *dst, size_t dstCapacity, const FSE_CTable *CTable_MatchLength, const BYTE *mlCodeTable, const FSE_CTable *CTable_OffsetBits, const BYTE *ofCodeTable, const FSE_CTable *CTable_LitLength, const BYTE *llCodeTable, const seqDef *sequences, size_t nbSeq, int longOffsets, int bmi2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress_sequences.c (ffffffff818556d0)
Location: lib/zstd/compress/zstd_compress_sequences.c:419
Inline: False
```
**Symbols:**

```
ffffffff818556d0-ffffffff8185574f: ZSTD_encodeSequences (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
size_t ZSTD_encodeSequences(void *dst, size_t dstCapacity, const FSE_CTable *CTable_MatchLength, const BYTE *mlCodeTable, const FSE_CTable *CTable_OffsetBits, const BYTE *ofCodeTable, const FSE_CTable *CTable_LitLength, const BYTE *llCodeTable, const seqDef *sequences, size_t nbSeq, int longOffsets, int bmi2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress_sequences.c (ffffffff818a7290)
Location: lib/zstd/compress/zstd_compress_sequences.c:419
Inline: False
```
**Symbols:**

```
ffffffff818a7290-ffffffff818a730f: ZSTD_encodeSequences (STB_GLOBAL)
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
