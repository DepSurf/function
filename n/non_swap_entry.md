# Function: <code>non_swap_entry</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811bd965)
Location: include/linux/swapops.h:231
Inline: True
Inline callers:
  - mm/memory.c:unmap_page_range
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:copy_page_range
```
```
In mm/mincore.c (ffffffff811c2913)
Location: include/linux/swapops.h:231
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/madvise.c (0)
Location: include/linux/swapops.h:231
Inline: True
```
```
In mm/swapfile.c (ffffffff811d3b65)
Location: include/linux/swapops.h:231
Inline: True
Inline callers:
  - mm/swapfile.c:__swap_duplicate
  - mm/swapfile.c:free_swap_and_cache
```
```
In mm/hugetlb.c (ffffffff811db0ed)
Location: include/linux/swapops.h:231
Inline: True
Inline callers:
  - mm/hugetlb.c:is_hugetlb_entry_hwpoisoned
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/memcontrol.c (ffffffff811fa98e)
Location: include/linux/swapops.h:231
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In fs/proc/task_mmu.c (ffffffff812788f8)
Location: include/linux/swapops.h:231
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_pte_range
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811d9ab8)
Location: include/linux/swapops.h:231
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
```
```
In mm/mincore.c (ffffffff811de4cf)
Location: include/linux/swapops.h:231
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/madvise.c (ffffffff811eec12)
Location: include/linux/swapops.h:231
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swapfile.c (ffffffff811f1985)
Location: include/linux/swapops.h:231
Inline: True
Inline callers:
  - mm/swapfile.c:__swap_duplicate
  - mm/swapfile.c:free_swap_and_cache
```
```
In mm/hugetlb.c (ffffffff811f9278)
Location: include/linux/swapops.h:231
Inline: True
Inline callers:
  - mm/hugetlb.c:is_hugetlb_entry_hwpoisoned
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/memcontrol.c (ffffffff8121e8bc)
Location: include/linux/swapops.h:231
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In fs/proc/task_mmu.c (ffffffff812a52d1)
Location: include/linux/swapops.h:231
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811e95ee)
Location: include/linux/swapops.h:231
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
```
```
In mm/mincore.c (ffffffff811ee2e6)
Location: include/linux/swapops.h:231
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/madvise.c (ffffffff811ff543)
Location: include/linux/swapops.h:231
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swapfile.c (ffffffff81202375)
Location: include/linux/swapops.h:231
Inline: True
Inline callers:
  - mm/swapfile.c:__swap_duplicate
  - mm/swapfile.c:free_swap_and_cache
```
```
In mm/hugetlb.c (ffffffff81209e58)
Location: include/linux/swapops.h:231
Inline: True
Inline callers:
  - mm/hugetlb.c:is_hugetlb_entry_hwpoisoned
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/memcontrol.c (ffffffff81230ee1)
Location: include/linux/swapops.h:231
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In fs/proc/task_mmu.c (ffffffff812bac24)
Location: include/linux/swapops.h:231
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811f475e)
Location: include/linux/swapops.h:222
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:copy_page_range
```
```
In mm/mincore.c (ffffffff811f92ac)
Location: include/linux/swapops.h:222
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/madvise.c (ffffffff8120a1fa)
Location: include/linux/swapops.h:222
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swapfile.c (ffffffff8120d715)
Location: include/linux/swapops.h:222
Inline: True
Inline callers:
  - mm/swapfile.c:__swap_duplicate
  - mm/swapfile.c:free_swap_and_cache
```
```
In mm/hugetlb.c (ffffffff812153d8)
Location: include/linux/swapops.h:222
Inline: True
Inline callers:
  - mm/hugetlb.c:is_hugetlb_entry_hwpoisoned
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/memcontrol.c (ffffffff8123c744)
Location: include/linux/swapops.h:222
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In fs/proc/task_mmu.c (ffffffff812c7e86)
Location: include/linux/swapops.h:222
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8120c556)
Location: include/linux/swapops.h:381
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:copy_pte_range
```
```
In mm/mincore.c (ffffffff812116a4)
Location: include/linux/swapops.h:381
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/madvise.c (ffffffff81223443)
Location: include/linux/swapops.h:381
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff812260c5)
Location: include/linux/swapops.h:381
Inline: True
Inline callers:
  - mm/swap_state.c:do_swap_page_readahead
  - mm/swap_state.c:swap_readahead_detect
