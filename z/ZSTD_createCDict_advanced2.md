# Function: <code>ZSTD_createCDict_advanced2</code>

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
ZSTD_CDict *ZSTD_createCDict_advanced2(const void *dict, size_t dictSize, ZSTD_dictLoadMethod_e dictLoadMethod, ZSTD_dictContentType_e dictContentType, const ZSTD_CCtx_params *originalCctxParams, ZSTD_customMem customMem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff8171abe0)
Location: lib/zstd/compress/zstd_compress.c:3689
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_CCtx_init_compressStream2
  - lib/zstd/compress/zstd_compress.c:ZSTD_createCDict_advanced
```
**Symbols:**

```
ffffffff8171abe0-ffffffff8171aff0: ZSTD_createCDict_advanced2 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ZSTD_CDict *ZSTD_createCDict_advanced2(const void *dict, size_t dictSize, ZSTD_dictLoadMethod_e dictLoadMethod, ZSTD_dictContentType_e dictContentType, const ZSTD_CCtx_params *originalCctxParams, ZSTD_customMem customMem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff81810320)
Location: lib/zstd/compress/zstd_compress.c:4775
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_CCtx_init_compressStream2
  - lib/zstd/compress/zstd_compress.c:ZSTD_createCDict_advanced
```
**Symbols:**

```
ffffffff81810320-ffffffff818107b7: ZSTD_createCDict_advanced2 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ZSTD_CDict *ZSTD_createCDict_advanced2(const void *dict, size_t dictSize, ZSTD_dictLoadMethod_e dictLoadMethod, ZSTD_dictContentType_e dictContentType, const ZSTD_CCtx_params *originalCctxParams, ZSTD_customMem customMem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff81850e00)
Location: lib/zstd/compress/zstd_compress.c:4775
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_CCtx_init_compressStream2
  - lib/zstd/compress/zstd_compress.c:ZSTD_createCDict_advanced
```
**Symbols:**

```
ffffffff81850e00-ffffffff81851297: ZSTD_createCDict_advanced2 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ZSTD_CDict *ZSTD_createCDict_advanced2(const void *dict, size_t dictSize, ZSTD_dictLoadMethod_e dictLoadMethod, ZSTD_dictContentType_e dictContentType, const ZSTD_CCtx_params *originalCctxParams, ZSTD_customMem customMem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff818a29c0)
Location: lib/zstd/compress/zstd_compress.c:4775
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_CCtx_init_compressStream2
  - lib/zstd/compress/zstd_compress.c:ZSTD_createCDict_advanced
```
**Symbols:**

```
ffffffff818a29c0-ffffffff818a2e57: ZSTD_createCDict_advanced2 (STB_GLOBAL)
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
