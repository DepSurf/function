# Function: <code>ZSTD_sizeof_matchState</code>

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
size_t ZSTD_sizeof_matchState(const const ZSTD_compressionParameters * cParams, const U32 forCCtx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff8171a055)
Location: lib/zstd/compress/zstd_compress.c:1231
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_estimateCDictSize
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_initStaticCDict
  - lib/zstd/compress/zstd_compress.c:ZSTD_createCDict_advanced2
  - lib/zstd/compress/zstd_compress.c:ZSTD_estimateCCtxSize_usingCCtxParams_internal
```
**Symbols:**

```
ffffffff81711ae0-ffffffff81711b9e: ZSTD_sizeof_matchState (STB_LOCAL)
ffffffff81e96e2d-ffffffff81e96e63: ZSTD_sizeof_matchState.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
size_t ZSTD_sizeof_matchState(const const ZSTD_compressionParameters * cParams, const ZSTD_paramSwitch_e useRowMatchFinder, const U32 enableDedicatedDictSearch, const U32 forCCtx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (0)
Location: lib/zstd/compress/zstd_compress.c:1348
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_initStaticCDict
  - lib/zstd/compress/zstd_compress.c:ZSTD_createCDict_advanced2
  - lib/zstd/compress/zstd_compress.c:ZSTD_estimateCDictSize
  - lib/zstd/compress/zstd_compress.c:ZSTD_estimateCCtxSize_usingCCtxParams_internal
```
**Symbols:**

```
ffffffff81804620-ffffffff818047be: ZSTD_sizeof_matchState (STB_LOCAL)
ffffffff8207d9a3-ffffffff8207d9d9: ZSTD_sizeof_matchState.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
size_t ZSTD_sizeof_matchState(const const ZSTD_compressionParameters * cParams, const ZSTD_paramSwitch_e useRowMatchFinder, const U32 enableDedicatedDictSearch, const U32 forCCtx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (0)
Location: lib/zstd/compress/zstd_compress.c:1348
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_initStaticCDict
  - lib/zstd/compress/zstd_compress.c:ZSTD_createCDict_advanced2
  - lib/zstd/compress/zstd_compress.c:ZSTD_estimateCDictSize
  - lib/zstd/compress/zstd_compress.c:ZSTD_estimateCCtxSize_usingCCtxParams_internal
```
**Symbols:**

```
ffffffff81845010-ffffffff818451ae: ZSTD_sizeof_matchState (STB_LOCAL)
ffffffff820fdf56-ffffffff820fdf8c: ZSTD_sizeof_matchState.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
size_t ZSTD_sizeof_matchState(const const ZSTD_compressionParameters * cParams, const ZSTD_paramSwitch_e useRowMatchFinder, const U32 enableDedicatedDictSearch, const U32 forCCtx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (0)
Location: lib/zstd/compress/zstd_compress.c:1348
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_initStaticCDict
  - lib/zstd/compress/zstd_compress.c:ZSTD_createCDict_advanced2
  - lib/zstd/compress/zstd_compress.c:ZSTD_estimateCDictSize
  - lib/zstd/compress/zstd_compress.c:ZSTD_estimateCCtxSize_usingCCtxParams_internal
```
**Symbols:**

```
ffffffff81896bd0-ffffffff81896d6e: ZSTD_sizeof_matchState (STB_LOCAL)
ffffffff821dc0c3-ffffffff821dc0f9: ZSTD_sizeof_matchState.cold (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const ZSTD_paramSwitch_e useRowMatchFinder</code>
</li>
<li>
<b>Param added. </b>
<code>const U32 enableDedicatedDictSearch</code>
</li>
<li>
<b>Param reordered. </b>
<code>cParams, forCCtx</code> ➡️ <code>cParams, useRowMatchFinder, enableDedicatedDictSearch, forCCtx</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
