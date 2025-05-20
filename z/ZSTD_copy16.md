# Function: <code>ZSTD_copy16</code>

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
In lib/zstd/compress/zstd_compress.c (ffffffff817126b8)
Location: lib/zstd/common/zstd_internal.h:241
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_copySequencesToSeqStoreNoBlockDelim
  - lib/zstd/compress/zstd_compress.c:ZSTD_copySequencesToSeqStoreNoBlockDelim
  - lib/zstd/compress/zstd_compress.c:ZSTD_copySequencesToSeqStoreNoBlockDelim
  - lib/zstd/compress/zstd_compress.c:ZSTD_copySequencesToSeqStoreNoBlockDelim
  - lib/zstd/compress/zstd_compress.c:ZSTD_copySequencesToSeqStoreExplicitBlockDelim
  - lib/zstd/compress/zstd_compress.c:ZSTD_copySequencesToSeqStoreExplicitBlockDelim
  - lib/zstd/compress/zstd_compress.c:ZSTD_copySequencesToSeqStoreExplicitBlockDelim
  - lib/zstd/compress/zstd_compress.c:ZSTD_copySequencesToSeqStoreExplicitBlockDelim
  - lib/zstd/compress/zstd_compress.c:ZSTD_safecopyLiterals
  - lib/zstd/compress/zstd_compress.c:ZSTD_safecopyLiterals
  - lib/zstd/compress/zstd_compress.c:ZSTD_safecopyLiterals
```
```
In lib/zstd/compress/zstd_double_fast.c (ffffffff81721574)
Location: lib/zstd/common/zstd_internal.h:241
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
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
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_safecopyLiterals
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_safecopyLiterals
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_safecopyLiterals
```
```
In lib/zstd/compress/zstd_fast.c (ffffffff81729c72)
Location: lib/zstd/common/zstd_internal.h:241
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_extDict_generic
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_extDict_generic
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_extDict_generic
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_extDict_generic
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_extDict_generic
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_extDict_generic
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_extDict_generic
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_extDict_generic
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
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast
  - lib/zstd/compress/zstd_fast.c:ZSTD_safecopyLiterals
  - lib/zstd/compress/zstd_fast.c:ZSTD_safecopyLiterals
  - lib/zstd/compress/zstd_fast.c:ZSTD_safecopyLiterals
```
```
In lib/zstd/compress/zstd_lazy.c (ffffffff81742690)
Location: lib/zstd/common/zstd_internal.h:241
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2_extDict
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
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dedicatedDictSearch
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dedicatedDictSearch
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dedicatedDictSearch
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dedicatedDictSearch
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dedicatedDictSearch
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dedicatedDictSearch
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dedicatedDictSearch
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dedicatedDictSearch
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dedicatedDictSearch
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dedicatedDictSearch
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dedicatedDictSearch
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dedicatedDictSearch
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dedicatedDictSearch
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dedicatedDictSearch
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dedicatedDictSearch
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dictMatchState
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dictMatchState
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dictMatchState
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dictMatchState
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dictMatchState
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dictMatchState
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dictMatchState
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dictMatchState
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dictMatchState
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dictMatchState
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dictMatchState
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dictMatchState
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dictMatchState
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dictMatchState
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dictMatchState
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2_dictMatchState
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2_dictMatchState
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2_dictMatchState
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2_dictMatchState
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2_dictMatchState
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy
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
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2
  - lib/zstd/compress/zstd_lazy.c:ZSTD_safecopyLiterals
  - lib/zstd/compress/zstd_lazy.c:ZSTD_safecopyLiterals
  - lib/zstd/compress/zstd_lazy.c:ZSTD_safecopyLiterals
```
```
In lib/zstd/compress/zstd_ldm.c (ffffffff8174405c)
Location: lib/zstd/common/zstd_internal.h:241
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_ldm.c:ZSTD_ldm_blockCompress
  - lib/zstd/compress/zstd_ldm.c:ZSTD_ldm_blockCompress
  - lib/zstd/compress/zstd_ldm.c:ZSTD_ldm_blockCompress
  - lib/zstd/compress/zstd_ldm.c:ZSTD_ldm_blockCompress
  - lib/zstd/compress/zstd_ldm.c:ZSTD_ldm_blockCompress
  - lib/zstd/compress/zstd_ldm.c:ZSTD_ldm_blockCompress
  - lib/zstd/compress/zstd_ldm.c:ZSTD_ldm_blockCompress
