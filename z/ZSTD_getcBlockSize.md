# Function: <code>ZSTD_getcBlockSize</code>

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
size_t ZSTD_getcBlockSize(const void *src, size_t srcSize, blockProperties_t *bpPtr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (ffffffff814b85ec)
Location: lib/zstd/decompress.c:394
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_decompressStream
  - lib/zstd/decompress.c:ZSTD_decompressContinue
  - lib/zstd/decompress.c:ZSTD_decompressDCtx
  - lib/zstd/decompress.c:ZSTD_findDecompressedSize
```
**Symbols:**

```
ffffffff814b4b10-ffffffff814b4b5e: ZSTD_getcBlockSize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
size_t ZSTD_getcBlockSize(const void *src, size_t srcSize, blockProperties_t *bpPtr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (ffffffff814e9baf)
Location: lib/zstd/decompress.c:394
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_decompressContinue
  - lib/zstd/decompress.c:ZSTD_decompressDCtx
  - lib/zstd/decompress.c:ZSTD_findFrameCompressedSize
```
**Symbols:**

```
ffffffff814e7400-ffffffff814e7449: ZSTD_getcBlockSize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
size_t ZSTD_getcBlockSize(const void *src, size_t srcSize, blockProperties_t *bpPtr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (ffffffff814fd7e2)
Location: lib/zstd/decompress.c:394
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_decompressContinue
  - lib/zstd/decompress.c:ZSTD_decompressDCtx
  - lib/zstd/decompress.c:ZSTD_findFrameCompressedSize
```
**Symbols:**

```
ffffffff814fb0f0-ffffffff814fb139: ZSTD_getcBlockSize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
size_t ZSTD_getcBlockSize(const void *src, size_t srcSize, blockProperties_t *bpPtr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (ffffffff8152af96)
Location: lib/zstd/decompress.c:394
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_decompressContinue
  - lib/zstd/decompress.c:ZSTD_decompressDCtx
  - lib/zstd/decompress.c:ZSTD_findDecompressedSize
```
**Symbols:**

```
ffffffff815288e0-ffffffff81528929: ZSTD_getcBlockSize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
size_t ZSTD_getcBlockSize(const void *src, size_t srcSize, blockProperties_t *bpPtr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (ffffffff8154be26)
Location: lib/zstd/decompress.c:394
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_decompressContinue
  - lib/zstd/decompress.c:ZSTD_decompressDCtx
  - lib/zstd/decompress.c:ZSTD_findDecompressedSize
```
**Symbols:**

```
ffffffff81549770-ffffffff815497b9: ZSTD_getcBlockSize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
size_t ZSTD_getcBlockSize(const void *src, size_t srcSize, blockProperties_t *bpPtr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (ffffffff815d7709)
Location: lib/zstd/decompress.c:394
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_decompressContinue
  - lib/zstd/decompress.c:ZSTD_decompressMultiFrame
  - lib/zstd/decompress.c:ZSTD_findDecompressedSize
```
**Symbols:**

```
ffffffff815d5070-ffffffff815d50bd: ZSTD_getcBlockSize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
size_t ZSTD_getcBlockSize(const void *src, size_t srcSize, blockProperties_t *bpPtr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (ffffffff815f530e)
Location: lib/zstd/decompress.c:394
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_decompressContinue
  - lib/zstd/decompress.c:ZSTD_decompressMultiFrame
  - lib/zstd/decompress.c:ZSTD_findDecompressedSize
```
**Symbols:**

```
ffffffff815f2d20-ffffffff815f2d77: ZSTD_getcBlockSize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
size_t ZSTD_getcBlockSize(const void *src, size_t srcSize, blockProperties_t *bpPtr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (ffffffff815d6aeb)
Location: lib/zstd/decompress.c:394
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_decompressContinue
  - lib/zstd/decompress.c:ZSTD_decompressMultiFrame
  - lib/zstd/decompress.c:ZSTD_findFrameCompressedSize
```
**Symbols:**

```
ffffffff815d4130-ffffffff815d4187: ZSTD_getcBlockSize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
size_t ZSTD_getcBlockSize(const void *src, size_t srcSize, blockProperties_t *bpPtr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (ffffffff81641d5d)
Location: lib/zstd/decompress.c:394
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_decompressContinue
  - lib/zstd/decompress.c:ZSTD_decompressMultiFrame
  - lib/zstd/decompress.c:ZSTD_findFrameCompressedSize
```
**Symbols:**

```
ffffffff8163ef30-ffffffff8163ef87: ZSTD_getcBlockSize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
size_t ZSTD_getcBlockSize(const void *src, size_t srcSize, blockProperties_t *bpPtr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress/zstd_decompress_block.c (ffffffff81759c90)
Location: lib/zstd/decompress/zstd_decompress_block.c:56
Inline: False
Direct callers:
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_decompressFrame
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_findFrameSizeInfo
```
**Symbols:**

```
ffffffff81759c90-ffffffff81759cf2: ZSTD_getcBlockSize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
size_t ZSTD_getcBlockSize(const void *src, size_t srcSize, blockProperties_t *bpPtr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress/zstd_decompress_block.c (ffffffff81883140)
Location: lib/zstd/decompress/zstd_decompress_block.c:56
Inline: False
Direct callers:
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_decompressFrame
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_findFrameSizeInfo
```
**Symbols:**

```
ffffffff81883140-ffffffff818831a2: ZSTD_getcBlockSize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
size_t ZSTD_getcBlockSize(const void *src, size_t srcSize, blockProperties_t *bpPtr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress/zstd_decompress_block.c (ffffffff818c5640)
Location: lib/zstd/decompress/zstd_decompress_block.c:56
Inline: False
Direct callers:
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_decompressFrame
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_findFrameSizeInfo
```
**Symbols:**

```
ffffffff818c5640-ffffffff818c56a2: ZSTD_getcBlockSize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
size_t ZSTD_getcBlockSize(const void *src, size_t srcSize, blockProperties_t *bpPtr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress/zstd_decompress_block.c (ffffffff81917200)
Location: lib/zstd/decompress/zstd_decompress_block.c:56
Inline: False
Direct callers:
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_decompressFrame
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_findFrameSizeInfo
```
**Symbols:**

```
ffffffff81917200-ffffffff81917262: ZSTD_getcBlockSize (STB_GLOBAL)
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
size_t ZSTD_getcBlockSize(const void *src, size_t srcSize, blockProperties_t *bpPtr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (ffff800010657fd8)
Location: lib/zstd/decompress.c:394
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_decompressContinue
  - lib/zstd/decompress.c:ZSTD_decompressDCtx
  - lib/zstd/decompress.c:ZSTD_findDecompressedSize
```
**Symbols:**

```
ffff8000106559c0-ffff800010655a10: ZSTD_getcBlockSize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
size_t ZSTD_getcBlockSize(const void *src, size_t srcSize, blockProperties_t *bpPtr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (c0801a44)
Location: lib/zstd/decompress.c:394
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_decompressContinue
  - lib/zstd/decompress.c:ZSTD_decompressDCtx
  - lib/zstd/decompress.c:ZSTD_findDecompressedSize
```
**Symbols:**

```
c0800358-c08003b4: ZSTD_getcBlockSize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
size_t ZSTD_getcBlockSize(const void *src, size_t srcSize, blockProperties_t *bpPtr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (c000000000808660)
Location: lib/zstd/decompress.c:394
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_decompressContinue
  - lib/zstd/decompress.c:ZSTD_decompressDCtx
  - lib/zstd/decompress.c:ZSTD_findDecompressedSize
```
**Symbols:**

```
c000000000805b90-c000000000805bf8: ZSTD_getcBlockSize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
size_t ZSTD_getcBlockSize(const void *src, size_t srcSize, blockProperties_t *bpPtr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (ffffffe000485ec6)
Location: lib/zstd/decompress.c:394
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_decompressContinue
  - lib/zstd/decompress.c:ZSTD_decompressDCtx
  - lib/zstd/decompress.c:ZSTD_findDecompressedSize
```
**Symbols:**

```
ffffffe000483690-ffffffe0004836e8: ZSTD_getcBlockSize (STB_GLOBAL)
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
size_t ZSTD_getcBlockSize(const void *src, size_t srcSize, blockProperties_t *bpPtr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (ffffffff81544406)
Location: lib/zstd/decompress.c:394
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_decompressContinue
  - lib/zstd/decompress.c:ZSTD_decompressDCtx
  - lib/zstd/decompress.c:ZSTD_findDecompressedSize
```
**Symbols:**

```
ffffffff81541d50-ffffffff81541d99: ZSTD_getcBlockSize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
size_t ZSTD_getcBlockSize(const void *src, size_t srcSize, blockProperties_t *bpPtr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (ffffffff815346e6)
Location: lib/zstd/decompress.c:394
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_decompressContinue
  - lib/zstd/decompress.c:ZSTD_decompressDCtx
  - lib/zstd/decompress.c:ZSTD_findDecompressedSize
```
**Symbols:**

```
ffffffff81532030-ffffffff81532079: ZSTD_getcBlockSize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
size_t ZSTD_getcBlockSize(const void *src, size_t srcSize, blockProperties_t *bpPtr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (ffffffff81540146)
Location: lib/zstd/decompress.c:394
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_decompressContinue
  - lib/zstd/decompress.c:ZSTD_decompressDCtx
  - lib/zstd/decompress.c:ZSTD_findDecompressedSize
```
**Symbols:**

```
ffffffff8153da90-ffffffff8153dad9: ZSTD_getcBlockSize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
size_t ZSTD_getcBlockSize(const void *src, size_t srcSize, blockProperties_t *bpPtr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (ffffffff81559f76)
Location: lib/zstd/decompress.c:394
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_decompressContinue
  - lib/zstd/decompress.c:ZSTD_decompressDCtx
  - lib/zstd/decompress.c:ZSTD_findDecompressedSize
```
**Symbols:**

```
ffffffff815578c0-ffffffff81557909: ZSTD_getcBlockSize (STB_GLOBAL)
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
