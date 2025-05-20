# Function: <code>ZSTD_DCtx_loadDictionary_advanced</code>

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
size_t ZSTD_DCtx_loadDictionary_advanced(ZSTD_DCtx *dctx, const void *dict, size_t dictSize, ZSTD_dictLoadMethod_e dictLoadMethod, ZSTD_dictContentType_e dictContentType);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress/zstd_decompress.c (ffffffff81753d2b)
Location: lib/zstd/decompress/zstd_decompress.c:1465
Inline: True
Inline callers:
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_initDStream_usingDict
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_initDStream_usingDict
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_DCtx_refPrefix
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_DCtx_refPrefix
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_DCtx_loadDictionary_byReference
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_DCtx_loadDictionary_byReference
```
**Symbols:**

```
ffffffff81753870-ffffffff81753966: ZSTD_DCtx_loadDictionary_advanced (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
size_t ZSTD_DCtx_loadDictionary_advanced(ZSTD_DCtx *dctx, const void *dict, size_t dictSize, ZSTD_dictLoadMethod_e dictLoadMethod, ZSTD_dictContentType_e dictContentType);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress/zstd_decompress.c (ffffffff8187825b)
Location: lib/zstd/decompress/zstd_decompress.c:1511
Inline: True
Inline callers:
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_initDStream_usingDict
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_initDStream_usingDict
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_DCtx_refPrefix
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_DCtx_refPrefix
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_DCtx_loadDictionary_byReference
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_DCtx_loadDictionary_byReference
```
**Symbols:**

```
ffffffff81877d50-ffffffff81877e46: ZSTD_DCtx_loadDictionary_advanced (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
size_t ZSTD_DCtx_loadDictionary_advanced(ZSTD_DCtx *dctx, const void *dict, size_t dictSize, ZSTD_dictLoadMethod_e dictLoadMethod, ZSTD_dictContentType_e dictContentType);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress/zstd_decompress.c (ffffffff818b900b)
Location: lib/zstd/decompress/zstd_decompress.c:1530
Inline: True
Inline callers:
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_initDStream_usingDict
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_initDStream_usingDict
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_DCtx_refPrefix
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_DCtx_refPrefix
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_DCtx_loadDictionary_byReference
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_DCtx_loadDictionary_byReference
```
**Symbols:**

```
ffffffff818b8b00-ffffffff818b8bf6: ZSTD_DCtx_loadDictionary_advanced (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
size_t ZSTD_DCtx_loadDictionary_advanced(ZSTD_DCtx *dctx, const void *dict, size_t dictSize, ZSTD_dictLoadMethod_e dictLoadMethod, ZSTD_dictContentType_e dictContentType);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress/zstd_decompress.c (ffffffff8190abcb)
Location: lib/zstd/decompress/zstd_decompress.c:1530
Inline: True
Inline callers:
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_initDStream_usingDict
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_initDStream_usingDict
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_DCtx_refPrefix
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_DCtx_refPrefix
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_DCtx_loadDictionary_byReference
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_DCtx_loadDictionary_byReference
```
**Symbols:**

```
ffffffff8190a6c0-ffffffff8190a7b6: ZSTD_DCtx_loadDictionary_advanced (STB_GLOBAL)
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
