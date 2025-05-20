# Function: <code>try_to_free_swap</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int try_to_free_swap(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff811d49f0)
Location: mm/swapfile.c:953
Inline: True
Direct callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/memory.c:handle_mm_fault
  - mm/page_io.c:swap_writepage
  - mm/swap_state.c:free_page_and_swap_cache
  - mm/swap_state.c:free_pages_and_swap_cache
  - mm/swapfile.c:scan_swap_map
  - mm/ksm.c:try_to_merge_with_ksm_page
```
**Symbols:**

```
ffffffff811d49f0-ffffffff811d4a3a: try_to_free_swap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int try_to_free_swap(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff811f28c0)
Location: mm/swapfile.c:952
Inline: True
Direct callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/memory.c:do_swap_page
  - mm/madvise.c:madvise_free_pte_range
  - mm/page_io.c:swap_writepage
  - mm/swap_state.c:free_pages_and_swap_cache
  - mm/swap_state.c:free_page_and_swap_cache
  - mm/swapfile.c:scan_swap_map
  - mm/ksm.c:try_to_merge_with_ksm_page
```
**Symbols:**

```
ffffffff811f28c0-ffffffff811f2918: try_to_free_swap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int try_to_free_swap(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81203310)
Location: mm/swapfile.c:972
Inline: True
Direct callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/memory.c:do_swap_page
  - mm/madvise.c:madvise_free_pte_range
  - mm/page_io.c:swap_writepage
  - mm/swap_state.c:free_pages_and_swap_cache
  - mm/swap_state.c:free_page_and_swap_cache
  - mm/swapfile.c:scan_swap_map
  - mm/ksm.c:try_to_merge_one_page
```
**Symbols:**

```
ffffffff81203310-ffffffff81203384: try_to_free_swap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int try_to_free_swap(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8120e760)
Location: mm/swapfile.c:1381
Inline: True
Direct callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/vmscan.c:shrink_page_list
  - mm/memory.c:do_swap_page
  - mm/madvise.c:madvise_free_pte_range
  - mm/page_io.c:swap_writepage
  - mm/swap_state.c:free_pages_and_swap_cache
  - mm/swap_state.c:free_page_and_swap_cache
  - mm/swapfile.c:scan_swap_map_slots
  - mm/ksm.c:try_to_merge_one_page
```
**Symbols:**

```
ffffffff8120e760-ffffffff8120e7e1: try_to_free_swap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int try_to_free_swap(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81229ea0)
Location: mm/swapfile.c:1590
Inline: True
Direct callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/vmscan.c:shrink_page_list
  - mm/memory.c:do_swap_page
  - mm/madvise.c:madvise_free_pte_range
  - mm/page_io.c:swap_writepage
  - mm/swap_state.c:free_pages_and_swap_cache
  - mm/swap_state.c:free_page_and_swap_cache
  - mm/swapfile.c:scan_swap_map_slots
  - mm/ksm.c:try_to_merge_one_page
```
**Symbols:**

```
ffffffff81229ea0-ffffffff81229f3e: try_to_free_swap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int try_to_free_swap(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8124b130)
Location: mm/swapfile.c:1590
Inline: True
Direct callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/vmscan.c:shrink_page_list
  - mm/memory.c:do_swap_page
  - mm/madvise.c:madvise_free_pte_range
  - mm/page_io.c:swap_writepage
  - mm/swap_state.c:free_pages_and_swap_cache
  - mm/swap_state.c:free_page_and_swap_cache
  - mm/swapfile.c:scan_swap_map_slots
  - mm/ksm.c:try_to_merge_one_page
```
**Symbols:**

```
ffffffff8124b130-ffffffff8124b1ce: try_to_free_swap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int try_to_free_swap(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8125f7a0)
Location: mm/swapfile.c:1584
Inline: True
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/vmscan.c:shrink_page_list
  - mm/memory.c:do_swap_page
  - mm/madvise.c:madvise_free_pte_range
  - mm/page_io.c:swap_writepage
  - mm/swap_state.c:free_pages_and_swap_cache
  - mm/swap_state.c:free_page_and_swap_cache
  - mm/ksm.c:try_to_merge_one_page
