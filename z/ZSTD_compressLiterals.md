# Function: <code>ZSTD_compressLiterals</code>

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
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/zstd/compress.c (ffffffff815c8d79)
Location: lib/zstd/compress.c:482
Inline: True
Inline callers:
  - lib/zstd/compress.c:ZSTD_compressSequences_internal
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/zstd/compress.c (ffffffff815e68e9)
Location: lib/zstd/compress.c:482
Inline: True
Inline callers:
  - lib/zstd/compress.c:ZSTD_compressSequences_internal
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
size_t ZSTD_compressLiterals(const ZSTD_hufCTables_t *prevHuf, ZSTD_hufCTables_t *nextHuf, ZSTD_strategy strategy, int disableLiteralCompression, void *dst, size_t dstCapacity, const void *src, size_t srcSize, void *entropyWorkspace, size_t entropyWorkspaceSize, const int bmi2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/zstd/compress/zstd_compress_literals.c (0)
Location: lib/zstd/compress/zstd_compress_literals.c:70
Inline: False
```
**Symbols:**

```
ffffffff81e9750d-ffffffff81e9753a: ZSTD_compressLiterals.cold (STB_LOCAL)
ffffffff8171ca10-ffffffff8171cd75: ZSTD_compressLiterals (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
size_t ZSTD_compressLiterals(const ZSTD_hufCTables_t *prevHuf, ZSTD_hufCTables_t *nextHuf, ZSTD_strategy strategy, int disableLiteralCompression, void *dst, size_t dstCapacity, const void *src, size_t srcSize, void *entropyWorkspace, size_t entropyWorkspaceSize, const int bmi2, unsigned int suspectUncompressible);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/zstd/compress/zstd_compress_literals.c (0)
Location: lib/zstd/compress/zstd_compress_literals.c:70
Inline: False
```
**Symbols:**

```
ffffffff8207e09c-ffffffff8207e0c1: ZSTD_compressLiterals.cold (STB_LOCAL)
ffffffff81812340-ffffffff8181269a: ZSTD_compressLiterals (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
size_t ZSTD_compressLiterals(const ZSTD_hufCTables_t *prevHuf, ZSTD_hufCTables_t *nextHuf, ZSTD_strategy strategy, int disableLiteralCompression, void *dst, size_t dstCapacity, const void *src, size_t srcSize, void *entropyWorkspace, size_t entropyWorkspaceSize, const int bmi2, unsigned int suspectUncompressible);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/zstd/compress/zstd_compress_literals.c (0)
Location: lib/zstd/compress/zstd_compress_literals.c:70
Inline: False
```
**Symbols:**

```
ffffffff820fe613-ffffffff820fe638: ZSTD_compressLiterals.cold (STB_LOCAL)
ffffffff81852e40-ffffffff8185319a: ZSTD_compressLiterals (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
size_t ZSTD_compressLiterals(const ZSTD_hufCTables_t *prevHuf, ZSTD_hufCTables_t *nextHuf, ZSTD_strategy strategy, int disableLiteralCompression, void *dst, size_t dstCapacity, const void *src, size_t srcSize, void *entropyWorkspace, size_t entropyWorkspaceSize, const int bmi2, unsigned int suspectUncompressible);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/zstd/compress/zstd_compress_literals.c (0)
Location: lib/zstd/compress/zstd_compress_literals.c:70
Inline: False
```
**Symbols:**

```
ffffffff821dc780-ffffffff821dc7a5: ZSTD_compressLiterals.cold (STB_LOCAL)
ffffffff818a4a00-ffffffff818a4d5a: ZSTD_compressLiterals (STB_GLOBAL)
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
<b>Param added. </b>
<code>unsigned int suspectUncompressible</code>
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
