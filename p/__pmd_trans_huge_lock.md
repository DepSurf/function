# Function: <code>__pmd_trans_huge_lock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __pmd_trans_huge_lock(pmd_t *pmd, struct vm_area_struct *vma, spinlock_t **ptl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff811f6770)
Location: mm/huge_memory.c:1598
Inline: False
Direct callers:
  - mm/mincore.c:mincore_pte_range
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
**Symbols:**

```
ffffffff811f6770-ffffffff811f6874: __pmd_trans_huge_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
spinlock_t *__pmd_trans_huge_lock(pmd_t *pmd, struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812155c0)
Location: mm/huge_memory.c:1467
Inline: False
Direct callers:
  - mm/mincore.c:mincore_pte_range
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
**Symbols:**

```
ffffffff812155c0-ffffffff81215660: __pmd_trans_huge_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
spinlock_t *__pmd_trans_huge_lock(pmd_t *pmd, struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff81227c40)
Location: mm/huge_memory.c:1592
Inline: False
Direct callers:
  - mm/mincore.c:mincore_pte_range
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
**Symbols:**

```
ffffffff81227c40-ffffffff81227cdd: __pmd_trans_huge_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
spinlock_t *__pmd_trans_huge_lock(pmd_t *pmd, struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff81233e30)
Location: mm/huge_memory.c:1836
Inline: False
Direct callers:
  - mm/mincore.c:mincore_pte_range
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
**Symbols:**

```
ffffffff81233e30-ffffffff81233ecd: __pmd_trans_huge_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
spinlock_t *__pmd_trans_huge_lock(pmd_t *pmd, struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812518d0)
Location: mm/huge_memory.c:1942
Inline: False
Direct callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
**Symbols:**

```
ffffffff812518d0-ffffffff812519cd: __pmd_trans_huge_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
spinlock_t *__pmd_trans_huge_lock(pmd_t *pmd, struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff81275e10)
Location: mm/huge_memory.c:1930
Inline: False
Direct callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
**Symbols:**

```
ffffffff81275e10-ffffffff81275ef4: __pmd_trans_huge_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
spinlock_t *__pmd_trans_huge_lock(pmd_t *pmd, struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff8128ac70)
Location: mm/huge_memory.c:1950
Inline: False
Direct callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
**Symbols:**

```
ffffffff8128ac70-ffffffff8128ad54: __pmd_trans_huge_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
spinlock_t *__pmd_trans_huge_lock(pmd_t *pmd, struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812a5890)
Location: mm/huge_memory.c:2008
Inline: False
Direct callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
**Symbols:**

```
ffffffff812a5890-ffffffff812a5974: __pmd_trans_huge_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
spinlock_t *__pmd_trans_huge_lock(pmd_t *pmd, struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812b6d50)
Location: mm/huge_memory.c:2013
Inline: False
Direct callers:
  - mm/mincore.c:mincore_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
**Symbols:**

```
ffffffff812b6d50-ffffffff812b6e34: __pmd_trans_huge_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
spinlock_t *__pmd_trans_huge_lock(pmd_t *pmd, struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812ebeb0)
Location: mm/huge_memory.c:1886
Inline: False
Direct callers:
  - mm/mincore.c:mincore_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
**Symbols:**

```
ffffffff812ebeb0-ffffffff812ebf8b: __pmd_trans_huge_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
spinlock_t *__pmd_trans_huge_lock(pmd_t *pmd, struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812f6f20)
Location: mm/huge_memory.c:1901
Inline: False
Direct callers:
  - mm/mincore.c:mincore_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
**Symbols:**

```
ffffffff812f6f20-ffffffff812f6ffb: __pmd_trans_huge_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
spinlock_t *__pmd_trans_huge_lock(pmd_t *pmd, struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812fd2d0)
Location: mm/huge_memory.c:1908
Inline: False
Direct callers:
  - mm/mincore.c:mincore_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
**Symbols:**

```
ffffffff812fd2d0-ffffffff812fd3a9: __pmd_trans_huge_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
spinlock_t *__pmd_trans_huge_lock(pmd_t *pmd, struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff81346f90)
Location: mm/huge_memory.c:1831
Inline: False
Direct callers:
  - mm/mincore.c:mincore_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
  - mm/memory-failure.c:hwpoison_pte_range
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
**Symbols:**

