# Function: <code>ZSTD_count</code>

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
size_t ZSTD_count(const BYTE *pIn, const BYTE *pMatch, const const BYTE * pInLimit);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/compress.c (ffffffff815afa50)
Location: lib/zstd/compress.c:907
Inline: True
Direct callers:
  - lib/zstd/compress.c:ZSTD_compressBlock_btopt2
  - lib/zstd/compress.c:ZSTD_compressBlock_btopt2
  - lib/zstd/compress.c:ZSTD_compressBlock_btopt
  - lib/zstd/compress.c:ZSTD_compressBlock_btopt
  - lib/zstd/compress.c:ZSTD_BtGetAllMatches_selectMLS
  - lib/zstd/compress.c:ZSTD_BtGetAllMatches_selectMLS
  - lib/zstd/compress.c:ZSTD_insertBtAndGetAllMatches
  - lib/zstd/compress.c:ZSTD_insertBtAndGetAllMatches
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
  - lib/zstd/compress.c:ZSTD_compressBlock_greedy_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_greedy_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_greedy_extDict
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
  - lib/zstd/compress.c:ZSTD_updateTree
  - lib/zstd/compress.c:ZSTD_insertBtAndFindBestMatch
  - lib/zstd/compress.c:ZSTD_insertBtAndFindBestMatch
  - lib/zstd/compress.c:ZSTD_insertBtAndFindBestMatch
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
**Symbols:**

```
ffffffff815afa50-ffffffff815afad5: ZSTD_count (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
size_t ZSTD_count(const BYTE *pIn, const BYTE *pMatch, const const BYTE * pInLimit);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/compress.c (ffffffff815cb6e0)
Location: lib/zstd/compress.c:907
Inline: True
Direct callers:
  - lib/zstd/compress.c:ZSTD_compressBlock_btopt2
  - lib/zstd/compress.c:ZSTD_compressBlock_btopt2
  - lib/zstd/compress.c:ZSTD_compressBlock_btopt
  - lib/zstd/compress.c:ZSTD_compressBlock_btopt
  - lib/zstd/compress.c:ZSTD_BtGetAllMatches_selectMLS_extDict
  - lib/zstd/compress.c:ZSTD_BtGetAllMatches_selectMLS_extDict
  - lib/zstd/compress.c:ZSTD_BtGetAllMatches_selectMLS_extDict
  - lib/zstd/compress.c:ZSTD_BtGetAllMatches_selectMLS_extDict
  - lib/zstd/compress.c:ZSTD_BtGetAllMatches_selectMLS_extDict
  - lib/zstd/compress.c:ZSTD_BtGetAllMatches_selectMLS_extDict
  - lib/zstd/compress.c:ZSTD_BtGetAllMatches_selectMLS_extDict
  - lib/zstd/compress.c:ZSTD_BtGetAllMatches_selectMLS_extDict
  - lib/zstd/compress.c:ZSTD_BtGetAllMatches_selectMLS_extDict
  - lib/zstd/compress.c:ZSTD_BtGetAllMatches_selectMLS
  - lib/zstd/compress.c:ZSTD_BtGetAllMatches_selectMLS
  - lib/zstd/compress.c:ZSTD_BtGetAllMatches_selectMLS
  - lib/zstd/compress.c:ZSTD_insertBtAndGetAllMatches
  - lib/zstd/compress.c:ZSTD_insertBtAndGetAllMatches
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
  - lib/zstd/compress.c:ZSTD_compressBlock_btlazy2
  - lib/zstd/compress.c:ZSTD_compressBlock_btlazy2
  - lib/zstd/compress.c:ZSTD_compressBlock_btlazy2
  - lib/zstd/compress.c:ZSTD_compressBlock_btlazy2
  - lib/zstd/compress.c:ZSTD_updateTree
  - lib/zstd/compress.c:ZSTD_insertBtAndFindBestMatch
  - lib/zstd/compress.c:ZSTD_insertBtAndFindBestMatch
  - lib/zstd/compress.c:ZSTD_insertBtAndFindBestMatch
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
**Symbols:**

```
ffffffff815cb6e0-ffffffff815cb770: ZSTD_count (STB_LOCAL)
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
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
size_t ZSTD_count(const BYTE *pIn, const BYTE *pMatch, const const BYTE * pInLimit);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff81712397)
Location: lib/zstd/compress/zstd_compress_internal.h:615
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_isRLE
```
```
In lib/zstd/compress/zstd_double_fast.c (ffffffff81e9932c)
Location: lib/zstd/compress/zstd_compress_internal.h:615
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_count_2segments
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_count_2segments
```
```
In lib/zstd/compress/zstd_fast.c (ffffffff817299b2)
Location: lib/zstd/compress/zstd_compress_internal.h:615
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_extDict_generic
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_extDict_generic
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_extDict_generic
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_extDict_generic
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_extDict_generic
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_extDict_generic
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast
```
```
In lib/zstd/compress/zstd_lazy.c (ffffffff817406a0)
Location: lib/zstd/compress/zstd_compress_internal.h:615
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dedicatedDictSearch
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dedicatedDictSearch
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dedicatedDictSearch
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dedicatedDictSearch
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dedicatedDictSearch
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dictMatchState
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dictMatchState
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dictMatchState
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dictMatchState
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dictMatchState
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2_dictMatchState
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2
  - lib/zstd/compress/zstd_lazy.c:ZSTD_DUBT_findBestMatch
  - lib/zstd/compress/zstd_lazy.c:ZSTD_DUBT_findBestMatch
  - lib/zstd/compress/zstd_lazy.c:ZSTD_insertDUBT1
  - lib/zstd/compress/zstd_lazy.c:ZSTD_insertDUBT1