```
```
In mm/swapfile.c (ffffffff812276d5)
Location: include/linux/swapops.h:381
Inline: True
Inline callers:
  - mm/swapfile.c:__swap_duplicate
  - mm/swapfile.c:free_swap_and_cache
```
```
In mm/hugetlb.c (ffffffff8122ff9e)
Location: include/linux/swapops.h:381
Inline: True
Inline callers:
  - mm/hugetlb.c:is_hugetlb_entry_hwpoisoned
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/memcontrol.c (ffffffff8125c3ce)
Location: include/linux/swapops.h:381
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/hmm.c (0)
Location: include/linux/swapops.h:381
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff812ebff8)
Location: include/linux/swapops.h:381
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_pte_range
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8122d201)
Location: include/linux/swapops.h:381
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
```
In mm/mincore.c (ffffffff8123243c)
Location: include/linux/swapops.h:381
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/madvise.c (ffffffff812462bf)
Location: include/linux/swapops.h:381
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff81248478)
Location: include/linux/swapops.h:381
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swapin_readahead
```
```
In mm/swapfile.c (ffffffff81249c35)
Location: include/linux/swapops.h:381
Inline: True
Inline callers:
  - mm/swapfile.c:__swap_duplicate
  - mm/swapfile.c:free_swap_and_cache
```
```
In mm/hugetlb.c (ffffffff81252449)
Location: include/linux/swapops.h:381
Inline: True
Inline callers:
  - mm/hugetlb.c:is_hugetlb_entry_hwpoisoned
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/memcontrol.c (ffffffff8127fc2e)
Location: include/linux/swapops.h:381
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/hmm.c (ffffffff812936ae)
Location: include/linux/swapops.h:381
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/proc/task_mmu.c (ffffffff81319712)
Location: include/linux/swapops.h:381
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_pte_range
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81240798)
Location: include/linux/swapops.h:367
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
```
In mm/mincore.c (ffffffff81245c0f)
Location: include/linux/swapops.h:367
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/madvise.c (ffffffff8125a6df)
Location: include/linux/swapops.h:367
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff8125ca48)
Location: include/linux/swapops.h:367
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swapin_readahead
```
```
In mm/swapfile.c (ffffffff8125e295)
Location: include/linux/swapops.h:367
Inline: True
Inline callers:
  - mm/swapfile.c:__swap_duplicate
  - mm/swapfile.c:free_swap_and_cache
```
```
In mm/hugetlb.c (ffffffff812666a9)
Location: include/linux/swapops.h:367
Inline: True
Inline callers:
  - mm/hugetlb.c:is_hugetlb_entry_hwpoisoned
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/memcontrol.c (ffffffff8129459e)
Location: include/linux/swapops.h:367
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/hmm.c (ffffffff812a7c54)
Location: include/linux/swapops.h:367
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/proc/task_mmu.c (ffffffff81330333)
Location: include/linux/swapops.h:367
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_pte_range
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81252a3e)
Location: include/linux/swapops.h:352
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
```
In mm/mincore.c (ffffffff81257d6b)
Location: include/linux/swapops.h:352
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/madvise.c (ffffffff812757bf)
Location: include/linux/swapops.h:352
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff81277c3d)
Location: include/linux/swapops.h:352
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swapin_readahead
```
```
In mm/swapfile.c (ffffffff8127b3c5)
Location: include/linux/swapops.h:352
Inline: True
Inline callers:
  - mm/swapfile.c:free_swap_and_cache
```
```
In mm/hugetlb.c (ffffffff81281966)
Location: include/linux/swapops.h:352
Inline: True
Inline callers:
  - mm/hugetlb.c:is_hugetlb_entry_hwpoisoned
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/memcontrol.c (ffffffff812b0951)
Location: include/linux/swapops.h:352
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/hmm.c (ffffffff812c439c)
Location: include/linux/swapops.h:352
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff8135816a)
Location: include/linux/swapops.h:352
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_pte_range
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81260f9e)
Location: include/linux/swapops.h:352
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
```
In mm/mincore.c (ffffffff8126627b)
Location: include/linux/swapops.h:352
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/madvise.c (ffffffff8128478f)
Location: include/linux/swapops.h:352
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff8128772d)
Location: include/linux/swapops.h:352
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swapin_readahead
```
```
In mm/swapfile.c (ffffffff8128aea5)
Location: include/linux/swapops.h:352
Inline: True
Inline callers:
  - mm/swapfile.c:free_swap_and_cache
