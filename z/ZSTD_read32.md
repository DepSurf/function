# Function: <code>ZSTD_read32</code>

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
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/zstd/fse_compress.c (ffffffff815ac803)
Location: lib/zstd/mem.h:61
Inline: True
Inline callers:
  - lib/zstd/fse_compress.c:FSE_count_wksp
  - lib/zstd/fse_compress.c:FSE_count_wksp
  - lib/zstd/fse_compress.c:FSE_count_wksp
  - lib/zstd/fse_compress.c:FSE_count_wksp
  - lib/zstd/fse_compress.c:FSE_count_wksp
```
```
In lib/zstd/compress.c (ffffffff815bca2f)
Location: lib/zstd/mem.h:61
Inline: True
Inline callers:
  - lib/zstd/compress.c:ZSTD_compressBlock_btopt2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_btopt2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_btopt2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_btopt2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_btopt_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_btopt_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_btopt_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_btopt_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_btopt2
  - lib/zstd/compress.c:ZSTD_compressBlock_btopt2
  - lib/zstd/compress.c:ZSTD_compressBlock_btopt2
  - lib/zstd/compress.c:ZSTD_compressBlock_btopt2
  - lib/zstd/compress.c:ZSTD_compressBlock_btopt
  - lib/zstd/compress.c:ZSTD_compressBlock_btopt
  - lib/zstd/compress.c:ZSTD_compressBlock_btopt
  - lib/zstd/compress.c:ZSTD_compressBlock_btopt
  - lib/zstd/compress.c:ZSTD_BtGetAllMatches_selectMLS
  - lib/zstd/compress.c:ZSTD_compressBlock_btlazy2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_btlazy2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_btlazy2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_btlazy2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_btlazy2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_btlazy2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_btlazy2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_btlazy2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_greedy_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_greedy_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_greedy_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_greedy_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_greedy_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_greedy_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_greedy_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_greedy_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_greedy_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_greedy_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_greedy_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_greedy
  - lib/zstd/compress.c:ZSTD_compressBlock_greedy
  - lib/zstd/compress.c:ZSTD_compressBlock_greedy
  - lib/zstd/compress.c:ZSTD_compressBlock_greedy
  - lib/zstd/compress.c:ZSTD_compressBlock_greedy
  - lib/zstd/compress.c:ZSTD_compressBlock_greedy
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2
  - lib/zstd/compress.c:ZSTD_compressBlock_btlazy2
  - lib/zstd/compress.c:ZSTD_compressBlock_btlazy2
  - lib/zstd/compress.c:ZSTD_compressBlock_btlazy2
  - lib/zstd/compress.c:ZSTD_compressBlock_btlazy2
  - lib/zstd/compress.c:ZSTD_compressBlock_btlazy2
  - lib/zstd/compress.c:ZSTD_compressBlock_btlazy2
  - lib/zstd/compress.c:ZSTD_compressBlock_btlazy2
  - lib/zstd/compress.c:ZSTD_compressBlock_btlazy2
  - lib/zstd/compress.c:ZSTD_updateTree
  - lib/zstd/compress.c:ZSTD_insertBtAndFindBestMatch
  - lib/zstd/compress.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress.c:ZSTD_compressBlock_fast_extDict_generic
  - lib/zstd/compress.c:ZSTD_compressBlock_fast_extDict_generic
  - lib/zstd/compress.c:ZSTD_compressBlock_fast_extDict_generic
  - lib/zstd/compress.c:ZSTD_compressBlock_fast_extDict_generic
  - lib/zstd/compress.c:ZSTD_compressBlock_fast_extDict_generic
  - lib/zstd/compress.c:ZSTD_compressBlock_fast_extDict_generic
  - lib/zstd/compress.c:ZSTD_compressBlock_fast_extDict_generic
  - lib/zstd/compress.c:ZSTD_compressBlock_fast
  - lib/zstd/compress.c:ZSTD_compressBlock_fast
  - lib/zstd/compress.c:ZSTD_compressBlock_fast
  - lib/zstd/compress.c:ZSTD_compressBlock_fast
  - lib/zstd/compress.c:ZSTD_compressBlock_fast
  - lib/zstd/compress.c:ZSTD_compressBlock_fast
  - lib/zstd/compress.c:ZSTD_compressBlock_fast
  - lib/zstd/compress.c:ZSTD_compressBlock_fast
  - lib/zstd/compress.c:ZSTD_compressBlock_fast
  - lib/zstd/compress.c:ZSTD_compressBlock_fast
  - lib/zstd/compress.c:ZSTD_compressBlock_fast
  - lib/zstd/compress.c:ZSTD_compressBlock_fast
  - lib/zstd/compress.c:ZSTD_compressBlock_fast
  - lib/zstd/compress.c:ZSTD_compressBlock_fast
  - lib/zstd/compress.c:ZSTD_compressBlock_fast
  - lib/zstd/compress.c:ZSTD_compressBlock_fast
  - lib/zstd/compress.c:ZSTD_compressBlock_fast
  - lib/zstd/compress.c:ZSTD_compressBlock_fast
  - lib/zstd/compress.c:ZSTD_compressBlock_fast
  - lib/zstd/compress.c:ZSTD_compressBlock_fast
  - lib/zstd/compress.c:ZSTD_compressBlock_fast
  - lib/zstd/compress.c:ZSTD_compressBlock_fast
  - lib/zstd/compress.c:ZSTD_compressBlock_fast
  - lib/zstd/compress.c:ZSTD_compressBlock_fast
  - lib/zstd/compress.c:ZSTD_compressBlock_fast
  - lib/zstd/compress.c:ZSTD_compressBlock_fast
  - lib/zstd/compress.c:ZSTD_compressBlock_fast
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/zstd/fse_compress.c (ffffffff815c8308)
Location: lib/zstd/mem.h:61
Inline: True
Inline callers:
  - lib/zstd/fse_compress.c:FSE_count_wksp
  - lib/zstd/fse_compress.c:FSE_count_wksp
  - lib/zstd/fse_compress.c:FSE_count_wksp
  - lib/zstd/fse_compress.c:FSE_count_wksp
  - lib/zstd/fse_compress.c:FSE_count_wksp