Direct callers:
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dedicatedDictSearch
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dedicatedDictSearch
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dedicatedDictSearch
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dedicatedDictSearch
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dedicatedDictSearch
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dedicatedDictSearch
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dedicatedDictSearch
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dedicatedDictSearch
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dedicatedDictSearch
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dictMatchState
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dictMatchState
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dictMatchState
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dictMatchState
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dictMatchState
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dictMatchState
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dictMatchState
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dictMatchState
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dictMatchState
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2_dictMatchState
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2_dictMatchState
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2_dictMatchState
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2
  - lib/zstd/compress/zstd_lazy.c:ZSTD_DUBT_findBestMatch
  - lib/zstd/compress/zstd_lazy.c:ZSTD_insertDUBT1
```
```
In lib/zstd/compress/zstd_ldm.c (ffffffff817433df)
Location: lib/zstd/compress/zstd_compress_internal.h:615
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_ldm.c:ZSTD_ldm_generateSequences_internal
  - lib/zstd/compress/zstd_ldm.c:ZSTD_ldm_generateSequences_internal
  - lib/zstd/compress/zstd_ldm.c:ZSTD_ldm_generateSequences_internal
```
```
In lib/zstd/compress/zstd_opt.c (ffffffff81745cb8)
Location: lib/zstd/compress/zstd_compress_internal.h:615
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_opt.c:ZSTD_insertBtAndGetAllMatches
  - lib/zstd/compress/zstd_opt.c:ZSTD_insertBtAndGetAllMatches
  - lib/zstd/compress/zstd_opt.c:ZSTD_insertBtAndGetAllMatches
  - lib/zstd/compress/zstd_opt.c:ZSTD_insertBtAndGetAllMatches
  - lib/zstd/compress/zstd_opt.c:ZSTD_insertBtAndGetAllMatches
  - lib/zstd/compress/zstd_opt.c:ZSTD_insertBtAndGetAllMatches
  - lib/zstd/compress/zstd_opt.c:ZSTD_insertBtAndGetAllMatches
  - lib/zstd/compress/zstd_opt.c:ZSTD_insertBt1
  - lib/zstd/compress/zstd_opt.c:ZSTD_insertBt1
  - lib/zstd/compress/zstd_opt.c:ZSTD_insertBt1
