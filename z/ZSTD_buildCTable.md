# Function: <code>ZSTD_buildCTable</code>

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
size_t ZSTD_buildCTable(void *dst, size_t dstCapacity, FSE_CTable *nextCTable, U32 FSELog, symbolEncodingType_e type, unsigned int *count, U32 max, const BYTE *codeTable, size_t nbSeq, const S16 *defaultNorm, U32 defaultNormLog, U32 defaultMax, const FSE_CTable *prevCTable, size_t prevCTableSize, void *entropyWorkspace, size_t entropyWorkspaceSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress_sequences.c (ffffffff8171f4e0)
Location: lib/zstd/compress/zstd_compress_sequences.c:241
Inline: False
```
**Symbols:**

```
ffffffff8171f4e0-ffffffff8171f67f: ZSTD_buildCTable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
size_t ZSTD_buildCTable(void *dst, size_t dstCapacity, FSE_CTable *nextCTable, U32 FSELog, symbolEncodingType_e type, unsigned int *count, U32 max, const BYTE *codeTable, size_t nbSeq, const S16 *defaultNorm, U32 defaultNormLog, U32 defaultMax, const FSE_CTable *prevCTable, size_t prevCTableSize, void *entropyWorkspace, size_t entropyWorkspaceSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress_sequences.c (ffffffff81814e10)
Location: lib/zstd/compress/zstd_compress_sequences.c:243
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_buildSequencesStatistics
  - lib/zstd/compress/zstd_compress.c:ZSTD_buildSequencesStatistics
  - lib/zstd/compress/zstd_compress.c:ZSTD_buildSequencesStatistics
```
**Symbols:**

```
ffffffff81814e10-ffffffff81814faf: ZSTD_buildCTable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
size_t ZSTD_buildCTable(void *dst, size_t dstCapacity, FSE_CTable *nextCTable, U32 FSELog, symbolEncodingType_e type, unsigned int *count, U32 max, const BYTE *codeTable, size_t nbSeq, const S16 *defaultNorm, U32 defaultNormLog, U32 defaultMax, const FSE_CTable *prevCTable, size_t prevCTableSize, void *entropyWorkspace, size_t entropyWorkspaceSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress_sequences.c (ffffffff81855520)
Location: lib/zstd/compress/zstd_compress_sequences.c:243
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_buildSequencesStatistics
  - lib/zstd/compress/zstd_compress.c:ZSTD_buildSequencesStatistics
  - lib/zstd/compress/zstd_compress.c:ZSTD_buildSequencesStatistics
```
**Symbols:**

```
ffffffff81855520-ffffffff818556bf: ZSTD_buildCTable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
size_t ZSTD_buildCTable(void *dst, size_t dstCapacity, FSE_CTable *nextCTable, U32 FSELog, symbolEncodingType_e type, unsigned int *count, U32 max, const BYTE *codeTable, size_t nbSeq, const S16 *defaultNorm, U32 defaultNormLog, U32 defaultMax, const FSE_CTable *prevCTable, size_t prevCTableSize, void *entropyWorkspace, size_t entropyWorkspaceSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress_sequences.c (ffffffff818a70e0)
Location: lib/zstd/compress/zstd_compress_sequences.c:243
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_buildSequencesStatistics
  - lib/zstd/compress/zstd_compress.c:ZSTD_buildSequencesStatistics
  - lib/zstd/compress/zstd_compress.c:ZSTD_buildSequencesStatistics
```
**Symbols:**

```
ffffffff818a70e0-ffffffff818a727f: ZSTD_buildCTable (STB_GLOBAL)
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
