# Function: <code>ZSTD_safecopyLiterals</code>

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
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void ZSTD_safecopyLiterals(BYTE *op, const BYTE *ip, const const BYTE * iend, const BYTE *ilimit_w);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff817124a0)
Location: lib/zstd/compress/zstd_compress_internal.h:488
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_copySequencesToSeqStoreNoBlockDelim
  - lib/zstd/compress/zstd_compress.c:ZSTD_copySequencesToSeqStoreExplicitBlockDelim
```
```
In lib/zstd/compress/zstd_double_fast.c (ffffffff81720cc0)
Location: lib/zstd/compress/zstd_compress_internal.h:488
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
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
```
```
In lib/zstd/compress/zstd_fast.c (ffffffff81729470)
Location: lib/zstd/compress/zstd_compress_internal.h:488
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_extDict_generic
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_extDict_generic
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_extDict_generic
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_extDict_generic
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_extDict_generic
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState
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
In lib/zstd/compress/zstd_lazy.c (ffffffff8172f980)
Location: lib/zstd/compress/zstd_compress_internal.h:488
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dedicatedDictSearch
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dedicatedDictSearch
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dedicatedDictSearch
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dedicatedDictSearch
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dedicatedDictSearch
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dedicatedDictSearch
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dictMatchState
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dictMatchState
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
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2
```
```
In lib/zstd/compress/zstd_ldm.c (ffffffff817441fe)
Location: lib/zstd/compress/zstd_compress_internal.h:488
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_ldm.c:ZSTD_ldm_blockCompress
```
```
In lib/zstd/compress/zstd_opt.c (ffffffff817474a3)
Location: lib/zstd/compress/zstd_compress_internal.h:488
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_opt.c:ZSTD_compressBlock_opt_generic
```
**Symbols:**

```
ffffffff817124a0-ffffffff81712545: ZSTD_safecopyLiterals (STB_LOCAL)
ffffffff81720cc0-ffffffff81720d65: ZSTD_safecopyLiterals (STB_LOCAL)
ffffffff81729470-ffffffff81729515: ZSTD_safecopyLiterals (STB_LOCAL)
ffffffff8172f980-ffffffff8172fa25: ZSTD_safecopyLiterals (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void ZSTD_safecopyLiterals(BYTE *op, const BYTE *ip, const const BYTE * iend, const BYTE *ilimit_w);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff81803fd0)
Location: lib/zstd/compress/zstd_compress_internal.h:557
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_copySequencesToSeqStoreNoBlockDelim
  - lib/zstd/compress/zstd_compress.c:ZSTD_copySequencesToSeqStoreExplicitBlockDelim
```
```
In lib/zstd/compress/zstd_double_fast.c (ffffffff81815f10)
Location: lib/zstd/compress/zstd_compress_internal.h:557
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
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
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_6
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_6
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_6
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_5
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_5
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_5
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_4
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_4
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_4
```
```
In lib/zstd/compress/zstd_fast.c (ffffffff8181f190)
Location: lib/zstd/compress/zstd_compress_internal.h:557
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_7_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_7_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_7_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_7_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_6_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_6_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_6_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_6_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_5_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_5_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_5_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_5_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_4_0
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
In lib/zstd/compress/zstd_lazy.c (ffffffff81828b30)
Location: lib/zstd/compress/zstd_compress_internal.h:557
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_extDict_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_extDict_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_extDict_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_extDict_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_extDict_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_extDict_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dedicatedDictSearch_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dedicatedDictSearch_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dedicatedDictSearch_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dedicatedDictSearch_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dedicatedDictSearch_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dedicatedDictSearch_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dictMatchState_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dictMatchState_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dictMatchState_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dictMatchState_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dictMatchState_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dictMatchState_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dedicatedDictSearch
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dedicatedDictSearch
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dedicatedDictSearch
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dedicatedDictSearch
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dedicatedDictSearch
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dedicatedDictSearch
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dictMatchState
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dictMatchState
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
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2
```
```
In lib/zstd/compress/zstd_ldm.c (ffffffff8185db91)
Location: lib/zstd/compress/zstd_compress_internal.h:557
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_ldm.c:ZSTD_ldm_blockCompress
```
```
In lib/zstd/compress/zstd_opt.c (ffffffff8185de90)
Location: lib/zstd/compress/zstd_compress_internal.h:557
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_opt.c:ZSTD_compressBlock_opt2
  - lib/zstd/compress/zstd_opt.c:ZSTD_compressBlock_opt0
```
**Symbols:**

```
ffffffff81803fd0-ffffffff81804072: ZSTD_safecopyLiterals (STB_LOCAL)
ffffffff81815f10-ffffffff81815fb2: ZSTD_safecopyLiterals (STB_LOCAL)
ffffffff8181f190-ffffffff8181f232: ZSTD_safecopyLiterals (STB_LOCAL)
ffffffff81828b30-ffffffff81828bd2: ZSTD_safecopyLiterals (STB_LOCAL)
ffffffff8185de90-ffffffff8185df32: ZSTD_safecopyLiterals (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void ZSTD_safecopyLiterals(BYTE *op, const BYTE *ip, const const BYTE * iend, const BYTE *ilimit_w);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff818449c0)
Location: lib/zstd/compress/zstd_compress_internal.h:557
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_copySequencesToSeqStoreNoBlockDelim
  - lib/zstd/compress/zstd_compress.c:ZSTD_copySequencesToSeqStoreExplicitBlockDelim
