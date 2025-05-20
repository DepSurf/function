# Function: <code>pmd_trans_huge_lock</code>

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
In mm/mincore.c (ffffffff811c2737)
Location: include/linux/huge_mm.h:134
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/memcontrol.c (ffffffff811faf91)
Location: include/linux/huge_mm.h:134
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
```
```
In fs/proc/task_mmu.c (ffffffff812782c6)
Location: include/linux/huge_mm.h:134
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:clear_refs_pte_range
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
In mm/mincore.c (ffffffff811de294)
Location: include/linux/huge_mm.h:125
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/huge_memory.c (ffffffff8121822c)
Location: include/linux/huge_mm.h:125
Inline: True
Inline callers:
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In mm/memcontrol.c (ffffffff81220f9f)
Location: include/linux/huge_mm.h:125
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In fs/proc/task_mmu.c (ffffffff812a54f7)
Location: include/linux/huge_mm.h:125
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
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
In mm/mincore.c (ffffffff811ee0a4)
Location: include/linux/huge_mm.h:129
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/huge_memory.c (ffffffff8122a7cc)
Location: include/linux/huge_mm.h:129
Inline: True
Inline callers:
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In mm/memcontrol.c (ffffffff812336f3)
Location: include/linux/huge_mm.h:129
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In fs/proc/task_mmu.c (ffffffff812bae47)
Location: include/linux/huge_mm.h:129
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
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
In mm/mincore.c (ffffffff811f90ab)
Location: include/linux/huge_mm.h:182
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/huge_memory.c (ffffffff812363ec)
Location: include/linux/huge_mm.h:182
Inline: True
Inline callers:
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In mm/memcontrol.c (ffffffff8123efb3)
Location: include/linux/huge_mm.h:182
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In fs/proc/task_mmu.c (ffffffff812c7fc7)
Location: include/linux/huge_mm.h:182
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
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
In mm/mincore.c (ffffffff812113fa)
Location: include/linux/huge_mm.h:189
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mempolicy.c (ffffffff8123721f)
Location: include/linux/huge_mm.h:189
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/huge_memory.c (ffffffff8125526c)
Location: include/linux/huge_mm.h:189
Inline: True
Inline callers:
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In mm/memcontrol.c (ffffffff8125eb55)
Location: include/linux/huge_mm.h:189
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In fs/proc/task_mmu.c (ffffffff812eb87b)
Location: include/linux/huge_mm.h:189
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
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
In mm/mincore.c (ffffffff8123219e)
Location: include/linux/huge_mm.h:190
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mempolicy.c (ffffffff8125a762)
Location: include/linux/huge_mm.h:190
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/huge_memory.c (ffffffff812790a5)
Location: include/linux/huge_mm.h:190
Inline: True
Inline callers:
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In mm/memcontrol.c (ffffffff81282ec5)
Location: include/linux/huge_mm.h:190
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In fs/proc/task_mmu.c (ffffffff81318d3a)
Location: include/linux/huge_mm.h:190
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
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
In mm/mincore.c (ffffffff8124596e)
Location: include/linux/huge_mm.h:196
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mempolicy.c (ffffffff8126e5e2)
Location: include/linux/huge_mm.h:196
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/huge_memory.c (ffffffff8128d755)
Location: include/linux/huge_mm.h:196
Inline: True
Inline callers:
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In mm/memcontrol.c (ffffffff81298f15)
Location: include/linux/huge_mm.h:196
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In fs/proc/task_mmu.c (ffffffff8132fdea)
Location: include/linux/huge_mm.h:196
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
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
In mm/mincore.c (ffffffff81257aba)
Location: include/linux/huge_mm.h:211
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mempolicy.c (ffffffff81289c22)
Location: include/linux/huge_mm.h:211
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/huge_memory.c (ffffffff812a80c5)
Location: include/linux/huge_mm.h:211
Inline: True
Inline callers:
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In mm/memcontrol.c (ffffffff812b42f6)
Location: include/linux/huge_mm.h:211
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In fs/proc/task_mmu.c (ffffffff81357c1a)
Location: include/linux/huge_mm.h:211
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
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
In mm/mincore.c (ffffffff81265fca)
Location: include/linux/huge_mm.h:216
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/madvise.c (ffffffff81284e2b)
Location: include/linux/huge_mm.h:216
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/mempolicy.c (ffffffff81299792)
Location: include/linux/huge_mm.h:216
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/huge_memory.c (ffffffff812b95a5)
Location: include/linux/huge_mm.h:216
Inline: True
Inline callers:
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In mm/memcontrol.c (ffffffff812c5c16)
Location: include/linux/huge_mm.h:216
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In fs/proc/task_mmu.c (ffffffff8136fe4a)
Location: include/linux/huge_mm.h:216
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
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
In mm/mincore.c (ffffffff8129631a)
Location: include/linux/huge_mm.h:252
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/madvise.c (ffffffff812b700f)
Location: include/linux/huge_mm.h:252
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/mempolicy.c (ffffffff812cec82)
Location: include/linux/huge_mm.h:252
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/huge_memory.c (ffffffff812ee105)
Location: include/linux/huge_mm.h:252
Inline: True
Inline callers:
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In mm/memcontrol.c (ffffffff812fb906)
Location: include/linux/huge_mm.h:252
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In fs/proc/task_mmu.c (ffffffff813b7e7a)
Location: include/linux/huge_mm.h:252
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
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
In mm/mincore.c (ffffffff812a1287)
Location: include/linux/huge_mm.h:231
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/madvise.c (ffffffff812c1f4f)
Location: include/linux/huge_mm.h:231
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/mempolicy.c (ffffffff812da5c2)
Location: include/linux/huge_mm.h:231
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/huge_memory.c (ffffffff812f9788)
Location: include/linux/huge_mm.h:231
Inline: True
Inline callers:
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In mm/memcontrol.c (ffffffff81307556)
Location: include/linux/huge_mm.h:231
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In fs/proc/task_mmu.c (ffffffff813c9d3a)
Location: include/linux/huge_mm.h:231
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
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
In mm/mincore.c (ffffffff812a6a88)
Location: include/linux/huge_mm.h:236
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/madvise.c (ffffffff812c8e08)
Location: include/linux/huge_mm.h:236
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/mempolicy.c (ffffffff812e1e32)
Location: include/linux/huge_mm.h:236
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/huge_memory.c (ffffffff812ffd58)
Location: include/linux/huge_mm.h:236
Inline: True
Inline callers:
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In mm/memcontrol.c (ffffffff8130dcd6)
Location: include/linux/huge_mm.h:236
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In fs/proc/task_mmu.c (ffffffff813d139a)
Location: include/linux/huge_mm.h:236
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
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
In mm/mincore.c (ffffffff812e7f68)
Location: include/linux/huge_mm.h:236
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/madvise.c (ffffffff8130de2d)
Location: include/linux/huge_mm.h:236
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/mempolicy.c (ffffffff81328f15)
Location: include/linux/huge_mm.h:236
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/huge_memory.c (ffffffff813499a8)
Location: include/linux/huge_mm.h:236
Inline: True
Inline callers:
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In mm/memcontrol.c (ffffffff81358b36)
Location: include/linux/huge_mm.h:236
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/memory-failure.c (ffffffff8135f30a)
Location: include/linux/huge_mm.h:236
Inline: True
Inline callers:
  - mm/memory-failure.c:hwpoison_pte_range
