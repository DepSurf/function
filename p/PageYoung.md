# Function: <code>PageYoung</code>

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
In mm/migrate.c (ffffffff811f1c8a)
Location: include/linux/page-flags.h:292
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
```
```
In mm/huge_memory.c (ffffffff811f4cd3)
Location: include/linux/page-flags.h:292
Inline: True
Inline callers:
  - mm/huge_memory.c:khugepaged
  - mm/huge_memory.c:khugepaged
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In fs/proc/task_mmu.c (ffffffff8127693a)
Location: include/linux/page-flags.h:292
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_account
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
In mm/migrate.c (ffffffff812106c9)
Location: include/linux/page-flags.h:351
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
```
```
In mm/huge_memory.c (ffffffff81217cbb)
Location: include/linux/page-flags.h:351
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/khugepaged.c (ffffffff8121c048)
Location: include/linux/page-flags.h:351
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/proc/task_mmu.c (ffffffff812a4538)
Location: include/linux/page-flags.h:351
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_account
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
In mm/migrate.c (ffffffff81222816)
Location: include/linux/page-flags.h:367
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
```
```
In mm/huge_memory.c (ffffffff8122a279)
Location: include/linux/page-flags.h:367
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/khugepaged.c (ffffffff8122e71f)
Location: include/linux/page-flags.h:367
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
```
```
In fs/proc/task_mmu.c (ffffffff812b9e98)
Location: include/linux/page-flags.h:367
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_account
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
In mm/migrate.c (ffffffff8122e2a4)
Location: include/linux/page-flags.h:370
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
```
```
In mm/huge_memory.c (ffffffff81235e79)
Location: include/linux/page-flags.h:370
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/khugepaged.c (ffffffff8123a211)
Location: include/linux/page-flags.h:370
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/proc/task_mmu.c (ffffffff812c75ab)
Location: include/linux/page-flags.h:370
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_account
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
In mm/migrate.c (ffffffff81249378)
Location: include/linux/page-flags.h:371
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In mm/huge_memory.c (ffffffff81254bd3)
Location: include/linux/page-flags.h:371
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/khugepaged.c (ffffffff81259885)
Location: include/linux/page-flags.h:371
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
```
```
In fs/proc/task_mmu.c (ffffffff812eae8c)
Location: include/linux/page-flags.h:371
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_account
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
In mm/migrate.c (ffffffff8126cdf9)
Location: include/linux/page-flags.h:378
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In mm/huge_memory.c (ffffffff81278a33)
Location: include/linux/page-flags.h:378
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/khugepaged.c (ffffffff8127d1da)
Location: include/linux/page-flags.h:378
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/proc/task_mmu.c (ffffffff813184ef)
Location: include/linux/page-flags.h:378
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_account
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
In mm/migrate.c (ffffffff81281625)
Location: include/linux/page-flags.h:395
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In mm/huge_memory.c (ffffffff8128d0e2)
Location: include/linux/page-flags.h:395
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/khugepaged.c (ffffffff81291d53)
Location: include/linux/page-flags.h:395
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/proc/task_mmu.c (ffffffff8132f3c3)
Location: include/linux/page-flags.h:395
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_account
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
In mm/migrate.c (ffffffff8129d8b7)
Location: include/linux/page-flags.h:428
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In mm/huge_memory.c (ffffffff812a23c4)
Location: include/linux/page-flags.h:428
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
```
```
In mm/khugepaged.c (ffffffff812ac13a)
Location: include/linux/page-flags.h:428
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In fs/proc/task_mmu.c (ffffffff81356f84)
Location: include/linux/page-flags.h:428
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_account
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
In mm/migrate.c (ffffffff812ad1d5)
Location: include/linux/page-flags.h:428
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In mm/huge_memory.c (ffffffff812b38c2)
Location: include/linux/page-flags.h:428
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
```
```
In mm/khugepaged.c (ffffffff812bd94a)
Location: include/linux/page-flags.h:428
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In fs/proc/task_mmu.c (ffffffff8136f55c)
Location: include/linux/page-flags.h:428
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_account
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
In mm/migrate.c (ffffffff812e2d13)
Location: include/linux/page-flags.h:436
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In mm/huge_memory.c (ffffffff812e8909)
Location: include/linux/page-flags.h:436
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page_tail
```
```
In mm/khugepaged.c (ffffffff812f30ba)
Location: include/linux/page-flags.h:436
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In fs/proc/task_mmu.c (ffffffff813b6c23)
Location: include/linux/page-flags.h:436
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_account
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
In mm/migrate.c (ffffffff812ee143)
Location: include/linux/page-flags.h:440
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In mm/huge_memory.c (ffffffff812f3d23)
Location: include/linux/page-flags.h:440
Inline: True
```
```
In mm/khugepaged.c (ffffffff812fd6f5)
Location: include/linux/page-flags.h:440
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In fs/proc/task_mmu.c (ffffffff813c82b4)
Location: include/linux/page-flags.h:440
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_account
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
In mm/migrate.c (ffffffff812f3c33)
Location: include/linux/page-flags.h:440
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In mm/huge_memory.c (ffffffff812fa183)
Location: include/linux/page-flags.h:440
Inline: True
```
```
In mm/khugepaged.c (ffffffff8130445a)
Location: include/linux/page-flags.h:440
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In fs/proc/task_mmu.c (ffffffff813cf3f8)
Location: include/linux/page-flags.h:440
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_account
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
In mm/migrate.c (ffffffff8133e5d3)
Location: include/linux/page-flags.h:454
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In mm/huge_memory.c (ffffffff81343ea3)
Location: include/linux/page-flags.h:454
Inline: True
```
```
In mm/khugepaged.c (ffffffff8134e18a)
Location: include/linux/page-flags.h:454
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In fs/proc/task_mmu.c (ffffffff814207cd)
Location: include/linux/page-flags.h:454
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_account
```
</details>
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
In mm/migrate.c (ffff80001034f4f0)
Location: include/linux/page-flags.h:428
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In mm/huge_memory.c (ffff800010354954)
Location: include/linux/page-flags.h:428
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
```
```
In mm/khugepaged.c (ffff80001035ecc4)
Location: include/linux/page-flags.h:428
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In fs/proc/task_mmu.c (ffff800010438b20)
Location: include/linux/page-flags.h:428
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_account
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/migrate.c (c000000000431940)
Location: include/linux/page-flags.h:428
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In mm/huge_memory.c (c00000000043b964)
Location: include/linux/page-flags.h:428
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
```
```
In mm/khugepaged.c (c000000000448104)
Location: include/linux/page-flags.h:428
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In fs/proc/task_mmu.c (c00000000054c334)
Location: include/linux/page-flags.h:428
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_account
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
In mm/migrate.c (ffffffe00023e4f4)
Location: include/linux/page-flags.h:428
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In fs/proc/task_mmu.c (ffffffe0002d3276)
Location: include/linux/page-flags.h:428
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
In mm/migrate.c (ffffffff812a57b5)
Location: include/linux/page-flags.h:428
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In mm/huge_memory.c (ffffffff812abea2)
Location: include/linux/page-flags.h:428
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
```
```
In mm/khugepaged.c (ffffffff812b5f2a)
Location: include/linux/page-flags.h:428
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In fs/proc/task_mmu.c (ffffffff81367b3c)
Location: include/linux/page-flags.h:428
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_account
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
In mm/migrate.c (ffffffff81297285)
Location: include/linux/page-flags.h:428
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In mm/huge_memory.c (ffffffff8129da12)
Location: include/linux/page-flags.h:428
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
```
```
In mm/khugepaged.c (ffffffff812a70ec)
Location: include/linux/page-flags.h:428
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In fs/proc/task_mmu.c (ffffffff813587dc)
Location: include/linux/page-flags.h:428
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_account
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
In mm/migrate.c (ffffffff812a35c5)
Location: include/linux/page-flags.h:428
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In mm/huge_memory.c (ffffffff812a9cb2)
Location: include/linux/page-flags.h:428
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
```
```
In mm/khugepaged.c (ffffffff812b3d3a)
Location: include/linux/page-flags.h:428
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In fs/proc/task_mmu.c (ffffffff8136560c)
Location: include/linux/page-flags.h:428
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_account
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
In mm/migrate.c (ffffffff812b3dd5)
Location: include/linux/page-flags.h:428
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In mm/huge_memory.c (ffffffff812b9f32)
Location: include/linux/page-flags.h:428
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
```
```
In mm/khugepaged.c (ffffffff812c41b9)
Location: include/linux/page-flags.h:428
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In fs/proc/task_mmu.c (ffffffff81378cec)
Location: include/linux/page-flags.h:428
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_account
```
</details>
</li>
</ul>

## Differences
