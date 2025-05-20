# Function: <code>FSE_decompress_wksp_bmi2</code>

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
size_t FSE_decompress_wksp_bmi2(void *dst, size_t dstCapacity, const void *cSrc, size_t cSrcSize, unsigned int maxLog, void *workSpace, size_t wkspSize, int bmi2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/common/fse_decompress.c (ffffffff8170d279)
Location: lib/zstd/common/fse_decompress.c:374
Inline: True
Inline callers:
  - lib/zstd/common/fse_decompress.c:FSE_decompress_wksp
Direct callers:
  - lib/zstd/common/entropy_common.c:HUF_readStats_body_bmi2
  - lib/zstd/common/entropy_common.c:HUF_readStats_body_default
```
**Symbols:**

```
ffffffff8170d2a0-ffffffff8170d2f2: FSE_decompress_wksp_bmi2 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
size_t FSE_decompress_wksp_bmi2(void *dst, size_t dstCapacity, const void *cSrc, size_t cSrcSize, unsigned int maxLog, void *workSpace, size_t wkspSize, int bmi2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/common/fse_decompress.c (ffffffff81887829)
Location: lib/zstd/common/fse_decompress.c:374
Inline: True
Inline callers:
  - lib/zstd/common/fse_decompress.c:FSE_decompress_wksp
Direct callers:
  - lib/zstd/common/entropy_common.c:HUF_readStats_body_bmi2
  - lib/zstd/common/entropy_common.c:HUF_readStats_body_default
```
**Symbols:**

```
ffffffff81887860-ffffffff818878b2: FSE_decompress_wksp_bmi2 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
size_t FSE_decompress_wksp_bmi2(void *dst, size_t dstCapacity, const void *cSrc, size_t cSrcSize, unsigned int maxLog, void *workSpace, size_t wkspSize, int bmi2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/common/fse_decompress.c (ffffffff818c9ba9)
Location: lib/zstd/common/fse_decompress.c:374
Inline: True
Inline callers:
  - lib/zstd/common/fse_decompress.c:FSE_decompress_wksp
Direct callers:
  - lib/zstd/common/entropy_common.c:HUF_readStats_body_bmi2
  - lib/zstd/common/entropy_common.c:HUF_readStats_body_default
```
**Symbols:**

```
ffffffff818c9be0-ffffffff818c9c32: FSE_decompress_wksp_bmi2 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
size_t FSE_decompress_wksp_bmi2(void *dst, size_t dstCapacity, const void *cSrc, size_t cSrcSize, unsigned int maxLog, void *workSpace, size_t wkspSize, int bmi2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/common/fse_decompress.c (ffffffff8191b769)
Location: lib/zstd/common/fse_decompress.c:374
Inline: True
Inline callers:
  - lib/zstd/common/fse_decompress.c:FSE_decompress_wksp
Direct callers:
  - lib/zstd/common/entropy_common.c:HUF_readStats_body_bmi2
  - lib/zstd/common/entropy_common.c:HUF_readStats_body_default
```
**Symbols:**

```
ffffffff8191b7a0-ffffffff8191b7f2: FSE_decompress_wksp_bmi2 (STB_GLOBAL)
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
