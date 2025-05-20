# Function: <code>ZSTD_DCtx_refPrefix_advanced</code>

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
size_t ZSTD_DCtx_refPrefix_advanced(ZSTD_DCtx *dctx, const void *prefix, size_t prefixSize, ZSTD_dictContentType_e dictContentType);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress/zstd_decompress.c (ffffffff81753c25)
Location: lib/zstd/decompress/zstd_decompress.c:1491
Inline: True
Inline callers:
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_DCtx_refPrefix
```
**Symbols:**

```
ffffffff81753b30-ffffffff81753c16: ZSTD_DCtx_refPrefix_advanced (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
size_t ZSTD_DCtx_refPrefix_advanced(ZSTD_DCtx *dctx, const void *prefix, size_t prefixSize, ZSTD_dictContentType_e dictContentType);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress/zstd_decompress.c (ffffffff81878145)
Location: lib/zstd/decompress/zstd_decompress.c:1537
Inline: True
Inline callers:
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_DCtx_refPrefix
```
**Symbols:**

```
ffffffff81878040-ffffffff81878126: ZSTD_DCtx_refPrefix_advanced (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
size_t ZSTD_DCtx_refPrefix_advanced(ZSTD_DCtx *dctx, const void *prefix, size_t prefixSize, ZSTD_dictContentType_e dictContentType);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress/zstd_decompress.c (ffffffff818b8ef5)
Location: lib/zstd/decompress/zstd_decompress.c:1556
Inline: True
Inline callers:
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_DCtx_refPrefix
```
**Symbols:**

```
ffffffff818b8df0-ffffffff818b8ed6: ZSTD_DCtx_refPrefix_advanced (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
size_t ZSTD_DCtx_refPrefix_advanced(ZSTD_DCtx *dctx, const void *prefix, size_t prefixSize, ZSTD_dictContentType_e dictContentType);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress/zstd_decompress.c (ffffffff8190aab5)
Location: lib/zstd/decompress/zstd_decompress.c:1556
Inline: True
Inline callers:
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_DCtx_refPrefix
```
**Symbols:**

```
ffffffff8190a9b0-ffffffff8190aa96: ZSTD_DCtx_refPrefix_advanced (STB_GLOBAL)
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
