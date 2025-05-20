# Function: <code>ZSTD_searchMax</code>

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
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_lazy.c (ffffffff8185b8c6)
Location: lib/zstd/compress/zstd_lazy.c:1448
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_extDict_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_extDict_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_extDict_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_extDict_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_extDict_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_extDict_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dedicatedDictSearch_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dedicatedDictSearch_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dedicatedDictSearch_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dedicatedDictSearch_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dedicatedDictSearch_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dedicatedDictSearch_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dictMatchState_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dictMatchState_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dictMatchState_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dictMatchState_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dictMatchState_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dictMatchState_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dedicatedDictSearch
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dedicatedDictSearch
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dedicatedDictSearch
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dedicatedDictSearch
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dedicatedDictSearch
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dedicatedDictSearch
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dictMatchState
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
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_lazy.c (ffffffff8189c493)
Location: lib/zstd/compress/zstd_lazy.c:1448
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_extDict_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_extDict_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_extDict_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_extDict_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_extDict_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_extDict_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dedicatedDictSearch_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dedicatedDictSearch_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dedicatedDictSearch_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dedicatedDictSearch_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dedicatedDictSearch_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dedicatedDictSearch_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dictMatchState_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dictMatchState_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dictMatchState_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dictMatchState_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dictMatchState_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dictMatchState_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dedicatedDictSearch
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dedicatedDictSearch
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dedicatedDictSearch
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dedicatedDictSearch
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dedicatedDictSearch
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dedicatedDictSearch
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dictMatchState
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
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_lazy.c (ffffffff818ee053)
Location: lib/zstd/compress/zstd_lazy.c:1448
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_extDict_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_extDict_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_extDict_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_extDict_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_extDict_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_extDict_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_extDict
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dedicatedDictSearch_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dedicatedDictSearch_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dedicatedDictSearch_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dedicatedDictSearch_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dedicatedDictSearch_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dedicatedDictSearch_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dictMatchState_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dictMatchState_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dictMatchState_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dictMatchState_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dictMatchState_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dictMatchState_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_row
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dedicatedDictSearch
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dedicatedDictSearch
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dedicatedDictSearch
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dedicatedDictSearch
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dedicatedDictSearch
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dedicatedDictSearch
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dictMatchState
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
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2
  - lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2
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