```
```
In lib/zstd/compress/zstd_opt.c (ffffffff817473a7)
Location: lib/zstd/common/zstd_internal.h:241
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_opt.c:ZSTD_compressBlock_opt_generic
  - lib/zstd/compress/zstd_opt.c:ZSTD_compressBlock_opt_generic
  - lib/zstd/compress/zstd_opt.c:ZSTD_compressBlock_opt_generic
  - lib/zstd/compress/zstd_opt.c:ZSTD_compressBlock_opt_generic
  - lib/zstd/compress/zstd_opt.c:ZSTD_compressBlock_opt_generic
  - lib/zstd/compress/zstd_opt.c:ZSTD_compressBlock_opt_generic
  - lib/zstd/compress/zstd_opt.c:ZSTD_compressBlock_opt_generic
```
```
In lib/zstd/decompress/zstd_decompress_block.c (ffffffff81755ab0)
Location: lib/zstd/common/zstd_internal.h:241
Inline: True
Inline callers:
  - lib/zstd/decompress/zstd_decompress_block.c:ZSTD_safecopy
  - lib/zstd/decompress/zstd_decompress_block.c:ZSTD_safecopy
  - lib/zstd/decompress/zstd_decompress_block.c:ZSTD_safecopy
  - lib/zstd/decompress/zstd_decompress_block.c:ZSTD_safecopy
  - lib/zstd/decompress/zstd_decompress_block.c:ZSTD_safecopy
  - lib/zstd/decompress/zstd_decompress_block.c:ZSTD_safecopy
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
In lib/zstd/compress/zstd_compress.c (ffffffff818051ba)
Location: lib/zstd/common/zstd_internal.h:175
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_copySequencesToSeqStoreNoBlockDelim
  - lib/zstd/compress/zstd_compress.c:ZSTD_copySequencesToSeqStoreNoBlockDelim
  - lib/zstd/compress/zstd_compress.c:ZSTD_copySequencesToSeqStoreNoBlockDelim
  - lib/zstd/compress/zstd_compress.c:ZSTD_copySequencesToSeqStoreNoBlockDelim
  - lib/zstd/compress/zstd_compress.c:ZSTD_copySequencesToSeqStoreExplicitBlockDelim
  - lib/zstd/compress/zstd_compress.c:ZSTD_copySequencesToSeqStoreExplicitBlockDelim
  - lib/zstd/compress/zstd_compress.c:ZSTD_copySequencesToSeqStoreExplicitBlockDelim
  - lib/zstd/compress/zstd_compress.c:ZSTD_copySequencesToSeqStoreExplicitBlockDelim
  - lib/zstd/compress/zstd_compress.c:ZSTD_safecopyLiterals
  - lib/zstd/compress/zstd_compress.c:ZSTD_safecopyLiterals
  - lib/zstd/compress/zstd_compress.c:ZSTD_safecopyLiterals
