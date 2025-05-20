# Function: <code>HUF_compress_internal</code>

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
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
size_t HUF_compress_internal(void *dst, size_t dstSize, const void *src, size_t srcSize, unsigned int maxSymbolValue, unsigned int huffLog, unsigned int singleStream, void *workSpace, size_t wkspSize, HUF_CElt *oldHufTable, HUF_repeat *repeat, int preferRepeat);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/huf_compress.c (ffffffff815aef8a)
Location: lib/zstd/huf_compress.c:653
Inline: True
Inline callers:
  - lib/zstd/huf_compress.c:HUF_compress4X_wksp
  - lib/zstd/huf_compress.c:HUF_compress1X_wksp
Direct callers:
  - lib/zstd/huf_compress.c:HUF_compress4X_repeat
  - lib/zstd/huf_compress.c:HUF_compress1X_repeat
```
**Symbols:**

```
ffffffff815ae7b0-ffffffff815aec70: HUF_compress_internal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
size_t HUF_compress_internal(void *dst, size_t dstSize, const void *src, size_t srcSize, unsigned int maxSymbolValue, unsigned int huffLog, unsigned int singleStream, void *workSpace, size_t wkspSize, HUF_CElt *oldHufTable, HUF_repeat *repeat, int preferRepeat);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/huf_compress.c (ffffffff815cab2f)
Location: lib/zstd/huf_compress.c:654
Inline: True
Inline callers:
  - lib/zstd/huf_compress.c:HUF_compress4X_wksp
  - lib/zstd/huf_compress.c:HUF_compress1X_wksp
Direct callers:
  - lib/zstd/huf_compress.c:HUF_compress4X_repeat
  - lib/zstd/huf_compress.c:HUF_compress1X_repeat
```
**Symbols:**

```
ffffffff815ca330-ffffffff815ca7f5: HUF_compress_internal (STB_LOCAL)
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
size_t HUF_compress_internal(void *dst, size_t dstSize, const void *src, size_t srcSize, unsigned int maxSymbolValue, unsigned int huffLog, HUF_nbStreams_e nbStreams, void *workSpace_align4, size_t wkspSize, HUF_CElt *oldHufTable, HUF_repeat *repeat, int preferRepeat, const int bmi2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/huf_compress.c (ffffffff81710f00)
Location: lib/zstd/compress/huf_compress.c:764
Inline: False
Direct callers:
  - lib/zstd/compress/huf_compress.c:HUF_compress4X_repeat
  - lib/zstd/compress/huf_compress.c:HUF_compress4X_wksp
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_repeat
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_wksp
```
**Symbols:**

```
ffffffff81710f00-ffffffff817112cf: HUF_compress_internal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
size_t HUF_compress_internal(void *dst, size_t dstSize, const void *src, size_t srcSize, unsigned int maxSymbolValue, unsigned int huffLog, HUF_nbStreams_e nbStreams, void *workSpace, size_t wkspSize, HUF_CElt *oldHufTable, HUF_repeat *repeat, int preferRepeat, const int bmi2, unsigned int suspectUncompressible);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/huf_compress.c (ffffffff818037c0)
Location: lib/zstd/compress/huf_compress.c:1175
Inline: False
Direct callers:
  - lib/zstd/compress/huf_compress.c:HUF_compress4X_repeat
  - lib/zstd/compress/huf_compress.c:HUF_compress4X_wksp
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_repeat
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_wksp
```
**Symbols:**

```
ffffffff818037c0-ffffffff81803c5a: HUF_compress_internal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
size_t HUF_compress_internal(void *dst, size_t dstSize, const void *src, size_t srcSize, unsigned int maxSymbolValue, unsigned int huffLog, HUF_nbStreams_e nbStreams, void *workSpace, size_t wkspSize, HUF_CElt *oldHufTable, HUF_repeat *repeat, int preferRepeat, const int bmi2, unsigned int suspectUncompressible);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/huf_compress.c (ffffffff818441b0)
Location: lib/zstd/compress/huf_compress.c:1175
Inline: False
Direct callers:
  - lib/zstd/compress/huf_compress.c:HUF_compress4X_repeat
  - lib/zstd/compress/huf_compress.c:HUF_compress4X_wksp
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_repeat
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_wksp
```
**Symbols:**

```
ffffffff818441b0-ffffffff8184464b: HUF_compress_internal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
size_t HUF_compress_internal(void *dst, size_t dstSize, const void *src, size_t srcSize, unsigned int maxSymbolValue, unsigned int huffLog, HUF_nbStreams_e nbStreams, void *workSpace, size_t wkspSize, HUF_CElt *oldHufTable, HUF_repeat *repeat, int preferRepeat, const int bmi2, unsigned int suspectUncompressible);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/huf_compress.c (ffffffff81895d70)
Location: lib/zstd/compress/huf_compress.c:1175
Inline: False
Direct callers:
  - lib/zstd/compress/huf_compress.c:HUF_compress4X_repeat
  - lib/zstd/compress/huf_compress.c:HUF_compress4X_wksp
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_repeat
  - lib/zstd/compress/huf_compress.c:HUF_compress1X_wksp
```
**Symbols:**

```
ffffffff81895d70-ffffffff8189620b: HUF_compress_internal (STB_LOCAL)
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
<code>void *workSpace</code>
</li>
<li>
<b>Param added. </b>
<code>unsigned int suspectUncompressible</code>
</li>
<li>
<b>Param removed. </b>
<code>void *workSpace_align4</code>
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
