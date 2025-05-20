# Function: <code>ZSTD_compressStream_generic</code>

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
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
size_t ZSTD_compressStream_generic(ZSTD_CStream *zcs, void *dst, size_t *dstCapacityPtr, const void *src, size_t *srcSizePtr, const ZSTD_flush_e flush);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/compress.c (ffffffff815cb833)
Location: lib/zstd/compress.c:3129
Inline: True
Inline callers:
  - lib/zstd/compress.c:ZSTD_flushStream
  - lib/zstd/compress.c:ZSTD_compressStream
Direct callers:
  - lib/zstd/compress.c:ZSTD_endStream
```
**Symbols:**

```
ffffffff815cb170-ffffffff815cb40b: ZSTD_compressStream_generic (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/zstd/compress.c (ffffffff815e87c1)
Location: lib/zstd/compress.c:3129
Inline: True
Inline callers:
  - lib/zstd/compress.c:ZSTD_endStream
  - lib/zstd/compress.c:ZSTD_flushStream
  - lib/zstd/compress.c:ZSTD_compressStream
```
</details>
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
size_t ZSTD_compressStream_generic(ZSTD_CStream *zcs, ZSTD_outBuffer *output, ZSTD_inBuffer *input, const ZSTD_EndDirective flushMode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff81719620)
Location: lib/zstd/compress/zstd_compress.c:4093
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressStream2
```
**Symbols:**

```
ffffffff81719620-ffffffff81719bb0: ZSTD_compressStream_generic (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
size_t ZSTD_compressStream_generic(ZSTD_CStream *zcs, ZSTD_outBuffer *output, ZSTD_inBuffer *input, const ZSTD_EndDirective flushMode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff8180ecf0)
Location: lib/zstd/compress/zstd_compress.c:5209
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressStream2
```
**Symbols:**

```
ffffffff8180ecf0-ffffffff8180f280: ZSTD_compressStream_generic (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
size_t ZSTD_compressStream_generic(ZSTD_CStream *zcs, ZSTD_outBuffer *output, ZSTD_inBuffer *input, const ZSTD_EndDirective flushMode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff8184f800)
Location: lib/zstd/compress/zstd_compress.c:5209
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressStream2
```
**Symbols:**

```
ffffffff8184f800-ffffffff8184fd66: ZSTD_compressStream_generic (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
size_t ZSTD_compressStream_generic(ZSTD_CStream *zcs, ZSTD_outBuffer *output, ZSTD_inBuffer *input, const ZSTD_EndDirective flushMode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff818a13c0)
Location: lib/zstd/compress/zstd_compress.c:5209
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressStream2
```
**Symbols:**

```
ffffffff818a13c0-ffffffff818a1926: ZSTD_compressStream_generic (STB_LOCAL)
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
