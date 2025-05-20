# Function: <code>ZSTD_ldm_skipSequences</code>

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
void ZSTD_ldm_skipSequences(rawSeqStore_t *rawSeqStore, size_t srcSize, const U32 minMatch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_ldm.c (ffffffff81743e50)
Location: lib/zstd/compress/zstd_ldm.c:547
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_buildSeqStore
  - lib/zstd/compress/zstd_ldm.c:ZSTD_ldm_blockCompress
```
**Symbols:**

```
ffffffff81743e50-ffffffff81743f1a: ZSTD_ldm_skipSequences (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ZSTD_ldm_skipSequences(rawSeqStore_t *rawSeqStore, size_t srcSize, const U32 minMatch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_ldm.c (ffffffff8185d7a0)
Location: lib/zstd/compress/zstd_ldm.c:583
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_buildSeqStore
  - lib/zstd/compress/zstd_ldm.c:ZSTD_ldm_blockCompress
```
**Symbols:**

```
ffffffff8185d7a0-ffffffff8185d86a: ZSTD_ldm_skipSequences (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ZSTD_ldm_skipSequences(rawSeqStore_t *rawSeqStore, size_t srcSize, const U32 minMatch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_ldm.c (ffffffff8189e350)
Location: lib/zstd/compress/zstd_ldm.c:583
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_buildSeqStore
  - lib/zstd/compress/zstd_ldm.c:ZSTD_ldm_blockCompress
```
**Symbols:**

```
ffffffff8189e350-ffffffff8189e41a: ZSTD_ldm_skipSequences (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ZSTD_ldm_skipSequences(rawSeqStore_t *rawSeqStore, size_t srcSize, const U32 minMatch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_ldm.c (ffffffff818eff10)
Location: lib/zstd/compress/zstd_ldm.c:583
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_buildSeqStore
  - lib/zstd/compress/zstd_ldm.c:ZSTD_ldm_blockCompress
```
**Symbols:**

```
ffffffff818eff10-ffffffff818effda: ZSTD_ldm_skipSequences (STB_GLOBAL)
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