```
```
In lib/zstd/compress/zstd_double_fast.c (ffffffff81856630)
Location: lib/zstd/compress/zstd_compress_internal.h:557
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
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
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_6
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_6
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_6
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_5
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_5
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_5
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_4
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_4
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_4
```
```
In lib/zstd/compress/zstd_fast.c (ffffffff8185f9d0)
Location: lib/zstd/compress/zstd_compress_internal.h:557
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_7_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_7_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_7_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_7_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_6_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_6_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_6_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_6_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_5_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_5_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_5_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_5_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_4_0
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
In lib/zstd/compress/zstd_lazy.c (ffffffff818692d0)
Location: lib/zstd/compress/zstd_compress_internal.h:557
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_extDict_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_extDict_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_extDict_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_extDict_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_extDict_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_extDict_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dedicatedDictSearch_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dedicatedDictSearch_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dedicatedDictSearch_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dedicatedDictSearch_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dedicatedDictSearch_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dedicatedDictSearch_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dictMatchState_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dictMatchState_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dictMatchState_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dictMatchState_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dictMatchState_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dictMatchState_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dedicatedDictSearch
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dedicatedDictSearch
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dedicatedDictSearch
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dedicatedDictSearch
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dedicatedDictSearch
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dedicatedDictSearch
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dictMatchState
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dictMatchState
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
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2
```
```
In lib/zstd/compress/zstd_ldm.c (ffffffff8189e741)
Location: lib/zstd/compress/zstd_compress_internal.h:557
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_ldm.c:ZSTD_ldm_blockCompress
```
```
In lib/zstd/compress/zstd_opt.c (ffffffff8189ea40)
Location: lib/zstd/compress/zstd_compress_internal.h:557
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_opt.c:ZSTD_compressBlock_opt2
  - lib/zstd/compress/zstd_opt.c:ZSTD_compressBlock_opt0
```
**Symbols:**

```
ffffffff818449c0-ffffffff81844a62: ZSTD_safecopyLiterals (STB_LOCAL)
ffffffff81856630-ffffffff818566d2: ZSTD_safecopyLiterals (STB_LOCAL)
ffffffff8185f9d0-ffffffff8185fa72: ZSTD_safecopyLiterals (STB_LOCAL)
ffffffff818692d0-ffffffff81869372: ZSTD_safecopyLiterals (STB_LOCAL)
ffffffff8189ea40-ffffffff8189eae2: ZSTD_safecopyLiterals (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void ZSTD_safecopyLiterals(BYTE *op, const BYTE *ip, const const BYTE * iend, const BYTE *ilimit_w);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff81896580)
Location: lib/zstd/compress/zstd_compress_internal.h:557
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_copySequencesToSeqStoreNoBlockDelim
  - lib/zstd/compress/zstd_compress.c:ZSTD_copySequencesToSeqStoreExplicitBlockDelim
```
```
In lib/zstd/compress/zstd_double_fast.c (ffffffff818a81f0)
Location: lib/zstd/compress/zstd_compress_internal.h:557
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
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
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_6
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_6
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_6
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_5
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_5
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_5
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_4
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_4
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_4
```
```
In lib/zstd/compress/zstd_fast.c (ffffffff818b1590)
Location: lib/zstd/compress/zstd_compress_internal.h:557
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_7_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_7_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_7_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_7_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_6_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_6_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_6_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_6_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_5_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_5_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_5_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_5_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_4_0
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
In lib/zstd/compress/zstd_lazy.c (ffffffff818bae90)
Location: lib/zstd/compress/zstd_compress_internal.h:557
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_extDict_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_extDict_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_extDict_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_extDict_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_extDict_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_extDict_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dedicatedDictSearch_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dedicatedDictSearch_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dedicatedDictSearch_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dedicatedDictSearch_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dedicatedDictSearch_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dedicatedDictSearch_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dictMatchState_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dictMatchState_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dictMatchState_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dictMatchState_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dictMatchState_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dictMatchState_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dedicatedDictSearch
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dedicatedDictSearch
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dedicatedDictSearch
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dedicatedDictSearch
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dedicatedDictSearch
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dedicatedDictSearch
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dictMatchState
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dictMatchState
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
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2
```
```
In lib/zstd/compress/zstd_ldm.c (ffffffff818f0301)
Location: lib/zstd/compress/zstd_compress_internal.h:557
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_ldm.c:ZSTD_ldm_blockCompress
```
```
In lib/zstd/compress/zstd_opt.c (ffffffff818f0600)
Location: lib/zstd/compress/zstd_compress_internal.h:557
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_opt.c:ZSTD_compressBlock_opt2
  - lib/zstd/compress/zstd_opt.c:ZSTD_compressBlock_opt0
```
**Symbols:**

```
ffffffff81896580-ffffffff81896622: ZSTD_safecopyLiterals (STB_LOCAL)
ffffffff818a81f0-ffffffff818a8292: ZSTD_safecopyLiterals (STB_LOCAL)
ffffffff818b1590-ffffffff818b1632: ZSTD_safecopyLiterals (STB_LOCAL)
ffffffff818bae90-ffffffff818baf32: ZSTD_safecopyLiterals (STB_LOCAL)
ffffffff818f0600-ffffffff818f06a2: ZSTD_safecopyLiterals (STB_LOCAL)
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
