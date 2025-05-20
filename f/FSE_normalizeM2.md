# Function: <code>FSE_normalizeM2</code>

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
In lib/zstd/fse_compress.c (ffffffff815acc6f)
Location: lib/zstd/fse_compress.c:519
Inline: True
Inline callers:
  - lib/zstd/fse_compress.c:FSE_normalizeCount
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
In lib/zstd/fse_compress.c (ffffffff815c87b4)
Location: lib/zstd/fse_compress.c:519
Inline: True
Inline callers:
  - lib/zstd/fse_compress.c:FSE_normalizeCount
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
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
size_t FSE_normalizeM2(short int *norm, U32 tableLog, const unsigned int *count, size_t total, U32 maxSymbolValue, short int lowProbCount);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/zstd/compress/fse_compress.c (0)
Location: lib/zstd/compress/fse_compress.c:344
Inline: False
Direct callers:
  - lib/zstd/compress/fse_compress.c:FSE_normalizeCount
```
**Symbols:**

```
ffffffff8170d750-ffffffff8170da18: FSE_normalizeM2 (STB_LOCAL)
ffffffff81e95dd1-ffffffff81e95f25: FSE_normalizeM2.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
size_t FSE_normalizeM2(short int *norm, U32 tableLog, const unsigned int *count, size_t total, U32 maxSymbolValue, short int lowProbCount);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/zstd/compress/fse_compress.c (0)
Location: lib/zstd/compress/fse_compress.c:387
Inline: False
Direct callers:
  - lib/zstd/compress/fse_compress.c:FSE_normalizeCount
```
**Symbols:**

```
ffffffff817fc6b0-ffffffff817fc978: FSE_normalizeM2 (STB_LOCAL)
ffffffff8207aaff-ffffffff8207ac53: FSE_normalizeM2.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
size_t FSE_normalizeM2(short int *norm, U32 tableLog, const unsigned int *count, size_t total, U32 maxSymbolValue, short int lowProbCount);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/zstd/compress/fse_compress.c (0)
Location: lib/zstd/compress/fse_compress.c:387
Inline: False
Direct callers:
  - lib/zstd/compress/fse_compress.c:FSE_normalizeCount
```
**Symbols:**

```
ffffffff8183d090-ffffffff8183d350: FSE_normalizeM2 (STB_LOCAL)
ffffffff820fb26b-ffffffff820fb3b0: FSE_normalizeM2.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
size_t FSE_normalizeM2(short int *norm, U32 tableLog, const unsigned int *count, size_t total, U32 maxSymbolValue, short int lowProbCount);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/zstd/compress/fse_compress.c (0)
Location: lib/zstd/compress/fse_compress.c:387
Inline: False
Direct callers:
  - lib/zstd/compress/fse_compress.c:FSE_normalizeCount
```
**Symbols:**

```
ffffffff8188ec50-ffffffff8188ef10: FSE_normalizeM2 (STB_LOCAL)
ffffffff821d93d8-ffffffff821d951d: FSE_normalizeM2.cold (STB_LOCAL)
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
