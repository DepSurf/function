# Function: <code>walk_page_range</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int walk_page_range(long unsigned int start, long unsigned int end, struct mm_walk *walk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pagewalk.c (ffffffff811d0210)
Location: mm/pagewalk.c:239
Inline: False
Direct callers:
  - mm/mincore.c:SyS_mincore
  - mm/madvise.c:force_swapin_readahead
  - mm/mempolicy.c:queue_pages_range
  - mm/memcontrol.c:mem_cgroup_move_task
  - mm/memcontrol.c:mem_cgroup_can_attach
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:pagemap_read
```
**Symbols:**

```
ffffffff811d0210-ffffffff811d02ed: walk_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int walk_page_range(long unsigned int start, long unsigned int end, struct mm_walk *walk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pagewalk.c (ffffffff811ed3b0)
Location: mm/pagewalk.c:239
Inline: False
Direct callers:
  - mm/mincore.c:SyS_mincore
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:force_swapin_readahead
  - mm/mempolicy.c:queue_pages_range
  - mm/memcontrol.c:mem_cgroup_move_task
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:clear_refs_write
```
**Symbols:**

```
ffffffff811ed3b0-ffffffff811ed49f: walk_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int walk_page_range(long unsigned int start, long unsigned int end, struct mm_walk *walk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pagewalk.c (ffffffff811f77a0)
Location: mm/pagewalk.c:239
Inline: False
Direct callers:
  - mm/mincore.c:SyS_mincore
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:force_swapin_readahead
  - mm/mempolicy.c:queue_pages_range
  - mm/memcontrol.c:mem_cgroup_move_task
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:clear_refs_write
```
**Symbols:**

```
ffffffff811f77a0-ffffffff811f788f: walk_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int walk_page_range(long unsigned int start, long unsigned int end, struct mm_walk *walk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pagewalk.c (ffffffff81202900)
Location: mm/pagewalk.c:284
Inline: False
Direct callers:
  - mm/mincore.c:SyS_mincore
  - mm/madvise.c:madvise_willneed
  - mm/mempolicy.c:queue_pages_range
  - mm/memcontrol.c:mem_cgroup_move_task
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:clear_refs_write
```
**Symbols:**

```
ffffffff81202900-ffffffff812029dd: walk_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int walk_page_range(long unsigned int start, long unsigned int end, struct mm_walk *walk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pagewalk.c (ffffffff8121b670)
Location: mm/pagewalk.c:289
Inline: False
Direct callers:
  - mm/mincore.c:SyS_mincore
  - mm/madvise.c:madvise_willneed
  - mm/mempolicy.c:queue_pages_range
  - mm/memcontrol.c:mem_cgroup_move_task
  - mm/hmm.c:hmm_vma_fault
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:clear_refs_write
```
**Symbols:**

```
ffffffff8121b670-ffffffff8121b74d: walk_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int walk_page_range(long unsigned int start, long unsigned int end, struct mm_walk *walk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pagewalk.c (ffffffff8123d450)
Location: mm/pagewalk.c:293
Inline: False
Direct callers:
  - mm/mincore.c:__ia32_sys_mincore
  - mm/mincore.c:__x64_sys_mincore
  - mm/mprotect.c:mprotect_fixup
  - mm/madvise.c:madvise_willneed
  - mm/mempolicy.c:queue_pages_range
  - mm/memcontrol.c:mem_cgroup_move_task
  - mm/hmm.c:hmm_vma_fault
  - mm/hmm.c:hmm_vma_get_pfns
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:clear_refs_write
```
**Symbols:**

```
ffffffff8123d450-ffffffff8123d52c: walk_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int walk_page_range(long unsigned int start, long unsigned int end, struct mm_walk *walk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pagewalk.c (ffffffff812519a0)
Location: mm/pagewalk.c:293
Inline: False
Direct callers:
  - mm/mincore.c:__ia32_sys_mincore
  - mm/mincore.c:__x64_sys_mincore
  - mm/mprotect.c:mprotect_fixup
  - mm/madvise.c:madvise_willneed
  - mm/mempolicy.c:queue_pages_range
  - mm/memcontrol.c:mem_cgroup_move_task
  - mm/hmm.c:hmm_vma_fault
  - mm/hmm.c:hmm_vma_get_pfns
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:clear_refs_write
```
**Symbols:**

```
ffffffff812519a0-ffffffff81251a7c: walk_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int walk_page_range(long unsigned int start, long unsigned int end, struct mm_walk *walk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pagewalk.c (ffffffff81263c70)
Location: mm/pagewalk.c:293
Inline: False
Direct callers:
  - mm/mincore.c:__ia32_sys_mincore
  - mm/mincore.c:__x64_sys_mincore
  - mm/mprotect.c:mprotect_fixup
  - mm/madvise.c:madvise_willneed
  - mm/mempolicy.c:queue_pages_range
  - mm/memcontrol.c:mem_cgroup_move_task
  - mm/hmm.c:hmm_range_fault
  - mm/hmm.c:hmm_range_snapshot
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:clear_refs_write
```
**Symbols:**

```
ffffffff81263c70-ffffffff81263d4c: walk_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int walk_page_range(struct mm_struct *mm, long unsigned int start, long unsigned int end, const struct mm_walk_ops *ops, void *private);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pagewalk.c (ffffffff81272480)
Location: mm/pagewalk.c:301
Inline: False
Direct callers:
  - mm/mincore.c:__ia32_sys_mincore
  - mm/mincore.c:__x64_sys_mincore
  - mm/mprotect.c:mprotect_fixup
  - mm/madvise.c:__do_sys_madvise
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_pageout
  - mm/madvise.c:madvise_cold
  - mm/mempolicy.c:kernel_mbind
  - mm/mempolicy.c:migrate_to_node
  - mm/migrate.c:migrate_vma_setup
  - mm/memcontrol.c:mem_cgroup_move_task
  - mm/hmm.c:hmm_range_fault
  - mm/hmm.c:hmm_range_fault
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:clear_refs_write
```
**Symbols:**

```
ffffffff81272480-ffffffff81272584: walk_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int walk_page_range(struct mm_struct *mm, long unsigned int start, long unsigned int end, const struct mm_walk_ops *ops, void *private);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pagewalk.c (ffffffff812a2fc0)
Location: mm/pagewalk.c:379
Inline: False
Direct callers:
  - mm/mincore.c:do_mincore
  - mm/mprotect.c:mprotect_fixup
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_pageout
  - mm/madvise.c:madvise_cold
  - mm/madvise.c:madvise_willneed
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:migrate_to_node
  - mm/migrate.c:migrate_vma_collect
  - mm/memcontrol.c:mem_cgroup_move_charge
  - mm/hmm.c:hmm_range_fault
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:clear_refs_write
```
**Symbols:**

```
ffffffff812a2fc0-ffffffff812a30d4: walk_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int walk_page_range(struct mm_struct *mm, long unsigned int start, long unsigned int end, const struct mm_walk_ops *ops, void *private);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pagewalk.c (ffffffff812ae8e0)
Location: mm/pagewalk.c:379
Inline: False
Direct callers:
  - mm/mincore.c:do_mincore
  - mm/mprotect.c:mprotect_fixup
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_pageout
  - mm/madvise.c:madvise_cold
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:migrate_to_node
  - mm/migrate.c:migrate_vma_collect
  - mm/memcontrol.c:mem_cgroup_move_charge
  - mm/memcontrol.c:mem_cgroup_count_precharge
  - mm/hmm.c:hmm_range_fault
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:clear_refs_write
```
**Symbols:**

```
ffffffff812ae8e0-ffffffff812ae9f4: walk_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int walk_page_range(struct mm_struct *mm, long unsigned int start, long unsigned int end, const struct mm_walk_ops *ops, void *private);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pagewalk.c (ffffffff812b3d60)
Location: mm/pagewalk.c:379
Inline: False
Direct callers:
  - mm/mincore.c:__do_sys_mincore
  - mm/mprotect.c:mprotect_fixup
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_pageout
  - mm/madvise.c:madvise_cold
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:migrate_to_node
  - mm/migrate.c:migrate_vma_setup
  - mm/memcontrol.c:mem_cgroup_move_charge
  - mm/hmm.c:hmm_range_fault
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:clear_refs_write
```
**Symbols:**

```
ffffffff812b3d60-ffffffff812b3e77: walk_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int walk_page_range(struct mm_struct *mm, long unsigned int start, long unsigned int end, const struct mm_walk_ops *ops, void *private);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pagewalk.c (ffffffff812f5940)
Location: mm/pagewalk.c:427
Inline: False
Direct callers:
  - mm/mincore.c:__do_sys_mincore
  - mm/mprotect.c:mprotect_fixup
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_pageout
  - mm/madvise.c:madvise_cold
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:migrate_to_node
  - mm/migrate.c:migrate_vma_setup
  - mm/memcontrol.c:mem_cgroup_move_charge
  - mm/memory-failure.c:kill_accessing_process
  - mm/hmm.c:hmm_range_fault
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:clear_refs_write
```
**Symbols:**

```
ffffffff812f5940-ffffffff812f5a57: walk_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int walk_page_range(struct mm_struct *mm, long unsigned int start, long unsigned int end, const struct mm_walk_ops *ops, void *private);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pagewalk.c (ffffffff81359830)
Location: mm/pagewalk.c:427
Inline: False
Direct callers:
  - mm/mincore.c:__do_sys_mincore
  - mm/mlock.c:mlock_fixup
  - mm/mlock.c:mlock_fixup
  - mm/mprotect.c:mprotect_fixup
  - mm/madvise.c:madvise_vma_behavior
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_pageout
  - mm/madvise.c:madvise_cold
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:migrate_to_node
  - mm/migrate_device.c:migrate_vma_setup
  - mm/memcontrol.c:mem_cgroup_move_charge
  - mm/memcontrol.c:mem_cgroup_can_attach
  - mm/memory-failure.c:kill_accessing_process
  - mm/hmm.c:hmm_range_fault
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:clear_refs_write
```
**Symbols:**

```
ffffffff81359830-ffffffff81359956: walk_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int walk_page_range(struct mm_struct *mm, long unsigned int start, long unsigned int end, const struct mm_walk_ops *ops, void *private);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pagewalk.c (ffffffff813d4120)
Location: mm/pagewalk.c:427
Inline: False
Direct callers:
  - mm/vmscan.c:walk_mm
  - mm/mincore.c:do_mincore
  - mm/mlock.c:mlock_fixup
  - mm/mlock.c:mlock_fixup
  - mm/mprotect.c:mprotect_fixup
  - mm/madvise.c:madvise_vma_behavior
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_pageout
  - mm/madvise.c:madvise_cold
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:migrate_to_node
  - mm/migrate_device.c:migrate_vma_setup
  - mm/memcontrol.c:mem_cgroup_move_charge
  - mm/memcontrol.c:mem_cgroup_can_attach
  - mm/memory-failure.c:kill_accessing_process
  - mm/hmm.c:hmm_range_fault
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:clear_refs_write
```
**Symbols:**

```
ffffffff813d4120-ffffffff813d42ac: walk_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int walk_page_range(struct mm_struct *mm, long unsigned int start, long unsigned int end, const struct mm_walk_ops *ops, void *private);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pagewalk.c (ffffffff81408b00)
Location: mm/pagewalk.c:470
Inline: False
Direct callers:
  - mm/vmscan.c:walk_mm
  - mm/mincore.c:do_mincore
  - mm/mlock.c:mlock_fixup
  - mm/mlock.c:mlock_fixup
  - mm/mprotect.c:mprotect_fixup
  - mm/madvise.c:madvise_vma_behavior
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_pageout
  - mm/madvise.c:madvise_cold
  - mm/mempolicy.c:migrate_to_node
  - mm/migrate_device.c:migrate_vma_setup
  - mm/memcontrol.c:mem_cgroup_move_charge
  - mm/memcontrol.c:mem_cgroup_can_attach
  - mm/memory-failure.c:kill_accessing_process
  - mm/hmm.c:hmm_range_fault
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:clear_refs_write
```
**Symbols:**

```
ffffffff81408b00-ffffffff81408cc1: walk_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int walk_page_range(struct mm_struct *mm, long unsigned int start, long unsigned int end, const struct mm_walk_ops *ops, void *private);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pagewalk.c (ffffffff81435220)
Location: mm/pagewalk.c:470
Inline: False
Direct callers:
  - mm/vmscan.c:walk_mm
  - mm/mincore.c:do_mincore
  - mm/mlock.c:mlock_fixup
  - mm/mlock.c:mlock_fixup
  - mm/mprotect.c:mprotect_fixup
  - mm/madvise.c:madvise_vma_behavior
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_pageout
  - mm/madvise.c:madvise_cold
  - mm/mempolicy.c:queue_pages_range
  - mm/migrate_device.c:migrate_vma_setup
  - mm/memcontrol.c:mem_cgroup_move_charge
  - mm/memcontrol.c:mem_cgroup_can_attach
  - mm/memory-failure.c:kill_accessing_process
  - mm/hmm.c:hmm_range_fault
  - fs/proc/task_mmu.c:do_pagemap_scan
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:clear_refs_write
```
**Symbols:**

```
ffffffff81435220-ffffffff814353e1: walk_page_range (STB_GLOBAL)
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
int walk_page_range(struct mm_struct *mm, long unsigned int start, long unsigned int end, const struct mm_walk_ops *ops, void *private);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pagewalk.c (ffff800010307c88)
Location: mm/pagewalk.c:301
Inline: False
Direct callers:
  - mm/mincore.c:__do_sys_mincore
  - mm/madvise.c:__arm64_sys_madvise
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_pageout
  - mm/madvise.c:madvise_cold
  - mm/mempolicy.c:kernel_mbind
  - mm/memcontrol.c:mem_cgroup_move_task
  - mm/hmm.c:hmm_range_fault
  - mm/hmm.c:hmm_range_fault
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:clear_refs_write
```
**Symbols:**

```
ffff800010307c88-ffff800010307db8: walk_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int walk_page_range(struct mm_struct *mm, long unsigned int start, long unsigned int end, const struct mm_walk_ops *ops, void *private);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pagewalk.c (c05251e4)
Location: mm/pagewalk.c:301
Inline: False
Direct callers:
  - mm/mincore.c:__se_sys_mincore
  - mm/madvise.c:__se_sys_madvise
  - mm/madvise.c:__se_sys_madvise
  - mm/madvise.c:madvise_free_single_vma
  - mm/memcontrol.c:mem_cgroup_move_task
  - mm/hmm.c:hmm_range_fault
  - mm/hmm.c:hmm_range_fault
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:clear_refs_write
```
**Symbols:**

```
c05251e4-c0525320: walk_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int walk_page_range(struct mm_struct *mm, long unsigned int start, long unsigned int end, const struct mm_walk_ops *ops, void *private);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pagewalk.c (c0000000003d6d50)
Location: mm/pagewalk.c:301
Inline: False
Direct callers:
  - mm/mincore.c:__se_sys_mincore
  - mm/madvise.c:__se_sys_madvise
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_pageout
  - mm/madvise.c:madvise_cold
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:migrate_to_node
  - mm/migrate.c:migrate_vma_setup
  - mm/memcontrol.c:mem_cgroup_move_task
  - mm/hmm.c:hmm_range_fault
  - mm/hmm.c:hmm_range_fault
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:clear_refs_write
```
**Symbols:**

```
c0000000003d6d50-c0000000003d6f14: walk_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int walk_page_range(struct mm_struct *mm, long unsigned int start, long unsigned int end, const struct mm_walk_ops *ops, void *private);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pagewalk.c (ffffffe000212bd8)
Location: mm/pagewalk.c:301
Inline: False
Direct callers:
  - mm/mincore.c:__se_sys_mincore
  - mm/madvise.c:__se_sys_madvise
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_pageout
  - mm/madvise.c:madvise_cold
  - mm/memcontrol.c:mem_cgroup_move_task
  - mm/hmm.c:hmm_range_fault
  - mm/hmm.c:hmm_range_fault
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:clear_refs_write
```
**Symbols:**

```
ffffffe000212bd8-ffffffe000212cac: walk_page_range (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int walk_page_range(struct mm_struct *mm, long unsigned int start, long unsigned int end, const struct mm_walk_ops *ops, void *private);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pagewalk.c (ffffffff8126aad0)
Location: mm/pagewalk.c:301
Inline: False
Direct callers:
  - mm/mincore.c:__ia32_sys_mincore
  - mm/mincore.c:__x64_sys_mincore
  - mm/mprotect.c:mprotect_fixup
  - mm/madvise.c:__do_sys_madvise
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_pageout
  - mm/madvise.c:madvise_cold
  - mm/mempolicy.c:kernel_mbind
  - mm/mempolicy.c:migrate_to_node
  - mm/migrate.c:migrate_vma_setup
  - mm/memcontrol.c:mem_cgroup_move_task
  - mm/hmm.c:hmm_range_fault
  - mm/hmm.c:hmm_range_fault
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:clear_refs_write
```
**Symbols:**

```
ffffffff8126aad0-ffffffff8126abd4: walk_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int walk_page_range(struct mm_struct *mm, long unsigned int start, long unsigned int end, const struct mm_walk_ops *ops, void *private);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pagewalk.c (ffffffff8125cc30)
Location: mm/pagewalk.c:301
Inline: False
Direct callers:
  - mm/mincore.c:__ia32_sys_mincore
  - mm/mincore.c:__x64_sys_mincore
  - mm/mprotect.c:mprotect_fixup
  - mm/madvise.c:__do_sys_madvise
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_pageout
  - mm/madvise.c:madvise_cold
  - mm/mempolicy.c:kernel_mbind
  - mm/mempolicy.c:migrate_to_node
  - mm/migrate.c:migrate_vma_setup
  - mm/memcontrol.c:mem_cgroup_move_task
  - mm/hmm.c:hmm_range_fault
  - mm/hmm.c:hmm_range_fault
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:clear_refs_write
```
**Symbols:**

```
ffffffff8125cc30-ffffffff8125cd34: walk_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int walk_page_range(struct mm_struct *mm, long unsigned int start, long unsigned int end, const struct mm_walk_ops *ops, void *private);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pagewalk.c (ffffffff81268870)
Location: mm/pagewalk.c:301
Inline: False
Direct callers:
  - mm/mincore.c:__ia32_sys_mincore
  - mm/mincore.c:__x64_sys_mincore
  - mm/mprotect.c:mprotect_fixup
  - mm/madvise.c:__do_sys_madvise
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_pageout
  - mm/madvise.c:madvise_cold
  - mm/mempolicy.c:kernel_mbind
  - mm/mempolicy.c:migrate_to_node
  - mm/migrate.c:migrate_vma_setup
  - mm/memcontrol.c:mem_cgroup_move_task
  - mm/hmm.c:hmm_range_fault
  - mm/hmm.c:hmm_range_fault
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:clear_refs_write
```
**Symbols:**

```
ffffffff81268870-ffffffff81268974: walk_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int walk_page_range(struct mm_struct *mm, long unsigned int start, long unsigned int end, const struct mm_walk_ops *ops, void *private);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pagewalk.c (ffffffff81278200)
Location: mm/pagewalk.c:301
Inline: False
Direct callers:
  - mm/mincore.c:__ia32_sys_mincore
  - mm/mincore.c:__x64_sys_mincore
  - mm/mprotect.c:mprotect_fixup
  - mm/madvise.c:__do_sys_madvise
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_pageout
  - mm/madvise.c:madvise_cold
  - mm/mempolicy.c:kernel_mbind
  - mm/mempolicy.c:migrate_to_node
  - mm/migrate.c:migrate_vma_setup
  - mm/memcontrol.c:mem_cgroup_move_task
  - mm/hmm.c:hmm_range_fault
  - mm/hmm.c:hmm_range_fault
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:clear_refs_write
```
**Symbols:**

```
ffffffff81278200-ffffffff81278304: walk_page_range (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.3</code> and <code>5.4</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct mm_struct *mm</code>
</li>
<li>
<b>Param added. </b>
<code>const struct mm_walk_ops *ops</code>
</li>
<li>
<b>Param added. </b>
<code>void *private</code>
</li>
<li>
<b>Param removed. </b>
<code>struct mm_walk *walk</code>
</li>
<li>
<b>Param reordered. </b>
<code>start, end, walk</code> ➡️ <code>mm, start, end, ops, private</code>
</li>
</ul>
</details>
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
