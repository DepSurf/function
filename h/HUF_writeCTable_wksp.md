# Function: <code>HUF_writeCTable_wksp</code>

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
size_t HUF_writeCTable_wksp(void *dst, size_t maxDstSize, const HUF_CElt *CTable, U32 maxSymbolValue, U32 huffLog, void *workspace, size_t workspaceSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/huf_compress.c (ffffffff815ad8e0)
Location: lib/zstd/huf_compress.c:152
Inline: False
Direct callers:
  - lib/zstd/huf_compress.c:HUF_compress4X_wksp
  - lib/zstd/huf_compress.c:HUF_compress4X_wksp
  - lib/zstd/huf_compress.c:HUF_compress1X_wksp
  - lib/zstd/huf_compress.c:HUF_compress1X_wksp
  - lib/zstd/huf_compress.c:HUF_compress_internal
  - lib/zstd/huf_compress.c:HUF_compress_internal
```
**Symbols:**

```
ffffffff815ad8e0-ffffffff815adab9: HUF_writeCTable_wksp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
size_t HUF_writeCTable_wksp(void *dst, size_t maxDstSize, const HUF_CElt *CTable, U32 maxSymbolValue, U32 huffLog, void *workspace, size_t workspaceSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/huf_compress.c (ffffffff815c9440)
Location: lib/zstd/huf_compress.c:152
Inline: False
Direct callers:
  - lib/zstd/huf_compress.c:HUF_compress4X_wksp
  - lib/zstd/huf_compress.c:HUF_compress4X_wksp
  - lib/zstd/huf_compress.c:HUF_compress1X_wksp
  - lib/zstd/huf_compress.c:HUF_compress1X_wksp
  - lib/zstd/huf_compress.c:HUF_compress_internal
  - lib/zstd/huf_compress.c:HUF_compress_internal
```
**Symbols:**

```
ffffffff815c9440-ffffffff815c961e: HUF_writeCTable_wksp (STB_GLOBAL)
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
size_t HUF_writeCTable_wksp(void *dst, size_t maxDstSize, const HUF_CElt *CTable, unsigned int maxSymbolValue, unsigned int huffLog, void *workspace, size_t workspaceSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/huf_compress.c (ffffffff817101f0)
Location: lib/zstd/compress/huf_compress.c:113
Inline: False
Direct callers:
  - lib/zstd/compress/huf_compress.c:HUF_compress_internal
  - lib/zstd/compress/huf_compress.c:HUF_writeCTable
```
**Symbols:**

```
ffffffff817101f0-ffffffff8171054b: HUF_writeCTable_wksp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
size_t HUF_writeCTable_wksp(void *dst, size_t maxDstSize, const HUF_CElt *CTable, unsigned int maxSymbolValue, unsigned int huffLog, void *workspace, size_t workspaceSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/huf_compress.c (ffffffff81802910)
Location: lib/zstd/compress/huf_compress.c:169
Inline: False
Direct callers:
  - lib/zstd/compress/huf_compress.c:HUF_compress_internal
  - lib/zstd/compress/huf_compress.c:HUF_writeCTable
  - lib/zstd/compress/zstd_compress.c:ZSTD_buildBlockEntropyStats_literals
```
**Symbols:**

```
ffffffff81802910-ffffffff81802ce0: HUF_writeCTable_wksp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
size_t HUF_writeCTable_wksp(void *dst, size_t maxDstSize, const HUF_CElt *CTable, unsigned int maxSymbolValue, unsigned int huffLog, void *workspace, size_t workspaceSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/huf_compress.c (ffffffff81843200)
Location: lib/zstd/compress/huf_compress.c:169
Inline: False
Direct callers:
  - lib/zstd/compress/huf_compress.c:HUF_compress_internal
  - lib/zstd/compress/huf_compress.c:HUF_writeCTable
  - lib/zstd/compress/zstd_compress.c:ZSTD_buildBlockEntropyStats_literals
```
**Symbols:**

```
ffffffff81843200-ffffffff818436d3: HUF_writeCTable_wksp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
size_t HUF_writeCTable_wksp(void *dst, size_t maxDstSize, const HUF_CElt *CTable, unsigned int maxSymbolValue, unsigned int huffLog, void *workspace, size_t workspaceSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/huf_compress.c (ffffffff81894dc0)
Location: lib/zstd/compress/huf_compress.c:169
Inline: False
Direct callers:
  - lib/zstd/compress/huf_compress.c:HUF_compress_internal
  - lib/zstd/compress/huf_compress.c:HUF_writeCTable
  - lib/zstd/compress/zstd_compress.c:ZSTD_buildBlockEntropyStats_literals
```
**Symbols:**

```
ffffffff81894dc0-ffffffff81895293: HUF_writeCTable_wksp (STB_GLOBAL)
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
