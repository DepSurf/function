# Function: <code>__pte_offset_map</code>

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
In <code>6.2</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
pte_t *__pte_offset_map(pmd_t *pmd, long unsigned int addr, pmd_t *pmdvalp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff81409770)
Location: mm/pgtable-generic.c:235
Inline: False
Direct callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
  - kernel/events/core.c:perf_get_pgtable_size
  - mm/gup.c:gup_pte_range
  - mm/gup.c:get_gate_page
  - mm/pagewalk.c:walk_pte_range
  - mm/pgtable-generic.c:__pte_offset_map_lock
  - mm/pgtable-generic.c:pte_offset_map_nolock
  - mm/swap_state.c:swap_vma_readahead
  - mm/swapfile.c:unuse_pte_range
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_zero_page_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
```
**Symbols:**

```
ffffffff81409770-ffffffff81409924: __pte_offset_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
pte_t *__pte_offset_map(pmd_t *pmd, long unsigned int addr, pmd_t *pmdvalp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff81435fa0)
Location: mm/pgtable-generic.c:280
Inline: False
Direct callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
  - kernel/events/core.c:perf_get_pgtable_size
  - mm/gup.c:gup_pte_range
  - mm/gup.c:get_gate_page
  - mm/memory.c:alloc_anon_folio
  - mm/pagewalk.c:walk_pte_range
  - mm/pgtable-generic.c:__pte_offset_map_lock
  - mm/pgtable-generic.c:pte_offset_map_nolock
  - mm/swap_state.c:swap_vma_readahead
  - mm/swapfile.c:unuse_pte_range
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_zero_page_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
```
**Symbols:**

```
ffffffff81435fa0-ffffffff81436144: __pte_offset_map (STB_GLOBAL)
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
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
