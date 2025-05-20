# Function: <code>ZSTD_buildFSETable</code>

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
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void ZSTD_buildFSETable(ZSTD_seqSymbol *dt, const short int *normalizedCounter, unsigned int maxSymbolValue, const U32 *baseValue, const U32 *nbAdditionalBits, unsigned int tableLog, void *wksp, size_t wkspSize, int bmi2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress/zstd_decompress_block.c (ffffffff817558c4)
Location: lib/zstd/decompress/zstd_decompress_block.c:508
Inline: True
Direct callers:
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_loadDEntropy
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_loadDEntropy
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_loadDEntropy
```
**Symbols:**

```
ffffffff8175a110-ffffffff8175a166: ZSTD_buildFSETable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void ZSTD_buildFSETable(ZSTD_seqSymbol *dt, const short int *normalizedCounter, unsigned int maxSymbolValue, const U32 *baseValue, const U8 *nbAdditionalBits, unsigned int tableLog, void *wksp, size_t wkspSize, int bmi2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress/zstd_decompress_block.c (ffffffff8187a525)
Location: lib/zstd/decompress/zstd_decompress_block.c:584
Inline: True
Direct callers:
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_loadDEntropy
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_loadDEntropy
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_loadDEntropy
```
**Symbols:**

```
ffffffff81883910-ffffffff81883966: ZSTD_buildFSETable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void ZSTD_buildFSETable(ZSTD_seqSymbol *dt, const short int *normalizedCounter, unsigned int maxSymbolValue, const U32 *baseValue, const U8 *nbAdditionalBits, unsigned int tableLog, void *wksp, size_t wkspSize, int bmi2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress/zstd_decompress_block.c (ffffffff818bb360)
Location: lib/zstd/decompress/zstd_decompress_block.c:584
Inline: True
Direct callers:
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_loadDEntropy
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_loadDEntropy
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_loadDEntropy
```
**Symbols:**

```
ffffffff818c5e30-ffffffff818c5e86: ZSTD_buildFSETable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void ZSTD_buildFSETable(ZSTD_seqSymbol *dt, const short int *normalizedCounter, unsigned int maxSymbolValue, const U32 *baseValue, const U8 *nbAdditionalBits, unsigned int tableLog, void *wksp, size_t wkspSize, int bmi2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress/zstd_decompress_block.c (ffffffff8190cf20)
Location: lib/zstd/decompress/zstd_decompress_block.c:584
Inline: True
Direct callers:
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_loadDEntropy
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_loadDEntropy
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_loadDEntropy
```
**Symbols:**

```
ffffffff819179f0-ffffffff81917a46: ZSTD_buildFSETable (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>const U32 *nbAdditionalBits</code> ➡️ <code>const U8 *nbAdditionalBits</code>
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
