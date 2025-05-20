# Function: <code>FSE_optimalTableLog</code>

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
unsigned int FSE_optimalTableLog(unsigned int maxTableLog, size_t srcSize, unsigned int maxSymbolValue);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/fse_compress.c (ffffffff815aca10)
Location: lib/zstd/fse_compress.c:511
Inline: False
Direct callers:
  - lib/zstd/huf_compress.c:HUF_compressWeights_wksp
  - lib/zstd/compress.c:ZSTD_compressSequences_internal
  - lib/zstd/compress.c:ZSTD_compressSequences_internal
  - lib/zstd/compress.c:ZSTD_compressSequences_internal
```
**Symbols:**

```
ffffffff815aca10-ffffffff815aca6b: FSE_optimalTableLog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
unsigned int FSE_optimalTableLog(unsigned int maxTableLog, size_t srcSize, unsigned int maxSymbolValue);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/fse_compress.c (ffffffff815c8540)
Location: lib/zstd/fse_compress.c:511
Inline: False
Direct callers:
  - lib/zstd/huf_compress.c:HUF_compressWeights_wksp
  - lib/zstd/compress.c:ZSTD_compressSequences_internal
  - lib/zstd/compress.c:ZSTD_compressSequences_internal
  - lib/zstd/compress.c:ZSTD_compressSequences_internal
```
**Symbols:**

```
ffffffff815c8540-ffffffff815c85a5: FSE_optimalTableLog (STB_GLOBAL)
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
unsigned int FSE_optimalTableLog(unsigned int maxTableLog, size_t srcSize, unsigned int maxSymbolValue);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/fse_compress.c (ffffffff8170e9d0)
Location: lib/zstd/compress/fse_compress.c:336
Inline: False
Direct callers:
  - lib/zstd/compress/huf_compress.c:HUF_writeCTable_wksp
  - lib/zstd/compress/zstd_compress_sequences.c:ZSTD_buildCTable
  - lib/zstd/compress/zstd_compress_sequences.c:ZSTD_NCountCost
```
**Symbols:**

```
ffffffff8170e9d0-ffffffff8170ea2b: FSE_optimalTableLog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
unsigned int FSE_optimalTableLog(unsigned int maxTableLog, size_t srcSize, unsigned int maxSymbolValue);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/fse_compress.c (ffffffff817fda20)
Location: lib/zstd/compress/fse_compress.c:379
Inline: False
Direct callers:
  - lib/zstd/compress/huf_compress.c:HUF_writeCTable_wksp
  - lib/zstd/compress/zstd_compress_sequences.c:ZSTD_buildCTable
  - lib/zstd/compress/zstd_compress_sequences.c:ZSTD_NCountCost
```
**Symbols:**

```
ffffffff817fda20-ffffffff817fda7b: FSE_optimalTableLog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
unsigned int FSE_optimalTableLog(unsigned int maxTableLog, size_t srcSize, unsigned int maxSymbolValue);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/fse_compress.c (ffffffff8183e280)
Location: lib/zstd/compress/fse_compress.c:379
Inline: False
Direct callers:
  - lib/zstd/compress/huf_compress.c:HUF_writeCTable_wksp
  - lib/zstd/compress/zstd_compress_sequences.c:ZSTD_buildCTable
  - lib/zstd/compress/zstd_compress_sequences.c:ZSTD_NCountCost
```
**Symbols:**

```
ffffffff8183e280-ffffffff8183e2db: FSE_optimalTableLog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
unsigned int FSE_optimalTableLog(unsigned int maxTableLog, size_t srcSize, unsigned int maxSymbolValue);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/fse_compress.c (ffffffff8188fe40)
Location: lib/zstd/compress/fse_compress.c:379
Inline: False
Direct callers:
  - lib/zstd/compress/huf_compress.c:HUF_writeCTable_wksp
  - lib/zstd/compress/zstd_compress_sequences.c:ZSTD_buildCTable
  - lib/zstd/compress/zstd_compress_sequences.c:ZSTD_NCountCost
```
**Symbols:**

```
ffffffff8188fe40-ffffffff8188fe9b: FSE_optimalTableLog (STB_GLOBAL)
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
