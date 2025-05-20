# Function: <code>ZSTD_loadDictionaryContent</code>

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
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
size_t ZSTD_loadDictionaryContent(ZSTD_CCtx *zc, const void *src, size_t srcSize);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/compress.c (ffffffff815b71b0)
Location: lib/zstd/compress.c:2557
Inline: True
Direct callers:
  - lib/zstd/compress.c:ZSTD_initCDict
  - lib/zstd/compress.c:ZSTD_compress_usingDict
  - lib/zstd/compress.c:ZSTD_loadZstdDictionary
```
**Symbols:**

```
ffffffff815b71b0-ffffffff815b754b: ZSTD_loadDictionaryContent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
size_t ZSTD_loadDictionaryContent(ZSTD_CCtx *zc, const void *src, size_t srcSize);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/compress.c (ffffffff815d4680)
Location: lib/zstd/compress.c:2557
Inline: True
Direct callers:
  - lib/zstd/compress.c:ZSTD_initCDict
  - lib/zstd/compress.c:ZSTD_compress_usingDict
  - lib/zstd/compress.c:ZSTD_loadZstdDictionary
```
**Symbols:**

```
ffffffff815d4680-ffffffff815d4a20: ZSTD_loadDictionaryContent (STB_LOCAL)
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
size_t ZSTD_loadDictionaryContent(ZSTD_matchState_t *ms, ldmState_t *ls, ZSTD_cwksp *ws, const ZSTD_CCtx_params *params, const void *src, size_t srcSize, ZSTD_dictTableLoadMethod_e dtlm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff81713440)
Location: lib/zstd/compress/zstd_compress.c:3049
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_compress_insertDictionary
  - lib/zstd/compress/zstd_compress.c:ZSTD_compress_insertDictionary
```
**Symbols:**

```
ffffffff81713440-ffffffff81713729: ZSTD_loadDictionaryContent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
size_t ZSTD_loadDictionaryContent(ZSTD_matchState_t *ms, ldmState_t *ls, ZSTD_cwksp *ws, const ZSTD_CCtx_params *params, const void *src, size_t srcSize, ZSTD_dictTableLoadMethod_e dtlm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (0)
Location: lib/zstd/compress/zstd_compress.c:4109
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_compress_insertDictionary
  - lib/zstd/compress/zstd_compress.c:ZSTD_compress_insertDictionary
```
**Symbols:**

```
ffffffff81806a70-ffffffff81806d9f: ZSTD_loadDictionaryContent (STB_LOCAL)
ffffffff8207dc27-ffffffff8207dc44: ZSTD_loadDictionaryContent.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
size_t ZSTD_loadDictionaryContent(ZSTD_matchState_t *ms, ldmState_t *ls, ZSTD_cwksp *ws, const ZSTD_CCtx_params *params, const void *src, size_t srcSize, ZSTD_dictTableLoadMethod_e dtlm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (0)
Location: lib/zstd/compress/zstd_compress.c:4109
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_compress_insertDictionary
  - lib/zstd/compress/zstd_compress.c:ZSTD_compress_insertDictionary
```
**Symbols:**

```
ffffffff81847440-ffffffff81847774: ZSTD_loadDictionaryContent (STB_LOCAL)
ffffffff820fe1da-ffffffff820fe1f7: ZSTD_loadDictionaryContent.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
size_t ZSTD_loadDictionaryContent(ZSTD_matchState_t *ms, ldmState_t *ls, ZSTD_cwksp *ws, const ZSTD_CCtx_params *params, const void *src, size_t srcSize, ZSTD_dictTableLoadMethod_e dtlm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (0)
Location: lib/zstd/compress/zstd_compress.c:4109
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_compress_insertDictionary
  - lib/zstd/compress/zstd_compress.c:ZSTD_compress_insertDictionary
```
**Symbols:**

```
ffffffff81899000-ffffffff81899334: ZSTD_loadDictionaryContent (STB_LOCAL)
ffffffff821dc347-ffffffff821dc364: ZSTD_loadDictionaryContent.cold (STB_LOCAL)
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
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
