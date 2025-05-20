# Function: <code>ZSTD_findFrameCompressedSize</code>

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
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
size_t ZSTD_findFrameCompressedSize(const void *src, size_t srcSize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (ffffffff814b1e43)
Location: lib/zstd/decompress.c:1510
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_findDecompressedSize
Direct callers:
  - lib/zstd/decompress.c:ZSTD_decompressStream
```
**Symbols:**

```
ffffffff814b24d0-ffffffff814b27db: ZSTD_findFrameCompressedSize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
size_t ZSTD_findFrameCompressedSize(const void *src, size_t srcSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (ffffffff814e5e30)
Location: lib/zstd/decompress.c:1510
Inline: False
Direct callers:
  - lib/zstd/decompress.c:ZSTD_decompressStream
  - lib/zstd/decompress.c:ZSTD_findDecompressedSize
```
**Symbols:**

```
ffffffff814e5e30-ffffffff814e5fac: ZSTD_findFrameCompressedSize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
size_t ZSTD_findFrameCompressedSize(const void *src, size_t srcSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (ffffffff814f9b20)
Location: lib/zstd/decompress.c:1510
Inline: False
Direct callers:
  - lib/zstd/decompress.c:ZSTD_decompressStream
  - lib/zstd/decompress.c:ZSTD_findDecompressedSize
```
**Symbols:**

```
ffffffff814f9b20-ffffffff814f9c9c: ZSTD_findFrameCompressedSize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
size_t ZSTD_findFrameCompressedSize(const void *src, size_t srcSize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (ffffffff81527bf0)
Location: lib/zstd/decompress.c:1510
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_findDecompressedSize
Direct callers:
  - lib/zstd/decompress.c:ZSTD_decompressStream
```
**Symbols:**

```
ffffffff81527170-ffffffff815272da: ZSTD_findFrameCompressedSize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
size_t ZSTD_findFrameCompressedSize(const void *src, size_t srcSize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (ffffffff81548a80)
Location: lib/zstd/decompress.c:1510
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_findDecompressedSize
Direct callers:
  - lib/zstd/decompress.c:ZSTD_decompressStream
```
**Symbols:**

```
ffffffff81548000-ffffffff8154816a: ZSTD_findFrameCompressedSize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
size_t ZSTD_findFrameCompressedSize(const void *src, size_t srcSize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (ffffffff815d41c5)
Location: lib/zstd/decompress.c:1510
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_findDecompressedSize
Direct callers:
  - lib/zstd/decompress.c:ZSTD_decompressStream
```
**Symbols:**

```
ffffffff815d3910-ffffffff815d3a83: ZSTD_findFrameCompressedSize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
size_t ZSTD_findFrameCompressedSize(const void *src, size_t srcSize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (ffffffff815f1e4a)
Location: lib/zstd/decompress.c:1510
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_findDecompressedSize
Direct callers:
  - lib/zstd/decompress.c:ZSTD_decompressStream
  - lib/decompress_unzstd.c:decompress_single
```
**Symbols:**

```
ffffffff815f15b0-ffffffff815f1728: ZSTD_findFrameCompressedSize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
size_t ZSTD_findFrameCompressedSize(const void *src, size_t srcSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (ffffffff815d2e80)
Location: lib/zstd/decompress.c:1510
Inline: False
Direct callers:
  - lib/zstd/decompress.c:ZSTD_decompressStream
  - lib/zstd/decompress.c:ZSTD_findDecompressedSize
```
**Symbols:**

```
ffffffff815d2e80-ffffffff815d2fee: ZSTD_findFrameCompressedSize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
size_t ZSTD_findFrameCompressedSize(const void *src, size_t srcSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (ffffffff8163da00)
Location: lib/zstd/decompress.c:1510
Inline: False
Direct callers:
  - lib/zstd/decompress.c:ZSTD_decompressStream
  - lib/zstd/decompress.c:ZSTD_findDecompressedSize
```
**Symbols:**

```
ffffffff8163da00-ffffffff8163dbaf: ZSTD_findFrameCompressedSize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
size_t ZSTD_findFrameCompressedSize(const void *src, size_t srcSize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress/zstd_decompress.c (ffffffff81754bb1)
Location: lib/zstd/decompress/zstd_decompress.c:700
Inline: True
Inline callers:
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_decompressStream
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_findDecompressedSize
Direct callers:
  - lib/zstd/zstd_decompress_module.c:zstd_find_frame_compressed_size
```
**Symbols:**

```
ffffffff81752840-ffffffff8175285a: ZSTD_findFrameCompressedSize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
size_t ZSTD_findFrameCompressedSize(const void *src, size_t srcSize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress/zstd_decompress.c (ffffffff81879275)
Location: lib/zstd/decompress/zstd_decompress.c:746
Inline: True
Inline callers:
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_decompressStream
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_findDecompressedSize
Direct callers:
  - lib/zstd/zstd_decompress_module.c:zstd_find_frame_compressed_size
```
**Symbols:**

```
ffffffff81876cb0-ffffffff81876cca: ZSTD_findFrameCompressedSize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
size_t ZSTD_findFrameCompressedSize(const void *src, size_t srcSize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress/zstd_decompress.c (ffffffff818ba031)
Location: lib/zstd/decompress/zstd_decompress.c:746
Inline: True
Inline callers:
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_decompressStream
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_findDecompressedSize
Direct callers:
  - lib/zstd/zstd_decompress_module.c:zstd_find_frame_compressed_size
```
**Symbols:**

```
ffffffff818b7a60-ffffffff818b7a7a: ZSTD_findFrameCompressedSize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
size_t ZSTD_findFrameCompressedSize(const void *src, size_t srcSize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress/zstd_decompress.c (ffffffff8190bbf1)
Location: lib/zstd/decompress/zstd_decompress.c:746
Inline: True
Inline callers:
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_decompressStream
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_findDecompressedSize
Direct callers:
  - lib/zstd/zstd_decompress_module.c:zstd_find_frame_compressed_size
```
**Symbols:**

```
ffffffff81909620-ffffffff8190963a: ZSTD_findFrameCompressedSize (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
size_t ZSTD_findFrameCompressedSize(const void *src, size_t srcSize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (ffff800010654d4c)
Location: lib/zstd/decompress.c:1510
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_findDecompressedSize
Direct callers:
  - lib/zstd/decompress.c:ZSTD_decompressStream
```
**Symbols:**

```
ffff800010654228-ffff80001065439c: ZSTD_findFrameCompressedSize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
size_t ZSTD_findFrameCompressedSize(const void *src, size_t srcSize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (c07ffd58)
Location: lib/zstd/decompress.c:1510
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_findDecompressedSize
Direct callers:
  - lib/zstd/decompress.c:ZSTD_decompressStream
```
**Symbols:**

```
c07ff298-c07ff424: ZSTD_findFrameCompressedSize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
size_t ZSTD_findFrameCompressedSize(const void *src, size_t srcSize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (c000000000804afc)
Location: lib/zstd/decompress.c:1510
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_findDecompressedSize
Direct callers:
  - lib/zstd/decompress.c:ZSTD_decompressStream
```
**Symbols:**

```
c000000000803d00-c000000000803f28: ZSTD_findFrameCompressedSize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
size_t ZSTD_findFrameCompressedSize(const void *src, size_t srcSize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (ffffffe000482738)
Location: lib/zstd/decompress.c:1510
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_findDecompressedSize
Direct callers:
  - lib/zstd/decompress.c:ZSTD_decompressStream
```
**Symbols:**

```
ffffffe000481e4a-ffffffe000481f94: ZSTD_findFrameCompressedSize (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
size_t ZSTD_findFrameCompressedSize(const void *src, size_t srcSize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (ffffffff81541060)
Location: lib/zstd/decompress.c:1510
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_findDecompressedSize
Direct callers:
  - lib/zstd/decompress.c:ZSTD_decompressStream
```
**Symbols:**

```
ffffffff815405e0-ffffffff8154074a: ZSTD_findFrameCompressedSize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
size_t ZSTD_findFrameCompressedSize(const void *src, size_t srcSize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (ffffffff81531340)
Location: lib/zstd/decompress.c:1510
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_findDecompressedSize
Direct callers:
  - lib/zstd/decompress.c:ZSTD_decompressStream
```
**Symbols:**

```
ffffffff815308c0-ffffffff81530a2a: ZSTD_findFrameCompressedSize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
size_t ZSTD_findFrameCompressedSize(const void *src, size_t srcSize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (ffffffff8153cda0)
Location: lib/zstd/decompress.c:1510
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_findDecompressedSize
Direct callers:
  - lib/zstd/decompress.c:ZSTD_decompressStream
```
**Symbols:**

```
ffffffff8153c320-ffffffff8153c48a: ZSTD_findFrameCompressedSize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
size_t ZSTD_findFrameCompressedSize(const void *src, size_t srcSize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (ffffffff81556bd0)
Location: lib/zstd/decompress.c:1510
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_findDecompressedSize
Direct callers:
  - lib/zstd/decompress.c:ZSTD_decompressStream
```
**Symbols:**

```
ffffffff81556150-ffffffff815562ba: ZSTD_findFrameCompressedSize (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