```
```
In fs/proc/task_mmu.c (ffffffff8142289a)
Location: include/linux/huge_mm.h:236
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
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
In mm/mincore.c (ffffffff8134925b)
Location: include/linux/huge_mm.h:250
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mlock.c (ffffffff8134c542)
Location: include/linux/huge_mm.h:250
Inline: True
Inline callers:
  - mm/mlock.c:mlock_pte_range
```
```
In mm/madvise.c (ffffffff813771b8)
Location: include/linux/huge_mm.h:250
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/mempolicy.c (ffffffff81398175)
Location: include/linux/huge_mm.h:250
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/huge_memory.c (ffffffff813c01b8)
Location: include/linux/huge_mm.h:250
Inline: True
Inline callers:
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In mm/memcontrol.c (ffffffff813d2d3d)
Location: include/linux/huge_mm.h:250
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/memory-failure.c (ffffffff813d999a)
Location: include/linux/huge_mm.h:250
Inline: True
Inline callers:
  - mm/memory-failure.c:hwpoison_pte_range
```
```
In fs/proc/task_mmu.c (ffffffff814999aa)
Location: include/linux/huge_mm.h:250
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
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
In mm/mincore.c (ffffffff813c162e)
Location: include/linux/huge_mm.h:235
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mlock.c (ffffffff813c50e2)
Location: include/linux/huge_mm.h:235
Inline: True
Inline callers:
  - mm/mlock.c:mlock_pte_range