```
ffffffff81346f90-ffffffff8134706b: __pmd_trans_huge_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
spinlock_t *__pmd_trans_huge_lock(pmd_t *pmd, struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff813bd2d0)
Location: mm/huge_memory.c:1857
Inline: False
Direct callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mlock.c:mlock_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
  - mm/memory-failure.c:hwpoison_pte_range
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
**Symbols:**

```
ffffffff813bd2d0-ffffffff813bd3bf: __pmd_trans_huge_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
spinlock_t *__pmd_trans_huge_lock(pmd_t *pmd, struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff8143fa00)
Location: mm/huge_memory.c:1956
Inline: False
Direct callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mlock.c:mlock_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
  - mm/memory-failure.c:hwpoison_pte_range
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
**Symbols:**

```
ffffffff8143fa00-ffffffff8143faf7: __pmd_trans_huge_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
spinlock_t *__pmd_trans_huge_lock(pmd_t *pmd, struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff81475240)
Location: mm/huge_memory.c:1945
Inline: False
Direct callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mlock.c:mlock_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/mempolicy.c:queue_folios_pte_range
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
  - mm/memory-failure.c:hwpoison_pte_range
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
**Symbols:**

```
ffffffff81475240-ffffffff81475338: __pmd_trans_huge_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
spinlock_t *__pmd_trans_huge_lock(pmd_t *pmd, struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff814a4cb0)
Location: mm/huge_memory.c:2284
Inline: False
Direct callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mlock.c:mlock_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/mempolicy.c:queue_folios_pte_range
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
  - mm/memory-failure.c:hwpoison_pte_range
  - mm/userfaultfd.c:move_pages
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
**Symbols:**

```
ffffffff814a4cb0-ffffffff814a4da7: __pmd_trans_huge_lock (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
spinlock_t *__pmd_trans_huge_lock(pmd_t *pmd, struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffff800010357ad0)
Location: mm/huge_memory.c:2013
Inline: False
Direct callers:
  - mm/mincore.c:mincore_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
**Symbols:**

```
ffff800010357ad0-ffff800010357b98: __pmd_trans_huge_lock (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
spinlock_t *__pmd_trans_huge_lock(pmd_t *pmd, struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (c00000000043fd00)
Location: mm/huge_memory.c:2013
Inline: False
Direct callers:
  - mm/mincore.c:mincore_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
**Symbols:**

```
c00000000043fd00-c00000000043fea4: __pmd_trans_huge_lock (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
spinlock_t *__pmd_trans_huge_lock(pmd_t *pmd, struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812af330)
Location: mm/huge_memory.c:2013
Inline: False
Direct callers:
  - mm/mincore.c:mincore_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
**Symbols:**

```
ffffffff812af330-ffffffff812af414: __pmd_trans_huge_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
spinlock_t *__pmd_trans_huge_lock(pmd_t *pmd, struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812a0820)
Location: mm/huge_memory.c:2013
Inline: False
Direct callers:
  - mm/mincore.c:mincore_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
**Symbols:**

```
ffffffff812a0820-ffffffff812a08f1: __pmd_trans_huge_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
spinlock_t *__pmd_trans_huge_lock(pmd_t *pmd, struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812ad140)
Location: mm/huge_memory.c:2013
Inline: False
Direct callers:
  - mm/mincore.c:mincore_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
**Symbols:**

```
ffffffff812ad140-ffffffff812ad224: __pmd_trans_huge_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
spinlock_t *__pmd_trans_huge_lock(pmd_t *pmd, struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812bd4c0)
Location: mm/huge_memory.c:2013
Inline: False
Direct callers:
  - mm/mincore.c:mincore_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
**Symbols:**

```
ffffffff812bd4c0-ffffffff812bd5a2: __pmd_trans_huge_lock (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>spinlock_t **ptl</code>
</li>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>spinlock_t *</code>
</li>
</ul>
</details>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
