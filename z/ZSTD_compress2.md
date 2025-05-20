# Function: <code>ZSTD_compress2</code>

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
size_t ZSTD_compress2(ZSTD_CCtx *cctx, void *dst, size_t dstCapacity, const void *src, size_t srcSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff8171c340)
Location: lib/zstd/compress/zstd_compress.c:4403
Inline: False
Direct callers:
  - lib/zstd/zstd_compress_module.c:zstd_compress_cctx
  - lib/zstd/compress/zstd_compress.c:ZSTD_generateSequences
```
**Symbols:**

```
ffffffff8171c340-ffffffff8171c40c: ZSTD_compress2 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
size_t ZSTD_compress2(ZSTD_CCtx *cctx, void *dst, size_t dstCapacity, const void *src, size_t srcSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff81811b90)
Location: lib/zstd/compress/zstd_compress.c:5522
Inline: False
Direct callers:
  - lib/zstd/zstd_compress_module.c:zstd_compress_cctx
  - lib/zstd/compress/zstd_compress.c:ZSTD_generateSequences
```
**Symbols:**

```
ffffffff81811b90-ffffffff81811c5c: ZSTD_compress2 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
size_t ZSTD_compress2(ZSTD_CCtx *cctx, void *dst, size_t dstCapacity, const void *src, size_t srcSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff81852680)
Location: lib/zstd/compress/zstd_compress.c:5522
Inline: False
Direct callers:
  - lib/zstd/zstd_compress_module.c:zstd_compress_cctx
  - lib/zstd/compress/zstd_compress.c:ZSTD_generateSequences
```
**Symbols:**

```
ffffffff81852680-ffffffff81852754: ZSTD_compress2 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
size_t ZSTD_compress2(ZSTD_CCtx *cctx, void *dst, size_t dstCapacity, const void *src, size_t srcSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff818a4240)
Location: lib/zstd/compress/zstd_compress.c:5522
Inline: False
Direct callers:
  - lib/zstd/zstd_compress_module.c:zstd_compress_cctx
  - lib/zstd/compress/zstd_compress.c:ZSTD_generateSequences
```
**Symbols:**

```
ffffffff818a4240-ffffffff818a4314: ZSTD_compress2 (STB_GLOBAL)
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
