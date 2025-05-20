# Function: <code>vma_is_accessible</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (0)
Location: mm/memory.c:3458
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (0)
Location: mm/memory.c:3498
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (0)
Location: mm/memory.c:3699
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (0)
Location: mm/memory.c:3869
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81230132)
Location: mm/memory.c:3914
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:handle_pte_fault
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81241e5d)
Location: mm/memory.c:3704
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81254827)
Location: mm/memory.c:3753
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81262d87)
Location: mm/memory.c:3778
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
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
In arch/x86/mm/fault.c (ffffffff81087b7c)
Location: include/linux/mm.h:647
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
```
```
In kernel/sched/fair.c (ffffffff810e9a4a)
Location: include/linux/mm.h:647
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_work
```
```
In mm/gup.c (ffffffff8128b6d4)
Location: include/linux/mm.h:647
Inline: True
Inline callers:
  - mm/gup.c:populate_vma_page_range
```
```
In mm/memory.c (ffffffff81294b3e)
Location: include/linux/mm.h:647
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:handle_pte_fault
```
```
In mm/mmap.c (ffffffff8129a95c)
Location: include/linux/mm.h:647
Inline: True
Inline callers:
  - mm/mmap.c:expand_downwards
```
```
In mm/mempolicy.c (ffffffff812ce88c)
Location: include/linux/mm.h:647
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_test_walk
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
In arch/x86/mm/fault.c (ffffffff81088286)
Location: include/linux/mm.h:680
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
```
```
In kernel/sched/fair.c (ffffffff810e788f)
Location: include/linux/mm.h:680
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_work
```
```
In mm/gup.c (ffffffff81295548)
Location: include/linux/mm.h:680
Inline: True
Inline callers:
  - mm/gup.c:populate_vma_page_range
```
```
In mm/memory.c (ffffffff8129f3be)
Location: include/linux/mm.h:680
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:handle_pte_fault
```
```
In mm/mmap.c (ffffffff812a5b2c)
Location: include/linux/mm.h:680
Inline: True
Inline callers:
  - mm/mmap.c:expand_downwards
```
```
In mm/mempolicy.c (ffffffff812da1cc)
Location: include/linux/mm.h:680
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_test_walk
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
In arch/x86/mm/fault.c (ffffffff81088db1)
Location: include/linux/mm.h:703
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
```
```
In kernel/sched/fair.c (ffffffff810e975c)
Location: include/linux/mm.h:703
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_work
```
```
In mm/gup.c (ffffffff8129aea8)
Location: include/linux/mm.h:703
Inline: True
Inline callers:
  - mm/gup.c:populate_vma_page_range
```
```
In mm/memory.c (ffffffff812a444f)
Location: include/linux/mm.h:703
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:handle_pte_fault
```
```
In mm/mmap.c (ffffffff812ac268)
Location: include/linux/mm.h:703
Inline: True
Inline callers:
  - mm/mmap.c:expand_downwards
```
```
In mm/mempolicy.c (ffffffff812e1a2c)
Location: include/linux/mm.h:703
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_test_walk
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
In arch/x86/mm/fault.c (ffffffff810981df)
Location: include/linux/mm.h:704
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
```
```
In kernel/sched/fair.c (ffffffff81100fec)
Location: include/linux/mm.h:704
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_work
```
```
In mm/gup.c (ffffffff812db8a8)
Location: include/linux/mm.h:704
Inline: True
Inline callers:
  - mm/gup.c:populate_vma_page_range
```
```
In mm/memory.c (ffffffff812e57a0)
Location: include/linux/mm.h:704
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:handle_pte_fault
```
```
In mm/mmap.c (ffffffff812ed9b8)
Location: include/linux/mm.h:704
Inline: True
Inline callers:
  - mm/mmap.c:expand_downwards
```
```
In mm/mempolicy.c (ffffffff81328afc)
Location: include/linux/mm.h:704
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_test_walk
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
In arch/x86/mm/fault.c (ffffffff810aae44)
Location: include/linux/mm.h:656
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
```
```
In kernel/sched/fair.c (ffffffff8111c718)
Location: include/linux/mm.h:656
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_work
```
```
In mm/gup.c (ffffffff8133b642)
Location: include/linux/mm.h:656
Inline: True
Inline callers:
  - mm/gup.c:populate_vma_page_range
