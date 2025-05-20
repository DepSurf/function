# Function: <code>ZSTD_buildBlockEntropyStats_literals</code>

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
size_t ZSTD_buildBlockEntropyStats_literals(const void * src, size_t srcSize, const ZSTD_hufCTables_t *prevHuf, ZSTD_hufCTables_t *nextHuf, ZSTD_hufCTablesMetadata_t *hufMetadata, const int literalsCompressionIsDisabled, void *workspace, size_t wkspSize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff81804b70)
Location: lib/zstd/compress/zstd_compress.c:2963
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_buildBlockEntropyStats
```
**Symbols:**

```
ffffffff81804b70-ffffffff81804e9c: ZSTD_buildBlockEntropyStats_literals (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
size_t ZSTD_buildBlockEntropyStats_literals(const void * src, size_t srcSize, const ZSTD_hufCTables_t *prevHuf, ZSTD_hufCTables_t *nextHuf, ZSTD_hufCTablesMetadata_t *hufMetadata, const int literalsCompressionIsDisabled, void *workspace, size_t wkspSize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff81845570)
Location: lib/zstd/compress/zstd_compress.c:2963
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_buildBlockEntropyStats
```
**Symbols:**

```
ffffffff81845570-ffffffff818458a2: ZSTD_buildBlockEntropyStats_literals (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
size_t ZSTD_buildBlockEntropyStats_literals(const void * src, size_t srcSize, const ZSTD_hufCTables_t *prevHuf, ZSTD_hufCTables_t *nextHuf, ZSTD_hufCTablesMetadata_t *hufMetadata, const int literalsCompressionIsDisabled, void *workspace, size_t wkspSize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff81897130)
Location: lib/zstd/compress/zstd_compress.c:2963
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_buildBlockEntropyStats
```
**Symbols:**

```
ffffffff81897130-ffffffff81897462: ZSTD_buildBlockEntropyStats_literals (STB_LOCAL)
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
