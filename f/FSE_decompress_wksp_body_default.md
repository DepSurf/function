# Function: <code>FSE_decompress_wksp_body_default</code>

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
size_t FSE_decompress_wksp_body_default(void *dst, size_t dstCapacity, const void *cSrc, size_t cSrcSize, unsigned int maxLog, void *workSpace, size_t wkspSize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/zstd/common/fse_decompress.c (0)
Location: lib/zstd/common/fse_decompress.c:362
Inline: False
Direct callers:
  - lib/zstd/common/fse_decompress.c:FSE_decompress_wksp
```
**Symbols:**

```
ffffffff8170b4c0-ffffffff8170c38d: FSE_decompress_wksp_body_default (STB_LOCAL)
ffffffff81e95b80-ffffffff81e95c77: FSE_decompress_wksp_body_default.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
size_t FSE_decompress_wksp_body_default(void *dst, size_t dstCapacity, const void *cSrc, size_t cSrcSize, unsigned int maxLog, void *workSpace, size_t wkspSize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/zstd/common/fse_decompress.c (0)
Location: lib/zstd/common/fse_decompress.c:362
Inline: False
Direct callers:
  - lib/zstd/common/fse_decompress.c:FSE_decompress_wksp
```
**Symbols:**

```
ffffffff81885e00-ffffffff81886ab3: FSE_decompress_wksp_body_default (STB_LOCAL)
ffffffff8208c4ff-ffffffff8208c89e: FSE_decompress_wksp_body_default.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
size_t FSE_decompress_wksp_body_default(void *dst, size_t dstCapacity, const void *cSrc, size_t cSrcSize, unsigned int maxLog, void *workSpace, size_t wkspSize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/zstd/common/fse_decompress.c (0)
Location: lib/zstd/common/fse_decompress.c:362
Inline: False
Direct callers:
  - lib/zstd/common/fse_decompress.c:FSE_decompress_wksp
```
**Symbols:**

```
ffffffff818c82a0-ffffffff818c8ed5: FSE_decompress_wksp_body_default (STB_LOCAL)
ffffffff8210c87e-ffffffff8210cc20: FSE_decompress_wksp_body_default.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
size_t FSE_decompress_wksp_body_default(void *dst, size_t dstCapacity, const void *cSrc, size_t cSrcSize, unsigned int maxLog, void *workSpace, size_t wkspSize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/zstd/common/fse_decompress.c (0)
Location: lib/zstd/common/fse_decompress.c:362
Inline: False
Direct callers:
  - lib/zstd/common/fse_decompress.c:FSE_decompress_wksp
```
**Symbols:**

```
ffffffff81919e60-ffffffff8191aa95: FSE_decompress_wksp_body_default (STB_LOCAL)
ffffffff821ea9eb-ffffffff821ead8d: FSE_decompress_wksp_body_default.cold (STB_LOCAL)
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
