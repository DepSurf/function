# Function: <code>HIST_countFast_wksp</code>

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
size_t HIST_countFast_wksp(unsigned int *count, unsigned int *maxSymbolValuePtr, const void *source, size_t sourceSize, void *workSpace, size_t workSpaceSize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/hist.c (ffffffff8170f1b4)
Location: lib/zstd/compress/hist.c:140
Inline: True
Inline callers:
  - lib/zstd/compress/hist.c:HIST_count_wksp
  - lib/zstd/compress/hist.c:HIST_count_wksp
```
**Symbols:**

```
ffffffff8170f110-ffffffff8170f179: HIST_countFast_wksp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
size_t HIST_countFast_wksp(unsigned int *count, unsigned int *maxSymbolValuePtr, const void *source, size_t sourceSize, void *workSpace, size_t workSpaceSize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/hist.c (ffffffff817fe2a4)
Location: lib/zstd/compress/hist.c:140
Inline: True
Inline callers:
  - lib/zstd/compress/hist.c:HIST_count_wksp
  - lib/zstd/compress/hist.c:HIST_count_wksp
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_buildSequencesStatistics
  - lib/zstd/compress/zstd_compress.c:ZSTD_buildSequencesStatistics
  - lib/zstd/compress/zstd_compress.c:ZSTD_buildSequencesStatistics
```
**Symbols:**

```
ffffffff817fe1f0-ffffffff817fe259: HIST_countFast_wksp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
size_t HIST_countFast_wksp(unsigned int *count, unsigned int *maxSymbolValuePtr, const void *source, size_t sourceSize, void *workSpace, size_t workSpaceSize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/hist.c (ffffffff8183eae4)
Location: lib/zstd/compress/hist.c:140
Inline: True
Inline callers:
  - lib/zstd/compress/hist.c:HIST_count_wksp
  - lib/zstd/compress/hist.c:HIST_count_wksp
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_buildSequencesStatistics
  - lib/zstd/compress/zstd_compress.c:ZSTD_buildSequencesStatistics
  - lib/zstd/compress/zstd_compress.c:ZSTD_buildSequencesStatistics
```
**Symbols:**

```
ffffffff8183ea30-ffffffff8183ea99: HIST_countFast_wksp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
size_t HIST_countFast_wksp(unsigned int *count, unsigned int *maxSymbolValuePtr, const void *source, size_t sourceSize, void *workSpace, size_t workSpaceSize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/hist.c (ffffffff818906a4)
Location: lib/zstd/compress/hist.c:140
Inline: True
Inline callers:
  - lib/zstd/compress/hist.c:HIST_count_wksp
  - lib/zstd/compress/hist.c:HIST_count_wksp
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_buildSequencesStatistics
  - lib/zstd/compress/zstd_compress.c:ZSTD_buildSequencesStatistics
  - lib/zstd/compress/zstd_compress.c:ZSTD_buildSequencesStatistics
```
**Symbols:**

```
ffffffff818905f0-ffffffff81890659: HIST_countFast_wksp (STB_GLOBAL)
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
