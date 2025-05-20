# Function: <code>pte_mkold</code>

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
In mm/memory.c (ffffffff811c12ab)
Location: arch/x86/include/asm/pgtable.h:203
Inline: True
Inline callers:
  - mm/memory.c:copy_page_range
```
```
In mm/swapfile.c (0)
Location: arch/x86/include/asm/pgtable.h:203
Inline: True
```
```
In mm/migrate.c (ffffffff811f0d55)
Location: arch/x86/include/asm/pgtable.h:203
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff811f76c6)
Location: arch/x86/include/asm/pgtable.h:203
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
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
In mm/memory.c (ffffffff811dcd01)
Location: arch/x86/include/asm/pgtable.h:217
Inline: True
Inline callers:
  - mm/memory.c:copy_page_range
```
```
In mm/madvise.c (0)
Location: arch/x86/include/asm/pgtable.h:217
Inline: True
```
```
In mm/swapfile.c (ffffffff811f2473)
Location: arch/x86/include/asm/pgtable.h:217
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
```
```
In mm/migrate.c (ffffffff8120ffbf)
Location: arch/x86/include/asm/pgtable.h:217
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812163b5)
Location: arch/x86/include/asm/pgtable.h:217
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
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
In mm/memory.c (ffffffff811ec7f9)
Location: arch/x86/include/asm/pgtable.h:217
Inline: True
Inline callers:
  - mm/memory.c:copy_page_range
```
```
In mm/madvise.c (0)
Location: arch/x86/include/asm/pgtable.h:217
Inline: True
```
```
In mm/swapfile.c (ffffffff81202e6a)
Location: arch/x86/include/asm/pgtable.h:217
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
```
```
In mm/migrate.c (ffffffff812220e7)
Location: arch/x86/include/asm/pgtable.h:217
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff81228966)
Location: arch/x86/include/asm/pgtable.h:217
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
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
In mm/memory.c (ffffffff811f7739)
Location: arch/x86/include/asm/pgtable.h:274
Inline: True
Inline callers:
  - mm/memory.c:copy_page_range
```
```
In mm/madvise.c (0)
Location: arch/x86/include/asm/pgtable.h:274
Inline: True
```
```
In mm/swapfile.c (ffffffff8120def3)
Location: arch/x86/include/asm/pgtable.h:274
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
```
```
In mm/migrate.c (ffffffff8122df56)
Location: arch/x86/include/asm/pgtable.h:274
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff81231fde)
Location: arch/x86/include/asm/pgtable.h:274
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
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
In mm/memory.c (ffffffff8120a52b)
Location: arch/x86/include/asm/pgtable.h:289
Inline: True
Inline callers:
  - mm/memory.c:copy_pte_range
```
```
In mm/madvise.c (0)
Location: arch/x86/include/asm/pgtable.h:289
Inline: True
```
```
In mm/swapfile.c (ffffffff81229166)
Location: arch/x86/include/asm/pgtable.h:289
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
```
```
In mm/migrate.c (ffffffff81249c93)
Location: arch/x86/include/asm/pgtable.h:289
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff81252d5f)
Location: arch/x86/include/asm/pgtable.h:289
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
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
In mm/memory.c (ffffffff8122b38d)
Location: arch/x86/include/asm/pgtable.h:299
Inline: True
```
```
In mm/madvise.c (0)
Location: arch/x86/include/asm/pgtable.h:299
Inline: True
```
```
In mm/swapfile.c (ffffffff8124a473)
Location: arch/x86/include/asm/pgtable.h:299
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
```
```
In mm/migrate.c (ffffffff8126d4d6)
Location: arch/x86/include/asm/pgtable.h:299
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (0)
Location: arch/x86/include/asm/pgtable.h:299
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
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
In mm/memory.c (ffffffff8123e747)
Location: arch/x86/include/asm/pgtable.h:301
Inline: True
```
```
In mm/madvise.c (0)
Location: arch/x86/include/asm/pgtable.h:301
Inline: True
```
```
In mm/swapfile.c (ffffffff8125ead7)
Location: arch/x86/include/asm/pgtable.h:301
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
```
```
In mm/migrate.c (ffffffff81281bc6)
Location: arch/x86/include/asm/pgtable.h:301
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff81288a22)
Location: arch/x86/include/asm/pgtable.h:301
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
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
In mm/memory.c (ffffffff812505a0)
Location: arch/x86/include/asm/pgtable.h:318
Inline: True
```
```
In mm/madvise.c (0)
Location: arch/x86/include/asm/pgtable.h:318
Inline: True
```
```
In mm/swapfile.c (ffffffff81279803)
Location: arch/x86/include/asm/pgtable.h:318
Inline: True
```
```
In mm/migrate.c (ffffffff8129dcd2)
Location: arch/x86/include/asm/pgtable.h:318
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812a3668)
Location: arch/x86/include/asm/pgtable.h:318
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
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
In mm/memory.c (ffffffff8125eb50)
Location: arch/x86/include/asm/pgtable.h:318
Inline: True
```
```
In mm/madvise.c (ffffffff8128516a)
Location: arch/x86/include/asm/pgtable.h:318
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swapfile.c (ffffffff812892e3)
Location: arch/x86/include/asm/pgtable.h:318
Inline: True
```
```
In mm/migrate.c (ffffffff812ad582)
Location: arch/x86/include/asm/pgtable.h:318
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812b4b68)
Location: arch/x86/include/asm/pgtable.h:318
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
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
In mm/memory.c (ffffffff8128ec53)
Location: arch/x86/include/asm/pgtable.h:340
Inline: True
Inline callers:
  - mm/memory.c:copy_one_pte
