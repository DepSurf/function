# Function: <code>HUF_compress1X_usingCTable</code>

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
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
size_t HUF_compress1X_usingCTable(void *dst, size_t dstSize, const void *src, size_t srcSize, const HUF_CElt *CTable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/zstd/huf_compress.c (ffffffff815aee2a)
Location: lib/zstd/huf_compress.c:538
Inline: True
Inline callers:
  - lib/zstd/huf_compress.c:HUF_compress1X_wksp
  - lib/zstd/huf_compress.c:HUF_compress4X_usingCTable
  - lib/zstd/huf_compress.c:HUF_compress4X_usingCTable
  - lib/zstd/huf_compress.c:HUF_compress4X_usingCTable
  - lib/zstd/huf_compress.c:HUF_compress4X_usingCTable
  - lib/zstd/huf_compress.c:HUF_compress4X_usingCTable
  - lib/zstd/huf_compress.c:HUF_compress4X_usingCTable
  - lib/zstd/huf_compress.c:HUF_compress4X_usingCTable
Direct callers:
  - lib/zstd/huf_compress.c:HUF_compress1X_wksp
  - lib/zstd/huf_compress.c:HUF_compress4X_usingCTable
  - lib/zstd/huf_compress.c:HUF_compress4X_usingCTable
  - lib/zstd/huf_compress.c:HUF_compress4X_usingCTable
  - lib/zstd/huf_compress.c:HUF_compress4X_usingCTable
  - lib/zstd/huf_compress.c:HUF_compress4X_usingCTable
  - lib/zstd/huf_compress.c:HUF_compress4X_usingCTable
  - lib/zstd/huf_compress.c:HUF_compress4X_usingCTable
```
**Symbols:**

```
ffffffff815ad490-ffffffff815ad699: HUF_compress1X_usingCTable.part.0 (STB_LOCAL)
ffffffff815ae5d0-ffffffff815ae5e4: HUF_compress1X_usingCTable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
size_t HUF_compress1X_usingCTable(void *dst, size_t dstSize, const void *src, size_t srcSize, const HUF_CElt *CTable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/zstd/huf_compress.c (ffffffff815ca9bf)
Location: lib/zstd/huf_compress.c:538
Inline: True
Inline callers:
  - lib/zstd/huf_compress.c:HUF_compress1X_wksp
  - lib/zstd/huf_compress.c:HUF_compress4X_usingCTable
  - lib/zstd/huf_compress.c:HUF_compress4X_usingCTable
  - lib/zstd/huf_compress.c:HUF_compress4X_usingCTable
  - lib/zstd/huf_compress.c:HUF_compress4X_usingCTable
  - lib/zstd/huf_compress.c:HUF_compress4X_usingCTable
  - lib/zstd/huf_compress.c:HUF_compress4X_usingCTable
  - lib/zstd/huf_compress.c:HUF_compress4X_usingCTable
Direct callers:
  - lib/zstd/huf_compress.c:HUF_compress1X_wksp
  - lib/zstd/huf_compress.c:HUF_compress4X_usingCTable
  - lib/zstd/huf_compress.c:HUF_compress4X_usingCTable
  - lib/zstd/huf_compress.c:HUF_compress4X_usingCTable
  - lib/zstd/huf_compress.c:HUF_compress4X_usingCTable
  - lib/zstd/huf_compress.c:HUF_compress4X_usingCTable
  - lib/zstd/huf_compress.c:HUF_compress4X_usingCTable
  - lib/zstd/huf_compress.c:HUF_compress4X_usingCTable
```
**Symbols:**

```
ffffffff815c8ff0-ffffffff815c91fe: HUF_compress1X_usingCTable.part.0 (STB_LOCAL)
ffffffff815ca150-ffffffff815ca169: HUF_compress1X_usingCTable (STB_GLOBAL)
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
size_t HUF_compress1X_usingCTable(void *dst, size_t dstSize, const void *src, size_t srcSize, const HUF_CElt *CTable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/huf_compress.c (ffffffff817113c0)
Location: lib/zstd/compress/huf_compress.c:668
Inline: False
```
**Symbols:**

```
ffffffff817113c0-ffffffff817113df: HUF_compress1X_usingCTable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
size_t HUF_compress1X_usingCTable(void *dst, size_t dstSize, const void *src, size_t srcSize, const HUF_CElt *CTable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/huf_compress.c (ffffffff81803d90)
Location: lib/zstd/compress/huf_compress.c:1069
Inline: False
```
**Symbols:**

```
ffffffff81803d90-ffffffff81803daf: HUF_compress1X_usingCTable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
size_t HUF_compress1X_usingCTable(void *dst, size_t dstSize, const void *src, size_t srcSize, const HUF_CElt *CTable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/huf_compress.c (ffffffff81844780)
Location: lib/zstd/compress/huf_compress.c:1069
Inline: False
```
**Symbols:**

```
ffffffff81844780-ffffffff8184479f: HUF_compress1X_usingCTable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
size_t HUF_compress1X_usingCTable(void *dst, size_t dstSize, const void *src, size_t srcSize, const HUF_CElt *CTable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/huf_compress.c (ffffffff81896340)
Location: lib/zstd/compress/huf_compress.c:1069
Inline: False
```
**Symbols:**

```
ffffffff81896340-ffffffff8189635f: HUF_compress1X_usingCTable (STB_GLOBAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
