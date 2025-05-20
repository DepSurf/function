# Function: <code>ZSTD_DCtx_refDDict</code>

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
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
size_t ZSTD_DCtx_refDDict(ZSTD_DCtx *dctx, const ZSTD_DDict *ddict);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/zstd/decompress/zstd_decompress.c (ffffffff81753e01)
Location: lib/zstd/decompress/zstd_decompress.c:1542
Inline: True
Inline callers:
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_initDStream
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_initDStream
```
**Symbols:**

```
ffffffff81750e50-ffffffff81751050: ZSTD_DCtx_refDDict.part.0 (STB_LOCAL)
ffffffff81753ee0-ffffffff81753f12: ZSTD_DCtx_refDDict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
size_t ZSTD_DCtx_refDDict(ZSTD_DCtx *dctx, const ZSTD_DDict *ddict);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/zstd/decompress/zstd_decompress.c (ffffffff81878341)
Location: lib/zstd/decompress/zstd_decompress.c:1588
Inline: True
Inline callers:
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_initDStream
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_initDStream
```
**Symbols:**

```
ffffffff818750b0-ffffffff818752b0: ZSTD_DCtx_refDDict.part.0 (STB_LOCAL)
ffffffff81878450-ffffffff81878482: ZSTD_DCtx_refDDict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
size_t ZSTD_DCtx_refDDict(ZSTD_DCtx *dctx, const ZSTD_DDict *ddict);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/zstd/decompress/zstd_decompress.c (ffffffff818b90f1)
Location: lib/zstd/decompress/zstd_decompress.c:1607
Inline: True
Inline callers:
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_initDStream
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_initDStream
```
**Symbols:**

```
ffffffff818b5e00-ffffffff818b6000: ZSTD_DCtx_refDDict.part.0 (STB_LOCAL)
ffffffff818b9200-ffffffff818b9232: ZSTD_DCtx_refDDict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
size_t ZSTD_DCtx_refDDict(ZSTD_DCtx *dctx, const ZSTD_DDict *ddict);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/zstd/decompress/zstd_decompress.c (ffffffff8190acb1)
Location: lib/zstd/decompress/zstd_decompress.c:1607
Inline: True
Inline callers:
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_initDStream
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_initDStream
```
**Symbols:**

```
ffffffff819079c0-ffffffff81907bc0: ZSTD_DCtx_refDDict.part.0 (STB_LOCAL)
ffffffff8190adc0-ffffffff8190adf2: ZSTD_DCtx_refDDict (STB_GLOBAL)
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
