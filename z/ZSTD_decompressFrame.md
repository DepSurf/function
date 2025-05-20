# Function: <code>ZSTD_decompressFrame</code>

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
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (ffffffff814b81bb)
Location: lib/zstd/decompress.c:1566
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_decompressStream
  - lib/zstd/decompress.c:ZSTD_decompressDCtx
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (ffffffff814ead46)
Location: lib/zstd/decompress.c:1566
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_decompressDCtx
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (ffffffff814fea96)
Location: lib/zstd/decompress.c:1566
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_decompressDCtx
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (ffffffff8152c67c)
Location: lib/zstd/decompress.c:1566
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_decompressDCtx
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (ffffffff8154d50c)
Location: lib/zstd/decompress.c:1566
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_decompressDCtx
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (ffffffff815d7e5f)
Location: lib/zstd/decompress.c:1566
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_decompressMultiFrame
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
In lib/zstd/decompress.c (ffffffff815f5a64)
Location: lib/zstd/decompress.c:1566
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_decompressMultiFrame
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (ffffffff815d7226)
Location: lib/zstd/decompress.c:1566
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_decompressMultiFrame
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (ffffffff816424aa)
Location: lib/zstd/decompress.c:1566
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_decompressMultiFrame
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
size_t ZSTD_decompressFrame(ZSTD_DCtx *dctx, void *dst, size_t dstCapacity, const void **srcPtr, size_t *srcSizePtr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress/zstd_decompress.c (ffffffff81751a60)
Location: lib/zstd/decompress/zstd_decompress.c:785
Inline: False
Direct callers:
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_decompressMultiFrame
```
**Symbols:**

```
ffffffff81751a60-ffffffff81751dd3: ZSTD_decompressFrame (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
size_t ZSTD_decompressFrame(ZSTD_DCtx *dctx, void *dst, size_t dstCapacity, const void **srcPtr, size_t *srcSizePtr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress/zstd_decompress.c (ffffffff81875d00)
Location: lib/zstd/decompress/zstd_decompress.c:831
Inline: False
Direct callers:
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_decompressMultiFrame
```
**Symbols:**

```
ffffffff81875d00-ffffffff81876077: ZSTD_decompressFrame (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
size_t ZSTD_decompressFrame(ZSTD_DCtx *dctx, void *dst, size_t dstCapacity, const void **srcPtr, size_t *srcSizePtr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress/zstd_decompress.c (ffffffff818b6a60)
Location: lib/zstd/decompress/zstd_decompress.c:831
Inline: False
Direct callers:
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_decompressMultiFrame
```
**Symbols:**

```
ffffffff818b6a60-ffffffff818b6e0a: ZSTD_decompressFrame (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
size_t ZSTD_decompressFrame(ZSTD_DCtx *dctx, void *dst, size_t dstCapacity, const void **srcPtr, size_t *srcSizePtr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress/zstd_decompress.c (ffffffff81908620)
Location: lib/zstd/decompress/zstd_decompress.c:831
Inline: False
Direct callers:
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_decompressMultiFrame
```
**Symbols:**

```
ffffffff81908620-ffffffff819089ca: ZSTD_decompressFrame (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (ffff800010659520)
Location: lib/zstd/decompress.c:1566
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_decompressDCtx
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (c0802d6c)
Location: lib/zstd/decompress.c:1566
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_decompressDCtx
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (c000000000809fb4)
Location: lib/zstd/decompress.c:1566
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_decompressDCtx
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (ffffffe00048701c)
Location: lib/zstd/decompress.c:1566
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_decompressDCtx
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (ffffffff81545aec)
Location: lib/zstd/decompress.c:1566
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_decompressDCtx
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (ffffffff81535dcc)
Location: lib/zstd/decompress.c:1566
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_decompressDCtx
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (ffffffff8154182c)
Location: lib/zstd/decompress.c:1566
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_decompressDCtx
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (ffffffff8155b65c)
Location: lib/zstd/decompress.c:1566
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_decompressDCtx
```
</details>
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
