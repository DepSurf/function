# Function: <code>pte_young</code>

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
In arch/x86/mm/pgtable.c (0)
Location: arch/x86/include/asm/pgtable.h:105
Inline: True
```
```
In mm/memory.c (0)
Location: arch/x86/include/asm/pgtable.h:105
Inline: True
```
```
In mm/huge_memory.c (0)
Location: arch/x86/include/asm/pgtable.h:105
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: arch/x86/include/asm/pgtable.h:105
Inline: True
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
In arch/x86/mm/pgtable.c (0)
Location: arch/x86/include/asm/pgtable.h:116
Inline: True
```
```
In mm/memory.c (0)
Location: arch/x86/include/asm/pgtable.h:116
Inline: True
```
```
In mm/madvise.c (0)
Location: arch/x86/include/asm/pgtable.h:116
Inline: True
```
```
In mm/khugepaged.c (0)
Location: arch/x86/include/asm/pgtable.h:116
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: arch/x86/include/asm/pgtable.h:116
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
In arch/x86/mm/pgtable.c (0)
Location: arch/x86/include/asm/pgtable.h:116
Inline: True
```
```
In mm/memory.c (0)
Location: arch/x86/include/asm/pgtable.h:116
Inline: True
```
```
In mm/madvise.c (0)
Location: arch/x86/include/asm/pgtable.h:116
Inline: True
```
```
In mm/khugepaged.c (0)
Location: arch/x86/include/asm/pgtable.h:116
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: arch/x86/include/asm/pgtable.h:116
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
In arch/x86/mm/pgtable.c (0)
Location: arch/x86/include/asm/pgtable.h:128
Inline: True
```
```
In mm/memory.c (0)
Location: arch/x86/include/asm/pgtable.h:128
Inline: True
```
```
In mm/madvise.c (0)
Location: arch/x86/include/asm/pgtable.h:128
Inline: True
```
```
In mm/khugepaged.c (0)
Location: arch/x86/include/asm/pgtable.h:128
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: arch/x86/include/asm/pgtable.h:128
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
In arch/x86/mm/pgtable.c (ffffffff81079b25)
Location: arch/x86/include/asm/pgtable.h:138
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:ptep_clear_flush_young
```
```
In mm/memory.c (0)
Location: arch/x86/include/asm/pgtable.h:138
Inline: True
```
```
In mm/madvise.c (ffffffff812235b7)
Location: arch/x86/include/asm/pgtable.h:138
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/khugepaged.c (ffffffff81259869)
Location: arch/x86/include/asm/pgtable.h:138
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
```
```
In fs/proc/task_mmu.c (0)
Location: arch/x86/include/asm/pgtable.h:138
Inline: True
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
In arch/x86/mm/pgtable.c (ffffffff8107c6e5)
Location: arch/x86/include/asm/pgtable.h:138
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:ptep_clear_flush_young
```
```
In mm/memory.c (ffffffff8122bede)
Location: arch/x86/include/asm/pgtable.h:138
Inline: True
```
```
In mm/madvise.c (ffffffff812466c2)
Location: arch/x86/include/asm/pgtable.h:138
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/khugepaged.c (ffffffff8127d1d4)
Location: arch/x86/include/asm/pgtable.h:138
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/proc/task_mmu.c (ffffffff81319770)
Location: arch/x86/include/asm/pgtable.h:138
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
In arch/x86/mm/pgtable.c (ffffffff810830f5)
Location: arch/x86/include/asm/pgtable.h:140
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:ptep_clear_flush_young
```
```
In mm/memory.c (ffffffff8123f2fa)
Location: arch/x86/include/asm/pgtable.h:140
Inline: True
```
```
In mm/madvise.c (ffffffff8125aae5)
Location: arch/x86/include/asm/pgtable.h:140
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/khugepaged.c (ffffffff81291d4d)
Location: arch/x86/include/asm/pgtable.h:140
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/proc/task_mmu.c (ffffffff8133038d)
Location: arch/x86/include/asm/pgtable.h:140
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
In arch/x86/mm/pgtable.c (ffffffff81086d65)
Location: arch/x86/include/asm/pgtable.h:157
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:ptep_clear_flush_young
```
```
In mm/memory.c (ffffffff81250c37)
Location: arch/x86/include/asm/pgtable.h:157
Inline: True
```
```
In mm/madvise.c (ffffffff81275a7b)
Location: arch/x86/include/asm/pgtable.h:157
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/khugepaged.c (ffffffff812abfc6)
Location: arch/x86/include/asm/pgtable.h:157
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In fs/proc/task_mmu.c (ffffffff813581c0)
Location: arch/x86/include/asm/pgtable.h:157
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
In arch/x86/mm/pgtable.c (ffffffff81087a55)
Location: arch/x86/include/asm/pgtable.h:157
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:ptep_clear_flush_young
```
```
In mm/memory.c (ffffffff8125f217)
Location: arch/x86/include/asm/pgtable.h:157
Inline: True
```
```
In mm/madvise.c (ffffffff81284a4b)
Location: arch/x86/include/asm/pgtable.h:157
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/khugepaged.c (ffffffff812bd7d6)
Location: arch/x86/include/asm/pgtable.h:157
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In fs/proc/task_mmu.c (ffffffff813703f0)
Location: arch/x86/include/asm/pgtable.h:157
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
In arch/x86/mm/pgtable.c (ffffffff81089e95)
Location: arch/x86/include/asm/pgtable.h:159
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:ptep_clear_flush_young
```
```
In mm/memory.c (ffffffff8128f5ea)
Location: arch/x86/include/asm/pgtable.h:159
Inline: True
Inline callers:
  - mm/memory.c:zap_pte_range
