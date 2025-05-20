# Function: <code>ZSTD_DCtx_reset</code>

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
size_t ZSTD_DCtx_reset(ZSTD_DCtx *dctx, ZSTD_ResetDirective reset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress/zstd_decompress.c (ffffffff81753ea5)
Location: lib/zstd/decompress/zstd_decompress.c:1686
Inline: True
Inline callers:
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_resetDStream
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_initDStream
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_initDStream_usingDict
```
**Symbols:**

```
ffffffff817541b0-ffffffff8175426d: ZSTD_DCtx_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
size_t ZSTD_DCtx_reset(ZSTD_DCtx *dctx, ZSTD_ResetDirective reset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress/zstd_decompress.c (ffffffff81878405)
Location: lib/zstd/decompress/zstd_decompress.c:1732
Inline: True
Inline callers:
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_resetDStream
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_initDStream
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_initDStream_usingDict
```
**Symbols:**

```
ffffffff81878780-ffffffff8187883d: ZSTD_DCtx_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
size_t ZSTD_DCtx_reset(ZSTD_DCtx *dctx, ZSTD_ResetDirective reset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress/zstd_decompress.c (ffffffff818b91b5)
Location: lib/zstd/decompress/zstd_decompress.c:1751
Inline: True
Inline callers:
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_resetDStream
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_initDStream
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_initDStream_usingDict
```
**Symbols:**

```
ffffffff818b9530-ffffffff818b95ed: ZSTD_DCtx_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
size_t ZSTD_DCtx_reset(ZSTD_DCtx *dctx, ZSTD_ResetDirective reset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress/zstd_decompress.c (ffffffff8190ad75)
Location: lib/zstd/decompress/zstd_decompress.c:1751
Inline: True
Inline callers:
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_resetDStream
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_initDStream
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_initDStream_usingDict
```
**Symbols:**

```
ffffffff8190b0f0-ffffffff8190b1ad: ZSTD_DCtx_reset (STB_GLOBAL)
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
