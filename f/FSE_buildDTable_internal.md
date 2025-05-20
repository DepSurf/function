# Function: <code>FSE_buildDTable_internal</code>

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
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
size_t FSE_buildDTable_internal(FSE_DTable *dt, const short int *normalizedCounter, unsigned int maxSymbolValue, unsigned int tableLog, void *workSpace, size_t wkspSize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/zstd/common/fse_decompress.c (0)
Location: lib/zstd/common/fse_decompress.c:71
Inline: False
Direct callers:
  - lib/zstd/common/fse_decompress.c:FSE_decompress_wksp_body_bmi2
  - lib/zstd/common/fse_decompress.c:FSE_decompress_wksp_body_default
  - lib/zstd/common/fse_decompress.c:FSE_buildDTable_wksp
```
**Symbols:**

```
ffffffff8170a1a0-ffffffff8170a484: FSE_buildDTable_internal (STB_LOCAL)
ffffffff81e959c3-ffffffff81e95a57: FSE_buildDTable_internal.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
size_t FSE_buildDTable_internal(FSE_DTable *dt, const short int *normalizedCounter, unsigned int maxSymbolValue, unsigned int tableLog, void *workSpace, size_t wkspSize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/zstd/common/fse_decompress.c (0)
Location: lib/zstd/common/fse_decompress.c:71
Inline: False
Direct callers:
  - lib/zstd/common/fse_decompress.c:FSE_decompress_wksp_body_bmi2
  - lib/zstd/common/fse_decompress.c:FSE_decompress_wksp_body_default
  - lib/zstd/common/fse_decompress.c:FSE_buildDTable_wksp
```
**Symbols:**

```
ffffffff81884d50-ffffffff81885034: FSE_buildDTable_internal (STB_LOCAL)
ffffffff8208c02c-ffffffff8208c0c0: FSE_buildDTable_internal.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
size_t FSE_buildDTable_internal(FSE_DTable *dt, const short int *normalizedCounter, unsigned int maxSymbolValue, unsigned int tableLog, void *workSpace, size_t wkspSize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/zstd/common/fse_decompress.c (0)
Location: lib/zstd/common/fse_decompress.c:71
Inline: False
Direct callers:
  - lib/zstd/common/fse_decompress.c:FSE_decompress_wksp_body_bmi2
  - lib/zstd/common/fse_decompress.c:FSE_decompress_wksp_body_default
  - lib/zstd/common/fse_decompress.c:FSE_buildDTable_wksp
```
**Symbols:**

```
ffffffff818c7260-ffffffff818c7558: FSE_buildDTable_internal (STB_LOCAL)
ffffffff8210c3b7-ffffffff8210c45c: FSE_buildDTable_internal.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
size_t FSE_buildDTable_internal(FSE_DTable *dt, const short int *normalizedCounter, unsigned int maxSymbolValue, unsigned int tableLog, void *workSpace, size_t wkspSize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/zstd/common/fse_decompress.c (0)
Location: lib/zstd/common/fse_decompress.c:71
Inline: False
Direct callers:
  - lib/zstd/common/fse_decompress.c:FSE_decompress_wksp_body_bmi2
  - lib/zstd/common/fse_decompress.c:FSE_decompress_wksp_body_default
  - lib/zstd/common/fse_decompress.c:FSE_buildDTable_wksp
```
**Symbols:**

```
ffffffff81918e20-ffffffff81919118: FSE_buildDTable_internal (STB_LOCAL)
ffffffff821ea524-ffffffff821ea5c9: FSE_buildDTable_internal.cold (STB_LOCAL)
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
