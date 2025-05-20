# Function: <code>ZSTD_compressSuperBlock</code>

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
size_t ZSTD_compressSuperBlock(ZSTD_CCtx *zc, void *dst, size_t dstCapacity, const void *src, size_t srcSize, unsigned int lastBlock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress_superblock.c (ffffffff81720b10)
Location: lib/zstd/compress/zstd_compress_superblock.c:830
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_compress_frameChunk
```
**Symbols:**

```
ffffffff81720b10-ffffffff81720cb6: ZSTD_compressSuperBlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
size_t ZSTD_compressSuperBlock(ZSTD_CCtx *zc, void *dst, size_t dstCapacity, const void *src, size_t srcSize, unsigned int lastBlock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress_superblock.c (ffffffff81815de0)
Location: lib/zstd/compress/zstd_compress_superblock.c:551
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_compress_frameChunk
```
**Symbols:**

```
ffffffff81815de0-ffffffff81815ef5: ZSTD_compressSuperBlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
size_t ZSTD_compressSuperBlock(ZSTD_CCtx *zc, void *dst, size_t dstCapacity, const void *src, size_t srcSize, unsigned int lastBlock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress_superblock.c (ffffffff81856500)
Location: lib/zstd/compress/zstd_compress_superblock.c:551
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_compress_frameChunk
```
**Symbols:**

```
ffffffff81856500-ffffffff81856615: ZSTD_compressSuperBlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
size_t ZSTD_compressSuperBlock(ZSTD_CCtx *zc, void *dst, size_t dstCapacity, const void *src, size_t srcSize, unsigned int lastBlock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress_superblock.c (ffffffff818a80c0)
Location: lib/zstd/compress/zstd_compress_superblock.c:551
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_compress_frameChunk
```
**Symbols:**

```
ffffffff818a80c0-ffffffff818a81d5: ZSTD_compressSuperBlock (STB_GLOBAL)
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
