# Function: <code>ZSTD_ldm_blockCompress</code>

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
size_t ZSTD_ldm_blockCompress(rawSeqStore_t *rawSeqStore, ZSTD_matchState_t *ms, seqStore_t *seqStore, U32 *rep, const void *src, size_t srcSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_ldm.c (ffffffff81743fb0)
Location: lib/zstd/compress/zstd_ldm.c:623
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_buildSeqStore
  - lib/zstd/compress/zstd_compress.c:ZSTD_buildSeqStore
```
**Symbols:**

```
ffffffff81743fb0-ffffffff817444a2: ZSTD_ldm_blockCompress (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
size_t ZSTD_ldm_blockCompress(rawSeqStore_t *rawSeqStore, ZSTD_matchState_t *ms, seqStore_t *seqStore, U32 *rep, ZSTD_paramSwitch_e useRowMatchFinder, const void *src, size_t srcSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_ldm.c (ffffffff8185d920)
Location: lib/zstd/compress/zstd_ldm.c:660
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_buildSeqStore
  - lib/zstd/compress/zstd_compress.c:ZSTD_buildSeqStore
```
**Symbols:**

```
ffffffff8185d920-ffffffff8185de79: ZSTD_ldm_blockCompress (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
size_t ZSTD_ldm_blockCompress(rawSeqStore_t *rawSeqStore, ZSTD_matchState_t *ms, seqStore_t *seqStore, U32 *rep, ZSTD_paramSwitch_e useRowMatchFinder, const void *src, size_t srcSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_ldm.c (ffffffff8189e4d0)
Location: lib/zstd/compress/zstd_ldm.c:660
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_buildSeqStore
  - lib/zstd/compress/zstd_compress.c:ZSTD_buildSeqStore
```
**Symbols:**

```
ffffffff8189e4d0-ffffffff8189ea29: ZSTD_ldm_blockCompress (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
size_t ZSTD_ldm_blockCompress(rawSeqStore_t *rawSeqStore, ZSTD_matchState_t *ms, seqStore_t *seqStore, U32 *rep, ZSTD_paramSwitch_e useRowMatchFinder, const void *src, size_t srcSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_ldm.c (ffffffff818f0090)
Location: lib/zstd/compress/zstd_ldm.c:660
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_buildSeqStore
  - lib/zstd/compress/zstd_compress.c:ZSTD_buildSeqStore
```
**Symbols:**

```
ffffffff818f0090-ffffffff818f05e9: ZSTD_ldm_blockCompress (STB_GLOBAL)
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
<code>ZSTD_paramSwitch_e useRowMatchFinder</code>
</li>
<li>
<b>Param reordered. </b>
<code>rawSeqStore, ms, seqStore, rep, src, srcSize</code> ➡️ <code>rawSeqStore, ms, seqStore, rep, useRowMatchFinder, src, srcSize</code>
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