```
```
In mm/hugetlb.c (ffffffff81291376)
Location: include/linux/swapops.h:352
Inline: True
Inline callers:
  - mm/hugetlb.c:is_hugetlb_entry_hwpoisoned
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/memcontrol.c (ffffffff812c23b1)
Location: include/linux/swapops.h:352
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/hmm.c (ffffffff812d5cd2)
Location: include/linux/swapops.h:352
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff8137039a)
Location: include/linux/swapops.h:352
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_pte_range
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81291423)
Location: include/linux/swapops.h:355
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_one_pte
```
```
In mm/mincore.c (ffffffff812965d4)
Location: include/linux/swapops.h:355
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/madvise.c (ffffffff812b6938)
Location: include/linux/swapops.h:355
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff812b98aa)
Location: include/linux/swapops.h:355
Inline: True
Inline callers:
  - mm/swap_state.c:swap_vma_readahead
  - mm/swap_state.c:swap_ra_info
```
```
In mm/swapfile.c (ffffffff812be095)
Location: include/linux/swapops.h:355
Inline: True
Inline callers:
  - mm/swapfile.c:free_swap_and_cache
```
```
In mm/hugetlb.c (ffffffff812c467b)
Location: include/linux/swapops.h:355
Inline: True
Inline callers:
  - mm/hugetlb.c:is_hugetlb_entry_hwpoisoned
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/memcontrol.c (ffffffff812f5d7b)
Location: include/linux/swapops.h:355
Inline: True
```
```
In mm/hmm.c (0)
Location: include/linux/swapops.h:355
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff813b822e)
Location: include/linux/swapops.h:355
Inline: True
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
In mm/memory.c (ffffffff8129bd93)
Location: include/linux/swapops.h:355
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
```
In mm/mincore.c (ffffffff812a1547)
Location: include/linux/swapops.h:355
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/madvise.c (ffffffff812c2b88)
Location: include/linux/swapops.h:355
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff812c5313)
Location: include/linux/swapops.h:355
Inline: True
Inline callers:
  - mm/swap_state.c:swap_vma_readahead
```
```
In mm/swapfile.c (ffffffff812c9c95)
Location: include/linux/swapops.h:355
Inline: True
Inline callers:
  - mm/swapfile.c:free_swap_and_cache
```
```
In mm/memcontrol.c (0)
Location: include/linux/swapops.h:355
Inline: True
```
```
In mm/hmm.c (0)
Location: include/linux/swapops.h:355
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff813c998e)
Location: include/linux/swapops.h:355
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812a1031)
Location: include/linux/swapops.h:364
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
```
In mm/mincore.c (ffffffff812a6d3f)
Location: include/linux/swapops.h:364
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/madvise.c (ffffffff812c9a04)
Location: include/linux/swapops.h:364
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff812cbfc1)
Location: include/linux/swapops.h:364
Inline: True
Inline callers:
  - mm/swap_state.c:swap_vma_readahead
```
```
In mm/swapfile.c (ffffffff812d0705)
Location: include/linux/swapops.h:364
Inline: True
Inline callers:
  - mm/swapfile.c:free_swap_and_cache
```
```
In mm/memcontrol.c (0)
Location: include/linux/swapops.h:364
Inline: True
```
```
In mm/hmm.c (0)
Location: include/linux/swapops.h:364
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff813d0a7b)
Location: include/linux/swapops.h:364
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812e1f98)
Location: include/linux/swapops.h:392
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:copy_nonpresent_pte
```
```
In mm/mincore.c (ffffffff812e821f)
Location: include/linux/swapops.h:392
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/madvise.c (ffffffff8130ea24)
Location: include/linux/swapops.h:392
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff81311191)
Location: include/linux/swapops.h:392
Inline: True
Inline callers:
  - mm/swap_state.c:swap_vma_readahead