```
```
In lib/zstd/compress/zstd_double_fast.c (ffffffff8181e7f4)
Location: lib/zstd/common/zstd_internal.h:175
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_7
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_7
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_7
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_7
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_7
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_7
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_7
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_7
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_7
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_6
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_6
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_6
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_6
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_6
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_6
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_6
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_6
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_6
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_5
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_5
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_5
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_5
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_5
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_5
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_5
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_5
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_5
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_4
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_4
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_4
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_4
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_4
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_4
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_4
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_4
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_4
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_7
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_7
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_7
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_7
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
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_6
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_6
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_6
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_6
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_5
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_5
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_5
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_5
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
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_4
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_4
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_4
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_4
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_safecopyLiterals
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_safecopyLiterals
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_safecopyLiterals
```
```
In lib/zstd/compress/zstd_fast.c (ffffffff81822fcc)
Location: lib/zstd/common/zstd_internal.h:175
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_7_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_7_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_7_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_7_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_7_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_7_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_7_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_7_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_7_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_7_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_7_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_7_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_7_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_6_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_6_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_6_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_6_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_6_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_6_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_6_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_6_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_6_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_6_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_6_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_6_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_6_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_5_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_5_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_5_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_5_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_5_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_5_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_5_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_5_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_5_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_5_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_5_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_5_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_5_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_4_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_4_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_4_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_4_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_4_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_4_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_4_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_4_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_4_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_4_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_4_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_4_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_4_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_7_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_7_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_7_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_7_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_7_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_6_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_6_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_6_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_6_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_6_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_5_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_5_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_5_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_5_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_5_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_4_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_4_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_4_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_4_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_4_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_7_1
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_7_1
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_7_1
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_7_1
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_7_1
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_6_1
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_6_1
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_6_1
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_6_1
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_6_1
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_5_1
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_5_1
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_5_1
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_5_1
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_5_1
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_4_1
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_4_1
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_4_1
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_4_1
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_4_1
  - lib/zstd/compress/zstd_fast.c:ZSTD_safecopyLiterals
  - lib/zstd/compress/zstd_fast.c:ZSTD_safecopyLiterals
  - lib/zstd/compress/zstd_fast.c:ZSTD_safecopyLiterals
```
```
In lib/zstd/compress/zstd_lazy.c (ffffffff8185bf0d)
Location: lib/zstd/common/zstd_internal.h:175
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_extDict_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_extDict_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_extDict_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_extDict_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_extDict_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_extDict_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_extDict_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_extDict_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_extDict_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_extDict_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_extDict_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_extDict_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_extDict_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_extDict_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_extDict_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2_extDict
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
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dedicatedDictSearch_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dedicatedDictSearch_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dedicatedDictSearch_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dedicatedDictSearch_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dedicatedDictSearch_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dedicatedDictSearch_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dedicatedDictSearch_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dedicatedDictSearch_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dedicatedDictSearch_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dedicatedDictSearch_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dedicatedDictSearch_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dedicatedDictSearch_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dedicatedDictSearch_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dedicatedDictSearch_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dedicatedDictSearch_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dictMatchState_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dictMatchState_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dictMatchState_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dictMatchState_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dictMatchState_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dictMatchState_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dictMatchState_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dictMatchState_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dictMatchState_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dictMatchState_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dictMatchState_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dictMatchState_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dictMatchState_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dictMatchState_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dictMatchState_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dedicatedDictSearch
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dedicatedDictSearch
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dedicatedDictSearch
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dedicatedDictSearch
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dedicatedDictSearch
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dedicatedDictSearch
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dedicatedDictSearch
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dedicatedDictSearch
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dedicatedDictSearch
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dedicatedDictSearch
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dedicatedDictSearch
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dedicatedDictSearch
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dedicatedDictSearch
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dedicatedDictSearch
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dedicatedDictSearch
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dictMatchState
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dictMatchState
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dictMatchState
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dictMatchState
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dictMatchState
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dictMatchState
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dictMatchState
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dictMatchState
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dictMatchState
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dictMatchState
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dictMatchState
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dictMatchState
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dictMatchState
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dictMatchState
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dictMatchState
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2_dictMatchState
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2_dictMatchState
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2_dictMatchState
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2_dictMatchState
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2_dictMatchState
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy
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
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2
  - lib/zstd/compress/zstd_lazy.c:ZSTD_safecopyLiterals
  - lib/zstd/compress/zstd_lazy.c:ZSTD_safecopyLiterals
  - lib/zstd/compress/zstd_lazy.c:ZSTD_safecopyLiterals
