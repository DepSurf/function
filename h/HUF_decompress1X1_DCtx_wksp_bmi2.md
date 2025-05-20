# Function: <code>HUF_decompress1X1_DCtx_wksp_bmi2</code>

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
size_t HUF_decompress1X1_DCtx_wksp_bmi2(HUF_DTable *dctx, void *dst, size_t dstSize, const void *cSrc, size_t cSrcSize, void *workSpace, size_t wkspSize, int bmi2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress/huf_decompress.c (ffffffff81750230)
Location: lib/zstd/decompress/huf_decompress.c:1155
Inline: False
Direct callers:
  - lib/zstd/decompress/zstd_decompress_block.c:ZSTD_decodeLiteralsBlock
```
**Symbols:**

```
ffffffff81750230-ffffffff817502f4: HUF_decompress1X1_DCtx_wksp_bmi2 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
size_t HUF_decompress1X1_DCtx_wksp_bmi2(HUF_DTable *dctx, void *dst, size_t dstSize, const void *cSrc, size_t cSrcSize, void *workSpace, size_t wkspSize, int bmi2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress/huf_decompress.c (ffffffff81874350)
Location: lib/zstd/decompress/huf_decompress.c:1689
Inline: False
Direct callers:
  - lib/zstd/decompress/zstd_decompress_block.c:ZSTD_decodeLiteralsBlock
```
**Symbols:**

```
ffffffff81874350-ffffffff81874414: HUF_decompress1X1_DCtx_wksp_bmi2 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
size_t HUF_decompress1X1_DCtx_wksp_bmi2(HUF_DTable *dctx, void *dst, size_t dstSize, const void *cSrc, size_t cSrcSize, void *workSpace, size_t wkspSize, int bmi2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress/huf_decompress.c (ffffffff818b50b0)
Location: lib/zstd/decompress/huf_decompress.c:1689
Inline: False
Direct callers:
  - lib/zstd/decompress/zstd_decompress_block.c:ZSTD_decodeLiteralsBlock
```
**Symbols:**

```
ffffffff818b50b0-ffffffff818b5174: HUF_decompress1X1_DCtx_wksp_bmi2 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
size_t HUF_decompress1X1_DCtx_wksp_bmi2(HUF_DTable *dctx, void *dst, size_t dstSize, const void *cSrc, size_t cSrcSize, void *workSpace, size_t wkspSize, int bmi2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress/huf_decompress.c (ffffffff81906c70)
Location: lib/zstd/decompress/huf_decompress.c:1689
Inline: False
Direct callers:
  - lib/zstd/decompress/zstd_decompress_block.c:ZSTD_decodeLiteralsBlock
```
**Symbols:**

```
ffffffff81906c70-ffffffff81906d34: HUF_decompress1X1_DCtx_wksp_bmi2 (STB_GLOBAL)
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
