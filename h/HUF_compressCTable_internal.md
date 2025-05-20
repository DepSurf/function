# Function: <code>HUF_compressCTable_internal</code>

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
In lib/zstd/huf_compress.c (ffffffff815af122)
Location: lib/zstd/huf_compress.c:633
Inline: True
Inline callers:
  - lib/zstd/huf_compress.c:HUF_compress4X_wksp
  - lib/zstd/huf_compress.c:HUF_compress1X_wksp
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
In lib/zstd/huf_compress.c (ffffffff815cacc7)
Location: lib/zstd/huf_compress.c:634
Inline: True
Inline callers:
  - lib/zstd/huf_compress.c:HUF_compress4X_wksp
  - lib/zstd/huf_compress.c:HUF_compress1X_wksp
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
size_t HUF_compressCTable_internal(const BYTE * ostart, BYTE *op, const BYTE * oend, const void *src, size_t srcSize, HUF_nbStreams_e nbStreams, const HUF_CElt *CTable, const int bmi2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/huf_compress.c (ffffffff81710120)
Location: lib/zstd/compress/huf_compress.c:734
Inline: False
Direct callers:
  - lib/zstd/compress/huf_compress.c:HUF_compress_internal
  - lib/zstd/compress/huf_compress.c:HUF_compress_internal
```
**Symbols:**

```
ffffffff81710120-ffffffff817101b4: HUF_compressCTable_internal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
size_t HUF_compressCTable_internal(const BYTE * ostart, BYTE *op, const BYTE * oend, const void *src, size_t srcSize, HUF_nbStreams_e nbStreams, const HUF_CElt *CTable, const int bmi2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/huf_compress.c (ffffffff81802820)
Location: lib/zstd/compress/huf_compress.c:1141
Inline: False
Direct callers:
  - lib/zstd/compress/huf_compress.c:HUF_compress_internal
  - lib/zstd/compress/huf_compress.c:HUF_compress_internal
```
**Symbols:**

```
ffffffff81802820-ffffffff818028b4: HUF_compressCTable_internal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
size_t HUF_compressCTable_internal(const BYTE * ostart, BYTE *op, const BYTE * oend, const void *src, size_t srcSize, HUF_nbStreams_e nbStreams, const HUF_CElt *CTable, const int bmi2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/huf_compress.c (ffffffff81843110)
Location: lib/zstd/compress/huf_compress.c:1141
Inline: False
Direct callers:
  - lib/zstd/compress/huf_compress.c:HUF_compress_internal
  - lib/zstd/compress/huf_compress.c:HUF_compress_internal
```
**Symbols:**

```
ffffffff81843110-ffffffff818431a4: HUF_compressCTable_internal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
size_t HUF_compressCTable_internal(const BYTE * ostart, BYTE *op, const BYTE * oend, const void *src, size_t srcSize, HUF_nbStreams_e nbStreams, const HUF_CElt *CTable, const int bmi2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/huf_compress.c (ffffffff81894cd0)
Location: lib/zstd/compress/huf_compress.c:1141
Inline: False
Direct callers:
  - lib/zstd/compress/huf_compress.c:HUF_compress_internal
  - lib/zstd/compress/huf_compress.c:HUF_compress_internal
```
**Symbols:**

```
ffffffff81894cd0-ffffffff81894d64: HUF_compressCTable_internal (STB_LOCAL)
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
