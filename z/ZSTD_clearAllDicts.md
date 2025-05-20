# Function: <code>ZSTD_clearAllDicts</code>

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
<summary>In <code>5.19</code>: ✅</summary>

```c
void ZSTD_clearAllDicts(ZSTD_CCtx *cctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff8171a250)
Location: lib/zstd/compress/zstd_compress.c:130
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_initCStream
  - lib/zstd/compress/zstd_compress.c:ZSTD_initCStream_srcSize
  - lib/zstd/compress/zstd_compress.c:ZSTD_initCStream_usingCDict
  - lib/zstd/compress/zstd_compress.c:ZSTD_initCStream_usingCDict_advanced
  - lib/zstd/compress/zstd_compress.c:ZSTD_initCStream_internal
  - lib/zstd/compress/zstd_compress.c:ZSTD_CCtx_refPrefix
  - lib/zstd/compress/zstd_compress.c:ZSTD_CCtx_loadDictionary_byReference
  - lib/zstd/compress/zstd_compress.c:ZSTD_freeCCtx
  - lib/zstd/compress/zstd_compress.c:ZSTD_freeCCtx
  - lib/zstd/compress/zstd_compress.c:ZSTD_createCCtx_advanced
```
**Symbols:**

```
ffffffff8171a250-ffffffff8171a2fc: ZSTD_clearAllDicts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ZSTD_clearAllDicts(ZSTD_CCtx *cctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff8180f8c0)
Location: lib/zstd/compress/zstd_compress.c:145
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_initCStream
  - lib/zstd/compress/zstd_compress.c:ZSTD_initCStream_srcSize
  - lib/zstd/compress/zstd_compress.c:ZSTD_initCStream_usingCDict
  - lib/zstd/compress/zstd_compress.c:ZSTD_initCStream_usingCDict_advanced
  - lib/zstd/compress/zstd_compress.c:ZSTD_initCStream_internal
  - lib/zstd/compress/zstd_compress.c:ZSTD_CCtx_refPrefix
  - lib/zstd/compress/zstd_compress.c:ZSTD_CCtx_loadDictionary_byReference
  - lib/zstd/compress/zstd_compress.c:ZSTD_freeCCtx
  - lib/zstd/compress/zstd_compress.c:ZSTD_freeCCtx
  - lib/zstd/compress/zstd_compress.c:ZSTD_createCCtx_advanced
```
**Symbols:**

```
ffffffff8180f8c0-ffffffff8180f96c: ZSTD_clearAllDicts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ZSTD_clearAllDicts(ZSTD_CCtx *cctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff818503b0)
Location: lib/zstd/compress/zstd_compress.c:145
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_initCStream
  - lib/zstd/compress/zstd_compress.c:ZSTD_initCStream_srcSize
  - lib/zstd/compress/zstd_compress.c:ZSTD_initCStream_usingCDict
  - lib/zstd/compress/zstd_compress.c:ZSTD_initCStream_usingCDict_advanced
  - lib/zstd/compress/zstd_compress.c:ZSTD_initCStream_internal
  - lib/zstd/compress/zstd_compress.c:ZSTD_CCtx_refPrefix
  - lib/zstd/compress/zstd_compress.c:ZSTD_CCtx_loadDictionary_byReference
  - lib/zstd/compress/zstd_compress.c:ZSTD_freeCCtx
  - lib/zstd/compress/zstd_compress.c:ZSTD_freeCCtx
  - lib/zstd/compress/zstd_compress.c:ZSTD_createCCtx_advanced
```
**Symbols:**

```
ffffffff818503b0-ffffffff8185045c: ZSTD_clearAllDicts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ZSTD_clearAllDicts(ZSTD_CCtx *cctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff818a1f70)
Location: lib/zstd/compress/zstd_compress.c:145
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_initCStream
  - lib/zstd/compress/zstd_compress.c:ZSTD_initCStream_srcSize
  - lib/zstd/compress/zstd_compress.c:ZSTD_initCStream_usingCDict
  - lib/zstd/compress/zstd_compress.c:ZSTD_initCStream_usingCDict_advanced
  - lib/zstd/compress/zstd_compress.c:ZSTD_initCStream_internal
  - lib/zstd/compress/zstd_compress.c:ZSTD_CCtx_refPrefix
  - lib/zstd/compress/zstd_compress.c:ZSTD_CCtx_loadDictionary_byReference
  - lib/zstd/compress/zstd_compress.c:ZSTD_freeCCtx
  - lib/zstd/compress/zstd_compress.c:ZSTD_freeCCtx
  - lib/zstd/compress/zstd_compress.c:ZSTD_createCCtx_advanced
```
**Symbols:**

```
ffffffff818a1f70-ffffffff818a201c: ZSTD_clearAllDicts (STB_LOCAL)
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