```
```
In mm/swapfile.c (ffffffff81315c45)
Location: include/linux/swapops.h:392
Inline: True
Inline callers:
  - mm/swapfile.c:free_swap_and_cache
```
```
In mm/memcontrol.c (0)
Location: include/linux/swapops.h:392
Inline: True
```
```
In mm/hmm.c (0)
Location: include/linux/swapops.h:392
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff81421310)
Location: include/linux/swapops.h:392
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81343c20)
Location: include/linux/swapops.h:510
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:copy_nonpresent_pte
```
```
In mm/mincore.c (ffffffff81349591)
Location: include/linux/swapops.h:510
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/madvise.c (ffffffff81376bdf)
Location: include/linux/swapops.h:510
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:force_shm_swapin_readahead
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff8137c1ce)
Location: include/linux/swapops.h:510
Inline: True
Inline callers:
  - mm/swap_state.c:swap_vma_readahead
  - mm/swap_state.c:find_get_incore_page
```
```
In mm/swapfile.c (ffffffff81381d95)
Location: include/linux/swapops.h:510
Inline: True
Inline callers:
  - mm/swapfile.c:free_swap_and_cache
```
```
In mm/memcontrol.c (0)
Location: include/linux/swapops.h:510
Inline: True
```
```
In mm/hmm.c (0)
Location: include/linux/swapops.h:510
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff8149a41c)
Location: include/linux/swapops.h:510
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_pte_entry
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
In mm/memory.c (ffffffff813bbca0)
Location: include/linux/swapops.h:584
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:copy_nonpresent_pte
```
```
In mm/mincore.c (ffffffff813c197b)
Location: include/linux/swapops.h:584
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/madvise.c (ffffffff813f43a9)
Location: include/linux/swapops.h:584
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:force_shm_swapin_readahead
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff813f996e)
Location: include/linux/swapops.h:584
Inline: True
Inline callers:
  - mm/swap_state.c:swap_vma_readahead
  - mm/swap_state.c:filemap_get_incore_folio
```
```
In mm/swapfile.c (ffffffff81400545)
Location: include/linux/swapops.h:584
Inline: True
Inline callers:
  - mm/swapfile.c:free_swap_and_cache
```
```
In mm/memcontrol.c (0)
Location: include/linux/swapops.h:584
Inline: True
```
```
In mm/hmm.c (0)
Location: include/linux/swapops.h:584
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff8152f40c)
Location: include/linux/swapops.h:584
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_pte_entry
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
In mm/memory.c (ffffffff813f06c1)
Location: include/linux/swapops.h:575
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:copy_nonpresent_pte
```
```
In mm/mincore.c (ffffffff813f6814)
Location: include/linux/swapops.h:575
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/madvise.c (ffffffff81427a96)
Location: include/linux/swapops.h:575
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:shmem_swapin_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff8142c805)
Location: include/linux/swapops.h:575
Inline: True
Inline callers:
  - mm/swap_state.c:swap_vma_readahead
  - mm/swap_state.c:filemap_get_incore_folio
```
```
In mm/swapfile.c (ffffffff814333e5)
Location: include/linux/swapops.h:575
Inline: True
Inline callers:
  - mm/swapfile.c:free_swap_and_cache
```
```
In mm/memcontrol.c (0)
Location: include/linux/swapops.h:575
Inline: True
```
```
In mm/hmm.c (0)
Location: include/linux/swapops.h:575
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff815676cc)
Location: include/linux/swapops.h:575
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_pte_entry
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
In mm/memory.c (ffffffff81420050)
Location: include/linux/swapops.h:580
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:copy_nonpresent_pte
```
```
In mm/mincore.c (ffffffff814224c4)
Location: include/linux/swapops.h:580
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/madvise.c (ffffffff814612a9)
Location: include/linux/swapops.h:580
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:shmem_swapin_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff81465f50)
Location: include/linux/swapops.h:580
Inline: True
Inline callers:
  - mm/swap_state.c:swap_vma_readahead
  - mm/swap_state.c:filemap_get_incore_folio
```
```
In mm/swapfile.c (ffffffff8146c7d5)
Location: include/linux/swapops.h:580
Inline: True
Inline callers:
  - mm/swapfile.c:free_swap_and_cache
