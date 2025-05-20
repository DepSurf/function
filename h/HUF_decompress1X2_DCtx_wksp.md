# Function: <code>HUF_decompress1X2_DCtx_wksp</code>

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
size_t HUF_decompress1X2_DCtx_wksp(HUF_DTable *DCtx, void *dst, size_t dstSize, const void *cSrc, size_t cSrcSize, void *workspace, size_t workspaceSize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/huf_decompress.c (ffffffff814b0c9c)
Location: lib/zstd/huf_decompress.c:232
Inline: True
Inline callers:
  - lib/zstd/huf_decompress.c:HUF_decompress1X_DCtx_wksp
Direct callers:
  - lib/zstd/decompress.c:ZSTD_decompressContinue
  - lib/zstd/decompress.c:ZSTD_decompressBlock
```
**Symbols:**

```
ffffffff814af680-ffffffff814af86c: HUF_decompress1X2_DCtx_wksp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
size_t HUF_decompress1X2_DCtx_wksp(HUF_DTable *DCtx, void *dst, size_t dstSize, const void *cSrc, size_t cSrcSize, void *workspace, size_t workspaceSize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/huf_decompress.c (ffffffff814e573a)
Location: lib/zstd/huf_decompress.c:232
Inline: True
Inline callers:
  - lib/zstd/huf_decompress.c:HUF_decompress1X_DCtx_wksp
Direct callers:
  - lib/zstd/decompress.c:ZSTD_decodeLiteralsBlock
```
**Symbols:**

```
ffffffff814e4c10-ffffffff814e4c8e: HUF_decompress1X2_DCtx_wksp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
size_t HUF_decompress1X2_DCtx_wksp(HUF_DTable *DCtx, void *dst, size_t dstSize, const void *cSrc, size_t cSrcSize, void *workspace, size_t workspaceSize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/huf_decompress.c (ffffffff814f942a)
Location: lib/zstd/huf_decompress.c:232
Inline: True
Inline callers:
  - lib/zstd/huf_decompress.c:HUF_decompress1X_DCtx_wksp
Direct callers:
  - lib/zstd/decompress.c:ZSTD_decodeLiteralsBlock
```
**Symbols:**

```
ffffffff814f8900-ffffffff814f897e: HUF_decompress1X2_DCtx_wksp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
size_t HUF_decompress1X2_DCtx_wksp(HUF_DTable *DCtx, void *dst, size_t dstSize, const void *cSrc, size_t cSrcSize, void *workspace, size_t workspaceSize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/huf_decompress.c (ffffffff81526a66)
Location: lib/zstd/huf_decompress.c:232
Inline: True
Inline callers:
  - lib/zstd/huf_decompress.c:HUF_decompress1X_DCtx_wksp
Direct callers:
  - lib/zstd/decompress.c:ZSTD_decompressBlock
  - lib/zstd/decompress.c:ZSTD_decodeLiteralsBlock
```
**Symbols:**

```
ffffffff81525f00-ffffffff81525f7e: HUF_decompress1X2_DCtx_wksp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
size_t HUF_decompress1X2_DCtx_wksp(HUF_DTable *DCtx, void *dst, size_t dstSize, const void *cSrc, size_t cSrcSize, void *workspace, size_t workspaceSize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/huf_decompress.c (ffffffff815478f6)
Location: lib/zstd/huf_decompress.c:232
Inline: True
Inline callers:
  - lib/zstd/huf_decompress.c:HUF_decompress1X_DCtx_wksp
Direct callers:
  - lib/zstd/decompress.c:ZSTD_decompressBlock
  - lib/zstd/decompress.c:ZSTD_decodeLiteralsBlock
```
**Symbols:**

```
ffffffff81546d90-ffffffff81546e0e: HUF_decompress1X2_DCtx_wksp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
size_t HUF_decompress1X2_DCtx_wksp(HUF_DTable *DCtx, void *dst, size_t dstSize, const void *cSrc, size_t cSrcSize, void *workspace, size_t workspaceSize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/huf_decompress.c (ffffffff815d3216)
Location: lib/zstd/huf_decompress.c:232
Inline: True
Inline callers:
  - lib/zstd/huf_decompress.c:HUF_decompress1X_DCtx_wksp
Direct callers:
  - lib/zstd/decompress.c:ZSTD_decodeLiteralsBlock
```
**Symbols:**

```
ffffffff815d2700-ffffffff815d277e: HUF_decompress1X2_DCtx_wksp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
size_t HUF_decompress1X2_DCtx_wksp(HUF_DTable *DCtx, void *dst, size_t dstSize, const void *cSrc, size_t cSrcSize, void *workspace, size_t workspaceSize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/huf_decompress.c (ffffffff815f0e5b)
Location: lib/zstd/huf_decompress.c:232
Inline: True
Inline callers:
  - lib/zstd/huf_decompress.c:HUF_decompress1X_DCtx_wksp
Direct callers:
  - lib/zstd/decompress.c:ZSTD_decodeLiteralsBlock
```
**Symbols:**

```
ffffffff815f02e0-ffffffff815f0363: HUF_decompress1X2_DCtx_wksp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
size_t HUF_decompress1X2_DCtx_wksp(HUF_DTable *DCtx, void *dst, size_t dstSize, const void *cSrc, size_t cSrcSize, void *workspace, size_t workspaceSize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/huf_decompress.c (ffffffff815d272b)
Location: lib/zstd/huf_decompress.c:232
Inline: True
Inline callers:
  - lib/zstd/huf_decompress.c:HUF_decompress1X_DCtx_wksp
Direct callers:
  - lib/zstd/decompress.c:ZSTD_decodeLiteralsBlock
```
**Symbols:**

```
ffffffff815d1b90-ffffffff815d1c13: HUF_decompress1X2_DCtx_wksp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
size_t HUF_decompress1X2_DCtx_wksp(HUF_DTable *DCtx, void *dst, size_t dstSize, const void *cSrc, size_t cSrcSize, void *workspace, size_t workspaceSize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/huf_decompress.c (ffffffff8163d15d)
Location: lib/zstd/huf_decompress.c:232
Inline: True
Inline callers:
  - lib/zstd/huf_decompress.c:HUF_decompress1X_DCtx_wksp
Direct callers:
  - lib/zstd/decompress.c:ZSTD_decodeLiteralsBlock
```
**Symbols:**

```
ffffffff8163c220-ffffffff8163c2a3: HUF_decompress1X2_DCtx_wksp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
size_t HUF_decompress1X2_DCtx_wksp(HUF_DTable *DCtx, void *dst, size_t dstSize, const void *cSrc, size_t cSrcSize, void *workSpace, size_t wkspSize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress/huf_decompress.c (ffffffff81750098)
Location: lib/zstd/decompress/huf_decompress.c:931
Inline: True
Inline callers:
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress1X_DCtx_wksp
```
**Symbols:**

```
ffffffff8174fc00-ffffffff8174fc97: HUF_decompress1X2_DCtx_wksp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
size_t HUF_decompress1X2_DCtx_wksp(HUF_DTable *DCtx, void *dst, size_t dstSize, const void *cSrc, size_t cSrcSize, void *workSpace, size_t wkspSize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress/huf_decompress.c (ffffffff818741b8)
Location: lib/zstd/decompress/huf_decompress.c:1465
Inline: True
Inline callers:
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress1X_DCtx_wksp
```
**Symbols:**

```
ffffffff81873ca0-ffffffff81873d3a: HUF_decompress1X2_DCtx_wksp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
size_t HUF_decompress1X2_DCtx_wksp(HUF_DTable *DCtx, void *dst, size_t dstSize, const void *cSrc, size_t cSrcSize, void *workSpace, size_t wkspSize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress/huf_decompress.c (ffffffff818b4f18)
Location: lib/zstd/decompress/huf_decompress.c:1465
Inline: True
Inline callers:
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress1X_DCtx_wksp
```
**Symbols:**

```
ffffffff818b4a00-ffffffff818b4a9a: HUF_decompress1X2_DCtx_wksp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
size_t HUF_decompress1X2_DCtx_wksp(HUF_DTable *DCtx, void *dst, size_t dstSize, const void *cSrc, size_t cSrcSize, void *workSpace, size_t wkspSize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress/huf_decompress.c (ffffffff81906ad8)
Location: lib/zstd/decompress/huf_decompress.c:1465
Inline: True
Inline callers:
  - lib/zstd/decompress/huf_decompress.c:HUF_decompress1X_DCtx_wksp
```
**Symbols:**

```
ffffffff819065c0-ffffffff8190665a: HUF_decompress1X2_DCtx_wksp (STB_GLOBAL)
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
size_t HUF_decompress1X2_DCtx_wksp(HUF_DTable *DCtx, void *dst, size_t dstSize, const void *cSrc, size_t cSrcSize, void *workspace, size_t workspaceSize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/huf_decompress.c (ffff800010653b64)
Location: lib/zstd/huf_decompress.c:232
Inline: True
Inline callers:
  - lib/zstd/huf_decompress.c:HUF_decompress1X_DCtx_wksp
Direct callers:
  - lib/zstd/decompress.c:ZSTD_decompressBlock
  - lib/zstd/decompress.c:ZSTD_decodeLiteralsBlock
```
**Symbols:**

```
ffff800010652ee0-ffff800010652f80: HUF_decompress1X2_DCtx_wksp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
size_t HUF_decompress1X2_DCtx_wksp(HUF_DTable *DCtx, void *dst, size_t dstSize, const void *cSrc, size_t cSrcSize, void *workspace, size_t workspaceSize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/huf_decompress.c (c07feb8c)
Location: lib/zstd/huf_decompress.c:232
Inline: True
Inline callers:
  - lib/zstd/huf_decompress.c:HUF_decompress1X_DCtx_wksp
Direct callers:
  - lib/zstd/decompress.c:ZSTD_decompressBlock
  - lib/zstd/decompress.c:ZSTD_decodeLiteralsBlock
```
**Symbols:**

```
c07fdfac-c07fe02c: HUF_decompress1X2_DCtx_wksp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
size_t HUF_decompress1X2_DCtx_wksp(HUF_DTable *DCtx, void *dst, size_t dstSize, const void *cSrc, size_t cSrcSize, void *workspace, size_t workspaceSize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/huf_decompress.c (c0000000008034b0)
Location: lib/zstd/huf_decompress.c:232
Inline: True
Inline callers:
  - lib/zstd/huf_decompress.c:HUF_decompress1X_DCtx_wksp
Direct callers:
  - lib/zstd/decompress.c:ZSTD_decompressBlock
  - lib/zstd/decompress.c:ZSTD_decodeLiteralsBlock
```
**Symbols:**

```
c0000000008023e0-c0000000008024c0: HUF_decompress1X2_DCtx_wksp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
size_t HUF_decompress1X2_DCtx_wksp(HUF_DTable *DCtx, void *dst, size_t dstSize, const void *cSrc, size_t cSrcSize, void *workspace, size_t workspaceSize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/huf_decompress.c (ffffffe0004816ac)
Location: lib/zstd/huf_decompress.c:232
Inline: True
Inline callers:
  - lib/zstd/huf_decompress.c:HUF_decompress1X_DCtx_wksp
Direct callers:
  - lib/zstd/decompress.c:ZSTD_decompressBlock
  - lib/zstd/decompress.c:ZSTD_decodeLiteralsBlock
```
**Symbols:**

```
ffffffe000480c40-ffffffe000480cb4: HUF_decompress1X2_DCtx_wksp (STB_GLOBAL)
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
size_t HUF_decompress1X2_DCtx_wksp(HUF_DTable *DCtx, void *dst, size_t dstSize, const void *cSrc, size_t cSrcSize, void *workspace, size_t workspaceSize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/huf_decompress.c (ffffffff8153fed6)
Location: lib/zstd/huf_decompress.c:232
Inline: True
Inline callers:
  - lib/zstd/huf_decompress.c:HUF_decompress1X_DCtx_wksp
Direct callers:
  - lib/zstd/decompress.c:ZSTD_decompressBlock
  - lib/zstd/decompress.c:ZSTD_decodeLiteralsBlock
```
**Symbols:**

```
ffffffff8153f370-ffffffff8153f3ee: HUF_decompress1X2_DCtx_wksp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
size_t HUF_decompress1X2_DCtx_wksp(HUF_DTable *DCtx, void *dst, size_t dstSize, const void *cSrc, size_t cSrcSize, void *workspace, size_t workspaceSize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/huf_decompress.c (ffffffff815301b6)
Location: lib/zstd/huf_decompress.c:232
Inline: True
Inline callers:
  - lib/zstd/huf_decompress.c:HUF_decompress1X_DCtx_wksp
Direct callers:
  - lib/zstd/decompress.c:ZSTD_decompressBlock
  - lib/zstd/decompress.c:ZSTD_decodeLiteralsBlock
```
**Symbols:**

```
ffffffff8152f650-ffffffff8152f6ce: HUF_decompress1X2_DCtx_wksp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
size_t HUF_decompress1X2_DCtx_wksp(HUF_DTable *DCtx, void *dst, size_t dstSize, const void *cSrc, size_t cSrcSize, void *workspace, size_t workspaceSize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/huf_decompress.c (ffffffff8153bc16)
Location: lib/zstd/huf_decompress.c:232
Inline: True
Inline callers:
  - lib/zstd/huf_decompress.c:HUF_decompress1X_DCtx_wksp
Direct callers:
  - lib/zstd/decompress.c:ZSTD_decompressBlock
  - lib/zstd/decompress.c:ZSTD_decodeLiteralsBlock
```
**Symbols:**

```
ffffffff8153b0b0-ffffffff8153b12e: HUF_decompress1X2_DCtx_wksp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
size_t HUF_decompress1X2_DCtx_wksp(HUF_DTable *DCtx, void *dst, size_t dstSize, const void *cSrc, size_t cSrcSize, void *workspace, size_t workspaceSize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/huf_decompress.c (ffffffff81555a46)
Location: lib/zstd/huf_decompress.c:232
Inline: True
Inline callers:
  - lib/zstd/huf_decompress.c:HUF_decompress1X_DCtx_wksp
Direct callers:
  - lib/zstd/decompress.c:ZSTD_decompressBlock
  - lib/zstd/decompress.c:ZSTD_decodeLiteralsBlock
```
**Symbols:**

```
ffffffff81554ee0-ffffffff81554f5e: HUF_decompress1X2_DCtx_wksp (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>void *workSpace</code>
</li>
<li>
<b>Param added. </b>
<code>size_t wkspSize</code>
</li>
<li>
<b>Param removed. </b>
<code>void *workspace</code>
</li>
<li>
<b>Param removed. </b>
<code>size_t workspaceSize</code>
</li>
</ul>
</details>
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
