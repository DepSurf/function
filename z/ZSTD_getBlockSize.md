# Function: <code>ZSTD_getBlockSize</code>

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
size_t ZSTD_getBlockSize(const ZSTD_CCtx *cctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff81718715)
Location: lib/zstd/compress/zstd_compress.c:3030
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressBlock
```
**Symbols:**

```
ffffffff81e973f8-ffffffff81e97451: ZSTD_getBlockSize.cold (STB_LOCAL)
ffffffff817186c0-ffffffff81718701: ZSTD_getBlockSize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
size_t ZSTD_getBlockSize(const ZSTD_CCtx *cctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff8180db35)
Location: lib/zstd/compress/zstd_compress.c:4090
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressBlock
```
**Symbols:**

```
ffffffff8207dffa-ffffffff8207e053: ZSTD_getBlockSize.cold (STB_LOCAL)
ffffffff8180dad0-ffffffff8180db11: ZSTD_getBlockSize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
size_t ZSTD_getBlockSize(const ZSTD_CCtx *cctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff8184e5d5)
Location: lib/zstd/compress/zstd_compress.c:4090
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressBlock
```
**Symbols:**

```
ffffffff820fe571-ffffffff820fe5ca: ZSTD_getBlockSize.cold (STB_LOCAL)
ffffffff8184e570-ffffffff8184e5b1: ZSTD_getBlockSize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
size_t ZSTD_getBlockSize(const ZSTD_CCtx *cctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff818a0195)
Location: lib/zstd/compress/zstd_compress.c:4090
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressBlock
```
**Symbols:**

```
ffffffff821dc6de-ffffffff821dc737: ZSTD_getBlockSize.cold (STB_LOCAL)
ffffffff818a0130-ffffffff818a0171: ZSTD_getBlockSize (STB_GLOBAL)
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