```
```
In mm/memcontrol.c (0)
Location: include/linux/swapops.h:580
Inline: True
```
```
In mm/userfaultfd.c (ffffffff814d2eef)
Location: include/linux/swapops.h:580
Inline: True
Inline callers:
  - mm/userfaultfd.c:move_pages_pte
```
```
In mm/hmm.c (0)
Location: include/linux/swapops.h:580
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff8159fedc)
Location: include/linux/swapops.h:580
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_pte_entry
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffff8000102f834c)
Location: include/linux/swapops.h:352
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_pte_range
```
```
In mm/mincore.c (ffff8000102fd05c)
Location: include/linux/swapops.h:352
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/madvise.c (ffff80001031eadc)
Location: include/linux/swapops.h:352
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffff800010322244)
Location: include/linux/swapops.h:352
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swapin_readahead
```
```
In mm/swapfile.c (ffff800010326340)
Location: include/linux/swapops.h:352
Inline: True
Inline callers:
  - mm/swapfile.c:free_swap_and_cache
```
```
In mm/hugetlb.c (ffff800010335ddc)
Location: include/linux/swapops.h:352
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_huge_pmd
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/memcontrol.c (ffff800010363e68)
Location: include/linux/swapops.h:352
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/hmm.c (ffff80001037b778)
Location: include/linux/swapops.h:352
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/proc/task_mmu.c (ffff80001043a0d0)
Location: include/linux/swapops.h:352
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_pte_range
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (c051ab2c)
Location: include/linux/swapops.h:352
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_pte_range
```
```
In mm/mincore.c (c051c650)
Location: include/linux/swapops.h:352
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/madvise.c (c0537720)
Location: include/linux/swapops.h:352
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (c053a900)
Location: include/linux/swapops.h:352
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swapin_readahead
```
```
In mm/swapfile.c (c053db2c)
Location: include/linux/swapops.h:352
Inline: True
Inline callers:
  - mm/swapfile.c:free_swap_and_cache
```
```
In mm/memcontrol.c (c05561a8)
Location: include/linux/swapops.h:352
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/hmm.c (c05664d0)
Location: include/linux/swapops.h:352
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/proc/task_mmu.c (c0600a0c)
Location: include/linux/swapops.h:352
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_pte_entry
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (c0000000003c16a4)
Location: include/linux/swapops.h:352
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
```
```
In mm/mincore.c (c0000000003c870c)
Location: include/linux/swapops.h:352
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/madvise.c (c0000000003f312c)
Location: include/linux/swapops.h:352
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (c0000000003f7c84)
Location: include/linux/swapops.h:352
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swapin_readahead
```
```
In mm/swapfile.c (c0000000003fc980)
Location: include/linux/swapops.h:352
Inline: True
Inline callers:
  - mm/swapfile.c:free_swap_and_cache
```
```
In mm/hugetlb.c (c000000000406a14)
Location: include/linux/swapops.h:352
Inline: True
Inline callers:
  - mm/hugetlb.c:is_hugetlb_entry_hwpoisoned
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/memcontrol.c (c000000000450ea8)
Location: include/linux/swapops.h:352
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/hmm.c (c00000000046fedc)
Location: include/linux/swapops.h:352
Inline: True
```
```
In fs/proc/task_mmu.c (c00000000054dfe8)
Location: include/linux/swapops.h:352
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_pte_range
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffe0002088d0)
Location: include/linux/swapops.h:352
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
```
```
In mm/mincore.c (ffffffe00020bba4)
Location: include/linux/swapops.h:352
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/madvise.c (ffffffe000220576)
Location: include/linux/swapops.h:352
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffe00022325a)
Location: include/linux/swapops.h:352
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swapin_readahead
```
```
In mm/swapfile.c (ffffffe0002265ec)
Location: include/linux/swapops.h:352
Inline: True
Inline callers:
  - mm/swapfile.c:free_swap_and_cache
