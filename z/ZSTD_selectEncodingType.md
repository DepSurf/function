# Function: <code>ZSTD_selectEncodingType</code>

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
symbolEncodingType_e ZSTD_selectEncodingType(FSE_repeat *repeatMode, const unsigned int *count, const unsigned int max, const size_t mostFrequent, size_t nbSeq, const unsigned int FSELog, const FSE_CTable *prevCTable, const short int *defaultNorm, U32 defaultNormLog, const ZSTD_defaultPolicy_e isDefaultAllowed, const ZSTD_strategy strategy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/zstd/compress/zstd_compress_sequences.c (0)
Location: lib/zstd/compress/zstd_compress_sequences.c:155
Inline: False
```
**Symbols:**

```
ffffffff81e98a65-ffffffff81e98a9a: ZSTD_selectEncodingType.cold (STB_LOCAL)
ffffffff8171f260-ffffffff8171f4d8: ZSTD_selectEncodingType (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
symbolEncodingType_e ZSTD_selectEncodingType(FSE_repeat *repeatMode, const unsigned int *count, const unsigned int max, const size_t mostFrequent, size_t nbSeq, const unsigned int FSELog, const FSE_CTable *prevCTable, const short int *defaultNorm, U32 defaultNormLog, const ZSTD_defaultPolicy_e isDefaultAllowed, const ZSTD_strategy strategy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/zstd/compress/zstd_compress_sequences.c (0)
Location: lib/zstd/compress/zstd_compress_sequences.c:157
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_buildSequencesStatistics
  - lib/zstd/compress/zstd_compress.c:ZSTD_buildSequencesStatistics
  - lib/zstd/compress/zstd_compress.c:ZSTD_buildSequencesStatistics
```
**Symbols:**

```
ffffffff8207f758-ffffffff8207f78d: ZSTD_selectEncodingType.cold (STB_LOCAL)
ffffffff81814b80-ffffffff81814df8: ZSTD_selectEncodingType (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
symbolEncodingType_e ZSTD_selectEncodingType(FSE_repeat *repeatMode, const unsigned int *count, const unsigned int max, const size_t mostFrequent, size_t nbSeq, const unsigned int FSELog, const FSE_CTable *prevCTable, const short int *defaultNorm, U32 defaultNormLog, const ZSTD_defaultPolicy_e isDefaultAllowed, const ZSTD_strategy strategy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/zstd/compress/zstd_compress_sequences.c (0)
Location: lib/zstd/compress/zstd_compress_sequences.c:157
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_buildSequencesStatistics
  - lib/zstd/compress/zstd_compress.c:ZSTD_buildSequencesStatistics
  - lib/zstd/compress/zstd_compress.c:ZSTD_buildSequencesStatistics
```
**Symbols:**

```
ffffffff820ffa59-ffffffff820ffa9b: ZSTD_selectEncodingType.cold (STB_LOCAL)
ffffffff81855280-ffffffff81855501: ZSTD_selectEncodingType (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
symbolEncodingType_e ZSTD_selectEncodingType(FSE_repeat *repeatMode, const unsigned int *count, const unsigned int max, const size_t mostFrequent, size_t nbSeq, const unsigned int FSELog, const FSE_CTable *prevCTable, const short int *defaultNorm, U32 defaultNormLog, const ZSTD_defaultPolicy_e isDefaultAllowed, const ZSTD_strategy strategy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/zstd/compress/zstd_compress_sequences.c (0)
Location: lib/zstd/compress/zstd_compress_sequences.c:157
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_buildSequencesStatistics
  - lib/zstd/compress/zstd_compress.c:ZSTD_buildSequencesStatistics
  - lib/zstd/compress/zstd_compress.c:ZSTD_buildSequencesStatistics
```
**Symbols:**

```
ffffffff821ddbc6-ffffffff821ddc08: ZSTD_selectEncodingType.cold (STB_LOCAL)
ffffffff818a6e40-ffffffff818a70c1: ZSTD_selectEncodingType (STB_GLOBAL)
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
