# Function: <code>ZSTD_overflowCorrectIfNeeded</code>

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

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff81713600)
Location: lib/zstd/compress/zstd_compress.c:2756
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_loadDictionaryContent
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressContinue_internal
  - lib/zstd/compress/zstd_compress.c:ZSTD_compress_frameChunk
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_loadDictionaryContent
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressContinue_internal
  - lib/zstd/compress/zstd_compress.c:ZSTD_compress_frameChunk
```
**Symbols:**

```
ffffffff81713150-ffffffff8171343d: ZSTD_overflowCorrectIfNeeded.part.0 (STB_LOCAL)
ffffffff81e96fdf-ffffffff81e970c5: ZSTD_overflowCorrectIfNeeded.part.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void ZSTD_overflowCorrectIfNeeded(ZSTD_matchState_t *ms, ZSTD_cwksp *ws, const ZSTD_CCtx_params *params, const void *ip, const void *iend);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (0)
Location: lib/zstd/compress/zstd_compress.c:3810
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_loadDictionaryContent
  - lib/zstd/compress/zstd_compress.c:ZSTD_loadDictionaryContent
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressContinue_internal
  - lib/zstd/compress/zstd_compress.c:ZSTD_compress_frameChunk
```
**Symbols:**

```
ffffffff818066f0-ffffffff81806a60: ZSTD_overflowCorrectIfNeeded (STB_LOCAL)
ffffffff8207db81-ffffffff8207dc27: ZSTD_overflowCorrectIfNeeded.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void ZSTD_overflowCorrectIfNeeded(ZSTD_matchState_t *ms, ZSTD_cwksp *ws, const ZSTD_CCtx_params *params, const void *ip, const void *iend);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (0)
Location: lib/zstd/compress/zstd_compress.c:3810
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_loadDictionaryContent
  - lib/zstd/compress/zstd_compress.c:ZSTD_loadDictionaryContent
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressContinue_internal
  - lib/zstd/compress/zstd_compress.c:ZSTD_compress_frameChunk
```
**Symbols:**

```
ffffffff818470c0-ffffffff81847430: ZSTD_overflowCorrectIfNeeded (STB_LOCAL)
ffffffff820fe134-ffffffff820fe1da: ZSTD_overflowCorrectIfNeeded.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void ZSTD_overflowCorrectIfNeeded(ZSTD_matchState_t *ms, ZSTD_cwksp *ws, const ZSTD_CCtx_params *params, const void *ip, const void *iend);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (0)
Location: lib/zstd/compress/zstd_compress.c:3810
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_loadDictionaryContent
  - lib/zstd/compress/zstd_compress.c:ZSTD_loadDictionaryContent
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressContinue_internal
  - lib/zstd/compress/zstd_compress.c:ZSTD_compress_frameChunk
```
**Symbols:**

```
ffffffff81898c80-ffffffff81898ff0: ZSTD_overflowCorrectIfNeeded (STB_LOCAL)
ffffffff821dc2a1-ffffffff821dc347: ZSTD_overflowCorrectIfNeeded.cold (STB_LOCAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
