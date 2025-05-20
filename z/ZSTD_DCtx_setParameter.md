# Function: <code>ZSTD_DCtx_setParameter</code>

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
size_t ZSTD_DCtx_setParameter(ZSTD_DCtx *dctx, ZSTD_dParameter dParam, int value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress/zstd_decompress.c (ffffffff81753f75)
Location: lib/zstd/decompress/zstd_decompress.c:1653
Inline: True
Inline callers:
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_DCtx_setFormat
```
**Symbols:**

```
ffffffff81754090-ffffffff817541af: ZSTD_DCtx_setParameter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
size_t ZSTD_DCtx_setParameter(ZSTD_DCtx *dctx, ZSTD_dParameter dParam, int value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress/zstd_decompress.c (ffffffff81878505)
Location: lib/zstd/decompress/zstd_decompress.c:1699
Inline: True
Inline callers:
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_DCtx_setFormat
```
**Symbols:**

```
ffffffff81878650-ffffffff8187876f: ZSTD_DCtx_setParameter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
size_t ZSTD_DCtx_setParameter(ZSTD_DCtx *dctx, ZSTD_dParameter dParam, int value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress/zstd_decompress.c (ffffffff818b92b5)
Location: lib/zstd/decompress/zstd_decompress.c:1718
Inline: True
Inline callers:
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_DCtx_setFormat
```
**Symbols:**

```
ffffffff818b9410-ffffffff818b9515: ZSTD_DCtx_setParameter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
size_t ZSTD_DCtx_setParameter(ZSTD_DCtx *dctx, ZSTD_dParameter dParam, int value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress/zstd_decompress.c (ffffffff8190ae75)
Location: lib/zstd/decompress/zstd_decompress.c:1718
Inline: True
Inline callers:
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_DCtx_setFormat
```
**Symbols:**

```
ffffffff8190afd0-ffffffff8190b0d5: ZSTD_DCtx_setParameter (STB_GLOBAL)
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