```
```
In mm/madvise.c (ffffffff813f47c9)
Location: include/linux/huge_mm.h:235
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/mempolicy.c (ffffffff81417ef5)
Location: include/linux/huge_mm.h:235
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/huge_memory.c (ffffffff814424ae)
Location: include/linux/huge_mm.h:235
Inline: True
Inline callers:
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In mm/memcontrol.c (ffffffff8145852e)
Location: include/linux/huge_mm.h:235
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/memory-failure.c (ffffffff8145fd3a)
Location: include/linux/huge_mm.h:235
Inline: True
Inline callers:
  - mm/memory-failure.c:hwpoison_pte_range
```
```
In fs/proc/task_mmu.c (ffffffff8152dbda)
Location: include/linux/huge_mm.h:235
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
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
In mm/mincore.c (ffffffff813f65d6)
Location: include/linux/huge_mm.h:197
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mlock.c (ffffffff813f9550)
Location: include/linux/huge_mm.h:197
Inline: True
Inline callers:
  - mm/mlock.c:mlock_pte_range
```
```
In mm/madvise.c (ffffffff81427d93)
Location: include/linux/huge_mm.h:197
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/mempolicy.c (ffffffff8144b54c)
Location: include/linux/huge_mm.h:197
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_folios_pte_range
```
```
In mm/huge_memory.c (ffffffff81477ca8)
Location: include/linux/huge_mm.h:197
Inline: True
Inline callers:
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In mm/memcontrol.c (ffffffff8148e276)
Location: include/linux/huge_mm.h:197
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/memory-failure.c (ffffffff81495524)
Location: include/linux/huge_mm.h:197
Inline: True
Inline callers:
  - mm/memory-failure.c:hwpoison_pte_range
```
```
In fs/proc/task_mmu.c (ffffffff81566026)
Location: include/linux/huge_mm.h:197
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
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
In mm/mincore.c (ffffffff81422286)
Location: include/linux/huge_mm.h:318
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mlock.c (ffffffff814250f2)
Location: include/linux/huge_mm.h:318
Inline: True
Inline callers:
  - mm/mlock.c:mlock_pte_range
```
```
In mm/madvise.c (ffffffff81461976)
Location: include/linux/huge_mm.h:318
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/mempolicy.c (ffffffff81484f2e)
Location: include/linux/huge_mm.h:318
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_folios_pte_range
```
```
In mm/huge_memory.c (ffffffff814a7423)
Location: include/linux/huge_mm.h:318
Inline: True
Inline callers:
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In mm/memcontrol.c (ffffffff814bdae6)
Location: include/linux/huge_mm.h:318
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/memory-failure.c (ffffffff814c4d04)
Location: include/linux/huge_mm.h:318
Inline: True
Inline callers:
  - mm/memory-failure.c:hwpoison_pte_range
```
```
In mm/userfaultfd.c (ffffffff814d3225)
Location: include/linux/huge_mm.h:318
Inline: True
Inline callers:
  - mm/userfaultfd.c:move_pages