```
```
In mm/madvise.c (ffffffff812b6c34)
Location: arch/x86/include/asm/pgtable.h:159
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/khugepaged.c (ffffffff812f2eea)
Location: arch/x86/include/asm/pgtable.h:159
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In fs/proc/task_mmu.c (ffffffff813b8291)
Location: arch/x86/include/asm/pgtable.h:159
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
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8106589e)
Location: arch/x86/include/asm/pgtable.h:158
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_test_and_clear_young_cb
```
```
In arch/x86/mm/pgtable.c (ffffffff8108a115)
Location: arch/x86/include/asm/pgtable.h:158
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:ptep_clear_flush_young
```
```
In mm/memory.c (ffffffff8129a0f7)
Location: arch/x86/include/asm/pgtable.h:158
Inline: True
Inline callers:
  - mm/memory.c:zap_pte_range
```
```
In mm/madvise.c (ffffffff812c2e02)
Location: arch/x86/include/asm/pgtable.h:158
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/khugepaged.c (ffffffff812fd534)
Location: arch/x86/include/asm/pgtable.h:158
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In fs/proc/task_mmu.c (ffffffff813c99f1)
Location: arch/x86/include/asm/pgtable.h:158
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
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81065f6e)
Location: arch/x86/include/asm/pgtable.h:158
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_test_and_clear_young_cb
```
```
In arch/x86/mm/pgtable.c (ffffffff8108ad75)
Location: arch/x86/include/asm/pgtable.h:158
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:ptep_clear_flush_young
```
```
In mm/memory.c (ffffffff8129f319)
Location: arch/x86/include/asm/pgtable.h:158
Inline: True
Inline callers:
  - mm/memory.c:zap_pte_range
```
```
In mm/madvise.c (ffffffff812c9c7b)
Location: arch/x86/include/asm/pgtable.h:158
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/khugepaged.c (ffffffff81304293)
Location: arch/x86/include/asm/pgtable.h:158
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In fs/proc/task_mmu.c (ffffffff813d0ade)
Location: arch/x86/include/asm/pgtable.h:158
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
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8107008e)
Location: arch/x86/include/asm/pgtable.h:129
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_test_and_clear_young_cb
```
```
In arch/x86/mm/pgtable.c (ffffffff8109a315)
Location: arch/x86/include/asm/pgtable.h:129
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:ptep_clear_flush_young
```
```
In mm/memory.c (ffffffff812e057e)
Location: arch/x86/include/asm/pgtable.h:129
Inline: True
Inline callers:
  - mm/memory.c:zap_pte_range
```
```
In mm/madvise.c (ffffffff8130ec9b)
Location: arch/x86/include/asm/pgtable.h:129
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/khugepaged.c (ffffffff8134dfc6)
Location: arch/x86/include/asm/pgtable.h:129
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In fs/proc/task_mmu.c (ffffffff81421381)
Location: arch/x86/include/asm/pgtable.h:129
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
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8107d9ad)
Location: arch/x86/include/asm/pgtable.h:132
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_test_and_clear_young_cb
```
```
In arch/x86/mm/pgtable.c (ffffffff810ad465)
Location: arch/x86/include/asm/pgtable.h:132
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:ptep_clear_flush_young
```
```
In mm/memory.c (ffffffff81340c60)
Location: arch/x86/include/asm/pgtable.h:132
Inline: True
Inline callers:
  - mm/memory.c:zap_pte_range