```
```
In mm/hugetlb.c (ffffffe000231efe)
Location: include/linux/swapops.h:352
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_huge_pmd
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/memcontrol.c (ffffffe000241d1e)
Location: include/linux/swapops.h:352
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/hmm.c (ffffffe000251f90)
Location: include/linux/swapops.h:352
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/proc/task_mmu.c (ffffffe0002d31ce)
Location: include/linux/swapops.h:352
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_pte_range
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812595ee)
Location: include/linux/swapops.h:352
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
```
In mm/mincore.c (ffffffff8125e8cb)
Location: include/linux/swapops.h:352
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/madvise.c (ffffffff8127cddf)
Location: include/linux/swapops.h:352
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff8127fcf7)
Location: include/linux/swapops.h:352
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swapin_readahead
```
```
In mm/swapfile.c (ffffffff81283485)
Location: include/linux/swapops.h:352
Inline: True
Inline callers:
  - mm/swapfile.c:free_swap_and_cache
```
```
In mm/hugetlb.c (ffffffff81289956)
Location: include/linux/swapops.h:352
Inline: True
Inline callers:
  - mm/hugetlb.c:is_hugetlb_entry_hwpoisoned
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/memcontrol.c (ffffffff812ba991)
Location: include/linux/swapops.h:352
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/hmm.c (ffffffff812ce2b2)
Location: include/linux/swapops.h:352
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff8136897a)
Location: include/linux/swapops.h:352
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_pte_range
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8124ba65)
Location: include/linux/swapops.h:352
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
```
```
In mm/mincore.c (ffffffff81250c7b)
Location: include/linux/swapops.h:352
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/madvise.c (ffffffff8126ec49)
Location: include/linux/swapops.h:352
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff81271b37)
Location: include/linux/swapops.h:352
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swapin_readahead
```
```
In mm/swapfile.c (ffffffff81275325)
Location: include/linux/swapops.h:352
Inline: True
Inline callers:
  - mm/swapfile.c:free_swap_and_cache
```
```
In mm/hugetlb.c (ffffffff8127aa20)
Location: include/linux/swapops.h:352
Inline: True
Inline callers:
  - mm/hugetlb.c:is_hugetlb_entry_hwpoisoned
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/memcontrol.c (ffffffff812abb3d)
Location: include/linux/swapops.h:352
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/hmm.c (ffffffff812bf12a)
Location: include/linux/swapops.h:352
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff81359c2a)
Location: include/linux/swapops.h:352
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_pte_range
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8125738e)
Location: include/linux/swapops.h:352
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
```
In mm/mincore.c (ffffffff8125c66b)
Location: include/linux/swapops.h:352
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/madvise.c (ffffffff8127ab7f)
Location: include/linux/swapops.h:352
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff8127db1d)
Location: include/linux/swapops.h:352
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swapin_readahead
```
```
In mm/swapfile.c (ffffffff81281295)
Location: include/linux/swapops.h:352
Inline: True
Inline callers:
  - mm/swapfile.c:free_swap_and_cache
```
```
In mm/hugetlb.c (ffffffff81287766)
Location: include/linux/swapops.h:352
Inline: True
Inline callers:
  - mm/hugetlb.c:is_hugetlb_entry_hwpoisoned
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/memcontrol.c (ffffffff812b87a1)
Location: include/linux/swapops.h:352
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/hmm.c (ffffffff812cc0c2)
Location: include/linux/swapops.h:352
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff8136644a)
Location: include/linux/swapops.h:352
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_pte_range
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81266d7e)
Location: include/linux/swapops.h:352
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
```
In mm/mincore.c (ffffffff8126c052)
Location: include/linux/swapops.h:352
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/madvise.c (ffffffff8128a760)
Location: include/linux/swapops.h:352
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff8128d6cd)
Location: include/linux/swapops.h:352
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swapin_readahead
```
```
In mm/swapfile.c (ffffffff81290fa5)
Location: include/linux/swapops.h:352
Inline: True
Inline callers:
  - mm/swapfile.c:free_swap_and_cache
```
```
In mm/hugetlb.c (ffffffff81298296)
Location: include/linux/swapops.h:352
Inline: True
Inline callers:
  - mm/hugetlb.c:is_hugetlb_entry_hwpoisoned
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/memcontrol.c (ffffffff812c8de1)
Location: include/linux/swapops.h:352
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/hmm.c (ffffffff812dce02)
Location: include/linux/swapops.h:352
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff8137978a)
Location: include/linux/swapops.h:352
Inline: True
```
</details>
</li>
</ul>

## Differences
