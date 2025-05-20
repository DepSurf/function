# Function: <code>ZSTD_CCtx_refPrefix_advanced</code>

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
size_t ZSTD_CCtx_refPrefix_advanced(ZSTD_CCtx *cctx, const void *prefix, size_t prefixSize, ZSTD_dictContentType_e dictContentType);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff8171a705)
Location: lib/zstd/compress/zstd_compress.c:1009
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_CCtx_refPrefix
  - lib/zstd/compress/zstd_compress.c:ZSTD_CCtx_refPrefix
```
**Symbols:**

```
ffffffff8171a5b0-ffffffff8171a625: ZSTD_CCtx_refPrefix_advanced (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
size_t ZSTD_CCtx_refPrefix_advanced(ZSTD_CCtx *cctx, const void *prefix, size_t prefixSize, ZSTD_dictContentType_e dictContentType);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff8180fdd5)
Location: lib/zstd/compress/zstd_compress.c:1126
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_CCtx_refPrefix
  - lib/zstd/compress/zstd_compress.c:ZSTD_CCtx_refPrefix
```
**Symbols:**

```
ffffffff8180fc60-ffffffff8180fcd5: ZSTD_CCtx_refPrefix_advanced (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
size_t ZSTD_CCtx_refPrefix_advanced(ZSTD_CCtx *cctx, const void *prefix, size_t prefixSize, ZSTD_dictContentType_e dictContentType);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff818508b5)
Location: lib/zstd/compress/zstd_compress.c:1126
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_CCtx_refPrefix
  - lib/zstd/compress/zstd_compress.c:ZSTD_CCtx_refPrefix
```
**Symbols:**

```
ffffffff81850740-ffffffff818507b5: ZSTD_CCtx_refPrefix_advanced (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
size_t ZSTD_CCtx_refPrefix_advanced(ZSTD_CCtx *cctx, const void *prefix, size_t prefixSize, ZSTD_dictContentType_e dictContentType);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff818a2475)
Location: lib/zstd/compress/zstd_compress.c:1126
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_CCtx_refPrefix
  - lib/zstd/compress/zstd_compress.c:ZSTD_CCtx_refPrefix
```
**Symbols:**

```
ffffffff818a2300-ffffffff818a2375: ZSTD_CCtx_refPrefix_advanced (STB_GLOBAL)
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
