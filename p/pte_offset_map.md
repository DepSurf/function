# Function: <code>pte_offset_map</code>

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
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tboot.c (ffffffff810697e1)
Location: include/linux/mm.h:2850
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
```
```
In kernel/events/core.c (ffffffff8136d0a3)
Location: include/linux/mm.h:2850
Inline: True
Inline callers:
  - kernel/events/core.c:perf_get_pgtable_size
```
```
In mm/gup.c (ffffffff813e3f75)
Location: include/linux/mm.h:2850
Inline: True
Inline callers:
  - mm/gup.c:gup_pte_range
  - mm/gup.c:get_gate_page
```
```
In mm/pagewalk.c (ffffffff8140805f)
Location: include/linux/mm.h:2850
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pte_range
```
```
In mm/swap_state.c (ffffffff8142c874)
Location: include/linux/mm.h:2850
Inline: True
Inline callers:
  - mm/swap_state.c:swap_vma_readahead
```
```
In mm/swapfile.c (ffffffff814322ed)
Location: include/linux/mm.h:2850
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/huge_memory.c (ffffffff81472fbd)
Location: include/linux/mm.h:2850
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_zero_page_pmd
```
```
In mm/memory-failure.c (ffffffff81495253)
Location: include/linux/mm.h:2850
Inline: True
```
```
In mm/hmm.c (ffffffff814a4f92)
Location: include/linux/mm.h:2850
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/userfaultfd.c (ffffffff81524dea)
Location: include/linux/mm.h:2850
Inline: True
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
In arch/x86/kernel/tboot.c (ffffffff81070d21)
Location: include/linux/mm.h:2946
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
```
```
In kernel/events/core.c (ffffffff813962e3)
Location: include/linux/mm.h:2946
Inline: True
Inline callers:
  - kernel/events/core.c:perf_get_pgtable_size
```
```
In mm/gup.c (ffffffff8140e7d5)
Location: include/linux/mm.h:2946
Inline: True
Inline callers:
  - mm/gup.c:gup_pte_range
  - mm/gup.c:get_gate_page
```
```
In mm/memory.c (ffffffff8141f7c3)
Location: include/linux/mm.h:2946
Inline: True
Inline callers:
  - mm/memory.c:alloc_anon_folio
```
```
In mm/pagewalk.c (ffffffff8143476b)
Location: include/linux/mm.h:2946
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pte_range
```
```
In mm/swap_state.c (ffffffff814660d6)
Location: include/linux/mm.h:2946
Inline: True
Inline callers:
  - mm/swap_state.c:swap_vma_readahead
```
```
In mm/swapfile.c (ffffffff8146b6e6)
Location: include/linux/mm.h:2946
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/huge_memory.c (ffffffff814a1723)
Location: include/linux/mm.h:2946
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_zero_page_pmd
```
```
In mm/memory-failure.c (ffffffff814c4bbc)
Location: include/linux/mm.h:2946
Inline: True
```
```
In mm/hmm.c (ffffffff814d6052)
Location: include/linux/mm.h:2946
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/userfaultfd.c (ffffffff81558a7b)
Location: include/linux/mm.h:2946
Inline: True
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
