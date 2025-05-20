# Function: <code>FSE_compress_usingCTable_generic</code>

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
size_t FSE_compress_usingCTable_generic(void *dst, size_t dstSize, const void *src, size_t srcSize, const FSE_CTable *ct, const unsigned int fast);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/fse_compress.c (ffffffff815abcf0)
Location: lib/zstd/fse_compress.c:724
Inline: False
Direct callers:
  - lib/zstd/fse_compress.c:FSE_compress_usingCTable
  - lib/zstd/fse_compress.c:FSE_compress_usingCTable
```
**Symbols:**

```
ffffffff815abcf0-ffffffff815ac211: FSE_compress_usingCTable_generic (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
size_t FSE_compress_usingCTable_generic(void *dst, size_t dstSize, const void *src, size_t srcSize, const FSE_CTable *ct, const unsigned int fast);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/fse_compress.c (ffffffff815c77f0)
Location: lib/zstd/fse_compress.c:724
Inline: False
Direct callers:
  - lib/zstd/fse_compress.c:FSE_compress_usingCTable
  - lib/zstd/fse_compress.c:FSE_compress_usingCTable
```
**Symbols:**

```
ffffffff815c77f0-ffffffff815c7d03: FSE_compress_usingCTable_generic (STB_LOCAL)
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
size_t FSE_compress_usingCTable_generic(void *dst, size_t dstSize, const void *src, size_t srcSize, const FSE_CTable *ct, const unsigned int fast);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/zstd/compress/fse_compress.c (0)
Location: lib/zstd/compress/fse_compress.c:550
Inline: False
Direct callers:
  - lib/zstd/compress/fse_compress.c:FSE_compress_usingCTable
  - lib/zstd/compress/fse_compress.c:FSE_compress_usingCTable
```
**Symbols:**

```
ffffffff8170da20-ffffffff8170e56a: FSE_compress_usingCTable_generic (STB_LOCAL)
ffffffff81e95f25-ffffffff81e9683a: FSE_compress_usingCTable_generic.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
size_t FSE_compress_usingCTable_generic(void *dst, size_t dstSize, const void *src, size_t srcSize, const FSE_CTable *ct, const unsigned int fast);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/zstd/compress/fse_compress.c (0)
Location: lib/zstd/compress/fse_compress.c:593
Inline: False
Direct callers:
  - lib/zstd/compress/fse_compress.c:FSE_compress_usingCTable
  - lib/zstd/compress/fse_compress.c:FSE_compress_usingCTable
```
**Symbols:**

```
ffffffff817fc990-ffffffff817fd4da: FSE_compress_usingCTable_generic (STB_LOCAL)
ffffffff8207ac53-ffffffff8207b568: FSE_compress_usingCTable_generic.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
size_t FSE_compress_usingCTable_generic(void *dst, size_t dstSize, const void *src, size_t srcSize, const FSE_CTable *ct, const unsigned int fast);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/zstd/compress/fse_compress.c (0)
Location: lib/zstd/compress/fse_compress.c:593
Inline: False
Direct callers:
  - lib/zstd/compress/fse_compress.c:FSE_compress_usingCTable
  - lib/zstd/compress/fse_compress.c:FSE_compress_usingCTable
```
**Symbols:**

```
ffffffff8183d360-ffffffff8183dd15: FSE_compress_usingCTable_generic (STB_LOCAL)
ffffffff820fb3b0-ffffffff820fbb1f: FSE_compress_usingCTable_generic.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
size_t FSE_compress_usingCTable_generic(void *dst, size_t dstSize, const void *src, size_t srcSize, const FSE_CTable *ct, const unsigned int fast);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/zstd/compress/fse_compress.c (0)
Location: lib/zstd/compress/fse_compress.c:593
Inline: False
Direct callers:
  - lib/zstd/compress/fse_compress.c:FSE_compress_usingCTable
  - lib/zstd/compress/fse_compress.c:FSE_compress_usingCTable
```
**Symbols:**

```
ffffffff8188ef20-ffffffff8188f8d5: FSE_compress_usingCTable_generic (STB_LOCAL)
ffffffff821d951d-ffffffff821d9c8c: FSE_compress_usingCTable_generic.cold (STB_LOCAL)
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
