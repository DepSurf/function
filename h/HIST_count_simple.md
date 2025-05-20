# Function: <code>HIST_count_simple</code>

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
<summary>In <code>5.19</code>: ✅</summary>

```c
unsigned int HIST_count_simple(unsigned int *count, unsigned int *maxSymbolValuePtr, const void *src, size_t srcSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/hist.c (ffffffff8170f050)
Location: lib/zstd/compress/hist.c:29
Inline: False
Direct callers:
  - lib/zstd/compress/hist.c:HIST_count_wksp
  - lib/zstd/compress/huf_compress.c:HUF_writeCTable_wksp
  - lib/zstd/compress/zstd_opt.c:ZSTD_rescaleFreqs
```
**Symbols:**

```
ffffffff8170f050-ffffffff8170f106: HIST_count_simple (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
unsigned int HIST_count_simple(unsigned int *count, unsigned int *maxSymbolValuePtr, const void *src, size_t srcSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/hist.c (ffffffff817fe120)
Location: lib/zstd/compress/hist.c:29
Inline: False
Direct callers:
  - lib/zstd/compress/hist.c:HIST_count_wksp
  - lib/zstd/compress/huf_compress.c:HUF_compress_internal
  - lib/zstd/compress/huf_compress.c:HUF_compress_internal
  - lib/zstd/compress/huf_compress.c:HUF_writeCTable_wksp
  - lib/zstd/compress/zstd_opt.c:ZSTD_rescaleFreqs
```
**Symbols:**

```
ffffffff817fe120-ffffffff817fe1d6: HIST_count_simple (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
unsigned int HIST_count_simple(unsigned int *count, unsigned int *maxSymbolValuePtr, const void *src, size_t srcSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/hist.c (ffffffff8183e960)
Location: lib/zstd/compress/hist.c:29
Inline: False
Direct callers:
  - lib/zstd/compress/hist.c:HIST_count_wksp
  - lib/zstd/compress/huf_compress.c:HUF_compress_internal
  - lib/zstd/compress/huf_compress.c:HUF_compress_internal
  - lib/zstd/compress/huf_compress.c:HUF_writeCTable_wksp
  - lib/zstd/compress/zstd_opt.c:ZSTD_rescaleFreqs
```
**Symbols:**

```
ffffffff8183e960-ffffffff8183ea16: HIST_count_simple (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
unsigned int HIST_count_simple(unsigned int *count, unsigned int *maxSymbolValuePtr, const void *src, size_t srcSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/hist.c (ffffffff81890520)
Location: lib/zstd/compress/hist.c:29
Inline: False
Direct callers:
  - lib/zstd/compress/hist.c:HIST_count_wksp
  - lib/zstd/compress/huf_compress.c:HUF_compress_internal
  - lib/zstd/compress/huf_compress.c:HUF_compress_internal
  - lib/zstd/compress/huf_compress.c:HUF_writeCTable_wksp
  - lib/zstd/compress/zstd_opt.c:ZSTD_rescaleFreqs
```
**Symbols:**

```
ffffffff81890520-ffffffff818905d6: HIST_count_simple (STB_GLOBAL)
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