```
```
In lib/zstd/compress/zstd_ldm.c (ffffffff8185d9d0)
Location: lib/zstd/common/zstd_internal.h:175
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_ldm.c:ZSTD_ldm_blockCompress
  - lib/zstd/compress/zstd_ldm.c:ZSTD_ldm_blockCompress
  - lib/zstd/compress/zstd_ldm.c:ZSTD_ldm_blockCompress
  - lib/zstd/compress/zstd_ldm.c:ZSTD_ldm_blockCompress
  - lib/zstd/compress/zstd_ldm.c:ZSTD_ldm_blockCompress
  - lib/zstd/compress/zstd_ldm.c:ZSTD_ldm_blockCompress
  - lib/zstd/compress/zstd_ldm.c:ZSTD_ldm_blockCompress
```
```
In lib/zstd/compress/zstd_opt.c (ffffffff8185f223)
Location: lib/zstd/common/zstd_internal.h:175
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_opt.c:ZSTD_compressBlock_opt2
  - lib/zstd/compress/zstd_opt.c:ZSTD_compressBlock_opt2
  - lib/zstd/compress/zstd_opt.c:ZSTD_compressBlock_opt2
  - lib/zstd/compress/zstd_opt.c:ZSTD_compressBlock_opt2
  - lib/zstd/compress/zstd_opt.c:ZSTD_compressBlock_opt0
  - lib/zstd/compress/zstd_opt.c:ZSTD_compressBlock_opt0
  - lib/zstd/compress/zstd_opt.c:ZSTD_compressBlock_opt0
  - lib/zstd/compress/zstd_opt.c:ZSTD_compressBlock_opt0
  - lib/zstd/compress/zstd_opt.c:ZSTD_safecopyLiterals
  - lib/zstd/compress/zstd_opt.c:ZSTD_safecopyLiterals
  - lib/zstd/compress/zstd_opt.c:ZSTD_safecopyLiterals
```
```
In lib/zstd/decompress/zstd_decompress_block.c (ffffffff81879861)
Location: lib/zstd/common/zstd_internal.h:175
Inline: True
Inline callers:
  - lib/zstd/decompress/zstd_decompress_block.c:ZSTD_safecopyDstBeforeSrc
  - lib/zstd/decompress/zstd_decompress_block.c:ZSTD_safecopyDstBeforeSrc
  - lib/zstd/decompress/zstd_decompress_block.c:ZSTD_safecopyDstBeforeSrc
  - lib/zstd/decompress/zstd_decompress_block.c:ZSTD_safecopy
  - lib/zstd/decompress/zstd_decompress_block.c:ZSTD_safecopy
  - lib/zstd/decompress/zstd_decompress_block.c:ZSTD_safecopy
  - lib/zstd/decompress/zstd_decompress_block.c:ZSTD_safecopy
  - lib/zstd/decompress/zstd_decompress_block.c:ZSTD_safecopy
  - lib/zstd/decompress/zstd_decompress_block.c:ZSTD_safecopy
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
In lib/zstd/compress/zstd_compress.c (ffffffff81845c0d)
Location: lib/zstd/common/zstd_internal.h:175
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_copySequencesToSeqStoreNoBlockDelim
  - lib/zstd/compress/zstd_compress.c:ZSTD_copySequencesToSeqStoreNoBlockDelim
  - lib/zstd/compress/zstd_compress.c:ZSTD_copySequencesToSeqStoreNoBlockDelim
  - lib/zstd/compress/zstd_compress.c:ZSTD_copySequencesToSeqStoreNoBlockDelim
  - lib/zstd/compress/zstd_compress.c:ZSTD_copySequencesToSeqStoreExplicitBlockDelim
  - lib/zstd/compress/zstd_compress.c:ZSTD_copySequencesToSeqStoreExplicitBlockDelim
  - lib/zstd/compress/zstd_compress.c:ZSTD_copySequencesToSeqStoreExplicitBlockDelim
  - lib/zstd/compress/zstd_compress.c:ZSTD_copySequencesToSeqStoreExplicitBlockDelim
  - lib/zstd/compress/zstd_compress.c:ZSTD_safecopyLiterals
  - lib/zstd/compress/zstd_compress.c:ZSTD_safecopyLiterals
  - lib/zstd/compress/zstd_compress.c:ZSTD_safecopyLiterals
