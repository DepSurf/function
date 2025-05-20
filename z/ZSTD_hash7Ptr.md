# Function: <code>ZSTD_hash7Ptr</code>

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
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/zstd/compress.c (ffffffff815b1fd5)
Location: lib/zstd/compress.c:970
Inline: True
Inline callers:
  - lib/zstd/compress.c:ZSTD_updateTree
  - lib/zstd/compress.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress.c:ZSTD_compressBlock_fast_extDict_generic
  - lib/zstd/compress.c:ZSTD_compressBlock_fast
  - lib/zstd/compress.c:ZSTD_compressBlock_fast
  - lib/zstd/compress.c:ZSTD_compressBlock_fast
  - lib/zstd/compress.c:ZSTD_compressBlock_fast
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/zstd/compress.c (ffffffff815cc9f2)
Location: lib/zstd/compress.c:970
Inline: True
Inline callers:
  - lib/zstd/compress.c:ZSTD_updateTree
  - lib/zstd/compress.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress.c:ZSTD_compressBlock_doubleFast
  - lib/zstd/compress.c:ZSTD_compressBlock_fast_extDict_generic
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
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_double_fast.c (ffffffff81721e7d)
Location: lib/zstd/compress/zstd_compress_internal.h:677
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
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_fillDoubleHashTable
```
```
In lib/zstd/compress/zstd_fast.c (ffffffff8172ae2c)
Location: lib/zstd/compress/zstd_compress_internal.h:677
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
  - lib/zstd/compress/zstd_fast.c:ZSTD_fillHashTable
  - lib/zstd/compress/zstd_fast.c:ZSTD_fillHashTable
```
```
In lib/zstd/compress/zstd_lazy.c (ffffffff817330a6)
Location: lib/zstd/compress/zstd_compress_internal.h:677
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_lazy.c:ZSTD_dedicatedDictSearch_lazy_loadDictionary
  - lib/zstd/compress/zstd_lazy.c:ZSTD_dedicatedDictSearch_lazy_loadDictionary
  - lib/zstd/compress/zstd_lazy.c:ZSTD_insertAndFindFirstIndex
  - lib/zstd/compress/zstd_lazy.c:ZSTD_insertAndFindFirstIndex
```
```
In lib/zstd/compress/zstd_opt.c (ffffffff81745676)
Location: lib/zstd/compress/zstd_compress_internal.h:677
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_opt.c:ZSTD_insertBt1
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
In lib/zstd/compress/zstd_double_fast.c (ffffffff8181eece)
Location: lib/zstd/compress/zstd_compress_internal.h:803
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_7
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_7
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_7
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_7
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_7
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_7
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_7
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_7
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_7
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_fillDoubleHashTable
```
```
In lib/zstd/compress/zstd_fast.c (ffffffff8182273a)
Location: lib/zstd/compress/zstd_compress_internal.h:803
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_7_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_7_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_7_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_7_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_7_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_7_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_7_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_7_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_7_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_7_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_7_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_7_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_7_1
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_7_1
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_7_1
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_7_1
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_7_1
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_7_1
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_7_1
  - lib/zstd/compress/zstd_fast.c:ZSTD_fillHashTable
  - lib/zstd/compress/zstd_fast.c:ZSTD_fillHashTable
```
```
In lib/zstd/compress/zstd_lazy.c (ffffffff8184984b)
Location: lib/zstd/compress/zstd_compress_internal.h:803
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_lazy.c:ZSTD_insertAndFindFirstIndex
  - lib/zstd/compress/zstd_lazy.c:ZSTD_insertAndFindFirstIndex
  - lib/zstd/compress/zstd_lazy.c:ZSTD_dedicatedDictSearch_lazy_loadDictionary
  - lib/zstd/compress/zstd_lazy.c:ZSTD_dedicatedDictSearch_lazy_loadDictionary
```
```
In lib/zstd/compress/zstd_opt.c (ffffffff81860ac2)
Location: lib/zstd/compress/zstd_compress_internal.h:803
Inline: True
Inline callers:
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
In lib/zstd/compress/zstd_double_fast.c (ffffffff8185f6f8)
Location: lib/zstd/compress/zstd_compress_internal.h:803
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_7
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_7
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_7
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_7
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_7
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_7
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_7
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_7
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_7
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_fillDoubleHashTable
```
```
In lib/zstd/compress/zstd_fast.c (ffffffff81862ffb)
Location: lib/zstd/compress/zstd_compress_internal.h:803
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_7_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_7_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_7_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_7_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_7_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_7_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_7_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_7_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_7_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_7_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_7_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_7_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_7_1
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_7_1
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_7_1
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_7_1
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_7_1
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_7_1
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_7_1
  - lib/zstd/compress/zstd_fast.c:ZSTD_fillHashTable
  - lib/zstd/compress/zstd_fast.c:ZSTD_fillHashTable
```
```
In lib/zstd/compress/zstd_lazy.c (ffffffff8188a534)
Location: lib/zstd/compress/zstd_compress_internal.h:803
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_lazy.c:ZSTD_insertAndFindFirstIndex
  - lib/zstd/compress/zstd_lazy.c:ZSTD_insertAndFindFirstIndex
  - lib/zstd/compress/zstd_lazy.c:ZSTD_dedicatedDictSearch_lazy_loadDictionary
  - lib/zstd/compress/zstd_lazy.c:ZSTD_dedicatedDictSearch_lazy_loadDictionary
```
```
In lib/zstd/compress/zstd_opt.c (ffffffff818a15a3)
Location: lib/zstd/compress/zstd_compress_internal.h:803
Inline: True
Inline callers:
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
In lib/zstd/compress/zstd_double_fast.c (ffffffff818b12b8)
Location: lib/zstd/compress/zstd_compress_internal.h:803
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_7
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_7
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_7
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_7
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_7
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_7
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_7
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_7
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_7
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_fillDoubleHashTable
```
```
In lib/zstd/compress/zstd_fast.c (ffffffff818b4bbb)
Location: lib/zstd/compress/zstd_compress_internal.h:803
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_7_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_7_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_7_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_7_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_7_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_7_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_7_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_7_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_7_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_7_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_7_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_7_0
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_7_1
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_7_1
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_7_1
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_7_1
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_7_1
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_7_1
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_7_1
  - lib/zstd/compress/zstd_fast.c:ZSTD_fillHashTable
  - lib/zstd/compress/zstd_fast.c:ZSTD_fillHashTable
```
```
In lib/zstd/compress/zstd_lazy.c (ffffffff818dc0f4)
Location: lib/zstd/compress/zstd_compress_internal.h:803
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_lazy.c:ZSTD_insertAndFindFirstIndex
  - lib/zstd/compress/zstd_lazy.c:ZSTD_insertAndFindFirstIndex
  - lib/zstd/compress/zstd_lazy.c:ZSTD_dedicatedDictSearch_lazy_loadDictionary
  - lib/zstd/compress/zstd_lazy.c:ZSTD_dedicatedDictSearch_lazy_loadDictionary
```
```
In lib/zstd/compress/zstd_opt.c (ffffffff818f3163)
Location: lib/zstd/compress/zstd_compress_internal.h:803
Inline: True
Inline callers:
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
