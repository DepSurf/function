# Function: <code>ZSTD_CCtx_setParameter</code>

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
size_t ZSTD_CCtx_setParameter(ZSTD_CCtx *cctx, ZSTD_cParameter param, int value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff8171c01d)
Location: lib/zstd/compress/zstd_compress.c:531
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_initCStream
  - lib/zstd/compress/zstd_compress.c:ZSTD_initCStream_srcSize
  - lib/zstd/compress/zstd_compress.c:ZSTD_initCStream_usingDict
```
**Symbols:**

```
ffffffff81715e70-ffffffff81715f85: ZSTD_CCtx_setParameter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
size_t ZSTD_CCtx_setParameter(ZSTD_CCtx *cctx, ZSTD_cParameter param, int value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff8181182d)
Location: lib/zstd/compress/zstd_compress.c:621
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_initCStream
  - lib/zstd/compress/zstd_compress.c:ZSTD_initCStream_srcSize
  - lib/zstd/compress/zstd_compress.c:ZSTD_initCStream_usingDict
```
**Symbols:**

```
ffffffff81809e00-ffffffff81809f15: ZSTD_CCtx_setParameter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
size_t ZSTD_CCtx_setParameter(ZSTD_CCtx *cctx, ZSTD_cParameter param, int value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff8185231d)
Location: lib/zstd/compress/zstd_compress.c:621
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_initCStream
  - lib/zstd/compress/zstd_compress.c:ZSTD_initCStream_srcSize
  - lib/zstd/compress/zstd_compress.c:ZSTD_initCStream_usingDict
```
**Symbols:**

```
ffffffff8184a820-ffffffff8184a935: ZSTD_CCtx_setParameter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
size_t ZSTD_CCtx_setParameter(ZSTD_CCtx *cctx, ZSTD_cParameter param, int value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff818a3edd)
Location: lib/zstd/compress/zstd_compress.c:621
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_initCStream
  - lib/zstd/compress/zstd_compress.c:ZSTD_initCStream_srcSize
  - lib/zstd/compress/zstd_compress.c:ZSTD_initCStream_usingDict
```
**Symbols:**

```
ffffffff8189c3e0-ffffffff8189c4f5: ZSTD_CCtx_setParameter (STB_GLOBAL)
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
