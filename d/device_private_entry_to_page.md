# Function: <code>device_private_entry_to_page</code>

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
In kernel/memremap.c (ffffffff811c89e5)
Location: include/linux/swapops.h:132
Inline: True
Inline callers:
  - kernel/memremap.c:device_private_entry_fault
```
```
In mm/memory.c (ffffffff8120a85e)
Location: include/linux/swapops.h:132
Inline: True
Inline callers:
  - mm/memory.c:copy_pte_range
```
```
In mm/migrate.c (ffffffff8124b860)
Location: include/linux/swapops.h:132
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/memcontrol.c (0)
Location: include/linux/swapops.h:132
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff812eb773)
Location: include/linux/swapops.h:132
Inline: True
Inline callers:
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
In kernel/memremap.c (ffffffff811e91e5)
Location: include/linux/swapops.h:132
Inline: True
Inline callers:
  - kernel/memremap.c:device_private_entry_fault
```
```
In mm/memory.c (ffffffff8122b675)
Location: include/linux/swapops.h:132
Inline: True
```
```
In mm/migrate.c (ffffffff8126e1f3)
Location: include/linux/swapops.h:132
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/memcontrol.c (0)
Location: include/linux/swapops.h:132
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff81318ad6)
Location: include/linux/swapops.h:132
Inline: True
Inline callers:
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
In kernel/memremap.c (ffffffff811f9ef5)
Location: include/linux/swapops.h:128
Inline: True
Inline callers:
  - kernel/memremap.c:device_private_entry_fault
```
```
In mm/memory.c (ffffffff8123ea4a)
Location: include/linux/swapops.h:128
Inline: True
```
```
In mm/migrate.c (ffffffff81283064)
Location: include/linux/swapops.h:128
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/memcontrol.c (0)
Location: include/linux/swapops.h:128
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff8132fba9)
Location: include/linux/swapops.h:128
Inline: True
Inline callers:
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
In mm/memory.c (ffffffff812530c5)
Location: include/linux/swapops.h:128
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
```
In mm/memcontrol.c (0)
Location: include/linux/swapops.h:128
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff813579f9)
Location: include/linux/swapops.h:128
Inline: True
Inline callers:
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
In mm/memory.c (ffffffff81261625)
Location: include/linux/swapops.h:128
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
```
In mm/migrate.c (ffffffff812ae934)
Location: include/linux/swapops.h:128
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/memcontrol.c (0)
Location: include/linux/swapops.h:128
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff8136fc29)
Location: include/linux/swapops.h:128
Inline: True
Inline callers:
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
In mm/memory.c (ffffffff8129198f)
Location: include/linux/swapops.h:130
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_one_pte
```
```
In mm/migrate.c (ffffffff812e4043)
Location: include/linux/swapops.h:130
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/memcontrol.c (0)
Location: include/linux/swapops.h:130
Inline: True
```
```
In mm/hmm.c (ffffffff8130b06d)
Location: include/linux/swapops.h:130
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff813b7b51)
Location: include/linux/swapops.h:130
Inline: True
Inline callers:
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
In mm/memory.c (ffffffff8129c293)
Location: include/linux/swapops.h:130
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:zap_pte_range
```
```
In mm/migrate.c (ffffffff812efef5)
Location: include/linux/swapops.h:130
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/memcontrol.c (ffffffff813018a6)
Location: include/linux/swapops.h:130
Inline: True
```
```
In mm/hmm.c (ffffffff81316f3d)
Location: include/linux/swapops.h:130
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff813c95e1)
Location: include/linux/swapops.h:130
Inline: True
Inline callers:
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
In mm/memory.c (ffffffff812a1558)
Location: include/linux/swapops.h:137
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:zap_pte_range
```
```
In mm/migrate.c (ffffffff812f598a)
Location: include/linux/swapops.h:137
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/memcontrol.c (ffffffff8130809a)
Location: include/linux/swapops.h:137
Inline: True
```
```
In mm/hmm.c (ffffffff8131d173)
Location: include/linux/swapops.h:137
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff813d06e1)
Location: include/linux/swapops.h:137
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_hugetlb_range
```
</details>
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
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (0)
Location: include/linux/swapops.h:157
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/swapops.h:157
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/swapops.h:157
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
Location: include/linux/swapops.h:157
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/swapops.h:157
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/swapops.h:157
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
In mm/memory.c (c0000000003c1eb0)
Location: include/linux/swapops.h:128
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
```
```
In mm/migrate.c (c0000000004344f8)
Location: include/linux/swapops.h:128
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/memcontrol.c (0)
Location: include/linux/swapops.h:128
Inline: True
```
```
In fs/proc/task_mmu.c (c00000000054d9dc)
Location: include/linux/swapops.h:128
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
Location: include/linux/swapops.h:157
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/swapops.h:157
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/swapops.h:157
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
In mm/memory.c (ffffffff81259c75)
Location: include/linux/swapops.h:128
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
```
In mm/migrate.c (ffffffff812a6f14)
Location: include/linux/swapops.h:128
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/memcontrol.c (0)
Location: include/linux/swapops.h:128
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff81368209)
Location: include/linux/swapops.h:128
Inline: True
Inline callers:
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
In mm/memory.c (ffffffff8124c0a3)
Location: include/linux/swapops.h:128
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
```
```
In mm/migrate.c (ffffffff81298951)
Location: include/linux/swapops.h:128
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/memcontrol.c (0)
Location: include/linux/swapops.h:128
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff8135903f)
Location: include/linux/swapops.h:128
Inline: True
Inline callers:
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
In mm/memory.c (ffffffff81257a15)
Location: include/linux/swapops.h:128
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
```
In mm/migrate.c (ffffffff812a4d24)
Location: include/linux/swapops.h:128
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/memcontrol.c (0)
Location: include/linux/swapops.h:128
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff81365cd9)
Location: include/linux/swapops.h:128
Inline: True
Inline callers:
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
In mm/memory.c (ffffffff812673fe)
Location: include/linux/swapops.h:128
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
```
In mm/migrate.c (ffffffff812b5880)
Location: include/linux/swapops.h:128
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/memcontrol.c (0)
Location: include/linux/swapops.h:128
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff81379369)
Location: include/linux/swapops.h:128
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_hugetlb_range
```
</details>
</li>
</ul>

## Differences
