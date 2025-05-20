# Function: <code>HUF_decompress4X1_DCtx_wksp</code>

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
size_t HUF_decompress4X1_DCtx_wksp(HUF_DTable *dctx, void *dst, size_t dstSize, const void *cSrc, size_t cSrcSize, void *workSpace, size_t wkspSize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress/huf_decompress.c (ffffffff8174ffae)
Location: lib/zstd/decompress/huf_decompress.c:503
Inline: True
Inline callers:
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X_hufOnly_wksp
```
**Symbols:**

```
ffffffff8174f4e0-ffffffff8174f57a: HUF_decompress4X1_DCtx_wksp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
size_t HUF_decompress4X1_DCtx_wksp(HUF_DTable *dctx, void *dst, size_t dstSize, const void *cSrc, size_t cSrcSize, void *workSpace, size_t wkspSize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress/huf_decompress.c (ffffffff818740b1)
Location: lib/zstd/decompress/huf_decompress.c:798
Inline: True
Inline callers:
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X_hufOnly_wksp
```
**Symbols:**

```
ffffffff81873500-ffffffff8187359a: HUF_decompress4X1_DCtx_wksp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
size_t HUF_decompress4X1_DCtx_wksp(HUF_DTable *dctx, void *dst, size_t dstSize, const void *cSrc, size_t cSrcSize, void *workSpace, size_t wkspSize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress/huf_decompress.c (ffffffff818b4e11)
Location: lib/zstd/decompress/huf_decompress.c:798
Inline: True
Inline callers:
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X_hufOnly_wksp
```
**Symbols:**

```
ffffffff818b4270-ffffffff818b430a: HUF_decompress4X1_DCtx_wksp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
size_t HUF_decompress4X1_DCtx_wksp(HUF_DTable *dctx, void *dst, size_t dstSize, const void *cSrc, size_t cSrcSize, void *workSpace, size_t wkspSize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress/huf_decompress.c (ffffffff819069d1)
Location: lib/zstd/decompress/huf_decompress.c:798
Inline: True
Inline callers:
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X_hufOnly_wksp
```
**Symbols:**

```
ffffffff81905e30-ffffffff81905eca: HUF_decompress4X1_DCtx_wksp (STB_GLOBAL)
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