```
**Symbols:**

```
ffffffff8172f880-ffffffff8172f976: ZSTD_count (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline ⚠️</summary>

```c
size_t ZSTD_count(const BYTE *pIn, const BYTE *pMatch, const const BYTE * pInLimit);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff81804f37)
Location: lib/zstd/compress/zstd_compress_internal.h:741
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_isRLE
```
```
In lib/zstd/compress/zstd_double_fast.c (ffffffff8181af7a)
Location: lib/zstd/compress/zstd_compress_internal.h:741
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_7
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_7
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_7
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_6
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_6
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_6
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_5
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_5
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_5
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_4
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_4
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_4
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_7
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_7
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_7
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_7
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_7
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_6
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_6
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_6
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_6
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_6
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_5
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_5
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_5
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_5
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_5
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_4
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_4
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_4
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_4
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_4
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_count_2segments
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_count_2segments
```
```
In lib/zstd/compress/zstd_fast.c (ffffffff81822851)
Location: lib/zstd/compress/zstd_compress_internal.h:741
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_7_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_7_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_7_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_6_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_6_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_6_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_5_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_5_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_5_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_4_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_4_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_4_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_7_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_7_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_6_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_6_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_5_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_5_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_4_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_4_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_7_1
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_7_1
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_6_1
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_6_1
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_5_1
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_5_1
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_4_1
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_4_1
```
```
In lib/zstd/compress/zstd_lazy.c (ffffffff81858804)
Location: lib/zstd/compress/zstd_compress_internal.h:741
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dedicatedDictSearch
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dedicatedDictSearch
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dedicatedDictSearch
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dedicatedDictSearch
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dedicatedDictSearch
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dedicatedDictSearch
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dedicatedDictSearch
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dedicatedDictSearch
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dedicatedDictSearch
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dedicatedDictSearch
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dictMatchState
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dictMatchState
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dictMatchState
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dictMatchState
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dictMatchState
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dictMatchState
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dictMatchState
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dictMatchState
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dictMatchState
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dictMatchState
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2_dictMatchState
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2_dictMatchState
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2
  - lib/zstd/compress/zstd_lazy.c:ZSTD_DUBT_findBestMatch
  - lib/zstd/compress/zstd_lazy.c:ZSTD_DUBT_findBestMatch
  - lib/zstd/compress/zstd_lazy.c:ZSTD_DUBT_findBestMatch
  - lib/zstd/compress/zstd_lazy.c:ZSTD_insertDUBT1
  - lib/zstd/compress/zstd_lazy.c:ZSTD_insertDUBT1
  - lib/zstd/compress/zstd_lazy.c:ZSTD_insertDUBT1
Direct callers:
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_row
```
```
In lib/zstd/compress/zstd_ldm.c (ffffffff8185cca7)
Location: lib/zstd/compress/zstd_compress_internal.h:741
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_ldm.c:ZSTD_ldm_generateSequences_internal
  - lib/zstd/compress/zstd_ldm.c:ZSTD_ldm_generateSequences_internal
  - lib/zstd/compress/zstd_ldm.c:ZSTD_ldm_generateSequences_internal
```
```
In lib/zstd/compress/zstd_opt.c (ffffffff81866cde)
Location: lib/zstd/compress/zstd_compress_internal.h:741
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_6
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_6
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_6
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_6
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_5
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_5
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_5
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_5
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_4
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_4
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_4
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_4
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_3
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_3
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_3
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_3
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_3
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_extDict_6
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_extDict_6
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_extDict_6
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_extDict_6
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_extDict_5
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_extDict_5
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_extDict_5
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_extDict_5
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_extDict_4
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_extDict_4
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_extDict_4
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_extDict_4
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_extDict_3
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_extDict_3
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_extDict_3
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_extDict_3
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_extDict_3
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_noDict_6
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_noDict_6
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_noDict_5
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_noDict_5
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_noDict_4
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_noDict_4
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_noDict_3
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_noDict_3
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_noDict_3
  - lib/zstd/compress/zstd_opt.c:ZSTD_insertBt1
  - lib/zstd/compress/zstd_opt.c:ZSTD_insertBt1
  - lib/zstd/compress/zstd_opt.c:ZSTD_insertBt1
```
**Symbols:**

```
ffffffff81828bf0-ffffffff81828ce6: ZSTD_count (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Selective Inline ⚠️</summary>

```c
size_t ZSTD_count(const BYTE *pIn, const BYTE *pMatch, const const BYTE * pInLimit);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff81845948)
Location: lib/zstd/compress/zstd_compress_internal.h:741
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_isRLE
```
```
In lib/zstd/compress/zstd_double_fast.c (ffffffff8185b75b)
Location: lib/zstd/compress/zstd_compress_internal.h:741
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_7
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_7
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_7
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_6
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_6
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_6
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_5
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_5
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_5
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_4
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_4
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_4
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_7
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_7
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_7
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_7
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_7
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_6
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_6
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_6
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_6
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_6
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_5
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_5
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_5
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_5
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_5
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_4
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_4
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_4
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_4
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_4
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_count_2segments
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_count_2segments
```
```
In lib/zstd/compress/zstd_fast.c (ffffffff8186309d)
Location: lib/zstd/compress/zstd_compress_internal.h:741
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_7_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_7_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_7_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_6_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_6_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_6_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_5_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_5_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_5_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_4_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_4_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_4_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_7_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_7_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_6_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_6_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_5_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_5_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_4_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_4_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_7_1
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_7_1
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_6_1
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_6_1
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_5_1
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_5_1
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_4_1
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_4_1
```
```
In lib/zstd/compress/zstd_lazy.c (ffffffff81899382)
Location: lib/zstd/compress/zstd_compress_internal.h:741
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dedicatedDictSearch
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dedicatedDictSearch
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dedicatedDictSearch
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dedicatedDictSearch
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dedicatedDictSearch
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dedicatedDictSearch
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dedicatedDictSearch
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dedicatedDictSearch
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dedicatedDictSearch
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dedicatedDictSearch
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dictMatchState
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dictMatchState
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dictMatchState
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dictMatchState
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dictMatchState
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dictMatchState
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dictMatchState
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dictMatchState
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dictMatchState
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dictMatchState
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2_dictMatchState
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2_dictMatchState
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2
  - lib/zstd/compress/zstd_lazy.c:ZSTD_DUBT_findBestMatch
  - lib/zstd/compress/zstd_lazy.c:ZSTD_DUBT_findBestMatch
  - lib/zstd/compress/zstd_lazy.c:ZSTD_DUBT_findBestMatch
  - lib/zstd/compress/zstd_lazy.c:ZSTD_insertDUBT1
  - lib/zstd/compress/zstd_lazy.c:ZSTD_insertDUBT1
  - lib/zstd/compress/zstd_lazy.c:ZSTD_insertDUBT1