```
```
In mm/memory.c (ffffffff81347960)
Location: include/linux/mm.h:656
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:handle_pte_fault
```
```
In mm/mmap.c (ffffffff81350d73)
Location: include/linux/mm.h:656
Inline: True
Inline callers:
  - mm/mmap.c:expand_downwards
```
```
In mm/mempolicy.c (ffffffff81397d69)
Location: include/linux/mm.h:656
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_test_walk
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
In arch/x86/mm/fault.c (ffffffff810c4b27)
Location: include/linux/mm.h:666
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
```
```
In kernel/sched/fair.c (ffffffff811442eb)
Location: include/linux/mm.h:666
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_work
```
```
In mm/vmscan.c (ffffffff81377494)
Location: include/linux/mm.h:666
Inline: True
Inline callers:
  - mm/vmscan.c:should_skip_vma
```
```
In mm/gup.c (ffffffff813b31e2)
Location: include/linux/mm.h:666
Inline: True
Inline callers:
  - mm/gup.c:populate_vma_page_range
```
```
In mm/memory.c (ffffffff813bfcee)
Location: include/linux/mm.h:666
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:handle_pte_fault
```
```
In mm/mmap.c (ffffffff813cb246)
Location: include/linux/mm.h:666
Inline: True
Inline callers:
  - mm/mmap.c:expand_downwards
```
```
In mm/mempolicy.c (ffffffff814179b1)
Location: include/linux/mm.h:666
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_test_walk
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
In arch/x86/mm/fault.c (ffffffff810c6c62)
Location: include/linux/mm.h:867
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:access_error
```
```
In kernel/sched/fair.c (ffffffff81154968)
Location: include/linux/mm.h:867
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_work
```
```
In mm/vmscan.c (ffffffff813a9364)
Location: include/linux/mm.h:867
Inline: True
Inline callers:
  - mm/vmscan.c:should_skip_vma
```
```
In mm/gup.c (ffffffff813e7fa6)
Location: include/linux/mm.h:867
Inline: True
Inline callers:
  - mm/gup.c:populate_vma_page_range
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff813f49b5)
Location: include/linux/mm.h:867
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:handle_pte_fault
```
```
In mm/mmap.c (ffffffff813ff95d)
Location: include/linux/mm.h:867
Inline: True
Inline callers:
  - mm/mmap.c:expand_downwards
```
```
In mm/mempolicy.c (ffffffff8144af3e)
Location: include/linux/mm.h:867
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_test_walk
```
```
In mm/huge_memory.c (ffffffff81474a0e)
Location: include/linux/mm.h:867
Inline: True
Inline callers:
  - mm/huge_memory.c:follow_trans_huge_pmd
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
In arch/x86/mm/fault.c (ffffffff810cf12d)
Location: include/linux/mm.h:933
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:access_error
```
```
In kernel/sched/fair.c (ffffffff811697ed)
Location: include/linux/mm.h:933
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_work
```
```
In mm/vmscan.c (ffffffff813d2d64)
Location: include/linux/mm.h:933
Inline: True
Inline callers:
  - mm/vmscan.c:should_skip_vma
```
```
In mm/gup.c (ffffffff81412c16)
Location: include/linux/mm.h:933
Inline: True
Inline callers:
  - mm/gup.c:populate_vma_page_range
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff81420fed)
Location: include/linux/mm.h:933
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:handle_pte_fault
```
```
In mm/mmap.c (ffffffff8142bdc8)
Location: include/linux/mm.h:933
Inline: True
Inline callers:
  - mm/mmap.c:expand_downwards
```
```
In mm/huge_memory.c (ffffffff814a3fae)
Location: include/linux/mm.h:933
Inline: True
Inline callers:
  - mm/huge_memory.c:follow_trans_huge_pmd
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffff8000102f9e04)
Location: mm/memory.c:3778
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (0)
Location: mm/memory.c:3778
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (c0000000003c3fd0)
Location: mm/memory.c:3778
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (0)
Location: mm/memory.c:3778
Inline: True
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8125b3d7)
Location: mm/memory.c:3778
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8124d8c2)
Location: mm/memory.c:3778
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81259177)
Location: mm/memory.c:3778
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81268b77)
Location: mm/memory.c:3778
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
```
</details>
</li>
</ul>

## Differences
