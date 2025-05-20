# Function: <code>ZSTD_noCompressLiterals</code>

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
size_t ZSTD_noCompressLiterals(void *dst, size_t dstCapacity, const void *src, size_t srcSize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress.c (ffffffff815af9b0)
Location: lib/zstd/compress.c:443
Inline: False
Direct callers:
  - lib/zstd/compress.c:ZSTD_compressSequences_internal
  - lib/zstd/compress.c:ZSTD_compressSequences_internal
```
**Symbols:**

```
ffffffff815af9b0-ffffffff815afa45: ZSTD_noCompressLiterals (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
size_t ZSTD_noCompressLiterals(void *dst, size_t dstCapacity, const void *src, size_t srcSize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress.c (ffffffff815cb640)
Location: lib/zstd/compress.c:443
Inline: False
Direct callers:
  - lib/zstd/compress.c:ZSTD_compressSequences_internal
  - lib/zstd/compress.c:ZSTD_compressSequences_internal
```
**Symbols:**

```
ffffffff815cb640-ffffffff815cb6da: ZSTD_noCompressLiterals (STB_LOCAL)
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
size_t ZSTD_noCompressLiterals(void *dst, size_t dstCapacity, const void *src, size_t srcSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress_literals.c (ffffffff8171c8b0)
Location: lib/zstd/compress/zstd_compress_literals.c:16
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress_literals.c:ZSTD_compressLiterals
```
**Symbols:**

```
ffffffff8171c8b0-ffffffff8171c961: ZSTD_noCompressLiterals (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
size_t ZSTD_noCompressLiterals(void *dst, size_t dstCapacity, const void *src, size_t srcSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress_literals.c (ffffffff818121c0)
Location: lib/zstd/compress/zstd_compress_literals.c:16
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress_literals.c:ZSTD_compressLiterals
```
**Symbols:**

```
ffffffff818121c0-ffffffff81812271: ZSTD_noCompressLiterals (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
size_t ZSTD_noCompressLiterals(void *dst, size_t dstCapacity, const void *src, size_t srcSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress_literals.c (ffffffff81852cc0)
Location: lib/zstd/compress/zstd_compress_literals.c:16
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress_literals.c:ZSTD_compressLiterals
```
**Symbols:**

```
ffffffff81852cc0-ffffffff81852d71: ZSTD_noCompressLiterals (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
size_t ZSTD_noCompressLiterals(void *dst, size_t dstCapacity, const void *src, size_t srcSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress_literals.c (ffffffff818a4880)
Location: lib/zstd/compress/zstd_compress_literals.c:16
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress_literals.c:ZSTD_compressLiterals
```
**Symbols:**

```
ffffffff818a4880-ffffffff818a4931: ZSTD_noCompressLiterals (STB_GLOBAL)
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