```
```
In fs/proc/task_mmu.c (ffffffff8159e016)
Location: include/linux/huge_mm.h:318
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
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
In mm/mincore.c (ffff8000102fcf44)
Location: include/linux/huge_mm.h:216
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/madvise.c (ffff80001031f18c)
Location: include/linux/huge_mm.h:216
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/mempolicy.c (ffff800010338544)
Location: include/linux/huge_mm.h:216
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/huge_memory.c (ffff800010359e08)
Location: include/linux/huge_mm.h:216
Inline: True
Inline callers:
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In mm/memcontrol.c (ffff800010368a08)
Location: include/linux/huge_mm.h:216
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In fs/proc/task_mmu.c (ffff800010439b54)
Location: include/linux/huge_mm.h:216
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
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
In mm/mincore.c (0)
Location: include/linux/huge_mm.h:360
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/huge_mm.h:360
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/huge_mm.h:360
Inline: True
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
In mm/mincore.c (c0000000003c8384)
Location: include/linux/huge_mm.h:216
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/madvise.c (c0000000003f3ca4)
Location: include/linux/huge_mm.h:216
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/mempolicy.c (c000000000413090)
Location: include/linux/huge_mm.h:216
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/huge_memory.c (c00000000044360c)
Location: include/linux/huge_mm.h:216
Inline: True
Inline callers:
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In mm/memcontrol.c (c000000000456a60)
Location: include/linux/huge_mm.h:216
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In fs/proc/task_mmu.c (c00000000054d408)
Location: include/linux/huge_mm.h:216
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
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
In mm/mincore.c (0)
Location: include/linux/huge_mm.h:360
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/huge_mm.h:360
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/huge_mm.h:360
Inline: True
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
In mm/mincore.c (ffffffff8125e61a)
Location: include/linux/huge_mm.h:216
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/madvise.c (ffffffff8127d47b)
Location: include/linux/huge_mm.h:216
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/mempolicy.c (ffffffff81291d72)
Location: include/linux/huge_mm.h:216
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/huge_memory.c (ffffffff812b1b85)
Location: include/linux/huge_mm.h:216
Inline: True
Inline callers:
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In mm/memcontrol.c (ffffffff812be1f6)
Location: include/linux/huge_mm.h:216
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In fs/proc/task_mmu.c (ffffffff8136842a)
Location: include/linux/huge_mm.h:216
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
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
In mm/mincore.c (ffffffff81250aaa)
Location: include/linux/huge_mm.h:216
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/madvise.c (ffffffff8126f2e3)
Location: include/linux/huge_mm.h:216
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/mempolicy.c (ffffffff812839df)
Location: include/linux/huge_mm.h:216
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/huge_memory.c (ffffffff812a2f55)
Location: include/linux/huge_mm.h:216
Inline: True
Inline callers:
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In mm/memcontrol.c (ffffffff812af319)
Location: include/linux/huge_mm.h:216
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In fs/proc/task_mmu.c (ffffffff8135976a)
Location: include/linux/huge_mm.h:216
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
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
In mm/mincore.c (ffffffff8125c3ba)
Location: include/linux/huge_mm.h:216
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/madvise.c (ffffffff8127b21b)
Location: include/linux/huge_mm.h:216
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/mempolicy.c (ffffffff8128fb82)
Location: include/linux/huge_mm.h:216
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/huge_memory.c (ffffffff812af995)
Location: include/linux/huge_mm.h:216
Inline: True
Inline callers:
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In mm/memcontrol.c (ffffffff812bc006)
Location: include/linux/huge_mm.h:216
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In fs/proc/task_mmu.c (ffffffff81365efa)
Location: include/linux/huge_mm.h:216
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
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
In mm/mincore.c (ffffffff8126bdaa)
Location: include/linux/huge_mm.h:216
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/madvise.c (ffffffff8128adeb)
Location: include/linux/huge_mm.h:216
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/mempolicy.c (ffffffff8129f012)
Location: include/linux/huge_mm.h:216
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/huge_memory.c (ffffffff812bfcd5)
Location: include/linux/huge_mm.h:216
Inline: True
Inline callers:
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In mm/memcontrol.c (ffffffff812cc7d6)
Location: include/linux/huge_mm.h:216
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In fs/proc/task_mmu.c (ffffffff81379aea)
Location: include/linux/huge_mm.h:216
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
</details>
</li>
</ul>

## Differences
