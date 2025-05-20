# Function: <code>ZSTD_fillDoubleHashTable</code>

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
In lib/zstd/compress.c (ffffffff815b723e)
Location: lib/zstd/compress.c:1235
Inline: True
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
In lib/zstd/compress.c (ffffffff815d4713)
Location: lib/zstd/compress.c:1235
Inline: True
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
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void ZSTD_fillDoubleHashTable(ZSTD_matchState_t *ms, const void *end, ZSTD_dictTableLoadMethod_e dtlm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/zstd/compress/zstd_double_fast.c (0)
Location: lib/zstd/compress/zstd_double_fast.c:15
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_loadDictionaryContent
  - lib/zstd/compress/zstd_ldm.c:ZSTD_ldm_blockCompress
  - lib/zstd/compress/zstd_ldm.c:ZSTD_ldm_blockCompress
```
**Symbols:**

```
ffffffff81e9a590-ffffffff81e9a720: ZSTD_fillDoubleHashTable.cold (STB_LOCAL)
ffffffff81722030-ffffffff81722212: ZSTD_fillDoubleHashTable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void ZSTD_fillDoubleHashTable(ZSTD_matchState_t *ms, const void *end, ZSTD_dictTableLoadMethod_e dtlm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/zstd/compress/zstd_double_fast.c (0)
Location: lib/zstd/compress/zstd_double_fast.c:15
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_loadDictionaryContent
  - lib/zstd/compress/zstd_ldm.c:ZSTD_ldm_blockCompress
  - lib/zstd/compress/zstd_ldm.c:ZSTD_ldm_blockCompress
```
**Symbols:**

```
ffffffff820810c4-ffffffff82081254: ZSTD_fillDoubleHashTable.cold (STB_LOCAL)
ffffffff8181df10-ffffffff8181e0f2: ZSTD_fillDoubleHashTable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void ZSTD_fillDoubleHashTable(ZSTD_matchState_t *ms, const void *end, ZSTD_dictTableLoadMethod_e dtlm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/zstd/compress/zstd_double_fast.c (0)
Location: lib/zstd/compress/zstd_double_fast.c:15
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_loadDictionaryContent
  - lib/zstd/compress/zstd_ldm.c:ZSTD_ldm_blockCompress
  - lib/zstd/compress/zstd_ldm.c:ZSTD_ldm_blockCompress
```
**Symbols:**

```
ffffffff82101331-ffffffff821014c5: ZSTD_fillDoubleHashTable.cold (STB_LOCAL)
ffffffff8185e730-ffffffff8185e911: ZSTD_fillDoubleHashTable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void ZSTD_fillDoubleHashTable(ZSTD_matchState_t *ms, const void *end, ZSTD_dictTableLoadMethod_e dtlm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/zstd/compress/zstd_double_fast.c (0)
Location: lib/zstd/compress/zstd_double_fast.c:15
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_loadDictionaryContent
  - lib/zstd/compress/zstd_ldm.c:ZSTD_ldm_blockCompress
  - lib/zstd/compress/zstd_ldm.c:ZSTD_ldm_blockCompress
```
**Symbols:**

```
ffffffff821df49e-ffffffff821df632: ZSTD_fillDoubleHashTable.cold (STB_LOCAL)
ffffffff818b02f0-ffffffff818b04d1: ZSTD_fillDoubleHashTable (STB_GLOBAL)
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
