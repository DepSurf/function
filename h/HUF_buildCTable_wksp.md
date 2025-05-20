# Function: <code>HUF_buildCTable_wksp</code>

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
size_t HUF_buildCTable_wksp(HUF_CElt *tree, const U32 *count, U32 maxSymbolValue, U32 maxNbBits, void *workSpace, size_t wkspSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/huf_compress.c (ffffffff815ae1a0)
Location: lib/zstd/huf_compress.c:420
Inline: False
Direct callers:
  - lib/zstd/huf_compress.c:HUF_compress4X_wksp
  - lib/zstd/huf_compress.c:HUF_compress4X_wksp
  - lib/zstd/huf_compress.c:HUF_compress1X_wksp
  - lib/zstd/huf_compress.c:HUF_compress1X_wksp
  - lib/zstd/huf_compress.c:HUF_compress_internal
  - lib/zstd/huf_compress.c:HUF_compress_internal
```
**Symbols:**

```
ffffffff815ae1a0-ffffffff815ae5bc: HUF_buildCTable_wksp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
size_t HUF_buildCTable_wksp(HUF_CElt *tree, const U32 *count, U32 maxSymbolValue, U32 maxNbBits, void *workSpace, size_t wkspSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/huf_compress.c (ffffffff815c9d00)
Location: lib/zstd/huf_compress.c:420
Inline: False
Direct callers:
  - lib/zstd/huf_compress.c:HUF_compress4X_wksp
  - lib/zstd/huf_compress.c:HUF_compress4X_wksp
  - lib/zstd/huf_compress.c:HUF_compress1X_wksp
  - lib/zstd/huf_compress.c:HUF_compress1X_wksp
  - lib/zstd/huf_compress.c:HUF_compress_internal
  - lib/zstd/huf_compress.c:HUF_compress_internal
```
**Symbols:**

```
ffffffff815c9d00-ffffffff815ca124: HUF_buildCTable_wksp (STB_GLOBAL)
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
size_t HUF_buildCTable_wksp(HUF_CElt *tree, const unsigned int *count, U32 maxSymbolValue, U32 maxNbBits, void *workSpace, size_t wkspSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/huf_compress.c (ffffffff81710b70)
Location: lib/zstd/compress/huf_compress.c:510
Inline: False
Direct callers:
  - lib/zstd/compress/huf_compress.c:HUF_compress_internal
```
**Symbols:**

```
ffffffff81710b70-ffffffff81710eff: HUF_buildCTable_wksp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
size_t HUF_buildCTable_wksp(HUF_CElt *CTable, const unsigned int *count, U32 maxSymbolValue, U32 maxNbBits, void *workSpace, size_t wkspSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/zstd/compress/huf_compress.c (0)
Location: lib/zstd/compress/huf_compress.c:677
Inline: False
Direct callers:
  - lib/zstd/compress/huf_compress.c:HUF_compress_internal
  - lib/zstd/compress/zstd_compress.c:ZSTD_buildBlockEntropyStats_literals
```
**Symbols:**

```
ffffffff8207d960-ffffffff8207d985: HUF_buildCTable_wksp.cold (STB_LOCAL)
ffffffff818033b0-ffffffff818037a5: HUF_buildCTable_wksp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
size_t HUF_buildCTable_wksp(HUF_CElt *CTable, const unsigned int *count, U32 maxSymbolValue, U32 maxNbBits, void *workSpace, size_t wkspSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/zstd/compress/huf_compress.c (0)
Location: lib/zstd/compress/huf_compress.c:677
Inline: False
Direct callers:
  - lib/zstd/compress/huf_compress.c:HUF_compress_internal
  - lib/zstd/compress/zstd_compress.c:ZSTD_buildBlockEntropyStats_literals
```
**Symbols:**

```
ffffffff820fdf13-ffffffff820fdf38: HUF_buildCTable_wksp.cold (STB_LOCAL)
ffffffff81843da0-ffffffff81844195: HUF_buildCTable_wksp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
size_t HUF_buildCTable_wksp(HUF_CElt *CTable, const unsigned int *count, U32 maxSymbolValue, U32 maxNbBits, void *workSpace, size_t wkspSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/zstd/compress/huf_compress.c (0)
Location: lib/zstd/compress/huf_compress.c:677
Inline: False
Direct callers:
  - lib/zstd/compress/huf_compress.c:HUF_compress_internal
  - lib/zstd/compress/zstd_compress.c:ZSTD_buildBlockEntropyStats_literals
```
**Symbols:**

```
ffffffff821dc080-ffffffff821dc0a5: HUF_buildCTable_wksp.cold (STB_LOCAL)
ffffffff81895960-ffffffff81895d55: HUF_buildCTable_wksp (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>HUF_CElt *CTable</code>
</li>
<li>
<b>Param removed. </b>
<code>HUF_CElt *tree</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