```
```
In mm/madvise.c (ffffffff812b73c4)
Location: arch/x86/include/asm/pgtable.h:340
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swapfile.c (ffffffff812bbce2)
Location: arch/x86/include/asm/pgtable.h:340
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
```
```
In mm/migrate.c (ffffffff812e28e2)
Location: arch/x86/include/asm/pgtable.h:340
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812ea10e)
Location: arch/x86/include/asm/pgtable.h:340
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
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff810658b0)
Location: arch/x86/include/asm/pgtable.h:339
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_test_and_clear_young_cb
```
```
In mm/memory.c (ffffffff81299a47)
Location: arch/x86/include/asm/pgtable.h:339
Inline: True
Inline callers:
  - mm/memory.c:copy_pte_range
```
```
In mm/madvise.c (ffffffff812c2311)
Location: arch/x86/include/asm/pgtable.h:339
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swapfile.c (ffffffff812c7792)
Location: arch/x86/include/asm/pgtable.h:339
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
```
```
In mm/migrate.c (ffffffff812edd14)
Location: arch/x86/include/asm/pgtable.h:339
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812f52e4)
Location: arch/x86/include/asm/pgtable.h:339
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
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81065f80)
Location: arch/x86/include/asm/pgtable.h:339
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_test_and_clear_young_cb
```
```
In mm/memory.c (ffffffff8129ecd1)
Location: arch/x86/include/asm/pgtable.h:339
Inline: True
Inline callers:
  - mm/memory.c:copy_pte_range
```
```
In mm/madvise.c (ffffffff812c91a9)
Location: arch/x86/include/asm/pgtable.h:339
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swapfile.c (ffffffff812ce10a)
Location: arch/x86/include/asm/pgtable.h:339
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
```
```
In mm/migrate.c (ffffffff812f3ec3)
Location: arch/x86/include/asm/pgtable.h:339
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812fb82e)
Location: arch/x86/include/asm/pgtable.h:339
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
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff810700a0)
Location: arch/x86/include/asm/pgtable.h:310
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_test_and_clear_young_cb
```
```
In mm/memory.c (ffffffff812dff1c)
Location: arch/x86/include/asm/pgtable.h:310
Inline: True
Inline callers:
  - mm/memory.c:copy_pte_range
  - mm/memory.c:restore_exclusive_pte
```
```
In mm/madvise.c (ffffffff8130e1d4)
Location: arch/x86/include/asm/pgtable.h:310
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swapfile.c (ffffffff8131358a)
Location: arch/x86/include/asm/pgtable.h:310
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
```
```
In mm/migrate.c (ffffffff8133e8f4)
Location: arch/x86/include/asm/pgtable.h:310
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff81345669)
Location: arch/x86/include/asm/pgtable.h:310
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
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
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8107d9d4)
Location: arch/x86/include/asm/pgtable.h:313
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_test_and_clear_young_cb
```
```
In mm/memory.c (ffffffff81340248)
Location: arch/x86/include/asm/pgtable.h:313
Inline: True
Inline callers:
  - mm/memory.c:copy_present_pte
  - mm/memory.c:restore_exclusive_pte