Direct callers:
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_row
```
```
In lib/zstd/compress/zstd_ldm.c (ffffffff8189d870)
Location: lib/zstd/compress/zstd_compress_internal.h:741
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_ldm.c:ZSTD_ldm_generateSequences_internal
  - lib/zstd/compress/zstd_ldm.c:ZSTD_ldm_generateSequences_internal
  - lib/zstd/compress/zstd_ldm.c:ZSTD_ldm_generateSequences_internal
```
```
In lib/zstd/compress/zstd_opt.c (ffffffff818a7942)
Location: lib/zstd/compress/zstd_compress_internal.h:741
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_6
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_6
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_6
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_6
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_5
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_5
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_5
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_5
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_4
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_4
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_4
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_4
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_3
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_3
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_3
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_3
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_3
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_extDict_6
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_extDict_6
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_extDict_6
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_extDict_6
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_extDict_5
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_extDict_5
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_extDict_5
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_extDict_5
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_extDict_4
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_extDict_4
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_extDict_4
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_extDict_4
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_extDict_3
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_extDict_3
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_extDict_3
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_extDict_3
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_extDict_3
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_noDict_6
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_noDict_6
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_noDict_5
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_noDict_5
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_noDict_4
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_noDict_4
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_noDict_3
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_noDict_3
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_noDict_3
  - lib/zstd/compress/zstd_opt.c:ZSTD_insertBt1
  - lib/zstd/compress/zstd_opt.c:ZSTD_insertBt1
  - lib/zstd/compress/zstd_opt.c:ZSTD_insertBt1