```
```
In lib/zstd/compress.c (ffffffff815e3816)
Location: lib/zstd/mem.h:61
Inline: True
Inline callers:
  - lib/zstd/compress.c:ZSTD_compressBlock_btopt2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_btopt2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_btopt2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_btopt2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_btopt_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_btopt_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_btopt_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_btopt_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_btopt2
  - lib/zstd/compress.c:ZSTD_compressBlock_btopt2
  - lib/zstd/compress.c:ZSTD_compressBlock_btopt2
  - lib/zstd/compress.c:ZSTD_compressBlock_btopt2
  - lib/zstd/compress.c:ZSTD_compressBlock_btopt
  - lib/zstd/compress.c:ZSTD_compressBlock_btopt
  - lib/zstd/compress.c:ZSTD_compressBlock_btopt
  - lib/zstd/compress.c:ZSTD_compressBlock_btopt
  - lib/zstd/compress.c:ZSTD_BtGetAllMatches_selectMLS_extDict
  - lib/zstd/compress.c:ZSTD_BtGetAllMatches_selectMLS
  - lib/zstd/compress.c:ZSTD_compressBlock_btlazy2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_btlazy2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_btlazy2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_btlazy2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_btlazy2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_btlazy2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_btlazy2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_btlazy2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_greedy_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_greedy_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_greedy_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_greedy_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_greedy_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_greedy_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_greedy_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_greedy_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_greedy_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_greedy_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_greedy_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_greedy
  - lib/zstd/compress.c:ZSTD_compressBlock_greedy
  - lib/zstd/compress.c:ZSTD_compressBlock_greedy
  - lib/zstd/compress.c:ZSTD_compressBlock_greedy
  - lib/zstd/compress.c:ZSTD_compressBlock_greedy
  - lib/zstd/compress.c:ZSTD_compressBlock_greedy
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2
  - lib/zstd/compress.c:ZSTD_compressBlock_lazy2
  - lib/zstd/compress.c:ZSTD_compressBlock_btlazy2
  - lib/zstd/compress.c:ZSTD_compressBlock_btlazy2
  - lib/zstd/compress.c:ZSTD_compressBlock_btlazy2
  - lib/zstd/compress.c:ZSTD_compressBlock_btlazy2
  - lib/zstd/compress.c:ZSTD_compressBlock_btlazy2
  - lib/zstd/compress.c:ZSTD_compressBlock_btlazy2
  - lib/zstd/compress.c:ZSTD_compressBlock_btlazy2
  - lib/zstd/compress.c:ZSTD_compressBlock_btlazy2
  - lib/zstd/compress.c:ZSTD_updateTree
  - lib/zstd/compress.c:ZSTD_insertBtAndFindBestMatch
  - lib/zstd/compress.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress.c:ZSTD_compressBlock_fast_extDict_generic
  - lib/zstd/compress.c:ZSTD_compressBlock_fast_extDict_generic
  - lib/zstd/compress.c:ZSTD_compressBlock_fast_extDict_generic
  - lib/zstd/compress.c:ZSTD_compressBlock_fast_extDict_generic
  - lib/zstd/compress.c:ZSTD_compressBlock_fast_extDict_generic
  - lib/zstd/compress.c:ZSTD_compressBlock_fast_extDict_generic
  - lib/zstd/compress.c:ZSTD_compressBlock_fast_extDict_generic
  - lib/zstd/compress.c:ZSTD_compressBlock_fast
  - lib/zstd/compress.c:ZSTD_compressBlock_fast
  - lib/zstd/compress.c:ZSTD_compressBlock_fast
  - lib/zstd/compress.c:ZSTD_compressBlock_fast
  - lib/zstd/compress.c:ZSTD_compressBlock_fast
  - lib/zstd/compress.c:ZSTD_compressBlock_fast
  - lib/zstd/compress.c:ZSTD_compressBlock_fast
  - lib/zstd/compress.c:ZSTD_compressBlock_fast
  - lib/zstd/compress.c:ZSTD_compressBlock_fast
  - lib/zstd/compress.c:ZSTD_compressBlock_fast
  - lib/zstd/compress.c:ZSTD_compressBlock_fast
  - lib/zstd/compress.c:ZSTD_compressBlock_fast
  - lib/zstd/compress.c:ZSTD_compressBlock_fast
  - lib/zstd/compress.c:ZSTD_compressBlock_fast
  - lib/zstd/compress.c:ZSTD_compressBlock_fast
  - lib/zstd/compress.c:ZSTD_compressBlock_fast
  - lib/zstd/compress.c:ZSTD_compressBlock_fast
  - lib/zstd/compress.c:ZSTD_compressBlock_fast
  - lib/zstd/compress.c:ZSTD_compressBlock_fast
  - lib/zstd/compress.c:ZSTD_compressBlock_fast
  - lib/zstd/compress.c:ZSTD_compressBlock_fast
  - lib/zstd/compress.c:ZSTD_compressBlock_fast
  - lib/zstd/compress.c:ZSTD_compressBlock_fast
  - lib/zstd/compress.c:ZSTD_compressBlock_fast
  - lib/zstd/compress.c:ZSTD_compressBlock_fast
  - lib/zstd/compress.c:ZSTD_compressBlock_fast
  - lib/zstd/compress.c:ZSTD_compressBlock_fast
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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