```
```
In mm/madvise.c (ffffffff813779d7)
Location: arch/x86/include/asm/pgtable.h:313
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swapfile.c (ffffffff8137ea6a)
Location: arch/x86/include/asm/pgtable.h:313
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
```
```
In mm/migrate.c (ffffffff813b19d5)
Location: arch/x86/include/asm/pgtable.h:313
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff813bb650)
Location: arch/x86/include/asm/pgtable.h:313
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
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
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8108ef54)
Location: arch/x86/include/asm/pgtable.h:330
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_test_and_clear_young_cb
```
```
In mm/memory.c (ffffffff813b81d8)
Location: arch/x86/include/asm/pgtable.h:330
Inline: True
Inline callers:
  - mm/memory.c:copy_present_pte
  - mm/memory.c:restore_exclusive_pte
```
```
In mm/madvise.c (ffffffff813f4e91)
Location: arch/x86/include/asm/pgtable.h:330
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swapfile.c (ffffffff813fd413)
Location: arch/x86/include/asm/pgtable.h:330
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
```
```
In mm/migrate.c (ffffffff814324c4)
Location: arch/x86/include/asm/pgtable.h:330
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (0)
Location: arch/x86/include/asm/pgtable.h:330
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
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
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81091e44)
Location: arch/x86/include/asm/pgtable.h:336
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_test_and_clear_young_cb
```
```
In mm/memory.c (ffffffff813ecfa5)
Location: arch/x86/include/asm/pgtable.h:336
Inline: True
Inline callers:
  - mm/memory.c:copy_present_pte
  - mm/memory.c:restore_exclusive_pte
```
```
In mm/madvise.c (ffffffff81428054)
Location: arch/x86/include/asm/pgtable.h:336
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swapfile.c (ffffffff814306f0)
Location: arch/x86/include/asm/pgtable.h:336
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
```
```
In mm/migrate.c (ffffffff81467c34)
Location: arch/x86/include/asm/pgtable.h:336
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (0)
Location: arch/x86/include/asm/pgtable.h:336
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
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
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81099474)
Location: arch/x86/include/asm/pgtable.h:426
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_test_and_clear_young_cb
```
```
In mm/memory.c (ffffffff81418506)
Location: arch/x86/include/asm/pgtable.h:426
Inline: True
Inline callers:
  - mm/memory.c:copy_present_pte
  - mm/memory.c:restore_exclusive_pte
```
```
In mm/madvise.c (ffffffff814616ba)
Location: arch/x86/include/asm/pgtable.h:426
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swapfile.c (ffffffff814690a7)
Location: arch/x86/include/asm/pgtable.h:426
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
```
```
In mm/migrate.c (ffffffff81497907)
Location: arch/x86/include/asm/pgtable.h:426
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff814a1865)
Location: arch/x86/include/asm/pgtable.h:426
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
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
In virt/kvm/arm/mmu.c (ffff8000100ca3cc)
Location: arch/arm64/include/asm/pgtable.h:170
Inline: True
Inline callers:
  - virt/kvm/arm/mmu.c:kvm_age_hva_handler
  - virt/kvm/arm/mmu.c:kvm_age_hva_handler
  - virt/kvm/arm/mmu.c:kvm_age_hva_handler
```
```
In mm/memory.c (ffff8000102f64c4)
Location: arch/arm64/include/asm/pgtable.h:170
Inline: True
Inline callers:
  - mm/memory.c:copy_pte_range
```
```
In mm/pgtable-generic.c (ffff8000103080c0)
Location: arch/arm64/include/asm/pgtable.h:170
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmdp_clear_flush_young
```
```
In mm/rmap.c (ffff800010309d34)
Location: arch/arm64/include/asm/pgtable.h:170
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_referenced_one
```
```
In mm/madvise.c (ffff80001031f96c)
Location: arch/arm64/include/asm/pgtable.h:170
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swapfile.c (ffff80001032612c)
Location: arch/arm64/include/asm/pgtable.h:170
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/migrate.c (ffff80001034efc8)
Location: arch/arm64/include/asm/pgtable.h:170
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffff800010355f20)
Location: arch/arm64/include/asm/pgtable.h:170
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/page_idle.c (ffff8000103795e0)
Location: arch/arm64/include/asm/pgtable.h:170
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_clear_pte_refs_one
  - mm/page_idle.c:page_idle_clear_pte_refs_one