```
**Symbols:**

```
ffffffff8125f7a0-ffffffff8125f88c: try_to_free_swap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int try_to_free_swap(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8127a470)
Location: mm/swapfile.c:1693
Inline: True
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/vmscan.c:shrink_page_list
  - mm/memory.c:do_swap_page
  - mm/madvise.c:madvise_free_pte_range
  - mm/page_io.c:swap_writepage
  - mm/swap_state.c:free_pages_and_swap_cache
  - mm/swap_state.c:free_page_and_swap_cache
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
  - mm/ksm.c:replace_page
```
**Symbols:**

```
ffffffff8127a470-ffffffff8127a556: try_to_free_swap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int try_to_free_swap(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81289f50)
Location: mm/swapfile.c:1693
Inline: True
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/vmscan.c:shrink_page_list
  - mm/memory.c:do_swap_page
  - mm/madvise.c:madvise_free_pte_range
  - mm/page_io.c:swap_writepage
  - mm/swap_state.c:free_pages_and_swap_cache
  - mm/swap_state.c:free_page_and_swap_cache
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
  - mm/ksm.c:replace_page
```
**Symbols:**

```
ffffffff81289f50-ffffffff8128a036: try_to_free_swap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int try_to_free_swap(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/swapfile.c (ffffffff812bc7e0)
Location: mm/swapfile.c:1730
Inline: True
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/vmscan.c:shrink_page_list
  - mm/memory.c:do_swap_page
  - mm/madvise.c:madvise_free_pte_range
  - mm/page_io.c:swap_writepage
  - mm/swap_state.c:free_pages_and_swap_cache
  - mm/swap_state.c:free_page_and_swap_cache
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:__try_to_reclaim_swap
  - mm/ksm.c:replace_page
```
**Symbols:**

```
ffffffff812bc7e0-ffffffff812bc898: try_to_free_swap.part.0 (STB_LOCAL)
ffffffff812bcc60-ffffffff812bcca8: try_to_free_swap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int try_to_free_swap(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/swapfile.c (ffffffff812c82f0)
Location: mm/swapfile.c:1748
Inline: True
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/vmscan.c:shrink_page_list
  - mm/memory.c:do_swap_page
  - mm/madvise.c:madvise_free_pte_range
  - mm/page_io.c:swap_writepage
  - mm/swap_state.c:free_pages_and_swap_cache
  - mm/swap_state.c:free_page_and_swap_cache
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:__try_to_reclaim_swap
  - mm/ksm.c:replace_page
```
**Symbols:**

```
ffffffff812c82f0-ffffffff812c83a8: try_to_free_swap.part.0 (STB_LOCAL)
ffffffff812c8790-ffffffff812c87d8: try_to_free_swap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int try_to_free_swap(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff812cf130)
Location: mm/swapfile.c:1747
Inline: True
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/vmscan.c:shrink_page_list
  - mm/memory.c:do_swap_page
  - mm/madvise.c:madvise_free_pte_range
  - mm/page_io.c:swap_writepage
  - mm/swap_state.c:free_pages_and_swap_cache
  - mm/swap_state.c:free_page_and_swap_cache
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:__try_to_reclaim_swap
  - mm/ksm.c:replace_page
```
**Symbols:**

```
ffffffff812cf130-ffffffff812cf216: try_to_free_swap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int try_to_free_swap(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff813146d0)
Location: mm/swapfile.c:1716
Inline: True
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/vmscan.c:shrink_page_list
  - mm/memory.c:do_swap_page
  - mm/madvise.c:madvise_free_pte_range
  - mm/page_io.c:swap_writepage
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:__try_to_reclaim_swap
  - mm/ksm.c:replace_page
```
**Symbols:**

```
ffffffff813146d0-ffffffff813147b6: try_to_free_swap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int try_to_free_swap(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8137fa40)
Location: mm/swapfile.c:1591
Inline: False
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/vmscan.c:shrink_page_list
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/madvise.c:madvise_free_pte_range
  - mm/page_io.c:swap_writepage
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:__try_to_reclaim_swap
  - mm/ksm.c:replace_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
**Symbols:**

```
ffffffff8137fa40-ffffffff8137fce2: try_to_free_swap (STB_GLOBAL)
```
</details>
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
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int try_to_free_swap(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffff800010324df8)
Location: mm/swapfile.c:1693
Inline: True
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/vmscan.c:shrink_page_list
  - mm/memory.c:do_swap_page
  - mm/madvise.c:madvise_free_pte_range
  - mm/page_io.c:swap_writepage
  - mm/swap_state.c:free_pages_and_swap_cache
  - mm/swap_state.c:free_page_and_swap_cache
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
  - mm/ksm.c:try_to_merge_one_page
```
**Symbols:**

```
ffff800010324df8-ffff800010324ec8: try_to_free_swap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int try_to_free_swap(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (c053c868)
Location: mm/swapfile.c:1693
Inline: True
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/vmscan.c:shrink_page_list
  - mm/memory.c:do_swap_page
  - mm/madvise.c:madvise_free_pte_range
  - mm/page_io.c:swap_writepage
  - mm/swap_state.c:free_pages_and_swap_cache
  - mm/swap_state.c:free_page_and_swap_cache
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_mm
  - mm/swapfile.c:__try_to_reclaim_swap
  - mm/ksm.c:replace_page
```
**Symbols:**

```
c053c868-c053c91c: try_to_free_swap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int try_to_free_swap(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (c0000000003fafb0)
Location: mm/swapfile.c:1693
Inline: True
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/vmscan.c:shrink_page_list
  - mm/memory.c:do_swap_page
  - mm/madvise.c:madvise_free_pte_range
  - mm/page_io.c:swap_writepage
  - mm/swap_state.c:free_pages_and_swap_cache
  - mm/swap_state.c:free_page_and_swap_cache
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:__try_to_reclaim_swap
  - mm/ksm.c:replace_page
```
**Symbols:**

```
c0000000003fafb0-c0000000003fb0d8: try_to_free_swap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int try_to_free_swap(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffe0002254b0)
Location: mm/swapfile.c:1693
Inline: True
Direct callers:
  - mm/vmscan.c:shrink_page_list
  - mm/memory.c:do_swap_page
  - mm/madvise.c:madvise_free_pte_range
  - mm/page_io.c:swap_writepage
  - mm/swap_state.c:free_pages_and_swap_cache
  - mm/swap_state.c:free_page_and_swap_cache
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:__try_to_reclaim_swap
  - mm/ksm.c:try_to_merge_one_page
```
**Symbols:**

```
ffffffe0002254b0-ffffffe000225556: try_to_free_swap (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int try_to_free_swap(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81282530)
Location: mm/swapfile.c:1693
Inline: True
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/vmscan.c:shrink_page_list
  - mm/memory.c:do_swap_page
  - mm/madvise.c:madvise_free_pte_range
  - mm/page_io.c:swap_writepage
  - mm/swap_state.c:free_pages_and_swap_cache
  - mm/swap_state.c:free_page_and_swap_cache
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
  - mm/ksm.c:replace_page
```
**Symbols:**

```
ffffffff81282530-ffffffff81282616: try_to_free_swap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int try_to_free_swap(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81274050)
Location: mm/swapfile.c:1693
Inline: True
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/vmscan.c:shrink_page_list
  - mm/memory.c:do_swap_page
  - mm/madvise.c:madvise_free_pte_range
  - mm/page_io.c:swap_writepage
  - mm/swap_state.c:free_pages_and_swap_cache
  - mm/swap_state.c:free_page_and_swap_cache
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
  - mm/ksm.c:replace_page
```
**Symbols:**

```
ffffffff81274050-ffffffff81274136: try_to_free_swap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int try_to_free_swap(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81280340)
Location: mm/swapfile.c:1693
Inline: True
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/vmscan.c:shrink_page_list
  - mm/memory.c:do_swap_page
  - mm/madvise.c:madvise_free_pte_range
  - mm/page_io.c:swap_writepage
  - mm/swap_state.c:free_pages_and_swap_cache
  - mm/swap_state.c:free_page_and_swap_cache
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
  - mm/ksm.c:replace_page
```
**Symbols:**

```
ffffffff81280340-ffffffff81280426: try_to_free_swap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int try_to_free_swap(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81290060)
Location: mm/swapfile.c:1693
Inline: True
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/vmscan.c:shrink_page_list
  - mm/memory.c:do_swap_page
  - mm/madvise.c:madvise_free_pte_range
  - mm/page_io.c:swap_writepage
  - mm/swap_state.c:free_pages_and_swap_cache
  - mm/swap_state.c:free_page_and_swap_cache
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
  - mm/ksm.c:replace_page
```
**Symbols:**

```
ffffffff81290060-ffffffff81290146: try_to_free_swap (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