```
**Symbols:**

```
ffffffff81869390-ffffffff81869486: ZSTD_count (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
size_t ZSTD_count(const BYTE *pIn, const BYTE *pMatch, const const BYTE * pInLimit);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff81897508)
Location: lib/zstd/compress/zstd_compress_internal.h:741
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_isRLE
```
```
In lib/zstd/compress/zstd_double_fast.c (ffffffff818ad31b)
Location: lib/zstd/compress/zstd_compress_internal.h:741
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_7
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_7
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_7
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_6
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_6
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_6
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_5
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_5
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_5
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_4
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_4
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_4
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_7
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_7
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_7
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_7
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_7
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_6
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_6
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_6
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_6
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_6
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_5
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_5
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_5
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_5
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_5
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_4
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_4
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_4
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_4
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_4
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_count_2segments
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_count_2segments
```
```
In lib/zstd/compress/zstd_fast.c (ffffffff818b4c5d)
Location: lib/zstd/compress/zstd_compress_internal.h:741
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_7_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_7_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_7_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_6_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_6_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_6_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_5_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_5_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_5_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_4_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_4_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_4_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_7_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_7_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_6_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_6_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_5_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_5_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_4_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_4_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_7_1
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_7_1
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_6_1
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_6_1
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_5_1
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_5_1
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_4_1
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_4_1
```
```
In lib/zstd/compress/zstd_lazy.c (ffffffff818eaf42)
Location: lib/zstd/compress/zstd_compress_internal.h:741
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dedicatedDictSearch
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dedicatedDictSearch
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dedicatedDictSearch
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dedicatedDictSearch
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dedicatedDictSearch
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dedicatedDictSearch
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dedicatedDictSearch
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dedicatedDictSearch
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dedicatedDictSearch
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dedicatedDictSearch
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dictMatchState
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dictMatchState
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dictMatchState
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dictMatchState
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dictMatchState
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dictMatchState
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dictMatchState
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dictMatchState
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dictMatchState
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dictMatchState
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2_dictMatchState
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2_dictMatchState
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2
  - lib/zstd/compress/zstd_lazy.c:ZSTD_DUBT_findBestMatch
  - lib/zstd/compress/zstd_lazy.c:ZSTD_DUBT_findBestMatch
  - lib/zstd/compress/zstd_lazy.c:ZSTD_DUBT_findBestMatch
  - lib/zstd/compress/zstd_lazy.c:ZSTD_insertDUBT1
  - lib/zstd/compress/zstd_lazy.c:ZSTD_insertDUBT1
  - lib/zstd/compress/zstd_lazy.c:ZSTD_insertDUBT1
Direct callers:
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_row
```
```
In lib/zstd/compress/zstd_ldm.c (ffffffff818ef430)
Location: lib/zstd/compress/zstd_compress_internal.h:741
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_ldm.c:ZSTD_ldm_generateSequences_internal
  - lib/zstd/compress/zstd_ldm.c:ZSTD_ldm_generateSequences_internal
  - lib/zstd/compress/zstd_ldm.c:ZSTD_ldm_generateSequences_internal
```
```
In lib/zstd/compress/zstd_opt.c (ffffffff818f9502)
Location: lib/zstd/compress/zstd_compress_internal.h:741
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_6
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_6
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_6
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_6
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_5
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_5
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_5
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_5
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_4
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_4
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_4
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_4
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_3
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_3
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_3
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_3
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_3
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_extDict_6
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_extDict_6
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_extDict_6
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_extDict_6
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_extDict_5
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_extDict_5
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_extDict_5
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_extDict_5
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_extDict_4
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_extDict_4
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_extDict_4
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_extDict_4
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_extDict_3
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_extDict_3
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_extDict_3
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_extDict_3
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_extDict_3
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_noDict_6
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_noDict_6
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_noDict_5
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_noDict_5
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_noDict_4
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_noDict_4
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_noDict_3
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_noDict_3
  - lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_noDict_3
  - lib/zstd/compress/zstd_opt.c:ZSTD_insertBt1
  - lib/zstd/compress/zstd_opt.c:ZSTD_insertBt1
  - lib/zstd/compress/zstd_opt.c:ZSTD_insertBt1
```
**Symbols:**

```
ffffffff818baf50-ffffffff818bb046: ZSTD_count (STB_LOCAL)
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
