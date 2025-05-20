# Function: <code>ZSTD_compressBlock_opt0</code>

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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
size_t ZSTD_compressBlock_opt0(ZSTD_matchState_t *ms, seqStore_t *seqStore, U32 *rep, const void *src, size_t srcSize, const ZSTD_dictMode_e dictMode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_opt.c (ffffffff81862050)
Location: lib/zstd/compress/zstd_opt.c:1324
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_opt.c:ZSTD_compressBlock_btopt_extDict
  - lib/zstd/compress/zstd_opt.c:ZSTD_compressBlock_btopt_dictMatchState
  - lib/zstd/compress/zstd_opt.c:ZSTD_compressBlock_btopt
```
**Symbols:**

```
ffffffff81862050-ffffffff81863263: ZSTD_compressBlock_opt0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
size_t ZSTD_compressBlock_opt0(ZSTD_matchState_t *ms, seqStore_t *seqStore, U32 *rep, const void *src, size_t srcSize, const ZSTD_dictMode_e dictMode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_opt.c (ffffffff818a2b90)
Location: lib/zstd/compress/zstd_opt.c:1324
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_opt.c:ZSTD_compressBlock_btopt_extDict
  - lib/zstd/compress/zstd_opt.c:ZSTD_compressBlock_btopt_dictMatchState
  - lib/zstd/compress/zstd_opt.c:ZSTD_compressBlock_btopt
```
**Symbols:**

```
ffffffff818a2b90-ffffffff818a3ddc: ZSTD_compressBlock_opt0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
size_t ZSTD_compressBlock_opt0(ZSTD_matchState_t *ms, seqStore_t *seqStore, U32 *rep, const void *src, size_t srcSize, const ZSTD_dictMode_e dictMode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_opt.c (ffffffff818f4750)
Location: lib/zstd/compress/zstd_opt.c:1324
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_opt.c:ZSTD_compressBlock_btopt_extDict
  - lib/zstd/compress/zstd_opt.c:ZSTD_compressBlock_btopt_dictMatchState
  - lib/zstd/compress/zstd_opt.c:ZSTD_compressBlock_btopt
```
**Symbols:**

```
ffffffff818f4750-ffffffff818f599c: ZSTD_compressBlock_opt0 (STB_LOCAL)
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
