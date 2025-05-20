# Function: <code>ZSTD_ldm_generateSequences</code>

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
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
size_t ZSTD_ldm_generateSequences(ldmState_t *ldmState, rawSeqStore_t *sequences, const ldmParams_t *params, const void *src, size_t srcSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/zstd/compress/zstd_ldm.c (0)
Location: lib/zstd/compress/zstd_ldm.c:470
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_buildSeqStore
```
**Symbols:**

```
ffffffff81ea30bb-ffffffff81ea3105: ZSTD_ldm_generateSequences.cold (STB_LOCAL)
ffffffff81743c40-ffffffff81743e4c: ZSTD_ldm_generateSequences (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
size_t ZSTD_ldm_generateSequences(ldmState_t *ldmState, rawSeqStore_t *sequences, const ldmParams_t *params, const void *src, size_t srcSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/zstd/compress/zstd_ldm.c (0)
Location: lib/zstd/compress/zstd_ldm.c:505
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_buildSeqStore
```
**Symbols:**

```
ffffffff8208a4ee-ffffffff8208a540: ZSTD_ldm_generateSequences.cold (STB_LOCAL)
ffffffff8185d570-ffffffff8185d78b: ZSTD_ldm_generateSequences (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
size_t ZSTD_ldm_generateSequences(ldmState_t *ldmState, rawSeqStore_t *sequences, const ldmParams_t *params, const void *src, size_t srcSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/zstd/compress/zstd_ldm.c (0)
Location: lib/zstd/compress/zstd_ldm.c:505
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_buildSeqStore
```
**Symbols:**

```
ffffffff8210a945-ffffffff8210a997: ZSTD_ldm_generateSequences.cold (STB_LOCAL)
ffffffff8189e120-ffffffff8189e33b: ZSTD_ldm_generateSequences (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
size_t ZSTD_ldm_generateSequences(ldmState_t *ldmState, rawSeqStore_t *sequences, const ldmParams_t *params, const void *src, size_t srcSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/zstd/compress/zstd_ldm.c (0)
Location: lib/zstd/compress/zstd_ldm.c:505
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_buildSeqStore
```
**Symbols:**

```
ffffffff821e8ab2-ffffffff821e8b04: ZSTD_ldm_generateSequences.cold (STB_LOCAL)
ffffffff818efce0-ffffffff818efefb: ZSTD_ldm_generateSequences (STB_GLOBAL)
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