```
```
In lib/zstd/compress/zstd_double_fast.c (ffffffff8185eead)
Location: lib/zstd/common/zstd_internal.h:175
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_7
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_7
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_7
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_7
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_7
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_7
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_7
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_7
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_7
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_6
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_6
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_6
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_6
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_6
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_6
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_6
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_6
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_6
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_5
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_5
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_5
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_5
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_5
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_5
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_5
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_5
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_5
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_4
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_4
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_4
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_4
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_4
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_4
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_4
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_4
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_4
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_7
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_7
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_7
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_7
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
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_6
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_6
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_6
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_6
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_5
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_5
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_5
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_5
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
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_4
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_4
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_4
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_4
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_safecopyLiterals
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_safecopyLiterals
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_safecopyLiterals
```
```
In lib/zstd/compress/zstd_fast.c (ffffffff81863815)
Location: lib/zstd/common/zstd_internal.h:175
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_7_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_7_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_7_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_7_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_7_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_7_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_7_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_7_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_7_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_7_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_7_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_7_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_7_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_6_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_6_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_6_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_6_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_6_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_6_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_6_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_6_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_6_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_6_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_6_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_6_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_6_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_5_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_5_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_5_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_5_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_5_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_5_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_5_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_5_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_5_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_5_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_5_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_5_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_5_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_4_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_4_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_4_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_4_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_4_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_4_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_4_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_4_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_4_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_4_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_4_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_4_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_4_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_7_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_7_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_7_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_7_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_7_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_6_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_6_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_6_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_6_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_6_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_5_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_5_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_5_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_5_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_5_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_4_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_4_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_4_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_4_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_4_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_7_1
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_7_1
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_7_1
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_7_1
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_7_1
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_6_1
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_6_1
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_6_1
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_6_1
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_6_1
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_5_1
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_5_1
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_5_1
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_5_1
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_5_1
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_4_1
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_4_1
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_4_1
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_4_1
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_4_1
  - lib/zstd/compress/zstd_fast.c:ZSTD_safecopyLiterals
  - lib/zstd/compress/zstd_fast.c:ZSTD_safecopyLiterals
  - lib/zstd/compress/zstd_fast.c:ZSTD_safecopyLiterals
```
```
In lib/zstd/compress/zstd_lazy.c (ffffffff8189cb47)
Location: lib/zstd/common/zstd_internal.h:175
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_extDict_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_extDict_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_extDict_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_extDict_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_extDict_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_extDict_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_extDict_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_extDict_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_extDict_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_extDict_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_extDict_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_extDict_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_extDict_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_extDict_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_extDict_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2_extDict
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
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dedicatedDictSearch_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dedicatedDictSearch_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dedicatedDictSearch_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dedicatedDictSearch_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dedicatedDictSearch_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dedicatedDictSearch_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dedicatedDictSearch_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dedicatedDictSearch_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dedicatedDictSearch_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dedicatedDictSearch_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dedicatedDictSearch_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dedicatedDictSearch_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dedicatedDictSearch_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dedicatedDictSearch_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dedicatedDictSearch_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dictMatchState_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dictMatchState_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dictMatchState_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dictMatchState_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dictMatchState_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dictMatchState_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dictMatchState_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dictMatchState_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dictMatchState_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dictMatchState_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dictMatchState_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dictMatchState_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dictMatchState_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dictMatchState_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dictMatchState_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dedicatedDictSearch
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dedicatedDictSearch
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dedicatedDictSearch
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dedicatedDictSearch
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dedicatedDictSearch
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dedicatedDictSearch
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dedicatedDictSearch
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dedicatedDictSearch
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dedicatedDictSearch
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dedicatedDictSearch
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dedicatedDictSearch
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dedicatedDictSearch
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dedicatedDictSearch
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dedicatedDictSearch
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dedicatedDictSearch
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dictMatchState
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dictMatchState
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dictMatchState
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dictMatchState
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dictMatchState
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dictMatchState
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dictMatchState
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dictMatchState
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dictMatchState
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dictMatchState
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dictMatchState
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dictMatchState
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dictMatchState
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dictMatchState
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dictMatchState
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2_dictMatchState
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2_dictMatchState
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2_dictMatchState
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2_dictMatchState
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2_dictMatchState
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy
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
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2
  - lib/zstd/compress/zstd_lazy.c:ZSTD_safecopyLiterals
  - lib/zstd/compress/zstd_lazy.c:ZSTD_safecopyLiterals
  - lib/zstd/compress/zstd_lazy.c:ZSTD_safecopyLiterals
