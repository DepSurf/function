# Function: <code>HUF_optimalTableLog</code>

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
unsigned int HUF_optimalTableLog(unsigned int maxTableLog, size_t srcSize, unsigned int maxSymbolValue);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/huf_compress.c (ffffffff815af042)
Location: lib/zstd/huf_compress.c:68
Inline: True
Inline callers:
  - lib/zstd/huf_compress.c:HUF_compress4X_wksp
  - lib/zstd/huf_compress.c:HUF_compress1X_wksp
```
**Symbols:**

```
ffffffff815ad6a0-ffffffff815ad6b0: HUF_optimalTableLog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
unsigned int HUF_optimalTableLog(unsigned int maxTableLog, size_t srcSize, unsigned int maxSymbolValue);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/huf_compress.c (ffffffff815cabe7)
Location: lib/zstd/huf_compress.c:68
Inline: True
Inline callers:
  - lib/zstd/huf_compress.c:HUF_compress4X_wksp
  - lib/zstd/huf_compress.c:HUF_compress1X_wksp
```
**Symbols:**

```
ffffffff815c9200-ffffffff815c9215: HUF_optimalTableLog (STB_GLOBAL)
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
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
unsigned int HUF_optimalTableLog(unsigned int maxTableLog, size_t srcSize, unsigned int maxSymbolValue);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/huf_compress.c (ffffffff81711041)
Location: lib/zstd/compress/huf_compress.c:44
Inline: True
Inline callers:
  - lib/zstd/compress/huf_compress.c:HUF_compress_internal
```
**Symbols:**

```
ffffffff817101c0-ffffffff817101e1: HUF_optimalTableLog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
unsigned int HUF_optimalTableLog(unsigned int maxTableLog, size_t srcSize, unsigned int maxSymbolValue);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/huf_compress.c (ffffffff818039cc)
Location: lib/zstd/compress/huf_compress.c:44
Inline: True
Inline callers:
  - lib/zstd/compress/huf_compress.c:HUF_compress_internal
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_buildBlockEntropyStats_literals
```
**Symbols:**

```
ffffffff818028d0-ffffffff818028f1: HUF_optimalTableLog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
unsigned int HUF_optimalTableLog(unsigned int maxTableLog, size_t srcSize, unsigned int maxSymbolValue);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/huf_compress.c (ffffffff818443bc)
Location: lib/zstd/compress/huf_compress.c:44
Inline: True
Inline callers:
  - lib/zstd/compress/huf_compress.c:HUF_compress_internal
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_buildBlockEntropyStats_literals
```
**Symbols:**

```
ffffffff818431c0-ffffffff818431e1: HUF_optimalTableLog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
unsigned int HUF_optimalTableLog(unsigned int maxTableLog, size_t srcSize, unsigned int maxSymbolValue);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/huf_compress.c (ffffffff81895f7c)
Location: lib/zstd/compress/huf_compress.c:44
Inline: True
Inline callers:
  - lib/zstd/compress/huf_compress.c:HUF_compress_internal
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_buildBlockEntropyStats_literals
```
**Symbols:**

```
ffffffff81894d80-ffffffff81894da1: HUF_optimalTableLog (STB_GLOBAL)
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