```
```
In mm/madvise.c (ffffffff81376d7e)
Location: arch/x86/include/asm/pgtable.h:132
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/khugepaged.c (ffffffff813c7216)
Location: arch/x86/include/asm/pgtable.h:132
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In fs/proc/task_mmu.c (ffffffff8149a4d3)
Location: arch/x86/include/asm/pgtable.h:132
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
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8108ef2d)
Location: arch/x86/include/asm/pgtable.h:132
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_test_and_clear_young_cb
```
```
In arch/x86/mm/pgtable.c (ffffffff810c7595)
Location: arch/x86/include/asm/pgtable.h:132
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:ptep_clear_flush_young
```
```
In mm/vmscan.c (ffffffff81387390)
Location: arch/x86/include/asm/pgtable.h:132
Inline: True
Inline callers:
  - mm/vmscan.c:lru_gen_look_around
  - mm/vmscan.c:walk_pte_range
```
```
In mm/memory.c (ffffffff813b8bff)
Location: arch/x86/include/asm/pgtable.h:132
Inline: True
Inline callers:
  - mm/memory.c:zap_pte_range
```
```
In mm/rmap.c (ffffffff813d952d)
Location: arch/x86/include/asm/pgtable.h:132
Inline: True
Inline callers:
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:folio_referenced_one
```
```
In mm/madvise.c (ffffffff813f43fe)
Location: arch/x86/include/asm/pgtable.h:132
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/migrate_device.c (ffffffff81438f29)
Location: arch/x86/include/asm/pgtable.h:132
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/khugepaged.c (ffffffff8144b0ef)
Location: arch/x86/include/asm/pgtable.h:132
Inline: True
Inline callers:
  - mm/khugepaged.c:hpage_collapse_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In fs/proc/task_mmu.c (ffffffff8152f4b7)
Location: arch/x86/include/asm/pgtable.h:132
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
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81091e1d)
Location: arch/x86/include/asm/pgtable.h:133
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_test_and_clear_young_cb
```
```
In arch/x86/mm/pgtable.c (ffffffff810cace5)
Location: arch/x86/include/asm/pgtable.h:133
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:ptep_clear_flush_young
```
```
In mm/vmscan.c (ffffffff813b78c4)
Location: arch/x86/include/asm/pgtable.h:133
Inline: True
Inline callers:
  - mm/vmscan.c:lru_gen_look_around
  - mm/vmscan.c:walk_pte_range
```
```
In mm/memory.c (ffffffff813ed83d)
Location: arch/x86/include/asm/pgtable.h:133
Inline: True
Inline callers:
  - mm/memory.c:zap_pte_range
```
```
In mm/rmap.c (ffffffff8140dc1c)
Location: arch/x86/include/asm/pgtable.h:133
Inline: True
Inline callers:
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:folio_referenced_one
```
```
In mm/madvise.c (ffffffff81427908)
Location: arch/x86/include/asm/pgtable.h:133
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/migrate_device.c (ffffffff8146f769)
Location: arch/x86/include/asm/pgtable.h:133
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/khugepaged.c (ffffffff8147edf6)
Location: arch/x86/include/asm/pgtable.h:133
Inline: True
Inline callers:
  - mm/khugepaged.c:hpage_collapse_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In fs/proc/task_mmu.c (ffffffff81567777)
Location: arch/x86/include/asm/pgtable.h:133
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
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81099459)
Location: arch/x86/include/asm/pgtable.h:139
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_test_and_clear_young_cb
```
```
In arch/x86/mm/pgtable.c (ffffffff810d3235)
Location: arch/x86/include/asm/pgtable.h:139
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:ptep_clear_flush_young
```
```
In mm/vmscan.c (ffffffff813e06f7)
Location: arch/x86/include/asm/pgtable.h:139
Inline: True
Inline callers:
  - mm/vmscan.c:lru_gen_look_around
  - mm/vmscan.c:walk_pte_range
```
```
In mm/memory.c (ffffffff81418e2f)
Location: arch/x86/include/asm/pgtable.h:139
Inline: True
Inline callers:
  - mm/memory.c:zap_pte_range
```
```
In mm/rmap.c (ffffffff8143a3a1)
Location: arch/x86/include/asm/pgtable.h:139
Inline: True
Inline callers:
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:folio_referenced_one
```
```
In mm/madvise.c (ffffffff814610e4)
Location: arch/x86/include/asm/pgtable.h:139
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/migrate_device.c (ffffffff8149e3ac)
Location: arch/x86/include/asm/pgtable.h:139
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/khugepaged.c (ffffffff814afa8c)
Location: arch/x86/include/asm/pgtable.h:139
Inline: True
Inline callers:
  - mm/khugepaged.c:hpage_collapse_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In fs/proc/task_mmu.c (ffffffff8159ffb6)
