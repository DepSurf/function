# Function: <code>HUF_readStats_wksp</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
size_t HUF_readStats_wksp(BYTE *huffWeight, size_t hwSize, U32 *rankStats, U32 *nbSymbolsPtr, U32 *tableLogPtr, const void *src, size_t srcSize, void *workspace, size_t workspaceSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/entropy_common.c (ffffffff814b9330)
Location: lib/zstd/entropy_common.c:167
Inline: False
```
**Symbols:**

```
ffffffff814b9330-ffffffff814b94ff: HUF_readStats_wksp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
size_t HUF_readStats_wksp(BYTE *huffWeight, size_t hwSize, U32 *rankStats, U32 *nbSymbolsPtr, U32 *tableLogPtr, const void *src, size_t srcSize, void *workspace, size_t workspaceSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/entropy_common.c (ffffffff814ebb80)
Location: lib/zstd/entropy_common.c:167
Inline: False
Direct callers:
  - lib/zstd/huf_decompress.c:HUF_readDTableX4_wksp
  - lib/zstd/huf_decompress.c:HUF_readDTableX2_wksp
```
**Symbols:**

```
ffffffff814ebb80-ffffffff814ebd62: HUF_readStats_wksp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
size_t HUF_readStats_wksp(BYTE *huffWeight, size_t hwSize, U32 *rankStats, U32 *nbSymbolsPtr, U32 *tableLogPtr, const void *src, size_t srcSize, void *workspace, size_t workspaceSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/entropy_common.c (ffffffff814ff8d0)
Location: lib/zstd/entropy_common.c:167
Inline: False
Direct callers:
  - lib/zstd/huf_decompress.c:HUF_readDTableX4_wksp
  - lib/zstd/huf_decompress.c:HUF_readDTableX2_wksp
```
**Symbols:**

```
ffffffff814ff8d0-ffffffff814ffab2: HUF_readStats_wksp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
size_t HUF_readStats_wksp(BYTE *huffWeight, size_t hwSize, U32 *rankStats, U32 *nbSymbolsPtr, U32 *tableLogPtr, const void *src, size_t srcSize, void *workspace, size_t workspaceSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/entropy_common.c (ffffffff8152da90)
Location: lib/zstd/entropy_common.c:167
Inline: False
Direct callers:
  - lib/zstd/huf_decompress.c:HUF_readDTableX4_wksp
  - lib/zstd/huf_decompress.c:HUF_readDTableX2_wksp
```
**Symbols:**

```
ffffffff8152da90-ffffffff8152dc6e: HUF_readStats_wksp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
size_t HUF_readStats_wksp(BYTE *huffWeight, size_t hwSize, U32 *rankStats, U32 *nbSymbolsPtr, U32 *tableLogPtr, const void *src, size_t srcSize, void *workspace, size_t workspaceSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/entropy_common.c (ffffffff8154e920)
Location: lib/zstd/entropy_common.c:167
Inline: False
Direct callers:
  - lib/zstd/huf_decompress.c:HUF_readDTableX4_wksp
  - lib/zstd/huf_decompress.c:HUF_readDTableX2_wksp
```
**Symbols:**

```
ffffffff8154e920-ffffffff8154eafe: HUF_readStats_wksp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
size_t HUF_readStats_wksp(BYTE *huffWeight, size_t hwSize, U32 *rankStats, U32 *nbSymbolsPtr, U32 *tableLogPtr, const void *src, size_t srcSize, void *workspace, size_t workspaceSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/entropy_common.c (ffffffff815cc880)
Location: lib/zstd/entropy_common.c:167
Inline: False
Direct callers:
  - lib/zstd/huf_compress.c:HUF_readCTable_wksp
  - lib/zstd/huf_decompress.c:HUF_readDTableX4_wksp
  - lib/zstd/huf_decompress.c:HUF_readDTableX2_wksp
```
**Symbols:**

```
ffffffff815cc880-ffffffff815cca64: HUF_readStats_wksp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
size_t HUF_readStats_wksp(BYTE *huffWeight, size_t hwSize, U32 *rankStats, U32 *nbSymbolsPtr, U32 *tableLogPtr, const void *src, size_t srcSize, void *workspace, size_t workspaceSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/entropy_common.c (ffffffff815ea400)
Location: lib/zstd/entropy_common.c:167
Inline: False
Direct callers:
  - lib/zstd/huf_compress.c:HUF_readCTable_wksp
  - lib/zstd/huf_decompress.c:HUF_readDTableX4_wksp
  - lib/zstd/huf_decompress.c:HUF_readDTableX2_wksp
```
**Symbols:**

```
ffffffff815ea400-ffffffff815ea5e9: HUF_readStats_wksp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
size_t HUF_readStats_wksp(BYTE *huffWeight, size_t hwSize, U32 *rankStats, U32 *nbSymbolsPtr, U32 *tableLogPtr, const void *src, size_t srcSize, void *workspace, size_t workspaceSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/entropy_common.c (ffffffff815d8510)
Location: lib/zstd/entropy_common.c:167
Inline: False
Direct callers:
  - lib/zstd/huf_decompress.c:HUF_readDTableX4_wksp
  - lib/zstd/huf_decompress.c:HUF_readDTableX2_wksp
```
**Symbols:**

```
ffffffff815d8510-ffffffff815d86f4: HUF_readStats_wksp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
size_t HUF_readStats_wksp(BYTE *huffWeight, size_t hwSize, U32 *rankStats, U32 *nbSymbolsPtr, U32 *tableLogPtr, const void *src, size_t srcSize, void *workspace, size_t workspaceSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/zstd/entropy_common.c (0)
Location: lib/zstd/entropy_common.c:167
Inline: False
Direct callers:
  - lib/zstd/huf_decompress.c:HUF_readDTableX4_wksp
  - lib/zstd/huf_decompress.c:HUF_readDTableX2_wksp
```
**Symbols:**

```
ffffffff81cdd412-ffffffff81cdd450: HUF_readStats_wksp.cold (STB_LOCAL)
ffffffff816437a0-ffffffff816439a6: HUF_readStats_wksp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
size_t HUF_readStats_wksp(BYTE *huffWeight, size_t hwSize, U32 *rankStats, U32 *nbSymbolsPtr, U32 *tableLogPtr, const void *src, size_t srcSize, void *workSpace, size_t wkspSize, int bmi2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/common/entropy_common.c (ffffffff8170a0b8)
Location: lib/zstd/common/entropy_common.c:344
Inline: True
Inline callers:
  - lib/zstd/common/entropy_common.c:HUF_readStats
Direct callers:
  - lib/zstd/decompress/huf_decompress.c:HUF_readDTableX2_wksp
  - lib/zstd/decompress/huf_decompress.c:HUF_readDTableX1_wksp_bmi2
```
**Symbols:**

```
ffffffff8170a100-ffffffff8170a16b: HUF_readStats_wksp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
size_t HUF_readStats_wksp(BYTE *huffWeight, size_t hwSize, U32 *rankStats, U32 *nbSymbolsPtr, U32 *tableLogPtr, const void *src, size_t srcSize, void *workSpace, size_t wkspSize, int bmi2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/common/entropy_common.c (ffffffff81884c38)
Location: lib/zstd/common/entropy_common.c:344
Inline: True
Inline callers:
  - lib/zstd/common/entropy_common.c:HUF_readStats
Direct callers:
  - lib/zstd/decompress/huf_decompress.c:HUF_readDTableX2_wksp_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_readDTableX1_wksp_bmi2
```
**Symbols:**

```
ffffffff81884c90-ffffffff81884cfb: HUF_readStats_wksp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
size_t HUF_readStats_wksp(BYTE *huffWeight, size_t hwSize, U32 *rankStats, U32 *nbSymbolsPtr, U32 *tableLogPtr, const void *src, size_t srcSize, void *workSpace, size_t wkspSize, int bmi2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/common/entropy_common.c (ffffffff818c7148)
Location: lib/zstd/common/entropy_common.c:344
Inline: True
Inline callers:
  - lib/zstd/common/entropy_common.c:HUF_readStats
Direct callers:
  - lib/zstd/decompress/huf_decompress.c:HUF_readDTableX2_wksp_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_readDTableX1_wksp_bmi2
```
**Symbols:**

```
ffffffff818c71a0-ffffffff818c720b: HUF_readStats_wksp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
size_t HUF_readStats_wksp(BYTE *huffWeight, size_t hwSize, U32 *rankStats, U32 *nbSymbolsPtr, U32 *tableLogPtr, const void *src, size_t srcSize, void *workSpace, size_t wkspSize, int bmi2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/common/entropy_common.c (ffffffff81918d08)
Location: lib/zstd/common/entropy_common.c:344
Inline: True
Inline callers:
  - lib/zstd/common/entropy_common.c:HUF_readStats
Direct callers:
  - lib/zstd/decompress/huf_decompress.c:HUF_readDTableX2_wksp_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_readDTableX1_wksp_bmi2
```
**Symbols:**

```
ffffffff81918d60-ffffffff81918dcb: HUF_readStats_wksp (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
size_t HUF_readStats_wksp(BYTE *huffWeight, size_t hwSize, U32 *rankStats, U32 *nbSymbolsPtr, U32 *tableLogPtr, const void *src, size_t srcSize, void *workspace, size_t workspaceSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/entropy_common.c (ffff80001065aa70)
Location: lib/zstd/entropy_common.c:167
Inline: False
Direct callers:
  - lib/zstd/huf_decompress.c:HUF_readDTableX4_wksp
  - lib/zstd/huf_decompress.c:HUF_readDTableX2_wksp
```
**Symbols:**

```
ffff80001065aa70-ffff80001065ac48: HUF_readStats_wksp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
size_t HUF_readStats_wksp(BYTE *huffWeight, size_t hwSize, U32 *rankStats, U32 *nbSymbolsPtr, U32 *tableLogPtr, const void *src, size_t srcSize, void *workspace, size_t workspaceSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/entropy_common.c (c080402c)
Location: lib/zstd/entropy_common.c:167
Inline: False
Direct callers:
  - lib/zstd/huf_decompress.c:HUF_readDTableX4_wksp
  - lib/zstd/huf_decompress.c:HUF_readDTableX2_wksp
```
**Symbols:**

```
c080402c-c08041f8: HUF_readStats_wksp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
size_t HUF_readStats_wksp(BYTE *huffWeight, size_t hwSize, U32 *rankStats, U32 *nbSymbolsPtr, U32 *tableLogPtr, const void *src, size_t srcSize, void *workspace, size_t workspaceSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/entropy_common.c (c00000000080b9a8)
Location: lib/zstd/entropy_common.c:167
Inline: False
Direct callers:
  - lib/zstd/huf_decompress.c:HUF_readDTableX4_wksp
  - lib/zstd/huf_decompress.c:HUF_readDTableX2_wksp
```
**Symbols:**

```
c00000000080b9a8-c00000000080bc28: HUF_readStats_wksp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
size_t HUF_readStats_wksp(BYTE *huffWeight, size_t hwSize, U32 *rankStats, U32 *nbSymbolsPtr, U32 *tableLogPtr, const void *src, size_t srcSize, void *workspace, size_t workspaceSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/entropy_common.c (ffffffe00048849a)
Location: lib/zstd/entropy_common.c:167
Inline: False
Direct callers:
  - lib/zstd/huf_decompress.c:HUF_readDTableX4_wksp
  - lib/zstd/huf_decompress.c:HUF_readDTableX2_wksp
```
**Symbols:**

```
ffffffe00048849a-ffffffe000488660: HUF_readStats_wksp (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
size_t HUF_readStats_wksp(BYTE *huffWeight, size_t hwSize, U32 *rankStats, U32 *nbSymbolsPtr, U32 *tableLogPtr, const void *src, size_t srcSize, void *workspace, size_t workspaceSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/entropy_common.c (ffffffff81546f00)
Location: lib/zstd/entropy_common.c:167
Inline: False
Direct callers:
  - lib/zstd/huf_decompress.c:HUF_readDTableX4_wksp
  - lib/zstd/huf_decompress.c:HUF_readDTableX2_wksp
```
**Symbols:**

```
ffffffff81546f00-ffffffff815470de: HUF_readStats_wksp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
size_t HUF_readStats_wksp(BYTE *huffWeight, size_t hwSize, U32 *rankStats, U32 *nbSymbolsPtr, U32 *tableLogPtr, const void *src, size_t srcSize, void *workspace, size_t workspaceSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/entropy_common.c (ffffffff815371e0)
Location: lib/zstd/entropy_common.c:167
Inline: False
Direct callers:
  - lib/zstd/huf_decompress.c:HUF_readDTableX4_wksp
  - lib/zstd/huf_decompress.c:HUF_readDTableX2_wksp
```
**Symbols:**

```
ffffffff815371e0-ffffffff815373be: HUF_readStats_wksp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
size_t HUF_readStats_wksp(BYTE *huffWeight, size_t hwSize, U32 *rankStats, U32 *nbSymbolsPtr, U32 *tableLogPtr, const void *src, size_t srcSize, void *workspace, size_t workspaceSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/entropy_common.c (ffffffff81542c40)
Location: lib/zstd/entropy_common.c:167
Inline: False
Direct callers:
  - lib/zstd/huf_decompress.c:HUF_readDTableX4_wksp
  - lib/zstd/huf_decompress.c:HUF_readDTableX2_wksp
```
**Symbols:**

```
ffffffff81542c40-ffffffff81542e1e: HUF_readStats_wksp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
size_t HUF_readStats_wksp(BYTE *huffWeight, size_t hwSize, U32 *rankStats, U32 *nbSymbolsPtr, U32 *tableLogPtr, const void *src, size_t srcSize, void *workspace, size_t workspaceSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/entropy_common.c (ffffffff8155ca70)
Location: lib/zstd/entropy_common.c:167
Inline: False
Direct callers:
  - lib/zstd/huf_decompress.c:HUF_readDTableX4_wksp
  - lib/zstd/huf_decompress.c:HUF_readDTableX2_wksp
```
**Symbols:**

```
ffffffff8155ca70-ffffffff8155cc4e: HUF_readStats_wksp (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>void *workSpace</code>
</li>
<li>
<b>Param added. </b>
<code>size_t wkspSize</code>
</li>
<li>
<b>Param added. </b>
<code>int bmi2</code>
</li>
<li>
<b>Param removed. </b>
<code>void *workspace</code>
</li>
<li>
<b>Param removed. </b>
<code>size_t workspaceSize</code>
</li>
</ul>
</details>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
