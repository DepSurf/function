# Function: <code>PageReferenced</code>

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
In mm/swap.c (ffffffff8119de1e)
Location: include/linux/page-flags.h:211
Inline: True
Inline callers:
  - mm/swap.c:mark_page_accessed
  - mm/swap.c:mark_page_accessed
```
```
In mm/migrate.c (ffffffff811f1c29)
Location: include/linux/page-flags.h:211
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
```
```
In mm/huge_memory.c (ffffffff811f4cdd)
Location: include/linux/page-flags.h:211
Inline: True
Inline callers:
  - mm/huge_memory.c:khugepaged
  - mm/huge_memory.c:khugepaged
```
```
In fs/proc/task_mmu.c (ffffffff8127697e)
Location: include/linux/page-flags.h:211
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
In mm/swap.c (ffffffff811b35ae)
Location: include/linux/page-flags.h:257
Inline: True
Inline callers:
  - mm/swap.c:mark_page_accessed
  - mm/swap.c:mark_page_accessed
```
```
In mm/migrate.c (ffffffff812105ee)
Location: include/linux/page-flags.h:257
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
```
```
In mm/huge_memory.c (ffffffff81215fc9)
Location: include/linux/page-flags.h:257
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
```
```
In mm/khugepaged.c (ffffffff8121c057)
Location: include/linux/page-flags.h:257
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/proc/task_mmu.c (ffffffff812a463c)
Location: include/linux/page-flags.h:257
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
In mm/swap.c (ffffffff811c3c2e)
Location: include/linux/page-flags.h:267
Inline: True
Inline callers:
  - mm/swap.c:mark_page_accessed
  - mm/swap.c:mark_page_accessed
```
```
In mm/migrate.c (ffffffff8122272b)
Location: include/linux/page-flags.h:267
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
```
```
In mm/huge_memory.c (ffffffff8122858e)
Location: include/linux/page-flags.h:267
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
```
```
In mm/khugepaged.c (ffffffff8122e72e)
Location: include/linux/page-flags.h:267
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
```
```
In fs/proc/task_mmu.c (ffffffff812b9f9c)
Location: include/linux/page-flags.h:267
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
In mm/swap.c (ffffffff811cbfde)
Location: include/linux/page-flags.h:267
Inline: True
Inline callers:
  - mm/swap.c:mark_page_accessed
  - mm/swap.c:mark_page_accessed
```
```
In mm/migrate.c (ffffffff8122e1c9)
Location: include/linux/page-flags.h:267
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
```
```
In mm/huge_memory.c (ffffffff81231ccd)
Location: include/linux/page-flags.h:267
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/khugepaged.c (ffffffff8123a21f)
Location: include/linux/page-flags.h:267
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/proc/task_mmu.c (ffffffff812c76c6)
Location: include/linux/page-flags.h:267
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
In mm/swap.c (ffffffff811e0fce)
Location: include/linux/page-flags.h:268
Inline: True
Inline callers:
  - mm/swap.c:mark_page_accessed
  - mm/swap.c:mark_page_accessed
```
```
In mm/migrate.c (ffffffff8124929d)
Location: include/linux/page-flags.h:268
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In mm/huge_memory.c (ffffffff8125291a)
Location: include/linux/page-flags.h:268
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
```
```
In mm/khugepaged.c (ffffffff81259890)
Location: include/linux/page-flags.h:268
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
```
```
In fs/proc/task_mmu.c (ffffffff812eafa7)
Location: include/linux/page-flags.h:268
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
In mm/swap.c (ffffffff8120285e)
Location: include/linux/page-flags.h:275
Inline: True
Inline callers:
  - mm/swap.c:mark_page_accessed
  - mm/swap.c:mark_page_accessed
```
```
In mm/migrate.c (ffffffff8126cd1d)
Location: include/linux/page-flags.h:275
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In mm/huge_memory.c (ffffffff81276d63)
Location: include/linux/page-flags.h:275
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
```
```
In mm/khugepaged.c (ffffffff8127d702)
Location: include/linux/page-flags.h:275
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/proc/task_mmu.c (ffffffff813185fe)
Location: include/linux/page-flags.h:275
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
In mm/swap.c (ffffffff812151de)
Location: include/linux/page-flags.h:284
Inline: True
Inline callers:
  - mm/swap.c:mark_page_accessed
  - mm/swap.c:mark_page_accessed
```
```
In mm/migrate.c (ffffffff8128151f)
Location: include/linux/page-flags.h:284
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In mm/huge_memory.c (ffffffff812885f9)
Location: include/linux/page-flags.h:284
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/khugepaged.c (ffffffff81291d5d)
Location: include/linux/page-flags.h:284
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/proc/task_mmu.c (ffffffff8132f4f7)
Location: include/linux/page-flags.h:284
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
In mm/swap.c (ffffffff81224bfe)
Location: include/linux/page-flags.h:315
Inline: True
Inline callers:
  - mm/swap.c:mark_page_accessed
  - mm/swap.c:mark_page_accessed