```
```
In lib/zstd/compress/zstd_ldm.c (ffffffff8189e580)
Location: lib/zstd/common/zstd_internal.h:175
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_ldm.c:ZSTD_ldm_blockCompress
  - lib/zstd/compress/zstd_ldm.c:ZSTD_ldm_blockCompress
  - lib/zstd/compress/zstd_ldm.c:ZSTD_ldm_blockCompress
  - lib/zstd/compress/zstd_ldm.c:ZSTD_ldm_blockCompress
  - lib/zstd/compress/zstd_ldm.c:ZSTD_ldm_blockCompress
  - lib/zstd/compress/zstd_ldm.c:ZSTD_ldm_blockCompress
  - lib/zstd/compress/zstd_ldm.c:ZSTD_ldm_blockCompress
```
```
In lib/zstd/compress/zstd_opt.c (ffffffff8189fd3f)
Location: lib/zstd/common/zstd_internal.h:175
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_opt.c:ZSTD_compressBlock_opt2
  - lib/zstd/compress/zstd_opt.c:ZSTD_compressBlock_opt2
  - lib/zstd/compress/zstd_opt.c:ZSTD_compressBlock_opt2
  - lib/zstd/compress/zstd_opt.c:ZSTD_compressBlock_opt2
  - lib/zstd/compress/zstd_opt.c:ZSTD_compressBlock_opt0
  - lib/zstd/compress/zstd_opt.c:ZSTD_compressBlock_opt0
  - lib/zstd/compress/zstd_opt.c:ZSTD_compressBlock_opt0
  - lib/zstd/compress/zstd_opt.c:ZSTD_compressBlock_opt0
  - lib/zstd/compress/zstd_opt.c:ZSTD_safecopyLiterals
  - lib/zstd/compress/zstd_opt.c:ZSTD_safecopyLiterals
  - lib/zstd/compress/zstd_opt.c:ZSTD_safecopyLiterals
```
```
In lib/zstd/decompress/zstd_decompress_block.c (ffffffff818ba6a1)
Location: lib/zstd/common/zstd_internal.h:175
Inline: True
Inline callers:
  - lib/zstd/decompress/zstd_decompress_block.c:ZSTD_safecopyDstBeforeSrc
  - lib/zstd/decompress/zstd_decompress_block.c:ZSTD_safecopyDstBeforeSrc
  - lib/zstd/decompress/zstd_decompress_block.c:ZSTD_safecopyDstBeforeSrc
  - lib/zstd/decompress/zstd_decompress_block.c:ZSTD_safecopy
  - lib/zstd/decompress/zstd_decompress_block.c:ZSTD_safecopy
  - lib/zstd/decompress/zstd_decompress_block.c:ZSTD_safecopy
  - lib/zstd/decompress/zstd_decompress_block.c:ZSTD_safecopy
  - lib/zstd/decompress/zstd_decompress_block.c:ZSTD_safecopy
  - lib/zstd/decompress/zstd_decompress_block.c:ZSTD_safecopy
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
In lib/zstd/compress/zstd_compress.c (ffffffff818977cd)
Location: lib/zstd/common/zstd_internal.h:175
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_copySequencesToSeqStoreNoBlockDelim
  - lib/zstd/compress/zstd_compress.c:ZSTD_copySequencesToSeqStoreNoBlockDelim
  - lib/zstd/compress/zstd_compress.c:ZSTD_copySequencesToSeqStoreNoBlockDelim
  - lib/zstd/compress/zstd_compress.c:ZSTD_copySequencesToSeqStoreNoBlockDelim
  - lib/zstd/compress/zstd_compress.c:ZSTD_copySequencesToSeqStoreExplicitBlockDelim
  - lib/zstd/compress/zstd_compress.c:ZSTD_copySequencesToSeqStoreExplicitBlockDelim
  - lib/zstd/compress/zstd_compress.c:ZSTD_copySequencesToSeqStoreExplicitBlockDelim
  - lib/zstd/compress/zstd_compress.c:ZSTD_copySequencesToSeqStoreExplicitBlockDelim
  - lib/zstd/compress/zstd_compress.c:ZSTD_safecopyLiterals
  - lib/zstd/compress/zstd_compress.c:ZSTD_safecopyLiterals
  - lib/zstd/compress/zstd_compress.c:ZSTD_safecopyLiterals
