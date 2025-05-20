# Function: <code>HUF_fillDTableX2ForWeight</code>

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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void HUF_fillDTableX2ForWeight(HUF_DEltX2 *DTableRank, const sortedSymbol_t *begin, const sortedSymbol_t *end, U32 nbBits, U32 tableLog, U16 baseSeq, const int level);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress/huf_decompress.c (ffffffff81869e40)
Location: lib/zstd/decompress/huf_decompress.c:872
Inline: False
Direct callers:
  - lib/zstd/decompress/huf_decompress.c:HUF_fillDTableX2
  - lib/zstd/decompress/huf_decompress.c:HUF_fillDTableX2
```
**Symbols:**

```
ffffffff81869e40-ffffffff8186a09a: HUF_fillDTableX2ForWeight (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void HUF_fillDTableX2ForWeight(HUF_DEltX2 *DTableRank, const sortedSymbol_t *begin, const sortedSymbol_t *end, U32 nbBits, U32 tableLog, U16 baseSeq, const int level);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress/huf_decompress.c (ffffffff818aaab0)
Location: lib/zstd/decompress/huf_decompress.c:872
Inline: False
Direct callers:
  - lib/zstd/decompress/huf_decompress.c:HUF_fillDTableX2
  - lib/zstd/decompress/huf_decompress.c:HUF_fillDTableX2
```
**Symbols:**

```
ffffffff818aaab0-ffffffff818aad11: HUF_fillDTableX2ForWeight (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void HUF_fillDTableX2ForWeight(HUF_DEltX2 *DTableRank, const sortedSymbol_t *begin, const sortedSymbol_t *end, U32 nbBits, U32 tableLog, U16 baseSeq, const int level);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress/huf_decompress.c (ffffffff818fc670)
Location: lib/zstd/decompress/huf_decompress.c:872
Inline: False
Direct callers:
  - lib/zstd/decompress/huf_decompress.c:HUF_fillDTableX2
  - lib/zstd/decompress/huf_decompress.c:HUF_fillDTableX2
```
**Symbols:**

```
ffffffff818fc670-ffffffff818fc8d1: HUF_fillDTableX2ForWeight (STB_LOCAL)
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