```
```
In mm/migrate.c (ffffffff8129d7b0)
Location: include/linux/page-flags.h:315
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In mm/huge_memory.c (ffffffff812a3237)
Location: include/linux/page-flags.h:315
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/khugepaged.c (ffffffff812ac148)
Location: include/linux/page-flags.h:315
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In fs/proc/task_mmu.c (ffffffff81356f93)
Location: include/linux/page-flags.h:315
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
In mm/swap.c (ffffffff8123298e)
Location: include/linux/page-flags.h:315
Inline: True
Inline callers:
  - mm/swap.c:mark_page_accessed
  - mm/swap.c:mark_page_accessed
```
```
In mm/migrate.c (ffffffff812ad0ce)
Location: include/linux/page-flags.h:315
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In mm/huge_memory.c (ffffffff812b4737)
Location: include/linux/page-flags.h:315
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/khugepaged.c (ffffffff812bd958)
Location: include/linux/page-flags.h:315
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In fs/proc/task_mmu.c (ffffffff8136f56b)
Location: include/linux/page-flags.h:315
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
In mm/swap.c (ffffffff8125febb)
Location: include/linux/page-flags.h:323
Inline: True
Inline callers:
  - mm/swap.c:mark_page_accessed
```
```
In mm/migrate.c (ffffffff812e2c0e)
Location: include/linux/page-flags.h:323
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In mm/huge_memory.c (ffffffff812e9ce5)
Location: include/linux/page-flags.h:323
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/khugepaged.c (ffffffff812f30c8)
Location: include/linux/page-flags.h:323
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In fs/proc/task_mmu.c (ffffffff813b6c32)
Location: include/linux/page-flags.h:323
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
In mm/swap.c (ffffffff8126961b)
Location: include/linux/page-flags.h:331
Inline: True
Inline callers:
  - mm/swap.c:mark_page_accessed
```
```
In mm/migrate.c (ffffffff812ee03e)
Location: include/linux/page-flags.h:331
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In mm/huge_memory.c (ffffffff812f4ec5)
Location: include/linux/page-flags.h:331
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/khugepaged.c (ffffffff812fd703)
Location: include/linux/page-flags.h:331
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In fs/proc/task_mmu.c (ffffffff813c82c3)
Location: include/linux/page-flags.h:331
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
In mm/swap.c (ffffffff8126ea7d)
Location: include/linux/page-flags.h:331
Inline: True
Inline callers:
  - mm/swap.c:mark_page_accessed
```
```
In mm/migrate.c (ffffffff812f3b2e)
Location: include/linux/page-flags.h:331
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In mm/huge_memory.c (ffffffff812fb42f)
Location: include/linux/page-flags.h:331
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/khugepaged.c (ffffffff81304468)
Location: include/linux/page-flags.h:331
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In fs/proc/task_mmu.c (ffffffff813cf407)
Location: include/linux/page-flags.h:331
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
In mm/swap.c (ffffffff812abacd)
Location: include/linux/page-flags.h:345
Inline: True
Inline callers:
  - mm/swap.c:mark_page_accessed
```
```
In mm/migrate.c (ffffffff8133e4ce)
Location: include/linux/page-flags.h:345
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In mm/huge_memory.c (ffffffff8134525e)
Location: include/linux/page-flags.h:345
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/khugepaged.c (ffffffff8134e198)
Location: include/linux/page-flags.h:345
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In fs/proc/task_mmu.c (ffffffff814207dc)
Location: include/linux/page-flags.h:345
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_account
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
In mm/huge_memory.c (ffffffff813bb0f9)
Location: include/linux/page-flags.h:495
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/khugepaged.c (ffffffff813c7504)
Location: include/linux/page-flags.h:495
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In fs/proc/task_mmu.c (ffffffff81499eb8)
Location: include/linux/page-flags.h:495
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_account
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
In mm/huge_memory.c (ffffffff8143d6d7)
Location: include/linux/page-flags.h:474
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/khugepaged.c (ffffffff8144b4b1)
Location: include/linux/page-flags.h:474
Inline: True
Inline callers:
  - mm/khugepaged.c:hpage_collapse_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In fs/proc/task_mmu.c (ffffffff8152e0f3)
Location: include/linux/page-flags.h:474
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_account
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
In mm/huge_memory.c (ffffffff81472d6a)
Location: include/linux/page-flags.h:468
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/khugepaged.c (ffffffff8147f235)
Location: include/linux/page-flags.h:468
Inline: True
Inline callers:
  - mm/khugepaged.c:hpage_collapse_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In fs/proc/task_mmu.c (ffffffff815664c3)
