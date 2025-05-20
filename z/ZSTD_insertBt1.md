# Function: <code>ZSTD_insertBt1</code>

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
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/zstd/compress.c (ffffffff815b1d0c)
Location: lib/zstd/compress.c:1561
Inline: True
Inline callers:
  - lib/zstd/compress.c:ZSTD_updateTree
Direct callers:
  - lib/zstd/compress.c:ZSTD_BtGetAllMatches_selectMLS_extDict
  - lib/zstd/compress.c:ZSTD_BtGetAllMatches_selectMLS_extDict
  - lib/zstd/compress.c:ZSTD_BtGetAllMatches_selectMLS_extDict
  - lib/zstd/compress.c:ZSTD_BtGetAllMatches_selectMLS_extDict
```
**Symbols:**

```
ffffffff815b9790-ffffffff815b9b84: ZSTD_insertBt1.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/zstd/compress.c (ffffffff815cc711)
Location: lib/zstd/compress.c:1561
Inline: True
Inline callers:
  - lib/zstd/compress.c:ZSTD_updateTree
Direct callers:
  - lib/zstd/compress.c:ZSTD_BtGetAllMatches_selectMLS_extDict
  - lib/zstd/compress.c:ZSTD_BtGetAllMatches_selectMLS_extDict
  - lib/zstd/compress.c:ZSTD_BtGetAllMatches_selectMLS_extDict
  - lib/zstd/compress.c:ZSTD_BtGetAllMatches_selectMLS_extDict
```
**Symbols:**

```
ffffffff815d6c70-ffffffff815d70dc: ZSTD_insertBt1.constprop.0 (STB_LOCAL)
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
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
U32 ZSTD_insertBt1(ZSTD_matchState_t *ms, const const BYTE * ip, const const BYTE * iend, const U32 mls, const int extDict);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/zstd/compress/zstd_opt.c (0)
Location: lib/zstd/compress/zstd_opt.c:381
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_opt.c:ZSTD_BtGetAllMatches
  - lib/zstd/compress/zstd_opt.c:ZSTD_updateTree
```
**Symbols:**

```
ffffffff81744f50-ffffffff81745731: ZSTD_insertBt1 (STB_LOCAL)
ffffffff81ea3213-ffffffff81ea32ef: ZSTD_insertBt1.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
U32 ZSTD_insertBt1(const ZSTD_matchState_t *ms, const const BYTE * ip, const const BYTE * iend, const U32 target, const U32 mls, const int extDict);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/zstd/compress/zstd_opt.c (0)
Location: lib/zstd/compress/zstd_opt.c:411
Inline: False
Direct callers:
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
  - lib/zstd/compress/zstd_opt.c:ZSTD_updateTree
```
**Symbols:**

```
ffffffff81860360-ffffffff81860ba9: ZSTD_insertBt1 (STB_LOCAL)
ffffffff8208a6ce-ffffffff8208a808: ZSTD_insertBt1.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
U32 ZSTD_insertBt1(const ZSTD_matchState_t *ms, const const BYTE * ip, const const BYTE * iend, const U32 target, const U32 mls, const int extDict);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/zstd/compress/zstd_opt.c (0)
Location: lib/zstd/compress/zstd_opt.c:411
Inline: False
Direct callers:
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
  - lib/zstd/compress/zstd_opt.c:ZSTD_updateTree
```
**Symbols:**

```
ffffffff818a0e60-ffffffff818a1686: ZSTD_insertBt1 (STB_LOCAL)
ffffffff8210ab25-ffffffff8210ac97: ZSTD_insertBt1.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
U32 ZSTD_insertBt1(const ZSTD_matchState_t *ms, const const BYTE * ip, const const BYTE * iend, const U32 target, const U32 mls, const int extDict);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/zstd/compress/zstd_opt.c (0)
Location: lib/zstd/compress/zstd_opt.c:411
Inline: False
Direct callers:
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
  - lib/zstd/compress/zstd_opt.c:ZSTD_updateTree
```
**Symbols:**

```
ffffffff818f2a20-ffffffff818f3246: ZSTD_insertBt1 (STB_LOCAL)
ffffffff821e8c92-ffffffff821e8e04: ZSTD_insertBt1.cold (STB_LOCAL)
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
<code>const U32 target</code>
</li>
<li>
<b>Param reordered. </b>
<code>ms, ip, iend, mls, extDict</code> ➡️ <code>ms, ip, iend, target, mls, extDict</code>
</li>
<li>
<b>Param type changed. </b>
<code>ZSTD_matchState_t *ms</code> ➡️ <code>const ZSTD_matchState_t *ms</code>
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
