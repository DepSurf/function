# Function: <code>HUF_readDTableX4_wksp</code>

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
size_t HUF_readDTableX4_wksp(HUF_DTable *DTable, const void *src, size_t srcSize, void *workspace, size_t workspaceSize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/huf_decompress.c (ffffffff814afab0)
Location: lib/zstd/huf_decompress.c:482
Inline: True
Direct callers:
  - lib/zstd/huf_decompress.c:HUF_decompress1X_DCtx_wksp
  - lib/zstd/huf_decompress.c:HUF_decompress4X_hufOnly_wksp
  - lib/zstd/huf_decompress.c:HUF_decompress4X_DCtx_wksp
  - lib/zstd/decompress.c:ZSTD_loadEntropy
```
**Symbols:**

```
ffffffff814afab0-ffffffff814afecf: HUF_readDTableX4_wksp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
size_t HUF_readDTableX4_wksp(HUF_DTable *DTable, const void *src, size_t srcSize, void *workspace, size_t workspaceSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/huf_decompress.c (ffffffff814e4d50)
Location: lib/zstd/huf_decompress.c:482
Inline: False
Direct callers:
  - lib/zstd/huf_decompress.c:HUF_decompress1X_DCtx_wksp
  - lib/zstd/huf_decompress.c:HUF_decompress4X_hufOnly_wksp
  - lib/zstd/huf_decompress.c:HUF_decompress4X_DCtx_wksp
  - lib/zstd/decompress.c:ZSTD_loadEntropy
```
**Symbols:**

```
ffffffff814e4d50-ffffffff814e51ca: HUF_readDTableX4_wksp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
size_t HUF_readDTableX4_wksp(HUF_DTable *DTable, const void *src, size_t srcSize, void *workspace, size_t workspaceSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/huf_decompress.c (ffffffff814f8a40)
Location: lib/zstd/huf_decompress.c:482
Inline: False
Direct callers:
  - lib/zstd/huf_decompress.c:HUF_decompress1X_DCtx_wksp
  - lib/zstd/huf_decompress.c:HUF_decompress4X_hufOnly_wksp
  - lib/zstd/huf_decompress.c:HUF_decompress4X_DCtx_wksp
  - lib/zstd/decompress.c:ZSTD_loadEntropy
```
**Symbols:**

```
ffffffff814f8a40-ffffffff814f8ec0: HUF_readDTableX4_wksp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
size_t HUF_readDTableX4_wksp(HUF_DTable *DTable, const void *src, size_t srcSize, void *workspace, size_t workspaceSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/huf_decompress.c (ffffffff81526040)
Location: lib/zstd/huf_decompress.c:482
Inline: False
Direct callers:
  - lib/zstd/huf_decompress.c:HUF_decompress1X_DCtx_wksp
  - lib/zstd/huf_decompress.c:HUF_decompress4X_hufOnly_wksp
  - lib/zstd/huf_decompress.c:HUF_decompress4X_DCtx_wksp
  - lib/zstd/decompress.c:ZSTD_loadEntropy
```
**Symbols:**

```
ffffffff81526040-ffffffff815264b3: HUF_readDTableX4_wksp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
size_t HUF_readDTableX4_wksp(HUF_DTable *DTable, const void *src, size_t srcSize, void *workspace, size_t workspaceSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/huf_decompress.c (ffffffff81546ed0)
Location: lib/zstd/huf_decompress.c:482
Inline: False
Direct callers:
  - lib/zstd/huf_decompress.c:HUF_decompress1X_DCtx_wksp
  - lib/zstd/huf_decompress.c:HUF_decompress4X_hufOnly_wksp
  - lib/zstd/huf_decompress.c:HUF_decompress4X_DCtx_wksp
  - lib/zstd/decompress.c:ZSTD_loadEntropy
```
**Symbols:**

```
ffffffff81546ed0-ffffffff81547343: HUF_readDTableX4_wksp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
size_t HUF_readDTableX4_wksp(HUF_DTable *DTable, const void *src, size_t srcSize, void *workspace, size_t workspaceSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/huf_decompress.c (ffffffff815d2840)
Location: lib/zstd/huf_decompress.c:482
Inline: False
Direct callers:
  - lib/zstd/huf_decompress.c:HUF_decompress1X_DCtx_wksp
  - lib/zstd/huf_decompress.c:HUF_decompress4X_hufOnly_wksp
  - lib/zstd/huf_decompress.c:HUF_decompress4X_DCtx_wksp
  - lib/zstd/decompress.c:ZSTD_loadEntropy
```
**Symbols:**

```
ffffffff815d2840-ffffffff815d2c68: HUF_readDTableX4_wksp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
size_t HUF_readDTableX4_wksp(HUF_DTable *DTable, const void *src, size_t srcSize, void *workspace, size_t workspaceSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/huf_decompress.c (ffffffff815f0440)
Location: lib/zstd/huf_decompress.c:482
Inline: False
Direct callers:
  - lib/zstd/huf_decompress.c:HUF_decompress1X_DCtx_wksp
  - lib/zstd/huf_decompress.c:HUF_decompress4X_hufOnly_wksp
  - lib/zstd/huf_decompress.c:HUF_decompress4X_DCtx_wksp
  - lib/zstd/decompress.c:ZSTD_loadEntropy
```
**Symbols:**

```
ffffffff815f0440-ffffffff815f086c: HUF_readDTableX4_wksp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
size_t HUF_readDTableX4_wksp(HUF_DTable *DTable, const void *src, size_t srcSize, void *workspace, size_t workspaceSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/huf_decompress.c (ffffffff815d1cf0)
Location: lib/zstd/huf_decompress.c:482
Inline: False
Direct callers:
  - lib/zstd/huf_decompress.c:HUF_decompress1X_DCtx_wksp
  - lib/zstd/huf_decompress.c:HUF_decompress4X_hufOnly_wksp
  - lib/zstd/huf_decompress.c:HUF_decompress4X_DCtx_wksp
  - lib/zstd/decompress.c:ZSTD_loadEntropy
```
**Symbols:**

```
ffffffff815d1cf0-ffffffff815d2129: HUF_readDTableX4_wksp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
size_t HUF_readDTableX4_wksp(HUF_DTable *DTable, const void *src, size_t srcSize, void *workspace, size_t workspaceSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/zstd/huf_decompress.c (0)
Location: lib/zstd/huf_decompress.c:482
Inline: False
Direct callers:
  - lib/zstd/huf_decompress.c:HUF_decompress1X_DCtx_wksp
  - lib/zstd/huf_decompress.c:HUF_decompress4X_hufOnly_wksp
  - lib/zstd/huf_decompress.c:HUF_decompress4X_DCtx_wksp
  - lib/zstd/decompress.c:ZSTD_loadEntropy
```
**Symbols:**

```
ffffffff81cdd280-ffffffff81cdd3d0: HUF_readDTableX4_wksp.cold (STB_LOCAL)
ffffffff8163c380-ffffffff8163c881: HUF_readDTableX4_wksp (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
size_t HUF_readDTableX4_wksp(HUF_DTable *DTable, const void *src, size_t srcSize, void *workspace, size_t workspaceSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/huf_decompress.c (ffff800010653080)
Location: lib/zstd/huf_decompress.c:482
Inline: False
Direct callers:
  - lib/zstd/huf_decompress.c:HUF_decompress1X_DCtx_wksp
  - lib/zstd/huf_decompress.c:HUF_decompress4X_hufOnly_wksp
  - lib/zstd/huf_decompress.c:HUF_decompress4X_DCtx_wksp
  - lib/zstd/decompress.c:ZSTD_loadEntropy
```
**Symbols:**

```
ffff800010653080-ffff8000106534ac: HUF_readDTableX4_wksp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
size_t HUF_readDTableX4_wksp(HUF_DTable *DTable, const void *src, size_t srcSize, void *workspace, size_t workspaceSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/huf_decompress.c (c07fe0f8)
Location: lib/zstd/huf_decompress.c:482
Inline: False
Direct callers:
  - lib/zstd/huf_decompress.c:HUF_decompress1X_DCtx_wksp
  - lib/zstd/huf_decompress.c:HUF_decompress4X_hufOnly_wksp
  - lib/zstd/huf_decompress.c:HUF_decompress4X_DCtx_wksp
  - lib/zstd/decompress.c:ZSTD_loadEntropy
```
**Symbols:**

```
c07fe0f8-c07fe564: HUF_readDTableX4_wksp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
size_t HUF_readDTableX4_wksp(HUF_DTable *DTable, const void *src, size_t srcSize, void *workspace, size_t workspaceSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/huf_decompress.c (c000000000802620)
Location: lib/zstd/huf_decompress.c:482
Inline: False
Direct callers:
  - lib/zstd/huf_decompress.c:HUF_decompress1X_DCtx_wksp
  - lib/zstd/huf_decompress.c:HUF_decompress4X_hufOnly_wksp
  - lib/zstd/huf_decompress.c:HUF_decompress4X_DCtx_wksp
  - lib/zstd/decompress.c:ZSTD_loadEntropy
```
**Symbols:**

```
c000000000802620-c000000000802bb4: HUF_readDTableX4_wksp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
size_t HUF_readDTableX4_wksp(HUF_DTable *DTable, const void *src, size_t srcSize, void *workspace, size_t workspaceSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/huf_decompress.c (ffffffe000480d80)
Location: lib/zstd/huf_decompress.c:482
Inline: False
Direct callers:
  - lib/zstd/huf_decompress.c:HUF_decompress1X_DCtx_wksp
  - lib/zstd/huf_decompress.c:HUF_decompress4X_hufOnly_wksp
  - lib/zstd/huf_decompress.c:HUF_decompress4X_DCtx_wksp
  - lib/zstd/decompress.c:ZSTD_loadEntropy
```
**Symbols:**

```
ffffffe000480d80-ffffffe000481114: HUF_readDTableX4_wksp (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
size_t HUF_readDTableX4_wksp(HUF_DTable *DTable, const void *src, size_t srcSize, void *workspace, size_t workspaceSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/huf_decompress.c (ffffffff8153f4b0)
Location: lib/zstd/huf_decompress.c:482
Inline: False
Direct callers:
  - lib/zstd/huf_decompress.c:HUF_decompress1X_DCtx_wksp
  - lib/zstd/huf_decompress.c:HUF_decompress4X_hufOnly_wksp
  - lib/zstd/huf_decompress.c:HUF_decompress4X_DCtx_wksp
  - lib/zstd/decompress.c:ZSTD_loadEntropy
```
**Symbols:**

```
ffffffff8153f4b0-ffffffff8153f923: HUF_readDTableX4_wksp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
size_t HUF_readDTableX4_wksp(HUF_DTable *DTable, const void *src, size_t srcSize, void *workspace, size_t workspaceSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/huf_decompress.c (ffffffff8152f790)
Location: lib/zstd/huf_decompress.c:482
Inline: False
Direct callers:
  - lib/zstd/huf_decompress.c:HUF_decompress1X_DCtx_wksp
  - lib/zstd/huf_decompress.c:HUF_decompress4X_hufOnly_wksp
  - lib/zstd/huf_decompress.c:HUF_decompress4X_DCtx_wksp
  - lib/zstd/decompress.c:ZSTD_loadEntropy
```
**Symbols:**

```
ffffffff8152f790-ffffffff8152fc03: HUF_readDTableX4_wksp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
size_t HUF_readDTableX4_wksp(HUF_DTable *DTable, const void *src, size_t srcSize, void *workspace, size_t workspaceSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/huf_decompress.c (ffffffff8153b1f0)
Location: lib/zstd/huf_decompress.c:482
Inline: False
Direct callers:
  - lib/zstd/huf_decompress.c:HUF_decompress1X_DCtx_wksp
  - lib/zstd/huf_decompress.c:HUF_decompress4X_hufOnly_wksp
  - lib/zstd/huf_decompress.c:HUF_decompress4X_DCtx_wksp
  - lib/zstd/decompress.c:ZSTD_loadEntropy
```
**Symbols:**

```
ffffffff8153b1f0-ffffffff8153b663: HUF_readDTableX4_wksp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
size_t HUF_readDTableX4_wksp(HUF_DTable *DTable, const void *src, size_t srcSize, void *workspace, size_t workspaceSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/huf_decompress.c (ffffffff81555020)
Location: lib/zstd/huf_decompress.c:482
Inline: False
Direct callers:
  - lib/zstd/huf_decompress.c:HUF_decompress1X_DCtx_wksp
  - lib/zstd/huf_decompress.c:HUF_decompress4X_hufOnly_wksp
  - lib/zstd/huf_decompress.c:HUF_decompress4X_DCtx_wksp
  - lib/zstd/decompress.c:ZSTD_loadEntropy
```
**Symbols:**

```
ffffffff81555020-ffffffff81555493: HUF_readDTableX4_wksp (STB_GLOBAL)
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
