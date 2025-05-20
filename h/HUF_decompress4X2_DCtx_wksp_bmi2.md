# Function: <code>HUF_decompress4X2_DCtx_wksp_bmi2</code>

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
size_t HUF_decompress4X2_DCtx_wksp_bmi2(HUF_DTable *dctx, void *dst, size_t dstSize, const void *cSrc, size_t cSrcSize, void *workSpace, size_t wkspSize, int bmi2);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress/huf_decompress.c (ffffffff8174ff54)
Location: lib/zstd/decompress/huf_decompress.c:957
Inline: True
Inline callers:
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X_hufOnly_wksp
Direct callers:
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X_hufOnly_wksp_bmi2
```
**Symbols:**

```
ffffffff8174fb00-ffffffff8174fbc0: HUF_decompress4X2_DCtx_wksp_bmi2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
size_t HUF_decompress4X2_DCtx_wksp_bmi2(HUF_DTable *dctx, void *dst, size_t dstSize, const void *cSrc, size_t cSrcSize, void *workSpace, size_t wkspSize, int bmi2);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress/huf_decompress.c (ffffffff81874064)
Location: lib/zstd/decompress/huf_decompress.c:1491
Inline: True
Inline callers:
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X_hufOnly_wksp
Direct callers:
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X_hufOnly_wksp_bmi2
```
**Symbols:**

```
ffffffff81873b70-ffffffff81873c33: HUF_decompress4X2_DCtx_wksp_bmi2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
size_t HUF_decompress4X2_DCtx_wksp_bmi2(HUF_DTable *dctx, void *dst, size_t dstSize, const void *cSrc, size_t cSrcSize, void *workSpace, size_t wkspSize, int bmi2);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress/huf_decompress.c (ffffffff818b4dc4)
Location: lib/zstd/decompress/huf_decompress.c:1491
Inline: True
Inline callers:
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X_hufOnly_wksp
Direct callers:
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X_hufOnly_wksp_bmi2
```
**Symbols:**

```
ffffffff818b48d0-ffffffff818b4993: HUF_decompress4X2_DCtx_wksp_bmi2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
size_t HUF_decompress4X2_DCtx_wksp_bmi2(HUF_DTable *dctx, void *dst, size_t dstSize, const void *cSrc, size_t cSrcSize, void *workSpace, size_t wkspSize, int bmi2);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress/huf_decompress.c (ffffffff81906984)
Location: lib/zstd/decompress/huf_decompress.c:1491
Inline: True
Inline callers:
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X_hufOnly_wksp
Direct callers:
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X_hufOnly_wksp_bmi2
```
**Symbols:**

```
ffffffff81906490-ffffffff81906553: HUF_decompress4X2_DCtx_wksp_bmi2 (STB_LOCAL)
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