```
```
In lib/zstd/compress/zstd_double_fast.c (ffffffff818b0a6d)
Location: lib/zstd/common/zstd_internal.h:175
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_7
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_7
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_7
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_7
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_7
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_7
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_7
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_7
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_7
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_6
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_6
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_6
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_6
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_6
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_6
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_6
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_6
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_6
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_5
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_5
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_5
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_5
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_5
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_5
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_5
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_5
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_5
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_4
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_4
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_4
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_4
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_4
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_4
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_4
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_4
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_4
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_7
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_7
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_7
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_7
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
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_6
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_6
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_6
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_6
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_5
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_5
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_5
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_5
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
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_4
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_4
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_4
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_4
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_safecopyLiterals
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_safecopyLiterals
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_safecopyLiterals
```
```
In lib/zstd/compress/zstd_fast.c (ffffffff818b53d5)
Location: lib/zstd/common/zstd_internal.h:175
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_7_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_7_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_7_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_7_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_7_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_7_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_7_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_7_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_7_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_7_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_7_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_7_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_7_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_6_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_6_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_6_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_6_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_6_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_6_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_6_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_6_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_6_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_6_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_6_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_6_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_6_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_5_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_5_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_5_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_5_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_5_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_5_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_5_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_5_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_5_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_5_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_5_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_5_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_5_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_4_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_4_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_4_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_4_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_4_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_4_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_4_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_4_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_4_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_4_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_4_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_4_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_4_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_7_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_7_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_7_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_7_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_7_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_6_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_6_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_6_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_6_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_6_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_5_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_5_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_5_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_5_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_5_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_4_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_4_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_4_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_4_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_4_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_7_1
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_7_1
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_7_1
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_7_1
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_7_1
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_6_1
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_6_1
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_6_1
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_6_1
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_6_1
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_5_1
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_5_1
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_5_1
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_5_1
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_5_1
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_4_1
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_4_1
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_4_1
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_4_1
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_4_1
  - lib/zstd/compress/zstd_fast.c:ZSTD_safecopyLiterals
  - lib/zstd/compress/zstd_fast.c:ZSTD_safecopyLiterals
  - lib/zstd/compress/zstd_fast.c:ZSTD_safecopyLiterals
```
```
In lib/zstd/compress/zstd_lazy.c (ffffffff818ee707)
Location: lib/zstd/common/zstd_internal.h:175
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_extDict_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_extDict_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_extDict_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_extDict_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_extDict_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_extDict_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_extDict_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_extDict_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_extDict_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_extDict_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_extDict_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_extDict_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_extDict_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_extDict_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_extDict_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2_extDict
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
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dedicatedDictSearch_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dedicatedDictSearch_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dedicatedDictSearch_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dedicatedDictSearch_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dedicatedDictSearch_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dedicatedDictSearch_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dedicatedDictSearch_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dedicatedDictSearch_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dedicatedDictSearch_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dedicatedDictSearch_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dedicatedDictSearch_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dedicatedDictSearch_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dedicatedDictSearch_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dedicatedDictSearch_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dedicatedDictSearch_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dictMatchState_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dictMatchState_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dictMatchState_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dictMatchState_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dictMatchState_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dictMatchState_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dictMatchState_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dictMatchState_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dictMatchState_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dictMatchState_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dictMatchState_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dictMatchState_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dictMatchState_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dictMatchState_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dictMatchState_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dedicatedDictSearch
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dedicatedDictSearch
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dedicatedDictSearch
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dedicatedDictSearch
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dedicatedDictSearch
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dedicatedDictSearch
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dedicatedDictSearch
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dedicatedDictSearch
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dedicatedDictSearch
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dedicatedDictSearch
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dedicatedDictSearch
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dedicatedDictSearch
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dedicatedDictSearch
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dedicatedDictSearch
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dedicatedDictSearch
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dictMatchState
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dictMatchState
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dictMatchState
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dictMatchState
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dictMatchState
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dictMatchState
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dictMatchState
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dictMatchState
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dictMatchState
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dictMatchState
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dictMatchState
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dictMatchState
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dictMatchState
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dictMatchState
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dictMatchState
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2_dictMatchState
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2_dictMatchState
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2_dictMatchState
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2_dictMatchState
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2_dictMatchState
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy
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
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2
  - lib/zstd/compress/zstd_lazy.c:ZSTD_safecopyLiterals
  - lib/zstd/compress/zstd_lazy.c:ZSTD_safecopyLiterals
  - lib/zstd/compress/zstd_lazy.c:ZSTD_safecopyLiterals
