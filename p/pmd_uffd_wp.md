# Function: <code>pmd_uffd_wp</code>

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
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81294d90)
Location: arch/x86/include/asm/pgtable.h:415
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/huge_memory.c (ffffffff812e9eed)
Location: arch/x86/include/asm/pgtable.h:415
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
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
In mm/memory.c (ffffffff8129f609)
Location: arch/x86/include/asm/pgtable.h:414
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/huge_memory.c (ffffffff812f50cd)
Location: arch/x86/include/asm/pgtable.h:414
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
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
In mm/memory.c (ffffffff812a460d)
Location: arch/x86/include/asm/pgtable.h:414
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/huge_memory.c (ffffffff812fb655)
Location: arch/x86/include/asm/pgtable.h:414
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
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
In mm/memory.c (ffffffff812e58df)
Location: arch/x86/include/asm/pgtable.h:385
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/huge_memory.c (ffffffff81345481)
Location: arch/x86/include/asm/pgtable.h:385
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In fs/proc/task_mmu.c (0)
Location: arch/x86/include/asm/pgtable.h:385
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
In mm/memory.c (ffffffff81347bfa)
Location: arch/x86/include/asm/pgtable.h:388
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/huge_memory.c (ffffffff813bb455)
Location: arch/x86/include/asm/pgtable.h:388
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:follow_trans_huge_pmd
```
```
In fs/proc/task_mmu.c (0)
Location: arch/x86/include/asm/pgtable.h:388
Inline: True
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
In mm/memory.c (ffffffff813bffdb)
Location: arch/x86/include/asm/pgtable.h:405
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/huge_memory.c (ffffffff8143d869)
Location: arch/x86/include/asm/pgtable.h:405
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:can_change_pmd_writable
```
```
In fs/proc/task_mmu.c (0)
Location: arch/x86/include/asm/pgtable.h:405
Inline: True
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
In mm/memory.c (ffffffff813f4c91)
Location: arch/x86/include/asm/pgtable.h:411
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/huge_memory.c (ffffffff81472f42)
Location: arch/x86/include/asm/pgtable.h:411
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_zero_page_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:can_change_pmd_writable
```
```
In fs/proc/task_mmu.c (ffffffff81567d4e)
Location: arch/x86/include/asm/pgtable.h:411
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
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
In mm/memory.c (ffffffff814212fa)
Location: arch/x86/include/asm/pgtable.h:539
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/huge_memory.c (ffffffff814a1696)
Location: arch/x86/include/asm/pgtable.h:539
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_zero_page_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:can_change_pmd_writable
```
```
In fs/proc/task_mmu.c (ffffffff8159ecca)
Location: arch/x86/include/asm/pgtable.h:539
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_thp_category
  - fs/proc/task_mmu.c:pagemap_pmd_range
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
