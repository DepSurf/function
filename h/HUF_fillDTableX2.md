# Function: <code>HUF_fillDTableX2</code>

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
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/zstd/decompress/huf_decompress.c (0)
Location: lib/zstd/decompress/huf_decompress.c:571
Inline: True
Direct callers:
  - lib/zstd/decompress/huf_decompress.c:HUF_readDTableX2_wksp
```
**Symbols:**

```
ffffffff81748810-ffffffff81748a91: HUF_fillDTableX2.constprop.0 (STB_LOCAL)
ffffffff81ea35b7-ffffffff81ea363c: HUF_fillDTableX2.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void HUF_fillDTableX2(HUF_DEltX2 *DTable, const U32 targetLog, const sortedSymbol_t *sortedList, const U32 *rankStart, rankValCol_t *rankValOrigin, const U32 maxWeight, const U32 nbBitsBaseline);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress/huf_decompress.c (ffffffff8186a0b0)
Location: lib/zstd/decompress/huf_decompress.c:986
Inline: False
Direct callers:
  - lib/zstd/decompress/huf_decompress.c:HUF_readDTableX2_wksp_bmi2
```
**Symbols:**

```
ffffffff8186a0b0-ffffffff8186a3a4: HUF_fillDTableX2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void HUF_fillDTableX2(HUF_DEltX2 *DTable, const U32 targetLog, const sortedSymbol_t *sortedList, const U32 *rankStart, rankValCol_t *rankValOrigin, const U32 maxWeight, const U32 nbBitsBaseline);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress/huf_decompress.c (ffffffff818aad30)
Location: lib/zstd/decompress/huf_decompress.c:986
Inline: False
Direct callers:
  - lib/zstd/decompress/huf_decompress.c:HUF_readDTableX2_wksp_bmi2
```
**Symbols:**

```
ffffffff818aad30-ffffffff818ab040: HUF_fillDTableX2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void HUF_fillDTableX2(HUF_DEltX2 *DTable, const U32 targetLog, const sortedSymbol_t *sortedList, const U32 *rankStart, rankValCol_t *rankValOrigin, const U32 maxWeight, const U32 nbBitsBaseline);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress/huf_decompress.c (ffffffff818fc8f0)
Location: lib/zstd/decompress/huf_decompress.c:986
Inline: False
Direct callers:
  - lib/zstd/decompress/huf_decompress.c:HUF_readDTableX2_wksp_bmi2
```
**Symbols:**

```
ffffffff818fc8f0-ffffffff818fcc00: HUF_fillDTableX2 (STB_LOCAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
