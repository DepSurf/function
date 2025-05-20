# Function: <code>HUF_readDTableX2_wksp_bmi2</code>

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
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
size_t HUF_readDTableX2_wksp_bmi2(HUF_DTable *DTable, const void *src, size_t srcSize, void *workSpace, size_t wkspSize, int bmi2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/zstd/decompress/huf_decompress.c (0)
Location: lib/zstd/decompress/huf_decompress.c:1048
Inline: False
Direct callers:
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress1X_DCtx_wksp
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X_hufOnly_wksp
```
**Symbols:**

```
ffffffff8208b400-ffffffff8208b48c: HUF_readDTableX2_wksp_bmi2.cold (STB_LOCAL)
ffffffff818735b0-ffffffff81873b16: HUF_readDTableX2_wksp_bmi2 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
size_t HUF_readDTableX2_wksp_bmi2(HUF_DTable *DTable, const void *src, size_t srcSize, void *workSpace, size_t wkspSize, int bmi2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/zstd/decompress/huf_decompress.c (0)
Location: lib/zstd/decompress/huf_decompress.c:1048
Inline: False
Direct callers:
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress1X_DCtx_wksp
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X_hufOnly_wksp
```
**Symbols:**

```
ffffffff8210b6d6-ffffffff8210b762: HUF_readDTableX2_wksp_bmi2.cold (STB_LOCAL)
ffffffff818b4320-ffffffff818b487a: HUF_readDTableX2_wksp_bmi2 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
size_t HUF_readDTableX2_wksp_bmi2(HUF_DTable *DTable, const void *src, size_t srcSize, void *workSpace, size_t wkspSize, int bmi2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/zstd/decompress/huf_decompress.c (0)
Location: lib/zstd/decompress/huf_decompress.c:1048
Inline: False
Direct callers:
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress1X_DCtx_wksp
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress4X_hufOnly_wksp
```
**Symbols:**

```
ffffffff821e9843-ffffffff821e98cf: HUF_readDTableX2_wksp_bmi2.cold (STB_LOCAL)
ffffffff81905ee0-ffffffff8190643a: HUF_readDTableX2_wksp_bmi2 (STB_GLOBAL)
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
