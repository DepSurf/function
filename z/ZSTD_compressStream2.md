# Function: <code>ZSTD_compressStream2</code>

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
size_t ZSTD_compressStream2(ZSTD_CCtx *cctx, ZSTD_outBuffer *output, ZSTD_inBuffer *input, ZSTD_EndDirective endOp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff8171c060)
Location: lib/zstd/compress/zstd_compress.c:4361
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_endStream
  - lib/zstd/compress/zstd_compress.c:ZSTD_flushStream
  - lib/zstd/compress/zstd_compress.c:ZSTD_compress2
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressStream
```
**Symbols:**

```
ffffffff8171c060-ffffffff8171c24c: ZSTD_compressStream2 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
size_t ZSTD_compressStream2(ZSTD_CCtx *cctx, ZSTD_outBuffer *output, ZSTD_inBuffer *input, ZSTD_EndDirective endOp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff81811880)
Location: lib/zstd/compress/zstd_compress.c:5480
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_endStream
  - lib/zstd/compress/zstd_compress.c:ZSTD_flushStream
  - lib/zstd/compress/zstd_compress.c:ZSTD_compress2
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressStream
```
**Symbols:**

```
ffffffff81811880-ffffffff81811a6c: ZSTD_compressStream2 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
size_t ZSTD_compressStream2(ZSTD_CCtx *cctx, ZSTD_outBuffer *output, ZSTD_inBuffer *input, ZSTD_EndDirective endOp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff81852370)
Location: lib/zstd/compress/zstd_compress.c:5480
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_endStream
  - lib/zstd/compress/zstd_compress.c:ZSTD_flushStream
  - lib/zstd/compress/zstd_compress.c:ZSTD_compress2
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressStream
```
**Symbols:**

```
ffffffff81852370-ffffffff8185255c: ZSTD_compressStream2 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
size_t ZSTD_compressStream2(ZSTD_CCtx *cctx, ZSTD_outBuffer *output, ZSTD_inBuffer *input, ZSTD_EndDirective endOp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff818a3f30)
Location: lib/zstd/compress/zstd_compress.c:5480
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_endStream
  - lib/zstd/compress/zstd_compress.c:ZSTD_flushStream
  - lib/zstd/compress/zstd_compress.c:ZSTD_compress2
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressStream
```
**Symbols:**

```
ffffffff818a3f30-ffffffff818a411c: ZSTD_compressStream2 (STB_GLOBAL)
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