```
```
In fs/proc/task_mmu.c (ffff80001043aa18)
Location: arch/arm64/include/asm/pgtable.h:170
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
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
In mm/memory.c (c0518628)
Location: arch/arm/include/asm/pgtable.h:301
Inline: True
Inline callers:
  - mm/memory.c:copy_pte_range
```
```
In mm/pgtable-generic.c (c0525554)
Location: arch/arm/include/asm/pgtable.h:301
Inline: True
Inline callers:
  - mm/pgtable-generic.c:ptep_clear_flush_young
```
```
In mm/madvise.c (c0537c4c)
Location: arch/arm/include/asm/pgtable.h:301
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swapfile.c (c053d970)
Location: arch/arm/include/asm/pgtable.h:301
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
```
```
In mm/migrate.c (c0551730)
Location: arch/arm/include/asm/pgtable.h:301
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/page_idle.c (c0564494)
Location: arch/arm/include/asm/pgtable.h:301
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_clear_pte_refs_one
```
```
In fs/proc/task_mmu.c (c06004a4)
Location: arch/arm/include/asm/pgtable.h:301
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
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
In mm/memory.c (c0000000003bdf38)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:640
Inline: True
Inline callers:
  - mm/memory.c:copy_pte_range
```
```
In mm/madvise.c (c0000000003f485c)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:640
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swapfile.c (c0000000003fc6ac)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:640
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/migrate.c (c0000000004314e0)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:640
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (c00000000044442c)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:640
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:copy_huge_pmd
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
In mm/memory.c (ffffffe000209e72)
Location: arch/riscv/include/asm/pgtable.h:276
Inline: True
Inline callers:
  - mm/memory.c:copy_page_range
```
```
In mm/madvise.c (ffffffe000220c9a)
Location: arch/riscv/include/asm/pgtable.h:276
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swapfile.c (ffffffe000226462)
Location: arch/riscv/include/asm/pgtable.h:276
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/migrate.c (ffffffe00023e286)
Location: arch/riscv/include/asm/pgtable.h:276
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
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
In mm/memory.c (ffffffff812571a0)
Location: arch/x86/include/asm/pgtable.h:318
Inline: True
```
```
In mm/madvise.c (ffffffff8127d7ba)
Location: arch/x86/include/asm/pgtable.h:318
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swapfile.c (ffffffff812818c3)
Location: arch/x86/include/asm/pgtable.h:318
Inline: True
```
```
In mm/migrate.c (ffffffff812a5b62)
Location: arch/x86/include/asm/pgtable.h:318
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812ad148)
Location: arch/x86/include/asm/pgtable.h:318
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
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
In mm/memory.c (ffffffff81249a8e)
Location: arch/x86/include/asm/pgtable.h:318
Inline: True
Inline callers:
  - mm/memory.c:copy_pte_range
```
```
In mm/madvise.c (ffffffff8126f618)
Location: arch/x86/include/asm/pgtable.h:318
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swapfile.c (ffffffff81275055)
Location: arch/x86/include/asm/pgtable.h:318
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/migrate.c (ffffffff81297633)
Location: arch/x86/include/asm/pgtable.h:318
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff8129e154)
Location: arch/x86/include/asm/pgtable.h:318
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
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
In mm/memory.c (ffffffff81254f40)
Location: arch/x86/include/asm/pgtable.h:318
Inline: True
```
```
In mm/madvise.c (ffffffff8127b55a)
Location: arch/x86/include/asm/pgtable.h:318
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swapfile.c (ffffffff8127f6d3)
Location: arch/x86/include/asm/pgtable.h:318
Inline: True
```
```
In mm/migrate.c (ffffffff812a3972)
Location: arch/x86/include/asm/pgtable.h:318
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812aaf58)
Location: arch/x86/include/asm/pgtable.h:318
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
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
In mm/memory.c (ffffffff812649fc)
Location: arch/x86/include/asm/pgtable.h:318
Inline: True
```
```
In mm/madvise.c (ffffffff8128b125)
Location: arch/x86/include/asm/pgtable.h:318
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swapfile.c (ffffffff8128f3a6)
Location: arch/x86/include/asm/pgtable.h:318
Inline: True
```
```
In mm/migrate.c (ffffffff812b4182)
Location: arch/x86/include/asm/pgtable.h:318
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812bb2a8)
Location: arch/x86/include/asm/pgtable.h:318
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
</details>
</li>
</ul>

## Differences
