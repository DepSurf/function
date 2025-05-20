# Function: <code>ZSTD_compressRleLiteralsBlock</code>

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
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/zstd/compress.c (ffffffff815c9aa3)
Location: lib/zstd/compress.c:462
Inline: True
Inline callers:
  - lib/zstd/compress.c:ZSTD_compressSequences_internal
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
In lib/zstd/compress.c (ffffffff815e7666)
Location: lib/zstd/compress.c:462
Inline: True
Inline callers:
  - lib/zstd/compress.c:ZSTD_compressSequences_internal
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
size_t ZSTD_compressRleLiteralsBlock(void *dst, size_t dstCapacity, const void *src, size_t srcSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress_literals.c (ffffffff8171c970)
Location: lib/zstd/compress/zstd_compress_literals.c:43
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress_literals.c:ZSTD_compressLiterals
```
**Symbols:**

```
ffffffff8171c970-ffffffff8171ca08: ZSTD_compressRleLiteralsBlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
size_t ZSTD_compressRleLiteralsBlock(void *dst, size_t dstCapacity, const void *src, size_t srcSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress_literals.c (ffffffff81812290)
Location: lib/zstd/compress/zstd_compress_literals.c:43
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress_literals.c:ZSTD_compressLiterals
```
**Symbols:**

```
ffffffff81812290-ffffffff81812328: ZSTD_compressRleLiteralsBlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
size_t ZSTD_compressRleLiteralsBlock(void *dst, size_t dstCapacity, const void *src, size_t srcSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress_literals.c (ffffffff81852d90)
Location: lib/zstd/compress/zstd_compress_literals.c:43
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress_literals.c:ZSTD_compressLiterals
```
**Symbols:**

```
ffffffff81852d90-ffffffff81852e28: ZSTD_compressRleLiteralsBlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
size_t ZSTD_compressRleLiteralsBlock(void *dst, size_t dstCapacity, const void *src, size_t srcSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress_literals.c (ffffffff818a4950)
Location: lib/zstd/compress/zstd_compress_literals.c:43
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress_literals.c:ZSTD_compressLiterals
```
**Symbols:**

```
ffffffff818a4950-ffffffff818a49e8: ZSTD_compressRleLiteralsBlock (STB_GLOBAL)
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
