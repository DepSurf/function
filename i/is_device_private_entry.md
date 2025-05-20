# Function: <code>is_device_private_entry</code>

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
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8120c8af)
Location: include/linux/swapops.h:111
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:copy_pte_range
```
```
In mm/page_vma_mapped.c (ffffffff8121a605)
Location: include/linux/swapops.h:111
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/migrate.c (ffffffff8124b84d)
Location: include/linux/swapops.h:111
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/memcontrol.c (0)
Location: include/linux/swapops.h:111
Inline: True
```
```
In mm/hmm.c (0)
Location: include/linux/swapops.h:111
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff812ec8ad)
Location: include/linux/swapops.h:111
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
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
In mm/memory.c (ffffffff8122d80c)
Location: include/linux/swapops.h:111
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
```
In mm/page_vma_mapped.c (ffffffff8123c44a)
Location: include/linux/swapops.h:111
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/migrate.c (ffffffff8126e1e4)
Location: include/linux/swapops.h:111
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/memcontrol.c (0)
Location: include/linux/swapops.h:111
Inline: True
```
```
In mm/hmm.c (ffffffff812936d8)
Location: include/linux/swapops.h:111
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/proc/task_mmu.c (ffffffff8131a0cd)
Location: include/linux/swapops.h:111
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
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
In mm/memory.c (ffffffff81240dbc)
Location: include/linux/swapops.h:107
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
```
In mm/page_vma_mapped.c (ffffffff81250f6e)
Location: include/linux/swapops.h:107
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/migrate.c (ffffffff81283055)
Location: include/linux/swapops.h:107
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/memcontrol.c (0)
Location: include/linux/swapops.h:107
Inline: True
```
```
In mm/hmm.c (ffffffff812a7c94)
Location: include/linux/swapops.h:107
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/proc/task_mmu.c (ffffffff813311a0)
Location: include/linux/swapops.h:107
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
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
In mm/memory.c (ffffffff81253003)
Location: include/linux/swapops.h:107
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
```
In mm/page_vma_mapped.c (ffffffff8126320d)
Location: include/linux/swapops.h:107
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/memcontrol.c (0)
Location: include/linux/swapops.h:107
Inline: True
```
```
In mm/hmm.c (ffffffff812c43a6)
Location: include/linux/swapops.h:107
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff81358fa2)
Location: include/linux/swapops.h:107
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
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
In mm/memory.c (ffffffff81261563)
Location: include/linux/swapops.h:107
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
```
In mm/page_vma_mapped.c (ffffffff812719bd)
Location: include/linux/swapops.h:107
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/migrate.c (ffffffff812ae924)
Location: include/linux/swapops.h:107
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/memcontrol.c (0)
Location: include/linux/swapops.h:107
Inline: True
```
```
In mm/hmm.c (ffffffff812d5ce0)
Location: include/linux/swapops.h:107
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff813711f2)
Location: include/linux/swapops.h:107
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
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
In mm/memory.c (ffffffff8129192d)
Location: include/linux/swapops.h:109
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_one_pte
```
```
In mm/page_vma_mapped.c (ffffffff812a19e5)
Location: include/linux/swapops.h:109
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:map_pte
```
```
In mm/migrate.c (ffffffff812e4033)
Location: include/linux/swapops.h:109
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/memcontrol.c (0)
Location: include/linux/swapops.h:109
Inline: True
```
```
In mm/hmm.c (ffffffff8130affd)
Location: include/linux/swapops.h:109
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff813b7d93)
Location: include/linux/swapops.h:109
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:smaps_hugetlb_range
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
In mm/memory.c (ffffffff8129c231)
Location: include/linux/swapops.h:109
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:zap_pte_range
```
```
In mm/page_vma_mapped.c (ffffffff812ad2b3)
Location: include/linux/swapops.h:109
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:map_pte
```
```
In mm/migrate.c (ffffffff812efee9)
Location: include/linux/swapops.h:109
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/memcontrol.c (ffffffff8130184b)
Location: include/linux/swapops.h:109
Inline: True
```
```
In mm/hmm.c (ffffffff81316ecd)
Location: include/linux/swapops.h:109
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff813c9823)
Location: include/linux/swapops.h:109
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:smaps_hugetlb_range
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
In mm/memory.c (ffffffff812a14fb)
Location: include/linux/swapops.h:116
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:zap_pte_range
```
```
In mm/page_vma_mapped.c (ffffffff812b2c94)
Location: include/linux/swapops.h:116
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/migrate.c (ffffffff812f597a)
Location: include/linux/swapops.h:116
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/memcontrol.c (ffffffff8130803b)
Location: include/linux/swapops.h:116
Inline: True
```
```
In mm/hmm.c (ffffffff8131d101)
Location: include/linux/swapops.h:116
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff813d091b)
Location: include/linux/swapops.h:116
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:smaps_hugetlb_range
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
In mm/memory.c (ffffffff812e249c)
Location: include/linux/swapops.h:120
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_nonpresent_pte
```
```
In mm/page_vma_mapped.c (ffffffff812f4855)
Location: include/linux/swapops.h:120
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/migrate.c (ffffffff8133ff44)
Location: include/linux/swapops.h:120
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/memcontrol.c (ffffffff813521cb)
Location: include/linux/swapops.h:120
Inline: True
```
```
In mm/hmm.c (ffffffff8136a3f7)
Location: include/linux/swapops.h:120
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/swapops.h:120
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
In mm/memory.c (ffffffff81344214)
Location: include/linux/swapops.h:132
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_nonpresent_pte
```
```
In mm/page_vma_mapped.c (ffffffff813586b3)
Location: include/linux/swapops.h:132
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/migrate_device.c (ffffffff813b7232)
Location: include/linux/swapops.h:132
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/memcontrol.c (ffffffff813ce6d7)
Location: include/linux/swapops.h:132
Inline: True
```
```
In mm/hmm.c (ffffffff813e851b)
Location: include/linux/swapops.h:132
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff8149aed4)
Location: include/linux/swapops.h:132
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_hugetlb_range
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
In mm/memory.c (ffffffff813bc3a9)
Location: include/linux/swapops.h:178
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_nonpresent_pte
```
```
In mm/page_vma_mapped.c (ffffffff813d2e2b)
Location: include/linux/swapops.h:178
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/migrate_device.c (ffffffff81438c50)
Location: include/linux/swapops.h:178
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/memcontrol.c (ffffffff81450137)
Location: include/linux/swapops.h:178
Inline: True
```
```
In mm/hmm.c (ffffffff81470440)
Location: include/linux/swapops.h:178
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff8152eafa)
Location: include/linux/swapops.h:178
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:smaps_hugetlb_range
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
In mm/memory.c (ffffffff813f0de1)
Location: include/linux/swapops.h:178
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_nonpresent_pte
```
```
In mm/page_vma_mapped.c (ffffffff814074ab)
Location: include/linux/swapops.h:178
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:map_pte
```
```
In mm/migrate_device.c (ffffffff8146f4e1)
Location: include/linux/swapops.h:178
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/memcontrol.c (ffffffff81485b97)
Location: include/linux/swapops.h:178
Inline: True
```
```
In mm/hmm.c (ffffffff814a4c10)
Location: include/linux/swapops.h:178
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_handle_pte
```
```
In fs/proc/task_mmu.c (ffffffff81567f8d)
Location: include/linux/swapops.h:178
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:smaps_hugetlb_range
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
In mm/memory.c (ffffffff8142061a)
Location: include/linux/swapops.h:178
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_nonpresent_pte
```
```
In mm/page_vma_mapped.c (ffffffff81433b1b)
Location: include/linux/swapops.h:178
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:map_pte
```
```
In mm/migrate_device.c (ffffffff8149dfea)
Location: include/linux/swapops.h:178
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/memcontrol.c (ffffffff814b4547)
Location: include/linux/swapops.h:178
Inline: True
```
```
In mm/hmm.c (ffffffff814d5c3d)
Location: include/linux/swapops.h:178
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_handle_pte
```
```
In fs/proc/task_mmu.c (ffffffff8159ee4f)
Location: include/linux/swapops.h:178
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_thp_category
  - fs/proc/task_mmu.c:pagemap_page_category
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:smaps_hugetlb_range
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
In mm/memory.c (0)
Location: include/linux/swapops.h:142
Inline: True
```
```
In mm/page_vma_mapped.c (0)
Location: include/linux/swapops.h:142
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/swapops.h:142
Inline: True
```
```
In mm/hmm.c (0)
Location: include/linux/swapops.h:142
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/swapops.h:142
Inline: True
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
In mm/memory.c (0)
Location: include/linux/swapops.h:142
Inline: True
```
```
In mm/page_vma_mapped.c (0)
Location: include/linux/swapops.h:142
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/swapops.h:142
Inline: True
```
```
In mm/hmm.c (0)
Location: include/linux/swapops.h:142
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/swapops.h:142
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
In mm/memory.c (c0000000003c1df0)
Location: include/linux/swapops.h:107
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
```
```
In mm/page_vma_mapped.c (c0000000003d6004)
Location: include/linux/swapops.h:107
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/migrate.c (c0000000004344ec)
Location: include/linux/swapops.h:107
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/memcontrol.c (0)
Location: include/linux/swapops.h:107
Inline: True
```
```
In mm/hmm.c (c00000000046feec)
Location: include/linux/swapops.h:107
Inline: True
```
```
In fs/proc/task_mmu.c (c00000000054d9d0)
Location: include/linux/swapops.h:107
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_hugetlb_range
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
In mm/memory.c (0)
Location: include/linux/swapops.h:142
Inline: True
```
```
In mm/page_vma_mapped.c (0)
Location: include/linux/swapops.h:142
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/swapops.h:142
Inline: True
```
```
In mm/hmm.c (0)
Location: include/linux/swapops.h:142
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/swapops.h:142
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
In mm/memory.c (ffffffff81259bb3)
Location: include/linux/swapops.h:107
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
```
In mm/page_vma_mapped.c (ffffffff8126a00d)
Location: include/linux/swapops.h:107
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/migrate.c (ffffffff812a6f04)
Location: include/linux/swapops.h:107
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/memcontrol.c (0)
Location: include/linux/swapops.h:107
Inline: True
```
```
In mm/hmm.c (ffffffff812ce2c0)
Location: include/linux/swapops.h:107
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff813697d2)
Location: include/linux/swapops.h:107
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
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
In mm/memory.c (ffffffff8124bfb8)
Location: include/linux/swapops.h:107
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
```
```
In mm/page_vma_mapped.c (ffffffff8125c1bb)
Location: include/linux/swapops.h:107
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/migrate.c (ffffffff81298941)
Location: include/linux/swapops.h:107
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/memcontrol.c (0)
Location: include/linux/swapops.h:107
Inline: True
```
```
In mm/hmm.c (ffffffff812bf138)
Location: include/linux/swapops.h:107
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff8135965b)
Location: include/linux/swapops.h:107
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
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
In mm/memory.c (ffffffff81257953)
Location: include/linux/swapops.h:107
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
```
In mm/page_vma_mapped.c (ffffffff81267dad)
Location: include/linux/swapops.h:107
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/migrate.c (ffffffff812a4d14)
Location: include/linux/swapops.h:107
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/memcontrol.c (0)
Location: include/linux/swapops.h:107
Inline: True
```
```
In mm/hmm.c (ffffffff812cc0d0)
Location: include/linux/swapops.h:107
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff813672a2)
Location: include/linux/swapops.h:107
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
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
In mm/memory.c (ffffffff81267340)
Location: include/linux/swapops.h:107
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
```
In mm/page_vma_mapped.c (ffffffff81277770)
Location: include/linux/swapops.h:107
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/migrate.c (ffffffff812b5870)
Location: include/linux/swapops.h:107
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/memcontrol.c (0)
Location: include/linux/swapops.h:107
Inline: True
```
```
In mm/hmm.c (ffffffff812dce10)
Location: include/linux/swapops.h:107
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff8137a8f1)
Location: include/linux/swapops.h:107
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
```
</details>
</li>
</ul>

## Differences
