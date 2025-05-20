# Function: <code>ZSTD_buildSeqStore</code>

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
size_t ZSTD_buildSeqStore(ZSTD_CCtx *zc, const void *src, size_t srcSize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff81711fe0)
Location: lib/zstd/compress/zstd_compress.c:2391
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_compress_frameChunk
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressBlock_internal
```
**Symbols:**

```
ffffffff81711fe0-ffffffff81712306: ZSTD_buildSeqStore (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
size_t ZSTD_buildSeqStore(ZSTD_CCtx *zc, const void *src, size_t srcSize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff81806160)
Location: lib/zstd/compress/zstd_compress.c:2723
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_compress_frameChunk
  - lib/zstd/compress/zstd_compress.c:ZSTD_compress_frameChunk
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressBlock_internal
```
**Symbols:**

```
ffffffff81806160-ffffffff81806517: ZSTD_buildSeqStore (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
size_t ZSTD_buildSeqStore(ZSTD_CCtx *zc, const void *src, size_t srcSize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff81846b50)
Location: lib/zstd/compress/zstd_compress.c:2723
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_compress_frameChunk
  - lib/zstd/compress/zstd_compress.c:ZSTD_compress_frameChunk
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressBlock_internal
```
**Symbols:**

```
ffffffff81846b50-ffffffff81846ee9: ZSTD_buildSeqStore (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
size_t ZSTD_buildSeqStore(ZSTD_CCtx *zc, const void *src, size_t srcSize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff81898710)
Location: lib/zstd/compress/zstd_compress.c:2723
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_compress_frameChunk
  - lib/zstd/compress/zstd_compress.c:ZSTD_compress_frameChunk
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressBlock_internal
```
**Symbols:**

```
ffffffff81898710-ffffffff81898aa9: ZSTD_buildSeqStore (STB_LOCAL)
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
