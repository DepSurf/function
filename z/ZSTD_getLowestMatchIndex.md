# Function: <code>ZSTD_getLowestMatchIndex</code>

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
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_double_fast.c (ffffffff81721013)
Location: lib/zstd/compress/zstd_compress_internal.h:1031
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
```
```
In lib/zstd/compress/zstd_fast.c (ffffffff817297ac)
Location: lib/zstd/compress/zstd_compress_internal.h:1031
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_extDict_generic
```
```
In lib/zstd/compress/zstd_lazy.c (ffffffff81742467)
Location: lib/zstd/compress/zstd_compress_internal.h:1031
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_DUBT_findBestMatch
```
```
In lib/zstd/compress/zstd_opt.c (ffffffff81745b03)
Location: lib/zstd/compress/zstd_compress_internal.h:1031
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_opt.c:ZSTD_insertBtAndGetAllMatches
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_double_fast.c (ffffffff8181e212)
Location: lib/zstd/compress/zstd_compress_internal.h:1242
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
```
```
In lib/zstd/compress/zstd_fast.c (ffffffff81827b43)
Location: lib/zstd/compress/zstd_compress_internal.h:1242
Inline: True
```
```
In lib/zstd/compress/zstd_lazy.c (ffffffff8185b80b)
Location: lib/zstd/compress/zstd_compress_internal.h:1242
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_extDict_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_extDict_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_extDict_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_extDict_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_extDict_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_extDict_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_extDict_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_extDict_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_extDict_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_DUBT_findBestMatch
```
```
In lib/zstd/compress/zstd_opt.c (ffffffff81866b2a)
Location: lib/zstd/compress/zstd_compress_internal.h:1242
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_6
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_5
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_4
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_3
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_extDict_6
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_extDict_5
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_extDict_4
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_extDict_3
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_noDict_6
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_noDict_5
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_noDict_4
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_noDict_3
  - lib/zstd/compress/zstd_opt.c:ZSTD_insertBt1
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_double_fast.c (ffffffff8185ea35)
Location: lib/zstd/compress/zstd_compress_internal.h:1242
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
```
```
In lib/zstd/compress/zstd_fast.c (ffffffff81868339)
Location: lib/zstd/compress/zstd_compress_internal.h:1242
Inline: True
```
```
In lib/zstd/compress/zstd_lazy.c (ffffffff8189c3cc)
Location: lib/zstd/compress/zstd_compress_internal.h:1242
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_extDict_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_extDict_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_extDict_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_extDict_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_extDict_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_extDict_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_extDict_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_extDict_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_extDict_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_DUBT_findBestMatch
```
```
In lib/zstd/compress/zstd_opt.c (ffffffff818a7770)
Location: lib/zstd/compress/zstd_compress_internal.h:1242
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_6
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_5
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_4
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_3
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_extDict_6
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_extDict_5
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_extDict_4
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_extDict_3
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_noDict_6
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_noDict_5
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_noDict_4
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_noDict_3
  - lib/zstd/compress/zstd_opt.c:ZSTD_insertBt1
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_double_fast.c (ffffffff818b05f5)
Location: lib/zstd/compress/zstd_compress_internal.h:1242
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
```
```
In lib/zstd/compress/zstd_fast.c (ffffffff818b9ef9)
Location: lib/zstd/compress/zstd_compress_internal.h:1242
Inline: True
```
```
In lib/zstd/compress/zstd_lazy.c (ffffffff818edf8c)
Location: lib/zstd/compress/zstd_compress_internal.h:1242
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_extDict_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_extDict_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_extDict_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_extDict_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_extDict_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_extDict_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_extDict_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_extDict_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_extDict_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_DUBT_findBestMatch
```
```
In lib/zstd/compress/zstd_opt.c (ffffffff818f9330)
Location: lib/zstd/compress/zstd_compress_internal.h:1242
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_6
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_5
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_4
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_3
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_extDict_6
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_extDict_5
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_extDict_4
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_extDict_3
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_noDict_6
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_noDict_5
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_noDict_4
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_noDict_3
  - lib/zstd/compress/zstd_opt.c:ZSTD_insertBt1
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
