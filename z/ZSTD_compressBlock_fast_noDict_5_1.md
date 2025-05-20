# Function: <code>ZSTD_compressBlock_fast_noDict_5_1</code>

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
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
size_t ZSTD_compressBlock_fast_noDict_5_1(ZSTD_matchState_t *ms, seqStore_t *seqStore, U32 *rep, const void *src, size_t srcSize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/zstd/compress/zstd_fast.c (0)
Location: lib/zstd/compress/zstd_fast.c:326
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast
```
**Symbols:**

```
ffffffff8181f250-ffffffff8181fbef: ZSTD_compressBlock_fast_noDict_5_1 (STB_LOCAL)
ffffffff8208172a-ffffffff8208195b: ZSTD_compressBlock_fast_noDict_5_1.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
size_t ZSTD_compressBlock_fast_noDict_5_1(ZSTD_matchState_t *ms, seqStore_t *seqStore, U32 *rep, const void *src, size_t srcSize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/zstd/compress/zstd_fast.c (0)
Location: lib/zstd/compress/zstd_fast.c:326
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast
```
**Symbols:**

```
ffffffff8185fa90-ffffffff81860433: ZSTD_compressBlock_fast_noDict_5_1 (STB_LOCAL)
ffffffff8210196f-ffffffff82101be2: ZSTD_compressBlock_fast_noDict_5_1.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
size_t ZSTD_compressBlock_fast_noDict_5_1(ZSTD_matchState_t *ms, seqStore_t *seqStore, U32 *rep, const void *src, size_t srcSize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/zstd/compress/zstd_fast.c (0)
Location: lib/zstd/compress/zstd_fast.c:326
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast
```
**Symbols:**

```
ffffffff818b1650-ffffffff818b1ff3: ZSTD_compressBlock_fast_noDict_5_1 (STB_LOCAL)
ffffffff821dfadc-ffffffff821dfd4f: ZSTD_compressBlock_fast_noDict_5_1.cold (STB_LOCAL)
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
