# Function: <code>FSE_normalizeCount</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
size_t FSE_normalizeCount(short int *normalizedCounter, unsigned int tableLog, const unsigned int *count, size_t total, unsigned int maxSymbolValue);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/fse_compress.c (ffffffff815aca70)
Location: lib/zstd/fse_compress.c:608
Inline: False
Direct callers:
  - lib/zstd/huf_compress.c:HUF_compressWeights_wksp
  - lib/zstd/huf_compress.c:HUF_compressWeights_wksp
  - lib/zstd/compress.c:ZSTD_compressSequences_internal
  - lib/zstd/compress.c:ZSTD_compressSequences_internal
  - lib/zstd/compress.c:ZSTD_compressSequences_internal
```
**Symbols:**

```
ffffffff815aca70-ffffffff815ace48: FSE_normalizeCount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
size_t FSE_normalizeCount(short int *normalizedCounter, unsigned int tableLog, const unsigned int *count, size_t total, unsigned int maxSymbolValue);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/fse_compress.c (ffffffff815c85b0)
Location: lib/zstd/fse_compress.c:608
Inline: False
Direct callers:
  - lib/zstd/huf_compress.c:HUF_compressWeights_wksp
  - lib/zstd/huf_compress.c:HUF_compressWeights_wksp
  - lib/zstd/compress.c:ZSTD_compressSequences_internal
  - lib/zstd/compress.c:ZSTD_compressSequences_internal
  - lib/zstd/compress.c:ZSTD_compressSequences_internal
```
**Symbols:**

```
ffffffff815c85b0-ffffffff815c898d: FSE_normalizeCount (STB_GLOBAL)
```
</details>
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
size_t FSE_normalizeCount(short int *normalizedCounter, unsigned int tableLog, const unsigned int *count, size_t total, unsigned int maxSymbolValue, unsigned int useLowProbCount);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/fse_compress.c (ffffffff8170ea30)
Location: lib/zstd/compress/fse_compress.c:430
Inline: False
Direct callers:
  - lib/zstd/compress/huf_compress.c:HUF_writeCTable_wksp
  - lib/zstd/compress/zstd_compress_sequences.c:ZSTD_buildCTable
  - lib/zstd/compress/zstd_compress_sequences.c:ZSTD_NCountCost
```
**Symbols:**

```
ffffffff8170ea30-ffffffff8170ec5e: FSE_normalizeCount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
size_t FSE_normalizeCount(short int *normalizedCounter, unsigned int tableLog, const unsigned int *count, size_t total, unsigned int maxSymbolValue, unsigned int useLowProbCount);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/fse_compress.c (ffffffff817fda90)
Location: lib/zstd/compress/fse_compress.c:473
Inline: False
Direct callers:
  - lib/zstd/compress/huf_compress.c:HUF_writeCTable_wksp
  - lib/zstd/compress/zstd_compress_sequences.c:ZSTD_buildCTable
  - lib/zstd/compress/zstd_compress_sequences.c:ZSTD_NCountCost
```
**Symbols:**

```
ffffffff817fda90-ffffffff817fdcbe: FSE_normalizeCount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
size_t FSE_normalizeCount(short int *normalizedCounter, unsigned int tableLog, const unsigned int *count, size_t total, unsigned int maxSymbolValue, unsigned int useLowProbCount);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/fse_compress.c (ffffffff8183e2f0)
Location: lib/zstd/compress/fse_compress.c:473
Inline: False
Direct callers:
  - lib/zstd/compress/huf_compress.c:HUF_writeCTable_wksp
  - lib/zstd/compress/zstd_compress_sequences.c:ZSTD_buildCTable
  - lib/zstd/compress/zstd_compress_sequences.c:ZSTD_NCountCost
```
**Symbols:**

```
ffffffff8183e2f0-ffffffff8183e51e: FSE_normalizeCount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
size_t FSE_normalizeCount(short int *normalizedCounter, unsigned int tableLog, const unsigned int *count, size_t total, unsigned int maxSymbolValue, unsigned int useLowProbCount);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/fse_compress.c (ffffffff8188feb0)
Location: lib/zstd/compress/fse_compress.c:473
Inline: False
Direct callers:
  - lib/zstd/compress/huf_compress.c:HUF_writeCTable_wksp
  - lib/zstd/compress/zstd_compress_sequences.c:ZSTD_buildCTable
  - lib/zstd/compress/zstd_compress_sequences.c:ZSTD_NCountCost
```
**Symbols:**

```
ffffffff8188feb0-ffffffff818900de: FSE_normalizeCount (STB_GLOBAL)
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
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
