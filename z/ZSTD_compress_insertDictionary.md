# Function: <code>ZSTD_compress_insertDictionary</code>

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
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/zstd/compress.c (ffffffff815b958f)
Location: lib/zstd/compress.c:2723
Inline: True
Inline callers:
  - lib/zstd/compress.c:ZSTD_initCDict
  - lib/zstd/compress.c:ZSTD_compress_usingDict
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
In lib/zstd/compress.c (ffffffff815d6a74)
Location: lib/zstd/compress.c:2723
Inline: True
Inline callers:
  - lib/zstd/compress.c:ZSTD_initCDict
  - lib/zstd/compress.c:ZSTD_compress_usingDict
```
</details>
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
size_t ZSTD_compress_insertDictionary(ZSTD_compressedBlockState_t *bs, ZSTD_matchState_t *ms, ldmState_t *ls, ZSTD_cwksp *ws, const ZSTD_CCtx_params *params, const void *dict, size_t dictSize, ZSTD_dictContentType_e dictContentType, ZSTD_dictTableLoadMethod_e dtlm, void *workspace);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff81718c20)
Location: lib/zstd/compress/zstd_compress.c:3274
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_initCDict_internal
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressBegin_internal
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressBegin_internal
```
**Symbols:**

```
ffffffff81718c20-ffffffff81718d8c: ZSTD_compress_insertDictionary (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
size_t ZSTD_compress_insertDictionary(ZSTD_compressedBlockState_t *bs, ZSTD_matchState_t *ms, ldmState_t *ls, ZSTD_cwksp *ws, const ZSTD_CCtx_params *params, const void *dict, size_t dictSize, ZSTD_dictContentType_e dictContentType, ZSTD_dictTableLoadMethod_e dtlm, void *workspace);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff8180e060)
Location: lib/zstd/compress/zstd_compress.c:4356
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_initCDict_internal
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressBegin_usingDict
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressBegin_internal
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressBegin_internal
```
**Symbols:**

```
ffffffff8180e060-ffffffff8180e1cc: ZSTD_compress_insertDictionary (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
size_t ZSTD_compress_insertDictionary(ZSTD_compressedBlockState_t *bs, ZSTD_matchState_t *ms, ldmState_t *ls, ZSTD_cwksp *ws, const ZSTD_CCtx_params *params, const void *dict, size_t dictSize, ZSTD_dictContentType_e dictContentType, ZSTD_dictTableLoadMethod_e dtlm, void *workspace);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff8184eb70)
Location: lib/zstd/compress/zstd_compress.c:4356
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_initCDict_internal
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressBegin_usingDict
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressBegin_internal
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressBegin_internal
```
**Symbols:**

```
ffffffff8184eb70-ffffffff8184ecdc: ZSTD_compress_insertDictionary (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
size_t ZSTD_compress_insertDictionary(ZSTD_compressedBlockState_t *bs, ZSTD_matchState_t *ms, ldmState_t *ls, ZSTD_cwksp *ws, const ZSTD_CCtx_params *params, const void *dict, size_t dictSize, ZSTD_dictContentType_e dictContentType, ZSTD_dictTableLoadMethod_e dtlm, void *workspace);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff818a0730)
Location: lib/zstd/compress/zstd_compress.c:4356
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_initCDict_internal
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressBegin_usingDict
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressBegin_internal
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressBegin_internal
```
**Symbols:**

```
ffffffff818a0730-ffffffff818a089c: ZSTD_compress_insertDictionary (STB_LOCAL)
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
