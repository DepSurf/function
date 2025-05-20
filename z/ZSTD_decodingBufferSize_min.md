# Function: <code>ZSTD_decodingBufferSize_min</code>

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
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
size_t ZSTD_decodingBufferSize_min(long long unsigned int windowSize, long long unsigned int frameContentSize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress/zstd_decompress.c (ffffffff81754901)
Location: lib/zstd/decompress/zstd_decompress.c:1708
Inline: True
Inline callers:
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_decompressStream
```
**Symbols:**

```
ffffffff817542c0-ffffffff817542eb: ZSTD_decodingBufferSize_min (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
size_t ZSTD_decodingBufferSize_min(long long unsigned int windowSize, long long unsigned int frameContentSize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress/zstd_decompress.c (ffffffff81878fcd)
Location: lib/zstd/decompress/zstd_decompress.c:1754
Inline: True
Inline callers:
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_decompressStream
```
**Symbols:**

```
ffffffff818788b0-ffffffff818788de: ZSTD_decodingBufferSize_min (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
size_t ZSTD_decodingBufferSize_min(long long unsigned int windowSize, long long unsigned int frameContentSize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress/zstd_decompress.c (ffffffff818b9d7d)
Location: lib/zstd/decompress/zstd_decompress.c:1773
Inline: True
Inline callers:
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_decompressStream
```
**Symbols:**

```
ffffffff818b9660-ffffffff818b968e: ZSTD_decodingBufferSize_min (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
size_t ZSTD_decodingBufferSize_min(long long unsigned int windowSize, long long unsigned int frameContentSize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress/zstd_decompress.c (ffffffff8190b93d)
Location: lib/zstd/decompress/zstd_decompress.c:1773
Inline: True
Inline callers:
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_decompressStream
```
**Symbols:**

```
ffffffff8190b220-ffffffff8190b24e: ZSTD_decodingBufferSize_min (STB_GLOBAL)
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
