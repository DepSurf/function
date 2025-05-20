# Function: <code>ZSTD_CCtx_loadDictionary_advanced</code>

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
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
size_t ZSTD_CCtx_loadDictionary_advanced(ZSTD_CCtx *cctx, const void *dict, size_t dictSize, ZSTD_dictLoadMethod_e dictLoadMethod, ZSTD_dictContentType_e dictContentType);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff8171bee2)
Location: lib/zstd/compress/zstd_compress.c:945
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_initCStream_usingDict
  - lib/zstd/compress/zstd_compress.c:ZSTD_initCStream_advanced
  - lib/zstd/compress/zstd_compress.c:ZSTD_initCStream_internal
  - lib/zstd/compress/zstd_compress.c:ZSTD_CCtx_loadDictionary_byReference
  - lib/zstd/compress/zstd_compress.c:ZSTD_CCtx_loadDictionary_byReference
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_initCStream_usingDict
  - lib/zstd/compress/zstd_compress.c:ZSTD_initCStream_advanced
  - lib/zstd/compress/zstd_compress.c:ZSTD_initCStream_internal
```
**Symbols:**

```
ffffffff8171a480-ffffffff8171a555: ZSTD_CCtx_loadDictionary_advanced.part.0 (STB_LOCAL)
ffffffff8171aad0-ffffffff8171abd9: ZSTD_CCtx_loadDictionary_advanced (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
size_t ZSTD_CCtx_loadDictionary_advanced(ZSTD_CCtx *cctx, const void *dict, size_t dictSize, ZSTD_dictLoadMethod_e dictLoadMethod, ZSTD_dictContentType_e dictContentType);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff818116d2)
Location: lib/zstd/compress/zstd_compress.c:1062
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_initCStream_usingDict
  - lib/zstd/compress/zstd_compress.c:ZSTD_initCStream_advanced
  - lib/zstd/compress/zstd_compress.c:ZSTD_initCStream_internal
  - lib/zstd/compress/zstd_compress.c:ZSTD_CCtx_loadDictionary_byReference
  - lib/zstd/compress/zstd_compress.c:ZSTD_CCtx_loadDictionary_byReference
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_initCStream_usingDict
  - lib/zstd/compress/zstd_compress.c:ZSTD_initCStream_advanced
  - lib/zstd/compress/zstd_compress.c:ZSTD_initCStream_internal
```
**Symbols:**

```
ffffffff8180fb10-ffffffff8180fbe5: ZSTD_CCtx_loadDictionary_advanced.part.0 (STB_LOCAL)
ffffffff81810200-ffffffff81810309: ZSTD_CCtx_loadDictionary_advanced (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
size_t ZSTD_CCtx_loadDictionary_advanced(ZSTD_CCtx *cctx, const void *dict, size_t dictSize, ZSTD_dictLoadMethod_e dictLoadMethod, ZSTD_dictContentType_e dictContentType);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff818521b2)
Location: lib/zstd/compress/zstd_compress.c:1062
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_initCStream_usingDict
  - lib/zstd/compress/zstd_compress.c:ZSTD_initCStream_advanced
  - lib/zstd/compress/zstd_compress.c:ZSTD_initCStream_internal
  - lib/zstd/compress/zstd_compress.c:ZSTD_CCtx_loadDictionary_byReference
  - lib/zstd/compress/zstd_compress.c:ZSTD_CCtx_loadDictionary_byReference
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_initCStream_usingDict
  - lib/zstd/compress/zstd_compress.c:ZSTD_initCStream_advanced
  - lib/zstd/compress/zstd_compress.c:ZSTD_initCStream_internal
```
**Symbols:**

```
ffffffff818505f0-ffffffff818506c5: ZSTD_CCtx_loadDictionary_advanced.part.0 (STB_LOCAL)
ffffffff81850ce0-ffffffff81850de9: ZSTD_CCtx_loadDictionary_advanced (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
size_t ZSTD_CCtx_loadDictionary_advanced(ZSTD_CCtx *cctx, const void *dict, size_t dictSize, ZSTD_dictLoadMethod_e dictLoadMethod, ZSTD_dictContentType_e dictContentType);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff818a3d72)
Location: lib/zstd/compress/zstd_compress.c:1062
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_initCStream_usingDict
  - lib/zstd/compress/zstd_compress.c:ZSTD_initCStream_advanced
  - lib/zstd/compress/zstd_compress.c:ZSTD_initCStream_internal
  - lib/zstd/compress/zstd_compress.c:ZSTD_CCtx_loadDictionary_byReference
  - lib/zstd/compress/zstd_compress.c:ZSTD_CCtx_loadDictionary_byReference
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_initCStream_usingDict
  - lib/zstd/compress/zstd_compress.c:ZSTD_initCStream_advanced
  - lib/zstd/compress/zstd_compress.c:ZSTD_initCStream_internal
```
**Symbols:**

```
ffffffff818a21b0-ffffffff818a2285: ZSTD_CCtx_loadDictionary_advanced.part.0 (STB_LOCAL)
ffffffff818a28a0-ffffffff818a29a9: ZSTD_CCtx_loadDictionary_advanced (STB_GLOBAL)
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
