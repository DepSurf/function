# Function: <code>FSE_buildCTable_wksp</code>

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
size_t FSE_buildCTable_wksp(FSE_CTable *ct, const short int *normalizedCounter, unsigned int maxSymbolValue, unsigned int tableLog, void *workspace, size_t workspaceSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/fse_compress.c (ffffffff815ac220)
Location: lib/zstd/fse_compress.c:92
Inline: False
Direct callers:
  - lib/zstd/huf_compress.c:HUF_compressWeights_wksp
  - lib/zstd/huf_compress.c:HUF_compressWeights_wksp
  - lib/zstd/compress.c:ZSTD_loadZstdDictionary
  - lib/zstd/compress.c:ZSTD_loadZstdDictionary
  - lib/zstd/compress.c:ZSTD_loadZstdDictionary
  - lib/zstd/compress.c:ZSTD_compressSequences_internal
  - lib/zstd/compress.c:ZSTD_compressSequences_internal
  - lib/zstd/compress.c:ZSTD_compressSequences_internal
  - lib/zstd/compress.c:ZSTD_compressSequences_internal
  - lib/zstd/compress.c:ZSTD_compressSequences_internal
  - lib/zstd/compress.c:ZSTD_compressSequences_internal
```
**Symbols:**

```
ffffffff815ac220-ffffffff815ac44c: FSE_buildCTable_wksp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
size_t FSE_buildCTable_wksp(FSE_CTable *ct, const short int *normalizedCounter, unsigned int maxSymbolValue, unsigned int tableLog, void *workspace, size_t workspaceSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/fse_compress.c (ffffffff815c7d10)
Location: lib/zstd/fse_compress.c:92
Inline: False
Direct callers:
  - lib/zstd/huf_compress.c:HUF_compressWeights_wksp
  - lib/zstd/huf_compress.c:HUF_compressWeights_wksp
  - lib/zstd/compress.c:ZSTD_loadZstdDictionary
  - lib/zstd/compress.c:ZSTD_loadZstdDictionary
  - lib/zstd/compress.c:ZSTD_loadZstdDictionary
  - lib/zstd/compress.c:ZSTD_compressSequences_internal
  - lib/zstd/compress.c:ZSTD_compressSequences_internal
  - lib/zstd/compress.c:ZSTD_compressSequences_internal
  - lib/zstd/compress.c:ZSTD_compressSequences_internal
  - lib/zstd/compress.c:ZSTD_compressSequences_internal
  - lib/zstd/compress.c:ZSTD_compressSequences_internal
```
**Symbols:**

```
ffffffff815c7d10-ffffffff815c7f44: FSE_buildCTable_wksp (STB_GLOBAL)
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
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
size_t FSE_buildCTable_wksp(FSE_CTable *ct, const short int *normalizedCounter, unsigned int maxSymbolValue, unsigned int tableLog, void *workSpace, size_t wkspSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/zstd/compress/fse_compress.c (0)
Location: lib/zstd/compress/fse_compress.c:67
Inline: False
Direct callers:
  - lib/zstd/compress/huf_compress.c:HUF_writeCTable_wksp
  - lib/zstd/compress/zstd_compress.c:ZSTD_loadCEntropy
  - lib/zstd/compress/zstd_compress.c:ZSTD_loadCEntropy
  - lib/zstd/compress/zstd_compress.c:ZSTD_loadCEntropy
  - lib/zstd/compress/zstd_compress_sequences.c:ZSTD_buildCTable
  - lib/zstd/compress/zstd_compress_sequences.c:ZSTD_buildCTable
```
**Symbols:**

```
ffffffff81e9683a-ffffffff81e968ac: FSE_buildCTable_wksp.cold (STB_LOCAL)
ffffffff8170e570-ffffffff8170e870: FSE_buildCTable_wksp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
size_t FSE_buildCTable_wksp(FSE_CTable *ct, const short int *normalizedCounter, unsigned int maxSymbolValue, unsigned int tableLog, void *workSpace, size_t wkspSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/zstd/compress/fse_compress.c (0)
Location: lib/zstd/compress/fse_compress.c:67
Inline: False
Direct callers:
  - lib/zstd/compress/huf_compress.c:HUF_writeCTable_wksp
  - lib/zstd/compress/zstd_compress.c:ZSTD_loadCEntropy
  - lib/zstd/compress/zstd_compress.c:ZSTD_loadCEntropy
  - lib/zstd/compress/zstd_compress.c:ZSTD_loadCEntropy
  - lib/zstd/compress/zstd_compress_sequences.c:ZSTD_buildCTable
  - lib/zstd/compress/zstd_compress_sequences.c:ZSTD_buildCTable
```
**Symbols:**

```
ffffffff8207b568-ffffffff8207b6c2: FSE_buildCTable_wksp.cold (STB_LOCAL)
ffffffff817fd4f0-ffffffff817fd85b: FSE_buildCTable_wksp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
size_t FSE_buildCTable_wksp(FSE_CTable *ct, const short int *normalizedCounter, unsigned int maxSymbolValue, unsigned int tableLog, void *workSpace, size_t wkspSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/zstd/compress/fse_compress.c (0)
Location: lib/zstd/compress/fse_compress.c:67
Inline: False
Direct callers:
  - lib/zstd/compress/huf_compress.c:HUF_writeCTable_wksp
  - lib/zstd/compress/zstd_compress.c:ZSTD_loadCEntropy
  - lib/zstd/compress/zstd_compress.c:ZSTD_loadCEntropy
  - lib/zstd/compress/zstd_compress.c:ZSTD_loadCEntropy
  - lib/zstd/compress/zstd_compress_sequences.c:ZSTD_buildCTable
  - lib/zstd/compress/zstd_compress_sequences.c:ZSTD_buildCTable
```
**Symbols:**

```
ffffffff820fbb1f-ffffffff820fbc70: FSE_buildCTable_wksp.cold (STB_LOCAL)
ffffffff8183dd30-ffffffff8183e0b8: FSE_buildCTable_wksp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
size_t FSE_buildCTable_wksp(FSE_CTable *ct, const short int *normalizedCounter, unsigned int maxSymbolValue, unsigned int tableLog, void *workSpace, size_t wkspSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/zstd/compress/fse_compress.c (0)
Location: lib/zstd/compress/fse_compress.c:67
Inline: False
Direct callers:
  - lib/zstd/compress/huf_compress.c:HUF_writeCTable_wksp
  - lib/zstd/compress/zstd_compress.c:ZSTD_loadCEntropy
  - lib/zstd/compress/zstd_compress.c:ZSTD_loadCEntropy
  - lib/zstd/compress/zstd_compress.c:ZSTD_loadCEntropy
  - lib/zstd/compress/zstd_compress_sequences.c:ZSTD_buildCTable
  - lib/zstd/compress/zstd_compress_sequences.c:ZSTD_buildCTable
```
**Symbols:**

```
ffffffff821d9c8c-ffffffff821d9ddd: FSE_buildCTable_wksp.cold (STB_LOCAL)
ffffffff8188f8f0-ffffffff8188fc78: FSE_buildCTable_wksp (STB_GLOBAL)
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
