# Function: <code>FSE_buildCTable_rle</code>

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
size_t FSE_buildCTable_rle(FSE_CTable *ct, BYTE symbolValue);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/fse_compress.c (ffffffff815acec0)
Location: lib/zstd/fse_compress.c:702
Inline: False
Direct callers:
  - lib/zstd/compress.c:ZSTD_compressSequences_internal
  - lib/zstd/compress.c:ZSTD_compressSequences_internal
  - lib/zstd/compress.c:ZSTD_compressSequences_internal
```
**Symbols:**

```
ffffffff815acec0-ffffffff815acee4: FSE_buildCTable_rle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
size_t FSE_buildCTable_rle(FSE_CTable *ct, BYTE symbolValue);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/fse_compress.c (ffffffff815c8a10)
Location: lib/zstd/fse_compress.c:702
Inline: False
Direct callers:
  - lib/zstd/compress.c:ZSTD_compressSequences_internal
  - lib/zstd/compress.c:ZSTD_compressSequences_internal
  - lib/zstd/compress.c:ZSTD_compressSequences_internal
```
**Symbols:**

```
ffffffff815c8a10-ffffffff815c8a3e: FSE_buildCTable_rle (STB_GLOBAL)
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
size_t FSE_buildCTable_rle(FSE_CTable *ct, BYTE symbolValue);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/fse_compress.c (ffffffff8170ed20)
Location: lib/zstd/compress/fse_compress.c:527
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress_sequences.c:ZSTD_buildCTable
```
**Symbols:**

```
ffffffff8170ed20-ffffffff8170ed56: FSE_buildCTable_rle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
size_t FSE_buildCTable_rle(FSE_CTable *ct, BYTE symbolValue);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/fse_compress.c (ffffffff817fdda0)
Location: lib/zstd/compress/fse_compress.c:570
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress_sequences.c:ZSTD_buildCTable
```
**Symbols:**

```
ffffffff817fdda0-ffffffff817fddd6: FSE_buildCTable_rle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
size_t FSE_buildCTable_rle(FSE_CTable *ct, BYTE symbolValue);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/fse_compress.c (ffffffff8183e5f0)
Location: lib/zstd/compress/fse_compress.c:570
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress_sequences.c:ZSTD_buildCTable
```
**Symbols:**

```
ffffffff8183e5f0-ffffffff8183e626: FSE_buildCTable_rle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
size_t FSE_buildCTable_rle(FSE_CTable *ct, BYTE symbolValue);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/fse_compress.c (ffffffff818901b0)
Location: lib/zstd/compress/fse_compress.c:570
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress_sequences.c:ZSTD_buildCTable
```
**Symbols:**

```
ffffffff818901b0-ffffffff818901e6: FSE_buildCTable_rle (STB_GLOBAL)
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