Location: arch/x86/include/asm/pgtable.h:139
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
In <code>arm64</code>: Absent ⚠️
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
In arch/powerpc/mm/book3s64/hash_utils.c (c00000000008dc60)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:485
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/hash_utils.c:update_mmu_cache
```
```
In arch/powerpc/xmon/xmon.c (c00000000010ae34)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:485
Inline: True
Inline callers:
  - arch/powerpc/xmon/xmon.c:format_pte
```
```
In arch/powerpc/kvm/book3s_64_vio_hv.c (c000000000118e7c)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:485
Inline: True
Inline callers:
  - arch/powerpc/kvm/book3s_64_vio_hv.c:kvmppc_rm_h_put_tce_indirect
```
```
In mm/memory.c (c0000000003beb70)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:485
Inline: True
Inline callers:
  - mm/memory.c:zap_pte_range
```
```
In mm/madvise.c (c0000000003f345c)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:485
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/huge_memory.c (c00000000043c024)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:485
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In mm/khugepaged.c (c0000000004480fc)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:485
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In fs/proc/task_mmu.c (c00000000054dc68)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:485
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_pte_range
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
In mm/memory.c (ffffffe0002076f8)
Location: arch/riscv/include/asm/pgtable.h:235
Inline: True
Inline callers:
  - mm/memory.c:unmap_page_range
```
```
In mm/rmap.c (ffffffe000213cfe)
Location: arch/riscv/include/asm/pgtable.h:235
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_referenced_one
```
```
In mm/madvise.c (ffffffe000220c8e)
Location: arch/riscv/include/asm/pgtable.h:235
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/page_idle.c (ffffffe000250790)
Location: arch/riscv/include/asm/pgtable.h:235
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_clear_pte_refs_one
```
```
In fs/proc/task_mmu.c (ffffffe0002d22d6)
Location: arch/riscv/include/asm/pgtable.h:235
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
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
In arch/x86/mm/pgtable.c (ffffffff81086a55)
Location: arch/x86/include/asm/pgtable.h:157
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:ptep_clear_flush_young
```
```
In mm/memory.c (ffffffff81257867)
Location: arch/x86/include/asm/pgtable.h:157
Inline: True
```
```
In mm/madvise.c (ffffffff8127d09b)
Location: arch/x86/include/asm/pgtable.h:157
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/khugepaged.c (ffffffff812b5db6)
Location: arch/x86/include/asm/pgtable.h:157
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In fs/proc/task_mmu.c (ffffffff813689d0)
Location: arch/x86/include/asm/pgtable.h:157
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
In arch/x86/mm/pgtable.c (ffffffff810756e5)
Location: arch/x86/include/asm/pgtable.h:157
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:ptep_clear_flush_young
```
```
In mm/memory.c (ffffffff8124a1ee)
Location: arch/x86/include/asm/pgtable.h:157
Inline: True
Inline callers:
  - mm/memory.c:zap_pte_range
```
```
In mm/madvise.c (ffffffff8126ef1c)
Location: arch/x86/include/asm/pgtable.h:157
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/khugepaged.c (ffffffff812a6f72)
Location: arch/x86/include/asm/pgtable.h:157
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In fs/proc/task_mmu.c (ffffffff81359c80)
Location: arch/x86/include/asm/pgtable.h:157
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
In arch/x86/mm/pgtable.c (ffffffff81086a05)
Location: arch/x86/include/asm/pgtable.h:157
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:ptep_clear_flush_young
```
```
In mm/memory.c (ffffffff81255607)
Location: arch/x86/include/asm/pgtable.h:157
Inline: True
```
```
In mm/madvise.c (ffffffff8127ae3b)
Location: arch/x86/include/asm/pgtable.h:157
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/khugepaged.c (ffffffff812b3bc6)
Location: arch/x86/include/asm/pgtable.h:157
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In fs/proc/task_mmu.c (ffffffff813664a0)
Location: arch/x86/include/asm/pgtable.h:157
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
In arch/x86/mm/pgtable.c (ffffffff81088b35)
Location: arch/x86/include/asm/pgtable.h:157
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:ptep_clear_flush_young
```
```
In mm/memory.c (ffffffff812650af)
Location: arch/x86/include/asm/pgtable.h:157
Inline: True
```
```
In mm/madvise.c (ffffffff8128aa14)
Location: arch/x86/include/asm/pgtable.h:157
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/khugepaged.c (ffffffff812c4009)
Location: arch/x86/include/asm/pgtable.h:157
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In fs/proc/task_mmu.c (ffffffff813797e0)
Location: arch/x86/include/asm/pgtable.h:157
Inline: True
```
</details>
</li>
</ul>

## Differences
