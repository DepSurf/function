# Function: <code>FSE_writeNCount</code>

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
size_t FSE_writeNCount(void *buffer, size_t bufferSize, const short int *normalizedCounter, unsigned int maxSymbolValue, unsigned int tableLog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/fse_compress.c (ffffffff815ac470)
Location: lib/zstd/fse_compress.c:301
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
ffffffff815ac470-ffffffff815ac4c1: FSE_writeNCount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
size_t FSE_writeNCount(void *buffer, size_t bufferSize, const short int *normalizedCounter, unsigned int maxSymbolValue, unsigned int tableLog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/fse_compress.c (ffffffff815c7f70)
Location: lib/zstd/fse_compress.c:301
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
ffffffff815c7f70-ffffffff815c7fc6: FSE_writeNCount (STB_GLOBAL)
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
size_t FSE_writeNCount(void *buffer, size_t bufferSize, const short int *normalizedCounter, unsigned int maxSymbolValue, unsigned int tableLog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/fse_compress.c (ffffffff8170e8a0)
Location: lib/zstd/compress/fse_compress.c:285
Inline: False
Direct callers:
  - lib/zstd/compress/huf_compress.c:HUF_writeCTable_wksp
  - lib/zstd/compress/zstd_compress_sequences.c:ZSTD_buildCTable
  - lib/zstd/compress/zstd_compress_sequences.c:ZSTD_NCountCost
```
**Symbols:**

```
ffffffff8170e8a0-ffffffff8170e92c: FSE_writeNCount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
size_t FSE_writeNCount(void *buffer, size_t bufferSize, const short int *normalizedCounter, unsigned int maxSymbolValue, unsigned int tableLog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/fse_compress.c (ffffffff817fd8b0)
Location: lib/zstd/compress/fse_compress.c:328
Inline: False
Direct callers:
  - lib/zstd/compress/huf_compress.c:HUF_writeCTable_wksp
  - lib/zstd/compress/zstd_compress_sequences.c:ZSTD_buildCTable
  - lib/zstd/compress/zstd_compress_sequences.c:ZSTD_NCountCost
```
**Symbols:**

```
ffffffff817fd8b0-ffffffff817fd93f: FSE_writeNCount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
size_t FSE_writeNCount(void *buffer, size_t bufferSize, const short int *normalizedCounter, unsigned int maxSymbolValue, unsigned int tableLog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/fse_compress.c (ffffffff8183e110)
Location: lib/zstd/compress/fse_compress.c:328
Inline: False
Direct callers:
  - lib/zstd/compress/huf_compress.c:HUF_writeCTable_wksp
  - lib/zstd/compress/zstd_compress_sequences.c:ZSTD_buildCTable
  - lib/zstd/compress/zstd_compress_sequences.c:ZSTD_NCountCost
```
**Symbols:**

```
ffffffff8183e110-ffffffff8183e19f: FSE_writeNCount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
size_t FSE_writeNCount(void *buffer, size_t bufferSize, const short int *normalizedCounter, unsigned int maxSymbolValue, unsigned int tableLog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/fse_compress.c (ffffffff8188fcd0)
Location: lib/zstd/compress/fse_compress.c:328
Inline: False
Direct callers:
  - lib/zstd/compress/huf_compress.c:HUF_writeCTable_wksp
  - lib/zstd/compress/zstd_compress_sequences.c:ZSTD_buildCTable
  - lib/zstd/compress/zstd_compress_sequences.c:ZSTD_NCountCost
```
**Symbols:**

```
ffffffff8188fcd0-ffffffff8188fd5f: FSE_writeNCount (STB_GLOBAL)
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