```
```
In lib/zstd/compress/zstd_ldm.c (ffffffff818f0140)
Location: lib/zstd/common/zstd_internal.h:175
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_ldm.c:ZSTD_ldm_blockCompress
  - lib/zstd/compress/zstd_ldm.c:ZSTD_ldm_blockCompress
  - lib/zstd/compress/zstd_ldm.c:ZSTD_ldm_blockCompress
  - lib/zstd/compress/zstd_ldm.c:ZSTD_ldm_blockCompress
  - lib/zstd/compress/zstd_ldm.c:ZSTD_ldm_blockCompress
  - lib/zstd/compress/zstd_ldm.c:ZSTD_ldm_blockCompress
  - lib/zstd/compress/zstd_ldm.c:ZSTD_ldm_blockCompress
```
```
In lib/zstd/compress/zstd_opt.c (ffffffff818f18ff)
Location: lib/zstd/common/zstd_internal.h:175
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_opt.c:ZSTD_compressBlock_opt2
  - lib/zstd/compress/zstd_opt.c:ZSTD_compressBlock_opt2
  - lib/zstd/compress/zstd_opt.c:ZSTD_compressBlock_opt2
  - lib/zstd/compress/zstd_opt.c:ZSTD_compressBlock_opt2
  - lib/zstd/compress/zstd_opt.c:ZSTD_compressBlock_opt0
  - lib/zstd/compress/zstd_opt.c:ZSTD_compressBlock_opt0
  - lib/zstd/compress/zstd_opt.c:ZSTD_compressBlock_opt0
  - lib/zstd/compress/zstd_opt.c:ZSTD_compressBlock_opt0
  - lib/zstd/compress/zstd_opt.c:ZSTD_safecopyLiterals
  - lib/zstd/compress/zstd_opt.c:ZSTD_safecopyLiterals
  - lib/zstd/compress/zstd_opt.c:ZSTD_safecopyLiterals
```
```
In lib/zstd/decompress/zstd_decompress_block.c (ffffffff8190c261)
Location: lib/zstd/common/zstd_internal.h:175
Inline: True
Inline callers:
  - lib/zstd/decompress/zstd_decompress_block.c:ZSTD_safecopyDstBeforeSrc
  - lib/zstd/decompress/zstd_decompress_block.c:ZSTD_safecopyDstBeforeSrc
  - lib/zstd/decompress/zstd_decompress_block.c:ZSTD_safecopyDstBeforeSrc
  - lib/zstd/decompress/zstd_decompress_block.c:ZSTD_safecopy
  - lib/zstd/decompress/zstd_decompress_block.c:ZSTD_safecopy
  - lib/zstd/decompress/zstd_decompress_block.c:ZSTD_safecopy
  - lib/zstd/decompress/zstd_decompress_block.c:ZSTD_safecopy
  - lib/zstd/decompress/zstd_decompress_block.c:ZSTD_safecopy
  - lib/zstd/decompress/zstd_decompress_block.c:ZSTD_safecopy
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
