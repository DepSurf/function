# Function: <code>FSE_compress_usingCTable</code>

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
size_t FSE_compress_usingCTable(void *dst, size_t dstSize, const void *src, size_t srcSize, const FSE_CTable *ct);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/fse_compress.c (ffffffff815acef0)
Location: lib/zstd/fse_compress.c:785
Inline: False
Direct callers:
  - lib/zstd/huf_compress.c:HUF_compressWeights_wksp
  - lib/zstd/huf_compress.c:HUF_compressWeights_wksp
```
**Symbols:**

```
ffffffff815acef0-ffffffff815acf1a: FSE_compress_usingCTable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
size_t FSE_compress_usingCTable(void *dst, size_t dstSize, const void *src, size_t srcSize, const FSE_CTable *ct);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/fse_compress.c (ffffffff815c8a40)
Location: lib/zstd/fse_compress.c:785
Inline: False
Direct callers:
  - lib/zstd/huf_compress.c:HUF_compressWeights_wksp
  - lib/zstd/huf_compress.c:HUF_compressWeights_wksp
```
**Symbols:**

```
ffffffff815c8a40-ffffffff815c8a6f: FSE_compress_usingCTable (STB_GLOBAL)
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
size_t FSE_compress_usingCTable(void *dst, size_t dstSize, const void *src, size_t srcSize, const FSE_CTable *ct);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/fse_compress.c (ffffffff8170ed60)
Location: lib/zstd/compress/fse_compress.c:609
Inline: False
Direct callers:
  - lib/zstd/compress/huf_compress.c:HUF_writeCTable_wksp
```
**Symbols:**

```
ffffffff8170ed60-ffffffff8170edb5: FSE_compress_usingCTable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
size_t FSE_compress_usingCTable(void *dst, size_t dstSize, const void *src, size_t srcSize, const FSE_CTable *ct);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/fse_compress.c (ffffffff817fddf0)
Location: lib/zstd/compress/fse_compress.c:652
Inline: False
Direct callers:
  - lib/zstd/compress/huf_compress.c:HUF_writeCTable_wksp
```
**Symbols:**

```
ffffffff817fddf0-ffffffff817fde45: FSE_compress_usingCTable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
size_t FSE_compress_usingCTable(void *dst, size_t dstSize, const void *src, size_t srcSize, const FSE_CTable *ct);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/fse_compress.c (ffffffff8183e640)
Location: lib/zstd/compress/fse_compress.c:652
Inline: False
Direct callers:
  - lib/zstd/compress/huf_compress.c:HUF_writeCTable_wksp
```
**Symbols:**

```
ffffffff8183e640-ffffffff8183e695: FSE_compress_usingCTable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
size_t FSE_compress_usingCTable(void *dst, size_t dstSize, const void *src, size_t srcSize, const FSE_CTable *ct);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/fse_compress.c (ffffffff81890200)
Location: lib/zstd/compress/fse_compress.c:652
Inline: False
Direct callers:
  - lib/zstd/compress/huf_compress.c:HUF_writeCTable_wksp
```
**Symbols:**

```
ffffffff81890200-ffffffff81890255: FSE_compress_usingCTable (STB_GLOBAL)
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
