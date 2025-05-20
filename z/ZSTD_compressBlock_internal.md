# Function: <code>ZSTD_compressBlock_internal</code>

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
<summary>In <code>5.8</code>: ✅</summary>

```c
size_t ZSTD_compressBlock_internal(ZSTD_CCtx *zc, void *dst, size_t dstCapacity, const void *src, size_t srcSize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress.c (ffffffff815c9f50)
Location: lib/zstd/compress.c:2333
Inline: False
Direct callers:
  - lib/zstd/compress.c:ZSTD_compressContinue_internal
```
**Symbols:**

```
ffffffff815c9f50-ffffffff815ca05b: ZSTD_compressBlock_internal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
size_t ZSTD_compressBlock_internal(ZSTD_CCtx *zc, void *dst, size_t dstCapacity, const void *src, size_t srcSize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress.c (ffffffff815e7b20)
Location: lib/zstd/compress.c:2333
Inline: False
Direct callers:
  - lib/zstd/compress.c:ZSTD_compressContinue_internal
```
**Symbols:**

```
ffffffff815e7b20-ffffffff815e7c30: ZSTD_compressBlock_internal (STB_LOCAL)
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
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
size_t ZSTD_compressBlock_internal(ZSTD_CCtx *zc, void *dst, size_t dstCapacity, const void *src, size_t srcSize, U32 frame);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (0)
Location: lib/zstd/compress/zstd_compress.c:2612
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressContinue_internal
  - lib/zstd/compress/zstd_compress.c:ZSTD_compress_frameChunk
```
**Symbols:**

```
ffffffff81717570-ffffffff817177bd: ZSTD_compressBlock_internal (STB_LOCAL)
ffffffff81e97352-ffffffff81e97376: ZSTD_compressBlock_internal.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
size_t ZSTD_compressBlock_internal(ZSTD_CCtx *zc, void *dst, size_t dstCapacity, const void *src, size_t srcSize, U32 frame);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (0)
Location: lib/zstd/compress/zstd_compress.c:3672
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressContinue_internal
  - lib/zstd/compress/zstd_compress.c:ZSTD_compress_frameChunk
```
**Symbols:**

```
ffffffff8180c1d0-ffffffff8180c3cd: ZSTD_compressBlock_internal (STB_LOCAL)
ffffffff8207df7c-ffffffff8207dfa0: ZSTD_compressBlock_internal.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
size_t ZSTD_compressBlock_internal(ZSTD_CCtx *zc, void *dst, size_t dstCapacity, const void *src, size_t srcSize, U32 frame);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (0)
Location: lib/zstd/compress/zstd_compress.c:3672
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressContinue_internal
  - lib/zstd/compress/zstd_compress.c:ZSTD_compress_frameChunk
```
**Symbols:**

```
ffffffff8184cc70-ffffffff8184ce6d: ZSTD_compressBlock_internal (STB_LOCAL)
ffffffff820fe4f3-ffffffff820fe517: ZSTD_compressBlock_internal.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
size_t ZSTD_compressBlock_internal(ZSTD_CCtx *zc, void *dst, size_t dstCapacity, const void *src, size_t srcSize, U32 frame);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (0)
Location: lib/zstd/compress/zstd_compress.c:3672
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressContinue_internal
  - lib/zstd/compress/zstd_compress.c:ZSTD_compress_frameChunk
```
**Symbols:**

```
ffffffff8189e830-ffffffff8189ea2d: ZSTD_compressBlock_internal (STB_LOCAL)
ffffffff821dc660-ffffffff821dc684: ZSTD_compressBlock_internal.cold (STB_LOCAL)
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
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
