# Function: <code>HUF_compress1X_repeat</code>

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
size_t HUF_compress1X_repeat(void *dst, size_t dstSize, const void *src, size_t srcSize, unsigned int maxSymbolValue, unsigned int huffLog, void *workSpace, size_t wkspSize, HUF_CElt *hufTable, HUF_repeat *repeat, int preferRepeat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/huf_compress.c (ffffffff815aef30)
Location: lib/zstd/huf_compress.c:754
Inline: False
Direct callers:
  - lib/zstd/compress.c:ZSTD_compressSequences_internal
```
**Symbols:**

```
ffffffff815aef30-ffffffff815aef4d: HUF_compress1X_repeat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
size_t HUF_compress1X_repeat(void *dst, size_t dstSize, const void *src, size_t srcSize, unsigned int maxSymbolValue, unsigned int huffLog, void *workSpace, size_t wkspSize, HUF_CElt *hufTable, HUF_repeat *repeat, int preferRepeat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/huf_compress.c (ffffffff815caac0)
Location: lib/zstd/huf_compress.c:755
Inline: False
Direct callers:
  - lib/zstd/compress.c:ZSTD_compressSequences_internal
```
**Symbols:**

```
ffffffff815caac0-ffffffff815caae2: HUF_compress1X_repeat (STB_GLOBAL)
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
size_t HUF_compress1X_repeat(void *dst, size_t dstSize, const void *src, size_t srcSize, unsigned int maxSymbolValue, unsigned int huffLog, void *workSpace, size_t wkspSize, HUF_CElt *hufTable, HUF_repeat *repeat, int preferRepeat, int bmi2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/huf_compress.c (ffffffff81711450)
Location: lib/zstd/compress/huf_compress.c:865
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress_literals.c:ZSTD_compressLiterals
```
**Symbols:**

```
ffffffff81711450-ffffffff81711488: HUF_compress1X_repeat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
size_t HUF_compress1X_repeat(void *dst, size_t dstSize, const void *src, size_t srcSize, unsigned int maxSymbolValue, unsigned int huffLog, void *workSpace, size_t wkspSize, HUF_CElt *hufTable, HUF_repeat *repeat, int preferRepeat, int bmi2, unsigned int suspectUncompressible);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/huf_compress.c (ffffffff81803ee0)
Location: lib/zstd/compress/huf_compress.c:1293
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress_literals.c:ZSTD_compressLiterals
```
**Symbols:**

```
ffffffff81803ee0-ffffffff81803f1c: HUF_compress1X_repeat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
size_t HUF_compress1X_repeat(void *dst, size_t dstSize, const void *src, size_t srcSize, unsigned int maxSymbolValue, unsigned int huffLog, void *workSpace, size_t wkspSize, HUF_CElt *hufTable, HUF_repeat *repeat, int preferRepeat, int bmi2, unsigned int suspectUncompressible);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/huf_compress.c (ffffffff818448d0)
Location: lib/zstd/compress/huf_compress.c:1293
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress_literals.c:ZSTD_compressLiterals
```
**Symbols:**

```
ffffffff818448d0-ffffffff8184490c: HUF_compress1X_repeat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
size_t HUF_compress1X_repeat(void *dst, size_t dstSize, const void *src, size_t srcSize, unsigned int maxSymbolValue, unsigned int huffLog, void *workSpace, size_t wkspSize, HUF_CElt *hufTable, HUF_repeat *repeat, int preferRepeat, int bmi2, unsigned int suspectUncompressible);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/huf_compress.c (ffffffff81896490)
Location: lib/zstd/compress/huf_compress.c:1293
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress_literals.c:ZSTD_compressLiterals
```
**Symbols:**

```
ffffffff81896490-ffffffff818964cc: HUF_compress1X_repeat (STB_GLOBAL)
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