Location: include/linux/page-flags.h:468
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_account
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff8159e520)
Location: include/linux/page-flags.h:470
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_account
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
In mm/swap.c (ffff8000102c2808)
Location: include/linux/page-flags.h:315
Inline: True
Inline callers:
  - mm/swap.c:mark_page_accessed
  - mm/swap.c:mark_page_accessed
```
```
In mm/migrate.c (ffff80001034f38c)
Location: include/linux/page-flags.h:315
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In mm/huge_memory.c (ffff800010355d04)
Location: include/linux/page-flags.h:315
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/khugepaged.c (ffff80001035ee2c)
Location: include/linux/page-flags.h:315
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In fs/proc/task_mmu.c (ffff800010438c7c)
Location: include/linux/page-flags.h:315
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_account
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
In mm/swap.c (c04eda38)
Location: include/linux/page-flags.h:315
Inline: True
Inline callers:
  - mm/swap.c:mark_page_accessed
  - mm/swap.c:mark_page_accessed
```
```
In mm/migrate.c (c055130c)
Location: include/linux/page-flags.h:315
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In fs/proc/task_mmu.c (c0600bcc)
Location: include/linux/page-flags.h:315
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
In mm/swap.c (c00000000037c874)
Location: include/linux/page-flags.h:315
Inline: True
Inline callers:
  - mm/swap.c:mark_page_accessed
  - mm/swap.c:mark_page_accessed
```
```
In mm/migrate.c (c000000000431790)
Location: include/linux/page-flags.h:315
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In mm/huge_memory.c (c00000000043c008)
Location: include/linux/page-flags.h:315
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/khugepaged.c (c000000000448110)
Location: include/linux/page-flags.h:315
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In fs/proc/task_mmu.c (c00000000054c4d0)
Location: include/linux/page-flags.h:315
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
In mm/swap.c (ffffffe0001e3bcc)
Location: include/linux/page-flags.h:315
Inline: True
Inline callers:
  - mm/swap.c:mark_page_accessed
  - mm/swap.c:mark_page_accessed
```
```
In mm/migrate.c (ffffffe00023e3ea)
Location: include/linux/page-flags.h:315
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In fs/proc/task_mmu.c (ffffffe0002d3280)
Location: include/linux/page-flags.h:315
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
In mm/swap.c (ffffffff8122afde)
Location: include/linux/page-flags.h:315
Inline: True
Inline callers:
  - mm/swap.c:mark_page_accessed
  - mm/swap.c:mark_page_accessed
```
```
In mm/migrate.c (ffffffff812a56ae)
Location: include/linux/page-flags.h:315
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In mm/huge_memory.c (ffffffff812acd17)
Location: include/linux/page-flags.h:315
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/khugepaged.c (ffffffff812b5f38)
Location: include/linux/page-flags.h:315
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In fs/proc/task_mmu.c (ffffffff81367b4b)
Location: include/linux/page-flags.h:315
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
In mm/swap.c (ffffffff8121e0ee)
Location: include/linux/page-flags.h:315
Inline: True
Inline callers:
  - mm/swap.c:mark_page_accessed
  - mm/swap.c:mark_page_accessed
```
```
In mm/migrate.c (ffffffff8129717e)
Location: include/linux/page-flags.h:315
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In mm/huge_memory.c (ffffffff8129dde2)
Location: include/linux/page-flags.h:315
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/khugepaged.c (ffffffff812a70fa)
Location: include/linux/page-flags.h:315
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In fs/proc/task_mmu.c (ffffffff813587eb)
Location: include/linux/page-flags.h:315
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
In mm/swap.c (ffffffff81228d7e)
Location: include/linux/page-flags.h:315
Inline: True
Inline callers:
  - mm/swap.c:mark_page_accessed
  - mm/swap.c:mark_page_accessed
```
```
In mm/migrate.c (ffffffff812a34be)
Location: include/linux/page-flags.h:315
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In mm/huge_memory.c (ffffffff812aab27)
Location: include/linux/page-flags.h:315
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/khugepaged.c (ffffffff812b3d48)
Location: include/linux/page-flags.h:315
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In fs/proc/task_mmu.c (ffffffff8136561b)
Location: include/linux/page-flags.h:315
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
In mm/swap.c (ffffffff8123811e)
Location: include/linux/page-flags.h:315
Inline: True
Inline callers:
  - mm/swap.c:mark_page_accessed
  - mm/swap.c:mark_page_accessed
```
```
In mm/migrate.c (ffffffff812b3cce)
Location: include/linux/page-flags.h:315
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In mm/huge_memory.c (ffffffff812bae77)
Location: include/linux/page-flags.h:315
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/khugepaged.c (ffffffff812c41c7)
Location: include/linux/page-flags.h:315
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In fs/proc/task_mmu.c (ffffffff81378cfb)
Location: include/linux/page-flags.h:315
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_account
```
</details>
</li>
</ul>

## Differences
