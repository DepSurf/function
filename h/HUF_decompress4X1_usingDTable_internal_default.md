# Function: <code>HUF_decompress4X1_usingDTable_internal_default</code>

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
size_t HUF_decompress4X1_usingDTable_internal_default(void *dst, size_t dstSize, const void *cSrc, size_t cSrcSize, const HUF_DTable *DTable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress/huf_decompress.c (ffffffff817497c0)
Location: lib/zstd/decompress/huf_decompress.c:450
Inline: False
Direct callers:
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X_usingDTable_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X_hufOnly_wksp
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X_usingDTable
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable
```
**Symbols:**

```
ffffffff817497c0-ffffffff8174a905: HUF_decompress4X1_usingDTable_internal_default (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
size_t HUF_decompress4X1_usingDTable_internal_default(void *dst, size_t dstSize, const void *cSrc, size_t cSrcSize, const HUF_DTable *DTable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress/huf_decompress.c (ffffffff8186cce0)
Location: lib/zstd/decompress/huf_decompress.c:655
Inline: False
Direct callers:
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X_usingDTable_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X_hufOnly_wksp
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X_usingDTable
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable
```
**Symbols:**

```
ffffffff8186cce0-ffffffff8186e115: HUF_decompress4X1_usingDTable_internal_default (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
size_t HUF_decompress4X1_usingDTable_internal_default(void *dst, size_t dstSize, const void *cSrc, size_t cSrcSize, const HUF_DTable *DTable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress/huf_decompress.c (ffffffff818ad9d0)
Location: lib/zstd/decompress/huf_decompress.c:655
Inline: False
Direct callers:
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X_usingDTable_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X_hufOnly_wksp
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X_usingDTable
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable
```
**Symbols:**

```
ffffffff818ad9d0-ffffffff818aedf5: HUF_decompress4X1_usingDTable_internal_default (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
size_t HUF_decompress4X1_usingDTable_internal_default(void *dst, size_t dstSize, const void *cSrc, size_t cSrcSize, const HUF_DTable *DTable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress/huf_decompress.c (ffffffff818ff590)
Location: lib/zstd/decompress/huf_decompress.c:655
Inline: False
Direct callers:
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X_usingDTable_bmi2
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X_hufOnly_wksp
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X_usingDTable
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable
```
**Symbols:**

```
ffffffff818ff590-ffffffff819009b5: HUF_decompress4X1_usingDTable_internal_default (STB_LOCAL)
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
