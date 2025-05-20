# Function: <code>HUF_readCTable</code>

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
size_t HUF_readCTable(HUF_CElt *CTable, unsigned int *maxSymbolValuePtr, const void *src, size_t srcSize, unsigned int *hasZeroWeights);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/zstd/compress/huf_compress.c (0)
Location: lib/zstd/compress/huf_compress.c:160
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_loadCEntropy
```
**Symbols:**

```
ffffffff81e96dc1-ffffffff81e96e0f: HUF_readCTable.cold (STB_LOCAL)
ffffffff817105d0-ffffffff81710b42: HUF_readCTable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
size_t HUF_readCTable(HUF_CElt *CTable, unsigned int *maxSymbolValuePtr, const void *src, size_t srcSize, unsigned int *hasZeroWeights);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/zstd/compress/huf_compress.c (0)
Location: lib/zstd/compress/huf_compress.c:218
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_loadCEntropy
```
**Symbols:**

```
ffffffff8207d8d2-ffffffff8207d960: HUF_readCTable.cold (STB_LOCAL)
ffffffff81802da0-ffffffff8180336b: HUF_readCTable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
size_t HUF_readCTable(HUF_CElt *CTable, unsigned int *maxSymbolValuePtr, const void *src, size_t srcSize, unsigned int *hasZeroWeights);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/zstd/compress/huf_compress.c (0)
Location: lib/zstd/compress/huf_compress.c:218
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_loadCEntropy
```
**Symbols:**

```
ffffffff820fde8c-ffffffff820fdf13: HUF_readCTable.cold (STB_LOCAL)
ffffffff818437a0-ffffffff81843d59: HUF_readCTable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
size_t HUF_readCTable(HUF_CElt *CTable, unsigned int *maxSymbolValuePtr, const void *src, size_t srcSize, unsigned int *hasZeroWeights);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/zstd/compress/huf_compress.c (0)
Location: lib/zstd/compress/huf_compress.c:218
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_loadCEntropy
```
**Symbols:**

```
ffffffff821dbff9-ffffffff821dc080: HUF_readCTable.cold (STB_LOCAL)
ffffffff81895360-ffffffff81895919: HUF_readCTable (STB_GLOBAL)
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
